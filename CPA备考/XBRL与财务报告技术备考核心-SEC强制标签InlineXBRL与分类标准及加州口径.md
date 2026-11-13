# XBRL 与财务报告技术备考核心：SEC 强制标签、Inline XBRL 与分类标准及加州口径

> 个人学习笔记，不构成税务建议。规则以 SEC Regulation S-T 与 Regulation S-K 现行文本为准。加州口径为学习整理（证据等级 B）。

选题说明：经 ls／grep 实查「XBRL」全仓零命中、无本体专篇。与仓内《ISC 信息系统与控制深挖》以指针分工：ISC 篇管信息系统与控制的考试全景，本篇只管财务报告一侧的 XBRL 提交技术——强制从哪来、谁要交、错了谁负责、审计师站在哪。

## 一、先定位：XBRL 不是新报表，是给报表装上机器可读的标签

### 中文

XBRL 是 eXtensible Business Reporting Language（可扩展商业报告语言）：报表上的每个数字不再只是一个印在页面上的数，而是带上一个标准标签——这是什么科目、属于哪个期间、单位是什么、正负号怎么读。机器拿到标签就能直接比对、汇总和筛查，不必再靠人眼抄数。先分清三层：分类标准（taxonomy）是标签词典，规定每个概念叫什么、怎么算、跟谁勾稽；实例文档（instance）是某家公司某一期贴好标签的报表数据；扩展（extension）是词典里没有现成标签时公司自造的标签，必须锚定到最接近的标准概念，不能拿扩展藏数字。Inline XBRL（内嵌式，常写作 iXBRL）再进一步：把标签直接嵌进 HTML 申报文件本身，一份文件人能读、机器也能读，不再像早期那样正文一份、XBRL 附件另一份、两边对不上还不知道错在哪。考试爱考的认知只有一句：XBRL 改的是数据的格式与可核查性，不改确认与计量——数字本身对不对，仍由会计准则说了算。

### English

XBRL — eXtensible Business Reporting Language — turns every number in a filing into a tagged fact: what the item is, which period it belongs to, its unit, and its sign. Keep three layers apart: the taxonomy is the dictionary of standard tags; the instance document is one filer's tagged data for one period; extensions are filer-created tags for concepts the dictionary lacks, and they must anchor to the closest standard concept rather than hide a number. Inline XBRL (iXBRL) embeds the tags inside the HTML filing itself, so one document serves both human readers and machines, ending the old two-file problem of a body and a separate XBRL exhibit that could silently disagree. The exam point is simple: XBRL changes the format and checkability of the data, never recognition or measurement — the numbers themselves still answer to GAAP.

### Español (初译待校)

XBRL (eXtensible Business Reporting Language) convierte cada cifra de un informe en un dato etiquetado: qué partida es, a qué período pertenece, su unidad y su signo. Hay que distinguir tres capas: la taxonomía es el diccionario de etiquetas estándar; el documento de instancia es el dato etiquetado de una empresa en un período; las extensiones son etiquetas creadas por la propia empresa para conceptos que el diccionario no tiene, y deben anclarse al concepto estándar más cercano. Inline XBRL (iXBRL) incrusta las etiquetas dentro del propio archivo HTML, de modo que un solo documento sirve a lectores humanos y a máquinas. La idea de examen es una sola: XBRL cambia el formato y la verificabilidad del dato, no el reconocimiento ni la medición, que siguen rigiéndose por los principios contables.

### 한국어 (初译待校)

XBRL(eXtensible Business Reporting Language)은 보고서의 모든 숫자를 태그가 붙은 사실로 바꿉니다. 어떤 항목인지, 어느 기간인지, 단위와 부호가 무엇인지를 기계가 바로 읽습니다. 세 층을 구분하십시오. 분류체계(taxonomy)는 표준 태그의 사전이고, 인스턴스 문서는 한 회사의 한 기간 태그 데이터이며, 확장(extension)은 사전에 없는 개념에 회사가 만든 태그로 가장 가까운 표준 개념에 연결해야 합니다. Inline XBRL(iXBRL)은 태그를 HTML 제출 파일 자체에 넣어 사람과 기계가 같은 문서를 읽게 합니다. 시험 포인트는 하나입니다. XBRL은 데이터의 형식과 검증 가능성을 바꿀 뿐, 인식과 측정은 여전히 회계기준이 정합니다.

### Tiếng Việt (初译待校)

XBRL (eXtensible Business Reporting Language) biến mỗi con số trong báo cáo thành một dữ kiện có gắn thẻ: đó là khoản mục gì, thuộc kỳ nào, đơn vị gì, dấu ra sao, để máy đọc và đối chiếu trực tiếp. Cần phân biệt ba lớp: taxonomy là từ điển thẻ chuẩn; tài liệu instance là dữ liệu đã gắn thẻ của một công ty trong một kỳ; extension là thẻ do công ty tự tạo cho khái niệm từ điển chưa có, và phải neo vào khái niệm chuẩn gần nhất. Inline XBRL (iXBRL) nhúng thẻ ngay trong tệp HTML nộp, một tài liệu cho cả người và máy cùng đọc. Điểm thi chỉ một câu: XBRL thay đổi định dạng và khả năng kiểm chứng của dữ liệu, không thay đổi ghi nhận hay đo lường, vốn vẫn do chuẩn mực kế toán quyết định.

### हिन्दी (初译待校)

XBRL (eXtensible Business Reporting Language) रिपोर्ट की हर संख्या को टैग-युक्त तथ्य बना देता है: यह कौन-सी मद है, किस अवधि की है, इकाई क्या है और चिह्न क्या है — मशीन इसे सीधे पढ़ और मिला सकती है। तीन परतें अलग रखें: taxonomy मानक टैगों का शब्दकोश है; instance document किसी एक कंपनी के एक अवधि के टैग किए डेटा हैं; extension वे टैग हैं जो कंपनी उन अवधारणाओं के लिए बनाती है जो शब्दकोश में नहीं हैं, और उन्हें निकटतम मानक अवधारणा से जोड़ना ज़रूरी है। Inline XBRL (iXBRL) टैग को HTML फ़ाइल के भीतर ही रखता है, ताकि एक ही दस्तावेज़ मनुष्य और मशीन दोनों पढ़ सकें। परीक्षा-बिंदु एक ही है: XBRL डेटा का प्रारूप और जाँच-योग्यता बदलता है, मान्यता या मापन नहीं — वे लेखा सिद्धांतों से ही तय होते हैं।

## 二、强制从哪来：Regulation S-T Rule 405、Regulation S-K 与 EDGAR

### 中文

强制的地基在 Regulation S-T 的 Rule 405（17 CFR 232.405）：它规定互动数据（interactive data）必须按什么格式、用什么分类标准提交；Regulation S-K 的 Item 601(b)(101) 则把互动数据文件列为定期报告与注册说明书的附件——标签不是自愿装饰，是申报文件的一部分。提交走 EDGAR 系统，具体校验规则写在 EDGAR Filer Manual 里：格式不对、标签用错、校验不过，轻则被系统提示退回修正，重则申报不完整。标签词典这一头，用美国公认会计原则（US GAAP）编报的公司用 US GAAP Financial Reporting Taxonomy，由财务会计基金会一侧的 FASB 维护与更新；用 IFRS 编报的外国私人发行人用 IFRS Taxonomy。公司可以建扩展标签，但扩展要锚定标准概念，SEC 工作人员与市场数据质量组织（如 XBRL US 的数据质量委员会规则）长期盯的正是扩展滥用、符号用反、比例缩放错误这类把机器读数带偏的毛病。

### English

The mandate rests on Rule 405 of Regulation S-T (17 CFR 232.405), which prescribes the format and taxonomy for interactive data, while Item 601(b)(101) of Regulation S-K makes the interactive data file an exhibit to periodic reports and registration statements — tagging is part of the filing, not decoration. Filings go through EDGAR, and the EDGAR Filer Manual carries the operative validation rules: wrong formats and wrong tags draw system errors and, at worst, an incomplete filing. On the dictionary side, U.S. GAAP filers use the US GAAP Financial Reporting Taxonomy, maintained by the FASB under the Financial Accounting Foundation, and IFRS foreign private issuers use the IFRS Taxonomy. Extensions are permitted but must anchor to standard concepts; SEC staff and market data-quality efforts such as the XBRL US Data Quality Committee rules have long targeted extension abuse, sign errors, and scaling errors that quietly corrupt machine-read data.

### Español (初译待校)

El mandato descansa en la Rule 405 del Regulation S-T (17 CFR 232.405), que prescribe el formato y la taxonomía de los datos interactivos, mientras el Item 601(b)(101) del Regulation S-K convierte el archivo de datos interactivos en anexo de los informes periódicos y de los folletos de registro: etiquetar es parte de la presentación. Todo pasa por EDGAR y el EDGAR Filer Manual contiene las reglas de validación operativas. Del lado del diccionario, quien informa bajo US GAAP usa la US GAAP Financial Reporting Taxonomy, mantenida por el FASB dentro de la Financial Accounting Foundation, y los emisores privados extranjeros bajo IFRS usan la IFRS Taxonomy. Las extensiones se permiten, pero deben anclarse a conceptos estándar; el personal de la SEC y las reglas del Data Quality Committee de XBRL US vigilan desde hace años el abuso de extensiones, los errores de signo y los errores de escala.

### 한국어 (初译待校)

강제의 근거는 Regulation S-T의 Rule 405(17 CFR 232.405)입니다. 대화형 데이터의 형식과 분류체계를 정하고, Regulation S-K의 Item 601(b)(101)은 대화형 데이터 파일을 정기보고서와 등록신고서의 첨부로 만듭니다. 태그는 장식이 아니라 제출의 일부입니다. 제출은 EDGAR로 이뤄지고 실제 검증 규칙은 EDGAR Filer Manual에 있습니다. 사전 쪽에서는 US GAAP 보고기업이 FASB(재무회계재단 산하)가 유지하는 US GAAP Financial Reporting Taxonomy를 쓰고, IFRS 외국 민간 발행인은 IFRS Taxonomy를 씁니다. 확장은 허용되지만 표준 개념에 연결해야 하며, SEC 직원과 XBRL US 데이터 품질 위원회 규칙은 확장 남용, 부호 오류, 배율 오류를 오랫동안 주시해 왔습니다.

### Tiếng Việt (初译待校)

Căn cứ bắt buộc nằm ở Rule 405 của Regulation S-T (17 CFR 232.405), quy định định dạng và taxonomy cho dữ liệu tương tác, còn Item 601(b)(101) của Regulation S-K biến tệp dữ liệu tương tác thành phụ lục của báo cáo định kỳ và bản cáo bạch đăng ký: gắn thẻ là một phần của hồ sơ nộp. Hồ sơ đi qua EDGAR và EDGAR Filer Manual chứa các quy tắc kiểm hợp lệ thực tế. Về phía từ điển, đơn vị báo cáo theo US GAAP dùng US GAAP Financial Reporting Taxonomy do FASB thuộc Financial Accounting Foundation duy trì, còn nhà phát hành tư nhân nước ngoài theo IFRS dùng IFRS Taxonomy. Extension được phép nhưng phải neo vào khái niệm chuẩn; nhân viên SEC và các quy tắc của Data Quality Committee thuộc XBRL US từ lâu đã theo dõi lạm dụng extension, lỗi dấu và lỗi thang đo.

### हिन्दी (初译待校)

अनिवार्यता की नींव Regulation S-T की Rule 405 (17 CFR 232.405) है, जो interactive data का प्रारूप और taxonomy तय करती है, जबकि Regulation S-K का Item 601(b)(101) interactive data file को आवधिक रिपोर्टों और पंजीकरण विवरणों का exhibit बनाता है — टैगिंग सजावट नहीं, फ़ाइलिंग का हिस्सा है। फ़ाइलिंग EDGAR से जाती है और वास्तविक validation नियम EDGAR Filer Manual में हैं। शब्दकोश पक्ष पर, US GAAP रिपोर्टर FASB (Financial Accounting Foundation के अधीन) द्वारा रखरखाव की गई US GAAP Financial Reporting Taxonomy का उपयोग करते हैं, और IFRS वाले विदेशी निजी जारीकर्ता IFRS Taxonomy का। Extension की अनुमति है, पर उन्हें मानक अवधारणाओं से जोड़ना होगा; SEC स्टाफ़ और XBRL US Data Quality Committee के नियम लंबे समय से extension के दुरुपयोग, चिह्न-त्रुटियों और scale त्रुटियों पर नज़र रखते हैं।

## 三、覆盖对象与两轮分阶段实施：2009 年先贴标签，2019 年起改内嵌

### 中文

覆盖对象跟着「谁本来就要交 XBRL 财务信息」走：所有须提交 XBRL 财务报表信息的经营性公司都在内，包括小型报告公司（smaller reporting companies）、新兴成长公司与用 IFRS 编报的外国私人发行人——规模小不豁免，只是排队靠后。实施分两轮。第一轮是 2009 年的原始 XBRL 规则（独立附件时代）：公众持股市值超过 50 亿美元的大型加速申报人自财务期间结束于 2009 年 6 月 15 日或之后的期间先行，其余大型加速申报人自 2010 年 6 月 15 日或之后结束的期间跟上，其他全部申报人（含小型报告公司）自 2011 年 6 月 15 日或之后结束的期间全面跟上；附注的标签粒度也分步走，先整块标签、再逐项明细标签。第二轮是 2018 年通过的 Inline XBRL 规则（2018 年 6 月 28 日通过、同年 9 月 17 日生效），把独立附件改成内嵌一份文件，并同步取消把互动数据贴到公司网站上的旧要求：大型加速申报人自 2019 年 6 月 15 日或之后结束的期间、加速申报人自 2020 年 6 月 15 日或之后结束的期间、其余全部申报人自 2021 年 6 月 15 日或之后结束的期间依次切换。所以今天的口径是：Inline XBRL 已对全部覆盖对象适用，考试里再看到「小型公司还可以用旧式附件慢慢来」的选项，可以直接排除。

### English

Coverage follows whoever already owed XBRL financial statement information: all operating companies in that population are in, including smaller reporting companies, emerging growth companies, and IFRS foreign private issuers — small size defers a filer, it does not exempt it. Implementation came in two waves. The first was the original 2009 XBRL rule, in the separate-exhibit era: large accelerated filers with public float above $5 billion went first, for fiscal periods ending on or after June 15, 2009; other large accelerated filers followed for periods ending on or after June 15, 2010; and all other filers, smaller reporting companies included, for periods ending on or after June 15, 2011, with footnote tagging itself phased from block tagging to detailed tagging. The second wave was the Inline XBRL rule adopted June 28, 2018 and effective September 17, 2018, which replaced the separate exhibit with a single embedded document and eliminated the old requirement to post interactive data on the company website: large accelerated filers for periods ending on or after June 15, 2019, accelerated filers for periods ending on or after June 15, 2020, and all other filers for periods ending on or after June 15, 2021. Today Inline XBRL therefore applies across the covered population, and any exam option suggesting smaller companies may still linger on the old exhibit format can be eliminated on sight.

### Español (初译待校)

La cobertura sigue a quien ya debía entregar información financiera en XBRL: entran todas las compañías operativas de ese universo, incluidas las smaller reporting companies, las emerging growth companies y los emisores privados extranjeros bajo IFRS; ser pequeño retrasa, no exime. La implantación tuvo dos oleadas. La primera fue la regla XBRL original de 2009, en la era del anexo separado: los large accelerated filers con flotación pública superior a 5.000 millones de dólares empezaron con los períodos terminados el 15 de junio de 2009 o después; los demás large accelerated filers, con los terminados el 15 de junio de 2010 o después; y todos los demás, incluidas las pequeñas, con los terminados el 15 de junio de 2011 o después, con el etiquetado de notas pasando de bloque a detalle. La segunda fue la regla Inline XBRL, adoptada el 28 de junio de 2018 y vigente desde el 17 de septiembre de 2018, que sustituyó el anexo separado por un único documento incrustado y eliminó la antigua obligación de publicar los datos interactivos en el sitio web: large accelerated filers desde los períodos terminados el 15 de junio de 2019 o después, accelerated filers desde el 15 de junio de 2020 o después, y todos los demás desde el 15 de junio de 2021 o después. Hoy Inline XBRL ya aplica a todo el universo cubierto.

### 한국어 (初译待校)

적용 대상은 이미 XBRL 재무정보를 내야 했던 집단 그대로입니다. smaller reporting companies, emerging growth companies, IFRS 외국 민간 발행인까지 모두 포함되고, 규모가 작다고 면제되지 않고 순서만 뒤로 갑니다. 실시는 두 차례였습니다. 첫째는 2009년 원 규칙(별도 첨부 시대)입니다. 유통주식 시가 50억 달러를 넘는 large accelerated filer가 2009년 6월 15일 이후 종료 기간부터, 그 밖의 large accelerated filer가 2010년 6월 15일 이후 종료 기간부터, 나머지 전부(소형 보고회사 포함)가 2011년 6월 15일 이후 종료 기간부터 적용했고, 주석 태그는 블록 태그에서 상세 태그로 단계화했습니다. 둘째는 2018년 6월 28일 채택, 같은 해 9월 17일 시행된 Inline XBRL 규칙으로, 별도 첨부를 내장 단일 문서로 바꾸고 회사 웹사이트 게시 의무를 없앴습니다. large accelerated filer는 2019년 6월 15일 이후 종료 기간부터, accelerated filer는 2020년 6월 15일 이후 종료 기간부터, 나머지는 2021년 6월 15일 이후 종료 기간부터 전환했습니다. 오늘은 적용 대상 전원에게 Inline XBRL이 적용됩니다.

### Tiếng Việt (初译待校)

Phạm vi bao phủ đi theo nhóm vốn đã phải nộp thông tin tài chính dạng XBRL: mọi công ty hoạt động trong nhóm đó đều thuộc diện, gồm smaller reporting companies, emerging growth companies và nhà phát hành tư nhân nước ngoài theo IFRS; quy mô nhỏ chỉ được xếp sau, không được miễn. Việc triển khai có hai đợt. Đợt đầu là quy tắc XBRL gốc năm 2009, thời phụ lục tách riêng: large accelerated filer có giá trị cổ phiếu lưu hành trên 5 tỷ đô la áp dụng từ kỳ kết thúc vào hoặc sau ngày 15 tháng 6 năm 2009; các large accelerated filer còn lại từ kỳ kết thúc vào hoặc sau 15 tháng 6 năm 2010; và mọi đơn vị còn lại, kể cả công ty báo cáo nhỏ, từ kỳ kết thúc vào hoặc sau 15 tháng 6 năm 2011, với gắn thẻ thuyết minh đi từ thẻ khối sang thẻ chi tiết. Đợt hai là quy tắc Inline XBRL được thông qua ngày 28 tháng 6 năm 2018, hiệu lực 17 tháng 9 năm 2018, thay phụ lục tách riêng bằng một tài liệu nhúng duy nhất và bỏ yêu cầu cũ về đăng dữ liệu tương tác lên website công ty: large accelerated filer từ kỳ kết thúc vào hoặc sau 15 tháng 6 năm 2019, accelerated filer từ 15 tháng 6 năm 2020, và mọi đơn vị còn lại từ 15 tháng 6 năm 2021. Đến nay Inline XBRL đã áp dụng cho toàn bộ nhóm thuộc diện.

### हिन्दी (初译待校)

दायरा उन्हीं का है जिन्हें पहले से XBRL वित्तीय जानकारी देनी थी: उस समूह की सभी operating companies इसमें हैं, जिनमें smaller reporting companies, emerging growth companies और IFRS वाले विदेशी निजी जारीकर्ता शामिल हैं — छोटा आकार छूट नहीं देता, केवल क्रम पीछे करता है। कार्यान्वयन दो लहरों में हुआ। पहली लहर 2009 का मूल XBRL नियम था, अलग exhibit के युग में: $5 billion से अधिक public float वाले large accelerated filers 15 जून 2009 को या उसके बाद समाप्त अवधियों से, अन्य large accelerated filers 15 जून 2010 को या उसके बाद समाप्त अवधियों से, और शेष सभी, छोटे रिपोर्टरों समेत, 15 जून 2011 को या उसके बाद समाप्त अवधियों से आए; notes की tagging भी block से detail की ओर चरणबद्ध हुई। दूसरी लहर Inline XBRL नियम है, 28 जून 2018 को अपनाया गया और 17 सितंबर 2018 से प्रभावी, जिसने अलग exhibit की जगह एक ही embedded दस्तावेज़ रखा और कंपनी वेबसाइट पर interactive data डालने की पुरानी शर्त हटाई: large accelerated filers 15 जून 2019 को या उसके बाद समाप्त अवधियों से, accelerated filers 15 जून 2020 को या उसके बाद, और शेष सभी 15 जून 2021 को या उसके बाद समाप्त अवधियों से। आज Inline XBRL पूरे covered समूह पर लागू है।

## 四、错误与责任：有限责任期早已过去，标签错就是披露错

### 中文

早期为了让人敢上车，SEC 给过一段过渡保护：临时规则 Rule 406T（Regulation S-T）让互动数据文件在过渡期内享受修正责任待遇——大体上不按通常的「已申报」口径承担证券法责任（反欺诈条款除外），每家自首次被要求提交起最长 24 个月、且整段保护最迟到 2014 年 10 月 31 日为止。这条临时规则已经到期十多年，今天再拿「标签只是附件、错了没关系」当口径就是错题：互动数据自那时起与申报文件其余部分站在同一责任水平上，贴错科目、用反符号、缩放错数量级，性质上与正文印错数字没有区别。实务的落点是数据质量内控：提交前的校验（EDGAR 校验加数据质量规则检查）、扩展标签的审批、正负号与期间维度的复核，都要留痕。SEC 工作人员的公开提醒与执法口径里，XBRL 错误长期是高频瑕疵——错不在格式花哨，而在投资者与数据商直接按标签取数，一个符号贴反，机器读到的就是另一个故事。

### English

To get filers on board, the SEC once offered transitional protection: temporary Rule 406T of Regulation S-T gave interactive data files modified liability treatment — broadly, they were not treated as filed in the usual way for securities-law liability, anti-fraud provisions aside — for up to 24 months from each filer's first required submission, and in no event beyond October 31, 2014. That temporary rule expired long ago, and treating tags today as a mere attachment where errors do not matter is simply wrong: interactive data now stands on the same liability footing as the rest of the filing, and a wrong concept, a flipped sign, or a scaling error is in substance the same as a misprinted number in the body. In practice the landing point is data-quality control: pre-submission validation (EDGAR validation plus data-quality rule checks), approval of extensions, and review of signs and period dimensions, all documented. XBRL errors have been a perennial staff comment theme for a reason — investors and data vendors consume the tags directly, so one flipped sign tells machines a different story.

### Español (初译待校)

Para facilitar la adopción, la SEC ofreció una protección transitoria: la Rule 406T temporal del Regulation S-T dio a los archivos de datos interactivos un tratamiento de responsabilidad modificado — en general no se trataban como presentados en el sentido habitual a efectos de responsabilidad bajo las leyes de valores, salvo las normas antifraude — durante un máximo de 24 meses desde la primera presentación obligatoria de cada declarante y, en ningún caso, más allá del 31 de octubre de 2014. Esa regla temporal expiró hace años, y hoy tratar las etiquetas como un simple anexo sin importancia es un error: los datos interactivos están en el mismo plano de responsabilidad que el resto de la presentación, y un concepto equivocado, un signo invertido o un error de escala equivalen a una cifra mal impresa en el cuerpo. En la práctica, el punto de aterrizaje es el control de calidad de datos: validación previa (validación EDGAR más reglas de calidad), aprobación de extensiones y revisión de signos y períodos, todo documentado.

### 한국어 (初译待校)

도입을 돕기 위해 SEC는 한때 과도기 보호를 뒀습니다. Regulation S-T의 임시 Rule 406T는 대화형 데이터 파일에 수정된 책임 취급을 줬습니다. 대략적으로 사기방지 규정을 빼면 통상의 제출로 취급하지 않았고, 기간은 각 제출인의 첫 의무 제출부터 최장 24개월, 어떤 경우에도 2014년 10월 31일을 넘지 않았습니다. 이 임시 규칙은 오래전에 만료됐고, 오늘 태그를 대수롭지 않은 첨부로 보는 것은 틀린 답입니다. 대화형 데이터는 이제 제출 서류의 나머지 부분과 같은 책임 수준에 있고, 개념을 잘못 붙이거나 부호를 뒤집거나 배율을 틀리면 본문에 숫자를 잘못 인쇄한 것과 같습니다. 실무의 착지는 데이터 품질 통제입니다. 제출 전 검증(EDGAR 검증과 데이터 품질 규칙 점검), 확장의 승인, 부호와 기간 차원의 검토를 모두 기록으로 남기십시오.

### Tiếng Việt (初译待校)

Để khuyến khích áp dụng, SEC từng cho một lớp bảo vệ chuyển tiếp: Rule 406T tạm thời của Regulation S-T dành cho tệp dữ liệu tương tác chế độ trách nhiệm được sửa đổi — nói chung không được coi là đã nộp theo nghĩa thông thường đối với trách nhiệm theo luật chứng khoán, trừ các điều khoản chống gian lận — tối đa 24 tháng kể từ lần nộp bắt buộc đầu tiên của mỗi đơn vị, và trong mọi trường hợp không quá ngày 31 tháng 10 năm 2014. Quy tắc tạm thời đó đã hết hạn từ lâu, và hôm nay coi thẻ như phụ lục không quan trọng là sai: dữ liệu tương tác nay đứng cùng mức trách nhiệm với phần còn lại của hồ sơ, gắn sai khái niệm, đảo dấu hay sai thang đo về bản chất cũng như in sai con số trong thân bài. Trong thực hành, điểm rơi là kiểm soát chất lượng dữ liệu: kiểm hợp lệ trước khi nộp (kiểm EDGAR cộng quy tắc chất lượng dữ liệu), phê duyệt extension, rà soát dấu và chiều kỳ, tất cả đều lưu vết.

### हिन्दी (初译待校)

अपनाने को आसान बनाने के लिए SEC ने एक समय संक्रमणकालीन सुरक्षा दी थी: Regulation S-T की अस्थायी Rule 406T ने interactive data files को संशोधित दायित्व-व्यवहार दिया — सामान्यतः, धोखाधड़ी-विरोधी प्रावधानों को छोड़कर, उन्हें प्रतिभूति-कानून दायित्व के लिए सामान्य अर्थ में filed नहीं माना गया — हर filer की पहली अनिवार्य प्रस्तुति से अधिकतम 24 महीने तक, और किसी भी स्थिति में 31 अक्टूबर 2014 से आगे नहीं। वह अस्थायी नियम बहुत पहले समाप्त हो चुका है, और आज टैग को महत्वहीन अनुलग्नक मानना ग़लत है: interactive data अब फ़ाइलिंग के बाकी हिस्सों के समान दायित्व-स्तर पर है, और ग़लत अवधारणा, उलटा चिह्न या scale की त्रुटि सारतः मुख्य पाठ में ग़लत संख्या छपने जैसी ही है। व्यवहार में पड़ाव डेटा-गुणवत्ता नियंत्रण है: प्रस्तुति-पूर्व validation (EDGAR validation और data-quality नियम जाँच), extensions की स्वीकृति, और चिह्नों व अवधि-आयामों की समीक्षा, सब प्रलेखित।

## 五、审计与鉴证衔接：核对一致，不对标签单独发表审计意见

### 中文

审计师的位置要摆准。现行 SEC 规则不要求审计师对 XBRL 互动数据单独发表审计意见，也没有给标签单设一层强制鉴证：审计意见的对象始终是财务报表本身。衔接发生在三个点。第一，一致性：标签数据必须与已审计报表一致，审阅与审计过程中发现标签与正文对不上，属于要向管理层提出更正的申报瑕疵，而不是可以放过的格式小事。第二，内控：标签的生成、复核与提交流程属于财务报告内部控制的外围一环，流程失控（没人复核扩展、符号规则没人管）在整合审计里可能被评价为控制缺陷的信号。第三，自愿核对：实务中公司或审计师可以另做商定程序一类的核对工作，把标签逐项勾回报表正文——这是自愿的增信安排，不改变「无单独审计意见」的默认口径。备考口径一句收：问「XBRL 要不要审计」，标准答案是「报表要审、标签要与报表一致、但现行规则不对 XBRL 数据单独出审计意见」。

### English

Keep the auditor's place straight. Current SEC rules do not require the auditor to express a separate audit opinion on XBRL interactive data, and they impose no standalone assurance layer on the tags: the audit opinion still addresses the financial statements themselves. The connection runs through three points. First, consistency: tagged data must agree with the audited statements, and a mismatch found during audit or review is a filing defect to raise with management, not a formatting triviality. Second, controls: the tagging, review, and submission process sits at the edge of internal control over financial reporting, and an uncontrolled process — unreviewed extensions, unmanaged sign conventions — can signal a control deficiency in an integrated audit. Third, voluntary checking: companies or auditors may separately perform agreed-upon-procedures style work tying tags back to the statements — a voluntary comfort arrangement that does not change the default of no separate opinion on the data. The exam answer in one line: the statements are audited, the tags must agree with them, but no audit opinion is issued on XBRL data as such under current rules.

### Español (初译待校)

El lugar del auditor debe quedar claro. Las reglas actuales de la SEC no exigen que el auditor emita una opinión de auditoría separada sobre los datos interactivos XBRL ni imponen una capa de aseguramiento independiente sobre las etiquetas: la opinión sigue recayendo sobre los estados financieros mismos. La conexión pasa por tres puntos. Primero, consistencia: los datos etiquetados deben coincidir con los estados auditados, y una discrepancia detectada es un defecto de presentación que debe plantearse a la administración. Segundo, controles: el proceso de etiquetado, revisión y envío roza el control interno sobre la información financiera, y un proceso sin control puede señalar una deficiencia en una auditoría integrada. Tercero, verificación voluntaria: pueden realizarse trabajos de procedimientos acordados que amarren las etiquetas a los estados, un refuerzo voluntario que no altera la regla por defecto de no emitir opinión separada sobre los datos.

### 한국어 (初译待校)

감사인의 위치를 정확히 잡으십시오. 현행 SEC 규칙은 XBRL 대화형 데이터에 대해 별도의 감사 의견을 요구하지 않고, 태그에만 따로 강제 인증을 두지도 않습니다. 감사 의견의 대상은 여전히 재무제표 자체입니다. 연결은 세 지점입니다. 첫째, 일관성입니다. 태그 데이터는 감사받은 제표와 일치해야 하고, 어긋나면 경영진에게 시정을 요구할 제출 흠결입니다. 둘째, 통제입니다. 태그 생성·검토·제출 절차는 재무보고 내부통제의 언저리에 있어, 절차가 무통제면 통합감사에서 통제 결함의 신호가 될 수 있습니다. 셋째, 자발적 대조입니다. 태그를 본문으로 하나씩 대조하는 합의된 절차 같은 작업을 별도로 할 수 있지만, 데이터 자체에 별도 의견을 내지 않는다는 기본값은 바뀌지 않습니다.

### Tiếng Việt (初译待校)

Cần đặt đúng vị trí của kiểm toán viên. Quy tắc hiện hành của SEC không yêu cầu kiểm toán viên đưa ra ý kiến kiểm toán riêng cho dữ liệu tương tác XBRL, cũng không đặt một lớp bảo đảm bắt buộc riêng cho thẻ: ý kiến kiểm toán vẫn hướng vào chính báo cáo tài chính. Sự nối kết đi qua ba điểm. Thứ nhất, tính nhất quán: dữ liệu gắn thẻ phải khớp với báo cáo đã kiểm toán, và sai lệch phát hiện là khiếm khuyết hồ sơ phải nêu với ban quản lý. Thứ hai, kiểm soát: quy trình gắn thẻ, rà soát và nộp nằm ở rìa của kiểm soát nội bộ đối với báo cáo tài chính, và một quy trình thiếu kiểm soát có thể là tín hiệu thiếu sót kiểm soát trong kiểm toán tích hợp. Thứ ba, đối chiếu tự nguyện: có thể làm thêm công việc kiểu thủ tục đã thỏa thuận để nối từng thẻ về thân báo cáo — một sắp xếp tự nguyện, không đổi mặc định là không có ý kiến kiểm toán riêng cho dữ liệu XBRL.

### हिन्दी (初译待校)

ऑडिटर की जगह साफ़ रखें। वर्तमान SEC नियम XBRL interactive data पर अलग ऑडिट राय नहीं माँगते, और टैग पर कोई स्वतंत्र आश्वासन-परत भी अनिवार्य नहीं करते: ऑडिट राय का विषय स्वयं वित्तीय विवरण ही रहते हैं। जुड़ाव तीन बिंदुओं से है। पहला, सुसंगति: टैग किया डेटा ऑडिट किए विवरणों से मेल खाए, और बेमेल मिलना प्रबंधन के सामने उठाने योग्य फ़ाइलिंग-दोष है। दूसरा, नियंत्रण: टैगिंग, समीक्षा और प्रस्तुति की प्रक्रिया वित्तीय रिपोर्टिंग पर आंतरिक नियंत्रण के किनारे पर है, और अनियंत्रित प्रक्रिया एकीकृत ऑडिट में नियंत्रण-कमी का संकेत बन सकती है। तीसरा, स्वैच्छिक मिलान: agreed-upon procedures जैसी अलग जाँच टैग को विवरणों से जोड़ सकती है — यह स्वैच्छिक व्यवस्था है, और डेटा पर अलग राय न देने का डिफ़ॉल्ट नहीं बदलती।

## 六、示意算例勾稽、加州落点与备考清单

### 中文

算例为自编示意数字（明示为示意，已本地整数与 Decimal 两路复算）：某申报人一期 Inline XBRL 文件共 2,400 个事实点（facts），提交前按数据质量规则初检发现错误 36 个，错误率＝36 ÷ 2,400 ＝ 1.50%；修正后复检剩 6 个，错误率＝6 ÷ 2,400 ＝ 0.25%；一轮修正清掉 36 − 6 ＝ 30 个错误。时间线再算一笔：从 2009 年原始规则到 2021 年 Inline XBRL 对全部覆盖对象生效，2021 − 2009 ＝ 12 年、两轮推进——第一轮解决「有没有标签」，第二轮解决「标签与正文是不是同一份文件」。加州落点：州层面没有与 SEC 平行的 XBRL 财务报表强制——在加州注册或经营的公司，向州务卿交存续信息、向特许税委员会（FTB）报税，都不按 XBRL 提交财务报表；只要它是 SEC 申报人，无论注册地在哪个州，走的都是联邦这一套 Rule 405 与 EDGAR（证据等级 B）。备考清单收尾：其一，法源记 Regulation S-T Rule 405 加 Regulation S-K Item 601(b)(101)，不要写成 FASB 强制——FASB 管词典，不管谁必须交。其二，两轮年份分开背：原始附件轮 2009／2010／2011，内嵌轮 2019／2020／2021。其三，Rule 406T 的有限责任保护已于 2014 年 10 月 31 日到期，今日标签错误按申报错误同等看待。其四，审计口径是核对一致、无单独意见。

### English

The worked example uses self-devised illustrative figures (labeled as such; recomputed locally by both integer and Decimal paths): a filer's Inline XBRL document for one period contains 2,400 facts; a pre-submission data-quality check finds 36 errors, an error rate of 36 ÷ 2,400 = 1.50%; after correction, 6 remain, 6 ÷ 2,400 = 0.25%; one correction round clears 36 − 6 = 30 errors. One timeline computation: from the original 2009 rule to Inline XBRL applying to the whole covered population in 2021 is 2021 − 2009 = 12 years and two waves — the first settled whether data are tagged at all, the second settled whether tags and text are the same document. California landing point: the state has no XBRL financial-statement mandate parallel to the SEC's — a company incorporated or operating in California files its statement of information with the Secretary of State and its taxes with the Franchise Tax Board without submitting XBRL financial statements; if it is an SEC filer, it follows the single federal Rule 405 and EDGAR track wherever it is incorporated (evidence grade B). Closing checklist: the legal hooks are Regulation S-T Rule 405 plus Regulation S-K Item 601(b)(101) — not the FASB, which maintains the dictionary but mandates nothing; memorize the two waves separately, exhibits 2009/2010/2011 and Inline 2019/2020/2021; Rule 406T protection ended October 31, 2014, so tagging errors today rank with filing errors; and the audit posture is agreement without a separate opinion.

### Español (初译待校)

El ejemplo usa cifras ilustrativas propias (así señaladas; recomputadas localmente por las vías entera y Decimal): un documento Inline XBRL de un período contiene 2.400 hechos; la revisión previa de calidad detecta 36 errores, tasa de 36 ÷ 2.400 = 1,50 %; tras corregir quedan 6, 6 ÷ 2.400 = 0,25 %; una ronda de corrección elimina 36 − 6 = 30 errores. Cálculo de línea de tiempo: de la regla original de 2009 a la aplicación plena del Inline XBRL en 2021 van 2021 − 2009 = 12 años y dos oleadas. Punto de aterrizaje en California: el estado no tiene un mandato XBRL de estados financieros paralelo al de la SEC; la empresa californiana presenta su información ante el Secretary of State y sus impuestos ante la Franchise Tax Board sin entregar estados en XBRL, y si es declarante SEC sigue la única vía federal de la Rule 405 y EDGAR (grado de evidencia B). Cierre: las fuentes son la Rule 405 del Regulation S-T y el Item 601(b)(101) del Regulation S-K; las dos oleadas se memorizan por separado, 2009/2010/2011 y 2019/2020/2021; la protección de la Rule 406T terminó el 31 de octubre de 2014; y la postura de auditoría es concordancia sin opinión separada.

### 한국어 (初译待校)

산례는 자체 작성한 시연 숫자입니다(시연임을 명시했고, 정수와 Decimal 두 경로로 현지 복산했습니다). 한 기간의 Inline XBRL 문서에 사실(facts) 2,400개가 있고, 제출 전 데이터 품질 점검에서 오류 36개가 나와 오류율은 36 ÷ 2,400 = 1.50%입니다. 수정 후에는 6개가 남아 6 ÷ 2,400 = 0.25%이고, 한 번의 수정으로 36 − 6 = 30개를 지웠습니다. 시간선 계산 하나: 2009년 원 규칙부터 2021년 Inline XBRL 전면 적용까지 2021 − 2009 = 12년, 두 차례의 추진입니다. 캘리포니아 착지: 주 차원에는 SEC와 나란한 XBRL 재무제표 강제가 없습니다. 캘리포니아 회사는 국무장관에게 존속 정보를, FTB에 세금을 내지만 XBRL 재무제표는 제출하지 않고, SEC 제출인이면 등록 주가 어디든 연방의 Rule 405와 EDGAR 한 길을 따릅니다(증거 등급 B). 마무리: 법원은 Regulation S-T Rule 405와 Regulation S-K Item 601(b)(101), 두 차례 연도는 2009/2010/2011과 2019/2020/2021로 나눠 외우고, Rule 406T 보호는 2014년 10월 31일에 끝났으며, 감사는 일치 대조이되 별도 의견은 없습니다.

### Tiếng Việt (初译待校)

Ví dụ dùng số minh họa tự soạn (ghi rõ là minh họa; đã tính lại tại chỗ bằng cả hai đường số nguyên và Decimal): một tài liệu Inline XBRL của một kỳ có 2.400 dữ kiện; kiểm tra chất lượng trước khi nộp phát hiện 36 lỗi, tỷ lệ lỗi 36 ÷ 2.400 = 1,50 %; sau khi sửa còn 6 lỗi, 6 ÷ 2.400 = 0,25 %; một vòng sửa xóa 36 − 6 = 30 lỗi. Một phép tính dòng thời gian: từ quy tắc gốc 2009 đến khi Inline XBRL áp dụng cho toàn bộ nhóm thuộc diện năm 2021 là 2021 − 2009 = 12 năm, hai đợt thúc đẩy. Điểm rơi California: cấp bang không có bắt buộc báo cáo tài chính XBRL song song với SEC; công ty California nộp thông tin tồn tại cho Secretary of State và thuế cho FTB mà không nộp báo cáo tài chính XBRL, và nếu là đơn vị nộp SEC thì đi theo đường liên bang duy nhất là Rule 405 và EDGAR ở bất kỳ bang đăng ký nào (cấp bằng chứng B). Chốt: căn cứ pháp lý là Rule 405 của Regulation S-T và Item 601(b)(101) của Regulation S-K; hai đợt năm học riêng, 2009/2010/2011 và 2019/2020/2021; bảo vệ Rule 406T đã kết thúc ngày 31 tháng 10 năm 2014; và tư thế kiểm toán là đối chiếu nhất quán, không có ý kiến riêng.

### हिन्दी (初译待校)

उदाहरण स्वयं बनाए गए निदर्शी आँकड़े हैं (ऐसा स्पष्ट लिखा है; स्थानीय रूप से पूर्णांक और Decimal दोनों रास्तों से पुनर्गणना की गई): एक अवधि के Inline XBRL दस्तावेज़ में 2,400 तथ्य हैं; प्रस्तुति-पूर्व डेटा-गुणवत्ता जाँच में 36 त्रुटियाँ मिलीं, त्रुटि-दर 36 ÷ 2,400 = 1.50%; सुधार के बाद 6 रह गईं, 6 ÷ 2,400 = 0.25%; एक सुधार-दौर ने 36 − 6 = 30 त्रुटियाँ मिटाईं। समय-रेखा की एक गणना: 2009 के मूल नियम से 2021 में पूरे covered समूह पर Inline XBRL लागू होने तक 2021 − 2009 = 12 वर्ष, दो लहरें। California पड़ाव: राज्य-स्तर पर SEC के समानांतर XBRL वित्तीय-विवरण अनिवार्यता नहीं है; California की कंपनी Secretary of State को अस्तित्व-जानकारी और FTB को कर देती है, XBRL विवरण नहीं, और यदि वह SEC filer है तो किसी भी राज्य में पंजीकृत हो, संघीय Rule 405 और EDGAR का एक ही रास्ता चलता है (साक्ष्य ग्रेड B)। समापन सूची: विधिक आधार Regulation S-T Rule 405 और Regulation S-K Item 601(b)(101); दो लहरों के वर्ष अलग याद करें, 2009/2010/2011 और 2019/2020/2021; Rule 406T सुरक्षा 31 अक्टूबर 2014 को समाप्त हुई; और ऑडिट रुख़ सुसंगति-जाँच है, अलग राय नहीं।

---

来源与说明 / Sources：SEC《Inline XBRL Filing of Tagged Data》最终规则（2018 年 6 月 28 日通过、83 Fed. Reg. 2018 年 8 月 16 日刊，Regulation S-T Rule 405 与三档 Inline 生效日）；SEC《Interactive Data to Improve Financial Reporting》最终规则（2009 年，74 Fed. Reg. 2009 年 2 月 10 日刊，原始分阶段与临时 Rule 406T 至 2014 年 10 月 31 日）；Regulation S-K Item 601(b)(101)。算例为自编示意数字，已本地整数与 Decimal 两路复算：36 ÷ 2,400 ＝ 1.50%、6 ÷ 2,400 ＝ 0.25%、36 − 6 ＝ 30、2021 − 2009 ＝ 12。

## 免责声明 / Disclaimer

个人学习笔记，不构成税务建议，亦不构成会计、审计或法律建议；规则以 SEC 公布的现行原文为准，具体事务请咨询持牌专业人士。 / Personal study notes only; not tax, accounting, auditing, or legal advice.

## 补译增量（2026-11-13 04:55 轮）

### 한국어 (初译待校)

Rule 406T의 과도 보호를 보탭니다. 임시 규칙 Rule 406T(Regulation S-T)는 과도기 동안 인터랙티브 데이터 파일에 수정된 책임 대우를 줬습니다. 사기 방지 조항을 빼면 통상의 신고 완료 기준으로는 책임을 묻지 않는 보호였고, 기간은 각 신고인이 처음 제출을 요구받은 때부터 최대 24개월, 전체 보호는 늦어도 2014년 10월 31일에 끝났습니다. 이 임시 규칙은 만료된 지 10년이 넘었으므로, 오늘 태그를 첨부 수준으로 보고 틀려도 괜찮다고 하면 오답입니다. 기한이 지난 뒤 인터랙티브 데이터는 신고서의 나머지 부분과 같은 책임 높이에 서 있고, 과목을 잘못 붙이거나 부호를 뒤집거나 자릿수를 잘못 배율하는 것은 본문에 숫자를 잘못 인쇄한 것과 성격이 같습니다.

감사인의 위치를 보탭니다. 현행 SEC 규칙은 감사인에게 XBRL 인터랙티브 데이터만 따로 떼어 감사 의견을 내라고 요구하지 않고, 태그에 대한 별도의 강제 인증도 두지 않았습니다. 감사 의견의 대상은 어디까지나 재무제표 자체입니다. 연결 지점은 셋입니다. 태그 데이터는 감사받은 재무제표와 일치해야 하고, 태그와 본문이 어긋나면 경영진에게 수정을 요구할 신고 흠결이지 넘길 형식 문제가 아닙니다. 태그의 생성·검토·제출 절차는 재무보고 내부통제의 바깥 테두리에 있어, 절차가 무너지면 통합 감사에서 통제 결함의 신호로 평가될 수 있습니다. 회사나 감사인이 합의된 절차 같은 별도 대조를 자발적으로 할 수는 있지만, 그것은 자발적 보강일 뿐 단독 의견이 없다는 기본값은 바뀌지 않습니다. 시험용 한 줄은 이것입니다. 재무제표는 감사하고, 태그는 제표와 일치시키되, XBRL 데이터만으로는 별도 감사 의견을 내지 않습니다.

### Tiếng Việt (初译待校)

Bổ sung lớp bảo vệ chuyển tiếp của Rule 406T. Quy tắc tạm thời Rule 406T (Regulation S-T) từng cho các tệp dữ liệu tương tác một chế độ trách nhiệm được sửa đổi trong giai đoạn chuyển tiếp: ngoài các điều khoản chống gian lận, chúng không bị xét theo chuẩn đã nộp thông thường, và lớp bảo vệ kéo dài tối đa 24 tháng kể từ lần đầu mỗi bên nộp bị yêu cầu nộp, với toàn bộ bảo vệ kết thúc chậm nhất vào ngày 31 tháng 10 năm 2014. Quy tắc tạm thời đó đã hết hạn hơn mười năm, nên ngày nay coi thẻ gắn chỉ là phụ lục và sai cũng không sao là đáp án sai: kể từ khi hết hạn, dữ liệu tương tác đứng cùng mức trách nhiệm với phần còn lại của hồ sơ, và gắn sai tài khoản, lật ngược dấu hay sai hệ số tỷ lệ cũng cùng tính chất như in sai một con số trong phần chính.

Bổ sung vị trí của kiểm toán viên. Quy tắc SEC hiện hành không yêu cầu kiểm toán viên ra ý kiến kiểm toán riêng cho dữ liệu tương tác XBRL, và cũng không đặt một lớp bảo đảm bắt buộc riêng cho các thẻ gắn. Đối tượng của ý kiến kiểm toán luôn là báo cáo tài chính tự nó. Điểm nối có ba: dữ liệu thẻ gắn phải nhất quán với báo cáo tài chính đã kiểm toán, và khi thẻ gắn lệch khỏi phần chính thì đó là khiếm khuyết khai báo phải nêu với ban quản lý để sửa, không phải chuyện hình thức bỏ qua được; quy trình tạo, rà soát và nộp thẻ gắn thuộc vành ngoài của kiểm soát nội bộ báo cáo tài chính, nên quy trình mất kiểm soát có thể bị đánh giá là tín hiệu khiếm khuyết kiểm soát trong kiểm toán tích hợp; và công ty hay kiểm toán viên có thể tự nguyện làm thêm đối chiếu dạng thủ tục đã thỏa thuận, nhưng đó là bổ sung tự nguyện và không đổi mặc định là không có ý kiến riêng. Một câu chốt cho kỳ thi: báo cáo tài chính thì kiểm toán, thẻ gắn thì phải khớp với báo cáo, nhưng không có ý kiến kiểm toán riêng cho dữ liệu XBRL.

### हिन्दी (初译待校)

Rule 406T के संक्रमणकालीन संरक्षण को जोड़ते हैं। अस्थायी नियम Rule 406T (Regulation S-T) ने संक्रमण अवधि में interactive data फ़ाइलों को संशोधित दायित्व-व्यवहार दिया था: धोखाधड़ी-विरोधी प्रावधानों को छोड़कर वे सामान्य filed मानक से नहीं बँधे थे, और संरक्षण प्रत्येक filer के लिए पहली बार जमा अपेक्षित होने से अधिकतम 24 महीने चला, पूरी सुरक्षा अधिकतम 31 अक्टूबर 2014 को समाप्त हुई। वह अस्थायी नियम एक दशक से अधिक पहले समाप्त हो चुका है, इसलिए आज tags को केवल अनुलग्नक समझकर ग़लती को हल्का लेना ग़लत उत्तर है: समाप्ति के बाद interactive data रिटर्न के बाक़ी हिस्से के समान दायित्व-स्तर पर खड़ा है, और ग़लत खाता लगाना, चिह्न उलटना या scaling की मात्रा बिगाड़ना मूल पाठ में ग़लत संख्या छापने जैसा ही है।

ऑडिटर की स्थिति जोड़ते हैं। वर्तमान SEC नियम ऑडिटर से XBRL interactive data पर अलग ऑडिट राय नहीं माँगते, और tags के लिए कोई अलग अनिवार्य आश्वासन-परत भी नहीं रखते। ऑडिट राय का विषय हमेशा वित्तीय विवरण स्वयं रहते हैं। जुड़ाव के तीन बिंदु हैं: tag data ऑडिट किए गए विवरणों से सुसंगत होना चाहिए, और tag व मूल पाठ में अंतर मिले तो वह प्रबंधन से सुधार माँगने योग्य filing-दोष है, अनदेखा करने योग्य प्रारूप-त्रुटि नहीं; tags के निर्माण, समीक्षा व जमा की प्रक्रिया वित्तीय-रिपोर्टिंग आंतरिक नियंत्रण की बाहरी परिधि में आती है, इसलिए प्रक्रिया का नियंत्रण खोना एकीकृत ऑडिट में नियंत्रण-दोष का संकेत बन सकता है; और कंपनी या ऑडिटर स्वेच्छा से agreed-upon procedures जैसा अलग सत्यापन कर सकते हैं, पर वह स्वैच्छिक पूरक है और अलग राय न होने का डिफ़ॉल्ट नहीं बदलता। परीक्षा के लिए एक पंक्ति: विवरणों का ऑडिट होता है, tags उनसे मेल खाने चाहिए, किंतु XBRL data पर अलग ऑडिट राय नहीं निकलती।
