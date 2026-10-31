---
id: 1979-2-ovchinnikov-sharyigin-reshenie-neravenstv-s-modulem-f43cc6a1
issue: kvant_1979_2
year: 1979
number: "2"
title: Lời giải bất đẳng thức với mô đun
authors:
  - Овчинников С. В.
  - Шарыгин И. Ф.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 50
page_last: 53
page_labels: 48-51
tag: YI3I
lang: vi
source: kvant_digital
extraction: vision
content_sha256: bba1f2e84a2c9d41c5c430dd154c9c3ae15ced889b375e38d22c3741c8d771ef
prompt_sha256: draft-1
translated_from: content/ru/1979/02/articles/17_ovchinnikov-sharyigin-reshenie-neravenstv-s-modulem-f43cc6a1.md
source_content_sha256: c3755d71a3aa205d6354a10a5457da892503273ac46275af27091af76a5b94e9
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 48⟧

Lời giải bất đẳng thức với mô hình

Ghi chú này phác thảo một kỹ thuật, theo một nghĩa nào đó, sẽ “tự động” khớp các bất đẳng thức lời giải chứa một biến dưới dấu mô hình với các hệ lời giải và các tập hợp các bất đẳng thức trong đó các biến đã không có dấu mô hình.

Giả sử đây là một số bất đẳng thức - để đơn giản, đối với bất đẳng thức có cùng một biến:

$$f(x) > 0,$$
$$g(x) > 0.$$

Chúng ta hãy biểu thị tập lời giải của các bất đẳng thức (1) bằng $A$ và các bất đẳng thức (2) bằng $B$.

Nếu cần tìm một tập hợp số thỏa mãn đồng thời bất đẳng thức (1) và bất đẳng thức (2), tức là tìm giao điểm $C = A \cap B$ của tập hợp $A$ và $B$ thì các bất đẳng thức (1), (2) được nối với nhau bằng một hình có dấu ngoặc

$$\begin{cases} f(x) > 0, \\ g(x) > 0 \end{cases}$$

và được gọi là hệ bất đẳng thức (“Đại số và nguyên lý giải tích 10”, đoạn 123).

Nếu bạn muốn tìm một tập hợp số thỏa mãn bất đẳng thức (1) hoặc bất đẳng thức (2), tức là tập hợp $D = A \cup B$ $A$ và $B$ thì các bất đẳng thức (1), (2) được nối với nhau bằng dấu ngoặc vuông

$$\begin{cases} f(x) > 0, \\ g(x) > 0 \end{cases}$$

và được gọi là một tập hợp không

của cải *).

Chúng ta hãy nhắc lại một lần nữa: khi họ đang tìm một ngã tư, họ nói “hệ thống”; khi họ đang tìm kiếm một sự liên tưởng, họ nói “toàn bộ”. Bảng hiển thị ba cặp ký tự được hiểu tương ứng **).

Đối với lời giải bài toán, như chúng ta sẽ thấy bây giờ, chúng ta thường phải xem xét sự kết hợp giữa các hệ thống và tổng hợp; Để tránh sai sót trong những trường hợp như vậy, bạn nên sử dụng cẩn thận các ký hiệu sau.

* *

Sau đây là một ví dụ chung về bất đẳng thức lời giải chứa một biến dưới dấu mô hình, “sự tiết lộ” của mô hình. Dựa vào định nghĩa mô hình

$$|x| = \begin{cases} x, \text{ если } x \geqslant 0, \\ -x, \text{ если } x < 0, \end{cases}$$

tập hợp các giá trị cho phép của biến được chia thành các tập hợp con rời rạc, trên mỗi tập hợp đó tất cả các hàm chứa dấu .modula đều giữ nguyên dấu của chúng. Sau đó, lời giải của bài toán ban đầu giảm xuống còn lời giải tổng của hệ bất đẳng thức.

Ví dụ: giả sử bạn cần giải bất đẳng thức

$$|x-1| + |x-2| > 3+x$$

Kích thước của trục số tại điểm không giao nhau

*) Hoàn toàn giống với định nghĩa của thuật ngữ “hệ phương trình” và “tập phương trình” (“Đại số và nguyên lý giải tích 10”, đoạn 122).

**) Có thể tiếp tục bảng bằng cặp từ “liên từ - phân ly”; về những điều khoản này, ví dụ, xem «Kvant», 1971, No. 4, p. 15, hay 1947, số 12, tr. 14, hay 1975, số 1, tr. 29.

⟦folio 49⟧

Chọn các khoảng $|x| < 1$, $-(x-1)-(x-2) > 3+x$, $1 \leqslant x < 2$, $(x-1)-(x-2) > 3+x$, $x \geqslant 2$, $(x-1)+(x-2) > 3+x$.

Tập lời giải của hệ trên là giao $|x| < \infty$; $1[\cap] < \infty$; $0[$, tức là khoảng $|x| < \infty$; $0[$, hệ thống trung gian lời giải không có; cuối cùng, tập lời giải của hệ thống dưới là giao điểm $[2; +\infty][\cap]; 6 +\infty[$, tức là khoảng $|x| < \infty$; $0[$, Kết hợp (tổng cộng!) của các tập hợp kết quả, chúng ta thu được đáp số: $|x| < \infty$; $0[ \cup ] 6; +\infty[$.

Với phương pháp này lời giải người ta thường phải xem xét nhiều trường hợp và đôi khi thậm chí cả các trường hợp con. Ngoài ra, đôi khi việc tiết lộ một mô hình còn liên quan đến những khó khăn về mặt kỹ thuật (xem ví dụ 4 bên dưới).

* *

Ví dụ hứa hẹn ở trên dựa trên một định lý đơn giản:

1) $|f(x)| \leqslant g(x)$ $\Leftrightarrow$ $\begin{cases} f(x) \leqslant g(x), \\ f(x) \geqslant -g(x); \end{cases}$
2) $|f(x)| \geqslant g(x)$ $\Leftrightarrow$ $\begin{cases} f(x) \geqslant g(x), \\ f(x) \leqslant -g(x). \end{cases}$

Nó có thể được chứng minh dễ dàng bằng cách “tiết lộ” mô hình. Ví dụ: giả sử $x_0$ là nghiệm của bất đẳng thức $|f(x)| \leqslant g(x)$, tức là $|f(x_0)| \leqslant g(x_0)$.

Sau đó $g(x_0) \geqslant 0$. Nếu $f(x_0) \geqslant 0$ thì $|f(x_0)| = f(x_0)$ và bất đẳng thức (3) có dạng $f(x_0) \leqslant g(x_0)$.

Vì $f(x_0) \geqslant 0$ và $g(x_0) \geqslant 0$, $f(x_0) \geqslant -g(x_0)$.

Bất đẳng thức (4), (5) có nghĩa là trong trường hợp đang xét $x_0$ là nghiệm của hệ $\begin{cases} f(x) \leqslant g(x), \\ f(x) \geqslant -g(x). \end{cases}$ Nếu $f(x_0) < 0$ thì $|f(x_0)| = -f(x_0)$ và bất đẳng thức (3) có dạng $-f(x_0) \leqslant g(x_0)$, tương đương với bất đẳng thức (5). Bất đẳng thức (4) đúng trong trường hợp này do thực tế là $f(x_0) < 0$ và $g(x_0) \geqslant 0$.

Hãy tự mình chứng minh định lý.

Tất nhiên, định lý vẫn đúng khi thay dấu nâng của bất đẳng thức chặt $\leqslant$ bằng dấu của bất đẳng thức chặt $<$.

* *

Ví dụ 1. (Khoa Georgian của Đại học quốc gia Moscow, 1977). Giải bất đẳng thức
$2|x+1| > x+4$.

Lời giải.
$2|x+1| > x+4 \Leftrightarrow \begin{cases} 2x+2 > x+4, \\ 2x+2 < -x-4 \end{cases} \Leftrightarrow \begin{cases} x > 2, \\ x < -2. \end{cases}$

Ví dụ 2. (Khoa Địa chất Đại học Tổng hợp Matxcơva, 1977). Giải bất đẳng thức
$|x-2| \leqslant 2x^2-9x+9$.

Lời giải.
$|x-2| \leqslant 2x^2-9x+9 \Leftrightarrow \begin{cases} x-2 \leqslant 2x^2-9x+9, \\ x-2 \geqslant -2x^2+9x-9 \end{cases} \Leftrightarrow \begin{cases} 2x^2-10x+11 \geqslant 0, \\ 2x^2-8x+7 \geqslant 0. \end{cases}$

Các bất đẳng thức Lời giải có trong hệ thống thu được được mô tả theo các độ rộng khác nhau trong Hình 1. Lấy giao điểm của chúng, chúng ta thu được đáp số:
$-\infty; \frac{4-\sqrt{2}}{2} \cup \left[ \frac{5+\sqrt{3}}{2}; +\infty \right]$.

Chúng ta hãy quay trở lại với bất đẳng thức ban đầu được giải bằng cách “mở” mô hình.

Ví dụ 3. Giải bất đẳng thức
$|x-1| + |x-2| > 3+x$.

Cơm. 1.

⟦folio 50⟧

Lời giải. Áp dụng định lý hai lần, ta có
$$|x-1|+|x-2| > 3+x \Leftrightarrow
\Leftrightarrow |x-1| > 3+x-|x-2| \Leftrightarrow
\Leftrightarrow \begin{cases} x-1 > 3+x-|x-2|, \\ x-1 < -3-x+|x-2| \end{cases} \Leftrightarrow
\Leftrightarrow \begin{cases} |x-2| > 4, \\ |x-2| > 2x+2 \end{cases} \Leftrightarrow
\Leftrightarrow \begin{cases} x-2 > 4, \\ x-2 < -4, \\ x-2 > 2x+2, \\ x-2 < -2x-2 \end{cases} \Leftrightarrow
\Leftrightarrow \begin{cases} x > 6, \\ x < -2, \\ x < -\frac{4}{3}, \\ x < 0 \end{cases} \Leftrightarrow
\Leftrightarrow \begin{cases} x \leq 2, \\ 3^x \geq 1, \\ 3^x \geq 9, \\ x \leq 0 \end{cases} \Leftrightarrow
\Leftrightarrow \begin{cases} x \leq 2, \\ x \geq 0, \\ x \geq 2, \\ x \leq 0 \end{cases}$$

Đáp số: $]-\infty;0[ \cup ]6;+8[$.

Có thể dễ dàng lấy được Lời giải của tất cả bài toán trước đó bằng cách “vẽ” mô hình. Ví dụ sau khá khó giải, trong khi định lý đã được chứng minh lại rất dễ giải.

Ví dụ 4. Giải bất đẳng thức
$$|3^x+4x-9|-8| \leq 3^x-4x-1.$$

Lời giải. Một lần nữa áp dụng định lý hai lần:
$$||3^x+4x-9|-8| \leq 3^x-4x-1 \Leftrightarrow
\Leftrightarrow \begin{cases} |3^x+4x-9| \leq 3^x-4x+7, \\ |3^x+4x-9| \geq -3^x+4x+9 \end{cases} \Leftrightarrow
\Leftrightarrow \begin{cases} 3^x+4x-9 \leq 3^x-4x+7, \\ 3^x+4x-9 \geq -3^x+4x-7, \\ 3^x+4x-9 \geq -3^x+4x+9, \\ 3^x+4x-9 \leq 3^x-4x-9 \end{cases}$$
Do đó, tập hợp yêu cầu bằng $[0; 2] \cap (1-\infty; 0] \cup [2; +\infty]$.

Đáp số: $\{0, 2\}$.

Chúng ta sẽ kết thúc ghi chú này bằng bất đẳng thức có tham số.

Ví dụ 5. Giải bất đẳng thức
$$|1-|x||<a-x.$$

Lời giải.
$$1-|x||<a-x \Leftrightarrow
\Leftrightarrow \begin{cases} 1-|x| < a-x, \\ 1-|x| > -a+x \end{cases}$$

⟦folio 51⟧

hệ thống đã giải quyết
$$\begin{cases} x < \frac{a+1}{2}, \\ a > -1. \end{cases}$$

Trong Hình 4, giao điểm của hai tập hợp này được tô bóng, tức là tập lời giải của hệ tương đương với bất đẳng thức ban đầu. Từ hình này, khá dễ dàng để viết ra đáp số: cho $a \in ] -\infty; -1]$ lời giải không, cho $a \in ] 1; +\infty[$

Chúng tôi có $x \in ] -\infty; \frac{a-1}{2}$[$,$ cho $a \in ] 1; +\infty[$

Chúng tôi có $x \in ] -\infty; \frac{a+1}{2}$[$.$

Một người đọc chú ý có thể nhận thấy điều sau: nếu các tác giả đã sử dụng mặt phẳng $Oxa$, thì việc vẽ đồ thị của hàm số trên mặt phẳng này ngay từ đầu chẳng phải sẽ dễ dàng hơn sao?
$$a=x+|1-|x|$$
và nhìn vào khu vực phía trên biểu đồ này, hãy viết ra đáp số. Người đọc này chắc chắn đúng. (Đường màu đỏ trong Hình 4 là đồ thị của hàm $a=x+|1-|x|$.)

Phương pháp sử dụng mặt phẳng tọa độ, một trong các trục của nó là trục của các giá trị tham số, rất mạnh mẽ và với sự trợ giúp của nó, nhiều bài toán bài toán khó đã được giải quyết.

bị sốc
Giải các bất đẳng thức sau (bài toán 1-4):
1. (Khoa Sinh học Đại học Quốc gia Mátxcơva, 1968) $|3x+2| \leq x^2+x$.
2. (Khoa Vật lý, Đại học Quốc gia Mátxcơva, 1974) $3|x-1| > (x-1)^2+1$.
3. (Khoa Georgian của Đại học quốc gia Moscow, 1977)
a) $3|x-1| \leq x+3$;
b) $4|x+2| < 2x+10$;
b) $3|x+1| \geq x+5$.
4. (Khoa Địa chất Đại học Quốc gia Mátxcơva, 1977)
a) $3x^2-|x-3| > 9x-2$;
b) $x^2+4 \geq |3x-2|-7x$;
b) $x^2-|5x-3| < x<2$.
5. (Khoa Kinh tế Chính trị, Khoa Kinh tế, Đại học Tổng hợp Matxcơva, 1977)
a) Xác định xem $a$ bất đẳng thức $3-|x-a| > x^2$ có ít nhất một âm lời giải.
b) Xác định xem $a$ bất đẳng thức $2>|x+a|+x^2$ có ít nhất một dương lời giải.

*) Xem «Kvant», 1970, số 9, tr. 19.
