---
id: 1973-9-resheniya-zadach-m179-m183-f193-f197-2c65d950
issue: kvant_1973_9
year: 1973
number: "9"
title: Lời giải bài toán M179—M183; F193—F197
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 29
page_last: 39
page_labels: 27, 28, 30, 31, 32, 33, 34, 36, 37
tag: MP96
lang: vi
source: kvant_digital
extraction: vision
content_sha256: f4b2aeee1381a883f0f844e17958ff08d617e53c2ec43b4f8755fac9a5d9190d
prompt_sha256: draft-1
translated_from: content/ru/1973/09/articles/10_resheniya-zadach-m179-m183-f193-f197-2c65d950.md
source_content_sha256: f25b808aad68a4139c0b2a1d9811d574fccfae0cada82efd14ec7d82278299eb
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 27⟧

Lời giải bài toán
M179—M183; F193—F197

M179. Đối với mỗi tam giác hữu ích không trực tiếp $T$ chúng ta biểu thị bằng $H(T) = T_1$ tam giác có các đỉnh là đáy và chiều cao của tam giác $T$; qua $T_2 = H(T_1)$ một tam giác có các đỉnh là đáy của tam giác $T_1$; hãy tiếp tục $T_3 = H(T_2)$, $T_4 = H(T_3)$, ...

Các góc của tam giác $T$ phải bằng bao nhiêu để
a) tam giác $H(T)$ có nhọn không?
b) trong dãy $T_1, T_2, T_3, \dots$ ta vẽ một tam giác vuông $T_n$ (trong trường hợp này $H(T_n) = T_{n+1}$ không được xác định)?
c) tam giác $T_1 = H(T)$ có đồng dạng với tam giác $T$ không?
e)* với mỗi $n = 1, 2, 3, \dots$ chúng ta chỉ ra có bao nhiêu tam giác khác nhau $T$ tồn tại mà $T_n$ tương tự với $T$.

Gọi $AA_1, BB_1$ và $CC_1$ là đường cao của tam giác $T$. Các góc $\alpha_1, \beta_1, \gamma_1$ tại các đỉnh $A_1, B_1, C_1$ (tương ứng) của tam giác $A_1B_1C_1$ được biểu thị bằng các góc $\alpha, \beta, \gamma$ tại các đỉnh $A, B, C$ của tam giác $ABC$ như sau:

$$\alpha_1 = \pi - 2\alpha, \quad \beta_1 = \pi - 2\beta, \quad \gamma_1 = \pi - 2\gamma,$$

(11)

Hình 1.

Hình 2.

⟦folio 28⟧

s ($\alpha, \beta, \gamma$). Rõ ràng chúng ta chỉ có thể xét trường hợp
$$\alpha \geqslant \beta \geqslant \gamma$$
(2).

Các góc của bất kỳ tam giác nào cũng có thể được ký hiệu bằng các chữ cái $\alpha, \beta$ và $\gamma$, sao cho bất đẳng thức (2) được thỏa mãn.

Nếu $\alpha < \frac{\pi}{2}$ (tất cả các góc đều nhọn), thì vì bất đẳng thức $2\pi - \alpha \leqslant 2\pi - \beta \leqslant 2\pi - \gamma$ theo (2), nên đối với sự đồng dạng của các tam giác $T_1$ và $T$ thì hệ đẳng thức phải được thỏa mãn
$$\pi - 2\alpha = \gamma, \quad \pi - 2\beta = \beta, \quad \pi - 2\gamma = \alpha,$$
Ở đâu
$$\alpha = \beta = \gamma = \frac{\pi}{3}.$$

Nếu $\alpha > \frac{\pi}{2}$, thì từ (2) chúng ta chỉ có thể sử dụng thực tế là $2\beta \geqslant 2\gamma$ và phải xem xét ba mối quan hệ có thể có giữa các góc $\alpha_1, \beta_1$ và $\gamma_1$: $2\beta \geqslant 2\gamma \geqslant 2\alpha - \pi, \quad 2\beta \geqslant 2\alpha - \pi \geqslant 2\gamma$ và $2\alpha - \pi \geqslant 2\beta \geqslant 2\gamma$. Điều đầu tiên dẫn đến hệ thống
$$2\beta = \alpha, \quad 2\gamma = \beta, \quad 2\alpha - \pi = \gamma,$$
chúng ta tìm thấy những điều thú vị ở đâu lời giải:
$$\alpha = \frac{4\pi}{7}, \quad \beta = \frac{2\pi}{7}, \quad \gamma = \frac{\pi}{7},$$

và hai cái còn lại, rất dễ kiểm tra, dẫn đến các giải pháp “được biểu thị” (một trong các góc được tạo thành bằng 0), không phù hợp với chúng tôi, như người ta nói, “không nằm trong phạm vi các giá trị cho phép”.

Là những độc giả chiếm lời giải trong số bài toán này, hãy viết, cho $n = 2, 3, 4$ và nói chung cho bất kỳ $n$ lời giải nào, đều có thể được tìm thấy bằng cách tìm kiếm tương tự nhưng phức tạp hơn nhiều. Thật vậy, về nguyên tắc chúng ta đã quy bài toán thành đại số. Chúng ta hãy phác thảo khả năng của một kế hoạch mở rộng hơn nữa (đối với $n$ tự nhiên tùy ý). Từ (1) bằng quy nạp ta thu được công thức tính các góc của một tam giác

$$\begin{cases}
\alpha_n = s2^n & \alpha + p\pi \\
\beta_n = s2^n & \beta + q\pi \\
\gamma_n = s2^n & \gamma + r\pi,
\end{cases}$$

trong đó $s$ bằng $+1$ hoặc $-1$, $p, q$ và $r$ là số nguyên (chứng minh rằng đã cho $\alpha, \beta$ và $\gamma$ và với điều kiện bổ sung $\alpha_n \geqslant 0, \beta_n \geqslant 0, \gamma_n \geqslant 0$, $\alpha_n + \beta_n + \gamma_n = \pi$ thì các tham số $p, q, r$, $s$ được xác định từ (3) duy nhất!). Hãy viết sáu hệ, đánh đồng ($\alpha_n, \beta_n, \gamma_n$) với các hoán vị khác nhau ($\alpha, \beta, \gamma$) và giải từng hệ. Từ lời giải thu được (tùy thuộc vào tham số $p, q, r, s$), chúng tôi chọn những kết quả thỏa mãn điều kiện $\alpha \geqslant \beta \geqslant \gamma$. Để trả lời câu hỏi: có bao nhiêu lời giải (với một $n$ cho trước), bạn sẽ cần tìm xem có bao nhiêu lời giải trong các số nguyên $p, q, r, s$ (trong đó $s = \pm 1$) có sáu hệ bất đẳng thức dẫn đến. Để thực hiện kế hoạch này,

⟦folio 30⟧

Câu trả lời “có”: số $n$ luôn lớn hơn hoặc bằng số $x$ tiếp theo. Rõ ràng là $x$ tiếp theo phải được thực hiện nhiều hơn tất cả những câu đã được sử dụng (nếu không câu hỏi này sẽ là câu hỏi duy nhất).

Vì vậy, khi bắt đầu trò chơi, bạn phải thông báo $x$ mọi lúc - cho đến khi người thực hiện điều ước nói “không” lần đầu tiên. Đặt $x_1 < x_2 < x_3 < \dots$ là chuỗi mà người đoán quyết định đặt tên cho đến khi nhận được đáp số “không” đầu tiên. Nó phải là vô hạn, vì $n$ có thể lớn như bạn muốn.

Bây giờ chúng ta đến với trò chơi thứ hai: đến câu hỏi thứ $k$, người hỏi lần đầu trả lời “không”. Như vậy,

$$x_{k-1} \leq n < x_k.$$

Sau đó, bạn có thể áp dụng chiến lược tương tự như chiến lược $S_n$ được mô tả ở trên, chia đôi khoảng cách còn lại. Rõ ràng, điều này sẽ yêu cầu tới $|\log_2(x_k - x_{k-1})|$ câu hỏi.

Giả sử rằng ở giai đoạn thứ hai của trò chơi, tức là sau đáp số “không” đầu tiên, chúng ta có và chơi như thế này. Vẫn còn phải chọn một chuỗi tăng dần đơn điệu $x_k$ để xác định hoàn toàn chiến lược.

Chúng ta hãy xem xét ba chiến lược cụ thể, chỉ khác nhau ở việc lựa chọn chuỗi $x_k$.

1. Chiến lược $T^1$: $x_k = 10k$. Sau đó, như đã nêu trong các điều kiện, $f_T(n)$ tăng lên xấp xỉ bằng $\frac{n}{10}$.

2. Chiến lược $T^2$: $x_k = 2^k$. Khi đó số câu hỏi ở giai đoạn đầu không quá $|\log_2 n|$, và số câu hỏi ở giai đoạn thứ hai không quá $|\log_2 \frac{n}{2}|$. Tổng cộng có khoảng $2\log_2 n$ câu hỏi.

3. Chiến lược $T^3$: $x_k = 2^{2k}$. Bây giờ số lượng câu hỏi ở giai đoạn đầu tiên đã giảm mạnh. Trên thực tế, hãy

$$2^{2k-1} \leq n < 2^{2k}.$$

Khi đó số câu hỏi ở màn đầu tiên của trò chơi bằng $k$ và không vượt quá

$$k \leq \log_2 \log_2 n + 1,$$

đối với $n$ lớn thì nhỏ hơn đáng kể so với $\log_2 n$. Trong giai đoạn thứ hai, chúng ta sẽ tiêu thụ khoảng

$$\log_2(2^{2k} - 2^{2k-1}) \approx \log_2 2^{2k} = 2^k$$

 câu hỏi. Điều này tốt hay xấu? Nó phụ thuộc vào số $n$. Hóa ra là đối với hầu hết $n$ trong khoảng (2), chiến lược này tốt hơn đáng kể so với hầu hết $n$ trong cùng khoảng thời gian.

Hãy để $n = 2^{2k} - 1$.

Sau đó

$$f_T(n) \approx \log_2 \log_2 n + 2^k \approx \log_2 n + \log_2 \log_2 n,$$

Đối với $n$ lớn, số hạng thứ hai nhỏ hơn nhiều và tỷ lệ $f_T(n)$ so với ước tính thấp hơn $\log_2 n$ (xem công thức (1)) gần bằng 1.

Hãy để bây giờ $n = 2^{2k-1}$. Khi đó giá trị $f_T^3(n)$ giống nhau và được biểu thị qua $n$ là

$$f_T^3(n) \approx \log_2 \log_2 n + 2^k \approx 2\log_2 n + \log_2 \log_2 n,$$

nghĩa là có khoảng hai vượt quá ước tính thấp hơn (1). Do đó, đối với các giá trị $n$ này, chiến lược $T^3$ không tốt hơn chiến lược $T^2$.

Tình huống này được minh họa bằng biểu đồ trong Hình 7. Trong biểu đồ này, đường màu đỏ thường mô tả ước tính thấp hơn đã được chứng minh ở trên: $\log_2 n$ (biểu đồ có tính chất định tính, sơ sài và không được cho là chính xác).

Đường màu đen có bậc thể hiện đồ thị của hàm $f_T^3(n)$. Hàm này không đổi trên mỗi khoảng của loại (2). Vào cuối khoảng thời gian như vậy, ước tính thấp hơn gần như bắt kịp nó, nhưng ở đây, giả sử, $f_T^3(n)$ bị tê liệt và trở nên lớn gấp đôi.

Câu hỏi đặt ra: liệu có một chiến lược $T^4$ mà $f_T^4(n)$ cho tất cả $n$ không khác quá nhiều so với giới hạn dưới không? (Lịch trình ước tính $f_T^4(n)$ được đưa ra trong đoạn văn sau.)

Bây giờ chúng ta mô tả một chiến lược $T^4$ sao cho

$$\lim_{n \to \infty} \frac{f_T^4(n)}{\log_2 n} = 1,$$

nghĩa là mức vượt quá tương đối của $f_T^4(n)$ so với giới hạn dưới $\log_2 n$ đối với các chiến lược $n$ lớn bằng 0.

Giai đoạn đầu tiên của trò chơi, trước một chuỗi số

$$x_k = 2^{2k}.$$

Giả sử rằng đối với câu hỏi thứ $k$ lần đầu tiên chúng tôi nhận được đáp số “không” thì ở đâu

$$2^{2k-1} \leq n < 2^{2k}.$$

Hãy để chúng tôi mô tả chiến lược $T^4$ cho giai đoạn thứ hai của trò chơi. Chúng ta hãy gán $n$ cho mỗi phần trong khoảng (2)

Hình 7.

⟦folio 31⟧

"trọng lượng" bằng $\frac{1}{n}$. Bây giờ chúng ta sẽ đặt câu hỏi theo cách chia xấp xỉ một nửa không phải số giá trị mà $n$ vẫn có thể lấy mà là tổng trọng số của chúng.

Hãy tính toán xem sẽ cần bao nhiêu câu hỏi để gỡ lỗi $n$ tùy ý trong khoảng thời gian (2). Hãy đặt $m=2^{2k-1}$. Ban đầu tổng các trọng số xấp xỉ bằng

$$\frac{1}{m} + \frac{1}{m+1} + \cdots + \frac{1}{m^2} \approx$$

$$\approx \left(1 + \frac{1}{2} + \cdots + \frac{1}{m^2}\right) -$$

$$- \left(1 + \cdots + \frac{1}{m}\right) \approx \ln(m^2) - \ln m =$$

$$= \ln m \leqslant \ln n.$$

Nếu chúng ta đoán $n$ thì chúng ta sẽ đưa tổng các trọng số về giá trị $\frac{1}{n} \cdot$, nghĩa là tổng các trọng số sẽ giảm khoảng $n\ln n$ lần. Giả sử rằng chúng ta có thể chia nó thành một nửa mỗi lần. Sau đó nó đã được chi tiêu

$$\log_2 n\ln n = \log_2 n + \log_2 \ln n \approx \log_2 n$$

Vortsov (thuật ngữ thứ hai cho $n$ lớn nhỏ hơn đáng kể so với thuật ngữ đầu tiên). Vì theo quy định, không thể chia chính xác tổng trọng số làm đôi nên số lượng câu hỏi thực sự lớn hơn một chút. Có thể chứng minh (nhưng điều này khó hơn) là nó vẫn không vượt quá

$$\log_2 n + \text{const}\log_2 \log_2 n$$

vortsov. (Ở đây const có nghĩa là một số không đổi mà chúng tôi không đánh giá.) Bằng cách thêm vào đây số lượng câu hỏi trong màn đầu tiên của trò chơi, chúng tôi chỉ chỉ ra hệ số trong số hạng thứ hai. Vì vậy, chúng tôi đã xây dựng một chiến lược cho phép chúng tôi gỡ lỗi bất kỳ $n$ nào trong thời gian không quá

$$\log_2 n + \text{const}\log_2 \log_2 n$$

vortsov.

Dễ dàng chỉ ra rằng hàm này thỏa mãn điều kiện (3) mà chúng ta đã hứa thực hiện.

J. M. Bardzin, A. L. Toom

**M 181. Chiều dài tối thiểu của một miếng nút bần để có thể dùng làm khung hình lập phương có cạnh 10 cm là bao nhiêu?** (Một chiếc nút chai có thể đi dọc theo một cạnh hai lần, tùy thuộc vào $90^\circ$ và $180^\circ$, nhưng không thể bẻ gãy được.)

Đáp số. Bạn cần ít nhất 150 cm nút chai.

Theo khung nút chai có chiều dài như vậy, được thể hiện như thế nào trong Hình 8. Bây giờ chúng ta cần chứng minh rằng khung nút chai ngắn hơn chiều dài của khối lập phương có cạnh 10 cm?

(Chúng ta hãy giả sử trong giây lát rằng chúng ta chỉ được phép uốn nút chai ở các đỉnh của khối lập phương và chúng ta đã tạo ra một loại khung nào đó, và nút chai bắt đầu và kết thúc

Hình 8.

tại các đỉnh của hình lập phương. Hãy đếm số cạnh trong khung này. Tất nhiên, chúng ta sẽ không tính các cạnh của hình lập phương - có 12 cạnh - mà là các cạnh được tạo thành từ các lỗ. Trong khung có đúng một đỉnh mà lỗ bắt đầu và một đỉnh mà lỗ kết thúc (các đỉnh này có thể trùng nhau). Chúng ta sẽ gọi những đỉnh này là đỉnh cuối và tất cả các đỉnh còn lại là đỉnh đi qua. Mỗi đỉnh đi qua liền kề với một số cạnh chẵn. Thật vậy, một con bọ đã đi vào đỉnh này nhất thiết phải thoát ra khỏi nó. Do đó, có ít nhất bốn xương sườn liền kề với nó. Ít nhất ba gân liền kề với đỉnh cuối. Do đó, tổng số cạnh không nhỏ hơn $\frac{6 \cdot 4 + 2 \cdot 3}{2} = 15$. Thật vậy, mỗi cạnh liền kề với hai đỉnh, vì vậy nếu một đỉnh có số $i$ liền kề với $c_i$ cạnh ($i = 1, 2, \ldots, 8$), thì $c_1 + c_2 + \ldots + c_8$ bằng hai lần số cạnh. Do đó, có ít nhất 15 gân trong khung và vì chiều dài của một gân là 10 cm nên cần có ít nhất 150 cm lỗ.

Bây giờ chúng ta cần chứng minh rằng nếu chúng ta uốn cong các phích cắm ở các điểm bên trong của các gân thì vẫn không thể làm được các phích cắm khung nhỏ hơn 150 cm. bài toán này có thể được giảm xuống thành khung trước như sau: không cần thông báo độ dài của các lỗ, bất kỳ khung nào cũng có thể được cắt lại để tất cả các trụ đều ở các đỉnh. Chúng tôi sẽ không mô tả sự thay đổi này mà chỉ hiển thị một số hình ảnh xuất hiện (xem Hình 9, $a - \delta$; chúng hiển thị một cạnh nhất định của hình khối và lỗ bao phủ nó được mở rộng cho rõ ràng).

⟦folio 32⟧

Hình 9.

$$\frac{a}{b+c+d} + \frac{b}{a+c+d} + \frac{c}{a+b+d} + \frac{d}{a+b+c} \geq \frac{4}{3};$$

c) $a_1, a_2, a_3, \dots, a_n$ - số dương ($n \geq 2$), có thể

$$\frac{a_1}{a_2+a_3+\dots+a_n} + \frac{a_2}{a_1+a_3+\dots+a_n} + \dots + \frac{a_n}{a_1+a_2+\dots+a_{n-1}} \geq \frac{n}{n-1}.$$

Hãy giải quyết ngay nhé bài toán(c). Chúng ta biểu thị tổng $a_1 + a_2 + \dots + a_n$ bằng $s$ và các số $s - a_i$ bằng $b_i$. Trong ký hiệu này ta cần chứng minh rằng

$$\frac{s - b_1}{b_1} + \frac{s - b_2}{b_2} + \dots + \frac{s - b_n}{b_n} \geq \frac{n}{n-1}.$$

Bất đẳng thức này tương đương với:

$$s \left( \frac{1}{b_1} + \frac{1}{b_2} + \dots + \frac{1}{b_n} \right) \geq \frac{n}{n-1} + n = \frac{n^2}{n-1}.$$

(1)

Bây giờ chúng ta hãy sử dụng mối quan hệ phổ biến giữa trung bình số học và trung bình hình học (xem «Kvant», 1970, Số 8, trang 33): nếu $c_1, c_2, \dots, c_n$ là số không âm thì

$$\frac{c_1 + c_2 + \dots + c_n}{n} \geq \sqrt[n]{c_1 c_2 \dots c_n}.$$

(2)

Từ đó ngay lập tức xảy ra rằng

$$\left( \frac{1}{b_1} + \frac{1}{b_2} + \dots + \frac{1}{b_n} \right)^n \geq \frac{1}{b_1 b_2 \dots b_n}$$

và đó là $b_1 b_2 \dots b_n \leq \left( \frac{b_1 + b_2 + \dots + b_n}{n} \right)^n$.

Từ hai bất đẳng thức này suy ra

$$\left( \frac{1}{b_1} + \frac{1}{b_2} + \dots + \frac{1}{b_n} \right)^n \geq \left( \frac{n}{b_1 + b_2 + \dots + b_n} \right)^n$$

và cuối cùng,

$$\frac{1}{b_1} + \frac{1}{b_2} + \dots + \frac{1}{b_n} \geq \frac{n^2}{b_1 + b_2 + \dots + b_n}.$$

Nhưng

$$b_1 + b_2 + \dots + b_n = ns - a_1 - a_2 - \dots - a_n = (n-1)s,$$

Ở đâu

$$s \left( \frac{1}{b_1} + \frac{1}{b_2} + \dots + \frac{1}{b_n} \right) \geq \frac{sn^2}{s(n-1)} = \frac{n^2}{n-1}.$$

Bất đẳng thức (1) đã được chứng minh.

Bây giờ chúng ta hãy trình bày một số thông điệp mà nhờ đó chúng ta có thể chứng minh mối quan hệ (2). Hãy để $c_1 + c_2 + \dots + c_n = 1$. (Điều này không giới hạn tính tổng quát.) Giả sử rằng đối với những số này, quan hệ (2) bị vi phạm, nghĩa là

$$\frac{c_1 + c_2 + \dots + c_n}{n} < \sqrt[n]{c_1 c_2 \dots c_n}.$$

Giả sử trung bình của các số $c_i$ không bằng nhau. Sau đó, ở giữa $c_i$ có hai số - chúng ta có thể giả sử rằng đây là $c_1$ và $c_2$ - sao cho $c_1 < \frac{1}{n}$, $c_2 > \frac{1}{n}$. Lưu ý $c_1$ trên $c'_1 = \frac{1}{n}$ và $c_2$ trên $c'_2 = c_1 + c_2 - \frac{1}{n}$. Khi đó đối với các số $c'_1 = \frac{1}{n}, c'_2 = c_1 + c_2 - \frac{1}{n}$, quan hệ (2) cũng sẽ bị vi phạm. Bằng chứng của thực tế này được chứng minh bằng bất đẳng thức $\frac{1}{n} \left( c_1 + c_2 - \frac{1}{n} \right) > c_1 c_2$ (tại $c_1 < \frac{1}{n}, c_2 > \frac{1}{n}$), - bạn có thể dễ dàng tự mình giải quyết bất đẳng thức này.

Khi đề xuất những thay thế này, chúng ta phải thực hiện tập hợp $c_1 = c_2 = \dots = c_n = \frac{1}{n}$. Do đó, nếu quan hệ (2) bị vi phạm đối với một tập hợp $c_1, c_2, \dots, c_n$ nào đó, thì nó cũng sẽ bị vi phạm đối với tập hợp $\frac{1}{n}, \frac{1}{n}, \dots, \frac{1}{n}$. Tuy nhiên, bằng cách thay thế không xác định, chúng tôi đảm bảo rằng trong trường hợp này nó đúng. Điều này có nghĩa là nó cũng đúng với tập hợp ban đầu.

Đây là một lời giải khác trong số bài toán của chúng tôi, dựa trên mối quan hệ giữa mức trung bình

⟦folio 33⟧

Hình 10.

trung bình số học và hình học của hai số.
Chúng ta phải chứng minh rằng
$$ (n-1) \left( \frac{s-b_1}{b_1} + \dots + \frac{s-b_n}{b_n} \right) \geq n. $$
Lưu ý rằng $b_1 + \dots + b_n = (n-1) s$. Đó là lý do tại sao
$$ (n-1) \frac{s-b_1}{b_1} = \frac{b_1 + b_2 + \dots + b_n - (n-1) b_1}{b_1} = \frac{b_2 + \dots + b_n}{b_1} - (n-2) = \frac{b_2}{b_1} + \frac{b_3}{b_1} + \dots + \frac{b_n}{b_1} - (n-2). $$
Chúng ta cũng biến đổi các số hạng $(n-1) \frac{s-b_i}{b_i}$ còn lại và thêm tất cả các số hạng $n$.

Sau đó, chúng ta nhóm các phân số $\frac{b_i}{b_j}$ theo cặp và sử dụng bất đẳng thức:
$$ \frac{b_i}{b_j} + \frac{b_j}{b_i} \geq 2 $$
Vì tổng các cặp $i$ và $j$ ($1 \leq i < j \leq n$) sẽ là
$$ C_n^2 = \frac{n(n-1)}{2}, $$
thì kết quả là chúng ta nhận được:
$$ (n-1) \left( \frac{s-b_1}{b_1} + \dots + \frac{s-b_n}{b_n} \right) \geq C_n^2 \cdot 2 - (n-2) n = n^2 - n - n^2 + 2n = n. $$
Từ cả thứ nhất và thứ hai lời giải, có thể thấy ngay rằng các bất đẳng thức chỉ chuyển thành đẳng thức tại $b_1 = \dots = b_n$, tức là tại $a_1 = \dots = a_n$
L. G. Limanov

Hình 11.

M183. Tìm chiều cao của một hình thang có đáy là $a$ và $b$ ($a < b$), góc giữa hai đường chéo là $90^\circ$ và góc giữa phần kéo dài của các đường bên là $-45^\circ$.

Hầu hết độc giả đã gửi lời giải cho bài toán này bằng cách sử dụng lượng giác. Đây là một trong những lời giải ngắn nhất, được gửi bởi L. và S. Pizzkov.

Cho (Hình 10) trong hình thang $ABCD$, trong đó $AB \parallel CD$ $AB = a$, $CD = b$, $BC = x$, $AD = y$, điểm $E$ trên đáy $CD$ sao cho $ABCE$ là hình bình hành: $AE = x$, $DE = b - a$. Diện tích tam giác $ADE$ gấp đôi là
$$ xy \sin 45^\circ = (b - a) h, $$
(1)
trong đó $h$ là chiều cao của hình thang. Tiếp theo, sử dụng định lý cosine, chúng ta thu được điều đó
$$ (b - a)^2 = x^2 + y^2 - 2xy \cos 45^\circ. $$
(2)
Cuối cùng, sử dụng định lý Pythagore áp dụng cho bốn tam giác vuông $AOB$, $BOC$, $COD$, $DOA$, ta suy ra rằng
$$ x^2 + y^2 = a^2 + b^2 $$
(3)
Bây giờ chúng ta thay (3) và (1) thành (2) ($\cos 45^\circ = \sin 45^\circ$):
$$ (b - a)^2 = a^2 + b^2 - 2(b - a)h. $$
Như vậy,
$$ h = \frac{ab}{b - a}. $$

Độc giả của chúng tôi N.I. Berezovsky và một số người khác đưa ra phương pháp dựng hình thang, được thảo luận trong các điều kiện, theo dữ liệu a và b (Hình 11). Nghiên cứu cho thấy một hình thang như vậy tồn tại ở $\frac{b}{a} \geq 1 + \sqrt{2}$.
N. B. Vasiliev

F193. Có hai hệ thống đường có cùng khoảng cách hình thành. Trục quang của các đường thẳng trùng nhau. Hệ thống đường thứ nhất bao gồm các đường thu, trong hệ thống thứ hai có các đường thu qua một góc có đường phân tán. Các đường được đặt tên trong mỗi hệ thống, nếu khoảng cách giữa các đường cao hơn nhiều so với đường chính thức.

⟦folio 34⟧

Chúng ta hãy xem xét một chùm tia song song chạy dọc theo trục quang chính của hệ thống, bao gồm các thấu kính thu thập. Sau khi đi qua thấu kính thứ nhất, chùm tia sẽ hội tụ, khi đi qua thấu kính thứ hai - thậm chí còn hội tụ nhiều hơn, v.v. Nếu số lượng thấu kính đủ lớn thì ở đâu đó bên trong hệ thống chùm tia sẽ được chứa trong một điểm. Sau đó, chùm tia trở nên phân kỳ, nhưng độ phân kỳ của nó sẽ ngày càng ít đi cho đến khi nó trở nên song song; thì mọi thứ sẽ được lặp lại. Đường đi gần đúng của tia dan trong Hình 12, a.

Đối với trường hợp thứ hai, khi hệ thống bao gồm các thấu kính hội tụ và phân kỳ xen kẽ (xem Hình 12, b), “chu kỳ” của quỹ đạo tia sáng lớn hơn nhiều so với trường hợp đầu tiên, vì hoạt động của thấu kính hội tụ và thấu kính phân kỳ trên chùm sáng là ngược nhau.

Để xác định, khoảng cách giữa các thấu kính được lấy bằng tiêu cự $1/3$. Về nguyên tắc, tất cả những khác biệt vẫn giữ nguyên đối với cả chùm tia tùy ý và các mối quan hệ khác giữa tiêu cự và khoảng cách giữa các thấu kính.

F194. Một điện tích được đặt giữa các bản của một tụ điện phẳng. Nó sẽ chuyển động như thế nào nếu đặt một điện áp hình sin có pha ban đầu $\varphi_0 = 0$ vào tụ điện?

Giả sử vận ​​tốc điện tích ban đầu bằng không.

Nếu đặt một điện áp $u = U_0 \sin \omega t$ vào mặt phẳng của tụ điện thì hướng của điện trường bên trong tụ điện thay đổi theo thời gian theo định luật $E = E_0 \sin \omega t$. Vì điện tích $q$ chịu tác dụng của lực $F = Eq$ trong điện trường nên gia tốc của nó

⟦folio 36⟧

tại thời điểm lực đàn hồi của lò xo vết thương bằng trọng lượng của khối bên dưới.

Hoặc cũng có thể làm sao cho khối trên dừng lại khi lực của lò xo đàn hồi nhỏ hơn trọng lượng của khối dưới. Khi đó khối dưới sẽ dừng lại tại chỗ và chỉ cần xem xét chuyển động của một khối trên là đủ.

Hãy viết định luật bảo toàn năng lượng cho trường hợp này:

$$\frac{k(l_0 - l)^2}{2} = \frac{k(l_1 - l_0)^2}{2} + m_1g(l_1 - l)$$

($l_1$ là độ dài tối đa của lò xo).

Từ đây

$$l_1 = l_0 - \frac{m_1g}{k} + \sqrt{\left(l_0 - \frac{m_1g}{k}\right)^2 + l\left(l - 2l_0 + \frac{2m_1g}{k}\right)}$$

Chiều cao của hình lập phương trên bằng

$$\Delta l = l_1 - l$$

và khối tâm của hệ là

$$\Delta x_{\text{цм}} = \frac{\Delta l m_1}{m_1 + m_2}$$

F196. Trong buồng gia tốc, một bó lò xo rất mỏng chuyển động dọc theo một đường tròn có bán kính $R$. Độ lớn của moka tại thời điểm ban đầu là $I_0$, tổng số hạt trong buồng là $n$. Thông lượng cực đại xuyên qua quỹ đạo chùm tia không đổi thay đổi với tốc độ $\varphi$. Kích thước của moka sau khi tôi khai thác sẽ là bao nhiêu khi các hạt thực hiện một vòng quay? Tốc độ của hạt vẫn nhỏ hơn nhiều so với tốc độ ánh sáng.

Độ lớn của dòng điện $I$ phụ thuộc vào tốc độ của hạt như sau:

$$I = en_0 v S$$

trong đó $e$ là điện tích lò xo, $n_0$ là số proton trên một đơn vị thể tích, $S$ là diện tích tiết diện của chùm tia, $v$ là tốc độ. Do đó, chúng ta sẽ giả sử rằng các proton được phân bố đồng đều trên toàn bộ quỹ đạo của chúng (có tính đến việc chùm tia rất hẹp)

$$n_0 = \frac{n}{2\pi RS}$$

Sau đó

$$I = \frac{en}{2\pi R} v$$

Vì vậy, để tìm dòng điện, bạn cần tìm tốc độ của lò xo. Chúng tôi biết tốc độ ban đầu. Nó bằng nhau

$$v_0 = \frac{2\pi R I_0}{ne}$$

Do từ thông trong buồng máy gia tốc thay đổi nên sẽ gây ra e. d. c. cảm ứng bằng (tính theo giá trị abscillot) với tốc độ thay đổi của từ thông $\varphi$, nghĩa là

$$E = \varphi$$

Khi proton thực hiện một vòng quay, điện trường sẽ thực hiện công lên nó bằng $Ee$, công này bị ảnh hưởng bởi sự thay đổi động năng của proton:

$$\frac{mv^2}{2} - \frac{mv_0^2}{2} = Ee$$

($m$ là khối lượng proton $^*$).

Từ đây chúng ta tìm được tốc độ của proton sau khi nó thực hiện một vòng quay trong buồng máy gia tốc:

$$v = \sqrt{v_0^2 + \frac{2Ee}{m}}$$

Khi đó dòng điện trong buồng sẽ như thế này:

$$I = \frac{ne}{2\pi R} \sqrt{\left(\frac{2\pi R}{ne} I_0\right)^2 + 2\varphi \frac{e}{m}} = I_0 \sqrt{1 + \frac{n^2 e^3 \varphi}{2\pi^2 R^2 m I_0^2}}$$

Tôi. Sh. Slobodetsky

F197. Trên một viên phấn có khối lượng $m$, nằm trên đường chân trời của một bề mặt gồ ghề có hệ số lò xo $k$, tại thời điểm $t = 0$ một lực tỉ lệ với thời gian bắt đầu tác dụng một góc $\alpha$ so với đường chân trời. Xác định tốc độ $v$ chuyển động của vật sau t giây.

Coi vật là một điểm vật chất, khoảng cách của lực tác dụng lên nó (Hình 15). Đây là lực hấp dẫn mg, phản lực hỗ trợ $N$, lực $f = At$ (sẽ thuận tiện hơn khi nói về các thành phần của nó $f_1 = At$ cos $\alpha$ và $f_2 = At$ sin $\alpha$)

*) Vì tốc độ của proton vẫn nhỏ hơn nhiều so với tốc độ ánh sáng nên khối lượng proton có thể coi là một giá trị không đổi.

Hình 15.

⟦folio 37⟧

và lực ma sát $f_{\text{Tp}} = kN$. Gia tốc theo phương ngang của vật chỉ có thể được truyền bởi lực $f_1$, nhưng để làm được điều này, nó phải lớn hơn lực ma sát $f_{\text{Tp}} = kN = k(mg - At \sin \alpha)$, lực này cũng phụ thuộc vào thời gian $t$.

Chúng ta hãy vẽ đồ thị sự phụ thuộc của các lực ngang tác dụng lên vật theo thời gian $t$ (Hình 16).

Từ 0 đến thời điểm $t_1$ vật chưa chuyển động vì lực ma sát tĩnh cân bằng với lực $f_1$, tức là

$$At_1 \cos \alpha = kmg - kAt_1 \sin \alpha,$$

Ở đâu

$$t_1 = \frac{kmg}{A(\cos \alpha + k \sin \alpha)}.$$

Ngoài ra còn có giới hạn thời gian thứ hai $t_2$ cho chuyển động được chỉ định trong nhiệm vụ. Lúc này phản lực của mặt đất trở thành 0 và vật thể bay lên

$$N = mg - At_2 \sin \alpha = 0$$

Và

$$t_2 = \frac{mg}{A \sin \alpha}.$$

Như vậy, chuyển động của vật trên bề mặt nảy sinh trong thời gian $\tau$, nằm trong khoảng: $t_1 < \tau < t_2$.

Lưu ý rằng nếu $kA \sin \alpha \geq A \cos \alpha$ thì khoảng $t_2 - t_1$ trở nên hẹp hơn, nhưng mọi suy luận vẫn hợp lệ.

Hãy viết phương trình chuyển động của thời điểm thời gian $\tau = t_1 + t'$ ($t'$ là thời điểm hiện tại, vắng mặt tại thời điểm $t_1$)

$$A (t_1 + t') \cos \alpha + kA (t_1 + t') \sin \alpha - kmg - ma,$$

trong đó $a$ là gia tốc của vật.

Hình 17.

Thay thế biểu thức cho $t_1$, chúng tôi tìm thấy

$$a = \frac{A \cos \alpha + kA \sin \alpha}{m} t'.$$

Hãy vẽ đồ thị sự phụ thuộc $a(t)$ (Hình 17). Tốc độ mong muốn $v$ tại thời điểm $\tau = t_1 + t'$ bằng số với diện tích của tam giác đã chọn:

$$v = \frac{a(\tau - t_1)}{2} = \frac{(A \cos \alpha + kA \sin \alpha)(\tau - t_1)^2}{2m} = \frac{[\tau A(\cos \alpha + k \sin \alpha) - kmg]^2}{2mA(\cos \alpha + k \sin \alpha)}.$$

Nếu bạn thay đổi hướng của lực tác dụng, như trong Hình 18, thì phản lực hỗ trợ $N = mg + At \sin \alpha$ sẽ liên tục tăng (cũng như lực ma sát $f_{\text{Tp}}$).

Thời gian $t_1$, sau đó vật chuyển động, được tính từ điều kiện

$$At_1 \cos \alpha - kmg - kAt_1 \sin \alpha = 0;$$

Sau đó

$$t_1 = \frac{kmg}{A \cos \alpha - kA \sin \alpha}.$$

Tuy nhiên, trong trường hợp này, giá trị dương $t_1$ chỉ xảy ra nếu $A \cos \alpha > kA \sin \alpha$. Tại $A \cos \alpha \leq kA \sin \alpha$ thời gian là $t_1 < 0$ và không có chuyển động nào xảy ra.

Sự gia tăng thành phần $f_2$ có thể dẫn đến sự phá hủy cơ thể (điều này có thể xảy ra trước thời điểm $t_1$). Nếu vật không sụp đổ và $t_1$ có ​​giá trị hữu hạn, thì đối với tốc độ $v$ tại thời điểm $\tau = t_1 + t'$, chúng ta thu được giá trị:

$$v = \frac{[\tau A(\cos \alpha - k \sin \alpha) - kmg]^2}{2mA(\cos \alpha - k \sin \alpha)}.$$

A. V. Ustinova
