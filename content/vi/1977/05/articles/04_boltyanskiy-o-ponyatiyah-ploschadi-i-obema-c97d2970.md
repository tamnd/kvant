---
id: 1977-5-boltyanskiy-o-ponyatiyah-ploschadi-i-obema-c97d2970
issue: kvant_1977_5
year: 1977
number: "5"
title: Về khái niệm diện tích và thể tích
authors:
  - Болтянский В. Г.
rubric: osnovnye-stati
page_first: 4
page_last: 10
page_labels: 2, 4, 7, 8
tag: N9MW
lang: vi
source: kvant_digital
extraction: vision
content_sha256: b6bf07e70656c256311cf6577ee8b81e2308b6b7c3f25f023aa28ba727bcd8be
prompt_sha256: draft-1
translated_from: content/ru/1977/05/articles/04_boltyanskiy-o-ponyatiyah-ploschadi-i-obema-c97d2970.md
source_content_sha256: 1fdb16a56646a4eccf37df16d81a8b84f10a41794904005a6e5014341ee85990
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

Người ta thường nói diện tích $S(F)$ của hình $F$ là một con số cho biết hình này “được tạo thành” bằng bao nhiêu đơn vị diện tích (một đơn vị diện tích được coi là hình vuông có cạnh bằng một đơn vị chiều dài). Tuy nhiên, cách biểu diễn trực quan như vậy không thể đóng vai trò là một định nghĩa toán học chính xác về khái niệm diện tích. Chẳng hạn, vẫn chưa rõ làm thế nào một vòng tròn có bán kính nhất định được “tạo thành” từ các đơn vị diện tích.

Một trong những cách để làm rõ khái niệm diện tích dựa trên việc xem xét *bảng màu* - chia mặt phẳng thành các hình vuông tắc nghẽn. Đặt cạnh của một hình vuông trong bảng màu có chiều dài 1. Trong Hình 1, hình $F$ chứa một hình gồm 9 ô vuông trong bảng màu và được chứa trong một hình gồm 29 ô vuông; do đó $9 \leq S(F) \leq 29$. Để ước tính chính xác hơn, bạn có thể sử dụng bảng màu có các ô vuông có cạnh dài 1/10 (sao cho mỗi ô vuông chứa 100 ô vuông của một bảng màu mới). Giả sử, nếu $F$ chứa một hình gồm 1716 ô vuông của bảng màu mới và được chứa trong một hình gồm 1925 ô vuông như vậy, thì $17,16 \leq S(F) \leq 19,25$. Bằng cách giảm bảng màu một lần nữa (tức là giảm độ dài cạnh của hình vuông xuống 10 lần), chúng ta sẽ có thể ước tính $S(F)$, v.v., chính xác hơn nữa.

Quá trình đo được mô tả không chỉ được sử dụng để tính diện tích mà còn dùng để *định nghĩa* khái niệm diện tích. Cụ thể, hãy xem xét một bảng màu có độ dài các cạnh của hình vuông bằng $1/10^k$. Đặt $F$ chứa một hình bao gồm $a_k$ hình vuông của bảng màu này và được chứa trong hình bao gồm $b_k$ các hình vuông như vậy (ví dụ: ở trên chúng ta có $a_1 = 1716$, $b_1 = 1925$). Khi đó chúng ta có thể nói rằng $\frac{a_k}{10^{2k}}$ là giá trị của diện tích của hình $F$ khi thiếu và $\frac{b_k}{10^{2k}}$ khi thừa.

Tăng $k$ không giới hạn, ta có thể xét giá trị trước đó

$$S(F) = \lim_{k \to \infty} \frac{a_k}{10^{2k}}, \quad S(F) = \lim_{k \to \infty} \frac{b_k}{10^{2k}},$$

⟦folio 4⟧

điểm nội bộ thì $S(F_1 \cup F_2) = S(F_1) + S(F_2)$;
(hàm $\gamma$ $S$ là bất biến đối với chuyển vị, tức là nếu $F_1 \cong F_2$ thì $S(F_1) = S(F_2)$;
($\delta$ một hình vuông có diện tích bằng 1.

Sau khi xem xét những tính chất này, một bước ngoặt xuất hiện trong lý thuyết diện tích. Vấn đề là định lý tồn tại và duy nhất sau đây là hợp lệ: trên lớp của tất cả các hình tứ giác đều tồn tại và chỉ có một, hàm $S$, có thuộc tính $(\alpha), (\beta), (\gamma), (\delta)$. Định lý này đóng một vai trò quan trọng. Định nghĩa về diện tích ở trên (sử dụng bảng màu) có thể được gọi là mang tính xây dựng, vì diện tích được xác định bằng cách sử dụng cấu trúc được mô tả (quy trình đo lường). Bây giờ chúng ta có thể đưa ra một mô tả khác về khái niệm diện tích; Nói một cách đại khái, diện tích là “cái có tính chất $(\alpha), (\beta), (\gamma), (\delta)$”. Thật ra, theo định lý về sự tồn tại và duy nhất, ngoài diện tích ra không có hàm số nào khác có tính chất vừa nêu. Chính xác hơn, bây giờ chúng ta có thể nói rằng diện tích là một hàm số được xác định trên tập hợp tất cả các hình tứ phương và thỏa mãn điều kiện $(\alpha), (\beta), (\gamma), (\delta)$. Với cách tiếp cận này, các thuộc tính $(\alpha), (\beta), (\gamma), (\delta)$ không cần phải được chứng minh (chúng được coi là tiên đề diện tích) và bản thân định nghĩa trở thành tiên đề chứ không mang tính xây dựng như trước đây.

Với định nghĩa tiên đề về diện tích, các bảng màu trở nên không thể tránh khỏi $^*$) và tất cả các thuộc tính khác của diện tích đều được rút ra từ các tiên đề $(\alpha), (\beta), (\gamma), (\delta)$ dưới dạng định lý. Ví dụ, từ các tiên đề có thể suy ra rằng với $F \supset G$ thì bất đẳng thức $S(F) \geq S(G)$ là đúng (tính chất đơn điệu của diện tích); rằng đối với mọi hình tứ giác $F_1, F_2$ thì sự tương ứng $S(F_1 \cup F_2) = S(F_1) + S(F_2) - S(F_1 \cap F_2)$ là hợp lệ; tỉ số diện tích của các hình tương tự bằng bình phương của hệ số tương tự, v.v.

Cuối cùng chúng ta hãy chuyển sang câu hỏi về tính diện tích. Phương pháp đơn giản nhất để tính diện tích, được biết đến từ thời cổ đại, là phương pháp phân rã. Để hiểu phương pháp này, hãy xem xét các hình $F$ và $H$ được hiển thị trong Hình 3. Các đường chấm chấm chia các hình này thành các phần bằng nhau tương ứng, tức là các hình $F$ và $H$ có bố cục bằng nhau. Nói chung, hai hình được gọi là tương đương nếu cắt một trong chúng thành hữu hạn

**Cơm. 3.**

số phần, có thể (bằng cách sắp xếp các phần này theo cách khác nhau, nghĩa là bằng cách xem xét các số bằng nhau với các phần này) để tạo ra hình thứ hai từ chúng.

Từ các tiên đề $(\beta)$ và $(\gamma)$ suy ra hai hình đều có kích thước bằng nhau, tức là chúng có cùng diện tích. Phương pháp phân rã dựa trên điều này: hình, diện tích cần tính, được chia thành một số hữu hạn các phần để từ các phần này có thể tạo ra một hình đơn giản hơn (diện tích đã biết). Ví dụ, hình bình hành tương đương với một góc vuông, có cùng đáy và cùng chiều cao (Hình 4), và do đó, khi biết công thức tính diện tích góc vuông, chúng ta thiết lập công thức tính diện tích hình bình hành. Hình tam giác tương đương với một hình bình hành, có cùng đáy và một nửa chiều cao (Hình 5), và điều này cho phép chúng ta tính diện tích của hình tam giác.

Bạn có thể dễ dàng tính diện tích hình tam giác, dễ dàng tính diện tích

⟦folio 7⟧

và với mọi $\Delta x$ âm trừ khi $-\delta < \Delta x < 0$. Do đó, với bất kỳ $\varepsilon > 0$ nào cũng có một $\delta > 0$ sao cho bất đẳng thức $0 < |\Delta x| < \delta$ (*) đúng. Theo định nghĩa về giới hạn, điều này có nghĩa là

$$\lim_{\Delta x \to 0} \frac{\Delta S(x)}{\Delta x} = f(x),$$

tức là

$$S'(x) = f(x).$$

Đẳng thức đã được chứng minh cho phép chúng ta tính diện tích của hàm $F$. Giả sử $\varphi$ là nguyên hàm nào đó của hàm $f$. Vì $S$ cũng là nguyên hàm của hàm này, nên $\varphi$ và $S$ khác nhau một hằng số, tức là có một số $c$ sao cho $\varphi(x) = S(x) + c$ với bất kỳ $x \in [a, b]$ nào.

Kể từ đây,

$$\varphi(b) - \varphi(a) = (S(b) + c) - (S(a) + c) = S(b) - S(a) = S(F)$$

(vì $S(a) = 0$ và $S(b)$ là diện tích của toàn bộ hàm $F$). Vì vậy, nếu $\varphi$ là một nguyên hàm nào đó của hàm $f$, thì hiệu $\varphi(b) - \varphi(a)$ bằng diện tích của hàm $F$, tức là $S(F) = \int_a^b f(x) dx$.

Ví dụ: nếu $F$ là một “tam giác cong” được giới hạn bởi parabol $y = x^2$ và các đường thẳng $y = 0$, $x = b$ (Hình 11), thì đường thẳng đi qua điểm $x$ của đoạn $[0, b]$ và song song với trục tọa độ cắt ra khỏi “tam giác” $F$ này là một đoạn có độ dài $x^2$, tức là trong trường hợp này là $f(x) = x^2$. Đối với hàm $f(x) = x^2$ một trong các nguyên hàm là hàm $\varphi(x) = \frac{1}{3} x^3$. Do đó, diện tích của hàm $F$ được tìm theo công thức

$$S(F) = \varphi(b) - \varphi(0) = \frac{1}{3} b^3.$$

Lưu ý rằng bằng cách trừ diện tích của “tam giác” $F$ khỏi diện tích của hình chữ nhật $ABCD$ (Hình 12), chúng ta thu được diện tích của đoạn parabol, do đó hóa ra bằng $\frac{4}{3} b^3$. Như bạn có thể thấy, với sự trợ giúp của nguyên hàm, chúng ta chỉ cần thu được kết quả mà Archimedes rút ra bằng cách sử dụng một phép tính phức tạp dựa trên việc sử dụng phương pháp rút gọn *). Học sinh ngày nay biết nhiều hơn những gì Archimedes vĩ đại đã biết!

Kết thúc câu chuyện về khái niệm diện tích, chúng ta hãy xem xét cái gọi là giá trị Cavalieri**). Cho phép

*) Để biết thêm chi tiết về vấn đề này, xem bài viết của A.D. Bendukidze “Archimedes và phương trình cầu phương của parabol” (Kvant), 1971, số 7, tr. 7).

**) Nguyên tắc Cavalieri đối với diện tích đã được đề cập trên các trang «Kvant» - trong bài viết của S. Verov “Bí mật của Cyclops” («Kvant», 1975, Số 8, trang 21) và trong bài báo của S. Pukhov “Bài toán về vật thể lồi” («Kvant», 1977, Số 2, tr. 30).

⟦folio 8⟧

Ngoài $F$, còn có một hình khác $H$ (Hình 13), hình chiếu của nó, dựa trên sự hợp nhất, là cùng một đoạn $[a, b]$. Ngoài ra, giả sử rằng mỗi đường thẳng song song với trục tọa độ cắt các hình $F$ và $H$ dọc theo các đoạn bằng nhau. Khi đó diện tích của hình $H$ được biểu thị bằng tích phân giống như diện tích của hình $F$, tức là $S(H) = \int_{a}^{b} f(x) dx$, và do đó $S(F) = S(H)$. Vì vậy, nếu bất kỳ đường thẳng nào song song với một đường thẳng cố định cho trước (ví dụ: trục tọa độ) cắt các hình $F$ và $H$ dọc theo các đoạn thẳng bằng nhau thì các hình $F$ và $H$ có ​​kích thước bằng nhau: $S(F) = S(H)$. Đây là những nguyên tắc Cavalieri (đối với hình vuông). Chúng tôi rút ra nó bằng cách sử dụng công thức biểu thị diện tích của một hình thông qua tích phân. Cavalieri đã bày tỏ nguyên lý của mình (và áp dụng nó để tính diện tích và thể tích) ngay cả trước đó, trong các công trình của Newton, Leibniz và các nhà khoa học khác.

Cơm. 13.

Cơm. 14.

các khái niệm về thứ nhất và tích phân đã được giới thiệu.

Hình 14 cho thấy hai hình, do nguyên lý Cavalieri, có kích thước bằng nhau. Tuy nhiên, sự bằng nhau về diện tích của các hình này có thể dễ dàng được thiết lập bằng phương pháp phân vùng (làm thế nào?).

Khái niệm thể tích được đưa ra tương tự như khái niệm diện tích. Trong quá trình định nghĩa mang tính xây dựng, các hình khối (tương tự như pallet) sẽ được xem xét, tức là phân chia không gian thành các hình khối đồng dạng. Hãy xem xét một hình khối trong đó chiều dài các cạnh của hình lập phương bằng $1/10^k$. Đặt hình không gian $F$ chứa một hình gồm $a_h$ hình khối của khối này và được chứa trong hình gồm $b_h$ các hình khối như vậy. Khi đó $\frac{a_h}{10^{3k}}$ là giá trị thể tích của hình $F$ khi thiếu và $\frac{b_h}{10^{3k}}$ khi thừa. Nếu hình $F$ sao cho là giới hạn

$$V(F) = \lim_{k \to \infty} \frac{a_k}{10^{3k}}, \quad V(F) = \lim_{k \to \infty} \frac{b_k}{10^{3k}}$$

trùng nhau thì hình $F$ gọi là lập phương, số $V(F) = \overline{V}(F)$ gọi là thể tích của hình $F$ và ký hiệu là $V(F)$. Âm lượng $V$ là một hàm được xác định trên lớp của tất cả các hình lập phương và nhận các giá trị số.

Giống như diện tích, thể tích có thể được định nghĩa theo tiên đề và các tiên đề làm cơ sở cho khái niệm thể tích hoàn toàn giống với các tiên đề về diện tích:

(α) hàm $V$ không âm, tức là $V(F) \geq 0$ đối với mọi hình lập phương $F$;

(β) hàm $V$ là hàm cộng, tức là nếu $F_1$ và $F_2$ là các hình lập phương không có điểm chung bên trong thì

$$V(F_1 \cup F_2) = V(F_1) + V(F_2);$$

(γ) hàm $V$ là bất biến dưới các chuyển vị, tức là nếu $F_1 \cong F_2$ thì $V(F_1) = V(F_2);$

(δ).ed khối lập phương đơn vị (tức là khối lập phương có cạnh có chiều dài bằng 1) có thể tích là 1.
