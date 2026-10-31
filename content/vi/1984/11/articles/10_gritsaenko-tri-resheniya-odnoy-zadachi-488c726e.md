---
id: 1984-11-gritsaenko-tri-resheniya-odnoy-zadachi-488c726e
issue: kvant_1984_11
year: 1984
number: "11"
title: Ba lời giải một bài toán
authors:
  - Грицаенко Н. П.
rubric: shkola-v-kvante
page_first: 31
page_last: 32
page_labels: 29-30
tag: N08J
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c63d6984883bdf968797a4647542f6f6e65d96d88dd9457718f6024e3ae00035
prompt_sha256: draft-1
translated_from: content/ru/1984/11/articles/10_gritsaenko-tri-resheniya-odnoy-zadachi-488c726e.md
source_content_sha256: df1e32e0d991c155ef097f69e5f147f5e66c2409eabfa75c2c9c50b9b7b487c6
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 29⟧

Toán 8,9,10

Ghi chú được xuất bản bên dưới “Về một phương pháp lời giải của một số phương trình” trình bày khả năng suy luận ở từng mức độ có điều kiện, vì mỗi ghi chú này có thể hữu ích không chỉ cho học sinh của các lớp được chỉ định.

Về một chiều lời giải của một số phương trình

Hãy xem xét những điều sau bài toán:
1. Giải phương trình
$$ (2x-1)\sqrt{x-2}=7\sqrt{2}. $$
(1)

Bình phương truyền thống của cả hai bên dẫn đến một phương trình bậc ba
$$ 4x^3-12x^2+9x-100=0, $$
và nhiều nỗ lực mang tính quyết định để tìm ra cách khác của phương trình bài toán.

Có lẽ nhiều người đồng ý rằng chúng ta có thể cố gắng tìm ra một trong những nghiệm của phương trình bằng cách đánh đồng các thừa số tương ứng:
$$ \begin{cases} 2x-1=7, \\ \sqrt{x-2}=\sqrt{2}, \end{cases} $$
từ đâu $x=4$.

Thật không may, họ dừng lại ở đó và viết ra đáp số. Kết quả là, lời giải có sai số nghiêm trọng, mặc dù đáp số đúng: chúng tôi “đoán” nghiệm (đơn) của phương trình nhưng không chứng minh được rằng không còn nghiệm nào nữa.

Trong trường hợp này, thật dễ dàng để chứng minh rằng phương trình (1) không có nghiệm nào khác, vì với $x>4$ chúng ta có $2x-1>7$, $\sqrt{x-2}>\sqrt{2}$ và vế trái lớn hơn vế phải, và với $x<4$ (từ miền định nghĩa của phương trình) $2x-1<7$, $\sqrt{x-2}<\sqrt{2}$, do đó vế trái nhỏ hơn vế phải.

Hãy để chúng tôi nhấn mạnh một lần nữa rằng lời giải bao gồm hai phần:
1) chúng tôi “đoán” nghiệm (hoặc nghiệm) của phương trình;
2) Ta chứng minh rằng phương trình không còn nghiệm nữa.

Lưu ý rằng phương pháp phương trình nghiệm được sử dụng cho lời giải (1) cũng phù hợp trong trường hợp thay vì lấy tích thì người ta đưa tổng vào phương trình. Ví dụ: trong bài toán này:
2. Giải phương trình:
$$ 2x+\sqrt{x-2}=8+\sqrt{2}. $$

Số lượng các yếu tố (thuật ngữ) trong những bài toán như vậy có thể rất lớn; trong trường hợp này, một số hệ số phải được đặt bằng 1, chẳng hạn như trong bài toán sau:
3. Giải phương trình:
$$ (2y-1)\sqrt{y-2}\sqrt{y-3}=7\sqrt{2}. $$
Lưu ý rằng các phương pháp đoán gốc có thể khác nhau. Ví dụ: hãy xem xét bài toán sau:
4. Giải phương trình:
$$ 2a+\sqrt{a-2}+\sqrt{a-3}=9+\sqrt{2}. $$
(2)

Điều tự nhiên là giả sử rằng $\sqrt{a-2}=\sqrt{2}$, do đó $a=4$. Sau đó, thật dễ dàng để kiểm tra xem $a=4$
$$ 2a+\sqrt{a-3}=2\cdot4+\sqrt{1}=9. $$

Bây giờ chúng ta hãy chứng minh (tương tự như bài toán 1) rằng phương trình (2) không có nghiệm nào khác:
1) Đối với $a>4$ chúng ta có $2a>8$, $\sqrt{a-2}>\sqrt{2}$, $\sqrt{a-3}>1$, vì vậy bên trái lớn hơn bên phải;
2) tại $a<4$ (từ miền định nghĩa của phương trình), vế trái nhỏ hơn vế phải.

V. E. Olkhov

Ba lời giải một bài toán

Thường thì chúng ta không kết thúc lý luận của mình và bỏ rơi những ý tưởng nảy sinh trong đầu. Trong bài toán này, bằng cách sử dụng ví dụ về một bài toán, nó cho thấy các ý tưởng khác nhau, khác xa nhau trong giai đoạn đầu, có thể dẫn đến mục tiêu như thế nào nếu bạn thể hiện tính thực tế ở các giai đoạn thấp hơn của lời giải.

Vấn đề. Vẽ một tam giác vuông bằng cách sử dụng cạnh huyền và đường phân giác của góc vuông.

Vấn đề có vẻ tương đối đơn giản, nhưng không thể giải quyết nó một cách “nhanh chóng”.

Như bạn đã biết, lời giải bài toán đối với xây dựng bao gồm 4 điểm: 1) phân tích,

⟦folio 30⟧

2) xây dựng, 3) bằng chứng, 4) nghiên cứu. Chúng ta sẽ bắt đầu với cuộc điều tra chung cho cả ba phương pháp lời giải bài toán. Gọi $c, l_c, m_c, h_c$ là độ dài cạnh huyền tương ứng và đường phân giác, đường trung tuyến và đường cao vẽ từ đỉnh của góc vuông. Trong một tam giác vuông, chúng ta có $m_c = c/2 = R$, trong đó $R$ là bán kính của đường tròn ngoại tiếp tam giác.

Đường phân giác $CD$ của góc $C$ (Hình 1) đi qua điểm $K$—điểm giữa của cung $AB$. Do đó (nếu $|AC| \neq |BC|$) nó nằm giữa đường trung tuyến và chiều cao, và hình chiếu của nó lên cạnh huyền nhỏ hơn hình chiếu của đường trung tuyến lên cạnh huyền. Điều này hàm ý sự bất đẳng thức $h_c \leq l_c \leq m_c = c/2$ (sự đẳng thức đạt được đối với một tam giác đều). Do đó, vì $l_c > c/2$ lời giải không tồn tại, vì $l_c \leq c/2$ lời giải tồn tại và là duy nhất.

Lưu ý rằng với $l_c = c/2$ tam giác là tam giác đều, trong trường hợp này việc xây dựng và chứng minh rất phức tạp. Trong phần tiếp theo, chúng ta sẽ giả sử rằng $l_c < c/2$ (và tam giác là đều).

Ý tưởng đầu tiên. Tâm của đường tròn ngoại tiếp tam giác nằm ở giữa điểm enotenuse, đường phân giác của góc vuông đi qua giữa cung (hình bán nguyệt) $AB$, không chứa điểm $C$. Chúng ta sẽ xem xét một hình tam giác được ghi trong một vòng tròn. Khi đó, có lẽ sẽ có thể tìm thấy mối quan hệ giữa dữ liệu và các phần tử xuất hiện trong bản vẽ, xuất phát từ tính chất của một tam giác nội tiếp trong một vòng tròn.

Phân tích. Đặt tam giác $ABC$ là hình mong muốn. Chúng ta hãy vẽ một vòng tròn xung quanh nó (xem Hình 1). Đặt $M$ và $K$ là giao điểm của đường tròn và đường kính của nó,

$$\begin{align*}
\perp &= \perp \\
M &= M \\
K &= K
\end{align*}$$

vuông góc $AB$. Khi đó các cung $AK$ và $KB$ bằng nhau nên $CK$ là phân giác của góc $C$. Tam giác $MCK$ là hình chữ nhật. Rõ ràng, đối với lời giải bài toán, việc biểu thị độ dài của đoạn $CK$ theo $c$ và $l_c$ là đủ.

Hình tam giác $MCK$ và $KOD$ giống nhau ở hai góc. Chúng ta hãy biểu thị độ dài của đoạn $DK$ bằng $x$. Sau đó

$$\frac{|CK|}{|KM|} = \frac{|OK|}{|DK|} \text{ или } \frac{l_c + x}{c} = \frac{c/2}{x},$$

từ đâu $x^2 + l_c x - c^2/2 = 0$. Đó là lý do tại sao,

$$x = -l_c/2 + \sqrt{l_c^2/4 + c^2/2}$$

(rõ ràng chỉ có nghiệm dương của phương trình là phù hợp). Kế tiếp

$$|CK| = l_c + x = l_c/2 + \sqrt{l_c^2/4 + c^2/2}. \tag{1}$$

Sự thi công. Chúng ta hãy dựng đoạn $d = \sqrt{l_c^2/4 + c^2/2}$ làm cạnh huyền của một tam giác vuông có hai chân $l_c/2$ và $c/\sqrt{2}$, sau đó là đoạn $l_c/2 + d$. Sau đó, chúng ta sẽ dựng một tam giác vuông $CMK$ dọc theo cạnh huyền $|MK| = c$ và chân $|CK| = l_c/2 + d$, vẽ một đường tròn có đường kính $MK$ và dựng đường kính $AB$ của đường tròn này, đường kính vuông góc $MK$. Cần có tam giác $ABC$ (xem Hình 1).

Bằng chứng. Theo cách xây dựng, $|AB| = c, MK$ và $AB$ là các đường kính vuông góc với nhau, do đó $AK = KB = 90^\circ, ACK = KCB = 45^\circ$, tức là $CK$, là phân giác của góc (phải) $C$. Cần chỉ ra rằng $|CD| = l_c$, trong đó $D$ là giao điểm của các đoạn $CK$ và $AB$.

Hãy tiến hành chứng minh bằng phản chứng. Ví dụ: đặt $|CD| = f > l_c$. Khi đó trong tam giác $ABC$ độ dài cạnh huyền là $c$, và đường phân giác là $CD - f$, do đó, theo (1)

$$|CK| = \frac{f}{2} + \sqrt{\frac{f^2}{4} + \frac{c^2}{2}} > \frac{l_c}{2} +$$

$$+ \sqrt{\frac{l_c^2}{4} + \frac{c^2}{2}} = |CK|$$

(bằng cách xây dựng), mâu thuẫn. Trường hợp $|CD| = f < l_c$ cũng được xử lý tương tự.

Khi trình bày phương pháp thứ hai và thứ ba lời giải bài toán chúng tôi sẽ chỉ giới hạn ở việc phân tích. Hãy tự mình tiến hành xây dựng và chứng minh.

Ý tưởng thứ hai. Tam giác mong muốn có được kết nối với các tam giác khác có các phần tử chung với nó không?
