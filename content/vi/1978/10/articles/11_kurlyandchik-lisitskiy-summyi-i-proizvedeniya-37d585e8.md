---
id: 1978-10-kurlyandchik-lisitskiy-summyi-i-proizvedeniya-37d585e8
issue: kvant_1978_10
year: 1978
number: "10"
title: Tổng và sản phẩm
authors:
  - Курляндчик Л. Д.
  - Лисицкий А. Д.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 33
page_last: 38
page_labels: 31, 32, 33, 34, 36
tag: YV0W
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 8b684ae4cacb32a177b192dba7f3821e5f57bf2b857149cd804e8b4766fb7239
prompt_sha256: draft-1
translated_from: content/ru/1978/10/articles/11_kurlyandchik-lisitskiy-summyi-i-proizvedeniya-37d585e8.md
source_content_sha256: d340c61fc65a50b5870a361dae1a98d95aa1c38e7d1ab91e7e431a9f05157d41
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 31⟧

Chúng tôi viết các công thức, theo quy luật, ngắn gọn, sử dụng ký hiệu

$$\sum_{k=1}^{n} a_k = a_1 + a_2 + \dots + a_n,$$

$$\prod_{k=1}^{n} b_k = b_1 \cdot b_2 \cdot \dots \cdot b_n,$$

$$n! = 1 \cdot 2 \cdot \dots \cdot n.$$

Chúng tôi khuyên những người chưa học cách sử dụng chúng nên mô tả các phép tính chi tiết hơn.

1. Dư cực trị

Tiêu đề này được giải thích bằng đẳng thức tiếp theo sau:

$$(a_2 - a_1) + (a_3 - a_2) +$$

$$+ (a_4 - a_3) + \dots + (a_n - a_{n-1}) +$$

$$+ (a_{n+1} - a_n) = a_{n+1} - a_1$$

(1)

hoặc

$$\sum_{k=1}^{n} (a_{k+1} - a_k) = a_{n+1} - a_1,$$

(1')

từ đó người ta có thể, bằng cách chọn chuỗi $(a_k)$ theo nhiều cách khác nhau, thu được nhiều đẳng thức không tốt lắm.

Ví dụ 1. Đặt $a_k = -\frac{1}{k}$, ta được $\sum_{k=1}^{n} \frac{1}{k(k+1)} = \frac{n}{n+1}$; Thật khó để tìm được một cuốn sách giải toán đại số nào không có ví dụ này.

Ví dụ 2. Đặt $a_k = k(k-1)d/2$. Vì $a_{k+1} - a_k = kd$, đẳng thức (1) có dạng $\sum_{k=1}^{n} kd = (n+1) \cdot n \cdot d/2$. Bằng cách thêm $a - d$ vào mỗi thành phần của tổng vết và $n(a - d)$ vào tổng ở bên phải, chúng ta thu được công thức nổi tiếng về tổng $n$ số hạng của một cấp số cộng: $a + (a + d) + \dots + (a + (n-1)d) = n(a - d) + (n+1)nd/2 = na + n(n-1)d/2$.

Bài tập 1. Lấy $a_k = (2k-1)^3/24$ vào (1) và nhận được công thức của $\sum_{k=1}^{n} k^2$.

⟦folio 32⟧

Ví dụ 3. Cho $m$ là một số tự nhiên. Hãy đặt $a_k = \frac{1}{(m+2)} \times (k-1)k(k+1) \dots (k+m)$. Sau đó $a_{k+1} - a_k = \frac{1}{m+2}k \cdot (k+1) \dots (k+m) + 1 + m) - \frac{1}{m+2}(k-1)k \dots (k+m) = k(k+1) \dots (k+m)$. Trong trường hợp này, đẳng thức (1) được viết như sau:
$$\sum_{k=1}^{n} k(k+1) \dots (k+m) = \frac{1}{m+2}n(n+1) \dots (n+m+1).$$
Đẳng thức (1) có thể được sử dụng theo cách khác. Chúng ta cần chứng minh rằng
$$\sum_{k=1}^{n} f(k) = g(n).$$
Hãy thử chứng minh đẳng thức
$$g(k) - g(k-1) = f(k).$$
Nếu thành công thì (2) cũng sẽ được chứng minh. Thật vậy, xét dãy phụ trợ
$$\left\{ \begin{array}{l} a_1 = 0, \\ a_{k+1} = g(k). \end{array} \right.$$
Đối với dãy này, đẳng thức (1) có dạng
$$\sum_{k=1}^{n} [g(k) - g(k-1)] = g(n),$$
mà theo quan điểm (3), tương đương với (2).
Ví dụ, chúng ta hãy chứng minh bằng cách này đẳng thức
$$\sum_{k=1}^{n} C_{l+k-1}^{l+1} = C_{l+n}^{l+1}.$$
Theo những gì đã nói, để làm được điều này, chỉ cần kiểm tra đẳng thức $C_{l+n}^{l+1} - C_{l+n-1}^{l+1} = C_{l+n-1}^{l+1}$ hoặc $C_{l+n-1}^{l+1} + C_{l+n-1}^{l+1} = C_{l+n}^{l+1}$, xuất phát từ điểm nổi tiếng $C_n^m + C_n^{m+1} = C_n^{m+1}$ (“Đại số và nguyên tắc phân tích 9”, đoạn 8). Trong Phần 3 chúng ta sẽ chứng minh điểm (4) theo một cách khác.
Tất cả những điều trên áp dụng cho công việc. Trước tiên chúng ta hãy viết phép tương tự nhân của đẳng thức (1):
$$\frac{a_2}{a_1} \cdot \frac{a_3}{a_2} \cdot \frac{a_4}{a_3} \dots \frac{a_n}{a_{n-1}} \cdot \frac{a_{n+1}}{a_n} = \frac{a_{n+1}}{a_1}$$
(*) $n!!$ biểu thị tích của các số tự nhiên từ 1 đến $n$ có cùng tính chẵn lẻ với $n$. Ví dụ: $8!! = 2 \cdot 4 \cdot 6 \cdot 8, 9!! = 1 \cdot 3 \cdot 5 \cdot 7 \cdot 9$.

⟦folio 33⟧

4. $$\sum_{k=1}^{n} k \cdot k! = (n+1)! - 1.$$
5. $$\prod_{k=1}^{n} k^k \cdot k! = (n!)^{n+1}.$$
6. $$a_1 + (a_1+1) a_2 + (a_1+1) (a_2+1) \times a + \ldots + (a_1+1) (a_2+1) \ldots (a_{n-1}+1) \times a_n = (a_1+1) (a_2+1) \ldots (a_n+1) - 1.$$
7. $$\sum_{k=1}^{n} \frac{1}{k(k+1) \ldots (k+m)} = \frac{1}{m} \left( \frac{1}{m!} - \frac{1}{(n+1)(n+2) \ldots (n+m)} \right).$$
8. $$\sum_{k=1}^{n} \frac{x^k \cdot k!}{(x+1)(2x+1) \ldots (kx+1)} = \frac{1}{x-1} \frac{x^{n+1}(n+1)!}{(x+1) \ldots (nx+1)} + \frac{x}{1-x}.$$
9. $$\sum_{k=0}^{n-1} \frac{p_0 \cdot p_1 \ldots p_k q_{k+1}}{(p_1+q_1) \ldots (p_{k+1}+q_{k+1})} = 1 - \frac{p_1 p_2 \ldots p_n}{(p_1+q_1) \ldots (p_n+q_n)}.$$
(Ở đây $(p_k)$ và $(q_k)$ là hai chuỗi và $p_0 = 1$.)
Thật không may, phương pháp chỉ thị chỉ phù hợp trong trường hợp trong tổng $$\sum_{k=1}^{n} b_k$$ các số hạng $b_k$ không phụ thuộc vào $n$. Trong phần tiếp theo, chúng ta sẽ chứng minh các đẳng thức trong đó các số hạng phụ thuộc vào $n$.

2. Phương pháp qua lại

Tên của phương pháp này (nhưng không phải bản thân phương pháp) là do tác giả sáng chế ra. Các nhà sử học toán học cho rằng chính nhờ sự giúp đỡ của ông mà cậu bé Gaussoudi đã đánh bại giáo viên ở trường của mình khi tìm nhanh tổng các số tự nhiên từ 1 đến 100. Chúng ta hãy chứng minh việc sử dụng phương pháp “qua lại” bằng các ví dụ.

Hãy chứng minh điều đó với số lẻ $n$
$$\sum_{k=0}^{n} (-1)^k \sqrt{C_n^k} = 0.$$
Hãy viết tổng $S_n$ theo hai cách
$$S_n = \sqrt{C_n^0} - \sqrt{C_n^1} + \sqrt{C_n^2} - \ldots + \sqrt{C_n^{n-1}} - \sqrt{C_n^n} \text{ (туда)},$$

$$S_n = -\sqrt{C_n^0} + \sqrt{C_n^1} + \ldots - \sqrt{C_n^n} + \sqrt{C_n^0} \text{ (назад)}$$

Trong tổng của chúng ta có dấu trừ trước $$\sqrt{C_n^n}$$ vì $n$ là số lẻ. Hãy thêm hai biểu thức kết quả:

$$2S_n = \left( \sqrt{C_n^0} - \sqrt{C_n^n} \right) + \left( -\sqrt{C_n^1} + \sqrt{C_n^{n-1}} \right) + \ldots + \left( -\sqrt{C_n^n} + \sqrt{C_n^0} \right).$$

Dễ dàng nhận thấy rằng mỗi dấu ngoặc đơn chứa số 0, vì $C_n^m = C_n^{n-m}$. Do đó $2S_n = 0$, do đó $S_n = 0$.

Một ví dụ khác:

$$\sum_{k=0}^{2n+1} \frac{(-1)^k}{C_{2n+1}^k} = 0.$$

Nó hoạt động theo cùng một cách:

$$S_n = \frac{1}{(C_{2n+1}^0)^2} - \frac{1}{(C_{2n+1}^1)^2} + \ldots - \frac{1}{(C_{2n+1}^n)^2} \text{ (туда)},$$

$$S_n = -\frac{1}{(C_{2n+1}^0)^2} + \frac{1}{(C_{2n+1}^1)^2} - \ldots + \frac{1}{(C_{2n+1}^n)^2} \text{ (назад)}$$

Cộng các biểu thức này và tính đến $C_{2n+1}^k = C_{2n+1}^{2n+1-k}$, chúng ta thu được $2S_n = 0$. Do đó $S_n = 0$.

Và đây là một ví dụ phức tạp hơn nhưng cũng thú vị hơn về cùng một chủ đề:

$$\sum_{k=0}^{n} \frac{(-1)^k}{C_n^k} = \frac{n+1}{n+2} (1 + (-1)^n).$$

Việc giải bài toán này cũng dễ dàng như hai phần trước mà không cần xóa. Chúng ta hãy biểu thị $$\sum_{k=0}^{n} \frac{(-1)^k}{C_n^k}$$ bằng $S_n$. Nếu $n$ lẻ, bạn có thể dễ dàng chứng minh rằng $S_n = 0$. Trường hợp chẵn $n$ sẽ rút gọn thành lẻ. Hãy theo dõi cẩn thận cách thực hiện việc này.

⟦folio 34⟧

Chúng ta hãy biểu thị $\sum_{k=0}^{n} \frac{(-1)^k (k+1)}{C_n^k}$ bằng $T_n$.

Hãy viết $T_n$ theo hai cách:

$$T_n = \frac{1}{C_n^0} - \frac{2}{C_n^1} + \dots + \frac{n+1}{C_n^n} \text{ (туда)},$$

$$T_n = \frac{n+1}{C_n^n} - \frac{n}{C_n^{n-1}} + \dots + \frac{1}{C_n^0} \text{ (назад)}.$$

Thêm, chúng tôi nhận được $2T_n = (n+2) \times \left( \frac{1}{C_n^0} - \frac{1}{C_n^1} + \dots + \frac{1}{C_n^n} \right) = (n+2) \times S_n$. Mặt khác, $T_n = \sum_{k=0}^{n} \frac{(-1)^k (k+1) k! (n-k)!}{n!} = (n+1) \sum_{k=0}^{n} \frac{(-1)^k}{C_n^{k+1}} = (n+1) (1 - S_{n+1})$.

Nhưng vì $S_{n+1} = 0$ ($n+1$ là số lẻ), $T_n = n+1$. Chúng tôi đã chứng minh điều đó $S_n = \frac{2}{n+2} T_n$. Vì vậy, $S_n = \frac{2(n+1)}{(n+2)}$.

Vẫn cần lưu ý rằng $\frac{n+1}{n+2} (1 + (-1)^n) = \left\{ \begin{array}{l} 0, n нечетно, \\ \frac{2(n+1)}{n+2}, n четно. \end{array} \right.$

Bằng chứng về sự bình đẳng

$$\sum_{k=0}^{n} \frac{1}{C_n^k} = \frac{n+1}{2^{n+1}} \sum_{k=1}^{n+1} \frac{2^k}{k}. \tag{9}$$

khó hơn tất cả những cái trước, nhưng nó cũng mang tính hướng dẫn.

Hãy giới thiệu ký hiệu sau:

$$\sum_{k=0}^{n} \frac{1}{C_n^k} = D_n; \quad \sum_{k=0}^{n} \frac{k+1}{C_n^k} = E_n;$$

$$\frac{n+1}{2^{n+1}} \sum_{k=1}^{n+1} \frac{2^k}{k} = F_n.$$

Đầu tiên, sử dụng phương pháp “quay lại”, chúng ta viết số tiền hai lần

$$E_n = \frac{1}{C_n^0} + \frac{2}{C_n^1} + \dots + \frac{n+1}{C_n^n} \text{ (туда)},$$

$$E_n = \frac{n+1}{C_n^n} + \frac{n}{C_n^{n-1}} + \dots + \frac{1}{C_n^0} \text{ (назад)}.$$

Hãy cộng các đẳng thức sau: $2E_n = (n+2) \times \sum_{k=0}^{n} \frac{1}{C_n^k} = (n+2) D_n$. Vì vậy, $D_n = \sum_{k=0}^{n} \frac{1}{C_n^k} = (n+2) E_n$. Bây giờ, tiếp tục tính toán tương tự như những gì chúng tôi đã thực hiện cho lời giải và bài toán trước đó, chúng tôi biểu thị $E_n$ đến $D_{n+1}$.

Cụ thể là $E_n = \sum_{k=0}^{n} \frac{k+1}{C_n^k} = (n+1) \times \sum_{k=0}^{n} \frac{1}{C_n^{k+1}} = (n+1) (D_{n+1} - 1)$ và chúng ta có thể biểu thị $D_{n+1}$ theo $D_n$:

$$D_{n+1} = \frac{2}{n+2} E_n = \frac{2}{n+2} (n+1) (D_{n+1} - 1),$$

Ở đâu

$$D_{n+1} = 1 + \frac{n+2}{2(n+1)} D_n.$$

Bây giờ, người sử dụng quy nạp toán học, hãy chứng minh rằng $D_n = F_n$ với mọi số nguyên $n \geqslant 0$. Dễ dàng nhận thấy rằng $D_0 = 1$ và $F_0 = 1$. Giả sử rằng $D_s = F_s$. Sau đó $D_{s+1} = 1 + \frac{s+2}{2(s+1)} D_s = 1 + \frac{s+2}{2(s+1)} F_s = 1 + \frac{s+2}{2(s+1)} \cdot \frac{s+1}{2^{s+1}} \sum_{k=1}^{s+1} \frac{2^k}{k} = 1 + \frac{s+2}{2^{s+1}} \sum_{k=1}^{s+1} \frac{2^k}{k} = F_{s+1}$.

Điều này có nghĩa là $D_n = F_n$ đối với tất cả các số nguyên $n \geqslant 0$. Vấn đề lời giải.

Sau khi chứng minh các đẳng thức (8) và (9), chúng ta đã giải được bài toán M470 («Kvant», 1977, số 10). Bình đẳng (9) cho phép chúng ta đề xuất một lời giải bài toán M434 mới («Kvant», 1977, Số 12).

Đặt $\sum_{k=1}^{n} \frac{2^k}{k} = \frac{p_n}{q_n}$, trong đó $p_n, q_n$ là nguyên tố cùng nhau. Chúng ta hãy biểu thị $v(n)$ lũy thừa cao nhất của 2 mà $p_n$ có thể chia hết. Hãy để chúng tôi chứng minh rằng $v(n) \geqslant \frac{n-3}{2}$.

Từ (9) $\sum_{k=0}^{n} \frac{1}{C_n^k} = \frac{n+1}{2^{n+1}} \frac{p_{n+1}}{q_{n+1}}$. Đó là lý do tại sao $\frac{p_{n+1}}{q_{n+1}} = \frac{2^{n+1}}{n+1} \sum_{k=0}^{n} \frac{1}{C_n^k}$ hoặc $\frac{p_n}{q_n} = \frac{2^{n}}{n} \sum_{k=0}^{n-1} \frac{1}{C_n^k}$. Do đó $\frac{p_n}{q_n} = \frac{2^{n}}{n}! \times ((n-1)! + 1! (n-2)! + 2! (n-3)! + \dots + (n-1)!)$. Trong $n!$ số 2 được bao gồm trong lũy ​​thừa $\left[ \frac{n}{2} \right] + \dots \leqslant$

⟦folio 36⟧

đa thức
$$f(x) = (1+x)^n (x+1)^n = \left( C_n^0 + C_n^1 x + C_n^2 x^2 + \dots + C_n^n x^n \right) \times \left( C_n^0 x^n + C_n^1 x^{n-1} + C_n^2 x^{n-2} + \dots + C_n^n \right).$$

Hệ số $x^n$ trong sản phẩm này rõ ràng bằng $\sum_{k=0}^{n} \left( C_n^k \right)^2$.

Mặt khác, $f(x) = (1+x)^2n$. Hệ số $x^n$ trong đó bằng $C_{2n}^n$. Theo định lý ta thu được $\sum_{k=0}^{n} \left( C_n^k \right)^2 = C_{2n}^n$.

Bây giờ chúng ta hãy tìm $\sum_{k=0}^{n} (-1)^k \left( C_n^k \right)^2$.

Đối với lời giải của bài toán trước đó, chúng tôi đã xem xét đa thức $f(x) = (1+x)^n (x+1)^n$. Ở đây, rõ ràng, cần phải lấy một đa thức dương, nhưng sao cho dấu của các hệ số trong đó là tuyến tính. Chúng ta hãy thử xét đa thức $g(x) = (1+x)^n (x-1)^n = \left( C_n^0 + C_n^1 x + \dots + C_n^n x^n \right) \left( C_n^0 x^n - C_n^1 x^{n-1} + \dots + (-1)^n C_n^n \right)$.

Hệ số $x^n$ trong sản phẩm này bằng $\sum_{k=0}^{n} (-1)^k \left( C_n^k \right)^2$. Mặt khác, $g(x) = (1+x)^n (x-1)^n = (-1)^n (1-x^2)^n = (-1)^n \times \sum_{k=0}^{n} (-1)^k C_n^k x^{2k}$. Trong tổng này, các hệ số của lũy thừa lẻ $x$ bằng 0. Do đó, nếu $n$ là số lẻ thì hệ số của $x^n$ bằng 0. Nếu $n$ chẵn thì hệ số của $x^n$ bằng $(-1)^{n+\frac{n}{2}} C_n^{\frac{n}{2}} = (-1)^{\frac{n}{2}} C_n^{\frac{n}{2}}$. Vì vậy, $\sum_{k=0}^{n} (-1)^k \left( C_n^k \right)^2 = \left\{ \begin{array}{l} 0, n \text{ нечетно}, \\ (-1)^{\frac{n}{2}} C_n^{\frac{n}{2}}, n \text{ четно}. \end{array} \right.$

Bài tập

14. Tìm tổng $\sum_{k=0}^{n} \frac{C_n^k}{k+1}$. (Đáp số: $\frac{2^{n+1}-1}{n+1}$.)

15. Ta hãy biểu thị bằng $B_n^k$ hệ số của $x^k$ trong đa thức $(1+x+x^2)^n$. Tìm tổng $\sum_{k=0}^{2n} \left( B_n^k \right)^2$. (Đáp số: $B_{2n}^n$).

Thoạt nhìn, phương pháp này trông rất giả tạo, bởi vì mọi người không hiểu cách học cách chọn đa thức đúng. Thật không may, trong bài viết này chúng tôi không thể đi sâu vào chi tiết hơn về vấn đề này.

Tuy nhiên, chúng tôi cho rằng sau khi giải các bài tập gợi ý, bạn có thể tự mình giải các bài tập bài toán tương tự.

4. phép biến đổi Abel

Giả sử chúng ta có tổng $S_n = a_1 b_1 + a_2 b_2 + \dots + a_n b_n$, trong đó $a_1, a_2, \dots, a_n, b_1, b_2, \dots, b_n$ là hai dãy. Chúng ta hãy biểu thị tổng của $b_1, b_1 + b_2, \dots, b_1 + b_2, \dots, b_1 + b_2 + \dots + b_n$ tương ứng với $B_1, B_2, \dots, B_n$. Khi đó $b_1 = B_1, b_k = B_k - B_{k-1}$ với $k > 1$ và $\sum_{k=1}^{n} a_k b_k$ có thể được chuyển đổi như sau:

$$\sum_{k=1}^{n} a_k b_k = a_1 B_1 + a_2 (B_2 - B_1) + \dots + a_n (B_n - B_{n-1}) = (a_1 - a_2) B_1 + (a_2 - a_3) B_2 + \dots + (a_{n-1} - a_n) B_{n-1} + a_n B_n = \sum_{k=1}^{n-1} (a_k - a_{k+1}) B_k + a_n B_n.$$

Phép biến đổi này được gọi là phép biến đổi Abel (để biết bậc đáng chú ý của nhà toán học Nils Henrik Abell, xem «Kvant» số 5 năm 1976).

Sử dụng các phép biến đổi Abel, chúng ta tìm được tổng $\sum_{k=1}^{n} kq^{k-1}$.

Chúng ta đặt $a_1 = 1, a_2 = 2, \dots, a_n = n; b_1 = 1, b_2 = q, \dots, b_n = q^{n-1}$ tại điểm (10). Sau đó $B_k = \frac{q^k - 1}{q-1}$ và $a_1 - a_2 = a_2 - a_3 = \dots = a_{n-1} - a_n = -1$. Pozotomu

$$\sum_{k=1}^{n} kq^{k-1} = \sum_{k=1}^{n-1} (-1) \frac{q^k - 1}{q-1} +$$
