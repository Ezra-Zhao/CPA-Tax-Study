# 质押与空投收入怎么报税：支配控制、第 61 条与 IRS 裁定

这篇讲什么：
- 加密资产在联邦税上先是财产（Notice 2014-21），但空投和质押奖励不是等卖出才计税：拿到并能支配的那一刻，先按普通收入进账。
- 两份裁定定下时点：Rev. Rul. 2019-24 管硬分叉后的空投，Rev. Rul. 2023-14 管质押奖励，关键词都是支配与控制（dominion and control）。
- Jarrett 案没有推翻这个口径：IRS 退了税、案子以无实际争议结案，没有留下实体先例。报税落点是 1040 问答题、Schedule 1 与日后的 Schedule D／8949。

---

## 一、先定性：财产身份与第 61 条的总收入

### 中文
起点还是 Notice 2014-21：虚拟货币在联邦税上是财产，不是货币，卖出、交换、消费都按处置财产算。但收到新币是另一回事，管的是国内税法典第 61 条 a 款：总收入指来自任何来源的全部收入。最高法院在 Glenshaw Glass 案给的框架是三条——财富有明确增加、已经清楚实现、纳税人对它有完全支配。空投和质押奖励恰好落在这个框架里：凭空多出一批自己能卖、能转的币，就是财富增加。所以它们的计税逻辑分两层：收到时先按普通收入确认，确认的金额变成这批币的成本基数；日后卖出时，再按卖财产算资本利得或损失。把两层混成一层，是这类报税最常见的错法。

### English
The starting point is still Notice 2014-21: virtual currency is property for federal tax purposes, not currency, and selling, swapping, or spending it is a disposition of property. Receiving new units is a different question, governed by section 61(a) of the Code: gross income means all income from whatever source derived. The Supreme Court's framework in Glenshaw Glass has three elements — an undeniable accession to wealth, clearly realized, over which the taxpayer has complete dominion. Airdrops and staking rewards fit that frame: new units you can sell or transfer are an accession to wealth. So the taxation runs in two layers. On receipt, the value is ordinary income, and the amount included becomes your basis in those units. On a later sale, you compute capital gain or loss as with any property. Collapsing the two layers into one is the most common error in this area.

### Español (初译待校)
El punto de partida sigue siendo el Aviso 2014-21: la moneda virtual es un bien (property) a efectos fiscales federales, no una moneda, y venderla, cambiarla o gastarla es disponer de un bien. Recibir unidades nuevas es otra cuestión, regida por la sección 61(a) del Código: el ingreso bruto es todo ingreso de cualquier fuente. El marco de la Corte Suprema en Glenshaw Glass tiene tres elementos: un aumento de riqueza innegable, claramente realizado, sobre el que el contribuyente tiene dominio completo. Los airdrops y las recompensas de staking encajan en ese marco: unidades nuevas que puedes vender o transferir son un aumento de riqueza. Por eso la tributación va en dos capas. Al recibirlas, el valor es ingreso ordinario, y el importe incluido se convierte en tu base en esas unidades. Al venderlas después, calculas ganancia o pérdida de capital como con cualquier bien. Fundir las dos capas en una es el error más frecuente en este tema.

### 한국어 (初译待校)
출발점은 여전히 Notice 2014-21입니다. 가상화폐는 연방세법상 화폐가 아니라 재산(property)이며, 매도·교환·소비는 재산의 처분입니다. 새 코인을 받는 문제는 따로 국내세법전 제61조 a항이 다룹니다. 총소득이란 어떤 원천에서 생겼든 모든 소득을 말합니다. Glenshaw Glass 판결의 틀은 세 가지입니다. 부의 명백한 증가, 명확한 실현, 그리고 납세자의 완전한 지배입니다. 에어드롭과 스테이킹 보상은 이 틀에 들어갑니다. 팔거나 옮길 수 있는 새 코인이 생기는 것 자체가 부의 증가이기 때문입니다. 과세는 두 층으로 나뉩니다. 받을 때는 그 가치가 일반소득이 되고, 소득에 넣은 금액이 그 코인의 취득원가(basis)가 됩니다. 나중에 팔 때는 재산을 팔 때처럼 자본손익을 계산합니다. 두 층을 하나로 뭉개는 것이 이 분야에서 가장 흔한 실수입니다.

### Tiếng Việt (初译待校)
Điểm khởi đầu vẫn là Thông báo 2014-21: tiền ảo là tài sản (property) về thuế liên bang, không phải tiền tệ, và việc bán, đổi hay tiêu nó là chuyển nhượng tài sản. Nhận coin mới là chuyện khác, do Điều 61(a) của Bộ luật điều chỉnh: tổng thu nhập là mọi thu nhập từ bất kỳ nguồn nào. Khung của Tòa Tối cao trong vụ Glenshaw Glass gồm ba yếu tố — tài sản tăng lên rõ ràng, đã thực hiện rõ ràng, và người nộp thuế có quyền chi phối hoàn toàn. Airdrop và phần thưởng staking vừa khung này: có thêm coin mà bạn bán hay chuyển được chính là tài sản tăng lên. Vì vậy việc đánh thuế đi theo hai lớp. Khi nhận, giá trị là thu nhập thường, và số tiền đã khai trở thành cơ sở chi phí (basis) của số coin đó. Khi bán sau này, tính lãi hoặc lỗ vốn như với mọi tài sản. Gộp hai lớp thành một là lỗi phổ biến nhất trong mảng này.

### हिन्दी (初译待校)
शुरुआत अब भी Notice 2014-21 से है: वर्चुअल करेंसी संघीय कर में मुद्रा नहीं, संपत्ति (property) है, और इसे बेचना, बदलना या खर्च करना संपत्ति का निपटान है। नए कॉइन मिलना अलग प्रश्न है, जिसे संहिता की धारा 61(a) देखती है: सकल आय का अर्थ है किसी भी स्रोत से प्राप्त सारी आय। Glenshaw Glass में सर्वोच्च न्यायालय का ढाँचा तीन तत्वों का है — संपत्ति में निर्विवाद वृद्धि, स्पष्ट रूप से realized, और करदाता का पूर्ण प्रभुत्व। एयरड्रॉप और स्टेकिंग इनाम इसी ढाँचे में बैठते हैं: नए कॉइन जिन्हें आप बेच या स्थानांतरित सकें, वही संपत्ति-वृद्धि है। इसलिए कर दो परतों में लगता है। प्राप्ति पर मूल्य सामान्य आय है, और आय में शामिल राशि उन कॉइनों का लागत आधार (basis) बन जाती है। बाद में बेचने पर, किसी भी संपत्ति की तरह पूँजी लाभ या हानि गिनी जाती है। दो परतों को एक में मिला देना इस क्षेत्र की सबसे आम ग़लती है।

---

## 二、只有硬分叉、没拿到新币：不产生收入

### 中文
Rev. Rul. 2019-24 给了两个情境，先看情境一。纳税人持有的加密货币发生硬分叉，链分成了两条、新币也产生了，但新币没有空投给他、也没有转进他拥有或控制的账户。裁定的结论是：没有总收入。道理回到第 61 条的框架——他没有收到任何新财产，财富没有增加（no accession to wealth），自然无从谈支配。要注意裁定用的词：硬分叉本身不是应税事件，它只是一个技术与治理事件；税务后果要等财产真正易手才开始。考试或实务里看到「分叉了但交易所不支持、钱包里根本没到账」，先按情境一处理，不要急着确认收入。

### English
Revenue Ruling 2019-24 sets out two situations; take Situation 1 first. A taxpayer's cryptocurrency undergoes a hard fork — the chain splits and a new cryptocurrency is created — but no units of the new currency are airdropped to the taxpayer or otherwise transferred into an account the taxpayer owns or controls. The ruling holds: no gross income. The reasoning returns to the section 61 frame — the taxpayer received no new property and has no accession to wealth, so there is nothing over which dominion could exist. Note the ruling's logic: a hard fork by itself is not a taxable event; it is a technical and governance event, and tax consequences begin only when property actually changes hands. When the facts say the fork happened but the exchange does not support the new coin and nothing reached the wallet, start with Situation 1 and do not rush to recognize income.

### Español (初译待校)
La Rev. Rul. 2019-24 plantea dos situaciones; primero la Situación 1. La criptomoneda del contribuyente sufre una bifurcación dura (hard fork): la cadena se divide y nace una moneda nueva, pero ninguna unidad de la moneda nueva se entrega por airdrop al contribuyente ni se transfiere a una cuenta que él posea o controle. La resolución concluye: no hay ingreso bruto. El razonamiento vuelve al marco de la sección 61 — el contribuyente no recibió ningún bien nuevo y no hay aumento de riqueza (no accession to wealth), así que no existe nada sobre lo que ejercer dominio. Fíjese en la lógica: una bifurcación dura por sí sola no es un hecho imponible; es un hecho técnico y de gobernanza, y las consecuencias fiscales empiezan solo cuando un bien cambia efectivamente de manos. Si los hechos dicen que hubo bifurcación pero el exchange no admite la moneda nueva y nada llegó a la billetera, empiece por la Situación 1 y no se apresure a reconocer ingreso.

### 한국어 (初译待校)
Rev. Rul. 2019-24는 두 가지 상황을 제시합니다. 먼저 상황 1입니다. 납세자가 보유한 암호화폐에 하드포크가 일어나 체인이 둘로 갈라지고 새 코인이 생겼지만, 새 코인이 납세자에게 에어드롭되지 않았고 그가 소유하거나 통제하는 계좌로도 들어오지 않았습니다. 재정의 결론은 총소득이 없다는 것입니다. 이유는 제61조의 틀로 돌아갑니다. 새 재산을 받은 적이 없으니 부의 증가(no accession to wealth)가 없고, 지배를 논할 대상 자체가 없습니다. 재정이 쓰는 논리를 기억하십시오. 하드포크 자체는 과세 사건이 아니라 기술·거버넌스 사건이며, 세금 문제는 재산이 실제로 손을 바꿀 때 시작됩니다. 포크는 됐지만 거래소가 새 코인을 지원하지 않아 지갑에 아무것도 들어오지 않았다는 사실관계라면, 상황 1부터 적용하고 서둘러 소득을 잡지 마십시오.

### Tiếng Việt (初译待校)
Rev. Rul. 2019-24 đưa ra hai tình huống; xét Tình huống 1 trước. Tiền mã hóa của người nộp thuế trải qua một hard fork — chuỗi tách làm hai và một đồng tiền mới ra đời — nhưng không có đơn vị nào của đồng tiền mới được airdrop cho người nộp thuế, cũng không được chuyển vào tài khoản mà người đó sở hữu hay kiểm soát. Phán quyết kết luận: không có tổng thu nhập. Lý do quay về khung Điều 61 — người nộp thuế không nhận tài sản mới nào và không có tăng tài sản (no accession to wealth), nên không có gì để chi phối. Hãy chú ý logic của phán quyết: bản thân hard fork không phải sự kiện chịu thuế; đó là sự kiện kỹ thuật và quản trị, và hậu quả thuế chỉ bắt đầu khi tài sản thực sự chuyển tay. Nếu tình tiết nói đã fork nhưng sàn không hỗ trợ đồng mới và ví không nhận được gì, hãy bắt đầu với Tình huống 1 và đừng vội ghi nhận thu nhập.

### हिन्दी (初译待校)
Rev. Rul. 2019-24 दो स्थितियाँ रखती है; पहले स्थिति 1 लें। करदाता की क्रिप्टोकरेंसी में hard fork होता है — शृंखला दो में बँटती है और नई करेंसी बनती है — लेकिन नई करेंसी की कोई इकाई करदाता को एयरड्रॉप नहीं होती और न ही उसके स्वामित्व या नियंत्रण वाले खाते में आती है। रूलिंग का निष्कर्ष: कोई सकल आय नहीं। तर्क धारा 61 के ढाँचे पर लौटता है — करदाता को कोई नई संपत्ति मिली ही नहीं और संपत्ति-वृद्धि (no accession to wealth) नहीं हुई, तो प्रभुत्व का प्रश्न ही नहीं उठता। रूलिंग का तर्क नोट करें: hard fork अपने आप में करयोग्य घटना नहीं है; यह तकनीकी और शासन-संबंधी घटना है, और कर परिणाम तभी शुरू होते हैं जब संपत्ति सचमुच हाथ बदले। यदि तथ्य यह कहें कि fork हुआ पर एक्सचेंज नई कॉइन का समर्थन नहीं करता और वॉलेट में कुछ नहीं आया, तो स्थिति 1 से शुरू करें और आय मानने की जल्दबाज़ी न करें।

---

## 三、硬分叉后收到空投：支配控制时点按公允价计普通收入

### 中文
情境二只多一步，结论就翻过来。硬分叉之后，新币空投进了纳税人的分布式账本地址，而且他能立即处置这批新币。裁定说：这时他取得了支配与控制（dominion and control），新币的公平市价在收到的税年计入普通收入。时点原则上是空投记录到分布式账本之时；但如果币记在不支持该新币的交易所账户里、当时根本动不了，收到时点顺延到他能转让、出售、交换或以其他方式处置之时。金额成为新币的基数。拿裁定分析里的数算一遍：原币基数多少不影响这一算，空投新币在取得支配控制时公允价合计 25 美元，就确认普通收入 25 美元，新币基数 25 美元；日后以 40 美元卖出，资本利得是 40 减 25 等于 15 美元。复算：40－25＝15，无误。

### English
Situation 2 adds one step and flips the answer. After the hard fork, units of the new cryptocurrency are airdropped into the taxpayer's distributed ledger address, and the taxpayer is able to dispose of them immediately. The ruling holds that the taxpayer then has dominion and control, and the fair market value of the new units is ordinary income in the year received. Receipt generally occurs when the airdrop is recorded on the distributed ledger; but if the units sit at an exchange that does not support the new coin and cannot be touched, receipt is deferred until the taxpayer can transfer, sell, exchange, or otherwise dispose of them. The amount included becomes the basis in the new units. Run the ruling's arithmetic: whatever the basis in the old coin, if the airdropped units are worth $25 when dominion and control is obtained, ordinary income is $25 and basis is $25; a later sale for $40 gives a capital gain of 40 minus 25, which is $15. Recheck: 40 − 25 = 15, correct.

### Español (初译待校)
La Situación 2 añade un solo paso y la respuesta se invierte. Tras la bifurcación, las unidades de la nueva criptomoneda se entregan por airdrop a la dirección del libro distribuido del contribuyente, y este puede disponer de ellas de inmediato. La resolución sostiene que entonces el contribuyente tiene dominio y control (dominion and control), y el valor de mercado de las nuevas unidades es ingreso ordinario en el año de recepción. La recepción ocurre en general cuando el airdrop se registra en el libro distribuido; pero si las unidades están en un exchange que no admite la moneda nueva y no se pueden tocar, la recepción se difiere hasta que el contribuyente pueda transferirlas, venderlas, cambiarlas o disponer de ellas de otro modo. El importe incluido se convierte en la base de las nuevas unidades. Haga el cálculo de la resolución: sea cual sea la base de la moneda antigua, si las unidades recibidas valen 25 dólares al obtenerse el dominio y control, el ingreso ordinario es 25 dólares y la base es 25 dólares; una venta posterior por 40 dólares da una ganancia de capital de 40 menos 25, es decir, 15 dólares. Comprobación: 40 − 25 = 15, correcto.

### 한국어 (初译待校)
상황 2는 한 단계만 더해지는데 결론이 뒤집힙니다. 하드포크 뒤 새 코인이 납세자의 분산원장 주소로 에어드롭되고, 납세자가 그 코인을 즉시 처분할 수 있습니다. 재정은 이때 납세자가 지배와 통제(dominion and control)를 얻었으므로, 새 코인의 공정시가(fair market value)가 받은 해의 일반소득이라고 봅니다. 수령 시점은 원칙적으로 에어드롭이 분산원장에 기록될 때입니다. 다만 코인이 새 코인을 지원하지 않는 거래소 계정에 있어 당시에는 손댈 수 없었다면, 수령은 납세자가 양도·매도·교환하거나 달리 처분할 수 있게 될 때까지 늦춰집니다. 소득에 넣은 금액이 새 코인의 원가가 됩니다. 재정의 숫자로 계산해 보겠습니다. 기존 코인의 원가와 무관하게, 지배와 통제를 얻은 시점에 에어드롭 코인의 공정시가가 합계 25달러라면 일반소득은 25달러, 원가도 25달러입니다. 나중에 40달러에 팔면 자본이득은 40 빼기 25로 15달러입니다. 재계산: 40－25＝15, 맞습니다.

### Tiếng Việt (初译待校)
Tình huống 2 chỉ thêm một bước mà kết luận đảo ngược. Sau hard fork, các đơn vị của đồng tiền mới được airdrop vào địa chỉ sổ phân tán của người nộp thuế, và người đó có thể định đoạt chúng ngay lập tức. Phán quyết cho rằng khi đó người nộp thuế có quyền chi phối và kiểm soát (dominion and control), và giá trị thị trường hợp lý của số coin mới là thu nhập thường trong năm nhận. Thời điểm nhận về nguyên tắc là khi airdrop được ghi vào sổ phân tán; nhưng nếu số coin nằm tại một sàn không hỗ trợ đồng mới và không thể động vào, thời điểm nhận được dời tới khi người nộp thuế có thể chuyển nhượng, bán, đổi hoặc định đoạt chúng theo cách khác. Số tiền đã khai trở thành cơ sở của số coin mới. Tính theo con số của phán quyết: bất kể cơ sở của đồng cũ là bao nhiêu, nếu số coin airdrop trị giá 25 đô la khi có quyền chi phối và kiểm soát, thu nhập thường là 25 đô la và cơ sở là 25 đô la; bán sau này với giá 40 đô la cho lãi vốn 40 trừ 25 bằng 15 đô la. Kiểm tra lại: 40 − 25 = 15, đúng.

### हिन्दी (初译待校)
स्थिति 2 में केवल एक कदम बढ़ता है और उत्तर पलट जाता है। Hard fork के बाद नई क्रिप्टोकरेंसी की इकाइयाँ करदाता के distributed ledger पते पर एयरड्रॉप होती हैं, और करदाता उन्हें तुरंत निपटा सकता है। रूलिंग कहती है कि तब करदाता के पास प्रभुत्व व नियंत्रण (dominion and control) है, और नई इकाइयों का उचित बाज़ार मूल्य प्राप्ति वाले वर्ष में सामान्य आय है। प्राप्ति सामान्यतः तब होती है जब एयरड्रॉप distributed ledger पर दर्ज हो; लेकिन यदि इकाइयाँ ऐसे एक्सचेंज पर हों जो नई कॉइन का समर्थन नहीं करता और उन्हें छुआ ही न जा सके, तो प्राप्ति तब तक टलती है जब तक करदाता उन्हें स्थानांतरित, बेच, बदल या अन्यथा निपटा न सके। आय में शामिल राशि नई इकाइयों का आधार बन जाती है। रूलिंग के अंक चलाएँ: पुरानी कॉइन का आधार कुछ भी हो, यदि प्रभुत्व व नियंत्रण मिलने पर एयरड्रॉप इकाइयों का मूल्य $25 है, तो सामान्य आय $25 और आधार $25 है; बाद में $40 में बिक्री पर पूँजी लाभ 40 घटा 25 अर्थात $15 है। पुनः जाँच: 40 − 25 = 15, सही।

---

## 四、质押奖励：Rev. Rul. 2023-14 与现金法纳税人

### 中文
质押走同一把尺子。Rev. Rul. 2023-14（2023 年 7 月 31 日发布）设定的事实是：现金收付制（cash method）纳税人把币押在权益证明（proof-of-stake）链上做验证，拿到验证奖励。裁定结论：奖励的公平市价，在纳税人取得支配与控制的那个税年计入总收入；公允价按取得支配与控制之日、之时点确定。自己跑节点质押和通过中心化交易所质押，结论一样。奖励若还在锁定期、提不出也转不了，支配与控制尚未取得，收入时点随之往后。算例：某日取得可自由处置的质押奖励 10 个币，当时单价 5 美元，普通收入是 10 乘 5 等于 50 美元，这批币基数 50 美元、每个 5 美元；日后每个以 8 美元卖出，资本利得是（8－5）乘 10 等于 30 美元，持有期从取得支配与控制之日算起。复算：10×5＝50，（8－5）×10＝30，无误。

### English
Staking is measured with the same ruler. Revenue Ruling 2023-14, issued July 31, 2023, posits a cash-method taxpayer who stakes cryptocurrency on a proof-of-stake blockchain and receives validation rewards. The holding: the fair market value of the rewards is included in gross income in the taxable year the taxpayer gains dominion and control over them, with fair market value determined as of the date and time dominion and control is gained. The result is the same whether the taxpayer stakes directly or through a centralized exchange. If rewards are still locked and can neither be withdrawn nor transferred, dominion and control has not yet been gained, and the income point moves with it. Example: on a given day the taxpayer gains freely disposable staking rewards of 10 units priced at $5 each, so ordinary income is 10 times 5, or $50, and the basis in those units is $50, $5 per unit. A later sale at $8 per unit gives a capital gain of (8 − 5) times 10, or $30, with the holding period running from the date dominion and control was gained. Recheck: 10 × 5 = 50 and (8 − 5) × 10 = 30, correct.

### Español (初译待校)
El staking se mide con la misma regla. La Rev. Rul. 2023-14, emitida el 31 de julio de 2023, plantea un contribuyente de método de caja (cash method) que deposita criptomoneda en una cadena de prueba de participación (proof-of-stake) y recibe recompensas de validación. Conclusión: el valor de mercado de las recompensas se incluye en el ingreso bruto en el año fiscal en que el contribuyente obtiene dominio y control sobre ellas, y el valor se determina en la fecha y el momento en que se obtiene ese dominio y control. El resultado es el mismo si se hace staking directamente o a través de un exchange centralizado. Si las recompensas siguen bloqueadas y no pueden retirarse ni transferirse, el dominio y control aún no existe y el momento del ingreso se desplaza con él. Ejemplo: un día el contribuyente obtiene 10 unidades de recompensa libremente disponibles a 5 dólares cada una; el ingreso ordinario es 10 por 5, es decir, 50 dólares, y la base de esas unidades es 50 dólares, 5 por unidad. Una venta posterior a 8 dólares por unidad da una ganancia de capital de (8 − 5) por 10, es decir, 30 dólares, y el período de tenencia corre desde la fecha en que se obtuvo el dominio y control. Comprobación: 10 × 5 = 50 y (8 − 5) × 10 = 30, correcto.

### 한국어 (初译待校)
스테이킹도 같은 자로 잽니다. 2023년 7월 31일에 나온 Rev. Rul. 2023-14의 사실관계는 현금주의(cash method) 납세자가 지분증명(proof-of-stake) 체인에 코인을 맡겨 검증 보상을 받는 경우입니다. 결론은 이렇습니다. 보상의 공정시가는 납세자가 그 보상에 대한 지배와 통제를 얻은 과세연도에 총소득에 들어가며, 공정시가는 지배와 통제를 얻은 날짜와 시점을 기준으로 정합니다. 직접 노드를 돌려 스테이킹하든 중앙화 거래소를 통하든 결론은 같습니다. 보상이 아직 잠겨 있어 인출도 양도도 안 된다면 지배와 통제를 아직 얻지 못한 것이므로 소득 시점도 함께 늦춰집니다. 예시: 어느 날 자유롭게 처분할 수 있는 스테이킹 보상 10개를 받았고 당시 단가가 5달러라면, 일반소득은 10 곱하기 5로 50달러이고, 이 코인들의 원가는 50달러, 개당 5달러입니다. 나중에 개당 8달러에 팔면 자본이득은 (8－5) 곱하기 10으로 30달러이며, 보유 기간은 지배와 통제를 얻은 날부터 셉니다. 재계산: 10×5＝50, (8－5)×10＝30, 맞습니다.

### Tiếng Việt (初译待校)
Staking dùng cùng một thước đo. Rev. Rul. 2023-14, ban hành ngày 31/7/2023, đặt trường hợp người nộp thuế theo phương pháp tiền mặt (cash method) đem tiền mã hóa đi staking trên chuỗi bằng chứng cổ phần (proof-of-stake) và nhận phần thưởng xác thực. Kết luận: giá trị thị trường hợp lý của phần thưởng được tính vào tổng thu nhập trong năm tính thuế mà người nộp thuế có quyền chi phối và kiểm soát chúng, và giá trị được xác định tại ngày và thời điểm có quyền chi phối và kiểm soát. Kết quả như nhau dù staking trực tiếp hay qua sàn tập trung. Nếu phần thưởng còn bị khóa, không rút cũng không chuyển được, thì quyền chi phối và kiểm soát chưa hình thành và thời điểm tính thu nhập dời theo. Ví dụ: một ngày người nộp thuế nhận 10 đơn vị phần thưởng staking có thể định đoạt tự do, giá 5 đô la mỗi đơn vị, thì thu nhập thường là 10 nhân 5 bằng 50 đô la, và cơ sở của số coin này là 50 đô la, 5 đô la mỗi đơn vị. Bán sau này với giá 8 đô la mỗi đơn vị cho lãi vốn (8 − 5) nhân 10 bằng 30 đô la, và thời gian nắm giữ tính từ ngày có quyền chi phối và kiểm soát. Kiểm tra lại: 10 × 5 = 50 và (8 − 5) × 10 = 30, đúng.

### हिन्दी (初译待校)
स्टेकिंग भी उसी पैमाने से मापी जाती है। Rev. Rul. 2023-14, जो 31 जुलाई 2023 को जारी हुई, नकद-विधि (cash method) करदाता की स्थिति रखती है जो proof-of-stake शृंखला पर क्रिप्टोकरेंसी stake करके सत्यापन इनाम पाता है। निष्कर्ष: इनामों का उचित बाज़ार मूल्य उस कर-वर्ष में सकल आय में शामिल होता है जिसमें करदाता उन पर प्रभुत्व व नियंत्रण पाता है, और मूल्य उसी तिथि व समय पर तय होता है जब प्रभुत्व व नियंत्रण मिला। परिणाम एक ही है चाहे करदाता सीधे stake करे या केंद्रीकृत एक्सचेंज के माध्यम से। यदि इनाम अभी लॉक हैं और न निकाले जा सकें न स्थानांतरित, तो प्रभुत्व व नियंत्रण अभी नहीं मिला और आय का समय भी उसी के साथ खिसकता है। उदाहरण: किसी दिन करदाता को स्वतंत्र रूप से निपटान योग्य 10 स्टेकिंग इनाम मिलते हैं, कीमत $5 प्रति इकाई, तो सामान्य आय 10 गुणा 5 अर्थात $50 है, और इन इकाइयों का आधार $50 है, $5 प्रति इकाई। बाद में $8 प्रति इकाई पर बिक्री से पूँजी लाभ (8 − 5) गुणा 10 अर्थात $30 होगा, और धारण अवधि प्रभुत्व व नियंत्रण मिलने की तिथि से चलेगी। पुनः जाँच: 10 × 5 = 50 और (8 − 5) × 10 = 30, सही।

---

## 五、Jarrett 案：退了税，不等于立了先例

### 中文
反对这个口径的人常举 Jarrett 案。Joshua Jarrett 夫妇就 2019 年质押得到的新币主张：质押奖励是纳税人自己新造出来的财产（newly created property），应当等出售时才课税，收到当年不算收入。他们起诉后，IRS 把那一年的税全额退了，法院随即以争议已无实际意义（moot）驳回案件，自始至终没有就「质押奖励算不算收入」作实体判决。退税是 IRS 的个案处理，不是对法律问题的让步，更没有约束后来案件的先例效力。紧接着 IRS 在 2023-14 里把立场写死：收到并取得支配控制时计收入。备考和实务引用 Jarrett 时，口径只能到这里——它证明有人挑战过，不证明挑战成功了。按现行 IRS 口径报税、同时保留记录和争议空间，才是稳妥位置。

### English
Opponents of this treatment often cite the Jarrett case. Joshua Jarrett and his spouse argued that the new units he received from staking in 2019 were property he had newly created himself, taxable only when sold, not income on receipt. After they sued, the IRS refunded the tax for that year in full, and the court then dismissed the case as moot; at no point did any court decide on the merits whether staking rewards are income. A refund is case-specific handling by the IRS, not a concession on the legal question, and it carries no precedential force for later cases. The IRS then wrote its position into Revenue Ruling 2023-14: income when the rewards are received and dominion and control is gained. When citing Jarrett in an exam or in practice, the statement can go only this far — it proves the position was challenged, not that the challenge succeeded. Filing under the current IRS position while keeping records and preserving the dispute is the safe posture.

### Español (初译待校)
Quienes se oponen a este tratamiento suelen citar el caso Jarrett. Joshua Jarrett y su cónyuge sostuvieron que las unidades nuevas que recibió por staking en 2019 eran un bien creado por él mismo (newly created property), gravable solo al venderse y no ingreso al recibirse. Tras la demanda, el IRS devolvió íntegramente el impuesto de ese año, y el tribunal desestimó el caso por falta de objeto (moot); ningún tribunal decidió nunca el fondo de si las recompensas de staking son ingreso. Una devolución es un trato individual del IRS, no una concesión sobre la cuestión jurídica, y no tiene fuerza de precedente para casos posteriores. Acto seguido, el IRS fijó su posición en la Rev. Rul. 2023-14: ingreso cuando las recompensas se reciben y se obtiene dominio y control. Al citar Jarrett en un examen o en la práctica, la afirmación solo puede llegar hasta aquí: prueba que la posición fue impugnada, no que la impugnación prosperara. Declarar según la posición vigente del IRS, guardando los registros y preservando la disputa, es la postura segura.

### 한국어 (初译待校)
이 취급에 반대하는 사람들이 자주 드는 사례가 Jarrett 사건입니다. Joshua Jarrett 부부는 2019년에 스테이킹으로 받은 새 코인에 대해, 스테이킹 보상은 납세자 스스로 새로 만든 재산(newly created property)이므로 받을 때가 아니라 팔 때 과세해야 한다고 주장했습니다. 소송이 제기되자 IRS는 그 해 세금을 전액 환급했고, 법원은 분쟁의 실익이 사라졌다(moot)며 사건을 각하했습니다. 법원이 스테이킹 보상이 소득인지 실체적으로 판단한 적은 처음부터 끝까지 없었습니다. 환급은 IRS의 개별 사건 처리일 뿐 법률 문제에 대한 양보가 아니며, 이후 사건을 구속하는 판례 효력도 없습니다. 이어서 IRS는 2023-14 재정에서 입장을 못 박았습니다. 보상을 받고 지배와 통제를 얻은 때 소득이라는 것입니다. 시험이나 실무에서 Jarrett를 인용할 때 서술은 여기까지만 가능합니다. 도전이 있었다는 것을 보여 줄 뿐, 도전이 성공했다는 것을 보여 주지는 않습니다. 현행 IRS 입장에 따라 신고하면서 기록을 남기고 다툼의 여지를 보존하는 것이 안전한 자세입니다.

### Tiếng Việt (初译待校)
Người phản đối cách xử lý này thường dẫn vụ Jarrett. Vợ chồng Joshua Jarrett lập luận rằng số coin mới ông nhận từ staking năm 2019 là tài sản do chính ông mới tạo ra (newly created property), chỉ chịu thuế khi bán, chứ không phải thu nhập khi nhận. Sau khi họ kiện, IRS hoàn lại toàn bộ số thuế của năm đó, và tòa án liền bác vụ kiện vì tranh chấp không còn ý nghĩa thực tế (moot); từ đầu đến cuối không tòa nào phán quyết về thực chất việc phần thưởng staking có phải thu nhập hay không. Hoàn thuế là cách xử lý riêng của IRS cho một vụ việc, không phải nhượng bộ về vấn đề pháp lý, và không có hiệu lực tiền lệ cho các vụ sau. Ngay sau đó IRS ghi chặt lập trường trong Rev. Rul. 2023-14: thu nhập khi nhận phần thưởng và có quyền chi phối và kiểm soát. Khi dẫn Jarrett trong bài thi hay thực hành, câu nói chỉ được đến mức này — nó chứng minh lập trường từng bị thách thức, không chứng minh thách thức đã thành công. Khai theo lập trường hiện hành của IRS, đồng thời giữ hồ sơ và bảo lưu tranh chấp, là tư thế an toàn.

### हिन्दी (初译待校)
इस व्यवहार के विरोधी अक्सर Jarrett मामले का हवाला देते हैं। Joshua Jarrett और उनकी पत्नी ने तर्क दिया कि 2019 में स्टेकिंग से मिले नए कॉइन स्वयं उनके द्वारा नव-निर्मित संपत्ति (newly created property) हैं, जो केवल बिक्री पर करयोग्य होनी चाहिए, प्राप्ति पर आय नहीं। मुक़दमे के बाद IRS ने उस वर्ष का कर पूरा लौटा दिया, और अदालत ने विवाद को निरर्थक (moot) कहकर मामला ख़ारिज कर दिया; किसी भी अदालत ने कभी इस मूल प्रश्न पर निर्णय नहीं दिया कि स्टेकिंग इनाम आय है या नहीं। कर-वापसी IRS का एक मामले-विशेष का निपटारा है, कानूनी प्रश्न पर रियायत नहीं, और बाद के मामलों के लिए उसका कोई पूर्वनिर्णय-बल नहीं है। इसके बाद IRS ने Rev. Rul. 2023-14 में अपना रुख पक्का लिखा: इनाम प्राप्त होने और प्रभुत्व व नियंत्रण मिलने पर आय। परीक्षा या व्यवहार में Jarrett का हवाला देते समय कथन केवल यहीं तक जा सकता है — यह साबित करता है कि रुख को चुनौती दी गई थी, यह नहीं कि चुनौती सफल हुई। वर्तमान IRS रुख के अनुसार दाखिल करना, रिकॉर्ड रखना और विवाद सुरक्षित रखना ही सुरक्षित स्थिति है।

---

## 六、申报与记录：1040 问答题、Schedule 1 与基数承接，加州一句

### 中文
落点按顺序记。第一，Form 1040 首页的数字资产问题照实答：当年收到过空投或质押奖励，就勾「是」。第二，普通收入层：空投与质押奖励的美元金额一般进 Schedule 1（Form 1040）的「其他收入」一行，并写明来源，如 staking rewards、airdrop，金额以取得支配与控制时点的公允价为准。第三，基数承接：确认过收入的金额就是这批币的基数，取得日就是取得支配与控制之日；日后卖出、交换或消费，进 Form 8949 并汇总到 Schedule D，按持有期分长短期。第四，记录从收到那天留：日期与时点、数量、当时美元公允价及其来源、平台或钱包地址、交易编号；价格日后暴跌不改当年的收入确认，只能在卖出时体现为资本损失。加州方面，FTB 对加密资产大体跟随联邦的财产处理口径，但加州对资本利得没有优惠税率，卖出利得按普通收入的累进税率征税，联邦那套长短期优惠不要搬到州表上。

### English
File in this order. First, answer the digital-asset question on page 1 of Form 1040 truthfully: if you received an airdrop or staking rewards during the year, check Yes. Second, the ordinary-income layer: the dollar amount of airdrop and staking rewards generally goes on Schedule 1 (Form 1040) as other income, labeled by source, such as staking rewards or airdrop, valued at fair market value when dominion and control was obtained. Third, basis carryover: the amount included in income is the basis in those units, and the acquisition date is the date dominion and control was gained; a later sale, swap, or spend goes on Form 8949, summarized on Schedule D, split into short-term and long-term by holding period. Fourth, keep records from the day of receipt: date and time, quantity, the dollar fair market value and its source, the platform or wallet address, and the transaction ID. A later price crash does not rewrite that year's income — it shows up only as a capital loss when the units are sold. In California, the FTB generally follows the federal property treatment of crypto assets, but California gives capital gains no preferential rate: gains on a sale are taxed at ordinary progressive rates, so do not carry the federal long-term preference onto the state return.

### Español (初译待校)
Declare en este orden. Primero, responda con veracidad la pregunta sobre activos digitales de la primera página del Formulario 1040: si durante el año recibió un airdrop o recompensas de staking, marque Sí. Segundo, la capa de ingreso ordinario: el importe en dólares de airdrops y recompensas de staking va en general al Schedule 1 (Formulario 1040) como otros ingresos, indicando la fuente, por ejemplo staking rewards o airdrop, valorado al valor de mercado del momento en que se obtuvo dominio y control. Tercero, la base se traslada: el importe incluido en el ingreso es la base de esas unidades, y la fecha de adquisición es la fecha en que se obtuvo el dominio y control; una venta, cambio o gasto posterior va al Formulario 8949, resumido en el Schedule D, separado en corto y largo plazo según el período de tenencia. Cuarto, guarde registros desde el día de la recepción: fecha y hora, cantidad, valor de mercado en dólares y su fuente, plataforma o dirección de billetera, e identificador de la transacción. Una caída posterior del precio no reescribe el ingreso de ese año: solo aparece como pérdida de capital cuando las unidades se venden. En California, la FTB sigue en general el tratamiento federal de bien para los criptoactivos, pero California no da tipo preferente a las ganancias de capital: la ganancia de una venta tributa a los tipos progresivos ordinarios, así que no traslade la preferencia federal de largo plazo a la declaración estatal.

### 한국어 (初译待校)
신고 순서는 이렇게 기억하십시오. 첫째, Form 1040 첫 면의 디지털 자산 질문에 사실대로 답합니다. 그해 에어드롭이나 스테이킹 보상을 받았다면 '예'에 표시합니다. 둘째, 일반소득 층입니다. 에어드롭과 스테이킹 보상의 달러 금액은 일반적으로 Schedule 1(Form 1040)의 기타소득 줄에 staking rewards, airdrop처럼 출처를 적어 넣으며, 금액은 지배와 통제를 얻은 시점의 공정시가 기준입니다. 셋째, 원가 승계입니다. 소득에 넣은 금액이 그 코인의 원가가 되고, 취득일은 지배와 통제를 얻은 날입니다. 이후 매도·교환·소비는 Form 8949에 올리고 Schedule D로 합산하되 보유 기간에 따라 단기와 장기로 나눕니다. 넷째, 기록은 받은 날부터 남깁니다. 날짜와 시점, 수량, 당시 달러 공정시가와 그 출처, 플랫폼이나 지갑 주소, 거래 번호가 필요합니다. 나중에 가격이 폭락해도 그해의 소득 확인은 바뀌지 않고, 팔 때 자본손실로만 나타납니다. 캘리포니아에서는 FTB가 암호자산에 대해 대체로 연방의 재산 취급을 따르지만, 자본이득에 우대세율이 없어 매도 이득은 일반 누진세율로 과세됩니다. 연방의 장기 우대를 주 신고서에 그대로 가져오면 안 됩니다.

### Tiếng Việt (初译待校)
Khai theo thứ tự này. Một, trả lời trung thực câu hỏi về tài sản số ở trang đầu Form 1040: nếu trong năm bạn nhận airdrop hoặc phần thưởng staking, hãy chọn Có. Hai, lớp thu nhập thường: số tiền đô la của airdrop và phần thưởng staking thường vào Schedule 1 (Form 1040) ở dòng thu nhập khác, ghi rõ nguồn như staking rewards hay airdrop, định giá theo giá trị thị trường tại thời điểm có quyền chi phối và kiểm soát. Ba, chuyển tiếp cơ sở: số tiền đã tính vào thu nhập chính là cơ sở của số coin đó, và ngày mua là ngày có quyền chi phối và kiểm soát; việc bán, đổi hay tiêu sau này vào Form 8949, tổng hợp sang Schedule D, chia ngắn hạn và dài hạn theo thời gian nắm giữ. Bốn, giữ hồ sơ từ ngày nhận: ngày và giờ, số lượng, giá trị thị trường bằng đô la và nguồn của nó, nền tảng hoặc địa chỉ ví, và mã giao dịch. Giá sụt mạnh sau này không viết lại thu nhập của năm đó — nó chỉ thể hiện thành lỗ vốn khi bán coin. Tại California, FTB nhìn chung theo cách xử lý tài sản của liên bang đối với tài sản mã hóa, nhưng California không cho lãi vốn hưởng thuế suất ưu đãi: lãi khi bán chịu thuế theo thuế suất lũy tiến thường, nên đừng mang ưu đãi dài hạn của liên bang sang tờ khai bang.

### हिन्दी (初译待校)
इस क्रम से दाखिल करें। पहला, Form 1040 के पहले पृष्ठ के डिजिटल-संपत्ति प्रश्न का उत्तर सच दें: यदि वर्ष में एयरड्रॉप या स्टेकिंग इनाम मिला हो, तो Yes चुनें। दूसरा, सामान्य-आय परत: एयरड्रॉप और स्टेकिंग इनामों की डॉलर राशि सामान्यतः Schedule 1 (Form 1040) में अन्य आय के रूप में जाती है, स्रोत लिखकर — जैसे staking rewards या airdrop — और मूल्य प्रभुत्व व नियंत्रण मिलने के समय के उचित बाज़ार मूल्य पर। तीसरा, आधार का आगे बढ़ना: आय में शामिल राशि ही उन इकाइयों का आधार है, और अधिग्रहण तिथि वही है जब प्रभुत्व व नियंत्रण मिला; बाद की बिक्री, अदला-बदली या खर्च Form 8949 पर आता है, Schedule D में सारांशित होता है, और धारण अवधि से अल्पकालिक व दीर्घकालिक में बँटता है। चौथा, प्राप्ति के दिन से रिकॉर्ड रखें: तिथि व समय, मात्रा, उस समय का डॉलर उचित मूल्य और उसका स्रोत, प्लेटफ़ॉर्म या वॉलेट पता, और लेन-देन आईडी। बाद में कीमत गिरना उस वर्ष की आय को नहीं बदलता — वह केवल बिक्री पर पूँजी हानि के रूप में दिखता है। कैलिफ़ोर्निया में FTB क्रिप्टो संपत्तियों पर मोटे तौर पर संघीय संपत्ति-उपचार मानती है, लेकिन पूँजी लाभ को कोई तरजीही दर नहीं मिलती: बिक्री का लाभ सामान्य प्रगतिशील दरों से करयोग्य है, इसलिए संघीय दीर्घकालिक छूट को राज्य रिटर्न पर न लाएँ।

---

## 免责声明（六语）

*声明：本篇为个人学习笔记，不构成税务、财务或法律建议。具体事务请咨询持牌 CPA 或税务律师。*
*Disclaimer: This article is a personal study note and does not constitute tax, financial, or legal advice. For a specific matter, consult a licensed CPA or tax attorney.*
*Notas personales de estudio; no constituyen asesoría fiscal, financiera ni legal. Para asuntos concretos, consulte a un CPA o abogado fiscal con licencia. (初译待校)*
*개인 학습 노트이며 세무·재무·법률 자문이 아닙니다. 구체적인 사안은 자격 있는 CPA나 세무 변호사에게 상담하십시오. (初译待校)*
*Ghi chú học tập cá nhân, không cấu thành tư vấn thuế, tài chính hay pháp lý. Với việc cụ thể, hãy tham vấn CPA hoặc luật sư thuế có giấy phép. (初译待校)*
*यह व्यक्तिगत अध्ययन नोट है और कर, वित्तीय या कानूनी सलाह नहीं है। किसी विशिष्ट मामले के लिए लाइसेंस-प्राप्त CPA या कर वकील से परामर्श करें। (初译待校)*

## 来源 / Sources

- 《国内收入法典》第 61 条 a 款：总收入的一般定义；Commissioner v. Glenshaw Glass Co., 348 U.S. 426 (1955)：财富增加、清楚实现、完全支配三要素。
- IRS Notice 2014-21：虚拟货币在联邦税上按财产处理。
- IRS Rev. Rul. 2019-24（2019-10-09 发布）：情境一硬分叉未收到新币不产生总收入；情境二硬分叉后空投、取得支配与控制时按公允价计普通收入，收入额为新币基数；交易所不支持新币时收到时点顺延至可处置之时。
- IRS Rev. Rul. 2023-14（2023-07-31 发布）：现金法纳税人的质押验证奖励，在取得支配与控制的税年按当时公允价计入总收入，直接质押与经交易所质押同口径。
- Jarrett v. United States（M.D. Tenn.）：IRS 全额退还 2019 年税款后，案件以 moot 驳回，无实体判决、无先例效力。
- IRS Form 1040 数字资产问题、Schedule 1「其他收入」、Form 8949 与 Schedule D：两层申报的落点。
- 加州 FTB 口径：加密资产大体跟随联邦财产处理；加州对资本利得无优惠税率、按普通累进税率征税。

## 补译增量（2026-11-12 23:55轮）

### 한국어 (初译待校)

두 층 과세와 에어드롭 계산예를 보탭니다. 새 코인을 받는 일은 두 층으로 과세됩니다. 받을 때는 공정시가만큼이 일반소득이 되고, 소득에 넣은 금액이 그대로 그 코인의 취득원가(basis)가 됩니다. 나중에 팔 때는 재산을 팔 때처럼 자본손익을 계산합니다. 두 층을 하나로 뭉개는 것이 이 분야에서 가장 흔한 실수입니다. 재정의 숫자로 계산하면, 지배와 통제를 얻은 시점에 에어드롭 코인의 공정시가가 합계 25달러라면 일반소득은 25달러, 원가도 25달러입니다. 나중에 40달러에 팔면 자본이득은 40 빼기 25로 15달러입니다.

신고 순서와 기록 항목을 보탭니다. 첫째, Form 1040 첫 면의 디지털 자산 질문에 사실대로 답하고, 그해 에어드롭이나 스테이킹 보상을 받았다면 '예'에 표시합니다. 둘째, 일반소득 층의 금액은 Schedule 1(Form 1040)의 기타소득 줄에 staking rewards, airdrop처럼 출처를 적어 넣습니다. 셋째, 소득에 넣은 금액이 원가가 되고 취득일은 지배와 통제를 얻은 날이며, 이후의 매도·교환·소비는 Form 8949에 올리고 Schedule D로 합산합니다. 넷째, 기록은 받은 날부터 남깁니다. 날짜와 시점, 수량, 당시 달러 공정시가와 그 출처, 플랫폼이나 지갑 주소, 거래 번호가 필요합니다. 나중에 가격이 폭락해도 그해의 소득 확인은 바뀌지 않고, 팔 때 자본손실로만 나타납니다.

### Tiếng Việt (初译待校)

Bổ sung cách đánh thuế hai lớp và ví dụ tính airdrop. Nhận coin mới bị đánh thuế theo hai lớp: khi nhận, giá trị thị trường hợp lý là thu nhập thường, và số tiền đã tính vào thu nhập trở thành cơ sở chi phí (basis) của số coin đó; khi bán sau này, tính lãi hoặc lỗ vốn như bán mọi tài sản khác. Gộp hai lớp thành một là lỗi phổ biến nhất trong mảng này. Tính theo con số của phán quyết: nếu số coin airdrop trị giá tổng cộng 25 đô la khi có quyền chi phối và kiểm soát, thu nhập thường là 25 đô la và cơ sở cũng là 25 đô la; bán sau này với giá 40 đô la cho lãi vốn 40 trừ 25 bằng 15 đô la.

Bổ sung thứ tự khai và các mục hồ sơ. Một, trả lời trung thực câu hỏi về tài sản số ở trang đầu Form 1040: nếu trong năm bạn nhận airdrop hoặc phần thưởng staking, hãy chọn Có. Hai, số tiền ở lớp thu nhập thường vào Schedule 1 (Form 1040) ở dòng thu nhập khác, ghi rõ nguồn như staking rewards hay airdrop. Ba, số tiền đã tính vào thu nhập là cơ sở của số coin đó, ngày mua là ngày có quyền chi phối và kiểm soát, và việc bán, đổi hay tiêu sau này vào Form 8949, tổng hợp sang Schedule D. Bốn, giữ hồ sơ từ ngày nhận: ngày và giờ, số lượng, giá trị thị trường bằng đô la và nguồn của nó, nền tảng hoặc địa chỉ ví, và mã giao dịch. Giá sụt mạnh sau này không viết lại thu nhập của năm đó — nó chỉ thể hiện thành lỗ vốn khi bán coin.

### हिन्दी (初译待校)

दो-परत कराधान और एयरड्रॉप का गणना-उदाहरण जोड़ते हैं। नए कॉइन मिलना दो परतों में कर लगता है: प्राप्ति पर उचित बाज़ार मूल्य सामान्य आय होता है, और आय में शामिल राशि ही उन कॉइनों का लागत आधार (basis) बन जाती है; बाद में बेचने पर किसी भी संपत्ति की तरह पूँजी लाभ या हानि गिनी जाती है। दो परतों को एक में मिला देना इस क्षेत्र की सबसे आम ग़लती है। रूलिंग के अंकों से गिनें: यदि प्रभुत्व व नियंत्रण मिलने पर एयरड्रॉप इकाइयों का कुल मूल्य $25 है, तो सामान्य आय $25 और आधार भी $25 है; बाद में $40 में बिक्री पर पूँजी लाभ 40 घटा 25 अर्थात $15 है।

दाखिले का क्रम और अभिलेख की मदें जोड़ते हैं। पहला, Form 1040 के पहले पृष्ठ के डिजिटल-संपत्ति प्रश्न का उत्तर सच दें: यदि वर्ष में एयरड्रॉप या स्टेकिंग इनाम मिला हो, तो Yes चुनें। दूसरा, सामान्य-आय परत की राशि Schedule 1 (Form 1040) में अन्य आय के रूप में जाती है, स्रोत लिखकर — जैसे staking rewards या airdrop। तीसरा, आय में शामिल राशि ही उन इकाइयों का आधार है, अधिग्रहण तिथि वही है जब प्रभुत्व व नियंत्रण मिला, और बाद की बिक्री, अदला-बदली या खर्च Form 8949 पर आकर Schedule D में सारांशित होता है। चौथा, प्राप्ति के दिन से रिकॉर्ड रखें: तिथि व समय, मात्रा, उस समय का डॉलर उचित मूल्य और उसका स्रोत, प्लेटफ़ॉर्म या वॉलेट पता, और लेन-देन आईडी। बाद में कीमत गिरना उस वर्ष की आय को नहीं बदलता — वह केवल बिक्री पर पूँजी हानि के रूप में दिखता है।
