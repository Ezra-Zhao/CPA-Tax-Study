# 信托与遗产税备考核心：Subchapter J 与 Form 706／709 及加州口径

> 板块：CPA备考（REG／TCP）· 法源：Internal Revenue Code Subchapter J（§§ 641–692）、§ 642(b)、§ 645、§ 651／652、§ 661／662、§ 663(b)、§ 2010、§ 2032、§ 2503(b)；表格 Form 1041、Form 706、Form 709；加州口径：无州级遗产税、赠与税与继承税，但有信义所得税（Form 541）。年度数字以 IRS 当年公告为准；算例为自编教学数字、已复算勾稽。

## 中文

### 一、总纲：半实体、半穿透

§ 641 先立主体：遗产与信托是独立的所得税纳税主体，自己报 Form 1041、用一套压缩得很陡的信托税率表。紧接着 §§ 651／661 与 §§ 652／662 又把它打穿：当年分配给受益人的金额，在实体层面换成分配扣除（distribution deduction），在受益人层面计入所得——同一笔钱只征一次税，征在谁手里，取决于分出去多少、以及可分配净收入（DNI）有多大。三个配套件先钉住：一是个人免税额 § 642(b)：遗产 600 美元、简单信托 300 美元、复杂信托 100 美元。二是 DNI 一数三用：既是实体分配扣除的上限，也是受益人计入所得的上限，还是分配额在各类所得之间分摊性质的比例尺。三是性质保留：免税利息分到受益人手里还是免税利息，股息还是股息，靠 DNI 的比例分摊实现。

### 二、DNI：§ 643(a) 定义与可复算算例

§ 643(a) 把 DNI 定义为实体「修正后的应税所得」：不算分配扣除与个人免税额，并做关键调整——免税利息算进来（扣掉分摊其上的费用后的净额）；归于本金（corpus）的资本利得原则上剔出去（§ 643(a)(3)，除非当年实际分出或按文书计入可分配收入），归本金的资本损失同理。

自编算例（复杂信托，已勾稽）。当年：股息 50,000 美元、应税利息 30,000 美元、免税利息 20,000 美元；长期资本利得 15,000 美元归本金；受托人佣金 10,000 美元从收入中支付，按收入构成比例分摊。

1. 分摊：应税收入 80,000 占总收入 100,000 的 80%，佣金 8,000 美元可扣；免税占 20%，佣金 2,000 美元不可扣、只冲减免税净额。
2. 修正后应税所得＝80,000 − 8,000＝72,000 美元；免税净额＝20,000 − 2,000＝18,000 美元。
3. DNI＝72,000＋18,000＝**90,000 美元**。归本金的利得 15,000 不进 DNI：信托经济收入 105,000（115,000 − 10,000），DNI 只有 90,000，差额正是那笔利得——这是最爱考的分岔。

当年分配 75,000 美元（甲 50,000、乙 25,000，2∶1）。免税占 DNI 之比＝18,000 ÷ 90,000＝20%，故 75,000 中免税 15,000、应税 60,000。逐人拆：甲计入应税 40,000、免税 10,000；乙计入应税 20,000、免税 5,000，合计对平。实体侧：分配扣除只扣应税部分＝**60,000 美元**（§ 661 以 DNI 为限并剔除免税成分）；信托自身应税所得＝72,000 − 60,000 − 100（复杂信托免税额）＝**11,900 美元**。没分完的 DNI 与被剔掉的资本利得留在实体层面纳税，钱的去向与税的去向一一对应。

### 三、简单信托与复杂信托：§§ 651／652 对 §§ 661／662

分界线只有一条：**简单信托**（simple trust）须文书要求当年收入全部分配、不分本金、不做慈善捐赠，走 § 651／§ 652，受益人计入不分层级、以 DNI 为顶。不满足这三条的都是**复杂信托**（complex trust），走 § 661／§ 662 并启用两层制：第一层是文书要求必须分配的当年收入，优先吸收 DNI；第二层是其余一切实际分出额（裁量分配、本金分配），在余额内吸收。两层合计仍以 DNI 为顶，超出部分对受益人一般是免税的本金返还。慈善捐赠扣除 § 642(c) 只在实体层面走、不进 DNI 分摊。遗产没有简单／复杂之分，直接套 §§ 661／662。另记 § 663(a)：指定给特定受益人的定额赠与或遗赠，若一次性或不超过三期付清，不算分配、不带出 DNI。

### 四、时间与选举：§ 663(b) 65 天规则与 § 645

**§ 663(b)**：年度结束后 65 天内实际支付的分配，可选举视为在上一年度最后一天支付，把年初分配拉回上一年吸收上年 DNI，避免 DNI 留在实体层面被陡峭税率先咬一口。**§ 645 选举**：合格可撤销信托的受托人与遗产执行人可共同选举把信托并入遗产按一个主体申报，换取遗产待遇：600 美元免税额、可选财政年度等。选举期自死亡日起算分两档：须报 Form 706 的，到 706 申报期限（含延期）后 6 个月届满；不须报的，为死亡后 2 年——REG 的高频数字题。

### 五、转移税两表：Form 706 与 Form 709

**Form 706（遗产税）**：应税遗产＝总遗产（§§ 2031 起）减债务、丧葬与管理费用、慈善与婚姻扣除等，乘累进税率后用 § 2010 统一抵免（unified credit）抵掉。其对应的适用排除额逐年由 IRS 公告：2025 年基本排除额 13,990,000 美元（Rev. Proc. 2024-40）。已婚者的可携额（portability，§ 2010(c)(4)）：先亡配偶未用完的排除额（DSUE）可转给在世配偶，但必须在先亡一侧及时申报 706 选举——这是「没欠税也要报 706」的头号理由。**§ 2032 估值日选举**：可选死亡后 6 个月之日估值，但只有该选举同时使总遗产价值与遗产税额都下降时才可用，且对全部资产一致适用。

**Form 709（赠与税）**：与 706 共用一套统一抵免。生前赠与先吃 § 2503(b) 年度排除，按受赠人逐人算：2025 年每位受赠人 19,000 美元，2026 年同为 19,000 美元（具体年份以 IRS 当年通胀调整公告为准）；超出部分为应税赠与，先耗统一抵免、耗尽才实际缴税，逐年累计并最终在 706 合并结算。夫妻分赠 § 2513 可把一方送出的礼物视为各送一半、年度排除翻倍，须双方同意并在 709 表明。§ 2503(e)：直接付给教育机构的学费、直接付给医疗提供者的医疗费不算赠与且无上限——「直接付给机构」是要件，给孩子钱再由孩子交就不算。

### 六、加州口径：转移税是零，信义所得税不是零

加州自 1982 年选民通过 Proposition 6 废除州继承税与赠与税后，**没有州级遗产税、赠与税与继承税**，至今未恢复；别因华盛顿州、俄勒冈州有州遗产税就顺手给加州编一个。但空白只限转移税：遗产与信托在加州仍有所得税，报 Form 541，信托的加州来源所得与受益人居民身份影响分摊。一句话：转移免税、所得有税，分开记。

### 七、易错清单

一，先算 DNI 再谈分配：扣除之顶、计入之顶、性质之尺都是它。二，利得归本金不进 DNI；费用须按应税／免税比例分摊。三，简单信托三要件缺一即复杂；第一层先吸 DNI。四，§ 645 选举期两档别记串；65 天规则只挪所得税时点。五，706 的可携额靠及时申报锁定；§ 2032 须价值与税额双降。六，709 年度排除逐人算，2026 年 19,000 美元以 IRS 公告为准；§ 2503(e) 必须直付机构。七，加州无转移税，但 Form 541 照报。

---

## English

**Trusts, estates, and transfer taxes: Subchapter J, Form 706, and Form 709.** Under § 641 an estate or trust is its own taxpayer filing Form 1041, but §§ 651/661 give the entity a distribution deduction and §§ 652/662 tax beneficiaries on distributions — income is taxed once, to the entity if retained and to the beneficiary if distributed, capped both ways by distributable net income (DNI). Exemptions under § 642(b): $600 (estate), $300 (simple trust), $100 (complex trust). DNI (§ 643(a)) is modified taxable income without the distribution deduction or exemption, including tax-exempt interest net of allocable expenses and generally excluding capital gains allocated to corpus (§ 643(a)(3)).

Worked example (teaching figures, tied out). A complex trust has dividends of $50,000, taxable interest of $30,000, tax-exempt interest of $20,000, a $15,000 capital gain allocated to corpus, and trustee commissions of $10,000. Allocating commissions pro rata, $8,000 is deductible and $2,000 reduces the tax-exempt component. Modified taxable income = $72,000; net tax-exempt interest = $18,000; **DNI = $90,000**. The trust distributes $75,000 ($50,000 to A, $25,000 to B); the tax-exempt share of DNI is 20%, so $15,000 is exempt and $60,000 taxable (A: $40,000 taxable, $10,000 exempt; B: $20,000, $5,000). The distribution deduction is $60,000, and the trust's own taxable income = $72,000 − $60,000 − $100 = **$11,900**.

A simple trust must distribute all income currently, no corpus, no charitable gifts (§§ 651/652, no tiers); all else is complex under §§ 661/662 with two tiers — required distributions absorb DNI first, discretionary distributions absorb the remainder. Specific bequests paid in one sum or at most three installments are not distributions (§ 663(a)). The § 663(b) 65-day rule treats distributions paid within 65 days after year-end as paid on the prior year's last day if elected; a § 645 election taxes a qualified revocable trust as part of the estate (period: two years after death, or six months after the Form 706 due date with extensions if a return is required).

Transfer taxes: Form 706 applies graduated rates to the gross estate less deductions, offset by the § 2010 unified credit (basic exclusion $13,990,000 for 2025, Rev. Proc. 2024-40); portability of the deceased spousal unused exclusion (DSUE) requires a timely Form 706 election, and § 2032's alternate valuation date (six months after death) is available only if it reduces both the gross estate and the tax. Form 709 reports gifts: the § 2503(b) annual exclusion is per donee — $19,000 for 2025 and $19,000 for 2026, per the IRS announcement for the year — taxable gifts absorb the same unified credit over a lifetime, § 2513 gift-splitting lets a married couple double the exclusion, and § 2503(e) excludes tuition and medical amounts paid directly to the institution or provider, without limit. California has had no state estate, gift, or inheritance tax since 1982 (Proposition 6), but estates and trusts still file the fiduciary income tax return, Form 541.

---

## Español (初译待校)

**Fideicomisos, sucesiones y transferencia: Subchapter J, Form 706 y Form 709.** Según la § 641, la sucesión o el fideicomiso es contribuyente propio (Form 1041), pero las §§ 651/661 dan a la entidad una deducción por distribuciones y las §§ 652/662 gravan al beneficiario: el límite en ambos sentidos es el ingreso neto distribuible (DNI, § 643(a)), que incluye el interés exento neto de gastos y excluye las ganancias de capital atribuidas al principal (§ 643(a)(3)). Exenciones § 642(b): $600 sucesiones, $300 fideicomiso simple, $100 complejo.

Ejemplo verificado: dividendos $50.000, intereses gravables $30.000, intereses exentos $20.000, ganancia de capital de $15.000 al principal y comisiones de $10.000. Reparto proporcional: $8.000 deducibles y $2.000 reducen el componente exento. Ingreso modificado = $72.000; interés exento neto = $18.000; **DNI = $90.000**. Distribución de $75.000 (A $50.000, B $25.000): el componente exento es el 20% del DNI, así que $15.000 son exentos y $60.000 gravables (A: $40.000 y $10.000; B: $20.000 y $5.000). Deducción por distribución: $60.000; ingreso propio del fideicomiso = $72.000 − $60.000 − $100 = **$11.900**.

El fideicomiso simple debe distribuir todo el ingreso, sin principal ni caridad; el complejo sigue los dos niveles de §§ 661/662. La regla de 65 días (§ 663(b)) retrotrae distribuciones pagadas en los 65 días siguientes al cierre, y la elección § 645 grava un fideicomiso revocable calificado como parte de la sucesión. El Form 706 liquida el impuesto sobre sucesiones con el crédito unificado § 2010 (exclusión básica de $13.990.000 en 2025) y portabilidad del DSUE solo con presentación oportuna; la § 2032 exige que la valoración alternativa a los seis meses reduzca a la vez caudal e impuesto. El Form 709 declara donaciones: exclusión anual § 2503(b) por donatario, $19.000 en 2025 y $19.000 en 2026 según el anuncio del IRS; § 2513 permite dividir entre cónyuges y § 2503(e) excluye sin límite matrícula y gastos médicos pagados directamente a la institución. California no tiene impuesto estatal de sucesiones, donaciones ni herencias desde 1982, pero sí el Form 541 fiduciario.

---

## 한국어 (初译待校)

**신탁·유산 과세 핵심: Subchapter J와 Form 706/709.** § 641상 유산·신탁은 Form 1041을 내는 독립 납세자이지만 §§ 651/661이 주체에 분배공제를, §§ 652/662가 수익자에게 과세를 하며, 양쪽 상한은 분배가능순소득 DNI(§ 643(a))이다. DNI에는 비용을 뺀 면세이자가 포함되고 본금 귀속 자본이득은 빠진다(§ 643(a)(3)). § 642(b) 공제는 유산 600달러, 단순신탁 300달러, 복잡신탁 100달러이다.

검산 예시: 배당 50,000달러, 과세이자 30,000달러, 면세이자 20,000달러, 본금 귀속 자본이득 15,000달러, 수수료 10,000달러. 수수료 비례 배분 시 8,000달러 공제, 2,000달러는 면세분을 줄인다. 수정 과세소득 72,000달러, 순면세이자 18,000달러, **DNI = 90,000달러**. 75,000달러 분배(A 50,000, B 25,000)는 면세 비율 20%에 따라 면세 15,000, 과세 60,000이다(A 과세 40,000·면세 10,000, B 과세 20,000·면세 5,000). 분배공제 60,000달러, 신탁 자체 과세소득 = 72,000 − 60,000 − 100 = **11,900달러**.

단순신탁은 소득 전액 분배·본금 분배 금지·자선 금지가 요건이고, 복잡신탁은 §§ 661/662의 2단계 구조를 따른다. § 663(b) 65일 규칙, § 645 선택(적격 철회가능신탁을 유산의 일부로 과세)도 알아둘 것. Form 706은 § 2010 통합공제(2025년 기본공제 13,990,000달러)로 계산하고 DSUE 이월은 기한 내 신고가 필요하며, § 2032 대체 평가일은 총유산과 세액이 모두 줄 때만 가능하다. Form 709의 § 2503(b) 연간 제외는 수증자 1인당 2025년·2026년 모두 19,000달러(연도별 IRS 공고 확인), § 2513 부부 분할, § 2503(e) 기관 직접납부 학비·의료비 무제한 제외가 있다. 캘리포니아는 1982년 이후 주 유산세·증여세·상속세가 없지만 Form 541 신탁소득세는 있다.

---

## Tiếng Việt (初译待校)

**Thuế tín thác, di sản và chuyển nhượng: Subchapter J, Form 706 và Form 709.** Theo § 641, di sản hoặc tín thác là người nộp thuế độc lập (Form 1041), nhưng §§ 651/661 cho thực thể khấu trừ phân phối và §§ 652/662 đánh thuế người thụ hưởng; giới hạn hai chiều là DNI (§ 643(a)), gồm lãi miễn thuế sau chi phí phân bổ và loại trừ lãi vốn ghi vào gốc (§ 643(a)(3)). Miễn trừ § 642(b): di sản $600, tín thác đơn giản $300, phức tạp $100.

Ví dụ đã đối chiếu: cổ tức $50.000, lãi chịu thuế $30.000, lãi miễn thuế $20.000, lãi vốn $15.000 ghi vào gốc, phí ủy thác $10.000. Phân bổ phí theo tỷ lệ: $8.000 được khấu trừ, $2.000 giảm phần miễn thuế. Thu nhập đã điều chỉnh = $72.000; lãi miễn thuế ròng = $18.000; **DNI = $90.000**. Phân phối $75.000 (A $50.000, B $25.000): tỷ lệ miễn thuế 20%, nên $15.000 miễn thuế và $60.000 chịu thuế (A: $40.000 và $10.000; B: $20.000 và $5.000). Khấu trừ phân phối $60.000; thu nhập của tín thác = $72.000 − $60.000 − $100 = **$11.900**.

Tín thác đơn giản phải phân phối toàn bộ thu nhập, không phân phối gốc, không từ thiện; tín thác phức tạp theo hệ hai tầng §§ 661/662. Quy tắc 65 ngày § 663(b) và lựa chọn § 645 (đánh thuế tín thác có thể thu hồi như một phần của di sản) cần nắm. Form 706 dùng tín dụng thống nhất § 2010 (loại trừ cơ bản 2025 là $13.990.000), DSUE chỉ chuyển được khi khai 706 đúng hạn; § 2032 chỉ cho ngày định giá thay thế sau 6 tháng khi cả tổng di sản và thuế đều giảm. Form 709: loại trừ hằng năm § 2503(b) theo từng người nhận, $19.000 cho 2025 và $19.000 cho 2026 theo thông báo của IRS; § 2513 chia quà vợ chồng; § 2503(e) loại trừ không giới hạn học phí, y tế trả trực tiếp cho tổ chức. California không có thuế di sản, quà tặng, thừa kế cấp bang từ 1982, nhưng vẫn có Form 541.

---

## हिन्दी (初译待校)

**ट्रस्ट, संपदा और हस्तांतरण कर: Subchapter J, Form 706 और Form 709.** § 641 के अंतर्गत संपदा या ट्रस्ट Form 1041 भरने वाला स्वतंत्र करदाता है, किंतु §§ 651/661 इकाई को वितरण कटौती देते हैं और §§ 652/662 लाभार्थी को कर लगाते हैं; दोनों दिशाओं की सीमा DNI (§ 643(a)) है, जिसमें आवंटनीय व्यय घटाकर कर-मुक्त ब्याज शामिल होता है और मूलधन में जाने वाला पूंजीगत लाभ बाहर रहता है (§ 643(a)(3))। § 642(b) छूट: संपदा $600, सरल ट्रस्ट $300, जटिल ट्रस्ट $100।

जाँचा गया उदाहरण: लाभांश $50,000, करयोग्य ब्याज $30,000, कर-मुक्त ब्याज $20,000, मूलधन में जाने वाला पूंजीगत लाभ $15,000, ट्रस्टी शुल्क $10,000। शुल्क के आनुपातिक आवंटन पर $8,000 कटौती-योग्य, $2,000 कर-मुक्त भाग घटाता है। संशोधित करयोग्य आय = $72,000; शुद्ध कर-मुक्त ब्याज = $18,000; **DNI = $90,000**। $75,000 वितरण (A $50,000, B $25,000) में कर-मुक्त अनुपात 20% है, इसलिए $15,000 मुक्त और $60,000 करयोग्य (A: $40,000 करयोग्य, $10,000 मुक्त; B: $20,000 करयोग्य, $5,000 मुक्त)। वितरण कटौती $60,000; ट्रस्ट की अपनी करयोग्य आय = $72,000 − $60,000 − $100 = **$11,900**।

सरल ट्रस्ट के लिए आय का पूर्ण वितरण, मूलधन वितरण नहीं और धर्मार्थ दान नहीं अनिवार्य है; जटिल ट्रस्ट §§ 661/662 की दो-स्तरीय व्यवस्था मानता है। § 663(b) 65-दिन नियम और § 645 चुनाव (योग्य निरसनीय ट्रस्ट को संपदा के भाग के रूप में कर) भी महत्वपूर्ण हैं। Form 706 § 2010 एकीकृत क्रेडिट (2025 में मूल अपवर्जन $13,990,000) से चलता है; DSUE पोर्टेबिलिटी के लिए समय पर 706 आवश्यक है; § 2032 वैकल्पिक मूल्यांकन तिथि तभी, जब सकल संपदा और कर दोनों घटें। Form 709 में § 2503(b) वार्षिक अपवर्जन प्रति प्राप्तकर्ता है — 2025 और 2026 दोनों में $19,000, वर्ष की IRS घोषणा के अधीन — साथ में § 2513 दान-विभाजन और § 2503(e) संस्था को सीधे भुगतान की शिक्षण व चिकित्सा राशि का असीमित अपवर्जन। California में 1982 से राज्य संपदा, दान या विरासत कर नहीं है, किंतु Form 541 बना हुआ है।

---

声明（六语）：个人学习笔记，不构成税务建议。

Disclaimer: Personal study notes only; not tax advice.

Aviso: Notas personales de estudio; no constituye asesoría fiscal. (初译待校)

고지: 개인 학습 노트이며 세무 자문이 아닙니다. (初译待校)

Lưu ý: Ghi chú học tập cá nhân, không phải tư vấn thuế. (初译待校)

टिप्पणी: व्यक्तिगत अध्ययन नोट है, कर सलाह नहीं है। (初译待校)
