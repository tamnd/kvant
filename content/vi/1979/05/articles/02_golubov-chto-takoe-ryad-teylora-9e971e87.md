---
id: 1979-5-golubov-chto-takoe-ryad-teylora-9e971e87
issue: kvant_1979_5
year: 1979
number: "5"
title: Chuỗi Taylor là gì?
authors:
  - Голубов Б. И.
rubric: osnovnye-stati
page_first: 4
page_last: 9
page_labels: 2, 4, 5, 6, 7
tag: GRIE
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 4354381c73dca461143030374cf6cf7ed1c1249404219a92593891fdd581e9d1
prompt_sha256: draft-1
translated_from: content/ru/1979/05/articles/02_golubov-chto-takoe-ryad-teylora-9e971e87.md
source_content_sha256: 3b3d444a7304e8bfa436d15d37274f9db9f2563448572a3d299b21367477d170
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

B. Golubov

Chuỗi Taylor là gì?

Tên tuổi nhà toán học người Anh Brooke Taylor đã đi vào lịch sử toán học nhờ khám phá mà ông thực hiện vào năm 1715, ở tuổi 29. Khám phá này là gì? Chúng tôi sẽ cố gắng nói với bạn về điều này.

Nhìn vào hình ảnh 1-3. Chúng hiển thị biểu đồ của các hàm $y = e^x$, $y = \frac{1}{1+x}$ và $y = \ln(1+x)$.

Số 1 trong mỗi hình này biểu thị tiếp tuyến của đồ thị tương ứng tại điểm $x = 0$, tức là đồ thị của một hàm tuyến tính nào đó $y = ax + b$ (kiểm tra xem chính xác hàm tương ứng sẽ là gì -

các điểm $y = 1+x$, $y = 1-x$ và $y = x$). Số 2 trong mỗi hình này biểu thị tiếp tuyến của một tam giác vuông $y = ax^2 + bx + c$, tại điểm $x = 0$ liền kề với đồ thị của hàm tương ứng “gần” hơn tất cả các tam giác vuông khác. Chính xác hơn, chúng ta đang nói về những hình tam giác vuông sao cho tại điểm $x = 0$ trùng với các hàm tương ứng cùng với thứ tự thứ nhất và thứ hai tùy ý của chúng. Trong những trường hợp này, đồ thị của các tam giác vuông này được cho là có tiếp tuyến bậc hai với các đồ thị tương ứng (kiểm tra xem các tam giác vuông tương ứng $y = 1+x + \frac{x^2}{2}$, $y = 1-x + x^2$ và $y = x - \frac{x^2}{2}$) có như vậy không.

Cuối cùng, số 3 trong Hình 1-3 thể hiện đồ thị của hàm số $y = ax^3 + bx^2 + cx + d$, có tiếp tuyến bậc ba với đồ thị của các đường cong tương ứng tại điểm $x = 0$ (có thể dễ dàng nói rằng đây là

⟦folio 4⟧

Trong bài viết này, chúng ta sẽ thu được chuỗi Taylor cho hàm $y=\sin x$, $y=\cos x$, $y=e^x$ và $y=\ln(1+\dot{x})$.

Thông tin cần thiết từ việc phân tích

Trước hết, chúng ta cần công thức Newton-Leibniz:

$$\int_a^b f(x) \, dx = F(b) - F(a),$$

trong đó hàm $f$ liên tục trên khoảng $[a; b]$ và hàm $F$ là nguyên hàm của nó trên khoảng này.

Hơn nữa, từ ý nghĩa hình học của tích phân, ta suy ra rằng $\int_a^b f(x) \, dx \geq 0$ nếu $f(x) \geq 0$ nằm trên $[a; b]$ (Hình 5). Từ đó dễ dàng suy ra rằng nếu hai hàm liên tục trên khoảng $[a; b]$ thỏa mãn bất đẳng thức $f(x) \leq g(x)$, thì $\int_a^b f(x) \, dx \leq \int_a^b g(x) \, dx$, tức là các bất đẳng thức kết nối các hàm bất quy tắc, có thể được giải thích, thu được các bất đẳng thức cùng dấu.

Cuối cùng, chúng ta cần sự bình đẳng

$$\lim_{n \to \infty} \frac{x^n}{n!} = 0,$$

trong đó $x$ là số thực bất kỳ. Hãy chứng minh điều đó. Cho $x$, chúng ta hãy tìm một số tự nhiên $N$ sao cho $\frac{|x|}{N+1} \leq y=f(x)$

Cơm. 5. $S = \int_a^b f(x) \, dx$.

$\leq \frac{1}{2}$. Khi đó với mọi $n > N$ các bất đẳng thức sẽ được thỏa mãn

$$0 \leq \frac{|x|^n}{n!} = \frac{|x|}{1} \cdot \frac{|x|}{2} \cdot \dots \cdot \frac{|x|}{N} \times \times \frac{|x|}{N+1} \cdot \dots \cdot \frac{|x|}{n} \leq \frac{|x|^N}{N!} \cdot \left(\frac{1}{2}\right)^{n-N} = \frac{|x|^N \cdot 2^N}{N!} \cdot 2^{-n}.$$

Vì $N$ là cố định nên với $n \to \infty$ giới hạn của dãy ở vế phải của các bất đẳng thức này bằng 0. Do đó đẳng thức (1) theo sau.

Biểu diễn chuỗi Taylor của hàm $\sin x$ và cos $x$

Hãy để $x > 0$ hoạt động. Sau đó, tích phân bất đẳng thức $\cos t \leq 1$ trên đoạn $[0; x]$, ta thu được điều đó

$$\int_0^x \cos t \, dt \leq \int_0^x 1 \, dt.$$

Nhưng vì sin $t$ là nguyên hàm của cos $t$ và $t$ là nguyên hàm của 1, nên bất đẳng thức trước đó dựa trên công thức Newton-Leibniz có thể được viết là $sin x \leq x$. Bất đẳng thức này có thể được viết ngay lập tức, nhưng chúng tôi muốn giải thích nguyên tắc thu được các bất đẳng thức tiếp theo và do đó đã đưa ra chứng minh của nó.

Tích phân bất đẳng thức $\sin t \leq t$ trên đoạn $[0; x]$, ta thu được điều đó

$$\int_0^x \sin t \, dt \leq \int_0^x t \, dt.$$

Vì hàm - cos $t$ là nguyên hàm của sin $t$ và $\frac{t^2}{2}$ là nguyên hàm của $t$, nên bất đẳng thức trước đó dựa trên công thức Newton-Leibniz có dạng

$$1 - cos x \leq \frac{x^2}{2} \text{ или } cos x \geq 1 - \frac{x^2}{2}.$$

Bộ tích phân là một bất đẳng thức dọc theo đoạn $[0; x]$ và một lần nữa sử dụng công thức Newton-Leibniz để đi đến bất đẳng thức $\sin x \geq x - \frac{x^3}{3!}$.

⟦folio 5⟧

Tiếp tục quá trình tích phân tuần tự (và sử dụng phương pháp quy nạp toán học), dễ dàng chứng minh được các bất đẳng thức

$$\cos x \leq 1 - \frac{x^2}{2!} + \dots + \frac{x^{4n}}{(4n)!},$$

$$\sin x \leq x - \frac{x^3}{3!} + \dots + \frac{x^{4n+1}}{(4n+1)!},$$

$$\cos x \geq 1 - \frac{x^2}{2!} + \dots - \frac{x^{4n+2}}{(4n+2)!},$$

$$\sin x \geq x - \frac{x^3}{3!} + \dots - \frac{x^{4n+3}}{(4n+3)!},$$

ở đâu $n = 0, 1, \dots, x > 0$.

Kết hợp bất đẳng thức thứ nhất và thứ ba (2), ta thu được

$$1 - \frac{x^2}{2!} + \dots - \frac{x^{4n+2}}{(4n+2)!} \leq \cos x \leq 1 - \frac{x^2}{2!} + \dots + \frac{x^{4n}}{(4n)!}.$$

Đa thức bên trái có thể được coi là giá trị gần đúng của $\cos x$ với một nhược điểm và đa thức bên phải có thể được coi là giá trị gần đúng của $\cos x$ với một giá trị đã biết (Hình 6). Nhưng hiệu giữa đa thức bên phải và bên trái so với bất đẳng thức (3) bằng $\frac{x^{4n+2}}{(4n+2)!}$, và tại $n \to \infty$ nó có xu hướng bằng 0 dựa trên (1). Đó là lý do tại sao

$$\cos x = \lim_{n \to \infty} \left( 1 - \frac{x^2}{2!} + \dots - \frac{x^{4n+2}}{(4n+2)!} \right) = \lim_{n \to \infty} \left( 1 - \frac{x^2}{2!} + \dots + \frac{x^{4n}}{(4n)!} \right).$$

Kết quả được viết dưới dạng

$$\cos x = 1 - \frac{x^2}{2!} + \dots + \frac{(-1)^n}{(2n)!} x^{2n} + \dots.$$

Vế phải của đẳng thức này được gọi là $prdom Teйлора функции$ $\cos x$.

Khi chứng minh bất đẳng thức (3), và do đó, đẳng thức (4), chúng ta giả sử rằng $x > 0$. Nhưng chúng cũng hợp lệ cho $x < 0$ do tính chẵn lẻ của tất cả các hàm có trong chúng. Cuối cùng, chúng có thể dễ dàng được xác minh cho $x = 0$ và do đó hợp lệ cho tất cả $x$ thực.

Tương tự, với $x > 0$ từ (2) ta có

$$\sin x = \lim_{n \to \infty} \left( x - \frac{x^3}{3!} + \dots - \frac{x^{4n+3}}{(4n+3)!} \right) = \lim_{n \to \infty} \left( x - \frac{x^3}{3!} + \dots + \frac{x^{4n+1}}{(4n+1)!} \right).$$

Kết quả này được viết dưới dạng

$$\sin x = x - \frac{x^3}{3!} + \dots + \frac{(-1)^n}{(2n+1)!} x^{2n+1} + \dots,$$

và biểu thức ở vế phải của đẳng thức này được gọi là $prdom Teйлора функции$ $\sin x$.

Cuối cùng, hãy lưu ý rằng đẳng thức (5) vẫn hợp lệ với $x \leq 0$ do tính chẵn lẻ của tất cả các hàm có trong nó.

Chuỗi chức năng mở rộng chuỗi Taylor $e^x$

Người ta biết rằng $(e^x)' = e^x$, từ đó suy ra rằng đối với bất kỳ cách xây dựng $C$ nào, hàm $e^x + C$ là nguyên hàm của $e^x$. Ngoài ra, điều quan trọng là chúng ta phải biết rằng $e > 1$ ($e = 2,718\dots$).

Vì $e > 1$, thì $1 \leq e^t \leq e^a$ cho tất cả $t \in [0; a]$. Giải thích sự bất đẳng thức này dọc theo đoạn $[0; x]$, trong đó $0 \leq x \leq a$, chúng ta thu được $x \leq e^x - 1 \leq e^ax$ hoặc $1 + x \leq e^x \leq 1 + e^ax$. Những bất đẳng thức này cũng có thể được tích phân trên đoạn $[0; x]$ bằng cách trước tiên thay thế $x$ trong chúng bằng $t$. Kết quả là chúng tôi nhận được

$$x + \frac{x^2}{2!} \leq e^x - 1 \leq x + e^a \frac{x^2}{2!},$$

Cơm. 6.

⟦folio 6⟧

Ily

$$1 + x + \frac{x^2}{2!} \leq e^x \leq 1 + x + e^a \frac{x^2}{2!} (0 \leq x \leq a).$$

Tiếp tục quá trình tích phân tuần tự, ta thu được các bất đẳng thức

$$1 + x + \frac{x^2}{2!} + \dots + \frac{x^n}{n!} \leq e^x \leq 1 + x + \frac{x^2}{2!} + \dots + \frac{x^{n-1}}{(n-1)!} + \frac{x^n}{n!} e^a,$$

ở đâu $n=0, 1, \dots, 0 \leq x \leq a$.

Do đó, đối với mỗi giá trị $x$ từ đoạn $[0; a]$, giá trị gần đúng của hàm $e^x$ có ​​phần thiếu và phần thừa sẽ thu được dưới dạng đa thức bậc $n$. Hiệu giữa đa thức bên phải và bên trái trong bất đẳng thức (6) bằng $(e^a - 1) \frac{x^n}{n!}$; tại $n \to \infty$ nó có xu hướng về 0 dựa trên (1). Vì $a$ là một số dương tùy ý, nên từ bất đẳng thức (6) nó suy ra với mọi $x \geq 0$

$$e^x = \lim_{n \to \infty} \left( 1 + x + \frac{x^2}{2!} + \dots + \frac{x^n}{n!} \right).$$

Hãy viết điều này như một sự bình đẳng

$$e^x = 1 + x + \frac{x^2}{2!} + \frac{x^3}{3!} + \dots + \frac{x^n}{n!} + \dots$$

(7)

Biểu thức ở vế phải của (7) được gọi là chuỗi Taylor của hàm $e^x$.

Bài tập không phải 1. Chứng minh đẳng thức (7) cho $x < 0$. (Gợi ý không. Hãy lợi dụng sự thật là $e^x < 1$ đi cùng với $x < 0$).

Khai triển hàm số chuỗi Taylor $\ln(1+x)$

Hàm $\ln(1+x)$ được định nghĩa là $\log_e(1+x)$, tức là cơ số của logarit là $e$. Vì $\ln(1+x)^\prime = \frac{1}{1+x}$ với mọi $x > -1$, nên với $\frac{1}{1+x}$ hàm số $\ln(1+x) + C$ là nguyên hàm trên khoảng $-1; +\infty$ [ với mọi số được xây dựng $C$. Chúng tôi sẽ sử dụng điều này dưới đây. Lưu ý rằng với $t \geq 0$ bất đẳng thức

$$1 - t + \dots + t^{2n-2} - t^{2n-1} \leq \frac{1}{1+t} \leq 1 - t + \dots + t^{2n-2} - t^{2n-1} \leq \frac{1}{1+t} \leq 1 - t + \dots + t^{2n-2} - t^{2n-1} + t^{2n}.$$

(8)

(Hãy tự biện minh cho họ.)

Giải thích các bất đẳng thức (8) dọc theo đoạn $[0; x]$, trong đó $x \geq 0$ và sử dụng công thức Newton–Leibniz, chúng ta thu được các bất đẳng thức

$$x - \frac{x^2}{2} + \dots - \frac{x^{2n}}{2n} \leq \ln(1+x) \leq x - \frac{x^2}{2} + \dots - \frac{x^{2n}}{2n} + \frac{x^{2n+1}}{2n+1},$$

(9)

trong đó $x \geq 0$. Hiệu giữa đa thức bên phải và bên trái là $\frac{x^{2n+1}}{2n+1}$. Nếu $0 \leq x \leq 1$, thì nó có xu hướng về 0 tại $n \to \infty$. Đó là lý do tại sao

$$\ln(1+x) = x - \frac{x^2}{2} + \dots + \frac{(-1)^{n+1}}{n} x^n + \dots$$

(10)

cho $0 \leq x \leq 1$.

Phương trình không phải là 2. Hãy đảm bảo rằng đẳng thức này cũng đúng với $-1 < x < 0$. (Gợi ý không. Hãy tận dụng thực tế là tại $t > -1$ $1 - t + \dots + t^{2n-2} - t^{2n-1} \leq \frac{1}{1+t} \leq 1 - t + \dots + t^{2n-2} - t^{2n-1} + t^{2n}$ nếu $\lambda > \frac{1}{1+t}$.)

Biểu thức ở vế phải của đẳng thức (10) được gọi là chuỗi Taylor của hàm $\ln(1+x)$.

Khi tìm chuỗi Taylor của các hàm $\sin x$, $\cos x, e^x$ và $\ln(1+x)$, chúng tôi đã sử dụng nhiều kỹ thuật nhân tạo khác nhau. Trên thực tế, có một phương pháp thống nhất để tìm chuỗi Taylor của hàm số - nó dựa trên sự vi phân tuần tự của nó. Chúng ta có thể làm quen với anh ấy trong cuốn sách tuyệt vời của A. Ya. Khinchin “Tám bài giảng về phân tích toán học” (M., “Nauka”, 1977).

Kết quả đánh giá có ý nghĩa gì?

Các ước tính cho các hàm $\sin x$, $\cos x, e^x$ và $\ln(1+x)$ thu được ở trên cho phép chúng ta tính toán chúng tại một điểm tùy ý với bất kỳ độ chính xác cần thiết nào.

⟦folio 7⟧

Ví dụ: nếu chúng ta cần tìm giá trị của hàm sin x tại điểm $x \in \left[ 0; \frac{\pi}{2} \right]$ với sai số không vượt quá số $\varepsilon > 0$, thì trước tiên chúng ta tìm một số nguyên $n \geqslant 0$ sao cho $x^{4n+1}/(4n+1)! < \varepsilon$. Khi đó, giá trị của các đa thức từ bất đẳng thức (2) tại điểm $x$ cho ta giá trị của sin x lên đến $\varepsilon$, một có nhược điểm, một có chênh lệch. Tính toán giá trị tại các điểm khác bằng cách sử dụng công thức rút gọn tính chất tính toán tại các điểm của đoạn $\left[ 0; \frac{\pi}{2} \right]$.

Một chút lịch sử

Tác phẩm của B. Taylor “Phương pháp tăng trưởng trực tiếp và nghịch đảo” được xuất bản năm 1715 tại Luân Đôn bằng tiếng Latinh. Taylor là người cùng thời với Newton và Leibniz - người sáng lập ra phép tính vi phân và tích phân. Phương pháp của ông dựa trên công thức Newton, đưa ra biểu diễn gần đúng của một hàm trên một đoạn cho trước dưới dạng đa thức bậc $n$, trùng với hàm đã cho tại $n+1$ các điểm cách đều của đoạn đó (bao gồm cả các điểm cuối của nó). Taylor đã thực hiện quá trình chuyển đổi sang khúc dạo đầu trong công thức Newton cho $n \rightarrow \infty$ theo cách hoàn toàn mang tính công thức mà không cần lo lắng về việc biện minh cho việc chuyển đoạn đến giới hạn.

Nhân dịp này, nhà khoa học và sử gia toán học nổi tiếng người Đức F. Klein đã viết: “Về bản chất, Taylor ở đây xử lý các vi phân (vi phân) nhiều hơn, có thể nói, một cách phù phiếm hơn những người theo Leibniz từng làm; Thật thú vị khi lưu ý rằng ông ấy vẫn… trước mắt Newton, quá chệch khỏi phương pháp giới hạn mà ông ấy đã sử dụng” *).

Kết quả là, nhiều nhà toán học từ các quốc gia khác nhau đã tham gia chứng minh phương pháp Taylor: Lagrange, Cauchy, Schlömlch, Roche, Peano và những người khác. Nhờ nỗ lực của họ, phương pháp biểu diễn hàm số bằng chuỗi Taylor và phương pháp biểu diễn gần đúng hàm số bằng đa thức đã được chứng minh đầy đủ.

Hiện nay, khái niệm chuỗi Taylor là một trong những khái niệm chính trong tính toán toán học. Chuỗi Taylor hoặc các tổng hữu hạn của chúng được sử dụng khi cần biểu diễn chính xác hoặc gần đúng các hàm biến thiên.

Bài tập
1. Tận hưởng sự bình đẳng
$$\text{arctg} x = \int_0^x \frac{dt}{1+t^2} (-\infty < x < \infty),$$

chứng minh rằng với $x \geqslant 0$ và $n = 0,1, \dots$ các bất đẳng thức sau là đúng:
$$x - \frac{x^3}{3} + \dots - \frac{x^{4n+3}}{4n+3} \leqslant \text{arctg} x \leqslant x - \frac{x^3}{3} + \dots + \frac{x^{4n+1}}{4n+1}.$$

Nếu $x < 0$ thì trong các bất đẳng thức này, dấu “<” phải được thay bằng “>”.

2. Chứng minh rằng với $-1 < x \leqslant 1$ đẳng thức
$$\text{arctg} x = x - \frac{x^3}{3} + \frac{x^5}{5} - \frac{x^7}{7} + \dots$$

3. Chứng minh đẳng thức $\frac{\pi}{4} = 1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \dots$

4. Chứng minh đẳng thức $\ln 2 = 1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \dots$

5. Chứng minh đẳng thức
$$e^{-1} = \frac{1}{2!} - \frac{1}{3!} + \frac{1}{4!} - \dots$$

6. Chứng minh đẳng thức
$$(1+x)^{\alpha} = 1 + \alpha x + \frac{\alpha(\alpha-1)}{2!} x^2 + \dots + \frac{\alpha(\alpha-1)}{n!} x^n + \dots,$$
ở đâu $-1 < x \leqslant 1, -\infty < \alpha < +\infty$.
