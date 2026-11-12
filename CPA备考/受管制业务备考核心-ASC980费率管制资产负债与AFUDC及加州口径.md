# 受管制业务备考核心：ASC 980 费率管制、管制资产与管制负债及加州口径

> 个人学习笔记，不构成税务或会计建议。仓内《建设期利息备考核心》管 GASB 89 的费用化与受管制例外、《政府会计备考核心》管政府基金全景，本篇只管营利性受费率管制企业（电力、燃气、自来水等公用事业）的 ASC 980 本体：什么资格才能用、管制资产与管制负债怎么立、什么时候必须停用。政府自营公用事业走 GASB 62 的对应口径，只作指针。

## 中文主文

### 一、先判资格：ASC 980-10-15-2 的三要件，缺一不可

ASC 980（前身为 SFAS 71）不是按行业自动适用的。准则给的是一组必须同时满足的条件（ASC 980-10-15-2）：

1. 企业提供受管制产品或服务的费率，由独立的第三方管制者制定，或须经其批准；
2. 管制费率的设计目标，是收回企业提供该项服务的特定成本；
3. 结合需求变化与竞争程度，有合理把握认为按上述口径定的费率确实能向客户收取并收回。

三件齐备，费率制定过程的经济效果才进报表：本来要当期进损益的成本可以递延、本来要当期确认的收入可以递延。不齐备，就回到一般 GAAP，不许自称受管制而递延。考试第一步永远是先过这三关，再谈具体科目。同一家企业可以一部分业务适用（例如受管制的输配电）、另一部分不适用（例如竞争性发电），适用范围按可分离的业务部分切，不按法人整户一刀切。

### 二、管制资产：未来大概率能从费率里收回的已发生成本（ASC 980-340）

管制资产（regulatory asset）的确认门在 ASC 980-340-25-1：成本已经发生，按一般 GAAP 本应进当期费用，但管制者的行为使企业有理由认为，把这项成本放进未来可收回成本、经未来费率收回是大概率的（probable），这时才把成本资本化为管制资产，挂在账上等回收。

几个要点：

- 锚是管制者的行为（费率令、裁定、公式费率条款），不是管理层自己的希望；没有管制动作支撑的递延，只是提前不认费用。
- 回收期内是否同时赚取回报（return），看管制者给不给：给回报的管制资产在回收期还确认回报收入；只许收回本金、不给回报的，按规则折现或作相应处理，答题要分开。
- 一旦回收不再是大概率，立刻核销进当期损益，不许继续挂账等转机。管制资产的后续计量就是不断重问同一句话：还收得回来吗？

典型例子：异常风暴抢修成本、被命令提前退役电厂的未回收账面值、按费率公式先垫付后回收的燃料与外购电成本差额。

### 三、管制负债：已经向客户收了、将来要以减费或退款还回去的钱（ASC 980-405）

镜像科目是管制负债（regulatory liability），确认门在 ASC 980-405-25-1：企业已通过费率向客户收了钱，或已确认的收入，按管制者的要求大概率要在未来以降低费率或退款的方式返还客户，这时确认管制负债，把收入递延。

典型例子：燃料成本超收（实际成本低于费率里预收的数）、管制者命令退还的超额收益、以及所得税一侧的超额递延税款——税率下调后，原按高税率计提、将来要通过费率还给客户的递延税款差额（excess deferred income taxes），是近年费率案里最常见的管制负债之一。

管制资产与管制负债不能轧差列报的道理也在镜像关系里：一个是向未来客户收费的权利，一个是对未来客户减费的义务，权利义务对象与期间都不同。

### 四、所得税衔接：ASC 740-980 禁止净税法，管制资产还要毛额化

受管制企业的递延税款有专门衔接口径（ASC 740-980）：

- 禁止净税法（net-of-tax accounting）：递延税款按 ASC 740 全额确认，不许把税效果直接埋进管制资产净额里。
- 两笔递延所得税负债要认全：一是已流水式（flow-through）给客户的税收利益在暂时性差异产生时对应的递延税款；二是建设期资金补贴中权益部分（equity component of AFUDC）对应的递延税款。
- 管制者若大概率允许把未来多缴的税经费率向客户收回（或要求把少缴的税退回），就另行确认管制资产（或管制负债）；而这项管制资产本身又是一项暂时性差异，还要再确认一层递延税款——这就是毛额化（gross-up）的由来。

毛额化算例（示意数字，本地整数与 Decimal 两路复算勾稽）：设未来可收回的税额本金为 100,000 美元，适用税率 21%。管制资产 A 须满足 A 减去 A 乘 21% 等于 100,000，即 A 等于 100,000 除以（1 减 0.21）等于 100,000 除以 0.79，约 126,582.28 美元；其中税的一层为 126,582.28 乘 21%，约 26,582.28 美元；126,582.28 减 26,582.28 等于 100,000，对平。把 A 只记 100,000 是最常见的错法：收回那天还要再缴一次税，不毛额化就收不全。

### 五、建设期资金补贴 AFUDC 与电厂退役、核销两格

- **AFUDC**（allowance for funds used during construction，建设期资金补贴）：管制费率允许在建工程按债务与权益两部分计一笔资金成本并资本化进电厂成本，将来通过折旧随费率收回。债务部分冲减利息费用，权益部分计入其他收入；权益部分当期不纳税，由此产生的递延税款按上一节处理。AFUDC 不是现金，是费率机制造出来的资本化口径，现金流量表上是非现金项。
- **退役与放弃**（ASC 980-360 一带）：电厂被放弃或提前退役时，若管制者大概率允许收回但不允许在回收期赚取回报，管制资产按现值计量；若只允许收回一部分，未允许部分在裁定落定时确认损失。
- **管制者否决（disallowance）**：管制者明确不许把某项已发生成本放进费率的，否决部分立即进损失，不许继续当管制资产挂着。

### 六、停用 ASC 980：资格丢了，整套递延一起清算（ASC 980-10-40）

当某项业务不再满足三要件（例如该业务改为竞争定价、放松管制），对该部分业务停用 ASC 980：把不再符合确认条件的管制资产与管制负债从账上消除，净额进当期损益（按其性质列示），并披露停用的原因与金额。停用不是政策选择，是资格丧失的强制后果；部分停用只切丧失资格的那一块，仍受管制的业务继续用。考试爱考的正是这个转折点：放松管制法案通过、费率改市场价的那一年，报表上会出现一笔一次性的管制资产核销。

### 七、算例：一笔风暴成本的完整一生

示意算例（数字自编，本地两路复算勾稽）：某电力公司发生异常风暴抢修成本 120,000 美元，管制者发令允许在未来五年费率中收回本金（不另给回报，按准则口径此处为简化不折现的教学处理，实务须按 ASC 980-340 判断是否折现）。

- 立账：管制资产 120,000 美元，当年不进费用；
- 回收：每年随费率收回 120,000 除以 5 等于 24,000 美元，同步摊销管制资产 24,000 美元，五年收完、摊完，余额归零；
- 变体：第三年管制者复审后只许再收回余额的一部分——设三、四年已收回 48,000 美元，余额 72,000 美元中只许收回 50,000 美元，则不许收回的 72,000 减 50,000 等于 22,000 美元在裁定年立即确认损失。

勾稽：24,000 乘 5 等于 120,000；120,000 减 48,000 等于 72,000；72,000 减 50,000 等于 22,000，三步对平。

### 八、加州口径

加州的投资者拥有公用事业（investor-owned utilities，如 PG&E、Southern California Edison、San Diego Gas & Electric）由加州公用事业委员会（California Public Utilities Commission，CPUC）定费率，走总费率案（general rate case）等程序，其财务报告按 ASC 980 处理管制资产与管制负债，是本篇规则在加州的主要落点。市政自营公用事业（如市有电力局）属政府主体，走 GASB 62 把受管制业务口径编入政府会计的一套，不用 ASC 980 本体（证据等级 B：CPUC 管辖与 GASB 62 对应关系为公开制度事实，个别公司的费率令内容以 CPUC 当期裁定为准）。

> 个人学习笔记，不构成税务或会计建议。
>
> 来源：FASB ASC 980-10-15-2（三要件）、ASC 980-340-25-1（管制资产 probable 门）、ASC 980-405-25-1（管制负债）、ASC 740-980-25-1 与 25-2（禁止净税法、AFUDC 权益部分递延税款与毛额化）、ASC 980-10-40（停用）；前身 SFAS 71；政府对应口径 GASB Statement 62。

## English

ASC 980 (successor to SFAS 71) is not automatic by industry. Under ASC 980-10-15-2 an operation qualifies only if all three criteria hold: (1) rates are established by, or subject to approval of, an independent third-party regulator; (2) the regulated rates are designed to recover the specific costs of providing the service; and (3) given demand and competition, it is reasonable to assume the rates can be charged to and collected from customers. Qualification is assessed for separable portions of the business, not entity-wide.

A regulatory asset (ASC 980-340-25-1) is an incurred cost that would otherwise be expensed, capitalized because regulator action makes it probable that the cost will be recovered through future rates; if recovery ceases to be probable, the asset is written off to earnings at once. A regulatory liability (ASC 980-405-25-1) is the mirror image: amounts already collected from customers that the regulator will probably require to be returned through future rate reductions or refunds — fuel-cost over-recoveries and excess deferred income taxes after a statutory rate cut are standard examples. The two are not netted.

Income taxes have a dedicated subtopic (ASC 740-980): net-of-tax accounting is prohibited; deferred taxes are recognized in full, including for tax benefits flowed through to customers and for the equity component of AFUDC; and a regulatory asset recognized for future tax recovery is itself a temporary difference, producing the familiar gross-up. Worked example, recomputed two ways: at a 21% rate, the regulatory asset that recovers a $100,000 tax amount is $100,000 ÷ (1 − 0.21) = $100,000 ÷ 0.79 ≈ $126,582.28, of which the tax layer is ≈ $26,582.28, and $126,582.28 − $26,582.28 = $100,000. AFUDC capitalizes a debt component (offsetting interest) and an equity component (other income) into plant cost during construction. Disallowed costs are expensed when disallowed; abandoned plant is recoverable only to the extent the regulator allows, at present value if no return is allowed during recovery. When a portion of the business stops meeting the criteria (ASC 980-10-40), application is discontinued for that portion and the related regulatory balances that no longer qualify are eliminated through earnings, with disclosure. Storm-cost example: a $120,000 cost deferred and recovered over five years amortizes at $120,000 ÷ 5 = $24,000 per year ($24,000 × 5 = $120,000); after $48,000 has been recovered, a ruling allowing only $50,000 of the remaining $72,000 produces an immediate loss of $72,000 − $50,000 = $22,000. In California, investor-owned utilities regulated by the CPUC are the main ASC 980 reporters; municipal utilities are governmental and follow the GASB 62 counterpart instead (evidence grade B).

> Personal study notes only; not tax or accounting advice. Sources: FASB ASC 980-10-15-2, 980-340-25-1, 980-405-25-1, 740-980-25-1/-2, 980-10-40; GASB Statement 62.

## Español (初译待校)

La ASC 980 (sucesora de la SFAS 71) no se aplica automáticamente por sector. Según la ASC 980-10-15-2, una operación califica solo si cumple los tres criterios: (1) las tarifas las fija o aprueba un regulador independiente; (2) las tarifas están diseñadas para recuperar los costos específicos del servicio; y (3) es razonable suponer que esas tarifas podrán cobrarse a los clientes. La calificación se evalúa por partes separables del negocio.

Un activo regulatorio (ASC 980-340-25-1) es un costo ya incurrido que normalmente sería gasto, pero se capitaliza porque la actuación del regulador hace probable su recuperación en tarifas futuras; si la recuperación deja de ser probable, se castiga contra resultados de inmediato. Un pasivo regulatorio (ASC 980-405-25-1) es la imagen especular: importes ya cobrados a los clientes que probablemente habrá que devolver mediante tarifas futuras más bajas o reembolsos; los ejemplos típicos son la sobre-recuperación de combustible y el exceso de impuestos diferidos tras una rebaja legal del tipo. No se compensan entre sí.

En impuestos (ASC 740-980) está prohibida la contabilidad neta de impuestos: los impuestos diferidos se reconocen íntegros, incluidos los beneficios trasladados a los clientes y el componente de capital propio del AFUDC; y el activo regulatorio por impuestos futuros es en sí una diferencia temporaria, lo que produce el gross-up. Ejemplo, recalculado dos veces: con un tipo del 21%, el activo que recupera 100.000 dólares es 100.000 ÷ 0,79 ≈ 126.582,28, con una capa fiscal de ≈ 26.582,28, y 126.582,28 − 26.582,28 = 100.000. El AFUDC capitaliza durante la construcción un componente de deuda (que compensa intereses) y uno de capital (otro ingreso). Los costos denegados por el regulador se llevan a resultados; si una parte del negocio deja de cumplir los criterios (ASC 980-10-40), se discontinúa la aplicación y los saldos regulatorios que ya no califican se eliminan contra resultados, con revelación. Ejemplo de tormenta: 120.000 diferidos a cinco años se amortizan a 24.000 por año; tras recuperar 48.000, si solo se permiten 50.000 de los 72.000 restantes, la pérdida inmediata es 72.000 − 50.000 = 22.000. En California, las utilities de inversores reguladas por la CPUC son las principales usuarias de la ASC 980; las municipales siguen la norma equivalente de la GASB 62 (grado de evidencia B). (初译待校)

> Notas personales de estudio; no constituyen asesoría fiscal ni contable. Fuentes: FASB ASC 980-10-15-2, 980-340-25-1, 980-405-25-1, 740-980, 980-10-40; GASB 62.

## 한국어 (初译待校)

ASC 980(SFAS 71의 후계)은 업종만으로 자동 적용되지 않습니다. ASC 980-10-15-2에 따라 세 가지 요건을 모두 충족해야 합니다. (1) 요금이 독립된 제3자 규제기관에 의해 정해지거나 그 승인을 받아야 하고, (2) 규제 요금이 서비스 제공의 특정 원가를 회수하도록 설계되어야 하며, (3) 수요와 경쟁을 고려할 때 그 요금을 고객에게 부과하고 회수할 수 있다고 합리적으로 가정할 수 있어야 합니다. 자격은 분리 가능한 사업 부분별로 판단합니다.

규제자산(ASC 980-340-25-1)은 이미 발생한 원가로서 원래는 당기 비용이 되어야 하지만, 규제기관의 조치로 인해 미래 요금을 통한 회수가 probable(발생 가능성이 높음)해져 자본화한 것입니다. 회수가 더 이상 probable하지 않으면 즉시 손익으로 상각합니다. 규제부채(ASC 980-405-25-1)는 그 거울상입니다. 이미 고객에게서 받았지만 장차 요금 인하 또는 환급으로 돌려줘야 할 가능성이 높은 금액이며, 연료비 초과 회수와 법정세율 인하 후의 초과 이연법인세가 대표적 예입니다. 둘은 상계하지 않습니다.

법인세 연결(ASC 740-980)에서는 순액 세무회계(net-of-tax)가 금지됩니다. 이연법인세는 고객에게 전가된 세제 혜택과 AFUDC의 자본 구성요소를 포함해 전액 인식합니다. 미래 세금 회수를 위한 규제자산 자체도 일시적 차이이므로 gross-up이 생깁니다. 예시(두 번 재계산): 세율 21%에서 100,000달러를 회수하는 규제자산은 100,000 ÷ 0.79 ≈ 126,582.28달러, 그중 세금 층은 약 26,582.28달러이며, 126,582.28 − 26,582.28 = 100,000입니다. AFUDC는 건설기간 중 부채 구성요소(이자 상계)와 자본 구성요소(기타수익)를 플랜트 원가에 자본화합니다. 규제기관이 부인한 원가는 즉시 손실 처리합니다. 사업의 일부가 요건을 잃으면(ASC 980-10-40) 그 부분에 대해 적용을 중단하고 자격을 잃은 규제 잔액을 손익으로 제거하며 공시합니다. 폭풍 예시: 120,000달러를 5년에 걸쳐 회수하면 연 24,000달러씩 상각하고, 48,000달러 회수 후 잔액 72,000달러 중 50,000달러만 허용되면 22,000달러를 즉시 손실로 인식합니다. 캘리포니아에서는 CPUC의 규제를 받는 투자자 소유 유틸리티가 ASC 980의 주된 적용자이며, 시영 유틸리티는 GASB 62의 대응 기준을 따릅니다(증거 등급 B). (初译待校)

> 개인 학습 노트이며 세무·회계 자문이 아닙니다. 출처: FASB ASC 980-10-15-2, 980-340-25-1, 980-405-25-1, 740-980, 980-10-40; GASB 62.

## Tiếng Việt (初译待校)

ASC 980 (kế thừa SFAS 71) không áp dụng tự động theo ngành. Theo ASC 980-10-15-2, một hoạt động chỉ đủ điều kiện khi thỏa cả ba tiêu chí: (1) biểu giá do một cơ quan quản lý độc lập bên thứ ba đặt ra hoặc phê duyệt; (2) biểu giá được thiết kế để thu hồi các chi phí cụ thể của dịch vụ; và (3) có thể giả định hợp lý rằng biểu giá đó sẽ thu được từ khách hàng, xét đến nhu cầu và cạnh tranh. Việc đánh giá làm theo từng phần hoạt động tách biệt được.

Tài sản điều tiết (regulatory asset, ASC 980-340-25-1) là chi phí đã phát sinh, vốn sẽ phải ghi vào chi phí kỳ hiện tại, nhưng được vốn hóa vì hành động của cơ quan quản lý khiến việc thu hồi qua biểu giá tương lai trở nên probable (có khả năng cao xảy ra); nếu việc thu hồi không còn probable, phải ghi giảm vào kết quả kinh doanh ngay. Nợ điều tiết (regulatory liability, ASC 980-405-25-1) là hình ảnh phản chiếu: số tiền đã thu từ khách hàng mà nhiều khả năng phải trả lại qua giảm giá tương lai hoặc hoàn tiền; ví dụ điển hình là thu vượt chi phí nhiên liệu và thuế hoãn lại vượt mức sau khi luật giảm thuế suất. Hai khoản không được bù trừ.

Về thuế thu nhập (ASC 740-980), phương pháp ghi ròng sau thuế (net-of-tax) bị cấm: thuế hoãn lại được ghi đầy đủ, kể cả phần lợi ích thuế đã chuyển cho khách hàng và thành phần vốn chủ trong AFUDC; và bản thân tài sản điều tiết cho thuế tương lai cũng là một chênh lệch tạm thời, tạo ra phép gross-up. Ví dụ, đã tính lại hai lần: với thuế suất 21%, tài sản điều tiết thu hồi 100.000 đô la là 100.000 ÷ 0,79 ≈ 126.582,28, trong đó lớp thuế ≈ 26.582,28, và 126.582,28 − 26.582,28 = 100.000. AFUDC vốn hóa trong thời gian xây dựng một thành phần nợ (bù trừ lãi vay) và một thành phần vốn chủ (thu nhập khác). Chi phí bị cơ quan quản lý bác bỏ thì ghi vào lỗ ngay. Khi một phần hoạt động không còn thỏa tiêu chí (ASC 980-10-40), phải ngừng áp dụng cho phần đó và loại bỏ các số dư điều tiết không còn đủ điều kiện qua kết quả kinh doanh, kèm thuyết minh. Ví dụ bão: 120.000 đô la hoãn lại thu hồi trong năm năm thì khấu trừ 24.000 mỗi năm; sau khi đã thu 48.000, nếu trong số dư còn lại 72.000 chỉ được phép thu 50.000, khoản lỗ ghi ngay là 72.000 − 50.000 = 22.000. Tại California, các công ty tiện ích thuộc sở hữu nhà đầu tư do CPUC quản lý là đối tượng áp dụng ASC 980 chính; tiện ích thuộc thành phố đi theo chuẩn tương ứng GASB 62 (cấp bằng chứng B). (初译待校)

> Ghi chú học tập cá nhân, không phải tư vấn thuế hay kế toán. Nguồn: FASB ASC 980-10-15-2, 980-340-25-1, 980-405-25-1, 740-980, 980-10-40; GASB 62.

## हिन्दी (初译待校)

ASC 980 (SFAS 71 का उत्तराधिकारी) केवल उद्योग के आधार पर स्वतः लागू नहीं होता। ASC 980-10-15-2 के अनुसार तीनों शर्तें एक साथ पूरी होनी चाहिए: (1) दरें किसी स्वतंत्र तृतीय-पक्ष नियामक द्वारा तय या अनुमोदित हों; (2) विनियमित दरें सेवा की विशिष्ट लागतों की वसूली हेतु डिज़ाइन की गई हों; और (3) माँग व प्रतिस्पर्धा को देखते हुए यह मानना उचित हो कि वे दरें ग्राहकों से वसूली जा सकती हैं। योग्यता अलग किए जा सकने वाले व्यावसायिक हिस्सों के अनुसार परखी जाती है।

नियामक आस्ति (regulatory asset, ASC 980-340-25-1) वह लागत है जो सामान्यतः उसी अवधि में व्यय होती, परंतु नियामक कार्रवाई से भविष्य की दरों द्वारा उसकी वसूली probable (संभाव्य) हो जाने के कारण पूँजीकृत की जाती है; वसूली probable न रहे तो उसे तुरंत आय में बट्टे खाते डाला जाता है। नियामक देयता (ASC 980-405-25-1) इसकी दर्पण-छवि है: ग्राहकों से पहले ही वसूली गई राशि जिसे संभवतः भविष्य में दर-कटौती या धनवापसी से लौटाना होगा; ईंधन लागत की अतिरिक्त वसूली और वैधानिक दर-कटौती के बाद का अतिरिक्त आस्थगित कर इसके ठेठ उदाहरण हैं। दोनों का नेटिंग नहीं होता।

आयकर जोड़ (ASC 740-980) में net-of-tax लेखांकन निषिद्ध है: आस्थगित कर पूरे मान्य होते हैं, जिनमें ग्राहकों को प्रवाहित (flow-through) किए गए कर-लाभ और AFUDC का इक्विटी घटक शामिल है; और भविष्य के कर की वसूली हेतु मान्य नियामक आस्ति स्वयं एक अस्थायी अंतर है, जिससे gross-up बनता है। उदाहरण, दो बार पुनर्गणना: 21% दर पर 100,000 डॉलर वसूलने वाली नियामक आस्ति 100,000 ÷ 0.79 ≈ 126,582.28 है, जिसमें कर की परत ≈ 26,582.28 है, और 126,582.28 − 26,582.28 = 100,000। AFUDC निर्माण अवधि में ऋण घटक (ब्याज से समायोजन) और इक्विटी घटक (अन्य आय) को संयंत्र लागत में पूँजीकृत करता है। नियामक द्वारा अस्वीकृत लागत तुरंत हानि में जाती है। जब व्यवसाय का कोई हिस्सा शर्तें खो दे (ASC 980-10-40), तो उस हिस्से पर ASC 980 का प्रयोग बंद होता है और अयोग्य हो चुके नियामक शेष आय के माध्यम से हटाए जाते हैं, प्रकटीकरण सहित। तूफ़ान उदाहरण: 120,000 डॉलर को पाँच वर्षों में वसूलने पर वार्षिक परिशोधन 24,000 डॉलर; 48,000 वसूलने के बाद शेष 72,000 में से केवल 50,000 की अनुमति मिले तो 22,000 डॉलर की हानि तुरंत मान्य होगी। कैलिफ़ोर्निया में CPUC द्वारा विनियमित निवेशक-स्वामित्व वाली यूटिलिटी ASC 980 की मुख्य उपयोगकर्ता हैं; नगरपालिका यूटिलिटी GASB 62 का समकक्ष मानक अपनाती हैं (साक्ष्य ग्रेड B)। (初译待校)

> व्यक्तिगत अध्ययन नोट; कर या लेखा सलाह नहीं। स्रोत: FASB ASC 980-10-15-2, 980-340-25-1, 980-405-25-1, 740-980, 980-10-40; GASB 62.


## 补译增量（2026-11-11 15:55轮）

### 한국어 (초역 · 初译待校)

총액화(gross-up)의 전체 숫자 사슬은 이렇습니다. 미래에 회수할 세금 원금이 100,000달러이고 세율이 21%이면, 규제자산 A는 A에서 A의 21%를 뺀 값이 100,000이 되어야 하므로 A는 100,000을 0.79로 나눈 약 126,582.28달러입니다. 그중 세금 층은 126,582.28에 21%를 곱한 약 26,582.28달러이고, 126,582.28에서 26,582.28을 빼면 정확히 100,000이 됩니다. A를 100,000으로만 기록하는 것이 가장 흔한 오류입니다. 회수하는 날 다시 세금을 내야 하므로 총액화를 하지 않으면 전액을 회수할 수 없습니다.

### Tiếng Việt (Bản dịch sơ bộ · 初译待校)

Chuỗi số đầy đủ của phép gross-up như sau: nếu gốc thuế có thể thu hồi trong tương lai là 100.000 đô la và thuế suất là 21%, tài sản điều tiết A phải thỏa A trừ 21% của A bằng 100.000, tức A bằng 100.000 chia 0,79, khoảng 126.582,28 đô la. Lớp thuế trong đó là 126.582,28 nhân 21%, khoảng 26.582,28 đô la, và 126.582,28 trừ 26.582,28 đúng bằng 100.000. Ghi A chỉ là 100.000 là lỗi phổ biến nhất: vào ngày thu hồi còn phải nộp thuế một lần nữa, nên không gross-up thì không thu hồi đủ.

### हिन्दी (प्रारंभिक अनुवाद · 初译待校)

gross-up की पूरी संख्या-शृंखला इस प्रकार है: यदि भविष्य में वसूली जाने वाली कर-राशि का मूल 100,000 डॉलर है और दर 21% है, तो नियामक आस्ति A को इस शर्त को पूरा करना होगा कि A घटा A का 21% बराबर 100,000 हो, अर्थात A बराबर 100,000 भाग 0.79, लगभग 126,582.28 डॉलर। इसमें कर की परत 126,582.28 गुणा 21%, लगभग 26,582.28 डॉलर है, और 126,582.28 घटा 26,582.28 ठीक 100,000 होता है। A को केवल 100,000 लिखना सबसे आम भूल है: वसूली वाले दिन फिर कर देना होगा, इसलिए gross-up न किया जाए तो पूरी राशि वसूल नहीं होगी।

### 한국어 (초역 · 初译待校)

폭풍 비용 120,000달러의 전 생애는 이렇습니다. 처음에는 규제자산 120,000달러로 기록하고 그해 비용으로 처리하지 않습니다. 회수는 120,000을 5로 나눈 연 24,000달러씩이며 규제자산도 같은 금액씩 상각되어 5년이면 잔액이 0이 됩니다. 변형에서는 셋째 해와 넷째 해에 이미 48,000달러를 회수한 뒤 잔액 72,000달러 중 50,000달러만 추가 회수가 허용되므로, 허용되지 않은 72,000 빼기 50,000, 즉 22,000달러는 결정이 난 해에 즉시 손실로 인식합니다. 검산하면 24,000 곱하기 5는 120,000, 120,000 빼기 48,000은 72,000, 72,000 빼기 50,000은 22,000으로 세 단계가 모두 맞습니다.

### Tiếng Việt (Bản dịch sơ bộ · 初译待校)

Vòng đời đầy đủ của khoản chi phí bão 120.000 đô la như sau: ban đầu ghi tài sản điều tiết 120.000 đô la và không đưa vào chi phí năm đó; thu hồi mỗi năm 120.000 chia 5 bằng 24.000 đô la, đồng thời khấu hao tài sản điều tiết cùng số tiền, năm năm là hết, số dư về không. Ở biến thể, sau khi đã thu hồi 48.000 đô la trong năm thứ ba và thứ tư, trong số dư 72.000 đô la chỉ được thu hồi thêm 50.000 đô la, nên phần không được phép, 72.000 trừ 50.000 bằng 22.000 đô la, phải ghi nhận lỗ ngay trong năm có quyết định. Đối chiếu: 24.000 nhân 5 bằng 120.000; 120.000 trừ 48.000 bằng 72.000; 72.000 trừ 50.000 bằng 22.000, ba bước đều khớp.

### हिन्दी (प्रारंभिक अनुवाद · 初译待校)

तूफ़ान लागत 120,000 डॉलर का पूरा जीवन इस प्रकार है: शुरुआत में नियामक आस्ति 120,000 डॉलर दर्ज होती है और उस वर्ष व्यय नहीं बनती; वसूली हर वर्ष 120,000 भाग 5 बराबर 24,000 डॉलर होती है और नियामक आस्ति भी उतनी ही राशि से परिशोधित होती है, पाँच वर्ष में शेष शून्य हो जाता है। रूपांतर में, तीसरे और चौथे वर्ष में 48,000 डॉलर वसूलने के बाद शेष 72,000 डॉलर में से केवल 50,000 डॉलर की और वसूली अनुमत होती है, इसलिए अननुमत भाग, 72,000 घटा 50,000 बराबर 22,000 डॉलर, निर्णय वाले वर्ष में तुरंत हानि के रूप में मान्य होता है। जाँच: 24,000 गुणा 5 बराबर 120,000; 120,000 घटा 48,000 बराबर 72,000; 72,000 घटा 50,000 बराबर 22,000 — तीनों चरण मिलते हैं।
