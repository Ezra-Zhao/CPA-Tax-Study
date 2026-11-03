# 合伙企业税务备考核心：Subchapter K 出资、分配与基数

> 板块：CPA 备考（REG／TCP）· 法源：Internal Revenue Code Subchapter K（§§ 701–777），重点条文 § 701、§ 702、§ 704(b)、§ 704(c)、§ 707、§ 721、§ 722、§ 723、§ 731、§ 732、§ 736、§ 751、§ 752；法规 Treas. Reg. §§ 1.704-1、1.704-3、1.707-3、1.752-2、1.752-3；IRS Publication 541（Partnerships）；加州口径：FTB Form 565 与 Form 568 说明。

## 中文

### 一、先立总纲：合伙不缴税，人缴税

Subchapter K 的第一句话永远是 § 701：合伙企业本身不缴联邦所得税，应税所得穿透到合伙人，合伙人就其分配份额（distributive share）纳税，不管钱有没有实际分到手。配套的是 § 702：份额里的各类所得、利得、损失与扣除在合伙人层面大体保留原性质，须单独列报的项目单独穿透，合伙人在 Form 1065 的 Schedule K-1 上拿数、在自己的税表上报。考试里凡是问「合伙企业层面确认多少应税所得」，先想 § 701——实体层面答案通常是零，文章全在合伙人与基数上。

基数是这套规则的中轴，而且有两条，方向别弄反：合伙人对合伙权益的基数叫外部基数（outside basis），合伙对合伙人出资财产的基数叫内部基数（inside basis）。外部基数管合伙人个人的利得上限与损失可扣额度，内部基数管合伙卖财产时算多少利得。两条基数独立变动，差额正是 § 743(b) 调整（须有 § 754 选择）那类进阶题目的来源，本篇只点名，不展开。

### 二、出资：§ 721 不确认，§ 722 与 § 723 定两条基数

**§ 721(a)**：合伙人以财产出资换取合伙权益，合伙人与合伙双方一般都不确认利得或损失。这是 K 章的免税大门，与公司法的 § 351 有亲缘，但没有 § 351 的控制权门槛，适用面更宽。例外要记两个：一是 § 721(b)——出资给「投资公司型」合伙（贡献后资产高度集中于证券等）时出资人要确认利得；二是出资财产在七年内又分回给其他合伙人等情形会牵动 § 704(c)(1)(B) 与 § 737，不属 § 721 的平静适用区。

**§ 722（外部基数起点）**：合伙人初始外部基数＝出资的现金金额＋出资财产的调整后基数（adjusted basis），再加出资时确认的利得（如 § 721(b) 情形）。注意用的是出资财产的基数，不是公允价值——升值部分不因出资而实现，这正是内置利得被「冻」进合伙的原因，也直接引出 § 704(c)。

**§ 723（内部基数）**：合伙取得出资财产的基数＝出资合伙人手中的基数（结转基数），再加该合伙人在出资时确认的利得。出资环节两条基数在这一点上对称：贡献进来的是基数，不是价值。

**§ 752（负债进基数，最爱考的一条）**：合伙人分担的合伙负债份额增加，视同该合伙人向合伙出资现金，外部基数相应增加（§ 752(a)）；负债份额减少，视同合伙向合伙人分配现金，外部基数相应减少，减过头还会触发 § 731 利得（§ 752(b)）。有追索权负债（recourse）按经济损失风险分担（Treas. Reg. § 1.752-2，谁最终可能真金白银掏钱谁分）；无追索权负债（nonrecourse）按 Treas. Reg. § 1.752-3 的三层法分配：合伙最低利得（partnership minimum gain）份额、§ 704(c) 内置利得份额、超出部分按利润份额等合理方法。一句话：借钱不进所得，但进基数——负债是 K 章基数的放大器，也是分配环节的隐形现金。

### 三、可复算数字小例：初始外部基数一步不跳

合伙人 A 出资组建 AB 合伙：出现金 30,000 美元，另出资一块土地，公允价值 50,000 美元、A 手中基数 20,000 美元；合伙成立时有一笔 A 应分担份额为 10,000 美元的负债。

- § 721(a)：A 与合伙均不确认利得。土地升值的 30,000 美元（50,000 − 20,000）没有实现，只是被冻结。
- § 722 外部基数＝现金 30,000＋土地基数 20,000＋负债份额 10,000（§ 752(a) 视同现金出资）＝**60,000 美元**。
- § 723 内部基数：合伙对土地的基数＝**20,000 美元**（结转，不是 50,000）。
- § 704(c) 预热：日后合伙以 50,000 美元卖地，合伙层面利得＝50,000 − 20,000＝30,000 美元，这 30,000 美元先全额分给 A——就是出资时冻结的那笔内置利得，见下节。
- 分配验算：若合伙随后向 A 分配现金 40,000 美元，40,000＜60,000，按 § 731(a) 不确认利得，A 的外部基数降为 60,000 − 40,000＝20,000 美元；若分配现金 65,000 美元，超出基数的 65,000 − 60,000＝**5,000 美元**才是 A 要确认的利得。同一条算式，(REG 论述与计算题反复换皮考的就是它。

### 四、经营分配份额：§ 704(b) 管约定算不算数，§ 704(c) 管内置损益

**§ 704(a)/(b)**：合伙人的分配份额原则上按合伙协议定；但一项分配（allocation）若想被税法尊重，必须有实质经济效果（substantial economic effect）——经典两步检验是：合伙人资本账户按 Treas. Reg. § 1.704-1(b)(2)(iv) 维护、清算按资本账户正余额结算、赤字合伙人负有补足义务（或有合格收入抵销等替代安排），且该分配在经济上是实质性的（substantiality，看税后经济地位是否真随之变动）。过不了检验，份额就按「合伙人对合伙的利益」（partner's interest in the partnership）重算。

**§ 704(c)(1)(A)**：出资财产的内置利得或损失，在合伙计税时必须用合理方法把出资时「基数与公允价值之差」归到出资人头上，不能让其他合伙人分走或背上。三种常用方法（Treas. Reg. § 1.704-3）：传统法（traditional method，受天花板规则 ceiling rule 限制，分不够时只能认了）、传统法加补救性项目（curative allocations，用其他项目补差）、补救法（remedial method，合伙造出名义项目一次补平）。答题口诀：内置的先归出资人，剩下的再按协议分。

### 五、实际分配：§ 731／§ 732，钱先行、亏损基本不认

**§ 731(a)**（合伙人侧）：分配中只有「钱」（money，含 § 752(b) 的负债份额减少视同分钱、§ 731(c) 下可交易证券按规则视同钱）超过合伙人分配前外部基数的部分，才确认利得；损失原则上不确认，唯一例外是清算分配且只收到钱、可交易证券与未实现应收款时，未用完的基数可认损失（§ 731(a)(2)）。**§ 731(b)**（合伙侧）：合伙因分配不确认任何利得或损失。

**§ 732**（受分配财产的基数）：非清算分配中，财产基数先取合伙的内部基数，但封顶于「外部基数减去同笔分配中收到的钱」后的余额，多项财产按 § 732(c) 顺序在未实现应收款、存货与其它财产间分配；清算分配中，受分配财产的基数直接等于合伙人剩余外部基数（减去收到的钱），是基数的「用尽」机制。**§ 751** 另设热资产红线：未实现应收款与存货类项目在分配中比例失衡（§ 751(b)）会被拟制为合伙与合伙人之间的买卖，普通所得藏不住。**§ 737** 再补一刀：出资人七年内收到其他财产分配，超出其（经调整）基数的净内置利得要确认。

### 六、两处一瞥：§ 707 隐蔽销售与 § 736 退伙支付

**§ 707(a)(2)(B) 隐蔽销售（disguised sale）**：名为「出资＋分配」的一对交易，实质是合伙人把财产卖给合伙——判断看全部事实，Treas. Reg. § 1.707-3 给了时间推定：出资与分配在两年内相互关联发生的，推定为销售；相隔两年以上的，推定不是（均可反驳）。中招的后果是出资环节的 § 721 免税被拆掉，按真实买卖确认利得。合伙人以合伙人身份之外与合伙交易（如卖货、借钱）则走 § 707(a)(1)，按非合伙人对待。

**§ 736 退伙与身故合伙人支付**：向退出或已故合伙人（的继承人）支付分两类。（b）类是为换取其在合伙财产中权益的支付，按分配处理（走 § 731／§ 732），但不包括未实现应收款，商誉也只有合伙协议约定支付时才算（服务型合伙的普通合伙人另有特别限制）；（a）类是其余支付，按分配份额或有保证支付（guaranteed payment）处理，一般是普通所得性质。这条是 TCP 与实务题的常客，本篇只要求能先把一笔退伙款拆成（a）（b）两筐，性质再分别判断。

### 七、加州一瞥：Form 565 与 LLC 的税与费别混

联邦穿透不等于加州没动作，分清主体形态再看表：一般合伙与有限合伙在加州报 **Form 565**（合伙信息申报），合伙本身一般不缴加州所得税，税由合伙人各自承担。被归类为合伙课税的 **LLC** 报的是 **Form 568**，而且 LLC 层面有两笔钱，性质完全不同：一是 § 17941 的年度税（annual tax）800 美元，定额；二是 Rev. & Tax. Code § 17942 的 LLC 费（LLC fee），按来源于加州的总收入分档计征——250,000 美元起征 900 美元，500,000 美元档 2,500 美元，1,000,000 美元档 6,000 美元，5,000,000 美元以上 11,790 美元（以 FTB 当年 Form 568 说明为准）。把 800 美元年度税和按收入分档的费混成一笔，是加州口径题最常见的丢分点；Form 565 的普通合伙则没有这两笔 LLC 专属负担，不要张冠李戴。

### 八、备考易错清单

一，§ 701 的「合伙不缴税」是实体层面的零，不是「不用申报」——Form 1065 信息申报照交，合伙人按 K-1 报份额。

二，外部基数用出资财产的基数（§ 722），不是公允价值；公允价值只在 § 704(c) 内置利得与经济效果检验里出场。

三，负债份额增加是加基数（§ 752(a) 视同出资），减少是减基数并视同分钱（§ 752(b)）——减少减过头，先想 § 731 利得。

四，分配的利得只由「钱超基数」触发（§ 731(a)），财产分配本身一般不触发利得；损失只在清算分配的窄情形下才认。

五，§ 704(b) 检验的是「分配约定算不算数」，§ 704(c) 处理的是「出资时已存在的内置损益归谁」，两条的触发点一个在协议、一个在出资财产，别混。

六，隐蔽销售看两年推定（§ 707），出资财产七年内分回牵动 § 704(c)(1)(B)／§ 737——「两年」与「七年」是 K 章两个不能记串的时间点。

---

## 参考依据

- Internal Revenue Code §§ 701、702、704(b)、704(c)、707(a)、721、722、723、731、732、736、737、751、752；Treas. Reg. §§ 1.704-1(b)、1.704-3、1.707-3、1.752-2、1.752-3。
- IRS Publication 541, Tax Information on Partnerships（出资、基数与分配的行政口径）。
- California Rev. & Tax. Code §§ 17941（LLC 年度税 800 美元）、17942（LLC 费分档）；FTB Form 565 与 Form 568 说明。文中 LLC 费分档数字以 FTB 公布的现行说明为准；算例数字为自编教学数字，非官方数据。

---

## English

**Partnership taxation under Subchapter K: contributions, allocations, distributions, and basis.** Authorities: IRC § 701 (a partnership pays no entity-level federal income tax; partners are taxed on their distributive shares), § 702 (character retention and separately stated items, reported on Schedule K-1); § 721(a) (nonrecognition on contribution of property for a partnership interest, by both partner and partnership — note the § 721(b) investment-company exception); § 722 (a partner's initial outside basis equals money contributed plus the adjusted basis of property contributed, plus any gain recognized on the contribution); § 723 (the partnership's inside basis in contributed property is a carryover basis, plus gain recognized by the contributor); § 752 (an increase in a partner's share of partnership liabilities is treated as a contribution of money and raises outside basis under § 752(a); a decrease is treated as a distribution of money under § 752(b); recourse debt follows economic risk of loss under Reg. § 1.752-2, nonrecourse debt follows the three-tier method of Reg. § 1.752-3).

Allocations: an allocation in the partnership agreement is respected only if it has substantial economic effect under § 704(b) (capital accounts maintained under Reg. § 1.704-1(b)(2)(iv), liquidation by positive capital accounts, and a deficit restoration obligation or an accepted alternative, plus substantiality); otherwise shares are redetermined by the partner's interest in the partnership. Under § 704(c)(1)(A), built-in gain or loss in contributed property must be allocated back to the contributor using a reasonable method — traditional (subject to the ceiling rule), traditional with curative allocations, or remedial (Reg. § 1.704-3).

Distributions: under § 731(a) a partner recognizes gain only to the extent money distributed (including liability relief under § 752(b) and, under § 731(c), marketable securities treated as money) exceeds outside basis immediately before the distribution; loss is generally barred except in a liquidating distribution of only money, marketable securities, and unrealized receivables (§ 731(a)(2)). The partnership recognizes nothing (§ 731(b)). Basis of distributed property is set by § 732 — partnership's basis capped by remaining outside basis in a current distribution, and a substituted remaining-basis rule in liquidation — with § 732(c) ordering among asset classes, § 751 policing hot assets (unrealized receivables and inventory), and § 737 taxing a contributor who receives other property within seven years.

Worked example (teaching figures, fully checkable): A contributes $30,000 cash plus land with a fair market value of $50,000 and a basis of $20,000, and is allocated a $10,000 share of partnership liabilities. Section 721(a): no gain to anyone; the $30,000 of appreciation is frozen, not realized. Outside basis under §§ 722 and 752(a) = 30,000 + 20,000 + 10,000 = **$60,000**. Inside basis in the land under § 723 = **$20,000**. If the partnership later sells the land for $50,000, the $30,000 partnership gain is allocated first to A under § 704(c). A cash distribution of $40,000 produces no gain (40,000 < 60,000) and reduces A's outside basis to $20,000; a cash distribution of $65,000 produces gain of 65,000 − 60,000 = **$5,000** under § 731(a).

Two glances: § 707(a)(2)(B) disguised sales — a contribution paired with a related distribution may be recast as a sale, with Reg. § 1.707-3 presuming a sale when the two legs occur within two years (and presuming none when more than two years apart, both rebuttable). Section 736 splits payments to a retiring or deceased partner into § 736(b) payments for the partner's interest in partnership property (distribution treatment; unrealized receivables excluded, goodwill only if the agreement so provides, with a special limit for general partners in service partnerships) and § 736(a) payments (distributive share or guaranteed payment, generally ordinary in character).

California glance: general and limited partnerships file Form 565 as an information return and generally pay no California income tax at the entity level. An LLC taxed as a partnership files Form 568 and owes two different entity-level amounts that must not be conflated: the flat $800 annual tax (Rev. & Tax. Code § 17941) and the income-based LLC fee (§ 17942) — $900 once California total income reaches $250,000, then $2,500 at $500,000, $6,000 at $1,000,000, and $11,790 at $5,000,000 or more (per current FTB Form 568 instructions). A Form 565 partnership has neither LLC charge.

*Disclaimer: This article is a personal study note and does not constitute tax advice. For specific matters, consult a licensed CPA or tax attorney.*

---

## Español (初译待校)

**Impuestos de las sociedades colectivas (partnerships), Subchapter K: aportaciones, asignaciones, distribuciones y base.** Reglas centrales: § 701, la partnership no paga impuesto federal a nivel de entidad; cada socio tributa por su parte distributiva (§ 702, Schedule K-1). § 721(a): la aportación de bienes a cambio de una participación no genera ganancia ni pérdida para socio ni partnership (excepción: § 721(b), partnerships de inversión). § 722: la base externa inicial del socio es el dinero aportado más la base ajustada de los bienes aportados. § 723: la base interna de la partnership en el bien aportado es la base trasladada del aportante. § 752: el aumento de la parte de deudas de la partnership se trata como aportación de dinero y sube la base externa (§ 752(a)); la disminución se trata como distribución de dinero (§ 752(b)); las deudas con recurso siguen el riesgo económico de pérdida (Reg. § 1.752-2) y las sin recurso el método de tres niveles (Reg. § 1.752-3).

Asignaciones: § 704(b) solo respeta la asignación del acuerdo si tiene efecto económico sustancial; § 704(c) obliga a devolver al aportante la ganancia o pérdida incorporada (built-in) del bien aportado (métodos tradicional —con la regla del techo—, con asignaciones curativas, o remedial, Reg. § 1.704-3). Distribuciones: § 731(a), el socio solo reconoce ganancia cuando el dinero distribuido (incluido el alivio de deudas) supera su base externa; la pérdida casi nunca se reconoce; la partnership no reconoce nada (§ 731(b)); la base del bien distribuido la fija § 732, con § 751 para los activos calientes y § 737 para distribuciones al aportante dentro de siete años.

Ejemplo verificable (cifras didácticas): A aporta $30,000 en efectivo y un terreno con valor de mercado de $50,000 y base de $20,000, y asume una parte de deuda de $10,000. Base externa = 30,000 + 20,000 + 10,000 = **$60,000**; base interna del terreno = **$20,000**; si el terreno se vende en $50,000, la ganancia de $30,000 se asigna primero a A por § 704(c). Una distribución de $40,000 no genera ganancia y deja la base en $20,000; una de $65,000 genera ganancia de **$5,000** por § 731(a). Además: § 707(a)(2)(B), ventas disfrazadas (presunción de venta si aportación y distribución ocurren dentro de dos años, Reg. § 1.707-3); § 736, pagos al socio que se retira o fallece, divididos entre (b) por su interés en los bienes y (a) resto. California: las partnerships presentan el Form 565 informativo, sin impuesto estatal a nivel de entidad; una LLC gravada como partnership presenta el Form 568 y paga dos cosas distintas: el impuesto anual fijo de $800 (§ 17941) y la cuota según ingresos LLC fee (§ 17942): $900 desde $250,000, $2,500 desde $500,000, $6,000 desde $1,000,000 y $11,790 desde $5,000,000.

*Aviso: Este artículo es una nota personal de estudio y no constituye asesoría fiscal. Para asuntos concretos, consulte a un CPA con licencia o a un abogado fiscalista. Traducción inicial pendiente de revisión (初译待校).*

---

## 한국어 (初译待校)

**파트너십 과세(Subchapter K): 출자·배분·분배와 베이시스.** § 701: 파트너십 자체는 연방 소득세를 내지 않고, 각 파트너가 자기 배분 몫(distributive share)에 대해 과세된다(§ 702, Schedule K-1). § 721(a): 재산 출자에 대해서는 파트너와 파트너십 모두 손익을 인식하지 않는다(예외 § 721(b) 투자회사형). § 722: 파트너의 외부 베이시스(outside basis) 출발점은 출자한 현금과 출자 재산의 조정 베이시스의 합이다. § 723: 파트너십이 취득한 재산의 내부 베이시스(inside basis)는 출자자의 베이시스를 승계한다. § 752: 파트너십 부채 지분의 증가는 현금 출자로 보아 외부 베이시스를 올리고(§ 752(a)), 감소는 현금 분배로 보아 내리며(§ 752(b)), 소구채무는 경제적 손실위험(Reg. § 1.752-2), 비소구채무는 3단계 방법(Reg. § 1.752-3)을 따른다.

배분: § 704(b)는 배분이 실질적 경제효과(substantial economic effect)를 가질 때만 존중한다. § 704(c)는 출자 재산에 내재된 손익(built-in)을 출자자에게 먼저 귀속시킨다(전통법과 천장규칙, 치유 배분, 보정법; Reg. § 1.704-3). 분배: § 731(a)상 파트너는 분배받은 현금(부채 경감 포함)이 직전 외부 베이시스를 초과하는 부분에 대해서만 이익을 인식하고, 손실은 원칙적으로 청산분배의 좁은 경우에만 인정된다. 파트너십은 § 731(b)에 따라 아무것도 인식하지 않는다. 분배 재산의 베이시스는 § 732가 정하고, § 751은 핫 자산, § 737은 7년 내 출자자 반환을 다룬다.

검산 가능한 예시(교수용 수치): A가 현금 30,000달러와 시가 50,000달러·베이시스 20,000달러인 토지를 출자하고 부채 지분 10,000달러를 배정받았다. 외부 베이시스 = 30,000 + 20,000 + 10,000 = **60,000달러**. 토지의 내부 베이시스 = **20,000달러**. 토지를 50,000달러에 팔면 파트너십 이익 30,000달러는 § 704(c)에 따라 먼저 A에게 간다. 현금 40,000달러 분배는 이익이 없고 베이시스가 20,000달러로 줄며, 65,000달러 분배는 65,000 − 60,000 = **5,000달러**의 이익을 만든다. 그 밖에 § 707(a)(2)(B) 위장 매각(2년 내 출자와 분배가 짝을 이루면 매각으로 추정, Reg. § 1.707-3)과 § 736 탈퇴·사망 파트너 지급((b) 재산 지분 대가와 (a) 그 외 지급으로 구분)을 알아둘 것. 캘리포니아: 일반·유한 파트너십은 Form 565 정보 신고를 하고 주체 단계 주 소득세는 일반적으로 없지만, 파트너십으로 과세되는 LLC는 Form 568을 내고 성격이 다른 두 가지를 낸다. 정액 연간세 800달러(§ 17941)와 총소득 구간별 LLC 수수료(§ 17942: 250,000달러부터 900달러, 500,000달러 2,500달러, 1,000,000달러 6,000달러, 5,000,000달러 이상 11,790달러)이다.

*고지: 본 글은 개인 학습 노트이며 세무 자문이 아닙니다. 구체적인 사안은 면허 CPA나 세무 변호사에게 상담하시기 바랍니다. 초역으로 교정 대기 중입니다 (初译待校).*

---

## Tiếng Việt (初译待校)

**Thuế đối với partnership, Subchapter K: góp vốn, phân bổ, phân phối và cơ sở tính thuế (basis).** § 701: partnership không nộp thuế thu nhập liên bang ở cấp thực thể; mỗi thành viên chịu thuế trên phần phân bổ của mình (§ 702, Schedule K-1). § 721(a): góp tài sản đổi lấy quyền lợi partnership thì cả thành viên lẫn partnership đều không ghi nhận lãi/lỗ (ngoại lệ § 721(b) đối với partnership dạng công ty đầu tư). § 722: basis bên ngoài (outside basis) ban đầu của thành viên bằng tiền mặt đã góp cộng basis đã điều chỉnh của tài sản góp. § 723: basis bên trong (inside basis) của partnership đối với tài sản góp là basis chuyển tiếp của người góp. § 752: phần nợ của partnership tăng lên được coi như góp tiền mặt, làm tăng outside basis (§ 752(a)); giảm xuống được coi như phân phối tiền mặt (§ 752(b)); nợ có truy đòi theo rủi ro tổn thất kinh tế (Reg. § 1.752-2), nợ không truy đòi theo phương pháp ba tầng (Reg. § 1.752-3).

Phân bổ: § 704(b) chỉ tôn trọng thỏa thuận phân bổ nếu có hiệu quả kinh tế thực chất (substantial economic effect). § 704(c) buộc phải quy phần lãi/lỗ tích sẵn (built-in) của tài sản góp về cho người góp trước (phương pháp truyền thống với quy tắc trần ceiling rule, phân bổ chữa trị curative, hoặc phương pháp remedial; Reg. § 1.704-3). Phân phối: theo § 731(a), thành viên chỉ ghi nhận lãi ở phần tiền phân phối (kể cả phần giảm nợ) vượt quá outside basis ngay trước phân phối; lỗ hầu như không được ghi nhận; partnership không ghi nhận gì (§ 731(b)); basis của tài sản được phân phối do § 732 quy định, § 751 xử lý tài sản nóng (hot assets), § 737 xử lý việc phân phối lại cho người góp trong bảy năm.

Ví dụ có thể tính lại (số liệu giảng dạy): A góp $30,000 tiền mặt và một lô đất có giá thị trường $50,000, basis $20,000, đồng thời được chia phần nợ $10,000. Outside basis = 30,000 + 20,000 + 10,000 = **$60,000**; inside basis của đất = **$20,000**; nếu partnership bán đất với giá $50,000, khoản lãi $30,000 được phân bổ trước cho A theo § 704(c). Phân phối tiền mặt $40,000 không phát sinh lãi và basis còn $20,000; phân phối $65,000 phát sinh lãi 65,000 − 60,000 = **$5,000** theo § 731(a). Cần liếc thêm: § 707(a)(2)(B) bán trá hình (disguised sale — góp vốn và phân phối trong vòng hai năm bị suy đoán là mua bán, Reg. § 1.707-3) và § 736 thanh toán cho thành viên rút lui hoặc qua đời (chia thành khoản (b) cho quyền lợi tài sản và khoản (a) còn lại). California: partnership nộp Form 565 mang tính thông tin, nói chung không có thuế thu nhập cấp thực thể của bang; LLC bị đánh thuế như partnership nộp Form 568 và nợ hai khoản khác hẳn nhau: thuế hằng năm cố định $800 (§ 17941) và phí LLC theo tổng thu nhập (§ 17942: $900 từ $250,000, $2,500 từ $500,000, $6,000 từ $1,000,000, $11,790 từ $5,000,000 trở lên).

*Tuyên bố: Bài viết này là ghi chú học tập cá nhân, không phải tư vấn thuế. Với việc cụ thể, hãy tham vấn CPA có giấy phép hoặc luật sư thuế. Bản dịch sơ bộ chờ hiệu đính (初译待校).*

---

## हिन्दी (初译待校)

**साझेदारी कराधान (Subchapter K): अंशदान, आवंटन, वितरण और आधार (basis).** § 701: साझेदारी स्वयं संघीय आयकर नहीं देती; प्रत्येक साझेदार अपने वितरणात्मक हिस्से (distributive share) पर कर देता है (§ 702, Schedule K-1)। § 721(a): संपत्ति के अंशदान पर न साझेदार, न साझेदारी लाभ-हानि मान्यता देती है (अपवाद: § 721(b) निवेश-कंपनी प्रकार)। § 722: साझेदार का प्रारंभिक बाहरी आधार (outside basis) = अंशदान की गई नकदी + अंशदान संपत्ति का समायोजित आधार। § 723: अंशदान संपत्ति में साझेदारी का आंतरिक आधार (inside basis) अंशदाता के आधार का ही हस्तांतरण है। § 752: साझेदारी ऋण में हिस्से की वृद्धि को नकद अंशदान मानकर बाहर का आधार बढ़ाया जाता है (§ 752(a)); कमी को नकद वितरण माना जाता है (§ 752(b)); recourse ऋण आर्थिक हानि-जोखिम (Reg. § 1.752-2) से, nonrecourse ऋण त्रि-स्तरीय विधि (Reg. § 1.752-3) से बँटता है।

आवंटन: § 704(b) करार के आवंटन को तभी मानता है जब उसका पर्याप्त आर्थिक प्रभाव (substantial economic effect) हो। § 704(c) अंशदान संपत्ति के अंतर्निहित लाभ-हानि (built-in) को पहले अंशदाता को लौटाता है (पारंपरिक विधि व ceiling rule, curative आवंटन, remedial विधि; Reg. § 1.704-3)। वितरण: § 731(a) के तहत साझेदार केवल उतनी राशि पर लाभ मानता है जितनी वितरित नकदी (ऋण-मुक्ति सहित) उसके बाहरी आधार से अधिक हो; हानि सामान्यतः मान्य नहीं; साझेदारी § 731(b) से कुछ नहीं मानती। वितरित संपत्ति का आधार § 732 तय करता है; § 751 hot assets और § 737 सात वर्ष के भीतर अंशदाता को वितरण संभालता है।

पुनर्गणना-योग्य उदाहरण (शिक्षण आँकड़े): A ने $30,000 नकद और बाज़ार मूल्य $50,000 व आधार $20,000 वाली भूमि का अंशदान किया, और उसे $10,000 ऋण-हिस्सा मिला। बाहरी आधार = 30,000 + 20,000 + 10,000 = **$60,000**; भूमि का आंतरिक आधार = **$20,000**; भूमि $50,000 में बिके तो $30,000 का लाभ § 704(c) से पहले A को जाएगा। $40,000 का नकद वितरण लाभ नहीं देता और आधार $20,000 रह जाता है; $65,000 का वितरण 65,000 − 60,000 = **$5,000** लाभ देता है (§ 731(a))। दो झलकियाँ: § 707(a)(2)(B) छद्म बिक्री (disguised sale — दो वर्ष के भीतर अंशदान और वितरण की जोड़ी बिक्री मानी जा सकती है, Reg. § 1.707-3) और § 736 सेवानिवृत्त/मृत साझेदार के भुगतान ((b) संपत्ति-हित के बदले और (a) शेष)। कैलिफ़ोर्निया: partnership Form 565 सूचना-विवरणी देती है, सामान्यतः इकाई-स्तर पर राज्य आयकर नहीं; partnership के रूप में कर-योग्य LLC Form 568 देती है और दो अलग राशियाँ देती है — नियत वार्षिक कर $800 (§ 17941) और कुल आय पर आधारित LLC शुल्क (§ 17942: $250,000 से $900, $500,000 पर $2,500, $1,000,000 पर $6,000, $5,000,000 या अधिक पर $11,790)।

*अस्वीकरण: यह लेख व्यक्तिगत अध्ययन नोट है और कर सलाह नहीं है। किसी विशिष्ट मामले के लिए लाइसेंस-प्राप्त CPA या कर वकील से परामर्श करें। प्रारंभिक अनुवाद, समीक्षा लंबित (初译待校)।*

---

*声明：本篇为个人学习笔记，不构成税务建议。具体事项请咨询持牌 CPA 或税务律师。*
*Disclaimer: This article is a personal study note and does not constitute tax advice. For specific matters, consult a licensed CPA or tax attorney.*
*Aviso: Este artículo es una nota personal de estudio y no constituye asesoría fiscal. Las versiones en español son traducción inicial pendiente de revisión (初译待校).*
*고지: 본 글은 개인 학습 노트이며 세무 자문이 아닙니다. 한국어 버전은 초역으로 교정 대기 중입니다 (初译待校).*
*Tuyên bố: Bài viết này là ghi chú học tập cá nhân, không phải tư vấn thuế. Phiên bản tiếng Việt là bản dịch sơ bộ chờ hiệu đính (初译待校).*
*अस्वीकरण: यह लेख व्यक्तिगत अध्ययन नोट है और कर सलाह नहीं है। हिन्दी संस्करण प्रारंभिक अनुवाद है, समीक्षा लंबित (初译待校)。*
