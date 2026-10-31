---
id: 1972-9-vahovskiy-volyinskiy-nauchimsya-obraschatsya-s-absolyutnoy-velichinoy-1d52a223
issue: kvant_1972_9
year: 1972
number: "9"
title: Hãy học cách xử lý giá trị tuyệt đối
authors:
  - Ваховский Е. Б.
  - Волынский А. Б.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 47
page_last: 50
page_labels: 45-48
tag: 47WC
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 53095c14f425fb1fae2c562df877a1965e557e8323a0d69107452bb74f7fc04d
prompt_sha256: draft-1
translated_from: content/ru/1972/09/articles/12_vahovskiy-volyinskiy-nauchimsya-obraschatsya-s-absolyutnoy-velichinoy-1d52a223.md
source_content_sha256: 26405ab24cee8dc14681c254465a6ebfb9f26d7c217876d1dff8d982dd08e7ea
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 45⟧

HÃY HỌC XỬ LÝ SỐ LƯỢNG TUYỆT ĐỐI

E.B.Vakhovsky, A.B.Volynsky

Có một kỳ thi đang diễn ra. Người nộp đơn được cung cấp một phương trình lượng giác:

$$\sqrt{\cos^2 x - \cos 2x} - 1 = \sin x.$$

Trong quá trình lời giải, người nộp đơn viết ra phương trình sau:

$$\sqrt{\cos^2 x - \cos^2 x + \sin^2 x} - 1 = \sin x,$$

$$\sin x - 1 = \sin x, -1 = 0.$$

Người nộp đơn nói rằng kết quả bằng số sai có nghĩa là phương trình này không có lời giải.

Đáp số là không chính xác. Điều này có thể được xác minh dễ dàng bằng cách thay số $x = -\frac{\pi}{6}$ vào phương trình ban đầu, kết quả là nghiệm.

Nhân tiện, một sai lầm rất phổ biến của người nộp đơn là không phải mọi hành vi có thể bị kiện $a$

$$\sqrt{a^2} = a$$

(1)

(đặc biệt trong ví dụ này, người nộp đơn tin rằng $\sqrt{\sin^2 x} = \sin x$).

Trên thực tế, sự thật duy nhất là như nhau

$$\sqrt{a^2} = |a|,$$

(2)

trong khi đẳng thức (1) chỉ có giá trị với $a \ge 0$ (xem E. S. Kochetkov, E. S. Kochetkov “Đại số và các hàm cơ bản”, § 77).

Vì vậy, bằng cách giải phương trình trên, người nộp đơn sẽ nhận được

$$|\sin x| - 1 = \sin x.$$

Nếu $\sin x \ge 0$, thì phương trình cuối cùng sẽ được viết như sau: $\sin x - 1 = \sin x$, do đó $-1 = 0$, và trong trường hợp này không có lời giải.

Nếu $\sin x < 0$ thì $|\sin x| = -\sin x$ và chúng ta nhận được $-\sin x - 1 = \sin x$, từ đó $\sin x = -\frac{1}{2}$, phù hợp với các điều kiện $\sin x < 0$.

Đáp số: $x = (-1)^{n+1} \frac{\pi}{6} + \pi n$ ở đâu $n=0, \pm 1, \pm 2, \dots$.

Bây giờ chúng ta hãy xem xét kỹ hơn về khái niệm giá trị tuyệt đối.

Trước hết, chúng tôi lưu ý rằng các đồ thị của mô hình số $x$ là một khoảng cách đơn giản từ điểm $x$ của trục số đến đầu báo cáo (xem Hình 1).

Thông điệp trên đơn giản hóa lời giải một loại bất đẳng thức lớn.

Ví dụ 1. Giải bất phương trình

$$|x| < a \quad (a > 0),$$

(3)

$$|x| > a \quad (a > 0).$$

(4)

Lời giải. Bất đẳng thức (3) chỉ được thỏa mãn bởi những điểm trên trục số, khoảng cách từ đó đến đầu báo cáo nhỏ hơn $a$, tức là các điểm nằm giữa $-a$ và $a$ (Hình 2).

Đáp số: $-a < x < a$. Điều này có nghĩa là $x$ thỏa mãn hệ thống

⟦folio 46⟧

sự bất bình đẳng

$$\begin{cases} x > -a, \\ x < a. \end{cases}$$

Vì những lý do tương tự, nghiệm của bất đẳng thức (4) là các giá trị của $x$ thỏa mãn sự kết hợp của hai bất đẳng thức: $x < -a; x > a$ (Hình 3).

Cần lưu ý rằng với $a \leq 0$ bất đẳng thức (3) không có lời giải. Bất đẳng thức (4) với $a < 0$ được thỏa mãn bởi tất cả các số thực và với $a = 0$ - bởi tất cả trừ $x = 0$.

Vì vậy, trong các ví dụ thuộc loại này, trước hết chúng ta phải quan tâm đến dấu của vế phải. Vì vậy, ví dụ, bất đẳng thức $|x| < |a|$ thường được giải tự động bằng cách phân tích trường hợp $a \geq 0$ và $a < 0$, giả sử rằng điều này là cần thiết vì số $a$ nằm dưới dấu mô đun. Tuy nhiên, điều dễ nhận thấy nhất ở đây là $|a| > 0$ tại $a \neq 0$. Từ đây chúng ta dễ dàng nhận được đáp số: nếu $a \neq 0$ thì $|a| < x < |a|$, nếu $a = 0$ thì lời giải thì không.

Đối với các bất đẳng thức loại (3) và (4) có một số bất đẳng thức không chứa dấu giá trị tuyệt đối.

Ví dụ 2. Giải bất đẳng thức $4 < x^2 < 9$.

Lời giải. Chúng ta hãy trích căn bậc hai của cả ba phần của bất đẳng thức (số học). Bất đẳng thức tương đương thu được $2 < |x| < 3$ có thể được giải dễ dàng bằng cách biểu diễn đồ họa (Hình 4).

Đáp số: $-3 < x < -2; 2 < x < 3$.

Ví dụ 3 (MSU, mek. mat., 1966). Giải bất đẳng thức

$$|3^{tg\pi x} - 3^{1-tg\pi x}| \geq 2.$$

Lời giải. Bất đẳng thức này tương đương với sự kết hợp của hai bất đẳng thức: $3^{tg\pi x} - 3^{1-tg\pi x} \leq -2; 3^{tg\pi x} - 3^{1-tg\pi x} \geq 2$.

Ký hiệu $3^{tg\pi x}$ bằng $y$, ta thu được tập bất đẳng thức:

$$y - \frac{3}{y} \leq -2; y - \frac{3}{y} \geq 2 (y > 0).$$

⟦folio 47⟧

Lời giải. Trước hết, chúng ta cần loại bỏ các dấu của độ lớn tuyệt đối. Tuy nhiên, để làm được điều này, bạn cần biết các số $1 - x$ và $x^2 - x - 6$ dưới dấu mô đun có dấu gì. Nhưng con số $x$ là gì thì không ai biết trước nên cần phải phân tích một số trường hợp. Để thực hiện điều này một cách tiết kiệm nhất, chúng ta phân tích tam thức $x^2 - x - 6$ và biểu diễn bất đẳng thức này dưới dạng

$$\frac{6x - |x+2| |x-3|}{|x-1|} \leq 3 + 5x.$$

Vì luôn tồn tại $|x-1| \geq 0$ nên bất đẳng thức này tương đương với hệ

$$\begin{cases} 6x - |x+2| |x-3| \leq \\ \leq (3+5x) |x-1|, \\ x \neq 1. \end{cases}$$

Để giải hệ (5), vẽ các điểm $-2, 1$ và $3$ trên trục số (Hình 5), sẽ chia nó thành các vùng chẵn. Đối với số $x$, từ mỗi khu vực như vậy, có thể thấy rõ các số $x+2, x-1, x-3$ có dấu gì.

Ví dụ: nếu điểm $x$ nằm ở vùng ngoài cùng bên trái $(x < -2)$ thì $|x+2| = -(x+2), |x-1| = 1 - x, |x-3| = 3 - x$. Do đó, bất đẳng thức của chúng tôi tương đương với sự kết hợp của bốn hệ thống:

$$\begin{cases} x < -2, \\ 6x - (x+2)(x-3) \leq (3+5x)(1-x); \\ -2 \leq x < 1, \\ 6x + (x+2)(x-3) \leq (3+5x)(1-x); \\ 1 < x \leq 3, \\ 6x + (x+2)(x-3) \leq (3+5x)(x-1); \\ x > 3; \\ 6x - (x+2)(x-3) \leq (3+5x)(x-1). \end{cases}$$

Hệ thống đầu tiên không có lời giải. Lời giải phần còn lại của hệ thống:

$$-\frac{3}{2} \leq x < 1, \quad 1 < x \leq 3, \quad x > 3$$

tương ứng. Cuối cùng đáp số: $$-\frac{3}{2} \leq x < 1, \quad x > 1.$$

Hãy chuyển sang loại tiếp theo bài toán được liên kết với giá trị tuyệt đối.

Xét bất đẳng thức có dạng $|A| \leq B$, trong đó $A$ và $B$ là một số biểu thức chứa ẩn số $x$.

Do các thông điệp mà chúng ta đã đưa ra trong Ví dụ 1, bất đẳng thức này tương đương với hệ

$$\begin{cases} B \geq 0, \\ -B \leq A \leq B, \end{cases}$$

hoặc toàn bộ hệ thống:

$$\begin{cases} A \geq 0, \\ A \leq B; \quad A < 0, \\ -A \leq B. \end{cases}$$

Tương tự như vậy, bất đẳng thức $|A| \geq B$ tương đương với tổng của hệ

$$\begin{cases} B < 0, \\ A - \text{любое}; \quad B \geq 0, \\ A \leq -B, \quad A \geq B, \end{cases}$$

hoặc toàn bộ hệ thống

$$\begin{cases} A \geq 0, \\ A \geq B; \quad A < 0, \\ -A \geq B. \end{cases}$$

Trong mỗi ví dụ cụ thể của loại này, người ta phải xác định đường dẫn hữu ích nhất.

Ví dụ 5. Giải bất đẳng thức

$$5 + 2 \cos 2x \leq 3 \quad |2 \sin x - 1|.$$

Lời giải. Phương pháp đầu tiên được hướng dẫn ở đây, vì $5 + 2 \cos 2x > 0$ dành cho tất cả $x$. Bất đẳng thức được đề xuất tương đương với một tập hợp các bất đẳng thức:

$$3 (2 \sin x - 1) \leq -5 - 2 \cos 2x; \quad 3 (2 \sin x - 1) \geq 5 + 2 \cos 2x.$$

Mỗi bất đẳng thức này, sau khi thay thế $\cos 2x = 1 - 2 \sin^2 x$, sẽ trở thành bình phương đối với sin $x$. Giải chúng có tính đến bất đẳng thức $|\sin x| \leq 1$, ta thu được tập hợp

$$\sin x \leq -\frac{1}{2}, \quad \sin x \geq 1.$$

⟦folio 48⟧

Đáp số: $2\pi n - \frac{5}{6} \pi \leqslant x \leqslant -\frac{\pi}{6} + 2\pi n, \quad x = \frac{\pi}{2} + 2\pi k, \quad \text{где } n, \quad k = 0, \quad \pm 1, \dots$

Ví dụ 6. Giải bất đẳng thức $|x^3 - 8| \leqslant x^3 + x + 8$.

Lời giải. Ở đây, phương pháp đầu tiên đơn giản là không thể áp dụng được vì chúng ta không có cơ hội giải bất đẳng thức $x^3 + x + 8 \geqslant 0$. Phương pháp thứ hai giảm bài toán xuống toàn bộ hệ thống

$$\begin{cases} x^3 - 8 \geqslant 0, \\ x^3 + x + 8 \geqslant x^3 - 8; \\ x^3 - 8 < 0, \\ x^3 + x + 8 \geqslant -x^3 + 8, \end{cases}$$

từ đó dẫn đến tổng thể của hệ thống

$$\begin{cases} x \geqslant 2, \\ x \geqslant -16; \end{cases}$$

$$\begin{cases} x < 2, \\ x(2x^2 + 1) \geqslant 0. \end{cases}$$

Lời giải thứ nhất: $x \geqslant 2$, lời giải thứ hai: $0 \leqslant x < 2$.

Đáp số: $x \geqslant 0$.

Dễ dàng kiểm tra được rằng phương trình $|A| = B$ cũng có thể được giải theo hai cách; nó tương đương với hệ thống

$$\begin{cases} B \geqslant 0, \\ \pm B = A, \end{cases}$$

hoặc

$$\begin{cases} A \geqslant 0; \\ A = B; \end{cases}$$

$$\begin{cases} A < 0, \\ -A = B. \end{cases}$$

Ví dụ 7 (MAI, 1970). Giải phương trình:

$$x - \frac{|3x - 2|}{5} = 3 - \frac{2x - 5}{3}$$.

Lời giải. Sau khi biến đổi đơn giản, chúng ta nhận được

$$3 |3x - 2| = 25x - 70$$.

Hãy sử dụng phương pháp đầu tiên. Sau khi phương trình tương đương với tổng thể của hệ

$$\begin{cases} 25x - 70 \geqslant 0, \\ 3(3x - 2) = 25x - 70; \\ 25x - 70 \geqslant 0, \\ 3(3x - 2) = -25x + 70. \end{cases}$$

Lời giải hệ thống đầu tiên $x = 4$; hệ thống thứ hai không tương thích.

Đáp số: $x = 4$.

Ví dụ 8 (MSU, Khoa Vật lý, 1963). Cụ thể là phương trình deistrimel lời giải

$$\begin{cases} x^2 - \frac{3}{2}x - 1 = -x^2 - 4x + \beta. \end{cases}$$

Lời giải. Trong trường hợp này, phương pháp đầu tiên, bao gồm cả dấu của vế phải, là bất tiện, vì tham số $\beta$ sẽ không chỉ xuất hiện trong phương trình mà còn xuất hiện trong bất đẳng thức tương ứng. Hãy sử dụng phương pháp thứ hai.

Phương trình được đề xuất tương đương với tập hệ thống sau:

$$\begin{cases} x^2 - \frac{3}{2}x - 1 \geqslant 0, \\ x^2 - \frac{3}{2}x - 1 = -x^2 - 4x + \beta; \end{cases}$$

$$\begin{cases} x^2 - \frac{3}{2}x - 1 < 0, \\ -(x^2 - \frac{3}{2}x - 1) = -x^2 - 4x + \beta. \end{cases}$$

Hệ thống đầu tiên được rút gọn thành hệ thống

$$\begin{cases} x \leqslant -\frac{1}{2}, x \geqslant 2, \\ x_1 = \frac{-5 - \sqrt{57 + 32\beta}}{8}, \\ x_2 = \frac{-5 + \sqrt{57 + 32\beta}}{8}. \end{cases}$$

Vì $x_1 < 0$ nên ta phải thỏa mãn các bất đẳng thức $x_1 \leqslant -\frac{1}{2}, x_2 \leqslant -\frac{1}{2}, x_2 \geqslant 2$.

Thay thế các biểu thức của chúng cho $x_1$ và $x_2$ và giải các bất đẳng thức vô tỷ đối với $\beta$, chúng ta thu được
