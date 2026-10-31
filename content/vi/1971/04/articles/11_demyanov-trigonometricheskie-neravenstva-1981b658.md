---
id: 1971-4-demyanov-trigonometricheskie-neravenstva-1981b658
issue: kvant_1971_4
year: 1971
number: "4"
title: Bất đẳng thức lượng giác
authors:
  - Демьянов В. Б.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 45
page_last: 52
page_labels: 43-50
tag: DE7Y
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 85bfb2753cecdfdc7f9a91c99b6173af5a99bfcca83dc7463a9e3fa4b2c8772f
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1971/04/articles/11_demyanov-trigonometricheskie-neravenstva-1981b658.md
source_content_sha256: 5f6558d13eaba12d914dd6c05975be07e6696d3a29dae4b831d91183ce1b7fe6
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦folio 43⟧

Ta sẽ gọi các bất đẳng thức lượng giác là những bất đẳng thức chứa ẩn $x$, là thành phần trong các đối số của các hàm lượng giác. Giải một bất đẳng thức lượng giác tức là, như thường lệ, tìm tất cả các giá trị của ẩn thỏa mãn bất đẳng thức đó.

Để giải các bất đẳng thức lượng giác đơn giản nhất không cần bất kỳ kiến thức đặc biệt nào vượt ra ngoài chương trình phổ thông. Cụ thể, trong các ví dụ được xét dưới đây, ngoài các tính chất của các hàm lượng giác, chỉ dùng khái niệm giá trị tuyệt đối của một số (ví dụ 4), các quy tắc giải bất đẳng thức bậc hai (ví dụ 5—8) và các tính chất của hàm logarit (ví dụ 9, 10). Những kiến thức này cũng đủ để giải các ví dụ được nêu ở cuối bài để tự giải.

Tuy nhiên, ngay từ đầu cần lưu ý một điểm có tính nguyên tắc. Trong các bất đẳng thức lượng giác, đối số của các hàm lượng giác không được xét như các góc hoặc cung, mà như các số thực. Vì kinh nghiệm cho thấy rằng về vấn đề này nhiều học sinh tốt nghiệp trung học chưa có sự hiểu biết đầy đủ, ta sẽ dừng lại ở đây chi tiết hơn một chút. Thí sinh đại học được khuyên nên suy nghĩ kỹ điều được nói dưới đây về vấn đề này.

Thông thường, các hàm lượng giác trước hết được đưa vào như các hàm của góc (chính xác hơn, chỉ của góc nhọn). Sau đó khái niệm đối số của hàm lượng giác được mở rộng — bắt đầu xét các hàm của cung. Khi đó, thấy rằng thuận tiện là không giới hạn ở các cung nằm trong phạm vi một vòng quay, tức là có giá trị từ $0^\circ$ đến $360^\circ$, mà xét các cung có độ lớn được biểu thị bằng bất kỳ số độ nào (cả dương lẫn âm). Với cách hiểu như vậy về đối số, các hàm lượng giác trở thành tuần hoàn. Bước tiếp theo là chuyển từ cách đo cung bằng độ sang bằng radian. Và cuối cùng, đi đến khái niệm hàm lượng giác của một số thực. Cụ thể, giá trị của hàm lượng giác của một số được hiểu là giá trị của hàm ấy đối với cung mà độ lớn tính bằng radian được biểu thị bởi số đó.

Trong vật lý, các hàm lượng giác của đối số số tự nhiên xuất hiện khi mô tả các quá trình tuần hoàn khác nhau, tức là những quá trình mà tính chất của chúng lặp lại hoàn toàn sau những khoảng thời gian nhất định. Chính vì thế trong toán học cũng hợp lý khi xét các hàm lượng giác của đối số số. Thực tế, ta đã làm như vậy khi dựng đồ thị các hàm lượng giác. Thật vậy, trên trục hoành ta đặt các giá trị của các số thực.

Bây giờ ta xét một số bất đẳng thức lượng giác

⟦folio 44⟧

THỨC, và bắt đầu từ ví dụ đơn giản nhất.

Ví dụ 1. Giải bất đẳng thức $tg x < 1$.

Lời giải. Trước hết hãy chỉ ra không nên “giải” bất đẳng thức này như thế nào, tức là xét một số câu trả lời sai thường gặp cho câu hỏi.

Một số thí sinh, nhận thấy rằng $tg \frac{\pi}{4} = 1$ và rằng gần giá trị $x = \frac{\pi}{4}$ hàm số $tg x$ tăng khi $x$ tăng, viết đáp án dưới dạng: $x < \frac{\pi}{4}$. Chỉ nhìn hình thức của đáp án cũng có thể nói rằng nó không đúng, vì trong đó hoàn toàn không phản ánh tính tuần hoàn của hàm số $y = tg x$. Dễ chỉ ra cả những giá trị cụ thể của $x$, thỏa mãn điều kiện $x < \frac{\pi}{4}$, nhưng không thỏa mãn bất đẳng thức đã cho. Chẳng hạn, khi $x = -\frac{2\pi}{3}$ ta có: $-\frac{2\pi}{3} < \frac{\pi}{4}$, nhưng $tg\left(-\frac{2\pi}{3}\right) = \sqrt{3} > 1$; khi $x = -\frac{\pi}{2}$ vế trái của bất đẳng thức không có nghĩa, do đó giá trị này cũng không thỏa mãn bất đẳng thức, mặc dù lại có $-\frac{\pi}{2} < \frac{\pi}{4}$.

Cũng có khi thí sinh cố gắng tính đến tính tuần hoàn, nhưng lại tỏ ra lúng túng. Cụ thể, thường “đáp án” được đưa ra dưới dạng: $x < \frac{\pi}{4} + k\pi$, trong đó $k = 0, \pm 1, \pm 2, \dots$.

“Lời giải” này còn tệ hơn, vì nó hoàn toàn vô nghĩa. Dễ thấy rằng đơn giản là không có các số $x$ thỏa mãn điều kiện $x < \frac{\pi}{4} + k\pi$ với mọi $k = 0, \pm 1, \pm 2, \dots$.

Để có được lời giải đúng, hữu ích là xét đồ thị của hàm số $y = tg x$ (hình 1), vì khi đó lập luận sẽ có tính trực quan hình học.

Bất đẳng thức $tg x < 1$ được thỏa mãn khi và chỉ khi các giá trị $x$ tương ứng với những điểm của đồ thị nằm dưới đường thẳng ngang nét đứt $y = 1$. Hơn nữa, từ hình 1 thấy rõ rằng nếu ta tìm được mọi nghiệm thuộc một khoảng xác định nào đó có độ dài $x$, thì mọi nghiệm còn lại sẽ khác các nghiệm đã tìm được bởi phép tịnh tiến sang phải hoặc sang trái một đoạn $\pi, 2\pi, 3\pi$ v.v. Nguyên nhân là số $x$ là chu kỳ của hàm số $y = tg x$.

⟦folio 45⟧

Để đáp án được viết ngắn gọn nhất có thể, nên chọn khoảng ban đầu có độ dài $l$ sao cho các nghiệm thuộc nó lần lượt lấp đầy một khoảng liên tục nào đó. Từ hình vẽ lại thấy rằng điều đó sẽ xảy ra nếu chọn làm khoảng ban đầu, chẳng hạn, khoảng từ $-\frac{\pi}{2}$ đến $\frac{\pi}{2}$. Trên khoảng này, phía dưới đường thẳng $y = 1$ là những điểm của đồ thị tương ứng với các giá trị $x$ thỏa mãn bất đẳng thức $-\frac{\pi}{2} < x < \frac{\pi}{4}$. Vì vậy đáp án cuối cùng có dạng
$$-\frac{\pi}{2} + k\pi < x < \frac{\pi}{4} + k\pi$$
($k = 0, \pm 1, \pm 2, \dots$).

Như vậy, đáp án là tập hợp các khoảng, mỗi khoảng trong số đó thu được ứng với một giá trị cố định nào đó của $k$.

Tương tự cũng xảy ra trong đáp án của tất cả các ví dụ tiếp theo.

Ví dụ 2. Giải bất đẳng thức
$$\sin x \geq -\frac{1}{2}.$$

Lời giải. Xét đồ thị của hàm số $y = \sin x$ (hình 2). Bất đẳng thức $\sin x \geq -\frac{1}{2}$ được thỏa mãn bởi những giá trị $x$ mà tại đó các điểm tương ứng trên đồ thị nằm không thấp hơn đường thẳng chấm $y = -\frac{1}{2}$ (nếu điểm của đồ thị nằm ngay trên đường thẳng này, thì giá trị $x$ thỏa mãn bất đẳng thức đã cho, vì nó «không nghiêm ngặt», trong đó cho phép vế trái và vế phải bằng nhau). Hàm số $y = \sin x$ có chu kỳ $2\pi$. Vì vậy trước hết xét một khoảng nào đó có độ dài $2\pi$, chẳng hạn khoảng từ $-\frac{\pi}{2}$ đến $\frac{3\pi}{2}$. Từ hình 2 thấy rằng trong khoảng này, bất đẳng thức $\sin x \geq -\frac{1}{2}$ được thỏa mãn bởi các giá trị $x$ sau: $-\frac{\pi}{6} \leq x \leq \frac{7\pi}{6}$.

Xét đến tính chu kỳ, ta được đáp số:
$$-\frac{\pi}{6} + 2k\pi \leq x \leq \frac{7\pi}{6} + 2k\pi$$
($k = 0, \pm 1, \pm 2, \dots$).

Ví dụ 3. Giải bất đẳng thức
$$\cos(3x + 2) > -\frac{\sqrt{2}}{2}.$$

Lời giải. Đặt ẩn phụ $t = 3x + 2$. Khi đó đối với $t$ ta được bất đẳng thức $\cos t > -\frac{\sqrt{2}}{2}$. Vì nó hoàn toàn tương tự bất đẳng thức trong các ví dụ 1 và 2 (để giải nó có thể xét đồ thị hàm số $y = \cos t$), ta có ngay đáp án đối với $t$:
$$-\frac{3\pi}{4} + 2k\pi < t < \frac{3\pi}{4} + 2k\pi$$
($k = 0, \pm 1, \pm 2, \dots$).

⟦folio 46⟧

hay, trở lại với ẩn $x$,
$$-\frac{3\pi}{4} + 2k\pi < 3x + 2 < \frac{3\pi}{4} + 2k\pi$$
($k = 0, \pm 1, \pm 2, \dots$).

Suy ra $x$, ta được đáp án cho bất đẳng thức đã cho:
$$-\frac{2}{3} - \frac{\pi}{4} + \frac{2k\pi}{3} < x < -\frac{2}{3} + \frac{\pi}{4} + \frac{2k\pi}{3}$$
($k = 0, \pm 1, \pm 2, \dots$).

Ví dụ 4. Giải bất đẳng thức
$$|\sin x| > \frac{\sqrt{3}}{2}$$.

Lời giải. Loại bỏ dấu giá trị tuyệt đối, ta được rằng bất đẳng thức đã cho được thỏa mãn khi và chỉ khi các giá trị $x$ thỏa mãn một trong các bất đẳng thức
$$\sin x > \frac{\sqrt{3}}{2}, \sin x < -\frac{\sqrt{3}}{2}$$.

Giải từng bất đẳng thức bằng phương pháp đã trình bày trong các ví dụ 1 và 2, đối với bất đẳng thức $\sin x > \frac{\sqrt{3}}{2}$ ta được đáp số:
$$\frac{\pi}{3} + 2k\pi < x < \frac{2\pi}{3} + 2k\pi$$
($k = 0, \pm 1, \pm 2, \dots$),

còn đối với bất đẳng thức $\sin x < -\frac{\sqrt{3}}{2}$ ta được đáp số:
$$-\frac{2\pi}{3} + 2m\pi < x < -\frac{\pi}{3} + 2m\pi$$
($m = 0, \pm 1, \pm 2, \dots$).

Vì vậy, đáp số của bất đẳng thức đã cho
$$|\sin x| > \frac{\sqrt{3}}{2}$$ có thể viết dưới dạng hai “dãy”:
$$\frac{\pi}{3} + 2k\pi < x_1 < \frac{2\pi}{3} + 2k\pi$$
($k = 0, \pm 1, \pm 2, \dots$),
$$-\frac{2\pi}{3} + 2m\pi < x_2 < -\frac{\pi}{3} + 2m\pi$$
($m = 0, \pm 1, \pm 2, \dots$).

Lưu ý rằng vì
$$-\frac{2\pi}{3} = \frac{\pi}{3} - \pi$$
và
$$-\frac{\pi}{3} = \frac{2\pi}{3} - \pi$$,
dãy thứ hai có thể viết theo cách khác
$$\frac{\pi}{3} + (2m - 1)\pi < x_2 < \frac{2\pi}{3} + (2m - 1)\pi$$
($m = 0, \pm 1, \pm 2, \dots$).

Bây giờ có thể gộp cả hai dãy bằng một công thức:
$$\frac{\pi}{3} + n\pi < x < \frac{2\pi}{3} + n\pi$$
($n = 0, \pm 1, \pm 2, \dots$),

trong đó với $n$ chẵn ta được các khoảng của dãy thứ nhất, còn với $n$ lẻ – các khoảng của dãy thứ hai.

Ví dụ 5. Giải bất phương trình
$$\cos^2 x < \frac{3}{4}$$

Lời giải. Đặt ẩn phụ $y = \cos x$. Bất phương trình có dạng
$$y^2 < \frac{3}{4}$$
Suy ra
$$-\frac{\sqrt{3}}{2} < y < \frac{\sqrt{3}}{2}$$
hay
$$-\frac{\sqrt{3}}{2} < \cos x < \frac{\sqrt{3}}{2}$$

Như vậy, bất phương trình đã cho được đưa về hệ bất phương trình
$$\left\{ \begin{array}{l}
\cos x < \frac{\sqrt{3}}{2} \\
\cos x > -\frac{\sqrt{3}}{2}
\end{array} \right.$$

Hãy nhấn mạnh sự khác biệt giữa tình huống hiện nay và tình huống đã xảy ra trong ví dụ 4. Ở đó, để bất đẳng thức đã cho được thỏa mãn, cần có ít nhất một trong hai bất đẳng thức
$$\sin x > \frac{\sqrt{3}}{2}$$ hoặc $$\sin x < -\frac{\sqrt{3}}{2}$$

Ở đây, bất đẳng thức đã cho sẽ được thỏa mãn bởi những giá trị $x$ mà

⟦folio 47⟧

đồng thời thỏa mãn mỗi bất đẳng thức $\cos x < \frac{\sqrt{3}}{2}$ và $\cos x > -\frac{\sqrt{3}}{2}$.

Vì hàm số $y = \cos x$ có chu kỳ $2\pi$, trước hết hãy xét các giá trị $x$ nằm trên khoảng từ $-\pi$ đến $\pi$. Hãy dựng đồ thị hàm số $y = \cos x$ trên khoảng này (hình 3). Hệ

$$\begin{cases} \cos x < \frac{\sqrt{3}}{2}, \\ \cos x > -\frac{\sqrt{3}}{2} \end{cases}$$

được thỏa mãn bởi những giá trị $x$ mà các điểm tương ứng trên đồ thị nằm bên trong dải ngang, bị giới hạn phía trên bởi đường thẳng nét đứt $y = \frac{\sqrt{3}}{2}$, và phía dưới bởi đường thẳng nét đứt $y = -\frac{\sqrt{3}}{2}$.

Từ hình vẽ thấy rằng điều kiện này được thỏa mãn bởi các giá trị $x$ sau: thứ nhất, $\frac{\pi}{6} < x < \frac{5\pi}{6}$, thứ hai, $-\frac{5\pi}{6} < x < -\frac{\pi}{6}$. Xét tính tuần hoàn, bây giờ ta có thể viết đáp số dưới dạng hai dãy:

$$\frac{\pi}{6} + 2k\pi < x_1 < \frac{5\pi}{6} + 2k\pi$$

($k = 0, \pm 1, \pm 2, \dots$).

$- \frac{5\pi}{6} + 2m\pi < x_2 < - \frac{\pi}{6} + 2m\pi$

($m = 0, \pm 1, \pm 2, \dots$).

Như trong ví dụ 4, hai dãy này có thể gộp lại bằng một công thức:

$$\frac{\pi}{6} + n\pi < x < \frac{5\pi}{6} + n\pi$$

($n = 0, \pm 1, \pm 2, \dots$).

Lưu ý rằng bất đẳng thức $\cos^2 x < \frac{3}{4}$ có thể giải đơn giản hơn nếu trước hết biến đổi nó về dạng

$$\frac{1 + \cos 2x}{2} < \frac{3}{4}$$

từ đó $\cos 2x < \frac{1}{2}$. Đặt $2x = t$, ta được rằng

$$\frac{\pi}{3} + 2n\pi < t < \frac{5\pi}{3} + 2n\pi$$

($n = 0, \pm 1, \pm 2, \dots$).

Từ đây

$$\frac{\pi}{6} + n\pi < x < \frac{5\pi}{6} + n\pi$$

($n = 0, \pm 1, \pm 2, \dots$).

Tuy nhiên, cách giải thứ nhất, dựa trên việc đưa về bất đẳng thức bậc hai, có tính tổng quát hơn, điều mà ta sẽ thấy dưới đây (ví dụ 6, 7, 8).

Ví dụ 6. Giải bất đẳng thức $\mathrm{tg}^2 x - (1 + \sqrt{3}) \mathrm{tg} x + \sqrt{3} \leq 0$.

⟦folio 48⟧

Lời giải. Đặt $y = \text{tg} x$, cũng như trong ví dụ trước, ta đưa về bất đẳng thức bậc hai: $y^2 - (1 + \sqrt{3}) y + \sqrt{3} \leq 0$.
Giải nó, ta được $1 \leq y \leq \sqrt{3}$. Như vậy, bài toán lại đưa về việc giải hệ bất đẳng thức
$$\begin{cases} \text{tg} x \leq \sqrt{3}, \\ \text{tg} x \geq 1. \end{cases}$$

Chu kỳ của hàm $y = \text{tg} x$ bằng $\pi$. Lập luận như trong ví dụ 5, trước hết ta tìm được trên khoảng từ $-\frac{\pi}{2}$ đến $\frac{\pi}{2}$ các giá trị sau của $x$:
$\frac{\pi}{4} \leq x \leq \frac{\pi}{3}$. Xét tính chu kỳ, ta được đáp số cuối cùng:
$$\frac{\pi}{4} + k\pi \leq x \leq \frac{\pi}{3} + k\pi$$
($k = 0, \pm 1, \pm 2, \dots$).

Tất cả các ví dụ đã xét đến nay đều được chọn sao cho trong đáp số xuất hiện các giá trị “tròn” của đối số như $\frac{\pi}{6}, \frac{\pi}{4}, \frac{\pi}{3}$.

Tuy nhiên về nguyên tắc điều đó hoàn toàn không bắt buộc, vì đáp số luôn có thể được viết bằng các ký hiệu của các hàm lượng giác ngược. Để áp dụng điều này, xét một ví dụ chỉ khác ví dụ 6 ở các giá trị của hệ số số.

Ví dụ 7. Giải bất phương trình $\text{tg}^2 x - 5\text{tg} x + 6 \leq 0$.

Lời giải. Lập luận hoàn toàn giống như trong ví dụ 6, ta đi đến hệ bất phương trình
$$\begin{cases} \text{tg} x \leq 3, \\ \text{tg} x \geq 2. \end{cases}$$

Đáp số lúc này được viết dưới dạng
$$k\pi + \text{arctg} 2 \leq x \leq k\pi + \text{arctg} 3$$
($k = 0, \pm 1, \pm 2, \dots$).

Ví dụ 8. Giải bất phương trình $12\sin^2 x - 19\sin x + 5 < 0$.

Lời giải. Đặt $y = \sin x$, ta được bất phương trình bậc hai $12y^2 - 19y + 5 < 0$, từ đó $\frac{1}{3} < y < \frac{5}{4}$. Như vậy, ẩn $x$ phải nhận mọi giá trị thực $x$. Do đó thực tế chỉ cần giải bất phương trình thứ hai $\sin x > \frac{1}{3}$. Không khó thấy rằng các giá trị $x$ sau đây thỏa mãn nó:
$$2k\pi + \text{arcsin} \frac{1}{3} < x < (2k + 1)\pi - \text{arcsin} \frac{1}{3}$$
($k = 0, \pm 1, \pm 2, \dots$).

Đó là đáp số cuối cùng cho bất đẳng thức đã cho. Sẽ là một sai lầm rất thô nếu, liên quan đến bất đẳng thức $\sin x < \frac{5}{4}$, trong «đáp số» xuất hiện «biểu thức» $\text{arcsin} \frac{5}{4}$. Vì $\frac{5}{4} > 1$, nên ký hiệu $\text{arcsin} \frac{5}{4}$ không có bất kỳ ý nghĩa nào.

Ví dụ 9. Giải bất đẳng thức $\log_2 \sin x < -1$.

Lời giải. Đặt ẩn phụ $y = \sin x$. Khi đó bất đẳng thức có dạng $\log_2 y < -1$. Vì $-1 = \log_2 \frac{1}{2}$ và với cơ số lớn hơn 1, số lớn hơn tương ứng với lôgarit lớn hơn, ta được $y < \frac{1}{2}$. Tuy nhiên còn phải chú ý (khi giải các bất đẳng thức như vậy người ta thường quên điều này!) rằng với các giá trị âm của đối số, hàm lôgarit

⟦folio 49⟧

Hoàn toàn không xác định. Vì vậy, ở dạng cuối cùng, nghiệm của bất đẳng thức $\log_2 y < -1$ được viết như sau:
$$0 < y < \frac{1}{2}.$$
Như vậy, ta đi đến hệ bất đẳng thức
$$\begin{cases} \sin x < \frac{1}{2}, \\ \sin x > 0. \end{cases}$$

Lập luận tương tự như trong ví dụ 5, ta được đáp số sau đây, gồm hai dãy:

$$\begin{cases} 2k\pi < x_1 < \frac{\pi}{6} + 2k\pi \\ (k = 0, \pm 1, \pm 2, \dots), \\ \frac{5\pi}{6} + 2m\pi < x_2 < \pi + 2m\pi \\ (m = 0, \pm 1, \pm 2, \dots). \end{cases}$$

Khác với các ví dụ 4 và 5, ở đây không thể đưa ra một công thức đơn giản gộp hai dãy này thành một.

Ví dụ 10. Giải bất đẳng thức
$$\log_x tg x > 0.$$

Lời giải. Ví dụ này phức tạp hơn các ví dụ trước, vì ẩn số $x$ ở đây đồng thời đóng hai vai trò khác nhau: vừa là cơ số của các lôgarit, vừa là đối số của hàm lượng giác. Nhờ đó, ở đây đặc biệt rõ nét là sự thể hiện của việc $x$ phải được hiểu như một số.

Trước hết, nhận thấy rằng vì $x$ là cơ số của các lôgarit, nên nhất thiết $x > 0$ và $x \neq 1$. Vì tính chất của lôgarit phụ thuộc đáng kể vào việc cơ số của chúng lớn hơn hay nhỏ hơn 1, ta xét riêng các trường hợp này.

Trước hết, giả sử $0 < x < 1$. Vì với cơ số nhỏ hơn 1, lôgarit dương có các số nằm giữa 0 và 1, ta được hệ bất đẳng thức $0 < tg x < 1$. Giải hệ này, ta được
$$k\pi < x < \frac{\pi}{4} + k\pi$$
($k = 0, \pm 1, \pm 2, \dots$).

Nhưng ta còn bị ràng buộc bởi điều kiện $0 < x < 1$. Từ hình 4 thấy rằng các bất đẳng thức $0 < x < 1, 0 < tg x < 1$ đồng thời chỉ được thỏa mãn bởi các giá trị $x$ sau: $0 < x < \frac{\pi}{4}$.

Bây giờ giả sử $x > 1$. Xét rằng với cơ số nhỏ hơn 1, các số lớn hơn 1 có lôgarit dương, ta được $tg x > 1$, do đó
$$\frac{\pi}{4} + k\pi < x < \frac{\pi}{2} + k\pi$$
($k = 0, \pm 1, \pm 2, \dots$).

Bây giờ xét điều kiện $x > 1$. Từ hình 5 ta thấy rằng cả hai bất đẳng thức $x > 1$ và $tg x > 1$ đồng thời

⟦folio 50⟧

thỏa mãn các giá trị $x$ sau đây: thứ nhất, $1 < x < \frac{\pi}{2}$, thứ hai
$$\frac{\pi}{4} + k\pi < x < \frac{\pi}{2} + k\pi$$
trong đó $k$ — số nguyên dương, tức là $k = 1, 2, 3, \dots$.

Tập hợp tất cả các giá trị $x$ tìm được khi xét cả hai trường hợp, ta nhận được đáp số cuối cùng sau đây:

$$0 < x_1 < \frac{\pi}{4},$$
$$1 < x_2 < \frac{\pi}{2},$$
$$\frac{\pi}{4} + k\pi < x_3 < \frac{\pi}{2} + k\pi$$
($k = 1, 2, 3, \dots$).

Cuối cùng, chúng tôi đưa ra một loạt ví dụ để tự giải.

Giải các bất đẳng thức:

1. $\cos x \geq \frac{1}{2}$.
2. $\sin 2x < \frac{1}{\sqrt{2}}$.
3. $\sin \frac{x}{5} \geq -\frac{1}{2}$.
4. $\lg(3x - 1) < \frac{1}{\sqrt{3}}$.
5. $|\lg x| \geq \sqrt{3}$.
6. $|\cos x| < \frac{1}{2}$.
7. $\sin^2 x < \frac{1}{4}$.
8. $\lg^2 x \geq \frac{1}{3}$.
9. $2\sin^2 x \leq \sin x$.
10. $2\cos^2 x + \cos x < 1$.
11. $\log_3(\lg x) \geq \frac{1}{2}$.
12. $\log_{\frac{1}{2}}(\cos x) \leq 1$.
