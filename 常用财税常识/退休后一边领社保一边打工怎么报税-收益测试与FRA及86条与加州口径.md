# 退休后一边领社保一边打工怎么报税：收益测试与 FRA 及 86 条与加州口径

> 个人学习笔记，不构成税务或社保建议。提前领了社保又回去上班的人，第一个问题往往是「多挣的钱会不会把社保扣没、税又怎么算」。这里其实是三件互不相干的事被搅在了一起：社保局的收益测试管的是福利发不发，工资税管的是在职收入照常缴不缴，所得税管的是工资把多少社保金拖进应税。分开看，每一件都不难；混着算，步步都错。本篇与本仓《社保金要不要交税》分工：那篇专讲第 86 条的应税比例本身，本篇讲「在领钱的同时还在挣钱」这一组合状态下的三层规则。

## 中文主文

### 一、先拆三层：收益测试、工资税、所得税

第一层是社保福利的收益测试（retirement earnings test），出处是《社会保障法》第 203 条（42 U.S.C. § 403），它只决定社保局暂时扣住多少福利，跟税务局无关，更不是一种税。第二层是工资税：只要人在工作，工资照常走 FICA、自雇收入照常走 SECA，没有「已经领了社保就不用再缴」的豁免。第三层是所得税：工资本身按普通收入课税，同时工资会抬高第 86 条的临时收入（provisional income），把原本免税的那部分社保金一路拖到最高 85% 应税。三层各算各的，下面逐层拆。

### 二、收益测试：未到完全退休年龄，超线按比例暂扣

收益测试只咬未到完全退休年龄（full retirement age, FRA）就提前领钱的人；1960 年及以后出生者的 FRA 是 67 岁。2026 年的线分两档（SSA 按年公布，以下为 2026 年数字，2025 年为 23,400 与 62,160 美元）：整年都未到 FRA 的，年劳动收入超过 24,480 美元的部分，每超 2 美元暂扣 1 美元福利；在达到 FRA 的那一年，只看 FRA 当月之前的收入，线放宽到 65,160 美元，每超 3 美元暂扣 1 美元；从达到 FRA 的当月起，测试彻底消失，挣多少都不扣。第一年开始领钱还有一条月度宽限：首年可按月测，月收入不超过年线除以 12（2026 年一般档为 2,040 美元）的月份，福利照发，哪怕全年总数已超线。

### 三、什么算「劳动收入」：只认工资与自雇净收入

收益测试里的 earnings 不是税法上的总收入，只认两样：W-2 工资（含小费、奖金、佣金）和自雇净收入（net earnings from self-employment）。养老金、IRA 与 401(k) 支取、股息利息、资本利得、租金收入都不算，统统不进这条线——这也是为什么「从退休账户多取钱」不会触发暂扣、而「回去打一份工」会。兼职与正式工作没有区别，看的是金额不是身份；给家人公司打工等情形下工资是否真实、是否合理，SSA 会另行核查，不在本文展开。

### 四、被暂扣的钱没有丢：FRA 时重新计算

暂扣常被误读成罚款，其实是递延。到了 FRA，SSA 会把因收益测试被整月扣住福利的那些月份，从提前领取的减额月数里剔除，重新计算月 benefits——相当于把那几个月当作没领过，之后的每月金额相应调高。它不是一次性补发一笔钱，而是余生每月多领一点。所以提前领又高收入工作的人，真正的代价主要是现金流时点：在职那几年少领，FRA 之后每月领得更多，账要拉长了看。

### 五、税这一层：工资照常缴 FICA，社保金被工资拖进应税

在职一侧没有年龄豁免：工资按 IRC § 3101 的 FICA 税率缴（社保部分为 § 3101(a)、医保部分为 § 3101(b)），雇员社保部分 6.2%，2026 年只对 § 3121(a)(1) 工资基数上限以内的前 184,500 美元工资征收（2025 年为 176,100 美元），医保部分 1.45% 无上限；自雇者走 Schedule SE，合并税率 12.4% 加 2.9%，基数上限同口径。所得税一侧，工资全额计入普通收入，再看第 86 条：临时收入等于不含社保的 AGI 加免税利息再加社保金的一半；单身超过 34,000 美元（合报 44,000 美元）进入最高一档、最多 85% 的社保金应税。算一笔小账：单身，社保金一年 24,000 美元，工资 30,000 美元，临时收入是 30,000 加 12,000 等于 42,000 美元；按 Publication 915 工作表，应税社保金是 11,300 美元——算法是超过 34,000 的 8,000 美元乘 85% 得 6,800，加上第一档封顶额 4,500（25,000 至 34,000 区间 9,000 的一半与社保金一半 12,000 取小），合计 11,300，未触及 85% 上限的 20,400 美元。实务收尾两件：社保金到手看 Form SSA-1099，想避免来年补税大单，可以交 Form W-4V 对社保金选 7%、10%、12% 或 22% 的自愿预扣，或用工资的 W-4 多扣、季度预估补齐。

### 六、贯穿算例与加州口径

把两层叠起来看一个人：2026 年整年未到 FRA，工资 34,480 美元。收益测试：超出 24,480 的部分是 10,000 美元，按每 2 美元扣 1 美元，当年暂扣福利 5,000 美元，这 5,000 美元会在 FRA 后的月额重算里慢慢回来，不是罚款。工资税：雇员社保部分 34,480 乘 6.2% 约 2,138 美元、医保部分乘 1.45% 约 500 美元，照常从工资里扣（34,480×0.062＝2,137.76；34,480×0.0145＝499.96，约数勾稽）。加州口径一句：加州不征社保金的州所得税（R&TC § 17131），工资则按加州普通收入正常课税，收益测试是联邦社保制度的事，加州没有对应扣减。

*声明：个人学习笔记，不构成税务、财务或社保建议。来源：Social Security Act § 203（42 U.S.C. § 403）；SSA 2026 年事实表（收益测试限额 24,480／65,160 美元、应税工资基数 184,500 美元）；IRC §§ 86、3101、1401；IRS Publication 915 与 Form W-4V 说明。限额与基数逐年调整，个案以 SSA 与 IRS 当年公布为准，请咨询持牌 CPA 或社保规划专业人士。*

---

## English

Working while collecting Social Security involves three separate systems that are often confused. The retirement earnings test (Social Security Act § 203, 42 U.S.C. § 403) only decides whether SSA temporarily withholds benefits — it is not a tax. Payroll tax is the second layer: wages remain subject to FICA and self-employment income to SECA, with no exemption for people already collecting benefits. Income tax is the third: wages are ordinary income, and they also raise provisional income under IRC § 86, pulling up to 85% of benefits into taxable income. This article complements the repository's § 86 article by focusing on the combined work-and-collect state.

For 2026, a beneficiary under full retirement age (67 for those born in 1960 or later) all year has $1 of benefits withheld for every $2 of earnings above $24,480 (2025: $23,400). In the year FRA is reached, only earnings before the FRA month count, the limit rises to $65,160 (2025: $62,160), and withholding softens to $1 per $3. From the FRA month onward the test disappears. Only wages and net self-employment earnings count as earnings; pensions, IRA withdrawals, dividends, capital gains, and rent do not. A first-year monthly grace rule ($24,480 ÷ 12 = $2,040 for 2026) can protect benefits in low months of the first year. Withheld benefits are not lost: at FRA, SSA excludes the fully withheld months from the early-retirement reduction and recomputes a higher monthly benefit — a deferral repaid month by month, not a lump sum and not a fine.

On the tax side, the employee share of Social Security tax is 6.2% on wages up to the 2026 wage base of $184,500 (2025: $176,100), plus 1.45% Medicare tax with no cap. A worked example ties the layers together: earnings of $34,480 in 2026 produce an excess of $10,000 over the limit and $5,000 of withheld benefits; the same wages cost about $2,138 in employee Social Security tax (34,480 × 6.2%) and about $500 of Medicare tax. For § 86, a single filer with $24,000 of benefits and $30,000 of wages has provisional income of $42,000 and, under the Publication 915 worksheet, $11,300 of taxable benefits (85% of the $8,000 above $34,000, plus the $4,500 first-tier cap, below the $20,400 ceiling of 85% of benefits). Benefits arrive on Form SSA-1099; voluntary withholding on benefits uses Form W-4V at 7%, 10%, 12%, or 22%. California does not tax Social Security benefits (Rev. & Tax. Code § 17131), taxes wages normally, and has no earnings test of its own.

*Note: Personal study notes, not tax, financial, or Social Security advice. Sources: Social Security Act § 203 (42 U.S.C. § 403); SSA 2026 fact sheet (earnings limits $24,480/$65,160; wage base $184,500); IRC §§ 86, 3101, 1401; IRS Publication 915 and Form W-4V instructions.*

---

## Español (traducción de estudio)

Trabajar mientras se cobra el Seguro Social mezcla tres sistemas distintos. La prueba de ingresos (retirement earnings test, § 203 de la Ley del Seguro Social, 42 U.S.C. § 403) solo decide si la SSA retiene temporalmente prestaciones: no es un impuesto. La segunda capa es el impuesto sobre la nómina: el salario sigue sujeto a FICA y el trabajo autónomo a SECA, sin exención por ya estar cobrando. La tercera es el impuesto sobre la renta: el salario es ingreso ordinario y además eleva el ingreso provisional del § 86 del IRC, arrastrando hasta el 85% de las prestaciones a tributación.

En 2026, quien esté todo el año por debajo de la edad plena de jubilación (FRA, 67 años para nacidos en 1960 o después) pierde 1 dólar de prestaciones por cada 2 dólares de ingresos laborales que superen 24.480 dólares (2025: 23.400). En el año en que se alcanza la FRA solo cuentan los ingresos anteriores al mes de la FRA, el límite sube a 65.160 dólares (2025: 62.160) y la retención baja a 1 por cada 3. Desde el mes de la FRA la prueba desaparece. Solo cuentan salarios e ingresos netos del trabajo autónomo; pensiones, retiros de IRA, dividendos, ganancias de capital y rentas no cuentan. Existe además una regla mensual del primer año (24.480 ÷ 12 = 2.040 dólares en 2026). Lo retenido no se pierde: al llegar a la FRA, la SSA excluye los meses totalmente retenidos del cálculo de reducción por jubilación anticipada y recalcula una prestación mensual mayor; es un aplazamiento que se devuelve mes a mes, no una multa ni un pago único.

En lo fiscal, la parte del empleado del impuesto del Seguro Social es el 6,2% sobre salarios hasta la base de 2026 de 184.500 dólares (2025: 176.100), más el 1,45% de Medicare sin tope. Ejemplo completo: ingresos de 34.480 dólares en 2026 dejan un exceso de 10.000 sobre el límite y 5.000 dólares de prestaciones retenidas; ese mismo salario paga unos 2.138 dólares de impuesto del Seguro Social del empleado y unos 500 de Medicare. Para el § 86, un contribuyente soltero con 24.000 dólares de prestaciones y 30.000 de salario tiene un ingreso provisional de 42.000 y, según la hoja de trabajo de la Publicación 915, 11.300 dólares de prestaciones gravables (el 85% de los 8.000 sobre 34.000, más el tope del primer tramo de 4.500, por debajo del techo de 20.400). Las prestaciones llegan en el Formulario SSA-1099 y la retención voluntaria sobre ellas usa el Formulario W-4V (7%, 10%, 12% o 22%). California no grava las prestaciones del Seguro Social (Rev. & Tax. Code § 17131), grava el salario con normalidad y no tiene prueba de ingresos propia.

*Nota: notas personales de estudio, no asesoría fiscal ni de Seguro Social. Fuentes: § 203 de la Ley del Seguro Social (42 U.S.C. § 403); hoja de datos 2026 de la SSA (límites 24.480/65.160; base salarial 184.500); IRC §§ 86, 3101, 1401; Publicación 915 del IRS e instrucciones del Formulario W-4V.*

---

## 한국어 (초역, 원어민 감수 대기)

사회보장 연금을 받으면서 일하면 세 개의 서로 다른 제도가 한꺼번에 움직입니다. 은퇴 소득 테스트(retirement earnings test, 사회보장법 §203, 42 U.S.C. §403)는 SSA가 급여를 일시적으로 유보할지만 정할 뿐 세금이 아닙니다. 두 번째 층은 급여세로, 임금은 FICA, 자영업 소득은 SECA가 그대로 적용되며 이미 연금을 받고 있다는 이유로 면제되지 않습니다. 세 번째 층은 소득세로, 임금은 일반소득인 동시에 IRC §86의 잠정소득(provisional income)을 끌어올려 연금의 최대 85%까지 과세로 끌어들입니다.

2026년 기준, 완전 은퇴 연령(FRA, 1960년 이후 출생자는 67세)에 연중 도달하지 않는 사람은 노동소득이 24,480달러(2025년 23,400달러)를 넘는 부분에 대해 2달러 초과당 1달러의 급여가 유보됩니다. FRA에 도달하는 해에는 FRA 월 이전 소득만 셈하고 한도가 65,160달러(2025년 62,160달러)로 오르며 3달러 초과당 1달러로 완화되고, FRA 월부터는 테스트가 사라집니다. 소득으로 치는 것은 임금과 자영업 순소득뿐이며 연금, IRA 인출, 배당, 양도차익, 임대료는 들어가지 않습니다. 첫해에는 월별 유예 규칙(2026년 24,480÷12＝2,040달러)도 있습니다. 유보된 급여는 사라지지 않습니다. FRA에 도달하면 SSA가 전액 유보된 달들을 조기 수령 감액 개월 수에서 빼고 월 급여를 다시 계산해 높이므로, 벌금이 아니라 매달 돌려받는 이연입니다.

세금 쪽에서는 근로자 부담 사회보장세가 2026년 임금 상한 184,500달러(2025년 176,100달러)까지 6.2%, Medicare 세는 상한 없이 1.45%입니다. 종합 예시로, 2026년 임금이 34,480달러이면 한도 초과분은 10,000달러이고 유보 급여는 5,000달러이며, 같은 임금에 대한 근로자 사회보장세는 약 2,138달러, Medicare 세는 약 500달러입니다. §86에서는 연금 24,000달러에 임금 30,000달러인 단독 신고자의 잠정소득이 42,000달러가 되고, Publication 915 워크시트로는 과세 연금이 11,300달러(34,000 초과분 8,000의 85%인 6,800에 1구간 상한 4,500을 더한 값, 연금의 85% 상한 20,400에는 못 미침)가 됩니다. 급여는 Form SSA-1099로 확인하고, 급여에 대한 자발적 원천징수는 Form W-4V로 7%, 10%, 12%, 22% 중 고릅니다. 캘리포니아는 사회보장 급여에 주 소득세를 매기지 않고(R&TC §17131) 임금은 정상 과세하며, 주 자체의 소득 테스트는 없습니다.

*주: 개인 학습 노트이며 세무·사회보장 자문이 아닙니다. 출처: 사회보장법 §203(42 U.S.C. §403); SSA 2026년 팩트시트(소득 한도 24,480/65,160달러, 임금 상한 184,500달러); IRC §§86, 3101, 1401; IRS Publication 915와 Form W-4V 안내. 초역으로 원어민 감수 대기 중입니다.*

---

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

Vừa lãnh trợ cấp An sinh Xã hội vừa đi làm là ba hệ thống khác nhau chạy cùng lúc. Phép thử thu nhập khi nghỉ hưu (retirement earnings test, §203 của Đạo luật An sinh Xã hội, 42 U.S.C. §403) chỉ quyết định việc SSA tạm giữ lại bao nhiêu trợ cấp — đó không phải là thuế. Lớp thứ hai là thuế payroll: tiền lương vẫn chịu FICA và thu nhập tự doanh vẫn chịu SECA, không có miễn trừ vì đã lãnh trợ cấp. Lớp thứ ba là thuế thu nhập: tiền lương là thu nhập thường, đồng thời nâng thu nhập tạm tính (provisional income) theo IRC §86, kéo tối đa 85% trợ cấp vào diện chịu thuế.

Năm 2026, người chưa đạt tuổi hưu toàn phần (FRA — 67 tuổi với người sinh từ 1960 trở đi) trong cả năm sẽ bị giữ 1 đô la trợ cấp cho mỗi 2 đô la thu nhập lao động vượt 24.480 đô la (2025: 23.400). Trong năm đạt FRA, chỉ tính thu nhập trước tháng đạt FRA, hạn mức tăng lên 65.160 đô la (2025: 62.160) và mức giữ giảm còn 1 trên mỗi 3; từ tháng đạt FRA, phép thử biến mất. Chỉ tiền lương và thu nhập tự doanh ròng mới được tính; lương hưu, rút IRA, cổ tức, lãi vốn và tiền thuê nhà đều không tính. Năm đầu còn có quy tắc ân hạn theo tháng (2026: 24.480 ÷ 12 = 2.040 đô la). Phần trợ cấp bị giữ không mất đi: khi tới FRA, SSA loại các tháng bị giữ toàn bộ khỏi số tháng giảm trừ do lãnh sớm và tính lại mức trợ cấp hằng tháng cao hơn — đó là khoản hoãn được trả dần từng tháng, không phải tiền phạt hay trả một lần.

Về thuế, phần thuế An sinh Xã hội do người lao động chịu là 6,2% trên tiền lương tới mức trần 2026 là 184.500 đô la (2025: 176.100), cộng 1,45% thuế Medicare không trần. Ví dụ gộp: tiền lương 34.480 đô la năm 2026 tạo phần vượt hạn mức 10.000 đô la và 5.000 đô la trợ cấp bị giữ; cùng khoản lương đó chịu khoảng 2.138 đô la thuế An sinh Xã hội phần người lao động và khoảng 500 đô la thuế Medicare. Về §86, người khai đơn thân với 24.000 đô la trợ cấp và 30.000 đô la tiền lương có thu nhập tạm tính 42.000 đô la và, theo bảng tính của Publication 915, phần trợ cấp chịu thuế là 11.300 đô la (85% của 8.000 đô la vượt 34.000, cộng mức trần bậc một 4.500, vẫn dưới trần 20.400 đô la bằng 85% trợ cấp). Trợ cấp được báo trên Form SSA-1099; khấu trừ tự nguyện trên trợ cấp dùng Form W-4V với các mức 7%, 10%, 12% hoặc 22%. California không đánh thuế tiểu bang lên trợ cấp An sinh Xã hội (Rev. & Tax. Code §17131), đánh thuế tiền lương bình thường và không có phép thử thu nhập riêng.

*Ghi chú: ghi chép học tập cá nhân, không phải tư vấn thuế hay An sinh Xã hội. Nguồn: §203 Đạo luật An sinh Xã hội (42 U.S.C. §403); bảng số liệu 2026 của SSA (hạn mức 24.480/65.160; trần lương 184.500); IRC §§86, 3101, 1401; Publication 915 của IRS và hướng dẫn Form W-4V. Bản dịch sơ bộ, chờ hiệu đính.*

---

## हिन्दी (प्रारंभिक अनुवाद, समीक्षा लंबित)

Social Security लेते हुए काम करना तीन अलग प्रणालियों का एक साथ चलना है। Retirement earnings test (Social Security Act §203, 42 U.S.C. §403) केवल यह तय करता है कि SSA कितना लाभ अस्थायी रूप से रोकेगा — यह कर नहीं है। दूसरी परत payroll कर है: मज़दूरी पर FICA और स्वरोज़गार आय पर SECA सामान्य रूप से लगता रहता है, लाभ ले रहे होने से कोई छूट नहीं मिलती। तीसरी परत आयकर है: मज़दूरी सामान्य आय है और साथ ही IRC §86 की provisional income बढ़ाकर लाभ का अधिकतम 85% तक कर-योग्य बना देती है।

2026 में, जो व्यक्ति पूरे वर्ष full retirement age (FRA — 1960 या बाद में जन्मे लोगों के लिए 67 वर्ष) से नीचे है, उसकी श्रम आय 24,480 डॉलर (2025 में 23,400) से ऊपर के हर 2 डॉलर पर 1 डॉलर लाभ रोका जाता है। जिस वर्ष FRA आता है, केवल FRA माह से पहले की आय गिनी जाती है, सीमा 65,160 डॉलर (2025 में 62,160) हो जाती है और रोक हर 3 डॉलर पर 1 डॉलर रह जाती है; FRA माह से test समाप्त हो जाता है। आय में केवल मज़दूरी और शुद्ध स्वरोज़गार आय गिनी जाती है; पेंशन, IRA निकासी, लाभांश, पूंजीगत लाभ और किराया नहीं गिने जाते। पहले वर्ष के लिए मासिक छूट नियम (2026 में 24,480 ÷ 12 = 2,040 डॉलर) भी है। रोका गया लाभ खोता नहीं है: FRA पर SSA पूरे रोके गए महीनों को शीघ्र-सेवानिवृत्ति कटौती के महीनों से निकालकर मासिक लाभ फिर से गिनकर बढ़ा देता है — यह जुर्माना नहीं, बल्कि महीने-दर-महीने लौटने वाला स्थगन है।

कर पक्ष में कर्मचारी का Social Security कर 2026 की मज़दूरी सीमा 184,500 डॉलर (2025 में 176,100) तक 6.2% है और Medicare कर बिना सीमा के 1.45% है। संयुक्त उदाहरण: 2026 में 34,480 डॉलर मज़दूरी पर सीमा से अधिक भाग 10,000 डॉलर और रोका गया लाभ 5,000 डॉलर बनता है; उसी मज़दूरी पर कर्मचारी Social Security कर लगभग 2,138 डॉलर और Medicare कर लगभग 500 डॉलर है। §86 में, 24,000 डॉलर लाभ और 30,000 डॉलर मज़दूरी वाले अकेले filer की provisional income 42,000 डॉलर होती है और Publication 915 worksheet से कर-योग्य लाभ 11,300 डॉलर बनता है (34,000 से ऊपर के 8,000 का 85% यानी 6,800, जमा पहले स्तर की सीमा 4,500; लाभ के 85% की छत 20,400 से नीचे)। लाभ Form SSA-1099 पर आता है और लाभ पर स्वैच्छिक withholding Form W-4V से 7%, 10%, 12% या 22% चुना जाता है। कैलिफ़ोर्निया Social Security लाभों पर राज्य आयकर नहीं लगाता (Rev. & Tax. Code §17131), मज़दूरी पर सामान्य कर लगाता है और उसका अपना कोई earnings test नहीं है।

*टिप्पणी: व्यक्तिगत अध्ययन नोट्स, कर या Social Security सलाह नहीं। स्रोत: Social Security Act §203 (42 U.S.C. §403); SSA 2026 fact sheet (आय सीमाएँ 24,480/65,160 डॉलर, मज़दूरी आधार 184,500 डॉलर); IRC §§86, 3101, 1401; IRS Publication 915 व Form W-4V निर्देश। यह प्रारंभिक अनुवाद है, समीक्षा लंबित है।*

## 补译增量（2026-11-12 15:55轮：韩／越／印三语各补 2 项中文主文已有细节）

### 한국어 (初译待校)

1. 급여세 세율 구조 보충: 근로자 FICA는 두 조각으로 나뉩니다. § 3101(a)의 사회보장 부분 6.2%는 § 3121(a)(1)의 임금 상한까지만 부과되고, § 3101(b)의 Medicare 부분 1.45%에는 상한이 없습니다. 자영업자는 Schedule SE에서 사회보장 12.4%와 Medicare 2.9%를 합쳐 납부하며, 임금 상한은 같은 기준을 씁니다.
2. 소득 인정 경계 보충: 파트타임인지 풀타임인지는 따지지 않고 금액만 봅니다. 가족 회사에서 일하는 경우처럼 임금의 진정성과 합리성이 의심되는 상황에서는 SSA가 별도로 심사합니다. 본 글에서는 이 심사의 세부로 들어가지 않습니다.

### Tiếng Việt (初译待校)

1. Bổ sung cấu trúc thuế suất thuế payroll: FICA phần người lao động gồm hai mảnh — phần An sinh Xã hội 6,2% theo § 3101(a) chỉ áp dụng tới trần lương của § 3121(a)(1), và phần Medicare 1,45% theo § 3101(b) không có trần. Người tự làm chủ nộp qua Schedule SE với 12,4% An sinh Xã hội cộng 2,9% Medicare, và trần lương dùng cùng một chuẩn.
2. Bổ sung ranh giới tính thu nhập lao động: không phân biệt việc bán thời gian hay toàn thời gian, chỉ nhìn vào số tiền. Trong các tình huống như làm việc cho công ty của người nhà, nơi tính chân thực và hợp lý của tiền lương bị đặt dấu hỏi, SSA sẽ kiểm tra riêng. Bài viết này không đi sâu vào chi tiết của việc kiểm tra đó.

### हिन्दी (初译待校)

1. Payroll कर की दर-संरचना पर पूरक: कर्मचारी FICA के दो टुकड़े हैं — § 3101(a) का Social Security भाग 6.2% केवल § 3121(a)(1) की मज़दूरी-सीमा तक लगता है, और § 3101(b) का Medicare भाग 1.45% बिना किसी सीमा के लगता है। स्व-रोज़गारी व्यक्ति Schedule SE से Social Security 12.4% और Medicare 2.9% मिलाकर देता है, और मज़दूरी-सीमा का मानक वही रहता है।
2. श्रम-आय गणना की सीमा पर पूरक: part-time है या full-time, यह नहीं देखा जाता, केवल राशि देखी जाती है। परिवार की कंपनी में काम करने जैसे मामलों में, जहाँ मज़दूरी की सत्यता और औचित्य पर संदेह हो, SSA अलग से जाँच करता है। इस लेख में उस जाँच के विवरण में नहीं जाया गया है।

