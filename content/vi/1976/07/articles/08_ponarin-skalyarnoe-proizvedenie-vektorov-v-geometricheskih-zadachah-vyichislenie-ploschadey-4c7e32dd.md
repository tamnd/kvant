---
id: 1976-7-ponarin-skalyarnoe-proizvedenie-vektorov-v-geometricheskih-zadachah-vyichislenie-ploschadey-4c7e32dd
issue: kvant_1976_7
year: 1976
number: "7"
title: Tích vô hướng của vectơ trong các bài toán hình học. Tính diện tích
authors:
  - Понарин Я. П.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 27
page_last: 29
page_labels: 25, 27
tag: L0J1
lang: vi
source: kvant_digital
extraction: vision
content_sha256: ab33535ba77321676afd2a7a46881c3bd96f713891c04be175132a5b0c670df7
prompt_sha256: draft-1
translated_from: content/ru/1976/07/articles/08_ponarin-skalyarnoe-proizvedenie-vektorov-v-geometricheskih-zadachah-vyichislenie-ploschadey-4c7e32dd.md
source_content_sha256: 5f1fc9d5d3e34cb13f3e9f70fcea2824acc72fc1e02c44b242ffcdcb29fc79e6
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 25⟧

Vâng. ponarin

Khu vực nuôi

Diện tích của một hình tam giác
Được biết, diện tích tam giác ABC có thể tính được bằng công thức
$$S = \frac{1}{2} ab \sin \hat{C},$$
(1)

trong đó a, b và c lần lượt là độ dài các cạnh của tam giác nằm đối diện với các góc $\hat{A}, \hat{B}$ và $\hat{C}$.

Chúng ta hãy biểu thị các vectơ $\vec{CB}$ và $\vec{CA}$ của các cạnh của tam giác bằng $\vec{a}$ và $\vec{b}$. Từ định nghĩa tích vô hướng của vectơ, ta suy ra $\cos \hat{C} = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| \cdot |\vec{b}|}$, từ đó $\sin^2 \hat{C} = \frac{a^2 b^2 - (\vec{a} \cdot \vec{b})^2}{a^2 b^2}$
(bình phương vô hướng của một vectơ bằng bình phương chiều dài của nó).

Chúng ta hãy bình phương cả hai vế của công thức (1) và thay biểu thức tìm được cho $\sin^2 \hat{C}$; chúng tôi nhận được
$$4S^2 = a^2 b^2 - (\vec{a} \cdot \vec{b})^2.$$
(2)

Công thức (2) sẽ hữu ích cho chúng ta sau này (đặc biệt, từ đó dễ dàng thu được công thức Heron tính diện tích hình tam giác).

Diện tích của một tứ giác
Nếu p và q là độ dài các đường chéo của một tứ giác phẳng tùy ý (có các cạnh đối diện không cắt nhau tại các điểm bên trong), thì diện tích của nó có thể được tính bằng công thức
$$S = \frac{1}{2} pq \sin (\vec{p}, \vec{q}).$$
(3)

Như trong trường hợp tam giác, chúng ta viết lại công thức này ở dạng tương tự như (2):
$$4S^2 = p^2 q^2 - (\vec{p} \cdot \vec{q})^2.$$
(4)

Để đánh giá các công thức thu được (2) và (4), chúng ta hãy giải một số bài toán (nếu bạn cố gắng giải chúng theo cách khác mà không sử dụng tích vô hướng, bạn sẽ thấy lời giải phức tạp hơn nhiều).

Bài toán 1. Tính diện tích mặt ABC của metahedron ABCD, nếu a, b, c là độ dài các cạnh DA, DB và DC của nó và α, β, γ là các góc phẳng tại đỉnh D tương ứng với các cạnh BC, AC và AB.

Lời giải e. Chúng ta hãy giới thiệu ký hiệu sau: $\vec{DA} = \vec{a}, \vec{DB} = \vec{b}, \vec{DC} = \vec{c}$. Khi đó diện tích S của mặt ABC ta có
$$4S^2 = |\vec{CA}|^2 \cdot |\vec{CB}|^2 - (\vec{CA} \cdot \vec{CB})^2 = (\vec{a} - \vec{c})^2 \cdot (\vec{b} - \vec{c})^2 - ((\vec{a} - \vec{c}) \cdot (\vec{b} - \vec{c}))^2 = (a^2 + c^2 - 2ac \cos \beta)(b^2 + c^2 - 2bc \cos \alpha) - (ab \cos \gamma - ac \cos \beta - bc \cos \alpha + c^2)^2.$$

Trên thực tế, bài toán đã được giải, nhưng biểu thức thu được bao gồm độ dài a, b, c và các góc α, β, γ không đối xứng, mặc dù theo điều kiện bài toán ​​các giá trị của a, b, c, cũng như α, β, γ phải

⟦folio 27⟧

Bài tập 4. Vẽ một mặt phẳng đi qua đỉnh của một khối đa diện đều có cạnh a sao cho đường giao nhau của nó với mặt phẳng đáy song song với cạnh và chia đáy thành hai phần bằng nhau. Tìm diện tích mặt cắt ngang của khối đa diện theo mặt phẳng đã chỉ định (Hình 3).

Lời giải. Trong tứ diện đều này, chúng ta biểu thị $ABCD$ $\vec{DA} = \vec{a}$, $\vec{DB} = \vec{b}$, $\vec{DC} = \vec{c}$ và $|\vec{a}| = |\vec{b}| = |\vec{c}| = a$. Cho mặt phẳng cắt cắt mặt phẳng $ABC$ dọc theo các đường thẳng $MN$, $M \in (AB)$, $N \in (AC)$ và $(MN) \parallel (BC)$. Diện tích mặt cắt ngang yêu cầu có thể được tính bằng công thức

$$4S^2 = |\vec{DM}|^2 \cdot |\vec{DN}|^2 - (\vec{DM} \cdot \vec{DN})^2.$$

Công thức này cho bạn biết cách giải bài toán.

Chúng ta có $\vec{DM} = \vec{DA} + \vec{AM}$, trong đó $\vec{AM} = k \cdot \vec{AB}$.

Số $k$ được tìm thấy từ điều kiện đường thẳng $MN$ chia đáy $ABC$ thành hai phần bằng nhau và sao cho các tam giác $AMN$ và $ABC$ giống nhau; Đó là lý do tại sao

$$S_{AMN} : S_{ABC} = |\vec{AM}|^2 : |\vec{AB}|^2 = k^2 = \frac{1}{2},$$

từ đâu $k = \frac{1}{\sqrt{2}}$. Đó là lý do tại sao

$$\vec{DM} = \vec{DA} + k \cdot \vec{AB} = a + \frac{1}{\sqrt{2}} (\vec{b} - \vec{a}) = \frac{(\sqrt{2} - 1) \vec{a} + \vec{b}}{\sqrt{2}}.$$

Tương tự như $\vec{DN} = \frac{(\sqrt{2} - 1) \vec{a} + \vec{c}}{\sqrt{2}}$.

Thay thế các biểu thức cho $\vec{DM}$ và $\vec{DN}$ vào công thức cho $S$, chúng ta nhận được

$$16S^2 = ((\sqrt{2} - 1) \vec{a} + \vec{b})^2 \cdot ((\sqrt{2} - 1) \vec{a} + \vec{b}) \times ((\sqrt{2} - 1) \vec{a} + \vec{c})^2.$$

Vì đối với một tứ diện đều có độ dài cạnh $a$

$$\vec{a} \cdot \vec{b} = \vec{b} \cdot \vec{c} = \vec{a} \cdot \vec{c} = \frac{1}{2} a^2,$$

rồi sau tất cả những yêu cầu chúng tôi nhận được

$$S = \frac{1}{8} a^2 \sqrt{11 - 4\sqrt{2}}.$$

Hãy tự mình giải quyết câu bài toán sau:

1. Cho một tứ giác tùy ý $ABCD$. Điểm $A_1$ và $C_1$ là ảnh của cả hai đỉnh $A$ và $C$ khi ngực song song với giao điểm của chúng. Chứng minh rằng tứ giác $A_1BC_1D$ có kích thước bằng tứ giác $ABCD$ đã cho.

2. Trong tứ diện $ABCD$, độ dài của cả sáu cạnh đã biết: $|DA| = a$, $|DB| = b$, $|DC| = c$, $|BC| = a_1$, $|AC| = b_1$, $|AB| = c_1$. Một mặt phẳng được vẽ qua giữa cạnh $DB$ song song với các cạnh $AD$ và $BC$. Tìm diện tích mặt cắt ngang của tứ diện theo mặt phẳng này.

3. Trong một tam giác đều, lấy góc phẳng ở đỉnh là $\alpha$ và độ dài cạnh bên là $a$. Tìm diện tích mặt cắt ngang đi qua cạnh đáy và điểm giữa của gân bên đối diện.
