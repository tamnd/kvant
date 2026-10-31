---
id: 1972-12-resheniya-08e71b57
issue: kvant_1972_12
year: 1972
number: "12"
title: Lời giải bài toán M135—M140; F153—F158
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 38
page_last: 50
page_labels: 37, 38, 39, 41, 44, 45, 46, 47, 48
tag: 8WRM
lang: vi
source: kvant_digital
extraction: vision
content_sha256: fd1206c8633f0c54580844e19d1ae82a84607b6d345cf0ce680a995d87324d0d
prompt_sha256: draft-1
translated_from: content/ru/1972/12/articles/09_resheniya-08e71b57.md
source_content_sha256: 326704e86248fd1cdab4d33395c9f41c4239e4ee072c9a13beb2590d750774ea
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

Lời giải

Trong số này, chúng tôi xuất bản lời giải bài toán M135—M140

M135
Chứng minh rằng mọi số tự nhiên $n>1$ đều đúng công thức

$$\sin x \sin \left( x + \frac{\pi}{n} \right) \sin \left( x + \frac{2\pi}{n} \right) \times \cdots$$
$$\cdots \times \sin \left( x + \frac{(n-1)\pi}{n} \right) = c_n \sin nx,$$
trong đó $c_n$ là một số nào đó (tùy thuộc vào $n$) và tìm $c_n$.

Đầu tiên ta chứng minh bổ đề sau.
Bổ đề. $$\sin nx = \sin x \cdot A_n (\cos x),$$
thực phẩm $A_n (x)$ là một đa thức bậc $(n-1)$ với hệ số đầu tiên $2^{n-1}$, $$\cos nx = B (\cos x),$$
thực phẩm $B_n (x)$ là một đa thức phi hài cấp $n$ với hệ số đầu tiên $2^{n-1}$.

Rõ ràng là với $n=1$ mệnh đề của bổ đề là đúng. Giả sử nó đúng với $n=k$. Sau đó

$$\sin (k+1) x = \sin x \cdot \cos kx + \cos x \cdot \sin kx = \sin x \cdot \left( B_k (\cos x) + \cos x \cdot A_k (\cos x) \right);$$
$$\cos (k+1) x = \cos x \cdot \cos kx - \sin x \cdot \sin kx = \cos x \cdot B_k (\cos x) + \left( \cos^2 x - 1 \right) A_k (\cos x).$$

Do đó, rõ ràng $A_{k+1} (x) = B_k (x) + x A_k (x)$ và $B_{k+1} (x) = x B_k (x) + \left( x^2 - 1 \right) A_k (x)$ là các đa thức có hệ số thứ nhất bằng tổng các hệ số thứ nhất của đa thức $A_k (n)$ và $B_k (n)$, tức là có hệ số thứ nhất bằng $2^{k-1} + 2^{k-1} = 2^k$. Bổ đề đã được chứng minh.

Hãy đặt $f(x) = \sin \left( x + \frac{\pi}{n} \right) \times \cdots \times \sin \left( x + \frac{\pi (n-1)}{n} \right)$. Struppirum các số hạng theo cặp có dạng $\sin \left( x + \frac{\pi i}{n} \right)$ và $$\sin \left( x + \frac{\pi (n-i)}{n} \right),$$ trong đó $0 < i < \frac{n}{2}$.

Nếu $n$ chẵn thì tích vẫn có số hạng

$$\sin \left( x + \frac{\pi \frac{n}{2}}{n} \right) = \sin \left( x + \frac{\pi}{2} \right) = \cos x.$$

Hãy biến đổi các sản phẩm theo cặp:

$$\sin \left( x + \frac{\pi i}{n} \right) \cdot \sin \left( x + \frac{\pi (n-i)}{n} \right) = \frac{1}{2} \left( -\cos (2x + \pi) + \cos \left( \frac{2\pi i}{n} - \pi \right) \right) = \frac{1}{2} \left( \cos 2x - \cos \frac{2\pi i}{n} \right) = \frac{1}{2} \left( 2 \cos^2 x - 1 - \cos \frac{2\pi i}{n} \right) = \cos^2 x - d_i,$$
trong đó $d_i$ là một số hằng số.

Vì vậy, $f(x) = D_n (\cos x)$, trong đó $D_n (x)$ là đa thức không hài hòa bậc $(n-1)$ với hệ số đầu tiên là 1.

Chúng ta còn phải chứng minh rằng $A_n (x) = 2^{n-1} D_n (x)$ (cụ thể, từ đây sẽ suy ra rằng hằng số $c_n$ trong điều kiện bài toán bằng $\frac{1}{2^{n-1}}$).

Để làm điều này, chúng ta sử dụng lý thuyết rằng một đa thức bậc $k$ có nhiều nhất $k$ nghiệm khác nhau. (Dưới đây chúng ta sẽ nhớ lại cách chứng minh điều đó.)

⟦folio 37⟧

Xét đa thức $F(x) = A_n(x) - 2^{n-1}D_n(x)$. Bậc của nó nhỏ hơn $(n-1)$, vì các hệ số $x^{n-1}$ của đa thức $A_n(x)$ và $2^{n-1}D_n(x)$ bằng nhau. Điều này có nghĩa là $F(x)$ hoàn toàn bằng 0 hoặc $F(x)$ có nghiệm nhỏ hơn $(n-1)$.

Xét các điểm $x_1 = -\frac{\pi}{n}, x_2 = -\frac{2\pi}{n}, \ldots, x_{n-1} = -\frac{\pi(n-1)}{n}$ và đường đi $t_i = \cos x_i$. Rõ ràng là $f(x_i) = 0$, và do đó $D_n(t_i) = 0$; ngoài ra, $\sin(n \cdot x_i) = 0$ và $\sin x_i \neq 0$, có nghĩa là $A_n(\cos x_i) = A_n(t_i) = 0$. Lưu ý rằng tất cả các điểm $t_i$ đều khác biệt vì cos $x$ trả về trên đoạn $[-\pi, 0]$.

Vì vậy, đa thức $F(x)$ biến mất tại điểm $(n-1)$ $t_1, t_2, \ldots, t_{n-1}$ và do đó, $F(x)$ là một số 0 giống hệt nhau. Vì vậy, $A_n = 2^{n-1}D_n$, tức là

$$\sin x \cdot \sin \left(x + \frac{\pi}{n}\right) \times \cdots \times \sin \left(x + \frac{\pi(n-1)}{n}\right) = \frac{1}{2^{n-1}} \sin nx.$$

Bây giờ chúng ta hãy nhớ lại cách chứng minh một đa thức bậc $k$ có nhiều nhất $k$ nghiệm. Đối với $k = 1$ điều này là hiển nhiên. Giả sử câu phát biểu này đúng với $k = l-1$ và cho đường đi $P(t) = a_l t^l + a_{l-1} t^{l-1} + \ldots + a_1 t + a_0$ là đa thức bậc $l$ ($a_l \neq 0$). Giả sử $\alpha$ là nghiệm của đa thức $P$ (nếu $P$ không có nghiệm thì mọi thứ đều được chứng minh): $P(\alpha) = a_l \alpha^l + \ldots + a_0 = 0$. Do đó $P(t) = P(t) - P(\alpha) = a_l (t^l - \alpha^l) + a_{l-1} (t^{l-1} - \alpha^{l-1}) + \ldots + a_1 (t - \alpha).$ Dễ dàng kiểm tra rằng $t^l - \alpha^l = (t - \alpha)(t^{l-1} + \alpha t^{l-2} + \alpha^2 t^{l-3} + \ldots + \alpha^{i-2} t + \alpha^{i-1}).$ Do đó $P(t) = (t - \alpha)[a_l (t^{l-1} + \ldots + \alpha^{l-1}) + a_{l-1} (t^{l-2} + \ldots + \alpha^{l-2}) + \ldots + a_1] = (t - \alpha) H(t)$, trong đó $H(t)$ là đa thức bậc không phải bát phân $l-1$.

Theo giả định, $H(t)$ có nhiều nhất $(l-1)$ nghiệm. Điều này có nghĩa là $P$ có ​​nhiều nhất $l$ nghiệm ($\alpha$ và nghiệm của đa thức $H(t)$).

Tuyên bố của chúng tôi đã được chứng minh cho tất cả $k$.

I. N. Bernishtein

**M136**

Có thể tăng 50 viên đá từ một mỏ đá, có trọng lượng là 370 ke, 372 ke, 374 ke, ..., 468 ke (tất cả đều tạo thành một cấp số cộng với chênh lệch 2 ke), trên bảy ba con ngựa?

Đáp số: không thể được.

Nếu những viên đá được phóng to ra thì 8 viên đá sẽ phải được đặt trên một chiếc xe ba bánh nào đó, nhưng ngay cả 8 viên đá nhẹ nhất cũng nặng

$$370 + 372 + 374 + 376 + 384 + 382 + 380 + 378 = 4.754 = 3016$$

kg - hơn ba tấn.

⟦folio 38⟧

Cơm. 2.

dài và có diện tích lớn (Hình 1) thì rõ ràng chỉ cần chứng minh các bất đẳng thức a), 6) cho một tứ giác lồi là đủ. Vì vậy, chúng ta sẽ chỉ xét các tứ giác lồi.

Vậy đường đi trong tứ giác lồi $ABCD$ (Hình 2) là $AB = a, BC = b, CD = c, DA = d$, diện tích $ABCD$ bằng $S$. Diện tích của một hình tam giác luôn không vượt quá một nửa tích hai cạnh của nó (Hình 3). Đó là lý do tại sao

$$2S(\Delta ABC) \leq ab \text{ и } 2S(\Delta CDA) \leq cd. \tag{1}$$

Cộng các bất đẳng thức này, ta được

$$2S \leq ab + cd. \tag{2}$$

Sự bình đẳng ở đây đạt được trong trường hợp nó đạt được đồng thời trong các bất đẳng thức tổng quát (1), nghĩa là khi và chỉ khi các phần tử $B$ và $D$ đều bằng nhau. Tất nhiên, trong trường hợp này, tứ giác $ABCD$ có ​​thể được viết thành hình tròn (và đường chéo $AC$ là đường kính). Từ những điều trên cũng suy ra rằng một tứ giác mà $2S = ab + cd$ có thể gồm các đoạn $a, b, c, d$ khi và chỉ khi độ dài của chúng thỏa mãn điều kiện

$$a^2 + b^2 = c^2 + d^2. \tag{3}$$

Bài toán 6) có phần khó khăn hơn. Nó có thể được giải quyết “trực tiếp” bằng cách áp dụng các công thức khác nhau cho diện tích hình tam giác. Nhưng cũng có một hình học rất đơn giản lời giải.

Như trước, hãy cắt hình tứ giác, đường chéo $BD$ thành hai hình tam giác và một trong số chúng - giả sử, hình tam giác $BCD$ - “lật nó sang cạnh đối diện” và áp dụng lại cạnh $BD$ cho hình tam giác $BAD$. Nói cách khác, chúng ta thay thế $\triangle BCD$ bằng một hình tam giác $BC'D$, đối xứng với nó theo đường vuông góc đi qua giữa đoạn $BD$ (Hình 4). Rõ ràng là diện tích của tứ giác $S$ sẽ không thay đổi. Nhưng bây giờ chúng ta có thể sử dụng kết quả của bài toán a):

$$2S \leq AB \cdot BC' + C'D \cdot DA$$

hoặc

$$2S \leq ac + bd. \tag{4}$$

Sự bình đẳng ở (4) đạt được nếu tứ giác "được xây dựng lại" $ABC'D$ có các góc vuông $B$ và $D$, nghĩa là, nếu tứ giác ban đầu $ABCD$ có các góc mà đường chéo $BD$ tạo thành với mỗi cặp cạnh đối diện, tổng cộng bằng $90^\circ$:

$$\angle ABD + \angle BDC = \angle ADB + \angle DBC = 90^\circ \tag{5}$$

Tất nhiên, từ đây, suy ra rằng $\angle ABC + \angle ADC = 180^\circ$, tức là tứ giác $ABCD$ nội tiếp (điều này cũng rõ ràng từ thực tế là $\angle A + \angle C = \angle A + \angle C' = 180^\circ$). (Lưu ý rằng tứ giác có

$$2S = ac + bd, \tag{6}$$

có thể bao gồm các phân đoạn $a; b, c, d$ khi và chỉ khi

$$a^2 + c^2 = b^2 + d^2; \tag{7}$$

điều này diễn ra từ (3) áp dụng cho $ABC'D$.

Một lưu ý nữa. Bạn có nghĩ rằng điều kiện cần và đủ (5) để có đẳng thức (6) là “phi đẳng thức” không? Rốt cuộc, trong (6) cả hai cặp đỉnh đối diện đều tham gia như nhau - tại sao đường chéo $BD$ lại tốt hơn $AC$? Tất nhiên là cô ấy cũng không khá hơn. Bây giờ chúng ta sẽ thấy rằng điều kiện (5) có thể được thay thế bằng một phép đối xứng và do đó, như thường lệ, đơn giản hơn.

⟦folio 39⟧

Cơm. 4.

Dễ dàng kiểm tra (Hình 5) rằng điều kiện (5) tương đương đơn giản như sau: tứ giác ABCD là vipsan và AC⊥BD.

Bây giờ chúng ta có thể phát biểu kết quả như sau: để thỏa mãn đẳng thức (6), tứ giác ABCD nội tiếp và có các đường chéo vuông góc với nhau là cần thiết và đủ.

(Đồng thời, chúng ta cũng đã chứng minh được rằng với các tứ giác như vậy thì điều kiện (7) được thỏa mãn. Hãy nhớ cách thực hiện điều này!).

Cơm. 5.

Ngoài lời giải với “đảo nghịch tam giác”, một bất đẳng thức đơn giản khác lời giải bài toán 6) dựa trên bất đẳng thức Pmolemy, tức là dựa trên định lý sau (xem “Lượng tử” số 4, 1972, trang 45, lời giải M99):

Trong tứ giác ABCD bất kỳ

$$AC \cdot BD \leq AB \cdot CD + AD \cdot BC,$$

(8)

Hơn nữa, đẳng thức ở đây là đủ moeda và molko moeda, khi tứ giác ABCD là vipsan.

Từ định lý này suy ra rằng (φ là góc giữa hai đường chéo)

$$S = AC \cdot BD \cdot \sin \varphi \leq AB \cdot CD + AD \cdot BC = ac + bd.$$

Bằng cách này, điều kiện đẳng thức ngay lập tức thu được ở dạng “đối xứng” (nhưng khó đạt được điều kiện (7) hơn).

M138

Chứng minh rằng nếu m và n là số nguyên và 1 ≤ m < n thì

$$\sum_{k=1}^{n} (-1)^k k^m C_n^k = 0,$$

trong đó $C_n^k$ là các hệ số biomp, tức là hệ số của đa thức

$$(1+x)^n = \sum_{k=0}^{n} C_n^k x^k.$$

(Ví dụ: nếu n = 4 thì $C_4^0 = 1, C_4^1 = 4, C_4^2 = 6, C_4^3 = 4, C_4^4 = 1$ và các đẳng thức đều đúng:

$$-1 \cdot 4 + 2 \cdot 6 - 3 \cdot 4 + 4 \cdot 1 = 0,$$

$$-1^2 \cdot 4 + 2^2 \cdot 6 - 3^2 \cdot 4 + 4^2 \cdot 1 = 0,$$

$$-1^3 \cdot 4 + 2^3 \cdot 6 - 3^3 \cdot 4 + 4^3 \cdot 1 = 0.$$)

Mười độc giả đã thêm các phần tử lời giải vào bài toán (sử dụng phương pháp quy nạp toán học). Hãy để chúng tôi trình bày một trong những bằng chứng ngắn nhất do V. Frischling (Tbilisi) gửi.

Dễ dàng kiểm chứng rằng các đẳng thức đang được chứng minh là đúng với n=2, 3, 4 (xem ví dụ trong văn bản bài toán). Giả sử rằng với l<n-1 các đẳng thức $\sum_{j=0}^{l-1} j^l C_{n-1}^l = 0$ là đúng. Lợi dụng sự bình đẳng

$$C_n^k = \frac{n!}{k!(n-k)!} = \frac{n}{k} \cdot \frac{(n-1)!}{(k-1)!(n-k)!} = \frac{n}{k} C_{n-1}^k,$$

*) Chúng ta viết ở đây và dưới dấu tổng một cách không hoàn toàn quen thuộc

$$\sum_{k=0}^{n} \text{вместо «старого образца»} - \sum_{k=0}^{n} \text{чтобы сэкономить место и упростить работу наборщика. Так делают сейчас во многих научных журналах.}$$

⟦folio 41⟧

Trong trường hợp này, chúng tôi sẽ sử dụng thao tác $A'$ hoặc $B'$ mọi lúc, càng sớm càng tốt để giảm số lượng của chúng tôi ở mỗi bước nếu có thể. Chúng tôi nhận được:

$$1972 \rightarrow 3944 \rightarrow 394 \rightarrow 78 \rightarrow 156 \rightarrow 312 \rightarrow 624 \rightarrow 62 \rightarrow 124 \rightarrow 12 \rightarrow 24 \rightarrow 2 \rightarrow 4.$$

Rõ ràng là bằng cách đọc trình tự này từ đầu đến cuối, chúng ta sẽ nhận được kết quả mong muốn. (Thao tác $B'$ không được sử dụng ở đây.)

6) Hãy chứng minh rằng nếu chúng ta thực hiện với mỗi số $N$ giống như cách chúng ta đã làm với số 1972 (sử dụng phép toán $A'$ hoặc $B'$ và nếu không thể thực hiện được - $B'$), thì sau một vài bước chúng ta sẽ đến số 4.

Để làm được điều này, chỉ cần chứng minh rằng trong dãy kết quả, mỗi số sẽ chuyển thành một số nhỏ hơn (hoặc thành số 4) sau một vài bước là đủ. Từ đó, cuối cùng chúng ta chắc chắn sẽ đến với số 4, vì không thể xây dựng một dãy vô hạn các số tự nhiên trong đó có ít số đứng sau mỗi số hơn.

Vì vậy, hãy đảm bảo rằng mỗi số có thể được giảm bớt trong một số thao tác $A'$, $B'$, $B'$ (hoặc chuyển từ số đó xuống 4; chúng tôi không thảo luận cụ thể hơn về trường hợp cuối cùng này).

Nếu chữ số cuối cùng của một số là 0 hoặc 4 thì sau khi áp dụng $A'$ hoặc $B'$ nó sẽ giảm đi ít nhất 10 lần.

Cho chữ số cuối cùng của số khác 0 và 4. Bảng 1 cho biết chữ số cuối cùng thay đổi như thế nào khi sử dụng $B'$ (thao tác $B'$, tức là thông báo số đó 2 lần, được biểu thị bằng mũi tên màu đen; có thể sử dụng $A'$ hoặc $B'$ - với mũi tên màu đỏ):

$$\begin{array}{c}
0 \rightarrow \\
1 \rightarrow 2 \rightarrow 4 \rightarrow \\
2 \rightarrow 4 \rightarrow \\
3 \rightarrow 6 \rightarrow 2 \rightarrow 4 \rightarrow \\
4 \rightarrow \\
5 \rightarrow 0 \rightarrow \\
6 \rightarrow 2 \rightarrow 4 \rightarrow \\
7 \rightarrow 4 \rightarrow \\
8 \rightarrow 6 \rightarrow 2 \rightarrow 4 \rightarrow \\
9 \rightarrow 8 \rightarrow 6 \rightarrow 2 \rightarrow 4 \rightarrow
\end{array}$$

Từ bảng này, rõ ràng rằng nếu số $N$ hóa ra là bất kỳ chữ số nào ngoại trừ 9, thì sau không quá ba lần áp dụng $B'$, tức là sau khi thông báo không quá 8 lần, bạn có thể áp dụng $A'$ hoặc $B'$ cho nó, tức là giảm ít nhất 10 lần. Do đó, $N$ sẽ dẫn đến số không vượt quá $\frac{8}{10}N < N$.

Vẫn chỉ xem xét các số $N$ kết thúc bằng 9, được thông báo 16 lần trước khi chuyển sang $A'$. Lưu ý rằng dù chữ số trước của số $N$ trước 9 là chữ số áp chót của số đó

$$16N = 16(10a+9) = 160a+144$$

luôn luôn etna.

Nếu chữ số này không phải là 8 thì 16$N$ sau $A'$ và nhiều nhất là hai thao tác $B'$ sẽ trở lại thành một số có số 0 hoặc 4 ở cuối, chúng ta có thể giảm ít nhất 10 lần. Kết quả là $N$ sẽ dẫn đến số không vượt quá $\frac{16 \cdot 4N}{100} < N$.

Vẫn có trường hợp khi 16$N$ kết thúc bằng 84. Lưu ý rằng bất kể chữ số nào trước đó của số này trước 8, sau các phép toán

$$16N = \dots \quad 84 \rightarrow 10b+8 \rightarrow \rightarrow 80b+64 \rightarrow 8b+6$$

chúng ta nhận được một số kết thúc bằng một chữ số chẵn.

Nếu chữ số này không phải là 8, thì không quá hai thao tác $B$ chúng ta thu được một số có chữ số 0 hoặc 4 ở cuối, loại bỏ nó và cuối cùng thu được từ $N$ một số không vượt quá $\frac{16 \cdot 8 \cdot 4}{1000}N < N$.

Tuyên bố của chúng tôi đã được chứng minh và bài toán được giải quyết.

Hãy thử hiểu lời giải này, dịch bằng các phép toán $A$, $B$ sang số 4 trong 1249 (đây là một trong những con số “khó chịu” nhất).

Nhiều độc giả giải bài toán $M140$ theo cách này đã không để ý hoặc chưa hiểu hết trường hợp số $N$ tận cùng là 9.

Một lời giải ngắn hơn nhiều đã được phát minh ra $A$. Astmaov (Lvov), $A$. Arsasyan (Kamo), $\Gamma$. Visotskaya (Krasnoirsk). Họ chứng minh rằng từ bốn số bất kỳ, có thể thu được số nhỏ hơn bằng cách sử dụng các phép toán $A'$, $B'$, $B'$ (rõ ràng, điều này là đủ cho lời giải bài toán). Ở đây đủ để xét 5 trường hợp:

1) $10k \rightarrow k$,
2) $10k+2 \rightarrow 20k+4 \rightarrow 2k$,
3) $10k+4 \rightarrow k \rightarrow 2k$,
4) $10k+6 \rightarrow 20k+10+2 \rightarrow 40k+20+4 \rightarrow 4k+2$,
5) $10k+8 \rightarrow 20k+10+6 \rightarrow 40k+30+2 \rightarrow 80k+60+4 \rightarrow 8k+6$.

Dưới đây chúng tôi công bố danh sách những độc giả đã gửi chính xác cho chúng tôi lời giải

⟦folio 44⟧

Trong số này, chúng tôi xuất bản lời giải bài toán F153—F158

F153
Tại sao những dòng sông chảy qua vùng đất bằng phẳng, đồng nhất lại uốn cong?
Để đơn giản, hãy xem xét một dòng sông chảy dọc theo đường xích đạo.

Dòng chảy uốn khúc của các con sông là do dòng chảy thẳng của chúng không ổn định. Điều này có nghĩa là nếu một khúc cua nhỏ hoặc sự bất thường của dòng sông đang chảy vô tình hình thành, chẳng hạn như do cây đổ xuống nước, thì khúc cua của dòng sông sẽ tăng lên. Để tìm hiểu lý do tại sao điều này xảy ra, chúng ta hãy xem xét. . . một ly trà có những miếng trà nổi trong đó. Nếu bạn “quay” trà trong ly bằng thìa, khiến chất lỏng quay tròn, sau đó lấy thìa ra khỏi ly, thì sau một thời gian, tất cả các mảnh vụn sẽ tụ lại dọc theo trục của ly. Điều này được kết nối với điều này.

Khi một chất lỏng quay trong thủy tinh, mỗi phần của chất lỏng chịu tác dụng bởi các phần khác xung quanh nó bằng một lực sao cho hợp lực của lực này và trọng lực hướng theo phương ngang và truyền gia tốc hướng tâm cho hạt.

$$a = \omega^2 R,$$

trong đó $\omega$ là tốc độ góc quay của chất lỏng và $R$ là khoảng cách mà bộ phận đó nằm tính từ trục quay. Khoảng cách $R$ càng lớn thì gia tốc của hạt càng lớn, nghĩa là thành phần nằm ngang của lực tác dụng lên bộ phận này so với các bộ phận khác sẽ càng lớn. Do đó, bề mặt của chất lỏng quay có dạng parabolon. (Hãy nhớ rằng lực tác dụng lên một hạt chất lỏng nằm gần bề mặt từ các phần khác là vuông góc với bề mặt. Mặt khác, thành phần của lực này, parabol so với bề mặt, sẽ gây ra sự chuyển động của các hạt chất lỏng.) Do hình dạng này của bề mặt chất lỏng, áp suất trong nó ở cùng khoảng cách so với ngày sẽ tăng khi nó đến gần các ống kính.

Sau khi lấy thìa ra khỏi ly, tốc độ của các hạt chất lỏng ở thành ly và ở đáy ly bắt đầu giảm do ma sát. Trong trường hợp này, gia tốc do chất nhờn tác động lên chúng hóa ra lớn hơn gia tốc hướng tâm, và một dòng chất lỏng sẽ xuất hiện trong thủy tinh như trong Hình 7. Do ma sát, tốc độ của dòng điện này trên bề mặt nhỏ hơn tốc độ của nó ở một độ sâu nhất định. Dòng chảy này mang các khối đến trục quay của chất lỏng.

Các hiệu ứng dòng chảy tuần hoàn tương tự xảy ra ở dòng sông nơi dòng sông rẽ (Hình 8). Những hạt cát này được vận chuyển từ ban ngày và bờ sông bị xáo trộn vào bờ trong. Do đó, dòng chảy tuần hoàn làm tăng độ uốn của dòng sông, làm xói mòn bờ sông nguyên vẹn. Hơn nữa, xói mòn - sự tàn phá của bờ và ngày - trở nên mạnh hơn ở gần bờ sông bị xáo trộn. Do đó, đến tận sông nó có hình dáng như trong Hình 9.

F154
Ước tính có bao nhiêu giọt nước trong 1 m³ sương mù nếu tầm nhìn là 10 m và sương mù lắng xuống sau 2 giờ. Độ cao sương mù 200 m.

Lực cản của không khí tác dụng lên một giọt nước có bán kính $R$ (m), chuyển động với tốc độ $v$ (m/giây), bằng 4,3 Rv (n).

Để đánh giá, chúng tôi sẽ giả sử rằng những giọt sương mù là những quả bóng mờ giống hệt nhau có bán kính $R$. Mỗi giọt này có diện tích mặt cắt ngang $s = \pi R^2$. Điều này có nghĩa là $n$ giọt nằm trong 1 m³

⟦folio 45⟧

không khí và được bố trí một cách hỗn loạn, “chồng lên nhau” một diện tích xấp xỉ $S = n\pi R^2$. Trong đánh giá này, chúng tôi không tính đến việc các vốn chồng chéo một phần với nhau. Tuy nhiên, vì mục đích đánh giá - đạt được đáp số gần đúng - điều này không quan trọng.

Vì tầm nhìn là 10 m nên các mũ sương mù được đặt theo hình chữ nhật song song với diện tích đáy $1\ m^2$ và chiều dài 10 m, phải “chồng lên nhau” có diện tích $1\ m^2$. Có 10 n giọt trong hình bình hành này và diện tích bao phủ là

$$10\pi nR^2 = 1\ m^2.$$

Từ đây bạn có thể tìm thấy $n$:

$$n = \frac{1}{10\pi R^2}.$$

Công thức này bao gồm bán kính chưa biết của giọt nước. Hãy tìm anh ấy. Một giọt sương mù chịu tác dụng của hai lực: trọng lực không đổi và lực cản không khí hướng lên, lực này tăng khi tốc độ rơi của giọt nước tăng lên. Khi một giọt nước rơi xuống, chắc chắn sẽ đến lúc các lực này ngang bằng nhau. Sau đó, tốc độ của giọt nước ngừng thay đổi và giọt nước rơi đều với tốc độ có thể tìm được từ điều kiện cân bằng giữa trọng lực và lực cản không khí:

$$mg = 4,3Rv$$

$$(m = \frac{4}{3}\pi R^3\rho - \text{масса капли},$$

$$\rho = 10^3\ k\epsilon/m^3 - \text{плотность воды}).$$

Từ đây

$$\frac{4}{3}\pi R^3\rho g = 4,3Rv$$

Và

$$R^2 = \frac{3}{4}\frac{4,3v}{\pi\rho g} \approx \frac{v}{\rho g} m^2.$$

Vì sương mù đọng lại trong 2u và độ cao của lớp sương mù là 200 m nên tốc độ rơi bằng

$$v = \frac{200\ m}{2\cdot 3600c} \approx 0,028\ m/c.$$

Thay giá trị tốc độ rơi này vào công thức (2), chúng ta tìm được bán kính của giọt nước:

$$R = \sqrt{\frac{0,028}{10^4}} \approx 1,7\cdot 10^{-3}\ m.$$

Bây giờ từ công thức (1) chúng ta có thể tìm thấy $n$:

$$n = \frac{1}{10\cdot 3,14\cdot(1,7)^2\cdot 10^{-6}} \approx 1,1\cdot 10^4.$$

F155

Một mol khí được hớt sao cho thể tích của nó trong quá trình hớt bọt tỷ lệ thuận với nhau

Cơm. 10.

áp suất $V = \alpha P$. Áp suất khí tăng từ $P_1$ lên $P_2$. Tìm hệ số $\alpha$ nếu nhiệt dung của khí này ở thể tích không đổi là $c_V$ và trong quá trình đó lượng nhiệt bị mất từ ​​không khí được truyền vào khí:

$$Q = \Delta W_{BH} + A.$$

Từ định luật bảo toàn năng lượng, ta suy ra rằng lượng nhiệt mà khí giữ lại trong quá trình đó bằng tổng độ biến thiên nội năng của khí $\Delta W_{BH}$ và công $A$ mà khí thực hiện trong quá trình đó:

$$\Delta W_{BH} = c_V \Delta T.$$

Pozny

$$Q = c_V \Delta T + A.$$

Công mà chất khí thực hiện bằng diện tích hình thang theo đồ thị $P$ so với $V$ (Hình 10):

$$A = (V_2 - V_1) \frac{(P_2 + P_1)}{2} =$$

$$= \frac{(\alpha P_2 - \alpha P_1)(P_2 + P_1)}{2} = \frac{\alpha (P_2^2 - P_1^2)}{2}.$$

Như vậy,

$$Q = c_V \Delta T + \frac{\alpha (P_2^2 - P_1^2)}{2}.$$

Hãy biểu thị $\Delta T$ theo $P_1$ và $P_2$. Chúng ta hãy viết phương trình trạng thái khí cho trạng thái ban đầu và cuối cùng của khí:

$$P_1V_1 = RT_1,$$

$$P_2V_2 = RT_2,$$

$$\alpha P_1^2 = RT_1,$$

$$\alpha P_2^2 = RT_2.$$

⟦folio 46⟧

Trừ đẳng thức thứ nhất từ ​​đẳng thức thứ hai, chúng ta tìm thấy

$$\Delta T = T_2 - T_1 = \frac{\alpha (P_2^2 - P_1^2)}{R}.$$

Bây giờ, thay biểu thức này cho $\Delta T$ vào công thức (3), chúng ta thu được

$$Q = \frac{c_V \alpha}{R} \left( P_2^2 - P_1^2 \right) + \frac{\alpha}{2} \left( P_2^2 - P_1^2 \right).$$

Từ đây

$$\alpha = \frac{2QR}{(2c_V + R) (P_2^2 - P_1^2)}.$$

F156
Có một lưới thép vô tận với một ô hình chữ nhật. Điện trở của mỗi dây tạo nên ô lưới là $r$. Tìm điện trở lưới giữa các điểm $A$ và $B$ (Hình 11).

Để một nguồn có hiệu điện thế tại các cực $U$ được nối với các điểm $A$ và $B$ (điện trở trong của nguồn không đáng kể và có thể coi bằng 0). Đặt cường độ dòng điện chạy qua dây nguồn bằng $I$. Khi đó $U = IR$, trong đó $R$ là điện trở của dây xích giữa các điểm $A$ và $B$. Mặt khác, nếu dòng điện $I_1$ chạy qua dây dẫn $AB$ thì theo định luật Ohm $U = I_1 r$. Điều này có nghĩa là

$$I_1 r = IR \text{ и } R = \frac{I_1}{I} r.$$

Như vậy, để tìm được điện trở của dây xích cần tìm mối liên hệ giữa các điểm $I$ và $I_1$.

Như vậy, để tìm được điện trở của dây xích cần tìm mối liên hệ giữa các điểm $I$ và $I_1$.

Như vậy, để tìm được điện trở của dây xích cần tìm mối liên hệ giữa các điểm $I$ và $I_1$.

Như vậy, để tìm được điện trở của dây xích cần tìm mối liên hệ giữa các điểm $I$ và $I_1$.

Như vậy, để tìm được điện trở của dây xích cần tìm mối liên hệ giữa các điểm $I$ và $I_1$.

Như vậy, để tìm được điện trở của dây xích cần tìm mối liên hệ giữa các điểm $I$ và $I_1$.

Do đó, để tìm lực cản của sợi xích nối với tâm vòng, gia tốc của từng điểm của vòng bằng tổng gia tốc hướng tâm $a_ц = \frac{v^2}{R}$ (v là tốc độ tuyến tính của các điểm của vòng) và gia tốc tiếp tuyến (tiếp tuyến) (Hình 12, a). Vì vòng không trượt nên tốc độ tuyến tính của các điểm của vòng bất kỳ lúc nào cũng bằng tốc độ tâm của nó trong hệ tọa độ liên kết với Trái đất. Điều này có nghĩa là sự thay đổi tốc độ tuyến tính của vòng trong một đơn vị thời gian, tức là gia tốc tiếp tuyến của các điểm trên vòng, bằng gia tốc của tâm vòng, tức là $a$.

Để tính gia tốc hướng tâm của các điểm vòng sau thời gian $t$ sau khi bắt đầu chuyển động, bạn cần biết tốc độ tuyến tính của chúng tại thời điểm này. Nó bằng nhau

$$v = v_0 + at.$$

Pozny

$$a_ц = \frac{(v_0 + at)^2}{R}.$$

Để tìm gia tốc của các điểm vòng trong hệ tọa độ liên kết với Trái đất, bạn cần cộng vectơ gia tốc $a$của gia tốc tâm vòng với vectơ gia tốc của các điểm (Hình 12, b). Như vậy chúng ta tìm thấy:

$$a_A = \sqrt{a^2 + (a_ц + a)^2} =$$

$$= \sqrt{a^2 + \left[ \frac{(v_0 + at)^2}{R} + a \right]^2},$$

$$a_B = \sqrt{(2a)^2 + a_ц^2} =$$

$$= \sqrt{4a^2 + \frac{(v_0 + at)^4}{R^2}},$$

$$a_C = \sqrt{a^2 + (a_ц - a)^2} =$$

$$= \sqrt{a^2 + \left[ \frac{(v_0 + at)^2}{R} - a \right]^2},$$

$$a_D = a_ц = \frac{(v_0 + at)^2}{R}.$$

⟦folio 47⟧

Cơm. 12.

F158

Một quả tạ nằm ngang rơi từ độ cao $h$ và đập vào một đầu của nó trên bàn (Hình 13). Quả tạ sẽ đi được bao xa sau khi va chạm trước khi nó trở lại vị trí nằm ngang?

Quả tạ gồm hai quả bóng nặng giống hệt nhau được gắn trên một thanh không trọng lượng có chiều dài $l$. Tác động của quả tạ lên bàn là hoàn toàn đàn hồi. Chiếc bàn ngay lập tức bị loại bỏ sau cú va chạm.

Khi rơi từ độ cao $h$, quả tạ có tốc độ là

$$v = \sqrt{2gh}.$$

Vì tác động của quả tạ lên bàn có thể được coi là tức thời nên có thể bỏ qua ảnh hưởng của quả bóng thứ hai đến va chạm với bàn. Điều này có nghĩa là quả bóng thép tương tác với bàn giống như khi nó đứng một mình và không gắn vào thanh: khi va chạm, vận tốc và động lượng của quả bóng này đảo ngược nhưng động lượng và tốc độ của quả bóng thứ hai không thay đổi.

Chúng ta hãy xem xét chuyển động của một quả tạ trong hệ tọa độ gắn liền với tâm của thanh—tâm khối của hệ. Hệ tọa độ này di chuyển xuống dưới với gia tốc $g$ và ngay sau khi quả bóng chạm bàn, nó có vận tốc bằng 0. Trong hệ tọa độ này, vận tốc của các quả bóng sau khi chạm bàn có giá trị tuyệt đối bằng nhau $v$ và được định hướng theo các hướng khác nhau. Điều này có nghĩa là trong hệ tọa độ gắn liền với khối tâm, quả tạ sẽ quay sau bao nhiêu bước với bàn và tốc độ quay tuyến tính của các quả bóng bằng $v$. Quả tạ sẽ lại nằm ngang khi các quả bóng quay được nửa vòng quanh tâm thanh, tức là sau một thời gian.

$$t = \frac{\pi \frac{l}{2}}{v} = \frac{\pi l}{2v} = \frac{\pi l}{2\sqrt{2gh}}.$$

Trong thời gian này, tâm của thanh sẽ bao phủ khoảng cách

$$H = \frac{gt^2}{2} = \frac{1}{16} \frac{\pi^2 l^2}{h}.$$

Các biên tập viên đã nhận được khoảng 400 lá thư kèm theo quyết định bài toán F148 - F158. Hầu hết tất cả độc giả đều hoàn thành thành công bài toán F158. lời giải đúng trong số bài toán còn lại được thêm bởi: A. Hayrapemyan (Yerevan) F149; O. Azanina (Moscow) F152, F155; M. Aksman (Rostov-on-Don) F152; Sh. Amakulov (Fergana) F152; A. Baevsky (Gomel) F148, F152; Y. Belenko (Namangan) F155; V. Belov (Vologda) F148, F149, F151, F155, F156; A. Blyukhin (Kiselevsk, vùng Kemerovo) F149 - F152; L. Bradisky (Frunze)

⟦folio 48⟧

Sinh nhật cặp đôi

Với số lượng người tối thiểu trong một công ty thì xác suất để mặc dù hai người trong số họ sinh cùng ngày nhưng ít nhất phải bằng 1/2?

(Năm sinh có thể không giống nhau.)

Trên rìa của một vách đá

Người say đứng cách bờ vực thẳm một bước. Anh ta bước như sau: đến rìa vách đá hoặc không đến mép vách đá. Ở mỗi bước, xác suất để người này rời xa mép vách đá là 2/3 và bước về phía mép vách đá có xác suất là 1/3. Người say rượu làm thế nào để tránh bị ngã?

kim của Buffon

Vẽ các đường thẳng song song trên mặt phẳng, cách nhau một khoảng 2a. Một cây kim có chiều dài 2l (nhỏ hơn 2a) được ném ngẫu nhiên lên mặt phẳng. Xác suất để nó vượt qua một trong các đường thẳng là bao nhiêu?
