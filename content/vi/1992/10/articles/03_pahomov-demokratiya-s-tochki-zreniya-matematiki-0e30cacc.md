---
id: 1992-10-pahomov-demokratiya-s-tochki-zreniya-matematiki-0e30cacc
issue: kvant_1992_10
year: 1992
number: "10"
title: Dân chủ trong toán học
authors:
  - Пахомов В.
rubric: osnovnye-stati
page_first: 4
page_last: 9
page_labels: 2-7
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 01daf041961d5d4bd5b59e97352c169de7f1127c76909a409a6ce65ba676f437
prompt_sha256: draft-1
translated_from: content/ru/1992/10/articles/03_pahomov-demokratiya-s-tochki-zreniya-matematiki-0e30cacc.md
source_content_sha256: faf0398654ef874c1a18785ee78a8353206acaab52e34f62cec6548d25110cdd
translation_model: draft
translation_run: vi-draft-gaps-2026-11-07
translation_quality: draft
---

⟦folio 2⟧

---
running_head:
folio:
---

TỪ QUAN ĐIỂM
TOÁN HỌC

V. PAKHOMOV

Người ta có thể trích dẫn thêm rất nhiều quy tắc bầu cử và những nghịch lý để đảm bảo rằng không có một hệ thống dân chủ tuyệt đối tốt. Tất cả điều này dẫn đến suy nghĩ đáng buồn của nhiều người rằng nền dân chủ như ý chí của đa số không tồn tại, hoặc, như chúng ta đã thấy, chính khái niệm “ý kiến ​​đa số” không tồn tại...

Chức năng
sở thích tập thể

Hãy đặt một cái gì đó tổng quát hơn một chút bài toán. Hãy để $n$ các thành viên quốc hội xác định hệ thống ưu tiên tài trợ công $m$ của các chương trình khác nhau. Giả sử, trước hết, quỹ được phân bổ cho chăm sóc sức khỏe, từ phần còn lại của ngân sách - cho chương trình giáo dục, sau đó từ phần còn lại - cho chương trình xây dựng nhà ở, v.v. Mỗi thành viên quốc hội đều có quan điểm riêng của mình về việc sắp xếp các khoản mục chi phí này. Cần phải xây dựng trật tự của họ, phản ánh ý kiến ​​​​của toàn thể quốc hội.

Vì không có sự khác biệt về mặt toán học giữa thứ tự các chương trình của chính phủ và thứ tự của các ứng cử viên, chúng tôi sẽ tiếp tục lên tiếng để thuận tiện cho cử tri và các ứng cử viên của quốc hội và các chương trình. Vậy có $n$ cử tri và $m$ ứng cử viên. Yêu cầu

Kết thúc. Xem phần đầu ở «Kvant» số 9.

⟦folio 3⟧

---
running_head:
folio:
---

xây dựng một hàm xác định thứ tự tập thể trên tập hợp các ứng cử viên, tức là hàm chính xác cho bất kỳ thứ tự nhất định nào $>$, $>^2$, ..., $>^n$ xác định thứ tự tập thể $>$:

$$>^s = f(>^1, >^2, ..., >^n).$$

Ở đây, chúng tôi giả định ba khả năng để so sánh từng cặp ứng viên, chẳng hạn như $a$ và $b$:

$$a >^s b \text{ (a лучше } b),$$
$$a =^s b \text{ (a и } b \text{ одинаковы),}$$
$$a <^s b \text{ (a хуже } b),$$
và sự kết hợp của họ như

$$a >^s b \text{ (a не хуже } b).$$

Có thể có nhiều chức năng như vậy. Ví dụ: $f$ có thể tuyên bố tất cả các ứng viên đều bằng nhau. Vì vậy, cần phải áp đặt một số hạn chế đối với $f$. Trước hết, nó phải được xác định cho bất kỳ số lượng ứng cử viên (hữu hạn). Ví dụ: đối với hai ứng cử viên, tất cả các quy tắc bầu cử được liệt kê đều giống nhau, do đó, hàm $f$ trong trường hợp này rất dễ xây dựng: một trong hai ứng cử viên thắng và do đó chiếm vị trí đầu tiên (và đối thủ chiếm vị trí thứ hai), hoặc hóa ra họ bằng nhau. Ví dụ, đối với hồ sơ

| Cử tri | 1 | 2 | 3 | 4 | 5 | 6 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Ứng viên | $a$ | $a$ | $b$ | $a$ | $b$ | $a$ |
| | $b$ | $b$ | $a$ | $b$ | $a$ | $b$ |

hồ sơ tương đương

| Nhóm cử tri | {1, 2, 4, 6} | {3, 5} |
| :--- | :--- | :--- |
| Ứng viên | $a$ | $b$ |
| | $b$ | $a$ |

chúng tôi có $a >^s b$ theo bất kỳ quy tắc bỏ phiếu nào. Đối với hồ sơ

Không có quy tắc nào của chúng tôi tạo ra người chiến thắng, vì vậy $a =^s b$ nên được xem xét.

Tuy nhiên, những quy định này cần được bổ sung thêm trong trường hợp số lượng ứng cử viên nhiều hơn hai. Cách đơn giản nhất như sau.

Đặt $M$ là tập các ứng cử viên và $p$ là lựa chọn đúng. Hãy biểu thị người chiến thắng (có thể có một vài người trong số họ) bằng ký hiệu $p(M)$. Họ sẽ chiếm vị trí đầu tiên. Sau đó, chúng tôi loại trừ những người chiến thắng này khỏi $M$, dẫn đến một tập hợp mới $M_1 = M \setminus p(M)$. Áp dụng $p(M_1)$ đúng cho nó với tư cách là người chiến thắng từ $M_1$ sẽ xếp họ ở vị trí thứ hai. Loại bỏ những người chiến thắng khỏi $M_1$, chúng ta nhận được $M_2 = M_1 \setminus p(M_1)$ mới, v.v. Kết quả là chúng ta thu được hàm $f$.

Hãy xem xét một vài ví dụ.

Đặt $p$ là đa số đúng. Xem xét hồ sơ $H (n=3, M=\{a, b, c, d\})$:

| Hồ sơ $H$ |
| :--- |
| Cử tri | 1 | 2 | 3 |
| Ứng viên | $a$ | $d$ | $b$ |
| | $b$ | $a$ | $c$ |
| | $c$ | $b$ | $d$ |
| | $d$ | $c$ | $a$ |

Quy tắc đa số đưa ra một phiếu bầu cho $a, d, b$, do đó $p(M) = \{a, b, d\}$. Họ chiếm vị trí đầu tiên và ứng cử viên còn lại $c$ sẽ đứng thứ hai. Vậy $f$ khớp với hồ sơ $H$ thứ tự

$$a =^s b =^s c.$$

Hãy xem xét chức năng tương tự trên hồ sơ $A$. Chúng ta có $p(A) = \{a\}, A_1 = \{b, c, d\}$ và pro-

⟦folio 4⟧

---
running_head:
folio:
---

tập tin $A_1$ cho $p(A_1) = \{d\}$ và $A_2 = \{b, c\}$:

Hồ sơ $A_1$
Số phiếu bầu 5 3 5 4
Thí sinh $d$ $d$ $b$ $c$
$c$ $b$ $c$ $d$
$b$ $c$ $d$ $b$

Hồ sơ $A_2$
Số phiếu bầu 5 3 5 4
Thí sinh $c$ $b$ $b$ $c$
$b$ $c$ $c$ $b$

Cuối cùng, từ hồ sơ $A_2$, rõ ràng là $p(A_2) = \{c\}$, tức là $f$ chỉ định thứ tự của $a > s > d > s > b$.

Quy tắc đa số tuyệt đối tạo ra hàm riêng $f$, tuy nhiên, hàm này không được xác định cho tất cả các cấu hình (ví dụ: đối với cấu hình $H$), nhưng đối với cấu hình $A$, nó đưa ra (kiểm tra!) thứ tự $b > s > c > d > s > a$, chính xác là thứ tự ngược lại theo quy tắc đa số tương đối.

Quy tắc của Condorcet cũng không được xác định cho tất cả các cấu hình, nhưng đối với cấu hình $A$ nó đưa ra thứ tự (kiểm tra!) $c > s > d > s > a$.

Cuối cùng, quy tắc Borda trong phương thức của chúng tôi xác định hàm $f$, hàm này liên kết thứ tự $d > s > c > s > b > s > a$ với cấu hình $A$.

Lưu ý rằng quy tắc Borda có thể xác định hàm $f$ vô thời hạn: chỉ cần sắp xếp các ứng viên theo thứ tự điểm số giảm dần của họ là đủ. Điều này mang lại cho hồ sơ $A$ thứ tự $d > s > c > s > b > s$.

Như bạn có thể thấy, với định nghĩa về trật tự này, $b$ hóa ra là tệ nhất.

Vì vậy, tất cả các quy tắc đều khá hợp lý nhưng lại dẫn đến những kết quả khác nhau, thậm chí ngược lại. Để đạt được một kết quả rõ ràng, chúng tôi sẽ cố gắng trình bày một số yêu cầu đối với chức năng của một đề xuất tập thể mà chúng tôi sẽ xây dựng dưới dạng tiên đề. Để thuận tiện, chúng ta hãy biểu thị tập hợp cử tri bằng $S$.

Tiên đề 1 (sự đầy đủ). Đối với bất kỳ ứng cử viên nào $a$ và $b$ thứ tự chung được xác định là $a > s > b$, $a = b$ hoặc $a < s > b$.

Tiên đề 2 (tính bắc cầu). Nếu $a > b$ và $b > c$ thì $a > c$.

Tiên đề đầu tiên nói rằng chúng ta có thể so sánh hai ứng cử viên bất kỳ, và tiên đề thứ hai là đương nhiên đối với bất kỳ thứ tự nào; không có nó, một tình huống có thể xảy ra trong đó $a$ tốt hơn $b$, $b$ tốt hơn $c$ và $c$ tốt hơn $a$.

Tiên đề 3 (thống nhất). Nếu tất cả cử tri tin rằng $a$ tốt hơn $b$, thì $u$ trong đề xuất tập thể $a$ sẽ tốt hơn $b$.

Tiên đề này là chắc chắn và không cho phép chúng ta xây dựng một quy tắc trong đó “mọi người đều bình đẳng”.

Tiên đề 4 (độc lập). Vị trí của hai ứng cử viên bất kỳ $a$ và $b$ chỉ phụ thuộc vào vị trí tương đối của họ trong đề xuất cá nhân của cử tri và không phụ thuộc vào vị trí của các ứng cử viên khác.

Ví dụ, hồ sơ

Cử tri 1 2 3 4
Thí sinh $a$ $c$ $b$ $a$
$b$ $a$ $c$ $b$
$c$ $b$ $a$ $c$

Cử tri 1 2 3 4
Thí sinh $a$ $a$ $b$ $c$
$c$ $c$ $a$ $a$
$b$ $b$ $c$ $b$

nói chung là khác nhau, nhưng vị trí tương đối của $a$ và $b$ là như nhau đối với tất cả cử tri: cử tri 1, 2 và 4 coi $a$ tốt hơn $b$ và chỉ có cử tri thứ ba coi $b$ tốt hơn $a$. Trong trường hợp này, hàm tập thể

⟦folio 5⟧

---
running_head:
folio:
---

Đối với bất kỳ tùy chọn cụ thể nào, $a$ và $b$ phải được đặt theo cùng một cách cho cả cấu hình này và cấu hình kia. Chẳng hạn, đây có thể là các mệnh lệnh $a > b > c$ và $a > c > b$ (chúng được đưa ra ở đây theo quy tắc của Borda). Việc từ chối tiên đề độc lập dẫn đến sự xuất hiện của các thao tác: như chúng ta đã thấy, bằng cách loại bỏ (và do đó giới thiệu) các ứng cử viên, người ta có thể thay đổi vị trí tương đối của các ứng cử viên còn lại theo quy tắc Borda (so sánh hồ sơ $D$ và $E$).

Chúng ta hãy đưa ra một ví dụ về hàm ưu tiên tập thể thỏa mãn tất cả các tiên đề sau:

$$f(\geqslant 1, \geqslant 2, \dots, \geqslant n) = \geqslant 1.$$

Hàm này xác định một *quy tắc của nhà độc tài*: bất kể sở thích của những người bỏ phiếu khác, nó sẽ thiết lập thứ tự do người bỏ phiếu đầu tiên xác định. Tất nhiên, thay vì cử tri thứ nhất, người ta có thể chọn cử tri thứ hai, thứ ba, $n$th - bản chất của vấn đề không thay đổi. Chỉ có kẻ độc tài thay đổi.

**Mũi tên định lý**

Kết quả của Arrow, khiến nhiều người bất ngờ, là, bất chấp mọi tính hợp lý của các tiên đề của chúng ta, *quy tắc edinwall* thỏa mãn chúng là quy tắc của nhà độc tài.

Để chứng minh định lý này, chúng tôi giới thiệu một số khái niệm quan trọng. Tập hợp con $A$ tập hợp cử tri $S$ được gọi là *liên minh*. Chúng ta sẽ gọi một liên minh là $f$-quyết định cho ứng cử viên $a$ so với ứng cử viên $b$ nếu và chỉ khi, từ thực tế là tất cả các thành viên của liên minh xếp hạng $a$ trên $b$ và mọi người bên ngoài liên minh đó xếp hạng $b$ trên $a$, liên minh đó tuân theo $a > b$. Nói cách khác, đối với các cấu hình như

| Nhóm cử tri | Ứng viên |
| :--- | :--- |
| $A$ | ... $a...b...$ |
| $S \setminus A$ | ... $b...a...$ |

trong đó các dấu chấm thể hiện sự sắp xếp tùy ý của các ứng cử viên khác, hàm $f$ xác định thứ tự của loại

$$... > a > ... > b > ...$$

Sự thật này sẽ được viết ngắn gọn như sau: $A = f(a, b)$. Lưu ý rằng $A$ phụ thuộc vào các ứng cử viên cụ thể $a$ và $b$ và không bắt buộc phải là người quyết định f cho $c$ so với $d$. Cuối cùng, nếu đối với hai ứng cử viên bất kỳ $x$ và $y$, ứng cử viên $A$ là f-quyết định cho $x$ so với $y$, thì chúng tôi gọi đó là f-quyết định.

Đối với liên minh quyết định f, tên của các ứng cử viên không còn quan trọng nữa: nếu các thành viên của liên minh xếp hạng ai đó cao hơn người khác và tất cả các cử tri khác xếp hạng những ứng cử viên này hoàn toàn ngược lại (và không phải bằng cách nào đó!), thì trong nhóm ưu tiên, người được liên minh đánh giá cao hơn sẽ cao hơn.

Lưu ý rằng toàn bộ tập hợp cử tri $S$ là một trường hợp “hạn chế” của một liên minh quyết định f, hoặc đối với nó, định nghĩa này chắc chắn đúng do tiên đề về sự nhất trí.

Vì lý do tương tự, tập trống không thể mang tính quyết định f cho $a$ đối với $b$ với bất kỳ $a$ và $b$ nào: nếu không có gì đặt $a$ trên $b$, tức là mọi thứ đều đặt $b$ trên $a$, thì bằng tiên đề nhất trí $a < b$, và do đó không thể có $a > b$.

** Bổ đề 1. Có một cặp $(a, b)$ trong đó có một liên minh $D$ bao gồm một cử tri $\{d\}$, đồng thời $d$ là f-quyết định cho $a$ chống lại $b$.

Bằng chứng. Chúng ta hãy biểu thị bằng $F$ tập hợp các liên minh như vậy $A$, với mỗi liên minh trong số đó có một cặp $(a, b)$ sao cho $A = f(a, b)$ (đối với mỗi liên minh của $F$ thì có một liên minh của riêng nó).

Tập $F$ không trống vì nó bao gồm tập hợp tất cả các cử tri $S$. Chúng ta hãy lấy một liên minh $D$ từ tập hợp $F$ chứa số lượng cử tri nhỏ nhất. Vì $F$ không trống nên $D$ chứa ít nhất một người bỏ phiếu. Cần phải chứng minh rằng anh ta ở đó và sẽ chính xác một mình.

⟦folio 6⟧

---
running_head:
folio:
---

Vì vậy, nếu giả định rằng có ít nhất hai trong số chúng dẫn đến mâu thuẫn thì bổ đề sẽ được chứng minh.

Vì vậy, giả sử rằng $D$ có thể được chia thành hai tập con rời rạc, không trống: một $\{d\}$, bao gồm một phần tử và tập còn lại $E$, bao gồm tất cả các phần tử còn lại.

Bây giờ chúng ta hãy nhìn vào hồ sơ

Nhóm cử tri $\{d\} E S\backslash D$
Ứng viên $a c b b a c c$
Vì liên minh mang tính quyết định $D - f$ cho $a, b$, nên $a > b$. Nếu $c > b$, thì điều này có nghĩa là liên minh $E$ mang tính quyết định $f$ cho $c$ so với $b$. Nhưng $E$ có ít cử tri hơn $D$, theo định nghĩa là tối thiểu. Kết quả mâu thuẫn cho thấy rằng $c$ không thể tệ hơn $b$. Điều này có nghĩa là, theo tiên đề canvas, $b$ tốt hơn $c$.

Bây giờ chúng ta có $a > b, b > c$, mở đầu, nhờ vào tiên đề về tính bắc cầu, chúng ta thu được $a > c$. Nhưng điều này có nghĩa là $\{d\}$ là $f$ mang tính quyết định đối với $a$ đối với $c$, điều này cũng mâu thuẫn với tính chất tối thiểu của $D$.

Như vậy chúng ta đã đi đến một mâu thuẫn; và bổ đề đã được chứng minh.

Bổ đề 2. Liên minh $D = \{d\}$, mà sự tồn tại của nó đã được chứng minh trong bổ đề trước, là $f$-quyết định.

Bằng chứng. Cho $c$ là một ứng cử viên tùy ý. Chúng ta hãy nhìn vào hồ sơ

Nhóm cử tri Ứng viên $\{d\} \dots a \dots b \dots c$
$S\backslash \{d\} (S \text{ без } d)$ $\dots b \dots c \dots a$

($d$ đặt $a$ ở trên $b$ và $b$ ở trên $c$, những người khác đặt $b$ ở trên $c$ và $c$ ở trên $a$). Vì $\{d\} = f(a, b)$, nên $a > b$; theo tiên đề nhất trí, chúng ta có $b > c$, và do đó, theo tiên đề bắc cầu, $a > c$. Theo tiên đề độc lập, kết quả của chúng tôi không phụ thuộc vào $b$, tức là đối với bất kỳ hồ sơ nào có dạng

Nhóm cử tri Ứng viên $\{d\} \dots a \dots c$
$S\backslash \{d\} \dots c \dots a$

chúng ta có $a > c$, có nghĩa là $\{d\} = f(a, c)$, trong đó ứng viên $c$ đã là tùy ý.

Tương tự đối với ứng viên tùy ý $e$, lấy hồ sơ theo mẫu

Nhóm cử tri Ứng viên $\{d\} \dots e \dots a \dots c$
$S\backslash \{d\} (S \text{ без } d)$ $\dots c \dots e \dots a$

và lặp lại tất cả các lý do, chúng ta thu được $e > c$ đó. Trong ước tính cuối cùng, $\{d\} = f(c, e)$ đối với $e$ và $c$ tùy ý, tức là, là $f$-quyết định.

Bổ đề 3. Người bỏ phiếu $d$ được mô tả ở trên là một nhà độc tài.

Tại thời điểm này, chúng tôi nhận thấy rằng $d$ có thể nêu ý kiến ​​​​của mình về hai ứng cử viên bất kỳ $a$ và $b$, với điều kiện là ý kiến ​​​​của những cử tri còn lại trái ngược nhau. Điều này cũng cho thấy sự phụ thuộc vào ý kiến ​​của người khác. Chúng ta phải chứng minh rằng, dù số cử tri còn lại bỏ phiếu thế nào thì ý kiến ​​tập thể cũng trùng khớp với ý kiến ​​của $d$.

Chứng minh Bổ đề 3. Cũng xem xét một hồ sơ bỏ phiếu trong đó cử tri $d$ có thứ tự dạng $\dots a > d \dots c > d \dots b > d \dots$, tất cả các ứng cử viên khác xếp hạng $c$ trên $a$ và $b$, và nếu không thì thứ tự của các ứng cử viên của họ là tùy ý.

⟦folio 7⟧

---
running_head:
folio:
---

Vì liên minh mang tính quyết định $\{d\} — f$, nên $a > s$; bởi tiên đề nhất trí, $c > b$, do đó, bởi tiên đề bắc cầu, $a > b$. Loại trừ $c$ khỏi thư từ (do tiên đề độc lập), chúng ta thu được rằng nếu $d$ thích ứng viên $a$ hơn ứng cử viên $b$, thì anh ta sẽ được ưu tiên chung:

$$a > d \Rightarrow a > b$$

(bất kể vị trí của $a$ và $b$ trong số những cử tri khác!).

Thay đổi vai trò của $a$ và $b$, chúng ta nhận được

$$a < d \Rightarrow a < b$$.

Vì vậy, thứ tự $> d$ và $> s$ giống nhau:

$$a > d \Leftrightarrow a > b$$.

Như vậy định lý Arrow đã được chứng minh hoàn toàn.

Một số kết luận hàng ngày từ định lý Arrow

Cuối cùng chúng ta đã nhận được gì? Hóa ra bằng cách đưa ra những quy định rõ ràng và hợp lý mà thoạt nhìn đảm bảo cho việc lựa chọn một ứng cử viên hiệu quả được đa số ưa thích, chúng ta đã nhận được ... một chế độ độc tài. Tiên đề rõ ràng đã hủy hoại nền dân chủ.

Vì vậy, discatura là một khái niệm khá rõ ràng, đáp ứng các nguyên tắc đơn giản, nhưng khái niệm democratini không thể được hình thành khác hơn là một “sự thay thế cho discatura”.
Mặc dù vậy, dân chủ thu hút mọi người, là môi trường chính trị tự nhiên cho sự phát triển của xã hội. Chỉ trong đó mới có thể diễn ra quá trình lựa chọn tự nhiên những người “mạnh nhất” và “khôn ngoan nhất”, hoặc chiến thắng trong các cuộc bầu cử hoặc thực hiện lời giải của một người thường đòi hỏi, ngoài khả năng thuyết phục, còn có khả năng tính toán. Nhưng đây cũng chính là tai họa của nó. Thông thường, kết quả có thể bị thao túng bằng tính toán.

Hệ thống độc tài nhất quán, tự cung tự cấp đã chết: không còn nơi nào để nó phát triển.

Và một kết luận hàng ngày nữa. Bạn có bao giờ thắc mắc tại sao hệ thống hai đảng lại phổ biến ở nhiều nền dân chủ đến vậy không? Chúng tôi đã đề cập đến một trong những lý do giải thích cho điều này: đối với hai ứng cử viên, các quy tắc bỏ phiếu khác nhau sẽ cho kết quả như nhau và do đó phiếu bầu đa số sẽ bị loại bỏ.

Và cuối cùng là một bình luận...

Có ba người được đề cập trong bài viết này mà chúng tôi muốn nói vài lời.

Thông tin chúng tôi có về Jean Charles Borda như sau. Sinh năm 1733, mất năm 1799. Do đó, ông sống qua Cách mạng Pháp và chứng kiến ​​sự trỗi dậy của Bonaparte. Ông là nhà vật lý và khảo sát, thành viên của Viện Hàn lâm Pháp. Tham gia vào việc phát triển hệ thống đo lường số liệu. Năm 1792, ông xác định được độ dài của con lắc thứ hai ở Paris và tìm ra cách xác định chính xác chu kỳ dao động của con lắc. Ông cũng làm việc trong lĩnh vực thủy lực; đã chứng minh định lý, hiện mang tên ông, về tác dụng của một tia chất lỏng hoặc khí. Ông để lại công việc toán học về điều khiển vi phân và phép tính biến phân. Ông tham gia chính trị trong thời kỳ cách mạng; Khi đó nhu cầu thực sự phát triển các thủ tục dân chủ nảy sinh và Borda đã đề xuất hệ thống bỏ phiếu của mình.

Nổi tiếng hơn nhiều là Jean Antoine Nicolas de Condorcet (1745-1794), hầu tước, nhà bách khoa toàn thư, triết gia, nhà toán học, nhà xã hội học và chính trị gia. Bạn của d'Alembert và Voltaire. Tất nhiên là thành viên của Học viện Pháp. Năm 1776, ông được bầu làm thành viên của Viện Hàn lâm Khoa học St. Petersburg, nhưng vào năm 1792, ông bị trục xuất theo lệnh của Catherine II, người không tán thành (nói một cách nhẹ nhàng) quan điểm chính trị của ông. Condorcet chết bi thảm hơn. Anh ta đã bị máy chém đi ngang qua, hạ gục một cột những người ủng hộ chính trị của anh ta, nhưng buộc phải trốn tránh nó, Condorcet vào một giờ không may đã gặp phải bầy sói trong rừng.

Một cái tên khác mà bạn đã gặp là Kenneth Arrow. Ông là người theo chủ nghĩa cầu toàn của chúng ta, một nhà kinh tế học nổi tiếng người Mỹ, người đoạt giải Poblev năm 1972 về kinh tế. Hoạt động trong lĩnh vực kinh tế lượng, lý thuyết phát triển kinh tế nói chung, lý thuyết kinh tế phúc lợi, lý thuyết quản lý.
