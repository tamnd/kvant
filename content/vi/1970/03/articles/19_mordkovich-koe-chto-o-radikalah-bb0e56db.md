---
id: 1970-3-mordkovich-koe-chto-o-radikalah-bb0e56db
issue: kvant_1970_3
year: 1970
number: "3"
title: Đôi điều về căn thức
authors:
  - Мордкович А. Г.
rubric: raznoe
rubric_sub: Разное
page_first: 55
page_last: 59
page_labels: 53-57
tag: Q3LL
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 21da649542f3cb50e1e163b2e870f04f94a2d86219ede9e72ef1d45efbb1c173
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1970/03/articles/19_mordkovich-koe-chto-o-radikalah-bb0e56db.md
source_content_sha256: c5413f2dd1175d2141e3351e3944ba75a8dc49cde0d4c495e50ccbfcbff17c45
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-30
---

⟦folio 53⟧

ĐÔI ĐIỀU VỀ CĂN THỨC

A. G. MORDKOVICH

— Bây giờ, — Người khảo thí nói, — tôi muốn đề nghị với anh thêm một bài toán nữa, khá đơn giản. Đây là bài toán:

Tìm các cạnh của một tam giác vuông, biết rằng hình chiếu của một cạnh góc vuông lên cạnh huyền bằng 6 cm, còn hình chiếu của cạnh góc vuông kia nhỏ hơn độ dài của cạnh góc vuông đó 1,5 cm.

... Vài phút sau Thí sinh đến gặp Người khảo thí.
— Thế nào, anh đã giải bài toán chưa? — Người khảo thí hỏi.
— Rồi! — Thí sinh đáp.
— Và kết quả thế nào?
— Bài toán vô nghiệm.
— Và anh có thể chứng minh điều đó không?

— Tất nhiên! Xét tam giác ABC (xem hình); C — đỉnh của góc vuông, CH — đường cao. Đặt AC = x, khi đó theo giả thiết AH = = x—1,5, còn BH = 6.

⟦folio 54⟧

Dùng hệ thức đã biết
$$CH^2 = BH \cdot AH$$ hoặc $$CH^2 = 6(x - 1,5).$$

Áp dụng định lý Pythagore cho tam giác vuông $ACH$, ta được

$$\sqrt{AC^2 - CH^2} = AH,$$

tức là

$$\sqrt{x^2 - 6(x - 1,5)} = x - 1,5.$$

— Vậy thì, đến đây mọi thứ đều đúng, — Người khảo thí nhận xét, — mặc dù phải nói rằng cách giải được chọn không phải là hợp lý nhất.

— Còn tiếp theo, — Thí sinh nói tiếp, — chỉ còn những phép tính đơn giản:

$$\sqrt{x^2 - 6x + 9} = x - 1,5; \quad \sqrt{(x - 3)^2} = x - 1,5;$$

$$x - 3 = x - 1,5; \quad -3 = -1,5.$$

Vì đẳng thức cuối cùng sai, nên bài toán vô nghiệm.

— Tiếc rằng tôi phải làm anh thất vọng, — Người khảo thí nói, — bài toán có nghiệm. Chẳng hạn, có thể giải như sau: từ hệ thức đã biết $AC^2 = AB \cdot AH$ ta có $x^2 = (x + 4,5) (x - 1,5), 3x = 4,5 \cdot 1,5$ và $x = 2,25$, tức là $AC = 2,25$ cm. Khi đó $AB = 6,75$ cm, còn $BC = 4\sqrt{2}$ cm.

Và, bắt gặp ánh mắt ngạc nhiên của Thí sinh, Người khảo thí nói thêm:

— Có lẽ anh muốn biết sai lầm nằm ở đâu trong lập luận của anh. Vậy thì, chúng ta hãy xem xét.

SAI Ở ĐÂU?

— Anh còn nhớ, — Giám khảo bắt đầu, — rằng tôi, tuy có bảo lưu, đã chấp nhận lập luận hình học của anh. Vậy thì sai lầm chỉ có thể xảy ra trong điều anh gọi là «những phép tính đơn giản». Chính xác hơn, sai lầm đã mắc phải khi lấy căn bậc hai. Anh chưa học rằng, theo ý nghĩa của bài toán, đại lượng $\sqrt{(x - 3)^2}$ phải dương. Và nói chung, trong tập số thực, dấu $\sqrt{}$ hàm ý giá trị số học, không âm của căn. Chẳng hạn, $\sqrt{16} = 4$, và không thể viết rằng $\sqrt{16} = -4$ hoặc $\sqrt{16} = \pm 4$. Vì vậy không thể khẳng định rằng luôn luôn $\sqrt{a^2} = a$: khi $a \geq 0$ đẳng thức này đúng, nhưng số $a$ cũng có thể âm! Chẳng hạn, hãy rút gọn $\sqrt{(-3)^2}$:

Thí sinh viết:

$$\sqrt{(-3)^2} = \sqrt{9} = 3.$$

— Đúng. Nói cách khác,

$$\sqrt{(-3)^2} = -(-3).$$

Và nói chung, nếu $a < 0$, thì $\sqrt{a^2} = -a$.

Do đó,

$$\sqrt{a^2} = \begin{cases} a, если a \geq 0, \\ -a, если a < 0. \end{cases}$$

— Tôi hiểu rồi, — Thí sinh kêu lên, — điều này có thể viết gọn như sau: $\sqrt{a^2} = |a|$, vì môđun của $a$ được xác định hoàn toàn tương tự:

$$|a| = \begin{cases} a, nếu a \geq 0, \\ -a, nếu a < 0. \end{cases}$$

— Hoàn toàn đúng. Trong bài toán của bạn cũng vậy: không thể viết

⟦folio 55⟧

$$\sqrt{(x-3)^2} = (x-3), \text{ vì } (x-3) \text{ có thể là một số âm.}
\text{Nếu dùng điều rằng } \sqrt{(x-3)^2} = |x-3|, \text{ thì ta đi đến phương trình } |x-3| = x-1, 5.$$

Tiếp theo cần xét hai trường hợp: 1) $x-3 \geq 0$; 2) $x-3 < 0$. Bạn chỉ xét trường hợp thứ nhất, vì vậy kết luận rằng bài toán không có nghiệm là vội vàng. Trong trường hợp thứ hai $|x-3| = -(x-3)$. Khi đó từ phương trình $-(x-3) = x-1, 5$ ta được $x = 2, 25$, tức là $AC = 2, 25$ cm.

Mọi việc đều rõ, — Thí sinh nói.
Trong trường hợp đó, ta sẽ coi cuộc trò chuyện của chúng ta là kết thúc. Khi chia tay, xin cho phép tôi đưa ra cho bạn lời khuyên sau:

Đừng quên rằng $\sqrt{a^2} = |a|!$

Đến đây chúng ta chia tay Thí sinh và Giám khảo, nhưng sẽ ghi nhớ lời khuyên của Giám khảo. Đặc biệt, sẽ áp dụng nó khi giải ví dụ sau.

Ví dụ 1. Rút gọn biểu thức

$$\sqrt{\frac{a+x^2}{x} - 2\sqrt{a}} + \sqrt{\frac{a+x^2}{x} + 2\sqrt{a}}, \text{ nếu } x > \sqrt{a}.$$

Lời giải. Ta có

$$\sqrt{\frac{a+x^2-2x\sqrt{a}}{x}} + \sqrt{\frac{a+x^2+2x\sqrt{a}}{x}} =$$

$$\frac{\sqrt{(V\bar{a}-x)^2}}{\sqrt{x}} + \frac{\sqrt{(V\bar{a}+x)^2}}{\sqrt{x}} = \frac{|V\bar{a}-x|}{V\bar{x}} + \frac{|V\bar{a}+x|}{V\bar{x}}.$$

Vì theo điều kiện $x > \sqrt{a} \geq 0$, nên $|V\bar{a}-x| = -V\bar{a} + x$, $|V\bar{a}+\bar{x}| = \sqrt{a} + x$, và biểu thức đã cho biến đổi như sau:

$$\frac{-V\bar{a} + x + \sqrt{a} + x}{\sqrt{x}} = 2\sqrt{x}.$$

VÀI LỜI VỀ CÁC TÍNH CHẤT CỦA CĂN THỨC

Khi giải các ví dụ về phép toán với căn thức, phải áp dụng nhiều tính chất khác nhau của căn thức. Chẳng hạn, trong ví dụ 1 chúng ta đã sử dụng, hơn nữa khá vô tư, tính chất quen thuộc:

$$\sqrt{\frac{a}{b}} = \frac{\sqrt{a}}{b}.$$

Tuy nhiên, cần lưu ý rằng đẳng thức này chỉ đúng khi $a \geq 0$ và $b > 0$. Nếu $a$ và $b$ là các số âm, thì biểu thức $\frac{\sqrt{a}}{b}$ không có nghĩa trong phạm vi các số thực. Trong ví dụ 1, về phần chúng ta, đã không có sai lầm, vì $(V\bar{a}-x)^2 > 0$, $(V\bar{a}+x)^2 > 0$ và, hơn nữa, theo điều kiện $x > 0$. Nhưng dù sao, từ những điều nói trên có thể rút ra kết luận sau: cần hết sức cẩn thận khi khai căn (bậc chẵn) của một tích hoặc một phân thức. Trong trường hợp tổng quát, khi dấu của $a$ và $b$ chưa biết, nên lập luận như sau:

$$\sqrt{\frac{a}{b}} = \sqrt{\frac{|a|}{|b|}} = \sqrt{\frac{|a|}{|b|}}.$$

⟦folio 56⟧

Vậy, nếu các số $a$ và $b$ cùng dấu thì

$$\sqrt{\frac{a}{b}} = \frac{\sqrt{|a|}}{\sqrt{|b|}}$$

và tương tự

$$\sqrt{ab} = \sqrt{|a|} \cdot \sqrt{|b|}.$$

Ví dụ 2. Rút gọn

$$\sqrt{\frac{a-\sqrt{x}}{a+\sqrt{x}}} + \sqrt{\frac{a+\sqrt{x}}{a-\sqrt{x}}} - \sqrt{\frac{16}{a^2-x}},$$ nếu $x = 4(a-1)$.

Lời giải. Ngược lại, biểu diễn $a$ theo $x$: $a = \frac{x+4}{4}$, rồi thay vào biểu thức đã cho. Nó biến đổi như sau:

$$\sqrt{\frac{x-4\sqrt{x}+4}{x+4\sqrt{x}+4}} + \sqrt{\frac{x+4\sqrt{x}+4}{x-4\sqrt{x}+4}} - \sqrt{\frac{16^2}{(x+4)^2-16x}}$$

$$= \frac{|\sqrt{x}-2|}{|\sqrt{x}+2|} + \frac{|\sqrt{x}+2|}{|\sqrt{x}-2|} - \frac{16}{\sqrt{x^2}-8x+16}$$

$$= \frac{(x-4\sqrt{x}+4) + (x+4\sqrt{x}+4)}{|(\sqrt{x})^2-4|} - \frac{16}{|x-4|} = \frac{2x+8}{|x-4|} - \frac{16}{|x-4|} = 2\frac{x-4}{|x-4|}.$$

Cũng lưu ý rằng $x > 4$, nếu $a > 2$, và $x < 4$, nếu $1 \leqslant a < 2$.

Đáp số cuối cùng:

2, nếu $a > 2$,
- 2, nếu $1 \leqslant a < 2$.

Ta đã dùng — và điều này thường hữu ích — tính chất sau của giá trị tuyệt đối: với mọi $a$ và $b$

$$|a| \cdot |b| = |ab|, \quad |a|^2 = a^2.$$

Bây giờ ta sẽ dừng lại ở một tính chất quan trọng khác của căn.

Ví dụ 3. Rút gọn

$$\sqrt[10]{\frac{1}{2}(19+6\sqrt{10})} \sqrt[5]{3\sqrt{2}-2\sqrt{5}}.$$

Lời giải. Thường người ta lập luận như sau. Dùng tính chất đã biết của căn, có thể nhân chỉ số căn của thừa số thứ hai với 2 và đồng thời nâng biểu thức dưới căn lên bình phương; ta được

$$\sqrt[10]{\frac{1}{2}(19+6\sqrt{10})} \sqrt[5]{3\sqrt{2}-2\sqrt{5}}$$

$$= \sqrt[10]{\frac{1}{2}(19+6\sqrt{10})} \sqrt[10]{(3\sqrt{2}-2\sqrt{5})^2}$$

$$= \sqrt[10]{\frac{1}{2}(19+6\sqrt{10})} \sqrt[10]{19^2-(6\sqrt{10})^2} = \sqrt[10]{1} = 1.$$

Nhưng ở đây có sai lầm! Đáp số đúng là trừ một. Vấn đề là $3\sqrt{2}-2\sqrt{5} < 0$, vì $(3\sqrt{2})^2 = 18 < (2\sqrt{5})^2 = 20$.

Vì vậy, không đúng rằng $\sqrt[5]{3\sqrt{2}-2\sqrt{5}} = \sqrt[10]{(3\sqrt{2}-2\sqrt{5})^2}$, mà đúng là $\sqrt[5]{3\sqrt{2}-2\sqrt{5}} = -\sqrt[5]{2\sqrt{5}-3\sqrt{2}} = -\sqrt[10]{(2\sqrt{5}-3\sqrt{2})^2}$.

Ví dụ 4. Rút gọn $\sqrt[8]{(\pi^2-10)^4}$.

⟦folio 57⟧

Ở đây cũng sẽ không đúng nếu chỉ đơn giản chia số mũ của căn và của biểu thức dưới dấu căn cho 4:

$$\sqrt[8]{(\pi^2 - 10)^4} = \sqrt{\pi^2 - 10}$$

(kết quả thu được không có nghĩa, vì $\pi^2 < 10$). Đúng là đẳng thức sau:

$$\sqrt[8]{(\pi^2 - 10)^4} = \sqrt{10 - \pi^2}.$$

Cuối cùng, ta đi đến kết luận sau:

Khi sử dụng các tính chất cơ bản của căn thức trong những trường hợp không chắc rằng dưới dấu căn là một số dương, cần chú ý để, thứ nhất, kết quả thu được có nghĩa (khi cần thiết, dấu môđun sẽ giúp ta) và, thứ hai, để kết quả thu được có cùng dấu với biểu thức ban đầu tương ứng.

BÀI TẬP

1. Hãy nêu các điều kiện để các đẳng thức sau đúng ($k$ và $n$ là các số tự nhiên):

a) $$\sqrt[n]{-a} = -\sqrt[n]{a};$$
e) $$a \cdot \sqrt[n]{b} = \sqrt[n]{a^n b};$$
6) $$\sqrt[n]{a^n} = a;$$
ж) $$\sqrt[n]{a} = \sqrt[n]{a^k};$$
b) $$(\sqrt[n]{a})^n = a;$$
з) $$\sqrt[k]{\sqrt[n]{a}} = \sqrt[k]{a};$$
г) $$\sqrt[n]{a \cdot b} = \sqrt[n]{a} \cdot \sqrt[n]{b};$$
и) $$(\sqrt[n]{a})^k = \sqrt[n]{a^k};$$
д) $$\sqrt[n]{\frac{a}{b}} = \frac{\sqrt[n]{a}}{n \sqrt[n]{b}};$$
к) nếu $a < b$, thì $$\sqrt[n]{a} < \sqrt[n]{b}$$.

2. Rút gọn các biểu thức sau:

a) $$(\sqrt{\frac{a+1}{a-1}} + \sqrt{\frac{a-1}{a+1}}) \cdot (\sqrt{\frac{a+1}{a-1}} - \sqrt{\frac{a-1}{a+1}});$$
6) $$\sqrt{\frac{3y+x^3}{2x}} + \sqrt{3xy} - \sqrt{\frac{3y+x^3}{2x}} - \sqrt{3xy};$$
b) $$\frac{(4a^2m^{-2} + a^{-2}m^2 - 4)^{-1/2}}{2ma (m^2 - a^2)^{-1/2}} \cdot \left(2 \sqrt{m^4 - \frac{a^2}{m^{-2}}} - \frac{2a^2}{\sqrt{1 - a^2}m^{-2}}\right);$$
г) $$\frac{a + \sqrt{2 + \sqrt{5}} \cdot \sqrt[12]{(9 - 4\sqrt{5})^3}}{\sqrt[3]{2 - \sqrt{5}} \cdot \sqrt[6]{9 + 4\sqrt{5}} - \sqrt[3]{a^2} + \sqrt[3]{a}}.$$
