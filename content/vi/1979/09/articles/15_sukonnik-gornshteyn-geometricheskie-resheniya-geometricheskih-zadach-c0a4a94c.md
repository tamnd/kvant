---
id: 1979-9-sukonnik-gornshteyn-geometricheskie-resheniya-geometricheskih-zadach-c0a4a94c
issue: kvant_1979_9
year: 1979
number: "9"
title: Hình học lời giải Hình học bài toán
authors:
  - Суконник Я. Н.
  - Горнштейн П. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 40
page_last: 44
page_labels: 38-42
tag: 4S9C
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 3c5a7300d659501b686d90207227456742b2a93aaac403845f9ce5b727fdf5c3
prompt_sha256: draft-1
translated_from: content/ru/1979/09/articles/15_sukonnik-gornshteyn-geometricheskie-resheniya-geometricheskih-zadach-c0a4a94c.md
source_content_sha256: 2b4384ab2947b17b794fa3a6ab14ca91fe91065d99f5af34d74dd1416d84a6d8
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 38⟧

Hình học lời giải Hình học bài toán

Dành để tưởng nhớ Vainman V. Sh., một giáo viên dạy toán ở thành phố Kyiv.

Đối với lời giải hình học bài toán, trước tiên họ sử dụng nhiều phương pháp phân tích khác nhau. Hiện tại, bài viết nói về một số phương pháp hình học làm cho lời giải đơn giản và hợp lý. Các phương pháp được trình bày gần như giống hệt nhau và chắc chắn là không mới đối với người đọc, tuy nhiên, có vẻ như thông tin về chúng sẽ hữu ích cho tất cả những ai muốn học cách giải tốt hình học bài toán.

1. Hãy xác định loại hình.

Lời giải bài toán trong một số trường hợp, sẽ nhanh hơn đáng kể nếu trước tiên bạn xác định loại mà hình gốc có thể có (hoặc có thể không).

Bài toán 1 (MSU, VMK, 1978). Một đường tròn ngoại tiếp tam giác AMB, tâm cách cạnh AM một đoạn là 10. Phần kéo dài của cạnh AM vượt ra ngoài đỉnh M cắt đoạn BC bằng 29 từ tiếp tuyến với đường tròn vẽ qua đỉnh B. Tìm diện tích tam giác BMC nếu biết góc ACB bằng arctan $\frac{20}{21}$.

Hãy xác định loại tam giác BMC mà chúng ta vẽ chiều cao $BM_1$ của nó, mở rộng nó đến giao điểm với đường tròn tại điểm $M_2$ và chiếu tâm của đường tròn O lên cạnh AM và dây cung $BM_2$ (Hình 1). Sau đó, theo điều kiện,

$$|OK| = 10, |BM_1| = |BC| \sin \widehat{ACB} = 29 \sin \left( \arctg \frac{20}{21} \right) = 29 \cdot \frac{20}{29} = 20 = 2 |OK|, |BM_2| = 2 |BL| = 2 (|BM_1| - |LM_1|) = 2 (|BM_1| - |OK|) = 2 |BM_1| - |BM_2| = |BM_1|.$$

Theo đó, các điểm M, $M_1$ và $M_2$ trùng nhau (Hình 2) và do đó, điểm O nằm trên [AB] và tam giác BMC là tam giác vuông. Phần còn lại là rõ ràng. (Đáp số.210.)

Bài toán 2 (MSU, địa chất. khoa, 1978). Cho tam giác ABC có cạnh $|AC| = 3, \widehat{BAC} = \frac{\pi}{6}$ và bán kính đường tròn ngoại tiếp là 2. Chứng minh diện tích tam giác ABC có một cạnh nhỏ hơn 3.

Hãy chứng minh rằng $\triangle ABC$ không thể là góc vuông. Trên thực tế, chúng ta hãy vẽ trong đường tròn bán kính 2 từ điểm A các dây AC, AB$_1$, AB$_2$ và đường kính AD (Hình 3) sao cho $|AC| = 3, \widehat{B_1AC} = \widehat{B_2AC} = \frac{\pi}{6}$. Đoạn AB$_1$ không trùng với đoạn AD, vì $\widehat{CAB}_1 = \frac{\pi}{6} \neq \arccos \frac{3}{4} = \arccos \frac{|AC|}{|AD|} = \widehat{CAD}$. Do đó $\widehat{ACB}_1 \neq \frac{\pi}{2}$ và $|AB_1| < |AD|$. Vì vậy $S_{\Delta AB_1} = \frac{1}{2} |AC| \cdot |AB_1| \sin \widehat{B_1AC} < \frac{1}{2} |AC| \cdot |AD| \sin \widehat{B_1AC} = \frac{1}{2} \cdot 3 \cdot 4 \times \sin \frac{\pi}{6} = 3$. Bất bình đẳng $S_{\Delta AB_2} < 3$ dễ dàng xảy ra từ $|AB_2| < |AC| = 3$.

2. Hãy “hoàn thành” hình vẽ.

Bất kỳ hình học lời giải hình học bài toán nào đều bắt đầu bằng việc vẽ một bản vẽ.

⟦folio 39⟧

Đồng thời, đôi khi trong một bản vẽ “tự nhiên” (tức là trong một bản vẽ chỉ có điều kiện được “mô tả”), rất khó nhận thấy các kết nối giữa dữ liệu và các giá trị ban đầu và nếu hình đã “hoàn thành”, những kết nối này trở nên rõ ràng.

Bài toán 3 (MSU, Khoa Khoa học Đất, 1977). Độ dài đáy CD, đường chéo BD và cạnh AD của hình thang ABCD bằng nhau và bằng p. Độ dài cạnh BC bằng q. Tìm độ dài đường chéo AC.

Trong hình thang ABCD này (Hình 4), không thể thấy được mối liên hệ giữa đường chéo AC ban đầu và các đoạn khác. Nếu xét điểm D cách đều các điểm A, B và C, vẽ đường tròn O(D, p) và “hoàn thiện” hình thang này thành hình thang cân ABCE thì dễ dàng tìm được $|AC| = \sqrt{4p^2 - q^2}$ từ tam giác vuông ACE.

Bài toán 4 (NSU, 1976). Cho hình thang ABCD có đáy AB và CD, đường bicsectrix của B vuông góc với cạnh AD và cắt nó tại điểm E. Theo tỉ số nào?

Đường thẳng BE có chia cho diện tích hình thang nếu biết độ dài đoạn AE gấp đôi đoạn DE?

Nếu chúng ta “hoàn thiện” hình thang ABCD này thành tam giác AFB (Hình 5), chúng ta sẽ thu được một tam giác đều mà từ đó đoạn DC cắt tam giác đồng dạng DFC với hệ số tương tự $\frac{1}{4}$. Do đó, tỷ lệ cần thiết là bằng $\frac{S_{EDCB}}{S_{\Delta AEB}} = \frac{S_{\Delta EFB} - S_{\Delta DFC}}{S_{\Delta AEB}} = \frac{\frac{1}{2} S_{\Delta AFB} - \left(\frac{1}{4}\right)^2 S_{\Delta AFB}}{\frac{1}{2} S_{\Delta AFB}} = \frac{7}{8}$.

3. Hãy mô tả một vòng tròn.

Trong một số trường hợp, một điểm quan trọng trong hình học lời giải bài toán là việc thiết lập sự phụ âm của một số góc. Thông thường, các góc như vậy tương ứng trong các tam giác giống nhau

⟦folio 40⟧

hoặc đa giác. Tuy nhiên, những tình huống như vậy có thể xảy ra khi sự đồng dạng của một cặp góc được coi là tiếp nối sự đồng dạng của một cặp góc khác mà giá trị của chúng đã biết. Ví dụ: gần một hình tứ giác $ABCD$ khi và chỉ khi có thể mô tả một hình tròn khi $\widehat{ABC} + \widehat{ADC} = 180^\circ$ (“Hình học 8”, trang 113). Dễ dàng chứng minh được điều kiện này tương đương với điều kiện $\widehat{ABD} = \widehat{ACD}$. Do đó, các đẳng thức $\widehat{ABD} = \widehat{ACD}$, $\widehat{ACB} = \widehat{ADB}$, $\widehat{BAC} = \widehat{BDC}$, $\widehat{CAD} = \widehat{CBD}$ là tương đương (Hình 6).

Bài toán 5 (MIPT, 1976). Điểm $E$ nằm trên cạnh $AC$ của tam giác đúng $ABC$; điểm $K$ là điểm giữa của đoạn $AE$. Đường thẳng đi qua điểm $E$ vuông góc ($AB$) và đường thẳng đi qua điểm $C$ vuông góc ($BC$) cắt nhau tại điểm $D$. Tìm các góc của tam giác $BKD$.

Để đường thẳng $ED$ cắt đường thẳng $AB$ tại điểm $F$ (Hình 7). Khi đó tam giác $AFE$ là hình chữ nhật và $[FK]$ là đường trung tuyến. Điều này có nghĩa là tam giác $AFK$ là tam giác đều, đồng dạng với tam giác đã cho $ABC$. Posny $[FK] \parallel [BC]$ và tứ giác $BFKC$ là một hình thang cân. Do đó, hãy mô tả một vòng tròn xung quanh nó. Từ $\widehat{BFD} + \widehat{BCD} = 90^\circ + 90^\circ = 180^\circ$ suy ra điểm $D$ thuộc cùng một đường tròn.

Pozny $\widehat{BKD} = \widehat{BFD} = 90^\circ$, $\widehat{KDB} = \widehat{KCB} = 60^\circ$ và $\widehat{DBK} = 30^\circ$.

Bài toán 6 (MSU, vật lý, 1974). Điểm $A$ được lấy trên bisectrix của góc có đỉnh $L$. Điểm $K$ và $M$ là đáy của các đường vuông góc hạ từ $A$ xuống các cạnh của góc. Trên đoạn $KM$ lấy một điểm $P$ (|$KP$| < |$PM$|) và qua điểm $P$ vuông góc với đoạn $AP$ vẽ một đường thẳng cắt đường thẳng $KL$ tại điểm $Q$ (Giữa $Q$ và $L$) và đường thẳng $ML$ tại điểm $S$. Được biết, $\widehat{KLM} = \alpha$, |$KM$| = $a$, |$QS$| = $b$. Tìm độ dài của đoạn $KQ$.

Như bạn đã biết, $|AK| = |AM|$. Thật dễ dàng để báo cáo rằng $\widehat{AKM} = \widehat{ALK} = \frac{\alpha}{2}$.

Pozny $|AK| = \frac{a}{2\cos \frac{\alpha}{2}}$.

Có thể vẽ các vòng tròn xung quanh các hình tứ giác $APKQ$ ($\widehat{APQ} = \widehat{AKQ} = 90^\circ$) và $APSM$ ($\widehat{APS} + \widehat{AMS} = 90^\circ + 90^\circ = 180^\circ$) (Hình 8). Tìm kiếm $AQS = AQP = AKP = AKM = AMK = AMP = ASP = ASQ = \frac{\alpha}{2}$, tam giác $AQS$ - đều. Từ $\triangle AQS$ có $|AQ|$, rồi từ tam giác vuông $AKQ$ - $|KQ| = \frac{\sqrt{b^2 - a^2}}{2\cos \frac{\alpha}{2}}$.

⟦folio 41⟧

4. "Tam giác dẫn đầu này"

Hình học Ponsk lời giải bài toán có thể được dẫn theo hướng khoảng cách của các hình có tính chất đã được nghiên cứu kỹ. Tuy nhiên, một trong những hình này chắc chắn là hình tam giác. Sự giúp đỡ trung thành và tử tế - tam giác - việc tìm kiếm không phải là thiếu hiểu biết và đôi khi không thể thiếu trong những khác biệt của chúng ta, trong việc tìm kiếm đơn giản và rõ ràng lời giải. Hãy để chúng tôi cho phép mình đưa ra lời khuyên sau: nếu bạn gặp khó khăn trong việc chọn đường hình học chính xác lời giải bài toán, hãy tìm một hình tam giác!

Bài toán 7 (MSU, VMK, 1975). Cho một hình thang hình chữ nhật có đáy bằng a và b (a<b). Người ta biết rằng một đường thẳng song song với đáy của một vùng biển nào đó cắt nó thành hai hình thang, mỗi hình có thể nội tiếp một đường tròn. Xác định bán kính của các đường tròn này.

Chúng ta hãy xây hình thang ABCD này thành một hình tam giác (Hình 9). Cho các đường tròn nội tiếp hình thang AEFD và EBCF tiếp xúc với [EF] tại các điểm M và N, bán kính của chúng lần lượt là R và r. Vì hình thang này là hình chữ nhật nên |EM|=R, |EN|=r. Từ đẳng thức |KP|=|KQ| dễ dàng suy ra |EN|=|MF|. (Phát biểu này có tính chất tổng quát: trong bất kỳ tam giác nào, các điểm tiếp tuyến của đường tròn nội tiếp và đường tròn bên ngoài cách đều hai đầu của cạnh mà chúng tiếp xúc. Đường tròn nội tiếp là đường tròn tiếp xúc với một cạnh của tam giác và phần kéo dài của hai cạnh kia.) Vậy |EF|=R+r. Từ sự đồng dạng của các tam giác BKC, EKF và AKD ta thu được hệ

$$\begin{cases} \frac{a}{R+r} = \frac{r}{R}, \\ \frac{R+r}{b} = \frac{r}{R} \end{cases}$$

(trong các tam giác đồng dạng, cả bán kính nội tiếp và bán kính các hình tròn ngoài đều được coi là các cạnh tương ứng), trong đó $R = \frac{bV_a}{V_a + V_b}$, $r = \frac{aV_b}{V_a + V_b}$.

Hình 9.

Hình 10.

Bài toán 8 (MSU, khoa vật lý, 1975). Cho hình chữ nhật ABCD (|BC|>|CD|), các đường chéo AC và BD cắt nhau tại điểm O. Phân giác của góc CAD cắt [BD] tại điểm E. Gọi F là đáy của đường vuông góc hạ từ điểm E xuống cạnh AD; điểm K là điểm giữa [AD]. Qua điểm E, đường vuông góc cũng được vẽ tới [AE] cho đến khi nó cắt đường chéo AC tại điểm H. Tìm diện tích ABCD nếu |OH|=b, |KF|=\frac{4}{3}b.

Hãy làm [EL] || [AD], trong đó L∈[AO] (Hình 10). Vì $\hat{AEL} = \hat{EAD} = \hat{EAC}$, |AL|=|LE|=2|ME|=2|KF|=\frac{8}{3}b.

Tiếp tục vuông góc HE cho đến khi cắt [AD] tại điểm G. Tam giác AHG là đều ([AE] là đường phân giác và đường cao). Vì [LE] là đường giữa trong đó,

⟦folio 42⟧

Hình 11.

tam giác LHE cũng là tam giác đều. Pozny

$$|OM| = \sqrt{|OL|^2 - |LM|^2} = \sqrt{(|LH| - |OH|)^2 - |ME|^2} = \sqrt{(|LE| - |OH|)^2 - |KF|^2} = \sqrt{\left(\frac{8}{3}b - b\right)^2 - \left(\frac{4}{3}b\right)^2} = b.$$

Sử dụng các tam giác đồng dạng ACD và LOM có hệ số đồng dạng

$$\kappa = \frac{|AC|}{|LO|} = \frac{2|AO|}{|LH| - |OH|} = \frac{2(|AL| + |LH| - |OH|)}{|LE| - |OH|} = \frac{2\left(\frac{8}{3}b + \frac{8}{3}b - b\right)}{\frac{8}{3}b - b} = 5,2,$$

tìm diện tích cần thiết

$$S_{ABCD} = 2S_{\Delta ACD} = 2k^2 S_{\Delta LOM} = k^2 \cdot |LM| \cdot |OM| = (5,2)^2 \cdot \frac{4}{3}b \cdot b = \left(36 \cdot \frac{4}{75}\right)b^2.$$

Bài toán 9 (MIPT, 1974). Một ranh giới đều với các đáy AD và BC (|AD| > |BC|) được mô tả xung quanh đường tròn. Một đường thẳng song song với đường chéo AC cắt các cạnh AD và CD của đường thẳng tương ứng tại các điểm M và N và tiếp xúc với đường tròn tại điểm P. Xác định các góc của các đường biên nếu $\frac{|MP|}{|PN|} = k$.

Xét các tam giác đồng dạng ACD và MND (Hình 11) dẫn đến một hình học đơn giản lời giải. Ta ký hiệu E, F và G lần lượt là các điểm tiếp tuyến của đường tròn trên các cạnh AD, CD và BC, bằng H và Q - hình chiếu của các điểm C và N trên cạnh AD. Hãy |PN| = 1. Khi đó |MP| = k, |AH| = |AE| + |EH| = |ED| + |GC| = |DF| + |FC| = |DC|. Từ tính chất đồng dạng và trong tam giác MND sẽ có |MQ| = |DN|. Pozny

$$|MN| = |MP| + |PN| = k + 1, |DQ| = |DE| - |QM| - |ME| = |DF| - |DN| - |MP| = |NF| - |MP| = |NP| - |MP| = 1 - k, 2 |NQ|^2 = (|MQ|^2 + |NQ|^2) - (|DN|^2 - |NQ|^2) = |MN|^2 - |DQ|^2 = (k + 1)^2 - (1 - k)^2 = 4k, |NQ| = \sqrt{2k}.$$

Do đó, tan $\hat{D} = \frac{|NQ|}{|DQ|} = \frac{\sqrt{2k}}{1 - k}, \hat{A} = \hat{D} = \arctg \frac{\sqrt{2k}}{1 - k}, \hat{B} = \hat{C} = \pi - \arctg \frac{\sqrt{2k}}{1 - k}.$

Bài tập

1 (MSU, Khoa Ngữ văn, Khoa Cấu trúc và Ngôn ngữ học Ứng dụng, 1978). Ngũ giác ABCDE nội tiếp trong một đường tròn bán kính đơn vị. Được biết, |AB| = $\sqrt{2}$, $ABE = 45^\circ$, $EBD = 30^\circ$ và |BC| = |CD|. Diện tích của hình ngũ giác là gì?

2 (MSU, khoa địa chất, 1978). Cho tam giác ABC có độ dài cạnh AB là 4. $\widehat{CAB} = \frac{\pi}{3}$, và bán kính của đường tròn ngoại tiếp R bằng 2,2. Chứng minh rằng độ dài đường cao hạ từ đỉnh C xuống cạnh AB nhỏ hơn $\frac{11\sqrt{3}}{5}$.

3 (NSU, 1976). Cho hình bình hành ABCD có góc BAD bằng 60°. Đường tròn đi qua các điểm A, B, D cắt cạnh CD ở chính giữa. Tìm diện tích hình bình hành nếu bán kính hình tròn là R.

4 (MSU, Khoa Khoa học Cảm giác, 1977). Cạnh AB của hình thang ABCCD có độ dài gấp đôi đáy CD và gấp đôi cạnh AD. Độ dài đường chéo AC bằng a, độ dài cạnh BC bằng b. Tìm diện tích của hình thang.

5 (MINT, 1977). Tâm của hình bán nguyệt nằm trên đáy AD lớn hơn của hình thang ABCCD; tất cả các cạnh khác chạm vào hình bán nguyệt. Chứng minh rằng |AD| = |AB| + |CD|.
