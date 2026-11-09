# 区块链与数字资产审计备考核心：存在性、权利与估值断言，私钥控制证据与 AU-C 口径

> 个人学习笔记，不构成税务或会计建议。本文管的是审计与鉴证这一侧：数字资产怎么审、证据怎么拿。计量侧已有仓内《数字资产会计备考核心》管 ASU 2023-08 与 ASC 350-60 的公允价值处理，两篇以指针分工。具体审计处理以准则原文、AICPA 执业指引与公司审计师判断为准。

## 中文主文

审数字资产，难的不是看价格，而是先证明三件事：链上那笔资产真的存在、客户真的有权动它、报表上的金额真的站得住。普通存货有仓库、银行存款有函证，数字资产的仓库是一串字符、钥匙是一组私钥，谁掌握私钥谁就能转走资产，而且转账不可逆、地址又不写名字。这篇把断言、证据与准则锚点一次拆清。

### 一、断言地图：存在性、权利与完整性先于估值

- **存在性（existence）**：报表日链上或托管账户里的资产真实存在、数量对得上。证据要落到具体区块链地址与托管账户，不能只看管理层导出的一张电子表格。
- **权利与义务（rights and obligations）**：客户对地址有控制权、资产没有被质押或借出而未披露。数字资产的权利锚点不是一张权属证书，而是私钥控制：能控制私钥或多签安排中足够份额的一方，才推定能支配资产；资产放在交易所时，权利形态变成对交易所的债权性请求权，要与自托管分开评价。
- **完整性（completeness）**：所有钱包、交易所账户与链上地址都进了账。难点在匿名性与多地址：同一控制人可以有任意多个地址，遗漏一个热钱包，完整性就破了。分叉币、空投、质押奖励这类链上原生流入没有对手方单据，最容易漏记。
- **估值与分摊（valuation）**：价格取哪个市场、哪个时点，流动性差的代币怎么估，见第四节。
- **列报（presentation）**：自托管与第三方托管、受限或质押部分、自有资产与代客户持有的资产，分开列报与披露，口径与仓内数字资产会计篇的 ASC 350-60 衔接。

### 二、私钥控制证据：证明能动这笔钱，又不碰种子短语

- **签名验证**：请客户用钱包私钥对审计师随机给定的信息签名（sign a message），审计师用公开地址验签。能签出有效签名，说明客户在验证时点掌握该地址的私钥控制，这是存在性与权利断言的核心程序之一。
- **小额测试转账**：请客户把极小金额在自有地址之间或向审计师指定地址转一笔（业界常称 Satoshi test 一类做法），链上可查、金额可控，证明的不只是账面记录，而是实际动账能力。
- **观察与多签**：多重签名钱包要核签名人构成与门槛，观察客户在受控环境下发起签名；硬件钱包与托管安排要核设备与流程。
- **红线**：审计师绝不索取、绝不保管客户的种子短语或私钥全文。拿到私钥等于接管了资产的处置能力，既毁独立性也造安全风险；证据设计必须是客户演示控制、审计师观察验证，而不是客户交出钥匙。
- **时点与截止**：链上余额要按报表日的区块高度或时间戳截取，时区与区块时间要留档；报表日前后大额转入转出要查截止，防窗口修饰。

### 三、第三方托管与 SOC 报告：函证拿不到时怎么办

- **先分托管形态**：自托管（客户自持私钥）、第三方托管（持牌托管人）、交易所账户（平台代持、资产负债表外安排各异），三种形态的证据路线完全不同，不能一套程序打天下。
- **函证的现实**：AU-C 505 的外部函证思路在这里常碰壁，不少交易所不回函或只给账户快照。回函缺位时用替代程序补：客户在审计师在场时登录账户取数、链上地址与平台充值地址交叉核对、期后出入金流水核对。
- **SOC 报告怎么用**：托管人提供的 SOC 1 或 SOC 2 Type II 报告，按 AU-C 402 的服务组织框架评价：看报告覆盖期间与报表日是否衔接、例外事项、互补用户实体控制（CUEC）客户一侧有没有落实。SOC 报告证明的是托管人的控制，不是客户资产的数量本身，数量仍要单独取证。
- **储备证明的分界**：市场上常见的 proof of reserves 只是某一时点对链上资产的证明，通常不含负债端，不是审计、不提供合理保证，不能替代财务报表审计证据。备考与实务都要把这条界线说清。
- **平台风险**：交易所挪用与倒闭的教训说明，平台账户里的资产还要评价对手方风险与资产隔离安排，并在披露端如实反映。

### 四、估值：主市场价格、时点与不流动代币

- **计价锚点**：在 ASC 350-60 公允价值口径下，活跃市场资产取主市场（principal market）或最有利市场的报价，乘持有数量。多个交易所价格不一致时，要有一贯的主市场判定政策，不能逐笔挑最高价。
- **算例**：某客户报表日持有 BTC 2 枚与 ETH 10 枚，主市场报价分别为每枚 95,000 美元与每枚 3,200 美元。BTC 部分 2 乘 95,000 等于 190,000 美元，ETH 部分 10 乘 3,200 等于 32,000 美元，合计 190,000 加 32,000 等于 222,000 美元。本地两遍复算，勾稽一致。
- **对账算例**：客户称持有 BTC 共 10 枚，其中交易所账户 6 枚、自托管冷钱包 4 枚，6 加 4 等于 10 枚对上总数；按同一报价 95,000 美元计，总额为 10 乘 95,000 等于 950,000 美元。数量先对平，金额才有着落，这正是存在性先于估值的算例版。
- **不流动与长尾代币**：报价稀薄、交易量极低的代币可能落入公允价值层级较低层级，要用 AU-C 540 的估计审计思路与 AU-C 620 的估值专家：质疑模型、关键假设与折价依据，管理层自报的内部价格不能直接采信。
- **质押与借出**：参与质押（staking）或借出的资产要评价罚没（slashing）与对手方风险对估值和披露的影响，锁仓部分的可变现性不能按自由流通价无条件套用。

### 五、准则锚点：AU-C 500、501、620 与 AICPA 指引及 PCAOB 观察

- **AU-C 500（审计证据）**：充分性与适当性是总纲。链上数据是外部生成的信息，但把链上数据导进审计底稿的工具与接口可靠性要评价；管理层导出的表格属被审计单位生成的信息，使用前要测其准确性与完整性。
- **AU-C 501（特定项目的审计证据）**：其框架思路可类推到数字资产的特定取证设计：对存在性与权利这类高风险断言，要有针对性的专门程序，而不是只做分析程序。存货监盘式的在场观察，在这里对应在场观察客户登录、签名与转账演示。
- **AU-C 620（利用审计师专家的工作）**：区块链取证、钱包溯源与复杂估值常需专家。审计师要评价专家的胜任能力与客观性、约定工作范围、评价专家工作对审计目的的适切性；用专家不转移审计师对意见的责任。
- **AU-C 315 与 330、505 与 540 的衔接**：先按 315 识别重大错报风险（技术复杂性、新型交易、舞弊风险因素），再按 330 设计回应；函证走 505、估计走 540，本篇前四节的程序都是在这张网上落点。
- **AICPA 执业指引**：AICPA 的 Digital Assets Practice Aid（2019 年首发、其后持续更新）是非权威性指引，以问答形式覆盖数字资产的审计与会计问题，包括客户承接、风险评估、存在性与权利取证等，是备考与实务最常引的执业参考，引时注明其非权威地位。
- **PCAOB 观察**：PCAOB 近年在检查与公开材料中持续提示加密资产相关审计的风险点：承接前先评价事务所自身的胜任能力、对交易所与托管证据的过度依赖、专家使用与舞弊风险应对。上市公司审计还要叠加 PCAOB 准则一侧的要求，与 AU-C 不混用。
- **舞弊与法规风险**：地址匿名性抬高了关联方与资金来源的核查难度，未披露钱包、循环转账与对敲交易都要进舞弊风险讨论；客户业务涉无牌经营或制裁名单地址时，AU-C 250 的法规不合规框架同步启动。

### 六、加州口径

- **加州口径**：加州没有另设数字资产审计准则或断言框架，在加州执业的 CPA 做数字资产审计，同样跟随 GAAS（AU-C 体系）与适用时的 PCAOB 准则，执照与纪律归加州会计委员会（California Board of Accountancy）与《商业与职业法典》会计师法一带（证据等级 B：州内无单独审计规则、以全国准则为准系通行口径）。加州金融保护与创新部（DFPI）对部分数字资产活动的监管属业务监管线，不创设审计断言或证据标准，不得把业务合规状态当成审计证据。

> 个人学习笔记，不构成税务或会计建议。
>
> 来源：AICPA AU-C 500、501、505、540、620、402、315、330；AICPA, Accounting for and Auditing of Digital Assets (Practice Aid)；PCAOB 关于加密资产审计的检查观察与公开材料；FASB ASC 350-60 与 ASC 820（计量衔接口径）。

## English

Auditing digital assets turns on three assertions before valuation is even reached. **Existence**: the assets on the balance-sheet date must be tied to specific blockchain addresses and custodian accounts, not to a management spreadsheet. **Rights**: control follows the private keys — the party that controls the keys, or enough shares of a multisig arrangement, is presumed able to dispose of the assets; assets left on an exchange are instead a claim against that exchange and are evaluated separately. **Completeness** is the hard one: one controller can hold unlimited pseudonymous addresses, and forks, airdrops and staking rewards have no counterparty paperwork. Core evidence for control is demonstrative, never surrender-based: the client signs an auditor-supplied random message with the wallet key and the auditor verifies the signature against the public address, or moves a tiny test amount on-chain — while the auditor must never request or hold the seed phrase or the full private key, which would destroy independence and create a security risk. Balances are captured at a block height or timestamp as of the reporting date, with cut-off work around it.

For third-party custody, AU-C 505 confirmation often fails in practice — many exchanges do not reply — so auditors fall back on observed log-ins, on-chain deposit-address matching and post-period flow testing; a custodian's SOC 1 or SOC 2 Type II report is used under the AU-C 402 service-organization framework and proves the custodian's controls, not the quantity of the client's assets, and a marketing-style proof of reserves, which typically omits liabilities, is not an audit and provides no reasonable assurance. Valuation under the ASC 350-60 fair-value model uses the principal-market quote: **example** — 2 BTC at $95,000 plus 10 ETH at $3,200 gives 190,000 + 32,000 = $222,000, and a quantity reconciliation of 6 BTC on an exchange plus 4 BTC in a cold wallet ties to the 10 BTC total (10 × $95,000 = $950,000) before any amount is accepted. Illiquid tokens pull in AU-C 540 estimate auditing and AU-C 620 experts. The standards anchors are AU-C 500 (sufficiency and appropriateness of evidence, including testing entity-produced information), AU-C 501's framework for targeted procedures on specific items, and AU-C 620 on using an auditor's expert without shifting responsibility for the opinion; the AICPA's Digital Assets Practice Aid (first issued 2019, updated since) is the standard nonauthoritative reference, and the PCAOB has repeatedly flagged competence, over-reliance on exchange evidence and fraud risk in crypto-related audits. California sets no separate digital-asset audit standard — GAAS governs, with licensure and discipline under the California Board of Accountancy (evidence grade B).

> Personal study notes only; not tax or accounting advice. Sources: AICPA AU-C 500, 501, 505, 540, 620, 402, 315, 330; AICPA Digital Assets Practice Aid; PCAOB inspection observations on crypto-asset audits; FASB ASC 350-60 and ASC 820.

## Español (traducción de estudio)

Auditar activos digitales exige probar primero tres afirmaciones. **Existencia**: los activos a la fecha del balance deben vincularse a direcciones concretas de la cadena y a cuentas de custodia, no a una hoja de cálculo de la dirección. **Derechos**: el control sigue a las claves privadas: quien controla las claves, o suficientes partes de un esquema multifirma, puede disponer de los activos; lo depositado en un exchange es, en cambio, un crédito contra ese exchange y se evalúa aparte. La **integridad** es lo más difícil: un mismo controlador puede tener infinitas direcciones seudónimas, y las bifurcaciones, airdrops y recompensas de staking no tienen documentos de contraparte. La evidencia de control es demostrativa, nunca por entrega: el cliente firma un mensaje aleatorio del auditor con la clave de la billetera y el auditor verifica la firma contra la dirección pública, o mueve un importe mínimo en cadena; el auditor jamás debe pedir ni guardar la frase semilla ni la clave privada completa. Los saldos se capturan por altura de bloque o marca temporal a la fecha de cierre, con trabajo de corte.

En custodia de terceros, la confirmación de la AU-C 505 falla a menudo en la práctica —muchos exchanges no responden— y se recurre a accesos observados, cruce de direcciones de depósito en cadena y prueba de flujos posteriores; el informe SOC 1 o SOC 2 Tipo II del custodio se usa bajo el marco de la AU-C 402 y prueba los controles del custodio, no la cantidad de activos del cliente, y la llamada prueba de reservas, que suele omitir los pasivos, no es una auditoría ni da seguridad razonable. La valoración con el modelo de valor razonable de ASC 350-60 usa la cotización del mercado principal: **ejemplo**, 2 BTC a 95.000 más 10 ETH a 3.200 dan 190.000 + 32.000 = 222.000 dólares, y la conciliación de cantidades —6 BTC en el exchange más 4 BTC en billetera fría igual a 10 BTC (10 × 95.000 = 950.000)— precede a cualquier aceptación del importe. Los tokens ilíquidos activan la AU-C 540 y los expertos de la AU-C 620. Los anclajes normativos son la AU-C 500, el marco de la AU-C 501, la AU-C 620, la guía práctica no autoritativa de activos digitales de la AICPA (2019, actualizada) y las observaciones de inspección de la PCAOB sobre competencia y riesgo de fraude. California no tiene norma propia de auditoría de activos digitales: rigen las GAAS (grado de evidencia B).

> Notas personales de estudio; no constituyen asesoría fiscal ni contable. Fuentes: AICPA AU-C 500, 501, 505, 540, 620, 402; AICPA Digital Assets Practice Aid; PCAOB; FASB ASC 350-60 y ASC 820.

## 한국어 (초역, 원어민 감수 대기)

디지털 자산을 감사할 때는 평가에 들어가기 전에 세 가지 경영자주장부터 입증해야 합니다. **실재성**: 보고일 현재 자산은 관리자가 만든 표가 아니라 구체적인 블록체인 주소와 수탁 계좌에 연결되어야 합니다. **권리**: 통제는 개인키를 따라갑니다. 개인키, 또는 다중서명 구조의 충분한 몫을 통제하는 쪽이 자산을 처분할 수 있다고 추정되며, 거래소에 맡긴 자산은 그 거래소에 대한 청구권으로 바뀌어 따로 평가합니다. **완전성**이 가장 어렵습니다. 한 통제자가 익명 주소를 얼마든지 만들 수 있고, 포크·에어드롭·스테이킹 보상에는 상대방 서류가 없습니다. 통제 증거는 넘겨받는 방식이 아니라 보여 주는 방식입니다. 고객이 감사인이 준 무작위 메시지에 지갑 키로 서명하면 감사인은 공개 주소로 그 서명을 검증하고, 아주 적은 금액을 온체인으로 옮겨 보게 할 수도 있습니다. 감사인이 시드 문구나 개인키 전문을 요구하거나 보관해서는 절대 안 됩니다. 잔액은 보고일 기준 블록 높이나 타임스탬프로 확정하고 마감 전후를 검증합니다.

제3자 수탁에서는 AU-C 505의 확인조회가 실무에서 자주 막힙니다. 많은 거래소가 회신하지 않으므로, 감사인이 지켜보는 가운데 로그인해 자료를 받고, 온체인 입금 주소와 대조하고, 기말 후 흐름을 검증하는 대체 절차를 씁니다. 수탁기관의 SOC 1 또는 SOC 2 Type II 보고서는 AU-C 402의 틀에서 평가하며, 이는 수탁기관의 통제를 증명할 뿐 고객 자산의 수량을 증명하지 않습니다. 부채를 보통 빼는 이른바 보유고 증명(proof of reserves)은 감사가 아니며 합리적 확신을 주지 않습니다. 평가는 ASC 350-60의 공정가치 모형에서 주시장 가격을 씁니다. **예시:** BTC 2개 곱하기 95,000달러에 ETH 10개 곱하기 3,200달러를 더하면 190,000 + 32,000 = 222,000달러이고, 거래소 6개 + 콜드월렛 4개 = 10개라는 수량 대사가 금액을 받아들이기 전에 먼저 맞아야 합니다(10 × 95,000 = 950,000달러). 비유동 토큰에는 AU-C 540의 추정 감사와 AU-C 620의 전문가 활용이 붙습니다. 기준의 닻은 AU-C 500, AU-C 501의 특정 항목 틀, AU-C 620이며, AICPA의 Digital Assets Practice Aid(2019년 첫 발행, 이후 갱신)는 비권위적 실무 참고자료이고, PCAOB는 암호자산 감사에서 적격성, 거래소 증거에 대한 과도한 의존, 부정 위험을 반복해서 지적해 왔습니다. 캘리포니아에는 별도의 디지털 자산 감사 기준이 없고 GAAS를 따릅니다(증거 등급 B). (초역, 원어민 감수 대기)

> 개인 학습 노트이며 세무·회계 자문이 아닙니다. 출처: AICPA AU-C 500, 501, 505, 540, 620, 402; AICPA Digital Assets Practice Aid; PCAOB; FASB ASC 350-60, ASC 820.

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

Kiểm toán tài sản số phải chứng minh ba khẳng định trước khi bàn đến định giá. **Hiện hữu**: tài sản tại ngày báo cáo phải gắn với địa chỉ blockchain và tài khoản lưu ký cụ thể, không phải bảng tính của ban quản lý. **Quyền**: quyền kiểm soát đi theo khóa riêng — bên kiểm soát khóa riêng, hoặc đủ phần trong cơ chế đa chữ ký, mới được suy định là có thể định đoạt tài sản; tài sản gửi trên sàn là khoản phải đòi đối với sàn đó và phải đánh giá riêng. **Đầy đủ** là khẳng định khó nhất: một bên kiểm soát có thể có vô số địa chỉ ẩn danh, còn fork, airdrop và phần thưởng staking không có chứng từ đối tác. Bằng chứng kiểm soát mang tính trình diễn, không phải bàn giao: khách hàng ký một thông điệp ngẫu nhiên do kiểm toán viên đưa bằng khóa ví và kiểm toán viên xác minh chữ ký với địa chỉ công khai, hoặc chuyển một khoản rất nhỏ trên chuỗi; kiểm toán viên tuyệt đối không được yêu cầu hay giữ cụm từ hạt giống hay toàn bộ khóa riêng. Số dư được chốt theo chiều cao khối hoặc dấu thời gian tại ngày báo cáo, kèm kiểm tra khóa sổ.

Với lưu ký bên thứ ba, thư xác nhận theo AU-C 505 thường thất bại trong thực tế vì nhiều sàn không trả lời, nên kiểm toán viên dùng thủ tục thay thế: quan sát khách hàng đăng nhập lấy số, đối chiếu địa chỉ nạp tiền trên chuỗi và kiểm tra dòng tiền sau kỳ; báo cáo SOC 1 hoặc SOC 2 Type II của bên lưu ký được đánh giá theo khung AU-C 402 và chỉ chứng minh kiểm soát của bên lưu ký, không chứng minh số lượng tài sản của khách hàng, còn «bằng chứng dự trữ» thường bỏ qua phía nợ phải trả thì không phải kiểm toán và không cho bảo đảm hợp lý. Định giá theo mô hình giá trị hợp lý của ASC 350-60 dùng giá thị trường chính: **ví dụ**, 2 BTC nhân 95.000 cộng 10 ETH nhân 3.200 bằng 190.000 + 32.000 = 222.000 đô la, và việc đối chiếu số lượng — 6 BTC trên sàn cộng 4 BTC trong ví lạnh bằng 10 BTC (10 × 95.000 = 950.000) — phải khớp trước khi chấp nhận bất kỳ con số nào. Token kém thanh khoản kéo theo kiểm toán ước tính AU-C 540 và chuyên gia AU-C 620. Các neo chuẩn mực là AU-C 500, khung AU-C 501, AU-C 620, tài liệu thực hành không có tính bắt buộc về tài sản số của AICPA (ban hành 2019, cập nhật sau đó) và các quan sát thanh tra của PCAOB về năng lực và rủi ro gian lận. California không có chuẩn mực kiểm toán tài sản số riêng — GAAS vẫn áp dụng (cấp bằng chứng B). (Bản dịch sơ bộ, chờ hiệu đính)

> Ghi chú học tập cá nhân, không phải tư vấn thuế hay kế toán. Nguồn: AICPA AU-C 500, 501, 505, 540, 620, 402; AICPA Digital Assets Practice Aid; PCAOB; FASB ASC 350-60, ASC 820.

## हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

डिजिटल संपत्तियों की ऑडिट में मूल्यांकन से पहले तीन दावे सिद्ध करने होते हैं। **अस्तित्व**: रिपोर्टिंग तिथि की संपत्तियाँ प्रबंधन की स्प्रेडशीट से नहीं, ठोस ब्लॉकचेन पतों और संरक्षक खातों से जुड़ी होनी चाहिए। **अधिकार**: नियंत्रण निजी कुंजियों के साथ चलता है — जो पक्ष कुंजियाँ, या बहु-हस्ताक्षर व्यवस्था का पर्याप्त हिस्सा, नियंत्रित करता है वही संपत्ति का निपटान कर सकता है; एक्सचेंज पर रखी संपत्ति उस एक्सचेंज के विरुद्ध दावा बन जाती है और अलग से मूल्यांकित होती है। **पूर्णता** सबसे कठिन दावा है: एक ही नियंत्रक के पास असीम छद्मनाम पते हो सकते हैं, और फ़ोर्क, एयरड्रॉप व स्टेकिंग पुरस्कारों के कोई प्रतिपक्ष दस्तावेज़ नहीं होते। नियंत्रण का साक्ष्य प्रदर्शनात्मक होता है, सुपुर्दगी वाला नहीं: ग्राहक ऑडिटर के दिए यादृच्छिक संदेश पर वॉलेट कुंजी से हस्ताक्षर करता है और ऑडिटर सार्वजनिक पते से हस्ताक्षर सत्यापित करता है, या शृंखला पर बहुत छोटी राशि भेजता है; ऑडिटर को सीड वाक्यांश या पूरी निजी कुंजी कभी माँगनी या रखनी नहीं चाहिए। शेष रिपोर्टिंग तिथि के ब्लॉक-ऊँचाई या समय-मुहर पर तय किए जाते हैं और कट-ऑफ़ जाँच होती है।

तृतीय-पक्ष संरक्षण में AU-C 505 की पुष्टि व्यवहार में अक्सर विफल रहती है — कई एक्सचेंज उत्तर नहीं देते — इसलिए देखी हुई लॉग-इन प्रक्रिया, ऑन-चेन जमा पतों का मिलान और अवधि-पश्चात प्रवाह परीक्षण जैसे वैकल्पिक उपाय अपनाए जाते हैं; संरक्षक की SOC 1 या SOC 2 Type II रिपोर्ट AU-C 402 ढाँचे में मूल्यांकित होती है और वह संरक्षक के नियंत्रणों को सिद्ध करती है, ग्राहक की संपत्ति की मात्रा को नहीं, और आमतौर पर देयताओं को छोड़ देने वाला तथाकथित proof of reserves ऑडिट नहीं है और कोई उचित आश्वासन नहीं देता। ASC 350-60 के उचित-मूल्य मॉडल में मूल्यांकन प्रधान बाज़ार के भाव से होता है: **उदाहरण** — 2 BTC गुणा $95,000 जमा 10 ETH गुणा $3,200 बराबर 190,000 + 32,000 = $222,000, और मात्रा-मिलान — एक्सचेंज पर 6 BTC जमा कोल्ड वॉलेट में 4 BTC बराबर 10 BTC (10 × $95,000 = $950,000) — किसी भी राशि को स्वीकार करने से पहले मेल खाना चाहिए। तरलताहीन टोकन AU-C 540 के अनुमान-ऑडिट और AU-C 620 के विशेषज्ञों को खींच लाते हैं। मानक-आधार हैं AU-C 500, AU-C 501 का ढाँचा, AU-C 620, AICPA की ग़ैर-प्रामाणिक Digital Assets Practice Aid (2019 में प्रथम, बाद में अद्यतन) और योग्यता व धोखाधड़ी-जोखिम पर PCAOB की निरीक्षण टिप्पणियाँ। कैलिफ़ोर्निया का कोई अलग डिजिटल-संपत्ति ऑडिट मानक नहीं है — GAAS ही लागू होता है (साक्ष्य स्तर B)। (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

> व्यक्तिगत अध्ययन नोट; कर या लेखांकन सलाह नहीं। स्रोत: AICPA AU-C 500, 501, 505, 540, 620, 402; AICPA Digital Assets Practice Aid; PCAOB; FASB ASC 350-60, ASC 820.
