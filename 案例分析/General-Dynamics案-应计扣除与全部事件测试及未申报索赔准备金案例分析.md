# 案例分析：United States v. General Dynamics Corp. 案——应计扣除与全部事件测试、未申报索赔准备金为什么不能提前扣

> 个人学习笔记，不构成税务建议。案名、卷号与年份以判决原文为准：United States v. General Dynamics Corp., 481 U.S. 239 (1987)，美国联邦最高法院。

## 中文主文

### 一、案情：自保医疗计划与一笔「肯定会发生」的准备金

General Dynamics 是大型雇主，采用权责发生制（accrual method）报税，并为员工医疗费用实行自保（self-insured）：公司不向保险公司买全额保险，而是自己承担员工医疗报销，第三方管理人负责受理与支付索赔。争议年度，公司按精算估计提取了一笔准备金，覆盖当年已经发生但尚未向其申报的医疗费用（incurred but not reported, IBNR）——员工已经看过病、义务在经济上几乎必然存在，只是报销单还没递上来。公司把这笔估计数在当年扣除了。IRS 不允许，双方一路打到最高法院，争点收窄为一个：**应计扣除的「全部事件测试」（all events test）在什么时候才算满足——义务在事实上已经发生，够不够？**

### 二、规则地基：§461 与全部事件测试的两条腿

权责发生制下，负债要应计扣除，通说与条例（Treas. Reg. §1.461-1(a)(2) 一线）要求全部事件测试通过，测试有两条腿：第一，确立负债存在的**全部事件已经发生**（义务的事实基础成立，不是或然的）；第二，负债金额能以**合理准确性确定**（economic performance 经济履行要件由 §461(h) 另行把关，本案年代该条刚入法，判决主要在第一条腿上展开）。本案的关键在于第一条腿的读法：公司主张，员工接受医疗服务这一刻，全部事件已经发生——看病是事实、公司报销义务来自既有计划条款，剩下只是走流程；政府主张，最后一个事件是员工**提交索赔**，因为计划安排下，未申报的索赔中有一部分永远不会被申报（员工忘了、离职了、金额太小懒得报），对那一部分而言，公司义务永远不会落到实处。

### 三、判决：5 比 4，估计再可靠也过不了第一条腿

最高法院以 5 比 4 支持政府，判这笔 IBNR 准备金当年不得扣除。多数意见的逻辑链条：

1. **事实发生不等于义务落定**：在本案的计划结构下，员工申报是义务成立的构成性环节，而不是纯粹的行政手续——经验数据恰恰证明，总有一部分已发生的医疗服务永远不会转化为公司的付款义务。
2. **统计可靠性救不了它**：公司强调精算估计在整体上相当准确（大数法则下总额可预测）。法院回答：全部事件测试问的是每一笔负债的事件是否齐备，不是问总额估得准不准；以群体统计的可靠性，替代逐笔义务的确定性，等于让估计准备金普遍可扣，这与权责发生制下禁止一般准备金（general reserves）的长期立场冲突。
3. **先例坐标**：判决与 United States v. Hughes Properties, Inc., 476 U.S. 593 (1986) 一线相承——彼案累进奖池的付款义务由内华达州法锁死、无人能免，全部事件才告成立；与之相对，本案义务还悬在员工是否申报这个未定事件上。早年的账面估计扣除口径（如应收坏账准备的税法特别规则）属于立法另行开的口子，不能反推一般原则。

### 四、 dissent 与张力点

反对意见认为，多数意见把「申报」抬高成了义务的构成事件，实际上让扣除时点取决于员工的文书勤奋程度，与经济现实脱节：公司年末的真实经济负担并不会因为报销单晚到一个月而消失。这一分歧点明了本案留给实务的张力：全部事件测试守的是**确定性**，应计会计（财务报告口径）守的是**配比与如实反映**，同一笔 IBNR 在 GAAP 报表上照提准备、在税表上却要加回，两套口径的差异正是递延所得税的日常来源。

### 五、实务与备考落点

1. **三问顺序**：判应计扣除，先问全部事件齐备没有（尤其最后一个构成事件是什么），再问金额能否合理确定，最后问 §461(h) 经济履行走到哪一步（服务/财产提供、付款等分项规则）。
2. **准备金四分类**：坏账（税法有 §166 的具体查核/冲销规则）、保修与返利（看义务结构与履行时点）、自保医疗 IBNR（本案：申报前不可扣）、诉讼或有（§461 与或有负债立场：争议中的索赔一般更晚）——分类不同，答案不同，禁止用「估计可靠」一语通杀。
3. **考试触发词**：题目出现「estimated」「actuarially sound」「incurred but not reported」，第一反应就是 General Dynamics：估计的可靠性不是测试内容，事件的完备性才是。
4. **后续立法背景**：§461(h) 经济履行规则与 §461(l) 一线后来把时点问题进一步成文化，但本案确立的「最后一个事件未到、扣除不成立」仍是分析起点；另注意 §404、§419 等雇主福利计划条款对特定项目的专门时点规定，专门规则优先于一般测试。

*个人学习笔记，不构成税务建议。*

## English

United States v. General Dynamics Corp., 481 U.S. 239 (1987). The taxpayer, an accrual-method employer, self-insured its employee medical plan and deducted an actuarially estimated reserve for medical care that employees had already received but had not yet claimed — incurred but not reported (IBNR) liabilities. The Supreme Court, 5–4, denied the deduction. Under the all events test for accrual deductions (see Treas. Reg. §1.461-1(a)(2)), the events fixing the liability must all have occurred and the amount must be determinable with reasonable accuracy. The majority held that, under this plan's structure, the filing of a claim was the last event fixing liability: experience showed that some incurred services would never be claimed at all, so as to those amounts no liability ever came into existence. Statistical reliability of the aggregate estimate was beside the point — the test asks whether each liability's fixing events are complete, not whether a total can be predicted, and allowing the reserve would have opened the door to general contingency reserves that accrual accounting for tax has long rejected. The Court aligned the case with United States v. Hughes Properties, 476 U.S. 593 (1986), where state law had irrevocably fixed the obligation. The dissent objected that making deductibility turn on employees' paperwork divorced the deduction from economic reality. Practical takeaways: an IBNR reserve is booked under GAAP but added back for tax, a routine deferred-tax item; classify reserves before analyzing them (bad debts follow §166, self-insured medical IBNR follows this case); and whenever a fact pattern stresses that an estimate is actuarially sound, the issue is event completeness, not estimation quality — with §461(h) economic performance as the separate next gate. *Study notes only, not tax advice.*

## Español (traducción de estudio)

United States v. General Dynamics Corp., 481 U.S. 239 (1987). El contribuyente, empleador en base devengada, autoaseguraba el plan médico de sus empleados y dedujo una reserva estimada actuarialmente por atenciones médicas ya recibidas pero aún no reclamadas (IBNR, incurridas pero no reportadas). La Corte Suprema, por 5 a 4, rechazó la deducción. Según la prueba de todos los eventos (all events test, véase Treas. Reg. §1.461-1(a)(2)), deben haber ocurrido todos los eventos que fijan la obligación y el monto debe ser determinable con precisión razonable. La mayoría sostuvo que, en la estructura de este plan, la presentación de la reclamación era el último evento fijador: la experiencia mostraba que una parte de los servicios incurridos jamás se reclamaría, de modo que para esa parte la obligación nunca llegaba a existir. La confiabilidad estadística de la estimación global era irrelevante: la prueba pregunta por la completitud de los eventos de cada obligación, no por la predictibilidad del total, y aceptar la reserva abriría la puerta a reservas generales por contingencias. El caso se alineó con United States v. Hughes Properties, 476 U.S. 593 (1986), donde la ley estatal había fijado la obligación de modo irrevocable. El voto disidente objetó que hacer depender la deducción del papeleo del empleado la alejaba de la realidad económica. Lecciones prácticas: la reserva IBNR se registra en libros GAAP pero se revierte en la declaración fiscal (partida típica de impuesto diferido); cada tipo de reserva se analiza por su regla (cuentas incobrables por el §166, IBNR médico por este caso), y el §461(h) sobre cumplimiento económico es la puerta siguiente, separada. *Notas de estudio, no asesoría fiscal.*

## 한국어 (초역, 원어민 감수 대기)

United States v. General Dynamics Corp., 481 U.S. 239 (1987). 발생주의 납세자인 고용주는 직원 의료보험을 자가보험으로 운영하면서, 이미 제공됐으나 아직 청구되지 않은 의료비(IBNR)에 대해 계리 추정치로 준비금을 쌓고 이를 공제했다. 연방대법원은 5대 4로 공제를 부인했다. 발생주의 공제의 전부 사건 테스트(all events test, Treas. Reg. §1.461-1(a)(2) 참조)상 부채를 확정하는 모든 사건이 발생해야 하고 금액이 합리적 정확도로 확정 가능해야 한다. 다수의견은 이 플랜 구조에서는 직원의 청구 제출이 부채를 확정하는 마지막 사건이라고 봤다. 경험상 발생한 의료 중 일부는 영원히 청구되지 않으므로, 그 부분은 부채 자체가 성립하지 않는다. 총액 추정의 통계적 신뢰성은 쟁점이 아니다. 테스트는 총액 예측 가능성이 아니라 각 부채의 사건 완결성을 묻고, 이 준비금을 허용하면 일반 우발준비금 전반이 열리게 된다. 법원은 주법이 의무를 확정했던 United States v. Hughes Properties, 476 U.S. 593 (1986)와 궤를 같이했다. 반대의견은 공제 시점을 직원의 서류 제출에 거는 것이 경제 현실과 괴리된다고 비판했다. 실무 요점: IBNR 준비금은 GAAP 장부에는 잡히지만 세무상으로는 가산되어 이연세금의 일상적 원천이 되고, 준비금 유형(대손은 §166, 자가보험 의료 IBNR은 본 판결)별로 규칙이 다르며, §461(h) 경제적 이행은 그다음의 별도 관문이다. *학습 노트이며 세무 자문이 아니다.*

보충 번역（补译增量）: 시험 촉발어를 따로 외워 둡니다. 문제에 estimated, actuarially sound, incurred but not reported 같은 표현이 나오면 첫 반응은 General Dynamics여야 합니다. 시험이 묻는 것은 추정의 신뢰성이 아니라 사건의 완결성입니다. 응계 공제를 판단하는 세 단계 순서는 이렇습니다. 먼저 전부 사건이 갖춰졌는지(특히 마지막 구성 사건이 무엇인지)를 묻고, 다음으로 금액을 합리적 정확도로 확정할 수 있는지를 묻고, 마지막으로 §461(h) 경제적 이행이 어느 단계까지 왔는지를 봅니다. (초역, 원어민 감수 대기)

보충 번역（补译增量）: 준비금의 네 가지 분류도 구분해야 합니다. 대손은 §166에 특정상각(specific charge-off)에 관한 구체적인 규칙이 따로 있고, 보증과 리베이트는 의무 구조와 이행 시점에 따라 답이 달라지며, 자가보험 의료 IBNR은 본 판결대로 청구 전에 공제할 수 없고, 분쟁 중인 소송 우발채무는 일반적으로 더 늦게 공제가 성립합니다. 분류가 다르면 답이 다르므로, 추정이 신뢰할 만하다는 한마디로 전부 처리해서는 안 됩니다. 아울러 §404와 §419 등 고용주 복지계획에 관한 특별 시점 규정이 있는 항목에서는 그 특별 규칙이 일반 테스트에 우선합니다. (초역, 원어민 감수 대기)

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

United States v. General Dynamics Corp., 481 U.S. 239 (1987). Người nộp thuế là chủ lao động theo phương pháp dồn tích, tự bảo hiểm chương trình y tế cho nhân viên và khấu trừ một khoản dự phòng ước tính theo tính toán bảo hiểm cho chi phí y tế đã phát sinh nhưng chưa được yêu cầu bồi hoàn (IBNR). Tòa Tối cao, với tỷ lệ 5–4, bác bỏ khoản khấu trừ. Theo phép thử mọi sự kiện (all events test, xem Treas. Reg. §1.461-1(a)(2)), mọi sự kiện xác lập nghĩa vụ phải đã xảy ra và số tiền phải xác định được với độ chính xác hợp lý. Đa số cho rằng trong cấu trúc chương trình này, việc nhân viên nộp yêu cầu bồi hoàn là sự kiện cuối cùng xác lập nghĩa vụ: kinh nghiệm cho thấy một phần dịch vụ đã phát sinh sẽ không bao giờ được yêu cầu, nên phần đó nghĩa vụ không hề hình thành. Độ tin cậy thống kê của ước tính tổng thể không phải vấn đề: phép thử hỏi về tính hoàn tất sự kiện của từng nghĩa vụ, không hỏi khả năng dự đoán tổng số, và chấp nhận khoản dự phòng này sẽ mở cửa cho dự phòng dự liệu chung. Án lệ được đặt cạnh United States v. Hughes Properties, 476 U.S. 593 (1986), nơi luật bang đã cố định nghĩa vụ không thể thu hồi. Ý kiến bất đồng chỉ trích việc gắn khấu trừ vào thủ tục giấy tờ của nhân viên là xa rời thực tế kinh tế. Bài học thực hành: dự phòng IBNR được ghi trong sổ GAAP nhưng phải cộng lại khi tính thuế (nguồn thuế hoãn lại thường gặp); mỗi loại dự phòng có quy tắc riêng (nợ khó đòi theo §166, IBNR y tế tự bảo hiểm theo án này), và §461(h) về thực hiện kinh tế là cánh cổng riêng tiếp theo. *Ghi chú học tập, không phải tư vấn thuế.*

Phần dịch bổ sung（补译增量）: Hãy ghi nhớ riêng các từ khóa kích hoạt trong đề thi. Khi đề xuất hiện các từ estimated, actuarially sound hay incurred but not reported, phản xạ đầu tiên phải là General Dynamics: điều phép thử hỏi là tính hoàn tất của sự kiện, không phải độ tin cậy của ước tính. Trình tự ba câu hỏi để xét khấu trừ dồn tích là: trước hết mọi sự kiện đã đủ chưa, đặc biệt sự kiện cấu thành cuối cùng là gì; tiếp theo số tiền có xác định được với độ chính xác hợp lý không; cuối cùng thực hiện kinh tế theo §461(h) đã đi tới bước nào — cung cấp dịch vụ hay tài sản, thanh toán, và các quy tắc phân mục tương tự. (Bản dịch sơ bộ, chờ hiệu đính)

Phần dịch bổ sung（补译增量）: Cũng phải phân biệt bốn loại dự phòng. Nợ khó đòi có quy tắc riêng về xác minh và xóa sổ tại §166; bảo hành và hoàn tiền phụ thuộc cấu trúc nghĩa vụ và thời điểm thực hiện; IBNR y tế tự bảo hiểm, theo án này, không được khấu trừ trước khi có yêu cầu bồi hoàn; và các khoản nợ dự phòng đang tranh chấp trong kiện tụng thường còn muộn hơn nữa. Mỗi loại một đáp án, không được dùng một câu ước tính đáng tin cậy để xử lý tất cả. Ngoài ra, với các khoản có quy tắc thời điểm riêng trong các điều khoản phúc lợi người lao động như §404 và §419, quy tắc riêng đó ưu tiên hơn phép thử chung. (Bản dịch sơ bộ, chờ hiệu đính)

## हिन्दी (प्रारंभिक अनुवाद, समीक्षा लंबित)

United States v. General Dynamics Corp., 481 U.S. 239 (1987)। प्रोद्भवन (accrual) पद्धति वाला यह नियोक्ता अपने कर्मचारियों की चिकित्सा योजना का स्व-बीमा करता था और उसने उन चिकित्सा सेवाओं के लिए बीमांकिक अनुमान से आरक्षित राशि काटी जो मिल चुकी थीं पर जिनका दावा अभी दायर नहीं हुआ था (IBNR)। सर्वोच्च न्यायालय ने 5–4 से कटौती अस्वीकार की। प्रोद्भवन कटौती के all events test (देखें Treas. Reg. §1.461-1(a)(2)) के तहत देयता को निश्चित करने वाली सभी घटनाएँ घट चुकी होनी चाहिए और राशि उचित सटीकता से निर्धारित होनी चाहिए। बहुमत ने कहा कि इस योजना की संरचना में कर्मचारी का दावा दायर करना ही देयता निश्चित करने वाली अंतिम घटना थी: अनुभव दिखाता था कि कुछ प्राप्त सेवाओं का दावा कभी होगा ही नहीं, अतः उस हिस्से की देयता अस्तित्व में ही नहीं आई। कुल अनुमान की सांख्यिकीय विश्वसनीयता अप्रासंगिक थी — परीक्षण प्रत्येक देयता की घटना-पूर्णता पूछता है, कुल की पूर्वानुमेयता नहीं, और इस आरक्षित को स्वीकार करना सामान्य आकस्मिक आरक्षितों का द्वार खोल देता। न्यायालय ने United States v. Hughes Properties, 476 U.S. 593 (1986) से सामंजस्य रखा, जहाँ राज्य कानून ने देयता अपरिवर्तनीय रूप से निश्चित कर दी थी। असहमति ने आपत्ति की कि कटौती को कर्मचारी के कागज़ात से जोड़ना आर्थिक वास्तविकता से दूर है। व्यावहारिक सीख: IBNR आरक्षित GAAP बही में दर्ज होता है पर कर में वापस जोड़ा जाता है (आस्थगित कर की सामान्य मद); आरक्षित के प्रकार के अनुसार नियम अलग हैं (अप्राप्य ऋण §166 से, स्व-बीमित चिकित्सा IBNR इस निर्णय से), और §461(h) आर्थिक निष्पादन अगला अलग द्वार है। *केवल अध्ययन नोट, कर सलाह नहीं।*

पूरक अनुवाद（补译增量）: परीक्षा के संकेत-शब्द अलग से याद रखें। प्रश्न में estimated, actuarially sound या incurred but not reported जैसे शब्द आते ही पहली प्रतिक्रिया General Dynamics होनी चाहिए: परीक्षण अनुमान की विश्वसनीयता नहीं, घटनाओं की पूर्णता पूछता है। प्रोद्भवन कटौती परखने का त्रि-चरणीय क्रम यह है: पहले पूछें कि सभी घटनाएँ पूर्ण हुईं या नहीं, विशेषकर अंतिम घटक घटना कौन-सी है; फिर पूछें कि राशि उचित सटीकता से निर्धारित हो सकती है या नहीं; अंत में पूछें कि §461(h) आर्थिक निष्पादन किस चरण तक पहुँचा — सेवा या संपत्ति की आपूर्ति, भुगतान आदि उप-नियमों के अनुसार। (प्रारंभिक अनुवाद, समीक्षा लंबित)

पूरक अनुवाद（补译增量）: आरक्षितों का चार-वर्गीकरण भी अलग रखें। अप्राप्य ऋणों के लिए §166 में विशिष्ट सत्यापन और अपलेखन नियम हैं; वारंटी और छूट-वापसी का उत्तर दायित्व संरचना और निष्पादन समय पर निर्भर करता है; स्व-बीमित चिकित्सा IBNR इस निर्णय के अनुसार दावा दायर होने से पहले कटौती योग्य नहीं है; और विवादित मुक़दमेबाज़ी के आकस्मिक दायित्व सामान्यतः और भी बाद में बनते हैं। वर्ग अलग तो उत्तर अलग; अनुमान विश्वसनीय है कहकर सबको एक साथ निपटाना वर्जित है। साथ ही जहाँ §404 और §419 जैसे नियोक्ता कल्याण योजना प्रावधानों में किसी मद हेतु विशेष समय-नियम हो, वहाँ विशेष नियम सामान्य परीक्षण पर भारी पड़ता है। (प्रारंभिक अनुवाद, समीक्षा लंबित)
