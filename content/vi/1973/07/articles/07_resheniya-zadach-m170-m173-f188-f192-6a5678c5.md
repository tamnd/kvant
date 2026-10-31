---
id: 1973-7-resheniya-zadach-m170-m173-f188-f192-6a5678c5
issue: kvant_1973_7
year: 1973
number: "7"
title: Lời giải bài toán M170—M173; F188—F192
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 28
page_last: 30
page_labels: 26-28
tag: PT4C
lang: vi
source: kvant_digital
extraction: vision
content_sha256: cfe791ce66e7eeff94a44fb535e4c3edd40d07a4ca75d8cdc8384510da2a440a
prompt_sha256: draft-1
translated_from: content/ru/1973/07/articles/07_resheniya-zadach-m170-m173-f188-f192-6a5678c5.md
source_content_sha256: 8f074fe59e394b1271d75a1ba0d97a0c3be5e8c75d0b034c3985d4811ab08699
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 26⟧

Lời giải bài toán

M170—M173; F188—F192

M170. a) Gọi $M$ và $N$ là điểm tiếp tuyến của đường tròn nội tiếp tam giác ABC trên các cạnh AB và AC, P là giao điểm của đường thẳng MN với phân giác của góc B. Chứng minh rằng góc BPC vuông.

b). Chứng minh một thực tế tổng quát hơn: nếu điểm O nằm bên trong tam giác, cho cực đại $BOC - BAO = 90^\circ$, M và N là đáy của các đường vuông góc hạ từ điểm O đến các cạnh AB và AC, P là giao điểm của các đường thẳng BO và MN thì $BPC = 90^\circ$ (Hình 1).

Vấn đề a), thực ra, là trường hợp đặc biệt 6): nếu O là tâm của đường tròn nội tiếp thì BOC trong tổng các góc OCB và OBC bằng 180°, và BAO trong tổng có các góc bằng nhau bằng một nửa tổng các góc của tam giác, tức là 90°.

Chúng ta sẽ giải quyết tư thế ngay bài toán 6). Để xác định điểm, hãy đặt P nằm trên phần tiếp theo của đoạn MN ngoài điểm N, như trong hình của chúng ta. (Các trường hợp khác được chia theo cách tương tự; bạn có thể dễ dàng tự mình xử lý.) Theo điều kiện $OMA = ONA = 90^\circ$, do đó, vectơ của tứ giác OMNA có thể mô tả bằng một đường tròn, do đó,

$$OMM = OAM = BAO.$$

Bây giờ chúng ta hãy chứng minh rằng các điểm O, N, P và C nằm trên cùng một đường tròn. Thật vậy, $CNP = MNA = 90^\circ - MNO = 90^\circ - BAO = 180^\circ - BAO$.

Sử dụng điều kiện bài toán: $BOC - BAO = 90^\circ$, ta thu được $CNP = CPO$.

Cuối cùng, vì tứ giác CONP là tuần hoàn nên đẳng thức $CPO = CNO = 90^\circ$ mà chúng ta cần tuân theo.

I. F. Sharytsin

M171. Một tấm ván sáu chiều thông thường được vẽ trên mặt phẳng, chiều dài cạnh của nó bằng 1. Dùng thước kẻ dựng một đoạn có chiều dài $\sqrt{7}$.

Bạn có thể dễ dàng chứng minh rằng độ dài của các đoạn màu đỏ trong Hình 2 bằng $\sqrt{7}$.

Hình 2.

M172. Chứng minh rằng với mọi số nguyên tố p thì số $\underline{11\dots1}$ $\underline{22\dots2}$ $\underline{33\dots3}$ $\dots$ $\underline{99\dots9}$ $= \underline{10\dots02}$ $\underline{0\dots03}$ $\dots$ $\underline{0\dots08}$ $\underline{0\dots09}$ $= 10^8p + 2 \cdot 10^7p + 3 \cdot 10^6p + \dots + 8 \cdot 10^p + 9 = C$, $\underline{11\dots1} = E$.

Rõ ràng là $B = E \cdot C$, $C - A = (10^8p - 10^8) + 2 (10^7p - 10^7) + 3 (10^6p - 10^6) + \dots + 8 (10^p - 10)$, $10^p - 10 = (9 \cdot E + 1) - 10 = 9 (E - 1)$.

Theo định lý nhỏ Fermat (xem «Kvant» Số 10 (1972)), số $n^p$ - n chia hết cho $p$ với mọi số nguyên tố $p$ và mọi tự nhiên

⟦folio 27⟧

Cụ thể, $10^p - 10, 10^2p - 10^2, \dots, 10^8p - 10^8$ chia hết cho $p$. Vậy $C - A$ chia hết cho $p$ và $9(E - 1)$ chia hết cho $p$.

Vì tổng các chữ số của số $A$ là 45 nên $A$ chia hết cho 9 và do đó $A(E - 1)$ chia hết cho 9 $(E - 1)$. Do đó, $A(E - 1)$ chia hết cho $p$.

Do đó, $B - A = EC - AE + AE - A = E(C - A) + A(E - 1)$ chia hết cho $p$, đây là điều cần chứng minh.

M. L. Gerver

M173. Trong bảng vuông $4 \times 4$ khoảng cách các số lớn nhất là 1, 2, 3, ..., 16, sao cho tổng các số ở tất cả các hàng trong mỗi hàng, trong mỗi cột và trên mỗi đường chéo đều bằng cùng một số, với 1 và 16 đứng ở các góc đối diện của bảng. Chúng ta hãy chứng minh rằng trong phương trình bậc hai này, tổng của hai số bất kỳ nằm đối xứng qua tâm bằng 17. Đối với các số 1 và 16, điều này đúng theo điều kiện. Giả sử rằng 1 ở góc trên bên trái và 16 ở góc dưới bên phải, thì hai số còn lại trên cùng một đường chéo - hãy biểu thị chúng bằng $a$ và $a'$ - thỏa mãn đẳng thức $a + a' = 17$. Chúng ta hãy luôn đồng ý biểu thị số bổ sung $x$ lên đến 17 bằng $x' : x' = 17 - x$.

Bây giờ chúng ta hãy sử dụng ký hiệu được đưa ra trong Hình 3 ($S_i$ biểu thị tổng các số trong các ô tương ứng).

Các đẳng thức sau đây đúng:
$$S_1 + c + d + a + a' + S_2 + S_3 + c + d + a + a' + S_4 + 2(b + c + d + e) = 34 \cdot 6$$

Hình 3.

Hình 4.

Hình 5.

⟦folio 28⟧

Hình 6.

F188. Một chiếc tủ lạnh có dung tích $P$ trong thời gian $t$ đã biến $n$ lít nước thành đá, ban đầu có nhiệt độ $t^\circ$ C. Trong thời gian này, bao nhiêu nước đã thoát ra khỏi phòng?

Từ nguyên lý hoạt động của bất kỳ thiết bị làm lạnh nào, tất cả năng lượng mà tủ lạnh tiêu thụ từ mạng và năng lượng được tách ra khỏi các sản phẩm được làm mát (trong trường hợp này là nước) đều được chuyển thành nhiệt. Điều này có nghĩa là lượng nhiệt tỏa ra trong phòng trong thời gian $t$, $Q = P\tau + c_B m_B t^\circ + \lambda m_B$,

trong đó $m_B = n$ là khối lượng nước tính bằng kcal, $c_B$ là nhiệt dung riêng của nước và $\lambda$ là nhiệt dung riêng của sự tan chảy của băng.

Tôi. Sh. Slobodetsky

F189. Điện tích $q = 10^{-8}$ to được phân bố đều trên tâm của một hình tròn có bán kính $R = 1$ cm với góc khoảng cách bằng nước và $\lambda = 2/3$ π radian. Xác định cường độ điện trường tại tâm đường tròn.

a) Thể tích của cung được chia thành $n$ phần bằng nhau, mỗi phần có điện tích $q/n$. Khi đạt đến mức $n$ ($\pi R/n \ll R$) lớn, những khoản phí này có thể được coi là chính xác. Mỗi điện tích tạo ra một trường ở tâm vòng tròn có cường độ $\Delta E_i$ có độ lớn bằng nhau

$$\Delta E_i = k \frac{q}{nR^2},$$

ở đâu $k = \frac{1}{4\pi\epsilon_0} = 9.10^9 \text{ nm}^2/\text{k}^2$. Hướng của vectơ $\Delta E_i$ được thể hiện trong Hình 6,a.

Để tìm tổng cường độ trường $E = \sum_{i=1}^{n} \Delta E_i$, chúng ta sẽ chỉ cộng các vectơ này, đặt phần đầu của mỗi vectơ ở cuối vectơ trước đó (Hình 6.6). Giá trị $E$ càng lớn thì độ chính xác của việc xác định $n$ càng cao.

Dễ dàng nhận thấy rằng khi $n$ đạt đến một đường gãy lớn, được hình thành bằng cách cộng các vectơ $\Delta E_i$, người ta có thể nhận thấy một hình bán nguyệt và độ lớn của vectơ $E$ về mặt số học bằng đường kính của nó. Đối với hình bán nguyệt $l$ bằng

$$l = n \Delta E_i = n \frac{kq}{nR^2} = \frac{kq}{R^2}.$$

Mặt khác, $l = \pi E/2$.

Từ đây

$$E = \frac{2l}{\pi} = \frac{2kq}{\pi R^2} = 5.7 \cdot 10^5 \text{ σ/m}.$$

6) Bài toán đối với cung có góc mở tùy ý $\varphi$ cũng được giải tương tự. Trong trường hợp này, vectơ $E$ là dây cung của cung tròn (Hình 7.6). Độ dài của cung là $l = n \Delta E_i$, góc ở tâm là $\varphi$ (pad) ($\varphi$ là góc lớn nhất giữa các vectơ $\Delta E_i$).

Chúng ta hãy biểu thị bán kính của hình tròn $r$ và biểu thị qua nó độ dài của cung $l$ và dây cung $E$:

$$l = r \varphi, \quad E = 2r \sin \frac{\varphi}{2}.$$

Nhưng $l = n \Delta E_i = kq/R^2$ do đó

$$E = 2 \frac{kq}{\varphi R^2} \sin \frac{\varphi}{2}.$$

Với $\varphi = 2/3$ π chúng ta nhận được

$$E = 7.4 \cdot 10^5 \text{ σ/m}.$$

V. G. Svetmozarov

F190. Tải trọng được buộc trên một sợi dây vào một thanh dầm vuông $c$ theo cạnh $a$ (Hình 8). Chiều dài dây $l = na$ ($n$ là số nguyên). Tải trọng được truyền với tốc độ $V$ theo hướng vuông góc với sợi dây. Sau bao lâu thì toàn bộ sợi dây quấn quanh dầm?

Chúng ta hãy xem xét trường hợp tại thời điểm ban đầu sợi dây song song với một trong các mặt bên của dầm ($\alpha = 0$). Tải bắt đầu di chuyển xung quanh mép $A$ dọc theo một vòng tròn bán kính $l$ với tốc độ tuyến tính $V$. Sau một phần tư vòng, sợi dây chạm vào mép dầm, tải trọng có cùng tốc độ tuyến tính dọc theo một vòng tròn bán kính $l - a$. Sau một phần tư lượt quay nữa, bán kính của hình tròn sẽ trở thành $l - 2a$, v.v.
