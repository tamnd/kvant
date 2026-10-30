---
id: 1970-8-berkolayko-katok-ob-odnom-induktivnom-metode-dokazatelstva-neravenstv-c5f6fef3
issue: kvant_1970_8
year: 1970
number: "8"
title: Về một phương pháp quy nạp chứng minh bất đẳng thức
authors:
  - Берколайко С. Т.
  - Каток С. Б.
rubric: raznoe
page_first: 35
page_last: 38
page_labels: 33, 34, 36
tag: 77TL
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 9b53d6f8a943bdcc251419397d838b3042b8974ec0cedef6e0afa44ba9fce61d
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1970/08/articles/08_berkolayko-katok-ob-odnom-induktivnom-metode-dokazatelstva-neravenstv-c5f6fef3.md
source_content_sha256: 6f4d9a2f9d09e38d95b6d58331bf71718fc154ce47859013578e568aa504621a
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-30
---

⟦folio 33⟧

Về một phương pháp quy nạp chứng minh bất đẳng thức

S. T. Bercolaiko,
S. B. Katok

Định lý về trung bình cộng và trung bình nhân, khẳng định rằng với mọi $x_1, x_2, \dots, x_n$ dương đều đúng bất đẳng thức

$$\frac{1}{n} (x_1 + x_2 + \dots + x_n) \geq \sqrt{x_1 x_2 \dots x_n},$$

thuộc vào số những sự kiện toán học mà các chứng minh của chúng ít được biết đến hơn các phát biểu. (Những ví dụ khác cùng loại: trong số học — sự phân tích duy nhất một số thành các thừa số nguyên tố, trong hình học — định lý nói rằng các đường cao của một tam giác cắt nhau tại một điểm.) Trong khi đó có rất nhiều cách khác nhau để chứng minh bất đẳng thức đáng chú ý này, kể cả các cách sơ cấp (chẳng hạn, trong [1] (lời giải bài toán 268) đưa ra 3 chứng minh sơ cấp, còn ở đầu [5] đề xuất 12 chứng minh khác nhau). Trong bài ghi chú này đưa ra thêm một chứng minh ngắn bằng quy nạp, cũng áp dụng được cho các bất đẳng thức dương khác.

Ta phải chứng minh rằng

$$x_1 + \dots + x_n \geq n (x_1 \dots x_n)^{\frac{1}{n}}$$

(1)

với mọi số nguyên $n \geq 2$ và các $x_1, \dots, x_n$ dương.

Với $n=2$ bất đẳng thức này có dạng:

$$x_1 + x_2 \geq 2 (x_1 x_2)^{\frac{1}{2}}$$

(2)

và suy ra ngay từ bất đẳng thức hiển nhiên

$$(x_1^{\frac{1}{2}} - x_2^{\frac{1}{2}})^2 \geq 0.$$

Giả sử với $n=k$ bất đẳng thức (1) đúng, và chứng minh nó với $n=k+1$.

Để làm điều đó, xét biểu thức sau:

$$x_1 + x_2 + \dots + x_k + x_{k+1} + (k-1) (x_1 x_2 \dots x_{k+1})^{\frac{1}{k+1}}.$$

Chia tổng này thành hai tổng, mỗi tổng có $k$ số hạng, và đánh giá mỗi tổng bằng cách áp dụng bất đẳng thức (1) với $n=k$:

$$x_1 + x_2 + \dots + x_k \geq k (x_1 \dots x_k)^{\frac{1}{k}},$$

$$x_{k+1} + (k-1) (x_1 \dots x_{k+1})^{\frac{1}{k+1}} \geq k (x_{k+1} x_1^{\frac{k-1}{k+1}} \dots x_{k+1}^{\frac{k-1}{k+1}})^{\frac{1}{k}}.$$

Ta xem $(k-1) (x_1 x_2 \dots x_{k+1})^{\frac{1}{k+1}}$ là tổng của $(k-1)$ số hạng bằng nhau $(x_1 x_2 \dots x_{k+1})^{\frac{1}{k+1}}$.

⟦folio 34⟧

Áp dụng bất đẳng thức (2) cho vế phải của hai bất đẳng thức đã nêu ở trên, ta được

$$k \left(x_1 \dots x_k\right)^{\frac{1}{k}} + k \left(x_{k+1} x_1^{\frac{k-1}{k+1}} \dots x_k^{\frac{k-1}{k+1}}\right)^{\frac{1}{k}} \geq 2k \left(x_1 \dots x_{k+1}\right)^{\frac{1}{k+1}},$$

suy ra

$$x_1 + x_2 + \dots + x_{k+1} \geq (k + 1) \left(x_1 x_2 \dots x_{k+1}\right)^{\frac{1}{k+1}}.$$

Để “cảm nhận” phép biến đổi đại số này, hãy xem nó trông như thế nào khi $n=3$:

$$x_1 + x_2 + x_3 + \left(x_1 x_2 x_2\right)^{\frac{1}{3}} \geq 2 \left(x_1 x_2\right)^{\frac{1}{2}} + 2 \left(x_1^{\frac{1}{3}} x_2^{\frac{1}{3}} x_3^{\frac{4}{3}}\right)^{\frac{1}{2}} \geq$$

$$\geq 2 \cdot 2 \left[ \left(x_1 x_2\right)^{\frac{1}{2}} \left(x_1^{\frac{1}{3}} x_2^{\frac{1}{3}} x_3^{\frac{4}{3}}\right)^{\frac{1}{2}} \right]^{\frac{1}{2}} \geq 4 \left(x_1 x_2 x_3\right)^{\frac{1}{3}},$$

suy ra $x_1 + x_2 + x_3 \geq 3 \left(x_1 x_2 x_3\right)^{\frac{1}{3}}$. Ở đây bất đẳng thức (2) đã được sử dụng ba lần.

Gần như bằng cách đó có thể chứng minh bất đẳng thức sau:

a) $a_1^p + a_2^p + \dots + a_n^p \geq n \left(\frac{a_1 + a_2 + \dots + a_n}{n}\right)^p$,

trong đó $n$ và $p$ là các số tự nhiên, $a_i > 0$ ($i = 1, 2, \dots, n$);

b) $\sin \alpha_1 + \sin \alpha_2 + \dots + \sin \alpha_n \leq n \sin \left(\frac{\alpha_1 + \alpha_2 + \dots + \alpha_n}{n}\right)$,

trong đó $0 < \alpha_i < \frac{\pi}{2}$ ($i = 1, 2, \dots, n$);

b) $\sin \alpha_1 \sin \alpha_2 \dots \sin \alpha_n \leq \sin^n \left(\frac{\alpha_1 + \alpha_2 + \dots + \alpha_n}{n}\right)$,

trong đó $0 < \alpha_i < \frac{\pi}{2}$ ($i = 1, 2, \dots, n$);

г) $\frac{1}{a_1^p} + \frac{1}{a_2^p} + \dots + \frac{1}{a_n^p} \geq \frac{n}{\left(\frac{a_1 + a_2 + \dots + a_n}{n}\right)^p}$,

trong đó $p$ và $n$ là các số tự nhiên, $a_i > 0$ ($i = 1, 2, \dots, n$);

д) $(a_1 + b_1) (a_2 + b_2) \dots (a_n + b_n) \geq \left(\sqrt[n]{a_1 a_2 \dots a_n} + \sqrt[n]{b_1 b_2 \dots b_n}\right)^n$,

trong đó $a_i > 0, b_i > 0$ ($i = 1, 2, \dots, n$).

⟦folio 36⟧

Nói cách khác, chỉ cần chứng minh bất đẳng thức cần thiết với $n=2$.

Và nếu chứng minh được tính lồi lên của hàm số $\lg x$ (điều này quy về việc chứng minh bất đẳng thức (2)), thì từ định lý của chúng ta, như một trường hợp riêng, sẽ suy ra định lý về trung bình cộng và trung bình nhân:

$$\lg \left( \frac{x_1 + \ldots + x_n}{n} \right) \leq \frac{\lg x_1 + \ldots + \lg x_n}{n},$$

tức là

$$\lg \left( \frac{x_1 + \ldots + x_n}{n} \right) \leq \lg \left( x_1 \ldots x_n \right)^{\frac{1}{n}}, \quad \frac{1}{n} \left( x_1 + \ldots + x_n \right) \leq \left( x_1 \ldots x_n \right)^{\frac{1}{n}}.$$

Cuối cùng, chúng tôi đưa ra danh sách các sách có thể đọc những chứng minh khác của định lý về trung bình cộng và trung bình nhân.

[1] Đ. O. Shklyarsky, N. N. Chentsov, I. M. Yaglom, Các bài toán và định lý chọn lọc của toán học sơ cấp, phần I, M., “Nauka”, 1965.

Hãy chú ý đến chứng minh thứ nhất trong ba chứng minh được đưa ra trong cuốn sách này (“Quy nạp ngược”).

[2] Krechmar, Sách bài tập đại số. M., “Nauka”, 1968.

[3] E. Beckenbach và R. Bellman, Nhập môn các bất đẳng thức, M., “Mir”, 1965.

[4] G. G. Hardy, D. E. Littlewood, G. Pólya, Các bất đẳng thức, IL, 1948.

[5] E. Beckenbach và R. Bellman, Các bất đẳng thức, M., “Mir”, 1965.

Bài tập

1. Bất đẳng thức nào sẽ thu được nếu áp dụng định lý cho hàm số $y=x^2$? Hãy thử chứng minh trực tiếp bất đẳng thức này.

2. Suy ra từ định lý tổng quát các bất đẳng thức a)—đ). Cần chứng minh tính lồi của những hàm nào để làm điều đó?

3. Hãy nghĩ ra thêm vài ví dụ về các hàm lồi và viết bất đẳng thức thu được từ định lý 1 khi áp dụng cho các hàm này.

4. Hàm số $f$ được xác định trên đoạn $[a, b]$ và có hàm số ngược**) $g$. Chứng minh rằng nếu $f$ lồi lên trên thì $g$ lồi xuống dưới, và ngược lại.

5. Hàm số $f(x)$, được xác định trên đoạn $[a, b]$, lồi lên trên. Chứng minh rằng với mọi điểm $x_1, \ldots, x_n$ nằm trên đoạn $[a, b]$, và mọi số dương $a_1, \ldots, a_n$, bất đẳng thức sau đúng

$$\frac{a_1 f(x_1) + \ldots + a_n f(x_n)}{a_1 + \ldots + a_n} \leq f\left(\frac{(a_1 x_1 + \ldots + a_n x_n)}{a_1 + \ldots + a_n}\right).$$

(Lưu ý rằng bài toán này là sự tổng quát hóa của định lý đã được chứng minh trước đó, nhận được khi $a_1=a_2=\ldots=a_n=1$.)

Gợi ý. Để giải bài toán này có thể dùng cùng phương pháp mà chúng tôi đã dùng khi chứng minh định lý.

*) Có thể lấy lôgarit theo bất kỳ cơ số nào lớn hơn một.
**) Xem “Kvant”, số 1, tr. 22.
