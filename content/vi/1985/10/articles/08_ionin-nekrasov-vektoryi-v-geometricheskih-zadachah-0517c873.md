---
id: 1985-10-ionin-nekrasov-vektoryi-v-geometricheskih-zadachah-0517c873
issue: kvant_1985_10
year: 1985
number: "10"
title: Vectơ trong bài toán hình học
authors:
  - Ионин Ю. И.
  - Некрасов В. Б.
rubric: shkola-v-kvante
page_first: 23
page_last: 25
page_labels: 21-23
tag: K5Y7
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 9d4bd966da644ef3bdbe7c49912fd325e15c59f28ffb28c6ca18cc176fcd53b0
prompt_sha256: draft-1
translated_from: content/ru/1985/10/articles/08_ionin-nekrasov-vektoryi-v-geometricheskih-zadachah-0517c873.md
source_content_sha256: 00cd43ae4424b31f7f2b16c8d63901ed3e55beb3ee791ff662600841fb8d5a0f
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 21⟧

Matematika
8, 9, 10

Ghi chú được công bố dưới đây là dành cho học sinh lớp mười. Tuy nhiên, phần đầu tiên của nó có thể hữu ích cho học sinh lớp 8 và lớp 9.

Vectơ trong bài toán hình học

1. Tính song song và tỷ lệ của các phân đoạn

Bài toán 1. Điểm K, L, M, N là trung điểm các cạnh BC, CD, DE, EA của ngũ giác ABCDE, điểm P và Q là trung điểm của các đoạn KM và LN. Chứng minh hai đoạn thẳng PQ và AB song song và tìm tỉ số độ dài của chúng (trang 1).

Hãy để chúng tôi dịch câu lệnh bài toán sang ngôn ngữ vector.

Sự song song của các đoạn PQ và AB được viết bằng đẳng thức $\overrightarrow{PQ} = k \cdot \overrightarrow{AB}$, trong đó $k$ là một số thực. Sau khi tính $k$, ta tìm được tỉ số độ dài của các đoạn PQ và AB.

Công thức chính trong lời giải của bài toán này hóa ra là $\overrightarrow{OZ} = \frac{1}{2}(\overrightarrow{OX} + \overrightarrow{OY})$, trong đó $Z$ là trung điểm của đoạn XY và $O$ là một điểm tùy ý.

Lời giải. $\overrightarrow{PQ} = \overrightarrow{OQ} - \overrightarrow{OP} = \frac{1}{2}(\overrightarrow{OL} + \overrightarrow{ON}) - \frac{1}{2}(\overrightarrow{OK} + \overrightarrow{OM}) = \frac{1}{2}\left(\frac{1}{2}(\overrightarrow{OC} + \overrightarrow{OD}) + \frac{1}{2}(\overrightarrow{OA} + \overrightarrow{OE})\right) = \frac{1}{4}(\overrightarrow{OA} - \overrightarrow{OB}) = -\frac{1}{4}\overrightarrow{AB}$.

Suy ra hai đoạn PQ và AB song song và tỉ số của chúng là $\frac{1}{4}$.

Trong lời giải đã cho, chúng tôi đã sử dụng "công thức sai phân" hai lần

$\overrightarrow{XY} = \overrightarrow{OY} - \overrightarrow{OX}$, cho phép bạn biểu diễn bất kỳ vectơ nào theo các vectơ được vẽ từ cùng một điểm.

Dưới đây là một số ví dụ về cách viết cùng một câu lệnh bằng ngôn ngữ hình học và vectơ:

1. Các điểm A, B, C cùng nằm trên một đường thẳng.
2. Điểm M chia đoạn AB liên quan đến $|AM|:|MB| = l:k$
3. M là giao điểm các đường trung tuyến (trọng tâm) của tam giác ABC.
4. ABCD - đường song song.

Trong hai trường hợp cuối, các câu lệnh hình học và vectơ là tương đương với điều kiện là các điểm A, B, C không nằm trên cùng một đường thẳng.

Bài toán 2. Chứng minh rằng trung điểm hai đáy và giao điểm của các đường chéo của hình thang cùng nằm trên một đường thẳng (Hình 2).

Lời giải. Gọi M, N là trung điểm BC và AD của hình thang ABCD, O là giao điểm của hai đường chéo. Từ sự đồng dạng của các tam giác AOD và BOC ta có: $\frac{|OA|}{|OC|} = \frac{|OD|}{|OB|}$. Chỉ định những điều này

⟦folio 22⟧

2. Tâm của hệ thống điểm

Khái niệm trọng tâm có thể dễ dàng được chuyển từ một tam giác sang một hệ điểm hữu hạn tùy ý trong không gian:

Điểm M được gọi là trọng tâm của hệ gồm n điểm $A_1, A_2, \dots, A_n$ nếu $\overrightarrow{MA}_1 + \overrightarrow{MA}_2 + \dots + \overrightarrow{MA}_n = \overrightarrow{0}$.

Sử dụng công thức sai phân, đẳng thức cuối cùng có thể được viết lại như sau: $(\overrightarrow{OA}_1 - \overrightarrow{OM}) + (\overrightarrow{OA}_2 - \overrightarrow{OM}) + \dots + (\overrightarrow{OA}_n - \overrightarrow{OM}) = \overrightarrow{0}$ (O là điểm tùy ý),

$\overrightarrow{OA}_1 + \overrightarrow{OA}_2 + \dots + \overrightarrow{OA}_n - n \cdot \overrightarrow{OM} = \overrightarrow{0}$,

$\overrightarrow{OM} = \frac{1}{n} (\overrightarrow{OA}_1 + \overrightarrow{OA}_2 + \dots + \overrightarrow{OA}_n)$.

Từ công thức cuối cùng, suy ra rằng mọi hệ điểm hữu hạn đều có một trọng tâm. Hơn nữa, trọng tâm của một hệ gồm một điểm chính là điểm này, trọng tâm của một cặp điểm là chính giữa đoạn nối chúng. Việc tìm trọng tâm của một số lớn được tha thứ theo nguyên tắc sau: nếu $M_1$ là trọng tâm của hệ k điểm $A_1, A_2, \dots, A_k$, và $M_2$ là trọng tâm của hệ l điểm $B_1, B_2, \dots, B_l$ và các hệ này không có điểm chung thì trọng tâm của hệ k + l điểm $A_1, A_2, \dots, A_k, B_1, B_2, \dots, Bl$ là điểm M thuộc đoạn $M_1M_2$ và chia nó trong quan hệ $|M_1M_2| = l:k$.

Thật vậy, hãy để $k \cdot \overrightarrow{M_1M} = l \cdot \overrightarrow{MM_2}$.

Sử dụng công thức sai phân, ta có:

$k (\overrightarrow{OM} - \overrightarrow{OM}_1) = l (\overrightarrow{OM}_2 - \overrightarrow{OM}_1)$,

$k \cdot \overrightarrow{OM} - k \cdot \overrightarrow{OM}_1 = l \cdot \overrightarrow{OM}_2 - l \cdot \overrightarrow{OM}_1$,

$(k + l) \cdot \overrightarrow{OM} = k \cdot \overrightarrow{OM}_1 + l \cdot \overrightarrow{OM}_2$,

$\overrightarrow{OM} = \frac{k}{k + l} \overrightarrow{OM}_1 + \frac{l}{k + l} \overrightarrow{OM}_2$.

Theo công thức (1)

$\overrightarrow{OM}_1 = \frac{1}{k} (\overrightarrow{OA}_1 + \overrightarrow{OA}_2 + \dots + \overrightarrow{OA}_k)$,

$\overrightarrow{OM}_2 = \frac{1}{l} (\overrightarrow{OB}_1 + \overrightarrow{OB}_2 + \dots + \overrightarrow{OB}_l)$,

Vì thế

$\overrightarrow{OM} = \frac{1}{k + l} (\overrightarrow{OA}_1 + \overrightarrow{OA}_2 + \dots + \overrightarrow{OA}_k)$,

và chúng tôi đã có được thứ chúng tôi cần.

Áp dụng nguyên lý này cho ba đỉnh của một tam giác, ta thấy trọng tâm của tam giác nằm trên

⟦folio 23⟧

một đoạn nối đỉnh với tâm của hai đỉnh khác, tức là với điểm giữa của cạnh đối diện và chia đoạn này theo tỷ lệ 2: 1, tính từ đỉnh. Điều này dẫn đến định lý nổi tiếng về phép đo mặt phẳng: các đường trung tuyến của một tam giác cắt nhau tại một điểm và được chia cho điểm này theo tỷ lệ 2:1, tính từ các đỉnh.

Người ta chứng minh tương tự rằng các đoạn nối các đỉnh của một tam giác với trọng tâm của các mặt đối diện cắt nhau tại một điểm—trọng tâm của tam giác—và tại điểm này được chia theo tỷ lệ 3:1, tính từ các đỉnh.

3. Tính khoảng cách và góc

Sau khi đã cho bộ ba vectơ không đồng phẳng trong không gian - một cơ sở, có thể mở rộng bất kỳ vectơ nào vào cơ sở này một cách duy nhất. Biết tích vô hướng của các vectơ cơ sở, chúng ta có thể dễ dàng tính tích vô hướng của bất kỳ vectơ nào, cũng như độ dài và góc giữa chúng.

Nhiệm vụ 4. Cho $\vec{a}\vec{b} = 1$, $\vec{a}\vec{c} = 2$, $\vec{b}\vec{c} = 0$, $\vec{a}^2 = \vec{b}^2 = 4$, $\vec{c}^2 = 2$.

Tìm $|\vec{p}|$, $|\vec{q}|$, $(\vec{p}, \vec{q})$ nếu $\vec{p} = 2\vec{a} - \vec{b}$, $\vec{q} = \vec{a} + \vec{b} + \vec{c}$.

Lời giải: Hãy viết lại các điều kiện bài toán dưới dạng “bảng nhân” (Bảng 1). Chúng tôi tìm thấy: $|\vec{p}| = \sqrt{\vec{p}^2} = \sqrt{(2\vec{a} - \vec{b})^2} = \sqrt{4\vec{a}^2 - 4\vec{a}\vec{b} + \vec{b}^2} = \sqrt{16} = 4$;

$|\vec{q}| = \sqrt{\vec{q}^2} = \sqrt{(\vec{a} + \vec{b} + \vec{c})^2} = \sqrt{\vec{a}^2 + \vec{b}^2 + \vec{c}^2 + 2\vec{a}\vec{b} + 2\vec{a}\vec{c} + 2\vec{b}\vec{c}} = \sqrt{16} = 4$.

Từ định nghĩa tích vô hướng ta có:

$$\cos(\vec{p}, \vec{q}) = \frac{\vec{p}\vec{q}}{|\vec{p}| \cdot |\vec{q}|} = \frac{2(\vec{a} - \vec{b})(\vec{a} + \vec{b} + \vec{c})}{16} = \frac{2\vec{a}^2 + \vec{a}\vec{b} + 2\vec{a}\vec{c} - \vec{b}^2 - \vec{b}\vec{c}}{16} = \frac{9}{16},$$

từ đâu $(\vec{p}, \vec{q}) = \arccos \frac{9}{16}$.

Bài toán 5. Đáy của đặc điểm $ABCA_1B_1C_1$ là hình tam giác đều. Cạnh bên $AA_1$ lớn gấp đôi cạnh của đế và tạo thành các góc $A_1AB = 90^\circ$, $A_1AC = 60^\circ$. O là tâm tam giác $ABC$. Tìm trên đường $CC_1$ một điểm $K$ sao cho đường thẳng $B_1K$ và $A_1O$ vuông góc.

Lời giải. Vị trí của điểm $K$ trên đường thẳng $CC_1$ được xác định bởi giá trị của hệ số $x$ trong đẳng thức $\vec{C}_1\vec{K} = x \cdot \vec{C}_1\vec{C}$. Chúng ta hãy biểu thị bằng $a$ độ dài cạnh của cơ sở nhận biết, chọn làm cơ sở bộ ba vectơ $\vec{m} = \vec{AB}$, $\vec{n} = \vec{AC}$, $\vec{p} = \vec{AA}_1$ (hình 5), sau đó chúng ta biên soạn một “bảng nhân” (Bảng 2).

Chúng ta hãy phân tách các vectơ $\vec{A}_1\vec{O}$ và $\vec{B}_1\vec{K}$ thành cơ sở $(\vec{m}, \vec{n}, \vec{p})$: $\vec{A}_1\vec{O} = \vec{A}_1\vec{A} + \vec{A}O = -\vec{p} + \frac{1}{3}(\vec{m} + \vec{n}) = \frac{1}{3}(\vec{m} + \vec{n} - 3\vec{p})$, $\vec{B}_1\vec{K} = \vec{B}_1\vec{A}_1 + \vec{A}_1\vec{C}_1 + \vec{C}_1\vec{K} = \vec{m} + n - x\vec{p}$. Viết ra các điều kiện vuông góc với các số nguyên tố $A_1O$ và $B_1K$:

$(\vec{m} + \vec{n} - 3\vec{p})(-\vec{m} + \vec{n} - x\vec{p}) = 0$, chúng tôi thu được bằng cách sử dụng bảng 2: $11a^2x - 3a^2 = 0$, từ đâu $x = \frac{3}{11}$.

Bài tập

1. Trong khối địa hình $ABCD$ các điểm $E$ và $F$ là trung điểm của các cạnh $AB$ và $CD$. Chứng minh rằng trung điểm của các đoạn thẳng $CE, DE, AF$ là các đỉnh của hình bình hành.

2. Điểm $A, B, C, D, E, F$ không nằm trong cùng một mặt phẳng. Chứng minh rằng nếu các đường thẳng $AB$ và $DE, BC$ và $EF, CD$ và $AF$ song song thì $|AB| = |DE|, |BC| = |EF|, |CD| = |AF|$.

3. Chứng minh rằng các đoạn thẳng nối trung điểm đáy của các tứ giác của hình bình hành cắt nhau tại một điểm. Họ chia sẻ quan điểm này ở khía cạnh nào?

4. Chứng minh rằng trung điểm của các tứ giác được thảo luận ở bài tập trước là các đỉnh của hình bình hành.
