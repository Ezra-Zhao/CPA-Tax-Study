# 股权激励怎么计税：ISO、NSO、RSU 与 ESPP 的四条线

## 中文

股权激励报税最容易错的一步，是把「拿到股票」和「拿到钱」当成同一件事。联邦税法的主轴只有一条：IRC § 83——因提供服务而取得的财产，在可自由转让或不再有重大没收风险（即归属 vesting）时，按当时市价减去已付金额计入普通收入。下面四种工具都是这条主轴的变体。

### 一、NSO（非法定股票期权）：最直白的一条

- 授予和归属时一般不征税；**行权时**价差（行权日市价减行权价）计入普通收入，走工资单、扣 FICA 和预扣税。雇主在同一时点按 § 83(h) 扣除同额。
- 算例：1,000 股、行权价 10 美元、行权日市价 30 美元，价差 20 美元 × 1,000 = 20,000 美元普通收入；之后卖出时基数是 30 美元/股，再涨的部分才是资本利得，持有期从行权次日起算。

### 二、ISO（激励性股票期权）：两套账

- 满足 § 422 条件（股东批准的计划、行权价不低于授予日市价、每年首次可行权部分按授予日价值不超过 100,000 美元、离职后 3 个月内行权等）且满足持有期（授予后 2 年、行权后 1 年都不卖）时，行权不计普通收入、最终卖出全部按长期资本利得——这是合格处置（qualifying disposition）。
- 代价在替代最低税（AMT）：行权价差是 § 56(b)(3) 的 AMT 调整项，行权当年可能要交 AMT（之后可形成最低税抵免）。提前卖出即 disqualifying disposition，价差中较小一段转普通收入。
- 雇主在合格处置下没有扣除；这点常被忽略。

### 三、RSU（限制性股票单位）：没有 83(b) 可选

- RSU 在归属前只是承诺、不是已转移的财产，所以 **不能做 § 83(b) 选举**；归属（通常同时结算）时按市价全额计普通收入、扣工资税，公司常用扣股缴税（sell-to-cover / share withholding）。
- 对比：受限股票（restricted stock，股票已实际发行）可以做 § 83(b)——必须在转移后 **30 天内**向 IRS 提交（Reg. § 1.83-2），逾期基本无补救；选了就在授予日按低市价计税、之后全走资本利得，但若最终被没收，已缴的税拿不回来。

### 四、ESPP（员工购股计划）：折扣里的两段

- 符合 § 423 的计划折扣最高 15%，且通常有回望（lookback）定价。合格处置（购买后 2 年、取得后 1 年，两个期间以发行/授予日口径为准）时，普通收入只认折扣中较小的一段，其余走长期资本利得；提前卖出则折扣全额转普通收入。

### 五、两个别漏的点

- 递延安排要过 § 409A：RSU 若把结算推到归属之后，要么落在短期递延例外内，要么按 409A 的书面计划与支付时点规则走，违规是提前计税加 20% 附加税和利息。
- 会计是另一套账：公司按 ASC 718 在归属期内确认股份支付费用，与税务扣除时点不同，别把财报费用当税务扣除。加州口径：股权收入按普通收入征州税、没有资本利得优惠税率，行权/归属时的人在加州还是外州，还会影响来源地分配。

> 个人学习笔记，不构成税务建议。数字与条文以 IRS 现行公告与 IRC 原文为准。

## English

The most common equity-compensation tax mistake is treating "receiving shares" and "receiving cash" as the same event. The federal axis is IRC § 83: property transferred for services is taxed as ordinary income when it becomes transferable or vests, measured by fair market value minus any amount paid. Four common instruments are variations on that rule.

**NSOs.** Nonqualified options are generally not taxed at grant or vesting. At exercise, the spread is ordinary wage income subject to FICA and withholding; the employer deducts the same amount under § 83(h). Example: 1,000 shares, $10 strike, $30 FMV at exercise produces $20,000 of ordinary income; the basis becomes $30 per share and later appreciation is capital gain, with the holding period starting the day after exercise.

**ISOs.** If the § 422 conditions are met (shareholder-approved plan, strike at or above grant-date FMV, the $100,000 annual first-exercisable limit, exercise within 3 months after leaving employment, among others) and the shares are held more than 2 years after grant and 1 year after exercise, there is no regular-tax income at exercise and the entire gain is long-term capital gain at sale — a qualifying disposition. The cost is the alternative minimum tax: the spread is an AMT adjustment under § 56(b)(3) in the exercise year, potentially creating a minimum tax credit later. An early sale is a disqualifying disposition and converts part of the gain to ordinary income. The employer gets no deduction on a qualifying disposition.

**RSUs and restricted stock.** An RSU is only a promise before vesting, not transferred property, so no § 83(b) election is available; at vesting the full FMV is ordinary wage income, often settled net of shares for withholding. Restricted stock, by contrast, is actual property and may be covered by a § 83(b) election, which must be filed with the IRS within 30 days of transfer (Reg. § 1.83-2) — miss the deadline and there is generally no cure. The election taxes the (usually lower) grant-date value as ordinary income and converts later growth to capital gain, but tax paid is not refunded if the shares are later forfeited.

**ESPPs.** A § 423 plan may offer up to a 15% discount, often with a lookback. On a qualifying disposition (more than 2 years after the offering/grant date and 1 year after purchase), only the smaller discount slice is ordinary income and the rest is long-term capital gain; an early sale makes the full discount ordinary.

**Two traps.** Deferred settlement must satisfy § 409A or fit the short-term deferral exception; violations trigger early inclusion plus a 20% additional tax and interest. And book accounting is separate: companies expense share-based pay under ASC 718 over the vesting period, which does not match the tax deduction timing. California taxes equity income as ordinary income with no preferential capital-gains rate, and work location at exercise/vesting affects sourcing.

> Personal study notes only; not tax advice.

## Español (traducción de estudio)

El error más común con la compensación en acciones es confundir «recibir acciones» con «recibir dinero». El eje federal es el IRC § 83: la propiedad recibida por servicios tributa como ingreso ordinario cuando se consolida (vesting), por su valor de mercado menos lo pagado.

**NSO.** Sin impuesto al conceder ni al consolidar; al ejercer, la diferencia entre valor de mercado y precio de ejercicio es salario ordinario con FICA y retención, y el empleador deduce lo mismo según § 83(h). Ejemplo: 1.000 acciones, ejercicio a 10 dólares y valor de 30 dólares generan 20.000 dólares de ingreso ordinario; la base pasa a 30 dólares por acción.

**ISO.** Cumplidas las condiciones del § 422 (plan aprobado, precio no inferior al valor de concesión, límite anual de 100.000 dólares, ejercicio dentro de los 3 meses tras dejar el empleo, entre otras) y los plazos de tenencia (2 años desde la concesión y 1 año desde el ejercicio), no hay impuesto ordinario al ejercer y toda la ganancia final es de capital a largo plazo. El costo es el AMT: la diferencia es un ajuste según § 56(b)(3). La venta anticipada es una disposición descalificante. El empleador no deduce nada en la disposición calificada.

**RSU y acciones restringidas.** La RSU antes del vesting es solo una promesa: no cabe elección § 83(b); al consolidar, todo el valor es salario ordinario. La acción restringida sí es propiedad transferida y admite § 83(b), que debe presentarse ante el IRS dentro de los 30 días (Reg. § 1.83-2), sin remedio si se pasa el plazo; si luego se pierde la acción, el impuesto pagado no se devuelve.

**ESPP.** Un plan § 423 permite hasta 15% de descuento. En la disposición calificada (2 años desde la oferta y 1 año desde la compra), solo la parte menor del descuento es ingreso ordinario; la venta anticipada convierte todo el descuento en ordinario.

**Dos trampas.** El pago diferido debe cumplir § 409A o la excepción de corto plazo; la infracción suma un 20% adicional e intereses. La contabilidad es otra vía: ASC 718 registra el gasto durante el vesting, sin coincidir con la deducción fiscal. California grava estos ingresos como ordinarios, sin tasa preferente para ganancias de capital.

> Notas personales de estudio; no constituyen asesoría fiscal.

## 한국어 (초역, 교정 대기)

주식 보상의 가장 흔한 세무 실수는 「주식을 받는 것」과 「현금을 받는 것」을 같게 보는 것입니다. 연방 기준축은 IRC § 83으로, 서비스를 대가로 받은 재산은 베스팅 시점에 시가에서 지급액을 뺀 금액이 근로소득이 됩니다.

**NSO.** 부여·베스팅 시에는 과세되지 않고, 행사 시 행사가와 시가의 차액이 FICA와 원천징수 대상 근로소득이 되며 고용주는 § 83(h)에 따라 같은 금액을 공제합니다. 예: 1,000주, 행사가 10달러, 행사일 시가 30달러이면 근로소득 20,000달러, 취득가액은 주당 30달러가 됩니다.

**ISO.** § 422 요건(주주 승인 계획, 부여일 시가 이상의 행사가, 연간 100,000달러 한도, 퇴직 후 3개월 내 행사 등)과 보유기간(부여 후 2년, 행사 후 1년)을満た하면 행사 시 일반 과세가 없고 최종 매각 이익 전체가 장기 자본이득이 됩니다. 대가는 AMT로, 행사 차액이 § 56(b)(3) 조정항목이 됩니다. 조기 매각은 부적격 처분으로 일부가 근로소득으로 바뀝니다. 적격 처분에서 고용주 공제는 없습니다.

**RSU와 제한주식.** RSU는 베스팅 전 약속일 뿐 재산이 이전된 것이 아니어서 § 83(b) 선택이 불가능하고, 베스팅 시 전액 근로소득입니다. 실제 주식이 발행된 제한주식은 § 83(b) 선택이 가능하지만 이전 후 30일 이내에 IRS에 제출해야 하며(Reg. § 1.83-2), 기한을 놓치면 구제가 거의 없습니다. 나중에 몰수되어도 낸 세금은 돌려받지 못합니다.

**ESPP.** § 423 플랜은 최대 15% 할인이 가능합니다. 적격 처분(제공일 후 2년, 매입 후 1년)이면 할인 중 작은 부분만 근로소득이고, 조기 매각이면 할인 전액이 근로소득입니다.

**주의점.** 이연 정산은 § 409A를 충족하거나 단기 이연 예외에 들어가야 하며 위반 시 20% 추가세와 이자가 붙습니다. 회계는 별도로 ASC 718에 따라 베스팅 기간에 비용을 인식합니다. 캘리포니아는 주식 소득을 일반 소득으로 과세하고 자본이득 우대세율이 없습니다.

> 개인 학습 노트이며 세무 자문이 아닙니다. (초역, 교정 대기)

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

Sai lầm thuế phổ biến nhất với thù lao bằng cổ phiếu là coi «nhận cổ phiếu» và «nhận tiền» là một. Trục liên bang là IRC § 83: tài sản nhận vì dịch vụ bị đánh thuế thu nhập thông thường khi vesting, theo giá thị trường trừ số đã trả.

**NSO.** Không bị thuế khi cấp hay vesting; khi thực hiện quyền, phần chênh lệch là thu nhập lương chịu FICA và khấu trừ, và người sử dụng lao động được khấu trừ cùng số theo § 83(h). Ví dụ: 1.000 cổ phiếu, giá thực hiện 10 đô, giá thị trường 30 đô tạo 20.000 đô thu nhập thông thường; giá vốn trở thành 30 đô mỗi cổ phiếu.

**ISO.** Nếu đáp ứng § 422 (kế hoạch được cổ đông phê duyệt, giá thực hiện không thấp hơn giá ngày cấp, giới hạn 100.000 đô mỗi năm, thực hiện trong 3 tháng sau khi nghỉ việc, v.v.) và thời gian nắm giữ (2 năm sau cấp, 1 năm sau thực hiện), khi thực hiện không có thuế thông thường và toàn bộ lãi khi bán là lãi vốn dài hạn. Đổi lại là AMT: phần chênh lệch là khoản điều chỉnh theo § 56(b)(3). Bán sớm là disposition không đủ điều kiện. Người sử dụng lao động không được khấu trừ trong disposition đủ điều kiện.

**RSU và cổ phiếu hạn chế.** RSU trước vesting chỉ là lời hứa nên không thể chọn § 83(b); khi vesting toàn bộ giá trị là thu nhập lương. Cổ phiếu hạn chế đã chuyển giao thật thì có thể chọn § 83(b), phải nộp cho IRS trong 30 ngày sau chuyển giao (Reg. § 1.83-2), quá hạn hầu như không cứu được; nếu sau đó bị thu hồi, thuế đã nộp không được hoàn.

**ESPP.** Kế hoạch § 423 được chiết khấu tối đa 15%. Disposition đủ điều kiện (2 năm sau ngày chào, 1 năm sau mua) thì chỉ phần chiết khấu nhỏ hơn là thu nhập thông thường; bán sớm khiến toàn bộ chiết khấu thành thu nhập thông thường.

**Hai lưu ý.** Thanh toán hoãn phải tuân § 409A hoặc ngoại lệ hoãn ngắn hạn; vi phạm thêm 20% thuế và lãi. Kế toán theo ASC 718 ghi chi phí trong thời gian vesting, khác thời điểm khấu trừ thuế. California đánh thuế thu nhập cổ phiếu như thu nhập thông thường, không có thuế suất ưu đãi cho lãi vốn.

> Ghi chú học tập cá nhân, không phải tư vấn thuế. (Bản dịch sơ bộ)

## हिन्दी (प्रारंभिक अनुवाद, समीक्षा लंबित)

इक्विटी मुआवज़े की सबसे आम कर-गलती «शेयर मिलना» और «नकद मिलना» को एक मान लेना है। संघीय आधार IRC § 83 है: सेवाओं के बदले मिली संपत्ति vesting पर बाज़ार मूल्य ऋण भुगतान राशि पर सामान्य आय होती है।

**NSO.** अनुदान या vesting पर कर नहीं; exercise पर बाज़ार मूल्य और exercise मूल्य का अंतर FICA व withholding सहित वेतन आय है, और नियोक्ता § 83(h) के तहत उतनी ही कटौती लेता है। उदाहरण: 1,000 शेयर, exercise मूल्य 10 डॉलर, बाज़ार मूल्य 30 डॉलर → 20,000 डॉलर सामान्य आय; आधार प्रति शेयर 30 डॉलर हो जाता है।

**ISO.** § 422 की शर्तें (शेयरधारक-अनुमोदित योजना, अनुदान-दिन मूल्य से कम न हो exercise मूल्य, वार्षिक 100,000 डॉलर सीमा, नौकरी छोड़ने के 3 माह के भीतर exercise आदि) और धारण अवधि (अनुदान के 2 वर्ष बाद व exercise के 1 वर्ष बाद) पूरी हों तो exercise पर सामान्य कर नहीं और अंतिम लाभ पूरा दीर्घकालिक पूंजीगत लाभ होता है। कीमत AMT है: अंतर § 56(b)(3) का समायोजन है। जल्दी बिक्री अयोग्य निपटान है। योग्य निपटान पर नियोक्ता को कटौती नहीं मिलती।

**RSU व प्रतिबंधित स्टॉक।** RSU vesting से पहले केवल वादा है, इसलिए § 83(b) चुनाव संभव नहीं; vesting पर पूरा मूल्य वेतन आय है। वास्तविक रूप से हस्तांतरित प्रतिबंधित स्टॉक पर § 83(b) संभव है, पर हस्तांतरण के 30 दिनों के भीतर IRS में दाखिल करना होता है (Reg. § 1.83-2); समय चूकने पर उपचार लगभग नहीं। बाद में ज़ब्ती हो तो चुकाया कर वापस नहीं मिलता।

**ESPP.** § 423 योजना में अधिकतम 15% छूट संभव है। योग्य निपटान (प्रस्ताव के 2 वर्ष व खरीद के 1 वर्ष बाद) पर छूट का केवल छोटा भाग सामान्य आय; जल्दी बिक्री पर पूरी छूट सामान्य आय।

**दो सावधानियाँ।** स्थगित निपटान को § 409A या अल्पकालिक स्थगन अपवाद में आना चाहिए; उल्लंघन पर 20% अतिरिक्त कर व ब्याज। लेखा अलग है: ASC 718 vesting अवधि में व्यय मानता है। कैलिफ़ोर्निया इक्विटी आय को सामान्य आय मानता है, पूंजीगत लाभ की रियायती दर नहीं।

> व्यक्तिगत अध्ययन नोट; कर सलाह नहीं। (प्रारंभिक अनुवाद)

## 补译增量（2026-11-14 05:55轮）

### 한국어 (초역, 원어민 감수 대기)

보충 세부 두 가지. 첫째, NSO 계산 그룹: 비적격 스톡옵션은 부여와 귀속 시점에는 일반적으로 과세되지 않고, 행사 시점에 행사일의 시가에서 행사가격을 뺀 차액이 보통 근로소득으로 계산되어 FICA와 원천징수 대상이 되며, 고용주는 같은 시점에 제83조 (h)에 따라 같은 금액을 공제합니다. 예컨대 주식 1,000주, 행사가격 10달러, 행사일 시가 30달러이면 차액 20달러 곱하기 1,000 = 20,000달러가 보통소득이고, 이후 매도 시 기준가는 주당 30달러가 되며 보유기간은 행사일 다음 날부터 셉니다. 둘째, ISO 조건 그룹: 제422조의 조건(주주가 승인한 계획, 행사가격이 부여일 시가 이상, 부여일 가치 기준 연간 최초 행사 가능분이 100,000달러를 넘지 않을 것, 퇴사 후 3개월 이내 행사 등)을 갖추고, 부여 후 2년과 행사 후 1년의 보유기간을 모두 채우면 적격 처분이 되어 행사 시 보통소득이 없고 최종 매도에서 전부 장기 자본이득이 됩니다. 대가는 대체최저세로, 행사가격 차액은 제56조 (b)(3)의 AMT 조정 항목이라 행사한 해에 AMT를 낼 수 있고, 고용주는 적격 처분에서는 공제를 받지 못합니다.

### Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

Hai chi tiết bổ sung. Thứ nhất, nhóm tính toán NSO: quyền chọn cổ phiếu không đủ điều kiện thường không bị đánh thuế khi cấp hay khi đáo hạn quyền sở hữu; tại thời điểm thực hiện, phần chênh giữa giá thị trường ngày thực hiện và giá thực hiện tính vào thu nhập thông thường dạng lương, chịu thuế FICA và khấu trừ tại nguồn, và người sử dụng lao động được khấu trừ cùng số tiền tại cùng thời điểm theo Điều 83(h). Ví dụ: 1.000 cổ phiếu, giá thực hiện 10 đô la, giá thị trường ngày thực hiện 30 đô la thì phần chênh 20 đô la nhân 1.000 = 20.000 đô la thu nhập thông thường; khi bán sau đó, giá vốn là 30 đô la mỗi cổ phiếu và kỳ nắm giữ tính từ ngày hôm sau ngày thực hiện. Thứ hai, nhóm điều kiện ISO: khi thỏa các điều kiện của Điều 422 (kế hoạch được cổ đông phê chuẩn, giá thực hiện không thấp hơn giá thị trường ngày cấp, phần được thực hiện lần đầu mỗi năm tính theo giá trị ngày cấp không quá 100.000 đô la, thực hiện trong vòng 3 tháng sau khi nghỉ việc, v.v.) và giữ đủ thời hạn — 2 năm sau ngày cấp và 1 năm sau ngày thực hiện — thì đó là chuyển nhượng đủ điều kiện: không có thu nhập thông thường khi thực hiện và toàn bộ lãi khi bán cuối cùng là lãi vốn dài hạn. Cái giá phải trả nằm ở thuế tối thiểu thay thế: phần chênh giá là khoản điều chỉnh AMT theo Điều 56(b)(3) nên năm thực hiện có thể phải nộp AMT, và người sử dụng lao động không được khấu trừ gì trong chuyển nhượng đủ điều kiện.

### हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

दो पूरक विवरण। पहला, NSO गणना समूह: गैर-योग्य स्टॉक विकल्पों पर सामान्यतः अनुदान या निहित (vesting) के समय कर नहीं लगता; प्रयोग के समय प्रयोग-दिन के बाज़ार मूल्य और प्रयोग मूल्य का अंतर साधारण वेतन आय में गिना जाता है, FICA और withholding लागू होता है, और नियोक्ता उसी समय धारा 83(h) के तहत उतनी ही राशि की कटौती करता है। उदाहरण: 1,000 शेयर, प्रयोग मूल्य 10 डॉलर, प्रयोग-दिन का मूल्य 30 डॉलर हो तो अंतर 20 डॉलर गुणा 1,000 = 20,000 डॉलर साधारण आय है; बाद में बेचने पर आधार प्रति शेयर 30 डॉलर होगा और धारण अवधि प्रयोग के अगले दिन से गिनी जाएगी। दूसरा, ISO शर्त समूह: धारा 422 की शर्तें पूरी हों (शेयरधारकों द्वारा अनुमोदित योजना, प्रयोग मूल्य अनुदान-दिन के मूल्य से कम न हो, अनुदान-दिन मूल्य के आधार पर वार्षिक प्रथम-प्रयोज्य भाग 100,000 डॉलर से अधिक न हो, नौकरी छोड़ने के 3 महीने के भीतर प्रयोग आदि) और धारण अवधि — अनुदान के बाद 2 वर्ष और प्रयोग के बाद 1 वर्ष — दोनों पूरे हों, तो यह योग्य निपटान होता है: प्रयोग पर साधारण आय नहीं और अंतिम बिक्री पर पूरा लाभ दीर्घकालिक पूँजीगत लाभ। इसकी कीमत वैकल्पिक न्यूनतम कर में है: प्रयोग-अंतर धारा 56(b)(3) का AMT समायोजन है, इसलिए प्रयोग वाले वर्ष में AMT लग सकता है, और योग्य निपटान में नियोक्ता को कोई कटौती नहीं मिलती।

