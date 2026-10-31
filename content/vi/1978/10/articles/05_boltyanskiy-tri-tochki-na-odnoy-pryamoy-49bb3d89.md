---
id: 1978-10-boltyanskiy-tri-tochki-na-odnoy-pryamoy-49bb3d89
issue: kvant_1978_10
year: 1978
number: "10"
title: Ba điểm trên một đường
authors:
  - Болтянский В. Г.
rubric: osnovnye-stati
page_first: 16
page_last: 21
page_labels: 14, 15, 16, 18, 19
tag: 9WHD
lang: vi
source: kvant_digital
extraction: vision
content_sha256: d60ee0f6a90afd9d54180734d8a3a528695ea48cc8cafdc3829d1ab2d77305fe
prompt_sha256: draft-1
translated_from: content/ru/1978/10/articles/05_boltyanskiy-tri-tochki-na-odnoy-pryamoy-49bb3d89.md
source_content_sha256: fd135da9482f19db1fea38c1339363d60507a75044a0b972c16e857d47adf74c
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 14⟧

Trong bài viết này, chúng ta sẽ xem xét một số bài toán trong đó lời giải hóa ra lại hữu ích khi sử dụng vectơ. Về cơ bản, đây là bài toán, trong đó bạn cần chứng minh ba điểm nào đó nằm trên cùng một đường thẳng, hoặc từ việc ba điểm nào đó nằm trên cùng một đường thẳng, rút ​​ra một số hệ quả nhất định. Định lý chính cho lời giải như vậy bài toán là một định lý nổi tiếng. Điểm C trong cả hai trường hợp đều thuộc đường thẳng AB khi các vectơ $\overrightarrow{AB}$ và $\overrightarrow{AC}$ thẳng hàng (tức là có một số $k \in R$ sao cho $\overrightarrow{AC} = k\overrightarrow{AB}$).

Vì vậy, để chứng minh rằng ba điểm A, B và C thuộc về một đường thẳng, chỉ cần đảm bảo rằng có một số $k$ mà $\overrightarrow{AC} = k\overrightarrow{AB}$ là đủ. Số $k$ tương ứng với $\overrightarrow{AC} = k\overrightarrow{AB}$ có (tại $A \neq B$) ý nghĩa hình học đơn giản: $|k| = \frac{|\overrightarrow{AC}|}{|\overrightarrow{AB}|}$, và $k > 0$ nếu điểm C thuộc tia AB và $k < 0$ nếu nó thuộc tia đối diện.

Ví dụ: nếu C là trung điểm của đoạn AB (Hình 1), thì $\overrightarrow{AC} = \frac{1}{2}\overrightarrow{AB}$; từ đây đến bất kỳ điểm Q nào

$$\overrightarrow{QC} = \frac{1}{2}\overrightarrow{QA} + \frac{1}{2}\overrightarrow{QB}.$$

Hơn nữa, nếu $B$ là trung điểm cạnh MN của tam giác AMN và $C$ là trọng tâm (điểm giao nhau của các đường trung tuyến) của tam giác này thì độ dài đoạn AC là $\frac{2}{3}$ độ dài đoạn AB (Hình 2): $\overrightarrow{AC} = \frac{2}{3}\overrightarrow{AB}$; vì với bất kỳ điểm Q nào đẳng thức $\overrightarrow{QB} = \frac{1}{2}\overrightarrow{QM} + \frac{1}{2}\overrightarrow{QN}$ giữ nguyên, chúng ta có thể kết luận rằng

$$\overrightarrow{QC} = \frac{1}{3}\overrightarrow{QA} + \frac{1}{3}\overrightarrow{QM} + \frac{1}{3}\overrightarrow{QN}.$$

Cuối cùng, một nhận xét nữa: nếu các vectơ $\vec{a}$ và $\vec{b}$ không thẳng hàng thì từ sự tương ứng

$$\vec{ka} + \vec{lb} = \vec{ma} + \vec{nb}$$

theo sau là $k = m$ và $l = n$. Thật vậy, đẳng thức này có thể viết lại dưới dạng

$$(k - m)\vec{a} = (n - l)\vec{b};$$

nếu bây giờ $k \neq m$ thì $\vec{a} = \frac{n - l}{k - m}\vec{b}$, điều này mâu thuẫn với tính không cộng tuyến của các vectơ $\vec{a}$ và $\vec{b}$. Do đó, $k = m$ và tương tự, $l = n$.

Đó là tất cả sự gần đúng "lý thuyết". Bây giờ chúng ta hãy xem xét bốn ví dụ.

Ví dụ 1. Biết rằng trung điểm hai đáy của hình thang và giao điểm của các đường chéo của nó nằm trên cùng một đường thẳng. Bây giờ chúng ta hãy chứng minh định lý “nghịch đảo” trong một số trường hợp: nếu điểm A của giao điểm của đường chéo

⟦folio 15⟧

Hình 2.

biệt danh MNPQ và B giữa, Với sự ủng hộ của nó
Vì các cạnh đối diện MN và PQ nằm trên cùng một đường thẳng nên MNPQ là hình thang hoặc hình bình hành (Hình 3).

Bằng chứng. Hãy đặt $\vec{a} = \vec{AM}$, $\vec{b} = \vec{AN}$. Khi đó $\vec{AP} = k\vec{a}$ (vì các điểm A, M, P nằm trên cùng một đường thẳng) và theo cách tương tự, $\vec{AQ} = l\vec{b}$. Vì B là trung điểm của đoạn MN nên

$$\vec{AB} = \frac{1}{2}\vec{AM} + \frac{1}{2}\vec{AN} = \frac{1}{2}\vec{a} + \frac{1}{2}\vec{b}.$$

Hoàn toàn giống nhau

$$\vec{AC} = \frac{1}{2}\vec{AP} + \frac{1}{2}\vec{AQ} = \frac{k}{2}\vec{a} + \frac{l}{2}\vec{b}.$$

Theo điều kiện, các điểm A, B, C cùng nằm trên một đường thẳng nên tồn tại số m sao cho $\vec{AC} = m\vec{AB}$, tức là

$$m\left(\frac{1}{2}\vec{a} + \frac{1}{2}\vec{b}\right) = \frac{k}{2}\vec{a} + \frac{l}{2}\vec{b}.$$

Do tính phi tuyến tính của vectơ $\vec{a}$ và $\vec{b}$ nên dẫn đến $m = k = l$.

Cuối cùng, chúng tôi có

$$\vec{MN} = \vec{b} - \vec{a}, \vec{PQ} = l\vec{b} - k\vec{a} = k(\vec{b} - \vec{a}),$$

nghĩa là, $\vec{PQ} = k\vec{MN}$. Do đó, $(PQ) \parallel (MN)$, tức là $MNPQ$, là hình thang hoặc hình bình hành.

Quét. Trên Hình 3, các điểm A, M, N, P, Q được đặt sao cho các số k và l âm. Tuy nhiên, trong lời giải chủ đề này không được sử dụng. Vì vậy, lý giải trên có thể áp dụng mà không có bất kỳ thay đổi nào đối với trường hợp các số k và l dương. Trường hợp này được mô tả trong Hình 4. Như vậy, chúng ta đã “miễn phí” nhận được chứng minh định lý sau: nếu điểm A, tại đó phần kéo dài của các cạnh NQ và MP của hình thang MNQP cắt nhau, và các trung điểm B, C của các cạnh MN và PQ cùng nằm trên một đường thẳng thì hình thang MNQP là hình thang. Chúng tôi cũng mời người đọc thấy rằng các lập luận trên diễn ra (hầu như không thay đổi) theo thứ tự ngược lại. Điều này đưa ra một chứng minh vectơ của các định lý “trực tiếp” tương ứng: trong mọi hình thang, trung điểm của hai đáy và giao điểm của các đường chéo nằm trên cùng một đường thẳng; trong bất kỳ hình thang nào, trung điểm của các đáy và giao điểm của phần kéo dài của các cạnh bên nằm trên cùng một đường thẳng (nói cách khác, cả bốn điểm chỉ đều nằm trên cùng một đường thẳng).

Ví dụ 2. Về phía ON của hình bình hành AMNO và trên đường chéo của nó

⟦folio 16⟧

Hình 4.

Các aeonals OM cũng lấy các điểm B và C, lần lượt là $\overrightarrow{OB} = \frac{1}{n} \overrightarrow{ON}$ và $\overrightarrow{OC} = \frac{1}{n+1} \overrightarrow{OM}$ (Hình 5). Chứng minh rằng các điểm A, B, C thẳng hàng.

Lời giải. Hãy đặt $\overrightarrow{AB} = \vec{a}$, $\overrightarrow{ON} = \vec{b}$. Sau đó

$$\overrightarrow{AC} = \overrightarrow{AO} + \overrightarrow{OC} = \overrightarrow{AO} + \frac{1}{n+1} \overrightarrow{OM};$$

$$\overrightarrow{AO} = \overrightarrow{AB} - \overrightarrow{OB} = \vec{a} - \frac{1}{n} \vec{b};$$

$$\overrightarrow{OM} = \overrightarrow{ON} - \overrightarrow{AO} = \vec{b} - \left( \vec{a} - \frac{1}{n} \vec{b} \right) = \frac{n+1}{n} \vec{b} - \vec{a},$$

đó là

$$\overrightarrow{AC} = \left( \vec{a} - \frac{1}{n} \vec{b} \right) + \frac{1}{n+1} \left( \frac{n+1}{n} \vec{b} - \vec{a} \right) = \frac{n}{n+1} \vec{a},$$

hoặc $\overrightarrow{AC} = \frac{n}{n+1} \overrightarrow{AB}$. Từ đó suy ra các điểm A, B, C cùng nằm trên một đường thẳng.

Ghi chú. Trong lời giải người ta chưa bao giờ nói rằng $n$ là số tự nhiên. Lý giải trên cho thấy ở đây $n$ có ​​thể là bất kỳ số thực nào ngoài 0 và -1 (trong ký hiệu của phân số có biểu thức $n$ và $n+1$).

Hình 5 thể hiện trường hợp $n = 4$ (điểm B cắt đi 1/4 cạnh ON và điểm C cắt đi 1/5 đường chéo OM). Nếu đặt $n = -m-1$ thì chúng ta sẽ có $\frac{1}{n} = -\frac{1}{m+1}, \frac{1}{n+1} = -\frac{1}{m}$, tức là

$$\overrightarrow{OB} = -\frac{1}{m+1} \overrightarrow{ON}, \overrightarrow{OC} = -\frac{1}{m} \overrightarrow{OM}.$$

Hình 6 thể hiện trường hợp khi $m = 3$ (trên phần tiếp theo của mặt ON, một phần tư cạnh bị lệch khỏi điểm O và trên phần tiếp theo của đường chéo, phần tư thứ ba MNP). Trên các đường thẳng MN, NP, PM lấy các điểm A, B và C:

$$\overrightarrow{MA} = \alpha \overrightarrow{AN}, \overrightarrow{NB} = \beta \overrightarrow{BP},$$

$$\overrightarrow{PC} = \gamma \overrightarrow{CM}.$$

Chứng minh rằng nếu $\alpha \beta \gamma = -1$ thì các điểm A, B, C thẳng hàng (định lý Menelaus).

Bằng chứng. Hãy đặt $\overrightarrow{AN} = \vec{a}, \overrightarrow{BP} = \vec{b}, \overrightarrow{CM} = \vec{c}$.

Sau đó

$$\overrightarrow{MA} = \alpha \vec{a}, \overrightarrow{NB} = \beta \vec{b}, \overrightarrow{PC} = \gamma \vec{c}.$$

Các vectơ $\overrightarrow{AB}$ và $\overrightarrow{AC}$ rất dễ biểu diễn

⟦folio 18⟧

Hình 8.

Vì $\overrightarrow{AB} = \overrightarrow{AO} - \overrightarrow{BO}$ và $\overrightarrow{AB} = \overrightarrow{CB} - \overrightarrow{CA}$, chúng ta nhận được
$$\overrightarrow{b} - \overrightarrow{a} = x(\beta \overrightarrow{b} - \overrightarrow{a}) - y(\alpha \overrightarrow{a} - \overrightarrow{b}),$$
đó là
$$(x + \alpha y - 1)\overrightarrow{a} - (y + \beta x - 1)\overrightarrow{b} = 0.$$

Do vectơ $\overrightarrow{a}$ và $\overrightarrow{b}$ không thẳng hàng nên các hệ số ở vế trái của đẳng thức cuối cùng phải bằng 0, tức là
$$\begin{cases} x + \alpha y = 1, \\ \beta x + y = 1. \end{cases}$$

Giải hệ phương trình này, ta tìm được đáp số:
$$x = \frac{1 - \alpha}{1 - \alpha\beta}, \quad y = \frac{1 - \beta}{1 - \alpha\beta}.$$

Nhiệm vụ và

1. Các điểm $A, B, C, M$ và $N$ không nằm trên cùng một đường thẳng được đặt sao cho các tia $AM$ và $BN$ song song và ngược chiều nhau; $|AC| = p, |BC| = q, |AB| = p + q$. Để có sự tương ứng giữa độ dài của các đoạn $AM$ và $BN$ thì các điểm $M, N$ và $C$ nằm trên cùng một đường thẳng?

2. Các đường $a$ và $b$ song song với nhau. Trên dòng $a$ ta lấy điểm tùy ý $A_1, A_2, A_3$, trên dòng $b$ ta lấy điểm tùy ý $B_1, B_2, B_3$. Trên các đoạn $A_1B_1, A_2B_2, A_3B_3$, chúng tôi cũng lấy điểm $C_1, C_2, C_3$, tức là $|A_1C_1| = \alpha |A_1B_1|, |A_2C_2| = \alpha |A_2B_2|, |A_3C_3| = \alpha |A_3B_3|$. Chứng minh rằng các điểm $C_1, C_2, C_3$ nằm trên cùng một đường thẳng.

3. Các điểm $M, N, P$ đối xứng với điểm $O$ so với cạnh của tam giác $ABC$. Chứng minh rằng điểm $O$ và tâm của tam giác $ABC$ và $MNP$ cùng nằm trên một đường thẳng.

4. Điểm $A, B, C$ là tâm của tam giác $OMN, ONP, OMP$. Chứng minh rằng tâm của các tam giác là $BCD, ACD, ABD, ABC$. Chứng minh rằng các đoạn $AA_1, BB_1, CC_1, DD_1$ cắt nhau tại một điểm $M$ và điểm $M$ cắt đoạn thứ tư của mỗi đoạn này. Thực hiện theo các bản vẽ cho các lớp phẳng và không gian.

⟦folio 19⟧

10. Hình 10.

11. Chứng minh rằng nếu giao điểm các đường trung bình của tứ giác ABCD thuộc đường chéo AC thì đường chéo BD chia đôi đường chéo AC. Định lý ngược lại có đúng không?

12. Cho tam giác MNP. Các điểm A, B, C cũng lấy trên các đường thẳng MN, NP, PM bằng $\overrightarrow{MA} = \alpha \overrightarrow{AN}, \overrightarrow{NB} = \beta \overrightarrow{BP}, \overrightarrow{PC} = \gamma \overrightarrow{CM}$. Chứng minh rằng nếu $\alpha \beta \gamma = 1$ thì các đường thẳng MB, NC và PA cắt nhau tại một điểm (định lý Ceva).

13. Các đoạn $A_1A_4$ và $D_1D_4$ (nằm tùy ý trong không gian) được chia thành ba phần tắc nghẽn của mỗi điểm $A_2$, $A_3$ và lần lượt là $D_2$, $D_3$ (Hình 10). Điểm $B_i$ và $C_i$ chia đoạn $A_iD_i$ thành ba phần tắc nghẽn ($i = 1, 2, 3, 4$). Chứng minh rằng điểm $B_1, B_2, B_3, B_4$ nằm trên cùng một đường thẳng và điểm $C_1, C_2, C_3, C_4$ nằm trên cùng một đường thẳng.

14. Trên các đoạn $A_1C_1$ và $A_2C_2$ (nằm tùy ý trong không gian), các điểm $B_1$ và $B_2$ được lấy sao cho $|A_1B_1| = \alpha |A_1C_1|$, $|A_2B_2| = \alpha |A_2C_2|$. Trên các đoạn $A_1A_2, B_1B_2, C_1C_2$ ta lấy các điểm $M, N, P$ (Hình 11) sao cho $|A_1M| = \beta |A_1A_2|$, $|B_1N| = \beta |B_1B_2|$, $|C_1P| = \beta |C_1C_2|$. Chứng minh rằng các điểm $M, N, P$ cùng nằm trên một đường thẳng.

15. Hai điểm vật chất chuyển động đều (với vận tốc khác 0) dọc theo hai đường thẳng $a$ và $b$. Đường thẳng nối các điểm chuyển động luôn đi qua điểm cố định $O$. Chứng minh rằng $a \parallel b$.

16. Hai điểm vật chất chuyển động thẳng đều và đều trong không gian với vận tốc $v_1$ và $v_2$. Vị trí của các điểm chuyển động tại thời điểm $t$ được ký hiệu là $A_t$ và $B_t$, và $C_t$ chúng ta cũng ký hiệu là điểm của đoạn $A_tB_t$, tức là $|A_tC_t| : |A_tB_t| = \alpha (0 < \alpha < 1)$. Chứng minh rằng điểm $C_t$ cũng chuyển động thẳng đều. Ở tốc độ nào?

17. Một chiếc máy bay mang một nguồn sáng điểm sáng chuyển động đều và tuyến tính trên một bề mặt phẳng với tốc độ $v_1$, và chiếc máy bay thứ hai chuyển động đều và tuyến tính với vận tốc $v_2$. Tại một số thời điểm, mặt phẳng, mặt phẳng thứ hai và bóng của mặt phẳng thứ hai lần lượt được đặt tại các điểm $A, B, C$ (Hình 12) và $|BC| = \alpha |AC| (0 < \alpha < 1)$. Ở mức độ tương ứng nào giữa tốc độ của các mặt phẳng thì bóng của mặt phẳng thứ hai cũng chuyển động đều và thẳng?

18. Ba điểm vật chất chuyển động đều và thẳng trong không gian, mỗi điểm có tốc độ riêng. Vị trí của các điểm chuyển động tại thời điểm $t$ được ký hiệu là $A_t, B_t, C_t$. Chứng minh trọng tâm của tam giác $A_tB_tC_t$ cũng chuyển động thẳng và đều.
