# 生意亏太多为什么当年扣不完：第 461(l) 条超额经营亏损门槛、算例与 NOL 结转及加州口径

> 个人学习笔记，不构成税务建议。门槛金额以 IRS 年度通胀调整公告为准（2025 年见 Rev. Proc. 2024-40）；个案请咨询持牌税务专业人士。

## 中文主文

### 一、常见困惑：账上真亏了，为什么税表上不让全扣

自雇、独资、合伙份额或 S 公司份额一年亏得很多的人，常遇到一件事：生意是真亏，银行流水、发票都在，可当年申报时有一截亏损被税表「存起来」了，不许抵当年的工资、利息或其他收入。这截被存起来的，通常就是第 461(l) 条的超额经营亏损。它针对的是非公司纳税人：经营亏损当年能扣的部分，以「经营收入合计加一个门槛」为天花板，超出的部分当年扣不了，但也不消失，转成下一年的净经营亏损（NOL）结转，以后再慢慢抵。

### 二、先算一笔完整的账（2025 年，单身）

设某人 2025 年只有一门生意：经营扣除合计 800,000 美元，经营收入合计 400,000 美元，账面净亏 400,000 美元。第一步，2025 年单身门槛为 313,000 美元（联合申报 626,000 美元）。第二步，当年可扣上限等于经营收入 400,000 加门槛 313,000，等于 713,000 美元。第三步，超额等于扣除 800,000 减 713,000，等于 87,000 美元。结论：400,000 美元净亏里，313,000 美元当年照常扣（把其他收入往下抵），87,000 美元当年扣零、转成 2026 年的 NOL 结转。本地复算：800,000 减 713,000 等于 87,000；400,000 减 313,000 等于 87,000，两路一致。

### 三、结转出去的 87,000 美元以后怎么用

转成 NOL 后，按第 172 条的 NOL 规矩走：一般不能往回抵以前年度（无回溯结转），只能往后抵；每年最多抵当年应税所得的 80%，剩下的继续往后结转，没有年限上限。所以它更像一张「以后有利润时慢慢兑」的券，而不是作废。实务提醒三件：其一，每年申报都要把 NOL 结转余额接上，换报税软件或换会计师时最容易断链；其二，Form 461 是算超额的表，NOL 的使用另有其申报位置，两张账要对得上；其三，若亏损来自合伙或 S 公司，先在实体层与个人层过各自的基数、风险（第 465 条）与被动（第 469 条）限制，最后才轮到第 461(l) 条在个人层比门槛——顺序错了，数字全错。

### 四、哪些情形最容易撞上这道闸

一是创业或扩张年：大额折旧、一次性开办投入把账面亏损推得很高，而收入还没跟上。二是夫妻一方高薪、一方创业亏损：本想用亏损全额抵工资，门槛之外要先结转（联合申报门槛是单身的两倍，626,000 美元对 313,000 美元，算婚前婚后税负时这是变量之一，但只按税务数字、不构成婚姻建议）。三是同一年多门生意：汇总口径是全部经营活动合并算，一门赚一门亏先在汇总里互抵，再比门槛，不要逐门各比一次。

### 五、加州口径（单独注明）

加州没有第 461(l) 条的对应限制，加州个人所得税走自己的 NOL 规则（《收入与税法典》第 17276 条一带），结转年限与抵减方式与联邦不同。结果是：联邦被挡下转结转的 87,000 美元，在加州当年可能可以扣（仍要过加州自己的规则），两边的结转余额从此分叉。做账时把联邦与加州的亏损结转各记一本台账，报税时分别取数；拿联邦 Form 461 的数字直接填加州表，是这类申报最常见的错法之一。

## English

A common surprise for sole proprietors and for partners and S corporation shareholders: the business really lost money, yet part of the loss is "banked" on the return instead of offsetting wages and other income that year. The usual reason is § 461(l). For noncorporate taxpayers, deductible business loss for the year is capped at aggregate business income plus a threshold — $313,000 for a single filer in 2025, $626,000 on a joint return (Rev. Proc. 2024-40). Worked example, single filer, 2025: business deductions of $800,000 and business income of $400,000 give a book loss of $400,000. The deductible ceiling is $400,000 plus $313,000, or $713,000; the excess is $800,000 minus $713,000, which equals $87,000 (cross-check: $400,000 minus $313,000 also equals $87,000). So $313,000 of the loss is deductible in 2025 and $87,000 is disallowed for the year. The disallowed part becomes a net operating loss carryforward under § 172: no carryback, usable against up to 80 percent of taxable income in later years, with no expiration. Form 461 computes the excess. Ordering matters: basis, at-risk (§ 465), and passive activity (§ 469) limits apply before § 461(l) compares the remaining loss with the threshold, and all trades or businesses are aggregated before the comparison. California has no § 461(l) counterpart and applies its own NOL rules (Revenue and Taxation Code § 17276 et seq.), so the federal and California carryforward balances diverge and must be tracked in separate ledgers.

## Español (traducción de estudio)

Una sorpresa frecuente para empresarios individuales, socios y accionistas de sociedades S: el negocio perdió dinero de verdad, pero una parte de la pérdida queda «guardada» en la declaración en vez de compensar salarios y otros ingresos ese año. La causa habitual es la § 461(l). Para contribuyentes no corporativos, la pérdida empresarial deducible del año tiene un techo: ingresos empresariales agregados más un umbral —313.000 dólares para solteros en 2025 y 626.000 en declaración conjunta (Rev. Proc. 2024-40)—. Ejemplo completo, soltero, 2025: deducciones empresariales de 800.000 dólares e ingresos de 400.000 dan una pérdida contable de 400.000. El techo deducible es 400.000 más 313.000, es decir, 713.000; el excedente es 800.000 menos 713.000, igual a 87.000 dólares (verificación cruzada: 400.000 menos 313.000 también da 87.000). Así, 313.000 se deducen en 2025 y 87.000 quedan diferidos. La parte diferida se convierte en arrastre de pérdida neta de operación (NOL) bajo la § 172: sin retroarrastre, utilizable hasta el 80 por ciento de la renta imponible de años futuros y sin vencimiento. El Formulario 461 calcula el excedente. El orden importa: los límites de base, de riesgo (§ 465) y de actividad pasiva (§ 469) se aplican antes de que la § 461(l) compare la pérdida restante con el umbral, y todas las actividades empresariales se agregan antes de comparar. California no tiene equivalente de la § 461(l) y aplica sus propias reglas de NOL (Revenue and Taxation Code § 17276 y siguientes), por lo que los saldos federales y estatales se bifurcan y deben llevarse en libros separados.

## 한국어 (초역, 교정 대기)

개인사업자, 파트너십 지분자, S법인 주주가 자주 겪는 일이다. 사업이 실제로 적자를 냈는데도 손실의 일부가 그해 임금 등 다른 소득과 상계되지 못하고 신고서에 「보관」된다. 보통 그 원인이 §461(l)이다. 비법인 납세자의 그해 사업 손실 공제 상한은 사업 소득 합계에 문턱을 더한 금액이다. 2025년 문턱은 독신 313,000달러, 부부 합산 626,000달러이다(Rev. Proc. 2024-40). 완전한 예시(2025년, 독신): 사업 공제 합계 800,000달러, 사업 소득 합계 400,000달러이면 장부상 순손실은 400,000달러이다. 공제 상한은 400,000 더하기 313,000으로 713,000달러이고, 초과분은 800,000 빼기 713,000으로 87,000달러이다(교차 확인: 400,000 빼기 313,000도 87,000). 따라서 313,000달러는 2025년에 공제되고 87,000달러는 그해 공제가 막힌다. 막힌 부분은 §172의 순영업손실(NOL) 이월이 되어 소급 이월 없이, 이후 연도 과세소득의 최대 80퍼센트까지, 만기 없이 사용할 수 있다. 초과분 계산은 Form 461로 한다. 순서가 중요하다. 지분 기준, §465 위험 부담, §469 수동 활동 제한이 먼저 적용되고, 그 뒤에 남은 손실을 §461(l) 문턱과 비교하며, 모든 사업 활동은 합산한 뒤 비교한다. 캘리포니아에는 §461(l)에 대응하는 규정이 없고 Revenue and Taxation Code §17276 이하의 자체 NOL 규칙을 적용하므로 연방과 주의 이월 잔액은 갈라지며 별도 장부로 관리해야 한다.

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

Một bất ngờ thường gặp với chủ hộ kinh doanh cá thể, thành viên hợp danh và cổ đông công ty S: doanh nghiệp thật sự lỗ, nhưng một phần khoản lỗ bị «gửi lại» trên tờ khai thay vì bù trừ với tiền lương và thu nhập khác trong năm. Nguyên nhân thường là §461(l). Với người nộp thuế không phải công ty, lỗ kinh doanh được khấu trừ trong năm bị giới hạn ở tổng thu nhập kinh doanh cộng một ngưỡng — 313.000 đô la cho người độc thân năm 2025, 626.000 đô la khai chung (Rev. Proc. 2024-40). Ví dụ đầy đủ, độc thân, 2025: khấu trừ kinh doanh 800.000 đô la và thu nhập kinh doanh 400.000 đô la cho khoản lỗ sổ sách 400.000 đô la. Trần khấu trừ là 400.000 cộng 313.000 bằng 713.000; phần vượt là 800.000 trừ 713.000 bằng 87.000 đô la (kiểm tra chéo: 400.000 trừ 313.000 cũng bằng 87.000). Như vậy 313.000 đô la được khấu trừ năm 2025 và 87.000 đô la bị hoãn. Phần bị hoãn trở thành lỗ hoạt động ròng (NOL) chuyển tiếp theo §172: không chuyển ngược, dùng tối đa 80 phần trăm thu nhập chịu thuế các năm sau, không hết hạn. Mẫu 461 dùng để tính phần vượt. Thứ tự rất quan trọng: các giới hạn về vốn góp, rủi ro (§465) và hoạt động bị động (§469) áp dụng trước, rồi §461(l) mới so phần lỗ còn lại với ngưỡng, và mọi hoạt động kinh doanh được cộng gộp trước khi so. California không có quy định tương đương §461(l) mà áp dụng quy tắc NOL riêng (Revenue and Taxation Code §17276 trở đi), nên số dư chuyển tiếp liên bang và của bang tách ra và phải theo dõi bằng sổ riêng.

## हिन्दी (प्रारंभिक अनुवाद, समीक्षा लंबित)

एकल स्वामियों, साझेदारों और S corporation शेयरधारकों के लिए एक आम आश्चर्य: व्यवसाय ने सचमुच घाटा किया, फिर भी घाटे का एक हिस्सा उस वर्ष वेतन और अन्य आय से समायोजित होने के बजाय रिटर्न पर «रुक» जाता है। इसका सामान्य कारण §461(l) है। गैर-कॉर्पोरेट करदाताओं के लिए वर्ष की कटौतीयोग्य व्यावसायिक हानि की सीमा कुल व्यावसायिक आय और एक सीमा का योग है — 2025 में एकल दाखिलकर्ता के लिए 313,000 डॉलर, संयुक्त रिटर्न पर 626,000 डॉलर (Rev. Proc. 2024-40)। पूरा उदाहरण, एकल, 2025: व्यावसायिक कटौतियाँ 800,000 डॉलर और व्यावसायिक आय 400,000 डॉलर होने पर बही-घाटा 400,000 डॉलर है। कटौती की छत 400,000 जमा 313,000 अर्थात 713,000 है; अतिरिक्त राशि 800,000 ऋण 713,000 अर्थात 87,000 डॉलर है (पार-जाँच: 400,000 ऋण 313,000 भी 87,000 है)। अतः 313,000 डॉलर 2025 में कटते हैं और 87,000 डॉलर उस वर्ष रुक जाते हैं। रुका हुआ भाग §172 के तहत शुद्ध परिचालन घाटा (NOL) कैरीफ़ॉरवर्ड बन जाता है: कोई कैरीबैक नहीं, बाद के वर्षों की करयोग्य आय के 80 प्रतिशत तक उपयोग, कोई समाप्ति नहीं। Form 461 अतिरिक्त राशि की गणना करता है। क्रम महत्वपूर्ण है: आधार, at-risk (§465) और निष्क्रिय गतिविधि (§469) सीमाएँ पहले लागू होती हैं, फिर §461(l) शेष घाटे की सीमा से तुलना करता है, और सभी व्यापारों को तुलना से पहले जोड़ा जाता है। California में §461(l) का कोई समकक्ष नहीं है; वह अपने NOL नियम (Revenue and Taxation Code §17276 आदि) लागू करता है, इसलिए संघीय और राज्य कैरीफ़ॉरवर्ड शेष अलग हो जाते हैं और अलग बही-खातों में रखने चाहिए।

---

*声明：本文为个人学习笔记，不构成法律、税务或医疗建议。*
