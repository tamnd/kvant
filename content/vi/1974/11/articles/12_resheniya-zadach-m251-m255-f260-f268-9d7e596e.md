---
id: 1974-11-resheniya-zadach-m251-m255-f260-f268-9d7e596e
issue: kvant_1974_11
year: 1974
number: "11"
title: Lời giải bài toán M251—M255; F260—F268
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 44
page_last: 52
page_labels: 42-50
tag: 4TC4
lang: vi
source: kvant_digital
extraction: vision
content_sha256: b16b6504a305816bb9bd143b89204f205e5e2d10b0eadc010ff81a4413a02f3f
prompt_sha256: draft-1
translated_from: content/ru/1974/11/articles/12_resheniya-zadach-m251-m255-f260-f268-9d7e596e.md
source_content_sha256: a73af4a0205cffd82f96336d0c20b60abc6353742d8eb28a6eafaacff0dc3513
translation_model: draft
translation_run: vi-draft-2026-11-03
translation_quality: draft
---

⟦folio 42⟧

Lời giải bài toán
M251—M255; F260—F268

M251. Cho n chip có nhiều màu, không quá n/2 chip cho mỗi màu. Hãy để chúng tôi chứng minh rằng chúng có thể được xem xét trên một vòng tròn mak sao cho không có hai chip cùng màu nào liền kề nhau.

Đầu tiên lời giải: Chúng ta sẽ giả sử rằng nếu có hai con chip cùng màu cạnh nhau thì chúng được nối với nhau bằng một vòng cung. Khi đó chúng ta cần chứng minh rằng có sự sắp xếp các con chip như vậy trên một vòng tròn trong đó không có bạn bè nào.

Hãy sắp xếp các con chip thành một vòng tròn; Chúng ta hãy chứng minh rằng các con chip có thể được sắp xếp lại sao cho số lượng trong cách sắp xếp mới giảm đi.

Trên thực tế, chẳng hạn, trong một cách sắp xếp, hai quân đen được nối với nhau bằng một vòng cung. Khi đó anh ta chắc chắn sẽ tìm thấy hai con chip đen trên vòng tròn, đứng cạnh nhau. Thật vậy, nếu bên cạnh mỗi quân đen có những quân đen và hai quân đen nữa đứng cạnh nhau thì sẽ có hơn một nửa số quân đen, và điều này mâu thuẫn với điều kiện.

Bây giờ chúng ta hãy lấy một trong những quân không phải màu đen đã đề cập và đặt nó vào giữa hai quân đen. Đồng thời, số lượng bạn bè trong cơ chế mới một lần nữa sẽ giảm đi. Vì số người bạn trong cách sắp xếp không thể nhỏ hơn 0 nên cuối cùng chúng ta sẽ có được sự sắp xếp các con chip trên một vòng tròn không có bạn bè.

Thứ hai lời giải. Ta sẽ chứng minh khẳng định bài toán bằng quy nạp theo số k có các màu khác nhau. Khi k=2, mệnh đề hiển nhiên: trong trường hợp này phải có $\frac{n}{2}$ chip của mỗi màu và chúng có thể được sắp xếp theo thứ tự màu đen. Nếu chúng ta có k=3 mã thông báo màu, chẳng hạn như đỏ, đen và xanh lục, chúng ta sẽ hành động như thế này. Hãy bắt đầu đặt những con chip nhiều nhất, chẳng hạn như những con chip màu đỏ, lần lượt ở những vị trí kỳ lạ. Khi hết chip đỏ, chúng ta sẽ tiếp tục đặt chip đen vào những vị trí lẻ. Rõ ràng là chúng ta sẽ sử dụng các chip có hai màu để loại bỏ tất cả các khoảng trống lẻ, đặt phần còn lại của các chip màu đen vào giữa các chip màu đỏ và đặt các chip màu xanh lá cây vào các khoảng trống (chẵn) (hình 1).

Nếu số chip là k ≥4 thì anh ta sẽ tìm hai màu sao cho sẽ không có nhiều hơn n/2 chip của hai màu này. Bằng cách sơn lại các mã thông báo này thành một màu, chúng ta thu được một bộ mã thông báo gồm (k-1) màu mà giả thuyết quy nạp được thỏa mãn. Bằng cách sắp xếp chúng xung quanh vòng tròn sao cho đáp ứng điều kiện và trở về màu ban đầu, chúng ta thu được sự sắp xếp mong muốn của các chip gồm k màu.

Thứ ba lời giải. Hãy lấy n hiệp sĩ, trao cho mỗi hiệp sĩ một mã thông báo và tuyên bố hai hiệp sĩ là kẻ thù nếu họ đạt được các mã thông báo cùng màu và bạn bè nếu họ có các mã thông báo khác nhau. Khi đó điều kiện bài toán M250, a; do đó, các hiệp sĩ có chip có thể được đặt xung quanh một bàn tròn.

V. L. Gutemacher

Lời giải bài toán M252 xem bài viết của A. A. Egorov “Lưới và đa giác đều”, mà chúng tôi sẽ đặt ở «Kvant» số 12 cho năm 1974.

M253. Ba điểm được cho trên mặt phẳng, đó là các tâm tương ứng của đường nội tiếp, đường ngoại tiếp và một trong các đường tròn bên ngoài của tam giác. Làm thế nào để xây dựng lại một hình tam giác từ dữ liệu này?

(Nhắc lại rằng đường tròn ngoài của một tam giác được gọi là đường tròn tiếp xúc với một cạnh của tam giác và kéo dài bởi hai cạnh kia.)

Chúng ta hãy biểu thị các đỉnh của tam giác mong muốn bằng các chữ cái A, B và C, và tâm của các đường tròn ngoại tiếp, nội tiếp và đùn bằng các chữ cái lần lượt là O, O₁ và O₂ (hình 2).

Lưu ý rằng đường thẳng O₁O₂ đi qua tâm của đường tròn nội tiếp và ngoại tiếp là phân giác góc A của tam giác ABC, nghĩa là đường thẳng O₁O₂ phải đi qua đỉnh A. Dễ dàng

⟦folio 43⟧

Hình 2.
nhận ra rằng $\Rightarrow O_1BO_2 = \Rightarrow O_1CO_2 = \pi/2$. Do đó, các điểm $B$ và $C$ nằm trên đường tròn $s$ có đường kính $O_1O_2$; Hãy biểu thị tâm của vòng tròn này (tức là giữa đoạn $O_1O_2$) bằng cây sồi $S$. Vì điểm $O$ là tâm của đường tròn ngoại tiếp nên nó nằm trên đường vuông góc đi qua giữa đoạn $BC$. Nhưng đoạn $BC$ là dây cung của đường tròn $s$ nên đường vuông góc này phải đi qua tâm đường tròn $s$, tức là đi qua điểm $S$.

Vì vậy, nếu các điểm $O$ và $S$ không trùng nhau thì đường thẳng $OS$ vuông góc với cạnh $BC$ của tam giác loại trừ và đi qua điểm giữa của nó.

Vẫn cần lợi dụng điểm giao nhau của đường vuông góc đi qua giữa cạnh $BC$ và góc phân giác $A$ (tức là điểm $S$) nằm trên đường tròn ngoại tiếp tam giác $ABC$ (xem hình 2). Do đó, chúng ta có thể dựng một đường tròn (có tâm $O$) từ mô tả (bán kính của nó qua điểm $SO$). Điểm giao nhau thứ hai của đường tròn này với đường thẳng $O_1O_2$ là đỉnh $A$ của tam giác loại trừ. Các điểm mà đường tròn giao với đường tròn $s$ là điểm hạn chế về vị trí của các điểm $O$, $O_1, O_2$ là điểm duy nhất.

L. G. Limanov

M254. Giá trị cao nhất $\sqrt{0,11111\ldots11111}$
với độ chính xác: $a) 100$ chữ số thập phân; $b) 101$ chữ số thập phân; $v) 200$ chữ số thập phân.

Chúng tôi trình bày lời giải, cho phép chúng tôi tính căn bậc này với độ chính xác là 301 chữ số thập phân.

Hãy biến đổi số này như sau:

$$\frac{1}{3} \sqrt{0,999\ldots999} = \frac{1}{3} \sqrt{1-10^{-100}}.$$

Sau đó

$$\sqrt{1-10^{-100}} < 1 - 0,5 \cdot 10^{-100}.$$

Chúng ta hãy tinh chỉnh ước tính này: tìm một số dương $a$ sao cho bất đẳng thức

$$\sqrt{1-10^{-100}} < 1 - 0,5 \cdot 10^{-100} - a \cdot 10^{-200}.$$

Để làm điều này, hãy bình phương cả hai vế của bất đẳng thức (2):

$$1-10^{-100} < 1 + 0,25 \cdot 10^{-200} + a^2 \cdot 10^{-400} - 10^{-100} - 2a \cdot 10^{-200} + a \cdot 10^{-300};$$

đơn giản hóa, chúng tôi nhận được

$$0 < (0,25-2a) + a \cdot 10^{-100} + a^2 \cdot 10^{-200}.$$

Để bất đẳng thức (2) được giữ nguyên, chỉ cần lấy $a=0,125+10^{-102}$. Thật vậy, trong trường hợp này các giá trị của $a$ và biểu thức $0,25-2a+a \cdot 10^{-100}$ là dương.

Vì vậy, chúng tôi đi đến ước tính:

$$\sqrt{1-10^{-100}} < 1 - 0,5 \cdot 10^{-100} - 0,125 \cdot 10^{-200} - 10^{-302}.$$

Để đánh giá số $\sqrt{1-10^{-100}}$ trước tiên hãy chọn số $b$ sao cho bất đẳng thức đúng

$$\sqrt{1-10^{-100}} > 1 - 0,5 \cdot 10^{-100} - b \cdot 10^{-200},$$

tương đương

$$0 > (0,25-2b) + b \cdot 10^{-100} + b^2 \cdot 10^{-200}.$$

Để bất đẳng thức (4) được giữ nguyên, chỉ cần đặt $b=0,125+10^{-101}$ là đủ.

Chúng tôi nhận được ước tính sau:

$$\sqrt{1-10^{-100}} > 1 - 0,5 \cdot 10^{-100} - 0,125 \cdot 10^{-200} - 10^{-301}.$$

Từ ước tính (3) và (5) suy ra rằng

$$0,9\ldots949\ldots98 < \sqrt{1-10^{-100}} < 0,9\ldots949\ldots98$$

Cho đến lúc đó chúng tôi nhận được

$$\sqrt{0,11\ldots11} = 0,33\ldots3166\ldots62499\ldots9\ldots,$$

và tất cả 301 chữ số thập phân đều đúng.

Một lời giải tương tự như bài toán này đã được gửi bởi độc giả S. Domoryad của chúng tôi.

S. T. Bercolako

⟦folio 44⟧

Hình 3. Những quả cầu mây tràn ngập ánh sáng là những quả cầu mà từ đó bạn có thể vẽ tiếp tuyến với một quả cầu khác.

M255. AB và CD là các tiếp tuyến khác nhau của hai quả bóng cho trước (A và C thuộc về các bề mặt của cùng một quả bóng, B và D thuộc các bề mặt khác). Chứng minh rằng hình chiếu của các đoạn AC và BD lên đường thẳng đi qua tâm các quả bóng là bằng nhau.

Đặt $O_1$ và $O_2$ là tâm của các quả bóng, $|O_1A| = |O_1C| = r_1$ và $|O_2B| = |O_2D| = r_2$ bán kính của chúng, $|O_1O_2| = d$, $|AB| = l$, $|CD| = m$, $\Rightarrow AO_1O_2 = \varphi$, $\Rightarrow CO_1O_2 = \psi$.

Khi đó độ dài của đoạn AC chiếu lên đường thẳng $O_1O_2$ bằng
$$\|AO_1\| \cos \varphi - |CO_1| \cos \psi| = |r_1 \cos \varphi - r_1 \cos \varphi|.$$ (1)

Theo định lý cosine cho $\triangle AO_1O_2$ (hình 3)
$$|AO_2|^2 = r_1^2 + d^2 - 2r_1 d \cos \varphi.$$ (2)

Vì góc $ABO_2$ (giữa tiếp tuyến và bán kính) là góc vuông nên
$$|AO_2|^2 = |AB|^2 + |B_2O|^2 = l^2 + r_2^2.$$ (3)

Từ (2) và (3) chúng ta thu được
$$2dr_1 \cos \varphi = r_1^2 + d^2 - r_2^2 - l^2.$$ (4)

Tương tự tìm
$$2dr_1 \cos \psi = r_1^2 + d^2 - r_2^2 - m^2.$$ (5)

Từ (1), (4) và (5) suy ra hình chiếu của đoạn AC lên $O_1O_2$ có độ dài
$$\frac{|l^2 - m^2|}{2d}.$$

Rõ ràng là đoạn hình chiếu BD có cùng độ dài.

Hãy để chúng tôi trình bày thêm một lời giải trong số bài toán này, nó thể hiện rõ hơn nền tảng hình học của nó. Tương tự mặt phẳng của bài toán M255 (hình 4) quy định rằng các tiếp tuyến phải được đặt sao cho trung điểm của chúng chiếu tới cùng một điểm trên đường thẳng $O_1O_2$, nghĩa là tất cả trung điểm của các tiếp tuyến với hai quả bóng đã cho phải nằm trong cùng một mặt phẳng, vuông góc với đường xu. Ta sẽ chứng minh một phát biểu tổng quát hơn.

Hình 4. Hình chiếu của các đoạn AC và BD lên tâm đường thẳng là như nhau nếu trung điểm AB và CD được chiếu vào cùng một điểm P.

Định lý. Tất cả các điểm M, tiếp tuyến của hai quả bóng cho trước có cùng chiều dài, nằm trong cùng một mặt phẳng, vuông góc với đường xu $O_1O_2$ và cắt nhau $O_1O_2$ tại điểm cao nhất P, sao cho
$$|PO_1|^2 - |PO_2|^2 = r_1^2 - r_2^2.$$ (6)

Lưu ý rằng đẳng thức cuối cùng xác định duy nhất vị trí của điểm P trên đường $O_1O_2$: nếu trên đường $O_1O_2$ ta chọn hệ tọa độ sao cho các điểm $O_1$ và $O_2$ nhận tọa độ 0 và d thì tọa độ x của điểm P được xác định duy nhất từ ​​phương trình $x^2 - (x - d)^2 = r_1^2 - r_2^2$:
$$x = \frac{r_1^2 - r_2^2 + d^2}{2d}.$$

Bây giờ chúng ta hãy chứng minh định lý. Điều đáng chú ý nhất ở đây là chúng ta có thể lên mặt phẳng ngay lập tức bài toán: xét cho cùng, từ điểm M đến mỗi quả bóng chúng ta có thể vẽ nhiều - cả một “hình nón” - tiếp tuyến, rất indo, có chiều dài bằng nhau và chúng ta luôn có thể chọn những quả nằm trong mặt phẳng $MO_1O_2$ (hình 5). Trong hình 5. Độ dài của tất cả các tiếp tuyến vẽ từ điểm M đến mỗi quả bóng là như nhau.

⟦folio 45⟧

Hình 6. Sự khác biệt về bình phương khoảng cách từ $M$ đến tâm của các đường tròn không đổi. Do đó, điểm $M$ thuộc một đường thẳng nhất định, vuông góc với đường tâm (trục đẳng phương của hai đường tròn).

mặt phẳng (hình 6) cũng chứa hình chiếu $M'$ của điểm $M$ lên đường thẳng $O_1O_2$.

Từ sự bằng nhau của độ dài tiếp tuyến

$$\sqrt{|MO_1|^2 - r_1^2} = \sqrt{|MO_2|^2 - r_2^2}$$

nó theo sau đó

$$|MO_1|^2 - |MO_2|^2 = r_1^2 - r_2^2.$$

Sử dụng thực tế là các tam giác $MM'O_1$ và $MM'O_2$ là hình chữ nhật, ta thu được

$$|M'O_1|^2 - |M'O_2|^2 = r_1^2 - r_2^2,$$

nghĩa là, đối với điểm $M'$, đẳng thức (6) được thỏa mãn như đối với điểm $P$; như chúng tôi đã nói, trong trường hợp này $M'$ phải khớp với $P$. Như vậy, điểm $M$ nằm trong mặt phẳng vuông góc với đường tâm và đi qua điểm $P$, xác định bởi đẳng thức (6) (mặt phẳng này gọi là mặt phẳng đẳng phương của hai mặt cầu đã cho). Định lý đã được chứng minh.

I. F. Sharytsin, N. B. Vasiliev

Tới lời giải bài toán M218. Trong «Kvant» số 4 năm nay, chúng tôi đã cung cấp cho độc giả bản tóm tắt về bài toán M218. Các biên tập viên đã nhận được một số lá thư. lời giải đầy đủ nhất được gửi bởi V. L. Rabinovich.

Chúng ta hãy nhớ lại công thức của bài toán, trình bày đáp số và cho biết ý chính của lời giải.

Bài toán. Với hầu hết $c_n$ với mọi số dương $x_1, \dots, x_n$ thì bất đẳng thức đúng

$$(x_1 + x_2 + \dots + x_n)^2 \geq c_n (x_1 x_2 + x_2 x_3 + \dots + x_n x_1))?$$

Đáp số: $c_2 = 2, c_3 = 3, c_n = 4$ cho $n \geq 4$, trong khi trong trường hợp $n = 2, 3, 4$ bất đẳng thức đúng với mọi $x_1, \dots, x_n$.

Hãy chứng minh rằng bất đẳng thức

$$(x_1 + x_2 + \dots + x_n)^2 \geq 4 (x_1 x_2 + x_2 x_3 + \dots + x_n x_1))$$

(2)

đúng với giá trị dương $x_1, x_2, \dots, x_n$ tại $n \geq 4$.

Với $n = 4$, bất đẳng thức (2) đúng với mọi $x_1, x_2, x_3, x_4$. Trong thực tế,

$$(x_1 + x_2 + x_3 + x_4)^2 - 4 (x_1 x_2 + x_2 x_3 + x_3 x_4 + x_4 x_1) = ((x_1 + x_3) + (x_2 + x_4))^2 - 4 (x_1 + x_3) \times (x_2 + x_4) = (x_1 - x_2 + x_3 - x_4)^2 \geq 0.$$

Hãy chứng minh rằng nếu bất đẳng thức (2) đúng với $n$ số dương thì nó cũng đúng với $(n + 1)$ số dương.

Chúng ta có thể giả sử rằng $x_{n+1}$ là nhỏ nhất trong $x_1, x_2, \dots, x_{n+1}$. Sau đó

$$(2x_1 - x_{n+1}) (2x_n - x_{n+1}) \geq 0.$$

Cộng bất đẳng thức này vào (2), ta được

$$(x_1 + x_2 + \dots + x_n)^2 + x_{n+1}^2 + 4x_1 x_n - 2x_1 x_{n+1} - 2x_{n+1} x_n \geq 4 (x_1 x_2 + x_2 x_3 + \dots + x_{n-1} x_n + x_n x_1),$$

Ở đâu

$$(x_1 + x_2 + \dots + x_n)^2 + 2x_{n+1} (x_1 + x_n) + x_{n+1}^2 \geq 4 (x_1 x_2 + \dots + x_{n-1} x_n + x_n x_1) - 4x_1 x_n + 4x_n x_{n+1} + 4x_{n+1} x_1 = 4 (x_1 x_2 + \dots + x_n x_{n+1} + x_{n+1} x_1),$$

đặc biệt

$$(x_1 + x_2 + \dots + x_{n+1})^2 = (x_1 + \dots + x_n)^2 + 2x_{n+1} (x_1 + x_2 + \dots + x_n) + \dots + x_n) + x_{n+1}^2 > 4 (x_1 x_2 + \dots + x_n x_{n+1} + x_{n+1} x_1).$$

V. L. Gutemacher

F260. Các hướng góc trực tiếp có độ lớn $U_0$ và đường kính $T$ được cung cấp cho đầu vào của mạch (hình 7, a). Chu kỳ quay của xung là $T$ (hình 7, b). Tên của hình vẽ là rất nhiều chu kỳ hướng trên tụ điện, nếu trong khoảng thời gian đó hướng trên tụ thay đổi rất ít.

Khi trạng thái cân bằng được thiết lập trong mạch, hướng và do đó điện tích trên tụ điện sẽ không thay đổi. Tức là sự gia tăng

⟦folio 46⟧

Hình 8.

sạc khi sạc sẽ bằng mức giảm sạc khi sạc.
Khi nạp tụ điện trong thời gian τ thì chiều của tụ điện bằng
$$U_C = U_0 - I_3 r.$$
Vì điện tích trên tụ điện thay đổi rất ít trong khoảng thời gian nên chúng ta có thể coi dòng điện nạp không đổi và bằng
$$I_3 = \frac{\Delta q}{\tau},$$
trong đó $\Delta q$ là sự thay đổi về phí. Như vậy,
$$U_C = U_0 - \frac{\Delta q}{\tau} r.$$ (1)

Khi sạc, tụ điện phóng điện qua điện trở $R$ trong thời gian $T - \tau$, vậy $U_C = I_p R$, dòng điện sạc ở đâu
$$I_p = \frac{\Delta q}{T - \tau}.$$
Vì vậy, trong khi sạc
$$U_C = \frac{\Delta q}{T - \tau} R.$$ (2)

Giải (1) và (2) cùng nhau, ta thu được
$$U_C = U_0 \frac{R\tau}{(R - r)\tau + rT}.$$

F261. Chúng tôi nổi ở bề mặt phân cách giữa hai chất lỏng có mật độ khác nhau, vì vậy chúng tôi đi sâu vào chất lỏng phía dưới đến độ sâu $h$, một loại gia vị molstomic với độ mờ mỏng. Gia vị được đổ đầy chất lỏng phía trên lên trên. Bán kính bên ngoài của hương vị là $R$, bán kính bên trong là $r$. Ở đáy của món ăn, độ sâu của tình bạn của món ăn xuất hiện sau khi có thể chuyển chất lỏng lại với nhau vào đó?

Chúng ta hãy viết điều kiện cân bằng của thủy tinh trong trường hợp đầu tiên (hình 8, a):
$$mg + m_1 g = F_{B1}.$$
Ở đây $m$ là khối lượng của kính, $m_1 = \rho_1 \pi r^2 l$ là khối lượng chất lỏng bên trong kính ($l$ là chiều cao của kính), $F_{B1}$ là lực nổi.

Hình 9.

Nếu một vật nổi trên mặt tiếp giáp giữa hai chất lỏng sao cho trong chất lỏng thứ nhất có một phần của vật có thể tích $V_1$, và trong chất lỏng thứ hai - $V_2$, thì lực nổi bằng
$$F_B = \rho_1 g V_1 + \rho_2 g V_2.$$
Thật vậy, bạn có thể tưởng tượng chia cơ thể thành hai phần dọc theo mặt phân cách giữa các chất lỏng và xem xét từng phần riêng biệt. Tất nhiên, điều này không làm thay đổi vị trí của vật hoặc các lực tác dụng lên nó. Như vậy,
$$F_{B1} = \rho_1 g \pi R^2 (l - h) + \rho_2 g \pi R^2 h.$$
Khi đó điều kiện cân bằng được viết như sau:
$$mg + \rho_1 g \pi r^2 l = \rho_1 g \pi R^2 (l - h) + \rho_2 g \pi R^2 h.$$ (1)

Khi một lỗ xuất hiện ở đáy ly, chất lỏng ở dưới sẽ chảy vào ly, chiếm chỗ của chất lỏng ở trên. Điều này sẽ xảy ra cho đến khi mức của ranh giới chất lỏng trùng với mức của ranh giới chất lỏng trong kính (hình 8, 6). Và trong trường hợp này, ngăn xếp sẽ ở trạng thái cân bằng nên chúng ta có thể viết một đẳng thức tương tự như đẳng thức (1):
$$mg + \rho_1 g \pi r^2 (l - x) + \rho_2 g \pi r^2 x = \rho_1 g \pi R^2 (l - x) + \rho_2 g \pi R^2 x.$$ (2)

Từ (1) và (2) ta tìm được
$$x = h \frac{R^2}{R^2 - r^2}.$$

Chúng tôi thấy rằng đáp số không phụ thuộc vào khối lượng của thủy tinh hoặc mật độ của chất lỏng. Điều này có thể gây ngạc nhiên. Xét cho cùng, tấm kính nặng, và phương tiện phía trên chẳng hạn, có thể, rõ ràng là sau khi cái lỗ xuất hiện, tấm kính sẽ chìm xuống. Tuy nhiên, đáp sốbài toán là chính xác. Thực tế là tại lời giải, chúng tôi thường tin rằng $h < l$ và $x < l$ (tại $h \geq l$ hoặc $x \geq l$ kính sẽ chìm). Những điều kiện này, cùng với các đẳng thức (1) và (2), giúp tìm ra mối quan hệ giữa mật độ của vật liệu thủy tinh và mật độ của chất lỏng tại đó thủy tinh có thể cân bằng trong cả trường hợp thứ nhất và thứ hai.

F262. Một loại kính hình trụ có thành mỏng, đáy mỏng, được đóng bằng vật liệu không trọng lượng

⟦folio 47⟧

Hình 10.

pittông mỏng. Có một lò xo giữa piston và đáy kính. Bên trong kính có không khí ở áp suất khí quyển $p_0$. Thủy tinh nổi trong nước như hình hình 9, và khoảng cách từ mặt nước đến pít-tông là $l_1$, độ sâu của thủy tinh là $l_2$. Diện tích pít-tông $S$, độ cứng của lò xo $k$, mật độ nước $ρ$. Độ sâu tối đa mà một chiếc cốc có thể được đặt dưới nước là bao nhiêu để nó vẫn nổi lên được? Bỏ qua thể tích của lò xo.

Lúc đầu, tấm kính nổi trên mặt nước. Điều này có nghĩa là lực hấp dẫn tác dụng lên nó được cân bằng bởi lực Archimedean nổi:

$$mg = \rho g l_2 S.$$

Lúc đầu nhúng thủy tinh vào nước thì lực nổi sẽ tăng lên. Nhưng khi piston chạm tới mực nước, lực ép của nước bắt đầu khuấy động piston xuống đáy ly. Trong trường hợp này, thể tích của kính và do đó lực nổi sẽ giảm. Rõ ràng, độ sâu ngâm tối đa của kính là độ sâu mà tại đó lực nổi, tại thời điểm ban đầu, bằng lực hấp dẫn tác dụng lên kính:

$$mg = \rho g x S.$$

Ở đây $x$ là chiều cao của piston tính từ đáy kính (hình 9, b). Hơn nữa, từ (1) và (2)

$$x = l_2.$$

Mặt khác, giá trị $x$ liên quan đến độ sâu ngâm của kính $h$. Hãy viết điều kiện cân bằng của piston. Nó được tác dụng từ phía trên bởi lực áp suất khí quyển $p_0 S$ và lực áp suất thủy tĩnh $\rho g (h - x) S$, và từ bên dưới bởi lực đàn hồi của lò xo $k \Delta x = k (l_1 + l_2 - x)$ và lực áp suất không khí trong kính $p S$. Do đó, điều tự nhiên là giả định rằng nhiệt độ không khí dưới pít-tông không thay đổi (nó bằng nhiệt độ nước), do đó, theo định luật Boyle-Mariotte

$$p_0 (l_1 + l_2) = px,$$

Ở đâu

$$p = p_0 \frac{l_1 + l_2}{x}.$$

Hình 11.

Vì vậy, chúng ta có thể viết

$$p_0 S + \rho g (h - x) S =$$

$$= k (l_1 + l_2 - x) + \frac{p_0 (l_1 + l_2) S}{x}.$$

Thay thế $x = l_2$ ở đây, chúng ta nhận được:

$$p_0 S + \rho g (h - l_2) S = k l_1 + p_0 S \left( \frac{l_1}{l_2} + 1 \right),$$

Ở đâu

$$h = \frac{p_0 S l_1 + k l_1 l_2 + \rho g l_2^2 S}{\rho g S_2}.$$

F263. Kính mờ (một trong các bề mặt nhẵn, mặt còn lại được đánh bóng) được áp dụng cho bản vẽ: một lần với bề mặt nhẵn lên, lần còn lại hướng xuống. Trong một trường hợp, cái tốt có thể nhìn thấy được, trong trường hợp khác thì không thể phân biệt được. Tại sao?

Bề mặt gồ ghề của dòng chảy phân tán ánh sáng chiếu vào nó đều theo mọi hướng. Nếu kính nằm trên hình vẽ có bề mặt nhẵn (hình 10, a), thì các tia phát ra từ cả đường vẽ và từ những nơi sạch sẽ tới từng điểm trên bề mặt gồ ghề của kính. Các luồng ánh sáng đến từ các phần khác nhau của hình vẽ sau đó sẽ bị phân tán theo mọi hướng như nhau và từ mỗi phần của các tia vẽ đến từ cả các đường vẽ và từ những nơi sạch sẽ đi vào mắt. Do đó, các khu vực khác nhau của dòng chảy có vẻ sáng như nhau và không thể tạo ra hình vẽ.

Nếu kính đối diện với hình vẽ của bề mặt mờ (hình 10, b), thì bề mặt mờ sẽ được chiếu sáng không đồng đều. Các tia tới từ các điểm khác nhau trên bề mặt đi vào mắt mà không giao nhau và hình vẽ rất dễ nhận ra.

F264. Hai tấm kim loại phẳng tròn giống hệt nhau, được sắp xếp như trong hình 11, được xử lý theo một góc

⟦folio 48⟧

tốc độ hú $\omega$ theo các hướng ngược nhau trong trường cực đại, vuông góc với các mặt phẳng của các tấm. Cảm ứng trường tối đa là $B$, khoảng cách giữa các bản là $a$. Các trục của tấm được nối với nhau bằng dây. Sự phân bố mật độ điện tích cơ bắp nhất trên các tấm.

Các tấm quay tạo thành một tụ điện phẳng với sự phân bố điện tích không đều dọc theo các tấm. Nếu chọn các phần bản có diện tích $S$ nằm đối diện nhau giống hệt nhau thì không khó tìm được điện dung của tụ điện mà các phần này tạo thành. Nó bằng $C = \frac{\varepsilon_0 S}{a}$. Vì điện tích của một tụ điện như vậy bằng $Q=CU$, trong đó $U$ là hiệu điện thế giữa các phần, nên rõ ràng là chúng ta có thể dễ dàng xác định mật độ điện tích trong phần $\sigma = \frac{Q}{S} = \frac{CU}{S} = \frac{\varepsilon_0 U}{a}$ nếu chúng ta có thể tính được $U$. Hãy thử làm điều này.

Điện tích $q$, nằm cách tâm các tấm một khoảng $x$, chịu tác dụng của hai lực: lực Lorentz $F_\pi = qvB = q\omega xB$ và lực $F_\alpha = qE$ từ điện trường, sinh ra trong tấm do sự phân bố điện tích không đều trên đĩa. Các lực tổng hợp $F_\pi$ và $F_\alpha$ tạo ra gia tốc hướng tâm $a = \omega^2 x$ cho điện tích. Do đó, theo định luật II Newton

$$F_\pi + F_\alpha = ma.$$ (1)

Vì các đĩa quay theo các hướng khác nhau, lực Lorentz tác dụng lên các điện tích nằm ở cùng một khoảng cách tính từ tâm của các đĩa sẽ hướng theo các hướng khác nhau trong các đĩa khác nhau. Vì vậy, nếu đối với đĩa đầu tiên

$$qE - q\omega xB = m\omega^2 x,$$ (2)

sau đó cho đĩa thứ hai

$$qE + q\omega xB = m\omega^2 x^*).$$ (3)

Từ những điều kiện cân bằng này, chúng ta tìm được hướng của trường ở khoảng cách $x$ tính từ tâm của các đĩa. Chúng bằng $(\omega B + \frac{m}{q}\omega^2)x$ ở đĩa đầu tiên và $(\omega^2 \frac{m}{q} - \omega B)x$ ở đĩa thứ hai. TRONG

*) Hướng của lực $F_\alpha$ trong đĩa phụ thuộc vào độ lớn $\omega$. Nếu $\omega$ nhỏ nên $m\omega^2 x < q\omega xB$, thì hướng của lực $F_\alpha$ trong các đĩa là ngược nhau, nếu $m\omega^2 x > q\omega xB$, thì lực $F_\alpha$ trong các đĩa khác nhau sẽ hướng cùng một hướng. Điều này có thể được nhìn thấy từ các phương trình (2) và (3).

Hình 12.

⟦folio 49⟧

Hình 13.

hướng về bên phải, nghĩa là theo hướng ngược lại với khả năng di chuyển cậu bé so với xe trượt tuyết.

Cậu bé không chuyển động theo phương thẳng đứng nhưng chúng ta coi chuyển động ngang của cậu ấy cùng với chiếc xe trượt là chuyển động đều. Khi đó chúng ta có thể viết các đẳng thức sau:

$$T \sin \alpha + N - Mg = 0,$$
$$T \cos \alpha - F_{TP} = 0,$$

trong đó $F_{TP} = k_1 N$ ($k_1$ là hệ số ma sát của cậu bé trên xe trượt tuyết).

Từ đây

$$k_1 = \frac{T \cos \alpha}{Mg - T \sin \alpha}.$$

Chúng ta sẽ tìm lực căng của sợi dây $T$, khoảng cách chuyển động của toàn bộ hệ cậu bé - xe trượt nói chung (hình 13, b). Đối với hướng dọc, chúng ta có thể viết:

$$T \sin \alpha + N_1 - (M + m)g = 0,$$
$$T + T \cos \alpha - F_{TP_1} = 0.$$

Ở đây $N_1$ là phản lực hỗ trợ, $F_{TP_1} = k N_1$ là lực ma sát của xe trượt trên tuyết. Từ những đẳng thức này

$$T = \frac{k (M + m) g}{1 + \cos \alpha + k \sin \alpha}.$$

Rồi cuối cùng

$$k_1 = \frac{T \cos \alpha}{Mg - T \sin \alpha} = \frac{k (M + m) \cos \alpha}{M (1 + \cos \alpha) - km \sin \alpha}.$$

F266. Buồng lái hình chữ U chuyển động với tốc độ không đổi $v$ song song với bề mặt chất lỏng (hình 14). Tiết diện của phần dưới của cabin khi hạ xuống nước là $S_1$, và phần trên, nằm phía trên mặt nước, là $S_2$. Lực nào tác dụng lên khối cắt? Mật độ chất lỏng $ρ$. Ma sát và sự hình thành sóng trên bề mặt chất lỏng.

Bài toán thuận tiện giải trong hệ tọa độ liên kết với ống. Trong hệ thống này, chất lỏng ở đáy ống chuyển động với tốc độ $v$.

Trong thời gian $\Delta t$, một lượng nước $V = S_1 v \Delta t$ có khối lượng $m = \rho S_1 v \Delta t$ đi vào ống. Động lượng của nước này là

$$mv = \rho S_1 v^2 \Delta t.$$

Vì chất lỏng không tích tụ trong ống nên trong thời gian $\Delta t$ cùng một khối lượng chất lỏng chảy ra khỏi ống phía trên. Nhưng tốc độ $u$ của chất lỏng chảy đã khác rồi. Vì thể tích chất lỏng đi vào ống bằng thể tích chất lỏng chảy ra khỏi ống

$$S_1 v = S_2 u.$$

Từ đây

$$u = v \frac{S_1}{S_2},$$

và động lượng của nước chảy ra khỏi ống có giá trị tuyệt đối bằng nhau

$$mu = \rho S_2 u^2 \Delta t = \rho v^2 \frac{S_1^2}{S_2} \Delta t,$$

a hướng theo hướng ngược lại với hướng xung lực của dòng nước đang chảy.

Như vậy, trong thời gian $\Delta t$ động lượng của nước trong ống thay đổi một lượng

$$\Delta (mv) = mv - (-mu) = \rho S_1 \left( \frac{S_1}{S_2} + 1 \right) v^2 \Delta t.$$

Theo định luật II Newton, lực tác dụng lên nước trong ống là

$$F = \frac{\Delta (mv)}{\Delta t} = \rho S_1 \left( \frac{S_1}{S_2} + 1 \right) v^2.$$

Hình 14.

⟦folio 50⟧

Một lực có cùng độ lớn tuyệt đối, nhưng hướng theo hướng khác (theo định luật thứ ba của Newton), tác dụng lên ống từ phía chất lỏng.

F267. Một tàu vũ trụ hình cầu di chuyển quanh Mặt trời theo quỹ đạo tròn. Nhiệt độ của con tàu là bao nhiêu nếu năng lượng phát ra trên một đơn vị ngựa từ bề mặt Mặt trời và con tàu tỷ lệ thuận với nhiệt độ tuyệt đối của chúng? Các phi hành gia trên tàu nhìn thấy Mặt trời ở góc 30°. Nhiệt độ bề mặt của Mặt trời được lấy là 6000° K.

Ở trạng thái cân bằng nhiệt, khi nhiệt độ của tàu không thay đổi thì năng lượng mà tàu nhận được trong một đơn vị thời gian từ Mặt trời bằng năng lượng do chính tàu phát ra trong không gian xung quanh trong cùng một đơn vị thời gian:

$$W_{\text{изл}} = W_{\text{полл}}.$$

Năng lượng do tàu phát ra tỷ lệ thuận với diện tích bề mặt của tàu $S_K = 4\pi R_K^2$ ($R_K$ là bán kính của tàu) và lũy thừa bậc 4 của nhiệt độ $T_K$ và bằng

$$W_{\text{изл}} = k S_K T_K^4 = 4k\pi R_K^2 T_K^4,$$

trong đó $k$ là hệ số tỷ lệ, giống nhau đối với cả con tàu và Mặt trời.

Bây giờ xác định năng lượng mà con tàu nhận được từ Mặt trời. Năng lượng bằng $k T_K^4$ được phát ra trên một đơn vị bề mặt của Mặt trời; tất cả mặt trời đều phát ra năng lượng

$$W_c = 4k\pi R_c^2 T_c^4,$$

trải đều về mọi hướng.

Ở khoảng cách $l$ tính từ Mặt trời, nơi đặt tàu vũ trụ, năng lượng này truyền qua một quả cầu có diện tích bề mặt

$$S = 4\pi l^2.$$

Năng lượng bằng $\frac{W_c}{S}$ truyền qua một đơn vị diện tích bề mặt của quả cầu này. Diện tích mặt cắt ngang của tàu là $\pi R_K^2$ nên năng lượng đi vào tàu

$$W_{\text{полл}} = \frac{W_c}{S} \pi R_K^2 = \frac{W_c}{4\pi l^2} \pi R_K^2 = k \frac{\pi R_c^2 R_K^2}{l^2} T_c^4.$$

Vì người Cosmian nhìn Mặt trời ở góc $\alpha = 30^\circ$ và góc này nhỏ, nên

$$\frac{\alpha}{2} = \frac{R_c}{l}$$

Và

$$W_{\text{полл}} = \frac{k\pi R_K^2 \alpha^2 T_c^4}{4}.$$

Vì vậy, đẳng thức năng lượng do tàu phát ra và hấp thụ sẽ được viết như sau:

$$4k\pi R_K^2 T_K^4 = \frac{k\pi R_K^2 \alpha^2 T_c^4}{4}.$$

Từ đây

$$T_K = \frac{T_c}{2} \sqrt{\alpha} \approx 270^\circ \text{K}.$$

Chúng tôi thấy rằng nhiệt độ của con tàu không phụ thuộc vào bán kính của nó và chỉ được xác định bởi góc $\alpha$ mà Mặt trời có thể nhìn thấy được. Góc này bằng góc mà Mặt trời được nhìn thấy từ Trái đất. Do đó, nhiệt độ của tàu vũ trụ hóa ra có cùng độ lớn với nhiệt độ của “tàu vũ trụ” Girant - Trái đất.

F268. Để xác định nhiệt độ tương đối của khí ở một thể tích không đổi và ở áp suất và nhiệt độ cung cấp không đổi, cần xác định lượng khí, nhiệt độ, thể tích và áp suất ban đầu bằng $T_0$, $V_0$ và $p_0$ tương ứng, được làm nóng bằng dây ngọn lửa mà van điện đi qua trong một thời gian nhất định, một lần ở thể tích không đổi $V_0$, và khí đạt áp suất $p_1$, khác thời gian ở áp suất không đổi $p_0$, và vật thể khí trở nên bằng $V_1$. Hãy chứng tỏ rằng $\frac{c_p}{c_V} = \frac{(p_1 - p_0) V_0}{(V_1 - V_0) p_0}$.

Vì hệ thống dây điện được làm nóng bởi cùng một dòng điện trong cùng thời gian nên khí trong cả hai trường hợp đều tạo ra cùng một lượng nhiệt.

Nếu một khối khí được nung nóng ở thể tích không đổi thì nhiệt lượng mà khối khí đó nhận được bằng

$$Q = c_V m(T - T_0).$$

Viết phương trình trạng thái của khí:

$$p_0 V_0 = nRT_0$$

Và

$$p_1 V_0 = nRT.$$

Ở đây $n$ là số mol khí, $T$ là nhiệt độ khí ở áp suất $p_1$.

Từ đây

$$T - T_0 = \frac{V_0 (p_1 - p_0)}{n},$$

Và

$$Q = c_V m \frac{V_0 (p_1 - p_0)}{n}.$$

(1)
