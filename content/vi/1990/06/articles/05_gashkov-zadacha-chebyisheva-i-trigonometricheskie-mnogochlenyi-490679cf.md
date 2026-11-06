---
id: 1990-6-gashkov-zadacha-chebyisheva-i-trigonometricheskie-mnogochlenyi-490679cf
issue: kvant_1990_6
year: 1990
number: "6"
title: Bài toán Chebyshev và đa thức lượng giác
authors:
  - Гашков С. Б.
rubric: osnovnye-stati
page_first: 27
page_last: 30
page_labels: 25-28
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 8463da2da0b18fd1d020343af3971e53e19a93bfbb9bf5e024087629cd339d37
prompt_sha256: draft-1
translated_from: content/ru/1990/06/articles/05_gashkov-zadacha-chebyisheva-i-trigonometricheskie-mnogochlenyi-490679cf.md
source_content_sha256: a5e5d5648d0aa4faf0c27f74fb3fafc39b111ac71769ffb5976862354e7f1f67
translation_model: draft
translation_run: vi-draft-gaps-2026-11-05
translation_quality: draft
---

⟦folio 25⟧

---
running_head:
folio:
---

VẤN ĐỀ CHEBYSHEV
VÀ lượng giác
ĐA THỨC

Ứng viên Khoa học Vật lý và Toán học
S. GASHKOV

Từ biên tập viên. Trong bài viết trước, chúng ta đã nói về các đa giác ít lệch nhất so với 0. Trong đó, các tính chất của polylen Chebyshev được bắt nguồn từ hình dạng đồ thị của chúng. Bài viết mà chúng tôi mang đến cho bạn sự chú ý đưa ra một cách tiếp cận khác cho vấn đề này bài toán - một cách tiếp cận dựa trên nghiên cứu về polylen lượng giác. Cái nào tốt hơn - hãy tự quyết định. Chúng tôi xuất phát từ thực tế là việc giải một bài toán theo nhiều cách sẽ hữu ích hơn là giải nhiều bài toán trong một...

Đa giác đại số và lượng giác

Hàm đa giác lượng giác được gọi là

$$f(\alpha) = a_0 + a_1 \cos \alpha + a_2 \cos 2\alpha + \dots + a_n \cos n\alpha,$$

(1)

trong đó $a_0, a_1, \dots, a_n$ là các hệ số bằng số. Số $n$ được gọi là độ và số $a_n$ là hệ số cao nhất của polylen lượng giác.

Chắc hẳn bạn có thắc mắc: tại sao hàm lượng giác (1) được gọi là bội số? Lý do là $f(\alpha)$ là một đa giác đại số thông thường của các hàm $\cos \alpha$. Trong bài viết trước, “Polylen ít lệch nhất so với 0”, người ta đã chứng minh rằng $2\cos n\alpha$ là polylen bậc $n$ của $2\cos \alpha$ với hệ số dẫn đầu là 1. Nếu bạn đọc bài viết đó, bạn biết rằng điều này rất dễ chứng minh bằng quy nạp; và nếu không, tôi khuyên bạn nên tự làm điều đó. Trong mọi trường hợp, với bất kỳ $n$ nào

$$\cos n\alpha = p_n(\cos \alpha),$$

trong đó $p_n(x)$ là đa giác bậc $n$ với hệ số cao nhất $2^{n-1}$:

$$\cos \alpha = x = p_1(x),$$

$$\cos 2\alpha = 2 \cos^2 \alpha - 1 = 2x^2 - 1 = p_2(x),$$

$$\cos 3\alpha = 4 \cos^3 \alpha - 3 \cos \alpha = 4x^3 - 3x = p_3(x),$$

$$\cos n\alpha = 2^{n-1}x^n + \dots = p_n(x),$$

$(x = \cos \alpha)$.

Nhân các đẳng thức trước đó với các hệ số $a_0, a_1, \dots, a_n$ và cộng lại, chúng ta thấy rằng mọi đa giác lượng giác (1) là một đa giác đại số bậc $n$ từ $\cos \alpha$.

Bây giờ chúng ta thử “đọc” các đẳng thức (2) từ phải sang trái và từ dưới lên trên. Từ đẳng thức cuối cùng nó suy ra rằng

$$x^n = 1/2^{n-1} \cos n\alpha + \dots,$$

(3)

trong đó đa họ hàng biểu thị $x^k$ độ hàng năm, nhỏ hơn $n$. Từ đẳng thức áp chót suy ra rằng

$$x^{n-1} = 1/2^{n-2} \cos(n-1)\alpha + \dots,$$

(4)

trong đó nhiều họ hàng thay thế $x^k$ độ hàng năm, nhỏ hơn $n-1$. Và vân vân. Thay thế (4) và các đẳng thức tương tự cùng với đa âm bậc $n$ với hệ số dẫn đầu $1/2^{n-1}$.

Theo đó, mọi đa giác đại số có bậc $n$th $p_n(x)$ với hệ số cao nhất là 1 tại $x = \cos \alpha$ là một đa giác lượng giác có bậc $n$với hệ số cao nhất là $1/2^{n-1}$.

⟦folio 26⟧

---
running_head:
folio:
---

Giá trị trung bình
đa thức lượng giác
Xét đa thức lượng giác $f(\alpha)$ với hệ số cao nhất $a_n$. Chúng ta hãy chia miền định nghĩa của nó [0; 2π] thành 2n phần bằng nhau theo điểm
$0, \pi/n, 2\pi/n, 3\pi/n, \dots, (2n-1)\pi/n$
và xét giá trị trung bình của nó tại các điểm có dấu giao nhau:
$$\frac{1}{2n}(f(0) - f(\pi/n) + f(2\pi/n) - f(3\pi/n) + \dots - f(2n-1)\pi/n)$$ (5)
Bổ đề. Số này bằng $a_n$.
Bằng chứng. Đa thức lượng giác (1) bao gồm các số hạng có dạng $g_k(\alpha) = \cos k\alpha$, trong đó $0 \leq k \leq n$. Chúng ta sẽ chứng minh rằng tổng (5) với tất cả $g_k$, ngoại trừ số cuối cùng, bằng 0. Nếu $k = 0$; thì $g_0(\alpha) = 1$, vậy
$$g_0(0) - g_0(\pi/n) + g_0(2\pi/n) - \dots = 1 - 1 + 1 - \dots - 1 = 0.$$
Hãy để bây giờ $0 < k < n$. Tổng (5) bằng hiệu của hai số hạng:
$$\cos(0) + \cos(2\pi/k) + \cos(4\pi/k) + \dots + \cos((2n-2)\pi/k),$$ (6₁)
$$\cos(\pi/k) + \cos(\pi/k + 2\pi/k) + \cos(\pi/k + 4\pi/k) + \dots + \cos(\pi/k + (2n-2)\pi/k).$$ (6₂)
Mỗi số tiền này đều bằng không. Thật vậy, hãy xem xét hai $n$-giác thông thường (trên hình $n=6$). Chúng ta hãy đi vòng quanh các đỉnh của $n$-gon theo thứ tự sau: $A_1, A_{1+k}, A_{1+2k}$, ... Sau một vài bước, đường dẫn của chúng ta sẽ đóng lại (tại hình $a$) $k=2$. Do tính đối xứng, tổng các vectơ có điểm bắt đầu ở tâm đa giác và kết thúc tại các điểm lệch nhau bằng 0. Do đó, tổng các hình chiếu của chúng lên trục hoành cũng bằng 0. Nhưng đây là số tiền (6₁)! Lập luận tương tự với hình 6) - trên đó $k=1$ - chứng tỏ tổng (6₂) cũng bằng 0.

Vì vậy, vẫn phải tính tổng (5) tại $f(\alpha) = a_n \cos n\alpha$. Nhưng trong trường hợp này $f(\pi/k) = a \cos(\pi k) = (-1)^k a.$
Tổng Pozny (5) bằng
$$1/2n(1 - (-1) + 1 - (-1) + \dots)a_n = 1/2n \cdot 2n \cdot a_n = a_n.$$
Bổ đề đã được chứng minh.

Lời giải
bài toán Chebysheva
Mọi công việc đều được khen thưởng: giờ đây chúng tôi có thể giải được bài toán của Chebyshev. Hãy nhớ lại rằng độ lệch của hàm số so với 0 trên một khoảng nào đó là mô đun quan trọng nhất trên khoảng này. Nhiệm vụ là tìm độ lệch lớn nhất có thể so với 0 trên đoạn [-1; 1] đa thức bậc $n$ với hệ số cao nhất là 1.

Trước hết, chúng ta hãy ước tính độ lớn độ lệch so với 0 của đa thức lượng giác (1). Điều này được thực hiện như thế này:
$$1/2n(|f(0)| + |f(\pi/n)| + |f(2\pi/n)| + \dots + |f((2n-1)\pi/n)|) \geq 1/2n(f(0) - f(\pi/n) + f(2\pi/n) - f(3\pi/n) + \dots - f((2n-1)\pi/n)| = |a_n|.$$
Bất bình đẳng có nghĩa là tổng của mô hình không nhỏ hơn tổng của mô hình; và đẳng thức là phát biểu của bổ đề ở đoạn trước. Từ bất đẳng thức (7), suy ra rằng mặc dù với một $k$ thì bất đẳng thức $|f(\pi/k)| \geq |a_n|$ đúng. Pozny

⟦folio 27⟧

---
running_head:
folio:
---

độ lệch so với 0 của đa thức lượng giác không nhỏ hơn mô đun của hệ số cao nhất của nó.
Bây giờ bài toán Chebyshev đã được giải quyết “chỉ trong một nước đi”. Theo những gì đã nói ở đầu bài viết, đa thức rút gọn bậc $n$th $p_n(x)$, với sự thay thế $x = \cos \alpha$, biến thành đa thức tam giác $f(\alpha)$ với hệ số cao nhất $1/2^{n-1}$; Hơn nữa, khi $\alpha$ đoạn [0; 2π], $x$ chạy qua đoạn [−1; 1]. Mặt khác, độ lệch so với 0 $f(\alpha)$ không nhỏ hơn hệ số dẫn đầu của nó. Có nghĩa,

độ lệch so với 0 của đa thức rút gọn bậc $n$ trên khoảng [−1; 1] không ít hơn $1/2^{n-1}$.
Dễ dàng nhận thấy độ lệch so với 0 trên khoảng [−1; 1], bằng $1/2^{n-1}$, có đa thức rút gọn $p_n(x)$, trong đó
$$p_n(\cos \alpha) = 1/2^{n-1}\cos n\alpha, \text{ т. е.}$$
$$p_n(x) = 1/2^{n-1}\cos (n\arccos x).$$
Tóm lại - một vài bài toán.

Đa thức lệch ít nhất so với 0

(Để bắt đầu, xem trang 23)

Như bạn đã đồng ý, đa thức $f_n(x)$ là những gì chúng ta cần. Thật vậy, $\alpha$ trống chạy qua đoạn [0; π]. Khi đó $n\alpha$ thay đổi từ 0 đến $n\pi$ và hàm $x = 2\cos \alpha$ và $f_n(x) = 2\cos n\alpha$ nhận các giá trị trên khoảng [−2; 2]. Trong trường hợp này, $x$ chạy qua phân đoạn này một lần và $f_n(x) - n$ một lần, luân phiên lấy $\pm 2$ với $x = \arccos \left(\frac{\pi k}{n}\right), k = 0, 1, \dots, n$. Điều này có nghĩa là đồ thị của đa thức $f_n(x)$ nằm trong dải $|y| \leq 2$ và chứa điểm $n+1$ xen kẽ của ranh giới trên và dưới của nó. Nghĩa là, $f_n(x)$ là đa thức ít sai lệch nhất so với 0 trên khoảng [−2; 2] (và khả năng né tránh là 2). Những đa thức này được gọi là đa thức Chebyshev.

Từ những điều trên rút ra kết luận cần thiết như sau:
bất kể đa thức rút gọn $g(x)$ là gì, điểm đó của đoạn [−2; 2], trong đó_module giá trị của nó không nhỏ hơn 2.

Theo tôi, không thể lường trước được một kết quả như vậy. Sau bài toán về các đa thức ít sai lệch nhất so với 0 được giải trên khoảng [−2; 2], không khó để giải quyết nó trên bất kỳ phân khúc nào khác. Để làm được điều này, chỉ cần thực hiện phép biến đổi tuyến tính của biến trong đa thức Chebyshev là đủ.

Bài tập 3. Tìm tên độ lệch so với 0 của các đa thức rút gọn bậc $n$ trên các đoạn a) [0; 4]; b) [−1; 1].

Đa thức Chebyshev chắc chắn xứng đáng được thảo luận chi tiết hơn. Câu chuyện về các tính chất tổ hợp của chúng đã xuất hiện trong «Kvant» - ở vị trí số 1 năm 1982. Tôi giới thiệu với anh ấy những người quan tâm đến các đa thức sai lệch ít nhất so với 0.

⟦folio 28⟧

---
running_head:
folio:
---

Chúng tôi đã chạy phần này từ vấn đề này sang vấn đề khác kể từ khi thành lập.
tạp chí mới. bài toán được xuất bản trong đó là không chuẩn
đúng như vậy, nhưng lời giải của họ không yêu cầu kiến ​​thức ngoài phạm vi chương trình học ở trường.
bài toán khó nhất được đánh dấu bằng dấu hoa thị. Sau từ ngữ bài toán, chúng tôi thường cho biết ai đã đề xuất điều đó cho chúng tôi. Tất nhiên, không phải tất cả những bài toán này đều được xuất bản lần đầu tiên.
Lời giải bài toán từ số này phải được gửi chậm nhất là ngày 15 tháng 8 năm 1990 đến địa chỉ: 103006, Moscow K-6, st. Gorky, 32/1, «Kvant». Lời giải bài toán từ các số khác nhau của tạp chí hoặc trong các chủ đề khác nhau (toán học và vật lý) được phân bổ trong các phong bì khác nhau. Trên phong bì, ở cột “Tới”, ghi: “Bài toán Kvant Số 6 - 90” và các số bài toán, lời giải bạn đang gửi, ví dụ “M1226” hoặc “F1233”. Ở cột “…địa chỉ người gửi”, vui lòng ghi rõ họ và tên của bạn.
vào. Bao gồm một phong bì có ghi địa chỉ của bạn trên đó (trong phong bì này bạn sẽ nhận được kết quả xác minh lời giải).
Tình trạng của mỗi bản gốc bài toán được đề xuất xuất bản được chỉ định trong một phong bì riêng biệt, được làm thành hai bản sao cùng với giải pháp của bạn cho bài toán này (trên vị trí phong bì: “Bài toán Kvant, bài toán mới trong vật lý” hoặc “...mới bài toán trong toán học”).
Ở đầu mỗi chữ cái, vui lòng cho biết mã số trường và lớp bạn sẽ học.
