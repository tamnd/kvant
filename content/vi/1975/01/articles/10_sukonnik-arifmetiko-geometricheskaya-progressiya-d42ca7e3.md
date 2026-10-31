---
id: 1975-1-sukonnik-arifmetiko-geometricheskaya-progressiya-d42ca7e3
issue: kvant_1975_1
year: 1975
number: "1"
title: Cấp tiến số học-hình học
authors:
  - Суконник Я. Н.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 38
page_last: 40
page_labels: 36-38
tag: PPLZ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: e1d492d01b8df214175147aff65f23ea000af898dcd268bd14430953c1c1f998
prompt_sha256: draft-1
translated_from: content/ru/1975/01/articles/10_sukonnik-arifmetiko-geometricheskaya-progressiya-d42ca7e3.md
source_content_sha256: 6b0588f272ef65c305545680949173fb6cbee224cc9251557178811ee51f78bc
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦rubric⟧ VÒNG TRÒN TOÁN HỌC

## Cấp tiến số học-hình học
Y. N. Sukonnik

Toán học có thể được nghiên cứu theo nhiều cách khác nhau. Bạn có thể nghe giảng hoặc lấy một cuốn sách dày và đọc liên tiếp: định nghĩa, định lý, chứng minh. Hoặc bạn có thể hành động tích cực hơn: đọc các định nghĩa và phát biểu của các định lý, đặt cuốn sách sang một bên và tự mình đưa ra cách chứng minh. Phương pháp đầu tiên giúp bạn có thể di chuyển nhanh hơn lúc đầu. Nhưng chỉ có phương pháp thứ hai mới giúp bạn hiểu sâu lý thuyết toán học, nhớ lâu và học cách áp dụng nó. Vì vậy, phương pháp này – sự khám phá độc lập những chân lý cũ – thường được sử dụng trong các hội thảo, trường học và câu lạc bộ toán học.

Chính loại hoạt động tích cực này của độc giả mà các bài báo xuất bản trong phần “Vòng tròn toán học” được thiết kế dành cho. Thông thường những bài viết này là một loạt bài toánthống nhất bởi một chủ đề hoặc phương pháp chung lời giải. Một số trong số chúng được giải quyết trong văn bản, nhưng hầu hết - cả dễ và khó - đều được để độc lập lời giải tới người đọc. Đôi khi ngắn gọn lời giải những cái này bài toán (hoặc gợi ý Và đáp số) được đăng trong cùng một số, nhưng thường xuyên hơn - ở một trong những số tiếp theo của tạp chí ở những trang cuối cùng.

Theo quy định, “Câu lạc bộ Toán học” của chúng tôi dành cho học sinh từ lớp 8-9, và đôi khi thậm chí là lớp 7. Vui lòng gửi thư kèm theo nhận xét và đề xuất về phần này với ghi chú “Vòng tròn Toán học” trên phong bì.

Nhiều người tham gia Olympic toàn Liên minh duy trì thư từ thường xuyên với Vòng tròn Toán học.

⟦column⟧

Bài viết này xem xét một chuỗi có thể được gọi đại khái là *cấp số số học-hình học*; nó được đưa ra bởi mối quan hệ tái phát sau đây:

$$u_1 = a_1, \quad u_{n+1} = qu_n + d, \qquad (1)$$

trong đó $q$ và $d$ là các tham số không đổi. Đặt $q = 1$ vào (1), chúng ta có được một cấp số *số học*

$$u_1 = a_1, \quad u_{n+1} = u_n + d,$$

đặt $d = 0$, - *hình học*:

$$u_1 = a_1, \quad u_{n+1} = qu_n.$$

(Điều này giải thích tại sao chúng tôi gọi chuỗi (1) là cấp số cộng-hình học. Bằng cách tương tự, chúng tôi sẽ nói rằng $q$ là mẫu số và $d$ là hiệu của cấp số cộng-hình học.)

Ví dụ về cấp số cộng-hình học

a) $1, \ \dfrac{3}{2}, \ \dfrac{7}{4}, \ \dfrac{15}{8}, \ \dfrac{31}{16}, \ \cdots$

$$\left(u_1 = 1, \ q = \frac{1}{2}, \ d = 1\right);$$

b) $-1, \ \dfrac{3}{2}, \ \dfrac{1}{4}, \ \dfrac{7}{8}, \ \dfrac{9}{16}, \ \cdots$

$$\left(u_1 = -1, \ q = -\frac{1}{2}, \ d = 1\right).$$

Ý tưởng nói về các trình tự như vậy được thúc đẩy bởi bài toán M97, được xuất bản trên «Kvant» Số 8 năm 1971 (trong “Bài toán Kvant”). Đây là tình trạng của cô ấy (có sửa đổi một chút):

⟦folio 36⟧

*Trong hình thang $AA_1B_1B$ có đáy $AB = a$ và $A_1B_1 = a_1$ $(a < a_1)$ một đoạn $A_2B_2$ được vẽ nối trung điểm của các đường chéo. Trong hình thang thu được $AA_2B_2B$, đoạn $A_3B_3$ một lần nữa được vẽ, nối trung điểm của các đường chéo, v.v. Tìm độ dài của đoạn $A_{n+1}B_{n+1}$.*

Hình 1 thể hiện hình thang $AA_nB_nB$ - ở đây $AB = a$, $CD$ là đường giữa của hình thang, $A_{n+1}$ và $B_{n+1}$ là trung điểm của các đường chéo $A_nB$ và $AB_n$. Rõ ràng là các điểm $A_{n+1}$ và $B_{n+1}$ nằm trên $CD$. Biểu thị độ dài của các đoạn $A_nB_n$ và $A_{n+1}B_{n+1}$ bằng $a_n$ và $a_{n+1}$, ta thu được

$$a_{n+1} = |A_{n+1}B_{n+1}| =$$
$$= |A_{n+1}D| - |B_{n+1}D| = \frac{1}{2}\,a_n - \frac{1}{2}\,a,$$

và do đó, độ dài của các đoạn $A_nB_n$ tạo thành một *cấp số số học-hình học* một cách chính xác.

Một cấp số cộng-hình học có các đặc điểm của cả cấp số cộng và cấp số hình học. Chúng ta hãy rút ra công thức cho số hạng tổng quát của nó.

Đặt trong mối quan hệ (1) $q \neq 1$ (và $d \neq 0$). Thêm biểu thức $\dfrac{d}{q-1}$ vào cả hai vế của (1), chúng ta thu được

$$u_{n+1} + \frac{d}{q-1} = q\left(u_n + \frac{d}{q-1}\right).$$

Xét rằng mối quan hệ này là hồi quy, chúng ta viết các đẳng thức tương tự cho $k = n+1, n, \ldots, 2$:

$$u_{n+1} + \frac{d}{q-1} = q\left(u_n + \frac{d}{q-1}\right),$$

$$u_2 + \frac{d}{q-1} = q\left(a_1 + \frac{d}{q-1}\right).$$

Bằng cách nhân các đẳng thức viết được và trừ các thừa số giống nhau, chúng ta thu được *công thức tính số hạng tổng quát của cấp số cộng-hình học*

$$\boxed{u_{n+1} = q^n\left(a_1 + \frac{d}{q-1}\right) + \frac{d}{1-q}.}\qquad(2)$$

⟦column⟧

⟦figure⟧
Hình 1.

Trong bài toán M97 $a_{n+1} = \dfrac{1}{2}\,a_n - \dfrac{1}{2}\,a$, tức là $q = \dfrac{1}{2}$, $d = -\dfrac{1}{2}\,a$; Đó là lý do tại sao

$$a_{n+1} = |A_{n+1}B_{n+1}| = \frac{1}{2^n}\,(a_1 + a) - a.$$

Bây giờ chúng ta hãy xây dựng một số tính chất cơ bản của cấp số cộng-hình học (chúng tôi để lại cách chứng minh cho độc giả).

$1^\circ$. Cấp số nhân-hình học (1) là *chuỗi hồi quy bậc hai*\*) và được cho bởi phương trình

$$u_{n+1} = (q+1)\,u_n - qu_{n-1}.\qquad(3)$$

Cụ thể, với $q = 1$ ta thu được tính chất đặc trưng của cấp số cộng

$$u_n = \frac{u_{n-1} + u_{n+1}}{2}.$$

Hệ quả: Mẫu số $q$ của cấp số cộng - hình học được xác định theo công thức

$$q = \frac{u_{n+1} - u_n}{u_n - u_{n-1}}.\qquad(4)$$

$2^\circ$. Hiệu $d$ của cấp số cộng-hình học được xác định

---

\*) Dãy số $u_1, u_2, \ldots, u_n, \ldots$ được gọi là *chuỗi trả về thứ $k$* nếu có một số tự nhiên $k$ và các số $a_1, a_2, \ldots, a_k$ sao cho, bắt đầu từ một số $N$ và cho tất cả các số tiếp theo $m \geqslant N$
$$u_{m+k} = a_1u_{m+k-1} + a_2u_{m+k-2} + \ldots + a_ku_m.$$
Mối quan hệ cuối cùng được gọi là *phương trình nghịch đảo bậc $k$*.

⟦folio 37⟧

theo công thức

$$d = \frac{u_n^2 - u_{n-1}\cdot u_{n+1}}{u_n - u_{n-1}}. \qquad (5)$$

Cụ thể, nếu $d = 0$ (và $q \neq 1$), chúng ta thu được tính chất đặc trưng của cấp số nhân

$$u_n = \sqrt{u_{n-1}\cdot u_{n+1}}.$$

$3^\circ$ (*tính chất đặc trưng của cấp số cộng-hình học*). Dãy số $\{a_n\}$, trong đó $a_n = u_{n+1} - u_n$, là một cấp số nhân có cùng mẫu số $q$, tức là

$$|u_{n+1} - u_n| =$$
$$= \sqrt{|u_n - u_{n-1}|\cdot|u_{n+2} - u_{n+1}|}. \qquad (6)$$

$4^\circ$. Tiếp theo

$$S_1 = u_1, \quad S_2 = u_1 + u_2, \quad \ldots,$$
$$S_n = u_1 + \ldots + u_n,$$
$$S_{n+1} = S_n + u_{n+1}, \quad \ldots$$

*tổng riêng* của các số hạng của cấp số cộng-hình học là một dãy nghịch đảo bậc ba và được cho bởi phương trình sau:

$$S_{n+1} = (q+2)\,S_n -$$
$$- (2q+1)\,S_{n-1} + qS_{n-2}. \qquad (7)$$

$5^\circ$. Nếu dãy tổng riêng $S_1$, $\ldots$, $S_n$, $\ldots$ là một cấp số cộng-hình học thì dãy $u_1, \ldots, u_n \ldots$ là một cấp số nhân.

Nhận xét. Từ công thức tính số hạng tổng quát của cấp số cộng-hình học (xem công thức (2)), ta suy ra rằng

a) đối với $|q| < 1$ cấp số cộng-hình học *hội tụ* (và đối với $0 \leqslant q < 1$ - *đơn điệu*) với số

$$A = \lim_{n \to \infty} u_n = \frac{d}{1-q};$$

b) tại $|q| \geqslant 1$ cấp số cộng-hình học *phân kỳ*.

Cụ thể, bằng cách hướng số $n$ trong bài toán M97 đến vô cùng, chúng ta thu được số đó trong giới hạn

$$b = \lim_{n \to \infty}|A_{n+1}B_{n+1}| = \left|\frac{-\dfrac{1}{2}\,a}{1 - \dfrac{1}{2}}\right| = a.$$

⟦column⟧

(Thật thú vị, nếu trong bài toán M97 thay vì điều kiện $a < a_1$ chúng ta yêu cầu $a > a_1$, thì

$$|A_{n+1}B_{n+1}| = -\frac{1}{2}\,a_n + \frac{1}{2}\,a,$$

đó là

$$|A_{n+1}B_{n+1}| = \left(-\frac{1}{2}\right)^n\left(a_1 - \frac{a}{3}\right) + \frac{a}{3},$$

Và

$$b = \lim_{n \to \infty} A_{n+1}B_{n+1} = \frac{a}{3}\Bigg).$$

Việc làm quen với cấp số cộng-hình học đôi khi giúp ích cho lời giải một số bài toán hình học. Ví dụ, hãy xem xét vấn đề sau:

*Các đường cao của tam giác nhọn $A_1B_1C_1$ được kéo dài cho đến khi chúng giao với đường tròn ngoại tiếp tại các điểm $A_2$, $B_2$, $C_2$, tương ứng, đóng vai trò là các đỉnh của tam giác nhọn $A_2B_2C_2$. Độ cao của tam giác $A_2B_2C_2$ được mở rộng đến giao điểm với đường tròn ngoại tiếp tại các điểm $A_3$, $B_3$, $C_3$, tương ứng, đóng vai trò là các đỉnh của tam giác nhọn $A_3B_3C_3$, v.v. - bao gồm cả tam giác $A_{n+1}B_{n+1}C_{n+1}$. Tìm các góc của tam giác $A_{n+1}B_{n+1}C_{n+1}$, giả sử các góc của tam giác $A_1B_1C_1$ đều đã biết.*

Giải pháp. Hình 2 cho thấy một hình tròn và các hình tam giác nhọn $A_nB_nC_n$ và $A_{n+1}B_{n+1}C_{n+1}$ nội tiếp trong đó. Hãy biểu thị góc $A_{n+1}$ thông qua góc $A_n$:

$$\angle A_{n+1} = \angle B_{n+1}A_{n+1}C_{n+1} =$$
$$= \angle B_{n+1}A_{n+1}A_n + \angle A_nA_{n+1}C_{n+1} =$$
$$= \angle B_{n+1}B_nA_n + \angle A_nC_nC_{n+1} =$$
$$= \left(\frac{\pi}{2} - \angle A_n\right) +$$
$$+ \left(\frac{\pi}{2} - \angle A_n\right) = \pi - 2\angle A_n,$$

đó là

$$\angle A_{n+1} = -2\angle A_n + \pi$$

và dãy các góc $A_1$, $A_2$, $\ldots$, $A_{n+1}$ tạo thành một cấp số cộng-hình học. Sử dụng công thức (2) chúng tôi tìm thấy

$$\angle A_{n+1} = (-2)^n\cdot\left(\angle A_1 - \frac{\pi}{3}\right) + \frac{\pi}{3}.$$

⟦folio 38⟧
