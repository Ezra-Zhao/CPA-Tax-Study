# 基金余额五分类备考核心：GASB 54 约束强度阶梯与支出顺序及加州口径

导语：政府基金报表底下那一行剩余，叫基金余额（fund balance），不叫净位置。GASB 第 54 号公告（2009 年 2 月发布、2010 年 6 月 15 日后开始的期间生效）把它按约束强度分成五类：不可动用、限制性、承诺性、指派性、未指派。通论篇里只有一段带过，本篇单拆这一格：五类各自的判定钥匙、谁能设谁能撤、支出时的动用顺序、赤字落在哪一类、稳定基金（雨天基金）怎么归类，以及与政府层面净位置三分的对照。本选题经 ls 文件名加全仓 grep 正文双查：文件名零命中、无 GASB 54 本体专篇，仓内仅政府会计通论篇一段提及五分类、与本篇以指针分工，故成篇。

## 中文主文

### 一、先认层级：只有政府基金用基金余额

基金余额只出现在政府基金（governmental funds：一般基金、特殊收入基金、资本项目基金、偿债基金、永久基金）的资产负债表里，因为政府基金用修正权责发生制加当期财务资源计量焦点，剩余反映的是可花资源的约束状态。专有基金与受托基金的剩余仍叫净位置（net position），沿用净投资于资本资产、限制性、未限制性三分。政府层面的政府活动列也用净位置三分。考试第一步永远是先认报表层级：看到 fund balance 就知道是政府基金层面，看到 net position 就不是五分类的地盘。

### 二、五分类：按约束强度从强到弱

第一类，不可动用（nonspendable）：形式上就不能花的，如存货、预付项目、长期应收的本金部分；或法律与契约要求完整保有的，如永久基金的本金。它问的不是谁限制了用途，而是这笔资源根本不是可花形态。

第二类，限制性（restricted）：约束来自外部或法律——债权人（债务契约）、捐赠人与出资人、其他政府的法律规定，或宪法条款与授权立法（enabling legislation）强加的用途。政府自己说了不算，外部方或更高位阶的法源才能设，也只有外部条件变化或约束到期才能解。

第三类，承诺性（committed）：政府最高决策层（highest level of decision-making authority，如市议会）在报告期末之前采取正式行动（formal action，如条例 ordinance 或决议）自我设定的用途约束。解除或变更必须走同一层级的同类正式行动——这是与下一类的分界线：设得正式，撤得也必须正式。

第四类，指派性（assigned）：只是政府或被授权官员表达的拟用意图（intent），既没有外部约束，也没有最高层正式行动。一般基金里，除不可动用、限制性、承诺性之外、政府有意指定用途的正余额落这一类；其他政府基金里，交完前三类后剩下的正余额全部是指派性。指派可以由最高决策层自己做，也可以授权某个机构或官员做，撤销不需要正式行动。

第五类，未指派（unassigned）：一般基金交完前四类后的剩余，正负都落这里；正的未指派余额只能出现在一般基金。其他政府基金只有在支出超过前四类合计、出现赤字时才报告负的未指派。记法：正未指派是一般基金的专利，负未指派哪儿赤字哪儿见。

### 三、支出顺序：花钱时先动哪一类

一笔支出同时符合多类的用途时，要有动用顺序政策。GASB 54 的默认口径是先花约束最强的：当限制性与未限制性（承诺、指派、未指派合称）都可用于同一目的时，先动用限制性；在未限制性内部，顺序为承诺性、指派性、未指派。政府可以自定未限制性内部的动用顺序政策，但必须披露，且实务与考试默认按承诺、指派、未指派的次序。顺序直接决定期末各类的余额，是报表编制的真动作，不是文字游戏。

### 四、稳定基金与最低余额政策

稳定安排（stabilization arrangement，俗称雨天基金）不是第六类：动用条件足够具体、且不是日常发生情形的，按限制性或承诺性报告（看约束来源）；条件宽泛到什么都能装的，只能落指派性或未指派。政府自定的最低基金余额政策（minimum fund balance policy）本身不产生任何一类约束，只须披露——目标线写得再正式，没有经正式行动把具体金额承诺给具体用途，就不进承诺性。附注还要披露五分类的构成细节、承诺与指派的决策层级与程序、稳定安排的要件与余额。

### 五、算例：五类拆账与顺序动用

某市一般基金期末基金余额合计 2,400,000 美元：存货 90,000 加预付 60,000 等于不可动用 150,000；州拨款与债务契约限制 600,000 为限制性；议会以条例承诺 450,000；管理层指派 350,000；则未指派等于 2,400,000 减 150,000 减 600,000 减 450,000 减 350,000 等于 850,000 美元。次年一笔 200,000 美元支出同时符合限制性、承诺性与指派性用途：按默认顺序先动限制性 200,000，限制性余 400,000，承诺与指派不动。两组数字本地复算两遍一致。

### 六、加州口径与易错点

加州各市县与学区同按 GASB 编报，基金余额五分类直接适用；加州政府法典对县库与预算的州法要求与 GASB 分类是两套语言，报表分类以 GASB 54 为准（联邦与准则锚点证据等级 A、加州落点 B）。易错点收束：一，把净位置三分套到政府基金头上。二，把管理层意图写成承诺性——没有最高层在期末前的正式行动，就只是指派性。三，以为其他政府基金可以有正的未指派。四，以为最低余额政策能造出承诺性。五，动用顺序反着来，先花未指派、把限制性留到期末，分类余额全错。

个人学习笔记，不构成税务或会计建议。条文以 GASB 第 54 号公告（Fund Balance Reporting and Governmental Fund Type Definitions）现行文本为准。算例本地复算两遍一致：90,000 加 60,000 等于 150,000；2,400,000 减 1,550,000 等于 850,000；600,000 减 200,000 等于 400,000。

## English

Fund balance is the residual of governmental funds only, reported under GASB Statement No. 54 (issued February 2009, effective for periods beginning after June 15, 2010) in five categories ranked by the strength of the constraint. Nonspendable amounts are not in spendable form (inventories, prepaids, long-term receivable principal) or must legally be kept intact (permanent fund principal). Restricted amounts carry constraints imposed externally — by creditors, grantors, contributors, laws of other governments — or by constitutional provisions and enabling legislation. Committed amounts are set by the government's highest level of decision-making authority through formal action taken before year-end, and can be undone only by the same type of formal action. Assigned amounts reflect mere intent, expressed by the governing body or a delegated official, with no formal-action requirement; in governmental funds other than the general fund, any positive residual after the first three categories is assigned. Unassigned is the general fund residual; a positive unassigned balance appears only in the general fund, while other governmental funds report negative unassigned when spending drives them into deficit. Proprietary and fiduciary funds, and the government-wide statements, still use three-component net position — the first exam step is always to identify the reporting layer. Spending order matters: when both restricted and unrestricted resources can fund an outlay, restricted is spent first; within unrestricted, the default flow is committed, then assigned, then unassigned, and the government's policy must be disclosed. Stabilization ("rainy day") arrangements are not a sixth category: with sufficiently specific, non-routine conditions they are reported as restricted or committed depending on the source of the constraint, and otherwise fall to assigned or unassigned; a minimum fund balance policy by itself creates no classification and is disclosed only. Worked example, verified twice: total fund balance $2,400,000; nonspendable $90,000 + $60,000 = $150,000; restricted $600,000; committed $450,000; assigned $350,000; unassigned = $2,400,000 − $1,550,000 = $850,000; a later $200,000 outlay eligible under three categories draws restricted first, leaving restricted at $400,000. California cities, counties and districts report under GASB, so the five categories apply directly; state budget statutes speak a different language and do not displace the GASB classification. *Personal study notes; not tax or accounting advice.*

## Español (初译待校)

El saldo de fondo es el residual solo de los fondos gubernamentales, clasificado por la GASB 54 (emitida en febrero de 2009, vigente para períodos iniciados después del 15 de junio de 2010) en cinco categorías por fuerza de la restricción. Lo no gastable no está en forma gastable (inventarios, anticipos, principal de cuentas por cobrar a largo plazo) o debe mantenerse intacto por ley (principal de fondos permanentes). Lo restringido trae restricciones externas: acreedores, otorgantes, contribuyentes, leyes de otros gobiernos, o disposiciones constitucionales y legislación habilitante. Lo comprometido lo fija la máxima autoridad decisoria mediante acción formal anterior al cierre, y solo se deshace con el mismo tipo de acción formal. Lo asignado es mera intención, sin acción formal; en fondos gubernamentales distintos del fondo general, todo residual positivo tras las tres primeras categorías es asignado. Lo no asignado es el residual del fondo general: un saldo positivo no asignado solo aparece en el fondo general, y otros fondos reportan no asignado negativo solo en déficit. Los fondos patrimoniales y fiduciarios siguen con posición neta de tres componentes. Al gastar, primero se usa lo restringido; dentro de lo no restringido, el orden por defecto es comprometido, asignado y no asignado. Los fondos de estabilización no son una sexta categoría, y una política de saldo mínimo por sí sola no crea clasificación alguna. Ejemplo verificado dos veces: total 2.400.000; no gastable 90.000 + 60.000 = 150.000; restringido 600.000; comprometido 450.000; asignado 350.000; no asignado = 2.400.000 − 1.550.000 = 850.000. (初译待校) *Notas personales de estudio; no constituyen asesoría fiscal ni contable.*

## 한국어 (初译待校)

기금 잔액(fund balance)은 정부기금만의 잔여이며, GASB 제54호(2009년 2월 발표, 2010년 6월 15일 이후 시작 기간에 적용)에 따라 제약의 강도 순으로 다섯 가지로 나뉩니다. 사용불가(nonspendable)는 재고·선급금·장기채권 원금처럼 지출 가능한 형태가 아니거나, 영구기금 원금처럼 온전히 보전해야 하는 금액입니다. 제한(restricted)은 채권자·보조자·출연자·다른 정부의 법률, 또는 헌법 규정과 수권 입법이 부과한 외부 제약입니다. 약정(committed)은 최고 의사결정기구가 기말 전에 취한 공식 조치로 설정되며, 같은 유형의 공식 조치로만 해제됩니다. 지정(assigned)은 공식 조치 없는 단순한 의도이며, 일반기금 이외의 정부기금에서는 앞의 세 범주 뒤에 남는 양의 잔여가 모두 지정입니다. 미지정(unassigned)은 일반기금의 잔여로, 양의 미지정은 일반기금에만 나타나고, 다른 기금은 적자일 때만 음의 미지정을 보고합니다. 전용기금과 신탁기금은 여전히 세 구성요소의 순자산(net position)을 씁니다. 지출 순서는 제한을 먼저 쓰고, 비제한 안에서는 약정·지정·미지정 순이 기본입니다. 안정화(비상) 기금은 여섯 번째 범주가 아니며, 최소 잔액 정책만으로는 어떤 분류도 생기지 않습니다. 두 번 검증한 산례: 합계 2,400,000달러, 사용불가 90,000 + 60,000 = 150,000, 제한 600,000, 약정 450,000, 지정 350,000, 미지정 = 2,400,000 − 1,550,000 = 850,000달러. (초역, 원어민 감수 대기) *개인 학습 노트이며 세무·회계 자문이 아닙니다.*

## Tiếng Việt (初译待校)

Số dư quỹ chỉ là phần còn lại của các quỹ chính phủ, được GASB 54 (ban hành tháng 2 năm 2009, áp dụng cho các kỳ bắt đầu sau ngày 15 tháng 6 năm 2010) chia thành năm loại theo độ mạnh của ràng buộc. Không chi được (nonspendable) là phần không ở dạng chi được — hàng tồn kho, trả trước, gốc phải thu dài hạn — hoặc phải giữ nguyên theo luật như gốc quỹ vĩnh viễn. Bị hạn chế (restricted) mang ràng buộc từ bên ngoài: chủ nợ, nhà tài trợ, người đóng góp, luật của chính phủ khác, hoặc điều khoản hiến pháp và luật trao quyền. Đã cam kết (committed) do cấp quyết định cao nhất đặt ra bằng hành động chính thức trước cuối kỳ, và chỉ gỡ được bằng cùng loại hành động chính thức. Đã chỉ định (assigned) chỉ là ý định, không cần hành động chính thức; ở các quỹ chính phủ ngoài quỹ chung, phần dương còn lại sau ba loại đầu đều là đã chỉ định. Chưa chỉ định (unassigned) là phần còn lại của quỹ chung: số dương chỉ xuất hiện ở quỹ chung, các quỹ khác chỉ báo cáo số âm khi thâm hụt. Quỹ doanh nghiệp và quỹ tín thác vẫn dùng vị thế ròng ba thành phần. Khi chi, dùng phần bị hạn chế trước; trong phần không hạn chế, thứ tự mặc định là cam kết, chỉ định, chưa chỉ định. Quỹ ổn định không phải loại thứ sáu, và chính sách số dư tối thiểu tự nó không tạo ra phân loại nào. Ví dụ đã kiểm hai lần: tổng 2.400.000; không chi được 90.000 + 60.000 = 150.000; bị hạn chế 600.000; đã cam kết 450.000; đã chỉ định 350.000; chưa chỉ định = 2.400.000 − 1.550.000 = 850.000. (Bản dịch sơ bộ, chờ hiệu đính) *Ghi chú học tập cá nhân, không phải tư vấn thuế hay kế toán.*

## हिन्दी (初译待校)

निधि शेष (fund balance) केवल सरकारी निधियों का अवशेष है, जिसे GASB 54 (फ़रवरी 2009 में जारी, 15 जून 2010 के बाद शुरू अवधियों पर लागू) बाध्यता की मज़बूती के क्रम में पाँच वर्गों में बाँटती है। अव्ययनीय (nonspendable) व्यय-योग्य रूप में नहीं है — माल-सूची, पूर्वभुगतान, दीर्घकालिक प्राप्य का मूलधन — या कानूनन अक्षुण्ण रखना है, जैसे स्थायी निधि का मूलधन। प्रतिबंधित (restricted) पर बाहरी बाध्यता है: लेनदार, अनुदानदाता, अंशदाता, अन्य सरकारों के कानून, या संवैधानिक प्रावधान और सशक्तिकरण विधान। प्रतिबद्ध (committed) सर्वोच्च निर्णय-स्तर द्वारा अवधि-अंत से पहले की गई औपचारिक कार्रवाई से बनता है और उसी प्रकार की औपचारिक कार्रवाई से ही हटता है। निर्दिष्ट (assigned) केवल आशय है, औपचारिक कार्रवाई आवश्यक नहीं; सामान्य निधि से भिन्न सरकारी निधियों में पहले तीन वर्गों के बाद बचा धनात्मक अवशेष निर्दिष्ट ही होता है। अनिर्दिष्ट (unassigned) सामान्य निधि का अवशेष है: धनात्मक अनिर्दिष्ट केवल सामान्य निधि में आता है, अन्य निधियाँ घाटे में ही ऋणात्मक अनिर्दिष्ट दिखाती हैं। स्वामित्व और न्यासी निधियाँ तीन-घटक शुद्ध स्थिति ही रखती हैं। खर्च में पहले प्रतिबंधित, फिर अप्रतिबंधित के भीतर प्रतिबद्ध, निर्दिष्ट, अनिर्दिष्ट का क्रम है। स्थिरीकरण निधि छठा वर्ग नहीं है, और न्यूनतम शेष नीति अकेले कोई वर्गीकरण नहीं बनाती। दो बार सत्यापित उदाहरण: कुल 2,400,000; अव्ययनीय 90,000 + 60,000 = 150,000; प्रतिबंधित 600,000; प्रतिबद्ध 450,000; निर्दिष्ट 350,000; अनिर्दिष्ट = 2,400,000 − 1,550,000 = 850,000। (प्रारंभिक अनुवाद, समीक्षा लंबित) *व्यक्तिगत अध्ययन नोट्स; कर या लेखा सलाह नहीं।*


## 补译增量（2026-11-17 02:55轮）

### 한국어 (初译待校)

보충 1 — 주석 공시 그룹(중국어 본문 넷째 절): 재무제표 주석에는 다섯 가지 분류의 구성 세부사항을 공시해야 하고, 약정과 지정이 어느 의사결정 단계에서 어떤 절차로 이루어지는지, 그리고 안정화 약정의 요건과 잔액도 공시해야 합니다.
보충 2 — 지출 순서 정책 공시 그룹(중국어 본문 셋째 절): 정부는 비제한 내부의 지출 순서를 자체 정책으로 정할 수 있지만 그 정책은 반드시 공시해야 하며, 정책을 두지 않은 경우의 기본 순서는 약정, 지정, 미지정 순입니다. 이 순서는 기말 각 분류의 잔액을 직접 결정합니다.
(초역, 원어민 감수 대기)

### Tiếng Việt (初译待校)

Bổ sung 1 — nhóm thuyết minh phải công bố (phần bốn của bản chính tiếng Trung): thuyết minh báo cáo tài chính phải công bố chi tiết cấu thành của năm nhóm phân loại, cấp ra quyết định và thủ tục của phần cam kết và phần chỉ định, cùng các điều kiện và số dư của thỏa thuận ổn định.
Bổ sung 2 — nhóm công bố chính sách thứ tự chi (phần ba của bản chính tiếng Trung): chính quyền có thể tự định thứ tự chi trong nhóm không bị hạn chế bằng chính sách riêng, nhưng chính sách đó bắt buộc phải công bố; khi không có chính sách riêng, thứ tự mặc định là cam kết, chỉ định, rồi chưa chỉ định, và thứ tự này quyết định trực tiếp số dư từng nhóm cuối kỳ.
(Bản dịch sơ bộ, chờ hiệu đính)

### हिन्दी (初译待校)

पूरक 1 — टिप्पणी प्रकटीकरण समूह (चीनी मूल पाठ का चौथा खंड): वित्तीय विवरणों की टिप्पणियों में पाँचों वर्गों की संरचना का विवरण, प्रतिबद्ध और निर्दिष्ट राशियों के निर्णय-स्तर व प्रक्रिया, तथा स्थिरीकरण व्यवस्था की शर्तें और शेष राशि प्रकट करनी होती है।
पूरक 2 — व्यय क्रम नीति प्रकटीकरण समूह (चीनी मूल पाठ का तीसरा खंड): सरकार अप्रतिबंधित वर्गों के भीतर व्यय क्रम अपनी नीति से तय कर सकती है, किंतु वह नीति प्रकट करना अनिवार्य है; अपनी नीति न हो तो डिफ़ॉल्ट क्रम प्रतिबद्ध, निर्दिष्ट और अनिर्दिष्ट है, और यही क्रम अवधि-अंत में प्रत्येक वर्ग का शेष सीधे तय करता है।
(प्रारंभिक अनुवाद, समीक्षा लंबित)
