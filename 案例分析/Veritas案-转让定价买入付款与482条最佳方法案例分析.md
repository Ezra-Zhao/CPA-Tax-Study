# Veritas 案：转让定价买入付款、§ 482 最佳方法与聚合估值之争

> 个人学习笔记，不构成税务建议。案件主线：Veritas Software Corp. v. Commissioner, 133 T.C. 297 (2009)，美国税务法院。金额均为判决公开口径的约数，具体数字以判决原文为准。仓内分工：Altera 篇管 § 482 成本分摊条例本身的有效性，本篇管估值方法之争的事实战，Amazon 案与本篇同属买入付款聚合之争、以下写明分工。

## 中文主文

跨国软件公司把现成平台技术装进海外成本分摊安排时，第一笔钱怎么算，往往就是一场几亿美元的官司。Veritas 案问的是：美国母公司把已经做出来的平台无形资产交给爱尔兰子公司共同开发，子公司要付的买入付款（buy-in payment），应当只按转让时点那些现成无形资产的价值算，还是可以把公司后来才做出来的技术、后来才长大的市场与整个企业的未来收益一并打包聚合（aggregation）估值。税务法院选了前者，并把 IRS 的调整大幅调减。这案子至今仍是 § 482 最佳方法规则（best method rule）最常被引的事实战样本。

### 一、案情：成本分摊安排与一笔被重新估价的买入付款

- **当事人与安排**：Veritas Software Corp. 是美国软件公司。它与爱尔兰关联公司订立成本分摊安排（cost sharing arrangement），由海外公司分担后续研发成本，并取得在约定地域利用既有平台技术开发与销售产品的权利。作为取得既有平台无形资产使用权的对价，海外公司须向美国公司支付买入付款，其形式与金额依安排约定分期或按特许费结构处理。
- **争议税年与 IRS 立场**：在涉案年度的查核中，IRS 依 § 482 重新估价，认为原买入付款严重偏低。IRS 专家采用带聚合色彩的方法，把转让标的看成接近整个业务平台乃至其后续发展潜力，估出的买入价约在 25 亿美元量级（约数，以判决原文为准）。
- **纳税人立场**：Veritas 主张应以可比非受控交易（comparable uncontrolled transaction, CUT）为锚：市场上独立方为类似软件平台授权实际支付的费率与价款，才是这笔既有技术在转让时点的独立交易价格；后续研发的成本已由成本分摊各方按年分担，不能再塞回买入价里收第二遍。

### 二、法院第一步：买入付款只买转让时点已存在的平台

- **标的先行定界**：成本分摊的买入付款，买的是安排开始时已经存在、被拿出来共享的平台无形资产（platform intangibles）。安排开始之后才研发出来的成果，其成本已经由各参与方通过年度成本分摊摊掉了，成果的权益也按分摊结构归属；把未来成果的价值提前资本化进买入价，等于同一份价值收两次。
- **后续成功不能倒灌**：企业后来经营得好、产品卖得旺，证明的是后续研发与市场执行的价值，不能 retroactively 证明转让时点的既有技术就值那么多。以结果倒推起点的估值，在法院眼里不是独立交易原则，而是事后诸葛。
- **与 § 367(d) 及周期性调整的边界一句带过**：超级特许费与周期性调整有各自的法定与条例通道，IRS 不能在没有满足其条件时，借聚合估值把同样的效果绕道做出来。通道归通道，方法归方法。

### 三、法院第二步：最佳方法规则下，CUT 胜过聚合估值

- **规则框架**：§ 482 的核心是独立交易原则（arm's length standard），Reg. § 1.482-1(c) 的最佳方法规则要求按事实与可比数据的可靠性，在可用方法里挑最可靠的那一个。方法没有法定排位，赢在数据，不赢在气势。
- **IRS 方法为何落败**：IRS 的聚合式估值把被转让的既有平台与未被转让的后续无形资产、商誉性因素与企业整体收益捆在一起，法院认定这种做法在涉案事实与当时条例下任意且不可靠：可比性对不上、把不属于买入标的的价值算了进来。用判决的逻辑说，聚合不是一种更全面的精确，而是把标的换掉了。
- **CUT 为何胜出**：Veritas 一侧拿出的可比非受控授权交易，与被转让平台技术的性质、市场与授权结构足够接近，经调整后能直接锚定独立交易价格。法院在 CUT 框架内做了自己的调整与取舍，最终认定的买入付款约在 9 亿美元量级（约 8.95 亿美元，约数以判决原文为准），远低于 IRS 的约 25 亿美元主张。
- **算例一（案件量级，约数）**：IRS 主张约 2,500（百万美元）减法院认定约 895，差额 2,500 减 895 等于 1,605，即约 16 亿美元的调整被调减；调减比例 1,605 除以 2,500 等于约 64.2%。本地两遍复算，勾稽一致。注意此算例只示意量级与比例，正式引用回判决原文核数。
- **算例二（教学示意，非案件数字）**：设海外公司某年利用平台技术的相关销售额为 1,000（百万美元），经调整的可比 CUT 费率为 15%，则该年买入对价的费率锚为 1,000 乘 15% 等于 150；若改用聚合法把后续成果与企业整体收益打包，同年可能估到 400，两者差 400 减 150 等于 250。差额的来源不是技术本身涨价，而是标的被悄悄扩大，这正是法院拒绝聚合的算例版。

### 四、与 Altera、Amazon 的分工：三种争点不要混答

- **与 Altera 分工**：Altera 案（145 T.C. 91 (2015)，第九巡回 2019 年维持条例）争的是条例有效性：财政部能不能通过条例要求成本分摊参与方把股票薪酬成本也纳入分摊池，那是行政法与条例制定程序之争。Veritas 争的是个案估值：在有效条例之下，这笔买入价用哪个方法算最可靠。一个问规则能不能立，一个问数字怎么算。
- **与 Amazon 分工**：Amazon 案（148 T.C. 108 (2017)，第九巡回 2019 年维持税务法院）与 Veritas 是同一家族的事实战：同样是买入付款、同样是 IRS 聚合估值被税务法院拒绝、同样以转让时点既有无形资产为标的。Veritas 在前、是这条线的源头判例，Amazon 在后、确认了同一立场在另一组事实上的适用。答题时以 Veritas 为方法论起点、Amazon 为后续确认，两篇不要互相替代。
- **时代边界**：Veritas 与 Amazon 审的都是较早年度与其当时条例。2009 年前后成本分摊条例修订、以及 2017 年税改在 § 482 增设关于聚合估值与周期性调整的成文授权之后，新年度案件的法律地形已经变化；引 Veritas 时必须带上它的年度与条例版本前提，不能无条件平移到今天的安排。这一边界恰恰是本案最容易被误用的地方，写明证据等级：判例本身 A 级，其对现行安排的可平移程度须逐案核（B 级）。

### 五、要点清单与加州口径

- **要点清单**：第一，买入付款只买转让时点已存在的平台无形资产，后续成果的成本已在年度分摊里付过。第二，最佳方法规则按可靠性选方法，CUT 有好可比数据时优先于把企业整体打包的聚合估值。第三，后续经营成功不能倒灌为转让时点的价值。第四，IRS 的调整被大幅调减，不等于纳税人原价全对，法院是在 CUT 框架内重算了一个数。第五，引本案必须注年度与条例版本，税改后的聚合授权是另一套地形。
- **加州口径**：加州没有州版 § 482 买入付款判例体系。加州的关联方收入分配调整走《收入与税收法典》第 24725 条一带的州级授权（该条大体对应联邦 § 482 的分配与调整思路），跨国成本分摊在州层面的处理以 FTB 当期口径为准，联邦 Veritas 的方法论可作分析参考、不自动成为州法结论（证据等级 B）。

> 个人学习笔记，不构成税务建议。
>
> 来源：Veritas Software Corp. v. Commissioner, 133 T.C. 297 (2009)；IRC § 482；Treas. Reg. § 1.482-1(c)（最佳方法规则）与 § 1.482-7（成本分摊，含买入付款，现行条号以涉案年度版本为准）；对照 Altera Corp. v. Commissioner, 145 T.C. 91 (2015), aff'd, 926 F.3d 1061 (9th Cir. 2019) 与 Amazon.com, Inc. v. Commissioner, 148 T.C. 108 (2017), aff'd, 934 F.3d 976 (9th Cir. 2019)（仓内 Altera 另有专篇）。

## English

*Veritas Software Corp. v. Commissioner*, 133 T.C. 297 (2009), is the leading fact-fight over a cost-sharing **buy-in payment** under § 482. Veritas's Irish affiliate joined a cost sharing arrangement and had to pay for the right to use the existing platform intangibles; the IRS revalued that buy-in with an aggregation-flavored approach that swept in later-developed technology and the business's future earning power, arriving at a figure on the order of **$2.5 billion** (approximate; see the opinion). The Tax Court rejected that approach. A buy-in buys only the platform intangibles that existed at the start of the arrangement: the fruits of later R&D are already paid for through the annual cost shares, and later commercial success cannot be poured back into the transfer-date value. Under the **best method rule** of Reg. § 1.482-1(c), the court found the comparable uncontrolled transaction (CUT) method, anchored in real third-party licenses for comparable software, more reliable than an aggregation that changed the subject of the valuation, and it redetermined the buy-in at roughly **$895 million** (approximate). The magnitude check: 2,500 − 895 = 1,605, a reduction of about 64.2% of the IRS figure; and in a purely illustrative example, sales of 1,000 at an adjusted CUT rate of 15% give an annual anchor of 150, against an aggregated 400 — the 250 gap comes from enlarging the subject, not from the technology being worth more.

Keep the neighbors separate. *Altera* is about the **validity of a regulation** (whether stock-based compensation must be put in the cost-sharing pool — an administrative-law fight), while Veritas is about **which valuation method is most reliable on these facts**. *Amazon* is Veritas's sibling fact-fight: same rejection of IRS aggregation, with Veritas as the source case and Amazon as later confirmation. And mind the era: Veritas and Amazon were decided under the regulatory regime for their years; the cost-sharing regulations were revised around 2009 and the 2017 tax reform added statutory language on aggregate valuation to § 482, so the case cannot be transplanted to a modern arrangement without checking the applicable version (precedent itself grade A; transplantability grade B). California has no state buy-in case law; related-party allocation adjustments run through Revenue and Taxation Code § 24725 and current FTB guidance.

> Personal study notes only; not tax advice. Sources: *Veritas Software Corp. v. Commissioner*, 133 T.C. 297 (2009); IRC § 482; Treas. Reg. §§ 1.482-1(c), 1.482-7; *Altera* and *Amazon* as cited in the Chinese text.

## Español (traducción de estudio)

*Veritas Software Corp. v. Commissioner*, 133 T.C. 297 (2009), es el litigio de hechos paradigmático sobre el **pago de entrada (buy-in)** de un acuerdo de costos compartidos bajo la § 482. La filial irlandesa de Veritas se sumó a un acuerdo de reparto de costos y debía pagar por el derecho a usar los intangibles de plataforma ya existentes; el IRS revaluó ese pago con un enfoque de agregación que incorporaba la tecnología desarrollada después y el potencial futuro del negocio, llegando a una cifra del orden de **2.500 millones de dólares** (aproximada; véase la sentencia). El Tribunal Fiscal lo rechazó: el buy-in compra solo los intangibles de plataforma existentes al inicio del acuerdo, porque los frutos de la I+D posterior ya se pagan con las cuotas anuales de costos, y el éxito comercial posterior no puede verterse hacia atrás en el valor a la fecha de transferencia. Bajo la **regla del mejor método** del Reg. § 1.482-1(c), el tribunal consideró más fiable el método de la transacción comparable no controlada (CUT), anclado en licencias reales de terceros para software comparable, que una agregación que cambiaba el objeto de la valoración, y fijó el buy-in en unos **895 millones de dólares** (aproximados). Comprobación de magnitud: 2.500 − 895 = 1.605, una reducción de cerca del 64,2 % de la cifra del IRS; y en un ejemplo puramente ilustrativo, ventas de 1.000 a una tasa CUT ajustada del 15 % dan un ancla anual de 150 frente a 400 con agregación: la diferencia de 250 viene de ampliar el objeto, no de que la tecnología valga más.

No se debe confundir con los vecinos. *Altera* trata de la **validez de un reglamento** (si la compensación en acciones debe entrar en el fondo de costos compartidos: un litigio de derecho administrativo), mientras que Veritas trata de **qué método de valoración es más fiable en estos hechos**. *Amazon* es el litigio hermano: mismo rechazo de la agregación del IRS, con Veritas como caso fuente y Amazon como confirmación posterior. Y ojo con la época: ambos casos se decidieron bajo el régimen reglamentario de sus años; los reglamentos de costos compartidos se revisaron hacia 2009 y la reforma fiscal de 2017 añadió a la § 482 lenguaje legal sobre valoración agregada, así que el caso no se trasplanta a un acuerdo actual sin revisar la versión aplicable. California no tiene jurisprudencia estatal de buy-in; los ajustes entre partes vinculadas corren por la § 24725 del código fiscal estatal y la guía vigente de la FTB.

> Notas personales de estudio; no constituyen asesoría fiscal. Fuentes: *Veritas Software Corp. v. Commissioner*, 133 T.C. 297 (2009); IRC § 482; Reg. §§ 1.482-1(c), 1.482-7; *Altera* y *Amazon*, citados en el texto chino.

## 한국어 (초역, 원어민 감수 대기)

*Veritas Software Corp. v. Commissioner*, 133 T.C. 297 (2009)은 § 482 아래 비용분담 **매입 지급금(buy-in payment)**을 둘러싼 대표적인 사실 다툼입니다. Veritas의 아일랜드 관계회사는 비용분담 약정에 참여하면서 이미 존재하던 플랫폼 무형자산을 사용할 권리의 대가를 내야 했습니다. IRS는 나중에 개발된 기술과 사업의 미래 수익력까지 쓸어 담는 집계(aggregation) 성격의 방법으로 그 지급금을 다시 평가해 약 **25억 달러** 규모(約수, 판결문 확인)의 수치를 냈습니다. 조세법원은 이를 거부했습니다. 매입 지급금이 사는 것은 약정 시작 시점에 이미 존재하던 플랫폼 무형자산뿐입니다. 이후 연구개발의 성과는 연간 비용 분담금으로 이미 대가가 지불되었고, 이후의 상업적 성공을 이전 시점 가치에 거꾸로 부어 넣을 수는 없습니다. Reg. § 1.482-1(c)의 **최선 방법 규칙(best method rule)** 아래에서 법원은, 평가 대상 자체를 바꿔 버리는 집계법보다 비교 가능한 소프트웨어에 대한 실제 제3자 라이선스에 닻을 내린 비교가능 비통제 거래(CUT) 방법이 더 신뢰할 만하다고 보고, 매입 지급금을 약 **8억 9,500만 달러**(約수)로 다시 정했습니다. 규모 검산: 2,500 − 895 = 1,605로 IRS 수치의 약 64.2%가 깎였고, 순수한 예시로 매출 1,000에 조정 CUT 요율 15%를 곱하면 연간 닻은 150인데 집계법에서는 400이 되어, 그 250의 차이는 기술의 가치가 올라서가 아니라 대상이 넓어졌기 때문에 생깁니다.

이웃 사건과 섞지 마십시오. *Altera*는 **규정의 유효성**(주식 기준 보상을 비용 분담 풀에 넣어야 하는가라는 행정법 다툼)에 관한 것이고, Veritas는 **이 사실관계에서 어떤 평가 방법이 가장 신뢰할 만한가**에 관한 것입니다. *Amazon*은 같은 계열의 사실 다툼으로, IRS 집계법을 거부한 같은 입장이 Veritas를 원천 판례로, Amazon을 후속 확인으로 이어집니다. 시대 구분도 중요합니다. 두 사건 모두 해당 연도의 규정 체제 아래에서 결정되었고, 비용분담 규정은 2009년 전후에 개정되었으며 2017년 세제 개편은 § 482에 집계 평가에 관한 성문 문언을 더했으므로, 적용 버전을 확인하지 않고 오늘의 약정에 그대로 옮길 수 없습니다. 캘리포니아에는 주 차원의 매입 지급금 판례가 없고, 특수관계자 배분 조정은 주 세법 § 24725와 FTB의 현행 안내를 따릅니다. (초역, 원어민 감수 대기)

> 개인 학습 노트이며 세무 자문이 아닙니다. 출처: *Veritas Software Corp. v. Commissioner*, 133 T.C. 297 (2009); IRC § 482; Reg. §§ 1.482-1(c), 1.482-7; 본문에 인용된 *Altera*와 *Amazon*.

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

*Veritas Software Corp. v. Commissioner*, 133 T.C. 297 (2009), là vụ tranh chấp sự kiện tiêu biểu về **khoản thanh toán mua quyền tham gia (buy-in payment)** trong thỏa thuận chia sẻ chi phí theo § 482. Công ty liên kết Ireland của Veritas tham gia thỏa thuận chia sẻ chi phí và phải trả tiền cho quyền sử dụng các tài sản vô hình nền tảng đã có sẵn; IRS định giá lại khoản buy-in đó bằng cách tiếp cận mang tính gộp (aggregation), cuốn cả công nghệ phát triển về sau và sức kiếm tiền tương lai của doanh nghiệp vào, cho ra con số ở mức khoảng **2,5 tỷ đô la** (số ước lượng; xem bản án). Tòa án Thuế bác bỏ cách làm đó: khoản buy-in chỉ mua các tài sản vô hình nền tảng đã tồn tại khi thỏa thuận bắt đầu, vì thành quả R&D về sau đã được trả qua phần chia sẻ chi phí hằng năm, và thành công thương mại sau này không thể đổ ngược vào giá trị tại thời điểm chuyển giao. Theo **quy tắc phương pháp tốt nhất** của Reg. § 1.482-1(c), tòa cho rằng phương pháp giao dịch không bị kiểm soát có thể so sánh (CUT), neo vào các giấy phép thực tế của bên thứ ba cho phần mềm tương đương, đáng tin hơn cách gộp làm thay đổi chính đối tượng định giá, và tòa xác định lại khoản buy-in ở mức khoảng **895 triệu đô la** (số ước lượng). Kiểm tra độ lớn: 2.500 − 895 = 1.605, tức giảm khoảng 64,2% so với con số của IRS; và trong một ví dụ thuần minh họa, doanh số 1.000 nhân tỷ lệ CUT đã điều chỉnh 15% cho neo hằng năm là 150, so với 400 theo cách gộp — khoảng chênh 250 đến từ việc mở rộng đối tượng chứ không phải công nghệ đáng giá hơn.

Đừng trộn với các vụ kề bên. *Altera* bàn về **hiệu lực của một quy định** (có phải đưa bồi thường bằng cổ phiếu vào quỹ chia sẻ chi phí hay không — tranh chấp luật hành chính), còn Veritas bàn về **phương pháp định giá nào đáng tin nhất trên các sự kiện này**. *Amazon* là vụ anh em cùng họ: cùng bác bỏ cách gộp của IRS, với Veritas là án nguồn và Amazon là xác nhận về sau. Cũng phải để ý thời đại: cả hai vụ đều quyết theo chế độ quy định của những năm đó; quy định chia sẻ chi phí được sửa quanh 2009 và cải cách thuế 2017 đã thêm ngôn ngữ luật định về định giá gộp vào § 482, nên không thể chuyển vụ án sang một thỏa thuận hiện nay mà không kiểm tra phiên bản áp dụng. California không có án lệ buy-in cấp bang; điều chỉnh phân bổ giữa các bên liên kết đi theo § 24725 của bộ luật thuế bang và hướng dẫn hiện hành của FTB. (Bản dịch sơ bộ, chờ hiệu đính)

> Ghi chú học tập cá nhân, không phải tư vấn thuế. Nguồn: *Veritas Software Corp. v. Commissioner*, 133 T.C. 297 (2009); IRC § 482; Reg. §§ 1.482-1(c), 1.482-7; *Altera* và *Amazon* như dẫn trong văn bản tiếng Trung.

## हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

*Veritas Software Corp. v. Commissioner*, 133 T.C. 297 (2009), § 482 के अंतर्गत लागत-साझाकरण **ख़रीद-प्रवेश भुगतान (buy-in payment)** पर अग्रणी तथ्य-विवाद है। Veritas की आयरिश सहयोगी कंपनी लागत-साझाकरण व्यवस्था में शामिल हुई और उसे पहले से मौजूद प्लेटफ़ॉर्म अमूर्त संपत्तियों के उपयोग-अधिकार का मूल्य चुकाना था; IRS ने उस buy-in का पुनर्मूल्यांकन एक समेकन (aggregation) रंग वाली पद्धति से किया, जिसमें बाद में विकसित तकनीक और व्यवसाय की भावी कमाई-क्षमता तक समेट ली गई, और आँकड़ा लगभग **$2.5 अरब** के स्तर पर पहुँचा (अनुमानित; निर्णय देखें)। कर न्यायालय ने इसे ठुकरा दिया: buy-in केवल उन्हीं प्लेटफ़ॉर्म अमूर्त संपत्तियों को ख़रीदता है जो व्यवस्था की शुरुआत में मौजूद थीं, क्योंकि बाद के R&D के फल वार्षिक लागत-हिस्सों से पहले ही चुकाए जा चुके हैं, और बाद की व्यावसायिक सफलता को हस्तांतरण-तिथि के मूल्य में पीछे की ओर नहीं उड़ेला जा सकता। Reg. § 1.482-1(c) के **सर्वोत्तम विधि नियम (best method rule)** के तहत न्यायालय ने तुलनीय सॉफ़्टवेयर के वास्तविक तृतीय-पक्ष लाइसेंसों से जुड़ी तुलनीय अनियंत्रित लेनदेन (CUT) विधि को, मूल्यांकन के विषय को ही बदल देने वाले समेकन से अधिक विश्वसनीय माना, और buy-in को लगभग **$895 मिलियन** (अनुमानित) पर पुनः निर्धारित किया। परिमाण जाँच: 2,500 − 895 = 1,605, अर्थात IRS के आँकड़े में लगभग 64.2% की कमी; और शुद्ध दृष्टांत उदाहरण में, 1,000 की बिक्री पर 15% की समायोजित CUT दर से वार्षिक आधार 150 बनता है, जबकि समेकन से 400 — 250 का अंतर विषय को बड़ा करने से आता है, तकनीक के अधिक मूल्यवान होने से नहीं।

पड़ोसी मामलों से न मिलाएँ। *Altera* **एक विनियम की वैधता** के बारे में है (क्या स्टॉक-आधारित मुआवज़ा लागत-साझाकरण पूल में डालना होगा — एक प्रशासनिक-कानून विवाद), जबकि Veritas इस बारे में है कि **इन तथ्यों पर कौन-सी मूल्यांकन विधि सबसे विश्वसनीय है**। *Amazon* इसी परिवार का तथ्य-विवाद है: IRS के समेकन की वही अस्वीकृति, जिसमें Veritas स्रोत मामला है और Amazon बाद की पुष्टि। युग का ध्यान भी रखें: दोनों मामले अपने वर्षों की विनियामक व्यवस्था के तहत तय हुए थे; लागत-साझाकरण विनियम 2009 के आसपास संशोधित हुए और 2017 के कर सुधार ने § 482 में समग्र मूल्यांकन की वैधानिक भाषा जोड़ी, इसलिए लागू संस्करण जांचे बिना मामले को आज की व्यवस्था पर नहीं चढ़ाया जा सकता। कैलिफ़ोर्निया में राज्य-स्तरीय buy-in न्यायशास्त्र नहीं है; संबंधित-पक्ष आवंटन समायोजन राज्य राजस्व व कराधान संहिता § 24725 और वर्तमान FTB मार्गदर्शन से चलते हैं। (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

> व्यक्तिगत अध्ययन नोट; कर सलाह नहीं। स्रोत: *Veritas Software Corp. v. Commissioner*, 133 T.C. 297 (2009); IRC § 482; Reg. §§ 1.482-1(c), 1.482-7; चीनी पाठ में उद्धृत *Altera* और *Amazon*।


## 补译增量（2026-11-09 18:55轮）

本节为存量补译增量：韩／越／印三语各补 2 项此前译文未覆盖、只取中文主文已有事实的细节（第 367 条 d 款与周期性调整的独立通道边界、法院在 CUT 框架内自行重算且调减不等于原价全对），原有段落未删改。

### 한국어 — 보충 번역 증분 (초역, 교정 대기 중)

- § 367(d) 및 주기적 조정과의 경계(제2절 보충): 슈퍼 로열티와 주기적 조정에는 각자의 법정 및 규정상 통로가 있어서, IRS는 그 요건을 갖추지 못한 채 집계 평가를 우회로 삼아 같은 효과를 만들어 낼 수 없습니다. 통로는 통로이고, 방법은 방법입니다.
- 법원이 CUT 틀 안에서 다시 계산했다는 점(제5절 요점 보충): IRS의 조정이 대폭 깎였다고 해서 납세자가 제시한 원래 가격이 전부 옳았다는 뜻은 아닙니다. 법원은 CUT 틀 안에서 스스로 조정과 취사선택을 거쳐 매입 지급금을 다시 정한 것입니다.

### Tiếng Việt — phần dịch bổ sung (bản dịch sơ bộ, chờ hiệu đính)

- Ranh giới với § 367(d) và điều chỉnh định kỳ (bổ sung cho phần về giới hạn đối tượng): tiền bản quyền siêu mức (super royalty) và điều chỉnh định kỳ có kênh luật định và quy định riêng của chúng; IRS không thể, khi chưa đáp ứng các điều kiện của những kênh đó, mượn định giá gộp để đi đường vòng đạt cùng một hiệu quả. Kênh thuộc về kênh, phương pháp thuộc về phương pháp.
- Tòa tự tính lại trong khung CUT (bổ sung cho phần điểm chính): việc điều chỉnh của IRS bị cắt giảm mạnh không có nghĩa là mức giá ban đầu của người nộp thuế hoàn toàn đúng; tòa đã tự thực hiện các điều chỉnh và lựa chọn trong khung CUT để xác định lại con số.

### हिन्दी — पूरक अनुवाद वृद्धि (प्रारंभिक अनुवाद, समीक्षा लंबित)

- § 367(d) और आवधिक समायोजन से सीमा (विषय-सीमा वाले भाग का पूरक): सुपर रॉयल्टी और आवधिक समायोजन के अपने वैधानिक और विनियामक मार्ग हैं; IRS उन मार्गों की शर्तें पूरी किए बिना समेकन मूल्यांकन को चक्करदार रास्ता बनाकर वही प्रभाव पैदा नहीं कर सकता। मार्ग अपनी जगह है, विधि अपनी जगह।
- न्यायालय ने CUT ढाँचे के भीतर स्वयं पुनर्गणना की (मुख्य बिंदुओं का पूरक): IRS के समायोजन में भारी कटौती का अर्थ यह नहीं है कि करदाता का मूल मूल्य पूरी तरह सही था; न्यायालय ने CUT ढाँचे के भीतर स्वयं समायोजन और चयन करके आँकड़ा फिर से निर्धारित किया।
