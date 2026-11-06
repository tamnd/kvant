---
id: 1991-5-yarskiy-ot-uravneniya-k-sisteme-066e5ef6
issue: kvant_1991_5
year: 1991
number: "5"
title: Từ phương trình đến hệ thống
authors:
  - Ярский А. С.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 64
page_last: 66
page_labels: 62, 64
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 40440095dde9e78dfe968687999be04763fc642458723646eb333f3b167b5eaa
prompt_sha256: draft-1
translated_from: content/ru/1991/05/articles/09_yarskiy-ot-uravneniya-k-sisteme-066e5ef6.md
source_content_sha256: d023ff93d767442bbf6bc6a84c9d9ec3eb0c3ffaa8847f3c1bba03a3db0d801d
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 62⟧

---
running_head:
folio:
---

Từ phương trình đến hệ thống
Ứng viên Khoa học Vật lý và Toán học A. YARSKY

Hãy bắt đầu với một ví dụ khá điển hình cho kỳ thi tuyển sinh.
Bài toán 1 (MIEM, 1982). Giải phương trình
$$\sqrt{x+2} - \sqrt{x-a+2} = 1.$$
Rõ ràng các ví dụ thuộc loại này được giải bằng cách bình phương chúng hai lần. Trong trường hợp này, cần phải thu được các số đọc thu được nhờ bình phương các nghiệm không liên quan, mà nếu có một tham số trong phương trình thì đây là một nhiệm vụ khá khó khăn. Chúng tôi sẽ cố gắng làm mọi việc khác đi.
Lời giải. Hãy giới thiệu những ẩn số mới
$$\begin{cases} u = \sqrt{x+2} \geq 0, \\ v = \sqrt{x-a+2} \geq 0. \end{cases}$$
Các ẩn số $u$ và $v$ có liên hệ bằng nhau
$$u^2 - v^2 = a,$$
và phương trình ban đầu có dạng
$$u - v = 1.$$
Như vậy từ phương trình ta đi đến hệ
$$\begin{cases} u - v = 1, \\ u^2 - v^2 = a, \end{cases}$$
được giải quyết dễ dàng:
$$\begin{cases} u - v = 1, \\ (u - v)(u + v) = a \iff \begin{cases} u - v = 1, \\ u + v = a \iff \end{cases} \\ u = (a + 1)/2, \\ v = (a - 1)/2.$$
Vì thế,
$$\begin{cases} \sqrt{x+2} = (a+1)/2 \geq 0, \\ \sqrt{x-a+2} = (a-1)/2 \geq 0, \end{cases}$$
chúng ta lấy nó từ đâu

Đáp số: $x = \frac{(a+1)^2}{4} - 2$ tại $a \geq 1,$ tại $a < 1$ lời giải không.
Bài toán 2. Giải phương trình
$$\sqrt[3]{2-x} + \sqrt{x-1} - 1 = 0.$$
Lời giải. Hãy giới thiệu những điều chưa biết
$$u = \sqrt[3]{2-x}, v = \sqrt{x-1} \geq 0.$$
Sau đó
$$\begin{cases} u^3 + v^2 = 1, \\ u + v = 1. \end{cases}$$

Kể từ đây,
$$u^3 + u^2 - 2u = 0,$$
từ đâu $u \in \{0, 1, -2\}$, vậy hệ (1) có 3 lời giải: (0; 1), (1; 0), (-2; 3), sau đó nó được tìm thấy.
Đáp số: 2; 1; 10.
Tất nhiên, để tìm giá trị của $x$ không cần phải xem xét cả hai sự tương ứng của hệ (6) ở giai đoạn cuối. Nhưng trong trường hợp này, bạn sẽ phải kiểm tra để hoàn thành lời giải.
Khi chuyển từ một phương trình sang một hệ thống, nói chung, có thể nảy sinh một số ẩn số, một hệ thống phức tạp xuất hiện, không rõ thế nào là ẩn số mới, v.v.
Bài toán 3. Giải phương trình
$$\sqrt[4]{97-x} + \sqrt[4]{x-15} = 4.$$
Lời giải. Bằng cách nhập ẩn số
$$u = \sqrt[4]{97-x} \geq 0, v = \sqrt[4]{x-15} \geq 0,$$
chúng tôi đến với hệ thống
$$\begin{cases} u^4 + v^4 = 82, \\ u + v = 4. \end{cases}$$

Kế tiếp,
$$u^4 + v^4 = ((u + v)^2 - 2uv)^2 - 2u^2v^2,$$
và vì $u + v = 4$, thì
$$u^4 + v^4 = (16 - 2uv)^2 - 2u^2v^2.$$
Chúng ta nhận được phương trình bậc hai cho $t = uv$:
$$(16 - t)^2 - 2t^2 = 82.$$
Do đó $t = 29$ hoặc $t = 3$. Có tính đến (2) chúng tôi có được

⟦folio 64⟧

---
running_head:
folio:
---

$$y = x^2 + 1,$$
hãy rút gọn phương trình về dạng
$$\frac{y(y + 2x) + x^2}{y^2 - x^2} = \frac{y}{x}.$$

Sau khi thay thế $y/x = t$ ta được phương trình
$$\frac{t(t + 2) + 1}{t^2 - 1} = t,$$ hoặc $t + 1 = t(t - 1),$
có rễ $t_{1,2} = 1 \pm \sqrt{2}$.
Vì vậy, $\frac{x^2 + 1}{x} = 1 \pm \sqrt{2},$
tức là $x^2 - (1 \pm \sqrt{2})x + 1 = 0$, từ đâu chúng tôi nhận được

Đáp số: $(1 + \sqrt{2} \pm \sqrt{2\sqrt{2} - 1})/2.$

Việc đưa ra các ẩn số bổ sung đặc biệt hữu ích cho các hệ phương trình lời giải.

Bài toán 8. Giải hệ
$$\begin{cases}
2x^2 + xy = 1, \\
\frac{9x^2}{2(1-x)^4} = 1 + \frac{3xy}{2(1-x)^2}.
\end{cases}$$

Lời giải. Trong phương trình thứ hai của hệ, thật thuận tiện để đặt
$$z = \frac{3x}{(1-x)^2}.$$

Sau đó
$$z^2 = 2 + zy.$$ (4)

Bây giờ, chia phương trình đầu tiên cho $x^2$, chúng ta rút gọn nó về dạng
$$\left(\frac{1}{x}\right)^2 = 2 + \left(\frac{1}{x}\right)y$$ (5)

$(x \neq 0)$. Điều gì xảy ra tiếp theo: trừ phương trình (5) khỏi phương trình (4), chúng ta thu được
$$\left(z - \frac{1}{x}\right)\left(z + \frac{1}{x}\right) = \left(z - \frac{1}{x}\right)y,$$
từ đâu $z = 1/x$ hoặc $z + 1/x = y$. Trong trường hợp đầu tiên chúng tôi nhận được
$$\frac{3x}{(1-x)^2} = \frac{1}{x},$$ tức là $x = \frac{1}{2}(-1 \pm \sqrt{3}),$
$y = 2.$

Trong trường hợp thứ hai, $xz + 1 = xy$, cùng với phương trình đầu tiên của hệ ban đầu cho ra $2x^2 + xz + 1 = 1$. Và vì $x \neq 0$, nên $2x + z = 0$, tức là

$$\frac{3x}{(1-x)^2} + 2x = 0.$$

Phương trình này không có nghiệm nào khác 0.
Đáp số: $((-1 \pm \sqrt{3})/2; 2).$

Để kết luận, chúng tôi khuyên bạn nên tự mình giải các phương trình sau.

Bài tập
1. Giải phương trình
a) (MIEM, 1979) $\sqrt{x + 1} - \sqrt{a - x} = 1$;
b) $2\sqrt{3x - 1} + \sqrt{27 - 14x} = 1$;
r) $x = \sqrt{a - x} \sqrt{b - x} + \sqrt{b - x} \sqrt{c - x} + \sqrt{c - x} \sqrt{a - x}$;
d) $7\sqrt{4x^2 + 5x - 1} - 14\sqrt{x^2 - 3x + 3} = 17x - 13$;
e) $(x^2 + 3x - 4)^3 + (2x^2 - 5x + 3)^3 = (3x^2 - 2x - 1)^3$;
j) (LSU, vật lý, 1974)

$$\frac{x^2}{x - 1} + \sqrt{x - 1} + \frac{\sqrt{x - 1}}{x^2} = \frac{x - 1}{x^2} + \frac{1}{\sqrt{x - 1}} + \frac{x^2}{\sqrt{x - 1}};$$

3) (Tháng 5 năm 1973) $\sqrt{3 - x} - \sqrt{\frac{1 - x}{2 - x}} = 1$;
i) (MIREA, 1986) $\sqrt{7x^2 + 8x + 10} - \sqrt{7x^2 - 8x + 10} = 2x$;
j) $(x^2 + 2x - 5)^2 + 2(x^2 + 2x - 5) = x + 5$;
l) $\sqrt{a - \sqrt{a + x}} = x$;
m) $\frac{(x - 1)^2x}{(x^2 - x + 1)^2} = \frac{2}{9}$;
n) $\frac{x^2 - 10x + 15}{x^2 - 6x + 15} = \frac{3x}{x^2 - 8x + 15}$;
o) $\frac{1}{x} + \frac{1}{\sqrt{1 - x^2}} = \frac{35}{12}$;
n) $\frac{x^4 + 4}{x^2 + 2} = 5x$;
p) $x^2 + \frac{25x^2}{(x + 5)^2} = 11.$

2. Giải bất đẳng thức
a) $\sqrt{x - \frac{1}{x}} - \sqrt{1 - \frac{1}{x}} > \frac{x - 1}{x}$;
b) $\sqrt{12 - \frac{12}{x^2}} + \sqrt{x^2 - \frac{12}{x^2}} < x^2.$

3. Giải hệ phương trình
a) (NSU, địa chất. Khoa, 1976)

$$\begin{cases}
\sqrt{-1 - x} - \sqrt{2y - x} = 1, \\
\sqrt{1 - 2y} + \sqrt{2y - x} = 4;
\end{cases}$$
