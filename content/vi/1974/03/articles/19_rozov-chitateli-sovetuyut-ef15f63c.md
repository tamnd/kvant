---
id: 1974-3-rozov-chitateli-sovetuyut-ef15f63c
issue: kvant_1974_3
year: 1974
number: "3"
title: Lời khuyên của độc giả
authors:
  - Розов Н. Х.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 50
page_last: 53
page_labels: 48-51
tag: CTEA
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 3cff449ed2cdeaedc57fb714fea44cf96b948659a8acd668c2f889ebb2765b6c
prompt_sha256: draft-1
translated_from: content/ru/1974/03/articles/19_rozov-chitateli-sovetuyut-ef15f63c.md
source_content_sha256: 712e6e2f929fa971a1b6c3a945008ee5e5abef44c15de03cc938cbeeb0d9ee0f
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 48⟧

Lời khuyên của độc giả
N. Kh. Rozov

Trong thư xã luận chung «Kvant» có nhiều thư thảo luận về một số vấn đề lý thuyết nhất định trong khóa học toán và vật lý ở trường, đề xuất các kỹ thuật lời giải thuộc một số loại bài toán, đồng thời chứa các nhận xét và quan sát cá nhân có tính chất phương pháp luận. Mặc dù các thông điệp và bài toán do độc giả cung cấp không phải lúc nào cũng mới và độc đáo, nhưng theo quan điểm của chúng tôi, một số vấn đề nêu ra trong các bức thư sẽ được người nộp đơn quan tâm.

Vì vậy, hôm nay bài viết bắt buộc đã được xuất bản trong “Hội thảo dành cho người nộp đơn”: các biên tập viên đang xuất bản tuyển tập các tài liệu về toán học, được biên soạn theo ý tưởng và gợi ý từ thư của độc giả. Chúng tôi hy vọng rằng những bộ sưu tập như thế này sẽ mang lại những trải nghiệm và ý tưởng kịp thời.

Trong các kỳ thi tuyển sinh, họ thường đưa ra bài toán thuộc loại này: tìm hiểu (không sử dụng bảng) số nào lớn hơn: $\log_a M$ hoặc $\log_b N$, trong đó $a, b, M, N$ là các số đã cho và tất nhiên là $a > 0, a \neq 1, b > 0, b \neq 1, M > 0, N > 0$. Trong “Hội thảo dành cho người nộp đơn” (xem «Kvant», 1972, Số 3) các ví dụ về lời giải tương tự như bài toán đã được đưa ra. Độc giả V.A. Grubyan (Berezniki, vùng Perm) thu hút sự chú ý đến khả năng sử dụng ví dụ sau để so sánh độ lớn logarit của hai số.

Bài toán lời giải khá đơn giản nếu bạn có thể tìm thấy một số nguyên $k$ sao cho, chẳng hạn,

$$\log_a M < k, k < \log_b N.$$

Vì vậy, trường hợp thú vị nhất là khi

$$k - 1 < \log_a M < k,$$
$$k - 1 < \log_b N < k.$$

Trong trường hợp này, người ta nên cố gắng chọn một số tự nhiên $n$ sao cho giữa $n$ và $n \log_b N$ có ​​một số nguyên nhất định $p$. Việc lựa chọn số $n$ với thuộc tính được chỉ định được thực hiện bằng các phép thử liên tiếp.

Ví dụ 1. So sánh $\log_3 4$ và $\log_7 10$.

Thật dễ dàng để kiểm tra $1 < \log_3 4 < 2, 1 < \log_7 10 < 2$, nhưng từ đây không rõ logarit được đề xuất nào lớn hơn. Hãy lấy $n = 2$; chúng tôi nhận được $2 \log_3 4 = \log_3 16, 2 \log_7 10 = \log_7 100$. Vì $2 < \log_3 16 < 3$ và $2 < \log_7 100 < 3$ (hãy đảm bảo điều này!), nên giá trị $n = 2$ không có thuộc tính bắt buộc. Tương tự, chúng tôi kiểm tra xem giá trị $n = 3$ có phù hợp với chúng tôi hay không.

Với $n = 4$ chúng ta nhận được:

$$4 \log_3 4 = \log_3 256, 4 \log_7 10 = \log_7 1000.$$

Vì $3^5 = 243, 3^6 = 729$ và $7^4 = 2401, 7^5 = 16807$, nên $5 < 4 \log_3 4 < 6, 4 < 4 \log_7 10 < 5$, nên giá trị $n = 4$ có thuộc tính bắt buộc (vai trò của $p$ do số 5 đảm nhận). Từ đây chúng ta có được điều đó

$$\log_3 4 > \log_7 10.$$

Ví dụ 2. Trong hai số, số nào lớn hơn: $\log_{\sqrt{2}} \frac{6}{11}$ hay $\log_{2/5}$?

Người ta xác minh trực tiếp rằng cả hai số đều nằm trong khoảng từ -2 đến -1. Lấy $n = 2$ chúng ta nhận được

⟦folio 49⟧

$$2 \log_2 \frac{6}{11} = -\log_2 \frac{11^4}{6^4},$$

cái gì có thể dễ dàng tìm thấy ở đâu
$$-4 < 2 \log_2 \frac{6}{11} < -3.$$

Ở phía bên kia,
$$2 \log_2 \pi = \log_2 \pi^2,$$
và một phép tính đơn giản cho thấy rằng
$$-3 < \log_2 \pi^2 < -2.$$

Vì vậy, $\log_2 \frac{6}{11} < \log_2 \pi$.

Tất nhiên, số lần thử cần thiết để chọn $n$ cần thiết sẽ khác nhau tùy theo các bài toán khác nhau (và có thể lớn), nhưng điều quan trọng là sẽ luôn có $n$ như vậy. Cụ thể, chúng ta sẽ chứng minh các mệnh đề sau, làm cơ sở lý thuyết cho kỹ thuật được sử dụng: nếu $\log_a M \neq \log_b N$, thì tồn tại một số tự nhiên $n$ sao cho giữa $n \log_a M$ và $n \log_b N$ có một số nguyên.

Đặt $\alpha = \log_a M$ và $\beta = \log_b N$ và $\alpha \neq \beta$. Ví dụ: giả sử rằng $\alpha > \beta$ (trường hợp $\alpha < \beta$ được xử lý tương tự). Khi đó $\alpha - \beta$ là một số dương và do đó tồn tại một số tự nhiên $n$ sao cho phân số $1/n$ nhỏ hơn số dương này: $\frac{1}{n} < \alpha - \beta$ hoặc $n\alpha - n\beta > 1$. Nhưng bất đẳng thức cuối cùng có nghĩa là các số $n\alpha = n \log_a M$ và $n\beta = n \log_b N$ khác nhau nhiều hơn một, nghĩa là phải có một số nguyên nào đó giữa các số này.

Để kết luận, chúng ta hãy nhớ lại một phương pháp chung để xác định dấu bất đẳng thức giữa các số (hoặc biểu thức) $\alpha$ và $\beta$: điều quan trọng là chọn một số (biểu thức) $\gamma$, ví dụ: $\alpha < \gamma$ và đồng thời $\gamma < \beta$. Cách được mô tả ở trên về cơ bản là một biến thể của phương pháp này: vai trò của $\gamma$ ở đây được thực hiện bởi số $p/n$.

Bài tập

1. (MSU, Khoa Tâm lý học, 1969). Chứng minh rằng $\log_3 7 > \log_7 27$ mà không cần dùng bảng.

2. (MSU, Khoa Ngữ văn, 1969). Chứng minh rằng $\log_5 14 > \log_7 18$ mà không cần dùng bảng.

3. (MSU, Khoa Kinh tế, 1972). Không sử dụng bảng, hãy xác định giá trị nào lớn hơn: $\log_4 60$ hoặc $\log_3 30$.

Khi chứng minh các đẳng thức đại số và đặc biệt là các đẳng thức
$$a^n - b^n = (a - b) (a^{n-1} + a^{n-2} b + \dots + ab^{n-2} + b^{n-1}),$$
trong đó $n$ là số tự nhiên và $a$ và $b$ là số thực. Học sinh lớp 10 L. Davitidze (làng Shukhevi, Liên Xô thuộc Gruzia) mời độc giả của tạp chí sử dụng nhận dạng này (bằng cách chứng minh) cho lời giải bài tập tiếp theo.

4. Chứng minh; rằng nếu $m$ là số tự nhiên và $c \ge 1$ thì bất đẳng thức đúng
$$m^2 - c + 1 + m^2 - c - 1 < 2m^2 - c.$$
Lời giải của một số bài toán có thể được đơn giản hóa đáng kể nếu chúng ta áp dụng phép thay thế lượng giác thành công. Trong một số trường hợp, tính linh hoạt của các công thức lượng giác cho phép tạo điều kiện thuận lợi cho các phép biến đổi, loại bỏ các căn thức và thu được các biểu thức đơn giản và dễ hiểu hơn. Vấn đề này được giải quyết trong thư của độc giả V.V. Pikan (Kyiv) và D.P. Dorozhin (Pavlovskaya Sloboda, vùng Moscow).

Bản chất của phép thay thế lượng giác là biến $x$, có trong các biểu thức xuất hiện trong điều kiện xác định, được coi là giá trị của một hàm lượng giác nào đó của góc biến phụ $φ$, và họ cố gắng chọn hàm này để các biểu thức đề xuất được viết gọn hơn.

Ví dụ 3: Tính giá trị của biểu thức
$$A = \left[ \frac{(x^2 + a^2)^{-1/4} + (x^2 - a^2)^{-1/4}}{(x^2 + a^2)^{-1/4} - (x^2 - a^2)^{-1/4}} \right]^{-3} \tag{1}$$

⟦folio 50⟧

$$npu x = a \left( \frac{m^2 + n^2}{2mn} \right)^{1/2},$$
$$\varepsilon de a < 0, n > m > 0.$$

Vì giá trị $x$ mà chúng ta quan tâm là âm nên trước hết chúng ta đơn giản hóa biểu thức (1), giả sử rằng $x < a$. (Lưu ý rằng (1) chỉ có ý nghĩa với $|x| > |a|$ và chứng minh rằng giá trị $x$ nêu trong điều kiện không thỏa mãn bất đẳng thức này!). Sự hiện diện của nhị thức $x^2 \pm a^2$ gợi ý ý tưởng đặt $x = a \mathrm{tg} \varphi$, cho phép chúng ta viết các nhị thức này trong thủ tục:

$$x^2 + a^2 = \frac{a^2}{\cos^2 \varphi},$$
$$x^2 - a^2 = -\frac{a^2 \cos 2\varphi}{\cos^2 \varphi}.$$

Chúng tôi áp dụng thay thế lượng giác cho Pozny:

$$x = a \mathrm{tg} \varphi, \frac{\pi}{4} < \varphi < \frac{\pi}{2}.$$

Các phép biến đổi đơn giản chứng tỏ rằng

$$A = \left( \frac{\sqrt{4 - \cos 2\varphi} - 1}{\sqrt{4 - \cos 2\varphi} + 1} \right)^3, \frac{\pi}{4} < \varphi < \frac{\pi}{2}.$$

Hơn nữa, có thể dễ dàng tính được rằng nếu $x = a \mathrm{tg} \varphi = a \left( \frac{m^2 + n^2}{2mn} \right)^{1/2}$ thì

$$\cos 2\varphi = \frac{1 - \mathrm{tg}^2 \varphi}{1 + \mathrm{tg}^2 \varphi} = -\frac{(n - m)^2}{(n + m)^2},$$

và sau đó ở giá trị được chỉ định $x$

$$A = \frac{(4n^2 - m^2) \sqrt{n^2 - m^2} - (4n^2 - 3m^2)n}{m^3}.$$

Ví dụ 4: Giải phương trình

$$\sqrt{1 + \sqrt{1 - x^2}} \left[ \sqrt{(1 + x)^3} - \sqrt{(1 - x)^3} \right] = 2 + \sqrt{1 - x^2}.$$

Phạm vi giá trị được chấp nhận cho phương trình này là tập hợp $|x| \leq 1$. Nếu chúng ta sử dụng phép thay thế lượng giác $x = \cos \varphi, 0 \leq \varphi \leq \pi$ thì dễ dàng kiểm tra được rằng từ căn thức chúng ta có thể sử dụng nguyên lý dạng

$$\left( \cos \frac{\varphi}{2} + \sin \frac{\varphi}{2} \right) \cdot 2\sqrt{2} \times \left( \cos^3 \frac{\varphi}{2} - \sin^3 \frac{\varphi}{2} \right) = 2 + \sin \varphi.$$

Từ đây lần lượt ta thu được phương trình

$$\sqrt{2} \left( 1 + \frac{1}{2} \sin \varphi \right) \cos \varphi = 1 + \frac{1}{2} \sin \varphi$$

hoặc

$$\left( \sqrt{2} \cos \varphi - 1 \right) \left( 1 + \frac{1}{2} \sin \varphi \right) = 0,$$

chỉ được kiểm soát ở $\cos \varphi = \sqrt{2}/2$. Do đó, phương trình ban đầu có nghiệm $x = \sqrt{2}/2$.

Ví dụ 5. Tìm giá trị nhỏ nhất và lớn nhất của hàm

$$y = \frac{1 + x^4}{(1 + x^2)^2}.$$

Đối số của hàm này chạy trên tất cả các số thực và do đó chúng ta có thể coi $x$ là giá trị tiếp tuyến của góc biến phụ $\varphi$, thay đổi trong khoảng $-\pi/2 < \varphi < \pi/2$. Phép thay thế lượng giác $x = \mathrm{tg} \varphi, -\pi/2 < \varphi < \pi/2$ cho phép, cùng với hàm (2), nghiên cứu hàm

$$y = 1 - \frac{1}{2} \sin^2 2\varphi$$

tại $-\pi/2 < \varphi < \pi/2$. Vì $0 \leq \sin^2 2\varphi \leq 1$, rõ ràng giá trị nhỏ nhất của hàm (3) bằng $\frac{1}{2}$ và đạt được ở $\varphi = -\pi/4$ và $\varphi = \pi/4$, còn giá trị lớn nhất bằng 1 và đạt được ở $\varphi = 0$. Từ đây, chúng ta kết luận rằng giá trị nhỏ nhất của hàm (2) bằng $\frac{1}{2}$ và đạt được ở $x = -1$ và $x = 1$, còn giá trị lớn nhất bằng 1 và đạt được ở $x = 0$.

Lưu ý rằng các ví dụ về cách sử dụng phép thay thế lượng giác cho phương trình lời giải đã được thảo luận

⟦folio 51⟧

đã xem trong “Hội thảo dành cho người đăng ký” (xem «Kvant», 1971, số 1).

Tại sợi
5. Đơn giản hóa một biểu thức
$$B = \frac{(m+x)^{3/2} - (m-x)^{3/2}}{(m+x)^{3/2} + (m-x)^{3/2}}, \quad m > 0.$$

6. Tìm giá trị lớn nhất và lớn nhất của hàm
$$y = \frac{(x+1)^2}{x^2+1}.$$

Học sinh lớp 9 V. Olasyuk (Tulup, vùng Irkutsk) mời độc giả của tạp chí giải câu bài toán sau.

7. Mặt giấy thể hiện các trục tọa độ và một parabol là đồ thị của hàm số $y = x^2$. Tuy nhiên, độ dài tương tự được sử dụng khi xây dựng biểu đồ để đo khoảng cách dọc theo các trục không được chỉ định. Làm thế nào để khôi phục độ dài đơn này?

***

Tại lời giải của phương trình, việc thay thế thành công ẩn số thường cho phép chúng ta xem xét một phương trình đơn giản hơn thay vì phương trình ban đầu phức tạp. Tuy nhiên, việc “nhìn thấy” nhu cầu thay thế không phải lúc nào cũng dễ dàng và chỉ có thực tế, kinh nghiệm tích lũy được và ý nghĩa của những thay thế phổ biến nhất mới có thể giúp ích ở đây.

Độc giả của chúng tôi I.A. Gavrilov (Fryazino, vùng Moscow) trong thư của mình đã nhắc lại một kiểu thay thế cho phương trình đại số lời giải. Những sự thay thế này có thể được gọi một cách chính đáng là “sự đối xứng”.

Chúng ta hãy chỉ ra “sự đối xứng” bao gồm những gì bằng cách sử dụng ví dụ về hai phương trình bậc bốn.

Nếu phương trình
$$(x-a)^4 + (x-b)^4 = c$$
nhập một ẩn số mới thay vì ẩn số $x$
$$y = x - \frac{a+b}{2},$$
Chúng ta có thể thu được một phương trình hai bậc hai.

Rõ ràng rằng với bất kỳ $x$ nào thì số $x - \frac{a+b}{2}$ là trung điểm của đoạn có các điểm cuối tại $x-a$ và $x-b$. Nếu trong phương trình
$$(x-a)(x-b)(x-c)(x-d) = p$$ (4)
nếu bất kỳ cặp số nào $a, b, c, d$ trùng nhau, ví dụ: $a-b = c-d$, thì thay thế số chưa biết
$$y = x - \frac{b+c}{2}$$
dẫn đến phương trình hai phương trình (hãy kiểm tra xem!). Lưu ý rằng nếu $a-b = c-d$, thì nhị thức $x-a - \frac{b+c}{2}$ phục vụ một số “trọng tâm” của các thừa số $x-a, x-b, x-c, x-d$, điều này được thấy rõ từ cách giải thích hình học của các phương trình này theo các điểm trên trục số (xem hình).

Ý tưởng “đối xứng” được áp dụng thành công cho lời giải và một số phương trình đại số và hệ phương trình khác.

Tại sợi
8. Giải phương trình $x^2 + \frac{25x^2}{(x+5)^2} = 11$.
9. Giải phương trình
$$4\sqrt{x} + \sqrt{4-x^2} = 4+x.$$
10. Tìm hệ phương trình lời giải thực
$$\begin{align*}
(x+y-2)^4 + (x+y)^4 &= 82, \\
x^2-y^2 &= 3.
\end{align*}$$
11. (UDN, 1973). Giải phương trình
$$(x^2-4x)^2 + 2(x-2)^2 = 43.$$
12. (UDN, 1973). Giải phương trình
$$\frac{5}{x^2+3x} + \frac{6}{(x+1)(x+2)} = 1.$$
