# 信托能当 S 公司股东吗：IRC §1361 的 QSST 与 ESBT、选举与计税及加州口径

> 个人学习笔记，不构成税务建议。选举期限与表格落点以当年 Reg. §1.1361-1 与 Form 1120-S、Form 2553 说明为准。

## 中文主文

### 一、先看门：S 公司股东名单是封闭的

第 1361(b)(1) 条把 S 公司的股东资格写成封闭名单：股东总数不超过 100 人（§1361(b)(1)(A)）、只能有一类股票（§1361(b)(1)(D)）、个人股东只能是美国公民或居民外国人、非居民外国人不行，公司与合伙原则上不能当股东，信托只有落进 §1361(c)(2)、(d)、(e) 列举的类型才行。股票一旦落到不合格持有人手里，S 选举在转让当日终止（§1362(d)(2) 的终止时点），公司从那天起按 C 公司课税；确属无意终止的，可走 §1362(f) 向 IRS 申请救济，但那是补救，不是规划。把股票放进信托之前先对名单，是这篇的出发点。

过渡性的合格信托先记三种：授予人信托（grantor trust，授予人在世时由授予人本人视为股东，§1361(c)(2)(A)(i)）；授予人去世后可再延续 2 年（§1361(c)(2)(A)(ii)）；遗嘱信托（testamentary trust）自股票转入起 2 年（§1361(c)(2)(A)(iii)）。2 年是窗口，不是长期答案，窗口内要么把股票分给合格个人，要么转成下面两种长期结构。

### 二、QSST：一个수익人、收入全分、수익人自己选举

合格 S 章信托（Qualified Subchapter S Trust, QSST）出自 §1361(d)，条件是信托条款层面的硬约束：信托存续期内同一时点只能有 1 名收入수익人，且该수익人是美国公民或居民；信托全部收入必须当期分给（或要求分给）该수익人；수익人在世期间，本金只能分给该수익人一人；수익人的收入权益在其死亡或信托终止时先到者结束；信托若在수익人在世期间终止，全部资产归该수익人。税性上，수익人就 S 股票部分被视为股东（§1361(d)(1)）：K-1 穿透项目进수익人个人税表，按수익人自己的档位计税，信托这一层不截留。

选举由수익人本人（不是受托人）作出，就每一家 S 公司分别选，一般须在股票转入信托后 2 个月 15 天内提交（Reg. §1.1361-1(j) 的期限口径）。수익人换人时，新수익人要重新选，老选举不自动跟人走，这是 QSST 最常见的漏项。

### 三、ESBT：多人수익、可以不分、信托层按最高档交税

可选小型企业信托（Electing Small Business Trust, ESBT）出自 §1361(e)：수익人可以多人，收入不必当期分配，灵活性换来两个代价。其一是资格面：全部수익人只能是个人、遗产或 §170(c) 类慈善组织等合格主体；任何信托权益不得以购买方式取得（no interest acquired by purchase）；部分信托类型被明确挡在门外（如慈善剩余信托不得作 ESBT）。其二是人数面：ESBT 的每一名潜在现行수익人（potential current beneficiary）都按一名股东计数（§1361(e)(2)），大家族信托很容易把 100 人上限顶穿。

选举由受托人作出（与 QSST 正好相反），一般同样在生效后 2 个月 15 天内提交。计税走 §641(c)：S 部分在信托层面单独计算、按最高边际税率课税（普通所得部分按现行个人最高档 37% 示意），수익人不就 S 部分再拿 K-1 报一遍。同一笔 S 收入，QSST 跟着수익人档位走、ESBT 直接顶格，这是两种结构最要紧的价差。

**算例一（本地两遍复算）。** 信托持有 S 股票，当年 S 收入 80,000 美元。走 QSST、수익人示意边际税率 22%：税额 ＝ 80,000 × 22% ＝ 17,600 美元（复算：80,000 × 0.22 ＝ 17,600，一致）。走 ESBT、按 §641(c) 最高档 37% 示意：税额 ＝ 80,000 × 37% ＝ 29,600 美元（复算：80,000 × 0.37 ＝ 29,600，一致）。年差 ＝ 29,600 − 17,600 ＝ 12,000 美元。数字是示意（未计 NIIT 与档位叠加），结构价差是真的：수익人档位越低、收入越大，QSST 的优势越明显；수익人多、又要累积收入时，才轮到 ESBT 用灵活性换税率。

**算例二（人数计数，本地两遍复算）。** 某 S 公司已有其他股东 97 人，拟由一名下有 4 名潜在现行수익人的 ESBT 入股：计数 ＝ 97 ＋ 4 ＝ 101 人（复算：97 ＋ 4 ＝ 101，一致），超过 §1361(b)(1)(A) 的 100 人上限，这个结构下 S 资格过不了关（本例未计 §1361(c)(1) 家族归属合并计数的特殊口径，个案须另核）。同一信托若只有 2 名潜在现行수익人，计数 ＝ 97 ＋ 2 ＝ 99 人，未越线。

### 四、怎么选：一张对照表看完

수익人只有一人、收入本来就要年年分掉的，QSST 简单且税率跟着人走；수익人多人、需要累积收入或把慈善主体放进수익名单的，只能往 ESBT 走，并把最高档税率与人数计数先算进成本。两条路共同的纪律是：信托文件先按目标类型的条款要件起草（文件不合格，选举救不了），选举按主体（수익人对受托人）和期限（2 个月 15 天）双核，授予人或遗嘱信托的 2 年窗口在日历上单独设线，不要等窗口快关才发现文件还没改。

### 五、加州口径

加州承认 S 公司制度但有自己的选举与申报：加州 S 公司走 Form 100S，实体层按 R&TC §23802 征 1.5% 特许税（最低 800 美元），股东层再就穿透收入按加州口径计税，与联邦的零实体税不同，算结构价差时加州这一层要单列。信托股东的 QSST、ESBT 资格判断大体衔接联邦框架，但加州的同意与申报细节以 FTB 当年说明为准，联邦选举做完不等于加州手续齐全，两边清单分开核。

*声明：个人学习笔记，不构成税务建议。来源：IRC §1361(b)(1)（股东资格与 100 人及一类股票）、§1361(c)(1)–(2)（家族计数与过渡信托及 2 年窗口）、§1361(d)（QSST）、§1361(e)（ESBT 与수익人计数）、§641(c)（ESBT 的 S 部分计税）、§1362(d)(2) 与 (f)（终止与无意终止救济）；Treas. Reg. §1.1361-1（选举主体与期限）；加州 R&TC §23802 与 Form 100S 说明。*

---

## English

An S corporation may only have the shareholders §1361(b)(1) allows: no more than 100 shareholders, one class of stock, individuals who are U.S. citizens or resident aliens (never nonresident aliens), estates, and only the trusts the statute lists. Stock reaching an ineligible holder terminates the S election on the transfer date under §1362(d)(2), with §1362(f) inadvertent-termination relief as a remedy rather than a plan. Grantor trusts qualify while the grantor lives, and grantor and testamentary trusts each get only a two-year window after death or transfer under §1361(c)(2)(A). The two permanent structures differ sharply. A QSST under §1361(d) may have only one income beneficiary at a time, a U.S. citizen or resident, must distribute all income currently to that beneficiary, may distribute corpus to no one else during the beneficiary's life, and the beneficiary — treated as the shareholder for the S stock — makes a separate election for each corporation, generally within two months and 15 days of the transfer; the beneficiary reports the pass-through income at personal rates. An ESBT under §1361(e) may have several beneficiaries and need not distribute, but every beneficiary must be an eligible individual, estate, or §170(c)-type organization, no interest may have been acquired by purchase, the trustee (not a beneficiary) elects, each potential current beneficiary counts as a shareholder under §1361(e)(2), and the S portion is taxed at the trust level under §641(c) at the highest marginal rate. Worked examples (recomputed twice): on $80,000 of S income, a QSST beneficiary at an illustrative 22% pays $80,000 × 22% = $17,600, while an ESBT at the illustrative 37% top rate pays $80,000 × 37% = $29,600, a $12,000 yearly gap; and a corporation with 97 other shareholders plus an ESBT with 4 potential current beneficiaries counts 97 + 4 = 101 shareholders, over the 100 limit. California runs its own S regime: Form 100S and a 1.5% entity-level franchise tax (minimum $800) under R&TC §23802, with trust-shareholder qualification broadly following the federal framework but its own consent and filing details. *Personal study notes only; not tax advice.*

## Español (traducción de estudio, pendiente de revisión nativa)

Una corporación S solo puede tener los accionistas que permite el §1361(b)(1): máximo 100 accionistas, una sola clase de acciones, personas físicas ciudadanas o residentes de EE. UU. (nunca extranjeros no residentes), patrimonios hereditarios y únicamente los fideicomisos que enumera la ley. Si las acciones llegan a un titular no elegible, la elección S termina en la fecha de la transferencia según el §1362(d)(2), y el alivio por terminación involuntaria del §1362(f) es un remedio, no un plan. Los fideicomisos del otorgante califican en vida de este, y tanto estos como los fideicomisos testamentarios tienen solo una ventana de dos años tras la muerte o la transferencia, §1361(c)(2)(A). Las dos estructuras permanentes difieren mucho. Un QSST, §1361(d), solo puede tener un beneficiario de ingresos a la vez, ciudadano o residente, debe distribuirle actualmente todo el ingreso, no puede distribuir capital a nadie más en vida del beneficiario, y es el beneficiario —tratado como accionista respecto de las acciones S— quien hace una elección separada por cada corporación, en general dentro de los dos meses y 15 días de la transferencia; el beneficiario declara el ingreso trasladado a sus tipos personales. Un ESBT, §1361(e), puede tener varios beneficiarios y no está obligado a distribuir, pero cada beneficiario debe ser una persona física, un patrimonio o una organización tipo §170(c) elegible, ningún interés puede haberse adquirido por compra, elige el fiduciario (no un beneficiario), cada beneficiario actual potencial cuenta como un accionista según el §1361(e)(2), y la parte S tributa en el fideicomiso según el §641(c) al tipo marginal máximo. Ejemplos (recalculados dos veces): con $80.000 de ingreso S, un beneficiario de QSST a un tipo ilustrativo del 22% paga 80.000 × 22% = $17.600, mientras un ESBT al tipo máximo ilustrativo del 37% paga 80.000 × 37% = $29.600, una diferencia anual de $12.000; y una corporación con otros 97 accionistas más un ESBT con 4 beneficiarios actuales potenciales suma 97 + 4 = 101 accionistas, por encima del límite de 100. California tiene su propio régimen S: Formulario 100S y un impuesto de franquicia del 1,5% a nivel de entidad (mínimo $800) según R&TC §23802, con una calificación de fideicomisos accionistas que en general sigue el marco federal pero con consentimientos y trámites propios. *Notas personales de estudio; no constituye asesoramiento fiscal.*

## 한국어 (초역, 원어민 감수 대기 / 初译待校)

S 법인의 주주는 §1361(b)(1)이 허용하는 자로 한정됩니다. 주주 100명 이하, 주식은 한 종류만, 개인은 미국 시민 또는 거주 외국인(비거주 외국인은 불가), 유산재단, 그리고 법이 열거한 신탁만 가능합니다. 부적격 보유자에게 주식이 넘어가면 §1362(d)(2)에 따라 이전일에 S 선택이 종료되고, §1362(f)의 비의도 종료 구제는 계획이 아니라 구제책입니다. 위탁자 신탁(grantor trust)은 위탁자 생존 시 자격이 있고, 위탁자 신탁과 유언 신탁은 사망 또는 이전 후 2년의 유예만 받습니다(§1361(c)(2)(A)). 상설 구조 두 가지는 성격이 크게 다릅니다. QSST(§1361(d))는 소득수익자가 한 번에 한 명뿐이고 미국 시민 또는 거주자여야 하며, 모든 소득을 그수익자에게 당기 분배해야 하고,수익자 생존 중 원금은 그수익자에게만 분배할 수 있습니다. 선거는 수탁자가 아니라수익자 본인이 법인마다 따로 하며, 일반적으로 이전 후 2개월 15일 이내에 해야 하고, 통과 소득은수익자 개인 세율로 신고합니다. ESBT(§1361(e))는수익자가 여럿이어도 되고 분배 의무가 없지만, 모든수익자가 적격 개인·유산재단·§170(c)형 조직이어야 하고, 어떤 지분도 구매로 취득해서는 안 되며, 선거는 수탁자가 하고, 잠재적 현수익자 전원이 주주 1명으로 각각 셈해지며(§1361(e)(2)), S 부분은 §641(c)에 따라 신탁 층위에서 최고 한계세율로 과세됩니다. 예시(두 번 재계산): S 소득 80,000달러에서 예시 세율 22%의 QSST수익자는 80,000 × 22% = 17,600달러, 예시 최고세율 37%의 ESBT는 80,000 × 37% = 29,600달러를 내어 연 12,000달러 차이가 납니다. 또 다른 주주 97명에 잠재적 현수익자 4명인 ESBT가 들어오면 97 + 4 = 101명으로 100명 한도를 넘습니다. 캘리포니아는 자체 S 제도를 운영합니다. Form 100S와 R&TC §23802에 따른 실체 층위 1.5% franchise tax(최저 800달러)가 있고, 신탁 주주 자격은 대체로 연방 틀을 따르되 동의와 신고 세부 사항은 별도입니다. *개인 학습 노트이며 세무 자문이 아닙니다.*

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính / 初译待校)

Công ty S chỉ được có các cổ đông mà §1361(b)(1) cho phép: tối đa 100 cổ đông, một loại cổ phần duy nhất, cá nhân là công dân hoặc người nước ngoài cư trú tại Hoa Kỳ (không bao giờ là người nước ngoài không cư trú), di sản, và chỉ những quỹ tín thác mà luật liệt kê. Cổ phần rơi vào tay người nắm giữ không đủ điều kiện sẽ làm chấm dứt lựa chọn S ngay ngày chuyển nhượng theo §1362(d)(2), và cứu trợ chấm dứt vô ý §1362(f) là biện pháp khắc phục chứ không phải kế hoạch. Quỹ tín thác của người lập (grantor trust) đủ điều kiện khi người lập còn sống, và cả quỹ grantor lẫn quỹ theo di chúc chỉ có cửa sổ hai năm sau khi qua đời hoặc chuyển nhượng theo §1361(c)(2)(A). Hai cấu trúc lâu dài khác nhau rõ rệt. QSST theo §1361(d) chỉ được có một người hưởng thu nhập tại một thời điểm, là công dân hoặc cư trú nhân Hoa Kỳ, phải phân phối toàn bộ thu nhập hiện hành cho người đó, không được phân phối vốn cho ai khác khi người đó còn sống, và chính người hưởng — được coi là cổ đông đối với cổ phần S — thực hiện lựa chọn riêng cho từng công ty, thường trong vòng hai tháng 15 ngày kể từ ngày chuyển nhượng; người hưởng khai thu nhập xuyên suốt theo thuế suất cá nhân. ESBT theo §1361(e) có thể có nhiều người hưởng và không bắt buộc phân phối, nhưng mọi người hưởng phải là cá nhân, di sản hoặc tổ chức kiểu §170(c) đủ điều kiện, không phần quyền nào được mua mà có, người được ủy thác (không phải người hưởng) thực hiện lựa chọn, mỗi người hưởng hiện tại tiềm năng được tính là một cổ đông theo §1361(e)(2), và phần S bị đánh thuế ở cấp quỹ theo §641(c) ở mức thuế suất biên cao nhất. Ví dụ (đã tính lại hai lần): với 80.000 đô la thu nhập S, người hưởng QSST ở mức minh họa 22% nộp 80.000 × 22% = 17.600 đô la, trong khi ESBT ở mức cao nhất minh họa 37% nộp 80.000 × 37% = 29.600 đô la, chênh 12.000 đô la mỗi năm; và một công ty có 97 cổ đông khác cộng một ESBT có 4 người hưởng hiện tại tiềm năng sẽ đếm thành 97 + 4 = 101 cổ đông, vượt giới hạn 100. California có chế độ S riêng: Mẫu 100S và thuế franchise 1,5% ở cấp thực thể (tối thiểu 800 đô la) theo R&TC §23802, tư cách quỹ tín thác cổ đông nhìn chung theo khung liên bang nhưng có chi tiết đồng ý và nộp hồ sơ riêng. *Ghi chú học tập cá nhân, không phải tư vấn thuế.*

## हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित / 初译待校)

S corporation के शेयरधारक केवल वे हो सकते हैं जिन्हें §1361(b)(1) अनुमति देता है: अधिकतम 100 शेयरधारक, stock की एक ही श्रेणी, व्यक्ति अमेरिकी नागरिक या निवासी विदेशी (अनिवासी विदेशी कभी नहीं), संपदाएँ (estates), और केवल वे trusts जो कानून सूचीबद्ध करता है। अयोग्य धारक के पास stock पहुँचते ही §1362(d)(2) के तहत हस्तांतरण तिथि को S चुनाव समाप्त हो जाता है, और §1362(f) की अनजाने समाप्ति राहत योजना नहीं, उपाय है। Grantor trust अनुदाता के जीवनकाल में योग्य है, और grantor व testamentary trusts को मृत्यु या हस्तांतरण के बाद केवल दो वर्ष की खिड़की मिलती है, §1361(c)(2)(A)। दो स्थायी संरचनाएँ बहुत भिन्न हैं। QSST, §1361(d), में एक समय में केवल एक आय-लाभार्थी हो सकता है, जो अमेरिकी नागरिक या निवासी हो, सारी आय उसी को वर्तमान में वितरित होनी चाहिए, लाभार्थी के जीवनकाल में मूलधन किसी और को नहीं जा सकता, और चुनाव लाभार्थी स्वयं — जिसे S stock के लिए शेयरधारक माना जाता है — प्रत्येक corporation के लिए अलग से करता है, सामान्यतः हस्तांतरण के दो माह 15 दिन के भीतर; पास-थ्रू आय लाभार्थी अपनी व्यक्तिगत दरों पर घोषित करता है। ESBT, §1361(e), में कई लाभार्थी हो सकते हैं और वितरण अनिवार्य नहीं, परंतु हर लाभार्थी पात्र व्यक्ति, संपदा या §170(c) प्रकार का संगठन होना चाहिए, कोई हित खरीदकर प्राप्त नहीं होना चाहिए, चुनाव trustee करता है (लाभार्थी नहीं), प्रत्येक संभावित वर्तमान लाभार्थी §1361(e)(2) के तहत एक शेयरधारक गिना जाता है, और S भाग पर §641(c) के तहत trust स्तर पर उच्चतम सीमांत दर से कर लगता है। उदाहरण (दो बार पुनर्गणना): $80,000 S आय पर उदाहरणात्मक 22% वाला QSST लाभार्थी 80,000 × 22% = $17,600 देता है, जबकि उदाहरणात्मक 37% शीर्ष दर वाला ESBT 80,000 × 37% = $29,600 देता है, वार्षिक अंतर $12,000; और 97 अन्य शेयरधारकों वाली कंपनी में 4 संभावित वर्तमान लाभार्थियों वाला ESBT जुड़े तो गिनती 97 + 4 = 101 होकर 100 की सीमा पार कर जाती है। California का अपना S regime है: Form 100S और R&TC §23802 के तहत इकाई-स्तर पर 1.5% franchise tax (न्यूनतम $800), trust-शेयरधारक योग्यता मोटे तौर पर संघीय ढाँचे का पालन करती है परंतु सहमति व दाखिले के अपने विवरण हैं। *व्यक्तिगत अध्ययन नोट; कर सलाह नहीं।*

## 补译增量（2026-11-08 追加：韩／越／印三语各补 2 项细节增量，与中文主文细节对齐，正文原有段落未改动）

### 한국어 보충 (초역 · 初译待校)

보충 1 (QSST의 종료 규칙과 수익자 교체 시 재선거): QSST 수익자의 소득 지분은 수익자의 사망과 신탁 종료 중 먼저 오는 시점에 끝납니다. 신탁이 수익자 생존 중에 종료되면 신탁 자산 전부가 그 수익자에게 귀속되어야 합니다. 또 수익자가 바뀌면 새 수익자가 직접 다시 선거를 해야 하며, 이전 수익자의 선거는 자동으로 따라오지 않습니다. 이 재선거 누락이 QSST에서 가장 흔한 빠뜨림입니다.

보충 2 (ESBT에서 자선 잔여 신탁 제외와 인원 계산의 두 번째 가지): 자선 잔여 신탁(charitable remainder trust)은 ESBT가 될 수 없도록 명시적으로 막혀 있습니다. 인원 계산 예시의 반대쪽 가지도 확인합니다. 같은 신탁의 잠재적 현수익자가 2명뿐이라면 셈은 97 + 2 = 99명이 되어 100명 상한을 넘지 않으므로 이 지점에서는 자격이 유지됩니다(가족 귀속 합산 같은 특수 셈법은 사안별로 별도 확인이 필요합니다).

### Bổ sung Tiếng Việt (bản dịch sơ bộ · 初译待校)

Bổ sung 1 (quy tắc chấm dứt của QSST và việc bầu chọn lại khi đổi người hưởng): Quyền hưởng thu nhập của người hưởng QSST kết thúc tại thời điểm sớm hơn giữa cái chết của người hưởng và việc chấm dứt quỹ tín thác; nếu quỹ chấm dứt khi người hưởng còn sống, toàn bộ tài sản của quỹ phải thuộc về người hưởng đó. Khi người hưởng thay đổi, người hưởng mới phải tự mình thực hiện một lựa chọn mới — lựa chọn của người hưởng cũ không tự động đi theo — và việc bỏ sót lần bầu chọn lại này là lỗi thường gặp nhất của QSST.

Bổ sung 2 (loại trừ quỹ tín thác phần dư từ thiện khỏi ESBT và nhánh thứ hai của ví dụ đếm người): Quỹ tín thác phần dư từ thiện (charitable remainder trust) bị cấm rõ ràng không được làm ESBT. Cũng cần kiểm nhánh ngược lại của ví dụ đếm cổ đông: nếu cùng quỹ đó chỉ có 2 người hưởng hiện tại tiềm năng, phép đếm là 97 + 2 = 99 người, không vượt trần 100 nên tại điểm này tư cách vẫn giữ được (các cách đếm đặc biệt như gộp theo gia đình vẫn phải kiểm riêng theo từng trường hợp).

### हिन्दी पूरक (प्रारंभिक अनुवाद · 初译待校)

पूरक 1 (QSST के समापन नियम और लाभार्थी बदलने पर पुनः चुनाव): QSST लाभार्थी का आय-अधिकार लाभार्थी की मृत्यु और trust की समाप्ति, जो भी पहले हो, उस पर समाप्त होता है; यदि trust लाभार्थी के जीवनकाल में समाप्त हो तो उसकी सारी संपत्ति उसी लाभार्थी को जानी चाहिए। लाभार्थी बदलने पर नए लाभार्थी को स्वयं नया चुनाव करना होता है — पुराने लाभार्थी का चुनाव स्वतः साथ नहीं चलता — और यही पुनः चुनाव छूट जाना QSST की सबसे आम चूक है।

पूरक 2 (ESBT से charitable remainder trust का बहिष्करण और गिनती-उदाहरण की दूसरी शाखा): Charitable remainder trust को ESBT बनने से स्पष्ट रूप से रोका गया है। गिनती के उदाहरण की दूसरी शाखा भी जाँच लें: यदि उसी trust के संभावित वर्तमान लाभार्थी केवल 2 हों तो गिनती 97 + 2 = 99 होती है, जो 100 की सीमा से नीचे है, इसलिए इस बिंदु पर योग्यता बनी रहती है (परिवार-आरोपण जैसी विशेष गिनती-विधियाँ मामले के अनुसार अलग से जाँचनी होती हैं)।
