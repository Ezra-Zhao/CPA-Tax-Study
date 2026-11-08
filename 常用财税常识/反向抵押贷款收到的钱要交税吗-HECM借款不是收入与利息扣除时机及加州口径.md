# 反向抵押贷款收到的钱要交税吗：HECM 借款不是收入、利息扣除时机与加州口径

> 个人学习笔记，不构成税务建议。Personal study notes, not tax advice.
> 核心依据：IRC § 61、§ 163(h)、§ 121；IRS Publication 936（Home Mortgage Interest Deduction）与 IRS 官网老年纳税人问答；12 U.S.C. § 1715z-20 与 24 CFR Part 206（HECM 规则）；CFPB 反向抵押消费者指南。

先给结论：反向抵押（reverse mortgage）每月或一次性拿到的钱不交税——它在税法眼里是借款预支（loan advance），不是收入。代价在另一头：逐年滚进余额的利息和房贷保险费，当期一分不能扣；将来把贷款付清时，利息也通常因为「房屋净值债务」的定性而扣不了，能扣的只是少数情形。把这条线分清，这篇就读完了。

## 中文主文

### 一、到手的钱为什么不交税：借款不产生所得

§ 61(a) 的总收入口径虽宽，但所得要有「实现」——借来的钱同时背上一笔等额偿还义务，财富没有净增加，所以借款本身从不构成收入，这是联邦税法的老原则。IRS 在 Publication 936 里对反向抵押说得很直白：因为反向抵押被视为贷款预支而非收入，你收到的金额不课税（"Because reverse mortgages are considered loan advances and not income, the amount you receive isn't taxable"）；IRS 官网的老年纳税人问答同样写明反向抵押付款是 loan proceeds、不是 income。所以无论是 HECM 的按月付款、一次性提取还是信用额度提款，都不进 Form 1040 的收入行，也不会有 1099 把它报成收入。

两个相邻的坑顺带点清。一是福利资格：不交税不等于不算钱——提取后跨月留在银行账户里的余额，可能计入 SSI、Medicaid（加州 Medi-Cal）等按资产审查的福利资源口径，与税法口径是两套账，领福利的人提取节奏要另外算。二是把钱转赠子女：到手时不课税，但你转手送人走的是赠与口径（年度排除额与 Form 709 的老规则），别把两步混成一步。

### 二、市面上最常见的 HECM：FHA 保险、62 岁门槛与先咨询后申请

反向抵押里占绝对多数的是 HECM（Home Equity Conversion Mortgage），法定根基在 12 U.S.C. § 1715z-20，细则在 24 CFR Part 206，由联邦住房管理局（FHA，隶属 HUD）提供房贷保险。要点五条：

- **年龄**：每位借款人关闭时须年满 62 岁（24 CFR § 206.33），无年龄上限；未满 62 岁的配偶不能当共同借款人，但符合条件的「合格非借款配偶」（Eligible Non-Borrowing Spouse）可在借款人去世后获得延期、继续住在房里（24 CFR § 206.55）。
- **房子**：须是借款人的主要居所，产权仍在借款人名下；借款人要持续住在里面，并继续缴财产税、房屋保险、HOA 等物业费用并维护房屋——这些义务断一档，贷款就可能被宣布到期。
- **咨询**：申请前必须先完成一次由 HUD 认可机构提供的独立咨询（24 CFR § 206.41），咨询师不能与放贷方有利益关联，谈清成本、替代方案与对配偶的影响后才签咨询证书，没有这一步贷款办不下来。
- **能借多少**：本金限额（principal limit）由最年轻借款人（或合格非借款配偶）的年龄、预期利率与最高索赔额（maximum claim amount，取房屋评估值与当年 FHA 限额孰低；2026 年 HECM 限额为 1,249,125 美元）算出，年龄越大、利率越低，可借比例越高。
- **成本进余额**：前期房贷保险费（upfront MIP，按最高索赔额的 2% 收）、持续年 MIP（按平均余额年率 0.5%）、利息，大多不是当场付现，而是滚进贷款余额——余额只涨不落，是这类贷款的常态。

### 三、利息与 MIP 的扣除：当期不能扣，付清时通常也扣不了

这一节是全篇最容易记错的地方，要分两层看，缺一层都会说错。

**第一层是时机。** Publication 936：反向抵押上累积的利息（含原始发行折价 OID），在你实际支付之前不得扣除，而实际支付通常发生在贷款全额付清时。逐年滚进余额的利息，你没有掏钱、也没有「支付」动作，当年 Schedule A 里没有它的位置；每年寄来的 Form 1098 上若列了应计利息，那是余额信息，不是可扣凭证。

**第二层是定性。** 就算到了付清那一年，IRS 的现行口径仍然卡着：IRS 官网问答写明，反向抵押的应计利息一般不得扣除，因为它被视为房屋净值债务（home equity debt）的利息；而 § 163(h)(3) 经 TCJA 修改后，房屋净值类债务的利息只有在借款用于购买、建造或实质改良担保住宅时才可能进合格住宅利息。普通 HECM 的钱多半用于生活支出，不满足这个用途条件，所以「等付清那年一次扣完多年利息」在多数个案里并不成立。只有能清楚对应到买房、建房或实质改良部分的那一截利息，才有在实际支付年度讨论扣除的余地，且仍要过列举扣除（Schedule A）与购置债务上限那道门。MIP 同理跟随利息口径走：未实际支付前不扣，支付后也要先过用途定性这一关，不要把 Form 1098 第 10 格一带的数字直接搬进扣除。

### 四、算例：余额怎么长、卖房怎么算（本地两遍复算）

**算例一（本金限额与一年余额）。** 房屋评估值 500,000 美元，假设本金限额因子 0.40：本金限额 ＝ 500,000 × 0.40 ＝ 200,000 美元（本地复算：500,000 × 0.40 ＝ 200,000，一致）。第一年提取 120,000 美元，示意利率 6%、年 MIP 按余额 0.5% 简化计：一年利息 ＝ 120,000 × 6% ＝ 7,200 美元（复算：120,000 × 0.06 ＝ 7,200，一致），MIP ＝ 120,000 × 0.5% ＝ 600 美元（复算：120,000 × 0.005 ＝ 600，一致），年末余额 ＝ 120,000 ＋ 7,200 ＋ 600 ＝ 127,800 美元。这一年里：提取的 120,000 美元不报收入，7,200 美元利息当年可扣额为 0。

**算例二（卖房结清）。** 多年后卖房，成交价 650,000 美元，当年贷款余额 420,000 美元，房屋基数 250,000 美元：卖房款先还贷款，到手净额 ＝ 650,000 − 420,000 ＝ 230,000 美元（复算一致）。利得的算法里没有贷款余额的位置：利得 ＝ 650,000 − 250,000 ＝ 400,000 美元；单身借款人符合 § 121 所有权与使用测试的，排除 250,000 美元，应税利得 ＝ 400,000 − 250,000 ＝ 150,000 美元（复算一致）。注意还掉的 420,000 美元里含多年累积利息，但如第三节所述，那截消费用途的利息通常不能在这一年补扣——别把「卖房年」误当成「利息扣除年」。

### 五、到期、不追索与继承人：人走了账怎么结

HECM 没有固定到期日，到期靠事件触发：最后一位借款人去世、卖房或转让产权、搬出主要居所（因健康原因入住医疗机构连续超过 12 个月也算）、或断缴财产税与保险等义务落空。到期后贷款方发到期通知，遗产或继承人一般先有 30 天表态，实务上可申请延期争取最长约 6 个月处理出售或融资（以服务商与 HUD 当期流程为准）。

最关键的保护是**不追索（nonrecourse）**：HECM 按 24 CFR Part 206 的设计，借款人与遗产对余额没有个人责任，还款以房屋为限。余额 420,000 美元而房价跌到 380,000 美元时，差额 40,000 美元（复算：420,000 − 380,000 ＝ 40,000）由 FHA 保险兜底，没有人能拿借款人的其他资产、更不能向继承人追这笔缺口。继承人的选择题因此很干净，四选一：其一，还清余额把房留下；其二，按孰低价买下——余额与当前评估值 95% 孰低（HUD 对到期后继承人购回的通行口径）；其三，卖掉房子，还清贷款后多出的钱归遗产，卖价不够也止于房子本身；其四，什么都不做，签 deed-in-lieu 把房交回贷款方。继承人拿房后再卖，基数按 § 1014 的身故日公允价值提升（step-up）起算，与借款余额无关——余额再大，也不吃掉继承人的基数提升。

还要分清遗产税那一层：房屋按全值进遗产总额，贷款余额是遗产的可扣债务，两边同时列，不存在「有反向抵押就不算遗产」的说法；是否真缴遗产税，看当年联邦免税额与州口径（加州无州遗产税）。

### 六、加州口径：定性同向，扣除更没指望

加州对反向抵押没有另设税种，定性与联邦同向：到手的钱是借款、不是加州所得，不计入州收入；利息扣除上，加州的房贷利息规则有自己的衔接日期与购置债务上限（联邦 750,000 美元的新上限加州未同步、州口径仍按其衔接版本执行），但反向抵押利息卡住的真正原因是「净值债务＋未实际支付」这层定性，州里同样过不去，不要指望在州表上把这截利息找回来。福利侧提醒一句：Medi-Cal 的资产口径与联邦税口径无关，在加州办 HECM 前若家里有人领 Medi-Cal，先把提取与留存节奏问清。州层细节以 FTB 与 DHCS 当年口径为准。

**来源与依据**：IRC § 61(a)（总收入定义与借款无所得的一般原则）、§ 163(h)(3)（合格住宅利息与 TCJA 后的用途条件）、§ 121（自住房利得排除）、§ 1014（继承基数提升）；IRS Publication 936 反向抵押条目（贷款预支非收入、利息实际支付前不扣）；IRS 官网 "For senior taxpayers" 问答（付款为 loan proceeds、应计利息因属 home equity debt 一般不可扣）；12 U.S.C. § 1715z-20；24 CFR § 206.33（62 岁）、§ 206.41（咨询）、§ 206.55（非借款配偶延期）与 Part 206 的不追索设计；HUD 2026 年 HECM 最高索赔限额 1,249,125 美元；CFPB 反向抵押消费者指南（到期事件、继承人选择与延期实务）。

*声明：个人学习笔记，不构成税务建议。HECM 的利率、本金限额因子与费用逐单不同，签约前以 HUD 咨询证书、贷款方的 Loan Estimate 与当年 IRS／FTB 口径为准，金额较大先咨询持牌 CPA 与 HUD 认可咨询师。*

---

## English

**Reverse mortgage proceeds are not taxable — but the interest is rarely deductible.** Money received from a reverse mortgage is a loan advance, not income: borrowed funds carry an offsetting repayment obligation, so there is no accession to wealth under § 61. IRS Publication 936 says it directly — because reverse mortgages are considered loan advances and not income, the amount you receive is not taxable — and the IRS senior-taxpayer FAQ calls the payments loan proceeds. Lump sums, monthly advances, and credit-line draws are all outside Form 1040 income, though cash retained in a bank account past the month of receipt can still count as a resource for SSI or Medicaid/Medi-Cal, a separate non-tax ledger.

Most reverse mortgages are HECMs (12 U.S.C. § 1715z-20; 24 CFR Part 206), insured by the FHA. Every borrower must be at least 62 at closing (§ 206.33); the home must be the principal residence, with taxes, insurance, and upkeep kept current; and an independent counseling session with a HUD-approved agency is required before application (§ 206.41). The principal limit turns on the youngest borrower's age, the expected rate, and the maximum claim amount — the lesser of appraised value or the FHA cap ($1,249,125 for 2026). Upfront MIP (2% of the maximum claim amount) and annual MIP (0.5%) usually roll into the balance, so the balance grows by design.

The deduction fails on two independent grounds. Timing: under Publication 936, interest (including OID) accrued on a reverse mortgage is not deductible until you actually pay it, usually at full payoff. Characterization: the IRS treats that accrued interest as interest on home equity debt, and after the TCJA, § 163(h)(3) allows such interest only when the proceeds were used to buy, build, or substantially improve the securing home — living-expense draws do not qualify, so the payoff year does not unlock years of accumulated interest for most borrowers. Worked examples (recomputed twice): a $500,000 home at a 0.40 principal-limit factor gives a $200,000 principal limit; drawing $120,000 at an illustrative 6% plus 0.5% MIP grows the balance to $120,000 + $7,200 + $600 = $127,800 in one year, with $0 of that interest deductible. On a later sale at $650,000 with a $420,000 balance and a $250,000 basis, net cash is $230,000, gain is $650,000 − $250,000 = $400,000, and a qualifying single borrower excludes $250,000 under § 121, leaving $150,000 taxable — the loan balance never enters the gain formula.

The loan comes due when the last borrower dies, sells or transfers the home, moves out (including more than 12 consecutive months in a care facility), or lets taxes or insurance lapse. HECMs are nonrecourse: if a $420,000 balance meets a $380,000 home value, the $40,000 shortfall falls on FHA insurance, never on the borrower's other assets or the heirs. Heirs may repay and keep the home, buy it at the lesser of the balance or 95% of current appraised value, sell it and keep any excess, or hand back a deed in lieu; their basis is the § 1014 date-of-death value regardless of the loan balance. California follows the same characterization — proceeds are not state income, and the interest deduction fails at the state level for the same home-equity-debt and not-yet-paid reasons.

*Personal study notes, not tax advice.*

## Español

**El dinero de una hipoteca inversa no tributa, pero sus intereses rara vez se deducen.** Lo recibido de una hipoteca inversa es un anticipo de préstamo, no ingreso: el dinero prestado trae consigo la obligación de devolverlo, así que no hay aumento de patrimonio bajo el § 61. La Publicación 936 del IRS lo dice sin rodeos —como las hipotecas inversas se consideran anticipos de préstamo y no ingresos, el monto recibido no es gravable— y las respuestas del IRS para contribuyentes mayores lo describen como producto de un préstamo. Ni el pago único, ni los pagos mensuales, ni los retiros de una línea de crédito entran como ingreso en el Formulario 1040; eso sí, el efectivo que queda en el banco más allá del mes de recepción puede contar como recurso para SSI o Medicaid/Medi-Cal, que es otra contabilidad distinta de la fiscal.

La mayoría de las hipotecas inversas son HECM (12 U.S.C. § 1715z-20; 24 CFR Parte 206), aseguradas por la FHA. Cada prestatario debe tener al menos 62 años al cierre (§ 206.33); la vivienda debe ser la residencia principal, con impuestos, seguros y mantenimiento al día; y antes de solicitar se exige una sesión de consejería independiente con una agencia aprobada por HUD (§ 206.41). El límite de principal depende de la edad del prestatario más joven, la tasa esperada y el monto máximo de reclamación —el menor entre el valor tasado y el tope de la FHA ($1.249.125 en 2026)—. La prima inicial MIP (2% del monto máximo) y la anual (0,5%) suelen sumarse al saldo, que por diseño crece.

La deducción fracasa por dos vías independientes. Por tiempo: según la Publicación 936, el interés acumulado (incluido el OID) no es deducible hasta que se paga efectivamente, normalmente al liquidar el préstamo. Por calificación: el IRS trata ese interés como interés de deuda sobre el valor neto de la vivienda (home equity debt), y tras la TCJA el § 163(h)(3) solo lo admite si el dinero se usó para comprar, construir o mejorar sustancialmente la vivienda que lo garantiza; los retiros para gastos de vida no cumplen, así que el año de liquidación no «desbloquea» años de intereses para la mayoría. Ejemplos (recalculados dos veces): vivienda de $500.000 con factor 0,40 → límite de principal de $200.000; retirar $120.000 a un 6% ilustrativo más 0,5% de MIP lleva el saldo a $120.000 + $7.200 + $600 = $127.800 en un año, con $0 de interés deducible. En una venta posterior por $650.000, con saldo de $420.000 y base de $250.000, el efectivo neto es $230.000, la ganancia es $650.000 − $250.000 = $400.000 y un prestatario soltero que cumpla el § 121 excluye $250.000, dejando $150.000 gravables; el saldo del préstamo nunca entra en la fórmula de la ganancia.

El préstamo vence cuando el último prestatario fallece, vende o transfiere la vivienda, se muda (incluidos más de 12 meses seguidos en un centro de cuidados) o deja de pagar impuestos o seguros. El HECM es sin recurso personal (nonrecourse): si un saldo de $420.000 se encuentra con una vivienda que vale $380.000, los $40.000 de diferencia los absorbe el seguro de la FHA, nunca los demás bienes del prestatario ni los herederos. Los herederos pueden pagar y quedarse la casa, comprarla por el menor entre el saldo y el 95% del valor tasado actual, venderla y quedarse el excedente, o entregar la escritura (deed in lieu); su base es el valor a la fecha de fallecimiento según el § 1014, sin importar el saldo. California sigue la misma calificación: lo recibido no es ingreso estatal y la deducción del interés fracasa también a nivel estatal por las mismas razones.

*Notas personales de estudio, no asesoría fiscal. Traducción inicial, pendiente de revisión (初译待校).*

## 한국어 (초역 · 初译待校)

**역모기지(리버스 모기지)로 받는 돈은 과세되지 않지만, 그 이자는 거의 공제되지 않습니다.** 역모기지로 받는 돈은 소득이 아니라 대출 선급금입니다. 빌린 돈에는 같은 금액의 상환 의무가 붙어 순자산이 늘지 않으므로 §61의 소득이 아닙니다. IRS Publication 936은 역모기지는 대출 선급금으로 취급되어 받는 금액이 과세되지 않는다고 명시하고, IRS 고령 납세자 안내도 그 지급금을 loan proceeds라고 부릅니다. 일시금, 월 지급금, 신용한도 인출 모두 Form 1040의 소득에 들어가지 않습니다. 다만 받은 달을 넘겨 은행 계좌에 남겨 둔 현금은 SSI나 Medicaid(캘리포니아 Medi-Cal) 같은 자산 심사 복지에서 자원(resource)으로 셀 수 있어, 세법과는 별개의 장부입니다.

역모기지의 대부분은 FHA가 보험하는 HECM입니다(12 U.S.C. § 1715z-20, 24 CFR Part 206). 모든 차입자는 계약 시 만 62세 이상이어야 하고(§ 206.33), 집은 주 거주지여야 하며 재산세·보험·유지를 계속 책임져야 하고, 신청 전에 HUD 승인 기관의 독립 상담을 받아야 합니다(§ 206.41). 원금 한도는 가장 젊은 차입자의 나이, 예상 금리, 최고 청구액(감정가와 FHA 한도 중 낮은 쪽, 2026년 한도 1,249,125달러)으로 정해집니다. 초기 MIP(최고 청구액의 2%)와 연 MIP(0.5%)는 대개 잔액에 rolled-in 되므로 잔액은 구조적으로 늘어납니다.

공제는 두 겹에서 막힙니다. 첫째 시기: Publication 936에 따라 역모기지의 발생 이자(OID 포함)는 실제로 지급할 때까지 공제할 수 없고, 실제 지급은 보통 전액 상환 시점입니다. 둘째 성격: IRS는 그 발생 이자를 주택 순자산 채무(home equity debt)의 이자로 보는데, TCJA 이후 §163(h)(3)는 담보 주택을 사거나 짓거나 실질적으로 개량하는 데 쓴 경우에만 그런 이자를 허용합니다. 생활비 인출은 여기에 들지 않으므로, 대부분의 차입자에게 상환 연도가 누적 이자를 한꺼번에 풀어 주지 않습니다. 예시(두 번 재계산): 감정가 500,000달러, 원금 한도 계수 0.40이면 원금 한도는 200,000달러. 120,000달러를 연 6% 예시 금리와 0.5% MIP로 인출하면 1년 뒤 잔액은 120,000 + 7,200 + 600 = 127,800달러가 되고, 그 이자의 공제액은 0입니다. 나중에 650,000달러에 팔고 잔액이 420,000달러, basis가 250,000달러이면 순수령액은 230,000달러, 양도차익은 650,000 − 250,000 = 400,000달러, §121 요건을 갖춘 단독 차입자는 250,000달러를 제외해 과세 차익은 150,000달러입니다. 대출 잔액은 차익 공식에 들어가지 않습니다.

대출은 마지막 차입자가 사망하거나, 집을 팔거나 이전하거나, 이사를 가거나(의료시설에 연속 12개월 넘게 머무는 경우 포함), 재산세·보험을 체납하면 만기가 됩니다. HECM은 비소구(nonrecourse)입니다. 잔액 420,000달러에 집값이 380,000달러로 떨어져도 40,000달러의 부족분은 FHA 보험이 부담하고, 차입자의 다른 자산이나 상속인에게 청구되지 않습니다. 상속인은 상환하고 집을 유지하거나, 잔액과 현재 감정가의 95% 중 낮은 금액으로 사들이거나, 팔아서 대출을 갚고 남은 돈을 가지거나, deed in lieu로 집을 넘길 수 있습니다. 상속인의 basis는 대출 잔액과 무관하게 §1014의 사망일 가치입니다. 캘리포니아도 같은 성격 규정을 따릅니다. 받는 돈은 주 소득이 아니고, 이자 공제도 같은 이유로 주에서도 성립하지 않습니다.

*개인 학습 노트이며 세무 조언이 아닙니다. (초역 · 初译待校)*

## Tiếng Việt (bản dịch sơ bộ · 初译待校)

**Tiền nhận từ thế chấp ngược không bị đánh thuế, nhưng lãi của nó hầu như không được khấu trừ.** Tiền từ thế chấp ngược (reverse mortgage) là khoản ứng trước của khoản vay, không phải thu nhập: tiền vay đi kèm nghĩa vụ hoàn trả tương ứng nên không làm tăng tài sản theo § 61. Publication 936 của IRS nói thẳng — vì thế chấp ngược được coi là khoản ứng vay chứ không phải thu nhập, số tiền bạn nhận không bị đánh thuế — và mục hỏi đáp cho người cao tuổi của IRS gọi các khoản chi trả này là loan proceeds. Tiền nhận một lần, tiền nhận hàng tháng và tiền rút từ hạn mức tín dụng đều không vào thu nhập trên Form 1040; tuy nhiên tiền mặt còn giữ trong tài khoản ngân hàng qua tháng nhận có thể bị tính là tài sản khi xét SSI hay Medicaid/Medi-Cal — đó là sổ sách phúc lợi, khác với sổ sách thuế.

Phần lớn thế chấp ngược là HECM (12 U.S.C. § 1715z-20; 24 CFR Part 206) do FHA bảo hiểm. Mọi người vay phải đủ 62 tuổi khi ký kết (§ 206.33); căn nhà phải là nơi cư trú chính, thuế tài sản, bảo hiểm và bảo trì phải được giữ liên tục; và trước khi nộp đơn phải hoàn thành buổi tư vấn độc lập với tổ chức được HUD phê duyệt (§ 206.41). Hạn mức gốc vay phụ thuộc vào tuổi của người vay trẻ nhất, lãi suất kỳ vọng và số tiền yêu cầu tối đa — lấy giá trị thấp hơn giữa giá thẩm định và trần FHA (1.249.125 đô la năm 2026). Phí bảo hiểm MIP ban đầu (2% số tiền yêu cầu tối đa) và MIP hằng năm (0,5%) thường được cộng dồn vào dư nợ, nên dư nợ tăng theo thiết kế.

Khấu trừ lãi bị chặn ở hai lớp độc lập. Lớp thời điểm: theo Publication 936, lãi phát sinh trên thế chấp ngược (kể cả OID) không được khấu trừ cho đến khi bạn thực sự trả, thường là khi trả hết toàn bộ khoản vay. Lớp tính chất: IRS coi phần lãi phát sinh đó là lãi của nợ trên giá trị nhà ròng (home equity debt), và sau TCJA, § 163(h)(3) chỉ cho phép loại lãi này khi tiền vay được dùng để mua, xây hoặc cải tạo đáng kể căn nhà thế chấp; tiền rút để chi tiêu sinh hoạt không đạt, nên năm trả hết nợ cũng không «mở khóa» nhiều năm lãi tích lũy cho đa số người vay. Ví dụ (đã tính lại hai lần): nhà trị giá 500.000 đô la với hệ số hạn mức 0,40 cho hạn mức gốc 200.000 đô la; rút 120.000 đô la ở lãi suất minh họa 6% cộng MIP 0,5% thì sau một năm dư nợ là 120.000 + 7.200 + 600 = 127.800 đô la, và phần lãi được khấu trừ bằng 0. Bán nhà sau đó với giá 650.000 đô la, dư nợ 420.000 đô la, cơ sở giá vốn 250.000 đô la: tiền ròng nhận được là 230.000 đô la, lãi là 650.000 − 250.000 = 400.000 đô la, người vay độc thân đủ điều kiện § 121 được loại trừ 250.000 đô la, còn 150.000 đô la chịu thuế — dư nợ không bao giờ xuất hiện trong công thức tính lãi.

Khoản vay đến hạn khi người vay cuối cùng qua đời, bán hoặc chuyển nhượng nhà, chuyển đi hẳn (kể cả ở cơ sở chăm sóc liên tục hơn 12 tháng), hoặc để thuế hay bảo hiểm quá hạn. HECM là khoản vay không truy đòi (nonrecourse): nếu dư nợ 420.000 đô la mà nhà chỉ còn đáng giá 380.000 đô la, khoản thiếu 40.000 đô la do bảo hiểm FHA gánh, không bao giờ truy sang tài sản khác của người vay hay sang người thừa kế. Người thừa kế có thể trả hết để giữ nhà, mua lại nhà với giá thấp hơn giữa dư nợ và 95% giá thẩm định hiện tại, bán nhà và giữ phần thừa sau khi trả nợ, hoặc giao nhà bằng deed in lieu; cơ sở giá vốn của họ là giá trị tại ngày qua đời theo § 1014, bất kể dư nợ là bao nhiêu. California theo cùng cách phân loại — tiền nhận không phải thu nhập của bang, và khấu trừ lãi cũng không được chấp nhận ở cấp bang vì cùng lý do.

*Ghi chú học tập cá nhân, không phải tư vấn thuế. (bản dịch sơ bộ · 初译待校)*

## हिन्दी (प्रारंभिक अनुवाद · 待校)

**रिवर्स मॉर्गेज से मिला पैसा करयोग्य नहीं है, पर उसका ब्याज शायद ही कभी कटौती योग्य होता है।** रिवर्स मॉर्गेज से प्राप्त धन ऋण-अग्रिम (loan advance) है, आय नहीं: उधार लिए धन के साथ उतनी ही चुकौती की ज़िम्मेदारी जुड़ी होती है, इसलिए § 61 के तहत संपत्ति में कोई वृद्धि नहीं होती। IRS Publication 936 स्पष्ट कहता है — क्योंकि रिवर्स मॉर्गेज को ऋण-अग्रिम माना जाता है, आय नहीं, इसलिए प्राप्त राशि करयोग्य नहीं है — और IRS का वरिष्ठ-नागरिक FAQ इन भुगतानों को loan proceeds कहता है। एकमुश्त राशि, मासिक किश्तें और क्रेडिट-लाइन निकासी — तीनों Form 1040 की आय से बाहर हैं; हाँ, प्राप्ति के माह के बाद बैंक ख़ाते में बची नकदी SSI या Medicaid/Medi-Cal जैसी संपत्ति-आधारित सुविधाओं में संसाधन (resource) गिनी जा सकती है — वह कर से अलग खाता है।

अधिकांश रिवर्स मॉर्गेज HECM होते हैं (12 U.S.C. § 1715z-20; 24 CFR Part 206), जिनका बीमा FHA करता है। प्रत्येक उधारकर्ता की आयु समापन पर कम से कम 62 वर्ष होनी चाहिए (§ 206.33); घर मुख्य निवास होना चाहिए और संपत्ति कर, बीमा व रखरखाव निरंतर चालू रहने चाहिए; आवेदन से पहले HUD-अनुमोदित एजेंसी से स्वतंत्र परामर्श सत्र अनिवार्य है (§ 206.41)। मूल सीमा सबसे कम आयु के उधारकर्ता की आयु, अपेक्षित दर और अधिकतम दावा राशि — मूल्यांकित मूल्य और FHA सीमा में से कम — पर निर्भर है (2026 की सीमा $1,249,125)। प्रारंभिक MIP (अधिकतम दावा राशि का 2%) और वार्षिक MIP (0.5%) सामान्यतः शेष राशि में जुड़ते जाते हैं, इसलिए शेष राशि डिज़ाइन से ही बढ़ती है।

ब्याज की कटौती दो स्वतंत्र कारणों से रुकती है। समय: Publication 936 के अनुसार रिवर्स मॉर्गेज पर अर्जित ब्याज (OID सहित) तब तक कटौती योग्य नहीं है जब तक आप उसे वास्तव में चुका न दें — सामान्यतः पूर्ण चुकौती पर ही। स्वरूप: IRS उस अर्जित ब्याज को home equity debt का ब्याज मानता है, और TCJA के बाद § 163(h)(3) ऐसा ब्याज केवल तब अनुमति देता है जब राशि उसी घर को ख़रीदने, बनाने या सार्थक रूप से सुधारने में लगी हो — जीवन-यापन की निकासी इसमें नहीं आती, इसलिए अधिकांश उधारकर्ताओं के लिए चुकौती का वर्ष वर्षों के जमा ब्याज को एक साथ नहीं खोलता। उदाहरण (दो बार पुनर्गणित): $500,000 के घर पर 0.40 कारक से मूल सीमा $200,000; 6% उदाहरण-दर और 0.5% MIP पर $120,000 निकालने से एक वर्ष में शेष $120,000 + $7,200 + $600 = $127,800 हो जाता है, और उस ब्याज की कटौती $0 है। बाद में $650,000 में बिक्री, $420,000 शेष और $250,000 आधार पर शुद्ध नकदी $230,000, लाभ $650,000 − $250,000 = $400,000, और § 121 की शर्तें पूरी करने वाला एकल उधारकर्ता $250,000 बाहर करके $150,000 पर कर देता है — ऋण-शेष लाभ के सूत्र में कभी आता ही नहीं।

ऋण तब देय होता है जब अंतिम उधारकर्ता का निधन हो जाए, घर बिक या हस्तांतरित हो जाए, वह स्थायी रूप से चला जाए (देखभाल केंद्र में लगातार 12 माह से अधिक रहना भी शामिल है), या कर व बीमा बकाया हो जाए। HECM nonrecourse है: $420,000 शेष के सामने घर का मूल्य $380,000 रह जाए तो $40,000 की कमी FHA बीमा उठाता है — उधारकर्ता की अन्य संपत्ति या उत्तराधिकारियों से कभी वसूली नहीं होती। उत्तराधिकारी चुका कर घर रख सकते हैं, शेष या वर्तमान मूल्यांकन के 95% में से कम राशि पर घर ख़रीद सकते हैं, घर बेचकर ऋण चुकाने के बाद बचा धन रख सकते हैं, या deed in lieu से घर सौंप सकते हैं; उनका आधार ऋण-शेष से निरपेक्ष § 1014 के तहत मृत्यु-तिथि का मूल्य होता है। California भी यही वर्गीकरण अपनाता है — प्राप्त राशि राज्य-आय नहीं है, और ब्याज की कटौती राज्य स्तर पर भी इन्हीं कारणों से विफल रहती है।

*व्यक्तिगत अध्ययन नोट; कर सलाह नहीं। (प्रारंभिक अनुवाद · 待校)*


## 补译增量（2026-11-07 本轮）

### 한국어 보충 (초역 · 初译待校)

보충 1 — 세금이 없다고 복지 자격까지 안전한 것은 아닙니다. 역모기지 수령액은 소득세는 없지만, 인출한 뒤 월을 넘겨 은행 계좌에 남아 있는 잔액은 SSI·Medicaid(캘리포니아 Medi-Cal) 같은 자산 심사형 복지의 자원(resource) 산정에 들어갈 수 있습니다. 세법의 장부와 복지의 장부는 별개이므로, 해당 복지를 받는 분은 인출 리듬을 따로 설계해야 합니다. 또 다른 함정: 받은 돈을 자녀에게 넘기면 그 단계는 증여의 세계로 넘어갑니다. 수령 시 비과세였다는 사실이 증여 단계까지 따라가지 않고, 연간 제외액과 Form 709의 일반 규칙이 그대로 적용됩니다.

보충 2 — 비용의 선행 구조와 만기 후 유예. HECM의 초기 모기지 보험료(upfront MIP)는 최고청구액(maximum claim amount)의 2%로 부과되고, 연 0.5%의 계속 MIP와 이자처럼 대부분 현금이 아니라 대출 잔액에 가산됩니다. 신청 전 HUD 공인 기관의 독립 상담(24 CFR § 206.41)은 형식이 아닙니다. 상담사가 대출기관과 이해관계가 없어야 하고, 비용·대안·배우자에게 미치는 영향까지 다룬 뒤 발급되는 상담 인증서가 없으면 대출 자체가 진행되지 않습니다. 만기가 도래한 뒤에도 상속인에게는 통상 30일의 의사표시 기간이 먼저 주어지고, 실무에서는 매각이나 재융자를 위해 최장 약 6개월까지 연장을 신청할 수 있는 것이 일반적 흐름입니다(서비스 제공자와 HUD의 당시 절차 기준).

### Tiếng Việt bổ sung (bản dịch sơ bộ · 初译待校)

Bổ sung 1 — Không bị thuế không có nghĩa là an toàn với điều kiện hưởng phúc lợi. Tiền nhận từ thế chấp ngược không chịu thuế thu nhập, nhưng số dư rút ra mà còn nằm trong tài khoản ngân hàng qua tháng có thể bị tính vào nguồn lực (resource) khi xét các phúc lợi kiểm tra tài sản như SSI và Medicaid (Medi-Cal của California). Sổ thuế và sổ phúc lợi là hai sổ riêng, nên người đang hưởng phúc lợi phải tính nhịp rút tiền riêng. Một cái bẫy kề bên nữa: khi chuyển số tiền đã nhận cho con cái, bước đó bước sang thế giới tặng cho — việc không bị thuế lúc nhận không đi theo sang bước tặng, và mức loại trừ hằng năm cùng các quy tắc chung của Form 709 vẫn áp dụng nguyên vẹn.

Bổ sung 2 — Cấu trúc chi phí ban đầu và thời gian ân hạn sau khi đến hạn. Phí bảo hiểm thế chấp ban đầu của HECM (upfront MIP) thu ở mức 2% của số tiền yêu cầu tối đa (maximum claim amount), và cùng với MIP hằng năm 0,5% và lãi, phần lớn không trả bằng tiền mặt mà cộng dồn vào dư nợ vay. Buổi tư vấn độc lập của tổ chức được HUD công nhận trước khi nộp đơn (24 CFR § 206.41) không phải thủ tục hình thức: chuyên viên tư vấn không được có xung đột lợi ích với bên cho vay, và nếu không có giấy chứng nhận tư vấn được cấp sau khi đã bàn về chi phí, phương án thay thế và ảnh hưởng tới vợ/chồng, khoản vay không thể tiến hành. Sau khi khoản vay đến hạn, người thừa kế thường trước hết có 30 ngày để bày tỏ ý định, và trong thực tiễn có thể xin gia hạn tới khoảng sáu tháng để lo việc bán nhà hoặc tái tài trợ (theo quy trình hiện hành của bên quản lý khoản vay và HUD).

### हिन्दी पूरक (प्रारंभिक अनुवाद · 初译待校)

पूरक 1 — कर न लगना कल्याण-पात्रता की सुरक्षा नहीं है। रिवर्स मॉर्गेज से मिली राशि पर आयकर नहीं लगता, परंतु निकासी के बाद महीने पार करके बैंक खाते में पड़ा शेष, SSI और Medicaid (California में Medi-Cal) जैसे संपत्ति-जाँच वाले कल्याण कार्यक्रमों में resource के रूप में गिना जा सकता है। कर की बही और कल्याण की बही दो अलग बहियाँ हैं, इसलिए ऐसे लाभ पाने वालों को निकासी की लय अलग से तय करनी होगी। पास का एक और जाल: प्राप्त धन बच्चों को दे देना उपहार की दुनिया में क़दम है — प्राप्ति पर कर-मुक्त होना उपहार-चरण तक साथ नहीं चलता, और वार्षिक बहिष्करण तथा Form 709 के सामान्य नियम वैसे ही लागू होते हैं।

पूरक 2 — अग्रिम लागत संरचना और देयता के बाद की मोहलत। HECM की upfront MIP maximum claim amount की 2% दर से लगती है, और वार्षिक 0.5% MIP व ब्याज की तरह अधिकांशतः नकद न देकर ऋण-शेष में जुड़ती जाती है। आवेदन से पहले HUD-मान्यता प्राप्त संस्था की स्वतंत्र परामर्श बैठक (24 CFR § 206.41) औपचारिकता नहीं है: परामर्शदाता का ऋणदाता से कोई हित-संघर्ष नहीं होना चाहिए, और लागत, विकल्पों और जीवनसाथी पर प्रभाव पर चर्चा के बाद जारी परामर्श प्रमाणपत्र के बिना ऋण आगे बढ़ ही नहीं सकता। ऋण देय हो जाने के बाद भी उत्तराधिकारियों को सामान्यतः पहले 30 दिन का समय अपनी मंशा बताने को मिलता है, और व्यवहार में बिक्री या पुनर्वित्त की व्यवस्था के लिए लगभग छह माह तक की मोहलत माँगी जा सकती है (servicer और HUD की तत्कालीन प्रक्रिया के अनुसार)।
