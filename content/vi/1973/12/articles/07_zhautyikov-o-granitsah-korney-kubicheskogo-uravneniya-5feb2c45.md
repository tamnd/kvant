---
id: 1973-12-zhautyikov-o-granitsah-korney-kubicheskogo-uravneniya-5feb2c45
issue: kvant_1973_12
year: 1973
number: "12"
title: Trên ranh giới của các nghiệm của phương trình bậc ba
authors:
  - Жаутыков О. А.
rubric: osnovnye-stati
page_first: 23
page_last: 25
page_labels: 21-23
tag: KPKG
lang: vi
source: kvant_digital
extraction: vision
content_sha256: db7c18a36b3f4d672d32a8376338432d5d3cca5a398d634ae546d40d6e3c3875
prompt_sha256: draft-1
translated_from: content/ru/1973/12/articles/07_zhautyikov-o-granitsah-korney-kubicheskogo-uravneniya-5feb2c45.md
source_content_sha256: 10c5ae07cf2d4d646688d1d014d5277b7a164a4403f4cb4b4a94b82da76cccd5
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 21⟧

Trên ranh giới của các nghiệm của phương trình bậc ba

Như bạn đã biết, các công thức cho phép bạn biểu diễn chính xác nghiệm của phương trình bậc ba thông qua các hệ số, trọng lượng của nó. Vì vậy, việc tính gần đúng các nghiệm của phương trình bậc ba thường rất quan trọng.

Bài viết này đánh giá các ranh giới mà các nghiệm thực của phương trình bậc ba có thể nằm trong đó.*)

Xét phương trình bậc ba
$$ax^3 + bx^2 + cx + d = 0,$$
(1)
hệ số $a, b, c, d$ là số thực, $a \neq 0$. Số hạng đầu tiên $ax^3$ ở vế trái của phương trình (1) được gọi là số hạng cũ, số hạng cuối cùng $d$ được gọi là số hạng tự do.

Như đã biết**), phương trình (1) có ba nghiệm, một trong số đó là nghiệm thực và hai nghiệm còn lại là thực hoặc liên hợp phức. Chúng ta sẽ chỉ quan tâm đến nghiệm thực của phương trình (1). Mục tiêu của chúng tôi là thế này: không cần tự tính toán các nghiệm, chúng ta sẽ thu được các ranh giới (ước tính) phi hài hước cho chúng, nghĩa là chỉ ra các tích phân trên trục thực mà các nghiệm này nằm trong đó.

Để làm điều này, cùng với phương trình (1), chúng ta xét đa thức bậc ba
$$y = ax^3 + bx^2 + cx + d.$$

Có thể nói gì về hoạt động của hàm này đối với các giá trị tuyệt đối lớn $x$? Nếu đối số $x$ tăng giá trị tuyệt đối của giá trị thì giá trị tuyệt đối

*) Bài viết này là phần tiếp theo của loạt tài liệu dành cho phương trình bậc ba (xem «Kvant», 1971, số 11, 1972, số 6).
**) Xem «Kvant», 1971, số 11, tr. 20-21.

Giá trị lô của mỗi số hạng ở vế phải của phương trình (2) sẽ tăng lên và bậc của số hạng này càng cao thì càng nhanh.

Rõ ràng là giá trị tuyệt đối của số hạng dẫn đầu $ax^3$ sẽ tăng nhanh nhất. Do đó, chúng ta có thể kỳ vọng rằng nếu chọn giá trị $|x|$ đủ lớn thì giá trị tuyệt đối của số hạng dẫn đầu $ax^3$ sẽ lớn hơn giá trị tuyệt đối của tổng tất cả các số hạng khác, tức là
$$|ax^3| > |bx^2 + cx + d|.$$

Hãy chứng minh rằng bất đẳng thức này đúng với mọi $x$ đủ lớn về giá trị tuyệt đối.

Vì giá trị tuyệt đối của tổng không vượt quá tổng các giá trị tuyệt đối của các số hạng nên
$$|bx^2 + cx + d| \leq |b| \cdot x^2 + |c| \cdot |x| + |d|.$$

Đặt $|x| = v$, chúng ta viết lại bất đẳng thức này:
$$|bx^2 + cx + d| \leq |b| \cdot v^2 + |c| \cdot v + |d|.$$

Các hệ số $|b|, |c|$ và $|d|$ ở vế phải của bất đẳng thức (4) là các số thực không âm; chúng ta hãy biểu thị số lớn nhất trong số chúng bằng $M$:
$$M = \max(|b|, |c|, |d|).$$

Nếu ở vế phải của bất đẳng thức (4) thay vì từng hệ số $|b|, |c|, |d|$ ta thay số $M$,

⟦folio 22⟧

thì bất đẳng thức (4) chỉ là thành công. Do đó, bất đẳng thức đúng
$$|bx^2 + cx + d| \leq M(v^2 + v + 1),$$
mà, nếu chúng ta sử dụng danh tính nổi tiếng,
$$v^2 + v + 1 = \frac{v^3 - 1}{v - 1}, \quad v \neq 1,$$
có thể được viết dưới dạng
$$|bx^2 + cx + d| \leq M \frac{v^3 - 1}{v - 1}.$$
Vì chúng tôi quan tâm đến các giá trị lớn của $|x| = v$, nên chúng tôi sẽ giả định rằng $v > 1$. Nhưng sau đó
$$\frac{M(v^3 - 1)}{v - 1} < \frac{Mv^3}{v - 1},$$
và do đó bất đẳng thức (6) sẽ có dạng
$$|bx^2 + cx + d| < \frac{Mv^3}{v - 1}, \quad |x| = v > 1.$$
(7)

Nếu chúng ta chứng minh được rằng giá trị tuyệt đối của số hạng dẫn đầu $ax^3$ đối với tất cả các giá trị $x$ đủ lớn về giá trị tuyệt đối (sao cho điều kiện $v > 1$ cũng được thỏa mãn) lớn hơn biểu thức $\frac{Mv^3}{v - 1}$, nằm ở vế bên phải của bất đẳng thức (7), thì bất đẳng thức (3) sẽ được chứng minh. Hãy xem cách chọn $|x| = v$ sao cho bất đẳng thức $|ax^3| > \frac{Mv^3}{v - 1}$ được thỏa mãn, tức là
$$|a|v^3 > \frac{Mv^3}{v - 1}.$$
Giải bất đẳng thức thu được đối với $v$, ta thấy rằng nó chắc chắn đúng với mọi
$$v > \frac{M+|a|}{|a|}.$$
Vì $\frac{M+|a|}{|a|} \geq 1$ (kể từ $M \geq 0$), nên với điều kiện (8) bất đẳng thức $v > 1$ luôn được thỏa mãn. Điều này chứng tỏ rằng bất đẳng thức (3) đúng với
$$|x| \geq \frac{M+|a|}{|a|}.$$
Theo đó, đối với các giá trị $x$ thỏa mãn điều kiện (9), hàm (2) không thể biến mất. Nói cách khác, mọi nghiệm thực của phương trình (1) đều thỏa mãn bất đẳng thức
$$|x| \leq \frac{M+|a|}{|a|}.$$
Số dương $A = \frac{M+|a|}{|a|}$ được gọi là giới hạn trên của nghiệm thực của phương trình bậc ba (1).
Hóa ra cũng có thể tìm thấy giới hạn dưới cho các nghiệm thực của phương trình bậc ba (1), tức là một số không âm $B$ sao cho tất cả các nghiệm thực của phương trình (1) đều thỏa mãn bất đẳng thức $|x| \geq B$.
Để làm điều này, chúng ta cần thay thế phương trình (1)
$$x = \frac{1}{z}.$$
(11)

Sau đó, sau các phép biến đổi tiếp theo, chúng ta thu được phương trình
$$dz^3 + cz^2 + bz + a = 0.$$
(Chúng ta sẽ giả sử rằng trong phương trình (1) số hạng tự do $d \neq 0$ hoặc trường hợp $d = 0$ không được quan tâm (phương trình (1) trong trường hợp này có nghiệm $x = 0$ và các nghiệm còn lại của nó được xác định từ phương trình bậc hai).
Vì $|x| = \frac{1}{|z|}$ (xem (11)), rõ ràng là bất đẳng thức $|z| < K$, trong đó $K > 0$, hàm ý bất đẳng thức $|x| > \frac{1}{K}$.
Pozny, nếu với $K$ chúng ta lấy giới hạn trên của nghiệm thực của phương trình (12), thì số $\frac{1}{K}$ sẽ là giới hạn dưới của nghiệm thực của phương trình (1). Nhưng chúng ta đã biết cách tìm giới hạn trên $K$ của nghiệm thực của phương trình (12) (xem (5), (10)):
$$K = \frac{N+|d|}{|d|},$$
Ở đâu
$$N = \max(|c|, |b|, |a|).$$
(13)

⟦folio 23⟧

Giới hạn dưới của Pozny cho nghiệm thực của phương trình bậc ba (1) là:

$$B = \frac{|d|}{N + |d|}.$$

Cần lưu ý rằng công thức này cũng hợp lệ trong trường hợp $d = 0$, khi đó giới hạn dưới rõ ràng bằng 0 (vì nó có gốc bằng 0) và chính xác thì kết quả tương tự thu được từ công thức (14) (tất nhiên trong trường hợp này là $N \neq 0$ hoặc trong phương trình (1) theo giả định $a \neq 0$).

Tóm lại: tất cả các nghiệm thực của phương trình bậc ba (1) đều thỏa mãn bất đẳng thức

$$B \leq |x| \leq A,$$

Các số $A$ và $B$ được xác định thông qua các hệ số của phương trình sử dụng các công thức (10), (5) và (14), (13). Nói cách khác, nghiệm thực của phương trình bậc ba (1) chỉ có thể nằm trên các đoạn $[-A, -B]$ và $[B, A]$ của trục thực; bên ngoài các phân đoạn này, phương trình (1) không có nghiệm thực sự.

Ví dụ Xét phương trình

$$2x^3 + 5x^2 - 4x - 3 = 0.$$

Đây là $M = 5$, $|a| = 2$ và sau đó là $A = \frac{7}{2}$. Do đó, giới hạn trên của nghiệm thực được coi là $\frac{7}{2}$. Tiếp theo, $N = 5$, $|d| = 3$ và sau đó là $B = \frac{3}{8}$. Do đó, giới hạn dưới của nghiệm thực được coi là $\frac{3}{8}$. Nói cách khác, nghiệm thực được coi là nằm trên các đoạn $(-7/2, -3/8)$ và $(3/8, 7/2)$.

Từ từ điển cũ

(Tiếp tục Bắt đầu xem trang 20)

Chúng ta hãy nhìn vào từ điện. Chúng ta đọc: “... Vật chất, chất tinh tế nhất trong tất cả các vật thể lỏng được biết đến, giao tiếp với hầu hết mọi vật thể, ở mức độ lớn hơn hoặc thấp hơn và chuyển động với tốc độ phi thường.”

Đối với mô tả này, chúng ta có thể nói thêm rằng vào đầu thế kỷ 19, người ta tin rằng có hai chất lỏng điện tương ứng với hai điện tích - dương và âm. Những chất lỏng này được bổ sung thêm hai chất từ ​​tính nữa (từ tính bắc và nam), một chất lỏng liên kết với lực hấp dẫn và nhiệt lượng.

Điều thú vị là Từ điển phân biệt giữa “trọng lực, lực đẩy mọi vật xuống đáy hoặc vào tâm Trái đất” và “lực hấp dẫn phổ quát, lực hút lẫn nhau của tất cả các thiên thể”.

Người ta có thể hiểu tại sao với sự liên kết nhiệt và điện lại tồn tại các chất lỏng cụ thể. Các nhà vật lý đã nhận thấy rằng có một cái gì đó trong tự nhiên được bảo tồn. Định luật đơn giản và dễ hiểu nhất là định luật bảo toàn vật chất - một phần là chất lỏng. Định luật này được sử dụng rộng rãi trong thủy động lực học. Vì vậy, chất lỏng cụ thể cũng phải gắn liền với các khoản nợ dinh dưỡng dự trữ khác. Thực tế là những chất lỏng này dễ dàng xâm nhập vào mọi cơ thể một cách bất thường đã được thể hiện rõ ở giai đoạn đầu tiên của món sinh tố nhỏ: các cơ thể có vẻ đơn giản và chất lỏng thì “mỏng”.

(Cuối cùng xem trang 28)
