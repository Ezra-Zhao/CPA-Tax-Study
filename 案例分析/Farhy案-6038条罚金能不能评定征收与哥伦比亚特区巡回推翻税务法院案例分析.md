# Farhy 案：罚金写在法里，不等于税务局能自己评定征收

> 个人学习笔记，不构成税务建议。仓内指针分工：经 ls/grep 实查，「Farhy」文件名与正文全仓零命中、无本体专篇。仓内《Bittner 案》管 FBAR 罚款按报告还是按账户计，《Boechler 案》《Brockamp 案》管期限与管辖，本篇管另一件事——一笔罚金在法典里写明了金额，税务局能不能不经法院起诉、自己评定（assess）再用留置与征收去收。罚则在第 6038 条，评定权在第 6201 条，两条不在同一格，这正是全案的争点。

## 中文主文

### 一、引证与程序链，先把两级裁判钉死

- 税务法院：Farhy v. Commissioner, 160 T.C. No. 6 (2023)，2023 年 4 月 3 日判决，Marvel 法官执笔，按 Rule 122 以书面事实审理。税务局长败诉：法院认定其无权评定第 6038(b) 条罚金，也不得用拟议征收（levy）去收这笔已经评定的罚金。
- 上诉法院：Farhy v. Commissioner, 100 F.4th 223 (D.C. Cir. 2024)，2024 年 5 月 3 日判决，推翻税务法院：哥伦比亚特区巡回认定第 6038(b)(1) 条的定额罚金是可评定的（assessable）。同院 2024 年 6 月 13 日拒绝再审（rehearing）。
- 后续分裂：税务法院在 Mukhi v. Commissioner, 162 T.C. No. 8 (2024) 中沿用 Farhy 税务法院口径，经再议（on reconsideration）又以 163 T.C. No. 8 (2024) 重申原判，理由是该案可上诉至第八巡回、不受哥伦比亚特区巡回约束——这正是 Golsen 规则（Golsen v. Commissioner, 54 T.C. 742 (1970)）：税务法院在可上诉巡回已有相反判例时跟该巡回走，其余地区仍可守自家口径。同一笔罚金能不能被评定，眼下要看案件将来上诉到哪个巡回。

### 二、案情：八年没交 Form 5471，故意且无合理理由

Alon Farhy 在 2003 至 2010 各纳税年度持有在伯利兹注册的外国公司 100% 股权（税务法院判决书记载其间涉及两家伯利兹公司），按第 6038(a) 条本应逐年提交 Form 5471（美国人对某些外国公司的信息申报表），但一年也没交。税务法院认定未申报是故意（willful）且不构成合理理由（reasonable cause）——注意，纳税人输的不是罚不罚，而是该由谁来收。程序入口是征收正当程序：税务局拟以征收收罚金，纳税人依第 6330 条请求听证后进税务法院。评定时间与构成见下：2016 年 2 月税务局先寄出未申报通知；2018 年 11 月 5 日评定第 6038(b)(1) 条初始罚金，2018 年 11 月 12 日评定第 6038(b)(2) 条延续罚金。

### 三、罚金结构：第 6038(b) 条的两段式

第 6038(b)(1) 条：未按第 6038(a) 条及时提供所要求信息者，就每一存在未申报的年度会计期间罚 10,000 美元。第 6038(b)(2) 条：税务局寄出通知后，未申报状态在 90 天宽限期过后仍继续的，每满 30 天（不足 30 天按一段计）再罚 10,000 美元，就该年度期间累计增加额以 50,000 美元封顶。两段叠起来，一个年度期间的罚金上限就是 10,000 加 50,000 等于 60,000 美元。法条通篇没有出现「评定」（assess）一词，也没有写「按税款方式评定与征收」这类在其他罚则里常见的转介句——这处沉默，就是税务法院整篇判决的支点。

### 四、两级法院为什么给出相反答案

税务法院的读法是文本列举式：第 6201(a) 条授权财政部长评定法典课征的全部税款、利息与「可评定罚金」（assessable penalties）；国会在法典众多罚则里一再明文授权评定，唯独对第 6038(b) 条没有，于是这笔罚金不属于可评定罚金。没有评定权，征收工具也就无从谈起；政府要拿这笔钱，只能按 28 U.S.C. 第 2461(a) 条的默认路径，去联邦地区法院提起民事诉讼追收。

哥伦比亚特区巡回的读法是结构与沿革式：不能仅凭条文没写「评定」二字就推出无权评定；结合第 6038 条的整体结构与 1982 年修法把定额罚金放进这一条的沿革，定额、由具体未申报行为触发、不与欠税数额挂钩的罚金，在设计上本来就是可评定罚金。于是税务局的长期做法——直接评定、再走行政征收——在其管辖范围内恢复。

实务落点要分清三层：一，哥伦比亚特区巡回范围（含住所地在该院辖区的案件）按上诉口径，罚金可评定；二，可上诉至其他巡回的案件，税务法院按 Golsen 与 Mukhi 再议口径仍守税务法院原判，罚金不可行政评定；三，纳税人一侧的救济路径随之不同——不可评定口径下政府须起诉，纳税人等着应诉即可；可评定口径下罚金经评定进入征收程序，纳税人的争点要走征收听证或缴付后退税诉讼。引申问题是射程：第 6038A 条（Form 5472）、第 6038B 条（Form 926）、第 6038D 条（Form 8938）等同样没有明文评定句的国际信息申报罚则，在各巡回的命运都悬在这条分界线上，考试与实务都不能把 Farhy 读成只管一张 Form 5471 的小案。

### 五、示意算例：按判决书记载的评定口径把八年加总

下列合计按税务法院判决书记载的评定方式复算：初始罚金每涉案年度 10,000 美元，延续罚金每涉案年度合计封顶 50,000 美元，涉案年度为 2003 至 2010 年共 8 个年度。数字经本地整数与 Decimal 两路复算勾稽一致。

- 初始罚金：10,000 乘以 8 等于 80,000 美元。
- 延续罚金：50,000 乘以 8 等于 400,000 美元；单看一个年度，延续罚金按每 30 天 10,000 美元累加，五段即 5 乘以 10,000 等于 50,000 美元触顶，与法条封顶自洽。
- 合计：80,000 加 400,000 等于 480,000 美元，也等于每年度上限 60,000 乘以 8。争点从来不是这 480,000 美元算得对不对，而是它能不能以「评定加征收」的方式收上来——税务法院说不能，哥伦比亚特区巡回说能。

### 六、加州口径

加州没有与第 6038(b) 条对应的州版外国公司信息罚金评定机制，联邦这两级裁判的结论不直接移入加州税表；加州居民持有外国实体的申报义务以联邦 Form 5471 一线为主，州侧另有 FTB 对联邦信息与州申报衔接的当期口径。凡在加州处理国际信息申报罚金，先分清争议在评定权还是在罚金本身，再定上诉巡回与救济路径（证据等级 B；案名、引证、日期与罚金额度经判决与法典原文回核，证据等级 A）。

> 来源：Farhy v. Commissioner, 160 T.C. No. 6 (Apr. 3, 2023)；Farhy v. Commissioner, 100 F.4th 223 (D.C. Cir. May 3, 2024)；Mukhi v. Commissioner, 162 T.C. No. 8 (2024) 及再议 163 T.C. No. 8 (2024)；Golsen v. Commissioner, 54 T.C. 742 (1970)；26 U.S.C. 第 6038、6201、6330 条；28 U.S.C. 第 2461(a) 条。
>
> 个人学习笔记，不构成税务建议。

## English

Farhy v. Commissioner, 160 T.C. No. 6 (Apr. 3, 2023) (Marvel, J.), held that the IRS lacks statutory authority to assess the penalties imposed by section 6038(b) and may not collect them through the proposed levy that brought the case into court under section 6330. The D.C. Circuit reversed: Farhy v. Commissioner, 100 F.4th 223 (D.C. Cir. May 3, 2024), held the fixed-dollar penalty under section 6038(b)(1) assessable, and rehearing was denied on June 13, 2024. The Tax Court then reaffirmed its own reading on reconsideration in Mukhi v. Commissioner, 163 T.C. No. 8 (2024) (the original Mukhi opinion is 162 T.C. No. 8), because that case was appealable to the Eighth Circuit — under Golsen v. Commissioner, 54 T.C. 742 (1970), the Tax Court follows a circuit that has decided the issue for cases appealable there, and keeps its own rule elsewhere. Whether this penalty can be assessed therefore now depends on the circuit of appeal.

The facts were not close on liability: for his 2003 through 2010 tax years Alon Farhy owned 100% of Belize corporations and filed no Form 5471 as section 6038(a) required; the Tax Court found the failure willful and without reasonable cause. The IRS mailed a failure-to-file notice in February 2016, assessed the section 6038(b)(1) initial penalties on November 5, 2018, and the section 6038(b)(2) continuation penalties on November 12, 2018. Section 6038(b)(1) imposes $10,000 for each annual accounting period of failure; section 6038(b)(2) adds $10,000 for each 30-day period (or fraction) the failure continues after the 90-day notice period, capped at $50,000 per period — a per-year ceiling of $10,000 + $50,000 = $60,000. The provision never uses the word "assess" and contains no "assessed and collected as a tax" cross-reference.

The Tax Court reasoned from enumeration: section 6201(a) authorizes assessment of taxes and "assessable penalties," Congress expressly authorized assessment in myriad penalty provisions but not in section 6038(b), so these penalties are not assessable and the government must sue for them in district court under the default rule of 28 U.S.C. 2461(a). The D.C. Circuit reasoned from structure and history, including the 1982 amendment that placed the fixed-dollar penalty in this section: a fixed amount triggered by a defined failure and unconnected to any tax deficiency is by design an assessable penalty, and the absence of the word "assess" is not conclusive. The same textual gap runs through sections 6038A (Form 5472), 6038B (Form 926) and 6038D (Form 8938), which is why the case matters well beyond Form 5471.

Recomputation on the assessment pattern stated in the Tax Court opinion (initial $10,000 and continuation penalties totaling the $50,000 cap for each of the eight years at issue, 2003–2010; integer and Decimal passes agree): initial penalties $10,000 × 8 = $80,000; continuation penalties $50,000 × 8 = $400,000, with the cap itself checking out as 5 × $10,000 = $50,000 per year; total $80,000 + $400,000 = $480,000, equivalently $60,000 × 8. The fight was never over the arithmetic — it was over whether the sum could be collected by assessment and levy at all. California has no state counterpart to the section 6038(b) assessment mechanism, and the federal holding does not carry onto state returns (evidence grade B; case citations, dates and penalty amounts verified against the opinions and the Code, grade A).

> Personal study notes only; not tax advice. Sources: 160 T.C. No. 6 (2023); 100 F.4th 223 (D.C. Cir. 2024); Mukhi, 162 T.C. No. 8 and 163 T.C. No. 8 (2024); Golsen, 54 T.C. 742 (1970); 26 U.S.C. 6038, 6201, 6330; 28 U.S.C. 2461(a).

## Español (初译待校)

Farhy v. Commissioner, 160 T.C. n.º 6 (3 de abril de 2023), sostuvo que el IRS carece de autoridad legal para liquidar (assess) las multas del artículo 6038(b) y que no puede cobrarlas mediante el embargo propuesto que llevó el caso ante el Tribunal Fiscal por la vía del artículo 6330. El Circuito del Distrito de Columbia revocó: Farhy v. Commissioner, 100 F.4th 223 (D.C. Cir., 3 de mayo de 2024), declaró liquidable la multa fija del artículo 6038(b)(1), y la revisión fue denegada el 13 de junio de 2024. El Tribunal Fiscal reafirmó luego su criterio en la reconsideración de Mukhi v. Commissioner, 163 T.C. n.º 8 (2024) (la opinión original es 162 T.C. n.º 8), porque ese caso era apelable ante el Octavo Circuito: según Golsen v. Commissioner, 54 T.C. 742 (1970), el Tribunal Fiscal sigue al circuito que ya decidió en los casos apelables ante él y mantiene su regla en los demás. Hoy, si esta multa puede liquidarse depende del circuito de apelación.

Los hechos no eran dudosos en cuanto a la infracción: entre 2003 y 2010 Alon Farhy poseyó el 100% de sociedades de Belice y no presentó ningún Formulario 5471, como exige el artículo 6038(a); el Tribunal Fiscal declaró la omisión dolosa y sin causa razonable. El IRS notificó la omisión en febrero de 2016, liquidó las multas iniciales del 6038(b)(1) el 5 de noviembre de 2018 y las de continuación del 6038(b)(2) el 12 de noviembre de 2018. El 6038(b)(1) impone 10.000 dólares por cada período contable anual de omisión; el 6038(b)(2) añade 10.000 por cada 30 días (o fracción) de continuación tras el plazo de gracia de 90 días, con tope de 50.000 por período: el techo anual es 10.000 + 50.000 = 60.000. La norma nunca usa la palabra «liquidar» ni remite a la liquidación como impuesto.

El Tribunal Fiscal razonó por enumeración: el artículo 6201(a) autoriza liquidar impuestos y «multas liquidables», y el Congreso autorizó expresamente la liquidación en multitud de multas pero no en el 6038(b); sin liquidación administrativa, al gobierno solo le queda demandar en el tribunal de distrito según la regla general de 28 U.S.C. 2461(a). El Circuito de D.C. razonó por estructura e historia, incluida la reforma de 1982 que introdujo la multa fija en este artículo: una suma fija, disparada por una omisión definida y sin conexión con deuda tributaria alguna, es por diseño una multa liquidable. La misma laguna textual atraviesa los artículos 6038A (Formulario 5472), 6038B (Formulario 926) y 6038D (Formulario 8938). Recálculo según el patrón de liquidación descrito en la opinión (cifras verificadas dos veces): multas iniciales 10.000 × 8 = 80.000; continuación 50.000 × 8 = 400.000, con el tope comprobado como 5 × 10.000 = 50.000 por año; total 80.000 + 400.000 = 480.000, equivalente a 60.000 × 8. La disputa nunca fue la aritmética, sino si la suma podía cobrarse por liquidación y embargo. California no tiene un mecanismo estatal equivalente al del 6038(b) (grado de evidencia B; citas, fechas e importes verificados en las sentencias y el Código, grado A). (初译待校)

> Notas personales de estudio; no constituye asesoramiento fiscal. Fuentes: 160 T.C. n.º 6 (2023); 100 F.4th 223 (D.C. Cir. 2024); Mukhi, 162 T.C. n.º 8 y 163 T.C. n.º 8 (2024); Golsen, 54 T.C. 742 (1970); 26 U.S.C. 6038, 6201, 6330; 28 U.S.C. 2461(a).

## 한국어 (初译待校)

Farhy v. Commissioner, 160 T.C. No. 6 (2023년 4월 3일)은 IRS가 제6038(b)조 벌금을 부과·평가(assess)할 법정 권한이 없으며, 제6330조에 따라 사건을 법원에 가져온 압류로 그 벌금을 징수할 수도 없다고 판시했습니다. 컬럼비아특별구 순회항소법원은 이를 뒤집었습니다. Farhy v. Commissioner, 100 F.4th 223 (D.C. Cir. 2024년 5월 3일)은 제6038(b)(1)조의 정액 벌금이 평가 가능하다고 했고, 재심 청구는 2024년 6월 13일 기각되었습니다. 조세법원은 Mukhi v. Commissioner, 163 T.C. No. 8 (2024)(원판결은 162 T.C. No. 8)의 재고 결정에서 자기 입장을 재확인했는데, 그 사건은 제8순회로 항소할 사건이었기 때문입니다. Golsen v. Commissioner, 54 T.C. 742 (1970)에 따라 조세법원은 이미 판단한 순회의 결론을 그 순회로 항소될 사건에 따르고, 그 밖의 지역에서는 자기 규칙을 지킵니다. 이제 이 벌금의 평가 가능성은 항소 순회에 따라 갈립니다.

책임 자체는 다툼이 없었습니다. Alon Farhy는 2003년부터 2010년까지 벨리즈 법인들의 지분 100%를 보유하고도 제6038(a)조가 요구하는 Form 5471을 한 번도 제출하지 않았고, 조세법원은 그 불이행이 고의적이며 합리적 사유가 없다고 인정했습니다. IRS는 2016년 2월에 미제출 통지를 보냈고, 2018년 11월 5일에 제6038(b)(1)조 초기 벌금을, 2018년 11월 12일에 제6038(b)(2)조 지속 벌금을 평가했습니다. 제6038(b)(1)조는 미제출이 있는 각 연간 회계기간마다 10,000달러를, 제6038(b)(2)조는 통지 후 90일 유예기간이 지난 뒤에도 불이행이 계속되는 30일(또는 그 미만 기간)마다 10,000달러를 더하되 기간당 50,000달러가 상한이라, 연간 상한은 10,000 + 50,000 = 60,000달러입니다. 이 조항에는 «평가한다»는 말이 없고 세금처럼 평가·징수한다는 참조 조항도 없습니다.

조세법원은 열거 방식으로 읽었습니다. 제6201(a)조는 세금과 «평가 가능한 벌금»의 평가를 허용하는데, 의회는 수많은 벌금 조항에서 평가를 명시하면서도 제6038(b)조에서는 그러지 않았으므로 이 벌금은 평가할 수 없고, 정부는 28 U.S.C. 제2461(a)조의 기본 경로대로 연방지방법원에 소송을 내야 한다는 것입니다. 컬럼비아특별구 순회는 구조와 연혁으로 읽었습니다. 정액 벌금을 이 조항에 넣은 1982년 개정을 포함해 볼 때, 정해진 불이행으로 촉발되고 세액 부족분과 무관한 정액 벌금은 설계상 평가 가능한 벌금이며, «평가»라는 단어의 부재가 결론을 좌우하지 않는다는 것입니다. 같은 문언 공백이 제6038A조(Form 5472), 제6038B조(Form 926), 제6038D조(Form 8938)에도 있어 이 사건의 영향 범위는 Form 5471을 넘습니다. 판결문에 기재된 평가 방식으로 재계산하면(정수와 Decimal 두 번 검증) 초기 벌금 10,000 × 8 = 80,000달러, 지속 벌금 50,000 × 8 = 400,000달러(상한 자체도 5 × 10,000 = 50,000으로 맞아떨어짐), 합계 80,000 + 400,000 = 480,000달러, 즉 60,000 × 8과 같습니다. 싸움은 계산이 아니라 그 합계를 평가와 압류로 거둘 수 있는가였습니다. 캘리포니아에는 제6038(b)조에 대응하는 주 차원의 평가 장치가 없습니다(증거 등급 B; 사건 인용, 날짜, 금액은 판결과 법전 원문으로 확인, A등급). (初译待校)

> 개인 학습 노트이며 세무 자문이 아닙니다. 출처: 160 T.C. No. 6 (2023); 100 F.4th 223 (D.C. Cir. 2024); Mukhi, 162 T.C. No. 8 및 163 T.C. No. 8 (2024); Golsen, 54 T.C. 742 (1970); 26 U.S.C. 6038, 6201, 6330; 28 U.S.C. 2461(a).

## Tiếng Việt (初译待校)

Farhy v. Commissioner, 160 T.C. No. 6 (ngày 3 tháng 4 năm 2023) phán quyết rằng IRS không có thẩm quyền theo luật để ấn định (assess) các khoản phạt theo mục 6038(b) và không thể thu chúng bằng biện pháp cưỡng chế (levy) đã đưa vụ việc ra tòa theo mục 6330. Tòa Phúc thẩm Khu vực D.C. đã đảo ngược: Farhy v. Commissioner, 100 F.4th 223 (D.C. Cir., ngày 3 tháng 5 năm 2024) cho rằng khoản phạt cố định theo mục 6038(b)(1) là có thể ấn định được, và yêu cầu xét lại bị bác ngày 13 tháng 6 năm 2024. Tòa Thuế sau đó tái khẳng định quan điểm của mình khi xét lại vụ Mukhi v. Commissioner, 163 T.C. No. 8 (2024) (bản án gốc là 162 T.C. No. 8), vì vụ đó thuộc thẩm quyền phúc thẩm của Khu vực 8 — theo Golsen v. Commissioner, 54 T.C. 742 (1970), Tòa Thuế tuân theo khu vực đã phán quyết đối với các vụ thuộc khu vực đó và giữ quy tắc riêng ở nơi khác. Nay việc khoản phạt này có ấn định được hay không phụ thuộc vào khu vực phúc thẩm.

Về trách nhiệm thì không có gì phải bàn: từ 2003 đến 2010, Alon Farhy sở hữu 100% các công ty tại Belize và không nộp một tờ Form 5471 nào như mục 6038(a) yêu cầu; Tòa Thuế xác định việc không nộp là cố ý và không có lý do chính đáng. IRS gửi thông báo không nộp vào tháng 2 năm 2016, ấn định phạt ban đầu theo 6038(b)(1) vào ngày 5 tháng 11 năm 2018 và phạt tiếp diễn theo 6038(b)(2) vào ngày 12 tháng 11 năm 2018. Mục 6038(b)(1) phạt 10.000 đô la cho mỗi kỳ kế toán hằng năm có vi phạm; mục 6038(b)(2) cộng thêm 10.000 đô la cho mỗi 30 ngày (hoặc phần lẻ) vi phạm còn tiếp diễn sau thời gian ân hạn 90 ngày kể từ thông báo, tối đa 50.000 đô la cho mỗi kỳ — trần mỗi năm là 10.000 + 50.000 = 60.000 đô la. Điều khoản không hề dùng từ «ấn định» và cũng không có câu chuyển dẫn «ấn định và thu như thuế».

Tòa Thuế đọc theo lối liệt kê: mục 6201(a) cho phép ấn định thuế và «các khoản phạt có thể ấn định», Quốc hội đã cho phép ấn định một cách minh thị trong vô số điều khoản phạt nhưng không làm vậy với 6038(b), nên khoản phạt này không ấn định được và chính phủ phải kiện ra tòa quận liên bang theo quy tắc mặc định tại 28 U.S.C. 2461(a). Khu vực D.C. đọc theo cấu trúc và lịch sử lập pháp, kể cả sửa đổi năm 1982 đưa khoản phạt cố định vào mục này: một khoản tiền cố định, kích hoạt bởi một vi phạm xác định và không gắn với bất kỳ khoản thuế thiếu nào, theo thiết kế vốn là phạt có thể ấn định, và việc vắng chữ «ấn định» không quyết định kết quả. Khoảng trống văn bản tương tự cũng chạy qua các mục 6038A (Form 5472), 6038B (Form 926) và 6038D (Form 8938). Tính lại theo cách ấn định ghi trong bản án (đã kiểm chứng hai lần): phạt ban đầu 10.000 × 8 = 80.000; phạt tiếp diễn 50.000 × 8 = 400.000, với mức trần tự nó khớp 5 × 10.000 = 50.000 mỗi năm; tổng 80.000 + 400.000 = 480.000, tức 60.000 × 8. Tranh chấp chưa bao giờ nằm ở phép tính, mà ở chỗ tổng số đó có thu được bằng ấn định và cưỡng chế hay không. California không có cơ chế bang tương ứng với mục 6038(b) (cấp bằng chứng B; trích dẫn, ngày tháng và số tiền đã đối chiếu với bản án và Bộ luật, cấp A). (初译待校)

> Ghi chú học tập cá nhân, không phải tư vấn thuế. Nguồn: 160 T.C. No. 6 (2023); 100 F.4th 223 (D.C. Cir. 2024); Mukhi, 162 T.C. No. 8 và 163 T.C. No. 8 (2024); Golsen, 54 T.C. 742 (1970); 26 U.S.C. 6038, 6201, 6330; 28 U.S.C. 2461(a).

## हिन्दी (初译待校)

Farhy v. Commissioner, 160 T.C. No. 6 (3 अप्रैल 2023) ने कहा कि IRS के पास धारा 6038(b) के दंडों को निर्धारित (assess) करने का वैधानिक अधिकार नहीं है और वह उस प्रस्तावित लेवी से उन्हें वसूल भी नहीं सकता जिसके माध्यम से मामला धारा 6330 के तहत न्यायालय आया था। D.C. सर्किट ने इसे उलट दिया: Farhy v. Commissioner, 100 F.4th 223 (D.C. Cir., 3 मई 2024) ने धारा 6038(b)(1) के नियत-राशि दंड को निर्धारणीय ठहराया, और 13 जून 2024 को पुनः सुनवाई अस्वीकार हुई। कर न्यायालय ने फिर Mukhi v. Commissioner, 163 T.C. No. 8 (2024) (मूल निर्णय 162 T.C. No. 8) के पुनर्विचार में अपना मत दोहराया, क्योंकि वह मामला आठवें सर्किट में अपीलयोग्य था — Golsen v. Commissioner, 54 T.C. 742 (1970) के अनुसार कर न्यायालय उस सर्किट का अनुसरण करता है जिसने उस सर्किट में अपीलयोग्य मामलों पर निर्णय दे दिया हो, और अन्यत्र अपना नियम बनाए रखता है। अब इस दंड का निर्धारण संभव है या नहीं, यह अपील के सर्किट पर निर्भर है।

दायित्व पर कोई वास्तविक विवाद नहीं था: 2003 से 2010 तक Alon Farhy बेलीज़ निगमों के 100% स्वामी रहे और धारा 6038(a) की माँग के बावजूद एक भी Form 5471 दाखिल नहीं किया; कर न्यायालय ने चूक को जानबूझकर की गई और बिना उचित कारण की पाया। IRS ने फरवरी 2016 में चूक की सूचना भेजी, 5 नवंबर 2018 को धारा 6038(b)(1) के प्रारंभिक दंड निर्धारित किए और 12 नवंबर 2018 को धारा 6038(b)(2) के निरंतरता दंड। धारा 6038(b)(1) चूक वाले प्रत्येक वार्षिक लेखा अवधि पर 10,000 डॉलर लगाती है; धारा 6038(b)(2) सूचना के बाद 90 दिन की छूट अवधि बीतने पर भी चूक जारी रहने के प्रत्येक 30 दिन (या उसके अंश) पर 10,000 डॉलर और जोड़ती है, प्रति अवधि अधिकतम 50,000 डॉलर — अर्थात वार्षिक छत 10,000 + 50,000 = 60,000 डॉलर। प्रावधान में «निर्धारित» शब्द कहीं नहीं है और «कर की भाँति निर्धारित व वसूल» जैसी संदर्भ-पंक्ति भी नहीं है।

कर न्यायालय ने गणना-पद्धति से पढ़ा: धारा 6201(a) करों और «निर्धारणीय दंडों» के निर्धारण की अनुमति देती है; कांग्रेस ने असंख्य दंड प्रावधानों में निर्धारण का स्पष्ट अधिकार दिया, परंतु धारा 6038(b) में नहीं, इसलिए ये दंड निर्धारणीय नहीं हैं और सरकार को 28 U.S.C. 2461(a) के डिफ़ॉल्ट मार्ग से जिला न्यायालय में वाद करना होगा। D.C. सर्किट ने संरचना और इतिहास से पढ़ा, जिसमें 1982 का वह संशोधन भी शामिल है जिसने नियत-राशि दंड इस धारा में डाला: निश्चित चूक से सक्रिय होने वाली और किसी कर-कमी से असंबद्ध नियत राशि अपने स्वरूप से ही निर्धारणीय दंड है, और «निर्धारित» शब्द का अभाव निर्णायक नहीं है। यही पाठ्य अंतराल धारा 6038A (Form 5472), 6038B (Form 926) और 6038D (Form 8938) में भी है। निर्णय में वर्णित निर्धारण पद्धति पर पुनः गणना (दो बार सत्यापित): प्रारंभिक दंड 10,000 × 8 = 80,000; निरंतरता दंड 50,000 × 8 = 400,000, जहाँ छत स्वयं 5 × 10,000 = 50,000 प्रति वर्ष से मेल खाती है; कुल 80,000 + 400,000 = 480,000, अर्थात 60,000 × 8। लड़ाई गणित पर कभी नहीं थी — वह इस पर थी कि यह राशि निर्धारण और लेवी से वसूली जा सकती है या नहीं। California में धारा 6038(b) जैसी कोई राज्य-व्यवस्था नहीं है (साक्ष्य ग्रेड B; उद्धरण, तिथियाँ व राशियाँ निर्णयों व संहिता से सत्यापित, ग्रेड A)। (初译待校)

> व्यक्तिगत अध्ययन नोट; कर सलाह नहीं है। स्रोत: 160 T.C. No. 6 (2023); 100 F.4th 223 (D.C. Cir. 2024); Mukhi, 162 T.C. No. 8 व 163 T.C. No. 8 (2024); Golsen, 54 T.C. 742 (1970); 26 U.S.C. 6038, 6201, 6330; 28 U.S.C. 2461(a)।
