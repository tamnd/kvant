---
id: 1973-11-ovchinnikov-sharyigin-chislovyie-dannyie-v-geometricheskih-zadachah-3d4c74f7
issue: kvant_1973_11
year: 1973
number: "11"
title: Dữ liệu số trong các bài toán hình học
authors:
  - Овчинников С. В.
  - Шарыгин И. Ф.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 54
page_last: 58
page_labels: 52-56
tag: 27S0
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 5990f3521a66977b0a1fcf94a8414c059d9e0c47ea7a75eed85825220eaf36e4
prompt_sha256: draft-1
translated_from: content/ru/1973/11/articles/11_ovchinnikov-sharyigin-chislovyie-dannyie-v-geometricheskih-zadachah-3d4c74f7.md
source_content_sha256: f61adac7daff3ad343b2b3ce52fd2ca87088ffc377678ea8e10183b609f0e746
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 52⟧

Dữ liệu số trong các bài toán hình học
S. V. Ovchinnikov, I. F. Sharytsin

Ở hầu hết các trường học tiêu chuẩn, các con số bài toán không đóng vai trò gì cả. Theo quy định, bài toán như vậy có thể được giải ở dạng tổng quát, sử dụng ký hiệu “chữ cái”, sau đó thay thế các số này thành kết quả đáp số. Tuy nhiên, việc thường xuyên sử dụng "thông số kỹ thuật" của dữ liệu số sẽ tạo ra lời giải đơn giản hơn. Trong ghi chú này, chúng tôi sẽ đưa ra các ví dụ bằng cách dữ liệu số ảnh hưởng khác nhau như thế nào đến lời giải bài toán.

Hãy bắt đầu với bài toán, được đưa ra trong kỳ thi tuyển sinh vào Khoa Hóa học của Đại học Tổng hợp Moscow năm 1970.

Bài toán 1. Dây AB chúng ta nối cung của một đường tròn bằng 120°. Điểm C nằm trên bộ đôi emoy và điểm D nằm trên dây AB. Trong trường hợp này AD = 2, BD = 1, DC = √2. Trực giác của tam giác ABC.

Lưu ý rằng ∠ODC = 90°. Thật vậy, chúng ta hãy tiếp tục đoạn CD cho đến khi nó giao với đường tròn (Hình 1). Vì AD · BD = CD × DE nên DE = CD = √2 và OD ⊥ CE. Từ △AOF chúng ta tìm được bán kính của hình tròn. Nó bằng √3, vì vậy từ tam giác OFD ta có ∠FDO = 60°. Do đó ∠CDA = 30°, ∠CDB = 150°.

Sử dụng công thức để xác định diện tích của một tam giác dựa trên hai cạnh và góc xen giữa chúng, ta thấy S△ADC = √2/2, S△CDB = √2/4. Do đó S△ABC = 3/4 √2.

Phân tích lời giải đã cho, chúng ta thấy rằng dữ liệu số trong bài toán đã được chọn “rất tốt”. Nếu chúng ta cố gắng giải bài toán này ở dạng tổng quát, tức là lấy các số tùy ý làm dữ liệu ban đầu, chúng ta sẽ nhanh chóng thấy rằng lời giải hóa ra cực kỳ cồng kềnh. (Hãy thử giải bài toán này ở dạng tổng quát. Đây sẽ là một bài tập hữu ích.) Nhưng đây là một bài toán điển hình, trong đó dữ liệu số không đóng bất kỳ vai trò nào. Chúng chỉ được sử dụng ở giai đoạn cuối khi thay thế vào đáp số chung và nhằm mục đích minh họa.

Bài toán 2 (geofakt của Đại học quốc gia Moscow, 1968). Cho tam giác ABC vẽ các đường phân giác AD, BAC và hai đường phân giác CF, ACB (phần D nằm trên cạnh BC, phần F nằm trên cạnh AB). Tỉ số rõ ràng của diện tích một tam giác

⟦folio 53⟧

Hình 2.

Bộ đệm ABC và AFD, nếu biết AB = 21, AC = 28, CB = 20.

Chúng ta ký hiệu các cạnh của tam giác AB, BC và CA lần lượt là c, a và b (Hình 2). Áp dụng tính chất phân giác của một góc trong tam giác ta tìm được

$$AF = \frac{bc}{a+b}, \quad BD = \frac{ac}{b+c}.$$

Từ đây

$$\frac{S_{\triangle ABD}}{S_{\triangle ABC}} = \frac{BD}{BC} = \frac{c}{b+c},$$

$$\frac{S_{\triangle AFD}}{S_{\triangle ABD}} = \frac{AF}{AB} = \frac{b}{(a+b)},$$

$$\frac{S_{\triangle ABC}}{S_{\triangle AFD}} = \frac{(a+b)(b+c)}{bc}$$

Thay thế các giá trị số của chúng cho a, b và c, chúng ta tìm thấy $$\frac{S_{\triangle ABC}}{S_{\triangle AFD}} = 4,$$ và do đó ngoại lệ là 4.

bài toán tiếp theo có thể được giải ở dạng tổng quát, nhưng lời giải tồn tại sẽ được đơn giản hóa nếu chúng ta sử dụng các giá trị số theo thời gian.

Bài toán 3 (Cơ học và Toán học của Đại học quốc gia Moscow, 1969). Các hình chiếu thẳng của tam giác ABC lên hai mặt phẳng vuông góc với nhau là các tam giác vuông có cạnh bằng 1. Tìm chu vi tam giác ABC biết AB = $$\frac{\sqrt{5}}{2}$$.

Chúng ta hãy biểu thị các mặt phẳng mà tam giác ABC được chiếu bởi P và Q (Hình 3). Rõ ràng, chúng ta có thể giả sử rằng một trong các đỉnh của tam giác, chẳng hạn như A, nằm trên cạnh chung R của các mặt phẳng P và Q. Vì các hình chiếu của cạnh AB và AC trên các mặt phẳng P và Q bằng nhau, nên các điểm A, B và C nằm trong mặt phẳng phân giác S của góc nhị diện được tạo bởi các mặt phẳng P và Q. Chúng ta biểu thị các hình chiếu của điểm B và C trên Q là D và E. Chúng ta thả đường cong phân phối lại BF từ điểm B xuống cạnh R, $\Rightarrow BFD = 45^\circ$.

Trong các tính toán tiếp theo, có thể không cố định độ dài của đoạn AB mà có thể coi nó là một giá trị a tùy ý. Trong trường hợp này, lời giải cũng có thể được hoàn thành. Nhưng ý nghĩa cụ thể này của $AB = \frac{\sqrt{5}}{2}$ cho phép thực thể đơn giản hóa lời giải.

Thật vậy, từ tam giác ABD ta tìm được: BD = $$\frac{1}{2} (\Rightarrow ADB = 90^\circ, AB и AD данные).$$ Vì $\Rightarrow BFD = 45^\circ$ nên FD = BD = $$\frac{1}{2}$$ và trong tam giác AFD ta có $\Rightarrow AFD = 90^\circ, \Rightarrow FAD = 30^\circ$. Từ đó, chúng ta luôn thu được AE ⊥ AF, $\Rightarrow CAE = 45^\circ, \Rightarrow CEA = 90^\circ, AC = \sqrt{2}$. Từ CBDE hình chữ nhật ta có $(CE - BD)^2 + DE^2 = BC^2$. Do đó BC = $$\frac{\sqrt{5}}{2}$$ và chu vi của tam giác ABC là $$\sqrt{5} + \sqrt{2}$$.

Nếu việc xem xét là bài toán dữ liệu số, thì

⟦folio 54⟧

Mặc dù số lượng phép tính đã giúp ích cho chúng ta, nhưng ngược lại, đôi khi chúng lại tạo ra những khó khăn trong tính toán và thậm chí che khuất ý nghĩa hình học đơn giản của bài toán.

Bài toán 4 (Khoa Địa lý, Đại học Tổng hợp Matxcơva, 1971). Cho tam giác ABC vẽ đường phân giác BD có AB = 3 cm, BC = 4 cm và AC = 5 cm. Tam giác ABD và BCD có các đường tròn nội tiếp tiếp xúc với BD lần lượt tại M và N. Tính độ dài đoạn MN.

Dữ liệu số của bài toán này cho thấy tam giác này là góc vuông. Điều này có thể dẫn đến việc cố gắng giải bài toán bằng cách sử dụng các tính chất hệ mét của một tam giác vuông.

Trên thực tế, bài toán có một hình học đơn giản lời giải cho tam giác ABC tùy ý. Chúng ta hãy ký hiệu AB là c, BC là a và AC là b (Hình 4). Theo tính chất phân giác, AD = \frac{bc}{a+c}, CD = \frac{ab}{a+c}.

Hãy đưa ra các ẩn số x = BM, y = MN và z = ND. Vì các tiếp tuyến kẻ từ một điểm đến đường tròn bằng nhau nên ta có thể xây dựng hệ phương trình sau:

$$\begin{cases} x + y + \left( \frac{ab}{a+c} - z \right) = a, \\ x + \left( \frac{bc}{a+c} - z - y \right) = c. \end{cases}$$

Trừ từ phương trình đầu tiên

bầy đàn, chúng ta sẽ có được

$$2y + \frac{ab}{a+c} - \frac{bc}{a+c} = a - c,$$

Ở đâu

$$y = \frac{1}{2} \frac{(a-c)(a+c-b)}{a+c}.$$

Thay giá trị của chúng vào a, b và c, ta thấy MN = \frac{1}{7}.

Bây giờ chúng tôi xem xét bài toán, trong đó dữ liệu số được chọn đặc biệt đơn giản hóa đáng kể lời giải bài toán.

Bài toán 5. Trong tam giác ABC có các cạnh AB = 4, AC = \sqrt{17} và BC = 5. Trên cạnh AB lấy điểm D, chứng tỏ AD = 1. Khoảng cách giữa tâm các đường tròn ngoại tiếp các tam giác ADC và DBC nằm ở trung điểm của các cạnh AC và BC, và khoảng cách cần tìm bằng độ dài đường giữa song song với AB, tức là 2 (Hình 5). CD đó có chiều cao suy ra từ đẳng thức

$$BC^2 - AC^2 = BD^2 - DA^2 = 8.$$

Làm thế nào người ta đồng ý rằng CD là chiều cao? Xét cho cùng, từ lời giải rõ ràng thỏa thuận này là điểm chính trong lời giải - tất cả những cân nhắc khác đều tầm thường. Chúng tôi không đồng

Hình 4.

Hình 5.

⟦folio 55⟧

Chúng tôi cố gắng (và không thể) giải thích cách đoán, nhưng nó chỉ ra một tình huống quan trọng. Chúng ta đang nói về một bản vẽ. Một bản vẽ được thực hiện cẩn thận và thành thạo là trợ thủ đắc lực cho lời giải bài toán. Điều này áp dụng cho mọi hình học bài toán, với cả dữ liệu số và chữ cái. Nếu dữ liệu là số thì các kích thước đã cho của hình sẽ được phản ánh trong bản vẽ. Ví dụ: nếu bạn tạo một bản vẽ bài toán đã được tháo rời theo các tỷ lệ đã cho, thì khá dễ dàng nhận thấy rằng CD là chiều cao.

Nhiệm vụ 6 (khoa địa chất của Đại học quốc gia Moscow, 1970). Cho ABCD biết các đáy AD = 39 cm, BC = 26 cm và các cạnh AB = 5 cm, CD = 12 cm. Tìm bán kính của đường tròn đi qua các điểm A và B và tiếp xúc với cạnh CD hoặc phần kéo dài của nó.

Hãy dựng hình thang thành tam giác AED (Hình 6). Từ sự đồng dạng của các tam giác BEC và AED ta dễ dàng thu được BE = 10 cm, CE = 24 cm. Nếu vẽ cẩn thận, bạn sẽ nhận thấy rằng $\angle AED = 90^\circ$: Điều này dễ chứng minh: $AE^2 + ED^2 = AD^2$. Gọi O là tâm đường tròn đi qua A và B và tiếp xúc ED tại điểm G. Từ O thả điểm chuyển tiếp OF sang AB thì F là trung điểm của dây AB. Rõ ràng OG = EF = 12,5 cm. Do đó bán kính cần tìm là 12,5 cm.

Trong các nhiệm vụ sau, dữ liệu số cho thấy trọng lượng của ánh sáng...

Hình 6.

Hình 7.

khác biệt. Với nghiên cứu sơ bộ về bài toán như vậy, rất khó để dự đoán chính xác những dữ liệu này sẽ ảnh hưởng như thế nào đến lời giải, nhưng một khi bạn bắt đầu giải bài toán, và tại một số thời điểm, bạn chỉ có thể nhận được đáp số với những dữ liệu này. Theo quy luật, trong những vấn đề như vậy, hãy để lời giải rất IDEN, mặc dù ngay từ đầu vẫn chưa rõ liệu nó có dẫn đến đáp số hay không.

Nhiệm vụ 7 (Khoa Sinh học Đại học Tổng hợp Matxcơva, 1970). Trên các cạnh của tứ giác lồi ABCD có diện tích bằng 1, lấy các điểm: K trên AB, L trên BC, M trên CD và N trên AD. Đồng thời $\frac{AK}{KB} = 2, \frac{BL}{LC} = \frac{1}{3}, \frac{CM}{MD} = 1, \frac{DN}{NA} = \frac{1}{5}$. Tìm diện tích hình lục giác AKLCMN.

Tỷ lệ diện tích của tam giác KBL và ABC là $\frac{BK \cdot BL}{AB \cdot BC} = \frac{1}{12}$ (Hình 7). Tỉ số diện tích của tam giác MND và ADC là $\frac{DN \cdot DM}{AD \cdot CD} = \frac{1}{12}$. Do đó, tổng diện tích của các tam giác KBL và MND là $\frac{1}{12}$ nên diện tích cần tìm là $\frac{11}{12}$.

Rõ ràng là bài toán như vậy nói chung không có lời giải duy nhất nào cả.

Nhiệm vụ 8 (Đại học Cơ khí và Toán học bang Ural, 1968). Ba điểm A, B, C nối trực tiếp

⟦folio 56⟧

đường moline. Liền kề đoạn đường AB là một thửa ruộng hình vuông có cạnh $\frac{1}{2} AB$. Đoạn đường BC tiếp giáp với một thửa ruộng hình vuông có cạnh bằng BC, đoạn đường CA tiếp giáp với một khu rừng hình chữ nhật có chiều dài bằng CA, chiều rộng 4 km. Diện tích rừng lớn hơn tổng diện tích 20 km2. Tìm diện tích của khu rừng.

Thoạt nhìn, có quá ít dữ liệu cho lời giải bài toán. Tuy nhiên, hãy chuyển sang tính toán. Gọi các cạnh của tam giác AB, BC và CA lần lượt là c, a, b. Khi đó từ điều kiện bài toán ta có: $4b = 20 + \frac{c^2}{4} + a^2$. Hãy sử dụng bất đẳng thức tam giác $b \leq a + c$ và thay b vào đó, biểu thị theo a và c:

$$\frac{1}{4}\left(20 + \frac{c^2}{4} + a^2\right) \leq a + c.$$

Sau khi biến đổi đơn giản bất đẳng thức này, chúng ta thu được: $\left(\frac{c}{2} - 4\right)^2 + (a - 2)^2 \leq 0$, từ đó $c = 8(\text{km})$, $a = 2(\text{km})$ và $b = a + c = 10(\text{km})$. Diện tích rừng là 40 km2.

Đường dẫn đã chọn lời giải là đường dẫn duy nhất có thể có trong bài toán đã cho. Nhưng những gì nó dẫn đến đáp số hóa ra lại là hệ quả của dữ liệu được chọn lọc đặc biệt. Kết quả của lựa chọn này là ba điểm A, B và C nằm trên cùng một đường thẳng và dữ liệu từ bài toán đủ để thu được đáp số.

Bài tập

1. (Cơ học và Toán học của Đại học quốc gia Moscow, 1969). Các hình chiếu hình chữ nhật của một tứ giác phẳng lên hai mặt phẳng vuông góc với nhau là các hình vuông có cạnh 2. Odan của các đường chéo của tứ giác là $\sqrt{14}$. Tìm một đường chéo khác.

2. Trong tam giác nhọn ABC, cho $AB = 15$, $BC = 10$ và góc BAC bằng arccos $\frac{7}{9}$. Một đường tròn ngoại tiếp tam giác ABC và vẽ dây BE đi qua điểm D nằm trên AC cách A một khoảng bằng 9. Tìm diện tích tam giác AEC.

3. Cho tam giác ABC có các cạnh 5, 2 và $\sqrt{22}$, với $AC = \sqrt{22}$. Lấy điểm D trên AC sao cho BD = 3. Tìm khoảng cách giữa điểm D và tâm đường tròn ngoại tiếp tam giác ABC.

4. (Khoa Vật lý, Đại học Tổng hợp Matxcova, 1971). Một hình cầu nội tiếp thành tam giác đều SABC có các cạnh bằng a. Trên cạnh SA lấy điểm M sao cho AM = MS, và lấy điểm N trên cạnh BC sao cho 2CN = NB. Hố MN cắt hình cầu tại hai điểm P và Q. Tìm độ dài đoạn PQ.

5. (Khoa Hóa học, Đại học Tổng hợp Matxcova, 1971). Cho tam giác ABC, đường trung tuyến BD kẻ từ cạnh AB = $\sqrt{3}$ cm, BC = = 4 cm, AC = $\sqrt{7}$ cm. Đường tròn nội tiếp tam giác ABD và BDC tiếp xúc với BD lần lượt tại các điểm M và N. Tính độ dài đoạn MN.

6. (Khoa Địa lý, Đại học quốc gia Mátxcơva, 1971). Hai đường tròn bán kính r tiếp xúc nhau. Ngoài ra, mỗi người trong số họ tiếp xúc từ bên ngoài vào một tam giác bán kính R tại các điểm A và B của tam giác tương ứng. Xác định bán kính r nếu AB = 12 cm, R = 8 cm.

7. (Khoa Sinh học Đại học Tổng hợp Matxcova, 1971). Tam giác đều ABC có cạnh bằng 3 nội tiếp trong một đường tròn. Điểm D nằm trên đường tròn và độ dài dây AD bằng $\sqrt{3}$. Tìm độ dài của dây BD và CD.

8. (Khoa Sinh học Đại học Quốc gia Mátxcơva, 1970). Cho tam giác ABC có diện tích bằng 1. Trên các đường trung tuyến AK, BL, CN của tam giác ABC lấy các điểm P, Q, R tương ứng sao cho

$$\frac{AP}{PK} = 1, \frac{BQ}{QL} = \frac{1}{2}, \frac{CR}{RN} = \frac{5}{4}.$$

Tìm diện tích tam giác PQR.

9. (Khoa Kinh tế Đại học Tổng hợp Mátxcơva, 1970). Thể tích của khối hình bình hành thẳng là 150 cm³, tổng diện tích toàn phần là 280 cm2, chu vi đáy là 40 cm. Tìm kích thước của khối.

10. (Khoa Kinh tế Đại học Tổng hợp Matxcova, 1971). Một quả cầu bán kính R được nội tiếp hai góc bằng 60°. Tìm bán kính của một quả bóng nội tiếp một góc và tiếp tuyến với quả bóng dango, biết rằng đường thẳng nối tâm của cả hai quả bóng tạo thành một góc 45° với cạnh ở hai góc.

11. Cho tam giác có cạnh AB = 4, BC = 3 và AC = 5. Lấy điểm D trên cạnh AB sao cho DB = $\frac{7}{8}$. Một đường tròn vẽ qua các điểm C, D, B và cắt AC tại điểm E. Tìm độ dài đoạn BE.
