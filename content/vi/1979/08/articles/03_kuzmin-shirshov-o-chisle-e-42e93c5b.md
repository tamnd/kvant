---
id: 1979-8-kuzmin-shirshov-o-chisle-e-42e93c5b
issue: kvant_1979_8
year: 1979
number: "8"
title: Về số e
authors:
  - Кузьмин Е. Н.
  - Ширшов А. И.
rubric: osnovnye-stati
page_first: 5
page_last: 10
page_labels: 3, 4, 6, 7, 8
tag: 9KKE
lang: vi
source: kvant_digital
extraction: vision
content_sha256: d413929bdb468efdaa97840fb098bd9965d9a2df7fc8b6eab277ef0a10ee6e8d
prompt_sha256: draft-1
translated_from: content/ru/1979/08/articles/03_kuzmin-shirshov-o-chisle-e-42e93c5b.md
source_content_sha256: 1f0814c7955b733281e991b0fb138da56f98c980f31e0857d49fe5f443a6ba38
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 3⟧

Về số e

1. e là gì?

Ở trường, ngay từ lớp 5, bạn đã được làm quen với số π, con số này có lịch sử rất lâu đời, khởi đầu của nó đã bị thất lạc trong sương mù thời gian, trong thế giới cổ đại *). Rồi bạn gặp anh ấy vào năm lớp tám, lớp chín, lớp mười. Bạn chỉ bắt gặp số e vào cuối năm lớp mười. Tuy nhiên, con số đáng chú ý này, được đưa vào sử dụng vào thế kỷ 18 cùng với sự phát triển của giải tích toán học, gần như đóng một vai trò quan trọng hơn trong toán học hiện đại.

Trong sách giáo khoa của trường có hai định nghĩa về số e. Trong trường hợp thứ hai (chúng ta không cần số thứ nhất), số e là giới hạn của dãy $x_n = \left(1 + \frac{1}{n}\right)^n$. Hãy chứng minh rằng giới hạn này tồn tại.

Bổ đề 1. Với mọi m, n

$$\left(1 + \frac{1}{n}\right)^n < \left(1 + \frac{1}{m}\right)^{m+1}.$$

(1)

bất đẳng thức (1) rất dễ chứng minh bằng bất đẳng thức Cauchy nổi tiếng:

$$\sqrt[n]{a_1 \cdot a_2 \cdot \dots \cdot a_n} < \frac{a_1 + a_2 + \dots + a_n}{n},$$

(2)

trong đó $a_1, a_2, \dots, a_n$ là các số dương, trong đó có các số khác nhau**). Từ (2)

$$\sqrt[n]{1 + \frac{1}{n}} \left(1 - \frac{1}{m+1}\right)^{m+1} < \frac{n \left(1 + \frac{1}{n}\right) + (m+1) \left(1 - \frac{1}{m+1}\right)}{m+n+1} = 1,$$

từ đâu $$\left(1 + \frac{1}{n}\right)^n \left(1 - \frac{1}{m+1}\right)^{m+1} < 1$$ và $$\left(1 + \frac{1}{n}\right)^n < \left(1 + \frac{1}{m}\right)^{m+1}.$$

Bổ đề 2. Dãy số $(x_n)$ tăng dần.

Bằng chứng. Chúng ta hãy biểu thị $\left(1 + \frac{1}{n}\right)^n+1$ bằng $y_n$. Theo Bổ đề 1, $x_{n(n+2)} < y_{n+1}$, đó là

$$\left(1 + \frac{1}{n(n+2)}\right)^{n(n+2)} < \left(1 + \frac{1}{n+1}\right)^{n+2}.$$

*) Nhiều chi tiết thú vị về số π có thể được tìm thấy trong cuốn sách của F. Kymen và “Lịch sử của số π” (M., “Nauka”, 1971). Xem thêm bài viết của A. Zvonkin “Pi là gì?” («Kvant», 1978, số 11).

**) Hãy thử tự mình chứng minh điều đó. Bạn cũng có thể đọc bằng chứng của anh ấy trên trang. 26.

⟦folio 4⟧

Có nghĩa,

$$\left(1 + \frac{1}{n(n+2)}\right)^n < 1 + \frac{1}{n+1}.$$

Vì vậy, $$\left(1 + \frac{1}{n(n+2)}\right)^n = \frac{(n+1)^2n}{n^n(n+2)^n} < \frac{n+2}{n+1}.$$

Vì vậy $$\left(\frac{n+1}{n}\right)^n < \left(\frac{n+2}{n+1}\right)^{n+1}$$ hoặc $$x_n < x_{n+1}.$$

Từ Bổ đề 1, 2 và định lý Weierstrass suy ra rằng dãy $(x_n)$ có giới hạn. Ký hiệu $e$ cho giới hạn này được đưa ra bởi L. Euler (1707–1783).

Bài tập. Chứng minh rằng $$\lim_{n \to \infty} y_n = e$$ và với mọi $m, n$

$$x_n < e < y_m.$$

Số $e$ cũng có thể được định nghĩa là giới hạn của chuỗi $s_n = 1 + \frac{1}{1!} + \frac{1}{2!} + \dots + \frac{1}{n!}$. Hãy chứng minh điều đó. Theo công thức Newton

$$x_n = 1 + n \cdot \frac{1}{n} + \frac{n(n-1)}{2!} \cdot \frac{1}{n^2} + \dots + \frac{n(n-1) \cdot \dots \cdot (n-k+1)}{k!} \cdot \frac{1}{n^k} + \dots + \frac{1}{n^n} = 1 + 1 + \frac{1}{2!} \left(1 - \frac{1}{n}\right) + \dots + \frac{1}{k!} \left(1 - \frac{1}{n}\right) \times \left(1 - \frac{2}{n}\right) \dots \dots \left(1 - \frac{k-1}{n}\right) \times \left(1 - \frac{2}{n}\right) \dots \dots \left(1 - \frac{n-1}{n}\right).$$

(Từ (3), cũng rõ ràng là dãy $(x_n)$ đang tăng dần.) Bằng cách loại bỏ các thừa số trong ngoặc đơn, chúng ta sẽ tăng từng số hạng ở vế phải của đẳng thức (4). Do đó, $x_n < s_n$ (tại $n > 1$).

Bây giờ chúng tôi sửa một $k > 1$ tùy ý. Giả sử rằng $n > k$, chúng tôi loại bỏ tất cả các số hạng ở vế phải của đẳng thức (3), bắt đầu bằng $(k+2)$. chúng tôi nhận được

$$x_n > 1 + 1 + \frac{1}{2!} \left(1 - \frac{1}{n}\right) + \dots + \frac{1}{k!} \left(1 - \frac{1}{n}\right) \left(1 - \frac{2}{n}\right) \dots \dots \left(1 - \frac{k-1}{n}\right).$$

Đối với $n \to \infty$ (và cố định $k$), vế phải của bất đẳng thức (4) có xu hướng $s_k$. Vượt qua giới hạn của bất đẳng thức (4), ta thu được $e \geqslant s_k$. Vì vậy, $x_n < s_n \leqslant e$. Từ $$\lim_{n \to \infty} x_n = e$$ chúng ta nhận được $$\lim_{n \to \infty} s_n = e.$$ Do đó,

$$e = 1 + \frac{1}{1!} + \frac{1}{2!} + \dots + \frac{1}{n!} + \dots.$$

Chuỗi $(s_n)$ thuận tiện hơn nhiều khi sử dụng để tính các giá trị gần đúng của số $e$ so với chuỗi $(x_n)$. Hãy ước tính sự khác biệt $e - s_n$. Từ (5)

$$e - s_n = \frac{1}{(n+1)!} + \frac{1}{(n+2)!} + \dots =$$

$$= \frac{1}{(n+1)!} \left[ 1 + \frac{1}{n+2} + \frac{1}{(n+2)(n+3)} + \dots \right] <$$

$$< \frac{1}{(n+1)!} \left[ 1 + \frac{1}{n+2} + \frac{1}{(n+2)^2} + \dots \right] =$$

$$= \frac{1}{(n+1)!} \cdot \frac{1}{1 - \frac{1}{n+2}} = \frac{n+2}{(n+1)^2 \cdot n!} < \frac{1}{n \cdot n!}.$$

⟦folio none⟧

Kết quả thu được có thể viết dưới dạng đẳng thức

$$e = s_n + \frac{\theta_n}{n \cdot n!} \quad (0 < \theta_n < 1).$$

Từ (6) dễ dàng suy ra tính vô tỷ của số $e$. Thật vậy, giả sử rằng $e = \frac{p}{q}$. thì $q!e$ là một số nguyên. Từ (6) tại $n=a$

$$q!e = q! + q! + \frac{q!}{2!} + \dots + \frac{q!}{q!} + \frac{\theta_q}{q}.$$

Hóa ra $\frac{\theta_q}{q}$ là một số nguyên, rõ ràng là sai. Đây là chữ số thập phân đầu tiên của số $e$.

$$e = 2,718281828459045\dots$$

2. Vấn đề về phân vùng

Con số $e$, con cưng của giải tích toán học và lý thuyết hàm số, xuất hiện khá bất ngờ trong một số bài toán tổ hợp. Hãy xem xét một bài toán như vậy.

Hãy bắt đầu với một ví dụ. Tập hợp hai phần tử $\{a_1, a_2\}$ có thể được phân chia thành các tập con rời rạc (khi nói về phân vùng, chúng được gọi là các lớp) theo hai cách: đây là phân vùng “từng phần đất” $\{a_1\}, \{a_2\}$ và phân vùng “số nguyên” suy biến $\{a_1, a_2\}$. Các phân vùng tương tự tồn tại (cho $n>2$) cho bất kỳ bộ phần tử $n$ nào. Tại $n=3$, ba phân vùng nữa được thêm vào chúng (Hình 1).

Chúng ta hãy biểu thị số phân vùng của phần tử $n$ được đặt bởi $\tau(n)$ *).

Rõ ràng là $\tau(0) = \tau(1) = 1$. Như chúng tôi vừa lưu ý, $\tau(2) = 2$, $\tau(3) = 5$. $\tau(n)$ bằng bao nhiêu đối với $n$ tùy ý? Có thể chỉ ra một số công thức đơn giản cho $\tau(n)$ không?

Như thường thấy trong các bài toán tổ hợp, rất dễ tìm thấy mối quan hệ truy hồi liên quan đến $\tau(n)$ với các giá trị $\tau(k)$ của $k < n$.

Hãy để $M = \{a_1, a_2, \dots, a_n\}$. Chúng ta hãy sắp xếp tất cả các phân vùng của tập hợp $M$ tùy thuộc vào số lượng $k$ các phần tử của lớp trong đó phần tử $a_1$ nằm trong một phân vùng nhất định. Số $k$ có thể bằng 1,2,...,$n$. Đối với $k$ cố định, số lượng phân vùng như vậy rõ ràng bằng $C_{n-1}^{k-1}\tau(n-k)$.

Vì vậy, $\tau(n) = \sum_{k=1}^{n} C_{n-1}^{k-1}\tau(n-k)$. Thật dễ dàng để kiểm tra điều đó

$$\sum_{k=1}^{n} C_{n-1}^{k-1}\tau(n-k) = \sum_{k=0}^{n-1} C_{n-1}^{k-1}\tau(k).$$

Tất nhiên rồi,

$$\tau(n) = \sum_{k=0}^{n-1} C_{n-1}^{k-1}\tau(k).$$

Sử dụng công thức (7), dễ dàng tính được $\tau(4)=15$, $\tau(5)=52$, $\tau(6)=203$, $\tau(7)=877$, $\tau(8)=4140$—khi $n$ tăng, số $\tau(n)$ tăng nhanh.

*) Các số $\tau(n)$ được gọi là số Bell («Kvant», 1978, số 7).

⟦folio 6⟧

Chúng ta sẽ sử dụng công thức truy hồi (7) để chứng minh một phát biểu yêu thích trong đó cần kiểm tra số $e$:

$$e \cdot \tau(n) = \frac{1^n}{1!} + \frac{2^n}{2!} + \dots + \frac{k^n}{k!} + \dots \quad (n \geqslant 1)$$

Bằng chứng. Hãy sử dụng phương pháp quy nạp toán học. Vì $n=1$ (8) đúng do (5). Bây giờ chúng ta giả sử rằng (8) đúng với mọi số nhỏ hơn một số $n$; Hãy chứng minh điều đó thì nó cũng đúng với $n$. Theo (5) và theo giả thuyết quy nạp, các đẳng thức sau đây đúng:

$$e \cdot \tau(0) = 1 + \frac{1}{1!} + \frac{1}{2!} + \dots + \frac{1}{k!} + \dots$$

$$e \cdot \tau(1) = \frac{1}{1!} + \frac{2}{2!} + \dots + \frac{k}{k!} + \dots$$

$$e \cdot \tau(2) = \frac{1^2}{1!} + \frac{2^2}{2!} + \dots + \frac{k^2}{k!} + \dots$$

$$e \cdot \tau(n-1) = \frac{1^{n-1}}{1!} + \frac{2^{n-1}}{2!} + \dots + \frac{k^{n-1}}{k!} + \dots$$

(Các tổng vô hạn ở vế phải tất nhiên phải được hiểu là tổng một phần giới hạn.) Chúng ta hãy cộng các đẳng thức này theo từng số hạng với các hệ số tương ứng với $C_{n-1}^0, C_{n-1}^1, C_{n-1}^2, \dots, C_{n-1}^{n-1}$. Ở vế trái, theo (7), ta được $e \cdot \tau(n)$, ở vế phải

$$1 + \frac{\varphi(1)}{1!} + \frac{\varphi(2)}{2!} + \dots + \frac{\varphi(k)}{k!} + \dots$$

ở đâu $\varphi(t) = C_{n-1}^0 + C_{n-1}^1 t + C_{n-1}^2 t^2 + \dots + C_{n-1}^{n-1} t^{n-1} = (1+t)^{n-1}$.

Kể từ đây,

$$e \cdot \tau(n) = 1 + \frac{2^{n-1}}{1!} + \frac{3^{n-1}}{2!} + \dots + \frac{(k+1)^{n-1}}{k!} + \dots = \frac{1^n}{1!} + \frac{2^n}{2!} + \frac{3^n}{3!} + \dots + \frac{(k+1)^n}{(k+1)!} + \dots$$

Q.E.D. Từ (8) chúng ta có được một công thức đẹp

$$\tau(n) = \frac{1}{e} \sum_{k=1}^{\infty} \frac{k^n}{k!}$$

tuy nhiên, bất tiện cho việc tính $\tau(n)$. Dưới đây chúng ta sẽ thu được các công thức hữu hạn (không thông qua một chuỗi) đơn giản (theo nghĩa “không lặp lại”) để tính $\tau(n)$.

Chúng ta hãy gọi thứ hạng của một phân vùng nhất định bằng số lớp mà nó bao gồm. Chúng ta hãy biểu thị bằng $c_{n,k}$ số phân vùng xếp hạng $k$ của tập hợp phần tử $n$ $^*$. Rõ ràng, thứ hạng chỉ có thể lấy các giá trị $1,2,\dots,n$; Đó là lý do tại sao

$$\tau(n) = \sum_{k=1}^{n} c_{n,k}.$$

Đối với $k>n$ chúng tôi đặt $c_{n,k}=0$.

Đối với các số $c_{n,k}$ dễ dàng có được quan hệ truy hồi. Hãy để $M=\{a_1,a_2,\dots,a_n\}, M'=\{a_2,\dots,a_n\}$. Hãy chia các phân vùng của tập hợp

$$^*$$

*) Các số $c_{n,k}$ được gọi là số Stirling.

⟦folio 7⟧

stva $M$ thứ hạng $k$ thành hai nhóm - thành các phân vùng chứa tập hợp một màu xanh lá cây $\{a_1\}$ như một lớp phân vùng và không chứa. Rõ ràng là có nhiều phân vùng thuộc loại đầu tiên bằng số phân vùng của tập hợp $M'$ thứ hạng $k-1$, đó là $c_{n-1,k-1}$; phân vùng loại thứ hai - trong $k$ gấp nhiều lần so với phân vùng của tập hợp $M'$ thứ hạng $k$ (yếu tố $a_1$ có thể được đặt trong bất kỳ $k$ thiết lập các lớp phân vùng $M'$), đó là $k \cdot c_{n-1,k}$. Vì vậy, khi $n > 1, k > 1$

$$c_{n,k} = c_{n-1,k-1} + k \cdot c_{n-1,k}. \tag{10}$$

Hãy để chúng tôi chứng minh điều đó với $n \geqslant 1, k \geqslant 1$

$$c_{n,k} = \sum_{s=0}^{k-1} \frac{(-1)^s (k-s)^{n-1}}{s! (k-s-1)!}. \tag{11}$$

Chúng ta hãy biểu thị thương số đúng lời giải (11) bằng $b_{n,k}$. Nếu $k=1$ thì $b_{n,1} = 1 = c_{n,1}$. Nếu $k > 1$ và $n=1$ thì

$$b_{1,k} = \sum_{s=0}^{k-1} \frac{(-1)^s}{s! (k-s-1)!} = \frac{1}{(k-1)!} \sum_{s=0}^{k-1} (-1)^s C_{k-1}^s = \frac{1}{(k-1)!} (1-1)^{k-1} = 0 = c_{1,k}.$$

Cuối cùng, nếu $k > 1$ và $n > 1$ thì

$$b_{n,k} = \sum_{s=0}^{k-1} \frac{(-1)^s (k-s)^{n-1}}{s! (k-s-1)!} = \sum_{s=0}^{k-1} \frac{(-1)^s (k-s)^{n-2} \cdot (k-s)}{s! (k-s-1)!} = k \sum_{s=0}^{k-1} \frac{(-1)^s (k-s)^{n-2}}{s! (k-s-1)!} + \sum_{s=0}^{k-1} \frac{(-1)^s+1 (k-s)^{n-2} \cdot s}{s! (k-s-1)!} = k \cdot b_{n-1,k} + \sum_{s=1}^{k-1} \frac{(-1)^s+1 (k-s)^{n-2}}{s! (k-s-1)!} = k \cdot b_{n-1,k} + \sum_{s=0}^{k-1} \frac{(-1)^s+1 (k-s)^{n-2}}{s! (k-s-1)!} = k \cdot b_{n-1,k} + b_{n-1,k-1}.$$

Do đó, các số $c_{n,k}$ và $b_{n,k}$ thỏa mãn cùng một quan hệ rerent của dạng (10); Ngoài ra, “giá trị ban đầu” của chúng: cho $k=1$ (và bất kỳ $n \geqslant 1$) và cho $n=1$ (và bất kỳ $k \geqslant 1$) trùng khớp. Do đó (Hình 2), $c_{n,k} = b_{n,k}$ với mọi $n \geqslant 1$ và $k \geqslant 1$.

Từ (9) và (11)

$$\tau(n) = \sum_{k=1}^{n} \sum_{s=0}^{k-1} \frac{(-1)^s (k-s)^{n-1}}{s! (k-s-1)!}. \tag{12}$$

Chúng ta hãy biểu thị $k-s$ bằng $t$; thì $1 \leqslant t \leqslant n$. Đối với $t$ cố định trong tổng kép (12), $s$ có thể thay đổi từ 0 đến $n-t$. Thu thập các hệ số của $t^{n-1}$, chúng ta có thể sử dụng công thức (12) để chuyển nó về dạng

$$\tau(n) = \sum_{t=1}^{n} \left( \sum_{s=0}^{n-t} \frac{(-1)^s}{s!} \right) \frac{t^{n-1}}{(t-1)!}.$$

⟦folio 8⟧

Các số $c_{n,k}$, vốn có ý nghĩa tổ hợp rõ ràng, bất ngờ xuất hiện trong một đại số bài toán gắn liền với các đa thức.

Đặt $x^{(1)} = x, x^{(2)} = x (x-1), x^{(3)} = x (x-1)(x-2)$, v.v. Các đa thức 1, $x^{(1)}, x^{(2)}, \dots, x^{(n)}$ có bậc 0, 1, 2, ..., $n$ tương ứng. Do đó, bất kỳ đa thức bậc nào $x$ không cao hơn $n$ đều có thể được biểu diễn duy nhất dưới dạng tổng của các đa thức này (với một số hệ số). Đặc biệt,

$$x^n = a_{n,1}x^{(1)} + a_{n,2}x^{(2)} + \dots + a_{n,n}x^{(n)}$$

(13)

Đối với một số số $a_{n,k}$, $(n \geqslant 1, 1 \leqslant k \leqslant n)$. Đối với $k > n$ chúng tôi đặt $a_{n,k} = 0$. Hóa ra $a_{n,k} = c_{n,k}$. Hãy chứng minh điều đó.

Đặt $x = 1$ trong (13), chúng ta thu được $a_{n,1} = 1 = c_{n,1}$. Nếu $k > 1$ và $n = 1$ thì $a_{1,k} = 0 = c_{1,k}$. Bây giờ hãy đặt $k > 1$ và $n > 1$.

$$x^n = \sum_{k=1}^{n} a_{n,k} x^{(k)} = x \cdot x^{n-1} = x \cdot \sum_{i=1}^{n-1} a_{n-1,i} x^{(i)} = \sum_{i=1}^{n-1} a_{n-1,i} x^{(i)} \left[ (x-i) + i \right] =$$

$$= \sum_{i=1}^{n-1} a_{n-1,i} \left[ x^{(i)} (x-i) + ix^{(i)} \right] = \sum_{i=1}^{n-1} a_{n-1,i} \left[ x^{(i+1)} + ix^{(i)} \right] = \sum_{i=1}^{n-1} a_{n-1,i} x^{(i+1)} +$$

$$+ \sum_{i=1}^{n-1} a_{n-1,i} ix^{(i)}$$

So sánh các hệ số tại $x^{(k)}$, ta thu được $a_{n,k} = a_{n-1,k-1} + k \cdot a_{n-1,k}$. Như trên, nó tuân theo $a_{n,k} = c_{n,k}$ cho tất cả $n, k$.

Luật pháp không có nó. Chứng minh đẳng thức:

$$\tau(n-1) = \sum_{t=0}^{n-1} (-1)^t C_{n-1}^t \tau(n-t).$$
