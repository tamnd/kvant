---
id: 1976-10-resheniya-zadach-m365-m370-f373-f377-e25cc171
issue: kvant_1976_10
year: 1976
number: "10"
title: Lời giải bài toán M365—M370; F373—F377
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 36
page_last: 47
page_labels: 34, 35, 36, 37, 38, 39, 40, 43, 44, 45
tag: 6CZV
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 1450c6243e32217b4f832ee43c2f92b8230b94b5d872b61866b10a5debfbc112
prompt_sha256: draft-1
translated_from: content/ru/1976/10/articles/11_resheniya-zadach-m365-m370-f373-f377-e25cc171.md
source_content_sha256: 658a8dc4bd7b1079aa599f74aa4fb43bfedb072e4958fb98cd5baa6e2bc9b5f3
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 34⟧

Lời giải bài toán

M365). a) Tổng của nhiều số bằng một. Tổng các khối của chúng có thể lớn hơn một không?
b) Câu hỏi tương tự đối với các số, mỗi số nhỏ hơn một.
c) Có thể chuỗi $a_1 + a_2 + a_3 + \dots$ được mã hóa còn chuỗi $a_1^3 + a_2^3 + a_3^3 + \dots$ thì không?
(Hãy nhớ lại rằng chuỗi $x_1 + x_2 + x_3 + \dots$ được cho là có thể thu gọn nếu dãy số $S_n = x_1 + x_2 + \dots + x_n$ có giới hạn.)

Cơm. 1.

M366. Có thể sắp xếp một số hình tam giác trên một mặt phẳng sao cho hai đỉnh của mỗi hình nằm trên các cạnh (nhưng không nằm ở các đỉnh) của các hình tam giác khác không?

M367. Tích của a) ba b) bốn số tự nhiên liên tiếp có thể bằng một số tự nhiên nào đó (hình vuông, hình lập phương, v.v.) không?

*) Bài toán M364 đã được L. Beve giải trong bài “Minigeometry”, xem «Kvant», 1976, số 6, tr. 11.

Đáp số cho cả ba câu hỏi - khẳng định. Hãy để chúng tôi đưa ra những ví dụ cho thấy điều gì đó có thể xảy ra ngẫu nhiên như vậy.

a) Hai số: 2 và -1.

b) Tám số: 4/5, 4/5, -1/10, -1/10, ..., -1/10.

Tổng của chúng là 1 và tổng các lập phương là $2 \cdot (4/5)^3 - 6 \cdot (1/10)^3 = 1,018$. Ví dụ sau đây dựa trên cùng một ý tưởng - so sánh các số dương và cộng các số âm với chúng - với số lượng lớn hơn nhưng với số lượng nhỏ hơn.

b) Hãy làm một loạt bài

$$1 + (-1/2) + (-1/2) + 1/2 + (-1/4) + (-1/4) + (1/2) + (-1/4) + (-1/4) + \dots$$

như sau: sau tổng 1 + (-1/2) + (-1/2), chúng ta đặt 2^3 = 8 tổng $1/2$ + (-1/4) + (-1/4), sau đó 3^3 = 27 tổng $1/3$ + (-1/6) + (-1/6), ..., $n^3$ tổng $(1/n) + (-1/2n) + (-1/2n)$, v.v. Chuỗi này hội tụ và tổng của nó bằng 0, vì tổng $N$ của số hạng đầu tiên, trong đó 3 ($1 + 2^3 + 3^3 + \dots + n^3$) $N \leq 3$ [1 + 2^3 + 3^3 + ... + ($n + 1$)], không lớn hơn $1/(n+1)$ (cụ thể là nó bằng 0 hoặc $1/(n+1)$ hoặc $1/(n+1)$). Hàng hình khối tương ứng phân kỳ. Thật vậy, tổng $n^3$ của các tổng $(1/n)^3 + (-1/2n)^3 + (-1/2n)^3 = 3/4n^3$ bằng $3/4$, nên tổng của 3 số hạng ($1 + 2^3 + \dots + n^3$) đầu tiên của chuỗi bằng $3n/4$.

Tất nhiên, nếu trong điều kiện bài toán tất cả các số được coi là dương thì đáp số đối với cả ba câu hỏi sẽ là số âm.

N. Vasiliev

Điều kiện bài toán không quy định rằng các hình tam giác không được giao nhau và một số độc giả của chúng tôi đã giải được bài toán, xem xét khả năng giao nhau (trong trường hợp này, lời giải tất nhiên trông khá đơn giản). Đối với các hình tam giác không giao nhau đáp số câu hỏi vẫn khẳng định: Hình 1 cho thấy cách sắp xếp 6 hình tam giác trên một mặt phẳng theo cách yêu cầu.

B. Kolosov

a) Giả sử rằng $k(k+1)(k+2)=u^n$, $n>1$. Số $k+1$ là số nguyên tố cùng nhau với các số $k$ và $k+2$; do đó $k+1=m^n$, $k(k+2)=k^2+2k=l^n$ (đây là hệ quả của Định lý cơ bản của số học về tính duy nhất của phép phân tích số tự nhiên thành thừa số nguyên tố). Khi đó $(k+1)^2=k^2+2k+1=m^2n$, tức là $(m^2)^n — l^n = 1$, là mâu thuẫn: $(a^n - b^n) = (a - b)(a^{n-1} + a^{n-2}b + \dots + b^{n-1}) \neq 1$. Điều này có nghĩa là tích của ba số tự nhiên liên tiếp không thể là lũy thừa của một số tự nhiên.

b) Hãy chứng minh rằng trong trường hợp này đáp số âm. Chúng ta hãy giả sử điều ngược lại: chúng ta hãy giả sử điều đó đối với một số $k(k+1)(k+2)=u^n$.

⟦folio 35⟧

Cách lập luận sẽ giống như trong nhiệm vụ a): chúng ta xây dựng hai số gần nhau, mỗi số đó phải là lũy thừa thứ $n$ và một phương pháp mâu thuẫn. Khoảng cách là riêng biệt cho $n = 2$ và $n \ge 3$.

Tôi. $n = 2$. Chúng tôi có $(k^2 + 3k)(k^2 + 3k + 2) = u^2$. Ký hiệu $k^2 + 3k + 1$ bằng $y$, ta thu được đẳng thức $y^2 - 1 = u^2$, điều này không thể xảy ra đối với các số tự nhiên $u$ và $y$.

II. $n \ge 3$. Lưu ý rằng số $k + 1$ hoặc $k + 2$ là số nguyên tố cùng nhau với ba số còn lại.

1) Cho số $k + 1$ nguyên tố cùng nhau với $k$, $k + 2$ và $k + 3$. Sau đó (xem lời giải của điểm a)) $k + 1 = m^n$, $k(k + 2)(k + 3) = l^n$. Chúng tôi có $k = m^n - 1$, $k + 2 = m^n + 1$, $k + 3 = m^n + 2$; có nghĩa là $(m^n - 1)(m^n + 1)(m^n + 2) = m^{3n} + 2m^{2n} - m^n - 2 = l^n$. Bởi vì $m \ge 2$ và $n \ge 3$, $2m^{2n} - m^n - 2 > 0$, tức là $l^n > (m^3)^n$ hoặc $l > m^3$. Mặt khác, $(m^3 + 1)^n > m^{3n} + nm^{3n-3} > m^{3n} + 2m^{2n} - m^n - 2 = l^n$, từ đâu $l < m^3 + 1$. Vì vậy phải có $m^3 < l < m^3 + 1$, điều này là không thể đối với các chất tự nhiên $m$ và $l$.

2) Nếu số $k + 2$ là số nguyên tố cùng nhau với $k$, $k + 1$ và $k + 3$ thì $k + 2 = m^n$ và $k(k + 1)(k + 3) = l^n$ hoặc $(m^n - 2)(m^n - 1)(m^n + 1) = l^n$, tức là $l^n = m^{3n} - 2m^{2n} - m^n - 2 = l^n$, từ đó $l < m^3 + 1$. Vì vậy phải có $m^3 < l < m^3 + 1$, điều này là không thể đối với $m$ và $n$. Vì vậy, $l < m^3$.

Bây giờ chúng ta hãy so sánh $l$ và $m^3 - 1$. Để làm điều này, chúng tôi lưu ý những điều sau đây. Vì $m^3 > 4$, chúng ta có $m^{3n-3} > 4m^{3n-6}$; và $3n - 6 \ge n$ kể từ $n \ge 3$. Do đó $m^{3n-3} > 3m^{3n-6} + m^n$. Bây giờ chúng ta hãy ước tính sự khác biệt giữa $(m^3)^n$ và $(m^3 - 1)^n: (m^3)^n - (m^3 - 1)^n = m^{3n-3} + m^{3n-6} (m^3 - 1) + m^{3n-9} (m^6 - 2m^3 + 1) + \dots + (m^3 - 1)^{n-1} > 3m^{3n-3} - 3m^{3n-6} > 2m^{3n-3} + m^n > 2m^{2n} + m^n - 2 = (m^3)^n - l^n$.

Do đó $(m^3 - 1)^n < l^n$, tức là $m^3 - 1 < l < m^3$, không thể xảy ra, vì $m$ và $l$ là tự nhiên.

Mâu thuẫn thu được chứng tỏ giả định của chúng ta: tích của bốn số tự nhiên liên tiếp không thể bằng lũy ​​thừa của một số tự nhiên.

D. Fleishan

M368. Chứng minh rằng giao điểm của ba hình trụ tròn bên phải có bán kính 1, có mô tả vuông góc với nhau theo từng cặp (nhưng không nhất thiết phải giao nhau), nằm trong một quả cầu có bán kính nhất định $\sqrt{3}/2$

Chức năng không gian được thảo luận trong bài tập, giao điểm của ba hình trụ, khá khó hình dung. Nhưng điều này là không cần thiết: ​​bài toán lời giải rất đơn giản, nếu bạn dịch nó sang ngôn ngữ đại số - hãy sử dụng phương pháp tọa độ.

Hãy chọn hệ tọa độ như sau: dựng một hình song song thẳng có ba cạnh đi dọc theo trục của các hình trụ (để làm được điều này, bạn cần vẽ hai mặt phẳng qua trục của mỗi hình trụ, song song với trục của hai hình trụ còn lại); Hãy đặt gốc tọa độ ở trung tâm của hình bình hành này và hướng các trục song song với các cạnh của nó (Hình 2). Khi đó, nếu điểm $(x, y, z)$ thuộc phần bên trong của hình trụ thì các bất đẳng thức đúng

$$(x - a)^2 + (y + b)^2 \leq 1, (y - b)^2 + (z + c)^2 \leq 1, (z - c)^2 + (x + a)^2 \leq 1$$

(2a, 2b và 2c là độ dài các cạnh của hình song song được xây dựng). Cộng các bất đẳng thức này, đối với các điểm bên trong $(x, y, z)$ giao điểm của các hình trụ, ta thu được

$$(x^2 + y^2 + z^2) + (a^2 + b^2 + c^2) \leq 3/2,$$

tức là $x^2 + y^2 + z^2 \leq 3/2$, là điều cần chứng minh.

Cơm. 2.

N. Vasiliev

⟦folio 36⟧

M369. Cho tam giác ABC nhọn. O là giao điểm các đường cao của nó, $\omega$ là đường tròn có tâm O nằm bên trong tam giác này. Dựng tam giác $A_1B_1C_1$ ngoại tiếp đường tròn $\omega$ và nội tiếp tam giác ABC (sao cho $A_1 \in [BC]$, $B_1 \in [AC]$, $C_1 \in [AB]$).

Cơm. 3.

Cơm. 4.

M370. Cho $a, b, c$ là bộ ba của các số dương. Hãy tạo một bản nhạc mới từ họ:
$$|a - b|, |b - c|, |c - a|,$$

Hãy để chúng tôi giới thiệu ký hiệu sau: $\widehat{ABO} = \widehat{ACO} = \alpha = 90^\circ - \widehat{A}$;
$\widehat{BAO} = \widehat{BCO} = \beta = 90^\circ - \widehat{B}$, $\widehat{CAO} = \widehat{CBO} = \gamma = 90^\circ - \widehat{C}$. Giả sử rằng điểm $B_1$ sao cho góc giữa tiếp tuyến $B_1C_1$ vẽ từ nó với đường tròn $\omega$ và đường thẳng $B_1O$ bằng $\beta$ (Hình 3). Hãy vẽ một tiếp tuyến với $\omega$ từ điểm $C_1 - [C_1A_1]$. Hãy chứng minh rằng $B_1A_1$ cũng là một tiếp tuyến, tức là $C_1\widehat{B_1A_1} = 2\beta$. Xét tứ giác $AC_1OB_1$. Một vòng tròn có thể được vẽ xung quanh nó kể từ $C_1AO = C_1B_1O = \beta$. Từ việc tứ giác $AC_1OB_1$ nội tiếp suy ra các góc $OAB_1$ và $OC_1B_1$ bằng nhau, cụ thể là: $OAB_1 = OC_1B_1 = \gamma$. Do đó $B_1\widehat{C_1A_1} = 2\gamma$. Người ta đã chứng minh tương tự rằng một đường tròn có thể được mô tả xung quanh tứ giác $C_1BA_1O$: $OC_1A_1 = OBA_1 = \gamma$. Ngược lại, điều này ngụ ý sự bằng nhau của các góc $C_1BO$ và $C_1A_1O$: $C_1\widehat{BO} = C_1\widehat{A_1O} = \alpha$.

Bây giờ chúng ta xét tứ giác $B_1OA_1C$. Hãy để chúng tôi chứng minh rằng một vòng tròn có thể được mô tả xung quanh nó. Thật vậy, $B_1\widehat{OA_1} = 2\pi - (B_1OC_1 + C_1OA_1) = \alpha + \beta + 2\gamma$, vậy $B_1\widehat{OA_1} + \widehat{C_1} = 2(\alpha + \beta + \gamma) = \pi$. Do đó, các góc $OB_1A_1$ và $OC_1A_1$ bằng nhau khi nội tiếp và phụ bởi cùng một dây $OA_1$: $OB_1A_1 = OCA_1 = \beta$ nên $C_1\widehat{B_1A_1} = 2\beta$. Tương tự, người ta chứng minh rằng $C_1\widehat{A_1B_1} = 2\alpha$, tức là $B_1A_1$ thực sự là một tiếp tuyến (và tam giác $A_1B_1C_1$ là tam giác mong muốn).

Tất cả những gì còn lại là xây dựng một điểm $B_1$ mà từ đó đường tròn $\omega$ sẽ nhìn thấy được một góc $2\beta$. Giả sử rằng tiếp tuyến $B_1C_1$ đã tồn tại. Hãy vẽ bán kính của đường tròn $\omega$ đến điểm tiếp xúc. Nếu bán kính là $r$ thì độ dài của đoạn $B_1O$ là $r/\sin \beta$. Do đó, chúng ta có thể thu được các điểm $B_1$ là kết quả của giao điểm của các cạnh $AC$ của tam giác $ABC$ với đường tròn $C$ có tâm tại điểm $O$ bán kính $r/\sin \beta$.

Điểm $B_1$ nào của giao điểm của đường tròn này với $[AC]$ (có thể có hai, một hoặc không có điểm nào như vậy) tương ứng với tam giác mong muốn $A_1B_1C_1$:

Vì vậy, chúng ta đã tìm ra cách dựng một tam giác $A_1B_1C_1$ có các góc $A_1, B_1, C_1$ lần lượt là $2\alpha, 2\beta$ và $2\gamma$. Hóa ra bài toán của chúng tôi không có lời giải nào khác. Trên thực tế, chúng tôi sẽ chỉ ra rằng từ đỉnh $B_1$ của tam giác mong muốn $A_1B_1C_1$, đường tròn $\omega$ có thể nhìn thấy được ở một góc $2\beta$.

Đặt $B' \in [AC]$ và đặt, ví dụ: $C'B'O < \beta$ ($C'B'$ tiếp tuyến với $\omega$). Hãy vẽ một vòng tròn qua các điểm $A, C'$ và $O$ (Hình 4); thì điểm $B'$ nằm ngoài vòng tròn này và $B'C'O < \gamma$ (hãy chắc chắn rằng điều này đúng). Nếu $A' \in [BC]$ và $C'A'$ tiếp tuyến với $\omega$, thì $B'C'A' < 2\gamma$. Tương tự như vậy, $C'A'B' < 2\alpha$, do đó tổng các góc trong tam giác giả định hiện có $A'B'C'$ (với đỉnh $B'$ không giống với $B_1$) nhỏ hơn $2\alpha + 2\beta + 2\gamma = \pi$ - một mâu thuẫn. Trường hợp $C'B'O > \beta$ cũng được xử lý tương tự.

D.Izaak

a) Hãy chứng minh rằng trong trường hợp này số 0 chắc chắn sẽ xuất hiện trong dãy các rãnh. Chúng ta hãy biểu thị số lớn nhất trong bộ ba đầu tiên $(a, b, c)$ bằng $m$. Rõ ràng rằng số lớn nhất trong mỗi bộ ba tiếp theo ít nhất là

⟦folio 37⟧

rồi từ bộ ba này, theo các quy tắc tương tự, bộ ba tiếp theo, v.v. Trung bình của các số thu được theo cách này có nhất thiết phải bằng 0 nếu các số ban đầu là a) số nguyên; b) hợp lệ?

F373. Hai quả bóng lớn, trong đó một quả lúc đầu sẽ đứng yên, chịu va chạm “xiên” đàn hồi hơn. Đường đi qua tâm của các quả bóng khi va chạm tạo thành một góc 60° so với hướng chuyển động ban đầu của quả bóng va chạm. Trong quá trình va chạm, quả bóng bị biến dạng, một phần động năng của quả bóng va chạm biến thành thế năng biến dạng đàn hồi của các quả bóng, khi các quả bóng tách ra sẽ lại chuyển thành động năng. Xác định phần năng lượng cực đại của quả cầu chuyển thành năng lượng biến dạng đàn hồi khi va chạm. Những quả bóng được coi là những cái đầu tuyệt đối.

Cơm. 5.

1 nhỏ hơn số trước, vì vậy số tối đa trong bộ ba thứ hai không quá m-1, trong bộ ba thứ ba - không quá m-2, v.v. Điều này không thể tiếp tục lâu: không muộn hơn trong bộ ba thứ m số lớn nhất bằng không.

6) Hãy để chúng tôi đưa ra một ví dụ cho thấy rằng 0 có thể không xảy ra trong bất kỳ bộ ba nào. Hãy bắt đầu với bộ ba ($\lambda, \lambda^2, \lambda^3$), trong đó $\lambda$ được chọn sao cho các số trong bộ ba tiếp theo

$$|\lambda^2 - \lambda|, |\lambda^3 - \lambda^2|, |\lambda^3 - \lambda|$$

tỉ lệ với số của ba số đầu tiên. Vì $\lambda^2 - \lambda = \lambda(\lambda - 1), \lambda^3 - \lambda^2 = \lambda^2(\lambda - 1), \lambda^3 - \lambda = (\lambda^2 + \lambda)(\lambda - 1)$, nên đối với điều này, chúng ta lấy $\lambda$ bằng nghiệm dương của phương trình $\lambda^2 + \lambda = \lambda^3$: tức là $\lambda = (1 + \sqrt{5})/2$. Trong trường hợp này, bộ ba thứ $n$ sẽ như sau: $\lambda(\lambda - 1)^{n-1}, \lambda^2(\lambda - 1)^{n-1}, \lambda^3(\lambda - 1)^{n-1}$ (điều này dễ kiểm tra bằng quy nạp), vì vậy không có số nào bằng 0.

Một câu hỏi thú vị nhưng khó hơn: bộ ba số nào khác ($a, b, c$) có tính chất mà dãy phát sinh từ chúng sẽ không chứa số 0? Hãy cố gắng tìm ra nó. Không kém phần thú vị là bài toán tương tự về phép biến đổi của bốn số

$$(a, b, c, d) \rightarrow (|a - b|, |b - c|, |c - d|, |d - a|).$$

N. Vasiliev

Chúng ta hãy biểu thị bằng $v_0$ vận tốc ban đầu của quả bóng thứ nhất (bị va chạm), và bằng $v_1$ và $v_2$ vận tốc của quả bóng thứ nhất và thứ hai tại thời điểm chúng biến dạng tối đa. Theo định luật bảo toàn năng lượng

$$\frac{mv_0^2}{2} = \frac{mv_1^2}{2} + \frac{mv_2^2}{2} + \Pi,$$

trong đó $m$ là khối lượng của mỗi quả bóng, $\Pi$ là giá trị cực đại của thế năng biến dạng đàn hồi của các quả bóng.

Chúng ta hãy giới thiệu hệ tọa độ $XOY$ và tìm hình chiếu của vận tốc $v_1$ và $v_2$ lên các trục tọa độ tương ứng. Hãy hướng trục $OX$ dọc theo đường nối tâm của các quả bóng khi di chuyển ra xa (Hình 5). Theo hướng này, tác động đàn hồi LOB chung sẽ xảy ra giữa các quả bóng. Vì hệ các quả bóng bị cô lập nên hình chiếu động lượng của hệ lên trục $OX$ được bảo toàn. Tại thời điểm ban đầu, hình chiếu này bằng $mv_0 \cos \alpha$. Tại thời điểm khi độ biến dạng của các quả bóng là cực đại thì hình chiếu vận tốc của chúng lên trục $OX$ là như nhau: $v_{1x} = v_{2x} = v_x$.

Từ định luật bảo toàn động lượng

$$mv_0 \cos \alpha = 2mv_x,$$

hoặc

$$v_{1x} = v_{2x} = v_x = \frac{1}{2} v_0 \cos \alpha.$$

Vì các quả bóng hoàn toàn trơn tru nên sự tương tác của chúng dọc theo trục $OY$ không xảy ra. Hình chiếu tốc độ của quả bóng thứ nhất lên trục này không thay đổi:

$$v_{1y} = v_{0y} = v_0 \sin \alpha,$$

và hình chiếu vận tốc của quả bóng thứ hai vẫn bằng 0:

$$v_{2y} = 0.$$

Do đó, định luật bảo toàn năng lượng có thể được viết như sau:

$$\frac{mv_0^2}{2} = \frac{m(v_1^2 + v_2^2)}{2} + \frac{m(v_2^2 + v_1^2)}{2} + \Pi,$$

hoặc

$$\frac{mv_0^2}{2} = \frac{mv_0^2 \cos^2 \alpha}{4} + \frac{mv_0^2 \sin^2 \alpha}{2} + \Pi.$$

⟦folio 38⟧

F374. Dưới đáy ly nước có một số ống mao dẫn bịt kín bằng một đầu và chứa đầy không khí. Đường kính của ống là $d=0,2$ mm, chiều cao của mực nước trong cốc là $h=10$ cm. Khi nước sôi, bọt hơi hình thành ở hai đầu hở của ống. Nhiệt độ của nước ở đáy cốc là bao nhiêu nếu áp suất khí quyển là $10^5$ n/m$^2$? Giả sử hệ số sức căng bề mặt của nước là 57 dynes/cm. Xét rằng áp suất hơi bão hòa của nước lớn hơn 100°C tăng 27 mm pt. Nghệ thuật. khi nhiệt độ tăng thêm 1°.

Từ đây ta tìm được phần động năng của quả cầu tới đã chuyển hóa thành thế năng biến dạng đàn hồi:

$$\frac{\Pi}{mv_0^2/2} = \frac{\cos^2\alpha}{2} = \frac{1}{8}.$$

◆ Một bong bóng hơi vỡ ra khỏi ống tại thời điểm áp suất hơi bão hòa $p_H$ bên trong bong bóng bằng áp suất bên ngoài $p$ trên bong bóng. Áp suất bên ngoài này bao gồm áp suất khí quyển $p_0$, áp suất thủy tĩnh $\rho g$ và áp suất bổ sung $2\sigma/r$ do sức căng bề mặt của chất lỏng gây ra. Ở đây $p_0 = 10^5$ n/m$^2$, $\rho = 10^3$ ke/m$^3$ là mật độ của nước, $\sigma = 57$ dyne/cm là hệ số căng bề mặt của nước và $r$ là bán kính cong của bề mặt chất lỏng tại ống. Tại thời điểm bong bóng tách ra, $r$ bằng bán kính của ống, tức là $r = d/2$.

Như vậy,

$$p_H = p_0 + \rho g h + 4\sigma/d.$$

Áp suất $p_H$ khác với áp suất hơi bão hòa ở 100°C, bằng $p_0$, khoảng $\Delta p = p_H - p_0 = \rho g h + 4\sigma/d \approx 16$ mm rm. cm.

Do đó, nhiệt độ $t$ của nước ở đáy cốc

$$t = 100^\circ C + \frac{16}{27} \cdot 1^\circ C \approx 100,6^\circ C.$$

I. Slobodetsky

◆ Rõ ràng khối thứ hai sẽ bắt đầu chuyển động tại thời điểm lực đàn hồi của lò xo $F_{yпр}$ ở giá trị tuyệt đối bằng giá trị cực đại của lực ma sát tĩnh $\mu m_2 g$ (Hình 6). Khoảng cách giữa khối lông và tìm xem lực đàn hồi của lò xo thay đổi như thế nào khi nó chuyển động. Khối này bắt đầu di chuyển nếu $F > \mu m_1 g$. Khi khối chuyển động, ngoài lực $F$ và lực ma sát $\mu m_1 g$ còn có một lực đàn hồi tác dụng lên nó (xem Hình 6), lực này tăng giá trị tuyệt đối khi khối di chuyển ra khỏi vị trí ban đầu. Do đó, gia tốc của khối sẽ giảm và tại thời điểm $F - \mu m_1 g - F_{yпр} = 0$, nó trở thành 0. Khi đó gia tốc sẽ đổi dấu và hướng theo vận tốc của vật. Tốc độ của khối bắt đầu giảm, đến một lúc nào đó nó sẽ về 0, sau đó khối sẽ di chuyển sang trái (tất nhiên nếu khối thứ hai rời đi).

Rõ ràng là độ biến dạng của lò xo và do đó lực đàn hồi đạt cực đại khi tốc độ của vật bằng không. Và nếu tại thời điểm này lực đàn hồi bằng (chính xác hơn là lớn hơn một chút) lực ma sát tĩnh cực đại giữa khối thứ hai và bề mặt:

$$F_{yпр.max} = \mu m_2 g,$$

 khối thứ hai sẽ bắt đầu di chuyển. Hãy tìm $F_{yпр.max}$.

Cơm. 6.

⟦folio 39⟧

Vì động năng của các thanh tại thời điểm đang xét bằng 0 nên công của các lực $F$ và $\mu m_1 g$ trong toàn bộ thời gian thanh thứ nhất chuyển động sang phải sẽ bằng độ biến thiên thế năng của mồi:

$$\frac{kx_{\text{max}}^2}{2} = (F - \mu m_1 g) x_{\text{max}}.$$

Ở đây $k$ là độ cứng của mảnh ghép, $x_{\text{max}}$ là độ giãn dài tối đa của mảnh ghép. Từ đây

$$F_{\text{упр.max}} = kx_{\text{max}} = 2(F - \mu m_1 g).$$

Do đó, khối thứ hai sẽ di chuyển nếu

$$2(F - \mu m_1 g) = \mu m_2 g,$$

hoặc

$$F = \mu g(m_1 + m_2/2).$$

G. Komkin

F376. Một chiếc đồng hồ cát có đường kính $d$ được để trong một ống thủy tinh có đường kính $D(D \approx d)$, đậy kín và đổ đầy nước. Lúc đầu đồng hồ ở dưới đáy ống. Khi bạn lật ống lại, đồng hồ sẽ vẫn ở trên đầu ống một lúc rồi từ từ hạ xuống. Tìm thời gian đồng hồ ở trên đỉnh ống nếu chiều cao của đồng hồ là $h(h \gg d)$, khối lượng của nó là $M$, khối lượng cát trong đồng hồ là $m$ và hệ số ma sát của đồng hồ với thành ống là $k$. Thời gian chuyển đổi của cát từ mép trên xuống mép dưới của đồng hồ là $t$.

Khi đồng hồ được quay lại, trọng tâm của nó - điểm $C$ trong Hình 7 - nằm phía trên điểm $O$, tại đó lực đẩy Archimedean được tác dụng, và đồng hồ bị "xoắn". Trong trường hợp này, phản lực $N_1$ và $N_2$ và lực ma sát $F_{\text{тр}_1}$ và $F_{\text{тр}_2}$ tác dụng lên đồng hồ từ các thành ống. Khi cát thức dậy, các lực $N_1$ và $N_2$ giảm giá trị tuyệt đối. Khoảnh khắc đồng hồ bắt đầu trượt xuống,

$$F_{\text{тр}_1} = kN_1 \text{ и } F_{\text{тр}_2} = kN_2.$$

Vì đồng hồ không chuyển động theo phương ngang nên $N_1 = N_2 = N$. Kể từ đây,

$$F_{\text{тр}_1} = F_{\text{тр}_2} = kN.$$

Chúng ta biểu thị bằng $t$ thời gian từ lúc lật ống cho đến thời điểm đồng hồ bắt đầu trượt so với ống. Trong thời gian này, $x = \frac{t}{\tau}$ một phần cát thức dậy. Chúng ta hãy tìm vị trí trọng tâm của đồng hồ tại thời điểm $t$. Đồng thời, cần lưu ý rằng ở phía dưới có phần cát thứ $x$, phía trên có phần cát thứ $(1-x)$. Nếu chiều cao của cát là $l$ thì ở dưới cùng có cột cát có chiều cao $xl$ với khối lượng $xm$, và ở trên cùng có cột có chiều cao $(1-x)l$ với khối lượng $(1-x)m$. Để đơn giản, chúng ta sẽ coi các cột này có dạng hình trụ. Khi đó, sử dụng các quy tắc chung, không khó để tìm ra vị trí trọng tâm của đồng hồ:

$$OC = \frac{m}{2(M+m)}(2x^2l - hx + l - 2xl).$$

Giả sử rằng $l = h/4$ (như trong Hình 7), ta thu được

$$OC = \frac{mh}{8(M+m)}(2x^2 - 6x + 1).$$

Bây giờ hãy viết ra các điều kiện cân bằng cho đồng hồ. Thứ nhất, rõ ràng là $F_{\text{тр}_1} + F_{\text{тр}_2} + F_B = (M+m)g$, từ đâu

$$F_{\text{тр}_1} = F_{\text{тр}_2} = \frac{1}{2}[(M+m)g - F_B] = \frac{g}{2}(M+m - \rho V),$$

Và

$$N = \frac{g}{2k}(M+m - \rho V),$$

trong đó $\rho$ là mật độ của nước và $V$ là thể tích của đồng hồ.

⟦folio 40⟧

Ngoài ra, $N_1 \cdot OA \cdot \cos(\alpha + \beta) + N_2 \cdot OB \cdot \cos(\alpha + \beta) + F_{\text{Tp}_1} \times OA \cdot \sin(\alpha + \beta) = F_{\text{Tp}_2} \cdot OB \cdot \sin(\alpha + \beta) + (M + m)g \cdot OC \cdot \sin \alpha$.

Vì $d \approx D$ và góc $\alpha$ đều nhỏ nên

$$OA \cdot \cos(\alpha + \beta) = OA \cdot \cos \beta = h/2, \quad OA \cdot \sin(\alpha + \beta) = OB \cdot \sin(\alpha + \beta) \quad \text{и} \quad OC \cdot \sin \alpha = OC \cdot \mathrm{tg} \alpha = OC \cdot (D - d)/h.$$

Kết quả là, từ đẳng thức (3) chúng ta thu được

$$N = (M + m)g \frac{D - d}{h^2} OC.$$

Thay thế ở đây các biểu thức cho $N$ (từ đẳng thức (2)) và cho $OC$ ( đẳng thức (1)) và giải phương trình thu được cho $x$, chúng ta tìm thấy

$$x = \frac{1}{2} \left(3 - \sqrt{7 + 2a}\right), \quad t = x\tau = \frac{\tau}{2} \left(3 - \sqrt{7 + 2a^2}\right),$$

ở đâu $a = \frac{4h (M + m - \rho V)}{mk (D - d)}$.

I. Slobodetsky

F377. Nếu bạn nheo mắt nhìn những ngọn đèn sáng ở xa, bạn thường thấy những cột ánh sáng thẳng đứng hoặc nghiêng đi xuống từ đèn. Giải thích hiện tượng này. Tạo và thực hiện các thí nghiệm để kiểm tra lời giải thích của bạn.

Manh mối. Bề mặt hoa hồng không bị khô. Nó luôn được bao phủ bởi một lớp nước mắt.

Cơm. 8.

"Dọc theo mép mí mắt, nước mắt tạo thành một sụn nhỏ trong đó các tia sáng bị khúc xạ. Như trong Hình 8, $a$, các tia khúc xạ từ mí mắt trên khiến mỗi tia trở nên hơi xanh và nguồn sáng nhận được một "đuôi" hình thành hướng xuống dưới. Tương tự như vậy, một "đuôi" sáng xuất hiện ở mí mắt dưới, hướng lên trên. Có thể quan sát rõ sự xuất hiện của những "đuôi" này nếu khi nhắm một mắt, từ từ nhắm mắt kia lại, hoặc nâng và hạ đầu, giữ cả hai mắt nhắm một nửa. Các tia sáng xuất hiện vào đúng thời điểm mí mắt bắt đầu nhắm lại, người cận thị rất dễ nhận thấy điều này, vì nguồn sáng đối với anh ta như một vòng tròn mờ, lúc này bị che khuất một phần.

Các tia không hoàn toàn song song, ngay cả khi chỉ nhìn bằng một mắt. Nhìn thẳng vào nguồn sáng, sau đó hơi quay đầu sang phải và đảo mắt sao cho nguồn sáng này quay trở lại. Bây giờ các tia được định hướng xiên (Hình 8, 6). Nguyên nhân có vẻ là do mép mí mắt, nơi giao nhau với đồng tử, không còn nằm ngang nữa và mỗi tia tia đều nằm vuông góc với mép mí mắt. Hướng biểu kiến ​​của các tia phù hợp với lời giải thích này. Bây giờ bạn có thể hiểu tại sao các tia không song song nếu bạn nhìn thẳng về phía trước: độ cong của mí mắt ảnh hưởng ngay cả với chiều rộng đồng tử nhỏ (Hình 8, 8). Dùng ngón tay đóng mép phải của đồng tử lại, các tia nằm ở bên trái sẽ biến mất ”.

Từ cuốn sách “Ánh sáng và màu sắc trong thiên nhiên” của M. Minnarma

⟦folio 43⟧

Đáp số và bình luận câu hỏi 1

a) Tất nhiên, một hàm như vậy tồn tại - xem hình. 3, a và 3, b (Hình 3, b hiển thị đồ thị của đa thức $y = x^4 - x^2$ - hãy xác nhận điều này bằng cách nghiên cứu bằng cách sử dụng một biểu đồ tùy ý).

b) Hoá ra có tồn tại một hàm như vậy! Các đồ thị tương ứng được thể hiện trên Hình 4, a và 4, b: giữa các điểm cực tiểu $x_1$ và $x_2$ của các hàm này có một “ngọn đồi bằng phẳng” - một phần của đồ thị phía trên đoạn $[a_1, a_2]$ trên đó hàm được xây dựng. Tất nhiên, tôi muốn coi slide này bao gồm toàn bộ số điểm tối đa. Tuy nhiên, điểm $x_0 \in [a_1, a_2]$ không phù hợp với định nghĩa của chúng tôi về mức tối đa - mức tối đa “nghiêm ngặt” ($f(x) < f(x_0)$ đối với các điểm $x \neq x_0$ trong vùng lân cận của $(x_0)$. Nhưng chúng là các điểm có mức tối đa không nghiêm ngặt: đối với các điểm $x$ trong một lân cận nào đó của điểm $x_0$ thì bất đẳng thức không nghiêm ngặt $f(x) \leqslant f(x_0)$ được thỏa mãn. Rõ ràng bằng trực giác rằng giữa một liên tục hàm số phải có điểm cực đại—giữa hai đáy phải có ít nhất một ngọn đồi! Điều này đúng, nhưng mức tối đa có thể không nghiêm ngặt.

Khái niệm cực trị không sắc nét (cực đại hoặc cực tiểu) rất thuận tiện, nhưng hơi “mơ hồ”: các điểm của tích phân $|a_1, a_2|$ trong Hình 4, a và 4, b có thể được coi là điểm cực tiểu không sắc nét! Một ví dụ khác: một hàm số có đồ thị như trong Hình 5 nhưng không

⟦folio 44⟧

có cực trị nghiêm ngặt, nhưng điểm $x_1$ là điểm tối đa không nghiêm ngặt đối với nó, $x_2$ là điểm tối thiểu không nghiêm ngặt và tất cả các điểm $x_0$ của khoảng xây dựng $|x_1, x_2|$ đồng thời là điểm tối đa không nghiêm ngặt và tối thiểu không nghiêm ngặt. Phân tích các hàm $y = |x - 1| + |x + 1|$ và $y = |x - 1| - |x + 1|$ theo cách tương tự (đồ thị của chúng tương ứng được hiển thị trong Hình 5, 6 và 5 - hãy kiểm tra!).

Vì vậy, cùng với các khái niệm trường học về mức tối đa và tối thiểu, các khái niệm về mức tối đa và tối thiểu không nghiêm ngặt cũng được chấp nhận trong toán học - tổng quát hơn, “hơi mơ hồ” (xem ở trên), nhưng đôi khi thuận tiện khi xây dựng các định lý. Để làm ví dụ, chúng tôi đưa ra các tuyên bố sau:

Nếu hàm $f$ được xác định và không liên tục trên đoạn $[a, b]$ và chúng ta lấy các giá trị giống nhau ở các đầu của nó, tức là $f(a) = f(b)$, thì tồn tại một điểm $x_1 \in ]a, b[$,

Cơm. 5.

Cơm. 6.

trong đó hàm $f$ có giá trị tối đa hoặc tối thiểu (mặc dù có thể).

Hình 6 ($a, b, \theta$) minh họa định lý này và mức tối đa và tối thiểu được chỉ ra trong hình là nghiêm ngặt.

Câu 3. Nhận xét nêu trên có đúng không nếu mức tối đa và tối thiểu được coi là nghiêm ngặt trong sữa?

Trong sách giáo khoa giải tích toán dành cho học sinh đang học cực đại và cực tiểu, người ta thường hiểu chúng theo nghĩa không chặt chẽ - vì lý do đã nêu ở trên. Ở trường trung học, bạn hầu như phải giải quyết các hàm chỉ có cực đại và cực đại nghiêm ngặt. Đặc biệt, lớp hàm này bao gồm các đa thức và hàm hữu tỉ phân số. Ví dụ, lưu ý rằng đồ thị ở Hình 4, 6 không thể là đồ thị của đa thức thấp hơn (không giống như đồ thị ở Hình 3, 6) - hãy thử chứng minh điều đó!

Đáp số cho câu hỏi 2

a) Các chức năng như vậy tồn tại - ví dụ: “cái cưa” trong Hình 7, $a$ hoặc

⟦folio 45⟧

hình sin - đồ thị $y = \sin x$ (Hình 7, 6).

6) Hóa ra những chức năng như vậy cũng tồn tại. Các điểm cực trị có thể được “cô đọng” sao cho có vô số điểm trên đoạn $|0, 1|$. Ví dụ: trong Hình 8, $a$ tại các điểm $x_n = 1/n$ đối với $n$ chẵn là cực tiểu, đối với lẻ - cực đại. Tuy nhiên, đồ thị 8, $a$ không xác định giá trị của hàm tại $x = 0$. Người ta có thể lấy $f(0) = 0$ hoặc $f(0) = c$, nhưng hàm số như vậy sẽ không liên tục tại điểm $x = 0$: giá trị của $f(x)$ không có xu hướng tiến tới $f(0)$ tại $x \rightarrow 0$. Để thu được hàm liên tục, bạn có thể làm cho các giá trị hàm tại các điểm cực trị $x_n$ có ​​xu hướng tiến tới 0 tại $n \rightarrow \infty$, như trong Hình 8, 6. Nếu sau đó bạn tiếp tục

Cơm. 7.

Cơm. 8.

Nếu chúng ta vẽ biểu đồ như trong hình này thì chúng ta sẽ nhận được một hàm liên tục và xác định ở mọi nơi có vô số cực trị trên khoảng $|0, 1|$ - đáp số (câu hỏi 2, B).

Tất nhiên, các đồ thị tương tự như đồ thị trong Hình 8, $a$ và 8, 6, có thể được thiết lập bằng cách sử dụng các công thức: ví dụ: kiểm tra đồ thị của hàm số là gì

$$y = \sin \frac{1}{x} \left( \text{при } 0 < x \leq \frac{2}{\pi} \right),$$

$$y = \begin{cases} x \sin \frac{1}{x} & \text{при } x \neq 0, \\ 0 & \text{при } x = 0. \end{cases}$$

Bạn không nên nghĩ rằng các chức năng được thảo luận ở câu hỏi 2 là một số loại “ngoại lệ”. Người ta gặp những chức năng tương tự khi nghiên cứu các quá trình khác nhau trong vật lý.

Để kết luận, chúng tôi sẽ hỏi bạn một câu hỏi nữa. Rõ ràng, nếu hàm $x \rightarrow f(x)$ trả về dấu vết từ điểm $x_0$, tức là trong một số khoảng $|x_0 - \delta, x_0|$ và giảm dần về bên phải của điểm này - trong khoảng $|x_0, x_0 + \delta|$, thì $x_0$ là điểm cực đại của hàm $f$ (giải thích!).

Câu 4. Điều ngược lại có đúng không: nếu một hàm số liên tục $f$ đạt cực đại tại điểm $x = x_0$ thì nó trả về vết từ điểm $x_0$ và vết từ $x_0$ giảm?
