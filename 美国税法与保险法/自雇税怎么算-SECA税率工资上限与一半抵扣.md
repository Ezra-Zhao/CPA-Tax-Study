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

---

## 来源与说明 / Sources / Fuentes

主要出处：Internal Revenue Code 第 1401 条（税率与附加医疗保险税）、第 1402 条（自雇净收入定义与第 (a)(12) 项的 92.35% 调整、400 美元门槛）、第 164 条第 (f) 款（一半抵扣）；Social Security Administration, Contribution and Benefit Base（2026 年应税工资基数 184,500 美元，2025 年 176,100 美元）；IRS Schedule SE (Form 1040)、Schedule 1 (Form 1040)、Form 8959 与 Topic No. 751（Social Security and Medicare Withholding Rates）。数字为 2026 税务年度口径，后续年度上限以 SSA 年度公布为准。

西班牙语为学习译稿，待母语校对。El texto en español es una traducción de estudio, pendiente de revisión por un hablante nativo.

声明：本篇为个人学习笔记，不构成税务、财务或法律建议。This article is a personal study note only and does not constitute tax, financial, or legal advice. Este artículo es una nota personal de estudio y no constituye asesoría fiscal, financiera ni legal.
