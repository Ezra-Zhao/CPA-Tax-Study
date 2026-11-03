# 529 里的钱用不完怎么办：转 Roth、改受益人与剩余额处理及加州口径

> 个人学习笔记，不构成税务建议。条文以 IRC § 529 现行文本为准，年度金额以 IRS 当年公告为准。Personal study notes, not tax advice.

## 中文主文

### 一、先说清问题出在哪：529 的税惠是「专款专用」换来的

529 计划（IRC § 529 的合格学费计划）的好处是三段式的：缴款时联邦层面不给扣除（不少州给州税扣除或抵免，是州自己的事）；账户里增值不逐年计税；取出来花在合格高等教育费用上，收益部分也免税（§ 529(c)(3)(B)）。代价是这笔钱被「锁」在教育用途上。孩子拿了全额奖学金、决定不读大学、或者当年存多了，账户里就会剩下钱。剩余额的出口按代价从低到高大致四条：换受益人、扩围花掉、转进受益人的 Roth IRA、最后才是非合格取款硬退。本文逐条拆条件，重点放在 2024 年新开的转 Roth 通道。

先记住一个贯穿全篇的拆分：任何一笔 529 分配都按比例拆成本金与收益两部分（按账户整体的收益占比折算，凭计划发的 Form 1099-Q 看数）。本金是税后钱存进来的，取出不再计税；要算税、要算罚的，永远只有收益部分，别把「取款要交税」理解成整笔交税。

### 二、新出口：SECURE 2.0 第 126 条的 529 转 Roth IRA（§ 529(c)(3)(E)）

《SECURE 2.0 法案》（Pub. L. 117-328）第 126 条给 § 529 新增了 (c)(3)(E) 款：自 **2024 年 1 月 1 日**起（适用于 2023 年 12 月 31 日之后的分配），符合条件的 529 资金可直接转入受益人本人的 Roth IRA，转入部分不计所得税、也不加下文的 10% 附加税。门槛刻意设得窄，五道硬条件缺一不可：

1. **账户年龄满 15 年**：转入时，该 529 账户须已为该受益人维持至少 15 年。改过受益人后这 15 年怎么算，IRS 尚无最终指引，宜按重新起算的保守口径规划，以 IRS 现行指引为准。
2. **钱本身要「老」满 5 年**：只能转「转入日之前 5 年以前」已缴入的款项及其收益；最近 5 年内缴入的款项和这部分款项产生的收益，不在可转范围内。
3. **终身累计上限 35,000 美元**：按受益人个人算，从所有 529 账户转进 Roth IRA 的总额终身不得超过 35,000 美元。
4. **年度按 Roth 供款上限走**：每一年的转入额不得超过受益人当年的 Roth IRA 年度供款限额（2025 年为 7,000 美元，50 岁以上另有追补额度；2026 年为 7,500 美元，以 IRS 当年公告为准），且要减去受益人当年已经自己往 IRA 里存过的钱——转入额占用的是同一个年度额度，不是额外再给一份。
5. **受益人当年要有劳动收入**：转入额不得超过受益人当年的劳动收入（earned income）；且 Roth IRA 必须开在 **529 受益人本人**名下，不能转给账户所有人（通常是家长）自己的 Roth。程序上须由计划直接划转到 Roth IRA（trustee-to-trustee），不要先取到个人账户里再存。

有个容易记反的点：普通 Roth 供款的收入上限（MAGI 相位）**不适用于**这条转入通道——受益人收入再高，只要年度额度与劳动收入两条够，转入照走；而劳动收入这条又把还没工作的在校生挡在门外，所以这条路天然适合「孩子已经工作、529 还剩一截」的家庭，按一年一笔、数年转完的节奏走。

**算例（2025 年口径，已复算）**：某 529 账户 2010 年开立，2025 年已满 15 年；余额 52,000 美元，其中缴款 40,000 美元、收益 12,000 美元，最后一笔缴款在 2019 年，全部款项已满 5 年。受益人 24 岁，2025 年打工收入 9,000 美元，当年未自行供款 IRA。2025 年可转额 = min（年度限额 7,000，劳动收入 9,000）= **7,000 美元**，免税免罚转入其本人 Roth IRA。转完终身额度还剩 35,000 − 7,000 = 28,000 美元，按每年 7,000 美元的节奏还需 4 年转完（各年实际限额以当年公告为准）。对照：如果同一年改走非合格取款取出 10,000 美元，收益占比 = 12,000 ÷ 52,000 ≈ 23.08%，应税收益 = 10,000 × 12,000 ÷ 52,000 ≈ **2,307.69 美元**，另加 10% 附加税约 **230.77 美元**——同一笔剩余额，走 Roth 通道与硬退的代价差就摆在这里。

### 三、老出口一：改受益人给家里另一个人用

成本最低的出口往往是换人。§ 529(c)(5) 允许把受益人换成原受益人的家庭成员（定义在 § 529(e)(2)），换人本身不产生所得税。§ 529(e)(2) 的家庭成员范围比日常理解的「直系亲属」宽：配偶、子女及后代、兄弟姐妹、父母及直系尊亲属、侄甥、姻亲，以及上述人员的配偶等。实务排法：大宝剩下的转给二宝；孩子用不完的留给将来孙辈；甚至改回家长自己，留着读研。换人没有次数与金额上限，也不受 Roth 通道 35,000 美元封顶的影响，缺点只有一个：钱还是教育钱，家里没人再读书时它解决不了问题。

### 四、老出口二：把「合格支出」的范围用足

剩余额没想象中那么容易剩，因为合格高等教育费用（§ 529(e)(3)）的口径一直在扩：

- 研究生阶段的学费与必需费用，与本科同口径；
- 在劳动部注册备案的**学徒制（apprenticeship）**项目的费用、书本、用品与必需设备（§ 529(c)(8)）；
- **偿还学生贷款**：受益人本人（以及受益人的兄弟姐妹，各自独立计算）的合格教育贷款本金与利息，每人**终身**上限 10,000 美元（§ 529(c)(9)）——注意是终身额、不是每年 10,000；
- K-12 阶段学费另有年度上限口径（§ 529(c)(7)，近年立法有调整，具体金额以 IRS 现行公告为准）；
- 529 与 ABLE 之间另有结转通道，细则见本仓 ABLE 专篇。

先把家里现存的学生贷款按人头对一遍，再看换受益人，往往能消化掉相当一部分余额。

### 五、最后的出口：非合格取款，税只打在收益上、再加 10%

以上都用不掉，才轮到非合格取款。处理是固定三步：分配按比例拆本金与收益；本金免税退回；收益部分计入取款人当年普通收入，并按 § 529(c)(6) 再加 **10% 附加税**。四类情形免掉这 10%（所得税照交）：免税奖学金（奖学金额度内）、受益人死亡、残疾、就读美国军校类院校。第二节算例里那 230.77 美元就是这一罚的量级——它只打收益、不打本金，「硬退」远没有传言中可怕；真正的成本在收益部分的税率档位，尽量挑受益人收入低的年份分批取。

### 六、加州口径：联邦的出口都在，加州的税惠从来没有跟

加州在 529 上是出名的「不跟随」：其一，缴款没有州扣除或抵免；其二，加州未采纳联邦 § 529 的分配排除口径——联邦免税的合格分配，其收益部分在加州层面仍可能被计税，529 转 Roth 的转入额亦然：**加州未采纳该转入的免税处理，收益部分按非合格分配的思路在州税层面处理，具体以 FTB 现行指引为准**。所以加州家庭做第二节的规划时账要分两本算：联邦侧转 Roth 免税，加州侧先预留收益部分的州税成本，再决定节奏。

### 七、决策顺序清单

1. 先对人头：家里还有谁要读书、谁有学生贷款（每人 10,000 美元终身额）、谁符合 ABLE；
2. 能换受益人消化的先换（§ 529(c)(5)），零税成本；
3. 受益人已工作、账户满 15 年的，排转 Roth 的多年节奏表，年度限额、劳动收入、35,000 美元终身顶逐年核对；
4. 余下无教育用途的，按收益占比估算非合格取款的税与 10% 附加税，挑低收入年份分批取；
5. 留好 1099-Q 与开户、缴款年份记录，15 年与 5 年两个时钟靠记录说话。

*个人学习笔记，不构成税务建议。依据：IRC § 529（(c)(3)(B)、(c)(3)(E)、(c)(5)、(c)(6)、(c)(7)、(c)(8)、(c)(9)、(e)(2)、(e)(3)）；SECURE 2.0 Act（Pub. L. 117-328）§ 126；IRS Publication 970 与 529 计划问答；Roth IRA 年度限额 2025 年 7,000 美元、2026 年 7,500 美元（IRS 年度公告）；加州口径为 FTB 一般公开口径，转 Roth 的州税后果以 FTB 现行指引为准。算例已复算：min(7,000, 9,000) = 7,000；35,000 − 7,000 = 28,000；10,000 × 12,000 ÷ 52,000 ≈ 2,307.69，附加税 ≈ 230.77。*

---

## English

**Leftover 529 money: the Roth rollover, changing beneficiaries, and California.** A 529 plan (IRC § 529) shelters earnings only while the money stays on education: distributions for qualified higher education expenses exclude the earnings portion under § 529(c)(3)(B), and every distribution is split pro rata between basis (contributions, never taxed again) and earnings (the only part ever taxed or penalized).

**The Roth door — SECURE 2.0 § 126, codified at § 529(c)(3)(E), for distributions after December 31, 2023.** Five hard conditions: (1) the account must have been maintained for the beneficiary at least **15 years** (no final IRS guidance on whether a beneficiary change restarts this clock); (2) only contributions made **more than five years** earlier, plus their earnings, may move; (3) a **$35,000 lifetime cap** per beneficiary; (4) each year's rollover may not exceed that year's Roth IRA limit ($7,000 for 2025; $7,500 for 2026) minus the beneficiary's own IRA contributions that year — it consumes the same annual limit; and (5) **earned income** at least equal to the rollover, the Roth IRA in the **beneficiary's own** name, and a direct trustee-to-trustee transfer. The usual Roth MAGI phase-out does **not** apply here. Example (2025 figures, recomputed): an account opened in 2010 holds $52,000 — $40,000 of contributions, all made by 2019, and $12,000 of earnings. The beneficiary, 24, has $9,000 of earned income and made no IRA contributions. The 2025 rollover is min($7,000, $9,000) = **$7,000**, tax- and penalty-free, leaving $35,000 − $7,000 = $28,000 of lifetime capacity. By contrast, a $10,000 nonqualified withdrawal the same year would tax the earnings slice: $10,000 × 12,000 ÷ 52,000 ≈ **$2,307.69** of ordinary income, plus the 10% additional tax under § 529(c)(6), about **$230.77**.

**Changing the beneficiary (§ 529(c)(5))** to a member of the family of the old beneficiary — defined broadly in § 529(e)(2) — is tax-free, has no dollar cap, and is usually the first move. **Widened qualified uses** (§ 529(e)(3)) also absorb balances: graduate school, registered apprenticeship costs (§ 529(c)(8)), and student-loan repayment (§ 529(c)(9)) — a **$10,000 lifetime** cap per person, applying separately to the beneficiary and each sibling. **Nonqualified withdrawals** tax only the earnings portion as ordinary income plus the § 529(c)(6) 10% additional tax, waived (income tax still applies) for scholarships up to the award amount, death, disability, and U.S. military academy attendance. **California does not conform** to section 529: no state deduction, and no federal-style shelter for the earnings portion at the state level; for the Roth rollover California has not adopted the federal exclusion, so treat the earnings portion as state-taxed and confirm against current FTB guidance. *Personal study notes only; not tax advice.*

## Español (traducción de estudio, pendiente de revisión nativa)

**Dinero sobrante en un plan 529: traspaso a Roth, cambio de beneficiario y criterio de California.** El plan 529 (IRC § 529) protege los rendimientos solo mientras el dinero siga en educación: los retiros calificados excluyen los rendimientos según el § 529(c)(3)(B), y todo retiro se divide entre capital aportado (nunca vuelve a tributar) y rendimientos (la única parte gravable o penalizable). Salidas para un excedente, de menor a mayor costo: cambiar el beneficiario, usar la lista ampliada de gastos calificados, traspasar a la Roth IRA del beneficiario y, al final, retirar de forma no calificada.

**La vía Roth: SECURE 2.0 § 126, codificado en el § 529(c)(3)(E), para distribuciones posteriores al 31 de diciembre de 2023.** Cinco condiciones estrictas: (1) cuenta mantenida para el beneficiario al menos **15 años** (sin guía definitiva del IRS sobre el reinicio tras un cambio de beneficiario); (2) solo aportaciones hechas **más de cinco años** antes, con sus rendimientos; (3) tope **vitalicio de 35.000 dólares** por beneficiario; (4) el traspaso anual no supera el límite Roth IRA del año (7.000 dólares en 2025; 7.500 en 2026) menos las aportaciones propias del beneficiario a IRA ese año: consume el mismo límite; y (5) **ingresos laborales** del beneficiario al menos iguales al traspaso, Roth IRA **del propio beneficiario** y transferencia directa entre administradores. La reducción por MAGI de las aportaciones Roth ordinarias **no se aplica** aquí. Ejemplo (2025, recalculado): cuenta abierta en 2010 con 52.000 dólares — 40.000 de aportaciones, todas hasta 2019, y 12.000 de rendimientos. El beneficiario, de 24 años, tiene 9.000 dólares de ingresos laborales y no aportó a ninguna IRA. El traspaso de 2025 es min(7.000, 9.000) = **7.000 dólares**, libre de impuesto y de penalización, y deja 35.000 − 7.000 = 28.000 dólares de capacidad vitalicia. En cambio, un retiro no calificado de 10.000 dólares ese mismo año gravaría la parte de rendimientos: 10.000 × 12.000 ÷ 52.000 ≈ **2.307,69 dólares** de ingreso ordinario, más el impuesto adicional del 10 % del § 529(c)(6), unos **230,77 dólares**.

**Cambiar el beneficiario (§ 529(c)(5))** a un miembro de la familia del beneficiario anterior (§ 529(e)(2), definición amplia) es libre de impuestos, sin tope en dólares, y suele ser el primer paso. **Los usos calificados ampliados** (§ 529(e)(3)) también absorben saldos: posgrado, aprendizaje registrado (§ 529(c)(8)) y préstamos estudiantiles (§ 529(c)(9)), con tope **vitalicio de 10.000 dólares** por persona, por separado para el beneficiario y cada hermano. **El retiro no calificado** grava solo los rendimientos como ingreso ordinario más el 10 % adicional del § 529(c)(6), eximido (no así el impuesto sobre la renta) en caso de beca hasta su monto, fallecimiento, discapacidad o academia militar. **California no se ajusta** al § 529: sin deducción estatal por aportaciones y sin el refugio federal para los rendimientos; en el traspaso a Roth, California no adoptó la exclusión federal, así que los rendimientos tributan a nivel estatal según la guía vigente de la FTB. *Notas personales de estudio; no constituye asesoría fiscal. Traducción de estudio, pendiente de revisión por hablante nativo.*

## 한국어 (초역, 원어민 감수 대기)

**529에 남은 돈 처리법: Roth 이체, 수익자 변경과 캘리포니아 기준.** 529 플랜(IRC § 529)의 세제 혜택은 돈이 교육 용도에 머무는 동안만 유지됩니다. 적격 고등교육 비용에 대한 인출은 § 529(c)(3)(B)에 따라 수익 부분이 제외되고, 모든 인출은 납입 원금(다시 과세되지 않음)과 수익(과세·추가세 대상은 이 부분뿐)의 비율로 나뉩니다. 잔액의 출구는 비용이 낮은 순서대로 수익자 변경, 적격 용도 확대 활용, 수익자 본인의 Roth IRA 이체, 그리고 마지막에 비적격 인출입니다.

**Roth 출구 — SECURE 2.0 제126조, § 529(c)(3)(E)로 성문화, 2023년 12월 31일 이후 분배부터 적용.** 다섯 가지 엄격한 조건이 있습니다. (1) 529 계좌가 해당 수익자를 위해 **15년 이상** 유지됐어야 합니다(수익자 변경 시 이 기간이 다시 시작되는지에 대해 IRS 최종 지침이 없어 보수적으로 계획하는 것이 안전합니다). (2) 이체일 기준 **5년보다 전에** 납입한 금액과 그 수익만 옮길 수 있습니다. (3) 수익자 1인당 **평생 한도 35,000달러**. (4) 연도별 이체액은 그해 Roth IRA 연간 납입 한도(2025년 7,000달러, 2026년 7,500달러)에서 수익자가 그해 스스로 IRA에 넣은 금액을 뺀 금액을 넘을 수 없습니다. 이체는 같은 연간 한도를 소진합니다. (5) 수익자에게 이체액 이상의 **근로소득**이 있어야 하고, Roth IRA는 반드시 **수익자 본인 명의**여야 하며 계획에서 직접 이체(trustee-to-trustee)해야 합니다. 일반 Roth 납입의 MAGI 소득 제한은 이 이체에 **적용되지 않습니다**. 예시(2025년 수치, 재계산 완료): 2010년 개설 계좌에 52,000달러가 있고 납입금 40,000달러(전부 2019년까지 납입), 수익 12,000달러입니다. 24세 수익자의 근로소득은 9,000달러이고 그해 IRA 납입은 없습니다. 2025년 이체액은 min(7,000, 9,000) = **7,000달러**로 비과세·무벌칙이며, 평생 한도는 35,000 − 7,000 = 28,000달러가 남습니다. 반면 같은 해 비적격으로 10,000달러를 빼면 수익 부분 10,000 × 12,000 ÷ 52,000 ≈ **2,307.69달러**가 일반소득으로 과세되고 § 529(c)(6)의 10% 추가세 약 **230.77달러**가 붙습니다.

**수익자 변경(§ 529(c)(5))** 은 기존 수익자의 가족 구성원(§ 529(e)(2)에서 배우자, 후손, 형제자매, 부모, 조카, 인척과 그 배우자까지 넓게 정의)에게 비과세로 가능하고 금액 한도가 없어 보통 첫 번째 수단입니다. **확대된 적격 용도**(§ 529(e)(3))도 잔액을 흡수합니다. 대학원, § 529(c)(8)의 등록 도제(apprenticeship) 프로그램 비용, 그리고 § 529(c)(9)의 학자금 대출 상환 — 1인당 **평생 10,000달러** 한도로 수익자 본인과 각 형제자매에게 따로 적용됩니다. **비적격 인출**은 수익 부분만 일반소득으로 과세하고 § 529(c)(6) 10% 추가세를 붙이되, 장학금(수령액 한도 내), 사망, 장애, 미국 군사학교 재학의 경우 추가세는 면제됩니다(소득세는 유지). **캘리포니아는 § 529를 따르지 않습니다.** 납입에 대한 주 공제가 없고 수익 부분에 연방식 제외가 주 차원에서 적용되지 않으며, Roth 이체에 대해서도 캘리포니아는 연방 제외를 채택하지 않았으므로 수익 부분은 주 차원에서 과세되는 것으로 보고 FTB 현행 지침으로 확인해야 합니다. *개인 학습 노트이며 세무 자문이 아닙니다. 초역으로 교정 대기 중입니다.*

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

**Tiền 529 còn dư thì sao: chuyển sang Roth, đổi người thụ hưởng và quy tắc California.** Chương trình 529 (IRC § 529) chỉ bảo vệ phần lãi khi tiền còn dùng cho giáo dục: khoản rút cho chi phí giáo dục đại học đủ điều kiện được loại phần lãi theo § 529(c)(3)(B), và mọi khoản rút đều được chia theo tỷ lệ giữa vốn góp (không bị đánh thuế lại) và lãi (phần duy nhất có thể bị đánh thuế hoặc phạt). Các lối ra cho số dư, theo thứ tự chi phí tăng dần, là: đổi người thụ hưởng, dùng hết danh sách chi phí đủ điều kiện đã mở rộng, chuyển tiền sang Roth IRA của người thụ hưởng, và cuối cùng mới rút không đủ điều kiện.

**Lối ra Roth — SECURE 2.0 mục 126, luật hóa tại § 529(c)(3)(E), cho phân phối sau 31/12/2023.** Năm điều kiện cứng: (1) tài khoản đã duy trì cho người thụ hưởng ít nhất **15 năm** (chưa có hướng dẫn cuối cùng của IRS về việc đổi người thụ hưởng có khởi động lại đồng hồ này hay không); (2) chỉ phần đã đóng **hơn năm năm** trước, cùng lãi của chúng, được chuyển; (3) trần **trọn đời 35.000 đô la** mỗi người thụ hưởng; (4) khoản chuyển hằng năm không vượt giới hạn Roth IRA của năm đó (7.000 đô la năm 2025; 7.500 đô la năm 2026) trừ khoản tự đóng vào IRA trong năm — dùng chung một giới hạn; và (5) **thu nhập lao động** ít nhất bằng khoản chuyển, Roth IRA đứng tên **chính người thụ hưởng**, chuyển trực tiếp trustee-to-trustee. Giới hạn MAGI của đóng góp Roth thông thường **không áp dụng** ở đây. Ví dụ (2025, đã tính lại): tài khoản mở năm 2010 có 52.000 đô la — 40.000 đô la vốn góp, toàn bộ đóng trước năm 2019, và 12.000 đô la lãi. Người thụ hưởng 24 tuổi có thu nhập lao động 9.000 đô la, không đóng IRA trong năm. Khoản chuyển năm 2025 là min(7.000, 9.000) = **7.000 đô la**, miễn thuế và miễn phạt, còn lại 35.000 − 7.000 = 28.000 đô la hạn mức trọn đời. Ngược lại, rút không đủ điều kiện 10.000 đô la trong cùng năm sẽ đánh thuế phần lãi: 10.000 × 12.000 ÷ 52.000 ≈ **2.307,69 đô la** thu nhập thường, cộng thuế bổ sung 10% theo § 529(c)(6) khoảng **230,77 đô la**.

**Đổi người thụ hưởng (§ 529(c)(5))** sang thành viên gia đình của người thụ hưởng cũ (§ 529(e)(2), định nghĩa rộng) được miễn thuế, không có trần tiền và thường là bước đầu tiên. **Các mục đích sử dụng đủ điều kiện đã mở rộng** (§ 529(e)(3)) cũng hấp thụ số dư: học sau đại học, học nghề đã đăng ký (§ 529(c)(8)) và trả nợ vay sinh viên (§ 529(c)(9)) với trần **trọn đời 10.000 đô la** mỗi người, áp dụng riêng cho người thụ hưởng và từng anh chị em. **Rút không đủ điều kiện** chỉ đánh thuế phần lãi theo thu nhập thường cộng thuế bổ sung 10% của § 529(c)(6); thuế bổ sung được miễn (thuế thu nhập vẫn áp dụng) với học bổng trong phạm vi tiền học bổng, tử vong, khuyết tật và học viện quân sự Hoa Kỳ. **California không tuân theo** § 529: không khấu trừ bang cho đóng góp, phần lãi không được loại trừ kiểu liên bang ở cấp bang; với chuyển sang Roth, California chưa áp dụng loại trừ liên bang nên phần lãi chịu thuế ở cấp bang theo hướng dẫn hiện hành của FTB. *Ghi chú học tập cá nhân, không phải tư vấn thuế. Bản dịch sơ bộ, chờ hiệu đính.*

## हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

**529 में बचा पैसा क्या करें: Roth में स्थानांतरण, लाभार्थी बदलना और California नियम।** 529 योजना (IRC § 529) की कर-सुरक्षा केवल तब तक है जब तक पैसा शिक्षा पर रहे: योग्य उच्च-शिक्षा व्ययों हेतु वितरण में आय-अंश § 529(c)(3)(B) से बाहर रहता है, और हर वितरण मूल योगदान (जिस पर दोबारा कर नहीं लगता) और आय (केवल यही अंश कर या अतिरिक्त कर के अधीन है) के अनुपात में बँटता है। अधिशेष के निकास, सस्ते से महँगे क्रम में, हैं: लाभार्थी बदलना, विस्तारित योग्य-व्यय सूची का उपयोग, लाभार्थी के Roth IRA में स्थानांतरण, और अंत में अग़ैर-योग्य निकासी।

**Roth निकास — SECURE 2.0 धारा 126, § 529(c)(3)(E) में संहिताबद्ध, 31 दिसंबर 2023 के बाद के वितरणों पर लागू।** पाँच कठोर शर्तें: (1) खाता उस लाभार्थी के लिए कम से कम **15 वर्ष** पुराना हो (लाभार्थी बदलने से घड़ी फिर शुरू होती है या नहीं, IRS का अंतिम मार्गदर्शन नहीं है); (2) केवल **पाँच वर्ष से अधिक पहले** का योगदान और उसकी आय जा सकती है; (3) प्रति लाभार्थी **जीवनकाल सीमा 35,000 डॉलर**; (4) वार्षिक स्थानांतरण उस वर्ष की Roth IRA सीमा (2025 में 7,000 डॉलर; 2026 में 7,500 डॉलर) से लाभार्थी के उसी वर्ष के अपने IRA योगदान घटाकर उससे अधिक नहीं — स्थानांतरण वही सीमा खपत करता है; और (5) **श्रम-आय** स्थानांतरण के बराबर हो, Roth IRA **स्वयं लाभार्थी के नाम** हो, हस्तांतरण सीधे trustee-to-trustee हो। सामान्य Roth की MAGI आय-सीमा यहाँ **लागू नहीं होती**। उदाहरण (2025, पुनर्गणना की गई): 2010 में खुले खाते में 52,000 डॉलर हैं — योगदान 40,000 डॉलर, सारा 2019 तक, और आय 12,000 डॉलर। 24 वर्षीय लाभार्थी की श्रम-आय 9,000 डॉलर है, उस वर्ष IRA में कुछ नहीं डाला। 2025 का स्थानांतरण min(7,000, 9,000) = **7,000 डॉलर** है, कर-मुक्त और दंड-मुक्त, और जीवनकाल क्षमता 35,000 − 7,000 = 28,000 डॉलर शेष रहती है। इसके विपरीत, उसी वर्ष 10,000 डॉलर की अग़ैर-योग्य निकासी पर आय-अंश पर कर लगेगा: 10,000 × 12,000 ÷ 52,000 ≈ **2,307.69 डॉलर** सामान्य आय, साथ में § 529(c)(6) का 10% अतिरिक्त कर, लगभग **230.77 डॉलर**।

**लाभार्थी बदलना (§ 529(c)(5))** पुराने लाभार्थी के परिवार के सदस्य के पक्ष में (§ 529(e)(2), व्यापक परिभाषा) कर-मुक्त है, कोई डॉलर-सीमा नहीं है और यह आमतौर पर पहला कदम होता है। **विस्तारित योग्य उपयोग** (§ 529(e)(3)) भी शेष राशि सोखते हैं: स्नातकोत्तर अध्ययन, § 529(c)(8) के पंजीकृत प्रशिक्षु कार्यक्रमों की लागत और § 529(c)(9) के तहत छात्र-ऋण चुकौती — प्रति व्यक्ति **जीवनकाल सीमा 10,000 डॉलर**, लाभार्थी और प्रत्येक भाई-बहन पर अलग-अलग। **अग़ैर-योग्य निकासी** पर केवल आय-अंश सामान्य आय के रूप में कर-योग्य है और § 529(c)(6) का 10% अतिरिक्त कर लगता है, जो छात्रवृत्ति (पुरस्कार राशि तक), मृत्यु, विकलांगता और सैन्य अकादमी उपस्थिति पर माफ़ है (आयकर बना रहता है)। **California § 529 का अनुसरण नहीं करता**: योगदान पर राज्य कटौती नहीं है और आय-अंश को राज्य स्तर पर संघीय जैसी छूट नहीं मिलती; Roth स्थानांतरण के लिए California ने संघीय छूट नहीं अपनाई है, इसलिए आय-अंश को राज्य स्तर पर कर-योग्य मानें और FTB के वर्तमान मार्गदर्शन से पुष्टि करें। *व्यक्तिगत अध्ययन नोट; कर सलाह नहीं। प्रारंभिक अनुवाद, समीक्षा लंबित।*

---
*个人学习笔记，不构成税务建议。*
