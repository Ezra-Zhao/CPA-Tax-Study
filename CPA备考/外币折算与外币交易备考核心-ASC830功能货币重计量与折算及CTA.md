# 外币折算与外币交易备考核心：ASC 830 功能货币、重计量与折算及 CTA

> 个人学习笔记，不构成税务或审计建议。本文以 ASC 830（Foreign Currency Matters）现行框架为准，写于 2026 年 10 月；考试以 AICPA 当期 CPA Exam Blueprints 为准。

## 中文主文

### 一、先分清三件事：记账货币、功能货币、报告货币

- **记账货币（books of record）**：子公司日常记账用的货币，常是当地货币。
- **功能货币（functional currency）**：该经营主体主要经济环境中的货币——它主要产生与支出哪种货币的现金，它就是哪种功能货币（ASC 830-10-45-2）。
- **报告货币（reporting currency）**：母公司合并报表呈现用的货币（美国母公司通常是美元）。
- **考场第一刀**：功能货币＝报告货币时只剩**外币交易**问题；功能货币≠报告货币时才有**折算（translation）**；当地货币≠功能货币时先**重计量（remeasurement）**再谈折算。顺序错了整题错。

### 二、功能货币怎么判定：830 的指标清单

ASC 830-10-55-5 给六组指标，互相矛盾时靠管理层判断哪组更能反映主要经济环境：

1. **现金流指标**：经营现金流主要以该货币取得、且不直接影响母公司现金流的，指向当地货币。
2. **销售价格指标**：售价主要由当地竞争与法规决定、短期不受汇率影响的，指向当地货币；售价随汇率即时调整的指向美元。
3. **销售市场指标**：产品主要在当地有活跃市场的指向当地货币。
4. **费用指标**：劳工、材料等成本主要在当地发生的指向当地货币。
5. **融资指标**：融资主要以当地货币、靠自身现金流偿还的指向当地货币；靠母公司输血的指向美元。
6. **内部交易指标**：与母公司交易量大、关系密的指向美元；相对独立的指向当地货币。

功能货币一经确定，除非经济事实发生重大变化，不得随意更换（变更按未来适用处理）。

### 三、外币交易：买卖那一刻起就盯着汇率走

- **初始确认**：以外币计价的交易按交易日即期汇率折成记账货币入账。
- **后续计量（ASC 830-20-35-1）**：外币货币性项目（应收、应付、借款）在资产负债表日按现行汇率重估，**汇兑差额进当期损益**；非货币性项目（如预付、存货成本基础）留在历史汇率，不重估。
- **算例**：美国公司以赊销方式卖出商品，应收 €10,000，交易日汇率 €1＝$1.10，记收入 $11,000。年末汇率升到 1.12，应收重估为 $11,200，确认汇兑**收益 $200** 进损益。次年收款时汇率跌到 1.09，实收 $10,900，自年末账面 $11,200 确认汇兑**损失 $300**。三段：11,000 → 11,200（+200）→ 10,900（−300），全程走损益，不进 OCI。

### 四、折算（translation）：功能货币≠报告货币时走时态之外的方法

- **现行汇率法（current rate method）**：资产与负债按资产负债表日**现行汇率**折算；收入费用按发生时汇率、实务上用**加权平均汇率**；股本等权益按**历史汇率**。
- **差额去哪**：折算差额不进损益，进**其他综合收益（OCI）**，累积在权益里单列为累计折算调整（cumulative translation adjustment, CTA，属 AOCI）。
- **CTA 何时释放**：出售或实质完全清算该境外经营时，CTA 转入损益（ASC 830-30-40-1）；部分出售按规则按比例或视控制权丧失与否处理，是高频考点。
- **算例**：欧洲子公司设立时投入资本 €300,000，当时汇率 €1＝$1.00，权益历史口径 $300,000；年末子公司净资产仍为 €300,000，年末汇率升到 1.12，折算后净资产 $336,000。多出的 **$36,000 就是贷方 CTA**，进 OCI 而不是利润——子公司一欧元没多赚，纯粹是汇率把美元口径撑大了。

### 五、重计量（remeasurement）：当地货币≠功能货币时的时态法

- **时态法（temporal method）**：货币性项目按**现行汇率**，非货币性项目按**历史汇率**，与非货币项目相关的收入费用（如折旧、销售成本）按历史汇率、其余按平均汇率。
- **差额去哪**：重计量差额**进当期损益**（与折算进 OCI 正相反——这是 CPA 最爱设的对比陷阱）。
- **典型场景**：境外子公司处在以美元为真实经济锚的环境（如销售、融资全走美元），或身处高通胀经济（见下条），先把当地账重计量成功能货币，再（如功能≠报告）折算。

### 六、两个特殊口袋

- **高通胀经济（highly inflationary）**：三年累计通胀约 100% 或以上时（ASC 830-10-45-11），该经济体子公司的功能货币**视为报告货币（美元）**处理——即用重计量而非折算，差额进损益，避免资产在通胀里「折没了」。
- **内部往来**：具长期投资性质的公司间外币贷款（不预计在可预见未来结算的），其汇兑差额随 CTA 进 OCI；普通经营性往来差额进损益。

### 七、一张对照表收尾

| 情形 | 方法 | 汇率 | 差额去向 |
|---|---|---|---|
| 外币交易（单笔买卖借贷） | — | 交易日入账、货币性项目现行汇率重估 | 损益 |
| 当地≠功能货币 | 重计量（时态法） | 货币性现行、非货币性历史 | 损益 |
| 功能≠报告货币 | 折算（现行汇率法） | 资产负债现行、损益平均、权益历史 | OCI（CTA） |

---

## English

### Foreign Currency Translation and Transactions (ASC 830): Functional Currency, Remeasurement, Translation, and CTA

- **Three currencies, in order.** Books of record (day-to-day bookkeeping), the **functional currency** (currency of the primary economic environment, ASC 830-10-45-2), and the reporting currency. If functional = reporting, only foreign-currency *transactions* remain; if local ≠ functional, **remeasure first**; if functional ≠ reporting, **translate**.
- **Indicators (ASC 830-10-55-5).** Cash flows, sales prices, sales markets, expenses, financing, and intercompany transactions: locally driven indicators point to the local currency; parent-driven indicators point to the dollar. Once set, the functional currency changes only when economic facts change materially.
- **Transactions (ASC 830-20-35-1).** Record at the spot rate on the transaction date. Monetary items are revalued at the current rate each balance-sheet date with gains and losses **in net income**; nonmonetary items stay at historical rates. Example: a €10,000 receivable booked at 1.10 ($11,000) is revalued to $11,200 at 1.12 (gain $200 in income) and settled at 1.09 for $10,900 (loss $300 in income).
- **Translation (current rate method).** Assets and liabilities at the closing rate; revenues and expenses at weighted-average rates; equity at historical rates. The plug is the **cumulative translation adjustment (CTA) in OCI**, released into income only on sale or substantially complete liquidation of the foreign entity (ASC 830-30-40-1). Example: a subsidiary capitalized at €300,000 when the rate was 1.00 ($300,000) still has €300,000 of net assets at year-end, when the rate is 1.12 — translated net assets are $336,000 and the **$36,000 credit CTA sits in OCI, not profit**.
- **Remeasurement (temporal method).** Monetary items at current rates, nonmonetary items at historical rates, and the **remeasurement gain or loss goes to net income** — the mirror image of translation, and the classic exam trap.
- **Special pockets.** In a highly inflationary economy (cumulative three-year inflation of roughly 100% or more, ASC 830-10-45-11), the functional currency is treated as the reporting currency, so remeasurement applies. Exchange differences on long-term, investment-nature intercompany loans go to CTA; ordinary intercompany balances go to income.

*Personal study notes only; not tax or audit advice.*

## Español

### Conversión de moneda extranjera (ASC 830): moneda funcional, remedición, conversión y CTA

- **Tres monedas en orden.** Moneda de registro, **moneda funcional** (la del entorno económico principal, ASC 830-10-45-2) y moneda de presentación. Si la funcional coincide con la de presentación, solo quedan las *transacciones* en moneda extranjera; si la local difiere de la funcional, primero se **remide**; si la funcional difiere de la de presentación, se **convierte**.
- **Indicadores (ASC 830-10-55-5).** Flujos de efectivo, precios de venta, mercados, gastos, financiación y operaciones intercompañía: lo determinado localmente apunta a la moneda local; lo determinado por la matriz, al dólar.
- **Transacciones (ASC 830-20-35-1).** Se registran al tipo al contado de la fecha. Las partidas monetarias se revalúan al tipo vigente en cada balance y la diferencia va **al resultado**; las no monetarias quedan al tipo histórico. Ejemplo: una cuenta por cobrar de 10.000 € registrada a 1,10 (11.000 $) se revalúa a 11.200 $ con el tipo 1,12 (ganancia de 200 $ en resultados) y se cobra a 1,09 por 10.900 $ (pérdida de 300 $ en resultados).
- **Conversión (método del tipo corriente).** Activos y pasivos al tipo de cierre; ingresos y gastos al tipo medio ponderado; patrimonio al tipo histórico. La diferencia es el **ajuste acumulado por conversión (CTA) en otro resultado integral**, que pasa a resultados solo al vender o liquidar sustancialmente la entidad extranjera (ASC 830-30-40-1). Ejemplo: una filial capitalizada con 300.000 € a 1,00 (300.000 $) mantiene activos netos de 300.000 € al cierre, con el tipo en 1,12: los activos netos convertidos son 336.000 $ y el **CTA acreedor de 36.000 $ queda en el patrimonio, no en el beneficio**.
- **Remedición (método temporal).** Partidas monetarias al tipo corriente y no monetarias al histórico, con la diferencia **en resultados**: la imagen especular de la conversión y la trampa clásica del examen.
- **Casos especiales.** En economías altamente inflacionarias (inflación acumulada de tres años cercana o superior al 100%, ASC 830-10-45-11) la moneda funcional se trata como la de presentación y se aplica la remedición. Las diferencias de préstamos intercompañía de naturaleza de inversión a largo plazo van al CTA; las ordinarias, a resultados.

*Notas personales de estudio; no constituyen asesoría fiscal ni de auditoría. Traducción de estudio, pendiente de revisión nativa.*

## 한국어 (초역, 교정 대기)

### 외화 환산과 외화 거래(ASC 830): 기능통화, 재측정, 환산과 CTA

- **세 가지 통화의 순서.** 기록통화, **기능통화**(주요 경제환경의 통화, ASC 830-10-45-2), 보고통화가 있다. 기능통화와 보고통화가 같으면 외화 *거래* 문제만 남고, 현지통화와 기능통화가 다르면 먼저 **재측정(remeasurement)**, 기능통화와 보고통화가 다르면 **환산(translation)**을 한다.
- **판단 지표(ASC 830-10-55-5).** 현금흐름, 판매가격, 판매시장, 비용, 자금조달, 내부거래 여섯 지표가 현지 요인이 강하면 현지통화를, 모회사 요인이 강하면 달러를 가리킨다.
- **외화 거래(ASC 830-20-35-1).** 거래일 현물환율로 기록하고, 화폐성 항목은 매 결산일 현재환율로 재평가하며 차액은 **당기손익**에 넣는다. 비화폐성 항목은 역사적 환율을 유지한다. 예: 1.10에 기록한 €10,000 채권($11,000)은 1.12가 되면 $11,200로 재평가되어 손익에 이익 $200이 잡히고, 1.09에 회수하면 $10,900이 되어 손실 $300이 손익에 잡힌다.
- **환산(현행환율법).** 자산·부채는 기말환율, 수익·비용은 가중평균환율, 자본은 역사적 환율로 환산한다. 차액은 **기타포괄손익의 누적환산조정(CTA)**으로 가며, 해외사업체를 매각하거나 실질적으로 청산할 때만 손익으로 재분류한다(ASC 830-30-40-1). 예: 환율 1.00일 때 €300,000으로 설립된 자회사의 순자산이 연말에도 €300,000이고 환율이 1.12이면 환산 순자산은 $336,000이며 **$36,000의 대변 CTA는 이익이 아니라 OCI**에 쌓인다.
- **재측정(시간법).** 화폐성은 현재환율, 비화폐성은 역사적 환율을 쓰고 차액은 **당기손익**으로 간다. 환산과 정반대라는 점이 단골 함정이다.
- **특수 규정.** 3년 누적 인플레이션이 약 100% 이상인 고인플레이션 경제에서는 기능통화를 보고통화로 취급해 재측정을 적용한다(ASC 830-10-45-11). 장기 투자성 내부대출의 환산차액은 CTA로, 일반 내부거래 차액은 손익으로 간다.

*개인 학습 노트이며 세무·감사 조언이 아닙니다.*

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

### Chuyển đổi ngoại tệ (ASC 830): tiền tệ chức năng, đo lường lại, chuyển đổi và CTA

- **Ba loại tiền tệ theo thứ tự.** Tiền ghi sổ, **tiền tệ chức năng** (đồng tiền của môi trường kinh tế chính, ASC 830-10-45-2) và tiền tệ báo cáo. Nếu tiền chức năng trùng tiền báo cáo, chỉ còn vấn đề *giao dịch* ngoại tệ; nếu tiền địa phương khác tiền chức năng thì **đo lường lại (remeasurement)** trước; nếu tiền chức năng khác tiền báo cáo thì **chuyển đổi (translation)**.
- **Chỉ dấu phán đoán (ASC 830-10-55-5).** Dòng tiền, giá bán, thị trường bán, chi phí, tài trợ và giao dịch nội bộ: yếu tố địa phương chiếm ưu thế thì chọn tiền địa phương, yếu tố công ty mẹ chiếm ưu thế thì chọn đô la.
- **Giao dịch (ASC 830-20-35-1).** Ghi nhận theo tỷ giá giao ngay ngày giao dịch. Khoản mục tiền tệ được đánh giá lại theo tỷ giá hiện hành mỗi ngày kết sổ, chênh lệch vào **lãi lỗ thuần**; khoản mục phi tiền tệ giữ tỷ giá lịch sử. Ví dụ: khoản phải thu €10.000 ghi ở 1,10 ($11.000) được đánh giá lại thành $11.200 ở 1,12 (lãi $200 vào thu nhập) và thu về ở 1,09 được $10.900 (lỗ $300 vào thu nhập).
- **Chuyển đổi (phương pháp tỷ giá hiện hành).** Tài sản và nợ theo tỷ giá cuối kỳ; doanh thu và chi phí theo tỷ giá bình quân gia quyền; vốn chủ sở hữu theo tỷ giá lịch sử. Phần chênh là **điều chỉnh chuyển đổi lũy kế (CTA) trong thu nhập toàn diện khác**, chỉ chuyển vào lãi lỗ khi bán hoặc thanh lý về cơ bản toàn bộ đơn vị nước ngoài (ASC 830-30-40-1). Ví dụ: công ty con được góp vốn €300.000 khi tỷ giá 1,00 ($300.000), cuối năm tài sản ròng vẫn €300.000 nhưng tỷ giá là 1,12 — tài sản ròng chuyển đổi là $336.000 và **khoản CTA có $36.000 nằm trong OCI, không phải lợi nhuận**.
- **Đo lường lại (phương pháp thời gian).** Khoản tiền tệ theo tỷ giá hiện hành, phi tiền tệ theo tỷ giá lịch sử, chênh lệch vào **lãi lỗ thuần** — hình ảnh phản chiếu của chuyển đổi và là cái bẫy kinh điển trong đề thi.
- **Trường hợp đặc biệt.** Trong nền kinh tế siêu lạm phát (lạm phát lũy kế ba năm khoảng 100% trở lên, ASC 830-10-45-11), tiền chức năng được coi như tiền báo cáo và áp dụng đo lường lại. Chênh lệch tỷ giá của khoản vay nội bộ dài hạn mang tính đầu tư vào CTA; khoản vay nội bộ thông thường vào thu nhập.

*Ghi chép học tập cá nhân, không phải tư vấn thuế hay kiểm toán.*

## हिन्दी (प्रारंभिक अनुवाद, समीक्षा लंबित)

### विदेशी मुद्रा रूपांतरण (ASC 830): कार्यात्मक मुद्रा, पुनर्मापन, अनुवाद और CTA

- **तीन मुद्राएँ, क्रम से।** अभिलेख मुद्रा, **कार्यात्मक मुद्रा** (प्राथमिक आर्थिक परिवेश की मुद्रा, ASC 830-10-45-2) और रिपोर्टिंग मुद्रा। यदि कार्यात्मक और रिपोर्टिंग एक ही हों, तो केवल विदेशी-मुद्रा *लेन-देन* का प्रश्न रहता है; यदि स्थानीय मुद्रा कार्यात्मक से भिन्न हो तो पहले **पुनर्मापन (remeasurement)**, और यदि कार्यात्मक रिपोर्टिंग से भिन्न हो तो **अनुवाद (translation)** होता है।
- **संकेतक (ASC 830-10-55-5).** नकदी प्रवाह, बिक्री मूल्य, बिक्री बाज़ार, व्यय, वित्तपोषण और अंतर्कंपनी लेन-देन: स्थानीय कारक मज़बूत हों तो स्थानीय मुद्रा, मूल कंपनी के कारक मज़बूत हों तो डॉलर।
- **लेन-देन (ASC 830-20-35-1).** लेन-देन की तिथि की हाज़िर दर से दर्ज करें। मौद्रिक मदों का प्रत्येक तुलन-पत्र तिथि पर वर्तमान दर से पुनर्मूल्यांकन होता है और अंतर **शुद्ध आय** में जाता है; गैर-मौद्रिक मदें ऐतिहासिक दर पर रहती हैं। उदाहरण: 1.10 पर दर्ज €10,000 की प्राप्य राशि ($11,000) 1.12 पर $11,200 हो जाती है (आय में $200 लाभ) और 1.09 पर $10,900 में वसूल होती है (आय में $300 हानि)।
- **अनुवाद (वर्तमान दर विधि)।** संपत्ति व देयताएँ समापन दर पर, आय व व्यय भारित औसत दर पर, इक्विटी ऐतिहासिक दर पर। अंतर **अन्य व्यापक आय में संचित अनुवाद समायोजन (CTA)** है, जो विदेशी इकाई की बिक्री या सारतः पूर्ण परिसमापन पर ही आय में जाता है (ASC 830-30-40-1)। उदाहरण: 1.00 की दर पर €300,000 से स्थापित सहायक कंपनी की शुद्ध संपत्ति वर्षांत में भी €300,000 है, पर दर 1.12 हो गई — अनूदित शुद्ध संपत्ति $336,000 होगी और **$36,000 का क्रेडिट CTA लाभ में नहीं, OCI में** रहेगा।
- **पुनर्मापन (सामयिक विधि)।** मौद्रिक मदें वर्तमान दर पर, गैर-मौद्रिक ऐतिहासिक दर पर, और अंतर **शुद्ध आय** में — अनुवाद की ठीक उलटी तस्वीर, परीक्षा का प्रिय जाल।
- **विशेष स्थितियाँ।** अति-मुद्रास्फीति अर्थव्यवस्था (तीन वर्ष की संचित मुद्रास्फीति लगभग 100% या अधिक, ASC 830-10-45-11) में कार्यात्मक मुद्रा को रिपोर्टिंग मुद्रा माना जाता है और पुनर्मापन लागू होता है। दीर्घकालिक निवेश-स्वरूप अंतर्कंपनी ऋणों के विनिमय अंतर CTA में, सामान्य अंतर्कंपनी शेष आय में जाते हैं।

*यह व्यक्तिगत अध्ययन नोट है; कर या अंकेक्षण सलाह नहीं है।*

---

**声明**：个人学习笔记，不构成法律、税务或医疗建议。具体事务请咨询持牌专业人士。
