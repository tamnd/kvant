---
id: 1983-1-vasilev-gutenmaher-arifmetika-i-printsipyi-podscheta-69079b76
issue: kvant_1983_1
year: 1983
number: "1"
title: Nguyên tắc số học và đếm
authors:
  - Васильев Н. Б.
  - Гутенмахер В. Л.
rubric: shkola-v-kvante
rubric_sub: Школа в «Кванте»
page_first: 32
page_last: 37
page_labels: 30-35
tag: 7EGL
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 11552364447cf2d8d59d5d25836ec8cebea2b6ad9d7af203902a6a2dbfaeaed4
prompt_sha256: draft-1
translated_from: content/ru/1983/01/articles/08_vasilev-gutenmaher-arifmetika-i-printsipyi-podscheta-69079b76.md
source_content_sha256: ba6d7ebca30244debe266c260d947c200052163f8fb112f9fc6169e4ebbbc27f
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 30⟧

Nguyên tắc số học và đếm

N. B. VASILIEV,
V. L. GUTENMACHER

Toán học dựa trên số học - lý thuyết về các số tự nhiên 1, 2, 3, .... Về lý thuyết có một số định lý sâu sắc và đỏng đảnh. Trong đó có rất nhiều bài toán khó và vẫn chưa có lời giải, mà hàng trăm năm nay đã thách thức nỗ lực của những nhà toán học xuất sắc nhất. Các nhánh mục đích của toán học hiện đại nảy sinh từ những nỗ lực tại lời giải và sự khái quát hóa của lý thuyết số bài toán. C. F. Gauss (1777-1855), người có nhiều khám phá đáng chú ý về lý thuyết số và các lĩnh vực khác của toán học, đã nói: “Matematika là nữ hoàng của khoa học; lý thuyết số là nữ hoàng của toán học”.

Mục đích của bài viết này là giới thiệu cho độc giả những khái niệm đơn giản nhất của ngành khoa học hấp dẫn này, các định lý cơ bản của số học, một số hàm số học và nguyên lý đếm.

§ 1. Số nguyên tố và hợp số

Trong suốt phần tiếp theo chúng ta sẽ giải quyết các số tự nhiên. Ta nói số $n$ chia hết cho số $a$ nếu tồn tại một số $b$ sao cho $n=ab$. Trong trường hợp này, số $a$ được gọi là ước số của số $n$ và số $n$ lần lượt được gọi là bội số của số $a$.

Mọi số tự nhiên lớn hơn một đều có ít nhất hai ước: 1 và chính số đó. Một số lớn hơn 1 được gọi là số nguyên tố nếu nó không có ước nào khác và hợp số nếu có. Một không phải là số nguyên tố cũng không phải là số tổng hợp.

Mọi số tự nhiên đều có thể phân tích thành tích của các số nguyên tố.

Trên thực tế, hợp số $n$ có thể phân tích thành tích của hai thừa số nhỏ hơn $n$. Nếu trong số chúng có những cái không đơn giản (tổng hợp), thì mỗi cái có thể được phân tách thành một tích của hai phần nhỏ hơn.

⟦folio 31⟧

v.v ... Rõ ràng quá trình này không thể tiếp tục vô thời hạn, vì ở mỗi bước chúng ta nhận được ít thừa số hơn bước trước và tổng số tự nhiên nhỏ hơn $n$ là hữu hạn: $n-1$. Kết quả là chúng ta phân tích số đó thành thừa số nguyên tố.

Thông thường, các thừa số nguyên tố giống hệt nhau được tập hợp lại và khai triển được viết dưới dạng chuẩn này:

$$n = p_1^{a_1} \cdot p_2^{a_2} \cdot \dots \cdot p_k^{a_k},$$

trong đó $p_1 < p_2 < \dots < p_k$ là các số nguyên tố khác nhau, $a_1, a_2, \dots, a_k$ là các số tự nhiên. Ví dụ: $1350 = 2 \cdot 3^3 \cdot 5^2$.

Định lý cơ bản của số học. Mọi số tự nhiên lớn hơn 1 đều có thể phân tích thành nhân tử một cách duy nhất.

Định lý này được gọi là định lý cơ bản vì trên thực tế tất cả các tính chất chia hết của số đều là hệ quả của nó.

Chúng ta sẽ không tập trung vào việc chứng minh định lý chính (ví dụ, nó có thể được tìm thấy trong [1], [3]), mà chỉ xây dựng một trong các hệ quả của nó.

Để số $a$ chia hết cho số $b$, điều cần thiết là mỗi thừa số nguyên tố có trong khai triển của số $b$ đều được đưa vào khai triển $a$ ở cùng mức hoặc cao hơn.

Làm thế nào bạn có thể phân tích một số lớn hơn thành thừa số nguyên tố? Quan sát hữu ích này sẽ giúp chúng ta điều này.

Nếu số $n$ thì nó có ước số không vượt quá $\sqrt{n}$ và lớn hơn 1.

Hãy giả sử điều ngược lại. Giả sử $n=ab$ và cả hai ước $a$ và $b$ đều lớn hơn $\sqrt{n}$. Vì $a > \sqrt{n}$ và $b > \sqrt{n}$, chúng ta có $ab > n$, điều này mâu thuẫn với giả định.

Để xác minh tính nguyên tố của một số đã cho $n$ hoặc, nếu $n$ là một thừa số, để tìm ước số của nó, việc kiểm tra xem $n$ có ​​chia hết cho các số nguyên tố không lớn hơn $\sqrt{n}$ hay không là đủ.

Bạn có thể tạo danh sách các số nguyên tố không vượt quá một số nhất định $N$ theo cách này. Bạn cần viết liên tiếp tất cả các số tự nhiên từ 1 đến $N$, gạch bỏ một số, sau đó gạch bỏ tất cả các số chẵn trừ số 2, sau đó gạch bỏ tất cả các số là bội số của 3, trừ chính số 3, sau đó là bội số của 5, v.v. cho đến khi số nguyên tố lớn nhất không vượt quá $\sqrt{N}$. Sau khi gạch bỏ các số là bội số của một số nguyên tố $p$, số đầu tiên không bị gạch bỏ sẽ là số nguyên tố tiếp theo sau $p$. Phương pháp đọc số này được gọi là “sàng Eratosthenes”. Nó không tệ như thoạt nhìn: ví dụ: để tạo một bảng gồm các số nguyên tố lên đến 2000, chỉ cần gạch bỏ tất cả bội số của mười bốn số nguyên tố đầu tiên từ 2 đến 43 (kể từ $47^2 > 2000 > 43^2$). Với sự trợ giúp của máy tính hiện đại, nhiều bảng số nguyên tố khác đã được biên soạn. Tất nhiên, ở đây cần lưu ý rằng tất cả các số nguyên tố đều không thể viết được. Như Euclid đã chứng minh được,

Có vô số số nguyên tố.

Giả sử có một số hữu hạn các số nguyên tố và $p$ là số lớn nhất trong số đó. Xét tích $p! = 1 \cdot 2 \cdot 3 \cdot 4 \cdot \dots \cdot p$ của tất cả các số từ 1 đến $p$ (đọc “$p$ giai thừa”). Số $p!$ chia hết cho tất cả các số nguyên tố, vì theo giả định, tích $p!$ chứa tất cả các số nguyên tố. Số $p! + 1$ theo sau nó trong chuỗi tự nhiên phải được phân tích thành thừa số nguyên tố, nhưng điều này là không thể, vì $p! + 1$ không chia hết cho bất kỳ số nguyên tố nào! Sự mâu thuẫn.

Nhiều bài toán cổ xưa và vẫn chưa giải quyết được hoàn toàn của lý thuyết số liên quan đến sự phân bố của các số nguyên tố trong chuỗi tự nhiên.

⟦folio 32⟧

Ví dụ, qua quan sát, họ chỉ ra rằng có các số lẻ đơn giản liền kề: 3 và 5, 5 và 7, 17 và 19, 29 và 31, v.v. Những số như vậy được gọi là số nguyên tố đóng. Cho đến lúc đó, người ta vẫn chưa biết số lượng các cặp sinh đôi đơn giản là hữu hạn hay vô hạn.

Mặt khác, giữa các số nguyên tố có thể có càng nhiều khoảng cách càng tốt, chính xác hơn là

Với bất kỳ $k$ nào trong chuỗi tự nhiên đều có $k$ số tổng hợp liên tiếp.

Thật vậy, hãy lấy số $(k+1)!$ và xét một chuỗi $k$ số liên tiếp:

$$(k+1)!+2; (k+1)!+3; (k+1)!+4;...$$
...; $(k+1)!+k+1,$

Tất cả chúng đều là hợp số: số thứ nhất chia hết cho 2, số thứ hai cho 3, ..., số cuối cùng chia hết cho $k+1$.

Bài toán
1. Phân tích các số $a$) 1981 thành thừa số nguyên tố; $b$) 1982; $c$) 1983; $d$) 1984.
Lời giải bài toán 1$\theta$). Chia 1983 cho 3, ta được 1983=3·661. Teler, chúng ta đang tìm các ước của số 661. Vì $25^2<661<26^2$, chúng ta cần kiểm tra khả năng chia hết cho các số nguyên tố 3, 5, 7, 11, 13, 17, 19, 23. 661 không chia hết cho bất kỳ số nào trong số đó, nghĩa là 661 là số nguyên tố.
2. Viết sáu theo chuỗi tự nhiên $a)$; $b)$ mười ba số tổng hợp liên tiếp.
$\theta)$ Có những số nguyên tố lân cận nào mà có đúng sáu số tổng hợp nằm giữa chúng trong chuỗi tự nhiên không?
3. Chứng minh rằng nếu $d$ là ước số lớn nhất của hợp số $n$, nhỏ hơn $n$ thì số $n/d$ là số nguyên tố.
4. Chứng minh rằng trong các số tự nhiên từ 1 đến 30$m$ có nhiều nhất 10$m$ số nguyên tố (với mỗi số $m=1, 2, 3, ...$).
5. Tìm tất cả các số $p$ sao cho $p, p+2, p+4$ cũng là số nguyên tố (những số như vậy có thể được gọi là “bộ ba” nguyên tố).

6. Ký hiệu thập phân của số 30 có bao nhiêu số 0?
7. Chứng minh rằng trong các số 2, 5, 8, 11, ... (tức là các số có dạng $3m+2$, trong đó $m=0, 1, 2, ...$) có vô số số nguyên tố.

§ 2. Số ước.
Quy tắc sản phẩm kết hợp

Trong Hình 1 bên dưới, tất cả các ước tự nhiên của các số 96 và 144 đều được viết ra. Chúng ta thấy rằng tất cả các ước số của số 96 được chia thành các cặp ước số bổ sung cho nhau (trong Hình 1 chúng được nối bởi hai) và của số 144, một trong các ước số, 12, bổ sung cho chính nó, vì $144=12^2$. Từ tính đối xứng của tập hợp ước số, phát biểu sau:

Nếu số $n$ không phải là số bình phương của một số nguyên thì số đó có số ước chẵn và nếu đúng thì số đó có số lẻ.

Trên thực tế, với mỗi ước số $a$ của số $n$, nhỏ hơn $\sqrt{n}$, sẽ có một ước số tương ứng $n/a$, lớn hơn $\sqrt{n}$. Do đó, các ước số khác $\sqrt{n}$ luôn là một số. Nếu $n=k^2$ thì một ước số khác $k$ sẽ được thêm vào chúng.

Gọi $d(n)$ là số ước của số $n$. Như được minh họa ở trên, nếu $n$ là một hình vuông hoàn hảo thì $d(n)$ là số lẻ (ví dụ: $d(144)=15$) và nếu không thì $d(n)$ là số chẵn (ví dụ: $d(96)=12$). Bây giờ chúng ta hãy trình bày cách phân tích số $n$ thành thừa số nguyên tố, tìm giá trị $d(n)$.

Trước hết, hãy lưu ý rằng đối với số nguyên tố $p$ thì luôn có $d(p^a)=a+1$.

Thật vậy, theo định nghĩa, số nguyên tố $p$ chỉ có hai de-

Cơm. 1. Ước số và phần bù của chúng

⟦folio 33⟧

Cơm. 2. Quy tắc tích: các ước số $2^{\beta_1} \cdot 3^{\beta_2}$ của số $144 = 2^4 \cdot 3^2 (0 \leq \beta_1 \leq 4, 0 \leq \beta_2 \leq 2)$ được đặt trong bảng $5 \times 3$.

chọn: 1 và $p$, và theo hệ quả tất yếu của định lý cơ bản của số học, số $p^a$ có $(a+1)$ ước số: 1, $p$, $p^2$, ..., $p^a$ (được coi là $p^0 = 1$).

Bây giờ hãy xem xét số $n$ với hai thừa số nguyên tố khác nhau, ví dụ $n = 144 = 2^4 \cdot 3^2$. Tất cả các ước số của nó đều có dạng $2^{\beta_1} \cdot 3^{\beta_2}$, trong đó $\beta_1$ có thể nhận bất kỳ giá trị nguyên nào trong số năm giá trị nguyên từ 0 đến 4, $\beta_2$ là một trong ba giá trị 0, 1 hoặc 2. Điều này có nghĩa là tổng số các cặp $(\beta_1; \beta_2)$ khác nhau có thể là $3 \cdot 5 = 15$, sao cho $d(144) = 15$ (xem Hình 2). Ở đây chúng ta đã sử dụng một nguyên tắc đếm hữu ích.

Quy tắc sản phẩm. Nếu phần tử $\beta_1$ có thể được chọn theo $N_1$ cách và phần tử $\beta_2$ có ​​thể được chọn không đáng kể trong số $\beta_1 - N_2$ cách, thì có thể tạo ra tổng cộng $N_1 \cdot N_2$ các cặp $(\beta_1; \beta_2)$ khác nhau. Nói chung, nếu bạn cần soạn một tập hợp $(\beta_1; \beta_2; ..., \beta_k)$ gồm $k$ phần tử và phần tử $\beta_1$ có thể được chọn theo $N_1$ cách, phần tử $\beta_2$ theo $N_2$ cách, ..., phần tử $\beta_k$ theo $N_k$ cách, thì tổng cộng bạn có thể soạn $N_1 \cdot N_2 \cdots N_k$ các bộ khác nhau $(\beta_1; \beta_2; ...; \beta_k)$.

Quy tắc chung này cho phép chúng ta viết công thức tính số ước của bất kỳ $n = p_1^{\alpha_1} \cdot p_2^{\alpha_2} \cdots p_k^{\alpha_k}$ nào. Thật vậy, theo hệ quả tất yếu của định lý cơ bản của số học, bất kỳ ước số nào của số $n$ đều có dạng $p_1^{\beta_1} \cdot p_2^{\beta_2} \cdots p_k^{\beta_k}$, trong đó $\beta_i$ nhận một trong các giá trị $(\alpha_i + 1)$ ​​0, 1, ..., $\alpha_i$. Do đó, số tập hợp $(\beta_1; \beta_2; ...; \beta_k)$ khác nhau và do đó các ước số khác nhau của $n$ là $d(n) = (\alpha_1 + 1)(\alpha_2 + 1) \cdots (\alpha_k + 1)$. (*)

Bài tập:
8. Tìm: a) $d(1000)$; 6) $d(1350)$; b) $d(5040)$; d) $d(84^{19})$.

Lời giải bài toán 6). Đáp số: 24. Vì $1350 = 2 \cdot 3^3 \cdot 5^2$, sử dụng công thức (*) ta thu được $d(2^1 \cdot 3^3 \cdot 5^2) = (1 + 1)(3 + 1)(2 + 1) = 24$.

9. Cho ví dụ về một số có a) có đúng 6 ước số; 6) có đúng 7 ước.

10. Chứng minh rằng số $n$ khi chia cho 3 còn dư 2, có ước số bằng nhau có dạng $3l + 1$ và $3s + 2$ và không phải là số chính phương.

11. Vòng tròn được chia thành 720 cung giống hệt nhau. Có bao nhiêu đa giác đều khác nhau (theo số cạnh) có các đỉnh tại các điểm chia?

12. Số $n$ có bao nhiêu ước chẵn (viết công thức tổng quát)? Với những số nào $n$ thì số ước như vậy bằng $\frac{1}{2} d(n)$?

13. Bàn có 9 ngăn kéo. Có bao nhiêu cách xếp 5 cuốn sách khác nhau vào chúng?

Đáp số: $9^5$ cách. Lời giải. Chúng ta có thể đặt cuốn sách đầu tiên theo 9 cách vào hộp này hay hộp khác, và bất kể lựa chọn này, có 9 cách để chọn hộp cho cuốn sách thứ hai, v.v. Theo quy tắc của tác phẩm, tất cả các cách đều là $9^5$.

14. Có bao nhiêu số có ba chữ số mà tất cả các chữ số đều là số lẻ?

15. Có bao nhiêu số có năm chữ số trong đó chữ số 5 xuất hiện ít nhất một lần trong ký hiệu thập phân?

§ 3. Hàm Euler.
Bao gồm và loại trừ

Trong § 2 chúng ta đã làm quen với hàm số học Euler: $\varphi(n)$ là số các số nhỏ hơn số $n$ và nguyên tố cùng nhau, tức là các số không có ước chung với $n$ (ngoại trừ 1).

Trong Hình 3, làm ví dụ, các số từ 1 đến 18 được viết ra. Ta thấy tất cả các số nguyên tố cùng nhau từ 18 trở đi đều được chia thành các cặp $(a; 18 - a)$.

Sự đối xứng như vậy sẽ áp dụng cho mọi $n > 2$: nếu số $a$ nguyên tố cùng nhau với $n$ thì $(n - a)$ cũng sẽ nguyên tố cùng nhau với $n$ và không bằng $a$. Trên thực tế, nếu $n - a$ và $n$ có ước chung $p > 1$, thì hiệu $n - (n - a) = a$ của chúng sẽ có cùng ước số $p$, do đó $n$ và $a$ sẽ không nguyên tố cùng nhau.

Từ sự đối xứng $a \leftrightarrow (n - a)$ này chúng ta thấy rằng số $\varphi(n)$ luôn là số chẵn (đối với $n > 2$).

Bây giờ chúng ta hãy chỉ ra cách tìm thấy $\varphi(n)$ khi biết cách phân tích số $n$ thành

⟦folio 34⟧

Các yếu tố chính. Trước hết, hãy lưu ý rằng nếu $p$ là số nguyên tố thì $\varphi(p) = p - 1$, vì tất cả các số 1, 2, ..., $(p - 1)$ đều nguyên tố cùng nhau với $p$ và nhỏ hơn nó. Đặt $n = p^\alpha$, trong đó $p$ là số nguyên tố và $\alpha > 1$. thì từ các số $n$, không vượt quá chúng $n$, chúng ta phải loại trừ những số chia hết cho $p$. Vậy con số

$$\frac{n}{p} = \frac{p^\alpha}{p} = p^{\alpha - 1},$$

tư thế

$$\varphi(n) = n - \frac{n}{p} = n \left(1 - \frac{1}{p}\right).$$

Bây giờ chúng ta hãy xem xét các số $n = p_1^{\alpha_1} p_2^{\alpha_2}$ với hai thừa số nguyên tố khác nhau. Ta minh họa cách đếm $\varphi(n)$ (đối với $n = 18$ tiếp tục ở Hình 3) bằng sơ đồ ở Hình 4: hình vuông biểu thị tập hợp các số từ 1 đến $n$, các hình tròn màu đỏ và xanh lam lần lượt là tập hợp các số chia hết cho $p_1$ và $p_2$, giao của các hình tròn là tập hợp các số chia hết cho $p_1 p_2$.

Các số nguyên tố cùng nhau đến $n$ được thể hiện bằng phần bóng mờ của hình vuông. Để xác định số của chúng, chúng ta phải loại trừ $N_1 = n/p_1$ “số màu đỏ”, $N_2 = n/p_2$ số “màu xanh” và thêm $N_{12} = n/p_1 p_2$ số nằm ở giao điểm của các vòng tròn. Như vậy,

$$\varphi(n) = N - N_1 - N_2 + N_{12} = n - \frac{n}{p_1} - \frac{n}{p_2} + \frac{n}{p_1 p_2} =$$

$$= n \left(1 - \frac{1}{p_1}\right) \left(1 - \frac{1}{p_2}\right).$$

Hình 5 sẽ giúp chúng ta phân tích trường hợp số $n = p_1^{\alpha_1} p_2^{\alpha_2}$ với các thừa số khác nhau: hình vuông biểu thị tập hợp các số không vượt quá chúng, hình tròn biểu thị tập hợp các số chia hết cho $p_1$, $p_2$ và $p_3$; thì trong các vòng tròn sẽ có các số $N_1 = \frac{n}{p_1}, N_2 = \frac{n}{p_2}$ và $N_3 = \frac{n}{p_3}$ tương ứng, trong các giao điểm theo cặp của chúng - các số $N_{12} = \frac{n}{p_1 p_2}, N_{13} = \frac{n}{p_1 p_3}$ và $N_{23} = \frac{n}{p_2 p_3}$, và trong giao điểm của cả ba vòng tròn - các số $N_{123} = \frac{n}{p_1 p_2 p_3}$ (đây là các số chia hết đồng thời cho $p_1, p_2$ và $p_3$, tức là cho $p_1 p_2 p_3$).

Chúng ta phải đếm có bao nhiêu số có trong hình vuông nhưng không rơi vào bất kỳ hình tròn nào. Nếu chúng ta trừ tổng $(N_1 + N_2 + N_3)$ từ $n$, thì chúng ta trừ các số rơi vào đúng hai trong ba vòng tròn hai lần và các số rơi vào cả ba vòng tròn thậm chí ba lần.

Bây giờ với hiệu $N - (N_1 + N_2 + N_3)$ chúng ta cộng tổng $(N_{12} + N_{13} + N_{23})$. Sau đó, chúng tôi sẽ tính toán chính xác tất cả các số chỉ thuộc một trong hai vòng tròn và chỉ các số

Cơm. 4.

Cơm. 5. Nếu tất cả những thứ này nằm trong hình vuông gồm $N$ phần tử, thì bên ngoài các hình tròn có $N - N_1 - N_2 - N_3 + N_{12} + N_{23} + N_{31} - N_{123}$ trong số chúng.

⟦folio 35⟧

rơi vào cả ba vòng tròn cùng một lúc là không chính xác: chúng ta đã trừ số của chúng ba lần và cộng lại ba lần. Bạn sẽ phải trừ đi $N_{123}$ khác từ tổng $N - (N_1 + N_2 + N_3) + (N_{12} + N_{13} + N_{23})$. Bây giờ chúng ta đã học được tất cả các số có trong hợp của ba vòng tròn một lần và đi đến công thức sau:

$$\varphi(n) = n - \frac{n}{p_1} - \frac{n}{p_2} - \frac{n}{p_3} + \frac{n}{p_1 p_2} + \frac{n}{p_1 p_3} + \frac{n}{p_2 p_3} - \frac{n}{p_1 p_2 p_3} = n \left(1 - \frac{1}{p_1}\right) \left(1 - \frac{1}{p_2}\right) \left(1 - \frac{1}{p_3}\right).$$

Ở đây chúng ta đã gặp những trường hợp đặc biệt của quy tắc đếm đã hứa này.

Quy tắc bao gồm và loại trừ. Cho tập hợp $A$ và tập hợp con $k$ của nó được chọn. Số phần tử của tập hợp $A$, không có trong bất kỳ tập hợp con nào đã chọn, được tính như sau: từ tổng số phần tử $A$, trừ đi số phần tử của tất cả các tập hợp con $k$, cộng số phần tử của tất cả các giao điểm theo cặp của chúng, trừ đi số phần tử của tất cả các giao điểm ba, cộng số phần tử của tất cả các giao điểm với bốn, v.v. cho đến giao điểm của tất cả $k$ tập hợp con.

Áp dụng quy tắc này để đếm $\varphi(n)$, trong đó

$$n = p_1^{a_1} p_2^{a_2} \dots p_k^{a_k},$$

và sử dụng danh tính đại số

$$1 - x_1 - x_2 - \dots - x_k + x_1 x_2 + x_1 x_3 + \dots + x_{k-1} x_k - x_1 x_2 x_3 - \dots - x_{k-2} x_{k-1} x_k + \dots + (-1)^k x_1 x_2 \dots x_k = (1 - x_1) (1 - x_2) \dots (1 - x_k)$$

(phía bên trái của thiết bị tuân theo đúng quy tắc “bao gồm và loại trừ”), bạn có thể nhận được công thức chung

$$\varphi(n) = n \left(1 - \frac{1}{p_1}\right) \left(1 - \frac{1}{p_2}\right) \dots \left(1 - \frac{1}{p_k}\right).$$

Lưu ý rằng đẳng thức đại số được viết ở trên cũng có thể được sử dụng để chứng minh quy tắc chung bao gồm và loại trừ: bằng cách đặt một số $j$ trong số $k$ chữ cái $x_1, x_2, \dots, x_k$ bằng 1 và $(k - j)$ còn lại bằng 0, chúng ta thu được (cho $0 < j \leq k$) ở vế phải 0, và vế trái cho thấy các phần tử giao nhau chính xác là $j$ tập hợp con là cộng và trừ cùng số lần.

Để kết luận, chúng tôi lưu ý rằng hàm $\varphi(n)$ và hàm $d(n)$ từ phần trước có một thuộc tính quan trọng như vậy, mà trong lý thuyết số được gọi là phép nhân:

Nếu $a$ và $b$ nguyên tố cùng nhau thì $\varphi(ab) = \varphi(a) \cdot \varphi(b)$ và $d(ab) = d(a) d(b)$

(Hãy tự mình kiểm tra điều này.)

Bài toán

16. Có bao nhiêu phân số tối giản thích hợp có giá trị là 288?

17. Tìm $a)$ $\varphi(96)$; $b)$ $\varphi(540)$; $b)$ $\varphi(1983)$.

18. Có bao nhiêu số không quá 1000 mà $a)$ chia hết cho cả 6 và 15; $b)$ chia hết cho 3 nhưng không chia hết cho 7; $b)$ chia hết cho 6 hoặc 15.

19. Có bao nhiêu số tự nhiên không quá 1000 không chia hết cho 3, 5, 7?

20. Hợp của tập hợp $A$ và $B$ bao gồm 25 phần tử, giao điểm - gồm 10 phần tử. Có bao nhiêu phần tử trong tập hợp $A$ nếu có 15 phần tử trong $B$; $6$ 21 yếu tố; $b)$ 10 yếu tố?

21. Tháng 12 có 10 ngày trong xanh và lặng gió, 15 ngày có gió và 12 ngày có tuyết. Đã có bao nhiêu ngày có bão tuyết (cả tuyết và gió)?

22. Trong một nhóm 25 học sinh, có 12 em học tiếng Latinh, 10 học tiếng Hy Lạp và 9 tiếng Phạn. Cứ hai ngôn ngữ thì có đúng 5 học sinh đang học về những ngôn ngữ này. Có bao nhiêu học sinh học cả ba ngôn ngữ?

23. Trên mỗi cạnh của tam giác $ABC$ 9 điểm được đánh dấu và chia thành 10 phần bằng nhau. Hãy sắp xếp tất cả các hình tam giác có thể có các đỉnh ở các điểm lệch nhau (mỗi bên một cạnh). Có bao nhiêu hình tam giác trong đó một cạnh không song song với cạnh của tam giác $ABC$?

Văn học

1. I. M. Vinogradov. “Cơ sở cơ bản của lý thuyết số” (M., “Nauka”, 1980).

2. I. I. Ezhov, A. V. Skorokhod, M. I. Yadrenko. “Các yếu tố của tổ hợp” (Moscow, “Nauka”, 1977).

3. L. A. Kaluzhin. “Định lý cơ bản của Alfmetic” (Moscow, “Nauka”, 1969).

4. O. Ore. “Lời mời đến lý thuyết số” (M., “Nauka”, Thư viện «Kvant», 1980).

5. L. A. Basova, M. A. Shubin, L. A. Epstein. “Các bài giảng và bài toán về toán học” (M., “Prosveshcheniye”, 1981).

6. Tối ưu hóa toán học tương ứng (M., “Nauka”, 1981).

7. R. Courant, G. Robbins. "Toán học là gì?" (M., “Khai sáng”, 1967).
