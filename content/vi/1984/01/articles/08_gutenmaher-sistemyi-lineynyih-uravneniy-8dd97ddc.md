---
id: 1984-1-gutenmaher-sistemyi-lineynyih-uravneniy-8dd97ddc
issue: kvant_1984_1
year: 1984
number: "1"
title: Hệ phương trình tuyến tính
authors:
  - Гутенмахер В. Л.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 26
page_last: 31
page_labels: 24-29
tag: 8U8G
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 347f7175bceb55dc1f74fa93033bbc88cfa328c4aee9fb91ed9a69e666f7209d
prompt_sha256: draft-1
translated_from: content/ru/1984/01/articles/08_gutenmaher-sistemyi-lineynyih-uravneniy-8dd97ddc.md
source_content_sha256: 73ff2afb36f83408da75fd427b77eadef4c593ee4838cdd495e4b314c07ce9ac
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 24⟧

Hệ phương trình tuyến tính
Ứng viên Khoa học Vật lý và Toán học
V. L. GUTENMACHER

Hệ phương trình tuyến tính thường được tìm thấy trong các ứng dụng khác nhau của toán học (ví dụ: vật lý, hóa học, kinh tế). Bài viết nói về các phương pháp đơn giản nhất lời giải của các hệ thống đó và về phương pháp phổ quát - phương pháp Gauss.

Loại trừ biến

Cách tốt nhất để hiểu phương pháp này là bằng một ví dụ. Hãy xem xét hệ thống
$$\begin{cases} 2x + 3y = 5 \\ 7x + 5y = 1. \end{cases}$$

Để giải nó, chúng ta sử dụng phương trình đầu tiên để loại bỏ biến $x$ khỏi phương trình thứ hai. Với mục đích này, chúng ta hãy chuẩn bị cả hai phương trình sao cho các hệ số của $x$ giống nhau. Nhân phương trình thứ nhất với 7 và phương trình thứ hai với 2, ta được
$$\begin{cases} 14x + 21y = 35 \\ 14x + 10y = 2. \end{cases}$$

Bây giờ chúng ta giữ nguyên phương trình đầu tiên và thay thế phương trình thứ hai bằng hiệu giữa phương trình thứ nhất và phương trình thứ hai:
$$\begin{cases} 14x + 21y = 35 \\ 11y = 33. \end{cases}$$

Bây giờ chúng ta đưa phương trình thứ nhất về dạng ban đầu và chia phương trình thứ hai cho 11:
$$\begin{cases} 2x + 3y = 5 \\ y = 3. \end{cases}$$

Thay giá trị $y=3$ vào phương trình đầu tiên, ta tìm được
$$\begin{cases} x = -2 \\ y = 3. \end{cases}$$

⟦folio 25⟧

Thu được Đáp số, hệ phương trình chỉ có một lời giải - một cặp số (-2; 3).

Bài toán
1. Phương pháp loại bỏ biến hệ thống lời giải
   a) $\begin{cases} 2x+3y=4 \\ 3x-2y=5 \end{cases}$
   b) $\begin{cases} \frac{3}{4}x-\frac{5}{6}y=1 \\ \frac{5}{6}x-\frac{3}{4}y=2. \end{cases}$
2. Hai điểm di chuyển dọc theo trục số với tốc độ $u=-12$ km/h và $v=12$ m/s. Lúc đầu, trục hoành của chúng là $a=3$ km và $b=-500$ m. Họ sẽ gặp nhau ở đâu và khi nào?

Thay thế các biến
Một trong những kỹ thuật cơ bản của đại số là thay thế một biến bằng một biến khác. Kỹ thuật này cho phép bạn tạo bài toán thành những cái đơn giản hơn. Ví dụ, chúng ta cần giải một hệ phương trình phi tuyến tính
   $$\begin{cases} \frac{2}{x}+\frac{3}{y}=5. \\ \frac{7}{x}+\frac{5}{y}=1. \end{cases}$$
Bằng cách bảo vệ $u=\frac{1}{x}, v=\frac{1}{y}$, chúng ta thu được một hệ thống tuyến tính với các biến mới $u, v$:
   $$\begin{cases} 2u+3v=5 \\ 7u+5v=1. \end{cases}$$
Giải nó, ta tìm được $u=-2, v=3$. Bây giờ chúng ta quay lại các biến cũ: $\frac{1}{x}=-2, \frac{1}{y}=3$, từ đâu $x=-\frac{1}{2}, y=\frac{1}{3}$.

Bài toán 3. Phương pháp thay biến lời giải hệ thống
   a) $$\begin{cases} \frac{1}{2x+3y-5}+\frac{7}{5x-8y+12}=1 \\ \frac{4}{2x+3y-5}-\frac{14}{5x-8y+12}=1 \end{cases}$$
   b) $$\frac{x^2+xy=5}{3x^2+5xy=23}$$
   c) $$\frac{xy}{3x+2y}=\frac{1}{5}, \frac{xy}{5x+7y}=1.$$

Ý nghĩa hình học của phương trình tuyến tính
Để tìm phương trình đường thẳng $y=kx+b$, đi qua các điểm có tọa độ (1; 2) và (3; 1), ta thay tọa độ của dữ liệu điểm vào phương trình $y=kx+b$ thay vì $x$ và $y$. Chúng ta sẽ có được hệ thống
   $$\begin{cases} 2=k+b \\ 1=3k+b. \end{cases}$$
Giải nó, ta tìm được $k=-\frac{1}{2}, b=\frac{5}{2}$.
Vì vậy, phương trình đúng là $y=-\frac{1}{2}x+\frac{5}{2}$.
Nhưng có thể hệ phương trình tương ứng không có lời giải. Ví dụ: giả sử các điểm này có tọa độ (1; 2) và (1; 3). Thay các giá trị này vào phương trình $y=kx+b$, ta thu được hệ
   $$\begin{cases} 2=k+b \\ 3=k+b, \end{cases}$$
không có lời giải (xét cho cùng, $2=3$ tuân theo phương trình của hệ). Thoạt nhìn, điều này hơi ngạc nhiên - xét cho cùng, một đường thẳng luôn đi qua hai điểm. Hóa ra phương trình của đường thẳng đi qua các điểm (1; 2) và (1; 3) không được viết dưới dạng $y=kx+b$ - phương trình của nó là $x=1$.
Như vậy, chúng ta đã tìm ra nguyên nhân của sự hiểu lầm - bài toán được xây dựng kém: trong điều kiện giả sử phương trình của một đường thẳng trên mặt phẳng tọa độ luôn có dạng $y=kx+b$, nhưng đối với các đường thẳng song song với trục tọa độ thì không phải vậy. Về vấn đề này, chúng ta để lại phương trình đường thẳng tùy ý được viết dưới dạng $ax+by=c$. Chế độ xem này cho phép bạn bao quát tất cả các đường thẳng trên mặt phẳng tọa độ. Ví dụ: nếu đặt $a=\frac{1}{2}, b=1, c=\frac{5}{2}$, chúng ta sẽ có phương trình của đường thẳng thứ nhất và nếu đặt $a=1, b=0, c=1$, chúng ta sẽ có phương trình của đường thẳng thứ hai.
Bây giờ chúng ta hãy xem xét hệ thống
   $$\begin{cases} x+\sqrt{2}y=\sqrt{3} \\ \sqrt{2}x+2y=\sqrt{6}. \end{cases}$$
Giải nó, theo ngôn ngữ hình học, có nghĩa là tìm điểm chung của các đường thẳng cho bởi phương trình $x+\sqrt{2}y=\sqrt{3}, \sqrt{2}x+2y=\sqrt{6}$. Hãy giải hệ này bằng cách loại bỏ biến: nhân phương trình đầu tiên với $\sqrt{2}$ và trừ phương trình thứ hai:

⟦folio 26⟧

$$\begin{cases} \sqrt{2}x + 2y = \sqrt{6} \\ \sqrt{2}x + 2y = \sqrt{6} \end{cases} \quad 0 = 0.$$

Kết quả là chỉ còn lại một phương trình. Điều này có nghĩa là hệ thống có số vô hạn lời giải và các đường thẳng trùng nhau. Trong quá trình lời giải, chúng tôi phát hiện ra rằng phương trình thứ hai là phương trình đầu tiên nhân với $\sqrt{2}$, điều này có thể không được chú ý ngay lập tức.

Trong các bài toán được phân tích, chúng tôi gặp tất cả các tình huống có thể xảy ra: hệ thống có một lời giải, không có lời giải, có vô số lời giải. Điều tương tự cũng đúng trong trường hợp tổng quát. Một hệ phương trình tuyến tính $n$ với ẩn số $n$ thường có một lời giải duy nhất. Nhưng khi một trong các phương trình của nó là "tổ hợp tuyến tính" của các phương trình khác hoặc mâu thuẫn với chúng, thì nó có vô số lời giải hoặc không có gì cả.

Bài toán

4. Tìm phương trình đường thẳng đi qua các điểm a) (1; 5) và (2; 3); b) (6; 1) và (6; 5).

5. Đối với $k$ và $b$ thì các đường $y - kx = 2$ và $2y - 6x = b$ trùng nhau? b) không cắt nhau?

6. Tại hệ thống $a$ nào

$$\begin{cases} 2x + (9a^2 - 2)y = 3a \\ x + y = 1 \end{cases}$$

không có lời giải?

7. Chứng minh rằng hệ thống

$$\begin{cases} a_1x + b_1y = c_1 \\ a_2x + b_2y = c_2 \end{cases}$$

có lời giải duy nhất khi và chỉ khi $a_1b_2 - a_2b_1 \neq 0$. (Số $a_1b_2 - a_2b_1$ gọi là số xác định của hệ.)

Lỗi làm tròn

Khi lời giải bài toán tình huống bất ngờ có thể xảy ra trên máy tính. Minh họa kinh điển cho điều này là hệ thống lời giải

$$\begin{cases} x + \sqrt{2}y = \sqrt{3} \\ \sqrt{2}x + 2y = \sqrt{6}. \end{cases}$$

Hệ thống này, như chúng ta đã thấy, có vô số lời giải. Tuy nhiên, nếu giải trên máy tính thì sẽ có... thứ duy nhất là lời giải! Điều này xảy ra vì máy tính không thể hoạt động với các số có dạng $\sqrt{2}$ - chúng được thay thế bằng các giá trị gần đúng thập phân (hoặc gấp đôi).

Ví dụ: nếu các số $\sqrt{2}, \sqrt{3}, \sqrt{6}$ được thay thế bằng giá trị gần đúng thập phân của chúng bằng một chữ số sau dấu thập phân: $\sqrt{2} \approx 1.4; \sqrt{3} \approx 1.7; \sqrt{6} \approx 2.4$, hệ thống sẽ có dạng

$$\begin{cases} x + 1.4y = 1.7 \\ 1.4x + 2y = 2.4. \end{cases}$$

Giải xong ta được một lời giải: $x = 1; y = 0.5$.

Nếu bỏ đi 4 chữ số thập phân thì ta được hệ

$$\begin{cases} x + 1.4142y = 1.7320 \\ 1.4142x + 2y = 2.4494 \end{cases}$$

cũng có một thứ (nhưng hoàn toàn khác) lời giải: $x = 0,3178; y = 1$.

Điều thú vị là, cho dù chúng ta thay thế số $\sqrt{2}$ bằng phép tính gần đúng thập phân nào thì kết quả duy nhất sẽ luôn là lời giải.

Hãy chứng minh điều đó. Thay $\sqrt{2}$ trong hệ (1) bằng chữ $a$, ta thu được

$$\begin{cases} x + ay = \sqrt{3} \\ ax + 2y = \sqrt{6}. \end{cases}$$

Hãy chứng minh rằng với $a^2 \neq 2$ hệ thống có duy nhất lời giải. Nếu $a = 0$, điều đó là hiển nhiên. Hãy bây giờ $a \neq 0$. Nhân phương trình đầu tiên với $a$ và trừ phương trình thứ hai với nó, chúng ta rút gọn hệ về dạng

$$\begin{cases} x + ay = \sqrt{3} \\ (a^2 - 2)y = a\sqrt{3} - \sqrt{6}. \end{cases}$$

Vì $a^2 \neq 2$, $y$ nhận một giá trị duy nhất $\frac{a\sqrt{3} - \sqrt{6}}{a^2 - 2}$. Thay nó vào phương trình đầu tiên, chúng ta tìm thấy giá trị duy nhất $x$. Do đó, nếu với $a$, chúng ta không lấy chính số $\sqrt{2}$ mà lấy một số giá trị gần đúng của nó, thì $a^2 \neq 2$ có nghĩa là hệ thống có một lời giải duy nhất.

Cần phải nhắc lại (“Đại số 7,” trang 28) rằng bản thân số $\sqrt{2}$ không thể được biểu diễn dưới dạng phân số thập phân hữu hạn (hoặc thậm chí ở dạng bất kỳ phân số nào $\frac{p}{q}$, trong đó $p$ và $q$ là số nguyên).

Vì điều này, chúng ta gặp phải một nghịch lý liên quan đến việc giải hệ phương trình (1) trên máy tính.

Chúng ta hãy chú ý đến thực tế là ngay cả trong trường hợp tất cả các hệ số của một hệ thống nhất định đều là phân số thập phân hữu hạn, khi chúng được làm tròn, lời giải của hệ thống có thể thay đổi đáng kể. Do đó, hệ (2) thu được bằng cách làm tròn các hệ số của hệ (3), đồng thời lời giải của chúng hoàn toàn khác nhau. Trong một hệ thống có số lượng biến lớn, các lỗi xảy ra trong quá trình làm tròn có thể dẫn đến những thay đổi đáng kể trong lời giải.

Việc ước tính lỗi và chỉ định quy trình lời giải đảm bảo lỗi nhỏ nhất là quan trọng và không hề đơn giản bài toán. Vào đầu thế kỷ trước, nhà toán học vĩ đại Gauss bắt đầu nghiên cứu nó và những tiến bộ đáng kể hơn nữa theo hướng này chỉ được thực hiện trong những năm thập phân cuối cùng. Do những đóng góp quan trọng của Gauss cho lĩnh vực này, một phương pháp đơn giản và phổ biến để loại bỏ các biến số được đặt theo tên ông.

Phương pháp Gauss

Loại bỏ tuần tự các biến là cách thuận tiện nhất lời giải của hệ tuyến tính

⟦folio 27⟧

Phương trình trên máy tính. Chúng ta hãy chứng minh điều đó bằng ví dụ về hệ ba phương trình với ba biến

$$\begin{cases}
x_1 + x_2 + 2x_3 = -1 \\
2x_1 - x_2 + 2x_3 = -4 \\
4x_1 + x_2 + 4x_3 = -2.
\end{cases}$$

Bước đầu tiên là sử dụng phương trình thứ nhất, biến $x_1$ được loại khỏi các phương trình còn lại: phương trình thứ nhất được giữ nguyên; từ phương trình thứ hai, chúng ta trừ đi phương trình thứ nhất; từ phương trình thứ ba, chúng ta trừ bốn lần phương trình thứ nhất; chúng tôi nhận được

$$\begin{cases}
x_1 + x_2 + 2x_3 = -1 \\
-3x_2 - 2x_3 = -2 \\
-3x_2 - 4x_3 = 2.
\end{cases}$$

Bước thứ hai là bằng cách sử dụng phương trình thứ hai mới, biến $x_2$ được loại khỏi phương trình thứ ba: hai phương trình đầu tiên được giữ nguyên; trừ đi số thứ hai từ phương trình thứ ba; chúng tôi nhận được

$$\begin{cases}
x_1 + x_2 + 2x_3 = -1 \\
-3x_2 - 2x_3 = -2 \\
-2x_3 = 4.
\end{cases}$$

Bây giờ từ phương trình cuối cùng chúng ta tìm thấy $x_3 = -2$. Thay giá trị này vào phương trình trước đó, chúng ta tìm thấy $x_2 = 2$. Thay thế $x_2 = 2$ và $x_3 = -2$ vào phương trình đầu tiên, chúng ta tìm thấy $x_1 = 1$. Vậy là chúng ta đã sẵn sàng đáp số: $(1; 2; -2)$.

Bạn có thể giải bất kỳ hệ phương trình tuyến tính nào theo cách tương tự. Nói một cách đại khái, phương pháp Gaussian như sau:

Sử dụng phương trình đầu tiên, biến $x_1$ bị loại khỏi các phương trình còn lại. Sau đó, phương trình thứ hai mới sẽ loại bỏ biến $x_2$ khỏi tất cả các phương trình tiếp theo. Sau đó, sử dụng phương trình thứ ba mới, biến $x_3$ bị loại bỏ. Và cứ như vậy cho đến khi ta nhận được giá trị của biến cuối cùng trong phương trình cuối cùng. Sau đó, chúng ta tìm các biến theo thứ tự ngược lại, thay thế các giá trị đã biết của chúng vào phương trình.

Chúng tôi thấy rằng đây là một chương trình máy tính gần như được tạo sẵn. Nhưng để phương pháp này có thể so sánh, điều cần thiết là ở bước thứ $k$, phương trình thứ $k$ mới chứa biến thứ $k$ (xét cho cùng, với sự trợ giúp của nó, chúng ta cần loại trừ biến này khỏi các phương trình còn lại). Nếu thực tế không phải như vậy thì cần phải sắp xếp lại (đo lường lại) các phương trình hoặc các biến.

Cũng có thể từ một thời điểm nào đó các phương trình cuối cùng chuyển thành các đẳng thức số có dạng $0 = b$. Nếu ít nhất một trong các đẳng thức này sai ($b \neq 0$), thì hệ thống không có lời giải. Nếu tất cả các đẳng thức này đều đúng thì hệ có số vô hạn lời giải. (Tất cả cũng được coi là được cung cấp bằng cách sử dụng chương trình máy tính.)

Lưu ý rằng không phải các phương trình được nhập vào máy tính mà là các bảng hệ số - cái gọi là ma trận hệ thống. Ví dụ: hệ ta vừa giải được liên kết với ma trận

$$\begin{pmatrix}
1 & 1 & 2 & -1 \\
2 & -1 & 2 & -4 \\
4 & 1 & 4 & -2
\end{pmatrix}$$

Hai bước của phương pháp Gauss mà chúng tôi đã thực hiện ở lời giải có thể được mô tả như sau:

$$\begin{pmatrix}
1 & 1 & 2 & -1 \\
2 & -1 & 2 & -4 \\
4 & 1 & 4 & -2
\end{pmatrix} \rightarrow \\
\begin{pmatrix}
1 & 1 & 2 & -1 \\
0 & -3 & -2 & -2 \\
0 & -3 & -4 & -2
\end{pmatrix} \rightarrow \\
\begin{pmatrix}
1 & 1 & 2 & -1 \\
0 & -3 & -2 & -2 \\
0 & 0 & -2 & 4
\end{pmatrix}$$

Nhân tiện, người ta nói rằng khi các hệ thống có khay và một số lượng lớn biến được giải thủ công chứ không phải trên máy tính, thì việc làm việc với ma trận cũng thuận tiện hơn - ít có khả năng mắc lỗi hơn.

Bài toán 8. Giải hệ do nhà cổ điển thứ bảy ở loại XV loại 2 vùng Matxcơva đề xuất:

$$\begin{align*}
x_1 + 2x_2 + 2x_3 + 2x_4 + 2x_5 &= 1 \\
x_1 + 3x_2 + 4x_3 + 4x_4 + 4x_5 &= 2 \\
x_1 + 3x_2 + 5x_3 + 6x_4 + 6x_5 &= 3 \\
x_1 + 3x_2 + 5x_3 + 7x_4 + 8x_5 &= 4 \\
x_1 + 3x_2 + 5x_3 + 7x_4 + 9x_5 &= 5.
\end{align*}$$

Khác nhau bài toán

9. Nhà toán học ra ngoài đi dạo - lúc đầu ông đi một con đường bằng phẳng, sau đó lên núi, quay lại và trở về nhà theo cách tương tự.

⟦folio 28⟧

Hình 1. Hình 2. Hình 3.

Đắt. Anh ta biết rằng anh ta đã đi bộ được 5 giờ, tốc độ của anh ta trên đường bằng là 4 km/h, lên dốc - 3 km/h và khi xuống dốc - 6 km/h. Ngồi xuống bàn và soạn một phương trình với hai biến: $x$ - quãng đường di chuyển ở hai đầu và $y$ - độ dài của phần nghiêng, nhà toán học rất ngạc nhiên khi phát hiện ra rằng mình có thể tìm thấy $x$. Tìm $x$.

10. 4 chú lùn đang ngồi ở một chiếc bàn tròn. Trước mỗi điểm dừng có một cốc sữa. Một trong những người lùn đổ $\frac{1}{4}$ sữa của mình cho người hàng xóm bên phải. Sau đó, người hàng xóm cũng làm như vậy. Sau đó, người hàng xóm tiếp theo cũng làm như vậy và cuối cùng, chú lùn thứ tư $\frac{1}{4}$ đổ sữa mà anh ta có cho chú lùn đầu tiên. Tất cả các cốc đều chứa 2 lít sữa. Hỏi ban đầu trong cốc có bao nhiêu sữa, nếu
a) cuối cùng tất cả các chú lùn đều có nhiều sữa như lúc đầu?

11. Xác định các số $a, b$ và $c$ để hàm $y = ax^2 + bx + c$ có ​​bảng giá trị

Lời giải. Thay tuần tự các giá trị đã cho $x$ và $y$ vào công thức $y = ax^2 + bx + c$, chúng ta thu được $1 = a \cdot 0 + b \cdot 0 + c, 2 = a \cdot 1 + b \cdot 1 + c, 2 = a \cdot 2^2 + b \cdot 2 + c$. Giải hệ phương trình này, ta tìm được $c = 1$, $a = -\frac{1}{2}, b = \frac{3}{2}$. Do đó hàm số có dạng
$$y = -\frac{1}{2}x^2 + \frac{3}{2}x + 1.$$

12. Xác định các số $a, b$ và $c$ để hàm $y = a + b(x-1) + c(x-1)(x-2)$ có ​​bảng giá trị

Lời giải. Từ Hình 1 ta có hệ thống

$\cdot$ Vì bài viết này chủ yếu dành cho học sinh lớp bảy nên sau đây các ký hiệu từ sách giáo khoa “Hình học 6-10” của A. V. Pogorelov sẽ được sử dụng.

⟦folio 29⟧

Hình 4. Hình 5.

$$x + y = c, y + z = a, z + x = b.$$

Tất nhiên, nó có thể được giải quyết dễ dàng bằng bất kỳ phương pháp nào ở trên, nhưng cách khác sẽ đẹp hơn và dễ dàng hơn. Hãy cộng cả ba phương trình. Chúng tôi nhận được $2x + 2y + 2z = a + b + c$, từ đâu $x + y + z = \frac{a + b + c}{2}$. Trừ từng phương trình của hệ khỏi phương trình này, chúng ta tìm thấy $x = \frac{b + c - a}{2}, y = \frac{a + c - b}{2}, z = \frac{a + b - c}{2}$.

16. Dựa vào $AB$ của tam giác đều $ABC$, lấy điểm $E$. Tam giác $ACE$ và $ECB$ chứa các đường tròn nội tiếp tiếp xúc với đoạn $CE$ tại các điểm $K$ và $H$. tương ứng. Tìm độ dài của đoạn $KH$ nếu $AE = a, EB = b$.

17. (Hồi ký được đưa ra tại Olympic Ukraina lần thứ XXIII năm 1983) Hình chữ nhật được chia thành các hình vuông như trên Hình 2. Biết cạnh của hình vuông được bảo vệ bằng 1. Tìm các cạnh của các hình vuông còn lại.

Lời giải. Chúng ta hãy biểu thị các cạnh được yêu cầu bằng $x, y, z, u$ (xem Hình 2). Sau đó $MN = y = u + 1, AB = x = y + 1, KL = z = x + 1$. Thay thế $y = u + 1$ vào trận đấu thứ hai, chúng ta tìm thấy $x = u + 2$. Thay $x = u + 2$ vào tương ứng thứ ba, ta tìm được $z = u + 3$. Bây giờ chúng ta hãy viết ra sự bằng nhau của các cạnh đối diện của hình chữ nhật: $x + z = y + 2u$; thay thế $x, y$ và $z$ ở đây, chúng ta nhận được $(u + 2) + (u + 3) = (u + 1) + 2u$, do đó $u = 4$. Bây giờ chúng tôi tìm thấy $x = 6, y = 5, z = 7$.

18. Hình chữ nhật được chia thành các hình vuông như Hình 3. Biết cạnh của hình vuông được bảo vệ là 2. Tìm cạnh của các hình vuông còn lại.

Hai vấn đề tiếp theo liên quan đến các mạch điện phân nhánh được tạo thành từ các dây dẫn có điện trở đơn vị. Mỗi mạch được kết nối với nguồn tại hai điểm (cực). Toki tuân theo định luật đúng của Kirchhoff, đối với các mạch đang xét có thể được biểu diễn như sau:

1) Tổng dòng điện đi vào bất kỳ nút nào bằng tổng dòng điện đi ra khỏi nút đó (cực không được coi là nút).

2) Trong bất kỳ mạch kín nào, tổng dòng điện chạy theo chiều kim đồng hồ bằng tổng dòng điện chạy ngược chiều kim đồng hồ $^*$).

19. Hình 4 thể hiện một mạch điện có các cực $A, C$ và các nút $B, D$. Tìm dòng điện trong tất cả các dây dẫn của mạch này nếu biết rằng dòng điện trong dây dẫn $DB$ bằng 1. (Các mũi tên chỉ chiều của dòng điện.)

20. Hình 5 thể hiện các mạch điện có cực $A$ và $C$. Tìm dòng điện trong dây dẫn của chúng nếu biết rằng trong mỗi mạch dòng điện trong dây dẫn $CD$ bằng 1. Một số dòng điện bằng 0 và in dấu, điều này có nghĩa là gì?

21. Hai người chơi một trò chơi như thế này: trong hệ thống
$$\begin{cases} x + y = * \\ x + y = * \end{cases}$$
Họ lần lượt ghép một số số lại với nhau bằng dấu hoa thị; cái đầu tiên muốn hệ thống kết quả có lời giải và cái thứ hai muốn hệ thống không có lời giải. Ai sẽ thắng nếu chơi đúng? Và ai sẽ thắng nếu ngược lại, người đầu tiên muốn hệ thống kết quả không có lời giải, và người thứ hai muốn nó có?

22. (Nó được đưa ra ở lớp 8 và lớp 10 tại XXIII All-Olympid và được đưa vào nhiệm vụ “Kwaンタ” với số M578; lời giải xem phần “Đáp số, gợi ý, lời giải”.) Giải hệ $(a$ và $b$ - các số đã cho)
$$\frac{x - y \sqrt{x^2 - y^2}}{\sqrt{1 - x^2 + y^2}} = a, \quad \frac{y - x \sqrt{x^2 - y^2}}{\sqrt{1 - x^2 + y^2}} = b.$$

$^*)$ Nói rằng tổng hướng giảm như nhau thì đúng hơn, nhưng vì tất cả các dây dẫn đều có điện trở đơn vị nên chúng ta có thể nói về dòng điện.
