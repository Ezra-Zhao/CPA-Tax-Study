# OPT 与 CPT 收入怎么报税：FICA 豁免、税收协定与 1040-NR

> 个人学习笔记，不构成税务建议。数字与口径以报税年度 IRS 公布为准；不确定的年度数字本文写「以当年 IRS 口径为准」，不硬填。

## 中文主文

### 一、先分清身份：税务居民身份不看签证名字，看测试

持 F-1 做 CPT、OPT 的人，最容易犯的错是把「移民法上的非移民」直接等同于「税法上的非居民外国人」。税法看的是 IRC §7701(b) 的两套测试：绿卡测试与实质居住测试（substantial presence test）。但有一类人先被排除在实质居住测试之外——exempt individual（豁免个人）。IRC §7701(b)(5) 把教师、学员（teacher/trainee）与学生分开规定：持 F、J 等身份的学生，在符合签证要求的前提下属于 exempt individual，其在美天数不计入实质居住测试；学生这一类的豁免年限一般是 **5 个日历年**（any 5 calendar years），教师与学员一般是 2 年口径，且条文还有「一生中以学生身份 claiming 的年限」等限制细节，报税时以当年 IRS Publication 519 口径为准。过了豁免年限、又通过实质居住测试的人，转为税务居民，改报 Form 1040；没过的人仍是非居民外国人（nonresident alien），报 Form 1040-NR。

豁免个人每年还有一个不能漏的动作：**Form 8843**。哪怕当年一分钱收入都没有，持 F/J 的 exempt individual 原则上也要单独寄出 Form 8843（Statement for Exempt Individuals and Individuals With a Medical Condition）；有收入、要报 1040-NR 的人，则把 8843 随 1040-NR 一起提交。8843 不是税表，是身份说明，漏交不会立刻产生税款，但会给以后解释身份留下缺口。

### 二、FICA 豁免：条文在 §3121(b)(19)，只豁工资税，不豁所得税

社会保障税与医保税（FICA）对非居民外国人有一条专门豁免：IRC **§3121(b)(19)** 规定，非居民外国人持 F-1、J-1、M-1、Q-1 等身份、为取得该身份的目的而从事的服务，其报酬不算 FICA 意义上的「工资」。落到 CPT/OPT 就是：身份仍是非居民外国人、且工作与 F/J 身份目的相符（校内工作、CPT、OPT 均在此列）时，工资**免 FICA**——雇主不应预扣 Social Security 与 Medicare 两部分。一旦此人转为税务居民（例如学生豁免年限用完并通过实质居住测试，或婚后选择按居民报税），豁免随之结束，FICA 照常扣。注意边界：豁免只管 FICA，不管联邦所得税——OPT 工资该交的所得税一分不少，预扣走 1040-NR 配套规则。

算例（复算用）：某 F-1 学生 OPT 年工资 20,000 美元，身份仍为非居民外国人。若雇主误扣 FICA，按雇员侧 7.65% 计算，被扣额为 20,000 × 6.2%（Social Security）＝1,240 美元，加 20,000 × 1.45%（Medicare）＝290 美元，合计 **1,530 美元**——这 1,530 美元就是后面要追回的金额。税率与 Social Security 工资上限逐年调整，算例只演示结构，实际以当年 IRS 口径为准。

### 三、所得税与中美税收协定：学生条款是第 20 条，每年 5,000 美元

工资的联邦所得税，持 F/J 的非居民外国人用 Form **1040-NR** 申报，与签证身份相连的收入填在相应行次，并附 Form 8843。中国学生的额外一层是《中美税收协定》：协定的**学生条款（第 20 条，Article 20）**规定，中国居民来美仅为教育或培训目的停留期间，为维持生活、教育或培训而取得的奖学金等款项有相应免税安排；实务中被引用最多的是：在美从事个人劳务（包括校内工作与 OPT 等）取得的收入，**每年有 5,000 美元免税额**。口径要点有三：①这 5,000 美元是协定免税额，不是标准扣除——非居民外国人一般没有联邦标准扣除（印度学生等协定特例除外），不要把两者混为一谈；②主张协定待遇要在 1040-NR 上按协定条目披露（金额大或条目要求时另附 Form 8833，以当年说明为准）；③协定只减联邦所得税，不减 FICA——FICA 靠的是 §3121(b)(19)，两条线不要串。加州不跟随联邦税收协定的这一免税处理：报加州税时，协定免掉的那部分收入通常要在州表上加回，以 FTB 当年口径为准。

算例接上：同一笔 20,000 美元工资，主张协定第 20 条后，联邦应税工资先减 5,000 美元，按 15,000 美元进入 1040-NR 的税率表计算（非居民外国人单身档税率表与居民同表、但无标准扣除）；FICA 仍为 0（靠 §3121(b)(19)），不是靠协定减的。

### 四、雇主错扣 FICA 怎么办：先找雇主，再走 843/8316

W-2 到手发现 Social Security 税框里有数字，先别直接找 IRS。IRS 定的顺序是：**第一步向雇主申请退还**——把身份文件、签证与 I-20/DS-2019、说明豁免的简短书面请求交给 payroll，雇主更正后会退钱并发更正的 W-2（W-2c）。多数大雇主与学校 payroll 熟悉这条，退得最快。**第二步，雇主拒绝或不回应时**，才向 IRS 提交 **Form 843**（Claim for Refund, and Request for Abatement）并附 **Form 8316**（Information Regarding Request for Refund of Social Security Tax Erroneously Withheld on Wages Received by an Alien Holding an F, J, or M Visa），同时附 W-2 副本、签证页与雇主拒绝或未退的说明，按 8316 说明寄到指定处理中心。时效上按一般退税申请期限理解（通常为税款视为缴纳之日起 3 年内，以当年 IRS 口径为准），所以发现错扣要尽早动手，不要拖过年限。注意：这条退还路径只适用于「本不该扣却扣了」的情形；已转税务居民年份被扣的 FICA 是合法预扣，不能用 843 要回。

### 五、清单收尾

每年开春先自问四件事：①今年我还是 exempt individual 吗（数清已用豁免日历年）？②8843 交了吗？③W-2 上 FICA 两框是否为空，不为空立刻启动退还顺序？④协定 5,000 美元主张了没有、披露对不对？四件事对齐，OPT/CPT 报税就不会出大错。

*声明：个人学习笔记，不构成税务建议。来源：IRC §3121(b)(19)、§7701(b)(5)；IRS Publication 519（U.S. Tax Guide for Aliens）；Form 8843、1040-NR、843、8316 说明；《中华人民共和国和美利坚合众国关于对所得避免双重征税和防止偷漏税的协定》第 20 条。*

---

## English

**Step 1 — status first.** For F-1 students on CPT/OPT, tax residency is not the visa label: IRC §7701(b)(5) treats qualifying F/J students as "exempt individuals" whose days do not count toward the substantial presence test, generally for up to **5 calendar years** as students (teachers/trainees follow a different, generally 2-year, pattern — confirm in IRS Publication 519 for the filing year). Exempt individuals file **Form 8843** every year, even with no income; with income they file **Form 1040-NR** with Form 8843 attached.

**Step 2 — FICA.** IRC **§3121(b)(19)** excludes from FICA "wages" the pay of a nonresident alien on F-1/J-1/M-1/Q-1 status for services performed to carry out the purpose of that status — so on-campus work, CPT and OPT pay is FICA-exempt while the person remains a nonresident alien, and the exemption ends once the person becomes a resident alien. It exempts FICA only, never income tax. Example: on $20,000 of OPT wages, a mistaken withholding at the employee rate would be $20,000 × 6.2% = $1,240 plus $20,000 × 1.45% = $290, total **$1,530**.

**Step 3 — the U.S.–China treaty.** Article 20 (students) of the U.S.–China income tax treaty is the provision Chinese students rely on; in practice the most-used piece is a **$5,000 annual exemption** for income from personal services performed in the United States. It is a treaty exemption, not a standard deduction (nonresident aliens generally get no standard deduction), it must be claimed and disclosed on Form 1040-NR (with Form 8833 when required), it does not reduce FICA, and California does not conform — the treaty-exempt amount is generally added back for state purposes (check current FTB guidance).

**Step 4 — getting wrongly withheld FICA back.** Ask the **employer first** for a refund and a corrected W-2c. Only if the employer refuses or does not respond, file **Form 843** with **Form 8316**, copies of the W-2 and visa documents, and proof of the failed employer request, within the general refund limitations period (confirm the current IRS instructions). FICA correctly withheld for resident-alien years cannot be reclaimed this way.

*Disclaimer: Personal study notes only; not tax advice. Sources: IRC §§3121(b)(19), 7701(b)(5); IRS Publication 519; Forms 8843, 1040-NR, 843 and 8316 instructions; U.S.–China income tax treaty, Article 20.*

## Español (traducción de estudio, pendiente de revisión nativa)

**Primero, el estatus.** Para estudiantes F-1 en CPT/OPT, la residencia fiscal no es la etiqueta de la visa: el IRC §7701(b)(5) trata a los estudiantes F/J que cumplen los requisitos como «exempt individuals», cuyos días no cuentan para la prueba de presencia sustancial, por lo general hasta **5 años calendario** como estudiantes (docentes y pasantes siguen otra pauta, en general 2 años; confirme en la Publicación 519 del IRS del año de declaración). Deben presentar el **Formulario 8843** cada año, incluso sin ingresos; con ingresos presentan el **Formulario 1040-NR** junto con el 8843.

**FICA.** El IRC **§3121(b)(19)** excluye de los «salarios» FICA la remuneración de un no residente con estatus F-1/J-1/M-1/Q-1 por servicios prestados para cumplir el propósito de ese estatus: el trabajo en el campus, el CPT y el OPT están exentos de FICA mientras la persona siga siendo extranjero no residente, y la exención termina al pasar a residente fiscal. Solo exime FICA, nunca el impuesto sobre la renta. Ejemplo: sobre $20,000 de salario OPT, una retención errónea a la tasa del empleado sería $20,000 × 6.2% = $1,240 más $20,000 × 1.45% = $290, total **$1,530**.

**Convenio EE. UU.–China.** El artículo 20 (estudiantes) es la norma que invocan los estudiantes chinos; en la práctica, la pieza más usada es una **exención anual de $5,000** para ingresos por servicios personales prestados en EE. UU. No es la deducción estándar (los no residentes por lo general no la tienen), debe reclamarse y revelarse en el 1040-NR (con el Formulario 8833 cuando se exige), no reduce FICA, y California no se ajusta a ella: el monto exento por convenio suele sumarse de nuevo a nivel estatal.

**Recuperar FICA retenido por error.** Pida primero el reembolso al **empleador** (y un W-2c corregido). Solo si el empleador se niega o no responde, presente el **Formulario 843** con el **Formulario 8316**, copias del W-2 y de la visa, y prueba de la gestión ante el empleador, dentro del plazo general de reembolso. El FICA correctamente retenido en años de residencia fiscal no se recupera por esta vía.

*Nota: notas personales de estudio; no constituye asesoría fiscal. Fuentes: IRC §§3121(b)(19), 7701(b)(5); Publicación 519 del IRS; instrucciones de los Formularios 8843, 1040-NR, 843 y 8316; convenio fiscal EE. UU.–China, artículo 20.*

## 한국어 (초역, 원어민 감수 대기 / 初译待校)

**1단계 — 신분부터.** F-1 학생의 CPT/OPT에서 세법상 거주성은 비자 이름이 아닙니다. IRC §7701(b)(5)는 요건을 갖춘 F/J 학생을 exempt individual로 보아 실질거주 테스트 일수에 넣지 않으며, 학생은 일반적으로 **5개 역년**까지입니다(교사·연수생은 일반적으로 2년의 다른 기준, 해당 연도 IRS Publication 519로 확인). 소득이 없어도 매년 **Form 8843**을 내고, 소득이 있으면 8843을 첨부해 **Form 1040-NR**로 신고합니다.

**FICA.** IRC **§3121(b)(19)**는 F-1/J-1/M-1/Q-1 신분 비거주 외국인이 그 신분의 목적을 수행하기 위한 근로로 받은 보수를 FICA 임금에서 제외합니다. 비거주 외국인인 동안 교내 근로·CPT·OPT 급여는 FICA가 면제되고, 세법상 거주자가 되면 면제가 끝납니다. 소득세는 면제되지 않습니다. 예시: OPT 급여 $20,000에 잘못 원천징수됐다면 근로자 부담률로 $20,000 × 6.2% = $1,240에 $20,000 × 1.45% = $290를 더해 합계 **$1,530**입니다.

**미·중 조세조약.** 중국 학생이 근거로 삼는 것은 조약 **제20조(학생)**이며, 실무에서 가장 많이 쓰는 부분은 미국 내 인적 용역 소득에 대한 **연 $5,000 면제**입니다. 이는 표준공제가 아니고(비거주 외국인은 원칙적으로 표준공제가 없음), 1040-NR에서 주장·공시해야 하며(필요시 Form 8833), FICA를 줄이지 않고, 캘리포니아는 이를 따르지 않아 주 신고에서 보통 다시 더합니다.

**잘못 낸 FICA 돌려받기.** 먼저 **고용주**에게 환급과 정정 W-2c를 요청하십시오. 고용주가 거부하거나 답이 없을 때만 W-2·비자 사본과 고용주 요청 실패 증빙을 붙여 **Form 843**과 **Form 8316**을 제출합니다. 거주자 연도에 정당하게 낸 FICA는 이 절차로 돌려받을 수 없습니다.

*개인 학습 노트이며 세무 자문이 아닙니다. 초역으로 교정 대기 중입니다. 출처: IRC §3121(b)(19), §7701(b)(5); IRS Publication 519; Form 8843·1040-NR·843·8316 안내; 미·중 조세조약 제20조.*
- 보충(중국어 본문과 대조): 세법상 신분은 먼저 § 7701(b)의 두 테스트, 즉 영주권 테스트와 실질거주 테스트로 가립니다. 이민법상의 비이민 신분이 곧바로 세법상의 비거주 외국인과 같지는 않습니다.
- 보충: 학생 exempt individual 지위는 비자 요건을 지키는 것이 전제이며, 학생 신분으로 주장할 수 있는 연수에는 평생 기준의 제한 등 세부 조건이 붙습니다. 해당 연도의 Publication 519로 반드시 확인하십시오.
- 보충: Form 8843은 세금 신고서가 아니라 신분 설명서입니다. 소득이 없으면 단독으로 보내고, 소득이 있으면 1040-NR에 붙여 냅니다. 내지 않아도 당장 세금이 생기지는 않지만, 나중에 신분을 설명할 때 빈틈이 됩니다.
- 보충: 조약 제20조에는 생활·교육·훈련을 위한 장학금 성격의 금액에 대한 면세 부분도 들어 있습니다. 또 비거주 외국인의 표준공제 부재에는 인도 학생 조약 특례 같은 예외가 있으니, 일률적으로 없다고 단정하지 마십시오.
- 보충: Form 843 환급 청구는 일반적으로 세금이 납부된 것으로 간주되는 시점부터 3년 이내가 기준이며, Form 8316 안내가 지정하는 처리 센터로 보냅니다. 첫 단계인 고용주 요청 때는 I-20/DS-2019 등 신분 서류를 함께 내는 것이 좋습니다.
- 보충: 연초 점검 네 가지 — ① 아직 exempt individual인가(사용한 역년 계산), ② 8843을 냈는가, ③ W-2의 FICA 두 칸이 비어 있는가(아니면 환급 순서 즉시 시작), ④ 조약 5,000달러를 주장했고 공시가 맞는가. 또 위 FICA 예시의 세율과 사회보장 임금 상한은 매년 조정되므로, 예시는 구조만 보여 줍니다. (초역 보충, 원어민 감수 대기)

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính / 初译待校)

**Bước 1 — xác định tình trạng trước.** Với sinh viên F-1 làm CPT/OPT, cư trú thuế không phải là tên visa: IRC §7701(b)(5) coi sinh viên F/J đủ điều kiện là exempt individual, số ngày không tính vào substantial presence test, thường tối đa **5 năm dương lịch** với diện sinh viên (giáo viên/thực tập sinh theo chuẩn khác, thường 2 năm — đối chiếu Publication 519 của IRS cho năm khai thuế). Mỗi năm phải nộp **Form 8843** kể cả khi không có thu nhập; có thu nhập thì nộp **Form 1040-NR** kèm 8843.

**FICA.** IRC **§3121(b)(19)** loại khỏi "tiền lương" FICA khoản thù lao của người nước ngoài không cư trú diện F-1/J-1/M-1/Q-1 cho công việc nhằm thực hiện mục đích của diện đó: việc làm trong trường, CPT và OPT được miễn FICA khi người đó vẫn là nonresident alien, và miễn trừ chấm dứt khi trở thành resident alien. Miễn trừ này chỉ áp dụng cho FICA, không cho thuế thu nhập. Ví dụ: với lương OPT $20,000, khấu trừ nhầm theo tỷ lệ phía nhân viên sẽ là $20,000 × 6.2% = $1,240 cộng $20,000 × 1.45% = $290, tổng **$1,530**.

**Hiệp định Mỹ–Trung.** Điều 20 (sinh viên) là căn cứ sinh viên Trung Quốc viện dẫn; phần dùng nhiều nhất trong thực tế là **miễn $5,000 mỗi năm** cho thu nhập từ dịch vụ cá nhân thực hiện tại Hoa Kỳ. Đây không phải khấu trừ tiêu chuẩn (nonresident alien thường không có), phải khai và công bố trên 1040-NR (kèm Form 8833 khi được yêu cầu), không làm giảm FICA, và California không tuân theo — phần miễn theo hiệp định thường phải cộng lại khi khai thuế bang.

**Lấy lại FICA bị khấu trừ nhầm.** Trước hết yêu cầu **người sử dụng lao động** hoàn tiền và cấp W-2c đính chính. Chỉ khi họ từ chối hoặc không phản hồi mới nộp **Form 843** kèm **Form 8316**, bản sao W-2 và visa, cùng bằng chứng đã yêu cầu chủ lao động, trong thời hạn hoàn thuế chung. FICA đã khấu trừ đúng cho các năm resident alien thì không lấy lại được bằng cách này.

*Ghi chú học tập cá nhân, không phải tư vấn thuế. Bản dịch sơ bộ, chờ hiệu đính. Nguồn: IRC §3121(b)(19), §7701(b)(5); IRS Publication 519; hướng dẫn Form 8843, 1040-NR, 843, 8316; Hiệp định thuế Mỹ–Trung, Điều 20.*
- Bổ sung (đối chiếu văn bản tiếng Trung): tình trạng thuế trước hết được xét bằng hai phép thử tại § 7701(b) — green card test và substantial presence test; thân phận nonimmigrant theo luật di trú không tự động đồng nghĩa nonresident alien theo luật thuế.
- Bổ sung: tư cách exempt individual diện sinh viên có tiền đề là tuân thủ điều kiện visa, và số năm được viện dẫn diện sinh viên còn có các giới hạn chi tiết theo cả đời người — phải đối chiếu Publication 519 của năm khai thuế.
- Bổ sung: Form 8843 không phải tờ khai thuế mà là bản giải trình tình trạng; không có thu nhập thì gửi riêng, có thu nhập thì nộp kèm 1040-NR. Không nộp không phát sinh thuế ngay, nhưng để lại khoảng trống khi phải giải trình tình trạng về sau.
- Bổ sung: Điều 20 của hiệp định còn có phần miễn thuế cho các khoản kiểu học bổng phục vụ sinh hoạt, giáo dục hoặc đào tạo. Ngoài ra, việc nonresident alien không có standard deduction vẫn có ngoại lệ như đặc lệ hiệp định cho sinh viên Ấn Độ, không nên khẳng định tuyệt đối.
- Bổ sung: yêu cầu hoàn thuế bằng Form 843 thường theo mốc 3 năm kể từ khi thuế được coi là đã nộp, và gửi tới trung tâm xử lý do hướng dẫn Form 8316 chỉ định. Ở bước yêu cầu người sử dụng lao động trước, nên kèm theo giấy tờ tình trạng như I-20/DS-2019.
- Bổ sung: bốn câu hỏi tự kiểm mỗi đầu năm — ① còn là exempt individual không (đếm số năm dương lịch đã dùng), ② đã nộp 8843 chưa, ③ hai ô FICA trên W-2 có trống không (nếu không, bắt đầu ngay trình tự đòi lại), ④ đã viện dẫn 5.000 đô la theo hiệp định và công bố đúng chưa. Thuế suất và trần lương an sinh trong ví dụ FICA ở trên thay đổi theo năm; ví dụ chỉ minh họa cấu trúc. (Bổ sung bản dịch sơ bộ, chờ hiệu đính)

## हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित / 初译待校)

**चरण 1 — पहले स्थिति तय करें।** F-1 छात्रों के CPT/OPT में कर-निवास वीज़ा के नाम से तय नहीं होता: IRC §7701(b)(5) योग्य F/J छात्रों को exempt individual मानता है, जिनके दिन substantial presence test में नहीं गिने जाते, छात्रों के लिए सामान्यतः **5 कैलेंडर वर्ष** तक (शिक्षक/प्रशिक्षुओं के लिए अलग, सामान्यतः 2 वर्ष का मानदंड — दाखिल वर्ष के IRS Publication 519 से जाँचें)। आय न हो तब भी हर वर्ष **Form 8843** दें; आय हो तो 8843 के साथ **Form 1040-NR** दाखिल करें।

**FICA.** IRC **§3121(b)(19)** F-1/J-1/M-1/Q-1 स्थिति वाले अनिवासी विदेशी के उस स्थिति के उद्देश्य हेतु किए कार्य के पारिश्रमिक को FICA "wages" से बाहर रखता है: nonresident alien रहते हुए campus work, CPT और OPT वेतन FICA से मुक्त है, और resident alien बनते ही छूट समाप्त हो जाती है। यह केवल FICA छूट है, आयकर नहीं। उदाहरण: $20,000 OPT वेतन पर ग़लत कटौती कर्मचारी दर से $20,000 × 6.2% = $1,240 और $20,000 × 1.45% = $290, कुल **$1,530** होगी।

**अमेरिका–चीन संधि।** चीनी छात्र संधि के **अनुच्छेद 20 (छात्र)** का सहारा लेते हैं; व्यवहार में सबसे अधिक प्रयुक्त भाग अमेरिका में व्यक्तिगत सेवाओं से आय पर **$5,000 वार्षिक छूट** है। यह standard deduction नहीं है (nonresident aliens को सामान्यतः वह नहीं मिलता), इसे 1040-NR पर दावा और प्रकट करना होता है (आवश्यकता पर Form 8833), यह FICA नहीं घटाती, और California इसका अनुसरण नहीं करता — संधि-मुक्त राशि राज्य स्तर पर सामान्यतः वापस जुड़ती है।

**ग़लत कटा FICA वापस पाना।** पहले **नियोक्ता** से refund और corrected W-2c माँगें। नियोक्ता मना करे या जवाब न दे तभी W-2 व वीज़ा की प्रतियों और नियोक्ता-प्रयास के प्रमाण के साथ **Form 843** और **Form 8316** सामान्य refund समय-सीमा में दाखिल करें। Resident-alien वर्षों में सही कटा FICA इस मार्ग से वापस नहीं मिलता।

*व्यक्तिगत अध्ययन नोट्स; कर सलाह नहीं। प्रारंभिक अनुवाद, समीक्षा लंबित। स्रोत: IRC §3121(b)(19), §7701(b)(5); IRS Publication 519; Form 8843, 1040-NR, 843, 8316 निर्देश; अमेरिका–चीन कर संधि, अनुच्छेद 20।*

---

*声明（六语）：个人学习笔记，不构成税务建议。 / Personal study notes only; not tax advice. / Notas personales de estudio; no constituye asesoría fiscal. / 개인 학습 노트이며 세무 자문이 아닙니다. / Ghi chú học tập cá nhân, không phải tư vấn thuế. / व्यक्तिगत अध्ययन नोट्स; कर सलाह नहीं।*
- पूरक (चीनी मूल पाठ से मिलान): कर-स्थिति पहले § 7701(b) की दो कसौटियों — green card test और substantial presence test — से तय होती है; आप्रवासन कानून का nonimmigrant दर्जा अपने आप कर-कानून का nonresident alien नहीं होता।
- पूरक: छात्र exempt individual का दर्जा वीज़ा शर्तों के पालन पर निर्भर है, और छात्र के रूप में दावा किए जा सकने वाले वर्षों पर आजीवन-आधारित सीमा जैसी विस्तृत शर्तें हैं — दाखिल वर्ष के Publication 519 से अवश्य जाँचें।
- पूरक: Form 8843 कर रिटर्न नहीं, स्थिति-विवरण है; आय न हो तो अलग से भेजें, आय हो तो 1040-NR के साथ लगाएँ। न भेजने से तुरंत कर नहीं बनता, किंतु बाद में स्थिति समझाने में कमी रह जाती है।
- पूरक: संधि के अनुच्छेद 20 में जीवन-यापन, शिक्षा या प्रशिक्षण हेतु छात्रवृत्ति-स्वरूप राशियों की छूट का भाग भी है। साथ ही, nonresident alien को standard deduction न मिलने के अपवाद भी हैं, जैसे भारतीय छात्रों के लिए संधि-विशेष व्यवस्था — इसे निरपेक्ष नियम न कहें।
- पूरक: Form 843 से refund का दावा सामान्यतः उस समय से 3 वर्षों के भीतर होता है जब कर चुकाया माना जाता है, और इसे Form 8316 निर्देशों में बताए गए प्रोसेसिंग केंद्र को भेजा जाता है। पहले चरण में नियोक्ता से अनुरोध करते समय I-20/DS-2019 जैसे स्थिति दस्तावेज़ साथ रखना उपयोगी है।
- पूरक: हर वर्ष की शुरुआत में चार आत्म-प्रश्न — ① क्या मैं अब भी exempt individual हूँ (प्रयुक्त कैलेंडर वर्ष गिनें), ② 8843 दाखिल किया क्या, ③ W-2 के दोनों FICA बॉक्स खाली हैं क्या (न हों तो वापसी की प्रक्रिया तुरंत शुरू करें), ④ संधि की $5,000 छूट का दावा और प्रकटीकरण सही है क्या। ऊपर के FICA उदाहरण की दरें और सामाजिक सुरक्षा वेतन सीमा हर वर्ष बदलती हैं; उदाहरण केवल संरचना दिखाता है। (पूरक प्रारंभिक अनुवाद, समीक्षा लंबित)
