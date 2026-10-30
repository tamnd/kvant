---
id: 1970-12-margulis-mordkovich-radunskiy-esche-raz-ob-uravneniyah-s-parametrami-e4de8adf
issue: kvant_1970_12
year: 1970
number: "12"
title: Một lần nữa về các phương trình có tham số
authors:
  - Маргулис А. Я.
  - Мордкович А. Г.
  - Радунский Б. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 48
page_last: 51
page_labels: 46-49
tag: R1KM
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 57141cd60ba409b6a4e89913038fe66818cd868a59d159edc04a19ebc2f7d54e
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1970/12/articles/08_margulis-mordkovich-radunskiy-esche-raz-ob-uravneniyah-s-parametrami-e4de8adf.md
source_content_sha256: 264645cf41f61b7b2894372529c338d17d0ece6c264a83a11f57bd9ec9c1c051
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦folio 46⟧

MỘT LẦN NỮA VỀ CÁC PHƯƠNG TRÌNH
CÓ THAM SỐ

Các em đã nhiều lần gặp các phương trình và bất phương trình chứa một tham số. Còn nếu có nhiều hơn một tham số thì sao? Tự nhiên có thể chờ đợi rằng số trường hợp cần xét cũng sẽ tăng lên. Không được bỏ sót bất kỳ khả năng nào. Làm thế nào để thực hiện điều đó? Không có phương pháp thống nhất nào phù hợp với mọi phương trình và bất phương trình có tham số. Trong bài này, qua các ví dụ, chúng tôi sẽ chỉ ra cách giải các phương trình có hai tham số.

Dạng tổng quát của phương trình theo $x$ với hai tham số $a, b$ là:

$$F(x; a; b) = 0.$$

(1)

Phương trình (1) với hàm $F$ đã cho, về thực chất, là một tập hợp vô số phương trình, mỗi phương trình được xác định bởi một cặp số có thứ tự $(a; b)$.

Như đã biết, một cặp có thứ tự như vậy có thể được biểu diễn như một điểm trên mặt phẳng tọa độ. Điều này cho phép thiết lập sự tương ứng một-một giữa các phương trình dạng (1) với hàm $F$ đã cho và các điểm của mặt phẳng.

Để làm điều đó, ta đưa vào hệ tọa độ $aOb$ và quy ước rằng với mỗi phương trình dạng (1) tương ứng một điểm của mặt phẳng $aOb$ có tọa độ $(a; b)$, và ngược lại. Ta gọi mặt phẳng này là mặt phẳng tham số. Sự tương ứng như vậy có phần không quen thuộc (phương trình tương ứng với điểm), nhưng nó sẽ giúp ta trong mỗi trường hợp cụ thể hình dung tập giá trị cho phép của các tham số và không bỏ sót trường hợp nào: mỗi điểm của mặt phẳng tham số tương ứng với một phương trình dạng (1) và phải tương ứng với một đáp án xác định.

Ví dụ 1. Giải phương trình

$$\frac{2a + b}{a + x} - \frac{2a - b}{a - x} = \frac{2a}{b}$$

(2)

Lời giải. Nhận thấy ngay rằng khi $b = 0$ phương trình (2) không có nghĩa, tức là với mọi cặp số dạng $(a; 0)$, trong đó $a$ là một số thực bất kỳ, không có nghiệm nào (đường màu đỏ trên hình 1).

Giả sử $b \neq 0$. Tìm ĐKXĐ: $x \neq \pm a$, khử mẫu và thu gọn các hạng tử đồng dạng. Ta được

$$a(x^2 - 2bx + b^2 - a^2) = 0.$$

(3)

Nếu $a = 0$, thì mọi giá trị $x$ đều là nghiệm của phương trình (3). Trong số đó, các giá trị $x = \pm a$, tức là $x = 0$, bị loại đối với phương trình (2).

Vì vậy, với mọi cặp số dạng $(0; b)$, trong đó $b \neq 0$, mọi số trừ 0 đều là nghiệm của phương trình (2) (đường màu xanh lá). Bây giờ giả sử $a \neq 0$. Giải phương trình $x^2 - 2bx + b^2 - a^2 = 0$, ta được $x_1 = b + a$, $x_2 = b - a$.

*) Ở dạng (1), phương trình này là: $$\frac{2a + b}{a + x} - \frac{2a - b}{a - x} - \frac{2a}{b} = 0.$$

⟦folio 47⟧

Có thể coi rằng với mọi $a, b$ khác không, các giá trị tìm được $x_1$ và $x_2$ là nghiệm của phương trình (2) không? Không, có thể xảy ra rằng với một số giá trị của các tham số, $x_1$ hoặc $x_2$ trùng với các giá trị bị cấm $\pm a$.

Vậy còn phải làm rõ khi nào $x_1 = \pm a$ hoặc $x_2 = \pm a$. Nếu $x_1 = a$ hoặc $x_2 = -a$, thì $b = 0$, nhưng ta xét trường hợp $b \neq 0$. Do đó, $x_1 \neq a$, $x_2 \neq -a$.

Giả sử $x_1 = -a$, tức là $b + a = -a$, suy ra $b = -2a$. Nhưng khi đó $x_2 = -3a$. Như vậy, nếu các tham số $a$ và $b$ sao cho $b = -2a$, thì phương trình (2) có nghiệm duy nhất $x = -3a$ (đường màu xanh lam trên hình 1). Giả sử $x_2 = a$, tức là $b - a = a$. Điều này có thể khi $b = 2a$.

Nhưng khi đó $x_1 = 3a$. Do đó, nếu các tham số $a$ và $b$ sao cho $b = 2a$, thì phương trình (2) có một nghiệm duy nhất $x = 3a$ (đường màu vàng).

Tóm lại, ta nhận được đáp án sau:

nếu $b = 0$, $a$ là số thực bất kỳ, thì không có nghiệm;
nếu $b \neq 0$, $a = 0$, thì $x$ là số thực bất kỳ khác không;
nếu $b = -2a$, $b \neq 0$, thì $x = -3a$;
nếu $b = 2a$, $b \neq 0$, thì $x = 3a$;
nếu $a, b \neq 0$, $b \neq \pm 2a$, thì $x_1 = b + a$, $x_2 = b - a$.

Ví dụ 2*). Giải phương trình

$$\sqrt{a^2 - x} + \sqrt{b^2 - x} = a + b.$$

(4)

Lời giải. Miền xác định được xác định bởi hệ bất đẳng thức

$$x \leq a^2, \quad x \leq b^2, \quad \text{hoặc } x \leq \min\{a^2; b^2\}.$$

Vế trái của phương trình (4) không âm, do đó khi $a + b < 0$ phương trình này không thể có nghiệm. Trên hình 2 điều này được biểu thị bằng việc miền nằm dưới đường thẳng $b = -a$ được tô màu hồng.

Bây giờ xét trường hợp $a + b \geq 0$. Sau các biến đổi tương đương, ta được

$$x(a + b)^2 = 0$$

(5)

Xét hai trường hợp:

Trường hợp I: $a + b > 0$. Khi đó $x = 0$. Đồng thời các điều kiện $x \leq a^2$ và $x \leq b^2$ được thỏa mãn tự động, điều không thể nói về điều kiện $x \geq -ab$. Nếu $ab > 0$, thì điều kiện này, rấtindo, được thỏa mãn. Nếu $ab < 0$, thì $-ab > 0$ và $x = 0 < -ab$. Vì vậy trên hình 2 trong các vùng II và III (nơi $a + b > 0$, nhưng $ab < 0$) không có nghiệm. Do đó, $x = 0$ là một nghiệm

*) Ví dụ này được lấy từ cuốn sách của N. P. Antonov và các tác giả khác “Tuyển tập bài toán toán học sơ cấp” (M., “Nauka”, 1969), trong đó nó được giải sai.

⟦folio 48⟧

Hình 2.

của phương trình (4), chỉ khi $a + b > 0$ và $ab \geq 0$, tức là đối với các điểm của góc phần tư thứ nhất của mặt phẳng tham số, kể cả các điểm trên biên của nó (vùng $I$ trên hình 2).

Trường hợp P: $a + b = 0$. Trong trường hợp này phương trình (5) trở thành đồng nhất thức $x \cdot 0 = 0$, nhưng điều đó hoàn toàn không có nghĩa là mọi số thực đều là nghiệm của phương trình ban đầu (4) (hãy tự giải thích vì sao).

Khi $a + b = 0$ ta lần lượt có $b = -a$, $b^2 = a^2$, và phương trình (4) có dạng $2\sqrt{a^2 - x} = 0$, suy ra $x = a^2 = b^2$, và mọi điều kiện ở đây hiển nhiên đều được thỏa mãn. Trên hình 2 đáp số này được ghi bên cạnh đường thẳng màu xanh $b = -a$.

Gộp tất cả các kết quả đã thu được, ta nhận được đáp số:
nếu $a + b > 0$ và $ab \geq 0$, thì $x = 0$;
nếu $a + b = 0$, thì $x = a^2$;
nếu $a + b < 0$ hoặc $a + b > 0$ và $ab < 0$, thì vô nghiệm.

Ví dụ 3. Giải hệ phương trình

$$tg x + tg y = a, \quad x + y = b.$$

Lời giải. Nêu điều kiện xác định: $x, y \neq \frac{\pi}{2} + n\pi$ (ở đây và sau này $k, l, m, n = 0; \pm 1; \ldots$). Đưa phương trình thứ nhất của hệ về dạng $\frac{\sin(x + y)}{\cos x \cos y} = a$ và tiếp theo, có tính đến $x + y = b$, ta được

$$a \cos x \cos y = \sin b.$$

Trường hợp I: $a = 0$. Nó, dĩ nhiên, chia thành hai phương án: I, a) $a = 0$, $\sin b = 0$; I, 6) $a = 0$, $\sin b \neq 0$.

Nếu $sin b = 0$, tức là $b = m\pi$, thì mọi cặp $(x; y)$ đều thỏa mãn phương trình (7), còn hệ (6) — mọi cặp $(x; y)$ thỏa mãn các điều kiện sau:

$$x \neq \frac{\pi}{2} + n\pi; \quad y \neq \frac{\pi}{2} + n\pi; \quad x + y = b.$$

Nếu $sin b \neq 0$, tức là $b \neq m\pi$, thì phương trình (7), và cùng với nó hệ (6), không có nghiệm.

Trường hợp II: $a \neq 0$. Khi đó phương trình (7) được biến đổi thành dạng

$$\cos x \cos y = \frac{\sin b}{a} \text{ và tiếp theo,}$$

$$\cos (x + y) + \cos (x - y) = \frac{2 \sin b}{a}.$$

Nếu lại xét rằng $x + y = b$, thì phương trình (8) có thể viết lại như sau:

$$\cos (x - y) = \frac{2 \sin b}{a} - \cos b.$$

⟦folio 49⟧

Các lập luận tiếp theo phụ thuộc vào việc đánh giá vế phải của phương trình (9):
nếu $\left| \frac{2 \sin b}{a} - \cos b \right| > 1$, thì phương trình (9), và cùng với nó hệ (6), không có nghiệm; còn nếu $\left| \frac{2 \sin b}{a} - \cos b \right| \leq 1$, thì
$$x - y = \pm \arccos \left( \frac{2 \sin b}{a} - \cos b \right) + 2k\pi.$$
Giải phương trình cuối cùng trong hệ với phương trình $x + y = b$, ta được
$$\begin{cases} x = \frac{b}{2} \pm \frac{1}{2} \arccos \left( \frac{2 \sin b}{a} - \cos b \right) + k\pi, \\ y = \frac{b}{2} \pm \frac{1}{2} \arccos \left( \frac{2 \sin b}{a} - \cos b \right) - k\pi. \end{cases}$$
Ta chỉ còn phải выяснить xem có thể xảy ra trường hợp nào mà với một số giá trị của các tham số, các giá trị tìm được $x, y$ lại trùng với các giá trị bị cấm $\frac{\pi}{2} + n\pi$ hay không. Dễ thấy rằng điều này xảy ra khi $b \pm \arccos \left( \frac{2 \sin b}{a} - \cos b \right) = \pi + 2l\pi$. Viết lại đẳng thức cuối cùng như sau: $\pm \arccos \left( \frac{2 \sin b}{a} - \cos b \right) = \pi - b + 2l\pi$, rồi lấy côsin của hai vế. Ta được
$$\frac{2 \sin b}{a} - \cos b = -\cos b, \quad \sin b = 0, \quad b = m\pi.$$
Vậy, nếu $b = m\pi$ và $a \neq 0$, thì hệ (6) sẽ không có nghiệm. Gộp tất cả các kết quả đã thu được, ta viết đáp số:
nếu $a = 0, b = m\pi$, thì nghiệm của hệ (6) là mọi cặp $(x, y)$ sao cho $x \neq \frac{\pi}{2} + n\pi, \quad y \neq \frac{\pi}{2} + n\pi, \quad x + y = b$;
nếu $a = 0, b \neq m\pi$, hoặc $a \neq 0, b = m\pi$, thì không có nghiệm;
nếu $a \neq 0, b \neq m\pi$, nhưng $\left| \frac{2 \sin b}{a} - \cos b \right| \leq 1$, thì không có nghiệm.

Chúng tôi chỉ xét các ví dụ với hai tham số. Việc tăng thêm số tham số, không đem lại điều gì mới về nguyên tắc, chỉ dẫn đến sự tăng thêm các khó khăn kĩ thuật.

Bài tập
1. Giải các phương trình sau:
2. Giải hệ phương trình:

a) $a^2 - \frac{a^2 - b^2}{2x - x^2} = \frac{b^2 (x + 2)}{x - 2}$;
b) $\frac{\sqrt{a - x} - \sqrt{x - b}}{\sqrt{a - x} + \sqrt{x - b}} = \frac{a - b}{a + b - 2x}$;
b) $\frac{\mathrm{tg} ax}{\sin bx} = 0$.
