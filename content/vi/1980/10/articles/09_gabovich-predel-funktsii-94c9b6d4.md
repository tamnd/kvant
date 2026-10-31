---
id: 1980-10-gabovich-predel-funktsii-94c9b6d4
issue: kvant_1980_10
year: 1980
number: "10"
title: Giới hạn chức năng
authors:
  - Габович И. Г.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 42
page_last: 44
page_labels: 40-42
tag: J474
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 1e3af9698786beda4dd9d6378a44e6742b5ad41f0cea42980c89467a6e028cc2
prompt_sha256: draft-1
translated_from: content/ru/1980/10/articles/09_gabovich-predel-funktsii-94c9b6d4.md
source_content_sha256: f3800ae08a98529689b21112f34ea6fc744ef252449c9beaae6a865811267511
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 40⟧

I. Gabovich

Giới hạn chức năng

Khái niệm “giới hạn của hàm số” là một trong những khái niệm quan trọng nhất trong môn toán ở trường. Thông qua đó, “tính liên tục” và “đạo hàm” được xác định.

Chúng tôi xây dựng định nghĩa chính (§ 38 của sổ tay “Đại số và Nguyên tắc Phân tích 9”) theo hai cách.

Đầu tiên trong ngôn ngữ “số học”: số $b$ được gọi là giới hạn của hàm $f$ với $x$ hướng tới $a$ nếu với bất kỳ $\varepsilon > 0$ nào có một $\delta > 0$ sao cho với mọi $x$ thỏa mãn bất đẳng thức kép*)

$$0 < |x - a| < \delta,$$

bất bình đẳng giữ

$$|f(x) - b| < \varepsilon.$$

Để xây dựng định nghĩa về giới hạn của hàm số bằng ngôn ngữ “hình học”, chúng tôi giới thiệu một thuật ngữ không có trong sách giáo khoa. Như đã biết, lân cận của điểm $a \in R$ được gọi là khoảng có dạng $]a - \delta; a + \delta[$, trong đó $\delta$ là một số dương tùy ý. Chúng ta hãy lấy lân cận bị thủng của điểm $a \in R$ làm lân cận của nó, từ đó bản thân điểm $a$ bị loại ra (“bị thủng”), tức là một tập hợp “bị hỏng” có dạng $]a - \delta; a[U]a; a + \delta[$. Bây giờ định nghĩa giới hạn của hàm có thể được hình thành như sau: số $b$ được gọi là giới hạn của hàm $f$ với $x$ hướng tới $a$ nếu có

$$*) |x - a| > 0 \iff x \neq a.$$

lân cận $B$ của điểm $b$ có lân cận bị thủng $A$ của điểm $a$ sao cho $f(A) \subset B$ (Hình 1).

Vì vậy, không nhất thiết bất đẳng thức (2) cũng đúng với $x = a$. Hàm $f$ tại điểm $a$ thậm chí có thể không được xác định - điều này không ảnh hưởng đến giới hạn của nó theo bất kỳ cách nào vì $x$ có xu hướng $a$. Ví dụ: hàm $\frac{x^2 - 9}{x - 3}$ không được xác định tại $x = +3$, nhưng tồn tại giới hạn của nó tại $x \rightarrow +3$.

Một ví dụ tổng quát hơn: hàm $\frac{\Delta f(x_0)}{\Delta x}$ luôn không được xác định tại $\Delta x = 0$, nhưng giới hạn của nó tại $\Delta x \rightarrow 0$ “thường” tồn tại (nó được gọi là hàm tùy ý $f$ tại điểm $x_0$).

Tuy nhiên, bất đẳng thức “rất thường xuyên” (2) cũng được thỏa mãn với $x = a$; nếu cùng lúc $b = f(a)$ thì hàm $f$ được gọi là liên tục tại điểm $a$.

Nếu một tuyên bố có dạng

$$\lim_{x \rightarrow 1} f(x) = b$$

chứng minh kết quả vô thời hạn từ định nghĩa, thì bất kỳ $\varepsilon > 0$ nào cũng cần phải tìm ra $\delta > 0$ tương ứng hoặc ít nhất phải chứng minh rằng $\delta > 0$ đó tồn tại.

Ví dụ 1. Hãy chứng minh rằng

$$\lim_{x \rightarrow \frac{1}{7}} (3 - 2x) = \frac{19}{7}.$$

Đối với những “tác nhân” này $(f(x) = 3 - 2x, a = \frac{1}{7}, b = \frac{19}{7})$ bất đẳng thức (2) có dạng

$$|3 - 2x - \frac{19}{7}| < \varepsilon.$$

Để tìm $\delta$ cần tìm, hãy “tiết lộ” bất đẳng thức (4) và xây dựng

⟦folio 41⟧

xia “trần trụi” $x$. Bất đẳng thức (4) tương đương với bất đẳng thức

$$\left| -2x + \frac{2}{7} \right| < \varepsilon,$$
$$-\varepsilon < -2x + \frac{2}{7} < \varepsilon,$$
$$-\frac{2}{7} - \varepsilon < -2x < -\frac{2}{7} + \varepsilon,$$
$$\frac{1}{7} + \frac{\varepsilon}{2} > x > \frac{1}{7} - \frac{\varepsilon}{2},$$
$$\frac{1}{7} - \frac{\varepsilon}{2} < x < \frac{1}{7} + \frac{\varepsilon}{2}.$$

Bây giờ chúng ta “thu gọn” bất đẳng thức (5) và nhận được bất đẳng thức có dạng (1):

$$-\frac{\varepsilon}{2} < x - \frac{1}{7} < \frac{\varepsilon}{2},$$
$$|x - \frac{1}{7}| < \frac{\varepsilon}{2}.$$

Chúng tôi đang nhắm đủ. Do đó, đối với $\delta = \frac{\varepsilon}{2}$, (4) suy ra từ $0 < |x - \frac{1}{7}| < \delta$. Trong ví dụ này, bất đẳng thức (2) = (4) cũng đúng với $x = a$; vì $\delta$ rõ ràng người ta có thể lấy bất kỳ số nào từ $] 0; \frac{\varepsilon}{2}]$.

Tuy nhiên, nhận xét thứ hai là đúng và có tính chất chung: nếu đối với một số $\varepsilon_0 > 0$ một số $\delta_0 > 0$ là phù hợp, tức là từ $0 < |x - a| < \delta_0$ (6)

chảy ra

$$|f(x) - b| < \varepsilon_0,$$

thì tất nhiên, bất kỳ $\delta \in ]0; \delta_0[$ nào cũng phù hợp cho $\varepsilon_0 > 0$ này: nếu $0 < |x - a| < \delta$, thì từ $\delta < \delta_0$ theo sau (6), và do đó (7).

Ví dụ 2. Hãy chứng minh rằng $\lim_{x \to -2} \frac{5}{x} = -\frac{5}{2}$.

Bất đẳng thức (2) trong trường hợp này có dạng

$$\left| \frac{5}{x} - \left( -\frac{5}{2} \right) \right| < \varepsilon.$$

Chúng ta hãy đi cùng một con đường một lần nữa. Bất đẳng thức (8) tương đương với bất đẳng thức

$$\left| \frac{5}{x} + \frac{5}{2} \right| < \varepsilon,$$
$$-\varepsilon < \frac{5}{x} + \frac{5}{2} < \varepsilon,$$
$$-\frac{5}{2} - \varepsilon < \frac{5}{x} < -\frac{5}{2} + \varepsilon.$$

Để đạt được mục tiêu “phơi bày” $x$, chúng ta cần chia từng số hạng thành từng phần của bất đẳng thức kép (9); nhưng điều này chỉ có thể thực hiện được nếu tất cả các phần của bất đẳng thức có cùng dấu, vì tính chất tương ứng của bất đẳng thức từ cho biết: nếu $a < b$ và các số $a, b$ có ​​cùng dấu (viết tắt: $ab > 0$), thì $\frac{1}{a} > \frac{1}{b}$ (chứng minh khẳng định này!). $-\frac{5}{2} - \varepsilon < 0$. Vì vậy, chúng ta cần hai phần còn lại của bất đẳng thức (9) âm. Chỉ cần yêu cầu $-\frac{5}{2} + \varepsilon < 0$ hoặc $\varepsilon < \frac{5}{2}$ là đủ.

Vì vậy, hãy bắt đầu với $\varepsilon < \frac{5}{2}$ (lưu ý địa điểm này - chúng ta sẽ quay lại sau một chút). Khi đó tất cả các phần của bất đẳng thức (9) đều âm. Đó là lý do tại sao

$$\frac{1}{-\frac{5}{2} - \varepsilon} > \frac{x}{5} > \frac{1}{-\frac{5}{2} + \varepsilon},$$
$$\frac{5}{-\frac{5}{2} - \varepsilon} > x > \frac{5}{-\frac{5}{2} + \varepsilon},$$
$$\frac{5}{-\frac{5}{2} + \varepsilon} < x < \frac{5}{-\frac{5}{2} - \varepsilon},$$
$$\frac{10}{-5 + 2\varepsilon} < x < \frac{10}{-5 - 2\varepsilon}.$$

$x$ “để trần.” Bây giờ chúng ta cần thu được từ (10) bất đẳng thức có dạng (1):

$$|x - (-2)| < \delta,$$
$$-\delta < x - (-2) < \delta,$$
$$-2 - \delta < x < -2 + \delta.$$

Từ (10):

$$-2 + \frac{10}{-5 + 2\varepsilon} + 2 < x < -2 +$$
$$+ \frac{10}{-5 - 2\varepsilon} + 2,$$
$$-2 - \frac{4\varepsilon}{5 - 2\varepsilon} < x < -2 + \frac{4\varepsilon}{5 + 2\varepsilon}.$$

Cho đến nay, bất đẳng thức (12) không hoàn toàn có dạng (11). Tại $\varepsilon < \frac{5}{2}$

$$\frac{4\varepsilon}{5 - 2\varepsilon} > \frac{4\varepsilon}{5 + 2\varepsilon}.$$

⟦folio 42⟧

Có nghĩa,

$$-2 - \frac{4\varepsilon}{5-2\varepsilon} < -2 - \frac{4\varepsilon}{5+2\varepsilon}. \tag{13}$$

Hãy giải quyết sự bất bình đẳng (12):

$$-2 - \frac{4\varepsilon}{5+2\varepsilon} < x < -2 + \frac{4\varepsilon}{5+2\varepsilon}. \tag{14}$$

Từ (13) suy ra rằng nếu $x$ thỏa mãn bất đẳng thức (14) thì nó cũng thỏa mãn bất đẳng thức (12) (xem Hình 2). Nhưng (14) đã có dạng (11). Khu công nghiệp (14)

$$|x - (-2)| < \frac{4\varepsilon}{5+2\varepsilon}.$$

Do đó, nếu $\varepsilon < \frac{5}{2}$, thì với $\delta = \frac{4\varepsilon}{5+2\varepsilon}$ từ $0 < |x - (-2)| < \delta$ tuân theo (8).

Nhưng chúng ta cần chứng minh rằng với mọi $\varepsilon > 0$ đều tồn tại một $\delta > 0$ như vậy và chúng ta chỉ chứng minh điều này cho $\varepsilon < \frac{5}{2}$. Tuy nhiên, về bản chất, điều này là đủ, vì đối với $\varepsilon \geq \frac{5}{2}$, $\delta$ cũng sẽ làm như vậy!

Thật vậy, hãy $\varepsilon_1 \geq \frac{5}{2}$; tùy ý $\varepsilon_2 < \frac{5}{2}$ và $\delta_2 = \frac{4\varepsilon_2}{5+2\varepsilon_2}$ đều có thể; theo chứng minh từ

$$0 < |x - (-2)| < \delta_2$$

chảy ra $$\left| \frac{5}{x} - \left( -\frac{5}{2} \right) \right| < \varepsilon_2;$$

nhưng $\varepsilon_2 < \frac{5}{2} \leq \varepsilon_1$; Có nghĩa,

$$\left| \frac{5}{x} - \left( -\frac{5}{2} \right) \right| < \varepsilon_1.$$

Nhận xét này có tính chất chung: hóa ra là chúng ta luôn có thể tìm kiếm $\delta$ không phải tất cả $\varepsilon > 0$, mà tìm mọi số dương $\varepsilon$ nhỏ hơn bất kỳ số dương nào chúng ta chọn.

Tất nhiên, trong ví dụ này, bất đẳng thức (2) = (8) đúng với $x = a$.

Ví dụ 3. Hãy chứng minh rằng

$$\lim_{x \to 0} \left( x \cdot \sin \frac{1}{x} \right) = 0.$$

Hình 2.

Bất đẳng thức (2) trong trường hợp này có dạng

$$|x \cdot \sin \frac{1}{x} - 0| < \varepsilon,$$

$$|x \cdot \sin \frac{1}{x}| < \varepsilon. \tag{15}$$

Nếu trong ví dụ này, chúng ta ngay lập tức đi theo con đường tương tự như trong những ví dụ trước, thì chúng ta đã không đạt được mục tiêu: $x$ chúng ta sẽ không thể “phơi bày”. Do đó, hãy bắt đầu bằng cách “làm trầm trọng thêm” sự bất bình đẳng (15): vì $$\left| \sin \frac{1}{x} \right| \leq 1,$$

$$|x \sin \frac{1}{x}| \leq |x|. \tag{16}$$

Từ (16) suy ra rằng cùng với (15) chỉ cần tìm $\delta$ cho bất đẳng thức $$|x| < \varepsilon.$$ Vì trong trường hợp của chúng ta, bất đẳng thức (1) có dạng $0 < |x| < \delta$, rõ ràng là chúng ta có thể lấy $\varepsilon$ là $\delta$ cần tìm.

Trong ví dụ này, bất đẳng thức (2) = (15) với $x = a = 0$ tất nhiên là không đúng: hàm $x \sin \frac{1}{x}$ cho $x = 0$ không được xác định.

Hãy nhớ lại ví dụ về “làm thô” mà chúng tôi đã sử dụng hai lần - nó thường hữu ích.

Trong các ví dụ mà chúng tôi đã xem xét, việc tìm $\delta$ không tạo ra các hàm lớn; chứng minh khẳng định (3) trực tiếp bằng cách tìm trực tiếp $\delta$ chắc chắn là không thể. Trong những trường hợp như vậy, lý thuyết có thể giúp ích.

Hãy để chúng tôi đưa ra một ví dụ từ lý thuyết “phi trường học”. Định lý cũng đúng: nếu $$\lim_{x \to a} f(x) = 0, \lim_{x \to a} g(x) = 0$$ tồn tại và $$\lim_{x \to a} \frac{f'(x)}{g'(x)},$$ tồn tại thì $u$ $$\lim_{x \to a} \frac{f(x)}{g(x)} u$$ tồn tại

$$\lim_{x \to a} \frac{f(x)}{g(x)} = \lim_{x \to a} \frac{f'(x)}{g'(x)}.$$

Định lý này được gọi là *Quy tắc Lopitania*. Theo quy tắc này:

$$\lim_{x \to 0} \frac{e^x - e^{-x}}{\ln(e - x) + x - 1} =$$

$$= \lim_{x \to 0} \frac{e^x + e^{-x}}{-1 - \frac{1}{e} + 1} = \frac{2}{1 - \frac{1}{e}} = \frac{2e}{e - 1}.$$
