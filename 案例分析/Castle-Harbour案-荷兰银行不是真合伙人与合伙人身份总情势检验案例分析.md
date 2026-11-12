# Castle Harbour 案：分走 98% 经营收入的荷兰银行，为什么不算真合伙人

> 板块：案例分析｜本篇经 ls/grep 实查：「Castle Harbour」「TIFD」「城堡港」全仓零命中、无本体专篇，故一次成篇；仓内《合伙企业税务备考核心》篇管 Subchapter K 的分配规则本体、《ACM 案》与《Coltec 案》两篇管经济实质一侧，本篇管更靠前的一道门——名义合伙人到底算不算合伙人，三篇以指针分工。案情与引证经第二巡回判决原文（459 F.3d 220，司法部所载文本）逐项回核，见文末来源。文末声明：个人学习笔记，不构成税务建议。

## 中文主文

### 一、案情：一支折旧提光的机队，配上一份九成八的收入分配

通用电气资本公司（GECC）长期做飞机租赁：向航空公司出租自有商用飞机，收入来自租金，税上的好处来自折旧。问题是，它手里有一支飞机已经把折旧提满了——租金照收，却再没有折旧可扣，持有这支机队的税后回报明显变差。1993 年，GECC 采纳了 Babcock & Brown 的方案（为此支付了 9,000,000 美元的协助费用），组建一家存续期八年的合伙 Castle Harbour LLC，把这支机队装进去，再请在美国不缴税的外国金融机构进来当合伙人。

注资结构（判决原文数字）：GECC 一侧转入市值 272,000,000 美元的飞机、22,000,000 美元的租金应收款与 296,000,000 美元现金，合计出资 590,000,000 美元；两家荷兰银行——ING Bank N.V. 与 Rabo Merchant Bank N.V.——合计投入现金 117,500,000 美元。地区法院认定的资本份额是 GECC 一侧约 82%、荷兰银行约 18%。银行的参与是被动的：不选管理人、不派员工、不管日常经营，经营全归 GECC 一侧。

分配机制是全案的心脏。合伙协议把合伙的「经营收入」（Operating Income，占合伙收入的绝大部分）按 98% 分给荷兰银行。但这只是税口径的分配：经营收入先被大额折旧冲减，而这批飞机税上早已提满折旧、冲减的折旧在税上根本不被承认，于是银行名下分到的应税收入，远远大于它们实际能拿到的钱。银行实际拿到的，是按事先排定的八年时间表返还其 117,500,000 美元本金，外加年化 9.03587% 的回报率（某些情形下为 8.53587%），只在合伙收益意外大好时有小幅上浮的可能；这份返还还被 GECC 一侧的多重合同承诺牢牢担保。效果一目了然：合伙的大部分应税收入在纸面上归了不缴美国税的银行，现金却基本按固定回报流回 GECC 一侧。

### 二、程序链：四站诉讼，两次被第二巡回推翻

合伙在 1993 至 1998 年逐年申报。2001 年，IRS 发出两份最终合伙行政调整通知（FPAA），认定荷兰银行不是真正的权益合伙人、分配不成立，把约 310,000,000 美元收入重新分给纳税人 TIFD III-E（GECC 的子公司、合伙的税务事项合伙人），补税 62,212,010 美元。纳税人按第 6226 条缴存税款后起诉。

- **地区法院（Castle Harbour I）**：康涅狄格区法院（Underhill 法官）经八天庭审，于 2004 年判决纳税人胜诉，342 F. Supp. 2d 94——合伙虽有明显的税务动机，但另有真实经营目的与经济效果，银行是合伙人，FPAA 无效。
- **第二巡回（Castle Harbour II）**：2006 年 8 月 3 日判决，459 F.3d 220（Leval 法官执笔，2005 年 12 月 1 日辩论），推翻并回。核心认定：银行对合伙的成败没有实质性的利害关系（no meaningful stake in the success or failure of the partnership），其权益实质上是担保贷款式的安排，凡与权益合伙人标签相符的部分都属虚幻或微不足道，IRS 有权对这种名实不符的权益重新定性。法院据此结案，无须再审第 704(b) 条的分配问题。
- **回审与再审（Castle Harbour III、IV）**：回审后地区法院 2009 年改以第 704(e)(1) 条认定银行是合伙人、且不应加罚，660 F. Supp. 2d 367；第二巡回 2012 年再次推翻，666 F.3d 836——银行按第 704(e)(1) 条也不算合伙人，第 6662 条实质性低报罚则成立。

### 三、检验内容：先问是不是合伙人，再问分配合不合规

本案留下的检验顺序，是合伙税备考的一条主线：

1. **身份先于分配**。第 704(b) 条的实质性经济效果检验，预设了对方先是合伙人。若被分收入的一方根本不是真正的合伙人，分配条款写得再合规也救不回来——本案第二巡回正是绕开第 704(b) 条、在身份层结案。
2. **身份看总情势，不看标签**。沿 Culbertson 一脉的合伙意图与总情势检验：各方是否真心以合伙人身份共同经营、共担盈亏。协议把银行写成「权益合伙人」只是标签，法院看的是权利义务的实际构造。
3. **利害关系要双向真实**。下行一侧：银行的本金与固定回报被多重担保锁死，合伙亏损基本伤不到它；上行一侧：收益意外大好时银行只能小幅多分，98% 的名义份额并不对应真实的上行敞口。两个方向都接近于零时，权益就是虚幻或微不足道的。
4. **重新定性的权限**。判决开头的问题意识是：当一项权益只在虚幻或微不足道的方面与它的名义分类相符时，IRS 有权加以审查并重新定性——本案的银行权益被读成实质上的担保融资。

### 四、算例（案卷数字，本地整数与 Decimal 两路复算勾稽一致）

- 固定回报的量级：117,500,000 美元乘 9.03587%，约等于 10,617,147 美元一年；按较低档 8.53587% 算，约 10,029,647 美元一年。银行的年现金回报是一条由本金乘固定费率得出的直线，不随合伙经营收入起伏——这正是法院认定其为贷款式回报的算术面孔。
- 名实差距：银行名义分得经营收入的 98%，资本份额却只有约 18%，两者相差 80 个百分点；税上分走的收入份额与账上资本、现金回报三条线全对不齐，正是「分配」被掀翻的数字证据。
- 筹划成本：Babcock & Brown 的协助费 9,000,000 美元，约占 GECC 一侧出资 590,000,000 美元的 1.53%——方案本身就是一笔为税而买的交易。

### 五、今日落点与加州口径

今日做合伙分配，先过身份门、再过第 704(b) 条：第 704(e)(1) 条（资本权益持有人的合伙人地位）在本案后再审中被读成同样要看权益的真实经济含量；身份不成立时，第 6662 条罚则可以跟上（Castle Harbour IV）。与仓内 ACM、Coltec 两案的经济实质路径对照：那两案打的是交易本身的实质，本案打的是参与人的身份——三条防线层次不同，引用时不要混作一谈。

加州口径：加州的合伙与有限责任公司税制大体跟随联邦的合伙人身份与分配框架处理州申报，州法院无针对本案的对应判例，本案在州侧只作联邦规则的出处引用（证据等级 B）。

*来源：TIFD III-E, Inc. v. United States, 459 F.3d 220 (2d Cir. 2006)（2005-12-01 辩论、2006-08-03 判决、Leval 执笔；案情数字——飞机 272,000,000 美元、应收款 22,000,000 美元、现金 296,000,000 美元、银行注资 117,500,000 美元、回报率 9.03587% 与 8.53587%、重新分配收入约 310,000,000 美元、补税 62,212,010 美元、Babcock & Brown 费用 9,000,000 美元——经判决原文回核）；下级链 342 F. Supp. 2d 94 (D. Conn. 2004)；后续链 660 F. Supp. 2d 367 (D. Conn. 2009) 与 666 F.3d 836 (2d Cir. 2012)；法条为第 704(b)、704(e)(1)、6226、6662 条。*

*个人学习笔记，不构成税务建议。*

## English

Castle Harbour is the Second Circuit's leading modern statement that partnership tax begins with a status question: is the person allocated the income actually a partner? GECC owned a fleet of fully depreciated leased aircraft — rents still coming in, no depreciation left. In 1993, on a Babcock & Brown plan for which it paid 9,000,000 dollars, GECC formed the eight-year Castle Harbour LLC, contributing aircraft worth 272,000,000 dollars, 22,000,000 dollars of rental receivables and 296,000,000 dollars of cash (590,000,000 dollars in total), while two Dutch banks, ING and Rabo Merchant Bank, contributed 117,500,000 dollars in cash — about 18 percent of the capital against GECC's 82 percent — and played no role in management.

The operating agreement allocated 98 percent of Operating Income, the great bulk of partnership income, to the banks for tax purposes. But Operating Income was computed after huge depreciation charges on aircraft that were already fully depreciated for tax purposes, so the banks' share of taxable income vastly exceeded anything they would receive. What the banks were actually entitled to was return of their 117,500,000 dollars on a fixed eight-year schedule at 9.03587 percent (8.53587 percent in some circumstances), formidably secured by GECC undertakings, with only a slight possible increase if earnings were unexpectedly strong. Almost all taxable income was thus paper-allocated to partners who paid no United States tax, while the cash economics stayed with GECC.

The IRS's 2001 FPAAs reallocated roughly 310,000,000 dollars of income to the tax-matters partner, TIFD III-E, assessing 62,212,010 dollars. The district court (342 F. Supp. 2d 94, D. Conn. 2004) held for the taxpayer after an eight-day bench trial. The Second Circuit reversed, TIFD III-E, Inc. v. United States, 459 F.3d 220 (2d Cir. 2006) (Leval, J.; argued December 1, 2005, decided August 3, 2006): the banks had no meaningful stake in the success or failure of the partnership, their interest was in substance a secured financing, and whatever resembled equity was illusory or insignificant — so the section 704(b) allocation question never had to be reached. On remand the district court sustained partner status under section 704(e)(1) and rejected penalties (660 F. Supp. 2d 367, D. Conn. 2009), and the Second Circuit reversed again (666 F.3d 836, 2d Cir. 2012): not partners under section 704(e)(1), and the section 6662 penalty applied.

The arithmetic exposes the design (case figures, recomputed two ways locally): 117,500,000 at 9.03587 percent is about 10,617,147 dollars a year — a straight line off principal, not a share of fluctuating profits — while the banks' nominal 98 percent income share stood 80 percentage points away from their roughly 18 percent capital share. California practice generally follows the federal partner-status and allocation framework for state filing, with no state counterpart decision (evidence grade B).

*Personal study notes; not tax advice. Sources: 459 F.3d 220 (2d Cir. 2006) and the decisions cited within; IRC sections 704(b), 704(e)(1), 6226, 6662.*

## Español — traducción preliminar, pendiente de revisión (初译待校)

Castle Harbour es la declaración moderna principal del Segundo Circuito de que el impuesto de sociedades colectivas empieza con una pregunta de estatus: ¿la persona a la que se asigna el ingreso es realmente socia? GECC poseía una flota de aviones arrendados ya totalmente depreciados. En 1993, con un plan de Babcock & Brown por el que pagó 9,000,000 de dólares, formó Castle Harbour LLC por ocho años, aportando aviones por 272,000,000, cuentas por cobrar de 22,000,000 y efectivo de 296,000,000 (590,000,000 en total), mientras dos bancos neerlandeses, ING y Rabo Merchant Bank, aportaron 117,500,000 en efectivo — cerca del 18 por ciento del capital — sin papel alguno en la gestión.

El acuerdo asignó a los bancos, a efectos fiscales, el 98 por ciento del ingreso operativo, calculado tras enormes cargos de depreciación sobre aviones ya depreciados fiscalmente, de modo que su ingreso gravable superaba con creces lo que recibirían. En realidad tenían derecho a la devolución de sus 117,500,000 según un calendario fijo de ocho años al 9.03587 por ciento (8.53587 en algunos casos), sólidamente garantizada, con solo un leve aumento posible si las ganancias eran inesperadamente altas. El IRS reasignó en 2001 unos 310,000,000 de ingreso y liquidó 62,212,010 de impuesto adicional. El tribunal de distrito falló por el contribuyente (342 F. Supp. 2d 94, 2004), pero el Segundo Circuito revocó (459 F.3d 220, 2006): los bancos no tenían una participación significativa en el éxito o fracaso de la sociedad, su interés era en sustancia una financiación garantizada y lo que parecía capital era ilusorio o insignificante. Tras la devolución, el tribunal de distrito reconoció la condición de socios bajo el § 704(e)(1) (660 F. Supp. 2d 367, 2009) y el Segundo Circuito revocó de nuevo (666 F.3d 836, 2012), con multa del § 6662. La aritmética lo resume: 117,500,000 al 9.03587 por ciento son unos 10,617,147 al año, una línea recta sobre el principal, frente a una participación nominal del 98 por ciento del ingreso con solo un 18 por ciento del capital. (初译待校)

*Notas personales de estudio; no constituyen asesoramiento fiscal. Fuentes: 459 F.3d 220 (2d Cir. 2006); IRC §§ 704(b), 704(e)(1), 6226, 6662.*

## 한국어 — 초역, 교정 대기 중 (初译待校)

Castle Harbour 사건은 파트너십 과세가 지위 문제에서 시작한다는 제2순회항소법원의 대표적 현대 판례이다. GECC는 감가상각이 이미 끝난 임대 항공기 기단을 보유하고 있었다. 1993년 Babcock & Brown의 방안에 9,000,000달러를 지급하고 8년 존속의 Castle Harbour LLC를 설립하여 항공기 272,000,000달러, 임대료 채권 22,000,000달러, 현금 296,000,000달러(합계 590,000,000달러)를 출자했고, 네덜란드 은행 두 곳(ING와 Rabo Merchant Bank)은 현금 117,500,000달러(자본의 약 18%)를 출자하고 경영에는 참여하지 않았다.

운영계약은 영업소득의 98%를 세무상 은행에 배분했는데, 이 소득은 세무상 이미 상각이 끝난 항공기에 대한 거액의 감가상각을 차감한 뒤 계산되어 은행의 과세소득은 실제 수령액을 훨씬 넘었다. 은행이 실제로 받는 것은 117,500,000달러를 8년 고정 일정으로 연 9.03587%(일부 경우 8.53587%)의 수익률과 함께 돌려받는 권리뿐이었고, 이는 GECC 측의 다중 약속으로 강력히 담보되었으며 이익이 이례적으로 좋을 때만 소폭의 추가분이 가능했다. IRS는 2001년 약 310,000,000달러의 소득을 재분배하고 62,212,010달러를 추징했다. 지방법원은 납세자 승소 판결을 내렸으나(342 F. Supp. 2d 94, 2004), 제2순회항소법원은 이를 뒤집었다(459 F.3d 220, 2006). 은행은 파트너십의 성패에 실질적인 이해관계가 없었고, 그 지분은 실질상 담보부融资이며 자본처럼 보이는 부분은 환상에 가깝거나 미미하다는 이유였다. 환송 후 지방법원이 §704(e)(1)에 따라 파트너 지위를 인정하자(660 F. Supp. 2d 367, 2009), 항소법원은 다시 뒤집고 §6662 가산세까지 인정했다(666 F.3d 836, 2012). 숫자도 같은 이야기를 한다. 117,500,000달러의 9.03587%는 연 약 10,617,147달러로 원금에 대한 직선이며, 명목 소득 지분 98%와 자본 지분 약 18%는 80%포인트 벌어져 있다. (初译待校)

*개인 학습 노트이며 세무 자문이 아니다. 출처: 459 F.3d 220 (2d Cir. 2006); IRC §§ 704(b), 704(e)(1), 6226, 6662.*

## Tiếng Việt — bản dịch sơ bộ, chờ hiệu đính (初译待校)

Castle Harbour là phán quyết hiện đại tiêu biểu của Tòa phúc thẩm khu vực 2 rằng thuế đối tác bắt đầu bằng câu hỏi về tư cách: người được phân bổ thu nhập có thực sự là thành viên hợp danh không? GECC sở hữu một đội máy bay cho thuê đã khấu hao hết. Năm 1993, theo phương án của Babcock & Brown với phí 9,000,000 đô la, GECC thành lập Castle Harbour LLC thời hạn tám năm, góp máy bay trị giá 272,000,000, khoản phải thu tiền thuê 22,000,000 và tiền mặt 296,000,000 (tổng 590,000,000), trong khi hai ngân hàng Hà Lan, ING và Rabo Merchant Bank, góp 117,500,000 tiền mặt — khoảng 18 phần trăm vốn — và không tham gia quản lý.

Thỏa thuận phân bổ 98 phần trăm thu nhập hoạt động cho các ngân hàng về mặt thuế, nhưng thu nhập này được tính sau các khoản khấu hao khổng lồ trên những máy bay đã hết khấu hao thuế, nên thu nhập chịu thuế của ngân hàng vượt xa số tiền thực nhận. Thực tế ngân hàng chỉ được hoàn lại 117,500,000 theo lịch cố định tám năm với lãi suất 9.03587 phần trăm (8.53587 phần trăm trong một số trường hợp), được bảo đảm chặt chẽ, và chỉ có thể tăng nhẹ nếu lợi nhuận bất ngờ cao. Năm 2001 IRS phân bổ lại khoảng 310,000,000 thu nhập và truy thu 62,212,010. Tòa sơ thẩm xử cho người nộp thuế (342 F. Supp. 2d 94, 2004), nhưng Tòa khu vực 2 đã đảo ngược (459 F.3d 220, 2006): các ngân hàng không có lợi ích thực chất trong thành bại của công ty hợp danh, quyền lợi của họ về bản chất là khoản tài trợ có bảo đảm, phần giống vốn chủ sở hữu chỉ là hư ảo hoặc không đáng kể. Sau khi hoàn lại, tòa sơ thẩm công nhận tư cách thành viên theo § 704(e)(1) (660 F. Supp. 2d 367, 2009) và tòa phúc thẩm lại đảo ngược (666 F.3d 836, 2012), kèm phạt theo § 6662. Con số tự nó nói lên tất cả: 117,500,000 nhân 9.03587 phần trăm bằng khoảng 10,617,147 mỗi năm — một đường thẳng trên gốc — so với tỷ lệ thu nhập danh nghĩa 98 phần trăm và tỷ lệ vốn chỉ khoảng 18 phần trăm. (初译待校)

*Ghi chú học tập cá nhân; không phải tư vấn thuế. Nguồn: 459 F.3d 220 (2d Cir. 2006); IRC §§ 704(b), 704(e)(1), 6226, 6662.*

## हिन्दी — प्रारंभिक अनुवाद, समीक्षा लंबित (初译待校)

Castle Harbour द्वितीय सर्किट का अग्रणी आधुनिक कथन है कि साझेदारी कर की शुरुआत स्थिति के प्रश्न से होती है: जिसे आय आवंटित की गई है, क्या वह वास्तव में साझेदार है? GECC के पास पूरी तरह मूल्यह्रासित पट्टे वाले विमानों का बेड़ा था। 1993 में, Babcock & Brown की योजना पर 9,000,000 डॉलर देकर, GECC ने आठ वर्षीय Castle Harbour LLC बनाई और 272,000,000 डॉलर के विमान, 22,000,000 डॉलर की किराया प्राप्तियाँ और 296,000,000 डॉलर नकद (कुल 590,000,000) लगाए, जबकि दो डच बैंकों, ING और Rabo Merchant Bank, ने 117,500,000 डॉलर नकद — पूँजी का लगभग 18 प्रतिशत — लगाए और प्रबंधन में कोई भूमिका नहीं निभाई।

परिचालन समझौते ने परिचालन आय का 98 प्रतिशत कर प्रयोजनों के लिए बैंकों को आवंटित किया, परंतु यह आय उन विमानों पर भारी मूल्यह्रास कटौती के बाद गिनी गई थी जिनका कर मूल्यह्रास पहले ही समाप्त हो चुका था, इसलिए बैंकों की करयोग्य आय उनकी वास्तविक प्राप्ति से कहीं अधिक थी। वास्तव में बैंकों को केवल अपने 117,500,000 डॉलर आठ वर्ष की निश्चित अनुसूची में 9.03587 प्रतिशत (कुछ स्थितियों में 8.53587 प्रतिशत) प्रतिफल सहित वापस पाने का अधिकार था, जो मज़बूती से सुरक्षित था और आय अप्रत्याशित रूप से अधिक होने पर ही मामूली वृद्धि संभव थी। 2001 में IRS ने लगभग 310,000,000 डॉलर आय का पुनः आवंटन करके 62,212,010 डॉलर कर लगाया। ज़िला न्यायालय ने करदाता के पक्ष में निर्णय दिया (342 F. Supp. 2d 94, 2004), किंतु द्वितीय सर्किट ने पलट दिया (459 F.3d 220, 2006): बैंकों का साझेदारी की सफलता या विफलता में कोई सार्थक हित नहीं था, उनका हित सारतः सुरक्षित वित्तपोषण था और इक्विटी जैसा दिखने वाला अंश भ्रामक या नगण्य था। रिमांड के बाद ज़िला न्यायालय ने § 704(e)(1) के अंतर्गत साझेदार स्थिति मानी (660 F. Supp. 2d 367, 2009) और अपील न्यायालय ने फिर पलट दिया (666 F.3d 836, 2012), साथ में § 6662 का दंड भी लागू किया। गणित भी यही कहता है: 117,500,000 का 9.03587 प्रतिशत लगभग 10,617,147 डॉलर प्रति वर्ष है — मूलधन पर एक सीधी रेखा — जबकि नाममात्र आय हिस्सा 98 प्रतिशत और पूँजी हिस्सा केवल लगभग 18 प्रतिशत है। (初译待校)

*व्यक्तिगत अध्ययन नोट; कर सलाह नहीं। स्रोत: 459 F.3d 220 (2d Cir. 2006); IRC §§ 704(b), 704(e)(1), 6226, 6662.*

## 补译增量（2026-11-12 03:55 轮）

本节为存量补译：韩／越／印三语各补 2 项中文主文已有、原译文未及的细节——程序链细节组（1993 至 1998 年逐年申报、2001 年两份 FPAA、按第 6226 条缴存后起诉、地区法院八天庭审与 Underhill 法官）与双档算例组（低档回报 8.53587% 对应年回报约 10,029,647 美元、筹划费 9,000,000 美元约占 GECC 一侧出资 590,000,000 美元的 1.53%）。增量只取中文主文已有事实，不新增数字与法条。

### 한국어 (初译待校)

- 절차 보충: 파트너십은 1993년부터 1998년까지 매년 신고했고, IRS는 2001년에 FPAA 두 통을 발송했다. 납세자는 §6226에 따라 세금을 예치한 뒤 소송을 제기했고, 지방법원(Underhill 판사)은 8일간의 재판 끝에 2004년에 판결했다. (初译待校)
- 금액 보충: 낮은 수익률 8.53587%를 적용하면 은행의 연 수익은 약 10,029,647달러이며, Babcock & Brown에 지급한 수수료 9,000,000달러는 GECC 측 출자 590,000,000달러의 약 1.53%이다. (初译待校)

### Tiếng Việt (初译待校)

- Bổ sung thủ tục: công ty hợp danh khai thuế hằng năm từ năm 1993 đến 1998; năm 2001 IRS ban hành hai thông báo FPAA; người nộp thuế đã nộp tiền theo § 6226 rồi khởi kiện; tòa sơ thẩm (thẩm phán Underhill) xét xử trong tám ngày và ra phán quyết năm 2004. (初译待校)
- Bổ sung con số: với mức lãi thấp hơn 8.53587 phần trăm, khoản thu hằng năm của các ngân hàng là khoảng 10,029,647 đô la; khoản phí trả cho Babcock & Brown là 9,000,000 đô la, bằng khoảng 1.53 phần trăm số vốn góp 590,000,000 đô la của phía GECC. (初译待校)

### हिन्दी (初译待校)

- प्रक्रिया पूरक: साझेदारी ने 1993 से 1998 तक हर वर्ष रिटर्न दाखिल किया; 2001 में IRS ने दो FPAA जारी किए; करदाता ने § 6226 के तहत राशि जमा करके मुकदमा किया; ज़िला न्यायालय (न्यायाधीश Underhill) ने आठ दिन की सुनवाई के बाद 2004 में निर्णय दिया। (初译待校)
- राशि पूरक: निचली दर 8.53587 प्रतिशत पर बैंकों का वार्षिक प्रतिफल लगभग 10,029,647 डॉलर बनता है; Babcock & Brown को दी गई फ़ीस 9,000,000 डॉलर GECC पक्ष के 590,000,000 डॉलर अंशदान का लगभग 1.53 प्रतिशत है। (初译待校)
