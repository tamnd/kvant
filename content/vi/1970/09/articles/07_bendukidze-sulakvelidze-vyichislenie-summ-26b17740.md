---
id: 1970-9-bendukidze-sulakvelidze-vyichislenie-summ-26b17740
issue: kvant_1970_9
year: 1970
number: "9"
title: Tính các tổng
authors:
  - Бендукидзе А. Д.
  - Сулаквелидзе А. К.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 39
page_last: 41
page_labels: 37-39
tag: 77RH
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 2ab98e9039b2054ac3e94441c7377a65d9348d4efb7d09a1c54a84e8c23f4d9e
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1970/09/articles/07_bendukidze-sulakvelidze-vyichislenie-summ-26b17740.md
source_content_sha256: 73646112a227d2669d3ffd84430f964c665cd991ebf70b40ebe04d5deec31260
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦folio 37⟧

TÍNH TỔNG

Tính tổng là một trong những vấn đề quan trọng và thú vị nhất của toán học. Có nhiều phương pháp tính tổng khác nhau. Bài viết trình bày hai trong số đó.

1. Trong toán học và nhiều ứng dụng của nó, người ta dùng một dấu hiệu đặc biệt để viết gọn tổng. Đó là Σ — chữ cái “sigma” trong bảng chữ cái Hy Lạp. Cách viết tổng bằng dấu Σ thường rất tiện lợi. Hãy làm quen với dấu này.

Giả sử cho một tổng dạng
$$a_1 + a_2 + \dots + a_n.$$
Mọi số hạng của tổng này đều được ký hiệu bằng một chữ cái, để phân biệt dùng các chỉ số. Tổng đã cho có thể viết gọn như sau:

$$\sum_{k=1}^{n} a_k.$$
Đọc là: “sigma $a_k$, $k$ thay đổi từ 1 đến $n$”. Để viết như vậy, lấy một số hạng “điển hình” của tổng, trong trường hợp của ta là $a_k^*$, viết dấu Σ trước nó và chỉ ra các giới hạn thay đổi của $k$. Chẳng hạn, cách viết

$$\sum_{k=1}^{10} k$$
có nghĩa là tổng
$$1 + 2 + 3 + 4 + 5 + 6 + 7 + 8 + 9 + 10,$$
*) $a_k$ được gọi là số hạng tổng quát của tổng.

còn cách viết
$$\sum_{k=1}^{n} \frac{1}{k(k+1)}$$

— có nghĩa là tổng
$$\frac{1}{1 \cdot 2} + \frac{1}{2 \cdot 3} + \dots + \frac{1}{(n-1)n} + \frac{1}{n(n+1)}$$.

Không khó để kiểm tra các tính chất sau của dấu Σ:
$$\sum_{k=1}^{n} 1 = n, \quad \sum_{k=1}^{n} ca_k = c \sum_{k=1}^{n} a_k,$$
$$\sum_{k=1}^{n} (a_k + b_k) = \sum_{k=1}^{n} a_k + \sum_{k=1}^{n} b_k.$$

Chẳng hạn, hãy kiểm tra tính chất thứ hai.

Theo định nghĩa
$$\sum_{k=1}^{n} ca_k = ca_1 + ca_2 + \dots + ca_n,$$

vì vậy, theo tính chất đã biết của tổng, ta có:
$$\sum_{k=1}^{n} ca_k = c(a_1 + a_2 + \dots + a_n).$$

Nhưng biểu thức trong ngoặc không gì khác chính là
$$\sum_{k=1}^{n} a_k$$
và do đó
$$\sum_{k=1}^{n} ca_k = c \sum_{k=1}^{n} a_k.$$

⟦folio 38⟧

Hai tính chất còn lại được kiểm tra tương tự.

2. Xét vấn đề tính tổng dạng

$$\sum_{k=1}^{n} f(k) = f(1) + f(2) + \dots + f(n),$$

trong đó $f$ là một hàm đã biết của đối số nguyên, được xác định trên đoạn $[1, n]$ của dãy số tự nhiên.

Tổng này dễ tính nếu tìm được một hàm $F$, được xác định trên đoạn $[1, n+1]$ của dãy số tự nhiên, sao cho với mọi $k, 1 \leq k \leq n$, đẳng thức sau đúng:

$$f(k) = F(k+1) - F(k).$$

Thật vậy, lần lượt cho $k = 1, 2, \dots, n-1, n$ trong đẳng thức này, ta được:

$$f(1) = F(2) - F(1),$$
$$f(2) = F(3) - F(2),$$
$$f(3) = F(4) - F(3),$$

$$f(n-1) = F(n) - F(n-1),$$
$$f(n) = F(n+1) - F(n).$$

Cộng các đẳng thức này, ta đi đến công thức sau:

$$\sum_{k=1}^{n} f(k) = F(n+1) - F(1).$$

Như vậy, nếu tìm được hàm $F$, thì tổng (1) được tính một cách sơ cấp.

Minh họa công thức (3) bằng một cấp số nhân.

Trong hình 1, ta cần tìm tổng (1), được ký hiệu đơn giản là $\Sigma$, như độ dài của đoạn thẳng đứng. Mỗi số hạng dạng $f(k)$ tương ứng với độ dài của đoạn màu đỏ, bằng hiệu độ dài của các đoạn màu xanh lá $F(k+1)$ và $F(k)$. Rõ ràng, tổng độ dài của tất cả các đoạn màu đỏ bằng hiệu độ dài của đoạn thứ nhất và đoạn cuối cùng trong các đoạn màu xanh lá.

Ví dụ 1. Tính tổng

$$\frac{1}{1.2} + \frac{1}{2.3} + \frac{1}{3.4} + \dots + \frac{1}{n(n+1)},$$

tức là

$$\sum_{k=1}^{n} \frac{1}{k(k+1)}.$$

Ở đây

$$f(k) = \frac{1}{k(k+1)},$$

và, như dễ kiểm tra, nó có thể được biểu diễn dưới dạng hiệu sau:

$$f(k) = \frac{1}{k} - \frac{1}{k+1}.$$

Vì vậy, nếu đặt

$$F(k) = -\frac{1}{k},$$

thì công thức (2) sẽ đúng với mọi $k$ tự nhiên:

$$f(k) = F(k+1) - F(k).$$

Áp dụng công thức (3), ta dễ dàng thu được

$$\sum_{k=1}^{n} \frac{1}{k(k+1)} = 1 - \frac{1}{n+1} = \frac{n}{n+1}.$$

Ví dụ 2. Tìm tổng các số hạng của cấp số nhân sau:

$$q, q^2, q^3, \dots, q^n \quad (q \neq 1).$$

Ở đây $f(k) = q^k$, và, sử dụng đẳng thức $q^{k+1} - q^k = q^k(q-1)$, có thể viết

$$q^k = \frac{q^{k+1}}{q-1} - \frac{q^k}{q-1}.$$

Từ đó thấy rằng có thể đặt

$$F(k) = \frac{q^k}{q-1},$$

và do đó,

$$\sum_{k=1}^{n} q^k = \frac{q^{n+1}}{q-1} - \frac{q}{q-1} = \frac{q^{n+1}-q}{q-1}.$$

Ta thu được công thức quen thuộc.

⟦folio 39⟧

Ví dụ 3. Tính tổng
$$\sum_{k=1}^{n} \sin kx (x \neq 2\pi n).$$
Không khó để kiểm tra rằng
$$\sin kx = \frac{\cos(k-0,5)x - \cos(k+0,5)x}{2\sin 0,5x},$$
tức là
$$\sin kx = F(k+1) - F(k),$$
trong đó
$$F(k) = -\frac{\cos(k-0,5)x}{2\sin 0,5x}.$$
Bây giờ, dựa vào công thức (3), sau những biến đổi đơn giản ta được
$$\sum_{k=1}^{n} \sin kx = \frac{\sin 0,5(n+1)x \sin 0,5nx}{2\sin 0,5x}.$$
Bạn đọc đã tự thấy rằng công thức (3) cho một cách hiệu quả để tính tổng (1). Điều chủ yếu là tìm hàm $F$. Đáng tiếc là điều này thường không phải là một bài toán dễ, đôi khi thậm chí không thể giải được.
3. Bây giờ giả sử cho hai dãy số hữu hạn
$$u_1, u_2, \dots, u_n,$$
và
$$v_1, v_2, \dots, v_n$$
và cần tính tổng
$$\sum_{k=1}^{n} u_k v_k.$$
Ở đây thường hữu ích một phép biến đổi do nhà toán học Na Uy Abel nêu ra. Cụ thể, giả sử $V_k$ là tổng $k$ số hạng đầu của dãy (4), tức là
$$V_k = \sum_{i=1}^{k} v_i = v_1 + v_2 + \dots + v_k.$$
Rõ ràng $v_1 = V_1$; còn nếu $k > 1$, thì
$$v_h = V_h - V_{h-1}.$$

Do đó
$$\sum_{k=1}^{n} u_k v_k = u_1 v_1 + u_2 v_2 + \dots + u_n v_n = u_1 V_1 + u_2 (V_2 - V_1) + \dots + u_n (V_n - V_{n-1})$$
Khai triển các ngoặc và nhóm các số hạng từng đôi, ta được
$$\sum_{k=1}^{n} u_k v_k = (u_1 - u_2) V_1 + (u_2 - u_3) V_2 + \dots + (u_{n-1} - u_n) V_{n-1} + u_n V_n$$
hay cuối cùng:
$$\sum_{k=1}^{n} u_k v_k = u_n V_n - \sum_{k=1}^{n-1} (u_{k+1} - u_k) V_k.$$ (5)
Diễn giải hình học của phương pháp này được đưa ra ở hình 2. Mỗi số hạng dạng $u_k v_k$ tương ứng với diện tích của một hình chữ nhật (màu xanh lá). Các số hạng dạng $(u_{k+1} - u_k) V_n$ tương ứng với diện tích của các hình chữ nhật màu đỏ. Biểu thức $u_n V_n$ là diện tích của toàn bộ hình chữ nhật. Sau đó công thức (5) trở nên rất rõ ràng.

Ví dụ 4. Tính tổng
$$1^2 + 2^2 + \dots + n^2.$$
Ký hiệu tổng cần tìm là $S$ và viết nó bằng dấu $\Sigma$:
$$S = \sum_{k=1}^{n} k^2.$$
