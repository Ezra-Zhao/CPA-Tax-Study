# 超额经营损失怎么限：第 461(l) 条门槛、Form 461 与 NOL 结转及加州口径

> 个人学习笔记，不构成税务建议。门槛数字以 Rev. Proc. 当年公告与 Form 461 当年说明为准。

## 中文主文

### 一、这道关卡管谁、排第几：只限非公司纳税人，而且是最后一关

做生意亏了钱，能扣多少并不是算出净亏损就全额往其他收入上抵。《国内收入法典》第 461(l) 条专管非公司纳税人（noncorporate taxpayer）的超额经营损失（excess business loss）：个人、信托与遗产的经营损失，超过当年门槛的那一部分，当年不得扣除。公司纳税人不在本条射程内，C 公司自己的亏损走公司层面的规则，不要把本条套到公司税表上。

更要紧的是顺序。本条不是第一道关，而是最后一道：在它之前，纳税人要先依次过基数限制（投资基数不够，损失先挂起）、第 465 条风险限制（at-risk，不承担经济风险的部分先拦下）、第 469 条被动活动限制（被动损失一般只能抵被动收入），三关都过了、还能往下抵的经营损失，最后才到第 461(l) 条跟门槛比大小。备考与实务里把顺序记反是常见错误——顺序不同，挂起的原因、结转的性质与日后释放的条件都不同，不能混成一句「亏损被限制了」。计算落在 Form 461（Limitation on Business Losses）上，逐项把经营收入、经营扣除与门槛对完，再把结果带回主表。

### 二、门槛数字：2025 年与 2026 年对照，2026 年不升反降是最大的坑

第 461(l) 条的门槛按申报身份给数，原始数经通胀调整后逐年由 IRS 以收入程序（Revenue Procedure）公布。两个相邻年份的数字放在一起看，反常之处一眼可见：

- 2025 年：单身及其他一般身份 313,000 美元，夫妻合报 626,000 美元（Rev. Proc. 2024-40 第 3.32 节）。
- 2026 年：单身及其他一般身份 256,000 美元，夫妻合报 512,000 美元（Rev. Proc. 2025-32 第 4.31 节）。

物价还在涨，门槛却从 313,000 掉到 256,000，单身口径整整少了 57,000 美元，合报口径少了 114,000 美元。原因不在算错，而在立法重置了起算点：OBBBA（Pub. L. 119-21）第 70601 节做了两件事——第一，把第 461(l) 条限制改为永久，取消了原定的日落安排，这道关卡不会再自动到期消失；第二，把通胀调整的起算基年重置为 2024 年，等于把前几年累计放大的基数收回去重新起算。基年一重置，2026 年算出来的门槛自然低于 2025 年。用 2025 年的数字去预估 2026 年能扣多少，会系统性地高估可扣额、做错预估税与交易测算，这是本篇最值得划线的一处：跨年比较税法数字时，先确认基年与法版有没有被改过，再谈涨跌。

门槛的比法也要说清：比的是净额。先把当年的经营收入与经营扣除轧差得出净经营损益，再看净损失超过门槛多少；有经营收入顶着的年份，能容纳的毛损失比「无经营收入、纯亏损」时更大。信托与遗产另有其门槛适用口径，以 Form 461 当年说明为准，本文算例只走个人口径。

### 三、超额部分去哪了：当年不得扣，转成 NOL 向后结转

超过门槛的那部分并非被没收，而是换了一件衣服往后走：超额经营损失在次年起视为第 172 条下的净经营损失（net operating loss，NOL），按 NOL 的规则向后结转，在以后年度抵扣应税所得。结转不等于以后想抵多少就抵多少——现行第 172 条对这类结转 NOL 设了 80% 上限：以后年度使用结转 NOL 时，最多只能把当年应税所得抵掉 80%，剩下的 20% 仍要计税，结转本身则可无限期往后滚，直到用完为止。于是同一笔超额损失的时间价值被拉长：当年少抵的那一截，要分多年、打八折节奏慢慢收回，做现金流预测时不能按「明年全额补回」来算。还要注意身份转换：这笔金额一旦转成 NOL，后续年度就按 NOL 的身份与规则走，不再回到第 461(l) 条的门槛里重复计算；当年未超门槛、正常扣掉的部分则与结转无关，不受 80% 上限影响。

申报动作上，Form 461 负责算出当年可扣额与超额结转额，结转额进入 NOL 台账，后续年度用 Form 1045 或申报表上的 NOL 扣除行衔接（以当年表格说明为准）。台账要逐年留痕：哪一年产生多少超额、哪一年用了多少结转、还剩多少，光靠记忆在三五年后必然对不上。

### 四、算例：同一笔 40 万美元净损失，2025 年与 2026 年差出 57,000 美元（本地复算）

教学设定（数字自编，已复算两遍）：单身纳税人某年无经营收入、净经营损失 400,000 美元，已依次过完基数、风险与被动三关，只剩第 461(l) 条这一关。

放在 2026 年算：门槛 256,000 美元，当年可扣 256,000 美元，超额 ＝ 400,000 － 256,000 ＝ 144,000 美元，当年不得扣，转成第 172 条 NOL 向后结转，日后使用时受 80% 应税所得上限约束。

同样一笔放在 2025 年算：门槛 313,000 美元，当年可扣 313,000 美元，超额 ＝ 400,000 － 313,000 ＝ 87,000 美元。

两年对照：超额差 ＝ 144,000 － 87,000 ＝ 57,000 美元，恰与单身门槛的落差 313,000 － 256,000 ＝ 57,000 美元相等——亏损规模相同时，门槛降多少，超额就多多少，分毫不差。合报口径同理：门槛落差 626,000 － 512,000 ＝ 114,000 美元，同样规模的合报净损失在 2026 年会比在 2025 年多出 114,000 美元被推入结转。勾稽：400,000 － 256,000 ＝ 144,000；400,000 － 313,000 ＝ 87,000；144,000 － 87,000 ＝ 57,000，三项均已本地复算两遍一致。

### 五、加州口径：州表另行处理，不要把联邦算式直接搬过去

加州对第 461(l) 条的处理要谨慎下笔。加州税法按其自身的 IRC 从属日期（conformity date）口径衔接联邦规则，并未直接跟随第 461(l) 条的联邦计算把同一道门槛原样搬到州表上；州层面的经营损失与 NOL 结转自成一套规则与表格处理，近年州 NOL 还经历过暂停与恢复的阶段变化。因此联邦 Form 461 算出的可扣额与结转额，不能直接抄作加州数字：州税申报时须按 FTB 当期说明，分别核对州的损失限制与州 NOL 的产生、使用与结转余额，两本账分开建、分开对。本文只点明「联邦与加州算法分开、以 FTB 当期说明为准」这一口径，不对加州作「有或没有」之外的一刀切细节断言，以免把某一年的阶段规则写成永久结论。

### 六、易错清单

一，把第 461(l) 条套到 C 公司身上——本条只限非公司纳税人。二，把顺序记反，在被动损失还没过第 469 条之前就先比门槛——本条是最后一关。三，拿 2025 年的 313,000／626,000 去估 2026 年——2026 年已重置基年，数字是 256,000／512,000。四，以为超额部分被永久没收——它转成 NOL 结转，只是日后使用受 80% 上限约束。五，以为结转 NOL 明年可以全额抵光——每年最多抵当年应税所得的 80%。六，把联邦 Form 461 的结果直接抄到加州州表——州表另行处理，以 FTB 当期说明为准。

*来源：IRC §§ 461(l)、172、465、469；OBBBA（Pub. L. 119-21）§ 70601；Rev. Proc. 2024-40 § 3.32（2025 年门槛 313,000／626,000 美元）；Rev. Proc. 2025-32 § 4.31（2026 年门槛 256,000／512,000 美元）；IRS Form 461 当年说明；加州口径以 FTB 当期说明为准。算例为自编教学数字，已本地复算两遍一致。*

*声明：个人学习笔记，不构成税务建议。具体损失规划请咨询持牌 CPA 或税务律师。*

---

## English

**How the excess business loss limit works: the § 461(l) thresholds, Form 461, NOL carryforwards, and California.** Section 461(l) caps the business losses of noncorporate taxpayers only — individuals, trusts, and estates; C corporations are outside it. It is also the last gate, not the first: basis limits apply first, then the at-risk rules of § 465, then the passive activity rules of § 469, and only the loss that survives all three is tested against the § 461(l) threshold on Form 461 (Limitation on Business Losses). The threshold is applied to the net business result for the year. For 2025 the amounts are $313,000 for single filers and $626,000 for joint filers (Rev. Proc. 2024-40, § 3.32). For 2026 they fall — counterintuitively — to $256,000 and $512,000 (Rev. Proc. 2025-32, § 4.31). The drop is legislative, not an error: § 70601 of the OBBBA (P.L. 119-21) made the § 461(l) limitation permanent, removing its sunset, and reset the inflation-adjustment base year to 2024, wiping out the accumulated inflation built into the 2025 figures. Anyone who budgets a 2026 deduction using the 2025 numbers will overstate it by $57,000 on the single threshold and $114,000 on the joint threshold. The disallowed excess is not lost: it is treated from the next year as a net operating loss (NOL) under § 172, carried forward indefinitely but usable each year only up to 80% of that year's taxable income, so recovery is spread over time rather than taken at once. Example, recomputed locally twice: a single filer with a $400,000 net business loss and no business income, having cleared the earlier gates, deducts $256,000 in 2026 and carries $400,000 − $256,000 = $144,000 forward as an NOL; the identical loss in 2025 would have produced only $400,000 − $313,000 = $87,000 of excess — a $57,000 difference that exactly equals the threshold drop ($313,000 − $256,000 = $57,000; joint: $626,000 − $512,000 = $114,000). California must be handled separately and cautiously: under its own IRC conformity-date framework California does not simply import the federal § 461(l) computation, and state loss and NOL treatment follows its own forms and rules, so follow current FTB guidance rather than copying the federal Form 461 result onto the state return. *Personal study notes; not tax advice.*

## Español

**Cómo se limita la pérdida empresarial excedente: los umbrales del § 461(l), el Formulario 461, el arrastre como NOL y California.** El § 461(l) limita solo a los contribuyentes no societarios —personas físicas, fideicomisos y sucesiones—; las corporaciones C quedan fuera. Además es la última puerta, no la primera: primero operan los límites de base, después las reglas de riesgo del § 465 y después las de actividad pasiva del § 469, y solo la pérdida que supera las tres se contrasta con el umbral del § 461(l) en el Formulario 461. El umbral se aplica al resultado neto empresarial del año. Para 2025 los importes son 313.000 dólares para solteros y 626.000 para declaración conjunta (Rev. Proc. 2024-40, § 3.32). Para 2026 bajan —contra lo intuitivo— a 256.000 y 512.000 dólares (Rev. Proc. 2025-32, § 4.31). La bajada es legislativa, no un error: la § 70601 de la OBBBA (P.L. 119-21) hizo permanente la limitación del § 461(l), al eliminar su fecha de caducidad, y reinició el año base del ajuste por inflación a 2024, borrando la inflación acumulada que llevaban las cifras de 2025. Quien presupueste una deducción de 2026 con los números de 2025 la sobreestimará en 57.000 dólares en el umbral individual y en 114.000 en el conjunto. El exceso no admitido no se pierde: desde el año siguiente se trata como pérdida operativa neta (NOL) del § 172, arrastrable sin límite de años pero utilizable cada año solo hasta el 80 % de la renta imponible de ese año, así que la recuperación se reparte en el tiempo. Ejemplo, recalculado localmente dos veces: un soltero con pérdida neta empresarial de 400.000 dólares y sin ingresos empresariales, superadas las puertas anteriores, deduce 256.000 dólares en 2026 y arrastra 400.000 − 256.000 = 144.000 dólares como NOL; la misma pérdida en 2025 habría generado solo 400.000 − 313.000 = 87.000 dólares de exceso, una diferencia de 57.000 dólares idéntica a la caída del umbral (313.000 − 256.000 = 57.000; en conjunto, 626.000 − 512.000 = 114.000). California debe tratarse por separado y con cautela: con su propio marco de fecha de conformidad con el IRC, California no importa sin más el cálculo federal del § 461(l), y el tratamiento estatal de pérdidas y NOL sigue sus propios formularios y reglas, así que siga la guía vigente de la FTB en lugar de copiar el resultado federal del Formulario 461 en la declaración estatal. *Notas personales de estudio; no constituye asesoría fiscal.*

## 한국어 (초역, 원어민 감수 대기)

**초과 사업손실은 어떻게 제한되나: § 461(l) 문턱, Form 461, NOL 이월과 캘리포니아.** § 461(l)은 비법인 납세자, 즉 개인·신탁·유산에만 적용되며 C법인에는 적용되지 않습니다. 또한 이 조항은 첫 관문이 아니라 마지막 관문입니다. 먼저 취득원가(기초) 한도, 다음으로 § 465 위험부담(at-risk) 규칙, 그다음 § 469 수동활동 규칙을 차례로 통과한 손실만이 Form 461(Limitation on Business Losses)에서 § 461(l) 문턱과 비교됩니다. 문턱은 해당 연도의 순사업손익에 적용됩니다. 2025년 문턱은 독신 등 313,000달러, 부부합산 626,000달러입니다(Rev. Proc. 2024-40 § 3.32). 그런데 2026년 문턱은 오르지 않고 오히려 독신 256,000달러, 합산 512,000달러로 내려갑니다(Rev. Proc. 2025-32 § 4.31). 계산 오류가 아니라 입법 때문입니다. OBBBA(P.L. 119-21) § 70601은 § 461(l) 제한을 영구화해 일몰을 없애고, 물가연동 기준연도를 2024년으로 재설정해 2025년 수치에 쌓였던 누적 물가를 지웠습니다. 2025년 숫자로 2026년 공제를 가늠하면 독신 기준 57,000달러, 합산 기준 114,000달러를 과대평가하게 됩니다. 문턱을 넘는 초과분은 사라지지 않습니다. 다음 해부터 § 172의 순영업손실(NOL)로 취급돼 무기한 이월되지만, 매년 그해 과세소득의 80%까지만 사용할 수 있어 회복이 여러 해에 나뉩니다. 예시(로컬에서 두 번 재계산): 앞선 관문을 모두 통과한 독신 납세자가 사업소득 없이 순사업손실 400,000달러를 보면, 2026년에는 256,000달러를 공제하고 초과분 400,000 － 256,000 ＝ 144,000달러를 NOL로 이월합니다. 같은 손실을 2025년에 보면 초과분은 400,000 － 313,000 ＝ 87,000달러에 불과합니다. 차이 57,000달러는 문턱 하락분 313,000 － 256,000 ＝ 57,000달러와 정확히 같고, 합산으로는 626,000 － 512,000 ＝ 114,000달러입니다. 캘리포니아는 조심스럽게 별도로 다뤄야 합니다. 주는 자체 IRC 적용기준일(conformity date) 틀에 따라 연방 § 461(l) 계산을 그대로 들여오지 않으며, 주 차원의 손실과 NOL은 자체 양식과 규칙을 따르므로, 연방 Form 461 결과를 주 신고서에 그대로 옮기지 말고 FTB의 현행 안내를 확인하십시오. *개인 학습 노트이며 세무 자문이 아닙니다. (초역, 원어민 감수 대기)*

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

**Lỗ kinh doanh vượt mức bị giới hạn thế nào: các ngưỡng § 461(l), Mẫu 461, kết chuyển NOL và California.** Mục § 461(l) chỉ giới hạn người nộp thuế không phải công ty — cá nhân, tín thác và di sản thừa kế; công ty C nằm ngoài phạm vi này. Đây cũng là cánh cổng cuối cùng chứ không phải đầu tiên: trước hết là giới hạn giá vốn đầu tư, rồi đến quy tắc chịu rủi ro § 465, rồi quy tắc hoạt động thụ động § 469, và chỉ khoản lỗ vượt qua cả ba mới được đối chiếu với ngưỡng § 461(l) trên Mẫu 461. Ngưỡng áp dụng trên kết quả kinh doanh ròng của năm. Năm 2025, các mức là 313.000 đô la cho người độc thân và 626.000 đô la cho vợ chồng khai chung (Rev. Proc. 2024-40, § 3.32). Năm 2026, các mức ấy lại giảm — ngược trực giác — xuống 256.000 và 512.000 đô la (Rev. Proc. 2025-32, § 4.31). Sự sụt giảm này do luật định, không phải lỗi tính toán: § 70601 của OBBBA (P.L. 119-21) biến giới hạn § 461(l) thành vĩnh viễn, xóa bỏ điều khoản hết hạn, và đặt lại năm gốc điều chỉnh lạm phát thành năm 2024, xóa phần lạm phát tích lũy trong số liệu 2025. Ai dự toán khoản khấu trừ năm 2026 bằng số của năm 2025 sẽ ước cao hơn 57.000 đô la ở ngưỡng độc thân và 114.000 đô la ở ngưỡng khai chung. Phần vượt ngưỡng bị bác trong năm không mất đi: từ năm sau nó được coi là lỗ hoạt động ròng (NOL) theo § 172, kết chuyển vô thời hạn nhưng mỗi năm chỉ được dùng tối đa 80% thu nhập chịu thuế của năm đó, nên việc thu hồi trải dài theo thời gian. Ví dụ, đã tính lại tại chỗ hai lần: một người độc thân có lỗ kinh doanh ròng 400.000 đô la và không có thu nhập kinh doanh, đã qua các cổng trước, sẽ khấu trừ 256.000 đô la vào năm 2026 và kết chuyển 400.000 － 256.000 ＝ 144.000 đô la thành NOL; cùng khoản lỗ ấy vào năm 2025 chỉ tạo ra 400.000 － 313.000 ＝ 87.000 đô la phần vượt — chênh lệch 57.000 đô la đúng bằng mức giảm của ngưỡng (313.000 － 256.000 ＝ 57.000; khai chung: 626.000 － 512.000 ＝ 114.000). California phải xử lý riêng và thận trọng: theo khung ngày tuân thủ IRC riêng của bang, California không đơn thuần nhập nguyên phép tính § 461(l) của liên bang, và việc xử lý lỗ cùng NOL cấp bang tuân theo mẫu biểu và quy tắc riêng, vì vậy hãy làm theo hướng dẫn hiện hành của FTB thay vì sao chép kết quả Mẫu 461 liên bang sang tờ khai bang. *Ghi chú học tập cá nhân, không phải tư vấn thuế. (Bản dịch sơ bộ, chờ hiệu đính)*

## हिन्दी (प्रारंभिक अनुवाद, समीक्षा लंबित)

**अतिरिक्त व्यावसायिक हानि कैसे सीमित होती है: § 461(l) सीमाएँ, Form 461, NOL अग्रनयन और California।** धारा § 461(l) केवल ग़ैर-कॉर्पोरेट करदाताओं — व्यक्तियों, न्यासों और संपदाओं — को सीमित करती है; C निगम इसके दायरे से बाहर हैं। यह पहला द्वार भी नहीं, अंतिम द्वार है: पहले आधार (basis) सीमाएँ, फिर § 465 की जोखिम-आधारित (at-risk) नियमावली, फिर § 469 की निष्क्रिय गतिविधि नियमावली लागू होती है, और केवल तीनों को पार करने वाली हानि ही Form 461 पर § 461(l) सीमा से जाँची जाती है। सीमा वर्ष के शुद्ध व्यावसायिक परिणाम पर लागू होती है। 2025 के लिए राशियाँ एकल दाखिलकर्ताओं हेतु 313,000 डॉलर और संयुक्त हेतु 626,000 डॉलर हैं (Rev. Proc. 2024-40, § 3.32)। 2026 के लिए ये — सहज अपेक्षा के विपरीत — घटकर 256,000 और 512,000 डॉलर हो जाती हैं (Rev. Proc. 2025-32, § 4.31)। यह गिरावट विधायी है, गणना-त्रुटि नहीं: OBBBA (P.L. 119-21) की § 70601 ने § 461(l) सीमा को स्थायी बना दिया, उसकी समाप्ति हटा दी, और मुद्रास्फीति-समायोजन का आधार-वर्ष 2024 पर पुनः निर्धारित कर दिया, जिससे 2025 के आँकड़ों में जमा संचित मुद्रास्फीति मिट गई। जो कोई 2026 की कटौती का अनुमान 2025 के आँकड़ों से लगाएगा, वह एकल सीमा पर 57,000 डॉलर और संयुक्त सीमा पर 114,000 डॉलर अधिक गिनेगा। अस्वीकृत अतिरिक्त भाग नष्ट नहीं होता: अगले वर्ष से वह § 172 के तहत शुद्ध परिचालन हानि (NOL) माना जाता है, अनिश्चित काल तक अग्रनीत होता है, किंतु प्रत्येक वर्ष उस वर्ष की करयोग्य आय के अधिकतम 80% तक ही उपयोग हो सकता है, इसलिए वसूली समय में फैल जाती है। उदाहरण, स्थानीय रूप से दो बार पुनर्गणना किया गया: पूर्व द्वार पार कर चुका एकल करदाता यदि बिना व्यावसायिक आय के 400,000 डॉलर की शुद्ध व्यावसायिक हानि देखे, तो 2026 में 256,000 डॉलर काटेगा और 400,000 － 256,000 ＝ 144,000 डॉलर NOL के रूप में आगे ले जाएगा; वही हानि 2025 में केवल 400,000 － 313,000 ＝ 87,000 डॉलर अतिरिक्त देती — 57,000 डॉलर का अंतर ठीक सीमा की गिरावट के बराबर है (313,000 － 256,000 ＝ 57,000; संयुक्त: 626,000 － 512,000 ＝ 114,000)। California को अलग और सावधानी से संभालना होगा: अपने IRC अनुरूपता-तिथि ढाँचे के तहत California संघीय § 461(l) गणना को यथावत आयात नहीं करता, और राज्य की हानि व NOL व्यवस्था अपने फ़ॉर्मों और नियमों से चलती है, इसलिए संघीय Form 461 का परिणाम राज्य रिटर्न पर नकल करने के बजाय FTB के चालू मार्गदर्शन का पालन करें। *व्यक्तिगत अध्ययन नोट; कर सलाह नहीं। (प्रारंभिक अनुवाद, समीक्षा लंबित)*
