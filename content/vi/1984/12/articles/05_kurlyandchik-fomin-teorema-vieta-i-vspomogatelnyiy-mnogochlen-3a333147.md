---
id: 1984-12-kurlyandchik-fomin-teorema-vieta-i-vspomogatelnyiy-mnogochlen-3a333147
issue: kvant_1984_12
year: 1984
number: "12"
title: Định lý Vieta và đa thức phụ trợ
authors:
  - Курляндчик Л. Д.
  - Фомин С. В.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 16
page_last: 17
page_labels: 14-15
tag: A6YU
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 648e5b3bcf26d7a0963a8d88389b1025907078bc09e95fc9dc121277cac10c17
prompt_sha256: draft-1
translated_from: content/ru/1984/12/articles/05_kurlyandchik-fomin-teorema-vieta-i-vspomogatelnyiy-mnogochlen-3a333147.md
source_content_sha256: b605927b70c7d486e9ef7bf98e70b0a56601b5e1f92c63f9e79ce2f3ca3f89d0
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 14⟧

Định lý Vieta và đa thức phụ trợ

L. D. KURLYANDCHIK,
Ứng viên Khoa học Vật lý và Toán học
S. V. FOMIN

Nhiều bài toán bằng cách này hay cách khác đi đến việc tìm ra nghiệm của các phương trình đại số. Nhưng đôi khi - và điều này sẽ được thảo luận ở nước ta - rằng đối với lời giải bài toán, ngược lại, sẽ rất hữu ích khi xây dựng một đa thức có nghiệm đã cho, các số đã biết. Kỹ thuật liên quan đến việc đưa ra đa thức phụ trợ cho phép chúng ta giải một số bài toán có dạng hoàn toàn khác. Điểm trung bình của họ là bài toán M879 và M882 từ Zadachik «Kvant» và một trong bài toán từ Olympic quốc tế vừa qua.

Cho $u$ và $v$ là hai số thực. Làm thế nào để xây dựng một tam thức bậc hai có nghiệm là $u$ và $v$? Cách dễ nhất là xét đa thức
$$P(t)=(t-u)(t-v)=t^2+pt+q.$$
Các hệ số của nó là:
$$p=-(u+v), q=uv,$$
(1) tức là tổng (có dấu trừ) và tích của các số ban đầu. Công thức (1) được gọi là công thức Vieta. Hai định lý trong sách giáo khoa ở trường có liên quan đến nó:
nếu phương trình bậc hai $t^2+pt+q=0$ có nghiệm $u$ và $v$ thì các đẳng thức (1) được thỏa mãn (định lý Vieta);
các số $u$ và $v$ là nghiệm của phương trình bậc hai $t^2-(u+v)t+uv=0$ (định lý ngược).
Hãy để chúng tôi đưa ra một số ví dụ về việc áp dụng định lý Vieta nghịch đảo. Hãy bắt đầu với bài toán rất đơn giản.
Bài toán 1. Lập phương trình bậc hai với các hệ số nguyên có nghiệm là số $2+\sqrt{3}$.
Lời giải của bài toán này, cũng như nhiều phương trình khác, có thể dựa trên thực tế là một phương trình bậc hai có nghiệm “liên hợp” $a+b\sqrt{d}$ và $a-b\sqrt{d}$ (trong đó $a, b$ và $d$ là số nguyên) có

hệ số nguyên*). Tất nhiên, thực tế này được rút ra ngay từ công thức của Vieta (1).

Vì vậy, phương trình ban đầu có nghiệm $t_1=2+\sqrt{3}$ và $t_2=2-\sqrt{3}$ nên các hệ số của nó bằng nhau: $p=-(t_1+t_2)=-4$, $q=t_1t_2=1$.

Đáp số: $t^2-4t+1=0$.

Bài toán 2. Số $t_1=\sqrt{37}-\sqrt{20}$ có phải là nghiệm của bất đẳng thức $t^2+9t-17>0$ không?

Lời giải. Hãy tạo một phương trình bậc hai có gốc là các số $t_1$ và $t_2=-\sqrt{37}-\sqrt{20}$:
$$t^2+2\sqrt{20}t-17=0.$$
Vì $2\sqrt{20}=\sqrt{80}<9$ nên bất đẳng thức $t_1^2+9t_1-17>t_1^2+2\sqrt{20}t_1-17=0$ đúng.

Đáp số: Số $t_1$ là nghiệm của bất đẳng thức này.

Việc tính giá trị của hàm số tại một điểm cho trước thường được đơn giản hóa nếu lần đầu tiên bạn xây dựng một đa thức triệt tiêu tại điểm này. Đây là một ví dụ điển hình.

Bài toán 3. Tính $u^4-5u^3+6u^2-5u$ nếu $u=2+\sqrt{3}$.

Lời giải. Nhớ lại kết quả của bài toán 1: $u^2-4u+1=0$ hoặc $u^2=4u-1$. Bằng cách sử dụng mối quan hệ này, chúng ta biểu diễn nó một cách tuyến tính theo lũy thừa $u$ $u^3$ và $u^4$:
$$u^3=u^2\cdot u=(4u-1)u=4u^2-u=4(4u-1)-u=15u-4,$$
$$u^4=u^3\cdot u=(15u-4)u=15u^2-4u=15(4u-1)-4u=56u-15.$$
Do đó $u^4-5u^3+6u^2-5u=56u-15-5(15u-4)+6(4u-1)-5u=-1$.

Đáp số: —1.

Hoạt động theo cách tương tự như trong lời giải đã cho, giá trị của bất kỳ đa thức nào có hệ số nguyên tại điểm $u=a+b\sqrt{d}$ có thể được biểu diễn dưới dạng $ku+l$ ($a, b, d, k, l$ là số nguyên).
Bài toán 4. Chứng minh số $(7+\sqrt{48})^{13}+(7-\sqrt{48})^{13}$ là số nguyên chia hết cho 14.

Lời giải. Các số $u=7+\sqrt{48}$ và $v=7-\sqrt{48}$ là nghiệm của tam thức bình phương $t^2-14t+1$. Sử dụng công thức $u^2=14u-1$ và $v^2=14v-1$, chúng ta thu được “mối quan hệ lặp lại” cho giá trị $a_n=u^n+v^n$:

* (Người đọc sẽ tìm thấy nhiều ví dụ hay liên quan đến ý tưởng này trong bài viết “Các số liên hợp” của N. Vaguten (Kvant, 1980, số 2, trang 26).

⟦folio 15⟧

$$a_0 = 2$$
$$a_1 = u + v = 14$$
$$a_2 = u^2 + v^2 = (14u - 1) + (14v - 1) = 14a_1 - a_0$$
$$a_3 = u^3 + v^3 = u(14u - 1) + v(14v - 1) = 14a_2 - a_1$$
$$a_n = u^n + v^n = u^{n-2}(14u - 1) + v^{n-2}(14v - 1) = 14a_{n-1} - a_{n-2}.$$

Từ những mối quan hệ này, suy ra rằng tất cả các số $a_n$ đều là số nguyên. Ngoài ra, nếu $n$ lẻ thì $a_n$ chia hết cho 14. Câu này có thể được chứng minh bằng quy nạp: nếu $a_{n-2}$ chia hết cho 14 thì $a_n$ chia hết cho 14.

Bài toán 5. Tìm $u^8 + \frac{1}{u^8}$ nếu $u = \sqrt{2} + 1$.

Công thức Vieta, tương tự như công thức (1) cho tam thức bậc hai, cũng có thể được viết cho đa thức bậc $n$

$$P(t) = (t - x_1)(t - x_2) \dots (t - x_n) = t^n + a_1 t^{n-1} + a_2 t^{n-2} + \dots + a_n$$

có rễ $x_1, \dots, x_n$. Để làm điều này, bạn cần mở ngoặc, đưa các số hạng tương tự và đánh đồng các hệ số có cùng lũy ​​thừa $t$ ở bên trái và bên phải.

Chúng ta hãy viết các công thức này một cách rõ ràng cho đa thức bậc ba

$$P(t) = (t - x)(t - y)(t - z) = t^3 + pt^2 + qt + r$$

có gốc $x, y$ và $z$:

$$p = -x - y - z$$
$$q = xy + yz + zx$$
$$r = -xyz$$

Bây giờ chúng ta hãy chuyển sang các ví dụ thú vị nhất về việc sử dụng đa thức phụ trợ - chúng liên quan chính xác đến trường hợp đa thức được xây dựng từ một số (ít nhất ba) nghiệm.

Bài toán 6. Các số $x, y, z$ thỏa mãn hệ thức:

$$x + y + z = a, \frac{1}{x} + \frac{1}{y} + \frac{1}{z} = \frac{1}{a}.$$

Chứng minh rằng ít nhất một trong các số này bằng $a$.

Lời giải. Chấp nhận công thức (2). Trong trường hợp của chúng tôi $p = -a$, $q = xyz/a = -r/a$. Đó là lý do tại sao

$$P(t) = t^3 - at^2 - \frac{r}{a} t + r = (t - a)\left(t^2 - \frac{r}{a}\right).$$

Do đó, số $a$ là nghiệm của đa thức $P(t)$ và do đó trùng với một trong các số $x, y, z$.

Bài toán 7. (M882) Tổng của ba số nguyên $u, v$ và $w$ bằng 0. Chứng minh rằng số $2u^4 + 2v^4 + 2w^4$ là bình phương của một số nguyên.

Lời giải. Giả sử $P(t) = t^3 + pt^2 + qt + r$ là một đa thức có nghiệm là các số $u, v$ và $w$. Theo định lý Vieta, $p = -(u + v + w) = 0$. Chúng tôi có:

$$u^3 + qu + r = 0$$
$$v^3 + qv + r = 0$$
$$w^3 + qw + r = 0.$$

Để thu được biểu thức hoạt động trong các điều kiện, chúng ta nhân các phương trình này với $2u, 2v$ và $2w$ tương ứng rồi thêm:

$$2u^4 + 2v^4 + 2w^4 + 2q(u^2 + v^2 + w^2) = 0$$

(chúng tôi sử dụng những gì $u + v + w = 0$). Nhưng $u^2 + v^2 + w^2 = (u + v + w)^2 - 2q = -2q$, do đó $2u^4 + 2v^4 + 2w^4 = (2q)^2$.

bài toán được bao gồm trước đó được giải quyết theo cách tương tự theo định nghĩa

$$x^3 + px^2 + qx + r = 0$$
$$y^3 + py^2 + qy + r = 0$$
$$z^3 + pz^2 + qz + r = 0$$,

và sau đó chúng ta sẽ sử dụng các công thức của Vieta (2) và đạo hàm đã gặp ở bài toán trước đó

$$x^2 + y^2 + z^2 = (x + y + z)^2 - 2(xy + yz + zx) = p^2 - 2q.$$

chúng tôi nhận được

$$x^3 + y^3 + z^3 + p(p^2 - 2q) - qp + 3r = 0,$$

Ở đâu

$$x^3 + y^3 + z^3 - 3xyz = -p(p^2 - 3q) = (x + y + z)(x^2 + y^2 + z^2 - xy - yz - zx)$$.

Bình luận. Biểu thức $x^2 + y^2 + z^2 - xy - yz - zx$ không âm (vì $(x - y)^2 + (y - z)^2 + (z - x)^2 \geq 0)$. Do đó, từ thực tế đã chứng minh nó tuân theo bất đẳng thức

$$\frac{a + b + c}{3} \geq \sqrt[3]{abc}$$

(3)

đối với trung bình số học và trung bình hình học của ba số không âm: chỉ cần đặt $x = \sqrt[3]{a}$, $y = \sqrt[3]{b}$, $z = \sqrt[3]{c}$ trong định nghĩa này là đủ.

Bây giờ chúng ta hãy xem cách chúng ta có thể sử dụng đa thức phụ tại lời giải của hệ phương trình.

Bài toán 9. Giải hệ

$$\begin{cases} x + y + z = 2 \\ x^2 + y^2 + z^2 = 14 \\ x^3 + y^3 + z^3 = 20. \end{cases}$$

Lời giải. Theo phương pháp của chúng tôi, chúng tôi giới thiệu đa thức

$$P(t) = (t - x)(t - y)(t - z) = t^3 + pt^2 + qt + r.$$

Theo định lý Vieta

$$p = -(x + y + z) = -2$$
$$q = xy + yz + zx = \frac{(x + y + z)^2 - (x^2 + y^2 + z^2)}{2} = -5.$$

Để tìm hệ số $r$, hãy nhân các phương trình hệ thống với $q$, $p$ và $1$ tương ứng rồi cộng chúng lại. Vì $P(x) = P(y) = P(z) = 0$, chúng tôi nhận được:

$$-3r = 2q + 14p + 20 = -10 - 28 + 20 = -18.$$

Vì vậy, $P(t) = t^3 - 2t^2 - 5t + 6$. Đây là một đa thức có hệ số nguyên và hệ số cao nhất của nó là 1. Do đó, bất kỳ hệ số nguyên nào bằng $P(t)$ đều phải là ước số của một số tự do. Trong trường hợp này, cả ba gốc đều là số nguyên (và ước số của số 6 là 1, -2 và 3$^*$). Vì vậy, $\{x, y, z\} = \{1, -2, 3\}$.

$\cdot$) Về nguyên tắc, chỉ cần giải - hoặc tìm - ít nhất một nghiệm, rồi sử dụng khai triển đa thức là đủ. Chúng tôi sử dụng điều này chi tiết hơn trong bài viết của S. V. Fomin “Phân tích thành đa thức” (Kvant, 1983, số 7, trang 23).
