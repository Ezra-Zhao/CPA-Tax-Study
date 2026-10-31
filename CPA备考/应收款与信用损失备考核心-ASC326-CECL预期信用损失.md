# 应收款与信用损失备考核心：ASC 326 与 CECL 预期信用损失模型

> 个人学习笔记，不构成税务或审计建议。本文以 ASC 326（Financial Instruments — Credit Losses）现行框架为准，写于 2026 年 10 月；考试以 AICPA 当期 CPA Exam Blueprints 为准，FAR 与 BAR 均可能涉及。

## 中文主文

### 一、先认模型换代：从「已发生损失」到「当前预期」

- FASB 2016 年以 ASU 2016-13 创设 ASC 326，核心是 CECL（Current Expected Credit Losses，当期预期信用损失）：按摊余成本计量的金融资产，确认时就要按**整个合同期**的预期信用损失计提备抵，不再等损失「已经发生且很可能」才认。
- 生效分层：SEC 申报公司（小型申报公司除外）自 2019-12-15 后开始的财年适用；其余主体经 ASU 2019-10 等递延后，自 2022-12-15 后开始的财年适用。考试问「哪年起」，先看主体类型这一刀。

### 二、范围：326-20 与 326-30 别混

- **ASC 326-20（CECL 本体）**：摊余成本计量的金融资产——持有至投资贷款、持有至到期（HTM）债务证券、应收账款、ASC 606 合同资产、租赁净投资等；表外信用敞口（贷款承诺、备用信用证）另以负债形式计提，不与资产备抵混账。
- **ASC 326-30（可供出售 AFS 债务证券）**：不走 CECL 全周期口径。当公允价值低于摊余成本时先分信用与非信用：信用部分进备抵（以公允价值下限封顶，即备抵不超过摊余成本与公允价值之差），非信用部分进 OCI；有出售意图或很可能被要求在收回前出售的，直接把摊余成本减记到公允价值。
- **范围外**：交易性证券、公允价值选择权资产、待售贷款等不在 326-20 内——看到题目先问计量属性，比先算数字重要。

### 三、怎么估：分组、方法与预测期

- **分组（pooling）**：风险特征相似的资产合并评估（产品类型、账龄、地区、抵押等）；不与他人共享风险特征的单独评估。
- **方法不指定**：折现现金流法、损失率法、滚动率法、违约概率法、账龄分析法都可，关键是口径一致、可支持。
- **信息三件套**：历史损失经验＋当前状况＋对未来的「合理且可支持的预测」；预测期之后的部分回归历史损失信息（reversion）。 Day-1 即计提是常态：新发放贷款或新确认应收款，确认当期就产生信用损失费用——这是 CECL 与旧模型的标志性差别。
- **ASU 2025-05 的实务简便法**：对源于 ASC 606 的当期应收账款与合同资产，FASB 2025 年给了实务权宜——可假设资产负债表日的当前状况在余额存续期内不变；适用于 2025-12-15 后开始的年度期间。知道有这个口子，细则查原文。

### 四、完整算例一：账龄分析法与备抵滚动表

某公司年末应收账款按账龄分组，损失率已综合历史、当前与可支持预测：

| 分组 | 余额 | 损失率 | 备抵 |
|---|---:|---:|---:|
| 未逾期 | 600,000 | 0.5% | 3,000 |
| 逾期 1–30 天 | 250,000 | 2% | 5,000 |
| 逾期 31–60 天 | 100,000 | 5% | 5,000 |
| 逾期 60 天以上 | 50,000 | 20% | 10,000 |
| 合计 | 1,000,000 | — | 23,000 |

- 应收账款净额＝1,000,000 − 23,000＝**977,000**。
- 备抵滚动：期初备抵 18,000，本年核销 4,000，收回已核销款 1,000，则本年信用损失费用＝期末 23,000 − 期初 18,000 ＋ 核销 4,000 − 收回 1,000＝**8,000**。验算：18,000 ＋ 8,000 − 4,000 ＋ 1,000＝23,000，勾稽一致。
- 易错点：核销只同时冲减应收与备抵，不进费用；费用在计提时已经认过。收回已核销款先恢复备抵，也不直接进收入。

### 五、完整算例二：PCD 资产的 gross-up

购入一笔已发生信用减值的贷款（purchased credit-deteriorated, PCD）：未偿本金 1,000,000，买价 800,000，购买日预期信用损失 120,000。

- 初始摊余成本＝买价 800,000 ＋ 初始备抵 120,000＝**920,000**——备抵「加回」到成本里（gross-up），购买日**不确认信用损失费用**，避免把买价里已反映的信用折价再费用化一次（所谓双重计算）。
- 非信用折价＝1,000,000 − 920,000＝**80,000**，在剩余期限内按实际利率法摊入利息收入。
- 对照：非 PCD 的购入贷款走普通口径，初始备抵经信用损失费用确认——同一把尺，PCD 与非 PCD 的 Day-1 处理正相反，这是高频陷阱。

### 六、列报、披露与对照

- 资产按「预期能收回的净额」列示；备抵变动表（rollforward）、信用质量指标、逾期情况、抵押品信息是 326-20-50 的披露主干。
- **与 IFRS 9 对照**：IFRS 用三阶段——信用风险未显著增加时只认 12 个月预期损失，显著增加后才转全周期；US GAAP 的 CECL 不分阶段，确认即全周期。两套都叫「预期损失」，触发时点完全不同，混答必错。

> 个人学习笔记，不构成税务、财务或审计建议。

## English

ASU 2016-13 created ASC 326 and replaced the incurred-loss model with CECL: financial assets at amortized cost carry an allowance for **lifetime** expected credit losses from day one, based on historical experience, current conditions, and reasonable and supportable forecasts, with reversion to historical information beyond the forecast period. CECL took effect for SEC filers (other than smaller reporting companies) for fiscal years beginning after December 15, 2019, and for all other entities after December 15, 2022. **Scope:** ASC 326-20 covers loans held for investment, HTM debt securities, trade receivables, ASC 606 contract assets, and net investments in leases; off-balance-sheet exposures are accrued as a separate liability. AFS debt securities sit in ASC 326-30 instead — the credit portion goes through an allowance capped at the gap between amortized cost and fair value, the non-credit portion goes to OCI. **Pooling and methods** are judgment-based (loss-rate, roll-rate, PD, aging, DCF); ASU 2025-05 added a practical expedient for current receivables and contract assets from ASC 606, effective for annual periods beginning after December 15, 2025.

**Worked example 1 (aging).** Balances of 600,000 / 250,000 / 100,000 / 50,000 at loss rates of 0.5% / 2% / 5% / 20% give an allowance of 3,000 + 5,000 + 5,000 + 10,000 = **23,000**, so net receivables are **977,000** on 1,000,000 gross. Rollforward: beginning 18,000, write-offs 4,000, recoveries 1,000, so credit loss expense = 23,000 − 18,000 + 4,000 − 1,000 = **8,000** (check: 18,000 + 8,000 − 4,000 + 1,000 = 23,000). Write-offs never hit expense; they were expensed when provided. **Worked example 2 (PCD gross-up).** A purchased credit-deteriorated loan with unpaid principal of 1,000,000 bought for 800,000 with expected credit losses of 120,000 starts at amortized cost of 800,000 + 120,000 = **920,000**, with **no day-one expense**, and the noncredit discount of 1,000,000 − 920,000 = **80,000** accreted into interest income. A non-PCD purchased loan does the opposite — day-one allowance through expense. **IFRS 9 contrast:** staged model, 12-month ECL until credit risk increases significantly; CECL is lifetime from recognition, no staging.

*Personal study notes only; not tax, financial, or audit advice.*

## Español (traducción de estudio)

La ASU 2016-13 creó la ASC 326 y sustituyó el modelo de pérdida incurrida por CECL: los activos financieros a costo amortizado llevan desde el primer día una provisión por pérdidas crediticias esperadas de **toda la vida contractual**, con experiencia histórica, condiciones actuales y pronósticos razonables y sustentables. Vigencia: declarantes SEC (salvo emisores pequeños) desde ejercicios iniciados tras el 15 de diciembre de 2019; el resto, tras el 15 de diciembre de 2022. **Ámbito:** la ASC 326-20 cubre préstamos para inversión, deuda HTM, cuentas por cobrar comerciales, activos contractuales de la ASC 606 e inversión neta en arrendamientos; las exposiciones fuera de balance se provisionan como pasivo separado. La deuda AFS va por la ASC 326-30: la parte crediticia por provisión con tope en la diferencia entre costo amortizado y valor razonable, y la no crediticia a OCI. La ASU 2025-05 añadió un expediente práctico para cuentas por cobrar corrientes de la ASC 606, efectivo para períodos anuales iniciados tras el 15 de diciembre de 2025.

**Ejemplo 1 (antigüedad).** Saldos de 600.000 / 250.000 / 100.000 / 50.000 con tasas de 0,5% / 2% / 5% / 20% dan provisión de 3.000 + 5.000 + 5.000 + 10.000 = **23.000**; el neto es **977.000** sobre 1.000.000 brutos. Conciliación: saldo inicial 18.000, castigos 4.000, recuperaciones 1.000, luego el gasto = 23.000 − 18.000 + 4.000 − 1.000 = **8.000**. Los castigos nunca pasan por gasto. **Ejemplo 2 (PCD).** Un préstamo comprado ya deteriorado: capital impago 1.000.000, precio 800.000, pérdidas esperadas 120.000; el costo amortizado inicial es 800.000 + 120.000 = **920.000**, **sin gasto inicial**, y el descuento no crediticio de 1.000.000 − 920.000 = **80.000** se acumula como ingreso por intereses. **Contraste IFRS 9:** modelo por etapas con pérdida de 12 meses hasta que el riesgo aumente significativamente; CECL es de vida completa desde el reconocimiento.

> Notas personales de estudio; no constituyen asesoría fiscal, financiera ni de auditoría.

## 한국어 (초역, 교정 대기)

ASU 2016-13이 만든 ASC 326의 CECL 모델은 상각후원가 금융자산에 대해 발생손실이 아니라 **계약 전 기간**의 기대신용손실을 첫날부터 충당금으로 잡습니다. 과거 손실경험, 현재 상황, 합리적이고 뒷받침 가능한 전망을 함께 쓰고, 전망기간 이후는 과거 정보로 복귀합니다. 시행은 SEC 제출기업(소규모 보고기업 제외)이 2019년 12월 15일 이후 시작 회계연도, 나머지는 2022년 12월 15일 이후 시작 회계연도부터입니다. **범위:** ASC 326-20은 보유 대출, 만기보유 채무증권, 매출채권, ASC 606 계약자산, 리스 순투자를 다룹니다. 매도가능(AFS) 채무증권은 ASC 326-30으로 가서 신용 부분은 상각후원가와 공정가치 차이로 상한이 정해지는 충당금으로, 비신용 부분은 OCI로 처리합니다. ASU 2025-05는 ASC 606에서 생긴 당기 매출채권·계약자산에 실무적 간편법을 추가했습니다(2025년 12월 15일 이후 시작 연차기간 적용).

**예제 1(연령분석).** 잔액 600,000 / 250,000 / 100,000 / 50,000에 손실률 0.5% / 2% / 5% / 20%를 적용하면 충당금은 3,000 + 5,000 + 5,000 + 10,000 = **23,000**, 순 매출채권은 **977,000**입니다. 조정: 기초 18,000, 제각 4,000, 회수 1,000이면 신용손실비용 = 23,000 − 18,000 + 4,000 − 1,000 = **8,000**입니다. 제각은 비용으로 가지 않습니다. **예제 2(PCD gross-up).** 신용이 이미 손상된 매입대출: 미상환 원금 1,000,000, 매입가 800,000, 기대신용손실 120,000이면 최초 상각후원가는 800,000 + 120,000 = **920,000**이고 첫날 비용은 없으며, 비신용 할인 1,000,000 − 920,000 = **80,000**은 이자수익으로 상각합니다. **IFRS 9와 비교:** 단계별 모델로 신용위험이 유의하게 증가하기 전에는 12개월 손실만 잡지만, CECL은 처음부터 전 기간 손실을 잡습니다.

> 개인 학습 노트이며 세무·재무·감사 조언이 아닙니다. (초역, 교정 대기)

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

ASU 2016-13 tạo ra ASC 326 và thay mô hình tổn thất đã phát sinh bằng CECL: tài sản tài chính theo chi phí khấu hao phải trích dự phòng tổn thất tín dụng kỳ vọng cho **toàn bộ thời hạn hợp đồng** ngay từ ngày đầu, dựa trên kinh nghiệm lịch sử, điều kiện hiện tại và dự báo hợp lý, có căn cứ. Hiệu lực: đơn vị khai SEC (trừ công ty báo cáo nhỏ) cho năm tài chính bắt đầu sau ngày 15 tháng 12 năm 2019; các đơn vị khác sau ngày 15 tháng 12 năm 2022. **Phạm vi:** ASC 326-20 gồm khoản vay giữ để đầu tư, chứng khoán nợ HTM, phải thu thương mại, tài sản hợp đồng theo ASC 606 và đầu tư thuần vào thuê; cam kết ngoài bảng cân đối trích riêng thành nợ phải trả. Chứng khoán nợ AFS thuộc ASC 326-30: phần tín dụng qua dự phòng bị chặn ở mức chênh lệch giữa chi phí khấu hao và giá trị hợp lý, phần phi tín dụng vào OCI. ASU 2025-05 bổ sung phương án thực tế đơn giản cho phải thu hiện hành từ ASC 606, áp dụng cho kỳ năm bắt đầu sau ngày 15 tháng 12 năm 2025.

**Ví dụ 1 (tuổi nợ).** Số dư 600.000 / 250.000 / 100.000 / 50.000 với tỷ lệ tổn thất 0,5% / 2% / 5% / 20% cho dự phòng 3.000 + 5.000 + 5.000 + 10.000 = **23.000**; phải thu thuần là **977.000** trên tổng 1.000.000. Đối chiếu: đầu kỳ 18.000, xóa nợ 4.000, thu hồi 1.000, nên chi phí = 23.000 − 18.000 + 4.000 − 1.000 = **8.000**. Xóa nợ không qua chi phí. **Ví dụ 2 (PCD).** Khoản vay mua lại đã suy giảm tín dụng: gốc chưa trả 1.000.000, giá mua 800.000, tổn thất kỳ vọng 120.000; chi phí khấu hao ban đầu là 800.000 + 120.000 = **920.000**, **không có chi phí ngày đầu**, và chiết khấu phi tín dụng 1.000.000 − 920.000 = **80.000** được phân bổ vào thu nhập lãi. **Đối chiếu IFRS 9:** mô hình theo giai đoạn, chỉ 12 tháng cho đến khi rủi ro tín dụng tăng đáng kể; CECL là toàn bộ thời hạn ngay từ đầu.

> Ghi chú học tập cá nhân, không phải tư vấn thuế, tài chính hay kiểm toán. (Bản dịch sơ bộ)

## हिन्दी (प्रारंभिक अनुवाद, समीक्षा लंबित)

ASU 2016-13 ने ASC 326 बनाया और incurred-loss मॉडल की जगह CECL लाया: amortized cost पर मापी वित्तीय संपत्तियों पर पहले दिन से **पूरे अनुबंध-जीवन** के अपेक्षित क्रेडिट नुकसान का भत्ता रखा जाता है — ऐतिहासिक अनुभव, वर्तमान स्थितियों और उचित व समर्थनीय पूर्वानुमान के आधार पर। प्रभाव: SEC फ़ाइलरों (छोटी रिपोर्टिंग कंपनियों को छोड़कर) के लिए 15 दिसंबर 2019 के बाद शुरू होने वाले वर्षों से; शेष के लिए 15 दिसंबर 2022 के बाद से। **दायरा:** ASC 326-20 में निवेश हेतु रखे ऋण, HTM ऋण प्रतिभूतियाँ, व्यापारिक प्राप्तियाँ, ASC 606 अनुबंध संपत्तियाँ और पट्टा शुद्ध निवेश आते हैं; off-balance-sheet जोखिम अलग देयता के रूप में रखा जाता है। AFS ऋण प्रतिभूतियाँ ASC 326-30 में जाती हैं — क्रेडिट भाग भत्ते से (जिसकी सीमा amortized cost और उचित मूल्य के अंतर तक है) और गैर-क्रेडिट भाग OCI से। ASU 2025-05 ने ASC 606 से उत्पन्न चालू प्राप्तियों के लिए एक व्यावहारिक छूट जोड़ी, जो 15 दिसंबर 2025 के बाद शुरू होने वाली वार्षिक अवधियों पर लागू है।

**उदाहरण 1 (aging).** 600,000 / 250,000 / 100,000 / 50,000 की शेषराशियों पर 0.5% / 2% / 5% / 20% दरों से भत्ता 3,000 + 5,000 + 5,000 + 10,000 = **23,000** बनता है; कुल 1,000,000 पर शुद्ध प्राप्ति **977,000** है। समायोजन: आरंभिक 18,000, write-off 4,000, वसूली 1,000, अतः व्यय = 23,000 − 18,000 + 4,000 − 1,000 = **8,000**। Write-off कभी व्यय में नहीं जाता। **उदाहरण 2 (PCD gross-up).** क्रय की गई पहले से बिगड़ी ऋण-संपत्ति: बकाया मूलधन 1,000,000, क्रय मूल्य 800,000, अपेक्षित क्रेडिट नुकसान 120,000; प्रारंभिक amortized cost = 800,000 + 120,000 = **920,000**, **पहले दिन कोई व्यय नहीं**, और गैर-क्रेडिट छूट 1,000,000 − 920,000 = **80,000** ब्याज आय में amortize होती है। **IFRS 9 से तुलना:** वहाँ चरणबद्ध मॉडल है — क्रेडिट जोखिम सार्थक बढ़ने तक केवल 12-माह नुकसान; CECL शुरुआत से ही पूर्ण-जीवन नुकसान लेता है।

> व्यक्तिगत अध्ययन नोट; कर, वित्तीय या अंकेक्षण सलाह नहीं। (प्रारंभिक अनुवाद)
