---
id: 1977-3-rozov-otvet-na-vopros-chitatelya-s-kirzhalova-o-reshenii-irratsionalnogo-uravneniya-305cc53b
issue: kvant_1977_3
year: 1977
number: "3"
title: '[Đáp số gửi câu hỏi của độc giả S. Kirzhalov về lời giải phương trình vô tỉ]'
authors:
  - Розов Н. Х.
rubric: raznoe
page_first: 58
page_last: 59
page_labels: 56-57
tag: H0M1
lang: vi
source: kvant_digital
extraction: vision
content_sha256: ee66c6d09f3e986b7ad3bc95cff8dc9e907b250d0de8129138c6cc63319f880b
prompt_sha256: draft-1
translated_from: content/ru/1977/03/articles/19_rozov-otvet-na-vopros-chitatelya-s-kirzhalova-o-reshenii-irratsionalnogo-uravneniya-305cc53b.md
source_content_sha256: de5302fa57fda7c02ca1f98b1d30e661f3138133afbf629ddfccd55a041ac217
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 56⟧

Hỏi - chúng tôi trả lời

Người biên tập nhận được một lá thư từ thành phố Kharkov của Stepan Kirzhalov, một học sinh lớp 9. Đây là những gì anh ấy viết.

“Trong “Sổ tay toán tiểu học” (Kyiv, 1973) tôi đã tìm ra cách giải phương trình vô tỉ
$$\sqrt[3]{8x+4} - \sqrt[3]{8x-4} = 2.$$ (*)

Bất cứ khi nào chúng ta đưa các phần của phương trình này vào một khối lập phương, chúng ta sẽ nhận được $(8x+4)$ -
$$-3\sqrt[3]{8x+4}\sqrt[3]{8x-4} \times (\sqrt[3]{8x+4} - \sqrt[3]{8x-4}) - (8x-4) = 8.$$

Xét rằng theo điều kiện biểu thức trong ngoặc vuông phải bằng 2, ta có thể viết
$$-6\sqrt[3]{64x^2-16} = 0,$$
từ đâu $x_1=1/2$, $x_2=-1/2$. Tôi cũng đã cố gắng giải các phương trình khác
$$\sqrt[3]{2x-1} + \sqrt[3]{x-1} = 1,$$ (**)

nhưng hóa ra trong hai giá trị thu được $x_1=1$, $x_2=0$ chỉ có giá trị đầu tiên thỏa mãn phương trình. Có chuyện gì vậy?

Vì lá thư của đáp số gửi Stepan Kirzhalov có thể được nhiều độc giả «Kvant» khác quan tâm nên chúng tôi đăng đáp số này trên các trang của tạp chí.

Trước hết, chúng tôi nhắc nhở độc giả rằng trong tài liệu toán học, ký hiệu $\sqrt[3]{a}$ được sử dụng theo hai nghĩa (xem “Đại số 8”, M., “Prosveshchenie”, 1975, trang 95).

Đầu tiên, ký hiệu $\sqrt[3]{a}$ biểu thị một số không âm có khối lập phương là $a$; thì ký hiệu này xác định cho bất kỳ $a$ nào. Trong cuốn sách được đề cập trong thư của S. Kirzhalov của G. P. Bevz, P. F. Filchkov, K. I. Shvetsov, F. P. Yaremchuk “Sổ tay về toán tiểu học để xây dựng một trường đại học” (Kyiv, “Naukova Dumka”, 1973, trang 152-153), ký hiệu $\sqrt[3]{a}$ được sử dụng theo nghĩa này, do đó, ví dụ, biểu thức $\sqrt[3]{8x-4}$ tại $x=-1/2$ tồn tại và bằng -2.

Phương pháp giải phương trình lũy thừa bậc ba mà tác giả bức thư viết đến được sử dụng khá thường xuyên. Nó cũng được đề cập trong “Sách tham khảo” nói trên, tuy nhiên, thật không may, trong đó không chỉ ra rằng khi giải một phương trình theo phương pháp châm ngôn, chúng ta có thể thu được các nghiệm ngoại lai, và do đó chúng ta luôn cần phải kiểm tra.

Không khó để kiểm chứng điều này. Hiện chúng tôi đang tiến hành lập luận tương ứng, đặc biệt vì chúng rất đáng tôn trọng và chỉ ra cách điều tra cụ thể câu hỏi về sự tương đương của các phương trình và lý do vi phạm nó được làm rõ. Trước tiên chúng ta hãy trình bày một cách tiếp cận đại số:

$$a^3+b^3+c^3-3abc = \frac{1}{2}(a+b+c)[(a-b)^2+(b-c)^2+(c-a)^2];$$

Để chứng minh điều đó, chỉ cần mở dấu ngoặc ở phía bên phải là đủ.

Xét phương trình

$$\sqrt[3]{f(x)} + \sqrt[3]{g(x)} = \varphi(x)$$

và giả sử rằng $x_0$ là gốc của nó, vậy

⟦folio 57⟧

$$\sqrt[3]{f(x_0)} + \sqrt[3]{g(x_0)} - \varphi(x_0).$$

Nâng cả hai vế của đẳng thức số đúng (3) thành lập phương và tiếp tục biến đổi, chúng ta thu được:

$$f(x_0) + 3\sqrt[3]{f(x_0)} \sqrt[3]{g(x_0)} \left[ \sqrt[3]{f(x_0)} + \sqrt[3]{g(x_0)} \right] + g(x_0) = \varphi^3(x_0).$$

Nếu chúng ta sử dụng lại đẳng thức số đúng (3), chúng ta thu được đẳng thức

$$f(x_0) + 3\sqrt[3]{f(x_0)} \sqrt[3]{g(x_0)} \varphi(x_0) + g(x_0) = \varphi^3(x_0),$$

cho thấy $x_0$ là nghiệm của phương trình

$$f(x) + 3\sqrt[3]{f(x)} \sqrt[3]{g(x)} \varphi(x) + g(x) = \varphi^3(x).$$

Do đó, mọi nghiệm của phương trình (2) đều là nghiệm của phương trình (5).

Bây giờ chúng ta hãy xem xét phương trình (5) và giả sử rằng $x_0$ là nghiệm của nó, do đó đẳng thức số (4) được giữ nguyên. Áp dụng đồng nhất thức (1) với

$$a = \sqrt[3]{f(x_0)}, b = \sqrt[3]{g(x_0)}, c = -\varphi(x_0),$$

chúng ta viết lại đẳng thức (4) dưới dạng

$$\frac{1}{2} \left( \sqrt[3]{f(x_0)} + \sqrt[3]{g(x_0)} - \varphi(x_0) \right) \times \left| \left( \sqrt[3]{f(x_0)} - \sqrt[3]{g(x_0)} \right)^2 + \left( \sqrt[3]{f(x_0)} + \varphi(x_0) \right)^2 + \left( \sqrt[3]{g(x_0)} + \varphi(x_0) \right)^2 \right| = 0.$$

Từ đẳng thức (6), rõ ràng số $x_0$ hoặc thỏa mãn đẳng thức (3), tức là là nghiệm của phương trình (2), hoặc thỏa mãn đẳng thức

$$\sqrt[3]{f(x_0)} = \sqrt[3]{g(x_0)} = -\varphi(x_0),$$

tức là nó là nghiệm của hệ phương trình

$$\begin{cases} f(x) = -\varphi^3(x), \\ g(x) = -\varphi^3(x). \end{cases}$$

Do đó, phương trình (5) có thể có các nghiệm không phải là nghiệm của phương trình (2). Dễ dàng kiểm chứng rằng nghiệm $x_0$ của phương trình (5) được xây dựng cho phương trình (2) khi và chỉ khi các điều kiện

$$\begin{cases} \varphi(x_0) \neq 0, \\ f(x_0) = g(x_0) = -\varphi^3(x_0). \end{cases}$$

Giá trị $x = 0$ mà tác giả bức thư tìm thấy thỏa mãn các điều kiện này và do đó sẽ là nghiệm được xây dựng cho phương trình (**).

Để kết luận, chúng tôi lưu ý một lần nữa rằng theo quan điểm của chương trình giảng dạy ở trường mới, giá trị $x = -1/2$ không phải là nghiệm của phương trình (*), vì trong trường hợp này giá trị của vế trái của phương trình (*) không được xác định.

H. Rozov
