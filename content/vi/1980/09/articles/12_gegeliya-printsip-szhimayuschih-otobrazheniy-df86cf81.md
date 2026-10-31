---
id: 1980-9-gegeliya-printsip-szhimayuschih-otobrazheniy-df86cf81
issue: kvant_1980_9
year: 1980
number: "9"
title: Nguyên tắc lập bản đồ co
authors:
  - Гегелия Г.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 30
page_last: 34
page_labels: 28-32
tag: W3RC
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 198e662193c5fcf5138c602f92f9989406ec3a8a4ff1932dd81fa21046c221cf
prompt_sha256: draft-1
translated_from: content/ru/1980/09/articles/12_gegeliya-printsip-szhimayuschih-otobrazheniy-df86cf81.md
source_content_sha256: 350ee970db584c7690ad54c9e32b3b587e69524045dd64d5633f87a9ff5701d2
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 28⟧

Điểm tham quan của màn hình lướt qua

(Từ biên niên sử NOU)

Bài viết này dựa trên một báo cáo của tác giả, khi đó là một học sinh lớp 10, tại “Ngày hội Toán học” ở Batumi. Nó nói về một định lý quan trọng mà phần chúng tôi sử dụng cho lời giải các hệ thống lớn trên máy tính, nhưng cũng có thể được sử dụng để tìm nghiệm gần đúng của các phương trình “trường học điển hình”.

Điểm cố định

Đặt $f$ là ánh xạ của tập hợp $A$ tùy ý vào chính nó. Điểm $x \in A$ được gọi là điểm cố định $f$ của ánh xạ $f$ nếu

$$f(x) = x. \tag{1}$$

Khi $A \subset R$ (tức là khi $f$ là hàm số tổng quát), việc tìm điểm cố định của bản đồ $f$ chỉ đơn giản là giải phương trình (1). Ngược lại, nếu một phương trình đã cho là $g(x) = 0$ thì lời giải của nó sẽ là một điểm cố định của ánh xạ $f$, trong đó

$$f(x) = g(x) + x. \tag{2}$$

Hãy xem xét một vài ví dụ.

1) Mặt phẳng quay một góc khác 0 gần một điểm cho trước có một điểm cố định duy nhất (tâm quay).

2) Sự tịnh tiến song song của một mặt phẳng sang một vectơ khác 0 không có điểm cố định.

*) Điểm cố định cũng được thảo luận trong bài viết của B. Wertheim («Kvant», 1980, số 6).

3) Sự đối xứng của mặt phẳng so với đường thẳng có vô số điểm cố định (tất cả các điểm của đường thẳng này).

4) Ánh xạ $x \rightarrow ax^2 + bx + c$, trong đó $a \neq 0$, có hai, một hoặc không có điểm cố định tùy thuộc vào dấu của biểu thức

$$\Delta = (b - 1)^2 - 4ac.$$

Nhiệm vụ 1. Xây dựng bản đồ mặt phẳng có chính xác $n$ điểm cố định ($n \in \mathbb{N}$).

Màn hình nén

Như chúng tôi đã lưu ý ở trên, lời giải của bất kỳ phương trình nào có dạng $g(x) = 0$ bằng một kỹ thuật đơn giản (bằng cách thêm $x$ vào vế trái của phương trình) sẽ trùng khớp với việc tìm một điểm cố định của một số ánh xạ. Điều rất quan trọng đối với Pozny là phải biết các điều kiện tồn tại của một điểm cố định và cũng có thể tìm thấy chính điểm cố định đó. Bây giờ chúng tôi đang xác định điều kiện này.

Đặt ánh xạ này là $f: A \rightarrow A$, trong đó khoảng cách giữa các điểm được xác định trong tập hợp $A$: $d(x, y)$; (ví dụ: $A$ là tập hợp con của đường thẳng, mặt phẳng hoặc khoảng trắng). Ánh xạ $f$ được gọi là lướt nếu có một số $a < 1$ sao cho bất kỳ điểm nào $x, y$ $A$

$$ad(x, y) \geq d(f(x), f(y)). \tag{3}$$

Nói cách khác, khoảng cách giữa ảnh của một điểm nhỏ hơn khoảng cách giữa chính các điểm đó và nó giảm ít nhất $a$ “lần”, trong đó $a < 1$. Số $a$ được gọi là hệ số hớt váng. Ví dụ:

1) Tính đồng nhất của mặt phẳng có hệ số $0 < k < 1$ sẽ là bản đồ lướt (có hệ số $k$).

2) Xoay một mặt phẳng không phải là một màn trình diễn lướt qua. Định lý sau đây cho thấy tại sao cần có khái niệm bản đồ lướt.

Định lý (nguyên tắc ánh xạ lướt trên một dòng). Tất cả-

⟦folio 29⟧

Cơm. 1.

một số ánh xạ co $f$:
$|a; b| \rightarrow |a; b|$ của tích phân vào chính nó có một điểm cố định.

Tính chất đơn vách của một điểm cố định là hiển nhiên: nếu có hai trong số chúng thì khoảng cách giữa chúng sẽ thay đổi (theo điều kiện (3)), trong khi nó thực sự không thay đổi (vì bản thân các điểm không chuyển động).

Bằng chứng về sự tồn tại dựa trên một phương pháp tích phân đơn giản nhưng quan trọng: lấy bất kỳ điểm $x_0 \in |a; b|$ nào và áp dụng $f$ cho nó nhiều lần:

$$x_0, x_1 = f(x_0), x_2 = f(x_1), \dots, x_n = f(x_{n-1}), \dots$$

thì dãy $x_1, x_2, \dots, x_n$ ... hội tụ về điểm cố định.

Trước khi chứng minh phương pháp này (nghĩa là hoàn thành việc chứng minh định lý), chúng tôi minh họa nó bằng một ví dụ đơn giản:

Đặt $f: ] - 1; 1[ \rightarrow ] - 1; 1[$ là ánh xạ được cho bởi công thức $f(x) = \dot{x}^2$ (Hình 1). Hãy lấy điểm $x_0 = 0,1$. Sau đó

$$x_1 = (0,1)^2 = 0,01,$$
$$x_2 = (0,01)^2 = 0,0001,$$

Rõ ràng là $\lim_{k \to \infty} x_k = 0$. Điểm 0 thực sự đứng yên, hoặc $0^2 = 0$.

(Nhân tiện, chúng ta đã giải phương trình $x^2 - x = 0, x \ni 1$; 1[] theo cách này).

Quay lại chứng minh định lý, chúng ta ký hiệu dãy (4) bằng $(x_n)$. Hãy chứng minh rằng dãy này có các tính chất sau.

(K) Với mọi $\varepsilon > 0$ đều tồn tại một số $n_0$ sao cho với mọi số lớn $n, m > n_0$ bất đẳng thức

$$d(x_n, m) < \varepsilon.$$

Nói cách khác, các điểm của dãy có số đủ lớn sẽ đóng tùy ý.

Để chứng minh điều này, chúng ta áp dụng bất đẳng thức (3) $k$ lần; chúng tôi nhận được

$$d(x_k, x_{k+1}) \leq \alpha^{k-1} d(x_1, x_2).$$

Bởi vì

$$d(x_n, x_{n+p}) \leq d(x_n, x_{n+1}) + d(x_{n+1}, x_{n+2}) + \dots + d(x_{n+p-1}, x_{n+p}) \leq \alpha^{n-1} + \alpha^n + \dots + \alpha^{n+p-2} d(x_1, x_n) = \frac{\alpha^{n-1}(1-\alpha)^p}{1-\alpha} d(x_1, x_n) \leq \frac{\alpha^{n-1}}{1-\alpha} d(x_1, x_2).$$

Bây giờ với bất kỳ $\varepsilon > 0$ nào chúng ta có thể coi là $n_0$

$$n_0 = \log_a \frac{\varepsilon(1-\alpha)}{d(x_1, x_2)}.$$

Khi đó, với mọi $n, m > n_0$, bất đẳng thức (6) ngay lập tức hàm ý điều kiện bắt buộc

⟦folio 30⟧

Cơm. 2.

chúng ta cần bất đẳng thức (5) (kiểm tra!). Tính chất (K) đã được chứng minh.

Sử dụng tính chất (K), bây giờ chúng ta chứng minh sự hội tụ của dãy $(x_n)$. Đối với số $\varepsilon = 1/2$, theo thuộc tính (K), có một số $n_1$ sao cho $m > n_1$ $d(x_m, x_{n_1}) < 1/2$ thỏa mãn, tức là $x_m \in ]a_1; b_1[$, trong đó $a_1 = x_{n_1} - 1/2$, $b_1 = x_{n_1} + 1/2$. Khoảng cách xa hơn là số $\varepsilon = 1/4$ và tương tự, chúng ta tìm số $n_2$ sao cho $m > n_2$ $x_m \in ]a_2; b_2[$ thỏa mãn, trong đó $a_2 = x_{n_2} - 1/2$, $b_2 = x_{n_2} + 1/2$. Nếu một trong các điểm $a_2, b_2$ không nằm trong $]a_1; b_1[$ thì chúng ta sẽ thay thế nó bằng $a_1$ (tương ứng với $b_1$), giữ nguyên ký hiệu $]a_2; b_2[$ cho đoạn đã dựng. Và vân vân (xem Hình 2).

Chúng ta thu được dãy tích phân

$$]a_1; b_1[ \supset ]a_2; b_2[ \supset ... \supset ]a_n; b_n[ \supset ...$$

độ dài của tích phân thứ $n$ không vượt quá $1/2^{n-1}$ và ứng với mỗi số đó có một số sao cho tất cả $x_i$ có ​​số lớn đều nằm trong tích phân này.

Hãy xem xét dãy $(a_n)$ của các đầu bên trái của tích phân của chúng ta. Nó đang tăng dần và bị giới hạn từ phía trên (ví dụ: bằng số $b_1$) và do đó (xem “Đại số và sự khởi đầu của phân tích 9”, đoạn 32), có giới hạn $x = \lim_{n \to \infty} a_n$. Hãy chứng minh rằng số $x$ chính là giới hạn của dãy $(x_n)$. Thật sự,

$$d(x, x_n) \leq d(x, a_n) + d(a_n, x_n);$$

cả hai số hạng ở phía bên phải đều có góc nhỏ (đối với $n$ đủ lớn), sau đó $d(x, x_n)$ trở thành góc nhỏ (đối với $n$ đủ lớn), tức là $x = \lim_{n \to \infty} x_n$.

Tất cả những gì chúng ta phải làm là chứng minh rằng $x$ là một điểm cố định của ánh xạ $f$. chúng tôi có

$$0 \leq d(x, f(x)) \leq d(x, x_n) + d(x_n, f(x)) = d(x, x_n) + d(f(x_{n-1}), f(x)) \leq d(x, x_n) + a d(x_{n-1}, x).$$

Hai số hạng cuối cùng có góc nhỏ (đối với $n$ đủ lớn), có nghĩa là $d(x, f(x)) = 0$, tức là $f(x) = x$, đây là điều cần được chứng minh.

Dễ dàng nhận thấy định lý sẽ vẫn đúng nếu chúng ta thay tích phân $]a; b[$ bằng một đoạn, một tia hoặc thậm chí toàn bộ đường thẳng $R$. Hơn nữa, nó vẫn đúng trên máy bay.

Bài 2. Hình thành và chứng minh nguyên lý vẽ lướt đường tròn trên mặt phẳng.

Gợi ý. Sử dụng tọa độ.

Tất nhiên, nếu bạn đã thực hiện bài tập này, bạn sẽ thấy rõ rằng mục tiêu của chúng tôi sẽ vẫn đúng đối với việc nhận bóng hoặc thoát bóng và thậm chí cả trong không gian - chẳng hạn như đối với một quả bóng. Điều tự nhiên là đặt câu hỏi: làm thế nào để xây dựng nguyên tắc này để bao quát được càng nhiều trường hợp càng tốt? Làm thế nào để tìm được công thức tổng quát nhất?

Sau khi đặt ra câu hỏi này, chúng tôi thấy mình đang ở trong một tình huống đặc trưng trong công việc sáng tạo của một nhà toán học nghiên cứu. Và bây giờ chúng ta sẽ thấy

Một nhà toán học lý luận như thế nào?

Một nhà toán học chuyên nghiệp ở đây sẽ nghĩ như thế này:

Chúng ta cần tìm một công thức tổng quát hóa định lý đã chứng minh ở trên. Để làm điều này, chúng ta hãy xem chính xác những tính chất nào của tình huống này thực sự cần thiết trong chứng minh.

Đầu tiên, chúng tôi sử dụng định nghĩa về bản đồ lướt (3). Điều này có nghĩa là tập hợp $A$ phải chứa khoảng cách $d(x, y)$ giữa các điểm $x, y$ trên một đường thẳng - đây là số

$$d(x, y) = |x - y|.$$

Nhưng điều quan trọng là nó được hỏi theo cách này? Có lẽ là không: xét cho cùng, trên mặt phẳng $d(x, y)$ được định nghĩa khác, nhưng bằng chứng vẫn có hiệu lực. Vì vậy, bạn cần xem thuộc tính khoảng cách nào thực sự được sử dụng. Hãy xem.

⟦folio 31⟧

Ở phần cuối của chứng minh, chúng tôi sử dụng thực tế là hai điểm nằm ở khoảng cách bằng 0 trùng nhau. Hãy viết nó như thế này:

$$d(x, y) = 0 \iff x = y.$$  (I)

Tiếp theo chúng tôi cần (ở đâu?)

$$d(x, y) = d(y, x)$$  (II)

(đối với bất kỳ $x, y \in A$).

Cuối cùng, chúng ta đã nhiều lần (ví dụ khi chứng minh bất đẳng thức (6)) đã sử dụng bất đẳng thức tam giác:

$$d(x, z) \leq d(x, y) + d(y, z)$$  (III)

(đối với bất kỳ $x, y, z \in A$).

Bây giờ hãy nghĩ xem - chúng ta có cần bất kỳ tính chất nào khác của khoảng cách không? Hãy xem lại bằng chứng; không, không cần gì hơn từ xa. Vì vậy, chúng ta chỉ cần các aximon khoảng cách tổng quát.

Hãy tiếp tục. Chúng ta hãy xem sự hội tụ của dãy (4) với tính chất (K) đã được chứng minh như thế nào. Khá thông minh, sử dụng các thuộc tính cụ thể của các khoảng trên một dòng. Thật khó để hiểu những thuộc tính chung nào được sử dụng ở đây. Chỉ có một lối thoát duy nhất là “gỡ khó khăn vào tiên đề”, tức là giả sử đáp số mọi dãy có tính chất (K) đều hội tụ. Xét cho cùng, điều này rất dễ thực hiện—bạn chỉ cần định hướng cho mình những tập hợp $A$ mà sự hội tụ tuân theo các điều kiện (K) là đủ!

Hãy tóm tắt. Bằng chứng được coi là bản đồ lướt nếu có khoảng cách trong $A$ thỏa mãn các điều kiện (I)–(III) và bất kỳ chuỗi điểm nào trong $A$ có thuộc tính (K) đều hội tụ đến một điểm trong $A$.

Công thức trong trường hợp tổng quát

Để xây dựng định lý chúng ta cần, hãy bắt đầu với các định nghĩa hình thức. Người đọc nào hiểu được lập luận của nhà toán học chuyên nghiệp hư cấu của chúng ta sẽ hiểu ngay tại sao những định nghĩa này lại như vậy.

Tập $A$, trong đó mỗi cặp điểm $x, y \in A$ được liên kết với số $d(x, y) \in \mathbb{R}$, được gọi là không gian mêtric nếu các điều kiện (I) - (III) được thỏa mãn cho $d$; trong trường hợp này, số $d(x, y)$ được gọi là khoảng cách giữa các điểm $x$ và $y$.

Dãy các điểm $x_1, x_2, \dots, x_k$, ... của không gian mêtric $A$ được gọi là hàm số (hoặc dãy Cauchy) nếu với bất kỳ $\varepsilon > 0$ nào tồn tại một số $n_0$ sao cho

$$n, m > n_0 \Rightarrow d(x_n, x_m) < \varepsilon.$$

Một dãy ($x_n$) trong không gian mêtric $A$ được gọi là hội tụ nếu tồn tại một điểm $x$ sao cho với bất kỳ $\varepsilon > 0$ nào cũng có một số $n_0$ thỏa mãn

$$n > n_0 \Rightarrow d(x_n, x) < \varepsilon.$$

Điểm $x$ trong trường hợp này được gọi là giới hạn của dãy $x_n$. Ký hiệu: $\lim_{n \to \infty} x_n = x$.

Cuối cùng, một không gian mêtric được gọi là đầy đủ nếu bất kỳ dãy hàm nào trong nó hội tụ.

Định lý (nguyên tắc chung của việc thêm ánh xạ). Bất kỳ bản đồ lướt nào của một không gian số liệu hoàn chỉnh vào chính nó đều có một điểm cố định duy nhất.

Chứng minh về cơ bản không khác với chứng minh của định lý thứ nhất, chỉ khác phần cuối của quá trình: từ việc dãy (4) là hàm số (nghĩa là nó có tính chất (K)), và từ khoang trống của không gian $A$, theo định nghĩa thì (4) hội tụ.

Bài 3. Viết chứng minh một cách chi tiết.

Trên thực tế, nguyên tắc skimming maps thường gắn liền với tên tuổi của Picard và Banach không được xây dựng ở dạng tổng quát nhất ở trên. Một phân tích tinh tế hơn về bằng chứng do nhà toán học S. Banach đưa ra về khái niệm không gian tuyến tính định chuẩn đầy đủ (hoặc, như ngày nay người ta nói, là không gian Banach), mà ông đã chứng minh định lý. Ưu điểm của công thức này là các “điểm” của không gian như vậy có thể là hàm số, do đó nguyên lý này có thể áp dụng được cho lời giải, chẳng hạn như các phương trình vi phân.

⟦folio 32⟧

Máy tính hoạt động như thế nào?
Chúng ta đã lưu ý rằng phương pháp tích phân cho chúng ta một cách để tìm gần đúng một điểm cố định:
vì chuỗi $x_0, x_1 = f(x_0), x_2 = f(x_1)$, ... hội tụ đến $x$, nên có thể đạt được điểm $x$ với độ chính xác cho trước $\varepsilon$ bằng cách chọn số $n$ sao cho $|x_n - x| < \varepsilon$.

Điều này có thể được thực hiện hoàn toàn tốt bởi một máy tính hoạt động theo thuật toán hiển thị trong hình (cái gọi là “sơ đồ khối” của thuật toán). Hãy xem xét nó một cách cẩn thận và thử cách thuật toán này hoạt động.

Rõ ràng là theo các điều kiện của định lý trên bản đồ lướt, máy, sau một số lần lặp hữu hạn, sẽ in ra số $x_n$ thỏa mãn điều kiện $|x_n - x| < \varepsilon$, tức là giá trị gần đúng (với độ chính xác cho trước $\varepsilon$) $x$. Nếu không đáp ứng được những điều kiện này, máy có thể “hoạt động mãi mãi” (nếu nó không hỏng mà không cho chúng ta đáp số).

Để không lãng phí thời gian tốn kém của máy tính, trước khi chạy thuật toán, nên kiểm tra việc đáp ứng các điều kiện của định lý trên bản đồ lướt.

Nhiệm vụ 4. Áp dụng thuật toán mô tả ở trên cho phương trình lời giải gần đúng
$$g(x) = x^3 + 3x + x \cos^2 x - \sin(\cos x) = 0,$$

Cơm. 4.
