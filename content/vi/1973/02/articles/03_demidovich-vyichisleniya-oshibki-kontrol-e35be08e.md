---
id: 1973-2-demidovich-vyichisleniya-oshibki-kontrol-e35be08e
issue: kvant_1973_2
year: 1973
number: "2"
title: Tính toán, lỗi, kiểm soát
authors:
  - Демидович Н. Б.
rubric: osnovnye-stati
page_first: 13
page_last: 18
page_labels: 11-16
tag: KYHH
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 30510d4b1fb3cbd6e19987ca67ef6da0a27d054c71cbfad73bea74eb42eb9ed7
prompt_sha256: draft-1
translated_from: content/ru/1973/02/articles/03_demidovich-vyichisleniya-oshibki-kontrol-e35be08e.md
source_content_sha256: 9161f4fb26fdee153bf16871ebc42397b556d2a9c3802340442724bd4be546cf
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 11⟧

Tính toán, lỗi, kiểm soát
N. B. Demidovich

Lỗi quan sát
Đếm chính xác không phải lúc nào cũng có nghĩa là đếm đúng. Khoảng cách ví dụ sau đây là bài toán.
Cạnh của mảnh đất hình vuông là 1,4 m. Nửa chu vi p và diện tích S của nó là bao nhiêu (Hình 1)?
Lời giải là tự định hướng: $p = 1,4 + 1,4 = 2,8$ ($m$), $S = 1,4 \times 1,4 = 1,96$ ($m^2$). Nhưng điều này chính xác đến mức nào đáp số? Hoàn toàn chính xác nếu độ dài cạnh của mặt cắt được xác định chính xác. Điều gì sẽ xảy ra nếu nó không được chỉ định, nhưng, ví dụ, được đo bằng thước dây decimet? Khi đó, điều tự nhiên là giả định rằng 1,4 m là độ chia của thước dây, gần với chiều dài thực của cạnh được đo của địa điểm. Từ đây chỉ rõ rằng chiều dài chính xác khác với 1,4 m không quá 0,05 m, nghĩa là giá trị tuyệt đối của sai số quan sát (nó được gọi là giá trị tuyệt đối)

Cơm. 1.

của giá trị đo x và được chỉ định $\Delta_x$) không vượt quá 0,05 m.

Một câu hỏi thực tế quan trọng được đặt ra: diện tích có thể được xác định với độ chính xác như thế nào ở các điều kiện tiên quyết đã chỉ định? Câu hỏi này và các câu hỏi tương tự được giải quyết bởi một nhánh toán học đặc biệt - lý thuyết tính toán gần đúng. Hãy để chúng tôi chứng minh các phương pháp của nó bằng cách sử dụng bài toán này.

Đặt chiều dài thực của cạnh (sau đây tất cả các chiều dài được đo bằng mét) bằng 1,4 + $\alpha$, trong đó $|\alpha| \leq 0,05$, tức là $0,5 \leq \alpha \leq 0,05$. Khi đó nửa chu vi của phần bằng $p = (1,4 + \alpha) + (1,4 + \alpha) = 2,8 + 2\alpha$.

Sai số tuyệt đối $\Delta_p$ của giá trị nửa chu vi là 2,8 không vượt quá $2 \times 0,05 = 0,1$, tức là $2,7 = 2,8 - 0,1 \leq p \leq 2,8 + 0,1 = 2,9$.

Công thức dễ dàng kiểm tra
$$\left|(x_{\text{прибл.}} \pm y_{\text{прибл.}})\right| \leq \Delta_x + \Delta_y$$

cho thấy rằng khi cộng và trừ các số, sai số tuyệt đối của chúng cộng lại.

Khi nhân các số, sẽ thuận tiện hơn khi xử lý lỗi tương đối. Sai số tương đối $\Delta_x$ của số x được gọi là tỉ số giữa sai số tuyệt đối $\Delta_x$ với giá trị tuyệt đối của số x: $\varepsilon_x = \frac{\Delta_x}{x_{\text{точн}}}$. Bởi vì $x_{\text{точн}}$ chúng tôi

⟦folio 12⟧

chúng tôi không biết, chúng tôi có thể thay thế $\varepsilon'_x$ bằng $\varepsilon_x$, trong đó $\varepsilon_x = \frac{\Delta_x}{x_{\text{прибл}}}$. Trong ví dụ này $\varepsilon_x = \frac{0,05}{1,4} \approx 0,036 = 3,6\%$.

Tất nhiên, bằng cách thay thế các giá trị của $\varepsilon'_x = \frac{\Delta_x}{x_{\text{точн}}}$ bằng $\varepsilon_x = \frac{\Delta_x}{x_{\text{прибл}}}$, chúng tôi cho phép xảy ra một số lỗi nhưng nó thường nhỏ đến mức luôn bị bỏ qua.

Khi nhân và chia các số, sai số tương đối của chúng sẽ được cộng thêm. Chúng tôi để lại bằng chứng của tuyên bố này cho người đọc; thì chúng ta chỉ cần ước tính số lượng

$$\varepsilon_{xy} = \left| \frac{(x + \alpha)(y + \beta) - xy}{xy} \right|$$

Và

$$\varepsilon_{\frac{x}{y}} = \left| \frac{\frac{x + \alpha}{y + \beta} - \frac{x}{y}}{\frac{x}{y}} \right|.$$

Bây giờ chúng ta hãy quay lại bài toán của chúng tôi. Diện tích của trang web được lấy bằng tích của chiều dài các cạnh, do đó sai số tương đối của nó là 7,2%. Các tính toán được chấp nhận cho

$$S = (1,4 + \alpha)^2 = 1,96 + 2,8\alpha + \alpha^2.$$

Ở đây 1,96 là đáp số ban đầu của chúng tôi và hai số hạng còn lại là độ lệch của nó so với đáp số chính xác. Hãy ước lượng sai số tuyệt đối của kết quả:

$$\Delta_S \leq |2,8\alpha + \alpha^2| \leq |2,8\alpha| + \alpha^2 \leq |2,8 \cdot 0,05| + |0,05|^2 = 0,1425 < 0,15.$$

Điều này có nghĩa là diện tích $S$ nằm trong

$$1,81 = 1,96 - 0,15 < S < 1,96 + 0,15 = 2,11.$$

Công thức cuối cùng cho thấy rõ ràng rằng trong công thức gốc đáp số 1.96, chứa hai dấu của công thức cuối cùng, có thể không có một chữ số đúng nào.

Do đó, lý thuyết tính toán gần đúng giải phóng chúng ta khỏi ảo tưởng rằng số lượng lớn hơn các chữ số được tính toán chính xác luôn đảm bảo độ chính xác tương ứng của chính kết quả. Hơn nữa, nó mang lại đáp số, độ chính xác của kết quả phụ thuộc vào độ chính xác của dữ liệu ban đầu, số lượng và loại hành động được thực hiện trên chúng.

Làm tròn số

Trong ví dụ ban đầu, chúng tôi đã quyết định rằng số 1,4 m có được bằng cách thay đổi nó bằng thước dây decimet và do đó sai số của thay đổi không vượt quá 7,2%. Các tính toán được chấp nhận cho

$$S = (1,4 + \alpha)^2 = 1,96 + 2,8\alpha + \alpha^2.$$

Ở đây 1,96 là đáp số ban đầu của chúng tôi và hai số hạng còn lại là độ lệch của nó so với đáp số chính xác. Hãy ước lượng sai số tuyệt đối của kết quả:

$$\Delta_S \leq |2,8\alpha + \alpha^2| \leq |2,8\alpha| + \alpha^2 \leq |2,8 \cdot 0,05| + |0,05|^2 = 0,1425 < 0,15.$$

Điều này có nghĩa là diện tích $S$ nằm trong

$$1,81 = 1,96 - 0,15 < S < 1,96 + 0,15 = 2,11.$$

Công thức cuối cùng cho thấy rõ ràng rằng trong công thức gốc đáp số 1.96, chứa hai dấu của công thức cuối cùng, có thể không có một chữ số đúng nào.

Do đó, lý thuyết tính toán gần đúng giải phóng chúng ta khỏi ảo tưởng rằng số lượng lớn hơn các chữ số được tính toán chính xác luôn đảm bảo độ chính xác tương ứng của chính kết quả. Hơn nữa, nó mang lại đáp số, độ chính xác của kết quả phụ thuộc vào độ chính xác của dữ liệu ban đầu, số lượng và loại hành động được thực hiện trên chúng.

Một ví dụ

Đặc biệt, trong lý thuyết tính toán gần đúng, các ví dụ tính toán cũng được phát triển, đồng thời đảm bảo đạt được độ chính xác cần thiết của kết quả, giảm số lượng thao tác xuống mức tối thiểu.

Ví dụ: hãy xem xét phép nhân các phân số thập phân thích hợp dương $n$-bit, nghĩa là các số có dạng

$$A = 0, a_1 a_2 \dots a_n,$$

ở đâu $0 \leq a_i \leq 9$ ($i = 1, 2, \dots, n$). Được biết, phân số thập phân (1) là viết tắt của số

$$A = \frac{a_1}{10} + \dots + \frac{a_i}{10^i} + \dots + \frac{a_n}{10^n}.$$

⟦folio 13⟧

Chúng ta sẽ coi phân số (1) là một số gần đúng, được làm tròn chính xác. Khi đó nó có sai số tuyệt đối không vượt quá $\frac{5}{10^{n+1}}$.

Cho phép

$$A = 0, a_1 a_2 \dots a_n,$$
$$B = 0, b_1 b_2 \dots b_n$$

là hai số gần đúng và $\alpha$ và $\beta$ là độ lệch tương ứng của chúng so với các số chính xác và giống nhau: $|\alpha| \leq 0,5 \cdot 10^{-n}, |\beta| \leq 0,5 \cdot 10^{-n}$. Hãy tính sai số tuyệt đối của tích:

$$\Delta_{AB} = (A + \alpha) \cdot (B + \beta) - AB = \alpha \cdot B + \beta \cdot A + \alpha \cdot \beta.$$

Ở đây $|\alpha \cdot \beta| = |\alpha| \cdot |\beta| \leq 0,5 \times 10^{-n} \cdot 0,5 \cdot 10^{-n} = 0,25 \cdot 10^{-2n}$, nghĩa là thuật ngữ này trong mô đun không vượt quá bốn chữ số cuối cùng có thể có của kết quả và do đó có thể không được tính đến. Chúng ta hãy ước tính tổng của hai số hạng ở giữa, có tính đến $A < 1$ và $B < 1$. Chúng tôi nhận được $|\alpha \cdot B + \beta \cdot A| < |0,5 \cdot 10^{-n} \cdot 1| + 0,5 \cdot 10^{-n} \cdot 1| = 10^{-n}$.

Điều này có nghĩa là trong số $2n$ chữ số của sản phẩm, chỉ có chữ số $n-1$ đầu tiên được đảm bảo là chính xác, chữ số thứ $n$, nhờ vào (2), hóa ra là thành phần (nó có thể khác với chữ số đúng $\pm 1$). Công thức (2) không đảm bảo tính chính xác của các số $(n+1)$ trở lên. Vì vậy, những con số này không có gì để đưa vào đáp số cuối cùng.

Theo đó, khi nhân các số gần đúng theo cách học - “thang bên trái” - chúng ta thực hiện một nửa công việc một cách vô ích. Chúng tôi hỏi, liệu có thể không làm một nửa công việc này không? Hóa ra là có thể. Để làm điều này, bạn cần sử dụng phương pháp nhân rút gọn - “thang bên phải”. Hơn nữa, để trình bày rõ ràng, chúng tôi sẽ giới hạn ở ví dụ nhân các số gần đúng $0,587 \times 0,736$.

Như các bạn đã biết, nhân số thập phân cũng tương tự như nhân số nguyên. Dưới đây là ba cách để nhân

$$\times 0,587 \times 0,587 \times 0,587$$
$$\times 0,736 \times 0,736 \times 0,736$$
$$\times 4109 \times 4109 \times 4109$$
$$1761 + 1761 + 1761 + 1761$$
$$4109 \times 3522 \times 3522 \times 3522$$
$$0,4320 \times 0,4320 \times 0,4320$$

(a) - “thang bên trái” (trường học);

Với phương pháp (6), không giống như phương pháp (a), phép nhân bắt đầu bằng chữ số cao nhất của số bị nhân và số nhân; đơn vị truyền từ chữ số bên phải liền kề của số bị nhân (ít thường xuyên hơn từ hai số liền kề) được tính ngay lập tức. Sau một thời gian luyện tập, phương pháp này không còn khó khăn hơn phương pháp (a).

Phương pháp (c) là một sửa đổi rút gọn của phương pháp (6), trong đó tích từng phần không được tính đến cuối mà được làm tròn ngay lập tức. Vị trí làm tròn cung cấp thêm một chữ số trong đáp số cuối cùng, cần thiết để làm tròn chính xác chữ số cuối cùng, thành phần,.

Được rồi, đáp số cuối cùng được tìm thấy bằng tất cả các phương pháp tính toán đó sẽ là 0,432. Để có được nó bằng phương pháp (c), công sức và thời gian chỉ bằng một nửa so với sử dụng phương pháp (a) và (6). Cách tiếp cận này được đặc biệt khuyến khích bởi nhà toán học, kỹ sư và thợ đóng tàu xuất sắc của Liên Xô, Viện sĩ A. N. Krylov, người có cuốn sách *) mà chúng tôi giới thiệu cho độc giả.

Xấp xỉ liên tiếp và kiểm soát tính toán

Tính gần đúng của dữ liệu nguồn (lỗi quan sát và thay đổi) không phải là nguyên nhân duy nhất gây ra lỗi trong kết quả. Một nguồn sai số khác trong kết quả là bản chất gần đúng của chính quá trình tính toán. Nguyên nhân của hiện tượng này là

*) A. N. Krylov, Bài giảng về tính toán gần đúng, M., FM, 1954.

⟦folio 14⟧

cho biết nhu cầu cơ bản để kiểm tra phép tính chính xác (ví dụ: $\sqrt{2}$, sin $20^\circ$) hoặc sự bất tiện khi sử dụng công thức chính xác của kết quả (ví dụ: phân số đơn giản chính xác $1/7$, theo quy tắc, được thay thế bằng phân số thập phân gần đúng 0,143). Việc phát triển các phương pháp tính toán với mức độ chính xác định trước là một lĩnh vực ứng dụng quan trọng của phép tính toán học cổ điển. Người đọc sẽ biết được các phương pháp này bằng cách xem trang cuối cùng của bảng Bradis. Có các công thức - cái gọi là chuỗi vô hạn - theo đó các giá trị của sin, tiếp tuyến, logarit và các hàm dạng bảng khác được tính toán. Phân tích các công thức này cho thấy kỹ thuật phương pháp chính - thay thế phép tính hàm ban đầu bằng phép tính đa thức, nghĩa là một hàm khác, đơn giản hơn, các giá trị của nó, với một mức độ chính xác nhất định, bằng với các giá trị của hàm ban đầu.

Một cách khác để kiểm tra phép tính với mức độ chính xác nhất định là phương pháp xấp xỉ liên tiếp. Hãy chứng minh điều đó bằng cách tính căn bậc hai của số $A$.

Khi xấp xỉ bằng 0 $\sqrt{A}$, chúng ta lấy một số dương tùy ý $x_0$.

Chúng ta hãy xem xét một đoạn trên trục số (Hình 2) được giới hạn bởi các điểm $x_0$ và $\frac{A}{x_0}$. Hãy xây dựng phép tính gần đúng thứ hai $x_1$ làm trung bình số học của $x_0$ và $\frac{A}{x_0}$:

$$x_1 = \frac{1}{2} \left( x_0 + \frac{A}{x_0} \right) :$$

Theo tính chất của trung bình số học, chúng ta có $x_0 \leqslant x_1 \leqslant \frac{A}{x_0}$ và theo tính chất đại lượng nghịch đảo $\frac{A}{x_0} \geqslant \frac{A}{x_1} \geqslant x_0$. Nói cách khác, đoạn

$$\left| \frac{A - x^2}{A + x^2} \right| < 1.$$

Các đoạn này co lại thành một điểm duy nhất $x$, thuộc về tất cả các đoạn. Để tính $x$, chúng ta thay nó vào công thức (3): $x = \frac{1}{2} \cdot \left( x + \frac{A}{x} \right), x = \frac{A}{x}, x = \sqrt{A}$.

Điểm $x = \sqrt{A}$ thuộc tất cả các đoạn thẳng nên $x_n$ hướng về $x = \sqrt{A}$, tức là phương pháp xấp xỉ liên tiếp giải được

⟦folio 15⟧

được đặt thành bài toán. Cần lưu ý rằng phép tính sẽ dừng sau khi $x_{n+1}$ trở thành bằng $x_n$ với số chữ số thập phân nhất định.

Phương pháp xấp xỉ liên tiếp có một ưu điểm lớn: sai số ngẫu nhiên trong các tác động trung gian sẽ không ảnh hưởng đến độ lớn của kết quả mà chỉ làm tăng thời gian để thu được kết quả đó.

Nhìn chung, khi thực hiện tính toán cần hết sức chú ý đến việc điều khiển. Tất nhiên, quá trình tính toán có thể được lặp lại một lần nữa, nhưng điều này sẽ tăng gấp đôi tổng thời gian chạy. Trong những trường hợp đặc biệt quan trọng, cần phải thực hiện bước này, nhưng cũng có thể áp dụng các phương pháp kiểm soát khác, có tính đến các chi tiết cụ thể của một phép tính cụ thể. Ví dụ: nếu sin $x$ và cos $x$ được tính từ một đối số $x$, thì việc tính $\sin^2 x + \cos^2 x$ và so sánh với sự thống nhất là điều đương nhiên.

Một ví dụ khác

Đặc biệt quan tâm là một kỹ thuật cho phép bạn kiểm soát từng giai đoạn tính toán. Hãy để chúng tôi chứng minh điều đó bằng ví dụ lời giải về hệ phương trình đại số tuyến tính.

Cho hệ hai phương trình có hai ẩn số:

$$\begin{align*}
5x + 2y &= 19, \\
3x + 7y &= 23.
\end{align*}$$

Hãy viết ra các hệ số và số hạng tự do của nó dưới dạng bảng:

$$\begin{align*}
\frac{5}{3} &\frac{2}{7} \frac{19}{23} \\
\end{align*}$$

Hãy hoàn thành bảng này bằng cách kiểm soát tổng các phần tử của hàng tương ứng. Ta được bảng tính:

$$\begin{align*}
\frac{5}{3} &\frac{2}{7} \frac{19}{23} \frac{26}{33} \\
\end{align*}$$

Trong phần tiếp theo, chúng ta sẽ coi bảng (5) là hình ảnh của hai hệ thống có các hệ số giống nhau và các số hạng tự do khác nhau: hệ thống (4) và hệ thống

$$\begin{align*}
\frac{5\tilde{x} + 2\tilde{y}}{3\tilde{x} + 7\tilde{y}} &= 26 \\
\frac{1}{3} \left| \frac{0,4}{7} \right| \frac{3,8}{23} \left| \frac{5,2}{33} \right| \\
\end{align*}$$

Giải hệ (4) và (6) bằng phương pháp Gauss, chia tất cả các phần tử của hàng đầu tiên cho số hạng đầu tiên của nó. Hãy lấy cái bàn

$$\left| \frac{1}{3} \right| \frac{0,4}{7} \frac{3,8}{23} \left| \frac{5,2}{33} \right|$$

Điều kiện là ở bất kỳ giai đoạn nào tổng của ba số ở dòng bất kỳ phải bằng số thứ tư; việc này được thực hiện ở đây.

Tiếp theo, nhân tất cả các phần tử của hàng đầu tiên với số hạng đầu tiên của hàng thứ hai. chúng tôi nhận được

$$\left| \frac{3}{3} \right| \frac{1,2}{7} \left| \frac{11,4}{23} \right| \left| \frac{15,6}{33} \right|$$

Trừ từng số hạng từ dòng thứ 2 cho dòng thứ nhất:

$$\left| \frac{3}{0} \right| \frac{1,2}{5,8} \left| \frac{11,4}{11,6} \right| \left| \frac{15,6}{17,4} \right|$$

Từ dòng thứ hai (8) chúng ta có được

$$y = \frac{11,6}{5,8} = 2, \quad \tilde{y} = \frac{17,4}{5,8} = 3.$$

Cuối cùng, từ hàng đầu tiên của bảng (7) chúng ta tìm thấy

$$x = 3,8 - 2 \cdot 0,4 = 3, \\
\tilde{x} = 5,2 - 3 \cdot 0,4 = 4.$$

Đã tìm kiếm lời giải: $x = 3, y = 2$; lời giải hệ thống (6): $\tilde{x} = 4, \tilde{y} = 3$. Có sự bình đẳng

$$\tilde{x} = x + 1, \quad \tilde{y} = y + 1,$$

điều này có nghĩa là hệ thống lời giải là chính xác. Lưu ý rằng nếu các đẳng thức đáp số cuối cùng (9) không được thỏa mãn thì khi kết hợp với một vị trí, việc làm tròn quá thô hoặc có ở đâu đó

⟦folio 16⟧

thì đã phạm phải một sai lầm. Sự hiện diện của cột điều khiển ở mỗi giai đoạn tính toán cho phép bạn nhanh chóng tìm ra vị trí có lỗi hoặc không chính xác.

Bình đẳng (9) là cơ sở lý luận của phương pháp điều khiển. Nếu chúng ta lấy hệ (6), nghiệm của nó là lời giải của hệ (4), tăng thêm một, $x = x + 1$, $y = y + 1$, thì các số hạng tự do của hệ (6) sẽ bằng tổng các hệ số của các hàng của hệ (4). Ví dụ: đối với dòng đầu tiên của hệ thống (4)

$$5(\tilde{x} - 1) + 2(\tilde{y} - 1) = 19,$$
$$5\tilde{x} - 5 + 2\tilde{y} - 2 = 19,$$
$$5\tilde{x} + 2\tilde{y} = 19 + 5 + 2 = 26.$$

Tính chất này có thể dễ dàng được kiểm chứng trong trường hợp tổng quát. Và vì tại lời giải chúng ta chuyển sang các hệ thống tương đương, nên trong đó tổng các hệ số phải bằng các số trong cột điều khiển.

Lỗi phương pháp

Có một nhóm nguyên nhân khác dẫn đến sai sót trong kết quả. Nó được gọi là lỗi phương pháp. Nó được kiểm tra, ví dụ, trong trường hợp, thay vì một hệ phương trình chính xác, một hệ phương trình đơn giản hơn mô tả gần đúng cùng một quá trình được xem xét. Những lý do cho sự thay thế như vậy rất đa dạng: thiếu hệ phương trình chính xác, không có khả năng chuẩn bị dữ liệu ban đầu cho một hệ chính xác, không thể hoặc phức tạp hơn trong việc giải chính xác hệ phương trình chính xác hiện có và các lý do khác. Ví dụ: hãy xem xét bài toán từ sách giáo khoa vật lý.

Máy bay nằm ngang ở độ cao $H$ với tốc độ $v$. Người đó phải thả quả bom cách vật một khoảng bằng bao nhiêu để quả bom trúng thẳng vào vật?

Nếu chúng ta đơn giản hóa giả định thì sẽ không có lực cản trước tác động của tác động đó.

Việc xem xét cần thiết $S$ được lấy từ công thức $S = v \cdot t$ tại $\frac{gt^2}{2} = H$, do đó $S = v \cdot \sqrt{\frac{2H}{g}}$.

Theo giả định này, quỹ đạo của quả bom là parabol (đường cong màu xanh lam trong Hình 3).

Nhưng trên thực tế, khả năng chống va đập sẽ có quỹ đạo lớn hơn. Nó được gọi là “đường cong đạn đạo” (đường cong màu đỏ trong Hình 3) và được xây dựng trên cơ sở dữ liệu thực nghiệm và các đề xuất lý thuyết bổ sung. Đường cong đạn đạo làm giảm đáng kể “sai số phương pháp”, nhưng do đặc điểm thực nghiệm của nó nên nó làm tăng nhẹ “sai số quan sát” và “sai số làm tròn”.

Bây giờ chúng ta có thể rút ra một số kết luận. Các ví dụ và tính toán đã cho cho thấy rằng quá trình tính toán bằng số của bất kỳ bài toán thực tế nào đều phải được lên kế hoạch cẩn thận.

Các giai đoạn dọc theo con đường này là:

1) lựa chọn phương pháp lời giải với ước tính sai số mà nó đưa ra;
2) đánh giá độ chính xác của dữ liệu nguồn;
3) lựa chọn sơ đồ đánh giá độ chính xác của việc làm tròn các giá trị trung gian và tổ chức kiểm soát hợp lý.

Sự phát triển hơn nữa của các phương pháp tính toán chịu ảnh hưởng của công nghệ máy tính, đặc biệt là máy tính điện tử kỹ thuật số (EDC), giúp thực hiện các phép tính bao gồm hàng tỷ phép tính số học. Tình huống này đòi hỏi phải tăng cường chú ý đến việc tích lũy sai sót và lựa chọn các phương pháp kế toán ít “nhạy cảm” hơn với chúng.
