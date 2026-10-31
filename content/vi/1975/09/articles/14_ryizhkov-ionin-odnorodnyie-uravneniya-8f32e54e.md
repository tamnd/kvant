---
id: 1975-9-ryizhkov-ionin-odnorodnyie-uravneniya-8f32e54e
issue: kvant_1975_9
year: 1975
number: "9"
title: phương trình đồng nhất
authors:
  - Рыжков Л. В.
  - Ионин Ю. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 51
page_last: 56
page_labels: 49-54
tag: TNVS
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 0fa86125c60bec767b1ac0a097164158f9a1bd03b4f06148e3346ffc4eeec1ac
prompt_sha256: draft-1
translated_from: content/ru/1975/09/articles/14_ryizhkov-ionin-odnorodnyie-uravneniya-8f32e54e.md
source_content_sha256: 32b145a08622ecfa4ff2fd46ca5ad9ed08aed1f192ff89c5b059697f4b2c8959
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 49⟧

phương trình đồng nhất

Trong một khóa học toán ở trường, khái niệm “phương trình đồng nhất” (“hệ phương trình đồng nhất”) xuất hiện ít nhất ba lần. Do đó, đối với hệ lời giải của phương trình tuyến tính, hệ $^*$ được gọi là đồng nhất)

$$\begin{cases} ax + by = 0, \\ cx + dy = 0. \end{cases}$$

Khi xem xét các hệ phương trình bậc hai, người ta nói rằng hệ phương trình

$$\begin{cases} 14x^2 - 5xy + 3y^2 = 16, \\ 6x^2 - xy + y^2 = 8 \end{cases}$$

là một hệ phương trình tương đương, một trong số đó là đồng nhất và phương trình thứ hai là một trong các phương trình của hệ ban đầu $^*$). Đối với lời giải phương trình lượng giác $^*$), các phương trình được gọi là đồng nhất

$$\sin x - \cos x = 0,$$

$$\sin^2 x - 5 \sin x \cos x + 6 \cos^2 x = 0.$$

Điều gì hợp nhất các ví dụ trên và thuật ngữ “phương trình đồng nhất” như một khái niệm?

Đa thức $f(u, v)$ của hai biến được gọi là đa thức đồng nhất bậc $n$ nếu tất cả đều là một-

$^*$) E. S. Kochetkov, E. S. Kochetkova. Đại số và sự khởi đầu của phân tích. M., “Khai sáng”, 1974, phần 1, tr. 54.

$^*$) Như trên, tr. 142.

$^*$) Như trên, tr. 281.

về mặt số lượng chúng ta có độ $n$. Ví dụ,

$$f(u, v) = 2u^2 - 7uv + 9v^2$$

là đa thức đồng nhất bậc hai và

$$f(u, v) = u^3 - 15u^2v + 5v^3$$

là đa thức thuần nhất bậc ba.

Phương trình $f(u, v) = 0$ được gọi là phương trình thuần nhất bậc $k$ nếu $f(u, v)$ là đa thức thuần nhất bậc $k$.

Lưu ý rằng khái niệm về tính đồng nhất cũng mở rộng cho các phương trình có số lượng lớn ẩn số. Ví dụ, chúng ta sẽ nói rằng phương trình $x^3 + 3x^2y + 3xyz + z^3 = 0$ là phương trình bậc ba thuần nhất đối với các ẩn số $x, y$ và $z$.

Xét một phương trình đồng nhất bậc $n$ với hai ẩn số $x$ và $y$:

$$f(x, y) \equiv a_0x^n + a_1x^{n-1}y + a_2x^{n-2}y^2 + \dots + a_ny^n = 0.$$ (1)

Chúng tôi sẽ giả định rằng $a_0 \neq 0$.

Trường hợp $a_0 = 0$ phù hợp để chúng ta xem xét như sau: nếu lấy $y$ ra khỏi ngoặc ở mức độ nhỏ nhất thì trong ngoặc sẽ có đa thức đồng nhất với hệ số dẫn đầu khác 0. Ví dụ: phương trình $x^4y^2 + 3xy^5 - 7y^6 = 0$ có ​​dạng $y^2(x^4 - 3xy^3 - 7y^4) = 0$, sau đó tập hợp các phương trình $y^2 = 0, x^4 + 3xy^3 - 7y^4 = 0$ vẫn được coi là phương trình của phương trình ban đầu.

Lưu ý rằng cặp $x = 0, y = 0$ là nghiệm của phương trình (1), nhưng cặp $x = x_0, y = 0$ với $a_0 \neq 0, x_0 \neq 0$ không phải là nghiệm của phương trình (1)

⟦folio 50⟧

Là. Chia cả hai vế của phương trình (1) cho $y^n$, chúng ta thu được phương trình $n$ độ với một ẩn số $t = x/y$:

$$a_0 t^n + a_1 t^{n-1} + \dots + a_{n-1} t + a_n = 0. \tag{2}$$

Chúng ta sẽ sử dụng tính chất này của các phương trình đồng nhất cho lời giải cho dưới đây bài toán.

Chúng ta hãy tìm hiểu tập hợp các điểm trên mặt phẳng có tọa độ $x, y$ thỏa mãn phương trình (1). Trước hết, bộ này bao gồm gốc $O(0, 0)$. Sau đó, nếu $a_0 = 0$ thì lời giải $y = 0$ xuất hiện, xác định trục x. Và các nghiệm $t_1, t_2, \dots, t_k$ của phương trình (2) xác định các đường thẳng $x = t_1 y, x = t_2 y, \dots, x = t_h y$ đi qua gốc tọa độ (ví dụ: trong Hình 1 $t_1 = 1, t_2 = -1, t_3 = 2$).

Bài toán 1 (MSU, Khoa Sinh học, 1967). Một ô tô đi từ điểm A đến điểm B. Tuy nhiên, một người đi xe đạp đã đi thẳng về phía cô từ điểm B. Sau khi gặp nhau 3 phút, ô tô rẽ nhẹ, đi theo người đi xe đạp $u$, đi theo người này, quay lại và đến điểm B. Nếu ô tô rẽ nhẹ 1 phút sau cuộc họp và người đi xe đạp sau cuộc họp báo tốc độ 15/7 lần thì xe sẽ chết máy trên toàn bộ đoạn đường cùng lúc. Tìm tốc độ tối ưu của xe đạp và ô tô.

Gọi $x (km/min)$ là tốc độ của ô tô và $y (km/min)$ là tốc độ của xe đạp. Lưu ý rằng chuyển động từ điểm A đến nơi gặp người đi xe đạp đầu tiên trong trường hợp thứ nhất và thứ hai mất như nhau và chuyển động của ô tô từ nơi gặp người đi xe đạp đầu tiên đến điểm B cũng mất thời gian như nhau trong cả hai trường hợp. Do đó, chuyển động của ô tô diễn ra trong khoảng thời gian như nhau kể từ thời điểm gặp người đi xe đạp đầu tiên cho đến đoạn đường thứ hai đến địa điểm gặp nhau đầu tiên. Hãy tính thời gian này trong từng trường hợp.

I. Sau khi gặp người đi xe đạp, ô tô đi được 3 phút theo hướng điểm B. Đi thêm 3 phút nữa sẽ quay lại điểm hẹn. Trong thời gian này, người đi xe đạp sẽ di chuyển cách địa điểm tập trung 6 km. Chiếc xe sẽ đánh giá cao nó ở tốc độ $(x-y) \cdot km/min$, sẽ tốn $\frac{6y}{x-y} \cdot min$. Cô ấy cũng sẽ phải mất $\frac{6y}{x-y} \cdot min$ để quay lại điểm hẹn, nhưng chỉ $3+3+2 \cdot \frac{6y}{x-y} = \left(6 + \frac{12y}{x-y}\right) \cdot min$.

II. Dây sự tha hóa tương tự, chúng tôi nhận được

$$1 + 1 + \frac{2 \cdot \frac{15}{7} y}{x - \frac{15}{7} y} + \frac{2 \cdot \frac{15}{7} y}{x - \frac{15}{7} y} = \left(2 + \frac{60y}{7x - 15y}\right) \cdot min$$

Cân bằng các biểu thức tìm được, ta thu được phương trình

$$6 + \frac{12y}{x - y} = 2 + \frac{60y}{7x - 15y},$$

Ở đâu

$$7x^2 - 16xy - 15y^2 = 0.$$

Đây là phương trình bậc hai thuần nhất đối với $x$ và $y$. Polyag $t = x/y$ (tỷ lệ giữa vận tốc của ô tô và người đi xe đạp) và giải phương trình $7t^2 - 16t - 15 = 0$, ta tìm được $t = 3$ (gốc âm không thỏa mãn điều kiện).

⟦folio 51⟧

Trong bài toán này, chúng ta có một phương trình với hai biến độc lập. Trường hợp này khá hiếm; thông thường trong các bài toán, các biến được kết nối bằng một số tương ứng bổ sung.

Bài toán 2 (MISI). Giải phương trình

$$20 \left( \frac{x-2}{x+1} \right)^2 - 5 \left( \frac{x+2}{x-1} \right)^2 + 48 \frac{x^2-4}{x^2-1} = 0.$$

Hãy để chúng tôi giới thiệu những ẩn số mới $u = \frac{x-2}{x+1}$, $v = \frac{x+2}{x-1}$. Chúng ta thu được phương trình $20u^2 - 5v^2 + 48uv = 0$, đồng nhất bậc hai đối với $u$ và $v$. Phân cách cả hai phần của nó bằng $v^2$ (dễ dàng nhận thấy rằng trong trường hợp $u = v = 0$ không có lời giải) và đặt $\frac{u}{v} = t$. Chúng ta thu được phương trình $20t^2 + 48t - 5 = 0$ với các nghiệm $t_1 = -\frac{5}{2}$, $t_2 = \frac{1}{10}$.

Trong trường hợp đầu tiên $\frac{u}{v} = -\frac{5}{2}$; $\frac{x-2}{x+1} : \frac{x+2}{x-1} = -\frac{5}{2}$; $\frac{x^2-3x+2}{x^2+3x+2} = -\frac{5}{2}$; $7x^2 + 9x + 14 = 0$, phương trình này không có nghiệm thực sự.

Trong trường hợp thứ hai $\frac{u}{v} = \frac{1}{10}$; $\frac{x^2-3x+2}{x^2+3x+2} = \frac{1}{10}$; $3x^2 - 11x + 6 = 0$; $x_1 = 3$; $x_2 = \frac{2}{3}$.

Bài toán 3 (MISI). Giải phương trình

$$2(x^2+x+1)^2 - 7(x-1)^2 = 13(x^3-1).$$

Hãy đặt $u = x-1$, $v = x^2+x+1$. Khi đó phương trình sẽ có dạng $2v^2 - 7u^2 = 13uv$. Trong trường hợp $v = u = 0$ lời giải thì không. Chia cả hai vế của phương trình cho $v^2$ và đưa vào một ẩn số mới $t = \frac{u}{v}$, chúng ta thu được phương trình $7t^2 + 13t - 2 = 0$ với các nghiệm $t_1 = 1/7$, $t_2 = -2$.

Trong trường hợp đầu tiên, $\frac{x-1}{x^2+x+1} = \frac{1}{7}$, $x^2 - 6x + 8 = 0$, $x_1 = 2$, $x_2 = 4$; ở phần thứ hai $\frac{x-1}{x^2+x+1} = -2$, $2x^2 + 3x + 1 = 0$, $x_3 = -1$, $x_4 = -\frac{1}{2}$.

Đáp số: $x_1 = 2$, $x_2 = 4$, $x_3 = -1$, $x_4 = -\frac{1}{2}$.

Bài toán 4 (MISI). Giải phương trình

$$x^2 + 2x + 15 = 2x\sqrt{2x+15}.$$

Hãy giới thiệu thêm một điều chưa biết $u = \sqrt{2x+15}$. Chúng ta thu được một phương trình thuần nhất $x^2 + u^2 = 2xu$. Nó có thể được giải như bình thường hoặc có thể biểu diễn dưới dạng $(x-u)^2 = 0$, do đó $x = u$. Từ phương trình $x = \sqrt{2x+15}$ suy ra $x^2 - 2x - 15 = 0$, $x_1 = -3$, $x_2 = 5$. Giá trị $x = -3$ không thỏa mãn phương trình (3), nhưng $x = 5$ thì thỏa mãn.

Bài toán 5. Giải phương trình

$$2\sqrt[3]{x+1} - \sqrt[3]{x-1} = \sqrt[6]{x^2-1}.$$

Nếu đặt $u = x+1$, $v = x-1$, chúng ta sẽ nhận được một phương trình có thể gọi là “đồng nhất bậc 1/3” nếu có định nghĩa tương ứng. Để không phải đối phó với các bước phân đoạn, chúng tôi đặt

a) $u = \sqrt[6]{x+1}$, $u = \sqrt[6]{x-1}$, nếu $x \ge 1$;

b) $u = \sqrt[6]{-x-1}$, $v = \sqrt[6]{-x+1}$, nếu $x \leq -1$.

Trong trường hợp đầu tiên, chúng ta thu được phương trình $2u^2 - uv - v^2 = 0$, từ đó, bằng cách chia cho $v^2$, chúng ta tìm được $\sqrt[6]{x+1} = 1$, $x+1 = x-1$, sao cho phương trình ban đầu không có nghiệm trên khoảng $x \ge 1$.

Trong trường hợp thứ hai (tại $x \leq -1$), chúng ta thu được phương trình $-2u^2 - uv + v^2 =$

⟦folio 52⟧

= 0, từ đó $\sqrt[6]{\frac{x+1}{x-1}} = \frac{1}{2}$, $x = -\frac{65}{63}$.
Vì $-\frac{65}{63} \leq -1$, đây là nghiệm của phương trình ban đầu.

Bài toán 6. Giải hệ phương trình

$$\begin{cases}
3x^2 - 2xy - y^2 = 0, \\
x^2 + 5y = 6.
\end{cases}$$

Phương trình đầu tiên của hệ là thuần nhất bậc 2. Chia cả hai vế của nó cho $y^2$ (trường hợp $y = x = 0$ không phải là nghiệm của hệ) và đặt $t = \frac{x}{y}$, chúng ta thu được phương trình bậc hai $3t^2 - 2t - 1 = 0$, từ đó $t_1 = 1$, $t_2 = -\frac{1}{3}$. Do đó, $y = x$ hoặc $y = -3x$. Thay thế $y = x$ và sau đó $y = -3x$ vào phương trình thứ hai của hệ, chúng ta tìm thấy bốn lời giải của nó: $x_1 = y_1 = 1; x_2 = y_2 = -6$;

$$x_{3,4} = \frac{15 \mp \sqrt{249}}{2},$$
$$y_{3,4} = \frac{-45 \pm \sqrt{249}}{2}.$$

Bài toán 7. Giải hệ phương trình

$$\begin{cases}
3x^2 - \frac{25}{12}xy + 3y^2 = 50, \\
x^2 + y^2 = 25.
\end{cases}$$

Hệ thống này được đặc trưng bởi thực tế là tất cả các thuật ngữ chứa ẩn số đều có cấp độ thứ hai. Để loại bỏ số hạng tự do, chúng ta nhân phương trình thứ hai của hệ với 2 và trừ phương trình thứ nhất. Xét một hệ phương trình bao gồm phương trình thu được (đồng nhất) và phương trình thứ hai của hệ ban đầu:

$$\begin{cases}
x^2 - \frac{25}{12}xy + y^2 = 0, \\
x^2 + y^2 = 25.
\end{cases}$$

Hệ (5) tương đương với hệ (4).

Từ phương trình đầu tiên của hệ (5), đặt $t = \frac{x}{y}$, ta tìm được: $t_1 = \frac{3}{4}, t_2 = \frac{4}{3}$. Thay $x = \frac{3}{4}y$ và $x = \frac{4}{3}y$ vào phương trình thứ hai của hệ, ta tìm được bốn lời giải: $x_{1,2} = \pm 3, y_{1,2} = \pm 4; x_{3,4} = \pm 4, y_{3,4} = \pm 3$.

Phương trình đầu tiên của hệ (5) xác định một cặp đường thẳng có phương trình $x = \frac{3}{4}y$ và $x = \frac{4}{3}y$, phương trình thứ hai là phương trình đường tròn có bán kính 5 và tâm ở gốc tọa độ. Hệ Lời giải sẽ là tọa độ giao điểm của các đường thẳng với đường tròn (Hình 2).

Bài toán 8 (MISI). Giải hệ phương trình

$$\begin{cases}
2x^2 - 3xy + y^2 = 3, \\
x^2 + 2xy - 2y^2 = 6.
\end{cases}$$

Nhân phương trình thứ nhất của hệ với 2 và trừ phương trình thứ hai, ta thu được hệ

$$\begin{cases}
3x^2 - 8xy + 4y^2 = 0, \\
x^2 + 2xy - 2y^2 = 6,
\end{cases}$$

trong đó phương trình đầu tiên là đồng nhất, nó là lời giải $x = 2y$ và $x = \frac{2}{3}y$. Thay chúng vào phương trình thứ hai của hệ, ta tìm được hai lời giải: $x_{1,2} = \pm 2, y_{1,2} = \pm 1$.

Chúng ta hãy xem xét các ví dụ về phương trình lượng giác, lời giải trong số đó có thể rút gọn thành lời giải phương trình đồng nhất.

⟦folio 53⟧

Bài 9. *Giải phương trình*
$$2\sin x + 3\cos x = 0.$$

Phương trình này thuần nhất bậc một đối với sin x và cos x. Chia cả hai vế của phương trình cho cos x (dễ dàng thấy không có nghiệm). Chúng tôi có:
$$2\mathrm{tg}x + 3 = 0, \quad \mathrm{tg}x = -\frac{3}{2}, \quad x = -\mathrm{arctg}\frac{3}{2} + \pi k \quad (k - \text{целое}).$$

Phương trình $a\sin^2x + b\sin x\cos x + c\cos^2x = 0$ được rút gọn về dạng $a\mathrm{tg}^2x + b\mathrm{tg}x + c = 0$.

Bài 10. *Giải phương trình*
$$\sin^2x - 3\sin x\cos x + 2\cos^2x = 0.$$

Khi chia các phần của phương trình cho $\cos^2x$ sẽ không bị mất nghiệm nên ta được phương trình $\mathrm{tg}^2x - 3\mathrm{tg}x + 2 = 0$, từ đó $\mathrm{tg}x_1 = 1$, $x_1 = \frac{\pi}{4} + \pi k$; $\mathrm{tg}x_2 = 2$, $x_2 = \mathrm{arctg}2 + \pi m \quad (k, m - \text{целые}).$

Phương trình $a\sin x + b\cos x = c$ cho phép có nhiều cách lời giải. Nó có thể được rút gọn thành một phương trình đồng nhất cho sin $\frac{x}{2}$ và cos $\frac{x}{2}$ bằng cách thay thế sin $x = 2\sin \frac{x}{2} \times \cos \frac{x}{2}$, cos $x = \cos^2\frac{x}{2} - \sin^2\frac{x}{2}$, $c = c\left(\cos^2\frac{x}{2} + \sin^2\frac{x}{2}\right)$.

Bài 11. *Giải phương trình*
$$3\sin x + 5\cos x = -3.$$

Chúng tôi có: $3\sin x + 5\cos x - 3, \quad \sin^2\frac{x}{2} - 3\sin \frac{x}{2}\cos \frac{x}{2} - 4\cos^2\frac{x}{2} = 0, \quad \mathrm{tg}^2\frac{x}{2} - 3\mathrm{tg}\frac{x}{2} - 4 = 0, \quad \mathrm{tg}\frac{x_1}{2} = -4, \quad x_1 = 2\mathrm{arctg}4 + 2\pi k; \quad \mathrm{tg}\frac{x_2}{2} = -1, \quad x_2 = -\frac{\pi}{2} + 2\pi m \quad (k, m - \text{целые}).$

Lưu ý rằng phương trình lời giải $a\sin x + b\cos x = c$ bằng cách đưa ra một đối số phụ không phải lúc nào cũng thuận tiện. Ví dụ, giải phương trình (6) bằng phương pháp này, ta thu được
$$3\sin x + 5\cos x$$

$$\sqrt{34}\left(\frac{3}{\sqrt{34}}\sin x + \frac{5}{\sqrt{34}}\cos x\right) =$$

$$= \sqrt{34}\sin \left[x + \arcsin \frac{5}{\sqrt{34}}\right],$$

$$\sin \left(x + \arcsin \frac{5}{\sqrt{34}}\right) = -\frac{3}{\sqrt{34}},$$

$$x = (-1)^{m+1}\arcsin \frac{3}{\sqrt{34}} -$$

$$- \arcsin \frac{5}{\sqrt{34}} + \pi m \quad (m - \text{целое}).$$

Ý tưởng sử dụng tính đồng nhất ở lời giải của các phương trình lượng giác được làm phong phú nhờ khả năng tăng 2 độ của một năm so với $u = \sin x$, $v = \cos x$ bằng cách nhân chúng với $\sin^2x + \cos^2x$.

Bài 12. *Giải phương trình*
$$4\sin^3x = \sin x + \cos x.$$

Nhân vế phải của phương trình với $\sin^2x + \cos^2x$ rồi chia cả hai vế cho $\cos^3x$, ta thu được phương trình
$$3\mathrm{tg}^3x - \mathrm{tg}^2x - \mathrm{tg}x - 1 = 0.$$

Đoán rằng khi phân tích vế trái thành thừa số thì một trong số chúng phải bằng $\mathrm{tg}x - 1$ (vì $\mathrm{tg}x = 1$ thỏa mãn phương trình) nên chúng ta dễ dàng tìm được phân tích này
$(\mathrm{tg}x - 1)(3\mathrm{tg}^2x + 2\mathrm{tg}x + 1) = 0$

và đáp số: $x = \frac{\pi}{4} + \pi k \quad (k - \text{целое}).$

Việc thay thế thành công cũng có thể biến một số phương trình hàm mũ thành phương trình thuần nhất.

Nhiệm vụ 13 (MSU, Khoa Hóa học, 1964). *Giải phương trình*
$$4^x = 2.14^x + 3.49^x.$$

Polyag $2^x = u, 7^x = v$, chúng ta đi đến phương trình bậc hai đồng nhất $u^2 - 2uv$ đối với $u$ và $v$

⟦folio 54⟧

- 3v² = 0. Giải phương trình này, ta tìm được:

a) $\frac{u}{v} = -1, \left(\frac{2}{7}\right)^x = -1$ – quyết định không;

6) $\frac{u}{v} = 3, \left(\frac{2}{7}\right)^x = 3, x = \log_{\frac{2}{7}} 3$.

Bài tập

1 (MSU, cơ chế, 1964). Giải phương trình $6\sqrt[3]{x-3} + \sqrt[3]{x-2} = 5\sqrt[6]{(x-2)(x-3)}$.

2 (NSU, 1970). Giải phương trình $5^{\log_2(x^2)} - 3^2\log_4(x^2/2) = \sqrt[3]{\log_2(\sqrt{2}/2)(2x^2)} - 5^{\log_2(x^2)} - 1$.

3 (UDN, 1971). Giải phương trình $(3 - 2\sqrt{2})^{x^2} - 6x + 9 + (3 + 2\sqrt{2})^{x^2} - 6x + 9 = 6$.

4 (MSU, Khoa Địa lý, 1960). Giải phương trình $\sin 2x - \mathrm{tg} \frac{\pi}{6} \cos 2x = 1$.

5 (MSU, Khoa Sinh học, 1966). Giải phương trình $2\sin 4x - 3\sin^2 2x = 1$.

6 (MSU, Khoa Hóa học, 1964). Giải phương trình $3\cos^2 x - \sin^2 x - \sin 2x = 0$.

7. Giải hệ phương trình

$$\begin{cases} x^2 + y\sqrt{xy} = 420, \\ y^2 + x\sqrt{xy} = 280. \end{cases}$$

8 (LPI, 1963). Giải hệ phương trình

$$\begin{cases} \frac{x^2 + y^2}{xy} = \frac{5}{2}, \\ x^2 - y^2 = 3. \end{cases}$$

9 (POI, 1964). Giải phương trình $7.3^{x+1} - 5^{x+2} = 3^{x+4} - 5^{x+3}$.

10 (MSU, Khoa Địa lý, 1967). Nước sạch bắt đầu chảy vào bể trống qua hai đường ống cùng lúc và nước không đổi bắt đầu chảy. Sau khi điền
