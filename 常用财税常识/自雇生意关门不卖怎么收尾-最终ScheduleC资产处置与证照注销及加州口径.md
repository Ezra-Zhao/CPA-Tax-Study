# 自雇生意关门不卖怎么收尾：最终 Schedule C、资产处置与证照注销及加州口径

> 个人学习笔记，不构成税务建议。分工先说清：本篇管「生意不做了、也没有买家接手」时的收尾路径——最后一年怎么报、剩下的存货和设备怎么处理、证照与账户怎么关。把整个生意打包卖给买家的分配规则（第 1060 条残余法与 Form 8594）见本仓同板块的卖生意专篇，两篇互为指针。关键步骤按 IRS 官网 Closing a Business（关闭企业）专题页与 IRS 相关出版物口径梳理，个案数字以当年表格说明为准。

## 中文主文

### 一、先分清：关门和卖掉是两套账

收尾方式不同，税表就不同。整间生意卖给买家，是把一组资产打包转让，总价要在七类资产之间分配，买卖双方还要各交一份 Form 8594 对上数。关门不卖没有这个动作：没有总价、没有分配，剩下的是三件事——营业到最后一天为止的收入费用照常结清，留在手里的存货与设备逐项处置，以及把雇主与经营者的各种登记逐项关掉。把关门当卖掉报，或者把卖掉当关门报，两边都会错位。

### 二、最后一年照常报，只是要标明是最后一年

独资经营者（sole proprietor）与按独资征税的单成员 LLC，最后一年仍用 Schedule C 报最后一年的收入与费用，之后不再有这间生意，就不再报 Schedule C。联邦 Schedule C 本身没有单独的「最终申报」勾选框，实务上以停止申报加保留记录来收口；相比之下，合伙用 Form 1065、公司用 Form 1120 或 1120-S 的，表上有 final return（最终申报）勾选框，关门那年要勾上，别漏。有雇员的，最后一份 Form 941（雇主季度税表）要勾选「这是最终申报」一类口径并注明停业日期，Form 940（联邦失业税）同理收尾；最后一批 W-2 与汇总表 W-3 仍按次年 1 月 31 日的期限交给社保局，最后一年付给外包人员的 Form 1099-NEC 也照常发出。预估税交到停业当年为止，停业后收入结构变了，次年预估税要按新情况重估，不要照着旧生意的节奏继续多交。

### 三、存货：卖掉、自用、捐掉，三条路三种处理

清仓打折卖掉的，按实际售价计收入，存货成本照常走销货成本（cost of goods sold），最后一年 Schedule C 的期末存货归零。卖不掉带回家自用的，没有出售行为、不产生出售收入；但要留神，进货成本已经通过销货成本或费用走过账的部分，不能在收尾时再重复扣一次。捐给慈善机构的，独资经营者就存货捐赠的扣除一般以存货基数（成本）为限，不按零售价算，具体按 IRS Publication 526 与存货捐赠规则核。最忌讳的是账上存货凭空消失：最后一年期末存货对不上，报税时很难解释，先盘点、再处置、留好清仓与捐赠凭证。

### 四、设备与车辆：算例一台机器

设备处置看三件事：调整后基数是多少、处置方式是什么、以前提过多少折旧。卖掉的走 Form 4797；第 1245 条规定，可折旧动产卖出有利得时，利得中相当于已提折旧的部分按普通收入回收（recapture），先于资本利得定性。报废丢弃的，未回收的基数一般按处置在 Form 4797 上形成损失处理；转作个人自用的，当下一般不确认损益，基数留着，日后出售再按转换与出售规则处理，细节以 IRS Publication 544 与 Publication 946 为准。

算例（情景假设，数字可复算）：假设一台机器买入价 30,000 美元，历年已提折旧合计 22,000 美元，则调整后基数 = 30,000 − 22,000 = 8,000 美元。情形一，关门时以 10,000 美元卖出：实现利得 = 10,000 − 8,000 = 2,000 美元；这 2,000 美元小于已提折旧 22,000 美元，按第 1245 条全额作为普通收入回收。情形二，只卖了 5,000 美元：损失 = 8,000 − 5,000 = 3,000 美元，在 Form 4797 上按营业资产处置处理。情形三，不卖、报废且无人要：未回收基数 8,000 美元按废弃处置形成损失处理，留好报废记录。三种情形共用同一个基数 8,000 美元，先算基数、再谈处置，是这一步不翻车的办法。

### 五、应收、应付与退休计划的尾巴

现金制（cash method）纳税人关门时，还没收到的应收账款一般不计收入，收不回来也没有坏账扣除可言，因为这笔钱从未计入过收入；应计制（accrual method）则相反，收入已经认过，真收不回时再按坏账规则处理。欠供应商的账、欠的税、营业场所租约的提前终止安排，属于债务与合同问题，不因停止申报而消失，该结清的结清、该协商的协商。自雇退休计划如 Solo 401(k)，关门不等于计划自动终止：要正式终止计划、把资产分配或滚存出去，并就终止年度提交最终版 Form 5500-EZ，期限与表格版本按 IRS 当期说明办；计划不正式终止，年度申报义务就可能一直挂着。

### 六、关户清单与记录保存

雇主识别号（EIN）本身不能注销、也不会被重新分配给别人，能关的是 IRS 那边的企业税务账户：按 IRS 关闭企业专题页的做法，给 EIN 当初分配函上列明的 IRS 地址写信，说明关户原因并附分配函副本，请求关闭企业账户。记录保存按 IRS 口径：雇佣税记录至少保留 4 年，所得税相关记录一般至少 3 年、涉及重大少报等情形更久，本仓税表保存年限专篇有细目。州与地方的证照不会因为联邦收尾自动关闭，逐项办：销售税许可证、营业执照、商号（DBA）登记、雇主账户，各回各的发证机关销户。

### 七、加州口径

加州一侧逐项对：独资经营者没有州层面的实体注销文件，主要动作在证照与税户——向 CDTFA 关闭销售税许可证（seller's permit）账户并交最后一期销售税申报，向 EDD 结清雇主工资税账户的最终申报，营业执照与 DBA 到市、县办理撤销。若生意是加州 LLC，须向州务卿提交注销文件（Certificate of Cancellation，Form LLC-4/4 一线）并交最终年度 Form 568；在正式注销完成之前，LLC 每年 800 美元的年税（annual tax）会继续产生，停业不报不等于义务停止，这一点最容易被拖出欠账。FTB 的最终口径与表格以当年公布为准。

*声明：个人学习笔记，不构成税务建议。来源：IRS 官网 Closing a Business 专题页（最终申报、最终雇佣税表、EIN 企业账户关闭与记录保存口径）；IRC 第 1245 条（折旧回收）与 Form 4797、Schedule C、Form 941、Form 5500-EZ 当期表格说明；IRS Publication 526、544、946 指针；加州 CDTFA、EDD、FTB 与州务卿注销口径指针。算例为情景假设并已复算：30,000 − 22,000 = 8,000；10,000 − 8,000 = 2,000；8,000 − 5,000 = 3,000。具体个案请咨询持牌 CPA 或税务律师。*

---

## English

> Study notes, not tax advice. This article covers closing a self-employed business with no buyer — as distinct from selling it as a package, which follows the section 1060 allocation rules and Form 8594 covered elsewhere in this repository.

**Final-year filing.** A sole proprietor (or a single-member LLC taxed that way) files a last Schedule C for the final year and then stops; the federal Schedule C has no separate final-return checkbox, while partnerships (Form 1065) and corporations (Form 1120 / 1120-S) do check the final return box in the closing year. Employers file a final Form 941 and Form 940 marked as final, still issue the last W-2s with Form W-3 by January 31, and still send final Forms 1099-NEC. **Inventory.** Clearance sales are income at actual prices with cost flowing through cost of goods sold, ending inventory at zero; inventory taken home for personal use is not a sale, but its cost cannot be deducted twice; donated inventory is generally deductible only up to basis for a sole proprietor (see IRS Publication 526). **Equipment — worked example (hypothetical).** A machine cost $30,000 with $22,000 of depreciation taken has an adjusted basis of $30,000 − $22,000 = $8,000. Sold for $10,000, the gain is $10,000 − $8,000 = $2,000, all ordinary under section 1245 recapture because it is less than the $22,000 of depreciation. Sold for $5,000, the loss is $8,000 − $5,000 = $3,000 on Form 4797. Scrapped, the unrecovered $8,000 basis is treated as an abandonment loss with records kept. **Loose ends.** Cash-method receivables never collected are simply never income (and yield no bad-debt deduction); a Solo 401(k) must be formally terminated, with assets distributed or rolled over and a final Form 5500-EZ filed. An EIN itself is never cancelled or reassigned; you close the IRS business account by letter under the IRS Closing a Business guidance, and keep employment tax records at least four years. **California:** close the CDTFA seller's permit account with a final sales tax return, file final EDD employer returns, and withdraw local licenses and the DBA; a California LLC must file a Certificate of Cancellation with the Secretary of State and a final Form 568 — until cancellation is complete, the $800 annual LLC tax keeps accruing. *Personal study notes; not tax advice.*

---

## Español (初译待校)

> Notas de estudio, no asesoría fiscal. Este artículo trata del cierre de un negocio propio sin comprador, distinto de venderlo como paquete, que sigue las reglas de asignación de la sección 1060 y el Formulario 8594 tratados en otra parte de este repositorio.

**Declaración del último año.** El empresario individual (o la LLC de un solo miembro gravada así) presenta un último Schedule C por el año final y después deja de presentarlo; el Schedule C federal no tiene casilla propia de declaración final, mientras que las sociedades colectivas (Formulario 1065) y las corporaciones (1120 / 1120-S) sí marcan la casilla de declaración final el año del cierre. El empleador presenta los Formularios 941 y 940 finales marcados como tales, emite los últimos W-2 con el W-3 antes del 31 de enero y envía los últimos 1099-NEC. **Inventario.** La liquidación se declara al precio real con el costo por costo de ventas e inventario final en cero; llevarse mercancía a casa para uso personal no es una venta, pero su costo no puede deducirse dos veces; el inventario donado, para el empresario individual, en general solo es deducible hasta su base (véase la Publicación 526 del IRS). **Equipo: ejemplo (hipotético).** Una máquina de 30.000 dólares con 22.000 de depreciación tiene base ajustada de 30.000 − 22.000 = 8.000. Vendida por 10.000, la ganancia es 10.000 − 8.000 = 2.000, toda ordinaria por la recaptura de la sección 1245 al ser menor que la depreciación de 22.000. Vendida por 5.000, la pérdida es 8.000 − 5.000 = 3.000 en el Formulario 4797. Desechada, la base no recuperada de 8.000 se trata como pérdida por abandono, con registros. **Cabos sueltos.** Las cuentas por cobrar del método de caja que nunca se cobran nunca fueron ingreso (y no dan deducción por incobrable); un Solo 401(k) debe terminarse formalmente, con distribución o reinversión de activos y un Formulario 5500-EZ final. El EIN nunca se cancela ni se reasigna: se cierra la cuenta comercial ante el IRS por carta según su guía Closing a Business, y los registros de impuestos sobre el empleo se guardan al menos cuatro años. **California:** cierre la cuenta del permiso de vendedor ante la CDTFA con declaración final, presente las declaraciones finales de empleador ante la EDD y retire licencias locales y el DBA; una LLC de California debe presentar el certificado de cancelación ante la Secretaría de Estado y un Formulario 568 final: hasta completar la cancelación, el impuesto anual de 800 dólares sigue generándose. (初译待校)

*Notas personales de estudio; no constituye asesoría fiscal.*

---

## 한국어 (初译待校)

> 개인 학습 노트이며 세무 자문이 아닙니다. 이 글은 사업체를 통째로 파는 경우(제1060조 배분 규칙과 Form 8594는 본 저장소의 다른 글에서 다룹니다)와 달리, 매수인 없이 자영업을 접을 때의 마무리를 다룹니다.

**마지막 해 신고.** 개인사업자(또는 그렇게 과세되는 1인 LLC)는 마지막 해의 Schedule C를 내고 이후 중단합니다. 연방 Schedule C에는 별도의 최종 신고 체크란이 없지만, 파트너십(Form 1065)과 법인(Form 1120 / 1120-S)은 폐업 연도에 최종 신고(final return)란에 표시합니다. 고용주는 최종 Form 941과 Form 940을 최종분으로 제출하고, 마지막 W-2와 W-3를 1월 31일까지 내며, 마지막 Form 1099-NEC도 보냅니다. **재고.** 할인 처분 판매는 실제 가격으로 소득 신고하고 원가는 매출원가로 흘려 기말 재고를 0으로 맞춥니다. 집에 가져가 개인적으로 쓰는 재고는 판매가 아니지만, 이미 처리한 원가를 다시 공제할 수는 없습니다. 기부한 재고는 개인사업자의 경우 일반적으로 취득가액(원가)까지만 공제됩니다(IRS Publication 526 참조). **장비 계산 예시(가정).** 취득가 30,000달러, 감가상각 누적 22,000달러인 기계의 조정 취득가액은 30,000 − 22,000 = 8,000달러입니다. 10,000달러에 팔면 이익은 10,000 − 8,000 = 2,000달러이고, 감가상각액 22,000달러보다 작으므로 제1245조에 따라 전액 경상소득으로 환수(recapture)됩니다. 5,000달러에 팔면 손실은 8,000 − 5,000 = 3,000달러로 Form 4797에 보고합니다. 폐기하면 회수되지 않은 8,000달러를 폐기 손실로 처리하고 기록을 남깁니다. **남은 일.** 현금주의 미수금은 끝내 받지 못하면 애초에 소득이 아니므로 대손 공제도 없습니다. Solo 401(k)는 정식으로 종료하고 자산을 분배하거나 이체한 뒤 최종 Form 5500-EZ를 내야 합니다. EIN 자체는 취소되거나 재사용되지 않으며, IRS의 Closing a Business 안내에 따라 서신으로 사업 계정을 닫고, 고용세 기록은 최소 4년 보관합니다. **캘리포니아:** CDTFA 판매자 허가 계정을 최종 판매세 신고와 함께 닫고, EDD 고용주 최종 신고를 하며, 지방 영업허가와 DBA를 철회합니다. 캘리포니아 LLC는 주무장관에게 취소 증명서를 제출하고 최종 Form 568을 내야 하며, 취소가 완료되기 전까지 연 800달러의 LLC 연간세가 계속 발생합니다. (初译待校)

*개인 학습 노트이며 세무 자문이 아닙니다.*

---

## Tiếng Việt (初译待校)

> Ghi chú học tập cá nhân, không phải tư vấn thuế. Bài này bàn về việc đóng cửa một cơ sở tự doanh khi không có người mua — khác với bán trọn gói, vốn theo quy tắc phân bổ của mục 1060 và Mẫu 8594 được trình bày ở nơi khác trong kho này.

**Khai thuế năm cuối.** Chủ hộ kinh doanh cá thể (hoặc LLC một thành viên bị đánh thuế như vậy) nộp Schedule C cuối cùng cho năm cuối rồi dừng; Schedule C liên bang không có ô riêng cho tờ khai cuối cùng, trong khi hợp danh (Mẫu 1065) và công ty (1120 / 1120-S) phải đánh dấu ô tờ khai cuối cùng (final return) vào năm đóng cửa. Người sử dụng lao động nộp Mẫu 941 và 940 cuối cùng có đánh dấu cuối cùng, vẫn cấp W-2 cuối cùng kèm W-3 trước ngày 31 tháng 1, và vẫn gửi Mẫu 1099-NEC cuối cùng. **Hàng tồn kho.** Bán thanh lý khai theo giá thực tế, giá vốn đi qua giá vốn hàng bán và tồn kho cuối kỳ bằng 0; mang hàng về nhà dùng cá nhân không phải là bán, nhưng giá vốn đã hạch toán không được khấu trừ lần nữa; hàng tồn kho đem tặng, với chủ hộ cá thể, nói chung chỉ được khấu trừ tối đa bằng giá vốn (xem IRS Publication 526). **Thiết bị — ví dụ tính (giả định).** Một máy mua 30.000 đô la, đã khấu hao 22.000, có cơ sở điều chỉnh là 30.000 − 22.000 = 8.000. Bán với giá 10.000, khoản lãi là 10.000 − 8.000 = 2.000, toàn bộ là thu nhập thường theo quy tắc thu hồi khấu hao của mục 1245 vì nhỏ hơn 22.000 khấu hao đã trừ. Bán với giá 5.000, khoản lỗ là 8.000 − 5.000 = 3.000 trên Mẫu 4797. Hủy bỏ thì phần cơ sở chưa thu hồi 8.000 được xử lý như lỗ do từ bỏ tài sản, có lưu hồ sơ. **Việc còn lại.** Khoản phải thu theo phương pháp tiền mặt mà không bao giờ thu được thì chưa từng là thu nhập (và cũng không được khấu trừ nợ xấu); Solo 401(k) phải chấm dứt chính thức, phân phối hoặc chuyển tiếp tài sản và nộp Mẫu 5500-EZ cuối cùng. Bản thân EIN không bao giờ bị hủy hay cấp lại cho người khác; bạn đóng tài khoản doanh nghiệp với IRS bằng thư theo hướng dẫn Closing a Business, và giữ hồ sơ thuế lao động ít nhất bốn năm. **California:** đóng tài khoản giấy phép người bán tại CDTFA kèm tờ khai thuế bán hàng cuối cùng, nộp tờ khai người sử dụng lao động cuối cùng cho EDD, rút giấy phép địa phương và DBA; LLC tại California phải nộp giấy chứng nhận hủy bỏ cho Bộ trưởng Ngoại giao bang và Mẫu 568 cuối cùng — cho đến khi hủy bỏ hoàn tất, khoản thuế hằng năm 800 đô la của LLC vẫn tiếp tục phát sinh. (初译待校)

*Ghi chú học tập cá nhân, không phải tư vấn thuế.*

---

## हिन्दी (初译待校)

> व्यक्तिगत अध्ययन नोट, कर सलाह नहीं। यह लेख बिना ख़रीदार के स्वरोज़गार व्यवसाय बंद करने की प्रक्रिया बताता है — पूरे व्यवसाय को पैकेज के रूप में बेचने से भिन्न, जिस पर धारा 1060 के आवंटन नियम और फ़ॉर्म 8594 लागू होते हैं और जो इस भंडार में अन्यत्र वर्णित है।

**अंतिम वर्ष की फ़ाइलिंग.** एकल स्वामी (या उसी तरह कर-योग्य एक-सदस्यीय LLC) अंतिम वर्ष के लिए आख़िरी Schedule C दाख़िल करता है और फिर रुक जाता है; संघीय Schedule C में अंतिम रिटर्न का अलग चेकबॉक्स नहीं है, जबकि साझेदारियाँ (फ़ॉर्म 1065) और निगम (1120 / 1120-S) बंद होने के वर्ष में final return बॉक्स पर निशान लगाते हैं। नियोक्ता अंतिम फ़ॉर्म 941 और 940 को अंतिम के रूप में दाख़िल करता है, 31 जनवरी तक अंतिम W-2 के साथ W-3 देता है, और अंतिम फ़ॉर्म 1099-NEC भी भेजता है। **इन्वेंटरी.** क्लीयरेंस बिक्री वास्तविक कीमतों पर आय है, लागत cost of goods sold से गुज़रती है और अंतिम इन्वेंटरी शून्य होती है; घर ले जाकर निजी उपयोग में ली गई इन्वेंटरी बिक्री नहीं है, पर उसकी लागत दोबारा नहीं काटी जा सकती; दान की गई इन्वेंटरी एकल स्वामी के लिए सामान्यतः केवल आधार (लागत) तक कटौती-योग्य है (IRS Publication 526 देखें)। **उपकरण — उदाहरण (काल्पनिक).** 30,000 डॉलर लागत और 22,000 डॉलर मूल्यह्रास वाली मशीन का समायोजित आधार 30,000 − 22,000 = 8,000 डॉलर है। 10,000 डॉलर में बेचने पर लाभ 10,000 − 8,000 = 2,000 डॉलर है, जो 22,000 डॉलर मूल्यह्रास से कम होने के कारण धारा 1245 की recapture के तहत पूरा साधारण आय है। 5,000 डॉलर में बेचने पर हानि 8,000 − 5,000 = 3,000 डॉलर फ़ॉर्म 4797 पर जाएगी। स्क्रैप करने पर अप्राप्त 8,000 डॉलर आधार परित्याग हानि के रूप में रहेगा, अभिलेख सहित। **बचे काम.** नकद-विधि की कभी न वसूली गई प्राप्तियाँ कभी आय ही नहीं थीं (और उन पर bad-debt कटौती भी नहीं मिलती); Solo 401(k) को औपचारिक रूप से समाप्त करना होगा, संपत्ति वितरित या rollover करनी होगी और अंतिम फ़ॉर्म 5500-EZ दाख़िल करना होगा। EIN स्वयं कभी रद्द या पुनः आवंटित नहीं होता; IRS की Closing a Business मार्गदर्शिका के अनुसार पत्र लिखकर व्यवसाय खाता बंद करें, और रोज़गार कर अभिलेख कम से कम चार वर्ष रखें। **California:** CDTFA विक्रेता परमिट खाता अंतिम बिक्री कर रिटर्न के साथ बंद करें, EDD में अंतिम नियोक्ता रिटर्न दें, स्थानीय लाइसेंस और DBA वापस लें; California LLC को Secretary of State के पास निरसन प्रमाणपत्र और अंतिम फ़ॉर्म 568 देना होगा — निरसन पूरा होने तक 800 डॉलर का वार्षिक LLC कर बनता रहेगा। (初译待校)

*व्यक्तिगत अध्ययन नोट; कर सलाह नहीं है।*


## 补译增量（2026-11-17 09:55轮）

以下韩／越／印三语各补两项中文主文已有、原译文同缺的细节（预估税重估与应付租约尾巴），纯增量只加不删：

한국어 보충 (초역, 원어민 감수 대기): 두 가지 세부사항을 보충합니다. 첫째, 추정세는 폐업 연도까지 납부하고, 폐업 후에는 소득 구조가 바뀌므로 다음 해 추정세는 새 상황에 맞춰 다시 산정해야 하며, 옛 사업의 리듬대로 계속 과다 납부하지 말아야 합니다. 둘째, 거래처에 대한 미지급금, 체납 세금, 사업장 임대차의 조기 종료 조정은 채무·계약 문제로서 신고를 중단한다고 사라지지 않으므로, 정산할 것은 정산하고 협의할 것은 협의해야 합니다.

Bổ sung tiếng Việt (bản dịch sơ bộ, chờ hiệu đính): bổ sung hai chi tiết. Một, thuế tạm nộp được nộp đến hết năm đóng cửa; sau khi đóng cửa, cơ cấu thu nhập đã thay đổi nên thuế tạm nộp của năm sau phải ước tính lại theo tình hình mới, đừng tiếp tục nộp thừa theo nhịp của cơ sở cũ. Hai, các khoản còn nợ nhà cung cấp, thuế còn nợ và việc dàn xếp chấm dứt sớm hợp đồng thuê mặt bằng là vấn đề nợ và hợp đồng, không biến mất khi ngừng khai thuế; khoản nào cần thanh toán thì thanh toán, khoản nào cần thương lượng thì thương lượng.

हिन्दी पूरक (प्रारंभिक अनुवाद, समीक्षा लंबित): दो विवरण जोड़े जाते हैं। पहला, अनुमानित कर बंद होने के वर्ष तक चुकाया जाता है; बंद होने के बाद आय की संरचना बदल जाती है, इसलिए अगले वर्ष का अनुमानित कर नई स्थिति के अनुसार फिर से आँकना चाहिए और पुराने व्यवसाय की लय में अधिक भुगतान जारी नहीं रखना चाहिए। दूसरा, आपूर्तिकर्ताओं के बकाए, देय कर और परिसर पट्टे की समय-पूर्व समाप्ति की व्यवस्था ऋण और अनुबंध के मामले हैं, जो फ़ाइलिंग बंद करने से ग़ायब नहीं होते; जिसका निपटान करना है उसका निपटान करें, जिस पर बातचीत करनी है उस पर बातचीत करें।
