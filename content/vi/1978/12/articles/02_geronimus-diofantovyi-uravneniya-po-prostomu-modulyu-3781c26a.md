---
id: 1978-12-geronimus-diofantovyi-uravneniya-po-prostomu-modulyu-3781c26a
issue: kvant_1978_12
year: 1978
number: "12"
title: Phương trình Diophantine modulo số nguyên tố
authors:
  - Геронимус А. Ю.
rubric: osnovnye-stati
page_first: 4
page_last: 8
page_labels: 2-6
tag: 09MK
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 3d00ffdb1e44ec08dd79373663176da070d2011a531ae76a8e815a15f21c8f19
prompt_sha256: draft-1
translated_from: content/ru/1978/12/articles/02_geronimus-diofantovyi-uravneniya-po-prostomu-modulyu-3781c26a.md
source_content_sha256: 88815c5942334e607fc5dac5177e7b32f50ad9cf977879d41eb0f8655c934cd2
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

Phương trình Diophantine modulo số nguyên tố

“Thưa ngài Dionysius đáng kính, biết rằng chúng tôi rất muốn học lời giải bài toán liên quan đến các con số, tôi đã cố gắng giải thích bản chất và sức mạnh của chúng, của chúng tôi, từ nền tảng mà khoa học này dựa trên.

Có lẽ chủ đề này có vẻ khó đối với tôi vì chúng ta vẫn chưa quen với nó và những người mới bắt đầu không có xu hướng mong đợi thành công. Nhưng trước hết, có thể nhờ sự siêng năng của bạn và những sai lầm của tôi, hoặc niềm đam mê khoa học nồng nàn sẽ giúp bạn học hỏi nhanh chóng”.

Với sự cống hiến này, Số học của Diophantus của Alexandria sẽ mở ra.

Trong cuốn sách này, Diophantus (có lẽ ông sống ở thế kỷ thứ 3) đã tóm tắt và mở rộng kinh nghiệm tích lũy trước ông lời giải về các phương trình đại số không xác định (tức là có nhiều biến) trong số nguyên hoặc số hữu tỷ. Kể từ đó, những phương trình này được gọi là phương trình Diophantine.

Dưới đây là ví dụ về các phương trình như vậy:
$$x^2 + y^2 = z^2, \quad x^2 = y^3 + 5y + 7.$$

Sự quan tâm đến phương trình Diophantine rõ ràng có liên quan đến bản chất của con người - các tài liệu được bảo tồn tiết lộ dấu vết của nó ở độ sâu hàng nghìn năm. Ngay cả ở Babylon cổ đại, họ cũng đang tìm kiếm các dự án Pythagore - số nguyên lời giải $x^2 + y^2 = z^2$.

“Số học” của Diophantus đã hình thành nền tảng của lý thuyết số hiện đại. Kể từ thời Fermat (thế kỷ 17), các phương trình Diophantine đã trở thành chủ đề nghiên cứu sâu sắc của các nhà toán học lỗi lạc nhất và là mối quan tâm không ngừng của tất cả những người yêu thích các con số, không kém gì Dionysius đáng kính.

Sức mạnh của bài toán, được nói đến trong sự cống hiến, đã và đang ngày càng lớn mạnh. Lý thuyết về phương trình Diophantine có mối liên hệ với hầu hết các lĩnh vực của toán học hiện đại.

Diophantus chỉ nhầm ở một điều - chủ đề không trở nên dễ hiểu.

Có lẽ người cuối cùng chia sẻ niềm hy vọng này là nhà toán học nổi tiếng người Đức David Hilbert. Năm 1900, trong một báo cáo tại Cuộc thi Toán học Quốc tế lần thứ hai, ông đã đưa ra 23 bài toán từ các lĩnh vực toán học khác nhau. Bài toán thứ mười được xây dựng như sau: chỉ ra phương pháp có thể thực hiện được, sau một số hữu hạn các thao tác cài đặt, liệu một phương trình Diophantine đã cho có thể giải được dưới dạng số nguyên hay không.

Một thời gian dài nghiên cứu đã kết thúc vào năm 1969 với một giải pháp tiêu cực cho vấn đề này: hóa ra phương pháp chung được đề cập trong công thức của nó hoàn toàn không tồn tại *).

Liên quan đến các phương trình Diophantine, các phương trình bài toán đơn giản hơn cũng được đặt ra. Với lời giải những lý thuyết rất hay của họ đã nảy sinh. Chúng tôi đã thảo luận về sự khởi đầu của một trong số đó - lý thuyết về phương trình Diophantine modulo nguyên tố - ở đất nước này. Để làm rõ câu chuyện này, chúng tôi khuyên bạn nên đọc lại các bài “So sánh và phân loại dư lượng” (số 10) và “So sánh theo modulo đơn giản” (số 11).

Chuyển sang phương trình modulo nguyên tố

Hãy xem xét một số phương trình Diophantine. Chúng ta hãy giả sử rằng nó có lời giải và cùng nhau xem xét

*) Để biết thêm thông tin về điều này, xem «Kvant», 1970, Số 7.

⟦folio 3⟧

được bao gồm trong số lời giải các lớp dư lượng của chúng mod p. Dễ dàng thấy rằng tập kết quả sẽ là nghiệm của phương trình đã cho - phương trình thu được từ phương trình đã cho bằng cách thay thế từng hệ số bằng lớp thặng dư mod p của nó. Vì vậy, cần coi nghiệm của phương trình Diophantine là sự tồn tại của lời giải của phương trình rút gọn mod p với mọi p*).

Trong phần này, chúng tôi sẽ đưa ra hai ví dụ về quá trình chuyển đổi sang mod p, và trong phần tiếp theo chúng tôi sẽ nghiên cứu phương trình Diophantine động mod p (nghĩa là các phương trình có hệ số trong tập F_p). Lý thuyết của họ đơn giản hơn nhiều so với lý thuyết về phương trình Diophantine thông thường. Tập F_p là hữu hạn và có thể xác định xem một phương trình Diophantine đã cho có lời giải hay không bằng cách liệt kê đơn giản. Do đó, không có gì đáng ngạc nhiên khi tập F_p có những định lý tổng quát đảm bảo sự tồn tại của lời giải. Chúng ta xây dựng và thảo luận về các định lý này trong các phần sau.

Phương trình số nguyên lời giải là gì

$$35x^4 + 24y^3 = 100\ 000?$$

(1)

Hãy trình bày phương trình này mod 3. 35 ≡ 2 (mod 3), 24 ≡ 0 (mod 3), 100\000 ≡ 1 (mod 3); do đó, mod 3, phương trình (1) có dạng

$$\bar{2}x^4 = \bar{1}.$$

(2)

$$\bar{2}x^4$$ với x ∈ F_3 nhận giá trị 0 và 2 (kiểm tra) nên phương trình (2) không có lời giải, nghĩa là phương trình (1) cũng không có lời giải.

Hãy xem ví dụ cuối cùng:

$$5x^3 + 11y^3 + 13z^3 = 0.$$

(3)

Phương trình này có một lời giải hiển nhiên: x = y = z = 0. Hãy thử chứng minh rằng nó không có lời giải nào khác.

Điều tự nhiên là xét phương trình (3) modulo 5, 11 hoặc 13 - khi đó một trong ba số hạng sẽ chuyển về 0. Chúng ta nên chọn modulo nào?

*) Các phép tính “modulo” cũng được thảo luận trong bài viết của M. I. Bashmkov («Kvant», 1971, số 3).

lời giải bài toán 4 bài “So sánh theo modulo đơn giản” sẽ giúp chúng ta giải đáp câu hỏi này. Từ đó suy ra rằng trong các tập F_5 và F_{11} tất cả các phần tử đều là hình lập phương và trong tập F_{13} chỉ có 5 phần tử là hình lập phương.

Sau khi rút gọn phương trình (3) modulo 5, nó có dạng

$$y^3 + \bar{3}z^3 = \bar{0}.$$

(4)

Vì mọi phần tử của tập hợp F_5 đều là lập phương và có thể chia được trong F_5, nên với mọi a và b chúng sẽ tìm được y và z sao cho y^3 = a và 3z^3 = b. Do đó, trong tập F_5, phương trình (4) có nhiều giá trị khác 0 lời giải (tương ứng với các cặp a, b mà a + b = 0). Kết quả tương tự cũng đúng với F_{11}. Vì vậy, chúng ta chưa tìm được, xét phương trình (3) modulo 5 hoặc 11, chứng minh được nó chỉ có 0 lời giải.

Xét phương trình (3) mod 13:

$$\bar{5}x^3 + \bar{11}y^3 = \bar{0}.$$

(5)

Trong tập F_{13} chỉ có các phần tử 0, 1, 5, 8, 12 là lập phương. Hãy lập một bảng gồm các giá trị có thể có của biểu thức $\bar{5}a + \bar{11}b$, trong đó a, b ∈ {0, 1, 5, 8, 12} (giao điểm chứa tổng $\bar{5}a + \bar{11}b$). Bảng cho thấy nghiệm duy nhất của phương trình (5) là x = y = 0.

Điều này có nghĩa là với mọi lời giải x_0, y_0, z_0, phương trình (3) x_0 và y_0 đều chia cho 13: x_0 = 13x_1, y_0 = 13y_1. Thay thế các biểu thức này cho x_0 và y_0 vào (3),

⟦folio 4⟧

chúng ta nhận được $5 \cdot 13^3 x_1^3 + 11 \cdot 13^3 y_1^3 + 13 z_0^3 = 0$, từ đó $z_0$ chia cho 13: $z_0 = 13 z_1$. Thay thế và giảm đi 13: $5 x_1^3 + 11 y_1^3 + 13 z_1^3 = 0$. Theo đó, $x_1 = 13 x_2$, $y_1 = 13 y_2$, $z_1 = 13 z_2$, v.v. Do đó, $x_0, y_0, z_0$ có thể chia hết cho bất kỳ lũy thừa nào của 13, điều này chỉ có thể chia hết nếu $x_0 = y_0 = z_0 = 0$.

**Định lý Chevalley và Varnin**

Biết tập hợp $F_{13}$ cho phép chúng ta biết nên chọn mô hình so sánh nào để nghiên cứu phương trình (3).

Điều gì xảy ra nếu phương trình không có ba biến mà có bốn hoặc năm biến? Điều gì xảy ra nếu bậc của phương trình không phải là 3 mà là 4, 5 hoặc 6? Người ta cảm thấy rằng nếu số lượng biến x được thông báo, thì cơ hội chứng minh lời giải của phương trình ban đầu là không thể, khi xem xét nó theo một mô hình nào đó; nếu mức độ của nó được thông báo, chúng sẽ phát triển. Thông điệp trực quan này có thể được cải tiến hơn nữa.

Định lý Chevalley đáng chú ý sau đây là đúng: xét tập $R(x_1, x_2, \dots, x_n)$ với các hệ số trong tập $F_p$; đặt $x_1 = x_2 = \dots = x_n = 0$ - lời giải phương trình $R(x_1, x_2, \dots, x_n) = 0$; nếu bậc của tập hợp $R(x_1, x_2, \dots, x_n)$ nhỏ hơn n thì phương trình $R(x_1, x_2, \dots, x_n) = 0$ cũng khác 0 lời giải.

Định lý Chevalley ngay lập tức tiếp nối định lý Varnin: nếu bậc nhân $R(x_1, x_2, \dots, x_n) = 0$ bằng 0 hoặc $\ge p$. Nhưng trường hợp đầu tiên bị loại trừ vì phương trình bằng 0 lời giải. Điều này có nghĩa là anh ta vẫn còn ít nhất p - 1 lời giải.

Chứng minh định lý Varnin rất đơn giản và hay nên chúng ta sẽ trình bày ở đây, nhưng trước tiên hãy nói.

**Về một số lượng bằng 0**

Tổng $\bar{b}_1 + \bar{b}_2 + \dots + \bar{b}_p$ của tất cả các phần tử của tập hợp $F_p$ là bao nhiêu? Hãy nhân tất cả các số hạng với một phần tử nào đó $\bar{a}$ từ $F_p$, không bằng 0 và 1. Khi đó tổng sẽ được nhân với cùng một phần tử: $\bar{a} \bar{b}_1 + \bar{a} \bar{b}_2 + \dots + \bar{a} \bar{b}_p = \bar{a} (\bar{b}_1 + \bar{b}_2 + \dots + \bar{b}_p)$. Mặt khác, khi nhân tất cả các phần tử của tập hợp $F_p$ với một phần tử nào đó ($\neq 0$), chúng ta lại nhận được tất cả các phần tử từ $F_p$; do đó $\bar{b}_1 + \bar{b}_2 + \dots + \bar{b}_p = \bar{a} (\bar{b}_1 + \bar{b}_2 + \dots + \bar{b}_p)$. Vì vậy, $\bar{b}_1 + \bar{b}_2 + \dots + \bar{b}_p = 0$.

Tổng $\bar{b}_1^2 + \bar{b}_2^2 + \dots + \bar{b}_p^2$ bình phương của các phần tử của tập hợp $F_p$ là bao nhiêu? Hãy nhân tất cả các phần tử một lần nữa với một phần tử nào đó $\bar{a} (\neq 0, 1)$. Sau đó, số tiền, vì lý do tương tự như trước, vẫn giữ nguyên: $(\bar{a} \bar{b}_1)^2 + (\bar{a} \bar{b}_2)^2 + \dots + (\bar{a} \bar{b}_p)^2 = \bar{b}_1^2 + \bar{b}_2^2 + \dots + \bar{b}_p^2$; mặt khác $(\bar{a} \bar{b}_1)^2 + (\bar{a} \bar{b}_2)^2 + \dots + (\bar{a} \bar{b}_p)^2 = \bar{a}^2 (b_1^2 + \dots + \bar{b}_p^2)$. Nếu $\bar{a}^2 \neq 0, 1$ thì $b_1^2 + \bar{b}_2^2 + \dots + \bar{b}_p^2 = 0$.

Và nói chung: nếu trong tập hợp $F_p$ có một phần tử $\bar{a}$ sao cho $\bar{a}^k \neq 0, 1$, thì tổng lũy ​​thừa $k$ của tất cả các phần tử từ $F_p$ bằng 0.

Rõ ràng là nếu $\bar{a}^k = 1$ đối với đa thức đầu tiên $\bar{a}$ của $F_p$, thì thậm chí còn hơn thế nữa $\bar{b}_k = 1$ đối với tất cả các phần tử khác $\bar{b} \neq 0$. Nếu $\bar{a}^k = 1$ nếu và chỉ nếu k chia hết cho p - 1. Cụ thể, nếu $0 < k < p - 1$, thì $\bar{a}^k \neq 1$ và tổng lũy thừa thứ k bằng 0. Vì $\bar{0}^{p-1} + \bar{1}^{p-1} + \dots + \bar{p-1}^{p-1} = \bar{p-1}$ và $x^p = x$ cho $x \in F_p$ (Định lý nhỏ Fermat), chúng tôi đã tìm thấy tổng lũy thừa thứ k của các phần tử từ $F_p$ với mọi k ≠ 0:

$$\bar{b}_1^k + \bar{b}_2^k + \dots \bar{b}_p^k =$$

$$= \begin{cases} 0, \text{ если } k \neq 0 (\text{mod } p - 1), \\ p - 1, \text{ если } k \equiv 0 (\text{mod } p - 1) \text{ и } k \neq 0. \end{cases}$$

⟦folio 5⟧

Bây giờ chúng ta hãy xem xét một số đơn thức $q = x_1^{k_1} x_2^{k_2} \dots x_t^{k_t}$ và tất cả các tập hợp có thứ tự có thể có $\langle \bar{c}_1, \bar{c}_2, \dots, \bar{c}_n \rangle$, trong đó $\bar{c}_i \in F_p$ ($i = 1, 2, \dots, n$). Có $p^n$ bộ như vậy. Chúng tôi sẽ giả định rằng $t \leq n$. thì với mỗi tập hợp, chúng ta có thể tính giá trị của đơn thức $q$, chúng ta chấp nhận trên tập hợp này: chúng ta cần thay thế các số $t$ đầu tiên của tập hợp thay vì $x_1, x_2, \dots, x_t$. Tổng của tất cả các giá trị $p^n$ này là bao nhiêu? (bài toán mà chúng tôi đã giải về tổng lũy ​​thừa $k$ là trường hợp đặc biệt của bài toán: $q = x_1^k, n = 1$.) Chúng tôi để độc giả tự tìm hiểu câu hỏi này.

Đối với những gì tiếp theo, chúng ta chỉ cần nếu $t < n$ hoặc $0 < k_i < p - 1$ đối với một số $i$, thì loại trừ tổng là $0$. Bạn có thể dễ dàng chứng minh điều này cho mình.

Chứng minh định lý Waring

Chúng ta hãy biểu thị bậc của đa thức $R(x_1, x_2, \dots, x_n)$ bằng $m$, số lời giải của phương trình $R(x_1, x_2, \dots, x_n) = 0$ bằng $N(R)$. Chúng ta cần suy ra từ điều kiện $m < n$ rằng $N(R)$ chia hết cho $p$.

Trong tập $M$ của tất cả các tập hợp phần tử được sắp xếp có thể có từ $F_p$ có độ dài $n$, hãy xem xét tập hợp con $M_R$ lời giải của phương trình $R(x_1, x_2, \dots, x_n) = 0$. Tập hợp con $M_R$ bao gồm các tập hợp $\langle \bar{c}_1, \bar{c}_2, \dots, \bar{c}_n \rangle$ mà $R(\bar{c}_1, \bar{c}_2, \dots, \bar{c}_n) = 0$.

Hãy xem xét hàm $f_R$, gán cho mỗi phần tử $\langle \bar{c}_1, \bar{c}_2, \dots, \bar{c}_n \rangle \in M$ số 1 nếu $\langle \bar{c}_1, \bar{c}_2, \dots, \bar{c}_n \rangle \in M_R$ và số 0 nếu $c \langle \bar{c}_1, \bar{c}_2, \dots, \bar{c}_n \rangle \notin M_R$.

(Một hàm được xác định trên một tập hợp $M$ nào đó và lấy giá trị 1 trên một tập hợp con nào đó $A \subset M$ và giá trị 0 trên các phần tử còn lại của $M$ được gọi là hàm đặc trưng của tập hợp con $A$. Do đó, hàm $f_R$ là hàm đặc trưng của tập hợp con $M_R$.) Từ chính định nghĩa của hàm $f_R$, ta suy ra rằng số lời giải $N(R)$ của phương trình $R(x_1, x_2, \dots, x_n) = 0$ bằng tổng các giá trị của hàm $f_R$ trên tất cả các phần tử của tập hợp $M$. Tuyên bố này dường như không bổ sung thêm gì vào định nghĩa của $f_R$. Tuy nhiên, người đọc sẽ thấy rằng việc thay thế tập $M_R$ bằng hàm $f_R$ là chìa khóa của chứng minh.

Bây giờ chúng ta hãy xem xét hàm $f_R$, khác với hàm $f_R$ ở chỗ thay vì các số 1 và 0, nó lấy lời giải và các giá trị không nghiệm của các giá trị tương ứng $\bar{1}$ và $\bar{0}$ từ $F_p$. Tổng các giá trị $S(\bar{f}_R)$ ​​của hàm $f_R$ trên tất cả các bộ $\langle \bar{c}_1, \bar{c}_2, \dots, \bar{c}_n \rangle$ bằng với lớp dư lượng $N(R)$ (mod $p$) của số $N(R)$. Do đó, để chứng minh định lý Waring, chỉ cần chứng minh $S(\bar{f}_R) = \bar{0}$ là đủ.

Sử dụng Định lý nhỏ Fermat, chúng ta biểu diễn hàm $f_R$ dưới dạng đa thức. Để làm điều này, hãy xem xét đa thức $Q(x_1, x_2, \dots, x_n) = \bar{1} - R(x_1, x_2, \dots, x_n)^{p-1}$. Nếu $R(\bar{c}_1, \bar{c}_2, \dots, \bar{c}_n) \neq 0$ thì Định lý nhỏ Fermat $R(\bar{c}_1, \bar{c}_2, \dots, \bar{c}_n) = \bar{0}$. Nếu $R(\bar{c}_1, \bar{c}_2, \dots, \bar{c}_n) = \bar{0}$ thì $R(\bar{c}_1, \bar{c}_2, \dots, \bar{c}_n)^{p-1} = \bar{0}$ và $Q(\bar{c}_1, \bar{c}_2, \dots, \bar{c}_n) = \bar{1}$. Vì vậy $f_R = Q$.

Đa thức $Q(x_1, x_2, \dots, x_n)$ là tổng của các đơn thức: $Q = q_1 + q_2 + \dots + q_l$.

Chúng ta chỉ cần kiểm tra xem tổng các giá trị của từng đơn thức $q_1, q_2, \dots, q_l$ trên tất cả các tập hợp $\langle \bar{c}_1, \bar{c}_2, \dots, \bar{c}_n \rangle$ có bằng $\bar{0}$ là đủ hay không. Khi đó tổng của $S(f_R) = S(Q)$ sẽ bằng $\bar{0}$, vì $S(Q) = S(q_1) + S(q_2) + \dots + S(q_l)$.

Lấy ví dụ, đơn thức $q_1 = x_1^{k_1} x_2^{k_2} \dots x_t^{k_t}$. Bậc của đa thức $Q$ bằng $(p - 1) m$. Do đó, bậc của đơn thức $q_1$ nhỏ hơn $(p - 1) n$ (theo các điều kiện của Định lý $m < n$). Vì vậy, $k_1 + k_2 + \dots + k_t < (p - 1) n$. Từ bất đẳng thức này, suy ra rằng $t < n$ hoặc trong số $k_1, k_2, \dots, k_t$ có số mũ $k_i$ mà $0 < k_i < p - 1$. Đẳng thức $S(q_1) = \bar{0}$ bây giờ tuân theo kết quả được hình thành ở cuối phần trước.

Định lý Weyl-Lang

Chúng ta đã nói ở trên rằng nếu phương trình diphant có lời giải

⟦folio 6⟧

nitsa, thì bất kỳ phương trình đã cho nào (theo modulo đơn giản bất kỳ $p$) cũng có lời giải.

Câu phát biểu: “Nếu một phương trình Diophantine có một lời giải khác 0, thì bất kỳ phương trình đã cho nào cũng có một lời giải khác 0” là không đúng. Ví dụ, phương trình
$$x^2 + y^2 = 9 = 0$$
có khác không lời giải ($x = 3, y = 0$), nhưng phương trình rút gọn modulo 3
$$x^2 + y^2 = 0$$
không có lời giải như vậy.

Tuy nhiên, rõ ràng là nếu một phương trình Diophantine có một lời giải khác 0, thì với mọi $p$, bắt đầu từ một số nào đó, phương trình đã cho cũng có một lời giải khác 0.

Điều ngược lại không đúng: phương trình.
$$x^2 + y^2 + z^2 = 0$$
(6)
theo định lý Chevalley có lời giải khác 0 trong $F_p$, và phương trình
$$x^2 + y^2 + z^2 = 0$$
không có giá trị khác 0 lời giải (không chỉ trong $Z$, mà còn trong $R$ *).

Bây giờ chúng ta hãy xem xét lại phương trình Diophantine
$$R(x_1, x_2, \dots, x_n) = 0$$,
có các hệ số là số nguyên. Thật thú vị khi biết tập hợp các số nguyên tố $p$ tồn tại lời giải mod $p$ là gì. Đáp số Câu hỏi này được trả lời bằng định lý Weyl-Lang đáng chú ý. Nếu tập $R(x_1, x_2, \dots, x_n)$ là một tập rút gọn tuyệt đối thì phương trình $R(x_1, x_2, \dots, x_n) = 0$ có lời giải theo modulo đơn giản $p$ cho tất cả $p$, bắt đầu từ một số.

Bằng cách rút gọn tuyệt đối bằng một đa thức, chúng tôi muốn nói đến một đa thức không thể khai triển thành tích của hai đa thức modulo $p$ với mọi $p$, bắt đầu từ một số.

*) Đây không phải là một ví dụ thú vị lắm: người đọc có thể kiểm tra rằng, modulo 8, phương trình (6) không có khác 0 lời giải. Trong bài viết được đề cập của M.I. Bashmkov, một ví dụ về phương trình Diophantine ($3x^3 + 4y^3 + 5z^3 = 0$) không có khác 0 lời giải, trong đó phương trình rút gọn lời giải không có phương trình khác 0 theo bất kỳ modulo $p$ nào, được đưa ra.

Điều kiện tối giản tuyệt đối trong việc xây dựng định lý là rất cần thiết: từ nhiệm vụ 2 đến bài “So sánh theo modulo đơn giản” ta suy ra phương trình $x_1^2 + x_2^2 = 0$ giải được cho $p = 4k + 1$ và không giải được cho $p = 4k + 3$. Có nhiều số nguyên tố dạng $p = 4k + 3$ vô hạn nên kết luận của định lý về đa thức $x_1^2 + x_2^2$ là không đúng. Tất nhiên, tiền đề cũng sai đối với anh ta: từ khả năng giải được của phương trình $x_1^2 + x_2^2 = 0$ modulo $p = 4k + 1$ (và cũng có vô số số nguyên tố thuộc loại này), suy ra rằng nó có thể phân tích thành nhân tử đối với modulo này.

Có thể chứng minh rằng "đại đa số" các đa thức là hoàn toàn bất khả quy.

Không giống như định lý Waring, việc chứng minh định lý Weyl-Lang rất khó khăn trong trường hợp tổng quát.

Hãy xem xét một trường hợp rất đặc biệt của phương trình $R(x_1, x_2, \dots, x_n) = 0$: khi đa thức $R$ bậc một: $R(x_1, x_2, \dots, x_n) = a_1x_1 + a_2x_2 + \dots + a_nx_n + b$ (mặc dù một trong các hệ số $a_i$ được giả sử khác 0). Dễ dàng nhận thấy điều đó trong trường hợp này $N(R) = p^{n-1}$. Thật vậy, chúng ta có thể giả sử (sắp xếp lại, nếu cần, chưa biết tức là) rằng $a_1 \neq 0$; sau đó, cho $x_2, \dots, x_n$ tất cả các ý nghĩa có thể có từ $F_p$ và đặt $x_1 = -a_1^{-1}(a_2x_2 + \dots + a_nx_n + b)$, chúng ta nhận được lời giải.

Định lý Weyl–Lang có thể được cải tiến: với $p$ lớn
$$|N(R) - p^{n-1}| < c \cdot p^{\frac{n-1}{2}},$$
trong đó $c$ là số hệ số, tùy thuộc vào đa thức $R$.

Bằng chứng ban đầu của Weyl dựa trên mối liên hệ sâu sắc mà ông đã phát hiện ra giữa các câu hỏi dường như xa xôi: bài toán rời rạc và thậm chí hữu hạn của số lời giải của phương trình $R(x_1, x_2, \dots, x_n) = 0$ trong một modulo đơn giản và cấu trúc hình học của đa thức liên tục của complis lời giải của phương trình này, tức là các tập hợp số complis $\langle d_1, d_2, \dots, d_n \rangle$ mà $R(d_1, d_2, \dots, d_n) = 0$.

Gần đây, một chứng minh cơ bản (không sử dụng phương pháp gián tiếp) nhưng lại rất phức tạp về định lý Weyl-Lang của nhà toán học Sverldov S. A. Stepanov.
