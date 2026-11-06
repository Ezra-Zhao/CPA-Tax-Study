# 开公司选实体怎么交税：LLC 穿透、S 公司工资与 C 公司双重税

> 个人学习笔记，不构成税务建议。Personal study notes, not tax advice.
> 核心依据：IRC § 11、§ 701、§ 1361–§ 1368、§ 1401–§ 1402；Treas. Reg. § 301.7701-2、§ 301.7701-3（check-the-box）；David E. Watson, P.C. v. United States, 668 F.3d 1008 (8th Cir. 2012)；加州 Revenue and Taxation Code § 17941、§ 17942、§ 23151、§ 23802；IRS 与 SSA 公布的自雇税与社保工资基数口径（年份随文标注）。

## 中文主文

先把一句话说清：**在美国开公司，选实体就是选「利润在哪一层交税、按什么税交」。** 有限责任（liability）是州公司法给的壳，联邦税怎么算，取决于这家实体在税法上被归成哪一类。下面把三条最常见的路——默认 LLC 穿透、S 公司、C 公司——的税理、算例和加州口径摆在一起，最后给一张取舍表。细节各有专篇（合伙与 S 公司、自雇税、公司所得税），本篇只管「开公司选实体」这一个决策点。

### 一、先分清两件事：法律外壳与税务分类不是一回事

LLC 是州法上的实体，联邦税上没有「LLC 税」这一档。按 check-the-box 规则（Treas. Reg. § 301.7701-2、§ 301.7701-3），一家国内 LLC 不做选择时的**默认分类**是：

- **只有一个成员**：disregarded entity（被忽略实体）——税上当它不存在，收入直接落到成员个人税表（经营走 Schedule C，出租走 Schedule E），成员以独资经营者（sole proprietor）身份交税；
- **两个或两个以上成员**：默认按**合伙（partnership）**纳税——实体报 Form 1065，利润穿透到成员的 Schedule K-1，按份额计入个人收入（IRC § 701、§ 702）。

想要公司待遇要自己选：填 Form 8832 选按公司（association）纳税，或直接填 Form 2553 选 S 公司（见第三节）。什么都不填，就停在默认分类。很多人的第一课是：注册了 LLC 不等于自动省税，省不省全看分类与利润形态。

### 二、默认 LLC 穿透：利润只交一次税，但整份净利通常要交自雇税

穿透的意思是实体层面不交所得税，利润无论是否实际分到手，都按份额在当年计入成员个人收入，适用个人边际税率。合伙口径下成员另有基数（basis，§ 705）与分配规则（§ 731），本篇不展开，要点只抓自雇税这一刀。

**自雇税（SECA，IRC § 1401）**：独资经营者与主动经营的合伙人/LLC 成员，对自雇净收入按 **15.3%** 交自雇税，其中社保部分 **12.4%**、医保部分 **2.9%**。两个口径必须记清：

- 社保 12.4% 只对**工资基数以内的部分**征收，基数逐年调整：**2025 年为 $176,100、2026 年为 $184,500**（Social Security Administration 公布的 contribution and benefit base；工资与自雇收入合并计算这个上限）；医保 2.9% **没有上限**，高收入者另有 0.9% 附加医保税（§ 1401(b)(2)(A)，门槛与工资口径相同，另有专篇）。
- 计税底子不是全额利润：先乘 **92.35%**（Schedule SE 的口径，相当于先把「雇主那一半」剔出去），再套税率；算出的自雇税可以**扣除一半**（§ 164(f)，线上调整，抵的是所得税、不是自雇税本身）。

**算例（可复算）**：单成员 LLC，2025 年 Schedule C 净利润 $100,000，无其他工资。自雇税计税底 = $100,000 × 92.35% = $92,350，未触 2025 年社保基数 $176,100，全额计税：社保部分 $92,350 × 12.4% = $11,451.40，医保部分 $92,350 × 2.9% = $2,678.15，自雇税合计 **$14,129.55**；其中一半 $7,064.78 可作线上调整抵减所得税应税所得。注意这 $14,129.55 是在个人所得税之外另交的——这正是很多人选 S 公司的动机。

### 三、S 公司：先过资格门，再谈「合理工资加分配」

S 公司不是一种州法实体，而是一种**税务选举**：先有公司（或选成公司纳税的 LLC），再按 § 1362 填 **Form 2553** 选举 S 地位。资格门（§ 1361(b)）四条硬线：

- 必须是国内公司；股东**不超过 100 人**（§ 1361(b)(1)(A)，家族成员有合并计算口径）；
- 股东只能是美国公民或居民个人、遗产、以及符合条件的信托等，**不得有非居民外国人股东、不得有公司或合伙股东**；
- 只能有**一类股票**（§ 1361(b)(1)(D)）——表决权可以不同，但分红与清算权利必须一致，第二类股票会直接掀翻 S 地位；
- Form 2553 一般须在课税年度开始后**第 3 个月的第 15 天之前**提交（新公司自首月起算），全体股东同意，迟交有 IRS 救济程序但要讲理由。

税理：利润穿透（§ 1366），股东按份额在 K-1 上交个人所得税，实体层面联邦一般不交所得税（内置利得税等例外另论）；股东有工资的先发工资。**省税点只在一个地方**：股东以雇员身份领的**工资**要交工资税（FICA，雇主与雇员合计 15.3%、结构与自雇税同档），而工资之外拿走的**分配（distribution）本身不交自雇税、也不交工资税**。于是账可以这样拆：同样的经营利润，一部分变工资（交工资税）、一部分变分配（不交这一层税）。

**算例（可复算，假设从简）**：经营利润在给业主发钱之前为 $120,000，按 2025 年口径、忽略州税与其他工资。若全走穿透自雇：自雇税底 = $120,000 × 92.35% = $110,820，自雇税 = $110,820 × 15.3% = **$16,955.46**（未触社保基数）。若改走 S 公司、给自己开 $60,000 合理工资：工资税 = $60,000 × 15.3% = **$9,180**（雇主与雇员两半合计，未计 FUTA 与州雇主税），其余利润作分配不再交这一层税——账面差 **$7,775.46**。但别只看这个差：S 公司要多付工资申报与合规成本、雇主那半工资税虽可作公司费用扣除、分配前还要先有股东基数撑着（§ 1367、§ 1368），利润太薄时省下的还不够付会计费。

**红线：工资必须是「合理的」**。IRS 的立场有判例锚点：**Watson 案**——David E. Watson, P.C. v. United States, 668 F.3d 1008 (8th Cir. 2012)。Watson 是有近二十年经验的 CPA，2002 年只给自己开 $24,000 工资、却以分配名义拿走 $203,651，2003 年同样是 $24,000 工资对 $175,470 分配；法院维持 IRS 的重新定性，把一部分分配改判为工资、补征雇佣税。规则的源头是 Rev. Rul. 74-44：名为分红、实为提供服务的报酬，要按工资课税。合理工资看岗位、经验、当地同类薪酬与公司利润来源——利润主要来自业主本人的劳动时，工资压得越低越危险；利润主要来自资本、设备或员工团队时，分配占比才站得住。本仓案例分析板块有 Watson 案专篇。

### 四、C 公司：21% 单一税率，代价是双重征税

C 公司是独立纳税人：利润先在公司层面按 **IRC § 11 的 21% 单一税率**交税（TCJA 起的 flat rate，不再分档）；税后利润再以股息分给股东时，股东还要就股息交一次个人所得税（合格股息多在 0%/15%/20% 档，高收入者另加 § 1411 的 3.8% 净投资收益税）——这就是**双重征税（double taxation）**。

**算例（可复算）**：公司利润 $100,000，全部分配。公司税 = $100,000 × 21% = $21,000；余 $79,000 作合格股息、假设股东适用 15% 档，股息税 = $79,000 × 15% = $11,850；两层合计 **$32,850**，综合税负 32.85%。若股东落在 20% 档并触发 3.8% NIIT（合计 23.8%）：股息税 = $79,000 × 23.8% = $18,802，两层合计 $39,802，约 **39.8%**（与本仓公司所得税专篇的演算一致）。反过来，利润**留存在公司内再投资**时只交第一层 21%，这也是 C 公司真正的用武之地：要融资、要留利润扩张、或将来谋划 § 1202 合格小企业股票排除的人，才有理由扛双重税的结构成本；小生意把钱都拿回家花的，双重税通常不划算。公司给股东发工资则工资在公司层面可扣除、只在个人层面交一次税，但要受合理工资的反向审查（工资过高会被质疑变相分红），且工资照样有工资税。

### 五、加州口径：三条路都要先过 FTB 这一关

联邦选完，加州另算（与联邦分类并不完全跟随，申报表也不同）：

- **LLC**：每年 **$800 年税**（Revenue and Taxation Code § 17941，Form 3522），再加按加州来源**总收入**（total income，看毛额不是净利）分档的 **LLC fee**（§ 17942，Form 3536 预缴、Form 568 年报）：总收入 $250,000–$499,999 交 $900，$500,000–$999,999 交 $2,500，$1,000,000–$4,999,999 交 $6,000，$5,000,000 以上交 $11,790，不满 $250,000 不交 fee。**算例**：加州来源总收入 $600,000、净利只有 $60,000——fee 照样按 $600,000 落在 $2,500 档，加 $800 年税，实体层面先交 **$3,300**，成员再就穿透利润交加州个人所得税。
- **S 公司**：按净收入交 **1.5% 特许税（franchise tax）**（§ 23802，最低 $800），股东再就穿透份额交加州个人所得税。算例：净收入 $100,000，特许税 = $100,000 × 1.5% = **$1,500**。
- **C 公司**：特许税率 **8.84%**（§ 23151，最低 $800）。算例：应税净收入 $100,000，特许税 = **$8,840**。

### 六、取舍速查

| 维度 | 默认 LLC（穿透） | S 公司 | C 公司 |
| --- | --- | --- | --- |
| 联邦所得税层数 | 一层（个人） | 一层（个人，穿透） | 两层（公司 21%＋股息） |
| 15.3% 那层税 | 自雇税打在（几乎）全部净利上 | 只打在工资上，分配免 | 工资打工资税，股息不打 |
| 资格/结构限制 | 最松 | 股东 ≤100、单一股票类别、无外国股东 | 最松，可多类股票、可融资 |
| 加州实体层成本 | $800＋按毛收入分档 fee | 净收入 1.5%（最低 $800） | 净收入 8.84%（最低 $800） |
| 典型适用 | 刚起步、利润薄、出租与持有型 | 利润主要来自业主劳动且利润够厚 | 留存利润再投资、融资与股权规划 |

另有两条旁线只点名：穿透实体合格收入可能有 § 199A 的 20% QBI 扣除（另有专篇，S 公司工资与 W-2 工资上限会与合理工资互相牵动）；实体选错不是绝症——分类选举与 S 选举都有变更与迟交救济通道，但都有时间窗与一致性代价，动手前先算总账（联邦税＋自雇/工资税＋州税＋合规成本），别只盯着省下的那一刀。

**来源与依据**：IRC § 11(b)（C 公司 21%）、§ 701、§ 702、§ 705、§ 731（合伙穿透与基数分配）、§ 1361(b)（S 公司资格）、§ 1362 与 Form 2553（选举与期限）、§ 1366–§ 1368（穿透、基数与分配）、§ 1401、§ 1402 与 § 164(f)（SECA 税率、92.35% 口径与一半扣除）；Treas. Reg. § 301.7701-2、§ 301.7701-3 与 Form 8832（check-the-box）；SSA 公布的社保工资基数（2025 年 $176,100、2026 年 $184,500）与 IRS 自雇税专题页（15.3% 构成）；Rev. Rul. 74-44；David E. Watson, P.C. v. United States, 668 F.3d 1008 (8th Cir. 2012)（工资与分配数字见判决书事实部分）；加州 Revenue and Taxation Code § 17941（LLC 年税 $800）、§ 17942（LLC fee 四档）、§ 23802（S 公司 1.5%）、§ 23151（C 公司 8.84%）与 FTB 的 Form 568/3536/3522 说明。

*声明：个人学习笔记，不构成税务、财务或法律建议。具体设立即实体变更请以当年 IRC、IRS 表格说明与加州 FTB 口径为准，并咨询持牌 CPA 或税务律师。*

---

## English

**The decision in one line**: choosing an entity is choosing where profit is taxed, and as what. An LLC is a state-law shell; federal tax follows its classification under the check-the-box rules (Treas. Reg. §§ 301.7701-2, 301.7701-3). With no election, a single-member LLC is a **disregarded entity** (income lands on the owner's Schedule C), and a multi-member LLC is taxed as a **partnership** (Form 1065, income passes through on Schedule K-1 under IRC §§ 701–702). Electing corporate treatment takes Form 8832; electing S status takes Form 2553.

**Default LLC (pass-through)**: profit is taxed once, at the owners' individual rates, whether or not it is distributed — but active owners generally pay **self-employment tax (SECA, § 1401) of 15.3%** on it: **12.4% for Social Security, capped at the annual wage base ($176,100 for 2025; $184,500 for 2026, per the Social Security Administration), plus 2.9% for Medicare with no cap** (a further 0.9% Additional Medicare Tax can apply at high incomes). The tax applies to 92.35% of net earnings (Schedule SE), and one-half of the tax is deductible above the line (§ 164(f)). Example: $100,000 of 2025 Schedule C profit → base $92,350 → Social Security $92,350 × 12.4% = $11,451.40, Medicare $92,350 × 2.9% = $2,678.15, total SE tax **$14,129.55**, on top of income tax.

**S corporation**: eligibility comes first (§ 1361(b)) — a domestic corporation with **no more than 100 shareholders**, only eligible shareholders (no nonresident aliens, corporations or partnerships), and **one class of stock**; Form 2553 is generally due by the 15th day of the third month of the tax year. Profit passes through (§ 1366), but the saving is narrow: **salary** the owner takes as an employee bears FICA (15.3% combined), while **distributions bear no employment tax**. Example: on $120,000 of profit before owner pay, full pass-through self-employment tax would be $120,000 × 92.35% × 15.3% = **$16,955.46**; as an S corporation paying a $60,000 salary, payroll tax is $60,000 × 15.3% = **$9,180** — a gross difference of $7,775.46 before payroll-compliance costs and California tax. The salary must be **reasonable**: in *David E. Watson, P.C. v. United States*, 668 F.3d 1008 (8th Cir. 2012), an experienced CPA paid himself $24,000 in salary against distributions of $203,651 (2002) and $175,470 (2003), and the courts upheld recharacterizing part of the distributions as wages (see also Rev. Rul. 74-44).

**C corporation**: a separate taxpayer at a **flat 21% under § 11**, and a second layer when after-tax profit is paid out as dividends — **double taxation**. Example: $100,000 of profit → corporate tax $21,000; the remaining $79,000 as a qualified dividend at 15% costs $11,850, for a combined **$32,850 (32.85%)**; at a 23.8% dividend rate (20% plus the 3.8% net investment income tax) the combined burden is $39,802, about 39.8%. The C form earns its keep when profits stay inside the business or equity financing is planned, not when every dollar is taken home.

**California**: an LLC owes an **$800 annual tax** (Rev. & Tax. Code § 17941) plus a **fee on California-source total income** (§ 17942): $900 at $250,000–$499,999, $2,500 at $500,000–$999,999, $6,000 at $1,000,000–$4,999,999 and $11,790 at $5,000,000 or more — so $600,000 of total income means $2,500 plus $800 = **$3,300** at the entity level even on thin profit. An S corporation pays a **1.5% franchise tax** on net income (§ 23802, $800 minimum; $100,000 → $1,500); a C corporation pays **8.84%** (§ 23151, $800 minimum; $100,000 → $8,840). Owners are then taxed again at the individual level on pass-through income.

*Personal study notes only; not tax, financial or legal advice. Check the current Code, IRS form instructions and FTB guidance for your year, and consult a licensed CPA or tax attorney.*

## Español

**La decisión en una línea**: elegir entidad es elegir dónde tributa la ganancia y como qué. La LLC es una figura del derecho estatal; el impuesto federal sigue su clasificación según las reglas check-the-box (Treas. Reg. §§ 301.7701-2 y 301.7701-3). Sin elección, la LLC de un solo miembro es una **entidad ignorada (disregarded)** — el ingreso va al Anexo C del dueño — y la de varios miembros tributa como **sociedad colectiva (partnership)**: Formulario 1065 y traspaso (pass-through) en el Anexo K-1 (IRC §§ 701–702). Para tributar como corporación se presenta el Formulario 8832; para el estatus S, el Formulario 2553.

**LLC por defecto (traspaso)**: la ganancia tributa una sola vez, a las tasas individuales de los dueños, se distribuya o no; pero los dueños activos pagan por lo general el **impuesto sobre el trabajo por cuenta propia (SECA, § 1401) del 15,3%**: **12,4% de Seguridad Social, con tope en la base salarial anual (176.100 dólares en 2025; 184.500 en 2026, según la Social Security Administration), más 2,9% de Medicare sin tope** (con un 0,9% adicional posible en ingresos altos). El impuesto se aplica sobre el 92,35% de la ganancia neta (Schedule SE) y la mitad es deducible (§ 164(f)). Ejemplo: 100.000 dólares de ganancia en 2025 → base 92.350 → Seguridad Social 92.350 × 12,4% = 11.451,40; Medicare 92.350 × 2,9% = 2.678,15; total **14.129,55 dólares**, además del impuesto sobre la renta.

**Corporación S**: primero la elegibilidad (§ 1361(b)): corporación nacional con **no más de 100 accionistas**, solo accionistas permitidos (nada de extranjeros no residentes, corporaciones ni sociedades) y **una sola clase de acciones**; el Formulario 2553 vence, en general, el día 15 del tercer mes del año fiscal. La ganancia se traspasa (§ 1366) y el ahorro es puntual: el **salario** del dueño-empleado paga FICA (15,3% combinado), mientras que las **distribuciones no pagan impuesto sobre el empleo**. Ejemplo: con 120.000 dólares de ganancia antes de pagar al dueño, el impuesto de cuenta propia en traspaso sería 120.000 × 92,35% × 15,3% = **16.955,46**; como corporación S con salario de 60.000, el impuesto sobre la nómina es 60.000 × 15,3% = **9.180** — diferencia bruta de 7.775,46 antes de costos de cumplimiento y del impuesto de California. El salario debe ser **razonable**: en *David E. Watson, P.C. v. United States*, 668 F.3d 1008 (8th Cir. 2012), un CPA experimentado se pagó 24.000 dólares de salario frente a distribuciones de 203.651 (2002) y 175.470 (2003), y los tribunales confirmaron reclasificar parte de las distribuciones como salario (véase también Rev. Rul. 74-44).

**Corporación C**: contribuyente separado con **tasa única del 21% (§ 11)** y segunda capa cuando la ganancia neta sale como dividendos: la **doble imposición**. Ejemplo: 100.000 de ganancia → impuesto corporativo 21.000; los 79.000 restantes como dividendo calificado al 15% cuestan 11.850; carga combinada **32.850 (32,85%)**. Con dividendos al 23,8% (20% más el 3,8% de NIIT), el total es 39.802, cerca del 39,8%. La forma C se justifica cuando la ganancia se reinvierte o se busca financiamiento con capital, no cuando todo se lleva a casa.

**California**: la LLC debe un **impuesto anual de 800 dólares** (Rev. & Tax. Code § 17941) más una **cuota según el ingreso total de fuente californiana** (§ 17942): 900 dólares entre 250.000 y 499.999; 2.500 entre 500.000 y 999.999; 6.000 entre 1.000.000 y 4.999.999; y 11.790 desde 5.000.000 — con 600.000 de ingreso total, son 2.500 + 800 = **3.300** a nivel de entidad, aunque la ganancia neta sea pequeña. La corporación S paga el **1,5%** sobre el ingreso neto (§ 23802, mínimo 800; 100.000 → 1.500) y la C el **8,84%** (§ 23151, mínimo 800; 100.000 → 8.840).

*Notas personales de estudio; no constituye asesoría fiscal, financiera ni legal. Verifique el Código vigente, las instrucciones de los formularios del IRS y la guía del FTB de su año, y consulte a un CPA o abogado fiscal con licencia.*

## 한국어 (초역, 교정 대기 — 초벌 번역, 원어민 교정 대기)

**한 줄 결론**: 법인 형태 선택은 이익이 어느 층에서, 어떤 세금으로 과세되는지를 정하는 일입니다. LLC는 주법상의 껍데기이고, 연방세는 check-the-box 규칙(Treas. Reg. §§ 301.7701-2, 301.7701-3)에 따른 분류를 따릅니다. 선택이 없으면 1인 LLC는 **무시되는 실체(disregarded entity)** 로 소유주의 Schedule C에 소득이 바로 잡히고, 다수 구성원 LLC는 **파트너십** 으로 과세됩니다(Form 1065, IRC §§ 701–702에 따라 Schedule K-1로 통과). 법인 과세를 원하면 Form 8832, S 지위를 원하면 Form 2553을 냅니다.

**기본 LLC(통과 과세)**: 이익은 분배 여부와 무관하게 소유주 개인 세율로 한 번 과세되지만, 적극적으로 경영하는 소유주는 대개 **자영업세(SECA, § 1401) 15.3%** 를 냅니다. **사회보장 12.4%는 연도별 임금 상한까지만(2025년 $176,100, 2026년 $184,500 — Social Security Administration 발표), 메디케어 2.9%는 상한이 없습니다**(고소득 시 0.9% 추가 메디케어세가 붙을 수 있음). 세금은 순이익의 92.35%(Schedule SE)에 매겨지고, 그 절반은 § 164(f)에 따라 조정으로 공제됩니다. 예: 2025년 Schedule C 이익 $100,000 → 과세 표준 $92,350 → 사회보장 $92,350 × 12.4% = $11,451.40, 메디케어 $92,350 × 2.9% = $2,678.15, 자영업세 합계 **$14,129.55** 로, 소득세와 별도로 냅니다.

**S 법인**: 먼저 자격(§ 1361(b)) — 국내 법인이어야 하고, **주주 100명 이하**, 허용된 주주만 가능(비거주 외국인·법인·파트너십 주주 불가), **주식 한 종류만** 허용됩니다. Form 2553은 원칙적으로 과세연도 셋째 달 15일까지입니다. 이익은 통과(§ 1366)되고, 절세 지점은 하나뿐입니다. 소유주가 종업원으로서 받는 **급여** 에는 FICA(합계 15.3%)가 붙지만, **분배에는 고용세가 없습니다**. 예: 소유주에게 주기 전 이익 $120,000이면 통과 자영업세는 $120,000 × 92.35% × 15.3% = **$16,955.46** 이고, S 법인으로 급여 $60,000을 주면 급여세는 $60,000 × 15.3% = **$9,180** 으로, 급여 신고 비용과 캘리포니아 세금을 빼기 전 총액 차이 **$7,775.46** 입니다. 급여는 **합리적** 이어야 합니다. *David E. Watson, P.C. v. United States*, 668 F.3d 1008 (8th Cir. 2012)에서 경력 많은 CPA가 급여 $24,000에 분배 $203,651(2002년)·$175,470(2003년)을 가져갔고, 법원은 분배 일부를 급여로 재분류한 IRS 처분을 유지했습니다(Rev. Rul. 74-44 참조).

**C 법인**: **§ 11의 단일 세율 21%** 로 따로 과세되는 납세자이며, 세후 이익이 배당으로 나갈 때 두 번째 층이 생기는 **이중과세** 구조입니다. 예: 이익 $100,000 → 법인세 $21,000, 남은 $79,000을 적격 배당 15%로 받으면 $11,850, 합계 **$32,850(32.85%)** 입니다. 배당 세율이 23.8%(20% + NIIT 3.8%)이면 합계 $39,802, 약 39.8%입니다. C 형태는 이익을 사업 안에 남겨 재투자하거나 지분 금융을 계획할 때 맞고, 돈을 전부 집으로 가져갈 때는 대개 맞지 않습니다.

**캘리포니아**: LLC는 **연 $800 세금**(Rev. & Tax. Code § 17941)에 더해 캘리포니아 원천 **총소득** 기준 수수료(§ 17942)를 냅니다 — $250,000–$499,999 구간 $900, $500,000–$999,999 구간 $2,500, $1,000,000–$4,999,999 구간 $6,000, $5,000,000 이상 $11,790. 총소득 $600,000이면 순이익이 얇아도 법인 단계에서 $2,500 + $800 = **$3,300** 입니다. S 법인은 순이익의 **1.5%**(§ 23802, 최소 $800; $100,000 → $1,500), C 법인은 **8.84%**(§ 23151, 최소 $800; $100,000 → $8,840)입니다.

*개인 학습 노트이며 세무·재무·법률 자문이 아닙니다. 해당 연도의 현행 법전, IRS 양식 설명과 FTB 안내를 확인하고 면허 있는 CPA나 세무 변호사에게 상담하십시오. (초역, 교정 대기)*
- 보충(중국어 본문과 대조): 무시되는 실체라도 소득 종류에 따라 신고 위치가 갈립니다. 사업 소득은 Schedule C, 임대 소득은 Schedule E로 갑니다. 다수 구성원 파트너십에서는 자영업세만이 아니라 § 705의 기준가액(basis)과 § 731의 분배 규칙도 함께 따라옵니다.
- 보충: Form 2553의 제출 기한에서 새 법인은 첫 달부터 세어 셉니다. 기한을 넘겨도 합리적 사유가 있으면 IRS의 지체 구제를 신청할 수 있으나, 이유를 설명해야 하고 자동으로 인정되는 것은 아닙니다.
- 보충: S 법인도 법인 단계 세금이 완전히 없지는 않습니다. 내재 이익세(built-in gains tax) 같은 예외가 있고, 고용주가 부담하는 급여세 절반은 법인 비용으로 공제됩니다. 분배를 받기 전에 § 1367·§ 1368의 주주 기준가액이 분배를 뒷받침해야 하며, 이익이 얇으면 아낀 세금이 급여 신고와 회계 비용보다 적을 수 있습니다.
- 보충: C 법인의 급여 검사는 반대 방향으로도 작동합니다. 주주-종업원 급여가 지나치게 높으면 변장된 배당으로 보아 재분류될 수 있습니다.
- 보충: 통과 실체의 적격 소득에는 § 199A의 20% QBI 공제가 붙을 수 있는데, S 법인의 W-2 급여 한도가 합리적 급여 수준과 서로 맞물립니다. 급여를 정할 때 두 제도를 함께 봐야 합니다.
- 보충: 실체 선택을 잘못해도 끝은 아닙니다. 분류 선택과 S 선택에는 변경과 지체 구제의 창구가 있지만 시간 제한과 일관성 비용이 따릅니다. 캘리포니아는 연방 분류를 완전히 따르지 않고 양식도 다르며, LLC 수수료는 Form 3536으로 예납하고 Form 568로 연례 신고합니다. 총소득이 $250,000 미만이면 수수료 자체가 없습니다. (초역 보충, 교정 대기)

## Tiếng Việt (初译待校 — Bản dịch sơ bộ, chờ hiệu đính)

**Kết luận một dòng**: chọn loại hình doanh nghiệp là chọn lợi nhuận bị đánh thuế ở tầng nào và bằng loại thuế nào. LLC là vỏ pháp lý cấp bang; thuế liên bang đi theo phân loại check-the-box (Treas. Reg. §§ 301.7701-2, 301.7701-3). Nếu không chọn gì, LLC một thành viên là **thực thể bị bỏ qua (disregarded entity)** — thu nhập ghi thẳng vào Schedule C của chủ sở hữu — và LLC nhiều thành viên bị đánh thuế như **hợp danh (partnership)**: Form 1065, lợi nhuận xuyên qua Schedule K-1 theo IRC §§ 701–702. Muốn bị đánh thuế như công ty thì nộp Form 8832; muốn tư cách S thì nộp Form 2553.

**LLC mặc định (xuyên qua)**: lợi nhuận chỉ bị đánh thuế một lần theo thuế suất cá nhân của chủ sở hữu, dù có phân phối hay không — nhưng chủ sở hữu trực tiếp kinh doanh thường phải nộp **thuế tự doanh (SECA, § 1401) 15,3%**: **12,4% An sinh xã hội, chỉ tính đến trần lương hằng năm (176.100 đô la năm 2025; 184.500 đô la năm 2026, theo Social Security Administration), cộng 2,9% Medicare không có trần** (thu nhập cao có thể thêm 0,9% thuế Medicare bổ sung). Thuế tính trên 92,35% thu nhập ròng (Schedule SE), và một nửa số thuế được khấu trừ trên dòng (§ 164(f)). Ví dụ: lợi nhuận Schedule C năm 2025 là 100.000 đô la → căn cứ 92.350 → An sinh xã hội 92.350 × 12,4% = 11.451,40; Medicare 92.350 × 2,9% = 2.678,15; tổng thuế tự doanh **14.129,55 đô la**, ngoài thuế thu nhập.

**Công ty S**: trước hết là điều kiện (§ 1361(b)) — công ty trong nước, **không quá 100 cổ đông**, chỉ cổ đông đủ điều kiện (không có người nước ngoài không cư trú, không có công ty hay hợp danh làm cổ đông) và **chỉ một loại cổ phiếu**; Form 2553 thường phải nộp trước ngày 15 của tháng thứ ba của năm thuế. Lợi nhuận xuyên qua (§ 1366), và điểm tiết kiệm rất hẹp: **lương** chủ sở hữu nhận với tư cách nhân viên phải chịu FICA (tổng 15,3%), còn **phần phân phối không chịu thuế việc làm**. Ví dụ: với 120.000 đô la lợi nhuận trước khi trả cho chủ, thuế tự doanh theo cách xuyên qua là 120.000 × 92,35% × 15,3% = **16.955,46**; nếu là công ty S trả lương 60.000 thì thuế lương là 60.000 × 15,3% = **9.180** — chênh lệch gộp **7.775,46** trước chi phí tuân thủ lương và thuế California. Lương phải **hợp lý**: trong vụ *David E. Watson, P.C. v. United States*, 668 F.3d 1008 (8th Cir. 2012), một CPA giàu kinh nghiệm chỉ trả cho mình 24.000 đô la lương trong khi lấy phân phối 203.651 đô la (2002) và 175.470 đô la (2003), và tòa án giữ nguyên việc IRS phân loại lại một phần phân phối thành lương (xem thêm Rev. Rul. 74-44).

**Công ty C**: là người nộp thuế riêng với **thuế suất phẳng 21% theo § 11**, và tầng thuế thứ hai xuất hiện khi lợi nhuận sau thuế được chia cổ tức — **đánh thuế hai lần**. Ví dụ: lợi nhuận 100.000 → thuế công ty 21.000; phần còn 79.000 nhận cổ tức đủ điều kiện ở mức 15% tốn 11.850; tổng cộng **32.850 (32,85%)**. Nếu cổ tức chịu 23,8% (20% cộng NIIT 3,8%), tổng là 39.802, khoảng 39,8%. Loại hình C phù hợp khi lợi nhuận ở lại trong doanh nghiệp để tái đầu tư hoặc khi có kế hoạch huy động vốn cổ phần, không phải khi rút hết tiền về nhà.

**California**: LLC nợ **800 đô la thuế hằng năm** (Rev. & Tax. Code § 17941) cộng **phí theo tổng thu nhập từ nguồn California** (§ 17942): 900 đô la ở mức 250.000–499.999; 2.500 ở mức 500.000–999.999; 6.000 ở mức 1.000.000–4.999.999; và 11.790 từ 5.000.000 trở lên — với tổng thu nhập 600.000, phần ở cấp thực thể là 2.500 + 800 = **3.300** dù lợi nhuận mỏng. Công ty S nộp **1,5%** trên thu nhập ròng (§ 23802, tối thiểu 800; 100.000 → 1.500) và công ty C nộp **8,84%** (§ 23151, tối thiểu 800; 100.000 → 8.840).

*Ghi chú học tập cá nhân, không phải tư vấn thuế, tài chính hay pháp lý. Hãy đối chiếu Bộ luật hiện hành, hướng dẫn biểu mẫu của IRS và hướng dẫn của FTB cho năm của bạn, và tham vấn CPA hoặc luật sư thuế có giấy phép. (Bản dịch sơ bộ, chờ hiệu đính)*
- Bổ sung (đối chiếu văn bản tiếng Trung): dù là thực thể bị bỏ qua, vị trí khai báo vẫn tùy loại thu nhập — thu nhập kinh doanh vào Schedule C, thu nhập cho thuê vào Schedule E. Với hợp danh nhiều thành viên, ngoài thuế tự doanh còn có basis theo § 705 và quy tắc phân phối theo § 731.
- Bổ sung: kỳ hạn nộp Form 2553 với công ty mới được tính từ tháng đầu tiên. Nộp trễ vẫn có thể xin cứu xét của IRS nếu có lý do hợp lý, nhưng phải giải trình và không được chấp nhận tự động.
- Bổ sung: công ty S không phải hoàn toàn không có thuế ở cấp thực thể — vẫn có các ngoại lệ như thuế built-in gains; một nửa thuế lương do chủ lao động gánh được khấu trừ như chi phí kinh doanh. Trước khi nhận phân phối, basis của cổ đông theo § 1367 và § 1368 phải đủ chống đỡ phần phân phối; lợi nhuận mỏng thì số thuế tiết kiệm có thể không bù nổi chi phí lương và kế toán.
- Bổ sung: với công ty C, việc rà soát lương chạy theo chiều ngược lại — lương cổ đông-nhân viên quá cao có thể bị xem là cổ tức trá hình và bị phân loại lại.
- Bổ sung: thu nhập đủ điều kiện của thực thể xuyên qua có thể được khấu trừ QBI 20% theo § 199A, và trần lương W-2 của công ty S gắn chặt với mức lương hợp lý — phải xem hai chế độ cùng nhau khi ấn định lương.
- Bổ sung: chọn sai loại hình không phải là hết đường — lựa chọn phân loại và lựa chọn S đều có cửa thay đổi và cứu xét nộp trễ, nhưng có cửa sổ thời gian và chi phí nhất quán. California không tuân theo hoàn toàn phân loại liên bang và dùng biểu mẫu riêng; phí LLC được tạm nộp bằng Form 3536 và khai hằng năm bằng Form 568, và không có phí nếu tổng thu nhập dưới 250.000 đô la. (Bổ sung bản dịch sơ bộ, chờ hiệu đính)

## हिन्दी (初译待校 — प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

**एक पंक्ति का निष्कर्ष**: इकाई चुनना यह चुनना है कि लाभ किस स्तर पर और किस कर से लगेगा। LLC राज्य-कानून का खोल है; संघीय कर उसकी check-the-box वर्गीकरण (Treas. Reg. §§ 301.7701-2, 301.7701-3) के अनुसार चलता है। कोई चुनाव न हो तो एकल-सदस्य LLC **अनदेखी इकाई (disregarded entity)** है — आय सीधे मालिक के Schedule C में जाती है — और बहु-सदस्य LLC **साझेदारी (partnership)** की तरह कर लगाती है: Form 1065 और IRC §§ 701–702 के तहत Schedule K-1 से आय सीधे मालिकों तक। कंपनी जैसा कर चाहें तो Form 8832, S दर्जा चाहें तो Form 2553 भरें।

**डिफ़ॉल्ट LLC (pass-through)**: लाभ बँटे या न बँटे, मालिकों की व्यक्तिगत दरों से केवल एक बार कर लगता है — लेकिन सक्रिय मालिकों पर आम तौर पर **स्व-रोज़गार कर (SECA, § 1401) 15.3%** लगता है: **सामाजिक सुरक्षा का 12.4%, वार्षिक वेतन आधार की सीमा तक (2025 में $176,100; 2026 में $184,500, Social Security Administration के अनुसार), और Medicare का 2.9% बिना किसी सीमा के** (उच्च आय पर 0.9% अतिरिक्त Medicare कर भी लग सकता है)। कर शुद्ध आय के 92.35% पर लगता है (Schedule SE) और उसका आधा हिस्सा § 164(f) के तहत above-the-line कटौती योग्य है। उदाहरण: 2025 में Schedule C लाभ $100,000 → आधार $92,350 → सामाजिक सुरक्षा $92,350 × 12.4% = $11,451.40, Medicare $92,350 × 2.9% = $2,678.15, कुल स्व-रोज़गार कर **$14,129.55**, आयकर से अलग।

**S कंपनी**: पहले पात्रता (§ 1361(b)) — घरेलू कंपनी, **शेयरधारक 100 से अधिक नहीं**, केवल पात्र शेयरधारक (अनिवासी विदेशी, कंपनी या साझेदारी शेयरधारक नहीं) और **शेयरों की केवल एक श्रेणी**; Form 2553 आम तौर पर कर वर्ष के तीसरे महीने की 15 तारीख तक देय है। लाभ pass-through होता है (§ 1366), और बचत का बिंदु संकरा है: मालिक कर्मचारी के रूप में जो **वेतन** लेता है उस पर FICA (संयुक्त 15.3%) लगता है, जबकि **वितरण पर रोज़गार कर नहीं** लगता। उदाहरण: मालिक को देने से पहले लाभ $120,000 हो तो pass-through स्व-रोज़गार कर $120,000 × 92.35% × 15.3% = **$16,955.46** होगा; S कंपनी बनकर $60,000 वेतन दें तो वेतन कर $60,000 × 15.3% = **$9,180** — वेतन-अनुपालन लागत और California कर से पहले सकल अंतर **$7,775.46**। वेतन **उचित** होना चाहिए: *David E. Watson, P.C. v. United States*, 668 F.3d 1008 (8th Cir. 2012) में एक अनुभवी CPA ने स्वयं को $24,000 वेतन देकर वितरण के रूप में $203,651 (2002) और $175,470 (2003) लिए, और अदालतों ने वितरण के एक हिस्से को वेतन में पुनर्वर्गीकृत करने का IRS का निर्णय बरकरार रखा (Rev. Rul. 74-44 भी देखें)।

**C कंपनी**: **§ 11 के तहत 21% की एकल दर** से अलग करदाता है, और कर-पश्चात लाभ लाभांश के रूप में बाहर जाने पर दूसरी परत बनती है — **दोहरा कराधान**। उदाहरण: लाभ $100,000 → कंपनी कर $21,000; शेष $79,000 योग्य लाभांश के रूप में 15% पर $11,850; संयुक्त भार **$32,850 (32.85%)**। लाभांश दर 23.8% (20% + NIIT 3.8%) हो तो कुल $39,802, लगभग 39.8%। C रूप तब काम का है जब लाभ व्यवसाय में ही रहकर पुनर्निवेश हो या इक्विटी वित्तपोषण की योजना हो, न कि जब हर डॉलर घर ले जाना हो।

**California**: LLC पर **$800 वार्षिक कर** (Rev. & Tax. Code § 17941) और California-स्रोत **कुल आय** पर शुल्क (§ 17942) दोनों लगते हैं: $250,000–$499,999 पर $900, $500,000–$999,999 पर $2,500, $1,000,000–$4,999,999 पर $6,000 और $5,000,000 या अधिक पर $11,790 — कुल आय $600,000 हो तो लाभ पतला होने पर भी इकाई स्तर पर $2,500 + $800 = **$3,300**। S कंपनी शुद्ध आय पर **1.5%** (§ 23802, न्यूनतम $800; $100,000 → $1,500) और C कंपनी **8.84%** (§ 23151, न्यूनतम $800; $100,000 → $8,840) देती है।

*व्यक्तिगत अध्ययन नोट; कर, वित्तीय या कानूनी सलाह नहीं। अपने वर्ष के वर्तमान Code, IRS फ़ॉर्म निर्देशों और FTB मार्गदर्शन से सत्यापित करें और लाइसेंसधारी CPA या कर वकील से परामर्श करें। (प्रारंभिक अनुवाद, समीक्षा लंबित)*
- पूरक (चीनी मूल पाठ से मिलान): disregarded entity होने पर भी आय का स्थान उसकी प्रकृति से तय होता है — व्यावसायिक आय Schedule C में, किराया आय Schedule E में जाती है। बहु-सदस्य साझेदारी में स्व-रोज़गार कर के साथ § 705 का basis और § 731 के वितरण नियम भी लागू होते हैं।
- पूरक: Form 2553 की समय-सीमा नई कंपनी के लिए उसके पहले महीने से गिनी जाती है। देर से दाखिल करने पर उचित कारण हो तो IRS से late relief माँगा जा सकता है, किंतु कारण बताना पड़ता है और relief स्वतः नहीं मिलता।
- पूरक: S कंपनी पर इकाई-स्तर का कर पूरी तरह शून्य नहीं है — built-in gains tax जैसे अपवाद हैं; नियोक्ता द्वारा दिया गया आधा वेतन कर व्यावसायिक व्यय के रूप में कटौती योग्य है। वितरण लेने से पहले § 1367 व § 1368 के तहत शेयरधारक basis का वितरण को सहारा देना आवश्यक है; लाभ पतला हो तो बचत वेतन-अनुपालन और लेखा लागत से कम भी हो सकती है।
- पूरक: C कंपनी में वेतन की जाँच उल्टी दिशा में भी चलती है — शेयरधारक-कर्मचारी का अत्यधिक वेतन छिपा लाभांश मानकर पुनर्वर्गीकृत हो सकता है।
- पूरक: pass-through इकाई की पात्र आय पर § 199A की 20% QBI कटौती मिल सकती है, और S कंपनी की W-2 वेतन सीमा उचित वेतन के स्तर से जुड़ी है — वेतन तय करते समय दोनों व्यवस्थाएँ साथ देखनी चाहिए।
- पूरक: ग़लत इकाई चुनना अंतिम नहीं है — वर्गीकरण चुनाव और S चुनाव दोनों में परिवर्तन और विलंब-राहत के मार्ग हैं, किंतु समय-सीमा और संगति लागत के साथ। California संघीय वर्गीकरण का पूर्ण अनुसरण नहीं करता और उसके फ़ॉर्म अलग हैं; LLC शुल्क Form 3536 से अग्रिम और Form 568 से वार्षिक दाखिल होता है, और कुल आय $250,000 से कम हो तो शुल्क लगता ही नहीं। (पूरक प्रारंभिक अनुवाद, समीक्षा लंबित)
