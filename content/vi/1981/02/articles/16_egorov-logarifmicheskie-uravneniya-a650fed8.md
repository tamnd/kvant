---
id: 1981-2-egorov-logarifmicheskie-uravneniya-a650fed8
issue: kvant_1981_2
year: 1981
number: "2"
title: phương trình logarit
authors:
  - Егоров А. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 42
page_last: 45
page_labels: 40-43
tag: WSYQ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 66c2c8cd9bb878c8771c3c10949f559b7a7aee8915807f5ec0983787d964b870
prompt_sha256: draft-1
translated_from: content/ru/1981/02/articles/16_egorov-logarifmicheskie-uravneniya-a650fed8.md
source_content_sha256: 818e1bc23e40bf34389fd2560605fe22227d0fe72401333ecede502f45590e6d
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 40⟧

phương trình logarit

Trong các kỳ thi đầu vào, bạn thường gặp các phương trình chứa một biến dưới dấu logarit. Những phương trình như vậy thường được gọi là logarit.

Phương trình logarit đơn giản nhất là phương trình có dạng $\log_a x = b$. Nếu $a > 0$, $a \neq 1$ và $b > 0$, nó có một gốc duy nhất $x = a^b$.

Trong phần tiếp theo, chúng ta sẽ thường sử dụng các tính chất sau của logarit:

$$\log_a xy = \log_a x + \log_a y,$$

$$\log_a \frac{x}{y} = \log_a x - \log_a y,$$

$$\log_a x^\alpha = \alpha \log_a x,$$

$$\log_a x^\beta = \frac{1}{\beta} \log_a x,$$

$$\log_a x = \frac{\log_b x}{\log_b a}$$

(ở đây mọi nơi $a > 0$, $a \neq 1$, $b > 0$, $b \neq 1$, $x > 0$, $y > 0$). Việc ghi nhớ trường hợp đặc biệt này của công thức (5) cũng rất hữu ích:

$$\log_a x = \frac{1}{\log_x a}.$$

Bây giờ chúng ta hãy xem xét một số loại phương trình logarit phổ biến.

Ví dụ 1: Giải phương trình

$$\log_4 x + \log_1 x + \log_8 x^3 = 5.$$

Lời giải. Sử dụng tính chất (4), chúng ta quy đổi tất cả logarit về cơ số 2; có tính đến tính chất (3), chúng tôi có được

$$\frac{1}{2} \log_2 x - \frac{1}{4} \log_2 x + \log_2 x = 5,$$

từ đâu $\frac{5}{4} \log_2 x = 5$, $\log_2 x = 4$, $x = 16$.

Đáp số. {16}.

Đôi khi, sau một số phép biến đổi, phương trình có thể được rút gọn về dạng

$$f(\log_a x) = 0.$$

Lời giải của phương trình (6) sau khi thay thế $y = \log_a x$ và tìm nghiệm của phương trình $f(y) = 0$ trùng với lời giải của các phương trình đơn giản nhất $\log_a x = y$. Do đó, bài toán chính là tìm các phép biến đổi đưa phương trình ban đầu về phương trình có dạng (6).

Ví dụ 2 (MIIGAiK, 1977). Giải phương trình

$$(\log_x 9x^2) \cdot \log_3^2 x = 4.$$

Lời giải. Chuyển sang logarit cơ số 3, ta thu được phương trình tương đương

$$\frac{\log_3 9x^2}{\log_3 x} \cdot \log_3^2 x = 4,$$

từ đâu $(2 + 2 \log_3 x) \cdot \log_3 x = 4$. Thăm dò $y = \log_3 x$, chúng ta đi đến phương trình bậc hai $y^2 + y - 2 = 0$, từ đó $y = -2$ hoặc $y = 1$. Việc còn lại là giải các phương trình đơn giản nhất $\log_3 x = -2$ và $\log_3 x = 1$.

Đáp số. $\left\{ \frac{1}{9}, 3 \right\}$.

Ví dụ 3: Giải phương trình

$$x^{\lg x} = 10^2 \lg^2 x - 3 \lg x + 2.$$

Lời giải. Ở đây $x$ nằm dưới dấu logarit, và do đó $x > 0$. Lấy logarit của vế trái và vế phải cơ số 10, ta thu được phương trình tương đương

$$\lg^2 x = 2 \lg^2 x - 3 \lg x + 2.$$

Thăm dò $y = \lg x$, chúng ta đi đến phương trình bậc hai $y^2 - 3y + 2 = 0$, có nghiệm $y_1 = 1$ và $y_2 = 2$.

Đáp số. {10, 100}.

Khá thường xuyên cũng có những phương trình có dạng

$$\log_a f(x) = g(x)$$

hoặc các phương trình dẫn đến dạng (7).

Phương trình (7) tương đương (với $a > 1$, $a \neq 1$) với phương trình $f(x) = a^{g(x)}$.

⟦folio 41⟧

Ví dụ 4: Giải phương trình
$$\log_3(4 \cdot 3^{x-1}-1) = 2x-1.$$
Lời giải. Phương trình này tương đương với phương trình sau:
$$4 \cdot 3^{x-1}-1 = 3^{2x-1}.$$
Thay thế $y=3^x$, ta thu được phương trình bậc hai
$$y^2-4y+3=0;$$
giải quyết nó, chúng tôi tìm thấy $y_1=1, y_2=3.$
Đáp số. {0,1}.
Phương trình của dạng
$$\log_{g(x)}f(x)=a$$
(8)
tương đương với hệ thống
$$\begin{cases}
f(x)=[g(x)]^a, \\
g(x)>0, \\
g(x)\neq 1.
\end{cases}$$

Ví dụ 5 (MSU, khoa địa chất, 1966). Giải phương trình
$$\log_{(x+1)}(x^2+x-6)^2=4.$$
Lời giải. Phương trình tương đương với hệ
$$\begin{cases}
(x^2+x-6)^2=(x+1)^4, \\
x+1>0, \\
x+1\neq 1.
\end{cases}$$
Chúng tôi có $(x^2+x-6)^2-[(x+1)^2]^2=0$, từ đâu
$$[x^2+x-6+(x+1)^2][x^2+x-6-(x+1)^2]=0,$$
nên phương trình của hệ này tương đương với:
$$(2x^2+3x-5)(x+7)=0,$$
từ đâu $x_1=1, x_2=-\frac{5}{2}, x_3=-7.$
Hệ thống chỉ thỏa mãn giá trị $x=1$.
Đáp số. {1}.
Trong một số trường hợp, sau khi biến đổi, phương trình ban đầu được rút gọn về dạng
$$\log_a f(x)=\log_a g(x).$$
(9)
Dễ dàng thấy mọi nghiệm của phương trình (9) đều thỏa mãn hệ
$$\begin{cases}
f(x)=g(x), \\
f(x)>0.
\end{cases}$$

Ngược lại, nếu $x_0$ là lời giải của hệ (9'), thì $\log_a f(x_0)=\log_a g(x_0)$, do đó bất kỳ lời giải nào của hệ (9') cũng thỏa mãn phương trình (9). Như vậy, phương trình (9) tương đương với hệ (9').

Ví dụ 6: Giải phương trình
$$\log_8(7x^2-5x-6)=2\log_4\sqrt{3x-1}.$$
Lời giải. Giảm logarit về cơ số 2, sau khi đơn giản hóa, chúng ta thu được phương trình tương đương
$$\log_2(7x^2-5x-6)=\log_2(3x-1),$$
tương đương với hệ thống
$$\begin{cases}
7x^2-5x-6=3x-1, \\
3x-1>0.
\end{cases}$$
Giải hệ phương trình, ta được
$$x=\frac{4+\sqrt{51}}{7}$$
($3x_2-1<0$).
Đáp số. $\{\frac{4+\sqrt{51}}{7}\}$.

Bây giờ chúng ta hãy lưu ý một số lỗi do những người sử dụng phương trình logarit lời giải mắc phải.
Thông thường, những lỗi này có liên quan đến việc áp dụng không chính xác các công thức tính logarit của tích, phân số và lũy thừa.
Ví dụ, khi giải phương trình ở Ví dụ 5, một số học sinh viết như sau:
"Nó tuân theo điều kiện $2\log_{(x+1)}(x^2+x-6)=4$, từ đó $x^2+x-6=(x+1)^2$ hoặc $x=-7$. Nhưng $x=-7$ không thỏa mãn phương trình ban đầu, và do đó nó không có nghiệm."
Nguyên nhân mất căn $x=1$ là do áp dụng công thức
$$\log_a x^2=2\log_a x,$$ điều này chỉ đúng với $x>0$. Trong trường hợp của chúng tôi, biểu thức $x^2+x-6$ với $x=1$ là khác nhau.
Ở đây chúng ta nên sử dụng công thức $\log_a x^2=2\log_a|x|$, công thức này đúng với mọi $x \neq 0$.
Một ví dụ khác. Giải phương trình
$$\log_2[(x+1)(x-3)]=2\log_4(x+8)-\log_1[(x+1)(x-5)],$$
sinh viên đã đưa anh ta đến gặp
$$\log_2(x+1)+\log_2(x-3)=\log_2(x+8)+\log_2(x+1)+\log_2(x-5),$$
hoặc
$$\log_2(x-3)=\log_2[(x+8)(x-5)].$$
(10)
Sau đó, anh ấy thu được phương trình bậc hai $x^2+2x-37=0$, do đó chúng ta có $x_1=-1+\sqrt{38}, x_2=-1-\sqrt{38}$.

⟦folio 42⟧

Học sinh loại bỏ căn bậc hai vì không thỏa mãn phương trình (10) và nhận được đáp số $x = -1 + \sqrt{38}$.

Có chuyện gì thế này? Công thức $\log_a xy = \log_a x + \log_a y$ chỉ hợp lệ cho $x > 0$ và $y > 0$. Do đó, khi lấy logarit của tích và tích thì nghiệm $x = -1 - \sqrt{38}$ bị mất, điều này trên thực tế thỏa mãn phương trình ban đầu.

Để thấy điều này, hãy lưu ý rằng phương trình ban đầu tương đương với hệ
$$\begin{cases} \log_2(x+1)(x-3) = \\ = \log_2(x+8)(x+1)(x-5), \\ x+8 > 0, \end{cases}$$

$$\begin{cases} (x+1)(x-3) = \\ = (x+8)(x+1)(x-5), \\ x+8 > 0, \\ (x+1)(x-3) > 0. \end{cases}$$

Lời giải của hệ thống cuối cùng là $\{-1 - \sqrt{38}, -1 + \sqrt{38}\}$.

Nói chung, việc sử dụng các công thức $\log_a u^2 = 2\log_a u$ và $\log_a uv = \log_a u + \log_a v$ “từ phải sang trái” sẽ dẫn đến việc mở rộng phạm vi định nghĩa của phương trình, có thể đòi hỏi phải sử dụng các nghiệm được xây dựng. Trong trường hợp nghiệm của phương trình thu được khá đơn giản và việc xác minh không nặng nề thì không cần thiết phải viết ra các hệ phương trình và bất đẳng thức. Bạn có thể chuyển sang phương trình và kiểm tra ở cuối lời giải.

Ví dụ 7. Giải phương trình $\log_{\frac{1}{2}}(x-1) + \log_{\frac{1}{2}}(x+1) - \log_{\frac{1}{\sqrt{2}}}(7-x) = 1$.

Lời giải. Chuyển sang logarit cơ số 2 và sắp xếp lại các số hạng ở vế phải, ta thu được phương trình
$$2\log_2(7-x) = \\ = 1 + \log_2(x-1) + \log_2(x+1),$$
từ đó chúng ta có được hệ quả phương trình
$$(7-x)^2 = 2(x^2-1),$$
hoặc
$$x^2 + 14x - 51 = 0.$$
Các nghiệm của phương trình bậc hai này là $x_1 = 3, x_2 = -17$.

Căn bậc hai rõ ràng không thỏa mãn phương trình này. Thay thế giá trị $x = 3$ vào đó, chúng tôi đảm bảo rằng $x = 3$ là gốc thực sự của nó.

Đáp số. {3}.

Cuối cùng, đây là một ví dụ khác về việc học sinh bị mất gốc khi sử dụng công thức chuyển sang căn cứ khác.

Ví dụ 8. Giải phương trình $\log_{2x}x + \log_{8x^2}x = 0$.

"Lời giải". Đi đến căn cứ $x$, chúng ta nhận được
$$\frac{1}{\log_x 2 + 1} + \frac{1}{2 + 3\log_x 2} = 0.$$
Đặt $y = \log_x 2$, ta thu được phương trình
$$\frac{1}{y+1} + \frac{1}{3y+2} = 0.$$
Phương trình này có nghiệm $y = -\frac{3}{4}$. Vì vậy $\log_x 2 = -\frac{3}{4}$, từ đâu
$$x_1 = 2^{-\frac{4}{3}} = \frac{1}{2^3\sqrt{2}}.$$
Giá trị $x = \frac{1}{2^3\sqrt{2}}$ thỏa mãn phương trình. Tuy nhiên, dễ dàng nhận thấy giá trị $x = 1$ cũng là gốc của nó. Có chuyện gì vậy?

Gốc $x = 1$ bị mất khi di chuyển đến căn cứ $x$, vì đến căn cứ $x$, vì đến căn cứ $x$, vì đối với phần còn lại $x$ giải quyết như đã làm.

Đáp số. $\{1, \frac{1}{2^3\sqrt{2}}\}$.

Nói chung, tốt nhất là tránh nhảy đến các căn cứ phụ thuộc vào $x$. Nếu quá trình chuyển đổi sang các cơ sở như vậy xảy ra, thì bạn cần phải theo dõi rất cẩn thận xem $x$ phép chuyển đổi nào có thể xảy ra và kiểm tra bằng cách thay thế vào phương trình ban đầu các giá trị $x$ mà tại đó cơ sở bằng 1 hoặc âm.

Vì vậy, khi giải phương trình cuối, tốt hơn nên chuyển sang cơ số 2. Kết quả là ta có

⟦folio 43⟧

$$\frac{\log_2 x}{1 + \log_2 x} + \frac{\log_2 x}{2 + 3 \log_2 x} = 0,$$
hoặc, sau khi thay thế $y = \log_2 x$,
$$\frac{y}{1 + y} + \frac{y}{2 + 3y} = 0.$$

Giải phương trình này, chúng ta tìm được nghiệm $y_1 = 0, y_2 = -\frac{4}{3}$, sau đó chúng ta dễ dàng thu được lời giải của phương trình này.

Bây giờ hãy xem xét hai bài toán, cho lời giải sử dụng các thuộc tính đơn điệu của một số hàm.

Ví dụ 9. Giải phương trình $\log_5(x + 3) = 3 - x$.

Lời giải. Dễ dàng kiểm tra được $x = 2$ là nghiệm của phương trình này. Rõ ràng là nó không có gốc nào khác, vì hàm $\log_5(x + 3)$ trả về trong toàn bộ miền định nghĩa của nó và hàm $y = 3 - x$ sẽ hủy bỏ.

Đáp số. {2}.

Ví dụ 10. Giải phương trình $(x + 1)\log_3^2 x + 4x\log_3 x - 16 = 0$.

Lời giải. Chúng ta hãy đặt $y = \log_3 x$ và giải $y$ phương trình bậc hai $(x + 1)y^2 + 4xy - 16 = 0$.

Chúng tôi nhận được $y = \frac{4}{x + 1}$ hoặc $y = -4$. Còn lại hai phương trình cần giải:

$$\log_3 x = \frac{4}{x + 1} \text{ и } \log_3 x = -4.$$

Phương trình thứ hai trong số này có thể được giải dễ dàng và đối với lời giải phương trình đầu tiên chỉ cần thay thế $x = 3$ thỏa mãn phương trình và hàm ở bên trái trả về $x > 0$, và hàm ở bên phải sẽ tắt.

Đáp số. $\left\{\frac{1}{81}; 3\right\}$.

Để kết luận, hãy xem xét một phương trình được giải từ những cân nhắc khác.

Ví dụ 11. Giải phương trình $3x^2 - 2x^3 = \log_2(x^2 + 1) - \log_2 x$.

Lời giải. Vế phải của phương trình được xác định tại $x > 0$ và bằng $\log_2\left(x + \frac{1}{x}\right)$. Kể từ $x + \frac{1}{x} \geq 2$ tại $x > 0; \log_2\left(x + \frac{1}{x}\right) \geq 1$. Mặt khác, $3x^2 - 2x^3 \leq 1$ cho $x > 0$ (ví dụ: bạn có thể xác minh điều này bằng cách kiểm tra hàm bằng cách sử dụng một hàm tùy ý). $\log_2\left(x + \frac{1}{x}\right) = 1$ tại $x = 1$. Vì $3x^2 - 2x^3$ cũng bằng 1 tại $x = 1$ nên vế trái chỉ bằng vế phải ở $x = 1$.

Đáp số. {1}.

Bài tập
Giải các phương trình:
1. $\log_4 x + \log_2 x + 2\log_16 x = 5$.
2. (MSU, địa chất. Khoa, 1974)
$$\log_{16}(x^2 - 2x - 3)^2 - 2\log_{16}(x^2 + x - 2) = \frac{1}{2}.$$
3. (MSU, Khoa Khoa học Đất, 1974)
$$\left[(\log_2 x)^2 + 2\log_1/2 \frac{1}{2\sqrt{2}}\right]\left(3\log_8 x - 1\right) = \left(\log_2 x\right)^2.$$
4. (MSU, Khoa Kinh tế, Khoa Kinh tế Chính trị, 1979)
$$\log_{(3 - 4x^2)}(9 - 16x^4) = 2 + \frac{1}{\log_2(3 - 4x^2)}$$
5. (MSU, Khoa Tâm lý học, 1978)
$$\left(\log_3 \frac{3}{x}\right)\log_2 x - \log_3 \frac{x^3}{\sqrt{3}} = \frac{1}{2} + \log_2 \sqrt{x}.$$
6. (MSU, Khoa Kinh tế, Khoa Kinh tế, Nghiên cứu Sách, 1978)
$$3 + \frac{1}{\log_3 \frac{x}{2}} = \log_2\left(\frac{75x}{4} - \frac{11}{x}\right).$$
7. (MSU, Khoa Kinh tế, Khoa Kinh tế Chính trị, 1979)
$$\log_{(2x + 1)}(5 + 8x - 4x^2) + \log_{(5 - 2x)}(1 + 4x + 4x^2) = 4.$$
8. (MVTU, 1979)
$$0,5\lg(2x - 1) + \lg\sqrt{x - 9} = 1.$$
9. (MSU, Khoa Khoa học Đất, 1979)
$$x^2\log_6\sqrt{5x^2 - 2x - 3} - x\log_1/6\left(5x^2 - 2x - 3\right) = x^2 + 2x.$$
10. (MSU, Khoa Hóa học, 1972)
$$\log_{(x^2 + 6x + 8)}(\log_{(2x^2 + 2x + 3)}(x^2 - 2x)) = 0.$$
11. (MSU, Khoa Vật lý, 1975)
$$6\log_1/6\left(x + 3\right) = \left(\frac{1}{2}\right)\log_4(x^2 + 5x + 12).$$
12. $\log_2^2 x + (x - 1)\log_2 x = 6 - 2x.$
13. $3^x = 10 - \log_2 x.$
14. $\log_{0,5}x^2 - 14\log_{16}x^3 + 40_4x\sqrt{x} = 0.$
