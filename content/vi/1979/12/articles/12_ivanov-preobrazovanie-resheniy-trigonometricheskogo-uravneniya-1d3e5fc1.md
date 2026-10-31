---
id: 1979-12-ivanov-preobrazovanie-resheniy-trigonometricheskogo-uravneniya-1d3e5fc1
issue: kvant_1979_12
year: 1979
number: "12"
title: Biến đổi phương trình lượng giác lời giải
authors:
  - Иванов В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 36
page_last: 37
page_labels: 34-35
tag: 5Y6H
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 1230c7a843fdd50f61e2cd39a4d0c78c9e83ffee3135f9e0ed1ff878d49c2774
prompt_sha256: draft-1
translated_from: content/ru/1979/12/articles/12_ivanov-preobrazovanie-resheniy-trigonometricheskogo-uravneniya-1d3e5fc1.md
source_content_sha256: 55b68c49d54f2a5e79033a4dc07be45f0fc5956fbdc53b3fb7e60801177fd508
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 34⟧

Biến đổi phương trình lượng giác lời giải

Rõ ràng, một số tự nhiên tùy ý $n$ có thể được biểu diễn dưới dạng $n=2t$ hoặc $n=2t+1$. Hơn nữa, bất kỳ số tự nhiên nào $n$ đều có thể được biểu diễn dưới dạng $n=3t$, $n=3t+1$ hoặc $n=3t+2$. Hơn nữa, tất cả các hệ số của số $n$ có thể được biểu diễn dưới dạng $n=4t$ hoặc $n=4t+1$ hoặc $n=4t+2$ hoặc $n=4t+3$. Nó. d. Chuỗi phát biểu này là cơ sở lý thuyết cho phép biến đổi đôi khi đi kèm với nghiệm của một phương trình lượng giác.

Ví dụ 1 (NSU, Cơ học và Toán học, 1974). Giải phương trình

$$\sqrt{\cos 2x - \sin 4x} = \sin x - \cos x.$$ (1)

Đường dẫn rõ ràng lời giải của phương trình (1) là bình phương cả hai vế của phương trình:

$$\cos 2x - \sin 4x = (\sin x - \cos x)^2.$$ (2)

Sau khi biến đổi x tương đương dễ dàng, chúng ta nhận được

$$\sin x (\sin x + \cos 3x) = 0.$$

Do đó, phương trình (2) có đáp số:

$$\begin{cases}
x_1 = \pi k & (k \in \mathbb{Z}), \\
x_2 = \frac{\pi}{4} + \pi l & (l \in \mathbb{Z}), \\
x_3 = -\frac{\pi}{8} + \frac{\pi}{2} m & (m \in \mathbb{Z}).
\end{cases}$$

Nhưng nói chung, phương trình (2) không tương đương với phương trình (1); nó chỉ là phần giới thiệu từ (1). Vì vậy cần phải tiến hành kiểm tra.

Chu kỳ chung ngắn nhất của các hàm $2x$, $\sin 4x$, $\sin x$ và $\cos x$ là $2\pi$. Điều này có nghĩa là nếu số $a$ là nghiệm của phương trình (1) thì tất cả các số $a+2\pi t$ ($t \in \mathbb{Z}$) đều là nghiệm của phương trình đó. Vì vậy, chúng ta viết lời giải (3) “với dấu chấm $2\pi$”.

Thay thế biến $k$ trong $x_1$ bằng $k=2t$ và $k=2t+1$, ta được

$$\begin{cases}
x_{11} = 2\pi t, \\
x_{12} = \pi + 2\pi t.
\end{cases}$$

Tương tự, từ $x_2$ ta thu được

$$\begin{cases}
x_{21} = \frac{\pi}{4} + 2\pi t, \\
x_{22} = \frac{5}{4} \pi + 2\pi t.
\end{cases}$$

Thay thế biến $m$ trong $x_3$ bằng $m=4t$, $m=4t+1$, $m=4t+2$ và $m=4t+3$, ta được

$$\begin{cases}
x_{31} = -\frac{\pi}{8} + 2\pi t, \\
x_{32} = \frac{3}{8} \pi + 2\pi t, \\
x_{33} = \frac{7}{8} \pi + 2\pi t, \\
x_{34} = \frac{11}{8} \pi + 2\pi t.
\end{cases}$$

Từ ($3_1$), ($3_2$), ($3_3$) rõ ràng, theo quan điểm trên, chỉ cần kiểm tra các số 0, $\pi$, $\frac{\pi}{4}$, $\frac{5}{4}\pi$, $-\frac{\pi}{8}$, $\frac{3}{8}\pi$, $\frac{7}{8}\pi$, $\frac{11}{8}\pi$. Bạn chỉ cần thay thế 8 số này thành (1). Tuy nhiên, sẽ đơn giản hơn khi nói rằng phương trình (1) tương đương với một “hệ hỗn hợp”.

Hình 1.

⟦folio 35⟧

$$\begin{cases} \cos 2x - \sin 4x = (\sin x - \cos x)^2, \\ \sin x - \cos x \geq 0. \end{cases}$$

Vì vậy, chỉ cần xem (Hình 1) số nào trong số các số được viết thỏa mãn bất đẳng thức $\sin x \geq \cos x$ là đủ. Bất đẳng thức này được “chịu đựng” bởi $\pi, \frac{\pi}{4}, \frac{5}{4}\pi, \frac{3}{8}\pi$ và $\frac{7}{8}\pi$.

Điều này có nghĩa là đáp số của phương trình (1) bao gồm $x_{12}, x_{21}, x_{22}, x_{32}$ và $x_{33}$. Nếu muốn, $x_{21}$ và $x_{22}$ có thể được kết hợp "ngược".

Ví dụ 2: Giải phương trình

$$\sin 7x + \cos 2x = -2. \tag{4}$$

Vì $\min \sin 7x = \min \cos 2x = -1$ nên phương trình (4) tương đương với hệ

$$\begin{cases} \sin 7x = -1, \\ \cos 2x = -1. \end{cases}$$

Lời giải phương trình đầu tiên của hệ thống

$$x_1 = \frac{3}{14}\pi + \frac{2\pi}{7}k (k \in \mathbb{Z}), \tag{5}$$

lời giải của phương trình thứ hai

$$x_2 = \frac{\pi}{2} + \pi l (l \in \mathbb{Z}). \tag{6}$$

Để tìm giao của các tập hợp (5), (6), ta viết chúng “với chu kỳ 2n”. Thay biến $k$ trong (5) bằng $7t, 7t+1, 7t+2, 7t+3, 7t+4, 7t+5$ và $7t+6$, ta thu được

$$\begin{cases} x_{11} = \frac{3}{14}\pi + 2\pi t, \\ x_{12} = \frac{\pi}{2} + 2\pi t, \\ x_{13} = \frac{11}{14}\pi + 2\pi t, \\ x_{14} = \frac{15}{14}\pi + 2\pi t, \\ x_{15} = \frac{19}{14}\pi + 2\pi t, \\ x_{16} = \frac{23}{14}\pi + 2\pi t, \\ x_{17} = \frac{27}{14}\pi + 2\pi t. \end{cases} \tag{7}$$

Thay biến $l$ trong (6) bằng $l=2t$ và $l=2t+1$, ta thu được

$$\begin{cases} x_{21} = \frac{\pi}{2} + 2\pi t, \\ x_{22} = \frac{3}{2}\pi + 2\pi t. \end{cases} \tag{8}$$

Từ việc so sánh (7) và (8) đáp số có thể thấy:

$$x_{12}.$$

Ví dụ 3 (MSU, Khoa Hóa học, 1977). Tìm phương trình lời giải

$$2 - \sqrt{3}\cos 2x + \sin 2x = 4\cos^2 3x, \tag{9}$$

thỏa mãn bất đẳng thức

$$\cos \left(2x - \frac{\pi}{4}\right) > 0.$$

Phương trình (9) tương đương với phương trình

$$1 - \cos \left(2x + \frac{\pi}{6}\right) = 1 + \cos 6x.$$

Đã đặt anh ấy đáp số:

$$\begin{cases} x_1 = \frac{5}{48}\pi + \frac{\pi}{4}k (k \in \mathbb{Z}), \\ x_2 = \frac{7}{24}\pi + \frac{\pi}{2}l (l \in \mathbb{Z}). \end{cases}$$

Vì vậy, $2x - \frac{\pi}{4}$ có dấu chấm $2\pi$, chúng ta viết đáp số này “với dấu chấm $l$”. Thay thế biến $k$ trong $x_1$ bằng $k = 4t, k = 4t+1, k = 4t+2$ và $k = 4t+3$, ta được

$$\begin{cases} x_{11} = \frac{5}{48}\pi + \pi t, \\ x_{12} = \frac{17}{48}\pi + \pi t, \\ x_{13} = \frac{29}{48}\pi + \pi t, \\ x_{14} = \frac{41}{48}\pi + \pi t. \end{cases}$$

Từ đây

$$\begin{cases} 2x_{11} - \frac{\pi}{4} = -\frac{\pi}{24} + 2\pi t, \\ 2x_{12} - \frac{\pi}{4} = \frac{11}{24}\pi + 2\pi t, \\ 2x_{13} - \frac{\pi}{4} = \frac{23}{24}\pi + 2\pi t, \\ 2x_{14} - \frac{\pi}{4} = \frac{35}{24}\pi + 2\pi t. \end{cases}$$

Có thể thấy, bất đẳng thức cần tìm thỏa mãn bất đẳng thức $x_{11}$ và $x_{12}$.

Tương tự, thay biến $l$ trong $x_2$ bằng $l=2t$ và $l=2t+1$, ta thu được
