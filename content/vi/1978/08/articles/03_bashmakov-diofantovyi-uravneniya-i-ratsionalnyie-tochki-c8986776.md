---
id: 1978-8-bashmakov-diofantovyi-uravneniya-i-ratsionalnyie-tochki-c8986776
issue: kvant_1978_8
year: 1978
number: "8"
title: Phương trình Diophantine và điểm hữu tỷ
authors:
  - Башмаков М. И.
rubric: osnovnye-stati
page_first: 4
page_last: 9
page_labels: 2, 4, 5, 6, 7
tag: 2VOJ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 9c3156d43f1b9b7a4ec2108222f977739f392df7b818d7e2d930b3fdb15ef331
prompt_sha256: draft-1
translated_from: content/ru/1978/08/articles/03_bashmakov-diofantovyi-uravneniya-i-ratsionalnyie-tochki-c8986776.md
source_content_sha256: c9d8ded41b15fbe1911d1cd32c5e9f9d4553171779031e11095a4f623e3bac96
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

Diophantov
phương trình
và hợp lý
điểm

Lĩnh vực lý thuyết số nghiên cứu các phương trình số nguyên lời giải có dạng $P(x, y, \dots) = 0$, trong đó $P(x, y, \dots)$ là đa thức của một số biến có hệ số nguyên, được gọi là phân tích Diophantine và bản thân các phương trình này được gọi là Diophantine.

Chúng được đặt theo tên của nhà toán học nổi tiếng người Hy Lạp Diophantus, người sống ở thế kỷ thứ 3 và đã viết chuyên luận đầu tiên về các phương trình như vậy.

Mặc dù thực tế là phương trình Diophantine là một trong những lĩnh vực lâu đời nhất của toán học,

phương pháp chung lời giải ra đời khá gần đây. Trong các tác phẩm cổ điển, phương trình Diophantine tuyến tính và bậc hai chủ yếu được xem xét. Lời giải Sự phát triển của các phương trình phức tạp hơn đã có tiến bộ vượt bậc trong 20-25 năm qua nhờ sự tham gia rộng rãi vào lý thuyết số từ các lĩnh vực khác của toán học, chủ yếu là từ hình học và cấu trúc liên kết. Theo lời của N. Bourbaki, “...hình học cổ điển...đang trở thành ngôn ngữ phổ quát của toàn bộ toán học, sở hữu tính linh hoạt và tiện lợi đặc biệt.” Hình học không chỉ cung cấp ngôn ngữ mà còn cung cấp cả cấu trúc và trực giác của nó.

Hãy nhìn xem ngôn ngữ hình học rõ ràng biết bao. Lấy ví dụ: phương trình Fermat $x^n + y^n = z^n$, chia cả hai vế cho $z^n$ và biểu thị $x/z$ cho $u, y/z$ cho $v$. Chúng ta thu được phương trình $u^n + v^n = 1$. Mỗi lời giải $(x; y; z)$ của phương trình Fermat cho mục đích số tương ứng (tại $z \neq 0$) với lời giải của phương trình $u^n + v^n = 1$ trong số hữu tỷ.

Nếu bây giờ chúng ta xem xét đồ thị của phương trình này trên mặt phẳng $(u, v)$,

⟦folio 4⟧

Bây giờ chúng ta hãy xem xét một đường cong được xác định bởi phương trình bậc ba, phương trình này cũng là hữu tỉ. Đây là đường cong $y^2=x^3-x^2$. Nó được hiển thị trong Hình 3 và bao gồm một điểm cô lập $O$ và một nhánh đối xứng với trục tương đối $x$.

Nhiệm vụ 3. Căn chỉnh Hình 3.

Chúng ta hãy vẽ qua điểm $O$ tất cả các đường thẳng có thể có $y=tx$. Các giá trị của hệ số góc $t$ có ​​thể được vẽ trên trục $t$ được vẽ qua điểm $(1, 0)$ (Hình 4). Thay $y=tx$ vào phương trình của đường cong và triệt tiêu bằng $x^2$ (mất điểm kỳ dị $O!$), ta thu được tham số hóa

$$\begin{cases} x=t^2+1, \\ y=t(t^2+1), \end{cases}$$

tại đó giá trị hữu tỉ $t$ tương ứng với các điểm hữu tỉ của đường cong $y^2=x^3-x^2$.

Bài 4. Lập và chứng minh mệnh đề ngược lại.

Vì vậy, có thể thiết lập sự tương ứng một-một giữa các điểm hữu tỉ của đường cong $y^2=x^3-x^2$ (không có điểm $(0, 0$)) và đường thẳng $t$. Về mặt hình học, chúng đại diện cho thiết kế trung tâm được thể hiện trong Hình 4.

Tương tự, người ta có thể tìm tham số hóa hợp lý của đường cong $y^2=x^3+x^2$:

$$x=t^2-1, y=t(t^2-1).$$

Bài 5. Xây dựng đường cong này và chứng minh rằng nếu thỏa mãn sự tương ứng $(t_1-1)(t_2-1)(t_3-1)=(t_1+1)(t_2+1)(t_3+1)$ với các giá trị của tham số $t_1, t_2$ thì ba điểm tương ứng nằm trên cùng một đường thẳng.

Vì vậy, đối với mỗi đường cong hữu tỉ mà chúng ta đã xem xét, chúng ta có thể chỉ định ánh xạ của một đường trên đường cong trong đó các điểm hữu tỉ của đường cong tương ứng với các điểm hữu tỉ của đường thẳng. Trên thực tế, phát biểu này cũng đúng với một đường cong hữu tỷ tùy ý; chúng ta thu được phương trình từ Diophantus.

Câu hỏi nảy sinh: có những đường cong vô tỷ không? Làm thế nào để mô tả tất cả các đường cong hợp lý? Đáp số được biết đến với những câu hỏi này. Ví dụ, tất cả các đường cong cấp một và cấp hai đều hữu tỉ. Có lý trí

⟦folio 5⟧

Hình 6.

các đường cong tự nhiên ở bất kỳ mức độ nào, nhưng tất cả các đường cong có mức độ lớn hơn hai đều có một đặc thù - điểm tự giao nhau, điểm tự chạm, v.v. (Hình 5).

Đối với $n > 2$ đường cong Fermat $u^n + v^n = 1$ không hợp lý. Chứng minh rằng điều này tương đương với phát biểu rằng phương trình Fermat $x^n + y^n = z^n$ không có lời giải trong số các đa thức $x(t), y(t), z(t)$ bậc ít nhất một. (Thực tế này đã được chứng minh trong bài báo của B. Martynov “Định lý Fermat cho đa thức” («Kvant», 1976, số 8).)

Chúng ta sẽ lại hiển thị cái thứ hai bằng ví dụ về hình tròn. Hãy lấy hai điểm hữu tỉ trên đường tròn - ví dụ: $P_1$ (3/5, 4/5) và $P_2$ (13/5, 12/13). Đặt $\alpha_1$ và $\alpha_2$ là các góc tương ứng với các điểm $P_1$ và $P_2$. Điểm tương ứng với góc $\alpha_1 + \alpha_2$ cũng sẽ hữu tỉ, vì

$$\cos(\alpha_1 + \alpha_2) = \cos \alpha_1 \cos \alpha_2 - \sin \alpha_1 \sin \alpha_2, \sin(\alpha_1 + \alpha_2) = \sin \alpha_1 \cos \alpha_2 + \cos \alpha_1 \sin \alpha_2.$$

Do đó, chúng ta có thể “cộng” các điểm hữu tỉ trên một vòng tròn bằng công thức $(u_1; v_1) \oplus (u_2; v_2) = (u_1 u_2 - v_1 v_2; u_1 v_2 + u_2 v_1)$ và thu được các điểm hữu tỉ mới. Đặc tính này của hình tròn làm cơ sở cho vẻ đẹp nhiều mặt bài toán.

Bài tập 6. a) Cho $P_1$ là điểm hữu tỉ của đường tròn ứng với một góc $\alpha$ nào đó. Chứng minh rằng các điểm $P_n$ tương ứng với các góc $n \in \mathbb{Z}$ cũng hữu tỉ.

b) Chứng minh rằng khoảng cách từng cặp giữa các điểm dựng ở phần a) là hợp lý.

c) Xây dựng $n$ điểm trên mặt phẳng, ba điểm dưới không nằm trên cùng một đường thẳng và khoảng cách theo cặp giữa chúng là số nguyên.

Hóa ra cũng có những đường cong có tính chất sau: các điểm trên chúng có thể được “cộng” và “tổng” các điểm hữu tỉ là một điểm hữu tỉ. Đối với những đường cong như vậy, đôi khi có thể “kéo dài” cả một chuỗi các điểm hữu tỉ mới từ hai điểm hữu tỉ.

Hãy lấy đường cong làm ví dụ

$$y^2 + y = x^3 - x.$$

Bài toán 7. Chứng minh đường cong này không hữu tỷ.

Hãy lấy hai điểm trên đường cong này và vẽ một đường thẳng đi qua chúng. Đường thẳng này sẽ cắt đường cong của chúng ta tại một điểm nữa (Hình 6). Thật vậy, nếu viết phương trình đường thẳng đã vẽ dưới dạng $y = kx + b$ và thay $y$ vào phương trình đường cong, chúng ta thu được phương trình bậc ba tương đối $x$. Khi nghiệm của phương trình này ứng với hoành độ của ba điểm giao nhau của đường thẳng và đường cong bậc ba của chúng ta. Gọi $P_1(x_1; y_1), P_2(x_2; y_2), P_3(x_3; y_3)$ là ba điểm giao nhau của đường $y = kx + b$ và đường cong $y^2 + y = x^3 - x$. Có một thư từ

$$x_1 + x_2 + x_3 = \left(\frac{y_1 - y_2}{x_1 - x_2}\right)^2.$$

Để chứng minh điều này, hãy thay $y = kx + b$ vào phương trình của đường cong. Chúng ta thu được phương trình $x^3 - k^2 x^2 - (2kb + k + 1)x - b^2 - b = 0$. Có thể chứng minh rằng $x^3 - k^2 x^2 - (2kb + k + 1)x - b^2 - b = (x - x_1)(x - x_2)(x - x_3)$. Vì vậy, $x_1 + x_2 + x_3 = k^2$. Độ dốc $k$ của đường thẳng đi qua các điểm $P_1(x_1, y_1)$ và $P_2(x_2, y_2)$ là $\frac{y_1 - y_2}{x_1 - x_2}$. Như vậy ta được (*).

Cho rằng $y_3 = kx_3 + b$, $b = \frac{y_2 x_1 - y_1 x_2}{x_1 - x_2}$, ta thấy tọa độ của giao điểm thứ ba là hữu tỉ nếu tọa độ của hai điểm đầu là hữu tỉ. Điều này giúp có thể thu được các phương trình lời giải mới $y^2 + y = x^3 - x$ ở dạng số hữu tỉ.

⟦folio 6⟧

Hình 7.

Bình luận. Khoảng cách phía trên phương trình bậc ba có thể có gốc trùng khớp. Điều này có nghĩa là đường thẳng và đường cong của chúng ta chạm vào nhau.

Bây giờ chúng ta sẽ xây dựng một chuỗi vô hạn các phương trình lời giải hữu tỉ $y^2+y=x^3-x$ bằng cách vẽ các cát tuyến và tiếp tuyến thông qua các điểm hữu tỷ đã biết. Trước tiên, chúng ta hãy lưu ý rằng các điểm trên đường cong của chúng ta nằm theo cặp - cùng với điểm $P(x_0; y_0)$ có ​​một điểm $P'(x_0; -1-y_0)$ trên đường cong, đối xứng với nó so với đường thẳng $y=-\frac{1}{2}$. Điều này diễn ra từ điểm $y^2+y=(-1-y)^2+(-1-y)$. Hãy bắt đầu với điểm hợp lý được đánh giá $P_1(0; 0)$. Điểm đối xứng với nó là $P'_1(0; -1)$. Hãy vẽ một tiếp tuyến qua $P_1$ (xem nhận xét). Phương trình của tiếp tuyến này là $y=-x$. Hãy tìm giao điểm của nó với đường cong của chúng ta: $P_2(1; -1)$. Những người không biết cách tìm tiếp tuyến có thể sử dụng phép thay thế trực tiếp để xác minh rằng điểm hữu tỉ $P_2$ nằm trên đường cong của chúng ta. Từ $P_2$ chúng ta nhận được điểm $P'_2(1; 0)$.

Vì vậy, có bốn điểm hợp lý trên đường cong của chúng tôi:

$$P_1(0; 0), \quad P'_1(0; -1),$$
$$P_2(1; -1), \quad P'_2(1; 0).$$

Bây giờ chúng tôi khởi động "băng tải". Hãy vẽ một đường thẳng qua $P_1$ và $P'_2$—đây là trục $x$. Nó cắt đường cong của chúng ta tại một điểm rõ ràng khác $P_3(-1; 0)$. Cùng với điểm đối xứng $P'_3(-1; -1)$ chúng ta có sáu điểm của đường cong ban đầu. Hãy nối các điểm $P'_3$ và $P_1$. Chúng ta có đường thẳng $y=x$. Dễ dàng tìm được giao điểm thứ ba: thay $y=x$, ta được phương trình bậc ba $x^3-x^2-2x=0$, hai nghiệm của phương trình này đã được thay đổi. Sử dụng (*), chúng ta thu được điểm mới $P_4(2; 2)$—điểm lời giải không hiển nhiên của phương trình ban đầu. Hãy tiếp tục quá trình này. Để lấy điểm $P_5$, hãy vẽ một đường thẳng qua các điểm $P'_4(2; -3)$ và $P_1$. Dễ dàng kiểm tra được kết quả sẽ là điểm $P_5(1/4; -3/8)$. Sử dụng Hình 7, có thể dễ dàng theo dõi quá trình xây dựng các điểm mới. Việc tính toán sử dụng công thức (*) cũng đơn giản. Kết quả là chúng ta thu được một loạt điểm như trong bảng.

Khó có độc giả nào có thể nói rằng tất cả lời giải mà chúng tôi tìm thấy đều hiển nhiên.

Tại điểm này trong bài viết, tác giả thậm chí còn nắm bắt được hai trong số đó - có thể đặt ra bao nhiêu câu hỏi có ý nghĩa khi nhìn vào Hình 7 vô hại. Dưới đây là một vài trong số đó:

1. Bằng cách vẽ các cát tuyến và tiếp tuyến, liệu chúng ta sẽ có được một chuỗi vô hạn các điểm khác nhau hay quá trình của chúng ta sẽ “đi theo chu kỳ”?
2. Có phải tất cả lời giải hữu tỉ của phương trình ban đầu đều xuất hiện trong dãy của chúng ta không?

⟦folio 7⟧

3. Liệu vẫn còn số nguyên lời giải (ví dụ: các điểm (6; 14) và (6; -15) đã được biểu thị) hay tất cả lời giải tiếp theo sẽ không phải là số nguyên?

4. Có phải ngẫu nhiên mà các mẫu số của lời giải chứa các hình vuông và lập phương của các số nguyên?

5. Ví dụ: trong hình có thể thấy rõ rằng điểm $P_5$ có thể đạt được theo cách khác - bằng cách vẽ một đường thẳng qua $P'_3$ và $P'_2$. Đây có phải là sự trùng hợp ngẫu nhiên?

6. Gần như hiển nhiên rằng tất cả các điểm có số lẻ đều nằm trên một nhánh của đường cong và tất cả các điểm có số chẵn đều nằm ở nhánh kia. Làm thế nào điều này có thể được chứng minh một cách chặt chẽ?

Ba câu hỏi đầu tiên rất khó. Hãy để tôi nói cho bạn biết rằng chuỗi điểm của chúng ta là vô hạn và tất cả các điểm có tọa độ hợp lý sẽ được tìm thấy trong đó.

Thay vì lăng mạ, tôi sẽ đưa ra một ví dụ nữa. Chúng ta hãy nhìn vào một đường cong rất giống nhau $y^2 + y = x^3 - x^2$. Một cấu hình tương tự như cấu hình mà chúng tôi đã xây dựng được khai báo ở bước thứ ba - xem Hình 8. Điều thú vị là đường cong này không có điểm hữu tỷ nào khác và phương trình $y^2 + y = x^3 - x^2$ không có lời giải ở dạng số hữu tỷ, ngoại trừ bốn điểm tầm thường.

Chúng ta đã đề cập đến một trong những vấn đề khó khăn nhất của lý thuyết số hiện đại.

Người ta biết rằng trên bất kỳ đường cong Cubian nào cũng có một số điểm hữu hạn, từ đó, bắt đầu quá trình được mô tả, người ta có thể thu được tất cả các điểm hữu tỷ của nó. Điều này đã được chứng minh khoảng năm mươi năm trước, nhưng vẫn chưa có cách tổng quát nào để tìm ra những điểm này.

Cách để tìm hiểu xem quá trình vẽ các đường thẳng hoặc nối ống dẫn một cấu hình vô hạn sẽ lặp lại hay không. Gần đây hơn, người ta đã chứng minh rằng cấu hình cuối cùng có thể có nhiều hơn 11 điểm và tất cả các trường hợp (trừ trường hợp 10 điểm) đều xảy ra và được nghiên cứu kỹ lưỡng.

Trên hầu hết các đường cong đã biết, số lượng điểm bắt đầu để xây dựng tất cả các điểm hữu tỉ là nhỏ - một hoặc hai. Tuy nhiên, có một giả thuyết cho rằng đối với bất kỳ $n$ nào cũng có những đường cong yêu cầu xây dựng tất cả các điểm lời giải $n$. Cho đến nay các ví dụ đã được xây dựng cho $n \leqslant 7$.

Và cuối cùng, nhận xét cuối cùng: nếu trong ví dụ của chúng ta với đường cong $y^2 + y = x^3 - x$, chúng ta thay đổi ký hiệu một chút - chúng ta viết $A_1$ cùng nhau $P_1$, $A_{-1}$ (thay vì $A'_1$, $A_k$ cùng nhau $P'_k$ và $A_{-k}$ cùng nhau $P_k$ (cho $k \geqslant 2$), và phép cộng đã cho phức tạp hơn một chút (“tổng” của hai điểm không phải là giao điểm thứ ba của một đường thẳng và một đường cong, mà là điểm đối xứng với nó so với đường thẳng $y = -\frac{1}{2}$), ta thu được công thức

$$A_m \oplus A_n = A_{m+n},$$

hợp lệ cho tất cả các số nguyên $m, n$.
