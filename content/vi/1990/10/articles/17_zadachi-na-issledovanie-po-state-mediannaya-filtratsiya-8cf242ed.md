---
id: 1990-10-zadachi-na-issledovanie-po-state-mediannaya-filtratsiya-8cf242ed
issue: kvant_1990_10
year: 1990
number: "10"
title: Bài toán cho nghiên cứu bài viết “Lọc trung vị”
rubric: raznoe
page_first: 49
page_last: 53
page_labels: 47, 49, 50, 51
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 8bf97d4b2b63b88ce8fe4b5f827848e3e1df22080d37f0766ab5f92b69ba5eee
prompt_sha256: draft-1
translated_from: content/ru/1990/10/articles/17_zadachi-na-issledovanie-po-state-mediannaya-filtratsiya-8cf242ed.md
source_content_sha256: 7afa5e2c26afc78614f40d6eb48de968140bb768500062c9e1feb19395669d7a
translation_model: draft
translation_run: vi-draft-gaps-2026-11-05
translation_quality: draft
---

⟦folio 47⟧

Nhiệm vụ nghiên cứu thống kê “Lọc trung vị”

(xem trang 8)

1. Chứng minh rằng nếu chuỗi $x_n$ bất biến dưới bộ lọc trung vị có độ rộng cửa sổ $2k+1$ và các số hạng của nó nhận ít nhất ba giá trị khác nhau, thì nó bất biến dưới bất kỳ bộ lọc trung vị nào có độ rộng cửa sổ nhỏ hơn.

Khi đánh dấu e. Điều kiện thứ hai là cần thiết. Ví dụ: "saw" $x_n=(-1)^n$ là bất biến đối với các bộ lọc có $k$ chẵn và không bất biến đối với các bộ lọc có $k$ lẻ.

2. Chuỗi hữu hạn tiếp tục đến vô hạn bằng cách lặp lại các phần tử cực trị ở bên trái và bên phải của phần tử tương ứng. Chứng minh rằng nếu độ dài của chuỗi là $l$ thì sau $\left[\frac{l-1}{2}\right]$ áp dụng bộ lọc trung vị với chiều rộng cửa sổ $2k+1$, sẽ thu được một chuỗi bất biến (ở đây [] là phần nguyên của số).

Kiểm tra xem cách trình tự tiếp tục có ý nghĩa hay không (ví dụ: tại $l=2$).

3. Bộ lọc trung vị đệ quy là bộ lọc trung vị trong đó các số $k$ đầu tiên của cửa sổ trượt được lấy từ chuỗi đã lọc, tức là chuỗi $x_n$ được chuyển thành chuỗi $y_n=m(y_{n-k}, y_{n-k+1}, \dots, y_{n-1}x_n, x_{n+1}, \dots, x_{n+k})$ (được coi là $x_n \equiv x_0$ khi $n<0$).

a) Chứng minh rằng một dãy bất biến dưới bộ lọc trung vị đệ quy khi và chỉ nếu nó bất biến dưới bộ lọc trung vị tổng quát.

b) Chứng minh rằng bất kỳ dãy nào sau khi đi qua bộ lọc trung vị đệ quy đều trở thành bất biến.

4. Chúng ta sẽ nói rằng dãy $x_n$ có điểm giữa bằng $a$ nếu với bất kỳ $\varepsilon>0$ nào tồn tại một $M$ sao cho với mọi $n$ và $m>M$

$$|m(x_{n-m}, x_{n-m+1}, \dots, x_n, \dots, x_{n+m-1}, x_{n+m}) - a| < \varepsilon.$$

Chứng minh rằng bộ lọc trung vị bảo toàn điểm giữa, tức là chuỗi thu được từ $x_n$ ở đầu ra của bộ lọc có cùng điểm giữa $a$.

5. Chúng ta sẽ nói rằng chuỗi $x_n$ có mức $a$ nếu với bất kỳ $\varepsilon>0$ nào có $M$ sao cho với mọi $n$ và $m>M$

$$|x_{n-m}+x_{n-m+1}+\dots+x_n+\dots+x_{n+m-1}+x_{n+m}| - a| < \varepsilon.$$

Có đúng là a) bộ lọc trung vị, b) các điều kiện trượt bảo toàn mức độ nhất quán không?

⟦folio 49⟧

---
running_head:
folio:
---

hoặc phân tích - ai thắng? Và Yu. Nesterenko hóa ra lại là nhân chứng cho cuộc tranh chấp này. Đối thủ của tôi là những nhà hình học hăng hái, và tôi phải làm điều đó. Nhưng đối thủ của tôi vẫn chưa giành được chiến thắng rõ ràng. Điều này được mô tả trong cuốn sách “Những câu chuyện về mức tối đa và mức tối thiểu” của tôi (Thư viện «Kvant», số 56, M., Nauka, 1986, trang 134-139). Và sau đó (như chính tác giả đã nói với tôi) Yu. Nesterenko bắt đầu tìm kiếm bài toán, nơi trí tưởng tượng hình học sẽ chiến thắng sự tẻ nhạt trong phân tích với lợi thế rõ ràng. Và anh ấy thực sự đã nghĩ ra nó! Bài toán đã được trình bày tại Olympic toàn liên bang lần thứ 19 dành cho học sinh năm 1985. Đây là cách diễn đạt của nó.

Cho một khối lập phương $ABCD_1B_1C_1D_1$ từ cạnh hai. Chúng ta hãy vẽ hai đường tròn: một đường tròn ngoại tiếp hình tam giác được tạo bởi các đỉnh không liền kề $AB_1C$, đường còn lại ngoại tiếp mặt $ABCD$. Cần phải tìm khoảng cách tối thiểu giữa các vòng tròn này (hình 1).

Và thực sự - bây giờ chúng ta sẽ thấy điều này - nó có thể được giải “bằng hai từ”, nhưng việc tìm ra chúng khá khó khăn (đặc biệt là trong bối cảnh một kỳ thi Olympic hoặc một kỳ thi). Chúng ta sẽ đề cập đến chủ đề thú vị này ở cuối bài viết và bây giờ hãy chuyển sang lời giải.

Đầu tiên, “hai từ” ủng hộ lời nói. Hình tròn nhỏ nằm trên hình cầu có bán kính $\sqrt{2}$ có tâm ở tâm hình lập phương, hình tròn lớn nằm trên hình cầu có bán kính $\sqrt{3}$ có cùng tâm, nghĩa là khoảng cách ngắn nhất giữa các hình tròn không nhỏ hơn $\sqrt{3} - \sqrt{2}$. Nhưng vết trên hình cầu lớn hơn của hình nón có đỉnh ở giữa hình lập phương chứa một đường tròn nhỏ giao nhau (như dễ hiểu) đường tròn lớn hơn (hình 2), tức là có hai điểm trên các đường tròn khác nhau, khoảng cách giữa chúng là $\sqrt{3} - \sqrt{2}$.

Điều này có nghĩa là khoảng cách tối thiểu bằng $\sqrt{3} - \sqrt{2}$! Mọi thứ đã được chứng minh. Tuy nhiên, hãy ghi nhớ những so sánh sâu hơn, chúng ta hãy mô tả “hai từ” này chi tiết hơn một chút. Vì vậy, chúng tôi trình bày để bạn xem xét hai lời giải - hình học và phân tích. Để giúp bạn dễ dàng so sánh “ưu điểm” và “nhược điểm” của lời giải này, chúng tôi đã xem những điểm chính trong mỗi chúng (“di chuyển”, “bước” - tùy thích) bằng một số trong ngoặc vuông. Nếu một nước đi có vẻ giống như một “cái nhìn sâu sắc” đối với chúng tôi, chúng tôi sẽ đặt nó bên cạnh con số! (hoặc thậm chí!!).

Lời giải đầu tiên (hình học). Chúng ta biểu thị đường tròn ngoại tiếp là $O_1$, đường tròn ngoại tiếp là $O_2$ và tâm của hình lập phương là $O$. Sau đó:

[1]. Vòng tròn $O_1$ nằm trên một hình cầu có tâm $O$ và bán kính $\sqrt{3}$.
[2]. Vòng tròn $O_2$ nằm trên một hình cầu có tâm $O$ và bán kính $\sqrt{2}$.
[3!]. Từ kết quả trên cho thấy khoảng cách tối thiểu cần thiết là $\rho \geqslant \sqrt{3} - \sqrt{2}$.

Hình 1.

Hình 2.

⟦folio 50⟧

---
running_head:
folio:
---

[4]. Chúng ta hãy dựng một bề mặt hình nón có đỉnh ở tâm $O$, nối nó với các tia tới các điểm của đường tròn $O_2$.

[5]. Khi đó đường sinh của hình nón—tia $OU'$ (hình 2)—nằm bên dưới $O_1$.

[6]. Ma trận của hình nón $OV'$ (hình 2) nằm phía trên $O_1$ (dễ đếm).

[7!!]. Từ hai phát biểu cuối cùng và thông điệp liên tục, suy ra rằng điểm hiện có $E$ trên $O_2$ sao cho tia $OE$ “tạo ra” đường tròn $O_1$ tại điểm $E'$,

[8] và do đó khoảng cách từ $E$ đến $E'$ bằng $\sqrt{3} - \sqrt{2}$, tức là $\rho \leqslant \sqrt{3} - \sqrt{2}$.

[9]. Vì vậy, $\rho = \sqrt{3} - \sqrt{2}$.

Màu đỏ tuyệt vời lời giải phải không? Bạn sẽ thích nó hơn nữa nếu bạn tự mình tìm thấy nó. Số người giải được câu bài toán này tại Olympic không hề nhỏ - từ năm đến mười người - và tất cả họ đều giải được như thế này, về mặt hình học. Nhưng chúng tôi có một con đường khác phía trước.

Nhưng trước khi chuyển sang phương pháp tương tự lời giải, tôi phải giới thiệu với bạn một phương pháp phân tích nghiên cứu rất quan trọng bài toán về cực trị, được phát hiện bởi Lagrange (Tôi đã dành một phần quan trọng trong cuốn sách nói trên của mình cho phương pháp này - hãy xem câu chuyện trong ngày). Với sự giúp đỡ của Lagrange, tôi đã bảo vệ một phần của những cái tương tự trong những điều kiện nhất định kết nối các biến $x, y, z$, $u$. Ví dụ,

$$f_1(x, y, z, u) = 0,$$
$$f_2(x, y, z, u) = 0,$$
trong đó $f_1$ và $f_2$ là dữ liệu hàm.

Sau đó (Trạng thái Lagrange) lời giải, nếu nó tồn tại, có thể được tìm thấy bằng phương pháp sau.

Giả sử $\lambda_0, \lambda_1$ và $\lambda_2$ là một số số (chúng ta chưa biết), không phải tất cả đều bằng 0.

Hãy xem xét chức năng

$$L = \lambda_0 f_0 + \lambda_1 f_1 + \lambda_2 f_2.$$

Đặt $L_x, L_y, L_z$ và $L_u$ là hàm tùy ý $L$ trong các biến $x, y, z, u$. Khi đó điểm $(x_0, y_0, z_0, u_0)$, tại đó đạt cực tiểu (cực đại) của hàm $f_0$, được cho bởi hệ phương trình

$$\begin{cases} f_1(x, y, z, u) = 0, \\ f_2(x, y, z, u) = 0, \\ L_x = L_y = L_z = L_u = 0. \end{cases}$$

(Lưu ý đây là hệ gồm 6 phương trình có 7 ẩn số, từ đó tìm ra các số $x_0, y_0, z_0, u_0$ và $\lambda_0, \lambda_1, \lambda_2$.)

Ví dụ này rất phổ biến, về mặt kỹ thuật rất đơn giản và để áp dụng nó không cần gì ngoại trừ một khái niệm tùy ý. Hãy sử dụng nó cho lời giải bài toán của chúng tôi.

Lời giải giây (phân tích).

[1]. Vòng tròn $O_2$ được thể hiện là $x = \cos \varphi, y = \sin \varphi, z = -1, -\pi \leqslant \varphi \leqslant \pi$.

[2]. Chúng ta xác định đường tròn $O_1$ là giao điểm của hình cầu $x^2 + y^2 + z^2 = 3$ và mặt phẳng $x - y + z = -1$.

[3]. Telery bài toán được xây dựng như sau. Tìm cực tiểu của hàm số

$$f_0(x, y, z, \varphi) = (x - \cos \varphi)^2 + (y - \sin \varphi)^2 + (z + 1)^2$$

trong điều kiện

$$f_1(x, y, z) = x - y + z + 1 = 0,$$
$$f_2(x, y, z) = x^2 + y^2 + z^2 - 3 = 0.$$

[4]. Dễ hiểu là chỉ cần xét ngành $-\frac{\pi}{2} \leqslant \varphi \leqslant \frac{\pi}{2}$ là đủ.

[5]. Hãy xây dựng hàm Lagrange

$$L = \lambda_0 ((x - \cos \varphi)^2 + (y - \sin \varphi)^2 + (z + 1)^2) + \lambda_1 (x - y + z + 1) + \lambda_2 (x^2 + y^2 + z^2 - 3)$$

và tính toán những cái tùy ý của nó:

$$L_\varphi = 2\lambda_0 ((x - \cos \varphi) \sin \varphi) - (y - \sin \varphi) \cos \varphi) = 0,$$

$$L_x = 2\lambda_0 (x - \cos \varphi) + \lambda_1 + 2\lambda_2 x = 0,$$

$$L_y = 2\lambda_0 (y - \sin \varphi) - \lambda_1 + 2\lambda_2 y = 0,$$

$$L_z = 2\lambda_0 (z + 1) + \lambda_1 + 2\lambda_2 z = 0.$$

⟦folio 51⟧

---
running_head:
folio:
---

[6]. Bây giờ hãy giải hệ kết quả (1) - (4). Nếu chúng ta giả sử rằng $\lambda_0 = 0$, thì từ (2) - (4) và phương trình ghép, chúng ta thu được $\lambda_1 = \lambda_2 = 0$ và điều này mâu thuẫn với giả định rằng $\lambda_0^2 + \lambda_1^2 + \lambda_2^2 \neq 0$.

Rõ ràng là các số $\lambda_0, \lambda_1, \lambda_2$ có thể được xác định theo tỷ lệ, vì vậy chúng ta giả sử $\lambda_0 = \frac{1}{2}$. Khi đó từ (1) suy ra
$$x \sin \varphi = y \cos \varphi.$$ (5)

Ký hiệu $a = -\frac{\lambda_1}{1+2\lambda_2}$, $b = \frac{\lambda_1}{1+2\lambda_2}$ (giả định $1+2\lambda_2=0$ dẫn đến hệ có trọng số rất thấp), ta thu được
$$x = a + b \cos \varphi, y = -a + b \sin \varphi, z = a - b.$$ (6)

[7]. Từ (6) và (5) suy ra ngay $a(\cos \varphi - \sin \varphi) = 0$, và điều này dẫn đến phương án
$$i) a = 0, (ii) \sin^2 \varphi + \cos \varphi = 0 (\Leftrightarrow \varphi = -\frac{\pi}{4}).$$ (7)

[8]. Nếu (i), thì từ (6) (với $a=0$) và $x^2+y^2+z^2=3$ ta thu được
$$b^2(\cos^2 \varphi + \sin^2 \varphi + 1) = 3 \Rightarrow b = \pm \sqrt{\frac{3}{2}}.$$ (8)

[9]. Nếu (ii) thì (dễ tính)
$$(x_0, y_0, z_0) = \left( \frac{1}{3}, -\frac{1}{3}, \frac{5}{3} \right).$$ (9)

[10]. Trong trường hợp (i)
$$(x - \cos \varphi)^2 + (y - \sin \varphi)^2 + (z + 1)^2 = (b - 1)^2(\cos^2 \varphi + \sin^2 \varphi + 1) = (\sqrt{3} - \sqrt{2})^2.$$

[11]. Trong trường hợp (ii), khoảng cách giữa các điểm $\left( \frac{1}{\sqrt{2}}, -\frac{1}{\sqrt{2}}, -1 \right)$ và $\left( \frac{1}{3}, -\frac{1}{3}, \frac{5}{3} \right)$ lớn hơn $\sqrt{3} - \sqrt{2}$. Đáp số: $\rho = \sqrt{3} - \sqrt{2}$.

Chà, bây giờ chúng ta hãy triết lý một chút. Chúng tôi đã đề cập đến hai chủ đề: 1) ai sẽ thắng? và 2) có bài toán có số nguyên tố lời giải, tuy nhiên rất khó tìm thấy?

Vậy lời giải đã đẹp chưa? Không thể nghi ngờ gì về điều đó, và tôi sẽ ngay lập tức trở thành người chiến thắng thứ một triệu. Nhưng xin phép tôi, sau khi khiêm tốn chấp nhận thất bại của mình, vẫn nói được vài lời.

Trước hết, tôi yêu cầu các bạn (hoặc giám khảo?) thân mến của tôi hãy chú ý đến thực tế là tôi không chỉ tìm thấy đáp số mà còn nhận được lời giải. Thật vậy, trong trường hợp (i), dẫn chúng ta đến đáp số, từ sự tương ứng (2) - (4) cho $a=0$ và từ biểu thức cho $b$, chúng ta thu được $\cos \varphi - \sin \varphi = 1 - \sqrt{\frac{2}{3}}$, từ đó tìm thấy ngay $\varphi$ mong muốn. Và bạn, những nhà hình học thân mến, vẫn phải làm việc một chút. Nhưng nhân tiện, đó là sự thật.

Thứ hai, tôi muốn công nhận phân tích vì thực tế là không có dấu chấm than trong kiểm tra phân tích lời giải. “Cái này thế nào?” - bạn hỏi. Hãy nhớ: - Tôi dùng dấu chấm than (như trong ván cờ) để biểu thị những nước đi đặc biệt đẹp mắt, bất ngờ. Vì vậy, tôi ghi nhận phân tích chính xác về thực tế là nó giúp bạn có thể đạt được mục tiêu theo một cách thông thường, tiêu chuẩn mà không cần bất kỳ “sự tiết lộ” nào. Đúng, nó dài hơn một chút (mười một bước thay vì tám, nhưng rất nhiều điều tầm thường, tiêu chuẩn, hoàn toàn cơ bản). Và bạn nhớ nhé, con đường này mang tính phổ quát. Rốt cuộc, nếu bạn thay đổi bài toán một chút, thì sẽ xảy ra trường hợp bạn, nhà hình học thân yêu của tôi, sẽ lại buộc phải chờ đợi sự hiểu biết sâu sắc, và con đường tiêu chuẩn (có thể với sự trợ giúp của máy tính) chắc chắn sẽ dẫn đến mục tiêu. Tuy nhiên, hãy nhớ cho tôi: tại sao tôi đột nhiên bắt đầu thắc mắc. Tranh chấp chưa kết thúc, không thể kết thúc! Bước tiếp theo là của bạn, người hâm mộ hình học thân mến của tôi!

Bây giờ - về chủ đề thứ hai. Vâng, thật kỳ lạ, có bài toán với lời giải rất đơn giản, cực kỳ khó tìm. Chúng tôi đang thảo luận - trong số họ (nếu chúng tôi không cho rằng khả năng áp dụng phương pháp phân tích). Một đặc điểm đặc trưng của bài toán như vậy là sự hiện diện của “dấu chấm than”. Nếu chúng ta phá vỡ bằng chứng của hầu hết

(Về phần kết xem trang 62)
