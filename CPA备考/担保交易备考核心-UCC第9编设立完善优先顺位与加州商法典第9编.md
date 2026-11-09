# 担保交易备考核心：UCC 第 9 编的设立、完善、优先顺位与加州商法典第 9 编

> 个人学习笔记，不构成法律或会计建议。本文以《统一商法典》（Uniform Commercial Code, UCC）第 9 编与加州《商法典》（California Commercial Code）第 9 编（Division 9）为纲，条号以现行官方文本为准；REG 商法部分的担保交易题，先把「设立—完善—优先」这条链子走通，再看例外。

## 中文主文

REG 里担保交易的分最好拿也最容易丢：题目往往只给三四个日期和两三个债权人，问谁先受偿。诀窍是把每个债权人都放回同一条时间线上——先问担保权益设立（attachment）没有，再问完善（perfection）没有、哪天完善的，最后才套优先规则。下面按这条链子拆。

### 一、适用范围与排除：先看担保物是不是第 9 编的菜

- **管什么**：UCC § 9-109(a) 管动产与附着物（fixtures）上的、依合意创设的担保权益（secured transaction），不问交易叫什么名字——名为买卖、实为担保融资的，照样进第 9 编。担保物分类是全篇的地基：货物（goods，又分消费品 consumer goods、库存 inventory、设备 equipment、农产品 farm products）、动产文据（chattel paper）、票据（instruments）、投资财产（investment property）、信用证权利、一般无形财产（general intangibles）与账户（accounts）等，分类错，后面的完善方式与优先规则全错。
- **不管什么**：§ 9-109(c)、(d) 排掉一串——不动产本身的权益（土地抵押另走不动产法，附着物部分除外）、联邦法优先管辖的领域（如联邦登记的飞机、船舶、版权中部分登记事项以联邦法为准）、工资索赔转让、侵权索赔（商业性侵权索赔除外）、消费者存款账户等。考试最爱埋的是「工资债权的转让不适用第 9 编」与「土地本身不适用」这两格。

### 二、设立 attachment：三要件齐了，权益才在当事人之间生效

§ 9-203 的三要件，缺一不可：①**价值**（value）已给付——贷款、赊销、既存债务都算；②**债务人对担保物有权利**（rights in the collateral）或有处分权——拿别人的东西设保，权益贴不上去；③**证据要件**三选一：债务人已认证（authenticate）一份描述担保物的担保协议（security agreement），或者担保物由担保权人**占有**（possession），或者对依法可控制的担保物已取得**控制**（control，如投资财产、存款账户）。三要件最后齐备的那一刻，担保权益设立完成（enforceable）。设立只解决「你我之间有效」，对第三人排第几，要看完善。

### 三、完善 perfection：四条路，选错路等于没完善

担保权益设立后还要完善，才对后来的债权人、留置权人和买方站得住。四条路：

- **提交融资声明**（filing）：向指定机关提交 UCC-1 融资声明，是大多数担保物的默认路。声明只须给出债务人与担保权人名称、担保物指示（indication），不要求附担保协议全文；债务人名称写错到「严重误导」（seriously misleading）的程度则声明无效——名称题是高频送分点。
- **占有**（perfection by possession，§ 9-313）：票据、动产文据、有形担保物等可由担保权人实际占有而完善；钱（money）原则上只能靠占有完善。
- **控制**（perfection by control，§ 9-314）：存款账户只能靠控制完善（§ 9-312(b)(1)），投资财产、信用证权利、电子动产文据也可走控制；存款账户「只能控制、不能提交」是必考点。
- **自动完善**（automatic perfection，§ 9-309）：设立即完善，不用做任何动作——最典型是消费品上的购买价款担保权益（purchase-money security interest, PMSI）；小额账户或一般无形财产的出售等也有自动完善格。

### 四、优先顺位总规则：三句口诀先背死

- **完善对未完善**：已完善的担保权益优先于未完善的（§ 9-322(a)(2) 对 (a)(3) 的结构）。
- **完善对完善**：谁先提交或先完善，谁优先（first to file or perfect，§ 9-322(a)(1)）——注意是「提交」与「完善」取其早：先提交、后设立完善的，优先时点可以回溯到提交日。
- **未完善对未完善**：先设立者优先（§ 9-322(a)(3)）。
- **留置权债权人**（lien creditor，如胜诉后取得司法留置权的普通债权人、破产受托人拟制的这一身份）：担保权益在其成为留置权债权人之前已完善的，担保权人赢；未完善的输给先成为留置权债权人的人（§ 9-317）。破产题里受托人能推翻的，正是未完善的那批。

### 五、PMSI 超级优先：分三档，条件一档比一档严

PMSI 是为「卖东西或借钱给债务人买这件东西」的那位债权人设的后发先至通道（§ 9-324），但三档条件差别很大，是全章最爱考的辨析：

- **消费品 PMSI**：自动完善，不用提交、不用通知，即可取得超级优先——但注意，对消费品的「车库买卖」买方另有 § 9-320(b) 的无负担取得规则，担保权人想挡住转售，常主动提交。
- **库存 PMSI**：条件最严，缺一不可——①须已完善（提交），且②在债务人取得占有之前已提交，③还须向已就同一库存提交在先的冲突担保权人发出经认证的通知（notification），且该通知须在债务人取得占有之前被收到，并说明自己将就何种库存享有 PMSI。少了通知这一步，超级优先落空，只能回普通「先提交」队列。
- **非库存、非消费品（如设备）PMSI**：债务人取得占有后 **20 天内**完善即可回溯取得超级优先，不要求事先通知在先提交人。20 天从债务人「取得占有」起算，不是签约日、不是发货日。

### 六、普通交易买方：在先留置与附着物的两条支线

- **普通交易进程买方**（buyer in ordinary course of business, BIOCB，§ 9-320(a)）：从卖货的人手里、按其通常卖法买走货物的人，即使知道担保权益存在，也无负担取得（卖方自己创设的担保权益挡不住他）。边界：买方须善意、不知该买卖违反担保协议，且卖方须是卖这类货的人——买库存找库存商买，才对味。
- **司法在先留置权**：见第四节 § 9-317 的时序赛跑。
- **附着物 fixture filing（§ 9-334）**：货物嵌进不动产变附着物后，与不动产业主、抵押权人的优先之争单设规则——在县级不动产登记处作附着物提交（fixture filing），且时点卡得巧（如在成为附着物后 20 天内提交、或附着物 PMSI 的专门窗口），可以赢过先在的不动产权益；晚了，就排在先登记的不动产权益之后。

### 七、担保物处置与价款 proceeds：权益会跟着钱走

- **Proceeds（§ 9-315）**：担保物被卖、租、许可或以其他方式处置时，担保权益原则上继续附在担保物上（除非担保权人授权无负担处置），并自动附到可识别的价款（proceeds）——现金、支票、换来的新物。原担保物已完善的，价款上的完善可延续 20 天，之后要靠「同一机关可提交且价款源自已提交声明覆盖的担保物」等条件接续，或及时补提交。
- **处置规则**：违约后担保权人可以出售担保物抵债，售得先冲合理处置费用与债务，余款（surplus）归债务人，不足（deficiency）原则上仍可向债务人追（消费者交易另有州法限制）。

### 八、违约救济 Part 6：能拿、能卖，但不能闹

- **和平取得占有**：违约后担保权人可不经法院程序自行取回担保物，但不得**破坏和平**（breach of the peace，§ 9-609）——破门、肢体冲突、债务人当场明确反对后仍强行拖走，都可能越线；越线就走司法程序（如 replevin）。
- **商业上合理的处置**（commercially reasonable disposition，§ 9-610）：处置的方式、方法、时间、地点、条款，每一面都要商业上合理；有公认市场的担保物按市场行情卖，是最稳的答卷。
- **通知**（§ 9-611 至 § 9-614）：处置前须向债务人及法定一串利害关系人发出合理的事前通知（非消费者交易看 § 9-613 的内容清单，消费者货物交易看 § 9-614 的更细清单）；通知不合理或处置不合理，受偿顺序与欠额追索都会被 § 9-626 一类规则反噬。
- **赎回权**（redemption，§ 9-623）：债务人在处置完成前付清全部担保债务与合理费用，可赎回担保物。

### 九、贯穿算例：两个日期计算（本地两遍复算）

**算例一（设备 PMSI 的 20 天宽限）**：经销商 3 月 1 日与买方签担保协议，买方 **2027 年 3 月 3 日**取得一台设备的占有，卖方经销商的 PMSI 于同日设立。宽限期自取得占有日起算 20 天：3 月 3 日加 20 天等于 **3 月 23 日**。复算：3 月 3 日之后第 20 天——3 月 4 日为第 1 天，3 月 23 日恰为第 20 天，一致。经销商只要在 2027 年 3 月 23 日（含当日）前提交融资声明完善，即取得对在先「全部资产」提交人的超级优先；拖到 3 月 24 日才提交，超级优先落空，只能按普通规则以 3 月 24 日的提交时点与在先提交人比先后。

**算例二（库存 PMSI 的时点赛跑）**：银行 2026 年 11 月 2 日已就零售商「全部库存」提交融资声明在先。供应商拟就一批新库存享 PMSI：2027 年 3 月 1 日提交自己的融资声明，同日向银行发出经认证的 PMSI 通知并经银行当日收到，零售商 **3 月 5 日**才取得这批库存的占有——提交与通知均在取得占有之前完成，超级优先成立，供应商就这批库存排在银行之前。反事实：若通知拖到 3 月 6 日（占有之后）才到，通知要件落空，供应商即使 3 月 1 日已提交，也只能回到 § 9-322 的普通队列，排在 2026 年 11 月 2 日先提交的银行之后。两个算例的结论都只卡在日期先后上，这正是 REG 的出题方式。

### 十、加州口径：Division 9 与集中提交

- **法典位置**：加州没有另起炉灶，其担保交易法就是加州《商法典》**第 9 编（Division 9，§ 9101 起）**，条号与 UCC 对应（UCC § 9-324 对应加州 § 9324，余类推）。
- **提交机关**：融资声明向**州务卿（Secretary of State）集中提交**（central filing），不是逐县提交；附着物提交等法定例外才落到不动产所在县的登记处。
- **备考提示**：题目给加州背景时，规则结构照 UCC 走，只把「提交去哪儿」换成州务卿、条号前面加个 9 即可；消费品交易中的欠额追索与通知细节，加州另有消费者保护成文法叠加，考场以题干给定为准。

> 个人学习笔记，不构成法律或会计建议。担保文件的实际提交与优先顺位判断，请结合现行 UCC 与加州商法典原文及专业人士意见处理。

## English

Secured transactions under UCC Article 9 turn on one chain: attachment, perfection, priority. Article 9 (section 9-109) covers consensual security interests in personal property and fixtures, whatever the deal is called, and excludes among other things interests in land itself, assignments of wage claims, and most tort claims. **Attachment** (section 9-203) needs three things: value given, the debtor's rights in the collateral, and an authenticated security agreement describing the collateral — or the secured party's possession or control. **Perfection** comes four ways: filing a UCC-1 financing statement (debtor-name errors that are seriously misleading kill it), possession (the only route for money), control (the only route for deposit accounts, section 9-312(b)(1)), and automatic perfection, classically for a purchase-money security interest (PMSI) in consumer goods.

**Priority** follows three sentences: perfected beats unperfected; between perfected interests, first to file or perfect wins (section 9-322(a)(1)), with the clock reaching back to an earlier filing; between unperfected interests, first to attach wins. A lien creditor (section 9-317) beats an interest not yet perfected when the lien arises. **PMSI superpriority** (section 9-324) has three tiers: consumer-goods PMSI is automatically perfected; inventory PMSI must be perfected by filing **and** an authenticated notification must reach conflicting inventory filers **before** the debtor receives possession; other PMSI gets a 20-day grace period after the debtor receives possession, with no notice requirement. A buyer in ordinary course (section 9-320(a)) takes free of a security interest created by the seller. Fixture priority is handled by fixture filings under section 9-334. On disposition, the interest follows identifiable proceeds (section 9-315, with a 20-day perfection bridge), and Part 6 remedies allow self-help repossession only without a breach of the peace (section 9-609), require a commercially reasonable disposition (section 9-610) with reasonable advance notification (sections 9-611 to 9-614), and preserve redemption (section 9-623).

**Worked dates (recomputed twice).** A dealer PMSI attaches when the buyer receives possession of equipment on March 3, 2027; March 3 plus 20 days is March 23, 2027, so filing on or before March 23 earns superpriority, and filing March 24 does not. For inventory: a bank filed against all inventory on November 2, 2026; a supplier that files and delivers its authenticated PMSI notice on March 1, 2027, before the debtor receives possession on March 5, wins superpriority in that inventory; notice arriving March 6 defeats the claim and the supplier queues behind the bank under the ordinary first-to-file rule. California enacts Article 9 as Division 9 of its Commercial Code (section 9101 et seq.), with central filing of financing statements with the Secretary of State.

> Personal study notes only; not legal or accounting advice.

## Español (traducción de estudio)

Las operaciones garantizadas del Artículo 9 del UCC siguen una cadena: constitución (attachment), perfeccionamiento y prioridad. Rige los gravámenes consensuales sobre bienes muebles y accesorios fijos (§ 9-109), con exclusiones como el suelo mismo o la cesión de créditos salariales. La **constitución** (§ 9-203) exige contraprestación (value), derechos del deudor sobre el bien y un acuerdo de garantía autenticado — o posesión o control del acreedor. El **perfeccionamiento** va por cuatro vías: presentación de la declaración de financiación UCC-1, posesión (única vía para el dinero), control (única vía para cuentas de depósito, § 9-312(b)(1)) y perfeccionamiento automático, típico del gravamen por precio de compra (PMSI) en bienes de consumo.

**Prioridad**: el perfeccionado vence al no perfeccionado; entre perfeccionados gana quien primero presentó o perfeccionó (§ 9-322(a)(1)); entre no perfeccionados, quien primero se constituyó. El acreedor con gravamen judicial (§ 9-317) vence al interés aún no perfeccionado. La **superprioridad PMSI** (§ 9-324) tiene tres niveles: en bienes de consumo es automática; en **inventario** exige presentación y notificación autenticada recibida por los acreedores en conflicto **antes** de que el deudor tome posesión; en los demás bienes hay un plazo de gracia de **20 días** desde la posesión, sin notificación. El comprador en el curso ordinario (§ 9-320(a)) adquiere libre del gravamen creado por su vendedor; los accesorios fijos se rigen por la presentación especial del § 9-334 y el producto de la enajenación por el § 9-315. Los remedios de la Parte 6 prohíben alterar el orden público al recuperar el bien (§ 9-609), exigen una disposición comercialmente razonable (§ 9-610) con notificación previa (§§ 9-611 a 9-614) y conservan el rescate (§ 9-623).

**Fechas del ejemplo (recalculadas dos veces).** Posesión de un equipo el 3 de marzo de 2027: 3 de marzo más 20 días = 23 de marzo de 2027, último día para la superprioridad. En inventario, con presentación bancaria previa del 2 de noviembre de 2026, el proveedor que presenta y notifica el 1 de marzo de 2027, antes de la posesión del 5 de marzo, gana; si la notificación llega el 6 de marzo, pierde y queda detrás del banco. En California, el Artículo 9 es la División 9 del Código Comercial (§ 9101 y siguientes), con presentación centralizada ante el Secretario de Estado.

> Notas personales de estudio; no constituyen asesoría legal ni contable.

## 한국어 (초역, 원어민 감수 대기)

UCC 제9편 담보거래는 설정(attachment)—완전화(perfection)—우선순위라는 한 줄기로 정리됩니다. 제9편(§ 9-109)은 동산과 정착물에 대한 합의 담보권을 다루며, 토지 자체의 권리나 임금채권 양도 등은 제외됩니다. **설정**(§ 9-203)에는 세 가지가 필요합니다. 대가(value)가 주어졌을 것, 채무자가 담보물에 권리를 가질 것, 그리고 담보물을 기술한 인증된 담보계약이 있거나 채권자가 점유 또는 통제(control)를 가질 것입니다. **완전화**는 네 길입니다. UCC-1 금융명세서 제출(filing), 점유(현금은 이 길뿐), 통제(예금계좌는 이 길뿐, § 9-312(b)(1)), 그리고 소비재 구매대금담보권(PMSI)처럼 설정과 동시에 이뤄지는 자동 완전화입니다.

**우선순위**는 세 문장입니다. 완전화된 권리가 미완전화 권리에 앞서고, 완전화된 권리끼리는 먼저 제출하거나 먼저 완전화한 쪽이 이기며(§ 9-322(a)(1)), 미완전화끼리는 먼저 설정된 쪽이 앞섭니다. 유치권 채권자(§ 9-317)는 유치권 발생 시점에 아직 완전화되지 않은 권리에 앞섭니다. **PMSI 최우선순위**(§ 9-324)는 세 등급입니다. 소비재 PMSI는 자동 완전화됩니다. **재고 PMSI**는 제출로 완전화해야 하고, 채무자가 점유를 취득하기 **전에** 경합하는 선행 제출권자에게 인증된 통지가 도달해야 합니다. 그 밖의 PMSI는 점유가 시작된 뒤 **20일**의 유예가 있으며 사전 통지는 필요 없습니다. 통상 거래 과정의 매수인(§ 9-320(a))은 매도인이 설정한 담보권 부담 없이 취득하고, 정착물은 § 9-334의 정착물 제출, 처분 대금은 § 9-315를 따릅니다. 제6부의 구제는 평화 파괴 없는 자력 회수(§ 9-609), 상업적으로 합리적인 처분(§ 9-610)과 사전 통지(§§ 9-611–9-614), 상환권(§ 9-623)을 핵심으로 합니다.

**날짜 예시(두 번 재계산).** 장비 점유가 2027년 3월 3일에 시작되면 3월 3일 더하기 20일은 3월 23일이며, 이날까지 제출해야 최우선순위를 얻고 3월 24일 제출은 늦습니다. 재고에서는 은행이 2026년 11월 2일에 먼저 제출한 상태에서, 공급자가 2027년 3월 1일에 제출과 통지를 마치고 채무자 점유가 3월 5일이면 공급자가 이기고, 통지가 3월 6일에 도착하면 져서 은행 뒤에 섭니다. 캘리포니아에서는 제9편이 상법전 제9편(Division 9, § 9101 이하)이며 금융명세서는 주무장관에게 집중 제출합니다.

> 개인 학습 노트이며 법률·회계 자문이 아닙니다. (초역, 원어민 감수 대기)

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

Giao dịch bảo đảm theo Chương 9 UCC đi theo một chuỗi: xác lập (attachment) — hoàn thiện (perfection) — thứ tự ưu tiên. Chương 9 (§ 9-109) điều chỉnh quyền bảo đảm theo thỏa thuận trên động sản và vật gắn liền, loại trừ như quyền trên chính đất đai hay chuyển nhượng tiền lương. **Xác lập** (§ 9-203) cần ba yếu tố: đã trao giá trị (value), người nợ có quyền trên tài sản bảo đảm, và có thỏa thuận bảo đảm đã xác thực mô tả tài sản — hoặc bên bảo đảm đã chiếm hữu hay kiểm soát. **Hoàn thiện** có bốn đường: nộp tờ khai tài trợ UCC-1, chiếm hữu (đường duy nhất cho tiền mặt), kiểm soát (đường duy nhất cho tài khoản tiền gửi, § 9-312(b)(1)), và hoàn thiện tự động, điển hình là quyền bảo đảm theo giá mua (PMSI) trên hàng tiêu dùng.

**Thứ tự ưu tiên** gói trong ba câu: đã hoàn thiện thắng chưa hoàn thiện; giữa các quyền đã hoàn thiện, ai nộp trước hoặc hoàn thiện trước thắng (§ 9-322(a)(1)); giữa các quyền chưa hoàn thiện, ai xác lập trước thắng. Chủ nợ có quyền lưu giữ tư pháp (§ 9-317) thắng quyền chưa hoàn thiện tại thời điểm lưu giữ phát sinh. **Siêu ưu tiên PMSI** (§ 9-324) có ba bậc: PMSI hàng tiêu dùng tự động hoàn thiện; PMSI trên **hàng tồn kho** phải nộp đơn hoàn thiện **và** thông báo đã xác thực phải đến tay các bên nộp đơn xung đột **trước khi** người nợ nhận chiếm hữu; PMSI khác có thời gian ân hạn **20 ngày** sau khi nhận chiếm hữu, không cần thông báo. Người mua trong quá trình kinh doanh thông thường (§ 9-320(a)) nhận hàng không vướng quyền bảo đảm do chính người bán tạo ra; vật gắn liền theo nộp đơn fixture § 9-334, tiền thu từ thanh lý theo § 9-315. Biện pháp Phần 6 chỉ cho tự thu hồi khi không phá vỡ hòa bình (§ 9-609), đòi thanh lý hợp lý về mặt thương mại (§ 9-610) kèm thông báo trước (§§ 9-611–9-614) và giữ quyền chuộc lại (§ 9-623).

**Ví dụ ngày tháng (đã tính lại hai lần).** Nhận chiếm hữu thiết bị ngày 3/3/2027: 3/3 cộng 20 ngày là 23/3/2027, nộp chậm nhất ngày này mới có siêu ưu tiên. Với hàng tồn kho, ngân hàng đã nộp ngày 2/11/2026; nhà cung cấp nộp đơn và gửi thông báo ngày 1/3/2027, trước ngày nhận chiếm hữu 5/3, thì thắng; thông báo tới ngày 6/3 thì thua và xếp sau ngân hàng. Tại California, Chương 9 là Division 9 của Bộ luật Thương mại (§ 9101 trở đi), tờ khai tài trợ nộp tập trung tại Secretary of State.

> Ghi chú học tập cá nhân, không phải tư vấn pháp lý hay kế toán. (Bản dịch sơ bộ, chờ hiệu đính)

## हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

UCC अनुच्छेद 9 के सुरक्षित लेन-देन एक ही शृंखला पर चलते हैं: संलग्नता (attachment) — पूर्णता (perfection) — प्राथमिकता। अनुच्छेद 9 (§ 9-109) चल संपत्ति और स्थावर-संलग्न वस्तुओं (fixtures) पर सहमतिपूर्ण प्रतिभूति हितों को नियंत्रित करता है; भूमि स्वयं के हित और वेतन-दावों का समनुदेशन जैसे विषय बाहर हैं। **संलग्नता** (§ 9-203) के लिए तीन चीज़ें चाहिए: मूल्य (value) दिया गया हो, देनदार के पास संपार्श्विक में अधिकार हों, और संपार्श्विक का वर्णन करने वाला प्रमाणित प्रतिभूति करार हो — या प्रतिभूत पक्ष के पास कब्ज़ा अथवा नियंत्रण हो। **पूर्णता** के चार रास्ते हैं: UCC-1 वित्तपोषण विवरण दाखिल करना, कब्ज़ा (धन के लिए एकमात्र रास्ता), नियंत्रण (जमा खातों के लिए एकमात्र रास्ता, § 9-312(b)(1)), और स्वतः पूर्णता — उपभोक्ता वस्तुओं पर क्रय-मूल्य प्रतिभूति हित (PMSI) इसका प्रसिद्ध उदाहरण है।

**प्राथमिकता** तीन वाक्यों में है: पूर्ण हित अपूर्ण से आगे; दो पूर्ण हितों में जो पहले दाखिल करे या पहले पूर्ण हो वह जीते (§ 9-322(a)(1)); दो अपूर्णों में जो पहले संलग्न हो। धारणाधिकार लेनदार (§ 9-317) उस हित से आगे रहता है जो उसके धारणाधिकार के समय तक पूर्ण न हुआ हो। **PMSI महा-प्राथमिकता** (§ 9-324) के तीन स्तर हैं: उपभोक्ता वस्तुओं का PMSI स्वतः पूर्ण होता है; **इन्वेंटरी PMSI** के लिए दाखिल करके पूर्ण करना होगा **और** प्रमाणित सूचना देनदार के कब्ज़ा लेने से **पहले** टकराव वाले पूर्व-दाखिलकर्ताओं तक पहुँचनी चाहिए; अन्य PMSI को कब्ज़े के बाद **20 दिन** की छूट मिलती है, सूचना आवश्यक नहीं। सामान्य व्यवसाय-क्रम का क्रेता (§ 9-320(a)) विक्रेता द्वारा सृजित प्रतिभूति हित से मुक्त होकर लेता है; fixtures के लिए § 9-334 का fixture filing और निपटान-राशि (proceeds) के लिए § 9-315 लागू होता है। भाग 6 के उपायों में शांति-भंग रहित स्व-सहायता कब्ज़ा (§ 9-609), वाणिज्यिक रूप से उचित निपटान (§ 9-610), पूर्व सूचना (§§ 9-611–9-614) और मोचन अधिकार (§ 9-623) प्रमुख हैं।

**तिथि उदाहरण (दो बार पुनर्गणना)।** उपकरण का कब्ज़ा 3 मार्च 2027 को मिला तो 3 मार्च जमा 20 दिन = 23 मार्च 2027; इसी तिथि तक दाखिल करने पर महा-प्राथमिकता मिलेगी। इन्वेंटरी में बैंक ने 2 नवंबर 2026 को पहले दाखिल किया था; आपूर्तिकर्ता 1 मार्च 2027 को दाखिल और सूचना पूरी करे और कब्ज़ा 5 मार्च को मिले तो आपूर्तिकर्ता जीतता है, सूचना 6 मार्च को पहुँचे तो वह हारकर बैंक के पीछे रहता है। कैलिफ़ोर्निया में अनुच्छेद 9 वहाँ के वाणिज्य संहिता का Division 9 (§ 9101 से आगे) है और वित्तपोषण विवरण Secretary of State के पास केंद्रीय रूप से दाखिल होते हैं।

> व्यक्तिगत अध्ययन नोट; कानूनी या लेखांकन सलाह नहीं। (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

## 补译增量（2026-11-09 追加：韩／越／印三语各补 2 项中文主文已有细节至对齐，正文原有段落未改动）

### 한국어 보충 (초역 · 初译待校)
- **대가(proceeds, § 9-315)와 처분 후 정산.** 담보물이 매각·임대·라이선스 등으로 처분되면 담보권은 원칙적으로 그 담보물에 계속 붙고, 식별 가능한 대가(proceeds)에도 자동으로 붙는다. 원래 담보물이 완성(perfection)되어 있었다면 대가에 대한 완성은 20일간 이어지며, 그 뒤에는 동일 기관에 제출할 수 있고 대가가 이미 제출된 명세서가 커버하는 담보물에서 비롯되었다는 등의 요건을 갖춰야 이어진다. 채무불이행 후 처분 대금은 합리적인 처분 비용과 채무에 먼저 충당되고, 잉여(surplus)는 채무자에게 돌아가며, 부족분(deficiency)은 원칙적으로 채무자에게 청구할 수 있다(소비자 거래에는 주법상 별도 제한이 있다).
- **부착물(fixture, § 9-334)과 통상 거래 매수인(§ 9-320(a))의 경계.** 물건이 부착물이 된 뒤 20일 이내에 부착물 제출(fixture filing)을 하는 등의 시점 창구 안에서는 먼저 있던 부동산 권리에 앞설 수 있다. 통상 거래 과정의 매수인(BIOCB)이 부담 없이 취득하려면 매도인이 그 종류의 물건을 파는 사람이어야 하고, 매수인이 선의이며 그 매매가 담보 계약을 위반한다는 사실을 몰라야 한다.

### Bổ sung Tiếng Việt (bản dịch sơ bộ · 初译待校)
- **Khoản thu từ việc xử lý tài sản bảo đảm (proceeds, § 9-315) và thanh toán sau xử lý.** Khi tài sản bảo đảm bị bán, cho thuê, cấp phép hoặc xử lý theo cách khác, quyền bảo đảm về nguyên tắc vẫn bám vào tài sản đó và tự động bám sang khoản thu có thể xác định được (proceeds). Nếu tài sản gốc đã được hoàn thiện (perfection), tình trạng hoàn thiện trên proceeds tiếp tục 20 ngày; sau đó phải đáp ứng các điều kiện như có thể nộp tại cùng cơ quan và proceeds phát sinh từ tài sản mà tờ khai đã nộp bao phủ thì mới tiếp tục được. Tiền bán sau vỡ nợ được trừ chi phí xử lý hợp lý và nợ trước, phần thừa (surplus) thuộc về con nợ, phần thiếu (deficiency) về nguyên tắc vẫn truy đòi con nợ (giao dịch tiêu dùng có giới hạn riêng theo luật bang).
- **Tài sản gắn liền (fixture, § 9-334) và người mua trong giao dịch thông thường (§ 9-320(a)).** Sau khi hàng hóa trở thành fixture, nếu nộp fixture filing trong vòng 20 ngày kể từ khi trở thành fixture thì trong cửa sổ thời điểm này có thể thắng quyền bất động sản đã có trước. Người mua trong quá trình kinh doanh thông thường (BIOCB) lấy tài sản không vướng quyền chỉ khi người bán là người bán loại hàng đó, người mua thiện chí và không biết việc mua bán vi phạm thỏa thuận bảo đảm.

### हिन्दी पूरक (प्रारंभिक अनुवाद · 初译待校)
- **प्राप्तियाँ (proceeds, § 9-315) और निपटान के बाद हिसाब.** संपार्श्विक बेचे जाने, किराए पर दिए जाने, लाइसेंस किए जाने या अन्यथा निपटाए जाने पर सुरक्षा हित सैद्धांतिक रूप से उस संपत्ति पर बना रहता है और पहचान-योग्य प्राप्तियों (proceeds) पर स्वतः लग जाता है। मूल संपत्ति परिपूर्ण (perfected) थी तो proceeds पर परिपूर्णता 20 दिन जारी रहती है; उसके बाद वही कार्यालय में दाखिल-योग्यता और proceeds का दाखिल विवरण से आच्छादित संपत्ति से उत्पन्न होना जैसी शर्तें पूरी होने पर ही निरंतरता मिलती है। चूक के बाद बिक्री राशि पहले उचित निपटान खर्च और ऋण में लगती है, अधिशेष (surplus) देनदार को मिलता है और कमी (deficiency) सैद्धांतिक रूप से देनदार से वसूली-योग्य रहती है (उपभोक्ता लेनदेन में राज्य-विधि की अलग सीमाएँ हैं)।
- **फ़िक्स्चर (fixture, § 9-334) और सामान्य व्यापार-क्रम क्रेता (§ 9-320(a)) की सीमा.** माल के fixture बन जाने के बाद, fixture बनने के 20 दिनों के भीतर fixture filing करने जैसे समय-खिड़की के भीतर पहले के अचल-संपत्ति हितों से आगे निकला जा सकता है। सामान्य व्यापार-क्रम क्रेता (BIOCB) तभी भार-मुक्त प्राप्त करता है जब विक्रेता उसी प्रकार का माल बेचने वाला हो, क्रेता सद्भाव में हो और उसे यह ज्ञात न हो कि बिक्री सुरक्षा करार का उल्लंघन करती है।
