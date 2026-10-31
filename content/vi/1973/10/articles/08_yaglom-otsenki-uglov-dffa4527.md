---
id: 1973-10-yaglom-otsenki-uglov-dffa4527
issue: kvant_1973_10
year: 1973
number: "10"
title: ước tính góc
authors:
  - Яглом И. М.
rubric: osnovnye-stati
page_first: 32
page_last: 36
page_labels: 30, 31, 32, 34
tag: PB76
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 5b3be3f9e4e04a92cc626061017841bfaa39e102b269729da7baef30f1d9d7bc
prompt_sha256: draft-1
translated_from: content/ru/1973/10/articles/08_yaglom-otsenki-uglov-dffa4527.md
source_content_sha256: a8b0d3a1ad58c0cdc98227e272e685ad6c9e72ec356455b91731866c3eb25b89
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 30⟧

I. M. Yaelom Ước tính các góc

Điểm khởi đầu đối với chúng ta sẽ là các điểm không trống nhưng đáng kính sau đây bài toán 1. Giả sử $A, B, C$ là ba điểm tùy ý (không trùng nhau) trên mặt phẳng; chúng tôi biểu thị các điểm của tam giác $ABC$ (moche, $\angle BAC, \angle ABC$ và $\angle ACB$) bằng $\alpha$, $\beta$ và $\gamma$. Hãy để $\alpha \geq \gamma \geq \beta$. $\alpha$, $\gamma$ và $\beta$ có ý nghĩa gì?

bài toán này minh họa rõ ràng chủ đề của bài viết này: nó thảo luận về những vấn đề sau (nói chung là chưa được giải quyết!)

Vấn đề chính. Trên mặt phẳng dữ liệu $n$ điểm $A_1, A_2, \dots, A_n$. Chúng ta hãy biểu thị bằng $\alpha_1, \alpha_2, \dots, \alpha_N$ các góc của các tam giác tạo bởi các điểm này *). Hãy để $\alpha_1 \geq \alpha_2 \geq \dots \geq \alpha_N$. $\alpha_1, \alpha_2, \dots, \alpha_N$ của tôi nên mang ý nghĩa gì?

Để biết được những gì chúng ta có thể gặp ở lời giải của bài toán chính, hãy giải bài toán 1.

Lời giải bài toán 1

Vì $\alpha + \beta + \gamma = 180^\circ = 3 \cdot 60^\circ$ nên lớn nhất ba góc của một tam giác không thể nhỏ hơn $60^\circ$, và

*) Số $N$ tất nhiên phụ thuộc vào $n$. Không khó để nhận ra điều đó

$$N = 3C_n^3 = 3 \frac{n(n-1)(n-2)}{1 \cdot 2 \cdot 3} = \frac{n(n-1)(n-2)}{2},$$

trong đó $C_n^3$ là số cách kết hợp của $n$ với 3, nhưng chúng ta không cần công thức này.

⟦folio 31⟧

Nếu chúng ta cần sắc nét thì $\gamma < 90^\circ$ (trường hợp ba điểm nằm trên cùng một đường thẳng sẽ không cứu vãn được tình thế, vì trong trường hợp này $\alpha = 180^\circ$, $\beta = 0^\circ$, $\gamma = 0^\circ$). Tuy nhiên, $\gamma$ có thể gần bằng $90^\circ$ (trong Hình 3, góc nhỏ nhất $\beta = \angle BAC$ là rất nhỏ và $\angle ABC = \angle ACB \approx 90^\circ$). Như vậy,

$$60^\circ \leq \alpha \leq 180^\circ, \quad 0^\circ \leq \gamma < 90^\circ, \quad 0^\circ \leq \beta \leq 60^\circ.$$

Để xác minh lời giải bài toán 1*, chúng ta vẫn cần chứng minh rằng $\alpha$ có ​​thể nhận nhiều giá trị hơn trong phạm vi $60^\circ \leq \alpha \leq 180^\circ$ (và tương tự đối với các góc $\beta$ và $\gamma$). Tuy nhiên, phần lời giải này rất đơn giản - nó trùng với việc xây dựng một tam giác $ABC$, trong đó góc lớn nhất $\alpha$ (hoặc góc “trung bình” $\gamma$ hoặc góc nhỏ nhất $\beta$) có một giá trị nhất định, được chọn trong giới hạn quy định; Bạn có thể dễ dàng tự làm điều này.

Thảo luận lời giải bài toán 1

Trước hết, hãy thay đổi ký hiệu. Các điều kiện là biểu thị các đỉnh của một tam giác bằng $A_1, A_2, A_3$ và các góc của nó bằng $\alpha_1, \alpha_2, \alpha_3$. Góc lớn nhất $\alpha_1, \alpha_2, \alpha_3$ có ​​thể được ký hiệu như sau:

$$\alpha = \max_i \alpha_i,$$

và góc nhỏ nhất $\alpha_1, \alpha_2, \alpha_3$ là như thế này:

$$\beta = \min_i \alpha_i,$$

và $i = 1, 2, 3.$

max là tên viết tắt của từ Latin *maximum* - “maximum”, tức là lớn nhất. Dấu $i$ under.max cho thấy rằng $i$ đang thay đổi, tức là một tập hợp các giá trị $\alpha_i$ được đưa ra (ở đây - $\alpha_1, \alpha_2, \alpha_3$), trong đó chúng ta lấy giá trị lớn nhất (chứ không phải là góc lớn nhất trong số các góc nói chung có thể có của tam giác $A_1A_2A_3$ - trong

*) Chúng tôi cung cấp ở đây chi tiết lời giải bài toán 1. Gợi ý đến lời giải phần còn lại bài toán được đặt ở cuối tạp chí (nhưng đừng nhìn vào đó - hãy cố gắng tự giải bài toán trước). Đánh dấu sao những câu khó hơn bài toán; một dấu hiệu đơn giản ở số bài toán sẽ chỉ ra rằng tác giả không biết đến lời giải (từ đó không hề chứng tỏ rằng bài toán này khó; hãy nghĩ về điều này bài toán).

trong trường hợp này chúng ta sẽ viết tối đa $\alpha$. Zakmak max $\Delta A_1A_2A_3$ thường được sử dụng cho số lớn nhất trong số hữu hạn (ở đây - trong số ba). Đối với số lượng lớn nhất trong số vô hạn, bạn cũng có thể sử dụng dấu max, nhưng điều này rất nguy hiểm - ở đây cũng cần phải chứng minh rằng số lượng lớn nhất này tồn tại (xem bên dưới).

min là tên viết tắt của từ Latin *minimum* - “minimum”, nghĩa là lớn nhất.

Trong bài toán 1 không khó khăn gì trong việc xác định giá trị lớn nhất có thể có $\alpha$, tức là

$$\max \alpha = \max \max \alpha_i = 180^\circ,$$

$$\Delta A_1A_2A_3 \quad \Delta A_1A_2A_3 \quad i$$

và giá trị nhỏ nhất có thể $\beta$, tức là

$$\min \beta = \min \min \alpha_i = 0^\circ.$$

Điều đáng quan tâm nhất ở đây là giá trị nhỏ nhất có thể có của $\alpha$, tức là

$$\min \alpha = \min \max \alpha_i = 60^\circ,$$

$$\Delta A_1A_2A_3 \quad \Delta A_1A_2A_3 \quad i$$

Công thức của “minimax” bài toán như vậy là đặc trưng của toán học ứng dụng “thuần túy” và (đặc biệt!) hiện đại.

Một phần đáng kể của bài toán 1 cũng là ước tính giá trị lớn nhất có thể có của $\gamma$ (rất dễ tìm thấy giá trị nhỏ nhất: từ Hình 2, giá trị tối thiểu đó là $\gamma = 0^\circ$). Tuy nhiên, ở đây chúng tôi rất tiếc: hóa ra giá trị tối đa mong muốn $\gamma$ không tồn tại: góc $\gamma$ có thể gần bằng $90^\circ$, nhưng nó không bao giờ bằng $90^\circ$. Khi đó, các nhà toán học nói rằng $90^\circ$ là (mon) tối đa của $\gamma$:

$$\sup \gamma = 90^\circ.$$

sup là tên viết tắt của từ Latin *supremum* - “supremum”, nghĩa là cao hơn. Ký hiệu sup $x_i = \xi$ có nghĩa là $x_i \leq \xi$ đối với bất kỳ $i$ nào, nhưng $x_i$ có thể là bất kỳ góc nào

⟦folio 32⟧

gần với ξ, tức là ξ là số nhỏ nhất, không nhỏ hơn bất kỳ $x_i$ nào. Có thể chứng minh rằng nếu các đại lượng $x_i$ bị chặn từ phía trên, tức là có ít nhất một giới hạn trên của đại lượng, thì trong số các giới hạn trên này có một (một) nhỏ nhất, tức là tồn tại sup $x_i$.

Ký hiệu inf $x_i$ được sử dụng tương tự. Inf là tên viết tắt của từ infimum trong tiếng Latin - "infimum", nghĩa là thấp hơn.

inf $x_i$ là cạnh thấp mạnh mẽ, tức là số lớn nhất không vượt quá bất kỳ $x_i$ nào. Trong trường hợp điều này không gây khó khăn cho việc đọc, chúng tôi sẽ không viết $i$, $\Delta A_1 A_2 A_3$, v.v. dưới các dấu sup, inf, max, min.

Không khó để hiểu loại sorbiriz này có liên quan gì. Rõ ràng là các giá trị tối đa $\alpha_i$ và tối thiểu $\alpha_i$ tồn tại - xét cho cùng, từ ba góc $\alpha_1$, $\alpha_2$ và $\alpha_3$ người ta luôn có thể chọn giá trị lớn nhất và nhỏ nhất. Và số lượng đường đi $\{A_1, A_2, A_3\}$ điểm trên mặt phẳng là vô hạn. Và ở đây chúng ta không còn có thể đảm bảo rằng sẽ có một rãnh tương ứng với giá trị lớn nhất của góc $\gamma$. Rốt cuộc, chúng ta có thể di chuyển từ rãnh điểm này sang rãnh điểm khác, tương ứng với giá trị lớn hơn của góc $\gamma$, bao nhiêu lần nếu cần thiết và mỗi lần như vậy có thể vẫn còn một rãnh còn lại tốt hơn rãnh trước đó.

Về nguyên tắc, không có giá trị sup $\alpha$, sup $\beta$, sup $\gamma$, inf $\alpha$, inf $\beta$, inf $\gamma$ là đủ cần thiết - và chúng ta nên coi thật may mắn khi các giá trị sup $\alpha = 180^\circ$, sup $\beta = 60^\circ$, inf $\alpha = 60^\circ$ và inf $\beta = 0^\circ$ đã đạt được, tức là tồn tại tối đa $\alpha$, tối đa $\beta$, tối thiểu $\alpha$ và tối thiểu $\beta$. Đối với giá trị $\gamma$, như chúng ta đã thấy, inf $\gamma = 0^\circ$ đạt được, nhưng sup $\gamma = 90^\circ$ thì không.

Tương tự, đối với đại lượng $\frac{1}{n}$, trong đó $n$ là số tự nhiên, đạt được sup $\frac{1}{n} = 1$ (tại $n = 1$), nhưng inf $\frac{1}{n} = 0$ thì không; Do đó, số lượng $\frac{1}{n}$ có mức tối đa và không có mức tối thiểu.

Cuối cùng chúng ta hãy xem xét câu hỏi về các dấu vết cụ thể nào của điểm $P_3 = \{A_1, A_2, A_3\}$ (hoặc $\{A, B, C\}$) đạt được các giá trị tối đa hoặc tối thiểu ​​của $\alpha$, $\beta$ và $\gamma$. Có thể dễ dàng nhận thấy rằng tối thiểu $\alpha$ và (đồng thời) tối đa $\beta$ đạt được cho một bộ ba điểm - tất nhiên đối với các đỉnh của một tam giác đều $ABC$ (xem Hình 1), cho đến việc thay thế tam giác $ABC$ bằng một tam giác tương tự, tuy nhiên, không làm thay đổi bất kỳ góc nào của nó. max $\gamma$, như chúng ta đã biết, hoàn toàn không tồn tại. Và các giá trị tối đa $\alpha$, tối thiểu $\beta$ và tối thiểu $\gamma$ được hiện thực hóa bằng vô số bộ ba điểm khác nhau (khác biệt hơn nữa) - xét cho cùng, điểm giữa trong Hình 2 có thể nằm ở bất kỳ đâu trên đoạn nối hai điểm khác.

Bây giờ chúng ta sẽ chuyển sang các nhiệm vụ khác.

Bài 2. a) Cho $P_4 = \{A, B, C, D\}$ là hệ bốn điểm tùy ý trên mặt phẳng; chúng tôi biểu thị các giá trị nhỏ nhất trong 12 góc được xác định bởi empirim và mochikas bằng $\beta$. Chứng minh rằng $0^\circ \leq \beta \leq 45^\circ$.

b) Cho $P_5$ là hệ bốn điểm tùy ý trên mặt phẳng; Chúng tôi biểu thị góc nhỏ nhất được xác định bởi góc theo kinh nghiệm và mochika bằng $\beta$. Chứng minh rằng $0^\circ \leq \beta \leq 36^\circ$.

c) Cho $P_6$ là hệ bốn điểm tùy ý trên mặt phẳng; Chúng tôi biểu thị góc nhỏ nhất được xác định bởi góc theo kinh nghiệm và mochika bằng $\beta$. Chứng minh rằng $0^\circ \leq \beta \leq 30^\circ$.

Đối với hệ bốn, gót và sáu điểm trên mặt phẳng nào đạt được giá trị lớn nhất và nhỏ nhất của góc $\beta$?

Bắt đầu lời giải bài toán 2. Giả sử các điểm đang xét được cắm sâu xuống đất

⟦folio 34⟧

Kết quả này cũng giống như đối với hệ 7 điểm (có thể ở đây cũng có inf α = 120°, u min α không tồn tại).

Chúng ta hãy quay lại hệ “tổng quát” $P_n = \{A_1, A_2, \dots, A_n\}$ của $n$ điểm trên mặt phẳng xuất hiện trong bài toán chính; Chúng tôi biểu thị nhiều góc nhất được xác định bởi các điểm này bằng $\alpha$ và nhiều nhất bằng $\beta$. Vì rõ ràng giá trị lớn nhất có thể có của $\alpha$ bằng 180° và giá trị lớn nhất có thể có của $\beta$ bằng 0°, nên việc đánh giá bài toán của các góc $\alpha$ và $\beta$ bao gồm việc tìm sûр $\beta$ (chúng tôi biểu thị giá trị này bằng $\beta$ hoặc mặt phẳng, nó, của tất nhiên, phụ thuộc vào $n$, - đến $\beta(n)$) và inf $\alpha$ (chúng tôi biểu thị giá trị này thông qua $\alpha$ hoặc $\alpha(n)$). Tìm một số giá trị của $\beta(n)$:

$$\beta(n) = \frac{180^\circ}{n},$$

và giá trị này luôn có thể đạt được (xem bài toán 3). Tuy nhiên, việc tìm bài toán giá trị $\alpha(n)$ không đơn giản và vẫn chưa được giải ở dạng tổng quát. Bài toán 4 và 5 cho rằng $\alpha(4) = 90^\circ$, $\alpha(5) = 108^\circ$ và $\alpha(6) = \alpha(7) = \alpha(8) = 120^\circ$; trong trường hợp này, các giá trị $\alpha(4), \alpha(5)$ và $\alpha(6)$ đã đạt được, nhưng các giá trị $\alpha(7)$ và $\alpha(8)$ chưa đạt được.

Bài toán xác định giá trị $\alpha(n)$ được đưa ra lần đầu tiên bởi nhà hình học người Mỹ L. Blumenthal; lời giải của nó được thực hiện bởi các nhà toán học Hungary P. Erdős*) và G. Szekeres. P. Erdős gợi ý điều đó cho mọi người $n \geq 6$ $\alpha(n) = \frac{k-1}{k} \cdot 180^\circ$, Ở đâu $2^{k-1} \leq n \leq 2^k$và giá trị này đạt được $\alpha(n)$ chỉ khi $n = 6$. Tuy nhiên, cho đến nay nó chỉ được chứng minh rằng

$$\alpha(2^k) = \frac{k-1}{k} \cdot 180^\circ$$ tại $k \geq 2$

*) Pál Erdős là một nhà toán học hiện đại nổi tiếng người Hungary. Erdős sở hữu nhiều kết quả nổi bật trong nhiều lĩnh vực toán học (lý thuyết số, giải tích toán học, lý thuyết xác suất, hình học, v.v.); Thứ nhất, do hoạt động của anh ấy, số lượng bài toán vẫn chưa được giải quyết chỉ tăng lên, nhưng anh ấy đặt nhiều bài toán mới hơn số lần giải được những cái cũ.

và điều gì sẽ xảy ra nếu $2^{k-1} < n < 2^k$ (trong đó $k \geq 3$), sau đó $\frac{k-1}{k} \cdot 180^\circ \geq \alpha(n) > \frac{k-2}{k-1} \cdot 180^\circ$ (ước tính sau thậm chí có thể được tăng cường một chút).

Bây giờ chúng ta hãy chuyển sang phần còn lại của các góc liên quan đến vấn đề.

Bài toán 6. Giả sử $P_4$ là hệ bốn điểm tùy ý trên mặt phẳng; $\alpha = \alpha^{(1)}$ và $\alpha^{(2)}$ là hai góc lớn nhất trong chín góc được chỉ định bởi các điểm này, $a = \beta = \beta^{(1)}$ và $\beta^{(2)}$ là hai góc nhỏ nhất; đồng thời $\alpha^{(1)} \geq \alpha^{(2)}$, $\beta^{(1)} \leq \beta^{(2)}$. Chứng minh rằng

a) $72^\circ \leq \alpha^{(2)} \leq 180^\circ$;
b) $0^\circ \leq \beta^{(2)} \leq 45^\circ$.

Đối với hệ thống điểm nào, giá trị lớn nhất và nhỏ nhất của $\alpha^{(2)}$ và $\beta^{(2)}$ được nhận ra?

Bài toán 7. Chứng minh rằng với mọi $n \geq 2$ lớn nhất $\alpha(i) = 180^\circ$ cho $1 \leq i \leq \frac{n(n-1)(n-2)}{6}$,

$$u \min \alpha^{(i)} = 0^\circ$$ tại $P_n$

$$\frac{n(n-1)(n-2)}{6} < j \leq N = \frac{n(n-1)(n-2)}{2}$$

Do đó, câu hỏi về ước tính của tất cả các góc $N$ $\alpha^{(i)}$ chỉ ra việc xác định giá trị inf $\alpha^{(i)}$, trong đó

$$1 \leq i \leq \frac{n(n-1)(n-2)}{6}$$

(inf $\alpha^{(i)}$ có thể được biểu thị bằng ký hiệu $\alpha^{(i)}(n)$) và sup $\beta^{(i)}$ khi

$$1 \leq j \leq \frac{n(n-1)(n-2)}{3}$$

*) Lưu ý rằng $\frac{n(n-1)(n-2)}{6} + \frac{n(n-1)(n-2)}{3} = \frac{n(n-1)(n-2)}{2} = N$. Chúng ta cũng hãy chỉ ra rằng số lượng đại lượng $\beta^{(i)}$ cần xác định luôn gấp đôi số lượng các số phụ $\alpha^{(i)}$, ví dụ: 2 và 1 cho $n = 3$, 8 và 4 cho $n = 4$, v.v.
