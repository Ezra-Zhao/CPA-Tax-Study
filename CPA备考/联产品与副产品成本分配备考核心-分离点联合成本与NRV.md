# 联产品与副产品成本分配备考核心：分离点、联合成本与 NRV

> 板块：CPA备考（BAR 商业分析与报告）· 成本会计。本篇所有算例数字均已复算勾稽，六语各版算例数字完全一致。

## 中文主文

### 一、基本概念：分离点之前与之后

联产品（joint products）是同一批原材料、同一道工艺在分离点（split-off point）之前共同加工，过了分离点才分化成两种以上可以分别辨认的产品。分离点之前发生、无法追溯到单个产品的成本叫联合成本（joint cost，又称共同成本）；过了分离点、只为某一种产品继续加工而发生的成本叫个别成本（separable cost），直接归属到该产品，不参与分配。判断题的第一刀永远先切时间：成本发生在分离点之前还是之后——之前进联合成本池等待分配，之后直接进对应产品的存货成本。联合成本本身没有「天然正确」的分法，GAAP 也不规定唯一方法；考试与实务共同的要求只有两条：方法必须系统（systematic）、前后一贯（consistent），且能大致反映各产品消耗共同资源的受益程度。CPA 的 BAR／成本会计口径与存货计量（ASC 330 的成本累积思路）一致：分配是为了计量存货与销货成本，不是为了给单个产品算「真实利润」，因此用联合成本分配结果去做停产某产品的决策是典型陷阱——停产决策只看个别成本与可避免成本，联合成本在既定工艺下属于共同发生的成本。

### 二、四种分配法

1. **实物量法（physical units method）**：按分离点的产量（重量、件数、体积等同一计量单位）比例分配。优点是简单、客观；缺点是完全不看产品的售价与盈利能力，低值产品会被分到与其收入不相称的成本，甚至出现账面亏损。只适用于各产品计量单位可比、单位售价相近的情形。
2. **分离点销售价值法（sales value at split-off method）**：按各产品在分离点的销售价值比例分配。产品在分离点就有市价时最干净，因为价值高的产品多担成本，与受益原则最贴合；缺点是分离点无市价的产品用不了。
3. **净可实现价值法（net realizable value method，NRV 法）**：NRV＝最终售价－分离后个别成本，再按各产品 NRV 比例分配联合成本。产品在分离点没有市价、必须深加工后才能出售时用这一法。逻辑是倒挤：最终能卖多少钱，先扣掉它自己专属的深加工成本，剩下的就是它在分离点的估算价值，联合成本按这个估算价值分摊。
4. **固定毛利百分比法（constant gross-margin percentage NRV method）**：先算全部产品合计的毛利率，再让每一种产品都背上同一个毛利率，倒挤出各自应担的联合成本。步骤：合计毛利率＝（最终销售总额－联合成本－个别成本总额）÷最终销售总额；每种产品销货成本＝其最终售价×（1－合计毛利率）；该产品分到的联合成本＝其销货成本－其个别成本。此法的好处是各产品毛利率整齐划一，缺点也在这里——它人为抹平了产品之间的盈利差异，倒挤结果个别情况下甚至可能出现负的联合成本分配，考试爱拿这一点设问。

四法怎么选，看题干给什么：给了分离点市价优先销售价值法；只给最终售价与个别成本用 NRV 法；要求各产品毛利率相同用固定毛利百分比法；只给产量且单位同质才用实物量法。无论哪一法，分配额合计必须恰好等于联合成本总额，这是每道题交卷前的勾稽线。

### 三、贯穿算例（NRV 法为主，四法对照）

某化工工艺投入联合成本 300,000 美元，到分离点产出主产品 A、B 两种，另有少量副产品（下一节单讲，本节先只算 A、B）。

已知数据：
- 产品 A：产量 10,000 件；最终售价 50 美元／件，最终销售价值 500,000 美元；分离后个别成本 100,000 美元；分离点销售价值 300,000 美元。
- 产品 B：产量 10,000 件；最终售价 30 美元／件，最终销售价值 300,000 美元；分离后个别成本 50,000 美元；分离点销售价值 200,000 美元。

**第一步，算 NRV**：A 的 NRV＝500,000－100,000＝400,000 美元；B 的 NRV＝300,000－50,000＝250,000 美元；NRV 合计 650,000 美元。

**第二步，NRV 法分配**：A 分得 300,000×（400,000÷650,000）＝184,615.38 美元；B 分得 300,000×（250,000÷650,000）＝115,384.62 美元。勾稽：184,615.38＋115,384.62＝300,000 美元，与联合成本分毫不差。进一步验算单位成本：A 的总成本＝184,615.38＋100,000＝284,615.38 美元，单位成本约 28.46 美元／件；B 的总成本＝115,384.62＋50,000＝165,384.62 美元，单位成本约 16.54 美元／件。

**第三步，同例换另三法对照**：
- 实物量法：A、B 产量同为 10,000 件，各分 150,000 美元，合计 300,000 美元。
- 分离点销售价值法：A 分 300,000×（300,000÷500,000）＝180,000 美元；B 分 300,000×（200,000÷500,000）＝120,000 美元，合计 300,000 美元（分离点价值合计为 300,000＋200,000＝500,000 美元）。
- 固定毛利百分比法：最终销售总额 800,000 美元，总成本＝300,000＋150,000＝450,000 美元，总毛利 350,000 美元，合计毛利率＝350,000÷800,000＝43.75%。A 的销货成本＝500,000×（1－43.75%）＝281,250 美元，减个别成本 100,000 美元，A 分得联合成本 181,250 美元；B 的销货成本＝300,000×（1－43.75%）＝168,750 美元，减个别成本 50,000 美元，B 分得 118,750 美元。勾稽：181,250＋118,750＝300,000 美元。

四法结果互不相同，这正是考点本身：联合成本分配是计量约定，不是物理事实；同一批产品，换一法存货与毛利就换一副面孔，所以「系统与一贯」才比「选哪一法」更重要。

### 四、主产品与副产品

主产品与副产品的分界看相对销售价值：价值高、是生产目的所在的产品是主产品（联产品）；价值低、附带产出的产品是副产品（byproduct）。分界不是绝对的，价格变动时副产品也可能升格为联产品，届时要改按联产品方法参与联合成本分配。副产品不单独分摊一整套联合成本，实务与考试只认两种处理：

1. **生产时确认（抵减法）**：在副产品产出时按其 NRV 记存货，同时用该 NRV 抵减主产品的联合成本。接上例：设副产品 C 的最终售价合计 20,000 美元、个别成本 5,000 美元，NRV＝20,000－5,000＝15,000 美元。此法下可供 A、B 分配的联合成本变为 300,000－15,000＝285,000 美元，再按 NRV 比例分配：A 分 285,000×（400,000÷650,000）＝175,384.62 美元；B 分 285,000×（250,000÷650,000）＝109,615.38 美元；勾稽 175,384.62＋109,615.38＝285,000 美元，副产品 C 按 15,000 美元入账存货，三者合计仍是 300,000 美元。
2. **出售时确认（其他收入法）**：生产时不记副产品存货，联合成本 300,000 美元全额由主产品 A、B 按原方法分配（NRV 法下仍是 A 184,615.38 美元、B 115,384.62 美元）；副产品实际出售时，把出售净额（售价减出售环节个别成本）计入其他收入（other income）或抵减当期销货成本。此法简单，但副产品跨期未售时存货被低估。

选择口径：副产品价值相对重要、期末常有存量时用抵减法，报表更准；价值微小、产销基本同步时用其他收入法，省事且影响不大。考试题干出现 byproduct，先判断它给的是生产时点还是出售时点的信息，再决定走哪一条。

### 五、易错点收束

1. 个别成本不进联合成本池：它直接加在分到联合成本的那份之上构成产品总成本，算 NRV 时先扣个别成本、分配时不再扣第二次。
2. NRV 法的分母是各产品 NRV 合计，不是最终售价合计；用售价合计当分母是本章最高频的算错。
3. 固定毛利百分比法要先用全部产品算统一毛利率，再逐产品倒挤，不要给每个产品各算一个毛利率。
4. 副产品的 NRV 在抵减法下先抵减联合成本再分配主产品，顺序反了主产品分配额就全错。
5. 用分配出的单位成本判断某产品「亏不亏、该不该停产」是决策误用：联合成本分配结果只服务于存货计量与财务报告。

> 个人学习笔记，不构成税务、财务或法律建议。口径以 AICPA CPA Exam Blueprints（BAR）与 ASC 330 为准。

## English

Joint products emerge from one process and one pool of inputs up to the **split-off point**, the moment the products become separately identifiable. Costs incurred before split-off that cannot be traced to a single product are **joint costs**; costs incurred after split-off for one product only are **separable costs**, assigned directly to that product. GAAP prescribes no single allocation method; the requirements are that the method be systematic, applied consistently, and roughly reflect relative benefits. Allocation exists to measure inventory and cost of goods sold — it must never drive a keep-or-drop decision, because the joint cost is incurred jointly regardless.

The four methods: (1) **Physical units** — allocate by output quantity; simple but blind to selling prices, so a low-value product can be pushed into a paper loss. (2) **Sales value at split-off** — allocate by each product's market value at split-off; cleanest when split-off prices exist. (3) **Net realizable value (NRV)** — NRV = final sales value − separable costs; allocate in proportion to NRV; used when there is no split-off market price. (4) **Constant gross-margin percentage NRV** — compute one overall gross-margin percentage, impose it on every product, and back into each product's joint-cost share as its cost of goods sold minus its separable costs; it equalizes margins by construction and can even produce a negative allocation.

**Worked example (identical figures in every language version).** Joint cost $300,000. Product A: 10,000 units, final sales value $500,000 ($50 per unit), separable costs $100,000, sales value at split-off $300,000. Product B: 10,000 units, final sales value $300,000 ($30 per unit), separable costs $50,000, sales value at split-off $200,000. NRV: A = 500,000 − 100,000 = $400,000; B = 300,000 − 50,000 = $250,000; total NRV $650,000. NRV allocation: A = 300,000 × (400,000 ÷ 650,000) = **$184,615.38**; B = 300,000 × (250,000 ÷ 650,000) = **$115,384.62**; check: 184,615.38 + 115,384.62 = $300,000. Total cost: A = $284,615.38 (about $28.46 per unit); B = $165,384.62 (about $16.54 per unit). Same data, other methods: physical units — $150,000 each; sales value at split-off — A $180,000, B $120,000; constant gross margin — overall margin = (800,000 − 450,000) ÷ 800,000 = 43.75%, so A = 500,000 × 56.25% − 100,000 = $181,250 and B = 300,000 × 56.25% − 50,000 = $118,750, again totaling $300,000.

A **byproduct** is an incidental output of low relative sales value. Two treatments: (1) **recognized at production** — record the byproduct at NRV and deduct that NRV from the joint cost borne by the main products. With byproduct C (sales $20,000, separable costs $5,000, NRV $15,000), the allocable joint cost falls to $285,000: A = **$175,384.62**, B = **$109,615.38** (sum $285,000), and C enters inventory at $15,000. (2) **recognized at sale** — the main products absorb the full $300,000 (A $184,615.38, B $115,384.62 under NRV), and the byproduct's net proceeds are reported as other income (or a reduction of cost of goods sold) when sold. Frequent errors: putting separable costs into the joint pool, using total final sales value instead of total NRV as the NRV denominator, and reversing the byproduct deduction order.

*Personal study notes only; not tax, financial, or legal advice.*

## Español

Los productos conjuntos salen de un mismo proceso hasta el **punto de separación** (split-off point). Los costos anteriores a ese punto, no trazables a un solo producto, son **costos conjuntos**; los posteriores, propios de un solo producto, son **costos separables** y se asignan directamente. Los GAAP no imponen un método único: se exige que sea sistemático, consistente y refleje aproximadamente el beneficio relativo. La asignación sirve para valorar inventarios y el costo de ventas, nunca para decidir si se abandona un producto.

Cuatro métodos: (1) **unidades físicas** — por cantidad producida; simple, pero ignora los precios y puede dejar en pérdida contable al producto de bajo valor. (2) **Valor de ventas en el punto de separación** — el más limpio cuando existe precio en ese punto. (3) **Valor neto realizable (VNR / NRV)** — VNR = valor final de ventas − costos separables; se asigna en proporción al VNR, útil cuando no hay precio en el punto de separación. (4) **Porcentaje constante de margen bruto (sobre VNR)** — se calcula un margen bruto global, se impone a cada producto y se despeja el costo conjunto como costo de ventas menos costos separables; iguala los márgenes por construcción.

**Ejemplo calculado (cifras idénticas en todas las versiones).** Costo conjunto: $300.000. Producto A: 10.000 unidades, valor final de ventas $500.000 ($50 por unidad), costos separables $100.000, valor en el punto de separación $300.000. Producto B: 10.000 unidades, valor final $300.000 ($30 por unidad), costos separables $50.000, valor en el punto de separación $200.000. VNR: A = 500.000 − 100.000 = $400.000; B = 300.000 − 50.000 = $250.000; total $650.000. Asignación por VNR: A = 300.000 × (400.000 ÷ 650.000) = **$184.615,38**; B = 300.000 × (250.000 ÷ 650.000) = **$115.384,62**; comprobación: 184.615,38 + 115.384,62 = $300.000. Costo total: A = $284.615,38 (≈ $28,46 por unidad); B = $165.384,62 (≈ $16,54 por unidad). Con los mismos datos: unidades físicas, $150.000 cada uno; valor en el punto de separación, A $180.000 y B $120.000; margen bruto constante, margen global = (800.000 − 450.000) ÷ 800.000 = 43,75 %, con A = 500.000 × 56,25 % − 100.000 = $181.250 y B = 300.000 × 56,25 % − 50.000 = $118.750, total $300.000.

El **subproducto** (byproduct) es un producto incidental de bajo valor relativo. Dos tratamientos: (1) **reconocimiento en la producción** — se registra por su VNR y ese VNR reduce el costo conjunto de los productos principales. Con el subproducto C (ventas $20.000, costos separables $5.000, VNR $15.000), el costo conjunto asignable baja a $285.000: A = **$175.384,62** y B = **$109.615,38** (suma $285.000), y C entra en inventario por $15.000. (2) **Reconocimiento en la venta** — los productos principales absorben los $300.000 completos (A $184.615,38; B $115.384,62 por VNR) y el producto neto del subproducto se presenta como otros ingresos al venderse. Errores frecuentes: meter los costos separables en el fondo conjunto, usar las ventas finales totales en vez del VNR total como denominador, e invertir el orden de la deducción del subproducto. *(Traducción de estudio, pendiente de revisión / 初译待校)*

*Notas personales de estudio; no constituye asesoría fiscal, financiera ni legal.*

## 한국어 (초역 · 初译待校)

연제품은 **분리점**(split-off point)까지 하나의 공정에서 함께 만들어집니다. 분리점 이전에 발생해 개별 제품으로 추적할 수 없는 원가가 **결합원가**(joint cost)이고, 분리점 이후 특정 제품에만 발생하는 원가는 **개별원가**(separable cost)로 해당 제품에 직접 귀속됩니다. GAAP는 유일한 배부 방법을 정하지 않으며, 체계적이고 일관되며 상대적 효익을 대략 반영할 것을 요구합니다. 배부는 재고자산과 매출원가 측정을 위한 것이지, 제품 중단 결정의 근거가 아닙니다.

네 가지 방법: (1) **물량 기준법** — 생산량 비례 배부. 단순하지만 가격을 무시해 저가 제품이 장부상 손실이 될 수 있습니다. (2) **분리점 판매가치법** — 분리점 시장가격이 있을 때 가장 깔끔합니다. (3) **순실현가능가치법(NRV)** — NRV = 최종 판매가치 − 개별원가. NRV 비례로 배부하며 분리점 가격이 없을 때 씁니다. (4) **고정 매출총이익률법** — 전체 매출총이익률을 하나로 구해 모든 제품에 적용하고, 매출원가에서 개별원가를 빼 결합원가 배부액을 역산합니다. 이익률이 강제로 균일해집니다.

**계산 예시(모든 언어판 숫자 동일).** 결합원가 $300,000. 제품 A: 10,000개, 최종 판매가치 $500,000(개당 $50), 개별원가 $100,000, 분리점 판매가치 $300,000. 제품 B: 10,000개, 최종 판매가치 $300,000(개당 $30), 개별원가 $50,000, 분리점 판매가치 $200,000. NRV: A = 500,000 − 100,000 = $400,000, B = 300,000 − 50,000 = $250,000, 합계 $650,000. NRV 배부: A = 300,000 × (400,000 ÷ 650,000) = **$184,615.38**, B = 300,000 × (250,000 ÷ 650,000) = **$115,384.62**. 검산: 184,615.38 + 115,384.62 = $300,000. 총원가: A = $284,615.38(개당 약 $28.46), B = $165,384.62(개당 약 $16.54). 같은 자료의 다른 방법: 물량 기준 각 $150,000, 분리점 판매가치법 A $180,000·B $120,000, 고정 매출총이익률법 전체 이익률 = (800,000 − 450,000) ÷ 800,000 = 43.75%로 A = 500,000 × 56.25% − 100,000 = $181,250, B = 300,000 × 56.25% − 50,000 = $118,750, 합계 $300,000.

**부산물**(byproduct)은 상대적 판매가치가 낮은 부수적 산출물입니다. 처리법은 둘입니다. (1) **생산 시점 인식**: 부산물을 NRV로 기록하고 그 NRV를 주제품의 결합원가에서 차감합니다. 부산물 C(판매 $20,000, 개별원가 $5,000, NRV $15,000)가 있으면 배부 대상 결합원가는 $285,000이 되어 A = **$175,384.62**, B = **$109,615.38**(합계 $285,000), C는 $15,000으로 재고에 기록됩니다. (2) **판매 시점 인식**: 주제품이 $300,000 전액을 부담하고(NRV법 기준 A $184,615.38, B $115,384.62), 부산물 순매각액은 판매 시 기타수익으로 보고합니다. 흔한 오류: 개별원가를 결합원가 풀에 넣는 것, NRV 분모에 최종 판매가치 합계를 쓰는 것, 부산물 차감 순서를 뒤집는 것. *(초벌 번역, 교정 대기)*

*개인 학습 노트이며 세무·재무·법률 자문이 아닙니다.*

## Tiếng Việt (bản dịch sơ bộ · 初译待校)

Sản phẩm liên hợp được tạo ra trong cùng một quy trình cho đến **điểm tách** (split-off point). Chi phí phát sinh trước điểm tách, không truy được cho từng sản phẩm, là **chi phí liên hợp** (joint cost); chi phí sau điểm tách, chỉ cho một sản phẩm, là **chi phí riêng** (separable cost), tính thẳng cho sản phẩm đó. GAAP không quy định một phương pháp phân bổ duy nhất; yêu cầu là phương pháp phải có hệ thống, nhất quán và phản ánh xấp xỉ lợi ích tương đối. Phân bổ chỉ để đo lường hàng tồn kho và giá vốn, không dùng để quyết định bỏ hay giữ một sản phẩm.

Bốn phương pháp: (1) **Theo sản lượng vật chất** — phân bổ theo số lượng; đơn giản nhưng bỏ qua giá bán, có thể đẩy sản phẩm giá trị thấp thành lỗ trên sổ sách. (2) **Theo giá trị bán tại điểm tách** — sạch nhất khi có giá thị trường tại điểm tách. (3) **Theo giá trị thuần có thể thực hiện (NRV)** — NRV = giá trị bán cuối cùng − chi phí riêng; phân bổ theo tỉ lệ NRV, dùng khi không có giá tại điểm tách. (4) **Tỉ lệ lãi gộp cố định trên NRV** — tính một tỉ lệ lãi gộp chung cho toàn bộ, áp cho mọi sản phẩm rồi suy ngược phần chi phí liên hợp bằng giá vốn trừ chi phí riêng; cách này ép mọi sản phẩm có cùng tỉ lệ lãi gộp.

**Ví dụ tính toán (số liệu giống hệt ở mọi bản ngôn ngữ).** Chi phí liên hợp $300.000. Sản phẩm A: 10.000 đơn vị, giá trị bán cuối cùng $500.000 ($50/đơn vị), chi phí riêng $100.000, giá trị bán tại điểm tách $300.000. Sản phẩm B: 10.000 đơn vị, giá trị bán cuối cùng $300.000 ($30/đơn vị), chi phí riêng $50.000, giá trị bán tại điểm tách $200.000. NRV: A = 500.000 − 100.000 = $400.000; B = 300.000 − 50.000 = $250.000; tổng $650.000. Phân bổ theo NRV: A = 300.000 × (400.000 ÷ 650.000) = **$184.615,38**; B = 300.000 × (250.000 ÷ 650.000) = **$115.384,62**; kiểm tra: 184.615,38 + 115.384,62 = $300.000. Tổng chi phí: A = $284.615,38 (khoảng $28,46/đơn vị); B = $165.384,62 (khoảng $16,54/đơn vị). Cùng dữ liệu với các phương pháp khác: theo sản lượng, mỗi sản phẩm $150.000; theo giá trị tại điểm tách, A $180.000 và B $120.000; lãi gộp cố định, tỉ lệ chung = (800.000 − 450.000) ÷ 800.000 = 43,75%, A = 500.000 × 56,25% − 100.000 = $181.250, B = 300.000 × 56,25% − 50.000 = $118.750, tổng $300.000.

**Phụ phẩm** (byproduct) là đầu ra phụ có giá trị bán tương đối thấp. Hai cách xử lý: (1) **Ghi nhận khi sản xuất** — ghi phụ phẩm theo NRV và khấu trừ NRV đó khỏi chi phí liên hợp của sản phẩm chính. Với phụ phẩm C (doanh thu $20.000, chi phí riêng $5.000, NRV $15.000), chi phí liên hợp được phân bổ giảm còn $285.000: A = **$175.384,62**, B = **$109.615,38** (tổng $285.000), C vào tồn kho $15.000. (2) **Ghi nhận khi bán** — sản phẩm chính gánh toàn bộ $300.000 (theo NRV: A $184.615,38; B $115.384,62) và số tiền thu ròng từ phụ phẩm được báo cáo là thu nhập khác khi bán. Lỗi thường gặp: cho chi phí riêng vào quỹ chi phí liên hợp, dùng tổng giá trị bán cuối cùng thay vì tổng NRV làm mẫu số, và đảo ngược thứ tự khấu trừ phụ phẩm. *(Bản dịch sơ bộ, chờ hiệu đính)*

*Ghi chú học tập cá nhân, không phải tư vấn thuế, tài chính hay pháp lý.*

## हिन्दी (प्रारंभिक अनुवाद · 初译待校)

संयुक्त उत्पाद एक ही प्रक्रिया से **विभाजन बिंदु** (split-off point) तक साथ बनते हैं। विभाजन बिंदु से पहले की, किसी एक उत्पाद से न जुड़ सकने वाली लागत **संयुक्त लागत** (joint cost) है; उसके बाद किसी एक उत्पाद पर होने वाली लागत **पृथक लागत** (separable cost) है और सीधे उसी उत्पाद को जाती है। GAAP कोई एकमात्र विधि नहीं थोपता; शर्त है कि विधि व्यवस्थित हो, लगातार लागू हो और सापेक्ष लाभ को मोटे तौर पर दर्शाए। यह विभाजन इन्वेंटरी और बिक्री-लागत के मापन के लिए है, किसी उत्पाद को बंद करने के निर्णय के लिए नहीं।

चार विधियाँ: (1) **भौतिक इकाई विधि** — मात्रा के अनुपात में; सरल किंतु मूल्य की अनदेखी करती है, कम मूल्य वाला उत्पाद कागज़ी घाटे में जा सकता है। (2) **विभाजन बिंदु पर विक्रय मूल्य विधि** — वहाँ बाज़ार मूल्य हो तो सबसे स्वच्छ। (3) **शुद्ध वसूलीयोग्य मूल्य विधि (NRV)** — NRV = अंतिम विक्रय मूल्य − पृथक लागत; NRV के अनुपात में विभाजन, जब विभाजन बिंदु पर मूल्य न हो तब उपयोगी। (4) **स्थिर सकल-मार्जिन प्रतिशत विधि** — एक समग्र सकल-मार्जिन प्रतिशत निकालकर हर उत्पाद पर लागू करें और बिक्री-लागत में से पृथक लागत घटाकर संयुक्त लागत का हिस्सा उलटी गणना से निकालें; इससे सभी उत्पादों का मार्जिन ज़बरदस्ती बराबर हो जाता है।

**परिकलित उदाहरण (सभी भाषा संस्करणों में संख्याएँ एक समान)।** संयुक्त लागत $300,000। उत्पाद A: 10,000 इकाइयाँ, अंतिम विक्रय मूल्य $500,000 (प्रति इकाई $50), पृथक लागत $100,000, विभाजन बिंदु पर विक्रय मूल्य $300,000। उत्पाद B: 10,000 इकाइयाँ, अंतिम विक्रय मूल्य $300,000 (प्रति इकाई $30), पृथक लागत $50,000, विभाजन बिंदु पर विक्रय मूल्य $200,000। NRV: A = 500,000 − 100,000 = $400,000; B = 300,000 − 50,000 = $250,000; कुल $650,000। NRV विभाजन: A = 300,000 × (400,000 ÷ 650,000) = **$184,615.38**; B = 300,000 × (250,000 ÷ 650,000) = **$115,384.62**; जाँच: 184,615.38 + 115,384.62 = $300,000। कुल लागत: A = $284,615.38 (लगभग $28.46 प्रति इकाई); B = $165,384.62 (लगभग $16.54 प्रति इकाई)। वही आँकड़े, अन्य विधियाँ: भौतिक इकाई — प्रत्येक $150,000; विभाजन बिंदु मूल्य — A $180,000, B $120,000; स्थिर सकल मार्जिन — समग्र मार्जिन = (800,000 − 450,000) ÷ 800,000 = 43.75%, A = 500,000 × 56.25% − 100,000 = $181,250, B = 300,000 × 56.25% − 50,000 = $118,750, कुल $300,000।

**उप-उत्पाद** (byproduct) कम सापेक्ष मूल्य वाला आकस्मिक उत्पादन है। दो उपचार: (1) **उत्पादन पर मान्यता** — उप-उत्पाद को NRV पर दर्ज करें और वह NRV मुख्य उत्पादों की संयुक्त लागत से घटाएँ। उप-उत्पाद C (बिक्री $20,000, पृथक लागत $5,000, NRV $15,000) हो तो विभाजनयोग्य संयुक्त लागत $285,000 रह जाती है: A = **$175,384.62**, B = **$109,615.38** (योग $285,000), और C $15,000 पर इन्वेंटरी में जाता है। (2) **बिक्री पर मान्यता** — मुख्य उत्पाद पूरे $300,000 वहन करते हैं (NRV से A $184,615.38, B $115,384.62) और उप-उत्पाद की शुद्ध प्राप्ति बिक्री के समय अन्य आय के रूप में दिखाई जाती है। आम भूलें: पृथक लागत को संयुक्त पूल में डालना, NRV के हर में अंतिम विक्रय मूल्य का योग रखना, और उप-उत्पाद कटौती का क्रम उलट देना। *(प्रारंभिक अनुवाद, समीक्षा लंबित)*

*व्यक्तिगत अध्ययन नोट; कर, वित्तीय या कानूनी सलाह नहीं।*

---
*个人学习笔记，不构成税务建议。*
