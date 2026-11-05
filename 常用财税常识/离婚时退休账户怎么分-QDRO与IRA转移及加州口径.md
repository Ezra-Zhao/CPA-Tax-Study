# 离婚时退休账户怎么分：QDRO 与 IRA 转移及加州口径

> 个人学习笔记，不构成税务或法律建议。离婚分财产时，退休账户往往是家里最大的一块资产，也是最容易分错的一块：401(k) 这类计划账户不能拿离婚判决直接去划钱，要先有一道叫 QDRO 的法院命令；IRA 则完全是另一套规则。分错一步，整笔会被当成提前支取，税和罚金一起到。

## 中文主文

### 一、先分清两类账户，两条路

分割路径取决于账户类型，不取决于判决书写了什么。第一类是雇主计划：401(k)、403(b)、养老金（pension）等受 ERISA 覆盖的合格计划，分给前配偶必须走 QDRO（Qualified Domestic Relations Order，合格家庭关系命令）。第二类是个人退休账户 IRA：不需要 QDRO，按 IRC § 408(d)(6) 以离婚判决为依据做受托人对受托人转移（trustee-to-trustee transfer）即可免税。把 IRA 的做法套到 401(k) 上（拿着判决书直接要求计划划款），或反过来给 IRA 去申请 QDRO，都是实务里最常见的两类错误。

### 二、QDRO 是什么：反转让规则的法定例外

合格计划的权益原则上不得转让（anti-alienation），依据是 IRC § 401(a)(13) 与 ERISA § 206(d)(1)。QDRO 是这条禁令的例外：IRC § 414(p) 与 ERISA § 206(d)(3) 规定，一份家庭关系命令（涉及离婚、子女抚养、赡养费或婚姻财产权利）若满足法定要件——明确双方与计划的名称地址、给 alternate payee（替代收款人，即前配偶或子女等受扶养人）的金额或比例与期间、不要求计划提供其原本没有的给付形式或增加精算价值——经计划管理员（plan administrator）审核认定为 qualified 之后，计划才能按命令把份额分给替代收款人。实务顺序是：判决先定分割比例 → 律师按 § 414(p) 要件起草 QDRO → 先送计划管理员预审 → 再交法院签署 → 签署版回送计划管理员执行。跳过预审直接让法院签，命令与计划条款对不上被退回重拟，是拖几个月的主因。

### 三、税怎么处理：滚存与领取是两种结果

QDRO 把份额分到前配偶名下后，税的走向看下一步动作。替代收款人是配偶或前配偶的，可以把分得的份额直接滚存（direct rollover）进自己名下的 IRA 或另一合格计划，滚存部分当期不缴税，税递延到日后支取；直接领取现金的，则按普通收入缴税，并由计划按 20% 强制预扣（§ 3405(c) 的合格计划直接滚存预扣规则）。这里有一个只属于 QDRO 的好处：IRC § 72(t)(2)(C) 规定，经 QDRO 分给替代收款人的计划分配，免于 10% 提前支取附加税——哪怕收款人还不到 59½ 岁。这条例外只适用于雇主计划经 QDRO 的分配；同一笔钱一旦先滚进 IRA，再从 IRA 提前取，§ 72(t) 的例外不再跟随，要另找 IRA 自己的例外（如 § 72(t)(2) 的其他项或 72(t) 分期支取安排）。顺序因此很重要：有近期用钱需求的人，往往应先在计划层完成 QDRO 分配与领取，再滚存剩余部分。

### 四、IRA 的分割：靠判决与直接转移，不靠 QDRO

IRA 按 § 408(d)(6)：依据离婚或分居协议把 IRA 权益转移给前配偶的，这笔转移不构成应税分配，也不触发提前支取税；操作上必须做成账户对账户的直接转移（改账户所有权或新开对方名下 IRA 后 trustee-to-trustee 转入），不要先把钱取到个人账户再转交——那样会被记录成一次分配，再存入还可能撞上 60 天间接滚存与一年一次的限制。转移完成后，前配偶按自己名下 IRA 的规则缴税与支取。另注意：分割基准日（以判决确定的估值日为准）之后到实际转移之间的涨跌归属，要在判决或协议里写清归谁，否则转移金额会长期扯皮。

### 五、养老金（DB 计划）的额外一层：份额形式与开始时间

确定给付型养老金没有现成账户余额可划，QDRO 要写清的是给付的切分方式：常见有按服务年限比例切分未来月付的 shared payment，或把替代收款人的份额单独精算成一笔 separate interest。两种写法的开始领取时间、身故处理与再婚影响都不同，属于必须由熟悉该计划的律师与精算口径核对的部分；本文只提示分法存在，不替代个案起草。

### 六、加州口径与收尾清单

加州是社区财产州，婚姻期间缴入的退休权益原则上属社区财产，离婚时由法院在财产分割中一并处理；联邦计划的执行仍受 ERISA 与 § 414(p) 支配，州法院的判决要落到计划层面，必须补上 QDRO 这一道，加州法院对此有专门的 joinder（计划加入诉讼）程序把计划拉进案件。收尾清单：①判决生效不等于分完——QDRO 签署并被计划管理员接受、IRA 转移实际入账，才算落地；②分割后立刻改受益人指定（beneficiary designation），计划受益人 designation 优先于遗嘱与多数州法文件，不改的话钱可能仍按旧指定走；③把 1099-R 留档：QDRO 分配与 IRA 转移的申报代码不同，报税时对不上要先找计划与受托机构核实，不要自行改数。

*声明：个人学习笔记，不构成税务、财务或法律建议。来源：IRC §§ 401(a)(13)、414(p)、408(d)(6)、72(t)(2)(C)、3405(c)；ERISA § 206(d)；IRS 关于 QDRO 与离婚退休金分割的公开说明（Retirement Topics — Divorce / QDRO）。计划条款与判决口径以个案文件为准，具体分割请咨询家事律师与 CPA。*

---

## English

In a divorce, retirement accounts are usually the largest asset — and the easiest to split wrongly. The route depends on the account type, not on what the decree says. Employer plans covered by ERISA (401(k), 403(b), pensions) can be divided with a former spouse only through a QDRO, a Qualified Domestic Relations Order. IRAs never use a QDRO: under IRC § 408(d)(6), an IRA interest transferred under a divorce decree by trustee-to-trustee transfer is not a taxable distribution.

Qualified plan benefits are normally non-assignable (IRC § 401(a)(13); ERISA § 206(d)(1)). A QDRO is the statutory exception: IRC § 414(p) and ERISA § 206(d)(3) let a domestic relations order assign benefits to an alternate payee — a spouse, former spouse, child, or other dependent — if it states the parties and plan, the amount or percentage and period, and does not require the plan to provide a form of benefit it does not otherwise offer or an actuarially increased benefit. The workable order of operations is: decree fixes the split → counsel drafts the QDRO → plan administrator pre-reviews the draft → court signs → administrator executes. Skipping pre-review is the main reason orders bounce back months later.

Tax then follows the alternate payee's next move. A spouse or former-spouse alternate payee may roll the awarded share directly into their own IRA or plan, deferring tax; taking cash means ordinary income plus 20% mandatory withholding on eligible rollover distributions. One QDRO-only benefit: § 72(t)(2)(C) exempts QDRO distributions to an alternate payee from the 10% early-distribution additional tax, even before age 59½ — but that exception lives only at the plan level. Once the money is rolled into an IRA, later withdrawals must find their own § 72(t) exception. For IRAs, the transfer itself is tax-free under § 408(d)(6) only if done trustee-to-trustee pursuant to the decree; withdrawing and handing over cash turns it into a distribution. Defined-benefit pensions need the QDRO to specify a shared-payment or separate-interest structure rather than an account balance.

California is a community-property state, so retirement earned during marriage is generally community property divided in the judgment — but federal plans still require the QDRO step, and California practice uses joinder to bring the plan into the case. Closing checklist: the split is not done until the QDRO is accepted and the IRA transfer posts; update beneficiary designations immediately (they override wills); and keep the Form 1099-R — QDRO distributions and IRA transfers report differently.

*Note: Personal study notes, not tax or legal advice. Sources: IRC §§ 401(a)(13), 414(p), 408(d)(6), 72(t)(2)(C), 3405(c); ERISA § 206(d); IRS retirement topics on divorce and QDROs.*

---

## Español (traducción de estudio)

Al divorciarse, las cuentas de jubilación suelen ser el activo mayor —y el más fácil de repartir mal—. La vía depende del tipo de cuenta, no de lo que diga la sentencia. Los planes de empleador cubiertos por ERISA (401(k), 403(b), pensiones) solo pueden dividirse con el excónyuge mediante una QDRO (Qualified Domestic Relations Order). Las IRA nunca usan QDRO: según el artículo 408(d)(6) del IRC, transferir el interés de una IRA conforme a la sentencia de divorcio, de fiduciario a fiduciario, no es una distribución gravable.

Los beneficios de un plan calificado son en principio intransferibles (§ 401(a)(13); ERISA § 206(d)(1)). La QDRO es la excepción legal: los artículos 414(p) del IRC y 206(d)(3) de ERISA permiten asignar beneficios a un alternate payee —cónyuge, excónyuge, hijo u otro dependiente— si la orden identifica a las partes y al plan, fija el monto o porcentaje y el período, y no exige al plan una forma de beneficio que no ofrece ni un valor actuarial mayor. El orden práctico es: la sentencia fija el reparto → el abogado redacta la QDRO → el administrador del plan la revisa en borrador → el juez la firma → el administrador la ejecuta. Saltarse la revisión previa es la causa principal de rechazos meses después.

El impuesto depende del siguiente paso del beneficiario alternativo. Si es cónyuge o excónyuge, puede trasladar (rollover) su parte directamente a su propia IRA u otro plan y diferir el impuesto; si cobra en efectivo, es ingreso ordinario con retención obligatoria del 20% en distribuciones elegibles para rollover. Una ventaja exclusiva de la QDRO: el § 72(t)(2)(C) exime las distribuciones por QDRO del impuesto adicional del 10% por retiro anticipado, aun antes de los 59½ años —pero esa excepción vive solo en el plan; una vez que el dinero entra en una IRA, los retiros posteriores necesitan su propia excepción del § 72(t)—. En las IRA, la transferencia es libre de impuesto bajo el § 408(d)(6) solo si es de fiduciario a fiduciario y conforme a la sentencia; retirar el dinero y entregarlo en mano lo convierte en distribución. Las pensiones de beneficio definido exigen que la QDRO defina una estructura de pago compartido (shared payment) o de interés separado (separate interest), porque no hay un saldo de cuenta que cortar.

California es un estado de bienes gananciales (community property): lo acumulado durante el matrimonio es en principio propiedad común que se reparte en la sentencia, pero los planes federales siguen exigiendo la QDRO, y la práctica californiana usa el joinder para traer al plan al proceso. Lista de cierre: el reparto no termina hasta que la QDRO es aceptada y la transferencia de la IRA se abona; hay que actualizar de inmediato los beneficiarios designados (prevalecen sobre el testamento) y guardar el formulario 1099-R, porque las distribuciones por QDRO y las transferencias de IRA se reportan de forma distinta.

*Nota: notas personales de estudio, no asesoría fiscal ni legal. Fuentes: IRC §§ 401(a)(13), 414(p), 408(d)(6), 72(t)(2)(C), 3405(c); ERISA § 206(d); temas de jubilación del IRS sobre divorcio y QDRO.*

---

## 한국어 (초역, 원어민 감수 대기)

이혼할 때 은퇴 계좌는 보통 가장 큰 자산이고, 가장 잘못 나누기 쉬운 자산입니다. 경로는 판결문 문구가 아니라 계좌 유형이 정합니다. ERISA가 적용되는 고용주 플랜(401(k), 403(b), 연금)은 QDRO(Qualified Domestic Relations Order, 적격 가정관계 명령)가 있어야만 전 배우자와 나눌 수 있습니다. IRA는 QDRO를 쓰지 않습니다. IRC §408(d)(6)에 따라 이혼 판결에 근거한 수탁자 간 직접 이전(trustee-to-trustee transfer)은 과세 대상 분배가 아닙니다.

적격 플랜의 급여는 원칙적으로 양도할 수 없습니다(§401(a)(13); ERISA §206(d)(1)). QDRO는 그 법정 예외로, §414(p)와 ERISA §206(d)(3)은 당사자와 플랜, 금액·비율과 기간을 명시하고 플랜에 원래 없는 급여 형태나 정산 가치 증가를 요구하지 않는 가정관계 명령에 대해 대체 수령인(alternate payee, 배우자·전 배우자·자녀 등)에게 급여를 배정할 수 있게 합니다. 실무 순서는 판결로 비율 확정 → QDRO 초안 작성 → 플랜 관리자의 사전 검토 → 법원 서명 → 집행입니다. 사전 검토를 건너뛰면 몇 달 뒤 반려되는 일이 잦습니다.

세금은 대체 수령인의 다음 행동이 정합니다. 배우자·전 배우자인 대체 수령인은 자기 IRA나 다른 플랜으로 직접 롤오버해 과세를 미룰 수 있고, 현금으로 받으면 일반소득에 20% 의무 원천징수가 붙습니다. QDRO만의 이점이 하나 있습니다. §72(t)(2)(C)는 QDRO로 대체 수령인에게 분배되는 금액에 대해 59½세 전이라도 10% 조기 인출 추가세를 면제합니다. 다만 이 예외는 플랜 단계에만 있고, 돈이 IRA로 넘어간 뒤의 인출은 IRA 자체의 예외를 따로 찾아야 합니다. 확정급여형 연금은 계좌 잔액이 없으므로 QDRO에 shared payment나 separate interest 같은 절단 방식을 명시해야 합니다.

캘리포니아는 부부공동재산(community property) 주로, 혼인 기간 중 쌓인 은퇴 권리는 원칙적으로 공동재산으로 판결에서 나뉘지만, 연방 플랜 집행에는 QDRO 단계가 여전히 필요하고 캘리포니아는 joinder 절차로 플랜을 사건에 끌어들입니다. 마무리 점검: QDRO가 승인되고 IRA 이전이 실제 입금되어야 분할이 끝난 것이고, 수익자 지정(beneficiary designation)은 유언보다 우선하므로 즉시 바꾸며, Form 1099-R은 QDRO 분배와 IRA 이전의 보고 방식이 다르므로 보관하십시오.

*주: 개인 학습 노트이며 세무·법률 자문이 아닙니다. 출처: IRC §§401(a)(13), 414(p), 408(d)(6), 72(t)(2)(C), 3405(c); ERISA §206(d); IRS 은퇴 주제(離婚·QDRO). 초역으로 원어민 감수 대기 중입니다.*

---

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

Khi ly hôn, tài khoản hưu trí thường là tài sản lớn nhất — và cũng dễ chia sai nhất. Lộ trình phụ thuộc vào loại tài khoản, không phụ thuộc vào cách viết của phán quyết. Các chương trình của người sử dụng lao động thuộc ERISA (401(k), 403(b), lương hưu) chỉ có thể chia cho vợ/chồng cũ thông qua QDRO (Qualified Domestic Relations Order — lệnh quan hệ gia đình đạt chuẩn). IRA không bao giờ dùng QDRO: theo IRC §408(d)(6), việc chuyển quyền lợi IRA theo phán quyết ly hôn bằng hình thức chuyển trực tiếp giữa các bên ủy thác (trustee-to-trustee) không phải là khoản phân phối chịu thuế.

Quyền lợi trong chương trình đạt chuẩn về nguyên tắc không thể chuyển nhượng (§401(a)(13); ERISA §206(d)(1)). QDRO là ngoại lệ theo luật: §414(p) của IRC và §206(d)(3) của ERISA cho phép một lệnh quan hệ gia đình phân bổ quyền lợi cho người thụ hưởng thay thế (alternate payee — vợ/chồng, vợ/chồng cũ, con hoặc người phụ thuộc khác) nếu lệnh nêu rõ các bên và chương trình, số tiền hoặc tỷ lệ cùng thời kỳ, và không buộc chương trình cung cấp hình thức quyền lợi vốn không có hoặc giá trị tính toán cao hơn. Thứ tự thực hành khả thi: phán quyết ấn định tỷ lệ chia → luật sư soạn QDRO → quản trị viên chương trình duyệt trước bản nháp → tòa ký → quản trị viên thi hành. Bỏ qua bước duyệt trước là nguyên nhân chính khiến lệnh bị trả lại sau nhiều tháng.

Thuế đi theo bước tiếp theo của người thụ hưởng thay thế. Nếu là vợ/chồng hoặc vợ/chồng cũ, người này có thể chuyển thẳng (rollover) phần được chia vào IRA hoặc chương trình khác của chính mình để hoãn thuế; nếu nhận tiền mặt thì là thu nhập thường kèm khấu trừ bắt buộc 20% đối với khoản phân phối đủ điều kiện rollover. Một lợi ích chỉ có ở QDRO: §72(t)(2)(C) miễn thuế bổ sung 10% do rút sớm cho khoản phân phối theo QDRO, kể cả trước 59½ tuổi — nhưng ngoại lệ này chỉ tồn tại ở tầng chương trình; khi tiền đã vào IRA, các lần rút sau phải tự tìm ngoại lệ §72(t) riêng. Lương hưu phúc lợi xác định (DB) không có số dư tài khoản, nên QDRO phải ghi rõ cấu trúc thanh toán chung (shared payment) hoặc quyền lợi tách riêng (separate interest).

California là bang tài sản chung (community property): quyền lợi hưu trí tích lũy trong hôn nhân về nguyên tắc là tài sản chung được chia trong phán quyết — nhưng chương trình liên bang vẫn đòi bước QDRO, và thực hành California dùng thủ tục joinder để đưa chương trình vào vụ án. Danh sách chốt việc: việc chia chỉ xong khi QDRO được chấp nhận và khoản chuyển IRA đã ghi có; cập nhật ngay người thụ hưởng chỉ định (chỉ định này thắng di chúc); và giữ Form 1099-R vì phân phối theo QDRO và chuyển IRA khai báo khác nhau.

*Ghi chú: ghi chép học tập cá nhân, không phải tư vấn thuế hay pháp lý. Nguồn: IRC §§401(a)(13), 414(p), 408(d)(6), 72(t)(2)(C), 3405(c); ERISA §206(d); chủ đề hưu trí của IRS về ly hôn và QDRO. Bản dịch sơ bộ, chờ hiệu đính.*

---

## हिन्दी (प्रारंभिक अनुवाद, समीक्षा लंबित)

तलाक़ में सेवानिवृत्ति खाते आम तौर पर सबसे बड़ी संपत्ति होते हैं — और सबसे आसानी से ग़लत बँटने वाले भी। रास्ता खाते के प्रकार से तय होता है, फ़ैसले की भाषा से नहीं। ERISA के तहत आने वाली नियोक्ता योजनाएँ (401(k), 403(b), पेंशन) पूर्व जीवनसाथी के साथ केवल QDRO (Qualified Domestic Relations Order) से बँट सकती हैं। IRA में QDRO कभी नहीं लगता: IRC §408(d)(6) के तहत तलाक़ के फ़ैसले के आधार पर trustee-to-trustee स्थानांतरण कर-योग्य वितरण नहीं है।

योग्य योजना के लाभ सामान्यतः अहस्तांतरणीय होते हैं (§401(a)(13); ERISA §206(d)(1))। QDRO इसका वैधानिक अपवाद है: §414(p) और ERISA §206(d)(3) घरेलू संबंध आदेश को alternate payee (जीवनसाथी, पूर्व जीवनसाथी, संतान या अन्य आश्रित) को लाभ देने की अनुमति देते हैं, यदि आदेश पक्षों व योजना को, राशि या प्रतिशत व अवधि को स्पष्ट करे, और योजना से ऐसी लाभ-आकृति न माँगे जो वह देती ही नहीं या बढ़ा हुआ actuarial मूल्य न माँगे। व्यावहारिक क्रम है: फ़ैसले से बँटवारा तय → वकील QDRO का मसौदा बनाए → योजना प्रशासक मसौदे की पूर्व-जाँच करे → न्यायालय हस्ताक्षर करे → प्रशासक लागू करे। पूर्व-जाँच छोड़ना महीनों बाद आदेश लौटने का मुख्य कारण है।

कर alternate payee के अगले कदम पर निर्भर करता है। जीवनसाथी या पूर्व जीवनसाथी अपनी हिस्सेदारी सीधे अपने IRA या अन्य योजना में rollover करके कर टाल सकता है; नकद लेने पर सामान्य आय और पात्र rollover वितरणों पर 20% अनिवार्य withholding लगता है। QDRO की एक विशेष सुविधा: §72(t)(2)(C) QDRO वितरणों को 59½ वर्ष से पहले भी 10% शीघ्र-वितरण अतिरिक्त कर से मुक्त करता है — लेकिन यह अपवाद केवल योजना स्तर पर रहता है; पैसा IRA में जाने के बाद की निकासियों को अपना §72(t) अपवाद अलग से खोजना होगा। Defined-benefit पेंशन में खाता शेष नहीं होता, इसलिए QDRO में shared payment या separate interest जैसी कटौती संरचना लिखनी पड़ती है।

कैलिफ़ोर्निया community property राज्य है: विवाह के दौरान अर्जित सेवानिवृत्ति अधिकार सामान्यतः सामुदायिक संपत्ति होकर फ़ैसले में बँटते हैं — फिर भी संघीय योजनाओं में QDRO चरण अनिवार्य रहता है, और कैलिफ़ोर्निया व्यवहार में योजना को मामले में लाने के लिए joinder प्रक्रिया चलती है। समापन सूची: बँटवारा तभी पूरा जब QDRO स्वीकार हो और IRA स्थानांतरण खाते में जमा हो जाए; beneficiary designation तुरंत बदलें (यह वसीयत पर भारी पड़ता है); और Form 1099-R सँभालकर रखें, क्योंकि QDRO वितरण और IRA स्थानांतरण अलग-अलग रिपोर्ट होते हैं।

*टिप्पणी: व्यक्तिगत अध्ययन नोट्स, कर या कानूनी सलाह नहीं। स्रोत: IRC §§401(a)(13), 414(p), 408(d)(6), 72(t)(2)(C), 3405(c); ERISA §206(d); तलाक़ व QDRO पर IRS के सेवानिवृत्ति विषय। यह प्रारंभिक अनुवाद है, समीक्षा लंबित है।*
