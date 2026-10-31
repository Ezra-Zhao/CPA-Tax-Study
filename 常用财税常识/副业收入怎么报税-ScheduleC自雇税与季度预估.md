# 副业收入怎么报税：Schedule C、自雇税与季度预估

这篇讲什么：
- 白天上班、晚上和周末接活的人最常问的三个问题：副业的钱算什么收入、自雇税为什么是 15.3%、公司给的 W-2 工资会不会让副业重复交社保税。这篇用一张 Schedule C 的骨架把收入、扣除、自雇税与预估税一次说清，并给一个 50,000 美元净利的完整算例。
- 来源口径：《国内收入法典》（IRC）第 61(a)(2) 条经营收入、第 162 条普通必要经营支出、第 1401 条自雇税率、第 1402(a)(12) 条 92.35% 系数、第 164(f) 条自雇税一半扣除、第 199A 条合格经营收入扣除、第 6654 条预估税；IRS Schedule C、Schedule SE 与 Publication 334、535 的现行口径。

---

## 中文主文

### 一、先定性：没有雇主发工资，就是自雇收入

判断只看一件事：这笔活是谁在管你怎么做。客户只买结果、不管过程、你自担盈亏，就是自雇（self-employed），哪怕你只有一个人、没有注册公司、客户只给你一张 1099-NEC。自雇收入进 Schedule C 申报，第 61(a)(2) 条把经营毛收入计入总收入；单成员 LLC 默认被无视（disregarded）时同样填 Schedule C，不另交公司税表。反过来，若对方控制你的时间、地点与做法，又给你 W-2，那是雇佣收入，不在本篇范围，分类边界见本仓 W-2 与 1099 那一篇。

### 二、Schedule C 的骨架：毛收入减普通必要支出等于净利

Schedule C 就三段。第一段算毛收入：客户付款、平台打款、现金与以物抵账都算，1099-NEC 上的数字要能对上，但报税以你实际收到的全部经营收入为准，少报一张没收到的 1099 不等于少报一笔收入。第二段减支出，标准是第 162 条的普通（ordinary）与必要（necessary）：同行通常都花的、且对这门生意有帮助的，如软件订阅、广告、耗材、外包、职业保险、为生意跑的里程；私人支出第 262 条一律不能扣，通勤与个人手机的话费里私人那部分要按比例切开。第三段得出净利（net profit），这个数字同时是两个税的起点：并入 Form 1040 算所得税，又流进 Schedule SE 算自雇税。记录义务在第 6001 条与 Reg. §1.6001-1：账、发票、银行流水要留到时效期过后，副业最常见的翻车不是税率算错，是现金收入没记录、个人与生意账混在一起对不上。

### 三、自雇税 15.3% 是怎么来的，为什么先乘 92.35%

雇员的社保医保税是雇主雇员各付一半，自雇者一个人付两半，这就是自雇税。第 1401(a) 条社会保障部分 12.4%，只对当年社保工资基数（wage base，逐年由 SSA 公布）以内的部分征收；第 1401(b) 条 Medicare 部分 2.9%，没有上限；两项合计 15.3%。收入超过门槛（单身 200,000 美元、夫妻合报 250,000 美元）还要按第 1401(b)(2) 条另付 0.9% 的附加 Medicare 税。计算时先打折：净利先乘第 1402(a)(12) 条的 92.35%，得净自雇收入，再乘税率，立法逻辑是把雇主那一半模拟扣除掉。一年里既有 W-2 工资又有副业时，两边的社保部分共用同一个工资基数上限，W-2 已交满的部分副业不再重复交 12.4%，但 2.9% 照付，这一步 Schedule SE 会自动处理，前提是把 W-2 工资如实填进去。交完别忘补偿：第 164(f) 条允许把自雇税的一半在算调整后总收入时先扣掉（above-the-line），这不是 Schedule C 支出，别填错地方。净自雇收入低于 400 美元时一般无须交自雇税、也不必交 Schedule SE（第 6017 条的申报门槛口径），但所得税该报还是报。

### 四、算例：副业净利 50,000 美元，自雇税交多少

设全年副业净利 50,000 美元、无 W-2 工资、全年在社保工资基数以内。第一步，净自雇收入等于 50,000 乘以 92.35%，等于 46,175 美元；第二步，自雇税等于 46,175 乘以 15.3%，等于 7,064.78 美元（约 7,065 美元）；第三步，其中一半 3,532 美元左右按第 164(f) 条在 Form 1040 上先行扣除，降低所得税的计税起点。注意所得税另算：50,000 美元净利并入总收入后，标准扣除与税档照常适用；若符合条件，还可按第 199A 条主张最高 20% 的合格经营收入（QBI）扣除，受应税收入门槛、工资与财产限制，副业规模小、总收入不高时通常能足额拿到，但它扣的是所得税，不是自雇税，顺序不能颠倒。

### 五、现金流安排：季度预估与加州落点

自雇没有雇主预扣，全靠自己按第 6654 条分四期交预估税（一般为 4 月、6 月、9 月与次年 1 月的中旬，遇节假日顺延），安全港与欠付罚金的算法见本仓季度预估税那一篇，这里的实务动作只有两个：每笔副业收入到账先划走一个固定比例到单独的税款账户，以及每季度末用 Schedule C 的年内账估一次净利再定预估额，年底才发现欠一大笔的人，问题多半出在没划账。加州落点：加州没有单独的自雇税，副业净利并入加州所得税按州税档计税、同样要交加州预估税（Form 540-ES，加州节奏为 30%、40%、0%、30%）；在加州卖实物商品还要另看 CDTFA 的销售税许可，与所得税是两套系统，别把平台代收当成自己已经办完。

*声明：个人学习笔记，不构成税务建议。具体申报请咨询持牌 CPA 或税务律师。*

---

## English

**Side income is self-employment income: Schedule C, the 15.3% self-employment tax, and quarterly estimates.** If clients buy results rather than control how you work, you are self-employed even without an entity, and the income is business gross income under IRC section 61(a)(2), reported on Schedule C (a single-member LLC is disregarded by default and uses the same form). Schedule C subtracts ordinary and necessary expenses under section 162 — personal expenses are barred by section 262 — and the resulting net profit feeds both income tax and Schedule SE. The self-employment tax combines section 1401(a), 12.4% Social Security up to the annual wage base, and section 1401(b), 2.9% Medicare with no cap, totaling 15.3%, plus a 0.9% Additional Medicare Tax above $200,000 single / $250,000 joint under section 1401(b)(2). Net profit is first multiplied by 92.35% under section 1402(a)(12), and section 164(f) lets you deduct one-half of the tax above the line. Worked example: $50,000 of net profit becomes $46,175 of net self-employment earnings, tax of $46,175 x 15.3% = $7,064.78, with about $3,532 deductible under section 164(f); the section 199A qualified business income deduction (up to 20%) may reduce income tax but never the self-employment tax. W-2 wages and side income share one Social Security wage base, so the 12.4% part is not paid twice. With no withholding, pay quarterly estimates under section 6654; California has no separate self-employment tax but taxes the same profit as state income, with its own 540-ES schedule. *Personal study notes; not tax advice.*

## Español (译稿)

**Los ingresos de un trabajo paralelo son ingresos de trabajo por cuenta propia: Schedule C, el impuesto del 15,3 % y los pagos estimados trimestrales.** Si los clientes compran resultados y no controlan cómo trabaja, usted es trabajador por cuenta propia aunque no tenga sociedad, y el ingreso es ingreso bruto de negocio según el IRC § 61(a)(2), declarado en el Schedule C (una LLC de un solo miembro es ignorada por defecto y usa el mismo formulario). El Schedule C resta los gastos ordinarios y necesarios del § 162 — los gastos personales están prohibidos por el § 262 — y la ganancia neta alimenta tanto el impuesto sobre la renta como el Schedule SE. El impuesto de autoempleo combina el § 1401(a), 12,4 % de Seguro Social hasta la base salarial anual, y el § 1401(b), 2,9 % de Medicare sin tope, en total 15,3 %, más un 0,9 % adicional de Medicare por encima de $200.000 (soltero) / $250.000 (conjunto) según el § 1401(b)(2). La ganancia neta se multiplica primero por 92,35 % según el § 1402(a)(12), y el § 164(f) permite deducir la mitad del impuesto por encima de la línea. Ejemplo: $50.000 de ganancia neta se convierten en $46.175 de ingreso neto de autoempleo, impuesto de $46.175 x 15,3 % = $7.064,78, con unos $3.532 deducibles según el § 164(f); la deducción por ingreso comercial calificado del § 199A (hasta 20 %) puede reducir el impuesto sobre la renta, pero nunca el de autoempleo. Los salarios W-2 y el trabajo paralelo comparten una sola base salarial del Seguro Social, así que el 12,4 % no se paga dos veces. Sin retención, pague estimados trimestrales según el § 6654; California no tiene un impuesto de autoempleo separado, pero grava la misma ganancia como renta estatal, con su propio calendario 540-ES. *Notas personales de estudio; no es asesoramiento fiscal.* (Traducción de estudio, pendiente de revisión nativa.)

## 한국어 (초역·교정 대기)

**부업 소득은 자영업 소득이다: Schedule C, 15.3% 자영업세와 분기별 예납.** 고객이 일하는 방식이 아니라 결과를 사는 구조라면 법인이 없어도 자영업자이며, 그 소득은 IRC § 61(a)(2)의 사업 총소득으로 Schedule C에 신고합니다(1인 LLC는 기본적으로 무시되어 같은 양식을 씁니다). Schedule C에서는 § 162의 통상적이고 필요한 경비를 빼고(개인 지출은 § 262로 금지), 남은 순이익이 소득세와 Schedule SE 양쪽의 출발점이 됩니다. 자영업세는 § 1401(a) 사회보장 12.4%(연간 임금 기준액까지)와 § 1401(b) Medicare 2.9%(상한 없음)를 합한 15.3%이며, § 1401(b)(2)에 따라 단독 $200,000 / 합산 $250,000 초과분에는 0.9% 추가 Medicare 세금이 붙습니다. 순이익에는 먼저 § 1402(a)(12)의 92.35%를 곱하고, § 164(f)로 세금의 절반을 조정 전 공제로 뺄 수 있습니다. 계산 예: 순이익 $50,000은 자영업 순수입 $46,175가 되고, 세금은 $46,175 x 15.3% = $7,064.78이며 약 $3,532를 § 164(f)로 공제합니다. § 199A 적격 사업소득 공제(최대 20%)는 소득세를 줄일 수 있어도 자영업세는 줄이지 못합니다. W-2 임금과 부업은 사회보장 임금 기준액을 공유하므로 12.4%를 두 번 내지 않습니다. 원천징수가 없으므로 § 6654에 따라 분기별 예납을 해야 하고, 캘리포니아에는 별도의 자영업세는 없지만 같은 이익에 주 소득세가 붙고 540-ES 일정이 따로 있습니다. (학습용 초역으로, 원어민 교정이 필요합니다.) *개인 학습 노트이며 세무 자문이 아닙니다.*

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

**Thu nhập phụ là thu nhập tự doanh: Schedule C, thuế tự doanh 15,3% và thuế tạm tính hằng quý.** Nếu khách hàng mua kết quả chứ không kiểm soát cách bạn làm việc, bạn là người tự doanh dù không có công ty, và khoản thu là thu nhập gộp kinh doanh theo IRC § 61(a)(2), khai trên Schedule C (LLC một thành viên mặc định bị bỏ qua và dùng cùng mẫu). Schedule C trừ các chi phí thông thường và cần thiết theo § 162 — chi phí cá nhân bị cấm theo § 262 — và lợi nhuận ròng là điểm khởi đầu cho cả thuế thu nhập lẫn Schedule SE. Thuế tự doanh gồm § 1401(a) An sinh xã hội 12,4% tới mức trần lương hằng năm và § 1401(b) Medicare 2,9% không trần, tổng 15,3%, cộng thêm 0,9% thuế Medicare bổ sung trên $200.000 (độc thân) / $250.000 (vợ chồng khai chung) theo § 1401(b)(2). Lợi nhuận ròng trước hết nhân với 92,35% theo § 1402(a)(12), và § 164(f) cho khấu trừ một nửa số thuế trên dòng. Ví dụ: lợi nhuận ròng $50.000 thành thu nhập tự doanh ròng $46.175, thuế $46.175 x 15,3% = $7.064,78, với khoảng $3.532 được khấu trừ theo § 164(f); khấu trừ thu nhập kinh doanh đủ điều kiện § 199A (tới 20%) có thể giảm thuế thu nhập nhưng không bao giờ giảm thuế tự doanh. Lương W-2 và thu nhập phụ dùng chung một trần lương An sinh xã hội, nên phần 12,4% không bị trả hai lần. Không có khấu lưu tại nguồn, hãy nộp tạm tính hằng quý theo § 6654; California không có thuế tự doanh riêng nhưng đánh thuế cùng khoản lợi nhuận như thu nhập của bang, với lịch 540-ES riêng. (Bản dịch học tập sơ bộ, chờ người bản ngữ hiệu đính.) *Ghi chép học tập cá nhân, không phải tư vấn thuế.*

## हिन्दी (प्रारंभिक अनुवाद, समीक्षा लंबित)

**साइड आय स्व-रोज़गार आय है: Schedule C, 15.3% स्व-रोज़गार कर और तिमाही अनुमानित भुगतान।** यदि ग्राहक यह नहीं नियंत्रित करते कि आप कैसे काम करते हैं, बल्कि परिणाम ख़रीदते हैं, तो बिना किसी इकाई के भी आप स्व-रोज़गारी हैं, और वह आय IRC § 61(a)(2) के तहत व्यवसाय की सकल आय है, जो Schedule C पर रिपोर्ट होती है (एकल-सदस्य LLC डिफ़ॉल्ट रूप से उपेक्षित होती है और वही फ़ॉर्म इस्तेमाल करती है)। Schedule C § 162 के साधारण और आवश्यक ख़र्च घटाता है — व्यक्तिगत ख़र्च § 262 से वर्जित हैं — और परिणामी शुद्ध लाभ आयकर और Schedule SE दोनों का आधार बनता है। स्व-रोज़गार कर में § 1401(a) का 12.4% सामाजिक सुरक्षा (वार्षिक वेतन-आधार तक) और § 1401(b) का 2.9% Medicare (बिना सीमा) मिलकर 15.3% बनता है, साथ ही § 1401(b)(2) के तहत $200,000 एकल / $250,000 संयुक्त से ऊपर 0.9% अतिरिक्त Medicare कर लगता है। शुद्ध लाभ को पहले § 1402(a)(12) के तहत 92.35% से गुणा किया जाता है, और § 164(f) कर के आधे हिस्से को above-the-line कटौती देता है। उदाहरण: $50,000 शुद्ध लाभ $46,175 शुद्ध स्व-रोज़गार आय बनता है, कर $46,175 x 15.3% = $7,064.78, जिसमें से लगभग $3,532 § 164(f) के तहत कटौती योग्य है; § 199A योग्य व्यवसाय आय कटौती (20% तक) आयकर घटा सकती है, पर स्व-रोज़गार कर कभी नहीं। W-2 वेतन और साइड आय एक ही सामाजिक सुरक्षा वेतन-आधार साझा करते हैं, इसलिए 12.4% हिस्सा दो बार नहीं चुकाया जाता। कोई withholding न होने पर § 6654 के तहत तिमाही अनुमानित भुगतान करें; कैलिफ़ोर्निया में अलग स्व-रोज़गार कर नहीं है, पर वही लाभ राज्य आय के रूप में कर योग्य है और उसका अपना 540-ES कार्यक्रम है। (अध्ययन हेतु प्रारंभिक अनुवाद, मूलभाषी समीक्षा लंबित है।) *व्यक्तिगत अध्ययन नोट्स; कर सलाह नहीं है।*
