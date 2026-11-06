---
id: 1990-5-sidorov-ob-odnom-zamechatelnom-uravnenii-30e1dd52
issue: kvant_1990_5
year: 1990
number: "5"
title: Về một phương trình tuyệt vời
authors:
  - Сидоров Ю. В.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 60
page_last: 64
page_labels: 58-62
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 06fa9f17839952524c8e0ed212ef53119a678a59404d3f69debbbaac2fbf01ee
prompt_sha256: draft-1
translated_from: content/ru/1990/05/articles/17_sidorov-ob-odnom-zamechatelnom-uravnenii-30e1dd52.md
source_content_sha256: 228bf07c989b141a46496bd3fc1209dd0c7b33593e618f082f4615aee55e83d5
translation_model: draft
translation_run: vi-draft-gaps-2026-11-05
translation_quality: draft
---

⟦folio 58⟧

---
running_head:
folio:
---

Về một phương trình tuyệt vời

Ứng viên Khoa học Vật lý và Toán học Y. SIDOROV

Hãy bắt đầu với bài toán, được đồn đại là đã từng được cấp cho một thí sinh trong kỳ thi tuyển sinh miệng.

Phương trình có bao nhiêu nghiệm?

$$\left( \frac{1}{16} \right)^x = \log_{\frac{1}{16}} x?$$

Nếu bạn vẽ phác họa đồ thị của các hàm $y = a^x$ và $y = \log_a x$ cho $0 < a < 1$ (hình 1), có vẻ như các đồ thị này nhất thiết phải giao nhau tại một điểm và điểm này nằm trên đường thẳng $y = x$.

Tuy nhiên, có thể thấy ngay rằng phương trình (1) có hai nghiệm: $x = \frac{1}{2}$ và $x = \frac{1}{4}$ (kiểm tra điều này bằng cách thay thế), và các giao điểm của đồ thị tương ứng với các nghiệm này không nằm trên đường thẳng $y = x$. Do đó, phương trình (1) có ít nhất ba nghiệm.

Thực tế này gây ngạc nhiên cho hầu hết học sinh tốt nghiệp trung học và thật không may, nhiều giáo viên, mặc dù bài toán đã khá “cũ” và thường được coi là một ví dụ cho thấy rằng phương pháp đồ họa lời giải của một phương trình phải hết sức thận trọng khi sử dụng. Bí mật của lời giải bài toán không chính xác rất đơn giản: hình 1 hiển thị các bản phác thảo rất thô của đồ thị và điều này dẫn đến kết luận sai về số nghiệm của phương trình (1).

hình 2 hiển thị các biểu đồ chính xác hơn được xây dựng bằng máy tính. Trong số này hình không

⟦folio 59⟧

---
running_head:
folio:
---

Có thể thấy phương trình (1) có bao nhiêu nghiệm, vì các đường cong không hoàn toàn mỏng và do đó trên thực tế hợp nhất ở một khoảng nào đó.

Các biểu đồ cho hình 3 cũng được xây dựng bằng máy tính. hình này đã cho thấy rõ rằng phương trình
$$\left(\frac{1}{64}\right)^x = \log_{\frac{1}{64}} x$$
có đúng ba gốc.

Nếu bạn sử dụng máy tính để xây dựng các biểu đồ giống nhau $y = \left(\frac{1}{16}\right)^x$ và $y = \log_{\frac{1}{16}} x$, ví dụ: chọn 100 cm làm đơn vị, thì cũng như với hình 3, bạn có thể thấy phương trình (1) có (chúng ta không có cơ hội đặt hình ở đây, do máy tạo ra) chính xác ba nghiệm. Tuy nhiên, không có máy tính nào có thể xây dựng được đồ thị hoàn toàn chính xác. Vì vậy, bằng chứng chỉ sử dụng hình không thể tin cậy được và cấu trúc suy luận toán học là cần thiết.

Ta nghiên cứu phương trình tổng quát:
$$a^x = \log_a x$$
cho các giá trị khác nhau của $a$ (tất nhiên, ở đây $a > 0, a \neq 1$).

Lưu ý rằng với mọi phương trình $a$ (2) đều tương đương với phương trình
$$a^{a^x} = x.$$

Cùng với phương trình (2'), ta xét phương trình
$$a^x = x.$$

Đặt $x_0$ là nghiệm của phương trình (3).

Khi đó $a^{a^x} = a^{x_0} = x_0$, tức là $x_0$ cũng là nghiệm của phương trình (2') và (2).

Vì vậy, nếu phương trình (3) có ít nhất một nghiệm thì phương trình (2) cũng có nghiệm.

Hãy đưa ra một nhận xét nữa. Tại $a > 1$ hàm $f(x) = a^x$ tăng. Phương trình (2') có thể được viết như sau: $f(f(x)) = x$ và phương trình (3) có dạng $f(x) = x$.

Bổ đề. Nếu hàm $y = f(x)$ tăng thì các phương trình $f(f(x)) = x$ và $f(x) = x$ là tương đương.

Bằng chứng. Đặt $x_0$ là nghiệm của phương trình $f(x) = x$. Khi đó $f(f(x_0)) = f(x_0) = x_0$, vậy $x_0$ là nghiệm của phương trình đầu tiên. Ngược lại, đặt $f(f(x_0)) = x_0$ và $x_0 \neq f(x_0)$. Sau đó là $x_0 > f(x_0)$ hoặc $x_0 < f(x_0)$ và vì hàm $f$ đang tăng lên nên chúng tôi thấy rằng trong trường hợp đầu tiên $f(x_0) > f(f(x_0)) = x_0$ và trong trường hợp thứ hai $f(x_0) < f(f(x_0)) = x_0$. Sự mâu thuẫn.

Từ bổ đề và nhận xét đưa ra trước đó, (2) tương đương với phương trình $a^x = x$.

Bài tập
1. Giải phương trình
$$2\sqrt{2x-1} = x^3 + 1.$$

2. Với mỗi giá trị của $a$, hãy giải phương trình
$$\sqrt{a + \sqrt{a + x}} = x.$$

Nghiên cứu phương trình $a^x = x$
Đầu tiên, chúng ta hãy xây dựng một định lý đáng chú ý đã được thảo luận trên tạp chí «Kvant».

Hình 1. Hình 2. Hình 3.

⟦folio 60⟧

---
running_head:
folio:
---

Định lý (Bolzano - Weierstrass). Nếu hàm $y = f(x)$ được xác định và liên tục trên khoảng $[a; b]$ và $f(a) < 0$, $f(b) > 0$, thì phương trình $f(x) = 0$ có nghiệm thuộc khoảng $(a; b)$.

Định lý này được chứng minh trong quá trình phân tích toán học. Tuy nhiên, ý nghĩa của nó rất rõ ràng: đường cong liên tục được hiển thị trong hình 4 nhất thiết phải cắt trục $Ox$. Chúng tôi sẽ sử dụng nó nhiều lần trong tương lai.

Cụ thể, nếu một hàm nhất định trả về hoặc hủy bỏ trên khoảng $[a; b]$, thì phương trình $f(x) = 0$ có một nghiệm duy nhất thuộc khoảng $(a; b)$.

Bây giờ hãy kiểm tra phương trình (3). Nó tương đương với phương trình

$$\ln a = \frac{\ln x}{x}.$$  (3')

Hãy vẽ đồ thị của hàm $h(x) = \frac{\ln x}{x}$. Vì $h' = \frac{1 - \ln x}{x^2}$, hàm $h$ trả về ở $x < e$ và hủy ở $x > e$, đồng thời tại điểm $x = e$ đạt tối đa là $\frac{1}{e}$ (hình 5, a). Do đó, phương trình (3') không có nghiệm nếu $\ln a > \frac{1}{e}$ (tức là tại $a > e^{\frac{1}{e}}$) và có một nghiệm duy nhất $x = e$ tại $a = e^{\frac{1}{e}}$. Bài tập

3. Chứng minh rằng với $0 < \ln a < \frac{1}{e}$, tức là với $1 < a < e^{\frac{1}{e}}$, phương trình (3') có đúng hai nghiệm.

4. Sử dụng đồ thị của hình 5 và chỉ ra rằng đồ thị của hàm $y = x^{\frac{1}{x}}$ có dạng như trong hình 5, b và kiểm tra phương trình $x^{\frac{1}{x}} = a$.

5. Vẽ đồ thị hàm $y = x^x$ và kiểm tra phương trình $x^x = a$.

Vì vậy, cuối cùng, đối với $1 < a < e^{\frac{1}{e}}$ phương trình (2) có chính xác hai nghiệm, đối với $a = e^{\frac{1}{e}}$ nó có một nghiệm $x = e$ và không có nghiệm nào cho $a > e^{\frac{1}{e}}$.

⟦folio 61⟧

---
running_head:
folio:
---

Với 0 < a < 1, phương trình $a^x = x$ có một nghiệm duy nhất $x_0$.
Hãy xem xét chức năng
$$f(x) = a^x - \log_a x$$
và nghiên cứu hành vi của cô ấy. Để làm điều này, chúng tôi tính toán đạo hàm của nó
$$f'(x) = a^x \ln a - \frac{1}{x \ln a} = \frac{xa^x \ln^2 a - 1}{x \ln a}.$$
Bây giờ chúng ta hãy xem xét tử số của phân số thu được $\varphi(x) = xa^x \ln^2 a - 1$. Mẫu số của nó âm với mọi $x > 0$ và do đó dấu $f'(x)$ ngược với dấu $\varphi(x)$.
Bài tập 6. Chứng minh hàm $\varphi(x)$ giảm tại $x < -\frac{1}{\ln a}$, trả về tại $x > -\frac{1}{\ln a}$ và lấy giá trị cao nhất $\varphi_{\max}$ tại $x = -\frac{1}{\ln a}$.
Từ Bài tập 6, ta suy ra rằng nếu $\varphi_{\max} \leq 0$ với mọi $x$ thì hàm $f(x)$ trả về cho mọi $x > 0$, vì vậy $x_0$ là nghiệm duy nhất của phương trình (2) (hình 6, a, b).

Giải bất đẳng thức $\varphi_{\max} = -\frac{\ln a}{e} - 1 \leq 0$, ta thu được $a \geq e^{-e}$. Vì vậy, đối với $e^{-e} \leq a < 1$, phương trình (2) có đúng một nghiệm $x = x_0$.

Nếu $0 < a < e^{-e}$ thì $\varphi_{\max} > 0$ và đồ thị của hàm $\varphi$ có ​​dạng như trong hình 6, c. Để biện minh cho điều này, chỉ cần lưu ý rằng $\varphi(0) = -1$ và $\varphi(1) < 0$ là đủ. Đồ thị của hàm $f(x) = a^x - \log_a x$ cho $e^{-e} < a < 1$ và $a = e^{-e}$ được thể hiện trên Hình 7, a, b.

Bài tập 7. Chứng minh $\varphi(1) = a \ln^2 a - 1 < 0$ khi $0 < a < e^{-e}$. Gợi ý. Tìm cực đại của hàm $g(a) = a \ln^2 a$.

Từ Bài tập 7, hàm số $\varphi(x)$ bằng 0 tại hai điểm $\alpha$ và $\beta$, và $0 < \alpha < -\frac{1}{\ln a}$ và $-\frac{1}{\ln a} < \beta < 1$.

Điều này có nghĩa là hàm $f$ trả về ở $x \in (0, \alpha)$, giảm ở $x \in (\alpha; \beta)$ và trả về lại ở

Puc. 7.

Puc. 8.

Puc. 9.

Puc. 10.

⟦folio 62⟧

---
running_head:
folio:
---

$x \in (\beta; 1)$. Như vậy, các điểm $\alpha$ và $\beta$ tương ứng: $\alpha$ là điểm cực đại và $\beta$ là điểm cực tiểu của hàm $f$ (đồ thị của hàm này được hiển thị trong hình 7, $\theta$).

Để hoàn thành nghiên cứu của mình, chúng tôi chứng minh rằng $\alpha < x_0 < \beta$.

Bài tập 8. Chứng minh $x_0 < \frac{1}{e}$ khi $0 < a < e^{-e}$. Gợi ý. Giả sử rằng $x_0 > \frac{1}{e}$, chúng ta nhận được $x_0 = a^{x_0} < a^{\frac{1}{e}} < \frac{1}{e}$ - mâu thuẫn!

Bây giờ chúng ta hãy tính $\varphi(x_0) = x_0^2 \ln^2 a - 1 = \ln^2 a x_0 - 1 = \ln^2 x_0 - 1$. Vì $\ln x_0 < -1$, chúng ta ngay lập tức nhận được $\varphi(x_0) > 0$, nên $f'(x_0) < 0$, tức là $\alpha < x_0 < \beta$.
