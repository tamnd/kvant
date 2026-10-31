---
id: 1986-2-v-reshenie-stereometricheskoy-zadachi-a4db58fc
issue: kvant_1986_2
year: 1986
number: "2"
title: '[Lời giải lập thể bài toán]'
authors:
  - Дубровский В. Н.
rubric: raznoe
rubric_sub: Разное
page_first: 29
page_last: 29
page_labels: "27"
tag: N6CH
lang: vi
source: kvant_digital
extraction: vision
content_sha256: d21b6644bdd9772c268a1bc352c59fd29a14f99ab4113a13f35bac8567561f73
prompt_sha256: draft-1
translated_from: content/ru/1986/02/articles/09_v-reshenie-stereometricheskoy-zadachi-a4db58fc.md
source_content_sha256: 1c79a90cbc77f473099a4e0a07167b64cc1495de669dd19124484d752c1cf7be
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 27⟧

Đây là một ví dụ:
$$] - \infty; 0 [ \cup \{ 4 \}.$$
bài toán đầu tiên được đưa ra ở đầu ghi chú cũng được giải bằng cách sử dụng sơ đồ tương tự.

Chúng tôi viết lại hệ thống tương đương:
$$\begin{cases} 8x - 6p - 3 > 0, \\ \frac{x^2 + 2px}{8x - 6p - 3} = 1 \end{cases}$$
(Rõ ràng nếu thỏa mãn các điều kiện này thì bất đẳng thức $x^2 + 2px > 0$ cũng được thỏa mãn), tức là
$$\begin{cases} 8x - 6p - 3 > 0, \\ x^2 + 2x(p - 4) + 6p + 3 = 0. \end{cases}$$
Một lần nữa có thể xảy ra hai trường hợp:
Trường hợp đầu tiên. Một phương trình bậc hai có một nghiệm duy nhất, nghĩa là phân biệt của phương trình bằng 0. Hãy viết điều kiện này:
$$p^2 - 14p + 13 = 0,$$
từ đâu $p = 1$ và $p = 13$.
Với $p = 1$ chúng tôi nhận được $x = 3$; với $p = 13$ chúng ta nhận được $x = -9$. Thay thế các giá trị tìm được $x$ và $p$ vào bất đẳng thức $8x - 6p - 3 > 0$, chúng tôi tin rằng các giá trị $p = 13$, $x = -9$ là không phù hợp. Ngược lại, các giá trị $p = 1$, $x = 3$ thỏa mãn bất đẳng thức này. Do đó, phương trình ban đầu tại $p = 1$ có một nghiệm duy nhất $x = 3$*).

Trường hợp thứ hai. Một phương trình bậc hai có hai nghiệm, nghiệm lớn hơn rơi vào ODZ, còn nghiệm nhỏ hơn thì không.

Bất đẳng thức $8x - 6p - 3 > 0$ ngụ ý rằng $x > \frac{6p - 3}{8}$, vì vậy nếu $x_1$ và $x_2$ ($x_1 < x_2$) là nghiệm của phương trình bậc hai $x^2 + 2x(p - 4) + 6p + 3 = 0$, thì nó phải là $x_2 > \frac{6p + 3}{8}$ và $x_1 \leqslant \frac{6p + 3}{8}$. Một lần nữa, như trong ví dụ $\frac{\lg px}{\lg(x + 1)} = 2$ (xem hình 2), chúng ta thu được rằng tất cả các điều kiện sẽ được thỏa mãn khi và chỉ khi đối với hàm $f(x) = x^2 + 2x(p - 4) + 6p + 3$ có $f\left(\frac{6p + 3}{8}\right) \leqslant 0$. Viết điều kiện này $\left(\frac{6p + 3}{8}\right)^2 + 2 \cdot \frac{6p + 3}{8}(p - 4) + 6p + 3 \leqslant 0$, chúng ta thu được sau khi biến đổi $(6p + 3)(22p + 3) \leqslant 0$, từ đó $-\frac{1}{2} \leqslant p \leqslant -\frac{3}{22}$.

Vì vậy, đáp số trong bài toán này:
$$\left[ -\frac{1}{2}; -\frac{3}{22} \right] \cup \{1\}.$$
I. G. Gabovich
P. I. Gorshtein

*) đáp số như vậy được đưa ra trong bộ sưu tập bài toán nêu trên.

bìa của chúng tôi

Rõ ràng là phép đo lập thể bài toán bắt đầu bằng thực tế là chúng ta tái tạo một cách tổng quát cấu hình được xem xét trong đó. Trong bài toán từ trang bìa của số trước, dễ dàng nhất để hình dung cấu hình trực tiếp dọc theo lời giải. Cái lớn ở cái tiếp theo (hiển thị trên trang bìa) thực sự sẽ không lọt vào mắt chúng ta.

Lời giải dựa trên phát biểu hữu ích sau: hai đường tròn có bán kính $R_1$ và $R_2$ tiếp xúc với nhau từ bên ngoài khi và chỉ khi đoạn tiếp tuyến chung ngoài của chúng giữa các điểm tiếp tuyến là $2\sqrt{R_1R_2}$ (hình 1). Chứng minh của khẳng định này rất thuận tiện từ hình 1. Xét các đường tròn trong mệnh đề này như là tiết diện của hai quả cầu với một mặt phẳng đi qua tâm của chúng, hoặc là tiết diện của một quả cầu và một khe của một mặt phẳng đi qua tâm của quả cầu vuông góc với trục của quả cầu, ta thu được các điều kiện về tiếp tuyến ngoài của quả cầu hoặc hình trụ; ví dụ, trong trường hợp sau cần khoảng cách từ điểm tiếp xúc của quả bóng với mặt phẳng đến đường thẳng mà hình trụ dọc theo.

$AB^2 = O_2C^2 = (R_1 + R_2)^2 - (R_1 - R_2)^2$

Hình 1.
