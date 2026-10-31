---
id: 1989-4-brudno-metod-lobachevskogo-49583d9c
issue: kvant_1989_4
year: 1989
number: "4"
title: phương pháp lobachevsky
authors:
  - Брудно А. Л.
rubric: raznoe
rubric_sub: Разное
page_first: 53
page_last: 54
page_labels: 51-52
tag: X2EG
lang: vi
source: kvant_digital
extraction: vision
content_sha256: d635377533c0953806100681d95cc40a4ef4c04e4894a361b82b6f5ce4bbc141
prompt_sha256: draft-1
translated_from: content/ru/1989/04/articles/13_brudno-metod-lobachevskogo-49583d9c.md
source_content_sha256: be6e66586612f57e3b48e8b8de6bb3fa75fa38b425b43fd0e83ea475d98d0191
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 51⟧

phương pháp lobachevsky

Tiến sĩ Khoa học Vật lý và Toán học
A. L. BRUDNO

Người sáng tạo ra hình học phi Euclide N. I. Lobachevsky cũng đã nghĩ ra phương pháp tính gần đúng các phương trình đại số lời giải (với hệ số thực)

$$a_0 + a_1x + a_2x^2 + \dots + a_nx^n = 0. \quad (1)$$

Phương pháp này cho phép bạn tìm giá trị tuyệt đối của nghiệm có mô đun cực đại. Sau đó, dấu của nghiệm có thể dễ dàng được xác định bằng cách thay thế vào phương trình đã cho. Hạn chế duy nhất trong việc sử dụng phương pháp này là gốc có giá trị tuyệt đối tối đa phải là duy nhất. Ví dụ, nếu nó hoàn chỉnh, thì đã có hai trong số chúng (nghĩa là nó cũng là liên hợp phức) và phương pháp này không thể áp dụng được. Sau đó, phương pháp này đã được cải tiến và có thể tìm thấy tất cả các nghiệm của phương trình nếu mô-đun của chúng khác nhau.

Ý tưởng của Lobachevsky như sau. Chúng ta hãy thay thế phương trình đã cho (1) bằng một phương trình khác có nghiệm bằng bình phương các nghiệm của phương trình đã cho. Chúng tôi sẽ lặp lại kỹ thuật này nhiều lần. Khi đó, các nghiệm của phương trình sẽ được “bình phương”, rồi đến lũy thừa thứ 4, đến bậc 8, v.v. Kết quả là, nghiệm có mô đun cực đại bắt đầu đóng vai trò lấn át so với các nghiệm khác và có thể dễ dàng tính toán từ các hệ số của phương trình thu được (xem bên dưới). Nếu bây giờ căn của đáp số được chuyển thành lũy thừa thì chúng ta sẽ nhận được giá trị tuyệt đối (xấp xỉ) của nghiệm của phương trình ban đầu.

1. Vì vậy, Lobachevsky cần tìm một đa thức có nghiệm bằng bình phương của các nghiệm của đa thức ban đầu, và ông phải tìm nó mà không cần tính nghiệm của đa thức ban đầu. Hãy xem lobachevsky đã làm gì. Chúng ta được cho một đa thức

$$P(x) = a_0 + a_1x + a_2x^2 + \dots + a_nx^n. \quad (2)$$

Có một định lý: đa thức $P(x)$ có thể biểu diễn dưới dạng

$$P(x) = a_n(x - x_1)(x - x_2) \dots (x - x_n),$$

trong đó $x_1, x_2, \dots, x_n$ là nghiệm của phương trình $P(x) = 0$ (ở trường, điều này chỉ được nghiên cứu với $n=2$ và được gọi là “phân tích nhân tử của tam thức bậc hai”). Hãy lấy đa thức $P(-x)$. Nó có thể được viết dưới dạng

$$P(-x) = a_0 - a_1x + a_2x^2 - \dots + (-1)^n a_nx^n.$$

hoặc

$$P(-x) = a_n(-x - x_1)(-x - x_2) \dots (-x - x_n),$$

hoặc thậm chí như thế này:

$$P(-x) = (-1)^n a_n(x + x_1)(x + x_2) \dots (x + x_n).$$

Xét tích của đa thức

$$P(x)P(-x) = (-1)^n a_n^2(x^2 - x_1^2)(x^2 - x_2^2) \dots (x^2 - x_n^2).$$

⟦folio 52⟧

Lưu ý rằng nó không chứa sức mạnh kỳ lạ $x$. Nếu thay thế $x^2$ bằng $t$ trong tích này, chúng ta sẽ nhận được đa thức cần thiết

$$Q(t) = (-1)^n a_n^2 (t - x_1^2) (t - x_2^2) \dots (t - x_n^2),$$

có các căn bằng bình phương các căn của đa thức đã cho $P(x)$. Để tính các hệ số $b_k$ của đa thức $Q(t)$

$$Q(t) = b_0 + b_1 t + b_2 t^2 + \dots + b_{n-1} t^{n-1} + b_n t^n$$

bạn có thể thay đổi $P(x)$ và $P(-x)$, đưa các thuật ngữ tương tự cho cùng lũy ​​thừa $x$ (các lũy thừa lẻ sẽ biến mất) và thay thế $x^2, x^4, \dots$ bằng $t, t^2, \dots$.

Dưới đây là công thức cho các hệ số $b_k$ cho $n=3$ và $n=4$:

$$n = 3; a_0 + a_1 x + a_2 x^2 + a_3 x^3 = 0$$
$$b_0 = a_0 a_0$$
$$b_1 = a_0 a_2 - a_1 a_1 + a_2 a_0$$
$$b_2 = -a_1 a_3 + a_2 a_2 - a_3 a_1$$
$$b_3 = -a_3 a_3$$

$$n = 4; a_0 + a_1 x + a_2 x^2 + a_3 x^3 + a_4 x^4 = 0$$
$$b_0 = a_0 a_0$$
$$b_1 = a_0 a_2 - a_1 a_1 + a_2 a_0$$
$$b_2 = a_0 a_4 - a_1 a_3 + a_2 a_2 - a_3 a_1 + a_4 a_0$$
$$b_3 = a_2 a_4 - a_3 a_3 + a_4 a_2$$
$$b_4 = a_4 a_4$$

Việc tính các hệ số $b_k$ không khó thực hiện trên máy tính hoặc thậm chí là máy tính vi mô có thể lập trình được. Sau khi tính toán các hệ số $b_k$, các giá trị của chúng được gán cho các hệ số $a_k$, các hệ số mới $b_k$ được tính toán, v.v., cho đến khi gốc có mô đun tối đa trở nên chiếm ưu thế.

Để tìm giá trị của gốc này, chúng ta hãy quay lại các công thức

$$Q(t) = b_0 + b_1 t + \dots + b_{n-1} t^{n-1} + b_n t^n$$
$$Q(t) = b_n (t - t_1) (t - t_2) \dots (t - t_n).$$

Nếu bạn mở dấu ngoặc và các thuật ngữ rút gọn ở dòng dưới cùng, bạn sẽ có được dòng trên cùng. Kể từ đây,

$$b_{n-1} = -(t_1 + t_2 + \dots + t_n) b_n$$

hoặc

$$t_1 (1 + t_2/t_1 + t_3/t_1 + \dots + t_n/t_1) = -b_{n-1}/b_n.$$

Nếu nghiệm $t_1$ vượt quá đáng kể các nghiệm số khác về mô đun thì biểu thức trong ngoặc đơn gần bằng 1 và giá trị gần đúng

$$t_1 \approx -b_{n-1}/b_n.$$

Điều thú vị là phương pháp Lobachevsky cũng có thể được sử dụng để tìm giá trị của các nghiệm còn lại của phương trình (nếu chúng khác nhau về mô đun). Đặt gốc $t_2$ nhỏ hơn $t_1$, nhưng giá trị lớn hơn phần còn lại. Khi đó trong biểu thức của $b_{n-2}$

$$b_{n-2} = (t_1 t_2 + t_1 t_3 + \dots + t_2 t_3 + \dots) b_n$$

trong ngoặc, vai trò chính sẽ do $t_1 t_2$ đảm nhận và chúng ta có thể giả định gần đúng rằng $b_{n-2} \approx t_1 t_2 b_n$, từ đó

$$t_2 \approx -b_{n-2}/b_{n-1}.$$

Tương tự như $t_k \approx -b_{n-k}/b_{n-k+1}$.

2. Các giá trị gần đúng thu được bằng phương pháp của Lobachevsky gần như chắc chắn sẽ nhanh chóng hội tụ về chính xác lời giải. Khi tính toán trên máy tính hoặc máy tính vi mô, bạn cần thiết lập bộ đếm số lần lặp (ký hiệu là $p$) và cộng thêm 1 vào sau mỗi lần lặp. Đối với các nghiệm $x_k$ của phương trình ban đầu, nó sẽ là

$$|x_k| = t_k^{1/2^p},$$

vì đa thức $Q(t)$ thu được nhờ các lần lặp $p$ (liên tục đi từ đa thức $P$ đến đa thức $Q$ và thay thế các nghiệm bằng bình phương của chúng). $|x_k|$ chỉ nên được tính nếu $t_k > 0$. Giá trị của $t_k$ có thể âm nếu có các nghiệm có độ lớn bằng nhau hoặc trong các lần lặp đầu tiên. Thật thuận tiện khi hiển thị các giá trị gần đúng của mô hình gốc $x_k$ trên màn hình sau mỗi lần lặp và theo dõi cách chúng được thiết lập. Chính phương pháp này, nhưng bằng cách tính toán bằng tay, Lobachevsky đã nghĩ ra.

Thử nghiệm với máy vi tính MK-61 để tìm phương trình bậc ba 0,76—1,37x—1,3x²+2x³=0, có nghiệm $x_1=0,95$; $x_2=-0,8$; $x_3=0,5$, đưa ra hình ảnh về sự hội tụ sau đây (có 2-3 chữ số thập phân; mỗi lần lặp mất 15 giây):
