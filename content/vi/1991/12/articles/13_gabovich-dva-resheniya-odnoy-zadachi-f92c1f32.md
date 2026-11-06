---
id: 1991-12-gabovich-dva-resheniya-odnoy-zadachi-f92c1f32
issue: kvant_1991_12
year: 1991
number: "12"
title: Hai lời giải một bài toán
authors:
  - Габович И. Г.
rubric: shkola-v-kvante
page_first: 44
page_last: 46
page_labels: 42-44
lang: vi
source: kvant_digital
extraction: vision
content_sha256: be98642cc732d8290c0b2fe39d8376ec08043cd104be7123935c7198c5ad960e
prompt_sha256: draft-1
translated_from: content/ru/1991/12/articles/13_gabovich-dva-resheniya-odnoy-zadachi-f92c1f32.md
source_content_sha256: db56217ce336e23b5cb75298a5488f2a021cdb2e48eb0abd202fd71e68a6d348
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 42⟧

Hai lời giải một bài toán

Điều khá thường xuyên xảy ra là với lời giải hình học bài toán thu được hai đáp số (theo quy luật, điều này là do sự hiện diện của hai nghiệm trong phương trình bậc hai). Câu hỏi được đặt ra một cách tự nhiên: cả hai lời giải có thỏa mãn tất cả các điều kiện của bài toán không?

Hãy để chúng tôi minh họa điều này bằng một ví dụ hiện đại.

Bài toán 1. Tìm cạnh AB của tam giác ABC nếu AC=6, BC=4, ∠BAC=30°.

Lời giải. Đặt AB=x. Viết định lý cosine cho tam giác ABC, sau khi biến đổi ta thu được phương trình bậc hai của x:

$$x^2 - 6\sqrt{3}x + 20 = 0,$$

từ đâu $x=3\sqrt{3} \pm \sqrt{7}$.

Trong trường hợp này, cả hai nghiệm của phương trình đều đúng đối với chúng ta, vì sự tồn tại của hai tam giác thỏa mãn các điều kiện bài toán nên rất dễ kiểm chứng bằng cách thực hiện phép dựng tương ứng (hình 1).

bài toán tiếp theo khó hơn một chút.

Bài toán 2. Một đường tròn nội tiếp trong một tam giác có chu vi 20. Đoạn tiếp tuyến của đường tròn song song với đáy, bao quanh các cạnh của tam giác, bằng 2,4. Tìm đáy của hình tam giác.

Lời giải. Gọi EF là tiếp tuyến của đường tròn nội tiếp song song với đáy AC của tam giác ABC (hình 2). Từ sự giống nhau của các tam giác BAC và BEF, suy ra rằng nửa chu vi p và p' của chúng liên hệ với nhau như các cạnh tương ứng, tức là.

$$\frac{p'}{p} = \frac{EF}{AC}.$$

(*)

Đồng thời $p' = BG = p - AC$.

Đặt AC=x. Từ đẳng thức (*) ta có:

$$\frac{10-x}{10} = \frac{12}{5x}$$

(**)

từ đâu $x=4$ và $x=6$.

Hai đáp số nữa!

Ở đây chúng ta không thể giải thích sự xuất hiện của hai đáp số đơn giản như khi giải bài toán 1. Vì vậy, hãy thử một phương pháp khác.

Hãy đặt EF=y. Từ thư từ (**), chúng tôi nhận được:

$$y = \frac{1}{10}x(10-x).$$

Ở phía bên phải của đẳng thức này có một hàm bình phương, đồ thị của nó được hiển thị bằng hình 3. Hàm này nhận các giá trị dương ​​tại $x \in (0; 10)$, có giá trị tối đa là 2,5 tại $x=5$. Hàm lấy bất kỳ giá trị nào từ khoảng (0; 2.5) hai lần - tại các điểm đối xứng với điểm $x=5$.

Do đó, chúng ta thấy rằng với $y=2,4$ có hai giá trị $x$ cho lời giải cho bài toán.

⟦folio 43⟧

---
running_head:
folio:
---

Nhân tiện, nghiên cứu đơn giản này cho thấy rằng với bất kỳ $y \in (0; 2,5)$ nào cũng có hai lời giải bài toán, với $y = 2,5$ thì có một, và với $y > 2,5$ thì không có lời giải. Chúng ta có thể làm tất cả những điều này ở dạng tổng quát, giả sử rằng chu vi của tam giác bằng $2p$ và đoạn $EF$ bằng $a$. Kết quả là, chúng ta đạt được các điều kiện trên $a$ và $p$ trong đó bài toán có hai, một hoặc không có lời giải.

Bài tập 1. Hãy tự làm việc này.

Hãy xem một ví dụ khác.

Bài toán 3. Thiết kế hình thang của ván lợp là 10, diện tích là $S = 48$. Tìm chiều cao $h$ của hình thang này.

Lời giải. Hãy vẽ chiều cao $BE$ trong hình thang của chúng ta. Đặt $AD = a, BC = b$ (hình 4). Sau đó $S = \frac{a+b}{2}h, BE = (a+b)/2$ (bạn tự xem phần này) và $d^2 = h^2 + \left(\frac{a+b}{2}\right)^2$. Hãy biểu thị $(a+b)/2$ bằng $k$. Các văn bản tương ứng trước đây đưa ra một hệ phương trình:

$$\begin{cases} hk = S, \\ h^2 + k^2 = d^2, \end{cases}$$

giải mà ta thu được hai giá trị $h$:

$$h_{1,2} = \sqrt{\frac{d^2 \pm \sqrt{d^4 - 4S^2}}{2}}.$$

(Trong bài toán $h_1 = 6, h_2 = 8$ của chúng tôi.) Trong trường hợp này, điều kiện cần thiết để giải được bài toán ngay lập tức hiển thị: $d \geq \sqrt{2S}$.

Bây giờ chúng ta hãy biểu thị $d^2$ theo $h$:

$$d^2 = \frac{S^2}{h^2} + h^2.$$

Hàm ở bên phải của phương trình này trả về ở mức $h > \sqrt{S}$, giảm ở $h < \sqrt{S}$ và đạt mức tối thiểu là $2S$ tại $h \leq \sqrt{S}$.

Hơn nữa, hàm này nhận mỗi giá trị lớn hơn $2S$ hai lần. Do đó, với $d > \sqrt{2S}$ có hai hình thang thỏa mãn điều kiện, với $d = \sqrt{2S}$ có ​​một, và với $d < \sqrt{2S}$ không có hình thang nào.

Bây giờ hãy xem xét hai hình lập thể bài toán.

Bài toán 4. Một hình nón được mô tả xung quanh quả bóng. Tìm góc nghiêng của đường sinh của hình nón với mặt phẳng đáy

⟦folio 44⟧

---
running_head:
folio:
---

Biết tỉ số thể tích của hình nón và hình cầu là 3,6.

Lời giải. Phần trục được coi là tổ hợp các hình bài toán là một tam giác đều có đường tròn nội tiếp (hình 5), bán kính của hình đó bằng bán kính của quả cầu.

Đặt $OO_1 = r$, $\angle SBA = \alpha$ ($0 < \alpha < \pi/2$), ta thấy rằng $BO = r \text{ctg} \alpha/2$, $SO = r \text{ctg} \frac{\alpha}{2} \text{tg} \alpha$. Viết tỷ số thể tích của hình nón và quả bóng, ta thu được phương trình tương đối $\alpha$:

$$\frac{1}{4} \text{ctg}^3 \frac{\alpha}{2} \cdot \text{tg} \alpha = 3,6.$$

Đối với lời giải của nó, thật thuận tiện khi thực hiện thay thế $t = \text{tg} \frac{\alpha}{2}$, dẫn đến phương trình

$$7,2t^4 - 7,2t^2 + 1 = 0,$$

từ đâu $t_1 = \frac{\sqrt{6}}{6}, t_2 = \frac{\sqrt{30}}{6}$. Kết quả là chúng ta thu được hai giá trị của góc độc quyền: $\alpha_1 = 2 \text{arctg} \sqrt{6}/6$ và $\alpha_2 = 2 \text{arctg} \sqrt{30}/6$.

Bây giờ hãy giải thích nguyên nhân gây ra điều này. Đầu tiên là “trên ngón tay”. Có thể mô tả vô số hình nón xung quanh một quả bóng. Nếu hình nón “hẹp và rất cao” hoặc “rất rộng nhưng không cao” (hình 6), tỷ lệ thể tích của hình nón và quả bóng là rất lớn. Bằng trực giác, rõ ràng rằng đối với một số giá trị của góc $\alpha$, tỷ lệ này là tối thiểu. Đường dẫn có giá trị tối thiểu này là $k_0$. Khi đó ở $k > k_0$ sẽ có các hình nón - “hẹp và cao” và “rộng và thấp”, trong đó tỷ lệ thể tích sẽ bằng $k$.

Bây giờ chúng ta hãy tiến hành một nghiên cứu chính xác. Chúng tôi đã thấy điều đó

$$k = \frac{1}{4} \text{ctg}^3 \frac{\alpha}{2} \cdot \text{tg} \alpha.$$

Giới thiệu một biến mới $x = \text{tg}^2 \frac{\alpha}{2}$, chúng ta thu được $k = \frac{1}{2x(1-x)}$ cho $0 < x < 1$. Mẫu số là hàm bậc hai của $x$. Do đó hàm $k$ giết chết

từ +∞ đến 2 tại $0 < x < 1/2$ và tăng không giới hạn ở $1/2 < x < 1$. Chúng ta thấy rằng tại $k > 2$ có ​​hai giá trị $x$ mà hàm của chúng ta bằng $k$. Và điều này có nghĩa là với bất kỳ $k > 2$ nào (một phần, đối với $k = 3,6$) có hai hình nón thỏa mãn các điều kiện.

Tất nhiên, bài toán được phân tích đại diện cho các trường hợp đơn giản nhất có thể phát sinh với lời giải hình học bài toán, vì “phần nổi của tảng băng trôi” được đưa ra. Đôi khi, khi nhận được một số đáp số, bạn phải thực hiện một nghiên cứu kỹ lưỡng hơn về đường chân trời, trong thời gian đó đôi khi hằng số lời giải bị loại bỏ. Chúng tôi chỉ muốn chứng tỏ làm thế nào số lượng hình học bài toán có thể được quy về các bài toán nghiên cứu một số hàm số nhất định. Tóm lại, chúng tôi khuyên bạn nên tự mình giải quyết vấn đề bài toán sau.

Trận chiến

2. Qua điểm $P$ của đường kính hình tròn bán kính $R$ vẽ một dây cung $AB$ tạo thành một góc $60^\circ$ với đường kính. Tìm $BP$ nếu $AP = a$ (xem xét tất cả các trường hợp có thể xảy ra).

3. Tỉ số bán kính của một quả bóng ngoại tiếp một đường thẳng tứ giác đều với cạnh đáy là $3/4$. Tìm góc giữa mặt bên và diện tích đáy.

4. Tỉ số bán kính của một quả bóng ngoại tiếp một đường thẳng tam giác đều với cạnh đáy là $k$. $k$ có bài toán lời giải ở những giá trị nào? Sẽ giải quyết được bao nhiêu tùy theo $k$?

I. Gabovich
