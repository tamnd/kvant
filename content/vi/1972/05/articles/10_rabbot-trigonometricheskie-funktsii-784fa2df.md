---
id: 1972-5-rabbot-trigonometricheskie-funktsii-784fa2df
issue: kvant_1972_5
year: 1972
number: "5"
title: Hàm lượng giác
authors:
  - Раббот Ж. М.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 38
page_last: 44
page_labels: 36-42
tag: 3T64
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 8e698b409ca84a24b931684ef5448305a5f16ef47cdeb02d0050b2d6fed91eed
prompt_sha256: draft-1
translated_from: content/ru/1972/05/articles/10_rabbot-trigonometricheskie-funktsii-784fa2df.md
source_content_sha256: 03dfbcd899b8451daac0529c7b88193be1e8f98d27d6b78ff9c91068d3d45ffe
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 36⟧

ỨNG DỤNG THỰC HÀNH

Chức năng lượng giác, mã hóa cho người nộp đơn vào các trường đại học trên bản sao đầu vào.

1. Hàm số tam lượng

Tội lỗi 1 là gì? ctg 21 có dấu hiệu gì? Những câu hỏi như vậy thường khiến nhiều ứng viên bối rối.

Chúng ta muốn định nghĩa hàm lượng giác trên tập hợp tất cả các số thực. Để làm điều này, hãy xem xét một đường tròn có bán kính đơn vị trên mặt phẳng tọa độ với tâm ở gốc tọa độ (“đường tròn lượng giác”).

Cho ta một số tùy ý $t_0$. Chúng ta hãy vẽ trên chu vi của đường tròn lượng giác từ điểm $E(1; 0)$ (Hình 1) một cung có độ dài $|t_0|$ theo hướng dương (ngược chiều kim đồng hồ) nếu $t_0 \geq 0$ và theo hướng âm (theo chiều kim đồng hồ) nếu $t_0 < 0$ (đơn vị độ dài của đường tròn lượng giác phục vụ). Trong trường hợp này, chúng ta nhận được điểm $P_{t_0}$ trên vòng tròn có tọa độ $(x_{t_0}, y_{t_0})$. Trục hoành $x_{t_0}$ của điểm $P_{t_0}$ được gọi là cosin của số $t_0$, và tọa độ $y_{t_0}$ của điểm này là sin của số $t_0$:

$$\cos t_0 = x_{t_0}; \sin t_0 = y_{t_0}.$$

Điểm tinh tế nhất trong định nghĩa của chúng tôi là quá trình mở một vòng tròn có độ dài cho trước. Nó có thể được hình dung như việc cuộn (không kéo dãn) một đoạn quanh một vòng tròn.

Vì vậy, để có được tội của số $t_0$, trước tiên chúng ta khớp (bằng cách quanh co) số $t_0$ với định nghĩa của điểm $P_{t_0}$ trên đường tròn, sau đó lấy tọa độ của điểm này:

$$t_0 \rightarrow P_{t_0}(x_{t_0}; y_{t_0}) \rightarrow y_{t_0} = \sin t_0.$$

Sử dụng định nghĩa của chúng ta, chúng ta có thể nghiên cứu các tính chất của hàm $y = \sin t$. Hãy cho thấy nó được thực hiện như thế nào.

⟦folio 37⟧

a) Tìm nghiệm của phương trình sin t=0. Đặt số $t$ sao cho sin t=0. Điều này có nghĩa là tọa độ của điểm $P_t$ tương ứng với số $t$ bằng 0. Có hai điểm như vậy trên vòng tròn đơn vị: $E$ và $E'$ (xem Hình 1). Chúng sẽ thu được bằng cách đặt nhau, chiều dài của chúng là bội số của chiều dài hình bán nguyệt.

Bây giờ nhận thấy rằng một nửa chiều dài của vòng tròn đơn vị là $\pi$, chúng ta thu được đẳng thức sin t=0 tương đương với đẳng thức $t=\pi k$, trong đó $k=0, \pm 1, \pm 2, \dots$.

6) Nếu các số $t_1$ và $t_2$ khác nhau một bội số của 2π (nghĩa là một số nguyên độ dài chu vi), thì các điểm của vòng tròn đơn vị tương ứng với các số $t_1$ và $t_2$ trùng nhau. Điều này có nghĩa là đẳng thức $t_1-t_2=2\pi k$ ($k=0, \pm 1, \pm 2, \dots$) bao hàm sin đẳng thức $t_1=\sin t_2$, tức là số 2π là chu kỳ của hàm $y=\sin t$.

Hãy chứng minh số 2π là chu kỳ dương nhỏ nhất của hàm số $y=\sin t$. Chúng ta hãy giả sử điều ngược lại: đặt $0<a<2\pi$ và

$$\sin (t+a)=\sin t$$

(1)

với bất kỳ $t$ nào (nghĩa là có một số dương $a$, nhỏ hơn 2π, cũng là một dấu chấm).

Hãy để $t=0$. Khi đó từ (1) ta thu được sin a=0. Nhưng trong khoảng $0<a<2\pi$ chỉ có số $\pi$, sin của nó bằng 0, do đó $a=\pi$. Bây giờ thay $t=\frac{\pi}{2}$ vào (1), chúng ta nhận được $1=-1\left(\sin \frac{\pi}{2}=1-\text{это ordinata точки } A\text{ на рисунке 1}, a \sin \left(\pi+\frac{\pi}{2}\right)=-1-\text{это ordinata точки } A'\right)$ đó. Chúng tôi đã đi đến bất đồng. Vì vậy, 2π là chu kỳ dương nhỏ nhất của hàm $y=\sin t$.

Tính chất tuần hoàn mà chúng ta đã thiết lập cho phép chúng ta nghiên cứu sâu hơn các tính chất của sin chỉ trong một khoảng thời gian, chẳng hạn như ở $0\leq t\leq 2\pi$.

Do tính tuần hoàn đã được chứng minh của xoang nên việc thay thế sẽ diễn ra sau đó. Trong sách giáo khoa “Đại số và các hàm cơ bản” của Kochetkovs (§ 207), người ta ngụ ý, nhưng không nêu rõ ràng, rằng đối với một hàm tuần hoàn, cùng với số $x$, tất cả các số $x+nT$ ($n$-bất kỳ số nguyên nào, $T$-dấu chấm) cũng phải được đưa vào miền định nghĩa. Trong khi đó, điều này rất quan trọng: đôi khi có thể chứng minh tính tuần hoàn của các hàm số bằng cách thu được chính xác tính chất này. Ví dụ, chúng ta hãy chỉ ra rằng hàm $y=\cos \frac{1}{x}$ là không tuần hoàn. Giả sử rằng chu kỳ $T$ của hàm số này. Tại $x=-T$ hàm của chúng ta được xác định, có nghĩa là nó phải được xác định tại $x=-T+T=0$, nhưng tại $x=0$ tham chiếu $\frac{1}{x}$ không tồn tại: chúng ta đi đến mâu thuẫn.

Theo cách hoàn toàn tương tự, chúng ta có thể nghiên cứu các tính chất của hàm $y=\cos t$. Bạn có vẻ khá rõ ràng về cách xác định hàm $y=\tg t$, $y=\ctg t$ (đối số dạng số) và khám phá các thuộc tính của chúng.

Trận chiến

1. Tìm chu kỳ dương nhỏ nhất của hàm số:

a) $y=\sin 3x$; 6) $y=\tg 2x-\sin 3x$; c) $y=2 \sin \left(\frac{\pi}{4}+\frac{x}{2}\right)$; d) $y=\sin^2 x$; e) $y=\sin(\cos x)$; e) $y=\cos(\sin x)$.

Ví dụ 1. Chứng minh hàm số $y=\sin x^2$ không tuần hoàn.

Đã giải quyết và e. Giả sử rằng hàm này là tuần hoàn. Chúng ta hãy tìm số 0 của hàm này (nghĩa là các giá trị của $x$ mà tại đó nó trở thành 0): sin $x^2=0$, từ đó $x^2=\pi k$ ($k=0, 1, 2, \dots$), $x=\pm \sqrt{\pi k}$. Nếu $k=0$ thì $x_0=0$; nếu $k=1$, thì $x_1=\sqrt{\pi}$. Từ giả thiết đưa ra về

⟦folio 38⟧

Tính tuần hoàn của hàm $y=\sin x^2$ ngụ ý rằng cũng có vô số cặp số 0 lân cận của nó (thu được từ $x_0$ và $x_1$ với dws ở bên phải một số nguyên dấu chấm), hiệu giữa chúng bằng $x_1-x_0=\sqrt{\pi}$. Nhưng với bất kỳ $k>1$ nào chúng ta có

$$|x_{k+1}-x_k|=|V(k+1)\pi-Vk\pi|=\frac{\pi}{\sqrt{(k+1)\pi}+\sqrt{k\pi}}<\sqrt{\pi}.$$

kể từ $V(k+1)\pi+Vk\pi>\sqrt{\pi}$. Mâu thuẫn thu được chứng tỏ rằng các hàm $y=\sin x^2$ là không tuần hoàn.

Bài tập

2. Chứng minh hàm số không tuần hoàn: a) $y=\sin \sqrt{x}$; b) $y=\cos x\cos \sqrt{2}x$.
3. Cho biết dấu của các số sau:
a) $\sin 2$; 6) $\cos 3,1$; b) $tg 10$; r) $\sin \pi^2$; d) $tg(\cos 2)$.
4. Người ta cho rằng $\cos^2 t+p\cos t+q>0$ cho tất cả các giá trị thực của $t$. Nó có tuân theo $x^2+px+q>0$ cho tất cả các giá trị thực của $x$ không?

Không khó để thiết lập một cách đơn giản giữa các định nghĩa về hàm lượng giác của góc (tổng quát hóa) và đối số bằng số. Hãy định vị góc sao cho cạnh ban đầu của nó chạy dọc theo trục $Ox$ (Hình 2). Khi đó, sin của một góc theo định nghĩa bằng tọa độ của điểm mà tại đó cạnh cuối của góc cắt đường tròn đơn vị.

Nếu một góc chứa $\alpha$ radian thì cạnh cuối của góc sẽ cắt đường tròn đơn vị ở cuối cung tương ứng với số $\alpha$ khi quấn. Do đó (so sánh Hình 1 và 2)

Hình 2.

Tính chất này đã được chấp nhận trong sách giáo khoa ở trường dưới dạng định nghĩa về sin của một số (và tương tự đối với các hàm khác: cosin, tang, cotang).

2. Chuyển đổi biểu thức lượng giác

Đối với lời giải khác nhau bài toán, thường cần phải thực hiện các phép biến đổi giống nhau và sử dụng các công thức lượng giác. Cần phải nhớ rằng một số công thức làm thay đổi phạm vi định nghĩa; Ngoài ra, cần làm rõ tính thuận nghịch của mọi chuyển đổi.

Ví dụ 2. (MAI, 1970). Chứng minh Giáng sinh:

$$\frac{\left(\cos \alpha+\cos \frac{\alpha}{2}\right)^2-\left(\sin \alpha+\sin \frac{\alpha}{2}\right)^2}{\sin 2\alpha-\sin \alpha}=\mathrm{ctg} \frac{\alpha}{4}.$$

Lời giải e. Trước hết, hãy tìm ODZ. Vế trái của (2) được xác định khi $\sin 2\alpha-\sin \alpha\neq 0$, tức là khi $2\sin \alpha\cos \alpha-\sin \alpha\neq 0$, từ đó $\sin \alpha\neq 0$, $\cos \alpha\neq \frac{1}{2}$; cuối cùng là $\alpha\neq \pi n$, $\alpha\neq \pm \frac{\pi}{3}+2\pi k^*)$. Phải

*) Ở đây và hơn thế nữa, trừ khi có quy định khác, theo đó các tham số $n, k, l$, v.v. chấp nhận tất cả các giá trị nguyên.

⟦folio 39⟧

phần (2) tồn tại với $\sin \frac{\alpha}{4} \neq 0$, tức là, với $\alpha \neq 4\pi l$. Vì vậy, ODZ đã được tìm thấy: $\alpha \neq n\pi, \alpha \neq \pm \frac{\pi}{3} + 2\pi k$.

Chúng ta hãy biểu thị phía bên trái của danh tính bằng $M$. Sau đó

$$M = \frac{\cos^2\alpha + 2\cos\alpha \cos \frac{\alpha}{2} + \cos^2 \frac{\alpha}{2} - \sin^2\alpha - 2\sin\alpha \sin \frac{\alpha}{2} - \sin^2 \frac{\alpha}{2}}{\sin 2\alpha - \sin\alpha} =$$

$$= \frac{(\cos^2\alpha - \sin^2\alpha) + \left(\cos^2 \frac{\alpha}{2} - \sin^2 \frac{\alpha}{2}\right) + 2\left(\cos\alpha \cos \frac{\alpha}{2} - \sin\alpha \sin \frac{\alpha}{2}\right)}{\sin 2\alpha - \sin\alpha} =$$

$$= \frac{\cos 2\alpha + \cos\alpha + 2\cos \frac{3\alpha}{2}}{\sin 2\alpha - \sin\alpha} = \frac{2\cos \frac{\alpha}{2} \cos \frac{3\alpha}{2} + 2\cos \frac{3\alpha}{2}}{2\sin \frac{\alpha}{2} \cos \frac{3\alpha}{2}} =$$

$$= \frac{\cos \frac{\alpha}{2} + 1}{\sin \frac{\alpha}{2}} = \frac{2\cos^2 \frac{\alpha}{4}}{2\sin \frac{\alpha}{4} \cos \frac{\alpha}{4}} = \text{ctg} \frac{\alpha}{4}.$$

Vì vậy, trong ODZ $M = \text{ctg} \frac{\alpha}{4}$.

Ví dụ 3. Chứng minh rằng nếu $\text{ctg}(\alpha + \beta) = 0$ thì

$$\sin(\alpha + 2\beta) = \sin\alpha.$$

(3)

Lời giải. Lưu ý rằng điều kiện $\text{ctg}(\alpha + \beta) = 0$ tương đương với điều kiện

$$\cos(\alpha + \beta) = 0.$$

(4)

Bây giờ chúng ta hãy xem xét sự khác biệt giữa bên phải và bên trái của (3): $\sin(\alpha + 2\beta) - \sin\alpha = 2\sin\beta \cos(\alpha + \beta)$, từ đó, sử dụng (4), chúng ta thu được kết quả cần thiết.

Bài tập

5. (MAI, 1970). Chứng minh danh tính:
a) $(\sin\alpha - \cos\alpha)^2 + (\cos\alpha - \sec\alpha)^2 = 4\text{ctg}^2 2\alpha + 1$;
b) $\sin\alpha + \text{ctg}\alpha - \text{ctg}\alpha \cos\alpha - 1 = \frac{2\cos\left(\frac{\pi}{4} + \alpha\right)\sin\left(\frac{\alpha}{2} - \frac{\pi}{4}\right)}{\cos \frac{\alpha}{4}}.$

6. Chứng minh danh tính:
a) (MISP, 1969). $\frac{1}{1 + \text{tg}\alpha \text{tg}2\alpha} = \sin\left(\frac{\pi}{2} + 2\alpha\right)$; b) (MEPhI). $\cos^2\varphi + \cos^2(\alpha + \varphi) - 2\cos\alpha \cos\varphi \cos(\alpha + \varphi) = \sin^2\alpha$.
7. (Khoa Vật lý, Đại học Tổng hợp Matxcơva).
a) Chứng minh rằng nếu $5\sin\beta = \sin(2\alpha + \beta)$ thì $\frac{\text{ctg}(\alpha + \beta)}{\text{tg}\alpha} = \frac{3}{2}$;
b) Chứng minh rằng nếu $\cos x = \cos a \cos b$, $x \pm a \neq \pi(2k + 1)$, $b \neq \pi(2k + 1)$ thì $1 + \text{tg}\frac{x + a}{2} \text{tg}\frac{x - a}{2} = \frac{1}{\cos^2 \frac{b}{2}}$.

Ví dụ 4. Rút gọn biểu thức

$$M = \sin\alpha + \sin(\alpha + \delta) + \dots + \sin(\alpha + n\delta).$$

⟦folio 40⟧

Lời giải. Nhận thấy rằng các đối số của hàm sin tạo thành một cấp số đối số có hiệu $\delta$, chúng ta nhân cả hai vế của đẳng thức với $2 \sin \frac{\delta}{2}$:

$$2 \sin \frac{\delta}{2} \cdot M = 2 \sin \frac{\delta}{2} \sin \alpha + 2 \sin \frac{\delta}{2} \sin (\alpha + \delta) + \dots + 2 \sin \frac{\delta}{2} \times$$

$$\times \sin (\alpha + n\delta) = \cos \left( \alpha - \frac{\delta}{2} \right) - \cos \left( \alpha + \frac{\delta}{2} \right) + \cos \left( \alpha + \frac{\delta}{2} \right) -$$

$$- \cos \left( \alpha + \frac{3\delta}{2} \right) + \dots + \cos \left[ \alpha + \left( n - \frac{1}{2} \right) \delta \right] - \cos \left[ \alpha + \left( n + \frac{1}{2} \right) \delta \right] =$$

$$= \cos \left( \alpha - \frac{\delta}{2} \right) - \cos \left[ \alpha + \left( n + \frac{1}{2} \right) \delta \right] = 2 \sin \left( \alpha + \frac{n\delta}{2} \right) \sin \frac{n+1}{2} \delta.$$

Vì vậy, nếu $\sin \frac{\delta}{2} \neq 0$, tức là $\delta \neq 2\pi k$, thì

$$M = \frac{\sin \left( \alpha + \frac{n\delta}{2} \right) \sin \left( \frac{(n+1)\delta}{2} \right)}{\sin \frac{\delta}{2}}.$$

Nếu $\delta = 2\pi k$ thì

$$M = \sin \alpha + \sin (\alpha + 2\pi k) + \dots + \sin (\alpha + 2\pi nk) = (n+1) \sin \alpha.$$

Bài tập

8. Chứng minh điều sau:

$$= \frac{\sin \frac{n\alpha}{2} \cos \frac{(n+1)\alpha}{2}}{\sin \frac{\alpha}{2}};$$

a) (MEPhI). $\cos \alpha + \cos 2\alpha + \cos 3\alpha + \dots + \cos n\alpha =$

b) (MSU). $\cos \frac{\pi}{5} + \cos \frac{3\pi}{2} = \frac{1}{2}$.

9. (MEPhI). Đơn giản hóa biểu thức của bạn. a) $\cos \alpha \cdot \cos 2\alpha \cdot \cos 4\alpha \dots \cos 2^{n}\alpha$;

b) $\cos \alpha - \cos 2\alpha + \cos 3\alpha - \cos 4\alpha + \dots + (-1)^{n+1} \cos n\alpha$;

b) $\sin \alpha + 2 \sin 2\alpha + 3 \sin 3\alpha + \dots + n \sin n\alpha$;

r) $\sin^3 \frac{\alpha}{3} + 3 \sin^3 \frac{\alpha}{3^2} + 9 \sin^3 \frac{\alpha}{3^3} + \dots + 3^{n-1} \sin^3 \frac{\alpha}{3^n}$.

Ví dụ 5. Chứng minh Giáng sinh:

$$\mathrm{tg} \alpha + \frac{1}{2} \mathrm{tg} \frac{\alpha}{2} + \frac{1}{4} \mathrm{tg} \frac{\alpha}{4} + \dots + \frac{1}{2^n} \mathrm{tg} \frac{\alpha}{2^n} = \frac{1}{2^n} \mathrm{ctg} \frac{\alpha}{2^n} - 2 \mathrm{ctg} 2\alpha.$$

Lời giải. Nhận thấy rằng phía bên phải của danh tính chứa cotan-gen, chúng tôi biểu thị $\mathrm{tg} \alpha$ đến $\mathrm{ctg} 2\alpha$ và $\mathrm{ctg} \alpha$: $\mathrm{tg} \alpha = \mathrm{ctg} \alpha - 2 \mathrm{ctg} 2\alpha$.

Sau đó

$$\mathrm{tg} \alpha = \mathrm{ctg} \alpha - 2 \mathrm{ctg} 2\alpha,$$

$$\mathrm{tg} \frac{\alpha}{2} = \mathrm{ctg} \frac{\alpha}{2} - 2 \mathrm{ctg} \alpha,$$

$$\mathrm{tg} \frac{\alpha}{4} = \mathrm{ctg} \frac{\alpha}{4} - 2 \mathrm{ctg} \frac{\alpha}{2},$$

$$\dots$$

$$\mathrm{tg} \frac{\alpha}{2^n} = \mathrm{ctg} \frac{\alpha}{2^n} - 2 \mathrm{ctg} \frac{\alpha}{2^{n-1}}.$$

⟦folio 41⟧

Nhân các danh tính viết lần lượt với 1, $\frac{1}{2}$, ..., $\frac{1}{2^n}$ rồi cộng chúng lại với nhau, ta được kết quả như mong muốn. Các phép biến đổi của chúng tôi chỉ có ý nghĩa đối với $\alpha \neq \frac{\pi k}{2}$ (kiểm tra!).

Bài tập

10. Chứng minh các đẳng thức: a) (UGPI). $\sin^2 \alpha + \sin^2 (120^\circ + \alpha) + \sin^2 (120^\circ - \alpha) = \frac{3}{2}$;
6) (MAI). $tg 3\alpha = tg \alpha tg \left(\frac{\pi}{3} + \alpha\right) tg \left(\frac{\pi}{3} - \alpha\right)$; b) (MagGPI). $4 \cos^2 \alpha + \sin^2 2\alpha + 4 \sin^4 \alpha = 4$.

11. Chuyển đổi thành sản phẩm: a) (MagGPI). $\cos^2 (x + y) + \sin (x + y) + \cos (x + y) + \sin^2 (x + y)$;
6) (MAI). $tg^3\alpha + \frac{1}{\cos^2 \alpha} + 3 \text{ctg} \left(\frac{3\pi}{2} + \alpha\right) - 4$;
b) (MISP, 1969). $\sin 5\alpha \sin 4\alpha + \sin 4\alpha \sin 3\alpha - \sin 2\alpha \sin \alpha$; r) (MTI, 1970).

$\sec^2 \alpha - tg^2 \alpha + tg \left(\frac{\pi}{2} - \frac{\alpha}{2}\right) + \text{ctg} \left(\frac{\pi}{4} - \frac{\alpha}{2}\right)$.

Ví dụ 6. Tính sin 18° không cần bảng.
Lời giải e. Chúng ta sẽ sử dụng thực tế là $18^\circ \cdot 5 = 90^\circ$, tức là $2 \cdot 18^\circ + 3 \cdot 18^\circ = 90^\circ$, từ đó

$$\cos (2 \cdot 18^\circ) = \sin (3 \cdot 18^\circ)$$

và thực tế là cos 2α và sin 3α được biểu diễn một cách hợp lý thông qua sin α. Áp dụng công thức cos 2α = 1 - 2 sin²α và sin 3α = 3 sin α - 4 sin³α, từ (5) ta thu được: $4 \sin^3 18^\circ - 2 \sin^2 18^\circ - 3 \sin 18^\circ + 1 = 0$.

Ký hiệu sin 18° bằng y, ta thu được phương trình

$$4y^3 - 2y^2 - 3y + 1 = 0,$$

điều này rất dễ giải quyết bằng cách lưu ý rằng $y = 1$ là nghiệm của nó (ngay sau đó vế trái của (6) chia hết cho $y - 1$): $(y - 1) (4y^2 + 2y - 1) = 0$, từ đó $y_1 = 1, y_2, 3 = \frac{-1 \pm \sqrt{5}}{4}$. Xét sin 18° ≠ 1, sin 18° > 0, ta thấy sin 18° = $\frac{\sqrt{5} - 1}{4}$.

Ví dụ 7. Hãy đơn giản các biểu thức: a) $S_1 = \cos^2 \alpha + \cos^2 2\alpha + \dots + \cos^2 n\alpha$; b) $S_2 = \sin^2 \alpha + \sin^2 2\alpha + \dots + \sin^2 n\alpha$.
Lời giải e. Vì sin2x + cos2x = 1 nên

$$S_1 + S_2 = n.$$

Bây giờ áp dụng kết quả của Bài tập 8a) (điều này có thể thực hiện được với α nào?), chúng ta thu được:

$$S_1 - S_2 = (\cos^2 \alpha - \sin^2 \alpha) + (\cos^2 2\alpha - \sin^2 2\alpha) + \dots + (\cos^2 n\alpha - \sin^2 n\alpha) = \cos 2\alpha + \cos 4\alpha + \dots + \cos 2n\alpha = \frac{\sin n\alpha \cos (n + 1)\alpha}{\sin \alpha}$$

Bây giờ từ (7) và (8) dễ dàng thu được: $S_1 = \frac{n}{2} + \frac{\sin n\alpha \cos (n + 1)\alpha}{2 \sin \alpha}$; $S_2 = \frac{n}{2} - \frac{\sin n\alpha \cos (n + 1)\alpha}{2 \sin \alpha}$. đáp số đối với α = πk là bao nhiêu?

Bài tập

12. Tính toán không cần bảng: a) cos 15°; b) tg 7,5°; c) tan 18°; r) (MAI, 1970). cos 55° cos 65° cos 175°; d) (MISP, 1969). tg 9° - tg 27° - tg 63° + tg 81°.

⟦folio 42⟧

Ví dụ 8. Tìm $\cos \alpha + \sin \alpha$ nếu $\sin \alpha \cos \alpha = 0,48$.

Lời giải. Lấy căn bậc hai (như mọi khi, số học!) Từ cả hai vế của đẳng thức $(\cos \alpha + \sin \alpha)^2 = 1 + 2 \sin \alpha \cos \alpha$, chúng ta thu được: $|\cos \alpha + \sin \alpha| = \sqrt{1 + 2 \sin \alpha \cos \alpha} = 1,4$ (biểu thức căn thức không âm: $1 + 2 \sin \alpha \cos \alpha = 1 + \sin 2\alpha \geq 0$, vì $\sin 2\alpha \geq -1$). Vì theo điều kiện $\sin \alpha \cos \alpha > 0$ nên $\sin \alpha$ và $\cos \alpha$ có cùng dấu, tức là $\alpha$ thuộc quý I hoặc quý III. Nếu $2\pi n < \alpha < \frac{\pi}{2} + 2\pi n$ thì $\sin \alpha + \cos \alpha = 1,4$;

nếu $\pi + 2\pi n < \alpha < \frac{3\pi}{2} + 2\pi n$ thì $\sin \alpha + \cos \alpha = -1,4$.

Bài tập

13. a) (MAI). Tìm $\frac{1 - 2 \sin^2 \frac{\alpha}{2}}{1 + \sin \alpha}$ nếu $tg \frac{\alpha}{2} = m - 1$; 6) (MSU). Chứng minh rằng nếu $tg \alpha = \frac{1}{7}$, $\sin \beta = \frac{1}{\sqrt{10}}$ thì $\alpha + 2\beta = \frac{\pi}{4}$ ($\alpha$ và $\beta$ là các góc của phần tư thứ nhất); 7) (MISP). Tìm $18 \sin \frac{3\alpha}{2} \sin \frac{\alpha}{2}$ nếu $\cos \alpha = \frac{2}{3}$. 8) (MTI). Tìm $tg \frac{\alpha}{2}$ nếu $tg \alpha = \frac{4}{3}$, $\pi < \alpha < \frac{3\pi}{2}$.

14. (MSU). Được biết, $\alpha + \beta + \gamma = \frac{\pi}{2}$, $\alpha > 0$, $\beta > 0$, $\gamma > 0$ và $ctg \alpha, ctg \beta, ctg \gamma$ tạo thành một cấp số cộng. Tìm $ctg \alpha$ $ctg \gamma$.

15. (MEPhI). Chứng minh rằng nếu $\alpha, \beta, \gamma$ là các góc của một tam giác thì

a) $\sin \alpha + \sin \beta + \sin \gamma = 4 \cos \frac{\alpha}{2} \cos \frac{\beta}{2} \cos \frac{\gamma}{2}$;

b) $tg \alpha + tg \beta + tg \gamma = tg \alpha tg \beta tg \gamma$;

r) $\sin 2\alpha + \sin 2\beta + \sin 2\gamma = 4 \sin \alpha \sin \beta \sin \gamma$;

d) $\sin^2 \alpha + \sin^2 \beta + \sin^2 \gamma = 2 \cos \alpha \cos \beta \cos \gamma + 2$;

e) $tg \frac{\alpha}{2} tg \frac{\beta}{2} + tg \frac{\alpha}{2} tg \frac{\gamma}{2} + tg \frac{\beta}{2} tg \frac{\gamma}{2} = 1$;

g) $\cos \alpha + \cos \beta + \cos \gamma \leq \frac{3}{2}$;

3) $\sin^2 \alpha + \sin^2 \beta + \sin^2 \gamma > 2$ (tam giác nhọn).

16. Chứng minh các bất đẳng thức:

a) (MIPT).

$ctg \frac{\alpha}{2} > 1 + ctg \alpha \left(0 < \alpha < \frac{\pi}{2}\right)$;

6) (VSU). $\cos \alpha + 3 \cos 3\alpha + 6 \cos 6\alpha \geq -7,2$;

b) (MIPT). $(1 - tg^2\alpha) (1 - 3tg^2\alpha) (1 + tg2\alpha tg3\alpha) > 0$; r) (MIPT).

$(ctg^2\alpha - 1) (3ctg^2\alpha - 1) \times (ctg3\alpha tg2\alpha - 1) \leq -1$; đ) (MSU). $4 \sin 3\alpha + 5 \geq 4 \cos 2\alpha + 5 \sin \alpha$.

Hơn thế nữa. Các chữ viết tắt sau đây được sử dụng trong bài viết:

MAI - Viện Hàng không Moscow, MSU - Đại học Bang Moscow, MGPI - Viện Sư phạm Bang Moscow, MagGPI - Học viện Sư phạm Bang Magadan, MTI - Viện Dệt may Moscow, MISP - Viện Thép và Slav Moscow, MEPhI - Viện Vật lý Kỹ thuật Moscow, USPI - Viện Sư phạm Bang Ulyanovsk, VSU - Đại học Bang Voronezh, MIPT - Viện Vật lý và Công nghệ Moscow.
