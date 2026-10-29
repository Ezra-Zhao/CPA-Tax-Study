# 国际税务怎么管：全球征税、FEIE 与 FBAR、FATCA 申报

这篇讲什么：
- 美国对公民和税务居民按全球收入征税，人搬到国外，税表并不会自动消失。少交税的正路只有两条常被用到的：外国所得排除（FEIE）先把一部分工资从收入里拿掉，外国所得税抵免（FTC）再拿在外国已经交过的税来抵美国税，同一笔收入不能两头占。
- 报告和缴税是两件事：FBAR 报的是外国金融账户，FATCA 的 Form 8938 报的是外国金融资产。门槛一到，两套都要报，报了 FBAR 不等于报了 8938，反过来也一样。
- 外国人取得美国来源收入，规则又反过来：一般先按 30% 预扣，协定能降；加州则没有 FEIE 的对应排除，在国外挣的工资对加州居民照样算收入。

---

## 一、谁被全球征税

### 中文

先分清身份。IRC 第 61 条把总收入定义得很宽，第 1 条对公民和居民课税，合起来就是全球征税：工资、利息、股息、租金、经营收入，不管在哪个国家取得，原则上都要进美国税表。谁算税务居民，看第 7701(b) 条，一是持绿卡的合法永久居民，二是满足实质居住测试的外国人，按公式数在美停留天数。公民更直接，哪怕多年不住在美国，申报义务仍在。弃籍也不是一走了之：第 877A 条对 covered expatriate 设弃籍税，触发线包括净资产达到 2,000,000 美元，或近 5 年年均净所得税负达到门槛（2025 年为 206,000 美元），触发后全球资产按弃籍前一日视同出售计税。这里先记住一点，身份决定税基，住在哪里只影响能用哪种减免，改不了全球申报这个底盘。

### English

Identity comes first. Section 61 defines gross income broadly and § 1 taxes citizens and residents, which together produce worldwide taxation: wages, interest, dividends, rent, and business income are reportable in the United States wherever earned. Tax residency under § 7701(b) means lawful permanent residents under the green card test and foreign nationals who meet the substantial presence test, which counts days of U.S. presence under a formula. Citizens keep a filing duty even after years abroad. Leaving is not a clean exit either: § 877A imposes an exit tax on a covered expatriate, triggered by net worth of $2,000,000 or by average annual net income tax over the prior five years reaching the threshold ($206,000 for 2025); covered assets are then treated as sold on the day before expatriation. Status sets the tax base; where you live affects relief, not the worldwide filing chassis.

### Español (译稿 de estudio)

Primero, la condición fiscal. La sección 61 define ampliamente el ingreso bruto y la sección 1 grava a ciudadanos y residentes; juntas producen tributación mundial: salarios, intereses, dividendos, alquileres e ingresos empresariales se declaran en EE. UU. se obtengan donde se obtengan. La residencia fiscal de la sección 7701(b) abarca a residentes permanentes con green card y a extranjeros que superan la prueba de presencia sustancial, que cuenta días de presencia con una fórmula. El ciudadano conserva la obligación de declarar aunque viva años fuera. Salir tampoco es gratis: la sección 877A impone un impuesto de salida al expatriado cubierto, activado por un patrimonio neto de 2.000.000 de dólares o por un impuesto medio anual de los cinco años previos que alcance el umbral (206.000 dólares en 2025); los bienes se tratan como vendidos el día anterior a la expatriación.

### 한국어 (초역)

먼저 신분부터입니다. 제61조는 총소득을 넓게 정의하고 제1조는 시민과 거주자에게 과세하므로, 합치면 전 세계 소득 과세가 됩니다. 임금, 이자, 배당, 임대료, 사업소득은 어느 나라에서 벌었든 원칙적으로 미국 세금보고에 들어갑니다. 제7701(b)조의 세법상 거주자는 그린카드 테스트를 통과한 영주권자와, 체류 일수를 공식으로 세는 실질 체류 테스트를 충족한 외국인입니다. 시민은 해외에 오래 살아도 신고 의무가 남습니다. 국적 포기도 단순하지 않습니다. 제877A조의 출국세는 순자산 2,000,000달러에 이르거나 최근 5년 평균 순소득세 부담이 문턱(2025년 206,000달러)에 닿은 covered expatriate에게 적용되며, 자산은 포기 전날 판 것으로 봅니다.

### Tiếng Việt (bản dịch sơ khởi)

Trước hết là thân phận. Điều 61 định nghĩa tổng thu nhập rất rộng và Điều 1 đánh thuế công dân cùng cư dân, kết hợp lại thành đánh thuế toàn cầu: lương, lãi, cổ tức, tiền thuê và thu nhập kinh doanh phải khai tại Hoa Kỳ dù kiếm được ở đâu. Cư dân thuế theo § 7701(b) gồm thường trú nhân theo kiểm tra thẻ xanh và người nước ngoài đạt kiểm tra hiện diện thực chất, tính ngày ở Mỹ theo công thức. Công dân vẫn phải khai dù sống ở nước ngoài nhiều năm. Bỏ quốc tịch cũng không đơn giản: § 877A áp thuế xuất cảnh với covered expatriate khi tài sản ròng đạt 2.000.000 đô la hoặc thuế thu nhập ròng trung bình năm năm trước đạt ngưỡng (206.000 đô la cho năm 2025); tài sản được coi như đã bán vào ngày trước khi bỏ quốc tịch.

### हिन्दी (प्रारंभिक अनुवाद)

पहले दर्जा तय करें। धारा 61 सकल आय को व्यापक रूप से परिभाषित करती है और धारा 1 नागरिकों व निवासियों पर कर लगाती है; दोनों मिलकर विश्वव्यापी कराधान बनाते हैं — मज़दूरी, ब्याज, लाभांश, किराया और व्यवसाय आय, चाहे किसी भी देश में कमाई गई हो, अमेरिका में रिपोर्ट होती है। § 7701(b) के तहत कर निवासी वे हैं जो ग्रीन कार्ड परीक्षण से स्थायी निवासी हैं या सारभूत उपस्थिति परीक्षण, जो उपस्थिति के दिनों को सूत्र से गिनता है, पूरा करते हैं। नागरिक वर्षों विदेश रहने पर भी दाखिल करने के दायी रहते हैं। नागरिकता छोड़ना भी आसान निकास नहीं: § 877A covered expatriate पर निकास कर लगाती है, जो 2,000,000 डॉलर की निवल संपत्ति या पिछले पाँच वर्षों के औसत वार्षिक निवल आयकर के सीमा तक पहुँचने (2025 में 206,000 डॉलर) से सक्रिय होता है; संपत्तियाँ त्याग से एक दिन पहले बेची गई मानी जाती हैं।

## 二、少交美国税的两条正路：FEIE 与 FTC 怎么选

### 中文

人在国外工作，减税先看第 911 条的外国所得排除（FEIE）。2025 年排除上限是 130,000 美元，出处是 Rev. Proc. 2024-40，每年按通胀调。资格要过两道测试之一：真实居住地测试，要求在外国有真实居所且住满整个纳税年度；实际停留测试，要求在连续 12 个月里在外国实际停留满 330 天。申报用 Form 2555。注意边界：FEIE 只排除所得税层面的外国劳动所得，自雇收入仍要交自雇税，它不免 SECA 税，房租、股息这类非劳动收入也进不了排除。第二条路是外国所得税抵免（FTC），条文在第 901 条至第 909 条，用 Form 1116，把在外国依法交过的所得税拿来抵美国税，但有上限：可抵额不能超过外国来源应税收入占全球应税收入的比例乘以美国税。选法很朴素：外国税率高，FTC 往往更合算，还能保住退休账户供款等资格；外国税率低或收入主要是工资，FEIE 可能先挡掉一大块。同一笔收入只能选一条路，已经被 FEIE 排除掉的那部分，不能再拿对应的外国税去抵免。

### English

For work abroad, start with the foreign earned income exclusion (FEIE) under § 911. The cap for 2025 is $130,000 (Rev. Proc. 2024-40), indexed yearly. Qualify under one of two tests: the bona fide residence test, requiring a genuine home abroad for the full tax year, or the physical presence test, requiring 330 full days abroad in a 12-month period. File Form 2555. The boundary matters: FEIE shelters foreign earned income for income tax only. Self-employment income still bears self-employment tax — FEIE does not waive SECA tax — and rent or dividends do not qualify. The second route is the foreign tax credit (FTC) under §§ 901–909, claimed on Form 1116 for foreign income taxes legally paid, capped at the share of U.S. tax proportional to foreign-source taxable income over worldwide taxable income. Where the foreign rate is high, the FTC often wins; where it is low and income is mostly wages, FEIE may shelter more. The same dollar of income gets one route only: income excluded under FEIE cannot also generate a credit for the foreign tax on it.

### Español (译稿 de estudio)

Para trabajar fuera, mire primero la exclusión por ingresos ganados en el extranjero (FEIE) de la sección 911. El tope de 2025 es 130.000 dólares (Rev. Proc. 2024-40), ajustado cada año. Se califica con una de dos pruebas: residencia de buena fe, con hogar real en el extranjero durante todo el año fiscal, o presencia física, con 330 días completos fuera en un periodo de 12 meses. Se usa el Formulario 2555. El límite es claro: la FEIE protege solo frente al impuesto sobre la renta; el ingreso por cuenta propia sigue pagando el impuesto de autoempleo, la FEIE no exime el SECA, y alquileres o dividendos no entran. La segunda vía es el crédito por impuestos extranjeros (FTC), secciones 901 a 909, en el Formulario 1116, con tope igual a la proporción del ingreso extranjero sobre el ingreso mundial multiplicada por el impuesto de EE. UU. Con tipo extranjero alto suele convenir el FTC; con tipo bajo y salario, la FEIE. El mismo dólar no admite las dos vías.

### 한국어 (초역)

해외에서 일하면 먼저 제911조의 해외 근로소득 공제(FEIE)를 보세요. 2025년 상한은 130,000달러(Rev. Proc. 2024-40)이고 매년 물가 조정을 받습니다. 자격은 둘 중 하나입니다. 진정한 거주지 테스트는 외국에 실제 거소가 있고 과세연도 내내 거주할 것, 실제 체류 테스트는 연속 12개월 중 외국에 만 330일을 있을 것을 요구합니다. 신고는 Form 2555입니다. 경계가 중요합니다. FEIE는 소득세 차원에서만 근로소득을 빼주고, 자영업 소득에는 여전히 자영업세가 붙습니다. FEIE는 SECA 세금을 면제하지 않으며, 임대료와 배당은 대상이 아닙니다. 두 번째 길은 제901조부터 제909조까지의 외국 세액공제(FTC)로 Form 1116을 씁니다. 한도는 외국 원천 과세소득이 전 세계 과세소득에서 차지하는 비율에 미국 세금을 곱한 금액입니다. 외국 세율이 높으면 FTC가, 낮고 임금 위주면 FEIE가 유리할 때가 많습니다. 같은 소득에 두 길을 겹칠 수는 없습니다.

### Tiếng Việt (bản dịch sơ khởi)

Làm việc ở nước ngoài, trước hết xem loại trừ thu nhập kiếm được ở nước ngoài (FEIE) theo § 911. Hạn mức năm 2025 là 130.000 đô la (Rev. Proc. 2024-40), điều chỉnh hằng năm. Điều kiện qua một trong hai kiểm tra: cư trú thực sự, có nơi ở thật ở nước ngoài suốt năm thuế, hoặc hiện diện thực tế, đủ 330 ngày trọn ở nước ngoài trong 12 tháng liên tục. Khai bằng Form 2555. Ranh giới cần rõ: FEIE chỉ che thu nhập lao động nước ngoài ở tầng thuế thu nhập; thu nhập tự làm vẫn chịu thuế tự làm, FEIE không miễn thuế SECA, và tiền thuê hay cổ tức không được loại trừ. Con đường thứ hai là tín dụng thuế nước ngoài (FTC) theo §§ 901–909, khai trên Form 1116, với trần bằng tỷ lệ thu nhập chịu thuế nguồn nước ngoài trên thu nhập toàn cầu nhân với thuế Mỹ. Thuế nước ngoài cao thì FTC thường lợi hơn; thuế thấp và chủ yếu là lương thì FEIE có thể lợi hơn. Cùng một khoản thu nhập không dùng cả hai.

### हिन्दी (प्रारंभिक अनुवाद)

विदेश में काम करने पर पहले § 911 की विदेश में अर्जित आय बहिष्करण (FEIE) देखें। 2025 की सीमा 130,000 डॉलर है (Rev. Proc. 2024-40), हर वर्ष समायोजित। पात्रता दो परीक्षणों में से एक से मिलती है: bona fide residence, जिसमें पूरे कर वर्ष विदेश में वास्तविक निवास चाहिए, या physical presence, जिसमें लगातार 12 महीनों में विदेश में पूरे 330 दिन चाहिए। Form 2555 उपयोग होता है। सीमा स्पष्ट है: FEIE केवल आयकर स्तर पर विदेशी अर्जित आय को बचाती है; स्व-रोज़गार आय पर स्व-रोज़गार कर फिर भी लगता है, FEIE SECA कर माफ़ नहीं करती, और किराया या लाभांश इसमें नहीं आता। दूसरा रास्ता §§ 901–909 का विदेशी कर क्रेडिट (FTC) है, Form 1116 पर, जिसकी सीमा विदेशी स्रोत कर-योग्य आय के विश्वव्यापी आय में अनुपात को अमेरिकी कर से गुणा करके मिलती है। विदेशी दर ऊँची हो तो FTC, कम हो और आय मुख्यतः वेतन हो तो FEIE अक्सर बेहतर रहता है। एक ही आय पर दोनों लाभ नहीं मिलते।

## 三、两套报告：FBAR 与 FATCA 对照表

### 中文

这一节最容易被误会成重复申报，其实两张表管的不是一回事。

| 对照项 | FBAR | FATCA（Form 8938） |
| --- | --- | --- |
| 法律依据 | 31 U.S.C. 第 5314 条，《银行保密法》一线 | IRC 第 6038D 条，税法一线 |
| 申报表与去向 | FinCEN Form 114，交财政部 FinCEN，不随税表 | Form 8938，附在当年的所得税表后面 |
| 报什么 | 外国银行与金融账户 | 指定的外国金融资产，范围比账户更宽 |
| 门槛 | 所有外国账户合计在年内任一时点超过 10,000 美元 | 住在美国的单身申报人：年末超过 50,000 美元，或年内任一时点超过 75,000 美元；夫妻合报翻倍为 100,000 / 150,000 美元 |
| 性质与期限 | 只报告、不交税；4 月 15 日到期，自动延期到 10 月 15 日 | 随税表申报；未申报罚则起步 10,000 美元 |

门槛一到，两套都要报，互不抵替。账户里哪怕一分钱收入都没有，FBAR 该报还是报，因为它盯的是账户本身。反过来，资产达到 8938 门槛，也不能拿 FBAR 顶替。还有一类资产先只点名：PFIC，也就是被动外国投资公司，申报用 Form 8621，其超额分配有一套高税负机制，细节不在这篇展开。

### English

These two filings are often mistaken for duplicates; they are not. The FBAR rests on 31 U.S.C. § 5314 under the Bank Secrecy Act: FinCEN Form 114 goes to FinCEN, not with the tax return, and reports foreign bank and financial accounts once their aggregate value exceeds $10,000 at any point in the year. It is reporting only, no tax, due April 15 with an automatic extension to October 15. Form 8938 rests on IRC § 6038D and attaches to the income tax return; it covers specified foreign financial assets, a broader category than accounts. For a single filer living in the United States, the threshold is more than $50,000 at year-end or more than $75,000 at any point in the year; married filing jointly doubles it to $100,000 / $150,000. Failure to file Form 8938 starts with a $10,000 penalty. Meeting one duty never discharges the other. A PFIC is named only in passing: it is reported on Form 8621 and its excess distributions face a punitive regime, not detailed here.

### Español (译稿 de estudio)

Estas dos declaraciones se confunden con un duplicado y no lo son. El FBAR nace del 31 U.S.C. sección 5314: el FinCEN Form 114 va a FinCEN, no con la declaración, e informa cuentas bancarias y financieras extranjeras cuando su total supera 10.000 dólares en cualquier momento del año. Es solo informativo, sin impuesto, vence el 15 de abril con prórroga automática al 15 de octubre. El Formulario 8938 nace de la sección 6038D, se adjunta a la declaración de la renta y cubre activos financieros extranjeros especificados, una categoría más amplia que las cuentas. Para un declarante soltero que vive en EE. UU., el umbral es más de 50.000 dólares al cierre o más de 75.000 en cualquier momento; en declaración conjunta se duplica a 100.000 / 150.000. No presentar el 8938 parte de una multa de 10.000 dólares. Cumplir una obligación no sustituye la otra. El PFIC solo se menciona: se informa en el Formulario 8621 y sus distribuciones excesivas tienen un régimen gravoso.

### 한국어 (초역)

이 두 신고는 중복으로 오해받지만 다릅니다. FBAR는 31 U.S.C. 제5314조에 근거하며 FinCEN Form 114를 세금보고와 별도로 FinCEN에 냅니다. 외국 은행·금융계좌의 합계가 연중 어느 시점에든 10,000달러를 넘으면 보고 대상입니다. 세금은 없고 보고만 하며, 기한은 4월 15일, 10월 15일까지 자동 연장됩니다. Form 8938은 IRC 제6038D조에 근거해 소득세 신고서에 붙고, 계좌보다 넓은 지정 외국 금융자산을 다룹니다. 미국에 사는 단독 신고자는 연말 50,000달러 초과 또는 연중 75,000달러 초과가 문턱이고, 부부 합산 신고는 100,000 / 150,000달러로 두 배입니다. 8938을 내지 않으면 벌금은 10,000달러부터 시작합니다. 하나를 냈다고 다른 하나가 면제되지 않습니다. PFIC는 이름만 짚습니다. Form 8621로 보고하고 초과 분배에는 무거운 과세 구조가 있습니다.

### Tiếng Việt (bản dịch sơ khởi)

Hai hồ sơ này hay bị tưởng là trùng lặp, nhưng không phải. FBAR dựa trên 31 U.S.C. § 5314: FinCEN Form 114 nộp cho FinCEN, không kèm tờ khai thuế, báo cáo tài khoản ngân hàng và tài chính nước ngoài khi tổng giá trị vượt 10.000 đô la tại bất kỳ thời điểm nào trong năm. Đây chỉ là báo cáo, không có thuế, đến hạn 15 tháng 4 và tự động gia hạn đến 15 tháng 10. Form 8938 dựa trên IRC § 6038D, đính kèm tờ khai thuế thu nhập, bao quát tài sản tài chính nước ngoài chỉ định — phạm vi rộng hơn tài khoản. Người khai đơn sống tại Mỹ có ngưỡng trên 50.000 đô la cuối năm hoặc trên 75.000 đô la tại bất kỳ thời điểm nào; vợ chồng khai chung gấp đôi thành 100.000 / 150.000. Không nộp Form 8938 bị phạt từ 10.000 đô la. Nộp một bên không thay cho bên kia. PFIC chỉ điểm tên: khai trên Form 8621, phần phân phối vượt mức chịu cơ chế thuế nặng.

### हिन्दी (प्रारंभिक अनुवाद)

इन दो फ़ाइलिंगों को अक्सर दोहराव समझा जाता है, पर वे अलग हैं। FBAR 31 U.S.C. § 5314 पर आधारित है: FinCEN Form 114 कर रिटर्न के साथ नहीं, FinCEN को जाता है, और विदेशी बैंक व वित्तीय खातों की रिपोर्ट करता है जब उनका कुल मूल्य वर्ष में किसी भी समय 10,000 डॉलर से अधिक हो जाए। यह केवल रिपोर्ट है, कर नहीं; देय तिथि 15 अप्रैल है और 15 अक्टूबर तक स्वतः विस्तार मिलता है। Form 8938 IRC § 6038D पर आधारित है, आयकर रिटर्न के साथ लगता है, और निर्दिष्ट विदेशी वित्तीय संपत्तियों को कवर करता है — खातों से व्यापक श्रेणी। अमेरिका में रहने वाले एकल फ़ाइलर के लिए सीमा वर्षांत में 50,000 डॉलर से अधिक या वर्ष में किसी समय 75,000 डॉलर से अधिक है; संयुक्त दंपति के लिए यह दोगुनी, 100,000 / 150,000 डॉलर है। 8938 न दाखिल करने पर जुर्माना 10,000 डॉलर से शुरू होता है। एक दायित्व पूरा करना दूसरे को नहीं चुकाता। PFIC का केवल नाम लिया गया है: Form 8621 पर रिपोर्ट होता है और उसकी अतिरिक्त वितरण राशियों पर भारी कर व्यवस्था लागू होती है।

## 四、外国人来美收入与 30% 预扣

### 中文

把镜头换到外国人。非居民外国人取得美国来源的固定、可确定、年度或周期性收入，比如股息、利息、租金，一般规则在第 871(a) 条和第 1441 条：按总额 30% 预扣，付款方先扣了再付，税收协定可以把税率降下来，有些类别甚至降到零。所以外国投资者拿到手的第一笔股息，常常已经是扣完三成的数字。另一类是与美国经营实际关联的收入（ECI），按第 871(b) 条走净额计税，能扣相关成本，税率用累进档，和居民的算法接近，只是范围限于这部分关联收入。判断顺序是先看收入是不是美国来源、再看是不是 ECI、最后看协定有没有更优惠的口径，预扣凭证和申报表再逐项对上。顺序反了，税率就容易用错。

### English

Now reverse the lens. A nonresident alien receiving U.S.-source fixed, determinable, annual or periodical income — dividends, interest, rent — faces the general rule of §§ 871(a) and 1441: 30 percent withholding on the gross amount, collected by the payer before payment. A tax treaty can lower that rate, in some categories to zero, so a foreign investor's first dividend often arrives already net of the 30 percent. The other lane is income effectively connected with a U.S. trade or business (ECI), taxed on a net basis under § 871(b): related deductions are allowed and graduated rates apply, much like for residents, but only on that connected income. Work in order — is the income U.S.-source, is it ECI, does a treaty give a better rate — then match withholding documents to the return. Reverse the order and the rate is easily wrong.

### Español (译稿 de estudio)

Invierta ahora la mirada. El extranjero no residente que recibe ingresos de fuente estadounidense de tipo fijo y periódico — dividendos, intereses, alquileres — se enfrenta a la regla general de las secciones 871(a) y 1441: retención del 30 por ciento sobre el bruto, que el pagador descuenta antes de pagar. Un convenio fiscal puede bajar ese tipo, en algunas categorías hasta cero, así que el primer dividendo de un inversor extranjero suele llegar ya neto. La otra vía es el ingreso efectivamente vinculado a una actividad en EE. UU. (ECI), gravado sobre base neta por la sección 871(b): se permiten deducciones vinculadas y se aplican tipos progresivos, parecido al residente, pero solo sobre ese ingreso. El orden de análisis es: fuente estadounidense, ECI o no, y convenio aplicable; luego se concilian los documentos de retención con la declaración.

### 한국어 (초역)

이제 반대쪽을 봅니다. 비거주 외국인이 배당, 이자, 임대료 같은 미국 원천의 고정·주기 소득을 받으면 제871(a)조와 제1441조의 일반 규칙이 적용됩니다. 총액의 30퍼센트를 지급자가 먼저 원천징수하고, 조세조약이 세율을 낮출 수 있으며 일부는 0까지 내려갑니다. 그래서 외국 투자자의 첫 배당은 대개 30퍼센트가 빠진 금액입니다. 다른 길은 미국 사업과 실질적으로 연결된 소득(ECI)으로, 제871(b)조에 따라 순액 과세합니다. 관련 비용을 공제하고 누진세율을 쓰며 거주자와 비슷하지만 그 연결 소득에만 한정됩니다. 판단 순서는 미국 원천인지, ECI인지, 조약상 더 유리한 세율이 있는지이고, 그다음 원천징수 서류와 신고를 맞춥니다.

### Tiếng Việt (bản dịch sơ khởi)

Đổi chiều nhìn. Người nước ngoài không cư trú nhận thu nhập nguồn Mỹ dạng cố định, định kỳ — cổ tức, lãi, tiền thuê — chịu quy tắc chung tại §§ 871(a) và 1441: khấu trừ 30 phần trăm trên tổng số, người chi trả khấu trừ trước khi trả. Hiệp định thuế có thể hạ mức đó, một số loại xuống tới 0, nên cổ tức đầu tiên của nhà đầu tư nước ngoài thường đã bị trừ 30 phần trăm. Làn còn lại là thu nhập liên kết thực chất với hoạt động kinh doanh tại Mỹ (ECI), đánh trên cơ sở ròng theo § 871(b): được trừ chi phí liên quan và áp biểu lũy tiến như cư dân, nhưng chỉ trên phần thu nhập liên kết đó. Thứ tự xét là: có phải nguồn Mỹ không, có phải ECI không, hiệp định có mức tốt hơn không, rồi đối chiếu chứng từ khấu trừ với tờ khai.

### हिन्दी (प्रारंभिक अनुवाद)

अब दिशा उलटें। अनिवासी विदेशी को मिलने वाली अमेरिकी स्रोत की निश्चित, आवधिक आय — लाभांश, ब्याज, किराया — पर §§ 871(a) और 1441 का सामान्य नियम लागू होता है: सकल राशि पर 30 प्रतिशत withholding, जो भुगतानकर्ता भुगतान से पहले काटता है। कर संधि इस दर को घटा सकती है, कुछ श्रेणियों में शून्य तक, इसलिए विदेशी निवेशक का पहला लाभांश अक्सर 30 प्रतिशत कटकर ही आता है। दूसरा मार्ग अमेरिकी व्यापार से प्रभावी रूप से जुड़ी आय (ECI) है, जिस पर § 871(b) के तहत निवल आधार पर कर लगता है: संबंधित कटौतियाँ मिलती हैं और क्रमिक दरें लागू होती हैं, निवासियों जैसी, पर केवल उसी जुड़ी आय पर। क्रम यह है — आय अमेरिकी स्रोत की है या नहीं, ECI है या नहीं, संधि बेहतर दर देती है या नहीं — फिर withholding दस्तावेज़ों को रिटर्न से मिलाएँ।

## 五、罚则与补救

### 中文

罚则先看 FBAR。故意不报，罚得很重；非故意则是另一套尺度。最高法院在 Bittner v. United States, 598 U.S. 85 (2023) 里明确，非故意罚按每份报告计、不是按每个账户计，上限是每份年度报告 10,000 美元。这个区别很实际：漏报一年里有五个账户，不再是简单地乘以五。Form 8938 这边，未申报的罚则从 10,000 美元起步，IRS 通知后还不补，罚则会继续往上加。已经漏了怎么办，补救通道只点名不展开：一是一般的自愿披露安排，二是针对海外居民等情形的 Streamlined 程序，两条路的资格和后果差别很大，选错路代价不小。共同的底线是先把漏报的年份和金额理清，再决定走哪条路，不要先补一张表把其余年份晾在那里。

### English

Start penalties with the FBAR. Willful failures are punished heavily; non-willful failures follow a different scale. In Bittner v. United States, 598 U.S. 85 (2023), the Supreme Court held that the non-willful penalty is computed per report, not per account, capped at $10,000 for each annual report. The difference is practical: five unreported accounts in one year are no longer simply multiplied by five. On the Form 8938 side, the failure-to-file penalty starts at $10,000 and can keep growing after IRS notice if the filing is still not made. For repair, two channels are named without detail: the general voluntary disclosure practice and the Streamlined procedures for certain taxpayers abroad. Their eligibility and consequences differ sharply, and choosing the wrong lane is costly. The shared first step is to map the missed years and amounts before filing anything piecemeal.

### Español (译稿 de estudio)

Empiece las sanciones por el FBAR. El incumplimiento doloso se castiga con dureza; el no doloso sigue otra escala. En Bittner v. United States, 598 U.S. 85 (2023), el Tribunal Supremo decidió que la multa no dolosa se calcula por informe, no por cuenta, con tope de 10.000 dólares por informe anual. La diferencia es práctica: cinco cuentas no declaradas en un año ya no se multiplican simplemente por cinco. En el Formulario 8938, la multa por no presentar parte de 10.000 dólares y puede seguir creciendo tras el aviso del IRS si no se presenta. Para corregir, se nombran dos vías sin desarrollarlas: la divulgación voluntaria general y los procedimientos Streamlined para ciertos contribuyentes en el extranjero. Sus requisitos y consecuencias difieren mucho. El primer paso común es ordenar años e importes omitidos antes de presentar nada por partes.

### 한국어 (초역)

벌칙은 FBAR부터 보세요. 고의적 미신고는 무겁게 처벌되고, 비고의적 미신고는 다른 잣대를 씁니다. 대법원은 Bittner v. United States, 598 U.S. 85 (2023)에서 비고의 벌칙은 계좌별이 아니라 보고서별로 계산되며 연간 보고서당 상한이 10,000달러라고 판단했습니다. 실질적 차이가 큽니다. 한 해에 다섯 개 계좌를 빠뜨렸다고 단순히 다섯 배가 되지 않습니다. Form 8938 쪽은 미신고 벌칙이 10,000달러부터 시작하고, IRS 통지 후에도 내지 않으면 계속 늘어날 수 있습니다. 구제 경로는 이름만 짚습니다. 일반적인 자진 공개 제도와 해외 거주자 등을 위한 Streamlined 절차인데, 자격과 결과가 크게 달라 잘못 고르면 대가가 큽니다. 공통된 첫 단계는 한 장을 급히 내기 전에 빠진 연도와 금액을 먼저 정리하는 것입니다.

### Tiếng Việt (bản dịch sơ khởi)

Xem phạt từ FBAR trước. Không khai do cố ý bị phạt nặng; không cố ý theo thang khác. Trong Bittner v. United States, 598 U.S. 85 (2023), Tòa Tối cao phán quyết tiền phạt không cố ý tính theo mỗi báo cáo, không theo mỗi tài khoản, trần 10.000 đô la cho mỗi báo cáo năm. Khác biệt rất thực tế: năm tài khoản chưa khai trong một năm không còn đơn giản nhân năm. Phía Form 8938, phạt không nộp bắt đầu ở 10.000 đô la và có thể tiếp tục tăng sau thông báo của IRS nếu vẫn không nộp. Về khắc phục, chỉ điểm tên hai kênh: tự nguyện tiết lộ chung và thủ tục Streamlined cho một số người nộp thuế ở nước ngoài. Điều kiện và hậu quả của chúng khác nhau nhiều, chọn sai đường tốn kém. Bước đầu chung là làm rõ các năm và số tiền đã bỏ sót trước khi nộp lẻ tẻ.

### हिन्दी (प्रारंभिक अनुवाद)

जुर्माने FBAR से शुरू करें। जानबूझकर न दाखिल करना भारी दंड पाता है; गैर-इरादतन चूक का पैमाना अलग है। Bittner v. United States, 598 U.S. 85 (2023) में सर्वोच्च न्यायालय ने कहा कि गैर-इरादतन जुर्माना प्रति खाता नहीं, प्रति रिपोर्ट गिना जाता है, प्रत्येक वार्षिक रिपोर्ट पर अधिकतम 10,000 डॉलर। अंतर व्यावहारिक है: एक वर्ष के पाँच अघोषित खाते अब सीधे पाँच गुना नहीं होते। Form 8938 की ओर, न दाखिल करने का जुर्माना 10,000 डॉलर से शुरू होता है और IRS नोटिस के बाद भी दाखिल न करने पर बढ़ सकता है। सुधार के दो मार्ग केवल नाम से दिए गए हैं: सामान्य स्वैच्छिक प्रकटीकरण और विदेश में रहने वाले कुछ करदाताओं के लिए Streamlined प्रक्रियाएँ। उनकी पात्रता और परिणाम बहुत अलग हैं। साझा पहला कदम है, अलग-अलग दाखिल करने से पहले छूटे हुए वर्षों और राशियों को साफ़ करना।

## 六、加州口径：没有 FEIE 对应排除

### 中文

最后落到加州。结论一句话：加州没有 FEIE 对应排除。联邦税表上用第 911 条排除掉的那部分外国工资，到了加州要加回来算。依据是加州对居民的全球收入征税，RTC 第 17041 条对加州居民的全部收入课税，不分来源；加州税法不采用第 911 条的排除安排，所以在国外挣的工资仍计入加州总收入。非居民则不同，只就加州来源收入计税。实务上最常见的错位是：联邦靠 FEIE 把税压得很低，人就以为州税也同步消失，结果加州那份表照样要按全额工资算。填州表之前，先把联邦排除额单独列出来，再决定州表的加回项，顺序别颠倒。

### English

End in California. The one-line answer: California has no FEIE counterpart exclusion. Wages excluded federally under § 911 are added back for California purposes. California taxes residents on worldwide income — RTC § 17041 reaches all income of a California resident regardless of source — and California law does not adopt the § 911 exclusion, so wages earned abroad still enter California total income. Nonresidents are taxed only on California-source income. The common mismatch is practical: FEIE drives the federal bill down and the taxpayer assumes the state bill vanished with it, while California still computes on the full wages. Before preparing the state return, list the federal exclusion separately and work out the state add-back; keep that order.

### Español (译稿 de estudio)

Terminemos en California. La respuesta en una línea: California no tiene una exclusión equivalente a la FEIE. El salario excluido en el plano federal por la sección 911 se vuelve a sumar en California. El estado grava a sus residentes por la renta mundial — la RTC sección 17041 alcanza toda la renta del residente sin importar la fuente — y la ley californiana no adopta la exclusión de la sección 911, así que el salario ganado fuera sigue entrando en la renta total de California. El no residente solo tributa por la renta de fuente californiana. El error práctico es frecuente: la FEIE baja la factura federal y se supone que la estatal desapareció con ella, cuando California sigue calculando sobre el salario completo. Antes de preparar la declaración estatal, anote la exclusión federal por separado y calcule la suma de vuelta.

### 한국어 (초역)

마지막은 캘리포니아입니다. 한 줄 결론으로, 캘리포니아에는 FEIE에 대응하는 공제가 없습니다. 연방에서 제911조로 제외한 임금은 캘리포니아에서는 다시 더해집니다. 캘리포니아는 거주자에게 전 세계 소득에 과세하는데, RTC 제17041조는 출처와 무관하게 거주자의 모든 소득에 미치고, 주법은 제911조 공제를 채택하지 않으므로 해외에서 번 임금도 캘리포니아 총소득에 들어갑니다. 비거주자는 캘리포니아 원천 소득에만 과세됩니다. 흔한 어긋남은 실무적입니다. FEIE로 연방 세금이 낮아지면 주 세금도 사라졌다고 생각하지만, 캘리포니아는 임금 전액으로 계산합니다. 주 신고를 준비하기 전에 연방 공제액을 따로 적고 주 차원의 가산을 계산하세요.

### Tiếng Việt (bản dịch sơ khởi)

Kết lại ở California. Câu trả lời một dòng: California không có loại trừ tương ứng với FEIE. Phần lương được loại trừ ở cấp liên bang theo § 911 phải cộng lại cho California. Bang đánh thuế cư dân trên thu nhập toàn cầu — RTC § 17041 chạm tới mọi thu nhập của cư dân California bất kể nguồn — và luật California không áp dụng loại trừ § 911, nên lương kiếm ở nước ngoài vẫn vào tổng thu nhập California. Người không cư trú chỉ chịu thuế trên thu nhập nguồn California. Lệch pha thường gặp rất thực tế: FEIE kéo thuế liên bang xuống thấp và người nộp tưởng thuế bang cũng biến mất theo, trong khi California vẫn tính trên toàn bộ lương. Trước khi làm tờ khai bang, hãy liệt kê riêng phần loại trừ liên bang rồi tính khoản cộng lại của bang.

### हिन्दी (प्रारंभिक अनुवाद)

अंत में कैलिफ़ोर्निया। एक पंक्ति का उत्तर: कैलिफ़ोर्निया में FEIE जैसी कोई समकक्ष छूट नहीं है। § 911 के तहत संघीय स्तर पर छूटा वेतन कैलिफ़ोर्निया के लिए वापस जोड़ा जाता है। राज्य निवासियों पर विश्वव्यापी आय पर कर लगाता है — RTC § 17041 निवासी की समस्त आय तक पहुँचता है, स्रोत चाहे जो हो — और कैलिफ़ोर्निया कानून § 911 की छूट नहीं अपनाता, इसलिए विदेश में कमाया वेतन भी कैलिफ़ोर्निया की कुल आय में जाता है। अनिवासी केवल कैलिफ़ोर्निया स्रोत आय पर कर देता है। आम गड़बड़ी व्यावहारिक है: FEIE संघीय बिल घटा देती है और करदाता मान लेता है राज्य बिल भी साथ गायब हो गया, जबकि कैलिफ़ोर्निया पूरे वेतन पर गणना करती है। राज्य रिटर्न से पहले संघीय बहिष्करण अलग से लिखें और राज्य की वापस-जोड़ राशि निकालें।

## 来源与说明 / Sources / Fuentes / 출처 / Nguồn / स्रोत

主要出处：IRC 第 61 条、第 1 条（全球征税）、第 7701(b) 条（绿卡测试与实质居住测试）、第 911 条（FEIE）、第 901–909 条（FTC）、第 6038D 条（Form 8938）、第 871(a) 条、第 871(b) 条、第 1441 条（30% 预扣与 ECI 净额计税）、第 877A 条（弃籍税）；IRS Rev. Proc. 2024-40（2025 年 FEIE 上限 130,000 美元、弃籍税年均税负门槛 2025 年 206,000 美元）；31 U.S.C. 第 5314 条与 FinCEN Form 114 说明（FBAR 门槛 10,000 美元、4 月 15 日到期自动延期至 10 月 15 日）；Bittner v. United States, 598 U.S. 85 (2023)（非故意 FBAR 罚按每份报告计、上限 10,000 美元）；Form 2555、1116、8938、8621 说明；IRS 国际税务页面（U.S. Citizens and Resident Aliens Abroad、Foreign Earned Income Exclusion、Foreign Tax Credit、FATCA 与 FBAR 对照页）；加州 RTC 第 17041 条与加州税务局（FTB）居民全球收入口径（加州没有 FEIE 对应排除）。

Key sources: IRC §§ 61, 1, 7701(b), 911, 901–909, 6038D, 871(a), 871(b), 1441, 877A; IRS Rev. Proc. 2024-40; 31 U.S.C. § 5314 and FinCEN Form 114 instructions; Bittner v. United States, 598 U.S. 85 (2023); Forms 2555, 1116, 8938, 8621; IRS international taxation pages; California RTC § 17041 and FTB guidance.

Fuentes principales: IRC, secciones 61, 1, 7701(b), 911, 901 a 909, 6038D, 871(a), 871(b), 1441 y 877A; Rev. Proc. 2024-40 del IRS; 31 U.S.C. sección 5314 y FinCEN Form 114; Bittner v. United States, 598 U.S. 85 (2023); Formularios 2555, 1116, 8938 y 8621; páginas internacionales del IRS; RTC sección 17041 y FTB de California.

주요 출처: IRC 제61·1·7701(b)·911·901–909·6038D·871(a)·871(b)·1441·877A조; IRS Rev. Proc. 2024-40; 31 U.S.C. 제5314조와 FinCEN Form 114; Bittner v. United States, 598 U.S. 85 (2023); Form 2555·1116·8938·8621; IRS 국제 과세 페이지; 캘리포니아 RTC 제17041조와 FTB.

Nguồn chính: IRC §§ 61, 1, 7701(b), 911, 901–909, 6038D, 871(a), 871(b), 1441, 877A; IRS Rev. Proc. 2024-40; 31 U.S.C. § 5314 và FinCEN Form 114; Bittner v. United States, 598 U.S. 85 (2023); Forms 2555, 1116, 8938, 8621; trang thuế quốc tế của IRS; California RTC § 17041 và FTB.

मुख्य स्रोत: IRC §§ 61, 1, 7701(b), 911, 901–909, 6038D, 871(a), 871(b), 1441, 877A; IRS Rev. Proc. 2024-40; 31 U.S.C. § 5314 और FinCEN Form 114; Bittner v. United States, 598 U.S. 85 (2023); Forms 2555, 1116, 8938, 8621; IRS अंतरराष्ट्रीय कर पृष्ठ; कैलिफ़ोर्निया RTC § 17041 और FTB।

西班牙语为学习译稿，韩语、越南语、印地语为初译待校。El texto en español es una traducción de estudio, pendiente de revisión nativa. 한국어·베트남어·힌디어 본문은 초역으로, 원어민 감수를 기다리고 있습니다. Bản tiếng Hàn, tiếng Việt và tiếng Hindi là bản dịch sơ khởi, đang chờ người bản ngữ hiệu đính. कोरियाई, वियतनामी और हिंदी पाठ प्रारंभिक अनुवाद हैं; मूल-भाषी समीक्षा लंबित है।

声明：本篇为个人学习笔记，不构成税务、财务或法律建议。This article is a personal study note only and does not constitute tax, financial, or legal advice. Este artículo es una nota personal de estudio y no constituye asesoría fiscal, financiera ni legal. 본 글은 개인 학습 노트이며 세무·재무·법률 자문이 아닙니다. Bài viết này là ghi chú học tập cá nhân, không cấu thành tư vấn thuế, tài chính hay pháp lý. यह लेख एक व्यक्तिगत अध्ययन नोट है और यह कर, वित्तीय या कानूनी सलाह नहीं है।
