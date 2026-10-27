# Crane 案：无追索权债务的基数与实现额（案例分析）

这篇讲什么：
- Crane v. Commissioner, 331 U.S. 1 (1947) 是美国税法里绕不开的一案：它同时回答了两个问题——带贷款的财产，基数里算不算那笔债；卖掉时，实现额里算不算被接走的那笔债。
- 先按判决原文把数字算一遍，再看这套「两边都算」的对称逻辑怎样写进现行《国内税收法典》（IRC）第 1001、1012、7701(g) 条，最后接上 Tufts 案（1983）补掉的那块拼图。
- CPA 的 REG 与税务实务里，带债处置的计算题几乎都是这一案的变体。

---

## 一、事实：一栋几乎全是贷款的楼

### 中文
Beulah Crane 的丈夫于 1932 年 1 月去世，她是遗产的唯一受益人和执行人。遗产里有一块地和一栋公寓楼，为遗产税目的估值 262,042.50 美元，其中土地 55,000 美元、建筑 207,042.50 美元。这栋楼上压着一笔 255,000 美元本金的抵押贷款，另有 7,042.50 美元利息已经拖欠；关键一点是，这笔贷款对她个人无追索权（nonrecourse），也就是说债权人只能拿楼本身受偿，不能追她个人其他财产。

她接手后继续经营这栋楼收租。在她持有期间，这栋建筑可计提的折旧共 28,045.10 美元——请注意这一点，折旧是本案真正的引线：她已经按包含贷款的完整价值提了折旧，卖楼时却想按另一套口径算。

1938 年 11 月 29 日，抵押权人威胁要止赎（foreclosure），她把楼以 3,000 美元现金、买方承受抵押贷款的方式卖给第三方，又付了 500 美元出售费用，净得现金 2,500 美元。她报税时的算法是：我当年继承的「财产」只是楼里扣掉贷款后的权益（equity），这份权益在继承时价值为零，所以我的基数是零，实现额就是净得的 2,500 美元，并按当时的资本利得规则申报了其中一半、1,250 美元为应税利得。

### English
Beulah Crane's husband died in January 1932, leaving her as sole beneficiary and executrix of his estate. The estate included land and an apartment building appraised, for estate tax purposes, at $262,042.50 — $55,000 allocated to the land and $207,042.50 to the building. The property was encumbered by a mortgage of $255,000 in principal, with a further $7,042.50 of interest in default. Critically, the mortgage was nonrecourse as to her: the lender could look only to the building, not to her other assets.

She operated the building and collected the rents. During her holding period, allowable depreciation on the building came to $28,045.10 — and depreciation is the real fuse of this case, because she had taken deductions measured by the property's full value, debt included, yet wanted to compute her sale on a different theory.

On November 29, 1938, with the mortgagee threatening foreclosure, she sold the property to a third party for $3,000 in cash, subject to the mortgage, and paid $500 in selling expenses, netting $2,500 in cash. Her return took this position: the "property" she had inherited was only her equity in the building — the value over and above the mortgage — and that equity had been worth zero when she acquired it. Her basis was therefore zero, her amount realized was the $2,500 of net cash, and, under the capital-gain inclusion rules of the day, she reported half of it, $1,250, as taxable gain.

### Español (译稿)
El esposo de Beulah Crane murió en enero de 1932 y ella quedó como única beneficiaria y albacea de la herencia. Esta incluía un terreno y un edificio de apartamentos tasado, a efectos del impuesto de sucesiones, en 262.042,50 dólares: 55.000 para el terreno y 207.042,50 para el edificio. Sobre el inmueble pesaba una hipoteca de 255.000 dólares de principal, con otros 7.042,50 dólares de intereses ya vencidos. El punto clave: la hipoteca era sin recurso personal (nonrecourse) contra ella, es decir, el acreedor solo podía cobrarse con el propio edificio, no con sus demás bienes.

Ella siguió explotando el edificio y cobrando los alquileres. Durante su período de tenencia, la depreciación admisible del edificio sumó 28.045,10 dólares, y esa depreciación es la verdadera mecha del caso: había deducido sobre el valor completo del inmueble, deuda incluida, pero al vender quería calcular con otra teoría.

El 29 de noviembre de 1938, con el acreedor hipotecario amenazando la ejecución (foreclosure), vendió el inmueble a un tercero por 3.000 dólares en efectivo, sujeto a la hipoteca, y pagó 500 dólares de gastos de venta, quedándose con 2.500 dólares netos. Su declaración sostuvo esto: la «propiedad» heredada era solo su participación neta (equity) en el edificio, el valor por encima de la hipoteca, y esa participación valía cero al adquirirla. Por tanto, su base era cero, su importe realizado eran los 2.500 dólares netos y, según las reglas de inclusión de ganancias de capital de la época, declaró la mitad, 1.250 dólares, como ganancia imponible.

---

## 二、争点：两个对称的问题

### 中文
税局局长（Commissioner）的算法正好相反，并把案子拆成两个必须一起回答的问题：

1. **取得端**：她继承的「财产」到底是整栋楼，还是扣掉贷款后的那份权益？如果财产是整栋楼，她的原始基数就是死亡时的完整估值 262,042.50 美元；如果只是权益，基数就是零。
2. **处置端**：买方承受的那笔 255,000 美元抵押贷款，算不算她出售时的实现额（amount realized）？税局认为算：实现额是 2,500 美元净现金加 255,000 美元债务，共 257,500 美元。

税局据此核定：调整后基数为 262,042.50 减去可提折旧 28,045.10，即 233,997.40 美元；实现额 257,500 美元与之相减，利得约为 23,502.60 美元（原核定还按土地与建筑的比例分摊售价、分别处理资本损失与普通利得，得出应税净利得 23,767.03 美元的口径）。税务法院（当时卷内为 3 T.C. 585）大体站在她一边，第二巡回法院又改判，案子最后到了最高法院。

两个问题为什么必须一起答？因为只答一个就会漏税或双重征税：基数算债、实现额不算债，纳税人就白拿了折旧又逃掉了还款；基数不算债、实现额算债，则是同一笔钱被算了两次。这个对称性就是全案的骨架。

### English
The Commissioner computed the tax the opposite way and framed two questions that had to be answered together:

1. **At acquisition**: was the "property" she inherited the whole building, or only the equity above the mortgage? If the property was the building itself, her original basis was its full date-of-death value of $262,042.50; if it was only the equity, her basis was zero.
2. **At disposition**: does the $255,000 mortgage, to which the buyer took the property subject, count in her amount realized? The Commissioner said yes: the amount realized was the $2,500 of net cash plus the $255,000 of debt, a total of $257,500.

On that footing the Commissioner determined an adjusted basis of $262,042.50 minus $28,045.10 of allowable depreciation, or $233,997.40, against an amount realized of $257,500 — a gain of roughly $23,502.60 before characterization (the original determination also allocated the price between land and building and treated a capital loss on the land and ordinary gain on the building separately, arriving at a net taxable gain of $23,767.03). The Tax Court (3 T.C. 585) largely sided with her; the Second Circuit reversed; the case reached the Supreme Court.

Why must the two questions be answered together? Answering only one either leaks revenue or double-counts. Include the debt in basis but not in amount realized, and the taxpayer keeps depreciation on money that is never accounted for. Exclude it from basis but include it on sale, and the same dollars are counted twice. That symmetry is the skeleton of the whole case.

### Español (译稿)
El Comisionado de Hacienda calculó el impuesto al contrario y planteó dos preguntas que debían responderse juntas:

1. **En la adquisición**: ¿la «propiedad» heredada era todo el edificio o solo la participación neta por encima de la hipoteca? Si era el edificio, su base original era el valor completo a la fecha de la muerte, 262.042,50 dólares; si era solo la participación neta, su base era cero.
2. **En la disposición**: ¿cuentan los 255.000 dólares de hipoteca, a los que el comprador tomó el inmueble sujeto, en su importe realizado (amount realized)? El Comisionado dijo que sí: el importe realizado eran los 2.500 dólares netos en efectivo más los 255.000 de deuda, en total 257.500 dólares.

Con esa base, el Comisionado fijó una base ajustada de 262.042,50 menos 28.045,10 de depreciación admisible, es decir, 233.997,40 dólares, frente a un importe realizado de 257.500: una ganancia de unos 23.502,60 dólares antes de su calificación (la liquidación original además repartía el precio entre terreno y edificio y trataba por separado una pérdida de capital del terreno y una ganancia ordinaria del edificio, llegando a una ganancia neta imponible de 23.767,03 dólares). El Tribunal Fiscal (3 T.C. 585) se inclinó en gran parte por ella; el Segundo Circuito revocó, y el caso llegó al Tribunal Supremo.

¿Por qué deben responderse las dos preguntas juntas? Responder solo una o bien deja escapar impuesto o bien cuenta dos veces lo mismo. Incluir la deuda en la base pero no en el importe realizado permite quedarse con la depreciación de un dinero que nunca se rinde en cuentas. Excluirla de la base e incluirla en la venta cuenta los mismos dólares dos veces. Esa simetría es el esqueleto de todo el caso.

---

## 三、判决：「财产」是楼本身，债在两端都要算

### 中文
1947 年 4 月 14 日，最高法院判决税局胜诉，首席大法官 Vinson 撰写法院意见（Crane v. Commissioner, 331 U.S. 1 (1947)）。两步推理都很直白：

第一步，定「财产」。她继承并出售的财产是土地和建筑本身，而不是扣掉贷款之后的权益。证据就在她自己的行为里：她一直按整栋楼的完整价值提折旧，税法也允许她这么提——如果她的财产只有那份价值为零的权益，这 28,045.10 美元折旧根本无从谈起。按当时《收入法典》中基数规则的前身条文（现行法对应 IRC 第 1014 条的死亡时价值基数），她的原始基数就是 262,042.50 美元。

第二步，定「实现额」。出售带债财产，卖方被解除的那笔债务与收到现金没有实质区别：买方承受抵押，等于替她把这笔债接了过去，她因此获得了与收到等额现金再去还债相同的经济利益。所以实现额包括 255,000 美元贷款余额加净现金 2,500 美元，共 257,500 美元。无追索权这一点不改变结论——贷款是真实债务，她取得财产时按真实债务处理、提了折旧，出售时就不能换一套说法。

判决还留了一个著名的尾巴：第 37 号脚注说，如果财产价值低于贷款额，无个人责任的借款人被解除的利益是否还等于全部贷款额，是「另一个可能不同的问题」，本案不处理。这个脚注悬了三十多年，直到 Tufts 案才被收掉，见第五节。

### English
On April 14, 1947, the Supreme Court held for the Commissioner, in an opinion by Chief Justice Vinson (Crane v. Commissioner, 331 U.S. 1 (1947)). The reasoning has two plain steps:

First, define the property. What she inherited and sold was the land and building themselves, not an equity interest net of the mortgage. Her own conduct proved it: she had claimed, and the tax law had allowed, depreciation measured by the building's full value — deductions that would have been impossible if her property had been a zero-value equity. Under the predecessor of the basis rule now codified at IRC section 1014 (basis set by value at death), her original basis was $262,042.50.

Second, define the amount realized. On a sale of encumbered property, relief from the debt is economically indistinguishable from cash: the buyer took the property subject to the mortgage, which is the same benefit as receiving cash and paying the debt off herself. The amount realized therefore included the $255,000 mortgage balance plus the $2,500 of net cash — $257,500 in all. The nonrecourse character of the loan did not change the answer: the debt was a true loan, it had been treated as one when she acquired the property and took depreciation, and she could not redescribe it at sale time.

The opinion left one famous loose end. Footnote 37 reserved the question whether, if the property were worth less than the mortgage, a borrower with no personal liability would still realize a benefit equal to the full debt, calling it a different problem that might be encountered on other facts. That footnote hung unresolved for more than three decades, until Tufts, taken up in section five.

### Español (译稿)
El 14 de abril de 1947, el Tribunal Supremo falló a favor del Comisionado, con opinión del presidente del Tribunal, Vinson (Crane v. Commissioner, 331 U.S. 1 (1947)). El razonamiento tiene dos pasos claros:

Primero, definir la propiedad. Lo que ella heredó y vendió fue el terreno y el edificio mismos, no una participación neta de la hipoteca. Su propia conducta lo probaba: había reclamado, y la ley fiscal le había permitido, una depreciación medida por el valor completo del edificio, deducciones imposibles si su propiedad hubiera sido una participación de valor cero. Según la norma predecesora de la hoy codificada en el artículo 1014 del IRC (base fijada por el valor a la fecha de la muerte), su base original era de 262.042,50 dólares.

Segundo, definir el importe realizado. En la venta de un bien gravado, liberarse de la deuda equivale económicamente a recibir efectivo: el comprador tomó el inmueble sujeto a la hipoteca, beneficio idéntico a recibir el dinero y pagar la deuda ella misma. El importe realizado incluyó, por tanto, los 255.000 dólares de saldo hipotecario más los 2.500 netos en efectivo: 257.500 en total. Que el préstamo fuera sin recurso personal no cambiaba la respuesta: era una deuda verdadera, así se trató al adquirir el inmueble y deducir la depreciación, y no podía redescribirse al vender.

La sentencia dejó un cabo suelto famoso. La nota 37 reservó la cuestión de si, cuando el inmueble vale menos que la hipoteca, un deudor sin responsabilidad personal seguiría realizando un beneficio igual a toda la deuda, calificándolo de problema distinto que podría presentarse con otros hechos. Esa nota quedó sin resolver más de tres décadas, hasta Tufts, que se trata en la sección cinco.

---

## 四、现行法典化：三条条文接住 Crane

### 中文
今天做带债处置，先查这三处，现行文本都留着 Crane 的逻辑：

- **IRC 第 1001 条**：第 (a) 款规定，出售或其他处置财产的利得等于实现额超过调整后基数的部分；第 (b) 款把实现额定义为收到的金钱加所收财产的公平市场价值。财政部条例 Reg. 第 1.1001-2 条进一步明确：实现额包括因处置而被解除的债务（liabilities from which the transferor is discharged），无论该债务有无追索权。
- **IRC 第 1012 条**：财产基数一般是成本，而买价里用借款支付的部分同样进成本——这就是 Crane 在购买场景下的对应面：贷款买房，基数按完整买价算，不按首付算。继承取得则走第 1014 条的死亡时价值基数，再按第 1016 条用折旧等项目往下调。
- **IRC 第 7701(g) 条**：为防止争议再起，条文直接规定，就无追索权债务担保的财产而言，该财产的公平市场价值视为不低于该无追索权债务的未偿金额。

实务上要与另一条线分清：**有追索权债务被免除**，通常走债务免除所得（cancellation of debt income，IRC 第 61(a)(11) 条），再看第 108 条的破产、无清偿能力等排除项；**无追索权债务随财产处置被接走或止赎**，则按 Crane 与 Tufts 并入实现额算处置利得，不另算债务免除所得。止赎也是一次处置：无追索权贷款止赎时，实现额就是未偿贷款余额（另加收到的其他对价）。两条线混用，是实务和考试里最常见的错法之一。

### English
For a disposition of encumbered property today, three provisions carry Crane's logic in current text:

- **IRC section 1001**: subsection (a) measures gain as the excess of the amount realized over adjusted basis, and subsection (b) defines the amount realized as money received plus the fair market value of property received. Treasury Regulation section 1.1001-2 then states expressly that the amount realized includes liabilities from which the transferor is discharged as a result of the disposition, whether or not the debt is recourse.
- **IRC section 1012**: basis is generally cost, and the borrowed portion of a purchase price is part of cost — Crane's mirror image on the buying side: a property bought with a loan takes a basis for the full price, not for the down payment. Property acquired from a decedent instead takes its section 1014 date-of-death basis, thereafter adjusted under section 1016 for items such as depreciation.
- **IRC section 7701(g)**: to foreclose the old argument, the statute provides that, for property encumbered by nonrecourse debt, the property's fair market value is treated as not less than the outstanding amount of that debt.

One neighboring line must be kept separate in practice. Cancellation of **recourse** debt ordinarily produces cancellation-of-debt income under IRC section 61(a)(11), subject to the exclusions of section 108 for bankruptcy, insolvency, and the like. Relief from **nonrecourse** debt on a sale, transfer, or foreclosure of the property is instead folded into the amount realized under Crane and Tufts and taxed as disposition gain, not separately as debt-discharge income. A foreclosure of nonrecourse debt is itself a disposition, with an amount realized equal to the outstanding loan balance (plus any other consideration received). Mixing the two lines is one of the most common errors in both practice and exam answers.

### Español (译稿)
Para disponer hoy de un bien gravado, tres normas conservan la lógica de Crane en el texto vigente:

- **Artículo 1001 del IRC**: el apartado (a) mide la ganancia como el exceso del importe realizado sobre la base ajustada, y el apartado (b) define el importe realizado como el dinero recibido más el valor justo de mercado de los bienes recibidos. El Reglamento del Tesoro, artículo 1.1001-2, precisa que el importe realizado incluye las deudas de las que el transmitente queda liberado como resultado de la disposición, sean o no con recurso personal.
- **Artículo 1012 del IRC**: la base es, en general, el costo, y la parte del precio pagada con préstamo también forma parte del costo: es la imagen especular de Crane en el lado de la compra. Una propiedad comprada con préstamo toma como base el precio completo, no el pago inicial. Lo heredado toma, en cambio, la base del artículo 1014 según el valor a la fecha de la muerte, ajustada después conforme al artículo 1016 por conceptos como la depreciación.
- **Artículo 7701(g) del IRC**: para cerrar la vieja discusión, la ley dispone que el valor justo de mercado de un bien gravado con deuda sin recurso se considera no inferior al saldo pendiente de esa deuda.

En la práctica hay que separar otra línea. La cancelación de deuda **con recurso** produce normalmente un ingreso por condonación de deuda según el artículo 61(a)(11) del IRC, sujeto a las exclusiones del artículo 108 (quiebra, insolvencia y otras). La liberación de deuda **sin recurso** al vender, transmitir o ejecutar el bien se incorpora, en cambio, al importe realizado según Crane y Tufts, y tributa como ganancia de la disposición, no como ingreso separado por condonación. La ejecución hipotecaria de una deuda sin recurso es en sí misma una disposición, con un importe realizado igual al saldo pendiente del préstamo (más cualquier otra contraprestación recibida). Confundir ambas líneas es uno de los errores más frecuentes, en la práctica y en los exámenes.

---

## 五、Tufts 补完与备考用法

### 中文
Crane 脚注 37 留下的问题是：如果楼只值 140 万，贷款却欠 185 万，卖方一分现金没拿到，实现额还按 185 万算吗？Commissioner v. Tufts, 461 U.S. 300 (1983) 的事实正好如此：合伙人处置了一处公寓项目，财产公平市场价值约 140 万美元，未偿无追索权贷款约 185.15 万美元，纳税人主张实现额只能按公平市场价值封顶、应报损失。最高法院一致判决税局胜诉：实现额按未偿贷款全额算，公平市场价值低于贷款额也不影响。理由还是对称——借款当初免税拿到、又全额进了基数提了折旧，处置时就必须全额交代；若按价值封顶，等于让纳税人确认一笔自己从未实际承受的经济损失。

至此两案合成一条完整规则，做题时照三步走：

1. **先定基数**：买价（含借款）或继承价值，减去已提或可提折旧，得调整后基数。折旧是「可提即减」，没提足也按可提额调（第 1016 条口径），不能靠少提折旧保住基数。
2. **再定实现额**：现金与其他对价，加上被买方承受或因处置解除的全部债务余额，不看财产现值是否低于债务。
3. **最后分性质**：利得再按财产性质与持有期分资本、普通（如折旧回转）等类别处理；本案的数字题走到这一步才开始分，别提前混。

给实务留一句提醒：Crane 式「幻影利得」（phantom gain）至今常见——财产贬值、现金没落袋，却因债务并入实现额而欠税。带高杠杆的房产在出售、赠与安排或止赎前，先把调整后基数与债务余额两个数字算出来再谈交易结构，顺序反了很容易在交割后才发现税单比现金还大。

### English
The question Crane's footnote 37 reserved was this: if the building is worth only $1.4 million but $1.85 million of debt is outstanding, and the seller receives no cash, is the amount realized still the full debt? Commissioner v. Tufts, 461 U.S. 300 (1983), presented exactly those facts: partners disposed of an apartment project whose fair market value was about $1.4 million against roughly $1,851,500 of unpaid nonrecourse debt, and claimed the amount realized was capped at fair market value, producing a loss. A unanimous Supreme Court held for the Commissioner: the amount realized is the full outstanding debt, and the shortfall of value below the debt is irrelevant. The reasoning is the same symmetry — the loan proceeds were received tax-free and were fully included in basis, supporting depreciation, so they must be fully accounted for on disposition; capping realization at value would let the taxpayer claim an economic loss never actually borne.

The two cases together yield one complete rule. Work any problem in three steps:

1. **Fix the basis**: purchase price (debt included) or inherited value, minus depreciation allowed or allowable, gives the adjusted basis. Depreciation reduces basis on an allowable basis under section 1016 whether or not the taxpayer actually claimed it all, so under-claiming depreciation does not preserve basis.
2. **Fix the amount realized**: cash and other consideration, plus the full balance of debt assumed by the buyer or discharged on the disposition — regardless of whether the property is now worth less than the debt.
3. **Characterize last**: only then split the gain by the property's character and holding period into capital and ordinary components such as depreciation recapture. Exam problems go wrong when characterization is attempted before the first two numbers are fixed.

One practice warning closes the loop: Crane-style "phantom gain" is still common — the property has fallen in value, little or no cash comes out, and yet tax is owed because the debt sits inside the amount realized. Before a highly leveraged property is sold, restructured, or surrendered in foreclosure, compute the adjusted basis and the outstanding debt first and design the transaction second; reversing the order is how a tax bill larger than the cash proceeds is discovered after closing.

### Español (译稿)
La pregunta que la nota 37 de Crane dejó reservada era esta: si el edificio vale solo 1,4 millones pero la deuda pendiente es de 1,85 millones, y el vendedor no recibe efectivo, ¿el importe realizado sigue siendo toda la deuda? Commissioner v. Tufts, 461 U.S. 300 (1983), presentó exactamente esos hechos: unos socios dispusieron de un complejo de apartamentos cuyo valor justo de mercado era de unos 1,4 millones frente a una deuda sin recurso pendiente de aproximadamente 1.851.500 dólares, y sostuvieron que el importe realizado quedaba limitado al valor de mercado, con una pérdida resultante. El Tribunal Supremo, por unanimidad, falló a favor del Comisionado: el importe realizado es la deuda pendiente completa, y que el valor sea inferior a la deuda es irrelevante. El razonamiento es la misma simetría: el préstamo se recibió libre de impuesto y entró por completo en la base, sustentando la depreciación, así que debe rendirse por completo al disponer; limitar la realización al valor permitiría declarar una pérdida económica nunca soportada en realidad.

Ambos casos forman una regla completa. Todo problema se resuelve en tres pasos:

1. **Fijar la base**: precio de compra (deuda incluida) o valor heredado, menos la depreciación permitida o permisible, da la base ajustada. La depreciación reduce la base por su importe permisible según el artículo 1016, se haya reclamado o no por entero.
2. **Fijar el importe realizado**: efectivo y demás contraprestación, más el saldo completo de la deuda asumida por el comprador o extinguida en la disposición, sin importar que el bien valga hoy menos que la deuda.
3. **Calificar al final**: solo entonces se reparte la ganancia según la naturaleza del bien y el período de tenencia, entre componentes de capital y ordinarios como la recuperación de la depreciación.

Una advertencia práctica cierra el tema: la «ganancia fantasma» al estilo Crane sigue siendo frecuente: el bien perdió valor, apenas sale efectivo y, sin embargo, se debe impuesto porque la deuda está dentro del importe realizado. Antes de vender, reestructurar o entregar en ejecución un inmueble muy apalancado, calcule primero la base ajustada y el saldo de la deuda, y diseñe después la operación; invertir el orden es la manera de descubrir, tras el cierre, una factura fiscal mayor que el efectivo recibido.

---

## 来源与声明

主要依据：Crane v. Commissioner, 331 U.S. 1 (1947) 判决原文（事实与数字：估值 262,042.50 美元、抵押本金 255,000 美元、可提折旧 28,045.10 美元、实现额 257,500 美元）；Commissioner v. Tufts, 461 U.S. 300 (1983)；IRC 第 61(a)(11)、1001、1012、1014、1016、108、7701(g) 条现行文本；Treas. Reg. 第 1.1001-2 条。税率与条文以 IRS 及法典现行公布文本为准，个案适用请复核最新修订。

本篇为个人学习笔记，不构成税务、财务或法律建议。具体事务请咨询持牌 CPA 或税务律师。

This article is a personal study note and does not constitute tax, financial, or legal advice. / Este artículo es una nota personal de estudio y no constituye asesoría fiscal, financiera ni legal. La versión en español es una traducción de estudio, pendiente de revisión por un hablante nativo.
