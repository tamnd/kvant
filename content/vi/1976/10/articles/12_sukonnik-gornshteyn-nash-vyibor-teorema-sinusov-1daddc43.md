---
id: 1976-10-sukonnik-gornshteyn-nash-vyibor-teorema-sinusov-1daddc43
issue: kvant_1976_10
year: 1976
number: "10"
title: Sự lựa chọn của chúng tôi là định lý về sin!
authors:
  - Суконник Я. Н.
  - Горнштейн П. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 48
page_last: 52
page_labels: 46-50
tag: 7Q2O
lang: vi
source: kvant_digital
extraction: vision
content_sha256: a98775af2fca710e186a5260c4e07a5bd46aac63ae2c6d16eb34b68649d0b95b
prompt_sha256: draft-1
translated_from: content/ru/1976/10/articles/12_sukonnik-gornshteyn-nash-vyibor-teorema-sinusov-1daddc43.md
source_content_sha256: b0de61526fe5130fa1f947a1f83887daf433f2981ee2244bdf727787e49ad2f1
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 46⟧

Sự lựa chọn của chúng tôi là định lý về sin!

Trong bất kỳ tam giác $ABC$ các cạnh $|BC| = a, |CA| = b, |AB| = c$ và các góc $\widehat{CAB} = \widehat{A}, \widehat{ABC} = \widehat{B}, \widehat{BCA} = \widehat{C}$ có ​​liên quan với nhau bởi các mối quan hệ quan trọng sau.

Định lý cosin*). Bình phương của một cạnh tùy ý bằng bình phương cạnh kia của hình vuông phẳng của tam giác trừ đi tích gấp đôi của các cạnh này với cosin của góc giữa chúng, nghĩa là
$$a^2 = b^2 + c^2 - 2bc \cos \widehat{A},$$
$$b^2 = c^2 + a^2 - 2ca \cos \widehat{B},$$
$$c^2 = a^2 + b^2 - 2ab \cos \widehat{C}.$$
Định lý sin. Một cạnh tùy ý bằng tích của đường kính đường tròn ngoại tiếp và sin của góc kề, nghĩa là
$$a = 2R \sin \widehat{A}, b = 2R \sin \widehat{B},$$
$$c = 2R \sin \widehat{C},$$
hoặc, ở dạng phổ biến hơn,
$$\frac{a}{\sin \widehat{A}} = \frac{b}{\sin \widehat{B}} = \frac{c}{\sin \widehat{C}} = 2R.$$
Nhưng nếu bạn được yêu cầu chỉ sử dụng một trong hai định lý này và loại bỏ định lý kia, bạn sẽ giữ lại định lý nào? Từ định lý sin người ta có thể suy ra định lý cos, và từ định lý cos thì định lý sin (mặc dù không có hệ số tỉ lệ $2R$ - như trong sách giáo khoa). Nhưng định lý

*) Về định lý cosine, xem bài viết của E. G. Gotman “Định lý Cosine và hệ quả của nó” («Kvant», 1972, số 7).

⟦folio 47⟧

kể từ đây,

$$|AB| \cdot |CD| + |BC| \cdot |DA| = 4R^2 \left| \sin(\hat{A} + \hat{B} - \alpha) \cdot \sin(\alpha) + \sin(\hat{A} - \alpha) \cdot \sin(\hat{B} - \alpha) \right| = 2R^2 \left| \cos(\hat{A} + \hat{B} - 2\alpha) - \cos(\hat{A} + \hat{B} - 2\alpha) \right| = 4R^2 \sin \hat{A} \sin \hat{B} = (2R \sin \hat{A}) \cdot (2R \sin \hat{B}) = |BD| \cdot |AC|.$$

Ứng dụng tự nhiên nhất của định lý sin dường như là trong những trường hợp khi trong bài toán chúng ta đang nói về các cạnh, các góc đối diện và bán kính của một hình tròn được mô tả xung quanh một hình tam giác.

Bài toán 2 (MSU, cơ chế, 1961). Cho một hình tam giác có đáy là $\alpha$ và góc ở đỉnh của nó là $\alpha$. Một đường tròn được dựng đi qua tâm của tam giác nội tiếp và các đầu của đáy. Tìm bán kính của nó.

Đặt $O$ (Hình 2) là tâm của đường tròn nội tiếp. Sau đó

$$\widehat{BOC} = 180^\circ - \widehat{OBC} - \widehat{OCB} = 180^\circ - \frac{\hat{B}}{2} - \frac{\hat{C}}{2} = 90^\circ + \frac{\alpha}{2}.$$

Vì tam giác $BOC$ nội tiếp trong đường tròn ban đầu nên sử dụng định lý sin chúng ta tìm được đường tròn này:

$$R = \frac{|BC|}{2 \sin \widehat{BOC}} =$$

Cơm. 1.

Cơm. 2.

Cơm. 3.

Bài toán 3 (MSU, vật lý, 1962; UrSU, vật lý, 1973). Trong một tam giác cân, góc đáy là $\alpha$. Chiều cao hạ xuống chân đế lớn hơn bán kính của dốc treo $m$. Xác định đáy của tam giác và bán kính của đường tròn chính.

Đặt lại $O$ là tâm của đường tròn nội tiếp (Hình 3). Sau đó

$$|AO| = |AD| - |OD| = h_a - r = m,$$

$$\widehat{AOC} = 90^\circ + \frac{\alpha}{2}, \quad \widehat{ACO} = \frac{\alpha}{2}.$$

Do đó, áp dụng định lý sin hai lần (đối với tam giác $ABC$ và $AOC$), ta thu được

$$|BC| = |AC| \cdot \frac{\sin \hat{A}}{\sin \hat{B}} =$$

$$= |AO| \frac{\sin \widehat{AOC}}{\sin \widehat{ACO}} \cdot \frac{\sin \hat{A}}{\sin \hat{B}} = 2m \cos \alpha \cdot \text{ctg} \frac{\alpha}{2},$$

$$R = \frac{|AC|}{2 \sin \hat{B}} = \frac{|AO| \sin \widehat{AOC}}{2 \sin \widehat{ACO} \cdot \sin \hat{B}} = \frac{m \sin \left(90^\circ + \frac{\alpha}{2}\right)}{2 \sin \frac{\alpha}{2} \cdot \sin \alpha} = \frac{m}{4 \sin^2 \frac{\alpha}{2}}.$$

Bài toán 4. Tứ giác $ABCD$ được mô tả ở gần độ dốc lớn, các đường chéo của nó

⟦folio 48⟧

hình xuyến cắt nhau tại điểm E. Bán kính của các đường tròn ngoại tiếp các tam giác AEB, BEC và CED lần lượt bằng $R_1$, $R_2$ và $R_3$.
Tìm bán kính R của đường tròn ngoại tiếp tam giác AED.

Tứ giác ABCD (Hình 4) được mô tả xung quanh một đường tròn nên đẳng thức đúng
$$|AB| + |CD| = |BC| + |AD|.$$
Bên cạnh đó,

$$\sin \widehat{AEB} = \sin \widehat{BEC} =$$
$$= \sin \widehat{CED} = \sin \widehat{DEA}.$$
Sau đó
$$\frac{|AB|}{\sin \widehat{AEB}} + \frac{|CD|}{\sin \widehat{CED}} =$$
$$= \frac{|BC|}{\sin \widehat{BEC}} + \frac{|AD|}{\sin \widehat{DEA}}.$$

Bây giờ, theo định lý sin, chúng ta có $R_1 + R_3 = R_2 + R$, từ đó
$$R = R_1 - R_2 + R_3.$$

Đôi khi trong các bài toán cần phải chuyển từ một tỷ lệ đã biết của một cạnh hoặc các đoạn sang tỷ lệ tương ứng giữa các góc của một tam giác. Và điều này được thực hiện thuận tiện nhất bằng cách sử dụng định lý sin.

Bài toán 5 (LSU, Khoa Hóa học, 1973). Trong tam giác đều ABC ($|AB| = |BC|$), vẽ đường trung tuyến AD. Tìm góc BAD nếu góc ở đỉnh B là α.

Từ tam giác ABD (Hình 5), trong đó $|AB| = 2|BD|$, suy ra định lý sin

$$2 = \frac{|AB|}{|BD|} = \frac{\sin \widehat{ADB}}{\sin \widehat{BAD}} = \frac{\sin(\alpha + \widehat{BAD})}{\sin \widehat{BAD}} = \sin \alpha \cdot \text{ctg} \widehat{BAD} + \cos \alpha.$$

Từ đây
$$\widehat{BAD} = \arctg \frac{2 - \cos \alpha}{\sin \alpha}.$$

Bài toán 6. Tam giác đều thứ hai nội tiếp trong tam giác đều này và tỉ số diện tích của chúng là 3. Chứng minh rằng các cạnh của tam giác nội tiếp vuông góc với các cạnh tương ứng của tam giác đã cho.

Thật dễ dàng để chứng minh (chứng minh!) rằng $|AF|$ bằng $|BD|$ (Hình 6). Bây giờ từ sự giống nhau của các tam giác ABC và DEF theo định lý sin ta có

$$\sqrt{3} = \sqrt{\frac{S_{\triangle ABC}}{S_{\triangle DEF}}} = \frac{|AB|}{|DF|} =$$
$$= \frac{|AF| + |FB|}{|DF|} = \frac{|BD|}{|DF|} + \frac{|FB|}{|DF|} = \frac{\sin \widehat{BFD}}{\sin \widehat{DBF}} + \frac{\sin \widehat{BDF}}{\sin \widehat{DBF}} = \frac{\sin(120^\circ - \widehat{BDF}) + \sin \widehat{BDF}}{\sin 60^\circ} = 2 \cos(60^\circ - \widehat{BDF})$$
$$\cos(60^\circ - \widehat{BDF}) = \frac{\sqrt{3}}{2}, \widehat{BDF} = 90^\circ$$
(sau đó $|FD| \perp |BC|$) hoặc $\widehat{BDF} = 30^\circ$. (sau đó $|FD| \perp |AB|$).

⟦folio 49⟧

Nhiệm vụ 7 (MSU, Cơ học và Toán học, 1972). Cho tam giác ABC, uelol C là tunoy; bissertis BE uela B ta chia cạnh AC thành các đoạn AE và EC có độ dài 3 m và 2 m. Biết rằng điểm K nằm trên phần kéo dài của cạnh BC ngoài đỉnh C, là tâm của đường tròn đi qua các điểm C, E và là giao điểm của bissertis uelela B với bissertis uelela ACK. Tính khoảng cách từ điểm E đến cạnh AB.

Rõ ràng, khoảng cách mong muốn EH (Hình 7) sẽ được tìm thấy nếu biết sin $\hat{A}$. Nhưng trước hết chúng ta hãy tìm mối liên hệ giữa các góc của tam giác ABC. Gọi D là giao điểm của góc bissertis B và ACK. Hãy vẽ hợp âm EF, sau đó $\hat{EDC} = \hat{EFC}$, nhưng

$$\hat{EDC} = \hat{DCF} - \hat{DBC} = \frac{1}{2} \hat{ACF} - \frac{\hat{B}}{2} = \frac{(180^\circ - \hat{C}) - \hat{B}}{2} = \frac{\hat{A}}{2},$$

$$\hat{EFC} = 90^\circ - \hat{ECF} = 90^\circ - (180^\circ - \hat{C}) = \hat{C} - 90^\circ,$$

tư thế

$$\frac{\hat{A}}{2} = \hat{C} - 90^\circ, \hat{C} = 90^\circ + \frac{\hat{A}}{2}.$$

Theo định lý sin và tính chất bissertis, từ tam giác ABC ta có

$$\frac{2}{3} = \frac{|EC|}{|AE|} = \frac{|BC|}{|AB|} = \frac{\sin A}{\sin \hat{C}} = \frac{\sin \hat{A}}{\sin \left(90^\circ + \frac{\hat{A}}{2}\right)} = 2 \sin \frac{\hat{A}}{2},$$

$$\sin \frac{\hat{A}}{2} = \frac{1}{3}, \sin \hat{A} = \frac{4\sqrt{2}}{9},$$

$$|EH| = |AE| \cdot \sin \hat{A} = \frac{4\sqrt{2}}{3}.$$

Đôi khi tích của một số tỷ lệ của các phân đoạn xuất hiện trong bài toán. Và ở đây việc áp dụng định lý sin sẽ dẫn đến một lời giải đơn giản.

Nhiệm vụ 8 (MSU, Khoa Kinh tế, 1975). Cho tam giác ABC có $|AB| = |AC|$ và $\hat{A} = 80^\circ$. Bên trong tam giác ABC lấy điểm M biểu thị $\hat{MBC} = 30^\circ$ và $\hat{MCB} = 10^\circ$. Tìm uelol AMC.

Chúng ta hãy biểu thị góc mong muốn $\hat{AMC}$ bằng x (Hình 8). Rõ ràng là

$$\hat{ABM} = 20^\circ, \hat{ACM} = 40^\circ, \hat{CMB} = 140^\circ,$$

và sau đó $\hat{AMB} = 220^\circ - x$. Theo điều kiện và định lý sin của tam giác AMB và AMC

Cơm. 7. Hình 8. Hình 9.

⟦folio 50⟧

chúng tôi có

$$1 = \frac{|AB|}{|AC|} = \frac{|AB|}{|AM|} \cdot \frac{|AM|}{|AC|} = \frac{\sin(220^\circ - x)}{\sin 20^\circ} \cdot \frac{\sin 40^\circ}{\sin x} = \frac{2 \sin(x - 40^\circ) \cos 20^\circ}{\sin x} = \frac{\sin(x - 20^\circ) + \sin(x - 60^\circ)}{\sin x},$$

$$\sin x - \sin(x - 60^\circ) = \sin(x - 20^\circ),$$
$$2 \sin 30^\circ \cdot \cos(x - 30^\circ) = \sin(x - 20^\circ),$$
$$\cos(x - 30^\circ) = \cos(110^\circ - x),$$
$$x = \widehat{AMC} = 70^\circ.$$

Bài toán 9. Trong chuỗi lồi ABCD có các giếng:
$$\widehat{BAC} = 15^\circ, \widehat{CBD} = 90^\circ, \widehat{DCA} = 30^\circ,$$
$$\widehat{ADB} = 75^\circ.$$ Đặt tên cho giếng giữa các diazons.

Chúng ta hãy biểu thị $\widehat{AED}$ bằng $x$ (Hình 9).

Sau đó $\widehat{ABE} = x - 15^\circ, \widehat{BCE} = 90^\circ - x,$
$\widehat{CDE} = x - 30^\circ, \widehat{DAE} = 105^\circ - x,$ và từ các tam giác $AEB, BEC, CED$ và $DEA$ theo định lý sin ta có
$$\frac{|AE|}{|BE|} = \frac{\sin(x - 15^\circ)}{\sin 15^\circ}, \frac{|BE|}{|CE|} = \frac{\sin(90^\circ - x)}{\sin 90^\circ}, \frac{|CE|}{|DE|} = \frac{\sin(x - 30^\circ)}{\sin 30^\circ},$$
$$\frac{|DE|}{|AE|} = \frac{\sin(105^\circ - x)}{\sin 75^\circ}.$$

Nhân các đẳng thức bằng văn bản với từng số hạng, sau khi khử các thừa số giống nhau ta thu được
$$\sin(x - 15^\circ) \cdot \sin(90^\circ - x) \times \sin(x - 30^\circ) \cdot \sin(105^\circ - x) = \sin 15^\circ \cdot \sin 90^\circ \cdot \sin 30^\circ \cdot \sin 75^\circ,$$
$$[2 \sin(x - 15^\circ) \cdot \sin(105^\circ - x)] \times [2 \sin(x - 30^\circ) \sin(90^\circ - x)] = 2 \sin 15^\circ \cdot \cos 15^\circ,$$
$$[\cos(2x - 120^\circ) - \cos 90^\circ] \times |\cos(2x - 120^\circ) - \cos 60^\circ| = \frac{1}{2},$$
$$2 \cos^2(2x - 120^\circ) - \cos(2x - 120^\circ) - 1 = 0,$$
do đó góc mong muốn bằng $60^\circ$.

Ở bên phải
1 (MSU, VMK, 1971). Trong hình tròn bán kính $R$ có hai dây: $AB$ và $AC$. Trên dây $AB$ hoặc trên phần mở rộng của nó, điểm $B$ được lấy làm điểm $M$, khoảng cách từ đó đến đường thẳng $AC$ bằng độ dài của dây cung $AC$. Tương tự, trên dây $AC$ hoặc trên phần mở rộng của nó, điểm $C$ được lấy là điểm $N$, khoảng cách từ đó đến đường thẳng $AB$ bằng độ dài của dây cung $AB$. Tìm độ dài của đoạn $MN$.

2 (NSU, mexmat, 1969). Chứng minh rằng trong các tam giác có đáy và góc ở đỉnh cho trước thì tam giác đều có chu vi lớn nhất.

3 (MIPT, 1970). Trong một tam giác, góc ở đỉnh $A$ gấp ba lần góc $B$ và các cạnh $AB, BC, AC$ (theo thứ tự đó) tạo thành một cấp số cộng. Tìm các góc của tam giác $ABC$.

4 (MIIT, 1972). Trong một tam giác vuông, cho một góc nhọn $\alpha$ và khoảng cách $a$ từ đỉnh của một góc nhọn khác đến tâm của đường tròn nội tiếp. Xác định diện tích của hình tam giác.

5 (MSU, Khoa Địa lý, 1969). Đường thẳng đi qua đỉnh $B$ của tam giác đều $ABC$, cắt đáy $AC$ tại điểm $D$. Người ta biết rằng

$$\widehat{ABD} = \frac{1}{3} \widehat{ABC} \text{ и } |AD|:|DC| = 3:4.$$

Góc nhọn hay góc tù $ABC$?
6 (MSU, Khoa Sinh học, 1968). Trong một tam giác tròn đều $ABC$, trong đó có $|AB| = |BC|$ và $\widehat{ABC} = \alpha$. Từ đỉnh $A$ vẽ một đường phân giác của góc $BAC$, cắt cạnh $BC$ tại điểm $D$ và đường tròn tại điểm $E$. Đỉnh $B$ được nối bằng một đoạn thẳng tới điểm $E$. Tìm tỉ số diện tích của các hình tam giác $ABE$ và $BDE$.

7 (MSU, Khoa Địa chất, 1975). Trong hình thoi $ABCD$, tính từ cạnh $(1 + \sqrt{5})$ с và ​​góc nhọn $\widehat{BAD} = 60^\circ$ có ​​một đường tròn nội tiếp tam giác $ABD$. Từ điểm $C$ đến đường tròn. một tiếp tuyến được vẽ cắt cạnh $AB$ tại điểm $E$. Tìm độ dài của đoạn $AE$.

8. Tứ giác tròn $ABCD$. Qua điểm $E$ giao điểm của đường chéo vẽ đoạn $FH$ (F nằm trên $AB$, $H$ trên $CD$). Chứng minh rằng

$$\frac{|FE|}{|EH|} = \sqrt{\frac{|AF|}{|CH|} \cdot \frac{|BF|}{|DH|}}.$$
