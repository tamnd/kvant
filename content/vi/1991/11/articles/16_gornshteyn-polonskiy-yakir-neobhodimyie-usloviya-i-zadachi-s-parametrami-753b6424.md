---
id: 1991-11-gornshteyn-polonskiy-yakir-neobhodimyie-usloviya-i-zadachi-s-parametrami-753b6424
issue: kvant_1991_11
year: 1991
number: "11"
title: Điều kiện tiên quyết và bài toán với các tham số
authors:
  - Горнштейн П. И.
  - Полонский В. Б.
  - Якир М. С.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 46
page_last: 51
page_labels: 44-49
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 8eb91e45e5e19347de555b6acb19ec25d9ac450373c2ebba0ec19707cad92c1f
prompt_sha256: draft-1
translated_from: content/ru/1991/11/articles/16_gornshteyn-polonskiy-yakir-neobhodimyie-usloviya-i-zadachi-s-parametrami-753b6424.md
source_content_sha256: 71b6257ea0f0819e56a10e04346559705d6091d67916b493ab7cffb34b5f2460
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 44⟧

---
running_head:
folio:
---

Điều kiện tiên quyết và bài toán với các tham số

P. GORNITEIN, V. POLONSKY, M. YAKIR

Những người hâm mộ truyện trinh thám đã quen thuộc với sơ đồ tiêu chuẩn: vòng tròn nghi phạm dần dần thu hẹp, và cuối cùng, Cape Puar vĩ đại đã phát hiện ra một người đại diện. Hóa ra một âm mưu tương tự được thực hiện trong cả lớp toán bài toán. Đây là một ví dụ.

Chúng ta cần giải phương trình $f(x)=g(x)$. Đầu tiên, toàn bộ tập hợp số thực bị nghi ngờ là nghiệm của phương trình. Hãy loại trừ những trường hợp có bằng chứng ngoại phạm rất mạnh: nghiệm của phương trình của chúng ta không thể xuất hiện bên ngoài phạm vi định nghĩa của hàm $f$ và $g$.

Nếu có thể chứng minh rằng tất cả các nghiệm của phương trình đều nằm trong một tập hợp nhất định $M$, thì một điều kiện cần thiết sẽ xuất hiện để thực hiện đẳng thức $f(x)=g(x)$: nếu $x$ là nghiệm của phương trình thì $x \in M$. Chúng ta sẽ gọi bài toán được giải bằng phương pháp này bài toán từ các điều kiện cần thiết của Nhật Bản.

Hãy để chúng tôi minh họa những gì đã được nói bằng các ví dụ cụ thể.

Bài toán 1 (MSU, 1983). Giải bất đẳng thức

$$\left( \sqrt{x^2}-5x+6+1 \right) \log_3 \frac{2x}{5} + \frac{1}{x} \sqrt{10x-2x^2-12} \leq 0.$$

Miền xác định của bất đẳng thức này là tập hai phần tử {2; 3}. Kiểm tra cho thấy chỉ $x=2$ thỏa mãn bất đẳng thức.

Bài toán 2. Tại giá trị nào của tham số a thì hệ phương trình

$$\begin{cases} a(x^4+1)=y+1-|x|, \\ x^2+y^2=1 \end{cases}$$

có một lời giải.

Rõ ràng, nếu $(x_0; y_0)$ là lời giải của một hệ thống, thì $(-x_0; y_0)$ cũng là lời giải của nó. Do đó, điều kiện $x=0$ là cần thiết để tồn tại duy nhất lời giải. Lưu ý rằng nó không xứng đáng: hệ thống của chúng tôi có thể có một số lời giải có dạng $(0; y_0)$ hoặc không có lời giải nào cả.

Hãy đặt $x=0$. Sau đó

$$\begin{cases} a=y+1, \\ y^2=1. \end{cases}$$

Do đó $a=0$ hoặc $a=2$.

Vì vậy, để tìm giá trị dấu phẩy của tham số, chúng ta phải chọn nó từ tập {0; 2}. Với $a=0$ chúng ta nhận được:

$$\begin{cases} y+1-|x|=0, \\ x^2+y^2=1, \end{cases}$$

Ở đâu

$$\begin{cases} |x|=y+1, \\ y^2+2y+1+y^2=1, \end{cases}$$

tư thế

$$\begin{cases} x=1, \\ y=0, \end{cases}$$

hoặc

$$\begin{cases} x=-1, \\ y=0, \end{cases}$$

⟦folio 45⟧

---
running_head:
folio:
---

Như bạn có thể thấy, có ba hệ thống lời giải, có nghĩa là $a=0$ không thỏa mãn các điều kiện của bài toán.
Với $a=2$ chúng ta nhận được:
$$\begin{cases} 2x^4 + |x| = y - 1, \\ x^2 + y^2 = 1. \end{cases}$$
Rõ ràng là $2x^4 + |x| \geq 0$. Từ phương trình đầu tiên, chúng ta có $y \geq 1$, từ phương trình thứ hai - $y \leq 1$. Vì vậy, $y=1$ có nghĩa là $x=0$. Việc kiểm tra cho thấy cặp (0; 1) là lời giải và do hạn chế đối với biến $y(y \geq 1$ và $y \leq 1)$ nên nó là duy nhất.
Đáp số: $a=2$.
Bài toán 3 (MSU, 1990). Với những giá trị nào của tham số c thì phương trình $x^2 - 2c \sin(\cos x) + 2 = 0$ có lời giải duy nhất?
Rõ ràng, $x=0$ là điều kiện cần để tồn tại một nghiệm duy nhất của phương trình này.
Với $x=0$ chúng ta có
$$c = \frac{1}{\sin 1}.$$
Hãy để chúng tôi chứng minh rằng giá trị tham số này là đặc biệt.
Thật vậy, với $c = \frac{1}{\sin 1}$ chúng ta thu được
$$x^2 + 2 = \frac{2}{\sin 1} \sin(\cos x).$$
(1)
Rõ ràng là $x^2 + 2 \geq 2$. Xét hàm $f(t) = \sin t$. Đối với $t \in [-1; 1] \subset [-\pi/2; \pi/2]$, hàm $f$ trả về. Vì vậy, $\sin(\cos x) \leq \sin 1$. Từ đây
$$\frac{2 \sin(\cos x)}{\sin 1} \leq \frac{2 \sin 1}{\sin 1} = 2.$$
Điều này có nghĩa là phương trình (1) tương đương với hệ
$$\begin{cases} x^2 + 2 = 2, \\ \frac{2 \sin(\cos x)}{\sin 1} = 2, \end{cases}$$
chỉ có lời giải $x=0$.
Đáp số: $c = \frac{1}{\sin 1}$.
Bài toán 4 (MSU, 1988). Tìm tất cả các giá trị của tham số $a$, trong đó

nhiều hệ thống tương đương
$$\begin{cases} x + 2y = 2 - a, \\ -x + ay = a - 2a^2 \end{cases}$$
(2)
$$\begin{cases} x^2 - y^4 - 4x + 3 = 0, \\ 2x^2 + y^2 + (a^2 + 2a - 11)x + 12 - 6a = 0. \end{cases}$$
(3)
Hệ (2) bao gồm hai phương trình tuyến tính với hai biến. Nó có lời giải duy nhất nếu $a \neq -2$.
Bằng cách xác minh trực tiếp, chúng tôi xác định rằng hệ thống $a=-2$ (2) không có lời giải.
Hệ thống (3) tại $a=-2$ trở thành:
$$\begin{cases} x^2 - y^4 - 4x + 3 = 0, \\ 2x^2 + y^2 - 11x + 24 = 0. \end{cases}$$
Phương trình thứ hai chứa tam thức bậc hai đối với $x: 2x^2 - 11x + 24$. Phân biệt đối xử của nó được in dấu, vì vậy phương trình thứ hai không có.
Do đó, $a=-2$ thỏa mãn điều kiện của bài toán.
Hãy để bây giờ $a \neq -2$. Trong trường hợp này, hệ thống thứ nhất có lời giải duy nhất, do đó, để hệ thống (2) và (3) tương đương nhau, hệ thống thứ hai cũng cần có lời giải duy nhất. (Lưu ý rằng điều kiện đủ cho sự tương đương của chúng là sự trùng hợp của lời giải.)
Ở đây, như trong bài toán 1, các điều kiện $y=0$ là cần thiết để tồn tại một hệ thống lời giải duy nhất (3) (kiểm tra!). Tại $y=0$ hệ thứ hai có dạng
$$\begin{cases} x^2 - 4x + 3 = 0, \\ 2x^2 + (a^2 + 2a - 11)x + 12 - 6a = 0. \end{cases}$$
Từ đây
$$\begin{cases} x = 1, \\ a^2 - 4a + 3 = 0, \end{cases}$$
hoặc
$$\begin{cases} x = 3, \\ a^2 = 1. \end{cases}$$
Do đó, các giá trị bắt buộc của tham số $a$, nếu chúng tồn tại, sẽ thuộc tập hợp {-1; 1; 3}. Đối với hệ thống $a=-1$ (2):
$$\begin{cases} x + 2y = 3, \\ -x - y = -3. \end{cases}$$

⟦folio 46⟧

---
running_head:
folio:
---

Nó có một lời giải (3; 0). Hệ thứ hai có dạng
$$\begin{cases} x^2 - y^4 - 4x + 3 = 0, \\ 2x^2 + y^2 - 12x + 18 = 0, \end{cases}$$
hoặc
$$\begin{cases} x^2 - y^4 - 4x + 3 = 0, \\ 2(x - 3)^2 + y^2 = 0. \end{cases}$$
Do đó $x = 3, y = 0$. Vì lời giải của hệ trùng khớp nên $a = -1$ thỏa mãn điều kiện bài toán.
Đối với $a = 1$, thật dễ dàng để thiết lập rằng hệ thống (2) có một lời giải $- (1; 0)$ và hệ thống (3) có hai lời giải $- (1; 0)$, $(3; 0)$.
Đối với $a = 3$, hệ thống (2) có lời giải $\left(\frac{27}{5}; -\frac{16}{5}\right)$ duy nhất không thỏa mãn hệ thống (3).
Đáp số: $a = -2$ hoặc $a = -1$.
Bài toán 5 (KPI, 1989). Với những số nguyên âm nào $n$ thì hàm $f(x) = \cos nx \sin \frac{15x}{n^2}$ thỏa mãn điều kiện $f(x + 5\pi) = f(x)$ với mọi $x \in R$.
Theo điều kiện bài toán đẳng thức
$$\cos n(x + 5\pi) \sin \frac{15x}{n^2} (x + 5\pi) =
= \cos nx \sin \frac{15x}{n^2}$$
phải đúng với bất kỳ $x$ thực nào, và do đó cũng đúng với $x = 0$.
Trong trường hợp này chúng ta có
$$\cos 5\pi n \cdot \sin \frac{75\pi}{n^2} = 0.$$
Vì $\cos 5\pi n \neq 0$ thì $\sin \frac{75\pi}{n^2} = 0$, tức là $\frac{75}{n^2} = k$, trong đó $k$ là số nguyên. Do đó $n^2 = 1$ hoặc $n^2 = 25$. Về mặt quan tâm chỉ có các giá trị âm $n$, do đó, lời giải bài toán nên được tìm kiếm trong tập hợp $-1; -5$. Việc kiểm tra cho thấy rằng cả đối với $n = -1$ và $n = -5$ đẳng thức của chúng ta đều đúng với mọi $x$ thực.
Đáp số: $n = -1$ hoặc $n = -5$.
Tất nhiên, người đọc sẽ hỏi tại sao chúng ta thay thế chính xác $x = 0$ vào đẳng thức của mình? Tất nhiên bạn có thể thay thế một số dấu hiệu khác
giá trị $x$: suy cho cùng, đẳng thức phải được giữ cho mọi $x$. Nhưng $x = 0$ dễ sử dụng hơn nhiều và không tạo ra các công thức rườm rà. Trong những trường hợp như vậy, việc lựa chọn các giá trị biến có lợi nhất thường dựa trên trực giác và kinh nghiệm cá nhân.
Bài toán 6 (MSU, 1989). Tìm mọi thứ với điều đó cho bất kỳ hệ thống $b$ nào
$$\begin{cases} (1 + 3x^2)^c + (b^2 - 4b + 5)^y = 2, \\ x^2y^2 - (2 - b)xy + c^2 + 2c = 3. \end{cases}$$
có ít nhất một lời giải.
Hệ thống này phải có ít nhất một lời giải cho bất kỳ $b$ nào và do đó cho $b = 2$. Trong trường hợp này
$$\begin{cases} (1 + 3x^2)^c = 1, \\ x^2y^2 + c^2 + 2c = 3, \end{cases}$$
Ở đâu
$$\begin{cases} x = 0, \\ c^2 + 2c = 3 \end{cases}$$ hoặc $$\begin{cases} c = 0, \\ x^2y^2 = 3. \end{cases}$$
Phạm vi giá trị “nghi ngờ” cho biến $c$ về cơ bản là $-3; 0; 1$.
Với $c = -3$ chúng tôi nhận được
$$\frac{1}{(1 + 3x^2)^3} + (b^2 - 4b + 5)^y = 2,$$
$$x^2y^2 - (2 - b)xy = 0.$$
Rõ ràng, hệ thống này có lời giải $(0; 0)$ cho bất kỳ $b$ nào.
Tại $c = 0$
$$\begin{cases} (b^2 - 4b + 5)^y = 1, \\ x^2y^2 - (2 - b)xy = 3. \end{cases}$$
Nếu $b \neq 2$ thì lời giải của phương trình thứ nhất $y = 0$ không thỏa mãn phương trình thứ hai. Nhưng theo điều kiện, hệ thống phải lời giải đối với bất kỳ $b$ nào, nghĩa là $c = 0$ sẽ phải bị loại khỏi danh sách “nghi phạm”.
Tại $c = 1$
$$\begin{cases} 3x^2 + (b^2 - 4b + 5)^y = 1, \\ x^2y^2 - (2 - b)xy = 0. \end{cases}$$
Rõ ràng, hệ thống này có lời giải $(0; 0)$ cho bất kỳ $b$ nào.
Đáp số: $c = 1$ hoặc $c = -3$.
Bài toán 7 (MAI, 1989). Với cái gì $x$ với bất kỳ $y$ nào cũng có $z$ sao cho

⟦folio 47⟧

---
running_head:
folio:
---

$$\sin(x + y + z) = \cos\left(2x + \frac{\pi}{3}\right)\left|y + \frac{1}{2}\right| + \frac{|y - 3/2|}{2\cos x}$$

Hãy thay $y = -1/2$ vào phương trình. Sau đó
$$\sin\left(x + z - \frac{1}{2}\right) = \frac{1}{\cos x},$$

từ đâu $\cos x = 1$ hoặc $\cos x = -1$. Khi $\cos x = 1$, tức là $x = 2\pi k$, $k$ là số nguyên, chúng ta nhận được
$$\sin(2\pi k + y + z) = \cos\left(4\pi k + \frac{\pi}{3}\right)\left|y + \frac{1}{2}\right| + \frac{|y - 3/2|}{2\cos x},$$
theo,
$$\sin(y + z) = \frac{|y + 1/2|}{2} + \frac{|y - 3/2|}{2}.$$
chúng tôi có
$$|\sin(y + z)| \leq 1,$$
Nhưng
$$\frac{|y + 1/2|}{2} + \frac{|y - 3/2|}{2} \geq 1.$$
Tại hình 1 có đồ thị của hàm số
$$f(x) = \frac{|y + 1/2|}{2} + \frac{|y - 3/2|}{2}.$$
Rõ ràng là đẳng thức từ điều kiện bài toán cho $x = 2\pi k$ không được thỏa mãn với mọi $y$ mà chỉ thỏa mãn với $y \in [-1/2; 3/2].$

Khi $\cos x = -1$, tức là $x = \pi + 2\pi k$, $k$ là số nguyên, chúng ta nhận được
$$\sin(\pi + 2\pi k + y + z) = \cos\left(2\pi + 4\pi k + \frac{\pi}{3}\right)\left|y + \frac{1}{2}\right| + \frac{|y - 3/2|}{2\cos(\pi + 2\pi k)},$$

Ở đâu
$$2\sin(y + z) = |y - 3/2| - |y + 1/2|.$$
Bởi vì
$$|2\sin(y + z)| \leq 2,$$
thì bất đẳng thức phải được thỏa mãn
$$||y - 3/2| - |y + 1/2|| \leq 2.$$
hình 2 hiển thị đồ thị của hàm số
$$f(y) = \left||y - \frac{3}{2}| - |y + \frac{1}{2}| \right|.$$
Trong trường hợp này, với bất kỳ $y$ nào, người ta có thể chọn $z$ sao cho đẳng thức (4) được thỏa mãn.

Đáp số: $x = \pi + 2\pi k$, $k \in \mathbf{Z}$.
Bài toán 8 (MAI, 1988). Tại giá trị nào của tham số $a$ các phương trình
$$\sin 2x + a = \sin x + 2a \cos x$$
u
$$2\cos 2x + a^2 = 5a \cos x - 2$$
chúng có tương đương không?
Dễ dàng thấy rằng $x = \frac{\pi}{3}$ là nghiệm của phương trình đầu tiên đối với bất kỳ $a$ nào. Vì

⟦folio 48⟧

---
running_head:
folio:
---

Sự tương đương của phương trình đòi hỏi nó cũng phải là nghiệm của phương trình thứ hai.

Với $x = \frac{\pi}{3}$ chúng tôi nhận được
$$-1 + a^2 = \frac{5a}{2} - 2,$$
do đó các ứng cử viên cho đáp số là $a = 2$ và $a = 1/2$.

Tại $a = 2$ phương trình đầu tiên có dạng
$$\sin 2x + 2 = \sin x + 4 \cos x,$$
và thứ hai -
$$\cos 2x - 5 \cos x + 3 = 0.$$

Người đọc có thể dễ dàng nhận thấy rằng mỗi phương trình trong hai phương trình cuối đều tương đương với phương trình $\cos x = 1/2$.

Tại $a = 1/2$ phương trình đầu tiên trở thành:
$$\sin 2x + 1/2 = \sin x + \cos x,$$
và cái thứ hai là như thế này:
$$2 \cos 2x + \frac{1}{4} = \frac{5}{2} \cos x - 2.$$

Rõ ràng, nghiệm của cái đầu tiên $x = -\frac{\pi}{3}$ không phải là nghiệm của cái thứ hai.

Đáp số: $a = 2$.

Trong tất cả các bài toán trước, các điều kiện đủ để loại trừ một tham số đã được thiết lập nhờ quá trình xác minh. Tuy nhiên, một cách tiếp cận khác cũng có thể thực hiện được.

Vì mọi điều kiện đủ đều cần thiết nhưng không phải điều kiện cần nào cũng đủ, rõ ràng là nhất quán

Bất kỳ điều kiện cần thành công nào cuối cùng cũng có thể được giảm xuống thành điều kiện đủ.

Để kết luận, chúng tôi đưa ra một ví dụ phản ánh những điều trên.

Bài toán 9 (MSU, 1988). Với giá trị nào của tham số $a$ và $b$ phương trình

$$|x + \cos^2 4a - 2 \sin a \cos^4 4a| + |x + \sin^2 a| = b \left(a + \frac{3\pi}{2}\right)$$

có một lời giải?

Xét hàm $f(x) = |x - c| + |x - d| + e (c, d$ và $e$ - một số số). Không làm mất tính tổng quát của lập luận, chúng ta đặt $d > c > 0, e > 0$. Đồ thị được xem xét bởi hàm được mô tả dưới dạng sơ đồ trong hình 3.

Rõ ràng là phương trình $f(x) = A$ có một nghiệm duy nhất tại $c = d$ (hình 4).

Đối với Pozny, để phương trình $f(x) = 0$ có một nghiệm duy nhất thì chỉ cần thỏa mãn điều kiện $c = d$ và $e = 0$ (hình 5).

Vì vậy, để tìm giá trị ban đầu của tham số $a$ và $b$ ta cần giải hệ

$$\begin{cases} \sin^2 a = 2 \sin a \cos^4 4a - \cos^2 4a, \\ b \left(a + \frac{3\pi}{2}\right) = 0. \end{cases}$$

Hãy xem xét phương trình đầu tiên của nó:

$$\sin^2 a - 2 \sin a \cos^4 4a = -\cos^2 4a.$$

Hãy thêm $\cos^8 4a$ vào cả hai phần của nó:

⟦folio 49⟧

---
running_head:
folio:
---

$$\sin^2 a - 2 \sin a \cos^4 4a + \cos^8 4a = \cos^8 4a - \cos^2 4a.$$
Sau đó
$$(\sin a - \cos^4 4a)^2 = \cos^8 4a - \cos^2 4a.$$
Vế phải của phương trình thu được là không dương:
$$\cos^8 4a - \cos^2 4a = \cos^2 4a(\cos^6 4a - 1) \leq 0,$$
Điều này có nghĩa là phương trình chỉ có lời giải
$$\begin{cases} \sin a = \cos^4 4a, \\ \cos 4a = 0 \end{cases}$$
hoặc
$$\begin{cases} \sin a = \cos^4 4a, \\ \cos^6 4a = 1. \end{cases}$$
Hệ thống đầu tiên trong số này mang lại
$$a = \frac{\pi}{2} + 2\pi k, k - целое.$$
Từ giây, chúng ta thu được điều đó, một mặt, $a = \frac{\pi}{8} + \frac{\pi k}{4}$, và mặt khác, $a = \pi k$, nhưng đối với số nguyên $k$ thì điều này không thể xảy ra.
Sau đó chúng tôi có
$$\begin{cases} a = \frac{\pi}{2} + 2\pi k, \\ b \left( a + \frac{3\pi}{2} \right) = 0, \text{ т. е.} \end{cases}$$
hoặc
$$\begin{cases} a = \frac{\pi}{2} + 2\pi k, \\ b = 0 \end{cases}$$
hoặc
$$\begin{cases} a = \frac{\pi}{2} + 2\pi k, \\ a = -\frac{3\pi}{2}, \\ b - целое. \end{cases}$$
Đáp số: $b = 0, a = \frac{\pi}{2} + 2\pi k, k - целое, или $a = -\frac{3\pi}{2}, b là số nguyên thực.

Bài toán dành cho độc lập lời giải
1 (MSU, 1990). Với giá trị nào của tham số $b$ phương trình
$$2x^2 - b \mathrm{tg} \cos x + b^2 = 0$$
có một lời giải?
2 (MSU, 1987). Tìm tất cả các giá trị của tham số $a$ mà hệ thống
$$\begin{cases} 3 \cdot 2^{|x|} + 5 |x| + 4 = 3y + 5x^2 + 3a, \\ x^2 + y^2 = 1 \end{cases}$$
có một lời giải.
3 (MIREA, 1983). Với giá trị nào của tham số $a$ thì hệ bất đẳng thức
$$\begin{cases} y \geqslant (x + y)^2 - x - 2y - a, \\ x \geqslant (y - x)^2 - 3y + 2x + a \end{cases}$$
có một lời giải?
4 (MAI, 1989). Với những giá trị thực nào của $x$, với bất kỳ $y$ thực nào, có $z$ sao cho
$$\cos (2x - y + z) = |y^3 - 1| \cos \left( \frac{4\pi}{3} - 2x \right) + \frac{|y^3 + 1|}{2 \sin x} ?$$
5 (MSU, 1978). Tìm tập hợp tất cả các cặp số $(a; b)$, với mỗi số đó, với tất cả $x$, đẳng thức sau có giá trị:
$$a \sin x + b = \sin (ax + b).$$
6 (Đại học bang Ural, 1976). Tìm các giá trị như vậy của tham số $a$, với mỗi giá trị đó bất đẳng thức
$$\sqrt{x^2 + 4x + 7} \leq x + 3$$
và phương trình
$$2^{x+2} - |2^{x+1} - a| = 2^{x+1} + 1$$
là tương đương.
7 (MSU, 1974). Tìm tất cả các giá trị thực $\alpha$, với mỗi giá trị đó có các số nguyên chẵn $(x, y, u, v)$ thỏa mãn các đẳng thức
$$x^2 + y^2 = (107 - \alpha)(\alpha - 91),$$
$$54(u^2 - v^2) = \alpha(15u + 3v - \alpha).$$
