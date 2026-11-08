# 用储蓄债券付学费利息能免税吗：IRC §135 教育储蓄债券、比例排除与 MAGI 相位

> 个人学习笔记，不构成税务建议。相位起止点逐年按通胀调整，报税时以当年 Rev. Proc. 与 IRS Publication 970、Form 8815 说明为准。

## 中文主文

### 一、先定性：免的不是本金，是赎回那年的利息

美国储蓄债券（Series EE 与 Series I）的利息，联邦层面本来要交税，只是通常可以递延到赎回、到期或转让那年再报。第 135 条（IRC §135）给的是再往前一步的排除：同一年里把赎回款拿去付合格高等教育费用，赎回利息可以全部或部分不进总收入。先分清三笔钱：本金从来不是收入，谈不上免；被排除的只有利息；而且排除额还要过两道筛——费用比例筛和收入相位筛（见第三、四节）。申报落点是 Form 8815（Education Savings Bond Program），排除额从利息收入里减掉，不是抵免，也不是逐项扣除。

### 二、哪种债券、哪种费用才算数

债券一侧看 §135(c) 的「合格美国储蓄债券」定义：1989 年 12 月 31 日之后发行、以折价发行口径计息的 EE 或 I 债券，且购买人在发行日之前已经年满 24 岁——给未成年孩子以孩子名义买的债券，利息不符合本条，债券登记在谁名下、谁买的，发行时就定了，后面补不回来。费用一侧看 §135(c)(2)：纳税人本人、配偶或受扶养人在合格教育机构（eligible educational institution）就读的学费与杂费（tuition and fees）。注意只有学费杂费：食宿、书本、交通不算，这一点比 529 的口径窄。向 §529 合格学费计划（QTP）或 §530 Coverdell 教育储蓄账户的供款，也算本条的合格费用。费用还要先减掉免税教育援助（免税奖学金、退伍军人教育补助等）以及已经拿去主张其他教育优惠（如 AOTC）的金额，同一美元不能两头占。

身份上还有一条硬线：已婚者必须与配偶合报（married filing jointly）才能用本条，分开报直接出局（§135 末段的合报要求）。

### 三、第一道筛：赎回款超过费用，按比例缩水

§135(b)(1) 的比例规则：当年赎回所得（本金加利息）不超过当年合格费用的，利息全额进排除候选；赎回所得超过费用的，可排除利息按「费用 ÷ 赎回所得」的比例缩减。

**算例一（本地两遍复算）。** 赎回一批债券拿到 12,000 美元，其中本金 9,000、利息 3,000；同年付合格学费杂费 9,000 美元。比例 ＝ 9,000 ÷ 12,000 ＝ 75%；可排除利息 ＝ 3,000 × 75% ＝ 2,250 美元（复算：3,000 × 0.75 ＝ 2,250，一致）；应税利息 ＝ 3,000 − 2,250 ＝ 750 美元。勾稽：9,000 ＋ 3,000 ＝ 12,000，与赎回所得对平。若按 22% 边际税率示意，全额排除 2,250 美元约省税 2,250 × 22% ＝ 495 美元（复算：2,250 × 0.22 ＝ 495，一致）。

### 四、第二道筛：MAGI 相位过了线，排除再打折

§135(b)(2) 的相位：法条基数是 40,000 美元（合报 60,000 美元），逐年按通胀调整，超过相位上限的部分按 15,000 美元（合报 30,000 美元）的宽度比例削减。现行公布数（Rev. Proc. 2024-40 与 Rev. Proc. 2025-32）：2025 年单身与户主 99,500–114,500 美元、合报 149,250–179,250 美元；2026 年单身与户主 101,800–116,800 美元、合报 152,650–182,650 美元。本条的 MAGI 是 AGI 加回本条排除本身等少数项目，以 Form 8815 工作表为准。

**算例二（接算例一，本地两遍复算）。** 合报，2026 年 MAGI 为 167,650 美元：超出相位起点 ＝ 167,650 − 152,650 ＝ 15,000 美元（复算：167,650 − 152,650 ＝ 15,000，一致）；削减比例 ＝ 15,000 ÷ 30,000 ＝ 50%；最终排除 ＝ 2,250 × (1 − 50%) ＝ 1,125 美元（复算：2,250 × 0.5 ＝ 1,125，一致）；应税利息 ＝ 3,000 − 1,125 ＝ 1,875 美元。两道筛是串联的：先比例、后相位，顺序不要颠倒。

### 五、和 529、教育抵免怎么分工

§135 是「先买债券、赎回年付学费」的老通道，金额小、门槛多，今天多数家庭的主力是 529；它的实际价值在存量债券：家里早年买的 EE、I 债券正好在孩子上大学那几年赎回的，先算一遍本条，能排除多少算多少，再考虑把赎回款供进 529（供款本身也算本条合格费用，见第二节）做衔接。顺序上同一笔费用先满足免税援助与抵免的口径，再轮到本条的工作表，账要留到税表时效走完。

### 六、加州口径与记录清单

储蓄债券利息在州层面另有出处：31 U.S.C. §3124 使美国政府义务的利息免于州与地方课税，所以这笔利息在加州本来就不交州税，§135 的排除只作用在联邦一层，不要在加州表上再找一遍加回或扣除。留存清单：债券购买记录与发行日期（核 24 岁与 1989 年后两道门）、赎回对账（Form 1099-INT 第 3 格是储蓄债券利息的核对起点）、学费账单与付款凭证、免税奖学金等援助的金额记录、Form 8815 工作表底稿。

*声明：个人学习笔记，不构成税务建议。来源：IRC §135（尤其 (b)(1) 比例限制、(b)(2) MAGI 相位、(c) 合格债券与合格费用定义）；31 U.S.C. §3124；Rev. Proc. 2024-40（2025 年相位）与 Rev. Proc. 2025-32（2026 年相位）；IRS Publication 970 第 10 章与 Form 8815 及其说明。*

---

## English

Series EE and Series I savings bond interest is federally taxable, normally deferred until redemption. IRC §135 lets a taxpayer exclude some or all of that interest in the redemption year if the proceeds pay qualified higher education expenses in the same year, claimed on Form 8815. Only interest can be excluded, never principal. A qualified bond must have been issued after December 31, 1989, and the purchaser must have been at least 24 years old before the issue date, so bonds bought in a young child's own name fail. Qualified expenses are tuition and fees only — not room, board, or books — for the taxpayer, spouse, or dependent at an eligible institution, and contributions to a §529 plan or a §530 Coverdell ESA also count; expenses are reduced by tax-free educational assistance and by amounts used for other education benefits. A married taxpayer must file jointly. Two screens then apply in order. First, the §135(b)(1) fraction: if redemption proceeds exceed qualified expenses, excludable interest is prorated — proceeds of $12,000 (principal $9,000 plus interest $3,000) against $9,000 of expenses give a 75% fraction, so $3,000 × 75% = $2,250 is the candidate exclusion and $750 stays taxable (recomputed twice). Second, the §135(b)(2) MAGI phaseout: for 2026 the ranges are $101,800–$116,800 for single and head-of-household filers and $152,650–$182,650 for joint filers (Rev. Proc. 2025-32; the 2025 ranges were $99,500–$114,500 and $149,250–$179,250 under Rev. Proc. 2024-40). A joint MAGI of $167,650 sits $15,000 into a $30,000-wide band, a 50% cut, leaving $2,250 × 50% = $1,125 excluded and $1,875 taxable. At the state level the interest is already exempt under 31 U.S.C. §3124, so §135 matters only on the federal return and California taxes none of this interest either way. *Personal study notes only; not tax advice.*

## Español (traducción de estudio, pendiente de revisión nativa)

Los intereses de los bonos de ahorro Series EE y Series I tributan a nivel federal, normalmente diferidos hasta el rescate. El §135 del IRC permite excluir parte o la totalidad de esos intereses en el año del rescate si el dinero paga gastos calificados de educación superior ese mismo año, mediante el Formulario 8815. Solo se excluye el interés, nunca el principal. El bono calificado debe haberse emitido después del 31 de diciembre de 1989 y el comprador debe haber cumplido 24 años antes de la fecha de emisión, por lo que los bonos comprados a nombre de un niño pequeño no califican. Los gastos calificados son solo matrícula y tasas —no alojamiento, comida ni libros— del contribuyente, su cónyuge o un dependiente en una institución elegible, y también cuentan las aportaciones a un plan §529 o a una cuenta Coverdell §530; los gastos se reducen por la ayuda educativa libre de impuestos y por los importes ya usados para otros beneficios. Quien está casado debe declarar en conjunto. Después operan dos filtros en orden. Primero, la fracción del §135(b)(1): si el producto del rescate supera los gastos, el interés excluible se prorratea —producto de $12.000 (principal $9.000 más interés $3.000) frente a gastos de $9.000 da una fracción del 75%, así que $3.000 × 75% = $2.250 es la exclusión candidata y $750 queda gravable (recalculado dos veces). Segundo, la reducción por MAGI del §135(b)(2): para 2026 los rangos son $101.800–$116.800 para solteros y cabezas de familia y $152.650–$182.650 para declaración conjunta (Rev. Proc. 2025-32; en 2025 fueron $99.500–$114.500 y $149.250–$179.250, Rev. Proc. 2024-40). Un MAGI conjunto de $167.650 está $15.000 dentro de una banda de $30.000, un recorte del 50%, que deja $2.250 × 50% = $1.125 excluidos y $1.875 gravables. A nivel estatal el interés ya está exento por 31 U.S.C. §3124, así que el §135 solo importa en la declaración federal y California no grava este interés en ningún caso. *Notas personales de estudio; no constituye asesoramiento fiscal.*

## 한국어 (초역, 원어민 감수 대기 / 初译待校)

Series EE와 Series I 저축채권 이자는 연방 과세 대상이며 보통 상환 시점까지 이연됩니다. IRC §135는 상환금을 같은 해에 적격 고등교육 비용으로 쓰면 그 이자의 전부 또는 일부를 제외할 수 있게 하며 Form 8815로 청구합니다. 제외되는 것은 이자뿐이고 원금은 애초에 소득이 아닙니다. 적격 채권은 1989년 12월 31일 이후에 발행되고 구매자가 발행일 전에 만 24세 이상이어야 하므로, 어린 자녀 명의로 산 채권은 해당되지 않습니다. 적격 비용은 수업료와 수수료뿐이며(기숙사비, 식비, 교재비 제외) 납세자·배우자·부양가족이 적격 기관에 다닐 때의 비용이고, §529 플랜이나 §530 Coverdell ESA에 대한 납입도 포함됩니다. 비용에서는 비과세 교육 지원과 다른 교육 혜택에 이미 쓴 금액을 차감하고, 기혼자는 반드시 합산 신고해야 합니다. 그다음 두 단계 심사가 순서대로 적용됩니다. 첫째 §135(b)(1) 비율: 상환금 12,000달러(원금 9,000 + 이자 3,000)에 비용이 9,000달러이면 비율은 75%이고, 제외 후보 이자는 3,000 × 75% = 2,250달러, 과세 이자는 750달러입니다(두 번 재계산). 둘째 §135(b)(2) MAGI 단계 축소: 2026년 구간은 독신·세대주 101,800–116,800달러, 합산 152,650–182,650달러입니다(Rev. Proc. 2025-32; 2025년은 99,500–114,500과 149,250–179,250, Rev. Proc. 2024-40). 합산 MAGI 167,650달러는 폭 30,000달러 구간에 15,000달러 들어간 지점이라 50% 삭감되어 제외액은 2,250 × 50% = 1,125달러, 과세 이자는 1,875달러가 됩니다. 주 차원에서는 31 U.S.C. §3124로 이자가 이미 면세이므로 §135는 연방 신고에서만 의미가 있고, 캘리포니아도 이 이자에는 과세하지 않습니다. *개인 학습 노트이며 세무 자문이 아닙니다.*

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính / 初译待校)

Lãi trái phiếu tiết kiệm Series EE và Series I chịu thuế liên bang, thường được hoãn đến năm chuộc lại. IRC §135 cho phép loại trừ một phần hoặc toàn bộ khoản lãi đó trong năm chuộc lại nếu tiền được dùng để trả chi phí giáo dục đại học đủ điều kiện trong cùng năm, khai trên Mẫu 8815. Chỉ lãi mới được loại trừ, tiền gốc không bao giờ là thu nhập. Trái phiếu đủ điều kiện phải phát hành sau ngày 31 tháng 12 năm 1989 và người mua phải đủ 24 tuổi trước ngày phát hành, nên trái phiếu mua đứng tên trẻ nhỏ không đạt. Chi phí đủ điều kiện chỉ gồm học phí và lệ phí — không gồm ăn ở hay sách vở — cho người nộp thuế, vợ/chồng hoặc người phụ thuộc tại một cơ sở đủ điều kiện, và khoản đóng góp vào chương trình §529 hoặc tài khoản Coverdell §530 cũng được tính; chi phí phải trừ đi hỗ trợ giáo dục miễn thuế và số tiền đã dùng cho các ưu đãi giáo dục khác. Người đã kết hôn phải khai chung. Sau đó áp dụng hai bộ lọc theo thứ tự. Thứ nhất, tỷ lệ §135(b)(1): tiền chuộc 12.000 đô la (gốc 9.000 cộng lãi 3.000) so với chi phí 9.000 đô la cho tỷ lệ 75%, nên lãi ứng viên loại trừ là 3.000 × 75% = 2.250 đô la và 750 đô la vẫn chịu thuế (đã tính lại hai lần). Thứ hai, giảm dần theo MAGI §135(b)(2): năm 2026 khoảng là 101.800–116.800 đô la cho người độc thân và chủ hộ, 152.650–182.650 đô la cho khai chung (Rev. Proc. 2025-32; năm 2025 là 99.500–114.500 và 149.250–179.250, Rev. Proc. 2024-40). MAGI khai chung 167.650 đô la nằm sâu 15.000 đô la trong dải rộng 30.000 đô la, tức cắt 50%, còn lại 2.250 × 50% = 1.125 đô la được loại trừ và 1.875 đô la chịu thuế. Ở cấp bang, khoản lãi này vốn đã được miễn theo 31 U.S.C. §3124, nên §135 chỉ có ý nghĩa ở tờ khai liên bang và California cũng không đánh thuế khoản lãi này trong mọi trường hợp. *Ghi chú học tập cá nhân, không phải tư vấn thuế.*

## हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित / 初译待校)

Series EE और Series I बचत बॉन्ड का ब्याज संघीय कर के अधीन है, सामान्यतः मोचन वर्ष तक स्थगित रहता है। IRC §135 उस वर्ष में उस ब्याज का कुछ या पूरा भाग बाहर करने देता है जब मोचन राशि उसी वर्ष योग्य उच्च-शिक्षा व्यय में लगे, दावा Form 8815 पर होता है। केवल ब्याज बाहर होता है, मूलधन कभी आय नहीं है। योग्य बॉन्ड 31 दिसंबर 1989 के बाद जारी होना चाहिए और क्रेता जारी-तिथि से पहले 24 वर्ष का हो चुका हो, इसलिए छोटे बच्चे के नाम खरीदे बॉन्ड अयोग्य हैं। योग्य व्यय केवल tuition और fees हैं — आवास, भोजन या पुस्तकें नहीं — करदाता, जीवनसाथी या आश्रित के लिए पात्र संस्थान में, और §529 योजना या §530 Coverdell ESA में योगदान भी गिना जाता है; व्यय से कर-मुक्त शिक्षा सहायता और अन्य शिक्षा लाभों में प्रयुक्त राशि घटती है। विवाहित व्यक्ति को संयुक्त रिटर्न ही दाखिल करना होगा। फिर दो छलनियाँ क्रम से लगती हैं। पहली, §135(b)(1) का अनुपात: मोचन राशि $12,000 (मूलधन $9,000 + ब्याज $3,000) और व्यय $9,000 हो तो अनुपात 75% है, अतः बाहर होने योग्य ब्याज 3,000 × 75% = $2,250 और $750 करयोग्य रहता है (दो बार पुनर्गणना की गई)। दूसरी, §135(b)(2) की MAGI चरणबद्ध कटौती: 2026 के लिए श्रेणी एकल व household प्रमुख हेतु $101,800–$116,800 और संयुक्त हेतु $152,650–$182,650 है (Rev. Proc. 2025-32; 2025 में $99,500–$114,500 और $149,250–$179,250 थी, Rev. Proc. 2024-40)। संयुक्त MAGI $167,650, $30,000 चौड़ी पट्टी में $15,000 अंदर है, अर्थात 50% कटौती, शेष बाहर राशि 2,250 × 50% = $1,125 और करयोग्य ब्याज $1,875। राज्य स्तर पर यह ब्याज 31 U.S.C. §3124 के तहत पहले से मुक्त है, अतः §135 केवल संघीय रिटर्न में मायने रखता है और California भी इस ब्याज पर किसी भी स्थिति में कर नहीं लगाता। *व्यक्तिगत अध्ययन नोट; कर सलाह नहीं।*
