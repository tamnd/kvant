---
id: 1987-7-izhboldin-kurlyandchik-razbienie-edinitsyi-02822458
issue: kvant_1987_7
year: 1987
number: "7"
title: Tách đơn vị
authors:
  - Ижболдин О. Т.
  - Курляндчик Л. Д.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 50
page_last: 54
page_labels: 48, 49, 51, 52
tag: 6HQS
lang: vi
source: kvant_digital
extraction: vision
content_sha256: cbad0c93ba78e5f2982520b33d750104145b98608ddc8c06b5bd01fffa9de378
prompt_sha256: draft-1
translated_from: content/ru/1987/07/articles/14_izhboldin-kurlyandchik-razbienie-edinitsyi-02822458.md
source_content_sha256: dfbb3fecb42b52d90bde51e693f2aceebc593f10ece40718c13e09889daf1247
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 48⟧

Chia tách đoàn kết

O. T. IZHBERIN, L. D. KURLYANDCHIK

Có rất nhiều bài toán liên quan đến tổng các nghịch đảo của các số tự nhiên. Tạp chí của chúng tôi đã nhiều lần đề cập đến chủ đề này: năm ngoái, trong “Vấn đề «Kvant»”, hai bài toán như vậy đã được đặt - M989 và M1010 (trong «Kvant» Số 6 và Số 10). Lời giải là cuốn đầu tiên được xuất bản (xem «Kvant» số 10 năm 1986); lời giải Nhiệm vụ thứ hai và một số nhiệm vụ tương tự khác có liên quan đến ghi chú này. Chúng ta hãy nhớ lại công thức của bài toán.

Trình tự $r_1, r_2, r_3, \dots$ được xác định bởi các điều kiện

$$r_1 = 2, r_{n+1} = r_1 r_2 \dots r_n + 1,$$

vậy $r_2 = 3, r_3 = 7, r_4 = 43, \dots$

a) Chứng minh rằng với mọi $n$

$$\frac{1}{r_1} + \frac{1}{r_2} + \dots + \frac{1}{r_n} < 1.$$

6)* Hãy để $n$ các số tự nhiên sao cho tổng các nghịch đảo của chúng bằng 1. Chứng minh rằng tổng này không lớn hơn

$$\frac{1}{r_1} + \frac{1}{r_2} + \dots + \frac{1}{r_n}.$$

Về cơ bản, điều cần thiết ở đây là tìm giá trị gần đúng tốt nhất của một đơn vị bằng tổng các phân số có dạng $1/n$ (nhân tiện, những số như vậy được gọi là phân số hoặc phân số Ai Cập). bài toán này thuộc về nhà toán học người Mỹ Kellogg. Năm 1915, Giáo sư Carmike, người đã báo cáo về nó, đã trích dẫn nó trong cuốn sách “Phân tích Diophantine” của ông. Năm 1922, nó đã được giải bởi nhà toán học người Mỹ Curtis. Chúng tôi sẽ cung cấp một cái khác, ngắn hơn lời giải. (Nói về câu chuyện của bài toán, chúng ta cũng xin đề cập rằng nó được xuất bản ở số 70 trong tuyển tập “400 Selected bài toán”, do nhà xuất bản Mir xuất bản năm 1977, nhưng thực ra không có lời giải.)

Sự liên tiếp
2, 3, 7, 42, 1807, 3263443, ...

Bình đẳng xác định tính nhất quán $r_n$ trong điều kiện bài toán, có thể viết lại dưới dạng

$$r_{n+1} = (r_n - 1) r_n + 1$$

*) In bài toán there was also a third point - lemma to lời giải bài toán 6). Chúng tôi sẽ đưa nó lên sau.

⟦folio 49⟧

hoặc
$$\frac{1}{r_{n+1}-1} = \frac{1}{(r_n-1)r_n} = \frac{1}{r_n-1} - \frac{1}{r_n}.$$
Kể từ đây,
$$\frac{1}{r_1} + \frac{1}{r_2} + \dots + \frac{1}{r_n} = \left( \frac{1}{r_1-1} - \frac{1}{r_2-1} \right) + \left( \frac{1}{r_2-1} - \frac{1}{r_3-1} \right) + \dots + \left( \frac{1}{r_n-1} - \frac{1}{r_{n+1}-1} \right) = 1 - \frac{1}{r_{n+1}-1} < 1$$
(kể từ $r_1-1=1$). Điều này chứng minh tuyên bố a) của bài toán của chúng tôi. Đồng thời, chúng tôi đã chứng minh rằng $1/r_{n+1}$ là giá trị tự nhiên thấp nhất của $r_n$ có thể cộng vào tổng $1/r_1+...+1/r_n$ sao cho nó vẫn nhỏ hơn 1 (bằng cách thêm $1/(r_{n+1}-1)$ chúng ta sẽ nhận được chính xác 1). Thus, when constructing the sequence $1/r_n$, you need to “bite off the largest possible piece” each time.

Nhân tiện, chúng ta hãy lưu ý rằng các số $r_n$ xuất hiện trong một bài toán khác, một ước tính bên ngoài khác xa với chúng ta: “mô tả tất cả các bộ số tự nhiên $n$ sao cho tích của bất kỳ $n-1$ nào trong số chúng có tổng bằng một thì chia hết cho phần còn lại”. Hãy tự kiểm tra xem các số $r_1, ..., r_n$ có thỏa mãn điều kiện này không. Toàn bộ lời giải của bài toán này vẫn chưa được biết; chi tiết đã được thảo luận trong bài viết của A. Gein “Trên đường tới lời giải” (Kvant, 1978, số 7, trang 9).

Chúng tôi sẽ không quay lại bài toán M1010 và chúng tôi bắt buộc,

Tại sao trình tự $1/r_n$ là chính xác nhất?

Giả sử tổng $1/a_1+...+1/a_n$, trong đó $a_1, ..., a_n$ là các số tự nhiên, $a_1 \leqslant a_2 \leqslant ... \leqslant a_n$, là giá trị gần đúng chính xác nhất cho sự thống nhất; sự tồn tại của phép tính gần đúng như vậy cho mọi số tự nhiên $n>1$ đã được chứng minh trong lời giải bài toán M989, c) (xem «Kvant» Số 10, 1986, trang 36). Hãy đặt $\alpha_k=1/a_k$ tại $k=1, 2, ..., n-1$, $\alpha_n=1-\alpha_1-\alpha_2-...-\alpha_{n-1}$. Ta sẽ chứng minh tập hợp số $a_1, ..., a_n$ thỏa mãn các điều kiện sau:
$$\alpha_1 \geqslant \alpha_2 \geqslant ... \geqslant \alpha_n \geqslant 0,$$
$$\alpha_1+\alpha_2+...+\alpha_n=1,$$
$$\alpha_1...\alpha_k \leqslant \alpha_{k+1}+...+\alpha_n$$
tại $k=1, 2, ..., n-1$. (3)

Đây là các điều kiện của bổ đề tạo nên phần c) bài toán M1010. Theo bổ đề này, được chứng minh dưới đây, số $a_n$, tức là sai số gần đúng của sự thống nhất của chúng ta, không nhỏ hơn $1/(r_n-1)$ và $a_n=1/(r_n-1)$ chỉ dành cho tập hợp $a_k=1/r_k$, $k=1, ..., n-1$. Do đó, $a_k=r_k$, tương đương với câu 6).

Vì vậy, hãy kiểm tra điều kiện (1)–(3) cho $a_1, ..., a_n$. Điều kiện (2) rất indo; cũng rõ ràng rằng $a_1 \geqslant a_2 \geqslant ... \geqslant a_{n-1}$. Hãy để chúng tôi chứng minh điều đó $a_{n-1} \geqslant a_n$. Vì trước tiên chúng ta xem xét xấp xỉ tốt nhất của sự thống nhất,

$$\frac{1}{a_1} + ... + \frac{1}{a_{n-1}} + \frac{1}{a_{n-1}-1} \geqslant 1.$$
Kể từ đây,
$$a_{k+1} + ... + a_n = 1-\alpha_1-...-\alpha_k =$$
$$= 1-\frac{1}{a_1}-...-\frac{1}{a_k} = \frac{N}{a_1...a_k} =$$
$$= N \cdot \alpha_1 \cdot ... \cdot \alpha_k,$$
trong đó $N$ là một số tự nhiên nào đó và do đó biểu thức cuối cùng không nhỏ hơn $a_1...a_k$.

Chứng minh bổ đề

Chúng ta phải chứng minh rằng một trong tập hợp ($\alpha_1, ..., a_n$) thỏa mãn điều kiện (1)–(3) mà $a_n$ là tối thiểu trùng khớp với tập hợp $(1/r_1, ..., 1/r_{n-1}, 1/(r_n-1))$.

Sẽ thuận tiện hơn khi tìm một tập hợp có tích các phần tử tối thiểu; chúng ta sẽ thấy rằng nó sẽ có phần tử tối thiểu và cuối cùng.

Vì vậy, giả sử $\beta=(\beta_1, ..., \beta_n)$ là tập hợp thỏa mãn các điều kiện (1)–(3) mà tích $\beta_1...\beta_n$ là tối thiểu (chúng ta sẽ thảo luận câu hỏi tại sao một tập hợp như vậy tồn tại ở phần sau). Chúng ta hãy lưu ý ngay rằng $\beta_n>0$, và do đó, nhờ vào (2) $\beta_1<1$. (Nếu $\beta_n=0$, thì từ bất đẳng thức (3), chúng ta luôn thu được: với $k=n-1$ - đó $\beta_n=0$, cho $k=n-2$ - đó $\beta_{n-2}=0$, v.v.; nhưng tất cả các số $\beta_i$ không thể bằng 0, vì chúng cộng lại bằng 1.).

Bây giờ chúng ta hãy chứng minh rằng với tập hợp $\beta$ mọi bất đẳng thức (3) đều biến thành đẳng thức.

Đối với $n=2$ từ (1)–(3), chúng ta ngay lập tức thu được $\beta_1 \geqslant \beta_2 \geqslant 0$, $\beta_1+\beta_2=1$ và $\beta_1 \leqslant \beta_2$, tức là $\beta_1=\beta_2=1/2$. Hãy để $n>2$.

⟦folio 51⟧

Hãy để chúng tôi giải thích định lý này bằng ví dụ về hàm $f$ và tập hợp $A$. Thứ nhất, rõ ràng là hàm $f$ không liên tục, tức là các giá trị của nó cho hai tập hợp, các phần tử tương ứng của chúng đủ khác nhau một chút, sẽ gần nhau như mong muốn. Thứ hai, tập hợp $A$ bị giới hạn, tức là các phần tử $\alpha_i$ của bất kỳ tập hợp nào có trong nó không vượt quá một số cố định nhất định về giá trị tuyệt đối; chúng tôi có $|\alpha_i| \leq 1$. Cuối cùng, tập $A$ bị đóng; điều này có nghĩa là nếu một chuỗi tùy ý gồm các tập hợp từ tập hợp $A$ bao gồm $\alpha = (\alpha_1, \dots, \alpha_n)$ (tức là, các phần tử đầu tiên của các tập hợp này tạo thành một chuỗi tương tự như $\alpha_1$, phần tử thứ hai đến $\alpha_2$, v.v.), thì tập hợp $\alpha$ cũng thuộc về tập hợp $A$. Tính đóng của tập $A$ đảm bảo rằng mọi bất đẳng thức trong điều kiện (1)–(3) đều phi lịch sử.

Như vậy, định lý về việc đạt được giá trị nhỏ nhất cung cấp nền tảng vững chắc cho cấu trúc mà chúng ta đang xây dựng và từ đó hoàn thành lời giải bài toán M1010. Điều khá bất thường là các phương pháp phân tích phải được áp dụng cho số nguyên bài toán như vậy. Tuy nhiên, lời giải ban đầu được đề cập ở đầu bài viết hoàn toàn là số học.

Mẫu số là một cấp số cộng

Chúng ta hãy thảo luận thêm về hai bài toán về cách biểu diễn số nguyên. Tổng các nghịch đảo của các số tự nhiên $a_1, a_2, \dots, a_n$ có tạo thành một cấp số cộng không có sai phân trường không?

Hãy bắt đầu với trường hợp đơn giản nhất, trong đó hiệu của cấp số là 1. Vậy, một số có thể được biểu diễn dưới dạng tổng $1/a_1 + 1/a_2 + \dots + 1/a_n$, trong đó các số tự nhiên $a_1, a_2, \dots, a_n$ tạo thành một cấp số cộng có hiệu không phải trường không?

Hãy bắt đầu với trường hợp đơn giản nhất, trong đó hiệu của cấp số là 1. Vậy, một số có thể được biểu diễn dưới dạng tổng $1/a_1 + 1/a_2 + \dots + 1/a_n$, trong đó các số tự nhiên $a_1, a_2, \dots, a_n$ tạo thành một cấp số cộng có hiệu không phải trường không?

Bài toán 2. Từ bất kỳ cấp số cộng nào của các số tự nhiên, chúng ta có thể chọn nhiều số khác nhau $a_1, a_2, \dots, a_n$ sao cho $1/a_1 + \dots + 1/a_n = 1$ không?

Đáp số ở đây là một tuyên bố, nhưng, như trong bài toán 1, chúng tôi sẽ giới hạn chỉ phân tích một vài ví dụ.

⟦folio 52⟧

Cách dễ nhất là đưa ra cách phân tách các đơn vị cần thiết cho cấp số cộng của bốn số 2, 4, 6...; Ví dụ:

$$1 = \frac{1}{2} + \frac{1}{4} + \frac{1}{6} + \frac{1}{12}.$$

Tình huống với các số lẻ phức tạp hơn một chút: một trong những cách mở rộng có thể là

$$1 = \frac{1}{3} + \frac{1}{5} + \frac{1}{7} + \frac{1}{9} + \frac{1}{11} + \frac{1}{15} + \frac{1}{21} + \frac{1}{35} + \frac{1}{231}.$$

Và một cách xây dựng nữa có tính chất tổng quát hơn - dành cho một tiến trình tùy ý có chênh lệch là 1: $a, a+1, a+2, \dots$. Cho $k$ là một số tự nhiên sao cho $2^k > a$. Nếu viết tử số của các phân số vào vế phải của đẳng thức

$$1 = \frac{1}{2^k} + \frac{3}{3 \cdot 2^k} + \dots + \frac{2^{k+1}-1}{(2^{k+1}-1)2^k}.$$

dưới dạng tổng các lũy thừa khác nhau của hai: $2^{l+1}-1=1+2+\dots+2^l$, chúng ta có được biểu diễn đơn vị của tổng

microcoppe đường hầm

(Để bắt đầu, xem trang 19)

Một ví dụ về bản đồ bề mặt tinh thể silicon mà một nhà khoa học Mỹ thu được được hiển thị ở hình bên phải. Vị trí của từng nguyên tử silicon riêng lẻ trong cấu trúc tinh thể tuần hoàn có thể nhìn thấy rõ ràng.

Một microcoppe đường hầm quét cũng được xây dựng ở nước ta. Nó được phân biệt bởi vùng quét quy mô nguyên tử khổng lồ 10 × 10 micron và khả năng hoạt động trong môi trường không dẫn điện dạng lỏng. Lý do quan trọng thứ hai. Thông thường, trong các thí nghiệm trên microcopper đường hầm, mẫu đang nghiên cứu, nhằm mục đích tạo ra các bề mặt số, được đặt trong chân không cao. Tuy nhiên, một môi trường dày đặc cũng có thể có lợi để đạt được những mục tiêu tương tự. Do đó, hydrocacbon lỏng, được sử dụng trong đồng vi mô đường hầm của Liên Xô, có tác dụng bảo vệ bề mặt của...

“Bản đồ địa hình” của một phần bề mặt silicon có kích thước 175×115 A. Vùng sáng hơn tương ứng với vị trí của các nguyên tử trong mạng tinh thể.

Microcop quét đường hầm hiện nay dường như không chỉ là một phương tiện nghiên cứu bề mặt mà còn là một công cụ để tác động lên nó. Người ta cho rằng cạnh của một microcopma đường hầm có thể được “vẽ” trên bề mặt của những microcopma có kích thước hàng trăm, thậm chí mười nguyên tử. Có thể chúng ta sẽ sớm chứng kiến ​​một giai đoạn mới trong quá trình tối thiểu hóa thiết bị điện tử. Và một microcop quét đường hầm sẽ giúp thực hiện việc này.

A. P. Volodin
