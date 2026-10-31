---
id: 1983-5-nesterenko-nikishin-ocherk-o-tsepnyih-drobyah-0674202c
issue: kvant_1983_5
year: 1983
number: "5"
title: Tiểu luận về phân số tiếp tục
authors:
  - Нестеренко Ю. В.
  - Никишин Е. М.
rubric: osnovnye-stati
page_first: 18
page_last: 21
page_labels: 16-19
tag: B4WE
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 8d14471e66b7b7176e6255207af229d4f78675dd70580e493af0896ef577e43d
prompt_sha256: draft-1
translated_from: content/ru/1983/05/articles/05_nesterenko-nikishin-ocherk-o-tsepnyih-drobyah-0674202c.md
source_content_sha256: dee0d5af84009ccedab00f6f433f5b635dd5ed008082e761dce55a79555d442f
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 16⟧

Tiểu luận
về phân số tiếp tục

Ứng viên Khoa học Vật lý và Toán học
Y. V. NESTERENKO,
Tiến sĩ Vật lý và Toán học
E. M. NIKISHIN

Có rất nhiều ví dụ khi một hướng đi khoa học, được coi là đầy hứa hẹn và quan trọng, đã không đáp ứng được những hy vọng đặt ra cho nó; Dần dần, có một luồng lực lượng khoa học chảy ra từ nó, và bản thân phương hướng này đã mất đi sự phù hợp. Một trong những lĩnh vực này trong toán học là lý thuyết về phân số tiếp tục (hoặc tiếp tục). Cho đến cuối thế kỷ trước, các phân số liên tục thuộc nhiều loại khác nhau thường xuất hiện trong các công trình toán học. Trong thế kỷ trước và sớm hơn một chút, các định lý quan trọng về phân số liên tục đã được chứng minh. Người ta hy vọng rằng nếu chúng ta có thể hiểu được cấu trúc của các phân số liên tục thì có thể thu được những kết quả mới trong lý thuyết số và phân tích toán học. Hy vọng chỉ được chứng minh một phần, và sau đó toán học, đặc biệt là trong lĩnh vực lý thuyết số, tiếp tục đi trên những con đường mới khiến các lý thuyết bài toán về phân số liên tục bị gạt sang một bên.

Nhưng dẫu sao đi nữa, cũng giống như Dải phía Bắc đã chấp nhận những kẻ chinh phục nó, với công thức đơn giản, các bài toán dễ nhìn về phân số liên tục đã thu hút các nhà toán học, buộc họ phải tìm kiếm đi tìm lại các hình mẫu của vật thể kỳ lạ này. Nhiều câu hỏi quan trọng trong toán học và vật lý hiện đại dẫn đến những đối tượng như phân số tiếp tục. Do đó, các phương pháp nghiên cứu mà họ dựa vào hóa ra lại hữu ích trong nhiều vấn đề. Ở đây chúng ta sẽ chỉ đề cập đến những vấn đề liên quan đến lý thuyết số, nơi trên thực tế đã nảy sinh lý thuyết về phân số liên tục.

Lịch, bánh răng và một chút lịch sử

Một năm có bao nhiêu ngày? Ai cũng biết năm thường có 365 ngày, năm cao có 366 ngày. Những năm có số chia hết cho 4 được khai báo là năm nhuận, ví dụ 1904, 1908, ..., 1980, 1984, ..., 1996. Tuy nhiên, các năm 1800, 1900, 2100, 2200 được khai báo không cao nhưng các năm 2000, 2400, 2800 sẽ là năm nhuận. Tại sao?

Cơ chế của lịch khá đơn giản. Trái đất quay đều quanh trục của nó, thực hiện một vòng mỗi ngày. Một vòng Trái đất quay quanh Mặt trời là một năm và năm nay bằng 365,24219878... ngày. Tất nhiên, chúng ta có thể nói rằng việc cộng thêm 0,242... ngày là nhỏ. Tuy nhiên, theo thời gian nó nóng lên nếu bạn đặt một năm bằng 365 ngày. Vào thời cổ đại, khi kiến ​​thức về một năm dài trong một ngày rất gần đúng, sai số ngày càng tăng lên đến mức độ máy chủ. Vì vậy, ở Rome vào năm 46 trước Công nguyên. đ. Việc tồn đọng là 90 ngày!

Để thiết lập mô hình năm bình thường và năm cao điểm trong lịch, bạn cần chọn độ dài của chu kỳ $q$ (sau đó tất cả các năm cao điểm được lặp lại) và số $p$ năm cao điểm trong chu kỳ. Chúng ta hãy viết các giá trị của năm dưới dạng $365+\alpha$, trong đó $\alpha=0,242...$. Các số tự nhiên $p$ và $q$ phải được chọn sao cho các giá trị

$$\beta = q\alpha - p$$

càng nhỏ càng tốt, trong khi $p$ và $q$ không lớn lắm. Trên thực tế, chỉ có thể chọn số tự nhiên $q$, trong khi số $p$ là số nguyên gần với $q\alpha$. Rồi sau $q$ năm $365q+p$ ngày sẽ trôi qua. Từ sự bình đẳng $365q+p=q(365+\alpha)-\beta$ suy ra rằng trong thời gian này Trái đất sẽ tạo ra

$$q - \frac{\beta}{365+\alpha} \approx q$$

⟦folio 17⟧

các cuộc cách mạng quanh Mặt Trời. Lỗi trong một ngày sẽ chỉ xảy ra trong $\frac{1}{\beta}$ chu kỳ như vậy hoặc $\frac{q}{\beta}$ năm.

Trong lịch Gregory mà chúng ta đang sống, $q=400$ năm được coi là độ dài chu kỳ. Trong số những năm này, 303 năm là bình thường và 97 năm là cao. Những năm chia hết cho 4 được tuyên bố là năm nhuận, ngoại trừ những năm có số hàng trăm cũng chia hết cho 4. Như vậy, thời gian trung bình của một năm theo lịch Gregory là 365,242500 ngày,

Một lỗi trong một ngày sẽ xảy ra trong khoảng 3300 năm. Độ chính xác này khá thỏa đáng. Thậm chí có thể đạt được độ chính xác cao hơn bằng cách sử dụng $q=128$ và $p=31$, nhưng thiết kế chu kỳ 128 năm của lịch gây bất tiện khi sử dụng.

Điều quan trọng đối với chúng ta trong trường hợp này là lỗi toán học bài toán: cho số $n$, hãy tìm $p$ và $q$, nếu có thể sao cho số $\frac{p}{q}$ xấp xỉ giá trị đã cho $\omega$ (tỷ lệ vận tốc góc mong muốn) tốt nhất có thể. Rõ ràng là từ các tin nhắn tiết kiệm, người ta nên chọn $p$ và $q$ càng ít càng tốt.

Có thể tăng danh sách các ví dụ dẫn chúng ta đến bài toán phép tính gần đúng hiện có của các số thực bằng cách sử dụng số hữu tỷ. Ví dụ, cấu trúc thang âm, ứng dụng trong toán học tính toán, trong các vấn đề lý thuyết của cơ học thiên thể, v.v.

Phân số liên tục chính xác là một công cụ, theo một nghĩa nào đó, cung cấp các phép tính gần đúng thực sự cho các số hữu tỉ. Những phân số này cho mục đích tính toán bắt đầu từ

2 «Kvant» № 5

thay đổi trong một thời gian dài. Ngay từ năm 1572, nhà toán học và kỹ sư người Ý R. Bombelli (1526? - 1572) đã sử dụng chúng để tính $\sqrt{13}$. Sau đó, người Anh W. Brounker (1620-1684) đã sử dụng chúng để dạy số $n$. H. Huygens (1629-1695), một nhà vật lý, thiên văn học, toán học xuất sắc (người phát minh ra đồng hồ từ), là người đầu tiên chỉ ra rằng, khi sử dụng các phân số liên tục, chúng mang lại giá trị gần đúng tốt nhất của một số thực theo nghĩa nào. L. Euler vĩ đại (1707-1783) đã chứng minh một số quy định của lý thuyết phân số liên tục và tìm ra phân số liên tục cho số $e$. Rất khó để liệt kê các nhà toán học đã đóng góp cho lý thuyết này sau công trình của Euler do số lượng của họ quá lớn. Bắt đầu với công trình của nhà toán học xuất sắc người Nga P. L. Chebyshev (1821–1894), một lý thuyết liên quan đến phân số liên tục đã được tích cực phát triển.

Thuật toán Euclid và phân rã liên tục

Cho $p$, $q$ là hai số tự nhiên. Sản xuất với phần còn lại, chúng tôi sẽ tìm thấy

$$p = a_0 q + q_1, \quad 0 < q_1 < q$$

$$q = a_1 q_1 + q_2, \quad 0 < q_2 < q_1$$

$$q_1 = a_2 q_2 + q_3, \quad 0 < q_3 < q_2$$

$$q_{k-2} = a_{k-1} q_{k-1} + q_k, \quad 0 < q_k < q_{k-1}$$

$$q_{k-1} = a_k q_k.$$

Tập hợp các hành động được chỉ định được gọi là thuật toán Euclide. Có thể chứng minh rằng số thu được $q_k$ sẽ là số thực chung rộng nhất trong các số $p$, $q$. Ta không cần điều kiện này nên bỏ qua chứng minh*).

Từ các đẳng thức thu được, suy ra

$$\frac{p}{q} = a_0 + \frac{q_1}{q} = a_0 + \frac{1}{a_1 + \frac{q_2}{q_1}} = \dots = a_0 + \frac{1}{a_1 + \frac{1}{a_2 + \dots + \frac{1}{a_k}}}.$$

⟦folio 18⟧

Quá trình này cũng dẫn đến kết quả tương tự. Cho α là một số thực. Hãy đặt
$$\alpha = a_0 + \frac{1}{a_1}, a_0 - \text{целое},$$
ở đâu $a_1 > 1$. Nếu $a_1$ không phải là số nguyên thì chúng ta sẽ tiếp tục quá trình này. Hãy biểu thị $a_1$ dưới dạng $a_1 = a_1 + \frac{1}{a_2}$, trong đó $a_1$ là số nguyên dương và $a_2 > 1$. Như vậy,
$$\alpha = a_0 \frac{1}{a_1 + \frac{1}{a_2}}.$$
Nếu $a_2$ không phải là số nguyên thì bạn có thể tiếp tục quá trình này. Như vậy, ở bước $k$ ta thu được đẳng thức Ký hiệu “Nhiều tầng” của phân số (1) rất cồng kềnh nên sau này chúng ta sẽ thường sử dụng ký hiệu đặc biệt gọn hơn sau đây:
$$\alpha = a_0 + \frac{1}{a_1} + \frac{1}{a_2} + \dots + \frac{1}{a_{k-1}} + \frac{1}{a_k},$$
ở đâu $a_k > 1$.
Không khó để chứng minh rằng nếu $\alpha = \frac{p}{q}$ là số hữu tỷ thì đối với một số $k$ số $a_k$ sẽ là số nguyên.

Cũng rõ ràng rằng nếu với một số $k$ thu được số nguyên $a_k$ thì số $a$ là hợp lý. Nếu $a$ là một số vô tỷ thì quá trình được chỉ định sẽ không bao giờ kết thúc và một phân số tiếp tục (hoặc tiếp tục) vô hạn sẽ phát sinh
$$\alpha = a_0 + \frac{1}{|a_1|} + \frac{1}{|a_2|} + \dots +$$
$$\dots + \frac{1}{|a_{k-1}|} + \frac{1}{|a_k|} + \dots$$
Dấu bằng ở đây là tùy ý, vì không rõ biểu thức bên phải nghĩa là gì. Để cho nó có ý nghĩa, hãy xem xét các tổng hữu hạn có dạng
$$\pi_k = a_0 + \frac{1}{a_1 + \dots} + \frac{1}{a_k},$$
được gọi là phân số tiếp tục thích hợp (2). Theo định nghĩa, người ta giả định rằng vế phải của đẳng thức (2) được biểu thị bằng giới hạn của các phân số phù hợp:
$$\lim_{k \to \infty} \pi_k$$
Bây giờ chúng ta hãy xây dựng dưới dạng một tập hợp bài toán những tính chất của các phân số liên tục tạo thành cơ sở cho lý thuyết cơ bản của chúng và đặc biệt là thiết lập đẳng thức (2).

Tính chất cơ bản của phân số tiếp theo
1. Đặt $\pi_k = \frac{p_k}{q_k}$ là một phân số thích hợp của phân số tiếp theo (2). Chứng minh tính đúng đắn của quan hệ truy hồi:
$$p_0 = a_0, p_1 = a_0 a_1 + 1, \dots,$$
$$p_{k+1} = a_{k+1} p_k + p_{k-1}, \dots$$
$$q_0 = 1, q_1 = a_1, \dots,$$
$$q_{k+1} = a_{k+1} q_k + q_{k-1}, \dots$$
cho $k = 1, 2, 3, \dots$.
2. Thiết lập các tỉ số sau:
a) $q_n p_{n-1} - p_n q_{n-1} = (-1)^n, n \geqslant 1$;
b) $q_k p_{k-2} - p_k q_{k-2} = (-1)^{k-1} a_k, k \geqslant 2$;
c) $\pi_{n-1} - \pi_n = \frac{(-1)^n}{q_n q_{n-1}}, n \geqslant 1$;
d) $\pi_{k-2} - \pi_k = \frac{(-1)^{k-1} a_k}{q_k q_{k-2}}, k \geqslant 2$.

⟦folio 19⟧

3. Chứng minh rằng các phân số $\pi_0, \pi_2, \pi_4, \dots$ tăng đơn điệu:
$$\pi_0 < \pi_2 < \pi_4 < \pi_6 < \dots,$$
và các phân số $\pi_1, \pi_3, \dots$ giảm đơn điệu:
$$\pi_1 > \pi_3 > \pi_5 > \dots$$

4. Giả sử các số $a_k$ được xác định bằng đẳng thức (1). Chứng minh sự tuân thủ:
$$\alpha = \frac{p_{k-1}a_k + p_{k-2}}{q_{k-1}a_k + q_{k-2}}, k \geqslant 2.$$

5. Chứng minh bất đẳng thức
$$\frac{1}{2q_{n+1}} < |q_n\alpha - p_n| \leqslant \frac{1}{q_{n+1}}.$$

6. Chứng minh rằng
$$\lim_{k \to \infty} \pi_k = \alpha.$$
Như có thể thấy từ bài toán 1–6, phép tính gần đúng của phân số $\pi_n$ khá gần đúng với số $\alpha$. Do đó, từ các ước tính bài toán 5 và bất đẳng thức $q_{n+1} < q_n$, suy ra rằng nếu $\alpha$ là vô tỷ thì bất đẳng thức
$$\left| \alpha - \frac{p_n}{q_n} \right| < \frac{1}{q_n^2}$$
đúng cho tất cả các phân số phù hợp $\pi_n = \frac{p_k}{q_k}$ của số phân số tiếp theo $\alpha$.

Ví dụ số

Phân số tiếp theo (2) của số $\alpha$ đôi khi được ký hiệu là $[a_0; a_1, a_2, \dots, a_k, \dots]$. Có thể chứng minh rằng với mọi dãy số nguyên $a_0, a_1, a_2, \dots, (a_0 \geqslant 0$ và $a_j \geqslant 1$ cho $j \geqslant 1$) đều tồn tại một số dương duy nhất $\alpha$ sao cho
$$\alpha = [a_0; a_1, a_2, \dots].$$
Nếu biết dãy $a_0, a_1, a_2, \dots$ thì có thể dễ dàng tính được dãy các phân số trùng khớp $\pi_k = \frac{p_k}{q_k}$; sử dụng các đẳng thức từ bài toán 1 để điền vào bảng sau:

| $a$ | $a_0$ | $a_1$ | $a_2$ | ... | $a_{n-1}$ | $a_k$ | $a_{k+1}$ | $a_{k+2}$ | ... |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $p$ | 1 | $a_0$ | $p_1$ | $p_2$ | ... | $p_{k-1}$ | $p_k$ | ... | ... |
| $q$ | 0 | 1 | $q_1$ | $q_2$ | ... | $q_{k-1}$ | $q_k$ | ... | ... |

Ví dụ 1. Tìm phân tích tiếp tục phân tách của số $\sqrt{2}$.
Chúng tôi có $a_0 = 1$,
$$a_1 = \frac{1}{\sqrt{2} - 1} = \sqrt{2} + 1, \quad a_1 = 2,$$
$$a_2 = \frac{1}{\sqrt{2} - 1} = \sqrt{2} + 1, \quad a_2 = 2.$$
Rõ ràng là trong dãy $a_j, j = 1, 2, \dots$, tất cả các số hạng đều bằng $\sqrt{2} + 1$, và trong dãy $a_j, j = 1, 2, \dots$, tất cả các số hạng đều bằng 2. Vì vậy,
$$\sqrt{2} = [1; 2, 2, 2, \dots].$$
Hãy tính một số phân số phù hợp cho $\sqrt{2}$:

| $a$ | 1 | 2 | 2 | 2 | 2 | 2 | 2 | ... |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $p$ | 1 | 1 | 3 | 7 | 17 | 41 | 99 | ... |
| $q$ | 0 | 1 | 2 | 5 | 12 | 29 | 70 | 169 | ... |

Chúng ta có dãy phân số phù hợp: $\frac{1}{1}, \frac{3}{2}, \frac{7}{5}, \frac{17}{12}, \frac{41}{29}, \frac{99}{70}, \dots$

Từ bài toán 5 theo sau
$$\left| \sqrt{2} - \frac{99}{70} \right| < \frac{1}{70 \cdot 169} < 10^{-4}.$$
Như vậy, phần trường
