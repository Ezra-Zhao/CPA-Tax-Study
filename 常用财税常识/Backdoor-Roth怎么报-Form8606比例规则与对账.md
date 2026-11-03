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
