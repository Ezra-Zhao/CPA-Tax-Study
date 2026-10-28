# 自雇税怎么算：SECA 税率、工资上限与一半抵扣

这篇讲什么：
- 前几篇把个人所得税的计算结构和资本利得拆过了，这一篇补上自雇者绕不开的另一套税：自雇税（self-employment tax）。它不在所得税的税档表里，是单独一套供社会保障和医疗保险的税，自由职业者、个体户和合伙人都要过这一关。
- 核心数字先记住四个：合计税率 15.3%，应税基数只算净收入的 92.35%，2026 年社会保障部分的应税上限是 184,500 美元，交完的自雇税有一半可以在算所得税时扣掉。
- 出处都标在正文里：税率和结构看《国内税收法典》（Internal Revenue Code, IRC）第 1401 至 1403 条，上限数字看社会保障署（SSA）公布的年度应税工资基数。

---

## 一、自雇税是什么：雇员和雇主的两半，自己一个人交

### 中文
上班族交的工资税叫 FICA：社会保障税 12.4% 加医疗保险税 2.9%，合计 15.3%，其中一半 7.65% 从工资里扣，另一半 7.65% 由雇主出，雇员在工资单上只看得见自己那一半。自雇者没有雇主替他出另一半，《自雇者社会保障税法》（Self-Employment Contributions Act, SECA，编于 IRC 第 1401 至 1403 条）就把两半合在一起，由本人就自雇净收入（net earnings from self-employment, IRC 第 1402 条定义）一次交清，这就是自雇税。

谁要交，看门槛：自雇净收入达到 400 美元就要申报并缴税，用附表 SE（Schedule SE）计算，随 1040 表一起报。收入来源通常是个体户的附表 C 利润、农场附表 F，以及合伙企业经 K-1 表分来的自雇收入。反过来，股息、利息和一般情况下的租金收入不是自雇收入，不进这套税，这一点在 REG 备考里是常设的辨析点。S 公司股东从分红里拿到的钱同样不算自雇收入，只有给自己发的合理工资走工资税，这正是之前 Watson 案讲工资定性的原因。

还有一层衔接：如果一个人既有 W-2 工资又有自雇收入，社会保障部分的年度上限是合并算的。W-2 工资先占用上限额度，剩余额度才轮到自雇收入交 12.4%，附表 SE 里就是按这个顺序算的。医疗保险的 2.9% 没有上限，多少收入都全额交。

### English
The payroll tax employees pay is called FICA: 12.4% for Social Security plus 2.9% for Medicare, 15.3% combined. Half, 7.65%, is withheld from wages, and the employer pays the other 7.65%, so an employee only ever sees one half on a pay stub. A self-employed person has no employer to carry the second half. The Self-Employment Contributions Act (SECA, Internal Revenue Code sections 1401 through 1403) merges both halves into one tax on net earnings from self-employment, as defined in section 1402, paid by the individual. That is the self-employment tax.

The filing threshold is low: net earnings of $400 or more trigger the tax, computed on Schedule SE and filed with Form 1040. Typical sources are sole-proprietor profit on Schedule C, farm income on Schedule F, and a partner's distributive share reported on Schedule K-1. By contrast, dividends, interest, and — in the general case — rental income are not self-employment earnings and stay out of this tax, a standard distinction on the REG exam. An S corporation shareholder's distributions are likewise outside the tax; only the reasonable salary the shareholder pays himself runs through payroll tax, which is exactly the issue the Watson case study covered.

One coordination rule matters for people with both kinds of income. The annual Social Security wage base applies to wages and self-employment earnings combined. W-2 wages consume the limit first, and only the remaining room is subject to the 12.4% rate on Schedule SE. The 2.9% Medicare portion has no cap and applies to every dollar.

### Español (译稿)
El impuesto sobre la nómina que pagan los empleados se llama FICA: 12,4% para la Seguridad Social más 2,9% para Medicare, 15,3% en total. La mitad, 7,65%, se retiene del salario y la otra mitad, 7,65%, la paga el empleador, así que el empleado solo ve una mitad en su recibo. Quien trabaja por cuenta propia no tiene empleador que cargue con la segunda mitad. La Ley de Contribuciones del Trabajo por Cuenta Propia (SECA, secciones 1401 a 1403 del Código de Rentas Internas, IRC) fusiona ambas mitades en un solo impuesto sobre los ingresos netos del trabajo autónomo, definidos en la sección 1402, que paga la propia persona. Ese es el impuesto del trabajo autónomo (self-employment tax).

El umbral es bajo: ingresos netos de 400 dólares o más activan el impuesto, que se calcula en el Anexo SE (Schedule SE) y se presenta con el Formulario 1040. Las fuentes típicas son el beneficio del empresario individual en el Anexo C, el ingreso agrícola en el Anexo F y la participación de un socio informada en el Anexo K-1. En cambio, los dividendos, los intereses y, en el caso general, los alquileres no son ingresos del trabajo autónomo y quedan fuera de este impuesto, una distinción clásica en el examen REG. Las distribuciones de un accionista de una corporación S tampoco están sujetas; solo el salario razonable que se paga a sí mismo pasa por el impuesto sobre la nómina, que es justo el tema del caso Watson ya estudiado.

Una regla de coordinación importa para quien tiene ambos tipos de ingreso. El tope anual de la base salarial de la Seguridad Social se aplica sumando salarios e ingresos autónomos. Los salarios W-2 consumen primero el límite, y solo el espacio restante soporta el 12,4% en el Anexo SE. La parte de Medicare, 2,9%, no tiene tope y se aplica a cada dólar.

### 한국어 (초역, 원어민 감수 대기)

직원이 내는 급여세는 FICA라고 부른다: 사회보장세 12.4%에 의료보험세(Medicare) 2.9%를 더해 합계 15.3%이며, 그중 절반인 7.65%는 임금에서 원천징수되고 나머지 절반 7.65%는 고용주가 부담하므로, 직원은 급여명세서에서 자기 몫 절반만 본다. 자영업자에게는 두 번째 절반을 대신 내 줄 고용주가 없다. 자영업자 기여법(Self-Employment Contributions Act, SECA, IRC 제1401조부터 제1403조에 편제)이 두 절반을 하나로 합쳐, 제1402조에 정의된 자영업 순소득(net earnings from self-employment)에 대해 본인이 한 번에 내도록 한 것이 바로 자영업세이다.

신고 문턱은 낮다: 자영업 순소득이 400달러 이상이면 신고하고 세금을 내야 하며, Schedule SE로 계산해 Form 1040과 함께 제출한다. 전형적인 원천은 개인사업자의 Schedule C 이익, 농장의 Schedule F 소득, 그리고 파트너가 Schedule K-1로 나눠 받는 지분 소득이다. 반대로 배당, 이자, 그리고 일반적인 경우의 임대소득은 자영업 소득이 아니어서 이 세금에 들어가지 않으며, 이는 REG 시험에서 단골로 나오는 구별 포인트이다. S 법인 주주가 배분으로 받는 돈도 마찬가지로 이 세금에 들어가지 않고, 본인에게 지급하는 합리적 급여만 급여세를 거치는데, 이것이 바로 앞에서 다룬 Watson 판례가 급여의 성격을 다툰 이유이다.

두 종류 소득을 모두 가진 사람에게는 하나의 조정 규칙이 중요하다. 연간 사회보장 임금 상한은 임금과 자영업 소득을 합쳐서 적용된다. W-2 임금이 먼저 상한을 소진하고, 남은 여유분에 대해서만 Schedule SE에서 12.4%가 적용된다. 의료보험 부분 2.9%는 상한이 없어 모든 달러에 적용된다.

### Tiếng Việt (bản dịch sơ bộ, chờ người bản ngữ hiệu đính)

Thuế tiền lương mà người lao động đóng gọi là FICA: thuế An sinh xã hội 12,4% cộng thuế Medicare 2,9%, tổng cộng 15,3%, trong đó một nửa 7,65% khấu trừ từ lương, nửa còn lại 7,65% do chủ lao động đóng, nên người lao động chỉ thấy một nửa của mình trên phiếu lương. Người tự làm chủ không có chủ lao động gánh nửa còn lại. Đạo luật Đóng góp của Người tự làm chủ (Self-Employment Contributions Act, SECA, quy định tại các điều 1401 đến 1403 của IRC) gộp cả hai nửa thành một sắc thuế đánh trên thu nhập ròng từ tự làm chủ (net earnings from self-employment, định nghĩa tại điều 1402), do chính cá nhân đóng một lần. Đó là thuế tự làm chủ.

Ngưỡng phải khai rất thấp: thu nhập ròng từ tự làm chủ đạt 400 đô la là phải khai báo và nộp thuế, tính bằng Schedule SE, nộp cùng Form 1040. Nguồn điển hình là lợi nhuận của hộ kinh doanh cá thể trên Schedule C, thu nhập nông trại trên Schedule F, và phần thu nhập của thành viên hợp danh nhận qua Schedule K-1. Ngược lại, cổ tức, lãi và — trong trường hợp thông thường — thu nhập cho thuê không phải thu nhập tự làm chủ, không thuộc sắc thuế này, đây là điểm phân biệt thường trực trong ôn thi REG. Tiền phân phối mà cổ đông công ty S nhận cũng không phải thu nhập tự làm chủ; chỉ mức lương hợp lý tự trả cho mình mới đi qua thuế tiền lương, đó chính là lý do vụ Watson đã học trước đây bàn về tính chất tiền lương.

Còn một quy tắc phối hợp quan trọng với người có cả hai loại thu nhập. Trần hàng năm của cơ sở lương An sinh xã hội áp dụng gộp lương và thu nhập tự làm chủ. Lương W-2 dùng trước hạn mức trần, phần hạn mức còn lại mới đến lượt thu nhập tự làm chủ chịu 12,4% trên Schedule SE. Phần Medicare 2,9% không có trần, bao nhiêu thu nhập cũng đóng toàn bộ.

### हिन्दी (अनुवाद, मूल-भाषी समीक्षा लंबित)

कर्मचारियों द्वारा दिया जाने वाला वेतन कर FICA कहलाता है: सामाजिक सुरक्षा कर 12.4% और Medicare कर 2.9%, कुल 15.3%, जिसमें से आधा 7.65% वेतन से काटा जाता है और दूसरा आधा 7.65% नियोक्ता देता है, कर्मचारी को वेतन पर्ची पर केवल अपना आधा ही दिखता है। स्व-रोज़गार वाले के पास दूसरा आधा देने वाला कोई नियोक्ता नहीं होता। स्व-रोज़गार अंशदान अधिनियम (Self-Employment Contributions Act, SECA, IRC धारा 1401 से 1403 में संहिताबद्ध) दोनों आधों को एक साथ जोड़कर, धारा 1402 में परिभाषित स्व-रोज़गार शुद्ध आय (net earnings from self-employment) पर व्यक्ति द्वारा एक बार में दिया जाने वाला कर बना देता है — यही स्व-रोज़गार कर है।

किसे देना है, सीमा देखें: स्व-रोज़गार शुद्ध आय 400 डॉलर तक पहुँचते ही घोषणा और कर देना होता है, Schedule SE से गणना करके Form 1040 के साथ दाखिल किया जाता है। आय के स्रोत सामान्यतः एकल स्वामित्व के Schedule C लाभ, फ़ार्म Schedule F, और साझेदारी से Schedule K-1 द्वारा बँटी स्व-रोज़गार आय होते हैं। इसके विपरीत, लाभांश, ब्याज और सामान्य स्थिति में किराया आय स्व-रोज़गार आय नहीं है, इस कर में नहीं आती — यह REG की तैयारी में स्थायी विभेद बिंदु है। S निगम के शेयरधारक को वितरण से मिली राशि भी स्व-रोज़गार आय नहीं गिनी जाती, केवल स्वयं को दिया गया उचित वेतन ही वेतन कर से गुज़रता है, यही पहले वाले Watson मामले में वेतन के स्वरूप पर चर्चा का कारण था।

एक और कड़ी भी है: यदि किसी व्यक्ति के पास W-2 वेतन भी है और स्व-रोज़गार आय भी, तो सामाजिक सुरक्षा भाग की वार्षिक सीमा दोनों को मिलाकर लगती है। W-2 वेतन पहले सीमा का हिस्सा उपयोग करता है, बची हुई सीमा पर ही स्व-रोज़गार आय पर 12.4% लगता है, Schedule SE में इसी क्रम से गणना होती है। Medicare के 2.9% की कोई सीमा नहीं है, जितनी भी आय हो पूरी पर लगता है।

---

## 二、四步算完：净收入、92.35%、税率、上限

### 中文
计算顺序是固定的四步，拿 2026 年自雇净收入 80,000 美元、没有 W-2 工资的人举例走一遍。

第一步，定净收入。营业收入减去可扣的经营费用，得到自雇净收入 80,000 美元，这一步在附表 C 上完成，费用怎么认是另一套规则，本篇不展开。

第二步，乘以 92.35%。IRC 第 1402 条第 (a)(12) 项把应税基数定在净收入的 92.35%，道理是模拟雇员口径：雇主出的那一半工资税本来就不算雇员的工资，所以自雇者先把相当于雇主份额的 7.65% 从基数里剔出去，再计税。80,000 乘以 92.35% 等于 73,880 美元。

第三步，套税率并卡上限。社会保障部分 12.4% 只对上限以内的部分征收：2026 年的应税工资基数（contribution and benefit base）是 184,500 美元，由社会保障署按全国平均工资指数公布，2025 年是 176,100 美元。例子里的 73,880 美元在上限之内，所以 12.4% 和 2.9% 全额适用，73,880 乘以 15.3% 等于 11,303.64 美元，约 11,304 美元。如果应税基数超过 184,500 美元，超出部分只交 2.9% 的医疗保险部分，不再交 12.4%。

第四步，高收入再看 0.9%。附加医疗保险税（Additional Medicare Tax, IRC 第 1401 条第 (b)(2) 款）对超过门槛的自雇收入另征 0.9%：单身 200,000 美元、夫妻合报 250,000 美元、夫妻分报 125,000 美元，门槛由法条写死、不随通胀调整，用 8959 表计算。它没有雇主对应份额，后面讲的一半抵扣也不包括这一块。

### English
The computation runs in four fixed steps. Take a taxpayer with $80,000 of net self-employment earnings in 2026 and no W-2 wages.

Step one: determine net earnings. Business receipts minus deductible business expenses give net earnings of $80,000, worked out on Schedule C; the rules for what counts as an expense are a separate topic.

Step two: multiply by 92.35%. Section 1402(a)(12) sets the tax base at 92.35% of net earnings. The logic mirrors the employee side: the employer's share of payroll tax is not part of an employee's wages, so the self-employed base is first reduced by the employer-equivalent 7.65%. Here, $80,000 times 92.35% equals $73,880.

Step three: apply the rates against the cap. The 12.4% Social Security portion applies only up to the wage base: the contribution and benefit base for 2026 is $184,500, published by the Social Security Administration from the national average wage index, up from $176,100 for 2025. The example's $73,880 sits below the cap, so both portions apply in full: $73,880 times 15.3% equals $11,303.64, about $11,304. If the adjusted base exceeded $184,500, the excess would bear only the 2.9% Medicare portion.

Step four: check the extra 0.9%. The Additional Medicare Tax under section 1401(b)(2) adds 0.9% on self-employment income above statutory thresholds — $200,000 for single filers, $250,000 for joint filers, $125,000 for married filing separately. The thresholds are fixed by statute and are not inflation-adjusted, and the tax is computed on Form 8959. It has no employer counterpart, and it is excluded from the one-half deduction covered next.

### Español (译稿)
El cálculo sigue cuatro pasos fijos. Tomemos a un contribuyente con 80.000 dólares de ingresos netos del trabajo autónomo en 2026 y sin salarios W-2.

Paso uno: determinar el ingreso neto. Los ingresos del negocio menos los gastos deducibles dan 80.000 dólares, calculados en el Anexo C; las reglas sobre qué cuenta como gasto son otro tema.

Paso dos: multiplicar por 92,35%. La sección 1402(a)(12) fija la base imponible en el 92,35% de los ingresos netos. La lógica replica el lado del empleado: la parte del impuesto sobre la nómina que paga el empleador no forma parte del salario del empleado, así que la base del autónomo se reduce primero por el 7,65% equivalente al empleador. Aquí, 80.000 por 92,35% da 73.880 dólares.

Paso tres: aplicar las tasas contra el tope. La parte de Seguridad Social, 12,4%, solo se aplica hasta la base salarial: la base de cotización y prestaciones (contribution and benefit base) de 2026 es de 184.500 dólares, publicada por la Administración de la Seguridad Social según el índice nacional de salarios medios, frente a 176.100 dólares en 2025. Los 73.880 dólares del ejemplo quedan por debajo del tope, así que ambas partes se aplican por completo: 73.880 por 15,3% da 11.303,64 dólares, unos 11.304 dólares. Si la base ajustada superara los 184.500 dólares, el exceso solo soportaría la parte de Medicare del 2,9%.

Paso cuatro: revisar el 0,9% adicional. El Impuesto Adicional de Medicare (Additional Medicare Tax), sección 1401(b)(2), añade un 0,9% sobre los ingresos autónomos que superen umbrales fijados por ley: 200.000 dólares para solteros, 250.000 para declaración conjunta y 125.000 para casados que declaran por separado. Los umbrales no se ajustan por inflación y el impuesto se calcula en el Formulario 8959. No tiene parte empresarial equivalente y queda fuera de la deducción de la mitad que sigue.

### 한국어 (초역, 원어민 감수 대기)

계산 순서는 고정된 네 단계이며, 2026년 자영업 순소득 80,000달러에 W-2 임금이 없는 사람을 예로 들어 한 번 따라가 보자.

첫째 단계, 순소득을 정한다. 영업수입에서 공제 가능한 사업비용을 빼면 자영업 순소득 80,000달러가 되며, 이 단계는 Schedule C에서 완성되고, 비용을 어떻게 인정하는지는 별도의 규칙 체계로 이 글에서는 전개하지 않는다.

둘째 단계, 92.35%를 곱한다. IRC 제1402조 (a)(12)항은 과세 기준을 순소득의 92.35%로 정한다. 그 논리는 직원 기준을 모방한 것이다: 고용주가 내는 절반의 급여세는 원래 직원의 임금에 포함되지 않으므로, 자영업자는 먼저 고용주 몫에 해당하는 7.65%를 기준에서 빼고 나서 세금을 계산한다. 80,000달러에 92.35%를 곱하면 73,880달러이다.

셋째 단계, 세율을 적용하고 상한을 건다. 사회보장 부분 12.4%는 상한 이내 부분에만 부과된다: 2026년의 과세 임금 기준(contribution and benefit base)은 184,500달러로, 사회보장청(SSA)이 전국 평균임금 지수에 따라 공표하며, 2025년은 176,100달러였다. 예시의 73,880달러는 상한 안에 있으므로 12.4%와 2.9%가 전액 적용되어, 73,880달러에 15.3%를 곱하면 11,303.64달러, 약 11,304달러이다. 과세 기준이 184,500달러를 초과하면 초과 부분은 2.9%의 의료보험 부분만 내고 12.4%는 더 내지 않는다.

넷째 단계, 고소득자는 0.9%를 다시 본다. 추가 의료보험세(Additional Medicare Tax, IRC 제1401조 (b)(2)항)는 문턱을 넘는 자영업 소득에 0.9%를 추가로 부과한다: 단독 200,000달러, 부부 합산 신고 250,000달러, 부부 분리 신고 125,000달러이며, 문턱은 법조문에 고정되어 물가 조정을 하지 않고, Form 8959로 계산한다. 여기에는 고용주 대응 몫이 없으며, 뒤에서 말할 절반 공제에도 이 부분은 포함되지 않는다.

### Tiếng Việt (bản dịch sơ bộ, chờ người bản ngữ hiệu đính)

Thứ tự tính cố định bốn bước, lấy ví dụ người có thu nhập ròng tự làm chủ năm 2026 là 80.000 đô la, không có lương W-2 để đi một lượt.

Bước một, xác định thu nhập ròng. Doanh thu kinh doanh trừ chi phí kinh doanh được khấu trừ, được thu nhập ròng tự làm chủ 80.000 đô la, bước này hoàn thành trên Schedule C, chi phí được công nhận thế nào là một bộ quy tắc khác, bài này không triển khai.

Bước hai, nhân với 92,35%. Khoản (a)(12) điều 1402 IRC quy định cơ sở chịu thuế là 92,35% thu nhập ròng, lý do là mô phỏng chuẩn của người lao động: nửa thuế tiền lương do chủ lao động đóng vốn không tính vào lương của người lao động, nên người tự làm chủ trước tiên loại khỏi cơ sở phần tương đương phần của chủ lao động 7,65%, rồi mới tính thuế. 80.000 nhân 92,35% bằng 73.880 đô la.

Bước ba, áp thuế suất và chặn trần. Phần An sinh xã hội 12,4% chỉ đánh trên phần trong trần: cơ sở lương chịu thuế (contribution and benefit base) năm 2026 là 184.500 đô la, do Cơ quan An sinh Xã hội (SSA) công bố theo chỉ số lương bình quân toàn quốc, năm 2025 là 176.100 đô la. 73.880 đô la trong ví dụ nằm trong trần, nên 12,4% và 2,9% áp toàn bộ, 73.880 nhân 15,3% bằng 11.303,64 đô la, khoảng 11.304 đô la. Nếu cơ sở chịu thuế vượt 184.500 đô la, phần vượt chỉ đóng phần Medicare 2,9%, không đóng 12,4% nữa.

Bước bốn, thu nhập cao xem thêm 0,9%. Thuế Medicare bổ sung (Additional Medicare Tax, khoản (b)(2) điều 1401 IRC) đánh thêm 0,9% trên thu nhập tự làm chủ vượt ngưỡng: độc thân 200.000 đô la, vợ chồng khai chung 250.000 đô la, vợ chồng khai riêng 125.000 đô la, ngưỡng do luật viết chết, không điều chỉnh theo lạm phát, tính bằng Form 8959. Nó không có phần tương ứng của chủ lao động, khoản khấu trừ một nửa nói ở phần sau cũng không bao gồm phần này.

### हिन्दी (अनुवाद, मूल-भाषी समीक्षा लंबित)

गणना का क्रम चार निश्चित चरणों का है, 2026 में 80,000 डॉलर स्व-रोज़गार शुद्ध आय और W-2 वेतन न रखने वाले व्यक्ति का उदाहरण लेकर चलें।

पहला चरण, शुद्ध आय तय करें। व्यवसाय आय से कटौती योग्य व्यवसाय खर्च घटाकर स्व-रोज़गार शुद्ध आय 80,000 डॉलर मिलती है, यह चरण Schedule C पर पूरा होता है, खर्च कैसे माने जाते हैं यह नियमों का अलग समूह है, इस लेख में विस्तार नहीं है।

दूसरा चरण, 92.35% से गुणा करें। IRC धारा 1402 की उपधारा (a)(12) कर आधार को शुद्ध आय के 92.35% पर तय करती है, तर्क कर्मचारी मानक का अनुकरण है: नियोक्ता द्वारा दिया गया आधा वेतन कर मूलतः कर्मचारी के वेतन में गिना ही नहीं जाता, इसलिए स्व-रोज़गार वाला पहले नियोक्ता हिस्से के बराबर 7.65% आधार से निकालता है, फिर कर गिनता है। 80,000 गुणा 92.35% बराबर 73,880 डॉलर।

तीसरा चरण, दरें लगाएँ और सीमा रोकें। सामाजिक सुरक्षा भाग 12.4% केवल सीमा के भीतर वाले भाग पर लगता है: 2026 का करयोग्य वेतन आधार (contribution and benefit base) 184,500 डॉलर है, सामाजिक सुरक्षा प्रशासन (SSA) द्वारा राष्ट्रीय औसत वेतन सूचकांक के अनुसार प्रकाशित, 2025 में 176,100 डॉलर था। उदाहरण के 73,880 डॉलर सीमा के भीतर हैं, इसलिए 12.4% और 2.9% पूरे लगते हैं, 73,880 गुणा 15.3% बराबर 11,303.64 डॉलर, लगभग 11,304 डॉलर। यदि कर आधार 184,500 डॉलर से अधिक हो जाए, तो अधिक भाग पर केवल 2.9% Medicare भाग लगेगा, 12.4% नहीं।

चौथा चरण, उच्च आय पर 0.9% फिर देखें। अतिरिक्त Medicare कर (Additional Medicare Tax, IRC धारा 1401 की उपधारा (b)(2)) सीमा से अधिक स्व-रोज़गार आय पर अलग से 0.9% लगाता है: एकल 200,000 डॉलर, विवाहित संयुक्त दाखिल 250,000 डॉलर, विवाहित अलग दाखिल 125,000 डॉलर, सीमाएँ कानून में स्थिर हैं, मुद्रास्फीति समायोजन नहीं होता, Form 8959 से गणना होती है। इसका कोई नियोक्ता समकक्ष हिस्सा नहीं है, आगे बताई गई आधी कटौती में भी यह भाग शामिल नहीं है।

---

## 三、一半抵扣：省的是所得税，不是自雇税本身

### 中文
自雇者最容易记错的一笔账，是 IRC 第 164 条第 (f) 款给的那一半抵扣。雇主交的那一半工资税对雇主来说是经营费用，自雇者一个人交两半，税法就让他把自雇税的一半当作雇主份额，在算所得税时从总收入里扣掉，位置在 1040 表的附表 1，属于调整总收入的线上扣除（above-the-line），不需要逐项列支、拿标准扣除的人也照样能用。

拿第二节的例子接着算：自雇税 11,304 美元，一半是 5,652 美元，这 5,652 美元从调整后总收入（AGI）里减掉，省多少所得税取决于他落在哪个边际税档。三个限定要记牢。一是这笔抵扣只减所得税，不减自雇税本身，附表 SE 算出的 11,304 美元一分不少要交。二是抵扣的一半只算常规的 15.3% 那部分，0.9% 的附加医疗保险税不在里面。三是顺序不能反：92.35% 是先在算自雇税之前调基数，50% 抵扣是在算完自雇税之后调 AGI，两个调整长得像、位置完全不同，考试爱在这里设选项。

申报节奏上，自雇税跟所得税一起走季度预估税（附表 ES 的 1040-ES），一年四期先交，年终在 1040 表上多退少补；少交了同样会吃低估罚款，安全港规则和之前讲季度预估税那篇是同一套。

### English
The item self-employed taxpayers most often get wrong is the one-half deduction in section 164(f). The employer's half of payroll tax is a business expense to the employer; since a self-employed person pays both halves alone, the statute lets him deduct one-half of the self-employment tax — the employer-equivalent share — in computing income tax. It sits on Schedule 1 of Form 1040 as an above-the-line adjustment to income, available whether or not the taxpayer itemizes.

Continuing the example: one-half of the $11,304 tax is $5,652, subtracted in arriving at adjusted gross income, and the actual income tax saved depends on the taxpayer's marginal bracket. Three limits are worth memorizing. First, the deduction reduces income tax only, never the self-employment tax itself; the $11,304 from Schedule SE is still owed in full. Second, the deductible half covers only the regular 15.3% tax, not the 0.9% Additional Medicare Tax. Third, the order cannot be reversed: the 92.35% factor adjusts the base before the SE tax is computed, while the 50% deduction adjusts AGI after the SE tax is computed. The two adjustments look alike and live in different places, a favorite exam trap.

For payment timing, the SE tax rides along with income tax in quarterly estimated payments on Form 1040-ES, trued up on the annual Form 1040. Underpay and the underpayment penalty applies, under the same safe harbor rules covered in the earlier article on estimated taxes.

### Español (译稿)
El punto que más se confunde es la deducción de la mitad de la sección 164(f). La mitad empresarial del impuesto sobre la nómina es un gasto del negocio para el empleador; como el autónomo paga ambas mitades solo, la ley le permite deducir la mitad del impuesto del trabajo autónomo —la parte equivalente al empleador— al calcular el impuesto sobre la renta. Va en el Anexo 1 del Formulario 1040 como un ajuste al ingreso por encima de la línea (above-the-line), disponible se detallen o no las deducciones.

Siguiendo el ejemplo: la mitad de 11.304 dólares es 5.652 dólares, que se restan al llegar al ingreso bruto ajustado (AGI), y el ahorro efectivo depende del tramo marginal del contribuyente. Hay tres límites que memorizar. Primero, la deducción reduce solo el impuesto sobre la renta, nunca el propio impuesto del trabajo autónomo; los 11.304 dólares del Anexo SE se deben íntegros. Segundo, la mitad deducible cubre solo el impuesto regular del 15,3%, no el 0,9% adicional de Medicare. Tercero, el orden no se puede invertir: el factor 92,35% ajusta la base antes de calcular el impuesto SE, mientras la deducción del 50% ajusta el AGI después de calcularlo. Los dos ajustes se parecen y viven en sitios distintos: una trampa clásica de examen.

En cuanto al calendario, el impuesto SE acompaña al impuesto sobre la renta en los pagos estimados trimestrales del Formulario 1040-ES y se regulariza en el 1040 anual. Pagar de menos acarrea la misma penalización por pago insuficiente, bajo las reglas de puerto seguro ya tratadas en el artículo sobre impuestos estimados.

### 한국어 (초역, 원어민 감수 대기)

자영업자가 가장 자주 틀리는 항목이 IRC 제164조 (f)항이 주는 절반 공제이다. 고용주가 내는 절반의 급여세는 고용주에게 사업비용이며, 자영업자는 혼자 두 절반을 모두 내므로, 세법은 자영업세의 절반을 고용주 몫으로 보아 소득세를 계산할 때 총소득에서 공제하도록 한다. 위치는 Form 1040의 Schedule 1로, 총소득 조정(above-the-line)에 속하며, 항목별 공제를 쓰지 않고 표준공제를 받는 사람도 그대로 쓸 수 있다.

둘째 절의 예를 이어서 계산하자: 자영업세 11,304달러, 그 절반은 5,652달러이며, 이 5,652달러를 조정총소득(AGI)에서 빼고, 실제로 아끼는 소득세는 본인이 어느 한계 세율 구간에 있는지에 달려 있다. 기억할 제한은 세 가지이다. 첫째, 이 공제는 소득세만 줄이고 자영업세 자체는 줄이지 않으므로, Schedule SE로 계산된 11,304달러는 한 푼도 빠짐없이 내야 한다. 둘째, 공제되는 절반은 정규 15.3% 부분만 해당하고, 0.9% 추가 의료보험세는 포함되지 않는다. 셋째, 순서를 뒤집으면 안 된다: 92.35%는 자영업세를 계산하기 전에 기준을 조정하는 것이고, 50% 공제는 자영업세를 계산한 뒤에 AGI를 조정하는 것으로, 두 조정은 비슷해 보이지만 위치가 완전히 다르며, 시험에서 이곳에 선택지를 파는 것을 좋아한다.

신고 리듬으로는, 자영업세는 소득세와 함께 분기별 추정세(Form 1040-ES)를 따라가며, 연 4회 먼저 내고 연말에 Form 1040에서 정산한다; 적게 내면 과소납부 벌금도 마찬가지로 붙으며, 세이프 하버 규칙은 앞에서 다룬 분기별 추정세 글과 같은 체계이다.

### Tiếng Việt (bản dịch sơ bộ, chờ người bản ngữ hiệu đính)

Khoản mà người tự làm chủ dễ nhớ sai nhất là khoản khấu trừ một nửa do khoản (f) điều 164 IRC cho. Nửa thuế tiền lương do chủ lao động đóng, đối với chủ lao động là chi phí kinh doanh; người tự làm chủ một mình đóng cả hai nửa, nên luật thuế cho người đó lấy một nửa thuế tự làm chủ làm phần của chủ lao động, khấu trừ khỏi tổng thu nhập khi tính thuế thu nhập, vị trí ở Schedule 1 của Form 1040, thuộc khoản khấu trừ trên dòng điều chỉnh tổng thu nhập (above-the-line), không cần liệt kê từng khoản, người dùng khấu trừ tiêu chuẩn cũng dùng được như thường.

Lấy ví dụ ở mục hai tính tiếp: thuế tự làm chủ 11.304 đô la, một nửa là 5.652 đô la, 5.652 đô la này trừ khỏi thu nhập gộp đã điều chỉnh (AGI), tiết kiệm được bao nhiêu thuế thu nhập tùy thuộc người đó rơi vào bậc thuế biên nào. Ba giới hạn phải nhớ kỹ. Một là khoản khấu trừ này chỉ giảm thuế thu nhập, không giảm chính thuế tự làm chủ, 11.304 đô la tính ra trên Schedule SE phải đóng không thiếu một xu. Hai là một nửa được khấu trừ chỉ tính phần thông thường 15,3%, thuế Medicare bổ sung 0,9% không nằm trong đó. Ba là thứ tự không được đảo ngược: 92,35% là điều chỉnh cơ sở trước khi tính thuế tự làm chủ, khấu trừ 50% là điều chỉnh AGI sau khi đã tính xong thuế tự làm chủ, hai điều chỉnh trông giống nhau, vị trí hoàn toàn khác nhau, thi cử thích đặt phương án ở chỗ này.

Về nhịp khai báo, thuế tự làm chủ đi cùng thuế thu nhập theo thuế tạm tính hàng quý (Form 1040-ES), một năm bốn kỳ đóng trước, cuối năm quyết toán thừa thiếu trên Form 1040; đóng thiếu cũng bị phạt đóng thiếu như thường, quy tắc bến an toàn cùng một bộ với bài về thuế tạm tính hàng quý đã nói trước đây.

### हिन्दी (अनुवाद, मूल-भाषी समीक्षा लंबित)

स्व-रोज़गार वालों की सबसे आसानी से गलत होने वाली मद IRC धारा 164 की उपधारा (f) द्वारा दी गई आधी कटौती है। नियोक्ता द्वारा दिया गया आधा वेतन कर नियोक्ता के लिए व्यवसाय खर्च है, स्व-रोज़गार वाला अकेला दोनों आधे देता है, इसलिए कर कानून उसे स्व-रोज़गार कर के आधे को नियोक्ता हिस्सा मानकर आयकर गिनते समय कुल आय से घटाने देता है, स्थान Form 1040 के Schedule 1 में है, यह कुल आय समायोजन की ऊपर-की-पंक्ति (above-the-line) कटौती है, मदवार सूची न देने वाले और मानक कटौती लेने वाले भी इसे उपयोग कर सकते हैं।

दूसरे खंड के उदाहरण को आगे गिनें: स्व-रोज़गार कर 11,304 डॉलर, आधा 5,652 डॉलर है, यह 5,652 डॉलर समायोजित कुल आय (AGI) से घटाया जाता है, कितना आयकर बचेगा यह इस पर निर्भर करता है कि वह किस सीमांत कर सोपान में पड़ता है। तीन सीमाएँ याद रखें। एक, यह कटौती केवल आयकर घटाती है, स्व-रोज़गार कर स्वयं नहीं घटाती, Schedule SE से निकले 11,304 डॉलर पूरे देने होंगे। दो, कटौती वाला आधा केवल नियमित 15.3% भाग पर गिना जाता है, 0.9% अतिरिक्त Medicare कर इसमें नहीं है। तीन, क्रम उलटा नहीं हो सकता: 92.35% स्व-रोज़गार कर गिनने से पहले आधार समायोजित करता है, 50% कटौती स्व-रोज़गार कर गिनने के बाद AGI समायोजित करती है, दोनों समायोजन दिखने में समान हैं, स्थान पूरी तरह अलग हैं, परीक्षा में यहाँ विकल्प रखना पसंद किया जाता है।

दाखिल की लय में, स्व-रोज़गार कर आयकर के साथ तिमाही अनुमानित कर (Form 1040-ES) के साथ चलता है, वर्ष में चार किस्तें पहले दी जाती हैं, वर्ष के अंत में Form 1040 पर अधिक-कम समायोजित होता है; कम दें तो कम भुगतान का जुर्माना भी लगेगा, सुरक्षित बंदरगाह नियम पहले वाले तिमाही अनुमानित कर लेख की ही प्रणाली है।

---

## 四、加州落点与 REG 备考定位

### 中文
加州这一层很简单：加州没有另设一套州级自雇税。自雇收入在加州只进州所得税，用 540 表申报，税率按加州自己的累进档走，自雇税的一半抵扣在联邦算出的 AGI 基础上自然带进州税计算的起点，加州税法大体遵从这一项的联邦处理。真正容易混的是另外两件事：给别人发工资时雇主在加州有州残疾保险（SDI）等工资税义务，那是雇主税，和本人自雇税是两套；LLC 在加州每年要交的年费和按总收入算的费用，也不是自雇税，别把三笔账记成一笔。

备考定位：自雇税在 REG 的个人税部分反复出现，题眼通常就四个，税率 15.3% 与拆分 12.4% 加 2.9%、92.35% 的基数调整、当年工资上限数字、50% 抵扣只减所得税不减自雇税。把这四点和附表 C、附表 SE、附表 1 三张表的位置对上号，这类题基本就是送分题。

### English
The California layer is simple: California has no separate state-level self-employment tax. Self-employment income enters only the state income tax, reported on Form 540 at California's own graduated rates, and the federal one-half deduction flows into the starting point of the state computation through the federal AGI figure, which California broadly follows on this item. Two nearby items are easy to confuse with it. An employer's California payroll obligations, such as State Disability Insurance (SDI) withholding on wages paid to others, are employer taxes, a different system from one's own SE tax. And the LLC annual tax and gross-receipts-based fee in California are not self-employment tax either. Three separate bills, three separate rules.

For REG, the self-employment tax recurs in the individual tax area, and the tested points are usually the same four: the 15.3% rate split into 12.4% and 2.9%, the 92.35% base adjustment, the current-year wage base figure, and the rule that the 50% deduction cuts income tax but not the SE tax itself. Match those four points to their homes on Schedule C, Schedule SE, and Schedule 1, and this family of questions becomes close to free points.

### Español (译稿)
La capa de California es simple: California no tiene un impuesto estatal separado sobre el trabajo autónomo. El ingreso autónomo solo entra en el impuesto estatal sobre la renta, declarado en el Formulario 540 con las tasas progresivas propias de California, y la deducción federal de la mitad se traslada al punto de partida del cálculo estatal a través de la cifra del AGI federal, que California sigue en líneas generales en este punto. Dos conceptos cercanos se confunden con facilidad. Las obligaciones salariales del empleador en California, como la retención del Seguro Estatal de Discapacidad (SDI) sobre salarios pagados a otros, son impuestos del empleador, un sistema distinto del impuesto SE propio. Y el impuesto anual de las LLC en California, junto con la cuota basada en ingresos brutos, tampoco es impuesto del trabajo autónomo. Tres pagos distintos, tres reglas distintas.

Para REG, el impuesto del trabajo autónomo reaparece en el área de impuestos individuales, y los puntos evaluados suelen ser los mismos cuatro: la tasa del 15,3% dividida en 12,4% y 2,9%, el ajuste de base del 92,35%, la cifra del tope salarial del año en curso y la regla de que la deducción del 50% reduce el impuesto sobre la renta pero no el impuesto SE en sí. Ubique esos cuatro puntos en el Anexo C, el Anexo SE y el Anexo 1, y esta familia de preguntas se vuelve casi un regalo.

### 한국어 (초역, 원어민 감수 대기)

캘리포니아 층은 매우 간단하다: 캘리포니아에는 별도의 주 단위 자영업세가 없다. 자영업 소득은 캘리포니아에서 주 소득세에만 들어가며, Form 540으로 신고하고 세율은 캘리포니아 자체의 누진 구간을 따르며, 자영업세 절반 공제는 연방에서 계산된 AGI를 기초로 주세 계산의 출발점에 자연스럽게 따라 들어간다. 캘리포니아 세법은 이 항목에서 연방 처리를 대체로 따른다. 진짜로 혼동하기 쉬운 것은 다른 두 가지이다: 다른 사람에게 임금을 지급할 때 고용주가 캘리포니아에서 부담하는 주 장애보험(SDI) 등 급여세 의무는 고용주세로, 본인의 자영업세와는 다른 체계이며; LLC가 캘리포니아에서 매년 내는 연간세와 총수입 기준으로 계산되는 수수료도 자영업세가 아니므로, 세 가지 청구서를 한 가지로 기억하지 말 것.

시험 대비 위치: 자영업세는 REG의 개인세 부분에 반복해서 나오며, 출제 포인트는 보통 네 가지이다 — 세율 15.3%와 12.4%에 2.9%를 더한 분해, 92.35%의 기준 조정, 당해 연도 임금 상한 숫자, 50% 공제는 소득세만 줄이고 자영업세는 줄이지 않는다는 점. 이 네 가지를 Schedule C, Schedule SE, Schedule 1 세 장의 표 위치와 맞춰 두면, 이 유형의 문제는 거의 공짜 점수이다.

### Tiếng Việt (bản dịch sơ bộ, chờ người bản ngữ hiệu đính)

Tầng California rất đơn giản: California không đặt thêm một sắc thuế tự làm chủ cấp bang riêng. Thu nhập tự làm chủ ở California chỉ vào thuế thu nhập bang, khai bằng Form 540, thuế suất đi theo biểu lũy tiến riêng của California, khoản khấu trừ một nửa thuế tự làm chủ dựa trên AGI đã tính ở liên bang tự nhiên đi vào điểm khởi đầu tính thuế bang, luật thuế California đại thể tuân theo cách xử lý liên bang ở khoản này. Hai việc thực sự dễ nhầm là hai việc khác: khi trả lương cho người khác, chủ lao động ở California có nghĩa vụ thuế tiền lương như bảo hiểm khuyết tật bang (SDI), đó là thuế của chủ lao động, khác hệ với thuế tự làm chủ của bản thân; khoản thuế hàng năm LLC phải đóng ở California mỗi năm và khoản phí tính theo tổng doanh thu cũng không phải thuế tự làm chủ, đừng ghi ba khoản tiền thành một.

Định vị ôn thi: thuế tự làm chủ xuất hiện lặp lại trong phần thuế cá nhân của REG, điểm ra đề thường chỉ có bốn: thuế suất 15,3% và cách tách 12,4% cộng 2,9%, điều chỉnh cơ sở 92,35%, con số trần lương của năm hiện tại, khấu trừ 50% chỉ giảm thuế thu nhập không giảm thuế tự làm chủ. Đối chiếu bốn điểm này với vị trí của ba biểu Schedule C, Schedule SE, Schedule 1, dạng câu hỏi này về cơ bản là điểm cho không.

### हिन्दी (अनुवाद, मूल-भाषी समीक्षा लंबित)

कैलिफ़ोर्निया स्तर बहुत सरल है: कैलिफ़ोर्निया में अलग से राज्य-स्तरीय स्व-रोज़गार कर नहीं है। स्व-रोज़गार आय कैलिफ़ोर्निया में केवल राज्य आयकर में जाती है, Form 540 से दाखिल होती है, दर कैलिफ़ोर्निया के अपने प्रगतिशील सोपानों के अनुसार लगती है, स्व-रोज़गार कर की आधी कटौती संघीय स्तर पर निकले AGI के आधार पर राज्य कर गणना के प्रारंभ बिंदु में स्वाभाविक रूप से आ जाती है, कैलिफ़ोर्निया कर कानून इस मद में संघीय व्यवहार का मोटे तौर पर पालन करता है। वास्तव में भ्रमित करने वाली दो अन्य बातें हैं: दूसरों को वेतन देते समय नियोक्ता पर कैलिफ़ोर्निया में राज्य विकलांगता बीमा (SDI) जैसी वेतन कर देयताएँ नियोक्ता कर हैं, स्वयं के स्व-रोज़गार कर से अलग प्रणाली; LLC को कैलिफ़ोर्निया में हर वर्ष देना पड़ने वाला वार्षिक कर और कुल आय के आधार पर लगने वाला शुल्क भी स्व-रोज़गार कर नहीं है, तीनों बिलों को एक न समझें।

परीक्षा स्थिति: स्व-रोज़गार कर REG के व्यक्तिगत कर भाग में बार-बार आता है, प्रश्न बिंदु सामान्यतः चार ही होते हैं — दर 15.3% और उसका 12.4% जमा 2.9% में विभाजन, 92.35% आधार समायोजन, उस वर्ष की वेतन सीमा संख्या, 50% कटौती केवल आयकर घटाती है स्व-रोज़गार कर नहीं। इन चार बिंदुओं को Schedule C, Schedule SE और Schedule 1 तीनों फ़ॉर्मों के स्थान से मिला लें, तो इस प्रकार के प्रश्न लगभग मुफ़्त के अंक हैं।

---

## 来源与说明 / Sources / Fuentes

主要出处：Internal Revenue Code 第 1401 条（税率与附加医疗保险税）、第 1402 条（自雇净收入定义与第 (a)(12) 项的 92.35% 调整、400 美元门槛）、第 164 条第 (f) 款（一半抵扣）；Social Security Administration, Contribution and Benefit Base（2026 年应税工资基数 184,500 美元，2025 年 176,100 美元）；IRS Schedule SE (Form 1040)、Schedule 1 (Form 1040)、Form 8959 与 Topic No. 751（Social Security and Medicare Withholding Rates）。数字为 2026 税务年度口径，后续年度上限以 SSA 年度公布为准。

西班牙语为学习译稿，待母语校对。El texto en español es una traducción de estudio, pendiente de revisión por un hablante nativo.

声明：本篇为个人学习笔记，不构成税务、财务或法律建议。This article is a personal study note only and does not constitute tax, financial, or legal advice. Este artículo es una nota personal de estudio y no constituye asesoría fiscal, financiera ni legal.

본문의 한국어, 베트남어, 힌디어는 학습용 초역으로 원어민 감수를 기다리고 있습니다. Bản tiếng Hàn, tiếng Việt và tiếng Hindi trong bài là bản dịch sơ bộ phục vụ học tập, chờ người bản ngữ hiệu đính. इस लेख के कोरियाई, वियतनामी और हिन्दी अनुवाद अध्ययन के लिए प्रारंभिक अनुवाद हैं, मूल-भाषी समीक्षा लंबित है।

이 글은 개인 학습 노트이며 세무, 재무 또는 법률 조언이 아닙니다. Bài này là ghi chú học tập cá nhân, không cấu thành tư vấn thuế, tài chính hay pháp lý. यह लेख एक व्यक्तिगत अध्ययन नोट है, कर, वित्तीय या कानूनी सलाह नहीं है।
