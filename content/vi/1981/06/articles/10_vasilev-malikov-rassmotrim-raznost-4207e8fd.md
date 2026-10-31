---
id: 1981-6-vasilev-malikov-rassmotrim-raznost-4207e8fd
issue: kvant_1981_6
year: 1981
number: "6"
title: Hãy xem xét sự khác biệt
authors:
  - Васильев Н. Б.
  - Маликов Т. С.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 29
page_last: 32
page_labels: 27, 29, 30
tag: KKJ5
lang: vi
source: kvant_digital
extraction: vision
content_sha256: dbb1c5942f9264f8713b2c08883f574ac4a8020fbab778b9cd6f4941e1e8b34e
prompt_sha256: draft-1
translated_from: content/ru/1981/06/articles/10_vasilev-malikov-rassmotrim-raznost-4207e8fd.md
source_content_sha256: d075b5209c26faafbb4981f49f97c1a39f66bf003adec84e49969af97569f606
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 27⟧

Hãy xem xét sự khác biệt

Thật khó để tìm thấy một tập hợp Olympid hoặc đại số bài toán trong đó các bài toán thuộc loại này không xuất hiện: để chứng minh rằng với mọi n tự nhiên

a) $7^{2n} - 5^{2n}$ chia hết cho 24;
b) $n^3 - n$ chia hết cho 6;
c) $\frac{n^5 - 5n^3 + 4n}{120}$ số nguyên;
d) $3^{2n+3} + 40n - 27$ chia hết cho 64;
e) $2^{2n-1} - 9n^2 + 21n - 14$ chia hết cho 27;
f) $5^n(5^n + 1) - 6^n(3^n + 2^n)$ chia hết cho 91;
g) $\frac{n^5}{5} + \frac{n^3}{3} + \frac{7n}{15}$ số nguyên.

Hãy thử giải những bài toán này. Bạn có thể sẽ thấy nhiều thông báo khác nhau như sau:
tại bài toán
a) lợi dụng thực tế là $7^2 - 5^2 = 24$ và cùng dấu
$$a^n - b^n = (1) = (a - b)(a^{n-1} + a^{n-2}b + \ldots + b^{n-1})$$,
chứng tỏ rằng $a^n - b^n$ luôn chia hết cho $a - b$;
b) khai triển đa thức ở tử số thành năm thừa số $(n-2)(n-1)n(n+1)(n+2)$ và thay gót của các số liên tiếp bằng một số chia hết cho 3, một cho 5, một cho 4 và một thừa số chia hết cho 2 (và không chia hết cho 4);

e) biểu thị hiệu bằng $(25^n - 18^n) - (12^n - 5^n)$ và $(25^n - 12^n) - (18^n - 5^n)$ để chứng minh khả năng chia hết của nó cho 7 và 13;
g) chứng minh riêng tính chia hết của $5n^3 + 7n$ cho 3 và tính chia hết của $3n^5 + 7n$ cho 5.

Không làm mất đi vẻ đẹp và sự hữu ích của những điều kỳ diệu này cũng như những kỳ quan tương tự khác, chúng tôi muốn hiểu một công thức chung cho tất cả những điều bài toán đó.

Chúng ta sẽ thấy rằng chỉ cần kiểm tra tính hợp lệ của từng câu a) - g) đối với một số nhỏ các giá trị đầu tiên của n (trong bài toán a) cho hai, d) cho ba, v.v.) để chắc chắn về tính hợp lệ của chúng đối với tất cả n.

Và người đọc hiểu đủ kỹ về ghi chú sẽ có thể tạo bài toán mới với số lượng không giới hạn (ngay cả những trường hợp xảy ra số vô tỷ):

3) số $45^n + (-44)^n - 1$ chia hết cho 1980;
i) số $[(6 + \sqrt{31})^n] - 2^n + 1$ chia hết cho 10; Tổng quát nếu m, a, b là số tự nhiên và b < 2a thì số $[(am + 1 + \sqrt{a^2m^2 + bm + 1})^n] - 2^n + 1$ chia hết cho 2m (ở đây [x] là phần nguyên của số x) *).

Tổng số khác biệt

Trước khi xây dựng các định lý tổng quát, chúng ta hãy chứng minh quá trình giải thích của chúng ta bằng ví dụ d). bài toán này, cũng như hệ quả tất yếu sau đây từ Định lý 2 và Bổ đề 1, tạo thành nội dung của bài toán M629 từ Zadaniak «Kvant».

Hãy xem xét sự khác biệt giữa các giá trị của hàm này
$$f(n) = 2^{2n-1} - 9n^2 + 21n - 14$$
tại các điểm n+1 và n:
$$g(n) = f(n+1) - f(n) = 3 \cdot 2^{2n-1} - 18n + 12.$$
Ta muốn chứng minh rằng $f(n)$ chia hết cho 27 với mọi n=1, 2,...

*) Hai bài toán này được gửi vào năm ngoái bởi độc giả B. Chuchin từ làng của chúng tôi. Voznesenskoye, Lãnh thổ Khabarovsk và Walter Janous từ Innsbruck (Áo).

⟦folio 29⟧

Làm thế nào để đưa ra một bài toán mới?

Không có gì có thể đơn giản hơn. Ví dụ: chúng ta hãy chọn $a, b$ và $c$ sao cho biểu thức $f(n) = an + b + c \cdot 9^n$ thuộc về (bất kỳ giá trị nguyên nào!) cho $n = -1$, $n = 0$ và $n = 1$. thì theo Định lý 2 (đối với $k = 2$), số $f(n)$ sẽ là số nguyên đối với mọi số nguyên $n \geq -1$.

Hãy lấy, ví dụ, $f(-1) = -1$, $f(0) = 0$, $f(1) = 4$. Đã giải quyết được hệ thống

$$\begin{cases}
-a + b + c/9 = -1, \\
b + c = 0, \\
a + b + 9c = 4.
\end{cases}$$

chúng ta sẽ tìm thấy $a = \frac{5}{8}$, $b = -\frac{27}{64}$, $c = \frac{27}{64}$.

Đây có lẽ chính xác là ví dụ d) đã được phát minh ra cách đây rất lâu. Chúng tôi khuyên người đọc nên tự mình đưa ra một vài ví dụ mới.

Nhưng con đường của chúng ta vẫn chưa kết thúc: chúng ta muốn khái quát hóa định lý để nó cũng bao gồm các ví dụ trong đó có một số cấp số nhân.

Tổng số tiến triển

Hãy thử chứng minh điều tương tự này với Định lý 1 và 2 của chúng tôi:

Định lý 3. Nếu $q_1, q_2, \dots, q_r$ là số nguyên $u$
$f(n) = c_1 q_1^n + c_2 q_2^n + \dots + c_{r-1} q_{r-1}^n + c_r q_r^n$
là số nguyên cho $n = 1, 2, \dots, r$, thì $f(n)$ là số nguyên cho mọi số tự nhiên $n$.
(Bổ đề 1 là trường hợp đặc biệt của định lý cho $r = 2, q_2 = 1$).

Gợi ý. Để chứng minh Định lý 3, cần xét hiệu $g(n) = f(n+1) - q_r f(n)$. Vì $g(n) = c_1 (q_1 - q_r) q_1^n + \dots + c_{r-1} (q_{r-1} - q_r) q_{r-1}^n$ là tổng của $r-1$ cấp số nhân và trong điều kiện của định lý, số $g(n)$ là số nguyên cho $1 \leq n \leq r-1$, nên định lý có thể được chứng minh bằng quy nạp trên $r$: xét cho cùng
$$f(n) = g(n-1) + q_r g(n-2) + \\
+ q_r^2 g(n-3) + \dots + q_r^{n-1} g(1) + q_r^n f(1).
$$
(Tak, trong bài toán 3) chúng ta có thể xét hiệu $f(n+1) - 45f(n)$.

Bài tập 1. Kiểm tra các ví dụ a), e) sử dụng Định lý 3 và đưa ra một số ví dụ mới cho nó.

Chúng tôi hy vọng rằng chúng tôi đã đánh thức niềm đam mê khái quát hóa của người đọc và chúng tôi cung cấp cho họ những bài tập khó hơn sau đây:

2. Hình thành và chứng minh các điều tương tự của Định lý 1–3

a) với tổng $r$ cấp số nhân và đa thức bậc $k-1$;

6) cho tích của một cấp số (có giá trị nguyên) theo một đa thức.

Hãy đưa ra một số ví dụ để áp dụng định lý của bạn.

3. Bạn có thể xây dựng định lý tổng quát nào hơn thuộc loại này?

4. Có thể, theo các điều kiện của định lý của chúng tôi, có thể giảm số điểm cần xác minh không?

5. Chứng minh nhận định và phát biểu khái quát hóa và phát biểu khái quát hóa được chứng minh rõ ràng và đơn giản hơn phát biểu cụ thể. Một minh họa tuyệt vời cho điều này là định lý sau đây, tuy có công thức khá phức tạp nhưng lại khái quát hóa các định lý trước đó và cho phép bạn trả lời tất cả các câu hỏi trong bài tập 2–5.

Định lý 4. Gọi biểu thức $f(n)$ là tổng của $r$ đa thức nhân với một cấp số nhân nào đó. Chúng ta hãy xây dựng một đa thức có hệ số cao nhất là 1, các nghiệm của nó là mẫu số của các cấp số $r$ này và bội số của mỗi nghiệm lớn hơn một bậc so với bậc của đa thức tương ứng. (Bậc $k$ của đa thức đặc trưng này bằng tổng của số $r$ cấp số nhân và bậc của tất cả các đa thức mà chúng được nhân với chúng.) Nếu (1) tất cả các hệ số của đa thức đặc trưng là số nguyên và (2) các giá trị của $f(n)$ là số nguyên tại $n=1, 2, \dots, k$, trong đó $k$ là bậc của đặc trưng đa thức thì $f(n)$ sẽ không bị ảnh hưởng ngay cả với $n>k$ hoàn toàn tự nhiên.

Tất nhiên, để điều kiện (1) được đáp ứng, điều đủ (nhưng không cần thiết) là tất cả các cấp số được chỉ ra đều là số nguyên. Vai trò của các hệ số của một đa thức đặc trưng được rõ ràng từ bổ đề quan trọng hiển nhiên sau đây, việc xác minh chúng tôi dành cho người đọc:

⟦folio 30⟧

Bổ đề 2. Hãy để
$$f(x) = B_1(x)q_1^x + B_2(x)q_2^x + \dots + B_r(x)q_r^x,$$
(3)
thức ăn $B_i(x)$ là đa thức bậc $k_i-1$ ($i=1, 2, \dots, r$), và
$$D(\lambda) = (\lambda-q_1)^{k_1}(\lambda-q_2)^{k_2} \dots (\lambda-q_r)^{k_r} = \lambda^k + d_1\lambda^{k-1} + d_2\lambda^{k-2} + \dots + d_{k-1}\lambda + d_k.$$
Khi đó thức ăn cho tất cả $x$ đẳng thức được đáp ứng:
$$f(x) + d_1f(x-1) + d_2f(x-2) + \dots + d_kf(x-k) = 0.$$

Định lý 4 suy ra ngay từ đây: nếu tất cả các hệ số $d_1, \dots, d_k$ được đặc trưng bởi đa thức $D(\lambda)$ - số nguyên, thì từ đẳng thức (3) suy ra rằng $f(n)$ cho mỗi $n > k$ thu được bằng cách cộng các giá trị nguyên $f(n-1), f(n-2), \dots, f(n-k)$ nhân với các hệ số nguyên cố định.

Để minh họa, hãy xem xét hai ví dụ cắt.

e) Đặt $f(n) = \frac{1}{2} \cdot 4^n + (-9n^2 + 21n-14) \cdot 1^n$. Đây $D(\lambda) = (\lambda-4)(\lambda-1)^3 = \lambda^4 - 7\lambda^3 + 15\lambda^2 - 13\lambda + 4$. Pozny dành cho mọi người $n$
$$f(n) = 7f(n-1) - 15f(n-2) + 13f(n-3) - 4f(n-4).$$

Cụ thể, sau $f(1) = f(2) = f(3) = 0$ và $f(4) = 54$ có $f(5) = 7 \cdot 54 = 378$, $f(6) = 7 \cdot 378 - 15 \cdot 54 = 1836, \dots$; Đương nhiên, tất cả chúng sẽ chia hết cho 27 (sau đây cho 54).

i) Đặt $f(n) = \frac{(6+\sqrt{31})^n}{10} + \frac{(6-\sqrt{31})^n}{10} - \frac{2^n}{10}$. Ở đây các hệ số của đa thức $D(\lambda) = (\lambda^2 - 12\lambda + 5)(\lambda-2) = \lambda^3 - 14\lambda^2 + 19\lambda - 10$ cũng là số nguyên. Sau các số hạng đầu tiên $f(0) = \frac{1}{10}, f(1) = 1, f(2) = 13$, tất cả các số hạng tiếp theo $f(n)$ được xác định bằng sự tương ứng đệ quy
$$f(n) = 14f(n-1) - 19f(n-2) + 10f(n-3).$$

Đặc biệt, $f(3) = 14 \cdot 13 - 19 \cdot 1 + \frac{10}{10} = 124$ là số nguyên nên tất cả $f(n)$ với $n=4, 5, \dots$ cũng sẽ là số nguyên.

Trong bài tập cuối cùng, chúng tôi mời người đọc hiểu cách sử dụng Bổ đề 2 để chứng minh các trường hợp từng phần của Định lý 4 đã thảo luận.
