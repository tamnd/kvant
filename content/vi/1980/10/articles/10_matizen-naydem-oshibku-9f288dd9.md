---
id: 1980-10-matizen-naydem-oshibku-9f288dd9
issue: kvant_1980_10
year: 1980
number: "10"
title: Hãy cùng tìm ra lỗi
authors:
  - Матизен В. Э.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 45
page_last: 48
page_labels: 43-46
tag: FKVS
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 8fade6d8aee3d4ee4048ca9e96ef19de0620bee4ed4e971c1e025fc12c1c4b0b
prompt_sha256: draft-1
translated_from: content/ru/1980/10/articles/10_matizen-naydem-oshibku-9f288dd9.md
source_content_sha256: b18427d8f4082750b35f06c0b81808abb4c51496a91fce96c335d5e1029d1299
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 43⟧

V. Matizen

Hãy cùng tìm ra lỗi

Khi giải bài toán, người nộp đơn và học sinh thường nhận được đáp số, người có kinh nghiệm thoạt nhìn sẽ thấy rõ lỗi này. Thực tế là tính không chính xác của kết quả thường có thể được xác định bằng những phương pháp rất đơn giản mà không cần giải lại bài toán.

Bài đăng này cho thấy những cách đơn giản nhất để nhanh chóng kiểm tra. Hãy đặt chỗ ngay: không ai trong số họ đảm bảo điểm dừng. Nhưng nếu đáp số có lỗi nghiêm trọng thì khả năng cao là nó sẽ bị phát hiện. Ngoài ra, việc kiểm tra còn hữu ích hơn nhiều so với phương pháp tự kiểm soát đó, than ôi, là phương pháp duy nhất mà hầu hết học sinh có - kiểm tra với hàng xóm. Vì vậy, thưa giáo viên, hãy tự kiểm tra!

1. Danh tính và các phép biến đổi giống hệt nhau

Cần đơn giản hóa biểu thức

$$f(x,y) = \sin^2 \frac{x-y}{2} + \sin^2 \frac{x+y}{2} - 2 \sin \frac{x+y}{2} \sin \frac{x-y}{2} \cos y.$$

Thực hiện tính toán

$$f(x,y) = \frac{1-\cos(x-y)}{2} + \frac{1-\cos(x+y)}{2} - (\cos x+\cos y) \cos y = f_1(x,y) = 1 - \frac{\cos(x-y)+\cos(x+y)}{2} - \cos x \cdot \cos y - \cos^2 y = f_2(x,y)$$

bạn có một vài điểm nổi bật đúng sự thật. Tất cả các công thức này trở thành đẳng thức thực sự khi thay thế điểm (0;0), nhưng chỉ công thức cuối cùng “chịu được” điểm $\left(\frac{\pi}{2}; \frac{\pi}{6}\right)$. Cô ấy sẽ chung thủy.

Tất nhiên, một học sinh được chuẩn bị tốt phải biết các công thức chuẩn và sử dụng chúng một cách chính xác. Thật không may, thực hành thi cử cho thấy rằng những sai sót “cuối cùng” vẫn xảy ra trong việc tự kiểm soát, mặc dù chúng không phải là tuyệt đối nhưng chúng rất hữu ích trong những nhiệm vụ như vậy.

⟦folio 44⟧

Đôi khi sự nghi ngờ về tính xác thực của một câu chuyện nảy sinh vì lý do tính đối xứng. Giả sử rằng khi phân tích đa thức

$$P(x, y, z) = (x + y + z)^3 - x^3 - y^3 - z^3$$

bạn có

$$3(x + y)(x + z)(y - z); \quad P_1(x, y, z)$$

thì bạn phải báo cáo ngay rằng mình đã nhầm: trong đa thức $P(x, y, z)$ các biến $x, y, z$ bằng nhau (nghĩa là nó không thay đổi theo bất kỳ hoán vị nào của các biến*):

$$P(x, y, z) = P(x, z, y) = P(z, x, y) = \dots),$$

nhưng trong đa thức $P_1(x, y, z)$ không có: $(P_1(x, y, z) = -P_1(x, z, y))$.

2. Phương trình, hệ phương trình

Sau khi giải phương trình, hãy thử thay kết quả đáp số vào đó và nếu khó tính thì ít nhất hãy ước tính xem cả hai bên có bằng nhau hay không. Điều này thường hữu ích cho dù có cần thử nghiệm công thức để loại bỏ những rễ thừa hay không. Giả sử, nếu với lời giải các phương trình

$$\sqrt{2x - 6} + \sqrt{x + 4} = 5$$

bạn đã thu được nghiệm 5 và 170, ước tính sẽ ngay lập tức cho thấy rằng tại $x = 170$ vế bên trái rõ ràng lớn hơn vế phải và giá trị tìm thấy của nghiệm $x = 170$ là sai. Cũng có thể thiết lập từ những cân nhắc chung rằng một phương trình đã cho không thể có nhiều hơn một nghiệm. Trên thực tế, hàm $f(x) = \sqrt{2x - 6} + \sqrt{x + 4}$ trả về trên tất cả các miền, tức là ở $x \ge 3$ (giải thích lý do tại sao mà không tính toán một giá trị tùy ý) và do đó, hàm này có thể nhận giá trị 5 nhiều nhất một lần. Nếu bạn biết một chút về tính chất của hàm đơn điệu liên tục (“Đại số và phần đầu của phân tích 10”, đoạn 84), thì từ thực tế là $f(3) = \sqrt{7} < 5$ và $f(10) = 2\sqrt{14} > 5$, chúng ta có thể kết luận rằng từ 3 đến 10 cũng cần phải tìm $x_0$, tức là $f(x_0) = 5$.

*) Các nhà toán học gọi đa thức (và thậm chí cả hàm số) có các tính chất này là đối xứng.

Lỗi trong hệ lời giải của phương trình thường có thể được phát hiện bằng cách quan sát tính đối xứng. Ví dụ, hệ thống

$$\begin{cases} x^2 + xy + y^2 = 7, \\ x^4 + x^2y^2 + y^4 = 21 \end{cases}$$

không thay đổi khi sắp xếp lại các ẩn số và khi thay đồng thời $x$ bằng $-x$ và $y$ bằng $-y$ (kiểm tra!). Do đó, nếu lời giải bạn tìm thấy bao gồm cặp (2; 1) và không bao gồm ít nhất một trong các cặp (1; 2), (-2; -1), (-1; -2), thì bạn đã mất lời giải ở đâu đó.

Tương tự, người ta có thể nhận thấy rằng cùng với nghiệm $(x_0; y_0)$ của hệ

$$\begin{cases} x + \frac{1}{x} + y + \frac{1}{y} = a, \\ x^2 + \frac{1}{x^2} + y^2 + \frac{1}{y^2} = b \end{cases}$$

nó cũng sẽ thỏa mãn các cặp $(x_0; \frac{1}{y_0}), (\frac{1}{x_0}; y_0), (\frac{1}{x_0}; y_0), (\frac{1}{x_0}; \frac{1}{y_0})$ và $(\frac{1}{y_0}; \frac{1}{x_0})$.

3. Bất bình đẳng

Đặt lời giải $\sqrt{7 + x} \ge 5 - x$ là bắt buộc.

«Đáp số»: [2; 9].

Để kiểm tra, chúng ta hãy bắt đầu nhìn vào trục thực, nhìn từ “âm vô cực” đến “cộng vô cực”. Trước hết, hãy lưu ý rằng các số âm “lớn” không được bao gồm trong tập lời giải: đối với chúng, biểu thức căn thức ở vế bên trái của bất đẳng thức của chúng ta là âm và bất đẳng thức không được xác định (kiểm tra bằng cách thay thế $x = -10^2; -10$). Khi tăng $x$, hàm $7 + x$ trả về và hàm $5 - x$ sẽ tắt. Bắt đầu với $x = -7$ chúng ta bước vào miền xác định sự bất bình đẳng. Hãy thay thế một số để tính cả hai phần của giá trị, ví dụ: $x = -6; -3; 0$. Chúng ta thấy rằng với những giá trị này thì bên trái vẫn nhỏ hơn bên phải. Hãy thay thế giới hạn dưới của đáp số của chúng ta, tức là $x = 2$. Bình đẳng! Khi $x$ tăng thêm, bên phải tiêu diệt, bên trái quay lại -

⟦folio 45⟧

do đó, các giá trị tiếp theo của $x$ được bao gồm trong tập hợp lời giải. Chúng ta hãy thay thế ranh giới bên phải $x=9$ vào bất đẳng thức. Chúng tôi nhận được $4>-4$. Sự bất bình đẳng là đúng, nhưng đáng thất vọng. Tại sao, với sự khác biệt như vậy giữa các phần của bất đẳng thức, đáp số lại cho thấy rằng không còn lời giải nữa? Hãy thay thế một số dương "lớn", ví dụ: $x=10^3$. Sự bất bình đẳng rõ ràng là công bằng! Dễ dàng kết luận rằng khoảng thời gian giảm cân là $]9; +\infty$ [: xét cho cùng, với bất kỳ $x>9$ nào thì phần bên phải là âm và phần bên trái là dương, và với $x>9$ thì bất đẳng thức là đúng. Kiểm tra của chúng tôi không chỉ phát hiện ra bất đẳng thức đáp số mà còn cho phép chúng tôi chỉ ra đáp số đúng.

(Bạn có thể lấy [2; 9] làm tập hợp lời giải, chẳng hạn như thế này:

$$\sqrt{7+x} \geq 5-x; 7+x \geq (5-x)^2;$$
$$x^2-11x+18 \leq 0; 2 \leq x \leq 9.$$

Để bắt lỗi, chúng tôi sử dụng điểm được gắn nhãn không có trong đáp số và thỏa mãn bất đẳng thức ban đầu, ví dụ $x=18$. Đã thay thế vào bất đẳng thức thứ hai cho thấy ngay bước đầu tiên, khi bình phương, chúng ta đã mất nghiệm.)

Vì vậy, khi nhận được đáp số, người ta thường nên “đi qua” toàn bộ trục số: có thể bỏ sót cả một khoảng; có thể trong đáp số bao gồm những con số rõ ràng không đạt yêu cầu. Đảm bảo thay thế các giá trị “lớn” và “nhỏ”: nó vừa đơn giản vừa hữu ích. Đặc biệt chú ý đến ranh giới của các khoảng thu được trong đáp số: theo quy luật, đây là ranh giới của khu vực định nghĩa bất bình đẳng hoặc các giá trị tại đó đạt được sự bình đẳng.

Một cách kiểm soát hiệu quả và trực quan thường là đồ họa. Nếu dễ dàng vẽ đồ thị cả hai vế của một bất đẳng thức, hãy làm điều đó!

4. Hình học bài toán

Việc kiểm tra đơn giản nhất của một công thức hình học dựa trên thực tế là cả hai phần phải có cùng chiều. Bạn chỉ có thể thêm số lượng có cùng thứ nguyên; trong trường hợp này tổng có cùng thứ nguyên với các số hạng. Thứ nguyên của tích bằng tổng các thứ nguyên của các thừa số, thứ nguyên của thương là hiệu giữa thứ nguyên của số bị chia và số chia. Hằng số được gán thứ nguyên 0, chiều dài được gán thứ nguyên 1. Diện tích và thể tích có thứ nguyên 2 và 3 tương ứng, và hàm lượng giác có thứ nguyên 0. Do các thuộc tính kích thước được liệt kê, không thể có những “công thức” như vậy:

$$l = \frac{a+b}{a-b}, \quad V = a^2 \cdot \frac{b}{a+c},$$
$$\sin \varphi = \frac{a^2+b^2}{S^2}, \quad S = a^2 + \frac{b}{c},$$

trong đó $l, S, V$ là độ dài, diện tích và thể tích, $a, b, c$ là độ dài. Trong ba công thức đầu tiên, kích thước của bên trái và bên phải không khớp nhau (một và 0, ba và hai, 0 và trừ hai); ở phía bên phải của công thức thứ tư, các giá trị của thứ nguyên 2 và 0 được thêm vào.

Việc sử dụng tính đối xứng để điều khiển cũng rất dễ dàng. Vấn đề là tính đối xứng trong các điều kiện bài toán phải được theo sau bởi tính đối xứng đáp số. Ví dụ: nếu trong bài toán cần tìm khoảng cách từ điểm tiếp tuyến ngoài của hai đường tròn có bán kính $a$ và $b$ đến tiếp tuyến chung của chúng, thì trong công thức tính khoảng cách loại trừ $a$ và $b$ phải bằng nhau, tức là công thức không được thay đổi do sự sắp xếp lại của chúng. Do đó, trong số ba đáp số:

$$x = \sqrt{a^2+2b^2}, \quad x = b \left( 1 + \frac{a-b}{a+b} \right),$$
$$x = \frac{2ab}{a+b}$$

điều đầu tiên rõ ràng là không phù hợp; bạn không thể nói ngay bất cứ điều gì về cái thứ hai - nó phải được chuyển sang dạng đối xứng, đó là dan trong công thức thứ ba.

Để thậm chí trước lời giải bài toán cần lưu ý rằng thể tích của một khối đa diện có đáy bằng nhau và các góc nhị diện ở đáy $\alpha, \beta, \gamma$ biểu thị hàm đối xứng của $\alpha, \beta, \gamma$

⟦folio 46⟧

(được định nghĩa ở chú thích ở trang 44) và trong công thức tính trung tuyến $m_c$ của một tam giác có cạnh $a, b, c$ chỉ $a$ và $b$ phải nhập theo cách tương tự (giải thích tại sao!).

Bạn có thể kiểm tra đáp số và xác nhận và xác nhận, ví dụ: trong bài toán đã cho về khoảng cách đến tiếp tuyến, kết quả ước lượng hình học: khoảng cách cần thiết bằng bán kính. Đây cũng là những gì công thức mang lại. Việc kiểm tra trong các trường hợp giới hạn, khi một trong các biến tiến tới ranh giới của miền định nghĩa, hầu như không cần tính toán. Trong bài toán được xem xét ở $a \rightarrow 0$ khoảng cách yêu cầu cũng có xu hướng về 0; công thức $x = ab/(a+b)$ cũng cho thấy điều tương tự.

Để kiểm tra bài toán bằng dữ liệu số, bạn cần tưởng tượng giá trị gần đúng của đáp số. Giả sử, nếu bạn muốn tìm độ dài phân giác $l_a$ của một tam giác có cạnh $a=7, b=6, c=5$, thì đáp số $\sqrt{50}$ và $3/\sqrt{7}$ là cái đầu tiên quá lớn và cái thứ hai quá nhỏ.

Để kết luận, chúng tôi xây dựng các kỹ thuật xác minh hoạt động chính mà chúng tôi đã sử dụng:

1. Thay thế các giá trị riêng tư
2. Nghiên cứu đóng cửa biên giới
3. Quan sát về tính đối xứng.
Hãy cố gắng làm chủ chúng. Để làm điều này, bạn được cung cấp hàng bài toán. Đối với mỗi cái có một số đáp số, trong đó chỉ có một cái được sửa. Tìm anh ấy.

1. Rút gọn biểu thức $3+4\cos 2a + \cos 4a$;
   a. $4\cos^4 a$. 6. $8\cos^3 a$. 8. $8\cos^4 a$. 8. $-6\cos^4 a$.
2. Giải phương trình $\sqrt{1+\log_2 x} + \sqrt{4\log_4 x-2} = 4$;

Sửa đổi

Trong bài “Sự dịch chuyển của không gian” («Kvant», 1980, số 8) trên tr. 7 - trong cách xây dựng Định lý 2 và ở đoạn cuối - do lỗi của tác giả, đã bỏ sót một chuyển động: thành phần phép quay quanh một đường thẳng và tính đối xứng đối với một mặt phẳng vuông góc với đường thẳng này.
