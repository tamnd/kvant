---
id: 1977-10-dorofeev-rozov-otvet-na-vopros-chitatelya-e-glikinoy-o-reshenii-uravneniy-s-beskonechnyim-kolichestvom-operatsiy-5e671270
issue: kvant_1977_10
year: 1977
number: "10"
title: '[Đáp số gửi câu hỏi của độc giả E. Glikina về phương trình lời giải với vô số phép tính]'
authors:
  - Дорофеев Г. В.
  - Розов Н. Х.
rubric: raznoe
page_first: 62
page_last: 63
page_labels: 60-61
tag: NMT0
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 0f67e3ff0e75e8499df64899b6e158fee7611596a9f006ce83c68b82534914c0
prompt_sha256: draft-1
translated_from: content/ru/1977/10/articles/15_dorofeev-rozov-otvet-na-vopros-chitatelya-e-glikinoy-o-reshenii-uravneniy-s-beskonechnyim-kolichestvom-operatsiy-5e671270.md
source_content_sha256: ddeb95da87f76514245dd1bee38c6d59715be0ca8dd4d390c609c4fc63998cb3
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 60⟧

Hỏi - chúng tôi trả lời

Ban biên tập «Kvant» nhận được thư của độc giả Elena Glikina đến từ thành phố Severodonets, vùng Voroshilograd. Đây là những gì cô ấy viết:

“Tôi tình cờ gặp phải một nghịch lý thú vị nhất. Tôi lấy phương trình
$$x^{x^x} = 2;$$
(1)
nó có thể được viết lại thành $x^2 = 2$, do đó $x = \sqrt{2}$, và do đó
$$\sqrt{2} \sqrt{2} \sqrt{2} = 2.$$
(2)
Tôi lấy một phương trình khác:
$$y^{y^y} = 4;$$
(3)
nó có thể được viết lại thành $y^4 = 4$, do đó $y = \sqrt{2}$, và do đó
$$\sqrt{2} \sqrt{2} \sqrt{2} = 4.$$
(4)
Theo sau đó là $2 = 4$. Tôi yêu cầu bạn giải thích lý do cho một phương trình nghịch lý như vậy..."

Chúng tôi nghĩ rằng nó sẽ hữu ích cho tất cả độc giả của chúng tôi khi nghĩ về bức thư này. Đó là lý do tại sao chúng tôi đặt trên các trang của tạp chí cả bức thư và đáp số cho câu hỏi được đặt ra trong đó. Tuy nhiên, đừng vội đọc đáp số - trước tiên hãy cố gắng tự mình hiểu các nguyên tắc xuất hiện của “một phương trình nghịch lý như vậy”.

Vì vậy, một loạt lập luận đã dẫn chúng ta đến đẳng thức $2 = 4$. Tính sai lầm của đẳng thức thu được là điều không thể nghi ngờ, và do đó chúng ta cần tìm kiếm lỗi. Chúng tôi sẽ tiến hành phân tích logic chi tiết từng bước được thực hiện, đặc biệt chú ý đến tính hợp pháp của từng bước chuyển đổi hợp lý. Một trong những quá trình chuyển đổi này dựa trên các quy luật chung của logic hoặc toán học, những chuyển đổi khác được liên kết với các đặc điểm cụ thể của bài toán được đề cập.

Ví dụ, ở bước cuối cùng của quá trình lập luận, chúng ta suy ra từ các đẳng thức (2) và (4) rằng $2 = 4$. Trong trường hợp này, chúng ta dựa rất ít vào tính chất sau: nếu $a = b$ và $a = c$ là các đẳng thức đúng thì $u = b = c$ là một đẳng thức đúng. Đương nhiên, chúng tôi sẽ không đặt câu hỏi về tài sản này.

Nhưng hệ quả $2 = 4$ vẫn sai, và do đó ít nhất một trong các đẳng thức (2), (4) sai.

Chúng ta hãy xem xét kỹ hơn về sự bình đẳng (2). Nó thu được bằng cách thay thế giá trị $x = \sqrt{2}$ tìm thấy tại lời giải của phương trình này vào phương trình (1). Tuy nhiên, nếu $\sqrt{2}$ là nghiệm của phương trình (1), thì đẳng thức (2), tất nhiên, là đúng - nhờ vào định nghĩa của nghiệm. Vì vậy, chúng ta cần kiểm tra xem số $\sqrt{2}$ có thực sự là nghiệm của phương trình (1) hay không.

Lời giải phương trình (1), chi tiết hơn, được thực hiện như sau: đặt số $a$ là nghiệm của phương trình (1), tức là đặt
$$a^{a^a} = 2.$$
(5)
Chúng ta hãy viết lại đẳng thức (5) dưới dạng
$$a^{a^a} = 2.$$
(6)
Sau đó, dựa vào đẳng thức tương tự (5), chúng ta kết luận rằng $a^2 = 2$. Đẳng thức này đúng với giá trị $a = \sqrt{2}$, được khai báo là nghiệm của phương trình (1).

Có phải mọi thứ đều làm chúng ta hài lòng ở lời giải này không? Rõ ràng là không: phương trình $x^2 = 2$ là hệ quả của phương trình bị loại trừ (1), và do đó cần kiểm tra xem lời giải trên có phải là vấn đề nghiêm trọng hay không.

Để kiểm tra việc xác minh, cần phải tìm hiểu xem giá trị của vế trái của phương trình (1) của $x = \sqrt{2}$ có thực sự bằng 2 hay không. Tuy nhiên, sau khi thay thế, chúng ta đi đến vế trái của phương trình (2), mà theo quan điểm của các định nghĩa trường học, nó không có ý nghĩa: ở trường chúng ta đang xử lý kết quả của một số hữu hạn

⟦folio 61⟧

lũy thừa hoạt động, và do đó đẳng thức (2) đơn giản là vô nghĩa. Tất nhiên, đẳng thức (4) không còn ý nghĩa nữa và không có gì đáng ngạc nhiên khi việc sử dụng hai “bình đẳng” này dẫn đến đẳng thức sai 2=4.

Những khó khăn logic nảy sinh có thể tránh được ngay lập tức nếu chúng ta xem xét phương trình (1) cẩn thận ngay từ đầu. Thật vậy, bằng cách thay thế bất kỳ số nào vào vế trái của nó, chẳng hạn như $x=2$ hoặc $x=1/2$, chúng ta nhận được một biểu thức chứa vô số số mũ và sau đó không có ý nghĩa. Ví dụ, hãy thử trả lời câu hỏi, cái gì là

$$2^2 \text{ или } \left(\frac{1}{2}\right)^{\left(\frac{1}{2}\right)} \cdot \left(\frac{1}{2}\right)$$

Trong khi đó, các ví dụ chứa vô số phép toán được tìm thấy trong một số bài toán xây dựng và thật không may, ngay cả trong các kỳ thi tuyển sinh.

Trong toán học, chúng ta thường gặp những biểu thức chứa vô số phép tính. Nhưng những biểu thức như vậy luôn được đưa ra định nghĩa rõ ràng trước. Chương trình giảng dạy mới ở trường học giúp trong một số trường hợp có thể gán ý nghĩa cho tổng của vô số số hạng (chuỗi vô hạn)
$$x_1 + x_2 + \dots + x_n + \dots$$
(xem sách giáo khoa “Đại số và sự khởi đầu của phân tích 9”, trang 67-68), cũng như nhiều biểu thức vô hạn khác.

Chẳng hạn, bằng cách sử dụng khái niệm giới hạn, người ta có thể đưa ra ý nghĩa một cách tự nhiên cho biểu thức

$$A = \sqrt{3\sqrt{3\sqrt{3}}}$$

(7)

Cụ thể, hãy xem xét chuỗi $\{x_n\}$

$$x_1 = \sqrt{3}, x_2 = \sqrt{3\sqrt{3}},$$

$$x_3 = \sqrt{3\sqrt{3\sqrt{3}}}, \dots$$

và chúng ta sẽ hiểu biểu thức (7) là giới hạn của dãy này:

$$A = \lim_{n \to \infty} x_n$$

(tất nhiên là nếu giới hạn này tồn tại). Hãy để chúng tôi chứng minh rằng nó thực sự tồn tại. Từ

$$x_n = 3^{\frac{1}{2}} \cdot 3^{\frac{1}{4}} \cdot \dots \cdot 3^{\frac{1}{2^n}} =$$

$$= 3^{\frac{1}{2}} + \frac{1}{4} + \dots + \frac{1}{2^n}$$

Và

$$\lim_{n \to \infty} \left(\frac{1}{2} + \frac{1}{4} + \dots + \frac{1}{2^n}\right) =$$

$$= \frac{1}{2} / (1 - \frac{1}{2}) = 1,$$

do tính chất không nguyên tố của hàm số mũ $y=3^x$

$$\lim_{n \to \infty} x_n = \lim_{n \to \infty} 3^{\frac{1}{2}} + \frac{1}{4} + \dots + \frac{1}{2^n} =$$

$$= 3^{\lim_{n \to \infty} \left(\frac{1}{2} + \frac{1}{4} + \dots + \frac{1}{2^n}\right)} = 3.$$

Do đó, biểu thức (7) có ý nghĩa và bằng 3.

Bây giờ chúng ta hãy cố gắng giải thích ý nghĩa cho biểu thức

$$\sqrt{2} \sqrt{2} \sqrt{2}, \sqrt{2} \sqrt{2} \sqrt{2}, \dots$$

(9)

Trong bài viết “Phương trình và giới hạn” của A. Egorov (tr. 34), người ta đã chứng minh rằng phương trình

$$(\sqrt{2})^x = x$$

(10)

có chính xác hai nghiệm (kể từ $1 < \sqrt{2} < 1, 42 < e^{\frac{1}{e}}$) và dãy (9) hội tụ về nghiệm nhỏ hơn trong số các nghiệm này. Có thể dễ dàng tìm thấy nghiệm của phương trình (10) bằng cách chọn: $x_1=2$, $x_2=4$. Do đó, giới hạn của dãy (9) bằng 2 và nếu biểu thức (8) mang ý nghĩa trên thì đẳng thức (2) là đúng và (4) là sai.

G. Dorofeev, N. Rozov
