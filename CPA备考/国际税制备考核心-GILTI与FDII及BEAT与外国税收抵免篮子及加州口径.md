# 国际税制备考核心：GILTI、FDII、BEAT 与外国税收抵免篮子及加州口径

TCJA（2017 年税改）把美国国际税制从「全球征税加递延」改成「参与豁免加三道反避税闸门」。备考要抓的骨架只有四块：§245A 的参与豁免作底盘，§951A 的 GILTI、§250 的 FDII、§59A 的 BEAT 三件套作闸门，外加 §904 外国税收抵免（FTC）的分篮计算。条号、比例与生效口径按现行法（2026 年适用规则：GILTI 与 FDII 的 §250 扣除比例经 2025 年立法调整——GILTI 扣除 40%、FDII 扣除 33.34%，对应有效税率约 12.6% 与约 14.0%，答题以题目给定的考试年度口径为准）核对。

## 中文主文

### 底盘：§245A 参与豁免与 Subpart F 的老地基

美国公司股东从受控外国公司（CFC）取得的股息，符合 §245A（持股 10% 以上、持有期等要件）可享 100% 股息扣除，等于对已在海外纳税的利润回流不再课美国税。但豁免之前先有两层穿透：Subpart F（§§951–965）把 CFC 的特定被动与关联交易所得当年穿透给美国股东；§956 的对美投资规则已基本被 §245A 时代的规则架空（2019 年最终法规使公司股东的 §956 纳入额降到与 §245A 扣除相抵的程度）。混合股息（hybrid dividend）不给 §245A 扣除，这是高频陷阱。

### GILTI：§951A 的计算链

GILTI 的公式要默写到分毫不差：美国股东的 GILTI 纳入额＝净 CFC 测试所得（net CFC tested income）－净认定有形收入回报（net deemed tangible income return）。后者＝合格商业资产投资（QBAI）的 10%－特定利息费用。测试所得为负的 CFC 产生 tested loss，不产生 QBAI 利益的跨期结转（GILTI 本身没有亏损结转，这是它与 Subpart F 的重要区别）。公司股东依 §250(a)(1)(B) 对 GILTI 享扣除（现行 40%），并依 §960(d) 就 GILTI 对应的外国税享 80% 的间接抵免，且 GILTI 篮子的抵免不得结转——多缴的外国税在 GILTI 篮子里过期作废，这一点与一般篮子形成对照，必考。个人直接持股 CFC 则没有 §250 扣除，除非作 §962 选举按公司税率计税并享间接抵免。

### FDII：§250 的另一半

FDII 鼓励把无形资产留在美国：公司取得的外国来源扣除可分配所得（deduction eligible income 中归属外国使用部分）超过认定有形回报（QBAI 的 10%）的部分即 FDII，享 §250(a)(1)(A) 扣除（现行 33.34%），把出口型无形所得的有效税率拉到与 GILTI 大体对称的水平。计算顺序是先算 DEI（扣除可分配所得，剔除 Subpart F、GILTI、股息等项目），再分 FDDEI（外国来源部分），最后减有形回报。GILTI 与 FDII 共用 §250 的应税所得上限：两者扣除合计超过应税所得时按比例削减——这是计算题的固定机关。

### BEAT：§59A 对着付款流的闸门

BEAT 盯的是美国公司向外国关联方的大额可扣除付款（基数侵蚀付款）。适用门槛：三年平均总收入不低于 5 亿美元，且基数侵蚀百分比不低于 3%（银行与证券商 2%）。税额＝10%（现行税率档；银行类纳税人加 1 个百分点）乘修改后应税所得（MTI＝常规应税所得＋基数侵蚀付款加回）－经调整的常规税。服务成本加成法下符合条件的服务付款、无加成部分可获豁免（services cost method 例外，且该部分不计入基数侵蚀百分比的分子分母有条件处理）。BEAT 与常规税取其大，与 GILTI 可以叠加但计算顺序独立。

### FTC 分篮：§904(d) 的四个篮子

现行外国税收抵免分四个篮子：被动类（passive）、一般类（general）、§951A 类（GILTI 篮子）、外国分支类（foreign branch）。抵免上限＝美国税前总税额×（该篮子外国来源应税所得÷全球应税所得），费用分摊（§861–865 与利息分摊规则）先行压低各篮子的外国来源所得，是计算题真正的杀分点。超限抵免一般可前转 1 年、后转 10 年（§904(c)），唯独 GILTI 篮子不得结转。可抵免税种须满足 §901/903 与 2022 年最终法规的可抵免性要求（归属要求 attribution requirement 使若干数字服务税类的新型税种出局）。§960 的间接抵免分工：Subpart F 走 §960(a)，GILTI 走 §960(d) 的 80%，§245A 股息对应的外国税既不可抵免也不可扣除（§245A(d)）。

### 加州口径：加州没有跟上联邦的这套

加州《收入与税法典》对国际税制的对接是断裂的：加州没有 GILTI、FDII、BEAT 的对应制度，也没有 §245A 式参与豁免。加州对跨国集团用合并申报与全球/水缘（water's-edge）选举（Rev. & Tax. Code §25110 一带）处理外国成员：水缘选举把外国子公司大部分排除在合并组外，只纳入特定项目；CFC 的 Subpart F 类所得在加州按股息性质与 factor 表示法处理，税率与扣除按州法另行计算。备考与实务都要提醒：联邦的 GILTI 纳入额到了加州不是自动应税所得，必须回到加州的合并申报与分配公式重算，这正是跨国企业州税争议的高发区。

### 参考依据

- IRC §§ 245A、250、59A、861–865、901–909（§904(c)/(d)、§960）、951–965（§951A、§956、§962）
- TCJA, Pub. L. 115-97；§250 扣除比例经 2025 年立法（Pub. L. 119-21）调整为 GILTI 40%、FDII 33.34%（2026 年起）
- Reg. §1.951A 系列（GILTI 最终法规）；2022 年 FTC 最终法规（可抵免性与归属要求）
- 加州 Rev. & Tax. Code §25110（water's-edge 选举）与 FTB 合并申报规则

### 免责声明

个人学习笔记，不构成税务建议。

## English

### The Architecture

The TCJA replaced worldwide taxation with deferral by a participation exemption policed by three anti-abuse gates. Section 245A gives a domestic corporation a 100% dividends-received deduction for the foreign-source portion of dividends from a 10%-owned foreign corporation — but hybrid dividends are excluded. Subpart F (§§ 951–965) still passes specified CFC income through currently, while §956 has been largely neutralized for corporate shareholders by the 2019 regulations.

### GILTI (§ 951A)

A U.S. shareholder's GILTI inclusion equals net CFC tested income minus the net deemed tangible income return (10% of QBAI, reduced by specified interest expense). Tested losses produce no carryforward — a deliberate contrast with other regimes. Corporate shareholders claim the § 250 deduction for GILTI (40% under current law, for an effective rate of about 12.6%) and an 80% deemed-paid credit under § 960(d); excess credits in the § 951A basket cannot be carried over at all. Individuals get no § 250 deduction unless they elect under § 962.

### FDII (§ 250)

FDII rewards keeping intangibles in the United States: the portion of deduction-eligible income attributable to foreign use, above a 10% QBAI deemed tangible return, receives the § 250 deduction (33.34% currently, effective rate about 14.0%). GILTI and FDII share § 250's taxable-income limitation, which prorates both deductions when taxable income is insufficient — a standard computational trap.

### BEAT (§ 59A)

The base erosion and anti-abuse tax targets large deductible payments to foreign related parties. It applies to groups with at least $500 million of average annual gross receipts and a base erosion percentage of at least 3% (2% for banks and securities dealers). The tax is the excess of the applicable rate (10%, plus 1 point for banks) of modified taxable income — regular taxable income plus base erosion payments added back — over adjusted regular tax. A services-cost-method exception shelters the no-markup portion of qualifying service payments.

### Foreign Tax Credit Baskets (§ 904(d))

Credits are computed separately in four baskets: passive, general, § 951A (GILTI), and foreign branch. The limitation is U.S. tax times foreign-source taxable income in the basket over worldwide taxable income, after expense apportionment — the real point-loser in exam computations. Excess credits generally carry back 1 year and forward 10 (§ 904(c)), except the GILTI basket, which allows no carryover. Taxes must satisfy the creditability requirements of §§ 901/903 as tightened by the 2022 final regulations, and foreign taxes on § 245A dividends are neither creditable nor deductible (§ 245A(d)).

### California

California has no GILTI, FDII, BEAT, or § 245A analogue. Multinationals are handled through combined reporting and the water's-edge election (Rev. & Tax. Code § 25110), which excludes most foreign subsidiaries from the combined group. A federal GILTI inclusion is not automatically California taxable income; the combined report and apportionment formula must be recomputed under state law.

### References

IRC §§ 245A, 250, 59A, 904, 951A, 960; TCJA, Pub. L. 115-97; 2025 legislation (Pub. L. 119-21) setting § 250 percentages; Reg. § 1.951A; 2022 FTC final regulations; Cal. Rev. & Tax. Code § 25110.

### Disclaimer

Personal study notes, not tax advice.

## Español

### La arquitectura

La TCJA sustituyó la tributación mundial con diferimiento por una exención de participación vigilada por tres puertas antiabuso. La sección 245A concede a las sociedades nacionales una deducción del 100% por dividendos de fuente extranjera de participadas al 10% o más; los dividendos híbridos quedan excluidos. Subpart F (§§ 951–965) sigue imputando en el año ciertas rentas de las CFC, mientras la § 956 quedó en gran parte neutralizada para accionistas corporativos por la reglamentación de 2019.

### GILTI (§ 951A)

La inclusión GILTI de un accionista estadounidense es la renta neta probada de las CFC menos el rendimiento tangible presunto neto (10% del QBAI, reducido por gastos de intereses específicos). Las pérdidas probadas no generan arrastre alguno. Las sociedades accionistas aplican la deducción de la § 250 para GILTI (40% según la ley vigente, tipo efectivo cercano al 12,6%) y un crédito indirecto del 80% bajo la § 960(d); el exceso de crédito en la cesta § 951A no puede arrastrarse en ningún caso. Las personas físicas no tienen deducción § 250 salvo elección bajo la § 962.

### FDII (§ 250)

FDII premia mantener los intangibles en EE. UU.: la parte de la renta elegible atribuible a uso extranjero que supere el rendimiento tangible presunto (10% del QBAI) recibe la deducción de la § 250 (33,34% en la ley vigente, tipo efectivo aproximado del 14,0%). GILTI y FDII comparten el límite de renta imponible de la § 250, que prorratea ambas deducciones si la renta no alcanza: trampa clásica de cálculo.

### BEAT (§ 59A)

El impuesto contra la erosión de bases se dirige a los grandes pagos deducibles a vinculadas extranjeras. Aplica a grupos con ingresos brutos medios de al menos 500 millones de dólares y un porcentaje de erosión del 3% o más (2% para bancos y corredores de valores). El impuesto es el exceso del tipo aplicable (10%, más un punto para bancos) sobre la renta imponible modificada — la renta ordinaria más la reincorporación de los pagos erosionantes — frente al impuesto ordinario ajustado. El método de costo de servicios protege la parte sin margen de ciertos pagos de servicios.

### Las cestas del crédito por impuestos extranjeros (§ 904(d))

El crédito se calcula por separado en cuatro cestas: pasiva, general, § 951A (GILTI) y sucursal extranjera. El límite es el impuesto estadounidense multiplicado por la renta de fuente extranjera de la cesta dividida entre la renta mundial, tras la imputación de gastos — el punto donde se pierden más notas en el examen. El exceso se arrastra 1 año atrás y 10 adelante (§ 904(c)), salvo en la cesta GILTI, sin arrastre alguno. Los impuestos deben cumplir los requisitos de acreditabilidad de §§ 901/903 según la reglamentación final de 2022, y los impuestos sobre dividendos § 245A no son acreditables ni deducibles (§ 245A(d)).

### California

California no tiene equivalentes de GILTI, FDII, BEAT ni de la § 245A. Los grupos multinacionales se tratan con declaración combinada y la elección water's-edge (Rev. & Tax. Code § 25110), que excluye a la mayoría de las filiales extranjeras del grupo combinado. Una inclusión GILTI federal no es automáticamente renta imponible en California; hay que recalcular el informe combinado y la fórmula de reparto según la ley estatal.

### Referencias

IRC §§ 245A, 250, 59A, 904, 951A, 960; TCJA, Pub. L. 115-97; legislación de 2025 (Pub. L. 119-21) sobre porcentajes de la § 250; Reg. § 1.951A; reglamentación final FTC de 2022; Rev. & Tax. Code de California § 25110.

### Aviso

Notas personales de estudio; no constituyen asesoría fiscal.

## 한국어 (초역 · 初译待校)

### 구조

TCJA는 이연을 동반한 전세계 과세를 참여면세(participation exemption)와 세 개의 남용방지 장치로 바꿨다. §245A는 국내 법인이 10% 이상 보유한 외국법인으로부터 받는 배당의 외국원천 부분에 100% 배당공제를 허용하되, 하이브리드 배당은 제외된다. Subpart F(§§951–965)는 CFC의 특정 소득을 여전히 당해 연도에 귀속시키고, §956은 2019년 규정으로 법인 주주에 대해 사실상 무력화되었다.

### GILTI (§951A)

미국 주주의 GILTI 포함액은 순 CFC 테스트소득에서 순 간주유형소득수익(QBAI의 10%에서 특정 이자비용을 차감)을 뺀 금액이다. 테스트 손실은 이월되지 않는다. 법인 주주는 GILTI에 대해 §250 공제(현행 40%, 실효세율 약 12.6%)와 §960(d)에 따른 80% 간주간주납부세액공제를 받으며, §951A 바스켓의 초과 공제는 전혀 이월할 수 없다. 개인은 §962 선택을 하지 않으면 §250 공제를 받을 수 없다.

### FDII (§250)

FDII는 무형자산을 미국에 두도록 유도한다. 외국 사용에 귀속되는 공제가능소득 중 간주유형수익(QBAI의 10%)을 넘는 부분이 §250 공제(현행 33.34%, 실효세율 약 14.0%)를 받는다. GILTI와 FDII는 §250의 과세소득 한도를 공유하며, 과세소득이 부족하면 두 공제가 비례 축소된다. 계산 문제의 단골 함정이다.

### BEAT (§59A)

기반침식·남용방지세는 외국 특수관계자에 대한 대규모 공제가능 지급을 겨냥한다. 연평균 총수입 5억 달러 이상이고 기반침식 비율이 3% 이상(은행·증권사는 2%)인 그룹에 적용된다. 세액은 수정과세소득(일반 과세소득에 기반침식 지급을 가산)에 적용세율(10%, 은행은 1%포인트 가산)을 곱한 금액에서 조정된 일반세를 뺀 초과분이다. 서비스원가법 예외는 요건을 갖춘 서비스 지급의 무마진 부분을 보호한다.

### 외국납부세액공제 바스켓 (§904(d))

공제는 수동, 일반, §951A(GILTI), 외국지점의 네 바스켓별로 따로 계산한다. 한도는 해당 바스켓의 외국원천 과세소득이 전세계 과세소득에서 차지하는 비율에 미국 세액을 곱한 것으로, 비용 배분이 먼저 이루어지는 것이 감점 포인트다. 초과 공제는 일반적으로 1년 소급·10년 이월(§904(c))이 가능하나 GILTI 바스켓은 이월이 없다. 세액은 2022년 최종 규정이 강화한 §§901/903의 공제가능 요건을 충족해야 하고, §245A 배당에 대한 외국세는 공제도 손금도 되지 않는다(§245A(d)).

### 캘리포니아

캘리포니아에는 GILTI, FDII, BEAT, §245A에 대응하는 제도가 없다. 다국적 그룹은 결합신고와 water's-edge 선택(Rev. & Tax. Code §25110)으로 처리되며, 대부분의 외국 자회사가 결합 그룹에서 제외된다. 연방 GILTI 포함액이 자동으로 캘리포니아 과세소득이 되지는 않으며, 주법에 따라 결합보고와 배분 공식을 다시 계산해야 한다.

### 참고 근거

IRC §§245A, 250, 59A, 904, 951A, 960; TCJA, Pub. L. 115-97; §250 비율에 관한 2025년 입법(Pub. L. 119-21); Reg. §1.951A; 2022년 FTC 최종 규정; 캘리포니아 Rev. & Tax. Code §25110.

### 면책

개인 학습 노트이며 세무 조언이 아니다.

## Tiếng Việt (Bản dịch sơ bộ · 初译待校)

### Kiến trúc

TCJA đã thay chế độ đánh thuế toàn cầu kèm hoãn thuế bằng miễn thuế tham gia (participation exemption) được canh giữ bởi ba cổng chống lạm dụng. §245A cho công ty trong nước khấu trừ 100% phần cổ tức nguồn nước ngoài từ công ty con nước ngoài nắm giữ từ 10% trở lên; cổ tức lai (hybrid) bị loại. Subpart F (§§951–965) vẫn quy kết một số thu nhập của CFC vào năm hiện hành, còn §956 phần lớn đã bị vô hiệu hóa với cổ đông công ty theo quy định năm 2019.

### GILTI (§951A)

Khoản GILTI của cổ đông Hoa Kỳ bằng thu nhập kiểm tra ròng của CFC trừ đi lợi nhuận hữu hình giả định ròng (10% QBAI, trừ chi phí lãi vay xác định). Lỗ kiểm tra không được chuyển sang năm sau. Cổ đông công ty được khấu trừ §250 cho GILTI (hiện 40%, thuế suất thực tế khoảng 12,6%) và tín dụng gián tiếp 80% theo §960(d); tín dụng thừa trong giỏ §951A không được chuyển tiếp chút nào. Cá nhân không có khấu trừ §250 trừ khi bầu chọn theo §962.

### FDII (§250)

FDII khuyến khích giữ tài sản vô hình tại Hoa Kỳ: phần thu nhập đủ điều kiện khấu trừ thuộc về sử dụng ở nước ngoài, vượt trên lợi nhuận hữu hình giả định (10% QBAI), được khấu trừ §250 (hiện 33,34%, thuế suất thực tế khoảng 14,0%). GILTI và FDII dùng chung giới hạn thu nhập chịu thuế của §250; khi thu nhập chịu thuế không đủ, cả hai khoản khấu trừ bị cắt theo tỷ lệ — bẫy tính toán quen thuộc.

### BEAT (§59A)

Thuế chống xói mòn cơ sở nhắm vào các khoản thanh toán lớn được khấu trừ cho bên liên quan nước ngoài. Áp dụng cho nhóm có tổng doanh thu bình quân từ 500 triệu đô la và tỷ lệ xói mòn từ 3% (2% với ngân hàng và công ty chứng khoán). Thuế là phần vượt của thuế suất áp dụng (10%, ngân hàng cộng 1 điểm) nhân với thu nhập chịu thuế đã sửa đổi — thu nhập chịu thuế thông thường cộng lại các khoản thanh toán xói mòn — so với thuế thông thường đã điều chỉnh. Ngoại lệ phương pháp giá vốn dịch vụ bảo vệ phần không có phụ phí của một số khoản thanh toán dịch vụ.

### Các giỏ tín dụng thuế nước ngoài (§904(d))

Tín dụng được tính riêng trong bốn giỏ: thụ động, chung, §951A (GILTI) và chi nhánh nước ngoài. Giới hạn bằng thuế Hoa Kỳ nhân với tỷ lệ thu nhập nguồn nước ngoài của giỏ trên thu nhập toàn cầu, sau khi phân bổ chi phí — điểm mất điểm chính trong bài thi. Tín dụng thừa thường được chuyển ngược 1 năm và chuyển tiếp 10 năm (§904(c)), ngoại trừ giỏ GILTI không cho chuyển tiếp. Thuế phải đáp ứng yêu cầu được tín dụng của §§901/903 theo quy định cuối cùng năm 2022, và thuế nước ngoài trên cổ tức §245A không được tín dụng cũng không được khấu trừ (§245A(d)).

### California

California không có chế độ tương đương GILTI, FDII, BEAT hay §245A. Các tập đoàn đa quốc gia được xử lý bằng khai thuế hợp nhất và bầu chọn water's-edge (Rev. & Tax. Code §25110), theo đó hầu hết công ty con nước ngoài nằm ngoài nhóm hợp nhất. Khoản GILTI ở cấp liên bang không tự động thành thu nhập chịu thuế California; phải tính lại báo cáo hợp nhất và công thức phân bổ theo luật bang.

### Tài liệu tham khảo

IRC §§245A, 250, 59A, 904, 951A, 960; TCJA, Pub. L. 115-97; luật năm 2025 (Pub. L. 119-21) về tỷ lệ §250; Reg. §1.951A; quy định cuối cùng FTC 2022; Rev. & Tax. Code California §25110.

### Tuyên bố miễn trừ

Ghi chép học tập cá nhân, không phải tư vấn thuế.

## हिन्दी (प्रारंभिक अनुवाद · 初译待校)

### ढाँचा

TCJA ने स्थगन सहित विश्वव्यापी कराधान को भागीदारी छूट (participation exemption) और तीन दुरुपयोग-रोधी द्वारों से बदल दिया। §245A घरेलू निगम को 10% या अधिक धारित विदेशी निगम से मिले लाभांश के विदेशी-स्रोत भाग पर 100% लाभांश-कटौती देता है; हाइब्रिड लाभांश बाहर हैं। Subpart F (§§951–965) CFC की निर्दिष्ट आय को उसी वर्ष में आरोपित करता रहता है, जबकि §956 को 2019 के नियमों ने निगम शेयरधारकों के लिए काफ़ी हद तक निष्प्रभावी कर दिया।

### GILTI (§951A)

अमेरिकी शेयरधारक की GILTI समावेशन राशि शुद्ध CFC परीक्षित आय में से शुद्ध अभिप्रेत मूर्त आय प्रतिफल (QBAI का 10%, निर्दिष्ट ब्याज व्यय घटाकर) घटाने पर मिलती है। परीक्षित हानियों का कोई अग्रनयन नहीं होता। निगम शेयरधारक GILTI पर §250 कटौती (वर्तमान में 40%, प्रभावी दर लगभग 12.6%) और §960(d) के तहत 80% अप्रत्यक्ष क्रेडिट पाते हैं; §951A बास्केट का अतिरिक्त क्रेडिट बिल्कुल आगे नहीं बढ़ाया जा सकता। व्यक्तियों को §962 चुनाव के बिना §250 कटौती नहीं मिलती।

### FDII (§250)

FDII अमूर्त संपत्ति को अमेरिका में रखने को प्रोत्साहित करता है: कटौती-योग्य आय का वह भाग जो विदेशी उपयोग से जुड़ा है और अभिप्रेत मूर्त प्रतिफल (QBAI का 10%) से ऊपर है, उसे §250 कटौती (वर्तमान में 33.34%, प्रभावी दर लगभग 14.0%) मिलती है। GILTI और FDII §250 की करयोग्य-आय सीमा साझा करते हैं; करयोग्य आय अपर्याप्त हो तो दोनों कटौतियाँ अनुपात से घटती हैं — गणना प्रश्नों का जाना-माना जाल।

### BEAT (§59A)

आधार-क्षरण और दुरुपयोग-रोधी कर विदेशी संबंधित पक्षों को बड़े कटौती-योग्य भुगतानों को निशाना बनाता है। यह उन समूहों पर लागू है जिनकी औसत वार्षिक सकल प्राप्तियाँ कम से कम 50 करोड़ डॉलर हों और आधार-क्षरण प्रतिशत कम से कम 3% (बैंक व प्रतिभूति व्यापारियों के लिए 2%) हो। कर, संशोधित करयोग्य आय — सामान्य करयोग्य आय में आधार-क्षरण भुगतानों को वापस जोड़कर — पर लागू दर (10%, बैंकों के लिए 1 अंक अधिक) और समायोजित सामान्य कर के अंतर के बराबर है। सेवा-लागत विधि का अपवाद योग्य सेवा भुगतानों के बिना-मार्जिन भाग को बचाता है।

### विदेशी कर क्रेडिट बास्केट (§904(d))

क्रेडिट चार बास्केटों में अलग-अलग गिना जाता है: निष्क्रिय, सामान्य, §951A (GILTI) और विदेशी शाखा। सीमा अमेरिकी कर गुणा उस बास्केट की विदेशी-स्रोत करयोग्य आय बटा विश्वव्यापी करयोग्य आय है, और व्यय-आवंटन पहले होता है — यही परीक्षा में अंक कटवाता है। अतिरिक्त क्रेडिट सामान्यतः 1 वर्ष पीछे और 10 वर्ष आगे (§904(c)) जाता है, परंतु GILTI बास्केट में अग्रनयन वर्जित है। करों को 2022 के अंतिम नियमों से कड़ी की गई §§901/903 की क्रेडिट-योग्यता शर्तें पूरी करनी होंगी, और §245A लाभांश पर विदेशी कर न क्रेडिट योग्य है न कटौती योग्य (§245A(d))।

### कैलिफ़ोर्निया

कैलिफ़ोर्निया में GILTI, FDII, BEAT या §245A जैसा कोई प्रावधान नहीं है। बहुराष्ट्रीय समूहों को संयुक्त रिपोर्टिंग और water's-edge चुनाव (Rev. & Tax. Code §25110) से निपटाया जाता है, जिसमें अधिकांश विदेशी सहायक कंपनियाँ संयुक्त समूह से बाहर रहती हैं। संघीय GILTI समावेशन अपने-आप कैलिफ़ोर्निया करयोग्य आय नहीं बनता; राज्य कानून के तहत संयुक्त रिपोर्ट और विभाजन सूत्र की पुनर्गणना करनी होती है।

### संदर्भ

IRC §§245A, 250, 59A, 904, 951A, 960; TCJA, Pub. L. 115-97; §250 प्रतिशतों पर 2025 का विधान (Pub. L. 119-21); Reg. §1.951A; 2022 FTC अंतिम नियम; कैलिफ़ोर्निया Rev. & Tax. Code §25110।

### अस्वीकरण

व्यक्तिगत अध्ययन नोट्स हैं, कर सलाह नहीं।
