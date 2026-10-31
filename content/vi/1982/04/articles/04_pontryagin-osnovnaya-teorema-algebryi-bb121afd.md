---
id: 1982-4-pontryagin-osnovnaya-teorema-algebryi-bb121afd
issue: kvant_1982_4
year: 1982
number: "4"
title: Định lý cơ bản của đại số
authors:
  - Понтрягин Л. С.
rubric: osnovnye-stati
page_first: 6
page_last: 11
page_labels: 4-9
tag: AG6B
lang: vi
source: kvant_digital
extraction: vision
content_sha256: a53e955914fec1904ebcc2fc488db0b379f325f639cf6a794e31d5519f8faef8
prompt_sha256: draft-1
translated_from: content/ru/1982/04/articles/04_pontryagin-osnovnaya-teorema-algebryi-bb121afd.md
source_content_sha256: a680041c105f3f03f55028c0c59c3e548fa06c69a2eee25011ad896dbd0597e4
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 4⟧

chuyển động chứ không phải đường mà điểm chuyển động mô tả. Tuy nhiên, cùng một dòng có thể được mô tả theo những cách khác nhau.

Trong quá trình chuyển động, điểm $z(t)$ tại những thời điểm khác nhau có thể cùng rơi vào một điểm trên mặt phẳng nên không loại trừ đẳng thức

$$z(t_2) = z(t_3)$$ tại $t_2 \neq t_3$.

Vì vậy, để có thể có giao lộ tự. Nó thậm chí có thể bao gồm một điểm, chính xác là trong trường hợp điểm $z(t)$ không di chuyển chút nào khi $t$ thay đổi.

Trong phần tiếp theo, trừ khi điều này được nêu cụ thể, chúng ta sẽ luôn giả sử rằng let không đi qua gốc tọa độ, nghĩa là đại lượng $z(t)$ không biến mất đối với bất kỳ giá trị nào $t$.

Điểm $z(t_0) = z_0$ được gọi là điểm bắt đầu của đường dẫn và điểm $z(t_1) = z_1$ là điểm kết thúc của đường dẫn đó.

Nếu đẳng thức $z_0 = z_1$ giữ nguyên thì gọi nó là đóng (Hình 2).

Vì số phức $z(t)$ không biến mất nên với bất kỳ giá trị $t$ nào, đối số $\varphi(t)$ được xác định là số phức $z(t)$; nhưng nó chỉ được định nghĩa theo thuật ngữ $2k\pi$. Sự mơ hồ này là điều chúng tôi không mong muốn. Để loại bỏ nó, chúng ta sẽ chọn một đối số được xác định rõ ràng $\varphi_0 = \varphi(t_0)$ cho điểm bắt đầu $z_0$.

Sau đó, khi $t$ tăng lên, chúng ta sẽ chọn đối số $\varphi(t)$ của điểm $z(t)$ sao cho với những thay đổi nhỏ $t$ thì nó sẽ thay đổi ít. Sự mơ hồ về lựa chọn đối số này sẽ bị loại bỏ. Việc thêm số $2k\pi$ vào đối số tại $k \neq 0$ sẽ ngay lập tức dẫn đến sự thay đổi mạnh về giá trị $\varphi(t)$. Bằng cách chọn giá trị ban đầu của đối số $\varphi(t_0) = \varphi_0$ và đảm bảo rằng đối số $\varphi(t)$ của điểm $z(t)$ thay đổi liên tục cùng với $t$, chúng ta thu được một hàm được xác định rõ ràng $\varphi(t)$, thay đổi liên tục, nghĩa là không có bước nhảy. Nếu bạn chọn giá trị ban đầu của đối số $\varphi_0$ khác, thay đổi nó thành $2k\pi$, thì nó sẽ khác với giá trị được chọn trước đó chính xác $2k\pi$ trong suốt quá trình thay đổi $t$. Theo đó, với phương pháp xây dựng hàm $\varphi(t)$ này, giá trị

$$\varphi(t_1) - \varphi(t_0)$$

không phụ thuộc vào giá trị ban đầu được chọn ngẫu nhiên của đối số của số $z_0$.

Nếu để đóng thì điểm $z_0$ và $z_1$ trùng nhau và do đó, đối số của chúng $\varphi(t_0)$ và $\varphi(t_1)$ chỉ có thể khác nhau $2k\pi$. Do đó, số (1) trong trường hợp đường dẫn kín là $2k\pi$. Số nguyên $k$ được gọi là chỉ số của một đường dẫn khép kín trong mặt phẳng của số nguyên phức $z$. Cần nhấn mạnh một lần nữa rằng chỉ số của một đường dẫn khép kín chỉ có thể được xác định nếu nó không đi qua gốc tọa độ.

Chỉ số $k$ có ý nghĩa hình học đơn giản. Cụ thể, nó cho biết số lần điểm $z(t)$, mô tả một đường dẫn khép kín, đi xung quanh gốc tọa độ (Hình 3).

Hãy xem xét một ví dụ đơn giản. Giả sử $1 + r(\cos t + i \sin t); 0 \leq t \leq 2\pi$ đóng lại. Nó mô tả một đường tròn có tâm tại điểm 1 và bán kính $r$ và vượt qua đường tròn

⟦folio 5⟧

theo thời gian $t$ đều ngược chiều kim đồng hồ. Nếu số $r$ nhỏ hơn 1 thì đường tròn không chứa điểm gốc và chỉ số đường dẫn là 0. Nếu $r > 1$ thì đường tròn chứa điểm gốc và chỉ số đường dẫn là 1 (bạn hãy tự kiểm tra điều này). Trong trường hợp $r = 1$, để nó đi qua gốc tọa độ và chỉ số của nó không được xác định. Nếu số $r$ nhỏ hơn 2, như đã nêu, thì biến dạng của một đường khép kín không làm thay đổi chỉ số của nó, trừ khi tại một điểm nào đó biến dạng đi qua gốc tọa độ.

Bằng cách nói rằng hãy để nó được mô tả bằng chuyển động của một thời điểm, chúng tôi chỉ muốn làm cho định nghĩa về đường đi trở nên trực quan hơn. Trong thực tế, chúng ta đang nói về sự phụ thuộc của biến phức $z$ vào một số tham số hành động $t$ (có thể được biểu thị bằng một chữ cái khác). Vì vậy, ví dụ: giả sử (2) được viết dưới dạng $1 + r(\cos \alpha + i \sin \alpha); 0 \leqslant \alpha \leqslant 2\pi,$ (3) trong đó tham số không còn là $t$ mà là $\alpha$. Rõ ràng rằng giả sử (3) được mô tả bởi điểm $1 + z$, khi điểm $z$ mô tả let

$$r(\cos \alpha + i \sin \alpha); 0 \leqslant \alpha \leqslant 2\pi.$$

Ở đây $r$ là một tham số số mà chính nó phụ thuộc vào. Nói rằng khi $r$ thay đổi thì cho (3) biến dạng.

Hãy để chúng tôi giới thiệu khái niệm về biến dạng đường dẫn. Giả sử rằng biến dạng, nếu nó thay đổi dần dần

$$r( \cos \alpha + i \sin \alpha ); 0 \leqslant \alpha \leqslant 2\pi.$$

Cơm. 4.

Biến dạng đường đi 1+r(cosα+i sinα) khi thay đổi $r$

Cơm. 5.

⟦folio 6⟧

thành 2π, đối số điểm $z^n$ thay đổi từ 0 thành $2n\pi$. Do đó, chỉ số của đường dẫn (5) bằng $n$ (xem Hình 6, minh họa sơ đồ trường hợp $n=3$).

Hàm phức của biến phức

Nếu giá trị số của một biến phức $w$ có thể được tìm thấy bằng cách biết giá trị số của một biến phức khác $z$, thì biến $w$ được gọi là hàm của biến $z$, được viết dưới dạng

$$w = f(z).$$

Nếu hàm phức $f(z)$ của biến phức $z$ là tùy ý thì nó được gọi là hàm phân tích. Lý thuyết về hàm giải tích hiện nay là một trong những nhánh quan trọng nhất của toán học. Ở đây chúng ta sẽ chỉ quan tâm đến các hàm giải tích thuộc một loại rất cụ thể, cụ thể là đa thức.

Xét đa thức

$$w = f(z) = z^n + a_1 z^{(n-1)} + \dots + a_{(n-1)} z + a_n,$$

trong đó $a_1, a_2, \dots, a_n$ là các hệ số phức và $n$ là số nguyên không âm được gọi là bậc của đa thức. Mục tiêu nghiên cứu của chúng tôi là chứng minh rằng đa thức (6) bậc dương có nghiệm, tức là phương trình

$$f(z) = 0,$$

trong đó $f(z)$ là đa thức (6) và $n > 0$ có lời giải. Để chứng minh điều này ta xét đường đi khép kín

$$f(r(\cos \alpha + i \sin \alpha)); 0 \leqslant \alpha \leqslant 2\pi,$$

điểm $f(z)$ mô tả khi điểm $z$ mô tả một đường dẫn đã đóng

$$r(\cos \alpha + i \sin \alpha); 0 \leqslant \alpha \leqslant 2\pi.$$

Trường hợp số hạng tự do $a_n$ của đa thức $f(z)$ bằng 0 thì không cần xét đến, vì trong trường hợp này đa thức $f(z)$ có ​​nghiệm rất mạnh $z = 0$. Vì vậy, chúng tôi sẽ giả sử rằng $a_n \neq 0$. Đường dẫn kín (7) phụ thuộc vào tham số $r$ và khi tham số $r$ thay đổi, nó sẽ bị biến dạng. Tại $r = 0$, số $z$ là 0 và đường dẫn $f(z)$ bao gồm điểm cố định $a_n$. Do đó, chỉ số của nó tại $r = 0$ là 0. Chúng ta sẽ chứng minh rằng nếu lấy $r$ đủ lớn thì chỉ số của đường dẫn (7) là $n$. Nhưng theo giả định $n \neq 0$, do đó, khi các số $r$ thay đổi từ giá trị lớn thành 0, đường dẫn (7) bị biến dạng, đi qua gốc tọa độ ở một giá trị $r$ nào đó, và điều này có nghĩa là ở một giá trị nào đó $z$ hàm $f(z)$ sẽ tiến về 0, tức là nghiệm của đa thức này tồn tại (Hình 7).

Để chứng minh rằng với một $r$ đủ lớn, đường dẫn đóng (7) có chỉ số bằng $n$, chúng ta tiếp tục đường dẫn này thành một đường dẫn đơn giản hơn, chỉ số của nó dễ tính toán.

Trước hết, chúng ta sẽ phân tích đa thức $f$ thành tổng của hai

$$f(z) = z^n + g(z),$$

trong đó $g(z)$ được cho bởi

$$g(z) = a_1 z^{n-1} + a_2 z^{n-2} + \dots + a_{n-1} z + a_n.$$

Đa thức $g(z)$ là các số được xác định rõ ràng, khi đó tất cả chúng đều không vượt quá modulo một số hằng số $C$. Từ bất đẳng thức (8) đã được chứng minh trong bài viết trước (xem «Kvant», 1982, Số 3), mở rộng đến một số số hạng tùy ý, suy ra điều đó cho $|z| > 1$

$$|g(z)| \leqslant nC|z^{n-1}|.$$

Xét đa thức $f(z, s)$, phụ thuộc vào tham số $s$, $0 \leqslant s \leqslant 1$, cho bởi công thức sau:

$$f(z, s) = z^n + sg(z).$$

Chúng ta có sự bình đẳng

$$z^n = f(z, s) - sg(z),$$

Ở đâu

$$|z^n| \leqslant |f(z, s)| + |-sg(z)| \leqslant |f(z, s)| + nC|z^{n-1}| \leqslant |f(z, s)| + nC|z^{n-1}|,$$

⟦folio 7⟧

Cơm. 7.

(xem (8)). Nó theo sau
$$|f(z, s)| \geq |z^n| - nC |z^{n-1}|.$$

Chúng ta biểu thị $|z|$ bằng $r$, khi đó bất đẳng thức cuối cùng có dạng
$$|f(z, s)| \geq r^n - nCr^{n-1} = r^{n-1}(r - Cn).$$

Do đó, tại $r > Cn$ phần bên phải của bất đẳng thức trước là dương. Do đó, mô hình của hàm $f(z, s)$ không biến mất đối với bất kỳ giá trị nào của $S$ trừ khi $0 \leq s \leq 1$.

Bây giờ chúng ta hãy chú ý đến thực tế là tại $s = 0$ đa thức $f(z, s)$ biến thành đa thức $z^n$ mà chúng ta đã biết. Và chỉ số đường dẫn $z^n$, khi $z$ mô tả vòng tròn $r(\cos \alpha + i \sin \alpha)$, đã được chúng tôi tính toán (xem (5)). Nó bằng $n$. Tại $s = 1$ đa thức $f(z, s)$ biến thành đa thức $f(z)$ và đường đi (7) được xác định bởi nó có chỉ số cũng bằng $n$. Vì vậy, chúng ta đã chứng minh rằng chỉ số đường dẫn (7), được xác định bởi đa thức $f(z)$, tại $r > Cn$ bằng $n$. Từ đó, như đã nêu ở trên, suy ra rằng đa thức $f(z)$ biến mất ở một giá trị nào đó $z$, trong đó $|z| < Cn$.

Vậy định lý cơ bản của đại số đã được chứng minh.

Chia đa thức

Khi chia số nguyên dương $a$ cho số nguyên dương $b$ ta thu được đẳng thức
$$a = bh + k,$$
trong đó $h$ và $k$ là số nguyên không âm và $k < b$. Số $h$ gọi là thương, $k$ là số dư khi chia số $a$ cho số $b$.

Một phương pháp chia số là tốt từ số học. Nhưng cũng giống như số nguyên, các đa thức cũng có thể chia được cho nhau. Chúng ta sẽ bắt đầu từ hai đa thức
$$a(z) = a_0 z^p + a_1 z^{p-1} + \dots + a_p,$$
$$b(z) = b_0 z^q + b_1 z^{q-1} + \dots + b_q.$$

Ở đây chúng ta sẽ giả sử rằng các số $a_0$ và $b_0$ không bằng 0, do đó đa thức $a(z)$ có ​​bậc $p$ và đa thức $b(z)$ có bậc $q$. Bằng cách chia đa thức $a(z)$ cho đa thức $b(z)$, chúng ta có thể đạt được đẳng thức sau, tương tự như đẳng thức (9):
$$a(z) = b(z)h(z) + k(z),$$
(10)

trong đó bậc của đa thức $k(z)$ nhỏ hơn $q$. Đa thức $h(z)$ và $k(z)$ lần lượt được gọi là thương và số dư khi chia đa thức $a(z)$ cho đa thức $b(z)$.

Nếu $k(z) = 0$ thì đa thức $a(z)$ được cho là chia hết cho đa thức $b(z)$ và $h(z)$ là thương của phép chia của chúng.

Đẳng thức (9) được chứng minh bằng số học và đẳng thức (10) phải được chứng minh bằng đại số. Nhưng phép chia đa thức không được đưa vào chương trình giảng dạy ở trường hiện nay. Để chứng minh (10), chúng ta phải xây dựng các đa thức $h(z)$ và $k(z)$ thỏa mãn đẳng thức này. Quá trình xây dựng này là một thuật toán rất quan trọng. Hãy mô tả nó.

Nếu $p < q$ thì $h(z) = 0$, $k(z) = a(z)$ và đẳng thức (10) được thỏa mãn.

Bây giờ chúng ta sẽ xây dựng các đa thức $h(z)$ và $k(z)$ với giả định rằng $p \geq q$. Đầu tiên chúng ta xây dựng đẳng thức
$$a(z) = b(z)h_1(z) + a_1(z),$$
(11)
trong đó xây dựng đa thức $a_1(z)$ nhỏ hơn $p$. Để làm điều này, hãy đặt
$$h_1(z) = \frac{a_0}{b_0}z^{(p-q)}.$$

Thế thì sự khác biệt
$$a(z) - b(z)h_1(z) = a_1(z)$$
có bậc nhỏ hơn $p$, vì trong đa thức này hệ số $z^p$ bằng 0 và các bậc còn lại $z$ có ​​trong đa thức này rất nhỏ hơn $p$. Do đó, đẳng thức (11) được xây dựng.

⟦folio 8⟧

Nếu đa thức $a_1(z)$ có bậc nhỏ hơn $q$ thì đẳng thức (11) đã là đẳng thức (10). Trong trường hợp ngược lại, chúng ta áp dụng cho đa thức $a_1(z)$ quy trình tương tự đã được áp dụng cho đa thức $a(z)$ khi xây dựng đẳng thức (11). Và sau đó chúng ta có được sự bình đẳng cho nó

$$a_1(z) = b(z)h_2(z) + a_2(z),$$

và bậc của đa thức $a_2(z)$ đã nhỏ hơn bậc của đa thức $a_1(z)$. Nếu đa thức $a_2(z)$ đã có bậc nhỏ hơn $q$, thì thay $a_1(z)$ từ đẳng thức cuối cùng vào đẳng thức (11), chúng ta nhận được

$$a(z) = b(z)(h_1(z) + h_2(z)) + a_2(z),$$

đó đã là sự bình đẳng (10). Nếu đa thức $a_2(z)$ cũng có bậc lớn hơn $q$, thì chúng ta sẽ tiếp tục xây dựng thêm và cuối cùng chúng ta sẽ chứng minh được đẳng thức mong muốn (10).

Ở đây chúng ta đã mô tả quá trình chia đa thức $a(z)$ cho đa thức $b(z)$, tức là tìm các đa thức $h(z)$ và $k(z)$ có trong đẳng thức (10). Bây giờ chúng ta hãy chứng minh rằng chúng được xác định duy nhất bởi các đa thức $a(z)$ và $b(z)$. Giả sử rằng nếu chúng ta vi phạm đẳng thức (10), chúng ta có đẳng thức

$$a(z) = b(z)h_0(z) + k_0(z),$$

và bậc của đa thức $k_0(z)$ nhỏ hơn $q$. Trừ đẳng thức (12) khỏi đẳng thức (10), ta thu được

$$b(z)(h(z) - h_0(z)) = k_0(z) - k(z).$$

Vì bậc của đa thức $b(z)$ bằng $q$ và bậc của đa thức $k_0(z) - k(z)$ nhỏ hơn $q$ nên đẳng thức cuối cùng chỉ có thể đúng với điều kiện $h(z) - h_0(z) = 0$, sao cho $k(z) - k_0(z) = 0$.

Đa thức có hệ số phức tùy ý

Bây giờ, theo định lý cơ bản của đại số, nghiệm của đa thức $f(z)$ với hệ số phức sẽ được ký hiệu là $z_1$. Hãy chứng minh rằng đa thức $f(z)$ chia hết cho hai biến $(z - z_1)$. Bằng cách chia đa thức $f(z)$ cho đa thức bậc một $(z - z_1)$ theo các quy tắc được mô tả trong phần trước, chúng ta thu được thương số, được biểu thị bằng $f_1(z)$ và một phần còn lại ở dạng đa thức bậc 0, tức là một số mà chúng ta biểu thị bằng $k$. Như vậy chúng ta có

$$f(z) = f_1(z)(z - z_1) + k.$$

Vì $f(z_1) = 0$, sau đó thay $z = z_1$ vào đẳng thức trước đó, chúng ta thu được $k = 0$.

Vậy đa thức $f(z)$ được chia cho $(z - z_1)$ và ta có

$$f(z) = (z - z_1)f_1(z),$$

trong đó $f_1(z)$ là đa thức bậc $n-1$, hiển nhiên bắt đầu bằng số hạng $z^{n-1}$. Nếu $n > 1$ thì $n-1 > 0$; thì đa thức $f_1(z)$ sẽ có bậc dương và, theo những gì đã được chứng minh trước đó, có nghiệm $z_2$ nào đó. Như vậy, theo điều vừa chứng minh, đa thức $f_1(z)$ được chia thành đa thức

$$f_1(z) = (z - z_2)f_2(z).$$

(13)

Tiếp tục quá trình này hơn nữa, chúng ta thu được sự phân tách $f(z)$ thành $n$ đa thức tuyến tính

$$f(z) = (z - z_1)(z - z_2) \dots (z - z_n).$$

Các số $z_1, z_2, \dots, z_n$ là nghiệm của đa thức $f(z)$, và đa thức $f(z)$ rõ ràng không có nghiệm nào khác. Tuy nhiên, có thể cùng một gốc xuất hiện nhiều lần trong bản mở rộng này. Nhóm các nghiệm bằng nhau, ta thu được phân tích

$$f(z) = (z - z_1)^{k_1}(z - z_2)^{k_2} \dots (z - z_q)^{k_q},$$

trong đó tất cả các gốc $z_1, z_2, \dots, z_q$ đều khác biệt. Số $k_1$ được gọi là bội số của căn $z_1$, số $k_2$ là bội số của căn $z_2$, v.v., số $k_q$ là bội số của căn $z_q$. Do đó, số nghiệm khác nhau của đa thức $f(z)$ có thể nhỏ hơn $n$. Tuy nhiên, nếu chúng ta tính đến bội số của mỗi nghiệm thì tổng của các bội số chính xác là $n$. Theo nghĩa này, đa thức $f(z)$ có chính xác nghiệm $n$.

Đa thức có hệ số thực

Bây giờ chúng ta hãy xem xét trường hợp tất cả các hệ số của đa thức $f(z)$ đều là số thực. Về cội nguồn

⟦folio 9⟧

mà đa thức có thể biểu diễn một số thang đo thông điệp bổ sung thú vị.

Để xem xét một đa thức có hệ số thực, chúng tôi đưa ra khái niệm số $\bar{z}$, liên hợp phức của một số phức cho trước $z$. Chính xác nếu
$$z = x + iy,$$
thì theo định nghĩa, số
$$\bar{z} = x - iy$$
(14)

được gọi là liên hợp phức của $z$. Do đó, số $\bar{z}$, liên hợp phức với số $z$, là ảnh phản chiếu của số $z$ so với trục của số thực.

Nếu như
$$z = r(\cos \alpha + i \sin \alpha),$$
Cái đó
$$\bar{z} = r(\cos \alpha - i \sin \alpha) = r(\cos (-\alpha) + i \sin (-\alpha)).$$
(15)

Như vậy, các đối số của hai số liên hợp phức chỉ khác nhau về dấu. Từ công thức (14) suy ra rằng
$$\bar{z}_1 + \bar{z}_2 = \bar{z}_1 + \bar{z}_2.$$
Từ công thức (15) suy ra rằng
$$\bar{z}_1 \bar{z}_2 = \bar{z}_1 \cdot \bar{z}_2.$$
Cũng lưu ý rằng đẳng thức
$$\bar{z} = z$$
giữ khi và chỉ khi $z$ là số thực.

Từ ba công thức trước, dễ dàng thấy rằng đối với đa thức $f(z)$ có hệ số thực thì đẳng thức đúng
$$\bar{f}(\bar{z}) = f(\bar{z}).$$
Từ đẳng thức này, suy ra rằng nếu $z_1$ là nghiệm của đa thức $f(z)$ với các hệ số thực thì $\bar{z}_1$ cũng là nghiệm của nó. Nếu $z_1$ là số thực thì câu này vô nghĩa. Nếu $z_1$ không phải là số thực thì câu lệnh biểu thị sự tồn tại, cùng với nghiệm $z_1$, của một nghiệm khác $\bar{z}_1$. Do đó, nếu $z_1$ không phải là số thực thì đa thức $f_1(z)$ (xem (13)) có ước số $(z - \bar{z}_1)$ và ta thu được phân tích nhân tử

$$f(z) = (z - z_1)(z - \bar{z}_1)f_2(z).$$
Polyaga trong sự bình đẳng này
$$z_1 = x_1 + iy_1,$$
chúng tôi nhận được
$$f(z) = (z^2 - 2x_1z + x_1^2 + y_1^2)f_2(z).$$

Như vậy, chúng ta đã thấy rằng đa thức $f(z)$ có thừa số bậc hai thực sự $z^2 - 2x_1z + x_1^2 + y_1^2$. Theo đó, đa thức $f_2(z)$ cũng là đa thức có hệ số thực, vì nó thu được bằng cách chia đa thức $f(z)$ cho một tam thức bậc hai thực. Do đó, đa thức $f_2(z)$ này có nghiệm phức và lại liên hợp theo cặp. Nếu anh ta tìm thấy một nghiệm bằng với nghiệm đã tìm thấy $z_1$ thì anh ta cũng sẽ tìm thấy một nghiệm $\bar{z}_1$. Do đó, trong trường hợp này, một thừa số bậc hai được trích từ đa thức $f_2(z)$, bằng hệ số bậc hai trước đó. Từ đó, rõ ràng rằng bội số của nghiệm phức của đa thức $f(z)$ với các hệ số thực bằng bội số của nghiệm thức liên hợp và ta thu được phép phân tích đa thức $f(z)$ thành thừa số thực:

$$f(z) = (z^2 - 2x_1z + x_1^2 + y_1^2)^{k_1} \dots (z^2 - 2x_pz + x_p^2 + y_p^2)^{k_p} \times (z - z_{p+1})^{k_{p+1}} \dots (z - z_q)^{k_q}.$$

Lưu ý rằng các thừa số bậc hai có dạng
$$z^2 - 2x_i z + x_i^2 + y_i^2, \quad i = 1, 2, \dots, p,$$
trong đó tất cả $y_i$ đều không bằng 0, không thể phân tích thành thừa số thực được nữa.
