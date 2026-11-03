# Backdoor Roth IRA 怎么报：Form 8606、比例规则与三张表对账

> 个人学习笔记，不构成税务建议。数字以 IRS 现行表格与说明为准，操作前请核对当年 Form 8606 Instructions。

## 中文主文

### 一、它到底是什么
Backdoor Roth 不是税法里的正式名称，而是两步的组合：先向 Traditional IRA 存入不可扣减供款（nondeductible contribution），再把这笔钱转入（convert）Roth IRA。收入超过 Roth 直接供款限额的人常用此路；直接供款的收入限额每年由 IRS 公布（见当年 Publication 590-A），本篇不写死某年数字、只讲机制与报表。

### 二、为什么 Form 8606 是核心
- **供款当年**：不可扣减供款必须报在 Form 8606 Part I，它把这笔钱登记为 Traditional IRA 的“基数（basis）”。
- **转换当年**：Form 8606 Part II 计算转换中应税的部分。基数登记过，转换时原则上只有转换前的收益部分应税；没登记基数，IRS 会把整笔转换当应税收入处理，等于同一笔钱被税两次。
- **每年供款都要留档**：8606 是累计档案，最后一次提款前都要保存；供款年份与转换年份可以不同年，两步各报各的。

### 三、比例规则（pro-rata rule）——最常见的坑
转换应税比例不是只看“刚存进去的那只账户”，而是看你名下**全部** Traditional、SEP、SIMPLE IRA 在当年 12 月 31 日的合计余额（Form 8606 的计算口径，另加当年转出与转换金额）：
- 应税比例 ≈（年末合计余额 + 当年转换额 − 基数）÷（年末合计余额 + 当年转换额），直观说：基数占全部税前加基数总额的比例决定免税部分。
- 算例：12 月 31 日你另有一只 rollover IRA 有税前资金 93,000 美元，当年存入不可扣减 7,000 美元并全额转换，年末 Traditional IRA 合计余额为 93,000 美元，基数 7,000 美元。转换总额口径为 93,000 + 7,000 = 100,000 美元，免税部分 = 7,000 × 7,000 ÷ 100,000 = 490 美元，应税部分 = 7,000 − 490 = 6,510 美元。也就是说大部分转换要交税，并非“后门全免”。
- 常见处置（只讲机制、不荐操作）：在转换前把税前 IRA 资金转入现雇主 401(k)（计划须接受 roll-in），使 12 月 31 日 IRA 余额归零，比例规则就无从稀释；雇主计划是否接受、时点是否赶在年底前，须逐项核实。

### 四、三张表怎么对账
1. **Form 5498**：托管机构次年寄来，记录供款与年末市值——核对供款年份与金额。
2. **Form 1099-R**：转换次年寄来，记录转出总额；代码常见 2 或 7，不等于应税额，应税额以 8606 计算为准。
3. **Form 8606**：你自己的申报——Part I 登记基数、Part II 算转换应税额、Part III 管 Roth 提款。

三者对不上时先查：供款报的年份是否与 5498 一致、转换是否跨年、年末是否还有其他 IRA 余额漏算。

### 五、加州注记
加州在 Form 540 上对 IRA 转换的州税处理大体跟随联邦应税口径，但加州历史上对 IRA 供款的扣除规则与联邦曾有差异、老账户可能有加州基数差额；有早年供款史的，先查 FTB Publication 1005 再报，不要直接把联邦基数抄到州表。

*声明：个人学习笔记，不构成税务建议。具体操作请咨询 CPA 或查 IRS Publication 590-A/590-B 与当年 Form 8606 说明。*

---

## English

A "backdoor Roth" is two steps: a nondeductible contribution to a traditional IRA, then a conversion to a Roth IRA. Form 8606 is the record: Part I registers the contribution as basis; Part II computes the taxable part of the conversion. The pro-rata rule looks at all your traditional, SEP and SIMPLE IRAs at December 31. Example: with $93,000 of pre-tax IRA money, a $7,000 nondeductible contribution fully converted is only $490 tax-free ($7,000 × $7,000 ÷ $100,000); $6,510 is taxable. Reconcile Forms 5498, 1099-R and 8606; a common fix before converting is rolling pre-tax IRA money into a current employer's 401(k) that accepts roll-ins, so the December 31 IRA balance drops to zero and the pro-rata rule has nothing to dilute. California filers with older contributions should check FTB Publication 1005 for a possible state basis difference. *Personal study notes only; not tax advice.*

## Español (traducción de estudio, pendiente de revisión nativa)

El «backdoor Roth» combina una aportación no deducible a una IRA tradicional y una conversión a Roth. El Formulario 8606 registra la base (Parte I) y calcula la parte imponible de la conversión (Parte II). La regla prorrateada (pro-rata) considera todas las IRA tradicionales, SEP y SIMPLE al 31 de diciembre: con 93.000 dólares antes de impuestos y una aportación de 7.000, solo 490 quedan exentos y 6.510 tributan. Concilie tres documentos: el Formulario 5498 (aportaciones y valor al cierre), el 1099-R (salida total; su código no fija el importe imponible) y el propio 8606. Una salida habitual antes de convertir es trasladar el dinero IRA antes de impuestos al 401(k) del empleador actual, si el plan acepta roll-ins, para dejar el saldo IRA a cero el 31 de diciembre. En California, quien tenga aportaciones antiguas debe revisar la Publication 1005 de la FTB por posibles diferencias de base estatal. *Notas personales de estudio; no constituye asesoría fiscal.*

## 한국어 (초역, 원어민 감수 대기)

Backdoor Roth는 Traditional IRA에 비공제 납입 후 Roth IRA로 전환하는 두 단계입니다. Form 8606 Part I에 basis를 등록해야 이중과세를 피할 수 있고, Part II에서 전환 과세분을 계산합니다. 비례 규칙(pro-rata)은 12월 31일 기준 모든 Traditional·SEP·SIMPLE IRA를 합산합니다. 세전 자금 93,000달러가 있으면 7,000달러 전환 중 490달러만 비과세, 6,510달러는 과세됩니다. 대조할 서류는 셋입니다. Form 5498(납입과 연말 평가액), Form 1099-R(출금 총액이며 코드가 과세액을 정하지 않음), 그리고 본인의 8606입니다. 전환 전 흔한 정리는 세전 IRA 자금을 현 고용주의 401(k)(roll-in 허용 시)로 옮겨 12월 31일 IRA 잔액을 0으로 만드는 것입니다. 캘리포니아에서는 오래된 납입 이력이 있으면 주 베이스 차이가 있을 수 있어 FTB Publication 1005를 확인해야 합니다. *개인 학습 노트이며 세무 자문이 아닙니다.*

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

Backdoor Roth gồm hai bước: đóng góp không được khấu trừ vào IRA truyền thống, rồi chuyển đổi sang Roth IRA. Form 8606 ghi lại cơ sở (basis) ở Phần I và tính phần chuyển đổi phải chịu thuế ở Phần II. Quy tắc pro-rata xét toàn bộ IRA truyền thống, SEP và SIMPLE tại ngày 31/12: có 93.000 đô la tiền trước thuế thì trong 7.000 đô la chuyển đổi chỉ 490 đô la được miễn thuế, 6.510 đô la phải chịu thuế. Đối chiếu ba chứng từ: Form 5498 (đóng góp và giá trị cuối năm), Form 1099-R (tổng số tiền rút; mã trên mẫu không quyết định số phải chịu thuế) và chính Form 8606. Cách xử lý thường gặp trước khi chuyển đổi là chuyển tiền IRA trước thuế vào 401(k) của chủ lao động hiện tại, nếu chương trình chấp nhận roll-in, để số dư IRA về 0 vào ngày 31/12. Ở California, người có lịch sử đóng góp cũ nên kiểm tra FTB Publication 1005 vì có thể có chênh lệch cơ sở (basis) ở cấp bang. *Ghi chú học tập cá nhân, không phải tư vấn thuế.*

## हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

Backdoor Roth दो चरण है: Traditional IRA में nondeductible योगदान, फिर Roth IRA में conversion। Form 8606 Part I में basis दर्ज होता है और Part II में conversion का करयोग्य भाग निकलता है। Pro-rata नियम 31 दिसंबर को सभी Traditional, SEP और SIMPLE IRA को जोड़ता है: $93,000 pre-tax राशि होने पर $7,000 conversion में केवल $490 कर-मुक्त, $6,510 करयोग्य होगा। तीन दस्तावेज़ों का मिलान करें: Form 5498 (योगदान व वर्षांत मूल्य), Form 1099-R (कुल निकासी; इसका कोड करयोग्य राशि तय नहीं करता) और स्वयं Form 8606। Conversion से पहले एक आम उपाय है pre-tax IRA राशि को वर्तमान नियोक्ता के 401(k) में (यदि plan roll-in स्वीकार करे) डालकर 31 दिसंबर को IRA शेष शून्य करना। California में पुराने योगदानों वालों को राज्य-basis अंतर की संभावना हेतु FTB Publication 1005 देखना चाहिए। *व्यक्तिगत अध्ययन नोट; कर सलाह नहीं।*

---

## 补译增量（2026-11-03 追加：韩／越／印三语按中文主文逐节补齐，正文原有段落未改动）

### 한국어 전문 보충 (초역, 初译待校)

**1. 그것이 정확히 무엇인가.** Backdoor Roth는 세법에 있는 정식 명칭이 아니라 두 단계의 조합이다. 먼저 Traditional IRA에 비공제 납입(nondeductible contribution)을 하고, 그 돈을 Roth IRA로 전환(convert)한다. 소득이 Roth 직접 납입 한도를 넘는 사람이 주로 쓰는 길이다. 직접 납입의 소득 한도는 매년 IRS가 공표하므로(Publication 590-A 참조), 이 글은 특정 연도 숫자를 박아 두지 않고 구조와 신고만 다룬다.

**2. 왜 Form 8606이 핵심인가.** 납입 연도에는 비공제 납입을 Form 8606 Part I에 신고해 그 돈을 Traditional IRA의 "기준가액(basis)"으로 등록한다. 전환 연도에는 Part II가 전환 중 과세 부분을 계산한다. basis가 등록되어 있으면 전환 시 원칙적으로 전환 전 발생한 수익 부분만 과세되고, 등록이 없으면 IRS가 전환 전액을 과세소득으로 취급해 같은 돈에 두 번 세금이 붙는다. 8606은 누적 기록이므로 마지막 인출 전까지 보관해야 하고, 납입 연도와 전환 연도는 다를 수 있으며 각 단계는 각자 신고한다.

**3. 비례 규칙(pro-rata rule) — 가장 흔한 함정.** 전환의 과세 비율은 "방금 넣은 그 계좌"만 보지 않는다. 본인 명의의 모든 Traditional·SEP·SIMPLE IRA의 그해 12월 31일 잔액 합계(Form 8606 계산 기준, 그해 인출·전환액 가산)를 본다. 예시: 별도의 rollover IRA에 세전 자금 93,000달러가 있고, 그해 비공제 7,000달러를 납입해 전액 전환했으며, 연말 Traditional IRA 합계 잔액이 93,000달러, basis가 7,000달러라면, 전환 총액 기준은 93,000 + 7,000 = 100,000달러, 비과세 부분 = 7,000 × 7,000 ÷ 100,000 = 490달러, 과세 부분 = 7,000 − 490 = 6,510달러다. 즉 대부분이 과세되며 "백도어 전액 면세"가 아니다. 흔한 정리법(구조만 설명): 전환 전에 세전 IRA 자금을 현 고용주의 401(k)(roll-in 허용 플랜)로 옮겨 12월 31일 IRA 잔액을 0으로 만들면 비례 규칙이 희석할 대상이 사라진다. 고용주 플랜의 수용 여부와 연말 전 시점은 건건이 확인해야 한다.

**4. 세 가지 서류의 대조.** Form 5498은 수탁기관이 이듬해 보내며 납입과 연말 평가액을 기록한다 — 납입 연도와 금액을 대조한다. Form 1099-R은 전환 이듬해 도착해 인출 총액을 기록한다. 코드 2나 7이 흔하지만 그것이 과세액을 정하지는 않으며, 과세액은 8606 계산이 기준이다. Form 8606은 본인의 신고로, Part I이 basis 등록, Part II가 전환 과세액, Part III가 Roth 인출을 담당한다. 셋이 어긋나면 납입 연도와 5498의 일치 여부, 전환의 연도 걸침, 연말 다른 IRA 잔액 누락부터 확인한다.

**5. 캘리포니아 주석.** 캘리포니아는 Form 540에서 IRA 전환의 주세 처리가 대체로 연방 과세 기준을 따르지만, 과거 IRA 납입 공제 규칙이 연방과 달랐던 시기가 있어 오래된 계좌에는 캘리포니아 basis 차이가 있을 수 있다. 이른 시기 납입 이력이 있으면 연방 basis를 주 신고서에 그대로 옮기지 말고 FTB Publication 1005를 먼저 확인한다.

### Bổ sung đầy đủ Tiếng Việt (bản dịch sơ bộ, 初译待校)

**1. Nó thực chất là gì.** Backdoor Roth không phải tên chính thức trong luật thuế mà là tổ hợp hai bước: trước hết đóng góp không được khấu trừ (nondeductible contribution) vào Traditional IRA, rồi chuyển đổi (convert) số tiền đó sang Roth IRA. Người có thu nhập vượt hạn mức góp trực tiếp vào Roth thường dùng đường này; hạn mức thu nhập để góp trực tiếp do IRS công bố hằng năm (xem Publication 590-A), nên bài này không cố định con số của một năm nào, chỉ nói cơ chế và tờ khai.

**2. Vì sao Form 8606 là cốt lõi.** Năm đóng góp: khoản góp không khấu trừ phải khai ở Form 8606 Phần I, ghi nó thành "cơ sở (basis)" của Traditional IRA. Năm chuyển đổi: Phần II tính phần chịu thuế của việc chuyển đổi. Đã ghi basis thì khi chuyển đổi, về nguyên tắc chỉ phần lãi phát sinh trước chuyển đổi mới chịu thuế; không ghi basis, IRS sẽ coi toàn bộ khoản chuyển đổi là thu nhập chịu thuế, tức cùng một số tiền bị đánh thuế hai lần. Form 8606 là hồ sơ lũy kế, phải giữ cho tới lần rút cuối cùng; năm đóng góp và năm chuyển đổi có thể khác nhau, mỗi bước khai riêng.

**3. Quy tắc pro-rata — cái bẫy phổ biến nhất.** Tỉ lệ chịu thuế của khoản chuyển đổi không chỉ nhìn vào "tài khoản vừa nạp", mà nhìn tổng số dư ngày 31/12 của toàn bộ Traditional, SEP và SIMPLE IRA mang tên bạn (theo cách tính của Form 8606, cộng thêm số đã rút và chuyển đổi trong năm). Ví dụ: bạn có một rollover IRA chứa 93.000 đô la tiền trước thuế; trong năm góp 7.000 đô la không khấu trừ và chuyển đổi toàn bộ; số dư tổng IRA truyền thống cuối năm là 93.000 đô la, basis là 7.000 đô la. Tổng cơ sở tính chuyển đổi là 93.000 + 7.000 = 100.000 đô la; phần miễn thuế = 7.000 × 7.000 ÷ 100.000 = 490 đô la; phần chịu thuế = 7.000 − 490 = 6.510 đô la. Nghĩa là phần lớn khoản chuyển đổi phải chịu thuế, chứ không phải "backdoor là miễn hết". Cách xử lý thường gặp (chỉ nói cơ chế): trước khi chuyển đổi, chuyển tiền IRA trước thuế vào 401(k) của chủ lao động hiện tại (nếu chương trình chấp nhận roll-in) để số dư IRA về 0 vào ngày 31/12, khi đó quy tắc pro-rata không còn gì để pha loãng; việc chương trình có chấp nhận hay không và thời điểm có kịp cuối năm hay không phải kiểm tra từng trường hợp.

**4. Đối chiếu ba chứng từ.** Form 5498 do tổ chức lưu ký gửi vào năm sau, ghi đóng góp và giá trị cuối năm — đối chiếu năm và số tiền đóng góp. Form 1099-R đến vào năm sau chuyển đổi, ghi tổng số tiền rút; mã thường là 2 hoặc 7 nhưng không quyết định số chịu thuế — số chịu thuế tính theo Form 8606. Form 8606 là tờ khai của chính bạn: Phần I ghi basis, Phần II tính phần chuyển đổi chịu thuế, Phần III quản rút tiền Roth. Khi ba chứng từ không khớp, kiểm tra trước: năm đóng góp có khớp 5498 không, chuyển đổi có vắt qua hai năm không, cuối năm có sót số dư IRA nào khác không.

**5. Ghi chú California.** Trên Form 540, California nhìn chung theo cách xử lý chịu thuế của liên bang đối với chuyển đổi IRA, nhưng ngày xưa quy tắc khấu trừ đóng góp IRA của California từng khác liên bang, nên tài khoản cũ có thể có chênh lệch basis ở cấp bang. Ai có lịch sử đóng góp sớm nên tra FTB Publication 1005 trước khi khai, đừng chép nguyên basis liên bang sang tờ khai bang.

### हिन्दी पूर्ण पूरक (प्रारंभिक अनुवाद, 初译待校)

**1. यह आख़िर है क्या।** Backdoor Roth कर-विधि का औपचारिक नाम नहीं, दो चरणों का संयोजन है: पहले Traditional IRA में nondeductible योगदान, फिर उसी राशि का Roth IRA में conversion। जिनकी आय Roth प्रत्यक्ष योगदान सीमा से ऊपर है वे अक्सर यही रास्ता लेते हैं; प्रत्यक्ष योगदान की आय-सीमा IRS हर वर्ष घोषित करता है (Publication 590-A देखें), इसलिए यह लेख किसी वर्ष का आँकड़ा स्थिर नहीं करता, केवल तंत्र और रिपोर्टिंग बताता है।

**2. Form 8606 क्यों केंद्र में है।** योगदान वाले वर्ष में nondeductible योगदान Form 8606 Part I में दर्ज करके उस राशि को Traditional IRA का "basis" बना दिया जाता है। Conversion वाले वर्ष में Part II conversion का करयोग्य भाग निकालता है। Basis दर्ज हो तो conversion पर सिद्धांततः केवल conversion-पूर्व की कमाई करयोग्य होती है; दर्ज न हो तो IRS पूरे conversion को करयोग्य आय मानेगा — एक ही राशि पर दो बार कर। 8606 संचयी अभिलेख है, अंतिम निकासी तक रखना होता है; योगदान-वर्ष और conversion-वर्ष अलग हो सकते हैं, हर चरण अलग दर्ज होता है।

**3. Pro-rata नियम — सबसे आम जाल।** Conversion का करयोग्य अनुपात केवल "अभी डाले गए खाते" से नहीं निकलता; आपके नाम के सभी Traditional, SEP और SIMPLE IRA के उस वर्ष 31 दिसंबर के कुल शेष (Form 8606 की गणना, उस वर्ष की निकासी व conversion जोड़कर) से निकलता है। उदाहरण: अलग rollover IRA में $93,000 pre-tax राशि है; उसी वर्ष $7,000 nondeductible योगदान करके पूरा convert किया; वर्षांत Traditional IRA कुल शेष $93,000, basis $7,000। Conversion की कुल गणना-राशि 93,000 + 7,000 = $100,000; कर-मुक्त भाग = 7,000 × 7,000 ÷ 100,000 = $490; करयोग्य भाग = 7,000 − 490 = $6,510। अर्थात अधिकांश conversion करयोग्य होगा, "backdoor पूरी तरह कर-मुक्त" नहीं। एक आम उपाय (केवल तंत्र): conversion से पहले pre-tax IRA राशि वर्तमान नियोक्ता के 401(k) में (यदि plan roll-in स्वीकार करे) डालकर 31 दिसंबर को IRA शेष शून्य कर दें, तो pro-rata नियम को घोलने के लिए कुछ बचेगा ही नहीं; plan स्वीकार करता है या नहीं और समय वर्षांत से पहले होगा या नहीं, मामला-दर-मामला जांचें।

**4. तीन दस्तावेज़ों का मिलान।** Form 5498 संरक्षक अगले वर्ष भेजता है — योगदान और वर्षांत मूल्य दर्ज होते हैं; योगदान-वर्ष और राशि जांचें। Form 1099-R conversion के अगले वर्ष आता है — कुल निकासी दर्ज होती है; कोड सामान्यतः 2 या 7 होता है, परंतु करयोग्य राशि वह तय नहीं करता, वह 8606 की गणना से तय होती है। Form 8606 आपकी अपनी रिपोर्ट है — Part I basis दर्ज करता है, Part II conversion का करयोग्य भाग, Part III Roth निकासी संभालता है। तीनों न मिलें तो पहले जांचें: योगदान का वर्ष 5498 से मेल खाता है क्या, conversion वर्ष पार तो नहीं गया, वर्षांत कोई अन्य IRA शेष छूटा तो नहीं।

**5. California टिप्पणी।** California Form 540 पर IRA conversion का राज्य-कर व्यवहार मोटे तौर पर संघीय करयोग्य पद्धति का अनुसरण करता है, किंतु अतीत में IRA योगदान कटौती के राज्य नियम संघ से भिन्न रहे हैं, इसलिए पुराने खातों में California basis का अंतर हो सकता है। प्रारंभिक वर्षों के योगदान वालों को संघीय basis राज्य प्रपत्र पर सीधे नक़ल करने से पहले FTB Publication 1005 जांचना चाहिए।
