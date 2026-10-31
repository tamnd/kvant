---
id: 1986-10-resheniya-zadach-m986-m990-f998-f1002-d5d688fb
issue: kvant_1986_10
year: 1986
number: "10"
title: Lời giải bài toán M986—M990; F998—F1002
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 36
page_last: 43
page_labels: 34, 35, 36, 37, 38, 39, 41
tag: RQJH
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 2997cb5e0c4b14551cb6e26e4ebe956829e0315e6163187e6bcb412e29f5b679
prompt_sha256: draft-1
translated_from: content/ru/1986/10/articles/15_resheniya-zadach-m986-m990-f998-f1002-d5d688fb.md
source_content_sha256: 977008c7ca4e47855d2c6a0e320a361dc2809f2a9f1c6415c456aede9fd667d3
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 34⟧

Lời giải bài toán

M986—M990; F998—F1002

Hãy đặt $a=x^{10}$, $b=y^{15}$ và xét hàm số
$$f(x)=2x^5+3y^5-5x^2y^3, \quad x \geqslant 0$$
(đã cố định $y > 0$). Chúng ta phải chứng minh rằng $f(x) \geqslant 0$. phái sinh
$$f'(x)=10x^4-10xy^3=10x(x^3-y^3)$$
trở thành 0 tại $x=y$, âm tại $0 < x < y$ và dương tại $x > y$. Do đó (xem hình), đối với $x=y$ hàm $f(x)$ nhận giá trị nhỏ nhất và với tất cả $x > 0$
$$f(x) \geqslant f(y)=2y^5+3y^5-5y^5=0.$$
Các bằng chứng khác không sử dụng phép tính có thể thu được bằng cách phân tích nhân tử $f(x)$:
$$f(x)=(x-y)^2(2x^3+4x^2y+6xy^2+3y^3)$$
hoặc sử dụng bất đẳng thức giữa đối số trung bình và trung bình hình học cho phần gót của số $x^5, x^5, y^5, y^5, y^5$:
$$\frac{2x^5+3y^5}{5} \geqslant \sqrt[5]{x^5 \cdot 2y^5 \cdot 3}=x^2y^3.$$
(Thảo luận chi tiết về bài toán này có trong ấn bản mới của cuốn sách “Tối ưu hóa toán học tương ứng”, M.: - “Nauka”, 1986, bài toán 4-16.)

N. V. Vasiliev

M987. Có 2 đội tham gia giải đấu. Trong cặp lệnh đầu tiên.type có một số cặp lệnh, trong cặp lệnh thứ hai - other.m. Chứng minh rằng sau đó bạn có thể chọn được m đội, trong đó chưa có hai đội nào từng đấu với nhau.

Hãy mô tả các lệnh 2m của chúng ta dưới dạng các điểm trên mặt phẳng. Chúng ta sẽ kết nối các cặp lệnh gặp trong phần đầu tiên với các đoạn màu đỏ và trong phần thứ hai với các đoạn màu xanh lam. Khi đó từ mỗi điểm sẽ có một đoạn màu đỏ và một đoạn màu xanh. Bất kỳ lệnh nào cũng thuộc về một “chu trình” nhất định - một đường đứt nét khép kín bao gồm các đoạn màu xanh và đỏ xen kẽ, sao cho tất cả các điểm 2m và đoạn 2m nối chúng tạo thành một hoặc nhiều chu trình như vậy (xem hình). Vì các màu xen kẽ nên số lượng lệnh trong mỗi chu kỳ là số chẵn. Bằng cách chọn trong mỗi chu kỳ việc sử dụng các đội cạnh nhau, chúng ta sẽ có được tập hợp m đội chưa chơi với nhau. Từ lời giải, rõ ràng là có thể chọn một bộ như vậy $2^c$ theo nhiều cách khác nhau, trong đó $c$ là số vòng và không thể chọn hơn m đội chưa đấu với nhau*).

M. Bona

M988. Từ điểm O của mặt phẳng vẽ n vectơ có độ dài đơn vị. Chứng minh rằng nếu với một số $k < n/2$ có ít nhất k vectơ ở cả hai phía của mỗi đường thẳng đi qua O thì độ dài tổng của tất cả n vectơ lớn nhất là n-2k.

Đặt $\vec{s}$ là tổng của các vectơ này; có thể được coi là $\vec{s} \neq \vec{0}$, nếu không thì mọi thứ đều rất rõ ràng. Ví dụ: nửa trục dương $Ox$ của hệ tọa độ $Oxy$ dọc theo vectơ $\vec{s}$. Di chuyển theo chiều kim đồng hồ từ

*)Đây là một bài toán khác có ý tưởng tương tự lời giải: chứng minh rằng nếu mỗi trong số m thành viên của vòng tròn giải được hai trong số m đề xuất bài toán thì có thể tổ chức phân tích bài toán sao cho mỗi người giải được một giải được bài toán (xem bài toán 5-42 trong cuốn sách được đề cập ở lời giải M986).

⟦folio 35⟧

nửa mặt phẳng âm $Ox$, chúng ta đo các vectơ này nằm ở nửa mặt phẳng trên $y \geqslant 0$:
$\vec{a}_1, \vec{a}_2, \dots$; tương tự, di chuyển ngược chiều kim đồng hồ, chúng ta cố định các vectơ còn lại (ở nửa mặt phẳng dưới): $\vec{b}_1, \vec{b}_2, \dots$ (xem hình). Theo điều kiện, ít nhất $k$ vectơ nằm trong nửa mặt phẳng bên trái $x \leqslant 0$; đặt nó là $\vec{a}_1, \vec{a}_2, \dots, \vec{a}_l$ và $\vec{b}_1, \vec{b}_2, \dots, \vec{b}_{k-1}$, ... Điều kiện “ở cả hai phía của mỗi đường thẳng có ít nhất $k$ vectơ” tương đương với việc mỗi vectơ $n$, cùng với $k$ theo sau nó ngược chiều kim đồng hồ (hoặc theo chiều kim đồng hồ) nằm trong cùng một nửa mặt phẳng. Theo đó, có $k$ tổng các vectơ theo cặp:
$\vec{a}_1 + \vec{b}_{k-1+1}$ (nghĩa là tổng của vectơ $a_1$ và $k$ từ nó ngược chiều kim đồng hồ, $\vec{a}_{l-1} + \vec{b}_{k-l+2}, \dots, \vec{a}_1 + \vec{b}_k$, cũng như $\vec{b}_{k-l} + \vec{a}_{l+1}, \vec{b}_{k-1-l} + \vec{a}_{l+2}, \dots, \vec{b}_1 + \vec{a}_k$ - tất cả đều cho hình chiếu âm lên trục $Ox$. (Thật vậy, ví dụ: tổng $\vec{v} = \vec{a}_1 + \vec{b}_k$ hướng dọc theo phân giác của góc được tạo bởi vectơ $\vec{a}_1$ và $\vec{b}_k$, và nửa trục âm $Ox$ nằm bên trong góc này và do đó tạo thành một góc nhọn với $\vec{v}$.) Hình chiếu của mỗi vectơ $n-2k$ còn lại không lớn hơn 1. Do đó, hình chiếu của tổng tất cả các vectơ và nó bằng độ dài $\vec{s}$, không lớn hơn $n-2k$.

Lưu ý rằng trong điều kiện bài toán một vectơ nằm trên một đường thẳng có thể được coi là nằm ở bất kỳ phía nào của nó.

Sẽ rất thú vị nếu thu được một phát biểu tương tự như bài toán của chúng tôi đối với vectơ trong không gian.

P. A. Kalutsin, V. V. Prasolov

◆ Đặt $d_1, d_2, \dots, d_n$ là ước của số $a$ sao cho
$$a - 1 = \frac{a}{d_1} + \frac{a}{d_2} + \dots + \frac{a}{d_n}.$$
Sau đó
$$1 - \frac{1}{a} = \frac{1}{d_1} + \frac{1}{d_2} + \dots + \frac{1}{d_n} < 1.$$ (1)

Ý tưởng của lời giải bài toán là mỗi $n=2, 3, \dots$ trong tập hợp $X_n$ các số được biểu thị bằng tổng của $n$ số, tượng hình của các số tự nhiên, biểu thị số lớn nhất $\mu_n$, hoàn toàn nhỏ hơn 1. Sau đó, từ (1) ước tính cho $a$ sẽ như sau:
$$1 - \frac{1}{a} \leqslant \mu_n \Rightarrow a \leqslant \frac{1}{1-\mu_n}.$$ (2)

Lưu ý rằng vì tập hợp $X_n$ là vô hạn, nên ngay cả sự tồn tại của $\mu_n$ như vậy cho mỗi $n$ cũng cần bằng chứng: một lời giải thích trực quan về bằng chứng này, mà chúng tôi sẽ đưa ra ở điểm c), là $X_n$ có được bằng cách thêm vào mỗi số từ $X_{n-1}$ tất cả các số có dạng $1/k$ ($k=1, 2, \dots$) và do đó các điểm từ $X_n$ chỉ tích lũy với số lượng vô hạn ở bên phải của mỗi điểm từ $X_{n-1}$ và không thể tích lũy ở bên trái của mỗi điểm (cụ thể là từ điểm 1).

a) Đáp số: $a=3, 4, 6$. Nếu như
$$x = \frac{1}{k_1} + \frac{1}{k_2} < 1, \quad k_1 \leqslant k_2,$$
sau đó $k_1 \geqslant 2, k_2 \geqslant 3$ (bắt đầu $x \geqslant 1/2 + 1/2=1$), do đó $x \leqslant \mu_2=1/2+1/3=5/6$ và từ (2) dẫn đến $a \leqslant 6$. Duyệt qua tất cả $a$ như vậy, ta thấy số đó là $a-1$

⟦folio 36⟧

có thể được biểu diễn dưới dạng tổng của hai ước $a$ chỉ cho $a=3, 4$ và 6 (trong những trường hợp này $a-1$ bằng $2=1+1, 3=2+1, 5=3+2$; 4 không thể được biểu diễn dưới dạng tổng của hai ước $a=5$).

6) Cho phép

$$x = \frac{1}{k_1} + \frac{1}{k_2} + \frac{1}{k_3} < 1, \quad k_1 \leqslant k_2 \leqslant k_3.$$

Nếu $k_1 \geqslant 3$ thì $x \leqslant 1/3+1/3+1/4=11/12$; nếu $k_1=2, \quad k_2 \geqslant 4$, thì $x \leqslant 1/2+1/4+1/5=19/20$; nếu $k_1=2, \quad k_2=3$ thì $k_3 \geqslant 7$ và

$$x \leqslant 1/2+1/3+1/7=41/42.$$

Do đó, $\mu_3=41/42$ và từ (2) suy ra $a \leqslant 42$. Bằng cách xem qua $a$ này, chúng ta có thể chọn những cái mà $a-1$ được biểu thị dưới dạng tổng của ba ước $a-1$. Đáp số: $a=4, 6, 8, 10, 12, 18, 20, 24$ và 42.

c) Chứng minh rằng với mọi $c>0$ trong tập hợp số thuộc $X_n$ và nhỏ hơn $c$ thì có số $\mu_n(c)$ lớn nhất. (Đối với lời giải bài toán chỉ cần chứng minh điều này cho $c=1$ là đủ, nhưng một phát biểu tổng quát hơn sẽ dễ chứng minh hơn bằng cách chỉ ra trên $n$.) Ví dụ: $X_n$ là một tập hợp vô hạn các số có dạng

$$x = \frac{1}{k_1} + \frac{1}{k_2} + \dots + \frac{1}{k_n},$$

(3)

trong đó $k_1, k_2, \dots, k_n$ là số tự nhiên.

Đối với $n=1$ tuyên bố của chúng tôi rất rõ ràng: $\mu_n(c)$ là số lớn nhất của dạng $1/k$, nhỏ hơn $c$, tức là $1/[c+1]$ (dấu ngoặc vuông biểu thị phần nguyên của số). Hãy để tuyên bố của chúng tôi được chứng minh cho $X_{n-1}$; Hãy chứng minh điều đó cho $X_n$.

Chúng ta hãy chọn một số tự nhiên $k$ sao cho $n/k < c$ (chúng ta có thể lấy $k=[n/c]+1$). Sau đó, trong số các số $x$ từ $X_n$, nhỏ hơn $c$, có số $n/k$ (tổng của $n$ phân số $1/k$) và dưới dạng biểu diễn (3) của bất kỳ số nào $x$, cũng là $n/k < x < c$, mặc dù một trong các phân số $1/k_i$ lớn hơn $1/k$, tức là $k_i \leqslant k-1$. Hơn nữa, $x-1/k_i$ thuộc về $X_{n-1}$ và phần lớn trong số này $x$ - và đây là $\mu_n(c)$ - sẽ bằng phần lớn của tập hợp số hữu hạn

$$\frac{n}{k}, \quad \mu_n\left(c - \frac{1}{k-1}\right) + \frac{1}{k-1},$$

$$\mu_n\left(c - \frac{1}{k-2}\right) + \frac{1}{k-2}, \dots, \quad \mu_n\left(c - \frac{1}{l}\right) + \frac{1}{l}$$

(trong đó $l$ là số tự nhiên nhất mà $c-1/l>0$, tức là $l=[1/c]+1$).

Hóa ra với mỗi $n=3, 4, \dots$, bạn có thể chỉ ra số $a_n$ nhiều nhất, trong đó $a_n-1$ được biểu thị bằng tổng của $n$ ước số $a_n$: cách đây khá lâu đã có giả thuyết rằng $\mu_n(1)$ - một số có dạng (3) gần bằng 1 ở bên trái - bằng tổng của số đầu tiên $n$ phân số $n$ phân số

$$\frac{1}{2} + \frac{1}{3} + \frac{1}{7} + \frac{1}{43} + \frac{1}{1807} + \dots,$$

trong đó mẫu số của mỗi phân số lớn hơn tích của mẫu số của tất cả các phân số trước đó 1 đơn vị; theo đó $a_n$ là tích của mẫu số của phân số $n$ đầu tiên (tức là $a_{n+1}=a_n^2-a_n$).

H. B. Vasiliev

⟦folio 37⟧

M990. Ba đường thẳng cắt nhau a, b và c không song song với cùng một mặt phẳng được cho trong không gian; có nhiều đường thẳng song song trong đó ba đường thẳng này là:
a) chạy dọc theo các xương sườn,
b) đi dọc theo các cạnh hoặc đường chéo của các mặt,
b) chứa b đỉnh song song?

Trước tiên chúng ta hãy lưu ý rằng với ba đường thẳng cắt nhau a, b và c bất kỳ không song song với cùng một mặt phẳng, sẽ có một đoạn duy nhất có các điểm cuối tại a và b, song song với c.

Thật vậy, đoạn cần tìm phải nằm trong mặt phẳng a, chứa a và song song với c. Hiển nhiên, tồn tại một mặt phẳng như vậy (có thể kiểm tra qua a và bất kỳ đường thẳng nào cắt a và song song với c), duy nhất và không song song với b. Điểm giao nhau của a và b là một trong những điểm cuối của đoạn thẳng của chúng tôi. Chúng ta hãy vẽ một đường thẳng song song với c cho đến khi nó cắt a và chúng ta sẽ có đầu thứ hai.

Chúng tôi sẽ phải thực hiện loại phân đoạn này nhiều lần; Để cho ngắn gọn, chúng ta sẽ gọi nó là cầu c giữa a và b hoặc đơn giản là cầu c. Trong Hình 1-9, các dòng dữ liệu được biểu thị bằng màu sắc và những dòng theo chủ nghĩa hoài cổ được biểu thị bằng màu đỏ.

a) Đáp số: 1. Rõ ràng 3 vị trí được xác định bởi các đường này là các cạnh của hình bình hành độc quyền (hình 1). Sau khi xây dựng chúng, chúng ta có 6 đỉnh, sau đó 2 đỉnh cuối cùng cũng được khôi phục duy nhất.

b) Đáp số: 19. Trước tiên chúng ta hãy liệt kê tất cả các bộ ba cạnh hoặc đường chéo giao nhau theo cặp có thể có của các mặt của một hình bình hành. Chúng có thể chứa:
1) 3 xương sườn (xem bài toán a));
2) đường chéo của mặt a, cạnh b song song với mặt này và cạnh c cắt nó (hình 2);
3) cạnh a, đường chéo b của mặt song song với a và đường chéo c của mặt cắt a (hình 3);
4) cạnh a và các đường chéo b, c của hai mặt song song với a (hình 4);
5) 3 đường chéo a, b và c của các mặt, trong đó 2 (giả sử b và c) nằm trên các mặt song song (hình 5).

Trong mỗi trường hợp này, đường song song có thể được xây dựng lại một cách duy nhất nếu cho trước các dòng chứa các đoạn a, b và c và nó cho biết dòng nào thuộc về từng đoạn này; Hơn nữa, những dòng như vậy có thể là 3 dòng bất kỳ thỏa mãn điều kiện bài toán.

Cách xây dựng một đường song song bằng cách sử dụng “những cây cầu” của chúng tôi đã được công bố hình 2-5. Chúng ta hãy xem xét chi tiết hơn chỉ một trường hợp 2). Bằng cách dựng cầu c AB giữa a và b và cầu b CD giữa c và a, chúng ta thu được 4 đỉnh của hình bình hành - đầu A và D của đường chéo của mặt a và một đầu mỗi đầu - B và C - của cạnh b và c. Để dựng các đỉnh còn lại, chỉ cần vẽ vectơ $\vec{AB}$ từ các điểm C và D và vectơ $\vec{CD}$ từ các điểm A và B. Cách xây dựng trong trường hợp 3) và 4) là tương tự nhau, và trong trường hợp 5) các đầu cầu của chúng ta có 4 đỉnh và tâm của hai mặt đối diện của hình bình hành, giúp dễ dàng tìm thấy các đỉnh còn lại.

Trong mỗi trường hợp 2)—5) cũng cần chỉ ra đoạn a, b, c nào sẽ nằm trên mỗi đoạn thẳng trong số ba đoạn thẳng đã cho. Việc “phân bố trường” này có thể được thực hiện theo 6 cách khác nhau và, như có thể thấy từ cách xây dựng, trong trường hợp 2) và 3) điều này tạo ra 6 hình bình hành khác nhau và trong trường hợp 4) và 5) - 3 (vì cấu trúc không thay đổi khi b và c được sắp xếp lại). Tổng hợp số hình bình hành trong mọi trường hợp, chúng ta được 1+6+6+3=19.

⟦folio 38⟧

B) Đáp số: 31. Đối với các tùy chọn được xem xét ở lời giải bài toán 6), những tùy chọn trong đó một trong các đường thẳng chứa đường chéo $a$ của hình bình hành và đường còn lại 2 -
6) 2 cạnh $b$ và $c$ (hình 6),
7) cạnh $b$ và đường chéo mặt $c$ (hình 7),
8) 2 đường chéo của các mặt $b$ và $c$ (hình 8).

Hãy xây dựng các cây cầu $b$- và $c$-. Trong trường hợp 6) các đầu của chúng là các đỉnh của hình bình hành và cách xây dựng tiếp theo rõ ràng từ hình 6. Trong trường hợp 7) cầu $b$-cầu $AC$ giữa $a$ và $c$ là một cạnh của hình bình hành; nếu $BD$ là cầu nối $c$ giữa $b$ và $a$ thì điểm $D$ (như các điểm $A$, $C$) là đỉnh của hình bình hành, 2 đỉnh nữa là hai đầu của vectơ bằng $\vec{CA}$, nằm từ $D$ và $B$, 3 đỉnh còn lại được xây dựng theo cách rất khác nhau (hình 7). Việc xây dựng trong trường hợp sau có phần phức tạp hơn 8). Đặt $A_1B$ và $A_2C$ lần lượt là $c$- và $b$-cầu nối giữa $a$ và $b$ hoặc $a$ và $c$ (hình 8). Sau đó, các điểm $A_1$ và $A_2$ chia đường chéo $a$ của hình bình hành thành 3 phần bằng nhau, còn các điểm $B$ và $C$ chia các đoạn $b$ và $c$ theo tỷ lệ 2:1, các đoạn $A_1B$ và $A_2C$ ngắn hơn 3 lần đường chéo $c$ và $b$. (Những câu lệnh này trở nên rõ ràng nếu bạn nhìn vào hình chiếu của hình bình hành dọc theo đường chéo $b$ - hình 9 - và tính đến rằng với phép chiếu song song, tỷ lệ độ dài của các đoạn song song được giữ nguyên.) Bây giờ, đặt các vectơ $\overrightarrow{A_2A_1}$ và $\overrightarrow{2A_1A_2}$ từ $A_1$ sang một bên, chúng ta tìm thấy các đầu của đoạn $a$; Đặt các vectơ $\overrightarrow{BA_1}$ và $\overrightarrow{2A_1B}$ từ $C$ sang một bên, chúng ta tìm các đầu của đoạn $c$ và tương tự, các đầu $b$, sau đó vẫn dựng 2 đỉnh còn lại bằng 6 đỉnh.

Vì trong trường hợp 7) có 6 cách để “phân phối các trường” giữa các dòng đã cho và trong trường hợp 6) và 8) có 3 cách, nên tổng số song song là $19 + 3 + 6 + 3 = 31$.

V. N. Dubrovsky

F998. Một vận động viên trượt tuyết đi xuống một ngọn núi cao với tốc độ đã định $v$. Núi tạo thành một khối có mặt cắt ngang và thông suốt thành mặt cắt ngang. Người trượt tuyết nên nghiêng người như thế nào để tránh bị ngã trong quá trình chuyển tiếp? Hãy coi rằng quá trình chuyển đổi vượt qua người trượt tuyết bằng $M$. Bỏ qua chuyển động của không khí.

Vì quá trình chuyển đổi diễn ra suôn sẻ nên động năng của vận động viên trượt tuyết được hình thành và tốc độ của anh ta $v_1$ ngay sau khi chuyển sang phần nằm ngang bằng $(по модулю) v$. Sự thay đổi động lượng của người trượt tuyết trong thời gian chuyển tiếp $t$ bằng $\Delta \vec{p} = M(\vec{v}_1 - \vec{v})$ và hướng dọc theo đường phân giác của góc $ABC$ (xem hìnhnok).

Từ định luật biến thiên động lượng, xét đến giá trị nhỏ của $t$, ta có: $\Delta \vec{p} = f\tau$, trong đó $\vec{f}$ là lực tác dụng lên cơ thể người trượt tuyết từ đường trượt (nó cũng hướng dọc theo đường phân giác). Để người trượt tuyết giữ thăng bằng, vectơ của lực này cần phải đi qua khối tâm của người trượt tuyết. Từ điều kiện này, người ta thấy rằng tại thời điểm chuyển sang mặt cắt ngang nó phải nghiêng về phía trước một góc $\alpha/2$ so với vị trí mà nó chiếm khi di chuyển dọc theo sườn dốc.

A. N. Semenov

⟦folio 39⟧

F999. Một túi có khối lượng $m_1$, được nối bằng một sợi dây nhỏ cứng với một túi có khối lượng $m_2$, trượt dọc theo mặt ngang chính của bàn. Sợi dây nối các túi đi qua một lỗ nhỏ trên bàn (xem hình). Chiều dài của sợi dây là $L$, chiều cao của bàn là $H$ và $H < L$. Hỏi độ cao của túi $m_2$ sau khi chạm sàn là bao nhiêu nếu tại thời điểm ban đầu toàn bộ sợi dây nằm trên bàn và các túi không chuyển động?

Vận tốc $v$ của các túi tại thời điểm một trong số chúng chạm sàn được xác định bởi định luật bảo toàn năng lượng:

$$\frac{1}{2} (m_1 + m_2) v^2 = m_2 g H.$$

Sau va chạm, túi có khối lượng $m_1$ sẽ chuyển động dọc theo bàn cho đến khi kéo được sợi dây. Lúc này, chiếc túi $m_2$ đang nằm trên sàn được cá tăng tốc sao cho tốc độ của các túi có độ lớn bằng nhau.

Sự thay đổi tốc độ của các túi về giá trị tuyệt đối trong quá trình giật này cũng giống như khi túi có khối lượng $m_2$ không nằm trên sàn mà nằm trên bàn. Thật vậy, sự tương tác của các túi được thực hiện thông qua sợi dây, và lực tác dụng lên túi nằm trên sàn chỉ khác hướng so với lực tác dụng lên túi khi nó nằm trên bàn.

Do đó, có thể tìm vận tốc của các túi $u$ sau cú giật bằng định luật bảo toàn động lượng:

$$m_1 v = (m_1 + m_2) u.$$

Chuyển động tiếp theo của túi một lần nữa được “điều khiển” bởi định luật bảo toàn năng lượng và độ cao tối đa $h$ của việc nâng túi $m_2$ được xác định bởi sự tương ứng

$$m_2 g h = \frac{1}{2} (m_1 + m_2) u^2.$$

Loại bỏ $v$, $u$ khỏi (1), (2), (3), ta thu được:

$$h = \left( \frac{m_1}{m_1 + m_2} \right)^2 H.$$

G. L. Kotkin

F1000. Dòng điện $I$, chạy dọc theo đường viền được tạo bởi bốn cạnh của khối lập phương (hình 1), tạo ra một từ trường có cảm ứng $B_0$ ở trung tâm của khối lập phương. Tìm độ lớn và hướng của vectơ cảm ứng từ trường được tạo ra ở tâm khối lập phương bởi dòng điện $I$ chạy dọc theo đường viền có sáu cạnh (xem hình 2 trên trang 40).

Hình 1.

Từ các thông báo đối xứng, ta suy ra rằng chỉ báo $\vec{B}_0$ của trường được tạo ở tâm khối (tại điểm $O$) bởi dòng điện $I$ chạy dọc theo đường viền $ABCDA$ (xem hình 1) song song với trục $OY$. Thật vậy, khi quay $90^\circ$ quanh $OY$, đường viền $ABCDA$ biến thành chính nó, do đó, vectơ $\vec{B}_0$ cũng phải biến thành chính nó. Theo gimlet, vectơ $\vec{B}_0$ hướng dọc theo $OY$. Do đó, trong phép chiếu trên trục $OX, OY, OZ$

$$\vec{B}_0 = (B_x, B_y, B_z) = (0, B_0, 0).$$

Để tìm trường $\vec{B}$ được tạo bởi dòng điện chạy dọc theo đường viền $ABCGHEA$ (xem hình 2), chúng ta sử dụng nguyên lý chồng chất. Lưu ý rằng sẽ thu được sự phân bố dòng điện chính xác như nhau dọc theo các cạnh của khối lập phương nếu chúng ta lấy ba mạch: $ABCDA$, $DCGHD$ và $ADHEA$, dọc theo mỗi mạch có dòng điện là $I$. Điều này có nghĩa là sự kết hợp của ba đường viền này sẽ tạo ra trường mong muốn $\vec{B}$ ở giữa khối lập phương. Theo nguyên lý chồng chất, $\vec{B}$ bằng tổng vectơ của ba trường được tạo bởi mỗi mạch:

$$\vec{B} = \vec{B}_{ABCDA} + \vec{B}_{DCGHD} + \vec{B}_{ADHEA} = (0, B_0, 0) + (-B_0, 0, 0) + (0, 0, B_0) = (-B_0, B_0, B_0).$$

⟦folio 41⟧

F1002. Một nguồn sáng điểm đặt cách màn một khoảng L. Một thấu kính hội tụ có tiêu cự F > (L/4), song song với màn, di chuyển giữa nguồn và màn. Tại vị trí nào của thấu kính thì đường kính của điểm nhìn thấy trên màn là nhỏ nhất?

Để thấu kính dịch chuyển sang một bên sao cho khoảng cách giữa thấu kính và màn không thay đổi. Khi đó kích thước của vết trên màn không thay đổi, vì chùm tia phía sau thấu kính là một hình nón có đỉnh nằm trong ảnh thật hoặc ảnh nhỏ nhất của nguồn và tia sáng đi qua chu vi của thấu kính. Vì điểm giao nhau của các mặt phẳng của thấu kính và màn với chiều cao của hình nón không thay đổi trong ánh sáng như vậy, nên (do độ tương tự) kích thước của điểm cũng không thay đổi.

Do đó, chúng ta có thể di chuyển thấu kính sao cho nguồn nằm trên trục quang chính của nó. Gọi x là khoảng cách từ nguồn tới thấu kính. Không khó để chỉ ra rằng trong điều kiện F > (L/4) không thể thu được ảnh sắc nét của nguồn (điểm) trên màn - tại bất kỳ vị trí nào của thấu kính, sẽ nhìn thấy một điểm trên màn, đường kính d của nó phụ thuộc vào x và nhỏ nhất tại x = x₀. Trong thực tế, hình ảnh nguồn xuất hiện trên màn hình nếu

$$\frac{1}{x} + \frac{1}{L-x} = \frac{1}{F},$$

hoặc $x^2 - Lx + FL = 0$,

nhưng phương trình này không có lời giải—phân biệt đối xử $L^2 - 4FL = 4L((L/4) - F)$ của nó âm theo điều kiện.

Nếu x < F thì chùm tia sáng ở phía sau thấu kính một khoảng, và điểm càng lớn thì thấu kính càng ở xa màn hình. Với F ≥ L, chúng ta có x < F với mọi x có thể xảy ra và trong trường hợp này d tối thiểu tại x₀ = L, tức là khi ống kính được lắp gần màn hình. Nếu (L/4) < F < L thì hiển nhiên x₀ > F (chùm tia phải hội tụ). Trong trường hợp này, ảnh nguồn nằm phía sau màn ảnh và cách thấu kính một khoảng y sao cho

$$\frac{1}{x} + \frac{1}{y} = \frac{1}{F},$$

tức là y = $\frac{xF}{x-F}$.

Từ các thông báo tương tự mà chúng tôi thu được (xem hình):

$$\frac{d}{D} = \frac{y - (L-x)}{y},$$

Ở đâu

$$d = D \frac{y - (L-x)}{y} = D \left(1 - \frac{(L-x)(x-F)}{xF}\right) = D \left(2 \sqrt{\frac{L}{F}} - \frac{L}{F} + \left(\sqrt{\frac{L}{x}} - \sqrt{\frac{x}{F}}\right)^2\right).$$

Biểu thức này có giá trị tối thiểu tại x = x₀ = $\sqrt{LF}$ và

$$d_{\min} = D \sqrt{\frac{L}{F}} \left(2 - \sqrt{\frac{L}{F}}\right).$$

Do đó, kích thước điểm là tối thiểu tại x₀ = L, nếu F ≥ L, tại x₀ = $\sqrt{LF}$, nếu F < L.

D. Yu. Grigoriev

Sửa đổi
Trên trang bìa thứ tư của «Kvant» số 6, tên tác giả của chương trình được ghi không chính xác. Tác giả của chương trình này là A. A. Levin.
