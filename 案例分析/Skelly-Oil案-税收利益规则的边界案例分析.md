# Skelly Oil 案：税收利益规则的边界案例分析

> 个人学习笔记，不构成税务建议。本案是理解税收利益规则（tax benefit rule）的源头案例，该规则现已法典化为《国内收入法典》第 111 条（26 U.S.C. § 111）。

## 中文

### 一、案件基本信息

案名：United States v. Skelly Oil Co.，案号 394 U.S. 678，美国联邦最高法院 1969 年判决。这是税收利益规则在最高法院层面的标志性表述案件：纳税人早年扣除过的支出，日后被他人偿还时，收回款是否要全额计入当期收入？最高法院给出的答案是：只在先前扣除实际带来税收利益的范围内计入，超出部分排除。这一裁判逻辑后来被 1984 年的立法法典化，成为今天的 § 111。

### 二、案件事实

Skelly Oil Company 是石油与天然气企业。在此前的纳税年度中，Skelly 就相关支出主张过扣除，其中包括百分比耗竭（percentage depletion）等款项——也就是说，某些支出与款项已经在先前年度的申报中被扣除，压低了那些年度的应税所得。后来，Skelly 从客户处收到了偿还款项，这笔钱在经济实质上是对其先前已扣除支出的偿还（reimbursement）。争点随之产生：政府主张收回款构成收入应全额计入；Skelly 主张，先前扣除中有相当部分在当年并未真正给它带来税收利益——若把收回款全额计入，等于对一笔从未产生过节税效果的「扣除」倒过来征税，结果失衡。本案的诉讼正是围绕这一争点展开，最终由最高法院裁断。

为什么会出现「扣除了却没有利益」？原因并不神秘：纳税人某年即使申报了扣除，也可能因当年本身处于亏损、其他扣除已把应税所得压到零、或适用税率结构等因素，使某笔扣除在当年没有减少任何实际税负。扣除写在报表上，不等于利益落进了口袋。Skelly 案要处理的核心，正是报表上的扣除与实际利益之间的这段落差。

### 三、法院推理与税收利益规则

最高法院按税收利益规则处理本案。规则的内容可以拆成两步：第一步，看收回的款项是否对应先前扣除过的项目——若先前根本没有扣除，收回款按一般收入规则处理，不适用本规则的排除。第二步，看先前扣除在扣除当年实际带来了多少税收利益——收回额只在「先前扣除实际产生利益」的范围内计入当期所得；先前扣除当年未产生利益的部分，对应的收回额不计入所得。

推理的根基是量能与对称：税法允许扣除，是因为支出减少了纳税人的经济能力；若支出后来被偿还，经济能力的恢复应当计入收入。但计入的上限应以纳税人实际享受过的利益为界——从未享受过的利益，无从「归还」。全额计入会把无利益的扣除变成纯粹的应税事件，违背所得概念的实质。法院同时强调，该规则是逐项、逐年衡量的：要回到扣除当年的具体申报情形，核算那笔扣除究竟减了多少税，而不是粗略地以「扣过就全额计入」了事。

### 四、数字示例（自洽校验）

设某纳税人先前年度扣除支出 100,000 美元，但经核算，其中 30,000 美元在扣除当年并未带来任何税收利益（例如当年应税所得已被其他项目压至零），实际产生利益的扣除只有 70,000 美元。本年收到全额偿还 100,000 美元。按税收利益规则：计入本年所得的金额 = 100,000 − 30,000 = 70,000 美元，未产生利益部分对应的 30,000 美元收回额排除在所得之外。复核：计入额 70,000 恰好等于当年实际获益的扣除额，勾稽一致；若全额计入 100,000，则多计的 30,000 正是对从未落袋的利益征税，与法院的推理相悖。

### 五、与 § 61、claim of right 的衔接与区别

与 § 61 的衔接：《国内收入法典》§ 61 对总所得（gross income）作广义定义，收回先前扣除的款项在表面上完全可以落入 § 61 的范围。税收利益规则（及后来的 § 111）是在 § 61 之上的一道排除机制：它不否认 § 61 的广义性，而是基于公平与对称，对「先前扣除未获利益」对应的收回额作出例外排除。理解顺序是先 § 61、后 § 111，两者是「原则—例外」关系，不是互相排斥。

与 claim of right（权利主张原则）的区别：claim of right 原则处理的是「纳税人基于表面权利收到款项时，即使日后可能要退还，也先在收到年度计入收入，退还时再作调整」的问题，关注的是收入确认的年度与归属。税收利益规则处理的是另一个维度的问题：「这笔收回款中，有多少根本不该计入」，关注的是计入的范围与上限。两者可能在同一笔款项上先后登场——先按 claim of right 确定收到年度计入，再按税收利益规则削减其中未获利益的部分——但切不可混为一谈：一个定「何时计」，一个定「计多少」。

### 六、法典化与备考要点

1984 年，国会把税收利益规则法典化为 § 111（26 U.S.C. § 111），标题即「税收利益项目的收回排除」（Recovery of tax benefit items）：先前年度扣除过的款项在后年收回的，若先前扣除未减少税负，对应收回额不计入总所得。法典化之后，Skelly 案的推理成为 § 111 的解释背景，实务适用以法条文本为主、以本案界定边界情形。

CPA REG 备考要点有三：第一，顺序感——先判断收回款是否对应先前扣除，再核算先前扣除的实际利益，最后定计入额；第二，核算落点在扣除当年——利益有无取决于扣除当年的申报实况，不是收回当年的状况；第三，区分概念——§ 61（广义收入）、§ 111（未获利益部分的排除）、claim of right（收到年度先计入）三者各管一段，题目常把三者编在一起设陷阱。掌握本案，税收利益规则的整条逻辑链就完整了。

## English

### Case Information

United States v. Skelly Oil Co., 394 U.S. 678 (1969), decided by the U.S. Supreme Court, is the landmark articulation of the tax benefit rule at the Supreme Court level. The question: when a taxpayer is later reimbursed for expenditures it deducted in earlier years, must the entire recovery be included in income? The Court's answer: only to the extent the earlier deduction actually produced a tax benefit; the portion attributable to deductions that yielded no benefit is excluded. Congress codified this logic in 1984 as § 111 of the Internal Revenue Code (26 U.S.C. § 111), "Recovery of Tax Benefit Items."

### Facts

Skelly Oil Company, an oil and gas business, had claimed deductions in prior taxable years, including amounts connected with percentage depletion. Expenditures reflected in those deductions were later reimbursed by customers—the recovery, in economic substance, repaid expenses Skelly had already deducted. The government argued the recovery was income in full. Skelly answered that a substantial part of the earlier deductions had produced no actual tax benefit in the deduction years—because, for example, losses or other deductions had already driven taxable income to zero—so taxing the full recovery would tax the reversal of a benefit never received. The Supreme Court resolved the dispute in Skelly's favor on that point.

### The Court's Reasoning and the Tax Benefit Rule

The tax benefit rule works in two steps. First, ask whether the recovery corresponds to an item previously deducted; if nothing was deducted, ordinary income principles apply without the exclusion. Second, measure how much tax benefit the earlier deduction actually produced in the deduction year: the recovery is included in income only up to that benefited amount, and the remainder is excluded. The logic is symmetry—deductions are allowed because an outlay reduced the taxpayer's economic capacity, and a later reimbursement restores that capacity, but the restoration can be taxed only to the extent of the benefit actually enjoyed. The inquiry is item-by-item and year-by-year, returning to the deduction year's actual return posture rather than applying a blanket "deducted, therefore fully taxable on recovery" rule.

### Numerical Example (Self-Consistent)

Suppose a taxpayer previously deducted $100,000, but $30,000 of that deduction produced no tax benefit in the deduction year, so only $70,000 of the deduction actually reduced tax. The taxpayer later recovers the full $100,000. Under the tax benefit rule, the amount included in income is $100,000 − $30,000 = $70,000; the $30,000 recovery attributable to the non-benefited portion is excluded. Check: the included $70,000 exactly equals the benefited deduction, while including the full $100,000 would tax $30,000 of benefit never received—precisely what the Court rejected.

### Relation to § 61 and Distinction from Claim of Right

Section 61 defines gross income broadly, and a recovery of a previously deducted item facially fits within it. The tax benefit rule, and later § 111, operates as an exclusion layered on top of § 61: a principle–exception relationship, not a conflict. The claim of right doctrine is different: it governs timing and attribution—a taxpayer who receives funds under an apparent claim of right includes them in the year of receipt even if repayment may later be required, with adjustment upon repayment. The tax benefit rule governs scope—how much of a recovery is includible at all. One doctrine answers "when," the other answers "how much," and both can apply to the same payment in sequence.

### Codification and Exam Points

In 1984 Congress codified the rule as § 111 (26 U.S.C. § 111): recoveries of amounts deducted in a prior year are excluded from gross income to the extent the deduction did not reduce tax. For CPA REG purposes: (1) apply the sequence—match the recovery to a prior deduction, then measure the deduction-year benefit, then fix the includible amount; (2) the benefit inquiry looks to the deduction year, not the recovery year; and (3) keep § 61, § 111, and claim of right distinct, as exam questions deliberately blend them.

## Español (初译待校)

### Datos del caso

United States v. Skelly Oil Co., 394 U.S. 678 (1969), resuelto por la Corte Suprema de Estados Unidos, es la formulación emblemática de la regla del beneficio fiscal (tax benefit rule). La pregunta: si un contribuyente recibe el reembolso de gastos deducidos en años anteriores, ¿debe incluirse todo el reembolso en el ingreso? La Corte respondió que solo hasta el monto en que la deducción anterior produjo realmente un beneficio fiscal; la parte correspondiente a deducciones sin beneficio queda excluida. En 1984 el Congreso codificó esta lógica en la sección 111 del Código de Rentas Internas (26 U.S.C. § 111).

### Hechos

Skelly Oil Company, empresa de petróleo y gas, había reclamado deducciones en años fiscales anteriores, incluidos montos vinculados al agotamiento porcentual (percentage depletion). Posteriormente, clientes le reembolsaron gastos que ya había deducido. El gobierno sostuvo que el reembolso era ingreso en su totalidad. Skelly respondió que una parte sustancial de las deducciones no había generado beneficio fiscal alguno en el año de la deducción —por ejemplo, porque otras pérdidas o deducciones ya habían reducido el ingreso gravable a cero— y que gravar todo el reembolso equivaldría a gravar la reversión de un beneficio nunca recibido. La Corte Suprema resolvió a favor de Skelly en ese punto.

### La regla del beneficio fiscal

La regla opera en dos pasos. Primero, se verifica si el reembolso corresponde a un concepto deducido previamente. Segundo, se mide cuánto beneficio fiscal produjo realmente la deducción en el año de la deducción: el reembolso se incluye en el ingreso solo hasta ese monto beneficiado y el resto se excluye. La medición es concepto por concepto y año por año, atendiendo a la situación real de la declaración del año de la deducción.

### Ejemplo numérico (consistente)

Un contribuyente dedujo $100,000, pero $30,000 de esa deducción no produjo beneficio fiscal en el año de la deducción, de modo que solo $70,000 redujo efectivamente el impuesto. Al recuperar luego los $100,000 completos, el monto incluido en el ingreso es $100,000 − $30,000 = $70,000, y los $30,000 restantes quedan excluidos. Verificación: los $70,000 incluidos igualan exactamente la deducción beneficiada.

### Relación con la § 61 y diferencia con claim of right

La § 61 define el ingreso bruto en términos amplios, y el reembolso de un concepto deducido encaja en apariencia en esa definición. La regla del beneficio fiscal (y luego la § 111) funciona como una exclusión sobre la § 61: relación de principio y excepción. La doctrina claim of right es distinta: regula el momento de inclusión —quien recibe fondos bajo una aparente titularidad los incluye en el año de recepción aunque luego deba devolverlos—. La regla del beneficio fiscal regula el alcance: cuánto del reembolso es incluible. Una responde «cuándo» y la otra «cuánto».

### Codificación y puntos de examen

En 1984 el Congreso codificó la regla en la § 111 (26 U.S.C. § 111): los reembolsos de montos deducidos en un año anterior se excluyen del ingreso bruto en la medida en que la deducción no redujo el impuesto. Para el examen REG: aplique la secuencia (vincular el reembolso con la deducción, medir el beneficio del año de la deducción, fijar el monto incluible); el beneficio se mide en el año de la deducción, no en el del reembolso; y mantenga distinguidos la § 61, la § 111 y el claim of right.

## 한국어 (초역, 교정 대기)

### 사건 개요

United States v. Skelly Oil Co., 394 U.S. 678 (1969)는 미국 연방대법원이 세제 혜택 규칙(tax benefit rule)을 표명한 대표적 판결이다. 쟁점은 납세자가 과거 연도에 공제한 지출을 나중에 상환받았을 때 상환액 전액을 소득에 포함해야 하는가였다. 법원은 이전 공제가 실제로 세제 혜택을 가져온 범위에서만 포함하고, 혜택이 없었던 부분은 제외한다고 판시했다. 이 논리는 1984년에 내국세입법 § 111(26 U.S.C. § 111)로 법전화되었다.

### 사실관계

석유·가스 회사인 Skelly Oil Company는 이전 과세 연도에 정률 고갈(percentage depletion) 관련 금액을 포함한 공제를 신청한 바 있었다. 이후 고객으로부터 이미 공제한 지출에 대한 상환을 받았다. 정부는 상환액 전액이 소득이라고 주장했지만, Skelly는 이전 공제 중 상당 부분이 공제 연도에 실제로 아무런 세제 혜택을 가져오지 않았다고 반박했다. 예를 들어 그 해에 이미 다른 손실이나 공제로 과세 소득이 0이 된 경우, 보고서상의 공제와 실제 혜택 사이에는 괴리가 생긴다. 연방대법원은 이 점에서 Skelly의 손을 들어주었다.

### 세제 혜택 규칙의 추론

규칙은 두 단계로 작동한다. 첫째, 상환액이 이전에 공제한 항목에 대응하는지 확인한다. 둘째, 이전 공제가 공제 연도에 실제로 얼마나 세제 혜택을 가져왔는지 측정한다. 상환액은 혜택을 받은 금액까지만 소득에 포함하고 나머지는 제외한다. 측정은 항목별, 연도별로 공제 연도의 실제 신고 상황을 기준으로 하며, "공제했으니 상환 시 전액 과세"라는 일괄 규칙은 적용하지 않는다.

### 수치 예시 (정합성 검증)

납세자가 이전에 100,000달러를 공제했지만, 그중 30,000달러는 공제 연도에 세제 혜택을 가져오지 못해 실제 혜택을 본 공제는 70,000달러뿐이었다고 하자. 이후 100,000달러 전액을 상환받으면, 세제 혜택 규칙상 소득 포함액 = 100,000 − 30,000 = 70,000달러이고, 혜택이 없었던 부분에 대응하는 30,000달러는 제외된다. 검산: 포함액 70,000달러는 실제 혜택을 본 공제액과 정확히 일치한다.

### § 61과의 관계 및 claim of right와의 구별

§ 61은 총소득을 넓게 정의하며 이전 공제 항목의 상환도 표면적으로는 그 범위에 들어간다. 세제 혜택 규칙(후의 § 111)은 § 61 위에 겹쳐지는 제외 장치로, 원칙과 예외의 관계이다. claim of right 원칙은 다른 차원의 문제이다. 겉보기에 권리가 있어 받은 금액은 나중에 반환해야 할 가능성이 있어도 받은 연도에 소득으로 포함한다는, 시기와 귀속에 관한 원칙이다. 세제 혜택 규칙은 포함 범위를 정한다. 하나는 "언제", 다른 하나는 "얼마나"에 답하며, 같은 금액에 순차적으로 함께 적용될 수 있다.

### 법전화와 시험 포인트

1984년 의회는 이 규칙을 § 111(26 U.S.C. § 111)로 법전화했다. 이전 연도에 공제한 금액의 상환은 공제가 세금을 줄이지 못한 범위에서 총소득에서 제외된다. REG 시험 포인트: 순서대로 적용할 것(상환과 이전 공제의 대응 확인 → 공제 연도의 혜택 측정 → 포함액 확정), 혜택 판단은 상환 연도가 아닌 공제 연도를 기준으로 할 것, § 61, § 111, claim of right를 명확히 구별할 것.

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

### Thông tin vụ án

United States v. Skelly Oil Co., 394 U.S. 678 (1969), do Tòa án Tối cao Hoa Kỳ xét xử, là phán quyết tiêu biểu về quy tắc lợi ích thuế (tax benefit rule). Vấn đề: khi người nộp thuế được hoàn lại các khoản chi đã khấu trừ ở các năm trước, khoản hoàn lại có phải tính toàn bộ vào thu nhập không? Tòa trả lời: chỉ tính trong phạm vi khoản khấu trừ trước đó thực sự mang lại lợi ích thuế; phần tương ứng với khấu trừ không mang lại lợi ích thì bị loại trừ. Năm 1984, Quốc hội pháp điển hóa logic này thành § 111 của Bộ luật Thuế vụ Nội địa (26 U.S.C. § 111).

### Sự kiện

Skelly Oil Company, doanh nghiệp dầu khí, đã khai khấu trừ trong các năm thuế trước, bao gồm các khoản liên quan đến khấu hao cạn kiệt theo tỷ lệ phần trăm (percentage depletion). Sau đó, khách hàng hoàn lại cho Skelly các khoản chi mà công ty đã khấu trừ. Chính phủ cho rằng toàn bộ khoản hoàn lại là thu nhập. Skelly phản biện rằng một phần đáng kể khấu trừ trước đó không hề mang lại lợi ích thuế trong năm khấu trừ — chẳng hạn vì thua lỗ hoặc các khoản khấu trừ khác đã đưa thu nhập chịu thuế về không — nên đánh thuế toàn bộ khoản hoàn lại tức là đánh thuế việc đảo ngược một lợi ích chưa từng nhận. Tòa án Tối cao đứng về phía Skelly ở điểm này.

### Suy luận và quy tắc lợi ích thuế

Quy tắc gồm hai bước. Bước một, xác định khoản hoàn lại có tương ứng với khoản đã khấu trừ trước đó hay không. Bước hai, đo lường khoản khấu trừ trước đó thực sự mang lại bao nhiêu lợi ích thuế trong năm khấu trừ: khoản hoàn lại chỉ tính vào thu nhập đến mức đã hưởng lợi, phần còn lại bị loại trừ. Việc đo lường thực hiện theo từng khoản, từng năm, dựa trên tình hình kê khai thực tế của năm khấu trừ, chứ không áp dụng máy móc quy tắc "đã khấu trừ thì hoàn lại phải tính hết".

### Ví dụ số (đã tự kiểm tra)

Giả sử người nộp thuế trước đó khấu trừ 100.000 USD, nhưng 30.000 USD trong đó không mang lại lợi ích thuế trong năm khấu trừ, nên chỉ 70.000 USD thực sự làm giảm thuế. Sau đó người này nhận lại đủ 100.000 USD. Theo quy tắc lợi ích thuế, số tính vào thu nhập = 100.000 − 30.000 = 70.000 USD; 30.000 USD tương ứng với phần không hưởng lợi bị loại trừ. Kiểm tra: số tính vào 70.000 USD đúng bằng khoản khấu trừ đã hưởng lợi.

### Quan hệ với § 61 và phân biệt với claim of right

§ 61 định nghĩa tổng thu nhập theo nghĩa rộng, và khoản hoàn lại của một khoản đã khấu trừ bề ngoài hoàn toàn nằm trong phạm vi đó. Quy tắc lợi ích thuế (và sau này là § 111) là cơ chế loại trừ đặt trên § 61: quan hệ nguyên tắc — ngoại lệ. Nguyên tắc claim of right lại khác: nó xử lý thời điểm ghi nhận — người nhận tiền dựa trên quyền bề ngoài phải tính vào thu nhập năm nhận, dù sau này có thể phải trả lại, và điều chỉnh khi trả lại. Quy tắc lợi ích thuế xử lý phạm vi: bao nhiêu trong khoản hoàn lại phải tính. Một bên trả lời "khi nào", một bên trả lời "bao nhiêu".

### Pháp điển hóa và điểm thi

Năm 1984, Quốc hội pháp điển hóa quy tắc thành § 111 (26 U.S.C. § 111): khoản hoàn lại của số tiền đã khấu trừ năm trước bị loại khỏi tổng thu nhập trong phạm vi khoản khấu trừ không làm giảm thuế. Điểm thi REG: áp dụng đúng trình tự (đối chiếu khoản hoàn lại với khấu trừ trước → đo lợi ích của năm khấu trừ → xác định số phải tính); lợi ích xét theo năm khấu trừ chứ không phải năm hoàn lại; phân biệt rõ § 61, § 111 và claim of right.

## हिन्दी (प्रारंभिक अनुवाद, समीक्षा लंबित)

### मामले की जानकारी

United States v. Skelly Oil Co., 394 U.S. 678 (1969), अमेरिकी सर्वोच्च न्यायालय का वह प्रमुख निर्णय है जिसने कर लाभ नियम (tax benefit rule) को प्रतिपादित किया। प्रश्न था: जब करदाता को पूर्व वर्षों में कटौती किए गए व्ययों की प्रतिपूर्ति बाद में मिलती है, तो क्या सम्पूर्ण वसूली आय में शामिल होगी? न्यायालय का उत्तर: केवल उसी सीमा तक जिस सीमा तक पूर्व कटौती ने वास्तव में कर लाभ दिया था; जिस भाग से कोई लाभ नहीं मिला, वह बाहर रहेगा। 1984 में कांग्रेस ने इस तर्क को आंतरिक राजस्व संहिता की धारा 111 (26 U.S.C. § 111) के रूप में संहिताबद्ध किया।

### तथ्य

Skelly Oil Company, एक तेल और गैस कंपनी, ने पूर्व कर वर्षों में कटौतियां ली थीं, जिनमें प्रतिशत अवक्षय (percentage depletion) से जुड़ी राशियां भी शामिल थीं। बाद में ग्राहकों ने उसे उन व्ययों की प्रतिपूर्ति की जो वह पहले ही घटा चुकी थी। सरकार ने कहा कि वसूली पूरी तरह आय है। Skelly ने उत्तर दिया कि पूर्व कटौतियों का एक बड़ा भाग कटौती वर्ष में वास्तव में कोई कर लाभ नहीं लाया था — उदाहरण के लिए, अन्य हानियों या कटौतियों ने कर योग्य आय को पहले ही शून्य कर दिया था — इसलिए पूरी वसूली पर कर लगाना उस लाभ के उलटने पर कर लगाना होगा जो कभी मिला ही नहीं। सर्वोच्च न्यायालय ने इस बिंदु पर Skelly का पक्ष लिया।

### कर लाभ नियम का तर्क

नियम दो चरणों में काम करता है। पहला, देखें कि वसूली किसी पूर्व में कटौती की गई मद से संबंधित है या नहीं। दूसरा, मापें कि पूर्व कटौती ने कटौती वर्ष में वास्तव में कितना कर लाभ दिया: वसूली केवल लाभ प्राप्त राशि तक ही आय में शामिल होती है, शेष बाहर रहता है। यह माप मद-दर-मद और वर्ष-दर-वर्ष, कटौती वर्ष की वास्तविक विवरणी स्थिति के आधार पर होता है, न कि "कटौती ली थी इसलिए वसूली पूरी कर योग्य है" जैसे सामान्य नियम से।

### संख्यात्मक उदाहरण (स्वयं सुसंगत)

मान लें कि करदाता ने पहले $100,000 की कटौती ली, परंतु उसमें से $30,000 ने कटौती वर्ष में कोई कर लाभ नहीं दिया, इसलिए केवल $70,000 ने वास्तव में कर घटाया। बाद में उसे पूरे $100,000 की वसूली होती है। कर लाभ नियम के अनुसार आय में शामिल राशि = $100,000 − $30,000 = $70,000; लाभ-रहित भाग से संबंधित $30,000 बाहर रहता है। जांच: शामिल $70,000 ठीक लाभ प्राप्त कटौती के बराबर है।

### § 61 से संबंध और claim of right से अंतर

धारा 61 सकल आय को व्यापक रूप से परिभाषित करती है, और पूर्व में कटौती की गई मद की वसूली सतही रूप से उसके दायरे में आती है। कर लाभ नियम (और बाद में § 111) § 61 के ऊपर एक अपवर्जन तंत्र है: सिद्धांत और अपवाद का संबंध। claim of right सिद्धांत इससे भिन्न है: यह समय और आरोपण का प्रश्न है — जो व्यक्ति प्रत्यक्ष अधिकार के आधार पर धन प्राप्त करता है, वह उसे प्राप्ति वर्ष में आय में शामिल करता है, भले ही बाद में वापसी करनी पड़े। कर लाभ नियम दायरे का प्रश्न है: वसूली का कितना भाग शामिल होगा। एक "कब" का उत्तर देता है, दूसरा "कितना" का, और दोनों एक ही भुगतान पर क्रम से लागू हो सकते हैं।

### संहिताकरण और परीक्षा बिंदु

1984 में कांग्रेस ने नियम को § 111 (26 U.S.C. § 111) के रूप में संहिताबद्ध किया: पूर्व वर्ष में कटौती की गई राशियों की वसूली, उस सीमा तक जितनी कटौती ने कर नहीं घटाया, सकल आय से बाहर रहती है। REG परीक्षा के बिंदु: क्रम का पालन करें (वसूली को पूर्व कटौती से मिलाएं, कटौती वर्ष का लाभ मापें, शामिल राशि तय करें); लाभ का आकलन कटौती वर्ष के आधार पर होता है, वसूली वर्ष के आधार पर नहीं; § 61, § 111 और claim of right को स्पष्ट रूप से अलग रखें।

---

**声明**：本文为个人学习笔记，不构成税务建议。Español、한국어、Tiếng Việt、हिन्दी 部分为初译待校。
