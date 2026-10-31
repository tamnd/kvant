---
id: 1981-7-krotov-matematicheskiy-mayatnik-v-neinertsialnoy-sisteme-otscheta-2eb7ba99
issue: kvant_1981_7
year: 1981
number: "7"
title: Con lắc toán học trong hệ quy chiếu không quán tính
authors:
  - Кротов С. С.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 34
page_last: 35
page_labels: 32-33
tag: TIZ9
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 24d22a93009271d66c03a25803709950b2f63cbf21b9a467d46456c71f1cabdc
prompt_sha256: draft-1
translated_from: content/ru/1981/07/articles/09_krotov-matematicheskiy-mayatnik-v-neinertsialnoy-sisteme-otscheta-2eb7ba99.md
source_content_sha256: 3568fd55c17289ba1272bd3a0eb3bd92177ff5c05f08f4de4ee5bf8d8d4ab7f5
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 32⟧

Sẽ có ít hơn nhiều so với sự thay đổi $\Delta v$ của vận tốc dọc theo tiếp tuyến, nghĩa là
$$\Delta v_r \approx a_r \Delta t = \left( \frac{e v_{cp} B}{m} \right) \Delta t = \frac{e \cdot \Delta v \cdot B \cdot \Delta t}{2m} \ll \Delta v.$$
Do đó, ràng buộc cho $\Delta t$:
$$\Delta t \ll \frac{2m}{eB}.$$
Vì vậy, với $B = 10^{-4}$ T
$$\Lambda t \ll \frac{2 \cdot 9 \cdot 10^{-31}}{1,6 \cdot 10^{-19} \cdot 10^{-4}} \approx 10^{-7} \text{ с}.$$
Tại $r = 10^{-2}$ m
$$\Delta v = \frac{1,6 \cdot 10^{-19} \cdot 10^{-4} \cdot 10^{-2}}{2 \cdot 9 \cdot 10^{-31}} \approx 10^{5} \text{ м/c} \ll c.$$
A. Zilberman

Sách toán toán trong hệ báo cáo phi quán tính

Mô tả bài toán về chuyển động của ma trận toán học - một tải trọng nhỏ lên một quả bóng không trọng lượng là gì? Chúng ta phải biết vị trí ban đầu và tốc độ ban đầu của tải, có thể xác định vị trí của nó tại bất kỳ thời điểm tiếp theo nào. Nói cách khác, chúng ta phải xác định dạng rõ ràng của sự phụ thuộc $x = x(t)$ và $y = y(t)$, trong đó $x$ và $y$ là tọa độ xác định vị trí của trọng lượng trong mặt phẳng chuyển động của nó.

Chúng ta hãy xem xét phương trình mô tả chuyển động của một ma trận toán học có chiều dài $l$ khi điểm treo của nó đứng yên so với mặt đất. Chúng ta hãy chọn trục tọa độ $OX$ và $OY$ như được chỉ ra trong Hình 1. Giả sử tại một thời điểm nào đó trong quá trình chuyển động của ma trận, sợi dây tạo thành một góc thẳng đứng $\varphi$ (góc $\varphi$ không có trên trục $OY$ ngược chiều kim đồng hồ). Phương trình chuyển động của tải trọng - phương trình P của định luật Newton
$$m \vec{a} = m \vec{g} + \vec{T} \tag{1}$$
($\vec{T}$ là lực căng của ren) trong các hình chiếu trên các trục $OX$ và $OY$ có ​​dạng
$$m a_x = -T \sin \varphi, \tag{2}$$
$$m a_y = m g - T \cos \varphi. \tag{3}$$
Do ma trận độ dài nit không thay đổi trong quá trình di chuyển nên có sự tương ứng giữa tọa độ $x$ và $y$ (kết nối động học)
$$x^2 + y^2 = l^2,$$
và để mô tả chuyển động của ma trận, chỉ cần biết sự phụ thuộc thời gian của bất kỳ tọa độ nào là đủ.

Tọa độ tự nhiên hơn mô tả chuyển động của ma trận là góc $\varphi$.

Tìm sự phụ thuộc của $\varphi(t)$, từ đó ta xác định được sự phụ thuộc thời gian của tọa độ $x$ và $y$:
$$x(t) = l \sin (\varphi(t)),$$
$$y(t) = l \cos (\varphi(t)).$$
Chúng ta hãy viết lại phương trình (2) và (3), thay thế các giá trị vào chúng
$$a_x = v'_x = x'' = -l(\varphi')^2 \sin \varphi + l\varphi'' \cos \varphi,$$
$$a_y = v'_y = y'' = -l(\varphi')^2 \cos \varphi - l\varphi'' \sin \varphi$$
và nhân (2) với $\cos \varphi$ và (3) với $\sin \varphi$. chúng tôi nhận được
$$l\varphi'' \cos^2 \varphi - l(\varphi')^2 \sin \varphi \cos \varphi + \frac{T}{m} \sin \varphi \cos \varphi = 0, \tag{2}$$
$$-l\varphi'' \sin^2 \varphi - l(\varphi')^2 \sin \varphi \cos \varphi + \frac{T}{m} \sin \varphi \cos \varphi - g \sin \varphi = 0. \tag{3}$$
Trừ $(3')$ từ $(2')$, chúng ta thu được một phương trình vi phân thỏa mãn hàm $\varphi(t)$:
$$\varphi'' + \frac{g}{l} \sin \varphi = 0. \tag{4}$$
Trong trường hợp ma trận nit có độ lệch nhỏ so với sin dọc $\varphi \approx \varphi$ và phương trình (4) trở thành phương trình
$$\varphi'' + \frac{g}{l} \varphi = 0,$$
đó là phương trình dao động điều hòa có tần số $\omega = \sqrt{\frac{g}{l}}$. Tổng quát lời giải của phương trình như vậy có dạng
$$\varphi = \varphi_0 \cos \left( \sqrt{\frac{g}{l}} t + \Phi \right),$$
trong đó $\varphi_0$ là biên độ dao động, $\Phi$ là pha ban đầu. Các đại lượng $\varphi_0$ và $\alpha_0$ được xác định duy nhất theo các điều kiện ban đầu.

Bây giờ, điểm treo của ma trận chuyển động được tăng tốc $\vec{b}$ so với hệ thống báo cáo quán tính - đứng yên (Hình 2). Gia tốc $\vec{a}$ của trọng lượng (điểm $A$) so với hệ thống này có thể là

⟦folio 33⟧

nhưng biểu diễn nó dưới dạng tổng vectơ
$$\vec{a} = \vec{a}' + \vec{b},$$
trong đó $\vec{a}'$ là gia tốc của điểm $A$ so với khung báo cáo không quán tính, điểm này di chuyển với gia tốc $\vec{b}$ so với khung báo cáo không quán tính. Phương trình (1) bây giờ sẽ được viết như sau:
$$m\vec{a}' + m\vec{b} = m\vec{g} + \vec{T}.$$
Từ đây
$$m\vec{a}' = m\vec{g} + \vec{T} - m\vec{b} = m(\vec{g} - \vec{b}) + \vec{T}.$$
Phương trình (5) có hình thức khác với phương trình (1) bởi sự có mặt của vectơ không đổi $m(-\vec{b})$, có thứ nguyên của lực. Như vậy, nếu chúng ta muốn sử dụng định luật PN của Newton trong một hệ báo cáo phi quán tính chuyển động tương đối so với hệ quán tính có gia tốc không đổi $\vec{b}$, thì đối với các lực thực tác dụng lên trọng lượng - trọng lượng $m\vec{g}$ và lực căng của sợi dây $\vec{T}$, chúng ta phải thêm một vectơ không đổi $m(-\vec{b})$. Vector này được gọi là lực quán tính. Trong phương trình (5), chúng ta kết hợp vectơ $m(-\vec{b})$ với vectơ lực $m\vec{g}$. Trong ký hiệu này, (5) biểu thị phương trình PJ theo định luật Newton đối với một trọng lượng mà trên đó lực căng của sợi dây $T$ và lực $m(\vec{g} - \vec{b})$, đóng vai trò là lực trọng lượng, tác dụng. Sự ra đời của một “lực hấp dẫn” mới $m(\vec{g} - \vec{b})$ cho chúng ta một hướng mới của “phương ngang” - vuông góc với phương thẳng đứng mới.

Các phép biến đổi được đưa ra từ phương trình (1) sang phương trình (4) cũng được áp dụng cho phương trình (5). Bạn chỉ cần nhớ rằng vị trí cân bằng của ma trận trong hệ quy chiếu phi quán tính được cho bởi hướng của trục dọc mới; Góc lệch của ma trận so với vị trí cân bằng cũng được đo từ phương thẳng đứng này; tốc độ của ma trận (trọng lượng) là tốc độ của nó so với hệ thống báo cáo chuyển động với gia tốc $\vec{b}$.

Hình 1.

Hình 2

Khi sử dụng quan hệ năng lượng (định luật bảo toàn cơ năng) trong hệ thống báo cáo phi quán tính, chúng ta có thể sử dụng ký hiệu công thức
$$m\vec{g}'h' + \frac{m(v')^2}{2} = \text{const},$$
trong đó $g' = |\vec{g} - \vec{b}|$, $h'$ là chiều cao, sự vắng mặt của con lắc dọc theo phương thẳng đứng mới, $v'$ là tốc độ của vật so với hệ quy chiếu phi quán tính. Các mặt phẳng vuông góc với vectơ $\vec{g} - \vec{b}$ bây giờ trở thành các bề mặt tương đương.

Bây giờ chúng ta chuyển sang lời giải bài toán F663 từ Bài toán Kvant. Chúng ta hãy nhớ lại các điều kiện của nó.

F663. Một xe nặng chuyển động với vận tốc $v_0$ dọc theo mặt phẳng nằm ngang và lao lên mặt phẳng nghiêng tạo một góc a với phương ngang. Chuyển tiếp giữa các mặt phẳng bơi. Một quả bóng đang treo trên một sợi dây dài $l$. Biên độ của quả cầu dao động khi đưa xe lên mặt phẳng nghiêng là bao nhiêu?

Chúng ta phải xem xét rất nhiều chuyển động của ma trận so với hệ thống báo cáo phi quán tính - một chiếc xe đẩy chuyển động bằng
