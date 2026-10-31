---
id: 1975-10-resheniya-zadach-m308-m315-f318-f321-a76d19d1
issue: kvant_1975_10
year: 1975
number: "10"
title: Lời giải bài toán M308—M315; F318—F321
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 42
page_last: 49
page_labels: 40-47
tag: WJRI
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 315df0a45bcf9963f03f7428f219fb7b0a2c7ab23979515fb58528cfde89262f
prompt_sha256: draft-1
translated_from: content/ru/1975/10/articles/18_resheniya-zadach-m308-m315-f318-f321-a76d19d1.md
source_content_sha256: 72ee6443ab6b5a868d4155536ae9456d29660f171a98b3dd82510c68c559d577
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 40⟧

Lời giải bài toán
M308-M315; F318-F321

M308. Nếu với bất kỳ $x$ $a_1\cos x + a_2\cos 2x + \dots + a_n\cos nx \geq -1$ nào, thì đối với các số $a_1, a_2, \dots, a_n$ thì bất đẳng thức $a_1 + a_2 + \dots + a_n \leq n$ đúng. Bằng chứng là phát biểu sau: a) cho $n = 2$; b) cho $n = 3$; c) đối với mọi $n$ tự nhiên.

a) Chỉ cần đặt $x = \frac{2\pi}{3}$ là đủ.

b) Đặt $x = \frac{\pi}{2}, x = \pi, x = \frac{3\pi}{2}$ liên tiếp và cộng các bất đẳng thức thu được.
b) Trước tiên chúng ta chứng minh công thức sau: nếu $\varphi = -\frac{2k\pi}{n+1}$, trong đó $k$ và $n$ là số nguyên và $k$ không chia hết cho $n+1$, thì
$$\cos \varphi + \cos 2\varphi + \cos 3\varphi + \dots + \cos n\varphi = -1. \quad (*)$$
Đặt các điểm đã cho là $O$ và $A_0$. Xoay điểm $A_0$ theo góc $\varphi$ so với điểm $O$, ta thu được điểm $A_1$. Từ điểm $A_1$ với cùng một góc quay, chúng ta thu được điểm $A_2$, từ điểm $A_2$ - điểm $A_3$, v.v. Vì $(n+1)\varphi = 2k\pi$ nên điểm $A_{n+1}$ trùng với điểm $A_0$. Tổng các vectơ $\overrightarrow{OA_0}, \overrightarrow{OA_1}, \overrightarrow{OA_2}, \dots, \overrightarrow{OA_n}$ bằng vectơ null. Thật vậy, khi mỗi vectơ này quay một góc $\varphi$ so với điểm $O$, thì một vectơ bằng tổng của chúng cũng phải quay theo cùng một góc. Mặt khác, vì một vectơ bằng tổng các vectơ $\overrightarrow{OA_0}, \overrightarrow{OA_1}, \dots, \overrightarrow{OA_n}$ sẽ không thay đổi trong quá trình quay này (đối với điểm $A_0$ sẽ chuyển sang điểm $A_1$, điểm $A_1$ thành điểm $A_2$, ..., điểm $A_n$ thành điểm $A_0$), thì nó bằng vectơ null.
Bây giờ chúng ta giả sử rằng điểm $O$ là gốc và vectơ $\overrightarrow{OA_0}$ có độ dài 1 và hướng dọc theo trục x. Vì hình chiếu của tổng các vectơ lên ​​một trục bất kỳ bằng tổng các hình chiếu của chúng lên trục này, nên tổng các hình chiếu của các vectơ $\overrightarrow{OA_1}, \overrightarrow{OA_2}, \dots, \overrightarrow{OA_n}$ lên trục abscissa bằng -1 (hình chiếu của vectơ $\overrightarrow{OA_0}$ lên trục abscissa bằng 1). Nhưng những phép chiếu này rõ ràng bằng $\cos \varphi, \cos 2\varphi, \dots, \cos n\varphi$, sự vắng mặt của nó theo công thức (*).

Công thức (*) có thể được chứng minh theo cách khác bằng cách nhân cả hai vế với $2\sin \frac{\varphi}{2}$ và sử dụng công thức
$$2\sin \frac{\varphi}{2}\cos k\varphi = -\sin \left(k - \frac{1}{2}\right)\varphi + \sin \left(k + \frac{1}{2}\right)\varphi,$$
- tự mình làm đi.

Hãy chuyển sang lời giải bài toán c).
Lấy một số tùy ý $x_1$, ta đặt $x_2 = 2x_1, x_3 = 3x_1, \dots, x_n = nx_1$. Với $x = x_1, x = x_2, x = x_3, \dots, x = x_n$ ta thu được các bất đẳng thức sau:
$$a_1\cos x_1 + a_2\cos 2x_1 + a_3\cos 3x_1 + \dots + a_n\cos nx_1 \geq -1,$$

⟦folio 41⟧

$$a_1 \cos x_2 + a_2 \cos 2x_2 + a_3 \cos 3x_2 + \dots + a_n \cos nx_2 \geq -1,$$
$$a_1 \cos x_3 + a_2 \cos 2x_3 + a_3 \cos 3x_3 + \dots + a_n \cos nx_3 \geq -1,$$
$$\dots$$
$$a_1 \cos x_n + a_2 \cos 2x_n + a_3 \cos 3x_n + \dots + a_n \cos nx_n \geq -1.$$

Cho rằng $kx_l = klx_1 = lkx_1 = lx_k$, các bất đẳng thức này có thể được viết lại như sau:

$$a_1 \cos x_1 + a_2 \cos x_2 + a_3 \cos x_3 + \dots + a_n \cos x_n \geq -1,$$
$$a_1 \cos 2x_1 + a_2 \cos 2x_2 + a_3 \cos 2x_3 + \dots + a_n \cos 2x_n \geq -1,$$
$$a_1 \cos 3x_1 + a_2 \cos 3x_2 + a_3 \cos 3x_3 + \dots + a_n \cos 3x_n \geq -1,$$
$$\dots$$
$$a_1 \cos nx_1 + a_2 \cos nx_2 + a_3 \cos nx_3 + \dots + a_n \cos nx_n \geq -1.$$

Cộng các bất đẳng thức này và đặt $x_1 = \frac{2\pi}{n+1}$ (rồi $x_2 = \frac{4\pi}{n+1}$, $x_3 = \frac{6\pi}{n+1}$, $\dots$, $x_n = \frac{2n\pi}{n+1}$), ta thu được bất đẳng thức

$$-a_1 - a_2 - a_3 - \dots - a_n \geq -n,$$

Ở đâu

$$a_1 + a_2 + a_3 + \dots + a_n \leq n^*).$$

Yu. I. Nokin

**M309. a) Với $n$ thì đa thức $x^{2n} + x^n + 1$ chia hết cho $x^2 + x + 1$ là bao nhiêu?**

b) Tại số $n$

$$1 \underbrace{0 \dots 0}_{n} \underbrace{1 \dots 0}_{n}$$

chia hết cho 37?

a) Xét ba trường hợp tương ứng với các số dư khác nhau khi $n$ chia cho 3.

1°. Để $n=3k$; Sau đó

$$x^{6k} + x^{3k} + 1 = (x^{6k} - 1) + (x^{3k} - 1) + 3 =$$
$$= (x^3 - 1)(x^{6k} - 3 + x^{6k} - 6 + \dots + 1) +$$
$$+ (x^3 - 1)(x^{3k} - 3 + x^{3k} - 6 + \dots + 1) + 3 =$$
$$= (x^2 + x + 1) \cdot Q(x) + 3,$$

ở đâu $Q(x) = (x - 1)[(x^{6k} - 3 + x^{6k} - 6 + \dots + 1) + (x^{3k} - 3 + \dots + 1)]$.

Do đó, nếu $n=3k$ thì đa thức $x^{2n} + x^n + 1$ khi chia cho $x^2 + x + 1$ cho số dư 3.

2°. Hãy để $n=3k + 1$. chúng tôi có

$$x^{6k + 2} + x^{3k + 1} + 1 = (x^{6k + 2} - x^2) + (x^{3k + 1} - x) +$$
$$+ (x^2 + x + 1) = x^2(x^{6k} - 1) + x(x^{3k} - 1) + (x^2 + x + 1)$$

Trong 1° chúng ta đã chỉ ra rằng các đa thức $(x^{6k} - 1)$ và $(x^{3k} - 1)$ đều chia hết cho $(x^3 - 1)$, do đó cũng chia hết cho $(x^2 + x + 1)$; do đó, tại $n=3k + 1$ đa thức $x^{2n} + x^n + 1$ chia hết cho $x^2 + x + 1$.

3°. Hãy để $n=3k + 2$. Sau đó

$$x^{6k + 4} + x^{3k + 2} + 1 = x^1(x^{6k} - 1) + x^2(x^{3k} - 1) + x^4 + x^2 +$$
$$+ 1 = x^4(x^{6k} - 1) + x^2(x^{3k} - 1) + x^3 - 1 + (x^2 + x + 1) = (x^2 + x + 1)[(x - 1)R(x) + 1],$$

trong đó $R(x) = x^4(x^{6k} - 3 + \dots + 1) + x^2(x^{3k} - 3 + \dots + 1) + x$ và đa thức $x^{2n} + x^n + 1$ lại chia hết cho $x^2 + x + 1$.

*) Điều bài toán này đã được giải quyết tương tự trong cuốn sách của Polin và Sethe “Bài toán và các định lý từ phân tích”.

⟦folio 42⟧

Vậy đáp số trong bài toán a) là:
đa thức $x^{2n} + x^n + 1$ chia hết cho $x^2 + x + 1$ trừ khi $n$ là bội số của ba.

6) Đối với lời giải bài toán này, chúng ta có thể sử dụng kết quả của điểm a), vì tất cả đa thức thu được trong quá trình chia—các phần và phần dư—có hệ số nguyên. Thật vậy, với $x = 10$ chúng ta nhận được kết quả tương ứng
$$x^2 + x + 1 = 111, x^{2(n+1)} + x^{(n+1)} + 1 = 1 \underbrace{0 \ldots 0}_{n} \underbrace{1 \ldots 0}_{n}.$$
Mặt khác, $10^{2m} + 10^m + 1$ chia hết cho 3 với mọi $m$, và câu hỏi $10^{2m} + 10^m + 1$ có chia hết cho 37 hay không cũng tương đương với câu hỏi liệu $10^{2m} + 10^m + 1$ có chia hết cho 37,3 = 111 hay không. Đáp số trong bài toán này là: số $\underbrace{10 \ldots 0}_{n} \underbrace{10 \ldots 0}_{n}$ chia hết cho 37 nếu $n$ là bội số của 3 hoặc nếu $n$ chia cho 3 dư 1.
F. G. Shleifer

**M311.** *) Từ một vi khuẩn, 1000 vi khuẩn thu được theo cách sau: đầu tiên vi khuẩn được chia thành hai, sau đó một trong hai vi khuẩn thu được được chia thành hai, sau đó một trong ba vi khuẩn thu được được chia thành hai, v.v. Chúng ta hãy chứng minh rằng tại một số thời điểm đã tồn tại một loại vi khuẩn như vậy, số lượng con của chúng trong môi trường của 1000 vi khuẩn, kết quả cuối cùng là từ 334 đến 667.

Hình 1.

**M312.** Trong hình bình hành $P_1$ có hình bình hành $P_2$, trong đó lần lượt có hình bình hành $P_3$, các cạnh $P_3$ song song với các cạnh $P_1$. Hãy chứng minh rằng ít nhất một cạnh của hình bình hành $P_3$ không nhỏ hơn một nửa độ dài cạnh $P_1$ song song với nó.

Để một vi khuẩn nhất định có $N$ dòng gồm 1000 vi khuẩn trung bình, tách thành hai, có dòng $N'$ và $N''$ tương ứng. Khi đó $N = N' + N''$, và do đó một trong các số $N'$ và $N''$ không nhỏ hơn $N/2$.

Hãy xem xét trình tự vi khuẩn $A_1, A_2, A_3, \ldots, A_m$, trong đó $A_1$ là vi khuẩn đầu tiên, $A_{k+1}$ (đối với $k = 1, 2, \ldots, m-1$) là một trong hai vi khuẩn được tạo ra từ sự phân chia $A_k$ có ít nhất nhiều dòng như chị em của nó và $A_m$ là một trong 1000 vi khuẩn tạo ra ở cuối. Để $A_k$ có luồng $N_k$. Sau đó trình tự
$$N_1 = 1000, N_2, N_3, \ldots, N_{m-1}, N_m = 1$$
giảm nhưng mỗi số hạng trong đó không nhỏ hơn một nửa số hạng trước: $N_k > N_{k+1} \geq N_k/2$. (Trong Hình 1, mô tả quá trình phân chia vi khuẩn dưới dạng “cây phả hệ”, chuỗi vi khuẩn $A_1, A_2, \ldots, A_m$ được hiển thị; ở đây $N_1 = 16, N_2 = 9, N_3 = 5, N_4 = 3, N_5 = 2, N_6 = 1$.) Nếu chúng ta chọn $j$ sao cho $N_{j-1} \geq 668$ và $N_j < 668$, chúng ta nhận được $334 \leq N_j \leq 667$, tức là vi khuẩn $A_j$ sẽ thỏa mãn điều kiện đã cho.

Theo cách tương tự, người ta có thể chứng minh rằng nếu cuối cùng kết quả là $M$ vi khuẩn, thì đối với bất kỳ $c$ tự nhiên nào cũng có một vi khuẩn có số lượng con cái $N$ thỏa mãn điều kiện $c \leq N < 2c$.

N. B. Vasiliev

Trước hết chúng ta hãy lưu ý rằng nếu hình bình hành $ABCD$ treo vào hình bình hành $KLMN$ (xem Hình 2), thì chúng có tâm đối xứng chung $O$. Điều này xuất phát từ thực tế là khi tính đối xứng tương đối với $O$, hình bình hành $KLMN$ đi vào chính nó và cạnh $AB$ của hình bình hành $ABCD$ đi qua

*) Lời giải bài toán M310 có trong bài viết của G. A. Gurevich và “Trình tự không lặp lại («Kvant», 1975, số 9).

⟦folio 43⟧

thành một đoạn song song có chiều dài bằng nhau với các đầu ở các cạnh tương ứng của hình bình hành KLMN, tức là thành đoạn CD.

Do đó, các hình bình hành $P_1, P_2$ và $P_3$ có chung tâm đối xứng. Từ đó, chúng ta thu được rằng bốn hình bình hành tô bóng nằm ở các góc $K, L, M$ và $N$ là bằng nhau; Chúng ta hãy biểu thị độ dài các cạnh của chúng lần lượt là $x$ và $y$.

Gọi $a$ và $b$ là độ dài các cạnh của hình bình hành $P_3$. Khi đó độ dài các cạnh của hình bình hành $P_1$ bằng $(a + 2x)$ và $(b + 2y)$. Chúng ta cần chứng minh rằng $a \geq \frac{a + 2x}{2}$ hoặc $b \geq \frac{b + 2y}{2}$, tức là $a \geq 2x$ hoặc $b \geq 2y$. Điều này sẽ đúng nếu chúng ta chứng minh bất đẳng thức sau: $ab \geq 4xy$.

Xét một hình bình hành có ba đỉnh là các điểm $A, L$ và $B$. Vì đường chéo $AB$ chia nó và các hình bình hành góc - phía dưới bên trái và phía trên bên phải - thành các hình tam giác bằng nhau nên diện tích của các hình bình hành được tô bóng trong Hình 2 là bằng nhau. Tương tự như vậy, diện tích của các hình bình hành được tô màu vàng, đỏ và xanh lục là bằng nhau: tất cả các hình bình hành được tô màu đều có kích thước bằng nhau. Rõ ràng (xem hình ok) tổng diện tích của các hình bình hành được tô bóng không vượt quá diện tích của hình bình hành $P_3$. Nhưng diện tích của một hình bình hành được tô bóng là $xy \cdot \sin \alpha$, và diện tích $P_3$ là $ab \cdot \sin \alpha$; Có nghĩa,

$$ab \geq 4xy,$$

đó là những gì được yêu cầu.

I. N. Klumova

**M313. Cho một góc có đỉnh O. Xét một tập hợp bốn đỉnh M của hình bình hành ONML, các đỉnh N và L nằm trên các cạnh của một góc cho trước và diện tích bằng một giá trị không đổi. (Tập hợp này được gọi là synerbola.) Chứng minh rằng trên bisserps đây là một góc và trên phần mở rộng của nó cũng có các điểm $F_1$ và $F_2$ ($2de |F_1O| = |F_2O|$), mà hiệu khoảng cách

$$||F_1M| - |F_2M||$$

không phụ thuộc vào điểm $M$.**

Đặt $2\alpha$ là một góc cho trước, $A$ là đỉnh của hyperbol (điểm giao nhau của nó với bisserse), $A'$ là một điểm đối xứng đối với $O$, $KMQ$ là đường vuông góc với bisserpse này đi qua $M$ (K nằm trên bisserse, $Q$ - trên cạnh góc, xem Hình 3).

Chúng ta hãy giới thiệu các ký hiệu sau: $r_1 = |F_1M|$, $r_2 = |F_2M|$, $a = |OA| = |OA'|$, $x = |ON|$, $y = |OL|$, $r = |OM|$, $\varphi = \widehat{AOM}$, cuối cùng, $c$ là khoảng cách cần thiết của các điểm $F_1$ và $F_2$ tính từ đỉnh $O$ của góc (cường điệu ở giữa). (Đối với những người muốn nói đến hình học giải tích: $x$ và $y$ là tọa độ xiên của điểm; $M$, $a$ và $\varphi$ là tọa độ cực của điểm đó.)

⟦folio 44⟧

Theo điều kiện bài toán, hình bình hành màu xanh và hình bình hành màu vàng phải có cùng diện tích:

$$k = xy \sin 2\alpha = \left( \frac{a}{2 \cos \alpha} \right)^2 \sin 2\alpha,$$

Ở đâu

$$xy = \frac{a^2}{4 \cos^2 \alpha}. \tag{1}$$

Chúng ta cần tìm vị trí của $F_1$ và $F_2$ (tức là giá trị của $c$) sao cho hiệu $r_2 - r_1$ là như nhau đối với tất cả các điểm $M$ của hyperbol. Cụ thể, đối với đỉnh $A$ của nó, chênh lệch $|F_1A| - |F_2A|$ này, do tính đối xứng của $(|F_2A| = |F_1A'|)$, bằng $|A'A| = 2a$ (trục của hyperbol). Điều này có nghĩa là sự khác biệt này phải bằng

$$r_2 - r_1 = 2a. \tag{2}$$

Hãy tìm biểu thức $r_1$ và $r_2$ thông qua các hằng số $a, c$ và $\alpha$ (tất nhiên, những biểu thức này cũng sẽ bao gồm một số đại lượng thay đổi). Áp dụng định lý cosin cho tam giác $F_1MO, F_2MO$ và $OMN$, ta có:

$$r_{1,2}^2 = c^2 + r^2 \pm 2cr \cos \varphi \tag{3}$$

(ký hiệu trên cho $r_1$, ký hiệu dưới cho $r_2$) và

$$r^2 = x^2 + y^2 + 2xy \cos 2\alpha. \tag{4}$$

Góc $\varphi$ có thể được sử dụng ngay từ công thức (3): từ hình vẽ cho thấy rõ rằng

$$r \cos \varphi = |OK| = |OQ| \cos \alpha = (|OL| + |LQ|) \cos \alpha =$$

$$= (|OL| + |LM|) \cos \alpha = (x + y) \cos \alpha;$$

theo,

$$r_{1,2}^2 = c^2 + r^2 \pm 2c(x + y) \cos \alpha. \tag{3'}$$

Thay (4) vào (3') và sử dụng điều kiện (1) cùng các đẳng thức $\cos 2\alpha = 2 \cos^2 \alpha - 1$ và $x^2 + y^2 = (x + y)^2 - 2xy$, chúng ta thu được:

$$r_{1,2}^2 = c^2 + (x + y)^2 - 2xy + 2xy \cos 2\alpha \pm 2c(x + y) \cos \alpha =$$

$$= c^2 + (x + y)^2 - \frac{a^2}{2 \cos^2 \alpha} +$$

$$+ \frac{a^2}{2 \cos^2 \alpha} (2 \cos^2 \alpha - 1) \pm 2c(x + y) \cos \alpha =$$

$$= \left[ c^2 - \frac{a^2}{2 \cos^2 \alpha} \right] + \left[ (x + y)^2 + a^2 \pm 2c(x + y) \cos \alpha \right]. \tag{5}$$

Làm схх vì $c$ là tùy ý. Bây giờ chúng ta hãy chọn nó để công thức (5) có dạng đơn giản hơn. Hãy đặt $c = \frac{a}{\cos \alpha}$ (sau đó $|OF_2| = |OB|$, xem hình). Khi đó công thức (5) có dạng sau:

$$r_{1,2}^2 = (x + y)^2 + a^2 \pm 2(x + y) a = [(x + y) \pm a]^2.$$

Từ hình vẽ cho thấy rõ rằng $x + y > a$ ($|OQ| > |OA|$); kể từ đây,

$$r_1 = (x + y) + a, \quad r_2 = (x + y) - a.$$

Điều này mang lại cho chúng tôi $r_1 - r_2 = 2a$. Thật thú vị khi lưu ý rằng $r_1 + r_2 = 2(x + y)$, tức là, từ bất kỳ lũy thừa nào của hyperbol đều được xem xét cho đến khi các tiêu điểm của nó là hình bình hành biến thiên khác nhau nằm trong một hyperbola nhất định.

⟦folio 45⟧

M315. *) Trên mỗi cạnh của một đa giác lồi, một mũi tên được đặt sao cho có ít nhất một mũi tên đi vào và rời khỏi mỗi đỉnh của đa hữu cơ. Chúng ta hãy chứng minh rằng có ít nhất hai mặt của một khối đa hữu cơ, mỗi mặt có thể đi vòng quanh chu vi, di chuyển theo hướng mũi tên trên các cạnh của nó.

Hình 4.

Hình 5.

F318. Tại mức $C_1$ thì điện dung của hệ tụ điện trên Hình 6 bằng: a) $C$; b) $kC$ ($k \neq 1$); c) $C_1$?

Hãy gọi trình tự
$$A_1A_2, A_2A_3, \dots, A_{t-1}A_t$$
xương sườn đa hữu cơ bởi
$$P = A_1A_2 \dots A_t$$
nếu trên tất cả các cạnh này, các mũi tên hướng theo cùng một hướng: từ $A_1$ đến $A_2$, từ $A_2$ đến $A_3$, ..., từ $A_{t-1}$ đến $A_t$ hoặc từ $A_t$ đến $A_{t-1}$, từ $A_{t-1}$ đến $A_{t-2}$, ..., từ $A_2$ đến $A_1$.

Vì, theo điều kiện, ít nhất một mũi tên đi vào và rời khỏi mỗi đỉnh của đa giác, nên bất kỳ đường dẫn nào cũng có thể bị loại bỏ theo cả hai hướng bằng cách gắn các cạnh mới vào các đầu của nó.

Bắt đầu với một cạnh tùy ý $A_1A_2$ của đa hữu cơ (rất/không, một đường dẫn), chúng ta sẽ xây dựng tuần tự các đường dẫn $A_1A_2A_3, A_1A_2A_3A_4$, v.v., cho đến khi chúng ta có được một đường dẫn trong đó một trong các đỉnh gặp nhau hai lần: $A_s = A_t$, $1 \leq s < t$. Do đó, chúng ta thu được một đường dẫn khép kín $P_0 = A_sA_{s+1} \dots A_t$ (tất cả các đỉnh của nó, ngoại trừ các đỉnh cực trị, $A_s = A_t$, đều khác nhau, Hình 4).

Vì đa hữu cơ là lồi nên đường dẫn $P_0$ chia bề mặt của nó thành hai vùng $D$ và $D'$. Hãy chứng minh rằng ở mỗi vùng có ít nhất một mặt có thể đi xung quanh chu vi, di chuyển theo hướng mũi tên ở hai bên của nó.

Hãy lấy diện tích $D$; đường dẫn nó bao gồm $k_0 \geq 1$ các mặt của đa hữu cơ. Nếu $k_0 = 1$ thì vùng này (được giới hạn bởi đường dẫn $P_0$) là khuôn mặt mong muốn. Nếu $k_0 > 1$, thì trong vùng $D$ có một cạnh $A_iB$ không nằm trong đường dẫn $P_0$ (và $A_i$ được bao gồm trong $P_0$). Bắt đầu từ cạnh này, chúng ta sẽ xây dựng một đường đi qua đỉnh $B$ bên trong vùng $D$ cho đến khi chúng ta có được một đường đi trong đó một trong các đỉnh gặp nhau hai lần (nếu chúng ta đi đến ranh giới của vùng $D$, sau đó đi xa hơn dọc theo đường dẫn $P_0$ sẽ quay trở lại $A_i$). Bằng cách này, chúng ta có được một đường dẫn khép kín mới $P_1$ (Hình 5). Đường dẫn $P_1$ nằm bên trong vùng $D$ và không trùng với $P_0$; Điều này có nghĩa là vùng được giới hạn bởi đường dẫn $P_1$ bao gồm $k_1 < k_0$ các mặt của đa hữu cơ. Nếu $k_1 = 1$ thì $P_1$ giới hạn cạnh cần thiết; nếu $k_1 > 1$, thì theo cách tương tự, chúng ta sẽ xây dựng một đường dẫn khép kín $P_2$, giới hạn vùng bao gồm các mặt $k_2 < k_1$, v.v. Vì tất cả các số $k_i$ đều là số tự nhiên và $k_{i+1} < k_i$, nên sau một số bước hữu hạn, chúng ta thu được một đường dẫn khép kín $P_0$, giới hạn chính xác một mặt mong muốn.

Bạn có thể tìm thấy cạnh bắt buộc thứ hai theo cách tương tự bằng cách xem $D'$ - cạnh bắt buộc thứ hai từ vùng mà đường dẫn $P_0$ chia đa giác của chúng ta.

A. M. Zubkov

◆ Nối hệ tụ điện đang xét vào nguồn có điện áp $U$. Từ thông điệp về tính đối xứng, suy ra rằng điện tích của các tụ điện trong xương $kC$ sẽ giống nhau. Chúng tôi biểu thị chúng bằng $Q$. Tương tự, điện tích $q$ của tụ điện embone $C$ bằng nhau. Điện tích của tụ $C_1$ được ký hiệu là $q_1$. Hãy xem xét điện tích của từng tụ điện (xem Hình 6).

Điện tích $Q_x = Q + q$ của một hệ tụ điện liên hệ với điện áp $U = U_2 + U_3 = \frac{q}{C} + \frac{Q}{kC}$ đặt vào hệ thống, tương ứng với $Q_x = C_xU$, trong đó $C_x$ là điện dung của hệ thống, tức là
$$Q + q = C_x \left( \frac{q}{C} + \frac{Q}{kC} \right).$$

*) Lời giải bài toán M314 sẽ được đăng trong số tiếp theo của tạp chí.

⟦folio 46⟧

Công do trường điện thực hiện buộc phải vượt qua bất kỳ điện tích nào, và do đó, đơn điện tích dọc theo một quỹ đạo kín luôn bằng không. Ví dụ, bỏ qua đường viền trên (xem Hình 6) ngược chiều kim đồng hồ, chúng ta có được

$$U_1 - U_2 + U_3 = \frac{q_1}{C_1} - \frac{q}{C} + \frac{Q}{kC} = 0.$$

Chúng ta cũng hãy sử dụng định luật bảo toàn điện tích. Phần của hệ thống được hiển thị trong Hình 6 có màu đỏ (bạn cũng có thể thấy phần được hiển thị bằng màu khác) ở trạng thái trung tính trước khi hệ thống được kết nối với nguồn. Vì phần này bị cô lập nên tổng điện tích của nó sẽ bằng 0:

$$q + q_1 - Q = 0.$$

Từ phương trình (1)—(3) suy ra rằng

$$C_x = \frac{2kC + (1+k)C_1}{2C_1 + (1+k)C} C.$$

Từ đây dễ dàng có được điều đó

a) $C_x = C$ với $C_1 = -C$, điều này là không thể;
b) $C_x = kC$ ($k \neq 1$) cho $C_1 = -kC$, điều này cũng không thể xảy ra;
b) $C_x = C_1$ tại $C_1 = \sqrt{k} C.$

F319. Nhìn 2F từ đường thu L1 với tiêu điểm F, chúng ta thấy một vật sáng. Độ rọi của ảnh của vật trên màn bằng $E_0$. Giữa màn và vạch L1 đặt một vạch tán xạ L2 có tiêu cự 2F. Để thu được ảnh của một vật, màn ảnh phải được chuyển sang giá trị bằng F. Xác định độ chói của ảnh của vật trong trường hợp thứ hai.

Từ điều kiện bài toán suy ra rằng ảnh của vật tạo bởi thấu kính L1 nằm cách nó một khoảng 2F (điều này có thể dễ dàng kiểm tra bằng công thức thấu kính). Đặt thấu kính khuếch tán L2 cách đường L1 một khoảng x (Hình 7). Rõ ràng, để có được hình ảnh rõ nét, màn hình phải di chuyển dữ liệu ra khỏi đường truyền. Ảnh trước đó được tạo bởi thấu kính L1 có thể được coi là vật thể tối thiểu cho đường thẳng L2. Khi đó khoảng cách từ “vật” đến đường thẳng L2 sẽ là 2F - x, và khoảng cách từ ảnh đến đường thẳng này sẽ là 3F - x. Từ công thức thấu kính

$$-\frac{1}{2F-x} + \frac{1}{3F-x} = -\frac{1}{2F}$$

x có thể được tìm thấy. Tính toán cho x = F.

Bây giờ hãy tìm độ phóng đại tuyến tính của thấu kính L2:

$$\Gamma = \frac{H}{h} = \frac{3F-x}{2F-x} = 2.$$

**F320.** *Trong một bình sơ tán có dung tích $V = 1$ l có 1 g uranium hydrua $\mathrm{UH_3}$. Khi đun nóng đến nhiệt độ $t_1 = 400^\circ\mathrm{C}$, hydrua phân hủy hoàn toàn thành uranium (trọng lượng nguyên tử $A = 238$) và hydro. Tìm áp suất của hydro trong bình ở nhiệt độ này.*

**F321.** *Cát mịn được đổ lên màng ngang. Màng dao động với tần số $\nu = 500$ Hz trong mặt phẳng thẳng đứng. Biên độ dao động của màng là bao nhiêu nếu các hạt cát nhảy lên độ cao $h = 3$ mm so với vị trí cân bằng của màng?*

⟦figure⟧
Hình 8.

⟦column⟧

Do đó, nếu toàn bộ quang thông rơi vào thấu kính $\mathrm{Л_1}$ đi qua thấu kính $\mathrm{Л_2}$, thì trong trường hợp thứ hai, quang thông này phân bố trên một diện tích lớn hơn $\Gamma^2 = 4$ lần. Do đó, độ chiếu sáng của hình ảnh sẽ ít hơn bốn lần, tức là $E = E_0/4$.

◆

Phản ứng phân hủy uranium hydrua tuân theo phương trình
$$2\mathrm{UH_3} = 2\mathrm{U} + 3\mathrm{H_2},$$
nghĩa là, từ 482 *g* (hai mol) uranium hydrua, người ta thu được 476 *g* (hai mol) uranium và 6 *g* (ba mol) hydro. Theo đó, từ 1 *g* uranium hydrua bạn sẽ nhận được $m = 6/482$ *g* hydro. Coi hydro là một loại khí lý tưởng, chúng ta tìm thấy áp suất của nó trong các điều kiện nhất định ($T = 673^\circ\mathrm{K}$, $V = 10^{-3}$ *m³*). Từ phương trình trạng thái của khí lý tưởng

$$p = \frac{m}{\mu}\frac{RT}{V} \approx 35\cdot 10^3 \ \ \textit{н/м}^2.$$

◆

Cho màng dao động theo quy luật
$$x = A \sin \omega t,$$
trong đó $x$ là độ dời khỏi vị trí cân bằng, $A$ là biên độ, $\omega = 2\pi\nu$ là tần số dao động tuần hoàn. Tại thời điểm ban đầu $t = 0$ màng và các hạt cát trên đó ở vị trí cân bằng. Màng sau đó được di chuyển ra khỏi vị trí cân bằng, ví dụ như hướng lên trên.

Một hạt cát chuyển động dọc theo màng chịu tác dụng của hai lực: trọng lực $mg$ và lực $\mathbf{N}$ của phản ứng màng (Hình 8). Hãy viết phương trình chuyển động của hạt cát:
$$N - mg = ma.$$
Tại thời điểm hạt cát tách ra, phản lực $N$ bằng 0 và do đó gia tốc của hạt cát là $a = -g$. Do đó, một hạt cát vỡ ra khỏi màng tại thời điểm $t_0$ khi gia tốc của nó bằng $-g$. Sau đó, hạt cát tiếp tục chuyển động lên độ cao $h$ khi một vật được ném thẳng đứng lên trên ở độ cao $h_0$, bằng độ lệch của màng so với vị trí cân bằng tại thời điểm $t_0$, với vận tốc ban đầu $v_0$, bằng vận tốc của màng tại cùng thời điểm $t_0$ (xem Hình 8). Theo định luật bảo toàn cơ năng

$$mgh_0 + \frac{mv_0^2}{2} = mgh. \qquad (*)$$

Bây giờ chúng ta hãy xem xét chuyển động của màng chi tiết hơn và liên hệ các đại lượng $h_0$ và $v_0$ với biên độ dao động của màng.

Tốc độ của màng tại bất kỳ thời điểm nào là $v = \omega A \sin(\omega t + \pi/2) = \omega A \cos \omega t$ và gia tốc là $a = -\omega^2 x = -\omega^2 A \sin \omega t$. Vào giây phút chia ly $t_0$

$$v = v_0 = \omega A \cos \omega t_0,$$
$$a = -g = -\omega^2 A \sin \omega t_0,$$
$$x = h_0 = A \sin \omega t_0.$$

Từ phương trình gia tốc $\sin \omega t_0 = \dfrac{g}{\omega^2 A}$, do đó $h_0 = g/\omega^2$ và $v_0 = \omega A \cos \omega t_0 = \sqrt{\omega^2 A^2 - g^2/\omega^2}$

Thay các giá trị $h_0$ và $v_0$ vào phương trình $(*)$, ta được

$$A = \frac{\sqrt{2gh\omega^2 - g^2}}{\omega^2} \approx 77{,}2\cdot 10^{-6} \ \textit{м} \approx 0{,}077 \ \textit{мм}.$$

*B. B. Bukhovtsev*

⟦folio 47⟧
