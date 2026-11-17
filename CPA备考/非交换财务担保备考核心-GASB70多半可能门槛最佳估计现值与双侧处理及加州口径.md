# 非交换财务担保备考核心：GASB 70 多半可能门槛、最佳估计现值与担保方被担保方双侧处理及加州口径

导语：政府替别人的债背书、又没收对等价值，这笔或有负担什么时候从附注走进资产负债表？GASB 第 70 号公告给的答案是一条比「很可能」更低的门槛：定性因素与历史数据表明担保人多半可能（more likely than not，概率大于 50%）要替被担保方付款时，就确认负债，按未来流出的最佳估计折现计量；没到门槛也要披露。被担保方一侧则相反：债还是自己的债，直到被法定免除才出表。本篇补 GASB 编号系列中第 70 号这一格，与仓内导管债务篇（GASB 91）、债务披露篇（GASB 88）以指针分工。

选题说明：经 ls 文件名＋grep 正文双路实查，「GASB 70」「非交换财务担保」在四板块文件名与正文均零命中、无本体专篇；GASB 系列已覆盖 33、49、54（散见）、63、65、68、72、75、77、81、83、84、86、87、88、89、91、93、94、96、99、100、101、102、103、104 等号，第 70 号的确认门槛与双侧处理整格空缺，本篇补之。

## 中文主文

### 一、定位与范围：先认「非交换」三个字

GASB 第 70 号公告《非交换财务担保的会计与财务报告》（Accounting and Financial Reporting for Nonexchange Financial Guarantees），2013 年 4 月发布，对 2013 年 6 月 15 日之后开始的报告期间生效，鼓励提前适用。所谓非交换财务担保，是政府在没有收到大致等值回报的情况下，为另一方（法律上独立的组织、政府或个人，含组成部分单位）的债务向债权人作出的担保：被担保方不付钱，担保人到期可能要替它付钱。两个范围排除要记牢：第一，交换性担保（收了担保费、按商业条件作保）不在本号内，按一般或有事项口径处理；第二，导管债务（conduit debt）相关的担保走 GASB 第 91 号的对应段落、特殊评估债务走 GASB 第 6 号口径，不与本号混用。考试第一步永远是先定性：是不是非交换、是不是替法律上独立的他方背书。

### 二、担保方确认门：多半可能，不是「很可能」

担保人一侧的确认规则是本号的核心考点。当定性因素与历史数据合起来表明，担保人多半可能（more likely than not，即概率大于 50%）将被要求就其作出的非交换财务担保付款时，担保人应在权责发生制报表中确认一项负债与费用（政府基金等修正权责发生制报表中，按到期应付、通常要用可动用当期财务资源清偿的金额确认负债与支出）。准则给的指示因素包括：被担保方已进入破产或接管程序；被担保方陷入财务困境（如违反债务契约、重大收入来源丧失、被宣布紧急状态之类）；担保人过去曾被要求就同类担保实际付款。注意门槛的刻度：FASB 体系或有事项常用的 probable（很可能，实务上常被理解为约 75% 以上）比这里高一截——GASB 70 只要越过 50% 这条线就确认，这是本号最爱考的一刀。反过来，没越过门槛不等于什么都不做：披露义务独立存在（见第四节）。

### 三、计量：最佳估计的折现现值，无最佳估计取区间最低

确认金额不是被担保债务的全额，而是担保人预计未来现金流出的最佳估计的折现现值（discounted present value of the best estimate of future outflows）。若估计只能给出一个区间、区间内没有哪一点比其他点更像最佳估计，则取区间最低金额作为计量基础（再按适用口径折现）。后续期间：担保人实际付款时冲减已确认负债；情况变化时重估负债金额。算例（教学设定数字，本地整数与 Decimal 两路复算一致）：某州政府为一家独立机构 10,000,000 美元债券作非交换担保，该机构违反债务契约且主要收入来源丧失，评估付款概率为 60%，已越过 50% 门槛，须确认负债。最佳估计为未来三年每年末各付 500,000 美元，折现率 4%：第一年 500,000 ÷ 1.04 ＝ 480,769.23 美元；第二年 500,000 ÷ 1.04² ＝ 462,278.11 美元；第三年 500,000 ÷ 1.04³ ＝ 444,498.18 美元；现值合计 480,769.23 ＋ 462,278.11 ＋ 444,498.18 ＝ 1,387,545.52 美元，即应确认的负债——注意是约 139 万的预计流出现值，不是 1,000 万的被担保本金全额。对照情形：若同一担保评估付款概率只有 40%，不确认负债，只走第四节披露。区间情形：若流出估计只能定在 800,000 至 1,200,000 美元之间且无最佳估计，计量基础取最低额 800,000 美元。

### 四、披露：没确认也要说清楚

无论是否确认负债，作出非交换财务担保的政府都要披露：担保的一般说明（为谁的什么债务作保）、被担保债务的总金额、担保期限、已确认负债的金额（如有）、截至报告日已累计支付的金额、以及已收回或预计可收回的金额等。被担保方一侧同样有披露：其债务由谁担保、担保金额、担保人已代付的金额等。考试陷阱正在这里：把「未达确认门槛」答成「无需任何报告」是最常见的丢分点——确认与披露是两条独立的线。

### 五、被担保方：债不因有人背书而出表

被担保方（发行被担保债务的政府）的处理与担保方正好成对：拿到担保不改变债务归属，被担保方继续确认自己的债务负债，直到被法定免除（legally released）为止。若担保人替它付了款、而它依法或依约须偿还担保人，原负债转为对担保人的负债（重分类，不出表）；若它被法定免除且无须偿还，则在免除时按负债减少额确认收入。换句话说，担保在被担保方报表上从来不是「债务消失键」，最多是债权人换人或最终免除时的一笔收入。

### 六、加州口径

加州各级政府同按 GASB 准则编报，州与地方政府对外作出的非交换担保（含为组成部分单位与独立机构背书）适用第 70 号的确认与披露框架，州主计长与地方审计口径以当期 GASB 文本为准（证据等级 B；GASB 公告原文与生效日为 A 级）。

### 七、备考要点

- 门槛刻度：more likely than not ＝ 大于 50%，低于 probable 一档；触发靠定性因素加历史数据，不靠管理层一句估计。
- 计量对象：预计流出的最佳估计现值，不是被担保本金全额；无最佳估计取区间最低额。
- 双侧不对称：担保方越线即确认负债，被担保方直到法定免除才出表；担保人代付且被担保方须偿还的，只是负债换债权人。
- 披露独立：未达门槛不确认，也要披露担保说明、总金额与期限。
- 范围分界：交换性担保不入本号；导管债务担保看 GASB 91、特殊评估债务看 GASB 6。

来源：GASB Statement No. 70, Accounting and Financial Reporting for Nonexchange Financial Guarantees（2013 年 4 月发布，2013 年 6 月 15 日后开始的期间生效；确认门槛、指示因素、最佳估计现值与区间最低额计量、担保方与被担保方披露、被担保方至法定免除前持续确认负债等口径）；Journal of Accountancy 2013 年 4 月报道与路易斯安那州 OSRAP 实施备忘 14-23、得州主计长年报指引（非交换担保节）复核生效日与修正权责发生制口径。算例本地整数与 Decimal 两路复算一致：500,000 ÷ 1.04 ＝ 480,769.23、500,000 ÷ 1.04² ＝ 462,278.11、500,000 ÷ 1.04³ ＝ 444,498.18、三者合计 1,387,545.52。

声明：个人学习笔记，不构成税务或会计建议。

---

## English

GASB Statement No. 70, Accounting and Financial Reporting for Nonexchange Financial Guarantees (issued April 2013; effective for reporting periods beginning after June 15, 2013), covers guarantees a government extends without receiving approximately equal value in exchange, backing the obligations of a legally separate organization, government, or individual (including component units). Exchange guarantees are outside its scope, conduit-debt guarantees follow GASB Statement No. 91, and special assessment debt follows GASB Statement No. 6. On the guarantor side, the recognition trigger is deliberately low: when qualitative factors and historical data indicate it is more likely than not — a likelihood greater than 50 percent — that the guarantor will be required to make a payment, the guarantor recognizes a liability and expense in accrual-basis statements (in governmental funds, to the extent the amount is due and payable with expendable available financial resources). Indicators include the obligated government's bankruptcy or receivership, financial difficulty such as a debt-covenant breach or loss of a major revenue source, and the guarantor having previously been required to pay. Note the calibration: this more-likely-than-not line sits below the "probable" threshold familiar from FASB contingency practice.

Measurement is not the face amount of the guaranteed debt. The liability is the discounted present value of the best estimate of future outflows; if the estimate is a range with no best point, the minimum of the range is used. Teaching example (recomputed with integers and Decimal, two ways): a state guarantees $10,000,000 of bonds of a separate agency; after a covenant breach and loss of a major revenue source, payment is assessed at 60 percent likely, so recognition is required. The best estimate is $500,000 at each of the next three year-ends, discounted at 4 percent: $500,000 ÷ 1.04 = $480,769.23; $500,000 ÷ 1.04² = $462,278.11; $500,000 ÷ 1.04³ = $444,498.18; present value $1,387,545.52 — not the $10,000,000 principal. At a 40 percent likelihood, nothing is recognized, but disclosure still applies: a description of the guarantee, the total amount guaranteed, its length, any liability recognized, cumulative payments made, and recoveries. On the obligated government's side, the debt stays on its own books until it is legally released; if the guarantor pays and the obligated government must repay the guarantor, the liability is reclassified as owed to the guarantor, and only a legal release without repayment produces revenue. California governments report under GASB, so Statement No. 70 frames state and local nonexchange guarantees there as well (evidence grade B; the Statement itself is grade A). Personal study notes; not tax or accounting advice.

## Español (初译待校)

La Declaración n.º 70 de la GASB, Contabilidad e información financiera para garantías financieras no cambiarias (emitida en abril de 2013; vigente para períodos que comiencen después del 15 de junio de 2013), cubre las garantías que un gobierno otorga sin recibir un valor aproximadamente equivalente, respaldando obligaciones de una organización, gobierno o persona legalmente separada (incluidas las unidades componentes). Quedan fuera las garantías cambiarias; las garantías de deuda conducto siguen la Declaración n.º 91 y la deuda de evaluación especial, la n.º 6. Para el garante, el disparador de reconocimiento es deliberadamente bajo: cuando los factores cualitativos y los datos históricos indican que es más probable que no (more likely than not, probabilidad mayor al 50 por ciento) que deba pagar, reconoce un pasivo y un gasto en estados de devengo pleno (en fondos gubernamentales, hasta el monto exigible con recursos financieros disponibles). Son indicios la quiebra o intervención del obligado, su dificultad financiera —incumplimiento de cláusulas de deuda o pérdida de una fuente principal de ingresos— y que el garante ya haya tenido que pagar antes. Esta línea está por debajo del umbral «probable» de la práctica FASB.

La medición no es el nominal garantizado: es el valor presente descontado de la mejor estimación de salidas futuras; si la estimación es un rango sin mejor punto, se usa el mínimo del rango. Ejemplo didáctico (recalculado con enteros y Decimal): un estado garantiza 10.000.000 de dólares de bonos de una agencia separada; tras el incumplimiento y la pérdida de ingresos, la probabilidad de pago se estima en 60 por ciento, así que hay reconocimiento. La mejor estimación es 500.000 dólares al cierre de cada uno de los próximos tres años, descontados al 4 por ciento: 480.769,23, 462.278,11 y 444.498,18; valor presente total 1.387.545,52 dólares, no los 10.000.000 del principal. Con 40 por ciento de probabilidad no se reconoce nada, pero sí se revela: descripción de la garantía, monto total garantizado, plazo, pasivo reconocido, pagos acumulados y recuperaciones. Para el gobierno obligado, la deuda permanece en sus libros hasta ser liberado legalmente; si el garante paga y el obligado debe reembolsarle, el pasivo se reclasifica como deuda con el garante, y solo una liberación legal sin reembolso genera ingreso. Los gobiernos de California reportan bajo GASB, así que la Declaración n.º 70 también enmarca allí estas garantías (evidencia B; la Declaración, A). Notas personales de estudio; no es asesoría fiscal ni contable. (初译待校)

## 한국어 (初译待校)

GASB 제70호 «비교환 금융보증의 회계처리와 재무보고»(2013년 4월 발표, 2013년 6월 15일 이후 개시하는 보고기간부터 적용)는 정부가 대략 동등한 대가를 받지 않고 법적으로 분리된 조직·정부·개인(구성단위 포함)의 채무를 보증하는 경우를 다룹니다. 교환성 보증은 범위 밖이고, 도관채무 보증은 제91호, 특별부과채무는 제6호를 따릅니다. 보증인 측 인식 문턱은 의도적으로 낮습니다. 정성적 요인과 과거 데이터가 보증인이 지급을 요구받을 가능성이 반반보다 크다(more likely than not, 50% 초과)고 시사하면, 보증인은 발생주의 재무제표에 부채와 비용을 인식합니다(정부기금에서는 가용 재무자원으로 지급기일에 갚을 금액 범위). 지표로는 채무자 정부의 파산·법정관리, 채무약정 위반이나 주요 수입원 상실 같은 재정 곤란, 과거에 보증인이 실제로 지급한 경험이 있습니다. 이 문턱은 FASB의 우발부채 실무에서 쓰는 probable보다 한 단계 낮습니다.

측정은 보증 원금 전액이 아닙니다. 부채는 미래 유출의 최상의 추정치의 할인 현재가치이며, 추정치가 범위이고 최상의 지점이 없으면 범위의 최저액을 씁니다. 교육용 예시(정수와 Decimal 두 방식으로 재계산): 한 주가 별도 기관의 채권 10,000,000달러를 보증했고, 약정 위반과 주요 수입원 상실 후 지급 확률이 60%로 평가되어 인식이 필요합니다. 최상의 추정치인 향후 3년간 매년 말 500,000달러를 4%로 할인하면 480,769.23달러, 462,278.11달러, 444,498.18달러, 현재가치 합계 1,387,545.52달러입니다. 원금 1,000만 달러가 아닙니다. 지급 확률이 40%이면 인식은 없지만 공시는 남습니다. 보증 설명, 총 보증액, 기간, 인식한 부채, 누적 지급액과 회수액이 공시 대상입니다. 채무자 정부 측은 법적 면책(legally released) 전까지 자기 부채를 그대로 보고합니다. 보증인이 대신 갚고 채무자가 보증인에게 상환해야 하면 부채는 보증인에 대한 부채로 재분류될 뿐이고, 상환 없는 법적 면책 때만 수익을 인식합니다. 캘리포니아 정부도 GASB로 보고하므로 제70호가 같은 틀로 적용됩니다(증거 등급 B, 본문 A). 개인 학습 노트이며 세무·회계 자문이 아닙니다. (초역, 원어민 감수 대기 · 初译待校)

## Tiếng Việt (初译待校)

Chuẩn mực GASB số 70, Kế toán và báo cáo tài chính cho các bảo lãnh tài chính phi trao đổi (ban hành tháng 4 năm 2013; hiệu lực cho các kỳ báo cáo bắt đầu sau ngày 15 tháng 6 năm 2013), điều chỉnh các bảo lãnh mà chính quyền cấp ra mà không nhận lại giá trị xấp xỉ tương đương, đứng sau nghĩa vụ của một tổ chức, chính quyền hoặc cá nhân tách biệt về pháp lý (kể cả đơn vị cấu thành). Bảo lãnh có trao đổi nằm ngoài phạm vi; bảo lãnh nợ ống dẫn (conduit debt) theo Chuẩn mực số 91, nợ đánh giá đặc biệt theo số 6. Phía bên bảo lãnh, ngưỡng ghi nhận cố ý đặt thấp: khi các yếu tố định tính và dữ liệu lịch sử cho thấy khả năng bên bảo lãnh phải trả tiền là lớn hơn khả năng không trả (more likely than not, trên 50 phần trăm), bên bảo lãnh ghi nhận nợ phải trả và chi phí trong báo cáo cơ sở dồn tích (ở quỹ chính phủ, ghi trong phạm vi khoản đến hạn phải trả bằng nguồn lực tài chính khả dụng). Các dấu hiệu gồm: bên có nghĩa vụ phá sản hoặc bị tiếp quản, khó khăn tài chính như vi phạm cam kết nợ hay mất nguồn thu chính, và bên bảo lãnh từng phải trả tiền trước đây. Ngưỡng này thấp hơn mức «probable» quen thuộc trong thực hành FASB.

Đo lường không phải là mệnh giá khoản nợ được bảo lãnh, mà là giá trị hiện tại đã chiết khấu của ước tính tốt nhất về dòng chi tương lai; nếu ước tính là một khoảng mà không có điểm tốt nhất, lấy mức tối thiểu của khoảng. Ví dụ giảng dạy (đã tính lại bằng số nguyên và Decimal hai cách): một bang bảo lãnh 10.000.000 đô la trái phiếu của một cơ quan tách biệt; sau vi phạm cam kết và mất nguồn thu chính, xác suất phải trả được đánh giá 60 phần trăm nên phải ghi nhận. Ước tính tốt nhất là 500.000 đô la vào cuối mỗi năm trong ba năm tới, chiết khấu 4 phần trăm: 480.769,23; 462.278,11; 444.498,18 đô la; tổng giá trị hiện tại 1.387.545,52 đô la — không phải 10.000.000 đô la gốc. Nếu xác suất chỉ 40 phần trăm thì không ghi nhận, nhưng vẫn phải thuyết minh: mô tả bảo lãnh, tổng số tiền bảo lãnh, thời hạn, nợ đã ghi nhận, số tiền đã trả lũy kế và khoản thu hồi. Phía bên có nghĩa vụ, khoản nợ vẫn nằm trên sổ của chính mình cho đến khi được giải phóng hợp pháp (legally released); nếu bên bảo lãnh trả thay và bên có nghĩa vụ phải hoàn trả, khoản nợ được phân loại lại thành nợ đối với bên bảo lãnh, và chỉ khi được giải phóng hợp pháp mà không phải hoàn trả mới ghi nhận doanh thu. Các chính quyền California báo cáo theo GASB nên Chuẩn mực số 70 cũng áp dụng theo cùng khung (mức chứng cứ B; bản thân chuẩn mực là A). Ghi chú học tập cá nhân; không phải tư vấn thuế hay kế toán. (Bản dịch sơ bộ, chờ hiệu đính · 初译待校)

## हिन्दी (初译待校)

GASB कथन सं. 70, अविनिमय वित्तीय गारंटियों के लिए लेखांकन और वित्तीय रिपोर्टिंग (अप्रैल 2013 में जारी; 15 जून 2013 के बाद शुरू होने वाली रिपोर्टिंग अवधियों के लिए प्रभावी), उन गारंटियों को नियंत्रित करता है जो कोई सरकार लगभग समान मूल्य प्राप्त किए बिना, किसी विधिक रूप से पृथक संगठन, सरकार या व्यक्ति (घटक इकाइयों सहित) के दायित्वों के पीछे देती है। विनिमय गारंटियाँ इसके दायरे से बाहर हैं; conduit debt की गारंटियाँ कथन सं. 91 और विशेष मूल्यांकन ऋण कथन सं. 6 का पालन करते हैं। गारंटर पक्ष पर मान्यता की सीमा जानबूझकर नीची रखी गई है: जब गुणात्मक कारक और ऐतिहासिक आँकड़े संकेत दें कि गारंटर को भुगतान करना पड़ने की संभावना न करने से अधिक है (more likely than not, 50 प्रतिशत से अधिक), तो गारंटर accrual-आधारित विवरणों में देयता और व्यय मान्य करता है (सरकारी निधियों में, उपलब्ध वित्तीय संसाधनों से देय राशि की सीमा तक)। संकेतकों में दायित्वधारी सरकार का दिवालिया या receivership में जाना, ऋण-प्रतिबंध उल्लंघन या प्रमुख राजस्व स्रोत की हानि जैसी वित्तीय कठिनाई, और गारंटर का पहले भुगतान करने को बाध्य होना शामिल हैं। यह रेखा FASB आकस्मिकता अभ्यास के «probable» स्तर से नीचे है।

मापन गारंटीकृत मूलधन का अंकित मूल्य नहीं है। देयता भविष्य के बहिर्वाह के सर्वोत्तम अनुमान का बट्टा-युक्त वर्तमान मूल्य है; यदि अनुमान एक सीमा है और कोई सर्वोत्तम बिंदु नहीं है, तो सीमा का न्यूनतम लिया जाता है। शिक्षण उदाहरण (पूर्णांक और Decimal दोनों विधियों से पुनर्गणित): एक राज्य एक पृथक एजेंसी के 10,000,000 डॉलर के बॉन्ड की गारंटी देता है; प्रतिबंध उल्लंघन और प्रमुख राजस्व हानि के बाद भुगतान की संभावना 60 प्रतिशत आँकी गई, इसलिए मान्यता आवश्यक है। सर्वोत्तम अनुमान अगले तीन वर्षों में प्रत्येक वर्ष-अंत पर 500,000 डॉलर है, 4 प्रतिशत पर बट्टा करने पर 480,769.23, 462,278.11 और 444,498.18 डॉलर; वर्तमान मूल्य कुल 1,387,545.52 डॉलर — 10,000,000 डॉलर मूलधन नहीं। यदि संभावना 40 प्रतिशत हो तो मान्यता नहीं, किंतु प्रकटीकरण फिर भी लागू होता है: गारंटी का विवरण, कुल गारंटीकृत राशि, अवधि, मान्य देयता, संचयी भुगतान और वसूलियाँ। दायित्वधारी सरकार की ओर, ऋण तब तक उसकी अपनी पुस्तकों में रहता है जब तक वह विधिक रूप से मुक्त (legally released) न हो जाए; यदि गारंटर भुगतान करे और दायित्वधारी को गारंटर को चुकाना पड़े, तो देयता गारंटर के प्रति देयता के रूप में पुनर्वर्गीकृत होती है, और बिना चुकाए विधिक मुक्ति पर ही राजस्व मान्य होता है। कैलिफ़ोर्निया की सरकारें GASB के तहत रिपोर्ट करती हैं, इसलिए कथन सं. 70 वहाँ भी उसी ढाँचे में लागू होता है (साक्ष्य ग्रेड B; कथन स्वयं A)। व्यक्तिगत अध्ययन नोट; कर या लेखा सलाह नहीं। (प्रारंभिक अनुवाद, समीक्षा लंबित · 初译待校)

---

## 补译增量（2026-11-17 04:55 轮）

本节为韩／越／印三语补齐中文主文已有、原译文未展开的两项细节：其一，区间估计的算例数字——流出估计只能定在 800,000 至 1,200,000 美元之间且无最佳估计时，计量基础取最低额 800,000 美元；其二，后续计量——担保人实际付款时冲减已确认负债，情况变化时重估负债金额。纯增量，只加不删。

### 한국어 (初译待校)

보충 1 — 구간 추정의 수치 예시: 유출 추정이 800,000달러에서 1,200,000달러 사이의 구간으로만 정해지고 구간 안에 최상의 추정치라 할 지점이 없으면, 측정 기초는 구간의 최저액인 800,000달러로 합니다. 보충 2 — 후속 측정: 보증인이 실제로 지급하면 이미 인식한 부채를 그만큼 줄이고(차감), 상황이 바뀌면 부채 금액을 다시 추정해 조정합니다. 인식은 일회성 판단이 아니라 이후 기간마다 따라가며 손보는 금액입니다. (초역, 원어민 감수 대기 · 初译待校)

### Tiếng Việt (初译待校)

Bổ sung 1 — Con số của ví dụ ước tính theo khoảng: nếu ước tính dòng chi chỉ xác định được trong khoảng 800.000 đến 1.200.000 đô la và không có điểm nào là ước tính tốt nhất, cơ sở đo lường lấy mức tối thiểu của khoảng là 800.000 đô la. Bổ sung 2 — Đo lường kỳ sau: khi bên bảo lãnh thực trả tiền, khoản nợ đã ghi nhận được giảm trừ tương ứng; khi hoàn cảnh thay đổi, số nợ được ước tính lại. Việc ghi nhận không phải là phán đoán một lần rồi bỏ đó, mà là con số phải theo dõi và chỉnh lại ở các kỳ sau. (Bản dịch sơ bộ, chờ hiệu đính · 初译待校)

### हिन्दी (初译待校)

पूरक 1 — सीमा-आधारित अनुमान के आँकड़े: यदि बहिर्वाह का अनुमान केवल 800,000 से 1,200,000 डॉलर की सीमा में ही तय हो सके और कोई सर्वोत्तम बिंदु न हो, तो मापन का आधार सीमा का न्यूनतम, अर्थात 800,000 डॉलर लिया जाता है। पूरक 2 — बाद की अवधि का मापन: जब गारंटर वास्तव में भुगतान करे तो मान्य देयता उतनी घटाई जाती है, और परिस्थितियाँ बदलने पर देयता की राशि का पुनः अनुमान लगाया जाता है। मान्यता एक बार का निर्णय नहीं है; यह वह राशि है जिसकी बाद की अवधियों में निगरानी और समायोजन होता रहता है। (प्रारंभिक अनुवाद, समीक्षा लंबित · 初译待校)
