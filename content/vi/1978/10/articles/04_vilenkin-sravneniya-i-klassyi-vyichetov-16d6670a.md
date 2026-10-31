---
id: 1978-10-vilenkin-sravneniya-i-klassyi-vyichetov-16d6670a
issue: kvant_1978_10
year: 1978
number: "10"
title: So sánh và các loại khấu trừ
authors:
  - Виленкин Н. Я.
rubric: osnovnye-stati
page_first: 6
page_last: 9
page_labels: 4-7
tag: IV5K
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 79f3a2632afe7946d984c84bbf8086ef092418e989d62ad79e1c964a40597401
prompt_sha256: draft-1
translated_from: content/ru/1978/10/articles/04_vilenkin-sravneniya-i-klassyi-vyichetov-16d6670a.md
source_content_sha256: 8865151fe074bc06da9c47d854420831b22c9dcde401b1bf540421eebcd0a95e
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 4⟧

N. Vilenkin

So sánh và các loại khấu trừ

Nhiều người yêu thích toán học biết những điều sau bài toán:

Khỉ và quả hạch

Năm du khách dừng lại một lúc. Họ mang theo một túi hạt và một con khỉ. Một người trong số họ thức dậy, đi đến túi và chia quả hạch thành 5 phần bằng nhau, còn lại một quả. Anh ta đưa cho con khỉ một quả hạch, ăn phần của mình và quay lại ngủ. Sau đó, người du hành thứ hai tỉnh dậy và không biết về hành động của người thứ nhất nên tiếp tục làm như vậy. Sau đó, ba du khách còn lại lần lượt làm như vậy. Khi số hạt còn lại được chia thành 5 phần bằng nhau thì buổi sáng lại còn lại một hạt cho khỉ. Có bao nhiêu quả hạch ở đó?

Toàn bộ khó khăn của bài toán này nằm ở các đai ốc bổ sung, nếu không có chúng đáp số sẽ đóng vai trò là bất kỳ số nào có thể chia sáu lần mà không có số dư cho 5, tức là bất kỳ số nào là bội số của $5^6 = 15625$. Và do thực tế là mỗi lần phép chia xảy ra với số dư nên bài toán khó giải hơn nhiều. Tuyệt vời lời giải được phát minh ở trường học

người quen thời thơ ấu của nhà vật lý người Anh Dirac. Anh ta quyết định tìm số hạt sẽ ... không thay đổi trong quá trình thực hiện mô tả (chia thành năm phần, chia một hạt cho khỉ và đưa một phần). Người đọc chắc chắn đã nói rằng không thể có nhiều hạt như vậy - rõ ràng là sau thao tác này, nó sẽ giảm đi. Nhưng mấu chốt là Dirac không giới hạn bản thân ở những số tự nhiên. Và sau đó tất cả những gì anh phải làm là giải phương trình $\frac{4}{5}(x-1)=x$. Căn nguyên của phương trình này là số -4. Vì vậy, số -4 có thể là một giải pháp cho bài toán của chúng ta, nhưng theo nghĩa của nó thì tất nhiên là không phù hợp. Nhưng bây giờ đã rõ làm thế nào để có được số dương đáp số: bạn cần thêm $5^6$ vào số -4 do Dirac tìm thấy. Kiểm tra xem đáp số 15 621 có thỏa mãn điều kiện bài toán hay không. Tuy nhiên, nó cũng được thỏa mãn bởi mọi số có dạng -4 + $5^6 \cdot k$, trong đó $k$ là số tự nhiên bất kỳ.

Những con số so sánh được là gì?

Nếu chúng ta bỏ qua yêu cầu về số dương lời giải, thì bất kỳ số nào có dạng -4 + $5^6 \cdot k$, trong đó $k$ là số nguyên, là nghiệm bài toán về quả hạch và con khỉ. Những con số này tạo thành một "cấp số học hai chiều" với hiệu $5^6$ kéo dài theo cả hai hướng. Chúng có một điểm chung - khi chia cho $5^6$ chúng đều có số dư là 15.621.

⟦folio 5⟧

Họ cũng nói về các con số trong toán học rằng chúng có thể so sánh được với nhau theo modulo*) 15 625.

Nói chung, khái niệm khả năng so sánh trên một số modulo $m \in \mathbb{N}$ có thể được định nghĩa theo hai cách tương đương:

Về giới hạn 1. Các số nguyên $a$ và $b$ được cho là có thể so sánh được modulo $m$ nếu hiệu của chúng chia hết cho $m$ mà không có số dư.

Về giới hạn 1'. Các số nguyên $a$ và $b$ được cho là có thể so sánh được với modulo $m$ nếu số dư của chúng khi chia cho $m$ là số lẻ*).

Nếu các số $a$ và $b$ có thể so sánh với nhau theo modulo $m$ thì chúng viết như sau:
$$a \equiv b \pmod{m}.$$
Ví dụ: $16 \equiv 30 \pmod{7}$, vì hiệu $16 - 30 = -14$ chia hết cho 7 và $72 \neq 45 \pmod{8}$, vì $72 - 45 = 27$ không chia hết cho 8.

Tính số dư

Tất cả các số có thể so sánh với số 2 modulo 5 đều hoạt động giống hệt nhau khi chia cho 5 - chúng có số dư là 2. Hãy kết hợp các số này thành một bộ và gọi nó là lớp của phép tính modulo 5. Hãy ký hiệu lớp này bằng cùng một số 2, chỉ để phân biệt với số 2, chúng ta sẽ viết nó như thế này: $\bar{2}$. Điều này có nghĩa là $\bar{2}$ không phải là một số mà là một tập hợp vô hạn các số:
$$\bar{2} = \{... -8, -3, 2, 7, 12, ...\}$$
Loại mục tiêu cũng được xác định bởi bất kỳ modulo nào $m$. Chia cho $m$ có thể cho ra $m$ số dư khác nhau: 0, 1, 2, ..., $m - 1$. Mỗi người trong số họ có lớp mục tiêu riêng. Phần còn lại $r$ tương ứng với lớp loại bỏ $\bar{r}$, bao gồm các số có dạng $r + km$, trong đó $k$ là số nguyên:
$$\bar{r} = \{r + km \mid k \in \mathbb{Z}\}.$$
Toàn bộ tập hợp các số nguyên $\mathbb{Z}$ rơi vào $m$ các lớp mục tiêu modulo $m$. Tập hợp tất cả các lớp này được ký hiệu là $F_m : F_m = \{0, 1, ..., m - 1\}$. Khi nghiên cứu các câu hỏi liên quan đến tính chia hết cho $m$, tốt hơn là xử lý tập hữu hạn $F_m$ hơn là tập vô hạn $Z$.

Để giải bài toán về tính chia hết, bạn cần có khả năng thực hiện các phép toán tranh luận trên các lớp mục tiêu. Hãy bắt đầu với phép cộng. Nó được định nghĩa rất đơn giản - trong mỗi thuật ngữ (hãy nhớ rằng lớp mục tiêu là một tập hợp vô hạn các số nguyên), nó lấy một đại diện và cộng chúng lại, sau đó xem xét tổng đó rơi vào loại mục tiêu nào. Nó được gọi là tổng của các lớp này. Ví dụ: hãy cộng các lớp mục tiêu $\bar{4}$ và $\bar{5}$ modulo 6. Để thực hiện việc này, hãy chọn một đại diện trong đó. Để không phải suy nghĩ quá lâu, chúng ta hãy lấy phần còn lại $\bar{4}$ và $\bar{5}$, phần này đã đặt tên cho các lớp. Tổng của chúng là 9. Nhưng $9 \equiv 3 \pmod{6}$ và do đó $\bar{4} + \bar{5} = \bar{3}$. Nếu các lớp mục tiêu không nằm trong $F_6$ mà nằm trong $F_8$, thì tổng sẽ khác: $\bar{4} + \bar{5} = \bar{1}$. Và trong $F_9$ $\bar{4} + \bar{5} = \bar{0}$.

Để chấm dứt vấn đề cộng các lớp người sống sót, cũng cần phải chứng minh rằng nếu chọn những đại diện khác thì tổng sẽ không thay đổi. Điều này suy ra từ định lý sau:

Định lý 1. Nếu $a \equiv a_1 \pmod{m}$ và $b \equiv b_1 \pmod{m}$ thì $a + b \equiv a_1 + b_1 \pmod{m}$.

Bằng chứng. Vì $a \equiv a_1 \pmod{m}$, $a = a_1 + km$, trong đó $k \in \mathbb{Z}$ và vì $b \equiv b_1 \pmod{m}$, $b = b_1 + lm$, trong đó $l \in \mathbb{Z}$. Do đó, $a + b = a_1 + b_1 + (k + l)m$, trong đó $k + l \in \mathbb{Z}$ và $a + b \equiv a_1 + b_1 \pmod{m}$.

Chúng tôi đã giảm việc bổ sung các lớp mục tiêu thành việc bổ sung số lượng. Do đó, các lớp Vytsel có tính tính toán và kết hợp, tức là $a + b = \bar{b} + \bar{a}$ và $(\bar{a} + \bar{b}) + \bar{c} = \bar{a} + (\bar{b} + \bar{c})$, việc thêm lớp $\bar{0}$ không làm thay đổi lớp Vytsel, tức là $\bar{a} + \bar{0} = \bar{a}$, v.v.

Phép trừ và phép nhân của các lớp mục tiêu được xác định theo cùng một cách - trong lớp, người ta chọn một đại diện và thực hiện các thao tác trên chúng. Và ở đây kết quả không phụ thuộc vào sự lựa chọn

⟦folio 6⟧

ra đại diện (tự mình chứng minh). Hơn nữa, các điều kiện sau là đúng:

Nếu $P(x)$ là đa thức có hệ số nguyên $u$ $a \equiv a_1$ (mod $m$), thì $P(a) \equiv P(a_1)$ (mod $m$). Hãy cố gắng tự mình chứng minh điều đó.

Các thuộc tính của các phép toán trừ và nhân của các lớp trừ cũng rất giống với các thuộc tính của các phép toán này đối với số nguyên (với một ngoại lệ; sẽ nói thêm về điều đó bên dưới).

Nhiệm vụ chia hết

Vì các lớp phép trừ modulo $m$ có liên quan chặt chẽ với số dư khi chia cho $m$, nên hầu hết tất cả bài toán trong đó người ta quyết định về khả năng chia hết của các số đều có thể được giải một cách thuận tiện bằng cách so sánh.

Ví dụ 1. Tìm số dư khi $212^{1978}$ chia cho 7.

Vì chia 212 cho 7 dư 2, $212 \equiv 2$ (mod 7). Theo sau đó là $212^{1978} \equiv 2^{1978}$ (mod 7). Bây giờ hãy lưu ý rằng $2^3 = 8 \equiv 1$ (mod 7). Nhưng 1978 = $659 \times 3 + 1$. Điều này có nghĩa là từ $2^3 \equiv 1$ (mod 7) nó theo sau $2^{1978} = (2^3)^{659} \cdot 2 \equiv 1^{659} \cdot 2 = 2$ (mod 7). Do đó, khi $212^{1978}$ chia cho 7 thì dư là 2.

Ví dụ 2. Hãy rút ra bài kiểm tra tính chia hết cho 9.

Vì $10 \equiv 1$ (mod 9), với bất kỳ $k$ nào chúng ta có $10^k \equiv 1$ (mod 9). Nhưng sau đó

$$a_0 \cdot 10^n + a_1 \cdot 10^{n-1} + \dots + a_n \equiv a_0 + a_1 + \dots + a_n \pmod{9}.$$

Điều này có nghĩa là các số $N = a_0 \cdot 10^n + \dots + a_n$ và $M = a_0 + \dots + a_n$ có cùng số dư khi chia cho 9. Cụ thể, $N$ chia hết cho 9 khi và chỉ khi số $M$ (tổng các chữ số của số $N$) chia hết cho 9.

Ví dụ 3. Hãy chứng minh rằng bình phương của một số tự nhiên bất kỳ đều chia hết cho 9 hoặc khi chia cho 3 dư 1.

Thật vậy, nếu $x \equiv 0$ (mod 3), thì $x^2$ chia hết cho 9. Nếu $x \equiv 1$ (mod 3) hoặc $x \equiv 2$ (mod 3), thì $x^2 \equiv 1$ (mod 3), vì $1^2 = 1$ và $2^2 = 4 \equiv 1$ (mod 3).

Ví dụ 4. Tìm chữ số cuối cùng của số $7^{71}$

Chúng ta cần tìm số dư khi chia số $7^{77}$ cho 10. Nhưng $7^2 = 49 \equiv -1$ (mod 10), và do đó $7^4 \equiv (-1)^2 \equiv 1$ (mod 10). Hãy tìm phần dư của phép chia số mũ $7^7$ cho 4. Vì $7 \equiv -1$ (mod 4), $7^7 \equiv (-1)^7 \equiv -1 \equiv 3$ (mod 4), và do đó $7^7 = 4m + 3$. Do đó, $7^{77} = (7^4)^m \cdot 7^3 \equiv (-3)^3 \equiv -27 \equiv 3$ (mod 10). Điều này có nghĩa là các số $7^{77}$ và 3 có cùng chữ số cuối cùng, tức là $7^{77}$ kết thúc bằng 3.

Phân chia các lớp trừ

Chia lớp trừ $\bar{b}$ thành lớp trừ $\bar{a}$ nghĩa là tìm lớp trừ $\bar{x}$ sao cho $\bar{ax} = \bar{b}$. Đối với số nguyên bài toán phép chia không phải lúc nào cũng giải được nhưng nó có thể được giải theo một cách duy nhất. Điều này là do tích của hai số nguyên chỉ bằng 0 trong trường hợp có ít nhất một trong các thừa số bằng 0. Nhưng trong $F_m$ nó được chia khác. Nhìn vào bảng nhân của $F_6$, chúng tôi lưu ý rằng các số 0 được tạo trong đó không chỉ ở hàng đầu tiên và cột đầu tiên (trong đó một trong các thừa số bằng 0).

Tích $\bar{2} \cdot \bar{3}$, $\bar{3} \cdot \bar{4}$ cũng bằng 0, mặc dù các thừa số khác 0. Như người ta nói, $F_6$ có ​​ước số bằng 0 (lớp trừ $\bar{a}$ được gọi là ước số 0 nếu nó khác 0, nhưng có một lớp $\bar{b} \neq \bar{0}$ sao cho $\bar{a} \cdot \bar{b} = \bar{0}$). Trong $F_6$ các ước số 0 hóa ra là nguyên tố cùng nhau với mô hình 6. Điều này cho thấy tính đúng đắn của định lý sau:

| | $\bar{0}$ | $\bar{1}$ | $\bar{2}$ | $\bar{3}$ | $\bar{4}$ | $\bar{5}$ |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $\bar{0}$ | $\bar{0}$ | $\bar{0}$ | $\bar{0}$ | $\bar{0}$ | $\bar{0}$ | $\bar{0}$ |
| $\bar{1}$ | $\bar{1}$ | $\bar{2}$ | $\bar{3}$ | $\bar{4}$ | $\bar{5}$ | $\bar{5}$ |
| $\bar{2}$ | $\bar{0}$ | $\bar{2}$ | $\bar{4}$ | $\bar{0}$ | $\bar{2}$ | $\bar{4}$ |
| $\bar{3}$ | $\bar{0}$ | $\bar{3}$ | $\bar{0}$ | $\bar{3}$ | $\bar{0}$ | $\bar{3}$ |
| $\bar{4}$ | $\bar{0}$ | $\bar{4}$ | $\bar{2}$ | $\bar{0}$ | $\bar{4}$ | $\bar{2}$ |
| $\bar{5}$ | $\bar{0}$ | $\bar{5}$ | $\bar{4}$ | $\bar{3}$ | $\bar{2}$ | $\bar{1}$ |

⟦folio 7⟧

Định lý 2. Lớp thặng dư $a$ trong $F_m$ không phải là ước số 0 khi và chỉ khi $a$ và $m$ nguyên tố cùng nhau.

Bằng chứng. Cho $a$ và $m$ nguyên tố cùng nhau. Nếu $a \cdot b = 0$ thì số $ab$ chia hết cho $m$. Tuy nhiên, do tính đơn giản lẫn nhau của $a$ và $m$, điều này chỉ có thể xảy ra khi $b$ chia hết cho $m$, tức là $b = 0$. Điều này có nghĩa là $ab = 0$ chỉ dành cho $b = 0$, nghĩa là $a$ không phải là ước số của 0.

Bây giờ giả sử rằng ước số chung nhất của các số $a$ và $m$ khác với 1, $a = a_1d$, $m = m_1d$, $d > 1$. thì số $m_1 < m$ là một số nguyên và khác với $m$ và do đó $m_1 \neq 0$. Nhưng $am_1 = a_1dm_1 = a_1m$, đó là $am_1 = 0$. Vậy $a$ là ước số bằng 0.

Nếu số $a$ là nguyên tố cùng nhau với mô hình $m$ thì tất cả các số từ lớp dư lượng $a$ đều nguyên tố cùng nhau với $m$. Trong trường hợp này, lớp $a$ được cho là nguyên tố cùng nhau với $m$.

Định lý 2 ngụ ý Hệ quả 1 quan trọng. Nếu lớp thặng dư $a$ nguyên tố cùng nhau với $m$, thì $F_m$ có ​​thể được chia duy nhất cho $a$, nghĩa là, với bất kỳ $b \in F_m$ nào thì phương trình $ax = b$ có một và chỉ một lời giải.

Đầu tiên chúng ta chứng minh rằng phương trình này không thể khác lời giải. Nếu $ax_1 = b$ và $ax_2 = b$ thì $a(x_1 - x_2) = 0$ và vì $a$ không phải là ước số 0, nên $x_1 - x_2 = 0$, tức là $x_1 = x_2$. Điều này có nghĩa là chỉ có thể có một lời giải.

Vẫn còn phải chứng minh rằng lời giải tồn tại.

Chúng ta vừa chứng minh rằng phương tiện của các lớp dư lượng $a \cdot 0, a \cdot 1, \ldots, a(m-1)$ là không giống nhau. Điều này có nghĩa là đây là các lớp giống nhau $0, 1, \ldots, m-1$, chỉ có lẽ được thực hiện theo một thứ tự khác. Và sau đó đối với bất kỳ lớp nào $b$ đều có một lớp $x$ sao cho $a \cdot x = b$.

Hệ quả đã được chứng minh có thể được xác nhận bằng bảng nhân sử dụng mô hình $6$ - nó cho thấy rằng chỉ trong các hàng dành cho các lớp $1$ và $5$ mới tìm thấy tất cả các lớp dư lượng. Các dòng khác chỉ chứa một phần của các lớp: trong các dòng cho $2$ và $4$ có các lớp $0, 2, 4$, và trong dòng cho $3$ có các lớp $0$ và $3$. Thật dễ hiểu cách mọi thứ hoạt động trong trường hợp chung:

Hệ quả 2. Nếu $(a, m) = d^*$ thì phương trình $ax = b$ chỉ có lời giải nếu $b$ chia hết cho $d$. Trong trường hợp này, số lời giải bằng $d$.

Chúng tôi để người đọc chứng minh nhận định này.

Trong trường hợp phương trình mô hình là số nguyên tố, nó có thể được chia thành bất kỳ lớp dư lượng khác 0 nào - trong trường hợp này, tất cả các lớp đó đều là nguyên tố cùng nhau với mô hình. Do đó, ví dụ, trong bảng nhân theo mô hình 5, một hàng bao gồm các số 0 và phần còn lại chứa tất cả các lớp dư lượng, mỗi lớp một lần.

Định lý Fermat và Euler

Trong lý thuyết số, cái gọi là Định lý nhỏ Fermat thường được sử dụng:

Định lý 3. Nếu $p$ là số nguyên tố và $a$ không chia hết cho $p$ thì số dư khi chia $a^{p-1}$ cho $p$ là 1.

Theo một cách khác, nó có thể được xây dựng như sau:

Định lý 3'. Nếu $a$ là lớp dư lượng khác 0 theo mô hình đơn giản $p$, thì $a^{p-1} = 1$.

Bằng chứng. Vì $0 < a < p$ và mẫu $p$ là số nguyên tố nên $a$ và $m$ là số nguyên tố cùng nhau. Do đó, các lớp dư lượng $a \cdot 1, a \cdot 2, \ldots, a(p-1)$ giống như $1, 2, \ldots, p-1$, chỉ

$*)$ $(a, m)$ là ước số chung nhất của các số $a$ và $m$.
