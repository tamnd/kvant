---
id: 1989-4-lvovskiy-proizvodnaya-slozhnoy-i-obratnoy-funktsiy-bc50f6af
issue: kvant_1989_4
year: 1989
number: "4"
title: Đạo hàm của hàm phức và hàm nghịch đảo
authors:
  - Львовский С. М.
rubric: shkola-v-kvante
page_first: 38
page_last: 41
page_labels: 36-39
tag: S5CM
lang: vi
source: kvant_digital
extraction: vision
content_sha256: cf20828ca864d6eb4f7f95192300f981ba30f1abcfd52a47522c32e761059c77
prompt_sha256: draft-1
translated_from: content/ru/1989/04/articles/08_lvovskiy-proizvodnaya-slozhnoy-i-obratnoy-funktsiy-bc50f6af.md
source_content_sha256: 683e308b6b5e98ca57d79a27edc3a55e854566679d83421f78aeea6cb1c2e7f9
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 36⟧

Toán 8, 9,10

Bài viết được xuất bản dành cho học sinh lớp chín và lớp mười.

Đạo hàm của hàm phức và hàm nghịch đảo

Từ sách giáo khoa ở trường, bạn biết hai cách giải thích đạo hàm của một hàm - hình học và cơ học *). Bạn biết rằng sự tồn tại đạo hàm của hàm số $f$ tại điểm $x$ tương đương với sự tồn tại của một tiếp tuyến không thẳng đứng tại điểm $(x; f(x))$

đồ thị của hàm số và hệ số góc của tiếp tuyến này bằng $f'(x)$. Ngoài ra, bạn biết rằng đạo hàm của tọa độ theo thời gian là tốc độ tức thời. Bây giờ chúng tôi sẽ giới thiệu cho bạn một cách giải thích khác về đạo hàm. Với sự trợ giúp của nó, chúng tôi sẽ minh họa các công thức đạo hàm của các hàm phức và hàm nghịch đảo.

Đạo hàm là hệ số co dãn

Hãy vẽ hai dòng số - xanh và đỏ. Trên một trong số chúng - màu xanh lam - chúng ta sẽ vẽ các giá trị của đối số và mặt khác - màu đỏ - các giá trị tương ứng của các hàm (trên cùng một tỷ lệ).

Hình 1 và 2 cho thấy điều gì xảy ra với các hàm $f(x)=3x+1$ và $g(x)=x^3$. Như có thể thấy từ hình 1, ​​​​hàm $f(x)=3x+1$ dịch đại diện-

*) Xem sách giáo khoa lớp 9-10 “Đại số và sự khởi đầu của phân tích” (M., Prosveshchenie, 1988, trang 22-24).

⟦folio 37⟧

mã [−1; 0] vào đoạn [−2; 1], đoạn [0; 1] - vào đoạn [1; 4], đoạn [1; 2] - vào đoạn [4; 7], v.v. Trong tất cả các trường hợp này, độ dài của đoạn tăng gấp 3 lần. Điều này không có gì đáng ngạc nhiên: xét cho cùng, đoạn [a; b] hàm của chúng tôi chuyển thành đoạn [3a+1; 3b+1].

Vì vậy, hàm $f(x)=3x+1$ thay đổi độ dài của tất cả các đoạn của đường thẳng thực theo cùng một cách: nó nhân với 3. (Nhận xét tương tự đúng với bất kỳ độ dài nào của hàm mới.)

Từ hình 2, rõ ràng hàm (phi tuyến tính) $g(x)=x^3$ kéo dài các đoạn nằm ở các vị trí khác nhau trên trục số theo các cách khác nhau: ví dụ: đoạn [0,8; 0,9] - 2,2 lần và đoạn [1,1; 1,2] - 4 lần. Do đó, sẽ không có ý nghĩa gì khi hỏi $g$ kéo dài các đoạn nằm trên trục số $b\ell n\zeta$ của một điểm cho trước bao nhiêu lần. Ví dụ: tại các điểm đóng $x=1$. Hãy bắt đầu với các đoạn có độ dài 0,1: đoạn [0,9; 1] tăng 2,7 lần và đoạn [1; 1,1] - 3,3 lần. Hãy lấy các đoạn ngắn - [0,99; 1] và [1; 1,01]. Chúng ta có: $0,99^3\approx 0,97,1,01^3\approx 1,03$ (chúng ta để lại hai chữ số thập phân). Do đó, đoạn [1; 1,01] kéo dài $\frac{1,01^3-1^3}{1,01-1}\approx 3$ lần; tương tự, đoạn [0,99; 1] kéo dài $\frac{1^3-0,99^3}{1-0,99}\approx 3$ lần. Nếu chúng ta lấy các đoạn thậm chí còn ngắn hơn chứa điểm 1, hệ số giãn sẽ thậm chí gần hơn với 3. Vì vậy, hàm $g(x)=x^3$ mở rộng:

$$\frac{1,01^3-1^3}{1,01-1}=3$$

Gris. 2.

Phân đoạn Grisens gần điểm 1 khoảng 3 lần. Đoạn càng gần điểm $x=1$ thì hệ số giãn tại điểm $x=1$ càng gần bằng 3.

Bây giờ hãy lưu ý rằng đối với bất kỳ hàm (vi phân) nào $f$, hệ số giãn nở của các đoạn nhỏ gần điểm $x$ không gì khác hơn là đạo hàm $f$ tại điểm $x$. Trên thực tế, nếu điểm $x_1$ gần với $x$ thì đoạn $[x; x_1]$ sẽ đi vào đoạn $[f(x); f(x_1)]$ và hệ số giãn nở của nó là $\frac{f(x_1)-f(x)}{x_1-x}$ và đây chính là biểu thức được sử dụng để xác định hàm tùy ý tại điểm $x$ (số thay thế là số gia của đối số, tử số là số gia của hàm). Khi $x_1$ có xu hướng $x$ (đoạn rút ngắn), tỷ lệ này có xu hướng $f'(x)$.

Hãy kiểm tra lựa chọn của chúng ta cho hàm $g(x)=x^3$. Như bạn đã biết, $g'(x)=3x^2$, vậy $g'(1)=3$; điều này trùng khớp với hệ số giãn mà chúng tôi đã tìm thấy gần đúng.

Trong các ví dụ của chúng tôi, hệ số giãn nở, tức là đạo hàm, lớn hơn đơn vị; nếu hệ số kéo dài nhỏ hơn một nhưng dương, thì các đoạn gần một điểm nhất định không bị kéo căng mà bị nén (độ dài của chúng được nhân với một số nhỏ hơn 1); nếu $f'(x)<0$, thì các đoạn được “lật”: đầu bên trái của đoạn [a; b] đi đến đầu bên phải của đoạn $[f(b); f(a)]$. Điều này không có gì đáng ngạc nhiên: khi đạo hàm âm, hàm số sẽ loại bỏ, vì vậy từ $a<b$ nó sẽ theo sau $f(b)<f(a)$.

⟦folio 38⟧

Vì vậy, lựa chọn chính của điểm này: các đoạn nhỏ gần điểm $x$ được kéo dài bởi hàm $f$ với hệ số gần $f'(x)$. Đoạn càng gần điểm $x$ thì hệ số càng gần $f'(x)$. Trong suốt phần tiếp theo, để ngắn gọn, chúng tôi sẽ bỏ qua những giải thích này và viết các cụm từ như “hàm $f(x)=x^3$ kéo dài các đoạn gần với điểm 1 theo hệ số 3”. Chúng tôi hy vọng điều này không làm phiền bạn.

Thành phần hàm (hàm phức tạp)

Hãy lấy hàm $f(x)=\sqrt{x^3}+1$. Phải lấy điểm $x$ đến điểm $\sqrt{x^3}+1$. Việc dịch này có thể được thực hiện theo hai giai đoạn: đầu tiên, chuyển điểm $x$ sang điểm $t=x^3+1$, sau đó chuyển điểm $t$ sang điểm $\sqrt{t}$. Hãy xem xét các hàm $g(x)=x^3+1$ và $h(t)=\sqrt{t}$. Sau đó hóa ra là $f(x)=h(g(x))$. Đôi khi nó được viết như thế này: $f=h\circ g$ và họ nói rằng $f$ là sự kết hợp của các hàm $h$ và $g$. Về ký hiệu $f(x)=h(g(x))$ họ cũng nói rằng $f$ được viết dưới dạng hàm phức.

Nếu chúng ta sử dụng biểu diễn sơ đồ của các hàm, chúng ta sẽ nhận được những gì được hiển thị trong hình 3. (Như trước đây, các giá trị $x$ nằm trên trục màu xanh lam, các giá trị $f(x)$ nằm trên trục màu đỏ.)

Cách tính hàm phức tùy ý

Chúng ta hãy xem xét hàm số tương tự $f(x)=\sqrt{x^3}+1$ và tìm hàm số tùy ý của nó tại điểm $x=2$. Chúng ta đã biết rằng tùy ý tại điểm $x=2$ là hệ số giãn của các đoạn gần với điểm 2 khi di chuyển từ trục xanh sang trục đỏ (hình 3). Trên đường từ trục màu xanh lam đến trục màu đỏ, đoạn này kết thúc trên trục màu xanh lá cây, trong đó chiều dài của nó được nhân với $g'(2)=12$; khi di chuyển từ trục màu xanh lá cây sang trục màu đỏ, độ dài của đoạn kết quả lần lượt được nhân với $h'(g(2))=h'(9)=\frac{1}{6}$; tổng cộng, do đó,

⟦folio 39⟧

độ dài của đoạn sẽ được nhân với $12 \cdot \frac{1}{6} = 2$, sao cho $f'(2) = 2$.

Lặp lại lý luận tương tự cho bất kỳ điểm $x$ nào, chúng ta thu được quy tắc sau:

$$\text{если } f(x) = h(g(x)), \\
\text{то } f'(x) = g'(x) \cdot h'(g(x)).$$

Tất nhiên, điều này đúng với mọi hàm $h$ và $g$.

Trong trường hợp của chúng tôi, khi $h(t) = \sqrt{t}, g(x) = x^3 + 1, f(x) = \sqrt{x^3 + 1}$, chúng tôi nhận được

$$f'(x) = 3x^2 \cdot \frac{1}{2\sqrt{x^3 + 1}}.$$

Vì vậy, chúng ta đã thu được công thức mà bạn đã biết từ sách giáo khoa cho hàm phức tùy ý. Chúng ta có thể viết một công thức tương tự cho trường hợp $f$ phức tạp không phải của hai mà của ba, bốn, v.v.

Hàm nghịch đảo

Trên hình 4, hàm $f(x) = x^3 + 1$ được mô tả theo cách đã được cung cấp cho chúng tôi. Mũi tên liền trên hình này cho biết cách chuyển các điểm $x$ trên trục của nó thành các điểm $y = x^3 + 1$ trên trục màu đỏ. Bây giờ, hãy tưởng tượng rằng hình 4 đặt ra một định luật, theo đó, ngược lại, các điểm từ trục màu đỏ được chuyển sang trục màu xanh (mũi tên đi lên hình)—điểm $y = x^3 + 1$ được chuyển sang điểm $x$. Chúng ta có thể biểu thị $x$ đến $y$ bằng công thức $x = \sqrt[3]{y - 1}$. Kết quả là một mô tả về chức năng mới. Hãy biểu thị nó bằng chữ cái $g$: $g(y) = \sqrt[3]{y - 1}$. Hàm $g(y) = \sqrt[3]{y - 1}$ được gọi là hàm nghịch đảo của hàm $f(x) = x^3 + 1$. Lưu ý rằng trong công thức xác định hàm $g$ (nói chung trong bất kỳ công thức xác định hàm nào), biến độc lập $y$ có thể được biểu thị bằng bất kỳ chữ cái nào. Ví dụ: bạn có thể viết $g(t) = \sqrt[3]{t - 1}$ hoặc thậm chí $g(x) = \sqrt[3]{x - 1}$.

Cũng lưu ý rằng không phải mọi chức năng đều có nghịch đảo. Ví dụ: hãy lấy hàm $f(x) = x^2$. Hàm này lấy cả điểm 2 và điểm (-2) về điểm 4. Nếu $g$ là nghịch đảo
