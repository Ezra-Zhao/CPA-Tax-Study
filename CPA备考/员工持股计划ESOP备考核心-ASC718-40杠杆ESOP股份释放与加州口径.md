# 员工持股计划 ESOP 备考核心：ASC 718-40 的杠杆 ESOP、股份释放与薪酬成本

> 个人学习笔记，不构成税务或会计建议。本文以 FASB《会计准则汇编》ASC 718-40（《薪酬——股份支付——员工持股计划》）与 ASC 718 总则为纲；ESOP 的税务面（IRC §§ 401(a)、4975、1042 等）仓内已有《ESOP 怎么计税》专篇，本篇只管发起人（雇主）一侧的财务会计与 CPA 考试口径，具体处理以准则原文与公司审计师意见为准。

## 中文主文

ESOP 在 FAR 里不算大题，但一出就是一串连环判断：信托买的股票先停在「暂缓账户」里不算已发行，债务还多少、股份放多少，薪酬成本按释放股份的公允价值走而不是按成本走，再加上股利的两副面孔。把这条链子理顺，这类题基本是送分。

### 一、定位：ESOP 是带信托外壳的员工福利计划

- **准则位置**：ASC 718-40 源自原 SOP 93-6（AICPA《雇主对 ESOP 的会计处理》），专管发起人对员工持股计划（employee stock ownership plan）的会计。ESOP 本身是符合 IRC § 401(a) 的限定性员工福利信托，主要投资于雇主自家证券；信托可以是**杠杆型**（leveraged，信托借钱买股）或非杠杆型（公司逐年供款或直接拨股）。考试几乎只考杠杆型。
- **与 ASC 718 总则的分工**：普通股份支付（如期权、RSU）看 ASC 718 本篇之外的部分；ESOP 有专门模型，不套用「授予日锁定」那套——它的计量锚点是股份**承诺释放**的时点。
- **1993 年分水岭**：1992 年 12 月 31 日之后取得的股份（以及之后新设的 ESOP）按现行模型（释放股份按公允价值计薪酬成本）；更早取得的股份有祖父条款，沿用取得成本计量。题干给取得年份时先看这一刀。

### 二、杠杆 ESOP 的交易结构：借钱、买股、停放、释放

- **四步结构**：①ESOP 信托向银行（或向雇主转借）借款；②信托用借款买入雇主股票（新发行股或老股东的存量股）；③买入的股份先记入**暂缓账户**（suspense account），在信托层面尚未分配给员工；④随着信托偿还债务，股份按偿债进度逐步「释放」（release），再分配（allocate）到员工个人账户。
- **发起人资产负债表**：雇主若为信托债务提供担保、或承诺供款使信托足以偿债，这笔债务要记在雇主账上（负债），同时以一项权益抵减项列示「未赚得的 ESOP 股份」（unearned ESOP shares，类似库存股的抵减权益科目）。信托若无雇主担保且雇主无供款承诺，债务不进雇主报表——这是范围判断的第一关。
- **暂缓股份的地位**：未释放的股份**不算已发行在外**——不进 EPS 分母、不享有已分配地位；只有已释放（committed to be released）并分配的股份才逐步进入流通股口径。这一条是 EPS 题的固定陷阱。

### 三、股份释放公式：按偿债比例，不按时间平均

- **释放比例**：每期释放的股份数，按当期偿债额（本金加利息，debt service）占**全部待偿债务的本金加利息总额**的比例计算。公式写作：本期释放股数＝暂缓股份总数 ×（本期偿还本息 ÷ 全部年度应偿本息总额）。只还利息的年份释放很少，本金还得快的年份释放多——释放跟着钱走，不跟着日历走。
- **承诺释放（committed to be released）**：股份一旦按公式算出应释放，即视为已承诺释放，当期就要确认相应的薪酬成本，哪怕信托内部的分配入账动作稍晚。计量时点卡在「承诺释放」，不是卡在员工拿到对账单。

### 四、薪酬成本：按释放股份的平均公允价值，差额进 APIC

- **计量规则**：当期薪酬成本＝当期承诺释放股份数 × 该期间股份的**平均公允价值**（average fair value）。注意不是信托当初的买入成本。
- **账务链条**：确认薪酬成本时，借记薪酬费用（按公允价值），贷记「未赚得的 ESOP 股份」抵减项（按这批股份的原始成本冲减），两者差额贷记（股价涨了）或借记（股价跌了）资本公积 APIC。成本口径负责清掉抵减项，公允价值口径负责定费用，差额由 APIC 吸收——这正是 SOP 93-6 相对旧法的核心改动。
- **利息与供款**：信托债务的利息按常规确认利息费用；雇主向信托的供款中，用于付息的部分是利息、用于还本的部分才触发股份释放与薪酬成本。把供款一股脑全记薪酬费用是常见错法。

### 五、股利的两副面孔：看股份分没分到员工头上

- **已分配股份的股利**：记为正常的股利——冲减留存收益，与普通股股利同口径。
- **暂缓（未分配）股份的股利**：若被信托用来偿还债务，它在经济实质上不是给股东的分红，而是偿债资金的一部分，会计上**冲减信托债务及应计利息**，不作股利处理、不冲留存收益。同一笔股利、两种落点，分水岭就是股份有没有分配到员工账户。

### 六、贯穿算例：一笔十年期杠杆 ESOP 的第一年

- **设定**：信托借款 1,000,000 美元买入雇主新发行股份 100,000 股，每股成本 10 美元。全部债务本息合计 1,250,000 美元（本金 1,000,000＋利息 250,000）。第一年信托偿还本息 250,000 美元；当年股份平均公允价值每股 13 美元；当年每股股利 0.50 美元。
- **释放股数**：250,000 ÷ 1,250,000＝20%，释放 100,000 × 20%＝20,000 股。
- **薪酬成本**：20,000 × 13＝260,000 美元。同时冲减未赚得 ESOP 股份抵减项 20,000 × 10＝200,000 美元，差额 260,000 − 200,000＝60,000 美元贷记 APIC。本地两遍复算：260,000＝200,000＋60,000，勾稽一致。
- **股利分流**：全年股利合计 100,000 × 0.50＝50,000 美元。其中已分配 20,000 股对应的 10,000 美元是真股利，冲留存收益；暂缓 80,000 股对应的 40,000 美元用于偿债，冲减债务与应计利息。10,000＋40,000＝50,000，与总额一致。
- **EPS 口径**：当年进 EPS 分母的只有已释放的 20,000 股按时间加权，暂缓的 80,000 股不算在外流通股。

### 七、披露与报表列示

- **资产负债表**：未赚得的 ESOP 股份在权益部分单列为抵减项；担保的 ESOP 债务按流动与非流动拆分列负债。
- **附注披露**：计划的一般说明、会计政策（特别是股份释放与薪酬成本计量政策）、暂缓与已分配股份数、未赚得股份的公允价值、股利如何使用等，都是 ASC 718-40-50 的常规披露项。
- **非杠杆 ESOP**：公司直接拨股或供款买股时，薪酬成本同样按拨出或承诺拨出股份的公允价值确认，逻辑与杠杆型在计量端汇合，差别只在没有债务与暂缓释放这一层结构。

### 八、加州口径与考试提示

- **加州口径**：加州没有另设一套 ESOP 会计规则——上市公司与非上市公司都按美国 GAAP（ASC 718-40）编报表，本篇的释放公式、公允价值计量与股利分流在加州雇主同样适用。加州特有的一层在税务与公司法：ESOP 信托的州税处理大体衔接联邦限定性计划框架，而加州《公司法》下新发行股份给信托的发行程序与董事会定价，属公司治理事项、不改会计确认；备考时把「加州口径」理解为「GAAP 照用、州法只管程序」即可，不要虚构加州版释放比例。
- **易错点清单**：①薪酬成本按买入成本算（应按释放时平均公允价值）；②释放比例只按本金算（应按本金加利息的偿债额）；③暂缓股份计入 EPS 分母（不计入）；④暂缓股份股利一律冲留存收益（用于偿债时冲债务）；⑤雇主无担保又无供款承诺时仍把信托债务上表（不应上表）；⑥把 1993 年前祖父股份也按公允价值计量（沿用成本）。

> 个人学习笔记，不构成税务或会计建议。ESOP 的设立、供款扣除与 § 1042 递延等问题请结合仓内税法篇与专业人士意见处理。

## English

An ESOP is a qualified employee benefit trust (IRC § 401(a)) invested primarily in employer securities; the sponsor's accounting sits in **ASC 718-40** (formerly SOP 93-6), not in the general grant-date model of ASC 718. In a **leveraged ESOP**, the trust borrows money, buys employer shares, and parks them in a **suspense account**. As the trust services the debt, shares are **released** in proportion to debt service: shares released for the period = total suspense shares × (current-period principal and interest paid ÷ total principal and interest over the life of the loan). Release follows the money, not the calendar. If the employer guarantees the debt or commits to fund contributions, the debt is recorded on the employer's balance sheet with an offsetting contra-equity account, **unearned ESOP shares**; uncommitted suspense shares are not outstanding — they stay out of the EPS denominator.

**Compensation cost is measured at fair value, not cost.** Cost for a period equals shares committed to be released multiplied by the period's **average fair value** per share. The entry debits compensation expense at fair value, credits the unearned ESOP shares contra account at the shares' original cost, and plugs the difference to APIC. Interest on the trust debt is ordinary interest expense; only the principal portion of contributions drives release. **Dividends split two ways**: dividends on allocated shares are normal dividends (a charge to retained earnings), while dividends on suspense shares used to service debt reduce the debt and accrued interest instead — they are not dividends in substance. Shares acquired after December 31, 1992 follow this fair-value model; older shares are grandfathered at cost. California adds no separate ESOP accounting model — GAAP governs reporting for California sponsors, and state law speaks mainly to issuance procedure and tax conformity.

**Worked example.** A trust borrows $1,000,000 and buys 100,000 newly issued shares at $10. Total debt service over the loan is $1,250,000; first-year debt service is $250,000, so the release fraction is 250,000 / 1,250,000 = 20%, releasing 20,000 shares. At an average fair value of $13, compensation cost is 20,000 × 13 = **$260,000**; the contra-equity account is relieved at cost, 20,000 × 10 = $200,000, and the $60,000 difference is credited to APIC (260,000 = 200,000 + 60,000). Dividends of $0.50 on 100,000 shares total $50,000: the $10,000 on allocated shares charges retained earnings, and the $40,000 on suspense shares used for debt service reduces debt and accrued interest (10,000 + 40,000 = 50,000). Only the released shares enter weighted-average shares outstanding.

> Personal study notes only; not tax or accounting advice.

## Español (traducción de estudio)

Un ESOP es un fideicomiso calificado de beneficios para empleados (IRC § 401(a)) invertido principalmente en valores del empleador; su contabilidad en cabeza del patrocinador está en **ASC 718-40** (antes SOP 93-6), no en el modelo general de fecha de concesión de ASC 718. En un **ESOP apalancado**, el fideicomiso se endeuda, compra acciones del empleador y las deja en una **cuenta en suspenso**. A medida que paga la deuda, las acciones se **liberan** en proporción al servicio de la deuda: acciones liberadas del período = total en suspenso × (capital e intereses pagados en el período ÷ capital e intereses totales del préstamo). Si el empleador garantiza la deuda o se compromete a aportar, la deuda se registra en su balance con una contrapartida reductora del patrimonio, **acciones ESOP no devengadas**; las acciones en suspenso no están en circulación y quedan fuera del denominador de EPS.

**El costo de compensación se mide a valor razonable, no al costo.** Es las acciones comprometidas para liberación por el **valor razonable promedio** del período. Se debita gasto de compensación a valor razonable, se acredita la cuenta reductora al costo original de las acciones, y la diferencia va a APIC. **Los dividendos se bifurcan**: los de acciones ya asignadas son dividendos normales (cargo a resultados acumulados); los de acciones en suspenso usados para pagar la deuda reducen la deuda y los intereses devengados, porque en sustancia son servicio de deuda. Las acciones adquiridas después del 31 de diciembre de 1992 siguen este modelo de valor razonable; las anteriores conservan el costo por cláusula de antigüedad. California no crea un modelo contable propio: rige GAAP.

**Ejemplo.** Préstamo de 1.000.000 para comprar 100.000 acciones a 10 dólares; servicio total de la deuda 1.250.000; primer año 250.000, es decir, 20%: se liberan 20.000 acciones. Con valor razonable promedio de 13, el costo es 20.000 × 13 = **260.000**; la cuenta reductora se libera al costo, 200.000, y los 60.000 de diferencia van a APIC. Dividendos de 0,50 por acción: 50.000 en total; 10.000 (acciones asignadas) cargan resultados acumulados y 40.000 (en suspenso, usados en la deuda) reducen deuda e intereses.

> Notas personales de estudio; no constituyen asesoría fiscal ni contable.

## 한국어 (초역, 원어민 감수 대기)

ESOP는 IRC § 401(a)의 적격 종업원 복지금고로, 주로 고용주 증권에 투자합니다. 스폰서 회계는 ASC 718 일반 모형이 아니라 **ASC 718-40**(구 SOP 93-6)에 있습니다. **레버리지형 ESOP**에서는 신탁이 차입하여 고용주 주식을 사서 **유예 계정(suspense account)**에 넣어 둡니다. 부채를 상환할수록 주식이 **방출(release)**되는데, 방출 비율은 해당 기간 원리금 상환액 ÷ 전체 원리금 총액입니다. 방출은 달력이 아니라 돈의 흐름을 따릅니다. 고용주가 부채를 보증하거나 출연을 약속하면 그 부채는 고용주 대차대조표에 부채로 기록되고, 자기자본 차감 항목인 **미획득 ESOP 주식(unearned ESOP shares)**이 대응합니다. 유예 중인 주식은 발행주식수에 들어가지 않아 EPS 분모에서 제외됩니다.

**보상원가는 취득원가가 아니라 공정가치로 측정**합니다. 기간 보상원가는 방출하기로 확정된 주식 수 × 기간 **평균 공정가치**입니다. 공정가치로 보상비용을 차변하고, 미획득 주식 차감 항목은 원래 취득원가로 대변하며, 차액은 APIC로 처리합니다. **배당은 두 갈래**입니다. 이미 배분된 주식의 배당은 통상의 배당으로 이익잉여금을 차감하지만, 유예 주식의 배당이 부채 상환에 쓰이면 부채와 미지급이자를 줄이며 배당으로 보지 않습니다. 1992년 12월 31일 이후 취득한 주식이 이 공정가치 모형을 따르고, 그 이전 주식은 원가 기준이 유지됩니다(조부 조항). 캘리포니아에는 별도의 ESOP 회계 모형이 없으며 GAAP가 적용됩니다.

**예시.** 신탁이 1,000,000달러를 빌려 주당 10달러에 100,000주를 샀습니다. 전체 원리금은 1,250,000달러, 첫해 상환액은 250,000달러로 방출 비율은 20%, 방출 주식은 20,000주입니다. 평균 공정가치가 13달러이면 보상원가는 20,000 × 13 = **260,000달러**, 차감 항목은 원가 200,000달러만큼 줄고 차액 60,000달러는 APIC에 대변합니다. 주당 0.50달러 배당 총액은 50,000달러이며, 배분된 주식분 10,000달러는 이익잉여금을 차감하고, 부채 상환에 쓰인 유예 주식분 40,000달러는 부채와 미지급이자를 줄입니다.

> 개인 학습 노트이며 세무·회계 자문이 아닙니다. (초역, 원어민 감수 대기)

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

ESOP là một quỹ tín thác phúc lợi nhân viên đủ điều kiện theo IRC § 401(a), đầu tư chủ yếu vào chứng khoán của chính người sử dụng lao động; kế toán phía nhà tài trợ nằm ở **ASC 718-40** (trước đây là SOP 93-6), không theo mô hình ngày cấp chung của ASC 718. Trong **ESOP có đòn bẩy**, quỹ vay tiền, mua cổ phiếu của công ty và giữ trong **tài khoản treo (suspense account)**. Khi quỹ trả nợ, cổ phiếu được **giải phóng (release)** theo tỷ lệ dịch vụ nợ: cổ phiếu giải phóng trong kỳ = tổng cổ phiếu treo × (gốc và lãi đã trả trong kỳ ÷ tổng gốc và lãi của khoản vay). Nếu công ty bảo lãnh khoản nợ hoặc cam kết đóng góp, khoản nợ được ghi trên bảng cân đối của công ty kèm khoản giảm trừ vốn chủ sở hữu **cổ phiếu ESOP chưa hưởng (unearned ESOP shares)**; cổ phiếu treo chưa được tính là đang lưu hành và nằm ngoài mẫu số EPS.

**Chi phí đãi ngộ được đo theo giá trị hợp lý, không theo giá vốn**: bằng số cổ phiếu cam kết giải phóng nhân **giá trị hợp lý bình quân** trong kỳ. Ghi Nợ chi phí theo giá trị hợp lý, ghi Có khoản giảm trừ theo giá gốc, chênh lệch vào APIC. **Cổ tức chia hai ngả**: cổ tức trên cổ phiếu đã phân bổ là cổ tức thông thường (trừ vào lợi nhuận giữ lại); cổ tức trên cổ phiếu treo dùng để trả nợ thì trừ vào nợ và lãi phải trả, vì bản chất là trả nợ. Cổ phiếu mua sau ngày 31/12/1992 theo mô hình giá trị hợp lý này; cổ phiếu cũ hơn giữ theo giá gốc. California không có mô hình kế toán ESOP riêng — GAAP vẫn áp dụng.

**Ví dụ.** Quỹ vay 1.000.000 USD mua 100.000 cổ phiếu giá 10 USD; tổng gốc lãi là 1.250.000; năm đầu trả 250.000, tức 20%, giải phóng 20.000 cổ phiếu. Giá trị hợp lý bình quân 13 USD cho chi phí 20.000 × 13 = **260.000**; khoản giảm trừ giảm theo giá gốc 200.000, chênh lệch 60.000 vào APIC. Cổ tức 0,50 USD/cổ phiếu tổng cộng 50.000: phần 10.000 của cổ phiếu đã phân bổ trừ vào lợi nhuận giữ lại, phần 40.000 của cổ phiếu treo dùng trả nợ thì trừ vào nợ và lãi phải trả.

> Ghi chú học tập cá nhân, không phải tư vấn thuế hay kế toán. (Bản dịch sơ bộ, chờ hiệu đính)

## हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

ESOP IRC § 401(a) के अंतर्गत एक अर्हक कर्मचारी-लाभ ट्रस्ट है जो मुख्यतः नियोक्ता की प्रतिभूतियों में निवेश करता है; प्रायोजक-पक्ष का लेखांकन ASC 718 के सामान्य अनुदान-तिथि मॉडल में नहीं, बल्कि **ASC 718-40** (पूर्व में SOP 93-6) में है। **लीवरेज्ड ESOP** में ट्रस्ट ऋण लेकर नियोक्ता के शेयर खरीदता है और उन्हें **सस्पेंस खाते** में रखता है। जैसे-जैसे ऋण चुकता है, शेयर ऋण-सेवा के अनुपात में **रिलीज़** होते हैं: अवधि में रिलीज़ शेयर = कुल सस्पेंस शेयर × (अवधि में चुकाया मूलधन व ब्याज ÷ कुल मूलधन व ब्याज)। यदि नियोक्ता ऋण की गारंटी दे या अंशदान का वादा करे, तो ऋण नियोक्ता की बैलेंस शीट पर देयता के रूप में दर्ज होता है और उसके सामने इक्विटी-घटाव मद **अनर्जित ESOP शेयर (unearned ESOP shares)** रहती है; सस्पेंस शेयर बकाया शेयरों में नहीं गिने जाते और EPS के हर से बाहर रहते हैं।

**मुआवज़ा लागत लागत-मूल्य पर नहीं, उचित मूल्य पर मापी जाती है** — रिलीज़ हेतु प्रतिबद्ध शेयर × अवधि का **औसत उचित मूल्य**। प्रविष्टि में उचित मूल्य पर मुआवज़ा व्यय डेबिट, अनर्जित शेयर घटाव खाता मूल लागत पर क्रेडिट, और अंतर APIC में जाता है। **लाभांश दो रास्ते लेता है**: आवंटित शेयरों का लाभांश सामान्य लाभांश है (प्रतिधारित आय से घटता है), जबकि सस्पेंस शेयरों का लाभांश यदि ऋण-चुकौती में जाए तो ऋण व उपचित ब्याज घटाता है। 31 दिसंबर 1992 के बाद अर्जित शेयर इसी उचित-मूल्य मॉडल पर हैं; पुराने शेयर लागत पर ही रहते हैं। कैलिफ़ोर्निया का कोई अलग ESOP लेखांकन मॉडल नहीं है — GAAP ही लागू होता है।

**उदाहरण.** ट्रस्ट ने 1,000,000 डॉलर उधार लेकर 10 डॉलर पर 100,000 शेयर खरीदे; कुल मूलधन व ब्याज 1,250,000; पहले वर्ष की चुकौती 250,000 अर्थात 20%, इसलिए 20,000 शेयर रिलीज़ हुए। औसत उचित मूल्य 13 डॉलर पर लागत 20,000 × 13 = **260,000**; घटाव खाता लागत 200,000 से घटा और 60,000 का अंतर APIC में गया। प्रति शेयर 0.50 डॉलर लाभांश कुल 50,000: आवंटित शेयरों का 10,000 प्रतिधारित आय से घटा, ऋण में लगा सस्पेंस भाग 40,000 ऋण व ब्याज घटाता है।

> व्यक्तिगत अध्ययन नोट; कर या लेखांकन सलाह नहीं। (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)
