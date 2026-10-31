---
id: 1971-6-goldberg-logarifmicheskie-uravneniya-45a02fed
issue: kvant_1971_6
year: 1971
number: "6"
title: Phương trình logarit
authors:
  - Гольдберг В. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 48
page_last: 53
page_labels: 46-51
tag: 975A
lang: vi
source: kvant_digital
extraction: vision
content_sha256: d5d483becdf4bf45e4c000ff732d95cdec1c92e9a9f704c13cb9a85dff72e584
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1971/06/articles/12_goldberg-logarifmicheskie-uravneniya-45a02fed.md
source_content_sha256: b79d2832634f1a72b4b29c1d048a564071ae93936e93364c592741f825b90190
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦trang 46⟧

Phương trình lôgarit
V. V. Goldberg

Người ta gọi phương trình lôgarit là những phương trình chứa ẩn dưới dấu lôgarit.
Việc giải phương trình lôgarit đơn giản nhất

$$\log_a x = b$$

(1)
dựa trên tính chất sau của lôgarit: nếu lôgarit của hai số (dương) theo cùng một cơ số $a(a > 0, a \neq 1)$ bằng nhau thì chính các số đó cũng bằng nhau.

Viết phương trình (1) dưới dạng $\log_a x = \log_a a^b$ và sử dụng tính chất đã nêu, ta được đáp số: $x = a^b$.

Phương pháp này cũng áp dụng được để giải các phương trình lôgarit phức tạp hơn có dạng

$$\log_a f(x) = b.$$

(2)
Đối với phương trình (2) ta có $f(x) = a^b$.

Ví dụ 1. Giải phương trình

$$\log_5 [2 + \log_3(3+x)] = 0.$$

Lời giải. Trước hết ta được

$$2 + \log_3(3+x) = 5^0, \quad 2 + \log_3(3+x) = 1, \quad \log_3(3+x) = -1.$$

Tiếp theo ta tìm được: $3 + x = 3^{-1}, x = \frac{1}{3} - 3, x = -\frac{8}{3}$.

Một số phương trình lôgarit dễ dàng đưa về dạng đơn giản nhất. Chẳng hạn, các phương trình dạng

$$f(\log_a x) = 0$$

(3)
bằng phép đặt $\log_a x = y$ được đưa về phương trình $f(y) = 0$. Nếu $y_1, \dots, y_k$ là các nghiệm của phương trình sau cùng, thì ta nhận được một hệ các phương trình lôgarit đơn giản nhất:

$$\log_a x = y_1, \dots, \log_a x = y_k.$$

Ví dụ 2. Giải phương trình $\lg^3 x - \lg^2 x - 6 \lg x = 0$.

Lời giải e. Đặt $\lg x$ là $y$. Khi đó ta được phương trình bậc ba đối với $y$:

$$y^3 - y^2 - 6y = 0.$$

Giải nó: $y(y^2 - y - 6) = 0, y_1 = 0, y_2 = 3, y_3 = -2$. Xét ba trường hợp có thể:

a). $\lg x = 0, x_1 = 1$; 6) $\lg x = 3, x_2 = 1000$; b) $\lg x = -2, x_3 = 0,01$.

Các phương trình mũ-lôgarit thuộc loại phương trình dạng (3) nếu trước hết lấy lôgarit của chúng.

⟦folio 47⟧

Phương pháp 3. Giải phương trình $x^2 + \log_3 x = 3^8$.

Lời giải. Vì cả hai vế của phương trình đều dương (ĐKXĐ: $x > 0$), ta cho các lôgarit cơ số 3 của chúng bằng nhau: $\log_3 x^2 + \log_3 x = \log_3 3^8$, từ đó suy ra $(2 + \log_3 x) \log_3 x = 8$. Đặt $\log_3 x$ là $y$, ta được phương trình bậc hai $y^2 + 2y - 8 = 0$ có các nghiệm $y_1 = -4, y_2 = 2$. Xét hai trường hợp:

a) $\log_3 x = -4, x_1 = 1/81$ 6) $\log_3 x = 2, x_2 = 9$.

Thủ pháp 4. Giải phương trình $9x^{\lg x} + 91x^{-\lg x} = 60$.

Lời giải. Đặt $x^{\lg x} = y$; khi đó $x^{-\lg x} = \frac{1}{y}$, do đó phương trình quy về phương trình sau đối với $y$: $9y^2 - 60y + 91 = 0$. Các nghiệm của phương trình sau là $y_1 = \frac{13}{3}, y_2 = \frac{7}{3}$. Xét cả hai khả năng:

a) $x^{\lg x} = \frac{13}{3}$; lấy logarit, ta được $\lg x^{\lg x} = \lg \frac{13}{3}, \lg^2 x = \lg \frac{13}{3}$, từ đó $\lg x = \pm \sqrt{\lg \frac{13}{3}}, x_1 = 10^{\sqrt{\lg \frac{13}{3}}}, x_2 = 10^{-\sqrt{\lg \frac{13}{3}}}$;

b) $x^{\lg x} = \frac{7}{3}$; tương tự như trong trường hợp thứ nhất, ta tìm được $x_3 = 10^{\sqrt{\lg \frac{7}{3}}}, x_4 = 10^{-\sqrt{\lg \frac{7}{3}}}$.

Khi giải các phương trình logarit, thường quy về giải phương trình dạng

$$\log_a f(x) = \log_a g(x).$$

Ở đây, bằng cách lũy thừa hóa cần chuyển sang phương trình

$$f(x) = g(x).$$

Nhưng cần lưu ý rằng khi lũy thừa hóa, ta mở rộng miền xác định của phương trình, vì vậy có thể xuất hiện các nghiệm ngoại lai. Do đó cần kiểm tra xem mỗi nghiệm của phương trình (5) có thuộc miền xác định của phương trình (4) hay không.

Phương pháp 5. Giải phương trình $\log_2(2x^2 - 2) = \log_2(5x - 4)$.

Lời giải. Tìm miền xác định:

$$\begin{cases} 2x^2 - 2 > 0, \\ 5x - 4 > 0, \end{cases}$$

tức là $$\begin{cases} x < -1, x > 1, \\ x > \frac{4}{5}. \end{cases}$$

Do đó, miền xác định là: $x > 1$. Lũy thừa hóa phương trình đã cho, ta được $2x^2 - 2 = 5x - 4$, hay $2x^2 - 5x + 2 = 0$, từ đó tìm được $x_1 = 2, x_2 = 1/2$.

Vì $x_2 = 1/2$ không thuộc ĐKXĐ, phương trình chỉ có một nghiệm: $x = 2$.

Các tính chất sau của lôgarit các số đã được biết rõ:

$$\log_a(AB) = \log_a A + \log_a B \quad (A > 0, B > 0, a > 0, a \neq 1),$$

$$\log_a \frac{A}{B} = \log_a A - \log_a B \quad (A > 0, B > 0, a > 0, a \neq 1),$$

$$\log_a A^p = p \log_a A \quad (A > 0, p - \text{một số thực bất kỳ}),$$

$$\log_a q^p = \frac{p}{q} \log_a A \quad (A > 0, q \neq 0).$$

⟦folio 48⟧

Cần áp dụng các tính chất này của lôgarit như thế nào khi giải các phương trình lôgarit, trong đó các biểu thức $A$ và $B$ chứa ẩn?

Để trả lời câu hỏi này, hãy lưu ý rằng ĐKXĐ của vế trái và vế phải của các công thức này khác nhau: chẳng hạn, vế phải của công thức (6) chỉ có nghĩa khi $A > 0$ và $B > 0$, còn vế trái của công thức này được xác định cả khi $A > 0$ và $B > 0$, lẫn khi $A < 0$, $B < 0$.

Tương tự, đối với các công thức còn lại, ĐKXĐ của vế trái có thể rộng hơn ĐKXĐ của vế phải (đồng thời trong công thức (9) cần xét các giá trị cho phép của đại lượng $a$ nằm trong cơ số). Điều đã nói có nghĩa là nếu ta sử dụng các công thức (6)—(9) “từ phải sang trái”, thì kết quả sẽ là một phương trình là hệ quả của phương trình ban đầu (ĐKXĐ của nó có thể rộng hơn). Khi đó, ta được bảo đảm rằng sẽ không làm mất nghiệm. Nhưng trong trường hợp này có thể xuất hiện nghiệm ngoại lai. Vì vậy, tất cả các nghiệm tìm được cần được kiểm tra (nếu nghiệm ngoại lai chỉ có thể xuất hiện do sử dụng các công thức (6)—(9), thì chỉ cần kiểm tra xem các nghiệm tìm được có thuộc ĐKXĐ của phương trình ban đầu hay không).

Ví dụ 6. Giải phương trình

$$\log_{\frac{1}{6}}(x-1) + \log_{\frac{1}{6}}(5x+3) = -2.$$

Lời giải. Tìm ĐKXĐ:

$$\begin{cases} x-1 > 0, \\ 5x+3 > 0. \end{cases} \quad \begin{cases} x > 1, \\ x > -\frac{3}{5}. \end{cases}$$

Do đó, ĐKXĐ là: $x > 1$.

Áp dụng công thức (6) cho vế trái của phương trình, ta được

$$\log_{\frac{1}{6}}[(x-1)(5x+3)] = -2,$$

từ đó tìm được $(x-1)(5x+3) = 36$, hay $5x^2-2x-39=0$. Các nghiệm của phương trình bậc hai là: $x_1=3$, $x_2=-13/5$.

Vì các nghiệm ngoại lai chỉ có thể xuất hiện do sử dụng công thức (6), chỉ cần kiểm tra xem các nghiệm thu được có thuộc ĐKXĐ của phương trình (10) hay không. Do đó, ta thấy rằng phương trình có nghiệm duy nhất $x=3$. Lưu ý rằng giá trị $x=-13/5$, không phải là nghiệm của phương trình (10), sẽ là nghiệm của phương trình (11), có ĐKXĐ rộng hơn: $x > 1$, $x < -3/5$.

Phải làm thế nào nếu khi giải phương trình lôgarit, ta gặp необходимость phải sử dụng các công thức (6)—(9) «từ trái sang phải»? Bởi vì nếu các công thức được sử dụng dưới dạng mà ta đã viết ra, ta sẽ đi đến một phương trình có ĐKXĐ có thể hẹp hơn ĐKXĐ của phương trình ban đầu! Nhưng khi đó ta có thể mất một phần nghiệm!

Để điều này không xảy ra ngẫu nhiên, cần sử dụng các công thức tổng quát hơn:

$$\log_a(AB) = \log_a|A| + \log_a|B| \quad (AB > 0,a > 0,a \neq 1),$$

$$\log_a\frac{A}{B} = \log_a|A| - \log_a|B| \quad (AB > 0,a > 0,a \neq 1),$$

$$\log_aA^{2p} = 2p\log_a|A| \quad (A \neq 0,p - целое число),$$

$$\log_a^{2q}A = \frac{1}{2q}\log_a|A| \quad (A > 0,q \neq 0 - целое число).$$

⟦folio 49⟧

Vế trái và vế phải của các công thức (6′) và (7′), cũng như của các công thức (6) và (7), có những điều kiện khác nhau đối với A và B: các vế trái có nghĩa khi A và B cùng dấu, còn các vế phải — với mọi A và B khác không.

Vì vậy, việc sử dụng các công thức (6′) và (7′) “từ trái sang phải” sẽ dẫn đến một phương trình mà ĐKXĐ của nó có thể rộng hơn. Nhưng điều này đã ít lạ hơn sự tồn tại của ĐKXĐ, bởi giờ đây ta không thể mất nghiệm mà chỉ có thể thu được một cấu tạo. Như chúng ta đã lưu ý, trong trường hợp này cần kiểm tra các nghiệm thu được (đôi khi chỉ cần kiểm tra xem chúng có thuộc ĐKXĐ của phương trình ban đầu hay không).

Ví dụ 7. Giải phương trình
$$\lg(x+1)^2 + \lg(x+9)^2 = 2\lg 9.$$ (12)

Để ngăn ngừa một phần các sai lầm thường gặp, trước hết ta đưa ra một lời giải không đúng.

Dùng các công thức (8), ta thấy rằng $2\lg(x+1) + 2\lg(x+9) = 2\lg 9$, hay
$$\lg(x+1) + \lg(x+9) = \lg 9.$$ (13)

Áp dụng công thức (6), ta được
$$\lg[(x+1)(x+9)] = \lg 9,$$ (14)

từ đó tìm được $(x+1)(x+9) = 9$, hay $x^2 + 10x = 0$ và tiếp theo $x_1 = 0, x_2 = -10$. Kiểm tra cho thấy cả hai nghiệm đều thỏa mãn phương trình (12).

Bây giờ ta đưa ra lời giải đúng của phương trình (12).

Lời giải. Tìm ĐKXĐ của phương trình (12): $x \neq -9, x \neq -1$. Dùng công thức (7′), ta được $2\lg|x+1| + 2\lg|x+9| = 2\lg 9$, từ đó suy ra $\lg|(x+1)(x+9)| = \lg 9$ và tiếp theo $|x^2 + 10x+9| = 9$.

Đẳng thức cuối cùng đúng trong mỗi trường hợp sau:

a) $x^2 + 10x+9 = 9, x^2 + 10x = 0, x_1 = 0, x_2 = -10$;
b) $x^2 + 10x+9 = -9, x^2 + 10x+18 = 0, x_3 = -5 + \sqrt{7}, x_4 = -5 - \sqrt{7}$.

Vậy phương trình (12) có bốn nghiệm.

Sai lầm trong lời giải sai được trình bày ở trên, như bạn, hiển nhiên, đã chứng minh, là ở chỗ đã áp dụng công thức (8), chứ không phải (8′). Điều này dẫn đến phương trình (13) có ĐKXĐ hẹp hơn: $x > -1$. Thương được thực hiện ở bước tiếp theo đã bù lại điều này: ĐKXĐ của phương trình (14) rộng hơn ĐKXĐ của phương trình (13) — ở đây có cả $x > -1$ lẫn $x < -9$. Điều sau phải làm mất nghiệm $x_2 = -10$, nhưng các nghiệm $x_3, 4 = -5 \pm \sqrt{7}$ lại bị mất.

Ví dụ 8. Giải phương trình
$$\lg[(x-2)(x+3)] + \lg[(x+3)/(x-2)] = 1.$$ (15)

Lời giải. Tìm ĐKXĐ: $(x-2)(x+3) > 0$, hay $x < -3$ và $x > 2$.

Để giải, sử dụng các công thức (6′) và (7′):
$$\lg|x-2| + \lg|x+3| + \lg|x+3| - \lg|x-2| = 1.$$

Thu gọn các hạng tử đồng dạng, ta được $\lg|x+3| = 1/2$, từ đó tìm được:
$$|x+3| = \sqrt{10}, x+3 = \pm \sqrt{10}, x_1 = -3 + \sqrt{10}, x_2 = -3 - \sqrt{10}$$.

Kiểm tra cho thấy $x = -3 - \sqrt{10}$ sẽ là nghiệm duy nhất của phương trình (15).

Khi sử dụng các công thức (6) và (7), ta sẽ có
$$\lg(x-2) + \lg(x+3) + \lg(x+3) - \lg(x-2) = 1,$$
$$\lg(x+3) = \frac{1}{2}, x+3 = \sqrt{10}, x = -3 + \sqrt{10}.$$

Với cách giải này, trước hết ta đã thu hẹp miền xác định, dẫn đến mất nghiệm $x = -3 - \sqrt{10}$, rồi sau khi khử các hạng tử đồng dạng đã mở rộng miền xác định, dẫn đến xuất hiện nghiệm $x = -3 + \sqrt{10}$.

⟦trang 50⟧

Một nguồn khác dẫn đến sự xuất hiện nghiệm ngoại lai là việc áp dụng đồng nhất thức lôgarit cơ bản

$$a^{\log_a b} = b \quad (b > 0, a > 0, a \neq 1)$$

trong trường hợp $a$ và $b$ chứa ẩn.

Ví dụ 9. Giải phương trình $x^{\log_x(x^2+1)} = 2$.

Giải. Sử dụng đồng nhất thức (16), ta được $x^2+1=2$, suy ra $x_1=-1, x_2=1$. Nhưng các giá trị $x=\pm 1$ không thể là cơ số của lôgarit, tức là không thuộc miền xác định. Vì vậy phương trình không có nghiệm.

Nếu trong phương trình có các lôgarit với những cơ số khác nhau, cần áp dụng công thức chuyển từ cơ số lôgarit này sang cơ số khác:

$$\log_b A = \frac{\log_a A}{\log_a b} \quad (A > 0, a > 0, b > 0, a \neq 1, b \neq 1)$$

và trường hợp riêng của nó

$$\log_b a = \frac{1}{\log_a b} \quad (a > 0, b > 0, a \neq 1, b \neq 1).$$

Ví dụ 10. Giải phương trình

$$\log_3 x \frac{3}{x} + \log_3^2 x = 1.$$

Giải. Tìm miền xác định: $x > 0, x \neq \frac{1}{3}$. Sử dụng công thức (17), ở số hạng thứ nhất ta chuyển sang cơ số 3; khi đó được

$$\frac{\log_3 \frac{3}{x}}{\log_3(3x)} + \log_3^2 x = 1,$$ hoặc $$\frac{1-\log_3 x}{1+\log_3 x} + \log_3^2 x = 1.$$

Đặt $\log_3 x$ bằng $y$, khi đó phương trình có dạng

$$\frac{1-y}{1+y} + y^2 = 1$$ hoặc $$y^3 + y^2 - 2y = 0,$$

từ đó tìm được $y_1=0, y_2=-2, y_3=1$. Xét ba khả năng:

a) $\log_3 x=0, x_1=1$; b) $\log_3 x=1, x_3=3$.

Ví dụ 11. Giải phương trình

$$20 \log_ax \sqrt{x} + 7 \log_a^2 x^3 = 3 \log_x x^2 \quad (a > 0, a \neq 1).$$

Lời giải. Tìm ĐKXĐ: $x > 0, x \neq \frac{1}{a}, x \neq \frac{1}{a^2}, x \neq \sqrt{a}$. Vì $x > 0$, ta có thể áp dụng công thức (8), được

$$10 \log_ax x + 21 \log_a^2 x = 6 \log_x x.$$

Bây giờ thuận tiện nhất là theo công thức (18) chuyển về cùng một cơ số $x$. Nhưng khi $x$ đứng ở cơ số của các logarit, ĐKXĐ của phương trình trở nên hẹp hơn,

⟦folio 51⟧

vì sau đó $x$ không thể bằng một. Vì vậy, trước khi chuyển sang cơ số $x$, ta kiểm tra xem $x=1$ có phải là nghiệm của phương trình hay không. Dễ thấy rằng $x_1=1$ là một nghiệm. Bây giờ chuyển sang cơ số $x$:

$$\frac{10}{\log_x(ax)} + \frac{21}{\log_x(a^2x)} = \frac{6}{\log_x\frac{x}{\sqrt{a}}}.$$

Đặt $\log_x a$ là $y$. Khi đó ta được

$$\frac{10}{1+y} + \frac{21}{1+2y} = \frac{6}{1-\frac{1}{2}y}.$$

Sau các biến đổi đơn giản, ta đi đến phương trình bậc hai $13y^2-3y-10=0$, có các nghiệm $y_1=1, y_2=-\frac{10}{13}$. Trong trường hợp thứ nhất ta có $\log_x a=1, x_2=a$, còn trong trường hợp thứ hai $\log_x a=-\frac{10}{13}, x^{-\frac{10}{13}}=a, x_3=a^{-\frac{13}{10}}$.

Đáp số: $x_1=1, x_2=a, x_3=a^{-\frac{13}{10}}$.

Khi giải các phương trình lôgarit, đôi khi tiện dùng công thức sau:

$$A^{\log_a B}=B^{\log_a A} (A>0, B>0, a>0, a\neq1).$$

Chứng minh công thức (19) rất đơn giản: vì cả hai vế của công thức này đều dương, hãy tìm logarit cơ số $a$ của $A^{\log_a B}$ và $B^{\log_a A}$. Không khó để thấy rằng các logarit này bằng cùng một biểu thức $\log_a A \log_a B$; từ sự bằng nhau của các logarit suy ra tính đúng đắn của công thức (19).

Ví dụ 12. Giải phương trình $3^{\log_a x}+3x^{\log_a 3}=2 (a>0, a\neq1)$.

Lời giải. ĐKXĐ: $x>0$. Theo (19) $x^{\log_a 3}=3^{\log_a x}$.

Vì vậy phương trình đã cho có thể viết dưới dạng $3^{\log_a x}+3\cdot3^{\log_a x}=2$, từ đó suy ra $4\cdot3^{\log_a x}=2$, tức là $3^{\log_a x}=\frac{1}{2}$. Tiếp theo có $\log_a x=-\log_3 2, x=a^{-\log_3 2}$.

Bài tập

Giải các phương trình:

1. $\log_3(3^x-1) \log_3(3^{x+1}-3)=6$.
2. $x^{\log_x(x+3)^2}=16$.
3. $x^{\log_3 x-\log_3 x}=3^{3\log_2 V^2+4}$.
4. $15^{\log_6 3} x^{\log_5(9x)}+1=1$.
5. $\lg(3x-11)+\lg(x-27)=3$.
6. $\frac{1}{\log_6(3+x)}+\frac{2\log_0.25(4-x)}{\log_2(3+x)}=1$.
7. $\lg\sqrt{1+x}+3\lg\sqrt{1-x}=\lg\sqrt{1-x^2}+2$.
8. $\log_x x^2-14\log_{16x}x^3+40\log_{4x}\sqrt{x}=0$.
9. $\log_x 10+2\log_{10x}10+3\log_{100x}10=0$.
10. $3x^{\log_6 2}+2^{\log_5 x}=64$.
11. $\lg x^2+\lg(x+10)^2=2\lg 11$.
12. $\lg[x(x+9)]+\lg\frac{x+9}{x}=0$.
