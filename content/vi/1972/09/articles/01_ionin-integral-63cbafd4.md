---
id: 1972-9-ionin-integral-63cbafd4
issue: kvant_1972_9
year: 1972
number: "9"
title: tích phân
authors:
  - Ионин Ю. И.
rubric: osnovnye-stati
page_first: 4
page_last: 8
page_labels: 2, 4, 6
tag: K3ES
lang: vi
source: kvant_digital
extraction: vision
content_sha256: b890d883fa38873bb3062aa50ff2954146811550c5cb9cc7964ee0baec45fa7a
prompt_sha256: draft-1
translated_from: content/ru/1972/09/articles/01_ionin-integral-63cbafd4.md
source_content_sha256: cb79b150ef03a4306d0004a5d40d211d856c7c2ac9bff257c1c58f708e6ceb74
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

Bài viết này nói về một trong những khái niệm toán học quan trọng nhất - tích phân. Sử dụng khái niệm này, người ta có thể giải được nhiều bài toán hình học và vật lý bài toán.

Lưu ý rằng theo chương trình mới, phép tính tích phân sẽ được học ở bậc trung học.

Bạn có thể tìm hiểu thêm về phép tính tích phân trong cuốn sách của B. E. Weizza, I. T. Demidav “Đại số và sự khởi đầu của phân tích” (sách giáo khoa thử nghiệm lớp 10, do viện sĩ A. N. Kolmogorov biên tập). Tuy nhiên, nó được trình bày dưới nhiều góc độ.

Khi bạn gặp khái niệm hàm số cho đến nay, người ta thường gợi ý rằng miền của hàm bao gồm các số.

Ví dụ: hàm $x \rightarrow \frac{\sqrt{x+2}}{x-3}$ được xác định trên tập hợp các số thỏa mãn $x \geq -2$ và $x \neq 3$ và hàm $x \rightarrow \sqrt{1g\cos 2\pi x}$ được xác định trên tập hợp các số nguyên.

Tuy nhiên, không kém phần quan trọng là các hàm có miền định nghĩa không phải là các số mà là một tập hợp nằm trên một đường thẳng, trong mặt phẳng hoặc trong không gian. Ví dụ, diện tích có thể được coi là một hàm được xác định trên một tập hợp các hàm số phẳng. Hàm này gán số $ab$ cho đường tròn bán kính $a$ và $b$, và số $\pi R^2$ cho đường tròn bán kính $R$. Nếu cho trước định luật chuyển động nào đó của một điểm thì chúng ta có thể xem xét một hàm liên kết từng khoảng thời gian với đường đi trong khoảng thời gian đó; miền định nghĩa của hàm này bao gồm các khoảng thời gian.

Có thể nói cả hai hàm số được xem xét đều có tính chất quảng cáo (từ tiếng Latinh addo - tôi thêm): nếu một hàm số được chia thành nhiều phần thì diện tích của nó bằng tổng diện tích của các phần đó; nếu một khoảng thời gian được chia thành nhiều phần thì tổng số đường đi được của mỗi phần này sẽ bằng tổng số đường đi được trong toàn bộ khoảng thời gian đó.

Vật lý cung cấp nhiều ví dụ về hàm cộng.

Nếu chuyển động của một điểm vật chất được cho trước, xảy ra dưới tác dụng của một lực nhất định, thì có thể gán cho mỗi đoạn của quỹ đạo một sự tương ứng với công của lực di chuyển điểm được thực hiện trên đoạn đó. Đây là một chức năng bổ sung.

Khối lượng, năng lượng, năng lượng cơ thể cũng là những hàm phụ *).

Nghiên cứu hàm cộng dựa trên thành công của các nhà khoa học vĩ đại thế kỷ 17-18, trước hết

*) Độ bám dính của khối lượng đã được Ya trình bày chi tiết trong bài viết. A. Smorodinsky trong «Kvant» số 3, 1972.

⟦folio 4⟧

Hình 2.

khối lượng được phân bố “gần như đồng đều”, nói cách khác, mật độ của thanh tại các điểm của mỗi đoạn như vậy sẽ khác rất ít so với mật độ trung bình của thanh trên đoạn đó.

Mật độ trung bình của thanh trên đoạn $[a, b]$ bằng $\frac{m[a, b]}{b-a}$. Một khái niệm tương tự rất dễ được đưa ra cho hàm khoảng tùy ý. Mật độ trung bình của hàm khoảng $T$ trên đoạn $[a, b]$ (tại $a \neq b$) là số $\frac{T[a, b]}{b-a}$.

Việc đưa ra định nghĩa về mật độ “tại một điểm” sẽ khó khăn hơn nhiều và chúng tôi cũng sẽ không đưa ra nó ở đây vì chúng tôi sẽ chỉ cần một tính chất của mật độ “điểm” này. Để xây dựng tính chất này, thuận tiện là đưa ra một số ký hiệu. Nếu đoạn $[a, b]$ nằm trong miền định nghĩa của hàm số $f$, thì bằng các ký hiệu $\min f$ và $\max f$, chúng ta sẽ lần lượt biểu thị giá trị nhỏ nhất và lớn nhất của hàm $f$ trên đoạn này. Điều thực sự thú vị về mật độ là như sau. Nếu hàm số $f$ là mật độ của hàm khoảng $T$ thì mật độ trung bình của hàm khoảng $T$ trên mỗi đoạn $[a, b]$ được chứa giữa các số $\min f$ và $\max f$ (Hình 2), tức là bất đẳng thức được thỏa mãn

$$\min f \leqslant \frac{T[a, b]}{b-a} \leqslant \max f,$$

(3)

có thể được viết lại như thế này:

$$(b-a) \min f \leqslant T[a, b] \leqslant \leqslant (b-a) \max f.$$

Giả sử rằng đối với một hàm cho trước của số $f$, chúng ta đã chọn được một hàm cộng như vậy của khoảng $T$ mà bất đẳng thức (3) được thỏa mãn trên mỗi phân đoạn từ miền định nghĩa của hàm $T$. Tuy nhiên, hàm khoảng $T$ có được xác định bởi điều này không? Người ta có thể nghĩ về một ví dụ về hàm số “xấu” $f$, trong đó hàm cộng của khoảng $T$ không được xác định duy nhất bởi các bất đẳng thức (3). Tuy nhiên, một ví dụ được đưa ra trong Bài tập 4. Nhưng đối với bất kỳ hàm đủ “tốt” $f$, chẳng hạn, đối với bất kỳ hàm đa âm nào, chỉ có một hàm cộng của khoảng $T$, các giá trị của nó trên mỗi khoảng $[a, b]$ thỏa mãn bất đẳng thức (3). Tuyên bố tương tự cũng đúng đối với các hàm đơn điệu từng phần $f$, tức là đối với một hàm có tính đơn điệu trên các phân đoạn. Đơn điệu từng phần là lũy thừa, hàm mũ, logarit, lượng giác và nhiều hàm khác.

Chúng ta đã đi đến định nghĩa của tích phân.

Sự định nghĩa. Giả sử hàm của số $f$ được xác định trên khoảng $[A, B]$. Hàm cộng của khoảng $T$, xác định trên tập các đoạn $[a, b]$ chứa trong đoạn $[A, B]$, được gọi là tích phân của hàm $f$, nếu với mỗi đoạn $[a, b]$ bất đẳng thức

$$(b-a) \min f \leqslant T[a, b] \leqslant \leqslant (b-a) \max f.$$

Do đó, tích phân của hàm số là hàm cộng của khoảng $T$ được xác định duy nhất.

⟦folio 6⟧

giữa này là 0,333. Chúng ta sẽ tìm thấy mục đích chính xác của nội dung này trong đoạn tiếp theo. Như bạn có thể đã đồng ý, nó bằng $1/3$.

Và trong trường hợp tổng quát hơn, có thể bằng cách chia đoạn $[a, b]$ thành các phần đủ nhỏ để xấp xỉ $\int \limits_a^b f(x) dx$ với tổng có dạng
$$f(x_1)(a_1 - a) + f(x_2)(a_2 - a_1) + \dots + f(x_n)(b - a_{n-1})$$
trong đó $a_1, a_2, \dots, a_{n-1}$ là các điểm chia đoạn $[a, b]$ thành các phần, $x_1, x_2, \dots, x_n$ là các điểm từ các phần này. Sự gần đúng này có thể được thực hiện chính xác như mong muốn.

Số tiền được viết ở trên được gọi là nội bộ. Rõ ràng, theo định nghĩa, một khoảng thời gian là giới hạn mà tổng giữa các khoảng có xu hướng khi phân vùng ngày càng trở nên mịn hơn. Trong định nghĩa của chúng ta về khoảng, khái niệm giới hạn không được sử dụng. Từ các khoản tiền nội bộ, việc chỉ định các nội bộ cũng được bắt nguồn. Ký hiệu $\int \limits_a^b f(x) dx$ có dạng như sau: “interral from a to be ef from x to de x.” Hàm $f$ được gọi là subinterral, các số $a$ và $b$ lần lượt là giới hạn dưới và giới hạn trên của nội hóa. Cần lưu ý rằng giống như $x \rightarrow x^2, t \rightarrow t^2, z \rightarrow z^2$ là cùng một hàm, các ký hiệu $\int \limits_a^b f(x) dx, \int \limits_a^b f(t) dt, \int \limits_a^b f(z) dz$ biểu thị cùng một số - giá trị khoảng của hàm $f$ trên đoạn $[a, b]$.

§ 4. Công thức tích phân

Tính toán các khoảng bằng cách sử dụng tổng giữa các khoảng là một công việc khá rắc rối và kết quả chỉ mang tính gần đúng. Thay vào đó, họ làm điều này: họ tính toán một số khoảng thời gian tiêu chuẩn, thường gặp và cố gắng giảm các khoảng thời gian khác cho chúng. Chúng ta sẽ tính hai khoảng chuẩn

$$\int \limits_a^b x_n dx \quad \int \limits_a^b \cos x dx \quad \text{и установим некоторые теоремы, позволяющие своить ряд интерралов к стандартным.}$$

Tính toán 1° $\int \limits_a^b x^n dx$.

Xét hàm khoảng $T$ cho bởi công thức
$$T[a, b] = \frac{b^{n+1} - a^{n+1}}{n+1}.$$

Chức năng này là phụ gia:
$$T[a, b] + T[b, c] = \frac{b^{n+1} - a^{n+1}}{n+1} + \frac{c^{n+1} - b^{n+1}}{n+1} = \frac{c^{n+1} - a^{n+1}}{n+1} = T[a, c].$$

Hãy chứng minh rằng $T$ là tích phân của hàm số $x \rightarrow x^n$. Để làm điều này, chúng ta cần chứng minh rằng trên mỗi phân đoạn $[a, b]$ có ​​bất đẳng thức $(b - a) \min x^n \leq T[a, b] \leq (b - a) \max x^n$. Chúng ta hãy kiểm tra bất đẳng thức này cho $a$ và $b$ không âm. Trong trường hợp này $\min x^n = a^n$, $\max x^n = b^n$, vậy ta cần chứng minh
$$(b - a) a^n \leq \frac{b^{n+1} - a^{n+1}}{n+1} \leq b^n (b - a)$$
hoặc
$$(n + 1) a^n (b - a) \leq b^{n+1} - a^{n+1} \leq (n + 1) b^n (b - a).$$

Khai triển $b^{n+1} - a^{n+1}$ thành một tập hợp và triệt tiêu $b - a > 0$, bất đẳng thức cuối cùng có thể được viết lại thành
$$a^n + a^n + \dots + a^n \leq b^n + b^n + \dots + b^n.$$

Bất đẳng thức này đúng vì các số hạng ở phần giữa của nó không nhỏ hơn các số hạng ở vế trái và không lớn hơn các số hạng ở vế phải.

Do đó, hàm cộng của khoảng $T$ là tích phân.
