---
id: 1992-6-egorov-o-diskriminante-e7c2ba1f
issue: kvant_1992_6
year: 1992
number: "6"
title: Về người phân biệt đối xử
authors:
  - Егоров А. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 61
page_last: 64
page_labels: 59-62
lang: vi
source: kvant_digital
extraction: vision
content_sha256: fbec622688c327e0eef1cb0d216088311e66e36795b672ac69d7c1ebe094590c
prompt_sha256: draft-1
translated_from: content/ru/1992/06/articles/18_egorov-o-diskriminante-e7c2ba1f.md
source_content_sha256: 47752bc56d550f406c09308521db4f4913f3a297d500a57fdc8073a318c9ff9b
translation_model: draft
translation_run: vi-draft-gaps-2026-11-07
translation_quality: draft
---

⟦folio 59⟧

---
running_head:
folio:
---

$(x+y-1)^2+(2x-y)^2=0.$

Tuy nhiên, để đạt được sự chuyển đổi như vậy không phải là điều dễ dàng. Do đó, chúng ta sẽ làm khác đi: coi phương trình của chúng ta là phương trình bậc hai $x$ với các hệ số phụ thuộc vào $y$:

$$5x^2-2(y+1)x+2y^2-2y+1=0.$$

Viết điều kiện giải được, ta thu được sau khi biến đổi

$$D/4=(y+1)^2-5(2y^2-2y+1)=-9y^2+12y-4=-(3y-2)^2,$$

từ đó nó ngay lập tức theo sau $y=2/3$ (nếu không thì phân biệt đối xử là âm). Bây giờ thật dễ dàng để tìm thấy điều đó $x=1/3$.

Đáp số: $(1/3; 2/3)$.

Bây giờ hãy giải hệ phương trình.

Bài toán 2 (MSU, Khoa Quân sự, 1979). Giải hệ phương trình

$$\begin{cases} x^2-2xy+2y^2+2x-8y+10=0, \\ 2x^2-7xy+3y^2+13x-4y-7=0. \end{cases}$$

Lời giải. Rất khó để đối phó với nhiệm vụ này bằng các phương pháp tiêu chuẩn. Do đó, chúng ta sẽ làm tương tự như đã làm ở bài toán đầu tiên - chúng ta sẽ giải phương trình đầu tiên dưới dạng phương trình bậc hai đối với $x$. Phân biệt đối xử của nó bằng

$$D/4=-(y-3)^2.$$

Hóa ra phương trình chỉ có lời giải thực với một giá trị duy nhất là $y$, cụ thể là cho $y=3$. Bây giờ, hãy tìm $x=2$ đó và kiểm tra kết quả lời giải bằng cách thay thế trực tiếp vào phương trình thứ hai.

Đáp số: $(2; 3)$.

Trong hệ sau, số phương trình nhỏ hơn số ẩn.

Bài toán 3. Giải hệ phương trình

$$\begin{cases} x+y+z=\sqrt{3}, \\ x^2+y^2+z^2=1. \end{cases}$$

Lời giải. Biểu thị $x$ theo $y$ và $z$ từ phương trình đầu tiên, chúng ta thu được sau khi thay thế vào phương trình thứ hai:

$$y^2+(z-\sqrt{3})y+z^2-\sqrt{3}z+1=0.$$

⟦folio 60⟧

---
running_head:
folio:
---

Nó là một đường tương đối vuông $y$ với các hệ số phụ thuộc vào $z$. Sự phân biệt đối xử của nó
$$D = -3z^2 + 2\sqrt{3}z - 1 = -(\sqrt{3}z - 1)^2$$
không thể âm, và do đó $z = 1/\sqrt{3}$. Phần còn lại là rõ ràng.
Đáp số: $(1/\sqrt{3}; 1/\sqrt{3}; 1/\sqrt{3})$.

Bài 4. Giải phương trình
$$\cos x + \cos y - \cos(x+y) = 3/2.$$

Lời giải. Biến đổi vế trái bằng các công thức quen thuộc, chúng ta thu được phương trình
$$4\cos \frac{x+y}{2}\cos \frac{x-y}{2} - 4\cos^2 \frac{x+y}{2} - 1 = 0,$$
mà sau khi thay thế $t = \cos \frac{x+y}{2}$ được rút gọn về dạng
$$4t^2 - 4\cos \frac{x-y}{2}t + 1 = 0.$$

Viết điều kiện giải được, ta thu được bất đẳng thức
$$D/4 = 4\left(\cos^2 \frac{x-y}{2} - 1\right) \geq 0,$$
từ đó nó ngay lập tức theo sau $\cos^2 \frac{x-y}{2} = 1$.

Còn lại là giải hai hệ phương trình
$$\begin{cases} \cos \frac{x-y}{2} = 1, \\ \cos \frac{x+y}{2} = \frac{1}{2} \end{cases}$$ và
$$\begin{cases} \cos \frac{x-y}{2} = -1, \\ \cos \frac{x+y}{2} = -\frac{1}{2}. \end{cases}$$

Đáp số: $(\pm \frac{\pi}{3} + 2(k+n)\pi; \pm \frac{\pi}{3} + 2(k-n)\pi); \quad (\pm \frac{2\pi}{3} + \pi + 2(k+n)\pi; \pm \frac{2\pi}{3} - \pi + 2(k-n)\pi), k, n \in \mathbb{Z}.$

Nhiệm vụ 5 (MIREA, 1990) Với giá trị nào của tham số a thì tồn tại một cặp $(x; y)$ thỏa mãn phương trình
$$ax^2 + (3a+2)y^2 + 4axy - 2ax + (4-6a)y + 2 = 0?$$

Lời giải. Với $a = 0$ ta thu được phương trình
$$2y^2 + 4y + 2 = 0,$$

có gốc duy nhất là $y = 1$.
Dễ dàng thấy rằng trong trường hợp này tất cả các cặp $(x; -1)$ sẽ là nghiệm của phương trình ban đầu nên $a = 0$ không thỏa mãn điều kiện.

Đối với $a \neq 0$, như trước đây, hãy coi phương trình ban đầu là phương trình bậc hai $x$:
$$ax^2 + 2a(2y-1)x + (3a+2)y^2 + (4-6a)y + 2 = 0.$$
Đối với anh ấy
$$D/4 = a(a-2)(y+1)^2.$$
Nếu $a(a-2) < 0$ thì $y = -1$, $x = 3$ là lời giải duy nhất. Nếu $a(a-2) \geq 0$, phương trình ban đầu của $x$ có lời giải với mọi $y$.
Đáp số: $0 < a < 2$.

Bất bình đẳng
Nhắc lại rằng bất đẳng thức
$$ax^2 + bx + c \geq 0 (a > 0)$$
hài lòng với tất cả $x$ khi và chỉ khi
$$b^2 - 4ac \leq 0.$$
Bất bình đẳng
$$ax^2 + bx + c < 0$$
có lời giải tại $a > 0$ khi và chỉ khi phương trình tương ứng $ax^2 + bx + c = 0$ có ​​2 nghiệm khác nhau, tức là tại $D > 0$.

Lời giải của bài toán nổi tiếng tiếp theo minh họa khá rõ phương pháp lời giải, dựa trên các tính chất được liệt kê của bất đẳng thức bậc hai.

Nhiệm vụ 6. Chứng minh bất đẳng thức
$$a^2 + b^2 + c^2 \geq ab + bc + ac,$$
thực phẩm $a, b, c$ - bất kỳ số thực nào.

Gợi ý. Bất bình đẳng
$$a^2 - a(b+c) + b^2 + c^2 - bc \geq 0$$
— tương đối bậc hai $a$ với các hệ số phụ thuộc vào $b$ và $c$. Phân biệt đối xử của nó, bằng $-3(b-c)^2$, không dương và bằng 0 tại $b = c$ và dấu bằng trong

⟦folio 61⟧

---
running_head:
folio:
---

bất đẳng thức ban đầu chỉ có thể xảy ra với $a = b = c$.
Nhưng đây là một bài toán phức tạp hơn một chút.

Bài toán 7. Chứng minh bất đẳng thức
$6a + 4b + 5c \geqslant 5\sqrt{ab} + 7\sqrt{ac} + 3\sqrt{bc}$, ở đâu $a \geqslant 0, b \geqslant 0, c \geqslant 0$.

Lời giải. Đặt $t = \sqrt{a}$, chúng ta viết bất đẳng thức dưới dạng bậc hai $t$:
$$6t^2 - (5\sqrt{b} + 7\sqrt{c})t + 4b + 5c - 3\sqrt{bc} \geqslant 0.$$

Phân biệt của tam thức bậc hai ở vế trái của bất đẳng thức thu được bằng
$$(5\sqrt{b} + 7\sqrt{c})^2 - 24(4b + 5c - 3\sqrt{bc}) = -71(\sqrt{b} - \sqrt{c})^2,$$
tức là âm tại $b \neq c$ và bằng 0 tại $b = c$.

Do đó, vế trái của bất đẳng thức này luôn không âm và chỉ có thể bằng 0 với $b = c = a$.

Bài toán 8. Với giá trị nào của $a$ thì bất đẳng thức
$$-1 < \frac{ax^2 + x + 2}{x^2 + 1} < 3$$
giữ cho tất cả $x$?

Lời giải. Điều kiện ngay lập tức hàm ý một sự phát biểu lại của bài toán: theo giá trị nào $a$ mỗi bất đẳng thức
$$ax^2 + x + 2 < 3x^2 + 3u$$
$$ax^2 + x + 2 > -x^2 - 1$$
giữ cho tất cả $x$?

Đối với trường hợp đầu tiên, $(a - 3)x^2 + x - 1 < 0$, chúng ta thu được điều kiện
$$\begin{cases} a < 3, \\ a < 11/4, \end{cases}$$
tức là $a < 11/4$. Tương tự, đối với bất đẳng thức thứ hai, chúng ta có $a > -1/3$.
Đáp số: $-1/3 < a < 11/4$.

Bài toán 9 (MEPhI, 1990). Với giá trị thực nào của $a$ thì bất đẳng thức
$$1 - \log_{1/7}(x^2 + 1) \geqslant \log_7(ax^2 + 4x + a)$$
giữ cho tất cả $x$?

Lời giải. Bất đẳng thức ban đầu tương đương với hệ
$$7(x^2 + 1) \geqslant ax^2 + 4x + a > 0,$$
hoặc
$$\begin{cases} (7 - a)x^2 - 4x + 7 - a \geqslant 0, \\ ax^2 + 4x + a > 0. \end{cases}$$

Hệ cuối cùng đúng với mọi $x$ khi và chỉ khi mỗi bất đẳng thức bậc hai đúng với mọi $x$, tức là, trong các điều kiện
$$\begin{cases} 0 < a < 7, \\ 4 - (7 - a)^2 \leqslant 0, \\ 4 - a^2 < 0. \end{cases}$$

Giải hệ thống kết quả, chúng tôi đạt được đáp số.
Đáp số: $2 < a \leqslant 5$.

Trong bài toán tiếp theo, trước khi sử dụng phương pháp của chúng tôi, trước tiên chúng tôi phải “xử lý” các điều kiện.

Bài toán 10 (MSU, Khoa Kinh tế, 1988). Tìm tất cả các giá trị của tham số $a$ mà bất đẳng thức
$$|3\sin^2x + 2a\sin x\cos x + \cos^2x + a| \leqslant 3$$
giữ cho mọi giá trị của $x$.

Lời giải. Nếu $x = 0$, bất đẳng thức có dạng
$$|a + 3| \leqslant 3.$$

lời giải của nó mang lại cho chúng tôi những hạn chế đối với $a: -6 \leqslant a \leqslant 0$.

Đối với $cos x \neq 0$, chia cả hai vế của bất đẳng thức cho $\cos^2x$ và thực hiện thay thế $t = tgx$. Kết quả là chúng ta thu được (sử dụng công thức $\frac{1}{\cos^2x} = 1 + tg^2x$) bất đẳng thức
$$|(a + 3)t^2 + 2at + a + 1| \leqslant 3(1 + t^2),$$
phải giữ cho tất cả $t$.

Bất đẳng thức này tương đương với hệ
$$-3 - 3t^2 \leqslant (a + 3)t^2 + 2at + a + 1 \leqslant 3(1 + t^2).$$

⟦folio 62⟧

---
running_head:
folio:
---

Với $a=0$ mọi bất đẳng thức đều đúng. Đối với $a \neq 0$, như trước đây, viết ra các điều kiện để các bất đẳng thức này được thỏa mãn với mọi $t$, chúng ta đi đến hệ bất đẳng thức cho $a$ và khi giải nó, chúng ta thu được đáp số.
Đáp số: $-12/5 \leq a \leq 0$.

Phạm vi chức năng.
Tối đa và tối thiểu

Khi tìm phạm vi giá trị của hàm, thường rất hữu ích khi sử dụng cách sau

Quét. Cho một số hàm $y=f(x)$. Xét phương trình $f(x)=a$. Phương trình này có lời giải khi và chỉ nếu số $a$ nằm trong phạm vi hàm $f$.

Trong các bài toán sau, việc áp dụng điều kiện giải được cho phương trình bậc hai và bất phương trình giúp đơn giản hóa vấn đề và tỏ ra thuận tiện hơn việc nghiên cứu hàm $f$ bằng phương pháp phân tích.

Bài toán 11. Tìm phạm vi giá trị của hàm $y=x/(x-1)^2$.

Lời giải. Bài toán ngay lập tức trùng khớp với các điều sau: a phương trình $x/(x-1)^2=a$ hoặc $ax^2-(2a+1)x+a=0$ có nghiệm là gì?

Trước hết, $a=0$ có gốc $x=0$. Nếu $a \neq 0$, tất cả các thuộc tính của lời giải đều là bất đẳng thức $D=4a+1 \geq 0$.

Đáp số: $[-1/4; +\infty)$.

Bây giờ một số câu khó hơn bài toán.

Bài toán 12. Tìm giá trị nhỏ nhất của hàm số

$$y=x(x+1)(x+2)(x+3).$$

Gợi ý. Vì $y=(x^2+3x)(x^2+3x+2)$, chúng tôi thực hiện thay thế $t=x^2+3x$.

Phương trình $t(t+2)=a$ có nghiệm tại $a \geq -1$, với vế trái bằng $-1$ tại $t=-1$. Vẫn còn phải xác minh rằng phương trình $x^2+3x=-1$ có nghiệm.

Đáp số: $-1$.

Bài toán 13 (MSU, cơ chế, 1989). Tìm giá trị lớn nhất $z$ mà tồn tại các số $x, y$ thỏa mãn phương trình

$$2x^2+2y^2+z^2+xy+xz+yz=4.$$

Lời giải. Phân biệt của phương trình bậc hai đối với $x$ với các hệ số phụ thuộc vào $y$ và $z$ phải không âm, tức là bất đẳng thức $D=(y+z)^2-16y^2-8yz-8z^2+32 \geq 0$ phải được thỏa mãn, hoặc

$$15y^2+6yz+7z^2-32 \leq 0.$$

Bất đẳng thức bậc hai đối với $y$ chỉ có lời giải nếu

$$9z^2-105z^2+15 \cdot 32 \geq 0,$$

tức là ở $z^2 \leq 5$.

Vì vậy, $-\sqrt{5} \leq z \leq \sqrt{5}$, nên $z$ không thể lớn hơn $\sqrt{5}$. Nếu $z=\sqrt{5}$, thì bất đẳng thức có một lời giải duy nhất đối với $y$. Nhưng khi đó cũng tồn tại $x$ (cùng một cái duy nhất) sao cho đồ chơi $(x, y, z)$ thỏa mãn phương trình

$$2x^2+2y^2+z^2+xy+xz+yz=4.$$

Đáp số: $\sqrt{5}$.

bài toán tiếp theo, mặc dù bên ngoài khác với cái trước, nhưng vẫn dễ dàng khớp với nó.

Bài toán 14 (MSU, Khoa Sinh học, 1989). Các số $x, y, z$ sao cho $x^2+2y^2+z^2=2$. Giá trị lớn nhất có thể thuộc về biểu thức $2x+y-z$ là gì?

Gợi ý. Hãy để $t=2x+y-z$. Sau đó, sau khi thay thế $z=2x+y-t$ vào phương trình, chúng ta đạt được bài toán, chỉ khác với phương trình trước ở giá trị của các hệ số. Chúng tôi để độc giả tiếp tục tất cả các tính toán cần thiết của chính Telano.

Đáp số: $t_{\max}=\frac{4}{3}\sqrt{6}$.

Tương tự, có thể có lời giải và tiếp theo là bài toán.

Bài toán 15 (MSU, Khoa Tâm lý học, 1986). Tìm số nhỏ nhất
