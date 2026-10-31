---
id: 1988-11-12-vaynshteyn-razbienie-chisel-d0904caf
issue: kvant_1988_11-12
year: 1988
number: 11-12
title: Phân vùng số
authors:
  - Вайнштейн Ф. В.
rubric: raznoe
page_first: 21
page_last: 27
page_labels: 19, 22, 23, 24, 25
tag: ER1M
lang: vi
source: kvant_digital
extraction: vision
content_sha256: a4e16ed29c4b3c1aa21f69ccd4c6d82ba51cd7f7c63f0eace6e59e8078443dc1
prompt_sha256: draft-1
translated_from: content/ru/1988/11-12/articles/08_vaynshteyn-razbienie-chisel-d0904caf.md
source_content_sha256: e6cbe1e0e535df33a378ae6253c20bcf6f5bbdd60ba874003b5c0721efb77db6
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 19⟧

TÁCH SỐ

F. V. WEINSTEIN

Một phân vùng là một số tự nhiên được biểu diễn dưới dạng tổng của các số hạng tự nhiên và bản thân các số hạng này được gọi là các phần của phân vùng. Thứ tự của các điều khoản không quan trọng; do đó các phân vùng 3=1+2 và 3=2+1 không khác nhau. Chúng tôi sẽ viết ra các phân vùng, liệt kê các phần của chúng được phân tách bằng dấu phẩy theo thứ tự không tăng. Ví dụ: phân vùng 4=2+1+1 được viết là (2, 1, 1).

Gọi $p(n)$ là số phân chia của số tự nhiên $n$. Đối với $n$ nhỏ, có thể dễ dàng tính $p(n)$ chỉ bằng cách viết ra tất cả các phân vùng. Ví dụ: $p(5)=7$. Dưới đây là tất cả 7 phép chia của số 5: (5), (4, 1), (3, 2), (3, 1, 1), (2, 2, 1), (2, 1, 1, 1), (1, 1, 1, 1, 1). Tuy nhiên, không thể tưởng tượng được việc đạt được $p(100)=190\ 569\ 292$ theo cách này mà không có sự trợ giúp của máy tính. Trong khi đó, $p(100)$ đã được biết đến vào thế kỷ trước. Chúng tôi sẽ giới thiệu cho bạn nhiều đặc tính thú vị của phân vùng và hướng dẫn bạn cách tìm $p(n)$ mà không cần viết ra tất cả các phân vùng của $n$.

Bài toán tính toán $p(n)$ có tuổi đời đáng kính. Nó được Leibniz xây dựng lần đầu tiên vào năm 1654, và vào năm 1740 nó được nhà toán học người Đức Philipp Naudet đề xuất với Leonard Euler. Trong khi nghiên cứu các phân vùng, Euler đã phát hiện ra một số tính chất của chúng, trong đó “định lý ngũ giác” nổi tiếng chiếm vị trí chính. Nghiên cứu của Euler bắt đầu lịch sử của lý thuyết phân chia, trong quá trình phát triển nó có sự tham gia của các nhà toán học vĩ đại nhất của các thế hệ tiếp theo.

⟦folio 22⟧

le, v.v., cho đến khi bạn đạt đến số $k_q$.

Ví dụ: chia số 25 thành các phần lẻ (9, 9, 5, 1, 1) sẽ tương ứng với hình được mô tả ở hình 1. Nó bao gồm các góc đối xứng với đường chéo, sao cho ở góc trên cùng có $2k_1+1$ điểm, ở các điểm $2k_2+1$ tiếp theo, v.v., và tổng cộng sẽ có $n$ điểm. Bây giờ, hãy vẽ các đường trên cùng một bản đồ như trong hình 2, đếm số điểm trên mỗi đường này và số phân vùng thu được theo cách này. Hóa ra tất cả các phần của phân vùng này đều khác nhau.

Bài tập 5. Chứng minh khẳng định này.

Trong ví dụ của chúng tôi, phân vùng sẽ là (9,6,5,4,1). Hãy suy nghĩ về cách xây dựng một phân vùng thành các phần lẻ từ phân vùng thành các phần khác nhau, tức là khôi phục bản đồ đối xứng ban đầu từ phân vùng đó.

Rút lui: lời giải bài toán M1065

Phần này sử dụng một kỹ thuật phức tạp hơn phần còn lại của bài viết. Nếu muốn, bạn có thể lướt qua mà không đi sâu vào chi tiết và tiếp tục đọc phần tiếp theo. Vì vậy, hãy giải bài toán M1065 từ “Bài toán «Kvant»” (1987, số 9). Chúng ta hãy nhớ lại công thức của nó.

Chúng tôi xem xét vectơ $(x, y)$ với tọa độ nguyên không âm và ít nhất một trong các tọa độ khác 0. Chúng tôi gọi vectơ như vậy là trình tạo nếu $|x-y|=1$.

a) Chứng minh rằng vectơ $(x, y)$ đang xét có thể được biểu diễn dưới dạng tổng của các bộ tạo khác nhau (hoặc chính nó là một bộ tạo) khi và chỉ khi đại lượng $k(x, y)=x+y-(x-y)^2$ không âm.

b) Chứng minh rằng số $N(x, y)$ khác nhau (theo thứ tự) được biểu thị bằng vectơ $(x, y)$ dưới dạng tổng của các phần tử sinh khác nhau chỉ phụ thuộc vào số $k=k(x, y)$. Tìm $N(13, 18)$.

Lời giải bài toán để tìm dạng tổng quát của bất đẳng thức số nguyên lời giải $k(x, y) \geq 0$. Các số $x+y$ và $x-y$ có cùng tính chẵn lẻ, vì vậy $k(x, y)$ là số chẵn đối với mọi số nguyên $x, y$. Do đó, với bất kỳ số nguyên $m \geq 0$ nào, chỉ cần tìm phương trình số nguyên lời giải $x+y-(x-y)^2=2m$ là đủ. Hãy đặt $x-y=q$. Sau đó $x+y=2m+q^2$. Từ hai đẳng thức này ta thu được ngay:

$$\begin{align*}
(x, y) &= (m+q(q+1)/2, \\
m+q(q-1)/2),
\end{align*}$$

trong đó $q$ là số nguyên bất kỳ và $m \geq 0$.

Ý nghĩa của các con số $m$ Và $q$ trở nên quan trọng hơn nếu chúng ta tưởng tượng các vectơ có dạng (3) với $m=0$ dưới dạng các điểm có tọa độ parabol nguyên $k(x, y)=0$, nằm trên máy bay $(x, y)$. (Bạn có hiểu tại sao đây là parabol không?) Khi đó các số nguyên ta thu được lời giải sự bất bình đẳng $k(x, y) \geq 0$ chứng minh rằng mọi điểm có tọa độ nguyên nằm trên một parabol $k(x, y)=0$ và bên trong nó, thu được bằng cách dịch chuyển các điểm nguyên của parabol này thành các vectơ $(m, m)$ (hình 3). Thật thuận tiện khi giả sử rằng số $m(m=0, 1, 2, ...)$ — số parabol mà điểm đó nằm trên đó $(x, y)$, MỘT $q=x-y=0, \pm 1, \pm 2, ...$ - số điểm trên parabol này.

Vì bài toán đối xứng về hoán vị tọa độ vectơ, nên việc rút ra tất cả các câu lệnh cho vectơ $(x, y)$ sao cho $x \geq y$, tức là đối với vectơ có dạng (3) với $q \geq 0$ là đủ.

Ta chứng minh điều kiện đủ ở phần a) bài toán. Sử dụng công thức tính tổng cấp số cộng

$$\begin{align*}
1+2+\dots+(q-1)+m+q &= m+q(q+1)/2; \\
0+1+\dots+q-2+m+(q-1) &= m+q(q-1)/2.
\end{align*}$$

⟦folio 23⟧

Các công thức của Posny $(x, y) = (1, 0) + (2, 1) + \dots + (q-1, q-2) + (m+q, m+q-1)$ cho $q > 0$ và $(m, m) = (1, 0) + (m-1, m)$ cho $q = 0$, $m > 0$ biểu diễn $(x, y)$ dưới dạng tổng của các bộ tạo khác nhau.

Việc chứng minh tính cần thiết của điều kiện cũng dễ dàng. Cho phép
$x = r_1 + \dots + r_a + s_1 + \dots + s_b$
$y = r_1 + \dots + r_a - a + s_1 + \dots + s_b + b$
có thể tạo dáng được $x - y = a - b$. Hãy đặt $q = x - y$ và
$m = (r_1 - q) + (r_2 - (q - 1)) + \dots$
$\dots + (r_q - 1) + r_{q+1} + \dots + r_a +$
$+ s_1 + \dots + s_b = x + y - q(q + 1)/2$
(ở đây chúng tôi lại sử dụng công thức tính tổng của một cấp số cộng). Từ bất đẳng thức (4) suy ra $r_a \geq 1, r_{a-1} \geq 2, r_{a-2} \geq 3, \dots$ và nói chung $r_i \geq q - i + 1$. Pozny $m \geq 0$, tức là $(x, y)$ là một vectơ có dạng (3), đây là điều bắt buộc.

Về mặt hình học, câu 6) có nghĩa là số

$$N(x, y)$$ chỉ phụ thuộc vào số $m$ của parabol và không phụ thuộc vào số $q$ của điểm trên parabol.

Đặt $T(m, q)$ là tập hợp các biểu diễn của vectơ (3) dưới dạng tổng của các bộ tạo khác nhau và $t(m, q)$ là số lượng các biểu diễn đó. Bài toán sẽ giải được nếu chúng ta chứng minh rằng với bất kỳ số nguyên $q$ nào thì đẳng thức $t(m, q) = t(m, q - 1)$ đúng (điều này có nghĩa là $t(m, q)$ và với nó $N(x, y)$, không phụ thuộc vào $q$). Chúng ta đặt phía trên tập $T(m, q)$ với tập hợp các cặp dãy thỏa mãn bất đẳng thức (4) sao cho $r_1 + \dots + r_a + s_1 + \dots + s_b = m + q(q + 1)/2$ cho $q = a - b$. Chúng ta sẽ viết một cặp như vậy dưới dạng $(r_1, \dots, r_a | s_1, \dots, s_b)$.

Xét việc ánh xạ $\varphi$ từ tập $T(m, q)$ vào tập $T(m, q - 1)$ được cho bởi công thức
$$\varphi(r_1, \dots, r_a | s_1, \dots, s_b) = \begin{cases} (r_1 - 1, \dots, r_a - 1 | s_1 + 1, \dots, s_b + 1, 0), \\ \text{если } r_a > 1, \\ (r_1 - 1, \dots, r_{a-1} - 1 | s_1 + 1, \dots, s_b + 1), \\ \text{если } r_a = 1. \end{cases}$$

Bài tập 6. Kiểm tra xem $\varphi(r_1, \dots, r_a | s_1, \dots, s_b) \in T(m, q - 1)$.

Để chứng minh $\varphi$ là ánh xạ một-một, ta xây dựng ánh xạ nghịch đảo $\psi$: $T(m, q - 1) \rightarrow T(m, q)$, đọc quy tắc cho bởi $\varphi$, ta làm theo:

$$\psi(r_1, \dots, r_a | s_1, \dots, s_b) = \begin{cases} (r_1 + 1, \dots, r_a + 1, 1 | s_1 - 1, \dots, s_b - 1), \\ \text{если } s_b > 0, \\ (r_1 + 1, \dots, r_a + 1 | s_1 - 1, \dots, s_b - 1), \\ \text{если } s_b = 0. \end{cases}$$

Các ánh xạ được xây dựng là nghịch đảo lẫn nhau, do đó $\varphi$ là sự tương ứng một-một. Điều này có nghĩa là $t(m, q) = t(m, q - 1)$, như đã nêu.

Để tìm hiểu cách tính các giá trị của $N(x, y)$, hãy đặt giữa các số $t(m, q)$ và $p(m)$.

Tuyên bố: $t(m, q) = p(m)$.

Chúng ta đã biết rằng $t(m, q) = t(m, 0)$ nên chỉ cần chứng minh rằng $t(m, 0) = p(m)$ là đủ. Hãy sử dụng một công cụ đồ họa đơn giản và hữu ích được gọi là sơ đồ Younes.

⟦folio 24⟧

Tôi đánh giá cao nó. Ví dụ, hãy xem xét phân vùng (6, 4, 4, 2, 1). Sơ đồ Young của anh ấy được hiển thị trên hình 4 (dòng đầu tiên có 6 dấu chấm, dòng thứ hai - 4, dòng thứ ba - 4, dòng thứ tư - 2, dòng thứ năm - 1). Bất kỳ phân vùng nào cũng có thể được mô tả dưới dạng sơ đồ Young và phân vùng đó có thể được viết dọc theo toàn bộ sơ đồ Young.

Hãy vẽ một đường chéo trên sơ đồ Young - một đường màu đen trên hình 4. Gọi $r_1$ là số điểm ở dòng đầu tiên nằm trên đường chéo và bên phải của nó, $r_2$ số điểm ở dòng thứ ba nằm trên đường chéo và bên phải của nó, v.v.; $s_1$ là số điểm của cột thứ nhất dưới đường chéo, $s_2$ là số điểm của cột thứ hai dưới đường chéo, v.v. Ta đặt theo sơ đồ Young, phân chia của số $m$, một cặp của dãy

$$\left( r_1, r_2, \dots | s_1, s_2, \dots \right),$$
$$r_1 + r_2 + \dots + s_1 + s_2 + \dots = m,$$

tức là một phần tử của tập hợp $T(m,0)$. Ví dụ: sơ đồ ở hình 4 tương ứng với cặp (6, 3, 2|4, 2, 0). Biết một vài trình tự, bạn có thể dễ dàng xây dựng lại sơ đồ Young. Do đó, chúng tôi đã thiết lập sự tương ứng một-một giữa tập hợp các phân vùng và tập hợp $T(m,0)$. Tuyên bố đã được chứng minh.

Bây giờ, bạn không mất phí gì để trả lời câu hỏi cuối cùng bài toán - về giá trị của $N(13,18)$. Vì $13 = 3 + 5 \cdot 4/2$, $18 = 3 + 6 \cdot 5/2$, điểm (13,18) nằm trên parabol thứ ba. Vì vậy, $N(13,18) = t(3,0) = p(3) = 3$.

Các bài tập sau đây nói về việc sử dụng sơ đồ Young.

Bài tập

7. Số phân vùng $n$ không quá $k$ phần bằng số phân vùng $n$ với số phần không quá $k$. Gợi ý: Hãy phản ánh biểu đồ Young theo đường chéo.

8. Số phân vùng $n$ với các phần khác nhau bằng số phân vùng $n$ có sơ đồ Young đối xứng qua đường chéo. Gợi ý: hãy nhớ thư từ của Sylvester.

Công thức Gauss-Jacobi

Chúng tôi đã làm rất nhiều việc để giải bài toán M1065. Có thể sử dụng lại các hàm tùy ý và trích xuất một số nhận dạng màu đỏ từ đẳng thức $t(m,q) = p(m)$ không?

$N(x,y)$ là số cách mà vectơ $(x,y)$ có thể được biểu diễn dưới dạng tổng của các bộ tạo khác nhau có dạng $(k,k-1)$ và $(k-1,k)$. Lập luận tương tự như khi suy ra công thức hàm số phân hoạch tùy ý có các phần khác nhau, ta sẽ viết hàm tùy ý cho $N(x,y)$ (đây là dãy gồm hai biến $u$ và $v$):

$$\prod_{k=1}^{\infty} \left( 1 + u^{k-1} v^k \right) \left( 1 + u^k v^{k-1} \right) = \sum_{x,y=0}^{\infty} N(x,y) u^x v^y.$$

Vì $N(x,y) = t(m,q)$, trong đó $x = m + q(q+1)/2, y = m + q(q-1)/2$, đẳng thức có thể được chia:

$$\sum_{q=-\infty}^{\infty} \left( \sum_{m=0}^{\infty} t(m,q) u^m v^m \right) \times u^{q(q+1)/2} v^{q(q-1)/2}.$$

Bây giờ chúng ta hãy sử dụng $t(m,q) = p(m)$ đó và tiếp tục đẳng thức:

$$\sum_{q=-\infty}^{\infty} \left( \sum_{m=0}^{\infty} p(m) u^m v^m \right) \times u^{q(q+1)/2} v^{q(q-1)/2}.$$

Chuỗi trong ngoặc đơn là hàm tùy ý của các số trong phân vùng $p(m)$ mà chúng ta đã biết (công thức (1)), vì vậy chúng ta tiếp tục:

$$\prod_{k=1}^{\infty} \left( 1 - u^k v^k \right)^{-1} \sum_{q=-\infty}^{\infty} u^{q(q+1)/2} v^{q(q-1)/2}.$$

Bây giờ, hãy so sánh vế trái của đẳng thức thứ nhất và vế phải của đẳng thức cuối cùng bằng cách nhân cả hai vế với $\Pi(1 - u^k v^k)^{-1}$. Chúng tôi nhận được kết quả cuối cùng:

$$\prod_{k=1}^{\infty} \left( 1 + u^{k-1} v^k \right) \left( 1 + u^k v^{k-1} \right) =$$

⟦folio 25⟧

$$\sum_{q=-\infty}^{\infty} u^{q(q+1)/2} v^{q(q-1)/2}.$$

Sự giống nhau này là mục tiêu của sự biến đổi của chúng tôi. Nó được gọi là công thức Gauss-Jacobi. Từ danh tính tuyệt vời với hai biến này, người ta có thể có được nhiều danh tính khác nhau với một biến.

Bài tập 9. Thay $u=-t$, $v=-t^2$ vào công thức Gauss-Jacobi và thu được định lý ngũ giác Euler.

Bây giờ hãy thay $u=v=-t$ vào công thức Gauss–Jacobi. Ở phía bên trái bạn nhận được:

$$\prod_{k=1}^{\infty} (1-t^{2k-1})^2 (1-t^{2k}) = \prod_{k=1}^{\infty} (1-t^{2k-1}) \prod_{k=1}^{(1-t^k)}.$$

Thay tích $\Pi(1-t^{2k-1})$ bằng $\Pi(1+t^k)^{-1}$ theo công thức (2), ta biến đổi vế trái thành $(1-t)(1-t^2)(1-t^3).../(1+t)(1+t^2)(1+t^3)...$.

Khi thay thế $u=v=-t$, vế phải của công thức Gauss-Jacobi biến thành $\sum_{-\infty}^{\infty} (-1)^q t^q$. Chúng ta nhận được công thức sau:

$$\frac{(1-t)(1-t^2)(1-t^3)...}{(1+t)(1+t^2)(1+t^3)...} = 1-2t+2t^4-2t^9+2t^{16}-...$$

Thay thế $u=t$, $v=1$ vào công thức Gauss–Jacobi tương tự sẽ dẫn đến công thức:

$$\frac{(1-t^2)(1-t^4)(1-t^6)...}{(1-t)(1-t^3)(1-t^5)...} = 1+t+t^3+t^6+t^{10}+...$$

Hai công thức này đã được Gaus thu được. Không cần phải nói, đây là những công thức đẹp đến kinh ngạc!

Đồng nhất thức Rogers–Ramanujan

Để kết luận, tôi muốn giới thiệu với bạn hai ý nghĩa về đồng nhất thức của lý thuyết phân vùng, mà vẫn chưa tìm thấy bằng chứng tùy ý, mặc dù bài toán và syaden này vẫn nằm trong lĩnh vực được nhiều nhà toán học quan tâm.

Danh tính đầu tiên. Số cách chia của số tự nhiên $n$ trong đó hiệu giữa hai phần bất kỳ lớn hơn một bằng số cách chia của số $n$ thành các phần chia cho 5 dư 1 hoặc 4.

Danh tính thứ hai. Số phân hoạch của số tự nhiên $n$ trong đó hiệu giữa hai phần bất kỳ và mỗi phần lớn hơn một bằng số phân hoạch của số $n$ thành các phần chia cho 5 dư 2 hoặc 3.

Tất nhiên, hình mẫu được thiết lập bởi những đồng nhất thức này là vô cùng đẹp đẽ và không tầm thường, và không có gì đáng ngạc nhiên khi nhà toán học người Anh vĩ đại nhất thế kỷ, G. Hardy, người biết về chúng từ bức thư của Ramanujan ngày 16 tháng 1 năm 1913, đã rất vui mừng.*)

Khi đọc bài viết này, bạn có thể có ấn tượng rằng lý thuyết phân chia chứa đầy những điều tò mò, trong đó nhiều thí nghiệm kỳ lạ khác nhau được thu thập cẩn thận và không có cách nào hoặc gần như không có cách nào kết nối với nhau. Cho đến gần đây đây là trường hợp. Tình hình chỉ thay đổi hoàn toàn vào những năm 70 của thế kỷ, khi nhà toán học người Anh I. MacDonald tìm ra một cách tiếp cận thống nhất để chứng minh một lớp lớn các đồng nhất thức của lý thuyết phân chia và khám phá ra nhiều đồng nhất thức mới, kết hợp chúng thành một lý thuyết mạch lạc (bao gồm cả đồng nhất thức Gauss-Jacobi).**) Đối với các đẳng thức Rogers-Ramanujan và nhiều đồng nhất thức tương tự, vẫn chưa tìm ra một cách tiếp cận tổng quát, mặc dù các phương pháp đại số cho chúng gần đây đã xuất hiện bằng chứng.

Vì vậy, người ta tin rằng vẫn cần phải hiểu được bản chất thực sự của những danh tính này.

*) Bạn có thể đọc về cuộc đời và sự nghiệp của nhà toán học nổi tiếng người Ấn Độ trong bài viết “Câu đố về Ramanujan” của S. G. Gindikin («Kvant», 1987, số 10).

**) Bạn có thể tìm thấy thông tin chi tiết hơn về điều này trong bài viết của D. V. Fuchs “Về việc mở ngoặc, về Euler, Gauss và MacDonald và về những cơ hội bị bỏ lỡ” («Kvant», 1981, số 8).
