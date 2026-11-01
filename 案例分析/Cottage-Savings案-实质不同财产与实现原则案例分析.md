# Cottage Savings 案：实质不同财产与「实现」原则案例分析

> 个人学习笔记，不构成税务或审计建议。法条与判例以现行官方文本为准，考试口径以 AICPA 当期 CPA Exam Blueprint 为准。

## 中文主文

**案名**：Cottage Savings Association v. Commissioner, 499 U.S. 554 (1991)，美国最高法院，1991 年 4 月 17 日判决，Marshall 大法官执笔；下级程序：税务法院准许扣除，第六巡回法院推翻。本案是 REG 里「实现（realization）与确认（recognition）之分」的锚点判例，一句话结论：**交换来的财产只要承载的法律权利在种类或程度上不同，就是 § 1001(a) 意义上的处置，损失即已实现；监管口径的「实质相同」管不了税法口径的「实质不同」。**

### 一、事实：一场监管默许的换仓，两个口径打架

1980 年前后利率飙升，储贷机构（S&L）手里的老抵押贷款市值大跌，账面逼近资不抵债。监管机关联邦住房贷款银行委员会（FHLBB）于 1980 年 6 月 27 日发布 R-49 备忘录开了一道口子：机构之间交换「实质相同」（substantially identical）的抵押贷款，监管账上**不必**确认损失。Cottage Savings 据此与另外四家储贷机构同时做了对等交换：

- 卖出：其在 **252 笔**单户住宅抵押贷款中的 90% 参与权益；
- 买入：对方在 **305 笔**其他抵押贷款中的参与权益；
- 交换双方权益的公允价值各约 **450 万美元**，而 Cottage 交出的权益面值约 **690 万美元**。

Cottage 在 1980 年税表上按交出权益与收回权益价值之间的调整后差额，主张了**超过 240 万美元**的损失扣除。税务局（Commissioner）全额否决。税务法院支持纳税人；第六巡回法院改判：损失虽已「实现」，但依 § 165(a) 并非真实发生的损失（bona fide loss），不得扣除。最高法院受理的正是这两层问题。

### 二、争点与规则：实质不同看法律权利，不看经济像不像

- **实现的总公式**：§ 1001(a) 规定，出售或其他处置财产的利得或损失＝实现额（amount realized）－调整后基数（adjusted basis）；§ 1001(c) 再规定除非本章另有规定，已实现利得或损失应予确认。实现是确认的前提，但两者不是一回事。
- **「处置」的门槛**：Treas. Reg. § 1.1001-1(a) 写明，只有收回的财产与交出的财产「实质不同」（materially different）时，交换才构成实现事件。争点因此收窄为一句话：经济上几乎等值的抵押贷款权益，法律上算不算实质不同？
- **最高法院的定义**：财产是否实质不同，看其持有人享有的**法律权利（legal entitlements）在种类或程度上是否不同**。权利不同，交换双方与税务局就能在交换时点把各自财产相对基数的涨跌固定下来——实现制度的目的（避免逐年估值的行政成本）即告满足，不需要再问经济上像不像。
- **本案适用**：换入与换出的参与权益源于**不同的借款人**、以**不同的住宅**作抵押，法律权利显然不同，损失在交换时点已实现。
- **§ 1031 的反推论证**：如果相似财产交换本来就不构成实现，国会就没有必要在 § 1031 里专门规定同类财产交换的利得损失不予确认——§ 1031 的存在本身证明一般交换先有实现、再谈不确认。
- **§ 165 这层**：法院认定损失是真实的——基数实实在在高于收回价值，纳税人换仓后承担的是另一组借款人的信用风险；第六巡回以「非真实损失」否决扣除的路径不成立。监管的 R-49「实质相同」只是监管会计的处理许可，与税法的实现判断各管一段。

### 三、算例：与案中数字同构的一道题

设某机构持有参与权益，调整后基数 6,900,000 美元，与同业交换取得另一组贷款参与权益，公允价值 4,500,000 美元：

- 实现额＝4,500,000；调整后基数＝6,900,000；
- 已实现损失＝4,500,000 − 6,900,000＝**−2,400,000 美元**（§ 1001(a)）；
- 因交换标的源于不同借款人与不同抵押物，构成实质不同，损失已实现；无 § 1031 等不确认条款适用时，依 § 1001(c) 当年确认。

反向练习：若只是把**同一借款人、同一抵押物**的权益在账面上换个持有形式，法律权利没有任何变化，则非实质不同、不构成处置，浮亏继续潜伏在基数里——这一正一反就是考试的判断式。

### 四、今天怎么用（备考与实务接口）

- **实现≠确认的完整地图**：先 § 1001 判实现，再找不确认条款——§ 1031（2017 年 TCJA 修法后仅限不动产）、§ 1033 非自愿转换、§ 1041 配偶间转移、§ 1091 洗售（30 天窗口内买入实质相同证券，损失不认但计入替代股份基数）；顺序反了必错。
- **债务修改的规章化**：本案之后，Treas. Reg. § 1.1001-3 把判断落到债务工具上——收益率变动超过规定门槛、义务人或担保发生变更等「重大修改」（significant modification）视为旧债被交换为新债，产生实现事件，业内直接称之为 Cottage Savings 条例。
- **数字资产接口**：IRS 以 Notice 2014-21 把虚拟货币定性为财产；2018 年以后 § 1031 仅适用于不动产，币币交换不再有同类交换的不确认待遇，每一次交换都按 § 1001 用公允价值算实现损益——推理结构正是本案：换回的是法律与经济权利不同的另一种财产。
- **与 Thor Power 的对照**：Thor Power（439 U.S. 522）管的是「数字能不能撑起扣除」，要的是客观证据；Cottage Savings 管的是「时点到没到」，要的是法律权利是否换了对象。两案合起来才是 REG 里损失类题目的完整判断链。

## English

*Cottage Savings Association v. Commissioner*, 499 U.S. 554 (1991) (Marshall, J.; decided April 17, 1991), is the anchor case for the realization/recognition split in REG. During the savings-and-loan crisis, the FHLBB's Memorandum R-49 (June 27, 1980) let institutions swap "substantially identical" mortgages without reporting losses for regulatory purposes. Cottage Savings simultaneously sold 90% participation interests in 252 mortgages to four other S&Ls and bought interests in 305 different mortgages; each side's package had a fair market value of about $4.5 million, while the interests Cottage surrendered had a face value of about $6.9 million. On its 1980 return it claimed a loss deduction of over $2.4 million. The Tax Court allowed it; the Sixth Circuit reversed, reasoning that the loss, though realized, was not a bona fide loss under §165(a). The Supreme Court reversed again. Under §1001(a), gain or loss equals the amount realized minus adjusted basis, and under Treas. Reg. §1.1001-1(a) an exchange is a realization event only if the properties are materially different. The Court defined that term legally, not economically: properties are materially different when their possessors enjoy legal entitlements different in kind or extent. Because the swapped interests rested on different obligors and different homes, the loss was realized at the exchange — and the very existence of §1031's nonrecognition rule for like-kind exchanges confirms that ordinary exchanges realize gain or loss first. Worked example mirroring the case: basis $6,900,000, amount realized $4,500,000, realized loss $2,400,000, recognized under §1001(c) absent a nonrecognition provision. The doctrine lives on in the "Cottage Savings regulations," Treas. Reg. §1.1001-3 (a significant modification of a debt instrument is a deemed exchange), in post-TCJA §1031 (real property only, so crypto-for-crypto swaps are taxable realization events for property under Notice 2014-21), and in the standard exam sequence: §1001 realization first, then §§1031, 1033, 1041 and 1091 nonrecognition or deferral. *Personal study notes only; not tax advice.*

## Español (traducción de estudio, pendiente de revisión nativa)

*Cottage Savings Association v. Commissioner*, 499 U.S. 554 (1991) (opinión de Marshall; 17 de abril de 1991) es el caso central sobre la distinción entre realización y reconocimiento en REG. En plena crisis de las cajas de ahorro, el Memorándum R-49 de la FHLBB (27 de junio de 1980) permitía intercambiar hipotecas «sustancialmente idénticas» sin reconocer pérdidas a efectos regulatorios. Cottage Savings vendió participaciones del 90% en 252 hipotecas a otras cuatro instituciones y compró participaciones en 305 hipotecas distintas; cada paquete valía en el mercado unos 4,5 millones de dólares, mientras que lo entregado tenía un valor nominal de unos 6,9 millones. En su declaración de 1980 reclamó una pérdida de más de 2,4 millones. El Tax Court la admitió; el Sexto Circuito la rechazó por no ser una pérdida auténtica bajo el §165(a); la Corte Suprema revocó. Según el §1001(a), la ganancia o pérdida es el importe realizado menos la base ajustada, y el Reg. §1.1001-1(a) exige que los bienes intercambiados sean «materialmente diferentes» para que haya realización. La Corte lo definió en términos jurídicos, no económicos: hay diferencia material cuando los derechos legales (legal entitlements) difieren en clase o alcance. Como las participaciones provenían de deudores distintos y de viviendas distintas, la pérdida se realizó en el intercambio; la propia existencia del §1031 confirma que el intercambio ordinario primero realiza y solo después puede no reconocer. Ejemplo con las cifras del caso: base 6.900.000 − importe realizado 4.500.000 = pérdida realizada de 2.400.000, reconocida por el §1001(c) si no aplica una norma de no reconocimiento. La doctrina continúa en el Reg. §1.1001-3 (la modificación significativa de una deuda equivale a un intercambio), en el §1031 tras la TCJA (solo inmuebles, por lo que el intercambio entre criptoactivos es un hecho imponible según el Notice 2014-21) y en la secuencia de examen: primero realización (§1001), después no reconocimiento (§§1031, 1033, 1041 y 1091). *Notas personales de estudio; no constituyen asesoría fiscal.*

## 한국어 (초역, 교정 대기)

*Cottage Savings Association v. Commissioner*, 499 U.S. 554 (1991)(Marshall 대법관, 1991년 4월 17일 판결)는 REG에서 실현(realization)과 인식(recognition)의 구분을 세운 기준 판례입니다. 저축대부 위기 당시 FHLBB의 R-49 메모(1980년 6월 27일)는 «실질적으로 동일한» 모기지를 교환해도 규제 회계상 손실을 보고하지 않도록 허용했습니다. Cottage Savings는 252개 모기지의 90% 참여 지분을 다른 네 기관에 팔고 305개 다른 모기지의 지분을 샀습니다. 양쪽 패키지의 공정시장가치는 각각 약 450만 달러였고, 양도한 지분의 액면가는 약 690만 달러였습니다. 1980년 신고에서 240만 달러가 넘는 손실 공제를 주장했고, 조세법원은 허용했으나 제6순회법원은 §165(a)의 진정한 손실이 아니라고 뒤집었고, 연방대법원이 다시 번복했습니다. §1001(a)에서 손익은 실현액에서 조정 기초가액을 뺀 금액이고, Reg. §1.1001-1(a)는 교환 재산이 «실질적으로 다를(materially different)» 때만 실현 사건이 된다고 봅니다. 법원은 이를 경제적이 아닌 법적 기준으로 정의했습니다. 보유자의 법적 권리가 종류나 범위에서 다르면 실질적으로 다른 재산입니다. 채무자와 담보 주택이 모두 달랐으므로 손실은 교환 시점에 실현되었고, §1031의 불인식 규정이 존재한다는 자체가 일반 교환에서는 먼저 실현이 일어남을 보여줍니다. 판례 숫자를 그대로 쓴 예시: 기초가액 6,900,000 − 실현액 4,500,000 = 실현 손실 2,400,000달러이며, 불인식 규정이 없으면 §1001(c)에 따라 그 해에 인식합니다. 이 법리는 Reg. §1.1001-3(채무의 중대한 변경은 교환으로 간주), TCJA 이후 부동산으로 한정된 §1031(따라서 암호자산 간 교환은 Notice 2014-21의 재산 개념 아래 과세되는 실현 사건), 그리고 «§1001 실현 먼저, §§1031·1033·1041·1091 불인식은 그다음»이라는 시험 순서로 이어집니다. *개인 학습 노트이며 세무 자문이 아닙니다.*

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

*Cottage Savings Association v. Commissioner*, 499 U.S. 554 (1991) (Thẩm phán Marshall, phán quyết ngày 17 tháng 4 năm 1991) là án lệ neo cho sự phân biệt giữa thực hiện (realization) và ghi nhận (recognition) trong REG. Trong khủng hoảng tiết kiệm-vay, Bản ghi nhớ R-49 của FHLBB (27 tháng 6 năm 1980) cho phép hoán đổi các khoản thế chấp «về cơ bản giống hệt nhau» mà không phải báo cáo lỗ cho mục đích quản lý. Cottage Savings đồng thời bán 90% quyền tham gia trong 252 khoản thế chấp cho bốn tổ chức khác và mua quyền tham gia trong 305 khoản thế chấp khác; mỗi gói có giá trị thị trường khoảng 4,5 triệu đô la, trong khi phần nhường đi có mệnh giá khoảng 6,9 triệu. Trong tờ khai năm 1980, tổ chức này khấu trừ khoản lỗ hơn 2,4 triệu đô la. Tòa Thuế vụ cho phép; Tòa Phúc thẩm Khu vực 6 bác bỏ vì cho rằng khoản lỗ không phải lỗ thật theo §165(a); Tòa Tối cao lật lại. Theo §1001(a), lãi hoặc lỗ bằng số tiền thực hiện trừ cơ sở đã điều chỉnh, và Reg. §1.1001-1(a) đòi hỏi tài sản trao đổi phải «khác biệt trọng yếu» (materially different) mới có sự kiện thực hiện. Tòa định nghĩa theo pháp lý chứ không theo kinh tế: tài sản khác biệt trọng yếu khi quyền pháp lý của người nắm giữ khác nhau về loại hoặc mức độ. Vì các quyền tham gia gắn với những người vay khác nhau và những căn nhà khác nhau, khoản lỗ đã thực hiện ngay tại thời điểm trao đổi; chính sự tồn tại của quy tắc không ghi nhận trong §1031 chứng tỏ trao đổi thông thường trước hết là thực hiện. Ví dụ dùng đúng số của vụ án: cơ sở 6.900.000 − số tiền thực hiện 4.500.000 = lỗ đã thực hiện 2.400.000, được ghi nhận theo §1001(c) nếu không có điều khoản không ghi nhận nào áp dụng. Học thuyết này tiếp nối trong Reg. §1.1001-3 (sửa đổi trọng yếu của công cụ nợ được coi là trao đổi), trong §1031 sau TCJA (chỉ còn bất động sản, nên hoán đổi tiền mã hóa là sự kiện thực hiện chịu thuế theo Notice 2014-21), và trong trình tự làm bài thi: §1001 xét thực hiện trước, §§1031, 1033, 1041 và 1091 xét không ghi nhận sau. *Ghi chú học tập cá nhân; không phải tư vấn thuế.*

## हिन्दी (प्रारंभिक अनुवाद, समीक्षा लंबित)

*Cottage Savings Association v. Commissioner*, 499 U.S. 554 (1991) (न्यायमूर्ति Marshall; 17 अप्रैल 1991) REG में वसूली (realization) और मान्यता (recognition) के भेद का आधार-प्रकरण है। बचत-ऋण संकट के दौरान FHLBB के ज्ञापन R-49 (27 जून 1980) ने «मूलतः समान» बंधकों के आदान-प्रदान पर नियामक लेखांकन में हानि न दिखाने की छूट दी। Cottage Savings ने 252 बंधकों में 90% भागीदारी हित चार अन्य संस्थाओं को बेचे और 305 भिन्न बंधकों में हित खरीदे; प्रत्येक पक्ष के पैकेज का उचित बाज़ार मूल्य लगभग $4.5 मिलियन था, जबकि छोड़े गए हितों का अंकित मूल्य लगभग $6.9 मिलियन था। 1980 के रिटर्न में उसने $2.4 मिलियन से अधिक की हानि कटौती माँगी। कर न्यायालय ने स्वीकार किया; छठे सर्किट ने §165(a) के तहत वास्तविक हानि न मानकर उलट दिया; सर्वोच्च न्यायालय ने फिर पलट दिया। §1001(a) के अनुसार लाभ या हानि = प्राप्त राशि − समायोजित आधार, और Reg. §1.1001-1(a) कहता है कि विनिमय तभी वसूली घटना है जब संपत्तियाँ «सारभूत रूप से भिन्न» (materially different) हों। न्यायालय ने इसे आर्थिक नहीं, कानूनी कसौटी दी: जब धारकों के कानूनी अधिकार (legal entitlements) प्रकार या सीमा में भिन्न हों, संपत्तियाँ सारभूत रूप से भिन्न हैं। चूँकि हित भिन्न ऋणियों और भिन्न घरों से जुड़े थे, हानि विनिमय के क्षण ही वसूल हो गई; §1031 के अमान्यता नियम का अस्तित्व ही दिखाता है कि सामान्य विनिमय में पहले वसूली होती है। प्रकरण के ही अंकड़ों वाला उदाहरण: आधार $6,900,000 − प्राप्त राशि $4,500,000 = वसूल हानि $2,400,000, जो अमान्यता प्रावधान न लगे तो §1001(c) से उसी वर्ष मान्य होगी। यह सिद्धांत Reg. §1.1001-3 (ऋण साधन का महत्वपूर्ण परिवर्तन काल्पनिक विनिमय), TCJA के बाद केवल अचल संपत्ति तक सीमित §1031 (अतः क्रिप्टो-से-क्रिप्टो विनिमय Notice 2014-21 के तहत करयोग्य वसूली घटना है), और परीक्षा के क्रम — पहले §1001 वसूली, फिर §§1031, 1033, 1041 व 1091 अमान्यता — में जीवित है। *ये व्यक्तिगत अध्ययन नोट्स हैं; कर सलाह नहीं।*
