---
id: 1974-11-dorofeev-predelyi-posledovatelnostey-b99bc085
issue: kvant_1974_11
year: 1974
number: "11"
title: Giới hạn trình tự
authors:
  - Дорофеев Г. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 56
page_last: 61
page_labels: 54-59
tag: QELK
lang: vi
source: kvant_digital
extraction: vision
content_sha256: f683e6bd5aaaef870bee5bfa9039de476c808a8de2153ad7736a9cac7f40ab8c
prompt_sha256: draft-1
translated_from: content/ru/1974/11/articles/14_dorofeev-predelyi-posledovatelnostey-b99bc085.md
source_content_sha256: 40d89f63645eae38546eea61e7907c3e831dff337f0e3242314347c489a17c6f
translation_model: draft
translation_run: vi-draft-2026-11-03
translation_quality: draft
---

⟦folio 54⟧

Giới hạn trình tự
G. V. Dorofeev

Không giống như hầu hết các bài viết được xuất bản trong phần “Thực hành của người nộp đơn”, bài viết này không có gợi ý trong đó cái này hoặc cái kia bài toán sẽ được đề xuất.
Điều này không khó giải thích: khái niệm giới hạn trong khóa học ở trường chỉ được sử dụng cho mục đích lý thuyết và mọi bài toán tính toán liên quan đến giới hạn đều không được giải quyết ở trường. Do đó, điều tự nhiên là trong các lựa chọn của bài kiểm tra viết dành cho người nộp đơn, loại bài toán này không có.
Tuy nhiên, trong các tấm vé thi vấn đáp, khái niệm giới hạn xuất hiện một phần và điều đặc biệt quan trọng là ở tất cả các tấm vé đó. Đối với những độc giả đã chuẩn bị kỹ càng, chúng tôi cũng khuyên bạn nên tự làm quen với các bài viết của M. L. Gerver “20 bài toán đến giới hạn” («Kvant», 1974, số 3).

Nếu chúng ta chuyển sang chương trình dành cho những trường đại học xây dựng, thì chúng ta sẽ chỉ gặp từ “giới hạn” trong đó - trong đoạn 5 của phần 1 “Số học, đại số và các hàm cơ bản”. Tuy nhiên, bạn có thể đếm được hơn mười câu hỏi có trong chương trình, cơ sở của nó chính xác là khái niệm giới hạn. Trước hết, đây là những câu hỏi hình học liên quan đến chu vi, diện tích hình tròn, diện tích bề mặt và thể tích của hình trụ, hình nón, hình cầu và các bộ phận của nó. Ngoài ra, khái niệm giới hạn còn được sử dụng để xác định bậc của một số dương với số mũ vô tỷ và tổng của cấp số nhân vô hạn.

Trên thực tế, danh sách các câu hỏi sử dụng khái niệm giới hạn rộng hơn nhiều; chúng tôi chỉ đưa ra những trường hợp mà việc sử dụng giới hạn là hoàn toàn tiêu chuẩn và quen thuộc với học sinh. Ví dụ, khái niệm giới hạn được sử dụng để chứng minh bổ đề chính về sự giống nhau của các hình tam giác, công thức tính diện tích đường thẳng và thể tích đường thẳng của hình bình hành, để chứng minh sự tồn tại của nghiệm bậc tự nhiên của các số dương, sự tồn tại của logarit của số dương, v.v. Chúng ta sẽ tập trung vào một trong những câu hỏi này ở cuối bài viết.

Người nộp đơn thường có một câu hỏi: họ cần có bao nhiêu kiến ​​thức về các giới hạn của dãy. Đồng thời, nhiều người cho rằng không cần thiết phải biết bất kỳ định lý nào về giới hạn - xét cho cùng, trong phần chương trình “Các công thức và định lý cơ bản” khái niệm giới hạn không được đề cập đến!

Tuy nhiên, điều này không hoàn toàn đúng - khi chứng minh một số công thức và định lý có trong chương trình, các định lý giới hạn khác nhau được sử dụng rõ ràng và do đó cần phải biết ít nhất công thức của các định lý này và tôi sẽ thảo luận về cách chứng minh sau.

Ví dụ, hãy xem xét việc tính tổng của một cấp số nhân vô hạn. Như đã biết, tổng của mức cắt như vậy là giới hạn S tuần tự

⟦folio 55⟧

kích thích $(S_n)$, thức ăn $S_n$ - tổng $n$ của các thành viên đầu tiên trong tiến trình: $S = \lim_{n \to \infty} S_n$. Đây là việc xác định số lượng. Và để chứng minh rằng tổng của cấp số đó luôn tồn tại (xét cho cùng, không phải dãy nào cũng có giới hạn!), và để tính tổng này, người ta thực hiện phép tính sau:

$$\lim_{n \to \infty} S_n = \lim_{n \to \infty} a_1 \frac{1-q^n}{1-q} =$$

$$= \lim_{n \to \infty} \left( \frac{a_1}{1-q} - \frac{a_1}{1-q} q^n \right) =$$

$$= \frac{a_1}{1-q} - \frac{a_1}{1-q} \lim_{n \to \infty} q^n = \frac{a_1}{1-q}.$$

Các định lý sau đây được sử dụng trong tính toán này:

(1) nếu dãy $(a_n)$ có giới hạn thì với bất kỳ số nào $c$
$$\lim_{n \to \infty} (c-a_n) = c - \lim_{n \to \infty} a_n;$$

(2) nếu dãy $(a_n)$ có giới hạn thì với bất kỳ số nào $c$
$$\lim_{n \to \infty} c a_n = c \lim_{n \to \infty} a_n;$$

(3) với bất kỳ số nào $q$ thì tối đa là $|q| < 1$
$$\lim_{n \to \infty} q^n = 0.$$

Ngoài ra, lưu ý rằng cùng với câu lệnh (1) khi thực hiện phép biến đổi đầu tiên, có thể sử dụng hai định lý có tính chất “phổ quát” hơn: giới hạn hiệu của hai dãy bằng hiệu giới hạn của chúng và giới hạn của một dãy không đổi (c) (nghĩa là một dãy trong đó tất cả các số hạng bằng cùng một số $c$) bằng $c$:

(4) nếu các dãy $(a_n)$ và $(b_n)$ có giới hạn thì
$$\lim_{n \to \infty} (a_n-b_n) = \lim_{n \to \infty} a_n - \lim_{n \to \infty} b_n;$$

(5) $$\lim_{n \to \infty} c = c.$$

Lưu ý rằng với đáp số câu hỏi có tổng cấp số nhân giảm vô hạn sẽ kiểm tra xem người nộp đơn hiểu chính xác định lý nào và vị trí chính xác của chứng minh mà anh ta đang sử dụng - nếu không có lời giải thích như vậy, phép tính được thực hiện trông giống như một “bức ảnh” từ sách giáo khoa và tất nhiên là không thể làm hài lòng người giám khảo.

Tuy nhiên, điều này có thể là chưa đủ, nhất là khi vào một trường đại học có chương trình toán cao cấp. Trên thực tế, nếu đọc kỹ chương trình tương tự dành cho người nộp đơn, chúng ta sẽ thấy rằng người nộp đơn phải nắm vững các khái niệm toán học được đề cập trong phần 1. Và thành thạo có nghĩa là không chỉ có thể hình thành định nghĩa mà còn có thể áp dụng nó trong những trường hợp đơn giản nhất. Và việc chứng minh các mệnh đề (1)-(5), thật không may, ngoại trừ mệnh đề (4), có thể được mô tả đầy đủ cho những trường hợp đơn giản như vậy: chúng không yêu cầu tính toán giả tạo, không cần sự khéo léo và bất kỳ ai biết và hiểu định nghĩa giới hạn đều có thể tiếp cận được. Chúng ta hãy nhìn vào bằng chứng này.

Trước tiên chúng ta hãy nhớ lại rằng số a được gọi là giới hạn của dãy $(a_n)$ nếu với bất kỳ số dương $\varepsilon$ nào có một số cực đại $N$ sao cho tất cả các thành viên của dãy, bắt đầu bằng $a_{N+1}$, nằm trong khoảng giữa các số $a-\varepsilon$ và $a+\varepsilon$; nói cách khác, với mọi $n>N$ thì bất đẳng thức $a-\varepsilon<a_n<a+\varepsilon$, hay, giống nhau, $|a_n-a|<\varepsilon$, đúng.

Từ định nghĩa này, ngay lập tức có một sơ đồ chứng minh trực tiếp cho phát biểu $a=\lim_{n \to \infty} a_n$: cần chỉ ra cách, đối với một số dương tùy ý $\varepsilon$, tìm số $N$ có ​​thuộc tính cần thiết. Trong trường hợp này, cần phải xem xét không phải một số giá trị số cụ thể $\varepsilon$ (vì đôi khi nó hợp nhất, “hãy lấy một số tùy ý $\varepsilon$, ví dụ $\varepsilon=1/2$), mà là một giá trị tùy ý, nghĩa là coi $\varepsilon$ làm tham số.

⟦folio 56⟧

Tất nhiên, trong phần lớn các trường hợp, con số mong muốn $N$ sẽ phụ thuộc vào $\varepsilon$.

Đầu tiên chúng ta hãy chứng minh phát biểu đơn giản nhất (5).

Cho một dãy có số hạng chung $a_n=c$. Chúng ta hãy lấy một số dương tùy ý $\varepsilon$ và bắt đầu tìm một số $N$ sao cho với mọi $n>N$ bất đẳng thức $c-\varepsilon<a_n<c+\varepsilon$, tức là $c-\varepsilon<c+c+\varepsilon$, đúng. Bạn sẽ không phải tìm kiếm lâu - bất đẳng thức kép này luôn đúng (vì $\varepsilon>0$), vì vậy bạn có thể lấy bất kỳ số nào, đặc biệt là 1, làm $N$.

Bây giờ hãy chứng minh khẳng định (3).

Để $|q|<1$; Chúng ta hãy lấy một số tùy ý $\varepsilon>0$ và bắt đầu tìm một số $N$ sao cho với mọi $n>N$ bất đẳng thức $-\varepsilon<q^n<\varepsilon$ hoặc, giống nhau, $|q^n|<\varepsilon$ hoặc $|q|^n<\varepsilon$ đúng. Bất đẳng thức cuối cùng rất dễ giải: nó đúng với mọi $n>\log|q| \varepsilon$ (lưu ý rằng $|q|<1$). Do đó, $N$ có thể là bất kỳ số tự nhiên nào lớn hơn $[\log|q| \varepsilon]$, ví dụ $1+[\log|q| \varepsilon]$.

Khi chứng minh tuyên bố được xem xét trong kỳ thi, không cần thiết phải lặp lại tất cả các giải thích trên về bản chất phương pháp luận; Tốt hơn là kiểm tra bằng chứng chính xác hơn:

“Cho $\varepsilon$ là một số dương tùy ý; đặt $N=1+[\log|q| \varepsilon]$, moeda, nếu $n>N$, thì $n>\log|q| \varepsilon$, có thể $|q|^n<\varepsilon$ hoặc $-\varepsilon<q^n<\varepsilon$. Do đó, $\lim_{n\to\infty} q^n=0$". Không cần phải sợ giám khảo sẽ không hiểu giá trị $N$ này đến từ đâu, hoặc sẽ khiển trách bạn vì đã lấy nó “bất ngờ”.

Trong các ví dụ được thảo luận, chúng tôi thực sự có thể chỉ định rõ ràng số ban đầu $N$. Nếu không, chúng ta phải hạn chế chứng minh sự tồn tại của một con số như vậy - điều này cũng khá đủ!

Hãy chứng minh khẳng định (2).

Để $\lim_{n\to\infty} a_n=a$; Chúng ta hãy lấy một số tùy ý $\varepsilon>0$ và tìm một số $N$ sao cho với bất kỳ số $n>N$ nào thì bất đẳng thức $|ca_n-ca|<\varepsilon$ hoặc $|c|\cdot|a_n-a|<\varepsilon$ đúng.

Vì $c=0$ mệnh đề đang được chứng minh rõ ràng là đúng (nhờ vào mệnh đề (5)), chúng ta sẽ giả sử rằng $c\neq0$ và viết lại bất đẳng thức trên dưới dạng

$$|a_n-a|<\frac{\varepsilon}{|c|}.$$

Vì $\varepsilon/|c|$ là một số dương nào đó và $a=\lim_{n\to\infty} a_n$, nên theo định nghĩa của giới hạn, tồn tại một số $N'$ sao cho bất đẳng thức $n>N'$ (*) được thỏa mãn. Đặt $N=N'$, khi đó với $n>N$ bất đẳng thức (*) là đúng, do đó bất đẳng thức tương đương $|ca_n-ca|<\varepsilon$.

Vì vậy, chúng ta đã chứng minh rằng đối với một $\varepsilon>0$ tùy ý thì có một số $N$ sao cho đối với $n>N$ bất đẳng thức $|ca_n-ca|<\varepsilon$ đúng, và điều này có nghĩa là $\lim_{n\to\infty} ca_n=ca$, đó là điều chúng ta cần chứng minh.

Chứng minh mệnh đề (4) có phần phức tạp hơn. Chúng ta sẽ chứng minh mệnh đề tương tự cho tổng các dãy, chứng minh mệnh đề (4) như một bài tập.

Cho $\lim_{n\to\infty} a_n=a$, $\lim_{n\to\infty} b_n=b$, lấy $\varepsilon>0$ tùy ý. Khi đó tồn tại một số $N_1$ sao cho với $n>N_1$ bất đẳng thức sau đúng:

$$a-\frac{\varepsilon}{2}<a_n<a+\frac{\varepsilon}{2}.$$

Mặt khác, tồn tại một số $N_2$ sao cho $n>N_2$ bất đẳng thức

$$b-\frac{\varepsilon}{2}<b_n<b+\frac{\varepsilon}{2}.$$

Đối với $n$, cả $N_1$ và $N_2$ đều lớn, cả hai bất đẳng thức thu được đều được thỏa mãn và do đó

⟦folio 57⟧

và sự bất bình đẳng

$(a+b) - \varepsilon < a_n + b_n < (a+b) + \varepsilon,$

thu được bằng cách cộng từng số hạng của chúng.

Chúng ta đặt $N$ bằng số lớn hơn trong các số $N_1$ và $N_2$, $N = \max(N_1, N_2)$, thì bất đẳng thức $n > N$ (**) sẽ được thỏa mãn. Do đó, với $\varepsilon$, chúng tôi đã tìm thấy giá trị $N$ theo yêu cầu của định nghĩa và từ đó chứng minh rằng $\lim_{n \to \infty} (a_n + b_n) = a + b$.

Chúng ta hãy lưu ý rằng trong việc xây dựng các phát biểu về giới hạn thường có một hạn chế là các dãy xuất hiện trong chúng đều có giới hạn; Không có giới hạn này, các câu (1), (2), (4) đơn giản là vô nghĩa. Để tránh những hạn chế này lơ lửng trong không khí, thật hữu ích khi biết rằng không phải mọi trình tự đều có giới hạn.

Ví dụ về dãy không có giới hạn là dãy

$$0, 1, 0, 1, 0, 1, \dots$$

Thật ra, giả sử ngược lại, cho dãy này có giới hạn $a$. Chúng ta đặt $\varepsilon = 1/3$, thì chúng ta phải tìm $N$ sao cho tất cả các số hạng của dãy có số lớn hơn $N$ đều nằm trong khoảng $(a-1/3, a+1/3)$. Do đó, khoảng cách giữa các số hạng đó (trên trục số) không vượt quá 2/3. Tuy nhiên, trong dãy của chúng ta có các số 0 và 1, dù cách nhau bao xa thì khoảng cách giữa chúng cũng bằng 1, tức là lớn hơn 2/3.

Bây giờ chúng ta hãy tìm giới hạn của dãy với số hạng chung

$$c_n = \frac{1^2 + 2^2 + 3^2 + \dots + n^2}{6n^3},$$

được sử dụng khi tính toán các thông số thể tích bằng cách sử dụng các vật thể bậc thang. Để tính giới hạn này, chúng ta biến đổi biểu thức cho $c_n$:

$$c_n = \frac{n(n+1)(2n+1)}{6n^3} = \frac{(1 + \frac{1}{n})(2 + \frac{1}{n})}{6}.$$

Bây giờ việc tính giới hạn này có liên quan đến việc tính giới hạn của sản phẩm $d_n = \left(1 + \frac{1}{n}\right)\left(2 + \frac{1}{n}\right)$ và đối với quy trình này, chúng tôi sử dụng câu lệnh sau:

(6) nếu dãy $(a_n)$ và $(b_n)$ có giới hạn thì

$$\lim_{n \to \infty} a_n b_n = \lim_{n \to \infty} a_n \cdot \lim_{n \to \infty} b_n.$$

Tuy nhiên, việc chứng minh khẳng định này phức tạp hơn nhiều so với tất cả những khẳng định trước đó: nó đòi hỏi chứng minh sơ bộ về một số định lý nữa về giới hạn. Đồng thời, việc tính giới hạn của chúng ta có thể được thực hiện trực tiếp mà không cần sử dụng định lý tổng quát này. Hãy để chúng tôi chứng minh rằng giới hạn này bằng 2 (“bạn có thể đoán” rằng điều này là như vậy từ những thông điệp trực quan hoặc trên cơ sở của Định lý tổng quát tương tự 6—xét cho cùng, đối với điều này thì không cần thiết phải chứng minh điều đó!). Cần chứng minh rằng với mọi $\varepsilon > 0$ tồn tại một số $N$ sao cho với mọi $n > N$ bất đẳng thức

$$-\varepsilon < d_n - 2 < \varepsilon$$

$$-\varepsilon < \frac{3}{n} + \frac{1}{n^2} < \varepsilon.$$

Rõ ràng là bất đẳng thức bên trái đúng với mọi $n$ và bất đẳng thức $\frac{3}{n} + \frac{1}{n^2} < \varepsilon$ không khó giải, nhưng chúng ta sẽ tiến hành theo cách nghịch đảo. Từ bất đẳng thức $\frac{1}{n^2} \leq \frac{1}{n}$ suy ra $\frac{3}{n} + \frac{1}{n^2} \leq \frac{4}{n}$, và bất đẳng thức $\frac{4}{n} < \varepsilon$ đúng với mọi $n > \frac{4}{\varepsilon}$.

Pozny, nếu chúng ta lấy $N$ bất kỳ số tự nhiên nào lớn hơn $\frac{4}{\varepsilon}$, thì tại $n > N$ sẽ có $n > \frac{4}{\varepsilon}$, tức là, $\frac{4}{n} < \varepsilon$, và do đó

$$\frac{3}{n} + \frac{1}{n^2} \leq \frac{4}{n} < \varepsilon.$$

⟦folio 58⟧

Do đó, đối với $\varepsilon > 0$ tùy ý, chúng tôi đã chỉ ra số được yêu cầu $N$, do đó, $\lim_{n \to \infty} d_n = 2$ và $\lim_{n \to \infty} c_n = 1/3$.

Để kết luận, chúng ta hãy chuyển sự chú ý sang một loạt vấn đề khác liên quan đến khái niệm giới hạn, cụ thể là ứng dụng của cái gọi là định lý Weierstrass. Chúng ta hãy nhớ lại công thức của nó: mọi dãy thao tác tăng đơn điệu đều có một giới hạn. Phát biểu tương tự cũng đúng đối với các dãy giảm đơn điệu.

Chúng ta sẽ không tập trung vào các ứng dụng tiêu chuẩn của định lý này (ví dụ: khi xác định chu vi của một hình tròn); chúng tôi sẽ chỉ ra một số ứng dụng khác của nó.

Mọi người đều biết rằng bạn không thể lấy căn bậc hai của số âm và họ có thể dễ dàng chứng minh điều đó. Mọi người cũng biết rằng căn bậc hai có thể được lấy từ bất kỳ số dương nào, nhưng làm thế nào người ta có thể chứng minh rằng nó tồn tại? Điều này được thiết lập bằng định lý Weierstrass.

Thật vậy, cho trước một số dương $c$; thì tồn tại một số nguyên không âm $a_0$ sao cho

$$a_0^2 \leq c < (a_0 + 1)^2$$

($a_0$ là số nguyên gần đúng của căn bậc hai của $c$ khi thiếu, $a_0 + 1$ khi thừa). Tiếp theo, chúng ta có thể tìm số nguyên $a_1$ từ 0 đến 9 sao cho

$$\left( a_0 + \frac{a_1}{10} \right)^2 \leq c < \left( a_0 + \frac{a_1 + 1}{10} \right)^2$$

(nghĩa là lấy xấp xỉ căn bậc hai của $c$ với độ chính xác là 1/10).

Tiếp tục quá trình này, chúng ta nhận được hai chuỗi:

$$(a_n) = \left( a_0, a_0 + \frac{a_1}{10}, a_0 + \frac{a_1 + 1}{100}, \dots \right)$$

Và

$$(b_n) = \left( a_0 + 1, a_0 + \frac{a_1 + 1}{10}, a_0 + \frac{a_1 + 1}{100}, \dots \right).$$

Chuỗi đầu tiên trong số này đang tăng dần và bị chặn - ví dụ: tất cả các số hạng của nó đều nhỏ hơn $a_0 + 1$; theo định lý Weierstrass nó có một giới hạn nhất định $a$. Chuỗi thứ hai tương tự có một số giới hạn $b$. Nhờ lời tuyên bố (6)

$$\lim_{n \to \infty} a_n^2 = a^2, \lim_{n \to \infty} b_n^2 = b^2.$$

Mặt khác, do chính việc xây dựng các chuỗi này nên có những bất đẳng thức

$$a_n^2 \leq c < b_n^2,$$

do đó (xem bài tập 9) rằng

$$a^2 \leq c \leq b^2.$$

Cuối cùng, chúng tôi thu được các câu (4) và (3), chúng tôi thu được

$$a - b = \lim_{n \to \infty} a_n - \lim_{n \to \infty} b_n =$$

$$= \lim_{n \to \infty} \left( a_n - b_n \right) = \lim_{n \to \infty} (1/10)^{n-1} = 0.$$

Do đó, $a = b$, và do đó, $a^2 = c$. Nói cách khác, $a$ là căn bậc hai của $c$ và chúng tôi yêu cầu tuyên bố đó phải được chứng minh.

Chúng ta thấy rằng việc chứng minh một phát biểu “hiển nhiên” như sự tồn tại căn bậc hai của một số dương thực sự đòi hỏi phải sử dụng một số lượng lớn các định lý giới hạn. Do đó, bằng chứng cấu trúc của nó (và bằng chứng của các mệnh đề tương tự: sự tồn tại của logarit của số dương, sự tồn tại của lũy thừa của số dương với số mũ vô tỷ, sự tồn tại của giá trị arcsine cho bất kỳ số nào từ -1 đến 1, v.v.) không được đưa vào chương trình giảng dạy ở trường hoặc chương trình xây dựng trường đại học. Chúng tôi xem xét vấn đề này chỉ để cho thấy sự khó khăn thực sự của việc chứng minh những phát biểu đó và đưa ra ý tưởng cơ bản về phương pháp chứng minh chúng.

⟦folio 59⟧

Tại sợi
1. Chứng minh rằng giới hạn của dãy $1, -\frac{1}{2}, \frac{1}{3}, -\frac{1}{4}, \frac{1}{5}, -\frac{1}{6}, \dots$ là 0.
2. Chứng minh rằng $\lim_{n \to \infty} \frac{1}{n} = 1$.
3. Giả sử các dãy $(a_n)$ và $(b_n)$ có giới hạn và với bất kỳ $n$ nào thì bất đẳng thức $0 \leq a_n \leq b_n$ đúng. Chứng minh rằng nếu $\lim_{n \to \infty} b_n = 0$ thì cũng $\lim_{n \to \infty} a_n = 0$.
4. Đặt chuỗi $(a_n)$ có giới hạn $a$ và chuỗi $(b_n)$ thu được từ nó:
   a) bằng cách đưa ra một số hữu hạn các số hạng;
   b) vứt bỏ vô số số hạng (ví dụ: tất cả các số hạng chẵn);
   b) việc bổ sung ở một số nơi số lượng thành viên mới có hạn;
   g) bằng cách thêm vào một số nơi vô số thành viên mới.
   Trong mỗi trường hợp này, có thể nói gì về giới hạn của dãy $(b_n)$?
5. Tính giới hạn của dãy có số hạng chung:
   a) $a_n = \frac{1}{n^2 + 2}$;
   b) $a_n = \frac{4n}{3n^3 - 5n - 4}$.
6. Chứng minh rằng dãy $1, 0, \frac{1}{2}, \frac{1}{2}, \frac{2}{3}, \frac{1}{3}, \frac{3}{4}, \frac{1}{4}, \frac{4}{5}, \frac{1}{5}, \dots$ và $1, 0, 2, 1, 0, 2, 1, 0, 2, \dots$ không có giới hạn.
7. Chứng minh rằng nếu dãy $(a_n)$ và $(b_n)$ có giới hạn thì $\lim_{n \to \infty} (a_n - b_n) = \lim_{n \to \infty} a_n - \lim_{n \to \infty} b_n$.
8. Chúng ta có thể nói gì về giới hạn của dãy $(a_n + b_n)$ nếu dãy $(a_n)$ và $(b_n)$:
   a) cả hai đều có giới hạn;
   b) cả hai đều không có giới hạn;
   b) một cái có giới hạn còn cái kia thì không?
9. Chứng minh rằng nếu mọi số hạng của dãy $(a_n)$ đều nhỏ hơn số $c$ thì giới hạn của dãy này không lớn hơn $c$. Chúng ta có thể nói rằng giới hạn này nhỏ hơn $c$ không?

Bài tập về đồ thị và truyện cổ tích “Ivan Tsarevich và Sói Xám”
(Kết thúc. Xem phần đầu ở trang 23)

2. Bạn không thể đi cùng một con đường; nếu bạn xóa con đường đó, chúng ta sẽ thấy rằng không còn cách nào để đến thủ đô từ một thành phố nào đó nữa. (Con đường như vậy được gọi là eo đất).

Nếu chúng ta theo sau bằng 2 thì tại bất kỳ thời điểm nào các con đường vẫn chưa bị xóa và các thành phố tạo thành một biểu đồ được kết nối. Hãy để chúng tôi chứng minh rằng chúng tôi luôn có thể đi theo một con đường bằng 2, nghĩa là khi đến bất kỳ thành phố nào $N$, chúng tôi sẽ có sẵn một con đường không phải là eo đất.

Trước tiên, chúng ta hãy lưu ý rằng nếu đường từ $N$ hóa ra là một eo đất thì cũng có những đường đi từ $N$. Hãy giả sử điều tồi tệ nhất - tất cả những con đường này hóa ra là eo đất vào thời điểm đó. Giả sử chúng ta đã xóa hai trong số chúng; một kết nối thành phố $N$ với thành phố $N_1$, cái còn lại - với thành phố $N_2$. Rõ ràng, trong trường hợp này, từ những phần này phải có một thành phố khác có số đường lẻ. Nhưng điều này là không thể, vì tại thời điểm này trên bản đồ có số lượng đường lẻ, ngoài các thành phố $N_1$ và $N_2$, chỉ còn lại thủ đô.

Cuối cùng chúng ta hãy chứng minh rằng, theo quy tắc 1 và 2, chúng ta phải đi vòng quanh tất cả các con đường một lần. Giả sử rằng chúng ta trở về thủ đô mà không đi qua hết các con đường. Điều này có nghĩa là các thành phố vẫn chưa bị xóa trên bản đồ. Khoảng cách là thành phố chưa bị xóa sổ $M$ mà chúng tôi đã đi qua lần trước. Rõ ràng, con đường mà chúng tôi rời đi là một eo đất: nó không dẫn đến thủ đô (nếu không chúng tôi đã đến thủ đô trực tiếp từ $M$, và thành phố $M$ sẽ bị xóa trên bản đồ - xem quy tắc 1), và bằng cách xóa con đường này, chúng tôi sẽ cắt đứt tất cả các tuyến đường từ $M$ đến thủ đô. Nhưng theo quy tắc 2, chúng ta không thể đi theo những con đường như vậy. Chúng tôi đã nhận được sự phản đối.

Như vậy định lý Euler đã được chứng minh hoàn toàn.
