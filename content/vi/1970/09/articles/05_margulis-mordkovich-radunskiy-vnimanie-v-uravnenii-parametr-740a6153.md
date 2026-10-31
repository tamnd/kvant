---
id: 1970-9-margulis-mordkovich-radunskiy-vnimanie-v-uravnenii-parametr-740a6153
issue: kvant_1970_9
year: 1970
number: "9"
title: 'Chú ý: có một tham số trong phương trình!'
authors:
  - Маргулис А. Я.
  - Мордкович А. Г.
  - Радунский Б. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 22
page_last: 27
page_labels: 20-25
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 5eb65b9d1b3b48f45fcb42a437d4861abd2a372e6da621ca1fcc73ee71e87d1f
prompt_sha256: draft-1
translated_from: content/ru/1970/09/articles/05_margulis-mordkovich-radunskiy-vnimanie-v-uravnenii-parametr-740a6153.md
source_content_sha256: da4a094c5192384dd8ef9381912ba8bba554b8f1be8baa3971dc37608d230c52
translation_model: draft
translation_run: vi-draft-gaps-2026-10-31
translation_quality: draft
---

⟦folio 20⟧

Về mặt tham số, khoảng cách của tất cả các trường hợp có thể xảy ra có tầm quan trọng đặc biệt. Tuy nhiên, rất khó để dự đoán trước trường hợp nào sẽ được xác định trong quá trình lời giải. Điều này một mặt làm phức tạp lời giải, nhưng mặt khác, làm cho công việc trở nên thú vị hơn, tạo cho nó tính chất nghiên cứu.

Một chút lý thuyết

Dạng tổng quát của phương trình với một tham số là:
$$F(x,a) = 0.$$ (3)

Đối với $a$ khác nhau, phương trình (3) có thể có các tập nghiệm khác nhau và bài toán của chúng tôi là nghiên cứu tất cả các trường hợp, tìm hiểu điều gì sẽ xảy ra với bất kỳ giá trị nào của tham số. Khi phương trình lời giải có ​​tham số, người ta thường phải xem xét nhiều phương án khác nhau. Việc phát hiện kịp thời ít nhất một số phương án không thể thực hiện được có tầm quan trọng rất lớn, vì nó giúp chúng ta thoát khỏi những công việc không cần thiết. Do đó, với lời giải của phương trình (3), ODZ nên hiểu phạm vi các giá trị cho phép của ẩn số và tham số, tức là tập hợp tất cả các cặp số $(x,a)$ mà hàm của hai biến $F(x,a)$ được xác định (có ý nghĩa). Do đó, minh họa hình học tự nhiên của ODZ dưới dạng một vùng nhất định của mặt phẳng $xOa$.

Ví dụ: phương trình ODZ
$$\sqrt{x} + \sqrt{a} = \sqrt{1-(x+a)}$$ (4)
được xác định bởi hệ bất đẳng thức
$$x \geq 0, a \geq 0, x+a \leq 1.$$

Hệ thống này thỏa mãn tọa độ của tất cả các điểm của tam giác (bao gồm cả ranh giới của nó), được bao quanh trong Hình 1 với màu xanh lam và xanh lam *). Nhân tiện, từ những khác biệt này, ngay lập tức suy ra rằng phương trình $a<0$ (4) không có lời giải.

Hãy giải phương trình (4). Sau khi bình phương cả hai phần của nó (trong trường hợp này là một phép biến đổi tương đương do cả hai vế của phương trình (4) không âm), chúng ta thu được phương trình
$$2\sqrt{ax} = 1 - 2(x+a).$$ (5)

Chúng tôi đã nói ở trên rằng việc loại bỏ ít nhất một phần các lựa chọn không thể thực hiện được sẽ giúp chúng ta thoát khỏi những công việc không cần thiết. Chúng tôi lưu ý rằng vế trái của phương trình (5) không âm đối với mọi $a,x$ được chấp nhận, có nghĩa là khi vế phải của phương trình này âm thì việc tìm kiếm lời giải là vô ích. Rõ ràng là bạn nên tìm kiếm lời giải trong phần ODZ nơi chúng có thể tồn tại, sau khi đã thu hẹp ODZ thích hợp cho việc này:
$$1 - 2(x+a) \geq 0, \text{ откуда } x+a \leq \frac{1}{2}.$$

Trong Hình 1, phần ODZ nơi lời giải không thể được tô bóng bằng màu rõ ràng.

Bằng cách bình phương cả hai vế của phương trình (5) **) và đưa các số hạng tương tự, ta thu được phương trình
$$x^2 + (a-1)x + a^2 - a + \frac{1}{4} = 0,$$

*) Để biết thêm chi tiết về hệ bất phương trình hình học lời giải với hai ẩn số, xem «Kvant» Số 4 năm 1970.
**) Trong ODZ mới, cả hai vế của phương trình (5) đều không âm. Trong trường hợp này, việc bình phương sẽ không dẫn đến sự xuất hiện của các rễ đã xây dựng.

⟦folio 21⟧

Ở đâu
$$x_{1,2} = \frac{1-a \pm \sqrt{2a-3a^2}}{2}.$$

Cả hai đều tìm thấy nghiệm cho tất cả các giá trị được chấp nhận của tham số $a$, (nghĩa là với tất cả $a$ thỏa mãn các bất đẳng thức $0 \leq a \leq \frac{1}{2}$ - xem Hình 1) đều là số thực. Thật vậy, phân biệt đối xử $D = 2a-3a^2 \geq 0$ cho $0 \leq a \leq \frac{2}{3}$; điều đó có nghĩa là thậm chí còn hơn thế nữa $D \geq 0$ với $0 \leq a \leq \frac{1}{2}$.

Bây giờ chúng ta cần tìm hiểu xem các giá trị tìm được có thỏa mãn các điều kiện $x \geq 0$, $x+a \leq \frac{1}{2}$ hay không.

Trước tiên chúng ta hãy kiểm tra xem điều kiện $x+a \leq \frac{1}{2}$ có được đáp ứng không. chúng tôi có
$$x_1+a = \frac{1-a-\sqrt{2a-3a^2}}{2} + a = \frac{1+a-\sqrt{2a-3a^2}}{2}.$$
Giải quyết bất đẳng thức
$$\frac{1+a-\sqrt{2a-3a^2}}{2} \leq \frac{1}{2},$$
chúng tôi nhận được $0 \leq a \leq \frac{1}{2}$. Điều này có nghĩa là $x_1+a \leq \frac{1}{2}$ cho tất cả các giá trị được chấp nhận của tham số $a$.

Kế tiếp,
$$x_2+a = \frac{1-a+\sqrt{2a-3a^2}}{2} + a = \frac{1+a+\sqrt{2a-3a^2}}{2}.$$
Bất bình đẳng
$$\frac{1+a+\sqrt{2a-3a^2}}{2} \leq \frac{1}{2}$$

chỉ được thực hiện ở $a = 0$. Nhưng đối với $a = 0$ chúng ta có $D = 0$ và $x_1=x_2 = \frac{1}{2}$.

Việc chứng minh tính không âm của cả hai nghiệm tìm được xin dành cho độc giả.

Đáp số: nếu $0 \leq a \leq \frac{1}{2}$ thì $x = \frac{1-a-\sqrt{2a-3a^2}}{2}$;

nếu $a < 0$ hoặc $a > \frac{1}{2}$ thì lời giải thì không.

Lưu ý rằng ở lời giải của phương trình đang xem xét, việc làm khô ODZ hóa ra lại có ích. Câu hỏi được đặt ra một cách tự nhiên: khi nào nên làm rõ những điều đó?

Nếu chúng ta thực hiện một phép biến đổi dẫn đến một phương trình tương đương với phương trình trước đó, thì tất nhiên trong trường hợp ODZ thì không cần thiết. Nếu không thì nó rất hữu ích. Ví dụ, tình huống này phát sinh khi bình phương (hoặc lũy thừa chẵn bất kỳ) cả hai phần của một phương trình, đó là điều chúng ta gặp trong ví dụ đã xem xét.

Một số ví dụ
Ví dụ 1*). Giải phương trình
$$\frac{\sqrt{a+x}}{a} + \frac{\sqrt{a+x}}{x} = \sqrt{x}.$$
Lời giải. ODZ được xác định bởi các phương trình $x > 0$, $a+x \geq 0$, $a \neq 0$ (nhân tiện, từ đây, ngay lập tức suy ra rằng đối với $a = 0$ phương trình không có lời giải). Hãy chuyển phương trình về dạng
$$(a+x)^{3/2} = ax^{3/2}.$$
Hãy làm khô ODZ: từ phần không âm của phương trình cuối cùng và các phương trình $x > 0$, $a \neq 0$ suy ra $a > 0$.

Tiếp theo chúng ta nhận được: $a+x = a^{2/3}x$, từ đâu $x (a^{2/3}-1) = a$.
Với $a = 1$ lời giải, rất/không, không. Nếu $a \neq 1$ thì
$$x = \frac{a}{a^{2/3}-1}.$$
Hãy cùng tìm hiểu xem, với sự cân nhắc của mọi người,
*) Số 206 từ “Bộ sưu tập bài toán về toán tiểu học”. Tác giả: N. P. Antonov, M. Ya. Vygodsky, V. V. Nikitin, A. I. Sankin. Trong bài toán đã cho, ví dụ đã được giải quyết/herno.

⟦folio 22⟧

---
running_head:
folio:
---

Cho các giá trị của tham số $a$ ($a > 0, a \neq 1$), điều kiện $x > 0$ được thỏa mãn (từ đó rõ ràng là điều kiện thứ hai $a + x \geq 0$ được thỏa mãn).

Bất đẳng thức $\frac{a}{a^{2/3} - 1} > 0$ chỉ đúng với $a > 1$ (có tính đến $a > 0$). Do đó, không phải với tất cả các giá trị được chấp nhận của $a$, nghiệm tìm được hóa ra là phù hợp.

Đáp số: nếu $a > 1$ thì $x = \frac{a}{a^{2/3} - 1}$; nếu $a \leq 1$ thì lời giải không phải.

Ví dụ 2: Giải phương trình
$$\log_9 x + \log_9 \frac{2 - x}{2} = \log_9 \log_9 p.$$

Lời giải. ODZ được xác định bởi các bất đẳng thức $0 < x < 2$, $p > 1$ (trong Hình 2 vùng này có màu đỏ thẫm). Giải phương trình, ta luôn thu được
$$\frac{x(2 - x)}{2} = \log_9 p,$$
$$x^2 - 2x + 2\log_9 p = 0,$$
$$x_{1,2} = 1 \pm \sqrt{1 - 2\log_9 p}.$$

Điều kiện $1 - 2\log_9 p \geq 0$ được thỏa mãn đối với $p \leq 3$, có tính đến ODZ, sẽ cho $1 < p \leq 3$. Với $p$ như vậy, nghiệm sẽ là số thực. Tại $p > 1$, bất đẳng thức $\log_9 p > 0$ được thỏa mãn và sau đó là $1 - 2\log_9 p < 1$. Theo đó, với $1 < p \leq 3$ bất đẳng thức $0 < x_{1,2} < 2$ đúng.

Đáp số: nếu $1 < p \leq 3$ thì $x_{1,2} = 1 \pm \sqrt{1 - 2\log_9 p}$; với phần còn lại $p$ lời giải không.

Bình luận. Từ phương trình (6) chúng ta thu được $p = 9^{\frac{x(2 - x)}{2}}$. Đồ thị của hàm này, được vẽ ở Hình 2, cho thấy rõ điều kiện $0 < x < 2$ được thỏa mãn tại $1 < p \leq 3$.

Ví dụ 3: Giải phương trình
$$\frac{a + \sin x}{a \cos x + 1} = \frac{a + \cos x}{a \sin x + 1}.$$

Lời giải. Trước tiên chúng ta hãy xem xét trường hợp $a = 0$. Phương trình đã cho có dạng $\sin x = \cos x$, do đó $x = \frac{\pi}{4} + \pi n$ ($n = 0, \pm 1, \ldots$).

Hãy để bây giờ $a \neq 0$. Khi đó ODZ được xác định bởi các phương trình
$$\cos x \neq -\frac{1}{a}; \sin x \neq -\frac{1}{a}.$$

Chúng ta hãy biến đổi phương trình đã cho thành dạng $(\sin x - \cos x)[a^2 + a(\sin x + \cos x) + 1] = 0$. Phương trình thuộc tính cuối cùng là tập hợp các phương trình sau:
$$a^2 + a(\sin x + \cos x) + 1 = 0,$$
$$\sin x - \cos x = 0.$$

Giải phương trình đầu tiên của tập hợp (7), ta thu được:
$$a\sqrt{2}\sin(x + \frac{\pi}{4}) = -a^2 - 1$$
trở đi
$$\sin\left(x + \frac{\pi}{4}\right) = -\frac{a^2 + 1}{a\sqrt{2}}.$$

Phương trình cuối cùng không có lời giải, vì $\left| -\frac{a^2 + 1}{a\sqrt{2}} \right| > 1$ với mọi $a \neq 0$. Thật vậy, giả sử rằng $\frac{a^2 + 1}{|a|\sqrt{2}} \leq 1$; biến đổi sự bất bình đẳng này, chúng ta nhận được
$$a^2 + 1 \leq |a|\sqrt{2}, (a^2 + 1)^2 \leq 2a^2,$$
$$a^4 + 1 \leq 0.$$

Bất đẳng thức cuối cùng sai.

⟦folio 23⟧

Nghiệm của phương trình tổng thể thứ hai (7) là các giá trị $x = \frac{\pi}{4} + \pi k$ ($k = 0, \pm 1, \ldots$). Vẫn còn phải kiểm tra xem, đối với tất cả các giá trị của $a \neq 0$, các giá trị tìm thấy của $x$ có được chấp nhận hay không.

Nếu $k = 2n$ thì $\sin x = \cos x = \frac{\sqrt{2}}{2}$ và điều kiện $\frac{\sqrt{2}}{2} \neq -\frac{1}{a}$ phải được thỏa mãn, tức là $a \neq -\sqrt{2}$.

Nếu $k = 2n + 1$ thì $\sin x = \cos x = -\frac{\sqrt{2}}{2}$.

Từ điều kiện $-\frac{\sqrt{2}}{2} \neq -\frac{1}{a}$ ta thu được: $a \neq \sqrt{2}$.

Tổng hợp tất cả các kết quả, viết

Đáp số: nếu $a \neq \pm \sqrt{2}$ thì $x = \frac{\pi}{4} + \pi k$;

nếu $a = \sqrt{2}$, thì $x = \frac{\pi}{4} + 2\pi n$;

nếu $a = -\sqrt{2}$ thì $x = \frac{\pi}{4} + \pi (2n + 1)$ ($k,n = 0, \pm 1, \pm 2; \ldots$).

Ví dụ 4. Giải phương trình $\log^2_{\sqrt{2}} \cos x - 2a \log_{\sqrt{2}} \cos x = a^2 - 8$.

(8)

Lời giải. Đặt $y = \log_{\sqrt{2}} \cos x$, chúng ta chuyển phương trình đã cho thành phương trình bậc hai $y^2 - 2ay - (a^2 - 8) = 0$,

từ đâu $y_{1,2} = a \pm \sqrt{2(a^2 - 4)}$.

Bây giờ chúng ta cần giải một tập phương trình logarit

$$\log_{\sqrt{2}} \cos x = a + \sqrt{2(a^2 - 4)}. \tag{9}$$

$$\log_{\sqrt{2}} \cos x = a - \sqrt{2(a^2 - 4)}. \tag{10}$$

Chúng tôi lưu ý rằng đối với $a^2 - 4 < 0$ vế phải của phương trình (9) và (10) không có ý nghĩa. Điều này có nghĩa là, đối với $-2 < a < 2$, cả hai phương trình đều không có lời giải. Hãy xem xét trường hợp $a^2 - 4 \geq 0$, trường hợp này có thể xảy ra với $a \geq 2$ hoặc với $a \leq -2$.

Hãy bắt đầu với $a \geq 2$. Vì $\cos x \leq 1$ và $\sqrt{2} > 1$, nên $\log_{\sqrt{2}} \cos x \leq 0$.

Điều này có nghĩa là phương trình (9) và (10) sẽ chỉ có lời giải đối với các giá trị của tham số $a$ mà vế phải của phương trình không dương. Dễ dàng nhận thấy rằng với $a \geq 2$ vế phải của phương trình (9) là dương nên phương trình (9) không có lời giải.

Chúng ta hãy tìm hiểu xem giá trị nào của tham số $a$ thì vế phải của phương trình (10) sẽ không dương. Giải bất đẳng thức $a - \sqrt{2(a^2 - 4)} \leq 0$ (có tính đến điều kiện $a \geq 2$), ta thu được $a \geq \sqrt{8}$. Do đó, nếu $2 \leq a < \sqrt{8}$, thì phương trình (10) không có lời giải (và vì phương trình (9) không có lời giải, nên chúng ta kết luận rằng phương trình (8) trong trường hợp này không có lời giải).

Nếu $a \geq \sqrt{8}$ thì từ phương trình (10) ta thu được

$$x = \pm \arccos(\sqrt{2})^{a - \sqrt{2(a^2 - 8)}} + 2\pi n. \tag{11}$$

Bây giờ chúng ta hãy xem xét trường hợp $a \leq -2$. Đối với các giá trị tham số này, vế phải của phương trình (10) khác, tức là phương trình này có lời giải (chúng đã được viết ở trên theo công thức (11)). Chúng ta hãy tìm hiểu xem giá trị nào của tham số $a$ thì vế phải của phương trình (9) sẽ không dương. Giải bất đẳng thức $a + \sqrt{2(a^2 - 4)} \leq 0$ (có tính đến điều kiện $a \leq -2$), ta thu được $a \geq -\sqrt{8}$. Do đó, nếu $a < -\sqrt{8}$ thì phương trình (9) không có lời giải, nếu $-\sqrt{8} \leq a \leq -2$ thì phương trình (9) có lời giải, cụ thể là:

$$x = \pm \arccos(\sqrt{2})^{a + \sqrt{2(a^2 - 8)}} + 2\pi n.$$

Kết hợp tất cả các kết quả thu được, chúng tôi viết ra

Đáp số: nếu $-2 < a < \sqrt{8}$ thì lời giải không;

nếu $a \geq \sqrt{8}$ hoặc $a < -\sqrt{8}$, thì

$$x = \pm \arccos(\sqrt{2})^{a - \sqrt{2(a^2 - 8)}} + 2\pi n;$$

nếu $-\sqrt{8} \leq a \leq -2$ thì

⟦folio 24⟧

Cơm. 3.

$$x = \pm \arccos(\sqrt{2})^{a \pm \sqrt{2}a^2 - 8} + 2\pi n.$$

Hình học giúp đại số

Đối với các phương trình lời giải có tham số, các cân nhắc hình học khác nhau có thể hữu ích. Ví dụ, hãy xem xét phương trình

$$\sqrt{x(2a-x)} = 1 - x \text{ при } a > 0.$$

Phương trình lời giải nào có thể hiểu là hoành độ giao điểm của đường thẳng $y = 1 - x$ với hình bán nguyệt

$$y = \sqrt{x(2a-x)}, \text{ или}$$
$$(x - a)^2 + y^2 = a^2; \text{ у} \geq 0$$

bán kính $a$, với tâm tại điểm $(a, 0)$ (Hình 3). Vị trí của hình bán nguyệt và bán kính của nó thay đổi khi tham số $a$ thay đổi. Hình 3 cho thấy rõ rằng đối với một số giá trị $a$ hình bán nguyệt không cắt đường $y = 1 - x$ (hình bán nguyệt nằm dưới đường thẳng), đối với các giá trị khác $a$ hình bán nguyệt cắt đường thẳng tại hai điểm (hình bán nguyệt nằm ở vùng đầu giữa), đối với giá trị thứ ba $a$ hình bán nguyệt cắt đường thẳng tại một điểm (hình bán nguyệt nằm trong vùng màu đỏ trở lên), và đối với một số giá trị $a$ hình bán nguyệt chạm vào đường thẳng (hình bán nguyệt ngăn cách phần đầu và vùng màu nâu).

Chúng ta xét trường hợp hình bán nguyệt chạm đường $y = 1 - x$. Từ những cân nhắc hình học, chúng ta kết luận rằng khoảng cách từ tâm của hình bán nguyệt này đến điểm giao nhau của đường thẳng $y = 1 - x$ với trục abscissa bằng $a\sqrt{2}$. Do đó $a + a\sqrt{2} = 1$, tức là trường hợp tiếp tuyến xảy ra tại $a = \sqrt{2} - 1$. Điều này có nghĩa là đối với $a < \sqrt{2} - 1$ phương trình không có lời giải (vùng màu xanh lam), nhưng đối với $a = \sqrt{2} - 1$ nó chỉ có lời giải, được tìm thấy từ các cân nhắc hình học: $x = a + \frac{a\sqrt{2}}{2}$ (xem Hình 3), từ đó chúng ta thu được $x = \frac{\sqrt{2}}{2}$.

Hình bán nguyệt đi qua điểm $(1, 0)$ trên Hình 3 tương ứng với giá trị của tham số $a = \frac{1}{2}$. Điều này có nghĩa là đối với $\sqrt{2} - 1 < a \leqslant \frac{1}{2}$ phương trình có hai lời giải:

$$x_1 = \frac{a + 1 - \sqrt{a^2 + 2a - 1}}{2},$$
$$x_2 = \frac{a + 1 + \sqrt{a^2 + 2a - 1}}{2}$$

(các nghiệm được tìm thấy bằng cách sử dụng phương trình đại số lời giải đã cho). Cuối cùng, nếu $a \geqslant \frac{1}{2}$ thì phương trình có một lời giải $x = x_1$ duy nhất (kể từ $x_1 < x_2$).

⟦folio 25⟧

Đáp số: nếu $a < \sqrt{2} - 1$ thì không có giải pháp nào;
nếu $a = \sqrt{2} - 1$, thì $x = \frac{\sqrt{2}}{2}$;
nếu $\sqrt{2} - 1 < a \leq \frac{1}{2}$,
thì $x_{1,2} = \frac{a+1 \pm \sqrt{a^2+2a-1}}{2}$.

Nếu như
$a > \frac{1}{2}$, rồi $x = \frac{a+1 - \sqrt{a^2+2a-1}}{2}$.

Hãy thử tự mình giải phương trình đại số đã đề xuất bằng nghiên cứu tương ứng, bạn sẽ thấy suy luận hình học trong trường hợp này vừa rõ ràng vừa đẹp mắt hơn.

NHIỆM VỤ

Chúng tôi đã xem xét một số ví dụ về phương trình lời giải với một tham số. Một số bạn thích chúng hơn, số khác thì ít hơn, nhưng có một điều chắc chắn: nếu bạn xem xét cẩn thận những ví dụ này bằng bút chì trên tay (như tập hợp biên tập của tạp chí của chúng tôi đã khuyên ở số 1), thì bạn đã hiểu được định nghĩa về sự leo thang. Bạn muốn chắc chắn về điều này? Tự giải phương trình sau với tham số $a$:

1. $a^2 - \frac{a^2-1}{2x-x^2} = \frac{x+2}{x-2}$.
2. $\sqrt{x+a} = a - \sqrt{x}$.
3. $\sqrt{x-2a} - \sqrt{x-a} = 2$.
4. $x + \sqrt{x^2-x} = a$.
5. $\sin(a+x) + \sin x = \cos \frac{a}{2}$.
6. $\sin^2 x + 4 \sin x + a = 0$.
7. $\sin x + 2 \cos ax = 3$.
8. $\log_{\sqrt{x}} a \log_{a^2} \frac{a^2-4}{2a-x} = 1$.
9. $\frac{\log_x(2a-x)}{\log_x 2} + \frac{\log_a \sqrt{x}}{\log_a 2} = \frac{1}{\log_{a^2}-1}$.
10. $\log_{\frac{1}{2}}(2 \sin x) + a \log_{\frac{1}{2}} \sin x + 3 = 0$.

4 Lượng tử số 9
