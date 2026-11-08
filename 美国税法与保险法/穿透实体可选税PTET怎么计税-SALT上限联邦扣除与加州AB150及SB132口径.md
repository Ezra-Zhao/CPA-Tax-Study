# 穿透实体可选税 PTET 怎么计税：SALT 上限、Notice 2020-75 联邦扣除与加州 AB 150／SB 132 口径

> 个人学习笔记，不构成税务建议。Personal study notes, not tax advice.
> 核心依据：IRC § 164(b)(6)–(7)（经 OBBBA, P.L. 119-21, § 70120 修订）；IRS Notice 2020-75；加州 AB 150（2021）与 SB 113（2022）、SB 132（2025），R&TC §§ 17052.10、17052.11、19914；FTB 的 PTE Elective Tax 指引与 Form 3893。

选题说明：本轮原定选题「机会区 Opportunity Zone 怎么计税」经实查仓内已有同题专篇《机会区投资怎么计税：第 1400Z 条合格机会区、递延确认与十年排除》（六语齐套，递延、基数步升与 2026 年后新规衔接俱全），按不重题规则换为同板块全仓从未成篇的本篇——穿透实体可选税（pass-through entity tax, PTET，又称 PTE elective tax）。它和本仓《合伙与 S 公司怎么计税》分工：那篇讲穿透的常态计税，本篇只讲一件事——州所得税本来由个人缴、被个人 SALT 上限卡住，改由实体层面缴，为什么联邦就能全额扣，以及加州这套选举的现行规则与 2026 年起的新变化。

先给结论：PTET 不是免税，是换缴费主体。合伙或 S 公司在州里选了这条通道，州税由实体缴、实体在联邦层面把这笔税当经营成本扣掉，所有者再在州税表上拿等额抵免——同一笔州税，个人缴时被上限卡死，实体缴时全额进扣除。联邦靠山是 Notice 2020-75；加州靠山是 AB 150 建制、SB 132 把它延到 2030 税年并放宽了 6 月预缴的死线。

## 中文主文

### 一、病根：SALT 上限只卡个人，不卡实体

州与地方税（SALT）扣除的上限写在 IRC § 164(b)：2018–2025 年是每年 10,000 美元的平顶（TCJA 口径），只作用于个人的逐项扣除（Schedule A）——你在 Schedule A 上能扣的州所得税、销售税与个人财产税，合起来不超过这个数。OBBBA（P.L. 119-21, § 70120）把上限改成新 § 164(b)(7) 的分年表：2025 年 40,000 美元、2026 年 40,400 美元（夫妻分开报减半），此后至 2029 年每年再涨 1%，2030 年起回到 10,000 美元；同时设高收入递减——2026 年修正 AGI 超过 505,000 美元（2025 年为 500,000 美元）的部分，按超出额的 30% 削减上限，但削到 10,000 美元为止（本地复算触底点：（40,400 − 10,000）÷ 30% ＝ 101,333.33，505,000 ＋ 101,333.33 ＝ 606,333.33，即 2026 年 MAGI 约达 606,333 美元时上限触底 10,000 美元，与公开口径一致）。

关键在上限的射程：它卡的是「个人」在 Schedule A 上的扣除，从来不管实体在经营里发生的税。经营性税费本来就走经营扣除、不进 Schedule A——PTET 钻的正是这条分界：把州所得税的缴费主体从个人换成实体，税的性质就从个人逐项扣除变成实体经营支出。上限涨到 40,400 美元之后 PTET 并没有过时：MAGI 一过递减线，上限迅速塌回 10,000 美元；房产税本身就可能占满上限；所有者边际税率越高，实体扣除越值钱——这三类人仍是 PTET 的主用户。

### 二、联邦怎么认：Notice 2020-75 的三句话

IRS 在 2020 年 11 月发 Notice 2020-75，预告将出台拟议法规，并明确在法规出台前可按公告口径依赖执行。要点三句：

1. 合伙或 S 公司向州（或地方）缴纳的、由实体自身承担的所得税款，属于公告定义的「指定所得税付款」（Specified Income Tax Payments）——包括实体按州法选择在实体层面缴的这笔税。
2. 这笔付款由实体在**付款当年**计算非单独列报收入（nonseparately stated income or loss）时扣除，也就是先在实体层面扣掉、再把净额经 Schedule K-1 穿给所有者；它不按 § 702／§ 1366 单独过给个人。
3. 正因为不落到个人头上，计算个人 SALT 上限时这笔税**不计入**——上限对它不起作用。

边界也要记清：公告管的是对实体征收的所得税；所有者个人层面的预估税、工资预扣不在内；实体替某个所有者代缴但性质上仍是个人税款的安排，不当然落入公告口径。OBBBA 立法过程中众议院版本曾有限制 PTET 的条款，成法文本（§ 70120）未采纳，Notice 2020-75 的扣除口径在现行法下完整保留——引用时以成法文本与公告原文为准，不引用未成法的草案口径。

### 三、机制四步：选举、缴税、联邦扣除、州抵免

以加州为例，一次完整的 PTET 循环是四步（各州细节不同，骨架相同）：

1. **实体作选举**：合格实体在实体税表上按年作出选举（annual election），只对自愿同意的所有者（consenting owners）的那部分收入选。
2. **实体缴税**：实体按州定税率对「合格净收入」（同意的所有者的应税份额、分配份额与保证支付中归属本州的部分）缴税；加州税率 9.3%（见第五节）。
3. **联邦扣除**：实体缴的税在联邦实体层面扣除，K-1 上所有者的收入份额已经是扣完这笔税之后的净额——所有者联邦少报的收入，就是扣除落点，不需要、也不能在 Schedule A 上再扣同一笔。
4. **州抵免**：所有者在州个人税表上按自己份额拿到等额抵免（credit），冲自己这笔穿透收入的州税；州层面因此不重复征税——实体缴过、个人抵掉，州只收一次。

时点纪律：联邦扣除落在**实际付款的年度**（Notice 2020-75 的付款年口径）。现金制实体 12 月底前没把钱缴出去，当年就没有这笔扣除；选举、付款、抵免分属三个环节，错位一年，账就串年。

### 四、算例：同一笔州税，两种缴法的联邦差

**算例一（基本盘）**：加州一合伙企业的合格净收入 400,000 美元，两名个人合伙人各占一半，均同意选举。实体缴 PTET ＝ 400,000 × 9.3% ＝ 37,200 美元（本地复算：400,000 × 0.093 ＝ 37,200，无误）。联邦层面，这 37,200 美元在实体扣除，每名合伙人 K-1 收入少 37,200 ÷ 2 ＝ 18,600 美元；按 37% 边际税率，每人省联邦税 18,600 × 37% ＝ 6,882 美元（本地复算：18,600 × 0.37 ＝ 6,882，无误），两人合计 13,764 美元。州层面，每人拿到 18,600 美元的加州抵免冲自己的州税，州税总负担不变。对照不选举：每人 18,600 美元州税只能走 Schedule A，若两人的 SALT 上限已被房产税等占满，这笔扣除的联邦价值就是 0——13,764 美元的差，全在缴费主体这一步。

**算例二（SB 132 后的预缴减额）**：某实体 2026 年 6 月 15 日前应预缴 20,000 美元，只缴了 8,000 美元，缺口 12,000 美元。按 SB 132 后的新规则（见第五节），选举不因此失效，但所有者抵免要减少缺口的 12.5%：减少额 ＝ 12,000 × 12.5% ＝ 1,500 美元（本地复算：12,000 × 0.125 ＝ 1,500，无误），按各所有者份额分摊。省下的现金流与丢掉的 1,500 美元抵免，哪头划算要提前算——这正是新规把「漏缴即全废」改成「漏缴打折」后的新算术。

### 五、加州口径：AB 150 建制、SB 132 延长与放宽

**建制**：AB 150（2021 年 7 月签署）给加州建了这套选举，法源两条腿——实体税在 R&TC Part 10.4 一带（选举与缴纳，§ 19914 是缴纳时点条），所有者抵免在 R&TC § 17052.10（适用于 2021 年起、2026 年前开始的税年）。SB 113（2022）做过一轮放宽（保证支付纳入合格净收入、部分所有者资格放宽等，细节以 FTB 当期指引为准）。

**谁能选**：合格实体是合伙（普通合伙、有限合伙、LLP）、按合伙课税的 LLC 与 S 公司；公开交易合伙、所有者里含合伙企业等嵌套情形受限制，公司所有者不是「合格纳税人」——只有个人、信托、遗产及 disregarded 单成员 LLC 等合格所有者的份额进合格净收入，且须该所有者同意。独资与 disregarded 单成员 LLC 本身不能作选举实体（它在联邦上不是独立于个人的实体，无从换主体）。选举按年作、在实体的原始税表上作出，作出后对该年不可撤销（以 FTB 当期说明为准）。

**税率与抵免**：税率 9.3%，对合格净收入征收。所有者抵免等于其实体已缴税款中归属自己份额的金额，不可退还（nonrefundable），用不完可结转 5 年。抵免只冲州税；实体的 $800 年税、LLC 的总收入 fee 等其他州费与 PTET 是两笔账，不受影响。

**两段式缴纳与 6 月死线（本题眼）**：自 2022 税年起分两段——第一笔在选举当年 6 月 15 日或之前缴，金额为「上年 PTET 的 50%」与「1,000 美元」两者取高，用 Form 3893（Pass-Through Entity Elective Tax Payment Voucher）缴付；第二笔在实体原始税表到期日或之前补齐差额。2026 年前的旧规则是硬死线：6 月该缴未缴，当年选举直接作废。**SB 132（2025 年 6 月签署）把制度延长并改了这一条**：新设 R&TC § 17052.11，适用于 2026 年 1 月 1 日起、2031 年 1 月 1 日前开始的税年（即 2026–2030 税年）；在此期间，6 月预缴漏缴或少缴不再让选举失效，改为按 § 17052.11 把所有者抵免减少「未缴金额中该所有者份额的 12.5%」（算例二）。实务结论没变——6 月 15 日仍是每年先排进日历的日期，只是漏缴的代价从「全废」降成了「打折」。SB 132 的延长另以联邦 SALT 上限存续为背景条件，引用时以 FTB 的 SB 132 说明页为准。

### 六、什么时候不划算：五个先算的账

1. **抵免用不完**：所有者州税负担低于抵免额、又无其他州税可冲时，不可退还抵免只能 5 年内结转，过期作废——低州税年份先算抵免吸收能力。
2. **边际税率太低**：联邦扣除的价值等于税额乘边际税率；所有者落在低档、或当年本就没多少联邦税时，省下的可能盖不过合规与现金流成本。
3. **外州抵免衔接**：所有者是外州居民、或实体收入来自多州时，「居民州认不认这笔实体税抵免」各州口径不一，有的州早期不认 PTET 抵免——跨州先逐州核，别假设全认。
4. **QBI 连动**：实体层面的扣除会压低经 K-1 穿出的合格经营收入（QBI），§ 199A 的 20% 扣除基数跟着变小；高收入、卡在 SSTB 与工资门槛附近的所有者，净收益要把 199A 的损失一并算进去再下结论。
5. **现金流与预缴**：6 月先掏一笔、余额次年春季补齐，实体现金流要排得出；新设实体第一年没有「上年 50%」可参照，预缴就是 1,000 美元起步，别按全额预缴吓自己、也别忘了缴。

**来源与依据**：IRC § 164(b)(6)–(7)（SALT 上限与 OBBBA § 70120 的 2025 年 40,000／2026 年 40,400 美元、MAGI 505,000 美元起按 30% 递减、10,000 美元地板、2030 年回落口径）；IRS Notice 2020-75（指定所得税付款的实体层面扣除与不计入个人上限，2020-11-09 发布）；加州 AB 150（2021，建制，R&TC § 17052.10 抵免与 Part 10.4 实体税）、SB 113（2022，放宽）、SB 132（2025，新增 R&TC § 17052.11、延长至 2030 税年、§ 19914(b) 的漏缴不废选举与 12.5% 抵免削减）；FTB 的 PTE Elective Tax 帮助页与 Form 3893 说明（6 月 15 日预缴的孰高规则与两段式缴纳）。各州 PTET 的税率、抵免形态（抵免型／排除型）与期限互不相同，跨州适用以各州当期官方指引为准。

*声明：个人学习笔记，不构成税务建议。具体选举与预缴安排请以 FTB 与各州当期指引为准，动手前先咨询持牌 CPA。*

---

## English

A pass-through entity tax (PTET) does not eliminate state tax; it changes who pays it. The partnership or S corporation elects to pay state income tax at the entity level, deducts that tax federally as a business cost, and the owners claim a state credit for their share — the same state tax that would be strangled by the individual SALT cap when paid personally is fully deducted when paid by the entity.

**The problem it solves.** The § 164(b) SALT cap limits an individual's Schedule A deduction for state and local taxes. OBBBA (P.L. 119-21, § 70120) rewrote the cap in new § 164(b)(7): $40,000 for 2025 and $40,400 for 2026 (half if married filing separately), rising 1% a year through 2029 and reverting to $10,000 in 2030, with a phase-down — for 2026, the cap is cut by 30% of modified AGI above $505,000, but not below $10,000 (the floor is reached at about $505,000 + ($40,400 − $10,000) ÷ 30% ≈ $606,333 of MAGI). The cap only ever reached personal itemized deductions, never an entity's business deductions; PTET walks through that gap. The higher cap did not retire PTET: taxpayers in the phase-down, taxpayers whose property tax alone fills the cap, and high-bracket owners still gain.

**The federal blessing: Notice 2020-75.** The IRS announced that a partnership's or S corporation's payment of a state income tax imposed on the entity — a "Specified Income Tax Payment" — is deducted by the entity in computing its nonseparately stated income for the year of payment. It is not passed through separately to the owners under § 702 or § 1366, and it is not taken into account in applying the SALT cap to any individual. The enacted OBBBA text left this treatment intact (a House-passed proposal to restrict PTET was not enacted).

**The four steps (California form).** (1) The qualified entity makes an annual election on its return, covering only consenting owners' shares. (2) The entity pays tax on qualified net income — in California, 9.3%. (3) Federally, the K-1 income reaching each owner is already net of the entity tax; the deduction lives at the entity level and the same tax may not be deducted again on Schedule A. (4) Each owner claims a state credit for their share, so the state collects once. Timing matters: the federal deduction belongs to the year the tax is actually paid.

**Worked examples.** A California partnership has $400,000 of qualified net income and two equal individual partners. Entity tax: $400,000 × 9.3% = $37,200. Each partner's K-1 income drops by $18,600; at a 37% marginal rate each saves $18,600 × 37% = $6,882 of federal tax, $13,764 combined, while each also receives an $18,600 California credit. Without the election, if each partner's SALT cap were already filled by property tax, the federal value of paying that state tax personally would be $0. Second example, under the post-SB 132 rule: an entity that owed a $20,000 June 15 prepayment for 2026 paid only $8,000; the $12,000 shortfall no longer kills the election, but the owners' credits shrink by $12,000 × 12.5% = $1,500.

**California specifics.** AB 150 (2021) created the election — entity tax in R&TC Part 10.4 (see § 19914) and the owner credit in § 17052.10 — and SB 113 (2022) loosened several rules. Qualified entities are partnerships, LLCs taxed as partnerships, and S corporations; publicly traded partnerships and certain tiered structures are restricted, corporate owners are not qualified taxpayers, and a disregarded single-member LLC cannot itself elect. The credit equals the owner's share of tax paid, is nonrefundable, and carries forward five years. Payment is two-step: by June 15 of the election year, the greater of 50% of the prior year's PTET or $1,000 (Form 3893 voucher), with the balance due by the entity's original return due date. Before 2026, missing the June payment voided the election. SB 132 (signed June 2025) added § 17052.11 and extended the regime to taxable years beginning in 2026 through 2030: a missed or short June payment now only reduces credits by 12.5% of each owner's share of the shortfall — June 15 remains the first date on the calendar, but the price of missing it fell from forfeiture to a haircut.

**When it does not pay.** Credits the owner cannot absorb within five years expire; a low federal bracket shrinks the deduction's value; a resident state may not credit entity-level tax paid to another state (check state by state); the entity deduction also reduces QBI, so the § 199A cost must be netted for owners near the SSTB and wage thresholds; and the June prepayment is a real cash-flow commitment.

*Personal study notes, not tax advice. State PTET regimes differ in rate, credit design, and deadlines; confirm the current-year FTB and state guidance before electing.*

---

## Español

El impuesto electivo de las entidades transparentes (PTET) no elimina el impuesto estatal: cambia quién lo paga. La sociedad (partnership) o la corporación S elige pagar el impuesto estatal sobre la renta a nivel de entidad, lo deduce federalmente como costo del negocio y los socios reclaman un crédito estatal por su parte — el mismo impuesto que, pagado personalmente, quedaría ahogado por el tope SALT individual.

**El problema.** El tope de § 164(b) limita la deducción del Anexo A por impuestos estatales y locales. La ley OBBBA (P.L. 119-21, § 70120) lo reescribió en el nuevo § 164(b)(7): $40.000 en 2025 y $40.400 en 2026 (la mitad si se declara por separado), con subidas del 1% anual hasta 2029 y retorno a $10.000 en 2030, además de una reducción progresiva: en 2026 el tope baja un 30% del MAGI que supere $505.000, sin bajar de $10.000 (el suelo se alcanza hacia los $606.333 de MAGI: $505.000 + ($40.400 − $10.000) ÷ 30%). El tope nunca alcanzó las deducciones empresariales de una entidad, solo las personales detalladas; el PTET pasa por esa rendija. Ni siquiera con el tope más alto el PTET quedó obsoleto: quien está en la zona de reducción, quien ya llena el tope con el impuesto predial o quien tributa en tramos altos sigue ganando.

**El respaldo federal: Notice 2020-75.** El IRS anunció que el pago por una partnership o corporación S de un impuesto estatal impuesto a la propia entidad (Specified Income Tax Payment) lo deduce la entidad al calcular su ingreso no declarado por separado (nonseparately stated income) en el año del pago; no se traslada por separado a los socios vía §§ 702 o 1366 ni se toma en cuenta al aplicar el tope SALT a ningún individuo. El texto final de OBBBA dejó intacto este tratamiento.

**Los cuatro pasos (versión California).** (1) La entidad calificada hace una elección anual en su declaración, solo sobre las participaciones de los socios que consienten. (2) La entidad paga sobre el ingreso neto calificado — en California, el 9,3%. (3) A nivel federal, el ingreso del K-1 ya llega neto del impuesto de la entidad; la misma cantidad no puede deducirse otra vez en el Anexo A. (4) Cada socio reclama un crédito estatal por su parte: el estado cobra una sola vez. El momento importa: la deducción federal es del año en que el impuesto se paga efectivamente.

**Ejemplos.** Una partnership de California con $400.000 de ingreso neto calificado y dos socios individuales al 50%: impuesto de entidad $400.000 × 9,3% = $37.200. El K-1 de cada socio baja $18.600; al 37% marginal, cada uno ahorra $18.600 × 37% = $6.882 federales, $13.764 en total, y cada uno recibe además un crédito californiano de $18.600. Sin elección, si el tope SALT ya estuviera lleno con el impuesto predial, el valor federal de pagar ese impuesto personalmente sería $0. Segundo ejemplo, con la regla posterior a SB 132: una entidad que debía prepagar $20.000 antes del 15 de junio de 2026 pagó solo $8.000; el faltante de $12.000 ya no anula la elección, pero los créditos de los socios se reducen en $12.000 × 12,5% = $1.500.

**California en detalle.** AB 150 (2021) creó la elección — impuesto de entidad en la Parte 10.4 del R&TC (véase § 19914) y crédito del socio en § 17052.10 — y SB 113 (2022) flexibilizó varias reglas. Son entidades calificadas las partnerships, las LLC gravadas como partnership y las corporaciones S; los socios corporativos no son contribuyentes calificados y una LLC unipersonal disregarded no puede elegir por sí misma. El crédito es no reembolsable, con arrastre de cinco años. El pago es en dos pasos: antes del 15 de junio del año de la elección, el mayor entre el 50% del PTET del año anterior o $1.000 (comprobante Form 3893), y el resto a la fecha de vencimiento original de la declaración de la entidad. Antes de 2026, no pagar en junio anulaba la elección. SB 132 (junio de 2025) añadió § 17052.11 y extendió el régimen a los años fiscales iniciados en 2026 y hasta 2030: el pago de junio faltante o insuficiente ahora solo reduce los créditos un 12,5% de la parte del faltante de cada socio.

**Cuándo no conviene.** Créditos que no se absorben en cinco años caducan; un tramo federal bajo reduce el valor de la deducción; el estado de residencia puede no reconocer el impuesto pagado a nivel de entidad en otro estado; la deducción de la entidad también reduce el QBI, coste § 199A que debe netearse; y el prepago de junio es un compromiso real de liquidez.

*Notas personales de estudio; no constituyen asesoría fiscal.*

---

## 한국어 (초역, 원어민 감수 대기)

PTET(통과실체 선택세)는 주세를 없애는 제도가 아니라 내는 주체를 바꾸는 제도입니다. 파트너십이나 S법인이 주 소득세를 법인·실체 차원에서 내기로 선택하면, 그 세금은 연방에서 사업 비용으로 공제되고 소유자는 주 신고에서 자기 몫만큼 세액공제를 받습니다. 개인이 내면 SALT 상한에 막히는 같은 세금이, 实体가 내면 전액 공제로 바뀝니다.

**병근은 SALT 상한입니다.** § 164(b)의 상한은 개인의 Schedule A 항목별 공제만 제한합니다. OBBBA(P.L. 119-21, § 70120)는 새 § 164(b)(7)로 상한을 다시 썼습니다: 2025년 40,000달러, 2026년 40,400달러(부부 별도 신고 시 절반), 2029년까지 매년 1% 인상, 2030년부터 10,000달러로 복귀. 여기에 고소득 감액이 붙어, 2026년에는 MAGI가 505,000달러를 넘는 부분의 30%만큼 상한이 줄되 10,000달러 아래로는 내려가지 않습니다(바닥 도달점: 505,000 + (40,400 − 10,000) ÷ 30% ≈ 606,333달러). 상한이 올라도 PTET가 사라지지는 않습니다. 감액 구간에 있는 사람, 재산세만으로 상한이 차는 사람, 한계세율이 높은 소유자에게는 여전히 값어치가 큽니다.

**연방의 근거는 Notice 2020-75입니다.** IRS는 파트너십·S법인이 实体 자체에 부과된 주 소득세(Specified Income Tax Payment)를 낸 경우, 그 금액을 낸 해의 비별도표시 소득(nonseparately stated income) 계산에서 공제한다고 밝혔습니다. §§ 702·1366으로 소유자에게 따로 넘기지 않고, 개인의 SALT 상한 적용 때도 계산에 넣지 않습니다. OBBBA 최종 성문은 이 취급을 그대로 두었습니다.

**네 단계(캘리포니아형).** (1) 적격 实体가 신고서에서 매년 선택(annual election)을 하되, 동의한 소유자의 몫에만 적용합니다. (2) 实体가 적격 순소득에 세금을 냅니다 — 캘리포니아 세율은 9.3%입니다. (3) 연방에서는 K-1 소득이 이미 이 세금을 뺀 순액으로 소유자에게 가므로, 같은 세금을 Schedule A에서 다시 공제할 수 없습니다. (4) 소유자는 주 개인 신고에서 자기 몫의 세액공제를 받아, 주는 한 번만 걷습니다. 연방 공제는 실제로 낸 해에 생기므로 시점이 중요합니다.

**예시.** 캘리포니아 파트너십의 적격 순소득 400,000달러, 개인 파트너 두 명이 절반씩이면 实体세는 400,000 × 9.3% = 37,200달러입니다. 각 파트너의 K-1 소득은 18,600달러 줄고, 한계세율 37%라면 각자 연방세가 18,600 × 37% = 6,882달러, 합계 13,764달러 절약되며, 각자 캘리포니아 공제 18,600달러도 받습니다. 선택하지 않고 SALT 상한이 이미 재산세로 찼다면, 개인이 낸 주세의 연방 가치는 0입니다. 두 번째 예시(SB 132 이후): 2026년 6월 15일까지 20,000달러를 선납해야 했는데 8,000달러만 낸 경우, 부족분 12,000달러 때문에 선택이 무효가 되지는 않지만 소유자 공제가 12,000 × 12.5% = 1,500달러 줄어듭니다.

**캘리포니아 세부.** AB 150(2021)이 제도를 만들었고(实体세는 R&TC Part 10.4, § 19914 참조; 소유자 공제는 § 17052.10), SB 113(2022)이 일부를 완화했습니다. 적격 实体는 파트너십, 파트너십으로 과세되는 LLC, S법인이며, 회사 소유자는 적격 납세자가 아니고 disregarded 1인 LLC는 스스로 선택할 수 없습니다. 공제는 환급 불가, 5년 이월됩니다. 납부는 두 단계로, 선택 연도 6월 15일까지 전년 PTET의 50%와 1,000달러 중 큰 금액(Form 3893 바우처), 나머지는 实体 원래 신고기한까지 냅니다. 2026년 전에는 6월 납부를 놓치면 선택 자체가 무효였지만, SB 132(2025년 6월 서명)가 § 17052.11을 신설해 제도를 2026–2030 과세연도까지 연장하면서, 미납·부족 시에는 선택이 유지되고 공제만 소유자별 부족 지분의 12.5%만큼 줄어드는 것으로 바뀌었습니다.

**손해가 될 때.** 5년 안에 다 쓰지 못한 공제는 소멸하고, 연방 한계세율이 낮으면 공제 가치가 작아지며, 거주 주가 타주 实体세 공제를 인정하지 않을 수 있고, 实体 공제는 QBI를 줄여 § 199A 비용도 함께 계산해야 하며, 6월 선납은 실제 현금흐름 부담입니다.

*개인 학습 노트이며 세무 조언이 아닙니다. (초역, 원어민 감수 대기)*

---

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

Thuế tự chọn của thực thể xuyên suốt (PTET) không xóa thuế bang; nó đổi chủ thể nộp thuế. Partnership hoặc S corporation chọn nộp thuế thu nhập bang ở cấp thực thể, khấu trừ khoản thuế đó ở cấp liên bang như chi phí kinh doanh, và các chủ sở hữu nhận tín dụng thuế bang theo phần của mình — cùng một khoản thuế bang, nếu nộp cá nhân sẽ bị trần SALT chặn, còn nộp qua thực thể thì được khấu trừ toàn bộ.

**Gốc vấn đề: trần SALT.** Trần tại § 164(b) chỉ giới hạn khấu trừ liệt kê (Schedule A) của cá nhân. OBBBA (P.L. 119-21, § 70120) viết lại trần trong § 164(b)(7) mới: 40.000 đô la cho 2025 và 40.400 cho 2026 (một nửa nếu vợ chồng khai riêng), tăng 1% mỗi năm đến 2029 và trở về 10.000 từ 2030, kèm giảm dần theo thu nhập — năm 2026, trần bị cắt 30% phần MAGI vượt 505.000 đô la, nhưng không xuống dưới 10.000 (điểm chạm sàn khoảng 505.000 + (40.400 − 10.000) ÷ 30% ≈ 606.333 đô la MAGI). Trần chưa bao giờ chạm tới khấu trừ kinh doanh của thực thể; PTET đi qua khe đó. Trần cao hơn cũng không làm PTET hết thời: người nằm trong vùng giảm dần, người có thuế bất động sản đã lấp đầy trần, và chủ sở hữu ở khung thuế cao vẫn có lợi.

**Căn cứ liên bang: Notice 2020-75.** IRS tuyên bố khoản thuế thu nhập bang đánh lên chính thực thể (Specified Income Tax Payment) do partnership hoặc S corporation nộp được thực thể khấu trừ khi tính thu nhập không liệt kê riêng (nonseparately stated income) trong năm nộp. Khoản này không chuyển riêng cho chủ sở hữu theo §§ 702 hay 1366 và không tính khi áp trần SALT cho bất kỳ cá nhân nào. Văn bản OBBBA đã ban hành giữ nguyên cách xử lý này.

**Bốn bước (mẫu California).** (1) Thực thể đủ điều kiện thực hiện lựa chọn hằng năm trên tờ khai, chỉ cho phần của các chủ sở hữu đồng ý. (2) Thực thể nộp thuế trên thu nhập ròng đủ điều kiện — California thu 9,3%. (3) Ở cấp liên bang, thu nhập K-1 đến tay chủ sở hữu đã trừ khoản thuế của thực thể; không được khấu trừ lại cùng khoản thuế đó ở Schedule A. (4) Mỗi chủ sở hữu nhận tín dụng thuế bang theo phần của mình, nên bang chỉ thu một lần. Thời điểm rất quan trọng: khấu trừ liên bang thuộc về năm thực tế nộp tiền.

**Ví dụ.** Một partnership ở California có thu nhập ròng đủ điều kiện 400.000 đô la, hai đối tác cá nhân mỗi người một nửa: thuế thực thể = 400.000 × 9,3% = 37.200 đô la. Thu nhập K-1 của mỗi người giảm 18.600; ở khung thuế biên 37%, mỗi người tiết kiệm 18.600 × 37% = 6.882 đô la thuế liên bang, tổng 13.764, và mỗi người còn nhận tín dụng California 18.600. Nếu không chọn và trần SALT của mỗi người đã bị thuế bất động sản lấp đầy, giá trị liên bang của việc tự nộp khoản thuế bang đó bằng 0. Ví dụ hai, theo quy tắc sau SB 132: thực thể phải nộp trước 20.000 đô la trước 15 tháng 6 năm 2026 nhưng chỉ nộp 8.000; phần thiếu 12.000 không còn làm mất hiệu lực lựa chọn, nhưng tín dụng của các chủ sở hữu bị giảm 12.000 × 12,5% = 1.500 đô la.

**Chi tiết California.** AB 150 (2021) lập ra chế độ này — thuế thực thể tại R&TC Part 10.4 (xem § 19914), tín dụng của chủ sở hữu tại § 17052.10 — và SB 113 (2022) nới lỏng một số quy tắc. Thực thể đủ điều kiện gồm partnership, LLC bị đánh thuế như partnership và S corporation; chủ sở hữu là công ty không phải người nộp thuế đủ điều kiện, và LLC một thành viên disregarded không tự lựa chọn được. Tín dụng không hoàn lại, chuyển tiếp năm năm. Nộp tiền hai đợt: trước 15 tháng 6 của năm lựa chọn, nộp số lớn hơn giữa 50% PTET năm trước và 1.000 đô la (voucher Form 3893), phần còn lại hạn chót là ngày hết hạn tờ khai gốc của thực thể. Trước 2026, bỏ lỡ đợt nộp tháng 6 là mất lựa chọn. SB 132 (ký tháng 6 năm 2025) thêm § 17052.11 và gia hạn chế độ cho các năm thuế bắt đầu trong 2026 đến 2030: nộp thiếu tháng 6 nay chỉ làm giảm tín dụng 12,5% phần thiếu của từng chủ sở hữu.

**Khi nào không đáng.** Tín dụng không dùng hết trong năm năm sẽ hết hạn; khung thuế liên bang thấp làm giảm giá trị khấu trừ; bang cư trú có thể không công nhận tín dụng cho thuế cấp thực thể nộp ở bang khác; khấu trừ của thực thể cũng làm giảm QBI nên phải tính cả chi phí § 199A; và khoản nộp trước tháng 6 là cam kết dòng tiền thật.

*Ghi chú học tập cá nhân, không phải tư vấn thuế. (bản dịch sơ bộ, chờ hiệu đính)*

---

## हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

पारदर्शी इकाई का वैकल्पिक कर (PTET) राज्य कर समाप्त नहीं करता; वह भुगतानकर्ता बदल देता है। Partnership या S corporation राज्य आयकर को इकाई-स्तर पर चुकाना चुनती है, उस कर को संघीय स्तर पर व्यावसायिक लागत के रूप में काटती है, और स्वामी अपने हिस्से का राज्य credit लेते हैं — वही राज्य कर जो व्यक्तिगत रूप से चुकाने पर SALT सीमा में अटकता, इकाई द्वारा चुकाने पर पूरी तरह कट जाता है।

**जड़: SALT सीमा।** § 164(b) की सीमा केवल व्यक्ति की Schedule A मदवार कटौती को सीमित करती है। OBBBA (P.L. 119-21, § 70120) ने नया § 164(b)(7) जोड़कर सीमा फिर लिखी: 2025 में 40,000 डॉलर, 2026 में 40,400 डॉलर (अलग दाख़िल करने वाले दंपति के लिए आधी), 2029 तक हर वर्ष 1% वृद्धि और 2030 से फिर 10,000 डॉलर; साथ में आय-आधारित कमी — 2026 में MAGI 505,000 डॉलर से ऊपर के हिस्से पर सीमा 30% घटती है, पर 10,000 डॉलर से नीचे नहीं (तल-बिंदु लगभग 505,000 + (40,400 − 10,000) ÷ 30% ≈ 606,333 डॉलर MAGI)। यह सीमा इकाई की व्यावसायिक कटौतियों को कभी छूती नहीं थी; PTET उसी दरार से निकलता है। सीमा बढ़ने के बाद भी PTET अप्रासंगिक नहीं हुआ: कमी-क्षेत्र वाले, केवल संपत्ति-कर से सीमा भर जाने वाले और ऊँचे कर-दर वाले स्वामियों को अब भी लाभ है।

**संघीय आधार: Notice 2020-75।** IRS ने घोषित किया कि partnership या S corporation द्वारा इकाई पर ही लगाए गए राज्य आयकर का भुगतान (Specified Income Tax Payment) इकाई अपने nonseparately stated income की गणना में, भुगतान के वर्ष में, काटती है। यह §§ 702 या 1366 से स्वामियों को अलग से नहीं जाता और किसी व्यक्ति पर SALT सीमा लगाते समय गिना भी नहीं जाता। अधिनियमित OBBBA पाठ ने यह व्यवहार अक्षुण्ण रखा।

**चार चरण (California रूप)।** (1) योग्य इकाई अपने रिटर्न पर वार्षिक चुनाव करती है, केवल सहमत स्वामियों के हिस्सों पर। (2) इकाई योग्य शुद्ध आय पर कर चुकाती है — California में दर 9.3% है। (3) संघीय स्तर पर प्रत्येक स्वामी की K-1 आय पहले से इकाई-कर घटाकर आती है; वही कर Schedule A पर दोबारा नहीं कट सकता। (4) हर स्वामी अपने हिस्से का राज्य credit लेता है, इसलिए राज्य एक ही बार वसूलता है। समय निर्णायक है: संघीय कटौती वास्तविक भुगतान के वर्ष की है।

**उदाहरण।** California की partnership की योग्य शुद्ध आय 400,000 डॉलर, दो व्यक्तिगत साझेदार आधे-आधे: इकाई कर = 400,000 × 9.3% = 37,200 डॉलर। हर साझेदार की K-1 आय 18,600 घटती है; 37% सीमांत दर पर हर एक 18,600 × 37% = 6,882 डॉलर संघीय कर बचाता है, कुल 13,764, और हर एक को 18,600 डॉलर California credit भी मिलता है। चुनाव न हो और SALT सीमा संपत्ति-कर से पहले ही भरी हो तो वही राज्य कर व्यक्तिगत रूप से चुकाने का संघीय मूल्य 0 होता। दूसरा उदाहरण, SB 132 के बाद का नियम: 2026 में 15 जून तक 20,000 डॉलर अग्रिम देना था, दिए केवल 8,000; 12,000 की कमी अब चुनाव रद्द नहीं करती, किंतु स्वामियों का credit 12,000 × 12.5% = 1,500 डॉलर घट जाता है।

**California विवरण।** AB 150 (2021) ने यह व्यवस्था बनाई — इकाई कर R&TC Part 10.4 में (§ 19914 देखें), स्वामी credit § 17052.10 में — और SB 113 (2022) ने कई नियम ढीले किए। योग्य इकाइयाँ हैं: partnerships, partnership की तरह कर लगने वाली LLCs और S corporations; corporative स्वामी योग्य करदाता नहीं हैं और disregarded एकल-सदस्य LLC स्वयं चुनाव नहीं कर सकती। Credit ग़ैर-वापसीयोग्य (nonrefundable) है, पाँच वर्ष आगे ले जाया जा सकता है। भुगतान दो चरणों में: चुनाव-वर्ष की 15 जून तक पिछले वर्ष के PTET के 50% या 1,000 डॉलर में से बड़ा (Form 3893 voucher), शेष इकाई के मूल रिटर्न की देय तिथि तक। 2026 से पहले जून का भुगतान चूकने पर चुनाव ही समाप्त हो जाता था। SB 132 (जून 2025 में हस्ताक्षरित) ने § 17052.11 जोड़कर व्यवस्था को 2026 से 2030 तक शुरू होने वाले कर-वर्षों तक बढ़ाया: अब जून की चूक या कमी पर केवल credit हर स्वामी के कमी-हिस्से के 12.5% से घटता है।

**कब लाभ नहीं।** पाँच वर्ष में अवशोषित न हो सका credit समाप्त हो जाता है; निम्न संघीय दर कटौती का मूल्य घटाती है; निवास-राज्य दूसरे राज्य के इकाई-स्तरीय कर का credit मानने से इनकार कर सकता है; इकाई की कटौती QBI भी घटाती है, इसलिए § 199A लागत साथ जोड़नी चाहिए; और जून का अग्रिम भुगतान वास्तविक नक़दी-प्रवाह प्रतिबद्धता है।

*व्यक्तिगत अध्ययन नोट, कर सलाह नहीं। (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)*


## 补译增量（2026-11-08 追加：韩／越／印三语各补 2 项细节增量，与中文主文细节对齐，正文原有段落未改动）

### 한국어 보충 (초역 · 初译待校)

보충 1 (Notice 2020-75의 경계): 이 안내가 다루는 것은 실체 자체에 부과된 소득세뿐입니다. 소유자 개인 차원의 추정세 납부나 급여 원천징수는 여기에 들어가지 않으며, 실체가 특정 소유자를 대신해 납부했더라도 성격상 여전히 개인의 세금인 금액은 당연히 이 안내의 범위에 들지 않습니다. 또 OBBBA 입법 과정에서 PTET를 제한하려던 하원안 조항은 성문(§ 70120)에 채택되지 않았으므로, 채택되지 않은 초안의 기준을 인용해서는 안 됩니다.

보충 2 (캘리포니아의 별도 장부와 신설 실체의 첫해 선납): 소유자 세액공제는 주 세금에만 충당할 수 있습니다. 실체의 연 800달러 세금과 LLC의 총수입 수수료(fee)는 PTET와 별개의 장부이며 영향을 받지 않습니다. 그리고 신설 실체는 첫해에 참조할 전년 PTET의 50%가 없으므로 6월 선납은 1,000달러에서 시작합니다. 전액을 선납해야 한다고 겁먹을 필요도 없고, 납부 자체를 잊어서도 안 됩니다.

### Bổ sung Tiếng Việt (bản dịch sơ bộ · 初译待校)

Bổ sung 1 (ranh giới của Notice 2020-75): Thông báo này chỉ bao quát thuế thu nhập đánh vào chính thực thể. Khoản thuế ước tính ở cấp cá nhân của chủ sở hữu và khấu trừ lương không nằm trong đó, và khoản thực thể nộp thay cho một chủ sở hữu cụ thể nhưng về bản chất vẫn là thuế cá nhân thì không đương nhiên rơi vào phạm vi của thông báo. Ngoài ra, điều khoản của bản Hạ viện nhằm hạn chế PTET trong quá trình lập pháp OBBBA đã không được đưa vào văn bản thành luật (§ 70120), nên không được trích dẫn tiêu chuẩn của dự thảo chưa thành luật.

Bổ sung 2 (sổ sách riêng của California và khoản nộp trước năm đầu của thực thể mới): Tín dụng của chủ sở hữu chỉ được trừ vào thuế bang. Khoản thuế hằng năm 800 đô la của thực thể và phí trên tổng thu nhập (fee) của LLC là hai sổ sách riêng với PTET và không bị ảnh hưởng. Thêm nữa, thực thể mới thành lập không có mức 50% PTET của năm trước để tham chiếu trong năm đầu, nên khoản nộp trước tháng 6 bắt đầu từ 1.000 đô la. Không cần hoảng vì tưởng phải nộp trước toàn bộ, và cũng không được quên nộp.

### हिन्दी पूरक (प्रारंभिक अनुवाद · 初译待校)

पूरक 1 (Notice 2020-75 की सीमा): यह नोटिस केवल उस आयकर को कवर करता है जो स्वयं इकाई पर लगाया गया हो। स्वामी के व्यक्तिगत स्तर के अनुमानित कर भुगतान और वेतन कटौती इसमें नहीं आते, और इकाई द्वारा किसी विशेष स्वामी की ओर से चुकाई गई राशि, यदि स्वभाव से वह फिर भी व्यक्तिगत कर है, तो स्वतः इस नोटिस के दायरे में नहीं आती। साथ ही OBBBA विधायी प्रक्रिया में PTET को सीमित करने वाला सदन-संस्करण का प्रावधान अधिनियमित पाठ (§ 70120) में अपनाया नहीं गया, इसलिए अनधिनियमित मसौदे के मानक का हवाला नहीं देना चाहिए।

पूरक 2 (कैलिफ़ोर्निया की अलग किताबें और नई इकाई के पहले वर्ष का पूर्व-भुगतान): स्वामी का क्रेडिट केवल राज्य कर में ही लगाया जा सकता है। इकाई का वार्षिक $800 कर और LLC का सकल-आय शुल्क (fee) PTET से अलग किताबें हैं और उन पर कोई असर नहीं पड़ता। और नई स्थापित इकाई के पास पहले वर्ष में संदर्भ के लिए पिछले वर्ष के PTET का 50% नहीं होता, इसलिए जून का पूर्व-भुगतान $1,000 से शुरू होता है। न तो पूरी राशि पहले चुकाने के डर की ज़रूरत है, न ही भुगतान भूलने की छूट।
