# Boechler, P.C. v. Commissioner, 596 U.S. 199 (2022) 案例分析

> 个人学习笔记，不构成税务建议。
> 核心依据：Boechler, P.C. v. Commissioner, 596 U.S. 199 (2022)（2022-04-21 宣判，Barrett 大法官执笔）；IRC § 6330(d)(1)；IRC § 7442；下级链 Boechler, P.C. v. Commissioner, 967 F.3d 760 (8th Cir. 2020)。

## 中文主文

### 一句话定位

向税务法院申请复审征收正当程序（CDP）裁定的 30 天期限，不是管辖性期限：国会没有把期限与法院的管辖权用清楚声明绑在一起，它就只是普通的程序期限，并且推定可以衡平中止（equitable tolling）——晚一天不再自动等于彻底没救，但能不能中止还要回到事实逐项证明。

### 硬事实

Boechler, P.C. 是北达科他州一家律师事务所，欠有雇佣税一类税款。IRS 拟以征提（levy）收税，先给了它 § 6330 的征收正当程序听证，IRS 上诉办公室于 2017-07-28 发出裁定通知、维持征提。按 § 6330(d)(1)，当事人可在裁定后 30 天内向税务法院申请复审。事务所的申请晚到了一天。税务法院以无管辖权驳回，第八巡回维持（967 F.3d 760 (8th Cir. 2020)），理由一脉相承：这个 30 天是管辖性的，法院对逾期申请根本没权力受理，更谈不上衡平中止。最高法院 2022-04-21 推翻，Barrett 执笔，发回税务法院就该所是否满足衡平中止的事实要件继续审理。案子的戏剧性全在一天：期限到底是法院权力的边界，还是可以被衡平推开的程序规则。

### 推理两步：先问管辖，再问中止

第一步，管辖性要国会说清楚。近年判例立了清楚声明规则：程序期限只有在国会清楚表明它与管辖权相连时，才按管辖性处理，因为管辖性标签后果极重——逾期不可补救、法院须依职权审查、任何阶段都能提出。看 § 6330(d)(1) 的文本，它只说当事人可在 30 天内申请复审、税务法院对该事项有管辖权；括号里那句管辖权讲的是法院能审哪类事（事由管辖），没有把 30 天写成取得管辖的条件。税务法院的一般管辖授予在别处的 § 7442，也没有把这条期限缝进去。所以 30 天只是申诉处理规则，不是权力边界。

第二步，非管辖性期限推定可衡平中止。衡平中止是美国法里长期存在的背景原则：当事人已勤勉行使权利、却因其控制之外的非常情事误期时，期限可以暂停计算。国会立法时被推定知道这个背景，除非文本或结构把推定推翻。§ 6330(d)(1) 没有禁止中止的文句，税务法院本就日常处理衡平问题，让 30 天这种极短期限完全拒绝中止、后果又格外严厉，反而与体系不合。两步都走完，结论才是：期限非管辖、且可衡平中止。但法院同时把话说死一半——它只裁定中止通道存在，Boechler 本人是否勤勉、有无非常情事，它不裁定，发回下级法院按事实判。后来税务法院在发回审理中认定该所不满足中止条件，正说明通道与过关是两回事（该事实结论其后另有上诉程序，细节以最新裁判为准）。

### 边界：千万别把本案读到 § 6213 的 90 天头上

这是本案最要紧的考试边界。欠税通知（notice of deficiency）后向税务法院申请重定的 90 天（境外 150 天）在 § 6213(a)，长期判例把它当管辖性期限。Boechler 的意见书提到了 § 6213，却明说不在本案裁定范围内——它裁的只有 § 6330(d)(1) 的 30 天。后续发展恰好证明这条边界真实存在：税务法院在 Hallmark Research Collective v. Commissioner, 159 T.C. 6 (2022) 中区分 Boechler、维持 § 6213(a) 的管辖性读法；第三巡回在 Culp v. Commissioner, 75 F.4th 196 (3d Cir. 2023) 中却按 Boechler 的逻辑判 § 6213(a) 非管辖且可中止，巡回分歧形成。答题时把两条期限混成一句「税务法院期限都可衡平中止」就是把本案读过头：正确句式是，§ 6330 的 30 天已由最高法院定性，§ 6213 的 90 天仍在下级法院拉锯、以所在巡回与最新裁判为准。

实务落点也要收紧：衡平中止从来不是逾期者的自动赦免。主张者要自证两件事——一直在勤勉追着权利跑、误期源于控制之外的非常情事；单纯算错日子、办公室流程失误、代理人疏忽，通常过不了勤勉这关（与 Boyle 案代理人误期不构成合理理由的精神互通）。征管流程上，CDP 听证是在征提前的最后常规救济站，30 天又比 90 天短得多，日历管理要按 30 天设双提醒，别拿 deficiency 的节奏套 CDP。

### 加州口径

加州州税救济有自己的一套期限：对 FTB 的拟评税通知提出抗辩、向州税务上诉办公室（OTA）上诉，各有州法与 OTA 规则定的期间与起算点，联邦的衡平中止法理不能直接搬进州程序。州层面逾期先查州法本身有没有迟延受理或合理理由的出口，再谈联邦判例的启发；本仓《收到加州 FTB 税信怎么办》一篇已把 FTB 抗辩与 OTA 上诉的期限细目列全，本篇不重复，只立一条界线：Boechler 是联邦税务法院 § 6330 的案子，引用到州税文书里只能作比较法理，不能当州期限的依据。

### 参考依据

- Boechler, P.C. v. Commissioner, 596 U.S. 199 (2022)
- IRC § 6330(d)(1)；IRC § 7442；IRC § 6213(a)
- Boechler, P.C. v. Commissioner, 967 F.3d 760 (8th Cir. 2020)
- Hallmark Research Collective v. Commissioner, 159 T.C. 6 (2022)
- Culp v. Commissioner, 75 F.4th 196 (3d Cir. 2023)

### 免责声明

个人学习笔记，不构成税务建议。

## English

### Holding in One Line

The 30-day deadline to petition the Tax Court for review of a collection due process (CDP) determination is not jurisdictional: because Congress did not clearly tie the deadline to the court's jurisdiction, it is an ordinary claim-processing rule, and it is presumptively subject to equitable tolling. Filing one day late is no longer automatically fatal — but the taxpayer still has to prove entitlement to tolling on the facts.

### The Facts

Boechler, P.C., a North Dakota law firm with an outstanding employment-tax liability, received a § 6330 collection due process hearing before the IRS levied. On July 28, 2017, the IRS Office of Appeals issued a notice of determination sustaining the levy. Under § 6330(d)(1), the firm had 30 days to petition the Tax Court for review. It filed one day late. The Tax Court dismissed for lack of jurisdiction, and the Eighth Circuit affirmed (967 F.3d 760 (8th Cir. 2020)): on their view the 30 days was jurisdictional, so the court had no power over a late petition and tolling never came into play. On April 21, 2022, the Supreme Court reversed in an opinion by Justice Barrett and remanded for the Tax Court to decide whether the firm actually qualifies for equitable tolling. The entire case turns on one day — and on whether a deadline marks the boundary of a court's power or is merely a procedural rule equity can move.

### The Reasoning, in Two Steps

Step one: jurisdictional treatment requires a clear statement from Congress. Modern cases treat a filing deadline as jurisdictional only if Congress clearly states that it is, because the jurisdictional label carries harsh consequences — no cure for lateness, a duty for courts to police it sua sponte, and vulnerability at any stage. Section 6330(d)(1) says the taxpayer may petition within 30 days and that the Tax Court "shall have jurisdiction with respect to such matter." That parenthetical grants subject-matter jurisdiction over the determination; it does not make the 30 days a condition of jurisdiction. The Tax Court's general jurisdictional grant sits elsewhere, in § 7442, and it does not stitch this deadline in. The 30 days is therefore a claim-processing rule, not a power boundary.

Step two: a nonjurisdictional deadline is presumptively subject to equitable tolling. Tolling is a traditional background principle — a deadline may be paused when a litigant pursued rights diligently yet extraordinary circumstances beyond its control caused the delay — and Congress legislates against that background unless the text or structure rebuts it. Nothing in § 6330(d)(1) forbids tolling, the Tax Court routinely applies equitable doctrines, and refusing tolling for so short a period with so severe a consequence would sit poorly with the scheme. But the Court decided only that the tolling door exists. Whether Boechler itself was diligent and faced extraordinary circumstances was for the Tax Court on remand — and on remand the Tax Court in fact found tolling unwarranted, which proves the point that an open door is not a free pass (that factual ruling later generated further appellate proceedings; check the latest decision for details).

### The Boundary: Do Not Read This Case onto § 6213's 90 Days

This is the boundary exams care about. The 90-day period (150 days for notices addressed abroad) to petition for redetermination of a deficiency under § 6213(a) was long treated as jurisdictional. Boechler mentioned § 6213 but expressly decided nothing about it; the holding covers § 6330(d)(1)'s 30 days only. Later cases prove the boundary is real: the Tax Court in Hallmark Research Collective v. Commissioner, 159 T.C. 6 (2022), distinguished Boechler and kept § 6213(a) jurisdictional, while the Third Circuit in Culp v. Commissioner, 75 F.4th 196 (3d Cir. 2023), followed Boechler's logic the other way, producing a circuit split. Writing "all Tax Court deadlines are now tollable" overreads the case. The precise sentence is: the § 6330 30-day period is settled by the Supreme Court; the § 6213 90-day period is still being fought over below, so check your circuit and the latest cases.

Practice consequences are equally narrow. Equitable tolling is never an automatic pardon: the claimant must show diligent pursuit of rights plus extraordinary circumstances beyond its control. A miscalculated date, an office docketing failure, or an agent's slip usually fails the diligence prong — the same spirit as Boyle, where an agent's missed deadline was not reasonable cause. And because a CDP hearing is the last regular stop before levy, and 30 days is far shorter than 90, calendar discipline for CDP cases needs its own double reminders, not the deficiency workflow's rhythm.

### California Note

California runs its own clocks: protests against FTB notices of proposed assessment and appeals to the Office of Tax Appeals each have periods and starting points set by state law and OTA rules, and federal equitable-tolling doctrine does not import itself into state procedure. For a late state filing, first look for a late-relief or reasonable-cause outlet in state law itself. This study repo's guide to FTB notices already lists the protest and OTA deadlines in full; the point here is jurisdictional hygiene — Boechler is a federal § 6330 Tax Court case and can be cited in state filings only as comparative reasoning, never as the authority for a state deadline.

Disclaimer: personal study notes, not tax advice.

## Español

### Tesis en una línea

El plazo de 30 días para pedir al Tribunal Fiscal la revisión de una determinación de debido proceso recaudatorio (CDP) no es jurisdiccional: como el Congreso no vinculó con claridad el plazo a la jurisdicción del tribunal, es una regla procesal ordinaria y se presume susceptible de suspensión equitativa (equitable tolling). Llegar un día tarde ya no es automáticamente fatal, pero el contribuyente debe probar en los hechos que merece la suspensión.

### Hechos

Boechler, P.C., un despacho de Dakota del Norte con un pasivo de impuestos sobre el empleo, obtuvo una audiencia CDP conforme a la § 6330 antes del embargo. El 28 de julio de 2017 la Oficina de Apelaciones del IRS emitió la determinación que confirmaba el embargo. Según la § 6330(d)(1), el despacho tenía 30 días para acudir al Tribunal Fiscal, y presentó su petición con un día de retraso. El Tribunal Fiscal desestimó por falta de jurisdicción y el Octavo Circuito confirmó (967 F.3d 760 (8th Cir. 2020)): para ellos el plazo era jurisdiccional y no cabía suspensión alguna. El 21 de abril de 2022 el Tribunal Supremo revocó, con opinión de la jueza Barrett, y devolvió el caso para que se decidiera si el despacho realmente reunía los requisitos de la suspensión equitativa. Todo el caso gira sobre un día y sobre si un plazo delimita el poder del tribunal o es solo una regla procesal que la equidad puede mover.

### Razonamiento en dos pasos

Primero, lo jurisdiccional exige una declaración clara del Congreso. Un plazo solo es jurisdiccional si el Congreso lo dice con claridad, porque esa etiqueta trae consecuencias duras: sin cura para el retraso y con control de oficio en cualquier etapa. La § 6330(d)(1) dice que el contribuyente puede pedir revisión en 30 días y que el Tribunal Fiscal «tendrá jurisdicción respecto de ese asunto»; ese inciso concede jurisdicción sobre la materia, no convierte los 30 días en condición de jurisdicción. La concesión general de jurisdicción está en otra parte, la § 7442, y no cose este plazo a ella. Los 30 días son, pues, una regla de tramitación.

Segundo, un plazo no jurisdiccional se presume suspendible en equidad. La suspensión equitativa es un principio de fondo tradicional: el plazo puede pausarse cuando el litigante persiguió sus derechos con diligencia y aun así circunstancias extraordinarias fuera de su control causaron el retraso; el Congreso legisla sobre ese fondo salvo que el texto lo desplace. Nada en la § 6330(d)(1) prohíbe la suspensión. Pero el Tribunal solo decidió que la puerta existe: si Boechler fue diligente es cuestión de hechos para la instancia inferior, que de hecho denegó la suspensión tras la devolución. Puerta abierta no es pase libre.

### El límite: no trasladar el caso a los 90 días de la § 6213

El plazo de 90 días (150 si la notificación se dirige al extranjero) para pedir la redeterminación de una deficiencia según la § 6213(a) fue tratado durante mucho tiempo como jurisdiccional. Boechler mencionó la § 6213 pero no decidió nada sobre ella; la sentencia cubre solo los 30 días de la § 6330(d)(1). Los casos posteriores lo confirman: el Tribunal Fiscal, en Hallmark Research Collective, 159 T.C. 6 (2022), distinguió Boechler y mantuvo la lectura jurisdiccional de la § 6213(a), mientras el Tercer Circuito, en Culp, 75 F.4th 196 (3d Cir. 2023), siguió la lógica contraria y creó una división entre circuitos. Escribir que «todos los plazos del Tribunal Fiscal ya son suspendibles» es leer el caso de más. En la práctica, además, quien pide la suspensión debe probar diligencia y circunstancias extraordinarias; un error de calendario o el fallo de un agente normalmente no superan la diligencia, en el mismo espíritu de Boyle. Y como la audiencia CDP es la última parada regular antes del embargo, sus 30 días exigen recordatorios propios.

### Nota de California

California tiene sus propios relojes: la protesta contra las notificaciones del FTB y la apelación ante la Oficina de Apelaciones Fiscales (OTA) siguen periodos fijados por la ley estatal y las reglas de la OTA, y la doctrina federal de suspensión equitativa no se importa sola al procedimiento estatal. Boechler es un caso federal de la § 6330: en escritos estatales solo sirve como razonamiento comparado, nunca como fundamento del plazo estatal.

Aviso: notas personales de estudio, no constituyen asesoría fiscal.

## 한국어 (초역 · 初译待校)

### 한 줄 요지

징수 적법절차(CDP) 결정의 재심을 조세법원에 청구하는 30일 기한은 관할 기한이 아닙니다. 의회가 기한과 법원의 관할을 명확한 진술로 묶지 않았으므로 이는 통상의 절차 기한이며 형평상 중단(equitable tolling)이 추정됩니다. 하루 늦었다고 자동으로 끝나는 것은 아니지만, 중단의 자격은 사실관계로 입증해야 합니다.

### 사실관계

노스다코타의 법률사무소 Boechler, P.C.는 고용세 체납이 있었고, IRS가 징수(levy)에 나서기 전 § 6330의 CDP 청문을 받았습니다. IRS 항소국은 2017-07-28 징수를 유지하는 결정 통지를 보냈습니다. § 6330(d)(1)에 따르면 30일 안에 조세법원에 재심을 청구해야 하는데, 사무소는 하루 늦게 제출했습니다. 조세법원은 관할 없음을 이유로 각하했고 제8순회도 이를 유지했습니다(967 F.3d 760 (8th Cir. 2020)). 연방대법원은 2022-04-21 Barrett 대법관의 의견으로 이를 파기하고, 사무소가 실제로 형평상 중단의 요건을 갖추었는지를 판단하도록 환송했습니다. 다툼은 단 하루, 그리고 기한이 법원 권한의 경계인지 형평이 움직일 수 있는 절차 규칙인지에 있습니다.

### 두 단계의 추론

첫째, 관할로 취급하려면 의회의 명확한 진술이 필요합니다. § 6330(d)(1)은 30일 내 청구와 함께 조세법원이 그 사항에 관할을 가진다고 쓰지만, 이 괄호 문구는 심판 대상에 대한 관할을 주는 것이지 30일을 관할의 조건으로 만들지 않습니다. 조세법원의 일반 관할 근거인 § 7442도 이 기한을 연결하지 않습니다. 따라서 30일은 청구 처리 규칙일 뿐입니다.

둘째, 비관할 기한은 형평상 중단이 추정됩니다. 권리를 성실히 추구했음에도 통제 밖의 비상한 사정으로 늦어진 경우 기한 계산을 멈출 수 있다는 것은 전통적인 배경 원칙이며, § 6330(d)(1)의 문언은 이를 배제하지 않습니다. 다만 대법원은 중단의 통로가 존재한다는 점까지만 판단했고, 성실성과 비상한 사정이 있는지는 환송 후 조세법원이 사실로 가렸으며 실제로 중단이 부정되었습니다. 문이 열렸다고 통과가 보장되는 것은 아닙니다.

### 경계: § 6213의 90일로 읽어 넓히지 말 것

결정세 통지 후 재결정을 구하는 90일(해외 주소는 150일) 기한인 § 6213(a)은 오랫동안 관할 기한으로 취급되었습니다. Boechler는 § 6213을 언급했을 뿐 그것에 대해서는 아무것도 판단하지 않았습니다. 이후 조세법원은 Hallmark Research Collective, 159 T.C. 6 (2022)에서 Boechler와 구별해 § 6213(a)의 관할성을 유지했고, 제3순회는 Culp, 75 F.4th 196 (3d Cir. 2023)에서 반대 방향으로 판단해 순회 간 견해가 갈렸습니다. 실무에서 중단 신청자는 성실한 권리 추구와 통제 밖의 비상한 사정을 스스로 입증해야 하며, 날짜 계산 착오나 대리인의 실수는 대개 성실성 문턱을 넘지 못합니다(Boyle 판례의 정신과 통합니다). CDP는 징수 전 마지막 통상 구제 단계이고 30일은 90일보다 훨씬 짧으므로 별도의 이중 알림이 필요합니다.

### 캘리포니아 주석

캘리포니아는 자체 기한 체계를 가집니다. FTB 통지에 대한 이의와 주 세무항소국(OTA) 항소는 주법과 OTA 규칙이 정한 기간을 따르며, 연방의 형평상 중단 법리가 주 절차에 그대로 들어오지 않습니다. Boechler는 연방 § 6330 사건이므로 주 서면에서는 비교 법리로만 인용할 수 있습니다. (초역·待校)

면책: 개인 학습 노트이며 세무 조언이 아닙니다.

## Tiếng Việt (bản dịch sơ bộ · 初译待校)

### Kết luận một dòng

Thời hạn 30 ngày để nộp đơn lên Tòa án Thuế xin xét lại quyết định trong thủ tục thu thuế hợp lệ (CDP) không phải là thời hạn thuộc thẩm quyền: vì Quốc hội không gắn rõ thời hạn với thẩm quyền của tòa, đây chỉ là một quy tắc tố tụng thông thường và được suy đoán là có thể tạm dừng theo công bằng (equitable tolling). Nộp muộn một ngày không còn tự động mất hết quyền, nhưng người nộp thuế vẫn phải chứng minh mình đủ điều kiện tạm dừng trên thực tế.

### Sự kiện

Boechler, P.C., một hãng luật ở North Dakota còn nợ thuế việc làm, đã được hưởng phiên điều trần CDP theo § 6330 trước khi IRS cưỡng thu (levy). Ngày 28/7/2017, Văn phòng Khiếu nại của IRS ra thông báo quyết định giữ nguyên việc cưỡng thu. Theo § 6330(d)(1), hãng có 30 ngày để nộp đơn lên Tòa án Thuế, và hãng đã nộp muộn một ngày. Tòa án Thuế bác đơn vì thiếu thẩm quyền, Tòa Phúc thẩm Khu vực 8 giữ nguyên (967 F.3d 760 (8th Cir. 2020)): theo các tòa này, 30 ngày là thời hạn thuộc thẩm quyền nên không thể tạm dừng. Ngày 21/4/2022, Tòa án Tối cao đảo ngược với ý kiến do thẩm phán Barrett chấp bút và gửi lại để Tòa án Thuế xét xem hãng có thật sự đủ điều kiện tạm dừng theo công bằng hay không. Toàn bộ vụ việc xoay quanh một ngày và câu hỏi: thời hạn là ranh giới quyền lực của tòa hay chỉ là quy tắc thủ tục mà công bằng có thể dịch chuyển.

### Lập luận hai bước

Bước một: muốn coi là thuộc thẩm quyền thì Quốc hội phải nói rõ. § 6330(d)(1) nói người nộp thuế có thể nộp đơn trong 30 ngày và Tòa án Thuế «có thẩm quyền đối với vấn đề đó»; câu này trao thẩm quyền theo subject matter đối với quyết định, chứ không biến 30 ngày thành điều kiện của thẩm quyền. Điều khoản trao thẩm quyền chung cho Tòa án Thuế nằm ở § 7442 và cũng không khâu thời hạn này vào. Vậy 30 ngày chỉ là quy tắc xử lý hồ sơ.

Bước hai: thời hạn không thuộc thẩm quyền được suy đoán có thể tạm dừng theo công bằng. Tạm dừng theo công bằng là nguyên tắc nền truyền thống: thời hạn có thể dừng tính khi người khởi kiện đã siêng năng theo đuổi quyền của mình nhưng hoàn cảnh đặc biệt ngoài tầm kiểm soát khiến họ chậm trễ; Quốc hội lập pháp trên nền đó trừ khi văn bản gạt bỏ. § 6330(d)(1) không cấm việc tạm dừng. Tuy nhiên Tòa án Tối cao chỉ quyết rằng cánh cửa tạm dừng tồn tại; việc Boechler có siêng năng và có hoàn cảnh đặc biệt hay không thuộc về tòa cấp dưới xét theo sự kiện, và sau khi gửi lại, Tòa án Thuế đã kết luận không đủ điều kiện tạm dừng. Cửa mở không có nghĩa là được qua.

### Ranh giới: đừng đọc vụ này sang 90 ngày của § 6213

Thời hạn 90 ngày (150 ngày nếu thông báo gửi ra nước ngoài) để xin xác định lại số thuế thiếu theo § 6213(a) từ lâu được coi là thuộc thẩm quyền. Boechler có nhắc § 6213 nhưng rõ ràng không quyết định gì về nó; phán quyết chỉ bao phủ 30 ngày của § 6330(d)(1). Các vụ sau cho thấy ranh giới này là thật: Tòa án Thuế trong Hallmark Research Collective, 159 T.C. 6 (2022) phân biệt Boechler và giữ cách đọc thuộc thẩm quyền cho § 6213(a), còn Tòa Khu vực 3 trong Culp, 75 F.4th 196 (3d Cir. 2023) đi theo logic của Boechler sang hướng ngược lại, tạo ra sự chia rẽ giữa các khu vực. Trong thực hành, người xin tạm dừng phải tự chứng minh sự siêng năng và hoàn cảnh đặc biệt ngoài tầm kiểm soát; tính sai ngày tháng hay lỗi của người đại diện thường không vượt qua được yêu cầu siêng năng, cùng tinh thần với vụ Boyle. Vì điều trần CDP là chặng cứu trợ thường lệ cuối cùng trước cưỡng thu và 30 ngày ngắn hơn 90 ngày rất nhiều, cần đặt nhắc hẹn riêng cho các vụ CDP.

### Ghi chú California

California có hệ thống thời hạn riêng: phản đối thông báo của FTB và kháng cáo lên Văn phòng Kháng cáo Thuế (OTA) đều theo thời hạn do luật bang và quy tắc OTA định, và học thuyết tạm dừng theo công bằng của liên bang không tự động nhập vào thủ tục bang. Boechler là vụ án liên bang về § 6330, trong hồ sơ cấp bang chỉ có thể trích dẫn như lập luận so sánh, không phải căn cứ cho thời hạn của bang. (bản dịch sơ bộ·待校)

Tuyên bố miễn trừ: ghi chú học tập cá nhân, không phải tư vấn thuế.

## हिन्दी (प्रारंभिक अनुवाद · 初译待校)

### एक पंक्ति में निर्णय

संग्रह उचित प्रक्रिया (CDP) निर्धारण की कर न्यायालय में समीक्षा माँगने की 30-दिन की समय-सीमा क्षेत्राधिकार-विषयक नहीं है: कांग्रेस ने समय-सीमा को न्यायालय के क्षेत्राधिकार से स्पष्ट रूप से नहीं जोड़ा, इसलिए यह एक साधारण प्रक्रिया नियम है और इसके लिए साम्यिक स्थगन (equitable tolling) की धारणा लागू होती है। एक दिन की देरी अब अपने आप घातक नहीं है, किंतु करदाता को तथ्यों पर स्थगन की पात्रता सिद्ध करनी होगी।

### तथ्य

Boechler, P.C., नॉर्थ डकोटा की एक विधि फ़र्म जिस पर रोज़गार कर बकाया था, ने IRS द्वारा लेवी से पहले § 6330 के अंतर्गत CDP सुनवाई पाई। 28 जुलाई 2017 को IRS अपील कार्यालय ने लेवी को बनाए रखने का निर्धारण जारी किया। § 6330(d)(1) के अनुसार फ़र्म के पास कर न्यायालय जाने के लिए 30 दिन थे, परंतु उसने एक दिन देर से याचिका दाखिल की। कर न्यायालय ने क्षेत्राधिकार के अभाव में ख़ारिज किया और आठवें सर्किट ने पुष्टि की (967 F.3d 760 (8th Cir. 2020))। 21 अप्रैल 2022 को सर्वोच्च न्यायालय ने न्यायमूर्ति Barrett के मत से निर्णय पलटा और मामला इस प्रश्न पर वापस भेजा कि फ़र्म वास्तव में साम्यिक स्थगन की पात्र है या नहीं। पूरा मामला एक दिन पर टिका है — और इस प्रश्न पर कि समय-सीमा न्यायालय की शक्ति की सीमा है या केवल प्रक्रिया नियम जिसे साम्य बदल सकती है।

### दो चरणों का तर्क

पहला चरण: क्षेत्राधिकार माना जाने के लिए कांग्रेस का स्पष्ट कथन चाहिए। § 6330(d)(1) कहता है कि करदाता 30 दिनों में याचिका दे सकता है और कर न्यायालय को उस विषय पर क्षेत्राधिकार होगा; यह वाक्यांश निर्धारण पर विषय-वस्तु क्षेत्राधिकार देता है, 30 दिनों को क्षेत्राधिकार की शर्त नहीं बनाता। कर न्यायालय का सामान्य क्षेत्राधिकार § 7442 में है और वह इस समय-सीमा को नहीं जोड़ता। अतः 30 दिन केवल दावा-प्रक्रिया नियम है।

दूसरा चरण: गैर-क्षेत्राधिकार समय-सीमा के लिए साम्यिक स्थगन की धारणा होती है — जब वादी ने अपने अधिकारों का परिश्रम से पीछा किया हो फिर भी उसके नियंत्रण से बाहर की असाधारण परिस्थितियों से देरी हुई हो, तो समय-सीमा रुक सकती है; कांग्रेस इसी पृष्ठभूमि के विरुद्ध कानून बनाती है जब तक पाठ उसे काट न दे। § 6330(d)(1) स्थगन का निषेध नहीं करता। किंतु न्यायालय ने केवल इतना तय किया कि स्थगन का द्वार मौजूद है; Boechler स्वयं परिश्रमी था या नहीं, यह तथ्यों पर निचली अदालत को तय करना था, और वापसी पर कर न्यायालय ने स्थगन को अनुचित पाया। द्वार खुला होना पास मिलना नहीं है।

### सीमा: इस मामले को § 6213 के 90 दिनों पर न पढ़ें

कमी निर्धारण की पुनः गणना के लिए § 6213(a) की 90-दिन (विदेश भेजे गए नोटिस पर 150-दिन) की अवधि लंबे समय से क्षेत्राधिकार-विषयक मानी गई थी। Boechler ने § 6213 का उल्लेख किया परंतु उस पर कुछ तय नहीं किया; निर्णय केवल § 6330(d)(1) के 30 दिनों तक सीमित है। बाद के मामले इस सीमा को साबित करते हैं: Hallmark Research Collective, 159 T.C. 6 (2022) में कर न्यायालय ने Boechler से अंतर करके § 6213(a) की क्षेत्राधिकार व्याख्या बनाए रखी, जबकि Culp, 75 F.4th 196 (3d Cir. 2023) में तीसरा सर्किट विपरीत दिशा गया और सर्किटों में विभाजन बन गया। व्यवहार में स्थगन माँगने वाले को परिश्रम और नियंत्रण-बाहर असाधारण परिस्थितियाँ स्वयं सिद्ध करनी होती हैं; तारीख़ की गणना-भूल या एजेंट की चूक आम तौर पर परिश्रम की कसौटी पार नहीं करती, Boyle वाले भाव के अनुरूप। CDP सुनवाई लेवी से पहले की अंतिम नियमित उपाय-सीढ़ी है और 30 दिन 90 से कहीं छोटे हैं, इसलिए इन मामलों के लिए अलग दोहरे अनुस्मारक चाहिए।

### कैलिफ़ोर्निया टिप्पणी

कैलिफ़ोर्निया की अपनी समय-सीमाएँ हैं: FTB नोटिसों के विरुद्ध विरोध और राज्य कर अपील कार्यालय (OTA) में अपील राज्य कानून और OTA नियमों की अवधि से चलती हैं, और संघीय साम्यिक स्थगन का सिद्धांत राज्य प्रक्रिया में अपने आप आयात नहीं होता। Boechler संघीय § 6330 का मामला है; राज्य दाखिलों में यह केवल तुलनात्मक तर्क के रूप में उद्धृत हो सकता है, राज्य समय-सीमा के प्राधिकार के रूप में नहीं। (प्रारंभिक अनुवाद·待校)

अस्वीकरण: व्यक्तिगत अध्ययन नोट्स, कर सलाह नहीं।
