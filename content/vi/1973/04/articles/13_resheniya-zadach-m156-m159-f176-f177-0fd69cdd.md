---
id: 1973-4-resheniya-zadach-m156-m159-f176-f177-0fd69cdd
issue: kvant_1973_4
year: 1973
number: "4"
title: Lời giải bài toán M156—M159; F176—F177
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 48
page_last: 53
page_labels: 46, 47, 48, 49, 51
tag: S30U
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 4a7b43a9dfda0f733ca8f74b2d2e3fe3b003ce3f6b89c0fb904ff295226c6f36
prompt_sha256: draft-1
translated_from: content/ru/1973/04/articles/13_resheniya-zadach-m156-m159-f176-f177-0fd69cdd.md
source_content_sha256: 34d02eb2ea6502f331296a1cca5c1ea2f6b35fc722d8ddb48b42b10f8e058f8f
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 46⟧

Lời giải bài toán

M156-M159; F176-F177

M156. Cho hình chữ nhật ABCD, M là trung điểm cạnh AD, N là trung điểm cạnh BC. Trên đoạn thẳng dài DC, lấy điểm D là điểm P. Ta ký hiệu giao điểm của đường thẳng PM và AC bằng Q. Chứng minh rằng QNM = MNP.

Bài toán có nhiều hình học đơn giản lời giải. Đây là một trong số đó.

Gọi O là tâm của hình chữ nhật (xem Hình 1) (giao điểm của MN và AC), K là giao điểm của QN với đường vuông góc với đoạn MN tại điểm giữa O. Khi đó, dễ thấy, QM/MP = QO/OC = QK/KN, và do đó, MK||PN. Nhưng tam giác MKN là tam giác đều: theo cách xây dựng KO có cả đường cao và đường trung tuyến. QNM tư thế = KMN = MNP.

Không khó để giải bài toán bằng phép tính. Ví dụ: bạn có thể sử dụng phương pháp tọa độ. Nếu ta đưa vào hệ tọa độ như Hình 2 thì tọa độ $(x_0, y_0)$ của điểm Q thỏa mãn hai phương trình:

$(p - 2b)x - ay = -2ab$ (phương trình đường thẳng MP) và $bx + ay = ab$ (phương trình đường thẳng CA).

Hãy nhân phương trình thứ hai với 2 và cộng nó với phương trình thứ nhất. Chúng tôi nhận được (cho $x = x_0, y = y_0$) $px_0 + ay_0 = 0$. Do đó, độ dốc của đường NQ bằng $\frac{y_0}{x_0} = -\frac{p}{a}$,

cơm. 1. Hình 2.

M157. Tổng của n số dương $x_1, x_2, x_3, \dots, x_n$ bằng 1. Gọi S là số lớn nhất

$$\frac{x_1}{1+x_1}, \frac{x_2}{1+x_1+x_2}, \dots, \frac{x_n}{1+x_1+x_2+\dots+x_n}.$$

Tìm giá trị nhỏ nhất có thể có của S. Đạt được giá trị nào của $x_1, x_2, \dots, x_n$?

Giả sử các số dương $a_1, a_2, \dots, a_n$ sao cho $a_1 + a_2 + \dots + a_n = 1$ và

$$\frac{a_1}{1+a_1} = \frac{a_2}{1+a_1+a_2} = \dots = \frac{a_n}{1+a_1+a_2+\dots+a_n}.$$

(Bên dưới chúng ta sẽ thấy rằng một tập hợp $a_1, a_2, \dots, a_n$ như vậy thực sự tồn tại.) Hãy chứng minh rằng với $x_1 = a_1, x_2 = a_2, \dots, x_n = a_n$ giá trị S nhận giá trị nhỏ nhất có thể có. Đặt $b_1, b_2, \dots, b_n$ là một tập hợp số dương khác có tổng bằng 1. Lưu ý rằng nếu $x_k$ tăng và tất cả $(x_1, x_2, \dots, x_k-1)$ trước đó không tăng thì số lượng

$$\frac{x_k}{1+x_1+\dots+x_{k-1}+x_k} = \frac{1}{\frac{1}{x_k}+\frac{x_1}{x_k}+\dots+\frac{x_{k-1}}{x_k}+1} = \frac{1}{1+x_1+\dots+x_{k-1}+x_k} + 1$$

sẽ tăng lên.

Pozny, nếu $b_1 > a_1$, thì $\frac{b_1}{1+b_1} > \frac{a_1}{1+a_1}$; nếu $b_1 \leq a_1, b_2 > a_2$, thì $\frac{b_2}{1+b_1+b_2} > \frac{a_2}{1+a_1+a_2} = \frac{a_1}{1+a_1}$; nếu $b_1 \leq a_1, b_2 \leq a_2, b_3 > a_3$ thì $\frac{b_3}{1+b_1+b_2+b_3} > \frac{a_3}{1+a_1+a_2+a_3} = \frac{a_1}{1+a_1+a_2+a_3}$, v.v. Vì tập hợp số $b_1, b_2, \dots, b_n$ khác với tập hợp $a_1, a_2, \dots, a_n$ và tổng các số trong các tập hợp chung

⟦folio 47⟧

rah cũng vậy, thì $b_k > a_k$ đối với một số $k$. Đặt $k$ là chỉ số nhỏ nhất có thuộc tính này, tức là $b_1 \leq a_1, b_2 \leq a_2, \dots, b_{k-1} \leq a_{k-1}, b_k > a_k$, thì

$$\frac{b_k}{1+a_1+\dots+a_k} > \frac{a_k}{1+a_1+\dots+a_k} = \frac{a_1}{1+a_1}.$$

Như vậy số lớn nhất

$$\frac{b_1}{1+b_1}, \frac{b_2}{1+b_1+b_2}, \dots, \frac{b_n}{1+b_1+\dots+b_n}$$ lớn hơn $\frac{a_1}{1+a_1}$

số lớn nhất trong các số $\frac{a_1}{1+a_1}, \frac{a_2}{1+a_1+a_2}, \dots, \frac{a_n}{1+a_1+\dots+a_n}$.

Việc còn lại là giải hệ phương trình số dương

$$\begin{cases} x_1+x_2+\dots+x_n=1, \\ \frac{x_1}{1+x_1} = \frac{x_2}{1+x_1+x_2} = \dots, \\ \dots = \frac{x_n}{1+x_1+x_2+\dots+x_n}. \end{cases}$$

Phương trình $\frac{x_1}{1+x_1} = \frac{x_k}{1+x_1+\dots+x_k}$ (đối với dương $x_1, x_2, \dots, x_k$) được chuyển về dạng $x_k = (1+x_1+\dots+x_{k-1})x_1$ nên hệ này tương đương với hệ

$$\begin{cases} x_2 = (1+x_1)x_1, \\ x_3 = (1+x_1+x_2)x_1, \\ \dots, \\ x_n = (1+x_1+\dots+x_{n-1})x_1, \\ x_1+x_2+\dots+x_n=1, \end{cases}$$

do đó tương đương với hệ thống

$$\begin{cases} x_2 = (1+x_1)x_1, \\ x_3 = (1+x_1)^2x_1, \\ \dots, \\ x_n = (1+x_1)^{n-1}x_1, \\ x_1+x_2+\dots+x_n=1, \end{cases}$$

nghĩa là, các số $x_1, x_2, \dots, x_n$ tạo thành một cấp số nhân có giá trị $(1+x_1)$ và tổng $(1+x_1)^n-1$.

1. Teler rất dễ tìm thấy hệ thống lời giải:

$$a_1 = \sqrt[n]{2}-1, a_2 = \sqrt[n]{2}\left(\sqrt[n]{2}-1\right), a_3 = \sqrt[n]{2^2}\left(\sqrt[n]{2}-1\right), \dots, a_n = \sqrt[n]{2^{n-1}}\left(\sqrt[n]{2}-1\right).$$

Giá trị bắt buộc của $S$ là

$$\frac{\sqrt[n]{2}-1}{\sqrt[n]{2}} = 1 - \frac{1}{\sqrt[n]{2}}.$$

M158. Bảng bộ ba được xây dựng theo quy tắc sau: số tự nhiên $a > 1$ được viết ở dòng trên cùng, sau mỗi số $k$ có $k^2$ và bên phải - số $k+1$. Ví dụ: với $a = 2$ ta có bảng:

Chứng minh rằng trên mỗi hàng của bảng tất cả các số đều khác nhau.

Giả sử rằng một số hàng của bảng chứa các số giống nhau. Gọi $n$ là số trên cùng của các dòng này, $p$ và $q$ là các số bằng nhau trong dòng được đánh số $n$. Vì không có số nào bằng nhau ở dòng trước, nên $p$ và $q$ được lấy từ các số ở dòng trước bằng các hành động khác nhau: một bằng cách bình phương, số còn lại bằng cách cộng 1. Đặt $p = r^2$, $q = s+1$ sao cho $s = r^2-1$. Các số $r$ và $s$ nằm ở dòng $(n-1)$. Hãy xem xét đường đi mà số $s$ được lấy từ số $a$. Giả sử rằng dọc theo con đường này, chúng ta gặp bình phương. Vì $s < r^2$, số lớn nhất chúng ta có thể bình phương sẽ là $r-1$. Nhưng $s-(r-1)^2 = 2r-2$. Điều này có nghĩa là chỉ có thể lấy được số $s$ từ số $(r-1)^2$ bằng cách thêm 2$r-2$ bước. Do đó, số $s$ được lấy từ số $a$ với không ít hơn $2r-1$ bước, sao cho $n-2 \geq 2r-1$. Nhưng tất cả các số thu được từ số $a$ trong số bước đó không nhỏ hơn $a+2r-1 > r$, trong khi số $r$, nằm trên cùng dòng với $s$, được lấy từ $a$ trong cùng số bước như $s$. Do đó, khi lấy số $s$ từ số $a$ thì không có bình phương. Điều tương tự cũng có thể nói về số $q = s+1$. Do đó, $q$ là số ngoài cùng bên phải nhỏ nhất trong hàng của nó, mâu thuẫn với đẳng thức $q = p$.

Bài toán có thể khái quát như sau.

Đặt $f$ là hàm được xác định trên tập hợp số tự nhiên và lấy giá trị. Giả sử $f(n+1)-f(n)>n+1$ với mọi số tự nhiên $n$. Do đó, một bảng tam giác theo sơ đồ tương tự như trong bảng đã cho, nhưng áp dụng mỗi lần

⟦folio 48⟧

hàm $f$ cùng với bình phương:

Khi đó ở mỗi hàng của bảng tất cả các số đều khác nhau.

Hãy để chúng tôi đưa ra một hệ quả thú vị bài toán M158.

Đặt một dãy vô hạn các số dương $a_1, a_2, a_3, \dots$ sao cho mọi số tự nhiên $n$
$a_n < a_{n+1} + a_n^2$,
vì vậy $a_2 < a_3 + a_4, a_3 < a_4 + a_9, a_4 < a_5 + a_{16}$, v.v. Sau đó, từ những số này, bạn có thể chọn một số số có tổng lớn hơn 1000. Số 1000 ở đây có thể được thay thế bằng bất kỳ số nào khác. (Như người ta nói, hàng $a_1 + a_2 + a_3 + \dots + a_n + \dots$ phân kỳ.)

Đặc biệt, điều kiện (*) được thỏa mãn bởi dãy $a_n = 1/n$, nên từ hệ quả tất yếu này người ta có thể thu được một chứng minh khác về dấu của định lý về sự phân kỳ của chuỗi hài $1 + \frac{1}{2} + \frac{1}{3} + \frac{1}{4} + \dots$: tổng các số phân biệt, nghịch đảo của các số tự nhiên, có thể tăng lên bằng một vành lớn hơn.

M159. Có thể xét các số 0, 1, 2. trong các ô của một tờ giấy ca rô có kích thước $100 \times 100$ sao cho trong mỗi hình chữ nhật $3 \times 4$, các cạnh của nó dọc theo các hàng ô, sẽ có số 0 là số nào và năm số hai?

Giả sử rằng chúng tôi đã điền được vào một tờ giấy ca rô theo yêu cầu. Chúng ta hãy lưu ý rằng số đầu tiên trong hai hình chữ nhật được tô bóng trong hình $3$ bằng số 0, bằng số một và bằng hai, vì chúng được bổ sung bằng cùng một hình cho hình chữ nhật $3 \times 4$. Vì lý do tương tự, có số lượng số 0 bằng nhau, số lượng số một bằng nhau và số lượng số hai bằng nhau trong hình chữ nhật được tô màu trong Hình $4$. Bây giờ chúng ta hãy chứng minh một loạt phát biểu về vị trí của số 0, số 1 và số 2.

1. Hình chữ nhật $1 \times 3$ có nhiều nhất một số 0.

Thật vậy, nếu có nhiều hơn một số 0 trong hình chữ nhật màu đỏ $1 \times 3$ trong hình $5$, thì sẽ có nhiều hơn một số 0 trong mỗi hình chữ nhật màu đỏ $1 \times 3$ và $1 \times 4$. Đồng thời, cả hai hình chữ nhật trống đều thuộc về một hình chữ nhật $3 \times 4$, hình chữ nhật này phải chứa ba số 0.

2. Hình chữ nhật $1 \times 4$ có nhiều nhất một số 0.

Nếu có hai số 0 trong hình chữ nhật màu đỏ $1 \times 4$ trong hình $6$ thì chúng nằm ở vị trí chính xác như trong hình. Cần có hai số 0 trong hình chữ nhật màu xanh lá cây, do đó, mỗi hình chữ nhật màu xanh lá cây sẽ có một số 0. Nhưng sau đó không có số 0 nào trong hai hình chữ nhật $1 \times 4$ nằm giữa hình chữ nhật màu đỏ và màu sáng (nếu không sẽ có hình chữ nhật $3 \times 4$ có nhiều hơn ba số 0). Do đó, chỉ có hai số 0 trong hình chữ nhật được khoanh tròn $3 \times 4$.

3. Có ít nhất một số 0 trong hình chữ nhật $1 \times 4$.

Nếu không có số 0 trong hình chữ nhật màu đỏ $1 \times 4$ trong hình $7$ thì không có số 0 nào trong hình chữ nhật màu xanh lam. Do đó, hai hình chữ nhật $1 \times 4$ phải có ba số 0 ở giữa. Đồng thời, mỗi hình chữ nhật này chứa không quá một số 0.

Do đó, trong mỗi hình chữ nhật $1 \times 4$ bằng một số không.

4. Hình chữ nhật $1 \times 4$ chứa không quá hai đơn vị.

Nếu có nhiều hơn hai đơn vị trong hình chữ nhật màu đỏ $1 \times 4$ trong hình $8$ thì có nhiều hơn hai đơn vị trong hình chữ nhật nhạt $1 \times 4$ và ít nhất hai đơn vị trong hình chữ nhật màu xanh lá cây $1 \times 3$. Nhưng sau đó có một hình chữ nhật $3 \times 4$ chứa nhiều hơn bốn đơn vị.

⟦folio 49⟧

5. Có nhiều nhất hai bảng trong hình chữ nhật $1 \times 4$.
Nếu có nhiều hơn hai bảng trong hình chữ nhật màu đỏ $1 \times 4$ trong Hình 8, thì có nhiều hơn hai bảng ở phần đầu và ít nhất hai bảng ở hình chữ nhật màu xanh lá cây. Hình chữ nhật $1 \times 4$, nằm phía trên hình chữ nhật đầu, có ít nhất một số hai, vì nó chứa nhiều nhất hai số một và một số không. Do đó, có nhiều hơn năm bảng trong hình chữ nhật khoanh tròn $3 \times 4$.

6. Có nhiều nhất một đơn vị trong hình chữ nhật $1 \times 3$.
Nếu có hai đơn vị trong hình chữ nhật màu đỏ $1 \times 3$ trong Hình 9, thì mỗi đơn vị có hai đơn vị trong hình chữ nhật đầu $1 \times 4$ và $1 \times 3$. Vì có một bảng trong hình chữ nhật màu xanh lá cây (nó chứa nhiều nhất hai bảng và một bảng số 0), nên hình chữ nhật được khoanh tròn $3 \times 4$ có nhiều hơn bốn bảng.

7. Có ít nhất một đơn vị trong hình chữ nhật $1 \times 3$.
Nếu không có số 1 trong hình chữ nhật màu đỏ $1 \times 3$ trong Hình 10, thì vì có nhiều nhất một số 1 trong mỗi hình chữ nhật đầu nên chỉ có ba số 1 trong hình chữ nhật $3 \times 4$.

Như vậy, trong mỗi hình chữ nhật, $1 \times 3$ bằng một đơn vị.

Hãy lấy một số không. Có một đơn vị bên cạnh nó, vì nếu không chúng ta sẽ có một hình chữ nhật $1 \times 3$ không có đơn vị. Vì phải có một số 0 trong hình chữ nhật $1 \times 4$ và một đơn vị trong hình chữ nhật $1 \times 3$, nên hai ô tiếp theo được chiếm bởi hai ô: $0 \mid 1 \mid 2 \mid 2$.

Ô bên cạnh hai ô đó phải chứa cả số 0 và số 1, vì nếu không, nó sẽ tìm thấy tương ứng một hình chữ nhật $1 \times 4$ không có số 0 hoặc một hình chữ nhật $1 \times 3$ không có số 0.

Cuối cùng chúng tôi đã có được sự mâu thuẫn cần thiết.

Tất cả các đối số trên đều hợp lệ nếu hình chữ nhật màu đỏ mà chúng ta bắt đầu mỗi lần không quá gần với đường viền của trang ô. Nhưng kích thước trang tính ($100 \times 100$) là khá đủ cho việc này. Hãy thử tìm xem câu bài toán ở tờ vuông nhỏ nhất nào là đúng.

Yu. I. Ionin

lời giải chính xác của một số bài toán M151—M159 đã được thêm vào (chữ số cuối cùng của các số đã giải bài toán được ghi sau họ): S. Abramov (Moscow) 1; O. Adanina (Moscow) 2; A. Baraov (quận Urvansky của Cộng hòa xã hội chủ nghĩa Xô viết tự trị Kabardino-Balkian) 3; O. Beelaryan (Liên Xô Sisan Armenia) 1, 6; O. Belolinetsky (Kirichach) 1; V. Benkhan (Kalinin) 1; A. Blinov (Moscow) 6; A. Blokh (Kharkov) 1—4, 6, 7; A. Valkov (Tashkent) 1, 6; S. Vasiliev (Ufa) 1, 6; G. Visotskaya (Krasnoisk) 1; L. và I. Gotman (Arzamas) 6; A. Gritsoryan (Baku) 1—4, 6, 7; S. Gritsoryan (Yerevan) 1, 2; E. Gurvits (Tashkent) 6; E. Gusev (Pavlograd, vùng Dnepropetrovsk) 1, 4, 6; K. Danilenko (Volgograd) 1, 6; Z. Dyachenko (Andrushevka, vùng Zhytomyr) 1; R. Yedoryan (Hrazdan) 1; A. Zhdanov (Slavyanskaya-Kuban) 1; V. Zarubin (Kỳ nghỉ hè của khu vực Mátxcơva) 1, 6; Z. Zeifman (Orreev MASSR) 1; L. Zelikov (Odessa) 1, 2; S. Zenovich (Tashkent) 1, 6; A. Izrailevich (Sverdlovsk) 1; V. Karasev (Yaroslavl) 1; V. Kvasnitsky (làng Korkino, vùng Chelyabinsk) 6; V. Kovtunets (làng Shostkov, vùng Rivne) 1, 7; V. Kolosov (Kyiv) 6; I. Komolev (Firsanovka, vùng Moscow) 6; M. Levin (Vitebsk) 6; A. Litovchenko (Belokorovich, vùng Zhytomyr) 1; M. Lomakin (làng Kersh-Vorki, vùng Tambov) 1, 6; G. Lutincer (Chernivtsi) 1; E. Mazur (Derbent) 1; A. Makariev (Lviv) 1, 2, 4, 6, 7; P. Manelov (Tbilisi) 6; B. Maryanovsky (Vinnitsa) 1, 2, 4; I. Medzhibovsky (Moscow) 1; E. Mett (Leningrad) 1; O. Myasikova (Uman) 1; G. Nadiryan (Yerevan) 1; S. Nuzhny (Kuibyshev) 1; A. Okrue (làng Donetsk, Kirovsk) 6; V. Palatnik (Baku) 6, 8; V. Panarin (Krasnoisk) 1; P. Paramonov (Moscow) 1-4; A. Razulyaev (Klin) 1, 3, 8; A. Reznikov (Kyiv) 1; I. Rivlis (Tiraspol) 6; R. Rozhkov (Ryazan) 6; L. Rudtser (Kharkov) 1; M. Sapir (Sverdlovsk) 1, 2, 4; V. Thứ bảy (Kyiv) 1; Y. Simkin (Moscow) 1, 6; R. Siroma (Kharkov) 1, 2, 6; S. Sokov (làng Sokovki, vùng Slovodsk) 1;

⟦folio 51⟧

ồ không có màu đỏ trong hình. Tuy nhiên, để cắt phô mai hoặc các loại thực phẩm dính khác, bạn chỉ cần tạo áp lực lên dao. Lực ma sát giữa phô mai và dao cao khiến việc di chuyển dao khó khăn.

F177. Tần số dao động của dây phụ thuộc vào độ dài, độ căng của nó và mật độ dương - khối lượng của một đơn vị dây. Xác định loại phụ thuộc này.

Từ những xem xét vật lý (bằng cách tương tự với dao động của nam châm), rõ ràng là sự phụ thuộc của tần số dao động của dây $v$ vào chiều dài $l$, lực căng $F$ và mật độ dương $\rho$ có thể được biểu diễn dưới dạng sau:

$$v \sim l^\alpha F^\beta \rho^\gamma,$$

trong đó $\alpha$, $\beta$ và $\gamma$ là các hằng số không thứ nguyên. Đối với lời giải bài toán, chúng tôi sẽ sử dụng phương pháp kích thước*, theo đó $\alpha$, $\beta$ và $\gamma$ phải sao cho đẳng thức giữ được

$$[v] = [l^\alpha F^\beta \rho^\gamma] = [l]^\alpha [F]^\beta [\rho]^\gamma.$$

Trong hệ SI

$$[v] = c^{-1}, \quad [l] = m,$$

$$[F] = \frac{\kappa_2 \cdot m}{c^2}, \quad [\rho] = \frac{\kappa_2}{m}.$$

Sau đó

$$c^{-1} = m^\alpha \left( \frac{\kappa_2 \cdot m}{c^2} \right)^\beta \left( \frac{\kappa_2}{m} \right)^\gamma.$$

Hãy đặt các đơn vị giống nhau ở phía bên phải:

$$c^{-1} = m^{\alpha+\beta-\gamma} \kappa_2^{\beta+\gamma} c^{-2\beta}.$$

Biểu thức này hợp lệ nếu các đẳng thức được thỏa mãn

$$-2\beta = -1,$$

$$\beta + \gamma = 0,$$

$$\alpha + \beta - \gamma = 0.$$

Từ đây

$$\alpha = -1, \quad \beta = \frac{1}{2} \quad \gamma = -\frac{1}{2}.$$

Sau đó

$$v \sim l^{-1} F^{\frac{1}{2}} \rho^{-\frac{1}{2}}.$$

Tôi. Sh. Slobodechkiy

*) Ví dụ, hãy xem tài liệu quảng cáo của B. Yu. Kogan “Kích thước của một đại lượng vật lý”, M., “Nauka”, 1968.
