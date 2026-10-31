---
id: 1976-7-gotman-skalyarnoe-proizvedenie-vektorov-v-geometricheskih-zadachah-zadachi-na-dokazatelstvo-ee40dabf
issue: kvant_1976_7
year: 1976
number: "7"
title: Tích vô hướng của vectơ trong các bài toán hình học. Bài toán để chứng minh
authors:
  - Готман Э. Г.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 23
page_last: 26
page_labels: 21, 23, 24
tag: JINI
lang: vi
source: kvant_digital
extraction: vision
content_sha256: b36e4faf192d2d605586122b4b10cf36808a7504b2ecd8c7bf57719004481774
prompt_sha256: draft-1
translated_from: content/ru/1976/07/articles/07_gotman-skalyarnoe-proizvedenie-vektorov-v-geometricheskih-zadachah-zadachi-na-dokazatelstvo-ee40dabf.md
source_content_sha256: fc8ca149abad960f8662319942e862a3178ce33579f59a41b987daacf8f3c270
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 21⟧

Chương trình hình học mới (dành cho lớp 9) bao gồm khái niệm tích vô hướng của vectơ. Tích số chấm của vectơ được sử dụng rộng rãi trong lời giải các chứng minh định lý và hình học bài toán khác nhau. Dưới đây chúng tôi đặt hai ghi chú - của E. Gotman và Y. Ponarin, minh họa việc sử dụng phương pháp vectơ bằng một số ví dụ. Người đọc cần phải làm quen với các thao tác đơn giản nhất - phép cộng vectơ và nhân vectơ với một số, cũng như khái niệm tích vô hướng của vectơ. Chúng ta hãy nhắc lại định nghĩa và một số tính chất của phép nhân vô hướng các vectơ.

Tích vô hướng của hai vectơ khác 0 là một số bằng tích của các giá trị số độ dài của các vectơ này và cosin của góc giữa các vectơ.

Tích vô hướng của vectơ a và b được ký hiệu là a·b; theo định nghĩa a·b = |a|·|b|·cos a, b). Các tính chất của phép nhân vectơ vô hướng tương tự như định luật thực hiện các số:

1) a·b = b·a;
2) (λa) b = λ(a b), trong đó λ là một số nhất định;
3) a·(b+c) = a·b+a·c

(để chứng minh, xem SGK hình học lớp 9, tr. 59).

E. Gotman

Nhiệm vụ

để chứng minh

Bạn nên vắt kiệt mọi thứ mà nó có thể mang lại từ kết quả thu được.

D. Hát a. Cách giải quyết bài toán.

Tứ giác phẳng

Dễ dàng nhận thấy nếu các đường chéo AC và BD của tứ giác ABCD vuông góc với nhau (Hình 1) thì

độ dài các cạnh của nó thỏa mãn mối quan hệ

$$|AB|^2 + |CD|^2 = |BC|^2 + |AD|^2.$$

Điều ngược lại có đúng không: có thể nói rằng các đường chéo của một tứ giác

⟦folio 23⟧

thay vì được nêu trong đoạn trước (sử dụng định lý cosine), nhưng nó được áp dụng rất nghiêm ngặt: xét cho cùng, bây giờ chúng ta biết rằng đẳng thức (2) đúng với bất kỳ vị trí nào của bốn điểm $A, B, C$ và $D$, và không chỉ khi các điểm này là các đỉnh của một tứ giác phẳng.

Áp dụng đẳng thức (3), bây giờ chúng ta sẽ thu được nhiều kết quả mới thú vị.

Hậu quả

1. Các cạnh công nghiệp $AC$ và $BD$ của khối mét mặt $ABCD$ phân phối lại moed và molkomoed khi tổng bình phương độ dài của các cạnh công nghiệp khác: $AB$ và $CD$, $BC$ và $AD$ bằng nhau.

Trên thực tế, góc giữa các cạnh $AC$ và $BD$ có thể tìm được bằng công thức

$$\cos(\overrightarrow{AC}, \overrightarrow{DB}) = \frac{|AB|^2 + |CD|^2 - |BC|^2 - |AD|^2}{2|AC| \cdot |BD|}.$$

nhưng $\cos(\overrightarrow{AC}, \overrightarrow{DB}) = 0$ nếu và chỉ nếu

$$|AB|^2 + |CD|^2 = |BC|^2 + |AD|^2.$$

2. Tập hợp các điểm $D$ của mặt phẳng, hiệu bình phương khoảng cách từ mỗi điểm đến hai điểm cho trước $A$ và $C$ là một giá trị không đổi, là đường thẳng, xác định lại đường thẳng $AC$.

Bằng chứng. Đặt hiệu này bằng $k^2$. Hãy xây dựng nó trong Hình 3.

thẳng $AC$ điểm $B$ sao cho $|AB|^2 - |BC|^2 = k^2$. Để làm điều này, thông qua điểm $C$, chúng ta vẽ phân phối lại cho đường thẳng $AC$ và vẽ một đoạn $CM$ có độ dài $k$ trên đó (Hình 2). Sự phân bố lại ở giữa của đoạn $AM$ sẽ cắt đường thẳng $AC$ với điểm chùa $B$.

Thật vậy, từ tam giác vuông $BCM$, $|BM|^2 - |BC|^2 = |CM|^2$. Nhưng $|BM| = |AB|$ theo tính chất của phân phối lại điểm giữa và $|CM| = k$. Vì vậy, $|AB|^2 - |BC|^2 = k^2$.

Rõ ràng, điểm $B$ luôn tồn tại và là duy nhất. Bây giờ hãy đặt $D$ là một điểm của tập hợp mong muốn. Áp dụng công thức (3) cho các điểm $A, B, C$ và $D$ của mặt phẳng, chúng ta thu được $|AD|^2 - |CD|^2 = |AB|^2 - |BC|^2$ khi và chỉ nếu đường thẳng $BD$ là phân phối lại của đường thẳng $AC$.

Quét. Tập hợp các điểm trong không gian có các tính chất đã chỉ ra là một mặt phẳng, phân bố lại thành đường thẳng $AC$.

3. Nếu $ACBD$ là một tứ giác lồi, các cạnh công nghiệp $AC$ và $BD$ của chúng được phân phối lại (Hình 3), thì tổng bình phương của độ dài các đường chéo của nó bằng tổng bình phương của độ dài của hai cạnh công nghiệp khác của nó.

Bằng chứng. Pokolku $(AC) \perp (DB)$, $\overrightarrow{AC} \cdot \overrightarrow{DB} = 0$, tức là vế phải của đẳng thức (3) trở thành số không. Kể từ đây,

$$|AB|^2 + |CD|^2 = |BC|^2 + |AD|^2.$$

⟦folio 24⟧

Cơm. 5.

4. Tổng bình phương chiều dài các đường chéo của hình thang bằng tổng bình phương chiều dài các cạnh bên của nó và nhân đôi chiều dài của các đáy.

Bằng chứng. Gọi AC và DB là đáy của hình thang ACBD (Hình 4). Vì các vectơ $\vec{AC}$ và $\vec{DB}$ được đồng sửa chữa nên $\vec{AC} \cdot \vec{DB} = |AC| \cdot |DB|$ và đẳng thức (3) có dạng $|AB|^2 + |CD|^2 - |BC|^2 - |AD|^2 = 2|AC| \cdot |BD|$, tức là.

$$|AB|^2 + |CD|^2 = |BC|^2 + |AD|^2 + 2|AC| \cdot |DB|$$

Q.E.D.

5. (Một định lý nổi tiếng.) Tổng bình phương chiều dài các đường chéo của hình bình hành bằng tổng bình phương chiều dài tất cả các cạnh của nó.

Bằng chứng. Các vectơ AC và DB được đồng hiệu chỉnh (Hình 5), do đó $\vec{AC} \cdot \vec{DB} = |AC| \cdot |DB| = |AC|^2$, vì $|AC| = |DB|$.

Thay giá trị tìm được $\vec{AC} \cdot \vec{DB}$ vào (3), ta thu được

$$|AB|^2 + |CD|^2 = |BC|^2 + |AD|^2 + 2|AC|^2 = |BC|^2 + |AD|^2 + |AC|^2 + |BD|^2$$

và định lý đã được chứng minh.

Hãy nhớ lại rằng bình phương khoảng cách giữa hai điểm bằng bình phương vô hướng của vectơ xác định bởi các điểm đó. Sau khi đã quyết định bài toán, hãy dành thời gian: suy nghĩ xem liệu kết quả có thể được sử dụng cho lời giải một số bài toán khác hay không.

3. a) Một đường tròn ngoại tiếp tam giác $ABC$ và dựng một điểm D đối xứng với tâm O so với cạnh AB. Biểu thị vectơ $\vec{CD}$ theo các vectơ $\vec{OA}$, $\vec{OB}$ và $\vec{OC}$. Chứng minh rằng

$$|CD|^2 = R^2 + a^2 + b^2 - c^2,$$

trong đó a = |BC|, b = |AC|, c = |AB|, R = |OA|.

6) Chứng minh rằng với mọi tam giác $ABC$ bất đẳng thức

$$\cos 2\hat{A} + \cos 2\hat{B} - \cos 2\hat{C} \leq \frac{3}{2}.$$

Tìm hiểu khi nào sự bình đẳng xảy ra.

2. a) Chứng minh khoảng cách từ tâm O của đường tròn ngoại tiếp tam giác $ABC$ đến trọng tâm ABC, M là điểm thỏa mãn điều kiện $|OM| = 3 |OG|$. Biểu thị khoảng cách từ đỉnh D đến điểm M bằng độ dài các cạnh của tam giác và bán kính của hình cầu ngoại tiếp tam giác.

6) Chứng minh rằng nếu a, b, c là độ dài các cạnh của một tam giác có chung một đỉnh, a1, b1, c1 là độ dài 3 cạnh còn lại và R là bán kính hình cầu ngoại tiếp nó thì

$$a_1^2 + b_1^2 + c_1^2 \leq 4R^2 + a^2 + b^2 + c^2.$$

4. Chứng minh rằng khoảng cách từ tâm O của hình cầu ngoại tiếp tam giác $ABC$ đến trọng tâm mặt ABC của nó, M là điểm thỏa mãn điều kiện $|OM| = 3 |OG|$. Biểu thị khoảng cách từ đỉnh D đến điểm M bằng độ dài các cạnh của tam giác có chung một đỉnh a1, b1, c1 - độ dài 3 cạnh còn lại và R - bán kính hình cầu ngoại tiếp nó, khi đó đẳng thức giữ nguyên

$$|OG|^2 = R^2 - \frac{1}{16} (a^2 + b^2 + c^2 + a_1^2 + b_1^2 + c_1^2),$$

trong đó a, b, c, a1, b1, c1 là độ dài các cạnh của tam giác, R là bán kính của hình cầu ngoại tiếp.

5. Chứng minh rằng nếu A, B, C, D là điểm bốn trường trong không gian, M và N lần lượt là trung điểm của các đoạn AC và BD thì đẳng thức đúng

$$|AC|^2 + |BD|^2 = |AB|^2 + |BC|^2 + |CD|^2 + |DA|^2 - 4 |MN|^2.$$

Định lý này có thể suy ra những hệ quả gì?

*) Xem bài viết “Euler's Direct” của E. Gottman (Quant, 1975, No. 2, p. 32).
