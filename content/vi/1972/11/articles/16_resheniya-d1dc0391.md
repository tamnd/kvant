---
id: 1972-11-resheniya-d1dc0391
issue: kvant_1972_11
year: 1972
number: "11"
title: Lời giải bài toán M129—M134; F148—F152
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 44
page_last: 53
page_labels: 42, 44, 45, 46, 47, 48, 49, 50, 51
tag: CYZB
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 68d7ffd7941aa4cc5ba8b145efed01984b1f0e14e67f4a03d5bfcc3796776cf0
prompt_sha256: draft-1
translated_from: content/ru/1972/11/articles/16_resheniya-d1dc0391.md
source_content_sha256: 3389207ca42649e5fe7f111442f7cf9ca097a4811f286555afb2642fd32c880a
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 42⟧

Lời giải

Trong số này chúng tôi xuất bản lời giải bài toán M129—M134

M129
a) Người ta đổ 12 lít sữa vào thùng. Làm thế nào, chỉ sử dụng bình 5 và 7 lít, bạn có thể chia sữa thành hai phần bằng nhau?
b)* Giải tổng quát bài toán: để tính a và b, ta có thể chia (a+b) lít sữa làm đôi, chỉ dùng bình 1 lít, b lít và (a+b) lít?

XE TĂNG
Tôi tàu 7 2 2 0 7 4 4 0 7 6
II tàu 0 5 0 2 2 5 0 4 4 5

XE TĂNG
Bảng 1.

Để giải bài toán 6), ta tiến hành như sau. Đặt a ≥b. Hãy lấy một chiếc bình có dung tích a+b lít làm bình chứa, một chiếc bình có dung tích 1 lít làm bình thứ nhất và một bình có dung tích b lít làm bình thứ hai. Chúng ta hãy chứng minh rằng có thể thu được c lít khi và chỉ nếu c=ma+lb, trong đó m và l là số nguyên, 0<c<a. Nếu a và b là số nguyên thì nó có thể được hình thành như sau: có thể thu được c lít khi và chỉ khi 0≤c≤a và c chia hết cho ước số chung lớn nhất của a và b (xem bài viết của V. N. Vagten “Thuật toán Euclide và Định lý cơ bản của số học”, «Kvant» Số 6, 1972). Chúng ta giải bài toán mà không giả sử rằng a và b là số nguyên; nếu điều này được biết trước thì lời giải có thể được đơn giản hóa; ví dụ, không cần xem xét riêng trường hợp m>0 và m<0.

Bảng 2.

I a-a-b a-b a-2b a-2b d₁=a-l₁b 0 a 2a-(l₁+1)b 2a-(l₁+1)b d₂=2a-l₂b dₘ=ma-lₘb
II 0 b 0 b 0 0 d₁ d₁ b 0 0

Bảng 3.

Đối với lời giải bài toán a) chỉ cần cung cấp một bảng là đủ (xem Bảng 1). Vì điều đó

Chúng ta hãy biểu thị bằng dₖ phần dư của phép chia ka cho b (k=1, 2, 3, ...): dₖ=ka-lₖb, 0≤dₖ<b.

Chúng ta chỉ cần chứng minh rằng có thể thu được dₘ lít là đủ. Thật vậy, vì dₘ=ma-lₘb là số nhỏ nhất có dạng ma+lb, trong đó l là một số nguyên, nên bằng cách thêm một phần l+lₘ khác của b lít vào dₘ, chúng ta có thể nhận được số tiền cần thiết

⟦folio 44⟧

Hình 3.

phải nằm trên biên của tập hợp $V$; không ai trong số chúng có thể ở bên trong $V$: xét cho cùng, $V$ được chứa trong mỗi sọc $\Pi_{ij}$.

Lời giải bài toán a) bây giờ hóa ra là hai từ. Trong trường hợp này, $V$ là một $n$-giác lồi có các đỉnh $A_1, A_2, \dots, A_n$. Tổng các góc của nó bằng $180^\circ (n - 2)$ và nếu mỗi góc không lớn hơn $90^\circ$ thì

$$180^\circ (n - 2) \leq 90^\circ n,$$

từ đâu $n \leq 4$.

Lời giải bài toán trên máy bay được rất nhiều bạn đọc gửi về. Không gian bài toán khó hơn nhiều và chúng tôi chưa nhận được bằng chứng đầy đủ từ bất kỳ độc giả nào. Hãy để chúng tôi trình bày lời giải, được phát hiện lần đầu tiên bởi các nhà hình học nổi tiếng L. Danzer và B. Grionbachum (1962).

Chúng ta xét, ngoài khối đa diện $V$ (ở đây $V$ có thể hiểu là bao lồi của các điểm $n$ đã cho $A_1, A_2, \dots, A_n$ hoặc giao điểm - phần chung - của tất cả các sọc $n (n - 1)/2$ $\Pi_{ij}$, còn có các khối đa diện:

$$V_i, \text{ получищеся из } V \text{ сдигом на вектор } \overrightarrow{A_1 A_i} (i = 1, 2, \dots, n); V_1, \text{ размещется, совпадает с } V), \text{ и } V', \text{ получищеся из } V \text{ расстоянием (гомотетей) с коэффициентом 2 и центром в точке } A_1.$$

Hãy chứng minh ba khẳng định sau.

1. Khối đa diện thu được từ $V$ bởi vectơ $\overrightarrow{A_i A_j}$ không có điểm chung bên trong nào với $V$ (nghĩa là nó chỉ có thể giao nhau với $V$ trên biên).

2. Không có hai khối đa diện $V_1, V_2, \dots, V_n$ nào có điểm chung bên trong.

3. Tất cả $V_i$ đều được chứa trong $V'$.

Hãy chứng minh 1°. Khi chuyển sang $\overrightarrow{A_i A_j}$, sọc $\Pi_{ij}$ biến thành một sọc mới, không có điểm chung bên trong nào với nó - hai sọc này chỉ có một mặt phẳng ranh giới chung. Nhưng $V$ được chứa trong $\Pi_{ij}$, nên 1° càng đúng hơn.

Thay đổi 2° diễn ra sau 1°: chỉ cần thay thế $V_j$ thu được từ $V_i$ bằng cách dịch chuyển sang vectơ $\overrightarrow{A_i A_j}$ (Hình 4).

Hình 4.

$$3^\circ \text{ следует из более общого факта: если } ABC \text{ — три точки выпуклого многогранника, } W \text{ и } W' \text{ — многогранник, полученный из } W \text{ растяжением в 2 раза с центром в точке } A, \text{ то четыряя вершина } D \text{ параллелограмма } ABDC \text{ (то есть точка, получшаяся из } C \text{ сдигром на вектор } \overrightarrow{AB}) \text{ принадлежит } W'.$$

Điều này dễ dàng được chứng minh: điểm $K$, từ đó khi kéo giãn sẽ thu được $D$ - trung điểm của đoạn $AD$ - đồng thời là trung điểm của đoạn $BC$, do đó nó thuộc về $W$ (xét cho cùng, đa diện $W$ là lồi), do đó $D$ thuộc về $W'$ (Hình 5).

Vì vậy, khẳng định 2° và 3° đã được chứng minh. Gọi $v$ là thể tích của khối đa diện $V$. Khi đó âm lượng của mỗi điểm $V_i$ là $v$ và âm lượng của $V'$ là $8 v$. Từ 2° và 3° rõ ràng là theo sau $nv \leq 8 v$, từ đó $n \leq 8$.

Lưu ý rằng chúng tôi đã quyết định bài toán, được đề xuất tại Olympic Quốc tế lần thứ XIII (xem “Quant” số 12 năm 1971, trang 54, bài toán 2): rõ ràng là bài toán M130 6), ban giám khảo quốc tế đã quyết định rằng nó quá khó đối với Olympic và chỉ bao gồm nửa sau của nó.

Liên quan đến tuyên bố đã được chứng minh, sẽ nảy sinh một số câu hỏi không thể giải quyết theo cách đẹp đẽ mà khá giả tạo mà chúng ta đã nói đến. Ví dụ, điểm thuần khiết nhất trong không gian có thể được

⟦folio 45⟧

nên đặt sao cho tất cả các góc của tam giác có đỉnh tại các điểm này đều nhọn?
Từ lời giải của chúng tôi, rõ ràng là không thể đặt 8 điểm (hãy đảm bảo điều này). Không khó để xây dựng một ví dụ khi có 5 điểm. Có thể có 6 người trong số họ? 7? Một câu hỏi tổng quát hơn và có lẽ rất khó là: số điểm tối đa có thể sắp xếp sao cho tất cả các góc không vượt quá một giá trị α cho trước là bao nhiêu?

Nếu bất kỳ độc giả nào trả lời được lời giải trong số những câu hỏi này, chúng tôi sẽ quay lại với họ một lần nữa.

M131
Chứng minh rằng các điểm chẵn mà tại đó các đường phân giác của các góc kéo dài các cạnh đối diện của một tứ giác nội tiếp cắt các cạnh của nó là các đỉnh của hình thoi.

Chúng ta sẽ giải bài toán bằng cách sử dụng các định lý nổi tiếng về góc giữa hai cát tuyến (Hình 6). Ký hiệu rõ ràng trong Hình 7. Vì $PN$ và $QK$ là các phân giác nên

$$\alpha_6 - \alpha_1 = \alpha_5 - \alpha_2,$$
$$\alpha_7 - \alpha_4 = \alpha_8 - \alpha_3.$$

Cộng hai đẳng thức này, ta được $\alpha_6 + \alpha_7 + \alpha_2 + \alpha_3 = \alpha_1 + \alpha_4 + \alpha_5 + \alpha_8$, do đó tổng các cung trong mỗi phần của đẳng thức cuối cùng bằng nửa hình tròn. Do đó, các đường thẳng $PN$ và $QK$ vuông góc với nhau. Suy ra rằng trong một tam giác $KPM$ phân giác của góc $P$ đồng thời với chiều cao; thì nó cũng là số trung vị; tam giác $KPM$ đều. Điều tương tự cũng có thể nói về tam giác $LQN$. Do đó, trong một tứ giác $KLMN$ các đường chéo chia đôi nhau và vuông góc với nhau nên nó là hình thoi.

N. B. Vasiliev

M132
Cho $n$ các số $x_1, x_2, \dots, x_n$ được viết xung quanh một vòng tròn, mỗi số bằng (+1) hoặc (-1) và tổng của $n$ tích theo cặp của các số lân cận bằng 0 (như trong bài toán M93, trang 42) và nói chung với mỗi $n = 1, 2, \dots, n - 1$ tổng $n$ của tích từng cặp của các số cách nhau bởi $k$ vị trí bằng 0 (tức là $x_1x_3 + x_2x_4 + \dots = 0$, $x_1x_4 + x_2x_5 + \dots = 0$, v.v.). Ví dụ về $n = 4$ dan trong Hình 8).

a) Chứng minh rằng $n$ là bình phương của một số nguyên.
b) Có bộ số $n$ như vậy cho $n = 16$ không?

Hình 8.

⟦folio 46⟧

Hãy chứng minh rằng $n$ là bình phương của một số nguyên. Hãy đặt $m = x_1 + x_2 + \dots + x_n$. Khi đó $m$ là một số nguyên,

$$m^2 = (x_1 + x_2 + \dots + x_n)^2 = (x_1^2 + x_2^2 + \dots + x_n^2) + (x_1x_2 + x_2x_3 + \dots + x_nx_1) + (x_1x_3 + x_2x_4 + \dots + x_{n-1} \times x_1 + x_nx_2) + \dots + x_nx_{n-1}).$$

Như sau từ điều kiện bài toán, ở vế phải của đẳng thức này, tổng các số trong dấu ngoặc đầu tiên là $n$ và tổng các số trong bất kỳ dấu ngoặc nào khác là 0. Do đó, $n = m^2$. Vấn đề a) đã được giải quyết.

Hãy để chúng tôi xác định xem $n$ nào chúng tôi có thể chọn các số $x_1, \dots, x_n$ thỏa mãn các điều kiện bài toán. Như sau từ bài toán M93, $n$ phải chia hết cho 4; Điều này có nghĩa là $n$ là bình phương của một số chẵn. Nếu $n=4$ thì có thể chọn các số sau: $x_1=x_2=x_3=1$, $x_4=-1$. Giá trị tiếp theo có thể có của $n$ là 16.

Hãy chứng minh rằng với $n=16$ những số như vậy $x_1, \dots, x_{16}$ không thể chọn được.

Giả sử rằng các số $x_1, \dots, x_{16}$ được cho thỏa mãn các điều kiện bài toán và cố gắng đi đến một điều mâu thuẫn.

Hãy để $m = x_1 + \dots + x_{16}$. Chúng ta có thể giả sử rằng $m \geq 0$ (nếu không, chúng ta có thể thay thế tất cả các số $x_i$ bằng $-x_i$ mà không vi phạm các điều kiện của bài toán), như đã được hiển thị, $m^2 = n = 16$, tức là $m=4$.

Nếu $p$ trong số $x_i$ bằng $1$ và $q$ bằng $-1$, thì

$$p + q = n = 16 \text{ и } p - q = m = 4.$$
Vì vậy, $p=10$, $q=6$.

Chúng ta sẽ giả sử rằng các số $x_i$ được viết ở các đỉnh của một hình 16 cạnh thông thường. Hãy đánh dấu bằng dấu hoa thị những đỉnh có số $-1$ (tổng cộng 6 sao). Chúng ta hãy xoay toàn bộ bức tranh theo $\frac{k}{16}$ phần của một vòng quay đầy đủ ($k=1, 2, \dots, 15$).

Hãy để chúng tôi chứng minh rằng trong trường hợp này có chính xác 2 ngôi sao sẽ đi đến các đỉnh mà các ngôi sao bằng nhau. Thật vậy, hãy để $r$ các số bằng $-1$ di chuyển đến vị trí có $-1$. Khi đó tổng của $x_1x_{k+1} + x_2x_{k+2} + \dots + x_{16-k+1}x_1$ sẽ là $(6-r)$ số hạng trong đó thừa số thứ nhất là $-1$ và số hạng thứ hai $+1$, và $(6-r)$ số hạng trong đó thừa số thứ hai là $-1$ và thừa số thứ nhất $+1$; điều đó có nghĩa là có $2(6-r)$ số hạng bằng $-1$.

Vì tổng bằng 0 nên $2(6-r) = 8$, tức là $r=2$.

Bây giờ chúng ta có thể định dạng lại bài toán như sau: có thể sắp xếp 6 ngôi sao ở các đỉnh của một 16 giác thông thường sao cho hai ngôi sao đứng ở các đỉnh đối diện nhau và với bất kỳ số $k$ nào từ 1 đến 7 sẽ bằng $k$ (dưới khoảng cách giữa hai điểm của một đa kế, độ dài nhỏ hơn các cung nối chúng và độ dài của toàn bộ vòng tròn được lấy là 16 khoảng cách giữa chúng ta sẽ biểu thị $(XY)$ bằng các điểm $X$ và $Y$.

Chúng ta hãy biểu thị bằng $A$ và $B$ các điểm đối xứng đường kính được bù bằng dấu hoa thị và bằng $C, D, E, F$ các điểm bù khác. Hãy tính tổng tất cả khoảng cách giữa các điểm $A, B, C, D, E, F$. Khoảng cách 8 xảy ra một lần và khoảng cách từ 1 đến 7 xảy ra hai lần—tổng cộng là $2(1+2+3+4+5+6+7)+8=64$.

Hãy xem khoảng cách được nhận ra giữa các điểm $C, D, E, F$. Vì $(AX) + (BX) = 8$ dành cho bất kỳ điểm $X$ nào, nên tổng $\Sigma$ của tất cả khoảng cách giữa các điểm $C, D, E, F$ sẽ bằng $64 - (AB) - 4 \cdot 8 = 24$. Ngoài ra, nếu khoảng cách $k$ được nhận ra giữa các điểm $C, D, E, F$, điều này có nghĩa là trong số các số $(AC), (AD), (AE), (AF) и (BC), (BD), (BE), (BF)$ xảy ra ít hơn hai lần; nhưng sau đó $(8-k)$ xảy ra ít hơn hai lần, tức là $(8-k)$ cũng được hiểu là khoảng cách giữa các điểm $C, D, E, F$. Hãy xem các điểm $C, D, E, F$ có ​​thể được định vị như thế nào. Dễ dàng kiểm tra được hai trường hợp có thể xảy ra.

1) Một số ba điểm (ví dụ: $C, D, E$) tạo thành một tam giác chứa tâm đường tròn. Đặt $F$ nằm giữa $C$ và $D$. Sau đó

$$(CD) + (DE) + (CE) = 16,$$
$$(CF) + (DF) = (CD),$$

và ngoài ra, $(EF)$ lớn hơn $(CE)$ hoặc $(DE)$. Vì $(CD) + (DE) > 8$ và $(CD) + (CE) > 8$, nên $\Sigma = (CD) + (DE) + (CE) + (CF) + (DF) + (EF) = 16 + (CD) + (EF) > 24$, mặc dù, như chúng tôi đã trình bày trước đó, tổng này phải bằng 24. Điều này có nghĩa là trường hợp đầu tiên là mới.

2) Điểm $C, D, E, F$ nằm về một phía của một đường kính nhất định. Hãy sắp xếp chúng xung quanh vòng tròn theo thứ tự sau $C, D, E, F$. Sau đó $(CD) + (DF) = (CF) + (CE) + (DF) + (EF) = 16$ (tổng của $3(CF) + (DE)$). Vì vậy, $3(CF) + (DE) = 24$. Vì $CF > DE$, nên $(CF) = 7$, $(DE) = 3$. Nếu $(CD) = 1$ thì $(DF) = 6$; nhưng đồng thời, khoảng cách $2 = 8 - 6$ không được nhận ra giữa các điểm $C, D, E, F$, điều này mâu thuẫn với những gì đã được chứng minh trước đó. Nếu $(CD) = 2$ thì mặc dù $(CF) = 7$, khoảng cách 1 không được thực hiện. Nếu $(CD) = 3$ thì $(EF) = 1$, và trường hợp này cũng không khác gì trường hợp $(CD) = 1$.

Vì vậy, chúng ta đã thu được rằng khoảng cách của dấu hoa thị theo cách yêu cầu (và do đó, rõ ràng, các số thỏa mãn điều kiện bài toán chỉ có thể được chọn cho $n=4$.

D. N. Bernishtein

M133

Một trong những sinh vật đa bào đơn giản nhất - tảo "sói" - là

⟦folio 47⟧

Hình 9.

là một lớp vỏ hình cầu được gấp lại thành một hình bảy cạnh chính, hình lục giác và hình ngũ giác với các ô (nghĩa là các ô có bảy, sáu hoặc năm ô lân cận; ba ô hội tụ ở mỗi “đỉnh” (Hình 9). Có những mẫu vật có cả ô tứ giác và hình bát giác, nhưng các nhà sinh học nhận thấy rằng nếu không có ô “không chuẩn” như vậy (nhỏ hơn ở cạnh thứ năm và lớn hơn bảy cạnh), thì hình ngũ giác luôn lớn hơn các ô hình bảy cạnh đúng 12 lần (hình tổng số ô có thể lên tới vài trăm, thậm chí hàng nghìn).

Tuyên bố bài toán được rút ra từ công thức Euler. (Đối với công thức Euler, xem «Kvant» Số 4, 1972, trang 31 hoặc Courant và Robbin và “Toán học là gì?” M., “Prosveshcheniye”, 1967). Thật vậy, chúng ta hãy biểu thị số đỉnh của một volvox bằng $B$, số cạnh bằng $P$ và số mặt có đỉnh $i$ bằng $\Gamma_i$. Khi đó theo công thức Euler

$$2 = B - P + \Sigma \Gamma_i.$$

Nhưng $3B = \Sigma_i \Gamma_i$, vì theo điều kiện, ba mặt hội tụ ở mỗi đỉnh và $2P = \Sigma_i \Gamma_i$ - hai mặt liền kề với mỗi cạnh. Kể từ đây,

$$12 = 6B - 6P + 6\Sigma \Gamma_i = \Sigma_{2i} \Gamma_i - \Sigma_{3i} \Gamma_i + \Sigma_{6i} \Gamma_i = \Sigma (6 - i) \Gamma_i.$$

Theo điều kiện, không có mặt không chuẩn, tức là $\Gamma_3 = \Gamma_4 = \Gamma_8 = \Gamma_9 = \ldots = 0$. Do đó, $\Gamma_5 - \Gamma_7 = 12$ phù hợp với quan sát của các nhà sinh vật học.

M134

Tập hợp điểm nào được lấp đầy bởi ba hình tam giác có ba đỉnh lần lượt nằm trên ba cạnh $AB, BC$ và $AC$ của tam giác đã cho $ABC$?

Hình 10.

Sẽ thuận tiện cho chúng ta khi xem xét không chỉ các tam giác đầy đủ mà còn cả các tam giác suy biến. Trước tiên chúng ta hãy chứng minh rằng bất kỳ điểm nào của hình lục giác màu xanh đều là trọng tâm của tam giác nội tiếp (Hình 10). Đối với điều này, chúng tôi cần như vậy

Bổ đề. Nếu điểm $O_1$ là trọng tâm của tam giác nội tiếp $K_1L_1M_1$ và điểm $O_2$ là trọng tâm của tam giác nội tiếp $K_2L_2M_2$, thì đối với bất kỳ điểm nào của đoạn $[O_1, O_2]$, người ta có thể chỉ định một tam giác nội tiếp mà nó là trọng tâm. Bây giờ chúng ta đặt các ranh giới $\frac{p_1}{3}$ tại các đỉnh của tam giác $K_1L_1M_1$ và các ranh giới $\frac{p_2}{3}$ tại các đỉnh của tam giác $K_2L_2M_2$ (Hình 11). Trọng tâm của các hình lục giác này trùng với điểm $O_3$. Mặt khác, nó là trọng tâm của ranh giới $\frac{p_1 + p_2}{3}$ đặt tại các đỉnh của tam giác $K_3L_3M_3$ do các cặp ranh giới $\frac{p_1}{3}, \frac{p_2}{3}$ sau đây lần lượt đặt tại các điểm $K_1, K_2; L_1, L_2$ và $M_1, M_2$. Do đó, dựa trên các tam giác $K_1L_1M_1$ và $K_2L_2M_2$ và một điểm tùy ý $O_3$ của đoạn $[O_1, O_2]$, chúng ta đã xây dựng một tam giác $K_3L_3M_3$, trọng tâm của nó. Bổ đề đã được chứng minh.

Bây giờ dễ dàng chứng minh được rằng mọi điểm của lục giác xanh đều là tâm

⟦folio 48⟧

Hình 11.

trọng lực và một số tam giác nội tiếp. Thật vậy, chỉ cần chứng minh điều này cho các đỉnh của nó là đủ và sau đó sử dụng bổ đề - với sự trợ giúp của nó, chúng ta có thể di chuyển từ các đỉnh đến biên và sau đó đến bất kỳ điểm bên trong nào. Nhưng đối với các đỉnh, những tam giác như vậy được xây dựng không gặp khó khăn: đây là những tam giác có các đỉnh nằm ở các đỉnh của tam giác chính và hai đỉnh hợp nhất thành một.

Hình 12.

Vẫn còn phải chứng minh rằng các điểm nằm bên trong các tam giác $AB_1C_1$, $A_1BC_2$, $A_2B_2C$ không thể là trọng tâm của các tam giác nội tiếp. Thật vậy, giả sử một số điểm $O$ của tam giác $AB_1C_1$ được gọi là tam giác $KLM$, mà nó là trọng tâm (Hình 12). Nhưng sau đó nó chia đoạn $KN$ theo tỷ lệ 1:2, điều này là không thể.

L. G. Limanov

Trong số này, chúng tôi xuất bản lời giải bài toán F148—F152

F148

Một hạt nhân có khối lượng $M$, bay với tốc độ $v$, vỡ thành hai mảnh giống hệt nhau. Nội năng của hạt nhân là $E_1$, nội năng của mỗi ổ cắm là $E_2$ ($E_1 > 2E_2$). Xác định góc lớn nhất có thể có giữa vectơ vận tốc của một trong các ổ cắm và vectơ $v$.

Hình 13.

Trong hệ tọa độ liên kết với khối tâm của lõi và chuyển động tương đối với Trái đất với tốc độ $v$, các hạt cói được tách ra theo các hướng ngược nhau với tốc độ bằng nhau. Động năng của các mảnh này bằng hiệu giữa nội năng của hạt nhân và

năng lượng bên trong của Osoklov. Nếu tốc độ của mỗi ổ cắm bằng $v_1$ thì

$$2 \frac{mv_1^2}{2} = E_1 - 2E_2.$$

Từ đây chúng ta tìm thấy tốc độ của từng mảnh:

$$v_1 = \sqrt{\frac{E_1 - 2E_2}{m}} = \sqrt{\frac{2(E_1 - 2E_2)}{M}}.$$

Vận tốc của cói trong hệ tọa độ gắn với Trái Đất bằng tổng vectơ các vận tốc $v$ và $v_1$. Tốc độ $v_1$ của ổ cắm trong hệ tọa độ liên kết với khối tâm của hạt nhân có thể có hướng tùy ý. Nhưng vectơ $v'$ của vận tốc cói trong hệ tọa độ liên kết với Trái Đất tạo góc lớn nhất với vectơ $v$ trong trường hợp vectơ $v_1$ vuông góc với vectơ $v'$ (Hình 12). Trong trường hợp này, vectơ vận tốc của cửa sổ $v'$ tạo một góc $\alpha$ với vectơ $v$ sao cho

$$\sin \alpha = \frac{v_1}{v} = \sqrt{\frac{2(E_1 - 2E_2)}{Mv^2}}.$$

Lực hấp dẫn của hai quả cầu nhỏ sẽ giảm đi bao nhiêu lần, trong đó một quả

⟦folio 49⟧

Cái nào tích điện và cái kia trung tính, nếu khoảng cách giữa các quả bóng tăng gấp đôi?

Quả bóng tích điện là nguồn điện trường làm phân cực quả bóng trung tính. Kết quả của sự phân cực, quả bóng trung tính trở thành một lưỡng cực - một quả bóng nói chung là trung tính có điện tích $+q'$ và $-q'$, khoảng cách giữa chúng bằng đường kính của quả bóng $2r$ (Hình 14). Độ lớn của điện tích $q'$, hay như người ta nói, mức độ phân cực của quả bóng, tỷ lệ thuận với cường độ trường tại tâm của quả bóng này, tức là độ lớn $\frac{q}{R^2}$, trong đó $q$ là điện tích của quả bóng kia:

$$q' = \frac{\alpha q}{R^2}$$

(α là hệ số tỉ lệ).

Bây giờ chúng ta hãy tìm lực tương tác giữa điện tích của các quả bóng. Lực này bằng tổng lực hút giữa điện tích $q$ và điện tích $-q'$ và lực đẩy giữa điện tích $q$ và điện tích $+q'$:

$$F = \frac{qq'}{(R-r)^2} - \frac{qq'}{(R+r)^2} = \frac{\alpha q^2}{R^2} \left( \frac{1}{(R-r)^2} - \frac{1}{(R+r)^2} \right) = \frac{\alpha q^2}{R^2} \frac{4Rr}{(R^2-r^2)^2}.$$

Vì $R > r$, nên $r^2$ có thể bị bỏ qua trong mẫu số của công thức so với $R^2$. Kết quả là chúng tôi nhận được:

$$F = \frac{\alpha q^2}{R^2} \frac{4Rr}{R^4} = \frac{4\alpha q^2 r}{R^5}.$$

Do đó, lực tương tác giữa các quả bóng tỷ lệ với $\frac{1}{R^5}$, trong đó $R$ là khoảng cách giữa tâm các quả bóng. Khi khoảng cách giữa các quả bóng tăng lên 2 lần thì lực tương tác của chúng giảm đi 32 lần:

$$\frac{F_1}{F_2} = \frac{\frac{4\alpha q^2 r}{R^5}}{\frac{4\alpha q^2 r}{(2R)^5}} = 2^5 = 32.$$

Hình 14.

F150

Ở một số thiên hà, một ngôi sao 3 với một hành tinh Π đã được phát hiện, thực hiện một vòng quanh ngôi sao trong thời gian $T_1$ và một vòng quanh ngôi sao trong thời gian $T_2$. Vệ tinh của hành tinh C quay một vòng quanh ngôi sao. Mất bao lâu để nhật thực của vệ tinh C lặp lại tại một vị trí nhất định trên hành tinh?

Mọi vật đều quay trong cùng một mặt phẳng.

Giả sử trong hệ tọa độ liên kết với các ngôi sao cố định, hành tinh và vệ tinh quay như hình 15, và $\omega_1 = \frac{2\pi}{T_1}$ là vận tốc góc chuyển động quay của hành tinh quanh trục quay của chính nó $\omega_3 = \frac{2\pi}{T_3}$ là vận tốc góc chuyển động quay của vệ tinh quanh trục quay $\omega_3$.

Trong hệ tọa độ gắn liền với hành tinh nhưng không quay tương đối với các ngôi sao cố định ở xa, ngôi sao quay quanh hành tinh với vận tốc góc $\omega_1$, như trong Hình 15, và vệ tinh quay quanh spi $\omega_3$.

Lúc này nó sẽ chuyển sang một hệ tọa độ gắn liền với hành tinh và quay cùng với nó. Trong hệ tọa độ này, ngôi sao quay quanh hành tinh với vận tốc góc $\omega' = \omega_1 - \omega_2$ và vệ tinh có vận tốc góc $\omega'' = \omega_3 - \omega_2$.

Nếu tại một thời điểm nào đó, vệ tinh được quan sát thấy nhật thực trên hành tinh, thì lần nhật thực tiếp theo của vệ tinh sẽ được quan sát trên hành tinh sau thời gian $t$, sau đó ngôi sao sẽ bị che khuất một góc $\varphi$ và vệ tinh sẽ bị che khuất một góc $2\pi + \varphi$. Chúng tôi giả sử $\omega_3 > \omega_1$.

$$\varphi = \omega' t$$

Và

$$2\pi + \varphi = \omega'' t.$$

Từ đây

$$2\pi = (\omega'' - \omega') t,$$

$$t = \frac{2\pi}{\omega'' - \omega'} = \frac{2\pi}{\omega_3 - \omega_1} = \frac{T_1 T_3}{T_1 - T_3}.$$

Rõ ràng là nhật thực tiếp theo sẽ xảy ra khi ngôi sao xuất hiện ở một góc $2\varphi$, sau đó khi nó xuất hiện ở một góc $3\varphi$, v.v. Nếu đối với một số nguyên $N$ thì số $N\varphi$ bằng bội số nguyên của $2\pi$, thì nhật thực $N$ sẽ gắn với điểm bắt đầu. Vì vậy, nếu $N\varphi = 2\pi m$, tức là nếu số $\frac{\varphi}{2\pi}$ có thể được biểu diễn dưới dạng phân số tối giản

$$\frac{\varphi}{2\pi} = \frac{\omega'}{\omega'' - \omega'} = \frac{T_3(T_2 - T_1)}{T_2(T_1 - T_3)} = \frac{m}{N},$$

⟦folio 50⟧

Pis. 15.

rồi sau một thời gian
$$mt = \frac{2\pi m}{\omega'' - \omega'} = \frac{2\pi m T_3 T_1}{T_1 - T_3}$$

nhật thực sẽ ở cùng một điểm. Nếu số $\frac{\varphi}{2\pi}$ và đường viền nằm trên một đường thẳng thì $N\varphi (N = 1, 2, 3, \dots)$ sẽ không bao giờ là bội số nguyên của 2l và do đó, bóng sẽ không bao giờ ở cùng một điểm.

Tất nhiên, trong thực tế, mối quan hệ $\frac{\varphi}{2\pi} = \frac{\omega'}{\omega'' - \omega'} = \frac{T_3 (T_2 - T_1)}{T_2 (T_1 - T_3)}$ chỉ có thể được xác định một cách gần đúng và không có ý nghĩa

Hãy nói xem con số này là hợp lý hay không hợp lý. Nhưng lý luận của chúng tôi cho thấy rằng nếu số $\frac{m}{N}$ có tử số và mẫu số nhỏ, thì nhật thực sẽ xảy ra gần như chính xác ở một trong các vị trí $N$ trong kế hoạch (tuần tự đi qua tất cả các vị trí $N$ này) và nếu không, nó sẽ xảy ra mỗi lần ở một địa điểm mới.

F151

Hai gương phẳng tạo thành hai góc bằng 0 cách nhau 90°. Một đường thẳng có tiêu cự $F$ được chèn vào góc sao cho trục quang chính của đường thẳng tạo một góc 45° với mỗi gương. Bán kính của đường thẳng bằng tiêu cự của nó. Tại vị trí này, ảnh của nguồn nằm trên trục quang chính của đường thẳng và cách đường đó 1,5F. Viết được công thức Lina
$$\frac{1}{F} = \frac{1}{1,5F} + \frac{1}{f_1},$$
chúng ta sẽ tìm
$$f_1 = 3 F.$$
Điều này có nghĩa là điểm $S_1$ nằm cách đường giao nhau của gương một khoảng 2F. Nhưng các tia tới gương $I$ bị phản xạ khỏi gương và nếu không có gương $II$ thì chúng sẽ giao nhau tại điểm $S_2$. Điểm $S_2$ nằm trên đường thẳng vuông góc với trục quang của đường thẳng đó, cách đường giao nhau của gương một khoảng 2F. Hãy chứng minh điều đó.

Góc 1 bằng góc 2 (như thể nằm ngang) và bằng góc 3 (điều này tuân theo định luật phản xạ). Do đó, góc 2 bằng góc 3. Cũng có thể chứng minh rằng góc 4 bằng góc 5. Nhưng suy ra tam giác $ABS_2$ bằng tam giác $ABS_1$ - chúng có một cạnh chung $AB$ và các góc kề với cạnh này bằng nhau. Rõ ràng, tam giác $ABS_2$ là hình chiếu của tam giác $ABS_1$ đối với đường thẳng $I-I$. Theo sau đó là $OS_2 = OS_1 = 2F$ và vì $S_1OC = S_2OC = 45^\circ$ nên $S_2OS_1 = 90^\circ$.

Không khó để chỉ ra rằng các tia đi tới gương $II$ tới “nguồn tối thiểu”, điểm $S_2$, bị phản xạ, sẽ giao nhau nếu không có đường thẳng, tại điểm $S_3$, nằm trên trục quang chính của đường thẳng đó và cách đường giao nhau một khoảng 2F, tức là cách đường thẳng $F$.

⟦folio 51⟧

Hình 16.

Điểm $S_3$ là nguồn tối thiểu cho ống kính. Hãy cùng tìm hình ảnh của nó $S_4$. Để làm điều này, hãy viết lại công thức thấu kính:

$$\frac{1}{F} = \frac{1}{d} + \frac{1}{f_2},$$

trong đó $d = -F$ (vì nguồn $S_3$ là tối thiểu), $a$ $f_2$ là khoảng cách từ thấu kính đến ảnh $S_4$.

Từ phương trình cuối cùng chúng ta tìm thấy

$$f_2 = 0,5 F.$$

Như vậy, ảnh $S_4$ của nguồn $S$ do hệ thống đưa ra sẽ cách thấu kính 0,5 $F$.

F152

Thể tích của một bể khí hình thành do một vụ nổ dưới nước sâu dao động với chu kỳ tỷ lệ với $pa\rho bEc$, trong đó $p$ là áp suất, $\rho$ là mật độ của nước và $E$ là tổng năng lượng của vụ nổ. Tìm $a$, $b$ và $c$.

Người ta biết rằng

$$T \sim pa\rho bEc.$$

Đại lượng ở bên trái trong công thức này có thứ nguyên thời gian $[c]$. Số lượng ở bên phải phải có cùng thứ nguyên. Hãy viết kích thước của tất cả các đại lượng:

$$p \rightarrow \left[ \frac{H}{m^2} \right] \rightarrow \left[ \frac{\kappa_2}{m \cdot c^2} \right]; \quad \rho \rightarrow \left[ \frac{\kappa_2}{m^3} \right];$$

$$E \rightarrow [\partial \kappa] \rightarrow \left[ \frac{\kappa_2 \cdot m^2}{c^2} \right].$$

Sản phẩm $\rho a\rho bEc$ có kích thước

$$\left[ \frac{\kappa_2}{m \cdot c^2} \right]^a \left[ \frac{\kappa_2}{m^3} \right]^b \left[ \frac{\kappa_2 \cdot m^2}{c^2} \right]^c \rightarrow [\kappa_2]^{a+b+c} [m]^{-a-3b+2c} [c]^{-2a-2c}.$$

Để kích thước của sản phẩm này là $[c]$, điều cần thiết là

$$-2a - 2c = 1,$$

$$a + b + c = 0,$$

$$-a - 3b + 2c = 0.$$

Giải hệ phương trình này, ta tìm được

$$a = -\frac{5}{6}; \quad b = \frac{1}{2}; \quad c = \frac{1}{3}.$$

Kể từ đây,

$$T \sim p^{-\frac{5}{6}} \rho^{\frac{1}{2}} E^{\frac{1}{3}}.$$

Tôi. Sh. Slobodetsky.
