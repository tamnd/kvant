---
id: 1980-4-smolyanskiy-umnozhenie-tochek-na-ploskosti-3b706904
issue: kvant_1980_4
year: 1980
number: "4"
title: Nhân... các điểm trên mặt phẳng
authors:
  - Смолянский М. Л.
rubric: osnovnye-stati
page_first: 21
page_last: 24
page_labels: 19-22
tag: AXNS
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 0011b6f1d1857ee227adc46d2fd6084bafe8fd910e264eb485ce8037404d5d74
prompt_sha256: draft-1
translated_from: content/ru/1980/04/articles/06_smolyanskiy-umnozhenie-tochek-na-ploskosti-3b706904.md
source_content_sha256: 7b8e9f0fdd875d3774fd0a804d8552f416ec52e15642028c85d2d62d6194e1cb
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 19⟧

M. Smolyansky

Phép nhân...
điểm trên mặt phẳng

"Nhân điểm - điều này có được không? - người đọc ngạc nhiên sẽ hỏi. "Rốt cuộc, họ nhân (và cộng) số chứ không phải điểm!" Người đọc như vậy rất dễ phản đối: thứ nhất, số thực thường được coi là điểm trên trục số, nên theo nghĩa này người ta có thể nhân các điểm; thứ hai, trong toán học hiện đại, họ không chỉ nhân điểm mà còn nhân hầu hết mọi thứ: hàm số, ma trận, chuyển vị...

Trong bài viết này, chúng tôi sẽ cố gắng chỉ cho người đọc cách thức và lý do bạn cần nhân các điểm trên một mặt phẳng. Trên con đường này, chúng ta sẽ thu được mô hình hình học của số phức và nghiên cứu một số tính chất của chúng. Và bên cạnh đó, chúng tôi sẽ chỉ ra rằng không thể nhân các điểm một cách thông minh trong không gian được nữa.

Trước khi học cách nhân các điểm trên một mặt phẳng, sẽ rất hữu ích khi xem xét...

Cách nhân điểm trên một dòng
Để cộng hai điểm trên một đường thẳng, chỉ cần thực hiện phép cộng

bắt đầu $O$: sau đó các điểm có thể được thêm dưới dạng vectơ. Nếu chúng ta sửa điểm $A$ và thêm điểm đó vào mỗi điểm $X$ trên đường thẳng, chúng ta sẽ thu được ánh xạ $X \rightarrow X + A$ của đường thẳng đó lên chính nó. Rõ ràng rằng đây sẽ là sự chuyển song song của toàn bộ đường thẳng sang vectơ $\vec{OA}$ (Hình 1a). Để nhân, đơn vị $1$ cũng phải hoạt động: sau đó thu được tọa độ và với các điểm trợ giúp của chúng có thể được nhân lên (như số); Hơn nữa, như dễ thấy, phép nhân tất cả các điểm của đường thẳng với điểm hàm $A$ là một phép đo hình học có tâm $O$, lấy điểm $1$ đến điểm $A$ (Hình 1, 6).

Hãy định nghĩa phép nhân trên mặt phẳng

Trước hết, chúng ta hãy tìm hiểu loại phép nhân mà chúng ta muốn xác định trên mặt phẳng của mình, trong đó trục số $Ox$ với đơn vị $1$ đã được chọn (Hình 2). (Lưu ý rằng phép cộng các điểm đã được xác định: sự hiện diện của gốc $O$ cho phép các điểm được thêm dưới dạng vectơ, theo quy tắc hình bình hành.) Tất nhiên, chúng tôi muốn phép nhân mới trùng với phép nhân đã có trên trục $Ox$ (chúng tôi sẽ gọi trục này là trục thực). Vì vậy chúng tôi sẽ yêu cầu:

I. Nhân với điểm bất kỳ $A$ của trục thực $Ox$ là một hình học có tâm $O$ và hệ số $x$, trong đó $x$ là hoành độ của điểm $A$.

Nhưng điều này, tất nhiên, là không đủ. Chúng ta cũng cần phép nhân để có các tính chất chung của các phép tính số học. Chính xác:

II. Phép nhân có tính kết hợp, phân phối đối với phép cộng và chia cho bất kỳ điểm nào $A$ khác với $O$ được xác định.

Hãy viết ra các thuộc tính này chi tiết hơn:

Pa. Tính liên kết. Đối với bất kỳ điểm nào $A, B, C: A(BC) = A(BC)$.

Hình 1.

⟦folio 20⟧

Pis. 2.

IIb. Tính phân phối. Đối với bất kỳ điểm nào $A, B, C$

$$A(B+C) = AB+AC,$$
$$ (B+C)A = BA+CA.$$

Phân thế kỷ II (tồn tại nghịch đảo). Đối với bất kỳ điểm nào (trừ $O$) $A$ cũng có một điểm $A^{-1}$, sao cho

$$A^{-1}A = AA^{-1} = 1.$$

Vì vậy, chúng ta cần xây dựng một phép nhân trên mặt phẳng thỏa mãn điều kiện I và II. Dừng lại: chưa đọc thêm mà trước tiên hãy nghĩ về cách thực hiện việc này.

Vâng, bạn đã nghĩ ra nó? Tất nhiên, cách dễ nhất để định nghĩa phép nhân là “giống” như đối với các điểm trên trục thực. Cụ thể, nhân với điểm $A$ là một dạng của một mặt phẳng lấy điểm 1 đến điểm $A$, để lại điểm $O$ tại chỗ và giữ nguyên hướng. Bạn có thể tưởng tượng rõ ràng rằng chúng ta quay mặt phẳng gần điểm đầu sao cho tia [O1) trùng với tia [OA], sau đó chúng ta tạo một mặt phẳng hoàn thiện chuyển điểm 1 thành điểm $A$.

Rõ ràng là với điều kiện nhân như vậy tôi thỏa mãn.

Bài tập 1. Chứng minh rằng II cũng đúng và hơn nữa phép nhân có tính giao hoán.

Trước khi đọc thêm, hãy hiểu cách hoạt động của phép nhân với các điểm cụ thể, chẳng hạn như $I(0,1)$, $J(-1,0)$, $C(1,1)$.

Người ta sẽ tự nhiên hỏi liệu phép nhân mà chúng ta vừa giới thiệu có phải là phép nhân duy nhất có tính chất I và II hay không.

Bài tập 2*. Chứng minh rằng phép nhân như vậy không duy nhất.

Nếu bài tập này không hiệu quả, chúng tôi khuyên bạn nên quay lại sau khi đọc thêm. Trong phần tiếp theo chúng tôi tiết lộ trong không gian?

Giống như mặt phẳng, không gian của chúng ta trước tiên có trục số $Ox$ với đơn vị 1; chúng ta sẽ tìm phép nhân thỏa mãn các điều kiện như ở phần trước, tức là để trả lời câu hỏi sau: liệu trong không gian của một vật có thể nhân thỏa mãn điều kiện I và II hay không?

Lấy cảm hứng từ các điều kiện trước đó, bạn sẽ nói: tất nhiên, bạn có thể, theo cách tương tự như trước: nhân với điểm $A$ là một loại không gian lấy 1 đến $A$ và $O$ đến $O$. Nhưng có một chút trở ngại ở đây:

Bài tập 3. Chứng minh rằng với $A$ không nằm trên trục thực thì có vô số điểm tương đồng như vậy.

Tôi nên lấy cái nào? Hãy lấy bất kỳ thứ gì, người lạc quan sẽ nói. Về điều này, chúng tôi sẽ phản đối anh ta rằng khó có điều gì tốt đẹp sẽ xảy ra từ việc này: xét cho cùng, phép nhân với các điểm khác nhau phải nhất quán (để điều kiện II được thỏa mãn). Làm thế nào để dung hòa chúng?

Đừng thử - nó sẽ không hiệu quả. Thực tế là phép nhân trong không gian có tính chất I và II không tồn tại! Chúng ta sẽ chứng minh điều này bằng phản chứng.

Giả sử chúng ta đã xác định được một số phép nhân. Chúng ta hãy lấy một điểm tùy ý $X$ bên ngoài trục $Ox$ và xem xét bậc của nó $X^2$ và $X^3$ (tức là các điểm $X \cdot X$ và $(X \cdot X) \cdot X$).

Nhờ một trong những tiên đề hình học do G. Weylem đề xuất (“Hình học 9–10”, trang 234), với bốn vectơ bất kỳ của không gian $\vec{a}, \vec{b}, \vec{c}, \vec{d}$ người ta có thể tìm thấy các số thực $k, l, m, n$, không phải tất cả đều bằng 0, sao cho đẳng thức

$$k\vec{a} + l\vec{b} + m\vec{c} + n\vec{d} = \vec{0}.$$

Chúng ta hãy áp dụng thực tế này cho bốn vectơ nối điểm $O$ với bốn điểm $1, X, X^2, X^3$; thì có những con số thực (theo thuật ngữ của chúng tôi -

⟦folio 21⟧

Hình 3.
các điểm của trục thực) $A, B, C, D$ sao cho đẳng thức thỏa mãn:
$$A + BX + CX^2 + DX^3 = 0$$
(1)

Pravanitsa có 4. Giải thích tại sao $A \cdot 1 = A$.

Bây giờ chúng ta cần thực tế sau:
Pravanitsa có 5*. Bất kỳ phương trình bậc ba nào cũng có nghiệm thực.
(Nếu bạn cảm thấy khó giải phương trình này, hãy xem «Kvant», 1980, số 2, trang 20.)

Chúng ta hãy biểu thị nghiệm này (một điểm trên trục thực) bằng $X_0$; sau đó đối với một số số (điểm trên trục thực) $C', B'$
$$X - X_0) (DX^2 + C'X + B') = A + BX + CX^2 + DX^3.$$

Vì tích của các thừa số khác 0 không thể cho kết quả bằng 0 (điều này tuân theo điều kiện Pa, PV: nếu $Q \neq 0$, $P \neq 0$ và $P \cdot Q = 0$ thì $0 = 0 \cdot Q^{-1} = P \cdot Q \cdot Q^{-1} = P \cdot 1 = P \neq 0$), một trong các dấu ngoặc này bằng 0. Vì $X$ không phải là điểm “thực”, nên $D \neq 0$ và các điểm 0, 1, $X$ và $X^2$ nằm trong cùng một mặt phẳng. Chúng ta hãy xem xét điểm $Y$, điểm không nằm trong mặt phẳng này (Hình 3).

Xét bốn điểm 1, $X$, $Y$, $YX$, nằm trong không gian; một lần nữa áp dụng tiên đề (tương tự), người ta có thể chọn các điểm $B_1$, $B_2$, $B_3$, $B_4$ trên trục thực, không phải tất cả đều bằng 0, sao cho
$$B_1 + B_2X + B_3Y + B_4YX = 0.$$

Nếu không nó có thể được viết như thế này:
$$(B_1 + B_2X) + Y(B_3 + B_4X) = 0.$$ (2)

Lưu ý rằng trong mặt phẳng chứa 0, 1, $X$ tồn tại điểm $Y_0$ thỏa mãn (2).

Hình 4.
Pravanice có 6. Viết nó dưới dạng $C_1 + C_2X$ và tìm $C_1$ và $C_2$ bằng cách sử dụng các phương trình $DX^2 + C'X + B' = 0$.

Nhưng sau đó $(Y - Y_0)(B_3 + B_4X) = 0$, từ đó $Y = Y_0$, tức là điểm $Y$ nằm trong mặt phẳng bên ngoài nơi nó được chọn. Sự mâu thuẫn. Không có phép nhân trong không gian mà chúng ta cần!

Đối với những người biết không gian bốn chiều là gì, chúng tôi lưu ý rằng có thể đưa ra phép nhân trong đó (thỏa mãn điều kiện I và II), nhưng phép nhân này sẽ không có tính giao hoán. Nó không dễ dàng, nhưng hãy thử nó!

Bây giờ chúng ta hãy quay trở lại máy bay. Chúng ta đã đạt được gì ở đó?

Điểm dưới dạng số phức

Chúng ta sẽ giả sử rằng đường thực nằm ngang và xem xét một vectơ có độ dài đơn vị hướng lên trên (Hình 4). Hãy biểu thị nó bằng $i$. Dễ dàng nhận thấy điều đó $i^2 = -1$. Vì vậy, đối với mặt phẳng, chúng ta giải phương trình $x^2 + 1 = 0$; Khi mở rộng đường thẳng thực thành mặt phẳng, chúng ta có thể giải được một phương trình không thể giải được đối với đường thẳng.

Bất kỳ điểm nào trong mặt phẳng đều có thể được viết là $a + bi$, trong đó $a$ và $b$ là các điểm thực; phép cộng và nhân một điểm viết theo cách này được cho bởi các công thức:
$$(a_1 + ib_1) + (a_2 + ib_2) = (a_1 + a_2) + i(b_1 + b_2),$$
$$(a_1 + ib_1) \cdot (a_2 + ib_2) = (a_1a_2 - b_1b_2) + i(a_1b_2 + b_1a_2).$$

U pravanice 7. Rút ra các công thức này từ các định nghĩa hình học.

⟦folio 22⟧

Hình 5.

Các công thức này cho thấy điểm của chúng ta, phép cộng và phép nhân của chúng là mô hình hình học của số phức *). Thật dễ dàng để thu được một thực tế đáng chú ý như vậy: bất kỳ phương trình $AX^2 + BX + C = 0$ nào (trong đó $A, B, C$ là các điểm của mặt phẳng và $A \neq 0$) bị cắt - có một điểm trên mặt phẳng biến nó thành một đẳng thức. Trên thực tế, bất kỳ phương trình đại số nào cũng có thể được cắt trên mặt phẳng (xem «Kvant», 1980, số 2, trang 17).

Bài tập 8. Viết công thức cho phương trình bậc hai lời giải trong mặt phẳng.

Công thức nghiệm bậc $n$

Như bạn đã biết, đối với các số thực và do đó đối với một đường thẳng thực, phương trình $X^n = A$ cho $A \neq 0$ và thậm chí $n$ không phải lúc nào cũng có thể cắt được. Hơn nữa, nó không thể cắt bỏ được, hoặc có thể cắt ghép giữa hai nghĩa. (Ví dụ: bình phương 1 và -1 cho kết quả bằng 1.) Đối với mặt phẳng ngưng tụ, nó tinh tế hơn nhiều: đối với mỗi điểm khác 0 $A$ phương trình $X^n = A$, $n$ là một số tự nhiên, có chính xác $n$ căn.

Để chứng minh điều này, trước tiên chúng ta sẽ học cách lũy thừa các điểm nằm trên một đường tròn $\Gamma$ bán kính đơn vị với tâm bằng 0 (Hình 5). Đường tròn này có một tính chất đáng chú ý: tích của hai điểm từ $\Gamma$ lại là một điểm của đường tròn $\Gamma$. Trên thực tế, nhân một mặt phẳng với một điểm trên đường tròn này chỉ đơn giản là một phép quay có tâm tại các điểm 0. Vì khi quay một vòng tròn đơn vị,

*) Xem «Kvant», 1980, số 2, tr. 17.

Hình 6.

giống như tất cả các vòng tròn khác có tâm bằng 0, biến thành chính nó, tuyên bố của chúng tôi là đúng. Nhìn lại, chúng ta đã có một cách mới để ghi lại một phép quay - bằng cách nhân với điểm tương ứng.

Bây giờ đã rõ $X^n$ dùng để làm gì cho $X \in \Gamma$. Nhân với $X^n$ là thành phần của $n$ phép quay với góc tương ứng với điểm $X$, do đó điểm $X^n$ tương ứng với góc $n$ lớn hơn góc $XO1$. Vậy $X^n$ là điểm $\Gamma$ mà

$$X^n \widehat{O1} = n \cdot X \widehat{O1}.$$

Xét dấu góc của điểm $X^n$ được xác định duy nhất bằng công thức này.

Nhưng bây giờ đã rõ làm thế nào để tìm được nghiệm của phương trình $X^n = A$, nếu $A \in \Gamma$: đây là điểm $X \in \Gamma$ sao cho

$$\widehat{XO1} = \frac{1}{n} \widehat{AO1}.$$

Chà, giá trị $n$ phổ biến ở đâu? Hóa ra chúng được ẩn trong công thức này. Thật vậy, chúng ta có thể xác định độ lớn của góc $AO1$ theo số radian chia hết cho 2π: góc $\widehat{AO1}, \widehat{AO1} + 2\pi, \widehat{AO1} + 4\pi, \dots$, nói chung $\widehat{AO1} + 2\pi k$, trong đó $k$ là số nguyên, tương ứng với cùng một điểm. Và khi xác định $X$ cho các $k$ khác nhau, chúng ta nhận được các điểm khác nhau. Dễ dàng nhận thấy bạn sẽ nhận được chính xác $n$ điểm khác nhau tương ứng với các góc độ lớn $\frac{1}{n} \widehat{AO1} + 2\pi \frac{k}{n}$ ($k = 0, 1, \dots, n-1$). Hình 6 cho thấy gốc của đơn vị tiếp theo. Có thể thấy rằng chúng tạo thành các đỉnh của một hình bảy cạnh đều.

(Cuối cùng xem trang 29)
