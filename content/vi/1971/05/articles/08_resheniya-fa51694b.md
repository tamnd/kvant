---
id: 1971-5-resheniya-fa51694b
issue: kvant_1971_5
year: 1971
number: "5"
title: Lời giải các bài toán M31—M33; F43, F48—F51
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 34
page_last: 40
page_labels: 32-38
tag: P8XZ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 33fa895532fcd29b6733bc807839d602db602d656ae04a89b7e3dbeb4cecac36
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1971/05/articles/08_resheniya-fa51694b.md
source_content_sha256: 4cbd00a132c3c5f38a5b2b221a0ed5acd080708b33e16812a1191668c89e420b
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦folio 32⟧

Lời giải

Trong số này, chúng tôi công bố lời giải các bài toán M31—M33

M31

Một tờ giấy hình vuông được cắt theo đường thẳng thành hai phần. Một trong các phần nhận được lại được cắt thành hai phần, và cứ làm như vậy nhiều lần. Cần thực hiện ít nhất bao nhiêu nhát cắt để trong các phần nhận được có đúng 100 đa giác 20 cạnh?

Sau mỗi lần cắt, tổng số mảnh giấy tăng thêm 1 (vì một mảnh biến mất và xuất hiện hai mảnh mới), do đó sau $n$ lần cắt sẽ có $(n+1)$ mảnh giấy.

Bây giờ hãy đếm xem tổng số đỉnh của tất cả các mảnh sau $n$ lần cắt có thể là bao nhiêu. Sau mỗi lần cắt, tổng số đỉnh tăng thêm hoặc 2 (nếu cắt qua các đỉnh), hoặc 3 (nếu cắt qua một đỉnh và một cạnh), hoặc 4 (nếu cắt qua 2 cạnh). Vì lúc đầu có 4 đỉnh, nên sau $n$ lần cắt, tổng số đỉnh của tất cả các mảnh không lớn hơn $4n+4$.

Giả sử sau $N$ lần cắt nhận được 100 đa giác 20 cạnh. Vì tổng số mảnh nhận được khi đó là $N+1$, nên ngoài các đa giác 20 cạnh này còn có $N+1-100$ mảnh nữa. Mỗi mảnh trong số đó có không ít hơn ba đỉnh, do đó tổng số đỉnh của tất cả các mảnh không ít hơn $100\cdot 20+(N-99)\cdot 3$. Như đã chứng minh trước đó, số này không lớn hơn $4N+4$. Vậy,

$$4N+4 \geq 100\cdot 20+(N-99)\cdot 3 = 3N+1703,$$

suy ra $N \geq 1699$.

Như vậy, chúng ta đã chứng minh rằng không thể nhận được 100 đa giác 20 cạnh nếu thực hiện ít hơn 1699 nhát cắt. Đây là phần chính và khó nhất của chứng minh.

Bây giờ hãy chỉ ra cách có thể nhận được 100 đa giác 20 cạnh bằng 1699 nhát cắt. Đây là một cách: cắt hình vuông thành 100 hình chữ nhật (99 nhát cắt), rồi biến mỗi hình chữ nhật thành một đa giác 20 cạnh bằng 16 nhát cắt, bằng cách cắt các tam giác ở các góc (1600 nhát cắt). Tổng cộng sẽ có 1699 nhát cắt.

Đáp số. Có thể nhận được 100 đa giác 20 cạnh bằng 1699 nhát cắt, còn nếu thực hiện ít nhát cắt hơn thì không thể nhận được 100 đa giác 20 cạnh.

Hoàn toàn tương tự, có thể tìm được cần thực hiện ít nhất bao nhiêu nhát cắt để nhận được đúng $k$ đa giác l cạnh.

Lời giải chính xác bài toán này được D. Grigoriev từ Leningrad và V. Livits từ Zaporozhye gửi đến.

I. N. Bernistei

M32

Trong mọi ô của bảng $100 \times 100$ có dấu cộng hoặc dấu trừ. Được phép đồng thời đổi dấu trong mọi ô của một hàng hoặc một cột. Có thể, tiếp tục thực hiện các phép biến đổi như vậy nhiều lần, nhận được một bảng có đúng 1970 dấu trừ không?

Giả sử ở hàng thứ $i$ ta đã đổi dấu $x_i$ lần, ở cột thứ $k$ — $y_k$ lần. Khi đó, trong ô nằm ở giao của hàng thứ $i$ và cột thứ $k$, dấu sẽ đổi $x_i+y_k$ lần. Do đó, trong ô này sẽ có dấu trừ khi và chỉ khi $x_i+y_k$ là số lẻ. Như vậy, tổn-

⟦folio 33⟧

g số dấu trừ trong bảng nhận được chỉ phụ thuộc vào tính chẵn lẻ của các số $x_i$ và $y_k$; trên hình 1, thay cho các số chẵn đặt các số không, thay cho các số lẻ — các số một. Giả sử $x$ là số các số lẻ trong các $x_i$; $y$ — số các số lẻ $y_k$ (trên hình $x = 5, y = 4$). Khi đó, như dễ tính được, tổng số dấu trừ trong bảng sẽ bằng

$$x(100-y)+(100-x)y = 100x+100y-2xy,$$

trong đó $x, y$ là các số nguyên.

Bây giờ trở lại bài toán của chúng ta và chứng minh rằng đáp án của nó là âm, tức là không thể thu được 1970 dấu trừ. Giả sử rằng ta đã thu được 1970 dấu trừ. Khi đó $1970 = 100x+100y-2xy$, từ đó

$$xy - 50x - 50y + 2500 = 1515.$$

Phân tích vế trái thành nhân tử, ta được

$$(x-50)(y-50) = 1515 = 15 \cdot 101.$$

Ta có

$$-50 \leq x-50 \leq 50, -50 \leq y-50 \leq 50.$$

Vì số 101 là số nguyên tố, nên либо $x-50$, либо $y-50$ chia hết cho 101 (vì tích của chúng chia hết cho 101). Nhưng từ các bất đẳng thức trước đó suy ra rằng либо $x-50$, либо $y-50$ bằng 0. Vậy ta đã thu được mâu thuẫn, điều này chứng minh rằng không thể thu được đúng 1970 dấu trừ.

Lời giải đúng do D. Grigoriev gửi.

A. V. Zelevinsky

M33

Cho số tự nhiên $n > 1000$. Lấy các số dư của phép chia số $2^n$ cho các số 1, 2, 3,..., $n$ và tìm tổng các số dư đó. Chứng minh rằng tổng này lớn hơn $2^n$.

Gọi tổng các số dư của $2^n$ khi chia cho các số 1, 2,..., $n$ là $S_n$. Ta sẽ củng cố khẳng định của bài toán và chứng minh rằng khi $n > 1000$ thì $S_n > 3,5n$. Đồng thời, bằng chính phương pháp ấy, ta sẽ chứng minh rằng

$$S_n > \frac{n}{2} (\log_2 n - 4)$$

với mọi $n$.

Chúng tôi chủ yếu theo lời giải của D. Grigoriev từ Leningrad. Lời giải dựa trên một nhận xét rất đơn giản: $2^n$ không chia hết cho một số nguyên lẻ khác 1, nên số dư khi chia $2^n$ cho số đó không nhỏ hơn 1. Từ đây dễ suy ra rằng với mọi $k > 1$ lẻ, số dư khi chia $2^n$ cho $2^l k$ không nhỏ hơn $2^l$. Thật vậy, giả sử số dư khi chia $2^{n-l}$ cho $k$ bằng $r$, tức là $2^{n-l} = mk + r$, trong đó $0 \leq r < k$, khi đó $2^n = m(2^l k) + 2^l r$, trong đó $0 \leq 2^l r < 2^l k$, tức là số dư khi chia $2^n$ cho $2^l k$ bằng $2^l r$, và vì $r \neq 0$, nên số dư này không nhỏ hơn $2^l$.

Từ đây suy ra rằng trong mọi trường hợp

$$S_n \geq 1 \cdot (\text{số lượng các số không vượt quá } n \text{ có dạng } 2k + 1, k > 1) + 2 \cdot (\text{số lượng các số không vượt quá } n \text{ có dạng } 2(2k + 1), k > 1) + 2^2 \cdot (\text{số lượng các số không vượt quá } n \text{ có dạng } 2^2(2k + 1), k > 1) + \dots$$

+ $2^l \cdot (\text{số lượng các số không vượt quá có dạng } 2^l(2k + 1), k > 1), (*)$

⟦folio 34⟧

trong đó $l$ được xác định bởi điều kiện $3 \cdot 2^l \leq n$, $3 \cdot 2^{l+1} > n$ (không có ý nghĩa gì khi lấy lớn hơn $l$, vì khi đó biểu thức trong ngoặc sẽ bằng không).

Có thể nói gì về vế phải của bất đẳng thức này?

Xét số hạng thứ $(i+1)$: $2^i(\ldots)$. Số đứng trong ngoặc, hiển nhiên, bằng số các số hạng không vượt quá $n$ của cấp số cộng $3 \cdot 2^i$, $5 \cdot 2^i$, $7 \cdot 2^i$, ..., tức là cấp số cộng có số hạng đầu $3 \cdot 2^i$ và công sai $2 \cdot 2^i$. Số các số hạng như vậy không nhỏ hơn $\frac{n-3 \cdot 2^i}{2^{i+1}}$ và, do đó, số hạng thứ $i$ của vế phải bất đẳng thức không nhỏ hơn $\frac{n}{2} - \frac{3}{2} \cdot 2^i$. Về cơ bản, lời giải bài toán đến đây là xong. Tất cả phần còn lại là các phép biến đổi khác nhau của vế phải (*) bằng các bất đẳng thức đã thu được. Chẳng hạn, thay tổng ở vế phải (*) bằng tám số hạng. Khi đó ta được

$$S_n > 8 \cdot \frac{n}{2} - \frac{3}{2} \sum_{i=0}^{7} 2^i >$$

$$> 8 \cdot \frac{n}{2} - \frac{3}{2} \cdot 2^8 = 3,5n + \left(\frac{n}{2} - 384\right).$$

Với $n > 1000$, biểu thức trong ngoặc là dương và, do đó, ta đã chứng minh rằng $S_n > 3,5n$ khi $n > 1000$. Như vậy, bài toán M33 được giải hoàn toàn.

Tuy nhiên, có thể thu được một bất đẳng thức chính xác hơn. Cộng tất cả các số hạng ở vế phải của (*), ta được:

$$S_n > (l+1) \frac{n}{2} - \frac{3}{2} \sum_{i=0}^{l} 2^i >$$

$$> (l+1) \frac{n}{2} - \frac{3 \cdot 2^{l+1}}{2}.$$

Dùng các bất đẳng thức $3 \cdot 2^l \leq n$, $3 \cdot 2^{l+1} > n$, ta thấy rằng

$$S_n > \frac{n}{2} \log_2 \frac{n}{3} - n =$$

$$= \frac{n}{2} \left(\log_2 \frac{n}{3} - 2\right) > \frac{n}{2} \left(\log_2 n - 4\right).$$

Công thức này cho thấy, chẳng hạn, rằng nếu $n > 2^{1004}$, thì $S_n > 500 n$.

Bài toán a. Tổng các số dư khi chia các số $2^{l+1}$, $2^{l+L}$ cho số lẻ $m > 1$ lớn hơn $\frac{m}{2} \left(\frac{L}{\log_2 2m} - 1\right)$.

Với sự trợ giúp của bài toán này, lời giải của nó sẽ được đưa ra dưới đây, có thể chứng minh rằng với vô số giá trị $n$ tổng $S_n$ trên thực tế lớn hơn nhiều so với $\frac{n}{2} \left(\log_2 n - 4\right)$, tức là có thể chứng minh rằng ước lượng $S_n > \frac{n}{2} \left(\log_2 n - 4\right)$ thô hơn nhiều đối với vô số giá trị $n$. Điều đó cũng không có gì đáng ngạc nhiên, vì phương pháp chứng minh của chúng ta không tính đến nhiều số dư khác không, trong khi các số dư này thường lớn. Đồng thời, các đại lượng $S_n$ khi $n$ tăng không thể tăng quá nhanh, vì hiển nhiên $S_n \leq 1 + 2 + \ldots + (n-1) = \frac{n(n-1)}{2}$.

Chúng tôi cho rằng giả thuyết sau đây có lẽ đúng:

Giả thuyết 1. Với $n$ đủ lớn, bất đẳng thức $S_n \leq \frac{n^2}{4}$ là đúng;

b) tồn tại một số dương $c > 0$ sao cho $cn^2 \leq S_n$.

Chúng tôi không biết cách chứng minh cũng như kiểm tra các khẳng định này. Hơn nữa, chúng tôi không biết liệu giả thuyết yếu hơn sau đây có đúng không.

Giả thuyết 2. Tồn tại một số dương $c > 0$ sao cho bất đẳng thức $cn^2 \leq S_n$ đúng với vô số giá trị $n$.

Nếu bạn đã chứng minh hoặc kiểm tra được một trong các giả thuyết này, hãy gửi cho chúng tôi lập luận của bạn. Nếu chúng tỏ ra thú vị, chúng tôi sẽ công bố chúng trong một trong các số báo. Như một sự xác nhận yếu của giả thuyết 2, có thể chứng minh điều sau đây.

Định lý. Với vô số giá trị của $n$ bất đẳng thức sau đúng

$$S_n > \frac{n^2}{132 \log_2 n}.$$

Định lý được suy ra từ bài toán theo cách sau. Xét tổng $\Sigma_k$ các số dư khi chia các số $2^{k+1}$, ..., $2^n$ cho số $k$. Theo bài toán, khi $k$ lẻ thì tổng $\Sigma_k$ khá lớn, vì vậy số $\Sigma_1 + \Sigma_2 + \ldots + \Sigma_n$ cũng lớn. Nhưng, như dễ nhận*

*) Số $\frac{n^2}{132 \log_2 n}$ khi $n$ lớn lớn hơn rất nhiều so với số $\frac{n}{2} \left(\log_2 n - 4\right)$. Không khó để chứng minh, chẳng hạn, rằng khi $n$ đủ lớn tỉ số của các số này lớn hơn $\sqrt{n}$.

⟦folio 35⟧

nhận xét rằng, $S_1 + S_2 + \dots + S_n = \Sigma_1 + \dots + \Sigma_n$,
do đó tổng ở vế trái cũng
lớn và, vì thế, một trong các số hạng, chẳng hạn $S_l$, cũng lớn. Chúng tôi dành việc trình bày cẩn thận chứng minh cho bạn đọc. Bây giờ chuyển sang giải bài toán.

Lời giải bài toán. Hãy viết các số dư khi chia các số $2^{l+1}, \dots, 2^l + L$ cho $m$ và đặt giữa hai số dư liên tiếp một “dấu tích” nếu số thứ nhất lớn hơn số thứ hai. Khi đó, thứ nhất, số dư đứng trước dấu tích lớn hơn $\frac{m}{2}$, thứ hai, số lượng các số giữa hai dấu tích liên tiếp nhỏ hơn $\log_2 2m$, vì các số dư giữa hai dấu tích tạo thành một cấp số nhân với công bội 2 (thật vậy, $2\log_2 2m - 1 = m > m - 1$, còn mọi số dư không lớn hơn $m - 1$). Như vậy, số khoảng giữa các dấu tích lớn hơn $\frac{L}{\log_2 2m} - 1$ và vì ở cuối mỗi khoảng có một số lớn hơn $\frac{m}{2}$, nên mọi điều đã được chứng minh.

A. G. Kushirenko

Trong số này chúng tôi công bố lời giải các bài toán F43, F48—F51

F43

Tìm áp suất tại tâm của một hành tinh lỏng bán kính $R$, nếu chất lỏng không nén được và có khối lượng riêng $\rho$.

Chia thể tích hành tinh thành các lớp cầu mỏng có bề dày $\Delta r$. Dễ thấy rằng hợp lực hấp dẫn tác dụng từ phía lớp lên một hạt nằm bên trong lớp đó bằng không. Thật vậy, hãy xét một hình nón có góc ở đỉnh nhỏ, chứa một phần khối lượng $m$. Hình nón cắt từ lớp các phần có diện tích $s_1$ và $s_2$ (hình 1). Nếu khối lượng vật chất trên một đơn vị diện tích của lớp bằng $\mu$, thì các lực hấp dẫn tác dụng lên khối lượng $m$ từ phía các phần $s_1$ và $s_2$ bằng

$$F_1 = \gamma \frac{m\mu s_1}{r_1^2}, \quad F_2 = \gamma \frac{m\mu s_2}{r_2^2};$$

nhưng

$$\frac{s_1}{r_1^2} \cos \alpha_1 = \frac{s_2}{r_2^2} \cos \alpha_2 = \Omega$$

(Ω — góc khối tại đỉnh hình nón), và $\alpha_1 = \alpha_2$; các tam giác gạch bóng đồng dạng, tức là $\angle OA_1 M_1 = \angle OA_2 M_2, \angle OA_1 B_1 = \angle OA_2 B_2$ (chúng chắn cùng một cung) và $\alpha_1 = \angle OA_1 B_1 - \angle OA_1 M_1 a\alpha_2 = \angle OA_2 B_2 - \angle OA_2 M_2$.

Do đó $\frac{s_1}{r_1^2} = \frac{s_2}{r_2^2}$. Nhờ vậy

$$F_1 = F_2,$$ tức là các lực này cân bằng lẫn nhau. Tiến hành xét tương tự đối với các phần khác của lớp, ta sẽ chứng minh được khẳng định đã nêu.

Lực mà phần tử của lớp $\Delta s\Delta r$ bị hút về tâm hành tinh bằng

$$F = \gamma \frac{4}{3} \pi r^3 \rho \Delta s \Delta r\rho$$,

trong đó $r$ là khoảng cách từ phần tử này đến tâm hành tinh. Từ đó ta thấy rằng độ tăng áp suất trên đoạn có bề dày $\Delta s$ bằng

$$\Delta p = \frac{F}{\Delta s} = \frac{4}{3} \pi \gamma \rho^2 r \Delta r.$$

Do đó áp suất ở khoảng cách $r_0$ từ tâm hành tinh sẽ bằng

$$p = p_0 + \frac{4}{3} \pi \gamma \rho^2 \Sigma r \Delta r.$$

Vì tổng $r\Delta r$ bằng diện tích

⟦folio 36⟧

hình được giới hạn bởi đồ thị $y=r$ và trục $r$ (hình 2), nên

$$\sum r \Delta r = \frac{(R+r_0)(R-r_0)}{2} = \frac{R^2-r_0^2}{2}.$$

Do đó

$$p = p_0 + \frac{2}{3} \pi \rho^2 (R^2-r_0^2);$$

$p_0$ là áp suất trên bề mặt hành tinh, có thể coi bằng không. Khi đó

$$p = \frac{2}{3} \pi \rho^2 (R^2-r_0^2).$$

Tại tâm hành tinh ($r_0=0$), áp suất sẽ bằng

$$p_\mu = \frac{2}{3} \pi \rho^2 R^2.$$

Ф48

Một sợi dây có treo vật nặng được quấn quanh trục phần ứng của MÁY PHÁT ĐIỆN. Khi đi xuống, vật nặng làm quay phần ứng. Khi phần ứng đã quay đủ nhanh, một điện trở tải được nối vào các cực của MÁY PHÁT ĐIỆN. Hãy biểu diễn trên đồ thị sự phụ thuộc của tốc độ quay của phần ứng vào thời gian kể từ lúc vật nặng bắt đầu chuyển động.

Vì trước khi nối tải, mômen của các ngoại lực tác dụng lên phần ứng không đổi, nên phần ứng quay với gia tốc góc không đổi và tốc độ của nó tăng tỉ lệ với thời gian.

Sau khi nối tải, dòng điện chạy qua cuộn dây phần ứng. Do đó, trong từ trường của stato, một mômen lực sẽ tác dụng lên phần ứng, tỉ lệ với cường độ dòng điện (cũng như lực tác dụng trong từ trường lên dây dẫn có dòng điện). Mômen lực này hãm sự quay của phần ứng. Vì dòng điện chạy qua cuộn dây phần ứng tỉ lệ với suất điện động cảm ứng xuất hiện trong cuộn dây, còn suất điện động cảm ứng lại tỉ lệ với tốc độ biến thiên của từ thông xuyên qua cuộn dây, tức là với tốc độ góc quay của phần ứng, nên tại một tốc độ góc nào đó $\omega_0$, mômen lực tác dụng lên phần ứng từ phía vật nặng sẽ bằng mômen của lực hãm tác dụng lên phần ứng trong từ trường. $\omega_0$ chính là tốc độ quay ổn định của phần ứng.

Đồ thị sự phụ thuộc của tốc độ quay của phần ứng vào thời gian được chỉ ra trên hình 4. Đường màu đỏ ứng với trường hợp tốc độ quay của phần ứng tại thời điểm nối tải nhỏ hơn $\omega_0$, còn đường màu xanh — khi nó lớn hơn $\omega_0$.

Ф49

Một ống chữ U chứa đầy nước (hình 4). Không khí đã được hút ra khỏi một nhánh; áp suất không khí trong nhánh kia ở nhiệt độ $T_0=20^\circ C$ bằng áp suất khí quyển. Cả hai đầu ống đều được bịt kín. Hiệu độ cao của mực nước trong hai nhánh sẽ bằng bao nhiêu nếu đun nóng ống đến $T=100^\circ C$?

⟦folio 37⟧

Hình 4.

Áp suất trong nhánh trái bằng áp suất hơi bão hòa. Còn trong nhánh phải có cả không khí lẫn hơi nước, và áp suất bằng tổng các áp suất riêng phần của không khí và hơi nước. Hơn nữa, hơi trong bình bên phải cũng bão hòa, và áp suất riêng phần của nó bằng áp suất hơi trong nhánh trái. Vì vậy, khi xét sự cân bằng của nước, ta có thể không tính đến áp suất hơi trong các nhánh trái và phải.

Viết điều kiện cân bằng của nước trong ống tại $T_0=20^\circ\text{C}$:

$$\rho gh_0 = P_0, \quad P_0 = 1 \text{ amm.}$$

Suy ra

$$h_0 = \frac{P_0}{\rho g} \approx 10 \text{ m.}$$

Tại $100^\circ\text{C}$ áp suất không khí trong nhánh phải trở thành $P$, còn hiệu độ cao của mực nước trong hai nhánh là $h$. Khi đó

$$\rho gh = P. \quad (*)$$

$P$ liên hệ với $P_0$ bởi định luật khí kết hợp:

$$\frac{P_0 V_0}{T_0} = \frac{PV}{T},$$

và $l - l_0 = \frac{1}{2} (h - h_0)$. Vì $V_0 = l_0 s$, $V = ls$ (s là diện tích tiết diện của ống), nên từ đây ta tìm được

$$P = P_0 \frac{T}{T_0} \frac{l_0}{l} =$$

$$= P_0 \frac{T}{T_0} \frac{l_0}{l_0 + \frac{1}{2} (h - h_0)}.$$

Thay biểu thức này vào phương trình (*), ta được

$$h = \frac{P_0}{\rho g} \frac{T}{T_0} - \frac{l_0}{l_0 + \frac{1}{2} \Delta h},$$

hay

$$h = h_0 \frac{T}{T_0} \frac{l_0}{l_0 + \frac{1}{2} \Delta h}.$$

Giả sử $1/2 \Delta h \ll l_0$, ta được

$$h = h_0 \frac{T}{T_0} \approx 13 \text{ m};$$

$\Delta h \approx 3 \text{ m}, \frac{1}{2} \Delta h \approx 1,5 \text{ m} \ll l_0 = 15 \text{ m}$. Điều này có nghĩa là, bỏ qua $1/2 \Delta h$ so với $l_0$, ta thu được kết quả ít khác với kết quả chính xác.

Ф50

Trên một bàn nằm ngang nhẵn có hai khối lập phương giống nhau, khối lượng $m$, được nối với nhau bằng một lò xo có độ cứng $k$ và chiều dài $l_0$ ở trạng thái không biến dạng. Lên khối lập phương bên trái (hình 5) bắt đầu tác dụng một lực $F$ không đổi về độ lớn và hướng. Hãy tìm khoảng cách nhỏ nhất và lớn nhất giữa các khối lập phương trong chuyển động tiếp theo của hệ.

Giả sử khoảng cách $l$ giữa các khối lập phương là nhỏ nhất hoặc lớn nhất (ta sẽ gọi là «cực trị»). Khi đó cả hai khối lập phương chuyển động với cùng vận tốc $v$, và động năng của hệ bằng $2 \frac{mv^2}{2} = mv^2$. Đồng thời

⟦folio 38⟧

thế năng của hệ bằng thế năng của lò xo bị nén, tức là $kx^2/2$, trong đó $x$ là độ thay đổi chiều dài của lò xo ($x$ có thể dương — khi đó chiều dài lò xo $l = l_0 - x$ nhỏ hơn $l_0$, cũng có thể âm — khi đó chiều dài lò xo lớn hơn $l_0$). Cơ năng của hệ bằng tổng động năng và thế năng, tức là $mv^2 + kx^2/2$. Vì hệ nhận được năng lượng này nhờ công của lực $F$, nên ta có thể viết rằng

$$FL = mv^2 + \frac{kx^2}{2}.$$

(*)

$L$ — quãng đường khối lập phương bên trái đi được vào thời điểm chiều dài lò xo trở nên cực trị (hình 6): $L = S + \frac{l_0}{2} - \frac{(l_0 - x)}{2} = S + \frac{x}{2}$ ($S$ — quãng đường tâm khối của hệ đi được).

Vận tốc $v$ của các khối bằng vận tốc của tâm khối hệ. Một lực ngoài không đổi tác dụng lên hệ, và hệ chuyển động nhanh dần đều với gia tốc $a = F/2m$. Vì vậy, nếu ký hiệu $t$ là thời gian kể từ khi khởi-

Hình 7.

đầu chuyển động đến thời điểm chiều dài lò xo trở thành $L$, thì $v = at$ và $L = \frac{at^2}{2} + \frac{x}{2}$. Thay các biểu thức này của $v$ và $L$ vào phương trình (*), ta được

$$F \left( \frac{at^2}{2} + \frac{x}{2} \right) = ma^2 t^2 + \frac{kx^2}{2}.$$

Từ đây $\frac{F^2 t^2}{4m} + \frac{x}{2} F = \frac{F^2 t^2}{4m} + \frac{kx^2}{2}$ hoặc $Fx = kx^2$. Do đó, $x_1 = 0$, $x_2 = F/k$.

Như vậy, khoảng cách nhỏ nhất giữa các nhóm là $l_{\min} = l_0 - x_2 = l_0 - \frac{F}{k}$, còn khoảng cách lớn nhất là $l_{\max} = l_0 - x_1 = l_0$.

Ф51

Chụp ảnh một con hổ từ khoảng cách 20 mét là nguy hiểm. Máy ảnh lỗ kim có lỗ 1 mm phải có kích thước bao nhiêu để con hổ trên ảnh hiện ra có vằn? Khoảng cách giữa các vằn trên da hổ bằng 20 cm.

Máy ảnh lỗ kim là một chiếc hộp có lỗ. Một chùm tia rộng, đi từ mỗi điểm của vật được chụp (hình 7), rơi vào phim ảnh đặt trong máy. Để con hổ trên ảnh hiện ra có vằn, cần để các vùng mà những tia đi từ các điểm gần nhất của hai vằn kề nhau trên da hổ rơi vào không giao nhau. Muốn vậy, phim phải cách lỗ một khoảng $x$, lớn hơn $d/tg\alpha$.

Vì

$$tg\alpha = \frac{l/2}{L + x},$$ nên $x > \frac{2d(L + x)}{l}$.

Từ đây $x > \frac{2dL}{l\left(1 - \frac{2d}{l}\right)}$. $\frac{2d}{l} \ll 1$, vì vậy, bỏ qua $2d/l$ so với 1 ở mẫu số của công thức, ta được $x > \frac{2dL}{l} = 20$ cm. Kích thước của máy ảnh phải lớn hơn 20 cm.

I. Sh. Slovodetsky
