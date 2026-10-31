---
id: 1980-11-avramov-arifmeticheskie-progressii-v-treugolnike-paskalya-5ee09e49
issue: kvant_1980_11
year: 1980
number: "11"
title: Cấp số cộng trong tam giác Pascal
authors:
  - Аврамов А.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 29
page_last: 30
page_labels: 27-28
tag: SI4T
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 1bef87bd8f17b2b113977bc2ac01e14015a9cde3c504d3c31b86dbedd8347a8d
prompt_sha256: draft-1
translated_from: content/ru/1980/11/articles/08_avramov-arifmeticheskie-progressii-v-treugolnike-paskalya-5ee09e49.md
source_content_sha256: faeb8640ef35bb5c08608eea88cb1ef29ecf5262ce1887a3c2e5468906fbda66
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 27⟧

F612. Lượng nhiệt Q phải truyền cho m=0,1 kk neon để cắt nó ở Δt=5°C, nếu trong quá trình cắt áp suất neon tỉ lệ thuận với thể tích của nó?

Theo nhiệt động lực học đầu tiên
$$Q = \Delta U + A,$$

trong đó ΔU là độ biến thiên nội năng của neon; A là công do khí thực hiện khi cắt nó.
Neon là một loại khí đơn nguyên tử. Đó là lý do tại sao
$$\Delta U = \frac{3}{2} v R (\Delta T) = \frac{3}{2} \frac{m}{M} R (\Delta T)$$
(v = $\frac{m}{M}$ là số lượng neon, M=20·10⁻³ kg/mol là khối lượng mol của nó).

Công A của một chất khí bằng tích của áp suất trung bình $p_{cp}$ và độ biến thiên về thể tích:
$$A = p_{cp} V = p_{cp} (V_2 - V_1),$$

trong đó $V_2$ là thể tích cuối cùng, $V_1$ là thể tích ban đầu của khí. Vì khi cắt khí, áp suất tỷ lệ thuận với thể tích nên áp suất trung bình bằng giá trị trung bình số học của áp suất $p_1$ ban đầu và áp suất cuối cùng $p_2$. Đó là lý do tại sao
$$A = \frac{1}{2} (p_2 + p_1) (V_2 - V_1).$$

Công thức này có thể được biến đổi như sau:
$$A = \frac{1}{2} (p_2 V_2 - p_1 V_1) + \frac{1}{2} (p_1 V_2 - p_2 V_1).$$

Áp suất neon trong quá trình cắt tỷ lệ thuận với thể tích của nó, tức là $p_1 = \alpha V_1$, $p_2 = \alpha V_2$, trong đó α là hệ số tỷ lệ. Vì vậy $p_1 V_2 - p_2 V_1 = \alpha V_1 V_2 - \alpha V_2 V_1 = 0$.
Như vậy,
$$A = \frac{1}{2} (p_2 V_2 - p_1 V_1) = \frac{1}{2} \Delta(pV),$$

trong đó Δ(pV) là sự thay đổi của tích pV. Theo phương trình trạng thái khí pV = $\frac{m}{M} RT$, do đó Δ(pV) = $\frac{m}{M} R (\Delta T)$ và
$$A = \frac{1}{2} \frac{m}{M} R (\Delta T),$$

Thay các giá trị của ΔU và A vào biểu thức (*), ta tìm được
$$Q = 2 \frac{m}{M} R (\Delta T) \approx 41,5 \text{ Дж.}$$

I. Slovodetsky

A. Avramov

Cấp số cộng trong tam giác Pascal

Bài toán được thảo luận trong ghi chú này (M602 - «Kvant», 1980, số 2) liên quan đến tam giác Pascal - một tam giác số, hàng thứ n (n=0,1,2,3,...) gồm n+1 số

$$C_n^0, C_n^1, C_n^2, ..., C_n^n$$

($C_n^m$ là số tổ hợp từ n đến m*).

Hình (tr. 28) hiển thị tám hàng đầu tiên của tam giác Pascal (n=0,1,2,...,7). Dòng thứ tám (n=7) gồm các số
1, 7, 21, 35, 35, 21, 7, 1.

Nó được thay thế bằng thực tế là trong đó các số thứ hai, thứ ba và thứ tư (cũng như thứ năm, thứ sáu và thứ bảy) tạo thành một cấp số nhân.

Có đường nào khác trong tam giác Pascal có đường thẳng tương tự không?

*) Về tam giác Pascal, xem cẩm nang “Đại số và sự khởi đầu của giải tích 9”, đoạn 7, 8. Ngoài ra, năm 1979, nhà xuất bản Nuka đã xuất bản ấn bản thứ 2 cuốn sách nhỏ “Tam giác Pascal” của V. A. Uspensky trong bộ “Bài giảng phổ biến về toán học”.

⟦folio 28⟧

Thuộc tính, tức là các dòng trong đó ba số đứng cạnh nhau sẽ tạo thành một cấp số cộng?

Giả sử có các số tự nhiên $n$ và $k$ sao cho bộ ba số $C_n^{k-1}, C_n^k, C_n^{k+1}$ là một cấp số cộng. Điều này có nghĩa là

$$2C_n^k = C_n^{k-1} + C_n^{k+1}$$

($1 \leq k \leq n-1$),

đó là

$$\frac{2n!}{k!(n-k)!} = \frac{n!}{(k-1)!(n-k+1)!} + \frac{n!}{(k+1)!(n-k-1)!},$$

từ đâu chúng ta có được phương trình

$$4k^2 - 4nk + n^2 - n - 2 = 0,$$

(1)

phải giải bằng số tự nhiên.

Hãy giải nó dưới dạng phương trình bậc hai cho $k$:

$$k_{1,2} = \frac{n \pm \sqrt{n+2}}{2}.$$

Chúng ta hãy đặt $n+2 = t^2$, trong đó $t$ là một số tự nhiên. chúng tôi nhận được

$$k_1 = \frac{(t+1)(t-2)}{2},$$

$$k_2 = \frac{(t-1)(t+2)}{2},$$

và với $t \geq 3$ cả $k_1$ và $k_2$ đều là số tự nhiên, $1 < k_1 < n-1$, $1 < k_2 < n-1$.

Vì vậy, nếu các số tự nhiên $n$ và $k$ thỏa mãn phương trình (1) thì chúng được tìm thấy theo công thức

$$\begin{cases} n = t^2 - 2, \\ k_{1,2} = \frac{t^2 + t - 2}{2}, \end{cases}$$

trong đó $t$ là số tự nhiên và $t \geq 3$.

Ngoài ra, với mọi số tự nhiên $t \geq 3$, mỗi cặp số $n$ và $k$ thu được theo công thức (2) đều thỏa mãn phương trình (1) - hãy đảm bảo điều này.

Các tài liệu này cho thấy trong tam giác Pascal có vô số dòng chứa cấp số cộng ba số hạng của các số liên tiếp. Hơn nữa, mỗi dòng có hai tiến trình. Điều này không có gì đáng ngạc nhiên: xét cho cùng, tam giác Pascal là đối xứng. Do đó, cả hai tiến trình này đều bao gồm các số giống nhau: số lần đầu tiên (thu được ở $k=k_1$) tăng lên và số lần giết thứ hai (ở $k=k_2$).

Tại $t=3$ chúng tôi nhận được $n=7$ - chúng tôi bắt đầu quan sát bằng dòng này. Đối với $t=4$, chúng tôi nhận được $n=14$, $k_1=5$, $k_2=9$. Điều này tương ứng với dòng thứ mười lăm của tam giác Pascal: 1, 14, 91, 364, 1001, 2002, 3003, 3432, 3003, 2002, 1001, 364, 91, 14, 1; ở đây các số được đánh dấu tạo thành một cấp số cộng.

Điều gì xảy ra nếu $t < 3$? $t=1$, rất indo, không phù hợp, nhưng với $t=2$ chúng ta nhận được $n=2$, $k_1=0$, $k_2=2$. Điều này tương ứng với hàng thứ ba của tam giác, chứa các số 1, 2, 1. Nếu chúng ta thêm số 0 vào bên trái và bên phải của chúng và không có số nào từ 0, chúng ta lại nhận được hai cấp số cộng: 0, 1, 2 và 2, 1, 0.

Dễ dàng nhận thấy rằng trong tam giác Pascal không có một dòng nào trong đó có một cấp số cộng chứa nhiều hơn ba số hạng (và các số hạng liên tiếp). Trên thực tế, nếu tìm được một dòng như vậy thì nó sẽ chứa ít nhất hai cấp số cộng ba số hạng bao gồm các số hạng khác nhau. Nhưng ở trên chúng ta đã chỉ ra rằng mỗi dòng có một cấp số cộng (trong đó các số nằm trên một hàng) được cấu trúc như thế này: về mặt thần kinh có hai cấp số được tạo thành từ các số giống nhau.

Chúng tôi mời bạn tự mình xác minh rằng không có một dòng nào trong tam giác Pascal chứa cấp số cộng bao gồm nhiều hơn ba số hạng (và một số hạng liên tiếp).
