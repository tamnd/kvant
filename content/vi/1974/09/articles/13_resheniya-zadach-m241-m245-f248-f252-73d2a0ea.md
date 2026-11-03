---
id: 1974-9-resheniya-zadach-m241-m245-f248-f252-73d2a0ea
issue: kvant_1974_9
year: 1974
number: "9"
title: Lời giải bài toán M241—M245; F248—F252
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 46
page_last: 51
page_labels: 44-49
tag: RCDS
lang: vi
source: kvant_digital
extraction: vision
content_sha256: ccb9be63cc0387e368687e383d06b551156b00e7a5bbce65be35d386ae486396
prompt_sha256: draft-1
translated_from: content/ru/1974/09/articles/13_resheniya-zadach-m241-m245-f248-f252-73d2a0ea.md
source_content_sha256: 00858984e06aef6a70a99234e56a0f46ed2d324fd78b6901096c0dea9f27dd52
translation_model: draft
translation_run: vi-draft-2026-11-03
translation_quality: draft
---

⟦folio 44⟧

Lời giải bài toán

M241—M245; F248—F252

M241: Hãy để chúng tôi chứng minh điều đó
31974 + 51974
chia hết cho 13.

Tác giả bài toán S.I. Mayzus đã đề xuất một lời giải khá thông minh như vậy. Hãy viết số 31974 + 51974 dưới dạng tổng
(31974 + 21974) + (51974 - 21974)

và chứng minh rằng mỗi dấu ngoặc đều chia hết cho 13.
1°. Với mọi số nguyên a, b và n lẻ, a^n + b^n đều chia cho a + b:
a^n + b^n = (a + b) ×
× (a^{n-1} - a^{n-2} b + ... + b^{n-1}).
Pozotomu
(3^2)^{987} + (2^2)^{987} = 9^{987} + 4^{987}

chia hết cho 13.
2°. Với mọi số nguyên a, b và n tự nhiên, a^n - b^n đều chia cho a - b:
a^n - b^n = (a - b) ×
× (a^{n-1} + a^{n-2} b + ... + b^{n-1}).
Pozotomu
(5^3)^{658} - (2^3)^{658} = 125^{658} - 8^{658}

chia cho 125 - 8 = 117 = 9,13.

Hầu hết độc giả đề xuất lời giải tự nhiên hơn, phù hợp với mọi ví dụ tương tự.

Chúng ta sẽ theo dõi số dư nào cho lũy thừa 3 và 5 khi chia cho 13. Chúng ta hãy biểu thị số dư này của các số 3^n và 5^n lần lượt là r_n và r'_n. Chúng ta luôn tìm được số dư r_n khi chia 3^n cho 13:
$$\frac{n}{r_n} \left| \begin{array}{c c c c} 0 & 1 & 2 & 3 & 4 & 5 & 6 & \dots \\ 1 & 3 & 9 & 1 & 3 & 9 & 1 & \dots \end{array} \right|$$

(Để lập bảng như vậy, bạn không cần chia 3^5, 3^6, ... cho 13: rõ ràng là nếu 3^n - r_n chia hết cho 13 thì 3^{n+1} - 3r_n cũng chia hết cho 13, nên số dư r_{n+1} có thể thu được đơn giản là số dư khi chia 3r_n cho 13.) Do đó, số dư được lặp lại với một khoảng thời gian là 3, và vì năm 1974 chia hết cho 3 nên r_{1974} = r_0 = 1.

Xét số dư thu được khi chia cho 13 số 5^n ta có bảng sau:

$$\frac{n}{r_n} \left| \begin{array}{c c c c c c c c c} 0 & 1 & 2 & 3 & 4 & 5 & 6 & \dots \\ 1 & 5 & 12 & 8 & 1 & 5 & 12 & \dots \end{array} \right|$$

Ở đây chu kỳ là 4 và r'_i = r'_i = 12. Do đó, 31974 có số dư là 12 và tổng của chúng chia cho 13.

Thông tin chi tiết hơn về quy luật xảy ra trong chuỗi số dư a^n (n = 0, 1, 2, ...) khi chia cho số nguyên tố p nào đó được mô tả trong bài viết của S. G. Gindikn “Định lý nhỏ Fermat”, «Kvant» Số 10, 1972.

M242. Gọi $A_i H_i$ là chiều cao và $A_i M_i$ là đường trung tuyến vẽ từ đỉnh $A_i$ của tam giác đảo $A_1 A_2 A_3$ (i = 1, 2, 3). Hãy chứng minh rằng một trong ba tích $|H_1 M_1| \cdot |A_2 A_3| \cdot |H_2 M_2| \cdot |A_3 A_1| \cdot |H_3 M_3| \cdot |A_1 A_2|$ bằng tổng của hai tích còn lại *). Tuyên bố này có đúng với tam giác directlocalhost và mysqllocalhost không?

Hãy chứng minh khẳng định này đúng với mọi tam giác. Chúng ta hãy biểu thị tích $|H_1 M_1| \cdot |A_2 A_3|$ theo độ dài các cạnh $|A_2 A_3| = a_1$, $|A_3 A_1| = a_2$, $|A_1 A_2| = a_3$.

Từ định lý Pythagore áp dụng cho $\triangle A_1 H_1 A_2$ và $\triangle A_1 H_1 A_3$, suy ra rằng (hình 1) $|A_1 H_1|^2 = |A_1 A_2|^2 - |A_2 H_1|^2 = |A_1 A_3|^2 - |A_3 H_1|^2$, từ đó
$|A_2 H_1|^2 - |A_3 H_1|^2 = a_3^2 - a_2^2$.

Chúng ta hãy chứng minh rằng, modulo, hiệu (1) bằng 2 $|H_1 M_1| \cdot |A_2 A_3|$.

Để không xét riêng trường hợp vị trí của điểm H_1 so với các điểm A_2, M_1, A_3, chúng tôi giới thiệu hệ tọa độ trên đường thẳng A_2 A_3. Lấy điểm M_1 làm gốc tọa độ. Cho tọa độ các điểm A_2, A_3 và H_1 tương ứng với

*)Qua |KL| biểu thị độ dài của đoạn có đầu K và L.

⟦folio 45⟧

Hình 3.

bằng $-\frac{a_1}{2}, \frac{a_1}{2}$ và $h_1$ (hình 2). Khoảng cách giữa các điểm có tọa độ $x_1$ và $x_2$ là $|x_2 - x_1|$, vì vậy

$$\left|A_2H_1\right|^2 - \left|A_3H_1\right|^2 = \left|h_1 + \frac{a_1}{2}\right|^2 - \left|h_1 - \frac{a_1}{2}\right|^2 = \left(h_1 + \frac{a_1}{2}\right)^2 - \left(h_1 - \frac{a_1}{2}\right)^2 = 2h_1a_1.$$

Vì $|h_1| = |H_1M_1|$ nên từ (1) và (2) đẳng thức suy ra

$$2|H_1M_1| \cdot |A_2A_3| = |a_3^2 - a_2^2|.$$

Đẳng thức được chứng minh tương tự

$$2|H_2M_2| \cdot |A_3A_1| = |a_1^2 - a_3^2|,$$

$$2|H_3M_3| \cdot |A_1A_2| = |a_2^2 - a_1^2|.$$

Nhưng tổng của ba số $a_3^2 - a_2^2, a_1^2 - a_3^2$ và $a_2^2 - a_1^2$ bằng 0. Do đó, mô hình của một trong số chúng bằng tổng mô hình của hai số còn lại. Điều này ngụ ý tuyên bố bài toán.

(Nếu ký hiệu đỉnh được chọn sao cho $a_1 \geq a_2 \geq a_3$ thì

$$\left|a_1^2 - a_3^2\right| = \left|a_1^2 - a_2^2\right| + \left|a_2^2 - a_3^2\right|$$

và nó sẽ trở thành

$$\left|H_2M_2\right| \cdot |A_3A_1| = |H_1M_1| \cdot |A_2A_3| + |H_3M_3| \cdot |A_1A_2|.$$

N. B. Vasiliev

**M243.** $n$ các đoạn $A_1B_1, A_2B_2, \dots, A_nB_n$ (hình 3) ​​​​được xem xét trên mặt phẳng tối đa, sao cho mỗi đoạn bắt đầu trên một trong hai đường thẳng cho trước, kết thúc trên đường thẳng kia và đi qua điểm $G$ (không nằm trên các đường thẳng này) - tâm của nhiều khối lượng đơn vị đặt tại các điểm $A_1, A_2, \dots, A_n$. Chứng minh rằng

$$\frac{A_1G}{GB_1} + \frac{A_2G}{GB_2} + \dots + \frac{A_nG}{GB_n} = n.$$

Chúng ta sẽ khái quát hóa một chút công thức của bài toán này, cụ thể là, chúng ta sẽ giả sử rằng tại các điểm $A_i$ không có khối lượng đơn vị mà có khối lượng $m_i$ (điểm $G$ là trọng tâm của các khối lượng $m_i$ nằm ở các điểm $A_i$). Vậy hãy chứng minh điều đó

$$\sum_{i=1}^{n} m_i \frac{A_iG}{B_iG} = \sum_{i=1}^{n} m_i.$$

Chúng ta hãy đặt một khối lượng $M_i = m_i \frac{A_iG}{B_iG}$ tại mỗi điểm $B_i$. Khi đó trọng tâm của cặp điểm $B_i$ và $A_i$ (với tất cả $i$) sẽ ở điểm $G$. Chúng tôi giả định rằng không phải tất cả các điểm $A_1, \dots, A_n$ đều nằm trên cùng một đường thẳng (để thuận tiện, chúng tôi biểu thị các đường thẳng của mình bằng các chữ cái $l_1$ và $l_2$). Trọng tâm của điểm $A_i$ nằm trên đường thẳng $l_1$ sẽ được ký hiệu là $C_1$; tương ứng với trọng tâm của điểm $A_i$ nằm trên đường thẳng $l_2$, ký hiệu là $C_2$. Tương tự, trọng tâm của điểm $B_i$ nằm trên đường thẳng $l_k$ ($k = 1, 2$) sẽ được ký hiệu là $D_k$. Chúng ta biểu thị khối lượng tương ứng bằng $P(C_1), P(C_2), P(D_1), P(D_2)$.

Từ điều kiện bài toán suy ra trọng tâm của các điểm $C_1$ và $C_2$ sẽ ở điểm $G$. Mặt khác, từ việc chọn khối lượng $M_i$ suy ra trọng tâm của các điểm $C_1$ và $D_2$ cũng sẽ tại điểm $G$. Vì vậy nó phải là $P(C_2) = P(D_2)$. Tương tự, chúng ta nhận được $P(C_1) = P(D_1)$; Có nghĩa,

$$P(C_1) + P(C_2) = P(D_1) + P(D_2).$$

Nhưng $P(C_1) + P(C_2) = \sum_{i=1}^{n} m_i$ và $P(D_1) + P(D_2)$

$$+ P(D_2) = \sum_{i=1}^{n} M_i$$, tức là

$$\sum_{i=1}^{n} m_i = \sum_{i=1}^{n} M_i = \sum_{i=1}^{n} m_i \cdot \frac{A_iG}{B_iG},$$

Q.E.D.

B. D. Ginzburg

**M244.** Dữ liệu từ tập hợp số thực $n$:

$a_1, a_2, \dots, a_n$ và $b_1, b_2, \dots, b_n$.

Chứng minh rằng nếu thoả mãn ít nhất một trong hai điều kiện:

a) $u_3 a_i < a_j$ theo sau là $b_i \leq b_j$;

b) $u_3 a_i < a_j$, trong đó $a = \frac{a_1 + a_2 + \dots + a_n}{n}$, nó dẫn đến $b_i \leq b_j$,

thì bất đẳng thức đúng

$$n \left(a_1 b_1 + a_2 b_2 + \dots + a_n b_n\right) \geq \left(a_1 + a_2 + \dots + a_n\right) \times \left(b_1 + b_2 + \dots + b_n\right).$$

⟦folio 46⟧

Vì điểm 6) tiếp nối điểm a) nên ta sẽ giải ngay điểm 6).

Giả sử rằng đối với một số giá trị $a_1, a_2, \dots, a_n$ và $b_1, b_2, \dots, b_n$ thì bất đẳng thức

$$n(a_1b_1 + a_2b_2 + \dots + a_nb_n) < (a_1 + a_2 + \dots + a_n) \times (b_1 + b_2 + \dots + b_n).$$

Nếu không phải tất cả $a_i$ đều bằng nhau thì anh ta sẽ tìm $a_i$ và $a_j$ sao cho $a_i < a < a_j$. Xét các số $a$ và $a_i + a_j$ – a; Chúng tôi sẽ thay thế $a_j$ bằng số lớn hơn trong số này và $a_i$ bằng số nhỏ hơn (rõ ràng là trong trường hợp này $a_i$ tăng và $a_j$ giảm và cùng một lượng $\Delta > 0$, vì vậy $a_i^* = a_i + \Delta$, $a_j^* = a_j - \Delta$).

Các bộ mới $\{a_i^*\}, \{b_i\}$ vẫn sẽ thỏa mãn điều kiện bài toán. Nếu trong bộ mới $\{a_i^*\}$ không phải tất cả các số đều giống nhau thì chúng ta sẽ lặp lại hướng dẫn trên một lần nữa. Hãy xác định, v.v. Sau một số hữu hạn các bước, chúng ta nhận được một tập hợp trong đó tất cả các số $\{a_i\}$ đều bằng nhau và bằng $a$. Hơn nữa, vì ở mỗi bước, vế phải của bất đẳng thức (1) không thay đổi $(a_i^* + a_j^*) = a_i + a_j)$ và vế trái giảm $(a_i^*b_i + a_j^*b_j) = (a_i + \Delta)b_i + (a_j - \Delta)b_j = a_i b_i + a_j b_j + \Delta (b_i - b_j) < a_i b_i + a_j b_j$, vì $b_i - b_j < 0$ và $\Delta > 0$, nên đối với tập bất đẳng thức cuối cùng (1) phải được thỏa mãn. Nhưng nếu tất cả $a_i$ đều bằng $a$ thì cả bên trái và bên phải của bất đẳng thức (1) đều giống nhau và bằng $na(b_1 + b_2 + \dots + b_n)$, và điều này mâu thuẫn với giả định của chúng tôi rằng đối với một số giá trị của $\{a_i\}$ và $\{b_i\}$ bất đẳng thức (1) đúng. Như vậy, bài toán lời giải: với mọi giá trị của $\{a_i\}$ và $\{b_i\}$ thỏa mãn điều kiện bài toán thì sẽ có

$$n(a_1b_1 + a_2b_2 + \dots + a_nb_n) \geq (a_1 + a_2 + \dots + a_n) \times (b_1 + b_2 + \dots + b_n).$$

L. G. Limanov

**M245. Chúng tôi đề xuất xây dựng $N$ điểm trên mặt phẳng hoa anh túc sao cho tất cả khoảng cách theo cặp giữa chúng bằng một số xác định trước: với mỗi hai điểm $M_i, M_j$, người ta biết khoảng cách $|M_iM_j| = r_{ij}$ phải bằng bao nhiêu (i và j là bất kỳ số nào từ 1 đến $N$).

a) Có thể dựng được nếu cho khoảng cách $r_{ij}$ sao cho có thể dựng được 5 điểm bất kỳ trong số $N$ không?

b) Biến đổi để có thể xây dựng 4 điểm $N$ bất kỳ có đủ không?

e) Điều gì sẽ thay đổi nếu bạn xây dựng các điểm không phải trên mặt phẳng mà trong không gian? Mô hình nhỏ nhất $K$ mà có thể xây dựng các điểm của bất kỳ $K$ nào từ $N$ điểm đã cho và đảm bảo việc xây dựng tất cả các điểm $N$ là gì?

a) Có thể xảy ra hai trường hợp loại trừ nhau.

1°. Năm điểm bất kỳ trong số $N$ được xây dựng theo yêu cầu bài toán trở thành một đường thẳng: ít nhất ba điểm tạo thành một hình tam giác; đặt đây là các điểm $M_1, M_2$ và $M_3$ (điều này luôn có thể đạt được bằng cách thay đổi cách đánh số các số $r_{ij}$, nếu cần).

Đầu tiên chúng ta hãy xem xét trường hợp tổng quát hơn của 2°. Hãy để chúng tôi chứng minh rằng trong trường hợp 2° tất cả các điểm $N$ đều có thể dựng được. Hãy xây dựng $\Delta M_1M_2M_3$ (sao cho $M_1M_2 = r_{12}, M_1M_3 = r_{13}, M_2M_3 = r_{23}$). Vì, theo điều kiện, năm điểm $N$ bất kỳ có thể được dựng trên mặt phẳng, nên bốn trong số các điểm $N$ thậm chí có thể được dựng nhiều hơn (sao cho khoảng cách giữa chúng bằng một số cho trước).

Lợi dụng điều này, chúng ta sẽ xây dựng điểm tiếp theo $M_4, M_5, \dots, M_N$, đảm bảo khi xây dựng điểm $M_k$ ($4 \leq k \leq N$) chỉ có $M_1M_k = r_{1k}, M_2M_k = r_{2k}$ và $M_3M_k = r_{3k}$.

Chúng ta sẽ có cái tiếp theo.

Bổ đề. Bạn có thể tìm thấy những chủ đề này trên máy bay: $A, B, C$ và $D$; $A, B$ và $C$ không nằm trên cùng một đường thẳng. Hãy để $E$ nêu quan điểm rằng $AE = AD, BE = BD$ và $CE = CD$. Khi đó $E$ nhất thiết phải trùng với $D$.

Bằng chứng. $AE = AD$ và $BE = BD$; Điều này có nghĩa là nếu $E$ và $D$ không trùng nhau thì chúng có tính tương đối đối xứng $AB$. Tương tự, nếu $E$ và $D$ không giống nhau thì chúng là tương đối đối xứng $AC$ (và tương đối $BC$). Vì hai điểm không thể vừa đối xứng vừa tương đối $AB$ và tương đối $AC$, nên nó có nghĩa là $E = D$.

Hãy quay lại lời giải bài toán của chúng tôi.

Theo bổ đề, vị trí của điểm $M_k$ ($4 \leq k \leq N$) luôn được xác định duy nhất. Chúng ta hãy kiểm tra xem các điểm được xây dựng theo cách này có phải là những điểm bắt buộc hay không: với mọi $i$ và $j$ khoảng cách là $M_iM_j = r_{ij}$.

Nếu ít nhất một trong các chỉ số là 1, 2 hoặc 3 thì điều này tuân theo cách xây dựng. Giả sử nó có chỉ số $i$ và $j$, lớn hơn 3. Chúng ta hãy dựng năm điểm $A_1, A_2, A_3, A_4$ và $A_5$ trên mặt phẳng sao cho khoảng cách theo cặp giữa chúng bằng một số cho trước (cụ thể là $A_iA_j = r_{ij}$) - theo điều kiện, điều này có thể thực hiện được. Chúng ta hãy di chuyển điểm $A_1A_2A_3A_4$ sao cho $\Delta A_1A_2A_3$ trùng với $\Delta M_1M_2M_3$ (hai tam giác này bằng nhau). Theo bổ đề, các điểm $A_i$ và $A_j$ trùng với các điểm $M_i$ và $M_j$. Do đó $M_iM_j = r_{ij}$, đó là điều cần chứng minh.

Trong trường hợp 1° (khi bất kỳ năm điểm nào nằm trên cùng một đường thẳng), tất cả các điểm $N$ thậm chí có thể được xây dựng nhiều hơn, vì cách xây dựng, kể từ khi xây dựng, phát biểu:

Giả sử chúng ta cần xây dựng $N$ điểm trên một đường thẳng (sao cho khoảng cách theo cặp

⟦folio 47⟧

giữa chúng bằng một số cho trước $r_{ij}$). Các số $r_{ij}$ được đưa ra sao cho có thể sử dụng bất kỳ số lượng thùy $N$ nào để tạo ra tất cả các thùy $N$.

Khẳng định này được chứng minh hoàn toàn tương tự như trên.

6) Trong trường hợp tổng quát, khả năng dựng bốn điểm bất kỳ không hàm ý khả năng dựng tất cả $N$ điểm. Hãy để chúng tôi đưa ra một ví dụ tương ứng cho $N = 5$.

Đặt $D$ là tâm của tam giác đều $ABC$ (hình 4), $E$ là điểm đối xứng với $D$ đối với $BC$. Hãy đặt $r_{12} = r_{13} = r_{23} = AB$, $r_{14} = r_{24} = r_{34} = r_{15} = r_{25} = r_{35} = AD$, $r_{45} = DE$. Rõ ràng là không thể xây dựng điểm thứ năm $M_1$, ..., $M_5$ sao cho $M_iM_j = r_{ij}$ với tất cả $i$ và $j$: nếu 9 đẳng thức $M_iM_j = r_{ij}$ được thỏa mãn (tất cả ngoại trừ $M_4M_5 = r_{45}$), thì theo Bổ đề $M_4 = M_5$; Điều này có nghĩa là không thể thỏa mãn tất cả 10 đẳng thức cùng một lúc. Đồng thời, có thể xây dựng bốn điểm bất kỳ từ điểm thứ năm: tất cả các điểm ngoại trừ $M_4$ và tất cả các điểm ngoại trừ $M_5$ tạo thành cấu hình $ABCD$; ba điểm "tăng gấp bốn" còn lại tạo thành cấu hình $BDCE$ đến hình. 4.

Trong trường hợp dựng điểm không phải trên mặt phẳng mà trong không gian, số nhỏ nhất $K$ sao cho khả năng dựng điểm bất kỳ $K$ từ $N$ điểm đảm bảo việc dựng tất cả $N$ điểm bằng 100.

Việc sáu dấu chấm là đủ được chứng minh tương tự như ở điểm a). Điểm thứ năm nhỏ theo sau, như ở điểm 6), từ hình 5, trong đó $E$ là tâm của tứ diện đều $ABCD$ và $F$ là một điểm đối xứng với điểm $E$ so với mặt $KBCD$.

M. L. Gerver

F248. Một vòng mềm mỏng có bán kính $R$ với lực rất nhẹ có thể được điều chỉnh tự do quanh trục nằm ngang. Một quả bóng nhỏ được gắn vào vòng, khối lượng của nó bằng khối lượng của vòng. Chu kỳ dao động nhỏ của một cái vòng với một quả bóng. Đối với emod, bạn có thể thử tìm ra một chất tương tự trong chuyển động của một cái vòng với một quả bóng và một nam châm toán học.

Một cách tổng quát để tìm chu kỳ dao động của nam châm là viết phương trình chuyển động của nam châm và sau đó, bằng cách sử dụng mối liên hệ giữa chu kỳ dao động và các hệ số trong phương trình chuyển động, người ta tìm được chu kỳ đó. Trong trường hợp này, chúng ta sẽ phải viết phương trình chuyển động quay của vòng. Tuy nhiên, có một cách khác - so sánh chuyển động của nam châm đang xét với chuyển động của nam châm toán học. Hãy sử dụng phương pháp này.

Rõ ràng, ở vị trí cân bằng của vòng với quả bóng, quả bóng chiếm vị trí thấp nhất và vectơ bán kính nối quả bóng với trục quay là thẳng đứng. Hãy tìm tốc độ của quả bóng tại thời điểm vectơ bán kính tạo một góc $\alpha$ với phương thẳng đứng và so sánh nó với tốc độ của một nam châm toán học khi sợi dây của nó cũng tạo thành một góc $\alpha$ với phương thẳng đứng. Điều tự nhiên là giả sử rằng chiều dài của sợi dây của một nam châm toán học bằng $R$ và độ lệch tối đa so với vị trí cân bằng là như nhau (độ cao $h_0$ đến hình 6, a và 6).

Từ định luật bảo toàn năng lượng suy ra rằng

$$mgh_0 = mgh + \frac{mv^2}{2} + W_{BP},$$

trong đó $mgh + \frac{mv^2}{2}$ là năng lượng của quả bóng và $W_{BP}$ là năng lượng của chuyển động quay của chính cái vòng.

Vì tất cả các điểm của vòng tại mỗi thời điểm đều chuyển động với cùng một tốc độ giá trị tuyệt đối $v$, nên động năng $W_{BP}$ của chuyển động quay của vòng bằng

$$W_{BP} = \frac{mv^2}{2}.$$

Pozny

Và

$$mgh_0 - mgh = 2\frac{mv^2}{2}$$

$$v = \sqrt{g(h_0 - h)}$$.

Trong trường hợp nam châm toán học, chúng ta có:

$$mgh_0 = mgh + \frac{mv^2}{2},$$

⟦folio 48⟧

Ở đâu

$$v = \sqrt{2g(h_0 - h)}$$

Chúng ta thấy rằng đối với bất kỳ vị trí nào của quả bóng (nghĩa là đối với bất kỳ $h$ nào), tốc độ của ma trận, tức là một vòng với một quả bóng, nhỏ hơn $\sqrt{2}$ lần so với tốc độ của ma trận toán học. Điều này có nghĩa là bất kỳ phần nào của quỹ đạo của quả bóng đều trôi qua chậm hơn $\sqrt{2}$ lần so với ma trận toán học, vì tốc độ trung bình trong phần này nhỏ hơn $\sqrt{2}$ lần. Do đó, chu kỳ dao động của ma trận $T_1$ này lớn hơn $\sqrt{2}$ lần chu kỳ dao động của ma trận toán học $T$ và do đó bằng

$$T_1 = \sqrt{2}T = 2\pi \sqrt{\frac{2R}{g}}.$$

F249. Một thanh không trọng lượng, ở đầu có gắn các quả cầu có khối lượng $m$ và $M$, nằm ở giữa trên một giá đỡ cứng, xung quanh nó có thể chuyển động tự do trong mặt phẳng thẳng đứng. Tại thời điểm ban đầu thanh nằm ngang và vận tốc của nó bằng không. Lúc này anh ta đang ấn vào giá đỡ bằng lực nào?

Lực ép lên giá đỡ $F_{\pi}$ bằng tổng lực ép $F_{\pi.1}$ và $F_{\pi.2}$ của các quả bóng trên thanh, vì bản thân thanh không có trọng lượng.

Mỗi quả bóng chịu tác dụng của hai lực: trọng lực và phản lực từ thanh, theo định luật thứ ba.

Newton có độ lớn bằng lực ép của quả bóng lên thanh (hình 7).

Hãy viết phương trình chuyển động của quả bóng:

$$Mg - F_{\pi.1} = Ma,$$

$$F_{\pi.2} - mg = ma.$$

Lưu ý rằng các lực $F_{\pi.1}$ và $F_{\pi.2}$ bằng nhau. Thật vậy, bản thân chuyển động quay của thanh so với trục đi qua tâm của nó là do mô men của các lực $F_{\pi.1}$ và $F_{\pi.2}$, nhưng vì thanh không có trọng lượng nên không cần tốn nhiều sức lực cho chuyển động quay của nó. Do đó, mômen lực $F_{\pi.1}$ và $F_{\pi.2}$ là như nhau. Và vì hai vai bằng nhau nên bản thân các lực cũng bằng nhau.

Do đó, từ (1) và (2), tính đến thực tế là $F_{\pi.1} = F_{\pi.2}$ (vì các lực có độ lớn bằng các lực ép tương ứng), ta thu được

$$F_{\pi.1} = F_{\pi.2} = \frac{2Mmg}{M + m}.$$

F250. Các điện tích giống hệt nhau $q$ nằm ở khoảng cách $a$ và $b$ tính từ quả cầu thay thế có bán kính nhỏ $r$ (hình 8). Khoảng cách đến bề mặt trái đất và các vật thể được thay thế khác lớn hơn nhiều so với $a$ và $b$. Tìm lực do các điện tích tác dụng lên quả cầu.

Dưới tác dụng của các điện tích bên ngoài, một điện tích nhất định $Q$ sẽ được tạo ra trên quả cầu được thay thế

⟦folio 49⟧

sẽ được phân bố tương ứng trên bề mặt của quả cầu. Hãy tìm độ lớn của quả cầu này.

Vì quả cầu được nối đất nên điện thế bề mặt của nó bằng không. Nhưng nếu không có điện tích bên trong vỏ dẫn điện thì ở đó không có điện trường. Do đó, điện thế của bất kỳ điểm nào bên trong quả cầu đều bằng điện thế trên bề mặt của nó, nghĩa là, trong trường hợp của chúng ta, bằng 0.

Đồng thời, theo nguyên lý chồng chất, điện thế trường tại tâm quả cầu (chúng ta sẽ xem xét chính xác điểm này) bằng tổng điện thế trường của các điện tích $q$ và điện tích của quả cầu $Q$:

$$\varphi_0 = 0 = \frac{q}{4\pi\varepsilon_0 a} + \frac{q}{4\pi\varepsilon_0 b} + \varphi_Q.$$

Để tìm thế năng trường của một quả cầu tích điện, thể tích bề mặt của quả cầu được chia thành các diện tích nhỏ sao cho điện tích trên chúng có thể được coi là chính xác. Trường thế ở tâm quả cầu tính từ một diện tích tùy ý bằng

$$\varphi_i = \frac{\Delta Q_i}{4\pi\varepsilon_0 r},$$

trong đó $\Delta Q_i$ là phí của phần này. Rõ ràng, điện thế trường của toàn bộ điện tích $Q$ tại tâm quả cầu sẽ bằng

$$\varphi_Q = \sum \varphi_i = \frac{1}{4\pi\varepsilon_0 r} \sum Q_i = \frac{Q}{4\pi\varepsilon_0 r}.$$

Như vậy,

$$\frac{q}{4\pi\varepsilon_0 a} + \frac{q}{4\pi\varepsilon_0 b} + \frac{Q}{4\pi\varepsilon_0 r} = 0,$$

Ở đâu

$$Q = -qr \left( \frac{1}{a} + \frac{1}{b} \right).$$

Bây giờ không khó để tính lực tác dụng lên quả cầu. Vì bán kính của quả cầu nhỏ so với khoảng cách $a$ và $b$, nên chúng ta có thể giả sử rằng điện tích của quả cầu $Q$ là chính xác và nằm ở tâm của quả cầu. Vì vậy (xem hình 8)

$$F = \sqrt{F_1^2 + F_2^2},$$

Ở đâu

$$F_1 = \frac{Qq}{4\pi\varepsilon_0 a^2} \quad \text{и} \quad F_2 = \frac{Qq}{4\pi\varepsilon_0 b^2}.$$

Thay thế giá trị của điện tích $Q$ tìm được ở trên, cuối cùng chúng ta thu được

$$F = \frac{q^2 r}{4\pi\varepsilon_0} \left( \frac{1}{a} + \frac{1}{b} \right) \sqrt{\frac{1}{a^4} + \frac{1}{b^4}}.$$

F251. Sự hình thành dây đeo của viên đạn (hình 9) thể hiện sóng âm được kích thích khi viên đạn di chuyển. (Có thể đạt được hình dạng như vậy do thực tế là các khu vực có mật độ không khí khác nhau sẽ khúc xạ các tia sáng khác nhau.) Dùng thước, xác định giá trị gần đúng của tốc độ của viên đạn. Tốc độ truyền âm trong không khí là 340 m/s.

Một sóng âm hình cầu lan truyền từ mỗi điểm trên quỹ đạo của viên đạn. Những sóng này cộng lại sẽ cho ra một bức tranh phụ thuộc đáng kể vào mối quan hệ giữa tốc độ của viên đạn và tốc độ âm thanh. Nếu tốc độ âm thanh lớn hơn tốc độ của viên đạn thì các sóng phát ra ở những điểm khác nhau không dám đuổi kịp nhau (hình 10). Nếu tốc độ của viên đạn lớn hơn tốc độ âm thanh, thì các mặt sóng sẽ giao nhau, như thể hiện trong hình 11, và cộng lại, các sóng này sẽ tạo thành các “râu” phân kỳ khỏi viên đạn, tương tự như các “râu” phát ra từ mũi tàu lượn. Những “râu” này đại diện cho lớp vỏ phía trước của sóng âm hình cầu. Hình ảnh tương tự
