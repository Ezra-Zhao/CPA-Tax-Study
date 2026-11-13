# 健康报销安排 HRA 怎么计税：ICHRA、EBHRA 与 QSEHRA 及加州口径

> 个人学习笔记，不构成税务建议。Personal study notes, not tax advice.
> 核心依据：IRC §§ 105、106（雇主健康计划排除）、§ 9831(d)（QSEHRA）、§ 4980H（雇主强制条款）、§ 36B（保费抵免）；2019 年最终法规（84 Fed. Reg. 28888，T.D. 9867 一带，Reg. § 54.9802-4 等）；IRS Notice 2017-67（QSEHRA）；Rev. Proc. 2024-40（2025 年 QSEHRA 上限）。HRA 限额逐年以 IRS 公告为准，加州以 FTB 现行口径为准。

HRA（health reimbursement arrangement，健康报销安排）与 HSA、FSA 最大的区别在出钱的人：它只能由雇主全额出资，员工一分钱不能往里放。2019 年的一套最终法规又把 HRA 家族拆出两个新成员——可以报销个人市场保费的 ICHRA，和小额定额的 EBHRA；再加上 2016 年立法给小雇主的 QSEHRA，今天一共四种 HRA 并行，计税主线同一根（§§ 105/106 排除），但资格、限额和与保费抵免（PTC）的互斥关系各不相同。这篇按「先主线、后三型、再互斥、末加州」的顺序拆。

## 中文主文

### 一、主线：雇主全额出资，报销在 §§ 105/106 下排除

传统 HRA 是雇主设立的一个记账式安排：雇主承诺一个年度报销额度，员工发生 § 213(d) 合格医疗费用后凭凭证报销。税法处理分三步。第一，资金来源只能是雇主：HRA 的定义要件就是雇主全额出资（employer-funded），员工不能通过 § 125 自助餐计划用税前工资往 HRA 里供款——这是它与健康 FSA 的根本分界，FSA 的钱主要是员工自己的税前选举，HRA 的钱全是雇主的。第二，报销排除：员工从雇主健康计划取得的医疗费用报销，依 § 105(b) 排除在总收入之外；雇主为员工健康保障的出资一侧，依 § 106 的框架不计入员工收入。两者合成的结果是：雇主出钱、员工报销合格费用，两头都不在员工身上计税。第三，报销边界：只能报 § 213(d) 的医疗照护费用（ICHRA 等新型另可报保费，见下），须有支出凭证，不能重复报销同一笔已由保险或其他计划赔付的费用；额度没用完能否结转、离职后是否保留，看计划文件——HRA 没有 HSA 那种法定个人所有权，计划可以规定离职即终止。

### 二、ICHRA：2019 年法规创设，报销个人市场保费

ICHRA（individual coverage HRA，个人保障型 HRA）由财政部、劳工部与 HHS 于 2019 年 6 月发布的最终法规创设（84 Fed. Reg. 28888，2019-06-20），适用于 2020 年 1 月 1 日或之后开始的计划年度，规则主要落在 Reg. § 54.9802-4 一带（另有劳工部、HHS 平行条文）。它把 HRA 的报销范围扩到个人市场（individual market）的医疗保险保费：雇主不买团体险，改为给员工一笔 ICHRA 额度，员工自己去市场上买个人保单、凭保费凭证报销，合格医疗费用也可一并报销。

成立要件抓四条。一是员工须实际参加个人市场保障（或 Medicare），没有个人保障就没有可报销的保费，雇主须做参保核实。二是同一「类别」（class，如全职/兼职、不同工作地点等法定类别）的员工须同等条件提供，且雇主不能就同一类别同时给「团体险或 ICHRA」的选择题——要给 ICHRA 的类别就不能再给该类别团体计划选项，防止按健康状况挑人。三是员工可每年选择退出（opt-out），以保留去交易所申请 PTC 的可能。四是雇主须提前书面通知（一般为计划年度开始前 90 天）。

与 § 4980H 的衔接是 ICHRA 的实务重心：适用大型雇主（ALE）向全职员工提供「可负担」（affordable）的 ICHRA，可视为满足雇主强制条款的 offer。负担能力按员工应自付的个人市场保费测算——以员工工作地（或居住地，依适用安全港）最低价银级计划保费减 ICHRA 额度后的差额，对照 § 4980H(b) 的负担能力比例判定；IRS 给了地点、回望月（look-back month）等安全港简化取数。若 ICHRA 被认定为可负担，被提供的员工当月即失去 PTC（见第四节）。

算例：某员工工作地最低价银级计划月保费 600 美元，雇主 ICHRA 每月给 450 美元，员工需自付差额 600−450＝150 美元，全年 150×12＝1,800 美元。是否「可负担」再把这 1,800 美元与该员工当年收入按 § 4980H 的负担能力比例比较判定（比例逐年由 IRS 公告，本篇不写死）。复算：600−450＝150，150×12＝1,800，无误。

### 三、EBHRA 与 QSEHRA：一个是「例外福利」小额版，一个是小雇主专用版

EBHRA（excepted benefit HRA，例外福利型 HRA）与 ICHRA 出自同一套 2019 年最终法规。它不报销个人保费，而是作为「例外福利」独立存在：年度报销上限最初为 2020 年的 1,800 美元，其后按通胀（CPI）逐年调整，具体年份金额以 IRS 当年公告为准。成立条件主要是：雇主须同时向同一批员工提供传统团体健康计划（员工可以不参加，但雇主必须有提供），EBHRA 只能报 § 213(d) 医疗费用与有限的非 COBRA 延续保障保费等，不能报个人市场保费（少数例外除外）。它的定位是给团体险再加一个小额自付费用报销口袋。

QSEHRA（qualified small employer HRA）来历不同：它由《21 世纪治愈法案》立法创设、条文在 IRC § 9831(d)，IRS 以 Notice 2017-67 落地细则，专供小雇主使用。资格要件：雇主不是 ALE（上年全职等值员工少于 50 人），且不向任何员工提供团体健康计划。额度有法定上限并按通胀调整：2025 年为自付（self-only）6,350 美元、家庭 12,800 美元（Rev. Proc. 2024-40）；其后年份以 IRS 当年公告为准。员工须有符合最低必要保障（minimum essential coverage）的个人保险才能按月报销，雇主供款额要计入员工 W-2 第 12 栏（代码 FF）报告；没有个人保障的月份，报销额要计入收入。QSEHRA 须在同一条件下向全体合格员工提供（服务年限、年龄等法定排除除外），并提前书面通知。

三型与传统 HRA 的分工一句话收：传统 HRA 绑团体险报医疗费；ICHRA 替代团体险报个人保费、无固定法定上限（由雇主定额，但受 § 4980H 负担能力约束）；EBHRA 附在团体险旁报小额费用、有年度法定上限；QSEHRA 是没团体险的小雇主专用、有年度法定上限且雇主规模受限。

### 四、互斥关系：与 § 125 的分界、与 PTC 的冲突

与 § 125 的互斥是结构性的：HRA 不能作为自助餐计划的选举项让员工用税前工资供款，四种 HRA 都如此。员工在 § 125 下能选的是健康 FSA 等；雇主想给报销额度，就走 HRA 并全额自担成本，两条通道不能混。

与 § 36B 保费抵免（PTC）的冲突更要紧。ICHRA：员工若被提供了可负担的 ICHRA，即便实际没用，也不能就同一月份主张 PTC；若 ICHRA 不可负担，员工可选择退出 ICHRA 并主张 PTC——这正是每年 opt-out 机制存在的意义，错过退出窗口就可能两头落空。QSEHRA：员工的 PTC 要按 QSEHRA 的可得利益（permitted benefit）按月扣减，扣减后为负则无 PTC，算式上是「先有 QSEHRA、再算剩余 PTC」。EBHRA：因属例外福利，其提供本身一般不阻断 PTC，但报销的费用构成与个人保障的衔接以当年 IRS 口径为准，本篇不展开。实务动作只有一个：每年开放注册期，把 ICHRA/QSEHRA 的额度与交易所 PTC 估算放在同一张纸上比较后再选，不默认接受雇主安排。

### 五、加州口径

加州对雇主健康计划的报销排除大体跟随联邦 §§ 105/106 的框架，HRA 报销合格医疗费用在州税层面的处理以 FTB 现行说明为准。加州特有的一层是州个人强制投保（state individual mandate）与州交易所 Covered California 的补贴体系：ICHRA 与 QSEHRA 在联邦 PTC 上的互斥逻辑，在州补贴一侧另有州规则衔接，员工比较「接受 HRA 还是走交易所」时要把州补贴一并算入，以 Covered California 与 FTB 当年指引为准。另注意加州不承认 HSA 的联邦待遇（见本仓 HSA 专篇），但这不影响 HRA 的分析——HRA 是雇主计划而非个人账户，两条线不要混。

**来源与依据**：IRC § 105(b)（医疗费用报销排除）、§ 106（雇主健康保障出资排除框架）、§ 213(d)（医疗照护定义）、§ 9831(d)（QSEHRA 要件与上限框架）、§ 4980H（ALE 雇主 offer 与负担能力）、§ 36B（PTC 与可负担雇主保障的互斥）、§ 125（HRA 不得由员工税前供款的结构分界）；2019 年最终法规 84 Fed. Reg. 28888（ICHRA 与 EBHRA，Reg. § 54.9802-4 一带，2020 年计划年度起适用；EBHRA 2020 年上限 1,800 美元、其后按 CPI 调整以 IRS 公告为准）；IRS Notice 2017-67（QSEHRA 细则）；Rev. Proc. 2024-40（2025 年 QSEHRA 上限自付 6,350/家庭 12,800 美元，其后年份以 IRS 当年公告为准）；IRS 关于 ICHRA 负担能力安全港的现行指引。

*声明：个人学习笔记，不构成税务建议。具体计划的资格、额度与补贴取舍请以计划文件与 IRS、HHS、FTB 及 Covered California 现行指引为准，金额较大时先咨询持牌 CPA。*

---

## English

An HRA (health reimbursement arrangement) differs from an HSA or FSA in one structural way: only the employer may fund it — employees contribute nothing. **The main rule.** Amounts an employer provides under a health plan are framed by IRC § 106, and reimbursements of § 213(d) medical care are excluded from the employee's income under § 105(b), so a qualifying reimbursement is tax-free at both ends. Because the money is entirely the employer's, an HRA can never be an election under a § 125 cafeteria plan: employees cannot fund an HRA with pre-tax salary. Only substantiated § 213(d) expenses may be reimbursed, the same expense cannot be reimbursed twice, and carryover or post-separation rights exist only if the plan document grants them — an HRA carries no statutory individual ownership like an HSA.

**ICHRA.** The individual coverage HRA was created by the June 2019 final regulations (84 Fed. Reg. 28888), effective for plan years beginning on or after January 1, 2020, with rules centered on Reg. § 54.9802-4. The employer funds an amount; the employee buys individual-market coverage and is reimbursed for premiums (and, if the plan allows, other medical expenses). Conditions: the employee must actually enroll in individual coverage or Medicare; employees within a permitted class must be offered the ICHRA on the same terms, and the employer may not offer that class a choice between a group plan and the ICHRA; employees may opt out annually (preserving premium tax credit options); and written notice is generally due 90 days before the plan year. For applicable large employers, an affordable ICHRA counts as an offer under § 4980H, with affordability measured on the employee's residual premium for the lowest-cost silver plan minus the ICHRA amount, under IRS safe harbors (location, look-back month, and the usual § 4980H affordability percentage for the year). Example: lowest-cost silver premium $600 per month, ICHRA $450, residual $600 − $450 = $150 per month, or $150 × 12 = $1,800 per year, which is then tested against the § 4980H affordability standard.

**EBHRA.** The excepted benefit HRA comes from the same 2019 regulations. It is a small add-on: the annual limit started at $1,800 for 2020 and is adjusted for inflation (CPI) — use the IRS figure for the current year. The employer must also offer a traditional group health plan to the same employees; the EBHRA reimburses § 213(d) expenses but generally not individual-market premiums.

**QSEHRA.** The qualified small employer HRA is statutory, under IRC § 9831(d) (guidance in IRS Notice 2017-67). It is only for employers that are not applicable large employers (fewer than 50 full-time-equivalent employees) and offer no group health plan at all. Statutory caps are inflation-adjusted: for 2025, $6,350 self-only and $12,800 family (Rev. Proc. 2024-40); later years follow the IRS annual guidance. Employees need minimum essential coverage to receive tax-free reimbursements, and the benefit is reported in W-2 box 12 with code FF.

**Conflicts to watch.** Section 125: no HRA of any type may be salary-funded. Section 36B premium tax credit (PTC): an employee offered an *affordable* ICHRA cannot claim the PTC for the same months even if the ICHRA goes unused; if the ICHRA is unaffordable, the employee may opt out and claim the PTC. A QSEHRA permitted benefit reduces the employee's PTC month by month. An EBHRA, as an excepted benefit, generally does not by itself block the PTC — confirm against current IRS guidance. Compare the HRA amount and the exchange credit on one page every open enrollment.

**California.** California broadly follows the federal §§ 105/106 exclusion framework for employer health plan reimbursements (confirm with current FTB guidance). Two California overlays matter: the state individual mandate and the Covered California subsidy system, whose interaction with ICHRAs and QSEHRAs follows state rules — include state subsidies in any HRA-versus-exchange comparison. California's non-conformity to HSAs does not change the HRA analysis; an HRA is an employer plan, not an individual account.

*Personal study notes only; not tax advice. Sources: IRC §§ 105(b), 106, 213(d), 9831(d), 4980H, 36B, 125; 84 Fed. Reg. 28888 (2019); IRS Notice 2017-67; Rev. Proc. 2024-40.*

## Español

Una HRA (health reimbursement arrangement) se distingue de la HSA y la FSA en un punto estructural: solo el empleador puede financiarla, el empleado no aporta nada. **Regla principal.** Los importes del empleador bajo un plan de salud se enmarcan en el IRC § 106, y los reembolsos de atención médica del § 213(d) se excluyen del ingreso del empleado según el § 105(b): el reembolso calificado queda libre de impuestos en ambos extremos. Como todo el dinero es del empleador, una HRA nunca puede ser una elección dentro de un plan de cafetería del § 125: el empleado no puede financiarla con salario antes de impuestos. Solo se reembolsan gastos del § 213(d) debidamente acreditados, sin doble reembolso, y la acumulación o la supervivencia tras la separación solo existen si el documento del plan las concede: la HRA no tiene la titularidad individual legal de la HSA.

**ICHRA.** La HRA de cobertura individual nació del reglamento final de junio de 2019 (84 Fed. Reg. 28888), aplicable a años del plan desde el 1 de enero de 2020, con reglas centradas en el Reg. § 54.9802-4. El empleador financia un importe; el empleado compra cobertura en el mercado individual y recibe el reembolso de las primas (y, si el plan lo permite, de otros gastos médicos). Condiciones: el empleado debe estar efectivamente inscrito en cobertura individual o Medicare; la oferta debe ser uniforme dentro de cada clase permitida, sin dar a la misma clase la opción de elegir entre plan grupal e ICHRA; el empleado puede renunciar (opt-out) cada año, preservando su acceso al crédito fiscal por primas; y el aviso escrito vence en general 90 días antes del año del plan. Para los grandes empleadores aplicables, una ICHRA asequible cuenta como oferta a efectos del § 4980H, con la asequibilidad medida sobre la prima residual del plan plata más barato menos el importe ICHRA, bajo los puertos seguros del IRS. Ejemplo: prima plata más barata de 600 dólares al mes, ICHRA de 450, residual 600 − 450 = 150 al mes, es decir, 150 × 12 = 1.800 al año, que luego se contrasta con el estándar de asequibilidad del § 4980H.

**EBHRA.** La HRA de beneficio excepto procede del mismo reglamento de 2019. Es un complemento pequeño: el límite anual comenzó en 1.800 dólares para 2020 y se ajusta por inflación (IPC); para el año en curso rige la cifra del IRS. El empleador debe ofrecer además un plan de salud grupal tradicional a los mismos empleados; la EBHRA reembolsa gastos del § 213(d), pero en general no primas del mercado individual.

**QSEHRA.** La HRA calificada para pequeños empleadores es legal, IRC § 9831(d) (guía en la Notice 2017-67 del IRS). Solo sirve a empleadores que no son grandes empleadores aplicables (menos de 50 empleados equivalentes a tiempo completo) y que no ofrecen ningún plan grupal. Los topes legales se ajustan por inflación: para 2025, 6.350 dólares individual y 12.800 familiar (Rev. Proc. 2024-40); los años posteriores siguen la guía anual del IRS. El empleado necesita cobertura esencial mínima para recibir reembolsos exentos, y el beneficio se declara en la casilla 12 del W-2 con el código FF.

**Conflictos.** § 125: ninguna HRA puede financiarse con salario. Crédito fiscal por primas del § 36B (PTC): quien recibe la oferta de una ICHRA *asequible* no puede reclamar el PTC por los mismos meses aunque no use la ICHRA; si la ICHRA no es asequible, puede renunciar a ella y reclamar el PTC. El beneficio permitido de una QSEHRA reduce el PTC mes a mes. La EBHRA, como beneficio excepto, en general no bloquea por sí sola el PTC — confírmese con la guía vigente del IRS.

**California.** California sigue en general el marco federal de exclusión de los §§ 105/106 para los reembolsos de planes de salud del empleador (confírmese con la guía vigente del FTB). Se añaden dos capas estatales: el mandato individual estatal y el sistema de subsidios de Covered California, cuya interacción con ICHRA y QSEHRA sigue reglas estatales — incluya los subsidios estatales en toda comparación. La no conformidad californiana con las HSA no altera el análisis de la HRA: esta es un plan del empleador, no una cuenta individual.

*Notas personales de estudio; no constituye asesoría fiscal. Fuentes: IRC §§ 105(b), 106, 213(d), 9831(d), 4980H, 36B, 125; 84 Fed. Reg. 28888 (2019); Notice 2017-67; Rev. Proc. 2024-40.*

## 한국어 (초역, 원어민 감수 대기)

HRA(health reimbursement arrangement)는 HSA, FSA와 구조적으로 다릅니다. 돈을 넣는 주체가 고용주뿐이고 종업원은 전혀 넣을 수 없습니다. **본칙.** 고용주가 건강 플랜으로 제공하는 금액은 IRC § 106의 틀에 있고, § 213(d) 의료비 상환은 § 105(b)로 종업원 소득에서 제외되므로 적격 상환은 양쪽 끝 모두 비과세입니다. 전액 고용주 돈이므로 HRA는 § 125 카페테리아 플랜의 선택 항목이 될 수 없습니다. 종업원이 세전 급여로 HRA를 채울 수는 없습니다. 증빙된 § 213(d) 비용만 상환되고 이중 상환은 안 되며, 이월이나 퇴사 후 권리는 플랜 문서가 정할 때만 존재합니다. HRA에는 HSA 같은 법정 개인 소유권이 없습니다.

**ICHRA.** 개인보장형 HRA는 2019년 6월 최종 규정(84 Fed. Reg. 28888)으로 만들어졌고 2020년 1월 1일 이후 시작하는 플랜 연도부터 적용되며, 규칙의 중심은 Reg. § 54.9802-4입니다. 고용주가 금액을 대고 종업원이 개인시장 보험에 가입해 보험료를 상환받습니다(플랜이 허용하면 다른 의료비도 가능). 요건은 이렇습니다. 종업원이 실제로 개인시장 보장이나 Medicare에 가입해 있어야 하고, 허용된 class 안에서는 같은 조건으로 제공해야 하며, 같은 class에 단체 플랜과 ICHRA 중 선택지를 줄 수는 없습니다. 종업원은 매년 opt-out으로 빠져나가 보험료 세액공제(PTC) 가능성을 지킬 수 있고, 서면 통지는 원칙적으로 플랜 연도 시작 90일 전까지입니다. 적용 대상 대기업(ALE)에게는 부담 가능한(affordable) ICHRA가 § 4980H의 offer로 인정되며, 부담 가능성은 최저가 실버 플랜 보험료에서 ICHRA 금액을 뺀 잔여 보험료로 IRS 안전항(safe harbor)에 따라 판정합니다. 예시: 최저가 실버 월 보험료 600달러, ICHRA 월 450달러이면 잔액은 600 − 450 = 150달러, 연 150 × 12 = 1,800달러가 되고 이를 § 4980H 부담 가능성 기준과 비교합니다.

**EBHRA.** 예외급여형 HRA도 같은 2019년 규정에서 나왔습니다. 소액 부가 장치로, 연간 상한은 2020년 1,800달러에서 시작해 물가(CPI)로 조정되므로 해당 연도는 IRS 금액을 확인합니다. 고용주는 같은 종업원에게 전통 단체 건강 플랜도 제공해야 하고, EBHRA는 § 213(d) 비용을 상환하지만 개인시장 보험료는 원칙적으로 상환하지 않습니다.

**QSEHRA.** 적격 소규모 고용주 HRA는 법률상 제도이며 IRC § 9831(d)에 근거합니다(지침은 IRS Notice 2017-67). 적용 대상 대기업이 아니고(전일제 환산 50인 미만) 단체 플랜을 전혀 제공하지 않는 고용주만 쓸 수 있습니다. 법정 상한은 물가 연동으로, 2025년은 본인 6,350달러, 가족 12,800달러입니다(Rev. Proc. 2024-40). 이후 연도는 IRS 연례 안내를 따릅니다. 종업원은 비과세 상환을 받으려면 최소 필수 보장(minimum essential coverage)에 가입해 있어야 하고, 급부는 W-2 12번 칸 코드 FF로 보고됩니다.

**충돌 지점.** § 125: 어떤 HRA도 급여로 채울 수 없습니다. § 36B 보험료 세액공제(PTC): 부담 가능한 ICHRA를 제공받은 종업원은 그 ICHRA를 쓰지 않았더라도 같은 달에 PTC를 받을 수 없습니다. 부담 가능하지 않으면 ICHRA에서 빠져나와 PTC를 받을 수 있습니다. QSEHRA의 허용 급부는 PTC를 월 단위로 줄입니다. 예외급여인 EBHRA는 일반적으로 그 자체로 PTC를 막지 않지만 현행 IRS 지침으로 확인해야 합니다.

**캘리포니아.** 캘리포니아는 고용주 건강 플랜 상환에 대해 연방 §§ 105/106 제외 틀을 대체로 따릅니다(현행 FTB 안내로 확인). 여기에 주 개인 의무 가입과 Covered California 보조금 체계라는 두 겹이 더해지며, ICHRA·QSEHRA와의 상호작용은 주 규칙을 따르므로 비교할 때 주 보조금까지 넣어야 합니다. 캘리포니아가 HSA에 동조하지 않는다는 점은 HRA 분석을 바꾸지 않습니다. HRA는 개인 계좌가 아니라 고용주 플랜입니다.

*개인 학습 노트이며 세무 자문이 아닙니다. 출처: IRC §§ 105(b), 106, 213(d), 9831(d), 4980H, 36B, 125; 84 Fed. Reg. 28888 (2019); Notice 2017-67; Rev. Proc. 2024-40. (초역, 원어민 감수 대기)*

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

HRA (health reimbursement arrangement — sắp xếp hoàn trả chi phí sức khỏe) khác HSA và FSA ở một điểm cấu trúc: chỉ chủ lao động được cấp tiền, nhân viên không đóng gì cả. **Nguyên tắc chính.** Các khoản chủ lao động cung cấp theo chương trình sức khỏe nằm trong khung IRC § 106, và khoản hoàn trả chi phí chăm sóc y tế theo § 213(d) được loại trừ khỏi thu nhập của nhân viên theo § 105(b), nên khoản hoàn đủ điều kiện được miễn thuế ở cả hai đầu. Vì toàn bộ tiền là của chủ lao động, HRA không bao giờ là một lựa chọn trong chương trình cafeteria § 125: nhân viên không thể nạp HRA bằng lương trước thuế. Chỉ chi phí § 213(d) có chứng từ mới được hoàn, không hoàn trùng, và quyền chuyển sang năm sau hay giữ sau khi nghỉ việc chỉ tồn tại nếu văn kiện chương trình cho phép — HRA không có quyền sở hữu cá nhân theo luật như HSA.

**ICHRA.** HRA bảo hiểm cá nhân được tạo bởi bộ quy định cuối cùng tháng 6/2019 (84 Fed. Reg. 28888), áp dụng cho các năm chương trình bắt đầu từ 1/1/2020, với quy tắc trọng tâm ở Reg. § 54.9802-4. Chủ lao động cấp một khoản tiền; nhân viên mua bảo hiểm ở thị trường cá nhân và được hoàn phí bảo hiểm (và nếu chương trình cho phép, cả chi phí y tế khác). Điều kiện: nhân viên phải thực sự tham gia bảo hiểm cá nhân hoặc Medicare; trong cùng một nhóm (class) được phép, điều kiện chào phải như nhau và chủ lao động không được cho cùng nhóm đó chọn giữa chương trình nhóm và ICHRA; nhân viên có thể từ chối (opt-out) hằng năm để giữ khả năng xin tín dụng thuế phí bảo hiểm (PTC); thông báo bằng văn bản thường đến hạn 90 ngày trước năm chương trình. Với chủ lao động lớn thuộc diện áp dụng, ICHRA ở mức «có thể chi trả» (affordable) được tính là một lời chào theo § 4980H, với mức affordable đo bằng phí còn lại của gói bạc rẻ nhất trừ đi khoản ICHRA, theo các safe harbor của IRS. Ví dụ: phí gói bạc rẻ nhất 600 đô la/tháng, ICHRA 450, phần còn lại 600 − 450 = 150 đô la/tháng, tức 150 × 12 = 1.800 đô la/năm, rồi đối chiếu với chuẩn affordable của § 4980H.

**EBHRA.** HRA phúc lợi ngoại lệ cũng đến từ bộ quy định 2019. Đây là khoản bổ sung nhỏ: trần hằng năm khởi điểm 1.800 đô la cho năm 2020 và được điều chỉnh theo lạm phát (CPI) — năm hiện tại dùng con số của IRS. Chủ lao động phải đồng thời chào một chương trình sức khỏe nhóm truyền thống cho cùng nhân viên; EBHRA hoàn chi phí § 213(d) nhưng nhìn chung không hoàn phí bảo hiểm thị trường cá nhân.

**QSEHRA.** HRA chủ lao động nhỏ đủ điều kiện là chế độ theo luật, IRC § 9831(d) (hướng dẫn tại IRS Notice 2017-67). Chỉ dành cho chủ lao động không thuộc diện chủ lao động lớn (dưới 50 nhân viên quy đổi toàn thời gian) và không chào bất kỳ chương trình nhóm nào. Trần theo luật được điều chỉnh theo lạm phát: năm 2025 là 6.350 đô la cho cá nhân và 12.800 đô la cho gia đình (Rev. Proc. 2024-40); các năm sau theo hướng dẫn hằng năm của IRS. Nhân viên cần có bảo hiểm thiết yếu tối thiểu (minimum essential coverage) để nhận hoàn miễn thuế, và quyền lợi được báo cáo ở ô 12 của W-2 với mã FF.

**Các điểm xung đột.** § 125: không loại HRA nào được nạp bằng lương. Tín dụng thuế phí bảo hiểm § 36B (PTC): nhân viên được chào một ICHRA *affordable* thì không thể xin PTC cho cùng những tháng đó dù không dùng ICHRA; nếu ICHRA không affordable, nhân viên có thể opt-out và xin PTC. Quyền lợi cho phép của QSEHRA làm giảm PTC theo từng tháng. EBHRA, với tư cách phúc lợi ngoại lệ, nhìn chung không tự nó chặn PTC — cần đối chiếu hướng dẫn IRS hiện hành.

**California.** California về cơ bản theo khung loại trừ liên bang §§ 105/106 đối với khoản hoàn của chương trình sức khỏe do chủ lao động lập (đối chiếu hướng dẫn FTB hiện hành). Hai lớp riêng của bang cần tính: lệnh bắt buộc mua bảo hiểm cấp bang và hệ thống trợ cấp của Covered California, mà tương tác với ICHRA và QSEHRA đi theo quy tắc của bang — hãy đưa trợ cấp bang vào mọi phép so sánh. Việc California không tuân theo HSA không làm thay đổi phân tích HRA; HRA là chương trình của chủ lao động, không phải tài khoản cá nhân.

*Ghi chú học tập cá nhân, không phải tư vấn thuế. Nguồn: IRC §§ 105(b), 106, 213(d), 9831(d), 4980H, 36B, 125; 84 Fed. Reg. 28888 (2019); Notice 2017-67; Rev. Proc. 2024-40. (Bản dịch sơ bộ, chờ hiệu đính)*

## हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

HRA (health reimbursement arrangement) HSA और FSA से एक संरचनात्मक बिंदु पर अलग है: इसमें धन केवल नियोक्ता दे सकता है, कर्मचारी कुछ नहीं देता। **मुख्य नियम।** नियोक्ता द्वारा स्वास्थ्य योजना के तहत दी गई राशियाँ IRC § 106 के ढाँचे में हैं, और § 213(d) चिकित्सा देखभाल की प्रतिपूर्ति § 105(b) के तहत कर्मचारी की आय से बाहर रहती है, इसलिए योग्य प्रतिपूर्ति दोनों सिरों पर कर-मुक्त है। चूँकि सारा धन नियोक्ता का है, HRA कभी § 125 cafeteria plan का चुनाव नहीं बन सकता: कर्मचारी कर-पूर्व वेतन से HRA नहीं भर सकता। केवल प्रमाणित § 213(d) ख़र्च ही प्रतिपूर्तियोग्य हैं, दोहरी प्रतिपूर्ति नहीं होती, और carryover या अलग होने के बाद के अधिकार केवल plan दस्तावेज़ दे तो ही मिलते हैं — HRA में HSA जैसा वैधानिक व्यक्तिगत स्वामित्व नहीं है।

**ICHRA।** Individual coverage HRA जून 2019 के अंतिम नियमों (84 Fed. Reg. 28888) से बना, जो 1 जनवरी 2020 से शुरू होने वाले plan वर्षों पर लागू है, और इसके नियमों का केंद्र Reg. § 54.9802-4 है। नियोक्ता एक राशि देता है; कर्मचारी individual market से बीमा ख़रीदता है और प्रीमियम की प्रतिपूर्ति पाता है (plan अनुमति दे तो अन्य चिकित्सा ख़र्च भी)। शर्तें: कर्मचारी वास्तव में individual coverage या Medicare में नामांकित हो; किसी अनुमत class के भीतर समान शर्तों पर प्रस्ताव हो, और उसी class को group plan व ICHRA के बीच चुनाव न दिया जाए; कर्मचारी हर वर्ष opt-out करके premium tax credit (PTC) का विकल्प बचा सकता है; लिखित सूचना सामान्यतः plan वर्ष से 90 दिन पहले देनी होती है। Applicable large employers के लिए affordable ICHRA § 4980H के तहत offer माना जाता है, और affordability सबसे सस्ते silver plan के प्रीमियम में से ICHRA राशि घटाकर बचे residual premium पर, IRS safe harbors के अनुसार, मापी जाती है। उदाहरण: सबसे सस्ता silver प्रीमियम $600 प्रति माह, ICHRA $450, तो residual $600 − $450 = $150 प्रति माह, अर्थात $150 × 12 = $1,800 प्रति वर्ष, जिसकी तुलना फिर § 4980H affordability मानक से होती है।

**EBHRA।** Excepted benefit HRA भी उसी 2019 नियमों से आया है। यह एक छोटा पूरक है: वार्षिक सीमा 2020 में $1,800 से शुरू हुई और मुद्रास्फीति (CPI) से समायोजित होती है — वर्तमान वर्ष के लिए IRS का आँकड़ा देखें। नियोक्ता को उन्हीं कर्मचारियों को पारंपरिक group health plan भी देना होगा; EBHRA § 213(d) ख़र्च देती है, किंतु सामान्यतः individual-market प्रीमियम नहीं।

**QSEHRA।** Qualified small employer HRA एक वैधानिक व्यवस्था है, IRC § 9831(d) के तहत (मार्गदर्शन IRS Notice 2017-67)। यह केवल उन नियोक्ताओं के लिए है जो applicable large employer नहीं हैं (50 से कम full-time-equivalent कर्मचारी) और कोई group plan नहीं देते। वैधानिक सीमाएँ मुद्रास्फीति-समायोजित हैं: 2025 के लिए self-only $6,350 और family $12,800 (Rev. Proc. 2024-40); बाद के वर्ष IRS के वार्षिक मार्गदर्शन से। कर-मुक्त प्रतिपूर्ति के लिए कर्मचारी के पास minimum essential coverage होना चाहिए, और लाभ W-2 के box 12 में code FF के साथ रिपोर्ट होता है।

**टकराव के बिंदु।** § 125: किसी भी प्रकार का HRA वेतन से नहीं भरा जा सकता। § 36B premium tax credit (PTC): जिसे *affordable* ICHRA दिया गया हो, वह उन्हीं महीनों के लिए PTC नहीं माँग सकता, भले ICHRA का उपयोग न हुआ हो; यदि ICHRA affordable न हो तो कर्मचारी opt-out करके PTC ले सकता है। QSEHRA का permitted benefit PTC को माह-दर-माह घटाता है। EBHRA, excepted benefit होने के कारण, सामान्यतः स्वयं PTC को नहीं रोकता — वर्तमान IRS मार्गदर्शन से जाँचें।

**California।** California नियोक्ता स्वास्थ्य योजना प्रतिपूर्तियों के लिए संघीय §§ 105/106 बहिष्करण ढाँचे का मोटे तौर पर पालन करता है (वर्तमान FTB मार्गदर्शन से जाँचें)। राज्य की दो परतें मायने रखती हैं: राज्य individual mandate और Covered California का subsidy तंत्र, जिनका ICHRA व QSEHRA से संबंध राज्य नियमों से चलता है — किसी भी तुलना में राज्य subsidy भी गिनें। California का HSA से असंगत होना HRA विश्लेषण नहीं बदलता; HRA नियोक्ता योजना है, व्यक्तिगत खाता नहीं।

*व्यक्तिगत अध्ययन नोट; कर सलाह नहीं है। स्रोत: IRC §§ 105(b), 106, 213(d), 9831(d), 4980H, 36B, 125; 84 Fed. Reg. 28888 (2019); Notice 2017-67; Rev. Proc. 2024-40। (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)*

## 补译增量（2026-11-12 15:55轮：韩／越／印三语各补 2 项中文主文已有细节）

### 한국어 (初译待校)

1. ICHRA 부담 가능성 산정의 보충: 부담 가능성은 그 직원 근무지의 개인시장으로 잽니다(적용되는 안전항에 따라 거주지로 잴 수도 있음). 그곳 최저가 실버 플랜 보험료에서 ICHRA 금액을 뺀 잔액이 출발점입니다. IRS는 지역 안전항과 함께 회고월(look-back month) 안전항을 둬서, 어느 달의 개인시장 보험료를 기준으로 삼을지를 단순화합니다. 이 잔액을 § 4980H(b)의 부담 가능성 비율과 견주어 그 ICHRA가 부담 가능한지를 판정합니다.
2. QSEHRA의 동일 조건과 무보장월 보충: QSEHRA는 법정 제외(근속 기간, 연령 등)를 뺀 모든 적격 직원에게 같은 조건으로 제공해야 합니다. 그리고 직원은 최소 필수 보장(minimum essential coverage)을 갖춘 달에만 비과세 상환을 받습니다. 보장이 없는 달의 상환액은 소득에 포함되므로, QSEHRA는 연 단위가 아니라 월 단위로 보장 유무를 따져야 하는 제도입니다.

### Tiếng Việt (初译待校)

1. Bổ sung cách lấy số đo khả năng chi trả của ICHRA: khả năng chi trả được đo bằng thị trường cá nhân tại nơi làm việc của nhân viên (hoặc, theo safe harbor áp dụng, nơi cư trú) — lấy phí của gói bạc rẻ nhất ở đó trừ đi khoản ICHRA để ra phần còn lại làm điểm khởi đầu. IRS cho safe harbor theo địa điểm và cả safe harbor tháng nhìn lại (look-back month) để đơn giản hóa việc chọn phí bảo hiểm của tháng nào làm chuẩn. Phần còn lại này được đối chiếu với tỷ lệ affordability của § 4980H(b) để kết luận ICHRA đó có affordable hay không.
2. Bổ sung điều kiện đồng nhất của QSEHRA và tháng không có bảo hiểm: QSEHRA phải được chào với cùng điều kiện cho mọi nhân viên đủ điều kiện, ngoài các loại trừ theo luật định (như thời gian làm việc, tuổi). Nhân viên chỉ được hoàn miễn thuế vào những tháng có bảo hiểm tối thiểu thiết yếu (minimum essential coverage); khoản hoàn của tháng không có bảo hiểm sẽ tính vào thu nhập, nên QSEHRA là chế độ phải xét theo từng tháng chứ không theo năm.

### हिन्दी (初译待校)

1. ICHRA की affordability के आँकड़े लेने पर पूरक: affordability उस कर्मचारी के कार्य-स्थान के individual market से मापी जाती है (लागू safe harbor के अनुसार निवास-स्थान से भी मापी जा सकती है) — वहाँ के सबसे सस्ते silver plan के प्रीमियम में से ICHRA राशि घटाकर बचा शेष ही प्रारंभ बिंदु है। IRS स्थान safe harbor के साथ look-back month safe harbor भी देता है, जिससे यह सरल हो जाता है कि किस माह का individual-market प्रीमियम मानक बने। इस शेष की तुलना § 4980H(b) के affordability अनुपात से करके तय होता है कि वह ICHRA affordable है या नहीं।
2. QSEHRA की समान-शर्त और बिना-कवरेज माह पर पूरक: QSEHRA वैधानिक अपवर्जनों (सेवा-अवधि, आयु आदि) को छोड़कर सभी पात्र कर्मचारियों को समान शर्तों पर देना होता है। और कर्मचारी केवल उन्हीं महीनों में कर-मुक्त प्रतिपूर्ति पाता है जिनमें उसके पास minimum essential coverage हो; बिना कवरेज वाले माह की प्रतिपूर्ति आय में शामिल होती है, इसलिए QSEHRA वर्ष-वार नहीं, माह-वार कवरेज से परखी जाने वाली व्यवस्था है।

