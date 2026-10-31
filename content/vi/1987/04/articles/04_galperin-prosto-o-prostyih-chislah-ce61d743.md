---
id: 1987-4-galperin-prosto-o-prostyih-chislah-ce61d743
issue: kvant_1987_4
year: 1987
number: "4"
title: Chỉ về số nguyên tố
authors:
  - Гальперин Г. А.
rubric: raznoe
page_first: 11
page_last: 16
page_labels: 9-14
tag: L8DM
lang: vi
source: kvant_digital
extraction: vision
content_sha256: ab8d35abaea90605e6d425644e18254a8a9b9336c8ff16bd8ba6c14e0bfa04c9
prompt_sha256: draft-1
translated_from: content/ru/1987/04/articles/04_galperin-prosto-o-prostyih-chislah-ce61d743.md
source_content_sha256: ab45eab8458514aabc142fb705005a5bdc0d1ce4deb287bdca5b9bf1adb8dd02
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 9⟧

CHỈ VỀ SỐ NGUYÊN TỐ

Ứng viên Khoa học Vật lý và Toán học
G.A.GALYPERIN

Tính vô hạn của tập hợp số nguyên tố

Mọi người đều biết rằng hầu hết các số tự nhiên đều có thể phân tích thành thừa số: 10=2·5, 60=3·4·5, 111=3·37, 144=3·3·2·2·2·2, v.v. Những số như vậy được gọi là hợp số. Nhưng trong số các số tự nhiên cũng có những số có thể phân tích thành nhân tử theo cách tương tự: ví dụ, 11 không thể biểu diễn dưới dạng tích của hai số tự nhiên nhỏ hơn, cả hai đều lớn hơn 1. Vì vậy, 11 được gọi là số nguyên tố. Nói chung, số nguyên tố (hay “số nguyên tố” - như cách gọi của người Hy Lạp cổ) là những số tự nhiên không thể phân tích thành hai thừa số lớn hơn 1 (một thừa số không được coi là số nguyên tố). Sau đây là một số số nguyên tố đầu tiên: 2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41,... Trong đó có một số chẵn là 2, các số còn lại là số lẻ.

Bài 1. Tìm tất cả các cặp số nguyên tố khác nhau: a) nhân 1, 6) nhân 17.

Thoạt nhìn bạn có thể thấy dãy số nguyên tố có phần kỳ quái; không có luật đơn giản nào được tìm thấy trong cấu trúc của nó.

Bộ truyện này có kết thúc không? Câu hỏi này được đặt ra trong Quyển IX của Cơ sở Euclide và có đáp số được đưa ra: sau mỗi số nguyên tố khác, có thể chỉ ra số nguyên tố lớn - dãy số nguyên tố là vô hạn.

Chứng minh của khẳng định này do Euclid đưa ra là vô cùng khéo léo. Euclid lý do như sau: nếu chỉ có một số hữu hạn các số nguyên tố và p là số lớn nhất trong số đó, thì số N = 2 3 5 ... p + 1, vì nó lớn hơn p, không phải là số nguyên tố, và do đó được chia cho một số nguyên tố nào đó trong số các số nguyên tố có sẵn từ 2 đến p (xét cho cùng, theo giả định, không có số nguyên tố nào khác!). Tuy nhiên, N không chia hết cho bất kỳ số nào trong số này, vì phần dư của phép chia N cho bất kỳ số nào trong số chúng là 1. Mâu thuẫn thu được chứng tỏ rằng không có số hữu hạn các số nguyên tố mà là số vô hạn.

Bằng chứng mâu thuẫn này nói rằng có bất kỳ số lượng số nguyên tố lớn nào, nhưng nó không nói rõ cách tìm thấy ít nhất một số nguyên tố lớn p. Tuy nhiên, điều này không khó thực hiện: để làm được điều này, chỉ cần kiểm tra tính đơn giản của các số tự nhiên trong khoảng từ p+1 đến N - trong số đó phải có số nguyên tố. Thật vậy, nếu bản thân N không phải là số nguyên tố thì nó chia hết cho một số nguyên tố, hơn nữa (như chúng ta đã thấy) lớn hơn p, nhưng nhỏ hơn N, tức là nằm trên đoạn [p; N].

Các phân đoạn có số nguyên tố

Việc chia trục số thành các đoạn, mỗi đoạn chứa một số nguyên tố, có thể chia tùy ý theo cách khác. Trước tiên chúng ta hãy chứng minh khẳng định sau: ước số nhỏ nhất của số N=n!+1 (trong đó n!=1·2·3…·n) là số nguyên tố lớn hơn n.

Hãy biểu thị ước số nhỏ nhất của số p. Vì n!+1 không chia hết cho bất kỳ số nào trong số 2, 3, 4, ..., n nên ta được p>n. Mặt khác, nếu chúng ta giả sử rằng p là hợp số, tức là p chia hết cho số không ctor nhỏ hơn p, thì p sẽ không phải là ước số nhỏ nhất của n!+1, điều này mâu thuẫn với giả định. Vì vậy, p là số nguyên tố lớn hơn n, đó là điều ta cần chứng minh.

Từ chứng minh này suy ra rằng trên bất kỳ khoảng [n nào; n!+1] có ít nhất một số nguyên tố. Và sau đó là các số 2, 2!+1, (2!+1)!+1,

⟦folio 10⟧

((2!+1)!+1)!+1, v.v. chia toàn bộ dãy số thành vô số đoạn, mỗi đoạn chứa ít nhất một số nguyên tố; Ta lại chứng minh được rằng có vô số số nguyên tố.

Hóa ra đã có trong mỗi phân đoạn [2; 4], [4; 8], [8; 16], [16; 32], ... chứa ít nhất một số nguyên tố. Nhưng đây là một định lý khó, được gọi là “Mệnh đề Bertrand”*), nghe như thế này: giữa các số n và 2n−2 với n>7 luôn có một số nguyên tố. Phương pháp Bertrand được chứng minh vào năm 1852 bởi nhà toán học nổi tiếng người Nga Pafnut Lvovich Chebyshev (1821-1894).

Bài toán 2. Chứng minh rằng nếu (p−1)!+1 chia hết cho p thì p là số nguyên tố. Gợi ý. Sử dụng bằng chứng của tuyên bố.

Bài toán 3. Chứng minh bằng mồi Bertrand rằng với mọi số tự nhiên n đều có ít nhất: a) một số nguyên tố có n chữ số; b) 3 số nguyên tố có n chữ số. Gợi ý. Các số 10^{n−1}, 2 10^{n−1}, 4 10^{n−1} và 8 10^{n−1} đều có n chữ số.

Lưu ý rằng chứng minh của Euclid không phải lúc nào cũng đưa ra số nguyên tố gần nhất sau p mà chỉ đưa ra một số nhất định thường nằm khá xa p. Ví dụ, vì một số nguyên tố rõ ràng lớn hơn 11, bằng chứng đưa ra không phải là 13 mà là 2311; với 13, nó không phải là 17 mà là 59 - một ước số đơn giản của số 30.031.

Các phân đoạn không có số nguyên tố

Để đưa ra một ý tưởng cụ thể về độ phức tạp của cấu trúc của tập hợp số nguyên tố, chúng ta sẽ chỉ ra điều đó trong chuỗi

*) M.I. Bashmakov. Hành động của Bertrand. «Kvant», 1971, số 5, tr. 4.

Cấp số cộng và số nguyên tố

Xét mọi số tự nhiên chia cho 3 dư 2: 2, 5, 8, 11, 14, ...; dạng tổng quát của những số đó là 3n+2. Hãy chứng minh rằng trong số vô hạn có nhiều số nguyên tố. Để làm điều này, chúng ta có thể sửa đổi một chút chứng minh của Euclid,

Bảng 1. Đoạn phân bố của số nguyên tố.

Bảng cho thấy số lượng số nguyên tố thay đổi như thế nào trong khoảng từ 8.900.000 đến 9.000.000, chia thành 1000 hàng trăm. Trong mỗi cột của bảng, số dưới cùng biểu thị số hàng trăm của khoảng đang xét trong đó số số nguyên tố bằng số trên cùng tương ứng của cột. Ví dụ, trong một trăm không có số nguyên tố nào cả, trong 117 phần trăm có 4 số nguyên tố, trong 130 phần trăm có 8 số nguyên tố.

| 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | 4 | 13 | 53 | 117 | 177 | 196 | 175 | 130 | 72 | 47 | 11 | 4 |

10

⟦folio 11⟧

Bảng 2. Phân bố tần số của các số nguyên tố trong chuỗi tự nhiên.

$A_n$ là số số nguyên tố trong số $n$ số tự nhiên đầu tiên. Tỷ lệ $A_n/n$ càng lớn đến 1/ln $n$ thì $n$ càng lớn (thường xuyên $A_n/n:1/\ln n$ thực tế không khác 1 tại $n=10^9$).

cụ thể là, thay vì số $N=2\cdot 3 \times 5 \dots p+1$, số $M=2\cdot 3\cdot 5 \dots p-1$ được xem xét, nhỏ hơn 1 so với bội số của 3, sẽ có chuỗi 2, 5, 8, 11, 14, ..., $3n+2$, ...

Bài tập 4. Chứng minh đầy đủ rằng $M$ có dạng $3n+2$.

Số $M$, như $N$, không chia hết cho bất kỳ số nguyên tố nào 2, 3, 5, ..., $p$. Cho dù $M$ là số nguyên tố hay có thể được phân tích thành một số thừa số nguyên tố - trong trường hợp chung, các số nguyên tố này sẽ lớn hơn $p$. Nhưng có yếu tố nào trong số các thừa số thu được có dạng $3n+2$, tức là sẽ nằm trong dãy 2, 5, 8, 11, ...? Giả sử rằng không phải như vậy, nghĩa là chúng ta giả sử rằng tất cả các thừa số nguyên tố của $M$ đều có dạng $3k+1$. Nhưng tích của họ cũng có dạng $3k+1$ (xem bài toán 5, a), và điều này mâu thuẫn với thực tế là $M$ có dạng $3n+2$ (xem bài toán 4). Do đó, giả định của chúng tôi không chính xác và ít nhất một thừa số nguyên tố của số $M$ có dạng $3k+2$. Do đó, có nhiều số nguyên tố có dạng $3k+2$ vô hạn.

Bài tập 5. a) Chứng minh tích của mọi số có dạng $3k+1$ cũng có dạng $3k+1$. b) Chứng minh tương tự cho các số có dạng $4k+1$, c) cho các số có dạng $6k+1$.

Lý luận trên (có sửa đổi một chút) cung cấp một công cụ để chứng minh tính vô hạn của tập hợp số nguyên tố có dạng $4k+3$ và $6k+5$. Đầu tiên chúng tôi yêu cầu người đọc suy nghĩ về vấn đề sau.

Bài 6. Chứng minh mọi số nguyên tố lớn hơn 3 đều có: a) dạng $4k+1$ hoặc dạng $4k+3$; b) xem $6k+1$ hoặc xem $6k+5$.

Ở đây chúng ta sẽ chỉ chứng minh tính vô hạn của tập hợp số nguyên tố có dạng $6k+5$. Chúng ta sẽ tiến hành chứng minh “bằng phản chứng” theo hai cách vốn có trong chứng minh ban đầu của Euclid. Giả sử rằng chỉ có một số hữu hạn các số nguyên tố thuộc loại này: $p_1, p_2, \dots, p_n$. Hãy xem xét số $K=$ $6p_1p_2\dots p_n-1 = 6(p_1p_2\dots p_n-1)+5$. Tuy nhiên, trong số hai: hoặc số $K$ tự nó là số nguyên tố hoặc nó bị phân tách thành một số hữu hạn các thừa số nguyên tố, trong đó không có số nào $p_1, p_2, \dots, p_n$ (tại sao?), và không phải tất cả các số đó đều có dạng $6k+1$, vì bản thân $k$ không có dạng này (xem bài toán 5, c). Điều này có nghĩa là một trong các thừa số nguyên tố của số $k$, không trùng với $p_1, p_2, \dots, p_n$, có dạng $6k+5$, điều này mâu thuẫn với giả định mà chúng tôi đã đưa ra. Mâu thuẫn này chứng tỏ danh sách các số nguyên tố có dạng $6k+5$ là vô hạn.

Bài 7. Chứng minh tập hợp số nguyên tố dạng $6k+5$ là vô hạn, nêu phương pháp rõ ràng để tìm các số này.

Bài 8. Chứng minh chi tiết tập hợp số nguyên tố dạng $4k+3$ một cách chi tiết. Lưu ý: Nhân bốn lần tích của các số thuộc loại này và trừ đi 1 từ tích.

Bài tập 9. Chứng minh rằng có vô số số nguyên tố không tận cùng bằng 1 (tức là tận cùng bằng 3, 7 và 9). Lưu ý: Xét tất cả các số nguyên tố có dạng $10k+a$, trong đó $a \neq 1$ và thực hiện suy luận tương tự như trên.

Một cách khái quát hóa các vấn đề đang được xem xét là định lý sau đây, được nhà toán học người Pháp Legendre xây dựng vào năm 1788 và được nhà toán học người Đức Dirichlet chứng minh vào năm 1837.

Định lý. Bất kỳ cấp số cộng vô hạn nào $a_1, a+d, a+2d, a+3d$, trong đó số hạng đầu tiên a là số nguyên tố cùng nhau với hiệu $d$, đều chứa vô số số nguyên tố. Nói cách khác, hàm $y=dx+a$, trong đó $d$ và $a$ là các số nguyên tố tương đối, nhận vô số giá trị nguyên tố khi $x$ đi qua một chuỗi số tự nhiên liên tiếp.

Chứng minh của Dirichlet không phải là cơ bản, và trong nhiều năm không có yếu tố chứng minh nào của định lý đáng chú ý này được nhìn thấy. Chứng minh cơ bản lần đầu tiên được thực hiện vào năm 1949 (161 năm sau Lê-

⟦folio 12⟧

Zhandra!) của nhà toán học nổi tiếng người Đan Mạch A. Selberg, người đã chứng minh nhiều định lý rất khó của lý thuyết số một cách cơ bản mà không cần sử dụng toán học cao cấp.

Sinh đôi

Chúng ta hãy nhớ lại công thức bài toán đầu tiên ở đầu bài viết. Như bạn có thể đã chứng minh, nếu hai số nguyên tố khác nhau bởi một số lẻ $p$ (1 hoặc 17, như trong bài toán 1), thì một trong các số nguyên tố này là số chẵn và sẽ bằng 2. Do đó, số nguyên tố còn lại $q$ khác với $p$ 2. Ngoài ra, nếu $p$ là số nguyên tố (như $p=17$ đến bài toán 1), thì các số nguyên tố $p$ và $q$ được gọi là số sinh đôi; trong bài toán 1 đây là các số 17 và 19.

Bài tập 10. Chứng minh bằng định lý Dirichlet rằng có vô số số nguyên tố không thuộc một cặp số nguyên tố sinh đôi nào. e được chỉ định. Ví dụ: tất cả các số nguyên tố này phải thuộc cấp số cộng $\{15k+7\}$.

Câu hỏi đặt ra: có bao nhiêu cặp số sinh đôi? Ví dụ, trong khoảng từ 0 đến 100.000 có 1225 cặp như vậy, và trong khoảng từ 8.000.000 đến 8.100.000 chỉ có 518. Những cặp như vậy có bao giờ gián đoạn trong chuỗi số nguyên tố kéo dài vô tận không? Cả câu hỏi này lẫn câu hỏi tổng quát hơn đều không được nhà toán học vĩ đại người Đức David Hilbert đặt ra tại Đại hội các nhà toán học quốc tế lần thứ 2 ở Pa-

Rige vào năm 1900, là phương trình tuyến tính $ax+by=c$ với hệ số nguyên $a, b, c$, trong đó $a$ và $b$ nguyên tố cùng nhau, luôn có thể giải được bằng số nguyên tố $x$ và $y$? — đáp số vẫn chưa nhận được.

Định lý cơ bản của số học

Bất kỳ số tự nhiên nào lớn hơn một đều thừa nhận một và chỉ một (theo thứ tự của các thừa số) phân tách thành thừa số nguyên tố.

Bằng chứng. Nếu có ít nhất một số thừa nhận hai khai triển thành các thừa số nguyên tố khác nhau thì nhất thiết phải tồn tại số nhỏ nhất $N$ có tính chất này:

$$N = p_1 p_2 \dots p_n = q_1 q_2 \dots q_m,$$

trong đó $p$ và $q$ biểu thị số nguyên tố. Nếu cần thay đổi thứ tự của các thừa số này, chúng ta có thể giả sử rằng $p_1 \leq p_2 \leq \dots \leq p_n, q_1 \leq q_2 \leq \dots \leq q_m$. Lưu ý rằng $p_1 \neq q_1$, vì trong trường hợp $p_1 = q_1$ số tự nhiên $N/p_1 = N/q_1$ nhỏ hơn $N$, sẽ có hai hệ số nguyên tố khác nhau, điều này mâu thuẫn với giả định rằng $N$ là tối thiểu. Giả sử $p_1 < q_1$ và xét số $N' = N - p_1 q_2 \dots q_m$. Dễ dàng nhận thấy số $N' = p_1(p_2 p_3 \dots p_n - q_1 q_2 q_3 \dots q_m) = (q_1 - p_1)q_2 q_3 \dots q_m$ là số dương và nhỏ hơn $N$. Điều này có nghĩa là, theo giả định của chúng tôi, $N'$ có

⟦folio 13⟧

có một cách phân tích nhân tử duy nhất thành thừa số nguyên tố. Nhưng cũng giống như số nguyên tố $p_1$ được đưa vào khai triển $N'$, thì $p_1$ cũng được đưa vào $q_1 - p_1$ hoặc $q_2 q_3 \dots q_m$. Từ bất đẳng thức $p_1 < q_1 \leqslant q_2 \leqslant \dots \leqslant q_m$ suy ra rằng $p_1$ không phải là thừa số của $q_2 q_3 \dots q_m$. Do đó, $p_1$ là một thừa số trong $q_1 - p_1$, tức là $q_1 - p_1$ được chia cho $p_1$. Và sau đó $q_1$ được chia cho số nguyên tố $p_1$. Tuy nhiên, điều này không thể xảy ra vì $q_1$ là số nguyên tố. Sự mâu thuẫn mà chúng ta đã đạt được cho thấy sự vô hiệu của giả định ban đầu đầu tiên, đó là nơi mà bằng chứng kết thúc.

Quét. Từ việc chứng minh định lý cơ bản của số học, người ta thấy rõ tại sao *ed1* không được phân loại là số nguyên tố. Nếu nó được bao gồm trong số các số nguyên tố, thì bất kỳ số tự nhiên nào cũng bắt đầu bị phân tách thành các thừa số nguyên tố theo nhiều cách, vì một số số 1 tùy ý có thể được thêm vào phân tách.

Bot một hệ quả quan trọng của định lý cơ bản của số học: nếu một số nguyên tố $p$ là một thừa số trong tích $ab$, thì nó là một thừa số trong $a$ hoặc $b$. Thật vậy, nếu $p$ không phải là thừa số trong $a$ hoặc $b$, thì biến phân tích thành thừa số nguyên tố của các số $a$ và $b$ sẽ dẫn đến phân tích thành thừa số nguyên tố của số $ab$ không chứa thừa số $p$. Mặt khác, đẳng thức $ab = pt$ là đúng, trong đó $t$ là một số tự nhiên nào đó. Do đó, biến $p$ và phân tích thành thừa số nguyên tố của số $t$, ta thu được phân tích số $ab$ thành thừa số nguyên tố đã chứa thừa số $p$. Do đó, chúng ta thu được hai khai triển của $ab$ thành các thừa số nguyên tố khác nhau, điều này mâu thuẫn với định lý chính.

Theo định lý chính, số $N$ có thể được biểu diễn dưới dạng
$$N = p_1^{k_1} p_2^{k_2} \dots p_s^{k_s},
$$ trong đó $k_1, \dots, k_s$ là số ước nguyên tố riêng biệt của $p_1, \dots, p_s$ tương ứng trong khai triển $N$. Tất cả các ước của $N$ đều có dạng $a = p_1^{r_1} p_2^{r_2} \dots p_s^{r_s}$, trong đó $0 \leqslant r_1 \leqslant k_1$, $0 \leqslant r_2 \leqslant k_2$, $0 \leqslant r_s \leqslant k_s$.

Một lần nữa về sự vô tận của số nguyên tố
Sự thống nhất của việc phân tích nhân tử cho phép chúng ta đưa ra một chứng minh mới về sự vô hạn của các số nguyên tố. Chứng minh này là của Leonhard Euler.

Giả sử 2, 3, 5, ..., $p$ đều là các số nguyên tố hiện có. Sau đó, từ công thức tính tổng của một cấp số nhân có giá trị nhỏ hơn 1, nó suy ra điều đó cho bất kỳ số tự nhiên nào $n$ $1 + \frac{1}{2} + \frac{1}{2^2} + \dots + \frac{1}{2^n} < \frac{1}{1 - \frac{1}{3}}, \dots, 1 + \frac{1}{p} + \frac{1}{p^2} + \dots + \frac{1}{p^n} < \frac{1}{1 - \frac{1}{p}}$.

Biến những bất đẳng thức này được sửa chữa:
$$\left(1 + \frac{1}{2} + \dots + \frac{1}{2^n}\right)\left(1 + \frac{1}{3} + \dots + \frac{1}{3^n}\right) \dots
\dots \left(1 + \frac{1}{p} + \dots + \frac{1}{p^n}\right) <
\frac{1}{\left(1 - \frac{1}{2}\right)\left(1 - \frac{1}{3}\right)\dots\left(1 - \frac{1}{p}\right)}$$.

Bên phải là một con số rất cụ thể; hãy biểu thị nó $A$. Tích ở bên trái, sau khi mở tất cả các dấu ngoặc đơn, sẽ trở thành tổng của các số $S$, nghịch đảo của tất cả các ước của số $N = 2^n 3^n 5^n \dots p^n$ (đây là nơi sử dụng định lý cơ bản của số học - hãy đảm bảo!). Do đó, vế trái của bất đẳng thức là tổng lớn $A_n = 1 + 1/2 + 1/3 + 1/4 + 1/5 + \dots + 1/2^n$, chỉ bao gồm một phần số hạng của tổng $S$. Vì vậy, với mọi $n$ $A_n < A$. Nhưng $A_n = 1 + 1/2 + (1/3 + 1/4) + (1/5 + 1/6 + 1/7 + +1/8) + \dots + (1/(2^n - 1) + 1) + \dots + (1/2^n) > 1 + 1/2 + 2 \cdot 1/4 + 4 \cdot 1/8 + \dots + 2^{n-1} \cdot 1/2^n = 1 + n/2$, điều này ngay lập tức dẫn đến mâu thuẫn: $A > 1 + n/2$ với tất cả $n$. Vì vậy, số nguyên tố không thể bị giới hạn trong bất kỳ danh sách hữu hạn nào, đó là điều cần phải chứng minh.

Kiểm tra tính đơn giản

Khi phân tích $N$ thành thừa số hoặc kiểm tra tính đơn giản của nó, bạn nên kiểm tra tính chia hết của $N$ thành các số nguyên tố liên tiếp 2, 3, 5, 7, .... Khi kiểm tra số $N$ để đơn giản, bạn chỉ cần giới hạn ở các ước nguyên tố không vượt quá $\sqrt{N}$. Thật vậy, nếu $N = ab$ thì số nhỏ hơn trong các số $a, b$ không lớn hơn $\sqrt{N}$ (nếu cả hai đều lớn hơn $\sqrt{N}$ thì tích của chúng sẽ lớn hơn $N$) và từ khả năng chia hết của $N$ cho $a$ nó tự động suy ra rằng $N$ cũng chia hết cho $N/a$ (vì vậy khả năng chia hết không cần kiểm tra $N/a$). Những phép tính toán học đầu tiên (Leonardo xứ Pisa).

Ví dụ. a) Nếu $N = 91$ thì $\sqrt{91} < 10$; Kiểm tra các số nguyên tố 2, 3, 5, 7, ta thấy $91 = 7 \cdot 13$.

⟦folio 14⟧

6) Nếu $N=1987$, thì $\sqrt{N}<45$, ..., và vì $N$ không chia hết cho bất kỳ số nguyên tố nào đến 43, thì 1987 là số nguyên tố.

Trong một số trường hợp, khi xác định số nguyên tố $N$, không thể thực hiện phép chia được chỉ định cho số nguyên tố. Mệnh đề đơn giản sau đây, do Euler đưa ra vào thế kỷ 18, cho phép chúng ta định nghĩa số nguyên tố $N$ theo một cách hoàn toàn khác.

Tiêu chuẩn đầu tiên của Euler. Nếu số lẻ $N>1$ có thể được biểu diễn dưới dạng hiệu của bình phương của hai số tự nhiên theo nhiều cách, thì $N$ là hợp số; nếu chỉ có một phương pháp như vậy thì $N$ thật đơn giản.

Bằng chứng. Chúng tôi coi $N$ không phải là số chính phương vì số chính phương luôn là hợp số. Hãy để $N=m^2-n^2=(m-n)(m+n)$. Suy ra rằng $m-n$ và $m+n$ là ước của $N$. Nếu $N$ là số nguyên tố thì $m-n=1$, $m+n=N$ và các số $m=(N+1)/2$, $n=(N-1)/2$ được xác định duy nhất bởi số $N$ và do đó $N$ không thể được biểu diễn theo cách khác dưới dạng hiệu của hai hình vuông.

Nếu $N$ là hợp số, tức là $N=ab$ và $a>b>1$ là các số lẻ thì khi lấy $x=(a+b)/2$ và $y=(a-b)/2$, chúng ta thu được: $a=x+y$, $b=x-y$, từ đó $N=ab=x^2-y^2$: một cách biểu diễn khác của $N$ thu được dưới dạng hiệu của các bình phương.

Theo đó, nếu $N$ được biểu diễn theo nhiều cách dưới dạng hiệu của các bình phương, thì $N$ không thể là số nguyên tố: đối với số nguyên tố $N$ cách biểu diễn như vậy là số ít. Nếu $N$ chỉ được biểu diễn theo một cách dưới dạng hiệu các bình phương, thì $N$ không thể là hợp số (như đã chứng minh ở trên), vì vậy sẽ đơn giản. Tiêu chí đã được thiết lập.

Tiêu chí này giúp bạn có thể kiểm tra các ước số $N$ bằng cách sử dụng bảng bình phương và bằng cách cộng tuần tự vào $N$ các bình phương của $n^2$ số nguyên, hãy kiểm tra xem tổng tại $n<(N-1)/2$ có phải là bình phương chính xác hay không.

Hãy phân tích nhân tử, ví dụ, 3551 theo cách này. Bằng cách cộng liên tiếp các số $1^2$, $2^2$, $3^2$, ... với 3551, mỗi lần chúng tôi kiểm tra xem tổng thu được có phải là số chính phương hay không. Kiểm tra (dùng bảng bình phương) cho thấy $3551+7^2=60^2$. Vì vậy, $3551=60^2-7^2=53\cdot67$.

Bài tập 11. Phân tích nhân tử các số 6557, 19019, 209209 bằng phương pháp đã cho.

Nó cũng dễ dàng để chứng minh.

Tiêu chuẩn thứ hai của Euler. Nếu một số tự nhiên có thể được biểu diễn dưới dạng tổng của hai bình phương của các số tự nhiên theo nhiều cách (giả sử rằng việc sắp xếp lại các chất làm ngọt không tạo ra một cách mới), thì $N$ là một số tổng hợp.

Từ tiêu chí thứ hai của Euler, suy ra rằng nếu một số nguyên tố được biểu diễn dưới dạng tổng của hai bình phương của các số tự nhiên thì chỉ có một cách. Nhưng những số nguyên tố nào được biểu diễn dưới dạng này?

Bài 12. Chứng minh rằng các số có dạng $4k+3$ không thể biểu diễn dưới dạng tổng của hai bình phương. Gợi ý. Bình phương của số chẵn chia hết cho 4, bình phương của số lẻ có số dư là 1.

Các số nguyên tố có dạng $4k+1$ vẫn là đối thủ cạnh tranh, và như Pierre Fermat đã chứng minh, tất cả các số như vậy có thể được biểu diễn dưới dạng tổng của hai bình phương. Vì vậy, không khó để trả lời, chẳng hạn, câu hỏi sau: số nào trong ba số nguyên tố 1973, 1979 và 1987 có thể biểu diễn dưới dạng tổng của hai bình phương?

Bài 13. a) Chứng minh rằng với mọi số tự nhiên $n$ thì số $N=n^4+4$ là hợp số (định lý Sophie Germain). 6) Chứng minh rằng với mọi số tự nhiên $m$ và $n$ thì số $N=n^4+4m^4$ là hợp số. Gợi ý. $N=(n^2-2m^2)^2+(2mn)^2$; áp dụng tiêu chuẩn thứ hai của Euler.

Đa thức tạo ra số nguyên tố

Với các số nguyên tố, mọi thứ sẽ đơn giản nếu có một công thức chung để tìm chúng. Những nỗ lực xây dựng một công thức như vậy đã được thực hiện, trong đó chỉ có các giá trị đơn giản. Nhưng đã ở mức $n=40$ giá trị của nó bằng $41^2$. Dễ dàng chứng minh rằng không có đa thức nào của một biến chỉ có thể nhận các giá trị đơn giản.

Gần đây một đa thức đã được tìm thấy, tất cả các giá trị dương

(Cuối cùng xem trang 38)
