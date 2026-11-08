# 网约车与外卖骑手怎么报税：1099、里程记录、Schedule C 与自雇税

> 个人学习笔记，讲清零工平台收入的联邦报税口径与加州衔接。数字以 IRS 现行公告为准，不构成税务建议。

## 中文主文

### 一、先定性：平台司机默认是独立承包商，不是雇员

为 Uber、Lyft、DoorDash、Instacart 等平台接单，在联邦税上通常按独立承包商处理：收入是经营收入，进 Schedule C（独资经营），按 IRC § 61(a)(2) 全额申报，不是工资，没有雇主代扣。分类看控制关系而非平台的说法（参见本仓「W-2 还是 1099」一篇）；此处只讲定性为自雇之后的报法。

### 二、会收到哪几张表：NEC、K 与平台年结单

- **Form 1099-NEC**：平台支付的服务报酬（非雇员补偿）走这张表。申报门槛原为 § 6041 的 600 美元；《大而美法案》(OBBBA, P.L. 119-21) 第 70433 条把 1099 系列的信息申报门槛提高到 2,000 美元，适用于 2025 年 12 月 31 日之后支付的款项，其后按通胀调整。门槛只决定平台要不要发文件，不决定收入要不要报——没有收到表，收入也要报。
- **Form 1099-K**：乘客与顾客通过平台支付的部分历史上走 1099-K。OBBBA 把 § 6050W 的门槛恢复为「超过 20,000 美元且交易超过 200 笔」的双门槛（此前被《美国救援计划》压到 600 美元的低门槛从未真正落地执行）。两张表的金额可能重叠，报税时不能简单相加：以平台年结单 (annual summary) 的总流水为起点对账，重复计算的部分要扣除并留底稿。
- **小费**：顾客在 App 内给的小费是收入的一部分，全额计入总收入；注意 2025–2028 年 § 224 的合格小费扣除另有口径（见本仓小费扣除一篇），自雇者能否适用要看 IRS 对合格职业的清单与引导，申报前先核当年口径。

### 三、Schedule C 的收入与费用

总收入填平台流水（车费分成、奖金、高峰补贴、推荐奖励、小费），再扣平台抽成与服务费——实务上通常直接以「总流水 − 平台费用」列示或分别列收入与费用，关键是与年结单能对上。常见可扣费用（§ 162 普通且必要）：

- **车辆费用二选一**：标准里程法或实际费用法。标准里程率 2025 年为每英里 70 美分（IRS Notice 2025-5），覆盖油、电、保险、折旧与维修；用标准里程法就不能再单列这些项目。接单里程、前往接客里程与载客里程一般属经营里程，离线私人里程不算；从家里出发去第一个接单点的通勤里程通常不可扣，除非家庭构成主要营业场所等例外。
- **其他**：手机话费的经营比例、车载用品、停车费与过路费（用标准里程法也可另扣与经营相关的停车费和过路费）、平台要求的背景调查费、保温箱与充电设备等。

里程记录是审计命门：IRS 要求同期记录 (contemporaneous log)——日期、里程、用途。平台 App 的里程统计只统计载客段，务必另用里程 App 或表格补记上线空驶段，年底总量与 Schedule C 数字要对得上。

### 四、自雇税与季度预估

净利进 Schedule SE：自雇税 15.3%（社保 12.4% 在工资基数内加医保 2.9%），先乘 92.35%（§ 1402(a)(12)），自雇税的一半可依 § 164(f) 作线上调整。算例：全年净利 40,000 美元 → 计税基数 36,940 美元 → 自雇税约 5,651.82 美元，另加按边际税率计算的所得税。没有雇主代扣，就靠 Form 1040-ES 季度预估，安全港与罚息规则见本仓「季度预估税」一篇。

### 五、容易踩的四个坑

1. 只报 1099 上的数字：现金小费、平台外收入漏报是最常见审计点。
2. 1099-NEC 与 1099-K 相加报双倍收入。
3. 里程年底凭印象编总数：无同期记录，审计时整段里程扣除会被否。
4. 第一年赚钱没做预估：次年 4 月连税带罚一起补，现金流直接断档。

### 六、加州口径

加州对平台司机同样按自雇收入征州税（Form 540 + Schedule CA），季度预估用 540-ES，节奏与联邦不同（加州分期比例为 30%/40%/0%/30%）。车辆里程与费用口径加州大体跟随联邦标准里程率。另注意 AB5 (Labor Code § 2775 起) 的 ABC 测试是劳动法与失业保险层面的分类规则，与联邦税分类不是同一套标准；税上按联邦口径报，劳动法争议另行处理。

### 参考依据

IRC §§ 61(a)(2), 162, 164(f), 1401, 1402(a)(12), 6041, 6050W；OBBBA (P.L. 119-21) §§ 70201（§ 224 小费扣除）、70433；IRS Notice 2025-5（2025 年标准里程率 70 美分）；IRS 零工经济税务中心 (Gig Economy Tax Center) 与 Schedule C/SE 说明；加州 FTB 与 EDD 平台用工指引。

*声明：个人学习笔记，不构成税务建议。具体申报请咨询注册会计师或税务律师。*

---

## English

**How rideshare and delivery drivers file taxes: 1099s, mileage logs, Schedule C, and self-employment tax.** Platform drivers for Uber, Lyft, DoorDash, or Instacart are generally independent contractors for federal tax purposes: the income is business income reported on Schedule C under IRC § 61(a)(2), with no employer withholding. Platforms report service pay on Form 1099-NEC and rider/customer payments on Form 1099-K. Two thresholds changed under the OBBBA (P.L. 119-21): § 70433 raised the § 6041 information-reporting threshold to $2,000 for payments after December 31, 2025 (inflation-adjusted thereafter), and the § 6050W Form 1099-K threshold was restored to more than $20,000 and more than 200 transactions. Filing thresholds never control taxability — unreported-by-form income is still income, and the NEC and K amounts can overlap, so reconcile against the platform's annual summary rather than adding the forms together. On Schedule C, deduct ordinary and necessary expenses under § 162. For the vehicle, choose the standard mileage rate — 70 cents per mile for 2025 (IRS Notice 2025-5) — or actual expenses; business miles include driving to pickups, not ordinary commuting or offline personal miles. A contemporaneous mileage log (date, miles, purpose) is the single most important audit record. Net earnings go to Schedule SE: 15.3% self-employment tax on 92.35% of net earnings (§ 1402(a)(12)), with one-half deductible under § 164(f). Example: $40,000 of net profit yields a $36,940 base and about $5,651.82 of SE tax, plus income tax. With no withholding, pay quarterly estimates on Form 1040-ES. California taxes the same income as self-employment (Form 540; estimates on Form 540-ES with the state's 30/40/0/30 installment pattern); note that AB5's ABC test is a labor-law classification rule, separate from the federal tax analysis. *Personal study notes; not tax advice.*

## Español (traducción de estudio, pendiente de revisión nativa)

**Cómo declaran impuestos los conductores de plataformas y repartidores: formularios 1099, registro de millas, Schedule C e impuesto de autónomo.** Quien trabaja para Uber, Lyft, DoorDash o Instacart suele ser contratista independiente a efectos federales: el ingreso es ingreso comercial en el Schedule C (IRC § 61(a)(2)), sin retención del empleador. Las plataformas informan el pago por servicios en el Formulario 1099-NEC y los pagos de pasajeros o clientes en el 1099-K. La OBBBA (P.L. 119-21) cambió dos umbrales: el § 70433 elevó el umbral de información del § 6041 a 2.000 dólares para pagos posteriores al 31 de diciembre de 2025 (con ajuste por inflación posterior), y el umbral del 1099-K (§ 6050W) volvió a ser más de 20.000 dólares y más de 200 transacciones. El umbral solo decide si la plataforma emite el formulario; el ingreso sin formulario también tributa, y los importes del NEC y del K pueden solaparse: concilie con el resumen anual de la plataforma en lugar de sumarlos. En el Schedule C se deducen los gastos ordinarios y necesarios (§ 162). Para el vehículo elija la tarifa estándar por milla —70 centavos por milla en 2025 (IRS Notice 2025-5)— o los gastos reales; cuentan las millas comerciales (incluido ir a recoger al pasajero), no el desplazamiento personal. El registro contemporáneo de millas (fecha, millas, finalidad) es la prueba clave en una auditoría. La ganancia neta va al Schedule SE: impuesto de autónomo del 15,3 % sobre el 92,35 % de la ganancia neta (§ 1402(a)(12)), con la mitad deducible (§ 164(f)). Ejemplo: 40.000 dólares de ganancia neta dan una base de 36.940 y unos 5.651,82 dólares de impuesto de autónomo, más el impuesto sobre la renta. Sin retención, pague estimaciones trimestrales (Formulario 1040-ES). California grava el mismo ingreso como trabajo autónomo (Formulario 540; estimaciones 540-ES con el patrón estatal 30/40/0/30); la prueba ABC de la AB5 es una regla laboral, distinta del análisis fiscal federal. *Notas personales de estudio; no constituye asesoría fiscal.*

## 한국어 (초역, 원어민 감수 대기)

**차량호출·배달 기사의 세금 신고: 1099, 주행거리 기록, Schedule C와 자영업세.** Uber, Lyft, DoorDash, Instacart 기사는 연방세에서 보통 독립계약자로 취급되어, 소득은 Schedule C의 사업소득(IRC § 61(a)(2))으로 신고하고 원천징수는 없습니다. 플랫폼은 서비스 대가를 Form 1099-NEC로, 승객·고객 결제를 1099-K로 보고합니다. OBBBA(P.L. 119-21)로 두 가지 문턱이 바뀌었습니다. § 70433은 § 6041 정보보고 문턱을 2025년 12월 31일 이후 지급분부터 2,000달러로 올렸고( 이후 물가 연동), § 6050W의 1099-K 문턱은 20,000달러 초과·200건 초과로 복원되었습니다. 문턱은 양식 발송 여부만 정할 뿐 과세 여부와 무관하며, NEC와 K 금액은 겹칠 수 있으니 두 양식을 합산하지 말고 플랫폼 연간 요약과 대사하십시오. Schedule C에서는 § 162의 통상·필요 경비를 공제합니다. 차량은 표준 주행거리율(2025년 마일당 70센트, IRS Notice 2025-5) 또는 실제비용 중 하나를 택하고, 영업 주행에는 승객 픽업 이동이 포함되지만 개인 통근은 제외됩니다. 날짜·거리·목적을 적은 동시기 주행기록이 감사의 핵심 증거입니다. 순이익은 Schedule SE로 가서 92.35%(§ 1402(a)(12))에 15.3% 자영업세를 적용하고, 절반은 § 164(f)로 조정 공제됩니다. 예: 순이익 40,000달러이면 과세표준 36,940달러, 자영업세 약 5,651.82달러에 소득세가 더해집니다. 원천징수가 없으므로 Form 1040-ES로 분기 예정납부를 하십시오. 캘리포니아도 자영업소득으로 과세합니다(Form 540, 예정납부 540-ES, 주 분납 비율 30/40/0/30). AB5의 ABC 테스트는 노동법상 분류 기준이라 연방세 분석과는 별개입니다. *개인 학습 노트이며 세무 자문이 아닙니다.*

(2026-11-08 보충) 두 가지 세부 사항. 첫째, 주행거리 기록은 이 업종 심사의 명줄입니다. IRS는 날짜·거리·용도가 적힌 동시기 기록(contemporaneous log)을 요구하고, 플랫폼 앱은 승객 탑승 구간만 세는 경우가 많아 온라인 상태의 빈차 구간은 별도 앱이나 표로 보완해야 하며, 연말 총량이 Schedule C 숫자와 맞아야 합니다. 둘째, 캘리포니아 분기 예납(540-ES)의 분할 비율은 연방과 달리 30%/40%/0%/30%이며, 주행거리와 차량 비용은 대체로 연방 표준 마일리지율을 따릅니다. AB5의 ABC 테스트는 노동법·실업보험 분류 규칙으로 연방 세법 분류와 동일하지 않습니다.

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

**Tài xế công nghệ và giao đồ ăn khai thuế thế nào: 1099, nhật ký quãng đường, Schedule C và thuế tự doanh.** Tài xế của Uber, Lyft, DoorDash hay Instacart thường là nhà thầu độc lập theo luật thuế liên bang: thu nhập là thu nhập kinh doanh khai trên Schedule C (IRC § 61(a)(2)), không có khấu trừ của người sử dụng lao động. Nền tảng báo cáo tiền công dịch vụ bằng Form 1099-NEC và tiền khách trả bằng 1099-K. OBBBA (P.L. 119-21) đã đổi hai ngưỡng: § 70433 nâng ngưỡng báo cáo thông tin của § 6041 lên 2.000 đô la cho các khoản chi trả sau ngày 31/12/2025 (sau đó điều chỉnh theo lạm phát), và ngưỡng 1099-K của § 6050W trở lại mức trên 20.000 đô la và trên 200 giao dịch. Ngưỡng chỉ quyết định nền tảng có phải gửi biểu mẫu hay không — thu nhập không có biểu mẫu vẫn phải khai — và số tiền trên NEC với K có thể trùng nhau, nên hãy đối chiếu với bản tổng kết năm của nền tảng thay vì cộng hai biểu mẫu. Trên Schedule C, khấu trừ chi phí thông thường và cần thiết theo § 162. Với xe, chọn mức quãng đường tiêu chuẩn — 70 cent mỗi dặm năm 2025 (IRS Notice 2025-5) — hoặc chi phí thực tế; quãng đường kinh doanh gồm cả đoạn đi đón khách, không gồm đi lại cá nhân. Nhật ký quãng đường ghi đồng thời (ngày, số dặm, mục đích) là chứng cứ quan trọng nhất khi bị kiểm tra. Lợi nhuận ròng chuyển sang Schedule SE: thuế tự doanh 15,3% trên 92,35% lợi nhuận ròng (§ 1402(a)(12)), một nửa được giảm trừ theo § 164(f). Ví dụ: lợi nhuận ròng 40.000 đô la cho cơ sở 36.940 đô la và khoảng 5.651,82 đô la thuế tự doanh, cộng thêm thuế thu nhập. Không có khấu trừ tại nguồn nên phải nộp tạm tính hằng quý bằng Form 1040-ES. California cũng đánh thuế thu nhập này như thu nhập tự doanh (Form 540; tạm tính 540-ES theo tỷ lệ đợt 30/40/0/30 của bang); lưu ý bài kiểm tra ABC của AB5 là quy tắc phân loại lao động, khác với phân tích thuế liên bang. *Ghi chú học tập cá nhân, không phải tư vấn thuế.*

(Bổ sung 2026-11-08) Hai chi tiết. Thứ nhất, nhật ký quãng đường là điểm sống còn khi bị kiểm toán: IRS yêu cầu ghi chép đồng thời (contemporaneous log) gồm ngày, số dặm và mục đích; ứng dụng nền tảng thường chỉ tính đoạn có khách, nên phải bổ sung đoạn chạy rỗng khi trực tuyến bằng ứng dụng hoặc bảng riêng, và tổng cuối năm phải khớp số trên Schedule C. Thứ hai, lịch tạm nộp theo quý của California (540-ES) chia theo tỷ lệ 30%/40%/0%/30%, khác liên bang, và quy tắc quãng đường, chi phí xe nhìn chung theo tỷ lệ dặm tiêu chuẩn liên bang. Bài kiểm tra ABC của AB5 thuộc luật lao động và bảo hiểm thất nghiệp, không đồng nhất với phân loại thuế liên bang.

## हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

**राइडशेयर और डिलीवरी चालक कर कैसे भरें: 1099, माइलेज लॉग, Schedule C और स्व-रोज़गार कर।** Uber, Lyft, DoorDash या Instacart के चालक संघीय कर में सामान्यतः स्वतंत्र ठेकेदार होते हैं: आय Schedule C पर व्यावसायिक आय (IRC § 61(a)(2)) के रूप में घोषित होती है, नियोक्ता की कोई कटौती नहीं होती। प्लेटफ़ॉर्म सेवा-भुगतान Form 1099-NEC पर और यात्री/ग्राहक भुगतान 1099-K पर रिपोर्ट करते हैं। OBBBA (P.L. 119-21) ने दो सीमाएँ बदल दीं: § 70433 ने § 6041 सूचना-रिपोर्टिंग सीमा 31 दिसंबर 2025 के बाद के भुगतानों के लिए 2,000 डॉलर कर दी (आगे मुद्रास्फीति-समायोजित), और § 6050W की 1099-K सीमा पुनः 20,000 डॉलर से अधिक व 200 से अधिक लेनदेन हो गई। सीमा केवल यह तय करती है कि फ़ॉर्म जारी होगा या नहीं — बिना फ़ॉर्म वाली आय भी करयोग्य है — और NEC व K राशियाँ परस्पर अतिव्यापी हो सकती हैं, इसलिए दोनों फ़ॉर्म जोड़ने के बजाय प्लेटफ़ॉर्म के वार्षिक सारांश से मिलान करें। Schedule C पर § 162 के साधारण व आवश्यक व्यय कटौती योग्य हैं। वाहन के लिए मानक माइलेज दर — 2025 में 70 सेंट प्रति मील (IRS Notice 2025-5) — या वास्तविक व्यय चुनें; व्यावसायिक मीलों में यात्री को लेने जाना शामिल है, निजी आवागमन नहीं। तिथि, मील और उद्देश्य सहित समकालीन माइलेज लॉग ऑडिट का सबसे महत्वपूर्ण अभिलेख है। शुद्ध लाभ Schedule SE पर जाता है: शुद्ध आय के 92.35% (§ 1402(a)(12)) पर 15.3% स्व-रोज़गार कर, जिसका आधा § 164(f) के तहत समायोजन योग्य है। उदाहरण: 40,000 डॉलर शुद्ध लाभ पर आधार 36,940 डॉलर और स्व-रोज़गार कर लगभग 5,651.82 डॉलर, साथ में आयकर। कटौती न होने से Form 1040-ES से त्रैमासिक अनुमानित कर दें। California भी इसी आय पर स्व-रोज़गार के रूप में कर लगाता है (Form 540; अनुमान 540-ES, राज्य की किश्त पद्धति 30/40/0/30)। ध्यान दें, AB5 की ABC परीक्षा श्रम-कानून वर्गीकरण का नियम है, संघीय कर विश्लेषण से अलग। *व्यक्तिगत अध्ययन नोट; कर सलाह नहीं।*

(2026-11-08 पूरक) दो विवरण। पहला, माइलेज रिकॉर्ड इस क्षेत्र के ऑडिट की जीवन-रेखा है: IRS तिथि, दूरी और उद्देश्य सहित समकालीन लॉग (contemporaneous log) माँगता है; प्लेटफ़ॉर्म ऐप सामान्यतः केवल यात्री वाला हिस्सा गिनता है, इसलिए ऑनलाइन खाली दौड़ को अलग ऐप या तालिका से पूरा करें और वर्षांत कुल Schedule C के अंकों से मिलना चाहिए। दूसरा, कैलिफ़ोर्निया के त्रैमासिक अनुमान (540-ES) का विभाजन संघीय से अलग 30%/40%/0%/30% है, और माइलेज व वाहन लागत सामान्यतः संघीय मानक दर का पालन करती है। AB5 का ABC परीक्षण श्रम कानून व बेरोज़गारी बीमा का वर्गीकरण नियम है, संघीय कर वर्गीकरण के समान नहीं।
