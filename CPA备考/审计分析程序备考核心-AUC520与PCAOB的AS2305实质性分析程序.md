# 审计分析程序备考核心：AU-C 520 与 PCAOB AS 2305 实质性分析程序

> 板块：CPA备考（AUD） · 锚点：AICPA AU-C 520《分析程序》（Analytical Procedures）、AU-C 315／330／450／500，PCAOB AS 2305《实质性分析程序》（Substantive Analytical Procedures）、AS 1105《审计证据》、AS 2810《评价审计结果》、AS 2110《识别与评估重大错报风险》；条文以 AICPA 与 PCAOB 现行文本为准，本文不编造段号，拿不准处只引准则名。

## 中文

### 一、先定位：分析程序在审计里干三件活

分析程序（analytical procedures）说白了就是一件事：通过研究数据之间可信的关系（财务数据相互之间、财务数据与非财务数据之间），看数字「合不合常理」。销量涨了三成、库存却没动，毛利率突然比同行高出一截——这类不合常理之处，就是风险藏身的地方。AUD 考试对分析程序的考法高度程式化，先把它的三个使用时点钉死：

1. **计划阶段（风险评估程序）**：必做。AU-C 520 明确要求，审计师应当在了解被审计单位及其环境、评估重大错报风险时运用分析程序；PCAOB 体系下对应 AS 2110 的风险评估要求。
2. **实质性程序阶段**：选做但常考。把分析程序当作实质性程序（substantive analytical procedures），直接拿它当证据去验证某个认定，前提是它对该认定足够有效（下文三、四节）。
3. **审计临近结束的总体复核（overall review）**：必做。AU-C 520 要求在审计临近结束时执行分析程序，帮审计师对财务报表形成总体结论，看报表整体是否与审计师对单位的了解一致；PCAOB 体系下这一步落在 AS 2810 评价审计结果的框架里。

易错的第一刀就在这里：计划与结束复核是「必须做」，实质性用途是「可以选择、但要满足条件」，三者的证据强度完全不同。计划阶段的分析程序只用来指方向，它本身不提供实质性证据；结束复核发现的异常若解释不通，要回到追加程序，不能拿「大方向没问题」盖过去。

### 二、AU-C 520 的主线：四步走完一个实质性分析程序

AU-C 520 对实质性分析程序的要求可以收成四步，考试的选择题与模拟题基本都围着这四步出：

1. **判断适用性（suitability）**：这个分析程序对所给认定是否对路。分析程序最擅长的是量大、可预测的交易流——收入与销量的配比、工资与人头的关系、折旧与资产规模的关系这类关系稳定的领域；对存在重大错报风险、关系本身不可预测或数据颗粒度太粗的认定，它的说服力天然打折。
2. **评价数据可靠性（reliability of data）**：期望值是拿数据算出来的，数据本身不可靠，结论就不可靠。判断可靠性要看数据的来源（独立外部数据优于内部数据）、可比性、性质，以及数据生成过程受控的程度——内部数据若来自受内部控制约束的系统，可靠性才上得去。这一步与 AU-C 500／AS 1105 对审计证据适当性的要求是同一条线。
3. **建立期望值并判断精确度（expectation and precision）**：审计师要自己建立对账面金额的期望值（expectation），并且这个期望值要精确到足以识别可能重大的错报。聚合层级越细（按月、按产品线、按门店拆开），期望值越精确；只看全年总数，很多错报会被正负相抵掩盖掉。
4. **定可接受差异并调查超限差异（acceptable difference and investigation）**：事先定好账面数与期望值之间多大差异可以不查（这个门槛必须小于重要性水平，通常参照执行重要性设定）；实际差异超过门槛，必须调查——先向管理层询问，再用其他审计证据印证解释（corroborate），解释不通或证据不足，就执行其他程序，直至得出结论。

### 三、PCAOB AS 2305：发行人审计的同名准则，多了什么

PCAOB AS 2305 的标题就叫《实质性分析程序》，管的是把分析程序用作实质性测试时的执行标准。它与 AU-C 520 骨架相同，但措辞更偏向「关系的可预测性决定证据力」，备考时记三点：

第一，**关系越可预测，程序越有力**。AS 2305 要求审计师考虑关系的可信赖与可预测程度：建立在稳定经营环境、非操纵性数据之上的关系（例如租金费用与租赁面积），比建立在管理层可自由裁量项目上的关系更能提供证据。

第二，**期望值的精确度与数据的可靠性共同决定差异门槛**。期望值越精确、数据越可靠，能容忍的未调查差异就越小；反过来，粗糙的期望值配上一个很紧的门槛，只会制造假警报或假安心。AS 2305 要求审计师在设定差异调查门槛时考虑重要性与所需的保证程度。

第三，**重大波动必须查到有证据支撑为止**。AS 2305 对与期望值不一致、或缺乏期望关系的重大波动（significant fluctuations）要求调查，并取得印证性证据；管理层的口头解释本身不是证据，必须与其他信息相互印证，无法印证时要执行其他审计程序。这与 AS 1105 的总原则衔接：审计证据要充分且适当，相关性与可靠性缺一不可；也与 AS 2810 衔接：临近结束评价审计结果时，未更正错报与异常关系要一并汇总评价，看它们是否改变对报表的总体结论。

### 四、易错点清单：这几处最容易丢分

一，**分析程序不能单独扛起重大风险的细节测试缺口**。按 AU-C 330 的应对要求，当对某重大错报风险（significant risk）的应对仅由实质性程序构成时，这些实质性程序应当包括细节测试（tests of details）——换句话说，面对重大风险，不能只做实质性分析程序就收工。PCAOB 体系下 AS 2301 对重大风险的应对逻辑相同。

二，**计划阶段做分析程序，不等于拿到了实质性证据**。风险评估阶段的分析程序只支持风险评估结论，不能替代对认定的实质性验证；把两者混写是 AUD 的经典错法。

三，**差异在门槛之内不等于万事大吉**。门槛之内的差异若呈现异常模式（例如每月都恰好贴着门槛、或与已知风险方向一致），仍应保持职业怀疑，必要时追加程序；门槛是调查的起点线，不是免责线。

四，**用管理层解释直接结案**。无论 AU-C 520 还是 AS 2305，询问只是调查的开始，解释必须被印证（corroboration）；未印证的解释在证据链上等于零。

五，**拿被审计单位自己生成、未经测试的数据直接建期望值**。数据若来自内部系统且其相关控制未经考虑，可靠性评价这一步就过不了关，整个实质性分析程序的证据力随之坍塌。

六，**结束复核阶段发现异常却不回头**。AU-C 520 的总体复核发现与审计师了解不一致的异常时，要执行追加程序并评价其对审计结论的影响，不能用「金额不重大」一句话带过而不留痕。

### 五、做题顺序收尾

遇到分析程序的题目，按这个顺序拆：先定它处在哪个阶段（计划／实质性／结束复核），再问四件事——对认定是否适用、数据是否可靠、期望值是否够精确、差异门槛与调查是否到位；发行人场景把准则名换成 AS 2305，并接上 AS 1105 的证据标准与 AS 2810 的结果评价。阶段定对、四问答全，这类题基本不丢分。

*声明：个人学习笔记，不构成税务、审计或法律建议。考试范围以 AICPA 当期蓝图与 AICPA、PCAOB 现行准则文本为准。*

---

## English

**Analytical procedures — exam core: AU-C 520 and PCAOB AS 2305.** Sources: AICPA AU-C 520 (Analytical Procedures), AU-C 315/330/450/500; PCAOB AS 2305 (Substantive Analytical Procedures), AS 1105 (Audit Evidence), AS 2810 (Evaluating Audit Results), AS 2110 (Identifying and Assessing Risks of Material Misstatement). Paragraph numbers are deliberately not cited where not verified; standard names control.

Analytical procedures evaluate financial information by studying plausible relationships among financial and non-financial data. They are used at three points, and the exam tests the distinctions hard: (1) **planning** — required, as risk assessment procedures under AU-C 520 (AS 2110 in PCAOB audits); (2) **substantive procedures** — optional, and effective only when conditions are met; (3) **the overall review near the end of the audit** — required under AU-C 520, and within AS 2810's evaluation framework for issuers. Planning analytics point the direction of the audit but provide no substantive evidence by themselves.

AU-C 520's substantive model has four steps. **Suitability**: the procedure must fit the assertion — analytical procedures work best on large volumes of predictable transactions and lose power where relationships are unstable or data are too aggregated. **Reliability of data**: external and independently generated data outrank internal data; internal data are stronger when produced under effective controls — the same relevance-and-reliability line as AU-C 500 and AS 1105. **Expectation and precision**: the auditor develops an independent expectation precise enough to identify a material misstatement; disaggregation by month, product or location raises precision, while a single annual total lets offsetting errors hide. **Acceptable difference and investigation**: set the threshold for differences that may be accepted without investigation (below materiality, typically referenced to performance materiality); investigate every difference above it — inquire, then *corroborate* management's explanations with other evidence, and perform other procedures when explanations are not corroborated.

PCAOB AS 2305, governing substantive analytical procedures in issuer audits, stresses the same skeleton with an evidence-strength accent: the more predictable the relationship, the more persuasive the procedure; the tolerable unexplained difference shrinks as expectation precision and data reliability rise; and significant fluctuations inconsistent with expectations must be investigated and corroborated — an uncorroborated management explanation is not evidence. AS 1105 supplies the sufficiency-and-appropriateness frame, and AS 2810 requires the results, together with uncorrected misstatements, to be evaluated before the overall conclusion.

Frequent exam traps: substantive analytical procedures alone cannot carry the response to a **significant risk** — under AU-C 330, when the response to a significant risk consists only of substantive procedures, those procedures must include tests of details; a within-threshold difference that shows an abnormal pattern still calls for professional skepticism; expectations built on untested client-generated data fail the reliability step; and inconsistencies found in the final overall review require further procedures, not a wave-through.

*Personal study notes only; not tax, audit or legal advice. Exam scope follows the current AICPA blueprint and the current AICPA and PCAOB standards.*

---

## Español

**Procedimientos analíticos: AU-C 520 y AS 2305 de la PCAOB.** Fuentes: AU-C 520 de la AICPA y normas AU-C 315/330/450/500; AS 2305, AS 1105, AS 2810 y AS 2110 de la PCAOB. No se citan números de párrafo no verificados.

Los procedimientos analíticos estudian relaciones plausibles entre datos financieros y no financieros y se usan en tres momentos: **planificación** (obligatorios, como procedimientos de valoración del riesgo), **procedimientos sustantivos** (opcionales y eficaces solo si cumplen condiciones) y **revisión global al final de la auditoría** (obligatoria; en auditorías PCAOB, dentro de la evaluación de AS 2810). Los analíticos de planificación orientan, pero no aportan por sí solos evidencia sustantiva.

El modelo sustantivo de AU-C 520 tiene cuatro pasos: idoneidad del procedimiento para la afirmación (funciona mejor con transacciones numerosas y predecibles); fiabilidad de los datos (los externos e independientes pesan más; los internos, si provienen de sistemas con controles eficaces); expectativa independiente con precisión suficiente para detectar una incorrección material —desagregar por mes, producto o ubicación aumenta la precisión—; y umbral de diferencia aceptable sin investigación, fijado por debajo de la importancia relativa, investigando toda diferencia superior: preguntar a la dirección no basta, hay que **corroborar** la explicación con otra evidencia.

AS 2305 añade el acento de la fuerza probatoria: cuanto más predecible la relación, más persuasivo el procedimiento; la diferencia tolerable se reduce cuando suben la precisión de la expectativa y la fiabilidad de los datos; y las fluctuaciones significativas contrarias a lo esperado deben investigarse y corroborarse, en conexión con AS 1105 (evidencia suficiente y adecuada) y AS 2810 (evaluación de resultados e incorrecciones no corregidas). Trampa clásica: frente a un **riesgo significativo**, los procedimientos analíticos sustantivos no bastan por sí solos —AU-C 330 exige incluir pruebas de detalle cuando la respuesta es solo sustantiva—; y una diferencia dentro del umbral pero con patrón anómalo sigue exigiendo escepticismo profesional.

*Notas personales de estudio; no es asesoría fiscal, de auditoría ni legal. Traducción de estudio pendiente de revisión nativa.*

---

## 한국어 (초역, 교정 대기)

**분석적 절차 핵심: AU-C 520과 PCAOB AS 2305.** 근거는 AICPA AU-C 520(분석적 절차), AU-C 315/330/450/500, PCAOB AS 2305(실질적 분석 절차), AS 1105(감사증거), AS 2810(감사결과 평가), AS 2110(중요왜곡표시위험 식별·평가)이며, 확인되지 않은 문단 번호는 인용하지 않는다.

분석적 절차는 재무·비재무 데이터 사이의 그럴듯한 관계를 연구하는 절차로, 사용 시점이 셋이다. ① 계획 단계(위험평가절차로서 필수), ② 실질적 절차(선택적이며 요건을 갖출 때만 유효), ③ 감사 종료 무렵의 전반적 검토(필수; PCAOB 감사에서는 AS 2810의 평가 틀 안). 계획 단계의 분석은 방향을 제시할 뿐 그 자체로 실질적 증거가 되지 않는다.

AU-C 520의 실질적 모델은 네 단계이다. 인정에 대한 적합성(예측 가능한 대량 거래에 강함), 데이터의 신뢰성(외부·독립 데이터가 우선하고 내부 데이터는 통제가 유효할 때 강해짐), 중요한 왜곡을 식별할 만큼 정확한 독립적 기대값 형성(월별·제품별·장소별 세분화가 정밀도를 높임), 그리고 조사 없이 받아들일 수 있는 차이의 문턱을 중요성보다 낮게 정하고 문턱을 넘는 차이는 반드시 조사하되 경영진의 설명은 다른 증거로 뒷받침(corroboration)해야 한다는 점이다.

AS 2305는 증거력의 관점을 강조한다. 관계가 예측 가능할수록 설득력이 커지고, 기대값의 정밀도와 데이터 신뢰성이 높을수록 허용 가능한 미조사 차이는 작아지며, 기대와 어긋나는 중대한 변동은 조사와 뒷받침이 필수이다. 고전적 함정으로, 유의적 위험(significant risk)에 대한 대응이 실질적 절차만으로 구성될 때는 AU-C 330상 세부테스트를 포함해야 하므로 분석적 절차만으로는 부족하고, 문턱 안의 차이라도 비정상적 패턴이면 전문가적 의구심을 유지해야 하며, 검증되지 않은 고객 생성 데이터로 만든 기대값은 신뢰성 단계를 통과하지 못한다.

*개인 학습 노트이며 세무·감사·법률 자문이 아닙니다. 초역으로 교정 대기 중입니다.*

---

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

**Thủ tục phân tích — trọng tâm ôn thi: AU-C 520 và PCAOB AS 2305.** Căn cứ: AU-C 520 của AICPA cùng AU-C 315/330/450/500; AS 2305, AS 1105, AS 2810 và AS 2110 của PCAOB. Không trích số đoạn chưa được kiểm chứng.

Thủ tục phân tích nghiên cứu các mối quan hệ hợp lý giữa dữ liệu tài chính và phi tài chính, được dùng ở ba thời điểm: **lập kế hoạch** (bắt buộc, thuộc thủ tục đánh giá rủi ro), **thủ tục cơ bản** (tùy chọn, chỉ hiệu quả khi đủ điều kiện) và **soát xét tổng thể cuối cuộc kiểm toán** (bắt buộc; với kiểm toán PCAOB nằm trong khung đánh giá của AS 2810). Phân tích ở giai đoạn lập kế hoạch chỉ định hướng, tự nó không tạo bằng chứng cơ bản.

Mô hình cơ bản của AU-C 520 gồm bốn bước: tính phù hợp với cơ sở dẫn liệu (mạnh nhất với khối lượng giao dịch lớn, dễ dự đoán); độ tin cậy của dữ liệu (dữ liệu bên ngoài, độc lập có trọng lượng cao hơn; dữ liệu nội bộ mạnh hơn khi sinh ra dưới kiểm soát hiệu quả); xây dựng kỳ vọng độc lập đủ chính xác để phát hiện sai sót trọng yếu — chia nhỏ theo tháng, sản phẩm hay địa điểm sẽ tăng độ chính xác; và ngưỡng chênh lệch có thể chấp nhận mà không cần điều tra, đặt dưới mức trọng yếu, mọi chênh lệch vượt ngưỡng phải được điều tra và giải thích của ban quản lý phải được **chứng thực** bằng bằng chứng khác.

AS 2305 nhấn mạnh sức thuyết phục: quan hệ càng dễ dự đoán, thủ tục càng có giá trị; chênh lệch bỏ qua được càng nhỏ khi độ chính xác của kỳ vọng và độ tin cậy dữ liệu càng cao; biến động trọng yếu trái kỳ vọng phải được điều tra và chứng thực, gắn với AS 1105 (bằng chứng đầy đủ, thích hợp) và AS 2810 (đánh giá kết quả). Bẫy thường gặp: trước **rủi ro đáng kể**, thủ tục phân tích cơ bản không thể đứng một mình — theo AU-C 330, khi ứng phó chỉ gồm thủ tục cơ bản thì phải có kiểm tra chi tiết; chênh lệch trong ngưỡng nhưng có mẫu bất thường vẫn cần thái độ hoài nghi nghề nghiệp.

*Ghi chú học tập cá nhân, không phải tư vấn thuế, kiểm toán hay pháp lý. Bản dịch sơ bộ chờ hiệu đính.*

---

## हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

**विश्लेषणात्मक प्रक्रियाएँ — परीक्षा सार: AU-C 520 और PCAOB AS 2305।** आधार: AICPA AU-C 520 तथा AU-C 315/330/450/500; PCAOB AS 2305, AS 1105, AS 2810 और AS 2110। असत्यापित अनुच्छेद-संख्याएँ नहीं दी गई हैं।

विश्लेषणात्मक प्रक्रियाएँ वित्तीय और गैर-वित्तीय आँकड़ों के बीच विश्वसनीय संबंधों का अध्ययन करती हैं और तीन चरणों में प्रयुक्त होती हैं: **योजना** (जोखिम-मूल्यांकन प्रक्रिया के रूप में अनिवार्य), **सारभूत प्रक्रियाएँ** (वैकल्पिक, शर्तें पूरी होने पर ही प्रभावी) और **ऑडिट के अंत में समग्र समीक्षा** (अनिवार्य; PCAOB ऑडिट में AS 2810 के मूल्यांकन ढाँचे के भीतर)। योजना-चरण का विश्लेषण दिशा देता है, स्वयं सारभूत साक्ष्य नहीं बनता।

AU-C 520 का सारभूत मॉडल चार चरणों का है: दावे के प्रति उपयुक्तता (बड़ी मात्रा के पूर्वानुमेय लेन-देनों में सबसे मज़बूत); आँकड़ों की विश्वसनीयता (बाहरी व स्वतंत्र आँकड़े भारी; आंतरिक आँकड़े प्रभावी नियंत्रणों वाली प्रणाली से आएँ तो मज़बूत); इतनी सटीक स्वतंत्र अपेक्षा बनाना कि महत्वपूर्ण ग़लतबयानी पकड़ी जा सके — माह, उत्पाद या स्थान के अनुसार विघटन सटीकता बढ़ाता है; और बिना जाँच स्वीकार्य अंतर की सीमा महत्वपूर्णता से नीचे तय करना, सीमा से ऊपर के हर अंतर की जाँच करना तथा प्रबंधन के स्पष्टीकरण को अन्य साक्ष्य से **पुष्ट** करना।

AS 2305 साक्ष्य-शक्ति पर ज़ोर देता है: संबंध जितना पूर्वानुमेय, प्रक्रिया उतनी विश्वसनीय; अपेक्षा की सटीकता और आँकड़ों की विश्वसनीयता बढ़ने पर सहनीय अंतर घटता है; अपेक्षा से भिन्न महत्वपूर्ण उतार-चढ़ाव की जाँच और पुष्टि अनिवार्य है — यह AS 1105 (पर्याप्त व उपयुक्त साक्ष्य) और AS 2810 (परिणामों का मूल्यांकन) से जुड़ता है। आम परीक्षा-जाल: **महत्वपूर्ण जोखिम** के सामने केवल विश्लेषणात्मक प्रक्रियाएँ पर्याप्त नहीं — AU-C 330 के अनुसार जब प्रतिक्रिया केवल सारभूत प्रक्रियाओं की हो तो उनमें विवरण परीक्षण शामिल होना चाहिए; सीमा के भीतर का अंतर भी असामान्य पैटर्न दिखाए तो व्यावसायिक संदेह बनाए रखें।

*व्यक्तिगत अध्ययन नोट; कर, ऑडिट या कानूनी सलाह नहीं। प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित।*
