---
id: 1981-1-egorov-pokazatelnyie-uravneniya-7d633aaf
issue: kvant_1981_1
year: 1981
number: "1"
title: phương trình hàm mũ
authors:
  - Егоров А. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 42
page_last: 44
page_labels: 40-42
tag: O5SA
lang: vi
source: kvant_digital
extraction: vision
content_sha256: fa989ba0b7b4fc825790de4ea949304adf9d4d1f51aa65290d3e7878f3c0331e
prompt_sha256: draft-1
translated_from: content/ru/1981/01/articles/13_egorov-pokazatelnyie-uravneniya-7d633aaf.md
source_content_sha256: fdaf09c12e47c00d3b3e3cbca7992b324b2eff3b168fa7e7d63aa73ecd77b825
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 40⟧

phương trình hàm mũ

Chủ đề của bài viết này là một phương trình chứa ẩn số trong số mũ. Những phương trình như vậy thường gặp trong các kỳ thi nâng cao và do đó, việc thí sinh làm quen với một số phương pháp lời giải của chúng sẽ rất hữu ích.

Phương trình hàm mũ đơn giản nhất là phương trình có dạng $a^x = b$, trong đó $a > 0, a \neq 1$. Đối với $b > 0$ phương trình này có một nghiệm duy nhất $x = \log_a b$, đối với $b \leq 0$ phương trình không có nghiệm.

Khi biến đổi phương trình hàm mũ, các tính chất của hàm mũ thường được sử dụng (xem cẩm nang “Đại số và Phân tích cơ bản 10”, đoạn 108): $a^{x_1} \cdot a^{x_2} = a^{x_1 + x_2}, (a^{x_1})^{x_2} = a^{x_1 x_2}, (ab)^x = a^x \cdot b^x$ (tại đây $a > 0, b > 0$).

Nếu phương trình ban đầu có dạng

$$f(a^x) = b,$$

(1)

trong đó $f$ là một hàm nhất định, thì đối với lời giải của nó, chúng ta có thể đặt $y = a^x$, giải phương trình $f(y) = b$, chọn nghiệm dương của nó rồi giải phương trình đơn giản nhất thu được.

Bài toán 1 (MIIGAiK, 1978). Giải phương trình

$$3^{2-x} = 3^x - 8.$$

Lời giải. Đặt $y = 3^x$, ta được phương trình $\frac{9}{y} = y - 8$ hoặc $y^2 - 8y - 9 = 0$. Phương trình bậc hai thu được có nghiệm

$$y_1 = -1, y_2 = 9.$$

Cái đầu tiên KHÔNG ĐẶT THƯỜNG chúng ta ($y > 0$). Do đó $3^x = 9$, do đó $x = 2$.

Đáp số. {2}.

Trong một số trường hợp, một phương trình không có dạng (1) có thể được chuyển đổi sang dạng này bằng cách sử dụng tính chất của hàm mũ.

Bài toán 2 (MII, 1976). Giải phương trình

$$3 \cdot 16^x + 2 \cdot 81^x = 5 \cdot 36^x.$$

Lời giải. Sau khi biến đổi rõ ràng, chúng tôi nhận được:

$$3 \cdot 4^{2x} + 2 \cdot 9^{2x} = 5 \cdot 4^x \cdot 9^x.$$

Vì $9^x \neq 0$ nên phương trình thu được tương đương với phương trình

$$3 \cdot \left(\frac{4}{9}\right)^{2x} + 2 = 5 \cdot \left(\frac{4}{9}\right)^x.$$

Bỏ phiếu $y = \left(\frac{4}{9}\right)^x$, chúng ta đi đến phương trình bậc hai $3y^2 - 5y + 2 = 0$. Gốc của nó là $y_1 = 1, y_2 = \frac{2}{3}$.

Giải phương trình đơn giản nhất $\left(\frac{4}{9}\right)^x = 1$ và $\left(\frac{4}{9}\right)^x = \frac{2}{3}$, chúng ta thu được trong trường hợp đầu tiên $x = 0$, và trong trường hợp thứ hai $\left(\frac{2}{3}\right)^{2x} = \frac{2}{3}$; nghĩa là $2x = 1$ hoặc $x = \frac{1}{2}$.

Đáp số. {0, 1/2}.

Bây giờ chúng ta hãy xem xét một số ví dụ trong đó số mũ hóa ra là các hàm phi octor của $x$.

Bài toán 3 (MIIGAiK, 1970). Giải phương trình

$$3^{2x^2 + 6x - 9} + 4 \cdot 15^{x^2 + 3x - 5} = 3 \cdot 5^{2x^2 + 6x - 9}$$

Lời giải. Chúng ta đặt $y = x^2 + 3x - 5$, sau đó phương trình sẽ được sắp xếp lại như sau:

$$3^{2y+1} + 4 \cdot 3^y \cdot 5^y = 3 \cdot 5^{2y+1}.$$

Tách vế phải và vế trái bằng $5^{2y}$, ta thu được phương trình

$$3 \cdot \left(\frac{3}{5}\right)^{2y} + 4 \cdot \left(\frac{3}{5}\right)^y - 15 = 0.$$

Giải phương trình này như phương trình trước, ta thu được $\left(\frac{3}{5}\right)^y = \frac{5}{3}$, từ đó

⟦folio 41⟧

$$y = -1. \text{ Осталось решить квадратное уравнение } x^2 + 3x - 5 = -1.$$

Đáp số. {1, -4}.

Đôi khi, sau khi biến đổi, phương trình ban đầu được rút gọn về dạng
$$a^{f(x)} = b^{g(x)}
(a > 0, b > 0, a \neq 1).$$

Đối với lời giải phương trình này, cần lưu ý rằng nó tương đương với phương trình
$$a^{f(x)} = a^{g(x)} \log_a b$$
(chúng tôi đã sử dụng alogab lý thuyết logarit cơ bản = b). Từ tính đơn điệu của hàm số mũ, suy ra phương trình (2) tương đương với phương trình
$$f(x) = g(x) \log_a b.$$

Bài toán 4. Giải phương trình
$$3^{x-3} = 5^{x^2 - 7x + 12}.$$
Lời giải. Hãy chuyển sang phương trình tương đương
$$x - 3 = (x^2 - 7x + 12) \log_3 5.$$
Tất nhiên, phương trình thu được có thể được giải theo cách thông thường (đây là phương trình bậc hai). Nhưng việc giải nó khá bất tiện vì nó có những hệ số “kinh tởm”.

Tuy nhiên, nếu bạn nhận thấy rằng $x^2 - 7x + 12 = (x - 3)(x - 4)$, lời giải sẽ đơn giản hóa đáng kể.

Chúng ta có $x - 3 = (x - 3)(x - 4) \log_3 5$, từ đó $x = 3$, hoặc $(x - 4) \times \log_3 5 = 1$ hoặc $x = 4 + \frac{1}{\log_3 5} = 4 + \log_5 3.$

Đáp số. {3, 4 + \log_5 3}.

Hãy xem xét một ví dụ nữa.

Bài toán 5 (Miệt, 1978). Giải phương trình
$$32^{\frac{x+5}{x-7}} = 0,25 \cdot 128^{\frac{x+17}{x-3}}.$$
$$32 = 2^5, 0,25 = 2^{-2}, 128 = 2^7$$, nên phương trình được viết lại thành:
$$2^{5 \cdot \frac{x+5}{x-7}} = 2^7 \cdot \frac{x+17}{x-3} - 2$$
và do đó tương đương với phương trình
$$\frac{5x+25}{x-7} = \frac{7x+119}{x-3} - 2,$$

làm giảm phương trình
$$\frac{x+5}{x-7} = \frac{x+25}{x-3},$$
có gốc $x = 10$.

Đáp số. {10}.

Đôi khi bạn gặp một phương trình chứa ẩn số ở cả cơ số và số mũ. Trước khi chuyển sang xem xét bài toán cụ thể, chúng ta hãy đưa ra một số nhận xét về miền định nghĩa các hàm có dạng $f(x)^{g(x)}$.

Rõ ràng, khi một bài kiểm tra cung cấp bài toán, trong đó hàm có dạng $f(x)^{g(x)}$, người ta giả định rằng người đăng ký sẽ xem xét bài kiểm tra đó với các giá trị $x$ đáp ứng một trong các điều kiện: $f(x) > 0$ hoặc $f(x) = 0$ và $g(x) > 0$.

Vì vậy, $x = 3$ là nghiệm của phương trình $(x - 3)^x = 3 - x$. Với $x > 3$ phương trình này hiển nhiên không có nghiệm (vế trái là dương và vế phải là âm). Đối với $x < 3$ cơ số của bậc là âm và do đó, $x'$ như vậy không nên được xem xét, mặc dù có thể lưu ý rằng việc thay thế trực tiếp $x = 2$ vào phương trình sẽ mang lại đẳng thức đúng $(2 - 3)^2 = 3 - 2$ và do đó số 2 cũng là nghiệm của nó.

Những người nộp đơn không thay thế điều này và không xem xét trường hợp $x < 3$ hoàn toàn không phạm bất kỳ sai sót nào và đáp số $x = 3$ trong bài toán này nên được coi là đúng.

Thỏa thuận được chấp nhận là do câu hỏi về ý nghĩa của biểu thức $a^b$ với $a < 0$ và số thực $b$, không phải là số nguyên, rất phức tạp và không thể giải quyết trong khuôn khổ một khóa học quy mô trung bình.

Bài toán 6. Giải phương trình
$$x^{x^2 - 5x + 8} = x^2.$$
Lời giải. Chúng tôi chỉ xem xét $x \ge 0$. Vì tại $x = 0$ hàm số ở vế trái được xác định và bằng 0 và vế phải bằng 0, nên 0 là nghiệm của phương trình này. Dễ dàng nhận thấy rằng đối với $x > 0$ phương trình này tương đương với phương trình $(x^2 - 5x + 8) \lg x = 2 \lg x$, do đó $\lg x = 0$, tức là $x = 1$, hoặc $x^2 - 5x + 6 = 0$, nghĩa là, $x = 2$ và $x = 3$.

⟦folio 42⟧

Đáp số. {0, 1, 2, 3}.

Để kết thúc phần này, chúng ta xem xét hai bài toán, có thể được giải bằng tính chất đơn điệu của số mũ của hàm.

Bài toán 7. Giải phương trình

$$3 \cdot 4^x + (3x - 10) \cdot 2^x + 3 - x = 0.$$

Lời giải. bài toán này không thuộc bất kỳ loại nào đã thảo luận trước đó. Tuy nhiên, chúng ta hãy thử thay thế $y = 2^x$. chúng tôi nhận được

$$3 \cdot y^2 + (3x - 10)y + 3 - x = 0.$$

Bây giờ chúng ta hãy giải phương trình thu được dưới dạng bậc hai đối với $y$. chúng tôi có

$$y = \frac{-3x + 10 \pm \sqrt{(3x - 10)^2 - 12(3 - x)}}{6}$$

$$= \frac{-3x + 10 \pm \sqrt{9x^2 - 48x + 64}}{6}$$

$$= \frac{-3x + 10 \pm (3x - 8)}{6},$$

từ đâu $y = 3 - x$ hoặc $y = \frac{1}{3}$.

Phương trình $2^x = \frac{1}{3}$ có nghiệm $x = -\log_2 3$.

Bây giờ chúng ta giải phương trình

$$2^x = 3 - x.$$

Thật dễ dàng để đoán gốc $x = 1$. Hãy chứng minh rằng phương trình này không có nghiệm nào khác. Thật vậy, với $x = 1$ vế trái bằng vế phải. Vế trái là hàm tăng, vế phải là hàm giảm. Do đó, với $x < 1$ bên trái sẽ nhỏ hơn bên phải và với $x > 1$ thì ngược lại, bên phải sẽ lớn hơn bên trái.

Đáp số. {1, $-\log_2 3$}.

Bài toán 8. Giải phương trình

$$6^x - 2^x = 32.$$

Lời giải. Những nỗ lực tìm nghiệm của phương trình này bằng các phương pháp thông thường không mang lại kết quả gì. Đồng thời dễ dàng nhận thấy phương trình thỏa mãn giá trị $x = 2$. Hãy chứng minh rằng không có nghiệm nào khác. Để làm điều này, chúng tôi sắp xếp lại phương trình như thế này:

$$3^x - 1 = \frac{32}{2^x}.$$

Bên phải đang giảm dần
