# 资本利得与合格股息怎么计税：持有期、三档税率与 NIIT

这篇在税法图谱里的位置：上一篇拆了个人所得税的计算结构，这一篇只钻投资所得这一块——卖股票、基金、加密资产和房产赚的钱，联邦怎么征税。核心规则集中在《国内税收法典》（Internal Revenue Code, IRC）第 1(h) 条、第 1221/1222 条和第 1411 条，税率门槛每年由 IRS 按通胀调整，文中数字以 2026 税年（Rev. Proc. 2025-32）为主、2025 税年（Rev. Proc. 2024-40）作对照。

---

## 一、先分短期与长期：一年零一天是分水岭

### 中文
资本利得先按持有期分家，这一步决定后面用哪套税率。依据 IRC 第 1222 条：出售时持有资本资产（capital asset，第 1221 条定义，库存、自用创作物等被排除）恰好一年或不足一年的，利得是短期资本利得（short-term），和工资一样并入普通所得按累进税率征税；持有超过一年的，是长期资本利得（long-term），才有资格用 0%、15%、20% 的优惠税率。注意用词是超过一年：满一年当天卖掉仍是短期，要等到一年零一天。

金额本身的算法不复杂：利得等于售价减去调整后计税基础（basis，第 1011、1012 条，一般就是买入成本加上佣金等调整）。同一税年内先把短期与短期轧差、长期与长期轧差，再把两边结果按第 1222 条的规则合并，最后进 Schedule D 和 Qualified Dividends and Capital Gain Tax Worksheet 算税。合格股息（qualified dividends，第 1(h)(11) 条）不是利得，但立法把它的税率直接挂到同一套 0/15/20 档上，前提包括持股期要求：一般要在股息除息日前后 121 天窗口内持有普通股超过 60 天。

### English
Capital gains are sorted first by holding period, and that sorting decides which rate schedule applies. Under IRC section 1222, a gain on a capital asset (defined in section 1221, which excludes inventory and certain self-created works) held for one year or less is a short-term capital gain, taxed with wages at ordinary graduated rates. A gain on an asset held for more than one year is long-term and qualifies for the preferential 0%, 15%, and 20% rates. The wording matters: selling on the one-year anniversary is still short-term; the line is crossed only after more than one year.

The amount itself is simple arithmetic: gain equals the amount realized minus adjusted basis (sections 1011 and 1012 — generally purchase cost plus adjustments such as commissions). Within the tax year, short-term items are netted against short-term items and long-term against long-term, then the two results are combined under the section 1222 mechanics and carried to Schedule D and the Qualified Dividends and Capital Gain Tax Worksheet. Qualified dividends (section 1(h)(11)) are not gains at all, but Congress taxes them on the same 0/15/20 schedule, subject to holding-period rules — for common stock, generally more than 60 days within the 121-day window around the ex-dividend date.

### Español (译稿)
Las ganancias de capital se clasifican primero por el período de tenencia, y esa clasificación decide qué escala de tasas se aplica. Según la sección 1222 del IRC, la ganancia por un activo de capital (definido en la sección 1221, que excluye inventarios y ciertas obras de creación propia) tenido un año o menos es ganancia de corto plazo (short-term) y tributa como el salario, a las tasas ordinarias progresivas. Si el activo se tuvo más de un año, la ganancia es de largo plazo (long-term) y accede a las tasas preferentes del 0%, 15% y 20%. La redacción importa: vender el mismo día del año cumplido sigue siendo corto plazo; el umbral se cruza solo tras más de un año.

El monto es aritmética sencilla: ganancia igual a precio de venta menos la base fiscal ajustada (secciones 1011 y 1012, por lo general el coste de compra más ajustes como comisiones). Dentro del año fiscal se compensan partidas de corto plazo entre sí y de largo plazo entre sí, luego ambos resultados se combinan según la mecánica de la sección 1222 y pasan al Anexo D (Schedule D) y a la hoja de cálculo de dividendos calificados y ganancias de capital. Los dividendos calificados (qualified dividends, sección 1(h)(11)) no son ganancias, pero el Congreso los grava con la misma escala 0/15/20, con requisitos de tenencia: para acciones ordinarias, en general más de 60 días dentro de la ventana de 121 días en torno a la fecha ex dividendo.

---

## 二、三档税率看的是应税收入，不是利得本身

### 中文
最常见的误读是把 0/15/20 当成看利得大小。实际上第 1(h) 条的门槛看的是全年应税收入（taxable income）：长期利得是叠在其他应税收入最上面的一层，落在门槛以下的部分按低档、超出的部分按高档，分段计税。门槛每年按通胀调整，依据是第 1(j)(5) 条的指数化规则和 IRS 当年的收入程序。

2026 税年门槛（Rev. Proc. 2025-32 第 4.03 节，maximum zero rate amount 与 maximum 15 percent rate amount）：

- 单身（Single）：应税收入不超过 49,450 美元的部分 0%；49,450 至 545,500 美元 15%；超过 545,500 美元 20%。
- 已婚合并申报（Married filing jointly）：98,900 美元以下 0%；98,900 至 613,700 美元 15%；超过 613,700 美元 20%。
- 户主（Head of household）：66,200 美元以下 0%；66,200 至 579,600 美元 15%；超过 579,600 美元 20%。

2025 税年作对照（Rev. Proc. 2024-40）：单身 0% 上限 48,350 美元、15% 上限 533,400 美元；合并申报 96,700 美元与 600,050 美元；户主 64,750 美元与 566,700 美元。每年门槛小幅上移，低收入年份实现利得、多拿一段 0% 区间的规划空间就是从这里来的。

算个具体例子检验理解。单身，2026 年其他应税收入 40,000 美元，卖出持有一年以上的股票得利 20,000 美元，应税收入合计 60,000 美元。利得的 9,450 美元落在 49,450 美元门槛以内，按 0%；剩下 10,550 美元按 15%，税款 1,582.50 美元。如果同一笔利得在持有满一年之前卖出，20,000 美元全部按普通税率走，税负明显更高——这就是持有期规则的实际分量。

### English
The most common misreading treats the 0/15/20 rates as if they turned on the size of the gain. In fact, the section 1(h) thresholds are measured against total taxable income. The long-term gain sits as the top layer on top of other taxable income: the slice falling below a threshold takes the lower rate and the slice above takes the higher rate, in a stacking calculation. The thresholds are inflation-indexed each year under section 1(j)(5) and published in the IRS annual revenue procedure.

For tax year 2026 (Rev. Proc. 2025-32, section 4.03 — the maximum zero rate amount and maximum 15 percent rate amount):

- Single: taxable income up to $49,450 at 0%; $49,450 to $545,500 at 15%; above $545,500 at 20%.
- Married filing jointly: up to $98,900 at 0%; $98,900 to $613,700 at 15%; above $613,700 at 20%.
- Head of household: up to $66,200 at 0%; $66,200 to $579,600 at 15%; above $579,600 at 20%.

For comparison, tax year 2025 (Rev. Proc. 2024-40) used $48,350 and $533,400 for single filers, $96,700 and $600,050 for joint filers, and $64,750 and $566,700 for heads of household. The thresholds creep up a little each year, which is exactly where the planning room comes from: realizing gains in a low-income year captures more of the 0% band.

A worked example checks the logic. Single filer, 2026, other taxable income of $40,000, plus a $20,000 long-term gain on stock held more than one year — total taxable income $60,000. Of the gain, $9,450 falls under the $49,450 threshold and is taxed at 0%; the remaining $10,550 is taxed at 15%, for a tax of $1,582.50. Sold one year or less after purchase, the same $20,000 would be taxed entirely at ordinary rates, a clearly heavier bill — that difference is the practical weight of the holding-period rule.

### Español (译稿)
El error más común es creer que las tasas 0/15/20 dependen del tamaño de la ganancia. En realidad, los umbrales de la sección 1(h) se miden sobre la renta imponible total (taxable income): la ganancia de largo plazo se coloca como la capa superior sobre los demás ingresos, la porción bajo el umbral tributa a la tasa menor y el exceso a la mayor, en un cálculo por capas. Los umbrales se ajustan cada año por inflación según la sección 1(j)(5) y se publican en el procedimiento anual del IRS.

Para el año fiscal 2026 (Rev. Proc. 2025-32, sección 4.03):

- Soltero (Single): renta imponible hasta $49.450 al 0%; de $49.450 a $545.500 al 15%; por encima de $545.500 al 20%.
- Casados con declaración conjunta: hasta $98.900 al 0%; de $98.900 a $613.700 al 15%; por encima de $613.700 al 20%.
- Cabeza de familia (Head of household): hasta $66.200 al 0%; de $66.200 a $579.600 al 15%; por encima de $579.600 al 20%.

A modo de comparación, el año fiscal 2025 (Rev. Proc. 2024-40) usó $48.350 y $533.400 para solteros, $96.700 y $600.050 para declaración conjunta, y $64.750 y $566.700 para cabeza de familia. Los umbrales suben un poco cada año, y de ahí sale el margen de planificación: realizar ganancias en un año de ingresos bajos aprovecha más tramo al 0%.

Un ejemplo con números lo deja claro. Soltero, 2026, otros ingresos imponibles de $40.000 y una ganancia de largo plazo de $20.000 por acciones tenidas más de un año: renta imponible total $60.000. De la ganancia, $9.450 quedan bajo el umbral de $49.450 y tributan al 0%; los $10.550 restantes tributan al 15%, es decir, un impuesto de $1.582,50. Si esa misma ganancia se realizara con un año o menos de tenencia, los $20.000 tributarían a tasas ordinarias, con una factura claramente mayor: esa es la importancia práctica de la regla de tenencia.

---

## 三、0/15/20 之外还要记住的三组特殊规则

### 中文
第一组是两种更高的长期利得税率。收藏品利得（collectibles gain，金银币、艺术品、古董等，第 1(h)(5) 条与第 408(m) 条口径）最高按 28% 征税；出售营业用不动产时，与以往折旧对应的未收回第 1250 条利得（unrecaptured section 1250 gain）最高按 25% 征税。报税软件里的 28% Rate Worksheet 和 Unrecaptured Section 1250 Gain Worksheet 就是为这两类准备的。

第二组是亏损怎么消化。资本亏损先抵同年资本利得；抵完还有净亏损的，每年最多再抵 3,000 美元普通所得（合并申报口径；分开申报为 1,500 美元，第 1211(b) 条），抵不完的按第 1212(b) 条无限期结转，并保留短期、长期的原属性。配套的反避税规则是第 1091 条的清洗销售规则（wash sale rule）：卖出亏损后 30 天内（前后共 61 天窗口）买入相同或实质相同的证券，被否定（disallowed）的亏损不消失，而是加进新仓位的计税基础里。加密资产目前是否属于第 1091 条所说的 stock or securities 尚无定论，IRS 把虚拟货币定性为财产（Notice 2014-21），实务上不要默认加密亏损可以无限制即时收割。

第三组是主要居所的排除。卖自住房的利得可按第 121 条排除：单身最高 250,000 美元、合并申报最高 500,000 美元，条件是在出售前五年内拥有并实际居住满两年（ownership and use tests）。这条对湾区房价量级的交易影响很大，是卖房年份要最先核对的一条。

### English
Three sets of special rules sit beside the headline 0/15/20 schedule.

The first is two higher long-term rates. Gain on collectibles — coins, art, antiques, and the like under sections 1(h)(5) and 408(m) — is taxed at a maximum rate of 28%. Unrecaptured section 1250 gain, the portion of a gain on business real estate attributable to prior depreciation, is taxed at a maximum of 25%. The 28% Rate Worksheet and the Unrecaptured Section 1250 Gain Worksheet in the Schedule D instructions exist for exactly these two categories.

The second is how losses are absorbed. Capital losses first offset capital gains of the same year. A remaining net capital loss may offset up to $3,000 of ordinary income per year ($1,500 if married filing separately, section 1211(b)), and any excess carries forward indefinitely under section 1212(b), keeping its short-term or long-term character. The companion anti-abuse rule is the wash sale rule of section 1091: sell at a loss and buy substantially identical stock or securities within 30 days before or after (a 61-day window) and the loss is disallowed — not destroyed, but added to the basis of the replacement position. Whether digital assets count as stock or securities under section 1091 remains unsettled; the IRS treats virtual currency as property (Notice 2014-21), so do not assume crypto losses can be harvested without limit.

The third is the principal-residence exclusion. Under section 121, gain on the sale of a main home may be excluded up to $250,000 for a single filer and $500,000 for joint filers, provided the taxpayer owned and used the home for at least two of the five years before the sale. At Bay Area price levels this is frequently the first provision to check in a home-sale year.

### Español (译稿)
Junto a la escala principal 0/15/20 conviven tres grupos de reglas especiales.

El primero son dos tasas de largo plazo más altas. La ganancia por objetos de colección (collectibles gain: monedas, arte, antigüedades, según las secciones 1(h)(5) y 408(m)) tributa a una tasa máxima del 28%. La ganancia de la sección 1250 no recapturada (unrecaptured section 1250 gain), la parte de la ganancia inmobiliaria comercial atribuible a la depreciación previa, tributa a un máximo del 25%. Las hojas de cálculo de la tasa del 28% y de la ganancia 1250 no recapturada en las instrucciones del Anexo D existen para estas dos categorías.

El segundo grupo es cómo se absorben las pérdidas. Las pérdidas de capital primero compensan las ganancias del mismo año. La pérdida neta restante puede compensar hasta $3.000 anuales de ingresos ordinarios ($1.500 en declaración separada, sección 1211(b)) y el exceso se traslada indefinidamente según la sección 1212(b), conservando su carácter de corto o largo plazo. La regla antiabuso compañera es la de venta ficticia (wash sale rule) de la sección 1091: si vende con pérdida y recompra valores iguales o sustancialmente idénticos dentro de los 30 días anteriores o posteriores (ventana de 61 días), la pérdida se deniega —no desaparece, se suma a la base fiscal de la nueva posición—. Si los activos digitales cuentan como valores a efectos de la sección 1091 sigue sin estar resuelto; el IRS trata las monedas virtuales como propiedad (Notice 2014-21), así que no dé por hecho que las pérdidas en cripto pueden cosecharse sin límite.

El tercer grupo es la exclusión por vivienda principal. Según la sección 121, la ganancia por vender la vivienda habitual puede excluirse hasta $250.000 (soltero) o $500.000 (declaración conjunta), si el contribuyente fue propietario y la usó al menos dos de los cinco años previos a la venta. Con precios como los del Área de la Bahía, suele ser la primera norma a revisar el año en que se vende la casa.

---

## 四、再叠一层：3.8% 的 NIIT 与加州的不跟随

### 中文
高收入者还要看净投资所得税（Net Investment Income Tax, NIIT），IRC 第 1411 条，税率 3.8%。触发线看调整后总收入（MAGI）：单身超过 200,000 美元、合并申报超过 250,000 美元、分开申报超过 125,000 美元，超出部分的净投资收入（利息、股息、资本利得、租金、被动经营所得等）按 3.8% 征收；应纳税额取两者的较小值——超额 MAGI 与净投资收入比大小取小。这几个门槛是 2013 年立法时写死的数字，法条没有通胀调整条款，所以十多年没动过，每年圈进来的人只增不减。叠满的状态是：20% 的长期利得税率加 3.8% 的 NIIT，联邦合计 23.8%。NIIT 用 Form 8960 申报，备考时注意它不属于第 1 章的普通所得税，而是第 2A 章的独立税种。

到了加州这一层，规则简单粗暴：加州没有长期资本利得优惠税率。《加州收入与税法典》下，资本利得全部并入普通所得，按加州 1% 至 12.3% 的累进税率征税（高收入另有 1% 的心理健康服务税，合计边际最高 13.3%），申报上用 Schedule CA 做联邦与州的差异调整。用联邦的 0% 思路去估加州税负，是新手最常见的错位。CPA 考试（REG）与实务口径一致：联邦先分短期长期、再叠 NIIT，州税单独按本州规则另算，两套系统不要混表。

### English
Higher-income taxpayers face one more layer: the Net Investment Income Tax (NIIT) of IRC section 1411, at 3.8%. It is triggered by modified adjusted gross income (MAGI) above $200,000 for single filers, $250,000 for joint filers, and $125,000 for married filing separately, and it applies to the lesser of the MAGI excess or the taxpayer's net investment income — interest, dividends, capital gains, rents, and passive business income. Those thresholds were fixed by statute in 2013 with no inflation adjustment, so they have not moved in over a decade and capture more taxpayers every year. Fully stacked, a top-bracket long-term gain pays 20% plus 3.8%, a combined 23.8% federal rate. The NIIT is reported on Form 8960 — and note for exam purposes that it sits in Chapter 2A of the Code, a separate tax from the Chapter 1 income tax.

California then runs its own, simpler rule: there is no preferential capital gains rate. Under California law, capital gains are ordinary income, taxed at the state's graduated 1% to 12.3% rates (with the additional 1% mental health services tax at the top, for a top marginal rate of 13.3%), with federal-to-state differences adjusted on Schedule CA. Estimating a California tax bill with the federal 0% bracket in mind is the most common beginner's mismatch. For CPA REG purposes and in practice alike: compute the federal side first — short versus long-term, then the NIIT layer — and compute California separately under its own rules.

### Español (译稿)
Los contribuyentes de ingresos altos tienen una capa más: el impuesto sobre la renta neta de inversión (Net Investment Income Tax, NIIT), sección 1411 del IRC, con una tasa del 3,8%. Se activa cuando el ingreso bruto ajustado modificado (MAGI) supera $200.000 (soltero), $250.000 (declaración conjunta) o $125.000 (declaración separada), y se aplica sobre lo menor entre el exceso de MAGI y la renta neta de inversión del contribuyente: intereses, dividendos, ganancias de capital, rentas y rentas pasivas de negocios. Esos umbrales quedaron fijos en la ley de 2013, sin ajuste por inflación, así que llevan más de una década sin moverse y cada año abarcan a más personas. En el extremo superior, una ganancia de largo plazo paga 20% más 3,8%: un 23,8% federal combinado. El NIIT se declara en el Formulario 8960 y, a efectos de examen, tenga en cuenta que está en el Capítulo 2A del Código, un impuesto distinto del impuesto sobre la renta del Capítulo 1.

California aplica su propia regla, más simple y menos amable: no existe una tasa preferente para las ganancias de capital. Conforme al derecho californiano, las ganancias de capital son ingreso ordinario y tributan en la escala progresiva estatal del 1% al 12,3% (con el 1% adicional del impuesto de servicios de salud mental en el tramo alto, para un tipo marginal máximo del 13,3%), con las diferencias frente a lo federal ajustadas en el Schedule CA. Estimar el impuesto de California con la lógica del tramo federal al 0% es el desajuste más común en quien empieza. Tanto para el examen CPA (REG) como en la práctica: primero se calcula la parte federal —corto frente a largo plazo, luego la capa del NIIT— y California se calcula por separado con sus propias reglas.

---

## 参考依据

- IRC section 1(h)（长期资本利得最高税率与合格股息）、section 1(h)(11)（合格股息）、section 1(j)(5)（门槛指数化）、sections 1011/1012（计税基础）、section 1091（清洗销售）、section 121（主要居所排除 250,000/500,000 美元）、section 1211(b)（资本亏损每年 3,000/1,500 美元限额）、section 1212(b)（亏损结转）、sections 1221/1222（资本资产与持有期）、section 1411（NIIT 3.8% 与 200,000/250,000/125,000 美元门槛）
- Rev. Proc. 2025-32, section 4.03（2026 税年 0% 与 15% 门槛：单身 49,450/545,500、合并申报 98,900/613,700、户主 66,200/579,600 美元）；Rev. Proc. 2024-40（2025 税年：单身 48,350/533,400、合并申报 96,700/600,050、户主 64,750/566,700 美元）
- IRS Topic No. 409（Capital Gains and Losses）；IRS Notice 2014-21（虚拟货币财产定性）；Form 8960 与 Schedule D 说明书（含 28% 与第 1250 条工作表）
- California Revenue and Taxation Code：加州无资本利得优惠税率，利得按普通所得 1% 至 12.3% 累进税率（另加高收入者 1% 心理健康服务税）征税；FTB Schedule CA 调整说明

## 免责声明

本篇为个人学习笔记，不构成税务建议。税率门槛逐年调整，具体申报请查当年 IRS 收入程序与表格说明书，或咨询持牌 CPA。

*This article is a personal study note, not tax advice. / Este artículo es una nota de estudio personal, no constituye asesoría fiscal. El texto en español es una traducción de estudio, pendiente de revisión por un hablante nativo.*
