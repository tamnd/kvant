---
id: 1990-1-bashmakov-o-postulate-bertrana-1dfbbf88
issue: kvant_1990_1
year: 1990
number: "1"
title: Về định đề Bertrand
authors:
  - Башмаков М. И.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 61
page_last: 64
page_labels: 59-62
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 8110da9ecbdd382344d63599d5bd8ab121562ed1c5127eef2a237e3239cbebf6
prompt_sha256: draft-1
translated_from: content/ru/1990/01/articles/14_bashmakov-o-postulate-bertrana-1dfbbf88.md
source_content_sha256: 3e4c9002bab11faa20f58765f1b3761a683d7ad1b84653ffc8f9b2dbaad184e9
translation_model: draft
translation_run: vi-draft-gaps-2026-11-01
translation_quality: draft
---

⟦folio 59⟧

---
running_head:
folio:
---

Về tiên đề
Bertrand
Tiến sĩ Khoa học Vật lý và Toán học
M. BASHMAKOV

Trong số 69 công trình của Pafnuty Lvovich Chebyshev, có hai công trình đóng vai trò đặc biệt quan trọng trong sự phát triển của lý thuyết số. Những tác phẩm này: “Xác định số nguyên tố không vượt quá một giá trị cho trước” và “Về số nguyên tố” do ông viết khi còn trẻ, dành cho câu hỏi khó nhất trong lý thuyết số, sự phân bố của các số nguyên tố.

Phần thứ hai trong số chúng chứa các bất đẳng thức giúp tính toán khá chính xác số lượng số nguyên tố không vượt quá một giá trị nhất định.

Người đọc có thể thắc mắc, logarit có liên quan gì đến số nguyên tố? Đây là công lao của Chebyshev, ông đã chỉ ra cách

nhưng để ước tính số lượng số nguyên tố trong một đoạn cho trước của chuỗi tự nhiên, và đặc biệt, thực tế sau đã được chứng minh: giữa x và 2x (trong đó x > 1) luôn có ít nhất một số nguyên tố. Tuyên bố này được đưa ra bởi nhà toán học nổi tiếng người Pháp Bertrand, người đã thử nghiệm nó trong các bảng số nguyên tố hiện có, nhưng không thể chứng minh được và chấp nhận nó như một cái cớ.

Chúng tôi sẽ theo dõi những ý tưởng chính của Chebyshev đã dẫn ông đến những ước tính này, sau đó đề xuất một loạt bài toán, lời giải cho phép người đọc (đủ quen thuộc với tính chất của logarit) xây dựng lại bằng chứng của Chebyshev về lệnh ân xá của Bertrand và thu được bất đẳng thức về số lượng số nguyên tố không vượt quá một giá trị nhất định.

Người đọc có thể thắc mắc, logarit có liên quan gì đến số nguyên tố? Đây là công lao của Chebyshev, ông đã chỉ ra cách

⟦folio 60⟧

---
running_head:
folio:
---

Bạn có thể sử dụng các hàm phân tích phổ biến - căn bậc, logarit - khi nghiên cứu bài toán về số nguyên. Nếu muốn tìm hiểu xem có ít nhất một số nguyên tố trong khoảng từ $n$ đến $2n$ hay không, thì chúng ta có thể tiến hành như sau:

1) nghĩ ra một số hàm $y=f(x)$ của đối số thực $x$, hàm này sẽ không thay đổi giá trị của nó trong khi $x$ chạy qua đoạn giữa các số nguyên tố lân cận và sẽ nhận nhiều giá trị hơn khi chuyển qua một số nguyên tố;

2) chứng minh các bất đẳng thức cho hàm tương đối $f$, điều này sẽ giúp ước tính chính xác tốc độ tăng trưởng của nó.

Đối với hàm được chọn theo cách này, hiệu $f(2n)-f(n)$ sẽ là số dương khi và chỉ nếu hàm $f$ trả về khi di chuyển từ $n$ đến $2n$, nghĩa là nếu có ít nhất một số nguyên tố nằm giữa $n$ và $2n$.

Điều kiện đầu tiên rất dễ được thỏa mãn. Chúng ta có thể xem xét hàm sau: hãy ký hiệu bằng $\pi(x)$ số lượng số nguyên tố không vượt quá $x$.

Ví dụ: $\pi(1)=0$ (một không được coi là số nguyên tố), $\pi(3)=2$, $\pi(9)=4$, $\pi(9,5)=4$, $\pi(10,9)=4$, $\pi(11)=5$, v.v.

Tất nhiên, nếu chúng ta có thể chứng minh được điều đó

$$\pi(2x)-\pi(x)>0,$$

chúng ta sẽ chứng minh và Bertrand sẽ hành động, vì

$$\pi(2x)-\pi(x)$$

biểu thị chính xác số lượng số nguyên tố có trong khoảng từ $x$ đến $2x$. Tuy nhiên, không dễ để đưa ra ước tính chính xác cho $\pi(x)$, và Chebyshev cho lời giải này bài toán đã đề xuất xem xét một hàm mà khi được chuyển qua sẽ trả về một số nguyên tố không phải bằng một, như $\pi(x)$, mà sai hơn. Ông đã nghiên cứu chức năng

$$\theta(x)=\log 2+\log 3+\log 5+\ldots=\sum_{p\leqslant x}\log p$$

($\theta(x)=0$ tại $x<2$)

- tổng logarit của tất cả các số nguyên tố không vượt quá số trước đó, thủ tục Bertrand tương đương với bất đẳng thức sau:

$$\theta(2x)-\theta(x)>0.$$

(1)

Để ước lượng hàm $\theta(x)$ và chứng minh (1), Chebyshev đã sử dụng hàm phụ $T(x)$:

$$T(x)=\log 2+\log 3+\ldots=\sum_{n\leqslant x}\log n.$$

Hàm $T(x)$ là logarit của tích của tất cả các số nguyên, không vượt quá chúng. Chebyshev đã chỉ ra rằng hàm $\theta(x)$ và $T(x)$ có ​​liên quan với nhau bởi đẳng thức đáng chú ý sau:

$$T(x)=\theta(x)+\theta(\sqrt{x})+\theta(\sqrt[3]{x})+\ldots$$

$$+\theta\left(\frac{x}{2}\right)+\theta\left(\sqrt{\frac{x}{2}}\right)+\theta\left(\sqrt[3]{\frac{x}{2}}\right)+\ldots$$

$$+\theta\left(\frac{x}{3}\right)+\theta\left(\sqrt{\frac{x}{3}}\right)+\theta\left(\sqrt[3]{\frac{x}{3}}\right)+\ldots$$

(2)

trong đó tổng của đối tượng là khi đối số $\sqrt[k]{x/m}$ trở thành nhỏ hơn hai và giá trị $\theta(\sqrt[k]{x/m})$ trở thành 0. Hàm $T$ đã được biết đến từ thời Euler, và rất lâu trước Chebyshev, các bất đẳng thức đã được chứng minh giúp người ta có thể ước tính khá chính xác bậc tăng trưởng của $T$.

Từ những bất đẳng thức này, Chebyshev thu được bất đẳng thức cho $\theta(x)$ có dạng

$$Ax+v_1(x)<\theta(x)<\frac{6}{5}Ax+v_2(x),$$

(3)

trong đó $A$ là một hằng số nào đó và các số hạng bổ sung $v_1(x)$ và $v_2(x)$ cho $x$ lớn nhỏ hơn đáng kể so với $x$. Điều này đã đủ để chứng minh bất đẳng thức $\theta(2x)-\theta(x)>0$ đối với $x$ lớn hơn một số $x_0$ (ở Chebyshev $x_0=160$). Đối với $x$, nhỏ hơn $x_0$, vừa phải

*) Ở đây và mọi nơi bên dưới, logarit được lấy về cơ số $e$ - đây được gọi là logarit tự nhiên.

⟦folio 61⟧

---
running_head:
folio:
---

Sự phát triển hơn nữa về ý tưởng của con người đã dẫn đến kết quả sau: đối với $x \geq 48$ $\theta\left(\frac{9}{8}x\right) - \theta(x) > 0$, tức là bắt đầu từ vị trí được chỉ định, giữa $x$ và $\frac{9}{8}x$ luôn có ít nhất một số nguyên tố.

Bạn có thể theo dõi lập luận của Chebyshev chi tiết hơn bằng cách giải các câu sau bài toán 1-5.

Để biểu thị $T(x)$ theo $\theta(x)$, thuận tiện đưa ra một hàm phụ trợ khác. Đặt $p^{a_p}$ là mức cao nhất của $p$ không vượt quá $x$. Hãy xác định hàm $\psi$ như thế này:

$$\psi(x) = a_2 \log 2 + a_3 \log 3 + a_5 \log 5 + \dots = \sum_{p \leq x} a_p \log p.$$

Rõ ràng $\psi(x)$ là logarit của bội số chung nhỏ nhất của tất cả các số nguyên, không vượt quá $\psi$. Bài toán 1. Chứng minh rằng

$$T(x) = \psi(x) + \psi\left(\frac{x}{2}\right) + \psi\left(\frac{x}{3}\right) + \dots$$

Bây giờ chúng ta cần kết nối hàm $\psi$ và $\theta$.

Bài toán 2. Chứng minh rằng

$$\psi(x) = \theta(x) + \theta\left(\sqrt{x}\right) + \theta\left(\sqrt[3]{x}\right) + \theta\left(\sqrt[4]{x}\right) + \dots$$

Bằng cách giải bài toán 1 và 2, bạn cũng sẽ thiết lập được số thực $e$, số thực này cho mọi số tự nhiên $n$

$$\left(\frac{n+1}{e}\right)^n < n! < n\left(\frac{n}{e}\right)^n$$

(trong đó $n! = 1 \cdot 2 \cdot 3 \cdot \dots \cdot n$).

Đối với lời giải bài toán này, sẽ rất hữu ích khi chỉ ra rằng mỗi số

$$a_n = \left(\frac{n+1}{n}\right)^n$$

biến của mỗi số

$$b_n = \left(\frac{n+1}{n}\right)^{n+1};$$

suy ra rằng có một số $e$ lớn hơn tất cả $a_n$ và nhỏ hơn tất cả $b_n$. Đây là con số mà chúng ta đang tìm kiếm (một số tính chất của nó đã được thảo luận trên trang cuối cùng của tạp chí số 1 năm 1971 của chúng ta).

Giải bài toán này, bạn cũng thu được các bất đẳng thức cho $T(x)$:

$$(x-1)(\log(x-1) < T(x) < (x+1)\log x-x).$$

Bản thân Chebyshev đã sử dụng các bất đẳng thức chính xác hơn.

Từ ước tính cho $T(x)$, Chebyshev thu được ước tính cho $\psi(x)$ và sau đó cho $\theta(x)$.

Để biểu thị $\psi$ theo $T$, Chebyshev thay thế như sau. Hãy xem xét số tiền

$$S = T(x) - T\left(\frac{x}{2}\right) - T\left(\frac{x}{3}\right) - T\left(\frac{x}{5}\right) + T\left(\frac{x}{30}\right).$$

Hãy sử dụng kết quả bài toán 1 và rút gọn số tiền này về dạng sau:

$$S = A_1 \psi(x) + A_2 \psi\left(\frac{x}{2}\right) + A_3 \psi\left(\frac{x}{3}\right) + \dots$$

Bài toán 4. Kiểm tra xem các hệ số $A_1, A_2, A_3$, ... có thay đổi theo khoảng thời gian 30 không và đối với ba mươi giá trị đầu tiên của $n$, các hệ số $A_n$ tạo thành chuỗi sau:

1, 0, 0, 0, 0, -1, 1, 0, 0, -1, 1, -1, 1, 0, -1, 0, 1, -1, 1, -1, 0, 0, 1, -1, 0, 0, 0, 0, 1, -1, 1.

Từ đó chúng ta có thể thấy rằng tổng $S$ được viết dưới dạng một chuỗi xen kẽ $S = \psi(x) - \psi\left(\frac{x}{6}\right) + \psi\left(\frac{x}{7}\right) - \psi\left(\frac{x}{10}\right) + \psi\left(\frac{x}{11}\right) - \dots$.

Vì $\psi$ là hàm không giảm,

$$S = \psi(x) - \left(\psi\left(\frac{x}{6}\right) - \psi\left(\frac{x}{7}\right)\right) - \left(\psi\left(\frac{x}{10}\right) - \psi\left(\frac{x}{11}\right)\right) \dots \leqslant \psi(x).$$

Tương tự

$$S = \psi(x) - \psi\left(\frac{x}{6}\right) + \left(\psi\left(\frac{x}{7}\right)\right) - \psi\left(\frac{x}{10}\right) + \dots \geqslant \psi(x) - \psi\left(\frac{x}{6}\right).$$

Từ (2), chúng ta ngay lập tức nhận được bất đẳng thức cho $\psi$, ước tính kích thước của nó, vì chúng ta biết các bất đẳng thức cho $T$ và thu được ước tính cho $\psi$ đến $S$, tức là kết hợp các giá trị $T$. Ước tính này sẽ có dạng sau: $\psi(x) \geqslant A_1(x) + \omega_1(x)$, trong đó $\omega_1$ tăng chậm hơn $x$, tức là.

$$\lim_{x \to \infty} \frac{\omega_1(x)}{x} = 0.$$

Để có được ước tính từ trên, người ta phải loại bỏ $\psi\left(\frac{x}{6}\right)$. Áp dụng bất đẳng thức (6) cho $\frac{x}{6}, \frac{x}{6^2}, \frac{x}{6^3}$, v.v. và cộng lại, chúng ta tìm thấy bất đẳng thức cho $\psi(x)$ thuộc loại $\psi(x) \leqslant A_2x + w_2(x)$, trong đó $w_2$ tăng chậm hơn $x$.

Bài toán 5. Chứng minh rằng

$$\psi(x) - 2\psi\left(\sqrt{x}\right) \leqslant \theta(x) \leqslant \psi\left(\sqrt{x}\right).$$

Từ đó chúng ta đã có được những ước tính cần thiết (3).

Kết quả của Chebyshev không chỉ ngụ ý rằng hành động của Bertrand là đúng, mà quan trọng hơn, chúng mang lại những bất đẳng thức cho phép ước tính chính xác hàm $\pi(x)$:

$$c_1 \frac{x}{\log x} < \pi(x) < c_2 \frac{x}{\log x},$$

trong đó $c_1$ và $c_2$ không dương.

⟦folio 62⟧

---
running_head:
folio:
---

hằng số *). Bạn có thể chứng minh những bất đẳng thức đó bằng cách giải bài toán sau.

Bài toán 6. Chứng minh rằng
$$\frac{\psi(x)}{\log x} < \pi(x) < \frac{\psi(x) + \theta(x)}{\log x}.$$

*) Logarit ở đây có thể ở cơ số bất kỳ $a$, lớn hơn một; từ $a$ chỉ có giá trị của hằng số phụ thuộc $c_1$ Và $c_2$, bởi vì $\log_b x$ thu được từ $\log_a x$ nhân với một số không đổi $\log_a b$. Sẽ tự nhiên hơn khi sử dụng logarit tự nhiên, vì đây là hàm $x/\log_e x$ tương đương $\pi(x)$ nói chung $x$, tức là $$\lim_{x \to \infty} \frac{\pi(x)}{x/\log_e x} = 1.$$ Điều này đã được chứng minh rất lâu sau đó, và từ công trình của chính Chebyshev, người ta chỉ suy ra rằng mối quan hệ $\pi(x)$ ĐẾN $x/\log_e x$ nằm trong khoảng từ 0,921 đến 1,106 và nếu giới hạn tại $x \to \infty$ tồn tại thì nó bằng một.

Sóng trên mặt nước và “Du khách nước ngoài” của N. Roerich

(Xem phần đầu ở trang 24)

Còn góc $\alpha$ thì sao? Tất cả những người được phỏng vấn đều đồng ý rằng nó nằm đâu đó trong khoảng $90^\circ < 2\alpha < 180^\circ$ (con tàu trong hình khá điển hình). Như vậy,
$$\frac{\sqrt{2}}{2} = \sin 45^\circ < \sin \alpha < \sin 90^\circ = 1.$$ (7)

Bây giờ chúng ta có mọi thứ để ước tính tốc độ và sóng bề mặt của con tàu.

Kết quả

Thay các giá trị $h$, $\lambda$ và $\sin \alpha$ từ (5), (6), (7) vào công thức (1) và (2), ta thu được
$$v \geq \sqrt{\frac{2 \cdot 9,8 \text{ m/c}^2 \cdot 0,26 \text{ m}}{1 \div \sqrt{2}/2}} \approx 5,1 \div 7,25 \text{ m}^2/\text{c}^2 \approx 2,25 \div 2,7 \text{ m/c},$$ (8)

$$u = \sqrt{\frac{9,8 \text{ m/c}^2 \cdot 0,34 \text{ m}}{2\pi}} \approx 0,7 \text{ m/c}.$$ (9)

Bây giờ chúng ta ngạc nhiên nhận thấy rằng sự tương ứng (8) và (9) không tương thích với bất đẳng thức (4). Thật vậy, xét theo độ cao của sóng mũi tàu, con tàu trôi với tốc độ $v$ không khác 2,25 m/s, và nếu chúng ta tập trung vào bề mặt hình tròn của sóng, gần như đồng tâm trong hình, thì tốc độ của con tàu sẽ nhỏ hơn nhiều so với tốc độ của những con sóng này $u = 0,7 \text{ m/c}$, vốn đã nhỏ hơn $v$.

Với một ngoại hình nhất định, bạn sẽ tìm thấy nhiều điểm không chính xác về mặt vật lý tương tự trong các tác phẩm nghệ thuật khác (rõ ràng, điều này là do anh ta có bộ quy tắc và luật riêng của mình). Khi đó, bạn không chỉ có thể đặt chúng xuống và thỏa mãn về mặt thẩm mỹ mà còn có thể nói chuyện với em trai mình về các định luật vật lý bằng cách sử dụng những hình ảnh minh họa rất hấp dẫn.
