# Black & Decker 案：或然负债庇护与全有全无检验案例分析

这篇讲什么：
- The Black & Decker Corporation v. United States, 436 F.3d 431 (4th Cir. 2006)，2006 年 2 月 2 日第四巡回上诉法院判决（下级审：Black & Decker Corp. v. United States, 340 F. Supp. 2d 621 (D. Md. 2004)）。引证以判决原文为准：本案是第四巡回、436 F.3d 431，市场上偶见的「436 F.3d 1325、联邦巡回」系误植，勿混——联邦巡回的那一案是同年 7 月的 Coltec，见文末对照。
- 与仓内《Coltec 案》同属或然负债庇护（contingent liability shelter）家族：把或然负债转移进子公司、利用第 357(c)(3) 与第 358(d)(2) 条的例外不调减股票基数，再低价卖股造出巨额资本损失。两案同年、同结构、不同巡回、不同程序结局，是 REG/TCP 里最值得成对背的一组。
- 按案例分析结构走：事实与数字、争点、判决、推理（条文层＋虚假交易层）、与 Coltec 对照、今天怎么用。事实经第四巡回判决原文回核。

### English

What this article covers:
- The Black & Decker Corporation v. United States, 436 F.3d 431 (4th Cir. 2006), decided February 2, 2006 (district court: 340 F. Supp. 2d 621 (D. Md. 2004)). The citation follows the opinion itself — Fourth Circuit, 436 F.3d 431; the Federal Circuit contingent-liability case of the same year is Coltec, decided in July.
- Same shelter family as this repository's Coltec note: contingent liabilities moved into a subsidiary, §§ 357(c)(3) and 358(d)(2) invoked to avoid a stock-basis reduction, then a cheap stock sale manufacturing a huge capital loss. The pair is best studied together: same structure, different circuit, different procedural outcome.

### Español

Lo que trata este artículo:
- The Black & Decker Corporation v. United States, 436 F.3d 431 (4th Cir. 2006), sentencia del Cuarto Circuito del 2 de febrero de 2006 (instancia inferior: 340 F. Supp. 2d 621 (D. Md. 2004)). La cita sigue el texto de la propia sentencia.
- Misma familia de refugios que el caso Coltec de este repositorio: pasivos contingentes trasladados a una filial, invocación de los §§ 357(c)(3) y 358(d)(2) para no reducir la base accionaria y venta barata de las acciones para fabricar una pérdida de capital enorme; el resultado procesal, sin embargo, fue distinto.

### 한국어 (초역, 원어민 감수 대기)

이 글에서 다루는 내용:
- The Black & Decker Corporation v. United States, 436 F.3d 431 (4th Cir. 2006), 2006년 2월 2일 제4순회법원 판결(하급심: 340 F. Supp. 2d 621 (D. Md. 2004)). 인용은 판결 원문을 따릅니다.
- 본 창고의 Coltec 사건과 같은 우발부채 셸터 가족입니다. 우발부채를 자회사로 옮기고 §357(c)(3)·§358(d)(2) 예외로 주식 원가 감액을 피한 뒤 주식을 헐값에 팔아 거액의 자본손실을 만드는 구조이며, 절차적 결말은 Coltec과 달랐습니다.

### Tiếng Việt (bản dịch sơ bộ, chờ người bản ngữ hiệu đính)

Bài viết này nói về:
- The Black & Decker Corporation v. United States, 436 F.3d 431 (4th Cir. 2006), phán quyết ngày 2 tháng 2 năm 2006 của Tòa phúc thẩm Vòng 4 (cấp dưới: 340 F. Supp. 2d 621 (D. Md. 2004)). Trích dẫn theo chính bản án.
- Cùng họ «hầm trú» nợ dự phòng với vụ Coltec trong kho này: chuyển nợ dự phòng vào công ty con, viện dẫn ngoại lệ Điều 357(c)(3) và 358(d)(2) để không giảm cơ sở cổ phiếu, rồi bán rẻ cổ phiếu để tạo khoản lỗ vốn khổng lồ; kết cục thủ tục lại khác Coltec.

### हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

यह लेख इन बातों पर है:
- The Black & Decker Corporation v. United States, 436 F.3d 431 (4th Cir. 2006), चौथे सर्किट का 2 फ़रवरी 2006 का निर्णय (निचली अदालत: 340 F. Supp. 2d 621 (D. Md. 2004))। उद्धरण स्वयं निर्णय के अनुसार है।
- यह इस भंडार के Coltec मामले के ही आकस्मिक-देनदारी आश्रय परिवार का मामला है: आकस्मिक देनदारियाँ सहायक कंपनी में डालो, §§ 357(c)(3) व 358(d)(2) के अपवाद से शेयर-आधार में कटौती टालो, फिर शेयर सस्ते में बेचकर विशाल पूँजी हानि बना लो; किंतु प्रक्रियात्मक परिणाम Coltec से भिन्न रहा।

---

## 一、事实与数字

### 中文
Black & Decker（下称 B&D）是大型电动工具与家居制造商，为数千名现职与退休员工提供医疗与牙科福利。这些未来医疗索赔的总额只能精算估计、无法确定，就是本案的或然负债——员工医疗索赔类负债，这一点与 Coltec 的石棉诉讼负债同类不同源。

1998 年，B&D 出售三项业务，实现近 303,000,000 美元资本利得（判决原文「nearly $303 million」，量级以原文为准）。为对冲这笔利得，B&D 采用会计师事务所 Deloitte & Touche 设计并向约 30 家公司客户推介的或然负债交易，落在子公司 Black & Decker Healthcare Management Inc.（BDHMI）上，两步落地：

1. **第一步（1998 年 11 月 25 日）**：B&D 及其加拿大子公司向 BDHMI 支付约 561,000,000 美元现金（资金系向银行借入的 30 天短期借款），换取 BDHMI 的 10,000 股 C 系列优先股；BDHMI 同时承接 B&D 与加拿大子公司 1999 至 2007 年的未来医疗福利索赔负债，精算现值估计约 560,000,000 美元。注意协议明文：承接不构成法定免责（defeasance）或债务更新（novation），B&D 对底层福利负债仍负首要责任。
2. **第二步（1998 年 12 月 29 日）**：B&D 与加拿大子公司把这 10,000 股以 1,000,000 美元卖给一只无关第三方信托。同日 BDHMI 承诺向 B&D 一方贷出约 564,000,000 美元，分期偿还的现金流正好设计为给 BDHMI 留足支付陆续到期医疗索赔的资金。

报税口径与 Coltec 如出一辙：B&D 主张股票基数就是付出的 561,000,000 美元现金，不因 BDHMI 承接负债而调减，于是 1,000,000 美元售价对 561,000,000 美元基数，造出 560,000,000 美元资本损失（561,000,000 − 1,000,000 ＝ 560,000,000，本地复算勾稽），不仅吞掉当年近 303,000,000 美元利得，还向 1995 至 2000 多个税年申索退税合计约 57,000,000 美元。IRS 拒绝退税并提出反诉，追索税款、利息与罚款合计约 215,000,000 美元量级（判决原文约数，以原文为准）。马里兰联邦地区法院（340 F. Supp. 2d 621）一审：驳回 IRS 的简易判决动议（条文层 IRS 输），却准予 B&D 的简易判决动议——理由是 BDHMI 系为正当经营目的设立、其交易「客观上合理」，故不构成可被否认的虚假交易。IRS 上诉至第四巡回。

### English
Black & Decker, a major power-tool and home-improvement manufacturer, provided medical and dental benefits to thousands of current and retired employees; the aggregate future health-benefit claims — estimable but not predictable — were the contingent liability. In 1998 it realized nearly $303 million of capital gains from selling three businesses and, to shelter them, executed a contingent-liability transaction designed by Deloitte & Touche and marketed to some 30 corporate clients, run through its subsidiary BDHMI. Phase One (November 25, 1998): B&D and its Canadian subsidiary paid BDHMI roughly $561 million in cash (borrowed from banks for 30 days) for 10,000 shares of BDHMI Series C preferred stock, while BDHMI assumed their 1999–2007 future health-benefit claims, actuarially estimated at a present value of about $560 million; the agreement expressly provided no legal defeasance or novation, so B&D remained primarily liable. Phase Two (December 29, 1998): the shares were sold for $1 million to an unrelated third-party trust, and BDHMI agreed to lend roughly $564 million back, with installments sized to fund the claims as they came due. B&D claimed a $561 million stock basis with no reduction for the assumed liabilities, producing a $560 million capital loss ($561 million − $1 million, recomputed locally) that absorbed the year's gains and supported refund claims of about $57 million across the 1995–2000 tax years. The IRS refused the refunds and counterclaimed for roughly $215 million in tax, interest, and penalties (approximate figures, per the opinion). The District of Maryland (340 F. Supp. 2d 621 (2004)) denied the IRS's summary-judgment motion but granted B&D's, reasoning that BDHMI was constituted for a valid business purpose and its transactions were objectively reasonable. The IRS appealed to the Fourth Circuit.

### Español
Black & Decker, gran fabricante de herramientas eléctricas, ofrecía prestaciones médicas y dentales a miles de empleados y jubilados; el total de futuras reclamaciones sanitarias —estimable pero impredecible— era el pasivo contingente. En 1998 realizó casi 303 millones de dólares en ganancias de capital por la venta de tres negocios y, para protegerlas, ejecutó la operación de pasivos contingentes diseñada por Deloitte & Touche y ofrecida a unos 30 clientes, a través de su filial BDHMI. Fase uno (25 de noviembre de 1998): B&D y su filial canadiense pagaron a BDHMI unos 561 millones en efectivo (tomados a préstamo bancario por 30 días) por 10.000 acciones preferentes serie C, mientras BDHMI asumía las reclamaciones sanitarias futuras de 1999 a 2007, estimadas actuarialmente en un valor presente de unos 560 millones; el acuerdo decía expresamente que no había extinción legal ni novación, de modo que B&D seguía siendo el obligado principal. Fase dos (29 de diciembre de 1998): las acciones se vendieron por 1 millón a un fideicomiso tercero no vinculado, y BDHMI se comprometió a prestar de vuelta unos 564 millones, con cuotas calculadas para financiar las reclamaciones a su vencimiento. B&D sostuvo una base de 561 millones sin reducción por los pasivos asumidos, lo que produjo una pérdida de capital de 560 millones (561 − 1, recalculado localmente) que absorbió las ganancias del año y sostuvo devoluciones de unos 57 millones para los años 1995–2000. El IRS denegó las devoluciones y reconvino por unos 215 millones entre impuesto, intereses y sanciones (cifras aproximadas, según la sentencia). El tribunal de distrito de Maryland (340 F. Supp. 2d 621 (2004)) denegó la moción del IRS pero estimó la de B&D, por entender que BDHMI se constituyó con un propósito empresarial válido y sus operaciones eran objetivamente razonables. El IRS apeló al Cuarto Circuito.

### 한국어 (초역, 원어민 감수 대기)

Black & Decker는 대형 전동공구 제조사로 수천 명의 현직·퇴직 직원에게 의료·치과 혜택을 제공했습니다. 장래 의료 청구 총액 — 추정은 가능하나 예측은 불가능한 금액 — 이 바로 우발부채였습니다. 1998년 세 사업 매각으로 약 303,000,000달러의 자본이익을 실현한 뒤, 이를 가리기 위해 Deloitte & Touche가 설계해 약 30개 기업 고객에게 판 우발부채 거래를 자회사 BDHMI를 통해 실행했습니다. 1단계(1998년 11월 25일): B&D와 캐나다 자회사가 은행에서 30일간 빌린 현금 약 561,000,000달러를 BDHMI에 지급하고 C 시리즈 우선주 10,000주를 받는 한편, BDHMI는 1999–2007년 장래 의료급여 청구를 인수했습니다(보험수리적 현가 추정 약 560,000,000달러). 합의서에는 법적 면책(defeasance)도 채무갱신(novation)도 없다고 명시돼 B&D가 여전히 1차 책임을 졌습니다. 2단계(1998년 12월 29일): 그 주식을 무관계 제3자 신탁에 1,000,000달러에 매각했고, BDHMI는 약 564,000,000달러를 되빌려주기로 했으며 상환 일정은 청구가 도래할 때 지급할 자금에 맞춰 설계됐습니다. B&D는 주식 원가를 561,000,000달러로 주장하며 인수 부채만큼 줄이지 않았고, 그 결과 자본손실 560,000,000달러(561,000,000 − 1,000,000, 로컬 재계산)가 생겨 그해 이익을 흡수하고 1995–2000 과세연도에 대한 약 57,000,000달러의 환급 청구를 뒷받침했습니다. IRS는 환급을 거부하고 세금·이자·가산세 합계 약 215,000,000달러 규모로 반소했습니다(판결 원문의 약수 기준). 메릴랜드 연방지방법원(340 F. Supp. 2d 621 (2004))은 IRS의 약식판결 신청은 기각했지만 B&D의 신청은 인용했습니다 — BDHMI가 정당한 사업 목적으로 설립됐고 그 거래가 객관적으로 합리적이라는 이유였습니다. IRS가 제4순회법원에 항소했습니다.

### Tiếng Việt (bản dịch sơ bộ, chờ người bản ngữ hiệu đính)

Black & Decker, nhà sản xuất dụng cụ điện lớn, cung cấp phúc lợi y tế và nha khoa cho hàng nghìn nhân viên và người nghỉ hưu; tổng các yêu cầu phúc lợi sức khỏe tương lai — ước tính được nhưng không dự đoán chắc được — chính là khoản nợ dự phòng. Năm 1998, công ty ghi nhận gần 303.000.000 đô la lãi vốn từ việc bán ba mảng kinh doanh và, để che chắn khoản lãi này, thực hiện giao dịch nợ dự phòng do Deloitte & Touche thiết kế và chào bán cho khoảng 30 khách hàng doanh nghiệp, chạy qua công ty con BDHMI. Giai đoạn một (25/11/1998): B&D và công ty con Canada trả cho BDHMI khoảng 561.000.000 đô la tiền mặt (vay ngân hàng 30 ngày) để lấy 10.000 cổ phiếu ưu đãi Series C, đồng thời BDHMI gánh các yêu cầu phúc lợi sức khỏe tương lai 1999–2007, ước tính theo tính toán bảo hiểm với giá trị hiện tại khoảng 560.000.000 đô la; thỏa thuận ghi rõ không có miễn trừ pháp lý (defeasance) cũng không có thay thế nghĩa vụ (novation), nên B&D vẫn chịu trách nhiệm chính. Giai đoạn hai (29/12/1998): số cổ phiếu được bán với giá 1.000.000 đô la cho một quỹ tín thác bên thứ ba không liên quan, và BDHMI cam kết cho vay ngược lại khoảng 564.000.000 đô la, với lịch trả góp được thiết kế vừa đủ để chi trả các yêu cầu khi đến hạn. B&D khẳng định cơ sở cổ phiếu là 561.000.000 đô la, không trừ khoản nợ BDHMI đã gánh, tạo ra khoản lỗ vốn 560.000.000 đô la (561.000.000 − 1.000.000, tính lại tại chỗ), hấp thụ lãi của năm đó và đỡ các yêu cầu hoàn thuế khoảng 57.000.000 đô la cho các năm 1995–2000. IRS từ chối hoàn thuế và kiện ngược đòi tổng cộng khoảng 215.000.000 đô la tiền thuế, lãi và phạt (con số gần đúng theo bản án). Tòa liên bang khu vực Maryland (340 F. Supp. 2d 621 (2004)) bác đơn xin phán quyết tóm tắt của IRS nhưng chấp nhận đơn của B&D, với lý do BDHMI được lập vì mục đích kinh doanh hợp lệ và các giao dịch của nó khách quan là hợp lý. IRS kháng cáo lên Tòa Vòng 4.

### हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

Black & Decker, एक बड़ी पावर-टूल निर्माता कंपनी, हज़ारों वर्तमान व सेवानिवृत्त कर्मचारियों को चिकित्सा व दंत लाभ देती थी; भविष्य के स्वास्थ्य-दावों का योग — जिसका अनुमान संभव था, भविष्यवाणी नहीं — ही आकस्मिक देनदारी था। 1998 में तीन व्यवसाय बेचकर उसने लगभग 303,000,000 डॉलर पूँजी लाभ कमाया और उसे बचाने के लिए Deloitte & Touche द्वारा रचित व लगभग 30 कॉर्पोरेट ग्राहकों को बेची गई आकस्मिक-देनदारी योजना अपनी सहायक BDHMI के माध्यम से चलाई। चरण एक (25 नवंबर 1998): B&D व उसकी कनाडाई सहायक ने BDHMI को लगभग 561,000,000 डॉलर नकद (बैंकों से 30 दिन का ऋण) देकर उसके 10,000 सीरीज़ C अधिमान शेयर लिए, और BDHMI ने 1999–2007 के भविष्य के स्वास्थ्य-दावे अपने ऊपर लिए, जिनका बीमांकिक वर्तमान मूल्य लगभग 560,000,000 डॉलर आँका गया; करार में स्पष्ट था कि न कानूनी मुक्ति (defeasance) है न दायित्व-नवीनीकरण (novation), अतः B&D ही मुख्य रूप से उत्तरदायी रहा। चरण दो (29 दिसंबर 1998): वे शेयर 1,000,000 डॉलर में एक असंबद्ध तृतीय-पक्ष ट्रस्ट को बेचे गए, और BDHMI ने लगभग 564,000,000 डॉलर वापस उधार देने का वचन दिया, जिसकी किस्तें दावों के भुगतान हेतु पर्याप्त नकदी देने के अनुरूप बनाई गईं। B&D ने शेयर-आधार 561,000,000 डॉलर माना और ली गई देनदारियों से उसे घटाया नहीं, जिससे 560,000,000 डॉलर की पूँजी हानि बनी (561,000,000 − 1,000,000, स्थानीय पुनर्गणना), जिसने उस वर्ष का लाभ सोख लिया और 1995–2000 कर-वर्षों के लिए लगभग 57,000,000 डॉलर के रिफ़ंड दावों का आधार बनी। IRS ने रिफ़ंड ठुकराया और कर, ब्याज व दंड मिलाकर लगभग 215,000,000 डॉलर के क्रम का प्रतिदावा किया (निर्णय के अनुमानित आँकड़े)। मैरीलैंड ज़िला न्यायालय (340 F. Supp. 2d 621 (2004)) ने IRS का संक्षिप्त-निर्णय प्रस्ताव ठुकराया किंतु B&D का प्रस्ताव मान लिया — BDHMI वैध व्यावसायिक उद्देश्य से बनी थी और उसके लेन-देन वस्तुगत रूप से उचित थे। IRS ने चौथे सर्किट में अपील की।

---

## 二、争点

### 中文
争点仍是两层，但比 Coltec 多一条岔路。条文层：第一，第 357(c)(3) 条的例外是否覆盖这批医疗福利或然负债，从而依第 358(d)(2) 条不把承接负债当作「收到的金钱」调减基数；第二，IRS 的进阶主张——就算例外成立，第 357(b)(1) 条的反滥用条款（缺乏真实经营目的时承接负债视为收到金钱）能否穿透到第 358 条的基数计算，即第 357(b) 与第 358(d)(2) 之间是否存在通道。原则层：条文走通之后，这笔交易在虚假交易／经济实质原则下是否整体站得住——而第四巡回对此有一套自家判例 Rice's Toyota World, Inc. v. Commissioner, 752 F.2d 89 (4th Cir. 1985) 的双要件合取检验，且该检验的适用是事实问题，能否在简易判决阶段了结。

### English
The issues again sit on two levels, with one extra fork. Textual level: first, whether the § 357(c)(3) exception covers these health-benefit contingent liabilities so that, under § 358(d)(2), the assumption is not "money received" reducing basis; second, the IRS's fallback — whether § 357(b)(1)'s anti-abuse rule can reach into § 358's basis computation at all, i.e., whether any bridge runs between § 357(b) and § 358(d)(2). Doctrinal level: whether the transaction survives the sham-transaction / economic-substance doctrine, which in the Fourth Circuit means the conjunctive two-prong test of Rice's Toyota World, Inc. v. Commissioner, 752 F.2d 89 (4th Cir. 1985) — and whether that fact-laden test can be resolved on summary judgment at all.

### Español
Las cuestiones ocupan dos niveles, con una bifurcación adicional. Nivel textual: primero, si la excepción del § 357(c)(3) cubre estos pasivos contingentes sanitarios y, por el § 358(d)(2), la asunción no cuenta como «dinero recibido» que reduzca la base; segundo, el argumento subsidiario del IRS: si la regla antiabuso del § 357(b)(1) puede alcanzar el cálculo de base del § 358. Nivel doctrinal: si la operación sobrevive a la doctrina de la transacción simulada, que en el Cuarto Circuito es la prueba conjunta de dos requisitos de Rice's Toyota World, Inc. v. Commissioner, 752 F.2d 89 (4th Cir. 1985), y si esa prueba, cargada de hechos, puede resolverse en juicio sumario.

### 한국어 (초역, 원어민 감수 대기)

쟁점은 두 층이며 갈림길이 하나 더 있습니다. 문구 층: 첫째, §357(c)(3) 예외가 이 의료급여 우발부채를 포괄해 §358(d)(2)에 따라 인수 부채가 원가를 줄이는 「받은 금전」으로 취급되지 않는지; 둘째, IRS의 예비 주장 — §357(b)(1)의 남용방지 규정이 §358의 원가 계산까지 도달할 수 있는지. 원칙 층: 이 거래가 허위거래·경제 실질 원칙을 견디는지 — 제4순회에서는 Rice's Toyota World, Inc. v. Commissioner, 752 F.2d 89 (4th Cir. 1985)의 동시충족(두 요건 모두 충족) 검사가 적용되며, 사실 판단이 무거운 이 검사를 약식판결 단계에서 끝낼 수 있는지가 문제됐습니다.

### Tiếng Việt (bản dịch sơ bộ, chờ người bản ngữ hiệu đính)

Vấn đề vẫn ở hai tầng, thêm một ngã rẽ. Tầng văn bản: thứ nhất, ngoại lệ Điều 357(c)(3) có bao phủ các khoản nợ dự phòng phúc lợi sức khỏe này không, để theo Điều 358(d)(2) việc gánh nợ không bị coi là «tiền nhận được» làm giảm cơ sở; thứ hai, lập luận dự phòng của IRS — quy tắc chống lạm dụng Điều 357(b)(1) có vươn tới phép tính cơ sở của Điều 358 hay không. Tầng nguyên tắc: giao dịch có đứng vững trước học thuyết giao dịch giả tạo hay không — ở Vòng 4 đó là phép thử hai yếu tố mang tính đồng thời (conjunctive) của Rice's Toyota World, Inc. v. Commissioner, 752 F.2d 89 (4th Cir. 1985) — và phép thử nặng tính thực tế ấy có thể được quyết trong thủ tục phán quyết tóm tắt hay không.

### हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

विवाद फिर दो स्तरों पर है, एक अतिरिक्त मोड़ के साथ। शाब्दिक स्तर: पहला, क्या § 357(c)(3) का अपवाद इन स्वास्थ्य-लाभ आकस्मिक देनदारियों को घेरता है जिससे § 358(d)(2) के तहत अधिग्रहण «प्राप्त धन» मानकर आधार न घटे; दूसरा, IRS का वैकल्पिक तर्क — क्या § 357(b)(1) का दुरुपयोग-रोधी नियम § 358 की आधार-गणना तक पहुँच सकता है। सिद्धांत स्तर: क्या लेन-देन छद्म-लेनदेन सिद्धांत के आगे टिकता है — चौथे सर्किट में यह Rice's Toyota World, Inc. v. Commissioner, 752 F.2d 89 (4th Cir. 1985) की संयुक्त (conjunctive) दो-शर्त परीक्षा है — और क्या तथ्य-भारी यह परीक्षा संक्षिप्त निर्णय में ही निपटाई जा सकती है।

---

## 三、判决

### 中文
2006 年 2 月 2 日，第四巡回部分维持、部分撤销、发回重审（affirmed in part, reversed in part, and remanded）：

- **条文层，B&D 赢、IRS 的简易判决被驳回得对。** 法院逐项拆解：这批医疗负债若由 B&D 自己支付本可产生扣除，落入第 357(c)(3) 条例外的明文范围；IRS 援引立法史主张例外只保护「资产与负债一并转移」的典型交易，法院不采——明文没有这个限制，不必用立法史给明文加条件。IRS 的「功能性双重扣除」政策主张同样未被采纳：实际申报扣除的是单独报税的 BDHMI，不是 B&D，在现有记录下没有理由把两个独立纳税主体合并看待。至于第 357(b) 通道说，法院双路封堵：其一，第 357(b)(1) 条通篇只指向「第 351 条的目的」，而第 351 条管的是利得损失的**确认**、第 358 条管的是**基数计算**，两者是不同概念，条文与 Reg. § 1.357-1(c) 都只谈确认不谈基数；其二，第 358(d)(2) 条引用的只是第 357(c)(3) 款本身，并未连带引用第 357(c)(1)、(2) 款，不能因为第 357(b) 触发了第 357(c)(2) 的关闭，就顺手把第 358(d)(2) 的例外也关掉。结论：条文不要求调减基数。
- **原则层，一审判错了、必须发回开庭审。** 地区法院把 Rice's Toyota 的客观要件读偏了：它看的是 BDHMI 这家公司整体有没有真实经营活动（有雇员、有资产、到期付索赔），而判例要求看的是**被争议的那一笔交易本身**在税外有没有合理的利润可能。B&D 在简易判决阶段曾自认避税是设立 BDHMI 的唯一动机（主观要件视为满足仅限于该动议），但客观要件上 IRS 交出了四位专家（经济学与福利咨询）的报告，主张这笔交易对 B&D 的唯一实质价值就是节税，B&D 亦有自家专家反驳——专家可信度之争不能在简易判决里裁，只能开庭由事实审理者称量。双要件是否**同时**成立，留待审判认定。

一句话定位：本案没有判 B&D 输，它判的是「这笔损失的生死不能在纸面上定，要开庭用事实定」。

### English
On February 2, 2006, the Fourth Circuit affirmed in part, reversed in part, and remanded. On the text, B&D won: the health-benefit liabilities fall within the plain terms of § 357(c)(3) — had B&D paid them itself, the payments would have given rise to a deduction — so under § 358(d)(2) the assumption is not money received and no basis reduction is required. The court rejected the IRS's legislative-history argument (the statute's plain language contains no "assets transferred together with liabilities" limitation) and its functional-double-deduction policy argument (BDHMI, a separate taxpayer, took the deductions, not B&D). It also closed both § 357(b) bridges: § 357(b)(1) speaks only to the "purposes of section 351," which govern gain-or-loss recognition, whereas § 358 governs basis computation — distinct concepts, confirmed by Reg. § 1.357-1(c), which addresses recognition only; and § 358(d)(2) incorporates § 357(c)(3) alone, not §§ 357(c)(1)–(2), so triggering § 357(b) does not switch off the § 358(d)(2) exception. On doctrine, the district court had misapplied Rice's Toyota: the objective prong examines the specific disputed transaction, not BDHMI's general business activities (employees, assets, paying claims), and the competing expert evidence on whether the transaction held any reasonable possibility of profit apart from tax created a genuine fact issue that credibility assessment at trial must resolve. The court decided no one's ultimate liability — it held only that the loss could not be sustained on summary judgment.

### Español
El 2 de febrero de 2006, el Cuarto Circuito confirmó en parte, revocó en parte y devolvió el caso. En el texto ganó B&D: los pasivos sanitarios entran en los términos claros del § 357(c)(3) —si B&D los hubiera pagado, el pago habría generado una deducción—, de modo que, por el § 358(d)(2), la asunción no es dinero recibido y no hay reducción de base. El tribunal rechazó el argumento de historia legislativa del IRS (el texto no contiene la limitación de «activos transferidos junto con pasivos») y el de doble deducción funcional (quien deducía era BDHMI, contribuyente separado). También cerró ambos puentes del § 357(b): el § 357(b)(1) se refiere solo a los «fines de la sección 351», que gobiernan el reconocimiento de ganancias y pérdidas, mientras el § 358 gobierna el cálculo de la base —conceptos distintos, como confirma Reg. § 1.357-1(c)—; y el § 358(d)(2) incorpora solo el § 357(c)(3), no los apartados (1) y (2), así que activar el § 357(b) no apaga la excepción. En la doctrina, el tribunal de distrito aplicó mal Rice's Toyota: el requisito objetivo examina la transacción concreta en disputa, no las actividades generales de BDHMI, y los informes periciales enfrentados sobre si existía una posibilidad razonable de beneficio al margen del impuesto creaban una cuestión de hecho genuina para el juicio. Nadie ganó el fondo: solo se decidió que la pérdida no podía sostenerse en juicio sumario.

### 한국어 (초역, 원어민 감수 대기)

2006년 2월 2일, 제4순회법원은 일부 확정, 일부 취소, 환송 판결을 내렸습니다. 문구에서는 B&D가 이겼습니다. 의료급여 부채는 §357(c)(3) 예외의 명문에 들어갑니다 — B&D가 스스로 지급했더라면 공제가 발생했을 부채이기 때문입니다. 따라서 §358(d)(2)에 따라 인수는 받은 금전으로 취급되지 않고 원가 감액도 요구되지 않습니다. 법원은 IRS의 입법사 주장(조문 명문에 「자산과 부채를 함께 이전」하는 거래로 한정한다는 제한이 없음)과 기능적 이중공제 주장(실제로 공제를 받은 것은 별도 납세자인 BDHMI)을 받아들이지 않았습니다. §357(b)의 두 다리도 모두 막았습니다. §357(b)(1)은 「§351의 목적」만을 가리키는데 §351은 이익·손실의 인식을, §358은 원가 계산을 다스리는 서로 다른 개념이며 Reg. § 1.357-1(c)도 인식만을 말합니다. 또 §358(d)(2)가 끌어오는 것은 §357(c)(3) 하나뿐이라 §357(b)가 발동돼도 그 예외가 꺼지지 않습니다. 원칙 층에서는 지방법원이 Rice's Toyota를 잘못 적용했습니다. 객관 요건이 보는 것은 BDHMI의 일반 사업 활동이 아니라 다투어지는 바로 그 거래 자체이며, 세금 외 합리적 이익 가능성에 대한 전문가 의견이 맞선 이상 사실심에서 심리해야 할 쟁점이 남아 있었습니다. 본안의 승패는 정해지지 않았고, 약식판결로 이 손실을 유지할 수 없다는 것만 정해졌습니다.

### Tiếng Việt (bản dịch sơ bộ, chờ người bản ngữ hiệu đính)

Ngày 2 tháng 2 năm 2006, Tòa Vòng 4 giữ nguyên một phần, hủy một phần và gửi trả vụ án. Ở tầng văn bản, B&D thắng: các khoản nợ phúc lợi sức khỏe rơi vào văn bản rõ ràng của Điều 357(c)(3) — nếu B&D tự chi trả, khoản chi đó sẽ làm phát sinh khấu trừ — nên theo Điều 358(d)(2), việc gánh nợ không phải là tiền nhận được và không phải giảm cơ sở. Tòa bác lập luận lịch sử lập pháp của IRS (văn bản không chứa giới hạn «tài sản chuyển giao cùng với nợ») và lập luận «khấu trừ kép về chức năng» (bên khấu trừ thực tế là BDHMI, một chủ thể thuế riêng). Tòa cũng đóng cả hai cây cầu của Điều 357(b): Điều 357(b)(1) chỉ nói tới «mục đích của Điều 351», vốn điều chỉnh việc ghi nhận lãi/lỗ, trong khi Điều 358 điều chỉnh phép tính cơ sở — hai khái niệm khác nhau, như Reg. § 1.357-1(c) xác nhận; và Điều 358(d)(2) chỉ viện dẫn Điều 357(c)(3), không viện dẫn khoản (1) và (2), nên việc kích hoạt Điều 357(b) không tắt được ngoại lệ. Ở tầng nguyên tắc, tòa cấp dưới đã áp dụng sai Rice's Toyota: yếu tố khách quan xét chính giao dịch đang tranh chấp, không xét hoạt động kinh doanh chung của BDHMI, và các báo cáo chuyên gia đối nghịch nhau về khả năng lợi nhuận hợp lý ngoài thuế đã tạo ra một vấn đề thực tế thực sự phải đưa ra xét xử. Tòa không quyết ai thắng cuối cùng — chỉ quyết rằng khoản lỗ này không thể được giữ lại bằng phán quyết tóm tắt.

### हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

2 फ़रवरी 2006 को चौथे सर्किट ने निर्णय को आंशिक रूप से बरकरार रखा, आंशिक रूप से पलटा और मामला वापस भेजा। शब्दों पर B&D जीता: स्वास्थ्य-देनदारियाँ § 357(c)(3) के स्पष्ट पाठ में आती हैं — यदि B&D स्वयं भुगतान करता तो कटौती उत्पन्न होती — अतः § 358(d)(2) के तहत अधिग्रहण प्राप्त धन नहीं है और आधार घटाना आवश्यक नहीं। न्यायालय ने IRS का विधायी-इतिहास तर्क (पाठ में «संपत्ति सहित देनदारी» की कोई सीमा नहीं) व कार्यात्मक दोहरी कटौती का तर्क (कटौती वास्तव में BDHMI ने ली थी, जो अलग करदाता है) ठुकरा दिया। § 357(b) के दोनों सेतु भी बंद कर दिए: § 357(b)(1) केवल «धारा 351 के प्रयोजनों» की बात करता है, जो लाभ-हानि की मान्यता को नियंत्रित करते हैं, जबकि § 358 आधार-गणना को — अलग अवधारणाएँ, जैसा Reg. § 1.357-1(c) भी पुष्टि करता है; और § 358(d)(2) केवल § 357(c)(3) को अपनाता है, उपधारा (1)–(2) को नहीं, अतः § 357(b) के सक्रिय होने से अपवाद बंद नहीं होता। सिद्धांत पर, ज़िला न्यायालय ने Rice's Toyota को ग़लत लगाया: वस्तुगत शर्त विवादित लेन-देन विशेष को देखती है, BDHMI की सामान्य गतिविधियों को नहीं, और कर के अलावा उचित लाभ-संभावना पर विशेषज्ञों की परस्पर विरोधी रिपोर्टों ने वास्तविक तथ्य-विवाद खड़ा कर दिया था, जिसका निर्णय मुक़दमे में होना था। अंतिम जीत किसी की नहीं हुई — बस इतना तय हुआ कि यह हानि संक्षिप्त निर्णय से नहीं बच सकती।

---

## 四、推理核心：全有全无的合取检验

### 中文
本案在备考上的分量，全在 Rice's Toyota 双要件检验的**合取（conjunctive）结构**上。第四巡回自 Rice's Toyota 以来一贯口径：认定一笔交易为虚假（sham），必须**同时**找到两件事——

1. **主观要件**：纳税人进入交易除取得税收利益外，没有任何经营目的；
2. **客观要件**：交易没有经济实质，因为除税收利益外不存在合理的利润可能（no reasonable possibility of a profit）。

两件缺一不可，这就是所谓「全有全无」（all-or-nothing）：只要有一件不成立，交易整体就被尊重，法院不能像拆零件一样只否认其中「没实质的那一半」再按重构征税。判决还点明两要件其实指向同一个问题——交易在税外到底有没有经济实质，主观查动机、客观查利润可能，证据上互相照明：纳税人单凭「我主观上相信能赚钱」的自述，扛不住客观上必亏的强证据。

这一结构与地区法院的错误正好构成对照题：地区法院把客观要件偷换成「设立的子公司有没有在真实经营」，等于把**主体**的真实性当成了**交易**的实质——Moline Properties, Inc. v. Commissioner, 319 U.S. 436 (1943) 管的是公司主体能否被无视，Rice's Toyota 管的是股东与受控公司之间的具体交易能否被无视，两者不是一回事，子公司是真公司，不等于它参与的这笔交易就有实质。

### English
The exam weight of this case sits in the conjunctive structure of the Rice's Toyota test. To treat a transaction as a sham, the Fourth Circuit requires both findings together: (1) subjectively, the taxpayer was motivated by no business purpose other than obtaining tax benefits; and (2) objectively, the transaction has no economic substance because no reasonable possibility of profit exists apart from tax. Missing either prong, the transaction is respected as a whole — the analysis is all-or-nothing, and a court may not salvage half the transaction and tax a judicial rewrite. The two prongs ultimately probe one question — whether the transaction contained economic substance aside from tax — from the subjective and objective sides, so a taxpayer's mere assertion of belief in profit cannot withstand strong objective evidence of loss. The district court's error is the mirror image of the test: it asked whether the subsidiary was genuinely operating (the Moline Properties question of corporate separateness, 319 U.S. 436 (1943)), whereas Rice's Toyota asks whether the specific transaction between shareholder and controlled corporation has substance; a real corporation does not make every transaction it touches real.

### Español
El peso de este caso en el examen está en la estructura conjunta de la prueba de Rice's Toyota: para calificar una operación de simulada deben concurrir dos hallazgos —(1) subjetivamente, el contribuyente no tuvo otro propósito empresarial que el beneficio fiscal, y (2) objetivamente, la operación carece de sustancia económica porque no existe posibilidad razonable de beneficio al margen del impuesto—. Si falta uno, la operación se respeta entera: es un todo o nada, y el tribunal no puede rescatar la mitad y gravar una versión reescrita. Ambos requisitos interrogan en el fondo lo mismo —si la operación tenía sustancia económica aparte del impuesto—, de modo que la mera afirmación subjetiva de creencia en el beneficio no resiste una prueba objetiva fuerte de pérdida. El error del tribunal de distrito fue el reflejo inverso: preguntó si la filial operaba de verdad (la cuestión de Moline Properties, 319 U.S. 436 (1943), sobre la personalidad societaria), cuando Rice's Toyota pregunta si la transacción concreta entre accionista y sociedad controlada tiene sustancia; que la sociedad sea real no hace real cada operación que toca.

### 한국어 (초역, 원어민 감수 대기)

이 사건의 시험상 무게는 Rice's Toyota 검사의 동시충족 구조에 있습니다. 거래를 허위(sham)로 보려면 두 가지가 함께 확인되어야 합니다. (1) 주관 요건: 납세자에게 세제 혜택 외의 사업 목적이 없었을 것, (2) 객관 요건: 세금을 빼면 합리적 이익 가능성이 없어 경제 실질이 없을 것. 하나라도 빠지면 거래는 통째로 존중됩니다 — 이른바 전부 아니면 전무(all-or-nothing)이며, 법원이 절반만 부인하고 재구성 과세할 수는 없습니다. 두 요건은 결국 하나의 질문, 즉 세금 외 경제 실질이 있었는지를 주관과 객관 양쪽에서 묻는 것이어서, 이익을 믿었다는 납세자의 자술만으로는 객관적인 손실 증거를 이기지 못합니다. 지방법원의 오류는 그 거울상입니다. 자회사가 실제로 영업하는지(Moline Properties, 319 U.S. 436 (1943)의 법인격 문제)를 물었지만, Rice's Toyota가 묻는 것은 주주와 지배회사 사이의 바로 그 거래에 실질이 있는지입니다. 진짜 회사라고 그 회사가 닿는 모든 거래가 진짜가 되지는 않습니다.

### Tiếng Việt (bản dịch sơ bộ, chờ người bản ngữ hiệu đính)

Sức nặng thi cử của vụ này nằm ở cấu trúc đồng thời của phép thử Rice's Toyota: để coi một giao dịch là giả tạo (sham), phải có đồng thời hai kết luận — (1) về chủ quan, người nộp thuế không có mục đích kinh doanh nào ngoài lợi ích thuế; và (2) về khách quan, giao dịch không có thực chất kinh tế vì không tồn tại khả năng lợi nhuận hợp lý nào ngoài thuế. Thiếu một trong hai, giao dịch được tôn trọng toàn bộ — theo kiểu «tất cả hoặc không gì cả» (all-or-nothing), và tòa không thể cứu một nửa giao dịch rồi đánh thuế theo một phiên bản viết lại. Hai yếu tố rốt cuộc cùng tra hỏi một câu — giao dịch có thực chất kinh tế ngoài thuế hay không — từ hai phía chủ quan và khách quan, nên lời khẳng định chủ quan thuần túy về niềm tin vào lợi nhuận không chống nổi bằng chứng khách quan mạnh về thua lỗ. Sai lầm của tòa cấp dưới là hình ảnh phản chiếu: tòa hỏi công ty con có thật sự hoạt động hay không (câu hỏi về tư cách pháp nhân của Moline Properties, 319 U.S. 436 (1943)), trong khi Rice's Toyota hỏi giao dịch cụ thể giữa cổ đông và công ty bị kiểm soát có thực chất hay không; công ty là thật không làm cho mọi giao dịch nó chạm vào đều thành thật.

### हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

इस मामले का परीक्षा-भार Rice's Toyota परीक्षा की संयुक्त संरचना में है। किसी लेन-देन को छद्म (sham) कहने के लिए दोनों निष्कर्ष एक साथ चाहिए: (1) व्यक्तिनिष्ठ — करदाता का कर-लाभ के अलावा कोई व्यावसायिक उद्देश्य नहीं था; और (2) वस्तुनिष्ठ — लेन-देन में आर्थिक सार नहीं क्योंकि कर के अलावा उचित लाभ की कोई संभावना नहीं। एक भी शर्त गिरी तो लेन-देन पूरा सम्मानित होता है — यह «सब या कुछ नहीं» (all-or-nothing) विश्लेषण है, न्यायालय आधा लेन-देन बचाकर पुनर्लिखित संस्करण पर कर नहीं लगा सकता। दोनों शर्तें अंततः एक ही प्रश्न पूछती हैं — क्या लेन-देन में कर के अलावा आर्थिक सार था — व्यक्तिनिष्ठ व वस्तुनिष्ठ दोनों ओर से, इसलिए लाभ में विश्वास का केवल दावा मज़बूत वस्तुनिष्ठ हानि-प्रमाण के सामने नहीं टिकता। ज़िला न्यायालय की भूल इसकी दर्पण-छवि थी: उसने पूछा कि क्या सहायक कंपनी सचमुच चल रही थी (Moline Properties, 319 U.S. 436 (1943) का निगम-पृथक्ता प्रश्न), जबकि Rice's Toyota पूछता है कि शेयरधारक व नियंत्रित कंपनी के बीच के उस विशिष्ट लेन-देन में सार है या नहीं; कंपनी असली होने से उसके हर लेन-देन असली नहीं हो जाते।

---

## 五、与 Coltec 对照：同一种庇护，两种死法

### 中文
| 维度 | Black & Decker（本案） | Coltec（仓内已有篇） |
|---|---|---|
| 引证与法院 | 436 F.3d 431，第四巡回，2006-02-02 | 454 F.3d 1340，联邦巡回，2006-07-12 |
| 或然负债类型 | 员工医疗福利索赔（1999–2007） | 石棉诉讼索赔 |
| 交易设计方 | Deloitte & Touche（约 30 家客户） | Arthur Andersen |
| 造亏量级 | 基数约 561,000,000 售 1,000,000，损失 560,000,000 量级 | 基数 379,200,000 售 500,000，损失 378,700,000 |
| 条文层结局 | 纳税人胜：第 357(c)(3)／358(d)(2) 例外成立，第 357(b) 不穿透基数 | 纳税人胜：同一例外成立，第 357(b)(1) 随之不适用 |
| 原则层结局 | **未决**：双要件系事实问题，撤销简易判决、发回开庭审 | **纳税人败**：审理记录齐全，经济实质客观检验下本票换承接一步无税外意义，整体不予承认 |
| 检验结构 | Rice's Toyota 合取双要件（主观无目的＋客观无利润可能，缺一不可） | 联邦巡回的经济实质分析重心在客观面：只抽掉制造基数的一步 |
| 后续立法 | 两案共同背景：第 358(h) 条（2000 年立法）已要求此后同类交易按转移负债调减基数，不溯及既往；Notice 2001-17 已把或然负债庇护列为 listed transaction | 同左；另 2010 年第 7701(o) 条把经济实质成文化 |

对照的备考价值在最后一行之前的那一行：两个巡回在条文层给出同一答案，说明第 357(c)(3) 的文字确实堵不住这个结构（这也是国会 2000 年要另立第 358(h) 条的原因）；分水岭只在原则层的程序与证明——Coltec 的记录允许法院直接判实质不存在，B&D 的记录只允许发回去审。答题时把「条文能不能走通」与「实质能不能站住」永远分两段写，是这一组案例最要紧的习惯。

### English
Side-by-side with Coltec: Black & Decker, 436 F.3d 431 (4th Cir., Feb. 2, 2006), involved employee health-benefit liabilities (1999–2007) in a Deloitte-designed transaction, with roughly $561 million of claimed basis sold for $1 million (a loss on the order of $560 million); Coltec, 454 F.3d 1340 (Fed. Cir., July 12, 2006), involved asbestos liabilities in an Andersen-designed transaction, $379.2 million of basis sold for $500,000 (a $378.7 million loss). Both taxpayers won the textual layer — the §§ 357(c)(3) / 358(d)(2) exception applied and § 357(b) did not defeat it — which is precisely why Congress had already prospectively closed the structure in § 358(h) (enacted 2000, not retroactive) and the IRS had listed it in Notice 2001-17. The circuits split on posture, not on text: Coltec's full trial record let the Federal Circuit decide economic substance on the merits against the taxpayer, disregarding only the basis-manufacturing step; Black & Decker's summary-judgment record let the Fourth Circuit decide only that the conjunctive Rice's Toyota test — no non-tax business purpose plus no reasonable possibility of profit — presented triable fact issues. Exam habit from the pair: always write the analysis in two separate movements, text first, substance second.

### Español
Comparación con Coltec: Black & Decker, 436 F.3d 431 (4.º Cir., 2 de febrero de 2006), trataba pasivos por prestaciones sanitarias de empleados (1999–2007) en una operación diseñada por Deloitte, con unos 561 millones de base vendidos por 1 millón (pérdida del orden de 560 millones); Coltec, 454 F.3d 1340 (Fed. Cir., 12 de julio de 2006), trataba pasivos por amianto en una operación de Andersen, con 379,2 millones de base vendidos por 500.000 (pérdida de 378,7 millones). Ambos contribuyentes ganaron el nivel textual —la excepción de los §§ 357(c)(3) y 358(d)(2) se aplicó y el § 357(b) no la derrotó—, razón por la cual el Congreso ya había cerrado la estructura con efectos prospectivos en el § 358(h) (2000, sin retroactividad) y el IRS la había catalogado en el Notice 2001-17. La diferencia fue procesal, no textual: el expediente completo de Coltec permitió al Circuito Federal decidir la sustancia económica en el fondo contra el contribuyente, desconociendo solo el paso que fabricaba la base; el expediente sumario de Black & Decker solo permitió al Cuarto Circuito decidir que la prueba conjunta de Rice's Toyota —ausencia de propósito no fiscal más ausencia de posibilidad razonable de beneficio— planteaba cuestiones de hecho para el juicio. Hábito de examen: escribir siempre el análisis en dos movimientos separados, primero el texto, después la sustancia.

### 한국어 (초역, 원어민 감수 대기)

Coltec과의 대조: Black & Decker, 436 F.3d 431 (4th Cir., 2006년 2월 2일)은 Deloitte가 설계한 거래에서 직원 의료급여 부채(1999–2007)를 다뤘고 원가 약 561,000,000달러를 1,000,000달러에 팔아 560,000,000달러 규모의 손실을 만들었습니다. Coltec, 454 F.3d 1340 (Fed. Cir., 2006년 7월 12일)은 Andersen이 설계한 거래에서 석면 부채를 다뤘고 원가 379,200,000달러를 500,000달러에 팔아 378,700,000달러의 손실을 만들었습니다. 두 납세자 모두 문구 층에서는 이겼습니다 — §357(c)(3)/§358(d)(2) 예외가 적용되고 §357(b)가 이를 깨지 못했습니다. 그래서 의회가 2000년 §358(h)로 이 구조를 장래 향해 닫았고(소급 없음) IRS가 Notice 2001-17로 이를 listed transaction에 올린 것입니다. 갈림길은 문구가 아니라 절차와 증명에 있었습니다. Coltec은 심리 기록이 완비돼 연방순회법원이 경제 실질을 본안으로 납세자에게 불리하게 판단하며 원가를 만든 단계만을 부인할 수 있었고, Black & Decker는 약식 기록이라 제4순회법원이 Rice's Toyota의 동시충족 검사 — 비세목적 부재와 합리적 이익 가능성 부재 — 가 사실심의 쟁점이라는 것까지만 판단할 수 있었습니다. 시험 습관: 분석은 언제나 문구 먼저, 실질 나중의 두 단락으로 쓰십시오.

### Tiếng Việt (bản dịch sơ bộ, chờ người bản ngữ hiệu đính)

Đối chiếu với Coltec: Black & Decker, 436 F.3d 431 (Vòng 4, 2/2/2006), xử lý nợ phúc lợi sức khỏe của nhân viên (1999–2007) trong giao dịch do Deloitte thiết kế, với cơ sở khoảng 561.000.000 đô la bán lấy 1.000.000 (khoản lỗ ở mức 560.000.000); Coltec, 454 F.3d 1340 (Vòng Liên bang, 12/7/2006), xử lý nợ amiăng trong giao dịch do Andersen thiết kế, cơ sở 379.200.000 bán lấy 500.000 (lỗ 378.700.000). Cả hai người nộp thuế đều thắng ở tầng văn bản — ngoại lệ Điều 357(c)(3) / 358(d)(2) được áp dụng và Điều 357(b) không đánh bại được nó — đó chính là lý do Quốc hội đã đóng cấu trúc này cho tương lai bằng Điều 358(h) (ban hành năm 2000, không hồi tố) và IRS đã liệt kê nó trong Notice 2001-17. Ranh giới nằm ở thủ tục và chứng cứ, không nằm ở văn bản: hồ sơ xét xử đầy đủ của Coltec cho phép Tòa Vòng Liên bang quyết định thực chất kinh tế về nội dung, bất lợi cho người nộp thuế, chỉ loại bỏ bước chế tạo cơ sở; hồ sơ tóm tắt của Black & Decker chỉ cho phép Tòa Vòng 4 quyết định rằng phép thử đồng thời Rice's Toyota — không mục đích ngoài thuế cộng không khả năng lợi nhuận hợp lý — còn chứa vấn đề thực tế phải xét xử. Thói quen đi thi: luôn viết phân tích thành hai chuyển động tách bạch, văn bản trước, thực chất sau.

### हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

Coltec से तुलना: Black & Decker, 436 F.3d 431 (4th Cir., 2 फ़रवरी 2006) में Deloitte-रचित लेन-देन में कर्मचारी स्वास्थ्य-लाभ देनदारियाँ (1999–2007) थीं, लगभग 561,000,000 डॉलर का आधार 1,000,000 में बिका (लगभग 560,000,000 की हानि); Coltec, 454 F.3d 1340 (Fed. Cir., 12 जुलाई 2006) में Andersen-रचित लेन-देन में एस्बेस्टस देनदारियाँ थीं, 379,200,000 का आधार 500,000 में बिका (378,700,000 की हानि)। दोनों करदाता शाब्दिक स्तर पर जीते — §§ 357(c)(3) / 358(d)(2) का अपवाद लागू हुआ और § 357(b) उसे हरा नहीं पाया — यही कारण है कि कांग्रेस ने 2000 में § 358(h) से इस संरचना को भविष्य के लिए बंद किया (अतीत पर लागू नहीं) और IRS ने Notice 2001-17 में इसे सूचीबद्ध किया। अंतर पाठ का नहीं, प्रक्रिया व प्रमाण का था: Coltec के पूर्ण परीक्षण-अभिलेख ने संघीय सर्किट को आर्थिक सार पर गुणात्मक निर्णय कर केवल आधार-निर्माण चरण को अमान्य करने दिया; Black & Decker के संक्षिप्त अभिलेख ने चौथे सर्किट को केवल इतना तय करने दिया कि Rice's Toyota की संयुक्त परीक्षा — ग़ैर-कर उद्देश्य का अभाव व उचित लाभ-संभावना का अभाव — तथ्य-विवाद खड़ा करती है। परीक्षा-आदत: विश्लेषण हमेशा दो अलग चरणों में लिखें, पहले पाठ, फिर सार।

---

## 六、今天怎么用

### 中文
1. **条文层先行**：或然负债进第 351 条交易的题，先走第 357(a) 的非确认通道，再查第 357(c)(3) 是否把负债排除出「收到的金钱」，最后落第 358(d)(2) 的基数不调减——顺序反了整道题就反了。
2. **第 357(b) 的射程只到确认**：本案确立（至少在第四巡回）第 357(b)(1) 缺乏经营目的的后果落在第 351 条的确认层，不自动传导为第 358 条的基数调减；答题若要主张传导，须另有依据，不能只引第 357(b)。
3. **实质层用对检验**：在第四巡回，主观无目的与客观无利润可能须**同时**成立才构成虚假，且客观要件盯的是交易本身而非子公司整体经营；引用时注明巡回差异——其他巡回与 2010 年成文的第 7701(o) 条口径（双要件合取＋第 6662 条严格责任罚款）并不完全同构。
4. **时点意识**：1998 年的交易靠普通法打；2000 年第 358(h) 条之后同类结构条文层直接关闭；2001 年 Notice 2001-17 后再做即属 listed transaction，披露与罚款风险另计。本案与 Coltec 都只适用于规则关闭之前的存量交易。


### 한국어 (초역, 원어민 감수 대기)

**조문 적용 순서와 §357(b)의 사정거리.** 우발부채가 들어간 §351 거래 문제는 순서가 생명입니다. 먼저 §357(a)의 비인식 통로를 확인하고, 다음에 §357(c)(3)가 그 부채를 「받은 금전」에서 빼 주는지를 보고, 마지막에 §358(d)(2)의 원가 무감액으로 떨어뜨리십시오. 순서를 뒤집으면 답 전체가 뒤집힙니다. 그리고 제4순회 기준 §357(b)(1)의 사업목적 결여 효과는 §351의 인식 층에서 멈추며 §358의 원가 조정으로 자동 전파되지 않습니다. 전파를 주장하려면 §357(b) 말고 별도 근거가 필요합니다.

**실질 층의 검사와 시점 감각.** 제4순회에서는 주관적 비세목적과 객관적 이익 가능성 부재가 동시에 성립해야 허위가 되며, 객관 요건이 보는 것은 자회사 전체의 영업이 아니라 바로 그 거래 자체입니다. 다른 순회와 2010년에 성문화된 §7701(o)(합치식 두 요건 + §6662의 엄격책임 가산세)는 구성이 완전히 같지 않으니 인용할 때 순회 차이를 밝혀야 합니다. 시점도 중요합니다. 1998년 거래는 보통법으로 다퉜지만, 2000년 §358(h) 이후 같은 구조는 조문 층에서 바로 닫혔고, 2001년 Notice 2001-17 이후에 하면 listed transaction이라 공시와 가산세 위험이 별도로 붙습니다. 본안과 Coltec 모두 규칙이 닫히기 전의 잔존 거래에만 적용됩니다.

### Tiếng Việt (bản dịch sơ bộ, chờ người bản ngữ hiệu đính)

**Thứ tự áp dụng văn bản và tầm bắn của Điều 357(b).** Với bài toán giao dịch Điều 351 có nợ dự phòng, thứ tự là sinh mệnh: trước hết đi qua hành lang không ghi nhận của Điều 357(a), rồi kiểm tra Điều 357(c)(3) có loại khoản nợ khỏi «tiền nhận được» hay không, cuối cùng mới rơi xuống quy tắc không giảm cơ sở của Điều 358(d)(2) — đảo thứ tự là đảo cả đáp án. Và ít nhất ở Vòng 4, hậu quả của việc thiếu mục đích kinh doanh theo Điều 357(b)(1) dừng ở tầng ghi nhận của Điều 351, không tự động truyền sang phép điều chỉnh cơ sở của Điều 358; muốn khẳng định sự truyền dẫn thì phải có căn cứ khác ngoài Điều 357(b).

**Phép thử ở tầng thực chất và ý thức thời điểm.** Ở Vòng 4, phải đồng thời có cả không mục đích ngoài thuế về chủ quan và không khả năng lợi nhuận về khách quan mới thành giao dịch giả tạo, và yếu tố khách quan nhìn vào chính giao dịch đó chứ không nhìn hoạt động chung của công ty con. Các vòng khác và Điều 7701(o) được luật hóa năm 2010 (hai yếu tố đồng thời cộng tiền phạt trách nhiệm nghiêm ngặt của Điều 6662) không hoàn toàn đồng cấu, nên khi trích dẫn phải nêu rõ khác biệt giữa các vòng. Thời điểm cũng quan trọng: giao dịch năm 1998 được xử bằng thông luật, nhưng sau Điều 358(h) năm 2000 cấu trúc tương tự bị đóng ngay ở tầng văn bản, và sau Notice 2001-17 năm 2001 nếu còn làm sẽ là listed transaction với rủi ro công bố và phạt riêng. Cả vụ này lẫn Coltec đều chỉ áp dụng cho các giao dịch tồn đọng trước khi quy tắc bị đóng.

### हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

**पाठ लागू करने का क्रम और §357(b) की पहुँच।** आकस्मिक देनदारी वाली §351 लेन-देन की समस्या में क्रम ही जान है: पहले §357(a) के गैर-मान्यता गलियारे से जाएँ, फिर जाँचें कि §357(c)(3) उस देनदारी को «प्राप्त धन» से बाहर करता है या नहीं, और अंत में §358(d)(2) के आधार-अपरिवर्तन पर आएँ — क्रम उलटते ही पूरा उत्तर उलट जाता है। और कम से कम चौथे सर्किट में, §357(b)(1) के तहत व्यावसायिक उद्देश्य की कमी का परिणाम §351 की मान्यता-परत पर रुकता है और §358 के आधार-समायोजन में स्वतः नहीं फैलता; फैलाव का दावा करना हो तो §357(b) से अलग आधार चाहिए।

**सार-परत की परीक्षा और समय-बोध।** चौथे सर्किट में छद्म तभी बनता है जब व्यक्तिनिष्ठ ग़ैर-कर उद्देश्य का अभाव और वस्तुनिष्ठ लाभ-संभावना का अभाव दोनों एक साथ मिलें, और वस्तुनिष्ठ शर्त सहायक कंपनी के समग्र कारोबार को नहीं, उसी विशिष्ट लेन-देन को देखती है। अन्य सर्किट और 2010 में संहिताबद्ध §7701(o) (संयुक्त दो-शर्तें व §6662 का strict-liability दंड) पूरी तरह एकरूप नहीं हैं, इसलिए उद्धरण में सर्किट-अंतर स्पष्ट करें। समय-बोध भी ज़रूरी है: 1998 के लेन-देन common law से लड़े गए, किंतु 2000 के §358(h) के बाद वही संरचना पाठ-स्तर पर ही बंद हो गई, और 2001 के Notice 2001-17 के बाद उसे करना listed transaction होगा, जिसके प्रकटीकरण व दंड जोखिम अलग गिने जाएँगे। यह मामला और Coltec दोनों नियम बंद होने से पहले के बचे हुए लेन-देनों पर ही लागू होते हैं।

> 声明：个人学习笔记，不构成税务或法律建议。来源：The Black & Decker Corporation v. United States, 436 F.3d 431 (4th Cir. 2006)（判决原文，含下级审 340 F. Supp. 2d 621 (D. Md. 2004)）；Rice's Toyota World, Inc. v. Commissioner, 752 F.2d 89 (4th Cir. 1985)；Moline Properties, Inc. v. Commissioner, 319 U.S. 436 (1943)；IRC §§ 351、357(a)、357(b)、357(c)(3)、358(a)、358(d)、358(h)；Reg. § 1.357-1(c)；Notice 2001-17；Coltec Industries, Inc. v. United States, 454 F.3d 1340 (Fed. Cir. 2006)（对照）。金额均为判决原文约数者已在正文标明以原文为准。

