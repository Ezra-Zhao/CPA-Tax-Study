# 作业成本法备考核心：ABC 与时间驱动 TDABC 及批次层级

> 板块：CPA备考（BAR 商业分析与报告）· 成本会计高频区。本篇所有算例均已本地复算勾稽。

## 中文

### 一、先说清病灶：传统量基分配为什么会扭曲成本

传统成本法把全部制造费用拢成一个池，用单一量基（直接人工小时或机器小时）按产量比例摊给产品。它的隐含假设是：所有间接成本都随产量同比例发生。这个假设在单一产品、低间接费时代勉强成立，在多品种、小批量、间接费占比高的现代工厂里系统性失真：

- 高产量、工艺简单的产品分到的费用被**高估**——因为量基大就摊得多，可它实际消耗的换模、检验、调度资源并不多；
- 低产量、工艺复杂的产品被**低估**——批量小、换模频、检验多，真正吃资源的恰恰是它，量基却摊不到它头上。

后果不是账面小误差，而是定价与产品组合决策被带偏：以为赚钱的产品在补贴以为亏钱的产品。作业成本法（activity-based costing, ABC）由 Cooper 与 Kaplan 等人在 1980 年代末系统提出，要解决的就是这个扭曲；其在 CPA 考试中的落点，是 BAR 的成本计量与绩效主题。

### 二、ABC 的骨架：两阶段分配

ABC 把「资源 → 产品」的直达分配拆成两段：

1. **第一阶段：资源 → 作业。** 先按资源动因（resource driver）把资源成本（人工、设备、场地、能源等）归集到各个作业（activity），形成作业成本池，如「设备调整（setup）」「加工作业支持」「质量检验」「订单处理」。
2. **第二阶段：作业 → 成本对象。** 再按作业动因（activity driver / cost driver）把每个作业池的成本分给产品、订单、客户等成本对象：调整池按调整次数、检验池按检验次数、加工支持池按机器小时。

关键在第二阶段的费率：作业成本率 ＝ 作业池成本 ÷ 动因总量；某产品分得的作业成本 ＝ 作业成本率 × 该产品消耗的动因量。动因选得对不对，决定 ABC 是照妖镜还是新一轮平均主义。

### 三、作业层级四分：ABC 的世界观

选动因之前，先按「成本随什么动」给作业分层（Cooper 的成本层级，cost hierarchy）：

| 层级 | 随什么动 | 典型作业 | 分配基础 |
|---|---|---|---|
| 单位级（unit-level） | 每生产一件就发生 | 加工用电、计件加工支持 | 产量、机器小时 |
| 批次级（batch-level） | 每生产一批就发生，与批内件数无关 | 设备调整、首件检验、批量物料搬运 | 调整次数、批次数 |
| 产品维持级（product-sustaining） | 为某个产品存在而发生，与产量批次无关 | 产品工程图纸维护、专用工装管理 | 产品种类数（难以按量分摊，常按产品线归集） |
| 设施维持级（facility-sustaining） | 为整个工厂存在而发生 | 厂房折旧、厂长薪酬、厂区安保 | **不强行分摊** |

设施维持级是层级表里最重要的一行：它与任何单个产品之间都找不到因果链。备考口径与实务共识一致——为求「完全成本」把设施级成本硬按面积或产量摊下去，摊的不是成本而是任意性，产品成本随之再度失真；正确处理是留在产品成本之外、在分部或工厂层面单列评价。产品维持级同理须谨慎：它可以归集到产品线，但摊到单个产品单位成本时要标明其非增量性质，否则停产决策会误以为这笔成本能随停产消失。

### 四、贯穿算例：同一笔 900,000 美元，两种摊法

某工厂年制造费用 900,000 美元，两种产品：A 为大批量简单产品（年产 10,000 件），B 为小批量复杂产品（年产 2,000 件）。

**传统量基法：** 全厂单一费率，按直接人工小时分配。A、B 合计人工小时 30,000，费率 ＝ 900,000 ÷ 30,000 ＝ 30 美元/小时。A 用 20,000 小时 → 600,000 美元，单位制造费用 60 美元；B 用 10,000 小时 → 300,000 美元，单位 150 美元。

**ABC 法：** 先分三池，再按动因分：

| 作业池 | 池成本 | 动因 | 动因总量 | 作业成本率 | A 消耗 | A 分得 | B 消耗 | B 分得 |
|---|---|---|---|---|---|---|---|---|
| 设备调整（批次级） | 360,000 | 调整次数 | 180 次 | 2,000/次 | 40 次 | 80,000 | 140 次 | 280,000 |
| 加工支持（单位级） | 360,000 | 机器小时 | 60,000 小时 | 6/小时 | 45,000 小时 | 270,000 | 15,000 小时 | 90,000 |
| 质量检验（批次级） | 180,000 | 检验次数 | 900 次 | 200/次 | 300 次 | 60,000 | 600 次 | 120,000 |
| **合计** | **900,000** | | | | | **410,000** | | **490,000** |

勾稽：80,000 ＋ 270,000 ＋ 60,000 ＝ 410,000（A）；280,000 ＋ 90,000 ＋ 120,000 ＝ 490,000（B）；410,000 ＋ 490,000 ＝ 900,000 ＝ 制造费用总额，分毫不差。单位制造费用：A ＝ 410,000 ÷ 10,000 ＝ 41 美元（传统法 60 美元，高估 19 美元）；B ＝ 490,000 ÷ 2,000 ＝ 245 美元（传统法 150 美元，低估 95 美元）。

读这组数的方法：扭曲全部来自批次级——B 只占产量六分之一，却吃掉 180 次调整中的 140 次、900 次检验中的 600 次。量基法看不见批次，只看得见产量，于是把 B 的批次成本大半塞给了 A。这正是「交叉补贴」的标准考图。

### 五、成本动因选择：三条判准

1. **因果优先**：动因与作业成本之间要有可解释的因果关系（调整次数驱动调整成本），相关性高但无因果的动因（如按销售额摊检验费）只能算分摊，不能算 ABC。
2. **可计量且行为可预期**：动因数据要能低成本取得；且动因一旦被用作考核口径，员工会朝动因方向优化行为——选错动因等于发错奖金。
3. **粗细适度**：作业池太细，维护成本爆炸、数据噪声大；太粗，又退回平均主义。考试常考的判断是批次级作业绝不能用单位级动因（如产量）去摊。

### 六、TDABC：用时间方程替代逐项访谈

传统 ABC 落地贵在维护：每次流程变化都要重新访谈、重新估每个作业的消耗比例。Kaplan 与 Anderson 提出的时间驱动作业成本法（time-driven ABC, TDABC）只保留两个参数：

1. **产能成本率（capacity cost rate）** ＝ 部门资源成本 ÷ 实际产能（practical capacity，通常取理论产能的约 80%–85%，扣除休息、维护、培训等必然闲置）；
2. **单位时间（unit time）**：每类交易在每个作业上消耗的时间，用**时间方程（time equation）**把流程差异写成算式，如「订单处理时间 ＝ 15 分钟 ＋ 2 分钟 × 订单行数 ＋ 加急时另加 10 分钟」，一个方程吃下全部变体，不必为每种情形单设作业池。

**教学算例（本地复算勾稽）：** 某订单处理部门年资源成本 560,000 美元，理论产能 800,000 分钟，实际产能按 87.5% 取 700,000 分钟。产能成本率 ＝ 560,000 ÷ 700,000 ＝ 0.80 美元/分钟。一张 5 行的标准订单耗时 ＝ 15 ＋ 2 × 5 ＝ 25 分钟，成本 ＝ 25 × 0.80 ＝ 20.00 美元；一张 3 行的加急订单耗时 ＝ 15 ＋ 2 × 3 ＋ 10 ＝ 31 分钟，成本 ＝ 31 × 0.80 ＝ 24.80 美元。全年实际消耗 560,000 分钟 → 已分配成本 ＝ 560,000 × 0.80 ＝ 448,000 美元；未用产能 ＝ 700,000 − 560,000 ＝ 140,000 分钟 → 112,000 美元**单独报告、不塞进产品成本**；448,000 ＋ 112,000 ＝ 560,000 ＝ 部门资源成本总额，勾稽闭合。

TDABC 相对传统 ABC 的考点优势有三：参数更新便宜（改时间估计即可）；时间方程天然处理交易异质性；未用产能的成本被单独揭示而不是摊进产品，管理层能直接看见闲置的代价。

### 七、与 ASC 330 的边界：管理会计的数不能直接搬进存货

ABC 与 TDABC 是管理会计工具，算出的「产品成本」不等于财务报告口径的存货成本，两条边界要守住：

1. **吸收边界**：ASC 330《存货》要求存货成本包含基于**正常产能（normal capacity）**分配的固定制造费用；未分配的固定费用（闲置产能部分）在发生当期计入费用。ASC 330-10-30 一带明确：异常闲置设施费用、异常货运与装卸、异常损耗属于当期费用，不得计入存货成本。这与 TDABC「未用产能单列」的处理方向一致，但口径锚点是正常产能而非 TDABC 的实际产能，答题勿混。
2. **费用性质边界**：销售、管理类作业成本（如订单获取、售后）在 ASC 框架下是期间费用，无论 ABC 如何把它们分到客户或产品，都不能借道存货资本化。

加州口径一句：加州无州级成本会计变通规则，企业所得税与特许税的存货与成本口径大体跟随联邦，细节以 FTB 当期指引为准。

### 八、易错点收束

1. 批次级成本用产量摊——层级错位，是 ABC 题的第一陷阱。
2. 设施维持级硬摊进单位成本——摊出的是任意数，不是成本。
3. TDABC 的分母是实际产能不是理论产能，更不是实际用量；用实际用量做分母会把闲置成本又摊回产品，TDABC 就白做了。
4. 未用产能成本在 TDABC 里单列报告、在 ASC 330 里当期费用化，两个口径方向同、锚点异（实际产能 vs 正常产能）。
5. ABC 改变的是成本的**归属**，不是成本总额：两种方法合计同为 900,000 美元，对不上的合计先查算术。

> 声明：个人学习笔记，不构成税务、会计或财务建议。来源：Cooper, R. & Kaplan, R. S., "Measure Costs Right: Make the Right Decisions," Harvard Business Review (1988) 及二人后续成本层级论述；Kaplan, R. S. & Anderson, S. R., Time-Driven Activity-Based Costing (2007)；FASB ASC 330-10-30（存货成本与异常闲置费用）；AICPA CPA Exam Blueprints（BAR）成本计量口径。加州细节以 FTB 当期指引为准。

## English

Traditional volume-based allocation distorts product cost because it assumes all overhead varies with output: high-volume simple products are overcosted and low-volume complex products undercosted, so pricing and mix decisions inherit the error. Activity-based costing (Cooper and Kaplan) fixes this in two stages — resources to activities via resource drivers, then activities to cost objects via activity drivers — and its worldview is the four-level cost hierarchy: unit-level (varies with each unit), batch-level (varies with each batch, regardless of batch size), product-sustaining (exists because a product exists), and facility-sustaining, which has no causal link to any single product and must not be force-allocated. In the worked example, $900,000 of overhead is split three ways: setups $360,000 over 180 setups ($2,000 each; A uses 40, B uses 140), machining support $360,000 over 60,000 machine hours ($6; A 45,000, B 15,000), and inspection $180,000 over 900 inspections ($200; A 300, B 600). ABC assigns A $410,000 ($41/unit) and B $490,000 ($245/unit), totaling exactly $900,000, versus the volume-based $600,000/$60 and $300,000/$150 — the distortion lives entirely in the batch-level pools. Time-driven ABC (Kaplan and Anderson) replaces interview-based ABC with two parameters: a capacity cost rate (department cost ÷ practical capacity, roughly 80–85% of theoretical) and time equations. Example: a $560,000 department with 700,000 practical minutes (87.5% of 800,000 theoretical) has a rate of $0.80/minute; an order takes 15 + 2 × line items minutes, plus 10 if rushed, so a standard 5-line order costs 25 × $0.80 = $20.00 and a rushed 3-line order 31 × $0.80 = $24.80; 560,000 minutes actually used absorb $448,000, and the 140,000 unused minutes ($112,000) are reported separately — $448,000 + $112,000 = $560,000. Boundary with financial reporting: ASC 330 allocates fixed overhead on normal capacity and expenses abnormal idle-facility amounts in the period (ASC 330-10-30), so managerial ABC/TDABC figures do not flow into inventory mechanically; California has no state cost-accounting variant and broadly follows the federal treatment, subject to current FTB guidance.

*Personal study notes only; not tax, accounting, or financial advice.*

## Español (traducción de estudio · 初译待校)

La asignación tradicional por volumen distorsiona el costo porque supone que todo el gasto indirecto varía con la producción: sobrecostea los productos simples de alto volumen y subcostea los complejos de bajo volumen. El costeo por actividades (ABC, Cooper y Kaplan) lo corrige en dos etapas — recursos a actividades y actividades a objetos de costo — con una jerarquía de cuatro niveles: nivel unitario, nivel de lote (varía con cada lote, no con su tamaño), nivel de sostenimiento del producto y nivel de sostenimiento de la planta, este último sin vínculo causal con ningún producto, por lo que no debe repartirse a la fuerza. En el ejemplo, 900.000 dólares se dividen en tres fondos: preparación 360.000 entre 180 preparaciones (2.000 cada una; A usa 40 y B, 140), apoyo de mecanizado 360.000 entre 60.000 horas-máquina (6 por hora; A 45.000, B 15.000) e inspección 180.000 entre 900 inspecciones (200 cada una; A 300, B 600). ABC asigna a A 410.000 dólares (41 por unidad) y a B 490.000 (245 por unidad), con un total exacto de 900.000, frente a 600.000/60 y 300.000/150 del método por volumen: la distorsión vive en los fondos de nivel de lote. El ABC impulsado por el tiempo (TDABC, Kaplan y Anderson) usa solo dos parámetros: la tasa de costo de capacidad (costo del departamento ÷ capacidad práctica, en torno al 80–85 % de la teórica) y ecuaciones de tiempo. Ejemplo: un departamento de 560.000 dólares con 700.000 minutos prácticos (87,5 % de 800.000 teóricos) tiene una tasa de 0,80 dólares por minuto; un pedido toma 15 + 2 × líneas minutos, más 10 si es urgente, de modo que un pedido estándar de 5 líneas cuesta 25 × 0,80 = 20,00 y uno urgente de 3 líneas 31 × 0,80 = 24,80; los 560.000 minutos usados absorben 448.000 y los 140.000 minutos ociosos (112.000) se informan por separado: 448.000 + 112.000 = 560.000. Frontera con la información financiera: ASC 330 reparte los gastos fijos según la capacidad normal y lleva a gasto del período los importes anómalos por capacidad ociosa (ASC 330-10-30); California no tiene variante estatal de contabilidad de costos y sigue en lo sustancial el tratamiento federal, según la guía vigente de la FTB.

*Notas personales de estudio; no constituye asesoría fiscal, contable ni financiera. Traducción de estudio, pendiente de revisión.*

## 한국어 (초역 · 初译待校)

전통적인 물량 기준 배부는 모든 간접비가 산출량에 비례한다는 가정 때문에 원가를 왜곡합니다. 대량·단순 제품은 과대계상되고 소량·복잡 제품은 과소계상됩니다. 활동기준원가계산(ABC, Cooper와 Kaplan)은 자원 → 활동 → 원가대상의 2단계 배부와 네 층의 원가계층으로 이를 고칩니다: 단위 수준, 배치 수준(배치 내 수량과 무관하게 배치마다 발생), 제품유지 수준, 시설유지 수준. 시설유지 수준은 어떤 단일 제품과도 인과관계가 없어 억지로 배부해서는 안 됩니다. 예시에서 제조간접비 900,000달러는 세 풀로 나뉩니다: 준비 360,000달러를 준비 180회로 나누면 회당 2,000달러(A 40회, B 140회), 가공지원 360,000달러를 기계시간 60,000시간으로 나누면 시간당 6달러(A 45,000, B 15,000), 검사 180,000달러를 검사 900회로 나누면 회당 200달러(A 300회, B 600회). ABC 결과 A는 410,000달러(단위당 41달러), B는 490,000달러(단위당 245달러)로 합계가 정확히 900,000달러이며, 물량 기준의 600,000/60달러, 300,000/150달러와 대비됩니다. 왜곡은 전부 배치 수준 풀에 있습니다. 시간구동 ABC(TDABC, Kaplan과 Anderson)는 두 매개변수만 씁니다: 설비가동률 원가율(부서 원가 ÷ 실제조업도, 통상 이론조업도의 80–85%)과 시간방정식. 예시: 원가 560,000달러, 실제조업도 700,000분(이론 800,000분의 87.5%)이면 분당 0.80달러, 주문 처리시간은 15 + 2 × 주문행 수 분(긴급 시 +10분)이라 5행 표준 주문은 25 × 0.80 = 20.00달러, 3행 긴급 주문은 31 × 0.80 = 24.80달러입니다. 실제 사용 560,000분은 448,000달러를 흡수하고 미사용 140,000분(112,000달러)은 별도 보고합니다: 448,000 + 112,000 = 560,000. 재무보고와의 경계: ASC 330은 고정제조간접비를 정상조업도로 배부하고 비정상 유휴비용은 당기 비용 처리합니다(ASC 330-10-30). 캘리포니아에는 주 차원의 원가회계 변형이 없고 대체로 연방 방식을 따르며, 세부 사항은 FTB의 현행 지침을 따릅니다.

*개인 학습 노트이며 세무·회계·재무 자문이 아닙니다. 초역으로 교정 대기 중입니다.*

## Tiếng Việt (bản dịch sơ bộ · 初译待校)

Phương pháp phân bổ truyền thống theo sản lượng làm méo mó chi phí vì giả định mọi chi phí gián tiếp biến thiên theo sản lượng: sản phẩm đơn giản sản lượng cao bị tính thừa, sản phẩm phức tạp sản lượng thấp bị tính thiếu. ABC (Cooper và Kaplan) sửa điều này bằng phân bổ hai giai đoạn — nguồn lực sang hoạt động, hoạt động sang đối tượng chi phí — cùng hệ thống phân cấp bốn tầng: cấp đơn vị, cấp lô (phát sinh theo mỗi lô, bất kể lô lớn hay nhỏ), cấp duy trì sản phẩm và cấp duy trì cơ sở; cấp cơ sở không có quan hệ nhân quả với bất kỳ sản phẩm đơn lẻ nào nên không được cưỡng ép phân bổ. Trong ví dụ, 900.000 đô la chi phí được chia ba quỹ: chuẩn bị máy 360.000 trên 180 lần chuẩn bị (2.000 mỗi lần; A dùng 40, B dùng 140), hỗ trợ gia công 360.000 trên 60.000 giờ máy (6 đô la/giờ; A 45.000, B 15.000), kiểm tra 180.000 trên 900 lần kiểm tra (200 mỗi lần; A 300, B 600). ABC phân cho A 410.000 đô la (41 đô la/đơn vị) và B 490.000 (245 đô la/đơn vị), tổng đúng 900.000, so với phương pháp sản lượng là 600.000/60 và 300.000/150 — méo mó nằm hoàn toàn ở các quỹ cấp lô. TDABC (Kaplan và Anderson) chỉ dùng hai tham số: tỉ lệ chi phí năng lực (chi phí bộ phận ÷ năng lực thực tế, khoảng 80–85% năng lực lý thuyết) và phương trình thời gian. Ví dụ: bộ phận 560.000 đô la với 700.000 phút thực tế (87,5% của 800.000 phút lý thuyết) có tỉ lệ 0,80 đô la/phút; một đơn hàng tốn 15 + 2 × số dòng phút, cộng 10 nếu gấp, nên đơn tiêu chuẩn 5 dòng tốn 25 × 0,80 = 20,00 đô la và đơn gấp 3 dòng tốn 31 × 0,80 = 24,80 đô la; 560.000 phút đã dùng hấp thụ 448.000 đô la, còn 140.000 phút nhàn rỗi (112.000 đô la) được báo cáo riêng: 448.000 + 112.000 = 560.000. Ranh giới với báo cáo tài chính: ASC 330 phân bổ chi phí cố định theo năng lực bình thường và ghi chi phí nhàn rỗi bất thường vào chi phí kỳ (ASC 330-10-30); California không có biến thể kế toán chi phí cấp bang và về cơ bản theo cách xử lý liên bang, chi tiết theo hướng dẫn hiện hành của FTB.

*Ghi chú học tập cá nhân, không phải tư vấn thuế, kế toán hay tài chính. Bản dịch sơ bộ, chờ hiệu đính.*

## हिन्दी (प्रारंभिक अनुवाद · 初译待校)

पारंपरिक मात्रा-आधारित आवंटन लागत को इसलिए बिगाड़ता है क्योंकि वह मानता है कि सारी उपरिव्यय लागत उत्पादन के अनुपात में बदलती है: अधिक मात्रा वाले सरल उत्पादों की लागत बढ़ाकर और कम मात्रा वाले जटिल उत्पादों की लागत घटाकर दिखाई जाती है। गतिविधि-आधारित लागत (ABC, Cooper व Kaplan) इसे दो चरणों में सुधारती है — संसाधन से गतिविधियों तक, फिर गतिविधियों से लागत-वस्तुओं तक — और चार-स्तरीय लागत पदानुक्रम देती है: इकाई स्तर, बैच स्तर (हर बैच पर होता है, बैच के आकार से स्वतंत्र), उत्पाद-पोषण स्तर और सुविधा-पोषण स्तर; सुविधा स्तर का किसी एक उत्पाद से कोई कारणात्मक संबंध नहीं, इसलिए उसे ज़बरदस्ती नहीं बाँटना चाहिए। उदाहरण में 900,000 डॉलर तीन पूलों में बँटते हैं: सेटअप 360,000 ÷ 180 सेटअप = 2,000 प्रति सेटअप (A 40, B 140), मशीनिंग सहायता 360,000 ÷ 60,000 मशीन-घंटे = 6 प्रति घंटा (A 45,000, B 15,000), निरीक्षण 180,000 ÷ 900 निरीक्षण = 200 प्रति निरीक्षण (A 300, B 600)। ABC से A को 410,000 डॉलर (41 प्रति इकाई) और B को 490,000 (245 प्रति इकाई) मिलते हैं, कुल ठीक 900,000 — मात्रा-पद्धति के 600,000/60 व 300,000/150 के मुकाबले; सारी विकृति बैच-स्तरीय पूलों में है। समय-चालित ABC (TDABC, Kaplan व Anderson) केवल दो मापदंड उपयोग करती है: क्षमता लागत दर (विभाग लागत ÷ व्यावहारिक क्षमता, सामान्यतः सैद्धांतिक क्षमता का 80–85%) और समय समीकरण। उदाहरण: 560,000 डॉलर का विभाग, 700,000 व्यावहारिक मिनट (सैद्धांतिक 800,000 का 87.5%) → दर 0.80 डॉलर/मिनट; एक ऑर्डर में 15 + 2 × लाइनें मिनट लगते हैं, जल्दबाज़ी पर +10, अतः 5-लाइन मानक ऑर्डर 25 × 0.80 = 20.00 डॉलर और 3-लाइन तत्काल ऑर्डर 31 × 0.80 = 24.80 डॉलर; उपयोग हुए 560,000 मिनट 448,000 डॉलर सोखते हैं और अप्रयुक्त 140,000 मिनट (112,000 डॉलर) अलग से रिपोर्ट होते हैं: 448,000 + 112,000 = 560,000। वित्तीय रिपोर्टिंग से सीमा: ASC 330 स्थिर उपरिव्यय को सामान्य क्षमता पर बाँटता है और असामान्य निष्क्रिय-क्षमता राशियाँ उसी अवधि में व्यय करता है (ASC 330-10-30); कैलिफ़ोर्निया में राज्य-स्तरीय लागत-लेखांकन भिन्नता नहीं है और वह मोटे तौर पर संघीय उपचार का पालन करता है, विवरण FTB के वर्तमान मार्गदर्शन के अनुसार।

*व्यक्तिगत अध्ययन नोट्स; कर, लेखांकन या वित्तीय सलाह नहीं। प्रारंभिक अनुवाद, समीक्षा लंबित।*
