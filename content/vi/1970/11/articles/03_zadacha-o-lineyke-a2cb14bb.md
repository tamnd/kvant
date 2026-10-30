---
id: 1970-11-zadacha-o-lineyke-a2cb14bb
issue: kvant_1970_11
year: 1970
number: "11"
title: Bài toán về thước kẻ
rubric: smes
page_first: 12
page_last: 17
page_labels: 10, 12, 14, 15
tag: P4D3
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 5946f1f6c413317104e0de9ad830186f9b547076069a15ffa4b2f1f177a2444d
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1970/11/articles/03_zadacha-o-lineyke-a2cb14bb.md
source_content_sha256: 268df441e1b6132de333aef26167840f070b39ab7eadc65e150a5b382f67ab2d
translation_model: gpt-5-6
translation_run: m10-1970-vi
---

⟦folio 10⟧

Để tại điểm này lực không tác dụng lên nó (điện áp bằng không) và khi điện tích lệch về bất kỳ phía nào thì lực tác dụng lên nó sẽ đưa nó trở lại điểm mà điện tích đang ở (các vectơ điện áp của trường tại mọi điểm lân cận phải hướng về điểm mà điện tích đang ở), tại đó còn phải có một điện tích trái dấu! Như vậy, khi điện tích bị dịch chuyển, cân bằng nhất thiết sẽ bị phá vỡ, và các điện tích hoặc sẽ nhập lại với nhau, hoặc sẽ bay tách ra.

Quan niệm về các electron quay quanh hạt nhân lần đầu tiên được Rutherford đưa ra. Mặc dù mô hình nguyên tử Rutherford với các electron quay quanh hạt nhân gặp nhiều khó khăn thoạt nhìn tưởng như không thể giải quyết, sự phát triển tiếp theo của vật lý đã cho thấy nó đúng. Nhưng đó đã là đề tài cho một câu chuyện khác.

Bài tập

1. Hãy vẽ hình ảnh gần đúng của các đường sức của trường của hai điện tích khác dấu và có độ lớn khác nhau.
2. Các đường sức của trường tĩnh điện có thể là đường kín không?
3. Đôi khi người ta nói rằng đường sức là các quỹ đạo mà điện tích dương sẽ chuyển động trong trường nếu đưa nó vào trường rồi để nó tự do. Khẳng định này có đúng không?
4. Có hai mặt cầu đồng tâm bán kính $R_1$ và $R_2$ và điện tích $q_1$ và $q_2$ ($R_1 < R_2$). Điện áp của trường do các điện tích của các mặt cầu gây ra phụ thuộc vào khoảng cách đến tâm chung của chúng như thế nào?
5. Điện áp của trường của một quả cầu tích điện đều phụ thuộc vào khoảng cách đến tâm quả cầu như thế nào?
6. Hãy tìm sự phụ thuộc vào khoảng cách của điện áp của trường do một dây tích điện đều vô hạn gây ra.
7. Hãy tìm điện áp của trường do một hình trụ tích điện đều rất dài gây ra.
8. Hãy chứng minh rằng bên trong một vật dẫn rỗng, trường bằng không, không phụ thuộc vào hình dạng của vật dẫn và khoang rỗng (che chắn).

Không tồn tại những số nguyên tố đơn giản nhất có chín chữ số (và dài hơn).

Mặc dù trên thước này chỉ có 4 vạch chia, bằng nó có thể đo tất cả các khoảng cách (nguyên) từ 1 đến 13 cm.

Cần ít nhất bao nhiêu vạch chia trên một thước dài 9 cm để nó đo được tất cả các khoảng cách từ 1 đến 9 cm?

Còn trên thước dài 12 cm?

⟦folio 12⟧

Định nghĩa. Ước chung lớn nhất của các số hoặc đa thức được gọi là một ước chung của chúng, chia hết không dư cho mọi ước chung của chúng.

Ta sẽ ký hiệu ƯCLN của các số hoặc đa thức $a, b$ như sau: ƯCLN $(a, b)$. Ví dụ, ƯCLN $(5, 10) = 5$; ƯCLN $(x^2, 3x-x^2) = x$; ƯCLN $(x^3-x^2,x-1) = x-1$.

Tìm ước chung lớn nhất

Đối với các số, có hai cách tìm ƯCLN.

Cách 1. Phân tích cả hai số thành các thừa số nguyên tố và lấy tích của những thừa số xuất hiện trong cả hai số. Chẳng hạn, khi rút gọn phân số $\frac{3770}{9425}$, có thể viết: $\frac{3770}{9425} = \frac{2\cdot 5\cdot 13\cdot 29}{5\cdot 5\cdot 13\cdot 29}$;

ƯCLN $(3770, 9425) = 5\cdot 13\cdot 29 = 1885$, $\frac{3770}{9425} = \frac{2}{5}$

Cách này có gì không tốt? Thứ nhất, trước hết phải chứng minh rằng mọi số tự nhiên đều có thể phân tích thành các thừa số nguyên tố và hơn nữa chỉ theo một cách duy nhất. Thứ hai, để tìm phép phân tích này, phải thực hiện một khối lượng công việc lớn, mà chủ yếu là theo hướng không cần thiết. Bởi vì ta sẽ tìm tất cả các ước của từng số, trong khi ta chỉ cần ước chung lớn nhất của chúng.

Như ta sẽ thấy sau đây, đối với các đa thức còn khó hơn nữa: phép phân tích luôn tồn tại, nhưng nói chung không thể tìm được nó, trừ khi có ai đó cố ý sắp đặt sao cho phép phân tích dễ tìm (như vẫn xảy ra trong những ví dụ cụ thể).

Nhưng cũng có thể không phân tích các số thành đa thức.

Cách 2. Thuật toán Euclid. Nó dựa trên các bổ đề sau.

Bổ đề 1. Mọi số tự nhiên $q$ có thể chia có dư cho một số tự nhiên khác $p$, tức là biểu diễn $q$ dưới dạng $q = kp+p_1$, trong đó $0 \leq p_1 < p$.

Bổ đề 2. Nếu số $d$ là ƯCLN của các số $p$ và $q$.

Nhận xét rằng bổ đề này cho phép chúng ta không chỉ tìm mà còn chứng minh sự tồn tại của ƯCLN của hai số, vì nó quy các vấn đề về sự tồn tại và việc tìm ƯCLN về các số nhỏ hơn.

Chứng minh các bổ đề này một cách độc lập. Trong bổ đề 1, cần chia trục số thành các đoạn bởi các điểm $0, p, 2p, 3p, \dots$ và xác định điểm $q$ nằm trong đoạn nào. Trong bổ đề 2, cần giả sử rằng số $d$ chia hết cho mọi ước chung của các số $p$ và $p_1$, đồng thời cả hai số $p, p_1$ đều chia hết cho $d$, rồi chứng minh rằng số $d$ cũng có hai tính chất này đối với các số $p$ và $q$.

Bây giờ, trên ví dụ đã xét trong cách 1, ta trình bày chính thuật toán Euclid — một dãy thao tác cho phép tìm ƯCLN của các số $q$ và $p$. Tiếp theo, bên trái ta viết dãy công thức ở dạng tổng quát, còn bên phải — đối với ví dụ.

Bước 1. Sử dụng bổ đề 1, chia $q$ cho $p$. Ta được:
$q = k_0p+p_1, 0 \leq p_1 < p$; $9425 = 2\cdot 3770+1885, 0 \leq 1885 < 3770$.
Dựa trên bổ đề 2, kết luận rằng
ƯCLN $(q, p) = \text{ƯCLN}(p, p_1)$; $\text{ƯCLN}(9425, 3770) = \text{ƯCLN}(3770, 1885)$.

Bước 2. Xem $p_1$ có bằng không hay không.
Nếu $p_1$ bằng không, thì kết thúc quá trình và chuyển sang bước 3.

⟦folio 14⟧

Trong bổ đề 1, số $p_1$ có độ lớn nhỏ hơn $p$, còn đối với đa thức, «kích thước» được lấy là bậc của đa thức. Ví dụ về phép chia đa thức có dư được đưa ra dưới đây, dựa vào đó bạn sẽ tự chứng minh bổ đề này.

Ví dụ. Chia đa thức $2x^5 + 4x^4 - 2x^3 - x + 1$ cho đa thức $x^2 + 2x + 5$ theo phép chia dài. Ta được:

$$\frac{-2x^5 + 4x^4 - 2x^3 - x + 1}{2x^5 + 4x^4 + 10x^3} = \frac{x^2 + 2x + 5}{2x^3 - 12x + 24}$$

$2x^5 + 4x^1 - 2x^3 - x + 1 = (2x^3 - 12x + 24)(x^2 + 2x + 5) + (11x - 119)$. Bây giờ chúng ta có các bổ đề cần thiết và có thể tiến hành theo thuật toán Euclid, tức là xây dựng một dãy các phép chia có dư (đối với đa thức!), trong đó các đa thức lần lượt giảm:

$$Q(x) = K_0(x) P(x) + P_1(x),$$
$$P(x) = K_1(x) P_1(x) + P_2(x),$$
$$P_1(x) = K_2(x) P_2(x) + P_3(x),$$

$$P_{m-2}(x) = K_{m-1}(x) P_{m-1}(x) + P_m(x),$$
$$P_{m-1}(x) = K_m(x) P_m(x).$$

Khi đó ƯCLN $(Q(x), P(x)) = \text{ƯCLN}(P(x), P_1(x)) = \dots = \text{ƯCLN}(P_{m-1}(x), P_m(x)) = \text{ƯCLN}(P_m(x), 0) = P_m(x)$. Thương cuối cùng $P_m(x)$ chính là ƯCLN của các đa thức ban đầu (hãy kiểm tra tất cả điều này).

Trong thực tế, các công thức này thu được bằng phép chia đặt tính, ở ví dụ đầu tiên trông như sau:

$$\frac{x^9 - x^8 - x^7 - 3x^6 + x^5 + 4x^4 + 4x^3 + x^2 - 2x - 1}{x^9 - x^8 - 3x^6 + x^5 + x^4 + 2x^3 - x} = \frac{x^8 - x^7 - 3x^5 + x^4 + x^3 + 2x^2 - 1}{x^8 - x^7 - 3x^5 + x^4 + x^3 + 2x^2 - x - 1}$$

Bây giờ còn lại là rút gọn phân thức đại số (2) bằng ước cuối cùng $-x^7 + 3x^4 + 2x^3 + x^2 - x - 1$, tức là chia tử số và mẫu số trong (2) cho ƯCLN thu được. Thực hiện tất cả điều này, ta nhận được $\frac{x - 1}{x^2 - x - 1}$.

Đây chính là đáp án.

Nếu bạn đã đọc bài của N. M. Beskin «Phân số liên tục» («Квант» № 8), thì có thể nhận thấy rằng phương pháp được mô tả ở đây chính là việc rút gọn các đa thức bằng cách khai triển thành phân số liên tục, được thực hiện cũng giống như đối với các số hữu tỉ. Chúng ta đã viết lại phân thức $\frac{P(x)}{Q(x)}$ như sau:

$$\frac{P(x)}{Q(x)} = \frac{P(x)}{K_0(x) P(x) + P_1(x)} = \frac{1}{K_0(x) + \frac{P_1(x)}{P(x)}}$$,

⟦folio 15⟧

$$\frac{P(x)}{Q(x)} = \frac{1}{K_0(x) + \frac{P_1(x)}{K_1(x) P_1(x) + P_2(x)}} = \frac{1}{K_0(x) + \frac{1}{K_1(x) + \frac{P_2(x)}{P_1(x)}}}$$

và tiếp tục như vậy. Cuối cùng $\frac{P_m(x)}{P_{m-1}(x)} = \frac{1}{K_m(x)}$, chỉ còn lại việc thu gọn phân số liên tục của các đa thức. Trong ví dụ đang xét, điều này được thực hiện như sau: $\frac{1}{x + \frac{1}{-x+1}} = \frac{x-1}{x^2-x-1}$.

Rút gọn các biểu thức:

1. $\frac{x^4 - 3x^2 + 1}{(3x^2 + 3x - 3)^2}$.
2. $\frac{x^3 + a^3}{x^4 + a^2x^2 + a^4}$.
3. $\frac{a(x^2 + 2) - 2ax - (x-1)^2 - 1}{x^4 + 4}$.
4. $\frac{x^2 + 6}{2(x^4 + 4x^2 - 12) + \frac{1}{7}(x^4 + 11x^2 + 30)}$.

NHỮNG LỖI IN ĐÃ ĐƯỢC PHÁT HIỆN

Ở những chỗ được đánh dấu dưới đây phải là các nội dung sau:

«Квант» số 6

Trang 6, cột bên phải. Trong hình vẽ của bài tập 3, nét gạch phía dưới là thừa; toàn bộ hình vẽ bị lật ngược.

Trang 21, cột bên phải, dòng thứ 1 từ trên xuống: ...=(1+x^t)[(1+x)^p-(1+x^p)]×...;
dòng thứ 7 từ trên xuống: x^{kp+s}...
dòng thứ 2 từ dưới lên: ...C_{119}^3 ≡ C_{23}^6 C_{4}^3...;

Trang 22, cột bên trái, dòng thứ 2 từ trên xuống: ...C_{23}^6 ≡ C_4^1 C_3^1...;

Trang 30, cột bên phải. Trong lời giải bài tập 3, điều kiện $b \geq 0$ là thừa, trường hợp $b < 0$ phải được xét riêng.

Trang 31, cột bên trái, dòng thứ 6 từ dưới lên:
$$x = \frac{a(2+tg\alpha)}{tg\alpha};$$
dòng thứ 3 từ dưới lên:
$$V = \frac{a^3(2+tg\alpha)^3}{6tg^2\alpha};$$

Trang 4, ở bài tập 15 hệ có dạng:
$$\begin{cases} x+3y=3, \\ ax+4y=6. \end{cases}$$

ở bài tập 35 hệ có dạng:
$$\begin{cases} 3|x|-5y=-3, \\ 2x+|y|=11. \end{cases}$$

Trang 35, ở bài tập 3 (phương án 2) phương trình là:
$$\log_3(\log_2x-1)^2=\sqrt{5}^{-\log_54}.$$

Trang 52, cột bên phải, dòng thứ 3 từ dưới lên: ... $p^2+13=17$...

Trang 59, cột bên phải. Trong bài tập 4, 6) đáp án: 5(11) 540; khi chia đã mắc lỗi.

Trang 60, cột bên phải,
8. $\frac{5}{6} < x < 2.$ 23. $S_\sigma = \frac{1}{2}\pi b^2$.
24. $V = -\frac{2}{3}l^2$.
Trang 61, cột bên trái, 37. $0 < t \leq 0,1$.
Trang 63, cột bên phải, dòng 11 từ dưới lên:
$$\begin{cases} 500-80=420=100a+b, \\ 2500-496=2004=100b+a. \end{cases}$$
Trang 3 bìa, ô chữ được xoay $90^\circ$.

«Kvant» số 7

Trang 43. Tại giao điểm của dòng 5 từ dưới lên và cột 8 phải là 256;
12 » » » » 46656;
14 » » » » 823 543.
Trang 49, cột bên phải, dòng 14 từ trên xuống:
$$\frac{4}{9}$$.
Trang 52, cột bên phải, dòng 15 từ trên xuống:
$$\sqrt{4r^2-h^2} = \frac{r}{\sin \frac{\pi}{n}}$$
cột bên trái, dòng 14 từ dưới lên: ... $A_nA_1 = 2r$.
Trang 59, bài 1234: ... bằng bốn lần cân...
