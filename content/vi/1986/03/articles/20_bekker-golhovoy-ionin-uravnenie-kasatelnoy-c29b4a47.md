---
id: 1986-3-bekker-golhovoy-ionin-uravnenie-kasatelnoy-c29b4a47
issue: kvant_1986_3
year: 1986
number: "3"
title: phương trình tiếp tuyến
authors:
  - Беккер Б. М.
  - Гольховой В. М.
  - Ионин Ю. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 53
page_last: 56
page_labels: 51-54
tag: J3ND
lang: vi
source: kvant_digital
extraction: vision
content_sha256: bbdfbd76b66dde28dba1016851e9b62c45ac4c23e3dd4524393d2228aec95561
prompt_sha256: draft-1
translated_from: content/ru/1986/03/articles/20_bekker-golhovoy-ionin-uravnenie-kasatelnoy-c29b4a47.md
source_content_sha256: 9f801c24003d94724823597f2a228b0bfefa4dbfd1e1ac313be2d8e790a66e7c
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 51⟧

phương trình tiếp tuyến

V. M. BECKER,
V. M. GOLKHOVY,
Ứng viên khoa học sư phạm Yu. I. IONIN

Trong bài viết này, chúng tôi sẽ phân tích một số loại bài toán về chủ đề “Tangent”, thường được đưa ra trong các kỳ thi toán cụ thể.

Hãy nhớ rằng phương trình của đường thẳng có độ dốc $k$ và đi qua điểm $M(x_0; y_0)$ có thể viết là $y = k(x - x_0) + y$. Vì hệ số góc của tiếp tuyến với đồ thị hàm vi phân $y = f(x)$ tại điểm hoành độ $x_0$ bằng $f'(x_0)$ nên phương trình tiếp tuyến có dạng

$$y = f'(x_0)(x - x_0) + f(x_0).$$

Như vậy, để viết phương trình tiếp tuyến, bạn cần biết ba số: $x_0$, $f(x_0)$ và $f'(x_0)$. Hãy bắt đầu với bài toán, trong đó giá trị $x_0$ có thể dễ dàng tìm thấy từ điều kiện, sau đó tính toán $f(x_0)$, $f'(x_0)$.

Bài toán 1 (MSU, Khoa Tâm lý học, 1980). Tính diện tích tam giác giới hạn bởi các trục tọa độ và tiếp tuyến của đồ thị hàm số $y = \frac{x}{2x - 1}$ tại điểm hoành độ $x_0 = 1$.

Lời giải. Hãy tìm phương trình tiếp tuyến. Để làm điều này, chúng tôi tính toán tuần tự $f(1)$, $f'(x)$, $f'(1)$:

$$f(1) = 1, f'(x) = -\frac{1}{(2x - 1)^2}, f'(1) = -1.$$

Phương trình tiếp tuyến có dạng $y = -(x - 1) + 1$, tức là $y = -x + 2$.

Đường này cắt các trục tọa độ tại các điểm $A$ (2; 0) và $B$ (0; 2). Vậy diện tích cần tìm là $S_{AOB} = \frac{1}{2} |OA| \cdot |OB| = 2$.

Bài toán 2 (Đại học bang Krasnoi, Khoa Toán, 1980). Dây cung của parabol $y = -a^2x^2 + 5ax - 4$ tiếp xúc với đường cong $y = \frac{1}{1-x}$ tại điểm $x_0 = 2$ và bị chia đôi bởi điểm này. Tìm $a$.

Lời giải. Phương trình của chúng ta cho tiếp tuyến với đồ thị của hàm $f(x) = \frac{1}{1-x}$ tại điểm $M$ với hoành độ $x_0 = 2$:

$$f(2) = -1, f'(x) = \frac{1}{(1-x)^2}, f'(2) = 1,$$

nên phương trình tiếp tuyến là $y = x - 3$.

Giả sử rằng tiếp tuyến này cắt parabol đã cho tại các điểm $A$ và $B$. Trục hoành của các điểm $A$ và $B$ là nghiệm của phương trình $-a^2x^2 + 5ax - 4 = x - 3$, hoặc

$$-a^2x^2 + (5a - 1)x - 1 = 0.$$

Điểm $M$ là trung điểm của đoạn $AB$ khi và chỉ khi hoành độ bằng hoành độ thu được của các điểm $A$ và $B$. Sử dụng định lý Vieta, điều kiện này có thể được viết dưới dạng đẳng thức $\frac{5a - 1}{a^2} = 4$, đúng cho $a = 1$ và cho $a = \frac{1}{4}$. Vẫn còn phải kiểm tra xem, đối với các giá trị này, $a$ của đường parabol đã cho và đường thẳng $y = x - 3$ có giao nhau hay không, tức là liệu phương trình (1) có nghiệm hay không. Đối với $a = 1$, chúng ta thu được phương trình $-x^2 + 4x - 1 = 0$ với bộ mô tả dương và đối với $a = \frac{1}{4}$, chúng ta thu được phương trình $-\frac{1}{16}x^2 + \frac{1}{4}x - 1 = 0$ với bộ mô tả phủ định.

Vì vậy, $a = 1$.

Bài toán 3. Phương trình của chúng ta là tiếp tuyến của parabol $y = 2x^2 - x - 1$ tại một điểm có tọa độ 5, nếu biết tiếp tuyến này không đi qua điểm $M$ (1; -2).

Lời giải. Trong điều kiện bài toán, không phải trục hoành được xác định mà là tọa độ của điểm tiếp tuyến. Để tìm hoành độ lời giải $2x^2 - x - 1 = 5$. Chúng ta có hai nghiệm $x_1 = -\frac{3}{2}$, $x_2 = 2$. Hãy để $f(x) = 2x^2 - x - 1$. Sau đó $f'(x) = 4x - 1$, $f'(-\frac{3}{2}) = -7$, $f'(2) = 7$. Các phương trình tiếp tuyến của chúng ta là $y = -7(x + \frac{3}{2}) + 5$ và $y = 7(x - 2) + 5$, tức là $y = -7x - 5,5$ và $y = 7x - 9$.

⟦folio 52⟧

Thay tọa độ của điểm $M$ vào từng phương trình, ta thấy rằng tiếp tuyến thứ nhất không đi qua điểm $M$, nhưng tiếp tuyến thứ hai lại đi qua điểm này.

Vì vậy, đáp số: $y = -7x - 5, 5$.

Trong các bài toán 4, 5, 6, điều kiện xác định bởi tiếp tuyến cho phép chúng ta tìm giá trị tùy ý tại điểm tiếp tuyến, sau đó là hoành độ và tọa độ của điểm này.

Bài toán 4 (LSU, Khoa Sinh học, 1977). Một tiếp tuyến được vẽ bởi đồ thị của hàm $y = x^3 - x^2 - 13x + 4$ tại điểm phần tư thứ hai, trong đó hệ số góc bằng 3. Tìm giao điểm của tiếp tuyến này với các trục tọa độ.

Lời giải. Gọi $a$ là hoành độ của điểm tiếp tuyến. Theo điều kiện $f'(a) = 3$. Vì $f'(x) = 3x^2 - 2x - 13$, để tìm $a$, chúng ta thu được phương trình $3a^2 - 2a - 13 = 3$, có nghiệm $-2$ và $8/3$. Giá trị $a = 8/3$ phải bị loại bỏ (theo điều kiện bài toán điểm tiếp tuyến nằm trong quý thứ hai). Tại $a = -2$ điểm tiếp tuyến có tọa độ $(-2; 18)$ và nằm trong góc phần tư thứ hai. Phương trình tiếp tuyến là $y = 3x + 24$. Đường thẳng này cắt các trục tọa độ tại các điểm $(-8; 0)$ và $(0; 24)$.

Bài toán 5 (LSU, Khoa Toán và Cơ học, 1977). Tại giá trị nào của $a$ thì tiếp tuyến của đồ thị hàm số $y = a - x^2$ cắt một phần tư thứ nhất của một tam giác vuông cân có diện tích bằng $\frac{9}{32}$?

Lời giải. Từ điều kiện bài toán suy ra góc nghiêng của tiếp tuyến với trục hoành bằng $135^\circ$. Vì $tg 135^\circ = -1$, hoành độ của điểm tiếp tuyến là nghiệm của phương trình $-2x = -1$. Do đó, phương trình tiếp tuyến có dạng $y = -x + a + \frac{1}{4}$. Đường thẳng này cắt các trục tọa độ tại các điểm $A(0; a + \frac{1}{4}), B(a + \frac{1}{4}; 0)$.

Theo điều kiện bài toán các điểm $A$ và $B$ nằm trên nửa trục dương nên $a + \frac{1}{4} > 0$. Diện tích của tam giác nói đến trong điều kiện là $\frac{1}{2}(a + \frac{1}{4})^2$. Giải phương trình $\frac{1}{2}(a + \frac{1}{4})^2 = \frac{9}{32}$ (có tính đến $a + \frac{1}{4} > 0$), ta thu được đáp số: $a = \frac{1}{2}$.

Nếu một đường thẳng được cho một phương trình có dạng $y = kx + b$ thì hệ số $k$ bằng tiếp tuyến của góc nghiêng của đường thẳng này với trục abscissa (chúng tôi đã sử dụng hệ số này khi giải bài toán 5). Theo đó, các đường thẳng cho bởi phương trình $y = k_1x + b_1$ và $y = k_2x + b_2$ song song khi và chỉ khi $k_1 = k_2$.

Bài toán 6 (Đại học bang Yerevan, Khoa Toán ứng dụng). Tại điểm nào của đường cong $y = \sqrt{1+x^2}$ là tiếp tuyến song song với đường thẳng $y = 3x + 24$. Đường thẳng này cắt các trục tọa độ tại các điểm $(-8; 0)$ và $(0; 24)$.

Lời giải. Chúng ta hãy tính một hàm đã cho tùy ý: $y' = \frac{x}{\sqrt{1+x^2}}$.

Hệ số góc của tiếp tuyến với đồ thị hàm số tại điểm có hoành độ $a$ bằng giá trị của hàm số tùy ý tại điểm này. Theo điều kiện, độ dốc này phải bằng $\frac{1}{2}$. Do đó, hoành độ của điểm mong muốn là nghiệm của phương trình $\frac{a}{\sqrt{1+a^2}} = \frac{1}{2}$. Giải phương trình này, ta được $a = 1/\sqrt{3}$.

Đáp số: $(1/\sqrt{3}; 2/\sqrt{3})$.

Bài toán 7 (MAI, 1981). Tại những điểm nào trên đồ thị hàm số $y = (1-x)\times(1+x)^2$ chúng ta nên kiểm tra các tiếp tuyến của nó để chúng đi qua điểm $(-1; 0)$?

Lời giải. Chúng ta hãy biểu thị bằng $t$ hoành độ của điểm tiếp tuyến. Vì $y' = -(1+x)^2 + 2(1+x)(1-x) = (1+x)\times(1-3x)$ nên phương trình tiếp tuyến là $y = (1+t)(1-3t)(x-t) + (1-t)(1+t)^2$. Điều kiện để tiếp tuyến đi qua điểm $(-1; 0)$ bây giờ sẽ được viết dưới dạng phương trình cho $t$:

$$0 = (1+t)(1-3t)(-1-t) + (1-t)(1+t)^2,$$

có thể dễ dàng chuyển đổi sang dạng $(1+t)^2 \cdot 2t = 0$. Các nghiệm của phương trình $t = 0$, $t = -1$ này là hoành độ của các điểm cần thiết; Chúng ta tìm tọa độ của chúng bằng cách tính các giá trị tương ứng của hàm này. Đáp số: $(0; 1), (-1; 0)$.

Bài toán 8 (Đại học bang Voronezh, Khoa Toán). Tìm phương trình tiếp tuyến của đường cong

⟦folio 53⟧

$$y = \frac{x+1}{x},$$
nếu biết tiếp tuyến đi qua điểm $M(a; b)$.
Có bao nhiêu lời giải tùy theo điểm $M(a; b)$?

Lời giải. Đáp số cho câu hỏi thứ hai bài toán rất dễ hình dung nếu bạn nhìn vào biểu đồ của hàm số này. Trên hình hyperbola $1 + \frac{1}{x}$ và các tiệm cận của nó (ngoại trừ điểm giao nhau của chúng) được hiển thị bằng màu đỏ. Một tiếp tuyến có thể được vẽ qua mỗi chấm đỏ. Các khu vực có thể vẽ được hai tiếp tuyến với một nhánh của hyperbol được hiển thị bằng màu xanh lam. Hai tiếp tuyến cũng đi qua các điểm của vùng màu xanh lá cây, nhưng một tiếp tuyến với mỗi nhánh của hyperbol. Từ điểm của vùng được tô màu vàng, các đường tiếp tuyến được vẽ với cường điệu này.

Bây giờ chúng ta biểu thị bằng $t$ hoành độ của một điểm tùy ý của hyperbol này và viết phương trình tiếp tuyến tại điểm này: $y = -\frac{1}{t^2}x + \frac{2}{t} + 1$. Đường thẳng này đi qua điểm $M(a; b)$ khi và chỉ khi $b = -\frac{1}{t^2}a + \frac{2}{t} + 1$. Điều kiện này tương đương với hệ thống
$$\begin{cases} (b-1)t^2 - 2t + a = 0, \\ t \neq 0. \end{cases}$$

Đầu tiên, hãy xem xét trường hợp $b=1$ (trong đó phương trình (2) là tuyến tính) và $a=0$ (đây là trường hợp duy nhất mà phương trình (2) có nghiệm $t=0$).

Đối với $b=1$, phương trình (2) có một nghiệm duy nhất $t = \frac{a}{2}$, khác 0 đối với $a \neq 0$. Phương trình tiếp tuyến duy nhất trong trường hợp này là $y = -\frac{4}{a^2}x + \frac{4}{a} + 1$.

Đối với $a=0$ và $b \neq 1$, phương trình (2) có nghiệm duy nhất $t = \frac{2}{b-1}$ từ 0. Phương trình tiếp tuyến duy nhất trong trường hợp này là $y = -\frac{(b-1)^2}{4}x + b$.

Cuối cùng, với $a=0, b=1$ phương trình (2) không có nghiệm nào khác 0.

Hãy để bây giờ $b \neq 1, a \neq 0$. Phân biệt của phương trình bậc hai (2) là $4(1+a-a b)$. Nếu $1+a-a b < 0$, thì phương trình (2) không có nghiệm và do đó, phương trình $M(a; b)$ không thể vẽ tiếp tuyến với đồ thị của hàm này. Lưu ý rằng bất đẳng thức $1+a-a b < 0$ có thể được viết là $b > \frac{1+a}{a}$ cho $a > 0$ và $b < \frac{1+a}{a}$ cho $a < 0$. Do đó, bất đẳng thức này đặt vùng màu vàng là hình.

Nếu $1+a-a b = 0$ (tức là điểm $M(a; b)$ nằm trên một hyperbol), thì phương trình (2) có một nghiệm duy nhất $t = a$ và phương trình tiếp tuyến có dạng $y = -\frac{1}{a^2}x + \frac{2}{a} + 1$.

Nếu $1+a-a b > 0$ thì phương trình (2) có hai nghiệm $t = \frac{1 \pm \sqrt{1+a-a b}}{b-1}$. Thay các nghiệm này vào phương trình $y = -\frac{1}{t^2}x + \frac{2}{t} + 1$, ta thu được phương trình hai tiếp tuyến đi qua điểm $M(a; b)$. Bất đẳng thức $1+a-a b > 0$ cùng với bất đẳng thức $b \neq 1, a \neq 0$ xác định các vùng được tô màu xanh lam và xanh lục trên hình.

Nhiệm vụ 9 (MIPT, 1982). Từ điểm $M(1; 1)$ vẽ các tiếp tuyến của hai nhánh của hyperbol $y = \frac{k}{x} (k < 0)$, tiếp xúc với các nhánh này tại các điểm $A$ và $B$, và tam giác MAB là tam giác đều. Tìm hệ số $k$ và diện tích tam giác MAB.

Lời giải. Gọi $t$ là hoành độ của một điểm tùy ý của hyperbol đã cho. Tiếp tuyến tại điểm này được cho

⟦folio 54⟧

phương trình $y = -\frac{k}{t^2}x + \frac{2k}{t}$ được hình thành và đi qua điểm $M(1; 1)$ khi và chỉ khi $1 = -\frac{k}{t^2} + \frac{2k}{t}$ hoặc $t^2 - 2kt + k = 0$. Phương trình này tại $k < 0$ có hai nghiệm $t_1, t_2$ - hoành độ của điểm $A$ và $B$. Theo định lý Vieta $t_1 + t_2 = 2k, t_1t_2 = k$. Vì các nhánh của hyperbol này đối xứng với đường thẳng $y = x$ và điểm $M$ nằm trên đường thẳng này nên các điểm $A$ và $B$ đối xứng với đường thẳng $y = x$. Tuy nhiên, bạn có thể xác minh điều này theo cách này: $t_1t_2 = k$, tức là trục hoành của điểm $B$ bằng trục hoành của điểm $A$ và trục hoành của điểm $B$ bằng trục hoành của điểm $A$. Do đó, điểm $A$ có tọa độ $(t_1; t_2)$ và điểm $B$ có tọa độ $(t_2; t_1)$. Theo sau đó là $|MA| = |MB|$ cho bất kỳ $k < 0$ nào. Vì vậy, $k$ phải được tìm thấy từ đẳng thức $|MA| = |AB|$. Hãy tính $|MA|^2$ và $|AB|^2$:

$$|AB|^2 = (t_1 - t_2)^2 + (t_2 - t_1)^2 = 2(t_1 - t_2)^2 = 2((t_1 + t_2)^2 - 4t_1t_2) = 8k^2 - 8k;$$

$$|MA|^2 = (t_1 - 1)^2 + (t_2 - 1)^2 = t_1^2 + t_2^2 - 2(t_1 + t_2) + 2 = (t_1 + t_2)^2 - 2(t_1 + t_2) - 2t_1t_2 + 2 = 4k^2 - 6k + 2.$$

Chúng ta đã thu được cho $k$ phương trình $8k^2 - 8k = 4k^2 - 6k + 2$, có một nghiệm âm duy nhất $k = -\frac{1}{2}$. Để tìm mặt phẳng của tam giác đúng $MAB$, chúng ta thay giá trị tìm được $k$ vào biểu thức cho $|AB|^2$. Chúng tôi nhận được $|AB|^2 = 6$ và do đó $S_{MAB} = \frac{3\sqrt{3}}{2}$.

Nhiệm vụ 10 (MISiS, 1978). Bắt đầu phương trình tiếp tuyến chung của parabol $y = x^2 + 4x + 8$ và $y = x^2 + 8x + 4$.

Lời giải. Chúng ta hãy biểu thị bằng $u$ và $v$ hoành độ của các điểm tiếp tuyến. Phương trình tiếp tuyến của parabol thứ nhất tại điểm có hoành độ $u$ là $y = (2u + 4)x - u^2 + 8$, và phương trình tiếp tuyến của parabol thứ hai tại điểm có hoành độ $v$ là $y = (2v + 8x - v^2 + 4$. Vì cả hai phương trình đều là phương trình của cùng một đường thẳng nên chúng ta có $2u + 4 = 2v + 8$, $-u^2 + 8 = -v^2 + 4$. Từ hệ phương trình thu được, chúng ta tìm thấy $u = 2$, $v = 0$. Do đó, phương trình tiếp tuyến mong muốn là $y = 8x + 4$.

Nhiệm vụ 11 (Vòng 2 Olympic Toán học Leningrad). Tìm phương trình tiếp tuyến của đồ thị hàm số $f(x) = x^4 - 2x^3 + x^2 + x - 2$ tại hai điểm.

Lưu ý rằng $f(x) - (x - 2) = x^2(x - 1)^2$. Hóa ra là nếu đa thức $f(x)$ được biểu diễn dưới dạng $f(x) = (x - a)^2g(x) + l(x)$, trong đó $l(x)$ là hàm tuyến tính và $g(x)$ là đa thức tùy ý, thì đường thẳng $y = l(x)$ tiếp tuyến với đồ thị của hàm $y = f(x)$ tại điểm có hoành độ $a$. Thật vậy, trong trường hợp này $f(a) = l(a)$, $f'(a) = l'(a)$, vậy đường thẳng $y = l(x)$ đi qua điểm $(a; f(a))$ và có độ dốc $f'(a)$. Trong trường hợp của chúng ta, nó ngay sau đường thẳng $y = x - 2$ chạm vào đồ thị của hàm này tại các điểm có hoành độ 0 và 1. Do đó, đường thẳng $y = x - 2$ chạm vào đồ thị của hàm này tại hai điểm. Hãy tự chứng minh rằng không có đường thẳng nào khác chạm vào đồ thị của hàm số này tại hai điểm. Vì vậy, phương trình tiếp tuyến mong muốn là $y = x - 2$.

Bài tập

1 (LSU, Khoa Toán và Cơ học, 1977). Tại giá trị nào của $k$ thì tiếp tuyến của đồ thị hàm số $y = kx^2$ sẽ tạo một góc bằng $\frac{\pi}{3}$ với trục hoành và cắt một tam giác có diện tích bằng $\frac{8\sqrt{3}}{3}$ khỏi góc phần tư thứ tư?

2 (Đại học bang Kazan, Khoa Vật lý, 1978). Trên đường cong $y = x^3 - 3x^2 + 2$, tìm các điểm tại đó tiếp tuyến song song với đường thẳng $y = 3x$.

3 (MSU, Khoa Toán tính toán và Điều khiển học, 1978). Tìm phương trình đường thẳng đi qua một điểm có tọa độ $\left(\frac{1}{2}; 2\right)$, tiếp xúc với đồ thị hàm số $y = -\frac{x^2}{2} + 2$ và cắt đồ thị hàm số $y = \sqrt{4 - x^2}$ tại hai điểm phân biệt.

4 (MSU, Khoa Toán và Toán, 1980). tiếp tuyến với đồ thị của hàm $y = \sqrt{3x^2}$ đồng thời trục hoành $c$ của điểm tiếp tuyến cũng thuộc đoạn $\left[\frac{1}{2}; 1\right]$. Tại giá trị nào của $c$ thì diện tích của tam giác giới hạn bởi tiếp tuyến này, trục x và đường thẳng đứng $x = 2$ sẽ nhỏ nhất và diện tích nhỏ nhất này bằng bao nhiêu?

5 (Vòng 2 Olympic Toán Leningrad, 1984). Chứng minh rằng nếu hai tiếp tuyến của parabol $y = x^2$ vuông góc với nhau thì khoảng cách giữa các tiếp tuyến ít nhất là 1.
