# 购入贷款备考核心：ASU 2025-08 购入经年贷款、gross-up 扩围与 Day-1 双重计算及加州口径

> 个人学习笔记，不构成税务或财务建议。本篇管 FASB ASU 2025-08 对购入贷款的一处改动：把原来只给已发生信用减值购入资产（PCD）用的 gross-up（总额法）扩到「购入经年贷款」（purchased seasoned loans, PSL）。仓内《应收款与信用损失备考核心》管 ASC 326 与 CECL 本体、含 PCD gross-up 算例，本篇只管这次扩围并以指针分工。

## 中文主文

### 一、改了什么：一类新贷款、一个老办法

FASB 于 2025 年 11 月 12 日发布 ASU 2025-08《金融工具——信用损失（专题 326）：购入贷款》（Financial Instruments—Credit Losses (Topic 326): Purchased Loans）。旧规矩把购入贷款劈成两半：起源后信用质量已显著恶化的 PCD 资产，取得日把预期信用损失备抵（allowance for credit losses）加回到买价上定初始摊余成本，取得日不确认信用损失费用，这就是 gross-up；非 PCD 的购入贷款恰恰相反，取得日按公允价值入账、备抵全额走信用损失费用进损益。问题出在后一半：买价本身已经反映了市场对预期损失的定价，再在 Day-1 把同一笔预期损失费用化一次，等于算了两遍——实务界多年抱怨的「双重计算」（double counting），还让两笔经济实质相近的购入贷款只因 PCD 与否的判定不同而报表大相径庭。

ASU 2025-08 的解法不是废掉 gross-up，而是扩围：新设「购入经年贷款」一类，把 gross-up 扩到符合条件的非 PCD 购入贷款上，Day-1 费用随之消失，PCD 本身的会计处理不变。

### 二、谁算经年：两条入围路，信用卡出局

购入经年贷款要同时过三道门：

1. **不是 PCD**：取得时没有发生起源后显著信用恶化——已经是 PCD 的走原 gross-up，不进这个新类。
2. **不是信用卡**：信用卡贷款被明确排除在 PSL 定义之外，理由是其交易量与循环性质特殊；债务证券与应收账款同样不在 PSL 定义内，本次扩围只管贷款。
3. **经年二选一**：其一，在企业合并中取得——合并里取得的非 PCD 贷款一律算经年；其二，在单项或组合购买中，购买发生在贷款起源后 90 天以上，且购买方没有参与该贷款的起源。

第三道门的逻辑要想通：合并取得的贷款，价格是在一揽子谈判里定的；起源 90 天后才买入的贷款，价格里也已经含了市场对这笔贷款信用状况的判断。两种情形下买价都已经「含损失定价」，再费用化一次才是重复。起源后立刻买入、或买方自己参与了起源的贷款，定价未必经过这层市场过滤，所以不给 gross-up。

### 三、怎么做账：买价加备抵，Day-1 不进损益

符合 PSL 的贷款，取得日这样定初始摊余成本：

**初始摊余成本 ＝ 购买价格 ＋ 取得日预期信用损失备抵**

备抵照 CECL 的口径估计（ASC 326-20），但它的对方科目不是费用，而是资产的入账成本。后续计量回到 CECL 的一般规则：备抵的后续变动才进信用损失费用，非信用折价部分在剩余期限内按实际利率法摊入利息收入。

算例（教学数字，本地整数与 Decimal 两路复算一致）：买方以 950,000 美元购入一组未偿本金 1,000,000 美元的非 PCD 经年贷款，取得日预期信用损失备抵为 40,000 美元。按 ASU 2025-08：初始摊余成本 ＝ 950,000 ＋ 40,000 ＝ 990,000 美元，取得日信用损失费用为零；非信用折价 ＝ 1,000,000 － 990,000 ＝ 10,000 美元，日后摊入利息收入。对照旧规矩下的非 PCD 处理：同一组贷款取得日要先认 40,000 美元信用损失费用进损益——买价里已经扣过一次的损失，在利润表上又出现一次，这正是本次修订要删掉的那一步。

### 四、生效与过渡：2026 年 12 月 15 日后，前瞻适用

- **生效**：所有主体，适用于 2026 年 12 月 15 日之后开始的年度报告期间，包括其中的中期期间；日历年度主体即 2027 年起。
- **提前采用**：允许，但只能就尚未发布或尚未可供发布的财务报表采用。
- **过渡**：前瞻适用——只管初始适用日或之后取得的贷款，存量购入贷款不追溯重述。

备考定位：本科在 FAR 的金融工具与信用损失范围内。题目若给「购入贷款、非 PCD、企业合并取得」这组条件，修订生效后的答案是 gross-up、无 Day-1 费用；题干年份在生效前或明示按旧规矩的，才走 Day-1 费用那条路。新旧并存期，先看题干的时间锚与取得方式，再动笔算，这是最容易丢分的地方。

### 五、加州口径

- **加州口径**：加州没有独立的州级会计准则，财务报告一律走美国 GAAP 本身；加州 CPA 的执照与执业规则由 California Board of Accountancy 管。本篇的判断（是不是 PSL、要不要 gross-up）在加州执业中与联邦层面完全同轨，所谓加州口径只是监管衔接，计量规则不另设一套（证据等级 B；ASU 原文、定义与生效日为 A 级）。

*声明：个人学习笔记，不构成税务或财务建议。来源：FASB ASU 2025-08, Financial Instruments—Credit Losses (Topic 326): Purchased Loans（2025-11-12 发布）；Thomson Reuters、BDO、Forvis Mazars、BerryDunn 对该 ASU 的公开解读（PSL 定义两路、信用卡与债务证券及应收账款排除、2026-12-15 后年度期间生效、允许提前采用、前瞻适用）。*

---

## English

FASB issued ASU 2025-08, *Financial Instruments—Credit Losses (Topic 326): Purchased Loans*, on November 12, 2025. Under the old model, purchased loans split in two: purchased credit-deteriorated (PCD) assets used the gross-up approach — the acquisition-date allowance for credit losses is added to the purchase price to set initial amortized cost, with no day-one credit loss expense — while non-PCD purchased loans recorded the allowance through credit loss expense on day one, even though the purchase price already reflected expected losses. That was the much-criticized double count. ASU 2025-08 creates **purchased seasoned loans (PSLs)**: non-PCD loans, excluding credit cards (debt securities and trade receivables are also outside the PSL definition), that were either acquired in a business combination or purchased more than 90 days after origination by an acquirer that was not involved in originating them. PSLs now use gross-up: initial amortized cost equals purchase price plus the acquisition-date allowance, and there is no day-one expense. PCD accounting does not change. **Example (recomputed with integers and Decimal, agreeing):** a non-PCD seasoned loan pool with unpaid principal of 1,000,000 bought for 950,000 with an acquisition-date allowance of 40,000 starts at amortized cost of 950,000 + 40,000 = **990,000**, with a noncredit discount of 1,000,000 − 990,000 = **10,000** accreted into interest income; under the old non-PCD rule the same pool would have taken a 40,000 day-one expense. The ASU is effective for annual reporting periods beginning after December 15, 2026, including interim periods, with early adoption permitted for financial statements not yet issued, applied prospectively to loans acquired on or after the initial application date. California has no separate state GAAP; the same measurement applies, with licensure and practice oversight through the California Board of Accountancy (evidence grade B).

> Personal study notes only; not tax or financial advice. Sources: FASB ASU 2025-08 (November 12, 2025); public firm summaries by Thomson Reuters, BDO, Forvis Mazars and BerryDunn.

## Español (traducción de estudio, pendiente de revisión por un hablante nativo; 初译待校)

La FASB emitió la ASU 2025-08, *Financial Instruments—Credit Losses (Topic 326): Purchased Loans*, el 12 de noviembre de 2025. En el modelo anterior, los préstamos comprados se dividían en dos: los activos con deterioro crediticio ya comprados (PCD) usaban el método gross-up — la provisión por pérdidas crediticias de la fecha de adquisición se suma al precio de compra para fijar el costo amortizado inicial, sin gasto por pérdida crediticia el primer día —, mientras que los préstamos comprados no PCD registraban la provisión como gasto el primer día, aunque el precio ya reflejaba las pérdidas esperadas: la criticada doble contabilización. La ASU 2025-08 crea los **préstamos comprados maduros (purchased seasoned loans, PSL)**: préstamos no PCD, con exclusión de las tarjetas de crédito (los valores de deuda y las cuentas por cobrar comerciales también quedan fuera de la definición), adquiridos en una combinación de negocios o comprados más de 90 días después de su originación por un adquirente que no participó en originarlos. Los PSL ahora usan gross-up: costo amortizado inicial igual a precio de compra más la provisión de la fecha de adquisición, sin gasto inicial. La contabilidad PCD no cambia. **Ejemplo (recalculado con enteros y Decimal, con el mismo resultado):** un grupo de préstamos maduros no PCD con capital impago de 1.000.000, comprado por 950.000 y con provisión inicial de 40.000, parte de un costo amortizado de 950.000 + 40.000 = **990.000**, con un descuento no crediticio de 1.000.000 − 990.000 = **10.000** que se acumula como ingreso por intereses; con la regla anterior el mismo grupo habría registrado un gasto inicial de 40.000. La ASU rige para períodos anuales iniciados después del 15 de diciembre de 2026, incluidos los períodos intermedios, con adopción anticipada permitida para estados financieros aún no emitidos y aplicación prospectiva a préstamos adquiridos en o después de la fecha de aplicación inicial. California no tiene GAAP estatal propio; rige la misma medición, bajo la supervisión de la California Board of Accountancy (nivel de evidencia B). (Traducción de estudio, pendiente de revisión nativa; 初译待校)

> Notas personales de estudio; no constituye asesoría fiscal ni financiera. Fuentes: FASB ASU 2025-08 (12 de noviembre de 2025); resúmenes públicos de Thomson Reuters, BDO, Forvis Mazars y BerryDunn.

## 한국어 (초역, 교정 대기; 初译待校)

FASB는 2025년 11월 12일 ASU 2025-08 『금융상품—신용손실(주제 326): 매입 대출』을 발표했습니다. 기존 모델에서 매입 대출은 둘로 갈렸습니다. 이미 신용이 손상된 매입 자산(PCD)은 gross-up 방식을 써서 취득일의 기대신용손실 충당금을 매입가에 더해 최초 상각후원가를 정하고 첫날 신용손실비용을 잡지 않지만, 비PCD 매입 대출은 매입가에 이미 기대손실이 반영됐는데도 첫날 충당금을 비용으로 잡았습니다. 이른바 이중 계산입니다. ASU 2025-08은 **매입 경년 대출(purchased seasoned loans, PSL)**이라는 새 범주를 만들었습니다. 비PCD 대출 중 신용카드를 제외하고(채무증권과 매출채권도 PSL 정의에서 빠집니다), 사업결합으로 취득했거나, 조성에 관여하지 않은 취득자가 조성 후 90일이 지나 매입한 대출이 해당합니다. PSL은 이제 gross-up을 씁니다. 최초 상각후원가 = 매입가 + 취득일 충당금이며 첫날 비용은 없습니다. PCD 회계는 바뀌지 않습니다. **예제(정수와 Decimal 두 방식으로 재계산해 일치):** 미상환 원금 1,000,000인 비PCD 경년 대출 묶음을 950,000에 사고 취득일 충당금이 40,000이면 최초 상각후원가는 950,000 + 40,000 = **990,000**이고, 비신용 할인은 1,000,000 − 990,000 = **10,000**으로 이자수익에 상각됩니다. 옛 비PCD 규칙이었다면 같은 묶음에 첫날 비용 40,000이 잡혔을 것입니다. 이 ASU는 2026년 12월 15일 이후 시작하는 연차 보고기간(중간기간 포함)부터 적용되며, 아직 발행되지 않은 재무제표에 대한 조기 적용이 허용되고, 최초 적용일 이후 취득한 대출에 전향적으로 적용됩니다. 캘리포니아에는 별도의 주 GAAP가 없어 같은 측정이 적용되고, 면허와 실무 감독은 California Board of Accountancy가 맡습니다(증거 등급 B). (초역, 원어민 교정 대기; 初译待校)

> 개인 학습 노트이며 세무·재무 조언이 아닙니다. 출처: FASB ASU 2025-08(2025년 11월 12일), Thomson Reuters·BDO·Forvis Mazars·BerryDunn의 공개 해설.

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính; 初译待校)

FASB đã ban hành ASU 2025-08, *Financial Instruments—Credit Losses (Topic 326): Purchased Loans*, vào ngày 12 tháng 11 năm 2025. Theo mô hình cũ, các khoản vay mua lại chia làm hai: tài sản mua đã suy giảm tín dụng (PCD) dùng phương pháp gross-up — dự phòng tổn thất tín dụng tại ngày mua được cộng vào giá mua để xác định chi phí khấu hao ban đầu, không ghi chi phí tổn thất tín dụng ngày đầu — trong khi khoản vay mua không phải PCD lại ghi dự phòng qua chi phí ngay ngày đầu, dù giá mua đã phản ánh tổn thất kỳ vọng: đó là lỗi tính trùng hai lần bị phê phán lâu nay. ASU 2025-08 tạo ra nhóm **khoản vay mua đã có tuổi (purchased seasoned loans, PSL)**: khoản vay không phải PCD, loại trừ thẻ tín dụng (chứng khoán nợ và phải thu thương mại cũng ngoài định nghĩa PSL), được mua trong một hợp nhất kinh doanh hoặc được mua hơn 90 ngày sau khi khởi tạo bởi bên mua không tham gia khởi tạo. PSL nay dùng gross-up: chi phí khấu hao ban đầu bằng giá mua cộng dự phòng tại ngày mua, không có chi phí ngày đầu. Kế toán PCD không đổi. **Ví dụ (tính lại bằng số nguyên và Decimal, kết quả khớp nhau):** một nhóm khoản vay PSL không phải PCD có gốc chưa trả 1.000.000, mua với giá 950.000, dự phòng ngày mua 40.000, thì chi phí khấu hao ban đầu là 950.000 + 40.000 = **990.000**, và phần chiết khấu phi tín dụng 1.000.000 − 990.000 = **10.000** được tích lũy vào thu nhập lãi; theo quy tắc cũ, cùng nhóm này sẽ phải ghi chi phí ngày đầu 40.000. ASU có hiệu lực cho các kỳ báo cáo năm bắt đầu sau ngày 15 tháng 12 năm 2026, kể cả kỳ giữa năm, được áp dụng sớm đối với báo cáo tài chính chưa phát hành, và áp dụng tương lai cho các khoản vay mua vào hoặc sau ngày áp dụng đầu tiên. California không có GAAP cấp bang riêng; cùng một cách đo lường được áp dụng, dưới sự giám sát của California Board of Accountancy (mức bằng chứng B). (Bản dịch sơ bộ, chờ hiệu đính; 初译待校)

> Ghi chú học tập cá nhân; không phải tư vấn thuế hay tài chính. Nguồn: FASB ASU 2025-08 (ngày 12 tháng 11 năm 2025); các bản tóm tắt công khai của Thomson Reuters, BDO, Forvis Mazars và BerryDunn.

## हिन्दी (प्रारंभिक अनुवाद, मूलभाषी समीक्षा लंबित; 初译待校)

FASB ने 12 नवंबर 2025 को ASU 2025-08, *Financial Instruments—Credit Losses (Topic 326): Purchased Loans*, जारी किया। पुराने मॉडल में ख़रीदे गए ऋण दो भागों में बँटते थे: ख़रीदे गए ऋण-बिगड़े (PCD) asset gross-up पद्धति अपनाते थे — अधिग्रहण-तिथि का अपेक्षित ऋण-हानि भत्ता ख़रीद-मूल्य में जोड़कर प्रारंभिक amortized cost तय होता था और पहले दिन कोई ऋण-हानि व्यय नहीं आता था — जबकि non-PCD ख़रीदे गए ऋणों में भत्ता पहले ही दिन व्यय में जाता था, भले ही ख़रीद-मूल्य में अपेक्षित हानि पहले से 반영 हो। यही वह दोहरी गिनती थी जिसकी लंबे समय से आलोचना होती रही। ASU 2025-08 एक नई श्रेणी बनाता है: **purchased seasoned loans (PSL)** — non-PCD ऋण, जिनमें credit card शामिल नहीं हैं (debt securities और trade receivables भी PSL परिभाषा से बाहर हैं), जो या तो business combination में प्राप्त हुए हों या origination के 90 दिन से अधिक बाद ऐसे acquirer द्वारा ख़रीदे गए हों जो origination में शामिल न रहा हो। PSL अब gross-up अपनाएँगे: प्रारंभिक amortized cost = ख़रीद-मूल्य + अधिग्रहण-तिथि भत्ता, और पहले दिन का व्यय शून्य। PCD लेखांकन नहीं बदलता। **उदाहरण (पूर्णांक और Decimal दोनों से पुनर्गणना, परिणाम समान):** अवैतनिक मूलधन 1,000,000 वाला non-PCD seasoned ऋण-समूह 950,000 में ख़रीदा जाए और अधिग्रहण-तिथि भत्ता 40,000 हो, तो प्रारंभिक amortized cost 950,000 + 40,000 = **990,000** होगा और noncredit discount 1,000,000 − 990,000 = **10,000** ब्याज-आय में amortize होगा; पुराने non-PCD नियम में उसी समूह पर पहले दिन 40,000 का व्यय आता। यह ASU 15 दिसंबर 2026 के बाद शुरू होने वाली वार्षिक रिपोर्टिंग अवधियों (उनके interim periods सहित) से प्रभावी है, अप्रकाशित वित्तीय विवरणों के लिए शीघ्र अपनाना अनुमत है, और यह प्रारंभिक अनुप्रयोग तिथि को या उसके बाद प्राप्त ऋणों पर prospectively लागू होगा। California का अपना राज्य-GAAP नहीं है; वही मापन लागू होता है और लाइसेंस व व्यवहार-पर्यवेक्षण California Board of Accountancy के पास है (साक्ष्य स्तर B)। (प्रारंभिक अनुवाद, मूलभाषी समीक्षा लंबित; 初译待校)

> व्यक्तिगत अध्ययन नोट; कर या वित्तीय सलाह नहीं। स्रोत: FASB ASU 2025-08 (12 नवंबर 2025); Thomson Reuters, BDO, Forvis Mazars और BerryDunn के सार्वजनिक सारांश।
