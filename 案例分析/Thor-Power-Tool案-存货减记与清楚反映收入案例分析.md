# Thor Power Tool 案：存货减记、客观证据与「GAAP 合规不等于税务合规」案例分析

> 个人学习笔记，不构成税务或审计建议。法条与判例以现行官方文本为准，考试口径以 AICPA 当期 CPA Exam Blueprint 为准。

## 中文主文

**案名**：Thor Power Tool Co. v. Commissioner, 439 U.S. 522 (1979)，美国最高法院，Blackmun 大法官执笔；下级程序：税务法院 64 T.C. 154 (1975)，第七巡回法院 563 F.2d 861 (1977)。本案是 REG 与 FAR 交叉地带最常考的判例之一，一句话结论：**财务会计的 GAAP 不能决定税务处理，税务只认 IRC § 446 与 § 471 的「清楚反映收入（clearly reflect income）」。**

### 一、事实：三笔减记，两种命运

Thor 是电动工具制造商。1964 年前后它做了三笔存货处理，前两笔被税务局（Commissioner）放行、第三笔被全额否决，对照本身就是考点：

1. **约 275 万美元报废核销**：新管理层清点后把过时零件、损坏工具与样品等实物报废（scrapped），大部分物品在减记后不久即实际销毁——税务局**允许**。
2. **24.5 万美元减记**：为三款失败产品备的零件，年度终了后不久即以削价方式实际售出——税务局**允许**。
3. **926,952 美元「超额存货」减记（争议笔）**：管理层按账龄公式（744,030 美元）与固定比例（160,832 美元），外加停产工具零件的十年摊销部分（22,090 美元），把按当时用量估计多年才用得完的备件减记到自己估算的净变现价值（大体是废料价）。但货物**一件没动**：仍留在库存里、仍按原价出售。Thor 把减记冲减 1964 年销售，形成经营净亏损（NOL），再依 § 172 回溯抵扣 1963 年。税务局全额否决，税务法院据此重定 1963 年欠税 494,055.99 美元、1965 年欠税 59,287.48 美元（1965 年欠税另涉下文坏账问题）。

### 二、争点与规则

- **存货计税的总框架**：§ 471(a) 要求存货方法符合财政部规章、能清楚反映收入；§ 446(b) 授权税务局在纳税人方法不能清楚反映收入时按能清楚反映收入的方法计算。规章（今 Treas. Reg. § 1.471-2）下，存货原则上按成本计价，只有「市价（market）」低于成本且有**客观证据**时才能按成本与市价孰低减记——例如实际要价、已报废、已削价出售。
- **「市价」不能靠主观估计**：纳税人对「将来卖得掉多少」的经营判断，哪怕符合 GAAP，也不是规章意义上的市价证据。允许主观估计减记，等于让纳税人自行决定何时确认亏损，收入即不再「清楚反映」。
- **GAAP 只是门槛、不是通行证**：税务法院已认定 Thor 的减记符合 GAAP 且属 § 471 所称「最佳会计实务」，最高法院仍判税务局胜诉——规章符合性与清楚反映收入是**独立于** GAAP 的税务要求；GAAP 与税法的目标不同（对投资者稳健列报 vs 对国库按年准确计税），账税差异本身合法且常见。
- **税务局裁量宽、法院审查窄**：§ 446(b) 的裁量只有被证明滥用时才推翻，本案纳税人未能证明。
- **第二个争点（坏账准备）**：Thor 1965 年按远高于近年实际核销率的比例向坏账准备金追加提列并依当时 § 166(c) 扣除；最高法院同样维持税务局按其历史经验公式核定的较低金额——准备金类估计在税务上一律要过「合理且有经验依据」这一关。（注：§ 166 的准备金法已于 1986 年《税制改革法》对多数纳税人废除、改为特定核销法，此争点今天只剩历史与原理价值。）

### 三、算例：为什么 926,952 美元必须加回

存货恒等式：销货成本＝期初存货＋本期购入／生产成本－期末存货。Thor 把期末存货人为压低 926,952 美元，销货成本即等额放大、应税所得等额缩小。否决减记后只需一步还原：期末存货加回 926,952 美元，1964 年应税所得等额增加，原先靠该亏损制造的 1963 年回溯退税随之落空。这就是「减记时点＝扣除时点」的操纵空间所在，也是规章坚持客观证据的原因。

### 四、今天怎么用（备考与实务接口）

1. **REG 口径**：存货题先问方法能否清楚反映收入（§§ 446, 471），再问减记有无客观证据；看到「按 GAAP 减记到净变现价值但货物未处置」直接联想 Thor，答案是否决。
2. **FAR 口径**：现行 GAAP 存货计量在 ASU 2015-11 后，FIFO 与平均成本法下按成本与净变现价值孰低（ASC 330），LIFO 与零售法的孰低规则另行——财务上照样可以减记，税务上照样要加回，账税差异进递延税（ASC 740），这正是 Thor 留给今天的日常形态。
3. **小企业例外别忘**：§ 471(c) 对符合 § 448(c) 毛收入测试（门槛逐年按通胀调整）的小纳税人放宽存货处理，可按账簿或免存货核算——例外有门槛，不是普遍规则，引用时以当年 IRS 公告数字为准。
4. **证据清单**：要让减记在税务上站住，留下实物处置记录、削价销售发票、报废证明三类客观凭证，缺一类就回到 Thor 的败局。

**一句话记忆**：Thor 案＝「GAAP 是地板不是天花板」——税法另有 § 446／§ 471 的清楚反映收入之尺，存货减记没有客观证据，再合规的估计也扣不了。

*声明：个人学习笔记，不构成税务建议。来源：Thor Power Tool Co. v. Commissioner, 439 U.S. 522 (1979)；64 T.C. 154 (1975)；563 F.2d 861 (7th Cir. 1977)；IRC §§ 166, 172, 446, 448(c), 471；Treas. Reg. § 1.471-2；FASB ASC 330、ASC 740；ASU 2015-11。*

---

## English

*Thor Power Tool Co. v. Commissioner*, 439 U.S. 522 (1979), is the Supreme Court's canonical statement that GAAP does not control tax accounting. In 1964 Thor wrote down "excess" spare-parts inventory by $926,952 ($744,030 by an aging formula, $160,832 by flat percentages, $22,090 of ten-year amortization for discontinued lines) to its own estimate of net realizable value — yet kept the goods in stock and kept selling them at original prices, manufacturing a net operating loss carried back to 1963 under § 172. The Commissioner allowed two companion items — roughly $2.75 million of inventory actually scrapped and $245,000 written down and promptly sold at reduced prices — but disallowed the $926,952 in full. The Tax Court (64 T.C. 154 (1975)) found the write-down conformed to GAAP yet upheld the Commissioner; the Supreme Court affirmed: §§ 446 and 471 impose an independent "clearly reflect income" standard, a write-down below cost needs objective evidence of a lower market (actual offering prices, scrapping, bona fide price cuts), and management's subjective estimate of future salability is not evidence. The arithmetic is one line: ending inventory understated by $926,952 overstates cost of goods sold and understates taxable income by the same $926,952. A companion holding sustained the Commissioner's experience-based limit on Thor's § 166(c) bad-debt reserve addition (the reserve method was later repealed for most taxpayers in 1986). Modern echo: ASC 330 still lets financial reporting write inventory down, while tax adds it back — a book-tax difference for ASC 740, subject to the small-taxpayer relief of § 471(c). *Personal study notes only; not tax advice.*

## Español (traducción de estudio, pendiente de revisión nativa)

*Thor Power Tool Co. v. Commissioner*, 439 U.S. 522 (1979), es la sentencia clásica de que los GAAP no gobiernan la contabilidad fiscal. En 1964 Thor rebajó su inventario «excedente» en 926.952 dólares (744.030 por fórmula de antigüedad, 160.832 por porcentajes fijos y 22.090 de amortización) hasta su propia estimación del valor neto realizable, pero conservó la mercancía y siguió vendiéndola al precio original, creando una pérdida operativa neta retroaplicada a 1963 (§ 172). El Comisionado aceptó unos 2,75 millones de inventario efectivamente destruido y 245.000 rebajados y vendidos pronto con descuento, pero rechazó íntegros los 926.952. La Corte Suprema confirmó: los §§ 446 y 471 exigen de forma independiente que el método «refleje claramente el ingreso», y una rebaja bajo costo requiere evidencia objetiva de mercado menor (precios reales de oferta, destrucción, rebajas efectivas); la estimación subjetiva de la gerencia no es evidencia. La aritmética es directa: inventario final subvaluado en 926.952 infla el costo de ventas y reduce el ingreso gravable en la misma cifra. *Notas personales de estudio; no constituye asesoría fiscal.*

## 한국어 (초역, 교정 대기)

*Thor Power Tool Co. v. Commissioner*, 439 U.S. 522 (1979)는 GAAP가 세무회계를 지배하지 않는다는 대법원의 대표 판례입니다. Thor는 1964년 '초과' 부품 재고를 자체 추정한 순실현가능가치까지 926,952달러 감액했습니다(연령 공식 744,030달러, 정률 160,832달러, 단종 부품 10년 상각분 22,090달러). 그러나 물품은 그대로 재고에 남아 원래 가격으로 계속 팔렸고, 이로써 생긴 순영업손실을 § 172에 따라 1963년으로 이월환급하려 했습니다. 국세청장은 실제로 폐기한 약 275만 달러와 곧 할인 판매한 245,000달러의 감액은 허용했지만 926,952달러는 전액 부인했습니다. 대법원은 §§ 446·471의 '소득의 명확한 반영(clearly reflect income)'이 GAAP와 독립된 기준이며, 원가 이하 감액에는 실제 제시가격·폐기·실제 할인 같은 객관적 증거가 필요하고 경영진의 주관적 추정은 증거가 되지 않는다고 확정했습니다. 산식도 한 줄입니다. 기말재고가 926,952달러 과소계상되면 매출원가가 같은 금액만큼 부풀고 과세소득이 그만큼 줄어듭니다.

보충: 이 사건에는 두 번째 쟁점도 있었습니다. Thor는 1965년에 최근 실제 대손율보다 훨씬 높은 비율로 대손충당금을 쌓고 당시 § 166(c)에 따라 공제하려 했으나, 대법원은 국세청장이 회사의 과거 경험 공식으로 산정한 낮은 금액을 유지했습니다. 충당금형 추정은 세무에서 언제나 합리성과 경험적 근거를 요구받습니다. 다만 § 166의 충당금 방식은 1986년 세제개혁법으로 대다수 납세자에게 폐지되고 특정 대손 상각 방식으로 바뀌었으므로, 이 쟁점은 오늘날 역사적·원리적 가치가 큽니다. 현대의 회계와의 연결도 분명합니다. ASU 2015-11 이후 FIFO와 평균원가법의 재고는 원가와 순실현가능가치 중 낮은 금액으로 측정하고(ASC 330), LIFO와 소매재고법은 별도 규칙을 따릅니다. 재무보고에서 감액하더라도 세무에서는 가산 조정하며 그 차이는 ASC 740의 이연법인세가 됩니다. 또 § 471(c)는 § 448(c) 총수입 테스트를 충족하는 소규모 납세자에게 재고 처리를 완화하지만, 기준은 매년 인플레이션 조정을 받으므로 당해 연도 IRS 수치를 확인해야 합니다. 실무 체크리스트는 세 가지입니다. 실제 처분 기록, 할인 판매 송장, 폐기 증명서를 남기지 못하면 Thor의 패소로 돌아갑니다. 조세법원이 GAAP 적합성을 인정했음에도 납세자가 패한 점, 그리고 § 446(b) 재량은 남용이 입증될 때만 뒤집힌다는 점도 함께 기억해야 합니다. *개인 학습 노트이며 세무 자문이 아닙니다.*

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

*Thor Power Tool Co. v. Commissioner*, 439 U.S. 522 (1979), là phán quyết kinh điển của Tòa Tối cao Hoa Kỳ rằng GAAP không chi phối kế toán thuế. Năm 1964, Thor ghi giảm hàng tồn kho "dư thừa" 926.952 đô la (744.030 theo công thức tuổi hàng, 160.832 theo tỷ lệ cố định, 22.090 khấu hao linh kiện ngừng sản xuất) xuống giá trị thuần có thể thực hiện do chính công ty ước tính — nhưng hàng vẫn nằm trong kho và vẫn bán theo giá gốc, tạo ra khoản lỗ hoạt động thuần mang ngược về năm 1963 theo § 172. Cơ quan thuế chấp nhận khoảng 2,75 triệu đô la hàng đã thực sự tiêu hủy và 245.000 đô la đã ghi giảm rồi bán giảm giá ngay sau đó, nhưng bác bỏ toàn bộ 926.952 đô la. Tòa Tối cao giữ nguyên: §§ 446 và 471 đặt ra tiêu chuẩn độc lập "phản ánh rõ ràng thu nhập", và ghi giảm dưới giá gốc cần bằng chứng khách quan về giá thị trường thấp hơn (giá chào bán thực tế, tiêu hủy, giảm giá thật); ước tính chủ quan của ban quản lý không phải bằng chứng. Phép tính chỉ một dòng: tồn kho cuối kỳ thấp hơn 926.952 đô la thì giá vốn cao hơn và thu nhập chịu thuế thấp hơn đúng 926.952 đô la.

Bổ sung: vụ án còn một vấn đề thứ hai. Năm 1965, Thor trích lập dự phòng nợ xấu theo tỷ lệ cao hơn nhiều so với tỷ lệ xóa nợ thực tế những năm gần đây và khấu trừ theo § 166(c) khi đó; Tòa Tối cao vẫn giữ mức thấp hơn mà cơ quan thuế tính theo công thức kinh nghiệm lịch sử của công ty — mọi ước tính dạng dự phòng đều phải qua cửa "hợp lý và có căn cứ kinh nghiệm" trong thuế. Tuy nhiên phương pháp dự phòng của § 166 đã bị bãi bỏ đối với đa số người nộp thuế bởi Đạo luật Cải cách Thuế 1986 và thay bằng phương pháp xóa nợ cụ thể, nên vấn đề này ngày nay chủ yếu còn giá trị lịch sử và nguyên lý. Mối nối với kế toán hiện nay cũng rõ: sau ASU 2015-11, hàng tồn kho theo FIFO và bình quân gia quyền được đo theo giá thấp hơn giữa giá gốc và giá trị thuần có thể thực hiện (ASC 330), còn LIFO và phương pháp bán lẻ theo quy tắc riêng; báo cáo tài chính có thể ghi giảm nhưng thuế vẫn cộng trở lại, và chênh lệch đó đi vào thuế hoãn lại theo ASC 740. Ngoài ra § 471(c) nới lỏng xử lý hàng tồn kho cho người nộp thuế nhỏ đáp ứng kiểm tra tổng thu nhập của § 448(c), nhưng ngưỡng được điều chỉnh theo lạm phát hằng năm nên phải đối chiếu con số IRS của năm liên quan. Danh mục bằng chứng thực tế gồm ba loại: hồ sơ tiêu hủy thực tế, hóa đơn bán giảm giá và chứng từ tiêu hủy hàng; thiếu một loại là quay lại kết cục của Thor. Cũng cần nhớ rằng Tòa Thuế đã công nhận việc ghi giảm phù hợp GAAP mà người nộp thuế vẫn thua, và quyền tùy nghi theo § 446(b) chỉ bị lật khi chứng minh được sự lạm dụng. *Ghi chép học tập cá nhân, không phải tư vấn thuế.*

## हिन्दी (प्रारंभिक अनुवाद, समीक्षा लंबित)

*Thor Power Tool Co. v. Commissioner*, 439 U.S. 522 (1979), सर्वोच्च न्यायालय का वह प्रसिद्ध निर्णय है कि GAAP कर-लेखांकन को नियंत्रित नहीं करता। 1964 में Thor ने 'अतिरिक्त' पुर्ज़ा-इन्वेंटरी को अपने अनुमानित net realizable value तक $926,952 घटाया (aging formula से $744,030, flat प्रतिशत से $160,832, बंद उत्पादों का $22,090), किंतु सामान गोदाम में ही रहा और मूल दामों पर बिकता रहा, जिससे बना net operating loss § 172 के तहत 1963 में ले जाया गया। Commissioner ने वास्तव में नष्ट की गई लगभग $2.75 million और तुरंत छूट पर बेची गई $245,000 की कटौती मान ली, परंतु $926,952 पूरी तरह अस्वीकार कर दिए। सर्वोच्च न्यायालय ने पुष्टि की: §§ 446 और 471 'clearly reflect income' का स्वतंत्र मानक रखते हैं; लागत से नीचे कटौती के लिए बाज़ार-मूल्य के वस्तुनिष्ठ साक्ष्य (वास्तविक प्रस्ताव-मूल्य, नष्टीकरण, असली मूल्य-कटौती) चाहिए, प्रबंधन का व्यक्तिपरक अनुमान साक्ष्य नहीं है। गणित एक पंक्ति का है: अंतिम इन्वेंटरी $926,952 कम दिखाने से cost of goods sold उतना ही बढ़ता है और करयोग्य आय उतनी ही घटती है।

पूरक: इस मामले में दूसरा प्रश्न भी था। Thor ने 1965 में हाल के वास्तविक बट्टे-खाते की दर से कहीं अधिक अनुपात में bad-debt reserve जोड़ा और तत्कालीन § 166(c) के तहत कटौती चाही; सर्वोच्च न्यायालय ने Commissioner द्वारा कंपनी के ऐतिहासिक अनुभव-सूत्र से तय की गई निचली राशि ही बनाए रखी — reserve जैसे अनुमान कर में हमेशा तर्कसंगत और अनुभव-आधारित होने चाहिए। यद्यपि § 166 की reserve विधि 1986 के Tax Reform Act से अधिकांश करदाताओं के लिए समाप्त कर दी गई और specific charge-off विधि आ गई, इसलिए यह प्रश्न आज मुख्यतः ऐतिहासिक और सैद्धांतिक महत्व रखता है। आधुनिक लेखांकन से कड़ी भी स्पष्ट है: ASU 2015-11 के बाद FIFO और औसत लागत वाली इन्वेंटरी लागत और net realizable value में से कम पर मापी जाती है (ASC 330), जबकि LIFO और retail विधि के नियम अलग हैं; वित्तीय रिपोर्टिंग में कटौती हो भी जाए तो कर में वह वापस जुड़ती है और अंतर ASC 740 में आस्थगित कर बनता है। साथ ही § 471(c) उन छोटे करदाताओं को इन्वेंटरी में राहत देता है जो § 448(c) gross receipts test पूरा करते हैं, किंतु सीमा हर वर्ष मुद्रास्फीति से समायोजित होती है, इसलिए संबंधित वर्ष के IRS आँकड़े जाँचने चाहिए। व्यावहारिक साक्ष्य सूची तीन प्रकार की है: वास्तविक निपटान अभिलेख, छूट पर बिक्री के चालान और नष्टीकरण प्रमाण; इनमें से कोई एक न हो तो परिणाम Thor जैसा होगा। यह भी याद रखें कि Tax Court ने GAAP अनुरूपता स्वीकार करने के बावजूद करदाता हारा, और § 446(b) का विवेक केवल दुरुपयोग सिद्ध होने पर ही पलटता है। *व्यक्तिगत अध्ययन नोट; कर सलाह नहीं है।*
