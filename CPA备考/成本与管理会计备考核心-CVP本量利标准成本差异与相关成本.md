# 成本与管理会计备考核心：CVP 本量利、标准成本差异与相关成本

> 板块：CPA备考（BAR 商业分析与报告）· 管理会计是 BAR 的高频计算区：先用边际贡献把 CVP 的量、价、利拴在一根绳上，再用标准成本差异把「价」与「量」拆开追责，最后用相关成本守住决策边界——只看未来、只看差量。本篇所有算例均已复算。

## 中文

### 一、先立地基：成本性态与边际贡献

CVP（cost-volume-profit，本量利）分析的全部公式，都从一个划分开始：把成本按性态拆成变动成本与固定成本。变动成本总额随业务量同比例变，单位变动成本不变；固定成本在相关范围（relevant range）内总额不变，单位固定成本随量摊薄。卖出一件产品，先扣掉它自己带来的变动成本，剩下的才有资格去覆盖固定成本、再变成利润，这个剩余就是边际贡献（contribution margin）：

- 单位边际贡献 ＝ 售价 － 单位变动成本
- 边际贡献率 ＝ 单位边际贡献 ÷ 售价
- 利润 ＝ 销量 × 单位边际贡献 － 固定成本总额

考试里最常见的第一步错误，是把期间费用、固定制造费用混进单位变动成本。口径要先定死：变动成本指随每多卖一件就多发生一件的成本（直接材料、直接人工中的计件部分、变动制造费用、销售佣金等）；固定成本是产能与期间成本，不进单位边际贡献，只在公式最后整笔扣掉。

### 二、盈亏平衡与目标利润：一道贯穿算例

设某产品售价 $50／件，单位变动成本 $30／件，固定成本总额 $100,000。逐步算：

1. 单位边际贡献 ＝ 50 － 30 ＝ $20／件；边际贡献率 ＝ 20 ÷ 50 ＝ 40%。
2. 盈亏平衡量 ＝ 固定成本 ÷ 单位边际贡献 ＝ 100,000 ÷ 20 ＝ 5,000 件。验算：5,000 件 × $20 ＝ $100,000，正好盖住固定成本，利润为零。换成金额口径：盈亏平衡销售额 ＝ 100,000 ÷ 40% ＝ $250,000 ＝ 5,000 件 × $50，两条路互洽。
3. 目标利润 $40,000 所需销量 ＝（固定成本 ＋ 目标利润）÷ 单位边际贡献 ＝（100,000 ＋ 40,000）÷ 20 ＝ 7,000 件。验算：7,000 × 20 － 100,000 ＝ 140,000 － 100,000 ＝ $40,000，分毫不差；目标销售额 ＝ 140,000 ÷ 40% ＝ $350,000 ＝ 7,000 × $50。

由这道例还能顺手读出两个常考指标：若实际（或预计）销量就是 7,000 件，安全边际（margin of safety）＝ 7,000 － 5,000 ＝ 2,000 件，安全边际率 ＝ 2,000 ÷ 7,000 ≈ 28.6%，意思是销量跌近三成才触及亏损线。经营杠杆（degree of operating leverage）＝ 边际贡献总额 ÷ 利润 ＝ 140,000 ÷ 40,000 ＝ 3.5 倍，销量每变 1%，利润约变 3.5%——固定成本越重，平衡点越高、杠杆越大，这正是 CVP 假设题爱埋的因果链。多产品情形再加一步：先按销售组合（sales mix）算加权平均单位边际贡献，再套同一公式，组合一变平衡点就变，这是多产品题唯一的机关。

### 三、标准成本差异：把总差异拆成「价」与「量」

标准成本法先给每件产品定好应该用的量（标准用量 SQ）与应该付的价（标准价格 SP），期末再拿实际价格 AP、实际用量 AQ 对照。总差异拆两刀，公式全线同构：

- 材料价格差异 ＝ AQ ×（AP － SP）
- 材料用量差异 ＝ SP ×（AQ － SQ）
- 人工工资率差异 ＝ AH ×（AR － SR）
- 人工效率差异 ＝ SR ×（AH － SH）

记忆法只有一条：价格类差异乘实际量，数量类差异乘标准价——这样拆完两刀之和恰好等于总差异，不重不漏。符号口径：实际大于标准为不利差异（U, unfavorable），反之为有利差异（F, favorable）。

算例（材料）：标准价 $5／公斤，实际价 $5.50／公斤，实际耗用 10,500 公斤，标准耗用量（实际产量对应的应耗量）10,000 公斤。价格差异 ＝ 10,500 ×（5.50 － 5.00）＝ 10,500 × 0.50 ＝ $5,250 U；用量差异 ＝ 5 ×（10,500 － 10,000）＝ 5 × 500 ＝ $2,500 U；合计 $7,750 U。勾稽：实际成本 10,500 × 5.50 ＝ $57,750，标准成本 10,000 × 5 ＝ $50,000，差 $7,750，分毫不差。算例（人工）：标准工资率 $20／小时，实际 $21／小时，实际工时 4,200 小时，标准工时 4,000 小时。工资率差异 ＝ 4,200 ×（21 － 20）＝ $4,200 U；效率差异 ＝ 20 ×（4,200 － 4,000）＝ $4,000 U；合计 $8,200 U。勾稽：实际 4,200 × 21 ＝ $88,200，标准 4,000 × 20 ＝ $80,000，差 $8,200。两点提醒：其一，价格差异的 AQ 在实务与不少考题中按采购量计（买入时即确认价格差异），本例为简明按耗用量计，公式结构不变、换量即可；其二，责任归属跟着拆分走——价格差异多归采购，用量与效率差异多归生产，但赶工用熟练工造成工资率高、效率好这类交叉情形，要合并看，不能机械追责。
### 四、相关成本：决策只看未来差量

短期决策（自制还是外购、停不停产一条线、接不接特别订单、约束资源下先产什么）只认相关成本（relevant cost），判别标准两条同时成立：发生在未来，且在备选方案之间有差异。不合这两条的一律剔除：

- 沉没成本（sunk cost）不相关：已经花掉、收不回来的钱（如已购设备的原价、已发生的研发费），无论选哪个方案都改变不了，进决策表就是干扰项——这是选择题里出现率最高的陷阱。
- 已承诺的固定成本多半不相关：两个方案下都要付的厂房租金、直线法折旧（多为沉没成本的分摊）不影响选择；只有可避免固定成本（avoidable fixed cost，如停掉产品线能省下的专属设备租费、线长工资）才相关。
- 机会成本（opportunity cost）相关且常被漏算：自制占用产能意味着放弃外租收入或另一产品的边际贡献，这笔账面看不见的放弃收益，必须计入自制方案的成本一侧。
- 特别订单的底线：有闲置产能时，只要订单价高于增量成本（incremental cost，基本就是单位变动成本加订单专属增量固定成本），接单就增利，原有固定成本不摊进来；产能已满时，则还要加上被挤掉产品的边际贡献作机会成本，底线随之抬高。
- 约束资源排序：当瓶颈是机器小时或稀缺材料时，比较的不是单位边际贡献，而是单位约束资源的边际贡献（contribution margin per unit of the constrained resource），高者优先排产。

### 五、平衡计分卡：从算利润到看战略

CVP 与差异分析盯的是财务结果，平衡计分卡（balanced scorecard, BSC）由 Kaplan 与 Norton 提出，把视野补全为四个维度，并用因果链串起来：学习与成长（员工能力、系统、文化）驱动内部流程（质量、周期、成本）改善，流程改善带来客户维度成果（满意度、留存、市场份额），最终兑现为财务维度成果（利润、收入增长、资产回报）。四维各记两类指标：结果性的滞后指标（lag indicators，如已实现的利润、客户留存率）与驱动性的领先指标（lead indicators，如培训时长、一次合格率、新产品收入占比）。备考抓三点：其一，四维的名称与顺序（财务、客户、内部流程、学习与成长）要背准；其二，BSC 在 BAR 里与战略地图（strategy map）、关键绩效指标（KPI）及 COSO 风险管理的话题同组出现，命题常把「某指标属于哪个维度」与「领先还是滞后」打包考；其三，它和前三节不是两张皮——标准成本差异就是内部流程维度的典型领先指标失守后的财务显形，CVP 的边际贡献则是财务维度定目标、自上而下拆到流程与产能的工具。

### 六、易错点收束

1. 盈亏平衡公式的分子只有固定成本，分母用单位边际贡献（算量）或边际贡献率（算额），不要把目标利润漏加或重复加。
2. 差异符号先算后判：统一用（实际－标准）的方向定 U／F，再写结论，别凭感觉标。
3. 价格差异乘 AQ、数量差异乘标准价——乘反了两刀之和就对不上总差异，勾稽一步就能自查。
4. 决策表里出现账面折旧、已付租金、历史采购价，先问一句「换个方案它变不变」，不变就划掉。
5. 平衡计分卡别把客户指标塞进内部流程：满意度与留存是客户维度，合格率与交付周期才是流程维度。

> 个人学习笔记，不构成税务、财务或法律建议。公式与板块口径以 AICPA 现行 CPA Exam Blueprints（BAR）为准。

## English

Cost-volume-profit analysis starts from one identity: unit contribution margin = price − unit variable cost, and profit = units × unit CM − total fixed costs. Worked example: price $50, unit variable cost $30, fixed costs $100,000. Unit CM = $20; CM ratio = 40%. Breakeven units = 100,000 ÷ 20 = 5,000 units (check: 5,000 × $20 = $100,000); breakeven sales = 100,000 ÷ 40% = $250,000. Units needed for a $40,000 target profit = (100,000 + 40,000) ÷ 20 = 7,000 units (check: 7,000 × 20 − 100,000 = $40,000); target sales = $350,000. At 7,000 units the margin of safety is 2,000 units, about 28.6%, and the degree of operating leverage is 140,000 ÷ 40,000 = 3.5×. For multiple products, use the weighted-average CM of the sales mix first. Standard-cost variances split every total variance into a price piece (actual quantity × price difference) and a quantity piece (standard price × quantity difference): materials price variance = AQ × (AP − SP), materials usage variance = SP × (AQ − SQ), with labor rate and efficiency variances built identically from AH, AR, SR, SH. Materials example: AP $5.50, SP $5.00, AQ 10,500 kg, SQ 10,000 kg → price variance $5,250 U, usage variance $2,500 U, total $7,750 U, which ties to actual cost $57,750 versus standard $50,000. Labor example: AR $21, SR $20, AH 4,200, SH 4,000 → rate variance $4,200 U, efficiency variance $4,000 U, total $8,200 U, tying to $88,200 versus $80,000. Relevant costing for short-term decisions counts only future costs that differ among alternatives: sunk costs are never relevant, unavoidable fixed costs are excluded, avoidable fixed costs and opportunity costs are included; with idle capacity a special order is profitable above its incremental cost, and under a bottleneck, rank products by CM per unit of the constrained resource. The balanced scorecard (Kaplan and Norton) links four perspectives by cause and effect — learning and growth → internal processes → customer → financial — mixing lag indicators with lead indicators; in the BAR section of the CPA exam it is tested together with strategy maps and KPIs, and variance analysis is best read as a process-perspective signal surfacing in financial results.

*Personal study notes only; not tax, financial, or legal advice.*

## Español (译稿 · 初译待校)

El análisis costo-volumen-utilidad parte de una identidad: margen de contribución unitario = precio − costo variable unitario, y utilidad = unidades × margen − costos fijos totales. Ejemplo: precio $50, costo variable unitario $30, costos fijos $100,000. Margen unitario = $20; razón de contribución = 40 %. Punto de equilibrio = 100.000 ÷ 20 = 5.000 unidades (comprobación: 5.000 × $20 = $100.000); ventas de equilibrio = $250.000. Para una utilidad objetivo de $40.000: (100.000 + 40.000) ÷ 20 = 7.000 unidades (7.000 × 20 − 100.000 = $40.000); ventas objetivo = $350.000. El margen de seguridad es de 2.000 unidades (≈ 28,6 %) y el apalancamiento operativo, 140.000 ÷ 40.000 = 3,5×. Las variaciones de costos estándar dividen cada variación total en precio (cantidad real × diferencia de precio) y cantidad (precio estándar × diferencia de cantidad): variación de precio de materiales = CA × (PA − PE) y de cantidad = PE × (CA − CE), con la mano de obra construida igual. Ejemplo de materiales: PA $5,50, PE $5,00, CA 10.500 kg, CE 10.000 kg → precio $5.250 desfavorable, cantidad $2.500 desfavorable, total $7.750, que cuadra con costo real $57.750 frente a estándar $50.000. Ejemplo de mano de obra: tarifa real $21, estándar $20, horas reales 4.200, estándar 4.000 → tarifa $4.200 desfavorable, eficiencia $4.000 desfavorable, total $8.200 ($88.200 frente a $80.000). En costos relevantes solo cuentan los costos futuros que difieren entre alternativas: los costos hundidos nunca son relevantes; sí lo son los fijos evitables y el costo de oportunidad; con capacidad ociosa, un pedido especial conviene por encima de su costo incremental, y ante un cuello de botella se ordena por margen por unidad del recurso escaso. El cuadro de mando integral (Kaplan y Norton) enlaza cuatro perspectivas — aprendizaje y crecimiento → procesos internos → cliente → financiera — con indicadores adelantados y rezagados; en la sección BAR se examina junto con mapas estratégicos y KPI.

*Notas personales de estudio; no constituye asesoría fiscal, financiera ni legal. Traducción de estudio, pendiente de revisión por hablante nativo.*

## 한국어 (초역 · 初译待校)

CVP 분석의 출발점은 하나의 항등식이다. 단위공헌이익 = 판매가격 − 단위변동원가, 이익 = 판매량 × 단위공헌이익 − 총고정원가. 예시: 가격 $50, 단위변동원가 $30, 고정원가 $100,000. 단위공헌이익 = $20, 공헌이익률 = 40%. 손익분기 수량 = 100,000 ÷ 20 = 5,000개(검산: 5,000 × $20 = $100,000), 손익분기 매출 = $250,000. 목표이익 $40,000에 필요한 수량 = (100,000 + 40,000) ÷ 20 = 7,000개(검산: 7,000 × 20 − 100,000 = $40,000), 목표 매출 = $350,000. 안전마진은 2,000개(약 28.6%), 영업레버리지는 140,000 ÷ 40,000 = 3.5배이다. 표준원가 차이는 모든 총차이를 가격 부분(실제수량 × 가격차)과 수량 부분(표준가격 × 수량차)으로 나눈다. 재료 가격차이 = AQ × (AP − SP), 재료 수량차이 = SP × (AQ − SQ)이며, 노무비의 임금률차이와 능률차이도 같은 구조이다. 재료 예시: AP $5.50, SP $5.00, AQ 10,500kg, SQ 10,000kg → 가격차이 $5,250 불리, 수량차이 $2,500 불리, 합계 $7,750 불리. 실제원가 $57,750 대 표준원가 $50,000과 일치한다. 노무 예시: AR $21, SR $20, AH 4,200시간, SH 4,000시간 → 임금률차이 $4,200 불리, 능률차이 $4,000 불리, 합계 $8,200 불리($88,200 대 $80,000). 관련원가에서는 미래에 발생하고 대안 간에 차이가 나는 원가만 본다. 매몰원가는 절대 관련이 없고, 회피가능 고정원가와 기회비용은 관련이 있다. 유휴설비가 있으면 특별주문은 증분원가보다 높은 가격이면 수주할 만하고, 병목 상황에서는 제약자원 단위당 공헌이익이 높은 제품부터 배정한다. 균형성과표(Balanced Scorecard, Kaplan과 Norton)는 학습·성장 → 내부 프로세스 → 고객 → 재무의 네 관점을 인과 사슬로 연결하고 후행지표와 선행지표를 함께 본다. CPA BAR 영역에서는 전략맵, KPI와 함께 출제되며, 원가 차이는 프로세스 관점의 신호가 재무 결과로 드러난 것으로 읽는 것이 좋다.

*개인 학습 노트이며 세무·재무·법률 자문이 아닙니다. 초역으로 교정 대기 중입니다.*

## Tiếng Việt (bản dịch sơ bộ · 初译待校)

Phân tích CVP bắt đầu từ một đẳng thức: lãi góp đơn vị = giá bán − chi phí biến đổi đơn vị, và lợi nhuận = sản lượng × lãi góp đơn vị − tổng chi phí cố định. Ví dụ: giá $50, chi phí biến đổi đơn vị $30, chi phí cố định $100.000. Lãi góp đơn vị = $20; tỷ lệ lãi góp = 40%. Sản lượng hòa vốn = 100.000 ÷ 20 = 5.000 đơn vị (kiểm tra: 5.000 × $20 = $100.000); doanh thu hòa vốn = $250.000. Để đạt lợi nhuận mục tiêu $40.000: (100.000 + 40.000) ÷ 20 = 7.000 đơn vị (kiểm tra: 7.000 × 20 − 100.000 = $40.000); doanh thu mục tiêu = $350.000. Biên an toàn là 2.000 đơn vị (≈ 28,6%), đòn bẩy hoạt động = 140.000 ÷ 40.000 = 3,5 lần. Chênh lệch chi phí định mức tách mọi chênh lệch tổng thành phần giá (lượng thực tế × chênh lệch giá) và phần lượng (giá định mức × chênh lệch lượng): chênh lệch giá nguyên liệu = AQ × (AP − SP), chênh lệch lượng = SP × (AQ − SQ); nhân công có chênh lệch đơn giá và chênh lệch năng suất với cấu trúc tương tự. Ví dụ nguyên liệu: AP $5,50, SP $5,00, AQ 10.500 kg, SQ 10.000 kg → chênh lệch giá $5.250 bất lợi, chênh lệch lượng $2.500 bất lợi, tổng $7.750 bất lợi, khớp với chi phí thực tế $57.750 so với định mức $50.000. Ví dụ nhân công: AR $21, SR $20, AH 4.200 giờ, SH 4.000 giờ → chênh lệch đơn giá $4.200 bất lợi, năng suất $4.000 bất lợi, tổng $8.200 bất lợi ($88.200 so với $80.000). Chi phí thích đáng chỉ tính chi phí tương lai có khác biệt giữa các phương án: chi phí chìm không bao giờ thích đáng; chi phí cố định tránh được và chi phí cơ hội thì có. Khi còn năng lực nhàn rỗi, đơn hàng đặc biệt có lời nếu giá cao hơn chi phí tăng thêm; khi có nút thắt, hãy xếp ưu tiên theo lãi góp trên mỗi đơn vị nguồn lực khan hiếm. Thẻ điểm cân bằng (Balanced Scorecard của Kaplan và Norton) nối bốn khía cạnh theo nhân quả — học hỏi và phát triển → quy trình nội bộ → khách hàng → tài chính — kết hợp chỉ số trễ và chỉ số dẫn dắt; trong phần BAR của kỳ thi CPA, nội dung này được hỏi cùng bản đồ chiến lược và KPI.

*Ghi chú học tập cá nhân, không phải tư vấn thuế, tài chính hay pháp lý. Bản dịch sơ bộ, chờ hiệu đính.*

## हिन्दी (प्रारंभिक अनुवाद · 初译待校)

CVP विश्लेषण एक ही समीकरण से शुरू होता है: इकाई योगदान मार्जिन = विक्रय मूल्य − इकाई परिवर्तनशील लागत, और लाभ = इकाइयाँ × इकाई योगदान − कुल स्थिर लागत। उदाहरण: मूल्य $50, इकाई परिवर्तनशील लागत $30, स्थिर लागत $100,000। इकाई योगदान = $20; योगदान अनुपात = 40%। सम-विच्छेद मात्रा = 100,000 ÷ 20 = 5,000 इकाइयाँ (जाँच: 5,000 × $20 = $100,000); सम-विच्छेद बिक्री = $250,000। $40,000 लक्ष्य लाभ के लिए मात्रा = (100,000 + 40,000) ÷ 20 = 7,000 इकाइयाँ (जाँच: 7,000 × 20 − 100,000 = $40,000); लक्ष्य बिक्री = $350,000। सुरक्षा मार्जिन 2,000 इकाइयाँ (लगभग 28.6%) और परिचालन लीवरेज 140,000 ÷ 40,000 = 3.5 गुना है। मानक लागत विचरण हर कुल विचरण को मूल्य भाग (वास्तविक मात्रा × मूल्य अंतर) और मात्रा भाग (मानक मूल्य × मात्रा अंतर) में बाँटता है: सामग्री मूल्य विचरण = AQ × (AP − SP), मात्रा विचरण = SP × (AQ − SQ); श्रम की दर और दक्षता विचरण भी इसी संरचना के हैं। सामग्री उदाहरण: AP $5.50, SP $5.00, AQ 10,500 kg, SQ 10,000 kg → मूल्य विचरण $5,250 प्रतिकूल, मात्रा विचरण $2,500 प्रतिकूल, कुल $7,750 प्रतिकूल, जो वास्तविक लागत $57,750 बनाम मानक $50,000 से मेल खाता है। श्रम उदाहरण: AR $21, SR $20, AH 4,200 घंटे, SH 4,000 घंटे → दर विचरण $4,200 प्रतिकूल, दक्षता विचरण $4,000 प्रतिकूल, कुल $8,200 प्रतिकूल ($88,200 बनाम $80,000)। प्रासंगिक लागत में केवल भविष्य की वे लागतें गिनी जाती हैं जो विकल्पों में भिन्न हों: डूबी लागत (sunk cost) कभी प्रासंगिक नहीं होती; परिहार्य स्थिर लागत और अवसर लागत प्रासंगिक होती हैं। खाली क्षमता हो तो विशेष ऑर्डर वृद्धिशील लागत से ऊपर की कीमत पर लाभदायक है, और अवरोध (bottleneck) हो तो दुर्लभ संसाधन की प्रति इकाई योगदान मार्जिन से प्राथमिकता तय होती है। संतुलित स्कोरकार्ड (Kaplan और Norton) चार दृष्टिकोणों को कारण-परिणाम शृंखला से जोड़ता है — सीखना व विकास → आंतरिक प्रक्रियाएँ → ग्राहक → वित्तीय — और पश्चगामी व अग्रगामी संकेतक साथ रखता है; CPA के BAR खंड में यह रणनीति मानचित्र और KPI के साथ पूछा जाता है।

*व्यक्तिगत अध्ययन नोट्स; कर, वित्तीय या कानूनी सलाह नहीं। प्रारंभिक अनुवाद, समीक्षा लंबित।*
