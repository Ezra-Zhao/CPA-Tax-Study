# 税收抵免投资备考核心：ASU 2023-02 把比例摊销法从 LIHTC 放宽到全部税收抵免结构

## 中文

### 一、先定性：比例摊销法到底在摊什么

比例摊销法（proportional amortization method, PAM）处理的是这样一类投资：企业出钱投进一个税收抵免结构（最典型的是低收入住房税收抵免 LIHTC 项目），图的不是项目本身的经营利润，而是项目分配来的税收抵免（tax credits）和其他税收利益。会计上如果按权益法硬套，投资的账面波动会跑进税前利润，把经营业绩搅浑。PAM 的处理是：把投资的初始成本按取得税收抵免的比例逐年摊销，摊销额与税收抵免、其他税收利益一起，统统放进所得税费用（income tax expense）这一行里列报——税前利润不受这项投资的扰动，全部影响落在税项里，与这类投资“买的就是税收利益”的经济实质对齐。

2023 年 3 月，FASB 发布 ASU 2023-02（《投资——权益法与合营企业（专题 323）：以比例摊销法核算税收抵免结构投资》），把 PAM 的适用范围从原来的 LIHTC 一类，扩展到满足条件的**所有税收抵免结构**——例如历史建筑修复抵免、新市场税收抵免、可再生能源抵免等结构，只要过得了第 323-740 节列的五项条件，都可以选用 PAM。

### 二、五项条件：第 323-740 节的入场券，缺一不可

选用 PAM 必须同时满足 ASC 323-740-25-1 的五项条件，考试逐项核：

1. **抵免大概率会来**：投资人取得该投资所产生的税收抵免，是大概率的（probable）。
2. **没有重大影响力**：投资人对被投资方的经营与财务政策不具有重大影响（significant influence）——有重大影响的，回权益法，不进 PAM。
3. **收益几乎全是税收利益**：投资预计收益中，绝大部分（substantially all）来自税收抵免和其他税收利益，而不是项目经营现金流。
4. **收益率只看税收利益**：投资人预计的收益率，在只计税收抵免和其他税收利益时为正——把经营收益拿掉，这笔投资靠税收利益本身就成立。
5. **责任封顶在出资额**：投资人的责任以其已投入的资本为限，不为项目债务兜底。

判别口诀：这笔投资如果把税收利益抽走就不值得做、投资人又管不了项目、赔也只赔出资额，它就是 PAM 的料。五项里任何一项不满足，改走权益法或按其他适用指引处理，并在报表附注中披露所选用的会计政策。

### 三、计量与列报：摊多少、放哪行

- **摊销节奏**：初始投资成本按各期取得的税收抵免占预计总抵免的比例摊销。教学算例（本地复算两遍一致）：投资成本 1,000,000 美元，预计总税收抵免 900,000 美元，第一年取得抵免 180,000 美元，则第一年摊销额等于 1,000,000 乘（180,000 除以 900,000）等于 1,000,000 乘 20% 等于 200,000 美元。抵免进度走多快，摊销就走多快，这是“比例”二字的来历。
- **列报位置**：摊销额与当期税收抵免、其他税收利益（如抵免结构带来的可抵扣亏损分配）一起，净额列在所得税费用一行。这是 PAM 与权益法最直观的区别：权益法下投资损益进税前，PAM 下全部进税项。
- **后续计量**：若预计抵免流发生变化或出现减值迹象，按第 323-740 节的后续计量与减值指引处理；投资人对超出账面金额的额外出资承诺等事项，另按相应指引确认负债。

### 四、生效与过渡：两档生效日，追溯或修正追溯

- **生效日分两档**：公众商业实体（public business entities）适用于 2023 年 12 月 15 日之后开始的财政年度（含中期期间）；其他实体推迟一年，适用于 2024 年 12 月 15 日之后开始的财政年度。允许提前采用。算一笔年份账：2024 减 2023 等于 1，两档正好错开一年（本地复算两遍一致）。
- **过渡方法**：可选用追溯法（retrospective）或修正追溯法（modified retrospective）过渡到新指引，选用时对同类投资一以贯之。
- **披露**：ASU 2023-02 同时强化了披露要求——按抵免项目类别披露税收抵免与其他税收利益的金额、投资的账面金额与承诺等信息，让报表使用者看清企业到底押了多少在这类结构上。

### 五、与 LIHTC 本体规则的分工

本篇管的是**会计**：投资人买了税收抵免结构，账上怎么记。LIHTC 本身的税法规则——第 42 条的合格基数、适用率、15 年合规期与加州 TCAC 的分配——是税法问题，本仓另有专篇，两边不要混：税法决定抵免生不生、给多少，会计决定这些抵免在报表上怎么走。加州口径：加州另有州级低收入住房抵免（《收入与税收法典》第 17058 条一带），州抵免的取得与合规按州法与 TCAC 口径，报表层面的会计处理仍按本篇的联邦 GAAP 框架，两套账各走各的。

### 六、易错点收束

1. 把 PAM 当成所有税收抵免投资的默认法：错。五项条件全过才可选用，不满足走权益法等其他指引。
2. 把摊销放进税前费用：PAM 的摊销与抵免一起列所得税费用，进错行整篇列报就错位。
3. 收益率条件看反：第 4 项要求只看税收利益时收益率为正；把经营收益算进去才为正的，不满足条件。
4. 生效日记混：公众实体与非公众实体错开一年，题目给出实体类型就是在考这一格。
5. 把会计篇与第 42 条税法篇混读：抵免的产生看税法，抵免的入账看本篇。

*声明：个人学习笔记，不构成税务或会计建议；条文与生效日以 FASB 现行文本为准。来源：FASB ASU 2023-02（Topic 323）；ASC 323-740-25-1 五项条件；IRC § 42（LIHTC 本体，加州口径另见 Cal. Rev. & Tax. Code § 17058 一带）。*

---

## English

ASU 2023-02 (March 2023) lets investors apply the proportional amortization method (PAM) to any tax credit structure that meets the five conditions of ASC 323-740-25-1, not just low-income housing tax credits. Under PAM, the cost of the investment is amortized in proportion to the tax credits received, and the amortization is presented net with the credits and other tax benefits inside income tax expense — keeping the investment out of pre-tax income. The five conditions: it is probable the investor will receive the tax credits; the investor lacks significant influence over the investee; substantially all projected benefits come from tax credits and other tax benefits; the projected yield based solely on tax benefits is positive; and the investor's liability is limited to its capital contribution. Worked example: a $1,000,000 investment expecting $900,000 of total credits that receives $180,000 in year one amortizes $1,000,000 × (180,000 ÷ 900,000) = $200,000 in year one. Effective for public business entities for fiscal years beginning after December 15, 2023, and one year later for all other entities, with retrospective or modified retrospective transition. Personal study notes only; not tax or accounting advice.

## Español — traducción preliminar, pendiente de revisión (初译待校)

La ASU 2023-02 (marzo de 2023) permite aplicar el método de amortización proporcional (PAM) a cualquier estructura de créditos fiscales que cumpla las cinco condiciones de ASC 323-740-25-1, no solo a los créditos por vivienda de bajos ingresos. Con el PAM, el costo de la inversión se amortiza en proporción a los créditos fiscales recibidos, y la amortización se presenta neta, junto con los créditos y otros beneficios fiscales, dentro del gasto por impuesto sobre la renta, manteniendo la inversión fuera del resultado antes de impuestos. Las cinco condiciones: es probable que el inversor reciba los créditos; el inversor no ejerce influencia significativa sobre la participada; sustancialmente todos los beneficios proyectados provienen de créditos y otros beneficios fiscales; el rendimiento proyectado basado solo en beneficios fiscales es positivo; y la responsabilidad del inversor se limita a su aportación de capital. Ejemplo: una inversión de 1.000.000 de dólares con 900.000 de créditos totales esperados que recibe 180.000 el primer año amortiza 1.000.000 × (180.000 ÷ 900.000) = 200.000 dólares ese año. Vigente para entidades comerciales públicas en ejercicios que comiencen después del 15 de diciembre de 2023, y un año después para las demás, con transición retrospectiva o retrospectiva modificada. Notas personales de estudio; no es asesoría fiscal ni contable.

## 한국어 — 초역, 교정 대기 중 (初译待校)

ASU 2023-02(2023년 3월)는 비례 상각법(PAM)을 저소득 주택 세액공제에 한정하지 않고, ASC 323-740-25-1의 다섯 가지 조건을 모두 충족하는 모든 세액공제 구조 투자에 적용할 수 있게 했다. PAM에서는 투자 원가를 받은 세액공제의 비율에 따라 상각하고, 상각액과 공제 및 기타 세제 혜택을 소득세 비용 안에 함께 표시하여 투자가 세전 이익에 영향을 주지 않게 한다. 다섯 가지 조건은 다음과 같다. 투자자가 세액공제를 받을 가능성이 높을 것, 피투자자에 대한 유의적 영향력이 없을 것, 예상 효익의 대부분이 세액공제와 기타 세제 혜택에서 나올 것, 세제 혜택만으로 계산한 예상 수익률이 양수일 것, 투자자의 책임이 출자액으로 한정될 것. 계산 예: 총 공제 예상액 900,000달러인 1,000,000달러 투자에서 첫해에 180,000달러의 공제를 받으면 첫해 상각액은 1,000,000 × (180,000 ÷ 900,000) = 200,000달러이다. 공적 사업체에는 2023년 12월 15일 이후 시작하는 회계연도부터, 그 밖의 기업에는 1년 늦게 적용되며, 소급 또는 수정 소급 방식으로 전환한다. 개인 학습 노트이며 세무·회계 자문이 아니다.

## Tiếng Việt — bản dịch sơ bộ, chờ hiệu đính (初译待校)

ASU 2023-02 (tháng 3 năm 2023) cho phép áp dụng phương pháp khấu hao tỷ lệ (PAM) cho mọi khoản đầu tư vào cấu trúc tín dụng thuế đáp ứng đủ năm điều kiện của ASC 323-740-25-1, không chỉ tín dụng nhà ở thu nhập thấp. Theo PAM, giá vốn của khoản đầu tư được khấu hao theo tỷ lệ tín dụng thuế nhận được, và phần khấu hao được trình bày gộp cùng các khoản tín dụng và lợi ích thuế khác trong chi phí thuế thu nhập, giữ khoản đầu tư ngoài lợi nhuận trước thuế. Năm điều kiện: nhà đầu tư nhiều khả năng sẽ nhận được tín dụng thuế; nhà đầu tư không có ảnh hưởng đáng kể đối với bên nhận đầu tư; hầu như toàn bộ lợi ích dự kiến đến từ tín dụng thuế và các lợi ích thuế khác; lợi suất dự kiến tính riêng trên lợi ích thuế là dương; và trách nhiệm của nhà đầu tư giới hạn trong số vốn đã góp. Ví dụ: khoản đầu tư 1.000.000 đô la với tổng tín dụng dự kiến 900.000 đô la, năm đầu nhận 180.000 đô la, sẽ khấu hao 1.000.000 × (180.000 ÷ 900.000) = 200.000 đô la trong năm đầu. Áp dụng cho các thực thể kinh doanh đại chúng từ năm tài chính bắt đầu sau ngày 15 tháng 12 năm 2023, và muộn hơn một năm cho các thực thể khác, với chuyển đổi hồi tố hoặc hồi tố sửa đổi. Ghi chú học tập cá nhân; không phải tư vấn thuế hay kế toán.

## हिन्दी — प्रारंभिक अनुवाद, समीक्षा लंबित (初译待校)

ASU 2023-02 (मार्च 2023) आनुपातिक परिशोधन विधि (PAM) को केवल कम-आय आवास कर क्रेडिट तक सीमित नहीं रखता; ASC 323-740-25-1 की पाँचों शर्तें पूरी करने वाली किसी भी कर क्रेडिट संरचना पर इसे लागू किया जा सकता है। PAM के तहत निवेश की लागत प्राप्त कर क्रेडिट के अनुपात में परिशोधित होती है, और परिशोधन को क्रेडिट तथा अन्य कर लाभों के साथ आयकर व्यय के भीतर दिखाया जाता है, जिससे निवेश कर-पूर्व आय से बाहर रहता है। पाँच शर्तें: निवेशक को कर क्रेडिट मिलने की प्रबल संभावना हो; निवेशक का निवेशित इकाई पर महत्वपूर्ण प्रभाव न हो; अनुमानित लाभों का लगभग संपूर्ण भाग कर क्रेडिट और अन्य कर लाभों से आए; केवल कर लाभों पर आधारित अनुमानित प्रतिफल धनात्मक हो; और निवेशक का दायित्व उसकी पूंजी तक सीमित हो। उदाहरण: 1,000,000 डॉलर के निवेश में कुल अपेक्षित क्रेडिट 900,000 डॉलर हो और पहले वर्ष 180,000 डॉलर मिले, तो पहले वर्ष का परिशोधन 1,000,000 × (180,000 ÷ 900,000) = 200,000 डॉलर होगा। यह सार्वजनिक व्यावसायिक इकाइयों के लिए 15 दिसंबर 2023 के बाद शुरू होने वाले वित्तीय वर्षों से और अन्य इकाइयों के लिए एक वर्ष बाद प्रभावी है, पूर्वव्यापी या संशोधित पूर्वव्यापी संक्रमण के साथ। व्यक्तिगत अध्ययन नोट्स; कर या लेखा सलाह नहीं।
