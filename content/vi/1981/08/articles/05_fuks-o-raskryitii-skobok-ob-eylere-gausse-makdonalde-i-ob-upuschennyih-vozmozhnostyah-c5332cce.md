---
id: 1981-8-fuks-o-raskryitii-skobok-ob-eylere-gausse-makdonalde-i-ob-upuschennyih-vozmozhnostyah-c5332cce
issue: kvant_1981_8
year: 1981
number: "8"
title: Về dấu ngoặc mở, về Euler, Gauss, Macdonald và những cơ hội bị bỏ lỡ
authors:
  - Фукс Д. Б.
rubric: osnovnye-stati
page_first: 14
page_last: 19
page_labels: 12-17
tag: AIB9
lang: vi
source: kvant_digital
extraction: vision
content_sha256: bab756f76d76961b7d3e811d34c70305b5cf97ce4ded8bd0eee19ac6cb385048
prompt_sha256: draft-1
translated_from: content/ru/1981/08/articles/05_fuks-o-raskryitii-skobok-ob-eylere-gausse-makdonalde-i-ob-upuschennyih-vozmozhnostyah-c5332cce.md
source_content_sha256: b757a9cbbc511e2cbade9b3169d3898bf25e65068795e425b7075c164815f178
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 12⟧

D. Fuchs

Về việc mở dấu ngoặc đơn
về Euler, Gauss, Macdonald
và về những cơ hội bị bỏ lỡ

Mỗi bạn đã phải mở ngoặc bao nhiêu lần trong một tác phẩm? Hàng nghìn, hay có thể là mười nghìn? Nếu có điều gì hấp dẫn trong hoạt động này thì người ta hy vọng rằng kết quả của phép nhân, sau khi cộng các số hạng tương tự, sẽ có dạng thuận lợi, chẳng hạn như,

$$\begin{align*}
(a+b) (a-b) &= a^2 - b^2, \\
(1-a) (1+a + \dots + a^n) &= 1 - a^{n+1}.
\end{align*}$$

Dưới đây chúng ta sẽ nói về những sự bình đẳng tương tự, chỉ là ít cực đoan hơn và sâu sắc hơn nhiều. Chúng là kết quả của hơn hai thế kỷ làm việc của các nhà toán học hàng đầu thế giới. Tôi khuyên độc giả của mình nên chuẩn bị sẵn giấy bút và lặp lại tất cả các phép tính theo tôi: điều này không chỉ giúp hiểu nội dung của bài viết mà còn đánh giá mức độ không tầm thường của kết quả của nó.

1. Danh tính Euler

Vào giữa thế kỷ 18 - đó là vào năm 1748 hoặc vài năm trước đó - Leonhard Euler bắt đầu quan tâm đến các hệ số của đa thức

$$\varphi_n(x) = (1-x) (1-x^2) (1-x^3) \dots (1-x^n).$$

Anh ta đã mở dấu ngoặc trong tác phẩm - và nhận được một phản hồi gây sốc

⟦folio 13⟧

Kết quả. Chúng ta hãy thực hiện phép tính này:

$$\varphi_1(x) = 1 - x,$$
$$\varphi_2(x) = 1 - x - x^2 + x^3,$$
$$\varphi_3(x) = 1 - x - x^2 + x^4 + x^5 - x^6,$$
$$\varphi_4(x) = 1 - x - x^2 + 2x^5 - x^8 - x^9 + x^{10},$$
$$\varphi_5(x) = 1 - x - x^2 + x^5 + x^6 + x^7 - x^8 - x^9 - x^{10} \dots,$$
$$\varphi_6(x) = 1 - x - x^2 + x^5 + 2x^7 - x^9 - x^{10} \dots,$$
$$\varphi_7(x) = 1 - x - x^2 + x^5 + x^7 + x^8 - x^{10} \dots,$$
$$\varphi_8(x) = 1 - x - x^2 + x^5 + x^7 + x^9 \dots,$$
$$\varphi_9(x) = 1 - x - x^2 + x^5 + x^7 + x^{10} \dots,$$
$$\varphi_{10}(x) = 1 - x - x^2 + x^5 + x^7 \dots$$

Đa điểm biểu thị các phần của đa thức $\varphi_n(x)$ chứa $x$ ở mức lớn hơn 10 (định dạng tạp chí không cho phép viết ra hoàn toàn các đa thức này: ví dụ: đa thức $\varphi_{10}(x)$ có ​​bậc 55).

Hãy bắt đầu với một quan sát khác nhưng quan trọng: các hệ số của đa thức $\varphi_n(x)$ “ổn định” khi $n$ tăng, nghĩa là mỗi hệ số không thay đổi bắt đầu từ một số $n$. Điều này dễ dàng bắt buộc: việc chuyển đổi từ $\varphi_{n-1}(x)$ sang $\varphi_n(x)$, bao gồm phép nhân với $1 - x^n$, không ảnh hưởng đến các hệ số của $1, x, \dots, x^{n-1}$, do đó tại $n > k$ hệ số của $x^k$ trong đa thức $\varphi_n(x)$ không phụ thuộc vào $n$. (Ví dụ: các phép tính của đa thức $\varphi_{10}(x)$ sẽ không thay đổi nếu thay vì $\varphi_{10}$ chúng ta lấy $\varphi_{11}, \varphi_{12}$, v.v.) Theo quan điểm này, chúng ta có thể nói về một “tích vô hạn”

$$\varphi(x) = (1 - x)(1 - x^2)(1 - x^3)(1 - x^4) \dots,$$

Tất nhiên, khái niệm đằng sau điều này không phải là đa thức, mà là một “chuỗi lũy thừa”, tức là một biểu thức của dạng

$$a_0 + a_1x + a_2x^2 + a_3x^3 + a_4x^4 + \dots,$$

trong đó $a_0, a_1, a_2, a_3, a_4 \dots$ là các số; trong trường hợp của chúng tôi, $a_0, a_1, a_2, a_3, a_4$ là các hệ số ổn định. Tính toán của chúng tôi cho thấy rằng

$$a_0 = a_5 = a_7 = 1,$$
$$a_1 = a_2 = -1,$$
$$a_3 = a_4 = a_6 = a_8 = a_9 = a_{10} = 0.$$

$\varphi(x)$ được gọi là hàm Euler.

Từ “hàm” không được sử dụng ở đây một cách ngẫu nhiên: đối với $-1 < x < 1$, các giá trị của $\varphi(x)$ có thể được tính toán (tương tự như cách tính tổng của một cấp số nhân vô hạn).

Bây giờ là điều chính. Sau khi mở dấu ngoặc của chúng tôi, rất nhiều thứ đã bị phá hủy, người ta có thể nói hầu hết mọi thứ. Ví dụ: kết quả của việc mở dấu ngoặc đơn trong tích $(1 - x)(1 - x^2) \dots (1 - x^{10})$ chứa, trước khi rút gọn các số tương tự, 43 số hạng có $x$ lũy thừa nhỏ hơn hoặc bằng 10, bao gồm 24 số hạng có $x$ lũy thừa 8, 9, 10. Sau khi rút gọn các số hạng tương tự, chỉ còn lại 5 trong số 43 số hạng này, kể cả không có số hạng nào có $x$ lũy thừa của 8, 9; 10. Chính xác hơn, như chúng ta đã thấy, trong số các hệ số $a_0, a_1, a_2, \dots, a_{10}$ có ba bằng 1, hai bằng -1 và sáu bằng 0. Chúng ta hãy đưa ra một giả thuyết thận trọng: các hệ số $a_k$ luôn bằng 0, 1 hoặc -1 và hầu hết chúng đều bằng 0. Phép tính tiếp theo mà người đọc có thể tự kiểm tra nếu muốn, không chỉ xác nhận giả thuyết này mà còn cho phép chúng ta làm rõ nó. Ví dụ: đây là một phần của chuỗi $\varphi(x)$ chứa $x$ lũy thừa không vượt quá 100:

$$\varphi(x) = 1 - x - x^2 + x^5 + x^7 - x^{12} - x^{15} + x^{22} + x^{26} -$$
$$- x^{35} - x^{40} + x^{51} + x^{57} - x^{70} - x^{77} + x^{92} + x^{100} \dots$$

Phải giả định rằng Euler, người không sợ tính toán dài và rất xuất sắc trong việc tính toán, đã tính được số lượng số hạng của chuỗi $\varphi(x)$ gần bằng nhau. Và sau đó anh ta chỉ đơn giản là không thể không nhận thấy rằng các hệ số khác 0 bằng 1 hoặc -1, đồng thời họ đặt các hệ số một và các hệ số trừ.

⟦folio 14⟧

Các bà vợ không hề lộn xộn mà theo một thứ tự được xác định chặt chẽ: hai đơn vị, hai phút một, hai phút một, v.v.*). Bảng chứa số mũ lũy thừa $x$, tại đó có các hệ số khác 0.

Rất dễ đoán những chỉ báo này là gì: trong cột thứ $n$ của bảng của chúng ta, dòng trên cùng chứa số $\frac{3n^2 \pm n}{2}$ và dòng dưới cùng chứa số $(-1)^n$. Nếu điều này đúng với mọi $n$, chúng ta đi đến đẳng thức

$$(1-x)(1-x^2)(1-x^3) \ldots = 1-x-x^2+x^5+x^7 \ldots +(-1)^n x^{\frac{3n^2-n}{2}} + (-1)^n x^{\frac{3n^2+n}{2}} + \ldots$$

hoặc, sử dụng ký hiệu viết tắt được sử dụng trong toán học,

$$\prod_{n=1}^{\infty} (1-x^n) = 1 + \sum_{n=1}^{\infty} (-1)^n \left( x^{\frac{3n^2-n}{2}} + x^{\frac{3n^2+n}{2}} \right).$$

Đây là đẳng thức của Euler. Lời chứng sau đó của các nhà toán học cung cấp một số bằng chứng về đồng nhất thức này. Tuy nhiên, một số trong số đó được đưa ra ở đoạn 3. (Người đọc quan tâm đến sự kiện hơn là chứng minh có thể bỏ qua đoạn này mà không cần đào tạo để hiểu sâu hơn.) Và bây giờ tôi sẽ nói về một ứng dụng đáng chú ý của đẳng thức Euler, ứng dụng tô điểm cho tất cả các sách giáo khoa về tổ hợp.

2. Danh tính Euler và số lượng phân vùng

Cho $n$ là một số tự nhiên. Chúng ta hãy biểu thị bằng $p(n)$ số cách mà $n$ có ​​thể được biểu diễn dưới dạng tổng của các số hạng tự nhiên (trong trường hợp này, các số hạng trong tổng có thể được lặp lại và cách biểu diễn chỉ khác nhau về thứ tự của các số hạng được coi là giống nhau).

Ví dụ:

$$p(1) = 1;$$
$$p(2) = 2 \quad (2=2; 2=1+1);$$
$$p(3) = 3 \quad (3=3; 3=2+1; 3=1+1+1);$$
$$p(4) = 5 \quad (4; 3+1; 2+2; 2+1+1; 1+1+1+1);$$
$$p(5) = 7 \quad (5; 4+1; 3+2; 3+1+1; 2+2+1; 2+1+1+1+1).$$

Các số $p(n)$ xuất hiện trong nhiều công thức toán học và rất hữu ích để giảm bớt. Nhưng làm thế nào để làm điều này? Ví dụ: hãy thử tìm $p(10)$. Bạn sẽ phải loay hoay một chút và nếu may mắn, bạn sẽ tìm thấy đáp số: 42. Nếu bạn cần biết, chẳng hạn như, $p(50)$ thì sao? Danh tính của Euler xuất hiện để giải cứu.

*) Hồi ký của Euler về chủ đề này được D. Poya trình bày đầy đủ trong cuốn sách “Matematika và lý luận hợp lý” (M., “Nauka”, 1975, tr. 111). Đọc chủ đề này cũng như các chương khác trong sách của Polya chắc chắn bạn sẽ thấy thoải mái hơn.

⟦folio 15⟧

Đầu tiên, một chút “lý thuyết”. Hãy đặt
$$\pi(x) = 1 + p(1)x + p(2)x^2 + p(3)x^3 + \dots = 1 + x + 2x^2 + 3x^3 + 5x^4 + 7x^5 + \dots$$

Giống như $\varphi(x)$, $\pi(x)$ là hàm xác định tại $-1 < x < 1$. Nhưng, một lần nữa, chúng ta chỉ quan tâm đến nó như một chuỗi lũy thừa.

Định lý. Chuỗi $\varphi(x)$ và $\pi(x)$ nghịch đảo lẫn nhau, tức là
$$\varphi(x) \cdot \pi(x) = 1.$$

Bạn có hiểu ý nghĩa của sự bình đẳng này là gì không? Chuỗi lũy thừa có thể được nhân lên:
$$(a_0 + a_1x + a_2x^2 + \dots) (b_0 + b_1x + b_2x^2 + \dots) = a_0b_0 + a_0b_1x + a_0b_2x^2 + \dots$$
$$+ a_1b_0x + a_1b_1x^2 + a_1b_2x^3 + \dots + a_2b_0x^2 + a_2b_1x^3 + a_2b_2x^4 + \dots$$
$$= a_0b_0 + (a_0b_1 + a_1b_0)x + (a_0b_2 + a_1b_1 + a_2b_0)x^2 + \dots;$$

tuyên bố của chúng tôi có nghĩa là nếu chúng tôi nhân chuỗi $\varphi(x)$ và $\pi(x)$ theo cách này thì tích thu được sẽ giảm xuống 1: các hệ số của $x, x^2, x^3, \dots$ sẽ bằng 0.

Bằng chứng.
$$\frac{1}{\varphi(x)} = \frac{1}{1-x} \cdot \frac{1}{1-x^2} \cdot \dots \cdot \frac{1}{1-x^k} \cdot \dots =$$
$$= (1+x+x^2+x^3+\dots) (1+x^2+x^4+x^6+\dots) \times \dots$$
$$\dots \times (1+x^k+x^{2k}+x^{3k}+\dots) \dots$$

Khi mở dấu ngoặc ở tích cuối cùng, chúng ta nhận được tổng của tất cả các biểu thức có thể có của dạng
$$x^{a_1}x^{2a_2} \dots x^{ka_k},$$

trong đó $a_1, \dots, a_k$ là số nguyên không âm. Do đó, $x^n$ sẽ được bao gồm trong tổng này bao nhiêu lần tùy theo bao nhiêu cách $n$ có ​​thể được biểu diễn dưới dạng
$$a_1 + 2a_2 + \dots + ka_k.$$

Nhưng biểu diễn này có thể được viết lại như thế này:
$$\underbrace{1 + \dots + 1}_{a_1} + \underbrace{2 + \dots + 2}_{a_2} + \underbrace{k + \dots + k}_{a_k}.$$

Ta thấy số $n$ được biểu diễn dưới dạng $a_1 + 2a_2 + \dots + ka_k$ giống như số được biểu diễn dưới dạng tổng các số hạng tự nhiên, tức là $p(n)$. Do đó, hệ số $x^n$ trong sản phẩm của chúng tôi bằng $p(n)$, tức là $\frac{1}{\varphi(x)} = \pi(x)$. Định lý đã được chứng minh.

Đặt $p(0) = 1$ để thuận tiện, chúng tôi viết
$$(1-x-x^2+x^5+x^7-\dots) (p(0) + p(1)x + p(2)x^2 + \dots) = 1$$

(các hệ số ở thừa số thứ nhất được viết theo kinh vĩ Euler!). Hãy mở ngoặc và đặt các hệ số $x, x^2, x^3, \dots, x^n$ ở vế trái bằng 0. Chúng tôi nhận được:
$$p(1) - p(0) = 0;$$
$$p(2) - p(1) - p(0) = 0;$$
$$p(3) - p(2) - p(1) = 0;$$
$$p(n) - p(n-1) - p(n-2) + p(n-5) + p(n-7) - \dots = 0$$

(ở phía bên trái của công thức cuối cùng, bạn cần viết các thuật ngữ miễn là đối số y p không âm). Vì thế,
$$p(n) = p(n-1) + p(n-2) - p(n-5) - p(n-7) + \dots$$

Công thức này cho phép bạn nhanh chóng tạo một bảng số khá dài $p(n)$. Đây là lời khuyên thiết thực về cách thực hiện điều đó. Lấy một tờ giấy ca rô - tốt nhất là một tờ giấy gấp đôi. Cắt một dải rộng 3-4 ô vuông dọc theo chiều dài của nó. Đặt dải này theo chiều dọc trước mặt bạn và đặt một số ký hiệu, chẳng hạn như dấu hoa thị, ở ô dưới cùng. Sau đó, ngạc nhiên hướng lên trên,

⟦folio 16⟧

đặt + vào ô đầu tiên, + ở ô thứ hai, - ở ô thứ năm, - ở ô thứ bảy, + ở ô thứ mười hai, + ở ô thứ mười lăm, v.v., miễn là dải đủ dài (Hình 1). Đặt phần còn lại của trang tính theo chiều dọc trước mặt bạn và cách mặt trái của nó 10-15 ô, vẽ một đường thẳng đứng trên đó - từ trên xuống dưới. Tại các ô liền kề dòng bên trái, phân kỳ từ trên xuống dưới, hãy ghi các số $p(n)$ bạn đã biết, bắt đầu bằng $p(0)$: 1, 1, 2, 3, 5, 7. Để tìm giá trị tiếp theo, gắn dải cắt bên phải vào đường thẳng đứng sao cho dấu hoa thị đối diện với ô trống đầu tiên. Bây giờ, từ tổng các số đối diện với các số phẳng, hãy viết tổng các số đối diện với các số âm. Viết điều gì xảy ra trong ô đối diện dấu hoa thị: đây là giá trị tiếp theo của hàm $p(n)$. Hạ dải xuống một ô vuông và lặp lại điều tương tự. Và vân vân. Trong vài phút bạn sẽ có một cột số $p(n)$ cao bằng tờ giấy của bạn.

Sử dụng cái sàng này, tôi đã tìm thấy các số $p(n)$ cho $n \leq 50$. Việc này mất - hoàn toàn, theo đồng hồ - 17 phút. (Tôi trình bày một số bước tính toán đầu tiên trong Hình 2; các số màu đỏ là giá trị mới của $p(n)$.) Cụ thể,

$$p(50) = 204226.$$

Hãy tưởng tượng sẽ mất bao nhiêu thời gian để tìm ra con số này bằng phương pháp tự chế!

3. Chứng minh điểm Euler

Hãy mở dấu ngoặc trong công việc của chúng tôi

$$(1-x)(1-x^2)(1-x^3)(1-x^4)$$

Kết quả là một tổng (vô hạn) trong đó $x^n$ xuất hiện nhiều lần theo số cách $n$ được biểu thị dưới dạng tổng của một chuỗi số tự nhiên tái sinh: $n=n_1+n_2+\dots+n_k$, $n_1<n_2<\dots<n_k$; trong trường hợp này, dấu tại $x^n$ sẽ là + nếu $k$ là số chẵn và - nếu $k$ là số lẻ. Dưới đây trong phần này, tập hợp 们 $(n_1, \dots, n_k)$ với $n_1+\dots+n_k=n$ và $n_1<\dots<n_k$ được gọi đơn giản là “phân vùng”.

Chúng ta sẽ phân biệt giữa ba loại phân vùng. Đối với phân vùng $(n_1, \dots, n_k)$, chúng ta hãy biểu thị bằng $s$ số lớn nhất sao cho $n_k-n_k-s+1=s-1$, tức là $s$ các số $n_k-s+1, \dots, n_k$ nằm liên tiếp (rõ ràng là $s \leq k$). Ví dụ: đối với phân vùng $12=2+4+6$ $s=1$, đối với phân vùng $12=1+5+6$ $s=2$, đối với phân vùng $33=4+5+7+8+9$ $s=3$. Chúng ta sẽ nói rằng phân vùng $(n_1, \dots, n_k)$ chiếm

*loại đầu tiên*, nếu $n_1 \leq s$, ngoại trừ trường hợp $n_1=s=k$;
*loại thứ hai*, nếu $n_1>s$, ngoại trừ trường hợp $n_1=s+1$, $s=k$;
*loại thứ ba* trong các trường hợp đặc biệt, nghĩa là nếu $s=k$ và $n_1$ bằng $s$ hoặc $s+1$.

Bây giờ chúng ta hãy liên kết phân vùng $(n_1, \dots, n_k)$ của loại phân vùng đầu tiên

$$\begin{cases}
(n_2, \dots, n_k-n_1, n_k-n_1+1+1, \dots, n_k+1), \text{ если } k-n_1 \geq 2, \\
(n_2+1, \dots, n_k+1), \text{ если } k-n_1=1,
\end{cases}$$

thuộc về loại thứ hai (kiểm tra!)

⟦folio 17⟧

Hình 2

Hơn nữa, bằng cách này, sẽ thu được sự tương ứng một-một giữa các phân vùng thuộc loại thứ nhất và thứ hai: ánh xạ nghịch đảo khớp với phân vùng $(n_1, \dots, n_k)$ của loại thứ hai với phân vùng
$$\begin{cases}
(s, n_1, \dots, n_{k-s}, n_{k-s+1}-1, \dots, n_k-1), \text{ если } k-s \geqslant 1, \\
(s, n_1-1, \dots, n_k-1), \text{ если } k-s=0
\end{cases}$$

(ký hiệu $s$ giữ nguyên nghĩa), thuộc loại thứ nhất (đánh dấu!). Vì sự tương ứng kết nối của chúng tôi cung cấp các phân vùng trong đó số lượng thuật ngữ khác nhau 1, nên các phân vùng tương ứng $x^n$ sẽ bị hủy và chỉ các thuật ngữ tương ứng với các phân vùng thuộc loại thứ ba vẫn còn trong tổng của chúng tôi. Và các phân vùng thuộc loại này, theo định nghĩa, có dạng
$$\begin{align*}
(k, k+1, \dots, 2k-1), \\
(k+1, k+2, \dots, 2k),
\end{align*}
$$
và chúng tương ứng với $(-1)^k x^{\frac{3k^2-k}{2}}, (-1)^k x^{\frac{3k^2+k}{2}}$ (như bạn biết, $k+(k+1)+\dots+(2k-1)=\frac{3k^2-k}{2}$ và $(k+1)+(k+2)+\dots+2k=\frac{3k^2+k}{2}$).

Bằng chứng đã kết thúc.

4. Nhận dạng Gauss

Khoảng 70 năm đã trôi qua kể từ phát hiện của Euler, và một nhà toán học vĩ đại khác, Carl-Friedrich Gauss, đã thực hiện bước tiếp theo với một lý thuyết tốt hơn (vì những lý do mà chúng ta sẽ không đề cập đến) được gọi là lý thuyết dạng mô đun. Ông phát hiện ra rằng nếu hàm Euler được lập phương thì kết quả là một chuỗi có lẽ còn đáng chú ý hơn chuỗi Euler:
$$\varphi(x)^3 = (1-x)^3(1-x^2)^3(1-x^3)^3\dots = 1-3x+5x^3-7x^6+9x^{10}-11x^{15}\dots$$
(Tôi khuyên các bạn đừng lười biếng mà tính càng nhiều hệ số của dãy $\varphi(x)^3$ hoặc
$$\prod_{n=1}^{\infty} (1-x^n)^3 = 1 + \sum_{n=1}^{\infty} (-1)^n (2n+1)x^{\frac{n(n+1)}{2}}.$$
Đồng nhất thức Gauss này còn đáng ngạc nhiên hơn vì bình phương của hàm Euler dường như không áp dụng được:
$$\varphi(x)^2 = 1-2x-x^2+2x^3+x^4+2x^5-2x^6-2x^8-2x^9+x^{10}\dots$$
