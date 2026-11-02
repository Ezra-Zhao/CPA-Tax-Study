# Kirby Lumber 案：折价购回自家债券的债务免除所得案例分析

> 个人学习笔记，不构成税务建议。案例：United States v. Kirby Lumber Co., 284 U.S. 1 (1931)，美国联邦最高法院判决，Holmes 大法官执笔，一致判决，1931 年 11 月 2 日宣判。

## 中文主文

### 一、案情：发债拿到面值，同年打折把债买回来

1923 年 7 月，Kirby Lumber 公司发行自家债券，面值总额 12,126,800 美元，公司按面值收到对价。同年稍后，公司在公开市场上以低于面值的价格购回其中一部分债券并予以注销：购回部分与发行价格之间的差额为 137,521.30 美元。争点年份的税法是 1921 年收入法（Revenue Act of 1921），其 § 213(a) 对总所得作宽泛界定；财政部规章（Regulations 62 第 545 条）当时已明文规定：公司以低于发行价或面值的价格购回并注销自家债券的，发行价超过购回价的差额是该纳税年度的利得或所得。

公司主张这笔差额不是所得：它没有收到任何新财产，只是把「自己将来要付款的承诺」买了回来，资产负债表上不过是负债减少。索赔法院（Court of Claims）站在了公司一边，判其可退税，理由与 Bowers v. Kerbaugh-Empire Co., 271 U.S. 170 (1925) 的整体交易亏损思路相近。政府上诉，最高法院发调卷令审理。

### 二、争点：负债减少，算不算「所得」

本案真正的问题比数字深一层：所得税法上的「所得」要不要以收到现金或财产为前提？借款的时候，借入的钱不算所得，因为资产增加的同时负债等额增加、净资产没变，还要还。那么反过来，当初按 100 借入、后来只花 89 就把债务了结，省下的 11 该怎么定性——是所得的「实现」，还是仅仅资产负债表内部的一次调整？

### 三、判决：被解放的资产就是所得

最高法院一致改判，政府胜诉，Holmes 的判词非常短，核心只有一句推理：**通过这笔交易，公司使 137,521.30 美元的资产被解放出来（made available）——这些资产此前一直被现已消灭的债券债务所抵销（offset）；债务一灭，资产便归公司自由支配，净资产实实在在地增加了。** 这就是后来所称的「资产被解放」逻辑（freeing-of-assets theory）：所得的实现不以收到新现金为必要，负债的消灭本身就能构成财富的增加（accession to wealth）。

法院同时确认财政部规章的口径有效：折价购回并注销自家债券的差额，是当年的应税利得或所得。Bowers 案没有挡住本案——那起案件涉及借入贬值货币、整体安排另有亏损背景，与本案「按面值取得资金、再以更少现金清偿同一债务」的干净事实不同。备考时注意本案的限定：公司在发行时是按面值足额收到资金的；若发行时就折价或溢价，比较的基准是调整后发行价格（adjusted issue price），不是票面面值本身。

### 四、规则坐标：从判例到 § 61(a)(11) 与 § 108

本案是债务免除所得（income from discharge of indebtedness，实务简称 COD income / CODI）的源头案例，后来被成文法吸收：

- **纳入规则**：现行 IRC § 61(a)(11) 明文把「债务免除所得」列入总所得。计算口径与本案一致：债务的调整后发行价格（或未偿本金口径）减去实际清偿所付金额，差额即所得；公司折价回购自家债券在规章层面同样按清偿处理（见 Reg. § 1.61-12 的债券回购口径），债权人发出 Form 1099-C 是信息报告，不决定所得是否成立。
- **排除规则**：§ 108 是对 Kirby 原则的成文修正，理由是被免债的人往往正是最没钱交税的人。主要排除包括：§ 108(a)(1)(A) 第 11 章破产程序内免除（优先适用）、§ 108(a)(1)(B) 资不抵债排除（以免除发生前纳税人负债超过资产公允价值的程度为限，即 § 108(d)(3) 的资不抵债定义）。被排除的所得并非凭空消失：§ 108(b) 要求按顺序冲减税属性（亏损结转、抵免、资产基数等，填报 Form 982），本质是把税递延到将来，而不是永久免除。
- **关联方堵漏**：§ 108(e)(4) 规定关联方折价买入债务人的债务，债务人视同自己回购、同样实现债务免除所得——防止把 Kirby 的事实换个主体重演来绕开规则。

### 五、与 Crane、Tufts 的分工：借款不算收入，免除才算

把本案与 Crane v. Commissioner, 331 U.S. 1 (1947) 和 Commissioner v. Tufts, 461 U.S. 300 (1983) 放在一起，债务的税务生命周期才完整：

- **借入时**：不计收入。借款人资产与负债同额增加，有清偿义务在身，没有财富增加——这是三案共同的隐含前提；
- **持有与处置时（Crane / Tufts）**：无追索权债务计入财产基数（Crane），处置财产时计入实现金额（amount realized），且 Tufts 进一步定明：即便财产公允价值已低于债务余额，实现金额仍按未偿无追索债务全额算，不以公允价值封顶；
- **清偿时（Kirby）**：以低于债务金额的对价了结债务，差额在清偿那一刻实现为所得——不再等处置财产。

一句话区分：Crane 与 Tufts 管「债跟着财产走时的基数与实现金额」，Kirby 管「债本身被打折消灭时的所得实现」。三者合起来，借入免税不是漏洞，只是一张延期券：要么将来按全额还、要么处置时按全额算实现金额、要么打折了结时就差额当场计税。

**教学算例（美元，自编，非本案数字）。** 某公司面值 1,000,000 美元债券在外流通（发行时按面值收到资金），以 920,000 美元购回并注销。债务免除所得＝1,000,000－920,000＝80,000，计入 § 61(a)(11) 总所得。若公司在免除前资不抵债金额为 50,000 美元，则可按 § 108(a)(1)(B) 排除 50,000，余下 30,000 仍应税，被排除的 50,000 按 § 108(b) 冲减税属性并报 Form 982。

### 六、现代回响与备考要点

今天这条规则的日常形态包括：企业在市场上折价回购自家债券（按清偿实现所得）、贷款和解与减免（差额计税，破产与资不抵债者走 § 108 排除）、信用卡与消费债务被免除（个人同样适用 § 61(a)(11)，常见争议点在资不抵债程度的举证）。REG 与 TCP 备考抓四点：

1. 案名、年份、法院与执笔：United States v. Kirby Lumber Co., 284 U.S. 1 (1931)，Holmes 执笔、一致判决；
2. 关键数字：1923 年发行面值总额 12,126,800 美元，购回差额 137,521.30 美元，法律依据为 1921 年收入法 § 213 与财政部规章；
3. 一句话规则：折价清偿债务的差额是所得，因为债务消灭使原被抵销的资产被解放；现行落点 § 61(a)(11) 纳入、§ 108 排除；
4. 易混点：借款本身不是所得（有清偿义务）；§ 108 排除要冲减税属性、不是永久免税；资不抵债排除以免除前的资不抵债程度封顶；比较基准是调整后发行价格，不是当然的票面面值。

*声明：个人学习笔记，不构成税务建议。来源：United States v. Kirby Lumber Co., 284 U.S. 1 (1931)（判决原文与 syllabus）；Revenue Act of 1921 § 213(a) 与 Regulations 62 Art. 545；现行 IRC §§ 61(a)(11)、108、Reg. § 1.61-12；Crane v. Commissioner, 331 U.S. 1 (1947)；Commissioner v. Tufts, 461 U.S. 300 (1983)。条号细目以现行法典与判决原文为准。*

---

## English

United States v. Kirby Lumber Co., 284 U.S. 1 (1931) (Holmes, J., for a unanimous Court; decided November 2, 1931). In July 1923 the Kirby Lumber Company issued its own bonds with an aggregate par value of $12,126,800 and received par value for them. Later the same year it repurchased some of those bonds in the open market at less than par and retired them; the difference between the issue price and the repurchase price was $137,521.30. Treasury Regulations 62, Article 545, issued under § 213(a) of the Revenue Act of 1921, treated that excess as gain or income for the year. The Court of Claims sided with the company, but the Supreme Court reversed: as Holmes put it, the transaction "made available $137,521.30 of assets previously offset by the obligation of bonds now extinct." That freeing-of-assets logic is the source of cancellation-of-debt (COD) income: discharging a liability for less than its amount is an accession to wealth, even though no new cash comes in. The principle was codified at IRC § 61(a)(11), which includes income from discharge of indebtedness in gross income; for bonds, the comparison is to adjusted issue price (see Reg. § 1.61-12), and a discounted repurchase of a company's own bonds is treated as a satisfaction of the debt. Section 108 then carves back the rule for debtors least able to pay: discharges in a Title 11 case (§ 108(a)(1)(A)) and discharges while the taxpayer is insolvent, up to the amount of insolvency (§ 108(a)(1)(B), with insolvency defined in § 108(d)(3)), are excluded — but excluded amounts reduce tax attributes under § 108(b) on Form 982, so the relief is largely a deferral, and § 108(e)(4) treats a related party's discounted purchase of the debt as a discharge to the debtor. Kirby pairs with Crane v. Commissioner, 331 U.S. 1 (1947), and Commissioner v. Tufts, 461 U.S. 300 (1983), to complete the life cycle of debt: borrowing is not income because an offsetting obligation accompanies the cash; nonrecourse debt counts in basis (Crane) and in amount realized on disposition, at the full outstanding balance even if the property is worth less (Tufts); and settling the debt itself at a discount realizes income at that moment under Kirby. Teaching example (not the case figures): bonds of $1,000,000 issued at par and repurchased for $920,000 produce $80,000 of COD income, of which $50,000 could be excluded if the issuer was insolvent by that amount immediately before the discharge, with attribute reduction for the excluded part and $30,000 still taxable. *Personal study notes only; not tax advice.*

## Español (traducción de estudio, pendiente de revisión nativa)

United States v. Kirby Lumber Co., 284 U.S. 1 (1931) (opinión de Holmes, unánime; decidido el 2 de noviembre de 1931). En julio de 1923, Kirby Lumber Company emitió sus propios bonos por un valor nominal total de $12.126.800 y recibió su valor a la par. Más tarde ese mismo año recompró algunos de esos bonos en el mercado abierto por debajo de la par y los retiró; la diferencia entre el precio de emisión y el precio de recompra fue de $137.521,30. El reglamento del Tesoro (Regulations 62, art. 545), bajo el § 213(a) de la Ley de Ingresos de 1921, trataba ese exceso como ganancia o ingreso del año. La Court of Claims falló a favor de la empresa, pero la Corte Suprema revocó: en palabras de Holmes, la operación «liberó» (made available) $137.521,30 de activos que antes estaban compensados por la obligación de los bonos ya extinguidos. Esa lógica de liberación de activos (freeing-of-assets) es la fuente del ingreso por cancelación de deuda (COD income): extinguir un pasivo por menos de su monto es un aumento de riqueza, aunque no entre dinero nuevo. El principio se codificó en el § 61(a)(11) del IRC, que incluye en el ingreso bruto el ingreso por condonación de deudas; en bonos, la comparación se hace con el precio de emisión ajustado (véase el Reg. § 1.61-12) y la recompra con descuento de los propios bonos se trata como satisfacción de la deuda. El § 108 modera luego la regla para los deudores menos capaces de pagar: se excluyen las cancelaciones en un caso del Título 11 (§ 108(a)(1)(A)) y las ocurridas en estado de insolvencia, hasta el monto de la insolvencia (§ 108(a)(1)(B), con la definición del § 108(d)(3)); pero los montos excluidos reducen atributos fiscales según el § 108(b), declarados en el Formulario 982, de modo que el alivio es en gran parte un diferimiento, y el § 108(e)(4) trata la compra con descuento por una parte relacionada como cancelación para el deudor. Kirby se combina con Crane v. Commissioner, 331 U.S. 1 (1947), y Commissioner v. Tufts, 461 U.S. 300 (1983), para completar el ciclo de vida de la deuda: pedir prestado no es ingreso porque el dinero viene acompañado de una obligación compensatoria; la deuda sin recurso cuenta en la base (Crane) y en el monto realizado al disponer del bien, por el saldo total aunque el bien valga menos (Tufts); y liquidar la propia deuda con descuento realiza ingreso en ese momento según Kirby. Ejemplo didáctico (cifras ajenas al caso): bonos de $1.000.000 emitidos a la par y recomprados por $920.000 generan $80.000 de ingreso COD, de los cuales $50.000 podrían excluirse si el emisor era insolvente por ese monto justo antes de la cancelación, con reducción de atributos por la parte excluida y $30.000 aún gravables. *Notas personales de estudio; no constituye asesoría fiscal.*

## 한국어 (초역, 원어민 감수 대기)

United States v. Kirby Lumber Co., 284 U.S. 1 (1931)(Holmes 대법관, 만장일치, 1931년 11월 2일 선고). 1923년 7월 Kirby Lumber Company는 액면 총액 $12,126,800의 자사 채권을 발행하고 액면금액을 수령했습니다. 같은 해 후반 회사는 그 채권 일부를 공개시장에서 액면 미만으로 매입해 소각했고, 발행가격과 매입가격의 차액은 $137,521.30이었습니다. 1921년 세입법(Revenue Act) § 213(a) 아래의 재무부 규정(Regulations 62 제545조)은 그 차액을 해당 연도의 이득 또는 소득으로 보았습니다. 청구법원(Court of Claims)은 회사 편을 들었지만 대법원은 파기했습니다. Holmes의 표현대로, 이 거래는 "이미 소멸한 채권 채무에 의해 상계되어 있던 $137,521.30의 자산을 사용 가능하게 만들었다(made available)"는 것입니다. 이른바 자산 해방(freeing-of-assets) 논리는 채무면제소득(COD income)의 원천입니다. 부채를 그 금액보다 적게 갚고 소멸시키는 것은 새 현금이 들어오지 않아도 재산의 증가입니다. 이 원칙은 IRC § 61(a)(11)에 성문화되어 채무면제소득을 총소득에 포함합니다. 채권의 비교 기준은 조정 발행가격이며(Reg. § 1.61-12 참조), 자사 채권의 할인 매입은 채무 변제로 취급됩니다. 이어서 § 108은 납세 여력이 가장 없는 채무자를 위해 규칙을 되돌립니다. 연방 파산법 Title 11 절차 내 면제(§ 108(a)(1)(A))와 지급불능 상태에서의 면제(지급불능 금액 한도, § 108(a)(1)(B), 지급불능의 정의는 § 108(d)(3))는 제외되지만, 제외 금액은 § 108(b)에 따라 Form 982로 세무 속성을 차감하므로 구제는 대부분 이연에 그치고, § 108(e)(4)는 관계인이 채권을 할인 매입한 경우 채무자에게 면제가 있었던 것으로 봅니다. Kirby는 Crane v. Commissioner, 331 U.S. 1 (1947) 및 Commissioner v. Tufts, 461 U.S. 300 (1983)과 함께 부채의 전 생애를 완성합니다. 차입은 상계되는 의무가 함께 오므로 소득이 아니고, 비소구 채무는 기준액(Crane)에 포함되며 처분 시 실현금액에도 재산 가치가 더 낮더라도 미상환 잔액 전액이 포함되고(Tufts), 채무 자체를 할인해 결산하면 그 시점에 Kirby에 따라 소득이 실현됩니다. 교육용 예시(본안 숫자 아님): 액면으로 발행한 $1,000,000 채권을 $920,000에 매입하면 COD 소득은 $80,000이며, 발행자가 면제 직전 $50,000만큼 지급불능이었다면 그만큼 제외할 수 있고, 제외 부분은 속성 차감 대상이며 나머지 $30,000은 여전히 과세됩니다. *개인 학습 노트이며 세무 자문이 아닙니다.*

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

United States v. Kirby Lumber Co., 284 U.S. 1 (1931) (thẩm phán Holmes viết ý kiến, nhất trí toàn viện; tuyên ngày 2 tháng 11 năm 1931). Tháng 7 năm 1923, Công ty Kirby Lumber phát hành trái phiếu của chính mình với tổng mệnh giá $12.126.800 và thu đủ mệnh giá. Cuối năm đó, công ty mua lại một phần các trái phiếu này trên thị trường mở với giá dưới mệnh giá và hủy bỏ chúng; chênh lệch giữa giá phát hành và giá mua lại là $137.521,30. Quy định của Bộ Tài chính (Regulations 62, Điều 545), ban hành theo § 213(a) của Đạo luật Doanh thu 1921, coi phần chênh đó là lãi hoặc thu nhập của năm. Tòa Khiếu nại (Court of Claims) xử cho công ty thắng, nhưng Tòa Tối cao đảo ngược: theo lời của Holmes, giao dịch đã «giải phóng» (made available) $137.521,30 tài sản vốn trước đó bị đối trừ bởi nghĩa vụ của các trái phiếu nay đã chấm dứt. Logic giải phóng tài sản (freeing-of-assets) này là nguồn gốc của thu nhập do xóa nợ (COD income): thanh toán một khoản nợ với số tiền ít hơn số nợ là một sự gia tăng tài sản, dù không có tiền mới chảy vào. Nguyên tắc này được luật hóa tại IRC § 61(a)(11), đưa thu nhập từ xóa nợ vào tổng thu nhập; với trái phiếu, mốc so sánh là giá phát hành đã điều chỉnh (xem Reg. § 1.61-12) và việc mua lại trái phiếu của chính công ty với giá chiết khấu được coi là thanh toán khoản nợ. § 108 sau đó nới lại quy tắc cho những con nợ ít khả năng nộp thuế nhất: xóa nợ trong vụ việc theo Title 11 (§ 108(a)(1)(A)) và xóa nợ khi người nộp thuế mất khả năng thanh toán, tối đa bằng mức mất khả năng thanh toán (§ 108(a)(1)(B), với định nghĩa tại § 108(d)(3)), được loại trừ — nhưng số tiền loại trừ phải giảm trừ các thuộc tính thuế theo § 108(b) trên Form 982, nên sự cứu trợ phần lớn chỉ là hoãn thuế, và § 108(e)(4) coi việc bên liên quan mua nợ với giá chiết khấu là xóa nợ đối với con nợ. Kirby kết hợp với Crane v. Commissioner, 331 U.S. 1 (1947), và Commissioner v. Tufts, 461 U.S. 300 (1983), để hoàn chỉnh vòng đời của khoản nợ: đi vay không phải thu nhập vì tiền vay đi kèm nghĩa vụ đối trừ; nợ không truy đòi được tính vào cơ sở tính thuế (Crane) và vào số tiền thực hiện khi chuyển nhượng tài sản, theo toàn bộ dư nợ dù tài sản có giá trị thấp hơn (Tufts); còn thanh toán chính khoản nợ với giá chiết khấu thì thực hiện thu nhập ngay tại thời điểm đó theo Kirby. Ví dụ giảng dạy (không phải số liệu vụ án): trái phiếu $1.000.000 phát hành theo mệnh giá và được mua lại với $920.000 tạo ra $80.000 thu nhập COD, trong đó $50.000 có thể được loại trừ nếu tổ chức phát hành mất khả năng thanh toán đúng số đó ngay trước khi xóa nợ, phần loại trừ bị giảm trừ thuộc tính thuế và $30.000 còn lại vẫn chịu thuế. *Ghi chú học tập cá nhân, không phải tư vấn thuế.*

## हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

United States v. Kirby Lumber Co., 284 U.S. 1 (1931) (Holmes न्यायाधीश, सर्वसम्मत; निर्णय 2 नवंबर 1931)। जुलाई 1923 में Kirby Lumber Company ने कुल अंकित मूल्य $12,126,800 के अपने बॉन्ड जारी किए और उनका सममूल्य प्राप्त किया। उसी वर्ष बाद में कंपनी ने उनमें से कुछ बॉन्ड खुले बाज़ार में सममूल्य से कम पर पुनः खरीदकर सेवानिवृत्त कर दिए; निर्गम मूल्य और पुनर्खरीद मूल्य का अंतर $137,521.30 था। Revenue Act of 1921 के § 213(a) के तहत Treasury Regulations 62, अनुच्छेद 545, उस आधिक्य को उस वर्ष का लाभ या आय मानता था। Court of Claims ने कंपनी के पक्ष में निर्णय दिया, किंतु सर्वोच्च न्यायालय ने पलट दिया: Holmes के शब्दों में, इस लेन-देन ने "$137,521.30 की उन परिसंपत्तियों को उपलब्ध (made available) कर दिया जो अब विलुप्त बॉन्ड-दायित्व से पहले प्रतिसंतुलित थीं।" यही परिसंपत्ति-मुक्ति (freeing-of-assets) तर्क ऋण-रद्दीकरण आय (COD income) का स्रोत है: दायित्व को उसकी राशि से कम में निपटाना संपत्ति की वृद्धि है, भले ही नई नकदी न आई हो। यह सिद्धांत IRC § 61(a)(11) में संहिताबद्ध हुआ, जो ऋण-मुक्ति से आय को सकल आय में शामिल करता है; बॉन्डों में तुलना समायोजित निर्गम मूल्य से होती है (Reg. § 1.61-12 देखें) और अपने ही बॉन्डों की छूट पर पुनर्खरीद ऋण की संतुष्टि मानी जाती है। फिर § 108 उन देनदारों हेतु नियम को नरम करता है जो कर देने में सबसे कम सक्षम हैं: Title 11 मामले में मुक्ति (§ 108(a)(1)(A)) और दिवालियापन की सीमा तक दिवाला-अवस्था में मुक्ति (§ 108(a)(1)(B), दिवाला की परिभाषा § 108(d)(3) में) अपवर्जित हैं — किंतु अपवर्जित राशियाँ § 108(b) के तहत Form 982 पर कर-गुणों को घटाती हैं, अतः राहत अधिकांशतः स्थगन है, और § 108(e)(4) संबंधित पक्ष द्वारा छूट पर ऋण-क्रय को देनदार हेतु मुक्ति मानता है। Kirby, Crane v. Commissioner, 331 U.S. 1 (1947), और Commissioner v. Tufts, 461 U.S. 300 (1983), के साथ मिलकर ऋण का पूरा जीवनचक्र बनाता है: उधार आय नहीं है क्योंकि नकदी के साथ प्रतिसंतुलित दायित्व आता है; अप्रत्याश्रय (nonrecourse) ऋण आधार में गिना जाता है (Crane) और निपटान पर वसूल राशि में भी, पूरी बकाया राशि पर, भले संपत्ति का मूल्य कम हो (Tufts); और स्वयं ऋण को छूट पर निपटाने से Kirby के तहत उसी क्षण आय वसूल होती है। शिक्षण उदाहरण (मामले के आँकड़े नहीं): सममूल्य पर जारी $1,000,000 के बॉन्ड $920,000 में पुनः खरीदे जाएँ तो $80,000 COD आय बनती है, जिसमें से $50,000 तब अपवर्जित हो सकता है यदि जारीकर्ता मुक्ति से ठीक पहले उतनी राशि से दिवालिया था, अपवर्जित भाग पर गुण-कटौती लागू होगी और $30,000 फिर भी करयोग्य रहेगा। *व्यक्तिगत अध्ययन नोट; कर सलाह नहीं।*

---

## 免责声明 / Disclaimer

中文：本文为个人学习笔记，不构成税务、财务或法律建议。具体事务请咨询持牌 CPA 或税务律师。

English: This article is a personal study note only and does not constitute tax, financial, or legal advice. For specific matters, consult a licensed CPA or tax attorney.

Español: Este artículo es solo una nota personal de estudio y no constituye asesoría fiscal, financiera ni legal. Para asuntos concretos, consulte a un CPA con licencia o a un abogado fiscalista.

한국어: 본 글은 개인 학습 노트이며 세무·재무·법률 자문이 아닙니다. 구체적인 사안은 면허 CPA나 세무 변호사에게 상담하시기 바랍니다.

Tiếng Việt: Bài viết này chỉ là ghi chú học tập cá nhân, không phải tư vấn thuế, tài chính hay pháp lý. Với vấn đề cụ thể, hãy tham vấn CPA có giấy phép hoặc luật sư thuế.

हिन्दी: यह लेख केवल व्यक्तिगत अध्ययन नोट है और कर, वित्तीय या कानूनी सलाह नहीं है। किसी विशिष्ट मामले के लिए कृपया लाइसेंस-प्राप्त CPA या कर वकील से परामर्श करें।
