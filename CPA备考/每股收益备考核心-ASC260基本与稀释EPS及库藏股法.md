# 每股收益备考核心：ASC 260 基本与稀释 EPS 及库藏股法

这篇讲什么：
- 这篇只抓一条主线：每股收益怎么算才不丢分。基本 EPS 看分子分母的口径，稀释 EPS 看潜在普通股怎么挤进来，库藏股法和 if-converted 法是两把最常用的尺子，两类法专管参与证券。全文用同一组数字从头算到尾。
- 来源口径：以 FASB ASC 260《每股收益》为主线，股份支付与参与证券的衔接看 ASC 718，国际口径对照 IAS 33《每股收益》；文中金额均为自编教学示例。

---

## 一、基本 EPS：公式与优先股股利

### 中文

基本 EPS 只有一条公式：基本 EPS＝（净利润－优先股股利）÷加权平均普通股股数。分子是归属于普通股股东的收益，先把优先股那一份拿掉；分母不是期末股数，而是当期加权平均流通在外的普通股股数，第二节细说。

优先股股利分两种扣法，最爱设坑。累积优先股：当年股利无论有没有宣告都要扣，因为这份钱迟早归优先股股东。非累积优先股：只有已经宣告的才扣。记法是累积的按年算账、非累积的按宣告算账。题目同时给应计数和宣告数，先判累积还是非累积，再选数字。

### English

Basic EPS = (net income − preferred dividends) ÷ weighted-average common shares outstanding. The numerator is income available to common shareholders; the denominator is the period's weighted average, not the ending count.

Cumulative preferred dividends are deducted for the current period whether declared or not, because they belong to the preferred holders. Noncumulative dividends are deducted only when declared. Classify the stock first, then pick the figure. (Study translation draft — pending review.)

### Español (译稿)

EPS básico = (ingreso neto − dividendos preferentes) ÷ promedio ponderado de acciones comunes en circulación. El numerador es el ingreso disponible para los accionistas comunes; el denominador es el promedio ponderado del periodo, no el número al cierre.

Los dividendos acumulativos se restan por el periodo corriente, se hayan declarado o no, porque pertenecen a los tenedores preferentes. Los no acumulativos se restan solo cuando se declaran. Clasifique primero la acción y luego elija la cifra. (Borrador de traducción para estudio — pendiente de revisión.)

### 한국어 (초역·교정 대기)

기본 EPS 공식은 하나입니다. 기본 EPS＝(순이익－우선주 배당)÷가중평균 유통 보통주 수. 분자는 보통주주에게 귀속되는 이익이라 우선주 몫을 먼저 빼고, 분모는 기말 주식 수가 아니라 기간 가중평균입니다.

우선주 배당은 두 가지로 차감합니다. 누적우선주는 선언 여부와 관계없이 당기 배당을 차감합니다. 비누적우선주는 실제로 선언된 배당만 차감합니다. 누적주는 연도 기준, 비누적주는 선언 기준입니다. 발생액과 선언액이 함께 나오면 먼저 종류를 판단한 뒤 숫자를 고르십시오. (학습용 초역 — 교정 대기 중입니다.)

### Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

EPS cơ bản = (lợi nhuận ròng − cổ tức ưu đãi) ÷ số cổ phiếu phổ thông bình quân gia quyền đang lưu hành. Tử số là thu nhập thuộc về cổ đông phổ thông; mẫu số là bình quân gia quyền của kỳ, không phải số cuối kỳ.

Cổ tức tích lũy được trừ cho kỳ hiện tại dù đã công bố hay chưa, vì chúng thuộc về cổ đông ưu đãi. Cổ tức không tích lũy chỉ trừ khi đã công bố. Hãy phân loại cổ phiếu trước, rồi chọn con số. (Bản dịch sơ bộ phục vụ học tập — chờ hiệu đính.)

### हिन्दी (प्रारंभिक अनुवाद, समीक्षा लंबित)

मूल EPS = (शुद्ध आय − अधिमान लाभांश) ÷ भारित-औसत सामान्य शेयर। अंश सामान्य शेयरधारकों को उपलब्ध आय है; हर अवधि का भारित औसत है, अंतिम संख्या नहीं।

संचयी अधिमान लाभांश चालू अवधि के लिए घटता है, चाहे घोषित हुआ हो या नहीं, क्योंकि वह अधिमान धारकों का है। असंचयी लाभांश केवल घोषित होने पर घटता है। पहले शेयर का प्रकार तय करें, फिर संख्या चुनें। (अध्ययन हेतु प्रारंभिक अनुवाद — समीक्षा लंबित है।)

---

## 二、加权平均股数、追溯调整与贯穿演算

### 中文

分母用加权平均，因为股份流通多久就计权多久。年中增发只算发行后的权重，年中回购从回购日起退出。草稿上画时间轴、分段乘权重，比死记口诀稳。

两类变动不看时间权重，要追溯调整所有呈报期间：股票股利和股票拆股，依据是 ASC 260-10-55 的相关指引。这类变动没有新资源流入，只是把同一块饼切成更多份，以前期间的股数和 EPS 都要按新口径重算。真金白银增发的不追溯，只从发行日起计权。判断标准就一句：有没有新资源进来。

贯穿演算第一步，全篇同一家公司：净利润 $500,000，优先股股利 $50,000，加权平均股数 200,000 股。基本 EPS＝(500,000－50,000)÷200,000＝450,000÷200,000＝$2.25。这个 $2.25 是所有稀释计算的起点，稀释 EPS 只会等于或低于它。

### English

A share counts only while it was outstanding, so the denominator is time-weighted. Mid-year issues earn weight after issuance; mid-year repurchases drop out at repurchase.

Stock dividends and stock splits ignore time weighting and are adjusted retrospectively for all periods presented, under ASC 260-10-55: no new resources enter, and the same pie is cut into more slices, so prior counts and EPS are restated. A cash issue is weighted only from its issue date.

Step one: net income $500,000, preferred dividends $50,000, weighted-average shares 200,000. Basic EPS = (500,000 − 50,000) ÷ 200,000 = $2.25. Diluted EPS can only equal or fall below this figure. (Study translation draft — pending review.)

### Español (译稿)

Cada acción cuenta solo mientras estuvo en circulación, por eso el denominador se pondera por tiempo. Las emisiones de mitad de año pesan tras la emisión; las recompras salen en la fecha de recompra.

Los dividendos en acciones y los desdoblamientos (splits) ignoran la ponderación temporal y se ajustan retroactivamente en todos los periodos presentados, según la ASC 260-10-55: no entran recursos nuevos, el mismo pastel se corta en más porciones y las cifras anteriores se reexpresan. Una emisión por efectivo se pondera desde su fecha.

Primer paso: ingreso neto de $500,000, dividendos preferentes de $50,000, promedio de 200,000 acciones. EPS básico = (500,000 − 50,000) ÷ 200,000 = $2.25. El EPS diluido solo puede igualar esta cifra o quedar por debajo. (Borrador de traducción para estudio — pendiente de revisión.)

### 한국어 (초역·교정 대기)

분모가 가중평균인 이유는 주식이 유통된 기간만큼만 반영되기 때문입니다. 연중 발행 주식은 발행 이후에만 가중되고, 연중 재매입 주식은 재매입일부터 빠집니다. 시간축을 그리고 구간마다 가중하는 편이 암기보다 안정적입니다.

시간 가중을 무시하고 모든 표시 기간에 소급 적용하는 변동은 주식배당과 주식분할이며, 근거는 ASC 260-10-55입니다. 새 자원이 들어오지 않고 같은 파이를 더 나눈 것뿐이라 전기 주식 수와 EPS도 새 기준으로 재작성합니다. 현금 발행은 발행일부터만 가중합니다. 기준은 새 자원이 들어왔는가입니다.

관통 예시 첫 단계입니다. 순이익 $500,000, 우선주 배당 $50,000, 가중평균 200,000주. 기본 EPS＝(500,000－50,000)÷200,000＝450,000÷200,000＝$2.25입니다. 모든 희석 계산은 $2.25에서 출발하며, 희석 EPS는 이와 같거나 낮을 수만 있습니다. (학습용 초역 — 교정 대기 중입니다.)

### Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

Mỗi cổ phiếu chỉ được tính khi nó đang lưu hành, nên mẫu số tính trọng số theo thời gian. Cổ phiếu phát hành giữa năm chỉ tính sau ngày phát hành; cổ phiếu mua lại rời phép tính từ ngày mua lại.

Cổ tức bằng cổ phiếu và tách cổ phiếu bỏ qua trọng số thời gian và phải điều chỉnh hồi tố cho mọi kỳ được trình bày, theo ASC 260-10-55: không có nguồn lực mới, cùng một chiếc bánh được cắt thành nhiều phần hơn, nên số liệu các kỳ trước trình bày lại. Đợt phát hành thu tiền chỉ tính từ ngày phát hành.

Bước một: lợi nhuận ròng $500,000, cổ tức ưu đãi $50,000, bình quân 200,000 cổ phiếu. EPS cơ bản = (500,000 − 50,000) ÷ 200,000 = $2.25. EPS pha loãng chỉ có thể bằng hoặc thấp hơn con số này. (Bản dịch sơ bộ phục vụ học tập — chờ hiệu đính.)

### हिन्दी (प्रारंभिक अनुवाद, समीक्षा लंबित)

शेयर केवल उतने समय गिना जाता है जितने समय वह चलन में रहा, इसलिए हर समय-भारित होता है। बीच में जारी शेयर जारी होने के बाद ही भार पाते हैं; पुनः खरीदे गए शेयर पुनः खरीद की तिथि से बाहर हो जाते हैं।

स्टॉक लाभांश और स्टॉक विभाजन समय-भार को अनदेखा करते हैं और सभी प्रस्तुत अवधियों के लिए पूर्वव्यापी समायोजित होते हैं, ASC 260-10-55 के अनुसार: कोई नया संसाधन नहीं आता, वही पाई अधिक टुकड़ों में कटती है, इसलिए पूर्व आँकड़े पुनः प्रस्तुत होते हैं। नकद निर्गम केवल उसकी तिथि से भारित होता है।

पहला चरण: शुद्ध आय $500,000, अधिमान लाभांश $50,000, भारित औसत 200,000 शेयर। मूल EPS = (500,000 − 50,000) ÷ 200,000 = $2.25। तनुकृत EPS इससे बराबर या कम ही हो सकता है। (अध्ययन हेतु प्रारंभिक अनुवाद — समीक्षा लंबित है।)

---

## 三、稀释 EPS 与库藏股法

### 中文

稀释 EPS 回答一个假设问题：稀释性潜在普通股都变成普通股，每股收益会被摊薄到多少。潜在普通股主要包括期权、认股权证、可转换债券和可转换优先股。顺序不能乱：先逐项判断稀释还是反稀释，再按稀释程度排序纳入。

期权和认股权证用库藏股法，步骤写死：假定在期初（或授予日，若更晚）全部行权，公司收到行权款；再假定用这笔钱按期间平均市价回购普通股；行权股数减可回购股数，差额是增量股数，只加分母，分子不动。平均市价高于行权价才有增量；低于行权价没人会行权，是反稀释，剔除。

接上演算：期权 20,000 份，行权价 $20，平均市价 $25。行权所得＝20,000×$20＝$400,000；可回购＝400,000÷25＝16,000 股；增量股数＝20,000－16,000＝4,000 股。无其他稀释证券时分子仍是 $450,000，分母＝200,000＋4,000＝204,000 股，稀释 EPS＝450,000÷204,000≈$2.21（四舍五入到分）。先算增量再动分母，别把 20,000 股全加进去。

### English

Diluted EPS asks how far EPS would be spread if dilutive potential common shares — options, warrants, convertible debt, convertible preferred stock — all became common shares. Test each item first, then include items by dilutive effect.

Options and warrants use the treasury stock method: assume exercise at the start of the period (or at grant, if later), receipt of the proceeds, and repurchase of shares at the average market price. Shares issued minus shares repurchasable is the incremental count, added to the denominator only. No increment arises when average price is at or below exercise price; the item is then antidilutive.

Example: 20,000 options, exercise price $20, average price $25. Proceeds = 20,000 × $20 = $400,000; repurchasable = 400,000 ÷ 25 = 16,000; incremental = 4,000 shares. Numerator $450,000; denominator 204,000; diluted EPS = 450,000 ÷ 204,000 ≈ $2.21 (nearest cent). (Study translation draft — pending review.)

### Español (译稿)

El EPS diluido pregunta hasta dónde se repartiría el EPS si las acciones potenciales dilutivas — opciones, warrants, deuda convertible, preferentes convertibles — se convirtieran en acciones comunes. Pruebe cada elemento primero; luego incorpórelos por efecto dilutivo.

Las opciones y los warrants usan el método de acciones en tesorería (treasury stock method): suponga el ejercicio al inicio del periodo (o en la concesión, si es posterior), la recepción del importe y la recompra de acciones al precio medio de mercado. Las emitidas menos las recompradas dan las acciones incrementales, solo en el denominador. No hay incremento cuando el precio medio no supera el de ejercicio; el elemento es entonces antidilutivo.

Ejemplo: 20,000 opciones, ejercicio de $20, precio medio de $25. Importe = 20,000 × $20 = $400,000; recompradas = 400,000 ÷ 25 = 16,000; incrementales = 4,000 acciones. Numerador $450,000; denominador 204,000; EPS diluido = 450,000 ÷ 204,000 ≈ $2.21 (al centavo). (Borrador de traducción para estudio — pendiente de revisión.)

### 한국어 (초역·교정 대기)

희석 EPS는 희석성 잠재적 보통주가 모두 보통주가 되면 주당이익이 얼마나 얇아지는지 묻습니다. 잠재 주식에는 옵션, 신주인수권, 전환사채, 전환우선주가 들어갑니다. 항목마다 먼저 판정하고, 희석 정도 순으로 넣으십시오.

옵션과 신주인수권은 자기주식법(treasury stock method)을 씁니다. 기간 초(부여일이 더 늦으면 부여일)에 전량 행사해 대금을 받는다고 가정하고, 그 돈으로 기간 평균 시장가격에 주식을 재매입한다고 가정합니다. 발행 주식 수에서 재매입 가능 주식 수를 뺀 값이 증분이며 분모에만 더합니다. 평균 시장가격이 행사가격보다 높아야 증분이 생기고, 낮으면 반희석이라 제외합니다.

예시를 잇습니다. 행사가격 $20, 평균 시장가격 $25인 옵션 20,000개. 행사 대금＝20,000×$20＝$400,000, 재매입 가능＝400,000÷25＝16,000주, 증분＝20,000－16,000＝4,000주입니다. 분자는 $450,000 그대로, 분모는 200,000＋4,000＝204,000주, 희석 EPS＝450,000÷204,000≈$2.21(센트 단위 반올림)입니다. 증분을 먼저 구하십시오. (학습용 초역 — 교정 대기 중입니다.)

### Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

EPS pha loãng hỏi EPS sẽ bị trải mỏng đến đâu nếu mọi cổ phiếu tiềm năng có tính pha loãng — quyền chọn, chứng quyền, nợ chuyển đổi, cổ phiếu ưu đãi chuyển đổi — đều thành cổ phiếu phổ thông. Kiểm tra từng khoản trước, rồi đưa vào theo mức độ pha loãng.

Quyền chọn và chứng quyền dùng phương pháp cổ phiếu quỹ (treasury stock method): giả định thực hiện vào đầu kỳ (hoặc ngày cấp, nếu muộn hơn), thu được tiền, và dùng tiền đó mua lại cổ phiếu theo giá bình quân của kỳ. Số phát hành trừ số mua lại được là số tăng thêm, chỉ cộng vào mẫu số. Không có số tăng thêm khi giá bình quân không cao hơn giá thực hiện; khoản đó khi ấy chống pha loãng.

Ví dụ: 20,000 quyền chọn, giá thực hiện $20, giá bình quân $25. Tiền thu = 20,000 × $20 = $400,000; mua lại được = 400,000 ÷ 25 = 16,000; tăng thêm = 4,000 cổ phiếu. Tử số $450,000; mẫu số 204,000; EPS pha loãng = 450,000 ÷ 204,000 ≈ $2.21 (đến cent). (Bản dịch sơ bộ phục vụ học tập — chờ hiệu đính.)

### हिन्दी (प्रारंभिक अनुवाद, समीक्षा लंबित)

तनुकृत EPS पूछता है कि यदि तनुकारी संभाव्य सामान्य शेयर — विकल्प, वारंट, परिवर्तनीय ऋण, परिवर्तनीय अधिमान शेयर — सभी सामान्य शेयर बन जाएँ, तो EPS कितना पतला बँटेगा। पहले हर मद को परखें, फिर तनुकरण के क्रम में शामिल करें।

विकल्पों और वारंटों पर ट्रेज़री स्टॉक विधि लगती है: अवधि के आरंभ में (या अनुदान तिथि पर, यदि बाद में हो) प्रयोग, राशि की प्राप्ति और औसत बाज़ार मूल्य पर पुनः खरीद मानें। जारी शेयरों में से पुनः खरीद योग्य घटाने पर वृद्धिशील शेयर मिलते हैं, जो केवल हर में जुड़ते हैं। औसत मूल्य प्रयोग मूल्य से ऊपर न हो तो वृद्धि नहीं मिलती; मद तब प्रतितनुकारी है।

उदाहरण: $20 प्रयोग मूल्य और $25 औसत मूल्य वाले 20,000 विकल्प। आगम = 20,000 × $20 = $400,000; पुनः खरीद योग्य = 400,000 ÷ 25 = 16,000; वृद्धिशील = 4,000 शेयर। अंश $450,000; हर 204,000; तनुकृत EPS = 450,000 ÷ 204,000 ≈ $2.21 (निकटतम सेंट तक)। (अध्ययन हेतु प्रारंभिक अनुवाद — समीक्षा लंबित है।)

---

## 四、可转换证券：if-converted 法与反稀释排序

### 中文

可转换证券不用库藏股法，用 if-converted 法，即假设已经转了。可转换债券假定在期初（或发行日，若更晚）转成普通股：分子加回税后利息，转股后利息不再付、税盾也要还原，加回额是利息×（1－税率）；分母加转股可得股数。可转换优先股同理，分子加回原来扣掉的股利，分母加转股股数；股利没有税盾，不乘（1－税率）。

纳入前逐项测反稀释：算每种证券的增量每股影响，即分子增量÷分母增量。转进来反而让 EPS 升高的就是反稀释，排除。多项并存时按增量每股影响从小到大排序，从最稀释的逐项纳入，每纳入一项重算一次，下一步会拉高 EPS 就停。硬规则一条：当期亏损时潜在普通股一律反稀释、不计入，稀释 EPS 等于基本 EPS，因为亏损摊到更多股数只会让每股亏损变小，那是美化，不是稀释。

### English

Convertible securities use the if-converted method: assume conversion at the start of the period (or at issuance, if later). For debt, add back after-tax interest — interest × (1 − tax rate) — to the numerator, and add the conversion shares to the denominator. For convertible preferred stock, add back the dividend previously deducted, with no tax factor.

Test each item by its incremental per-share effect, numerator increment ÷ denominator increment; exclude any item whose conversion would raise EPS. Rank items from most dilutive, include them one at a time, recompute each step, and stop when the next item would raise EPS. In a loss period, all potential shares are antidilutive and excluded, so diluted EPS equals basic EPS. (Study translation draft — pending review.)

### Español (译稿)

Los valores convertibles usan el método if-converted: suponer la conversión al inicio del periodo (o en la emisión, si es posterior). En la deuda, se devuelve al numerador el interés después de impuestos — interés × (1 − tasa fiscal) — y se suman al denominador las acciones de la conversión. En la preferente convertible, vuelve el dividendo antes restado, sin factor fiscal.

Pruebe cada elemento por su efecto incremental por acción, incremento del numerador ÷ incremento del denominador; excluya el que elevara el EPS al convertirse. Ordene los elementos desde el más dilutivo, incorpórelos uno a uno, recalcule en cada paso y deténgase cuando el siguiente vaya a subir el EPS. En un periodo con pérdida, todas las acciones potenciales son antidilutivas y se excluyen, así que el EPS diluido iguala al básico. (Borrador de traducción para estudio — pendiente de revisión.)

### 한국어 (초역·교정 대기)

전환증권에는 자기주식법이 아니라 if-converted 법을 씁니다. 이미 전환했다고 가정하는 방법입니다. 전환사채는 기간 초(발행일이 더 늦으면 발행일)에 전환했다고 봅니다. 분자에는 세후 이자를 다시 더하는데, 가산액은 이자×(1－세율)입니다. 이자와 세금 방패가 함께 사라지기 때문입니다. 분모에는 전환 주식 수를 더합니다. 전환우선주도 같으며, 다시 더하는 것은 앞서 차감한 배당이고 (1－세율)은 곱하지 않습니다.

넣기 전에 항목마다 증분 주당 영향, 즉 분자 증분÷분모 증분으로 반희석을 검사하십시오. 전환하면 EPS가 올라가는 항목은 제외합니다. 증권이 여러 개면 그 영향이 작은 것부터 정렬해 가장 희석적인 것부터 하나씩 넣고 매 단계 다시 계산하며, 다음 항목이 EPS를 올리면 멈춥니다. 손실 기간에는 잠재 주식을 전부 반희석으로 보아 제외하므로 희석 EPS는 기본 EPS와 같습니다. (학습용 초역 — 교정 대기 중입니다.)

### Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

Chứng khoán chuyển đổi dùng phương pháp if-converted: giả định chuyển đổi vào đầu kỳ (hoặc ngày phát hành, nếu muộn hơn). Với nợ, cộng lại vào tử số lãi sau thuế — lãi × (1 − thuế suất) — và cộng vào mẫu số số cổ phiếu khi chuyển đổi. Với cổ phiếu ưu đãi chuyển đổi, cộng lại cổ tức đã trừ trước đó, không nhân hệ số thuế.

Kiểm tra từng khoản bằng tác động tăng thêm trên mỗi cổ phiếu của nó, phần tăng tử số ÷ phần tăng mẫu số; loại khoản nào mà chuyển đổi sẽ làm EPS tăng lên. Xếp các khoản từ pha loãng nhất, đưa vào từng khoản, tính lại ở mỗi bước và dừng khi khoản tiếp theo sẽ đẩy EPS lên. Trong kỳ lỗ, mọi cổ phiếu tiềm năng đều chống pha loãng và bị loại, nên EPS pha loãng bằng EPS cơ bản. (Bản dịch sơ bộ phục vụ học tập — chờ hiệu đính.)

### हिन्दी (प्रारंभिक अनुवाद, समीक्षा लंबित)

परिवर्तनीय प्रतिभूतियों पर if-converted विधि लगती है: अवधि के आरंभ में (या निर्गम तिथि पर, यदि बाद में हो) परिवर्तन मान लें। ऋण के लिए अंश में कर-पश्चात ब्याज — ब्याज × (1 − कर दर) — वापस जोड़ें और हर में परिवर्तन वाले शेयर जोड़ें। परिवर्तनीय अधिमान शेयर के लिए पहले घटाया गया लाभांश वापस जुड़ता है, बिना कर गुणक के।

हर मद को उसके वृद्धिशील प्रति-शेयर प्रभाव, अंश की वृद्धि ÷ हर की वृद्धि, से परखें; जिस मद के परिवर्तन से EPS बढ़ जाए, उसे बाहर रखें। मदों को सबसे तनुकारी से क्रम में रखें, एक-एक करके लाएँ, हर चरण पर फिर गणना करें, और अगली मद EPS बढ़ाने लगे तो रुक जाएँ। हानि वाली अवधि में सभी संभाव्य शेयर प्रतितनुकारी होते हैं और बाहर रहते हैं, इसलिए तनुकृत EPS मूल EPS के बराबर होता है। (अध्ययन हेतु प्रारंभिक अनुवाद — समीक्षा लंबित है।)

---

## 五、两类法：参与证券与股份支付

### 中文

前面默认收益全归普通股，两类法（two-class method）处理例外：参与证券能跟普通股一起分享收益，收益就不能全算给普通股。ASC 260-10-45-59A 起的段落要求，存在参与证券时基本 EPS 用两类法：当期收益按参与权利在普通股和参与证券之间分配，未分配收益也按约定基础分摊，每类各算每股金额。常见例子是参与优先股和带参与分红安排的股份类别。

与 ASC 718 的衔接最容易漏考：未归属的股份支付奖励若带有不可没收的股利权（nonforfeitable rights to dividends），归属前就能领股利且领到不退，它就是参与证券，要用两类法分收益。股利权可没收的未归属奖励则不算。判断只看一句：归属条件没达到时，之前分到的钱要不要还。不用还，就是参与证券。稀释一侧，两类法结果要与库藏股法、if-converted 法比较，报更稀释的那个。

### English

Participating securities share earnings alongside common stock, so earnings cannot all go to the common class. From ASC 260-10-45-59A, basic EPS then uses the two-class method: earnings are allocated by participation rights, undistributed earnings are shared on the agreed basis, and each class gets its own per-share amount.

Under ASC 718, an unvested share-based award with nonforfeitable rights to dividends is a participating security: it collects dividends before vesting and keeps them even if it never vests, so earnings are allocated to it under the two-class method. Awards with forfeitable dividend rights are not participating securities. For diluted EPS, report the more dilutive of the two-class, treasury stock, and if-converted results. (Study translation draft — pending review.)

### Español (译稿)

Los valores participativos comparten las ganancias con las acciones comunes, así que la ganancia no puede ir entera a la clase común. Desde la ASC 260-10-45-59A, el EPS básico usa entonces el método de dos clases (two-class method): la ganancia se reparte según los derechos de participación, la no distribuida se comparte en la base pactada y cada clase obtiene su importe por acción.

Según la ASC 718, una concesión de pago basado en acciones aún no consolidada (unvested) con derechos no confiscables a dividendos es un valor participativo: cobra dividendos antes de consolidarse y los conserva aunque nunca se consolide, así que recibe ganancia con el método de dos clases. Las concesiones con derechos confiscables no son valores participativos. Para el EPS diluido, presente el resultado más dilutivo entre dos clases, tesorería e if-converted. (Borrador de traducción para estudio — pendiente de revisión.)

### 한국어 (초역·교정 대기)

앞 절들은 이익이 전부 보통주에 귀속된다고 가정했습니다. 이분법(two-class method)은 예외를 다룹니다. 참가증권이 보통주와 함께 이익을 나누면 이익을 전부 보통주에 줄 수 없습니다. ASC 260-10-45-59A 이하에서는 참가증권이 있을 때 기본 EPS를 이분법으로 계산합니다. 이익을 참가 권리에 따라 배분하고, 미배분 이익도 약정 기준으로 나누며, 종류별로 주당 금액을 구합니다. 예로 참가우선주와 참가 배당 약정이 있는 주식 종류가 있습니다.

ASC 718과의 연결은 놓치기 쉽습니다. 몰수 불가능한 배당권(nonforfeitable rights to dividends)을 가진 미귀속 주식기준보상 약정은 귀속 전에 배당을 받을 수 있고 귀속되지 않아도 그대로 가질 수 있어 참가증권에 해당하며, 이분법으로 이익을 배분해야 합니다. 배당권이 몰수 가능한 약정은 해당하지 않습니다. 판단은 하나입니다. 귀속에 실패하면 앞서 받은 배당을 돌려줘야 하는가. 돌려주지 않아도 되면 참가증권입니다. 희석 쪽에서는 이분법 결과와 자기주식법, if-converted 법 결과를 비교해 더 희석적인 결과를 표시합니다. (학습용 초역 — 교정 대기 중입니다.)

### Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

Chứng khoán tham gia cùng chia thu nhập với cổ phiếu phổ thông, nên thu nhập không thể gán hết cho lớp phổ thông. Từ ASC 260-10-45-59A, EPS cơ bản khi ấy dùng phương pháp hai lớp (two-class method): thu nhập được phân bổ theo quyền tham gia, phần chưa phân phối cũng được chia trên cơ sở đã thỏa thuận, và mỗi lớp có con số riêng.

Theo ASC 718, một khoản thưởng thanh toán bằng cổ phiếu chưa đủ điều kiện hưởng (unvested) mang quyền cổ tức không thể bị tịch thu (nonforfeitable) là chứng khoán tham gia: nó nhận cổ tức trước khi đủ điều kiện và giữ luôn kể cả khi không bao giờ đủ điều kiện, nên được phân bổ thu nhập theo phương pháp hai lớp. Khoản thưởng có quyền cổ tức có thể bị tịch thu thì không phải. Với EPS pha loãng, trình bày kết quả pha loãng hơn trong ba phương pháp hai lớp, cổ phiếu quỹ và if-converted. (Bản dịch sơ bộ phục vụ học tập — chờ hiệu đính.)

### हिन्दी (प्रारंभिक अनुवाद, समीक्षा लंबित)

भागीदारी प्रतिभूतियाँ सामान्य स्टॉक के साथ आय साझा करती हैं, इसलिए आय पूरी सामान्य वर्ग को नहीं दी जा सकती। ASC 260-10-45-59A से आगे, ऐसी प्रतिभूतियाँ हों तो मूल EPS द्वि-वर्ग विधि (two-class method) से निकलता है: आय भागीदारी अधिकारों के अनुसार बाँटी जाती है, अवितरित आय भी तय आधार पर साझा होती है, और हर वर्ग को अपनी प्रति-शेयर राशि मिलती है।

ASC 718 के अनुसार, अनर्जित (unvested) शेयर-आधारित पुरस्कार जिसके पास लाभांश के अजब्तीय (nonforfeitable) अधिकार हों, वह भागीदारी प्रतिभूति है: वह अर्जन से पहले लाभांश लेता है और कभी अर्जित न हो तब भी उसे रखता है, इसलिए द्वि-वर्ग विधि से उसे आय बाँटनी होगी। जब्त किए जा सकने वाले अधिकारों वाला पुरस्कार भागीदारी प्रतिभूति नहीं है। तनुकृत EPS के लिए द्वि-वर्ग, ट्रेज़री स्टॉक और if-converted परिणामों में से अधिक तनुकारी परिणाम प्रस्तुत करें। (अध्ययन हेतु प्रारंभिक अनुवाद — समीक्षा लंबित है।)

---

## 六、呈报要求与 IAS 33 对照

### 中文

算对还要列对。公开公司在损益表表内同时呈报基本和稀释每股收益，两者并列。范围不止净利润：持续经营收益和净利润都要分别给出每股金额；有终止经营的，其每股金额单独呈报，可在表内、也可在附注，关键是不能和持续经营的数字糊成一团。附注还要交代分子分母的调节，以及当期没计入但未来可能稀释的证券。

国际对照只记大方向。IAS 33 与 ASC 260 大体趋同：都有基本和稀释两套口径，英文用语统一叫 diluted EPS，库藏股法与反稀释的大思路基本一致，框架不用重搭。差异在个别证券的处理、参与证券与两类法的具体安排、以及某些呈报位置的要求上，不完全相同。跨境报表要回到各自原文逐项核对，不能把一边的结论搬到另一边。备考记住趋同是主线、差异是个别点即可。

### English

A public company presents basic and diluted EPS together on the face of the income statement. Per-share amounts are given separately for income from continuing operations and for net income. Discontinued operations get a separate per-share amount, on the face or in the notes, never blended into continuing operations. The notes reconcile the numerators and denominators and disclose securities excluded this period that could dilute later.

IAS 33 and ASC 260 are broadly converged: both use basic and diluted measures, the term is diluted EPS under both, and treasury stock logic and the antidilution idea are substantially alike. Differences lie in certain individual securities, participating-security arrangements, and some presentation placement rules. Cross-border work must return to each standard's own text. (Study translation draft — pending review.)

### Español (译稿)

Una entidad pública presenta el EPS básico y el diluido juntos en el cuerpo del estado de resultados. Se dan importes por acción por separado para el resultado de operaciones continuadas y para el ingreso neto. Las operaciones discontinuadas reciben un importe por acción separado, en el cuerpo o en las notas, sin mezclarlo con operaciones continuadas. Las notas concilian numeradores y denominadores y revelan los valores excluidos en este periodo que podrían diluir más adelante.

La IAS 33 y la ASC 260 están en gran medida convergidas: ambas usan medidas básica y diluida, el término es diluted EPS en las dos, y la lógica de tesorería y la idea de antidilución son parecidas. Las diferencias están en ciertos valores individuales, los arreglos de valores participativos y algunos requisitos de ubicación en la presentación. El trabajo transfronterizo debe volver al texto propio de cada norma. (Borrador de traducción para estudio — pendiente de revisión.)

### 한국어 (초역·교정 대기)

계산만큼 표시도 중요합니다. 공개기업은 손익계산서 본문에 기본 EPS와 희석 EPS를 함께 표시합니다. 주당 금액은 순이익만이 아니라 계속영업이익과 순이익 각각에 대해 따로 표시합니다. 중단영업이 있으면 그 주당 금액도 본문에 두든 주석에 두든 계속영업과 섞지 말고 별도로 표시합니다. 주석에서는 분자와 분모의 조정 내역과, 당기에는 제외됐지만 장래에 희석할 수 있는 증권도 공시합니다.

국제적으로 IAS 33과 ASC 260은 대체로 수렴합니다. 둘 다 기본과 희석 측정치를 쓰고, 용어는 양쪽 모두 diluted EPS이며, 자기주식법의 논리와 반희석 개념도 실질적으로 비슷해 틀은 그대로 이어집니다. 차이는 큰 방향만 적자면 개별 증권의 처리, 참가증권과 이분법의 구체적 정법, 일부 표시 위치 요구에 있습니다. 국경을 넘는 보고에서는 한쪽 결론을 옮기지 말고 각 기준 원문으로 돌아가 확인하십시오. 시험에서는 수렴이 본선이라는 정도면 충분합니다. (학습용 초역 — 교정 대기 중입니다.)

### Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

Công ty đại chúng trình bày EPS cơ bản và EPS pha loãng cùng nhau trên mặt báo cáo kết quả kinh doanh. Số tiền trên mỗi cổ phiếu được trình bày riêng cho thu nhập từ hoạt động liên tục và cho lợi nhuận ròng. Hoạt động đã ngừng nhận một con số riêng, trên mặt báo cáo hoặc trong thuyết minh, không trộn lẫn với hoạt động liên tục. Thuyết minh đối chiếu tử số và mẫu số, đồng thời công bố các chứng khoán bị loại kỳ này nhưng có thể pha loãng về sau.

IAS 33 và ASC 260 về cơ bản hội tụ: cả hai đều dùng thước đo cơ bản và pha loãng, thuật ngữ đều là diluted EPS, logic cổ phiếu quỹ và ý tưởng chống pha loãng cũng về cơ bản giống nhau. Chênh lệch nằm ở một số chứng khoán riêng lẻ, sắp xếp cho chứng khoán tham gia và một số yêu cầu về vị trí trình bày. Công việc xuyên biên giới phải quay về văn bản riêng của từng chuẩn mực. (Bản dịch sơ bộ phục vụ học tập — chờ hiệu đính.)

### हिन्दी (प्रारंभिक अनुवाद, समीक्षा लंबित)

सार्वजनिक कंपनी आय विवरण के मुख्य भाग में मूल EPS और तनुकृत EPS दोनों साथ-साथ प्रस्तुत करती है। प्रति-शेयर राशियाँ सतत परिचालनों से आय और शुद्ध आय के लिए अलग-अलग दी जाती हैं। बंद किए गए परिचालन हों तो उनकी प्रति-शेयर राशि भी अलग प्रस्तुत होती है, मुख्य भाग में या नोटों में, सतत परिचालन में मिलाए बिना। नोट अंश और हर का मिलान देते हैं और उन प्रतिभूतियों का खुलासा करते हैं जो इस अवधि में बाहर रहीं पर बाद में तनुकृत कर सकती हैं।

IAS 33 और ASC 260 मोटे तौर पर अभिसरित हैं: दोनों में मूल और तनुकृत माप हैं, शब्द दोनों में diluted EPS ही है, और ट्रेज़री स्टॉक तर्क तथा प्रतितनुकरण का विचार काफी हद तक समान है। अंतर कुछ व्यक्तिगत प्रतिभूतियों के व्यवहार, भागीदारी प्रतिभूतियों की व्यवस्थाओं और कुछ प्रस्तुति-स्थान आवश्यकताओं में हैं। सीमा-पार कार्य में प्रत्येक मानक के अपने पाठ पर लौटें। (अध्ययन हेतु प्रारंभिक अनुवाद — समीक्षा लंबित है।)

---

> 免责声明：本文为个人学习笔记，不构成税务、会计或投资建议；具体处理以现行准则原文与专业意见为准。
