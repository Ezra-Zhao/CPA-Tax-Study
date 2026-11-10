# 离职后 HSA 和 FSA 的钱怎么办：COBRA 衔接、余额处理与加州口径

> 个人学习笔记，不构成税务建议。Personal study notes, not tax advice.
> 核心依据：IRC § 223（HSA）、§ 125（cafeteria plan 与 FSA）、§ 4980B（COBRA）；IRS Publication 969、Publication 503；IRS Notice 2012-34（健康 FSA 的 COBRA 特别口径）；Rev. Proc. 2024-40（2025 年结转上限）。加州部分以 FTB 现行口径为准。

离职那一周，人事部门交代的多半是工卡、邮箱和最后一份工资，账户里的钱很少有人主动讲清。HSA 和健康 FSA 平时总被摆在一起比较，一到离职就彻底分家：一个是你的个人账户，跟着你走；另一个是雇主计划里的一个选举额，雇佣关系一断就开始倒计时。这篇把四种余额分开讲：HSA、医疗 FSA（health FSA）、受扶养人照护 FSA（dependent care FSA），外加 COBRA 续保在 FSA 上到底怎么衔接。

## 中文主文

### 一、HSA：账户是你的，离职不没收、不过期

HSA（健康储蓄账户）依 IRC § 223 设立，账户持有人是员工个人，由银行或托管机构（custodian/trustee）持有，不是雇主的钱。离职、换工作、退休，都不触发没收：余额原封不动留在账户里，继续按 § 223(f) 的规则使用——取款用于本人、配偶或受扶养人的 § 213(d) 合格医疗费用时免税，非医疗取款按 § 223(f)(4) 处理（65 岁前另加 20% 附加税，65 岁、残疾或死亡后只计普通收入、不再加罚）。

离职后有三件事容易混。第一，还能不能往里存钱，看的不是在不在职，而是还有没有 HSA 资格：只要仍参加合格 HDHP、没有其他冲突保障、未加入 Medicare，就可以继续供款（自己直接存入可走线上扣除，经新雇主工资供款则另说），与原雇主无关。第二，能不能花钱，与资格无关：哪怕已经换到非 HDHP 计划、甚至没有保险了，账户里的旧余额仍可免税支付合格医疗费用，直到花完为止。第三，账户可以留在原托管方，也可以做 trustee-to-trustee 转移或 60 天滚存（§ 223(f)(5) 一带口径，一年一次限制参照 IRA 滚存规则把握）换到自己选的托管方，原雇主无权扣留。

一句话：HSA 在离职清单上属于「不用抢时间」的那一类，真正要抢时间的是下面两种 FSA。

### 二、医疗 FSA：离职即止，use-it-or-lose-it 开始倒计时

健康 FSA 是 § 125 自助餐计划下的一个选举，不是个人账户。它有三层结构要分清。

第一层是覆盖期。离职（或其他覆盖终止事件）之后，新发生的医疗费用原则上不再可报，除非选了 COBRA 续保（见第三节）。离职日之前已经发生的合格费用，通常仍可在计划规定的 run-out period（申报宽限期，常见 90 天，以计划文件为准）内提交报销——注意 run-out 只是「提交截止」往后推，费用发生日必须落在覆盖期内。

第二层是没收规则。健康 FSA 是 use-it-or-lose-it：计划年度结束时未用完的余额归计划所有。雇主最多只能二选一给一个缓冲：要么允许有限结转（carryover）到下一计划年度——2025 年结转上限为 660 美元（Rev. Proc. 2024-40），其后年份的上限以 IRS 当年公告为准；要么给最长 2 个半月的宽限期（grace period）继续发生新费用。两者不能同时有，也可能都没有，以计划文件为准。关键提醒：结转和宽限期都是「计划年度」层面的安排，员工中途离职时，离职日的覆盖终止一般先于年度结转发生，不能指望靠结转把余额带过离职线。

第三层是 uniform coverage 的另一面。在职时，全年选举额从年初起就可全额报销，哪怕工资还没扣够；若离职前报销额已经超过实际已供款额，差额雇主一般不能向员工追讨。反过来，账户里还有正余额却没来得及花，就回到没收规则。所以离职前把已发生的费用先报掉、把能提前发生的合格支出（眼镜、牙科等可安排项目）排进覆盖期，是这条规则下最实际的动作。

### 三、COBRA 续保 FSA：能续，但健康 FSA 只续到当年年底

COBRA（IRC § 4980B 与 ERISA 相应条款）要求一定规模的雇主在员工离职等合格事件后，提供按原条件自费续保团体健康计划的机会，保费最高可达计划成本的 102%。健康 FSA 属于团体健康计划，原则上在 COBRA 射程内，但它有一套特别口径（IRS Notice 2012-34 与拟议条例的长期实务口径）：

一是「只到当年底」。健康 FSA 的 COBRA 续保期只到合格事件所在计划年度结束为止，不是普通医疗险 COBRA 的 18 个月。跨过计划年度，FSA 本身按没收规则结算，续保也随之结束。

二是「花超了可以不给续」。若离职时该员工的 FSA 已经 overspent——已报销额超过剩余可得利益，雇主可以不提供 FSA 的 COBRA 续保。判断线看的是：到年底前还能报销的最高金额（全年选举额减已报销额），是否不低于续保期剩余保费。只有账户 underspent（还有净利益可拿）时，续保才有实际内容、雇主才须提供选择。

三是算例把这条线算清。某员工全年选举 2,400 美元、每月供款 200 美元，6 月底离职：已供款 200×6＝1,200 美元，已报销 500 美元，年底前剩余最高可报金额为 2,400−500＝1,900 美元；下半年续保保费按剩余供款 1,200 美元的 102% 计为 1,224 美元。1,900 大于 1,224，属 underspent，雇主须提供续保选择；员工若续保并在年底前发生至少 1,224 美元以上的合格费用，续保才划算。反之若离职前已报销 2,000 美元，剩余最高可报只有 400 美元，低于续保保费，续保在经济上不成立，口径上也落入 overspent 一侧。数字均为自编教学演算，本地复算勾稽无误（2,400−500＝1,900；200×6＝1,200；1,200×102%＝1,224）。

四是续保期间的钱仍是 FSA 的钱：只能报 § 213(d) 合格费用，年度结束仍未用完的部分照样没收，续保不改变 use-it-or-lose-it 的本质。

### 四、Dependent care FSA：不归 COBRA 管，余额看到计划年度末

受扶养人照护 FSA（§ 129 排除、每户每年上限 5,000 美元，分开申报 2,500 美元）保的是托育、照护支出，不是医疗保障，因此它不是团体健康计划，不适用 COBRA 续保——离职后没有「自费续保 DCFSA」这一选项。

它的余额处理比医疗 FSA 宽一线：离职后，账户里已供款的余额通常仍可用于离职之后、计划年度结束之前发生的合格照护费用（IRS Publication 503 的实务口径是离职员工可继续花完余额，即 spend-down），前提是费用本身合格（为了让员工或配偶工作而发生的照护、合格受照护人等要件照常适用），且计划文件没有更严的截止。计划年度一结束，未用余额同样没收；DCFSA 没有结转（carryover）通道，雇主若给缓冲只有 2 个半月宽限期一途，以计划文件为准。

算例：全年选举 5,000 美元，上半年已供款 2,500 美元、已报销 1,800 美元，6 月底离职时余额 2,500−1,800＝700 美元。这 700 美元可继续支付下半年发生的合格托育费用，直到计划年度结束或花完为止；年底仍剩的部分没收。复算：2,500−1,800＝700，无误。

### 五、离职当周的动作清单

一、先向人事或计划管理方拿到三个日期：覆盖终止日、run-out 提交截止日、计划年度结束日。二、把覆盖期内已发生的医疗费用在 run-out 截止前报完，收据与 EOB 留档。三、收到 COBRA 选举通知后，先做第三节的 underspent 算术，再决定续不续健康 FSA；注意 COBRA 一般有 60 天选举期、选后可追溯，期限以通知书为准。四、DCFSA 有余额的，把下半年照护费用的凭证按月留好，在年度结束前报完。五、HSA 不用动，确认托管方联系方式与受益人信息跟着自己走即可；想换托管方时优先用 trustee-to-trustee 直转，避免 60 天滚存的时限与次数限制。

### 六、加州口径：HSA 州税不跟随这一条最要紧

加州不承认 HSA 的联邦税收待遇：HSA 供款在加州所得税下不可扣除、也不能作税前工资排除，账户内的利息、股息与投资收益要在加州当年计税，报州税时须在加州调整表（Schedule CA 一带）做加回与收益申报，合格医疗取款在州层面另按加州口径核对（以 FTB 现行说明为准）。这条不因离职改变：离职后继续持有、继续使用 HSA，加州调整年年都要做。相比之下，§ 125 下的健康 FSA 与 DCFSA 的税前处理，加州大体跟随联邦框架，但具体排除与申报口径以 FTB 当年说明为准；COBRA 州层面的延续保障另有 Cal-COBRA（针对小雇主计划）等州法安排，与联邦 COBRA 的适用范围不同，离职时以收到的选举通知所载依据为准，不把联邦结论直接套到州计划上。

**来源与依据**：IRC § 223（重点 (b) 资格与供款、(f) 取款计税与滚存）、§ 125（自助餐计划与 FSA 选举）、§ 129（受扶养人照护排除上限 5,000/2,500 美元）、§ 4980B（COBRA 续保与 102% 保费上限）；IRS Publication 969（HSA/FSA 与 COBRA 衔接口径）、Publication 503（DCFSA 与离职后 spend-down）；IRS Notice 2012-34（健康 FSA 的 COBRA 只到计划年度末与 underspent 判断）；Rev. Proc. 2024-40（2025 年健康 FSA 结转上限 660 美元，其后年份以 IRS 当年公告为准）；加州 FTB 关于 HSA 不跟随联邦的公开口径。计划层面的 run-out、结转与宽限期安排以各自计划文件为准。

*声明：个人学习笔记，不构成税务建议。具体离职结算请以计划文件、COBRA 选举通知与 IRS、FTB 现行指引为准，金额较大时先咨询持牌 CPA。*

---

## English

What happens to these accounts when you leave a job splits cleanly by account type. **The HSA is yours.** An HSA under IRC § 223 is an individual account held by a custodian, not employer property: separation, a job change, or retirement never forfeits it. The balance stays, keeps following § 223(f) — tax-free withdrawals for § 213(d) qualified medical expenses, and non-medical withdrawals taxed as income (with the 20% additional tax before age 65 under § 223(f)(4)). Two points are often confused: whether you may keep *contributing* depends on HSA eligibility (qualifying HDHP coverage, no disqualifying coverage, no Medicare), not on employment; whether you may keep *spending* the old balance on qualified expenses does not depend on eligibility at all. You may leave the account with the old custodian or move it by trustee-to-trustee transfer or a 60-day rollover.

**The health FSA ends with coverage.** A health FSA is a § 125 election, not a personal account. After the coverage termination date, newly incurred expenses are generally no longer reimbursable unless COBRA is elected; expenses incurred before termination can usually still be submitted during the plan's run-out period (often 90 days — check the plan document). Unused amounts are forfeited under use-it-or-lose-it: the employer may offer at most one cushion, either a limited carryover into the next plan year — capped at $660 for 2025 (Rev. Proc. 2024-40), with later years set by the IRS annual guidance — or a grace period of up to 2.5 months, never both, and possibly neither. Carryover and grace periods operate at the plan-year level; they do not carry a balance across a mid-year separation. The flip side of uniform coverage: if you were reimbursed more than you had contributed before leaving, the employer generally cannot claw back the difference.

**COBRA for a health FSA is narrow.** COBRA (§ 4980B) charges up to 102% of plan cost, but for health FSAs the continuation runs only to the end of the plan year in which the qualifying event occurs — not 18 months (IRS Notice 2012-34 practice). If the account is overspent, no COBRA offer is required; the test compares the maximum benefit still available for the year with the COBRA premium for the rest of the year. Example: a $2,400 election at $200 per month, separation on June 30 — $1,200 contributed, $500 reimbursed, so the remaining maximum benefit is $2,400 − $500 = $1,900; the COBRA premium for the second half is $1,200 × 102% = $1,224. Because $1,900 exceeds $1,224 the account is underspent and continuation must be offered — and it only pays off if the employee incurs enough qualified expenses by year-end. Anything still unused at year-end is forfeited anyway.

**The dependent care FSA has no COBRA, but allows spend-down.** A dependent care FSA (§ 129, $5,000 per household, $2,500 if married filing separately) is not a group health plan, so there is no COBRA continuation. However, the balance already contributed can generally be used for qualifying care expenses incurred after separation through the end of the plan year (IRS Publication 503 practice), subject to the plan document. There is no carryover for dependent care FSAs — at most a 2.5-month grace period. Example: a $5,000 election with $2,500 contributed and $1,800 reimbursed by mid-year leaves $2,500 − $1,800 = $700 usable for second-half qualifying care, forfeited if still unused at year-end.

**California.** California does not conform to the federal HSA regime: contributions are not deductible or excludable for California purposes, and account earnings are taxed by California each year, requiring a state adjustment — and that continues after you leave the job. California broadly follows the federal framework for § 125 health and dependent care FSAs (confirm against current FTB guidance), and state continuation for small-employer plans runs through Cal-COBRA, a separate state scheme from federal COBRA.

*Personal study notes only; not tax advice. Plan documents, the COBRA election notice, and current IRS and FTB guidance control.*

## Español

Lo que ocurre con estas cuentas al dejar un empleo se divide con claridad según el tipo de cuenta. **La HSA es suya.** Una HSA conforme al IRC § 223 es una cuenta individual en manos de un custodio, no propiedad del empleador: la separación, el cambio de empleo o la jubilación nunca la confiscan. El saldo permanece y sigue la regla del § 223(f): retiros libres de impuestos para gastos médicos calificados del § 213(d), y retiros no médicos gravados como ingreso (con el impuesto adicional del 20 % antes de los 65 años, § 223(f)(4)). Dos precisiones: poder seguir *aportando* depende de la elegibilidad HSA (cobertura HDHP calificada, sin cobertura incompatible y sin Medicare), no del empleo; poder seguir *gastando* el saldo antiguo en gastos calificados no depende de la elegibilidad. La cuenta puede quedarse con el custodio anterior o moverse por transferencia directa entre custodios o por rollover de 60 días.

**La FSA de salud termina con la cobertura.** Es una elección del § 125, no una cuenta personal. Tras la fecha de terminación de la cobertura, los gastos nuevos ya no son reembolsables salvo que se elija COBRA; los gastos incurridos antes sí pueden presentarse durante el período de liquidación (run-out, a menudo 90 días, según el documento del plan). Lo no usado se pierde (use-it-or-lose-it): el empleador puede ofrecer como máximo un colchón, o un arrastre limitado al año siguiente del plan —con tope de 660 dólares para 2025 (Rev. Proc. 2024-40) y los años posteriores según la guía anual del IRS— o un período de gracia de hasta 2,5 meses, nunca ambos y quizá ninguno. El arrastre y la gracia operan a nivel del año del plan y no trasladan el saldo a través de una separación a mitad de año. La otra cara de la cobertura uniforme: si antes de salir le reembolsaron más de lo aportado, el empleador en general no puede recuperar la diferencia.

**COBRA en la FSA de salud es estrecho.** COBRA (§ 4980B) cobra hasta el 102 % del costo, pero en la FSA de salud la continuación llega solo hasta el fin del año del plan en que ocurre el evento calificado, no 18 meses (práctica de la Notice 2012-34 del IRS). Si la cuenta está sobregirada (overspent), no hay obligación de ofrecerla; la prueba compara el beneficio máximo aún disponible con la prima COBRA del resto del año. Ejemplo: elección de 2.400 dólares a 200 por mes, salida el 30 de junio: aportado 1.200, reembolsado 500, beneficio máximo restante 2.400 − 500 = 1.900; la prima COBRA del segundo semestre es 1.200 × 102 % = 1.224. Como 1.900 supera a 1.224, la cuenta está underspent y debe ofrecerse la continuación, que solo compensa si se incurren gastos calificados suficientes antes de fin de año. Lo que quede sin usar a fin de año se pierde igualmente.

**La FSA de cuidado de dependientes no tiene COBRA, pero permite agotar el saldo.** Conforme al § 129 (5.000 dólares por hogar, 2.500 si declara por separado estando casado), no es un plan de salud grupal y no hay continuación COBRA. Sin embargo, el saldo ya aportado puede usarse en general para gastos de cuidado calificados incurridos después de la salida y hasta el fin del año del plan (práctica de la Publicación 503 del IRS), según el documento del plan. No hay arrastre en esta FSA: como máximo un período de gracia de 2,5 meses. Ejemplo: elección de 5.000, aportado 2.500 y reembolsado 1.800 a mitad de año, quedan 2.500 − 1.800 = 700 utilizables en el segundo semestre y perdidos si no se usan.

**California.** California no se ajusta al régimen federal de las HSA: las aportaciones no son deducibles ni excluibles a nivel estatal y los rendimientos tributan en California cada año, con el ajuste estatal correspondiente, también después de dejar el empleo. Para las FSA del § 125, California sigue en general el marco federal (confírmese con la guía vigente del FTB); la continuación estatal para planes de empleadores pequeños corre por Cal-COBRA, un régimen distinto del COBRA federal.

*Notas personales de estudio; no constituye asesoría fiscal. Rigen el documento del plan, el aviso de elección COBRA y la guía vigente del IRS y el FTB.*

## 한국어 (초역, 원어민 감수 대기)

퇴사 시 이 계좌들의 운명은 계좌 종류별로 갈립니다. **HSA는 본인 소유입니다.** IRC § 223의 HSA는 수탁기관이 보유하는 개인 계좌이지 고용주의 재산이 아니므로, 퇴사·이직·은퇴로 몰수되지 않습니다. 잔액은 그대로 남아 § 223(f)를 따릅니다. § 213(d) 적격 의료비 인출은 비과세이고, 비의료 인출은 소득으로 과세되며 65세 전에는 § 223(f)(4)의 20% 추가세가 붙습니다. 헷갈리기 쉬운 두 가지: 계속 *납입*할 수 있는지는 고용 여부가 아니라 HSA 자격(적격 HDHP 가입, 부적격 보장 없음, Medicare 미가입)으로 정해지고, 기존 잔액을 적격 비용에 계속 *쓰는* 것은 자격과 무관합니다. 계좌는 기존 수탁기관에 두거나 수탁자 간 직접 이체 또는 60일 롤오버로 옮길 수 있습니다.

**의료 FSA는 보장이 끝나면 끝납니다.** § 125의 선택이지 개인 계좌가 아닙니다. 보장 종료일 이후 새로 발생한 비용은 COBRA를 선택하지 않는 한 원칙적으로 상환되지 않고, 종료 전에 발생한 비용은 플랜의 run-out 기간(흔히 90일, 플랜 문서 확인) 안에 제출할 수 있습니다. 미사용액은 use-it-or-lose-it로 몰수됩니다. 고용주는 완충을 최대 하나만 줄 수 있습니다. 다음 플랜 연도로의 제한적 이월(2025년 상한 660달러, Rev. Proc. 2024-40; 이후 연도는 IRS 연례 안내 기준) 또는 최대 2.5개월의 유예기간 중 하나이며, 둘 다는 안 되고 없을 수도 있습니다. 이월과 유예는 플랜 연도 단위의 장치라 연도 중간의 퇴사를 넘어 잔액을 이어 주지 않습니다. 균일 보장(uniform coverage)의 반대면도 있습니다. 퇴사 전에 납입액보다 많이 상환받았더라도 고용주는 원칙적으로 그 차액을 돌려받을 수 없습니다.

**의료 FSA의 COBRA는 좁습니다.** COBRA(§ 4980B)는 비용의 최대 102%를 청구하지만, 의료 FSA의 연장은 자격 사건이 발생한 플랜 연도의 말일까지만 이어지고 18개월이 아닙니다(IRS Notice 2012-34의 실무). 계좌가 이미 초과 사용(overspent) 상태이면 연장을 제공할 의무가 없으며, 판단은 그해 남은 최대 급부와 남은 기간의 COBRA 보험료를 비교합니다. 예시: 연간 선택액 2,400달러, 월 200달러, 6월 30일 퇴사 — 납입 1,200달러, 상환 500달러이므로 남은 최대 급부는 2,400 − 500 = 1,900달러이고, 하반기 COBRA 보험료는 1,200 × 102% = 1,224달러입니다. 1,900이 1,224보다 크므로 underspent에 해당해 연장을 제공해야 하며, 연말까지 적격 비용이 충분히 발생할 때만 연장이 이득입니다. 연말에 남으면 어차피 몰수됩니다.

**부양가족 돌봄 FSA는 COBRA가 없지만 잔액 소진이 가능합니다.** § 129(가구당 5,000달러, 부부 별도 신고 시 2,500달러)의 이 FSA는 단체 건강 플랜이 아니므로 COBRA 연장이 없습니다. 다만 이미 납입한 잔액은 원칙적으로 퇴사 후 플랜 연도 말까지 발생한 적격 돌봄 비용에 쓸 수 있습니다(IRS Publication 503 실무, 플랜 문서가 우선). 이 FSA에는 이월이 없고 최대 2.5개월 유예만 가능합니다. 예시: 선택액 5,000달러, 반기까지 납입 2,500달러, 상환 1,800달러이면 2,500 − 1,800 = 700달러가 남아 하반기의 적격 돌봄 비용에 쓸 수 있고, 연말까지 못 쓰면 몰수됩니다.

**캘리포니아.** 캘리포니아는 연방 HSA 제도에 동조하지 않습니다. 납입금은 주세에서 공제·제외되지 않고 계좌 수익은 매년 캘리포니아에서 과세되므로 주 조정 신고가 필요하며, 이는 퇴사 후에도 계속됩니다. § 125 의료·돌봄 FSA에 대해 캘리포니아는 대체로 연방 틀을 따르지만 현행 FTB 안내로 확인해야 하고, 소규모 고용주 플랜의 주 차원 연장은 연방 COBRA와 별개 제도인 Cal-COBRA로 운영됩니다.

*개인 학습 노트이며 세무 자문이 아닙니다. 플랜 문서, COBRA 선택 통지와 현행 IRS, FTB 안내가 기준입니다. (초역, 원어민 감수 대기)*

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

Khi nghỉ việc, số phận của các tài khoản này tách rõ theo loại tài khoản. **HSA là của bạn.** HSA theo IRC § 223 là tài khoản cá nhân do tổ chức quản lý nắm giữ, không phải tài sản của chủ lao động: nghỉ việc, đổi việc hay nghỉ hưu đều không làm mất tài khoản. Số dư ở nguyên và tiếp tục theo § 223(f) — rút tiền cho chi phí y tế đủ điều kiện theo § 213(d) thì miễn thuế, rút ngoài y tế thì tính thu nhập (trước 65 tuổi thêm 20% thuế bổ sung theo § 223(f)(4)). Hai điểm hay nhầm: việc có tiếp tục *đóng góp* được hay không phụ thuộc vào tư cách HSA (tham gia HDHP đủ điều kiện, không có bảo hiểm xung đột, chưa vào Medicare) chứ không phụ thuộc việc làm; còn việc tiếp tục *chi* số dư cũ cho chi phí đủ điều kiện thì không phụ thuộc tư cách. Tài khoản có thể để ở tổ chức cũ hoặc chuyển thẳng giữa các tổ chức quản lý, hoặc rollover trong 60 ngày.

**FSA y tế kết thúc cùng bảo hiểm.** Đây là lựa chọn theo § 125, không phải tài khoản cá nhân. Sau ngày chấm dứt bảo hiểm, chi phí mới phát sinh nhìn chung không được hoàn nữa trừ khi chọn COBRA; chi phí phát sinh trước ngày chấm dứt vẫn có thể nộp trong thời gian run-out của chương trình (thường 90 ngày, theo văn kiện chương trình). Số tiền không dùng hết bị mất theo nguyên tắc use-it-or-lose-it: chủ lao động chỉ được cho tối đa một đệm — hoặc chuyển hạn chế sang năm chương trình sau (trần năm 2025 là 660 đô la, Rev. Proc. 2024-40; các năm sau theo hướng dẫn hằng năm của IRS) hoặc thời gian ân hạn tối đa 2,5 tháng, không bao giờ cả hai và có thể không có cái nào. Chuyển năm và ân hạn vận hành ở cấp năm chương trình, không mang số dư qua một lần nghỉ việc giữa năm. Mặt trái của bảo hiểm đồng nhất: nếu trước khi nghỉ bạn đã được hoàn nhiều hơn số đã đóng, chủ lao động nhìn chung không đòi lại phần chênh được.

**COBRA cho FSA y tế rất hẹp.** COBRA (§ 4980B) thu tối đa 102% chi phí, nhưng với FSA y tế, việc duy trì chỉ kéo dài đến cuối năm chương trình mà sự kiện đủ điều kiện xảy ra — không phải 18 tháng (thực hành theo IRS Notice 2012-34). Nếu tài khoản đã «dùng vượt» (overspent) thì không bắt buộc phải chào COBRA; phép thử so sánh quyền lợi tối đa còn lại trong năm với phí COBRA của phần năm còn lại. Ví dụ: đăng ký 2.400 đô la, mỗi tháng 200 đô la, nghỉ ngày 30/6 — đã đóng 1.200, đã hoàn 500, nên quyền lợi tối đa còn lại là 2.400 − 500 = 1.900; phí COBRA nửa cuối năm là 1.200 × 102% = 1.224. Vì 1.900 lớn hơn 1.224 nên tài khoản thuộc diện underspent và phải được chào duy trì — và chỉ có lợi nếu phát sinh đủ chi phí đủ điều kiện trước cuối năm. Phần còn thừa cuối năm vẫn bị mất.

**FSA chăm sóc người phụ thuộc không có COBRA nhưng được tiêu nốt số dư.** Theo § 129 (5.000 đô la mỗi hộ, 2.500 nếu vợ chồng khai riêng), FSA này không phải chương trình sức khỏe nhóm nên không có duy trì COBRA. Tuy nhiên, số dư đã đóng nhìn chung vẫn dùng được cho chi phí chăm sóc đủ điều kiện phát sinh sau khi nghỉ việc đến hết năm chương trình (thực hành theo IRS Publication 503), tùy văn kiện chương trình. FSA này không có chuyển năm — tối đa chỉ có ân hạn 2,5 tháng. Ví dụ: đăng ký 5.000, đến giữa năm đã đóng 2.500 và đã hoàn 1.800, còn 2.500 − 1.800 = 700 đô la dùng cho chi phí chăm sóc đủ điều kiện ở nửa cuối năm, không dùng hết thì mất.

**California.** California không tuân theo chế độ HSA liên bang: tiền đóng không được khấu trừ hay loại trừ ở cấp bang và lợi nhuận trong tài khoản bị California đánh thuế hằng năm, phải điều chỉnh khi khai thuế bang — kể cả sau khi nghỉ việc. Với FSA y tế và chăm sóc theo § 125, California về cơ bản theo khung liên bang (đối chiếu hướng dẫn FTB hiện hành); việc duy trì ở cấp bang cho chương trình của chủ lao động nhỏ chạy qua Cal-COBRA, một chế độ riêng với COBRA liên bang.

*Ghi chú học tập cá nhân, không phải tư vấn thuế. Văn kiện chương trình, thông báo lựa chọn COBRA và hướng dẫn hiện hành của IRS, FTB là căn cứ. (Bản dịch sơ bộ, chờ hiệu đính)*

## हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

नौकरी छोड़ने पर इन खातों का परिणाम खाते के प्रकार से स्पष्ट बँटता है। **HSA आपका अपना है।** IRC § 223 के तहत HSA एक व्यक्तिगत खाता है जिसे custodian रखता है, नियोक्ता की संपत्ति नहीं: अलग होने, नौकरी बदलने या सेवानिवृत्ति से यह ज़ब्त नहीं होता। शेष राशि बनी रहती है और § 223(f) का पालन करती है — § 213(d) योग्य चिकित्सा ख़र्चों के लिए निकासी कर-मुक्त, ग़ैर-चिकित्सा निकासी आय के रूप में करयोग्य (65 वर्ष से पहले § 223(f)(4) का 20% अतिरिक्त कर)। दो भ्रम दूर करें: *योगदान जारी* रख सकते हैं या नहीं, यह रोज़गार पर नहीं बल्कि HSA पात्रता (योग्य HDHP कवरेज, अयोग्य कवरेज का अभाव, Medicare में न होना) पर निर्भर है; पुरानी शेष राशि को योग्य ख़र्चों पर *ख़र्च करते रहना* पात्रता पर निर्भर ही नहीं है। खाता पुराने custodian के पास रखा जा सकता है या trustee-to-trustee transfer अथवा 60-दिन rollover से ले जाया जा सकता है।

**Health FSA कवरेज के साथ समाप्त होता है।** यह § 125 का चुनाव है, व्यक्तिगत खाता नहीं। कवरेज समाप्ति तिथि के बाद नए ख़र्च सामान्यतः प्रतिपूर्तियोग्य नहीं रहते, जब तक COBRA न चुना जाए; समाप्ति से पहले के ख़र्च plan के run-out period (अक्सर 90 दिन, plan दस्तावेज़ देखें) में जमा किए जा सकते हैं। अप्रयुक्त राशि use-it-or-lose-it के तहत ज़ब्त होती है: नियोक्ता अधिक से अधिक एक राहत दे सकता है — या अगले plan वर्ष में सीमित carryover (2025 की सीमा $660, Rev. Proc. 2024-40; बाद के वर्ष IRS के वार्षिक मार्गदर्शन से) या अधिकतम 2.5 माह की grace period, दोनों कभी नहीं, और शायद कोई भी नहीं। Carryover और grace period plan-वर्ष स्तर पर काम करते हैं; वर्ष-मध्य की नौकरी-छोड़ घटना के पार शेष राशि नहीं ले जाते। Uniform coverage का दूसरा पहलू: यदि छोड़ने से पहले आपको योगदान से अधिक प्रतिपूर्ति मिल चुकी हो, तो नियोक्ता सामान्यतः वह अंतर वापस नहीं माँग सकता।

**Health FSA के लिए COBRA संकीर्ण है।** COBRA (§ 4980B) लागत का अधिकतम 102% लेता है, किंतु health FSA में निरंतरता केवल उस plan वर्ष के अंत तक चलती है जिसमें qualifying event हुआ — 18 माह नहीं (IRS Notice 2012-34 का व्यवहार)। यदि खाता overspent हो तो COBRA देना अनिवार्य नहीं; परीक्षण उस वर्ष के शेष अधिकतम लाभ की तुलना शेष वर्ष के COBRA प्रीमियम से करता है। उदाहरण: $2,400 का चुनाव, $200 प्रति माह, 30 जून को अलग होना — योगदान $1,200, प्रतिपूर्ति $500, अतः शेष अधिकतम लाभ $2,400 − $500 = $1,900; दूसरी छमाही का COBRA प्रीमियम $1,200 × 102% = $1,224। $1,900, $1,224 से अधिक है, अतः खाता underspent है और निरंतरता देनी होगी — और यह तभी लाभदायक है जब वर्ष-अंत तक पर्याप्त योग्य ख़र्च हो। वर्ष-अंत पर बची राशि फिर भी ज़ब्त होगी।

**Dependent care FSA में COBRA नहीं, पर शेष राशि ख़र्च की जा सकती है।** § 129 (प्रति परिवार $5,000, विवाहित पृथक दाख़िल पर $2,500) के तहत यह group health plan नहीं है, इसलिए COBRA निरंतरता नहीं मिलती। किंतु पहले से जमा शेष राशि सामान्यतः अलग होने के बाद, plan वर्ष के अंत तक हुए योग्य देखभाल ख़र्चों पर इस्तेमाल की जा सकती है (IRS Publication 503 का व्यवहार), plan दस्तावेज़ के अधीन। इस FSA में carryover नहीं है — अधिकतम 2.5 माह की grace period ही संभव है। उदाहरण: $5,000 का चुनाव, मध्य-वर्ष तक योगदान $2,500 और प्रतिपूर्ति $1,800, तो $2,500 − $1,800 = $700 शेष रहता है जो दूसरी छमाही के योग्य देखभाल ख़र्चों में लग सकता है, न लगे तो ज़ब्त।

**California।** California संघीय HSA व्यवस्था का अनुसरण नहीं करता: योगदान राज्य-स्तर पर न कटौती योग्य है न अपवर्जित, और खाते की कमाई पर हर वर्ष California कर लगता है, जिसके लिए राज्य समायोजन चाहिए — नौकरी छोड़ने के बाद भी। § 125 health व dependent care FSA के लिए California मोटे तौर पर संघीय ढाँचे का पालन करता है (वर्तमान FTB मार्गदर्शन से जाँचें); छोटे नियोक्ता plans के लिए राज्य-स्तरीय निरंतरता Cal-COBRA से चलती है, जो संघीय COBRA से अलग व्यवस्था है।

*व्यक्तिगत अध्ययन नोट; कर सलाह नहीं है। Plan दस्तावेज़, COBRA चुनाव सूचना और वर्तमान IRS व FTB मार्गदर्शन ही मान्य हैं। (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)*

---
## 补译增量（2026-11-10 07:55轮追加：韩／越／印三语各补 2 项细节增量，与中文主文细节对齐，正文原有段落未改动）

### 한국어 보충 (초역 · 初译待校)

보충 1 (캘리포니아의 HSA 비협조): 캘리포니아는 HSA의 연방 세제 혜택을 인정하지 않습니다. HSA 납입액은 주 소득세에서 공제되지도, 세전 임금 제외도 되지 않고, 계좌 안의 이자·배당·투자 수익은 캘리포니아에서 그해 과세되며 주 신고 시 Schedule CA 등 조정표에서 가산과 수익 신고를 해야 합니다. 이 조정은 퇴사로 달라지지 않습니다. 퇴사 후에도 HSA를 계속 보유하고 사용하는 한 매년 해야 합니다. 반면 § 125의 건강 FSA와 부양가족 돌봄 FSA의 세전 처리는 캘리포니아가 대체로 연방 틀을 따르며, 세부 사항은 FTB 현행 설명이 기준입니다.

보충 2 (퇴사 주간의 행동 목록): 먼저 인사나 계획 관리자에게 날짜 세 개를 받아 두십시오. 보장 종료일, run-out 제출 마감일, 계획 연도 종료일입니다. 보장 기간 안에 발생한 의료비는 run-out 마감 전에 청구를 마치고 영수증과 EOB를 보관하십시오. COBRA 선거 통지를 받으면 먼저 underspent 계산을 해 보고 건강 FSA를 이어갈지 정하십시오. COBRA는 일반적으로 60일의 선거 기간이 있고 선택하면 소급 적용됩니다. HSA는 손댈 필요가 없지만, 수탁자를 바꾸고 싶으면 60일 롤오버의 기한과 횟수 제한을 피할 수 있는 trustee-to-trustee 직접 이전을 우선하십시오.

### Bổ sung Tiếng Việt (bản dịch sơ bộ · 初译待校)

Bổ sung 1 (California không theo chế độ HSA liên bang): California không công nhận ưu đãi thuế liên bang của HSA: khoản đóng HSA không được khấu trừ và không được loại trừ khỏi lương chịu thuế ở cấp bang, còn lãi, cổ tức và lợi nhuận đầu tư trong tài khoản bị đánh thuế California trong năm phát sinh, phải cộng lại và khai trên bảng điều chỉnh của bang (Schedule CA) khi khai thuế bang. Việc nghỉ việc không thay đổi điều này: chừng nào còn giữ và dùng HSA sau khi nghỉ, điều chỉnh bang phải làm hằng năm. Ngược lại, xử lý trước thuế của health FSA và dependent care FSA theo § 125 thì California nhìn chung theo khung liên bang, chi tiết theo hướng dẫn FTB hiện hành.

Bổ sung 2 (việc cần làm trong tuần nghỉ việc): Trước hết hãy lấy ba mốc ngày từ phòng nhân sự hoặc bên quản lý chương trình: ngày chấm dứt bảo hiểm, hạn cuối nộp hồ sơ run-out, và ngày kết thúc năm chương trình. Các chi phí y tế phát sinh trong thời gian còn bảo hiểm phải nộp xong trước hạn run-out, giữ lại biên lai và EOB. Khi nhận thông báo lựa chọn COBRA, hãy làm phép tính underspent trước rồi mới quyết định có tiếp tục health FSA hay không; COBRA thường có thời hạn lựa chọn 60 ngày và có hiệu lực hồi tố sau khi chọn. HSA không cần động vào; nếu muốn đổi bên ủy thác, hãy ưu tiên chuyển trực tiếp trustee-to-trustee để tránh giới hạn thời hạn và số lần của rollover 60 ngày.

### हिन्दी पूरक (प्रारंभिक अनुवाद · 初译待校)

पूरक 1 (California का HSA-अनुसरण न करना): California HSA की संघीय कर-व्यवस्था को नहीं मानता: HSA योगदान राज्य स्तर पर न कटौती योग्य है न वेतन से अपवर्जित, और खाते के भीतर का ब्याज, लाभांश व निवेश लाभ California में उसी वर्ष करयोग्य है, राज्य रिटर्न में Schedule CA जैसे समायोजन पत्रक पर जोड़कर घोषित करना होता है। नौकरी छोड़ने से यह नहीं बदलता: जब तक HSA रखा व इस्तेमाल किया जाता है, राज्य समायोजन हर वर्ष करना होगा। इसके विपरीत § 125 के health FSA व dependent care FSA की पूर्व-कर व्यवस्था में California मोटे तौर पर संघीय ढाँचे का पालन करता है, विवरण वर्तमान FTB मार्गदर्शन से लें।

पूरक 2 (छोड़ने वाले सप्ताह की कार्य-सूची): पहले मानव संसाधन या plan प्रशासक से तीन तिथियाँ लें: कवरेज समाप्ति तिथि, run-out जमा की अंतिम तिथि, और plan वर्ष की समाप्ति तिथि। कवरेज के भीतर हुए चिकित्सा ख़र्च run-out अंतिम तिथि से पहले जमा कर दें और रसीदें व EOB संभालकर रखें। COBRA चुनाव सूचना मिलने पर पहले underspent गणना करें, फिर तय करें कि health FSA जारी रखना है या नहीं; COBRA में सामान्यतः 60 दिन की चुनाव अवधि होती है और चुनने पर यह पूर्वव्यापी होती है। HSA को छूने की ज़रूरत नहीं; custodian बदलना हो तो 60-दिन rollover की समय-सीमा व संख्या-सीमा से बचने के लिए trustee-to-trustee सीधा स्थानांतरण प्राथमिकता दें।
