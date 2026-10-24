# 资本利得与合格股息怎么计税：持有期、三档税率与 NIIT

这篇在税法图谱里的位置：上一篇拆了个人所得税的计算结构，这一篇只钻投资所得这一块——卖股票、基金、加密资产和房产赚的钱，联邦怎么征税。核心规则集中在《国内税收法典》（Internal Revenue Code, IRC）第 1(h) 条、第 1221/1222 条和第 1411 条，税率门槛每年由 IRS 按通胀调整，文中数字以 2026 税年（Rev. Proc. 2025-32）为主、2025 税年（Rev. Proc. 2024-40）作对照。


### 한국어 (초역, 원어민 감수 대기)

이 글이 세법 지도에서 차지하는 위치: 앞 글에서는 개인소득세의 계산 구조를 분해했고, 이 글은 투자소득이라는 한 부분만 파고든다 — 주식, 펀드, 암호자산, 부동산을 팔아 번 돈에 연방이 어떻게 과세하는지. 핵심 규칙은 《국내세입법전》(Internal Revenue Code, IRC) 제1(h)조, 제1221/1222조, 제1411조에 집중되어 있고, 세율 문턱은 IRS가 매년 물가 조정하며, 본문의 숫자는 2026년 과세연도(Rev. Proc. 2025-32)를 중심으로 하고 2025년 과세연도(Rev. Proc. 2024-40)를 대조로 삼는다.

### Tiếng Việt (bản dịch sơ bộ, chờ người bản ngữ hiệu đính)

Vị trí của bài này trong bản đồ luật thuế: bài trước đã mổ xẻ cấu trúc tính thuế thu nhập cá nhân, bài này chỉ khoan vào một mảng thu nhập đầu tư — tiền kiếm được từ bán cổ phiếu, quỹ, tài sản tiền mã hóa và bất động sản, liên bang đánh thuế thế nào. Quy tắc cốt lõi tập trung ở điều 1(h), điều 1221/1222 và điều 1411 của 《Bộ luật Thuế vụ》(Internal Revenue Code, IRC), ngưỡng thuế suất mỗi năm do IRS điều chỉnh theo lạm phát, số liệu trong bài lấy năm thuế 2026 (Rev. Proc. 2025-32) làm chính, năm thuế 2025 (Rev. Proc. 2024-40) làm đối chiếu.

### हिन्दी (अनुवाद, मूल-भाषी समीक्षा लंबित)

कर कानून के मानचित्र में इस लेख का स्थान: पिछले लेख में व्यक्तिगत आयकर की गणना संरचना को खोला गया था, यह लेख केवल निवेश आय के एक भाग में ही गहराता है — शेयर, फंड, क्रिप्टो संपत्ति और अचल संपत्ति बेचकर कमाया धन, संघीय स्तर पर कैसे कर लगता है। मूल नियम 《Internal Revenue Code》(IRC) की धारा 1(h), धारा 1221/1222 और धारा 1411 में केंद्रित हैं, कर सीमा हर वर्ष IRS द्वारा मुद्रास्फीति के अनुसार समायोजित होती है, लेख की संख्याएँ मुख्यतः कर वर्ष 2026 (Rev. Proc. 2025-32) पर हैं और कर वर्ष 2025 (Rev. Proc. 2024-40) तुलना के लिए है।
---

## 一、先分短期与长期：一年零一天是分水岭

### 中文
资本利得先按持有期分家，这一步决定后面用哪套税率。依据 IRC 第 1222 条：出售时持有资本资产（capital asset，第 1221 条定义，库存、自用创作物等被排除）恰好一年或不足一年的，利得是短期资本利得（short-term），和工资一样并入普通所得按累进税率征税；持有超过一年的，是长期资本利得（long-term），才有资格用 0%、15%、20% 的优惠税率。注意用词是超过一年：满一年当天卖掉仍是短期，要等到一年零一天。

金额本身的算法不复杂：利得等于售价减去调整后计税基础（basis，第 1011、1012 条，一般就是买入成本加上佣金等调整）。同一税年内先把短期与短期轧差、长期与长期轧差，再把两边结果按第 1222 条的规则合并，最后进 Schedule D 和 Qualified Dividends and Capital Gain Tax Worksheet 算税。合格股息（qualified dividends，第 1(h)(11) 条）不是利得，但立法把它的税率直接挂到同一套 0/15/20 档上，前提包括持股期要求：一般要在股息除息日前后 121 天窗口内持有普通股超过 60 天。

### English
Capital gains are sorted first by holding period, and that sorting decides which rate schedule applies. Under IRC section 1222, a gain on a capital asset (defined in section 1221, which excludes inventory and certain self-created works) held for one year or less is a short-term capital gain, taxed with wages at ordinary graduated rates. A gain on an asset held for more than one year is long-term and qualifies for the preferential 0%, 15%, and 20% rates. The wording matters: selling on the one-year anniversary is still short-term; the line is crossed only after more than one year.

The amount itself is simple arithmetic: gain equals the amount realized minus adjusted basis (sections 1011 and 1012 — generally purchase cost plus adjustments such as commissions). Within the tax year, short-term items are netted against short-term items and long-term against long-term, then the two results are combined under the section 1222 mechanics and carried to Schedule D and the Qualified Dividends and Capital Gain Tax Worksheet. Qualified dividends (section 1(h)(11)) are not gains at all, but Congress taxes them on the same 0/15/20 schedule, subject to holding-period rules — for common stock, generally more than 60 days within the 121-day window around the ex-dividend date.

### Español (译稿)
Las ganancias de capital se clasifican primero por el período de tenencia, y esa clasificación decide qué escala de tasas se aplica. Según la sección 1222 del IRC, la ganancia por un activo de capital (definido en la sección 1221, que excluye inventarios y ciertas obras de creación propia) tenido un año o menos es ganancia de corto plazo (short-term) y tributa como el salario, a las tasas ordinarias progresivas. Si el activo se tuvo más de un año, la ganancia es de largo plazo (long-term) y accede a las tasas preferentes del 0%, 15% y 20%. La redacción importa: vender el mismo día del año cumplido sigue siendo corto plazo; el umbral se cruza solo tras más de un año.

El monto es aritmética sencilla: ganancia igual a precio de venta menos la base fiscal ajustada (secciones 1011 y 1012, por lo general el coste de compra más ajustes como comisiones). Dentro del año fiscal se compensan partidas de corto plazo entre sí y de largo plazo entre sí, luego ambos resultados se combinan según la mecánica de la sección 1222 y pasan al Anexo D (Schedule D) y a la hoja de cálculo de dividendos calificados y ganancias de capital. Los dividendos calificados (qualified dividends, sección 1(h)(11)) no son ganancias, pero el Congreso los grava con la misma escala 0/15/20, con requisitos de tenencia: para acciones ordinarias, en general más de 60 días dentro de la ventana de 121 días en torno a la fecha ex dividendo.

### 한국어 (초역, 원어민 감수 대기)

자본 이득은 먼저 보유 기간으로 나뉘며, 이 단계가 뒤에 어떤 세율표가 쓰일지를 결정한다. IRC 제1222조에 따르면: 매각 시 자본자산(capital asset, 제1221조 정의로, 재고와 자작 창작물 등은 제외됨)을 정확히 1년 또는 그 이하로 보유했으면 이득은 단기 자본 이득(short-term)이며, 임금과 마찬가지로 일반 소득에 합쳐 누진세율로 과세된다; 1년을 초과해 보유했으면 장기 자본 이득(long-term)이며, 그제야 0%, 15%, 20%의 우대세율을 쓸 자격이 생긴다. 단어에 주의하라: "1년을 초과"이다 — 정확히 1년이 되는 날 팔면 여전히 단기이며, 1년하고도 하루가 지나야 한다.

금액 자체의 계산은 복잡하지 않다: 이득은 매각가에서 조정된 과세 기준(basis, 제1011, 1012조, 일반적으로 매입 원가에 수수료 등의 조정을 더한 것)을 뺀 것과 같다. 같은 과세연도 안에서 먼저 단기와 단기를 상계하고, 장기와 장기를 상계한 뒤, 양쪽 결과를 제1222조의 규칙으로 합쳐, 마지막에 Schedule D와 Qualified Dividends and Capital Gain Tax Worksheet로 세금을 계산한다. 적격 배당(qualified dividends, 제1(h)(11)조)은 이득이 아니지만, 입법이 그 세율을 같은 0/15/20 단계에 직접 걸어 두었으며, 전제에는 보유 기간 요건이 포함된다: 일반적으로 배당락일 전후 121일 창 안에서 보통주를 60일을 초과해 보유해야 한다.

### Tiếng Việt (bản dịch sơ bộ, chờ người bản ngữ hiệu đính)

Lãi vốn trước tiên chia nhà theo thời gian nắm giữ, bước này quyết định phía sau dùng bộ thuế suất nào. Theo điều 1222 IRC: lúc bán, tài sản vốn (capital asset, định nghĩa tại điều 1221, hàng tồn kho, tác phẩm tự sáng tạo… bị loại trừ) nắm giữ đúng một năm hoặc chưa đến một năm, lãi là lãi vốn ngắn hạn (short-term), nhập vào thu nhập thông thường như lương và đánh thuế theo biểu lũy tiến; nắm giữ hơn một năm là lãi vốn dài hạn (long-term), mới đủ tư cách dùng thuế suất ưu đãi 0%, 15%, 20%. Chú ý cách dùng từ là hơn một năm: bán đúng ngày tròn một năm vẫn là ngắn hạn, phải đợi đến một năm lẻ một ngày.

Bản thân cách tính số tiền không phức tạp: lãi bằng giá bán trừ cơ sở tính thuế đã điều chỉnh (basis, điều 1011, 1012, thường là giá mua cộng các điều chỉnh như hoa hồng). Trong cùng một năm thuế, trước bù trừ ngắn hạn với ngắn hạn, dài hạn với dài hạn, rồi hợp hai kết quả theo quy tắc điều 1222, cuối cùng vào Schedule D và Qualified Dividends and Capital Gain Tax Worksheet để tính thuế. Cổ tức đủ điều kiện (qualified dividends, điều 1(h)(11)) không phải lãi, nhưng luật gắn thẳng thuế suất của nó vào cùng bộ bậc 0/15/20, tiền đề gồm yêu cầu thời gian nắm giữ: thường phải nắm giữ cổ phiếu phổ thông hơn 60 ngày trong cửa sổ 121 ngày quanh ngày chốt quyền cổ tức.

### हिन्दी (अनुवाद, मूल-भाषी समीक्षा लंबित)

पूँजी लाभ पहले धारण अवधि के अनुसार बँटता है, यही चरण तय करता है कि आगे कौन-सी कर सारणी लागू होगी। IRC धारा 1222 के अनुसार: बिक्री के समय पूँजी संपत्ति (capital asset, धारा 1221 की परिभाषा, इन्वेंटरी और स्व-निर्मित रचनाएँ आदि बाहर हैं) को ठीक एक वर्ष या उससे कम धारण किया हो तो लाभ अल्पकालिक पूँजी लाभ (short-term) है, वेतन की तरह सामान्य आय में मिलकर प्रगतिशील दरों से कर लगता है; एक वर्ष से अधिक धारण किया हो तो दीर्घकालिक पूँजी लाभ (long-term) है, तभी 0%, 15%, 20% की रियायती दरों की पात्रता मिलती है। शब्दों पर ध्यान दें, "एक वर्ष से अधिक" है: ठीक एक वर्ष पूरे होने के दिन बेचें तो भी अल्पकालिक ही रहेगा, एक वर्ष और एक दिन बीतना होगा।

राशि की गणना स्वयं जटिल नहीं है: लाभ बिक्री मूल्य से समायोजित कर आधार (basis, धारा 1011, 1012, सामान्यतः खरीद लागत और कमीशन आदि समायोजन) घटाकर बराबर होता है। एक ही कर वर्ष में पहले अल्पकालिक को अल्पकालिक से, दीर्घकालिक को दीर्घकालिक से समायोजित करें, फिर दोनों परिणाम धारा 1222 के नियमों से जोड़ें, अंत में Schedule D और Qualified Dividends and Capital Gain Tax Worksheet में कर की गणना करें। योग्य लाभांश (qualified dividends, धारा 1(h)(11)) लाभ नहीं है, लेकिन कानून उसकी दर को सीधे उसी 0/15/20 सोपान पर जोड़ता है, शर्तों में धारण अवधि की अपेक्षा शामिल है: सामान्यतः लाभांश-रहित तिथि के आसपास की 121-दिन की खिड़की में सामान्य शेयर 60 दिन से अधिक धारण करना होता है।

---

## 二、三档税率看的是应税收入，不是利得本身

### 中文
最常见的误读是把 0/15/20 当成看利得大小。实际上第 1(h) 条的门槛看的是全年应税收入（taxable income）：长期利得是叠在其他应税收入最上面的一层，落在门槛以下的部分按低档、超出的部分按高档，分段计税。门槛每年按通胀调整，依据是第 1(j)(5) 条的指数化规则和 IRS 当年的收入程序。

2026 税年门槛（Rev. Proc. 2025-32 第 4.03 节，maximum zero rate amount 与 maximum 15 percent rate amount）：

- 单身（Single）：应税收入不超过 49,450 美元的部分 0%；49,450 至 545,500 美元 15%；超过 545,500 美元 20%。
- 已婚合并申报（Married filing jointly）：98,900 美元以下 0%；98,900 至 613,700 美元 15%；超过 613,700 美元 20%。
- 户主（Head of household）：66,200 美元以下 0%；66,200 至 579,600 美元 15%；超过 579,600 美元 20%。

2025 税年作对照（Rev. Proc. 2024-40）：单身 0% 上限 48,350 美元、15% 上限 533,400 美元；合并申报 96,700 美元与 600,050 美元；户主 64,750 美元与 566,700 美元。每年门槛小幅上移，低收入年份实现利得、多拿一段 0% 区间的规划空间就是从这里来的。

算个具体例子检验理解。单身，2026 年其他应税收入 40,000 美元，卖出持有一年以上的股票得利 20,000 美元，应税收入合计 60,000 美元。利得的 9,450 美元落在 49,450 美元门槛以内，按 0%；剩下 10,550 美元按 15%，税款 1,582.50 美元。如果同一笔利得在持有满一年之前卖出，20,000 美元全部按普通税率走，税负明显更高——这就是持有期规则的实际分量。

### English
The most common misreading treats the 0/15/20 rates as if they turned on the size of the gain. In fact, the section 1(h) thresholds are measured against total taxable income. The long-term gain sits as the top layer on top of other taxable income: the slice falling below a threshold takes the lower rate and the slice above takes the higher rate, in a stacking calculation. The thresholds are inflation-indexed each year under section 1(j)(5) and published in the IRS annual revenue procedure.

For tax year 2026 (Rev. Proc. 2025-32, section 4.03 — the maximum zero rate amount and maximum 15 percent rate amount):

- Single: taxable income up to $49,450 at 0%; $49,450 to $545,500 at 15%; above $545,500 at 20%.
- Married filing jointly: up to $98,900 at 0%; $98,900 to $613,700 at 15%; above $613,700 at 20%.
- Head of household: up to $66,200 at 0%; $66,200 to $579,600 at 15%; above $579,600 at 20%.

For comparison, tax year 2025 (Rev. Proc. 2024-40) used $48,350 and $533,400 for single filers, $96,700 and $600,050 for joint filers, and $64,750 and $566,700 for heads of household. The thresholds creep up a little each year, which is exactly where the planning room comes from: realizing gains in a low-income year captures more of the 0% band.

A worked example checks the logic. Single filer, 2026, other taxable income of $40,000, plus a $20,000 long-term gain on stock held more than one year — total taxable income $60,000. Of the gain, $9,450 falls under the $49,450 threshold and is taxed at 0%; the remaining $10,550 is taxed at 15%, for a tax of $1,582.50. Sold one year or less after purchase, the same $20,000 would be taxed entirely at ordinary rates, a clearly heavier bill — that difference is the practical weight of the holding-period rule.

### Español (译稿)
El error más común es creer que las tasas 0/15/20 dependen del tamaño de la ganancia. En realidad, los umbrales de la sección 1(h) se miden sobre la renta imponible total (taxable income): la ganancia de largo plazo se coloca como la capa superior sobre los demás ingresos, la porción bajo el umbral tributa a la tasa menor y el exceso a la mayor, en un cálculo por capas. Los umbrales se ajustan cada año por inflación según la sección 1(j)(5) y se publican en el procedimiento anual del IRS.

Para el año fiscal 2026 (Rev. Proc. 2025-32, sección 4.03):

- Soltero (Single): renta imponible hasta $49.450 al 0%; de $49.450 a $545.500 al 15%; por encima de $545.500 al 20%.
- Casados con declaración conjunta: hasta $98.900 al 0%; de $98.900 a $613.700 al 15%; por encima de $613.700 al 20%.
- Cabeza de familia (Head of household): hasta $66.200 al 0%; de $66.200 a $579.600 al 15%; por encima de $579.600 al 20%.

A modo de comparación, el año fiscal 2025 (Rev. Proc. 2024-40) usó $48.350 y $533.400 para solteros, $96.700 y $600.050 para declaración conjunta, y $64.750 y $566.700 para cabeza de familia. Los umbrales suben un poco cada año, y de ahí sale el margen de planificación: realizar ganancias en un año de ingresos bajos aprovecha más tramo al 0%.

Un ejemplo con números lo deja claro. Soltero, 2026, otros ingresos imponibles de $40.000 y una ganancia de largo plazo de $20.000 por acciones tenidas más de un año: renta imponible total $60.000. De la ganancia, $9.450 quedan bajo el umbral de $49.450 y tributan al 0%; los $10.550 restantes tributan al 15%, es decir, un impuesto de $1.582,50. Si esa misma ganancia se realizara con un año o menos de tenencia, los $20.000 tributarían a tasas ordinarias, con una factura claramente mayor: esa es la importancia práctica de la regla de tenencia.

### 한국어 (초역, 원어민 감수 대기)

가장 흔한 오독은 0/15/20을 이득의 크기로 보는 것이다. 실제로 제1(h)조의 문턱은 연간 과세소득(taxable income) 전체를 본다: 장기 이득은 다른 과세소득 맨 위에 얹힌 한 층으로, 문턱 아래로 떨어지는 부분은 낮은 단계로, 초과 부분은 높은 단계로 구간별 과세한다. 문턱은 매년 물가 조정되며, 근거는 제1(j)(5)조의 지수화 규칙과 IRS 당해 연도 수입 절차이다.

2026년 과세연도 문턱(Rev. Proc. 2025-32 제4.03절, maximum zero rate amount와 maximum 15 percent rate amount):

- 단독(Single): 과세소득 49,450달러 이하 부분 0%; 49,450~545,500달러 15%; 545,500달러 초과 20%.
- 부부 합산 신고(Married filing jointly): 98,900달러 이하 0%; 98,900~613,700달러 15%; 613,700달러 초과 20%.
- 가구주(Head of household): 66,200달러 이하 0%; 66,200~579,600달러 15%; 579,600달러 초과 20%.

2025년 과세연도를 대조로(Rev. Proc. 2024-40): 단독 0% 상한 48,350달러, 15% 상한 533,400달러; 합산 신고 96,700달러와 600,050달러; 가구주 64,750달러와 566,700달러. 문턱은 매년 조금씩 오르며, 소득이 낮은 해에 이득을 실현해 0% 구간을 더 많이 가져가는 계획 공간이 바로 여기서 나온다.

구체적인 예로 이해를 검증하자. 단독, 2026년 다른 과세소득 40,000달러, 1년 이상 보유한 주식을 팔아 20,000달러의 이득, 과세소득 합계 60,000달러. 이득 중 9,450달러는 49,450달러 문턱 안에 들어 0%; 남은 10,550달러는 15%로, 세금은 1,582.50달러. 같은 이득을 보유 1년이 되기 전에 팔았다면 20,000달러 전부가 일반 세율로 가서 세 부담이 눈에 띄게 더 무거워진다 — 이것이 보유 기간 규칙의 실제 무게이다.

### Tiếng Việt (bản dịch sơ bộ, chờ người bản ngữ hiệu đính)

Cách đọc sai thường gặp nhất là coi 0/15/20 như nhìn vào độ lớn của khoản lãi. Thực ra ngưỡng của điều 1(h) nhìn vào toàn bộ thu nhập chịu thuế (taxable income) của năm: lãi dài hạn là một tầng chồng lên trên cùng của các thu nhập chịu thuế khác, phần rơi dưới ngưỡng theo bậc thấp, phần vượt theo bậc cao, tính thuế theo đoạn. Ngưỡng mỗi năm điều chỉnh theo lạm phát, căn cứ là quy tắc chỉ số hóa của điều 1(j)(5) và quy trình doanh thu năm đó của IRS.

Ngưỡng năm thuế 2026 (Rev. Proc. 2025-32 mục 4.03, maximum zero rate amount và maximum 15 percent rate amount):

- Độc thân (Single): phần thu nhập chịu thuế không vượt 49.450 đô la 0%; 49.450 đến 545.500 đô la 15%; vượt 545.500 đô la 20%.
- Vợ chồng khai chung (Married filing jointly): dưới 98.900 đô la 0%; 98.900 đến 613.700 đô la 15%; vượt 613.700 đô la 20%.
- Chủ hộ (Head of household): dưới 66.200 đô la 0%; 66.200 đến 579.600 đô la 15%; vượt 579.600 đô la 20%.

Năm thuế 2025 làm đối chiếu (Rev. Proc. 2024-40): độc thân trần 0% 48.350 đô la, trần 15% 533.400 đô la; khai chung 96.700 đô la và 600.050 đô la; chủ hộ 64.750 đô la và 566.700 đô la. Ngưỡng mỗi năm nhích lên một chút, không gian hoạch định hiện thực hóa lãi vào năm thu nhập thấp để lấy thêm một đoạn khoảng 0% chính là từ đây mà ra.

Lấy một ví dụ cụ thể để kiểm chứng hiểu biết. Độc thân, năm 2026 thu nhập chịu thuế khác 40.000 đô la, bán cổ phiếu nắm giữ hơn một năm lãi 20.000 đô la, tổng thu nhập chịu thuế 60.000 đô la. Trong khoản lãi, 9.450 đô la rơi trong ngưỡng 49.450 đô la, áp 0%; 10.550 đô la còn lại áp 15%, số thuế 1.582,50 đô la. Nếu cùng khoản lãi đó bán trước khi nắm giữ đủ một năm, toàn bộ 20.000 đô la đi theo thuế suất thông thường, gánh nặng thuế rõ ràng nặng hơn — đó là sức nặng thực tế của quy tắc thời gian nắm giữ.

### हिन्दी (अनुवाद, मूल-भाषी समीक्षा लंबित)

सबसे आम भ्रांति 0/15/20 को लाभ के आकार से जोड़ना है। वास्तव में धारा 1(h) की सीमाएँ पूरे वर्ष की करयोग्य आय (taxable income) को देखती हैं: दीर्घकालिक लाभ अन्य करयोग्य आय के सबसे ऊपर रखी एक परत है, सीमा से नीचे गिरने वाला भाग निचली दर पर, अधिक भाग ऊँची दर पर, खंड अनुसार कर लगता है। सीमाएँ हर वर्ष मुद्रास्फीति समायोजित होती हैं, आधार धारा 1(j)(5) का सूचकांक नियम और IRS की उस वर्ष की आय प्रक्रिया है।

कर वर्ष 2026 की सीमाएँ (Rev. Proc. 2025-32 धारा 4.03, maximum zero rate amount और maximum 15 percent rate amount):

- एकल (Single): करयोग्य आय 49,450 डॉलर तक का भाग 0%; 49,450 से 545,500 डॉलर 15%; 545,500 डॉलर से अधिक 20%।
- विवाहित संयुक्त दाखिल (Married filing jointly): 98,900 डॉलर तक 0%; 98,900 से 613,700 डॉलर 15%; 613,700 डॉलर से अधिक 20%।
- घर का मुखिया (Head of household): 66,200 डॉलर तक 0%; 66,200 से 579,600 डॉलर 15%; 579,600 डॉलर से अधिक 20%।

तुलना के लिए कर वर्ष 2025 (Rev. Proc. 2024-40): एकल 0% सीमा 48,350 डॉलर, 15% सीमा 533,400 डॉलर; संयुक्त दाखिल 96,700 डॉलर और 600,050 डॉलर; घर का मुखिया 64,750 डॉलर और 566,700 डॉलर। सीमाएँ हर वर्ष थोड़ा-थोड़ा ऊपर खिसकती हैं, कम आय वाले वर्ष में लाभ वसूल करके 0% खंड का अधिक भाग लेने की योजना-गुंजाइश यहीं से आती है।

एक ठोस उदाहरण से समझ जाँचें। एकल, 2026 में अन्य करयोग्य आय 40,000 डॉलर, एक वर्ष से अधिक धारण किया शेयर बेचकर 20,000 डॉलर का लाभ, कुल करयोग्य आय 60,000 डॉलर। लाभ का 9,450 डॉलर 49,450 डॉलर सीमा के भीतर आता है, 0% पर; शेष 10,550 डॉलर 15% पर, कर 1,582.50 डॉलर। यदि वही लाभ धारण का एक वर्ष पूरा होने से पहले बेचा जाता, तो पूरे 20,000 डॉलर सामान्य दरों पर जाते, कर भार स्पष्ट रूप से अधिक भारी होता — यही धारण अवधि नियम का व्यावहारिक भार है।

---

## 三、0/15/20 之外还要记住的三组特殊规则

### 中文
第一组是两种更高的长期利得税率。收藏品利得（collectibles gain，金银币、艺术品、古董等，第 1(h)(5) 条与第 408(m) 条口径）最高按 28% 征税；出售营业用不动产时，与以往折旧对应的未收回第 1250 条利得（unrecaptured section 1250 gain）最高按 25% 征税。报税软件里的 28% Rate Worksheet 和 Unrecaptured Section 1250 Gain Worksheet 就是为这两类准备的。

第二组是亏损怎么消化。资本亏损先抵同年资本利得；抵完还有净亏损的，每年最多再抵 3,000 美元普通所得（合并申报口径；分开申报为 1,500 美元，第 1211(b) 条），抵不完的按第 1212(b) 条无限期结转，并保留短期、长期的原属性。配套的反避税规则是第 1091 条的清洗销售规则（wash sale rule）：卖出亏损后 30 天内（前后共 61 天窗口）买入相同或实质相同的证券，被否定（disallowed）的亏损不消失，而是加进新仓位的计税基础里。加密资产目前是否属于第 1091 条所说的 stock or securities 尚无定论，IRS 把虚拟货币定性为财产（Notice 2014-21），实务上不要默认加密亏损可以无限制即时收割。

第三组是主要居所的排除。卖自住房的利得可按第 121 条排除：单身最高 250,000 美元、合并申报最高 500,000 美元，条件是在出售前五年内拥有并实际居住满两年（ownership and use tests）。这条对湾区房价量级的交易影响很大，是卖房年份要最先核对的一条。

### English
Three sets of special rules sit beside the headline 0/15/20 schedule.

The first is two higher long-term rates. Gain on collectibles — coins, art, antiques, and the like under sections 1(h)(5) and 408(m) — is taxed at a maximum rate of 28%. Unrecaptured section 1250 gain, the portion of a gain on business real estate attributable to prior depreciation, is taxed at a maximum of 25%. The 28% Rate Worksheet and the Unrecaptured Section 1250 Gain Worksheet in the Schedule D instructions exist for exactly these two categories.

The second is how losses are absorbed. Capital losses first offset capital gains of the same year. A remaining net capital loss may offset up to $3,000 of ordinary income per year ($1,500 if married filing separately, section 1211(b)), and any excess carries forward indefinitely under section 1212(b), keeping its short-term or long-term character. The companion anti-abuse rule is the wash sale rule of section 1091: sell at a loss and buy substantially identical stock or securities within 30 days before or after (a 61-day window) and the loss is disallowed — not destroyed, but added to the basis of the replacement position. Whether digital assets count as stock or securities under section 1091 remains unsettled; the IRS treats virtual currency as property (Notice 2014-21), so do not assume crypto losses can be harvested without limit.

The third is the principal-residence exclusion. Under section 121, gain on the sale of a main home may be excluded up to $250,000 for a single filer and $500,000 for joint filers, provided the taxpayer owned and used the home for at least two of the five years before the sale. At Bay Area price levels this is frequently the first provision to check in a home-sale year.

### Español (译稿)
Junto a la escala principal 0/15/20 conviven tres grupos de reglas especiales.

El primero son dos tasas de largo plazo más altas. La ganancia por objetos de colección (collectibles gain: monedas, arte, antigüedades, según las secciones 1(h)(5) y 408(m)) tributa a una tasa máxima del 28%. La ganancia de la sección 1250 no recapturada (unrecaptured section 1250 gain), la parte de la ganancia inmobiliaria comercial atribuible a la depreciación previa, tributa a un máximo del 25%. Las hojas de cálculo de la tasa del 28% y de la ganancia 1250 no recapturada en las instrucciones del Anexo D existen para estas dos categorías.

El segundo grupo es cómo se absorben las pérdidas. Las pérdidas de capital primero compensan las ganancias del mismo año. La pérdida neta restante puede compensar hasta $3.000 anuales de ingresos ordinarios ($1.500 en declaración separada, sección 1211(b)) y el exceso se traslada indefinidamente según la sección 1212(b), conservando su carácter de corto o largo plazo. La regla antiabuso compañera es la de venta ficticia (wash sale rule) de la sección 1091: si vende con pérdida y recompra valores iguales o sustancialmente idénticos dentro de los 30 días anteriores o posteriores (ventana de 61 días), la pérdida se deniega —no desaparece, se suma a la base fiscal de la nueva posición—. Si los activos digitales cuentan como valores a efectos de la sección 1091 sigue sin estar resuelto; el IRS trata las monedas virtuales como propiedad (Notice 2014-21), así que no dé por hecho que las pérdidas en cripto pueden cosecharse sin límite.

El tercer grupo es la exclusión por vivienda principal. Según la sección 121, la ganancia por vender la vivienda habitual puede excluirse hasta $250.000 (soltero) o $500.000 (declaración conjunta), si el contribuyente fue propietario y la usó al menos dos de los cinco años previos a la venta. Con precios como los del Área de la Bahía, suele ser la primera norma a revisar el año en que se vende la casa.

### 한국어 (초역, 원어민 감수 대기)

첫 번째 그룹은 더 높은 장기 이득 세율 두 가지이다. 수집품 이득(collectibles gain, 금화·은화, 예술품, 골동품 등, 제1(h)(5)조와 제408(m)조 기준)은 최고 28%로 과세된다; 영업용 부동산을 팔 때 과거 감가상각에 대응하는 미회수 제1250조 이득(unrecaptured section 1250 gain)은 최고 25%로 과세된다. 신고 소프트웨어의 28% Rate Worksheet와 Unrecaptured Section 1250 Gain Worksheet가 바로 이 두 종류를 위해 마련된 것이다.

두 번째 그룹은 손실을 어떻게 소화하는가이다. 자본 손실은 먼저 같은 해 자본 이득을 상쇄한다; 상쇄하고도 순손실이 남으면 매년 최대 3,000달러까지 일반 소득을 더 상쇄할 수 있고(합산 신고 기준; 분리 신고는 1,500달러, 제1211(b)조), 다 쓰지 못한 부분은 제1212(b)조에 따라 무기한 이월되며 단기·장기의 원래 성격을 유지한다. 짝을 이루는 남용 방지 규칙은 제1091조의 워시 세일 규칙(wash sale rule)이다: 손실을 보고 판 뒤 30일 이내(전후 합쳐 61일 창)에 동일하거나 실질적으로 동일한 증권을 다시 사면, 부인된(disallowed) 손실은 사라지지 않고 새 포지션의 과세 기준에 더해진다. 암호자산이 현재 제1091조에서 말하는 stock or securities에 속하는지는 아직 결론이 없으며, IRS는 가상화폐를 재산으로 규정하고 있어(Notice 2014-21), 실무에서 암호 손실이 무제한으로 즉시 수확 가능하다고 기본값으로 삼지 말 것.

세 번째 그룹은 주요 주거지의 제외이다. 자가를 팔아 얻은 이득은 제121조에 따라 제외할 수 있다: 단독 최대 250,000달러, 합산 신고 최대 500,000달러, 조건은 매각 전 5년 안에 2년 이상 소유하고 실제 거주한 것이다(ownership and use tests). 이 조항은 베이 에어리어 집값 수준의 거래에 영향이 매우 커서, 집을 파는 해에 가장 먼저 확인해야 할 조항이다.

### Tiếng Việt (bản dịch sơ bộ, chờ người bản ngữ hiệu đính)

Nhóm thứ nhất là hai mức thuế suất lãi dài hạn cao hơn. Lãi đồ sưu tầm (collectibles gain, tiền xu vàng bạc, tác phẩm nghệ thuật, đồ cổ…, theo chuẩn điều 1(h)(5) và điều 408(m)) đánh thuế tối đa 28%; khi bán bất động sản dùng cho kinh doanh, phần lãi điều 1250 chưa thu hồi (unrecaptured section 1250 gain) tương ứng với khấu hao trước đây đánh thuế tối đa 25%. 28% Rate Worksheet và Unrecaptured Section 1250 Gain Worksheet trong phần mềm khai thuế chính là chuẩn bị cho hai loại này.

Nhóm thứ hai là lỗ được tiêu hóa thế nào. Lỗ vốn trước bù lãi vốn cùng năm; bù xong còn lỗ ròng thì mỗi năm được bù thêm tối đa 3.000 đô la thu nhập thông thường (chuẩn khai chung; khai riêng là 1.500 đô la, điều 1211(b)), phần không dùng hết theo điều 1212(b) chuyển tiếp vô thời hạn, và giữ nguyên tính chất ngắn hạn, dài hạn ban đầu. Quy tắc chống lạm dụng đi kèm là quy tắc bán rửa (wash sale rule) của điều 1091: bán lỗ xong trong vòng 30 ngày (cửa sổ tổng cộng 61 ngày trước sau) mua lại chứng khoán giống hệt hoặc về cơ bản giống hệt, khoản lỗ bị bác bỏ (disallowed) không biến mất mà cộng vào cơ sở tính thuế của vị thế mới. Tài sản tiền mã hóa hiện có thuộc stock or securities mà điều 1091 nói tới hay không vẫn chưa có kết luận, IRS định tính tiền ảo là tài sản (Notice 2014-21), trong thực hành đừng mặc định lỗ tiền mã hóa có thể thu hoạch ngay không giới hạn.

Nhóm thứ ba là loại trừ nhà ở chính. Lãi bán nhà tự ở có thể loại trừ theo điều 121: độc thân tối đa 250.000 đô la, khai chung tối đa 500.000 đô la, điều kiện là trong năm năm trước khi bán đã sở hữu và thực tế cư trú đủ hai năm (ownership and use tests). Điều này ảnh hưởng rất lớn đến các giao dịch ở tầm giá nhà khu vực Vịnh, là điều phải kiểm tra đầu tiên trong năm bán nhà.

### हिन्दी (अनुवाद, मूल-भाषी समीक्षा लंबित)

पहला समूह दो ऊँची दीर्घकालिक लाभ दरों का है। संग्रहणीय वस्तुओं का लाभ (collectibles gain, सोने-चाँदी के सिक्के, कलाकृतियाँ, प्राचीन वस्तुएँ आदि, धारा 1(h)(5) और धारा 408(m) के मानक पर) अधिकतम 28% पर कर लगता है; व्यावसायिक अचल संपत्ति बेचते समय पिछले मूल्यह्रास के अनुरूप अवसूल धारा 1250 लाभ (unrecaptured section 1250 gain) पर अधिकतम 25% कर लगता है। दाखिल सॉफ़्टवेयर की 28% Rate Worksheet और Unrecaptured Section 1250 Gain Worksheet इन्हीं दो प्रकारों के लिए बनाई गई हैं।

दूसरा समूह है घाटा कैसे पचाया जाता है। पूँजी घाटा पहले उसी वर्ष के पूँजी लाभ को समायोजित करता है; समायोजन के बाद भी शुद्ध घाटा बचे तो हर वर्ष अधिकतम 3,000 डॉलर तक सामान्य आय और समायोजित की जा सकती है (संयुक्त दाखिल मानक; अलग दाखिल में 1,500 डॉलर, धारा 1211(b)), और जो भाग न उपयोग हो वह धारा 1212(b) के अनुसार अनिश्चित काल तक अग्रेषित होता है और अल्पकालिक, दीर्घकालिक अपना मूल स्वरूप बनाए रखता है। साथ की दुरुपयोग-रोधी नियम धारा 1091 का वॉश सेल नियम (wash sale rule) है: घाटे पर बेचने के 30 दिनों के भीतर (आगे-पीछे कुल 61 दिन की खिड़की) समान या मूलतः समान प्रतिभूति फिर खरीद लें, तो अस्वीकृत (disallowed) घाटा गायब नहीं होता, नई स्थिति के कर आधार में जुड़ जाता है। क्रिप्टो संपत्ति वर्तमान में धारा 1091 के stock or securities में आती है या नहीं, इसका निष्कर्ष अभी नहीं है, IRS आभासी मुद्रा को संपत्ति मानता है (Notice 2014-21), व्यवहार में यह न मानें कि क्रिप्टो घाटा असीमित रूप से तुरंत वसूला जा सकता है।

तीसरा समूह मुख्य आवास का बहिष्करण है। स्वयं के घर की बिक्री का लाभ धारा 121 के अनुसार बाहर किया जा सकता है: एकल अधिकतम 250,000 डॉलर, संयुक्त दाखिल अधिकतम 500,000 डॉलर, शर्त यह कि बिक्री से पहले के पाँच वर्षों में दो वर्ष स्वामित्व रहा हो और वास्तव में निवास किया हो (ownership and use tests)। यह प्रावधान खाड़ी क्षेत्र के घर मूल्यों के स्तर के सौदों पर बहुत प्रभाव डालता है, घर बेचने वाले वर्ष में सबसे पहले जाँचने वाला प्रावधान यही है।

---

## 四、再叠一层：3.8% 的 NIIT 与加州的不跟随

### 中文
高收入者还要看净投资所得税（Net Investment Income Tax, NIIT），IRC 第 1411 条，税率 3.8%。触发线看调整后总收入（MAGI）：单身超过 200,000 美元、合并申报超过 250,000 美元、分开申报超过 125,000 美元，超出部分的净投资收入（利息、股息、资本利得、租金、被动经营所得等）按 3.8% 征收；应纳税额取两者的较小值——超额 MAGI 与净投资收入比大小取小。这几个门槛是 2013 年立法时写死的数字，法条没有通胀调整条款，所以十多年没动过，每年圈进来的人只增不减。叠满的状态是：20% 的长期利得税率加 3.8% 的 NIIT，联邦合计 23.8%。NIIT 用 Form 8960 申报，备考时注意它不属于第 1 章的普通所得税，而是第 2A 章的独立税种。

到了加州这一层，规则简单粗暴：加州没有长期资本利得优惠税率。《加州收入与税法典》下，资本利得全部并入普通所得，按加州 1% 至 12.3% 的累进税率征税（高收入另有 1% 的心理健康服务税，合计边际最高 13.3%），申报上用 Schedule CA 做联邦与州的差异调整。用联邦的 0% 思路去估加州税负，是新手最常见的错位。CPA 考试（REG）与实务口径一致：联邦先分短期长期、再叠 NIIT，州税单独按本州规则另算，两套系统不要混表。

### English
Higher-income taxpayers face one more layer: the Net Investment Income Tax (NIIT) of IRC section 1411, at 3.8%. It is triggered by modified adjusted gross income (MAGI) above $200,000 for single filers, $250,000 for joint filers, and $125,000 for married filing separately, and it applies to the lesser of the MAGI excess or the taxpayer's net investment income — interest, dividends, capital gains, rents, and passive business income. Those thresholds were fixed by statute in 2013 with no inflation adjustment, so they have not moved in over a decade and capture more taxpayers every year. Fully stacked, a top-bracket long-term gain pays 20% plus 3.8%, a combined 23.8% federal rate. The NIIT is reported on Form 8960 — and note for exam purposes that it sits in Chapter 2A of the Code, a separate tax from the Chapter 1 income tax.

California then runs its own, simpler rule: there is no preferential capital gains rate. Under California law, capital gains are ordinary income, taxed at the state's graduated 1% to 12.3% rates (with the additional 1% mental health services tax at the top, for a top marginal rate of 13.3%), with federal-to-state differences adjusted on Schedule CA. Estimating a California tax bill with the federal 0% bracket in mind is the most common beginner's mismatch. For CPA REG purposes and in practice alike: compute the federal side first — short versus long-term, then the NIIT layer — and compute California separately under its own rules.

### Español (译稿)
Los contribuyentes de ingresos altos tienen una capa más: el impuesto sobre la renta neta de inversión (Net Investment Income Tax, NIIT), sección 1411 del IRC, con una tasa del 3,8%. Se activa cuando el ingreso bruto ajustado modificado (MAGI) supera $200.000 (soltero), $250.000 (declaración conjunta) o $125.000 (declaración separada), y se aplica sobre lo menor entre el exceso de MAGI y la renta neta de inversión del contribuyente: intereses, dividendos, ganancias de capital, rentas y rentas pasivas de negocios. Esos umbrales quedaron fijos en la ley de 2013, sin ajuste por inflación, así que llevan más de una década sin moverse y cada año abarcan a más personas. En el extremo superior, una ganancia de largo plazo paga 20% más 3,8%: un 23,8% federal combinado. El NIIT se declara en el Formulario 8960 y, a efectos de examen, tenga en cuenta que está en el Capítulo 2A del Código, un impuesto distinto del impuesto sobre la renta del Capítulo 1.

California aplica su propia regla, más simple y menos amable: no existe una tasa preferente para las ganancias de capital. Conforme al derecho californiano, las ganancias de capital son ingreso ordinario y tributan en la escala progresiva estatal del 1% al 12,3% (con el 1% adicional del impuesto de servicios de salud mental en el tramo alto, para un tipo marginal máximo del 13,3%), con las diferencias frente a lo federal ajustadas en el Schedule CA. Estimar el impuesto de California con la lógica del tramo federal al 0% es el desajuste más común en quien empieza. Tanto para el examen CPA (REG) como en la práctica: primero se calcula la parte federal —corto frente a largo plazo, luego la capa del NIIT— y California se calcula por separado con sus propias reglas.

### 한국어 (초역, 원어민 감수 대기)

고소득자는 순투자소득세(Net Investment Income Tax, NIIT), IRC 제1411조, 세율 3.8%도 봐야 한다. 발동선은 조정총소득(MAGI)을 본다: 단독 200,000달러 초과, 합산 신고 250,000달러 초과, 분리 신고 125,000달러 초과이면, MAGI 초과액과 순투자소득(이자, 배당, 자본 이득, 임대료, 수동적 사업소득 등)을 비교해 더 작은 쪽에 3.8%가 부과된다. 이 문턱들은 2013년 입법 때 고정된 숫자로, 법문에 물가 조정 조항이 없어서 십수 년 동안 움직이지 않았고, 매년 들어오는 사람만 늘어난다. 최대 상태는: 장기 이득 세율 20%에 NIIT 3.8%를 더해 연방 합계 23.8%. NIIT는 Form 8960으로 신고하며, 시험 대비로 주의할 점은 그것이 제1장의 일반 소득세가 아니라 제2A장의 독립된 세목이라는 것이다.

캘리포니아 층에 오면 규칙은 단순하고 거칠다: 캘리포니아에는 장기 자본 이득 우대세율이 없다. 《캘리포니아 수입 및 세금법전》에 따르면 자본 이득은 전액 일반 소득에 합쳐 캘리포니아의 1%~12.3% 누진세율로 과세되고(고소득자에게는 1%의 정신 건강 서비스세가 또 있어, 합쳐서 한계 최고 13.3%), 신고에서는 Schedule CA로 연방과 주의 차이를 조정한다. 연방의 0% 발상으로 캘리포니아 세 부담을 추정하는 것이 초보자의 가장 흔한 어긋남이다. CPA 시험(REG)과 실무의 기준은 일치한다: 연방은 먼저 단기·장기를 나누고 그다음 NIIT를 얹으며, 주세는 본주의 규칙으로 따로 계산한다. 두 시스템은 표를 섞어 쓰지 말 것.

### Tiếng Việt (bản dịch sơ bộ, chờ người bản ngữ hiệu đính)

Người thu nhập cao còn phải xem thuế thu nhập đầu tư ròng (Net Investment Income Tax, NIIT), điều 1411 IRC, thuế suất 3,8%. Vạch kích hoạt nhìn vào thu nhập gộp đã điều chỉnh (MAGI): độc thân vượt 200.000 đô la, khai chung vượt 250.000 đô la, khai riêng vượt 125.000 đô la thì so sánh phần vượt MAGI và thu nhập đầu tư ròng (lãi, cổ tức, lãi vốn, tiền thuê, thu nhập kinh doanh thụ động…) lấy bên nhỏ hơn để đánh 3,8%. Các ngưỡng này là con số viết chết khi lập pháp năm 2013, luật không có điều khoản điều chỉnh lạm phát, nên hơn mười năm không hề nhúc nhích, mỗi năm số người bị cuốn vào chỉ tăng không giảm. Trạng thái chồng đầy đủ là: thuế suất lãi dài hạn 20% cộng NIIT 3,8%, liên bang tổng cộng 23,8%. NIIT khai bằng Form 8960, khi ôn thi chú ý nó không thuộc thuế thu nhập thông thường của Chương 1, mà là sắc thuế độc lập của Chương 2A.

Đến tầng California, quy tắc đơn giản thô bạo: California không có thuế suất ưu đãi lãi vốn dài hạn. Theo 《Bộ luật Doanh thu và Thuế California》, lãi vốn toàn bộ nhập vào thu nhập thông thường, đánh theo biểu lũy tiến 1% đến 12,3% của California (thu nhập cao còn 1% thuế dịch vụ sức khỏe tâm thần, gộp lại biên cao nhất 13,3%), khai thuế dùng Schedule CA điều chỉnh chênh lệch liên bang và bang. Dùng lối nghĩ 0% của liên bang để ước gánh nặng thuế California là lệch lạc thường gặp nhất của người mới. Chuẩn của kỳ thi CPA (REG) và thực hành nhất trí: liên bang trước chia ngắn hạn dài hạn, rồi chồng NIIT; thuế bang tính riêng theo quy tắc của bang đó, hai hệ thống đừng trộn bảng.

### हिन्दी (अनुवाद, मूल-भाषी समीक्षा लंबित)

उच्च आय वालों को शुद्ध निवेश आय कर (Net Investment Income Tax, NIIT), IRC धारा 1411, दर 3.8% भी देखना होता है। ट्रिगर रेखा संशोधित समायोजित कुल आय (MAGI) को देखती है: एकल 200,000 डॉलर से अधिक, संयुक्त दाखिल 250,000 डॉलर से अधिक, अलग दाखिल 125,000 डॉलर से अधिक होने पर MAGI की अधिकता और शुद्ध निवेश आय (ब्याज, लाभांश, पूँजी लाभ, किराया, निष्क्रिय व्यवसाय आय आदि) की तुलना करके छोटी ओर पर 3.8% लगाया जाता है। ये सीमाएँ 2013 के कानून में ठहरी हुई संख्याएँ हैं, कानून में मुद्रास्फीति समायोजन का प्रावधान नहीं है, इसलिए दस से अधिक वर्षों से हिली नहीं हैं, हर वर्ष इसमें आने वाले लोग केवल बढ़ते हैं। पूरी तरह चढ़ी हुई स्थिति है: दीर्घकालिक लाभ दर 20% और NIIT 3.8% मिलाकर संघीय कुल 23.8%। NIIT Form 8960 से दाखिल होता है, परीक्षा की दृष्टि से ध्यान दें कि यह अध्याय 1 के सामान्य आयकर का नहीं, अध्याय 2A का स्वतंत्र कर है।

कैलिफ़ोर्निया स्तर पर नियम सरल और कठोर है: कैलिफ़ोर्निया में दीर्घकालिक पूँजी लाभ की रियायती दर नहीं है। 《कैलिफ़ोर्निया राजस्व और कर संहिता》 के अनुसार पूँजी लाभ पूरी तरह सामान्य आय में मिलता है, कैलिफ़ोर्निया की 1% से 12.3% प्रगतिशील दरों से कर लगता है (उच्च आय पर 1% मानसिक स्वास्थ्य सेवा कर और, मिलाकर सीमांत अधिकतम 13.3%), दाखिल में Schedule CA से संघीय और राज्य अंतर समायोजित होता है। संघीय 0% सोच से कैलिफ़ोर्निया कर भार का अनुमान लगाना शुरुआती लोगों की सबसे आम गड़बड़ी है। CPA परीक्षा (REG) और व्यवहार का मानक एक है: संघीय में पहले अल्पकालिक-दीर्घकालिक बाँटें, फिर NIIT की परत चढ़ाएँ, राज्य कर उस राज्य के नियमों से अलग गिनें, दोनों प्रणालियों की सारणियाँ न मिलाएँ।

---

## 参考依据

- IRC section 1(h)（长期资本利得最高税率与合格股息）、section 1(h)(11)（合格股息）、section 1(j)(5)（门槛指数化）、sections 1011/1012（计税基础）、section 1091（清洗销售）、section 121（主要居所排除 250,000/500,000 美元）、section 1211(b)（资本亏损每年 3,000/1,500 美元限额）、section 1212(b)（亏损结转）、sections 1221/1222（资本资产与持有期）、section 1411（NIIT 3.8% 与 200,000/250,000/125,000 美元门槛）
- Rev. Proc. 2025-32, section 4.03（2026 税年 0% 与 15% 门槛：单身 49,450/545,500、合并申报 98,900/613,700、户主 66,200/579,600 美元）；Rev. Proc. 2024-40（2025 税年：单身 48,350/533,400、合并申报 96,700/600,050、户主 64,750/566,700 美元）
- IRS Topic No. 409（Capital Gains and Losses）；IRS Notice 2014-21（虚拟货币财产定性）；Form 8960 与 Schedule D 说明书（含 28% 与第 1250 条工作表）
- California Revenue and Taxation Code：加州无资本利得优惠税率，利得按普通所得 1% 至 12.3% 累进税率（另加高收入者 1% 心理健康服务税）征税；FTB Schedule CA 调整说明

## 免责声明

本篇为个人学习笔记，不构成税务建议。税率门槛逐年调整，具体申报请查当年 IRS 收入程序与表格说明书，或咨询持牌 CPA。

*This article is a personal study note, not tax advice. / Este artículo es una nota de estudio personal, no constituye asesoría fiscal. El texto en español es una traducción de estudio, pendiente de revisión por un hablante nativo.*

*이 글은 개인 학습 노트이며 세무 조언이 아닙니다. 세율 문턱은 매년 조정되므로, 구체적인 신고는 당해 연도 IRS 수입 절차와 양식 설명을 확인하거나 면허 CPA에게 상담하십시오.*

*Bài này là ghi chú học tập cá nhân, không phải tư vấn thuế. Ngưỡng thuế suất điều chỉnh từng năm, khai thuế cụ thể hãy tra quy trình doanh thu và hướng dẫn biểu mẫu của IRS của năm đó, hoặc tham vấn CPA có giấy phép.*

*यह लेख एक व्यक्तिगत अध्ययन नोट है, कर सलाह नहीं। कर सीमाएँ हर वर्ष समायोजित होती हैं, विशिष्ट दाखिल के लिए उस वर्ष की IRS आय प्रक्रिया और फ़ॉर्म निर्देश देखें, या लाइसेंसधारी CPA से परामर्श करें।*
