---
id: 1977-10-egorov-uravneniya-i-predelyi-23685e69
issue: kvant_1977_10
year: 1977
number: "10"
title: Phương trình và giới hạn
authors:
  - Егоров А. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 36
page_last: 40
page_labels: 34-38
tag: CVXP
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 98539ae39a2ee966d41f34bc91939a913d071783561e1d94d9f07b01aa988862
prompt_sha256: draft-1
translated_from: content/ru/1977/10/articles/08_egorov-uravneniya-i-predelyi-23685e69.md
source_content_sha256: be92e8e6d81a6308c90f1c6a1da849d4cc9feb0d2c751ebcc3f4f47f342f9d15
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 34⟧

A. Egorov

Phương trình và trước đó

1. Ví dụ đơn giản

Để tính gần đúng căn bậc hai của một số dương $a$, hãy tiến hành như sau (ví dụ: xem cuốn sách “Đại số và nguyên tắc phân tích 9”, trang 83).

Một số tùy ý $a_0 > \sqrt{a}$ được lấy làm giá trị gần đúng đầu tiên. Giá trị gần đúng tiếp theo $a_1$ được tìm thấy theo công thức

$$a_1 = \frac{1}{2} \left( a_0 + \frac{a}{a_0} \right),$$

bởi $a_1$ tìm $a_2$:

$$a_2 = \frac{1}{2} \left( a_1 + \frac{a}{a_1} \right)$$

và nói chung

$$a_n = \frac{1}{2} \left( a_{n-1} + \frac{a}{a_{n-1}} \right).$$

Trình tự $\{a_n\}$ giết chóc một cách đơn điệu và bị hạn chế. Theo định lý Weierstrass, nó có giới hạn. Hãy để $\lim_{n \to \infty} a_n = s$. Khi đó $s > 0$ và $s = \frac{1}{2} \left( s + \frac{a}{s} \right)$, tức là $s^2 = a$, và vì $s > 0$, nên $s = \sqrt{a}$.

Nếu chúng ta lấy $n$ đủ lớn thì $a_n$ sẽ khác khá ít so với $\sqrt{a}$.

Bài tập
1. Chứng minh rằng dãy $\{a_n\}$ tiêu diệt một cách đơn điệu.
2. Ước tính sự khác biệt $|a_n - \sqrt{a}|$.

Hãy để chúng tôi phân tích phương pháp tính các giá trị gần đúng liên tiếp cho $\sqrt{a}$. Trình tự $\{a_n\}$ được chỉ định lặp lại: $a_n = \varphi(a_{n-1})$, trong đó $\varphi(x) = \frac{1}{2} \left( x + \frac{a}{x} \right)$. Sau khi thiết lập sự hội tụ của chuỗi $\{a_n\}$, ta kết luận rằng giới hạn $s$ của nó thỏa mãn đẳng thức $s = \frac{1}{2} \left( s + \frac{a}{s} \right)$, tức là nó là nghiệm của phương trình

$$\varphi(x) = x.$$

(1)

Hình 1 thể hiện đồ thị của hàm $y = \frac{1}{2} \left( x + \frac{2}{x} \right)$, $x > 0$ và thể hiện ba số hạng đầu tiên của dãy

$$\begin{cases} a_0 = 2, \\ a_n = \frac{1}{2} \left( a_{n-1} + \frac{2}{a_{n-1}} \right). \end{cases}$$

Bài tập 3. Biểu thị $a_n$ theo $n$ nếu $a_0 = 1$ và a) $a_n = a \cdot a_{n-1}$; 6) $a_n = a^a_{n-1}$; 7) $a_n = \sqrt{a + a_{n-1}}$; 8) $a_n = \frac{a_{n-1}}{\sqrt{1 + a_{n-1}^2}}$; 9) $a_n = \frac{1}{1 + a_{n-1}}$.

2. Phương trình và trước đó

Chúng ta cần giải phương trình (1), trong đó $\varphi$ là một hàm nào đó. Hãy lấy một số tùy ý $a_0 \in D(\varphi)$ và xác định chuỗi $\{a_n\}: a_n = \varphi(a_{n-1})$ một cách lặp lại. Giả sử $a_n \in D(\varphi)$ cho tất cả $n \in \mathbb{N}$.

Hình 1.

⟦folio 35⟧

Định lý 1. Nếu dãy $\{a_n\}$ hội tụ về s và hàm φ liên tục với $x = s$ thì s là nghiệm của phương trình (1).

Định lý này thực tế đã được áp dụng trong đoạn 1. Việc lựa chọn phép tính gần đúng đầu tiên (hoặc “số hạng 0” của dãy) được quyết định bởi thông điệp thuận tiện - $a_0$ là điều đương nhiên để gần với nghiệm ban đầu hơn.

Như sẽ thấy ở phần sau, một nghiên cứu thông minh về khả năng giải được của phương trình (1) đôi khi cho phép chúng ta giải được câu hỏi về sự hội tụ của dãy tương ứng $\{a_n\}$.

Bài tập
4. Khảo sát sự hội tụ của dãy:

a) $a_n = \sqrt{a + a_{n-1}}, a_0 = 0$;
b) $a_n = \frac{1}{1 + a_{n-1}}, a_0 = 1$.
5. Nêu cách tìm nghiệm dương của phương trình
$$x^3 - x - 1 = 0.$$ (1)
6. (Với phương pháp tính gần đúng $\sqrt[3]{a}$.) Dãy số $\{a_n\}$ được xây dựng theo quy tắc sau:
$$\begin{cases} a_0 = a > 0, \\ a_n = \frac{1}{3}(2a_{n-1} + \frac{a}{a_{n-1}}). \end{cases}$$
Chứng minh rằng $\lim_{n \to \infty} a_n = \sqrt[3]{a}$.
7. Hãy để $a > 0, b > 0, p > 0, q > 0$. Hãy xem xét trình tự
$$\frac{a}{b}, \frac{b}{pa+qb}, \frac{pa+qb}{pb+q(pa+qb)}, \dots, \frac{a_n}{b_n}, \dots$$
ở đâu $a_{n+1} = b_n, b_{n+1} = pa_n + qb_n$. Có giới hạn cho trình tự này không?
(Điều này bài toán do độc giả V. Fischuk của chúng tôi đề xuất.)

3. Ví dụ chính

Phần còn lại của bài viết dành cho vấn đề về sự hội tụ của chuỗi
$$\begin{cases} \alpha_0 = 1, \\ \alpha_n = a^{\alpha n-1}, \end{cases}$$ (2)
tức là 1, $a, a^a, a^{a^a}, a^{a^{a^a}}, \dots$. Tất nhiên, sự hội tụ này phụ thuộc vào tham số $a$.

Hóa ra là đối với $a$ lớn, việc tìm ra sự tồn tại của giới hạn là tương đối dễ dàng, còn đối với những cái nhỏ -

khó khăn hơn nhiều. Hãy đưa ra một vài ví dụ.

Với $a = 2$ ta thu được dãy
1; 2; 4; 16; 65536; ...
(cô ấy, rất/không, không đồng ý).

Khi $a = 1,5$ là dãy
1; 1,5; 2,106; 2,349; 2,592; ...
$\alpha_{11} \approx 10,99; \alpha_{12} \approx 86,163; \alpha_{13} > 10^{16}$
(cô ấy cũng phân kỳ, nhưng ở đây ngay từ đầu nó đã không nhiều/không).

Đối với $a = \sqrt{2} = 1,4142$ ...—chuỗi
1; $\sqrt{2}$; 1,632; 1,761; ...
$\alpha_8 \approx 1,966; \alpha_{25} \approx 1,9999$ (ở đây, như chúng ta sẽ thấy, giới hạn tồn tại và bằng 2).

Tại $a = 1$
1, 1, 1, ...
(giới hạn, rất/không, tồn tại và bằng 1).

Tại $a = 0,5$
1; 0,5; 0,707; 0,613; 0,654; ...
$\alpha_{12} \approx 0,641206; \alpha_{13} \approx 0,641177$.

Tại $a = 0,01$
1; 0,01; 0,955; 0,0123; 0,945; 0,013; ...
$\alpha_{15} \approx 0,013; \alpha_{16} \approx 0,941$ (chúng tôi sẽ bình luận về hành vi của 2 chuỗi cuối ở cuối bài viết).

Từ Định lý 1, chúng ta biết rằng nếu $\lim_{n \to \infty} a_n = s$ thì s là nghiệm

⟦folio 36⟧

phương trình
$$a^x = x$$
(hàm số $x \rightarrow a^x$ liên tục tại mọi điểm trên trục số). Do đó, nếu phương trình (3) đối với một số $a$ không có nghiệm thì dãy tương ứng (2) sẽ phân kỳ.

Hình 2 thể hiện đồ thị của hàm $y = a^x$ và các số hạng đầu tiên của dãy (2) - cho $a > 1$ và giả định rằng phương trình (3) có nghiệm; trong Hình 3 - tương tự cho $0 < a < 1$.

4. $a > 1$
Đối với $a > 1$, chuỗi (2) tăng đơn điệu (kiểm tra!).

Định lý 2. Với $a > 1$, dãy (2) hội tụ moeda và molъko moeda khi phương trình (3) có ít nhất một nghiệm. Trong trường hợp này, giới hạn của nó bằng nghiệm nhỏ hơn của phương trình (3).

Bằng chứng. Chúng ta vừa lưu ý rằng nếu dãy (2) hội tụ thì giới hạn của nó là nghiệm của phương trình (3). Bây giờ phương trình (3) có nghiệm. Chúng ta hãy biểu thị bằng $s_0$ căn nhỏ nhất. Hãy để chúng tôi chứng minh rằng $\alpha_n < s_0$ cho tất cả $n \in \mathbb{N}$. Thật dễ dàng để nhận thấy điều đó $s_0 > 1 = \alpha_0$. Nếu $s_0 > \alpha_n$ thì $s_0 = a^{s_0} > a^{\alpha_n} = a_{n+1}$. Từ định lý Weierstrass, chuỗi (2) hội tụ và hiển nhiên là đến $s_0$. Định lý đã được chứng minh.

5. $0 < a < 1$
Trong trường hợp này, chuỗi (2) bị giới hạn: $0 < \alpha_n < 1$. Thật không may, nó không đơn điệu. Trên thực tế, vì $0 < a < 1$, hàm $y = a^x$ loại bỏ và $\alpha_2 = a^a < 1 = \alpha_0$, do đó, nếu phương trình (3) đối với một số $a$ không có nghiệm, tức là $\alpha_3 > \alpha_1$. Tiếp theo, $\alpha_4 = a^{\alpha_3} < a^{\alpha_1} = \alpha_2$, tức là $1 = \alpha_0 > \alpha_2 > \alpha_4$. Sử dụng phương pháp quy nạp toán học, dễ dàng chứng minh được rằng dãy con $\alpha_1, \alpha_3, \alpha_5, \dots, \alpha_{2n-1}, \dots$ của dãy chúng ta tăng đơn điệu, còn dãy con $\alpha_0, \alpha_2, \alpha_4, \dots, \alpha_{2n}, \dots$ là dãy giết đơn điệu. Trong trường hợp này, nó luôn là $\alpha_{2n} > \alpha_{2n-1}$. Theo định lý Weierstrass, mỗi dãy con này đều có giới hạn. Đặt $\lim_{n \to \infty} \alpha_{2n-1} = s_1$ và $\lim_{n \to \infty} \alpha_{2n} = s_2$. Rõ ràng là $s_2 \geq s_1$ và dãy con (2) sẽ hội tụ khi và chỉ khi $s_1 = s_2$ (chứng minh!).

Bạn có thể nói gì về các số $s_1$ và $s_2$? Vì $\alpha_{2n+2} = a^{a^{\alpha_{2n}}}$, $\alpha_{2n+1} = a^{a^{\alpha_{2n-1}}}$ và hàm $x \rightarrow a^{a^x}$ liên tục tại mọi điểm trên trục số nên các số $s_1$ và $s_2$ là nghiệm của phương trình (3).

Định lý 3. Các số $s_1$ và $s_2$ là tỉ số giữa nghiệm nhỏ và nghiệm lớn của phương trình (4).

Bằng chứng. Đặt $s$ là một nghiệm tùy ý của phương trình (4). Để chứng minh định lý, chỉ cần thiết lập $\alpha_{2n-1} < s < \alpha_{2n}$ cho mọi $n \in \mathbb{N}$ là đủ.

Trước hết, hãy lưu ý rằng $s < 1$. Thật vậy, nếu $s \geq 1$, thì theo $a^s > 0$, $a^{a^s} < 1$, tức là, $a^{a^s} \neq s$. Ngoài ra còn rất tiện lợi, $s > 0$. Từ $0 < s < 1$ theo sau $a^0 > a^s > a^1$, tức là $\alpha_0 > a^s > \alpha_1$. Vì vậy, $a^{\alpha_0} < a^{a^s} < a^{\alpha_1}$, tức là $\alpha_1 < s < \alpha_2$. Bước cảm ứng được thực hiện theo cách tương tự.

Hệ quả 1. Nếu phương trình (4) có nhiều hơn một nghiệm thì dãy (2) phân kỳ.

Hệ quả 2. Nếu phương trình (4) có nhiều hơn một nghiệm thì dãy (2) hội tụ và giới hạn

⟦folio 37⟧

Hình 4.

dãy này là nghiệm của phương trình (3).

Dễ dàng thấy rằng mọi nghiệm của phương trình (3) cũng thỏa mãn phương trình (4). Nhưng đối với $0 < a < 1$, phương trình (3) rõ ràng có nghiệm (hãy vẽ đồ thị!). Điều này có nghĩa là đối với phương trình $a$ (4) như vậy phải có ít nhất một nghiệm.

Bài tập 8: Xét dãy $\alpha_0 = x > 0, \alpha_n = a^{\alpha n-1}$. $x$ dãy này hội tụ với điều kiện nào? (Xem xét riêng trường hợp $a > 1$ và $0 < a < 1$).

Vì vậy, câu hỏi về sự hội tụ của dãy (2) trùng với câu hỏi về số nghiệm của phương trình (3) đối với $a > 1$ và phương trình (4) đối với $0 < a < 1$.

6. Nghiên cứu phương trình (3) tại $a > 1$

Phương trình (3) tương đương với phương trình

$$\frac{\ln x}{x} = \ln a.$$ (Hình 4). Hàm này được xác định tại $x > 0$, đạt tối đa $1/e$ tại $x = e$, tiêu diệt ở $x > e$ và trả về ở $0 < x < e$.

Bài tập 9. Tiến hành nghiên cứu tương tự về hàm $y = \frac{\ln x}{x}$.

Do đó, đối với $\ln a > 1/e$, tức là $a > e^{1/e}$, phương trình (5) không có nghiệm.

Hình 5.

Đối với $0 < \ln a < 1/e$, tức là $1 < a < e^{1/e}$, phương trình (5) có hai nghiệm.

Tại $a = e^{1/e}$ nó có một gốc.

Chúng ta hãy lưu ý thêm rằng đối với $\ln a \leq 0$, tức là $0 < a \leq 1$, phương trình (5) có một nghiệm duy nhất.

7. Nghiên cứu phương trình (4) tại $0 < a < 1$

Chúng ta đã biết rằng tất cả các nghiệm của phương trình (4) đều nằm trong khoảng $[0; 1]$. Phương trình (4) tương đương với phương trình $a^x = \log_a x$, $x = \log_a \log_a x$ hoặc $x = \frac{1}{\ln a} \ln \frac{\ln x}{\ln a}$. Chúng ta hãy biểu thị hàm số bằng $\varphi$

$$\varphi(x) = \frac{1}{\ln a} \ln \frac{\ln x}{\ln a} - x.$$

Chúng ta muốn tìm ra có bao nhiêu nghiệm, tùy thuộc vào tham số $a$ mà phương trình $\varphi(x) = 0$ có, tương đương với phương trình (4). Để làm điều này, bạn cần đếm xem có bao nhiêu điểm giao nhau của đồ thị hàm số $\varphi$ với trục hoành.

Trước hết, chúng tôi lưu ý rằng điểm $s_0$ rõ ràng thuộc về các giao điểm này, trong đó $s_0$ là nghiệm duy nhất của phương trình (3), (5), hãy xem phần thay thế ở cuối đoạn văn. 6 và 5.

Hãy cùng nghiên cứu hàm $\varphi$.

Vì $\ln a < 0$, hàm $\varphi$ được xác định tại $0 < x < 1$. Tại $x \rightarrow 0$ (phải) $\varphi(x) \rightarrow -\infty$; tại $x \rightarrow 1$ (trái) $\varphi(x) \rightarrow +\infty$.

⟦folio 38⟧

Hãy tìm cực trị của hàm số $f$; Để làm điều này, chúng tôi kiểm tra đạo hàm của nó:

$$\varphi'(x) = \frac{1}{x \ln x \ln a} - 1.$$

Đánh đồng nó bằng 0, ta thu được phương trình

$$x \ln x = \frac{1}{\ln a}.$$

(6)

Hình 5 thể hiện đồ thị của hàm $y = x \ln x$.

Bài tập 10. Khám phá hàm $y = x \ln x$ và vẽ đồ thị.

Chúng ta thấy rằng tại $x = 1/e$ hàm $y = x \ln x$ đạt mức tối thiểu bằng $-1/e$. Do đó, nếu $1/\ln a < -1/e$, tức là $\ln a > -e$ hoặc $a > e^{-e}$, thì phương trình (6) không có nghiệm. Vì vậy, đối với $e^{-e} < a < 1$, hàm dẫn xuất $f$ hoàn toàn lớn hơn 0, nghĩa là đối với các giá trị như vậy của $a$ thì hàm $f$ đang tăng nghiêm ngặt. Điều này có nghĩa là phương trình $f(x) = 0$ cho $e^{-e} < a < 1$ có một nghiệm duy nhất $s_0$ (đồ thị gần đúng của hàm $f$ cho $e^{-e} < a < 1$ được hiển thị trong Hình 6).

Nếu $a = e^{-e}$ thì $\varphi'(x) = 0$ cho $x = 1/e$ và $\varphi'(x) > 0$ cho tất cả những người khác $x \in [0; 1/e] \cup [1/e; 1]$.

Trong trường hợp này, $f$ cũng tăng nghiêm ngặt trong toàn bộ miền định nghĩa và phương trình $f(x) = 0$ vẫn có một nghiệm duy nhất $x = 1/e$ (đồ thị của hàm $f$ cho $a = e^{-e}$ được hiển thị trong Hình 7).

Vì vậy, nếu $e^{-e} \leq a < 1$, phương trình (4) có đúng một nghiệm.

Nếu $0 < a < e^{-e}$ thì phương trình (6) có hai nghiệm: $x_1$ và $x_2$ (Hình 5). Hơn nữa, với $x \in [0; x_1]$ $x_1$ [∪] $x_2$; 1 [đạo hàm của $\varphi'(x)$ là dương và tại $x \in [x_1; x_2]$ nó âm, do đó $x_1$ là điểm cực đại và $x_2$ là điểm cực tiểu của hàm $f$; Điều này có nghĩa là $\varphi$ tại $x \in [0; x_1]$ [tăng và tại $x \in [x_1; x_2]$ 1 [tăng và tại $x \in [x_1; x_2]$ thì giảm (hãy tìm hiểu!).

Bây giờ chúng ta hãy chứng minh điều đó $s_0 \in [x_1; x_2]$. Để làm được điều này, chỉ cần chứng minh rằng $\varphi'(s_0) < 0$. chúng tôi có

$$\varphi'(s_0) = \frac{1}{s_0 \ln s_0 \ln a} - 1 = \frac{1}{(\ln s_0)^2} - 1$$

(kể từ $\frac{\ln s_0}{s_0} = \ln a$). Hãy chứng minh rằng $\ln s_0 < -1$ (khi đó $\varphi'(s_0) < 0$). Để làm điều này, chúng ta hãy quay lại hàm $y = \frac{\ln x}{x}$ (Hình 4). Vì nó tăng ở $0 < x < 1$ và $\ln a < -e$, nên nghiệm $s_0$ của phương trình (5) nằm ở bên trái của nghiệm của phương trình $\frac{\ln x}{x} = -e$, tức là ở bên trái của điểm $e^{-1}$. Vì vậy, $s_0 < 1/e$ và $\ln s_0 < -1$.

Vì vậy, về hàm $f$ bây giờ chúng ta đã biết rằng

1) $\varphi(x) \rightarrow -\infty$ tại $x \rightarrow 0$;
2) $\varphi(x) \rightarrow +\infty$ tại $x \rightarrow 1$;
3) $\varphi$ tăng trong khoảng $|0; x_1|$, tại điểm $x_1$ có ​​giá trị cực đại, giảm trong khoảng $|x_1; x_2|$, tại điểm $x_2$ có giá trị nhỏ nhất và tăng trở lại trong khoảng $|x_2; 1|$;
