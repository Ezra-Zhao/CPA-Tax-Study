# Jelke 案：内置资本利得税为什么全额逐元扣——净资产法与死亡日清算假设

> 个人学习笔记，不构成税务建议。本案争的不是要不要给内置利得税留折价，而是留多少：按预计卖出年份折现，还是假定死亡当日全部清算、逐元全扣。第十一巡回选了后者，并把它定成法律问题。

## 中文主文

### 一、案名与程序坐标

Estate of Frazier Jelke III v. Commissioner, 507 F.3d 1317 (11th Cir. 2007)，上诉自税务法院备忘录判决 T.C. Memo. 2005-131。第十一巡回 2007 年 11 月 15 日判决：撤销税务法院的估值方法部分，发回按其指示重算；缺乏控制权与缺乏流通性两项折价的认定则予以维持。先行先例是第五巡回的 Estate of Dunn v. Commissioner, 301 F.3d 339 (5th Cir. 2002)——同类问题上第二个采全额逐元扣的上诉法院判决。本案的估值标的、税种与争点都长在遗产税估值上：第 2031 条公允价值、意愿买家与意愿卖家标准，以及净资产价值法下如何处理公司层面的内置税负。

### 二、事实：6.44% 的投资控股公司股份

Frazier Jelke III 于 1999 年 3 月 4 日在佛罗里达州迈阿密去世。他通过可撤销信托持有 Commercial Chemical Company（CCC）3,000 股、占 6.44% 的股份。CCC 是一家紧密持有的投资控股公司，主要资产是可流通证券：死亡日证券公允价值约 178,000,000 美元，另有约 10,000,000 美元其他资产，净资产价值合计约 188,000,000 美元；证券上附着的内置资本利得税负债约 51,000,000 美元——资产一旦卖出，这笔公司层税负就要兑现。

遗产一方 1999 年 12 月 6 日提交联邦遗产税申报表，把这部分股份报为 4,588,155 美元：算法是先从净资产中逐元全扣约 51,000,000 美元内置税负，再叠加缺乏控制权与缺乏流通性折价（申报口径约为 20% 与 35%）。国税局局长核定价值为 9,111,111 美元并发出欠税通知。两方申报值与核定值之差为 9,111,111－4,588,155＝4,522,956 美元。双方对两点并无争议：这部分股份按 CCC 的净资产价值估值；内置利得税应当产生某种折价。真正的争点只有一个——折价的算法。

### 三、税务法院：按预计出售年份折现，只认约 2,100 万

税务法院采纳局长一方专家的「经济现实」进路：内置税负不会在死亡日一次付清，而是随资产在未来陆续卖出时分年发生，估算的兑现期约 16 年，因此应把约 51,000,000 美元税负按时间折现到死亡日，只允许约 21,000,000 美元的折价。同时税务法院认定缺乏控制权折价 10%、缺乏流通性折价 15%。遗产一方不服，上诉主张 Dunn 案的清算假设：估值就是估死亡当日的状态，应当假定 CCC 在估值日清算、资产全部卖出，税负逐元全额扣减，与何时实际出售无关。

### 四、第十一巡回：全额逐元扣是法律问题，撤销发回

第十一巡回以法律问题重新审查（de novo）的方法论问题，判决撤销并发回，指示税务法院按死亡日清算、资产全部售出的假定，把约 51,000,000 美元内置资本利得税负债逐元全额从净资产价值中扣减后重算。理由有三层：其一，遗产税估的是死亡当日财产的价值，估值日的假想交易本就以当日状态为准，为估值而设的清算假设与公司日后是否真清算无关；其二，现值进路要预测每项资产何时卖出、何时纳税，专家之间分歧巨大，法院被迫在猜测上裁量，逐元扣法以确定性换精度，作为法律规则更可执行——判决明说这种 100% 进路把问题作为法律事项一次定清，提供了估值领域通常欠缺的确定性；其三，与第五巡回 Dunn 案保持一致，避免同类紧密持有投资公司在不同巡回得到两套算法。Carnes 法官异议：假定的当日清算忽略了税负递延的时间价值，得到的是更不精确的价值。多数意见对税务法院认定的 10% 缺乏控制权折价与 15% 缺乏流通性折价予以维持——被推翻的只是内置税负这一项的算法，不是整张估值表。

### 五、算例勾稽（教学复算，本地整数与 Decimal 两路一致；非法院最终核定数）

以判决载明的约数复算两种算法差在哪一步。净资产价值取 188,000,000 美元（＝证券 178,000,000＋其他资产约 10,000,000）。

全额逐元扣：188,000,000－51,000,000＝137,000,000 美元；乘 6.44% 得 Jelke 份额 8,822,800 美元；再按税务法院认定并被维持的折价顺序打折：8,822,800×(1－10%)×(1－15%)＝8,822,800×0.9×0.85＝6,749,442 美元。

税务法院现值法：188,000,000－21,000,000＝167,000,000 美元；乘 6.44% 得 10,754,800 美元；同样两项折价后为 10,754,800×0.9×0.85＝8,227,422 美元。

两种算法在同一组折价下相差 8,227,422－6,749,442＝1,477,980 美元——全部差距只来自内置税负是扣 51,000,000 还是扣 21,000,000 这一步，折价率本身两边完全相同。这也解释了为什么本案值得打到上诉法院：方法之争就是近 150 万美元之争。注意本算例是教学复算，用来定位方法差异；发回重算的最终核定数以税务法院重算结果为准，不以本例数字为准。

### 六、规则落点与适用边界

第一，净资产法下内置利得税折价有两条路线：Dunn／Jelke 的逐元全扣（估值日清算假设）与按预计兑现期折现的事实测算。Jelke 把全扣定成第十一巡回的法律规则；在该巡回之外，税务法院在非 Golsen 情形仍可能按事实与专家证据测算折价，执业时先查估值标的公司所在巡回的口径，不要把 Jelke 当全国统一公式。第二，本案标的是纯投资控股公司、资产为可流通证券且双方同意用净资产法——经营性公司改用收益法或市场法时，内置税负的处理要另行论证，不能直接搬清算假设。第三，与第 14 章的衔接：家族实体估值先过第 2701 至 2704 条的法定调整（保留权益零值、限制不计），再谈缺乏控制权、缺乏流通性与内置税负这类估值折价，两层不要混在一起打折。本案与仓内《Estate of Powell 案》《Strangi 案》的家族有限合伙估值线互为参照：那两篇管第 2036 条拉回与真实出售例外，本篇管净资产法内部的税负折价。

### 七、加州口径

加州没有州级遗产税，本案的估值争点纯属联邦遗产税问题；加州实务中遇到同类紧密持有公司股份估值，仍按联邦第 2031 条与所在巡回的判例口径处理。州侧另行存在的是所得税与财产税问题，与本案的净资产估值方法不互相替代（证据等级 B；判决原文与引证为 A 级）。

*声明：个人学习笔记，不构成税务建议。来源：Estate of Jelke v. Commissioner, 507 F.3d 1317 (11th Cir. 2007) 判决原文；T.C. Memo. 2005-131；Estate of Dunn v. Commissioner, 301 F.3d 339 (5th Cir. 2002)；局长就本案申请调卷令状（No. 07-1582）所载申报值与核定值。*

---

## English

### Citation and Posture

Estate of Frazier Jelke III v. Commissioner, 507 F.3d 1317 (11th Cir. 2007), on appeal from T.C. Memo. 2005-131. On November 15, 2007, the Eleventh Circuit vacated the Tax Court's valuation methodology and remanded with instructions to recompute, while affirming the Tax Court's lack-of-control and lack-of-marketability discounts. The governing precedent it followed was Estate of Dunn v. Commissioner, 301 F.3d 339 (5th Cir. 2002)—making Jelke the second court of appeals decision to adopt a full dollar-for-dollar discount for built-in capital gains tax in a net-asset-value valuation under § 2031's willing buyer/willing seller standard.

### Facts

Jelke died on March 4, 1999, in Miami, Florida, holding 3,000 shares—a 6.44% interest—in Commercial Chemical Company (CCC), a closely held investment holding company, through his revocable trust. At death, CCC's marketable securities were worth about $178 million, with roughly $10 million of other assets, for a net asset value of about $188 million, and the securities carried a built-in capital gains tax liability of about $51 million. The estate's return, filed December 6, 1999, reported the interest at $4,588,155, using a dollar-for-dollar reduction for the built-in tax plus lack-of-control and lack-of-marketability discounts (reported at about 20% and 35%). The Commissioner determined a value of $9,111,111—a gap of $9,111,111 − $4,588,155 = $4,522,956. Both sides agreed the stock was to be valued on CCC's net asset value and that some discount for the built-in tax was appropriate; only the measurement was disputed.

### The Tax Court's Present-Value Approach

The Tax Court adopted the Commissioner's expert approach: because the tax would be incurred piecemeal as assets were sold over a projected period of about sixteen years, only the present value of the liability—about $21 million—should reduce net asset value. It separately allowed a 10% lack-of-control discount and a 15% lack-of-marketability discount.

### The Eleventh Circuit's Dollar-for-Dollar Rule

Reviewing the methodology de novo as a question of law, the Eleventh Circuit vacated and remanded with instructions to reduce net asset value by the entire $51 million built-in tax liability, on the arbitrary but deliberate assumption that CCC was liquidated on the date of death and all assets sold. Its reasons: estate tax values property as of the date of death, so the hypothetical transaction is measured at that date regardless of when sales actually occur; the present-value approach forces courts to wade through divergent expert predictions about sale timing, while the 100% approach settles the issue as a matter of law and supplies certainty that valuation usually lacks; and consistency with Dunn avoids two rules for the same asset type. Judge Carnes dissented, arguing that the liquidation assumption ignores the time value of deferring the tax and yields a less accurate value. The court affirmed the 10% and 15% discounts—only the built-in tax methodology was reversed.

### Worked Recomputation (Teaching Figures, Self-Checked)

Using the opinion's rounded figures and net asset value of $188,000,000 (= $178,000,000 + about $10,000,000): dollar-for-dollar gives $188,000,000 − $51,000,000 = $137,000,000; the 6.44% share is $8,822,800; applying the affirmed discounts in sequence, $8,822,800 × 0.9 × 0.85 = $6,749,442. The present-value route gives $188,000,000 − $21,000,000 = $167,000,000; the share is $10,754,800; after the same discounts, $8,227,422. The entire difference—$8,227,422 − $6,749,442 = $1,477,980—comes from the single step of deducting $51 million versus $21 million. These are teaching recomputations that locate the methodological difference, not the final assessed figures on remand.

### Scope and Limits

Jelke states a rule of law for the Eleventh Circuit; outside it, the Tax Court in non-Golsen cases may still measure the built-in tax discount on facts and expert proof, so the circuit governing the decedent's estate must be checked first. The case also presupposes a pure investment holding company valued by net asset value with both sides' agreement; operating companies valued on earnings or market approaches require separate argument. Finally, Chapter 14 adjustments (§§ 2701–2704) apply before valuation discounts are considered; the two layers are not interchangeable.

### California Notes

California has no state estate tax, so the dispute is purely federal; California practitioners apply § 2031 and the controlling circuit's case law. State income and property tax questions are separate systems (evidence grade B; the opinion and citations are grade A).

*Disclaimer: Personal study notes, not tax advice. Sources: Estate of Jelke v. Commissioner, 507 F.3d 1317 (11th Cir. 2007); T.C. Memo. 2005-131; Estate of Dunn v. Commissioner, 301 F.3d 339 (5th Cir. 2002); the Commissioner's certiorari petition in No. 07-1582 for the reported and determined values.*

---

## Español (初译待校)

### Cita y situación procesal

Estate of Frazier Jelke III v. Commissioner, 507 F.3d 1317 (11th Cir. 2007), en apelación de T.C. Memo. 2005-131. El 15 de noviembre de 2007, el Undécimo Circuito anuló la metodología de valoración del Tax Court y devolvió el caso con instrucciones de recalcular, confirmando a la vez los descuentos por falta de control y por falta de comerciabilidad. El precedente seguido fue Estate of Dunn v. Commissioner, 301 F.3d 339 (5th Cir. 2002): Jelke es la segunda decisión de un tribunal de apelaciones que adopta el descuento íntegro, dólar por dólar, del impuesto sobre ganancias de capital incorporado en una valoración por valor neto de activos bajo el estándar del comprador y vendedor dispuestos de la sección 2031.

### Hechos

Jelke falleció el 4 de marzo de 1999 en Miami, Florida, con 3.000 acciones —una participación del 6,44%— de Commercial Chemical Company (CCC), una sociedad holding de inversión de capital cerrado, a través de su fideicomiso revocable. A su muerte, los valores negociables de CCC valían unos $178 millones, con unos $10 millones de otros activos: un valor neto de activos de unos $188 millones y una obligación fiscal incorporada por ganancias de capital de unos $51 millones. La herencia declaró la participación en $4,588,155 en su declaración presentada el 6 de diciembre de 1999, con reducción íntegra del impuesto incorporado y descuentos por falta de control y de comerciabilidad (declarados en torno al 20% y al 35%). El Comisionado fijó un valor de $9,111,111: una diferencia de $9,111,111 − $4,588,155 = $4,522,956. Ambas partes aceptaban la valoración por valor neto de activos y que correspondía algún descuento por el impuesto incorporado; solo se discutía su medida.

### El enfoque de valor actual del Tax Court

El Tax Court aceptó el enfoque del perito del Comisionado: como el impuesto se pagaría por partes a medida que los activos se vendieran en un periodo proyectado de unos dieciséis años, solo debía deducirse su valor actual, unos $21 millones. Reconoció además un 10% por falta de control y un 15% por falta de comerciabilidad.

### La regla del Undécimo Circuito

Revisando la metodología de novo como cuestión de derecho, el tribunal anuló y devolvió el caso ordenando deducir la totalidad de los $51 millones bajo el supuesto —arbitrario pero deliberado— de que CCC se liquidaba en la fecha de la muerte y todos los activos se vendían. Razones: el impuesto sobre sucesiones valora a fecha de la muerte; el enfoque de valor actual obliga a los tribunales a dirimir predicciones periciales divergentes sobre el calendario de ventas, mientras que el enfoque del 100% resuelve la cuestión como materia de derecho y aporta una certeza poco habitual en valoración; y la coherencia con Dunn evita dos reglas para el mismo tipo de activo. El juez Carnes disintió: el supuesto de liquidación ignora el valor temporal de diferir el impuesto y produce un valor menos exacto. Los descuentos del 10% y del 15% fueron confirmados; solo cambió la metodología del impuesto incorporado.

### Recálculo didáctico (verificado)

Con las cifras redondeadas de la sentencia y un valor neto de $188,000,000 (= $178,000,000 + unos $10,000,000): el método íntegro da $188,000,000 − $51,000,000 = $137,000,000; el 6,44% equivale a $8,822,800; aplicando en secuencia los descuentos confirmados, $8,822,800 × 0,9 × 0,85 = $6,749,442. El método de valor actual da $188,000,000 − $21,000,000 = $167,000,000; la participación es $10,754,800 y, tras los mismos descuentos, $8,227,422. Toda la diferencia —$8,227,422 − $6,749,442 = $1,477,980— nace de un solo paso: deducir $51 millones frente a $21 millones. Son recálculos didácticos para localizar la diferencia metodológica, no las cifras finales de la devolución.

### Alcance y límites

Jelke enuncia una regla de derecho para el Undécimo Circuito; fuera de él, el Tax Court en casos no sometidos a Golsen puede seguir midiendo el descuento por hechos y prueba pericial, por lo que primero debe comprobarse el circuito aplicable. El caso presupone además una holding puramente inversora valorada por activos netos con acuerdo de ambas partes; las empresas operativas valoradas por resultados o mercado exigen argumentación propia. Y los ajustes del capítulo 14 (secciones 2701 a 2704) se aplican antes que los descuentos de valoración: son capas distintas.

### Nota sobre California

California no tiene impuesto estatal sobre sucesiones; la controversia es puramente federal y en la práctica californiana se aplican la sección 2031 y la jurisprudencia del circuito competente (grado de evidencia B; la sentencia es grado A).

*Nota: apuntes personales de estudio; no constituye asesoramiento fiscal. Fuentes: 507 F.3d 1317 (11th Cir. 2007); T.C. Memo. 2005-131; 301 F.3d 339 (5th Cir. 2002); petición de certiorari del Comisionado, n.º 07-1582.*

---

## 한국어 (初译待校)

### 인용과 절차

Estate of Frazier Jelke III v. Commissioner, 507 F.3d 1317 (11th Cir. 2007), T.C. Memo. 2005-131에 대한 항소 사건이다. 2007년 11월 15일 제11순회법원은 조세법원의 평가 방법론을 파기하고 재계산을 지시하며 환송하되, 통제권 부족과 유통성 부족 할인의 인정은 유지했다. 따른 선례는 Estate of Dunn v. Commissioner, 301 F.3d 339 (5th Cir. 2002)로, Jelke는 순자산가치 평가에서 내재 자본이득세를 전액 달러 대 달러로 차감한 두 번째 항소법원 판결이다. 평가 기준은 제2031조의 자발적 매수자·매도자 표준이다.

### 사실관계

Jelke는 1999년 3월 4일 플로리다주 마이애미에서 사망했고, 취소 가능 신탁을 통해 폐쇄형 투자 지주회사 Commercial Chemical Company(CCC)의 주식 3,000주, 지분 6.44%를 보유했다. 사망 당시 CCC의 유통 증권은 약 $178,000,000, 기타 자산은 약 $10,000,000으로 순자산가치는 약 $188,000,000이었고, 증권에는 약 $51,000,000의 내재 자본이득세 부채가 붙어 있었다. 유산 측은 1999년 12월 6일 제출한 신고에서 내재 세금을 전액 차감하고 통제권·유통성 부족 할인(신고 기준 약 20%와 35%)을 적용해 해당 지분을 $4,588,155로 신고했다. 국세청장은 $9,111,111로 결정했으니 차액은 $9,111,111 − $4,588,155 = $4,522,956이다. 양측 모두 순자산가치 평가와 내재 세금에 대한 일정한 할인 자체에는 동의했고, 다툼은 그 측정 방법뿐이었다.

### 조세법원의 현재가치 접근

조세법원은 청장 측 전문가의 접근을 받아들였다. 세금은 약 16년에 걸쳐 자산이 팔릴 때 나누어 발생하므로, 사망일로 할인한 현재가치 약 $21,000,000만 차감해야 한다는 것이다. 통제권 부족 할인 10%와 유통성 부족 할인 15%는 별도로 인정했다.

### 제11순회법원의 전액 차감 규칙

방법론을 법률 문제로 새로 심사한 제11순회법원은, 사망일에 CCC가 청산되고 전 자산이 매각된다는 가정 아래 내재 세금 $51,000,000 전액을 순자산가치에서 차감하라고 지시하며 파기 환송했다. 이유는 상속세는 사망일 현재의 가치를 재는 점, 현재가치 접근은 매각 시기에 대한 전문가들의 엇갈린 예측을 법원이 헤쳐 나가게 만드는 반면 100% 접근은 문제를 법률 사항으로 정해 평가 영역에 드문 확실성을 제공하는 점, 그리고 Dunn과의 일관성이다. Carnes 판사는 세금 이연의 시간가치를 무시해 덜 정확한 가치가 된다고 반대했다. 10%와 15% 할인은 유지되었고, 바뀐 것은 내재 세금의 방법론뿐이다.

### 교육용 재계산 (검증 완료)

판결의 반올림 수치와 순자산가치 $188,000,000(= $178,000,000 + 약 $10,000,000)을 쓰면, 전액 차감법은 $188,000,000 − $51,000,000 = $137,000,000, 6.44% 지분은 $8,822,800, 유지된 할인을 순서대로 적용하면 $8,822,800 × 0.9 × 0.85 = $6,749,442이다. 현재가치법은 $188,000,000 − $21,000,000 = $167,000,000, 지분은 $10,754,800, 같은 할인 후 $8,227,422이다. 차이 $8,227,422 − $6,749,442 = $1,477,980 전부가 $51,000,000를 빼느냐 $21,000,000를 빼느냐의 한 단계에서 나온다. 이는 방법 차이를 찾기 위한 교육용 재계산이며 환송 후 최종 결정액이 아니다.

### 범위와 한계

Jelke는 제11순회법원의 법률 규칙을 선언한 것이며, 그 밖에서는 Golsen이 적용되지 않는 사건에서 조세법원이 사실과 전문가 증거로 할인을 측정할 수 있으므로 먼저 적용 순회법원을 확인해야 한다. 또한 이 사건은 양측이 합의한 순자산법으로 평가되는 순수 투자 지주회사를 전제로 하며, 영업회사의 수익·시장 접근에는 별도 논증이 필요하다. 제14장(제2701조–제2704조)의 법정 조정은 평가 할인보다 먼저 적용되는 별개의 층이다.

### 캘리포니아 주석

캘리포니아에는 주 상속세가 없으므로 이 분쟁은 순전히 연방 문제이며, 실무에서는 제2031조와 관할 순회법원의 판례를 적용한다(증거 등급 B, 판결문은 A등급).

*메모: 개인 학습 노트이며 세무 자문이 아니다. 출처: 507 F.3d 1317 (11th Cir. 2007), T.C. Memo. 2005-131, 301 F.3d 339 (5th Cir. 2002), 청장의 상고허가 신청 No. 07-1582.*

---

## Tiếng Việt (初译待校)

### Trích dẫn và tư thế tố tụng

Estate of Frazier Jelke III v. Commissioner, 507 F.3d 1317 (11th Cir. 2007), kháng cáo từ T.C. Memo. 2005-131. Ngày 15 tháng 11 năm 2007, Tòa Phúc thẩm Khu vực 11 hủy bỏ phương pháp định giá của Tòa Thuế và chuyển hồ sơ về để tính lại theo chỉ dẫn, đồng thời giữ nguyên các mức chiết khấu thiếu quyền kiểm soát và thiếu tính thanh khoản. Tiền lệ được theo là Estate of Dunn v. Commissioner, 301 F.3d 339 (5th Cir. 2002); Jelke là phán quyết phúc thẩm thứ hai áp dụng chiết khấu toàn bộ theo từng đô-la đối với thuế lãi vốn tích lũy trong định giá theo giá trị tài sản ròng dưới chuẩn người mua sẵn lòng/người bán sẵn lòng của § 2031.

### Sự kiện

Jelke qua đời ngày 4 tháng 3 năm 1999 tại Miami, Florida, nắm giữ qua tín thác có thể thu hồi 3.000 cổ phần — lợi ích 6,44% — trong Commercial Chemical Company (CCC), một công ty holding đầu tư khép kín. Khi qua đời, chứng khoán có thể giao dịch của CCC trị giá khoảng $178 triệu, cùng khoảng $10 triệu tài sản khác, cho giá trị tài sản ròng khoảng $188 triệu, và chứng khoán mang nghĩa vụ thuế lãi vốn tích lũy khoảng $51 triệu. Phía di sản khai lợi ích ở mức $4,588,155 trong tờ khai nộp ngày 6 tháng 12 năm 1999, dùng cách trừ toàn bộ thuế tích lũy theo từng đô-la cộng các chiết khấu thiếu kiểm soát và thiếu thanh khoản (khai khoảng 20% và 35%). Ủy viên xác định giá trị $9,111,111 — chênh lệch $9,111,111 − $4,588,155 = $4,522,956. Cả hai bên đều đồng ý định giá theo giá trị tài sản ròng của CCC và rằng cần có một mức chiết khấu nào đó cho thuế tích lũy; chỉ cách đo lường là còn tranh cãi.

### Cách tiếp cận giá trị hiện tại của Tòa Thuế

Tòa Thuế chấp nhận cách tiếp cận của chuyên gia phía Ủy viên: vì thuế sẽ phát sinh từng phần khi tài sản được bán trong khoảng mười sáu năm dự kiến, chỉ giá trị hiện tại của nghĩa vụ — khoảng $21 triệu — mới được trừ khỏi giá trị tài sản ròng. Tòa còn cho chiết khấu 10% vì thiếu kiểm soát và 15% vì thiếu thanh khoản.

### Quy tắc trừ toàn bộ của Tòa Khu vực 11

Xét lại phương pháp như một vấn đề pháp luật theo chuẩn de novo, tòa hủy bỏ và chuyển hồ sơ về với chỉ dẫn trừ toàn bộ $51 triệu thuế tích lũy khỏi giá trị tài sản ròng, trên giả định — tùy ý nhưng có chủ đích — rằng CCC bị thanh lý vào ngày qua đời và mọi tài sản đều được bán. Lý do: thuế di sản định giá tài sản tại ngày qua đời; cách giá trị hiện tại buộc tòa phải lội qua các dự đoán chuyên gia trái ngược nhau về thời điểm bán, trong khi cách 100% giải quyết vấn đề như một matter of law và mang lại sự chắc chắn hiếm có trong định giá; và sự nhất quán với Dunn. Thẩm phán Carnes bất đồng: giả định thanh lý bỏ qua giá trị thời gian của việc hoãn nộp thuế và cho giá trị kém chính xác hơn. Các mức 10% và 15% được giữ nguyên — chỉ phương pháp thuế tích lũy bị đảo ngược.

### Tính lại mang tính giảng dạy (đã kiểm tra)

Dùng các con số làm tròn của phán quyết và giá trị tài sản ròng $188,000,000 (= $178,000,000 + khoảng $10,000,000): cách trừ toàn bộ cho $188,000,000 − $51,000,000 = $137,000,000; phần 6,44% là $8,822,800; áp dụng lần lượt hai chiết khấu đã được giữ nguyên, $8,822,800 × 0,9 × 0,85 = $6,749,442. Cách giá trị hiện tại cho $188,000,000 − $21,000,000 = $167,000,000; phần là $10,754,800 và sau cùng các chiết khấu là $8,227,422. Toàn bộ chênh lệch — $8,227,422 − $6,749,442 = $1,477,980 — đến từ một bước duy nhất: trừ $51 triệu so với $21 triệu. Đây là phép tính lại phục vụ giảng dạy để xác định khác biệt phương pháp, không phải con số xác định cuối cùng sau khi chuyển về.

### Phạm vi và giới hạn

Jelke tuyên bố một quy tắc pháp luật cho Khu vực 11; ngoài khu vực đó, Tòa Thuế trong các vụ không chịu Golsen vẫn có thể đo chiết khấu thuế tích lũy theo sự kiện và chứng cứ chuyên gia, nên phải kiểm tra khu vực áp dụng trước. Vụ án cũng giả định một công ty holding đầu tư thuần túy được định giá theo tài sản ròng với sự đồng ý của hai bên; công ty hoạt động được định giá theo thu nhập hoặc thị trường cần lập luận riêng. Các điều chỉnh của Chương 14 (§§ 2701–2704) áp dụng trước các chiết khấu định giá; hai lớp này không thay thế nhau.

### Ghi chú California

California không có thuế di sản cấp bang, nên tranh chấp hoàn toàn thuộc liên bang; người hành nghề tại California áp dụng § 2031 và án lệ của khu vực có thẩm quyền (mức bằng chứng B; bản án là mức A).

*Lưu ý: ghi chép học tập cá nhân, không phải tư vấn thuế. Nguồn: 507 F.3d 1317 (11th Cir. 2007); T.C. Memo. 2005-131; 301 F.3d 339 (5th Cir. 2002); đơn xin certiorari của Ủy viên, số 07-1582.*

---

## हिन्दी (初译待校)

### उद्धरण और प्रक्रियात्मक स्थिति

Estate of Frazier Jelke III v. Commissioner, 507 F.3d 1317 (11th Cir. 2007), T.C. Memo. 2005-131 से अपील। 15 नवंबर 2007 को ग्यारहवें सर्किट ने कर न्यायालय की मूल्यांकन पद्धति को रद्द कर निर्देशों सहित पुनर्गणना के लिए वापस भेजा, जबकि नियंत्रण की कमी और विपणन क्षमता की कमी की छूटों को बरकरार रखा। अनुसरित पूर्वनिर्णय Estate of Dunn v. Commissioner, 301 F.3d 339 (5th Cir. 2002) था — Jelke शुद्ध संपत्ति मूल्य मूल्यांकन में अंतर्निहित पूंजी लाभ कर के लिए पूर्ण डॉलर-दर-डॉलर छूट अपनाने वाला दूसरा अपीलीय निर्णय है, § 2031 के इच्छुक क्रेता/इच्छुक विक्रेता मानक के अंतर्गत।

### तथ्य

Jelke का निधन 4 मार्च 1999 को मियामी, फ़्लोरिडा में हुआ। वह अपने प्रतिसंहरणीय ट्रस्ट के माध्यम से एक निकट-स्वामित्व वाली निवेश होल्डिंग कंपनी Commercial Chemical Company (CCC) में 3,000 शेयर — 6.44% हित — रखते थे। निधन पर CCC की विपणन योग्य प्रतिभूतियाँ लगभग $178 मिलियन की थीं, अन्य संपत्ति लगभग $10 मिलियन, शुद्ध संपत्ति मूल्य लगभग $188 मिलियन, और प्रतिभूतियों पर लगभग $51 मिलियन का अंतर्निहित पूंजी लाभ कर दायित्व था। एस्टेट ने 6 दिसंबर 1999 को दाखिल रिटर्न में हित का मूल्य $4,588,155 बताया, जिसमें अंतर्निहित कर की पूर्ण कटौती और नियंत्रण व विपणन क्षमता की कमी की छूटें (रिपोर्ट अनुसार लगभग 20% और 35%) थीं। आयुक्त ने मूल्य $9,111,111 निर्धारित किया — अंतर $9,111,111 − $4,588,155 = $4,522,956। दोनों पक्ष इस पर सहमत थे कि शेयरों का मूल्यांकन CCC के शुद्ध संपत्ति मूल्य से होगा और अंतर्निहित कर के लिए कुछ छूट उचित है; विवाद केवल माप का था।

### कर न्यायालय का वर्तमान मूल्य दृष्टिकोण

कर न्यायालय ने आयुक्त के विशेषज्ञ का दृष्टिकोण अपनाया: क्योंकि कर लगभग सोलह वर्षों में संपत्तियों की बिक्री के साथ किस्तों में उत्पन्न होगा, दायित्व का केवल वर्तमान मूल्य — लगभग $21 मिलियन — शुद्ध संपत्ति मूल्य से घटाया जाना चाहिए। उसने नियंत्रण की कमी के लिए 10% और विपणन क्षमता की कमी के लिए 15% छूट अलग से दी।

### ग्यारहवें सर्किट का पूर्ण कटौती नियम

पद्धति को विधि के प्रश्न के रूप में de novo समीक्षा करते हुए न्यायालय ने रद्द कर वापस भेजा और निर्देश दिया कि संपूर्ण $51 मिलियन अंतर्निहित कर दायित्व शुद्ध संपत्ति मूल्य से घटाया जाए, इस मनमाने किंतु जानबूझकर चुने गए अनुमान पर कि CCC का निधन की तिथि पर परिसमापन हुआ और सभी संपत्तियाँ बेची गईं। कारण: एस्टेट कर संपत्ति का मूल्य निधन की तिथि पर आंकता है; वर्तमान मूल्य दृष्टिकोण न्यायालयों को बिक्री के समय पर विशेषज्ञों की परस्पर विरोधी भविष्यवाणियों से जूझने पर मजबूर करता है, जबकि 100% दृष्टिकोण प्रश्न को विधि के मामले के रूप में तय करता है और मूल्यांकन में दुर्लभ निश्चितता देता है; और Dunn से संगति। न्यायाधीश Carnes ने असहमति दी: परिसमापन अनुमान कर के स्थगन के समय मूल्य को नज़रअंदाज़ करता है और कम सटीक मूल्य देता है। 10% और 15% छूटें बरकरार रहीं — केवल अंतर्निहित कर की पद्धति बदली।

### शिक्षण पुनर्गणना (सत्यापित)

निर्णय के गोल आंकड़ों और शुद्ध संपत्ति मूल्य $188,000,000 (= $178,000,000 + लगभग $10,000,000) से: पूर्ण कटौती पर $188,000,000 − $51,000,000 = $137,000,000; 6.44% हिस्सा $8,822,800; बरकरार छूटों को क्रम से लगाने पर $8,822,800 × 0.9 × 0.85 = $6,749,442। वर्तमान मूल्य मार्ग पर $188,000,000 − $21,000,000 = $167,000,000; हिस्सा $10,754,800; उन्हीं छूटों के बाद $8,227,422। पूरा अंतर — $8,227,422 − $6,749,442 = $1,477,980 — केवल एक चरण से आता है: $51 मिलियन घटाना बनाम $21 मिलियन घटाना। ये शिक्षण पुनर्गणनाएँ हैं जो पद्धतिगत अंतर को दर्शाती हैं, वापसी पर अंतिम निर्धारित आंकड़े नहीं।

### दायरा और सीमाएँ

Jelke ग्यारहवें सर्किट के लिए विधि का नियम कहता है; उसके बाहर, गैर-Golsen मामलों में कर न्यायालय तथ्यों और विशेषज्ञ प्रमाण पर अंतर्निहित कर छूट माप सकता है, इसलिए पहले लागू सर्किट जाँचना चाहिए। मामला यह भी मानता है कि दोनों पक्षों की सहमति से शुद्ध संपत्ति मूल्य से मूल्यांकित एक शुद्ध निवेश होल्डिंग कंपनी है; आय या बाजार दृष्टिकोण से मूल्यांकित परिचालन कंपनियों के लिए अलग तर्क चाहिए। अध्याय 14 के समायोजन (§§ 2701–2704) मूल्यांकन छूटों से पहले लागू होते हैं; ये दो परतें परस्पर विनिमेय नहीं हैं।

### कैलिफ़ोर्निया टिप्पणी

कैलिफ़ोर्निया में राज्य एस्टेट कर नहीं है, इसलिए विवाद पूर्णतः संघीय है; वहाँ के व्यवहारकर्ता § 2031 और नियंत्रक सर्किट के निर्णयों को लागू करते हैं (साक्ष्य स्तर B; निर्णय स्तर A है)।

*टिप्पणी: व्यक्तिगत अध्ययन नोट्स, कर सलाह नहीं। स्रोत: 507 F.3d 1317 (11th Cir. 2007); T.C. Memo. 2005-131; 301 F.3d 339 (5th Cir. 2002); आयुक्त की certiorari याचिका सं. 07-1582.*
