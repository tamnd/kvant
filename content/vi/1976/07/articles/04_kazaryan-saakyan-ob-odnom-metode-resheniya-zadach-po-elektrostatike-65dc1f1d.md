---
id: 1976-7-kazaryan-saakyan-ob-odnom-metode-resheniya-zadach-po-elektrostatike-65dc1f1d
issue: kvant_1976_7
year: 1976
number: "7"
title: Về một phương pháp lời giải bài toán trong tĩnh điện
authors:
  - Казарян Э.
  - Саакян Р.
rubric: osnovnye-stati
page_first: 11
page_last: 15
page_labels: 9-13
tag: TUM2
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 39226b10cccc09751d4d9ba587dc38f5339339279eec6aa66920fa2611ef585f
prompt_sha256: draft-1
translated_from: content/ru/1976/07/articles/04_kazaryan-saakyan-ob-odnom-metode-resheniya-zadach-po-elektrostatike-65dc1f1d.md
source_content_sha256: 71fcfba5ac6235dfdb298d44eaac82b6b97df84d7f7a056fb30e5a472be7a0f0
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 9⟧

Khi nghiên cứu điện trường không đổi (không thay đổi theo thời gian) do dây dẫn tích điện tạo ra, trước hết cần lưu ý rằng hướng của điện trường bên trong dây dẫn bằng không. Ngay sau đó, điện tích trong dây dẫn được phân bố trên bề mặt của chúng. Vì vậy, bài toán kỹ thuật điện thường gắn liền với việc tìm ra điện trường bên ngoài dây dẫn và xác định sự phân bố điện tích trên bề mặt dây dẫn.

Hãy hình thành một số mạng điện điển hình bài toán.

Bài 1. Điện tích chính xác q nằm cách bề mặt của một vật dẫn hình cầu thay thế có bán kính r một khoảng d (Hình 1). Xác định điện tích q' cảm ứng trên bề mặt này.

Nhiệm vụ 2. Một điện tích q mạnh được đặt giữa hai quả cầu đồng tâm thay thế có bề mặt được tính toán có bán kính là r₁ và r₂ (Hình 2). Khoảng cách từ điện tích đến các bề mặt hình cầu bằng d₁ và d₂ tương ứng. Điện tích cảm ứng trên các quả cầu là q'₁ và q'₂.

Nhiệm vụ 3. Điện tích chính xác q nằm ở khoảng cách d₁ và d₂ tính từ các mặt phẳng vô hạn thay thế dẫn điện (Hình 3). Cụ thể là các điện tích q'₁ và q'₂ cảm ứng trên các mặt phẳng này.

Quan sát các phương pháp lời giải tương tự như bài toán được nghiên cứu trong phần tương ứng của toán vật lý, không có trong chương trình giảng dạy ở trường. Tuy nhiên, có một số phương pháp riêng tương đối đơn giản cho phép bạn giải bài toán trong lưới điện mà không vượt quá giới hạn của toán học cơ bản (ví dụ: phương pháp hình ảnh, đã được đề cập trong bài báo “Trường lưới điện” của G. Myakishev; xem «Kvant», 1975, số 4). Ở đây chúng ta sẽ xem xét một trong

⟦folio 10⟧

những phương pháp như vậy, dựa trên định lý (hoặc nguyên tắc) có đi có lại.

Bản chất của định lý này là gì? Nó có thể được phát biểu như sau: nếu trong một hệ gồm $n$ dây dẫn, không tồn tại dây dẫn $q_1, q_2, \dots, q_n$, có các điện tích $\varphi_1, \varphi_2, \dots, \varphi_n$, tương ứng và với các điện tích $q'_1, q'_2, \dots, q'_n$ các dây dẫn bằng $\varphi'_1, \varphi'_2, \dots, \varphi'_n$, thì đẳng thức là đúng

$$\sum_{i=1}^{n} q_i \varphi'_i = \sum_{i=1}^{n} q'_i \varphi_i.$$ (1)

Hãy để chúng tôi chứng minh rằng đây thực sự là trường hợp.

Theo nguyên lý chồng chất, điện thế của vật dẫn phụ thuộc tuyến tính vào điện tích. Hoặc ngược lại, điện tích trên dây dẫn phụ thuộc tuyến tính vào điện thế. Trước tiên chúng ta hãy xem xét một trường hợp đặc biệt—bên trong bề mặt dẫn điện nối đất có hai dây dẫn tích điện 1 và 2 (Hình 4). Hãy nối dây dẫn thứ hai với một dây dẫn nối đất, khi đó điện thế của dây dẫn này sẽ bằng 0 (xem Hình 4, a). Điện thế của dây dẫn thứ nhất được ký hiệu là $\varphi_1$. Điện tích trên mỗi dây dẫn phải tỷ lệ với $\varphi_1$, tức là

$$\Delta q_1 = C_{11} \varphi_1 \quad \text{и} \quad \Delta q_2 = C_{21} \varphi_1.$$ (2)

Ở đây $\Delta q_1$ và $\Delta q_2$ lần lượt là điện tích trên dây dẫn thứ nhất và thứ hai, còn $C_{11}$ và $C_{21}$ là các đại lượng không đổi gọi là hệ số điện dung và tùy thuộc vào hình dạng cũng như vị trí tương đối của dây dẫn. $C_{11}$ và $C_{21}$ đặc trưng cho điện tích của điện tích đầu tiên

$$q_i = C_{i1} \varphi_1 + C_{i2} \varphi_2 + \dots + C_{in} \varphi_n = \sum_{k=1}^{n} C_{ik} \varphi_k \quad (i=1, 2, \dots, n).$$ (3)

Ở đây, hệ số điện dung $C_{ik}$ đặc trưng cho điện tích của dây dẫn thứ $i$, khi tất cả các dây dẫn ngoại trừ dây dẫn thứ $k$

⟦folio 11⟧

Cơm. 5.

được nối đất và điện thế của dây dẫn thứ $k$ bằng 1. Giả sử điện tích của dây dẫn thứ $i$ bằng $q'_i$ và điện thế của nó $\varphi'_i$. Chúng ta hãy nhân số hạng đẳng thức (4) với $\varphi'_i$:

$$q'_i \varphi'_i = \sum_{k=1}^{n} C_{ik} \varphi_k \varphi'_i,$$

rồi tính tổng cả hai vế của đẳng thức thu được trên tất cả các giá trị của $i$ từ 1 đến $n$:

$$\sum_{i=1}^{n} q'_i \varphi'_i = \sum_{i,k=1}^{n} C_{ik} \varphi_k \varphi'_i.$$

Nhưng

$$\sum_{i,k=1}^{n} C_{ik} \varphi_k \varphi'_i = \sum_{i,k=1}^{n} C_{ik} \varphi'_i \varphi_k = \sum_{i=1}^{n} q'_i \varphi'_i$$

(vì $i$ và $k$ lấy tất cả các giá trị từ 1 đến $n$), nên cuối cùng chúng ta nhận được

$$\sum_{i=1}^{n} q'_i \varphi'_i = \sum_{i=1}^{n} q'_i \varphi'_i.$$

Như vậy, định lý tương hỗ đã được chứng minh, vì đẳng thức (1) và (5) giống hệt nhau.

Trước khi áp dụng định lý tương hỗ cho công thức lời giải bài toán ở trên, hãy xem xét hai bài toán bổ sung.

Bổ sung bài toán 1. Có một hệ thống dây dẫn, tất cả chúng, ngoại trừ $i$, đều được nối đất và dây dẫn thứ $i$ có ​​điện áp sử dụng $\varphi'_i$ (Hình 5). Tại một số điểm $A$ của hệ thống, công suất bằng $\varphi$. Xác định điện tích $q'_i$ cảm ứng

$$q \varphi + q'_i \varphi'_i = 0,$$

Ở đâu

$$q'_i = -q \frac{\varphi}{\varphi'_i}.$$

Bổ sung bài toán 2. Trong bề mặt dẫn điện kín 1, chúng ta đặt tủ ngăn kéo $\varphi_1$, chúng ta tìm thấy dây dẫn 2 (Hình 6). Chúng ta đặt điểm này bằng $\varphi_2$ và đặt điểm $A$, nằm giữa các dây dẫn, bằng $\varphi$. Tìm điện tích $q'_1$ và $q'_2$ sinh ra trên dây dẫn nếu dây dẫn được nối đất và đặt điện tích $q$ tại điểm $A$.

⟦folio 12⟧

Chúng ta có hai trạng thái của hệ thống:
a) điện tích tại điểm $A$ bằng 0, điện thế của nó là $q$, và điện thế của các vật dẫn là $\varphi_1$ và $\varphi_2$ (xem Hình 6, a);
b) điện tích tại điểm $A$ bằng $q$, điện thế của các vật dẫn bằng 0 và điện tích cảm ứng trên chúng bằng $q'_1$ và $q'_2$ (xem Hình 6, b).

Để đơn giản, ở đây và xa hơn chúng ta sẽ nói về điện tích và thế năng $A$, ngụ ý rằng có một vật dẫn tại điểm này (như đã làm ở bài toán 1).

Theo định lý tương hỗ
$$q'_1 \varphi_1 + q'_2 \varphi_2 + q \varphi = 0. \tag{6}$$

Tất nhiên, chỉ từ đẳng thức này thì không thể tìm được cả hai điện tích cảm ứng. Tuy nhiên, chúng ta cũng có thể sử dụng điều kiện là độ dẫn điện $1$ được thay thế trong trường hợp thứ hai. Điều này có nghĩa là không có điện trường bên ngoài, nghĩa là tổng đại số của tất cả các điện tích nằm bên trong chất dẫn điện thay thế bằng 0, tức là.
$$q'_1 + q'_2 + q = 0. \tag{7}$$

Giải các phương trình (6) và (7) cùng nhau, ta thu được
$$q'_1 = q \frac{\varphi_2 - \varphi}{\varphi_1 - \varphi_2}$$
Và
$$q_2 = -q \frac{\varphi_1 - \varphi}{\varphi_1 - \varphi_2}.$$

Bây giờ chúng ta có thể quay lại nhiệm vụ chính. Đối với lời giải của họ, chúng tôi sẽ sử dụng định lý có đi có lại. Phương pháp áp dụng định lý này có phần hình thức nhưng rất đơn giản và thuận tiện. Toàn bộ khó khăn chỉ nằm ở việc lựa chọn một cách khôn ngoan hai trạng thái của hệ thống đang được xem xét và viết ra sự bằng nhau (1) cho chúng.

Lời giải bài toán 1. Theo điều kiện bài toán điện tích chính xác $q$ nằm ở một khoảng nhất định so với quả cầu dẫn điện được thay thế nơi đặt điện tích $q'$ (tương ứng 1).

Giả sử rằng bề mặt hình cầu không bị thay thế và có điện thế $\varphi_0$, nhưng điện tích $q$ thì không. Khi đó ở vị trí của nó điện thế trường bằng
$$\varphi = \varphi_0 \frac{r}{r + d} (r - \text{радис сферической поверхности}, d - \text{расстояние от заряда } q \text{ до этой поверхности}).$$ Đây là trạng thái thứ hai của hệ thống.

Chúng ta hãy viết định lý tương hỗ cho hai trạng thái này của hệ thống:
$$q \varphi + q' \varphi_0 = 0,$$
hoặc
$$q' = -q \frac{\varphi}{\varphi_0} = -q \frac{r}{r + d}.$$

Kết quả thu được có thể áp dụng cho trường hợp điện tích $q'$ nằm trên mặt phẳng dẫn vô hạn. Thật vậy, một mặt phẳng vô hạn có thể được coi là một bề mặt hình cầu có bán kính lớn vô hạn, tức là
$$r \rightarrow \infty.$$ Do đó, trong giới hạn tại $r \rightarrow \infty$ ta có
$$q' = -q \frac{r}{r + d} = -q \frac{1}{1 + d/r} = -q,$$
nghĩa là, điện tích cảm ứng trên một mặt phẳng vô hạn có giá trị bằng nhau, nhưng ngược lại về giá trị từ điểm này sang điểm khác, bất kể điện tích này nằm ở đâu.

Lời giải bài toán 2. Theo điều kiện bài toán, trạng thái đầu tiên của hệ thống như sau: điện tích $q$ nằm tại một điểm nhất định giữa các dây dẫn hình cầu thay thế nơi đặt điện tích $q'_1$ và $q'_2$.

Ở trạng thái thứ hai, chúng ta hãy xem xét trường hợp khi quả cầu bên ngoài được thay thế, quả cầu bên trong có điện thế $\varphi_1$, điện tích $q$ không có, nhưng ở vị trí của nó thì điện thế trường là $q$.

Dựa trên lời giải bổ sung bài toán 1, chúng tôi nhận được
$$q'_1 = -q \frac{\varphi}{\varphi_1}. \tag{8}$$

⟦folio 13⟧

Cơm. 7.

Chúng ta tìm thấy điện tích $q'_2$ cảm ứng trên quả cầu bên ngoài với điều kiện tổng đại số của các điện tích nằm bên trong bề mặt nối đất bằng 0:

$$q'_1 + q'_2 + q = 0.$$ (9)

Vì vậy, chúng ta chỉ cần tìm mối quan hệ $\varphi/\varphi_1$. Giả sử rằng khi quả cầu bên ngoài nối đất và quả cầu bên trong có điện thế $\varphi_1$ thì điện tích trên quả cầu bên trong là $q_0$. Rõ ràng là trong trường hợp này một điện tích $-q_0$ sẽ được tạo ra ở quả cầu bên ngoài. Hãy để chúng tôi biểu thị tiềm năng $\varphi$ và $\varphi_1$ dưới dạng điện tích $q_0$ và $-q_0$:

$$\varphi = \frac{q_0}{r_1 + d_1} + \frac{-q_0}{r_2},$$

$$\varphi_1 = \frac{q_0}{r_1} + \frac{-q_0}{r_2}.$$ (10)

Cuối cùng từ đẳng thức (8) – (10) ta thu được:

$$q'_1 = -q \frac{r_1 d_2}{(r_1 + d_1)(d_1 + d_2)},$$

$$q'_2 = -q \frac{r_2 d_1}{(r_1 + d_1)(d_1 + d_2)}.$$

Lời giải bài toán 3. Nó theo ngay sau lời giải bài toán 2, vì hai mặt phẳng vô hạn song song có thể

Cơm. 8.

coi chúng là hai mặt cầu đồng tâm có bán kính vô cùng lớn.

Hãy viết kết quả lời giải bài toán 2 dưới dạng:

$$q'_1 = -q \frac{r_1 d_2}{(r_1 + d_1)(d_1 + d_2)} = -q \frac{d_2}{(1 + d_1/r_1)(d_1 + d_2)},$$

$$q'_2 = -q \frac{r_2 d_1}{(r_1 + d_1)(d_1 + d_2)} = -q \frac{d_1}{(1 - d_2/r_2)(d_1 + d_2)}.$$

Nếu $r_1 \to \infty$ và $r_2 \to \infty$ thì

$$q'_1 = -q \frac{d_2}{d_1 + d_2},$$

$$q'_2 = -q \frac{d_1}{d_1 + d_2}.$$

Bài tập

1. Tâm của quả bóng không tồn tại $q$ nằm ở khoảng cách $a$ tính từ tâm của một dây dẫn hình cầu nối đất có bán kính $r$ (Hình 7). Xác định điện tích $q'$ gây ra trên quả bóng được nối đất.

2. Trong hai dây dẫn hình cầu đồng tâm, bán kính của chúng là $r_1$ và $r_2$ ($r_1 < r_2$), dây dẫn bên trong được nối đất và dây dẫn bên ngoài có điện tích $q$ (Hình 8). Tìm điện tích $q'$ cảm ứng trên quả cầu bên trong.
