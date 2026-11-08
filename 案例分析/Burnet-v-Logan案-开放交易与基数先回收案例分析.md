# Burnet v. Logan 案：开放交易原则与基数先回收

这篇讲什么：
- Burnet v. Logan, 283 U.S. 404 (1931) 确立了开放交易（open transaction）处理：一笔对价根本估不出价值的交易先不关账，收款先回收基数，超出的部分才算所得。
- 本案是实现原则在估值不能时的出口：不是免税，也不是递延花招，而是价值没法合理确定时，税只能等钱真收回来再算。
- 后世把这条路收得很窄：临时法规只留给罕见且特殊的情形，现代默认路径是 IRC 453 分期付款法，考试里开放交易是例外，不是常规。

## 一、事实与程序：卖股份，换一纸按吨付钱的承诺

### 中文
本案是 Burnet v. Logan, 283 U.S. 404 (1931)，由美国联邦最高法院判决。能核实的事实只讲经得起查的几条。Logan 持有与矿业相关的公司的股份，她把这部分股份出售，对价由两部分构成：一部分是现金，另一部分是买方的一项承诺，按照将来实际开采出的矿石数量，每吨支付 60 美分给她。问题出在第二部分：矿山将来能采多少矿石、采多少年，当时谁也说不准，这项按吨付款的权利在交易当年无法合理估值。税务机关主张按交易已经关闭处理、估值当期计税；Logan 一方则主张真金白银收回来之前算不出所得。争议表面是估值问题，底下更根本：一项无法估值的权利，能不能被当成已经实现的收入课税？

### English
The case is Burnet v. Logan, 283 U.S. 404 (1931), decided by the U.S. Supreme Court. Logan held shares in a company connected with mining operations, and she sold those shares for two kinds of consideration: cash, plus a promise to pay her 60 cents for each ton of ore actually extracted in the future. The problem sat in the second part. How much ore the mine would produce, and over how many years, no one could say at the time, so the right to those per-ton payments had no reasonably ascertainable value in the year of the sale. The tax authorities wanted to treat the deal as closed and tax it currently; Logan argued no income could be computed until money actually came in. Underneath the valuation dispute sat a basic question: can an unvaluable right be taxed as realized income?

### Español (译稿·初译待校)
El caso es Burnet v. Logan, 283 U.S. 404 (1931), resuelto por el Tribunal Supremo de EE. UU. Logan poseía acciones de una sociedad vinculada a operaciones mineras y las vendió por efectivo, más la promesa de pagarle 60 centavos por cada tonelada de mineral efectivamente extraída en el futuro. Cuánto mineral daría la mina y durante cuántos años nadie podía decirlo entonces, de modo que ese derecho no tenía un valor razonablemente determinable en el año de la venta. La administración quiso tratar la operación como cerrada y gravarla en el acto; Logan sostuvo que no podía computarse renta hasta que el dinero entrara. En el fondo había una pregunta básica: ¿puede gravarse como renta realizada un derecho que no se puede valorar?

### 한국어 (초역·待校)

이 사건은 미국 연방 대법원의 Burnet v. Logan, 283 U.S. 404 (1931)입니다. 확인 가능한 사실만 적습니다. Logan은 광업 관련 회사의 주식을 보유하고 있었고, 그 주식을 현금과 장래 실제 채굴되는 광석 1톤당 60센트를 지급하겠다는 약속을 대가로 매각했습니다. 광산이 앞으로 얼마나, 몇 년간 생산할지 당시에는 알 수 없어 톤당 지급 권리는 매각 연도에 합리적으로 확정할 수 있는 가치가 없었습니다. 과세 관청은 거래가 종결된 것으로 보고 과세하려 했고, Logan 측은 실제로 돈을 받기 전에는 소득을 계산할 수 없다고 맞섰습니다.

### Tiếng Việt (bản dịch sơ bộ·待校)
Vụ án là Burnet v. Logan, 283 U.S. 404 (1931), do Tòa án Tối cao Hoa Kỳ phán quyết. Logan nắm giữ cổ phần trong một công ty gắn với hoạt động khai khoáng, và bà bán số cổ phần đó lấy hai phần đối giá: tiền mặt, cộng một cam kết trả cho bà 60 xu cho mỗi tấn quặng thực tế khai thác trong tương lai. Vấn đề nằm ở phần thứ hai: mỏ sẽ cho bao nhiêu quặng và trong bao nhiêu năm, khi đó không ai nói được, nên quyền nhận tiền theo tấn không có giá trị có thể xác định hợp lý trong năm bán. Cơ quan thuế muốn coi giao dịch đã đóng và đánh thuế ngay; phía Logan cho rằng không thể tính thu nhập cho đến khi tiền thật sự về tay. Bên dưới tranh chấp định giá là câu hỏi căn bản hơn: một quyền không định giá được có thể bị đánh thuế như thu nhập đã thực hiện hay không?

### हिन्दी (प्रारंभिक अनुवाद·待校)

यह Burnet v. Logan, 283 U.S. 404 (1931) है, अमेरिका के सर्वोच्च न्यायालय का निर्णय। केवल सत्यापन-योग्य तथ्य रखें। Logan के पास खनन से जुड़ी कंपनी के शेयर थे; उन्होंने वे शेयर नकद और भविष्य में वास्तव में निकाले गए प्रत्येक टन अयस्क पर 60 सेंट देने के वादे के बदले बेचे। खदान कितना अयस्क देगी और कितने वर्षों तक, उस समय कोई नहीं बता सकता था, इसलिए टन-दर भुगतान के अधिकार का बिक्री-वर्ष में कोई उचित निश्चित मूल्य नहीं था। कर-प्रशासन सौदे को बंद मानकर कर लगाना चाहता था; Logan का पक्ष था कि धन वास्तव में मिले बिना आय गिनी ही नहीं जा सकती।

## 二、争点与裁决：交易保持开放，先回收基数

### 中文
争点是：或有付款权利要不要在交易当年估值计入所得，还是把交易视为未关闭、等收款时再算。最高法院选了后者，这就是开放交易（open transaction）处理。判决要点只有两步。第一步，在累计实际收款超过 Logan 就其所售股份享有的基数（basis）之前，不确认所得：收回来的钱先算回收自己的本，也就是先回收基数。第二步，只有当累计收款越过基数之后，超出部分才构成利得，在本案的语境下按资本利得处理。底气来自一个朴素判断：按吨付款的权利当时没有可合理确定的公允价值，硬编一个数课税，征的是猜测而非已实现的所得。于是交易在税务上保持开放，账随真钱一笔笔进来再慢慢关。先回收基数不等于免税，税只是往后挪。

### English
The issue was whether Logan's contingent payment right had to be valued into income in the year of sale, or whether the transaction stayed open until payments arrived. The Supreme Court chose the second course — the open transaction treatment. The holding has two steps. Step one: until cumulative amounts actually received exceed Logan's basis in the shares she sold, no income is recognized; money coming in is first treated as a recovery of her own capital, a return of basis. Step two: only after cumulative receipts pass that basis does the excess become gain, treated in this case's setting as capital gain. The footing was plain: the per-ton right had no reasonably ascertainable fair value, and inventing a number would tax a guess, not realized income. So the transaction stayed open, closing gradually as payments arrived. Recovering basis first is not an exemption; the tax is only postponed.

### Español (译稿·初译待校)
La cuestión era si el derecho contingente de Logan debía valorarse en el año de la venta o si la operación permanecía abierta hasta los cobros. El Tribunal Supremo eligió lo segundo: la operación abierta (open transaction). La decisión tiene dos pasos. Paso uno: mientras lo efectivamente cobrado, en acumulado, no supere la base (basis) de Logan en las acciones vendidas, no se reconoce renta; el dinero que entra es primero recuperación de su propio capital. Paso dos: solo cuando lo cobrado supera esa base, el exceso es ganancia, tratada en el contexto del caso como ganancia de capital. El fundamento fue sencillo: el derecho por tonelada carecía de valor razonable determinable, e inventarle una cifra gravaría una conjetura. La operación quedó abierta y se fue cerrando con cada cobro. Recuperar la base no es exención, es aplazamiento.

### 한국어 (초역·待校)

쟁점은 Logan이 받은 조건부 지급 권리를 매각 연도에 평가해 소득에 넣어야 하는지, 아니면 거래를 열어 두고 실제 수령 때 계산해야 하는지였습니다. 대법원은 후자, 즉 개방 거래(open transaction) 처리를 택했습니다. 판결은 두 단계입니다. 첫째, 누적 실수령액이 매각 주식에 대한 Logan의 기준가액(basis)을 넘기 전까지는 소득을 인식하지 않습니다. 들어오는 돈은 먼저 자기 자본의 회수, 즉 basis 회수입니다. 둘째, 누적 수령액이 basis를 넘은 뒤에야 초과분이 이득이 되며, 본 사건의 맥락에서는 자본이득으로 취급됩니다. 톤당 권리에는 당시 합리적으로 확정할 수 있는 가치가 없었고, 숫자를 지어내 과세하면 추측을 과세하는 셈이라는 것이 근거였습니다.

### Tiếng Việt (bản dịch sơ bộ·待校)
Vấn đề là quyền nhận thanh toán có điều kiện mà Logan nhận được có phải định giá và tính vào thu nhập ngay trong năm bán hay không, hay giao dịch vẫn để mở và chỉ tính khi tiền về. Tòa án Tối cao chọn cách thứ hai — xử lý giao dịch mở (open transaction). Phán quyết có hai bước. Bước một: chừng nào tổng số tiền thực nhận lũy kế chưa vượt quá cơ sở (basis) của Logan trong số cổ phần đã bán, thì chưa ghi nhận thu nhập; tiền về trước hết là thu hồi vốn của chính mình, tức thu hồi basis. Bước hai: chỉ sau khi tổng tiền nhận vượt qua basis đó, phần vượt mới thành khoản lãi, và trong bối cảnh vụ này được xử lý như lãi vốn (capital gain). Nền tảng của phán quyết rất thẳng: quyền theo tấn khi đó không có giá trị hợp lý nào xác định được một cách hợp lý, bịa ra một con số để đánh thuế là đánh thuế vào phỏng đoán, không phải thu nhập đã thực hiện. Lưu ý: thu hồi basis trước không phải miễn thuế, mà chỉ là hoãn lại.

### हिन्दी (प्रारंभिक अनुवाद·待校)

प्रश्न था कि Logan को मिला आकस्मिक भुगतान-अधिकार बिक्री-वर्ष में ही मूल्यांकित कर आय में जोड़ा जाए, या सौदा खुला (open transaction) रखकर प्राप्ति पर हिसाब हो। सर्वोच्च न्यायालय ने दूसरा रास्ता चुना। निर्णय के दो चरण हैं। चरण एक: जब तक संचयी वास्तविक प्राप्तियाँ बेचे गए शेयरों में Logan के आधार (basis) से अधिक न हों, कोई आय नहीं मानी जाती; आता धन पहले अपनी पूँजी की वापसी है। चरण दो: प्राप्तियाँ basis पार करें, तभी अतिरिक्त राशि लाभ बनती है, इस मामले के संदर्भ में पूँजीगत लाभ। आधार सीधा था: टन-दर अधिकार का तब कोई उचित निश्चित मूल्य नहीं था, और संख्या गढ़कर कर लगाना अनुमान पर कर होता।

## 三、推理：实现原则与估值不能如何衔接

### 中文
要理解本案，得把它接回实现原则（realization）。Eisner v. Macomber, 252 U.S. 189 (1920) 是所得税法绕不开的源头之一：价值涨了，不等于所得已经实现，税要等实现事件、所得真正从资本里分离出来才登场。Logan 把这个思路往前推了一步：变现的形式已经发生，可拿到的东西根本估不出价时怎么办。最高法院的答案是先不关账：实现原则不只管有没有交易，还管结果能不能被合理计量。与其按猜测的价值先征一道，不如让交易保持开放，以实际收款为准，先回本、后计利。这也划出它的底色：它救的是估值真正不能的极端情形，不是给所有或有对价开的后门。

### English
To place the case doctrinally, connect it to realization. Eisner v. Macomber, 252 U.S. 189 (1920), separates income from mere appreciation: a rise in value is not yet realized income, and tax generally waits for a realization event. Logan carries that thinking one step further — a disposition has occurred, but the thing received cannot be valued at all. The Court's answer was to leave the account open: the realization principle cares not only whether a transaction happened, but whether its result can be reasonably measured. When measurement cannot honestly be made, the better course is to keep the transaction open and let actual receipts do the work — basis back first, gain after — rather than tax a guessed value now and true it up later. Open transaction rescues only the extreme case of genuinely impossible valuation, not every contingent deal.

### Español (译稿·初译待校)
Para situar el caso hay que conectarlo con la realización. Eisner v. Macomber, 252 U.S. 189 (1920), fuente ineludible del impuesto sobre la renta, separa la renta de la mera apreciación del patrimonio: que un bien valga más no es aún renta realizada. Logan lleva esa idea un paso más allá. Si Macomber responde qué pasa antes de que la apreciación se realice, Logan responde qué pasa cuando la disposición ya ocurrió pero lo recibido no puede valorarse en absoluto. La respuesta del Tribunal fue dejar la cuenta abierta: el principio de realización atiende no solo a si hubo operación, sino a si su resultado puede medirse razonablemente. Cuando la medición no es honestamente posible, es mejor mantener la operación abierta y que los cobros reales hagan el trabajo —primero la base, después la ganancia— que gravar un valor adivinado. Por eso la operación abierta socorre el caso extremo de valoración realmente imposible, no cualquier pacto contingente valorable.

### 한국어 (초역·待校)

법리상 위치를 잡으려면 실현 원칙(realization)과 연결해야 합니다. Eisner v. Macomber, 252 U.S. 189 (1920)는 소득과 단순한 재산 가치 상승을 나눈 원천 중 하나입니다. 가치가 올랐다고 실현된 소득은 아니며, 과세는 보통 실현 사건을 기다립니다. Logan은 그 생각을 한 걸음 더 밀었습니다. 처분은 일어났지만 받은 것의 가치를 도저히 매길 수 없을 때 어떻게 할 것인가가 문제였고, 대법원의 답은 장부를 열어 두는 것이었습니다. 실현 원칙은 거래의 유무만이 아니라 그 결과를 합리적으로 측정할 수 있는지도 봅니다. 추측값에 먼저 과세하는 것보다 실제 수령을 기준으로 basis를 먼저 회수하고 그다음 이득을 세는 편이 낫다는 것입니다.

### Tiếng Việt (bản dịch sơ bộ·待校)
Muốn đặt vụ án đúng chỗ, phải nối nó với nguyên tắc thực hiện (realization). Eisner v. Macomber, 252 U.S. 189 (1920), một nguồn không thể bỏ qua của luật thuế thu nhập, tách thu nhập khỏi sự tăng giá trị thuần túy của tài sản: giá trị tăng chưa phải thu nhập đã thực hiện. Logan đưa tư tưởng đó thêm một bước. Nếu Macomber trả lời chuyện gì xảy ra trước khi phần tăng giá thành hiện thực, thì Logan trả lời chuyện gì xảy ra khi việc chuyển nhượng đã diễn ra nhưng thứ nhận được lại hoàn toàn không định giá nổi. Đáp án của Tòa là để tài khoản mở: nguyên tắc thực hiện không chỉ hỏi có giao dịch hay không, mà còn hỏi kết quả của nó có đo lường hợp lý được không. Khi không đo được một cách trung thực, để giao dịch mở và dùng tiền thực nhận làm thước — thu hồi basis trước, tính lãi sau — vẫn hơn là đánh thuế trên một giá trị đoán mò. Vì thế giao dịch mở chỉ cứu trường hợp cực đoan không thể định giá thật sự.

### हिन्दी (प्रारंभिक अनुवाद·待校)

मामले को सिद्धांत में रखने के लिए उसे वसूली/बोध सिद्धांत (realization) से जोड़ें। Eisner v. Macomber, 252 U.S. 189 (1920) आयकर कानून का एक मूल स्रोत है: यह आय को संपत्ति के केवल मूल्य-वृद्धि से अलग करता है। मूल्य बढ़ना अभी वसूल आय नहीं है; कर आम तौर पर वसूली-घटना की प्रतीक्षा करता है। Logan उस विचार को एक कदम आगे ले जाता है। निस्तारण हो चुका है, किंतु मिली वस्तु का मूल्य बिल्कुल नहीं आँका जा सकता — तब क्या हो? न्यायालय का उत्तर था खाता खुला रखना: वसूली सिद्धांत केवल सौदे के होने को नहीं, उसके परिणाम के उचित मापन को भी देखता है। अनुमानित मूल्य पर कर लगाने से बेहतर है वास्तविक प्राप्तियों से पहले basis वसूला जाए, फिर लाभ गिना जाए।

## 四、后世限制：从判例出口到罕见且特殊的例外

### 中文
本案判于 1931 年，但后来的规则把口子收得非常窄，今天不能直接抱着它套。关键一步在法规层：分期付款销售临时法规 Treas. Reg. 15a.453-1(c) 明确，开放交易只保留给罕见且特殊（rare and extraordinary）的情形，即对价确实没有可合理确定公允价值的极端案件。绝大多数或有对价和分期安排，要么能估值，要么有成文规则可走。现代默认路径是 IRC 453 的分期付款法（installment method）：符合条件的出售按收款比例确认利得，每收一期钱，按总利润比例算出一份利得计入当期。两种处理放在一起对比，差别一目了然：开放交易是先回本、后计利，分期付款法是边收款、边按比例计利。考试爱考的正是这个对照，看到或有对价先想 453，再想 Logan 是否够得上罕见且特殊，不够格就老实回默认路径。法规条号与适用细节以现行官方文本为准。

### English
Decided in 1931, the case cannot simply be ridden on today; later law narrowed the opening sharply. The key step is regulatory: Treas. Reg. section 15a.453-1(c), the temporary regulation on installment sales, keeps open-transaction treatment only for rare and extraordinary situations — the extreme cases where what the seller received truly has no reasonably ascertainable fair market value. For most contingent and installment arrangements, the consideration either can be valued or has a statutory route. The modern default route is the installment method of IRC section 453: on a qualifying sale, gain is recognized in proportion as payments are received, each payment carrying its fraction of total gross profit into income. The contrast is stark — open transaction is basis first, gain later; the installment method is gain proportionally as cash arrives. Exams test exactly this contrast. Regulation numbering and details follow the current official text.

### Español (译稿·初译待校)
El caso se decidió en 1931, pero hoy ni el examen ni la planificación pueden apoyarse en él sin más, porque el derecho posterior estrechó mucho la puerta. El paso clave es reglamentario: la norma temporal sobre ventas a plazos, Treas. Reg. 15a.453-1(c), reserva el tratamiento de operación abierta a supuestos raros y extraordinarios (rare and extraordinary), los casos extremos en que lo recibido por el vendedor de verdad carece de valor de mercado razonablemente determinable. En la mayoría de los pactos contingentes o a plazos, la contraprestación o puede valorarse o tiene una vía legal prevista. La ruta moderna por defecto es el método de plazos del IRC 453 (installment method): la ganancia se reconoce en proporción a los cobros. El contraste es nítido: operación abierta es primero la base y después la ganancia; el método de plazos es ganancia proporcional a cada cobro. Los detalles se rigen por el texto oficial vigente.

### 한국어 (초역·待校)

본 판결은 1931년의 것이지만, 이후 규칙이 입구를 대폭 좁혔기 때문에 오늘 시험과 설계에 그대로 쓸 수는 없습니다. 핵심은 임시 규정 Treas. Reg. 15a.453-1(c)입니다. 이 규정은 개방 거래 처리를 희귀하고 예외적인(rare and extraordinary) 상황, 즉 매도인이 받은 대가에 합리적으로 확정할 수 있는 공정한 시장가치가 실제로 없는 극단적인 경우에만 남겨 뒀습니다. 현대의 기본 경로는 IRC 453의 할부법(installment method)입니다. 요건을 갖춘 매각에서는 수령 비율에 따라 이득을 인식합니다. 개방 거래가 basis 먼저, 이득 나중이라면, 할부법은 받을 때마다 비율로 이득을 세는 방식입니다. 시험은 바로 이 대조를 묻습니다.

### Tiếng Việt (bản dịch sơ bộ·待校)
Vụ án được phán quyết năm 1931, nhưng ngày nay cả bài thi lẫn việc lập kế hoạch đều không thể cứ thế dựa vào nó, vì luật về sau đã thu hẹp cánh cửa rất nhiều. Bước then chốt nằm ở cấp quy định: quy định tạm thời về bán trả góp, Treas. Reg. 15a.453-1(c), chỉ giữ xử lý giao dịch mở cho những tình huống hiếm và đặc biệt (rare and extraordinary) — những trường hợp cực đoan mà đối giá người bán nhận được thật sự không có giá trị thị trường hợp lý nào xác định được. Với hầu hết các thỏa thuận có điều kiện hay trả góp, đối giá hoặc định giá được, hoặc đã có con đường luật định. Con đường mặc định hiện đại là phương pháp trả góp (installment method) của IRC 453: khoản lãi được ghi nhận theo tỷ lệ tiền nhận được. Khác biệt rất rõ: giao dịch mở là basis trước, lãi sau; phương pháp trả góp là lãi theo tỷ lệ mỗi lần thu tiền. Chi tiết theo văn bản chính thức hiện hành.

### हिन्दी (प्रारंभिक अनुवाद·待校)

मामला 1931 का है, किंतु बाद के नियमों ने द्वार बहुत संकरा कर दिया, इसलिए आज इसे सीधे लागू नहीं किया जा सकता। मुख्य कदम विनियम-स्तर पर है: किस्त-बिक्री पर अस्थायी विनियम Treas. Reg. 15a.453-1(c) खुला-सौदा व्यवहार केवल दुर्लभ और असाधारण (rare and extraordinary) स्थितियों के लिए रखता है — वे चरम मामले जहाँ मिली प्रतिफल का वास्तव में कोई उचित निश्चित बाज़ार मूल्य नहीं है। आधुनिक डिफ़ॉल्ट मार्ग IRC 453 की किस्त पद्धति (installment method) है: योग्य बिक्री पर लाभ प्राप्तियों के अनुपात में माना जाता है। विरोधाभास स्पष्ट है — खुले सौदे में पहले basis, फिर लाभ; किस्त पद्धति में हर प्राप्ति के साथ आनुपातिक लाभ। विवरण वर्तमान आधिकारिक पाठ के अनुसार।

## 五、教学落点：考试抓手与筹划边界

### 中文
本案最后收成三句考试能直接用的话。第一，对价里有按产量、销量或将来事件付钱的或有权利，先问两个问题：有没有可合理确定的公允价值，够不够罕见且特殊。都过才轮得到开放交易；过不了，默认走 IRC 453 分期付款法。第二，计算顺序背死：累计收款先冲基数，冲完之前所得为零，之后超出的每一分都是利得；不要把每期收款拆成本和利两块，那是分期付款法的拆法。第三，筹划边界要清醒：开放交易是估值不能时的救济，不是推迟正常交易纳税的工具。能估值的或有对价硬往 Logan 上靠，今天过不了关，写成常规筹划方案同样丢分。记忆法一句话：Logan 的门只为估不出价的极端情形留着，门很窄，里面很简单——先回本，后算利。（个人学习笔记，不构成税务建议。）

### English
Close the case with three exam-ready lines. First, when consideration includes a contingent right paid by output, sales, or a future event, ask two questions before valuing it: does it have a reasonably ascertainable fair market value, and is the situation rare and extraordinary? Only if both hold does open transaction enter; otherwise the default is the IRC section 453 installment method. Second, memorize the arithmetic: cumulative receipts recover basis first, income is zero until basis is fully back, and every dollar after that is gain. Do not split each payment into basis and gain; that split belongs to the installment method. Third, keep the planning boundary clear: open transaction is relief for impossible valuation, not a device to defer tax on ordinary deals, and presenting it as routine planning loses marks. Memory aid: Logan's door stays open only for the extreme case that cannot be valued — capital back first, gain after. (Personal study notes; not tax advice.)

### Español (译稿·初译待校)
Tres frases para el examen. Primera: si la contraprestación incluye un derecho contingente, pregunte antes si tiene valor determinable y si el supuesto es raro y extraordinario; solo entonces entra la operación abierta, y si no, rige el método de plazos del IRC 453. Segunda: lo cobrado recupera primero la base, la renta es cero hasta recuperarla entera y cada dólar posterior es ganancia; no divida cada cobro en base y ganancia, porque esa división es del método de plazos. Tercera: la operación abierta es remedio para la valoración imposible, no herramienta para aplazar impuestos normales. Frase memoria: la puerta de Logan solo queda abierta para el caso extremo que no puede valorarse; primero el capital, después la ganancia. (Notas personales de estudio; no constituye asesoría fiscal.)

### 한국어 (초역·待校)

시험용으로 세 문장으로 정리합니다. 첫째, 생산량이나 미래 사건에 따라 지급되는 조건부 권리가 대가에 들어 있으면 먼저 평가하지 말고, 합리적으로 확정 가능한 공정 시장가치가 있는지, 희귀하고 예외적인 경우인지부터 묻습니다. 둘 다 충족돼야 개방 거래이고, 아니면 기본값인 IRC 453 할부법으로 수령 비율대로 이득을 인식합니다. 둘째, 개방 거래의 계산 순서는 고정입니다. 누적 수령액이 basis를 먼저 회수하고, 다 회수하기 전까지 소득은 0이며, 그 뒤의 초과분은 전부 이득입니다. 셋째, 개방 거래는 평가가 불가능할 때의 구제책이지 정상 거래의 납세를 미루는 도구가 아닙니다. 기억법: Logan의 문은 평가할 수 없는 극단적인 경우에만 열려 있습니다. 먼저 원금, 나중 이득입니다. (개인 학습 노트이며 세무 자문이 아닙니다.)

보충하면, 회수 순서를 가르치는 산례입니다(구성 예시). 기초 금액(basis)이 10,000달러이고 톤당 0.60달러를 받는다고 하면, 첫해 수령 6,000달러는 전액 기초 금액 회수라 소득이 0이고 남은 기초 금액은 4,000달러입니다. 둘째 해 수령 7,000달러는 먼저 남은 4,000달러를 채우고, 초과분 3,000달러가 그제야 이익이 됩니다. 누적 수령이 기초 금액을 넘는 순간부터 과세가 시작되는데, 이것이 매기 수령을 원금과 이익으로 나누는 분할법(분납법)과의 결정적 차이입니다.
또 보충하면, 현대 실무에서 Logan의 문은 거의 열리지 않습니다. 추정이 어느 정도라도 가능하면 법원은 대개 평가 경로를 찾기 때문이며, §453이 적용되지 않는 재고·딜러 처분·상장 증권 같은 거래는 분할법으로도 개방 거래로도 가지 않고 통상 규칙으로 돌아갑니다. 그리고 누적 수령이 끝내 기초 금액을 채우지 못한 채 권리가 무가치해지면, 회수되지 않은 기초 금액은 권리가 최종적으로 무가치해졌다는 것이 확정될 때에야 손실로 다룰 수 있는 것이 원칙입니다.

### Tiếng Việt (bản dịch sơ bộ·待校)
Ba câu dùng ngay trong phòng thi. Một: khi đối giá có quyền có điều kiện, hãy hỏi trước nó có giá trị xác định được không và tình huống có hiếm và đặc biệt không; cả hai đều thỏa mới đến giao dịch mở, nếu không mặc định là phương pháp trả góp của IRC 453. Hai: tiền nhận lũy kế thu hồi basis trước, thu nhập bằng không cho đến khi thu hồi đủ, mỗi đồng sau đó đều là lãi; đừng tách mỗi lần nhận thành basis và lãi. Ba: giao dịch mở là cứu cánh cho trường hợp không định giá nổi, không phải công cụ hoãn thuế. Câu nhớ: cánh cửa của Logan chỉ mở cho trường hợp cực đoan không định giá được; thu hồi vốn trước, tính lãi sau. (Ghi chú học tập cá nhân; không phải tư vấn thuế.)

Bổ sung thêm, một ví dụ dạy học về thứ tự thu hồi (ví dụ được xây dựng). Giả sử giá trị cơ sở (basis) là 10.000 đô la và nhận 0,60 đô la mỗi tấn: năm đầu nhận 6.000 đô la thì toàn bộ là thu hồi cơ sở, thu nhập bằng 0, cơ sở còn lại 4.000 đô la. Năm hai nhận 7.000 đô la thì trước hết lấp hết 4.000 đô la cơ sở còn lại, và phần vượt 3.000 đô la mới thành lợi nhuận. Thuế chỉ bắt đầu từ khoảnh khắc tổng số tiền đã nhận vượt cơ sở — đó là khác biệt quyết định so với phương pháp trả góp vốn chia mỗi khoản thu thành vốn và lãi.
Bổ sung thêm nữa, trong thực tiễn hiện đại cánh cửa Logan hầu như không mở. Chỉ cần việc định giá ở mức nào đó còn khả thi, tòa thường tìm ra đường định giá; và các giao dịch mà Mục 453 không áp dụng — hàng tồn kho, thanh lý của nhà buôn, chứng khoán niêm yết — thì quay về quy tắc thông thường chứ không vào phương pháp trả góp hay giao dịch mở. Còn nếu tổng số tiền nhận được đến cuối vẫn không lấp hết cơ sở và quyền trở nên vô giá trị, phần cơ sở chưa thu hồi về nguyên tắc chỉ được xử lý như khoản lỗ khi tính vô giá trị đó được xác định dứt điểm.

### हिन्दी (प्रारंभिक अनुवाद·待校)

मामले को परीक्षा-योग्य तीन पंक्तियों में समेटें। पहली: प्रतिफल में उत्पादन, बिक्री या भविष्य की घटना पर आधारित आकस्मिक अधिकार हो तो पहले मूल्यांकन न करें; पूछें कि क्या उसका उचित निश्चित बाज़ार मूल्य है और क्या स्थिति दुर्लभ व असाधारण है। दोनों पूरे हों तभी खुला सौदा आएगा, वरना डिफ़ॉल्ट IRC 453 किस्त पद्धति है। दूसरी: खुले सौदे का हिसाब याद रखें — संचयी प्राप्तियाँ पहले basis वसूलती हैं, पूर्ण वसूली तक आय शून्य, उसके बाद हर राशि लाभ। तीसरी: खुला सौदा असंभव मूल्यांकन की राहत है, सामान्य सौदों का कर टालने का औज़ार नहीं। स्मरण-पंक्ति: Logan का द्वार केवल उसी चरम मामले के लिए खुला है जिसका मूल्य न निकल सके; पहले पूँजी, फिर लाभ। (व्यक्तिगत अध्ययन नोट; कर सलाह नहीं है।)

पूरक रूप से, वसूली क्रम सिखाने वाला एक उदाहरण (रचित उदाहरण)। मान लें आधार (basis) 10,000 डॉलर है और प्रति टन 0.60 डॉलर मिलता है: पहले वर्ष मिले 6,000 डॉलर पूरी तरह आधार-वसूली हैं, आय शून्य है और शेष आधार 4,000 डॉलर है। दूसरे वर्ष मिले 7,000 डॉलर पहले बचे 4,000 डॉलर आधार को भरेंगे, और अतिरिक्त 3,000 डॉलर तभी लाभ बनेगा। कर ठीक उसी क्षण शुरू होता है जब संचयी प्राप्तियाँ आधार को पार करती हैं — यही किस्त विधि से निर्णायक अंतर है, जो प्रत्येक प्राप्ति को मूलधन और लाभ में बाँटती है।
एक और पूरक: आधुनिक व्यवहार में Logan का द्वार लगभग नहीं खुलता। जब तक किसी हद तक मूल्यांकन संभव हो, न्यायालय प्रायः मूल्यांकन का रास्ता खोज लेते हैं; और जिन लेन-देनों पर धारा 453 लागू नहीं होती — माल-सूची, डीलर निपटान, सूचीबद्ध प्रतिभूतियाँ — वे किस्त विधि या खुला लेन-देन नहीं, सामान्य नियमों पर लौटते हैं। और यदि संचयी प्राप्तियाँ अंत तक आधार न भर पाएँ और अधिकार बेकार हो जाए, तो अवसूल आधार सैद्धांतिक रूप से तभी हानि माना जा सकता है जब वह बेकारी अंतिम रूप से तय हो जाए।

## 来源与声明

来源（中文）：
- Burnet v. Logan, 283 U.S. 404 (1931)，美国联邦最高法院判决：案件事实（股份出售、现金加按将来实际开采矿石每吨 60 美分的或有付款）与开放交易、先回收基数的判决要点，以判决原文为准。
- Eisner v. Macomber, 252 U.S. 189 (1920)，美国联邦最高法院判决：实现原则的源头判例，与本案的衔接关系。
- Treas. Reg. 15a.453-1(c)（分期付款销售临时法规）：开放交易限于罕见且特殊情形的口径；IRC 453 分期付款法：现代默认处理路径。条号与细节以现行官方文本为准。
- 本篇不载本案股份基数金额与累计收款总额：相关史料口径不一，故只采用每吨 60 美分这一可核对价条款，不编造具体金额。

声明（六语）：
- 中文：个人学习笔记，不构成法律、税务或医疗建议，具体适用以现行官方文本与专业意见为准。
- English: Personal study notes; not legal, tax, or medical advice. For specific matters, rely on the current official text and professional advice.
- Español (译稿·初译待校): Notas personales de estudio; no constituye asesoría legal, fiscal ni médica. Para casos concretos, rige el texto oficial vigente y el consejo profesional.
- 한국어 (초역·待校): 개인 학습 노트이며 법률·세무·의료 자문이 아닙니다. 구체적인 사안은 현행 공식 문언과 전문가 의견을 기준으로 합니다.
- Tiếng Việt (bản dịch sơ bộ·待校): Ghi chú học tập cá nhân; không phải tư vấn pháp lý, thuế hay y tế. Với trường hợp cụ thể, căn cứ vào văn bản chính thức hiện hành và ý kiến chuyên môn.
- हिन्दी (प्रारंभिक अनुवाद·待校): व्यक्तिगत अध्ययन नोट; यह कानूनी, कर या चिकित्सा सलाह नहीं है। विशिष्ट मामलों में वर्तमान आधिकारिक पाठ और पेशेवर सलाह ही मान्य है।
