---
id: 1981-8-resheniya-zadach-m656-m660-f668-f672-ac902701
issue: kvant_1981_8
year: 1981
number: "8"
title: Lời giải bài toán M656—M660; F668—F672
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 42
page_last: 50
page_labels: 40, 41, 42, 44, 45, 46, 48
tag: 1Z4J
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 7d18761d9d4d4aa85db44ffc08283ac5dd477390d59758077c677758b3f2250a
prompt_sha256: draft-1
translated_from: content/ru/1981/08/articles/11_resheniya-zadach-m656-m660-f668-f672-ac902701.md
source_content_sha256: e088df7e47142c23e7bf523cbbbc9a5f29dcbcfb796d7f4b68c8fa515cf573a5
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 40⟧

F712. Một quả bóng nhỏ chuyển động với tốc độ không đổi $\vec{V}_0$ dọc theo một mặt phẳng nằm ngang nhẵn và rơi tại điểm $A$ vào một giếng hình trụ thẳng đứng có độ sâu $H$ và bán kính $R$. Vectơ vận tốc của quả bóng tạo một góc $\alpha$ với đường kính của giếng hướng về điểm $A$ (Hình 4). Với những tỷ lệ nào giữa $\vec{V}_0$, $H$, $R$ và $\alpha$ quả bóng có thể “ra khỏi” giếng sau khi va chạm đàn hồi với tường và nhà? (8)

S. Krotov

Lời giải bài toán

M656—M660; F668—F672

Chúng ta hãy đặt gốc của tất cả các vectơ tại một điểm và dựng một hình cầu có bán kính 1 với tâm tại điểm này. Chúng ta hãy lấy các điểm giao nhau của vectơ của chúng ta (hoặc phần mở rộng của chúng) với hình cầu không đổi và bao quanh một trong số chúng bằng nắp có “đường kính” $45^\circ$ (Hình 1) hoặc, về cơ bản là giống nhau, bản thân các vectơ có hình nón có mẫu $45^\circ$ (và dạng 1). Mệnh đề bài toán sẽ được chứng minh nếu chúng ta chứng minh rằng hai “lân cận” bất kỳ: hình mũ hoặc hình nón, cắt nhau. Và để làm điều này, hãy so sánh tổng diện tích bề mặt của nắp (hoặc tổng thể tích của hình nón) với diện tích bề mặt của hình cầu (tương ứng với thể tích của quả bóng).

Diện tích bề mặt của nắp (xem Hình 1; $H = R(1-\cos \varphi)$ là chiều cao của nắp) bằng $2\pi RH = 2\pi \left(1-\cos \frac{\pi}{8}\right) = 2\pi \left(1-\frac{\sqrt{2}+\sqrt{2}}{2}\right)$ (chúng tôi đã sử dụng công thức tính cosin của một góc polyvine). Mục tiêu của chúng ta là chứng minh rằng $30 \cdot 2\pi \left(1-\frac{\sqrt{2}+\sqrt{2}}{2}\right) > 4\pi$, tức là $\frac{\sqrt{2}+\sqrt{2}}{2} < \frac{4}{15}$. Sau khi thực hiện một số phép biến đổi đơn giản (hai trong số đó là phép biến đổi bình phương), chúng ta đi đến bất đẳng thức tương đương chính xác $\frac{1}{2} < \left(\frac{167}{225}\right)^2$. Từ đó, trong số những chiếc mũ anh ta sẽ tìm thấy hai chiếc mũ giao nhau; góc giữa các vectơ tương ứng của chúng sẽ nhỏ hơn $45^\circ$.

Nếu so sánh thể tích (Hình 2), chúng ta cần chứng minh rằng thể tích của mỗi hình nón lớn hơn $\frac{4}{90}$ π. Chúng tôi mời bạn tự mình kiểm tra điều này.

A. Tolpieo

M657. Trong bảng $n \times n$ chứa đầy các số, tất cả các dòng đều khác nhau. Chứng minh rằng bạn có thể xóa cột không có biểu quyết khỏi bảng sao cho tất cả các hàng trong bảng còn lại cũng khác biệt.

Giả sử điều ngược lại: bất kể chúng ta gạch bỏ bảng nào, bảng còn lại sẽ tìm thấy ít nhất một cặp hàng giống hệt nhau. Chúng ta hãy xem xét $n$ các bảng “rút gọn” thu được từ một bảng tương ứng nhất định bằng cách xóa bảng thứ nhất, thứ hai, ..., $n$. Đối với mỗi bảng này, hãy đánh dấu một cặp hàng giống hệt nhau (độ dài $n-1$). Bây giờ chúng ta sẽ giả sử rằng các hàng của bảng gốc là các điểm trên mặt phẳng và các điểm tương ứng với tham số được đánh dấu trong các bảng rút gọn được kết nối theo cặp. Chúng tôi nhận được hình ảnh về “$n$ điểm - $n$ phân đoạn”. Không khó để chứng minh rằng trong bức tranh như vậy sẽ có một chu trình - một đường đứt đoạn khép kín với các đỉnh tính từ các điểm của chúng ta. Đặt các đỉnh này tương ứng với các đường $A_1$, $A_2$, ..., $A_m$ và đặt đoạn $A_iA_{i+1}$ là kết quả của việc xóa

⟦folio 41⟧

cột $B_i$ ($i=1, 2, \dots, m-1$) và đoạn $A_m A_1$ - cột $B_m$.
Khi đó trong bảng gốc, các hàng $A_1$ và $A_2$ chỉ khác nhau ở cột $B_1$, các hàng $A_2$ và $A_3$ - chỉ khác nhau ở cột $B_2$, ...
các hàng $A_{m-1}$ và $A_m$ chỉ có trong cột $B_{m-1}$, vì vậy trong cột $B_m$, tất cả các hàng này đều có cùng một số.
Nhưng điều này mâu thuẫn với thực tế là các điểm tương ứng với hàng $A_1$ và $A_m$ được kết nối với nhau (vì theo quy ước, tất cả các hàng trong bảng gốc đều khác nhau, các hàng $A_1$ và $A_m$ phải khác nhau ở cột $B_m$).

A. Anjan

**M658. Trong một hình vuông, trên cạnh 1 có hữu hạn các đoạn thẳng (Hình 1) song song với cạnh của nó. Các đoạn đường có thể cắt nhau. Tổng độ dài của các đoạn được vẽ là 18. Chứng minh rằng trong số các phần mà hình vuông chia các điểm đó của đoạn thẳng đó, có một phần có diện tích không nhỏ hơn 0,01.**

◆ Tổng độ dài các cạnh của tất cả các phần mà hình vuông được chia thành các đoạn bằng $2 \cdot 18 + 4 = 40$ (độ dài của các đoạn đã vẽ được tính vào tổng này hai lần, độ dài các cạnh của hình vuông - một lần). Đặt cho phần $i$ tổng độ dài của các ranh giới ngang bằng $2x_i$, các đường dọc - $2y_i$ và diện tích của phần $i$ bằng $c_i^2 (c_i > 0)$; rồi $x_i y_i \geqslant c_i^2$ (Hình 2), do đó $x_i + y_i \geqslant 2\sqrt{x_i y_i} \geqslant 2c_i$. Vì thế,

$$40 = \Sigma (2x_i + 2y_i) \geqslant 4\Sigma c_i,$$

từ đâu $\Sigma c_i \leqslant 10$ (ở đây tổng $\Sigma$ được lấy trên tất cả các phần của phân vùng).

Cơm. 1.

Cơm. 2.

Nếu $c_i^2 < 0,01$ (nghĩa là $c_i < 0,1$) với tất cả $i$, thì $1 = \Sigma c_i^2 < \Sigma 0,1c_i = 0,1\Sigma c_i$, do đó $\Sigma c_i > 10$. Sự mâu thuẫn. Rõ ràng, ước tính 18 là chính xác: với đoạn 18/18 có độ dài 1, hình vuông của chúng ta có thể được chia thành 100 hình vuông giống hệt nhau có diện tích 0,01 mỗi hình.

A. Berzin

**M659. Chứng minh các tính chất sau của dãy Fibonacci $f_1 = 1, f_2 = 2, \dots, f_{k+1} = f_k + f_{k-1}$.**

a) Mỗi ​​số tự nhiên $n \geqslant 3$ được biểu diễn dưới dạng tổng của các số Fibonacci khác nhau.

b)* Ta biểu thị số cách biểu diễn như vậy của số $n$ dưới dạng tổng của một số chẵn với $K_n$, dưới dạng tổng của một số lẻ với $H_n$; thì $|K_n - H_n| \leqslant 1$ cho tất cả $n$.

c)* Nếu bạn liên tiếp vượt qua một số kẻ giết hai người dai dẳng trong chuỗi

$$1 - x, 1 - x^2, 1 - x^3,$$

$$1 - x^5, \dots, 1 - x^{f_k}, \dots$$

Để ngắn gọn, chúng ta sẽ cùng nhau nói “biểu diễn của số $n$ dưới dạng tổng của các số Fibonacci khác nhau” là “biểu diễn của số $n$”; chúng ta sẽ gọi các biểu diễn thỏa mãn điều kiện d) chính xác.

Câu lệnh bài toán a) có trong câu lệnh bài toán d).

Lời giải bài toán g). Bên lề là một bảng biểu diễn chính xác các số tự nhiên. Bảng này có cấu trúc như thế này. Các dòng của nó được chia thành các nhóm chứa các giá trị tương ứng của các đẳng thức $1, 2, \dots, f_k$, .... Nhóm đầu tiên bao gồm các đẳng thức $1 = 1$, nhóm thứ hai - từ các đẳng thức $2 = 2$ và $3 = 1 + 2$, và nhóm có số $k \geqslant 3$ thu được từ các nhóm $(k-2)$ và $(k-1)$ bằng cách tăng cạnh trái của các đẳng thức có trong chúng lên $f_k$ và gán chúng cho vế phải của số hạng $f_k$. Bảng cho thấy mọi số tự nhiên $n \geqslant 3$ đều có cách biểu diễn đúng. Để chứng minh tính duy nhất của cách biểu diễn đúng, giả sử rằng $n$ là số nhỏ nhất mà nó là duy nhất; cho phép

$$n = f_{i_1} + \dots + f_{i_m} (i_1 < \dots < i_m)$$

- một khung nhìn không có trong bảng của chúng tôi. Nhưng sau đó

⟦folio 42⟧

(các chỉ số là số Fibonacci), khi đó trong đa thức thu được tất cả các hệ số sẽ bằng 0, -1 hoặc +1. Chứng minh của phát biểu b) và c) mà chúng ta biết dựa trên tính chất sau:
e) Đối với bất kỳ $n \geq 3$ nào, có một biểu diễn duy nhất của $n$ dưới dạng tổng của các số Fibonacci khác nhau, cùng với mỗi số hạng $f_k(k \geq 3)$ chứa ít nhất một trong hai số Fibonacci trước đó $f_{k-1}$ hoặc $f_{k-2}$.

$$1 = 1$$
$$2 = 2$$
$$3 = 1 + 2$$
$$4 = 1 + 3$$
$$5 = 2 + 3$$
$$6 = 1 + 2 + 3$$
$$7 = 2 + 5$$
$$8 = 1 + 2 + 5$$
$$9 = 1 + 3 + 5$$
$$10 = 2 + 3 + 5$$
$$11 = 1 + 2 + 3 + 5$$
$$12 = 1 + 3 + 8$$
$$13 = 2 + 3 + 8$$

$$1 = S(1)$$
$$2 = T(1)$$
$$3 = S(2)$$
$$4 = S(1,1)$$
$$5 = T(2)$$
$$6 = S(3)$$
$$7 = T(1,1)$$
$$8 = S(2,1)$$
$$9 = S(1,2)$$
$$10 = T(3)$$
$$11 = S(4)$$
$$12 = S(1,1,1)$$
$$13 = T(2,1)$$

$$37 = S(2,2,1)$$

$$K_1 - H_1 = M(1) = -1$$
$$K_2 - H_2 = N(1) = -1$$
$$K_3 - H_3 = M(2) = 0$$
$$K_1 - H_4 = M(1,1) = 1$$
$$K_5 - H_5 = N(2) = 0$$
$$K_6 - H_6 = M(3) = 0$$
$$K_7 - H_7 = N(1,1) = 1$$
$$K_8 - H_8 = M(2,1) = -1$$
$$K_9 - H_9 = M(1,2) = 0$$
$$K_{10} - H_{10} = N(3) = 0$$
$$K_{11} - H_{11} = M(4) = 1$$
$$K_{12} - H_{12} = M(1,1,1) = 0$$
$$K_{13} - H_{13} = N(2,1) = -1$$

$$K_{37} - H_{37} = M(2,2,1) = 0$$

trình bày đúng
$$n - f_{i_m} = f_{i_1} + \dots + f_{i_{m-1}}$$
điều tương tự có thể được chứa trong bảng, nếu không, chúng tôi sẽ phải đưa các chế độ xem (1) vào bảng khi xử lý nhóm thứ $i_m$. Sự mâu thuẫn.

Lời giải bài toán 6). Chúng ta sẽ mô tả cách biểu diễn các số tự nhiên dưới dạng chuỗi các vòng tròn đen và trắng: vòng tròn màu đen ở vị trí $k$ có ​​nghĩa là $f_k$ được bao gồm trong biểu diễn, vòng tròn màu trắng có nghĩa là nó không được bao gồm (chúng ta đảo ngược chuỗi trong vòng tròn màu đen cuối cùng). Trong Hình 1, sáu cách biểu diễn khác nhau của số 37 được viết theo cách này (đây là tất cả các cách biểu diễn có thể có của nó). Ý đúng có dạng như hình 2, a hoặc 2, 6; ở đây $j_1, \dots, j_q$ là số tự nhiên. Trong trường hợp đầu tiên, chúng tôi đặt $n = S(j_1, \dots, j_q)$, $K_n - H_n = M(j_1, \dots, j_q)$; trong trường hợp thứ hai, chúng tôi đặt $n = T(j_1, \dots, j_q)$, $K_n - H_n = N(j_1, \dots, j_q)$. (Vì vậy, 37 = S(2, 2, 1), $M(2, 2, 1) = K_{37} - H_{37} = 3 - 3 = 0$; các ví dụ khác được đưa ra gần bên lề.)

Nếu $n = f_{i_1} + \dots + f_{i_m}$ là biểu thị của số $n$, bao gồm $f_r$ và $f_{r+1}$, nhưng không bao gồm $f_{r+2}$ của nó, thì bằng cách thay thế các thuật ngữ $f_r$ và $f_{r+1}$ bằng các thuật ngữ $f_{r+2}$, chúng ta sẽ có được một cách biểu diễn khác của số $n$. Chúng ta sẽ gọi phép biến đổi này (... ● ● ○ ... → ... ○ ○ ● ...) đơn giản hóa cơ bản. Rõ ràng, bất kỳ biểu diễn nào của một số đều có được từ việc đơn giản hóa cơ bản một cách chính xác. Hãy để nó là $q = 1$ trước. Hình 3 hiển thị bộ biểu diễn hoàn chỉnh cho số $n = S(j)$ (bằng $f_{j+2} - 2$). Ta thấy $K_{S(j)}$ là số bốn từ $[(j+1)/2]$ đến $j$, và $H_{S(j)}$ là số x số lẻ trên đoạn này. Kể từ đây,

$$K_n - H_n = M(j) = \begin{cases} 1, \text{ если } j \equiv 0 \text{ mod } 4^* \\ -1, \text{ если } j \equiv 1 \text{ mod } 4, \\ 0, \text{ если } j \equiv 2 \text{ mod } 4. \end{cases}$$

Bây giờ chúng ta chuyển sang số $M(j_1, \dots, j_q)$. Chúng ta hãy chia cách biểu diễn của số $S(j_1, \dots, j_q)$ thành hai nhóm: cách biểu diễn dạng $f_{1+1} + \dots + f_{j+1} + \dots$ và phần còn lại. Số cách biểu diễn của nhóm đầu tiên trùng với số lượng tất cả các cách biểu diễn của số $S(j_2, \dots, j_q)$, chỉ có số sau có $j_1$ số hạng ít hơn, do đó nó bao gồm nhóm đầu tiên trong $M(j_1, \dots, j_q)$ bằng $(-1)^j M(j_2, \dots, j_q)$ (một số ví dụ hoặc những ví dụ xây dựng quan sát của chúng tôi được đưa ra bên lề).

Tiếp theo, để có được cách biểu diễn chính xác của nhóm thứ hai bằng cách sử dụng các yếu tố đơn giản hóa, cần phải đơn giản hóa cơ bản ($f_{j_1-1}, f_{j_1}) \rightarrow f_{j_1+1}$ và người ta có thể tìm thấy từ đó. Do đó, giữa các thuật ngữ $j_1-2$ đầu tiên và phần còn lại có thể có một khoảng cách có độ dài 2 (Hình 4), loại trừ khả năng tương tác. Do đó, trong tương lai, sự đơn giản hóa cơ bản của các thuật ngữ $j_1-2$ đầu tiên và phần còn lại là độc lập, sao cho nhóm thứ hai được bao gồm trong $M(j_1, \dots, j_q)$ bằng $M(j_1-2) M(j_2+1, j_3, \dots, j_q)$.

$$M(j_1, \dots, j_q) = (-1)^j M(j_2, \dots, j_q) + M(j_1-2) M(j_2+1, j_3, \dots, j_q)$$

(xem thêm ví dụ ở lề)**). Bây giờ chúng ta hãy chứng minh từ $q$ rằng $M(j_1, \dots, j_q) = -1, 0$ hoặc 1.

Tại $q = 1$ chúng tôi đã biết điều này. Giả sử rằng $M(k_1, \dots, k_r) = -1, 0$ hoặc 1 cho $r = q$ và bất kỳ $k_1, \dots, k_r$ nào. Nếu $j_1 \equiv 0$ hoặc 1 mod 4 thì $M(j_1-2) = 0$ (xem công thức (2)) và $M(j_1, \dots, j_q) = (-1)^j M(j_2, \dots, j_q) = -1, 0$ hoặc 1.

Nếu $j_1 \equiv 2$ hoặc 3 mod 4 thì $M(j_1-2) = (-1)^j M(j_2, \dots, j_q)$ (xem công thức (2)) cho $q = 2$ và

*) Ký hiệu $a \equiv b$ mod $c$ (đọc: $a$ có ​​thể so sánh với $b$ mod $c$), trong đó $0 \leq b < c$, có nghĩa là khi $a$ chia cho $c$, thu được phần dư $b$.

**) Công thức (3) chỉ có ý nghĩa với $j_1 \geq 3$, nhưng nó cũng có thể được sử dụng cho $j_1 = 1, 2$ bằng cách đặt $M(-1) = 0, M(0) = 1$ (không mâu thuẫn với công thức (2)); việc chứng minh được để lại cho người đọc.

⟦folio 44⟧

M660. Các chấm xanh và đỏ được đặt trên vòng tròn (Hình 1, a). Được phép thêm một chấm đỏ mới và đồng thời thay đổi màu của từng chấm trong hai chấm liền kề (Hình 1, b) hoặc loại bỏ chấm đỏ và thay đổi màu của từng chấm lân cận (Hình 1, c). Giả sử ban đầu chỉ có hai chấm đỏ (không có vết cắt nào giữa hai chấm). Có thể đạt được trên một vòng tròn bằng một số thao tác như vậy không
a) hai chấm - xanh và đỏ;
b) 8 chấm đỏ;
c) một chấm đỏ và 6 chấm xanh;
e) hai chấm xanh?

Cơm. 1.
Cơm. 2.
Cơm. 3.
Cơm. 4.

F668. Thông qua một khối peroxid hóa cố định có một sợi dây không trọng lượng. Một khối lượng $m_1$ được gắn vào một đầu của sợi chỉ. Đến đầu bên kia của một con suối

$M(n) = G(n, k)$ cho $f_{k+1} > n$ và cho lời giải bài toán c) - rằng hệ số cho $x^n$ trong tích $(1-x^{j+1})\ldots(1-x^{i+k})$ bằng 0 nếu $n$ không được biểu diễn dưới dạng tổng của các số hạng khác nhau được chọn từ tập hợp $f_{i+1},\ldots,f_{i+k}$ và bằng $G(f_{j_1}+f_{j_2}+...+f_{j_s}, k)$ nếu $n=f_{i+j_1}+\ldots+f_{i+j_s}, 1 \leq j_1 <...<j_s \leq k$.

Đáp số cho câu hỏi 6) và c) là tích cực.

Đối với 6), điều này xuất phát từ thực tế là, bằng phép cộng, ba chấm đỏ liên tiếp luôn có thể được đặt ở bất kỳ vị trí nào trên vòng tròn (Hình 2). Sau đó, tám chấm đỏ sẽ thu được từ hai chấm đỏ bằng cách chèn ba chấm đỏ hai lần.

Mặt khác, từ ba chấm đỏ liên tiếp, bạn luôn có thể nhận được hai chấm xanh (bằng cách bỏ chấm ở giữa). Do đó, trước tiên bằng cách thêm một chấm đỏ vào hai chấm đỏ đã cho, sau đó thêm hai lần ba chấm đỏ, rồi thay thế “bộ ba màu đỏ” này bằng “cặp xanh lam”, chúng ta sẽ có được một chấm đỏ và sáu chấm xanh lam.

Phủ định đáp số cho câu hỏi a) xuất phát từ thực tế là với các phép toán được phép, tính chẵn lẻ của số chấm màu xanh lam không thay đổi, và ở vị trí ban đầu và vị trí cuối cùng bắt buộc thì khác nhau.

Phủ định đáp số đối với câu hỏi d) xuất phát từ một đặc tính bất biến khác trong các hoạt động của chúng ta, việc phát hiện ra đặc tính này đòi hỏi sự quan sát nhiều hơn và một số lượng lớn các thí nghiệm. Hơn nữa, tính chất này chỉ bất biến đối với tập hợp các vị trí có số chấm màu xanh chẵn.

Đối với những sắp xếp như vậy, chúng tôi xác định một tổng thay thế $|m_1-m_2+m_3-m_4+\ldots+m_{2k-1}-m_{2k}|$ theo chiều dài của các chấm đỏ: $m_1$ - số chấm đỏ nằm giữa chấm xanh thứ nhất và chấm xanh thứ hai (hướng di chuyển ngang và chấm xanh đầu tiên được chọn tùy ý), $m_2$ - số chấm đỏ giữa chấm xanh thứ hai và thứ ba, $m_3$ - giữa chấm thứ ba và thứ tư,..., $m_{2k}$ - giữa chấm thứ 2$k$ cuối cùng và chấm xanh đầu tiên (trong Hình 3 $k=2$, $m_1=2$, $m_2=3$, $m_3=1$, $m_4=5$); một số $m_i$ có thể bằng 0. Nếu không có chấm màu xanh nào trong cách sắp xếp, hãy đặt tổng này bằng số chấm màu đỏ của nó.

Hóa ra khả năng chia hết cho 3 của tổng được xác định theo cách này là một tính chất bất biến. (Thử nghiệm với sự sắp xếp như trong Hình 3, sau đó chứng minh phát biểu đã nêu về thao tác cắt một chấm đỏ bằng cách xét trường hợp các “láng giềng” của nó là các chấm xanh, chấm đỏ, chấm khác màu.) Nhưng đối với hai chấm đỏ, tổng của chúng ta bằng 2 (không chia hết cho 3) và đối với hai chấm xanh thì nó bằng 0 (chia hết cho 3). Điều này có nghĩa là sự sắp xếp thứ hai không thể có được từ sự sắp xếp thứ nhất.

Để kết luận, chúng ta lưu ý rằng bất kỳ sự sắp xếp (hữu hạn) nào của các điểm đỏ và xanh đều có thể thu được từ một số hai điểm một hoặc, tương tự như vậy, từ bất kỳ cách sắp xếp nào người ta cũng có thể thu được một hai điểm. Nhận xét này gần như hiển nhiên: chỉ cần loại bỏ các chấm đỏ cho đến khi còn lại hai chấm trên vòng tròn là đủ. Nếu trên vòng tròn ở một bước nào đó chỉ còn lại các chấm màu xanh lam (nhiều hơn hai), thì bằng cách thêm một chấm đỏ và sau đó loại bỏ chấm liền kề với nó, chúng ta sẽ có được sự sắp xếp có tổng số chấm như nhau, chứa các chấm đỏ (Hình 4).

K. Kazarnovsky

Nếu các vật nặng được nối với nhau bằng một sợi dây không có lò xo thì chúng sẽ bắt đầu chuyển động với gia tốc có giá trị tuyệt đối bằng

$$a = g \frac{m_2-m_1}{m_2+m_1}$$

⟦folio 45⟧

một tải trọng có khối lượng $m_2$ được treo với độ cứng k. Chiều dài của lò xo ở trạng thái không giãn nở là $l_0$. Tìm biên độ dao động mà tải $m_2$ sẽ thực hiện khi hệ được để yên. Không có sự xoay ngang qua sợi chỉ.

(chúng tôi giả sử $m_2 > m_1$). Trong trường hợp này lực căng của sợi dây sẽ bằng

$$T = \frac{2m_1m_2}{m_1 + m_2} g.$$

Chúng ta sẽ giả sử rằng tại thời điểm ban đầu hệ được giữ ở trạng thái cân bằng nhờ sự trợ giúp của một lực bổ sung tác dụng lên tải $m_1$. Khi đó lực căng của lò xo ở thời điểm ban đầu

$$T_0 = m_2g \neq T,$$

do đó, ngoài chuyển động có gia tốc còn xảy ra dao động của các tải trọng tương đối với nhau. Biên độ của lực căng trong quá trình dao động này bằng

$$T_0 - T = \frac{m_2 - m_1}{m_2 + m_1} m_2g,$$

độ dãn cực đại của lò xo là

$$\Delta l = \frac{T_0 - T}{k}.$$

Sự trộn lẫn các tải trọng trong quá trình dao động tỷ lệ nghịch với khối lượng của chúng. Nếu $l_1$ và $l_2$ lần lượt là sự pha trộn tối đa của tải $m_1$ và $m_2$ thì

$$l_1m_1 = l_2m_2$$

$$l_1 + l_2 = l = \frac{T_0 - T}{k} = \frac{m_2 - m_1}{m_2 + m_1} m_2g.$$

Từ đây ta tìm được biên độ dao động của tải $m_2$:

$$l_2 = l \frac{m_1}{m_1 + m_2} = \frac{m_2 - m_1}{k(m_1 + m_2)^2} m_1m_2g.$$

Chúng ta xét chuyển động của tải trọng với điều kiện tại thời điểm ban đầu tải trọng $m_2$ làm căng lò xo. Hãy tự giải bài toán, giả sử lò xo không bị giãn ở thời điểm ban đầu.

G. Kotkin

F669. Lật một tấm kính có thành mỏng có đáy bằng nút chai có độ dày d nổi ở bề mặt tiếp xúc giữa hai chất lỏng có mật độ $\rho_1$ và $\rho_2$. Mặt trên của kính nằm ở vị trí H phía trên giao diện. Tiết diện của tấm kính là S. Tấm kính dâng lên bao xa nếu dưới đáy tấm kính xuất hiện một lỗ?

Sau khi xuất hiện một lỗ ở đáy, mức độ tách chất lỏng bên trong và bên ngoài kính sẽ được cân bằng. Trong trường hợp này, tấm kính sẽ bắt đầu chuyển động hướng lên trên vì lực nổi tăng lên (áp suất lên đáy nút chai tăng lên, vì $\rho_2 > \rho_1$). Hiệu ứng phản tác dụng duy nhất phát sinh do thực tế là trong trường hợp này lực tác động lên một đầu tấm kính giảm (kính có thành mỏng; điều này có nghĩa là diện tích phần cuối $\Delta S \ll S$). Rõ ràng là trong trường hợp lực nổi tăng lên không đáng kể (và nếu cần thiết, đây sẽ là giá trị của $H - d$), tấm kính sau khi đã nổi đến một khoảng cách nhất định mà chúng ta ký hiệu là x, lại thấy mình ở trạng thái cân bằng. Chúng ta hãy viết độ tăng cân bằng trong trường hợp thứ nhất và thứ hai ($p_0$ - áp suất tại bề mặt chất lỏng, $L$ - tổng chiều cao của kính):

$$mg + (p_0 - \rho_1gH)S = [p_0 + \rho_2g(L - H)]\S + [p_0 - \rho_2g(H - d)](S - \Delta S),$$

$$mg + [p_0 - \rho_1g(H + x)]S = [p_0 + \rho_2g(L - H - x)]\Delta S + [p_0 - \rho_1g(H + x - d)](S - \Delta S).$$

Mở ngoặc và đưa các thuật ngữ tương tự, ta được

$$m = \rho_1HS - \rho_2HS + \rho_1dS + \rho_2L\Delta S - \rho_2d\Delta S,$$

$$m = \rho_1dS + \rho_2L\Delta S - \rho_2H\Delta S - \rho_2x\Delta S + \rho_1H\Delta S + \rho_1x\Delta S - \rho_1d\Delta S.$$

Đánh đồng các vế phải, sau các phép biến đổi đơn giản, ta thu được:

$$x = (H - d) \frac{S - \Delta S}{\Delta S}.$$

Kính sẽ ngừng chuyển động đi lên nếu điều kiện x < L - H bị nén chặt, hoặc

⟦folio 46⟧

$$H - d < \frac{\Delta S}{S} (L - d).$$

Nếu điều kiện này không được đáp ứng, kính sẽ nổi lên bề mặt.

A. Zilberman

F670. Chứng tỏ rằng tốc độ cực đại mà hạt α có thể truyền cho proton khi va chạm bằng 1,6 lần tốc độ ban đầu của hạt α.

Trước tiên chúng ta giả sử rằng proton kết thúc so với hệ quy chiếu đứng yên và hạt α có tốc độ $\vec{v}_0$. Quá trình điều khiển chúng được mô tả bằng định luật bảo toàn động lượng

$$4m\vec{v}_0 = m\vec{v}_1 + 4m\vec{v}_2$$

và định luật bảo toàn năng lượng

$$\frac{4mv_0^2}{2} = \frac{mv_1^2}{2} + \frac{4mv_2^2}{2},$$

trong đó $\vec{v}_1$ và $\vec{v}_2$ là vectơ vận tốc của proton và hạt α tương ứng trong hệ quy chiếu đứng yên sau va chạm, $m$ và $4m$ là khối lượng của proton và hạt α.

Chúng ta hãy xem xét quá trình va chạm của các hạt này trong hệ quy chiếu tâm, nghĩa là trong một hệ quy chiếu quán tính chuyển động tương đối so với một hệ quy chiếu đứng yên với tốc độ $\vec{v}' = \frac{4m\vec{v}_0}{m+4m} = \frac{4}{5}\vec{v}_0$ (tử số của hạt thứ nhất là toàn bộ xung lực của hệ, mẫu số là tổng khối lượng của nó). Hình vẽ biểu diễn vectơ $\vec{v}_0$ và vectơ vận tốc của hạt α (vectơ $\vec{OB}$) và proton (vectơ $\vec{OA}$) ở tâm hệ khối lượng trước khi va chạm; $|\vec{OB}| = \frac{1}{5}|\vec{v}_0|, |\vec{OA}| = \frac{4}{5}|\vec{v}_0|$.

Theo định luật va chạm ngầm định, sau va chạm các vectơ $\vec{OB}'$ và $\vec{OA}'$ của vận tốc của hạt α và proton phải nằm trên cùng một đường thẳng và phải thỏa mãn sự tương ứng $|\vec{OB}'|:|\vec{OA}'| = 1:4$ (xem hình); theo định luật va chạm của năng lượng, $|\vec{OB}'| = |OB|$ và $|\vec{OA}'| = |\vec{OA}|$ (chỉ cho tôi xem!).

Vận tốc của hạt α và proton trong hệ quy chiếu đứng yên được mô tả trong hình bằng các vectơ lần lượt là $\vec{OC}_2 = \vec{OB}' + \vec{v}$, $\vec{OC}_1 = \vec{OA}' + \vec{v}$ ($\vec{v} = \frac{4}{5}\vec{v}_0$).

Để trả lời câu hỏi bài toán, chúng ta phải xác định độ dài lớn nhất có thể có của vectơ $\vec{OC}_1$, tức là trong tam giác cân bằng $OA'C_1$ cần xác định độ dài lớn nhất có thể có của đáy với độ dài các cạnh không đổi. Rõ ràng, mức tối đa của $|\vec{OC}_1|$ bằng $2 \cdot \frac{4}{5}|\vec{v}_0| = 1,6|\vec{v}_0|$. Tình trạng này phản ứng với udur trung tâm.

S. Krotov

F671. Có 1 lít nước nóng có nhiệt độ $T_1$ và 1 lít nước lạnh có nhiệt độ $T_2$. Dùng nước nóng để sưởi ấm khi trời lạnh. Có thể làm cho nhiệt độ cuối cùng của nước lúc đầu lạnh trở nên cao hơn nhiệt độ của nước lúc đầu nóng không?

Đáp số: bạn có thể.

Chúng tôi sẽ chỉ cho bạn cách làm điều đó. Chúng ta hãy tùy ý sử dụng một bình $A$ chứa nước nóng (nhiệt độ nước nóng $T_r$), một bình $B$ với nước lạnh (nhiệt độ $T_x$), một bình $C$, các thành của nó dẫn nhiệt và một bình $D$, dẫn nhiệt.

Chúng tôi làm nóng nước lạnh theo hai giai đoạn:

1) Đổ một ít nước lạnh từ $B$ vào $C$; hạ $C$ từ nước lạnh xuống $A$. Sau một thời gian, nhiệt độ nước ở $A$ và $C$ sẽ bằng nhau: $T_A = T_C = T_1$, và

$$T_r > T_1 > T_x.$$

Chúng ta đổ nước “lạnh” từ $C$ vào bình dẫn nhiệt $D$.

2) Đổ phần nước lạnh còn lại vào $C$; chúng tôi hạ $C$ xuống $A$ (trong $A$ nước “nóng” có nhiệt độ $T_1$). Bởi vì

⟦folio 48⟧

$$\approx 10^{-3}g.$$
Mặt trăng cũng cho kết quả tương tự (hãy nhớ thủy triều).

Lực cản không khí: lực kéo $F = asv^2$. Giá trị $\alpha$ có thể được ước tính gần đúng bằng cách biết tốc độ mưa đá $v_r \approx 20$ m/s tại $r_r \approx 0,5$ cm:

$$\alpha \pi r_r^2 v_r^2 = m_r g = \frac{4}{3} \pi r^3 g \Rightarrow \alpha = \frac{4 \rho_r r_r}{3 v_r^2}.$$

Đối với lõi, tốc độ $v_r$, tại đó lực cản của không khí bằng lực hấp dẫn, được xác định bởi các điều kiện

$$v_r = v_r \sqrt{\frac{\rho_r r_r}{Q_r r_r}} \approx 200 \text{ m/c}.$$

Điều này có nghĩa là với một tốc độ nhất định $F_{\text{conp}} = mg \left(\frac{12}{200}\right)^2 \approx 3 \cdot 10^{-3}mg$. (Lưu ý rằng ở những tốc độ như vậy lực ma sát cao lớn hơn lực ma sát trực diện, nhưng nó cũng không đúng.)

Sức mạnh của Archimedes

$$F_A = \frac{\rho_B}{Q_A} mg \leq 10^{-3}mg.$$

Hiệu chỉnh biến dạng rơi tự do do Trái Đất quay

$$\Delta g_2 = \omega_2^2 R_2,$$

trong đó $\omega_2 = 2\pi/1$ ngày, $R_2 = 6,3 \cdot 10^6$ cos $\varphi$ (f là vĩ độ của khu vực). Tại xích đạo $\Delta g_2 \leq 3 \times 10^{-3}g$.

Các số trong bài toán được đặt thành “làm tròn”; Từ những báo cáo thực tế đơn giản, rõ ràng chúng tôi yêu cầu độ chính xác không quá 3-5%. Điều này có nghĩa là tất cả những sửa đổi trên đều không đáng kể và mô hình của chúng tôi là hoàn toàn hợp lý. Lời giải Nhiệm vụ rất đơn giản, chúng tôi không trình bày.

Tuy nhiên, có những tình huống có thể xảy ra khi ngay cả những điều chỉnh nhỏ cũng có thể có tác động quyết định đến kết quả. Điều này có thể xảy ra, chẳng hạn, nếu chúng ta quan tâm đến những chuyển động khác nhau của một số vật. Hãy tự mình xem xét câu hỏi này: liệu một viên đạn bắn thẳng đứng có bắn trúng nòng súng không?

Một mô hình có thể hoàn toàn không thể áp dụng được nếu nó không phản ánh được những đặc điểm cơ bản của hiện tượng. Ví dụ, mô hình của một vật rắn tuyệt đối không thể áp dụng để mô tả một va chạm tuyệt đối - các biến dạng đóng vai trò quan trọng trong quá trình va chạm và một vật rắn tuyệt đối không bị biến dạng. Một ví dụ khác: độ tự cảm của dây dẫn (hoặc, tương tự, năng lượng của từ trường phát sinh xung quanh dây dẫn khi có dòng điện chạy qua nó) thường bị bỏ qua; tuy nhiên, trong bài toán nổi tiếng về một tụ điện, sau khi sạc được nối ngắn mạch với một dây dẫn, không thể xem xét đồng thời điện trở của dây dẫn và độ tự cảm của nó - nếu điện trở rất nhỏ thì dòng điện sẽ rất lớn, và ngay cả khi có độ tự cảm thấp, năng lượng của từ trường vẫn rất đáng kể. Một phân tích đơn giản cho thấy rằng tác dụng của điện cảm trong các trường hợp khác nhau khác biệt đáng kể so với điện cảm chỉ trong các trường hợp khác nhau, và cát lấp đầy chất lỏng có trong cơ thể (điều tương tự sẽ xảy ra khi muốn lấp đầy hình ảnh các đường thoát nước của từ trường, chúng ta đổ mạt sắt lên một tờ giấy và lắc nó để làm suy yếu lực căng).
