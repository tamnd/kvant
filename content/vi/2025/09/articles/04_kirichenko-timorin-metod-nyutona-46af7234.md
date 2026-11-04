---
id: 2025-9-kirichenko-timorin-metod-nyutona-46af7234
issue: kvant_2025_9
year: 2025
number: "9"
title: phương pháp Newton
authors:
  - Кириченко В. А.
  - Тиморин В. А.
rubric: osnovnye-stati
page_first: 13
page_last: 22
page_labels: 12, 13, 14, 15, 16, 17, 18, 20
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 581080b9ff789f50f4156f500b285c0d559e0f92b8033736b95b26a1ac853fed
prompt_sha256: draft-1
translated_from: content/ru/2025/09/articles/04_kirichenko-timorin-metod-nyutona-46af7234.md
source_content_sha256: f8ff2d20259e90d9c3d3118788eb5f76eed259d6dced968f00c87ae59b024001
translation_model: draft
translation_run: vi-draft-gaps-2026-11-04
translation_quality: draft
---

⟦folio none⟧

---
running_head:
folio:
---

V.KIRICHENKO, V.TIMORIN

Hiện tại anh ấy đang học cách lấy căn bậc hai của 2. Anh chưa bao giờ nhìn thấy bất cứ điều gì giống như vậy, nó vừa làm anh vừa vui mừng vừa lo lắng. “Điều này... điều này thật tuyệt vời,” anh lẩm bẩm. Quy trình này gây ấn tượng mạnh cả về tính hiệu quả lẫn tính đơn giản của nó. Aristomachus bắt đầu từ một phân số khách quan, gần đúng với căn bậc hai: 7/5. Sau đó, tôi đảo ngược phân số, biến nó thành nghịch đảo (5/7) và nhân nó với hai (10/7). Phân số thu được là một phép tính gần đúng khác với căn bậc hai; Aristomachus tin rằng kết quả tốt nhất sẽ là điểm trung gian giữa hai phép tính gần đúng và đây chính là kết quả. Nhận được kết quả, tôi lặp lại quá trình. Phương pháp rất đơn giản: nhân đôi phân số nghịch đảo và tìm kết quả. Kết quả thật tuyệt vời.

Markov Chikot. Giết Pythagoras

Cách đếm số $\sqrt{2}$ đến mười chữ số thập phân mà không cần máy tính

Aristomachus là học trò huyền thoại của Pythagoras; chính ông là người có công phát hiện ra căn bậc hai là một số vô tỉ. Xét về thuật ngữ Hy Lạp cổ đại, kết quả của ông gần với hình học hơn là đại số. Ông phát hiện ra rằng đường chéo của hình vuông và cạnh của nó không cân xứng. Khám phá đáng tiếc này đã đặt dấu chấm hết cho ý tưởng ban đầu của Pythagoras rằng thế giới được thống trị bởi các số tự nhiên. Theo truyền thuyết, vì hành động lật đổ nền tảng như vậy, Aristomachus đã bị những người theo trường phái Pythogoreans của mình hành quyết. Cốt truyện nhận được một cách giải thích bất ngờ trong truyện trinh thám lịch sử gần đây “Kill Pythagoras” của Markov Chikot. Obya-
DOI: https://doi.org/10.4213/kvant20250902

Hãy nhớ đọc nó sau khi bạn tròn 18 tuổi. Tuy nhiên, cuộc thảo luận hiện nay không phải về chủ nghĩa obirational mà là về cách tính nhanh số $\sqrt{2}$ với độ chính xác rất cao. Đây chính xác là những gì bản văn nói về.

Hãy bắt đầu với xếp hạng rõ ràng nhất từ ​​trên xuống dưới: $1 < \sqrt{2} < 2$. Aristomakh tại Markov Chikota bắt đầu với 7/5, nhưng đây không phải là phép tính gần đúng rõ ràng nhất - để có được nó, bạn cần phải tính toán điều gì đó. Ý tưởng cơ bản là thế này: nếu đã có được hai phép tính gần đúng, một từ trên và một từ dưới, thì chúng ta có thể lấy những gì chúng ta nhận được và hy vọng rằng bằng cách này, chúng ta sẽ có được xấp xỉ tốt hơn. Nói cách khác, nếu $a < \sqrt{2} < b$ thì giá trị gần đúng tiếp theo sẽ là $\frac{a+b}{2}$. Phép tính gần đúng tiếp theo này - hãy biểu thị nó bằng $c$ - tiếp cận nghiệm từ một phía (từ trên hoặc dưới), nhưng sau đó $2/c$ là xấp xỉ từ phía đối diện. Do đó, nếu chúng ta bắt đầu với một cặp số $\{a, b\}$, thì số $\sqrt{2}$ được tiếp cận ở cả hai vế, thì có thể lấy cặp tiếp theo $\left\{\frac{a+b}{2}, \frac{4}{a+b}\right\}$, và nói chung, phép tính gần đúng mới này tốt hơn phép tính gần đúng cũ. Ví dụ: nếu ban đầu $ab = 2$, thì chúng ta thay thế các số $a$ và $b$ bằng trung bình đối số và trung bình điều hòa của chúng: cả hai trung bình đều nằm trên đoạn $[a;b]$ và do đó chúng ta thu được một phân đoạn nhỏ hơn $[a';b']$, vẫn chứa nghiệm mong muốn. Ngoài ra, sự tương ứng $ab = 2$ có thể diễn giải được, tức là lặp lại quy trình tương tự cho đến khi chất lượng của phép tính gần đúng đạt yêu cầu.

⟦folio 12⟧

---
running_head:
folio:
---

$$a_1 = 1, b_1 = 2,$$
$$a_{n+1} = \frac{a_n + b_n}{2}, b_{n+1} = \frac{4}{a_n + b_n}.$$

Không khó để tính các giá trị của $a_n, b_n$ cho một vài $n$ đầu tiên. Điều này có thể được thực hiện ngay cả bằng tay của bạn mà không cần máy tính. Viết kết quả tính toán dưới dạng bảng:

| $n$ | 1 | 2 | 3 | 4 | 5 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| $a_n$ | 1 | 3/2 | 17/12 | 577/408 | 665857/470832 |
| $b_n$ | 2 | 4/3 | 24/17 | 816/577 | 941664/665857 |

Việc đánh giá độ chính xác của các phép tính gần đúng thu được dựa trên thực tế là nghiệm luôn nằm giữa $a_n$ và $b_n$ – do đó, độ lớn sai số trong ước tính trên là khoảng cách giữa $a_n$ và $b_n$. Dựa trên những thông báo này, chúng tôi thấy rằng phép tính gần đúng thứ tư đã cho năm chữ số thập phân chính xác và phép tính gần đúng thứ năm - tất cả đều giống nhau. Nói chung có thể chứng minh rằng tốc độ hội tụ là cực kỳ nhanh. Nói một cách đại khái, số lượng vị trí thập phân hợp lệ sẽ tăng gấp đôi ở mỗi bước.

Lưu ý rằng theo định nghĩa $b_n = 2/a_n$, và do đó chỉ cần xem xét một chuỗi $a_n$ là đủ. Trình tự này có thể được xác định bằng mối quan hệ lặp lại

$$a_1 = 1, a_{n+1} = \frac{a_n}{2} + \frac{1}{a_n}.$$

Bây giờ chúng ta hãy thảo luận về một phương pháp tổng quát hơn để tìm các giá trị gần đúng liên tiếp của lời giải của các phương trình nhất định, một trường hợp đặc biệt vừa được viết ra. Phương pháp này thuộc về Isaac Newton và mang tên ông: Phương pháp Newton.

Chúng ta muốn tìm lời giải $x_0$ của phương trình $f(x) = 0$ và chúng ta có một giá trị gần đúng ban đầu $x_1$ với nghiệm mong muốn $x_0$. Nói chung, phương pháp này chỉ hoạt động nếu chúng ta đoán đủ tốt với xấp xỉ ban đầu. Nếu hàm $f$ khả vi thì ở gần điểm $x_1$ giá trị $f(x)$ có thể được viết là

$$f(x) = f(x_1) + f'(x_1)(x - x_1) + \ldots,$$

trong đó $f'(x_1)$ là tích tại điểm $x_1$ và đa thức biểu thị các số hạng nhỏ so với $x - x_1$.

Xét hàm tuyến tính của $x$

$$g(x) = f(x_1) + f'(x_1)(x - x_1).$$

Trong quá trình phân tích toán học, người ta đã chứng minh rằng hàm này xấp xỉ hàm $f$ trong vùng lân cận của điểm $x_1$ tốt hơn tất cả các hàm tuyến tính khác. Các hệ số $f(x_1), f'(x_1)$ của hàm này là các số phụ thuộc vào $x_1$ nhưng không phụ thuộc vào $x$. Do đó, đạo hàm $f'(x_1)$ là độ dốc của phép tính gần đúng tuyến tính tốt nhất.

Ý tưởng của phương pháp Newton rất đơn giản, giống như mọi thứ thiên tài. Hàm $f$ có thể rất phức tạp - phức tạp đến mức người ta thậm chí không thể hiểu rõ làm thế nào người ta có thể tham gia vào phương trình lời giải rõ ràng. Mặt khác, bất kỳ phương trình tuyến tính nào cũng không khó giải một cách rõ ràng và hàm $f$ có ​​thể được thay thế bằng phép tính gần đúng tuyến tính của nó với độ chính xác nhất định. Ví dụ: nếu đã đạt được giá trị gần đúng tiếp theo $x_n$ ở bước $n$ thì bước tiếp theo là thay thế phương trình phi tuyến $f(x) = 0$ bằng phương trình tuyến tính

$$f(x_n) + f'(x_n)(x - x_n) = 0.$$

Cái sau hóa ra đủ gần với cái trước nếu $x_n$ gần với $x_0$. Chúng ta biểu thị Lời giải của phương trình tuyến tính bằng $x_{n+1}$ và tiếp tục quá trình theo sơ đồ tương tự. Ta thu được dãy $x_n$ thỏa mãn hệ thức truy hồi

$$x_{n+1} = x_n - \frac{f(x_n)}{f'(x_n)}.$$

Chúng ta hãy biểu thị bằng $N_f$ hàm được xác định bởi công thức

$$N_f(z) = z - \frac{f(z)}{f'(z)}.$$

Hàm này phụ thuộc vào $f$, được phản ánh trong ký hiệu; nó được gọi là `отображением Ньютона` cho $f$. Việc tìm các giá trị gần đúng với nghiệm của phương trình $f(x) = 0$ cho thấy, nhờ phương pháp của Newton, việc áp dụng lặp lại cùng một phép toán

$$z \mapsto N_f(z).$$

Nếu hàm $f$ được cho bằng một công thức đơn giản thì $N_f$ không quá phức tạp. Hãy đặt nó lại với nhau

⟦folio 13⟧

---
running_head:
folio:
---

nếu $f$ là đa thức thì $N_f$ là hàm hữu tỉ, tức là tỷ số của hai đa thức. Đối với hàm $f(x) = x^2 - 2$, người ta có thể kiểm tra xem quán tính của bản đồ $N_f$ có cho tổng của chuỗi các phép tính gần đúng với nghiệm của hai, đã được thảo luận ở trên hay không.

Markov Chikot đã khám phá lại phương pháp của Newton và ngạc nhiên trước sự đơn giản của nó, ông đã truyền ý tưởng này vào những anh hùng của mình - những người theo trường phái Pythagore. Tuy nhiên, nó không hoàn toàn xa với tính chính xác lịch sử. Một trường hợp đặc biệt của phương pháp Newton áp dụng để tìm căn bậc hai được biết đến là Heron, người sống vào thế kỷ thứ nhất hoặc thứ hai sau Công nguyên ở Alexandria (một thành phố ở Ai Cập, lúc đó là một phần của Đế chế La Mã). Công thức tính diện tích hình tam giác dựa trên các cạnh của Heron là công thức nổi tiếng nhất hiện nay, nhưng không phải là thành tựu duy nhất của nhà toán học, vật lý và kỹ sư này. Ông cũng phát minh ra động cơ hơi nước và cơ chế được sử dụng trong đài phun nước ngọt - ở Alexandria vào thế kỷ thứ hai có những chiếc máy tương tự ở lối vào ngôi đền và bất kỳ ai cũng có thể nhét một đồng xu vào và lấy một phần nhỏ nước thánh.

Tuy nhiên, có bằng chứng cho thấy phương pháp tính gần đúng căn bậc hai đã nêu thậm chí còn có nguồn gốc xa xưa hơn - bảng đất sét Babylon cổ YBC 7289 (từ năm 1800 đến năm 1600 trước Công nguyên) chứa giá trị $\sqrt{2}$, được tính bằng các chữ số thập phân lục thập phân. Giá trị này có thể thu được bằng phương pháp của Newton. Không phải vô cớ mà phương pháp chiết rễ này được gọi là “Babylon” vào thời cổ đại.

Tại sao và làm thế nào để làm việc

Chúng ta hãy thảo luận chi tiết hơn về phương pháp của Newton vì nó áp dụng để tìm căn bậc hai với độ chính xác nhất định. Cụ thể, chúng tôi muốn hiểu mức độ tiến gần đến gốc mong muốn trong $n$ bước. Chúng ta sẽ xem xét phương trình ở vế trái $f(x) = x^2 - a$ cho một hành động tùy ý có giá trị không âm $a$. Đồ thị của hàm $f(x)$ là một parabol. Nó cắt trục $x$ tại hai điểm hoặc, nếu $a = 0$, tại một nhiều điểm. Phương pháp của Newton cho phép mô tả hình học như sau. Hãy bắt đầu với một điểm tùy ý $x_1$. Chúng ta vẽ một tiếp tuyến của đồ thị hàm số $f(x)$ tại điểm $(x_1; f(x_1))$ (hình 1). Chúng ta hãy biểu thị bằng $x_2$ điểm chuyển tiếp

Hình1. Phương pháp Newton cho phương trình bậc hai trên số thực

các phần của tiếp tuyến này với trục $x$ rồi lặp lại thao tác tương tự với $x_2$ cùng với $x_1$. Kết quả của quá trình lặp lại được mô tả là sẽ thu được chuỗi điểm $x_1, x_2, \dots, x_n$....

Nếu chúng ta bắt đầu ở bên phải của nghiệm mong muốn, tức là từ điểm $x_1 > \sqrt{a}$, thì chuỗi điểm $x_n$ sẽ chết một cách đơn điệu khi $n$ tăng lên, rất giống với mô tả hình học của phương pháp Newton. Và nếu điểm ban đầu $x_1$ nằm trên khoảng $(0; \sqrt{a})$, thì đầu tiên chúng ta nhận được điểm $x_2 > \sqrt{a}$, sau đó là một chuỗi giảm dần đơn điệu $x_2, x_3, \dots$. Do đó, trong mọi trường hợp giá trị ban đầu $x_1$ được chọn là dương, thì các số hạng của dãy $x_n$ sẽ nằm ngày càng gần gốc mong muốn, bắt đầu từ số hạng thứ hai. Tôi muốn ước tính chính xác hơn khoảng cách từ $x_n$ đến $\sqrt{a}$. Với mục đích này, hãy xem xét chuỗi $u_n = x_n / \sqrt{a}$. Biết cách đánh giá trình tự $x_n$, chúng ta có thể tìm thấy mối quan hệ truy hồi cho $u_n$. Thật vậy, bản đồ Newton $N_f(z)$ trong trường hợp này có dạng

$$N_f(z) = z - \frac{z^2 - a}{2z} = \frac{z}{2} + \frac{a}{2z},$$

Có nghĩa,

$$x_{n+1} = \frac{x_n}{2} + \frac{a}{2x_n}.$$

⟦folio 14⟧

---
running_head:
folio:
---

Từ đó chúng ta thu được $u_{n+1} = u_n/2 + 1/(2u_n)$,
những thứ kia. chuỗi $u_n$ thu được bằng phương pháp Newton cho phương trình $x^2 - 1 = 0$.
Tuy nhiên, điều này có thể được nhìn thấy mà không cần bất kỳ tính toán nào. Chúng ta hãy áp dụng sự lăn hoặc kéo dài đều theo mọi hướng với hệ số $a^{-1/2}$ cho đồ thị hàm số $f(x) = x^2 - a$. Với phép biến đổi này, đồ thị sẽ chuyển thành đồ thị của hàm số $f_1(x) = x^2 - 1$ và mô tả hình học của phương pháp Newton sẽ không thay đổi: các đường tiếp tuyến sẽ trở thành đường tiếp tuyến.

Vì vậy, chỉ cần xem xét phương pháp của Newton cho $f_1$ là đủ. Từ quan điểm thu được đáp số, điều này không thú vị chút nào: chúng ta đã biết $\sqrt{1}$ bằng bao nhiêu. Nhưng mặt khác, bản chất sự hội tụ của phương pháp Newton đối với một giá trị tùy ý của số $a$ không thay đổi nếu chúng ta đặt $a = 1$.

Để viết rõ ràng $u_n$ dưới dạng hàm của $u_1$, chúng ta cần thêm một phép thay thế nữa. Hãy xem xét sự chuyển đổi

$$h(u) = \frac{u - 1}{u + 1},$$

mà “gửi” các nghiệm của phương trình $f_1 = 0$ đến trường và vô cực: $h(1) = 0$, $h(-1) = \infty$. Hãy đặt $v_n = h(u_n)$, sau đó

$$v_{n+1} = \frac{u_n + u_n^{-1} - 2}{u_n + u_n^{-1} + 2} = \frac{(u_n - 1)^2}{(u_n + 1)^2} = v_n^2.$$

Ở đây trong đẳng thức đầu tiên, chúng ta đã sử dụng $v_{n+1} = h(u_{n+1})$ được xác định, cũng như sự tương ứng lặp lại cho $u_n$; đẳng thức thứ hai thu được bằng cách biến đổi đơn giản giống hệt các công thức.

Ta thấy rằng $v_n$ thỏa mãn sự tương ứng lặp lại rất đơn giản

$$v_{n+1} = v_n^2.$$

Biết $v_1$, giờ đây người ta có thể dễ dàng tìm thấy $v_n$ tùy thuộc vào $n$, cụ thể là $v_n = v_1^{2n-1}$. Quay lại $u_n$ và $x_n$, ta thu được các công thức sau:

$$u_n = h^{-1} \left( h(u_1)^{2n-1} \right),$$

$$x_n = \sqrt{a} h^{-1} \left( h \left( x_1 / \sqrt{a} \right)^{2n-1} \right).$$

Ở đây $h^{-1}$ biểu thị phép biến đổi nghịch đảo với phép biến đổi $h$, tức là một phép biến đổi có thuộc tính sau: nếu bạn áp dụng $h$ trước, rồi $h^{-1}$ hoặc trước $h^{-1}$, rồi $h$, thì bạn cũng sẽ nhận được một phép biến đổi con.

Tất nhiên, người ta có thể viết ra công thức của $h^{-1}$ một cách rõ ràng và thu được một biểu thức rõ ràng hơn nữa cho $x_n$ (chúng tôi khuyên người đọc nên làm điều này). Tuy nhiên, không khó để nhận thấy ngay cả khi không có bất kỳ tính toán nào rằng cả việc áp dụng phép biến đổi $h$, cũng như việc áp dụng sự lăn hoặc kéo dài đều đều không có ảnh hưởng đáng kể đến tốc độ lặp lại liên tiếp của phương pháp Newton có xu hướng đến giá trị giới hạn. Đầu tiên, chúng tôi xây dựng ước tính về các đặc điểm và tốc độ hội tụ cho $v_n$, sau đó chuyển kết quả này sang chuỗi $x_n$.

**Định lý.** Nếu $|v_1| < 1$, thì chuỗi $v_n$ hội tụ về 0 cực nhanh theo hàm mũ, m.e. nhanh hơn bất kỳ phép cắt hình học nào. Nếu $|v_1| > 1$, thì chuỗi $v_n$ sẽ thoát ra vô cực với tốc độ siêu cấp số nhân. Cuối cùng, nếu $|v_1| = 1$, thì chuỗi $v_n$ không hội tụ về 0 cũng như không hội tụ về vô cùng.

Đây là kết quả rút ra từ định lý này khi chuyển từ $v_n$ sang $x_n$.

**Hệ quả tất yếu.** Nếu $x_1 > 0$ thì chuỗi $x_n$ hội tụ về $\sqrt{a}$ siêu nhanh theo cấp số nhân và nếu $x_1 < 0$ thì chuỗi $x_n$ hội tụ về $-\sqrt{a}$ siêu nhanh theo cấp số nhân. Và chỉ khi $x_1 = 0$, chuỗi $x_n$ không được xác định (hoặc chúng ta có thể đặt $x_2 = \infty$ và tất cả các số hạng tiếp theo có thể bằng $\infty$).

Xin lưu ý: điểm ban đầu duy nhất $x_1$ mà không thể tính gần đúng nghiệm bằng phương pháp của Newton là điểm $x_1 = 0$, tức là chính xác ở giữa hai nghiệm. Phương pháp của Newton, được đưa ra từ thời điểm này, hóa ra là ở trạng thái con lừa Buridan, tức là không thể chọn nghiệm nào trong hai nghiệm để hội tụ về. Sự hội tụ của phương pháp Newton, nếu nó xảy ra, là cực kỳ

⟦folio 15⟧

---
running_head:
folio:
---

tự phát. Phân tích cẩn thận hơn về các công thức cho thấy rằng ở mỗi bước của phương pháp Newton, số chữ số thập phân chính xác gần như có thể quản lý được. Ví dụ: nếu số $v_n$ gần đúng với số 0 có dấu trùng khớp, tức là $v_n$ được viết là “số không, dấu phẩy, một trăm số không và sau đó, có lẽ là một số số khác,” thì số $v_{n+1} = v_n^2$ được viết là “số không, dấu phẩy, hai trăm số không, và sau đó, có lẽ là một số khác”.
Một phân tích về phương pháp Newton cho phương trình bậc hai được thực hiện bởi Arthur Cayley, một nhà toán học người Anh thế kỷ 19. Tốt nghiệp loại xuất sắc tại Cambridge, Cayley đã tích cực hành nghề luật trong hai mươi năm và chỉ ở tuổi 42 mới nhận được một vị trí học thuật, điều này khiến lương của ông bị giảm đáng kể. Cayley đã có những đóng góp đáng kể cho một số lượng lớn các lĩnh vực toán học, ông đã viết hơn 400 bài báo khoa học, khoảng một nửa trong số đó xảy ra trong giai đoạn cuộc đời ông phải kết hợp các hoạt động khoa học và pháp lý của mình.

Một số có hình vuông tận cùng là 987654321

Hãy xem xét bài toán điều này: tìm một số tự nhiên $k$ sao cho trong ký hiệu thập phân của số $k^2$ 9 chữ số cuối là 987654321. Trong bài toán này, bạn có thể đoán đáp số, sau đó căn chỉnh nó dựa trên các thông báo chung, nhưng chúng tôi sẽ tiến hành một cách có hệ thống hơn và các phương pháp mà chúng tôi đã xem xét sẽ không chỉ hiệu quả với tập hợp chữ số cụ thể này. Xét bài toán từ lĩnh vực số học, dường như nó không liên quan gì đến chủ đề tính toán gần đúng nói chung và phương pháp Newton nói riêng. Tuy nhiên, nó được kết nối và trực tiếp nhất. Bạn chỉ cần diễn giải thuật ngữ “xấp xỉ” một cách sáng tạo.

Tiếp cận là một từ có cùng gốc từ là “sự gần gũi”. Nói một cách tổng quát, hai số gần nhau nếu có nhiều chữ số giống nhau ở đầu ký hiệu thập phân của chúng. Chúng ta sẽ cần một cách hiểu không chuẩn về độ gần: hai số tự nhiên là gần nhau nếu khai triển thập phân của chúng có nhiều chữ số giống nhau, tức là (giống nhau) nếu hiệu của hai số đã cho chia hết cho lũy thừa lớn hơn mười. Sau đó, bài toán đặt ra có thể được biểu diễn lại như sau: tìm một số tự nhiên $k$ có bình phương thập phân gần với số $b = 987654321$.

Khi chúng tôi cố gắng tìm gần đúng các nghiệm của phương trình $x^2 - a = 0$ bằng phương pháp của Newton, chúng tôi thực sự đang thực hiện nhiệm vụ sau: tìm số $x$ có bình phương gần với $a$ theo nghĩa thông thường. Bây giờ chúng ta muốn tìm số $k$ có bình phương gần với $b$ theo nghĩa thập phân. Do đó, có thể thấy sự tương đồng giữa hai bài toán và chúng ta có thể cố gắng tìm ra sự tương tự của lời giải với số học bài toán.

Bạn cần bắt đầu với một số phép tính gần đúng, chẳng hạn như với một số có bình phương kết thúc bằng 1. Trong trường hợp của chúng ta, chúng ta có thể lấy $k_1 = 1$. Tiếp theo, chúng ta sẽ tìm giá trị gần đúng tiếp theo $k_2$ sao cho $k_1 - k_2$ chia hết cho 10 và sao cho số $k_2^2$ là 21. Chúng ta hãy viết $k_2$ là $k_1 + 10m_1$, sau đó

$$k_2^2 = k_1^2 + 20k_1m_1 + \dots,$$

trong đó dấu chấm lửng biểu thị các số hạng ở cấp độ nhỏ tiếp theo (tất nhiên là theo nghĩa thập phân!) so với những gì đã được viết. So sánh công thức này với khai triển

$$f(x) = f(x_1) + f'(x_1)(x - x_1).$$

Chúng tôi muốn $k_2^2$ gần bằng 21 và do đó yêu cầu phải thỏa mãn $k_1^2 + 20k_1m_1 = 21$ modulo 100, tức là sao cho hiệu giữa bên trái và bên phải chia hết cho 100. Trong trường hợp của chúng tôi, hóa ra $20m_1 = 20$ modulo 100 hoặc $m_1 = 1$ modulo 5. Ví dụ: $m_1 = 1$ phù hợp với chúng tôi. Vì vậy, phép tính gần đúng tiếp theo là $k_2 = 11$ và bình phương của số này thực sự kết thúc ở 21. Sự tương tự giữa quá trình được mô tả với phương pháp của Newton là hiển nhiên. Quá trình có thể được tiếp tục: chúng ta tìm kiếm $k_3$ ở dạng $k_2 + 100m_2$ và yêu cầu đẳng thức $k_2^2 + 200k_2m_2 = 321$ phải được thỏa mãn modulo

⟦folio 16⟧

---
running_head:
folio:
---

1000. $m_2 = 1$ lại tốt, tình trạng này sẽ lặp lại. Sau 9 bước, chúng ta sẽ tìm được giá trị gần đúng $k_9 = 111111111$ có bình phương kết thúc là $b$. Tuyên bố cuối cùng này không khó chứng minh nếu không có phương pháp của Newton.

Tất nhiên, trước lời giải $k = 111111111$, một thỏa thuận là có thể xảy ra. Nhưng đây là một lời giải khác thu được bằng phương pháp của Newton: $k = 380642361$. Nó dựa trên thực tế là không chỉ 1 mà cả 6 cũng phù hợp là $m_1$. Thật không may, và không giống như phương pháp cổ điển của Newton, phương pháp thập phân của Newton không phải lúc nào cũng được tiếp tục - ngay cả khi có thể thực hiện được một vài bước đầu tiên, thì cũng có thể không thể thực hiện được bước tiếp theo. Khả năng không thể tiếp tục liên lạc với những gì modulo 10 không phải lúc nào cũng có thể thực hiện được; ví dụ: không thể thực hiện điều đó trên 2 và 5, tức là giải phương trình $2x = b$ hoặc $5x = b$ modulo 10. Điều này là do 10 không phải là số nguyên tố. Tình hình sẽ được cải thiện nếu thay vì khai triển số thập phân, chúng ta xem xét khai triển đến cơ số của số nguyên tố $p$. Tương tự, độ gần thập phân được xác định bởi độ gần $p$-adic, phát biểu này được gọi là bổ đề Hanselai.

Một vài quan sát thêm

Chúng ta hãy quay lại phương pháp của Newton đối với số thực và thậm chí cụ thể là phép tính $\sqrt{2}$. Có một cách cổ điển khác để tính số này - thông qua các phân số liên tục, tức là dưới dạng giới hạn của chuỗi

$$x_n = 1 + \frac{1}{2 + \frac{1}{2 + \frac{1}{\ddots + \frac{1}{2}}}}$$

$^1$ Bạn có thể tìm hiểu thêm về khoảng cách $p$-aditsa và số $p$-aditsa từ bài viết [1]. Chúng tôi cũng khuyên bạn nên thay thế cuốn sách [2].

(quy tắc phần được viết $n$ twos), có thể được chỉ định tương đương bởi sự tương ứng hiện tại $x_{n+1} = 1 + \frac{1}{1 + x_n}$ với điều kiện ban đầu $x_0 = 1$. Tại sao chuỗi này hội tụ đến $\sqrt{2}$ và nhanh như thế nào? Điều này có thể được hiểu bằng cách sử dụng cùng một phép thay thế $v = \frac{x - \sqrt{2}}{x + \sqrt{2}}$ đã được mô tả ở trên. Ý nghĩa của việc thay thế là các gốc $x = \pm \sqrt{2}$ được gửi đến $v = 0, \infty$ và bản đồ Newton được viết là $v \mapsto v^2$. Chuỗi $x_n$ trở thành chuỗi $v_n$ và trận đấu hiện tại trên $x_n$ được viết lại như sau theo $v_n$:

$$v_{n+1} = \lambda v_n, \quad v_0 = \lambda, \quad \lambda = \frac{1 - \sqrt{2}}{1 + \sqrt{2}},$$

từ đó nó ngay lập tức theo sau $v_n = \lambda^{n+1}$. Số $\lambda$ là số âm và có modulo nhỏ hơn một. Điều này có nghĩa là chuỗi $v_n$ hội tụ về 0 theo cấp số nhân với các dấu xen kẽ - nghĩa là $x_n$ có xu hướng $\sqrt{2}$ theo tỷ lệ cấp số nhân, với giá trị $x_n - \sqrt{2}$ liên tục thay đổi dấu khi $n$ tăng thêm một. Bản đồ của Newton theo biến $v$ hoạt động giống như bình phương, và do đó gửi $v_n$ đến $v_{2n+1}$—thực sự, nếu $v_n = \lambda^{n+1}$ thì $v_n^2 = \lambda^{2n+2} = v_{2n+1}$. Chúng ta có thể kết luận, quay lại biến $x$, rằng $N_f(x_n) = x_{2n+1}$, tức là đạt được số hai ở mỗi lần lặp lại phương pháp Newton. Lưu ý rằng sẽ khó có được kết luận này hơn bằng cách tính toán trực tiếp trên biến ban đầu $x$.

Bây giờ chúng ta hãy thảo luận xem tốc độ hội tụ của phương pháp Newton có thể phụ thuộc vào điều gì. Chúng ta có thể giả sử không mất tính tổng quát rằng nghiệm cần tìm nằm ở điểm 0. Giả sử rằng hàm $f$ có thể được viết gần 0 bằng các công thức có dạng $f(x) = x^k g(x)$, trong đó $k$ là số dương và $g$ là hàm chứa $g(0) \neq 0$. Nếu $f$ là đa thức hoặc ít nhất khả vi đủ nhiều lần

⟦folio 17⟧

---
running_head:
folio:
---

chức năng của tôi, thì điều này luôn có thể thực hiện được,
và $k$ sẽ là số nguyên; chúng ta nên thảo luận
Tuy nhiên, chúng tôi cũng xem xét trường hợp số mũ phân số $k$. Chúng ta sẽ giả định rằng đạo hàm
hàm $g$ tồn tại trong vùng lân cận bằng 0,
không tính điểm 0 và không nguyên tố tại
khu phố bị thủng này. Sau đó từ
Phương trình Newton có thể được viết là

$$N_f(x) = x - \frac{f(x)}{f'(x)} = x \frac{(k-1)g(x) + xg'(x)}{kg(x) + kg'(x)}$$

Nếu $k = 1$, thì phần bên phải chia hết cho $x^2$, và vì lý do này, chúng ta kỳ vọng rằng $N_f(x)$ đối với $x$ nhỏ sẽ có cùng thứ tự với $x^2$, tức là độ hội tụ của phương pháp Newton sẽ nhanh như trong trường hợp căn bậc hai: số chữ số thập phân đúng sẽ gần gấp đôi sau mỗi lần lặp. Tuy nhiên, ở $k \neq 1$ sự hội tụ nhanh như vậy sẽ không còn xảy ra nữa.

Ví dụ: hãy xem xét hàm $f(x) = x^2$ (hình 2). Đối với chức năng này,

$$f(x) = x^2$$

Hình 2. Phương pháp Newton cho $f(x) = x^2$

hóa ra $N_f(x) = x/2$. Khi thao tác này được lặp lại nhiều lần, sẽ thu được một chuỗi các điểm hội tụ về 0, nhưng bây giờ chỉ theo cấp số nhân: cần 3-4 lần lặp để đạt được mỗi chữ số thập phân tiếp theo.

Nói chung, nếu $g(x) = 1$ thì $N_f(x) = \frac{k-1}{k}x$.

Khi $k > 1$ tăng, hệ số tại $x$ tăng
biến mất, còn lại trong khoảng $(0;1)$, và
tiến tới 1 tại $k \rightarrow \infty$. Đạo đức là: hơn

$k$ càng lớn thì phương pháp Newton hội tụ càng kém. Giá trị tự nhiên $k > 1$ tương ứng
tương ứng với *nhiều gốc*, tức là vì lý do này
trà, khi một số rễ được hợp nhất vào
một. Nhiều gốc nên được xem xét
được sử dụng như biểu hiện: niềm tin rằng
rằng một hàm được chọn ngẫu nhiên
tion sẽ tiết lộ nhiều gốc, bằng 0.
Vì vậy, sự suy giảm tính hội tụ
nhân vật đặc biệt và cuộc gặp gỡ
chỉ xảy ra trong các tình huống suy biến.

Nếu lấy $k = 1/3$ thì điều này còn “đáng sợ” hơn
new" biểu thức: hàm $f(x)$ nói chung
sẽ không khả vi tại điểm 0.
Mặc dù những tính năng như vậy đôi khi có thể
xảy ra trong bối cảnh tự nhiên, nói
zhem, trong các mô hình toán học bài toán es-
kiểm tra kiến ​​thức, đánh vào các tính năng của
mo vào thư mục gốc mong muốn - một danh sách đáng kinh ngạc
mới không cắt. Nhưng điều quan trọng vẫn là phải xem xét
đối xử với loại tình huống này như
kontriprimera. Đối với chức năng $f(x) = \sqrt[3]{x}$
Bản đồ của Newton $N_f(x) = -2x$ nói chung
không xấp xỉ bất kỳ giá trị ban đầu nào khác 0
giá trị cho gốc mong muốn, và ngược lại,
miệng, đưa anh ta nhanh theo cấp số nhân
vô cực (hình 3). Tiếp theo

Hình 3. Phương pháp Newton cho $f(x) = \sqrt[3]{x}$

các lần lặp trông giống như một chuỗi “transfer-
tov" (mỗi chuyến bay mới lại tệ hơn nhiều
trước).

Trên những con số đầy đủ

Lịch sử, số đầy đủ
đã được thảo luận do cần phải xem xét
tạo ra các phương trình thực tế
các số không có lời giải. Tại-

⟦folio 18⟧

---
running_head:
folio:
---

số đo của phương trình đó: $x^2 + 1 = 0$. Không có giá trị thực nào của $x$ mà phương trình sẽ đúng. Thật thú vị khi xem phương pháp của Newton làm được gì trong trường hợp này. Phương pháp của Newton cố gắng tìm ra các gốc rễ, nhưng không có gốc rễ nào cả. Kết quả là *diapamic hỗn loạn*, tức là các chuỗi điểm thu được từ việc áp dụng phương pháp Newton không hiển thị bất kỳ khuôn mẫu rõ ràng nào mà hành xử như thể ngẫu nhiên.

Ký hiệu $x^2 + 1$ bằng $f_{-1}(x)$, chúng ta xây dựng một số tính chất của bản đồ Newton $N = N_{f-1}$.

• Có thể chọn một giá trị ban đầu $x_1$ mà chuỗi lặp lại $x_n$, được cho bởi $x_{n+1} = N(x_n)$ tương ứng, tiếp cận theo góc gần với bất kỳ số thực nào, tức là với mọi $a \in \mathbb{R}$ và mọi $\varepsilon > 0$ đều có $n$ với thuộc tính $a - \varepsilon < x_n < a + \varepsilon$.

• Với mọi số tự nhiên $m > 0$ đều có một giá trị ban đầu $x_1$ mà dãy $x_n$ tuần hoàn với dấu chấm $m$, tức là $x_{n+m} = x_n$ với tất cả $n \ge 1$.

• Nếu $x_1$ chỉ được biết với độ chính xác nhất định thì không thể nói gì về $x_n$ đối với $n$ lớn: bất kỳ vùng lân cận nào của bất kỳ điểm đã cho nào $c \in \mathbb{R}$, dù có góc nhỏ đến đâu, sẽ được ánh xạ dưới tác động của phép lặp đủ cao của bản đồ $N$ trên toàn bộ đường thẳng.

Chúng tôi để lại cho bạn đọc việc chứng minh các tính chất này như một bài tập không hề đơn giản.

Từ thời điểm này trở đi, chúng ta chuyển từ số thực sang số phức trong một số phức. Việc giải phương trình trên số phức rất hữu ích. Hơn nữa, trong mặt phẳng số phức, phần lớn những điều trên đã được đơn giản hóa. Ví dụ, các đa thức thực có cùng bậc có thể có số nghiệm khác nhau và một số đa thức có bậc cao, chẳng hạn như bậc 100, không có nghiệm nào cả. Các đa thức phức luôn có nghiệm và số của chúng (kể cả bội số) luôn bằng bậc của đa thức. Điều này có nghĩa là với sự thay đổi trơn tru trong các hệ số của đa thức ở một mức độ nhất định, các nghiệm của nó có thể hợp nhất (đi xuyên qua nhau), nhưng không thể xuất hiện đột ngột và không thể biến mất không dấu vết. Tuyên bố rằng một đa thức bậc $d > 0$ luôn có ít nhất một nghiệm được gọi là *định lý cơ bản của đại số*. Chúng ta sẽ không thảo luận về cách chứng minh định lý sâu sắc này ở đây, nhưng lưu ý rằng phát biểu về số nghiệm có tính đến bội số là một hệ quả đơn giản của nó.

Để hiểu đầy đủ cách thức hoạt động của phương pháp Newton, nó cũng cần phải được chạy trên mặt phẳng số phức. Dưới đây chúng tôi mô tả cách hoạt động của phương pháp Newton đối với lời giải phương trình bậc hai $f(z) = 0$, tức là các phương trình có vế trái có dạng $f(z) = az^2 + bz + c$, $a \neq 0$. Mô tả này được thu thập bởi Arthur Cayley. Mặc dù không có bằng chứng nào được đưa ra, nhưng một người đọc có suy nghĩ sâu sắc sẽ có thể xây dựng lại nó và sử dụng các ý tưởng trong phần “Tại sao và cách làm việc”.

Một phương trình bậc hai có hai nghiệm khác nhau hoặc một nghiệm bội. Trước tiên, hãy giả sử rằng $f$ có gốc $\alpha \neq \beta$ (hình 4). Chúng ta hãy vẽ một đường thẳng $l$, một đoạn vuông góc có các đầu $\alpha$, $\beta$ và chia đoạn này làm đôi. Dòng $l$ này chia mặt phẳng của số phức thành hai nửa mặt phẳng, một trong số đó, $H_\alpha$, chứa gốc $\alpha$, và mặt kia, $H_\beta$, chứa gốc $\beta$. Nếu phép tính gần đúng ban đầu được chọn trong nửa mặt phẳng $H_\alpha$, thì việc lặp lại phương pháp

Hình 4. Phương pháp Newton cho phương trình bậc hai trên số phức

⟦folio 20⟧

---
running_head:
folio:
---

Hình 6. Lưu vực hấp dẫn của bản đồ Newton cho $f(z) = z^3 - 1$

bao gồm vô số diện tích. Có những điểm bên trong khu vực, tức là bên trong các lưu vực hấp dẫn, và cũng có những điểm mà các lưu vực khác nhau tích lũy - loại điểm sau được gọi là *thảm Jull*. Gần mỗi điểm Jull, và càng gần điểm đang nói đến càng tốt, có những khu vực nhỏ tùy ý nằm trong mỗi lưu vực trong số ba lưu vực. Trên hình người ta cũng có thể thấy một số điểm Jull đặc biệt, liền kề với 6 thành phần, cụ thể là 2 thành phần từ mỗi lưu vực.

Tập hợp tất cả các điểm Jull được gọi là *Tập hợp Jull* cho một bản đồ Newton cho trước. Bản đồ Newton cho phương trình bậc hai có hai nghiệm khác nhau biểu thị tập Jull dưới dạng hình chữ nhật. Và trong trường hợp phương trình bậc ba, tập Jull của bản đồ Newton tương ứng là một thực tế không tầm thường, tức là tập tự tương tự. Ý nghĩa của sự tự tương tự cần phải được làm rõ, vì nó không hẳn là sự tương tự theo nghĩa Euclide, mặc dù nó gần với nghĩa sau.

Thật không may, độ dài của bài viết không cho phép chúng ta đi sâu hơn vào thảo luận về vấn đề thú vị này. Lớn về sự tự tin

Hình 7. Phương pháp Newton cho $f(z) = z^3 - 2z + 2$
