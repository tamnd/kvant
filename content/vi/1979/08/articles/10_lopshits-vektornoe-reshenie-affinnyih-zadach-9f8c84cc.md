---
id: 1979-8-lopshits-vektornoe-reshenie-affinnyih-zadach-9f8c84cc
issue: kvant_1979_8
year: 1979
number: "8"
title: Vectơ lời giải affine bài toán
authors:
  - Лопшиц А. М.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 32
page_last: 35
page_labels: 30-33
tag: QZ3X
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c49098c82f018c8d71eeb74f12b7184228fccbce4dcc0400ccaa6e7429e4e2d9
prompt_sha256: draft-1
translated_from: content/ru/1979/08/articles/10_lopshits-vektornoe-reshenie-affinnyih-zadach-9f8c84cc.md
source_content_sha256: 2d0eb0bcb2d06500dce796a43211d48ee00c4f69edfe38cea6479fc67dd04570
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 30⟧

Vector lời giải ảnh hưởng bài toán

Trong bài học vòng tròn toán học này, chúng ta sẽ học cách giải hình học bài toán của một loại nhất định - cái gọi là afficine bài toán. Đầu tiên chúng tôi sẽ không giải thích bài toán này là gì. Chúng tôi hy vọng rằng sau khi đọc bài viết bạn sẽ hiểu điều này.

1. Phiên bản tình cảm của định lý Morley

Trong «Kvant» Số 8 năm 1978 (trang 28), định lý đáng chú ý sau đây đã được xem xét: nếu trong tam giác ABC vẽ các đường ba góc A, B và C, thì giao điểm của chúng, gần các cạnh, là các đỉnh của một tam giác đều. Điều gì xảy ra nếu trisecgris được thay thế bằng tris, nghĩa là các đường thẳng đi qua các đỉnh của tam giác và chia các cạnh đối diện của nó thành ba phần bằng nhau? Hóa ra... Tuy nhiên, người đọc thực sự sẽ tự mình xây dựng xong định lý, tìm ra tính chất của tam giác $P_{14}P_{36}P_{25}$ (ký hiệu dễ truyền đạt, nói

Cơm. 1

Tham khảo Hình 1), hãy chắc chắn rằng các cạnh của lục giác $P_{13}P_{46}P_{15}P_{24}P_{35}P_{26}$ song song với các cạnh của tam giác ban đầu ABC, và cuối cùng chứng minh rằng trung điểm của cạnh lục giác này và các điểm $P_{36}, P_{23}, P_{25}, P_{45}, P_{14}, P_{61}$ nằm trên ba đường thẳng. Nếu bạn chưa hiểu cách giải quyết vấn đề này bài toán, đừng lo lắng. Sau khi đọc bài viết, bạn chắc chắn sẽ có thể làm được điều này. Hãy bắt đầu với bài toán đơn giản hơn.

2. Cảm động bài toán Lewis Carroll

Áp chót bài toán của bộ sưu tập “Ngày trả lương bài toán, được phát minh trong những giờ mất ngủ” *) yêu cầu viết một hình lục giác trong một tam giác nhất định sao cho các cạnh đối diện của nó bằng nhau và song song, ba trong số chúng nằm trên các cạnh của tam giác và các đường chéo giao nhau tại một điểm nhất định bên trong tam giác. Lời giải, do Carroll đưa ra, sử dụng phương tiện dành cho một học sinh thời cổ đại đó (thập niên tám mươi đã trôi qua nhiều thế kỷ). Chúng ta sẽ xem xét công thức tổng quát hơn của bài toán của Carroll và giải nó bằng cách sử dụng một công cụ quen thuộc với một học sinh hoàn hảo từ lớp bảy - trong đó. Tất nhiên, bài toán của Carroll không khó giải quyết chút nào nếu không có sự giúp đỡ của họ. Nhưng chính vì nó không khó nên bạn học tốt từ nó!

Chúng ta sẽ giải Carroll's bài toán theo công thức sau: trên các đường thẳng chứa các cạnh BC, CA và AB của tam giác ABC, lần lượt đặt các điểm $A_1$ và $A_2$, $B_1$ và $B_2$, $C_1$ và $C_2$ sao cho các đỉnh đối diện của lục giác $A_1A_2B_1B_2C_1C_2$ (tức là, các điểm $A_1$ và $B_2$, $A_2$ và $C_1$, $B_1$ và $C_2$) đối xứng với điểm P, được xác định tùy ý trong mặt phẳng của tam giác ABC (Hình 2) **). (Hình lục giác như vậy được gọi là trung tâm.)

*) Lewis Carroll. Câu chuyện với những nút thắt (M., Mir, 1973).
**) Đây là tính tổng quát lớn trong công thức của chúng ta - Carroll tin rằng điểm P nằm bên trong tam giác ABC.

⟦folio 31⟧

3. Phân tách vectơ

Chúng ta sẽ cần thực tế sau: nếu các vectơ $\vec{a}$ và $\vec{b}$ không thẳng hàng thì bất kỳ vectơ $\vec{c}$ nào nằm trong cùng mặt phẳng với các vectơ $\vec{a}$, $\vec{b}$ đều có thể được biểu diễn dưới dạng

$$\vec{c} = \alpha \vec{a} + \beta \vec{b}$$

(ở đây $\alpha$ và $\beta$ là số thực) và cách biểu diễn như vậy là duy nhất (xem định lý từ § 23 của “Hình học 9”).

Chúng ta sẽ gọi biểu diễn này là sự phân rã của vectơ $\vec{c}$ thành các vectơ $\vec{a}$ và $\vec{b}$ (Hình 3).

Lưu ý rằng nếu $O$ là một điểm cố định của mặt phẳng thì vectơ $\overrightarrow{OM}$ có ​​thể được dựng tại bất kỳ điểm $M$ nào của mặt phẳng. Điểm $O$ được gọi là cực, vectơ $\overrightarrow{OM}$ là vectơ bán kính của điểm $M$. Vectơ bán kính $\overrightarrow{OM}$ xác định duy nhất điểm “của chính nó” $M$; chúng tôi sẽ ký hiệu nó bằng $\overrightarrow{M}$ để cho ngắn gọn.

4. Lời giải bài toán Carroll

Chúng ta hãy chọn đỉnh $C$ của tam giác này làm cực.

Vectơ bán kính của một điểm cho trước $P$ sẽ bị phân tách thành vectơ $\vec{A}$ và $\vec{B}$:

$$\vec{P} = \alpha \vec{A} + \beta \vec{B}.$$

Vì điểm yêu cầu $A_1$ nằm trên đường $CB$ (Hình 2),

$$\vec{A}_1 = x\vec{B},$$

trong đó $x$ là phân số mà điểm $A_1$ “cắt đứt” khỏi đoạn được định hướng $\overrightarrow{CB}$. Chúng tôi đặt từ “cắt đứt” trong dấu ngoặc kép vì điểm $A_1$ không nhất thiết phải nằm trong đoạn $CB$; nó có thể “cắt đứt” ngay cả một “chia sẻ” tiêu cực (trong trường hợp này là $x < 0$). Tương tự, với điểm mong muốn $B_2$, chúng ta thu được

$$\vec{B}_2 = y\vec{A}$$

(ở đây $y$ là phân số mà điểm mong muốn “cắt đứt” khỏi đoạn được định hướng $\overrightarrow{CA}$). Từ thực tế rằng điểm $P$ là trung điểm của đoạn $A_1B_2$, suy ra (§ 22 “Hình học 9”)

$$\vec{P} = \frac{1}{2} (\vec{A}_1 + \vec{B}_2),$$

đó là

$$\alpha \vec{A} + \beta \vec{B} = \frac{1}{2} (x\vec{B} + y\vec{A}),$$

Ở đâu

$$x = 2\beta, y = 2\alpha$$

và do đó

$$\vec{A}_1 = 2\beta\vec{B}, \quad \vec{B}_2 = 2\alpha\vec{A}.$$

Những đẳng thức này cho phép chúng ta xây dựng các điểm $A_1$ và $B_2$.

Việc tìm các điểm $B_1$ và $C_2$ khó hơn một chút. Nếu điểm $B_1$ cắt phần $z$ khỏi đoạn được định hướng $\overrightarrow{CA}$ thì

$$\vec{B}_1 = z\vec{A}.$$

Bây giờ chúng ta hãy soạn một biểu thức cho vectơ bán kính của điểm $C_2$, cắt phân số $u$ khỏi đoạn có hướng $\overrightarrow{AB}$:

$$\vec{AC}_2 = u\vec{AB}.$$

Hãy sử dụng thực tế là $\vec{AC}_2 = \vec{C}_2 - \vec{A}$; $\vec{AB} = \vec{B} - \vec{A}$. Do đó $u(\vec{B} - \vec{A}) = \vec{C}_2 - \vec{A}$ và do đó $\vec{C}_2 = \vec{A} + u(\vec{B} - \vec{A}) = (1 - u)\vec{A} +$

⟦folio 32⟧

+ $u\vec{B}$. Theo điều kiện
$$P = \frac{1}{2} (\vec{B}_1 + \vec{C}_2),$$
đó là
$$\alpha \vec{A} + \beta \vec{B} = \frac{1}{2} [z\vec{A} + (1 - u)\vec{A} + u\vec{B}]$$
và do đó
$$u = 2\beta, z = 2\alpha + 2\beta - 1$$
$$\vec{B}_1 = (2\alpha + 2\beta - 1)\vec{A},$$
$$\vec{C}_2 = (1 - 2\beta)\vec{A} + 2\beta\vec{B}.$$
Thực hiện giai đoạn cuối cùng một cách độc lập, người đọc sẽ bị thuyết phục rằng
$$\vec{A}_2 = (2\alpha + 2\beta - 1)\vec{B},$$
$$\vec{C}_1 = 2\alpha\vec{A} + (1 - 2\alpha)\vec{B}.$$
Do đó, chúng tôi đã phát hiện ra rằng bài toán của Carroll có lời giải (tuy nhiên $P!$ được xác định) và lời giải là duy nhất:
$$\begin{cases} \vec{A}_1 = 2\beta\vec{B}, \vec{A}_2 = (2\alpha + 2\beta - 1)\vec{B} \\ \vec{B}_1 = (2\alpha + 2\beta - 1)\vec{A}, \vec{B}_2 = 2\alpha\vec{A} \\ \vec{C}_1 = 2\alpha\vec{A} + (1 - 2\alpha)\vec{B}, \vec{C}_2 = \\ = (1 - 2\beta)\vec{A} + 2\beta\vec{B} \end{cases}$$

5. Lạc đề từ bài toán Carroll.
Đạo hàm của công thức cho $\vec{C}_2$ thực sự chứng minh kết quả tổng quát sau: nếu $\vec{A}$ và $\vec{B}$ là vectơ bán kính của các điểm tùy ý $A$ và $B$ (so với chính sách được chọn tùy ý $C!$), thì vectơ bán kính $\vec{M}$ của điểm thuộc đường thẳng $AB$ và cắt bỏ Phần “chia sẻ” $\lambda$ từ đoạn được định hướng $\vec{AB}$, tức là điểm $M$, trong đó $\vec{AM} = \lambda\vec{AB}$ (Hình 4), được xác định bằng một công thức đơn giản và đẹp mắt:
$$\vec{M} = (1 - \lambda)\vec{A} + \lambda\vec{B}.$$ (!!)
Cần ghi nhớ công thức này - nó có ứng dụng tuyệt vời cho người dùng cho lời giải nhiều hình học bài toán *).

*) Xem bài viết của V. Boltyansky “Ba điểm trên một đường thẳng” («Kvant», 1978, số 10) và bài viết của I. Gabovich “Vector giúp làm bài thi” («Kvant», 1979, số 1).

Cơm. 4.
Số $\lambda$ được gọi là tọa độ affine của điểm $M$ (so với hệ tọa độ được chỉ định bởi $A$ ban đầu và vectơ tỷ lệ $\vec{AB}$). Tên này được xác định: xét cho cùng, nếu cho trước một hệ tọa độ và một số tùy ý $\lambda$, thì điểm $M$ trên đường thẳng $AB$ được xác định duy nhất:
$$\vec{AM} = \lambda\vec{AB}.$$
Hãy quay trở lại công thức
$$\vec{P} = \alpha\vec{A} + \beta\vec{B},$$
với sự trợ giúp của nó, chúng ta đã viết ra vectơ bán kính của điểm $P$ nằm trong mặt phẳng của tam giác $ABC$. Nó cho thấy rằng việc chỉ định một cặp số có thứ tự tùy ý $\alpha$, $\beta$ sẽ xác định điểm $P$ trong mặt phẳng $ABC$, nếu điểm $C$ và các vectơ $\vec{CA}$ và $\vec{CB}$ cho trước (Hình 5).
Những số này được gọi là tọa độ affine của điểm $P$ (trong hệ tọa độ có gốc là điểm $C$ và vectơ tỷ lệ là $\vec{CA}$ và $\vec{CB}$). Dễ dàng nhận thấy các điểm của mặt phẳng $ABC$ có tọa độ thứ hai bằng 0 nằm trên đường thẳng $CA$; do đó nó được gọi là trục tọa độ đầu tiên. Tương tự, những điểm có tọa độ đầu tiên bằng 0 nằm trên

⟦folio 33⟧

6. Các trường hợp đặc biệt của bài toán Carroll

1) Nếu điểm $P$ là trọng tâm của tam giác $ABC$ (tức là giao điểm của các đường trung tuyến của nó), thì (§ 22 “Hình học 9”)
$$\overrightarrow{OP} = \frac{1}{3} (\overrightarrow{OA} + \overrightarrow{OB} + \overrightarrow{OC})$$
và do đó
$$\bar{P} = \frac{1}{3} \bar{A} + \frac{1}{3} \bar{B},$$
đó là
$$\alpha = \frac{1}{3}, \quad \beta = \frac{1}{3}.$$
Thay thế các giá trị này vào công thức (1), chúng ta thu được $\bar{A}_1 = \frac{2}{3} \bar{B},$
$$\bar{A}_2 = \frac{1}{3} \bar{B}, \quad \bar{B}_1 = \frac{1}{3} \bar{A}, \quad \bar{B}_2 = \frac{2}{3} \bar{A},$$
$$\bar{C}_1 = \frac{2}{3} \bar{A} + \frac{1}{3} \bar{B}, \quad \bar{C}_2 = \frac{1}{3} \bar{A} + \frac{2}{3} \bar{B}$$
và do đó (do những gì đã nói ở đoạn trước), các đỉnh của hình lục giác tìm thấy bị cắt khỏi các cạnh của tam giác $\frac{1}{3}$ và $\frac{2}{3}$.

2) Cho $P$ là điểm bất kỳ của đoạn $B'C'$ nối trung điểm $B'$ và $C'$ hai cạnh CA và AB. Vì điểm này nằm bên trong đoạn $B'C'$, nên nó cắt phần $0 < \lambda < 1$ khỏi đoạn đó và nhờ công thức (!!),
$$\bar{P} = (1 - \lambda) \bar{B}' + \lambda \bar{C}'$$
$$\bar{P} = \frac{1 - \lambda}{2} \bar{A} + \frac{\lambda}{2} (\bar{A} + \bar{B})$$

đó là
$$\alpha = \frac{1}{2}, \quad \beta = \frac{\lambda}{2}.$$
Thay thế các giá trị này vào công thức (1), chúng ta thu được
$$\bar{A}_1 = \lambda \bar{B}, \quad \bar{A}_2 = \lambda \bar{B}, \quad \bar{B}_1 = \lambda \bar{A}, \quad \bar{B}_2 = \bar{A},$$
$$\bar{C}_1 = \bar{A}, \quad \bar{C}_2 = (1 - \lambda) \bar{A} + \lambda \bar{B}.$$
Do đó, trong trường hợp này, hình lục giác $A_1A_2B_1B_2C_1C_2$ suy biến thành hình bình hành $A_1A_1B_1AAC_2 = A_1B_1AC_2$ (Hình 6 được lập cho trường hợp khi $\lambda = \frac{4}{5}$).

3) Nếu điểm $P$ nằm tùy ý trên đường $B'C'$ trong không phải đoạn $B'C'$, thì tọa độ affine của nó $\lambda$ (trong hệ tọa độ có gốc tại điểm $C'$ và vectơ tỷ lệ $\overrightarrow{B'C'}$) là số dương lớn hơn một hoặc là số âm. Tất nhiên, vectơ bán kính của các đỉnh của hình lục giác dựng được xác định theo cùng các công thức như trong trường hợp tổng quát, tuy nhiên, các đỉnh này - người đọc sẽ tự thấy điều này - mặc dù nằm trên các đường thẳng AB, BC và CA, sẽ nằm ngoài các đoạn AB, BC, CA (trong Hình 7 $\lambda = \frac{5}{4}$).

4) Nếu điểm $P$ được chọn ở giữa $A'$ của đoạn BC, nghĩa là, nếu $\bar{P} = \frac{1}{2} \bar{B}$ và do đó, $\alpha = 0, \quad \beta = \frac{1}{2}$, thì nhờ các công thức
