# 遗产与信托所得税怎么算：Form 1041、DNI 与分配扣除

这篇讲什么：
- 遗产与信托是独立的所得税纳税主体，用 Form 1041（U.S. Income Tax Return for Estates and Trusts）报税，适用税法 J 章（IRC 第 641–668 条），不是被继承人的 1040 的简单延续。
- 核心机制是可分配净收入（DNI）与分配扣除：信托或遗产向受益人分配，分配部分一般从信托层面扣、受益人按 K-1（Schedule K-1, Form 1041）计入，二者合计约等于该笔收入只征一次税。
- 2025 年信托与遗产的税率档极度压缩（Rev. Proc. 2024-40）：应税所得超过 15,650 美元即进入 37% 最高档；免税额只有遗产 600 美元、必须分配的信托 300 美元、其他信托 100 美元（IRC 第 642(b) 条）。
- 赠与人信托（grantor trust）是例外：按第 671–679 条，收入直接归赠与人报税，信托本身一般不另行计税。

---

## 一、总览：谁是纳税人、报哪张表

### 中文

人去世后，未分配的遗产在所得税上是一个独立纳税人；生前信托与遗嘱信托在符合条件时也是独立纳税人。它们报 Form 1041，而不是被继承人最后的 Form 1040。被继承人本人的最后一张 1040 覆盖到去世日为止，之后的收入归遗产或信托。申报门槛见 IRC 第 6012 条：遗产或信托在任何一年总收入达到 600 美元、或有非居民受益人等情形时一般须报 1041；信托若有应税所得，即便总收入未满 600 美元也可能须报。报税年度：遗产一般可选日历年或财政年度，多数信托须用日历年（第 645 条的合格可撤销信托选举是常见例外）。本篇只讲所得税，不讲遗产税（estate tax）与赠与税，那是另一套按转移征税的规则。

### English

After a person dies, the unsettled estate is a separate income-tax taxpayer, and a living trust or testamentary trust is also a separate taxpayer when the conditions are met. They file Form 1041, not the decedent's final Form 1040. The decedent's own final Form 1040 covers income only up to the date of death; later income belongs to the estate or trust. The filing threshold follows IRC section 6012: an estate or trust generally must file Form 1041 when gross income reaches 600 dollars in any year, or when there is a nonresident beneficiary, among other cases, and a trust with taxable income may have to file even below 600 dollars of gross income. For the tax year, an estate may generally choose a calendar or fiscal year, while most trusts must use a calendar year, the qualified revocable trust election under section 645 being a common exception. This note covers income tax only, not estate tax or gift tax, which tax transfers under a different set of rules.

### Español (学习译稿)

Tras el fallecimiento de una persona, el caudal relicto sin repartir es un contribuyente independiente del impuesto sobre la renta, y un fideicomiso en vida o testamentario también lo es cuando se cumplen las condiciones. Presentan el Formulario 1041, no el Formulario 1040 final del causante. El 1040 final del propio causante cubre ingresos solo hasta la fecha del fallecimiento; los ingresos posteriores pertenecen al caudal o al fideicomiso. El umbral de presentación sigue la sección 6012 del Código de Rentas Internas (IRC): un caudal o fideicomiso en general debe presentar el 1041 cuando el ingreso bruto alcanza 600 dólares en un año, o cuando hay un beneficiario no residente, entre otros casos, y un fideicomiso con renta imponible puede tener que presentarlo incluso por debajo de 600 dólares de ingreso bruto. En cuanto al año fiscal, el caudal en general puede elegir año natural o ejercicio fiscal, mientras que la mayoría de los fideicomisos debe usar el año natural, siendo la elección del fideicomiso revocable cualificado de la sección 645 una excepción frecuente. Esta nota trata solo del impuesto sobre la renta, no del impuesto sobre sucesiones ni del de donaciones, que gravan las transmisiones con otro conjunto de reglas.

### 한국어 (初译待校)

사람이 사망하면 아직 정리되지 않은 유산은 소득세상 독립된 납세자이고, 생전 신탁이나 유언 신탁도 조건이 맞으면 독립된 납세자입니다. 이들은 피상속인의 마지막 Form 1040이 아니라 Form 1041을 신고합니다. 피상속인 본인의 마지막 1040은 사망일까지의 소득만을 다루고, 이후 소득은 유산이나 신탁에 귀속됩니다. 신고 문턱은 IRC 제6012조를 따릅니다. 유산이나 신탁은 어느 해든 총소득이 600달러에 달하거나 비거주 수혜자가 있는 경우 등 일반적으로 1041을 신고해야 하고, 과세소득이 있는 신탁은 총소득이 600달러 미만이어도 신고해야 할 수 있습니다. 과세연도는 유산이 일반적으로 역년이나 회계연도를 고를 수 있는 반면, 대부분의 신탁은 역년을 써야 하며, 제645조의 적격 취소 가능 신탁 선택이 흔한 예외입니다. 이 글은 소득세만 다루고, 이전에 과세하는 별개의 규칙인 유산세나 증여세는 다루지 않습니다.

### Tiếng Việt (初译待校)

Sau khi một người qua đời, di sản chưa phân chia là một người nộp thuế thu nhập riêng biệt, và một quỹ tín thác khi còn sống hay theo di chúc cũng là người nộp thuế riêng khi đáp ứng điều kiện. Họ nộp Mẫu 1041, không phải Mẫu 1040 cuối cùng của người đã mất. Mẫu 1040 cuối cùng của chính người đã mất chỉ bao quát thu nhập đến ngày qua đời; thu nhập sau đó thuộc về di sản hoặc quỹ tín thác. Ngưỡng nộp tờ khai theo điều 6012 của Bộ luật Thuế thu nhập (IRC): di sản hoặc quỹ tín thác nhìn chung phải nộp Mẫu 1041 khi tổng thu nhập đạt 600 đô la trong bất kỳ năm nào, hoặc khi có người hưởng lợi không cư trú, cùng các trường hợp khác, và quỹ tín thác có thu nhập chịu thuế có thể phải nộp ngay cả khi tổng thu nhập dưới 600 đô la. Về năm tính thuế, di sản nhìn chung có thể chọn năm dương lịch hoặc năm tài chính, trong khi đa số quỹ tín thác phải dùng năm dương lịch, lựa chọn quỹ tín thác có thể hủy bỏ đủ điều kiện theo điều 645 là một ngoại lệ thường gặp. Ghi chú này chỉ bàn về thuế thu nhập, không bàn về thuế di sản hay thuế tặng cho, vốn đánh thuế việc chuyển giao theo một bộ quy tắc khác.

### हिन्दी (初译待校)

किसी व्यक्ति की मृत्यु के बाद, अनबाँटी हुई संपदा आयकर में एक स्वतंत्र करदाता है, और जीवित ट्रस्ट या वसीयती ट्रस्ट भी शर्तें पूरी होने पर स्वतंत्र करदाता है। वे मृतक का अंतिम Form 1040 नहीं, बल्कि Form 1041 दाखिल करते हैं। मृतक का अपना अंतिम 1040 केवल मृत्यु की तिथि तक की आय को कवर करता है; बाद की आय संपदा या ट्रस्ट की होती है। दाखिल करने की सीमा IRC धारा 6012 के अनुसार है: कोई संपदा या ट्रस्ट सामान्यतः Form 1041 दाखिल करेगा जब किसी वर्ष सकल आय 600 डॉलर तक पहुँचे, या जब कोई अनिवासी लाभार्थी हो, आदि, और करयोग्य आय वाला ट्रस्ट 600 डॉलर से कम सकल आय पर भी दाखिल कर सकता है। कर वर्ष के लिए संपदा सामान्यतः कैलेंडर वर्ष या वित्तीय वर्ष चुन सकती है, जबकि अधिकांश ट्रस्टों को कैलेंडर वर्ष ही अपनाना होगा, धारा 645 के तहत योग्य रद्द करने योग्य ट्रस्ट का चुनाव एक आम अपवाद है। यह नोट केवल आयकर के बारे में है, संपदा कर या उपहार कर के बारे में नहीं, जो हस्तांतरण पर अलग नियमों से कर लगाते हैं।

## 二、税率档与免税额：为什么信托税率看起来很陡

### 中文

遗产与信托的应税所得按与个人类似的方式算（第 641(b) 条），但税率档被压得很窄。2025 年档位（Rev. Proc. 2024-40）是：10% 至 3,150 美元；24% 在 3,150 至 11,450 美元；35% 在 11,450 至 15,650 美元；37% 超过 15,650 美元。也就是说，信托里留 2 万美元应税所得，几乎全部都在最高档附近。免税额也很小：第 642(b) 条给遗产 600 美元，必须当年分配全部收入的信托 300 美元，其他信托 100 美元；而且遗产与信托没有个人的标准扣除。信托还可能适用净投资所得附加税（NIIT，第 1411 条）：信托的起征点就是最高档门槛（2025 年 15,650 美元），不是个人的 200,000 或 250,000 美元。实务结论很直接：能合法分配给受益人的收入，一般不留在信托里按最高档缴税，除非有积累的理由。

### English

Taxable income of an estate or trust is computed in a manner similar to an individual's under section 641(b), but the rate brackets are severely compressed. The 2025 brackets (Rev. Proc. 2024-40) are: 10 percent up to 3,150 dollars; 24 percent from 3,150 to 11,450 dollars; 35 percent from 11,450 to 15,650 dollars; and 37 percent above 15,650 dollars. That means 20,000 dollars of taxable income retained in a trust sits almost entirely at or near the top rate. The exemption is also small: section 642(b) allows 600 dollars for an estate, 300 dollars for a trust required to distribute all of its income currently, and 100 dollars for other trusts, and estates and trusts have no personal standard deduction. A trust may also face the net investment income tax (NIIT, section 1411): the trust threshold is the top-bracket threshold (15,650 dollars for 2025), not the individual's 200,000 or 250,000 dollars. The practical conclusion is direct: income that can lawfully be distributed to beneficiaries is generally not left in the trust to be taxed at the top rate, unless there is a reason to accumulate.

### Español (学习译稿)

La renta imponible de un caudal o fideicomiso se calcula de forma similar a la de una persona física según la sección 641(b), pero los tramos son muy estrechos. Los tramos de 2025 (Rev. Proc. 2024-40) son: 10% hasta 3.150 dólares; 24% de 3.150 a 11.450 dólares; 35% de 11.450 a 15.650 dólares; y 37% por encima de 15.650 dólares. Es decir, 20.000 dólares de renta imponible retenidos en un fideicomiso quedan casi por completo en el tramo máximo o cerca de él. La exención también es pequeña: la sección 642(b) concede 600 dólares al caudal, 300 dólares al fideicomiso obligado a distribuir toda su renta en el ejercicio y 100 dólares a los demás fideicomisos, y los caudales y fideicomisos no tienen deducción estándar personal. Un fideicomiso puede además afrontar el impuesto sobre la renta neta de inversión (NIIT, sección 1411): el umbral del fideicomiso es el umbral del tramo máximo (15.650 dólares en 2025), no los 200.000 o 250.000 dólares de las personas físicas. La conclusión práctica es directa: la renta que puede distribuirse legalmente a los beneficiarios en general no se deja en el fideicomiso para tributar al tipo máximo, salvo que haya una razón para acumularla.

### 한국어 (初译待校)

유산이나 신탁의 과세소득은 제641(b)조에 따라 개인과 비슷한 방식으로 계산되지만, 세율 구간이 극도로 좁습니다. 2025년 구간(Rev. Proc. 2024-40)은 3,150달러까지 10%, 3,150달러에서 11,450달러까지 24%, 11,450달러에서 15,650달러까지 35%, 15,650달러 초과는 37%입니다. 즉 신탁에 남겨진 과세소득 20,000달러는 거의 전부 최고 세율 구간에 있거나 그 근처에 있습니다. 공제액도 작습니다. 제642(b)조는 유산에 600달러, 당해 연도 소득 전부를 분배해야 하는 신탁에 300달러, 그 밖의 신탁에 100달러를 허용하고, 유산과 신탁에는 개인의 표준공제가 없습니다. 신탁은 순투자소득세(NIIT, 제1411조)도 부담할 수 있습니다. 신탁의 문턱은 최고 구간 문턱(2025년 15,650달러)이지, 개인의 200,000달러나 250,000달러가 아닙니다. 실무 결론은 직접적입니다. 적법하게 수혜자에게 분배할 수 있는 소득은, 축적할 이유가 없는 한, 최고 세율로 과세되도록 신탁에 남겨 두지 않는 것이 일반적입니다.

### Tiếng Việt (初译待校)

Thu nhập chịu thuế của di sản hoặc quỹ tín thác được tính tương tự như của cá nhân theo điều 641(b), nhưng các bậc thuế bị nén rất hẹp. Các bậc năm 2025 (Rev. Proc. 2024-40) là: 10% đến 3.150 đô la; 24% từ 3.150 đến 11.450 đô la; 35% từ 11.450 đến 15.650 đô la; và 37% trên 15.650 đô la. Nghĩa là 20.000 đô la thu nhập chịu thuế giữ lại trong quỹ tín thác gần như hoàn toàn nằm ở mức cao nhất hoặc gần mức đó. Khoản miễn trừ cũng nhỏ: điều 642(b) cho phép 600 đô la cho di sản, 300 đô la cho quỹ tín thác bắt buộc phân phối toàn bộ thu nhập trong năm hiện tại, và 100 đô la cho các quỹ tín thác khác, và di sản cùng quỹ tín thác không có khoản khấu trừ tiêu chuẩn của cá nhân. Quỹ tín thác cũng có thể chịu thuế thu nhập đầu tư ròng (NIIT, điều 1411): ngưỡng của quỹ tín thác là ngưỡng bậc cao nhất (15.650 đô la năm 2025), không phải 200.000 hay 250.000 đô la của cá nhân. Kết luận thực tế rất trực tiếp: thu nhập có thể phân phối hợp pháp cho người hưởng lợi nhìn chung không được để lại trong quỹ tín thác để chịu thuế ở mức cao nhất, trừ khi có lý do để tích lũy.

### हिन्दी (初译待校)

किसी संपदा या ट्रस्ट की करयोग्य आय धारा 641(b) के तहत किसी व्यक्ति की तरह ही गिनी जाती है, लेकिन कर स्लैब अत्यंत संकुचित हैं। 2025 के स्लैब (Rev. Proc. 2024-40) हैं: 3,150 डॉलर तक 10%; 3,150 से 11,450 डॉलर तक 24%; 11,450 से 15,650 डॉलर तक 35%; और 15,650 डॉलर से ऊपर 37%। यानी ट्रस्ट में रखी 20,000 डॉलर की करयोग्य आय लगभग पूरी तरह उच्चतम दर पर या उसके निकट बैठती है। छूट भी छोटी है: धारा 642(b) संपदा के लिए 600 डॉलर, चालू वर्ष में अपनी सारी आय बाँटने वाले ट्रस्ट के लिए 300 डॉलर, और अन्य ट्रस्टों के लिए 100 डॉलर देती है, और संपदा व ट्रस्टों को व्यक्तिगत मानक कटौती नहीं मिलती। ट्रस्ट पर शुद्ध निवेश आय कर (NIIT, धारा 1411) भी लग सकता है: ट्रस्ट की सीमा उच्चतम स्लैब की सीमा है (2025 में 15,650 डॉलर), व्यक्ति की 200,000 या 250,000 डॉलर नहीं। व्यावहारिक निष्कर्ष सीधा है: जो आय वैध रूप से लाभार्थियों को बाँटी जा सकती है, उसे सामान्यतः ट्रस्ट में उच्चतम दर पर कर देने के लिए नहीं छोड़ा जाता, जब तक संचय का कोई कारण न हो।

## 三、DNI 与分配扣除：收入只征一次的机制

### 中文

DNI（distributable net income，第 643(a) 条）是信托税务的上限概念：它约等于信托当年可分配的应税所得，扣掉资本利得等调整项（一般不计入 DNI，除非按信托文件计入）。分配扣除（第 651、661 条）的工作方式是：信托把钱分给受益人，分出的部分在信托层面扣除；受益人按第 652、662 条把相应部分计入自己的收入，数额与性质按 K-1 告知。简单信托（simple trust）须当年分配全部收入，扣除额以 DNI 为上限；复杂信托（complex trust）可积累，也可酌情分配，分配同样以 DNI 为上限。分配的层级（tier system，第 662(a) 条）是：第一层是须当年分配的收入先算，第二层是其他分配再算；第一层未用完的 DNI 才轮到第二层。资本利得一般留在信托层面按信托税率缴税，除非信托文件或州法把它算进当年分配的收入。

### English

DNI (distributable net income, section 643(a)) is the ceiling concept of trust taxation: it roughly equals the trust's taxable income available for distribution for the year, with adjustments such as excluding capital gains unless they are included in income under the trust instrument. The distribution deduction (sections 651 and 661) works as follows: the trust distributes money to a beneficiary, the distributed portion is deducted at the trust level, and the beneficiary includes the corresponding portion in the beneficiary's own income under sections 652 and 662, with amount and character reported on the K-1. A simple trust must distribute all of its income currently and its deduction is capped at DNI; a complex trust may accumulate or distribute at discretion, and its distributions are likewise capped at DNI. The tier system (section 662(a)) orders the inclusion: first-tier amounts required to be distributed currently are counted first, and other distributions are counted second, only up to the DNI not used by the first tier. Capital gains generally stay at the trust level and are taxed at trust rates, unless the trust instrument or state law counts them as income distributed currently.

### Español (学习译稿)

La DNI (renta neta distribuible, sección 643(a)) es el concepto techo de la tributación del fideicomiso: equivale aproximadamente a la renta imponible del fideicomiso disponible para distribuir en el ejercicio, con ajustes como excluir las ganancias de capital salvo que se incluyan en la renta según el instrumento del fideicomiso. La deducción por distribución (secciones 651 y 661) funciona así: el fideicomiso distribuye dinero al beneficiario, la parte distribuida se deduce en el fideicomiso, y el beneficiario incluye la parte correspondiente en su propia renta según las secciones 652 y 662, con monto y naturaleza informados en el K-1. Un fideicomiso simple debe distribuir toda su renta en el ejercicio y su deducción tiene como tope la DNI; un fideicomiso complejo puede acumular o distribuir a discreción, y sus distribuciones también tienen como tope la DNI. El sistema de niveles (sección 662(a)) ordena la inclusión: primero se cuentan las cantidades de primer nivel que deben distribuirse en el ejercicio, y después las demás distribuciones, solo hasta la DNI no usada por el primer nivel. Las ganancias de capital en general quedan en el fideicomiso y tributan a los tipos del fideicomiso, salvo que el instrumento del fideicomiso o el derecho estatal las cuente como renta distribuida en el ejercicio.

### 한국어 (初译待校)

DNI(distributable net income, 제643(a)조)는 신탁 과세의 상한 개념입니다. 대략 신탁의 해당 연도 분배 가능한 과세소득과 같으며, 신탁 문서에 따라 소득에 포함되지 않는 한 자본이득을 제외하는 등의 조정이 있습니다. 분배 공제(제651조, 제661조)는 이렇게 작동합니다. 신탁이 수혜자에게 돈을 분배하면, 분배된 부분은 신탁 차원에서 공제되고, 수혜자는 제652조, 제662조에 따라 해당 부분을 자기 소득에 포함하며, 금액과 성격은 K-1에 보고됩니다. 단순 신탁(simple trust)은 당해 연도 소득 전부를 분배해야 하고 공제는 DNI를 상한으로 합니다. 복합 신탁(complex trust)은 축적하거나 재량으로 분배할 수 있고, 분배도 마찬가지로 DNI를 상한으로 합니다. 단계 체계(제662(a)조)는 포함 순서를 정합니다. 당해 연도에 분배해야 하는 1단계 금액이 먼저 계산되고, 그 밖의 분배는 1단계가 쓰지 않은 DNI 범위에서만 두 번째로 계산됩니다. 자본이득은 일반적으로 신탁 차원에 남아 신탁 세율로 과세되며, 신탁 문서나 주법이 이를 당해 연도에 분배되는 소득으로 보지 않는 한 그렇습니다.

### Tiếng Việt (初译待校)

DNI (thu nhập ròng có thể phân phối, điều 643(a)) là khái niệm trần của việc đánh thuế quỹ tín thác: nó xấp xỉ bằng thu nhập chịu thuế của quỹ tín thác có thể phân phối trong năm, với các điều chỉnh như loại trừ lãi vốn trừ khi chúng được tính vào thu nhập theo văn kiện của quỹ tín thác. Khoản khấu trừ phân phối (điều 651 và 661) hoạt động như sau: quỹ tín thác phân phối tiền cho người hưởng lợi, phần đã phân phối được khấu trừ ở cấp quỹ tín thác, và người hưởng lợi cộng phần tương ứng vào thu nhập của mình theo điều 652 và 662, với số tiền và tính chất được báo trên K-1. Quỹ tín thác đơn giản (simple trust) phải phân phối toàn bộ thu nhập trong năm hiện tại và khoản khấu trừ bị giới hạn ở DNI; quỹ tín thác phức tạp (complex trust) có thể tích lũy hoặc phân phối theo quyết định, và các khoản phân phối cũng bị giới hạn ở DNI. Hệ thống tầng (điều 662(a)) sắp xếp thứ tự tính: các khoản tầng một bắt buộc phải phân phối trong năm hiện tại được tính trước, các khoản phân phối khác được tính sau, chỉ trong giới hạn DNI chưa dùng hết ở tầng một. Lãi vốn nhìn chung ở lại cấp quỹ tín thác và chịu thuế theo mức của quỹ tín thác, trừ khi văn kiện của quỹ tín thác hoặc luật bang tính chúng là thu nhập được phân phối trong năm hiện tại.

### हिन्दी (初译待校)

DNI (distributable net income, धारा 643(a)) ट्रस्ट कराधान की सीमा अवधारणा है: यह मोटे तौर पर ट्रस्ट की उस वर्ष बाँटने योग्य करयोग्य आय के बराबर है, जिसमें पूँजीगत लाभ को छोड़ने जैसे समायोजन होते हैं, जब तक ट्रस्ट दस्तावेज़ के तहत उसे आय में न गिना जाए। वितरण कटौती (धारा 651 और 661) इस तरह काम करती है: ट्रस्ट लाभार्थी को धन बाँटता है, बाँटा गया भाग ट्रस्ट स्तर पर काटा जाता है, और लाभार्थी धारा 652 और 662 के तहत संगत भाग को अपनी आय में जोड़ता है, राशि और स्वरूप K-1 पर बताया जाता है। साधारण ट्रस्ट (simple trust) को चालू वर्ष की सारी आय बाँटनी होगी और उसकी कटौती DNI तक सीमित है; जटिल ट्रस्ट (complex trust) संचय कर सकता है या विवेक से बाँट सकता है, और उसके वितरण भी DNI तक सीमित हैं। स्तर प्रणाली (धारा 662(a)) समावेश का क्रम तय करती है: चालू वर्ष में बाँटने के लिए आवश्यक प्रथम-स्तर की राशियाँ पहले गिनी जाती हैं, और अन्य वितरण बाद में केवल प्रथम स्तर से बची DNI तक गिने जाते हैं। पूँजीगत लाभ सामान्यतः ट्रस्ट स्तर पर रहकर ट्रस्ट दरों पर कर योग्य होते हैं, जब तक ट्रस्ट दस्तावेज़ या राज्य विधि उन्हें चालू वर्ष में बाँटी गई आय न माने।

## 四、算例：10,000 美元利息收入，分与不分的税差

### 中文

算例只为说明机制，数字按 2025 年信托档位简化，不计州税与 NIIT。假设某复杂信托当年有利息收入 10,000 美元，无其他收入，免税额 100 美元。若不分配：应税所得约 9,900 美元，按档位算税约 10% × 3,150 ＋ 24% × (9,900 − 3,150) ＝ 315 ＋ 1,620 ＝ 1,935 美元。若全部分给受益人且受益人当年 DNI 覆盖：信托分配扣除 10,000 美元，信托应税所得约 0（扣除与免税额的顺序按 1041 表格处理，实际可能为零或负数归零），税约 0；受益人把 10,000 美元利息计入自己的 1040，按个人档位缴税，通常低于信托最高档的边际负担。结论不是“分配永远省税”：受益人若本身已在高档位，或分配会触发其他税负，仍须逐案算；但信托档位极窄，使得不分配的代价在多数情形下格外明显。

### English

This example illustrates the mechanism only; the numbers use the 2025 trust brackets in simplified form and ignore state tax and NIIT. Suppose a complex trust has 10,000 dollars of interest income for the year, no other income, and a 100-dollar exemption. If nothing is distributed, taxable income is about 9,900 dollars, and the tax by bracket is about 10 percent times 3,150 plus 24 percent times (9,900 minus 3,150), equal to 315 plus 1,620, or 1,935 dollars. If the full amount is distributed to a beneficiary and DNI covers it, the trust's distribution deduction is 10,000 dollars, trust taxable income is about zero (the ordering of the deduction and the exemption follows the Form 1041 computation, and in practice the result may be zero), and trust tax is about zero; the beneficiary includes the 10,000 dollars of interest on the beneficiary's own Form 1040 and pays tax at individual brackets, usually at a lower marginal burden than the trust's top bracket. The conclusion is not that distribution always saves tax: if the beneficiary is already in a high bracket, or a distribution triggers other tax costs, the case must be computed separately; but the narrowness of the trust brackets makes the cost of not distributing conspicuous in most cases.

### Español (学习译稿)

Este ejemplo solo ilustra el mecanismo; las cifras usan los tramos de fideicomisos de 2025 de forma simplificada y omiten el impuesto estatal y el NIIT. Supongamos que un fideicomiso complejo tiene 10.000 dólares de intereses en el ejercicio, ningún otro ingreso y una exención de 100 dólares. Si no se distribuye nada, la renta imponible es de unos 9.900 dólares, y el impuesto por tramos es de alrededor del 10% por 3.150 más el 24% por (9.900 menos 3.150), es decir, 315 más 1.620, o 1.935 dólares. Si se distribuye todo al beneficiario y la DNI lo cubre, la deducción por distribución del fideicomiso es de 10.000 dólares, la renta imponible del fideicomiso es de alrededor de cero (el orden de la deducción y la exención sigue el cálculo del Formulario 1041, y en la práctica el resultado puede ser cero), y el impuesto del fideicomiso es de alrededor de cero; el beneficiario incluye los 10.000 dólares de intereses en su propio Formulario 1040 y paga según los tramos personales, normalmente con una carga marginal menor que el tramo máximo del fideicomiso. La conclusión no es que distribuir siempre ahorre impuestos: si el beneficiario ya está en un tramo alto, o la distribución genera otros costos fiscales, el caso debe calcularse por separado; pero la estrechez de los tramos del fideicomiso hace que el costo de no distribuir sea llamativo en la mayoría de los casos.

### 한국어 (初译待校)

이 예시는 메커니즘을 설명하기 위한 것일 뿐입니다. 숫자는 2025년 신탁 구간을 단순화한 것이고, 주세와 NIIT는 제외합니다. 복합 신탁이 해당 연도에 이자소득 10,000달러가 있고, 다른 소득이 없으며, 공제액이 100달러라고 가정합니다. 아무것도 분배하지 않으면 과세소득은 약 9,900달러이고, 구간별 세금은 약 10% × 3,150달러에 24% × (9,900달러 − 3,150달러)를 더한 315달러 + 1,620달러 = 1,935달러입니다. 전액을 수혜자에게 분배하고 DNI가 이를 충당하면, 신탁의 분배 공제는 10,000달러, 신탁 과세소득은 약 0(공제와 공제액의 순서는 Form 1041 계산을 따르며, 실제로는 0이 될 수 있음)이고, 신탁 세금도 약 0입니다. 수혜자는 10,000달러의 이자를 자기 1040에 포함해 개인 구간으로 세금을 내며, 보통 신탁 최고 구간의 한계 부담보다 낮습니다. 결론은 분배가 항상 세금을 아낀다는 것이 아닙니다. 수혜자가 이미 높은 구간에 있거나 분배가 다른 세금 비용을 유발하면 건별로 계산해야 합니다. 그러나 신탁 구간의 좁음 때문에, 대부분의 경우 분배하지 않는 비용이 유난히 뚜렷합니다.

### Tiếng Việt (初译待校)

Ví dụ này chỉ minh họa cơ chế; các con số dùng bậc thuế của quỹ tín thác năm 2025 ở dạng đơn giản và bỏ qua thuế bang cùng NIIT. Giả sử một quỹ tín thác phức tạp có thu nhập lãi 10.000 đô la trong năm, không có thu nhập khác, và khoản miễn trừ 100 đô la. Nếu không phân phối gì, thu nhập chịu thuế khoảng 9.900 đô la, và thuế theo bậc khoảng 10% nhân 3.150 cộng 24% nhân (9.900 trừ 3.150), bằng 315 cộng 1.620, tức 1.935 đô la. Nếu phân phối toàn bộ cho người hưởng lợi và DNI bao quát khoản đó, khoản khấu trừ phân phối của quỹ tín thác là 10.000 đô la, thu nhập chịu thuế của quỹ tín thác khoảng bằng 0 (thứ tự của khoản khấu trừ và khoản miễn trừ theo cách tính của Mẫu 1041, và trên thực tế kết quả có thể bằng 0), và thuế của quỹ tín thác khoảng bằng 0; người hưởng lợi cộng 10.000 đô la tiền lãi vào Mẫu 1040 của mình và nộp thuế theo bậc cá nhân, thường với gánh nặng biên thấp hơn bậc cao nhất của quỹ tín thác. Kết luận không phải là phân phối luôn tiết kiệm thuế: nếu người hưởng lợi đã ở bậc cao, hoặc việc phân phối gây ra chi phí thuế khác, phải tính riêng từng trường hợp; nhưng sự hẹp của các bậc thuế của quỹ tín thác khiến chi phí của việc không phân phối trở nên nổi bật trong đa số trường hợp.

### हिन्दी (初译待校)

यह उदाहरण केवल तंत्र समझाने के लिए है; संख्याएँ 2025 के ट्रस्ट स्लैबों को सरल रूप में इस्तेमाल करती हैं और राज्य कर व NIIT को छोड़ देती हैं। मान लें कि एक जटिल ट्रस्ट की उस वर्ष ब्याज आय 10,000 डॉलर है, कोई अन्य आय नहीं, और छूट 100 डॉलर है। यदि कुछ भी न बाँटा जाए, तो करयोग्य आय लगभग 9,900 डॉलर होगी, और स्लैब से कर लगभग 10% × 3,150 जमा 24% × (9,900 − 3,150) होगा, यानी 315 + 1,620 = 1,935 डॉलर। यदि पूरी राशि लाभार्थी को बाँट दी जाए और DNI उसे कवर करे, तो ट्रस्ट की वितरण कटौती 10,000 डॉलर होगी, ट्रस्ट की करयोग्य आय लगभग शून्य होगी (कटौती और छूट का क्रम Form 1041 की गणना के अनुसार है, और व्यवहार में परिणाम शून्य हो सकता है), और ट्रस्ट कर लगभग शून्य होगा; लाभार्थी 10,000 डॉलर ब्याज को अपने 1040 में जोड़कर व्यक्तिगत स्लैबों से कर देगा, जो आमतौर पर ट्रस्ट के उच्चतम स्लैब के सीमांत भार से कम होगा। निष्कर्ष यह नहीं है कि बाँटना हमेशा कर बचाता है: यदि लाभार्थी पहले से उच्च स्लैब में हो, या वितरण से अन्य कर लागत पैदा हो, तो मामले को अलग से गिनना होगा; लेकिन ट्रस्ट स्लैबों की संकीर्णता के कारण, अधिकांश मामलों में न बाँटने की लागत विशेष रूप से स्पष्ट होती है।

## 五、赠与人信托、65 天选举与加州衔接

### 中文

赠与人信托按第 671–679 条处理：若赠与人保留对信托的控制权（如可撤销生前信托中赠与人可随时撤销），信托收入直接归赠与人，赠与人在自己的 1040 上报税，信托一般另附一份仅作信息用的 1041（或按 Reg. 第 1.671-4 条用赠与人社会安全号报）。这也是为什么多数生前可撤销信托在赠与人在世时没有独立的信托税单。65 天选举（第 663(b) 条）是另一个实务工具：遗产或复杂信托可在次年 3 月 6 日前（按当年报税表说明的截止规则）选举，把在次年 1 月 1 日至 3 月 6 日之间作出的分配视同上一年度作出，从而用上一年的 DNI 覆盖分配，避免收入滞留在信托的高档位。加州层面：遗产与信托除联邦 1041 外，还可能须报加州 Form 541（Fiduciary Income Tax Return），加州对信托的居民与非居民规则（Rev. & Tax. Code 第 17742 条起）决定哪些收入在加州征税，联邦与加州的分配扣除规则大体平行但细节须分别核对。

### English

Grantor trusts are handled under sections 671–679: where the grantor retains control over the trust (as in a revocable living trust that the grantor may revoke at any time), the trust's income is taxed directly to the grantor, who reports it on the grantor's own Form 1040, while the trust generally files an informational Form 1041 only (or reports under the grantor's Social Security number under Reg. section 1.671-4). That is why most revocable living trusts have no separate trust tax bill while the grantor is alive. The 65-day election (section 663(b)) is another practical tool: an estate or complex trust may elect, by the following March 6 (under the return-instruction deadline rules for the year), to treat a distribution made between January 1 and March 6 of the following year as made in the prior year, so that the prior year's DNI covers the distribution and income is not left stranded in the trust's high brackets. In California, an estate or trust may also have to file California Form 541 (Fiduciary Income Tax Return) in addition to the federal Form 1041; California's resident and nonresident trust rules (Revenue and Taxation Code sections 17742 onward) determine which income is taxed in California, and the federal and California distribution-deduction rules run broadly in parallel but must be checked separately in detail.

### Español (学习译稿)

Los fideicomisos del otorgante se tratan según las secciones 671–679: cuando el otorgante conserva el control del fideicomiso (como en un fideicomiso revocable en vida que el otorgante puede revocar en cualquier momento), la renta del fideicomiso se grava directamente en el otorgante, que la declara en su propio Formulario 1040, mientras que el fideicomiso en general solo presenta un 1041 informativo (o informa con el número de Seguridad Social del otorgante según el Reglamento, sección 1.671-4). Por eso la mayoría de los fideicomisos revocables en vida no tienen factura fiscal propia mientras el otorgante vive. La elección de 65 días (sección 663(b)) es otra herramienta práctica: un caudal o fideicomiso complejo puede elegir, hasta el 6 de marzo siguiente (según las reglas de plazo de las instrucciones de la declaración del año), tratar una distribución hecha entre el 1 de enero y el 6 de marzo del año siguiente como hecha en el año anterior, de modo que la DNI del año anterior cubra la distribución y la renta no quede varada en los tramos altos del fideicomiso. En California, un caudal o fideicomiso puede además tener que presentar el Formulario 541 de California (Declaración del Impuesto sobre la Renta Fiduciaria) junto al 1041 federal; las reglas californianas para fideicomisos residentes y no residentes (Código de Rentas e Impuestos, secciones 17742 y siguientes) determinan qué renta se grava en California, y las reglas federal y californiana de deducción por distribución discurren en general en paralelo pero deben comprobarse por separado en detalle.

### 한국어 (初译待校)

증여자 신탁은 제671–679조에 따라 처리됩니다. 증여자가 신탁에 대한 통제권을 유지하면(증여자가 언제든 취소할 수 있는 취소 가능 생전 신탁처럼), 신탁 소득은 증여자 본인에게 직접 과세되고, 증여자는 자기 1040에 신고하며, 신탁은 일반적으로 정보용 1041만 제출합니다(또는 Reg. 제1.671-4조에 따라 증여자의 사회보장번호로 보고합니다). 그래서 대부분의 취소 가능 생전 신탁은 증여자가 살아 있는 동안 별도의 신탁 세금 고지서가 없습니다. 65일 선택(제663(b)조)은 또 다른 실무 도구입니다. 유산이나 복합 신탁은 다음 해 3월 6일까지(해당 연도 신고서 지침의 마감 규칙에 따라) 선택하여, 다음 해 1월 1일부터 3월 6일 사이에 이루어진 분배를 전년도에 이루어진 것으로 간주할 수 있어, 전년도 DNI가 분배를 충당하고 소득이 신탁의 높은 구간에 갇히지 않게 합니다. 캘리포니아 차원에서는 유산이나 신탁이 연방 1041 외에 캘리포니아 Form 541(수탁자 소득세 신고서)도 제출해야 할 수 있습니다. 캘리포니아의 거주자 및 비거주자 신탁 규칙(Revenue and Taxation Code 제17742조부터)이 캘리포니아에서 어떤 소득이 과세되는지를 정하고, 연방과 캘리포니아의 분배 공제 규칙은 대체로 평행하지만 세부 사항은 따로 확인해야 합니다.

### Tiếng Việt (初译待校)

Quỹ tín thác của người lập được xử lý theo điều 671–679: khi người lập giữ quyền kiểm soát quỹ tín thác (như trong quỹ tín thác khi còn sống có thể hủy bỏ mà người lập có thể hủy bỏ bất cứ lúc nào), thu nhập của quỹ tín thác bị đánh thuế trực tiếp vào người lập, người này khai báo trên Mẫu 1040 của mình, trong khi quỹ tín thác nhìn chung chỉ nộp Mẫu 1041 mang tính thông tin (hoặc báo cáo theo số An sinh Xã hội của người lập theo Quy định, điều 1.671-4). Đó là lý do đa số quỹ tín thác khi còn sống có thể hủy bỏ không có hóa đơn thuế riêng trong khi người lập còn sống. Lựa chọn 65 ngày (điều 663(b)) là một công cụ thực tế khác: di sản hoặc quỹ tín thác phức tạp có thể lựa chọn, đến ngày 6 tháng 3 năm sau (theo quy tắc hạn chót trong hướng dẫn tờ khai của năm), coi khoản phân phối thực hiện từ ngày 1 tháng 1 đến ngày 6 tháng 3 năm sau như được thực hiện trong năm trước, để DNI của năm trước bao quát khoản phân phối và thu nhập không bị kẹt ở các bậc cao của quỹ tín thác. Ở California, di sản hoặc quỹ tín thác còn có thể phải nộp Mẫu 541 của California (Tờ khai Thuế thu nhập của người được ủy thác) ngoài Mẫu 1041 liên bang; các quy tắc của California về quỹ tín thác cư trú và không cư trú (Bộ luật Thuế và Doanh thu, từ điều 17742) xác định thu nhập nào bị đánh thuế ở California, và các quy tắc khấu trừ phân phối liên bang và của California nhìn chung chạy song song nhưng phải kiểm tra riêng từng chi tiết.

### हिन्दी (初译待校)

अनुदाता ट्रस्ट धारा 671–679 के तहत संभाले जाते हैं: जहाँ अनुदाता ट्रस्ट पर नियंत्रण बनाए रखता है (जैसे रद्द करने योग्य जीवित ट्रस्ट जिसे अनुदाता कभी भी रद्द कर सकता है), ट्रस्ट की आय सीधे अनुदाता पर कर योग्य होती है, जो उसे अपने 1040 पर बताता है, जबकि ट्रस्ट सामान्यतः केवल सूचनात्मक 1041 दाखिल करता है (या Reg. धारा 1.671-4 के तहत अनुदाता के Social Security नंबर से रिपोर्ट करता है)। इसीलिए अधिकांश रद्द करने योग्य जीवित ट्रस्टों का अनुदाता के जीवित रहते कोई अलग ट्रस्ट कर बिल नहीं होता। 65-दिन का चुनाव (धारा 663(b)) एक और व्यावहारिक उपकरण है: कोई संपदा या जटिल ट्रस्ट अगले 6 मार्च तक (उस वर्ष की रिटर्न निर्देशों की समय-सीमा नियमों के तहत) चुनाव कर सकता है कि अगले वर्ष 1 जनवरी से 6 मार्च के बीच किया गया वितरण पिछले वर्ष में किया गया माना जाए, ताकि पिछले वर्ष की DNI वितरण को कवर करे और आय ट्रस्ट के उच्च स्लैबों में अटकी न रहे। California स्तर पर, किसी संपदा या ट्रस्ट को संघीय 1041 के अलावा California Form 541 (Fiduciary Income Tax Return) भी दाखिल करना पड़ सकता है; California के निवासी और अनिवासी ट्रस्ट नियम (Revenue and Taxation Code धारा 17742 से आगे) तय करते हैं कि California में कौन-सी आय कर योग्य है, और संघीय व California के वितरण-कटौती नियम मोटे तौर पर समानांतर चलते हैं लेकिन विस्तार से अलग-अलग जाँचे जाने चाहिए।

## 六、读完自检

### 中文

自检五问：能否说清 1041 与被继承人最后 1040 的分界；能否写出 2025 年信托的四个档位与 15,650 美元最高档门槛、遗产 600、300、100 美元三档免税额；能否解释 DNI 是什么、分配扣除怎样让收入只征一次；能否算出本篇算例中不分配约 1,935 美元与全部分配后信托税约 0 的差；能否说出赠与人信托为何在赠与人在世时一般无独立税单、65 天选举的截止日与加州 Form 541 的存在。五问都能答出，本篇的骨架才算立住。

### English

Five self-check questions: can you explain the boundary between Form 1041 and the decedent's final Form 1040; can you state the four 2025 trust brackets with the 15,650-dollar top-bracket threshold and the three exemption amounts of 600, 300, and 100 dollars; can you explain what DNI is and how the distribution deduction makes the same income taxed about once; can you compute the difference in this note's example between about 1,935 dollars with no distribution and about zero trust tax with full distribution; and can you say why a grantor trust generally has no separate tax bill while the grantor is alive, the deadline for the 65-day election, and that California Form 541 exists? If all five can be answered, the skeleton of this note is in place.

### Español (学习译稿)

Cinco preguntas de autoevaluación: ¿puede explicar la frontera entre el Formulario 1041 y el 1040 final del causante; puede enunciar los cuatro tramos de fideicomisos de 2025 con el umbral del tramo máximo de 15.650 dólares y las tres exenciones de 600, 300 y 100 dólares; puede explicar qué es la DNI y cómo la deducción por distribución hace que la misma renta tribute aproximadamente una sola vez; puede calcular la diferencia del ejemplo de esta nota entre unos 1.935 dólares sin distribución y unos cero dólares de impuesto del fideicomiso con distribución total; y puede decir por qué un fideicomiso del otorgante en general no tiene factura fiscal propia mientras el otorgante vive, el plazo de la elección de 65 días y que existe el Formulario 541 de California? Si las cinco tienen respuesta, el esqueleto de esta nota está en su sitio.

### 한국어 (初译待校)

다섯 가지 자가 점검 질문입니다. Form 1041과 피상속인의 마지막 1040의 경계를 설명할 수 있는가, 2025년 신탁의 네 구간과 15,650달러 최고 구간 문턱, 그리고 600달러, 300달러, 100달러의 세 공제액을 말할 수 있는가, DNI가 무엇이고 분배 공제가 어떻게 같은 소득을 대략 한 번만 과세하게 하는지 설명할 수 있는가, 이 글의 예시에서 분배하지 않을 때 약 1,935달러와 전부 분배할 때 신탁 세금이 약 0인 차이를 계산할 수 있는가, 그리고 증여자 신탁이 증여자가 살아 있는 동안 일반적으로 별도 세금 고지서가 없는 이유, 65일 선택의 마감일, 캘리포니아 Form 541의 존재를 말할 수 있는가. 다섯 가지에 모두 답할 수 있으면 이 글의 뼈대가 선 것입니다.

### Tiếng Việt (初译待校)

Năm câu hỏi tự kiểm tra: bạn có thể giải thích ranh giới giữa Mẫu 1041 và Mẫu 1040 cuối cùng của người đã mất không; bạn có thể nêu bốn bậc thuế của quỹ tín thác năm 2025 với ngưỡng bậc cao nhất 15.650 đô la và ba mức miễn trừ 600, 300 và 100 đô la không; bạn có thể giải thích DNI là gì và khoản khấu trừ phân phối làm cho cùng một khoản thu nhập chỉ bị đánh thuế khoảng một lần như thế nào không; bạn có thể tính chênh lệch trong ví dụ của ghi chú này giữa khoảng 1.935 đô la khi không phân phối và khoảng 0 đô la thuế của quỹ tín thác khi phân phối toàn bộ không; và bạn có thể nói vì sao quỹ tín thác của người lập nhìn chung không có hóa đơn thuế riêng trong khi người lập còn sống, hạn chót của lựa chọn 65 ngày, và sự tồn tại của Mẫu 541 của California không? Nếu trả lời được cả năm câu, khung sườn của ghi chú này mới coi như đã đứng vững.

### हिन्दी (初译待校)

पाँच आत्म-जाँच प्रश्न: क्या आप Form 1041 और मृतक के अंतिम Form 1040 के बीच की सीमा समझा सकते हैं; क्या आप 2025 के ट्रस्ट के चार स्लैब 15,650 डॉलर की उच्चतम सीमा के साथ और 600, 300 व 100 डॉलर की तीन छूटें बता सकते हैं; क्या आप समझा सकते हैं कि DNI क्या है और वितरण कटौती से वही आय लगभग एक बार ही कैसे कर योग्य होती है; क्या आप इस नोट के उदाहरण में बिना वितरण के लगभग 1,935 डॉलर और पूर्ण वितरण पर ट्रस्ट कर लगभग शून्य के बीच का अंतर निकाल सकते हैं; और क्या आप कह सकते हैं कि अनुदाता ट्रस्ट का अनुदाता के जीवित रहते सामान्यतः अलग कर बिल क्यों नहीं होता, 65-दिन के चुनाव की अंतिम तिथि क्या है, और California Form 541 मौजूद है? यदि पाँचों के उत्तर मिल जाएँ, तो इस नोट का मूल ढांचा खड़ा हो गया है।

---

本仓库为个人学习笔记，不构成税务建议。
