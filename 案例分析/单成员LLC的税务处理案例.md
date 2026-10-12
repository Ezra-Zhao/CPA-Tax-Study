# 单成员 LLC 的税务处理案例
# Case Study: Tax Treatment of a Single-Member LLC
# Caso práctico: tratamiento fiscal de una LLC de un solo miembro

一个人在加州开一家单成员 LLC 做咨询生意，联邦税上这家公司默认"不存在"，收入直接算到个人头上。
这篇用一组具体数字走一遍：默认穿透怎么报、自雇税怎么算、199A 扣除是什么，以及什么时候值得改选按公司纳税。
数字以 2025 税年、单身申报为口径，费率以 IRS 与加州 FTB 现行公布为准。

A single-member LLC in California is, by default, invisible for federal income tax: the income lands directly on the owner's personal return.
This walkthrough uses one set of numbers to show how the default pass-through works, how self-employment tax is computed, what the Section 199A deduction does, and when electing corporate taxation starts to make sense.
Figures use tax year 2025, single filer, with rates as published by the IRS and the California FTB.

Una LLC de un solo miembro en California es, por defecto, invisible para el impuesto federal sobre la renta: el ingreso llega directamente a la declaración personal del dueño.
Este caso recorre un conjunto de cifras para mostrar cómo funciona el régimen transparente por defecto, cómo se calcula el impuesto de trabajo por cuenta propia, qué hace la deducción de la Sección 199A y cuándo conviene optar por tributar como corporación.
Las cifras corresponden al año fiscal 2025, contribuyente soltero, con las tasas publicadas por el IRS y el FTB de California.

---

## 一、默认分类：被忽视实体 / Default classification: disregarded entity / Clasificación por defecto: entidad ignorada

**中文**

联邦税法先给实体"分类"，再谈怎么报。按 Treasury Regulations 的 check-the-box 规则（§301.7701-2、§301.7701-3）：

- 单成员 LLC 不做任何选择时，默认是 disregarded entity（被忽视实体）：税法上视为不存在，生意就是业主本人的独资经营（sole proprietorship）。
- 收入与费用报在个人税表 Form 1040 的 Schedule C（Profit or Loss from Business），净利并入个人总收入，按个人累进税率缴税。
- 业主不是公司雇员，不能给自己发 W-2 工资；从公司账户取钱叫 draw（提款），提款本身不产生税，也不能当费用扣除。
- 这个默认身份只影响所得税。雇佣税、销售税、州层面的义务（如加州 LLC 年费）各有各的规则，不因为"被忽视"而免除。

**English**

Federal tax starts by classifying the entity. Under the check-the-box regulations (Treas. Reg. §301.7701-2 and §301.7701-3):

- A single-member LLC that makes no election is a disregarded entity by default: it does not exist for federal income tax purposes, and the business is treated as the owner's sole proprietorship.
- Income and expenses are reported on Schedule C of the owner's Form 1040, and net profit is taxed at the owner's individual progressive rates.
- The owner is not an employee of the LLC and cannot take a W-2 salary from it. Money taken out is a draw — not a taxable event by itself, and not a deductible expense.
- "Disregarded" applies to income tax only. Employment taxes, sales tax, and state-level obligations (such as California's LLC charges) follow their own rules.

**Español**

El derecho fiscal federal primero clasifica la entidad. Según el reglamento check-the-box (Treas. Reg. §301.7701-2 y §301.7701-3):

- Una LLC de un solo miembro que no presenta ninguna elección es, por defecto, una entidad ignorada (disregarded entity): no existe a efectos del impuesto federal sobre la renta y el negocio se trata como empresa unipersonal del dueño.
- Los ingresos y gastos se declaran en el Anexo C (Schedule C) del Formulario 1040 del dueño, y la ganancia neta tributa a las tasas progresivas individuales.
- El dueño no es empleado de su LLC y no puede pagarse un salario con Formulario W-2. El dinero que retira es un draw (retiro): no es un hecho imponible en sí mismo ni un gasto deducible.
- Lo de «ignorada» aplica solo al impuesto sobre la renta. Los impuestos sobre el empleo, el impuesto sobre las ventas y las obligaciones estatales (como los cargos de California a las LLC) siguen sus propias reglas.

---

## 二、数字案例 / A worked example / Ejemplo numérico

**中文**

假设：加州居民，单身，经营一家单成员 LLC 做 IT 咨询，2025 年：

- 业务收入（gross receipts）：$120,000
- 可扣除经营费用（软件、设备、办公、保险等）：$40,000
- Schedule C 净利：$80,000

第一步，自雇税（Self-Employment Tax，Schedule SE）。业主不是雇员，所以社保与医保税（FICA 的对应物）要自己全额承担：

- 应税自雇收入 = $80,000 × 92.35% = $73,880
- 自雇税率 15.3%（社保 12.4% + 医保 2.9%）；2025 年社保部分的工资基数上限为 $176,100，本例未触顶，全额适用 15.3%
- 自雇税 = $73,880 × 15.3% ≈ $11,304
- 其中一半（约 $5,652）可在计算 AGI 时扣除（above-the-line deduction）

第二步，联邦所得税（简化演示，未计州税与其他调整）：

- AGI ≈ $80,000 − $5,652 = $74,348
- 减 2025 年单身标准扣除 $15,750 → $58,598
- 再减 §199A 合格营业收入扣除（见第三节）：暂按 20% × QBI $80,000 = $16,000，但 §199A(a) 还有一条总上限——扣除不得超过扣除前应税收入（减净资本利得，本例为 0）的 20%，即 $58,598 × 20% ≈ $11,720；两者取小，实际扣除 $11,720 → 应税收入 ≈ $46,878
- 按 2025 年单身税率档：10% 档 $0–$11,925，12% 档 $11,925–$48,475
- 所得税 ≈ $11,925 × 10% + ($46,878 − $11,925) × 12% ≈ $1,193 + $4,194 ≈ $5,387

合计联邦税负 ≈ $11,304 + $5,387 ≈ $16,691，占净利约 21%。注意自雇税是大头——这是很多新业主第一次报税时最意外的部分。实务上这笔税靠季度预缴（Form 1040-ES）分四次付，而不是年底一次付清。

**English**

Assume a California resident, single, running a one-person IT consulting LLC in 2025:

- Gross receipts: $120,000
- Deductible business expenses (software, equipment, office, insurance): $40,000
- Schedule C net profit: $80,000

Step 1 — self-employment tax (Schedule SE). The owner is not an employee, so both halves of the Social Security and Medicare taxes fall on the owner:

- Net earnings from self-employment = $80,000 × 92.35% = $73,880
- Rate 15.3% (12.4% Social Security + 2.9% Medicare); the 2025 Social Security wage base is $176,100, and this example stays below it, so the full 15.3% applies
- SE tax = $73,880 × 15.3% ≈ $11,304
- One half (about $5,652) is deductible in computing AGI

Step 2 — federal income tax (simplified; state tax and other adjustments ignored):

- AGI ≈ $80,000 − $5,652 = $74,348
- Less the 2025 standard deduction for a single filer, $15,750 → $58,598
- Less the §199A qualified business income deduction (Section 3 below): tentatively 20% × QBI of $80,000 = $16,000, but §199A(a) imposes an overall cap — the deduction may not exceed 20% of taxable income (computed before this deduction, minus net capital gain, which is zero here), i.e. 20% × $58,598 ≈ $11,720. The lesser amount applies: deduction of $11,720 → taxable income ≈ $46,878
- 2025 single brackets: 10% on $0–$11,925; 12% on $11,925–$48,475
- Income tax ≈ $11,925 × 10% + ($46,878 − $11,925) × 12% ≈ $1,193 + $4,194 ≈ $5,387

Total federal burden ≈ $11,304 + $5,387 ≈ $16,691, roughly 21% of net profit. Note that the SE tax is the bigger piece — the part that surprises most first-time filers. In practice it is paid through quarterly estimated payments (Form 1040-ES), not in one lump sum at filing time.

**Español**

Suponga un residente de California, soltero, con una LLC unipersonal de consultoría de TI en 2025:

- Ingresos brutos del negocio: $120.000
- Gastos deducibles (software, equipo, oficina, seguros): $40.000
- Ganancia neta en el Anexo C: $80.000

Paso 1: impuesto de trabajo por cuenta propia (Schedule SE). El dueño no es empleado, así que asume ambas mitades de los impuestos de Seguridad Social y Medicare:

- Base imponible = $80.000 × 92,35 % = $73.880
- Tasa del 15,3 % (12,4 % de Seguridad Social + 2,9 % de Medicare); el tope salarial de la Seguridad Social en 2025 es $176.100 y este ejemplo queda por debajo, así que aplica el 15,3 % completo
- Impuesto SE = $73.880 × 15,3 % ≈ $11.304
- La mitad (unos $5.652) es deducible al calcular el AGI

Paso 2: impuesto federal sobre la renta (simplificado; sin impuesto estatal ni otros ajustes):

- AGI ≈ $80.000 − $5.652 = $74.348
- Menos la deducción estándar 2025 para solteros, $15.750 → $58.598
- Menos la deducción §199A (sección 3): provisionalmente 20 % × QBI de $80.000 = $16.000, pero la §199A(a) impone un tope general: la deducción no puede superar el 20 % de la base imponible calculada antes de esta deducción (menos la ganancia neta de capital, aquí cero), es decir, 20 % × $58.598 ≈ $11.720. Rige la cifra menor: deducción de $11.720 → base imponible ≈ $46.878
- Tramos 2025 para solteros: 10 % de $0 a $11.925; 12 % de $11.925 a $48.475
- Impuesto ≈ $11.925 × 10 % + ($46.878 − $11.925) × 12 % ≈ $1.193 + $4.194 ≈ $5.387

Carga federal total ≈ $11.304 + $5.387 ≈ $16.691, alrededor del 21 % de la ganancia neta. Observe que el impuesto SE es la parte mayor: es lo que más sorprende a quienes declaran por primera vez. En la práctica se paga en cuatro pagos estimados trimestrales (Formulario 1040-ES), no en un solo pago al declarar.

---

## 三、§199A 扣除要点 / The Section 199A deduction / La deducción de la Sección 199A

**中文**

IRC §199A 给穿透实体业主一个额外扣除：合格营业收入（QBI）的 20%。要点：

- 它是税表上的扣除（在标准扣除或列举扣除之后再减），不减少自雇税的计算基数——上面案例里自雇税仍按 $80,000 全额算是这个原因。
- 有收入门槛。2025 年单身应税收入在门槛（约 $197,300 起，逐步淘汰区间约 $50,000）以下，一般可全额享受；超过门槛后，会引入 W-2 工资与资产基数限制，且特定服务行业（SSTB，如咨询、法律、医疗）在门槛以上逐步失去资格。
- 还有一条总上限（§199A(a)）：扣除额不得超过扣除前应税收入减去净资本利得后的 20%。收入不高时，这条上限比"20% × QBI"先咬到——本例的暂定扣除 $16,000 就是被它压到 $11,720 的。
- 本例业主做 IT 咨询，属于 SSTB 范畴；正因为收入在门槛以下，SSTB 的淘汰规则不适用，20% 的暂定额成立，只是最后被上面的总上限压低。收入一旦越过门槛，SSTB 资格逐步丧失，结论会完全不同——这是筹划时最先要复核的点。

**English**

IRC §199A gives owners of pass-through businesses an extra deduction of up to 20% of qualified business income (QBI). Key points:

- It is a deduction on the return (taken after the standard or itemized deduction) and it does not reduce the self-employment tax base — which is why the SE tax above is computed on the full $80,000.
- It has income thresholds. For 2025, a single filer with taxable income below the threshold (about $197,300, with a phase-in range of roughly $50,000 above it) generally gets the full 20%; above the threshold, W-2 wage and property limits phase in, and specified service trades or businesses (SSTBs — consulting, law, health, and similar) phase out entirely.
- There is also an overall cap (§199A(a)): the deduction cannot exceed 20% of taxable income (computed before this deduction) minus net capital gain. At modest income levels this cap bites before the 20%-of-QBI figure does — in the example above, it is what trims the tentative $16,000 down to $11,720.
- The IT consulting business in this example is an SSTB; because income sits below the threshold, the SSTB phase-out does not apply and the tentative 20% stands — though the overall cap then trims it, as Section 2 shows. Once income crosses the threshold, SSTB eligibility phases out and the answer changes completely — this is the first thing to re-check in any planning scenario.

**Español**

La Sección 199A del IRC concede a los dueños de negocios transparentes una deducción adicional de hasta el 20 % del ingreso comercial calificado (QBI). Puntos clave:

- Es una deducción en la declaración (posterior a la deducción estándar o detallada) y no reduce la base del impuesto de trabajo por cuenta propia; por eso el impuesto SE del ejemplo se calcula sobre los $80.000 completos.
- Tiene umbrales de ingreso. En 2025, un contribuyente soltero con base imponible por debajo del umbral (unos $197.300, con una franja de transición de unos $50.000) obtiene, por lo general, el 20 % completo; por encima, entran límites de salarios W-2 y de activos, y los negocios de servicios especificados (SSTB: consultoría, derecho, salud y similares) pierden el beneficio por completo.
- Existe además un tope general (§199A(a)): la deducción no puede superar el 20 % de la base imponible (calculada antes de esta deducción) menos la ganancia neta de capital. Con ingresos modestos, este tope actúa antes que la cifra del 20 % del QBI: en el ejemplo anterior es lo que reduce los $16.000 provisionales a $11.720.
- La consultoría de TI del ejemplo es un SSTB; como el ingreso está bajo el umbral, la exclusión de los SSTB no aplica y el 20 % provisional se mantiene, aunque luego el tope general lo reduce, como muestra la sección 2. Si el ingreso supera el umbral, la elegibilidad SSTB se pierde gradualmente y la conclusión cambia por completo: es lo primero que hay que revisar en cualquier planificación.

---

## 四、加州层面的成本 / The California layer / El nivel de California

**中文**

联邦"被忽视"不等于加州免单。加州对 LLC 另有一套收费（FTB Form 568）：

- LLC 年度税（annual tax）：$800/年，雷打不动，净亏损也要缴。
- LLC 费用（LLC fee）：按加州来源总收入（gross income，注意不是净利）分档：$250,000 以下为 $0；$250,000–$499,999 为 $900；$500,000–$999,999 为 $2,500；$1,000,000–$4,999,999 为 $6,000；$5,000,000 以上为 $11,790。
- 本例总收入 $120,000：LLC fee 为 $0，但 $800 年度税照缴。
- 此外业主个人还要按加州个人所得税率（1%–12.3% 累进）就这笔穿透收入缴州税。

一句话：评估一家小 LLC 的真实税负，要把联邦所得税 + 自雇税 + 加州 $800 与州所得税四块一起看。

**English**

Federal disregard does not mean California lets the LLC ride free. California charges LLCs separately (FTB Form 568):

- Annual tax: $800 per year, owed even in a loss year.
- LLC fee: based on California-source total (gross) income, not net profit — $0 under $250,000; $900 at $250,000–$499,999; $2,500 at $500,000–$999,999; $6,000 at $1,000,000–$4,999,999; $11,790 at $5,000,000 and above.
- In this example, gross income of $120,000 means a $0 LLC fee — but the $800 annual tax still applies.
- The owner also pays California personal income tax (progressive, 1%–12.3%) on the pass-through income.

In short, the real cost of a small LLC is four pieces together: federal income tax, SE tax, the California $800 plus state income tax.

**Español**

Que el gobierno federal «ignore» la LLC no significa que California la deje pasar. California cobra a las LLC por separado (Formulario 568 del FTB):

- Impuesto anual (annual tax): $800 por año, debido incluso en años con pérdidas.
- Cuota de LLC (LLC fee): según el ingreso total (bruto) de fuente californiana, no la ganancia neta: $0 por debajo de $250.000; $900 entre $250.000 y $499.999; $2.500 entre $500.000 y $999.999; $6.000 entre $1.000.000 y $4.999.999; $11.790 desde $5.000.000.
- En este ejemplo, con ingresos brutos de $120.000, la cuota es $0, pero el impuesto anual de $800 sí aplica.
- El dueño paga además el impuesto estatal sobre la renta de California (progresivo, del 1 % al 12,3 %) sobre el ingreso transparente.

En resumen, el costo real de una LLC pequeña son cuatro piezas juntas: impuesto federal sobre la renta, impuesto SE, los $800 de California y el impuesto estatal.

---

## 五、改选按公司纳税 / Electing corporate treatment / Optar por tributar como corporación

**中文**

默认不是唯一选项。单成员 LLC 可以：

- 提交 Form 8832，选择按 C 公司纳税：公司独立报 Form 1120，按 21% 联邦公司税率缴税；但利润分红给个人时再缴一层股息税（双重征税），且业主给自己发工资要走 payroll 并缴雇佣税。
- 或提交 Form 2553 选 S 公司（单独提交 2553 即被视为同时作出按公司分类的选择，不必先交 Form 8832）：仍是穿透（报 Form 1120-S，K-1 给个人），但业主可以以雇员身份领"合理工资"（reasonable compensation），工资部分缴雇佣税，剩余利润分配不缴自雇税——省税逻辑就在这条缝里。代价是 payroll 申报、账务与合规成本上升，且工资必须"合理"，明显压低工资会被 IRS 重新归类。
- 加州注意：S 公司在加州另有 1.5% 的特许经营税（franchise tax，最低 $800），联邦省下的要先扣掉这一块再比较。
- 选择有生效日与撤销限制（Form 8832 的选择一般有 60 个月锁定期的规则），属于需要先算账、再动手的决定。

什么时候开始值得算这笔账？经验上，当 Schedule C 净利稳定超过约 $40,000–$60,000、自雇税成为主要税负时，S 公司方案通常进入可讨论区间；低于这个量级，合规成本往往吃掉省下的税。

**English**

The default is not the only option. A single-member LLC can:

- File Form 8832 to be taxed as a C corporation: the company files Form 1120 and pays the flat 21% federal corporate rate — but profits distributed to the owner are taxed again as dividends (double taxation), and paying the owner a salary means running payroll with employment taxes.
- Or file Form 2553 to elect S status (filing Form 2553 alone is treated as also making the corporate classification election — no prior Form 8832 is required): still a pass-through (Form 1120-S, Schedule K-1 to the owner), but the owner takes a "reasonable compensation" salary subject to employment tax, while remaining profit distributions escape SE tax. That gap is where the savings live. The costs: payroll filings, heavier bookkeeping, and a salary that must genuinely be reasonable — an artificially low salary can be reclassified by the IRS.
- California caveat: an S corporation owes California's 1.5% franchise tax (minimum $800), which must be netted against the federal savings before deciding.
- Elections have effective-date and revocation limits (a Form 8832 election is generally locked in for 60 months), so this is a compute-first decision.

As a rule of thumb, once Schedule C profit is steadily above roughly $40,000–$60,000 and SE tax becomes the dominant cost, the S corporation analysis is usually worth running. Below that range, compliance costs often eat the savings.

**Español**

La opción por defecto no es la única. Una LLC de un solo miembro puede:

- Presentar el Formulario 8832 para tributar como corporación C: la empresa declara el Formulario 1120 y paga la tasa corporativa federal fija del 21 %, pero las ganancias distribuidas al dueño tributan otra vez como dividendos (doble imposición), y pagarle un salario exige nómina con impuestos sobre el empleo.
- O presentar el Formulario 2553 para elegir el estatus S (presentar solo el 2553 se trata también como elección de clasificación corporativa; no hace falta un 8832 previo): sigue siendo transparente (Formulario 1120-S, Anexo K-1 al dueño), pero el dueño cobra un salario de «compensación razonable» sujeto a impuestos sobre el empleo, mientras que el resto de la ganancia distribuida escapa al impuesto SE. En esa diferencia está el ahorro. Los costos: declaraciones de nómina, contabilidad más pesada y un salario que debe ser realmente razonable; un salario artificialmente bajo puede ser reclasificado por el IRS.
- Advertencia de California: una corporación S debe el impuesto de franquicia estatal del 1,5 % (mínimo $800), que hay que descontar del ahorro federal antes de decidir.
- Las elecciones tienen reglas de fecha de vigencia y revocación (la elección del Formulario 8832, en general, queda bloqueada por 60 meses), así que es una decisión que se calcula antes de actuar.

Como referencia práctica: cuando la ganancia del Anexo C supera de forma estable unos $40.000–$60.000 y el impuesto SE se vuelve el costo dominante, suele valer la pena analizar la vía S. Por debajo de ese rango, los costos de cumplimiento a menudo se comen el ahorro.

---

## 参考来源 / References / Referencias

- IRC §199A（合格营业收入扣除）；Treas. Reg. §301.7701-2、§301.7701-3（实体分类）
- IRS Publication 334《Tax Guide for Small Business》；Publication 583《Starting a Business and Keeping Records》；IRS《Guide to Business Expense Resources》（原 Publication 535《Business Expenses》已停刊，最后版本为 2022 年）
- IRS《Single Member Limited Liability Companies》专题页（irs.gov）；Schedule SE 说明（自雇税与 92.35% 系数、社保工资基数）
- California FTB，Form 568 说明与 LLC fee 分档表（ftb.ca.gov）
- IRS Rev. Proc. 与 2025 年税率档公告（标准扣除、税率档、社保工资基数）

---

*学习笔记，不构成建议。本仓库为个人学习记录，所举数字为教学简化的示例，不构成税务建议；具体申报请以 IRS、FTB 现行原文与持牌 CPA 的意见为准。*

*Study notes only. Figures are simplified teaching examples, not tax advice; for an actual filing, rely on current IRS and FTB guidance and a licensed CPA.*

*Solo notas de estudio. Las cifras son ejemplos didácticos simplificados, no asesoría fiscal; para una declaración real, siga las normas vigentes del IRS y del FTB y el criterio de un CPA con licencia.*
