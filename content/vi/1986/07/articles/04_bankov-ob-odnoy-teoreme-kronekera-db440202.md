---
id: 1986-7-bankov-ob-odnoy-teoreme-kronekera-db440202
issue: kvant_1986_7
year: 1986
number: "7"
title: Về một định lý Kronecker
authors:
  - Банков К. Г.
rubric: osnovnye-stati
page_first: 7
page_last: 9
page_labels: 5-7
tag: 57C8
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c43fe363b52edd4a4d68f17e88a0e88e2d3b51d75de0c50f91a92d640cc1ea15
prompt_sha256: draft-1
translated_from: content/ru/1986/07/articles/04_bankov-ob-odnoy-teoreme-kronekera-db440202.md
source_content_sha256: 5fd8f7e68c8753d423f508c22b42d4ee9ccb69b8d06963a288d02f02ecf87577
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 5⟧

Về một định lý
Kronecker

K. G. BANKOV (NRB)

Định lý được thảo luận ở đây đóng một vai trò nổi bật trong lý thuyết số. Tuy nhiên, điều thú vị đối với chúng tôi là vì một lý do khác: với sự trợ giúp của nó, có thể giải một cách đơn giản các công thức cơ bản nhưng về cơ bản là khó bài toán. Trước khi trình bày định lý, chúng ta sẽ xem xét hai bài toán như vậy.

Bài 1. Chứng minh tồn tại lũy thừa của 2 có ký hiệu thập phân bắt đầu bằng chữ số 1986.

Để giải bài toán này, chúng ta cần tìm lũy thừa $m \in N$ sao cho $10^n \cdot 1986 < 2^m < 10^n \cdot 1987$ đối với một số $n$. Lấy logarit cơ số 10, ta được

$$\lg 1986 + \lg 10^n < \lg 2 < \lg 1987 + \lg 10^n,$$

hoặc

$$\lg 1986 < \lg 2 - n < \lg 1987.$$

Bài toán sẽ được giải nếu chúng ta tìm được các số tự nhiên $n$ và $m$ sao cho một trong các số có dạng

$$\lg 2 - n, m, n \in N$$

(1)

rơi vào một khoảng nhỏ (lg 1986, lg 1987).

Bài toán 2. Tại các đỉnh của một lưới vuông nguyên có vẽ

những con mèo nhỏ giống hệt nhau (hình 1). Chứng minh rằng tia $y = kx$, $x \geq 0$ sẽ cắt nhau, ngoài tia ở giữa thì có ít nhất một con mèo nữa nếu số $k$ là số vô tỉ.

Đặt $2\varepsilon_0$ là “chiều rộng của con mèo”, nói cách khác, để con mèo trung tâm cắt trục $Ox$ dọc theo đoạn $[-\varepsilon_0; \varepsilon_0]$. Để xác định điều này, chúng ta giả sử rằng chùm tia nằm ở ô vuông đầu tiên (các trường hợp còn lại tương tự). Khi đó tia cắt các đường thẳng $y = 1, 2, \dots, n, \dots$ tại các điểm có hoành độ $\alpha, 2\alpha, \dots, n\alpha, \dots$, trong đó $\alpha = 1/k$. Vấn đề sẽ được giải quyết nếu chúng ta tìm thấy $n$ và $m$ tự nhiên sao cho

$$m - \varepsilon_0 < n\alpha < m + \varepsilon_0,$$

hoặc

$$-\varepsilon_0 < n\alpha - m < \varepsilon_0,$$

⟦folio 6⟧

nghĩa là, chúng ta có thể thiết lập rằng một trong các số có dạng
$$n\alpha - m, n, m \in \mathbb{N},$$
(2)
phục vụ trong một khoảng thời gian nhỏ $(-\varepsilon_0, \varepsilon_0)$.

Ý tưởng đáng chú ý của định lý Kroneckar*) là các tập hợp như (1) và (2) chứa các số nằm trong bất kỳ khoảng nào. Để đưa ra một công thức chính xác của định lý này, chúng ta cần một định nghĩa.

Một tập hợp số $A \subset \mathbb{R}$ được cho là dày đặc ở mọi nơi (trong $\mathbb{R}$) nếu bất kỳ khoảng nào chứa một phần tử của tập hợp này. Nói cách khác, $A$ dày đặc ở mọi nơi trong $\mathbb{R}$ nếu với mọi số $x, y \in \mathbb{R}$, $x < y$ đều tồn tại $a \in A$ sao cho $x < a < y$.

Bài tập
1. Cho biết tập hợp nào sau đây dày đặc ở mọi nơi trong $\mathbb{R}$: a) tất cả các số hữu tỷ; b) tất cả các số vô tỷ; c) tất cả các số có dạng $n + 5m/17$ ($n, m \in \mathbb{Z}$); d) tất cả các số có dạng $n + k/m$ ($n, k, m \in \mathbb{Z}$).
2. Đặt tập $A$ dày đặc ở mọi nơi trong $\mathbb{R}$ và $r \neq 0$ một số thực. Chứng minh rằng khi đó các tập hợp
$$B = \{a + r; a \in A\}, C = \{ra, a \in A\}$$
điều tương tự dày đặc ở mọi nơi trong $\mathbb{R}$.

**Định lý Kronekar.** Đối với một số vô tỉ tùy ý $a \neq 0$ thì tập hợp
$$\{m\alpha + n; m, n \in \mathbb{Z}\}$$
(3) dày đặc khắp nơi trong $\mathbb{R}$.

Bằng chứng. Chúng ta cần chứng minh rằng với hai số $x, y$ bất kỳ mà $x < y$ tồn tại các số có dạng $m\alpha + n$, trong đó $m, n \in \mathbb{Z}$ sao cho $x < m\alpha + n < y$. Chúng ta biểu thị bằng $\delta$ độ dài của khoảng $\Delta = (x; y)$ và chia khoảng [0; 1] thành một số hữu hạn các khoảng $\Delta_1, \Delta_2, \dots, \Delta_n$, mỗi khoảng có độ dài nhỏ hơn $\delta$. Bây giờ chúng ta hãy lưu ý rằng đối với bất kỳ số nguyên $m$ nào, rất lớn, đều có một số nguyên $n$ mà số $m\alpha + n$ nằm trên khoảng [0; 1]. Vì có vô số số nguyên và đoạn [0; 1] được chia thành một số hữu hạn các khoảng, có các số nguyên $m_1, m_2, n_1, n_2$ mà $m_1 \neq m_2$ và các số $m_1\alpha + n_1$ và $m_2\alpha + n_2$ nằm trong cùng một khoảng $\Delta_i$. Điều này có nghĩa là số $a = (m_1 - m_2)\alpha + (n_1 - n_2)$ có giá trị abscylotic nhỏ hơn $\delta$. Hơn nữa, đẳng thức $a = 0$ không thể đúng vì nó ngụ ý rằng $a = \frac{n_2 - n_1}{m_1 - m_2}$ là một số hữu tỉ. Từ kết quả trên, suy ra rằng một số bội số của $a$, cũng có dạng $m\alpha + n$, không phải số nguyên, sẽ thuộc về $\Delta = (x; y)$; định lý đã được chứng minh.

Bình luận. Định lý vẫn đúng nếu thay thế tập (3) bằng tập
$$\{m\alpha - n; m, n \in \mathbb{N}\}.$$

Điều này dễ dàng được suy ra từ định lý đã được chứng minh; chúng tôi để lại phần kết luận như một bài tập cho người đọc.

Bây giờ quay lại tập (1) và (2), chúng ta thấy rằng chúng thỏa mãn các điều kiện của định lý: bài toán 1 và 2 nhờ đó được giải. (Chúng ta coi như đã biết rằng số lg 2 là số vô tỷ; tuy nhiên, việc chứng minh điều này không khó.)

Bài tập 3. Chứng minh rằng trong bài toán về con mèo, điều kiện vô tỉ $k$ không thể bỏ qua.

Chúng ta hãy xem xét thêm một số bài toán, lời giải sử dụng định lý Kronekar.

Bài toán 3. Chứng minh rằng tồn tại bình phương của một số tự nhiên có ký hiệu mô tả bắt đầu bằng bất kỳ chữ số nào đã cho trước đó.

Lời giải. Hãy tìm bình phương của một số tự nhiên có chữ số thập phân đầu tiên là $-a_0a_1...a_s$. Chúng ta hãy biểu thị bằng $A$ số $A = a_0a_1...a_s$. Bây giờ chúng ta hãy tìm một số tự nhiên $n$ sao cho với một số tự nhiên $k$ các bất đẳng thức đúng
$$A \cdot 10^k < n^2 < (A + 1) \cdot 10^k,$$
hoặc lg $A < 2\lg n - k < \lg (A + 1)$.
Nếu chúng ta chọn số $n$ bằng $n = 2^m$ và số $k$ là số chẵn, $k = 2t$ thì lg $A < 2mlg 2 - 2t < \lg (A + 1)$. (5)

Theo định lý thế (xem (4)) và Bài tập 2, tập hợp
$$\{2mlg 2 - 2t; m, t \in \mathbb{N}\}$$ dày đặc ở mọi nơi, và do đó có các số $m$ và $t$ mà (5) đúng. Vấn đề lời giải.

Đối với lời giải bài toán tiếp theo, chúng ta cũng cần câu lệnh sau:

Bổ đề. Nếu hai hàm liên tục có cùng giá trị khi các đối số là các phần tử của cùng một tập dày đặc ở mọi nơi, thì chúng trùng nhau ở mọi nơi.

Bổ đề này mang tính "hình học"; Chứng minh công thức của nó không hấp dẫn (mặc dù không khó) nên chúng tôi không trình bày.

Bài toán 4. Chứng minh rằng hàm số
$$f(x) = \sin x + \sin \pi x$$
không phải veroid.

Lời giải. Giả sử rằng hàm $f$ là không nguyên tố và biểu thị bằng $T \neq 0$ một trong

⟦folio 7⟧

ee thời kỳ. Thế thì bình đẳng
$$\sin \pi(x+T) + \sin \pi\sqrt{2}(x+T) = \sin \pi x + \sin \pi\sqrt{2}x$$
(6)
đúng với mọi số thực $x$. Nếu trong đẳng thức này, chúng ta thay thế $x$ bằng số FourREM tùy ý $2m$, thì chúng ta nhận được
$$\sin \pi T + \sin \pi\sqrt{2}(2m+T) = \sin (\pi\sqrt{2} \cdot 2m).$$
Sử dụng lại tính tuần hoàn của hàm sin, chúng ta thu được đẳng thức
$$\sin \pi T + \sin \pi\sqrt{2}\left(2m + \frac{2n}{\sqrt{2}} + T\right) = \sin \pi\sqrt{2}\left(2m + \frac{2n}{\sqrt{2}}\right),$$
điều này đúng với hai số nguyên bất kỳ $m$ và $n$. Theo định lý của Bài tập 2, tập hợp
$$\left\{ 2m + \frac{2n}{\sqrt{2}}; m, n \text{ — целые числа} \right\}$$
rõ ràng là dày đặc. Điều này có nghĩa là hàm $\sin \pi T + \sin \pi\sqrt{2}(x+T)$ và sin $\pi\sqrt{2}x$ có cùng giá trị khi các đối số của chúng là các phần tử của cùng một tập dày đặc và do đó (theo bổ đề), trùng khớp về mọi mặt, tức là đẳng thức
$$\sin \pi T + \sin \pi\sqrt{2}(x+T) = \sin \pi\sqrt{2}x$$
(7)
đúng với mọi số thực $x$. Trừ (7) cho (6), ta được
$$\sin \pi(x+T) \sin \pi T = \sin \pi x.$$
Trong đẳng thức cuối cùng, chúng ta đặt $x = T$; chúng tôi nhận được
$$\sin 2\pi T - \sin \pi T = \sin \pi T,$$
hoặc
$$\sin \pi T(\cos \pi T - 1) = 0.$$
Từ đẳng thức cuối cùng, $T$ là một số nguyên. Khi đó từ (7) suy ra
$$\sin \pi\sqrt{2}(x+T) - \sin \pi\sqrt{2}x = 0,$$
hoặc
$$\sin \pi\sqrt{2}\frac{T}{2}\cos \pi\sqrt{2}\left(x + \frac{T}{2}\right) = 0.$$
Vì có các giá trị $x$ mà
$$\cos \pi\sqrt{2}\left(x + \frac{T}{2}\right) \neq 0,$$ rồi $\sin \pi\sqrt{2}\frac{T}{2} = 0$; theo đó $\sqrt{2}\frac{T}{2}$ là một số nguyên. Tuy nhiên, mặt khác, $T$ cũng là một số nguyên và $T \neq 0$, có nghĩa là $\sqrt{2}$ là số hữu tỷ, là số sai. Mâu thuẫn thu được chứng tỏ hàm $f$ không tuần hoàn.

Đây là một bài toán khác liên quan đến các hàm được thảo luận ở trên.
Bài toán 5. Chứng minh rằng hàm số
$$f(x) = \sin \pi x + \sin \pi\sqrt{2}x$$
không thể lấy giá trị 2 mà lấy giá trị càng gần số 2 càng tốt.
Lời giải. Nếu chúng ta giả sử rằng $f(x) = 2$ đối với một số $x$, thì đẳng thức đồng thời sẽ giữ nguyên
$$\sin \pi x = 1$$ và $\sin \pi\sqrt{2}x = 1$, do đó người ta không thể hiện rằng số $\sqrt{2}$ là hợp lý, nhưng điều này là sai. Do đó, $f(x) < 2$ với bất kỳ số nào.
Nếu $x$ là số tùy ý có dạng $2m + \frac{1}{2}$, trong đó $m$ là số nguyên, thì hàm $f$ có dạng
$$f(x) = 1 + \sin \pi\sqrt{2}\left(2m + \frac{1}{2}\right).$$
Hãy chứng minh rằng có thể tìm được số nguyên $m$ sao cho
$$\sin \pi\sqrt{2}\left(2m + \frac{1}{2}\right)$$ gần tùy ý với số 1. Xét tính liên tục của hàm sin, chỉ cần tìm các số nguyên $m$ và $n$ sao cho số $\sqrt{2}\left(2m + \frac{1}{2}\right)$ gần tùy ý với số $2n + \frac{1}{2}$. Do đó, chỉ cần chứng minh rằng với mọi $\varepsilon$ dương bất kỳ đều có các số nguyên $m$ và $n$ thỏa mãn
$$2n + \frac{1}{2} - \varepsilon < \sqrt{2}\left(2m + \frac{1}{2}\right) < 2n + \frac{1}{2} + \varepsilon.$$
Chúng ta hãy biến đổi các bất đẳng thức số nguyên cuối cùng về dạng
$$1 - 2\varepsilon - \sqrt{2} < 4m\sqrt{2} - 4n < 1 + 2\varepsilon - \sqrt{2}.$$
Bây giờ tất cả chúng ta đều làm theo định lý và bài tập 2.
Bài toán 6. Tìm tất cả các hàm số thực liên tục $f$ sao cho $f(x) = f(x+1) = f(x+\sqrt{2})$.
Lời giải. Cho $f$ là một hàm liên tục mà $f(x) = f(x+1) = f(x+\sqrt{2})$. Điều này có nghĩa là các số 1 và $\sqrt{2}$ là các chu kỳ của hàm $f$. Khi đó, chu kỳ của hàm $f$ cũng là tất cả các số có dạng $m + n\sqrt{2}$, trong đó $m$ và $n$ là số nguyên, nghĩa là với hai số nguyên $m$ và $n$ bất kỳ đẳng thức $f(x + m + n\sqrt{2}) = f(x)$ là đúng. Đẳng thức cuối cùng có nghĩa là $f(x + y)$ và $f(x)$ có cùng giá trị khi $y$ thuộc về nhiều dấu kiểm phẳng
$$\{m + n\sqrt{2}; m, n \text{ — целые числа}\}.$$
Khi đó, theo bổ đề, ta thu được đẳng thức $f(x + y) = f(x)$ đúng với mọi số $y$, nghĩa là mọi số (thực) là một chu kì của hàm $f$. Bây giờ, nếu $x_1$ và $x_2$ là hai số khác nhau, chúng ta đặt $y = x_2 - x_1$, sau đó
$$f(x_1) = f(x_1 + (x_2 - x_1)) = f(x_2).$$
Do đó, nghiệm của bài toán 6 sẽ là tất cả các hàm có dạng $f(x) = a$, trong đó $a$ là một hằng số.
