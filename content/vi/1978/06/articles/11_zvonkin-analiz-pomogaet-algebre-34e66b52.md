---
id: 1978-6-zvonkin-analiz-pomogaet-algebre-34e66b52
issue: kvant_1978_6
year: 1978
number: "6"
title: Phân tích giúp đại số
authors:
  - Звонкин А. К.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 55
page_last: 58
page_labels: 53-56
tag: NXFC
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 681a7dda470d318ac804dee6d5bd49860db9fde642f28d0b640891362fe2a9de
prompt_sha256: draft-1
translated_from: content/ru/1978/06/articles/11_zvonkin-analiz-pomogaet-algebre-34e66b52.md
source_content_sha256: cb176d117bce53ee9468b96ec8f079ae0dad68434fa22c224ff37f73964e7a47
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 53⟧

A. Zvonkin

phân tích
giúp đại số

Thông thường, đại số bài toán có thể được giải bằng cách tìm và nghiên cứu một số hàm phụ phù hợp bằng phương pháp phân tích. Chúng ta sẽ làm quen với bài toán này trong bài học câu lạc bộ toán học này.

Ví dụ 1. Phương trình có bao nhiêu nghiệm?
$$x^3 - 3x = a^2$$ (1)

Lời giải. Như đã biết, có một công thức cho phương trình lời giải Kubne («Kvant», 1976, số 9). Tuy nhiên, công thức này rất cồng kềnh. Có thể tìm ra số nghiệm của một phương trình mà không cần giải nó không?

Sử dụng một biểu đồ tùy ý, chúng ta vẽ đồ thị của hàm $y = x^3 - 3x$ (Hình 1a). Trong cùng một bản vẽ, chúng ta sẽ vẽ đồ thị của hàm $y = a$, tức là một đường thẳng nằm ngang (Hình 16 hiển thị một số đường thẳng như vậy cùng một lúc - cho các giá trị khác nhau của $a$). Số nghiệm của phương trình (1) chỉ đơn giản là số giao điểm của đồ thị và đường thẳng*). ngay lập tức

*) Việc đường thẳng thực sự cắt đồ thị như trên hình vẽ được rút ra từ đoạn 84 SGK “Đại số và sự khởi đầu của phép phân tích 10”. Thật vậy, hàm $x \rightarrow x^3 - 3x$ liên tục và đơn điệu trên mỗi khoảng $] -\infty, -1]$, $[-1, 1]$, $[1, +\infty]$; do đó, tập hợp các giá trị của nó trên mỗi khoảng này là một khoảng; do đó, ví dụ, với bất kỳ $a \in [-2; 2]$ nào cũng có một $x_0 \in [-1; 1]$ sao cho $f(x_0) = a$, và do tính đơn điệu của hàm $f$ trên khoảng $[-1; 1]$, nên $x_0$ đó là duy nhất. Trong các ví dụ sau, người đọc có thể dễ dàng tự mình xác minh lý do này.

Hình 1.

⟦folio 54⟧

Hình 2.

Hình 3.

không ít hơn cùng với $a^x$ chúng ta thay thế $x$, chúng ta nhận được $x = \frac{1}{\ln a}$. Chúng ta thay giá trị kết quả $x$ vào phương trình đầu tiên:
$$a^{\frac{1}{\ln a}} = \frac{1}{\ln a};$$
logarit và biến đổi:
$$\frac{1}{\ln a} \cdot \ln a = \ln \left( \frac{1}{\ln a} \right) \Leftrightarrow 1 = -\ln (\ln a) \Leftrightarrow \ln a = \frac{1}{e} \Leftrightarrow a = e^{\frac{1}{e}}.$$
Vì vậy, $a_0 = e^{\frac{1}{e}}$.

Bài toán 3. Phương trình có bao nhiêu nghiệm?
$$a^x = \log_a x?$$
Gợi ý $*$). Hình 3 cho thấy
*) Xem thêm bài viết của A. Egorov tại «Kvant»
Số 10 năm 1977, tr. 37.

vợ năm trường hợp sắp xếp lẫn nhau các đồ thị $y = a^x$ và $y = \log_a x$. Để thuận tiện, đường thẳng $y = x$ cũng được hiển thị bằng đường chấm. Các hàm $a^x$ và $\log_a x$ có thể tưởng tượng được nên đồ thị của chúng đối xứng qua đường thẳng này. Tất cả những gì bạn phải làm là tìm các giá trị của $a_1$ và $a_2$.

Nhân tiện, xin lưu ý rằng Hình 3 được hiển thị trên bìa sách giáo khoa Đại số 8 (tại $a = 10$). Chúng tôi thấy trường hợp trong Hình 3d đặc biệt thú vị. Ví dụ, bức ảnh này thu được ở $a = \frac{1}{16}$.

Tăng cường. Đối với $a = \frac{1}{16}$, tìm tọa độ của các điểm giao nhau.

Ví dụ 3. Với những giá trị nào của $a$ thì có $b$ dương sao cho phương trình
$$x^2 + a = 2b \cdot \ln x$$
có một gốc duy nhất?

⟦folio 55⟧

Lời giải. Như mọi khi, hãy bắt đầu với hình ảnh. Hình 4 cho thấy ba trường hợp về vị trí tương đối của đồ thị $y=x^2+a$ và $y=2b\cdot \ln x$ (đối với $b>0$). Rõ ràng là phương trình (3) có một nghiệm duy nhất khi và chỉ khi các đồ thị này chạm nhau (Hình 46). Tại điểm tiếp tuyến, không chỉ các giá trị của các hàm đồng thời $f(x)=x^2+a$ và $g(x)=2b\cdot \ln x$ mà cả các giá trị của các hàm tùy ý $f'(x)=2x$ và $g'(x)=\frac{2b}{x}$ của chúng đều trùng khớp. Hệ thống kết quả:

$$\begin{cases} x^2+a=2b\cdot \ln x \\ 2x=\frac{2b}{x} \end{cases}$$

Từ phương trình thứ hai của hệ thống này, chúng ta tìm thấy $x=\pm \sqrt{b}$ (nhớ lại điều đó theo giả định $b>0$). Giá trị $x=-\sqrt{b}$ không thỏa mãn hệ thống, vì $\ln x$ không xác định tại $x=-\sqrt{b}$. Thay giá trị kết quả $x$ vào phương trình đầu tiên, chúng ta nhận được $a=b\cdot \ln b-b$. (4)

Do đó, đồ thị $y=x^2+a$ và $y=2b\cdot \ln x$ tiếp tuyến khi và chỉ khi điều kiện (4) được thỏa mãn; trong trường hợp này, sự tiếp tuyến xảy ra tại điểm với trục hoành $x=\sqrt{b}$.

Bài toán bắt đầu làm rõ câu hỏi sau: với những giá trị nào của $a$ thì cực đại $b$ tồn tại sao cho đẳng thức $a=b\cdot \ln b-b$ đúng? Một công thức tương đương khác: tìm tập giá trị của hàm $f(b)=b\cdot \ln b-b$.

Câu hỏi bảo mật: Tại sao chúng tôi lại bỏ qua yêu cầu về số dương $b$?

Trên mặt phẳng tọa độ $Oba$ chúng ta sẽ vi phạm đồ thị của hàm $b \rightarrow b\cdot \ln b-b$ (Hình 5). Bây giờ đáp số đối với câu hỏi được đặt ra là “gần như rõ ràng”: giá trị bắt buộc $b$ tồn tại ở $a\geq a_0$ (có thể có hai giá trị!). Giá trị của $a_0$ được tìm thấy trong phương trình $f'(b)=0$. Bởi vì $f'(b)=\ln b$, $b_0=1$.

Vì vậy, $a_0=f(b_0)=-1$.

Câu hỏi bảo mật. Như có thể thấy trong Hình 5, nếu $a$ thuộc khoảng $[-1, 0]$, thì nó tương ứng với hai giá trị $b$. Điều này có ý nghĩa gì đối với đồ thị $y=x^2+a$ và $y=2b\cdot \ln x$? Vẽ tranh.

Đôi khi giá trị của số nghiệm đưa ra nghiệm của phương trình. Ví dụ, nếu biết rằng một phương trình nào đó có đúng một

⟦folio 56⟧

root, bạn chỉ cần thử đoán xem.

Kỹ thuật 4. Giải phương trình
$$\cos x = 1 - \frac{x^2}{2}.$$

Lời giải e. Một trong những gốc của phương trình này rất dễ đoán: $x = 0$. Có còn rễ không? Hãy nhìn vào biểu đồ (Hình 6). Điểm gần $x = 0$, đồ thị của hàm số $y = \cos x$ và $y = 1 - \frac{x^2}{2}$ giống nhau đến mức nếu không nghiên cứu thêm thì không thể xác định được hình nào trong số ba hay 66 là đúng. Hãy thử chứng minh rằng với mọi $x \neq 0$ phương trình $\cos x > 1 - \frac{x^2}{2}$ là đúng (nghĩa là không thể có sự bằng nhau).

Hãy để $f(x) = \cos x - 1 + \frac{x^2}{2}$.

Hàm này chẵn, (tức là $f(x) = f(-x)$), vì vậy chỉ xem xét các giá trị dương của $x$. Vì $f(0) = 0$, để chứng minh phương trình $f(x) > 0$ cho $x > 0$, chỉ cần thiết lập rằng $f$ được trả về cho $x = 0$ là đủ, chỉ cần thiết lập rằng $f'(x) > 0$ cho $x > 0$ (“Đại số và Nguyên tắc Phân tích 9”, đoạn 54 là đủ). Vì $f'(x) = x - \sin x$, nên phương trình $f'(x) > 0$ tương đương với phương trình $\sin x < x$, mà tại $x > 0$ là rất indo*).

Ví dụ cuối cùng chúng ta sẽ xem xét liên quan đến việc khái quát hóa phương trình giữa trung bình hình học và trung bình tranh luận. Dễ dàng chứng minh rằng với $x > 0$, $y > 0$ $\sqrt{x y} \leq \frac{x + y}{2}$ đúng và phương trình đạt được khi và chỉ khi $x = y$. Hãy viết phương trình này dưới dạng này:
$$\frac{1}{2} \cdot \frac{1}{2} \leq \frac{1}{2} x + \frac{1}{2} y.$$

Chúng ta hãy thực hiện khái quát hóa sau:

Kỹ thuật 5. Đặt các số dương $a$ và $b$ là số tối đa sao cho $a + b = 1$. Chứng minh rằng với mọi $x > 0$,

$$y > 0 \quad \text{справедливо уравнение}$$
$$x^a y^b \leq ax + by,$$
(5)

trong đó phương trình đạt được khi và chỉ khi $t = 1$. Chúng tôi để lại chứng minh này như một bài tập cho người đọc. (Được biểu thị. Hàm $at - t^a + 1 - a$ tại $t = 1$ có ​​mức tối thiểu).

Nhiệm vụ và

4. Phương trình có bao nhiêu nghiệm?
a) $e^x = ax$?
b) $3x^4 + 4x^3 - 36x^2 = a$?
b) $\frac{x}{\ln x} = a$?

5. Giải (một phương trình có hai ẩn số):

a) $\frac{1}{x} + 2\sqrt{x} = 3y (1 - \ln y)$;
b) $\frac{\ln x}{x} = e^{\cos y}$;
b) $4^x + 1 = 2^{x+1} \sin y$.
6. Vẽ trên mặt phẳng $(p, q)$ tập hợp các giá trị $(p, q)$ mà các phương trình
a) $x^3 = 3p^2x + q$;
b) $p^x = x^q (x > 0)$ có 0, 1, 2, ... lời giải tương ứng với $x$.
7. Giải phương trình
a) $\ln x = x - 1$
b) $(x - 1)e^x + x^2 - 3x + 2 = 0$
b) $\sin x = x - \frac{1}{6}x^3$.

8. Xác định (không cần bảng) số nào lớn hơn $e^\pi$ hoặc $\pi^e$.
