# 保险会计备考核心：ASC 944 长久期合同、LDTI 与市场风险福利

## 中文主文

### 一、先定位：保险会计为什么自成一科

保险合同的经济实质是「先收保费、后付赔款」，收入与成本在时间上严重错位，所以 ASC 944 单独成编：短久期合同（财产险、意外险为主）以未赚保费与赔案储备为核心，长久期合同（传统寿险、年金、长期失能、长期护理）以未来保单福利负债（liability for future policy benefits, LFPB）为核心。CPA 的 FAR 与 BAR 在保险行业专题里最爱考两件事：一是长久期负债的计量在《会计准则更新》ASU 2018-12（即 LDTI, Long-Duration Targeted Improvements）之后如何改口径，二是保险公司同时面对 GAAP 与州监管的法定会计（statutory accounting principles, SAP）双轨报表，两套口径的取向不同——GAAP 服务投资者、允许递延取得成本，SAP 服务偿付能力监管、取得成本当期费用化，这个对比是高频概念题。

### 二、LDTI 改了什么：四件套逐件记

ASU 2018-12 只动长久期合同的四处，每处都是考点：

1. **未来保单福利负债（LFPB）**：现金流假设（死亡率、退保率等）至少每年复核并更新，变更影响计入损益；净保费比率（net premium ratio）封顶 100%——预计未来福利现值除以预计未来总保费现值，超过 100% 的部分当期确认损失，不得递延。折现率改用「中上等级固定收益工具收益率」（upper-medium grade），每期更新，折现率变动的影响进其他综合收益（OCI），而不是损益。
2. **市场风险福利（market risk benefits, MRB）**：年金等合同里由保户承担以外、使保险公司暴露于资本市场风险的保证条款（如保证最低身故或提款利益），统一归类为 MRB，一律按公允价值计量，公允价值变动进损益，但归因于保险公司自身信用风险的部分进 OCI。
3. **递延取得成本（DAC）简化**：取消按保费或利润比例摊销的复杂模型，改为在合同预期存续期内按固定水平基础（constant-level basis）摊销，且不再做减值测试；摊销只与时间（及合同组别的预期存续）挂钩，不再与实际退保或利润实现联动。
4. **披露滚动表**：LFPB 与 MRB 都要给出期初到期末的滚动调节表（rollforward），把新签、计息、假设变更、实际与预期差异、赔付等驱动因素拆开列示——披露从「给个余额」升级为「讲清变动」，这是 LDTI 最直观的变化。

### 三、教学算例：净保费比率与 DAC 摊销

某传统寿险合同组别：预计未来福利现值 800,000 美元，预计未来总保费现值 1,000,000 美元，则净保费比率＝800,000 ÷ 1,000,000＝80%。含义是每收 1 美元保费（现值口径），其中 0.80 美元计为当期赚得的「净保费」用于承接福利成本，其余部分对应附加与利润边际。若假设复核后预计未来福利现值升至 1,050,000 美元，比率变为 105%，超过 100% 封顶——超出部分对应的负债缺口须当期进损益确认，不能靠未来保费慢慢填。这正是 LDTI 防「亏损递延」的核心机关。

DAC 侧：设某合同组别可递延取得成本 90,000 美元，预期存续期 15 年，按固定水平基础摊销，年摊销额＝90,000 ÷ 15＝6,000 美元，无论当年实际退保多少、利润多少，摊销额不随之波动（合同提前终止时未摊余额按规则处理）。与旧模型下「按预期总利润比例摊销、每年重估回溯调整」相比，算账从估计驱动变成时间驱动，备考判断题遇到「DAC 摊销随实际利润变动」应判错。

### 四、生效日与衔接：数字要记牢

LDTI 的生效日经 ASU 2020-11 推迟后定版：对符合 SEC 申报人定义且非小型报告公司的公众企业，自 2022 年 12 月 15 日之后开始的财政年度生效（含其中间期）；对所有其他实体，自 2024 年 12 月 15 日之后开始的财政年度生效（年度），中间期则顺延至 2025 年 12 月 15 日之后开始的财政年度内的期间。衔接以追溯法为主，转换日为所列报最早期间的期初。考试若问「非公众保险公司哪一年开始执行 LDTI 年度规定」，答案落在 2025 年开始的财政年度（即 2024-12-15 之后开始者）。

### 五、短久期一侧与双轨对比收束

短久期合同没有被 LDTI 触动，仍按老框架：保费在保障期内按比例赚取，未赚保费负债随时间释放；未付赔案及理赔费用（含已发生未报告 IBNR）按估计确认，估计变更计入当期。备考收束清单：①LFPB 假设年年更新、比率封顶 100%、折现进 OCI；②MRB 恒按公允价值、自有信用进 OCI；③DAC 固定水平摊销、不测减值；④滚动表披露是 LDTI 的标志动作；⑤GAAP 与 SAP 双轨：DAC 能否递延是最顺手的区分点。

*声明：个人学习笔记，不构成税务、审计或财务建议。来源：FASB ASC 944；ASU 2018-12 与 ASU 2020-11（LDTI 生效日）；AICPA 考试大纲（FAR/BAR 行业专题）。现行口径以 FASB 汇编原文为准。*

## English

Insurance accounting sits in ASC 944 because premiums are collected long before claims are paid. The CPA exams focus on long-duration contracts (traditional life, annuities, long-term disability and care) after ASU 2018-12, the Long-Duration Targeted Improvements (LDTI), which changed four things. First, the liability for future policy benefits (LFPB): cash-flow assumptions are reviewed and updated at least annually with changes in earnings; the net premium ratio — present value of expected future benefits divided by present value of expected future gross premiums — is capped at 100%, so any excess is recognized immediately rather than deferred; and the discount rate is an upper-medium grade fixed-income yield, updated each period with the effect in OCI. Second, market risk benefits (MRBs) — guarantees that expose the insurer to capital-market risk, such as guaranteed minimum death or withdrawal benefits — are measured at fair value, with changes in earnings except the portion attributable to the insurer's own credit risk, which goes to OCI. Third, deferred acquisition costs (DAC) are simplified: amortization on a constant-level basis over the expected contract term, with no impairment test. Fourth, LDTI requires rollforward disclosures for both LFPB and MRBs.

Worked example: expected future benefits of $800,000 against expected gross premiums of $1,000,000 give a net premium ratio of 80%. If an assumption update lifts expected benefits to $1,050,000, the 105% ratio hits the 100% cap and the shortfall is recognized in earnings at once — LDTI's anti-deferral mechanism. For DAC, $90,000 amortized over a 15-year expected term is $6,000 per year regardless of actual lapses or profits. Effective dates (after the ASU 2020-11 deferral): SEC filers that are not smaller reporting companies apply LDTI for fiscal years beginning after December 15, 2022; all other entities for fiscal years beginning after December 15, 2024, with interim periods a year later. Short-duration contracts were untouched: premiums are earned pro rata and unpaid claims, including IBNR, are estimated with changes in current earnings. Finally, insurers report under both GAAP and statutory accounting principles (SAP): SAP expenses acquisition costs immediately in the name of solvency, while GAAP defers them — the cleanest exam contrast between the two bases.

*Personal study notes only; not tax, audit, or financial advice.*

## Español (traducción de estudio, pendiente de revisión nativa)

La contabilidad de seguros vive en el ASC 944 porque las primas se cobran mucho antes de pagar los siniestros. El examen CPA se concentra en los contratos de larga duración tras el ASU 2018-12 (LDTI), que cambió cuatro piezas. Primero, el pasivo por beneficios futuros de póliza (LFPB): los supuestos de flujo de efectivo se revisan y actualizan al menos una vez al año, con cambios en resultados; la razón de prima neta —valor presente de beneficios futuros esperados dividido entre primas brutas futuras esperadas— tiene un tope del 100%, y cualquier exceso se reconoce de inmediato; la tasa de descuento es un rendimiento de instrumentos de renta fija de grado medio-alto, actualizado cada período con efecto en otro resultado integral (OCI). Segundo, los beneficios de riesgo de mercado (MRB) —garantías que exponen a la aseguradora al riesgo de los mercados de capitales— se miden a valor razonable, con cambios en resultados salvo la parte atribuible al riesgo de crédito propio, que va a OCI. Tercero, los costos de adquisición diferidos (DAC) se simplifican: amortización sobre una base de nivel constante durante la vigencia esperada del contrato, sin prueba de deterioro. Cuarto, se exigen tablas de movimiento (rollforwards) para LFPB y MRB.

Ejemplo: beneficios esperados de 800,000 dólares frente a primas esperadas de 1,000,000 dan una razón de prima neta del 80%; si una actualización eleva los beneficios a 1,050,000, la razón del 105% choca con el tope del 100% y el déficit se reconoce en resultados de inmediato. Un DAC de 90,000 a 15 años se amortiza a 6,000 por año, sin depender de caducidades ni beneficios reales. Fechas de vigencia (tras el aplazamiento del ASU 2020-11): para declarantes SEC que no sean compañías reportantes pequeñas, ejercicios iniciados después del 15 de diciembre de 2022; para las demás entidades, ejercicios iniciados después del 15 de diciembre de 2024, con períodos intermedios un año después. Los contratos de corta duración no cambiaron. Y recuerde el contraste de examen: bajo los principios estatutarios (SAP) los costos de adquisición se gastan de inmediato por prudencia de solvencia, mientras que GAAP los difiere.

*Notas personales de estudio; no constituyen asesoría fiscal, de auditoría ni financiera.*

## 한국어 (초역, 원어민 감수 대기)

보험 회계는 보험료를 먼저 받고 보험금은 나중에 지급하는 구조 때문에 ASC 944에 따로 자리합니다. CPA 시험은 ASU 2018-12(LDTI) 이후의 장기계약 회계에 집중하는데, 바뀐 것은 네 가지입니다. 첫째, 미래급부부채(LFPB): 현금흐름 가정을 최소 매년 재검토·갱신하고 변경 효과는 손익에 반영합니다. 순보험료비율(미래급부 현가 ÷ 미래 총보험료 현가)은 100%가 상한이라 초과분은 이연하지 않고 즉시 인식합니다. 할인율은 중상위 등급 고정수익 수익률을 쓰고 매기 갱신하되 그 효과는 기타포괄손익(OCI)으로 보냅니다. 둘째, 시장위험급부(MRB)는 자본시장 위험에 노출되는 보증 조항으로, 공정가치로 측정하고 변동은 손익에 반영하되 자사 신용위험에 기인하는 부분만 OCI로 보냅니다. 셋째, 이연신계약비(DAC)는 단순화되어 예상 존속기간에 걸쳐 정액 수준(constant-level)으로 상각하고 손상검사는 하지 않습니다. 넷째, LFPB와 MRB 모두 기초에서 기말까지의 변동표(rollforward) 공시가 요구됩니다.

예시로, 미래급부 현가 800,000달러, 총보험료 현가 1,000,000달러이면 순보험료비율은 80%입니다. 가정 갱신으로 급부가 1,050,000달러가 되면 비율은 105%가 되어 100% 상한에 걸리고, 부족분은 즉시 손익에 인식됩니다. DAC 90,000달러를 15년에 걸쳐 상각하면 연 6,000달러로, 실제 해지나 이익과 무관합니다. 시행일(ASU 2020-11로 연기된 뒤 확정)은 소규모 보고회사가 아닌 SEC 신고기업은 2022년 12월 15일 이후 시작하는 회계연도부터, 그 밖의 모든 기업은 2024년 12월 15일 이후 시작하는 회계연도부터(중간기간은 1년 뒤)입니다. 단기계약은 바뀌지 않았고, 법정회계(SAP)는 취득비를 즉시 비용화한다는 점이 GAAP와의 대표적 대비 포인트입니다.

*개인 학습 노트이며 세무·감사·재무 자문이 아닙니다.*

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

Kế toán bảo hiểm nằm tại ASC 944 vì phí bảo hiểm thu trước rất lâu so với chi trả bồi thường. Kỳ thi CPA tập trung vào hợp đồng dài hạn sau ASU 2018-12 (LDTI) với bốn thay đổi. Thứ nhất, nợ phải trả quyền lợi bảo hiểm tương lai (LFPB): các giả định dòng tiền được rà soát và cập nhật ít nhất hằng năm, thay đổi ghi vào kết quả kinh doanh; tỷ lệ phí thuần — giá trị hiện tại của quyền lợi tương lai dự kiến chia cho giá trị hiện tại của tổng phí dự kiến — bị chặn ở mức 100%, phần vượt phải ghi nhận ngay chứ không được hoãn; tỷ lệ chiết khấu dùng lợi suất trái phiếu hạng trung-cao, cập nhật mỗi kỳ và ảnh hưởng ghi vào thu nhập toàn diện khác (OCI). Thứ hai, quyền lợi rủi ro thị trường (MRB) — các điều khoản bảo đảm khiến hãng bảo hiểm chịu rủi ro thị trường vốn — được đo theo giá trị hợp lý, biến động ghi vào kết quả kinh doanh, trừ phần do rủi ro tín dụng của chính hãng thì ghi vào OCI. Thứ ba, chi phí khai thác hoãn lại (DAC) được đơn giản hóa: khấu hao theo mức cố định trên thời hạn hợp đồng dự kiến, không kiểm tra suy giảm. Thứ tư, LDTI yêu cầu bảng biến động (rollforward) cho cả LFPB và MRB.

Ví dụ: quyền lợi dự kiến 800.000 đô la trên tổng phí dự kiến 1.000.000 đô la cho tỷ lệ phí thuần 80%; nếu cập nhật giả định nâng quyền lợi lên 1.050.000 đô la, tỷ lệ 105% chạm trần 100% và phần thiếu phải ghi nhận ngay vào kết quả. DAC 90.000 đô la trên 15 năm là 6.000 đô la mỗi năm, không phụ thuộc hủy ngang hay lợi nhuận thực tế. Ngày hiệu lực (sau khi ASU 2020-11 hoãn): đơn vị nộp hồ sơ SEC không phải công ty báo cáo nhỏ áp dụng cho năm tài chính bắt đầu sau 15/12/2022; mọi đơn vị còn lại cho năm tài chính bắt đầu sau 15/12/2024, kỳ giữa niên độ chậm hơn một năm. Hợp đồng ngắn hạn không thay đổi, và hãy nhớ điểm đối chiếu kinh điển: theo kế toán luật định (SAP), chi phí khai thác ghi chi phí ngay vì thận trọng khả năng thanh toán, trong khi GAAP được hoãn lại.

*Ghi chú học tập cá nhân; không phải tư vấn thuế, kiểm toán hay tài chính.*

## हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

बीमा लेखांकन ASC 944 में अलग है क्योंकि प्रीमियम दावों के भुगतान से बहुत पहले वसूला जाता है। CPA परीक्षा ASU 2018-12 (LDTI) के बाद दीर्घ-अवधि अनुबंधों पर केंद्रित है, जिसमें चार बदलाव आए। पहला, भावी पॉलिसी-लाभ दायित्व (LFPB): नकदी-प्रवाह मान्यताओं की कम से कम वार्षिक समीक्षा व अद्यतन होता है और परिवर्तन आय में जाते हैं; शुद्ध प्रीमियम अनुपात — अपेक्षित भावी लाभों का वर्तमान मूल्य ÷ अपेक्षित भावी सकल प्रीमियम का वर्तमान मूल्य — 100% पर सीमित है, अधिकता तुरंत मान्य होती है; छूट-दर ऊपरी-मध्यम श्रेणी के निश्चित-आय प्रतिफल पर आधारित है, हर अवधि अद्यतित, प्रभाव OCI में। दूसरा, बाज़ार-जोखिम लाभ (MRB) — पूंजी-बाज़ार जोखिम उजागर करने वाली गारंटियाँ — उचित मूल्य पर मापे जाते हैं, परिवर्तन आय में, सिवाय अपने ही साख-जोखिम वाले हिस्से के, जो OCI में जाता है। तीसरा, आस्थगित अधिग्रहण लागत (DAC) सरल हुई: अपेक्षित अनुबंध-अवधि में स्थिर-स्तर आधार पर परिशोधन, कोई हानि-परीक्षण नहीं। चौथा, LFPB और MRB दोनों के लिए रोलफ़ॉरवर्ड प्रकटीकरण अनिवार्य है।

उदाहरण: अपेक्षित लाभ 800,000 डॉलर और अपेक्षित प्रीमियम 1,000,000 डॉलर हों तो शुद्ध प्रीमियम अनुपात 80% है; मान्यता-अद्यतन से लाभ 1,050,000 डॉलर हो जाएँ तो अनुपात 105% होकर 100% सीमा से टकराएगा और घाटा तुरंत आय में मान्य होगा। 90,000 डॉलर DAC का 15 वर्षों में परिशोधन प्रति वर्ष 6,000 डॉलर है, वास्तविक समाप्ति या लाभ से असंबद्ध। प्रभावी तिथियाँ (ASU 2020-11 के स्थगन के बाद): छोटे रिपोर्टर न होने वाले SEC फ़ाइलर के लिए 15 दिसंबर 2022 के बाद शुरू होने वाले वित्तीय वर्षों से; अन्य सभी संस्थाओं के लिए 15 दिसंबर 2024 के बाद शुरू होने वाले वित्तीय वर्षों से, अंतरिम अवधियाँ एक वर्ष बाद। लघु-अवधि अनुबंध अपरिवर्तित रहे, और परीक्षा का प्रमुख अंतर याद रखें: सांविधिक लेखांकन (SAP) शोधन-क्षमता की सावधानी से अधिग्रहण लागत तुरंत व्यय करता है, जबकि GAAP उसे आस्थगित करता है।

*व्यक्तिगत अध्ययन नोट; कर, लेखापरीक्षा या वित्तीय सलाह नहीं।*

## 补译增量 · 한국어 / Tiếng Việt / हिन्दी（细节对齐）

한국어: 중국어 본문의 세부 사항 두 가지를 보충합니다. 첫째, 롤포워드(rollforward) 공시의 내용입니다. LFPB와 MRB의 롤포워드는 기초 잔액과 기말 잔액을 잇는 표인데, 그 사이에 신규 발행, 이자 누적(계상), 가정 변경, 실제와 예상의 차이, 급부 지급 같은 변동 동인을 나눠서 표시해야 합니다. 즉 공시가 '잔액 하나를 제시하는 것'에서 '변동을 설명하는 것'으로 격상된 것이며, 이것이 LDTI에서 가장 눈에 띄는 변화입니다. 둘째, 단기계약 쪽의 기존 틀입니다. 단기계약은 LDTI의 영향을 받지 않았고, 보험료는 보장기간에 걸쳐 비례적으로 수익으로 인식되며 미지급 보험금과 손해사정비용(발생했지만 보고되지 않은 IBNR 포함)은 추정치로 인식하고 추정 변경은 당기에 반영합니다. 수험 마무리로 다섯 가지를 묶어 두면 좋습니다: LFPB 가정은 매년 갱신·비율은 100% 상한·할인은 OCI; MRB는 항상 공정가치·자사 신용 부분은 OCI; DAC는 정액 수준 상각·손상검사 없음; 롤포워드 공시가 LDTI의 상징적 동작; GAAP와 SAP의 이중 구조에서 DAC 이연 가능 여부가 가장 손쉬운 구분점입니다. (초역, 원어민 감수 대기)

Tiếng Việt: Bổ sung hai chi tiết từ phần chính tiếng Trung. Thứ nhất, nội dung của bảng biến động (rollforward): cả LFPB và MRB đều phải trình bày bảng nối số dư đầu kỳ đến cuối kỳ, trong đó tách riêng các yếu tố gây biến động — phát hành mới, tích lũy lãi, thay đổi giả định, chênh lệch giữa thực tế và dự kiến, và chi trả quyền lợi. Nói cách khác, công bố thông tin đã nâng cấp từ 'đưa ra một số dư' thành 'giải thích rõ biến động', và đây là thay đổi trực quan nhất của LDTI. Thứ hai, khuôn khổ cũ của hợp đồng ngắn hạn: hợp đồng ngắn hạn không bị LDTI đụng tới, phí bảo hiểm được ghi nhận doanh thu theo tỷ lệ trong thời gian bảo hiểm, bồi thường chưa thanh toán và chi phí giám định (bao gồm IBNR — đã phát sinh nhưng chưa báo cáo) được ghi nhận theo ước tính, và thay đổi ước tính đi vào kết quả kỳ hiện tại. Danh sách chốt cho ôn thi: giả định LFPB cập nhật hằng năm, tỷ lệ bị chặn ở 100%, chiết khấu vào OCI; MRB luôn theo giá trị hợp lý, phần tín dụng của chính hãng vào OCI; DAC khấu hao mức cố định, không kiểm tra suy giảm; công bố rollforward là dấu ấn của LDTI; và trong cấu trúc hai đường GAAP/SAP, việc DAC có được hoãn hay không là điểm phân biệt tiện nhất. (bản dịch sơ bộ, chờ hiệu đính)

हिन्दी: चीनी मुख्य पाठ के दो विवरण जोड़े जाते हैं। पहला, रोलफ़ॉरवर्ड (rollforward) प्रकटीकरण की सामग्री: LFPB और MRB दोनों के लिए आरंभिक शेष से अंतिम शेष तक की मेल-जोल तालिका देनी होती है, जिसमें नए निर्गम, ब्याज संचय, मान्यता परिवर्तन, वास्तविक बनाम अपेक्षित अंतर और लाभ-भुगतान जैसे परिवर्तन-कारकों को अलग-अलग दिखाया जाता है। अर्थात प्रकटीकरण 'एक शेष बता देने' से उन्नत होकर 'परिवर्तन की व्याख्या करने' तक पहुँचा है, और यही LDTI का सबसे दृश्यमान बदलाव है। दूसरा, लघु-अवधि पक्ष का पुराना ढाँचा: लघु-अवधि अनुबंधों को LDTI ने नहीं छुआ; प्रीमियम कवरेज अवधि में आनुपातिक रूप से अर्जित होता है, अदत्त दावे और दावा-व्यय (IBNR — घटित किंतु अप्रतिवेदित — सहित) अनुमान से मान्य होते हैं और अनुमान-परिवर्तन चालू अवधि में जाता है। परीक्षा के लिए समापन सूची: LFPB मान्यताएँ हर वर्ष अद्यतित, अनुपात 100% पर सीमित, छूट OCI में; MRB सदैव उचित मूल्य पर, स्वयं-साख हिस्सा OCI में; DAC स्थिर-स्तर परिशोधन, कोई हानि-परीक्षण नहीं; रोलफ़ॉरवर्ड प्रकटीकरण LDTI की पहचान है; और GAAP व SAP द्वैध ढाँचे में DAC आस्थगित हो सकता है या नहीं, यही सबसे आसान विभेदक बिंदु है। (प्रारंभिक अनुवाद, समीक्षा लंबित)
