---
id: 1972-3-kleyman-neuzheli-otkryitie-ce84e03d
issue: kvant_1972_3
year: 1972
number: "3"
title: Có thực sự là một khám phá?
authors:
  - Клейман Я. М.
rubric: smes
page_first: 35
page_last: 35
page_labels: "33"
tag: GN8W
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 184261bf11e614d8ca2df35ee04190f2ff8b2f5bd37488f122991a6ca2e2a99b
prompt_sha256: draft-1
translated_from: content/ru/1972/03/articles/10_kleyman-neuzheli-otkryitie-ce84e03d.md
source_content_sha256: ae1c7a9cd6e23b55c08ead97d04bf7eee6457a4448009dcfe90de5e360e6c4dc
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 33⟧

Sau khi xem xét các phương trình số gần đúng lời giải của lũy thừa tính toán bằng các phương pháp phép thử, hợp âm, tiếp tuyến và tích phân trong bài học tự chọn cuối cùng về chủ đề: “Phương trình gần đúng lời giải”, học sinh cố gắng khám phá phương pháp phương trình số lời giải sau đây.

Cho phương trình $f(x) = 0$ có một nghiệm duy nhất $x_0$ trên đoạn $a \leq x \leq b$ và để hàm $f(x)$ liên tục trên đoạn này và lấy các giá trị của các dấu khác nhau ở hai đầu của nó. Hãy vẽ các dây cung $AC$ và $BC$ cho đồ thị của hàm số đã cho trên đoạn $[a, b]$.

Ta viết phương trình đường thẳng đi qua các điểm $A[b; f(b)]$ và $C(x_0; 0)$:

$$\frac{f(b) - y}{f(b) - 0} = \frac{b - x}{b - x_0},$$

từ đó nó nằm

$$y = f(b) - \frac{b - x}{b - x_0} f(b).$$

Tương tự, ta viết phương trình đường thẳng đi qua các điểm $B[a; f(a)]$ và $C(x_0; 0)$:

$$\frac{f(a) - y}{f(a) - 0} = \frac{a - x}{a - x_0},$$

![Graph of the function $y = f(b) - \frac{b - x}{b - x_0} f(b)$](image)

Ở đâu

$$y = f(a) - \frac{a - x}{a - x_0} f(a).$$

Để tìm tọa độ giao điểm của các đường thẳng này ta giải hệ

$$\begin{cases}
y = f(b) - \frac{b - x}{b - x_0} f(b), \\
y = f(a) - \frac{a - x}{a - x_0} f(a).
\end{cases}$$

Viết ra toàn bộ sự việc

$$f(b) - \frac{b - x}{b - x_0} f(b) = f(a) - \frac{a - x}{a - x_0} f(a),$$

$$f(b) \left[ 1 - \frac{b - x}{b - x_0} \right] = f(a) \left[ 1 - \frac{a - x}{a - x_0} \right],$$

$$f(b) \cdot \frac{x - x_0}{b - x_0} = f(a) \cdot \frac{x - x_0}{a - x_0},$$

$$\frac{f(b)}{f(a)} = \frac{b - x_0}{a - x_0},$$

chúng tôi tìm thấy

$$x_0 = \frac{bf(a) - af(b)}{f(a) - f(b)}.$$

Đã tìm được công thức nghiệm của phương trình này $f(x) = 0$! Rút kinh nghiệm từ kết quả bất ngờ đó với sự phấn khích và nhiệt tình vô cùng, họ thậm chí còn thốt lên: “Eureka!”

Nhưng sau vài phút, sự im lặng đáng báo động lại được khôi phục trong khán giả. Mọi người đều sửng sốt và mọi người đều hỏi: "Làm sao có thể như vậy?" Các nhà khoa học - nhà toán học nổi tiếng Abel và Evariste Galya đã đưa ra một chứng minh toàn diện rằng đối với tất cả các phương trình trên bậc bốn thì không thể soạn được công thức chính xác lời giải.

Sai lầm đã xảy ra ở đâu?

Y. M. Kleiman
