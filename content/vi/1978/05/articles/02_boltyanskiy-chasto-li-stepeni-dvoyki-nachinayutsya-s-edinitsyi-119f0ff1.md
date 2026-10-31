---
id: 1978-5-boltyanskiy-chasto-li-stepeni-dvoyki-nachinayutsya-s-edinitsyi-119f0ff1
issue: kvant_1978_5
year: 1978
number: "5"
title: Sức mạnh của hai có thường bắt đầu bằng một không?
authors:
  - Болтянский В. Г.
rubric: osnovnye-stati
page_first: 4
page_last: 8
page_labels: 2, 4, 6
tag: GLE7
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 8cfbfe80faac20a135c8b7e7cd779e68286b4fe9a342b113d9e0bb6aeec5527f
prompt_sha256: draft-1
translated_from: content/ru/1978/05/articles/02_boltyanskiy-chasto-li-stepeni-dvoyki-nachinayutsya-s-edinitsyi-119f0ff1.md
source_content_sha256: 6a0557be44f15c8e056cf405895e1e8f515ea49c1c41fd5d509391b3ac00cdee
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

V. Boltyansky

Sức mạnh của hai có thường bắt đầu bằng một không?

Sản xuất bài toán
Các lũy thừa trung bình của hai số bắt đầu bằng một xuất hiện lặp đi lặp lại. Chúng xảy ra thường xuyên như thế nào? Nói cách khác, xác suất để một số được chọn ngẫu nhiên từ các số $2^1, 2^2, \ldots, 2^n$ bắt đầu bằng chữ số 1 là $a_n/n$ là bao nhiêu. Xác suất này phụ thuộc vào $n$, tức là vào số lũy thừa bậc nhất của 2 đã được lấy. Giới hạn

$$p_1 = \lim_{n \to \infty} \frac{a_n}{n},$$

(nếu nó tồn tại) và được gọi là xác suất để một số tự nhiên bất kỳ chia hết cho 3?

1. Xác suất để một chữ số tùy ý trong phép khai triển thập phân của số $\frac{161}{222}$ là số năm là bao nhiêu? Gấp đôi?

2. Xác suất để một số tự nhiên bất kỳ là số chính phương là bao nhiêu?

⟦folio none⟧

Vượt quá giới hạn (1)

Trong số các số có hai chữ số là lũy thừa của hai, có chính xác một số (cụ thể là 16) bắt đầu bằng một. Trong số lũy thừa ba chữ số của hai, có đúng một số (cụ thể là 128) bắt đầu bằng một. Điều tương tự cũng đúng với lũy thừa bốn chữ số của hai.

Nói chung, đối với $k > 1$, trong số các số $k$ chữ số là lũy thừa của hai, có chính xác một số bắt đầu bằng chữ số 1. Thật vậy, số $k$ chữ số nhỏ nhất là lũy thừa của hai nhất thiết phải bắt đầu bằng một (nếu không, chia cho 2, chúng ta sẽ nhận được rằng lũy ​​thừa trước đó của hai là số $k$ chữ số). Không có số nào khác bắt đầu bằng số 1 trong số lũy thừa $k$ chữ số của hai: lũy thừa tiếp theo của hai sẽ có số 2 hoặc 3 ở vị trí đầu tiên, số tiếp theo sẽ có số cao hơn nữa, cho đến khi chúng ta nhận được số $(k+1)$ chữ số.

Từ điều trên, suy ra rằng nếu số $2^n$ là $m$ chữ số, thì trong số các số $2^1, 2^2, \dots, 2^n$ có ​​chính xác $m-1$ số bắt đầu bằng một, tức là $a_n = m-1$. Nhưng câu lệnh "số $2^n$ là $m$ chữ số" có nghĩa là

$$10^{m-1} \leq 2^n < 10^m,$$

đó là

$$m-1 \leq n \lg 2 < m.$$

Nhớ rằng $a_n = m-1$, chúng ta nhận được

Hình 1.

$$\lg 2 - \frac{1}{n} < \frac{a_n}{n} \leq \lg 2,$$

và do đó

$$p_1 = \lim_{n \to \infty} \frac{a_n}{n} = \lg 2 = 0,30103...$$

Vì vậy, hơn 30% sức mạnh của hai đều bắt đầu bằng một.

3 adach và

4. Chúng ta hãy biểu thị bằng $p_q$ xác suất mà lũy thừa tùy ý của hai bắt đầu bằng số $q^*$. Chứng minh đẳng thức

$$p_2 + p_3 = p_1, \quad p_4 + p_5 = p_2, \quad p_6 + p_7 = p_3, \quad p_8 + p_9 = p_4.$$

5. Chứng minh rằng $p_4 = 1-3 \lg 2 = 0,096...$

Như bạn có thể thấy, lũy thừa của hai bắt đầu bằng số 4 ít hơn ba lần so với số 1 (Hình 2).

Hình 2.

Chung bài toán

Xác suất để lũy thừa tùy ý của một số tự nhiên cho trước $l$ bắt đầu (theo ký hiệu thập phân) bằng chữ số $q$ là bao nhiêu?

Đặt số $l^n$ bắt đầu bằng ký hiệu thập phân bằng chữ số $q$, tức là.

$$q \cdot 10^m \leq l^n < (q+1) \cdot 10^m,$$

trong đó $m$ là một số tự nhiên. Chia các bất đẳng thức này cho $q \cdot 10^m$ và tiếp tục gieo vần theo cơ số 10, ta được:

$$0 \leq (n \lg l - \lg q) - m < \lg \frac{q+1}{q}.$$ (2)

Vì số bên phải nhỏ hơn một ($\frac{q+1}{q} = 1 + \frac{1}{q} \leq 2 < 10$) nên bất đẳng thức (2) có nghĩa là phần phân số của số $n \lg l - \lg q$ nhỏ hơn $\lg \frac{q+1}{q}$ (hãy nhớ rằng phần phân số)

*) Sự tồn tại của số $p_q$ suy ra điều gì sau đây.

⟦folio 4⟧

số $x$ là hiệu giữa số $x$ và phần nguyên của nó: $\{x\} = x - [x]$ và phần nguyên $x$ là số nguyên lớn nhất không vượt quá $x$). Ngược lại, nếu phần phân số của số $n \lg l - \lg q$ nhỏ hơn $\lg \frac{q+1}{q}$, nghĩa là, nếu đối với một số tự nhiên $m$ bất đẳng thức (2) nào đó được thỏa mãn thì $l^n$ bắt đầu bằng ký hiệu thập phân với số $q$. Do đó, bài toán đã cho tương đương với giá trị sau: xác suất để bất kỳ số tự nhiên nào $n$ là bao nhiêu

$$\{n \lg l - \lg q\} < \lg \frac{q+1}{q}$$

bài toán cuối cùng này sẽ giúp chúng ta giải quyết

Định lý phần phân số $x$. Giả sử $\alpha, \beta$ là số thực, hơn nữa, số $\alpha$ là số vô tỷ và $I$ là một khoảng có độ dài $h$ chứa trong khoảng [0, 1]. Khoảng cách đến chuỗi vô hạn $\alpha + \beta, 2\alpha + \beta, \dots, n\alpha + \beta, \dots$. Xác suất để bất kỳ số nào trong dãy này có phần phân số thuộc khoảng $I$ đều bằng $h$.

Chúng tôi sẽ chứng minh định lý này ở cuối bài viết, nhưng bây giờ chúng tôi sẽ chỉ ra cách nó áp dụng cho lời giải bài toán của chúng tôi.

Trước hết, hãy lưu ý rằng nếu $l$ là lũy thừa của mười thì tất cả lũy thừa của $l$ đều bắt đầu bằng chữ số $1$, tức là trong trường hợp này bài toán là tầm thường.

Nếu $l$ không phải là lũy thừa của mười thì số $\alpha = \lg l$ chính là hiệu. Theo định lý phần phân số, xác suất để một số tùy ý được lấy từ chuỗi $n \lg l - \lg q$ ($n = 1, 2, \dots$) có phần phân số thuộc khoảng $$\left[0, \lg \frac{q+1}{q}\right],$$ bằng $$\lg \frac{q+1}{q}.$$ Điều này cho ra lời giải được xem xét ở trên bài toán: xác suất mà một số toàn cầu tùy ý $l$ (không phải là lũy thừa của mười) bắt đầu bằng số đó $q$, bằng $$\lg \frac{q+1}{q}.$$

Lưu ý rằng xác suất này không phụ thuộc vào $l!$. Ví dụ, lũy thừa của hai và lũy thừa của ba thường xuyên như nhau (cụ thể là với xác suất lg 2) bắt đầu bằng số 1.

3 adach và

6. Chứng minh rằng nếu số tự nhiên $l$ không phải là lũy thừa của mười thì số $\lg l$ chơi được.

7. Tính các xác suất $p_2, \dots, p_9$ cho trong bài toán 4. Đưa ra chứng minh mới về các đẳng thức chứa trong đó.

8. Xác suất để một lũy thừa tùy ý của hai bắt đầu bằng số 1000 (Hình 3) là bao nhiêu?

Hình 3.

9. Xác suất để một lũy thừa tùy ý của $l$ (không phải là lũy thừa của mười) bắt đầu bằng tổ hợp chữ số $q_1 q_2 \dots q_r$ (trong đó $q_1 \neq 0$) là bao nhiêu? Từ đó suy ra rằng lũy ​​thừa của số $l$ có thể bắt đầu bằng tổ hợp các chữ số $q_1 q_2 \dots q_r$ ($q_1 \neq 0$).

10. Chứng minh các khẳng định sau:

a) Xác suất để lũy thừa tùy ý của số $l$, không phải là lũy thừa của mười, có chữ số thứ hai là 0, bằng

$$p_0^{(2)} = \lg(11 \cdot 21 \cdot 31 \cdot \dots \cdot 91) - \lg(9!) - 9.$$

Gợi ý: $p_0^{(2)}$ là tổng các xác suất mà lũy thừa tùy ý của số $l$ bắt đầu bằng các tổ hợp 10, 20, ..., 90.

6) Xác suất để lũy thừa tùy ý của $l$ không phải là lũy thừa của mười, chữ số thứ $k$ (từ bên trái) là $q$ (trong đó $k > 1$, $q = 0, 1, \dots, 9$) là:

$$p_k^{(2)} = \sum_{i=10}^{k-1} \lg \left(1 + \frac{1}{q+10i}\right).$$

11*. Sử dụng kết quả bài toán 10, 6), chứng minh rằng $\lim_{k \to \infty} p_k^{(2)} = 1/10$. Do đó, đối với $k$ đủ lớn, mỗi xác suất $p_k^{(2)}, p_1^{(2)}, \dots, p_9^{(2)}$ dưới dạng góc nhỏ sẽ khác với 1/10.

⟦folio 6⟧

số hạng của cấp số thứ hai, rằng mô hình chênh lệch của chúng nhỏ hơn 0,000001?

16. Chúng tôi gọi khu rừng niềm vui là sự kết hợp của tất cả các vòng tròn có bán kính $\varepsilon$, tâm của chúng là các điểm có tọa độ nguyên. Chứng minh rằng nếu một đường thẳng tạo thành một góc $\varphi$ với trục x, tiếp tuyến của nó vô tỉ thì nó nhất thiết phải cắt rừng (dù $\varepsilon$ nhỏ đến đâu; Hình 5).

Chứng minh định lý

Bây giờ chúng ta chuyển sang chứng minh định lý trên phần phân số.

Hãy lấy một số tự nhiên tùy ý $r$. Điểm $\frac{1}{r}, \frac{2}{r}, \dots, \frac{r-1}{r}$ chia đoạn $[0, 1]$ thành $r$ đoạn có độ dài $\frac{1}{r}$. Hãy gọi những phân đoạn này là "ô" và gọi phần phân số của các số $\alpha, 2\alpha, \dots, (r+1)\alpha$ "thỏ rừng"*). Vì có $r$ “ô” và $r+1$ “thỏ rừng”, nên có hai “thỏ rừng” nằm trong một ô, tức là có $p'$ và $p''$ ($p' > p''$) tự nhiên sao cho phần phân số của các số $p' \alpha$ và $p'' \alpha$ khác nhau ít hơn $\frac{1}{r}$. Điều này có nghĩa là $|(p' \alpha - p'' \alpha) - m| < \frac{1}{r}$ đối với một số nguyên $m$. Bằng cách đặt $p = p' - p''$, chúng ta có thể viết: $|p \alpha - m| = \varepsilon$, trong đó $\varepsilon < \frac{1}{r}$. Lưu ý rằng $\varepsilon \neq 0$, vì $\alpha$ là vô tỉ. Chúng ta hãy biểu thị bằng $s$ số tự nhiên nhỏ nhất lớn hơn $\frac{1}{\varepsilon}$, tức là $s - 1 \leqslant \frac{1}{\varepsilon} < s$.

Xét $s$ số hạng liên tiếp của cấp số cộng có hiệu $p \alpha$:

$$\gamma + p \alpha, \gamma + 2p \alpha, \dots, \gamma + sp \alpha,$$

(3) trong đó $\gamma$ là một số thực. Chúng ta hãy biểu thị phần phân số của số (3) bằng $x_1, x_2, \dots, x_s$. Do sự bằng nhau $|p \alpha - m| = \varepsilon$, các số $x_1, x_2, \dots, x_s$ cách nhau $\varepsilon$ (Hình 6). Do bất đẳng thức $\frac{1}{s} < \varepsilon \leqslant \frac{1}{s-1}$ khoảng cách giữa các điểm $x_1$

*) Thuật ngữ này liên quan đến nguyên lý Dirichlet («Kvant», 1977, số 2, trang 17). Định lý phần phân số có thể được gọi là “nguyên lý Dirichlet cho số lượng thỏ rừng vô hạn”.

Hình 6.

và $x_s$ trong Hình 6, 6 nhỏ hơn $\varepsilon$. Từ điều trên, suy ra rằng số điểm $x_1, x_2, \dots, x_s$ rơi trên đoạn $l$ có độ dài $h$ nằm giữa số $\frac{h}{\varepsilon} - 1$ và $\frac{h}{\varepsilon} + 2$, tức là giữa $sh-2$ và $sh+2$ (lưu ý rằng $h < 1$).

Bây giờ chúng ta hãy lấy $ps$ các số hạng liên tiếp $b_1, b_2, \dots, b_{ps}$ của một số cấp số cộng có hiệu $\alpha$ (tức là $b_{i+1} = b_i + \alpha$). Chúng ta hãy sắp xếp chúng dưới dạng một cái bàn; nó thể hiện sự tiến triển của dạng (3). Vì số dòng là $p$, nên số các số hạng của cấp số nhân $b_1, b_2, \dots, b_{ps}$ đang được xem xét, các phần phân số của chúng nằm trong khoảng $l$, được chứa giữa số $p (sh-2)$ và $p (sh+2)$.

Cuối cùng, đặt $n$ là một số tự nhiên tùy ý lớn hơn $rps$. Chia $n$ cho $ps$ với phần dư, ta được $n = lps + q$, trong đó $l \geqslant r$, $0 \leqslant q < ps$. Do đó, từ số $\alpha + \beta, 2\alpha + \beta, \dots, n\alpha + \beta$ chúng ta có thể lấy $l$ lần $ps$ số hạng liên tiếp của cấp số cộng với hiệu là $\alpha$,
