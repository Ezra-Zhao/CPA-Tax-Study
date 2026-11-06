# 审计数据分析与可视化备考核心：AU-C 与 CAATs 及职业判断

> 个人学习笔记，不构成税务/财务建议。准则以 AICPA 审计准则（AU-C）原文为准，考试口径以 AICPA 当期 CPA Exam Blueprint 为准。

## 中文主文

### 一、先定位：ADA 是一种技术，不是一部新准则

审计数据分析（audit data analytics，ADA）先要和「多了一部准则」划清界限。AICPA《Guide to Audit Data Analytics》给 ADA 的定义是：通过分析、建模与可视化，在与审计对象有关的数据中发现模式、识别异常并提取其他有用信息的科学与艺术，目的是规划或执行审计。这本指南在 AU-C 200 的框架里属于「其他审计出版物」（other auditing publication），本身没有权威地位；GAAS 至今并不要求审计师必须使用 ADA，也不为 ADA 单独立节。考试的问法因此很固定：ADA 做得再漂亮，也要回到它服务的那个程序所属的准则去评价——用在风险评估就看 AU-C 315，用作实质性证据就看 AU-C 500 与 520，涉及抽样推断就看 AU-C 530。把「用了 ADA」本身当成充分证据，是本题第一大坑。

工具一侧的旧词是 CAATs（computer-assisted audit techniques，计算机辅助审计技术）：用软件对电子数据做全量筛选、重算、匹配、缺号检查、分层与可视化。ADA 可以理解为 CAATs 在数据规模、建模与图形表达上的扩展，而不是另起炉灶的保证来源。可视化（散点、热力、趋势、分布图）的作用是帮审计师看见异常的形状，它本身不产生证据力；图上一个离群点只是一个待查事项（notable item），不是错报结论。

### 二、五步流程：指南给风险评估 ADA 的骨架

指南摘录给出的基本流程有五步，备考按这五步记最稳：

1. **规划 ADA**：定财务报表项目、认定与总体，定 ADA 的总体目的（风险评估、控制测试、实质性分析程序、细节测试还是总体结论程序）与具体目标，初步考虑数据的相关性、可得性与可靠性，并选定技术、工具与图表形式。
2. **获取并准备数据**：取得数据、清洗与格式化，使其能被分析工具处理。
3. **考虑所用数据的相关性与可靠性**：这是 AU-C 500 的要求落到数据上的版本（见第五节），不过关的数据不能往下跑。
4. **执行 ADA**：设计或执行需要修正就修正后重跑；识别出值得进一步考虑的事项，就按 ADA 的目的与目标对这些事项计划并执行追加程序。
5. **评价结果并下结论**：目的与具体目标没有达到，就换其他程序补，不许拿「跑过了」充数。

底稿要求随每一步走：风险评估 ADA 的记录接 AU-C 315 第 .33 段一带的风险评估记录要求，指南第 1.48–1.56 段另有 ADA 记录事项的讨论。

### 三、在五部 AU-C 里的定位：一张表钉死

| 用途 | 主准则 | ADA 在里面的位置 | 评价标准 |
| --- | --- | --- | --- |
| 风险评估 | AU-C 315 | 了解被审计单位及其环境、识别重大错报风险的程序之一；全量扫描月度分录、收入分布与异常波动，帮审计师把风险定位到账户、认定与期间 | 只定方向与风险高低，本身不提供关于认定不存在重大错报的实质性证据 |
| 应对已评估风险 | AU-C 330 | 决定进一步审计程序的性质、时间与范围：ADA 结果把细节测试与控制测试的火力引向高风险子总体；重大风险的应对必须包含细节测试，不能只靠实质性分析程序（含 ADA 式分析）过关 | 程序组合须与认定层风险相称；只做分析不做细节测试，应对重大风险不合格 |
| 审计证据总框架 | AU-C 500 | ADA 产出要成为证据，先过充分性与适当性（相关性＋可靠性）；使用被审计单位产生的信息（IPE）前，须验证其准确性与完整性 | 证据质量不因「全量」自动升级；来源、控制与验证决定可靠性 |
| 分析程序 | AU-C 520 | ADA 与分析程序高度重叠但不等同：不是所有 ADA 都是分析程序；用作实质性分析程序时，要建立期望值、定可接受差异门槛（低于重要性）、超限必须调查并印证管理层解释；计划阶段与临近结束的总体复核阶段的分析程序是必做项 | 期望值须精确到能识别重大错报；关系越可预测，证据力越强 |
| 审计抽样 | AU-C 530 | 只有当审计师有意用样本结果推断总体时才进 530：要考虑抽样风险、非抽样风险与可容忍错报；全量测试（100% 检查）不是抽样，不产生抽样风险，也不能把全量筛出的异常率直接当总体错报率 | 推断只能来自按抽样设计的样本；异常项的性质与原因仍须逐项评价 |

这张表的答题价值在分界：同一套收入分录可视化，用在 315 是找风险、用在 520 是取实质性证据、用在 530 的抽样里只是选样或分层工具——目的不同，达标线完全不同，选项里混着给就逐项对目的。

### 四、全量测试对抽样：省掉的是抽样风险，不是判断

ADA 最常被夸大的卖点是「查了 100%，所以没有风险」。把话拆开：对确实被完整、准确地纳入分析的那部分总体，全量测试消除了抽样风险（样本不代表总体的风险）；但它一点也不消除非抽样风险——数据本身不完整、筛选逻辑写错、阈值定得太宽、异常被解释掉却没有印证，都会让全量测试漏掉错报。反过来，抽样的价值也没有被全量测试废掉：需要人工检查原始凭证、函证、盘点观察的认定，逐笔看的成本决定了抽样仍是常态，此时 AU-C 530 的推断纪律（样本须有代表性、发现的错报要推断到总体并评价）照常适用。

还要分清两种「异常」：ADA 按规则筛出的异常项（exception / notable item）只是「与设定模式不一致」，可能是错报，也可能是正当的业务波动、数据口径问题或模型误报；只有经过追加程序追查、拿到印证证据的那部分，才升级为已识别错报。把检出率直接读成错报率，是实务与考试共同的错法。

### 五、数据可靠性与完整性验证：跑分析之前先验数据

AU-C 500 落到 ADA 上就是一组动手动作，指南第三步「考虑相关性与可靠性」与之对应：

- **完整性**：记录数、控制总数与哈希或金额合计要与源系统对账——提取行数对源表行数、金额合计对总账或报表数、期间覆盖无缺口；缺号检查（如发票号、支票号断号）本身既是完整性测试也是审计程序。
- **准确性**：抽取字段与源记录抽样核对（字段截断、日期与币种转换、负数与冲销符号最容易在 ETL 中出错）；重算类 ADA 要先在已知答案的小样本上验证逻辑。
- **相关性**：总体定义要与认定对齐——测收入发生认定用的是开票总体，测完整性认定要从发货或履约记录反向追到账面，拿错总体的全量分析再全也证明不了目标认定。
- **控制背景**：数据来自 IT 一般控制薄弱的系统时，可靠性打折，须加大直接验证；这与 ISC 的信息系统与控制内容直接衔接。

### 六、职业判断的边界：模型提名，人来定罪

ADA 改变的是审计师「看哪里」，不改变「谁下结论」。边界有三条：其一，阈值与模型参数（多大的波动算异常、哪些变量进模型）是职业判断，定得太松漏风险、太紧淹没在误报里，都要在底稿里说清理由；其二，异常项的处置是职业判断——管理层解释只能作线索，须以其他证据印证，这与 AU-C 520 对超限差异必须调查的要求同源，也与 AU-C 240 的职业怀疑相通：异常集中在期末、特定人员或特定客户时，先按舞弊风险因素想一遍再接受解释；其三，自动化偏见是明文要防的坑——工具没标红不等于没问题，未覆盖的认定、总体之外的数据与线下交易，仍靠传统程序与判断补位。

### 七、算例：检出率不是错报率，推断只来自抽样

**算例一（全量 ADA，自编）**：收入明细账全年共 200,000 行分录，ADA 按「期末集中过账、整数金额、同一客户同日多笔」等规则筛出异常项 2,400 行。异常检出率＝2,400 ÷ 200,000＝**1.2%**。追查结果：2,100 行有正当业务原因并获印证证据；300 行转入细节测试。勾稽：2,100＋300＝2,400，与筛出数相等。注意口径：1.2% 是「与规则模式不一致的比例」，在 300 行查完之前，不能说总体错报率是 1.2%，更不能反推其余 98.8%「已证明无错报」——未被规则命中的错报类型不在这套规则的视野内。

**算例二（抽样推断，自编）**：应收账款总体账面 10,000,000 美元，审计师按 AU-C 530 抽查账面 500,000 美元的样本（占总体 5%），样本中查实错报 15,000 美元。样本错报率＝15,000 ÷ 500,000＝**3%**；比率法推断总体错报＝3% × 10,000,000＝**300,000 美元**。复算：15,000 ÷ 500,000＝0.03，0.03 × 10,000,000＝300,000，勾稽成立。两例并排的考点：算例一没有推断动作（全量筛选只负责提名），算例二有推断动作且推断纪律归 AU-C 530——把两者的数字口径互换，就是选项里最常见的偷换。

### 八、考试定位：AUD 为主，BAR 与 ISC 各沾一边

CPA Evolution 是「核心＋学科」结构：核心三科 AUD、FAR、REG 人人必考，学科三选一（BAR、ISC、TCP）。ADA 的主考场在 AUD——蓝图把数据与技术概念贯穿于风险评估、证据与报告各领域，AICPA 还发布过以 ADA、数据完整性测试与可视化分析为题的退役模拟题（retired TBS）供备考参照。BAR 一侧接数据分析与可视化的商业分析用法（同一套图形与比率，目的从取证换成经营分析，达标线随之不同）；ISC 一侧接数据治理、系统控制与 SOC 业务，第五节的可靠性验证在那边是系统与数据管理的问题。答题时先问「这道题要的是审计证据，还是经营洞见，还是系统控制」，再选准则，避免三科口径串线。

**加州一格**：加州不另设 ADA 或 CAATs 准则——加州 CPA 执行非发行人审计同样遵循 AICPA 的 GAAS（AU-C 体系），发行人审计遵循 PCAOB 准则；工具选用与软件品牌不属加州会计委员会（CBA）的规范事项，CBA 管的是执照、独立性与执业质量，备考时不要给加州编造单独的数据分析规则。

**易错点清单**：

- 把指南当权威准则——它是其他审计出版物，权威性在 AU-C 本身。
- 以为 GAAS 要求必须用 ADA——不要求；要求的是程序要对风险、证据要充分适当。
- 全量测试后宣称无抽样风险即无审计风险——非抽样风险与总体外风险仍在。
- 异常检出率直接当错报率、或把筛余部分说成已获保证——都不成立。
- 重大风险只用实质性分析程序（含 ADA 分析）应对，不做细节测试——违反 AU-C 330 的应对要求。
- 用管理层解释直接销掉超限差异，不印证——违反 AU-C 520 的调查要求。

*声明：个人学习笔记，不构成税务或财务建议。来源：AICPA《Guide to Audit Data Analytics》（ADA 定义、五步流程与「其他审计出版物」定位，Journal of Accountancy 2017 年摘录）；AU-C 200、315、330、500、520、530；AICPA CPA Exam Blueprints（CPA Evolution 核心＋学科结构与 AUD 数据技术内容）与 AICPA 退役 AUD 模拟题（ADA 主题）说明。算例为自编教学数字，已本地复算勾稽（见第七节）。*

---

## English

Audit data analytics (ADA) is a technique, not a new standard. The AICPA *Guide to Audit Data Analytics* defines ADAs as the science and art of discovering and analyzing patterns, identifying anomalies, and extracting other useful information in data underlying or related to the subject matter of an audit through analysis, modeling, and visualization for the purpose of planning or performing the audit. The Guide is an "other auditing publication" under AU-C 200 with no authoritative status, and GAAS does not require ADAs. Every ADA is therefore judged under the standard governing the procedure it serves: AU-C 315 when it is a risk-assessment procedure, AU-C 330 for responses to assessed risks (a significant risk cannot be addressed by substantive analytical procedures alone — tests of details are required), AU-C 500 for the sufficiency and appropriateness of any evidence it yields, AU-C 520 when it functions as an analytical procedure (build an expectation, set an acceptable difference below materiality, investigate and corroborate differences above it), and AU-C 530 only when the auditor actually samples and projects to a population. CAATs are the older tool label; visualization helps the auditor see the shape of an anomaly, but a chart produces a notable item, not a conclusion.

The Guide's five steps for a risk-assessment ADA are: (1) plan the ADA — items, assertions, population, purpose, objectives, data considerations, techniques and graphics; (2) access and prepare the data; (3) consider the relevance and reliability of the data used; (4) perform the ADA, revising and reperforming if the design needs it, and plan follow-up procedures on items warranting further consideration; (5) evaluate the results and conclude whether the purpose and objectives were achieved — if not, perform different procedures. Before any analysis, AU-C 500 discipline applies to information produced by the entity: prove completeness (record counts and control totals reconciled to the source system, gap tests) and accuracy (field-level checks, since truncation, date and currency conversion, and sign errors creep in during extraction), and define the population to match the assertion — testing completeness of revenue from the sales ledger alone proves nothing.

Full-population testing removes sampling risk for the population actually captured completely and accurately; it removes nothing else. Non-sampling risk — incomplete data, wrong filter logic, thresholds set too wide, explanations accepted without corroboration — survives a 100% run untouched. An exception rate is not a misstatement rate. **Worked example 1 (full-population ADA):** 200,000 revenue journal lines yield 2,400 flagged items, an exception rate of 2,400 ÷ 200,000 = **1.2%**; follow-up corroborates a legitimate explanation for 2,100 and sends 300 to tests of details (2,100 + 300 = 2,400, footing to the flagged total), and until those 300 are resolved the 1.2% says nothing about the population misstatement rate. **Worked example 2 (sampling projection):** in a $10,000,000 receivables population, a sample with book value $500,000 contains $15,000 of factual misstatement; the sample rate is 15,000 ÷ 500,000 = **3%**, and the ratio projection is 3% × $10,000,000 = **$300,000** — projection is an AU-C 530 act and belongs only to designed samples. Professional judgment sets the thresholds, disposes of notable items (management explanations are leads, not evidence; AU-C 520 investigation and AU-C 240 skepticism apply), and guards against automation bias: what the tool did not flag is not thereby cleared.

For the CPA Evolution exam (Core AUD/FAR/REG plus one Discipline — BAR, ISC, or TCP), ADA lives mainly in AUD, where the Blueprint weaves data and technology concepts through risk assessment and evidence, and AICPA has released a retired AUD simulation on ADA, completeness testing, and visualization; BAR borrows the same charts for business analysis rather than evidence, and ISC covers the data-governance and controls side. California sets no separate ADA rule: nonissuer audits follow GAAS and issuer audits follow PCAOB standards. *Personal study notes only; not tax or financial advice.*

## Español (traducción de estudio, pendiente de revisión nativa)

La analítica de datos de auditoría (ADA) es una técnica, no una norma nueva. La *Guide to Audit Data Analytics* de la AICPA la define como la ciencia y el arte de descubrir y analizar patrones, identificar anomalías y extraer información útil de los datos del encargo mediante análisis, modelado y visualización, con el fin de planificar o ejecutar la auditoría. La guía es una «otra publicación de auditoría» en el marco de la AU-C 200, sin carácter autoritativo, y las GAAS no exigen usar ADA. Cada ADA se juzga por la norma del procedimiento al que sirve: AU-C 315 en evaluación de riesgos, AU-C 330 en respuestas (un riesgo significativo no se atiende solo con procedimientos analíticos sustantivos: hacen falta pruebas de detalle), AU-C 500 para la suficiencia e idoneidad de la evidencia, AU-C 520 cuando actúa como procedimiento analítico (expectativa, umbral aceptable por debajo de la materialidad e investigación corroborada de las diferencias) y AU-C 530 solo cuando hay muestreo con proyección. Las CAATs son la etiqueta clásica de las herramientas; un gráfico señala un elemento notable, no una conclusión.

Los cinco pasos de la guía para una ADA de evaluación de riesgos son: planificarla, acceder a los datos y prepararlos, considerar su relevancia y fiabilidad, ejecutarla (con procedimientos adicionales sobre los elementos señalados) y evaluar si se lograron el propósito y los objetivos. Antes de analizar, la información producida por la entidad debe validarse: integridad (conteos y totales de control conciliados con el sistema fuente, pruebas de huecos en la numeración) y exactitud (truncamientos y errores de conversión o de signo en la extracción), y la población debe corresponder a la afirmación examinada.

Examinar el 100% elimina el riesgo de muestreo sobre la población efectivamente capturada, pero no el riesgo ajeno al muestreo: datos incompletos, filtros mal diseñados o explicaciones aceptadas sin corroboración. La tasa de excepciones no es la tasa de incorrección. **Ejemplo 1:** 200.000 líneas de ingresos generan 2.400 elementos señalados, el 1,2% (2.400 ÷ 200.000); 2.100 se corroboran como legítimos y 300 pasan a pruebas de detalle (2.100 + 300 = 2.400). **Ejemplo 2:** en una población de cuentas por cobrar de $10.000.000, una muestra de $500.000 contiene $15.000 de incorrección: 3% muestral y proyección de $300.000, un acto propio de la AU-C 530. En CPA Evolution (núcleo AUD/FAR/REG y una disciplina entre BAR, ISC y TCP), la ADA se examina sobre todo en AUD; California no tiene norma propia de ADA. *Notas personales de estudio; no es asesoría fiscal ni financiera.*

## 한국어 (초역, 원어민 감수 대기)

감사 데이터 분석(ADA)은 새로운 기준이 아니라 기법입니다. AICPA 《Guide to Audit Data Analytics》는 ADA를 감사를 계획하거나 수행하기 위해 분석·모델링·시각화를 통해 감사 대상 데이터에서 패턴을 발견하고 이상을 식별하며 유용한 정보를 추출하는 과학이자 예술로 정의합니다. 이 지침은 AU-C 200 체계에서 «기타 감사 간행물»로 권위가 없으며, GAAS는 ADA 사용을 요구하지 않습니다. 따라서 ADA는 그것이 돕는 절차의 기준에 따라 평가됩니다. 위험평가 절차이면 AU-C 315, 위험 대응이면 AU-C 330(중요한 위험은 실질적 분석적 절차만으로 대응할 수 없고 세부 테스트가 필요합니다), 증거이면 AU-C 500의 충분성과 적합성, 분석적 절차로 쓰이면 AU-C 520(기대값 설정, 중요성보다 낮은 허용 차이, 초과 차이의 조사와 입증), 표본 결과를 모집단으로 추론할 때만 AU-C 530이 적용됩니다. CAATs는 도구의 옛 이름이며, 시각화는 주목 항목(notable item)을 보여줄 뿐 결론을 만들지 않습니다.

위험평가 ADA의 다섯 단계는 계획, 데이터 접근·준비, 데이터의 관련성과 신뢰성 검토, 실행(주목 항목에 대한 추가 절차 포함), 목적 달성 여부의 평가와 결론입니다. 실행 전에 기업이 만든 정보(IPE)의 완전성(레코드 수와 통제합계의 원천 시스템 대조, 번호 누락 검사)과 정확성(추출 과정의 절단·변환·부호 오류 점검)을 검증해야 하고, 모집단 정의는 확인하려는 인정과 일치해야 합니다.

전수 검사는 실제로 완전히 포착한 모집단에 대해 표본위험을 없애지만 비표본위험(불완전한 데이터, 잘못된 필터, 넓은 임계값, 입증 없는 설명 수용)은 그대로 남습니다. 예외 비율은 오류 비율이 아닙니다. **예시 1(전수 ADA):** 수익 분개 200,000행에서 2,400행이 표시되어 예외 비율은 2,400 ÷ 200,000 = **1.2%**이고, 2,100행은 정당한 사유가 입증되고 300행이 세부 테스트로 넘어가 2,100 + 300 = 2,400으로 맞아떨어집니다. **예시 2(표본 추론):** 장부가 10,000,000달러인 매출채권 모집단에서 장부 500,000달러 표본의 확인된 오류가 15,000달러이면 표본 오류율은 3%이고 비율법 추론액은 300,000달러로, 추론은 AU-C 530의 영역입니다. 임계값 설정과 주목 항목 처분은 전문가적 판단이며, 경영진 설명은 증거가 아니라 단서입니다. CPA Evolution(핵심 AUD/FAR/REG + 학문 분야 BAR·ISC·TCP 중 하나)에서는 ADA가 주로 AUD에서 출제되고, 캘리포니아에는 별도의 ADA 규칙이 없습니다. *개인 학습 노트이며 세무·재무 자문이 아닙니다.*

보충 세부사항: 위험평가 ADA의 문서화는 AU-C 315 제.33항 부근의 위험평가 기록 요구와 연결되며, 지침 제1.48–1.56항이 ADA 기록 사항을 별도로 다룹니다. 자동화 편향(automation bias)은 명시적으로 경계해야 할 함정입니다. 도구가 표시하지 않았다고 문제가 없는 것은 아니며, 모집단 밖의 데이터와 오프라인 거래는 전통적 절차로 메워야 합니다. 중요한 위험(significant risk)에 대해서는 실질적 분석적 절차만으로 대응할 수 없고 세부 테스트를 반드시 포함해야 한다는 AU-C 330의 요구, 그리고 허용 차이를 초과한 차이는 경영진 설명만으로 지우지 말고 조사·입증해야 한다는 AU-C 520의 요구가 대표적 오답 포인트입니다. 시험에서는 ADA 자체를 충분한 증거로 취급하는 보기, 검출률을 오류율로 읽는 보기, 전수 검사 후 표본위험이 없으니 감사위험도 없다는 보기가 반복해서 틀린 선택지로 등장합니다. 캘리포니아는 별도의 ADA 규칙을 두지 않습니다. 비상장 발행인 감사는 GAAS(AU-C 체계)를, 발행인 감사는 PCAOB 기준을 따릅니다.

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

Phân tích dữ liệu kiểm toán (ADA) là một kỹ thuật, không phải một chuẩn mực mới. *Guide to Audit Data Analytics* của AICPA định nghĩa ADA là khoa học và nghệ thuật khám phá, phân tích các mẫu hình, nhận diện điểm bất thường và trích xuất thông tin hữu ích từ dữ liệu của cuộc kiểm toán thông qua phân tích, mô hình hóa và trực quan hóa, nhằm lập kế hoạch hoặc thực hiện kiểm toán. Tài liệu hướng dẫn này là «ấn phẩm kiểm toán khác» theo AU-C 200, không có tính quyền uy, và GAAS không bắt buộc dùng ADA. Vì vậy mỗi ADA được đánh giá theo chuẩn mực của thủ tục mà nó phục vụ: AU-C 315 cho đánh giá rủi ro, AU-C 330 cho biện pháp ứng phó (rủi ro đáng kể không thể chỉ dùng thủ tục phân tích cơ bản mà phải có kiểm tra chi tiết), AU-C 500 cho tính đầy đủ và thích hợp của bằng chứng, AU-C 520 khi ADA đóng vai trò thủ tục phân tích (xây dựng giá trị kỳ vọng, ngưỡng chênh lệch chấp nhận được thấp hơn mức trọng yếu, điều tra và chứng thực các chênh lệch vượt ngưỡng), và AU-C 530 chỉ khi kiểm toán viên lấy mẫu và suy rộng cho tổng thể. CAATs là tên gọi cũ của công cụ; biểu đồ chỉ nêu ra khoản mục đáng chú ý chứ không tạo ra kết luận.

Năm bước của hướng dẫn cho một ADA đánh giá rủi ro là: lập kế hoạch, truy cập và chuẩn bị dữ liệu, xem xét tính thích hợp và độ tin cậy của dữ liệu, thực hiện ADA (kèm thủ tục bổ sung cho các khoản mục đáng chú ý), và đánh giá xem mục đích cùng mục tiêu có đạt hay không. Trước khi phân tích phải kiểm chứng thông tin do đơn vị tạo ra: tính đầy đủ (đối chiếu số bản ghi và tổng khống chế với hệ thống nguồn, kiểm tra đứt số) và tính chính xác (lỗi cắt trường, chuyển đổi ngày/tiền tệ, dấu âm trong quá trình trích xuất), đồng thời tổng thể phải khớp với cơ sở dẫn liệu cần kiểm tra.

Kiểm tra toàn bộ loại bỏ rủi ro chọn mẫu đối với tổng thể thực sự được thu thập đầy đủ, nhưng không loại bỏ rủi ro phi chọn mẫu. Tỷ lệ ngoại lệ không phải tỷ lệ sai sót. **Ví dụ 1:** 200.000 dòng bút toán doanh thu cho ra 2.400 khoản bị gắn cờ, tỷ lệ 2.400 ÷ 200.000 = **1,2%**; 2.100 khoản được chứng thực là hợp lệ và 300 khoản chuyển sang kiểm tra chi tiết (2.100 + 300 = 2.400). **Ví dụ 2:** trong tổng thể phải thu 10.000.000 USD, mẫu có giá trị sổ sách 500.000 USD chứa sai sót thực tế 15.000 USD, tỷ lệ mẫu là 3% và suy rộng theo tỷ lệ là 300.000 USD — việc suy rộng thuộc AU-C 530. Ngưỡng và cách xử lý khoản mục đáng chú ý là xét đoán nghề nghiệp; lời giải thích của ban quản lý chỉ là manh mối, không phải bằng chứng. Trong CPA Evolution, ADA chủ yếu thuộc môn AUD và California không có quy tắc ADA riêng. *Ghi chép học tập cá nhân, không phải tư vấn thuế hay tài chính.*

Chi tiết bổ sung: tài liệu hóa của một ADA đánh giá rủi ro gắn với yêu cầu ghi chép đánh giá rủi ro quanh AU-C 315 đoạn .33, và hướng dẫn dành các đoạn 1.48–1.56 cho các vấn đề ghi chép ADA. Thiên kiến tự động hóa (automation bias) là cái bẫy phải nêu rõ: công cụ không gắn cờ không có nghĩa là không có vấn đề, và dữ liệu ngoài tổng thể cùng giao dịch ngoại tuyến vẫn phải được bù bằng thủ tục truyền thống. Với rủi ro đáng kể, AU-C 330 cấm chỉ dựa vào thủ tục phân tích cơ bản mà bắt buộc phải có kiểm tra chi tiết; AU-C 520 yêu cầu điều tra và chứng thực các chênh lệch vượt ngưỡng chứ không xóa chúng bằng lời giải thích của ban quản lý. Các lỗi hay gặp trong phòng thi gồm: coi chính việc dùng ADA là bằng chứng đầy đủ, đọc tỷ lệ ngoại lệ thành tỷ lệ sai sót, và tuyên bố kiểm tra 100% xong thì không còn rủi ro kiểm toán. California không có quy tắc ADA riêng: kiểm toán đơn vị không phát hành theo GAAS (hệ AU-C), kiểm toán tổ chức phát hành theo chuẩn mực PCAOB.

## हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

ऑडिट डेटा एनालिटिक्स (ADA) एक तकनीक है, कोई नया मानक नहीं। AICPA की *Guide to Audit Data Analytics* ADA को ऑडिट की योजना बनाने या उसे करने के उद्देश्य से विश्लेषण, मॉडलिंग और विज़ुअलाइज़ेशन के माध्यम से ऑडिट से जुड़े डेटा में पैटर्न खोजने, विसंगतियाँ पहचानने और उपयोगी जानकारी निकालने का विज्ञान और कला कहती है। यह गाइड AU-C 200 के ढाँचे में «अन्य ऑडिट प्रकाशन» है, इसका कोई आधिकारिक दर्जा नहीं है, और GAAS ADA का उपयोग अनिवार्य नहीं करता। इसलिए हर ADA उसी मानक से परखा जाएगा जिस प्रक्रिया की वह सेवा करता है: जोखिम-आकलन में AU-C 315, जोखिम-प्रतिक्रिया में AU-C 330 (महत्वपूर्ण जोखिम का उत्तर केवल मूलभूत विश्लेषणात्मक प्रक्रियाओं से नहीं दिया जा सकता — विवरण परीक्षण आवश्यक हैं), साक्ष्य के लिए AU-C 500, विश्लेषणात्मक प्रक्रिया के रूप में AU-C 520 (अपेक्षा बनाना, महत्वपूर्णता से नीचे स्वीकार्य अंतर रखना, सीमा से ऊपर के अंतर की जाँच और पुष्टि), और AU-C 530 केवल तब जब नमूने से समष्टि पर अनुमान लगाया जाए। CAATs उपकरणों का पुराना नाम है; कोई चार्ट केवल ध्यान देने योग्य मद (notable item) दिखाता है, निष्कर्ष नहीं बनाता।

जोखिम-आकलन ADA के पाँच चरण हैं: योजना, डेटा तक पहुँच और तैयारी, डेटा की प्रासंगिकता और विश्वसनीयता पर विचार, निष्पादन (ध्यान योग्य मदों पर अतिरिक्त प्रक्रियाओं सहित), और उद्देश्य पूरे हुए या नहीं, इसका मूल्यांकन। विश्लेषण से पहले इकाई द्वारा बनाई गई जानकारी की पूर्णता (रिकॉर्ड गिनती और नियंत्रण योगों का स्रोत प्रणाली से मिलान, क्रमांक-छेद जाँच) और शुद्धता (निष्कर्षण में कटाव, तिथि/मुद्रा रूपांतरण और चिह्न त्रुटियाँ) सत्यापित करनी होगी, और समष्टि की परिभाषा उस अभिकथन से मेल खानी चाहिए जिसकी जाँच हो रही है।

100% जाँच उस समष्टि पर प्रतिचयन जोखिम खत्म करती है जो सचमुच पूरी और सही पकड़ी गई हो, पर ग़ैर-प्रतिचयन जोखिम (अधूरा डेटा, ग़लत फ़िल्टर, ढीली सीमाएँ, बिना पुष्टि स्वीकार की गई व्याख्याएँ) बना रहता है। अपवाद दर त्रुटि दर नहीं होती। **उदाहरण 1:** राजस्व जर्नल की 200,000 पंक्तियों में 2,400 चिह्नित हुईं — दर 2,400 ÷ 200,000 = **1.2%**; 2,100 की वैध व्याख्या पुष्ट हुई और 300 विवरण परीक्षण में गईं (2,100 + 300 = 2,400)। **उदाहरण 2:** $10,000,000 की प्राप्य समष्टि में $500,000 बही-मूल्य वाले नमूने में $15,000 की वास्तविक त्रुटि मिली; नमूना दर 3% और अनुपात-आधारित अनुमान $300,000 — अनुमान AU-C 530 का काम है। सीमाएँ तय करना और मदों का निपटान पेशेवर विवेक है; प्रबंधन की व्याख्या सुराग़ है, साक्ष्य नहीं। CPA Evolution में ADA मुख्यतः AUD में आता है और कैलिफ़ोर्निया का कोई अलग ADA नियम नहीं है। *व्यक्तिगत अध्ययन नोट; कर या वित्तीय सलाह नहीं है।*

पूरक विवरण: जोखिम-आकलन ADA का दस्तावेज़ीकरण AU-C 315 के अनुच्छेद .33 के आसपास की जोखिम-आकलन अभिलेख आवश्यकताओं से जुड़ता है, और गाइड के अनुच्छेद 1.48–1.56 ADA अभिलेख विषयों पर अलग से चर्चा करते हैं। स्वचालन पूर्वाग्रह (automation bias) स्पष्ट रूप से बचना चाहिए: उपकरण ने कुछ चिह्नित नहीं किया तो इसका अर्थ यह नहीं कि समस्या नहीं है, और समष्टि से बाहर का डेटा व ऑफ़लाइन लेनदेन पारंपरिक प्रक्रियाओं से पूरे करने होंगे। महत्वपूर्ण जोखिम के लिए AU-C 330 केवल मूलभूत विश्लेषणात्मक प्रक्रियाओं को अपर्याप्त मानकर विवरण परीक्षण अनिवार्य करता है, और AU-C 520 सीमा से ऊपर के अंतरों की जाँच व पुष्टि माँगता है — प्रबंधन की व्याख्या से उन्हें मिटाया नहीं जा सकता। परीक्षा की आम ग़लतियाँ हैं: ADA के उपयोग को ही पर्याप्त साक्ष्य मानना, अपवाद दर को त्रुटि दर पढ़ना, और 100% जाँच के बाद ऑडिट जोखिम समाप्त घोषित करना। कैलिफ़ोर्निया का कोई अलग ADA नियम नहीं है: ग़ैर-जारीकर्ता ऑडिट GAAS (AU-C प्रणाली) से और जारीकर्ता ऑडिट PCAOB मानकों से चलता है।
---

*声明：个人学习笔记，不构成法律、税务或医疗建议（personal study notes only; not legal, tax, or medical advice）。*

## 补译增量 · 한국어 / Tiếng Việt / हिन्दी（细节对齐）

### 한국어 (초역, 원어민 감수 대기)

보충 1 — 탐지율은 오류율이 아니다: 자릿수를 맞춘 예에서 전수 ADA는 200,000개 분개 중 규칙에 걸린 2,400개를 뽑아 탐지율 1.2%를 만들지만, 추적 결과 2,100개는 정당 사유로 확인되고 300개만 세부 테스트로 넘어갑니다(2,100+300=2,400으로 대사 일치). 300개가 끝나기 전에는 전체 오류율이 1.2%라고 말할 수 없고, 규칙에 걸리지 않은 나머지 98.8%가 "오류 없음이 증명됐다"고 역으로 말할 수도 없습니다 —— 규칙의 시야 밖에 있는 오류 유형은 이 분석이 보지 못합니다.

보충 2 — 전수 검사가 없애는 것과 못 없애는 것: 완전하고 정확하게 포함된 모집단에 대해서는 전수 검사가 표본추출 위험을 없애지만, 비표본 위험——데이터 자체의 불완전, 잘못 쓴 필터 논리, 너무 넓은 임계값, 입증 없이 받아들인 설명——은 그대로 남습니다. 실행 전에 원천 표의 행 수와 통제 합계를 대조하고, 발송 기록에서 장부로 역추적하는 등 총모집단 정의가 인정(assertion)과 맞는지부터 확인해야 합니다.

### Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

Bổ sung 1 — Tỷ lệ phát hiện không phải tỷ lệ sai sót: trong ví dụ đã đối chiếu, ADA toàn bộ rút ra 2.400 dòng trong 200.000 bút toán, tỷ lệ phát hiện 1,2%; truy vết cho thấy 2.100 dòng có lý do chính đáng kèm bằng chứng, chỉ 300 dòng chuyển sang kiểm tra chi tiết (2.100 + 300 = 2.400, khớp số rút ra). Trước khi 300 dòng đó xong, không thể nói tỷ lệ sai sót toàn thể là 1,2%, càng không thể suy ngược rằng 98,8% còn lại "đã được chứng minh không sai" — loại sai sót nằm ngoài tầm nhìn của bộ quy tắc thì phân tích này không thấy.

Bổ sung 2 — Kiểm tra toàn bộ xóa được gì và không xóa được gì: với phần tổng thể đã được đưa vào đầy đủ và chính xác, kiểm tra 100% loại bỏ rủi ro chọn mẫu, nhưng rủi ro phi chọn mẫu vẫn nguyên — dữ liệu thiếu, logic lọc viết sai, ngưỡng quá rộng, lời giải thích được chấp nhận mà không đối chứng. Trước khi chạy, đối chiếu số dòng và tổng kiểm soát với hệ thống nguồn, kiểm tra đứt số thứ tự, và bảo đảm định nghĩa tổng thể khớp với cơ sở dẫn liệu (assertion) đang kiểm tra — ví dụ kiểm tra tính đầy đủ phải truy ngược từ hồ sơ giao hàng về sổ sách.

### हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

पूरक 1 — पहचान दर, त्रुटि दर नहीं है: मिलान किए गए उदाहरण में पूर्ण-जनसंख्या ADA ने 200,000 प्रविष्टियों में नियम-विरुद्ध 2,400 निकाले, पहचान दर 1.2%; पड़ताल में 2,100 के वैध कारण साक्ष्य सहित मिले और केवल 300 विस्तृत परीक्षण में गए (2,100 + 300 = 2,400, निकाली संख्या से मेल)। उन 300 की जाँच से पहले समग्र त्रुटि दर 1.2% नहीं कही जा सकती, और शेष 98.8% को "त्रुटिहीन सिद्ध" भी नहीं कहा जा सकता — नियमों की दृष्टि से बाहर की त्रुटि-प्रकार इस विश्लेषण को दिखते ही नहीं।

पूरक 2 — पूर्ण परीक्षण क्या मिटाता है और क्या नहीं: जो जनसंख्या पूर्ण व सटीक रूप से शामिल हुई, उसके लिए 100% परीक्षण प्रतिचयन जोखिम समाप्त करता है, पर गैर-प्रतिचयन जोखिम बना रहता है — अधूरा डेटा, गलत लिखी फिल्टर तर्क-प्रणाली, अत्यधिक चौड़ी सीमा, बिना सहायक साक्ष्य स्वीकारी गई व्याख्या। चलाने से पहले स्रोत तालिका की पंक्ति-संख्या व नियंत्रण योग मिलाएँ, अनुक्रम-विच्छेद जाँचें, और जनसंख्या परिभाषा को परीक्षणाधीन दावे (assertion) से जोड़ें — पूर्णता के लिए शिपिंग अभिलेखों से बही की ओर उल्टा पता लगाना होगा।
