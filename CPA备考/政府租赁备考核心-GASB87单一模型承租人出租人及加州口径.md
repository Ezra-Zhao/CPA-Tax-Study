# 政府租赁备考核心：GASB 87 的单一模型、承租人与出租人会计及加州口径

> 个人学习笔记，不构成税务或会计建议。准则以 GASB Statement No. 87, Leases（2017 年 6 月发布）现行文本为准。Personal study notes, not tax or accounting advice.

## 中文主文

### 一、先定性：租赁是取得使用权的融资

GASB 第 87 号公告（Statement No. 87, Leases，2017 年 6 月发布）把州与地方政府的租赁会计从旧的「经营租赁／资本租赁」二分，改成一套单一模型。它的地基只有一句话：租赁的实质是为取得标的资产使用权而进行的融资（financing of the right to use an underlying asset）。租赁的定义随之收紧：一份合同构成租赁，须是「在交换或类交换交易中，转让在一段期间内控制使用另一主体非金融资产（标的资产）的权利」（GASB 87 第 4 段一带）。三个词抠住就不会跑偏：控制（control）、非金融资产（nonfinancial asset）、一段期间（period of time）。只有使用权、没有控制的服务合同不是租赁；标的是金融资产的也不走这条线。

生效日要记准：经 GASB 第 95 号公告因疫情顺延 18 个月后，第 87 号适用于 2021 年 6 月 15 日之后开始的财政年度及此后所有报告期，鼓励提前适用。过渡上，按实施期初存在的事实与情况确认计量，不要求把每一份旧合同从签约日重算一遍。加州政府普遍以 6 月 30 日为财年末，首个适用年度就是截至 2022 年 6 月 30 日的财年（2021 年 7 月 1 日开始）。

### 二、范围与两条出口：短期租赁与转移所有权

先把不进单一模型的情形排干净，这是考试最爱埋的坑：

- **短期租赁（short-term lease）**：在合同开始日，含全部延展选择权在内的最长可能租期（maximum possible term）为 12 个月或更短——注意看的是「最长可能」，与选择权行使的可能性无关。短期租赁不确认负债与使用权资产，承租人按付款进度确认费用，出租人按收款进度确认收入。
- **转移所有权的合同**：合同到期把标的资产所有权转给承租人的，根本不按租赁处理——承租人按融资购买（financed purchase）确认资产与负债，出租人按出售处理。
- **范围外标的**：无形资产（含后来被 GASB 96 单独接管的订阅制 IT 安排，见本仓 GASB 96 专篇）、生物资产、存货不走第 87 号；服务特许经营安排走 GASB 60，纯供应合同（supply contract）若不构成租赁定义也排除在外。出租人一侧另有窄例外：标的资产系持有待投资的、以及某些受管制租赁（regulated leases，如联邦规制的机场类安排），不按应收加递延流入的一般模型确认。

与企业会计的 ASC 842 对照着记最省力：ASC 842 承租人保留融资租赁／经营租赁双模型（费用形态不同），GASB 87 承租人只有一套模型；两边的出租人模型分岔更大，不要把 ASC 842 的销售型／直接融资型分类搬进政府报表。

### 三、承租人：一条负债、一项无形使用权资产

确认时点为租期开始日（commencement）。计量两步：

- **租赁负债**：租期内预期支付款项的现值。进现值的付款包括固定付款（含实质固定付款）、按指数或利率决定的可变付款（按开始日指数计量）、购买选择权行权价（行使相当确定时）、终止罚金（租期口径已反映会终止时）与残值担保下预计支付额等。折现率先用出租人在合同中收取的利率（即内含利率，可确定时），定不出来才用承租人的估计增量借款利率（estimated incremental borrowing rate）。
- **租赁资产**：以负债为锚——负债初始额，加上开始日或之前已付的款项、为使资产投入使用而发生的辅助性初始直接成本，减去收到的租赁激励。资产性质是无形的使用权资产（intangible right-to-use asset），列报上与自有资本资产分开。

后续计量：负债按实际利率法逐期滚利息、随付款减少；使用权资产一般在租期与资产使用寿命两者较短者内系统摊销，于是承租人的费用形态是「利息＋摊销」，前期偏高——这是单一模型与旧经营租赁直线租金最直观的区别。政府基金（修正权责发生制）层面另有列报口径：租期开始时按负债现值确认一笔支出与一笔其他融资来源，后续付款再拆本金与利息列支，答题时先看问的是政府层面报表还是基金报表，别混口径。

算例（虚构教学例，折现口径已本地两遍复算）：某市租入设备 5 年，每年末付 100,000 美元，折现率 3%，无预付、无激励、无初始直接成本。负债现值＝100,000 × 年金现值系数（3%，5 期）＝100,000 × 4.579707＝457,971 美元（精确值 457,970.72，四舍五入计），使用权资产同为 457,971 美元。第 1 年利息＝457,971 × 3%＝13,739 美元，当年付款 100,000 美元中本金部分 86,261 美元，年末负债＝457,971－86,261＝371,710 美元。使用权资产按 5 年直线摊销，每年 457,971 ÷ 5＝91,594 美元。全期勾稽：付款总额 500,000＝本金 457,971＋利息合计 42,029，数字闭合。

### 四、出租人：应收与递延流入并行，标的资产不出表

出租人在租期开始日确认**租赁应收款**（计量与承租人负债同法：租期内预期收款的现值）与**递延流入资源**（deferred inflow of resources，初始额原则上等于应收款，加上开始日前已收的与未来期间相关的款项，减激励）。关键一条：出租人**不终止确认标的资产**——资产留在出租人表上、继续按原政策折旧，这与旧资本租赁下出租人的处理正相反，也是 GASB 87 出租人模型与 ASC 842 销售型租赁最刺眼的分界。后续期间，出租人一面按实际利率确认应收款的利息收入，一面把递延流入按系统合理的方法（通常直线）转作租赁收入，于是收入是「利息＋租赁收入」双线并行。短期租赁、转移所有权与前述投资性持有等例外不走这套确认。

### 五、租期、重估与重新计量：什么时候回头改数字

租期＝不可取消期间，加上承租人行使相当确定（reasonably certain）的延展选择权覆盖期间、减去终止选择权相当确定行使时截断的部分；含购买选择权且行使相当确定时，租期不因该选择权提前结束。租期只在准则列明的事件发生时才重估（如选择权行使与否的事实发生决定性变化、合同修改增删标的资产等），不许每年凭感觉重估。负债的重新计量（remeasurement）触发点要背：租期变化、购买选择权行使确定性变化、付款所依据的指数或利率变动导致付款变化（此种情形同时调资产、一般不改折现率口径细节以准则为准）、残值担保预计付款变化等；重新计量调负债的同时一般等额调使用权资产，资产已减记至零的余量进当期损益。合同修改先分流：增加标的资产且对价相应增加的，按一份新租赁处理；其余修改回到租期与计量重估。附注披露两边都要：承租人披露使用权资产类别、负债到期结构与选择权安排，出租人披露应收与递延流入及受管制租赁等专门信息——披露问答在 CPA 政府会计部分占比不低，别只背确认计量。

### 六、加州口径：州主计长实施指引与州政府内部门槛

加州一侧的落点有三层。其一，日历：加州州政府与多数地方政府 6 月 30 日年结，第 87 号自 2021 年 7 月 1 日开始的财年落地，加州主计长办公室（State Controller's Office）发布了全州实施指引与决策树，地方政府在年报（ACFR）中按同一框架列报，审计时先看该财年附注是否已切换到单一模型口径。其二，州政府内部执行门槛：加州州级部门实施文件中曾设「未来付款总额 100,000 美元或以上」的确认门槛作为内部重要性口径——这是加州州政府的内部执行标准，不是 GASB 87 本身的门槛，准则原文并无金额下限，地方政府各自的重要性门槛以各自政策与审计师口径为准，写作时不要把内部数字写成准则规则。其三，与本仓既有篇目的分工：订阅软件走 GASB 96、带薪缺勤走 GASB 101、风险披露走 GASB 102、报告模型走 GASB 103，租赁本体就是本篇的第 87 号；遇到混合合同（租赁＋服务＋订阅）先拆组件再各回各家。

### 七、备考清单

1. 定义三词：控制、非金融资产、一段期间；服务合同无控制即出局；
2. 短期看「最长可能租期 ≤12 个月」，含全部选择权、与可能性无关；
3. 转移所有权＝融资购买／出售，不是租赁；
4. 承租人：负债现值＋资产以负债为锚；折现率先内含、后增量借款利率；
5. 出租人：应收＋递延流入，标的资产不出表、继续折旧；
6. 费用与收入形态：承租人利息加摊销，出租人利息加递延转入；
7. 租期只在列明事件时重估，重新计量触发点逐项对准则；
8. 生效日：2021 年 6 月 15 日后开始的财年；加州首个适用财年截至 2022 年 6 月 30 日。

*个人学习笔记，不构成税务或会计建议。依据：GASB Statement No. 87, Leases（2017 年 6 月）与 GASB 官方摘要、GASB Statement No. 95 顺延口径、加州主计长办公室 GASB 87 实施文件（州级部门内部 100,000 美元门槛为内部执行口径）。算例已经两遍复算：100,000 × 4.579707 ＝ 457,971；457,971 × 3% ＝ 13,739；457,971 − 86,261 ＝ 371,710；457,971 ÷ 5 ＝ 91,594；500,000 − 457,971 ＝ 42,029。*

---

## English

**Government leases for the CPA exam: GASB 87's single model, lessee and lessor accounting, and California.** GASB Statement No. 87, *Leases* (issued June 2017), replaces the old operating/capital split for state and local governments with a single model built on one principle: a lease is a financing of the right to use an underlying asset. A lease is a contract that conveys control of the right to use another entity's nonfinancial asset for a period of time in an exchange or exchange-like transaction. After the GASB 95 postponement, the standard applies to fiscal years beginning after June 15, 2021; for California's June 30 year-end governments, the first year was the fiscal year ended June 30, 2022.

**Scope and exits.** A short-term lease — maximum possible term of 12 months or less at commencement, including all extension options regardless of how likely exercise is — is not recognized; payments are expensed as made. A contract that transfers ownership is not a lease at all: the lessee accounts for a financed purchase and the lessor for a sale. Intangible assets (including the subscription-based IT arrangements later carved out to GASB 96), biological assets and inventory sit outside Statement 87, as do service concession arrangements (GASB 60) and supply contracts that fail the lease definition. Unlike ASC 842, GASB 87 keeps no dual lessee model.

**Lessee.** At commencement the lessee recognizes a lease liability at the present value of payments expected during the lease term — fixed and in-substance fixed payments, index- or rate-based variable payments measured at commencement, a purchase-option price if exercise is reasonably certain, termination penalties reflected in the term, and expected residual-guarantee payments — discounted at the rate the lessor charges if determinable, otherwise the lessee's estimated incremental borrowing rate. The intangible right-to-use asset starts from the liability, plus payments made at or before commencement and ancillary initial direct costs, minus incentives received. Afterwards the liability accretes interest while the asset is amortized, generally over the shorter of the term or the asset's useful life, producing the front-loaded "interest plus amortization" expense pattern; in governmental funds, commencement is reported as an expenditure and an other financing source.

Worked example (fictional, recomputed twice): five annual year-end payments of $100,000 at a 3% discount rate give a liability of $100,000 × 4.579707 = $457,971, and an equal right-to-use asset. Year 1 interest is $457,971 × 3% = $13,739, so $86,261 of the first payment is principal and the liability ends at $371,710; straight-line amortization is $457,971 ÷ 5 = $91,594 per year; total payments of $500,000 split into $457,971 principal and $42,029 interest.

**Lessor.** The lessor recognizes a lease receivable (present value of expected receipts) and a deferred inflow of resources, and — the sharpest contrast with sales-type leases under ASC 842 — does **not** derecognize the underlying asset, which keeps depreciating on the lessor's books. Interest revenue accrues on the receivable while the deferred inflow is released into lease revenue systematically over the term. Exceptions apply for short-term leases, ownership-transfer contracts, assets held as investments, and certain regulated leases.

**Term, reassessment, remeasurement.** The lease term is the noncancelable period plus reasonably certain extension periods, cut short where a termination option is reasonably certain to be exercised; the term is reassessed only on specified events, not annually at will. Remeasurement is triggered by changes in the term, in purchase-option certainty, in index- or rate-based payments, or in expected residual-guarantee amounts, with the offset generally to the right-to-use asset. **California:** the State Controller's Office issued statewide implementation guidance and decision trees; the $100,000 figure sometimes quoted is a California state-department internal capitalization threshold, not a floor in GASB 87 itself, which sets no dollar threshold.

*Personal study notes only; not tax or accounting advice.*

## Español (traducción de estudio, pendiente de revisión nativa)

**Arrendamientos gubernamentales para el examen CPA: el modelo único del GASB 87, contabilidad del arrendatario y del arrendador, y el criterio de California.** La Declaración n.º 87 del GASB, *Leases* (junio de 2017), sustituye la antigua división entre arrendamiento operativo y de capital en los gobiernos estatales y locales por un modelo único basado en un principio: el arrendamiento es una financiación del derecho a usar el activo subyacente. Hay arrendamiento cuando un contrato transfiere el control del derecho a usar el activo no financiero de otra entidad durante un período, en una transacción de intercambio o similar. Tras la prórroga del GASB 95, la norma rige para ejercicios iniciados después del 15 de junio de 2021; en California, con cierre al 30 de junio, el primer ejercicio fue el terminado el 30 de junio de 2022.

**Alcance y salidas.** El arrendamiento de corto plazo — plazo máximo posible de 12 meses o menos al inicio, incluidas todas las opciones de prórroga sin importar su probabilidad — no se reconoce: los pagos se gastan al realizarse. El contrato que transfiere la propiedad no es arrendamiento: el arrendatario lo trata como compra financiada y el arrendador como venta. Quedan fuera los activos intangibles (incluidos los arreglos de TI por suscripción, luego pasados al GASB 96), los activos biológicos y los inventarios, así como las concesiones de servicios (GASB 60) y los contratos de suministro que no cumplen la definición. A diferencia del ASC 842, el GASB 87 no mantiene un doble modelo para el arrendatario.

**Arrendatario.** Al inicio reconoce un pasivo por el valor presente de los pagos esperados durante el plazo — fijos y sustancialmente fijos, variables según índice o tasa medidos al inicio, precio de opción de compra si su ejercicio es razonablemente cierto, penalidades de terminación reflejadas en el plazo y pagos esperados por garantías de valor residual — descontados a la tasa que cobra el arrendador si es determinable, o a la tasa incremental estimada de endeudamiento del arrendatario. El activo intangible por derecho de uso parte del pasivo, más pagos hechos al inicio o antes y costos directos iniciales auxiliares, menos incentivos. Después, el pasivo devenga intereses y el activo se amortiza, en general en el menor entre el plazo y la vida útil, con el patrón de gasto «intereses más amortización», más cargado al principio; en fondos gubernamentales, el inicio se presenta como gasto y otra fuente de financiación.

Ejemplo (ficticio, recalculado dos veces): cinco pagos anuales de 100.000 dólares al final de cada año, al 3 %, dan un pasivo de 100.000 × 4,579707 = 457.971 dólares y un activo por el mismo importe. El interés del año 1 es 457.971 × 3 % = 13.739; el principal es 86.261 y el pasivo cierra en 371.710. La amortización lineal es 457.971 ÷ 5 = 91.594 al año, y los pagos totales de 500.000 se dividen en 457.971 de principal y 42.029 de intereses.

**Arrendador.** Reconoce una cuenta por cobrar por arrendamiento (valor presente de los cobros esperados) y una entrada diferida de recursos, y — el contraste más nítido con el arrendamiento tipo venta del ASC 842 — **no** da de baja el activo subyacente, que sigue depreciándose en su balance. Devenga intereses sobre la cuenta por cobrar y libera la entrada diferida como ingreso por arrendamiento de forma sistemática durante el plazo. Hay excepciones para corto plazo, transferencia de propiedad, activos mantenidos como inversión y ciertos arrendamientos regulados. **Plazo y remedición:** el plazo es el período no cancelable más las prórrogas razonablemente ciertas; solo se reevalúa ante hechos especificados, y la remedición se dispara por cambios de plazo, de certeza de la opción de compra, de pagos según índice o tasa, o de garantías de valor residual. **California:** la Oficina del Contralor estatal emitió guías de implementación; la cifra de 100.000 dólares que a veces se cita es un umbral interno de capitalización de los departamentos estatales, no un mínimo del GASB 87, que no fija umbral monetario. *Notas personales de estudio; no constituye asesoría fiscal ni contable. Traducción de estudio, pendiente de revisión por hablante nativo.*

## 한국어 (초역, 원어민 감수 대기)

**CPA 대비 정부 리스: GASB 87의 단일 모델, 리스이용자·리스제공자 회계, 캘리포니아 기준.** GASB 제87호(Leases, 2017년 6월 발표)는 주·지방정부의 기존 영업리스/자본리스 구분을 단일 모델로 바꿨습니다. 기초 원리는 하나입니다. 리스는 기초자산 사용권을 취득하는 금융(financing)입니다. 리스란 교환 또는 교환성 거래에서 일정 기간 다른 주체의 비금융자산 사용을 통제할 권리를 이전하는 계약을 말합니다. GASB 95의 연기 후 적용 시점은 2021년 6월 15일 이후 시작하는 회계연도이며, 6월 30일 결산인 캘리포니아 정부는 2022년 6월 30일 종료 연도가 첫 적용 연도입니다.

**범위와 출구.** 단기리스 — 시작 시점에 모든 연장 옵션을 포함해도 최장 가능 기간이 12개월 이하인 경우(행사 가능성과 무관) — 는 인식하지 않고 지급 시점에 비용 처리합니다. 소유권이 이전되는 계약은 리스가 아닙니다. 이용자는 자금조달 구매(financed purchase)로, 제공자는 매각으로 처리합니다. 무형자산(GASB 96으로 분리된 구독형 IT 포함), 생물자산, 재고자산은 제87호 밖에 있고, 서비스 양여 계약(GASB 60)과 리스 정의를 충족하지 못하는 공급 계약도 제외됩니다. ASC 842와 달리 GASB 87의 이용자 모델은 하나뿐입니다.

**리스이용자.** 시작 시점에 리스기간 중 예상 지급액의 현재가치로 리스부채를 인식합니다. 고정 및 실질 고정 지급액, 시작 시점 지수로 측정한 지수·요율 연동 변동 지급액, 행사가 합리적으로 확실한 매수옵션 가격, 리스기간에 반영된 해지 위약금, 잔존가치 보증 예상 지급액이 들어갑니다. 할인율은 제공자가 부과하는 이율(내재이율)을 쓸 수 있으면 그것을 쓰고, 없으면 이용자의 추정 증분차입이율을 씁니다. 무형의 사용권자산은 부채를 앵커로 하여 시작 전 지급액과 자산 사용 개시에 부수하는 초기직접원가를 더하고 받은 인센티브를 뺀 금액입니다. 이후 부채에는 이자가 쌓이고 자산은 통상 리스기간과 내용연수 중 짧은 기간에 상각되어 「이자＋상각」의 초반 가중 비용 패턴이 되며, 정부기금에서는 시작 시점에 지출과 기타재원조달원천으로 표시합니다.

산례(가상의 교습 예시, 두 번 재계산): 연말 지급 100,000달러 × 5년, 할인율 3%이면 부채는 100,000 × 4.579707 = 457,971달러, 사용권자산도 같습니다. 1년 차 이자는 457,971 × 3% = 13,739달러, 원금은 86,261달러, 기말 부채는 371,710달러입니다. 정액 상각은 연 457,971 ÷ 5 = 91,594달러이고, 총지급액 500,000달러는 원금 457,971과 이자 합계 42,029로 닫힙니다.

**리스제공자.** 예상 수령액의 현재가치로 리스채권과 자원유입이연액을 인식하고 — ASC 842의 판매형 리스와 가장 선명하게 갈리는 점 — 기초자산을 제거하지 않습니다. 자산은 제공자 장부에 남아 계속 감가상각됩니다. 채권에서는 이자수익이 발생하고 유입이연액은 기간에 걸쳐 체계적으로 리스수익으로 전환됩니다. 단기리스, 소유권 이전, 투자 목적 보유 자산, 일부 규제 리스에는 예외가 있습니다. **기간·재평가·재측정:** 리스기간은 취소 불가 기간에 합리적으로 확실한 연장 기간을 더한 것이고, 명시된 사건이 있을 때만 재평가합니다. 기간 변경, 매수옵션 확실성 변경, 지수·요율 연동 지급액 변경, 잔존보증 예상액 변경이 재측정 트리거입니다. **캘리포니아:** 주 회계감사관실(State Controller's Office)이 전 주 실시 지침을 냈고, 가끔 인용되는 100,000달러는 주 부처 내부 자본화 기준일 뿐 GASB 87 자체의 하한이 아닙니다. 기준서에는 금액 하한이 없습니다. *개인 학습 노트이며 세무·회계 자문이 아닙니다. 초역으로 원어민 감수 대기 중입니다.*

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

**Thuê tài sản của chính phủ cho kỳ thi CPA: mô hình duy nhất của GASB 87, kế toán bên thuê và bên cho thuê, và quy tắc California.** Chuẩn mực GASB số 87, *Leases* (ban hành tháng 6 năm 2017), thay cách chia cũ thành thuê hoạt động và thuê vốn ở chính quyền bang và địa phương bằng một mô hình duy nhất, dựa trên một nguyên tắc: hợp đồng thuê là việc tài trợ cho quyền sử dụng tài sản gốc. Thuê là hợp đồng chuyển giao quyền kiểm soát việc sử dụng tài sản phi tài chính của một đơn vị khác trong một khoảng thời gian, trong giao dịch trao đổi hoặc tương tự trao đổi. Sau khi GASB 95 hoãn áp dụng, chuẩn mực hiệu lực cho các năm tài chính bắt đầu sau ngày 15 tháng 6 năm 2021; với các chính quyền California kết thúc năm vào 30 tháng 6, năm đầu tiên là năm tài chính kết thúc ngày 30 tháng 6 năm 2022.

**Phạm vi và các lối ra.** Thuê ngắn hạn — thời hạn tối đa có thể là 12 tháng trở xuống tại ngày khởi đầu, tính cả mọi quyền chọn gia hạn bất kể khả năng thực hiện — không được ghi nhận; các khoản trả được hạch toán chi phí khi phát sinh. Hợp đồng chuyển giao quyền sở hữu không phải là thuê: bên thuê hạch toán như mua hàng trả góp tài trợ (financed purchase), bên cho thuê hạch toán như bán hàng. Tài sản vô hình (kể cả các thỏa thuận IT dạng đăng ký sau này tách sang GASB 96), tài sản sinh học và hàng tồn kho nằm ngoài Chuẩn mực 87, cũng như thỏa thuận nhượng quyền dịch vụ (GASB 60) và hợp đồng cung ứng không đáp ứng định nghĩa thuê. Khác ASC 842, GASB 87 không giữ mô hình kép cho bên thuê.

**Bên thuê.** Tại ngày khởi đầu, bên thuê ghi nhận nợ thuê bằng giá trị hiện tại của các khoản dự kiến phải trả trong thời hạn thuê — khoản cố định và cố định về bản chất, khoản biến đổi theo chỉ số hoặc lãi suất đo tại ngày khởi đầu, giá thực hiện quyền chọn mua nếu việc thực hiện khá chắc chắn, phạt chấm dứt đã phản ánh trong thời hạn, và khoản dự kiến trả theo bảo đảm giá trị còn lại — chiết khấu bằng lãi suất bên cho thuê áp dụng nếu xác định được, nếu không thì lãi suất vay tăng thêm ước tính của bên thuê. Tài sản quyền sử dụng vô hình lấy nợ thuê làm mốc, cộng khoản đã trả tại hoặc trước ngày khởi đầu và chi phí trực tiếp ban đầu phụ trợ, trừ ưu đãi đã nhận. Sau đó nợ thuê tích lãi còn tài sản được khấu hao, thường theo thời hạn ngắn hơn giữa thời hạn thuê và thời gian hữu dụng, tạo mẫu chi phí «lãi cộng khấu hao» nặng ở đầu kỳ; trong các quỹ chính phủ, ngày khởi đầu được trình bày là một khoản chi và một nguồn tài trợ khác.

Ví dụ (giả định giảng dạy, đã tính lại hai lần): năm khoản trả cuối năm, mỗi khoản 100.000 đô la, lãi suất chiết khấu 3 %, cho nợ thuê 100.000 × 4,579707 = 457.971 đô la và tài sản quyền sử dụng tương đương. Lãi năm 1 là 457.971 × 3 % = 13.739; phần gốc là 86.261 và nợ cuối kỳ còn 371.710. Khấu hao đường thẳng là 457.971 ÷ 5 = 91.594 mỗi năm; tổng số trả 500.000 gồm gốc 457.971 và lãi tổng cộng 42.029.

**Bên cho thuê.** Bên cho thuê ghi nhận khoản phải thu thuê (giá trị hiện tại của các khoản dự kiến thu) và dòng vào hoãn lại (deferred inflow of resources), và — điểm khác biệt rõ nhất với thuê kiểu bán hàng của ASC 842 — **không** ghi giảm tài sản gốc; tài sản vẫn ở trên sổ của bên cho thuê và tiếp tục trích khấu hao. Lãi tích trên khoản phải thu, còn dòng vào hoãn lại được chuyển thành doanh thu thuê một cách hệ thống trong thời hạn. Có ngoại lệ cho thuê ngắn hạn, hợp đồng chuyển quyền sở hữu, tài sản giữ để đầu tư và một số thuê chịu quản lý đặc biệt. **Thời hạn và đo lại:** thời hạn thuê là giai đoạn không hủy ngang cộng các giai đoạn gia hạn khá chắc chắn; chỉ đánh giá lại khi xảy ra các sự kiện được liệt kê, và việc đo lại được kích hoạt khi thời hạn, mức chắc chắn của quyền chọn mua, khoản trả theo chỉ số hoặc lãi suất, hay khoản bảo đảm giá trị còn lại thay đổi. **California:** Văn phòng Kiểm soát viên bang (State Controller's Office) đã ban hành hướng dẫn triển khai toàn bang; con số 100.000 đô la đôi khi được trích dẫn chỉ là ngưỡng vốn hóa nội bộ của các cơ quan bang, không phải mức sàn của GASB 87 — chuẩn mực không đặt ngưỡng tiền nào. *Ghi chú học tập cá nhân, không phải tư vấn thuế hay kế toán. Bản dịch sơ bộ, chờ hiệu đính.*

## हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

**CPA परीक्षा के लिए सरकारी पट्टे: GASB 87 का एकल मॉडल, पट्टेदार व पट्टादाता लेखांकन और California नियम।** GASB कथन संख्या 87, *Leases* (जून 2017 में जारी), राज्य व स्थानीय सरकारों के लिए पुराने परिचालन/पूँजी पट्टा विभाजन को एकल मॉडल से बदलता है, जिसका आधार एक ही सिद्धांत है: पट्टा अंतर्निहित संपत्ति के उपयोग-अधिकार का वित्तपोषण (financing) है। पट्टा वह अनुबंध है जो विनिमय या विनिमय-सदृश लेनदेन में, एक अवधि के लिए किसी अन्य इकाई की ग़ैर-वित्तीय संपत्ति के उपयोग पर नियंत्रण का अधिकार देता है। GASB 95 के स्थगन के बाद यह मानक 15 जून 2021 के बाद शुरू होने वाले वित्तीय वर्षों पर लागू है; 30 जून को वर्ष समाप्त करने वाली California सरकारों के लिए पहला वर्ष 30 जून 2022 को समाप्त वित्तीय वर्ष था।

**दायरा और निकास।** अल्पकालिक पट्टा — प्रारंभ पर अधिकतम संभव अवधि, सभी विस्तार-विकल्पों सहित और उनके प्रयोग की संभावना निरपेक्ष, 12 महीने या कम — मान्यता नहीं पाता; भुगतान होते समय व्यय होते हैं। स्वामित्व हस्तांतरित करने वाला अनुबंध पट्टा है ही नहीं: पट्टेदार उसे वित्तपोषित खरीद (financed purchase) और पट्टादाता बिक्री मानता है। अमूर्त संपत्तियाँ (बाद में GASB 96 में गए सदस्यता-आधारित IT समझौतों सहित), जैविक संपत्तियाँ और माल-सूची कथन 87 से बाहर हैं; सेवा-रियायत समझौते (GASB 60) और पट्टा-परिभाषा पूरी न करने वाले आपूर्ति अनुबंध भी बाहर हैं। ASC 842 के विपरीत GASB 87 पट्टेदार के लिए दोहरा मॉडल नहीं रखता।

**पट्टेदार।** प्रारंभ पर पट्टेदार पट्टा-अवधि में अपेक्षित भुगतानों के वर्तमान मूल्य पर पट्टा-देयता मानता है — निश्चित व सारतः निश्चित भुगतान, प्रारंभ पर मापे सूचकांक/दर-आधारित परिवर्तनशील भुगतान, प्रयोग यथोचित निश्चित हो तो क्रय-विकल्प मूल्य, अवधि में परिलक्षित समाप्ति-दंड, और अवशिष्ट-गारंटी के अपेक्षित भुगतान — छूट-दर पट्टादाता द्वारा लगाई गई दर (यदि ज्ञात हो) या पट्टेदार की अनुमानित वृद्धिशील उधार-दर है। अमूर्त उपयोग-अधिकार संपत्ति देयता से शुरू होकर प्रारंभ पर या पहले किए गए भुगतान और संपत्ति को उपयोग-योग्य बनाने की सहायक प्रारंभिक प्रत्यक्ष लागत जोड़कर, प्राप्त प्रोत्साहन घटाकर बनती है। बाद में देयता पर ब्याज बढ़ता है और संपत्ति सामान्यतः पट्टा-अवधि व उपयोगी जीवन में से छोटी अवधि में परिशोधित होती है, जिससे «ब्याज जमा परिशोधन» वाला अग्र-भारित व्यय-स्वरूप बनता है; सरकारी निधियों में प्रारंभ को व्यय व अन्य वित्तपोषण स्रोत के रूप में दिखाया जाता है।

उदाहरण (काल्पनिक शिक्षण उदाहरण, दो बार पुनर्गणना): वर्ष-अंत में 100,000 डॉलर के पाँच वार्षिक भुगतान, 3 % छूट-दर पर, देयता 100,000 × 4.579707 = 457,971 डॉलर देते हैं और समान उपयोग-अधिकार संपत्ति भी। वर्ष 1 का ब्याज 457,971 × 3 % = 13,739 है; मूलधन 86,261 और अंतिम देयता 371,710 रहती है। सीधी-रेखा परिशोधन प्रति वर्ष 457,971 ÷ 5 = 91,594 है; कुल भुगतान 500,000 में मूलधन 457,971 और कुल ब्याज 42,029 बैठता है।

**पट्टादाता।** पट्टादाता पट्टा-प्राप्य (अपेक्षित प्राप्तियों का वर्तमान मूल्य) और संसाधनों का आस्थगित अंतर्वाह मानता है, और — ASC 842 के बिक्री-प्रकार पट्टे से सबसे तीखा अंतर — अंतर्निहित संपत्ति को बही से **नहीं** हटाता; संपत्ति पट्टादाता की बहियों में रहकर मूल्यह्रास पाती रहती है। प्राप्य पर ब्याज-आय बढ़ती है और आस्थगित अंतर्वाह अवधि में व्यवस्थित रूप से पट्टा-आय में छूटता है। अल्पकालिक पट्टों, स्वामित्व-हस्तांतरण अनुबंधों, निवेश हेतु रखी संपत्तियों और कुछ विनियमित पट्टों के अपवाद हैं। **अवधि व पुनर्मापन:** पट्टा-अवधि अ-रद्दीकरणीय अवधि जमा यथोचित निश्चित विस्तार-अवधि है; पुनर्मूल्यांकन केवल निर्दिष्ट घटनाओं पर होता है, और पुनर्मापन अवधि, क्रय-विकल्प निश्चितता, सूचकांक/दर-आधारित भुगतान या अवशिष्ट-गारंटी राशियों में बदलाव से शुरू होता है। **California:** राज्य नियंत्रक कार्यालय (State Controller's Office) ने राज्यव्यापी कार्यान्वयन मार्गदर्शन जारी किया; कभी-कभी उद्धृत 100,000 डॉलर की राशि राज्य-विभागों का आंतरिक पूँजीकरण-सीमा है, GASB 87 की कोई न्यूनतम राशि नहीं — मानक कोई डॉलर-सीमा नहीं रखता। *व्यक्तिगत अध्ययन नोट; कर या लेखा सलाह नहीं। प्रारंभिक अनुवाद, समीक्षा लंबित।*

---
*个人学习笔记，不构成税务建议。*
