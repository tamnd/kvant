---
id: 1981-9-kreyn-nudelman-zamechatelnyie-predelyi-porozhdaemyie-klassicheskimi-srednimi-28b6d301
issue: kvant_1981_9
year: 1981
number: "9"
title: Các giới hạn đáng chú ý được tạo ra bởi mức trung bình cổ điển
authors:
  - Крейн М. Г.
  - Нудельман А. А.
rubric: osnovnye-stati
page_first: 15
page_last: 16
page_labels: 13-14
tag: UQWU
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 4191bb7236ad5b87828587d3451c57abea6f5c6bc9024ff8d3c036f73a4f4ac7
prompt_sha256: draft-1
translated_from: content/ru/1981/09/articles/07_kreyn-nudelman-zamechatelnyie-predelyi-porozhdaemyie-klassicheskimi-srednimi-28b6d301.md
source_content_sha256: ec705c66a1716c888516b689b15b093d9c259f8e7f7158bc89e756876cd0a9d2
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 13⟧

Hình nền tuyệt vời được tạo ra bởi mức trung bình cổ điển

Đối với hai số dương $a$ và $b$, như đã biết, số $\frac{a+b}{2}$ được gọi là trung bình số học và số $\sqrt{ab}$ được gọi là trung bình hình học. Ít phổ biến hơn những mức trung bình này là mức trung bình hài hòa $\frac{2ab}{a+b}$ (ví dụ: nó bằng tốc độ trung bình của một xạ thủ máy đã đi nửa đầu hành trình với tốc độ $a$, nửa sau với tốc độ $b$). Mỗi mức trung bình này nằm giữa các số $a$ và $b$ (hãy đảm bảo điều này).

Tính đúng đắn của đẳng thức của cô ấy được xác minh dễ dàng

$$\frac{2ab}{a+b} < \sqrt{ab} < \frac{a+b}{2}$$

đối với bất kỳ số dương nào $a \neq b^*$.

Chúng ta sẽ giải quyết câu hỏi tiếp theo ở đây. Gọi hai số dương đã cho là $a$ và $b$, $a < b$. Sau khi tính một số cặp trung bình của những số này, chúng ta thu được các số $a_1$ và $b_1$. Sau đó, đối với các số $a_1$ và $b_1$, chúng tôi tính toán mức trung bình giống nhau - chúng tôi nhận được các số $a_2$ và $b_2$. Chúng tôi sẽ lặp lại quy trình tương tự với họ, v.v. Kết quả là chúng ta thu được các chuỗi $(a_n)$ và $(b_n)$.

Ví dụ: lấy trung bình hình học và trung bình số học và bắt đầu từ số 1 và 3, chúng ta có được

$$a_1 = \sqrt{3} \approx 1.732050808, \quad b_1 = 2;$$
$$a_2 \approx 1.861209718, \quad b_2 \approx 1.866025404;$$
$$a_3 \approx 1.863616006, \quad b_3 \approx 1.863617561;$$
$$a_4 \approx 1.863616784, \quad b_4 \approx 1.863616784;$$
vân vân.

Chúng ta thấy rằng trong ví dụ của mình, các chuỗi $(a_n)$ và $(b_n)$ hội tụ rất nhanh. Nó sẽ luôn như thế này phải không? Hóa ra những dãy số như vậy luôn có một giới hạn chung - điều này tương đối dễ chứng minh. Nhưng làm thế nào để tìm được giá trị của giới hạn này?

Trung bình số học-điều hòa

Chúng ta sẽ bắt đầu với trường hợp cặp trung bình được chọn là trung bình điều hòa và trung bình số học; do đó, số hạng của dãy $(a_n)$ và $(b_n)$ được xác định bởi công thức

$$a_{n+1} = \frac{2a_nb_n}{a_n+b_n}, \quad b_{n+1} = \frac{a_n+b_n}{2}$$

($n=0, 1, 2, \dots; a_0=a, b_0=b$).

Bài toán về việc tìm ra giới hạn chung của mình được trình bày tại Olympic đồng đội II do trường thành phố Omsk («Kvant», 1979, số 12).

Từ bất đẳng thức (1) suy ra

$$a < a_n < a_{n+1} < b_{n+1} < b_n$$

nghĩa là, chuỗi $(a_n)$ trả về “hướng tới” chuỗi tiêu diệt $(b_n)$.

Vì vậy, cả hai chuỗi đều đơn điệu và bị giới hạn; do đó, theo định lý Weierstrass (Đại số và Nguyên tắc Phân tích 9, đoạn 32) chúng có giới hạn $\alpha = \lim_{n \to \infty} a_n, \beta = \lim_{n \to \infty} b_n$. Chuyển đến giới hạn của một trong các đẳng thức (2), ta thu được

$$\beta = \lim_{n \to \infty} b_{n+1} = \lim_{n \to \infty} \frac{a_n+b_n}{2} =$$
$$= \frac{1}{2} \left( \lim_{n \to \infty} a_n + \lim_{n \to \infty} b_n \right) = \frac{1}{2} (\alpha + \beta),$$

từ đâu $\alpha = \beta$: các dãy $(a_n)$, $(b_n)$ có ​​giới hạn chung. Giới hạn này được gọi là trung bình cộng số học điều hòa của các số $a$ và $b$. Hãy tìm anh ấy. Từ (2)

⟦folio 14⟧

$$a_{n+1} \cdot b_{n+1} = a_n \cdot b_n = \ldots = a_1 b_1 = ab,$$
bởi vì
$$a^2 = \left( \lim_{n \to \infty} a_n \right)^2 = \lim_{n \to \infty} a_n \times \lim_{n \to \infty} a_n = \lim_{n \to \infty} a_n \times b_n = ab,$$
Ở đâu
$$\alpha = \sqrt{ab} = \beta,$$
(trung bình số học-Garyonic trùng với trung bình hình học).

Bài tập 1. Chứng minh rằng $b_n - a_n < \frac{b-a}{2^n}$.

Vì vậy các trình tự $(a_n)$ Và $(b_n)$ hội tụ đủ nhanh để $\sqrt{ab}$. Vì vậy, chúng có thể hữu ích trong việc tính gần đúng căn bậc hai. Để tính toán $\sqrt{c}$ cần trình tự bắt đầu $(a_n)$, $(b_n)$ từ những con số như vậy $a$ Và $b$, Cái gì $c = ab$ (Ví dụ, $a = 1, b = c$), và quá trình sẽ hội tụ nhanh hơn, sự khác biệt giữa các hệ số này càng nhỏ (ví dụ: để tính $\sqrt{56}$ tốt hơn là không nên $a = 1$, $b = 56$, MỘT $a = 7$, $b = 8$). Thật dễ dàng để xác minh rằng các chuỗi $(a_n)$ Và $(b_n)$ thu được bằng công thức
$$b_{n+1} = \frac{1}{2} \left( b_n + \frac{c}{b_n} \right), a_{n+1} = \frac{c}{b_n}.$$
Để minh họa cách tính $\sqrt{12}$, hãy đặt $b = 4$. Chúng tôi nhận được $b_1 = \frac{1}{2} \left( 4 + \frac{12}{4} \right) = 3,5$, $b_2 \approx 3,464285715$, $b_3 \approx 3,464101620$, $b_4 \approx 3,464101615$ và sau đó tất cả các dấu hiệu đều ổn định:
$$\sqrt{12} \approx 3,464101615.$$

Trung bình số học-hình học Carl Friedrich Gauss, 14 tuổi*) đã phát hiện từ các ví dụ số rằng khi tính chuỗi $(a_n)$ và $(b_n)$ sử dụng trung bình hình học và số học:
$$a_{n+1} = \sqrt{a_n b_n}, b_{n+1} = \frac{a_n + b_n}{2}$$

($n = 0, 1, 2, \ldots; a_0 = a, b_0 = b$) các chuỗi này hội tụ rất nhanh với các chuỗi gần nhất.

*) Người đọc sẽ tìm thấy tiểu sử của “Vua toán học” và những thông tin thú vị về hoạt động khoa học của ông trong bài viết của S. Gindikn “Carl Friedrich Gauss” («Kvant», 1977, số 8).

Bài tập 2. Chứng minh sự tồn tại và trùng hợp của các giới hạn của dãy (3).

Giới hạn chung này được gọi là trung bình cộng hình học số học của các số $a$ và $b$ và được ký hiệu là $\mu(a, b)$. Việc tìm một biểu thức rõ ràng cho $\mu(a, b)$ thông qua $a$ và $b$ không phải là điều dễ dàng. nó lần đầu tiên được Gauss thu được nhờ sự phân tích và biến đổi cực kỳ sắc nét và thuần thục bằng cách sử dụng các đặc tính của cái gọi là các mục tiêu eliptic. Hãy để chúng tôi trình bày biểu thức này mà không cần chứng minh*):

$$\mu(a, b) = \frac{\pi}{2} \int_0^{\pi/2} \frac{dx}{\sqrt{a^2 \sin^2 x + b^2 \cos^2 x}}.$$

Trung bình hình học-Gharionch

Nếu chúng ta xây dựng các chuỗi $(a_n)$ và $(b_n)$ bằng cách sử dụng các phương tiện ngữ pháp và hình học:
$$a_{n+1} = \frac{2a_n b_n}{a_n + b_n}, b_{n+1} = \sqrt{a_n b_n}$$

($n = 0, 1, 2, \ldots; a_0 = a, b_0 = b$),

thì trong trường hợp này dễ dàng chứng minh được rằng chúng hội tụ về một giới hạn chung. Hãy gọi nó là số Garyonic hình học của $a$ và $b$ và biểu thị nó bằng $\nu(a, b)$. Tuy nhiên, ở đây không có gì đáng kể khi so sánh với các chuỗi (3), vì từ (4) chúng ta thấy rằng
$$\frac{1}{a_{n+1}} = \frac{1}{a_n} + \frac{1}{b_n}, \frac{1}{b_{n+1}} = \sqrt{\frac{1}{a_n} \cdot \frac{1}{b_n}}.$$
Bởi vì
$$\frac{1}{\nu(a, b)} = \mu\left(\frac{1}{b}, \frac{1}{a}\right),$$
hoặc, nhờ công thức Gaus.

*) Nếu biểu thức này được sử dụng “theo hướng ngược lại”, chúng ta có một cách nhanh chóng để tính gần đúng phép tính tích phân ở mẫu số: nó bằng $\frac{\pi}{2\mu(a, b)}$ và trung bình $\mu(a, b)$ được tính gần đúng bằng cách sử dụng các chuỗi $(a_n)$ và $(b_n)$. Trong thời đại máy tính của chúng ta, những phép tính này có thể được thực hiện với tốc độ và độ chính xác cao.
