---
id: 1987-10-gutenmaher-osnovnyie-teoremyi-0498e251
issue: kvant_1987_10
year: 1987
number: "10"
title: Định lý cơ bản
authors:
  - Гутенмахер В. Л.
rubric: shkola-v-kvante
rubric_sub: Школа в «Кванте»
page_first: 38
page_last: 40
page_labels: 36-38
tag: 561V
lang: vi
source: kvant_digital
extraction: vision
content_sha256: a00e5648f5d180c5e451fd4e1e4c7d4db108d8940a81cb9d2fba6a6e9dc887fc
prompt_sha256: draft-1
translated_from: content/ru/1987/10/articles/14_gutenmaher-osnovnyie-teoremyi-0498e251.md
source_content_sha256: 6072344ad0900278303c5525c7d2d7e109c480d673af44f02b5ef71b23cc2f24
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 36⟧

Định lý cơ bản

Ứng viên Khoa học Vật lý và Toán học
V. L. GUTENMACHER

Mục tiêu của chúng ta là nói về ba định lý chính của ba chữ A vĩ đại: Số học, Đại số, Giải tích. Bất cứ ai thậm chí hơi quan tâm đến toán học cũng nên biết những định lý này. Thứ nhất là phân tích số thành thừa số nguyên tố, thứ hai là phân tích đa thức thành đa thức tối giản, thứ ba là tính diện tích.

Chúng ta bắt đầu với định lý cơ bản của đại số: Rene Descartes đã viết về nó vào năm 1637 - đúng 350 năm trước - trong cuốn sách Hình học của ông.
Cuốn sách này có một chương về các phương trình; nó bắt đầu bằng những từ này:

“Biết rằng bất kỳ phương trình nào cũng có thể có nhiều nghiệm bằng với bậc của phương trình, hoặc độ biến thiên của hai phương trình $x-2=0$ và $x-3=0$, thì chúng ta thu được phương trình bậc hai: $x^2-5x+6=0$, có nghiệm 2 và 3. Nếu phương trình này lần lượt được nhân với $x-4=0$, chúng ta sẽ có phương trình bậc ba $x^3-9x^2+26x-24=0$ với phần ba 2, 3 và 4.”

Trong môn đại số lớp 8, người ta đã chứng minh rằng đa thức bậc hai $x^2+px+q$, có nghiệm $x_1$ và $x_2$, được biểu diễn dưới dạng tích của các đa thức bậc một:

$$x^2+px+q=(x-x_1)(x-x_2).$$

Ví dụ về phân tích trilen vuông thành tích:

$$x^2-x-2=(x+1)(x-2);$$
$$x^2-2x+1=(x-1)^2;$$
$$x^2-2=(x-\sqrt{2})(x+\sqrt{2});$$
$$x^2+x-1=(x+1/2-\sqrt{5}/2)(x+1/2+\sqrt{5}/2).$$

Tuy nhiên, theo đó, trilen vuông không có nghiệm và không thể phân hủy thành sản phẩm như vậy. Đối với các đa thức có bậc cao hơn, định lý cũng đúng với chúng:

Bất kỳ đa thức nào có dạng $x^n+a_{n-1}x^{n-1}+a_{n-2}x^{n-2}+\ldots+a_0$ đều có thể phân tích thành tích của các đa thức có dạng $x-a$ và đa thức bậc hai có dạng $x^2+px+q$, không có nghiệm; Hơn nữa, cách khai triển này là duy nhất: hai cách khai triển như vậy chỉ khác nhau về thứ tự các thừa số.

⟦folio 37⟧

Ví dụ về đa thức phân tích nhân tử:
$$x^3 + 1 = (x + 1)(x^2 - x + 1) \quad - 1 \text{ корень};$$
$$x^3 - 6x^2 + 11x - 6 = (x - 1)(x - 2)(x - 3) \quad - 3 \text{ корня};$$
$$x^3 - 3x^2 + 3x - 1 = (x - 1)^3 \quad - 1 \text{ корень};$$
$$x^4 - 1 = (x^2 + 1)(x - 1)(x + 1) \quad - 2 \text{ корня};$$
$$x^4 + 1 = (x^2 - \sqrt{2x} + 1)(x^2 + \sqrt{2x} + 1) \quad - 0 \text{ корней}.$$

Từ định lý này, suy ra rằng một đa thức bậc $n$ có thể có nhiều nhất $n$ nghiệm; sẽ có chính xác $n$ nghiệm nếu nó có thể phân tích thành tích của $n$ đa thức khác nhau có dạng $x-a$. Một đa thức có thể có nghiệm danh nghĩa do thực tế là một số đa thức như vậy được lặp lại (trong trường hợp này phát sinh nhiều nghiệm) và do thực tế là một số đa thức là tam thức vuông không có nghiệm.

Định lý này sẽ có dạng được nghiên cứu kỹ hơn nhiều nếu chúng ta giới thiệu cách sử dụng dạng số, tức là biểu thức có dạng $a - b\sqrt{-1}$, trong đó $(a; b)$ là một cặp số thực. Khi đó, bất kỳ tam thức bình phương nào (có hệ số thực hoặc phức) đều có hai nghiệm phức và có thể phân tích thành đa thức bậc một.

Ví dụ về khai triển tam thức bậc hai có nghiệm phức:
$$x^2 + 1 = (x + \sqrt{-1})(x - \sqrt{-1});$$
$$x^4 - 4x + 3 = (x - 1)^2(x + 1 - \sqrt{-2}) \times (x + 1 + \sqrt{-2}).$$

Nhờ đó, định lý được xây dựng trước đó có dạng sau:

Bất kỳ đa thức nào có dạng $x^n + \alpha_{n-1}x^{n-1} + \alpha_{n-2}x^{n-2} + \dots + \alpha_0$ (ede $\alpha_{n-1}, \alpha_{n-2}, \dots, \alpha_0$ là số phức) đều được biểu diễn dưới dạng tích của $n$ các hàm số $(x - \beta_1)(x - \beta_2) \dots (x - \beta_n)$ và $\beta_1, \beta_2, \dots, \beta_n$ là các số phức và cách biểu diễn như vậy là duy nhất tùy theo thứ tự của các hàm số.

Đây là định lý cơ bản của đại số.

* * *

Định lý cơ bản của số học gần giống với định lý cơ bản của đại số:

Mọi số nguyên dương lớn hơn một đều có thể được biểu diễn dưới dạng tích của các số nguyên tố. Hơn nữa, hai cách phân rã như vậy chỉ có thể khác nhau về thứ tự phức tạp.

Ví dụ về phân tích số thành thừa số nguyên tố:
$$400 = 2^4 \cdot 5^2; \quad 1001 = 7 \cdot 11 \cdot 13;$$
$$290 981 = 43 \cdot 67 \cdot 101; \quad 1987 = 1987.$$

Chúng ta thực sự sử dụng định lý này, bắt đầu từ trường tiểu học, cả khi rút gọn phân số và khi rút gọn chúng về giá trị tổng quát nhất.

Thông thường, chúng ta sử dụng câu lệnh sau, rất dễ hiểu, tương đương với định lý cơ bản của số học: nếu tích của các số chia hết cho một số nguyên tố nào đó thì ít nhất một trong các thừa số chia hết cho số nguyên tố này.

Vì vậy, cả hai định lý cơ bản - số học và đại số - đều liên quan đến vấn đề phân rã thành tích của những cái không thể giải được. Mục tiêu là các số được phân tách thành tích của các số nguyên tố và các đa thức được phân tách thành tích của các đa thức không dẫn điện, như người ta nói. Cả hai định lý đều phát biểu rằng sự phân tách như vậy là duy nhất.

Một bằng chứng chặt chẽ về định lý cơ bản của đại số được đưa ra vào năm 1799 bởi nhà toán học vĩ đại người Đức K. F. Gauss (1777-1855); Năm 1801, ông đã xây dựng và chứng minh định lý cơ bản của số học*).

Phát biểu về định lý cơ bản của số học là hoàn toàn rõ ràng và đã được biết đến từ thời cổ đại, nhưng chính Gauss là người hiểu tầm quan trọng của phát biểu về tính duy nhất của phân tích nhân tử. Hóa ra là có thể có các hệ thống số trong đó việc phân tích định lý cơ bản của số học không còn đúng nữa. Không đi sâu vào vấn đề này một cách chi tiết, chúng tôi sẽ chỉ đưa ra ví dụ nổi tiếng nhất - hệ thống số có dạng $a + b\sqrt{-5}$, trong đó $(a; b)$ là một cặp số (cộng và nhân theo cùng một quy tắc như phần bù). Ví dụ: trong hệ thống này, $21 = 3 \cdot 7 = (4 + \sqrt{-5})(4 - \sqrt{-5})$. Chúng ta sẽ không thảo luận ở đây tại sao các số 3, 7, 4 + \sqrt{-5}, 4 - \sqrt{-5} lại là số nguyên tố trong hệ thống số này. Bạn đọc quan tâm có thể tìm thấy đáp số trong cuốn sách tuyệt vời của G. Rademacher và O. Teplitz “Số và Hình” - M.: “Fizmatgiz”, 1962.

Tuy nhiên, người ta không nên nghĩ rằng trong bất kỳ hệ thống số nào có dạng $a + b\sqrt{d}$

*) Để chứng minh định lý cơ bản của số học, xem ví dụ «Kvant», 1987, số 4, tr. 12; chứng minh định lý cơ bản của đại số - năm «Kvant», 1980, số 2, tr. 17; 1982, không. 4, tr. 3.

⟦folio 38⟧

(a, b là số nguyên, d là số nguyên cố định) không có hệ số duy nhất thành thừa số nguyên tố. Một ví dụ quan trọng của hệ thống số “tốt” là cái gọi là số Gaussian, tức là các số có dạng $a+b\sqrt{-1}$, trong đó $a$ và $b$ là số nguyên. Đối với họ, việc phân tích định lý cơ bản của số học diễn ra.

Khi xây dựng phân tích này, chúng ta phải tính đến sự hiện diện của cái gọi là số khả nghịch. Một số (Gaussian hoặc số thường) được gọi là số nghịch đảo nếu tồn tại một số khác (có thể giống nhau) sao cho tích của hai số này bằng 1. Trong số các số nguyên, số 1 và - 1 là khả nghịch; trong số các đa thức, đa thức “độ 0” là khả nghịch - các số khác 0; giữa các số Gaussian - các số 1, - 1, $\sqrt{-1}$ và - $\sqrt{-1}$. Khi khai triển $q=p_1\dots p_n$ thành các đa thức đơn giản, người ta có thể nhân $p_1$ và $p_2$ với các số có tích bằng 1, để thu được một khai triển khác. Điều này buộc chúng ta không thể phân biệt giữa các khai triển thu được từ nhau bằng cách nhân các thành phần nghịch đảo. Trong trường hợp này, cả $q$ và $p_1$, ..., $p_n$ đều phải được coi là không đảo ngược. Khi xây dựng định lý cơ bản của số học, chúng ta đã tránh được những dè dặt này bằng cách giả định rằng tất cả các số đều lớn hơn 1; trong việc xây dựng định lý cơ bản của đại số - giả sử rằng các hệ số cao nhất của đa thức bằng 1.

* * *

Trong khi các định lý cơ bản của đại số và số học có liên quan với nhau, như chúng ta đã thấy, thì định lý cơ bản của giải tích lại khác xa chúng. Đây là định lý Newton-Leibniz được đưa vào chương trình toán lớp 10.

Định lý này được thay thế bằng thực tế là nó cho phép người ta tìm diện tích các hàm số cong. Nó tạo ra một số lượng lớn bản in cũng bởi vì nó liên kết với nhau hai vùng hình học dường như hoàn toàn khác nhau bài toán: bài toán kiểm tra các tiếp tuyến (đạo hàm) và bài toán các vùng tìm kiếm (các phần giữa). Ý tưởng cho rằng những bài toán này phải nghịch đảo lẫn nhau lần đầu tiên được thay thế bởi thầy của Newton, nhà toán học người Anh Isaac Barruu. Nhưng mối liên hệ này lần đầu tiên được Newton thu được dưới dạng một công thức và, độc lập với ông, bởi Leibniz.

Đặc biệt, định lý Newton–Leibniz phát biểu rằng nếu một hàm dương liên tục $f$ được xác định trên cùng một khoảng (hoặc, như người ta nói, hàm $F$ là một biến đổi nội hàm của hàm $f$), thì diện tích $S$ dưới đồ thị của nó được tìm thấy bằng công thức

$$S = \int_a^b f(x)dx = F(b) - F(a) \text{ (см. рис. 1)}.$$

Ví dụ: có thể tìm thấy diện tích của “giá đỡ parabol” (hình 2) bằng công thức sau: hàm $f(x) = x^2$ là đạo hàm của hàm $F(x) = x^3/3$ và do đó, diện tích mà chúng ta quan tâm bằng

$$\int_0^1 x^2dx = \frac{1}{3} - \frac{0}{3} = \frac{1}{3}.$$

Diện tích này lần đầu tiên được tính toán bởi Archimedes, tất nhiên là không biết gì về công thức Newton-Leibniz. (Điều thú vị là Archimedes đã giải được bài toán này trong các bối cảnh khác nhau ít nhất ba lần mà không biết rằng mình đang giải cùng một bài toán.)

Bài toán việc tìm một máy biến áp cho một hàm nhất định hóa ra lại là một bài toán giải tích quan trọng. Đối với các hàm hữu tỉ, nó liên quan đến định lý cơ bản của đại số: một hàm hữu tỉ phân số chưa biến đổi luôn có thể được biểu diễn dưới dạng các hàm cơ bản (bao gồm logarit và arcgent), nhưng để làm được điều này, bạn cần biết cách phân tích mẫu số thành thừa số tuyến tính và bình phương.
