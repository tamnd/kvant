---
id: 1977-7-ionin-plotkin-srednee-znachenie-funktsii-d4d6aa54
issue: kvant_1977_7
year: 1977
number: "7"
title: Giá trị trung bình của hàm
authors:
  - Ионин Ю. И.
  - Плоткин А. И.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 28
page_last: 32
page_labels: 26-30
tag: 1YAJ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 40529bf0c58ae11d4a0db69f887c9bb787ca30283333aebb9a1ba158759fe10e
prompt_sha256: draft-1
translated_from: content/ru/1977/07/articles/08_ionin-plotkin-srednee-znachenie-funktsii-d4d6aa54.md
source_content_sha256: f8bc7acc9952579c4b2606897992c7bb608a361547d6e3b4dcdb4e3ce88c4830
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 26⟧

Giá trị trung bình của hàm

Trong bài viết này, khái niệm trung bình số học $n$ của các số được khái quát hóa cho các hàm xác định trên đoạn thẳng, hình tròn và hình cầu. Ngoài ra, nó còn giải được bài toán M394 («Kvant», 1976, số 7).

1. Trên tập hữu hạn

Phát biểu tại buổi họp lớp, Makar Livanov nói: “Hãy đấu tranh để đảm bảo rằng thành tích của mọi học sinh trong lớp chúng ta đều trên mức trung bình!” Rõ ràng, Makar không giỏi toán lắm. Hãy tìm ra nó.

Như đã biết, trung bình số học $n$ của các số $x_1, x_2, \dots, x_n$ là số $M = M(x_1, x_2, \dots, x_n)$ cho bởi đẳng thức

$$M(x_1, x_2, \dots, x_n) = \frac{x_1 + x_2 + \dots + x_n}{n}.$$ (1)

Theo sự công nhận của Makar, chúng ta sẽ phải đạt được sự thỏa mãn đồng thời các bất đẳng thức $x_1 > M, x_2 > M, \dots, x_n > M$. Cộng các bất đẳng thức $n$ này, ta thu được mâu thuẫn với (1).

Chúng ta hãy lưu ý một số tính chất quan trọng của trung bình số học:

I. $M(x_1 + y_1, x_2 + y_2, \dots, x_n + y_n) = M(x_1, x_2, \dots, x_n) + M(y_1, y_2, \dots, y_n)$.

II. $M(\alpha x_1, \alpha x_2, \dots, \alpha x_n) = \alpha M(x_1, x_2, \dots, x_n)$.

III. $\min(x_1, x_2, \dots, x_n) \leqslant M(x_1, x_2, \dots, x_n)$.

Trong sợi 1. Chứng minh tính chất I-III.

U 2. Chứng minh bất đẳng thức $C_{2n}^n > \frac{2^{2n-1}}{n}$ cho $n > 1$. Điều này dễ thực hiện bằng phương pháp quy nạp toán học, nhưng có thể thực hiện được bằng tính chất III.

Thuộc tính III thường được sử dụng như sau: để xác định rằng trung bình $x_1, x_2, \dots, x_n$ là các số lớn hơn $d$, chỉ cần kiểm tra rằng $M(x_1, x_2, \dots, x_n) > d$ là đủ. Ví dụ: hãy xem xét bài toán, được đưa ra tại Olympic Toán học toàn Liên minh X.

Bài toán 1. Bằng cách nào đó có 50 chiếc đồng hồ tròn chạy đều trên một bàn tròn. Chứng minh rằng tại một số thời điểm, tổng khoảng cách từ tâm bàn $O$ đến hai đầu kim phút tại thời điểm $t$ là một giờ, và sau $d$ là tổng khoảng cách từ điểm $O$ đến tâm đồng hồ. Chúng ta cần chứng minh rằng $f(t) > d$ bằng $t$ tại một số điểm. Chúng ta sẽ chỉ ra rằng có $t_0$ thỏa mãn $M(f(t_0), f(t_0 + \frac{1}{2})) > d$.

Điều này có nghĩa là một trong những khoảnh khắc $t_0$, $t_0 + \frac{1}{2}$ là đặc biệt.

Chúng ta hãy biểu thị bằng $O_i$ tâm của $i$ giờ, bằng $A_i$ điểm cuối kim phút của đồng hồ này tại một số thời điểm $t$, bằng $B_i$ điểm cuối kim phút của cùng giờ nửa giờ sau, tức là tại thời điểm $t + \frac{1}{2}$. Vì, theo điều kiện, tất cả các đồng hồ đều “chạy chính xác”, nên có một thời điểm $t_0$ tại đó các điểm $O, A_1$ và $B_1$ không nằm trên cùng một đường thẳng. Xét tam giác $OA_1B_1$ và đường trung tuyến $OO_1$ trong đó (Hình 1). Dễ dàng chứng minh rằng trong một tam giác bất kỳ, độ dài đường trung tuyến nhỏ hơn một nửa tổng chiều dài các cạnh mà nó nằm giữa (hãy chứng minh điều đó!). Do đó, tại thời điểm $t_0$ chúng ta có

⟦folio 27⟧

Cơm. 1.

$$\frac{OA_1 + |OB_1|}{2} > |OO_1|.$$ Đối với số giờ còn lại tại thời điểm này $$\frac{|OA_i| + |OB_i|}{2} \geq |OO_i|$$ (tại sao chỉ $\geq$ mà không phải >?). Cộng 50 bất đẳng thức, ta được $M(f(t_0), f(t_0 + \frac{1}{2})) > d$.

2. Trên phân khúc

Trong bài toán 1 hóa ra là đủ để ước tính giá trị trung bình số học của hai giá trị hàm. Có thể xem xét mức trung bình của tất cả các giá trị? Để giống với định nghĩa của khái niệm này, chúng ta hãy đưa ra ý nghĩa hình học cho giá trị trung bình $n$ của các số dương $x_1, x_2, \dots, x_n$.

Chia một số đoạn $[a; b]$ thành $n$ các phần bằng nhau và xây dựng một funkru bậc bao gồm các hình chữ nhật, đáy của chúng là các đoạn thu được có chiều dài $\frac{b-a}{n}$ và chiều cao tương ứng là $x_1, x_2, \dots, x_n$ (Hình 2). Diện tích của hàm bước này là $M(x_1, x_2, \dots, x_n) \cdot (b-a)$. Do đó, $M(x_1, x_2, \dots, x_n)$ là chiều cao của hình chữ nhật có đáy $[a; b]$, có diện tích bằng đường cong tương ứng của hình thang tuyến tính (Hình 3). Vì trong trường hợp đang xét diện tích

Cơm. 2.

hình thang này bằng $$\int_a^b f(x) \, dx$$ (Đại số và các phần tử giải tích 10, mục 101), $M(f)$ được xác định theo công thức

$$M(f) = \frac{1}{b-a} \int_a^b f(x) \, dx. \quad (2)$$

Định nghĩa (2) không chỉ phù hợp với hàm liên tục và không âm mà còn phù hợp với bất kỳ hàm nào được xác định trên $[a; b]$, mà vế phải của đẳng thức (2) có ý nghĩa.

Vì vậy định nghĩa giá trị trung bình có những tính chất tương tự như tính chất I-III:

I'. $M(f + g) = M(f) + M(g)$.

II'. $M(\alpha f) = \alpha M(f)$.

III. $$\min_{[a; b]} f \leqslant M(f) \leqslant \max_{[a; b]} f.$$ Bài tập 3. Chứng minh tính chất I'—III'.

Biểu thức từ I'-III' của tính chất IV'. Nếu $f(x) \leqslant g(x)$ với tất cả $x \in [a; b]$ thì $M(f) \leqslant M(g)$.

Bạn đã xem giá trị trung bình của một hàm trên một đoạn trong ghi chú “Buffon's Needle” của A. Vilenkin («Kvant», 1977, số 5). Hãy để chúng tôi đưa ra một ví dụ khác về việc áp dụng khái niệm này.

Bài 2. Trên mặt phẳng dữ liệu có các vectơ $\vec{a}, \vec{b}, \vec{c}, \vec{d}$ có tổng bằng 0. Chứng minh bất đẳng thức

$$|\vec{a}| + |\vec{b}| + |\vec{c}| + |\vec{d}| \geqslant |\vec{a} + \vec{d}| + |\vec{b} + \vec{d}| + |\vec{c} + \vec{d}|. \quad (3)$$

lời giải của chúng tôi về bài toán này sẽ dựa trên biến thể một chiều của nó:

⟦folio 28⟧

Cơm. 3.

Bài tập 5. Chứng minh rằng nếu $a, b, c, d$ là số thực có tổng bằng 0 thì $|a| + |b| + |c| + |d| \geq |a+d| + |b+d| + |c+d|$.

Lời giải. Nếu trong (3) các vectơ $\vec{a}, \vec{b}, \vec{c}, \vec{d}$ được thay thế bằng hình chiếu của chúng lên một trục nào đó (“Hình học 9”), chúng ta nhận được (4). Một ý tưởng nảy sinh: chứng minh (3) bằng cách xem xét hình chiếu của các vectơ $\vec{a}, \vec{b}, \vec{c}, \vec{d}$ này lên tất cả các trục có thể. Hãy thử thực hiện nó.

Đặt $\vec{p}$ là một vectơ. Xin giới thiệu hàm phụ $p$ như sau: cố định một số trục $l_0$; chúng ta hãy biểu thị bằng $p(\alpha)$ hình chiếu của vectơ $\vec{p}$ lên trục $l$, tạo thành một góc $\alpha$ với trục $l_0$ (Hình 4). Nếu $\varphi$ là góc giữa vectơ $\vec{p}$ và trục $l_0$, thì $p(\alpha) = |\vec{p}| \cos(\varphi - \alpha)$.

Xét giá trị trung bình $M(|p|)$ của hàm $\alpha \rightarrow |p(\alpha)|$ trên khoảng $[0; 2\pi]$. Từ định nghĩa (2)

$$M(|p|) = \frac{1}{2\pi} \int_{0}^{2\pi} |p(\alpha)| d\alpha =$$

$$= \frac{1}{2\pi} \int_{0}^{2\pi} |\vec{p}| \cos(\varphi - \alpha)| d\alpha =$$

$$= \frac{|\vec{p}|}{2\pi} \int_{0}^{2\pi} |\cos(\varphi - \alpha)| d\alpha.$$

Hãy chứng minh sự tồn tại của $k \neq 0$ sao cho với mọi vectơ $\vec{p}$ đẳng thức

$$M(|\vec{p}|) = k |\vec{p}|.$$

(6)

Theo (5), đủ để chứng minh rằng tích phân $\int_{0}^{2\pi} |\cos(\varphi - \alpha)| d\alpha$ không phụ thuộc vào vectơ $\vec{p}$, nghĩa là không phụ thuộc vào góc $\varphi$.

$$\int_{0}^{2\pi} |\cos(\varphi - \alpha)| d\alpha = \int_{0}^{2\pi} |\cos(\alpha - \varphi)| d\alpha =$$

$$= \int_{0}^{2\pi} |\cos \alpha| d\alpha = \int_{0}^{2\pi} |\cos \alpha| d\alpha =$$

$$= \int_{0}^{2\pi} |\cos \alpha| d\alpha + \int_{0}^{2\pi} |\cos \alpha| d\alpha + \int_{0}^{2\pi} |\cos \alpha| d\alpha + \int_{0}^{2\pi} |\cos \alpha| d\alpha.$$

(7)

Phép tính này sử dụng hai tính chất của tích phân:

$$\int_{a}^{b} f(x + p) dx = \int_{a+p}^{b+p} f(x) dx,$$

$$\int_{a}^{b} f(x) dx = \int_{a}^{c} f(x) dx + \int_{c}^{b} f(x) dx$$

⟦folio 29⟧

"Đại số và nguyên tắc phân tích 10", đoạn 106 và bài toán số 512). Điểm trọng tâm của phép tính là sử dụng thực tế rằng $2\pi$ là chu kỳ của hàm $\alpha \rightarrow \cos \alpha$.

Tích phân $\int_0^{2\pi} |\cos \alpha| d\alpha$ có thể được tính (nó bằng 4), nhưng điều quan trọng đối với chúng ta là nó không phụ thuộc vào $\varphi$ và khác 0.

Nếu $\vec{a} + \vec{b} + \vec{c} = 0$, thì với bất kỳ $\alpha$ nào chúng ta có $a(\alpha) + b(\alpha) + c(\alpha) + d(\alpha) = 0$. Có hiệu lực (4)

$$|a(\alpha)| + |b(\alpha)| + |c(\alpha)| + |d(\alpha)| \geq |a(\alpha) + d(\alpha)| + |b(\alpha) + d(\alpha)| + |c(\alpha) + d(\alpha)|.$$

(8)

Vì (8) thỏa mãn với mọi $\alpha \in [0; 2\pi]$ nên nó suy ra từ tính chất IV' và I'

$$M(|a|) + M(|b|) + M(|c|) + M(|d|) \geq M(|a+d|) + M(|b+d|) + M(|c+d|).$$

Từ (6)

$$k|\vec{a}| + k|\vec{b}| + k|\vec{c}| + k|\vec{d}| \geq k|\vec{a}+d| + k|\vec{b}+d| + k|\vec{c}+d|.$$

Giảm $k$, ta thu được (3).

3. Trên hình tròn và hình cầu

Bài 3. Trong không gian dữ liệu có các vectơ $\vec{a}, \vec{b}, \vec{c}, \vec{d}$ có tổng bằng 0. Chứng minh bất đẳng thức (3) cho chúng.

Tôi xin chứng minh (3) bằng cách chuyển “giải tích phẳng” (từ bài 2) sang không gian. Để làm được điều này, bằng cách nào đó chúng ta cần xác định giá trị trung bình của mô hình chiếu vectơ lên ​​tất cả các trục có thể có trong không gian. Để giải thích cách thực hiện điều này, trước tiên hãy xem xét hàm được xác định trên một đường tròn có bán kính đơn vị.

Đặt $f$ là một hàm như vậy. Đối với $\alpha$ tùy ý, chúng tôi đặt $f(\alpha) = f(A)$, trong đó $A$ là điểm cuối của đường tròn của chúng tôi với số đo radian $\alpha$ (Hình 5). Vì vậy, chúng ta đã gán cho một hàm tùy ý $f$ được xác định trên vòng tròn đơn vị một hàm nhất định $f$,

xác định trên toàn bộ đường thẳng Rõ ràng, $f$ là hàm tuần hoàn có chu kỳ $2\pi$. Bây giờ chúng ta hãy xác định giá trị trung bình $M(f)$ của hàm $f$ trên đường tròn là giá trị trung bình của hàm $f$ trên đoạn [0; 2π].

Trong lời giải bài toán 2 đã cho, vai trò chính được thể hiện bởi sự bất đẳng thức của giá trị trung bình $M(|p|)$ theo hướng của vectơ $p$. Bất đẳng thức này là trường hợp một phần của tính chất chung sau đây của các giá trị trung bình của hàm số trên đường tròn:

$V'$. Đặt $f$ và $g$ là các hàm được xác định trên một đường tròn và có tối đa $\alpha$, giá trị này đối với bất kỳ $A$ đường tròn $g(A) = f(R^\alpha(A))$ nào (ở đây $R^\alpha$ là phép quay vectơ của một đường tròn đã cho theo một góc $\alpha$). Sau đó $M(g) = M(f)$.

Bài tập 6. Chứng minh tính chất $V'$.

Đến bài toán 3, xét trong không gian một hình cầu có bán kính đơn vị với tâm là gốc $O$. Đối với một hàm cho trên hình cầu này, giá trị trung bình có thể được xác định theo cách thỏa mãn các thuộc tính $I$ - $V'$. Ở đây chúng tôi không thể giải thích việc này được thực hiện như thế nào, vì để làm được điều này, chúng tôi sẽ phải giới thiệu nội hóa theo hình cầu. (Điều này có thể được thực hiện bằng cách sử dụng tổng giữa các khoảng theo cách tương tự như interAL được định nghĩa trên một dòng trong đoạn 104 của sách giáo khoa “Đại số và các yếu tố phân tích 10”.) Giả sử rằng giá trị trung bình $M(f)$ của hàm $f$ trên hình cầu được xác định bằng cách nào đó và các thuộc tính $I'$ - $V'$ được thỏa mãn. (Do đó, chúng ta coi việc gán tiên đề giá trị trung bình của hàm

⟦folio 30⟧

tsini trên quả cầu. Thật thú vị khi lưu ý rằng nó được xác định duy nhất bởi các “tiên đề” $I' - V'$.)

Đặt $p$ là một vectơ. Chúng ta hãy giới thiệu hàm phụ $p$ như sau: với bất kỳ điểm $A$ nào của hình cầu, chúng ta biểu thị bằng $p(A)$ hình chiếu của vectơ $p$ lên trục được xác định bởi vectơ $\vec{OA}$.

Xét giá trị trung bình $M(|p|)$ của hàm $A \rightarrow |p(A)|$ trên hình cầu. Hãy chứng minh sự tồn tại của $k \neq 0$ sao cho với mọi vectơ $p$ (6) đều thỏa mãn. Để làm điều này, sau khi suy ra các tính chất của $II'$, chỉ cần chứng minh rằng $|\vec{p}| = |\vec{q}|$ ngụ ý $M(|p|) = M(|q|)$ là đủ.

Làm bài tập 7. Chứng tỏ như vậy là đủ.

Hãy để $|\vec{p}| = |\vec{q}|$. Ta biểu thị bằng $R$ một phép quay nào đó của không gian quanh trục đi qua điểm $O$, biến tia có vectơ chỉ phương $\vec{q}$ thành tia có vectơ chỉ phương $p$. thì với bất kỳ điểm $A$ nào của hình cầu $q(A) = p(R(A))$. Từ $V'$ theo sau $M(|q|) = M(|p|)$.

Hơn nữa lời giải bài toán 3 nên lặp lại lời giải bài toán 2. (Bài tập 5 và bài toán 2, 3 sẽ cạn kiệt bài toán M394.)

4. Chiều dài trên chiều rộng

Ý tưởng dựa trên lời giải bài toán 2 và 3 có thể được sử dụng để tính chiều dài của một đa tuyến lồi đóng phẳng.

Đặt $J$ là một đường đứt quãng, $a_1, a_2, \dots, a_n$ các liên kết của nó. Chúng tôi sửa một số trục $l_0$. Đặt $l_\alpha$ là trục tạo thành một góc $\alpha$ với trục $l_0$. Chúng ta hãy biểu thị bằng $Ш(\alpha)$ “chiều rộng” của đường đứt nét theo hướng của trục $l_\alpha$, tức là độ dài hình chiếu của nó lên trục $l_\alpha$. Hóa ra là nếu bạn biết “chiều rộng” của đường đứt nét $J$ theo một hướng tùy ý, tức là có thể tính được hàm $\alpha \rightarrow Ш(\alpha)$, thì bạn có thể tìm thấy độ dài của nó $L$. Chúng tôi sẽ chỉ cho bạn cách làm điều đó.

Ta ký hiệu bằng $a_i(\alpha)$ độ dài hình chiếu của liên kết $a_i$ lên trục $l_\alpha$.

Bài tập 8. Chứng minh rằng $Ш(\alpha) = \frac{1}{2} [a_1(\alpha) + a_2(\alpha) + \dots + a_n(\alpha)]$.

Trong lời giải bài toán 2, giá trị trung bình của hàm $\alpha \rightarrow a_i(\alpha)$ tỷ lệ thuận với $|a_i|$. Từ (5) và (7), hệ số tỷ lệ bằng $\frac{1}{2\pi} \int_0^{2\pi} |\cos \alpha| d\alpha = \frac{2}{\pi}$.

Từ Bài tập 8 và các tính chất $I'$, $II'$, giá trị trung bình $M(Ш)$ của hàm $Ш$ bằng giá trị trung bình của hàm $\alpha \rightarrow a_i(\alpha)$. Kể từ đây,

$$M(Ш) = \frac{1}{2} \left( \frac{2}{\pi} |a_1| + \right. \\ + \frac{2}{\pi} |a_2| + \dots + \frac{2}{\pi} |a_n|) = \\ = \frac{1}{\pi} \left( |a_1| + |a_2| + \dots + |a_n| \right) = \frac{1}{\pi} L.$$

Từ đây và từ (2)

$$L = \pi \cdot M(Ш) = \pi \cdot \frac{1}{2\pi} \int_0^{2\pi} Ш(\alpha) d\alpha = \\ = \frac{1}{2} \int_0^{2\pi} Ш(\alpha) d\alpha (9)$$

Như vậy, biết hàm $Ш$, chúng ta có thể tìm được độ dài $L$ của đường đứt nét $J$.

Bài tập 9. Chứng minh rằng nếu độ dài tất cả các cạnh và các đường chéo của một đa giác lồi nhỏ hơn $d$ thì chu vi của đa giác đó nhỏ hơn $πd$.

Công thức (9) đúng cho mọi đường cong lồi phẳng khép kín. Phương pháp phác thảo để xác định chiều dài “thông qua chiều rộng” được đề xuất vào năm 1930 bởi nhà toán học nổi tiếng người Ba Lan G. Steinhuz.

5. chiều dài số tiền

Bài 4. Trên mặt phẳng dữ liệu có các vectơ $a_1, a_2, \dots, a_n$ có tổng độ dài bằng 1. Chứng minh rằng có thể chọn trung bình cho một số vectơ có tổng độ dài không nhỏ hơn $\frac{1}{\pi}$.

Hãy giải quyết bài toán này bằng cách làm theo kế hoạch được đề xuất bên dưới. Đặt $3$ là tập con của tập hợp $\{a_1, a_2, \dots\}$.
