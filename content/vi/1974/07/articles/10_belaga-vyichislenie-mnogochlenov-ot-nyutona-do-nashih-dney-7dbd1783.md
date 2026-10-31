---
id: 1974-7-belaga-vyichislenie-mnogochlenov-ot-nyutona-do-nashih-dney-7dbd1783
issue: kvant_1974_7
year: 1974
number: "7"
title: Tính đa thức - từ Newton cho đến ngày nay
authors:
  - Белага Э. Г.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 31
page_last: 34
page_labels: 29, 31, 32
tag: G5OY
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 78d6edfa73958f81b307e860a74fbf5eeb3652c26b7bd6665b53c1a798dd3478
prompt_sha256: draft-1
translated_from: content/ru/1974/07/articles/10_belaga-vyichislenie-mnogochlenov-ot-nyutona-do-nashih-dney-7dbd1783.md
source_content_sha256: c08b56a7575cf14514993e3c69910db4f3f03777e17fbba1d9fc60c6b586dce6
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 29⟧

§ 1. Đa thức - công cụ của máy tính

Nào, hãy bắt đầu! Khi đi đến cuối câu chuyện này, chúng ta sẽ biết được nhiều điều hơn là ít hơn.

G. H. Andersen

Trong vương quốc vô hình của các hàm số, thoạt nhìn, đa thức chiếm một vị trí rất khiêm tốn. Tuy nhiên, ấn tượng đầu tiên này là lừa dối.

Đa thức thực sự cực kỳ đơn giản: ký hiệu đại số
$$f(x) = x^n + a_1x^{n-1} + a_2x^{n-2} + \dots + a_{n-1}x + a_n$$ (1)
cũng là công thức tính các giá trị của đa thức $^*$). Mặc dù các biểu thức như $\cos x$, $\sqrt[5]{x}$, $10^x$ hoặc $\log_2 x$ ngắn gọn hơn nhiều, nhưng từ quan điểm tính toán, chúng vô nghĩa: để tính toán, chẳng hạn, các số $\cos 17^\circ$, $\sqrt[5]{2}$, $10^{0.13}$ hoặc $\log_2 7$, bạn cần các công thức gần đúng đặc biệt (hoặc các bảng được biên soạn bằng cách sử dụng cùng một công thức). Theo quy luật, đa thức xuất hiện trong các công thức như vậy: ví dụ:
$$\cos x \approx 1 - \frac{x^2}{2!} + \frac{x^4}{4!} - \frac{x^6}{6!} + \frac{x^8}{8!}$$

(sai số trong khoảng $0 \leq x \leq \pi/4$ nhỏ hơn một phần mười triệu!).

*) Để đơn giản hóa phép tính, chúng ta sẽ giới hạn ở các đa thức có hệ số đơn vị cho số hạng dẫn đầu ($a_0 = 1$); khi cần thiết, chúng tôi sẽ chỉ ra cách tiến hành trong trường hợp chung ($a_0 \neq 1$).

Nhưng các hàm lượng giác, lũy thừa, v.v. (cơ bản) là những hàm đơn giản nhất trong số các hàm phân tích, được các nhà toán học, vật lý và kỹ sư nghiên cứu và sử dụng. Nhà toán học tính toán nổi tiếng viết trong cuốn sách của mình *): “Bởi vì đa thức rất dễ xử lý nên hầu hết các phân tích số cổ điển đều dựa trên sự gần đúng của đa thức”.

Vì bạn thường phải tính các đa thức nên điều quan trọng là phải học cách thực hiện nó một cách đơn giản nhất có thể. Chúng ta sẽ nói về sự phát triển của các phương pháp tính giá trị của đa thức kể từ khi chúng ra đời (thế kỷ 17). Tuy nhiên, từ “tiến hóa” ở đây không hoàn toàn phù hợp: lịch sử của những phương pháp này là một cuốn tiểu thuyết rất dài với cốt truyện thú vị nhưng ngắn gọn, hành động đơn điệu và một cái kết bất ngờ.

§ 2. Sơ đồ Horner

Thành thật mà nói, ở đây sẽ nảy sinh một nghi ngờ, hay đúng hơn là một câu hỏi không thể giảm thiểu nếu không nêu ra và trả lời.

A. Dante. Lễ (1303)

Phương pháp tính đa thức được chấp nhận rộng rãi hiện nay có từ thời Newton và được gọi là sơ đồ Horner. Sơ đồ phổ quát này (nghĩa là có thể áp dụng cho bất kỳ đa thức nào) cực kỳ đơn giản và thanh lịch. Nó thu được từ công thức (1)

*) R. W. Hemming. Các phương pháp số M., “Khoa học”, 1972.

⟦folio 31⟧

Những sơ đồ như vậy có thể được tìm kiếm dựa trên các đặc điểm của một đa thức riêng lẻ (bằng cách kết hợp khéo léo các hệ số của nó), hoặc bằng cách xây dựng một phương pháp phổ quát để xây dựng các sơ đồ tiết kiệm hơn nhiều so với sơ đồ của Horner, nhưng có lẽ không phải là phương pháp tốt nhất cho một số đa thức. Nhược điểm của cách tiếp cận đầu tiên là với mỗi đa thức, chúng ta sẽ phải phát minh ra các kỹ thuật của riêng mình và không có gì đảm bảo rằng chúng ta sẽ luôn thành công; Sau này (trong § 10), chúng ta sẽ thấy rằng điều thứ hai đáng tin cậy hơn về mọi mặt.

Không cần phải nói rằng cả hai phương pháp này chỉ giảm trong trường hợp một đa thức cụ thể xuất hiện kịp thời và nỗ lực để xây dựng một mạch tốt cho nó. Ví dụ, các đa thức “sử dụng một lần” dễ tính toán hơn bằng cách sử dụng sơ đồ Horner.

Có lẽ lý luận tương tự đã dẫn đến việc phát hiện ra một sơ đồ phổ quát thuộc loại hoàn hảo vào năm 1955 cho đa thức bậc sáu. Chúng tôi sẽ minh họa ý tưởng chính của sơ đồ này bằng cách sử dụng sơ đồ đơn giản hơn cho đa thức bậc 4. Hãy để
$$f(x) = x^4 + ax^3 + bx^2 + cx + d;$$
hãy đặt
$$\begin{cases} p_1 = x \cdot (x + A); \\ p_2 = (p_1 + B)(p_1 + x + C) + D \\ f(x) = p_2 \end{cases}$$
trong đó A, B, C và D là các tham số.

Ví dụ. Đa thức $x^4 + 3x^3 + 6x^2 + 3x + 2$ có thể được tính bằng sơ đồ: $p_1 = x(x + 1), f(x) = (p_1 - 1)(p_1 + x + 5) + 7$, chứa hai phép nhân (thay vì ba theo Horner) và năm phép tính (thay vì bốn) $(\pm)$; ở đây A = 1, B = -1, C = 5, D = 7.

Hãy để chúng tôi viết ra một biểu thức rõ ràng cho $p_2(x)$:
$$p_2(x) = x^4 + (2A + 1)x^3 + (A^2 + A + B + C)x^2 + (AB + B + AC)x + BC + D;$$
đánh đồng các hệ số $f(x)$ và $p_2(x)$, ta biểu diễn các tham số ở dạng (5) thông qua hệ số (4):
$$A = (a - 1)/2;$$
$$B = c - b \cdot A + A^2(A + 1);$$
$$C = b - B - A(A + 1);$$
$$D = d - BC.$$
Từ những công thức này, rõ ràng sơ đồ (5) là phổ quát.

Chúng ta sẽ gọi các phép toán (6) là phép biến đổi các hệ số của đa thức; Tất nhiên, chúng không được bao gồm trong số phép toán của mạch: xét cho cùng, đối với mỗi đa thức đã cho, chúng chỉ được thực hiện một lần và bài toán của chúng ta là học cách tính nhanh các giá trị của một đa thức tùy ý nhưng cố định cho $x$ khác nhau.

§ 5. Sơ đồ phổ quát bậc n

“Tôi nghĩ,” Piglet trầm ngâm nói, “rằng nếu mọi người ở dưới gốc cây, Pooh đứng trên lưng nó, còn tôi đứng trên vai Pooh...
“Và nếu lưng Na-Na bỗng trở nên buồn bã thì tất cả chúng ta sẽ có một trận cười sảng khoái,” Na nói.

A. A. Mill. Winnie the Pooh

Năm 1958, một sơ đồ phổ quát chung với việc xử lý biến đổi các hệ số đã được tìm ra. Cấu trúc của sơ đồ này cho đa thức bậc chẵn ($n = 2k$) giống như một kim tự tháp - ở sơ đồ nằm ở đáy (5) (chúng ta đã thấy “sức mạnh” của nó), nằm trong sơ đồ bậc 6, nằm trong sơ đồ bậc 8, v.v.:
$$\begin{cases} p_1 = x(x + b_1), \\ p_2 = (p_1 + b_2)(p_1 + x + b_3) + b_4, \\ p_3 = p_2(p_1 + b_5) + b_6, \\ \dots \\ p_k = p_{k-1}(p_1 + b_{2k-1}) + b_{2k}, \\ f(x) = p_k, \end{cases}$$

sơ đồ (7.2) chính xác là sơ đồ (5). Kết quả của sơ đồ (7.k) là đa thức $p_k(x)$ bậc $n = 2k$; một đa thức bậc lẻ $n = 2k + 1$ có ​​thể được biểu diễn dưới dạng sau:
$$f(x) = x(x^2k + a_1x^{2k-1} + \dots + a_{2k}) + a_{2k-1};$$
đa thức trong ngoặc được tính bằng sơ đồ (7.k). Kết quả là

⟦folio 32⟧

mạch chứa $k$ phép nhân và $2k+1$ phép cộng cho đa thức bậc chẵn $n=2k$ và $k+1$ phép nhân và phép cộng $2k+2$ cho đa thức bậc lẻ $n=2k+1$ (có tính đến (7.k) và (8.)).

Bài tập
4. Tìm các công thức xử lý sơ bộ hệ số tương tự như công thức (6) cho sơ đồ (7.3) tính đa thức bậc sáu.
5. Chứng minh bằng quy nạp trên $k \geq 2$ sơ đồ phổ quát (7.k).

Bắt đầu từ dòng thứ ba, sơ đồ (7.k) rất giống với sơ đồ Horner (3); sự khác biệt duy nhất là bây giờ sau mỗi phép nhân, độ không tăng lên một mà là hai.

Vì vậy, chúng tôi đã giảm được một nửa số phép nhân so với sơ đồ của Horner. Với chi phí nào? Từ lời giải Bài tập 5, rõ ràng là quá trình tính các tham số $b_1, b_2, \dots, b_{2k}$ từ các hệ số $a_1, a_2, \dots, a_n$ rất phức tạp - nó bao gồm chuỗi lời giải phương trình với một lũy thừa chưa biết $k-1, k-2, \dots$. Đặc biệt, điều này có nghĩa là đối với $k \geq 6$ ($n \geq 12$) không có công thức tính các tham số *), mặc dù tất nhiên, giá trị của chúng có thể được tìm thấy bằng các phương pháp gần đúng với bất kỳ mức độ chính xác nào.

Ở đây lại nảy sinh một khó khăn khác, mặc dù hóa ra nó có thể giải quyết được. Cho đến bây giờ, chúng tôi vẫn chưa chỉ rõ chúng tôi đang tính toán đa thức nào - thực hay phức. Sơ đồ Horner có thể áp dụng được trong cả hai trường hợp, trong khi sơ đồ (7.k)

*) Công thức thường được hiểu là tập hợp các phép tính số học, căn, lũy thừa. Bạn có thể biết rằng E. Galou và N. Abel, những nhà toán học lỗi lạc (và cả hai đều chết rất sớm) của thế kỷ 19, đã chứng minh rằng những công thức tổng quát như vậy không tồn tại để tìm nghiệm của đa thức bậc năm và lũy thừa cao hơn (xem «Kvant», 1973, số 10, trang 3-12).

chủ yếu là phức tạp - các tham số phức tạp có thể tương ứng với các hệ số thực. Sự xuất hiện của số phức trong phép tính đa thức thực làm tăng đáng kể số phép tính *). May mắn thay, vào năm 1960, sơ đồ (7.k), vốn phức tạp hơn, đã được biến thành sơ đồ thực sự; tuy nhiên, việc chứng minh đầy đủ trong trường hợp này vốn đã rất khó khăn.

§ 6. Về các đề án nói chung...

“Chờ một phút, một phút thôi,” tiếng tai ngô vang lên. — Hãy tránh các thuật ngữ khoa học, sử dụng các thuật ngữ phổ biến...
- Phải! - những người khác xác nhận. - Nói rõ hơn đi. Rừng là gì?
Vâng. Osenka. Đi bộ xuyên quốc gia vào năm 2050

Đã đến lúc hỏi xem có phương án nào tiết kiệm hơn phương án (7.k) không? Nhưng sau đó câu hỏi không thể tránh khỏi - sơ đồ là gì?

Đã xác định. (TÔI). Sơ đồ xử lý sơ bộ các hệ số là một chuỗi các phép tính số học có liên quan đến biến $x$, tham số $b_1, b_2, \dots, b_m$ và kết quả của các phép tính trước đó. Chúng ta gọi kết quả của thao tác cuối cùng là `результатом схемы`. (II). Nếu, đối với một số tập hợp giá trị tham số $b_1, \dots, b_m$, kết quả của lược đồ là một đa thức bậc nhất định $n$, thì chúng ta nói rằng lược đồ đó là `представляем этот многочлен`. (III). Nếu mạch được biểu diễn bằng đa thức thì quá trình tính tập hợp các giá trị tham số tương ứng từ các hệ số của nó được gọi là `предварительной обработкой коэффициентов`. (IV). Một sơ đồ được gọi là `bậc siêu cấp $n$ nếu nó được biểu diễn bằng bất kỳ đa thức bậc $n$ nào có dạng (1).

*) Một phép cộng “phức tạp” là hai phép cộng “thực”, một phép nhân “phức tạp” là bốn (!) phép nhân và hai phép cộng.
