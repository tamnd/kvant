---
id: 1976-12-tolpyigo-invariantyi-60700968
issue: kvant_1976_12
year: 1976
number: "12"
title: Bất biến
authors:
  - Толпыго А. К.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 21
page_last: 26
page_labels: 19, 21, 22, 24
tag: HIKB
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 10dd36e536838ff1161492b193dba7bca846e5cc31537cc1eda2cc155e1b98a3
prompt_sha256: draft-1
translated_from: content/ru/1976/12/articles/08_tolpyigo-invariantyi-60700968.md
source_content_sha256: af98cfd9d62726e3b76cf52876b7f030bad5ac662d26ebb4f54d3cfbe8a4c02b
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 19⟧

Bất biến

Trong «Kvant» người ta đã viết về lời giải bài toán bằng cách sử dụng phép chọn bất biến (1976, số 2, trang 32). Bài viết này thảo luận về khái niệm bất biến và một số câu hỏi có thể có liên quan đến nó.

1. Cài đặt chung bài toán

Với sự trợ giúp của các bất biến, bài toán thuộc loại sau đã được giải: dữ liệu của tập hợp $M$ (chúng ta sẽ gọi các phần tử của nó là “vị trí”) và các quy tắc mà chúng ta di chuyển từ vị trí này sang vị trí khác; Có thể di chuyển từ vị trí nhất định $\alpha$ trong vài bước sang vị trí nhất định khác $\beta$ không? Tổng quát hơn bài toán: làm cách nào chúng ta có thể xác định một cặp vị trí tùy ý $\alpha$, $\beta$ liệu có thể đi từ $\alpha$ đến $\beta$ trong một vài bước hay không?

Rõ ràng, các tình huống được mô tả có thuộc tính sau: nếu từ vị trí $\alpha$ người ta có thể đi đến vị trí $\beta$ và từ $\beta$ người ta có thể đi đến vị trí $\gamma$, thì từ $\alpha$ người ta có thể đi đến $\gamma$. Tính chất này được gọi là tính xuyên suốt.

Hãy xem xét một bài toán cụ thể.

Bài toán 1. Vòng tròn được chia thành các khu vực trong đó $n$ chip được xem xét bằng cách nào đó. Có thể di chuyển đồng thời hai chip bất kỳ: một - một khu vực theo chiều kim đồng hồ, khu vực còn lại - một khu vực theo hướng ngược lại. Có thể từ vị trí $\mu$, trong đó có một chip trong mỗi khu vực, để chuyển từ vị trí $\alpha$ sang bất kỳ vị trí nào khác thuộc cùng một vị trí không?

*) «Kvant», 1972, № 2, c. 2.

⟦folio 21⟧

Vấn đề là nếu $f$ là một bất biến, thì nói chung, không có gì theo sau $f(\alpha) = f(\beta)$. Nếu $f(\alpha) \neq f(\beta)$ thì vị trí $\alpha$ và $\beta$ không tương đương (điều này suy ra từ (1)). Nếu $f(\alpha) = f(\beta)$, thì vị trí $\alpha$ và $\beta$ có thể tương đương hoặc không tương đương: bất biến không bị cấm lấy các giá trị giống nhau trên các quỹ đạo khác nhau. (Ví dụ: hàm hằng, tức là hàm nhận cùng một giá trị trên tất cả các phần tử từ $M$, cũng là bất biến.)

Làm thế nào điều này có thể được? Hãy thử cho mỗi $n$ gõ 4 $k$ để chuyển từ vị trí $\mu$ sang vị trí $v$... Vì lý do nào đó, nó không hoạt động. Hãy thử tìm một bất biến khác tinh tế hơn.

Các cung Zanuterum (giả sử theo chiều kim đồng hồ) từ 1 đến $n$. Đối với sự sắp xếp tùy ý của $\alpha$ fizek trong các lĩnh vực, chúng ta hãy biểu thị bằng $a_k(\alpha)$ số lượng fizek trong lĩnh vực $k$-thứ với sự sắp xếp $\alpha$. Bây giờ chúng ta hãy xem xét hàm sau $q$:
$$q(\alpha) = 1 \cdot a_1(\alpha) + 2 \cdot a_2(\alpha) + 3 \cdot a_3(\alpha) + \dots + n \cdot a_n(\alpha).$$

Hàm $q$ có bất biến không? Chuyển động cho phép tùy ý (Hình 5) ảnh hưởng đến 4 số hạng của tổng (2):
$$\dots + i \cdot a_i(\alpha) + (i + 1) \cdot a_{i+1}(\alpha) + \dots + (j - 1) \cdot a_{j-1}(\alpha) + j \cdot a_j(\alpha) + \dots$$

Khi di chuyển như hình 5 thì tổng (3) biến rất indo thành tổng
$$\dots + i \cdot [a_i(\alpha) - 1] + (i + 1) \cdot [a_{i+1}(\alpha) + 1] + \dots + (j - 1) \cdot [a_{j-1}(\alpha) + 1] + j \cdot [a_j(\alpha) - 1] + \dots$$

Dễ dàng kiểm tra được cả hai tổng bằng nhau. Vì vậy, $q$ là một bất biến! Không, chúng tôi đã tuyên bố rằng khu vực thứ $n$ giáp khu vực đầu tiên. Điều này có nghĩa là có thêm 3 khả năng nữa (Hình 6-8). Một phép tính tương tự như vừa thực hiện cho thấy rằng trong trường hợp hiển thị ở Hình 6, $q(\alpha)$ sẽ giảm $n$ và trong trường hợp Hình 7, nó sẽ tăng $n$. Trong trường hợp thứ ba, $q(\alpha)$ tất nhiên sẽ không thay đổi. Vì vậy, trong một lần di chuyển, giá trị của hàm $q$ có thể thay đổi, nhưng chỉ bằng $n$. Sledova-

⟦folio 22⟧

Do đó, $q(v) = l \cdot n$ và $r(v) = 0$ (bất kể $n$ và $l$ là gì). Ở phía bên kia,
$$a_1(\mu) = a_2(\mu) = \dots = a_n(\mu) = 1.$$
Có nghĩa,
$$q(\mu) = 1 + 2 + 3 + \dots + n = \frac{n(n+1)}{2}.$$
Nếu $n = 2m$ thì $q(\mu) = n \cdot m + m$ và $r(\mu) = m \neq 0$. Do đó, nếu $n$ chẵn, chúng ta nhận được $r(\mu) \neq r(v)$. Vì vậy, đối với $n$ chẵn, vị trí $\mu$ và $v$ không tương đương.
Nếu $n = 2m + 1$ thì $q(\mu) = n \cdot (m+1)$ và $r(\mu) = 0$. Do đó, với số chẵn $n$, chúng ta lại có: $r(\mu) - r(v)$. Hóa ra là ngay cả với $n$ câu hỏi về sự tương đương của vị trí $\mu$ và $v$ một lần nữa vẫn còn bỏ ngỏ.

3. Bất biến phổ quát

Chúng ta hãy gọi phổ biến $f$ bất biến nếu nó nhận các giá trị khác nhau ở các vị trí không tương đương:
nếu $\alpha \neq \beta$ thì $f(\alpha) \neq f(\beta)$.
Do đó, đối với bất biến phổ quát $f$
nếu $f(\alpha) = f(\beta)$ thì $\alpha \sim \beta$.
Bất biến phổ quát có giá trị riêng trên mỗi quỹ đạo. Vì đối với một bất biến phổ quát
$$\alpha \sim \beta \iff f(\alpha) = f(\beta),$$
một bất biến phổ quát cho bất kỳ cặp vị trí nào cho phép chúng ta xác định xem chúng có tương đương hay không.
Làm cách nào để kiểm tra xem bất biến neokot $f$ có phổ biến không? Không có phương pháp chung. Định lý đơn giản sau đây có thể giúp ích.
Nếu $a)$ có các vị trí $\delta_1, \delta_2, \dots, \delta_l$ sao cho mỗi vị trí $\alpha \in M$ tương đương với một trong số chúng và $b)$ bất biến $f$ nhận ít nhất $l$ giá trị khác nhau thì $f$ là bất biến phổ quát và các vị trí $\delta_i, \delta_j (i \neq j)$ không tương đương theo cặp.
Từ $a)$ suy ra có nhiều nhất $l$ quỹ đạo. Từ $b)$ suy ra có ít nhất $l$ quỹ đạo. Do đó, có chính xác $l$ quỹ đạo. Một lần nữa từ $b)$, bây giờ theo sau, $f$ bất biến nhận chính xác $l$ giá trị và giá trị, $f$ là phổ quát. Cuối cùng, từ $a)$, các vị trí $\delta_1, \delta_2, \dots, \delta_l$ có các quỹ đạo khác nhau và do đó, không tương đương theo cặp.

Bài toán 1 (kết thúc). Hãy để chúng tôi chứng minh rằng bất biến $r$ là phổ biến. Chúng ta hãy biểu thị bằng $\delta_i$ sự sắp xếp các bài tập sau: một bài tập nằm trong lĩnh vực $i$, tất cả các bài tập còn lại nằm trong lĩnh vực $n$. Tất nhiên, trong $\delta_n$, chúng tôi sẽ ghép nối sự sắp xếp trong đó tất cả các vật lý $n$ đều nằm trong khu vực $n$.

Có thể dễ dàng báo cáo rằng bất kỳ sự sắp xếp nào cũng tương đương với một trong các vị trí $\delta_1, \delta_2, \dots, \delta_n$. Trên thực tế, $a$ trống - một sự sắp xếp tùy ý của các đơn vị vật lý. Hãy cố gắng thu thập tất cả các đơn vị vật lý $n$ trong khu vực $n$. Để làm điều này, chúng tôi sẽ xoay fizek đầu tiên cho đến khi đưa nó vào khu vực $n$-thứ; đồng thời, theo quy định, chúng ta sẽ di chuyển fizek thứ hai theo hướng ngược lại. Sau đó, chúng ta sẽ lái fizek thứ hai vào khu vực thứ $n$, di chuyển fizek thứ ba theo hướng ngược lại, v.v. - cho đến fizek thứ $(n-1)$. Khi chúng ta đưa vật chất $n-1$ vào khu vực $n$, vật lý $n$ sẽ nằm trong một số khu vực $i$ $(i=1, 2, \dots, n)$. Điều này có nghĩa là $\alpha \sim \delta_i$.

Hãy đếm $r(\delta_i)$. Tại $i \neq n$:
$$\begin{cases} a_1(\delta_i) = a_2(\delta_i) = \dots = a_{i-1}(\delta_i) = \\ = a_{i+1}(\delta_i) = \dots = a_{n-1}(\delta_i) = 0, \\ a_i(\delta_i) = 1, \\ a_n(\delta_i) = n-1. \end{cases}$$
Do đó, $q(\delta_i) = i \cdot 1 + n \cdot (n-1)$ và $r(\delta_i) = i$. Ngoài ra, $q(\delta_n) = n \cdot n$ và $r(\delta_n) = 0$. Vì vậy, $r$ bất biến nhận ít nhất các giá trị $n$.

Theo định lý, bất biến $r$ là phổ quát và các vị trí $\delta_1, \delta_2, \dots, \delta_n$ không tương đương theo cặp.

Vì $r$ là một bất biến phổ quát,
$$\alpha \sim \beta \iff r(\alpha) = r(\beta).$$

⟦folio 24⟧

xảy ra đồng thời khi và chỉ khi vị trí α và β bằng nhau.

Bản chất của định nghĩa này là gì? Nếu vị trí α và β tương đương nhau thì vì $f_1, f_2, \dots, f_k$ là bất biến nên từng đẳng thức của hệ (5) vẫn được thỏa mãn. “Theo hướng này” canvas không liên quan gì đến nó. Nếu các bất biến $f_1, f_2, \dots, f_k$ là phổ quát, thì sự tương đương của các vị trí α và β sẽ tuân theo bất kỳ đẳng thức nào của hệ (5). Chúng ta không được cung cấp tính phổ quát của chúng, nhưng khi đó yêu cầu việc thực thi đồng thời hệ thống (5) sẽ làm lệch vị trí của α và β. Đây chính xác là bản chất của khái niệm canvas. Do đó, mặc dù một số bất biến $f_1, f_2, \dots, f_k$ có ​​thể nhận cùng một giá trị ở các vị trí không tương đương α, β, nhưng các giá trị của tập hợp $\langle f_1, f_2, \dots, f_k \rangle$ trên chúng là khác nhau.

Một hệ bất biến hoàn chỉnh là sự khái quát hóa của khái niệm bất biến phổ quát: nếu $f$ là một bất biến phổ quát, thì hệ $\langle f \rangle$, bao gồm một bất biến, tất nhiên là hoàn chỉnh.

Bài toán 3. Các số nguyên được viết trong bảng 2×2. Thứ nhất, được phép đồng thời trong bất kỳ bảng nào: thêm 2 vào một số, lấy 2 từ một số khác và thứ hai, đồng thời ở bất kỳ hàng nào: thêm 3 vào một số, lấy 3 từ một số khác. Những bảng nào tương đương?

Hãy xem xét ba hàm: cho bất kỳ bảng nào

$$\alpha = \begin{pmatrix} a & b \\ c & d \end{pmatrix}$$

chúng ta hãy biểu thị bằng $p(\alpha)$ tổng $a + b + c + d$, bằng $q(\alpha)$ phần còn lại của số $a + b$ chia cho 2 và bằng $r(\alpha)$ phần còn lại của số $a + c$ chia cho 3. Các hàm $p, q, r$ là bất biến. Không khó lắm để chứng minh một bảng α tùy ý tương đương với bảng

$$\begin{pmatrix} 0 & q(\alpha) \\ r(\alpha) & p(\alpha) - q(\alpha) - r(\alpha) \end{pmatrix}.$$

Do đó, từ đẳng thức

$$\begin{cases} p(\alpha) = p(\beta), \\ q(\alpha) = q(\beta), \\ r(\alpha) = r(\beta) \end{cases}$$

(6)

theo đó, các bảng α và β tương đương với cùng một bảng và do đó tương đương với nhau. Và ngược lại: sự tương đương của bảng α và β là bằng (6), vì $p, q$ và $r$ là bất biến. Như vậy, $\langle p, q, r \rangle$ là một hệ thống hoàn chỉnh.

Trong quy tắc 8. Giải bài toán cho bảng $n \times n$, cho phép các phép biến đổi tương tự như trong bài toán 3. Việc mong đợi một hệ thống hoàn chỉnh gồm các bất biến 2$n$-1 là điều tự nhiên.

Quy tắc 9. Nếu $f_1, f_2, \dots, f_k$ là bất biến và $g$ là hàm số của các đối số $k$, thì hàm $h$:

$$h(\alpha) = g(f_1(\alpha), f_2(\alpha), \dots, f_k(\alpha))$$

(7) là bất biến (xem Bài tập 2). Hãy kiểm tra nó.

Quy tắc 10. Nếu $h$ là bất biến và $\langle f_1, f_2, \dots, f_k \rangle$ là một hệ bất biến hoàn chỉnh, thì cũng có hàm số $g$ của $k$ đối số, thỏa mãn (7) (xem Bài tập 3). Chứng minh điều đó.

Quy tắc 11. Tập $M$ là tập hợp các điểm của mặt phẳng số, tức là tập hợp các cặp $\langle x, y \rangle$ của các số thực. Chuyển đổi hợp lệ duy nhất là $\langle x, y \rightarrow \langle y, x \rangle$. Cho phép

$$\begin{cases} f_1(x, y) = xy, \\ f_2(x, y) = x + y. \end{cases}$$

Chứng minh rằng $\langle f_1, f_2 \rangle$ là một hệ bất biến đầy đủ.

Quy tắc 12. Tập $M$ là tập hợp các điểm trong không gian hoặc tập hợp các vết $\langle x, y, z \rangle$ gồm các số thực. Cho phép chuyển tiếp $\langle x, y, z \rightarrow \langle y, x, z \rangle$ và $\langle x, y, z \rightarrow \langle x, z, y \rangle$. Cho phép

$$f_1(x, y, z) = xyz,$$

$$f_2(x, y, z) = xy + yz + zx,$$

$$f_3(x, y, z) = x + y + z.$$

Chứng minh rằng $\langle f_1, f_2, f_3 \rangle$ là một hệ bất biến đầy đủ.

Quy tắc 13. Tập hợp $M$ bao gồm tất cả các tập hợp (hoặc bộ dữ liệu) $\langle x_1, x_2, x_3, \dots, x_n \rangle$ có thể có của các số thực (n là cố định). Được phép hoán đổi vị trí của hai số liền kề bất kỳ. Tìm một hệ bất biến hoàn chỉnh.
