---
id: 1974-1-resheniya-zadach-m200-m204-f211-f212-fcd31a1e
issue: kvant_1974_1
year: 1974
number: "1"
title: Lời giải bài toán M200—M204; F211, F212
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 46
page_last: 49
page_labels: 44-47
tag: 97KB
lang: vi
source: kvant_digital
extraction: vision
content_sha256: d3fab102f7fc48c82819d70d9ed0b91aa1a3463858c987f597dcda76e1d8a507
prompt_sha256: draft-1
translated_from: content/ru/1974/01/articles/11_resheniya-zadach-m200-m204-f211-f212-fcd31a1e.md
source_content_sha256: be87316085b7355e243744616885a2c5efc152bde7055219a60f4cef2e9e8af2
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 44⟧

Lời giải bài toán

M200—M204; F211, F212

M200. a) Hình 1 thể hiện sáu thùy, nằm thẳng ba trên bốn. Chứng minh rằng có 24 cách ánh xạ tập hợp sáu thùy này lên chính nó sao cho cứ ba thùy nằm trên cùng một đường thẳng thì ánh xạ thành ba thùy cũng nằm trên cùng một đường thẳng.

b) Trong Hình 2.9, chín thùy nằm trên chín đường thẳng và qua mỗi moka có ba thùy có giá trị lớn nhất là “cấu hình Pascal”. Có bao nhiêu cách ánh xạ tập hợp chín thùy của chúng ta lên chính nó sao cho mỗi ba thùy nằm trên một trong chín thùy được ánh xạ lên ba thùy nằm trên một đường thẳng nào đó từ cấu hình của chúng ta?

b) Câu hỏi tương tự đối với cấu hình Desarada (mười thùy và mười đường thẳng) được hiển thị trong Hình 3.

a) Mọi thứ đều có sẵn 6! = 720 cách ánh xạ một tập hợp sáu điểm lên chính nó. Nhưng không phải tất cả các ánh xạ này đều thỏa mãn các điều kiện bài toán. Sẽ thuận tiện hơn khi tìm ánh xạ trực tiếp cấu hình của chúng tôi. Nếu đối với mỗi đường thẳng trong số bốn đường thẳng của chúng ta, nó được chỉ ra đường thẳng nào mà nó ánh xạ lên, thì ảnh của từng điểm sẽ được xác định (điểm nào trong cấu hình của chúng ta là điểm giao nhau của hai đường thẳng nhất định có trong cấu hình). Một tập hợp bốn đường thẳng có thể được ánh xạ lên chính nó 4! = 24 cách.

b) Lưu ý một trong các cấu hình cay l. Chúng ta hãy biểu thị ba điểm cấu hình nằm trên A, B và C. Sáu đường cấu hình nữa đi qua các điểm này. Phần dư 9 - 1 - 6 = 2 là các đường thẳng không đi qua bất kỳ điểm A, B và C nào. Ta ký hiệu chúng là p và q (Hình 4).

Ánh xạ đường thẳng l vào bất kỳ cấu hình nào trong số chín cấu hình thẳng - lên đường thẳng l1. Điều này có thể được thực hiện theo chín cách khác nhau. Các điểm A, B và C sẽ được ánh xạ lên các điểm A1, B1, C1 nằm trên đường l1. Điều này có thể được thực hiện 3! =

⟦folio 45⟧

và $Y_1$ điểm $X$ và $Y$ phải là giao điểm từng cặp của các đường cấu hình khác với $l_1$ đi qua các điểm $A_1$ và $B_1$ (chứng minh đi!). Tổng cộng có $10 \cdot 6 \cdot 2 = 120$ ánh xạ giao nhau với chúng tôi.

Ghi chú. Lưu ý đằng sau dòng chữ “chứng minh” vẫn còn ẩn chứa một phần khá lớn lời giải. Trong các số tiếp theo, chúng tôi sẽ thảo luận về các cách tiếp cận khác đối với lời giải bài toán M200.

A. N. Kolmodorov

**M201. Đường thẳng $l_1$ cắt các cạnh $a$, $b$ và từ tam giác hoặc phần tiếp nối của chúng tại các điểm $A_1$, $B_1$ và $C_1$ giao tuyến trực tiếp tương ứng vẫn là một phần khá lớn lời giải. Trong các số tiếp theo, chúng tôi sẽ thảo luận về các cách tiếp cận khác đối với lời giải bài toán M200.

Chúng ta sẽ giải bài toán bằng cách sử dụng vectơ. Đường dẫn này (cũng như phương pháp tọa độ lời giải) tốt ở chỗ nó cho phép bạn bao quát tất cả các trường hợp bằng một lý luận và không phải lo lắng về cách các đường $l_1$ và $l_2$ được đặt so với một tam giác nhất định.

⟦folio 46⟧

Cơm. 7.

của tôi là $AB$ (Hình 7). Chúng ta phải tìm một điều kiện mà theo đó $B'_1$ trùng với $C_1$, nghĩa là, $\overrightarrow{AB'_1} = \overrightarrow{AC'_1}$ hoặc tương đương,

$$\frac{\overrightarrow{AB'_1}}{\overrightarrow{C'_1B'_1}} = \frac{\overrightarrow{AC'_1}}{\overrightarrow{C'_1C'_1}}$$

(mối quan hệ $\frac{\overrightarrow{AM}}{\overrightarrow{C'_1M}} = k$ được xác định duy nhất bởi vị trí của điểm $M \in (AB)$, vì từ $\frac{\overrightarrow{AM}}{\overrightarrow{C'_1A} + \overrightarrow{AM}} = k$ kéo theo $\overrightarrow{AM} = \frac{k}{1-k} \cdot \overrightarrow{C'_1A}$).

Đẳng thức (3) tương đương với:

$$\frac{\overrightarrow{AC'_1}}{\overrightarrow{C'_1C'_1}} \cdot \frac{\overrightarrow{C'_1B'_1}}{\overrightarrow{AB'_1}} = 1,$$

$$\frac{\overrightarrow{AC'_1}}{\overrightarrow{BC'_1}} \cdot \frac{\overrightarrow{BC'_1}}{\overrightarrow{C'_1C'_1}} \cdot \frac{\overrightarrow{C'_1B'_1}}{\overrightarrow{AB'_1}} = 1,$$

và điều này tương đương với (1).

**M202.** Chứng minh rằng từ dãy $a, a+d, a+2d, \dots, a+nd, \dots$, là một cấp số cộng vô hạn ($d \neq 0$), có thể chọn một dãy là cấp số nhân vô hạn khi quan hệ $a/d$ là hữu tỉ.

Giả sử $a/d$ là hợp lý: rất indo, chúng ta có thể giả sử rằng $a$ và $d$ cùng dấu. Sau đó

$$\frac{a}{d} = \frac{s}{r},$$

trong đó $s$ và $r$ là số tự nhiên. Khi đó, với mọi số nguyên không âm $m$, số $(1+r)^m-1$ chia hết cho $(1+r)-1=r$, do đó số đó

$$n_m = \frac{a(1+r)^m-a}{d} =$$

$$= s \frac{a(1+r)^m-a}{sd} = s \frac{(1+r)^m-1}{r}$$

—số nguyên và không âm; do đó, mỗi số hạng của cấp số nhân $a(1+r)^m$, $(m=0,1,2,\dots)$ có dạng

$$a(1+r)^m = a + n_m d,$$

nghĩa là nó thuộc về một cấp số cộng.

Ví dụ Cấp số cộng $\frac{1}{5} + \frac{3}{7}n(n=0,1,2,\dots)$, trong đó $\frac{a}{d} = \frac{1.7}{5.3} = \frac{7}{15}$, chứa dãy con $\frac{1}{5} \cdot (15+1)^m = \frac{16}{5}m$ ($m$ là bất kỳ số nguyên không âm nào).

Ngược lại, giả sử cấp số cộng $a+nd$ ($d \neq 0$) chứa ít nhất ba số hạng liên tiếp của cấp số nhân. Hãy để nó là thành viên của cô ấy

$$a+kd, a+ld, a+md \ (k < l < m).$$

Rồi $(a+ld)^2 = (a+kd)(a+md)$, từ đâu

$$a(2l-k-m) = d(km-l^2).$$

Đây $2l-k-m \neq 0$. Thật vậy, nếu $2l-k-m = 0$ thì $km-l^2 = 0$. Nhưng sau đó $(k-m)^2 = (k+m)^2 - 4km = 4l^2 - 4l^2 = 0$, và do đó $k = m$, điều này mâu thuẫn với giả định $k < l < m$.

Do đó quan hệ $\frac{a}{d} = \frac{km-l^2}{2l-k-m}$ là hữu tỉ.

**M203.** a) Chứng minh rằng nếu các hình chiếu giao điểm của các đường chéo $AC$ và $BD$ thỏa mãn thì các giao điểm của ABCD trên các đường thẳng

⟦folio 47⟧

Cơm. 9.

Nối AB, BC, CD và DA nối tiếp bốn đường thẳng (Hình 8), khi đó các đường thẳng này sẽ tiếp xúc với cùng một đường tròn.

6) Viết và chứng minh định lý ngược lại.

Giải bài toán a), ta phải chứng tỏ đường tròn tâm nội tiếp tứ giác KLMN (OK, OL, OM, ON là các đường vuông góc hạ từ điểm O của giao điểm các đường chéo AC và BD với các cạnh AB, BC, CD, DA) là điểm O.

Để chứng minh điều này, chỉ cần chứng minh rằng cả bốn quang phổ của các góc của tứ giác KLMN đều đi qua O. Ta hãy chứng minh điều này cho điểm K (vì cả bốn đỉnh đều ở điều kiện đối xứng hoàn toàn nên điều này đã được chứng minh).

Vì tứ giác AKON và BLOK nội tiếp đường tròn (có đường kính AO và BO tương ứng) và ABCD cũng nội tiếp (theo điều kiện) nên
$$NKO = NAO = DAC = DBC = OBL = OKL.$$
Như vậy, ta đã chứng minh OK là bissertis góc K.

Tuyên bố bài toán được chứng minh tương tự trong trường hợp các hình chiếu rơi vào phần kéo dài của cạnh, nhưng khi đó đường tròn có thể chạm vào các cạnh kéo dài của tứ giác KLMN.

Đối với bài toán b), lời giải của nó hóa ra không rõ ràng. Đây là tất cả những gì về điều này.

Chúng ta coi định lý “nếu Q thì P” là nghịch đảo của định lý “nếu P thì Q” (ở đây P và Q là một mệnh đề). Nhưng hầu hết các định lý có ý nghĩa đều có cấu trúc phức tạp hơn, bao gồm một số yêu cầu riêng lẻ trong “điều kiện” và “kết luận”; ví dụ: “nếu P₁, P₂ và P₃ thì Q₁ và Q₂.” Trong tình huống như vậy, họ thường không chỉ đảo ngược định lý - chẳng hạn như “nếu Q₁ và Q₂ thì P₁, P₂ và P₃”, mà còn soạn thảo các thành phần khác:

"Nếu P₁, P₂, Q₁ và Q₂ thì P₃",

“Nếu giao điểm của các đường chéo của tứ giác lồi ABCD cách đều bốn đường thẳng nối các hình chiếu của nó lên các cạnh kề của tứ giác thì tứ giác ABCD là nội tiếp.

2. Nếu qua các đỉnh K, L, M, N của một tứ giác ngoại tiếp đường tròn tâm O vẽ các đường vuông góc với các đoạn OK, OL, OM, ON của đoạn thẳng tương ứng thì tứ giác KLMN ngoại tiếp đường tròn tâm O thì ABCD nội tiếp được trong đường tròn và tâm đường tròn trùng với P.

3. Gọi K, L, M, N là các hình chiếu giao điểm P của các đường chéo AC và BD của tứ giác lồi ABCD lên các cạnh AB, BC, CD, DA. Nếu tứ giác KLMN ngoại tiếp đường tròn tâm O thì ABCD nội tiếp được trong đường tròn và tâm đường tròn trùng với P.

Một số độc giả xây dựng định lý mạnh hơn - 2 hoặc 3 và chứng minh định lý yếu hơn - 1 (nghĩa là họ âm thầm cho rằng tâm O và giao điểm của các đường chéo AC và BD phải trùng nhau). Ta sẽ chứng minh 2 và 3.

2. Ta ký hiệu các điểm giao nhau của các đường vuông góc với hai cạnh OK, OL, OM, ON (Hình 9) bằng A, B, C, D. Dựa vào việc các tứ giác AKON, BLOK, CMOL, DNOM nội tiếp, dễ dàng chứng minh rằng mỗi tứ giác có cùng chữ cái α, β, γ, δ là bằng nhau. Sau đó, rõ ràng là α + β + γ + δ = BAD + BCD = ABC + ADC.

Tư thế ABCD - ghi. Kế tiếp,
$$AOC = \left(\frac{\pi}{2} - \beta\right) + \left(\frac{\pi}{2} - \delta\right) + \left(\frac{\pi}{2} - \alpha\right) + \left(\frac{\pi}{2} - \gamma\right) = \pi,$$
đặt đường thẳng A + C > D + B. Sau đó, ta chứng minh KLMN không miêu tả được, tức là các góc bissertis K, L, M, N không cắt nhau tại một điểm. Cụ thể, chúng ta sẽ chứng minh bissertis của các góc K và N cắt nhau bên trong AKPN (tương tự bissertis của các góc L và M cắt nhau bên trong CMPL).
