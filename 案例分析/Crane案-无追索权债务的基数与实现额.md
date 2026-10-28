# Crane 案：无追索权债务的基数与实现额（案例分析）

这篇讲什么：
- Crane v. Commissioner, 331 U.S. 1 (1947) 是美国税法里绕不开的一案：它同时回答了两个问题——带贷款的财产，基数里算不算那笔债；卖掉时，实现额里算不算被接走的那笔债。
- 先按判决原文把数字算一遍，再看这套「两边都算」的对称逻辑怎样写进现行《国内税收法典》（IRC）第 1001、1012、7701(g) 条，最后接上 Tufts 案（1983）补掉的那块拼图。
- CPA 的 REG 与税务实务里，带债处置的计算题几乎都是这一案的变体。

---

## 一、事实：一栋几乎全是贷款的楼

### 中文
Beulah Crane 的丈夫于 1932 年 1 月去世，她是遗产的唯一受益人和执行人。遗产里有一块地和一栋公寓楼，为遗产税目的估值 262,042.50 美元，其中土地 55,000 美元、建筑 207,042.50 美元。这栋楼上压着一笔 255,000 美元本金的抵押贷款，另有 7,042.50 美元利息已经拖欠；关键一点是，这笔贷款对她个人无追索权（nonrecourse），也就是说债权人只能拿楼本身受偿，不能追她个人其他财产。

她接手后继续经营这栋楼收租。在她持有期间，这栋建筑可计提的折旧共 28,045.10 美元——请注意这一点，折旧是本案真正的引线：她已经按包含贷款的完整价值提了折旧，卖楼时却想按另一套口径算。

1938 年 11 月 29 日，抵押权人威胁要止赎（foreclosure），她把楼以 3,000 美元现金、买方承受抵押贷款的方式卖给第三方，又付了 500 美元出售费用，净得现金 2,500 美元。她报税时的算法是：我当年继承的「财产」只是楼里扣掉贷款后的权益（equity），这份权益在继承时价值为零，所以我的基数是零，实现额就是净得的 2,500 美元，并按当时的资本利得规则申报了其中一半、1,250 美元为应税利得。

### English
Beulah Crane's husband died in January 1932, leaving her as sole beneficiary and executrix of his estate. The estate included land and an apartment building appraised, for estate tax purposes, at $262,042.50 — $55,000 allocated to the land and $207,042.50 to the building. The property was encumbered by a mortgage of $255,000 in principal, with a further $7,042.50 of interest in default. Critically, the mortgage was nonrecourse as to her: the lender could look only to the building, not to her other assets.

She operated the building and collected the rents. During her holding period, allowable depreciation on the building came to $28,045.10 — and depreciation is the real fuse of this case, because she had taken deductions measured by the property's full value, debt included, yet wanted to compute her sale on a different theory.

On November 29, 1938, with the mortgagee threatening foreclosure, she sold the property to a third party for $3,000 in cash, subject to the mortgage, and paid $500 in selling expenses, netting $2,500 in cash. Her return took this position: the "property" she had inherited was only her equity in the building — the value over and above the mortgage — and that equity had been worth zero when she acquired it. Her basis was therefore zero, her amount realized was the $2,500 of net cash, and, under the capital-gain inclusion rules of the day, she reported half of it, $1,250, as taxable gain.

### Español (译稿)
El esposo de Beulah Crane murió en enero de 1932 y ella quedó como única beneficiaria y albacea de la herencia. Esta incluía un terreno y un edificio de apartamentos tasado, a efectos del impuesto de sucesiones, en 262.042,50 dólares: 55.000 para el terreno y 207.042,50 para el edificio. Sobre el inmueble pesaba una hipoteca de 255.000 dólares de principal, con otros 7.042,50 dólares de intereses ya vencidos. El punto clave: la hipoteca era sin recurso personal (nonrecourse) contra ella, es decir, el acreedor solo podía cobrarse con el propio edificio, no con sus demás bienes.

Ella siguió explotando el edificio y cobrando los alquileres. Durante su período de tenencia, la depreciación admisible del edificio sumó 28.045,10 dólares, y esa depreciación es la verdadera mecha del caso: había deducido sobre el valor completo del inmueble, deuda incluida, pero al vender quería calcular con otra teoría.

El 29 de noviembre de 1938, con el acreedor hipotecario amenazando la ejecución (foreclosure), vendió el inmueble a un tercero por 3.000 dólares en efectivo, sujeto a la hipoteca, y pagó 500 dólares de gastos de venta, quedándose con 2.500 dólares netos. Su declaración sostuvo esto: la «propiedad» heredada era solo su participación neta (equity) en el edificio, el valor por encima de la hipoteca, y esa participación valía cero al adquirirla. Por tanto, su base era cero, su importe realizado eran los 2.500 dólares netos y, según las reglas de inclusión de ganancias de capital de la época, declaró la mitad, 1.250 dólares, como ganancia imponible.

### 한국어 (초역)
Beulah Crane의 남편은 1932년 1월에 사망했고, 그녀는 유산의 유일한 수익자이자 집행인이 되었습니다. 유산에는 토지와 아파트 건물이 포함되어 있었으며, 유산세 목적으로 $262,042.50로 평가되었습니다. 이 중 토지가 $55,000, 건물이 $207,042.50였습니다. 이 부동산에는 원금 $255,000의 모기지 대출이 걸려 있었고, 추가로 $7,042.50의 이자가 연체되어 있었습니다. 결정적으로 이 모기지는 그녀에 대해 무추소권(nonrecourse)이었습니다. 즉, 대출자는 건물 자체에서만 채권을 회수할 수 있었고, 그녀의 다른 자산에는 손을 댈 수 없었습니다.

그녀는 건물을 운영하며 임대료를 받았습니다. 보유 기간 동안 건물에 대해 허용 가능한 감가상각액은 $28,045.10에 달했습니다. 이 감가상각이 바로 이 사건의 진정한 도화선입니다. 그녀는 부채를 포함한 부동산의 전체 가치를 기준으로 공제를 받아왔으면서도, 매각 시에는 다른 이론으로 계산하려 했기 때문입니다.

1938년 11월 29일, 모기지 채권자가 압류(foreclosure)를 위협하자, 그녀는 부동산을 제3자에게 현금 $3,000에 모기지를 승계하는 조건으로 매각했고, 매각 비용으로 $500를 지급해 현금 $2,500를 순수하게 남겼습니다. 그녀의 세금 신고 입장은 이러했습니다. 그녀가 상속받은 “재산”은 건물에 대한 그녀의 지분(equity), 즉 모기지를 초과하는 가치뿐이었고, 그 지분은 취득 당시 가치가 0이었다는 것입니다. 따라서 그녀의 기준가액(basis)은 0이었고, 실현액(amount realized)은 순현금 $2,500였으며, 당시의 자본이득 포함 규정에 따라 그 절반인 $1,250를 과세 대상 이득으로 신고했습니다.

### Tiếng Việt (bản dịch)
Chồng của Beulah Crane qua đời vào tháng 1 năm 1932, để lại bà là người hưởng thừa kế duy nhất và là người thi hành di chúc của ông. Di sản bao gồm một mảnh đất và một tòa nhà chung cư được định giá, cho mục đích thuế di sản, là $262,042.50 — $55,000 cho đất và $207,042.50 cho tòa nhà. Bất động sản này bị thế chấp bởi một khoản vay thế chấp có số tiền gốc là $255,000, cùng với $7,042.50 tiền lãi đã quá hạn. Điểm then chốt là khoản thế chấp này không có quyền truy đòi (nonrecourse) đối với bà: bên cho vay chỉ có thể nhìn vào chính tòa nhà, không thể truy đòi các tài sản khác của bà.

Bà đã vận hành tòa nhà và thu tiền thuê. Trong thời gian bà nắm giữ, khấu hao được phép đối với tòa nhà lên tới $28,045.10 — và khấu hao chính là ngòi nổ thực sự của vụ án này, bởi vì bà đã khấu trừ dựa trên toàn bộ giá trị của bất động sản, bao gồm cả khoản nợ, nhưng khi bán lại muốn tính theo một lý thuyết khác.

Vào ngày 29 tháng 11 năm 1938, khi bên nhận thế chấp đe dọa tịch thu (foreclosure), bà đã bán bất động sản cho một bên thứ ba với giá $3,000 tiền mặt, kèm theo khoản thế chấp, và trả $500 chi phí bán, thu về ròng $2,500 tiền mặt. Tờ khai thuế của bà lập luận như sau: “tài sản” mà bà thừa kế chỉ là phần vốn chủ sở hữu (equity) của bà trong tòa nhà — phần giá trị vượt trên khoản thế chấp — và phần vốn đó có giá trị bằng không khi bà nhận được. Do đó, cơ sở tính thuế (basis) của bà bằng không, số tiền thực nhận (amount realized) của bà là $2,500 tiền mặt ròng, và theo quy tắc tính lãi vốn thời bấy giờ, bà đã khai một nửa số đó, $1,250, là lãi chịu thuế.

### हिन्दी (अनुवाद)
Beulah Crane के पति का जनवरी 1932 में निधन हो गया, और वह उनकी संपदा की एकमात्र लाभार्थी और निष्पादिका बनीं। संपदा में भूमि और एक अपार्टमेंट भवन शामिल था, जिसका संपदा कर के प्रयोजनों के लिए मूल्यांकन $262,042.50 किया गया था — भूमि के लिए $55,000 और भवन के लिए $207,042.50। इस संपत्ति पर $255,000 मूलधन का एक बंधक (mortgage) था, साथ ही $7,042.50 ब्याज बकाया था। महत्वपूर्ण बात यह है कि यह बंधक उनके लिए बिना सहारा (nonrecourse) था: ऋणदाता केवल भवन से ही वसूली कर सकता था, उनकी अन्य संपत्तियों से नहीं।

उन्होंने भवन का संचालन किया और किराया वसूला। उनके धारण काल के दौरान भवन पर अनुमेय मूल्यह्रास $28,045.10 हुआ — और मूल्यह्रास ही इस मामले की असली चिंगारी है, क्योंकि उन्होंने ऋण सहित संपत्ति के पूर्ण मूल्य के आधार पर कटौतियाँ ली थीं, फिर भी बिक्री की गणना एक अलग सिद्धांत पर करना चाहती थीं।

29 नवंबर 1938 को, जब बंधकधारी ने फोरक्लोज़र (foreclosure) की धमकी दी, तो उन्होंने संपत्ति को एक तीसरे पक्ष को $3,000 नकद में, बंधक के अधीन रहते हुए बेच दिया, और बिक्री खर्च के रूप में $500 का भुगतान किया, जिससे उन्हें शुद्ध $2,500 नकद मिला। उनके कर रिटर्न का रुख यह था: उन्होंने जो “संपत्ति” विरासत में पाई थी, वह केवल भवन में उनकी इक्विटी (equity) थी — बंधक से ऊपर का मूल्य — और वह इक्विटी उनके द्वारा प्राप्त किए जाने के समय शून्य मूल्य की थी। इसलिए उनका आधार (basis) शून्य था, उनकी प्राप्त राशि (amount realized) शुद्ध नकद $2,500 थी, और उस समय के पूंजीगत लाभ समावेशन नियमों के तहत, उन्होंने इसका आधा, $1,250, करयोग्य लाभ के रूप में घोषित किया।

---

## 二、争点：两个对称的问题

### 中文
税局局长（Commissioner）的算法正好相反，并把案子拆成两个必须一起回答的问题：

1. **取得端**：她继承的「财产」到底是整栋楼，还是扣掉贷款后的那份权益？如果财产是整栋楼，她的原始基数就是死亡时的完整估值 262,042.50 美元；如果只是权益，基数就是零。
2. **处置端**：买方承受的那笔 255,000 美元抵押贷款，算不算她出售时的实现额（amount realized）？税局认为算：实现额是 2,500 美元净现金加 255,000 美元债务，共 257,500 美元。

税局据此核定：调整后基数为 262,042.50 减去可提折旧 28,045.10，即 233,997.40 美元；实现额 257,500 美元与之相减，利得约为 23,502.60 美元（原核定还按土地与建筑的比例分摊售价、分别处理资本损失与普通利得，得出应税净利得 23,767.03 美元的口径）。税务法院（当时卷内为 3 T.C. 585）大体站在她一边，第二巡回法院又改判，案子最后到了最高法院。

两个问题为什么必须一起答？因为只答一个就会漏税或双重征税：基数算债、实现额不算债，纳税人就白拿了折旧又逃掉了还款；基数不算债、实现额算债，则是同一笔钱被算了两次。这个对称性就是全案的骨架。

### English
The Commissioner computed the tax the opposite way and framed two questions that had to be answered together:

1. **At acquisition**: was the "property" she inherited the whole building, or only the equity above the mortgage? If the property was the building itself, her original basis was its full date-of-death value of $262,042.50; if it was only the equity, her basis was zero.
2. **At disposition**: does the $255,000 mortgage, to which the buyer took the property subject, count in her amount realized? The Commissioner said yes: the amount realized was the $2,500 of net cash plus the $255,000 of debt, a total of $257,500.

On that footing the Commissioner determined an adjusted basis of $262,042.50 minus $28,045.10 of allowable depreciation, or $233,997.40, against an amount realized of $257,500 — a gain of roughly $23,502.60 before characterization (the original determination also allocated the price between land and building and treated a capital loss on the land and ordinary gain on the building separately, arriving at a net taxable gain of $23,767.03). The Tax Court (3 T.C. 585) largely sided with her; the Second Circuit reversed; the case reached the Supreme Court.

Why must the two questions be answered together? Answering only one either leaks revenue or double-counts. Include the debt in basis but not in amount realized, and the taxpayer keeps depreciation on money that is never accounted for. Exclude it from basis but include it on sale, and the same dollars are counted twice. That symmetry is the skeleton of the whole case.

### Español (译稿)
El Comisionado de Hacienda calculó el impuesto al contrario y planteó dos preguntas que debían responderse juntas:

1. **En la adquisición**: ¿la «propiedad» heredada era todo el edificio o solo la participación neta por encima de la hipoteca? Si era el edificio, su base original era el valor completo a la fecha de la muerte, 262.042,50 dólares; si era solo la participación neta, su base era cero.
2. **En la disposición**: ¿cuentan los 255.000 dólares de hipoteca, a los que el comprador tomó el inmueble sujeto, en su importe realizado (amount realized)? El Comisionado dijo que sí: el importe realizado eran los 2.500 dólares netos en efectivo más los 255.000 de deuda, en total 257.500 dólares.

Con esa base, el Comisionado fijó una base ajustada de 262.042,50 menos 28.045,10 de depreciación admisible, es decir, 233.997,40 dólares, frente a un importe realizado de 257.500: una ganancia de unos 23.502,60 dólares antes de su calificación (la liquidación original además repartía el precio entre terreno y edificio y trataba por separado una pérdida de capital del terreno y una ganancia ordinaria del edificio, llegando a una ganancia neta imponible de 23.767,03 dólares). El Tribunal Fiscal (3 T.C. 585) se inclinó en gran parte por ella; el Segundo Circuito revocó, y el caso llegó al Tribunal Supremo.

¿Por qué deben responderse las dos preguntas juntas? Responder solo una o bien deja escapar impuesto o bien cuenta dos veces lo mismo. Incluir la deuda en la base pero no en el importe realizado permite quedarse con la depreciación de un dinero que nunca se rinde en cuentas. Excluirla de la base e incluirla en la venta cuenta los mismos dólares dos veces. Esa simetría es el esqueleto de todo el caso.

### 한국어 (초역)
국세청장(Commissioner)은 세금을 반대로 계산했고, 함께 답해야 할 두 가지 질문을 제시했습니다.

1. **취득 시점**: 그녀가 상속받은 “재산”은 건물 전체였습니까, 아니면 모기지를 초과하는 지분뿐이었습니까? 재산이 건물 자체였다면, 그녀의 원래 기준가액은 사망일 당시의 전체 가치인 $262,042.50였습니다. 지분뿐이었다면, 기준가액은 0이었습니다.
2. **처분 시점**: 구매자가 부동산을 그 조건으로 인수한 $255,000의 모기지가 그녀의 실현액에 포함됩니까? 국세청장은 그렇다고 했습니다. 실현액은 순현금 $2,500에 부채 $255,000를 더한 총 $257,500였습니다.

이 기준에 따라 국세청장은 조정 기준가액을 $262,042.50에서 허용 가능한 감가상각 $28,045.10를 뺀 $233,997.40로 정했고, 이에 대비되는 실현액은 $257,500였습니다. 이는 성격 구분 전의 약 $23,502.60의 이익이었습니다(원래 결정에서는 또한 가격을 토지와 건물 사이에 배분하고, 토지에 대한 자본손실과 건물에 대한 일반 이익을 별도로 취급하여 순 과세 이익 $23,767.03에 도달했습니다). 조세법원(3 T.C. 585)은 대체로 그녀의 편을 들었고, 제2순회법원은 이를 뒤집었으며, 사건은 대법원에 이르렀습니다.

왜 두 질문에 함께 답해야 합니까? 하나만 답하면 세수가 누락되거나 이중으로 계산됩니다. 부채를 기준가액에는 포함하면서 실현액에는 포함하지 않으면, 납세자는 한 번도 정산되지 않은 돈에 대한 감가상각을 유지하게 됩니다. 기준가액에서 제외하면서 매각 시에는 포함하면, 같은 금액이 두 번 계산됩니다. 이 대칭성이 전체 사건의 뼈대입니다.

### Tiếng Việt (bản dịch)
Ủy viên Sở Thuế (Commissioner) đã tính thuế theo cách ngược lại và đặt ra hai câu hỏi phải được trả lời cùng nhau:

1. **Khi nhận tài sản**: “tài sản” mà bà thừa kế là toàn bộ tòa nhà, hay chỉ là phần vốn chủ sở hữu vượt trên khoản thế chấp? Nếu tài sản là chính tòa nhà, cơ sở ban đầu của bà là toàn bộ giá trị tại ngày qua đời là $262,042.50; nếu chỉ là phần vốn chủ sở hữu, cơ sở của bà bằng không.
2. **Khi chuyển nhượng**: Khoản thế chấp $255,000, mà người mua đã nhận bất động sản kèm theo, có tính vào số tiền thực nhận của bà không? Ủy viên nói có: số tiền thực nhận là $2,500 tiền mặt ròng cộng với $255,000 khoản nợ, tổng cộng là $257,500.

Trên cơ sở đó, Ủy viên xác định cơ sở đã điều chỉnh là $262,042.50 trừ đi $28,045.10 khấu hao được phép, tức là $233,997.40, so với số tiền thực nhận là $257,500 — một khoản lãi khoảng $23,502.60 trước khi phân loại (quyết định ban đầu cũng phân bổ giá giữa đất và tòa nhà và xử lý riêng khoản lỗ vốn đối với đất và lãi thông thường đối với tòa nhà, đi đến khoản lãi chịu thuế ròng là $23,767.03). Tòa án Thuế (3 T.C. 585) phần lớn đứng về phía bà; Tòa Phúc thẩm Khu vực 2 đã đảo ngược; vụ án đã lên tới Tòa án Tối cao.

Tại sao hai câu hỏi phải được trả lời cùng nhau? Chỉ trả lời một câu hỏi sẽ làm thất thu thuế hoặc tính trùng hai lần. Đưa khoản nợ vào cơ sở nhưng không đưa vào số tiền thực nhận, người nộp thuế sẽ giữ được khấu hao trên số tiền không bao giờ được tính đến. Loại khoản nợ khỏi cơ sở nhưng đưa vào khi bán, cùng một số tiền sẽ bị tính hai lần. Tính đối xứng đó là bộ khung của toàn bộ vụ án.

### हिन्दी (अनुवाद)
आयुक्त (Commissioner) ने कर की गणना इसके विपरीत तरीके से की और दो प्रश्न रखे जिनका उत्तर एक साथ देना आवश्यक था:

1. **अधिग्रहण के समय**: उन्होंने जो “संपत्ति” विरासत में पाई थी, वह पूरा भवन था, या केवल बंधक से ऊपर की इक्विटी थी? यदि संपत्ति स्वयं भवन थी, तो उनका मूल आधार मृत्यु की तिथि पर उसका पूर्ण मूल्य $262,042.50 था; यदि वह केवल इक्विटी थी, तो उनका आधार शून्य था।
2. **निपटान के समय**: क्या वह $255,000 बंधक, जिसके अधीन खरीदार ने संपत्ति ली थी, उनकी प्राप्त राशि में गिना जाता है? आयुक्त ने कहा हाँ: प्राप्त राशि शुद्ध नकद $2,500 और ऋण $255,000 थी, कुल $257,500।

इस आधार पर आयुक्त ने समायोजित आधार $262,042.50 में से $28,045.10 अनुमेय मूल्यह्रास घटाकर $233,997.40 निर्धारित किया, जिसके सामने प्राप्त राशि $257,500 थी — वर्गीकरण से पहले लगभग $23,502.60 का लाभ (मूल निर्धारण में कीमत को भूमि और भवन के बीच भी बाँटा गया था और भूमि पर पूंजीगत हानि और भवन पर साधारण लाभ को अलग-अलग माना गया था, जिससे शुद्ध करयोग्य लाभ $23,767.03 निकला)। कर न्यायालय (3 T.C. 585) ने काफी हद तक उनका पक्ष लिया; द्वितीय सर्किट ने इसे पलट दिया; मामला सर्वोच्च न्यायालय तक पहुँचा।

दोनों प्रश्नों का उत्तर एक साथ क्यों देना चाहिए? केवल एक का उत्तर देने से या तो राजस्व रिसता है या दोहरी गणना होती है। ऋण को आधार में शामिल करें लेकिन प्राप्त राशि में नहीं, तो करदाता उस धन पर मूल्यह्रास बनाए रखता है जिसका कभी हिसाब नहीं दिया गया। इसे आधार से बाहर रखें लेकिन बिक्री में शामिल करें, तो वही डॉलर दो बार गिने जाते हैं। यही समरूपता पूरे मामले का ढांचा है।

---

## 三、判决：「财产」是楼本身，债在两端都要算

### 中文
1947 年 4 月 14 日，最高法院判决税局胜诉，首席大法官 Vinson 撰写法院意见（Crane v. Commissioner, 331 U.S. 1 (1947)）。两步推理都很直白：

第一步，定「财产」。她继承并出售的财产是土地和建筑本身，而不是扣掉贷款之后的权益。证据就在她自己的行为里：她一直按整栋楼的完整价值提折旧，税法也允许她这么提——如果她的财产只有那份价值为零的权益，这 28,045.10 美元折旧根本无从谈起。按当时《收入法典》中基数规则的前身条文（现行法对应 IRC 第 1014 条的死亡时价值基数），她的原始基数就是 262,042.50 美元。

第二步，定「实现额」。出售带债财产，卖方被解除的那笔债务与收到现金没有实质区别：买方承受抵押，等于替她把这笔债接了过去，她因此获得了与收到等额现金再去还债相同的经济利益。所以实现额包括 255,000 美元贷款余额加净现金 2,500 美元，共 257,500 美元。无追索权这一点不改变结论——贷款是真实债务，她取得财产时按真实债务处理、提了折旧，出售时就不能换一套说法。

判决还留了一个著名的尾巴：第 37 号脚注说，如果财产价值低于贷款额，无个人责任的借款人被解除的利益是否还等于全部贷款额，是「另一个可能不同的问题」，本案不处理。这个脚注悬了三十多年，直到 Tufts 案才被收掉，见第五节。

### English
On April 14, 1947, the Supreme Court held for the Commissioner, in an opinion by Chief Justice Vinson (Crane v. Commissioner, 331 U.S. 1 (1947)). The reasoning has two plain steps:

First, define the property. What she inherited and sold was the land and building themselves, not an equity interest net of the mortgage. Her own conduct proved it: she had claimed, and the tax law had allowed, depreciation measured by the building's full value — deductions that would have been impossible if her property had been a zero-value equity. Under the predecessor of the basis rule now codified at IRC section 1014 (basis set by value at death), her original basis was $262,042.50.

Second, define the amount realized. On a sale of encumbered property, relief from the debt is economically indistinguishable from cash: the buyer took the property subject to the mortgage, which is the same benefit as receiving cash and paying the debt off herself. The amount realized therefore included the $255,000 mortgage balance plus the $2,500 of net cash — $257,500 in all. The nonrecourse character of the loan did not change the answer: the debt was a true loan, it had been treated as one when she acquired the property and took depreciation, and she could not redescribe it at sale time.

The opinion left one famous loose end. Footnote 37 reserved the question whether, if the property were worth less than the mortgage, a borrower with no personal liability would still realize a benefit equal to the full debt, calling it a different problem that might be encountered on other facts. That footnote hung unresolved for more than three decades, until Tufts, taken up in section five.

### Español (译稿)
El 14 de abril de 1947, el Tribunal Supremo falló a favor del Comisionado, con opinión del presidente del Tribunal, Vinson (Crane v. Commissioner, 331 U.S. 1 (1947)). El razonamiento tiene dos pasos claros:

Primero, definir la propiedad. Lo que ella heredó y vendió fue el terreno y el edificio mismos, no una participación neta de la hipoteca. Su propia conducta lo probaba: había reclamado, y la ley fiscal le había permitido, una depreciación medida por el valor completo del edificio, deducciones imposibles si su propiedad hubiera sido una participación de valor cero. Según la norma predecesora de la hoy codificada en el artículo 1014 del IRC (base fijada por el valor a la fecha de la muerte), su base original era de 262.042,50 dólares.

Segundo, definir el importe realizado. En la venta de un bien gravado, liberarse de la deuda equivale económicamente a recibir efectivo: el comprador tomó el inmueble sujeto a la hipoteca, beneficio idéntico a recibir el dinero y pagar la deuda ella misma. El importe realizado incluyó, por tanto, los 255.000 dólares de saldo hipotecario más los 2.500 netos en efectivo: 257.500 en total. Que el préstamo fuera sin recurso personal no cambiaba la respuesta: era una deuda verdadera, así se trató al adquirir el inmueble y deducir la depreciación, y no podía redescribirse al vender.

La sentencia dejó un cabo suelto famoso. La nota 37 reservó la cuestión de si, cuando el inmueble vale menos que la hipoteca, un deudor sin responsabilidad personal seguiría realizando un beneficio igual a toda la deuda, calificándolo de problema distinto que podría presentarse con otros hechos. Esa nota quedó sin resolver más de tres décadas, hasta Tufts, que se trata en la sección cinco.

### 한국어 (초역)
1947년 4월 14일, 대법원은 대법원장 Vinson이 작성한 의견으로 국세청장의 손을 들어주었습니다(Crane v. Commissioner, 331 U.S. 1 (1947)). 그 논리는 두 가지 분명한 단계로 이루어져 있습니다.

첫째, 재산을 정의하는 것입니다. 그녀가 상속받고 매각한 것은 토지와 건물 자체였지, 모기지를 차감한 순지분이 아니었습니다. 그녀 자신의 행위가 이를 증명했습니다. 그녀는 건물의 전체 가치를 기준으로 감가상각을 청구했고 세법도 이를 허용했는데, 이는 그녀의 재산이 가치가 0인 지분이었다면 불가능했을 공제였습니다. 현재 IRC 제1014조에 성문화된 기준가액 규칙(사망일 당시 가치로 기준가액을 정함)의 전신 규정에 따라, 그녀의 원래 기준가액은 $262,042.50였습니다.

둘째, 실현액을 정의하는 것입니다. 담보가 설정된 재산을 매각할 때, 부채에서 벗어나는 것은 경제적으로 현금 수령과 구별할 수 없습니다. 구매자가 모기지가 설정된 상태로 부동산을 인수한 것은, 그녀가 현금을 받아 직접 부채를 갚는 것과 동일한 이익이었습니다. 따라서 실현액에는 모기지 잔액 $255,000와 순현금 $2,500가 포함되어, 총 $257,500였습니다. 대출이 무추소권이라는 성격은 답을 바꾸지 않았습니다. 그 부채는 진정한 대출이었고, 그녀가 부동산을 취득하고 감가상각을 받을 때 진정한 대출로 취급되었으며, 매각 시점에 다시 설명할 수는 없었습니다.

이 판결은 유명한 미결 사항 하나를 남겼습니다. 각주 37은, 부동산 가치가 모기지보다 낮을 경우, 개인적 책임이 없는 차입인이 여전히 전체 부채와 같은 이익을 실현하는지에 대한 문제를 유보하면서, 이는 다른 사실관계에서 마주칠 수 있는 별개의 문제라고 불렀습니다. 그 각주는 30년 넘게 해결되지 않은 채 남아 있었고, 다섯 번째 절에서 다루는 Tufts 사건에 이르러서야 해결되었습니다.

### Tiếng Việt (bản dịch)
Vào ngày 14 tháng 4 năm 1947, Tòa án Tối cao đã phán quyết có lợi cho Ủy viên, trong một ý kiến do Chánh án Vinson viết (Crane v. Commissioner, 331 U.S. 1 (1947)). Lập luận gồm hai bước rõ ràng:

Thứ nhất, xác định tài sản. Thứ mà bà thừa kế và bán là chính đất và tòa nhà, không phải phần vốn chủ sở hữu sau khi trừ khoản thế chấp. Hành vi của chính bà đã chứng minh điều đó: bà đã yêu cầu, và luật thuế đã cho phép, khấu hao được đo theo toàn bộ giá trị của tòa nhà — những khoản khấu trừ sẽ không thể có nếu tài sản của bà là phần vốn có giá trị bằng không. Theo quy định tiền thân của quy tắc cơ sở hiện được quy định tại Điều 1014 của IRC (cơ sở được xác định theo giá trị tại ngày qua đời), cơ sở ban đầu của bà là $262,042.50.

Thứ hai, xác định số tiền thực nhận. Khi bán một tài sản bị thế chấp, việc được giải thoát khỏi khoản nợ về kinh tế không khác gì nhận tiền mặt: người mua đã nhận bất động sản kèm theo khoản thế chấp, điều này mang lại lợi ích tương tự như việc nhận tiền mặt và tự mình trả nợ. Do đó, số tiền thực nhận bao gồm số dư thế chấp $255,000 cộng với $2,500 tiền mặt ròng — tổng cộng là $257,500. Tính chất không truy đòi của khoản vay không làm thay đổi đáp án: khoản nợ là một khoản vay thực sự, nó đã được đối xử như vậy khi bà nhận bất động sản và khấu hao, và bà không thể mô tả lại nó vào thời điểm bán.

Phán quyết để lại một đầu mối nổi tiếng chưa được giải quyết. Chú thích 37 dành lại câu hỏi liệu, nếu bất động sản có giá trị thấp hơn khoản thế chấp, một người vay không có trách nhiệm cá nhân có vẫn thực nhận một lợi ích bằng toàn bộ khoản nợ hay không, và gọi đó là một vấn đề khác có thể gặp trong những tình huống khác. Chú thích đó đã treo lơ lửng hơn ba thập kỷ, cho tới vụ Tufts, được đề cập ở phần năm.

### हिन्दी (अनुवाद)
14 अप्रैल 1947 को, सर्वोच्च न्यायालय ने मुख्य न्यायाधीश Vinson द्वारा लिखित राय में आयुक्त के पक्ष में निर्णय दिया (Crane v. Commissioner, 331 U.S. 1 (1947))। तर्क के दो स्पष्ट चरण हैं:

पहला, संपत्ति को परिभाषित करना। उन्होंने जो विरासत में पाया और बेचा, वह भूमि और भवन स्वयं थे, न कि बंधक घटाकर बची इक्विटी। उनके अपने आचरण ने यह सिद्ध किया: उन्होंने भवन के पूर्ण मूल्य के आधार पर मूल्यह्रास का दावा किया था, और कर कानून ने इसकी अनुमति दी थी — ये कटौतियाँ असंभव होतीं यदि उनकी संपत्ति शून्य-मूल्य वाली इक्विटी होती। अब IRC की धारा 1014 में संहिताबद्ध आधार नियम (मृत्यु की तिथि के मूल्य से निर्धारित आधार) के पूर्ववर्ती नियम के तहत, उनका मूल आधार $262,042.50 था।

दूसरा, प्राप्त राशि को परिभाषित करना। गिरवी रखी संपत्ति की बिक्री पर, ऋण से मुक्ति आर्थिक रूप से नकद से अलग नहीं है: खरीदार ने संपत्ति को बंधक के अधीन लिया, जो नकद प्राप्त करके स्वयं ऋण चुकाने के समान लाभ है। इसलिए प्राप्त राशि में बंधक शेष $255,000 और शुद्ध नकद $2,500 शामिल थे — कुल मिलाकर $257,500। ऋण के बिना-सहारा होने से उत्तर नहीं बदला: ऋण एक वास्तविक ऋण था, संपत्ति प्राप्त करने और मूल्यह्रास लेने के समय इसे वैसा ही माना गया था, और बिक्री के समय इसे फिर से वर्णित नहीं किया जा सकता था।

राय ने एक प्रसिद्ध अधूरा सिरा छोड़ दिया। फुटनोट 37 ने यह प्रश्न आरक्षित रखा कि यदि संपत्ति का मूल्य बंधक से कम हो, तो क्या बिना व्यक्तिगत दायित्व वाला उधारकर्ता फिर भी पूरे ऋण के बराबर लाभ प्राप्त करेगा, और इसे एक अलग समस्या कहा जो अन्य तथ्यों पर सामने आ सकती है। वह फुटनोट तीन दशकों से अधिक समय तक अनसुलझा रहा, जब तक कि Tufts नहीं आया, जिस पर पाँचवें खंड में चर्चा की गई है।

---

## 四、现行法典化：三条条文接住 Crane

### 中文
今天做带债处置，先查这三处，现行文本都留着 Crane 的逻辑：

- **IRC 第 1001 条**：第 (a) 款规定，出售或其他处置财产的利得等于实现额超过调整后基数的部分；第 (b) 款把实现额定义为收到的金钱加所收财产的公平市场价值。财政部条例 Reg. 第 1.1001-2 条进一步明确：实现额包括因处置而被解除的债务（liabilities from which the transferor is discharged），无论该债务有无追索权。
- **IRC 第 1012 条**：财产基数一般是成本，而买价里用借款支付的部分同样进成本——这就是 Crane 在购买场景下的对应面：贷款买房，基数按完整买价算，不按首付算。继承取得则走第 1014 条的死亡时价值基数，再按第 1016 条用折旧等项目往下调。
- **IRC 第 7701(g) 条**：为防止争议再起，条文直接规定，就无追索权债务担保的财产而言，该财产的公平市场价值视为不低于该无追索权债务的未偿金额。

实务上要与另一条线分清：**有追索权债务被免除**，通常走债务免除所得（cancellation of debt income，IRC 第 61(a)(11) 条），再看第 108 条的破产、无清偿能力等排除项；**无追索权债务随财产处置被接走或止赎**，则按 Crane 与 Tufts 并入实现额算处置利得，不另算债务免除所得。止赎也是一次处置：无追索权贷款止赎时，实现额就是未偿贷款余额（另加收到的其他对价）。两条线混用，是实务和考试里最常见的错法之一。

### English
For a disposition of encumbered property today, three provisions carry Crane's logic in current text:

- **IRC section 1001**: subsection (a) measures gain as the excess of the amount realized over adjusted basis, and subsection (b) defines the amount realized as money received plus the fair market value of property received. Treasury Regulation section 1.1001-2 then states expressly that the amount realized includes liabilities from which the transferor is discharged as a result of the disposition, whether or not the debt is recourse.
- **IRC section 1012**: basis is generally cost, and the borrowed portion of a purchase price is part of cost — Crane's mirror image on the buying side: a property bought with a loan takes a basis for the full price, not for the down payment. Property acquired from a decedent instead takes its section 1014 date-of-death basis, thereafter adjusted under section 1016 for items such as depreciation.
- **IRC section 7701(g)**: to foreclose the old argument, the statute provides that, for property encumbered by nonrecourse debt, the property's fair market value is treated as not less than the outstanding amount of that debt.

One neighboring line must be kept separate in practice. Cancellation of **recourse** debt ordinarily produces cancellation-of-debt income under IRC section 61(a)(11), subject to the exclusions of section 108 for bankruptcy, insolvency, and the like. Relief from **nonrecourse** debt on a sale, transfer, or foreclosure of the property is instead folded into the amount realized under Crane and Tufts and taxed as disposition gain, not separately as debt-discharge income. A foreclosure of nonrecourse debt is itself a disposition, with an amount realized equal to the outstanding loan balance (plus any other consideration received). Mixing the two lines is one of the most common errors in both practice and exam answers.

### Español (译稿)
Para disponer hoy de un bien gravado, tres normas conservan la lógica de Crane en el texto vigente:

- **Artículo 1001 del IRC**: el apartado (a) mide la ganancia como el exceso del importe realizado sobre la base ajustada, y el apartado (b) define el importe realizado como el dinero recibido más el valor justo de mercado de los bienes recibidos. El Reglamento del Tesoro, artículo 1.1001-2, precisa que el importe realizado incluye las deudas de las que el transmitente queda liberado como resultado de la disposición, sean o no con recurso personal.
- **Artículo 1012 del IRC**: la base es, en general, el costo, y la parte del precio pagada con préstamo también forma parte del costo: es la imagen especular de Crane en el lado de la compra. Una propiedad comprada con préstamo toma como base el precio completo, no el pago inicial. Lo heredado toma, en cambio, la base del artículo 1014 según el valor a la fecha de la muerte, ajustada después conforme al artículo 1016 por conceptos como la depreciación.
- **Artículo 7701(g) del IRC**: para cerrar la vieja discusión, la ley dispone que el valor justo de mercado de un bien gravado con deuda sin recurso se considera no inferior al saldo pendiente de esa deuda.

En la práctica hay que separar otra línea. La cancelación de deuda **con recurso** produce normalmente un ingreso por condonación de deuda según el artículo 61(a)(11) del IRC, sujeto a las exclusiones del artículo 108 (quiebra, insolvencia y otras). La liberación de deuda **sin recurso** al vender, transmitir o ejecutar el bien se incorpora, en cambio, al importe realizado según Crane y Tufts, y tributa como ganancia de la disposición, no como ingreso separado por condonación. La ejecución hipotecaria de una deuda sin recurso es en sí misma una disposición, con un importe realizado igual al saldo pendiente del préstamo (más cualquier otra contraprestación recibida). Confundir ambas líneas es uno de los errores más frecuentes, en la práctica y en los exámenes.

### 한국어 (초역)
담보가 설정된 재산을 오늘 처분할 때, 현행 문언에 Crane의 논리를 담고 있는 조항은 세 가지입니다.

- **IRC 제1001조**: (a)항은 이익을 조정 기준가액을 초과하는 실현액의 초과분으로 측정하고, (b)항은 실현액을 수령한 금전과 수령한 재산의 공정시장가치의 합으로 정의합니다. 재무부 규정 제1.1001-2조는 이어서 실현액에는 처분의 결과로 양도인이 면제되는 부채가 포함되며, 그 부채가 추소권이 있는지 여부와 무관하다고 명시합니다.
- **IRC 제1012조**: 기준가액은 일반적으로 원가이며, 구매 가격 중 차입으로 조달된 부분도 원가의 일부입니다. 이는 구매 측면에서 본 Crane의 거울상입니다. 대출로 구매한 재산은 계약금이 아니라 전체 가격을 기준가액으로 삼습니다. 사망자로부터 취득한 재산은 대신 제1014조의 사망일 당시 기준가액을 취하고, 이후 감가상각과 같은 항목에 대해 제1016조에 따라 조정됩니다.
- **IRC 제7701(g)조**: 오래된 논쟁을 끝내기 위해, 이 법률은 무추소권 부채로 담보된 재산에 대해 그 재산의 공정시장가치를 해당 부채의 미상환 금액보다 낮지 않은 것으로 취급한다고 규정합니다.

실무에서는 인접한 또 다른 선을 분리해 두어야 합니다. **추소권** 부채의 면제는 통상 IRC 제61(a)(11)조에 따른 부채 면제 소득을 발생시키며, 파산, 지급불능 등과 관련한 제108조의 배제 규정이 적용됩니다. 반면, 재산의 매각, 양도 또는 압류 시 **무추소권** 부채로부터의 면제는 Crane와 Tufts에 따라 실현액에 포함되어 처분 이익으로 과세되며, 별도의 부채 면제 소득으로 과세되지 않습니다. 무추소권 부채의 압류 자체도 하나의 처분이며, 실현액은 미상환 대출 잔액(과 수령한 기타 대가)에 해당합니다. 두 선을 혼동하는 것은 실무와 시험 답안 모두에서 가장 흔한 오류 중 하나입니다.

### Tiếng Việt (bản dịch)
Đối với việc chuyển nhượng một tài sản bị thế chấp ngày nay, ba quy định mang theo logic của Crane trong văn bản hiện hành:

- **Điều 1001 của IRC**: khoản (a) đo lãi bằng phần số tiền thực nhận vượt quá cơ sở đã điều chỉnh, và khoản (b) định nghĩa số tiền thực nhận là tiền nhận được cộng với giá trị thị trường hợp lý của tài sản nhận được. Quy định của Bộ Tài chính, Điều 1.1001-2, sau đó nêu rõ rằng số tiền thực nhận bao gồm các khoản nợ mà người chuyển nhượng được giải thoát do kết quả của việc chuyển nhượng, bất kể khoản nợ đó có quyền truy đòi hay không.
- **Điều 1012 của IRC**: cơ sở nói chung là chi phí, và phần giá mua được vay mượn cũng là một phần của chi phí — đây là hình ảnh phản chiếu của Crane ở phía mua: một bất động sản mua bằng khoản vay sẽ lấy cơ sở là toàn bộ giá, không phải khoản trả trước. Tài sản nhận được từ người đã qua đời thay vào đó lấy cơ sở theo giá trị tại ngày qua đời theo Điều 1014, sau đó được điều chỉnh theo Điều 1016 đối với các khoản như khấu hao.
- **Điều 7701(g) của IRC**: để khép lại tranh luận cũ, luật quy định rằng, đối với tài sản bị thế chấp bởi nợ không truy đòi, giá trị thị trường hợp lý của tài sản được coi là không thấp hơn số tiền còn nợ của khoản nợ đó.

Trong thực tiễn, cần tách riêng một ranh giới kề bên. Việc hủy bỏ nợ **có truy đòi** thường tạo ra thu nhập từ việc hủy nợ theo Điều 61(a)(11) của IRC, tuân theo các loại trừ của Điều 108 về phá sản, mất khả năng thanh toán và các trường hợp tương tự. Ngược lại, việc được giải thoát khỏi nợ **không truy đòi** khi bán, chuyển nhượng hoặc tịch thu tài sản sẽ được gộp vào số tiền thực nhận theo Crane và Tufts và bị đánh thuế như lãi từ việc chuyển nhượng, chứ không phải riêng như thu nhập từ việc xóa nợ. Việc tịch thu nợ không truy đòi tự nó cũng là một việc chuyển nhượng, với số tiền thực nhận bằng số dư khoản vay chưa thanh toán (cộng với bất kỳ khoản đối ứng nào khác nhận được). Việc lẫn lộn hai ranh giới này là một trong những lỗi phổ biến nhất, cả trong thực tiễn và trong bài thi.

### हिन्दी (अनुवाद)
आज गिरवी रखी संपत्ति के निपटान के लिए, तीन प्रावधान वर्तमान पाठ में Crane के तर्क को आगे बढ़ाते हैं:

- **IRC धारा 1001**: उपधारा (a) लाभ को समायोजित आधार से अधिक प्राप्त राशि के रूप में मापती है, और उपधारा (b) प्राप्त राशि को प्राप्त धन और प्राप्त संपत्ति के उचित बाजार मूल्य के रूप में परिभाषित करती है। ट्रेजरी विनियमन धारा 1.1001-2 फिर स्पष्ट रूप से कहता है कि प्राप्त राशि में वे दायित्व शामिल हैं जिनसे हस्तांतरणकर्ता निपटान के परिणामस्वरूप मुक्त होता है, चाहे ऋण सहारा वाला हो या न हो।
- **IRC धारा 1012**: आधार आम तौर पर लागत होता है, और खरीद मूल्य का उधार लिया गया हिस्सा भी लागत का हिस्सा होता है — खरीद पक्ष पर Crane की दर्पण छवि: ऋण लेकर खरीदी गई संपत्ति का आधार पूरा मूल्य होता है, डाउन पेमेंट नहीं। मृतक से प्राप्त संपत्ति इसके बजाय धारा 1014 के अनुसार मृत्यु-तिथि का आधार लेती है, जिसे बाद में मूल्यह्रास जैसे मदों के लिए धारा 1016 के तहत समायोजित किया जाता है।
- **IRC धारा 7701(g)**: पुरानी बहस को समाप्त करने के लिए, कानून कहता है कि बिना-सहारा ऋण से गिरवी रखी संपत्ति के लिए, संपत्ति का उचित बाजार मूल्य उस ऋण की बकाया राशि से कम नहीं माना जाएगा।

व्यवहार में एक पड़ोसी रेखा को अलग रखना चाहिए। **सहारा वाले** ऋण की रद्दीकरण से आम तौर पर IRC धारा 61(a)(11) के तहत ऋण-रद्दीकरण आय उत्पन्न होती है, जो दिवालियापन, असमर्थता आदि के लिए धारा 108 के अपवर्जनों के अधीन होती है। इसके विपरीत, संपत्ति की बिक्री, हस्तांतरण या फोरक्लोज़र पर **बिना-सहारा** ऋण से मुक्ति को Crane और Tufts के तहत प्राप्त राशि में मिला दिया जाता है और निपटान लाभ के रूप में कर लगाया जाता है, न कि अलग से ऋण-मोचन आय के रूप में। बिना-सहारा ऋण का फोरक्लोज़र स्वयं एक निपटान है, जिसकी प्राप्त राशि बकाया ऋण शेष (और प्राप्त कोई अन्य प्रतिफल) के बराबर होती है। दोनों रेखाओं को मिलाना व्यवहार और परीक्षा उत्तरों दोनों में सबसे आम गलतियों में से एक है।

---

## 五、Tufts 补完与备考用法

### 中文
Crane 脚注 37 留下的问题是：如果楼只值 140 万，贷款却欠 185 万，卖方一分现金没拿到，实现额还按 185 万算吗？Commissioner v. Tufts, 461 U.S. 300 (1983) 的事实正好如此：合伙人处置了一处公寓项目，财产公平市场价值约 140 万美元，未偿无追索权贷款约 185.15 万美元，纳税人主张实现额只能按公平市场价值封顶、应报损失。最高法院一致判决税局胜诉：实现额按未偿贷款全额算，公平市场价值低于贷款额也不影响。理由还是对称——借款当初免税拿到、又全额进了基数提了折旧，处置时就必须全额交代；若按价值封顶，等于让纳税人确认一笔自己从未实际承受的经济损失。

至此两案合成一条完整规则，做题时照三步走：

1. **先定基数**：买价（含借款）或继承价值，减去已提或可提折旧，得调整后基数。折旧是「可提即减」，没提足也按可提额调（第 1016 条口径），不能靠少提折旧保住基数。
2. **再定实现额**：现金与其他对价，加上被买方承受或因处置解除的全部债务余额，不看财产现值是否低于债务。
3. **最后分性质**：利得再按财产性质与持有期分资本、普通（如折旧回转）等类别处理；本案的数字题走到这一步才开始分，别提前混。

给实务留一句提醒：Crane 式「幻影利得」（phantom gain）至今常见——财产贬值、现金没落袋，却因债务并入实现额而欠税。带高杠杆的房产在出售、赠与安排或止赎前，先把调整后基数与债务余额两个数字算出来再谈交易结构，顺序反了很容易在交割后才发现税单比现金还大。

### English
The question Crane's footnote 37 reserved was this: if the building is worth only $1.4 million but $1.85 million of debt is outstanding, and the seller receives no cash, is the amount realized still the full debt? Commissioner v. Tufts, 461 U.S. 300 (1983), presented exactly those facts: partners disposed of an apartment project whose fair market value was about $1.4 million against roughly $1,851,500 of unpaid nonrecourse debt, and claimed the amount realized was capped at fair market value, producing a loss. A unanimous Supreme Court held for the Commissioner: the amount realized is the full outstanding debt, and the shortfall of value below the debt is irrelevant. The reasoning is the same symmetry — the loan proceeds were received tax-free and were fully included in basis, supporting depreciation, so they must be fully accounted for on disposition; capping realization at value would let the taxpayer claim an economic loss never actually borne.

The two cases together yield one complete rule. Work any problem in three steps:

1. **Fix the basis**: purchase price (debt included) or inherited value, minus depreciation allowed or allowable, gives the adjusted basis. Depreciation reduces basis on an allowable basis under section 1016 whether or not the taxpayer actually claimed it all, so under-claiming depreciation does not preserve basis.
2. **Fix the amount realized**: cash and other consideration, plus the full balance of debt assumed by the buyer or discharged on the disposition — regardless of whether the property is now worth less than the debt.
3. **Characterize last**: only then split the gain by the property's character and holding period into capital and ordinary components such as depreciation recapture. Exam problems go wrong when characterization is attempted before the first two numbers are fixed.

One practice warning closes the loop: Crane-style "phantom gain" is still common — the property has fallen in value, little or no cash comes out, and yet tax is owed because the debt sits inside the amount realized. Before a highly leveraged property is sold, restructured, or surrendered in foreclosure, compute the adjusted basis and the outstanding debt first and design the transaction second; reversing the order is how a tax bill larger than the cash proceeds is discovered after closing.

### Español (译稿)
La pregunta que la nota 37 de Crane dejó reservada era esta: si el edificio vale solo 1,4 millones pero la deuda pendiente es de 1,85 millones, y el vendedor no recibe efectivo, ¿el importe realizado sigue siendo toda la deuda? Commissioner v. Tufts, 461 U.S. 300 (1983), presentó exactamente esos hechos: unos socios dispusieron de un complejo de apartamentos cuyo valor justo de mercado era de unos 1,4 millones frente a una deuda sin recurso pendiente de aproximadamente 1.851.500 dólares, y sostuvieron que el importe realizado quedaba limitado al valor de mercado, con una pérdida resultante. El Tribunal Supremo, por unanimidad, falló a favor del Comisionado: el importe realizado es la deuda pendiente completa, y que el valor sea inferior a la deuda es irrelevante. El razonamiento es la misma simetría: el préstamo se recibió libre de impuesto y entró por completo en la base, sustentando la depreciación, así que debe rendirse por completo al disponer; limitar la realización al valor permitiría declarar una pérdida económica nunca soportada en realidad.

Ambos casos forman una regla completa. Todo problema se resuelve en tres pasos:

1. **Fijar la base**: precio de compra (deuda incluida) o valor heredado, menos la depreciación permitida o permisible, da la base ajustada. La depreciación reduce la base por su importe permisible según el artículo 1016, se haya reclamado o no por entero.
2. **Fijar el importe realizado**: efectivo y demás contraprestación, más el saldo completo de la deuda asumida por el comprador o extinguida en la disposición, sin importar que el bien valga hoy menos que la deuda.
3. **Calificar al final**: solo entonces se reparte la ganancia según la naturaleza del bien y el período de tenencia, entre componentes de capital y ordinarios como la recuperación de la depreciación.

Una advertencia práctica cierra el tema: la «ganancia fantasma» al estilo Crane sigue siendo frecuente: el bien perdió valor, apenas sale efectivo y, sin embargo, se debe impuesto porque la deuda está dentro del importe realizado. Antes de vender, reestructurar o entregar en ejecución un inmueble muy apalancado, calcule primero la base ajustada y el saldo de la deuda, y diseñe después la operación; invertir el orden es la manera de descubrir, tras el cierre, una factura fiscal mayor que el efectivo recibido.

### 한국어 (초역)
Crane의 각주 37이 유보한 질문은 이것이었습니다. 건물의 가치가 $1.4 million에 불과한데 $1.85 million의 부채가 남아 있고, 매도인이 현금을 전혀 받지 못한다면, 실현액은 여전히 전체 부채입니까? Commissioner v. Tufts, 461 U.S. 300 (1983) 사건이 정확히 그런 사실관계를 제시했습니다. 파트너들이 공정시장가치가 약 $1.4 million인 아파트 프로젝트를 처분했는데, 미상환 무추소권 부채는 약 $1,851,500였고, 그들은 실현액이 공정시장가치로 제한되어 손실이 발생한다고 주장했습니다. 대법원은 만장일치로 국세청장의 손을 들어주었습니다. 실현액은 미상환 부채 전액이며, 가치가 부채에 미치지 못하는 것은 무관합니다. 그 논리는 동일한 대칭성입니다. 대출금은 비과세로 수령되었고 기준가액에 전액 포함되어 감가상각을 뒷받침했으므로, 처분 시 전액을 정산해야 합니다. 실현액을 가치로 제한하면 납세자가 실제로 부담한 적이 없는 경제적 손실을 주장할 수 있게 됩니다.

두 사건을 합치면 하나의 완전한 규칙이 됩니다. 모든 문제를 세 단계로 푸십시오.

1. **기준가액을 확정하십시오**: 구매 가격(부채 포함) 또는 상속 가치에서 허용되었거나 허용 가능한 감가상각을 빼면 조정 기준가액이 됩니다. 감가상각은 납세자가 실제로 전액을 청구했는지 여부와 무관하게 제1016조에 따른 허용 가능한 금액을 기준으로 기준가액을 감소시키므로, 감가상각을 적게 청구한다고 해서 기준가액이 보존되지는 않습니다.
2. **실현액을 확정하십시오**: 현금과 기타 대가에, 구매자가 인수하거나 처분 시 소멸되는 부채의 전체 잔액을 더한 것으로, 현재 부동산 가치가 부채보다 낮은지 여부와 무관합니다.
3. **성격 구분은 마지막에 하십시오**: 그 다음에야 이익을 재산의 성격과 보유 기간에 따라 자본적 요소와 감가상각 환입과 같은 일반적 요소로 나눕니다. 시험 문제는 성격 구분을 처음 두 숫자가 확정되기 전에 시도할 때 틀어집니다.

실무상의 경고 하나로 이 주제를 마무리합니다. Crane식 “유령 이익(phantom gain)”은 여전히 흔합니다. 재산 가치가 하락했고, 현금은 거의 또는 전혀 나오지 않았는데도, 부채가 실현액 안에 있기 때문에 세금이 부과됩니다. 레버리지가 높은 부동산을 매각, 구조조정 또는 압류로 넘기기 전에, 먼저 조정 기준가액과 미상환 부채를 계산하고 그 다음에 거래를 설계하십시오. 순서를 뒤집는 것이, 마감 후에 현금 수익보다 큰 세금 고지서를 발견하게 되는 방식입니다.

### Tiếng Việt (bản dịch)
Câu hỏi mà chú thích 37 của Crane dành lại là thế này: nếu tòa nhà chỉ có giá trị $1.4 million nhưng khoản nợ còn lại là $1.85 million, và người bán không nhận được tiền mặt, thì số tiền thực nhận có vẫn là toàn bộ khoản nợ không? Vụ Commissioner v. Tufts, 461 U.S. 300 (1983), trình bày đúng những tình tiết đó: các đối tác đã chuyển nhượng một dự án chung cư có giá trị thị trường hợp lý khoảng $1.4 million so với khoản nợ không truy đòi chưa thanh toán khoảng $1,851,500, và cho rằng số tiền thực nhận bị giới hạn ở giá trị thị trường hợp lý, tạo ra một khoản lỗ. Tòa án Tối cao nhất trí phán quyết có lợi cho Ủy viên: số tiền thực nhận là toàn bộ khoản nợ chưa thanh toán, và việc giá trị thấp hơn khoản nợ là không liên quan. Lập luận vẫn là tính đối xứng tương tự — tiền vay đã được nhận miễn thuế và đã được đưa toàn bộ vào cơ sở, hỗ trợ khấu hao, vì vậy phải được tính toàn bộ khi chuyển nhượng; việc giới hạn số tiền thực nhận ở giá trị sẽ cho phép người nộp thuế khai một khoản lỗ kinh tế mà họ chưa bao giờ thực sự gánh chịu.

Hai vụ án cùng nhau tạo thành một quy tắc hoàn chỉnh. Hãy giải quyết mọi bài toán theo ba bước:

1. **Xác định cơ sở**: giá mua (bao gồm cả nợ) hoặc giá trị thừa kế, trừ đi khấu hao đã được phép hoặc được phép khấu hao, cho ra cơ sở đã điều chỉnh. Khấu hao làm giảm cơ sở trên cơ sở số tiền được phép theo Điều 1016, bất kể người nộp thuế có thực sự khai toàn bộ hay không, vì vậy việc khai khấu hao ít hơn không bảo toàn được cơ sở.
2. **Xác định số tiền thực nhận**: tiền mặt và các khoản đối ứng khác, cộng với toàn bộ số dư nợ do người mua gánh chịu hoặc được xóa bỏ khi chuyển nhượng — bất kể bất động sản hiện có giá trị thấp hơn khoản nợ hay không.
3. **Phân loại cuối cùng**: chỉ khi đó mới chia khoản lãi theo tính chất và thời gian nắm giữ của tài sản thành các thành phần vốn và thông thường như việc hoàn nhập khấu hao. Các bài thi sai khi việc phân loại được thực hiện trước khi hai con số đầu tiên được xác định.

Một cảnh báo thực tiễn khép lại vòng tròn: “lãi ma” (phantom gain) kiểu Crane vẫn phổ biến — tài sản đã giảm giá trị, ít hoặc không có tiền mặt thu về, nhưng vẫn phải nộp thuế vì khoản nợ nằm trong số tiền thực nhận. Trước khi một bất động sản có đòn bẩy cao được bán, tái cấu trúc hoặc bị tịch thu, hãy tính cơ sở đã điều chỉnh và khoản nợ chưa thanh toán trước, rồi thiết kế giao dịch sau; đảo ngược thứ tự là cách để phát hiện, sau khi đóng giao dịch, một hóa đơn thuế lớn hơn số tiền mặt thu được.

### हिन्दी (अनुवाद)
Crane के फुटनोट 37 ने जो प्रश्न आरक्षित रखा था, वह यह था: यदि भवन का मूल्य केवल $1.4 million है लेकिन $1.85 million ऋण बकाया है, और विक्रेता को कोई नकद नहीं मिलता, तो क्या प्राप्त राशि फिर भी पूरा ऋण होगी? Commissioner v. Tufts, 461 U.S. 300 (1983) में ठीक यही तथ्य प्रस्तुत हुए: साझेदारों ने एक अपार्टमेंट परियोजना का निपटान किया जिसका उचित बाजार मूल्य लगभग $1.4 million था, जबकि बिना-सहारा ऋण लगभग $1,851,500 बकाया था, और उन्होंने दावा किया कि प्राप्त राशि उचित बाजार मूल्य तक सीमित थी, जिससे हानि हुई। एकमत सर्वोच्च न्यायालय ने आयुक्त के पक्ष में निर्णय दिया: प्राप्त राशि पूरा बकाया ऋण है, और मूल्य का ऋण से कम होना अप्रासंगिक है। तर्क वही समरूपता है — ऋण की राशि कर-मुक्त प्राप्त हुई थी और पूरी तरह आधार में शामिल की गई थी, जिससे मूल्यह्रास समर्थित हुआ, इसलिए निपटान पर इसका पूरा हिसाब देना होगा; प्राप्ति को मूल्य तक सीमित करने से करदाता को वह आर्थिक हानि दावा करने का अवसर मिलेगा जो उसने वास्तव में कभी नहीं उठाई।

दोनों मामले मिलकर एक पूर्ण नियम बनाते हैं। किसी भी समस्या को तीन चरणों में हल करें:

1. **आधार निश्चित करें**: खरीद मूल्य (ऋण सहित) या विरासत में मिला मूल्य, जिसमें से अनुमत या अनुमेय मूल्यह्रास घटा दें, तो समायोजित आधार मिलता है। मूल्यह्रास धारा 1016 के तहत अनुमेय आधार पर आधार को कम करता है, चाहे करदाता ने वास्तव में पूरा दावा किया हो या न हो, इसलिए मूल्यह्रास का कम दावा करने से आधार सुरक्षित नहीं रहता।
2. **प्राप्त राशि निश्चित करें**: नकद और अन्य प्रतिफल, साथ में खरीदार द्वारा ग्रहण किए गए या निपटान पर समाप्त हुए ऋण का पूरा शेष — इस बात की परवाह किए बिना कि संपत्ति का मूल्य अब ऋण से कम है या नहीं।
3. **अंत में वर्गीकरण करें**: केवल तभी लाभ को संपत्ति के स्वरूप और धारण अवधि के अनुसार पूंजीगत और साधारण घटकों, जैसे मूल्यह्रास की पुनः प्राप्ति (recapture), में बाँटें। परीक्षा की समस्याएँ तब गलत होती हैं जब पहले दो आँकड़े निश्चित किए जाने से पहले वर्गीकरण का प्रयास किया जाता है।

एक व्यावहारिक चेतावनी इस विषय को पूरा करती है: Crane-शैली का “प्रेत लाभ” (phantom gain) आज भी आम है — संपत्ति का मूल्य गिर गया है, बहुत कम या कोई नकद नहीं निकलता, और फिर भी कर देना पड़ता है क्योंकि ऋण प्राप्त राशि के अंदर बैठा है। अत्यधिक लीवरेज वाली संपत्ति को बेचने, पुनर्गठित करने या फोरक्लोज़र में सौंपने से पहले, पहले समायोजित आधार और बकाया ऋण की गणना करें और फिर लेनदेन की रूपरेखा बनाएँ; क्रम को उलटना ही वह तरीका है जिससे समापन के बाद नकद आय से बड़ी कर बिल की खोज होती है।

---

## 来源与声明

主要依据：Crane v. Commissioner, 331 U.S. 1 (1947) 判决原文（事实与数字：估值 262,042.50 美元、抵押本金 255,000 美元、可提折旧 28,045.10 美元、实现额 257,500 美元）；Commissioner v. Tufts, 461 U.S. 300 (1983)；IRC 第 61(a)(11)、1001、1012、1014、1016、108、7701(g) 条现行文本；Treas. Reg. 第 1.1001-2 条。税率与条文以 IRS 及法典现行公布文本为准，个案适用请复核最新修订。

本篇为个人学习笔记，不构成税务、财务或法律建议。具体事务请咨询持牌 CPA 或税务律师。

This article is a personal study note and does not constitute tax, financial, or legal advice. / Este artículo es una nota personal de estudio y no constituye asesoría fiscal, financiera ni legal. La versión en español es una traducción de estudio, pendiente de revisión por un hablante nativo.
