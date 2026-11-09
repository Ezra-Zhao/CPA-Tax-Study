# 建设期利息备考核心：GASB 89 的费用化、受管制例外及加州口径

> 个人学习笔记，不构成税务或会计建议。准则以 GASB Statement No. 89, Accounting for Interest Cost Incurred before the End of a Construction Period（2018 年 6 月发布）现行文本为准。Personal study notes, not tax or accounting advice.

## 中文主文

### 一、一句话规则：建设期利息不再进资产成本

备考时先把旧脑子关掉。企业会计里，符合条件的建设期利息要资本化进资产成本（FASB ASC 835-20）；州与地方政府在 GASB 第 89 号公告之前，走的也是类似路子——经 GASB 第 62 号公告纳入的旧规则要求，在经济资源计量焦点（economic resources measurement focus）下，把建设期利息按可避免利息（avoidable interest）的口径资本化。GASB 89 把这条路整个拆了：在经济资源计量焦点编制的报表中，建设期结束前发生的利息成本，应当在发生期间确认为费用（expense），不得作为资本资产历史成本的一部分资本化。就这一句，没有可避免利息的计算，没有资本化期间的起止判断，也没有特定借款与一般借款的加权平均利率。考试题里只要主体是州或地方政府、问建设期利息去向，答案先落费用，再看有没有第二节那条例外。

为什么改？GASB 给的理由是简化与可比：资本化利息让两座造价相同的设施，只因融资方式不同就报出不同的资产成本，信息的可比性与决策有用性都打折；费用化之后，借款成本回到期间成本的位置，资产成本只装建造本身的成本。代价也要说清：建设期当年的费用会变高、净资产会变低，这不是算错，是准则故意要的效果。

### 二、唯一要紧的例外：受管制运营记管制性资产，不是记回资产成本

GASB 89 没有动 GASB 62 的受管制运营（regulated operations）会计。满足 GASB 62 受管制运营条件、且选择适用其相关条款的主体（典型是费率受监管的公用事业），为费率制定目的资本化的合格利息，仍可按 GASB 62 第 485 段一带的老口径处理——但落点变了：资本化的金额记作一项单独的管制性资产（regulatory asset），通过未来费率回收，不并入在建工程或固定资产的历史成本。答题时把这三层分清：一般政府与企业型活动，费用化；受管制运营且满足条件，管制性资产；把利息塞回资产成本，在 GASB 89 之后两种情形下都不对。受管制例外是窄门，别把「这家水厂收费」直接等同于满足 GASB 62 的全部受管制条件，费率须由独立监管者或自身有权机构按收回成本的口径制定等要件仍要逐项对。

### 三、计量焦点分流：政府基金本来就不资本化

GASB 89 的主战场只在经济资源焦点：政府层面报表中的政府活动列、企业基金与其他企业型活动、以及用全权责发生制的受托活动。流动财务资源计量焦点（current financial resources measurement focus）下的政府基金（普通基金、资本项目基金等）本来就不把建设期利息资本化进资产——基金报表里根本不报资本资产，利息到期时按政府基金会计原则确认支出（expenditure）。所以同一笔建设借款，政府基金层面的处理在新旧准则下没有变化，变化只发生在政府层面报表与企业型基金的报表里。题目给出基金层面的数字问变化，答「不变」往往才是对的，这是 GASB 89 最爱设的静默陷阱。

### 四、生效与过渡：未来适用，不重述，老资本化利息不吐出来

GASB 89 原定适用于 2019 年 12 月 15 日之后开始的报告期；GASB 第 95 号公告因疫情整体顺延一年，现行生效口径为 2020 年 12 月 15 日之后开始的报告期，鼓励提前适用。加州政府普遍以 6 月 30 日为财年末，首个适用年度就是截至 2022 年 6 月 30 日的财年（2021 年 7 月 1 日开始）。过渡只用未来适用（prospective）：生效日之前已经资本化进资产成本的建设期利息，留在资产成本里继续折旧，不追溯剔除、不重述前期报表；只有适用期开始之后发生的利息才走费用化。算例与考题若跨生效日，先把利息按发生期切开，前段老口径、后段新口径，不要一刀切。

### 五、贯穿算例（虚构教学例，数字已本地两遍复算）

某市企业基金（自来水事业，非受管制运营情形）新建水厂：建造支出 10,000,000 美元（不含利息），建设期内实际发生利息 600,000 美元，按旧规则计算的可避免利息为 450,000 美元，资产预计使用 30 年、直线折旧、无残值。

- 旧口径（GASB 89 之前）：资本化额取实际利息与可避免利息两者较小者，即 450,000 美元；在建工程与完工资产成本为 10,000,000＋450,000＝10,450,000 美元；当期费用只剩 600,000－450,000＝150,000 美元。
- GASB 89 口径：600,000 美元全额在发生期确认为费用；资产成本就是 10,000,000 美元，一分利息不进。
- 两口径勾稽：首年费用差 450,000 美元（新口径多记 450,000）；资产成本差 450,000 美元；此后每年折旧差 450,000÷30＝15,000 美元（新口径每年少提 15,000），450,000 的总差额在 30 年里通过折旧逐年找平，数字闭合。
- 换成政府基金（资本项目基金）再算一遍：当期到期利息若为 200,000 美元，新旧口径下都按到期确认 200,000 美元支出，差额为零——计量焦点不同，结论不同。
- 换成满足 GASB 62 条件的受管制公用事业：假设为费率目的资本化的合格利息为 300,000 美元，则记管制性资产 300,000 美元，随费率回收期摊销，既不进当期费用全额、也不进资产成本。

### 六、与 FASB 的分岔，以及加州口径

这是 GASB 近年少有的、明知与 FASB 不同仍故意分岔的准则：非政府主体在 ASC 835-20 下继续资本化符合条件的利息，政府主体在 GASB 89 下费用化。合并报表或双轨报告的实务里，同一工程在两套报表里资产成本可以合法地差出一笔资本化利息，答题与做账都先问主体归谁管（GASB 还是 FASB），再谈数字。加州一侧没有另设州版规则：州与地方政府在年度综合财务报告（ACFR）中执行 GASB 89，加州主计长办公室（State Controller's Office）的报表指引按 GASB 公告口径走；实务核对点只有两个——附注里建设期利息政策是否已切换到费用化表述，以及生效前资本化的存量利息是否仍在资产成本中正常折旧（应当在，不要误以为要冲回）。

### 七、备考清单

1. 主规则：经济资源焦点下，建设期利息发生期费用化，不进资本资产历史成本；
2. 例外只有一个方向：满足 GASB 62 受管制运营条件者，资本化金额记管制性资产，不记回资产成本；
3. 政府基金（流动财务资源焦点）新旧无变化，利息到期作支出；
4. 生效：经 GASB 95 顺延后为 2020 年 12 月 15 日后开始的报告期；加州首个适用财年截至 2022 年 6 月 30 日；
5. 过渡未来适用：存量已资本化利息不重述、不剔除；
6. 与 FASB ASC 835-20 分岔是考点本身，先分准则主体再算数字；
7. 算例锚点：600,000 全额费用对旧口径资本化 450,000、费用 150,000，资产差 450,000、年折旧差 15,000。

*个人学习笔记，不构成税务建议。依据：GASB Statement No. 89（2018 年 6 月）、GASB Statement No. 95 顺延口径、GASB Statement No. 62 受管制运营条款及 GASB 官方摘要，Baker Tilly 等机构对受管制例外的解读作交叉核对。算例已经两遍复算：600,000－450,000＝150,000；10,000,000＋450,000＝10,450,000；450,000÷30＝15,000。*

---

## English

**Construction-period interest for the CPA exam: GASB 89 expensing, the regulated-operations exception, and California.** GASB Statement No. 89, *Accounting for Interest Cost Incurred before the End of a Construction Period* (issued June 2018), abolishes interest capitalization for state and local governments. In financial statements prepared using the economic resources measurement focus, interest cost incurred before the end of a construction period is recognized as an expense in the period incurred and is **not** capitalized as part of the historical cost of a capital asset — no avoidable-interest computation, no capitalization period, no weighted-average rate. The one surviving side door is regulated operations: a government that meets the GASB 62 regulated-operations criteria and applies those provisions may still capitalize qualifying interest for rate-making purposes, but the amount is reported as a separate **regulatory asset** recovered through future rates, never as part of the asset's cost. In governmental funds (current financial resources focus) nothing changes: interest is an expenditure when due, before and after Statement 89. After the one-year GASB 95 postponement, the statement is effective for reporting periods beginning after December 15, 2020 — for California's June 30 year-end governments, the fiscal year ended June 30, 2022 — applied prospectively, so interest capitalized before adoption stays in asset cost and keeps depreciating.

Worked example (fictional, recomputed twice): an enterprise fund builds a plant for $10,000,000 excluding interest; actual interest incurred during construction is $600,000 and avoidable interest under the old rules is $450,000, with a 30-year life. Under the old rules the fund capitalized the lesser amount, $450,000, reported an asset of $10,450,000, and expensed only $150,000. Under GASB 89 it expenses the full $600,000 and reports a $10,000,000 asset: first-year expense is $450,000 higher, the asset is $450,000 lower, and annual depreciation is $450,000 ÷ 30 = $15,000 lower thereafter. The deliberate split from FASB ASC 835-20, which still requires capitalization for nongovernmental entities, is itself a favorite exam point: identify the standard-setter before computing anything. *Personal study notes only; not tax advice.*

## Español (traducción de estudio · 初译待校)

**Intereses del período de construcción para el examen CPA: gasto inmediato según el GASB 89, excepción de operaciones reguladas y criterio de California.** La Declaración n.º 89 del GASB, *Accounting for Interest Cost Incurred before the End of a Construction Period* (junio de 2018), elimina la capitalización de intereses para los gobiernos estatales y locales. En los estados preparados con el enfoque de medición de recursos económicos, el interés incurrido antes del fin del período de construcción se reconoce como gasto del período y **no** se capitaliza como parte del costo histórico del activo: sin cálculo de interés evitable, sin período de capitalización y sin tasa promedio ponderada. La única puerta lateral es la de operaciones reguladas: quien cumple los criterios de operaciones reguladas del GASB 62 puede seguir capitalizando el interés calificado a efectos de tarifas, pero como un **activo regulatorio** separado, recuperable vía tarifas futuras, nunca como costo del activo. En los fondos gubernamentales (enfoque de recursos financieros corrientes) nada cambia: el interés es gasto presupuestario al vencimiento, antes y después. Tras la prórroga de un año del GASB 95, la vigencia es para períodos iniciados después del 15 de diciembre de 2020 —en California, con cierre al 30 de junio, el ejercicio terminado el 30 de junio de 2022— con aplicación prospectiva: el interés capitalizado antes de la adopción permanece en el costo del activo.

Ejemplo (ficticio, recalculado dos veces): un fondo empresarial construye una planta por 10.000.000 de dólares sin intereses; el interés real del período es 600.000 y el evitable, 450.000, con vida útil de 30 años. Con la regla antigua capitalizaba 450.000, el activo era 10.450.000 y el gasto, solo 150.000. Con el GASB 89 gasta los 600.000 completos y el activo queda en 10.000.000: el gasto del primer año sube 450.000 y la depreciación anual baja 450.000 ÷ 30 = 15.000. La divergencia deliberada frente al ASC 835-20 del FASB, que sigue exigiendo capitalizar, es en sí misma un punto de examen. *Notas personales de estudio; no constituye asesoría fiscal. Traducción de estudio, pendiente de revisión.*

## 한국어 (초역 · 初译待校)

**CPA 대비 건설기간 이자: GASB 89의 비용화, 규제 운영 예외, 캘리포니아 기준.** GASB 제89호(건설기간 종료 전 발생한 이자비용 회계, 2018년 6월 발표)는 주·지방정부의 이자 자본화를 폐지했습니다. 경제적 자원 측정초점으로 작성하는 재무제표에서는 건설기간 종료 전에 발생한 이자비용을 발생한 기간의 비용으로 인식하고 자본자산의 역사적 원가에 자본화하지 않습니다. 회피가능이자 계산도, 자본화 기간도, 가중평균 이자율도 없습니다. 살아남은 유일한 옆문은 규제 운영입니다. GASB 62의 규제 운영 요건을 충족하고 관련 규정을 적용하는 정부는 요금 산정 목적의 적격 이자를 계속 자본화할 수 있지만, 그 금액은 자산 원가가 아니라 미래 요금으로 회수하는 별도의 규제자산으로 보고합니다. 정부기금(유동 재무자원 초점)에서는 달라지는 것이 없습니다. 이자는 만기 시 지출이며 제89호 전후가 같습니다. GASB 95로 1년 연기된 후 시행일은 2020년 12월 15일 이후 시작하는 보고기간부터이며, 6월 30일 결산인 캘리포니아 정부는 2022년 6월 30일 종료 연도가 첫 적용 연도이고, 전진 적용이라 도입 전에 자본화된 이자는 자산 원가에 남아 계속 상각됩니다.

산례(가상의 교습 예시, 두 번 재계산): 기업기금이 이자 제외 10,000,000달러로 시설을 짓고, 건설기간 실제 이자는 600,000달러, 구 규칙의 회피가능이자는 450,000달러, 내용연수 30년입니다. 구 규칙에서는 적은 쪽인 450,000달러를 자본화해 자산이 10,450,000달러, 비용은 150,000달러만 남았습니다. GASB 89에서는 600,000달러 전액을 비용 처리하고 자산은 10,000,000달러입니다. 첫해 비용이 450,000달러 늘고 자산은 450,000달러 줄며, 이후 연 감가상각은 450,000÷30=15,000달러씩 줄어듭니다. 자본화를 계속 요구하는 FASB ASC 835-20과의 의도적 분기 자체가 단골 출제 포인트입니다. *개인 학습 노트이며 세무 자문이 아닙니다. 초역으로 원어민 감수 대기 중입니다.*

## Tiếng Việt (bản dịch sơ bộ · 初译待校)

**Lãi trong giai đoạn xây dựng cho kỳ thi CPA: GASB 89 hạch toán chi phí ngay, ngoại lệ hoạt động chịu quản lý, và quy tắc California.** Chuẩn mực GASB số 89, *Accounting for Interest Cost Incurred before the End of a Construction Period* (ban hành tháng 6 năm 2018), bãi bỏ việc vốn hóa lãi vay đối với chính quyền bang và địa phương. Trong báo cáo lập theo trọng tâm đo lường nguồn lực kinh tế, chi phí lãi phát sinh trước khi kết thúc giai đoạn xây dựng được ghi nhận là chi phí của kỳ phát sinh và **không** được vốn hóa vào nguyên giá tài sản: không tính lãi tránh được, không xác định giai đoạn vốn hóa, không dùng lãi suất bình quân gia quyền. Cửa ngách duy nhất còn lại là hoạt động chịu quản lý (regulated operations): đơn vị đáp ứng tiêu chí của GASB 62 có thể tiếp tục vốn hóa phần lãi đủ điều kiện cho mục đích định giá phí, nhưng khoản đó được báo cáo là một **tài sản điều tiết** (regulatory asset) riêng, thu hồi qua giá phí tương lai, chứ không nằm trong nguyên giá tài sản. Trong các quỹ chính phủ (trọng tâm nguồn lực tài chính hiện tại) không có gì thay đổi: lãi là khoản chi khi đến hạn, trước và sau Chuẩn mực 89 đều vậy. Sau khi GASB 95 hoãn một năm, chuẩn mực hiệu lực cho các kỳ báo cáo bắt đầu sau ngày 15 tháng 12 năm 2020 — với các chính quyền California kết thúc năm vào 30 tháng 6, năm đầu tiên là năm tài chính kết thúc ngày 30 tháng 6 năm 2022 — và áp dụng hồi tố về sau (prospective): lãi đã vốn hóa trước ngày áp dụng vẫn nằm trong nguyên giá và tiếp tục khấu hao.

Ví dụ (giả định giảng dạy, đã tính lại hai lần): một quỹ doanh nghiệp xây nhà máy 10.000.000 đô la chưa kể lãi; lãi thực tế trong giai đoạn xây dựng là 600.000 đô la, lãi tránh được theo quy tắc cũ là 450.000 đô la, thời gian hữu dụng 30 năm. Theo quy tắc cũ, quỹ vốn hóa 450.000 đô la, tài sản là 10.450.000 đô la và chi phí chỉ 150.000 đô la. Theo GASB 89, quỹ ghi chi phí toàn bộ 600.000 đô la và tài sản là 10.000.000 đô la: chi phí năm đầu cao hơn 450.000 đô la, khấu hao hằng năm thấp hơn 450.000 ÷ 30 = 15.000 đô la. Sự tách ra có chủ ý khỏi ASC 835-20 của FASB — vốn vẫn yêu cầu vốn hóa — tự nó là một điểm thi quen thuộc. *Ghi chú học tập cá nhân, không phải tư vấn thuế. Bản dịch sơ bộ, chờ hiệu đính.*

## हिन्दी (प्रारंभिक अनुवाद · 初译待校)

**CPA परीक्षा के लिए निर्माण-अवधि ब्याज: GASB 89 का व्यय-रूप, विनियमित परिचालन अपवाद और California नियम।** GASB कथन संख्या 89, *Accounting for Interest Cost Incurred before the End of a Construction Period* (जून 2018 में जारी), राज्य व स्थानीय सरकारों के लिए ब्याज-पूँजीकरण समाप्त करता है। आर्थिक संसाधन मापन-केंद्र (economic resources measurement focus) से बने विवरणों में निर्माण-अवधि समाप्त होने से पहले का ब्याज-व्यय उसी अवधि का व्यय माना जाएगा और पूँजीगत संपत्ति के ऐतिहासिक लागत में पूँजीकृत **नहीं** होगा — न परिहार्य ब्याज (avoidable interest) की गणना, न पूँजीकरण अवधि, न भारित-औसत दर। बचा हुआ एकमात्र पार्श्व-द्वार विनियमित परिचालन है: GASB 62 के विनियमित-परिचालन मानदंड पूरे करने वाली सरकार दर-निर्धारण हेतु योग्य ब्याज का पूँजीकरण जारी रख सकती है, परंतु वह राशि संपत्ति-लागत नहीं, भविष्य की दरों से वसूली जाने वाली एक अलग **विनियामक संपत्ति** (regulatory asset) होगी। सरकारी निधियों (वर्तमान वित्तीय संसाधन केंद्र) में कुछ नहीं बदलता: ब्याज देय होने पर व्यय है, कथन 89 से पहले भी और बाद में भी। GASB 95 से एक वर्ष स्थगन के बाद प्रभाव-तिथि 15 दिसंबर 2020 के बाद शुरू होने वाले रिपोर्टिंग काल हैं — 30 जून वर्षांत वाली California सरकारों के लिए पहला वर्ष 30 जून 2022 को समाप्त वित्तीय वर्ष — और अनुप्रयोग भविष्यलक्षी है: अंगीकरण से पहले पूँजीकृत ब्याज संपत्ति-लागत में रहकर मूल्यह्रासित होता रहेगा।

उदाहरण (काल्पनिक शिक्षण उदाहरण, दो बार पुनर्गणित): एक उद्यम निधि ब्याज छोड़कर $10,000,000 में संयंत्र बनाती है; निर्माण-अवधि का वास्तविक ब्याज $600,000 और पुराने नियम से परिहार्य ब्याज $450,000 है, उपयोगी जीवन 30 वर्ष। पुराने नियम में $450,000 पूँजीकृत हुआ, संपत्ति $10,450,000 रही और व्यय केवल $150,000 रहा। GASB 89 में पूरे $600,000 व्यय होंगे और संपत्ति $10,000,000 रहेगी: पहले वर्ष का व्यय $450,000 अधिक, और उसके बाद वार्षिक मूल्यह्रास $450,000 ÷ 30 = $15,000 कम। FASB ASC 835-20 से जानबूझकर किया गया यह विचलन — जो ग़ैर-सरकारी इकाइयों के लिए पूँजीकरण अब भी माँगता है — स्वयं एक परीक्षा-बिंदु है। *व्यक्तिगत अध्ययन नोट; कर सलाह नहीं। प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित।*


## 补译增量（2026-11-08：韩/越/印三语补细节增量至与中文主文对齐，正文原有段落未改动）

### 中文（增量锚点）
增量一（计量焦点分流与政府基金的静默陷阱）：GASB 89 的主战场只在经济资源计量焦点——政府层面报表的政府活动列、企业基金与其他企业型活动、以及全权责发生制的受托活动；流动财务资源计量焦点下的政府基金本来就不把建设期利息资本化进资产，基金报表根本不报资本资产，利息到期时确认支出，所以同一笔建设借款在政府基金层面新旧口径没有变化（算例：当期到期利息 200,000 美元，新旧都确认 200,000 美元支出，差额为零），题目给出基金层面数字问变化时答「不变」往往才是对的。增量二（受管制变体与存量处理）：换成满足 GASB 62 条件的受管制公用事业，为费率目的资本化的合格利息 300,000 美元记管制性资产、随费率回收期摊销，既不进当期费用全额、也不进资产成本；过渡只用未来适用，生效前已资本化进资产成本的存量利息留在资产成本里继续折旧，不追溯剔除、不重述前期报表——附注政策已切换到费用化表述、存量利息仍在正常折旧，是加州 ACFR 的两个实务核对点。

### 한국어 (초역 · 初译待校)
증보 1(측정초점의 갈림과 정부기금의 조용한 함정): GASB 89의 주전장은 경제자원 측정초점뿐입니다——정부 전체 재무제표의 정부활동 열, 기업기금과 그 밖의 기업형 활동, 완전 발생주의 수탁 활동이 그 범위입니다. 유동 재무자원 측정초점의 정부기금은 원래 건설기간 이자를 자산으로 자본화하지 않고, 기금 재무제표에는 자본자산 자체가 보고되지 않으며, 이자는 만기가 됐을 때 지출로 인식합니다. 그래서 같은 건설 차입금이라도 정부기금 층위에서는 신구 기준의 차이가 없습니다(예시: 당기 만기 이자 $200,000는 신구 모두 $200,000 지출로 인식, 차이 0). 문제에서 기금 층위 숫자를 주고 변화를 물으면 답은 '변함없음'인 경우가 많습니다. 증보 2(규제 변형과 기존 잔량 처리): GASB 62의 조건을満た는 규제 공익사업으로 바꾸면, 요금 목적상 자본화된 적격 이자 $300,000은 규제자산으로 기록해 요금 회수 기간에 상각합니다. 당기 비용 전액으로도, 자산 원가로도 들어가지 않습니다. 경과는 미래 적용만 씁니다. 시행 전에 이미 자산 원가에 자본화된 이자는 자산 원가에 남아 계속 감가상각하고, 소급 제거하거나 전기 재무제표를 다시 쓰지 않습니다. 주석 방침이 비용화 표현으로 바뀌었는지, 기존 이자가 여전히 정상 상각 중인지가 캘리포니아 ACFR의 두 가지 실무 확인점입니다.

### Tiếng Việt (bản dịch sơ bộ · 初译待校)
Bổ sung 1 (phân luồng theo trọng tâm đo lường và cái bẫy lặng của quỹ chính phủ): chiến trường chính của GASB 89 chỉ nằm ở trọng tâm đo lường nguồn lực kinh tế — cột hoạt động chính phủ trong báo cáo toàn chính phủ, các quỹ doanh nghiệp và hoạt động kiểu doanh nghiệp khác, cùng hoạt động ủy thác theo cơ sở dồn tích đầy đủ. Quỹ chính phủ theo trọng tâm nguồn lực tài chính hiện hành vốn không vốn hóa lãi xây dựng vào tài sản — báo cáo quỹ căn bản không trình bày tài sản vốn — và lãi được ghi là chi tiêu khi đến hạn, nên cùng một khoản vay xây dựng, ở tầng quỹ chính phủ, cách xử lý cũ và mới không khác nhau (ví dụ: lãi đến hạn trong kỳ $200.000, cả cũ lẫn mới đều ghi chi tiêu $200.000, chênh lệch bằng không); đề bài cho số ở tầng quỹ rồi hỏi thay đổi thì đáp án «không đổi» thường mới đúng. Bổ sung 2 (biến thể chịu quản chế và xử lý tồn đọng): đổi sang một đơn vị công ích chịu quản chế thỏa điều kiện GASB 62, khoản lãi đủ điều kiện vốn hóa vì mục đích giá cước $300.000 được ghi là tài sản quản chế và phân bổ theo kỳ thu hồi qua giá cước — không vào toàn bộ chi phí kỳ này, cũng không vào nguyên giá tài sản. Chuyển đổi chỉ áp dụng tương lai: lãi đã vốn hóa vào nguyên giá trước ngày hiệu lực ở lại trong nguyên giá và tiếp tục khấu hao, không loại trừ hồi tố, không trình bày lại báo cáo kỳ trước; hai điểm kiểm tra thực vụ ở ACFR của California là thuyết minh đã chuyển sang cách diễn đạt phí hóa hay chưa, và lãi tồn đọng còn đang khấu hao bình thường hay không.

### हिन्दी (प्रारंभिक अनुवाद · 初译待校)
वृद्धि 1 (मापन-केंद्र का विभाजन और सरकारी निधि का मौन जाल): GASB 89 का मुख्य क्षेत्र केवल आर्थिक संसाधन मापन-केंद्र है — सरकार-व्यापी विवरणों का सरकारी गतिविधि स्तंभ, उद्यम निधियाँ व अन्य उद्यम-प्रकार गतिविधियाँ, और पूर्ण उपार्जन आधार की न्यासी गतिविधियाँ। चालू वित्तीय संसाधन मापन-केंद्र वाली सरकारी निधियाँ निर्माण-अवधि ब्याज को संपत्ति में पूँजीकृत करती ही नहीं — निधि विवरणों में पूँजीगत संपत्ति रिपोर्ट ही नहीं होती — और ब्याज देय होने पर व्यय के रूप में दर्ज होता है, इसलिए उसी निर्माण ऋण पर निधि-स्तर पर पुरानी और नई पद्धति में कोई अंतर नहीं पड़ता (उदाहरण: अवधि में देय ब्याज $200,000, दोनों पद्धतियों में $200,000 व्यय, अंतर शून्य); प्रश्न निधि-स्तर के अंक देकर परिवर्तन पूछे तो उत्तर प्रायः «कोई परिवर्तन नहीं» होता है। वृद्धि 2 (विनियमित रूपांतर और पुराना शेष): GASB 62 की शर्तें पूरी करने वाली विनियमित उपयोगिता लें तो दर-निर्धारण हेतु पूँजीकृत पात्र ब्याज $300,000 विनियामक संपत्ति के रूप में दर्ज होगा और दर-वसूली अवधि में परिशोधित होगा — न पूरे का पूरा चालू व्यय, न संपत्ति लागत। संक्रमण केवल भविष्य-लक्षी है: प्रभावी तिथि से पहले संपत्ति लागत में पूँजीकृत ब्याज वहीं रहकर मूल्यह्रास पाता रहेगा, न पूर्वव्यापी हटाया जाएगा, न पूर्व विवरण फिर लिखे जाएँगे; California ACFR के दो व्यावहारिक जाँच-बिंदु यही हैं — टिप्पणी नीति व्यय-रूप में बदल गई हो, और पुराना ब्याज सामान्य रूप से मूल्यह्रास पा रहा हो।
