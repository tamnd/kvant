---
id: 1970-10-margulis-mordkovich-radunskiy-reshaya-neravenstvo-s-parametrom-214ec59c
issue: kvant_1970_10
year: 1970
number: "10"
title: Giải một bất phương trình có tham số...
authors:
  - Маргулис А. Я.
  - Мордкович А. Г.
  - Радунский Б. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 55
page_last: 61
page_labels: 53-59
tag: 3JN9
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 902a1430d5e97c9ce8cfdcb978afa7e7059ac262f01719ae81eb7368570b33f3
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1970/10/articles/10_margulis-mordkovich-radunskiy-reshaya-neravenstvo-s-parametrom-214ec59c.md
source_content_sha256: 532b7243d436ece7ff876473d88fa0bbf53fc9c46b0ac7b99432a42b7c547864
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦folio 53⟧

1. KHẢO SÁT KỸ LƯỠNG MỌI TRƯỜNG HỢP

Giả sử cần giải theo $x$ bất phương trình bậc nhất sau:

$$\frac{3ax + 4}{3a + 9} < \frac{x}{a + 3} + \frac{3a - 5}{3a - 9}.$$

Tưởng chừng còn gì đơn giản hơn? Theo quy tắc quen thuộc ở trường, ta chuyển tất cả các hạng chứa $x$ sang vế trái của bất phương trình, còn các hạng tự do sang vế phải:

$$\frac{3ax}{3a + 9} - \frac{x}{a + 3} < \frac{3a - 5}{3a - 9} + \frac{4}{3a + 9},$$

và rút gọn bất phương trình thu được:

$$\frac{a - 1}{a + 3} x < \frac{a^2 - 1}{a^2 - 9}.$$

(1)

Bây giờ chỉ còn «đơn giản» là chia cả hai vế của bất phương trình cho hệ số của ẩn.

Nhưng chính ở bước này — khi chia cả hai vế của bất phương trình (1) cho hệ số của ẩn — cần hết sức cẩn thận, nếu bất phương trình chứa tham số.

Bất phương trình có tham số thực chất là một tập hợp các bất phương trình, mỗi bất phương trình trong đó nhận được từ bất phương trình đã cho khi tham số có một giá trị cụ thể. Hãy hình dung một người bạn đề nghị bạn giải một bất phương trình có tham số, còn bản thân người ấy nghĩ đến một giá trị số cụ thể của tham số. Bạn không biết giá trị đã nghĩ đến, và nhiệm vụ của bạn là không để bị bất ngờ, khảo sát kỹ lưỡng mọi trường hợp có thể xảy ra. Sau khi bạn đã giải bất phương trình, và người bạn

cho bạn biết giá trị tham số mà người ấy đã nghĩ đến, bạn phải tìm trong lời giải của mình trường hợp ứng đúng với giá trị đó.

Trở lại ví dụ của chúng ta. Có thể có 4 trường hợp:

1) một hoặc cả hai vế của bất phương trình không có nghĩa;
2) hệ số của ẩn bằng không;
3) hệ số của ẩn dương;
4) hệ số của ẩn âm.

Trường hợp thứ nhất xảy ra khi $a = \pm 3$. Với các giá trị này của tham số, dĩ nhiên, bất phương trình (1) không có nghiệm.

Trường hợp thứ hai xảy ra khi $a = 1$. Với giá trị này của tham số, bất phương trình (1) có dạng $0 \cdot x < 0$ và hiển nhiên không có nghiệm.

Trường hợp thứ ba xảy ra khi $a < -3$ hoặc khi $a > 1$, $a \neq 3$. Chia cả hai vế của bất phương trình (1) cho số dương $\frac{a - 1}{a + 3}$, ta được:

$$x < \frac{a + 1}{a - 3}.$$

Trường hợp thứ tư xảy ra khi $-3 < a < 1$. Chia cả hai vế của bất đẳng thức (1) cho số âm $\frac{a - 1}{a + 3}$, ta được: $x > \frac{a + 1}{a - 3}$.

Gộp các kết quả đã nhận được, ta viết

Đáp số: nếu $a = 1$, $a = \pm 3$, thì không có nghiệm;

nếu $a < -3$, $1 < a < 3$, $a > 3$, thì

$$x < \frac{a + 1}{a - 3};$$

⟦folio 54⟧

nếu $-3 < a < 1$, thì $x > \frac{a+1}{a-3}$.

Đáp số trên chứa nghiệm của bất đẳng thức (1) đối với mọi giá trị của tham số. Chính điều đó là mục tiêu chủ yếu khi giải bất đẳng thức có tham số.

Sử dụng hình 1, giải bất đẳng thức $\cos x \geq a$ và chứng minh rằng đáp án là:
nếu $a \leq -1$, thì $-\infty < x < \infty$;
nếu $-1 < a < 1$, thì $m_1 + 2k\pi \leq x \leq m_2 + 2k\pi$,
trong đó $m_1 = -\arccos a$, $m_2 = \arccos a$;
nếu $a = 1$, thì $x = 2k\pi$;
nếu $a > 1$, thì không có nghiệm.
($k = 0, \pm 1, \dots$)

2. ĐỪNG VỘI KẾT LUẬN

Xét thêm một ví dụ đơn giản. Giải bất đẳng thức $\sqrt{x} > a$. Rất dễ muốn viết $x > a^2$ và khẳng định rằng biểu thức này chứa tất cả các nghiệm của bất đẳng thức. Nhưng không nên vội kết luận khi giải bất đẳng thức có tham số: bởi vì $a$ có thể nhỏ hơn không; khi đó nghiệm của bất đẳng thức $\sqrt{x} > a$ là mọi giá trị không âm của $x$; nếu $a \geq 0$, thì việc bình phương hai vế của bất đẳng thức $\sqrt{x} > a$ là một phép biến đổi tương đương; thực hiện nó, ta được $x > a^2$.

Đáp số: nếu $a < 0$, thì $x \geq 0$;
nếu $a \geq 0$, thì $x > a^2$.

Bây giờ chuyển sang xét các ví dụ phức tạp hơn.

Ví dụ 1. Giải bất đẳng thức $\sqrt{x^2 + x} < a - x$. (2)

Lời giải. Miền giá trị cho phép của ẩn được xác định bởi bất đẳng thức $x^2 + x \geq 0$. Ngoài ra, rõ ràng rằng nếu $a - x \leq 0$, thì bất đẳng thức (2) không có nghiệm, vì vậy ta chỉ xét tia $a - x > 0$. Nhưng khi điều kiện
$$\begin{cases} x^2 + x \geq 0, \\ a - x > 0 \end{cases}$$ (3)

được thỏa mãn, cả hai vế của bất đẳng thức (2) có thể được bình phương (điều này sẽ không dẫn đến xuất hiện nghiệm ngoại lai). Sau khi bình phương và thu gọn các hạng tử đồng dạng, ta được:
$$ (1+2a)x < a^2. $$
(4)

Bất đẳng thức (4) có các nghiệm sau:

$$ \text{ nếu } a = -\frac{1}{2}, $$
$$ \text{ thì } -\infty < x < \infty; $$
$$ \text{ nếu } a > -\frac{1}{2}, \text{ thì } x < \frac{a^2}{1+2a}; $$
$$ \text{ nếu } a < -\frac{1}{2}, \text{ thì } x > \frac{a^2}{1+2a}. $$

Nhưng không nên vội kết luận và cho rằng như vậy đã tìm được nghiệm của bất đẳng thức (2). Từ các nghiệm tìm được của bất đẳng thức (4) cần chọn ra những nghiệm thỏa mãn các điều kiện (3). Để thuận tiện cho công việc tiếp theo, ta giải theo $x$ hệ bất đẳng thức (3) với mọi giá trị của $a$.

Bất đẳng thức thứ nhất của hệ (3) có nghiệm $x \leq -1$ hoặc $x \geq 0$. Bất đẳng thức thứ hai có nghiệm $x < a$. Các lập luận tiếp theo phụ thuộc vào vị trí của số $a$ so với các số $-1$ và $0$.

Xét các trường hợp $a \leq -1$, $-1 < a \leq 0$, $a > 0$, ta nhận được các nghiệm sau đây của hệ (3):

a) nếu $a \leq -1$, thì $x < a$;
b) nếu $-1 < a \leq 0$, thì $x \leq -1$;
b) nếu $a > 0$, thì $x \leq -1$ hoặc $0 \leq x < a$.

Bây giờ, trong các nghiệm của bất phương trình (4) tìm được ở trên, ta chọn những nghiệm thỏa mãn các điều kiện vừa nhận được $a$), $6$), $b$). Đó chính là các nghiệm của bất phương trình ban đầu (2).

Khi $a = -\frac{1}{2}$, mọi số thực đều thỏa mãn bất phương trình (4). Điều kiện (6) buộc ta chỉ xét các giá trị $x \leq -1$. Vậy, nếu $a = -\frac{1}{2}$, thì bất phương trình (2) có các nghiệm: $x \leq -1$.

Với $a > -\frac{1}{2}$ bất đẳng thức (4) có nghiệm $x < \frac{a^2}{1+2a}$. Xét, theo các điều kiện (6) và (b), hai trường hợp:

$$ -\frac{1}{2} < a \leq 0 \text{ và } a > 0. $$

Trong trường hợp thứ nhất, ta cần tìm tất cả $x$ thỏa mãn hệ bất đẳng thức $x \leq -1$ và $x < \frac{a}{1+2a}$. Do đó, các giá trị $x \leq -1$.

Vậy, nếu $-\frac{1}{2} < a \leq 0$, thì bất đẳng thức (2) có nghiệm $x \leq -1$.

Trong trường hợp thứ hai, tức là khi $a > 0$, ta cần lấy những $x$ thỏa mãn một trong các hệ bất đẳng thức:

$$ \begin{cases} x < \frac{a^2}{1+2a}, \\ x \leq -1, \end{cases} $$
$$ \begin{cases} x < \frac{a^2}{1+2a}, \\ 0 \leq x < a. \end{cases} $$

Hệ thứ nhất trong các hệ này có nghiệm $x \leq -1$. Để giải hệ thứ hai, cần so sánh các số $a$ và $\frac{a^2}{1+2a}$. Ta lập hiệu $a - \frac{a^2}{1+2a} = \frac{a(a+1)}{1+2a}$.

Rõ ràng, khi $a > 0$ hiệu này dương, do đó $\frac{a^2}{1+2a} < a$. Vậy hệ thứ hai có các nghiệm sau: $0 \leq x < \frac{a^2}{1+2a}$.

Vậy, nếu $a > 0$, thì bất đẳng thức (2) có các nghiệm $x \leq -1$;
$$ 0 \leq x < \frac{a^2}{1+2a}. $$

Khi $a < -\frac{1}{2}$ bất đẳng thức (4) có các nghiệm $x > \frac{a^2}{1+2a}$. Xét, theo các điều kiện (6) và (b), hai trường hợp:

$$ a \leq -1 \text{ và } -1 < a < -\frac{1}{2}. $$

⟦folio 56⟧

Trong trường hợp thứ nhất, ta cần giải hệ bất đẳng thức sau:
$$\begin{cases} x > \frac{a^2}{1+2a}, \\ x < a. \end{cases}$$

Nhưng từ đẳng thức (5) suy ra rằng khi $a \leq -1$ thì đúng bất đẳng thức $a \leq \frac{a^2}{1+2a}$, vì vậy hệ vô nghiệm. Do đó, nếu $a \leq -1$, thì bất đẳng thức (2) vô nghiệm.

Trong trường hợp thứ hai, tức là khi $-1 < a < -\frac{1}{2}$, ta cần giải hệ bất đẳng thức sau:
$$\begin{cases} x > \frac{a^2}{1+2a}, \\ x \leq -1. \end{cases}$$

So sánh các số $\frac{a^2}{1+2a}$ và $-1$, bằng cách lập hiệu
$$\frac{a^2}{1+2a} - (-1) = \frac{(a+1)^2}{1+2a}.$$

Khi $-1 < a < -\frac{1}{2}$ hiệu này âm, do đó $\frac{a^2}{1+2a} < -1$.

Nhưng khi đó hệ bất đẳng thức cuối cùng có các nghiệm sau:
$$\frac{a^2}{1+2a} < x \leq -1.$$

Đó là các nghiệm của bất đẳng thức (2) trong trường hợp $-1 < a < -\frac{1}{2}$.

Gộp các kết quả đã thu được, ta viết

Đáp số: nếu $a \leq -1$, thì vô nghiệm;

nếu $-1 < a < -\frac{1}{2}$, thì
$$\frac{a^2}{1+2a} < x \leq -1;$$
nếu $-\frac{1}{2} \leq a \leq 0$, thì $x \leq -1;$
nếu $a > 0$, thì $x \leq -1;$
$0 \leq x < \frac{a^2}{1+2a}$.

3. HÃY CẨN THẬN

Ví dụ 2. Giải bất đẳng thức
$$\frac{1}{x} + ax > 1.$$

Lời giải. Đưa bất đẳng thức về dạng
$$\frac{ax^2 - x + 1}{x} > 0.$$ (6)

Phân tích tử số thành nhân tử, trước hết tìm các nghiệm của nó:
$$x_1 = \frac{1 + \sqrt{1-4a}}{2a};$$
$$x_2 = \frac{1 - \sqrt{1-4a}}{2a}.$$

Ở đây cần cẩn thận để không bỏ sót trường hợp biệt thức của tam thức bậc hai âm.

Điều này xảy ra khi $a > \frac{1}{4}$. Nhưng khi đó $ax^2 - x + 1 > 0$ với mọi $x$ và do đó bất đẳng thức (6) trong trường hợp này có nghiệm $x > 0$.

Với $a = \frac{1}{4}$, $x_1 = x_2 = 2$, và bất đẳng thức (6) có thể viết lại như sau:
$$\frac{(x - 2)^2}{4x} > 0.$$

Sau đó bất đẳng thức có nghiệm $0 < x < 2$, $x > 2$.

Bây giờ giả sử $a < \frac{1}{4}$. Khi đó bất đẳng thức (6) biến đổi thành dạng
$$\frac{a(x - x_1)(x - x_2)}{x} > 0$$ (7)

và ta nhận thấy rằng cần phân biệt hai trường hợp: $a > 0$ hoặc $a < 0$ (trường hợp $a = 0$ được xét).

Nếu $0 < a < \frac{1}{4}$, thì bất đẳng thức (7) có dạng
$$\frac{(x - x_1)(x - x_2)}{x} < 0,$$
từ đó (có tính đến rằng khi $a < 0$ $x_1 < 0 < x_2$) suy ra $x < x_1; 0 < x < x_2$.

⟦folio 57⟧

Khi $a=0$ bất đẳng thức ban đầu có dạng
$$\frac{1}{x} > 1.$$
Giải bất đẳng thức này, ta được:
$$0 < x < 1.$$
Gộp tất cả các kết quả đã nhận được, ta viết
Đáp số: nếu $a < 0$, thì $x < \frac{1 + \sqrt{1-4a}}{2a}$ hoặc $0 < x < \frac{1 - \sqrt{1-4a}}{2a}$;
nếu $a=0$, thì $0 < x < 1$;
nếu $0 < a < \frac{1}{4}$, thì $x > \frac{1 + \sqrt{1-4a}}{2a}$, hoặc $\frac{1 - \sqrt{1-4a}}{2a} > x > 0$;
nếu $a = \frac{1}{4}$, thì $0 < x < 2$, hoặc $x > 2$;
nếu $a > \frac{1}{4}$, thì $x > 0$.

Ví dụ 3. Giải bất đẳng thức $\log_{1/2}(x^2 - 2x + a) > -3$.
Lời giải. Bất đẳng thức đã cho tương đương với hệ bất đẳng thức
$$\begin{cases} x^2 - 2x + a > 0, \\ x^2 - 2x + a < 8. \end{cases}$$
Viết lại hệ như sau:
$$\begin{cases} (x-1)^2 > 1-a, \\ (x-1)^2 < 9-a. \end{cases}$$
Đặt $x-1$ là $y$ và viết lại hệ thu được dưới dạng chuỗi bất đẳng thức:
$$1-a < y^2 < 9-a.$$
Nếu chú ý, ta thấy rằng khi $a \geq 9$ chuỗi này vô nghiệm, còn khi $a > 1$ bất đẳng thức $y^2 > 1-a$ đúng với mọi $y$, vì vậy nghiệm của chuỗi trong trường hợp $1 < a < 9$ sẽ là nghiệm của bất đẳng thức $y^2 < 9-a$, tức là $-\sqrt{9-a} < y < \sqrt{9-a}$.
Cuối cùng, nếu $a \leq 1$, thì giải chuỗi, ta được
$$-\sqrt{9-a} < y < -\sqrt{1-a};$$
$$\sqrt{1-a} < y < \sqrt{9-a}.$$

Đáp số: nếu $a \leq 1$, thì
$$1 - \sqrt{9-a} < x < 1 - \sqrt{1-a},$$
hoặc $1 + \sqrt{1-a} < x < 1 + \sqrt{9-a}$;
nếu $1 < a < 9$, thì
$$1 - \sqrt{9-a} < x < 1 + \sqrt{9-a};$$
nếu $a \geq 9$, thì không có nghiệm.
Ví dụ 4. Giải bất đẳng thức
$$\cos x - \frac{1}{\cos x} \leq a (a > 0).$$
(khoa Vật lí, ĐHTH Moskva, năm 1966.)
Lời giải. Trước hết nhận thấy rằng mọi $x$ mà $\cos x > 0$ đều thỏa mãn bất đẳng thức (khi đó $\frac{1}{\cos x} \geq 1 \geq \cos x$).
Bây giờ ta sẽ tìm các nghiệm $x$ còn lại, với $\cos x < 0$.
Trong trường hợp này, bất đẳng thức (8) có dạng
$$\cos^2 x - a \cos x - 1 \geq 0,$$
từ đó suy ra $\cos x \geq \frac{a + \sqrt{a^2 + 4}}{2}$ hoặc $\cos x \leq \frac{a - \sqrt{a^2 + 4}}{2}$. Vì ta đang xét trường hợp $\cos x < 0$, nên bất đẳng thức $\cos x \geq \frac{a + \sqrt{a^2 + 4}}{2}$ bị loại bỏ.

Vậy, $\cos x \leq \frac{a - \sqrt{a^2 + 4}}{2}$. Chúng ta không được bỏ qua sự thật rằng với một số giá trị của $a$, số $\frac{a - \sqrt{a^2 + 4}}{2}$ có thể nhỏ hơn -1 (vì trong trường hợp này bất đẳng thức cuối cùng sẽ không có nghiệm). Vì vậy, chúng ta còn phải so sánh các số $\frac{a - \sqrt{a^2 + 4}}{2}$ và -1. Dễ thấy rằng $\frac{a - \sqrt{a^2 + 4}}{2} > -1$ (hãy kiểm tra điều này!).

Đáp số: $-\frac{\pi}{2} + 2k\pi < x < \frac{\pi}{2} + 2k\pi$, hoặc arccos $\frac{a - \sqrt{a^2 + 4}}{2} + 2k\pi \leq x \leq 2\pi - \frac{\pi}{2}$
arccos $\frac{a - \sqrt{a^2 + 4}}{2} + 2k\pi (k = 0, \pm 1, \pm 2, \ldots)$

⟦folio 58⟧

4. ĐỪNG QUÊN PHƯƠNG PHÁP ĐỒ THỊ

Ví dụ 5. Giải bất đẳng thức
$$2\sqrt{x+a} > x+1.$$

Lời giải. TXĐ được xác định bởi bất đẳng thức $x+a \geq 0$. Tương ứng, trên hình 2 nửa mặt phẳng phía dưới đường thẳng $x+a=0$ được tô màu xanh lam (miền không thể có nghiệm). Dấu của vế phải của bất đẳng thức (9) chưa biết, không thể bình phương hai vế của bất đẳng thức. Xét hai trường hợp:
1. $x+1 < 0$ hoặc $x < -1$ — bất đẳng thức (9) tự động đúng. Trên hình 2 phần TXĐ tương ứng được tô màu cam và ký hiệu là I.
2. $x+1 \geq 0$ hoặc $x \geq -1$. Trong trường hợp này có thể bình phương hai vế của bất đẳng thức (9). Ta được $4(x+a) > x^2+2x+1$, suy ra $a > \frac{1}{4}(x-1)^2$. Trên hình 2 parabol $a = \frac{1}{4}(x-1)^2$ được vẽ bằng nét đứt và chỉ với $x \geq -1$ (phù hợp với điều kiện của trường hợp 2). Miền,

trong đó $a > \frac{1}{4}(x-1)^2$ trên hình 2 cũng được tô màu cam, nhưng ký hiệu là II.

Do đó, miền được tô màu cam trên hình 2 cho tập các cặp $(x; a)$ thỏa mãn bất đẳng thức (9). Để tìm nghiệm của bất đẳng thức (9) khi đã cho giá trị $a$, ta kẻ qua điểm tương ứng trên trục $Oa$ một đường thẳng song song với trục $Ox$. Hoành độ các điểm của đoạn thẳng này nằm trong «miền màu cam» sẽ là các nghiệm của bất đẳng thức (9) ứng với giá trị đã chọn của tham số. Để viết đáp án, ta cần viết lại các phương trình của các đường biên thẳng của «miền màu cam» như sau: $x = -a$; $x = 1 - 2\sqrt{a}$ (phương trình nhánh parabol trên đoạn $-1 \leq x \leq 1$); $x = 1 + 2\sqrt{a}$ (phương trình nhánh parabol khi $x \geq 1$). Các phương trình $x = 1 - 2\sqrt{a}$ và $x = 1 + 2\sqrt{a}$ được suy ra từ phương trình $a = \frac{1}{4}(x-1)^2$.

Đáp án: nếu $a \leq 0$, thì không có nghiệm;

nếu $0 < a \leq 1$, thì
$$1 - 2\sqrt{a} < x < 1 + 2\sqrt{a};$$
nếu $a > 1$, thì $-a \leq x < 1 + 2\sqrt{a}$.

Nhận xét rằng với phương pháp giải như vậy, $x$ và $a$ hoàn toàn bình đẳng, và chỉ để trình bày đáp số mới phải «phân chia vai trò» giữa chúng *).

Ví dụ 6. Giải bất phương trình
$$\log_{\sqrt{2a}}(a + 2x - x^2) < 2.$$

Lời giải. ĐKXĐ của bất phương trình được xác định bởi các điều kiện sau:
$a > 0$, $a \neq \frac{1}{2}$, $a > x^2 - 2x$.

*) Ví dụ 5 lấy từ sách của M. I. Bashmakov và Z. I. Borevich «Các bài toán thi toán học» (Nhà xuất bản ĐHTH Leningrad, 1968). Trong sách này, bạn đọc sẽ tìm thấy một số ví dụ về bất phương trình có tham số, nhiều trong số đó được giải bằng phương pháp đồ thị.

⟦folio 59⟧

Hình 3.

Trên hình 3, các miền được tô màu xanh và các đường được vẽ nét đứt là những miền và đường mà mọi điểm của chúng không thuộc ĐKXĐ và vì thế không thể là nghiệm của bất phương trình (10).

Nếu $0 < a < \frac{1}{2}$, thì bất phương trình (10) được biến đổi thành dạng
$$a + 2x - x^2 > (\sqrt{2a})^2,$$
suy ra
$$a < -x^2 + 2x.$$

Vậy trong trường hợp này, bất phương trình (10) được thỏa mãn bởi những cặp $(x; a)$ là nghiệm của hệ sau:

$$\begin{cases} a > 0, \\ a < \frac{1}{2}, \\ a > x^2 - 2x, \\ a < -x^2 + 2x. \end{cases}$$

Các nghiệm này lấp đầy miền I trên hình 3.

Nếu $a > \frac{1}{2}$, thì bất đẳng thức (10) được biến đổi thành dạng
$$a + 2x - x^2 < (\sqrt{2a})^2,$$
từ đó $a > -x^2 + 2x.$

Vậy, trong trường hợp này bất đẳng thức (10) được thỏa mãn bởi những cặp $(x; a)$ là nghiệm của hệ sau:

$$\begin{cases} a > \frac{1}{2}, \\ a > x^2 - 2x, \\ a < -x^2 + 2x. \end{cases}$$

Các nghiệm này lấp đầy miền II trên hình 3.

Đáp số: nếu $a \leq 0$ hoặc $a = \frac{1}{2}$, thì không có nghiệm;

nếu $0 < a < \frac{1}{2}$, thì
$$1 - \sqrt{1 - a} < x < 1 + \sqrt{1 - a};$$
nếu $\frac{1}{2} < a \leq 1$, thì
$$1 - \sqrt{1 + a} < x < 1 + \sqrt{1 - a};$$
$$1 + \sqrt{1 - a} < x < 1 + \sqrt{1 + a};$$
nếu $a > 1$, thì
$$1 - \sqrt{1 + a} < x < 1 + \sqrt{1 + a}.$$

5. KẾT LUẬN

Khi giải bất đẳng thức có tham số, hãy khảo sát kỹ tất cả các trường hợp, đừng vội kết luận, hãy cẩn thận và đừng quên phương pháp đồ thị.

Bài tập

Giải theo $x$ các bất đẳng thức sau:

1. $2x + 3(ax - 8) + \frac{x}{3} < 4(x + \frac{1}{2}) - 5.$
2. $\frac{2ax + 3}{5x - 4a} < 4.$
3. $\left| \frac{ax - 5}{3} + x \right| < 3.$
4. $\sqrt{x} - \sqrt{x - 1} > a.$
5. $tg x + ctg x \leq a (a > 0).$
6. $\lg^2 x - 2a \lg x - a^2 + 2 > 0.$
7. $\sqrt{a^2 - x^2} + \sqrt{2ax - x^2} > a$ (dùng phương pháp đồ thị).
8. $\log_x(x - a) > 2$ (dùng phương pháp đồ thị).
