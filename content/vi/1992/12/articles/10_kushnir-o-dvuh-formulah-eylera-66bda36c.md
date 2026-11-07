---
id: 1992-12-kushnir-o-dvuh-formulah-eylera-66bda36c
issue: kvant_1992_12
year: 1992
number: "12"
title: Về hai công thức Euler
authors:
  - Кушнир И. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 45
page_last: 48
page_labels: 43-46
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 8993c61945a76d9badf25b0f4a31d196955cab33ea204a3151969ce0fdd50c37
prompt_sha256: draft-1
translated_from: content/ru/1992/12/articles/10_kushnir-o-dvuh-formulah-eylera-66bda36c.md
source_content_sha256: e96b6584b2aa0020bd4d10f47e6bb85b958b01748d13a2018a56f4d257e564df
translation_model: draft
translation_run: vi-draft-gaps-2026-11-07
translation_quality: draft
---

⟦folio 43⟧

---
running_head:
folio:
---

Về hai công thức Euler
I. KUSHNIR

Đa giác không có ít đỉnh hơn một hình tam giác, vì vậy theo một nghĩa nào đó, nó là đa giác đơn giản nhất. Tuy nhiên, tam giác này dường như là vô tận: dù bạn nhìn vào phía nào, chắc chắn bạn sẽ khám phá ra một số tính chất hữu ích. Các công thức Euler, sẽ được thảo luận ở đây, mô tả thêm hai sự kiện nữa từ tập hợp các tính chất phong phú nhất gắn liền với hình hình học này.

Gọi $X$ là một điểm tùy ý của mặt phẳng, $X_a, X_b, X_c$ hình chiếu của nó lên các cạnh $BC, AC, AB$ của tam giác $ABC$. Tam giác $X_aX_bX_c$ được gọi là nedal.

Công thức đầu tiên của Euler thiết lập mối liên hệ giữa diện tích $S$ của tam giác $ABC$ và diện tích $S_X$ của tam giác sư phạm:

$$S_X = \frac{1}{4} S \left| 1 - \frac{OX^2}{R^2} \right|$$

(ở đây $O$ và $R$ là tâm và bán kính của đường tròn ngoại tiếp tam giác $ABC$).

Để chứng minh công thức này chúng ta cần hai bổ đề.

Bổ đề 1. Nếu chúng ta mở rộng các đoạn $AX, BX$ và $CX$ đến giao điểm với đường tròn ngoại tiếp của tam giác $ABC$, thì tam giác thu được $A'B'C'$ sẽ giống với tam giác nedal.

Bài tập 1. Cho điểm $X$ di chuyển song song với một cạnh của tam giác $ABC$. Vị trí tương đối của tam giác sư phạm và tam giác $ABC$ và $A'B'C'$ thay đổi như thế nào?

Bằng chứng. Đầu tiên hãy để $X$ nằm bên trong tam giác này (hình 1). Điểm $X, X_b, A$ và $X_c$ nằm trên cùng một đường tròn, theo

⟦folio 44⟧

---
running_head:
folio:
---

vì chúng tạo thành hai tam giác vuông có chung cạnh huyền. Do đó, các góc $XX_bX_c$ và $XAX_c$ bằng nhau, giống như các góc treo trên một cung. Tương tự, các điểm $X, X_b, C$ và $X_a$ nằm trên cùng một đường tròn và các góc $X_aX_bX_c$ và $X_aCX$ bằng nhau. Nhưng góc $A'B'B$ bằng góc $A'AB$, vì nó nằm trên cùng một cung của đường tròn được mô tả xung quanh $\Delta ABC$ và góc $BB'C'$ bằng góc $BCC'$ vì lý do tương tự. Vì vậy $\angle A'B'C' = \angle X_aX_bX_c$. Tương tự, người ta chứng minh rằng các góc $X_bX_aX_c$ và $B'A'C'$ bằng nhau. Khi đó các tam giác $X_aX_bX_c$ và $A'B'C'$ đồng dạng ở hai góc.

Các thông báo tương tự như khi xem xét trường hợp này cho phép chúng ta xác minh tính hợp lệ của Bổ đề 1 khi điểm $X$ nằm trên cạnh của tam giác $ABC$ (hình 2) và khi điểm $X$ nằm ngoài tam giác $ABC$, nhưng bên trong đường tròn ngoại tiếp của nó (hình 3).

Bài tập 2. Tự mình chứng minh các trường hợp này.

Bây giờ đặt điểm $X$ nằm ngoài đường tròn ngoại tiếp tam giác $ABC$ (hình 4). Điểm $X, X_a, C, X_b$ nằm trên cùng một đường tròn; do đó $\angle XX_bX_a = \angle XCX_a$. Mặt khác, các điểm $X, X_c, X_b$, A cũng nằm trên cùng một đường tròn nên $\angle XAB = \angle XX_bX_c$. Nhưng $\angle XAB = \angle A'CB$, $\angle A'B'C' = \angle A'CC' = \angle A'CB - \angle C'CB = \angle XX_bX_c - \angle XX_bX_a = \angle X_aX_bX_c$ đến từ đâu.

Việc còn lại là chứng minh sự bằng nhau của hai góc bất kỳ còn lại của tam giác $A'B'C'$ và tam giác sư phạm. Hãy để chúng tôi chứng minh rằng $\angle X_bX_aX_c = \angle C'A'B'$.

Hình chữ nhật $XX_aC$ bằng tổng ba góc $-XX_aX_b, X_bX_aX_c$ và $X_cX_aC$:
$$\pi/2 = \angle XX_aX_b + \angle X_bX_aX_c + \angle X_cX_aC. \quad (*)$$

Từ đường tròn đi qua các điểm $X, X_a, C$ và $X_b$ ta thấy rõ $\angle XX_aX_b = \angle XCX_b$. Mặt khác, từ đường tròn đi qua các điểm $X, X_a, B$ và $X_c$ ta có $\angle X_cX_aB = \angle X_cX_B$, và từ tam giác vuông $XX_cB$ ta có $\angle X_cX_B = \pi/2 - \angle B'BX_c$. Nhưng $\angle B'BX_c = \angle B'BA = \angle B'CA = \angle B'CC' + \angle C'CA = \angle B'CC' + \angle XCX_b$. Thay vào công thức (*), ta được
$$\pi/2 = \angle XCX_b + \angle X_bX_aX_c + \pi/2 - \angle B'CC' - \angle XCX_b,$$
Ở đâu
$$\angle X_bX_aX_c = \angle B'CC',$$
Nhưng
$$\angle B'CC' = \angle C'A'B'.$$

Vì vậy, trong trường hợp này, Bổ đề 1 đúng.

Bổ đề 2. Tam giác $BXC$ và $B'XC'$ tương tự nhau.

Bằng chứng. Đặt $X$ nằm bên trong tam giác $ABC$ (hình 1). Khi đó các góc $C'CB$ và $C'B'B$ bằng nhau, giống như các góc mặt dây chuyền nằm trên một cung; tương tự, các góc $B'C'C$ và $B'BC$ bằng nhau.

Nếu $X$ nằm ngoài tam giác $ABC$, thì những tam giác này được tạo thành bởi hai đường cắt và do đó, tương tự nhau (tại sao?).

Bây giờ cuối cùng chúng ta cũng có thể chứng minh được công thức đầu tiên của Euler.

⟦folio 45⟧

---
running_head:
folio:
---

$R_X$ là bán kính của đường tròn ngoại tiếp tam giác $X_aX_bX_c$. Biểu thị diện tích của tam giác $ABC$ và tam giác bàn đạp theo các cạnh và bán kính của các đường tròn ngoại tiếp chúng, chúng ta thu được:

$$\frac{S_X}{S} = \frac{R}{R_X} \cdot \frac{X_bX_c \cdot X_aX_c \cdot X_aX_b}{BC \cdot AC \cdot AB}.$$

Theo Bổ đề 1, các tam giác $A'B'C'$ và $X_aX_bX_c$ tương tự nhau, do đó

$$R:R_X = B'C' : X_bX_c$$

Và

$$\frac{S_X}{S} = \frac{B'C' \cdot X_aX_b \cdot X_aX_c}{BC \cdot AC \cdot AB}.$$

Từ đường tròn đi qua các điểm $X_a$, $X$, $X_b$, $C$, ta có

$$X_aX_b = CX \sin \angle X_bCX_a = CX \frac{AB}{2R}.$$

Tương tự như vậy

$$X_aX_c = BX \sin \angle X_aBX_c = BX \frac{AC}{2R}$$

Thay vào công thức tính tỉ số diện tích, ta được

$$\frac{S_X}{S} = \frac{1}{4R^2} \cdot \frac{B'C'}{BC} \cdot BX \cdot CX.$$

Theo Bổ đề 2 $B'C' : BC = B'X : CX$, do đó

$$\frac{S_X}{S} = \frac{1}{4R^2} B'X \cdot BX.$$

Nhưng

$$B'X \cdot BX = |R - OX| \cdot (R + OX) = |R^2 - OX^2|$$

(chứng minh điều đó!). Kể từ đây,

$$S_X = \frac{S}{4} \left| 1 - \frac{OX^2}{R^2} \right|.$$

Như vậy ta đã chứng minh được công thức đầu tiên của Euler.

Bài tập 3. Chứng minh rằng nếu điểm $X$ nằm trong đường tròn ngoại tiếp tam giác $ABC$ thì bất đẳng thức sau đúng:

a) $S_X \leq S/4$,

b) $\frac{d_bd_c}{bc} + \frac{d_a d_c}{ac} + \frac{d_a d_b}{ab} \leq \frac{1}{4}$,

trong đó $a, b, c$ là độ dài cạnh $BC, AC, AB$ của tam giác $ABC$, $d_a, d_b, d_c$ là khoảng cách từ $X$ đến các cạnh tương ứng.

Từ công thức này cũng suy ra rằng nếu điểm $X$ nằm trên đường tròn ngoại tiếp tam giác $ABC$ thì các điểm $X_a$, $X_b$ và $X_c$ nằm trên cùng một đường thẳng (đường thẳng Simson). Thật vậy, trong trường hợp này $OX = R$, tức là $S_X = 0$.

Bây giờ chúng ta hãy chứng minh công thức thứ hai của Euler liên quan đến bán kính ngoại tiếp và ngoại tiếp của một tam giác. Đặt $J$ là tâm đường tròn ngoại tiếp của tam giác $ABC$, $r$ bán kính của nó; $O$ và $R$, như trước đây, là tâm và bán kính của đường tròn ngoại tiếp nó. Sau đó

Puc. 4.

Puc. 5.

⟦folio 46⟧

---
running_head:
folio:
---

$$OJ^2 = R^2 - 2Rr.$$
Bổ đề. Cho vòng tròn treo tiếp xúc với các cạnh BC, AC và AB của tam giác ABC lần lượt tại các điểm $K_a, K_b, K_c$ (hình 5). Khi đó diện tích tam giác $K_aK_bK_c$ liên hệ với diện tích tam giác ABC là $r:2R$.

Thật vậy, với diện tích $S_J$ của tam giác $K_aK_bK_c$ ta có:

$$S_J = \frac{1}{2} r^2 (\sin BAC + \sin ABC) + \sin ACB) = \frac{r^2}{4R} (a + b + c).$$

Xét rằng $S = r(a + b + c)/2$, chúng ta thu được mối quan hệ cần thiết:

$$\frac{S_J}{S} = \frac{2r^2(a + b + c)}{4R(a + b + c)} = \frac{r}{2R}.$$

Bây giờ chúng ta chứng minh công thức thứ hai của Euler. Để làm điều này, hãy viết công thức đầu tiên của Euler cho điểm X trùng với điểm J:

$$S_J = \frac{S}{4} \left(1 - \frac{OJ^2}{R^2}\right).$$

Từ bổ đề vừa chứng minh ta có

$$S_J = \frac{Sr}{2R},$$

tư thế

$$\frac{r}{R} = \frac{1}{2R^2} (R^2 - OJ^2)$$

(Để bắt đầu, xem trang 37)

tất cả những con số,” Mèo nói và bắt đầu tắm rửa lại – Đó là điều mà người ta gọi là “tự nhiên”. Đúng, trong số đó có một số cái thực sự đơn giản...

Alice định hỏi những “số nguyên tố thực sự” này là gì, nhưng rồi Không-Thật-Dina tuyên bố với niềm đam mê bất ngờ:

- Tôi sẽ chỉ gọi số tự nhiên! Mỗi người trong số họ đều tuyệt vời theo cách riêng của mình!

Và dần dần, cùng với động tác tắm rửa của mình, Mèo bắt đầu đếm:

- Một, hai, ba, bốn, năm, sáu, bảy, tám, de...

- Đủ! - Alice hét lớn, nhận ra mình lại đang đối mặt với vô cực. Và vì Not-Quite-Dina vẫn đang ngồi lộn ngược, Alice lặp lại câu hỏi thứ hai:

- Sao cậu lại lộn ngược thế?

Alice không bao giờ quên những câu hỏi mà cô chưa nhận được đáp số!...

$$OJ^2 = R^2 - 2Rr.$$
Bài tập 4. Chứng minh rằng $R \geq 2r$.

Điều thú vị là đối với khối đa diện, một công thức tương tự như công thức thứ hai của Euler vẫn đúng:

$$OJ^2 = R^2 - 2R_0r_0,$$

trong đó $O$ là tâm của hình cầu ngoại tiếp, $R$ là bán kính của nó, $J_0$ là tâm của đường tròn nội tiếp một trong các mặt, $r_0$ là bán kính của nó, $R_0$ là bán kính của đường tròn nội tiếp xung quanh mặt này.

Bài tập 5. Chứng minh công thức thứ hai của Euler cho khối lập phương.

6. Đường tròn nội tiếp tam giác ABC tiếp xúc với đường trung bình của nó. Tìm góc BAC biết rằng tâm của đường tròn ngoại tiếp nằm trên đường tròn nội tiếp.

7. Tạo một hình tam giác dọc theo $R, r, a$.

8. Các cạnh của một tam giác tạo thành một cấp số nhân $b > a > c$. Chứng minh rằng khoảng cách từ đỉnh đối diện với cạnh trung bình của tam giác là trung bình hình học giữa đường kính của đường tròn nội tiếp và bán kính của đường tròn ngoại tiếp.

9. Chứng minh rằng nếu $h$ và $l$ là đường cao và đường phân giác vẽ từ đỉnh A của tam giác ABC thì $h/l \geq \sqrt{2r/R}$.

10. Chứng minh rằng $S_X \leq (S_a + S_b + S_c)/3$, trong đó $S_a, S_b, S_c$ là diện tích của các tam giác $AX_bX_c, BX_aX_c, CX_bX_c$.

11. Trong tam giác vuông ABC, điểm X là trọng tâm của tam giác $X_aX_bX_c$. Chứng minh rằng $S_X = 2S/9$.
