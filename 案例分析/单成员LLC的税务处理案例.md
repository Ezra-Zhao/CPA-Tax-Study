# 单成员 LLC 的税务处理案例
# Case Study: Tax Treatment of a Single-Member LLC
# Caso práctico: tratamiento fiscal de una LLC de un solo miembro
# 사례 연구: 단일 구성원 LLC의 세무 처리
# Nghiên cứu trường hợp: Xử lý thuế của LLC một thành viên
# केस अध्ययन: एकल-सदस्य LLC का कर उपचार

一个人在加州开一家单成员 LLC 做咨询生意，联邦税上这家公司默认"不存在"，收入直接算到个人头上。
这篇用一组具体数字走一遍：默认穿透怎么报、自雇税怎么算、199A 扣除是什么，以及什么时候值得改选按公司纳税。
数字以 2025 税年、单身申报为口径，费率以 IRS 与加州 FTB 现行公布为准。

A single-member LLC in California is, by default, invisible for federal income tax: the income lands directly on the owner's personal return.
This walkthrough uses one set of numbers to show how the default pass-through works, how self-employment tax is computed, what the Section 199A deduction does, and when electing corporate taxation starts to make sense.
Figures use tax year 2025, single filer, with rates as published by the IRS and the California FTB.

Una LLC de un solo miembro en California es, por defecto, invisible para el impuesto federal sobre la renta: el ingreso llega directamente a la declaración personal del dueño.
Este caso recorre un conjunto de cifras para mostrar cómo funciona el régimen transparente por defecto, cómo se calcula el impuesto de trabajo por cuenta propia, qué hace la deducción de la Sección 199A y cuándo conviene optar por tributar como corporación.
Las cifras corresponden al año fiscal 2025, contribuyente soltero, con las tasas publicadas por el IRS y el FTB de California.


**한국어 (초역, 원어민 감수 대기)**

캘리포니아에서 한 사람이 단일 구성원 LLC를 열어 컨설팅 사업을 하면, 연방세상 이 회사는 기본적으로 "존재하지 않으며", 소득이 바로 개인에게 귀속된다.
이 글에서는 한 세트의 구체적인 숫자로 전체 과정을 따라간다: 기본 통과 방식의 신고 방법, 자영업세의 계산 방법, 199A 공제가 무엇인지, 그리고 언제 회사 과세로 바꾸는 것이 가치 있는지를 다룬다.
숫자는 2025 과세 연도, 단독 신고 기준이며, 세율은 IRS와 캘리포니아 FTB의 현행 공표를 기준으로 한다.

**Tiếng Việt (bản dịch sơ bộ, chờ người bản ngữ hiệu đính)**

Một người mở LLC một thành viên ở California làm kinh doanh tư vấn, về thuế liên bang công ty này mặc định "không tồn tại", thu nhập tính thẳng vào cá nhân.
Bài này dùng một bộ con số cụ thể đi qua một lượt: chế độ xuyên thấu mặc định khai thế nào, thuế tự doanh tính thế nào, khấu trừ 199A là gì, và khi nào đáng đổi sang chọn nộp thuế theo công ty.
Con số lấy chuẩn năm thuế 2025, khai đơn độc thân, thuế suất theo công bố hiện hành của IRS và FTB California.

**हिन्दी (अनुवाद, मूल-भाषी समीक्षा लंबित)**

एक व्यक्ति कैलिफ़ोर्निया में एकल-सदस्य LLC खोलकर परामर्श व्यवसाय करता है, संघीय कर में यह कंपनी डिफ़ॉल्ट रूप से "अस्तित्वहीन" है, आय सीधे व्यक्ति पर गिनी जाती है।
यह लेख संख्याओं के एक सेट के साथ पूरी प्रक्रिया चलता है: डिफ़ॉल्ट पास-थ्रू कैसे रिपोर्ट होता है, स्व-रोज़गार कर कैसे गिना जाता है, 199A कटौती क्या है, और कब कंपनी के रूप में कर देना चुनना सार्थक होता है।
संख्याएँ कर वर्ष 2025, एकल दाखिल के मानक पर हैं, दरें IRS और कैलिफ़ोर्निया FTB के वर्तमान प्रकाशनों के अनुसार हैं।
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

**한국어 (초역, 원어민 감수 대기)**

연방 세법은 먼저 실체에 "분류"를 한 뒤에 신고 방법을 논한다. Treasury Regulations의 check-the-box 규칙(§301.7701-2, §301.7701-3)에 따르면:

- 단일 구성원 LLC가 어떤 선택도 하지 않으면, 기본값은 disregarded entity(무시되는 실체)이다: 세법상 존재하지 않는 것으로 보며, 사업은 소유주 본인의 개인사업(sole proprietorship)이다.
- 소득과 비용은 개인 신고서 Form 1040의 Schedule C(Profit or Loss from Business)에 신고하고, 순이익은 개인 총소득에 합산되어 개인 누진세율로 과세된다.
- 소유주는 회사의 직원이 아니므로, 자신에게 W-2 급여를 줄 수 없다. 회사 계좌에서 돈을 꺼내는 것은 draw(인출)라고 하며, 인출 자체는 세금을 발생시키지 않고, 비용으로 공제할 수도 없다.
- 이 기본 신분은 소득세에만 영향을 미친다. 고용세, 판매세, 주 차원의 의무(예: 캘리포니아 LLC 연회비)는 각자 규칙이 있으며, "무시된다"고 면제되지 않는다.

**Tiếng Việt (bản dịch sơ bộ, chờ người bản ngữ hiệu đính)**

Luật thuế liên bang trước hết "phân loại" thực thể, rồi mới bàn cách khai. Theo quy tắc check-the-box của Treasury Regulations (§301.7701-2, §301.7701-3):

- LLC một thành viên không làm lựa chọn nào, mặc định là disregarded entity (thực thể bị bỏ qua): về luật thuế coi như không tồn tại, việc kinh doanh là hộ kinh doanh cá thể (sole proprietorship) của chính chủ sở hữu.
- Thu nhập và chi phí khai trên Schedule C (Profit or Loss from Business) của Form 1040 cá nhân, lợi nhuận ròng gộp vào tổng thu nhập cá nhân, nộp thuế theo biểu thuế lũy tiến cá nhân.
- Chủ sở hữu không phải nhân viên của công ty, không thể trả lương W-2 cho mình; lấy tiền từ tài khoản công ty gọi là draw (rút vốn), bản thân việc rút không sinh thuế, cũng không được tính là chi phí khấu trừ.
- Thân phận mặc định này chỉ ảnh hưởng thuế thu nhập. Thuế việc làm, thuế bán hàng, nghĩa vụ cấp bang (như phí năm LLC của California) có quy tắc riêng, không vì "bị bỏ qua" mà được miễn.

**हिन्दी (अनुवाद, मूल-भाषी समीक्षा लंबित)**

संघीय कर कानून पहले इकाई को "वर्गीकृत" करता है, फिर रिपोर्टिंग की बात करता है। Treasury Regulations के check-the-box नियमों (§301.7701-2, §301.7701-3) के अनुसार:

- एकल-सदस्य LLC कोई चुनाव न करे तो डिफ़ॉल्ट disregarded entity (अनदेखी इकाई) है: कर कानून में उसे अस्तित्वहीन माना जाता है, व्यवसाय स्वामी का स्वयं का एकल स्वामित्व (sole proprietorship) है।
- आय और व्यय व्यक्तिगत विवरणी Form 1040 के Schedule C (Profit or Loss from Business) पर रिपोर्ट होते हैं, शुद्ध लाभ व्यक्तिगत कुल आय में जुड़कर व्यक्तिगत प्रगतिशील दरों से कर लगता है।
- स्वामी कंपनी का कर्मचारी नहीं है, स्वयं को W-2 वेतन नहीं दे सकता; कंपनी खाते से धन निकालना draw (आहरण) कहलाता है, आहरण स्वयं कर उत्पन्न नहीं करता, और उसे व्यय के रूप में भी नहीं काटा जा सकता।
- यह डिफ़ॉल्ट स्थिति केवल आयकर को प्रभावित करती है। रोज़गार कर, बिक्री कर, राज्य स्तर के दायित्व (जैसे कैलिफ़ोर्निया LLC वार्षिक शुल्क) के अपने नियम हैं, "अनदेखा" होने से वे माफ़ नहीं होते।

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

**한국어 (초역, 원어민 감수 대기)**

가정: 캘리포니아 거주자, 단독, 단일 구성원 LLC를 운영하며 IT 컨설팅을 하고, 2025년:

- 사업 총수입(gross receipts): $120,000
- 공제 가능한 사업 비용(소프트웨어, 장비, 사무, 보험 등): $40,000
- Schedule C 순이익: $80,000

첫 단계, 자영업세(Self-Employment Tax, Schedule SE). 소유주는 직원이 아니므로, 사회보험 및 의료보험세(FICA에 대응)를 본인이 전액 부담한다:

- 과세 자영업 소득 = $80,000 × 92.35% = $73,880
- 자영업세율 15.3%(사회보험 12.4% + 의료보험 2.9%); 2025년 사회보험 부분의 임금 기준 상한은 $176,100이며, 본 사례는 상한에 닿지 않아 전액 15.3%가 적용된다
- 자영업세 = $73,880 × 15.3% ≈ $11,304
- 그 절반(약 $5,652)은 AGI 계산 시 공제할 수 있다(above-the-line deduction)

두 번째 단계, 연방 소득세(단순화된 시범, 주세와 기타 조정은 계산하지 않음):

- AGI ≈ $80,000 − $5,652 = $74,348
- 2025년 단독 표준공제 $15,750을 빼면 → $58,598
- §199A 적격 사업소득 공제를 다시 뺀다(제3절 참조): 잠정적으로 20% × QBI $80,000 = $16,000이지만, §199A(a)에는 총 상한이 또 하나 있다 — 공제는 공제 전 과세소득(순자본 이득을 뺀 금액, 본 사례에서는 0)의 20%를 초과할 수 없으며, 즉 $58,598 × 20% ≈ $11,720이다. 둘 중 더 작은 값을 취하므로 실제 공제는 $11,720 → 과세소득 ≈ $46,878
- 2025년 단독 세율 구간 기준: 10% 구간 $0–$11,925, 12% 구간 $11,925–$48,475
- 소득세 ≈ $11,925 × 10% + ($46,878 − $11,925) × 12% ≈ $1,193 + $4,194 ≈ $5,387

연방 세 부담 합계 ≈ $11,304 + $5,387 ≈ $16,691로, 순이익의 약 21%이다. 자영업세가 큰 부분을 차지한다는 점에 유의하라 — 이는 많은 신규 소유주가 첫 신고 때 가장 놀라는 부분이다. 실무에서 이 세금은 분기별 추정 납부(Form 1040-ES)로 네 번에 나눠 내며, 연말에 한 번에 완납하지 않는다.

**Tiếng Việt (bản dịch sơ bộ, chờ người bản ngữ hiệu đính)**

Giả thiết: cư dân California, độc thân, vận hành một LLC một thành viên làm tư vấn IT, năm 2025:

- Tổng thu kinh doanh (gross receipts): $120,000
- Chi phí kinh doanh được khấu trừ (phần mềm, thiết bị, văn phòng, bảo hiểm, v.v.): $40,000
- Lợi nhuận ròng Schedule C: $80,000

Bước một, thuế tự doanh (Self-Employment Tax, Schedule SE). Chủ sở hữu không phải nhân viên, nên thuế bảo hiểm xã hội và y tế (vật tương ứng của FICA) phải tự gánh toàn bộ:

- Thu nhập tự doanh chịu thuế = $80,000 × 92.35% = $73,880
- Thuế suất tự doanh 15.3% (bảo hiểm xã hội 12.4% + bảo hiểm y tế 2.9%); trần cơ sở lương của phần bảo hiểm xã hội năm 2025 là $176,100, trường hợp này chưa chạm trần, áp dụng toàn bộ 15.3%
- Thuế tự doanh = $73,880 × 15.3% ≈ $11,304
- Một nửa trong đó (khoảng $5,652) được khấu trừ khi tính AGI (above-the-line deduction)

Bước hai, thuế thu nhập liên bang (trình diễn đơn giản hóa, chưa tính thuế bang và điều chỉnh khác):

- AGI ≈ $80,000 − $5,652 = $74,348
- Trừ khấu trừ tiêu chuẩn độc thân 2025 $15,750 → $58,598
- Trừ tiếp khấu trừ thu nhập kinh doanh đủ điều kiện §199A (xem tiết ba): tạm tính 20% × QBI $80,000 = $16,000, nhưng §199A(a) còn một trần tổng nữa — khấu trừ không được vượt 20% của thu nhập chịu thuế trước khấu trừ (trừ lãi vốn ròng, trường hợp này là 0), tức $58,598 × 20% ≈ $11,720; lấy giá trị nhỏ hơn trong hai giá trị, khấu trừ thực tế $11,720 → thu nhập chịu thuế ≈ $46,878
- Theo bậc thuế độc thân 2025: bậc 10% $0–$11,925, bậc 12% $11,925–$48,475
- Thuế thu nhập ≈ $11,925 × 10% + ($46,878 − $11,925) × 12% ≈ $1,193 + $4,194 ≈ $5,387

Tổng gánh nặng thuế liên bang ≈ $11,304 + $5,387 ≈ $16,691, chiếm khoảng 21% lợi nhuận ròng. Lưu ý thuế tự doanh là phần lớn — đây là phần nhiều chủ sở hữu mới bất ngờ nhất khi khai thuế lần đầu. Trong thực tế, khoản thuế này dựa vào nộp tạm tính theo quý (Form 1040-ES) chia bốn lần, chứ không phải cuối năm nộp một lần.

**हिन्दी (अनुवाद, मूल-भाषी समीक्षा लंबित)**

मान लीजिए: कैलिफ़ोर्निया निवासी, एकल, एक एकल-सदस्य LLC चलाकर IT परामर्श करता है, 2025 में:

- व्यवसाय कुल प्राप्तियाँ (gross receipts): $120,000
- कटौती योग्य व्यवसाय व्यय (सॉफ़्टवेयर, उपकरण, कार्यालय, बीमा आदि): $40,000
- Schedule C शुद्ध लाभ: $80,000

पहला कदम, स्व-रोज़गार कर (Self-Employment Tax, Schedule SE)। स्वामी कर्मचारी नहीं है, इसलिए सामाजिक सुरक्षा और चिकित्सा कर (FICA के समकक्ष) उसे स्वयं पूरा वहन करना होगा:

- करयोग्य स्व-रोज़गार आय = $80,000 × 92.35% = $73,880
- स्व-रोज़गार कर दर 15.3% (सामाजिक सुरक्षा 12.4% + चिकित्सा 2.9%); 2025 में सामाजिक सुरक्षा भाग की वेतन आधार सीमा $176,100 है, यह उदाहरण सीमा तक नहीं पहुँचता, पूरी 15.3% लागू होती है
- स्व-रोज़गार कर = $73,880 × 15.3% ≈ $11,304
- इसका आधा (लगभग $5,652) AGI की गणना में काटा जा सकता है (above-the-line deduction)

दूसरा कदम, संघीय आयकर (सरलीकृत प्रदर्शन, राज्य कर और अन्य समायोजन शामिल नहीं):

- AGI ≈ $80,000 − $5,652 = $74,348
- 2025 की एकल मानक कटौती $15,750 घटाएँ → $58,598
- फिर §199A योग्य व्यवसाय आय कटौती घटाएँ (तीसरा भाग देखें): अस्थायी रूप से 20% × QBI $80,000 = $16,000, लेकिन §199A(a) में एक कुल सीमा और है — कटौती, कटौती-पूर्व करयोग्य आय (शुद्ध पूँजी लाभ घटाकर, इस उदाहरण में 0) के 20% से अधिक नहीं हो सकती, अर्थात $58,598 × 20% ≈ $11,720; दोनों में से छोटा लें, वास्तविक कटौती $11,720 → करयोग्य आय ≈ $46,878
- 2025 की एकल कर दर सारणी के अनुसार: 10% स्लैब $0–$11,925, 12% स्लैब $11,925–$48,475
- आयकर ≈ $11,925 × 10% + ($46,878 − $11,925) × 12% ≈ $1,193 + $4,194 ≈ $5,387

कुल संघीय कर भार ≈ $11,304 + $5,387 ≈ $16,691, शुद्ध लाभ का लगभग 21%। ध्यान दें कि स्व-रोज़गार कर बड़ा हिस्सा है — यह वह भाग है जिस पर कई नए स्वामी पहली विवरणी में सबसे अधिक चौंकते हैं। व्यवहार में यह कर तिमाही अनुमानित भुगतान (Form 1040-ES) से चार बार में दिया जाता है, वर्ष के अंत में एक बार में नहीं।

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

**한국어 (초역, 원어민 감수 대기)**

IRC §199A는 통과 실체 소유주에게 추가 공제를 준다: 적격 사업소득(QBI)의 20%. 요점:

- 이는 신고서상의 공제이다(표준공제나 항목공제 뒤에 다시 빼는 것). 자영업세의 계산 기준을 줄이지 않는다 — 위 사례에서 자영업세가 여전히 $80,000 전액으로 계산된 이유가 이것이다.
- 소득 문턱이 있다. 2025년 단독 과세소득이 문턱(약 $197,300부터, 단계적 배제 구간 약 $50,000) 이하이면, 일반적으로 전액을 누릴 수 있다. 문턱을 넘으면 W-2 급여와 자산 기준 제한이 도입되고, 특정 서비스 업종(SSTB, 예: 컨설팅, 법률, 의료)은 문턱 이상에서 점진적으로 자격을 잃는다.
- 총 상한이 또 하나 있다(§199A(a)): 공제액은 공제 전 과세소득에서 순자본 이득을 뺀 금액의 20%를 초과할 수 없다. 소득이 높지 않을 때, 이 상한이 "20% × QBI"보다 먼저 물어뜯는다 — 본 사례의 잠정 공제 $16,000이 $11,720으로 눌린 이유가 이것이다.
- 본 사례의 소유주는 IT 컨설팅을 하며, SSTB 범주에 속한다. 소득이 문턱 이하이기 때문에 SSTB의 배제 규칙이 적용되지 않고, 20%의 잠정액이 성립하되, 마지막에 위의 총 상한에 눌려 낮아졌다. 소득이 문턱을 넘는 순간, SSTB 자격은 점진적으로 사라지고, 결론은 완전히 달라진다 — 이는 계획 시 가장 먼저 재확인해야 할 지점이다.

**Tiếng Việt (bản dịch sơ bộ, chờ người bản ngữ hiệu đính)**

IRC §199A cho chủ sở hữu thực thể xuyên thấu một khấu trừ bổ sung: 20% thu nhập kinh doanh đủ điều kiện (QBI). Điểm chính:

- Nó là khấu trừ trên tờ khai (trừ tiếp sau khấu trừ tiêu chuẩn hoặc khấu trừ liệt kê), không làm giảm cơ sở tính thuế tự doanh — đó là lý do trong trường hợp trên thuế tự doanh vẫn tính trên toàn bộ $80,000.
- Có ngưỡng thu nhập. Năm 2025, thu nhập chịu thuế độc thân dưới ngưỡng (khoảng từ $197,300, khoảng loại trừ dần khoảng $50,000) thì thông thường được hưởng toàn bộ; vượt ngưỡng, sẽ đưa vào giới hạn lương W-2 và cơ sở tài sản, và ngành dịch vụ đặc định (SSTB, như tư vấn, luật, y tế) trên ngưỡng dần mất tư cách.
- Còn một trần tổng nữa (§199A(a)): số khấu trừ không được vượt 20% của thu nhập chịu thuế trước khấu trừ trừ lãi vốn ròng. Khi thu nhập không cao, trần này "cắn" trước "20% × QBI" — số khấu trừ tạm tính $16,000 của trường hợp này bị ép xuống $11,720 là vì nó.
- Chủ sở hữu trường hợp này làm tư vấn IT, thuộc phạm trù SSTB; chính vì thu nhập dưới ngưỡng, quy tắc loại trừ của SSTB không áp dụng, số tạm tính 20% thành lập, chỉ cuối cùng bị trần tổng trên ép thấp. Thu nhập một khi vượt ngưỡng, tư cách SSTB dần mất, kết luận sẽ hoàn toàn khác — đây là điểm phải phúc tra đầu tiên khi hoạch định.

**हिन्दी (अनुवाद, मूल-भाषी समीक्षा लंबित)**

IRC §199A पास-थ्रू इकाई स्वामियों को एक अतिरिक्त कटौती देता है: योग्य व्यवसाय आय (QBI) का 20%। मुख्य बिंदु:

- यह विवरणी पर मिलने वाली कटौती है (मानक कटौती या मदवार कटौती के बाद फिर घटाई जाती है), यह स्व-रोज़गार कर के गणना आधार को नहीं घटाती — ऊपर के उदाहरण में स्व-रोज़गार कर फिर भी पूरे $80,000 पर गिना गया, इसका यही कारण है।
- आय सीमा है। 2025 में एकल करयोग्य आय सीमा (लगभग $197,300 से शुरू, चरणबद्ध समाप्ति दायरा लगभग $50,000) से नीचे हो तो आमतौर पर पूरी कटौती मिलती है; सीमा से ऊपर जाने पर W-2 वेतन और संपत्ति आधार सीमाएँ आ जाती हैं, और विशिष्ट सेवा व्यवसाय (SSTB, जैसे परामर्श, कानून, चिकित्सा) सीमा के ऊपर धीरे-धीरे पात्रता खोते हैं।
- एक कुल सीमा और है (§199A(a)): कटौती राशि कटौती-पूर्व करयोग्य आय से शुद्ध पूँजी लाभ घटाने के बाद की राशि के 20% से अधिक नहीं हो सकती। आय अधिक न हो तो यह सीमा "20% × QBI" से पहले काटती है — इस उदाहरण की अस्थायी कटौती $16,000 इसी से दबकर $11,720 हुई।
- इस उदाहरण का स्वामी IT परामर्श करता है, SSTB श्रेणी में आता है; आय सीमा से नीचे होने के कारण ही SSTB की समाप्ति नियम लागू नहीं होते, 20% की अस्थायी राशि बनती है, केवल अंत में ऊपर की कुल सीमा से दब जाती है। आय सीमा पार करते ही SSTB पात्रता धीरे-धीरे समाप्त होगी, निष्कर्ष पूरी तरह बदल जाएगा — योजना बनाते समय यह सबसे पहले फिर से जाँचने वाला बिंदु है।

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

**한국어 (초역, 원어민 감수 대기)**

연방에서 "무시된다"고 캘리포니아에서 면제되는 것은 아니다. 캘리포니아는 LLC에 별도의 요금을 부과한다(FTB Form 568):

- LLC 연간세(annual tax): $800/년, 흔들리지 않으며, 순손실이어도 내야 한다.
- LLC 수수료(LLC fee): 캘리포니아 출처 총소득(gross income, 순이익이 아님에 유의)을 기준으로 구간이 나뉜다: $250,000 미만 $0; $250,000–$499,999 $900; $500,000–$999,999 $2,500; $1,000,000–$4,999,999 $6,000; $5,000,000 이상 $11,790.
- 본 사례의 총소득은 $120,000이다: LLC fee는 $0이지만, $800 연간세는 그대로 낸다.
- 그 밖에 소유주 개인은 이 통과 소득에 대해 캘리포니아 개인소득세율(1%–12.3% 누진)로 주세도 내야 한다.

한 마디로: 작은 LLC의 실제 세 부담을 평가하려면, 연방 소득세 + 자영업세 + 캘리포니아 $800 + 주 소득세, 네 덩어리를 함께 봐야 한다.

**Tiếng Việt (bản dịch sơ bộ, chờ người bản ngữ hiệu đính)**

Liên bang "bỏ qua" không có nghĩa California miễn đơn. California có một bộ thu phí riêng đối với LLC (FTB Form 568):

- Thuế năm LLC (annual tax): $800/năm, không lay chuyển, lỗ ròng cũng phải nộp.
- Phí LLC (LLC fee): phân bậc theo tổng thu nhập nguồn California (gross income, lưu ý không phải lợi nhuận ròng): dưới $250,000 là $0; $250,000–$499,999 là $900; $500,000–$999,999 là $2,500; $1,000,000–$4,999,999 là $6,000; $5,000,000 trở lên là $11,790.
- Trường hợp này tổng thu nhập $120,000: LLC fee là $0, nhưng thuế năm $800 vẫn nộp đủ.
- Ngoài ra chủ sở hữu cá nhân còn phải nộp thuế thu nhập cá nhân California (lũy tiến 1%–12.3%) trên khoản thu nhập xuyên thấu này.

Một câu: đánh giá gánh nặng thuế thật của một LLC nhỏ, phải nhìn cùng nhau bốn khối: thuế thu nhập liên bang + thuế tự doanh + $800 California + thuế thu nhập bang.

**हिन्दी (अनुवाद, मूल-भाषी समीक्षा लंबित)**

संघीय स्तर पर "अनदेखा" होने का अर्थ कैलिफ़ोर्निया में छूट नहीं है। कैलिफ़ोर्निया LLC पर अलग शुल्क लगाता है (FTB Form 568):

- LLC वार्षिक कर (annual tax): $800/वर्ष, अटल है, शुद्ध हानि हो तो भी देना होगा।
- LLC शुल्क (LLC fee): कैलिफ़ोर्निया स्रोत कुल आय (gross income, ध्यान दें शुद्ध लाभ नहीं) के अनुसार स्तर: $250,000 से कम $0; $250,000–$499,999 $900; $500,000–$999,999 $2,500; $1,000,000–$4,999,999 $6,000; $5,000,000 या अधिक $11,790।
- इस उदाहरण की कुल आय $120,000 है: LLC fee $0 है, लेकिन $800 वार्षिक कर फिर भी देना होगा।
- इसके अलावा स्वामी को व्यक्तिगत रूप से इस पास-थ्रू आय पर कैलिफ़ोर्निया व्यक्तिगत आयकर दरों (1%–12.3% प्रगतिशील) से राज्य कर भी देना होगा।

एक वाक्य में: एक छोटे LLC के वास्तविक कर भार का मूल्यांकन करने के लिए संघीय आयकर + स्व-रोज़गार कर + कैलिफ़ोर्निया $800 + राज्य आयकर, चारों खंडों को साथ देखना होगा।

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

**한국어 (초역, 원어민 감수 대기)**

기본값이 유일한 선택지는 아니다. 단일 구성원 LLC는 다음을 할 수 있다:

- Form 8832를 제출해 C 법인으로 과세되기를 선택한다: 회사는 Form 1120을 독립 신고하고 21% 연방 법인세율로 세금을 낸다. 그러나 이익을 개인에게 배당하면 한 층의 배당세가 더해지고(이중과세), 소유주가 자신에게 급여를 주려면 payroll을 거쳐 고용세를 내야 한다.
- 또는 Form 2553을 제출해 S 법인을 선택한다(2553만 단독 제출해도 회사 분류 선택을 동시에 한 것으로 간주되며, 먼저 Form 8832를 낼 필요가 없다): 여전히 통과 방식이지만(Form 1120-S 신고, K-1을 개인에게), 소유주는 직원 신분으로 "합리적 급여"(reasonable compensation)를 받을 수 있고, 급여 부분은 고용세를 내며, 남은 이익 분배는 자영업세를 내지 않는다 — 절세 논리가 바로 이 틈에 있다. 대가는 payroll 신고, 장부와 준수 비용의 상승이며, 급여는 "합리적"이어야 하고, 명백히 낮게 누른 급여는 IRS가 재분류한다.
- 캘리포니아 유의: S 법인은 캘리포니아에서 별도로 1.5%의 프랜차이즈세(franchise tax, 최저 $800)가 있어, 연방에서 아낀 금액은 이 부분을 먼저 빼고 비교해야 한다.
- 선택에는 발효일과 취소 제한이 있다(Form 8832의 선택에는 일반적으로 60개월 잠금 기간 규칙이 있다). 이는 먼저 계산한 뒤에 움직여야 할 결정에 속한다.

언제부터 이 계산을 할 가치가 생기는가? 경험상, Schedule C 순이익이 안정적으로 약 $40,000–$60,000을 넘고, 자영업세가 주요 세 부담이 될 때, S 법인 방안이 통상 논의 가능한 구간에 들어간다. 이 수준보다 낮으면, 준수 비용이 아낀 세금을 먹어버리는 경우가 많다.

**Tiếng Việt (bản dịch sơ bộ, chờ người bản ngữ hiệu đính)**

Mặc định không phải lựa chọn duy nhất. LLC một thành viên có thể:

- Nộp Form 8832, chọn nộp thuế theo công ty C: công ty khai độc lập Form 1120, nộp thuế theo thuế suất công ty liên bang 21%; nhưng lợi nhuận chia cho cá nhân lại thêm một tầng thuế cổ tức (đánh thuế hai lần), và chủ sở hữu trả lương cho mình phải qua payroll và nộp thuế việc làm.
- Hoặc nộp Form 2553 chọn công ty S (chỉ nộp riêng 2553 đã được coi là đồng thời làm lựa chọn phân loại công ty, không cần nộp Form 8832 trước): vẫn là xuyên thấu (khai Form 1120-S, K-1 cho cá nhân), nhưng chủ sở hữu có thể với thân phận nhân viên nhận "lương hợp lý" (reasonable compensation), phần lương nộp thuế việc làm, phần phân phối lợi nhuận còn lại không nộp thuế tự doanh — logic tiết kiệm thuế nằm ở khe này. Cái giá là khai báo payroll, chi phí sổ sách và tuân thủ tăng, và lương phải "hợp lý", lương ép thấp rõ ràng sẽ bị IRS phân loại lại.
- Lưu ý California: công ty S ở California còn có thuế nhượng quyền 1.5% riêng (franchise tax, tối thiểu $800), phần tiết kiệm được phía liên bang phải trừ khối này trước rồi mới so sánh.
- Lựa chọn có ngày hiệu lực và giới hạn hủy bỏ (lựa chọn của Form 8832 thường có quy tắc khóa 60 tháng), thuộc loại quyết định phải tính toán trước rồi mới hành động.

Khi nào bắt đầu đáng tính bài toán này? Theo kinh nghiệm, khi lợi nhuận ròng Schedule C ổn định vượt khoảng $40,000–$60,000, thuế tự doanh trở thành gánh nặng thuế chính, phương án công ty S thường vào khoảng có thể bàn. Dưới mức này, chi phí tuân thủ thường ăn mất thuế tiết kiệm được.

**हिन्दी (अनुवाद, मूल-भाषी समीक्षा लंबित)**

डिफ़ॉल्ट एकमात्र विकल्प नहीं है। एकल-सदस्य LLC ये कर सकता है:

- Form 8832 जमा करके C कंपनी के रूप में कर देना चुनें: कंपनी स्वतंत्र रूप से Form 1120 दाखिल करती है, 21% संघीय कंपनी कर दर से कर देती है; लेकिन लाभ व्यक्तिगत को लाभांश देने पर एक और स्तर का लाभांश कर लगता है (दोहरा कर), और स्वामी स्वयं को वेतन दे तो payroll से होकर रोज़गार कर देना होगा।
- या Form 2553 जमा करके S कंपनी चुनें (केवल 2553 जमा करना ही कंपनी वर्गीकरण चुनाव माना जाता है, पहले Form 8832 देना आवश्यक नहीं): फिर भी पास-थ्रू है (Form 1120-S दाखिल, व्यक्ति को K-1), लेकिन स्वामी कर्मचारी के रूप में "उचित वेतन" (reasonable compensation) ले सकता है, वेतन भाग पर रोज़गार कर लगता है, शेष लाभ वितरण पर स्व-रोज़गार कर नहीं — बचत का तर्क इसी दरार में है। कीमत यह है कि payroll रिपोर्टिंग, बही और अनुपालन लागत बढ़ती है, और वेतन "उचित" होना चाहिए, स्पष्ट रूप से दबाया वेतन IRS पुनः वर्गीकृत करेगा।
- कैलिफ़ोर्निया ध्यान दें: S कंपनी पर कैलिफ़ोर्निया में अलग से 1.5% फ्रैंचाइज़ कर (franchise tax, न्यूनतम $800) है, संघीय पक्ष में बचाई राशि से पहले यह खंड घटाकर तुलना करें।
- चुनावों पर प्रभावी तिथि और रद्द करने की सीमाएँ हैं (Form 8832 के चुनाव में आमतौर पर 60 महीने की लॉक-इन अवधि का नियम है), यह पहले गणना करके फिर कदम उठाने वाला निर्णय है।

यह गणना कब से सार्थक होने लगती है? अनुभव से, जब Schedule C शुद्ध लाभ स्थिर रूप से लगभग $40,000–$60,000 से ऊपर हो और स्व-रोज़गार कर मुख्य कर भार बन जाए, तो S कंपनी विकल्प आमतौर पर चर्चा योग्य दायरे में आता है; इस स्तर से नीचे, अनुपालन लागत अक्सर बचे कर को खा जाती है।

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

*학습 노트이며 조언이 아닙니다. 이 저장소는 개인 학습 기록이며, 제시된 숫자는 교육을 위해 단순화된 예시로, 세무 조언이 아닙니다. 구체적인 신고는 IRS와 FTB의 현행 원문과 면허 CPA의 의견을 기준으로 하십시오.*

*Chỉ là ghi chú học tập, không phải lời khuyên. Kho lưu trữ này là hồ sơ học tập cá nhân, các con số nêu ra là ví dụ giảng dạy đơn giản hóa, không phải tư vấn thuế; khai thuế cụ thể hãy theo nguyên văn hiện hành của IRS, FTB và ý kiến của CPA có giấy phép.*

*केवल अध्ययन नोट, सलाह नहीं। यह भंडार एक व्यक्तिगत अध्ययन अभिलेख है, दी गई संख्याएँ शिक्षण हेतु सरलीकृत उदाहरण हैं और कर सलाह नहीं हैं; वास्तविक दाखिल के लिए IRS और FTB के वर्तमान मूल पाठ और लाइसेंसधारी CPA की राय पर निर्भर करें।*
