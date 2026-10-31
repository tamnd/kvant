---
id: 1985-7-brodskiy-slipenko-funktsionalnyie-uravneniya-i-gruppyi-938d53e5
issue: kvant_1985_7
year: 1985
number: "7"
title: Phương trình và nhóm hàm
authors:
  - Бродский Я. С.
  - Слипенко А. К.
rubric: osnovnye-stati
page_first: 25
page_last: 27
page_labels: 23-25
tag: 7Y9R
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 691e132311d86661506afb7e1f2dd6fc6d598d0a072ea92747ae622a63ba1f03
prompt_sha256: draft-1
translated_from: content/ru/1985/07/articles/07_brodskiy-slipenko-funktsionalnyie-uravneniya-i-gruppyi-938d53e5.md
source_content_sha256: d97218f3c456cbd397ee38b966ee5b298380d9b201cee247934f6f3136c929a5
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 23⟧

Phương trình và nhóm hàm

Y. S. BRODSKY, A. K. SLIPENKO

Có thể bạn đã quen thuộc với các phương trình hàm, mặc dù bạn có thể không biết chúng được gọi như vậy. Do đó, chính các phương trình hàm $f(x)=f(-x), f(-x)=-f(x), f(x+a)=f(x)$ xác định các tính chất của hàm như tính chẵn, số lẻ và tính tuần hoàn.

Nói chung, phương trình hàm là một sự tương ứng nhất định mà từ đó bạn cần tìm một hàm chưa biết.

Ví dụ: $f(x+1)+f(x)=x,$
$2f(1-x)+1=xf(x),$
$xf(x)+f\left(\frac{4}{2-x}\right)=x$.

Các nhà toán học bắt đầu nghiên cứu các phương trình hàm từ hơn hai trăm năm trước, khi bài toán cơ khí. O. Cauchy (1789-1857) đã có đóng góp to lớn cho việc nghiên cứu các phương trình như vậy. Trên các trang tạp chí của chúng tôi, chúng tôi đã xem xét phương trình hàm $f(x+y)=f(x)+f(y)$, mang tên anh ấy*). Trong bài này chúng ta sẽ xem xét một trong những phương pháp lời giải phương trình hàm số, sử dụng khái niệm quan trọng nhất của đại số hiện đại - khái niệm nhóm.

Thành phần của chức năng

Tất nhiên, bạn đã nhận thấy rằng số lượng các hàm cơ bản ban đầu được học trong một khóa học toán ở trường là tương đối ít. Ví dụ, chúng bao gồm các hàm tuyến tính, lũy thừa, hàm mũ và lượng giác. Các hàm khác có thể được lấy từ các hàm chính bằng cách sử dụng các phép tính và phép tính đại số.

Do đó, hàm $f(x)=\sin(2x+1)$ là sự kết hợp của hàm tuyến tính $g(x)=2x+1$ và hàm lượng giác $h(x)=\sin x$, tức là $f(x)=h(g(x))=(h\circ g)(x)$.

Hàm $f(x)=\lg \arcsin x$ có được là kết quả của sự kết hợp của các hàm $g(x)=\arcsin x$ và $h(x)=\lg x$. Lưu ý rằng miền định nghĩa thành phần $h\circ g$ bao gồm các giá trị $x$ của $D(g)$ mà $g(x)\in D(h)$. Trong ví dụ cuối cùng $D(g)=[-1; 1], D(h)=] 0; \infty$. [. Vì $\arcsin x>0$ ở mức $x\in] 0; 1]$, nên $D(f)=] 0; 1]$.

Nếu chúng ta lấy thành phần của các hàm tương tự này theo thứ tự ngược lại, tức là hàm $f(x)=\arcsin \lg x$, thì chúng ta nhận được $D(f)=\left[\frac{1}{10}; 10\right]$.

Thành phần của các hàm tuyến tính phân số $g(x)=\frac{-2x+1}{3x+2}$ và $h(x)=\frac{3x-2}{-x+4}$ là các hàm $f(x)=h(g(x))=$
$$\frac{3\cdot\frac{-2x+1}{3x+2}-2}{-\frac{2x+1}{3x+2}+4}=\frac{-12x-1}{14x+7}, x\neq-\frac{2}{3}.$$
Đây $D(f)=R\left\{-\frac{2}{3},-\frac{1}{2}\right\}$.

Thông thường $f\circ g\neq g\circ f$. Đồng thời đối với bất kỳ chức năng nào
$(f\circ g)\circ h=f\circ(g\circ h)$,

những gì không được biểu diễn đều bắt nguồn từ định nghĩa của thành phần.

Trận chiến

1. Tìm các thành phần $f_1\circ f_2$ và $f_2\circ f_1$ của các hàm sau:
$f_1=\frac{x-2}{3x+4}, f_2=\frac{2x+3}{5x-1}$.

2. Tìm miền tổng hợp của $1-x^2$ và $\sqrt{x}$.

3. Hãy để $f(x)=\frac{x}{\sqrt{1-x^2}}$. Tìm $f\circ f\circ f\cdots f$.

Phương trình hàm

Hãy giải quyết vấn đề tiếp theo bài toán.
Bài toán 1. Tìm tất cả các chức năng $y=f(x)$ cũng vậy
$$2f(1-x)+1=xf(x).$$

⟦folio 24⟧

Lời giải. Giả sử có hàm $f(x)$ thỏa mãn phương trình này. Thay thế $x$ bằng $1-x$, chúng ta nhận được

$$2f(x) + 1 = (1 - x)f(1 - x).$$

Từ (1) ta tìm được $f(1 - x) = \frac{1}{2}(xf(x) - 1)$.

Thay thế giá trị $f(1 - x)$ và phương trình (2), ta thu được

$$2f(x) + 1 = (1 - x) \cdot \frac{1}{2} \cdot (xf(x) - 1),$$

từ đâu $f(x) = \frac{x - 3}{x^2 - x + 4}$.

Bằng cách xác minh trực tiếp, chúng tôi tin rằng hàm kết quả thỏa mãn phương trình (1).

Trong phương trình đang xét, ký hiệu con của hàm chưa biết là hàm $f_1 = x$ và $f_2 = 1 - x$. Thay thế $x$ bằng $1 - x$ sẽ ánh xạ hàm $f_1$ và $f_2$ với nhau. Thay thế $x \rightarrow 1 - x$ sẽ mang lại một phương trình khác chứa $f(x)$ và $f(1 - x)$. Chúng tôi đã giảm Lời giải của phương trình hàm thành lời giải của một hệ gồm hai phương trình tuyến tính có hai ẩn số.

Bây giờ chúng ta hãy xem xét bài toán phức tạp hơn.

Bài 2. Giải phương trình

$$xf(x) + 2f\left(\frac{x - 1}{x + 1}\right) = 1.$$

Lời giải. Hãy thử hành động tương tự như trong trường hợp đầu tiên. Hãy thay thế $x \rightarrow \frac{x - 1}{x + 1}$. chúng tôi nhận được

$$\frac{x - 1}{x + 1}f\left(\frac{x - 1}{x + 1}\right) + 2f\left(-\frac{1}{x}\right) = 1.$$

Cùng với các biểu thức $f(x)$ và $f\left(\frac{x - 1}{x + 1}\right)$ giờ đây chúng ta có một “ẩn số” mới $-f\left(-\frac{1}{x}\right)$. Hãy thử áp dụng thêm một phép thay thế nữa cho (3): $x \rightarrow -\frac{1}{x}$. chúng tôi có

$$-\frac{1}{x}f\left(-\frac{1}{x}\right) + 2f\left(\frac{x + 1}{1 - x}\right) = 1.$$

Ngoài $f\left(-\frac{1}{x}\right)$, biểu thức “không xác định” $f\left(\frac{x + 1}{1 - x}\right)$ đã xuất hiện trong phương trình. Nào, chúng ta hãy thử thực hiện phép thay thế $x \rightarrow \frac{x + 1}{1 - x}$ thành (3). Và cuối cùng, chúng tôi xóa nó. chúng tôi nhận được

$$\frac{x + 1}{1 - x}f\left(\frac{x + 1}{1 - x}\right) + 2f(x) = 1,$$

trong đó chưa phát sinh ẩn số mới, một hệ gồm bốn phương trình tuyến tính (3) - (6) với bốn ẩn số $f(x)$, $f\left(\frac{x - 1}{x + 1}\right)$, $f\left(-\frac{1}{x}\right)$ và $f\left(\frac{x + 1}{1 - x}\right)$ được xây dựng. Chúng tôi loại trừ tuần tự $f\left(\frac{x - 1}{x + 1}\right)$, $f\left(-\frac{1}{x}\right)$, $f\left(\frac{x + 1}{1 - x}\right)$ và tìm $f(x) = \frac{4x^2 - x + 1}{5x(x - 1)}$ ($x \neq -1, x \neq 0, x \neq 1$).

Như với lời giải của phương trình (1), chúng tôi giả định rằng tồn tại hàm thỏa mãn (3). Kiểm tra cho thấy $f$ thỏa mãn phương trình (3).

Nhóm xuất hiện

Hãy thử tìm hiểu lý do tại sao chúng ta có thể giải được phương trình của đoạn trước.

Hãy xem xét một phương trình khác

$$f(x + 1) + f(x) = x.$$

Nó trông không “đáng sợ” hơn phương trình (3), nhưng mọi nỗ lực giải nó theo cách tương tự đều vô ích: khi thay thế $x \rightarrow x + 1$, “không xác định” $f(x + 2)$ xuất hiện, v.v. Dây chuyền không thể thay thế được: chúng ta sẽ không bao giờ có được một hệ thống tuyến tính.

Hãy nhớ lại rằng khi giải phương trình đầu tiên, chúng ta đã thực hiện phép thay thế $x \rightarrow 1 - x$. Đồng thời $1 - x \rightarrow x$. Nghĩa là, hai hàm $g_1(x) = x$ và $g_2(x) = 1 - x$ đối với thao tác kết hợp hoạt động như $g_1 \circ g_2 = g_2 \circ g_1 = g_2$, $g_2 \circ g_2 = g_1$, $g_1 \circ g_1 = g_1$.

Hãy xem xét bảng “nhân” (tại giao điểm của hàng được đánh số $i$ và cột được đánh số $j$ có $g_i \circ g_j$).

Mỗi hàng và cột của bảng này chứa cả $g_1$ và $g_2$.

Bây giờ hãy nói rằng chúng ta cần

⟦folio 25⟧

giải phương trình

$$a(x)f(x) + b(x)f(1-x) = c(x),$$

(*)

trong đó $a, b, c$ là một số hàm. Rõ ràng là bằng cách thay thế $x \rightarrow 1-x$ chúng ta thu được phương trình

$$a(1-x)f(1-x) + b(1-x)f(x) = c(1-x),$$

(**)

cùng với phương trình (*) tạo thành một hệ tuyến tính gồm các hàm tương đối $f(x)$ và $f(1-x)$. Hơn nữa lời giải sẽ phát triển theo cách tương tự như với lời giải bài toán 1.

Trong ví dụ thứ hai, chúng tôi đã thay thế

$$x \rightarrow \frac{x-1}{x+1}, x \rightarrow -\frac{1}{x}, x \rightarrow \frac{x+1}{1-x},$$

nghĩa là, tên liên quan đến chức năng

$$g_1(x) = x, g_2(x) = \frac{x-1}{x+1},$$

$$g_3(x) = -\frac{1}{x}, g_4(x) = \frac{x+1}{1-x}.$$

Chúng ta hãy xem các hàm $g_1, g_2, g_3, g_4$ hoạt động như thế nào liên quan đến hoạt động tổng hợp. Soạn bảng 2 tương tự bảng 1 (giao nhau giữa hàng $i$ và cột $k$ ta viết $g_i \circ g_k$).

Bảng này đối xứng qua đường chéo của nó (điều này có nghĩa là $g_i \circ g_k = g_k \circ g_i$ với mọi $k$ và $i$). Hơn nữa, tất cả các hàm $g_i$ đều xuất hiện ở mọi hàng và mọi cột bằng nhau một lần, và cuối cùng rất dễ nhận thấy rằng $g_3 = g_2^2, g_4 = g_3^2, g_1 = g_2^4$. Đây $g_i^2 = g_2 \circ g_2 \circ \dots \circ g_2$.

Như vậy, hệ hàm $G = \{g_1, g_2, g_3, g_4\}$ có các tính chất sau: a) nó đóng dưới phép hợp; b) trong số các hàm này có một ánh xạ giống hệt nhau $g_1(x) = x$; c) mỗi hàm số $g_i$ có ​​nghịch đảo $g_i^{-1}: g_1^{-1} = g_1, g_2^{-1} = g_4, g_3^{-1} = g_3, g_4^{-1} = g_2$.

Hệ hàm số $G = \{g_1, g_2\}$ ở ví dụ 1 có tính chất tương tự.

Nếu bây giờ chúng ta được yêu cầu giải bất kỳ phương trình hàm nào có dạng

$$a(x)f(x) + b(x)f\left(\frac{x-1}{x+1}\right) + c(x)f\left(-\frac{1}{x}\right) + d(x)f\left(\frac{x+1}{1-x}\right) = h(x),$$

(***)

chúng ta sẽ làm điều này bằng cách thực hiện các thay thế $x \rightarrow g_2(x), x \rightarrow g_3(x), x \rightarrow g_4(x)$, sau đó chúng ta sẽ đạt được một hệ thống tuyến tính. Ví dụ: hãy viết ra kết quả của (***) sau khi thay thế $x \rightarrow g_2(x)$.

Hơn nữa, $g_2(x) \rightarrow g_3(x), g_3(x) \rightarrow g_4(x), g_4(x) \rightarrow g_1(x)$, nên ta thu được phương trình

$$a\left(\frac{x-1}{x+1}\right)f\left(\frac{x-1}{x+1}\right) + b\left(\frac{x-1}{x+1}\right)f\left(-\frac{1}{x}\right) + c\left(\frac{x-1}{x+1}\right) \cdot f\left(\frac{x+1}{1-x}\right) + d\left(\frac{x-1}{x+1}\right)f(x) = h\left(\frac{x-1}{x+1}\right).$$

Bây giờ chúng tôi đưa ra định nghĩa sau.

Về giới hạn. Một tập hợp tùy ý $G$ của một hàm được xác định trên một tập hợp $M$ nào đó được gọi là *epynnoi* đối với phép toán $\circ$ nếu nó có cùng các thuộc tính với hệ thống $(g_1, g_2, g_3, g_4)$, tức là

1. Đối với hai hàm $f \in G, g \in G$ bất kỳ, thành phần $f \circ g$ của chúng cũng thuộc về $G$.
2. Hàm $e(x) = x$ thuộc về $G$.
3. Đối với mọi hàm $f \in G$ đều có hàm nghịch đảo $f^{-1}$ thuộc về $G$.

Định nghĩa này là trường hợp đặc biệt của định nghĩa tổng quát của khái niệm nhóm - một trong những khái niệm quan trọng nhất của toán học hiện đại. Các khái niệm cơ bản của lý thuyết nhóm được trình bày chi tiết và phổ biến trong cuốn sách “Giới thiệu về lý thuyết nhóm” của P. S. Aleksandrov (Thư viện «Kvant», số 7, M.: Nauka, 1980).

Chúng ta đã thấy hai ví dụ về nhóm chức năng. Hãy đưa ra một vài ví dụ nữa.

a) Đặt $G$ của hàm tuyến tính $f(x) = ax + b$, ($a \neq 0, b \in R$);

b) $G = \{x, \frac{1}{1-x}, \frac{x-1}{x}\} \in R\{0, 1\}$;

b) $G = \{x, \frac{1}{1-x}, \frac{x-1}{x}\} \in R\{0, 1\}$;
