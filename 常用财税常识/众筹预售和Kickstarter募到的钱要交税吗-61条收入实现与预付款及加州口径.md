# 众筹预售和 Kickstarter 募到的钱要交税吗：61 条收入实现与预付款及加州口径

> 个人学习笔记，不构成税务建议。本文以联邦《国内收入法典》现行条文与 IRS 公开指引为据；众筹款项的定性先分清是生意预售、股权还是纯赠与，三条路的税完全不同。

## 中文主文

### 一、先分流：你收到的到底是哪一种钱

- **奖励型/预售型众筹（本篇主角）**：支持者付款、将来拿产品或服务——这在税法上是生意收入或生意预付款，不是赠与。Kickstarter、Indiegogo 上为做产品募的钱都走这条。
- **捐赠型众筹**：为医疗、灾难等个人困难募捐、给钱的人无求回报的，才可能落入第 102 条赠与排除（判断核心是给付人的无求回报意图，见本仓 Duberstein 案与众筹篇）。把产品预售包装成「捐赠」，定性不会跟着包装走。
- **股权型众筹**：按 Regulation Crowdfunding 等证券路径发行权益的，收到的是资本不是收入，但走证券合规与信息申报，与本篇分开。

### 二、收入何时算你的：第 61 条与第 451 条

- **总收入的入口**：第 61 条 (a) 把「来自任何来源的全部收入」都圈进来。众筹预售款一旦你取得无限制的支配（平台放款到账、不是还在托管待达标），就已进入总收入的讨论范围，剩下的只是哪一年确认。
- **权责发生制纳税人的预付款规则**：第 451 条 (c) 是预售款的关键条文——采用权责发生制并有适用财务报表（AFS）的纳税人，预收的商品/服务对价可按第 451(c) 的递延方法处理：与 AFS 收入确认进度衔接，但递延不是无限期的，Reg. § 1.451-8 给出的框架是预付款至迟在收到后的下一个纳税年度内计入（one-year deferral 的基本盘），且未交付部分的口径以规章为准。现金制纳税人没有这层递延讨论：收到即可支配的那一年计入。
- **达标才放款的平台结构**：全有或全无（all-or-nothing）模式里，项目未达标、钱还在平台托管且你无法动用时，一般还谈不上你的收入实现；达标放款后才起算。留好平台结算单与达标日期，这是年份归属的第一证据。

### 三、先算个例：预售 10 万美元、年底只交付一部分

- 设某现金制创作者 2026 年达标收到预售款 100,000 美元，年内已发货部分对应的可扣除成本（材料、代工、运费）38,000 美元，其余产品 2027 年交付。现金制下：2026 年计入收入 100,000 美元，可扣除的已发生经营成本按现金制时点扣（已付的 38,000 美元在 2026 年扣，2027 年再发生的成本在 2027 年扣）——收入先行、成本滞后是现金制预售最常见的现金流错位，季度预估税要按全额收入先备。
- 换作符合第 451(c) 递延条件的权责发生制纳税人：若其 AFS 在 2026 年只确认了已交付部分的收入 40,000 美元，则 2026 年先计入 40,000 美元，剩余 60,000 美元至迟在 2027 年（收到后的下一纳税年度）全部计入，哪怕货还没发完。两组数字并排看：现金制 100,000 全进 2026；451(c) 路径 40,000 进 2026、60,000 进 2027。方法选错，年份就错。

### 四、能扣什么：成本别等发货才想起来

- **可扣的经营费用**：产品材料、代工与包装、平台佣金与支付处理费、运费、为项目做的广告与样品——按第 162 条普通与必要经营费用框架，时点按你的会计方法走。
- **存货这条线不能绕**：卖货的生意原则上要走存货与销货成本（第 471 条一带），收入确认与成本结转要配比；小企业有第 448(c) 毛收入门槛下的简化与豁免讨论（门槛按年通胀调整，以当期 Rev. Proc. 为准），是否适用先核资格再动手，别默认「小就不用管存货」。
- **个人开支不混入**：设备若公私两用要留使用记录；把个人消费塞进项目成本，是众筹查税里最容易被整段否掉的一类。

### 五、信息申报：1099-K 会来，先对账再报税

- 平台与支付处理商可能就众筹收款发出 Form 1099-K。第 6050W 条的报告门槛经历过反复：现行口径以 IRS 当期公告为准（立法已将门槛恢复为 20,000 美元且 200 笔交易的旧框架方向，执行细节以 IRS 2026 年报税季指引为最终依据——本笔记不把过渡口径写死）。
- **对账动作**：1099-K 上是总额（含退款前、含平台费前），报税时按账簿的净口径走并留对账表：总额减退款、减平台费，再与收入确认年份核对。收到与你无关或金额明显错位的 1099-K，先联系发单方更正，别直接忽略。

### 六、州税与销售税：加州口径

- **所得税**：加州对众筹生意收入按一般生意收入课税（个人走 Schedule C 的州对应口径、公司走特许税体系），加州不完全跟随联邦第 451(c) 的递延细节，州申报时要做州调整（以 FTB 当期说明为准）。
- **销售税**：向加州买家预售实物产品，属应税零售的，卖家要有 CDTFA 卖家许可证并就加州内销售申报销售税——达标金额里含税还是不含税，要在项目页写清，后补税款最伤毛利。众筹阶段是否已有销售税征收时点，取决于交易结构与 CDTFA 口径，金额大时先书面确认再上线。

> 声明：本文为个人学习笔记，不构成税务建议。来源：I.R.C. §§ 61(a)、102、162、448(c)、451(c)、471、6050W；Treas. Reg. § 1.451-8；IRS 众筹与 Form 1099-K 公开指引（募资定性与对账口径）；Cal. Rev. & Tax. Code 一般生意收入与 CDTFA 卖家许可口径（州调整以 FTB 当期说明为准）。

## English
Money raised in a rewards-based crowdfunding campaign is business income, not a gift. Section 61(a) sweeps in income from whatever source derived; once platform funds are released to you without restriction, the only real question is the year of inclusion. All-or-nothing campaigns are different while funds sit in escrow before the goal is met — keep the settlement statement and the funding date as your primary evidence. For accrual-method taxpayers with an applicable financial statement, section 451(c) and Regulation section 1.451-8 allow advance payments to follow AFS recognition, but deferral is capped: the balance must be taken into income no later than the taxable year after receipt. A cash-method creator has no such deferral. Worked example: a cash-method creator receives 100,000 dollars in 2026 and pays 38,000 dollars of production costs that year — all 100,000 is 2026 income and estimated taxes must be budgeted on the full amount. Under section 451(c), if the AFS recognizes only 40,000 dollars in 2026, then 40,000 is included in 2026 and the remaining 60,000 no later than 2027 even if shipment is incomplete. Deductible costs follow section 162 (materials, contract manufacturing, platform and payment fees, shipping, promotion), but a business selling products must respect the inventory and cost-of-goods rules around section 471, subject to the small-business relief tied to the section 448(c) gross receipts test. Platforms may issue Form 1099-K under section 6050W; the form shows gross amounts before refunds and fees, so reconcile it to your books rather than copying it onto the return. In California, the income is taxed as ordinary business income with state adjustments (California does not simply mirror section 451(c)), and pre-selling taxable tangible goods to California buyers generally requires a CDTFA seller's permit and sales tax collection — decide whether your goal amount is tax-inclusive before you launch, not after.

## Español (traducción de estudio)
El dinero de una campaña de crowdfunding con recompensas es ingreso comercial, no donación. El § 61(a) abarca ingresos de cualquier fuente; cuando la plataforma libera los fondos sin restricción, la única pregunta es el año de inclusión (mientras el dinero sigue en custodia en campañas de «todo o nada», aún no hay ingreso: conserve el comprobante de liquidación y la fecha de financiamiento). Para contribuyentes de devengo con estados financieros aplicables, el § 451(c) y el Reg. § 1.451-8 permiten seguir el reconocimiento contable, pero con tope: el saldo debe incluirse a más tardar en el año siguiente al cobro; el método de caja no tiene diferimiento. Ejemplo: un creador en método de caja recibe 100.000 dólares en 2026 y paga 38.000 de costos ese año — los 100.000 completos son ingreso de 2026 y los pagos estimados deben calcularse sobre el total. Con § 451(c), si los estados reconocen solo 40.000 en 2026, se incluyen 40.000 en 2026 y los 60.000 restantes a más tardar en 2027 aunque falten envíos. Los costos deducibles siguen el § 162 (materiales, fabricación, comisiones de plataforma y de pago, envíos, promoción), pero vender productos exige respetar las reglas de inventario del § 471, con alivios para pequeñas empresas ligados al test de ingresos brutos del § 448(c). La plataforma puede emitir el Formulario 1099-K (§ 6050W) por montos brutos, antes de reembolsos y comisiones: concílielo con su contabilidad. En California, el ingreso tributa como ingreso comercial ordinario con ajustes estatales (California no replica simplemente el § 451(c)), y la preventa de bienes tangibles gravables a compradores californianos exige en general permiso de vendedor de CDTFA y cobro del impuesto sobre ventas: defina si su meta incluye el impuesto antes de lanzar, no después.

## 한국어 (초역, 원어민 감수 대기)
리워드형 크라우드펀딩으로 모은 돈은 증여가 아니라 사업소득입니다. § 61(a)는 출처를 묻지 않고 모든 소득을 포괄하며, 플랫폼이 자금을 제한 없이 지급한 시점부터 문제는 귀속 연도뿐입니다(올오어낫싱 구조에서 목표 미달로 자금이 에스크로에 있는 동안은 아직 소득이 아닙니다. 정산서와 펀딩 확정일을 증거로 보관하십시오). 적용 재무제표가 있는 발생주의 납세자는 § 451(c)와 Reg. § 1.451-8에 따라 선수금을 재무제표 인식에 맞출 수 있으나 이연에는 상한이 있어 잔액은 수령 다음 과세연도까지는 반드시 소득에 산입해야 합니다. 현금주의 창작자에게는 이 이연이 없습니다. 예시: 현금주의 창작자가 2026년에 100,000달러를 받고 그해 제작비 38,000달러를 지출하면 100,000달러 전액이 2026년 소득이며 예정세도 전액 기준으로 준비해야 합니다. § 451(c) 경로에서는 재무제표가 2026년에 40,000달러만 인식하면 2026년에 40,000달러, 나머지 60,000달러는 배송이 끝나지 않았어도 2027년까지 산입합니다. 비용은 § 162를 따르지만(재료, 외주 제작, 플랫폼·결제 수수료, 배송, 홍보), 제품을 파는 사업은 § 471의 재고 규칙을 지켜야 하며 § 448(c) 총수입 테스트에 연동된 소기업 완화가 있습니다. 플랫폼은 § 6050W에 따라 환불·수수료 차감 전 총액으로 Form 1099-K를 발행할 수 있으니 장부와 대조하십시오. 캘리포니아에서는 일반 사업소득으로 과세되고 주 조정이 필요하며(캘리포니아는 § 451(c)를 그대로 따르지 않습니다), 캘리포니아 구매자에게 과세 대상 유형 상품을 사전 판매하면 일반적으로 CDTFA 판매자 허가와 판매세 징수가 필요합니다. 목표 금액에 세금이 포함되는지는 출시 전에 정하십시오.

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)
Tiền huy động qua crowdfunding có thưởng là thu nhập kinh doanh, không phải quà tặng. § 61(a) bao quát thu nhập từ mọi nguồn; khi nền tảng giải ngân không hạn chế, câu hỏi duy nhất là năm ghi nhận (với mô hình tất cả hoặc không có gì, tiền còn trong ký quỹ khi chưa đạt mục tiêu thì chưa là thu nhập — hãy giữ chứng từ quyết toán và ngày đạt mục tiêu). Người nộp thuế theo cơ sở dồn tích có báo cáo tài chính áp dụng có thể dùng § 451(c) và Reg. § 1.451-8 để ghi nhận khoản trả trước theo tiến độ báo cáo tài chính, nhưng việc hoãn có trần: phần còn lại phải tính vào thu nhập chậm nhất là năm tính thuế sau năm nhận tiền. Người theo cơ sở tiền mặt không có cơ chế hoãn này. Ví dụ: một nhà sáng tạo theo cơ sở tiền mặt nhận 100.000 đô la năm 2026 và chi 38.000 đô la chi phí sản xuất trong năm — toàn bộ 100.000 là thu nhập 2026 và thuế tạm tính phải dự trù trên toàn bộ số tiền. Theo § 451(c), nếu báo cáo tài chính chỉ ghi nhận 40.000 năm 2026, thì 40.000 tính vào 2026 và 60.000 còn lại chậm nhất vào 2027 dù chưa giao xong hàng. Chi phí được trừ theo § 162 (vật liệu, gia công, phí nền tảng và thanh toán, vận chuyển, quảng bá), nhưng kinh doanh bán sản phẩm phải tuân thủ quy tắc hàng tồn kho của § 471, với giảm nhẹ cho doanh nghiệp nhỏ gắn với kiểm tra tổng doanh thu § 448(c). Nền tảng có thể phát hành Form 1099-K theo § 6050W theo số tổng trước hoàn tiền và phí — hãy đối chiếu với sổ sách. Tại California, thu nhập bị đánh thuế như thu nhập kinh doanh thông thường kèm điều chỉnh của bang (California không sao chép nguyên § 451(c)), và việc bán trước hàng hóa hữu hình chịu thuế cho người mua ở California thường cần giấy phép người bán của CDTFA và thu thuế bán hàng — hãy quyết định số tiền mục tiêu có gồm thuế hay không trước khi ra mắt.

## हिन्दी (प्रारंभिक अनुवाद, समीक्षा लंबित)
रिवॉर्ड-आधारित क्राउडफंडिंग से जुटाया धन उपहार नहीं, व्यावसायिक आय है। § 61(a) किसी भी स्रोत की आय को समेटता है; जब प्लेटफ़ॉर्म धन बिना प्रतिबंध जारी कर दे, तो एकमात्र प्रश्न शामिल करने का वर्ष है (ऑल-ऑर-नथिंग अभियानों में लक्ष्य पूरा होने से पहले एस्क्रो में रखा धन अभी आय नहीं है — निपटान विवरण और फंडिंग तिथि सबूत के रूप में रखें)। लागू वित्तीय विवरण वाले उपार्जन-आधारित करदाताओं के लिए § 451(c) और Reg. § 1.451-8 अग्रिम भुगतानों को वित्तीय विवरण मान्यता के साथ जोड़ने देते हैं, पर स्थगन की सीमा है: शेष राशि प्राप्ति के अगले कर वर्ष तक आय में शामिल करनी ही होगी। नकद-आधारित रचनाकार को यह स्थगन नहीं मिलता। उदाहरण: नकद-आधारित रचनाकार 2026 में 100,000 डॉलर पाता है और उसी वर्ष 38,000 डॉलर उत्पादन लागत देता है — पूरे 100,000 ही 2026 की आय हैं और अनुमानित कर भी पूरी राशि पर रखना होगा। § 451(c) के तहत यदि वित्तीय विवरण 2026 में केवल 40,000 मान्यता देता है, तो 40,000 सन् 2026 में और शेष 60,000 शिपमेंट अधूरा होने पर भी 2027 तक शामिल होंगे। लागतें § 162 के अनुसार कटौती योग्य हैं (सामग्री, अनुबंध निर्माण, प्लेटफ़ॉर्म व भुगतान शुल्क, शिपिंग, प्रचार), पर उत्पाद बेचने वाले व्यवसाय को § 471 के इन्वेंटरी नियम मानने होंगे, जिनमें § 448(c) सकल प्राप्ति परीक्षण से जुड़ी लघु-व्यवसाय राहत है। प्लेटफ़ॉर्म § 6050W के तहत रिफंड व शुल्क से पहले की सकल राशि का Form 1099-K जारी कर सकता है — उसे अपनी बहियों से मिलान करें। कैलिफ़ोर्निया में यह आय सामान्य व्यावसायिक आय के रूप में राज्य समायोजनों सहित करयोग्य है (कैलिफ़ोर्निया § 451(c) की सीधी नकल नहीं करता), और कैलिफ़ोर्निया खरीदारों को करयोग्य मूर्त वस्तुओं की प्री-सेल पर सामान्यतः CDTFA विक्रेता परमिट व बिक्री कर संग्रह चाहिए — लक्ष्य राशि कर-सहित है या नहीं, यह लॉन्च से पहले तय करें।

## 补译增量（2026-11-06 追加：韩／越／印三语各补 2 段细节增量，与中文主文细节对齐，正文原有段落未改动）

### 한국어 보충 (초역, 원어민 감수 대기)

보충 1 — 인벤토리(재고) 라인을 우회할 수 없는 이유: 제품을 파는 사업은 원칙적으로 § 471의 재고와 매출원가 틀을 따라야 하며, 선수금을 받았다는 사실이 비용을 먼저 전액 공제할 근거가 되지는 않습니다. § 448(c) 총수입 테스트에 연동된 소기업 간소화는 자격을 먼저 확인한 뒤에만 적용되는 논의이지, 규모가 작다는 이유만으로 자동 적용되는 면제가 아닙니다. 실무에서 흔한 오류는 플랫폼 정산액(수수료를 뺀 순액)을 그대로 매출로 잡는 것으로, 총액 기준 장부와 정산서 대조표를 남기지 않으면 1099-K 총액과의 차이가 설명되지 않습니다.

보충 2 — 캘리포니아 판매세의 시점 문제: 캘리포니아 구매자에게 과세 대상 유형 상품을 사전 판매하면, 펀딩 목표액에 판매세가 포함되는지 여부를 프로젝트 페이지 단계에서 정해 두어야 합니다. 나중에 세금을 매입자에게 소급 청구하는 구조는 사실상 불가능에 가깝고, 결국 판매자 마진에서 빠져나갑니다. 징수 시점이 펀딩 확정 시점인지 배송 시점인지는 거래 구조와 CDTFA 해석에 따라 달라질 수 있으므로, 금액이 큰 캠페인은 출시 전에 서면으로 확인하는 편이 안전하며, 이 확인 없이 진행한 경우의 위험은 세금이 아니라 마진 전체에 걸린다는 점이 본문이 경고하는 지점입니다.

### Bổ sung Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

Bổ sung 1 — Vì sao không thể bỏ qua tuyến hàng tồn kho: doanh nghiệp bán sản phẩm về nguyên tắc phải theo khung hàng tồn kho và giá vốn của § 471; việc đã nhận tiền trả trước không phải là căn cứ để khấu trừ toàn bộ chi phí trước. Cơ chế đơn giản hóa cho doanh nghiệp nhỏ gắn với kiểm tra tổng doanh thu § 448(c) chỉ là một thảo luận phải xác minh điều kiện trước khi áp dụng, không phải miễn trừ tự động chỉ vì quy mô nhỏ. Lỗi thực hành phổ biến là ghi doanh thu theo số tiền quyết toán ròng sau phí nền tảng; nếu không giữ sổ theo tổng số và bảng đối chiếu quyết toán, chênh lệch với tổng số trên Form 1099-K sẽ không giải thích được.

Bổ sung 2 — Vấn đề thời điểm của thuế bán hàng California: khi bán trước hàng hóa hữu hình chịu thuế cho người mua ở California, phải quyết định ngay từ trang dự án xem số tiền mục tiêu gây quỹ có gồm thuế bán hàng hay không. Cấu trúc thu hồi thuế từ người mua về sau gần như không khả thi, và cuối cùng phần thuế sẽ ăn vào biên lợi nhuận của người bán. Thời điểm thu thuế là lúc xác nhận gây quỹ hay lúc giao hàng có thể khác nhau tùy cấu trúc giao dịch và cách hiểu của CDTFA, nên với chiến dịch lớn, xác nhận bằng văn bản trước khi ra mắt là cách an toàn; rủi ro khi bỏ qua bước này không chỉ là tiền thuế mà là toàn bộ biên lợi nhuận, đúng như bài chính cảnh báo.

### हिन्दी पूरक (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

पूरक 1 — इन्वेंटरी लाइन को क्यों नहीं टाला जा सकता: उत्पाद बेचने वाले व्यवसाय को सिद्धांततः § 471 के इन्वेंटरी व बिक्री-लागत ढाँचे का पालन करना होता है; अग्रिम भुगतान मिल जाना सभी लागतें पहले ही काट लेने का आधार नहीं बनता। § 448(c) सकल प्राप्ति परीक्षण से जुड़ी लघु-व्यवसाय सरलीकरण केवल पात्रता जाँच के बाद लागू होने वाली चर्चा है, छोटा आकार अपने आप में स्वतः छूट नहीं है। व्यवहार में आम त्रुटि प्लेटफ़ॉर्म निपटान की शुद्ध राशि (शुल्क घटाकर) को ही बिक्री मान लेना है; यदि कुल-राशि आधारित बही और निपटान मिलान तालिका न रखी जाए, तो Form 1099-K की कुल राशि से अंतर समझाया नहीं जा सकेगा।

पूरक 2 — कैलिफ़ोर्निया बिक्री कर का समय-बिंदु प्रश्न: कैलिफ़ोर्निया खरीदारों को करयोग्य मूर्त वस्तुओं की प्री-सेल करते समय परियोजना पृष्ठ के स्तर पर ही तय कर लेना चाहिए कि फंडिंग लक्ष्य राशि में बिक्री कर शामिल है या नहीं। बाद में खरीदारों से कर वसूलने की संरचना व्यावहारिक रूप से असंभव है, और अंततः कर विक्रेता के मार्जिन से ही निकलता है। संग्रह का समय फंडिंग निश्चित होने का क्षण है या डिलीवरी का, यह लेन-देन संरचना और CDTFA की व्याख्या पर निर्भर कर सकता है, इसलिए बड़े अभियानों में लॉन्च से पहले लिखित पुष्टि सुरक्षित रहती है; इस चरण को छोड़ने का जोखिम केवल कर नहीं, पूरा मार्जिन है — यही मुख्य पाठ की चेतावनी है।
