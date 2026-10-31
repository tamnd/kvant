---
id: 1977-9-gabovich-otvet-v-trigonometricheskom-uravnenii-c20f36af
issue: kvant_1977_9
year: 1977
number: "9"
title: Đáp số trong phương trình lượng giác
authors:
  - Габович И. Г.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 55
page_last: 57
page_labels: 53-55
tag: FRLD
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 66d39e2d30de152fb98da93d666a220f0d78a4896d11e982b1c6120b947701c8
prompt_sha256: draft-1
translated_from: content/ru/1977/09/articles/18_gabovich-otvet-v-trigonometricheskom-uravnenii-c20f36af.md
source_content_sha256: 492e6b37de7a9a2d39c55fc08132eef73cee9ed68da19350ca5217565e467067
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 53⟧

Đáp số
trong phương trình lượng giác

Ký hiệu đáp số của phương trình lượng giác chủ yếu liên quan đến các khái niệm về hợp và giao của một tập hợp. Thông thường, với lời giải các phương trình như vậy, thu được một chuỗi nghiệm và ở dạng cuối cùng đáp số được viết dưới dạng hợp của các chuỗi này. Nhưng còn cuộc sống nếu những chuỗi này giao nhau thì sao? Có cần thiết phải loại trừ việc lặp lại lời giải hay điều này không thể thực hiện được?
Liên quan đến các giao điểm rõ ràng của tập hợp là một câu hỏi khác, rõ ràng là quan trọng nhất: trong đáp số không được có các giá trị của biến mà các biểu thức ở bên trái hoặc bên phải của phương trình không được xác định. Những giá trị như vậy, nếu chúng xuất hiện trong quá trình lời giải, phải được loại trừ. Và để làm được điều này, bạn cần có khả năng tìm ra giao điểm của các chuỗi khác nhau.

Bài viết này được dành cho những vấn đề này.

Một ví dụ
Hãy xem xét lời giải tiếp theo bài toán.

Ví dụ 1: Giải phương trình
$$\frac{1}{\sin x} - \frac{1}{\sin 2x} = \frac{1}{\sin 4x}.$$ (1)

Các giá trị hợp lệ cho biến định nghĩa điều kiện là: sin x ≠ 0, sin 2x ≠ 0, sin 4x ≠ 0. Điều này cho chúng ta x ≠ πk, x ≠ πm/2, x ≠ πn/4 (k, m, n∈Z). Dễ dàng thấy rằng ba điều kiện này có thể được thay thế bằng một điều kiện: x ≠ πn/4 (n∈Z). Điều này có thể được nhận thấy cả từ vòng tròn lượng giác đang xét (chuỗi x = πn/4 chứa chuỗi x = πk và x = πm/2), và hoàn toàn bằng đại số: đối với n chẵn, từ chuỗi x = πn/4 thu được chuỗi x = πm/2 và với n bội số của 4, thu được chuỗi x = πk. K như vậy cũng có thể được loại trừ. Sau đó phương trình
$$\sin 2x \sin 4x - \sin x \sin 4x = \sin x \sin 2x,$$
bằng giá trị ban đầu trong khoảng giá trị cho phép của biến. Biến đổi phương trình này, chúng ta nhận được:
$$\sin 2x \sin 4x = \sin x (\sin 2x + \sin 4x),$$
$$\sin 2x \sin 4x = 2 \sin x \sin 3x \cos x,$$
$$\sin 2x \sin 4x = \sin 2x \sin 3x,$$
$$\sin 2x (\sin 4x - \sin 3x) = 0,$$
$$\sin 2x \cdot \sin \frac{x}{2} \cdot \cos \frac{7x}{2} = 0.$$

Còn lại 3 trường hợp cần xét:
$$\sin 2x = 0, \sin \frac{x}{2} = 0, \cos \frac{7x}{2} = 0.$$

Phương trình sin 2x = 0 không cho chúng ta nghiệm của phương trình ban đầu, vì trong vùng đang xét phải có sin 2x ≠ 0.

Phương trình sin $\frac{x}{2} = 0$ và cos $\frac{7x}{2} = 0$ cho chúng ta chuỗi tương ứng $x_1 = 2\pi k$ và $x_2 = \frac{\pi}{7} (2k + 1) (k \in Z)$.

Việc còn lại là kiểm tra xem chúng có nằm trong vùng $x \in \mathbb{R}$, x ≠ πn/4, n∈Z hay không. Chuỗi $x_1$ rất dễ kiểm tra: vì $x \neq \pi n/4$ và với n bội số của n = 8l, hóa ra chỉ x ≠ 2πl, toàn bộ chuỗi $x_1$ bị loại trừ. Tình hình phức tạp hơn với các tập $x_2$. Ở đây chúng ta cần tìm số nguyên k có n thỏa mãn phương trình
$$\frac{\pi (2k + 1)}{7} = \frac{\pi n}{4},$$
và loại trừ k như vậy. Sau đó, phương trình

⟦folio 54⟧

mơ hồ nhớ đến
$$8k + 4 = 7n,$$
Hơn nữa, phương trình này phải được giải vì mục đích số học.

Phương trình sai phân tuyến tính trong hai biến
Phương trình sai phân tuyến tính hai biến được gọi là phương trình có dạng
$$ax + by = c,$$
(2)
trong đó $a$ và $b$ là số nguyên khác 0, $c$ là số nguyên tùy ý và chỉ cần tìm số nguyên lời giải.
Chúng ta có thể giả sử rằng các số $a, b$ và $c$ trong phương trình (2) là nguyên tố cùng nhau (chúng ta luôn có thể rút gọn cả hai vế của phương trình (2) bằng gcd $(a, b, c) \neq 1$).
Nhưng nếu các số là số nguyên tố chung thì chúng có thể không phải là số nguyên tố cùng nhau theo cặp (ví dụ: 6, 10, 15). Rõ ràng là nếu các số $a$ và $b$ trong phương trình (2) không nguyên tố cùng nhau thì phương trình này không có số nguyên lời giải. Thật vậy, khi đặt $a = ka_1$, $b = kb_1$, chúng ta nhận được $(a_1x + b_1y) = c$, mở ra $(a_1x + b_1y = c/k)$ và nếu $x$ và $y$ là số nguyên thì $c/k$ là số nguyên và điều này là không thể, vì $c$ không chia hết cho $k$ (chúng ta đã giả sử rằng $a, b$ và $c$ là các số nguyên tố tương đối).

Nếu $a$ và $b$ trong phương trình (2) là các số nguyên tố cùng nhau thì phương trình có số nguyên lời giải. Chúng tôi sẽ không tập trung vào việc chứng minh thực tế này mà sẽ chỉ trình bày cách tìm tất cả lời giải nếu biết ít nhất một trong số chúng (nó phải được tìm kiếm bằng cách chọn lọc).

Đặt $(x_0, y_0)$ là một số nguyên lời giải của phương trình (2):
$$ax_0 + by_0 = c.$$
Chúng ta hãy trừ số hạng đẳng thức này theo số hạng từ phương trình (2); chúng tôi nhận được
$$a(x - x_0) + b(y - y_0) = 0,$$
Ở đâu
$$x = x_0 - \frac{b(y - y_0)}{a}.$$

Để $x$, được xác định theo công thức (3), là một số nguyên, điều cần thiết và đủ là số $\frac{b(y - y_0)}{a}$ cũng là một số nguyên. Tuy nhiên, theo giả định, $a$ và $b$ là nguyên tố cùng nhau, do đó $\frac{y - y_0}{a}$ phải là số nguyên. Biểu thị mối quan hệ $\frac{y - y_0}{a}$ bằng chữ cái $t$, ta thu được:
$$x = x_0 - bt,$$
$$y = y_0 + at,$$
ở đâu $t \in \mathbb{Z}$.

Tiếp tục ví dụ
Vì vậy, chúng ta cần giải phương trình vì mục đích số học
$$7n - 4 = 8k.$$
Rõ ràng ngay rằng $n$ phải chia hết cho số chẵn; đặt $n = 4$, chúng ta tìm thấy $7 \cdot 4 - 4 = 24 = 8k$, mở $k = 3$. Chúng tôi đã nhanh chóng tìm được một phương trình lời giải: $k = 3$, $n = 4$. Khi đó, lời giải chung được viết là $k = 3 + 7t$, $n = 4 + 8t$ ($t \in \mathbb{Z}$).

Theo đó, trong dãy $x_2$ (xem trang 53) cần loại trừ tất cả $k$ có dạng $3 + 7t$, tức là đáp số ví dụ 1 có thể được viết ở dạng
$$x = \frac{\pi}{7}(2k + 1), k \neq 7t + 3, t \in \mathbb{Z}$$
hoặc
$$\left\{\frac{\pi}{7}(2k + 1)\right| k \neq 7t + 3; k, t \in \mathbb{Z}\}.$$

Phương trình $8k + 4 = 7n$ có thể được giải mà không cần sử dụng lý thuyết tổng quát. Theo sau đó là $n = 4l$ (vì vế trái của phương trình chia hết cho số chẵn). Thay $n = 4l$ vào phương trình, ta được: $8k + 4 = 28l$, mở $2k + 1 = 7l$. Tiếp theo, $l$ phải là số lẻ, $l = 2t + 1$; do đó $2k + 1 = 14t + 7$, $k = 7t + 3$. Vì vậy, lời giải xuất hiện: $k = 7t + 3$, $n = 4l = 4(2t + 1) = 8t + 4$.

Mục nhập đáp số
Bây giờ chúng ta hãy xem một bài toán khác.
Ví dụ 2: Giải phương trình
$$\sin^2 2x + \sin^2 3x + \sin^2 4x + \sin^2 5x = 2.$$
Sử dụng các điểm dữ liệu đã biết, chúng tôi nhận được:
$$\frac{1 - \cos 4x}{2} + \frac{1 - \cos 6x}{2} + \frac{1 - \cos 10x}{2} = 2,$$
với $4x + \cos 6x + \cos 8x + \cos 10x = 0,$
$2 \cos 5x \cos x + 2 \cos 9x \cos x = 0,$

⟦folio 55⟧

cos x (cos 5x + cos 9x) = 0,
cos x cos 2x cos 7x = 0.

Xét ba trường hợp, ta thu được ba dãy nghiệm ($k, l, m \in \mathbb{Z}$):

1) cos x = 0, $x_1 = \frac{\pi}{2} + \pi k$;
2) cos 2x = 0, $x_2 = \frac{\pi}{4} + \frac{\pi l}{2}$;
3) cos 7x = 0, $x_3 = \frac{\pi}{14} + \frac{\pi m}{7}$.

Làm thế nào để viết đáp số? Tôi có cần liệt kê cả ba tập không? Hãy xem liệu những chuỗi này có giao nhau hay không. Ở đây bạn có thể hành động theo những cách khác nhau.

Phương pháp hình học. “Chu kỳ” của chuỗi bằng π. Chúng ta hãy xem xét những nghiệm từ chuỗi $x_1, x_2, x_3$ nằm trong khoảng [0; π]. Nó sẽ là

$$x_1 : \pi/2;$$
$$x_2 : \pi/4, 3\pi/4;$$
$$x_3 : \pi/14, 3\pi/14; 5\pi/14, \pi/2, 9\pi/14, 11\pi/14, 13\pi/14.$$

Rõ ràng ngay rằng chuỗi $x_1$ nằm trong chuỗi $x_3$, và chuỗi $x_2$ và $x_3$ không giao nhau. Điều này có nghĩa là đáp số có thể được viết là

$$\left\{ \frac{\pi}{4} + \frac{\pi k}{2}; \frac{\pi}{14} + \frac{\pi k}{7} \mid k \in \mathbb{Z} \right\}.$$

Phương pháp đại số. Mẫu số chung của chuỗi $x_1$ và $x_2$ sẽ là 4:

$$x_1 = \frac{\pi(2+4k)}{4}, \quad x_2 = \frac{\pi(1+2l)}{4}.$$

Nếu $x_1 = x_2$ thì $2+4k = 1 + 2l$, nhưng nó theo sau một số chẵn và ở bên phải - một số lẻ. Sự bình đẳng là không thể, chuỗi $x_1$ và $x_2$ không giao nhau. Tương tự, ta thấy chuỗi $x_2$ và $x_3$ cũng không cắt nhau. Nhưng đối với chuỗi $x_1$ và $x_3$, chúng tôi nhận được công thức

$$x_1 = \frac{\pi(7+14k)}{14}, \quad x_3 = \frac{\pi(1+2m)}{14}.$$

Từ đẳng thức 7 + 14k = 1 + 2m ta thu được $m = 7k + 3$. Điều này có nghĩa là với mọi $k$ tồn tại một số nguyên $m$ sao cho đẳng thức 7 + 14k = 1 + 2m được thỏa mãn, nghĩa là mọi nghiệm từ chuỗi $x_1$ đều xuất hiện trong chuỗi $x_3$, do đó chuỗi $x_1$ đều nằm trong chuỗi $x_3$ và trong đáp số nó không thể bị chèn ép khi cần thiết.

Ví dụ 3. Giải phương trình $\cos 7x (\sin 5x - 1) = 0$.

Ta nhận ngay hai trường hợp ($k, n \in \mathbb{Z}$):

1) cos 7x = 0, $x_1 = \frac{\pi}{14} + \frac{k\pi}{7}$;
2) sin 5x = 1, $x_2 = \frac{\pi}{10} + \frac{2n\pi}{5}$.

Những chuỗi này có trùng nhau không? Khuyên bảo

$$\frac{\pi}{14} + \frac{\pi k}{7} = \frac{\pi}{10} + \frac{2\pi n}{5}$$

theo sau là $5k = 14n + 1$. Phương trình này có lời giải. Tuy nhiên, một trong số chúng được tìm thấy bằng cách chọn: $k = 3, n = 1$, và cái chung thì có dạng $k = 3 + 14t, n = 1 + 5t$.

Đáp số có thể được viết là

$$\left\{ \frac{\pi}{14} + \frac{\pi k}{7}; \frac{\pi}{10} + \frac{2\pi n}{5} \mid k \neq 3 + 14t; \right.$$
$$k, n, t \in \mathbb{Z}$$

hoặc ở dạng

$$\left\{ \frac{\pi}{14} + \frac{\pi k}{7}; \frac{\pi}{10} + \frac{2\pi n}{5} \mid n \neq 1 + 5t; \right.$$
$$k, n, t \in \mathbb{Z}$$.

Quét. Mặt khác, sự kết hợp của chuỗi trông phức tạp hơn chuỗi nhỏ hơn. Trong những trường hợp như vậy, có thể hữu ích nếu chia các chuỗi này thành “các phần”. Ví dụ: sự kết hợp của chuỗi $x_1 = \frac{\pi k}{2}$ và $x_2 = \frac{\pi}{6} + \frac{\pi k}{3}$ có thể được viết là

$$\left\{ \frac{\pi k}{2}; \frac{\pi}{6} + \pi k; \frac{5\pi}{6} + \pi k \mid k \in \mathbb{Z} \right\}.$$

Hệ thống

Đối với lời giải của một số phương trình lượng giác, chúng được thay thế bằng hệ phương trình,
