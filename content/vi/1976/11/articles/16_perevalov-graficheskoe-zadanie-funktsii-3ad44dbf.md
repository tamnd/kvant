---
id: 1976-11-perevalov-graficheskoe-zadanie-funktsii-3ad44dbf
issue: kvant_1976_11
year: 1976
number: "11"
title: Phân công chức năng đồ họa
authors:
  - Перевалов Г. Е.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 49
page_last: 54
page_labels: 47-52
tag: 756I
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 4235dceaff80e165b033b023ecbf28b08921aa2f224ebcb20d265e2095a85401
prompt_sha256: draft-1
translated_from: content/ru/1976/11/articles/16_perevalov-graficheskoe-zadanie-funktsii-3ad44dbf.md
source_content_sha256: 789fa17069032a3728ddab6e763449f0e46260d41100e7dfe6f5f4b9c7ce4552
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 47⟧

Chức năng đồ họa bài toán

Mùa hè năm nay, trong kỳ thi vấn đáp đầu vào môn toán, trong một cuộc gọi, cuộc trò chuyện sau đây đã diễn ra giữa giám khảo (E) và thí sinh (A).

E. Bạn biết những phương thức nào của hàm bài toán?

A. Có ba cách để thực hiện chức năng bài toán: phân tích, dạng bảng và đồ họa.

E. Cho ví dụ về hàm được xác định bằng đồ họa.

A (sau một số cuộc trò chuyện). Có cần thiết phải xây dựng đồ thị của hàm số không? Chức năng gì?

E. Chúng ta không nói về việc xây dựng đồ thị của một hàm xác định, chẳng hạn như sử dụng công thức, mà là về việc xác định chính hàm đó bằng biểu đồ. Rốt cuộc, bạn vừa nói rằng chức năng này có thể được chỉ định bằng đồ họa. Vì vậy bạn cần thiết lập, xác định một số chức năng đồ họa.

A... (im lặng).

E. Hãy nhớ ý nghĩa của việc định nghĩa một hàm số.

A. Để xác định một hàm, bạn cần lấy hai tập hợp—tập X và tập Y—và chỉ ra sự tương ứng giữa chúng sao cho mỗi x ∈ X được liên kết với một và chỉ một phần tử từ tập hợp Y.

E. Được rồi. Bây giờ lấy mặt phẳng tọa độ - vẽ hệ tọa độ hình chữ nhật trên mặt giấy và đánh dấu đơn vị đo trên mỗi trục. Tiếp theo, lấy một số đoạn trên trục Ox - đây sẽ là tập X và trên trục Oy - một đoạn khác - tập Y. Để xác định hàm, tất cả những gì còn lại là xác định sự tương ứng giữa tập hợp này. Làm thế nào điều này có thể được thực hiện?

A. Sự tương ứng có thể được xác định bằng công thức.

E. Còn đồ họa thì sao? Nazhe quan tâm đến phương pháp đặc biệt này.

À... (im lặng).

Chúng ta đừng tiếp tục cuộc trò chuyện này nữa. Vị trí bài toán hóa ra là quá sức đối với người nộp đơn. Khó khăn của thí sinh còn do các câu hỏi “đồ họa” khác gây ra, tức là các câu hỏi liên quan đến đồ thị hàm số - mô tả tính chất của hàm theo đồ thị của nó (nghiên cứu hàm số), xây dựng đồ thị hàm số bằng cách biến đổi một đồ thị cho trước, v.v. Thảo luận về các vấn đề như vậy là mục đích của bài viết này.

Một số hướng

Chúng tôi sẽ cần hai định nghĩa mà bạn đã quen thuộc. Chúng ta hãy nhớ lại chúng và đưa ra một vài nhận xét.

Hãy lấy câu đầu tiên từ sách giáo khoa ở trường*).

Định nghĩa 1. Sự tương ứng giữa tập hợp X và tập hợp Y, trong đó mỗi phần tử của tập hợp X tương ứng với một và chỉ một phần tử của tập hợp Y, được gọi là hàm. Tập X được gọi là miền định nghĩa của hàm số.

Thứ hai là từ một bài báo của A. N. Kolmogorov**).

*) Đại số. Sách giáo khoa lớp 6 bậc trung do A. I. Marekshevich biên tập (M., “Prosveshchenie”, 1976, tr. 69).

**) A. N. Kolmogorov. Đồ thị của hàm số là gì, «Kvant», 1970, Số 2.

⟦folio 48⟧

Định nghĩa 2. Cho tập $X$ có hàm $y = f(x)$. Đồ thị của hàm $y = f(x)$ là tập hợp tất cả các cặp $(x, y)$ sao cho:

1) phần tử đầu tiên $x$ của cặp $(x, y)$ thuộc miền $X$ của hàm $y = f(x)$;
2) phần tử thứ hai $y$ của cặp $(x, y)$ là giá trị của hàm $y = f(x)$ tại điểm $x$.

Do đó, đối với hàm $f(x)$ được cho bởi bảng

$$\begin{array}{c|c|c|c|c|c|c}
x & a & b & c & d & e \\
f(x) & 2 & 1 & 3 & 2 & 1 & 5
\end{array}$$

sẽ có nhiều đồ thị
$$\Gamma_f = \{(a, 2), (6, 1), (b, 3), (r, 2), (d, 1), (e, 5)\}.$$

Đối với một hàm có miền định nghĩa vô hạn, đương nhiên không thể viết ra tất cả các cặp $(x, f(x))$. Vì vậy, chúng ta phải mô tả các cặp này một cách khác nhau. Ví dụ: đối với hàm $y = f(x) = x^2$, $x \in R$, biểu đồ bao gồm tất cả các cặp số thực có thể có dạng $(x, x^2)$, tức là từ tất cả các cặp $(x, y)$ thỏa mãn điều kiện $y = x^2$. Sử dụng ký hiệu lý thuyết tập hợp, định nghĩa đồ thị của hàm $y = x^2$ có thể được viết dưới dạng công thức
$$\Gamma_f = \{(x, y) \mid x \in R, y = x^2\}.$$
Và định nghĩa tổng quát của đồ thị của hàm $y = f(x)$, $x \in X$ có thể viết dưới dạng công thức sau:
$$\Gamma_f = \{(x, y) \mid x \in X, y = f(x)\}.$$
Trong phần tiếp theo chúng ta sẽ giới hạn bản thân ở các hàm số. Đối với các hàm số $y = f(x)$ miền bao gồm các số thực, giá trị của các hàm này cũng là số thực và biểu đồ bao gồm tất cả các cặp $(x, y)$ số thực $x$ và $y$ thỏa mãn điều kiện $y = f(x)$.

Hãy nhớ lại rằng tập hợp tất cả các cặp $(x, y)$ số thực $x$ và $y$ được gọi là mặt phẳng số và được ký hiệu bằng ký hiệu $R^2$, và bất kỳ tập hợp con điểm nào trên mặt phẳng số đều được gọi là hình hình học. Ví dụ, một hình hình học sẽ là trục $Ox$, tức là một tập hợp các điểm
$$\{(x, y) \mid x \in R, y = 0\}.$$
Đồ thị của hàm số $y = f(x)$ cũng sẽ là hình trên mặt phẳng số $R^2$.

Các điểm và hình hình học của mặt phẳng số (đặc biệt là đồ thị của các hàm số) có thể được mô tả trực quan trong bản vẽ. Để làm điều này, chúng ta xây dựng một mặt phẳng tọa độ và trên đó, bằng một điểm có tọa độ $x, y$, chúng ta mô tả điểm $(x; y)$ của mặt phẳng số.

Theo Định nghĩa 1, mỗi phần tử $x \in X$ tương ứng với một và chỉ một phần tử $y$ từ tập hợp $Y$, do đó, tập hợp $\Gamma_f$ - đồ thị của hàm $y = f(x)$ - không được chứa hai cặp có phần tử đầu tiên chung và phần tử thứ hai khác nhau, tức là trên đồ thị của hàm số không được có hai điểm có cùng hoành độ và tọa độ khác nhau. Chúng ta hãy xây dựng thực tế này dưới dạng một định lý.

Định lý 1. Nếu tập $\Gamma_f$ là đồ thị của hàm số $y = f(x)$ thì đường thẳng nào song song với trục $Oy$ phải có nhiều hơn một điểm chung với tập $\Gamma_f$.

Sau những nhận xét sơ bộ này, chúng ta hãy chuyển sang các câu hỏi được đặt ra ở phần đầu.

Cách đồ họa để xác định chức năng
Chúng ta lấy điểm $(x; y)$ trên mặt phẳng tọa độ. Chúng ta sẽ giả sử điểm $(x; y)$ tương ứng với số $x$ - hoành độ của điểm - với số $y$ - tọa độ của điểm.

Bây giờ trên mặt phẳng tọa độ, chúng ta lấy một số tập hợp chính xác $M$, tức là tập hợp các cặp $(x; y)$ gồm các số thực $x$ và $y$. Tập hợp tất cả các hoành độ $x$ điểm $(x; y) \in M$

⟦folio 49⟧

Cơm. 1.

Chúng ta hãy biểu thị bằng $X = \{x\}$, tập hợp tất cả tọa độ $y$ của các điểm này bằng $Y = \{y\}$. Chúng ta sẽ giả sử rằng tập $M$ gán cho số $x \in X$ tất cả các số $y \in Y$ đó là tọa độ của các điểm $(x; y) \in M$ (tức là các điểm có cùng trục hoành bằng $x$). Sau đó, chúng ta nói rằng tập hợp $M$ xác định sự tương ứng $f$ giữa các tập hợp $X$ và $Y$. Bản thân tập hợp $M$ được gọi là đồ thị tương ứng $f$.

Ví dụ: trong Hình 1, tập hợp $M$ là một đường tròn có bán kính 5 với tâm là gốc tọa độ. Vòng tròn này chỉ định sự tương ứng giữa đoạn [—5; 5] trên trục $Ox$ và đoạn [—5; 5] trên trục $Oy$. Điểm 3 trên trục $Ox$ tương ứng với điểm 4 và -4 trên trục $Oy$, điểm 5 trên trục $Ox$ tương ứng với điểm 0 trên trục $Oy$, v.v.

Khi nào sự tương ứng $f$, một tập hợp $M$ cho trước trên mặt phẳng tọa độ, sẽ là một hàm? Để trả lời câu hỏi này, chúng ta hãy xem định nghĩa của hàm. Ngay sau đó, sự tương ứng $f$, được xác định bởi tập hợp $M$, sẽ là một hàm nếu mỗi trục hoành $x \in X$ tương ứng với một thứ tự duy nhất $y \in Y$. Chúng ta thu được định lý ngược lại với Định lý 1.

Định lý 2. Nếu tập hợp các tập hợp $M$ trên mặt phẳng tọa độ có châm ngôn là mọi đường thẳng song song với trục $Oy$ cắt nó nhiều nhất tại một điểm thì tập hợp $M$ là đồ thị của hàm số $y = f(x)$ nào đó.

Kết hợp Định lý 1 và 2, chúng ta thu được định lý sau.

Định lý 3. Để tập hợp $M$ trên mặt phẳng tọa độ là đồ thị của một hàm số nào đó (để xác định hàm số) thì mỗi đường thẳng song song với trục $Oy$ cắt nó không quá một lần (có nhiều nhất một điểm chung với $M$).

Bây giờ chúng ta thấy rằng tập $M$ trong Hình 1 không xác định hàm số - một đường thẳng song song với trục $Oy$ và đi qua điểm (3.0) cắt tập $M$ tại hai điểm; điều tương tự cũng đúng với tất cả các điểm khác trong khoảng - 5; 5].

Nhưng sự tương ứng $f$ giữa tập hợp $X = [1; 5]$ trên trục $Ox$ và $Y = [1; 3]$ trên trục $Oy$, được xác định bởi tập hợp $M$ trong Hình 2, là một hàm—mỗi đường thẳng song song với trục $Oy$ cắt tập hợp $M$ tại không quá một điểm.

⟦folio 50⟧

Cơm. 4.

Lưu ý rằng đối với tập hợp $X \subset (Ox)$, $Y \subset (Oy)$ đã cho, người ta có thể xây dựng vô số hàm với miền $X$ nhận các giá trị trong $Y$. Do đó, trong Hình 3, mỗi đường trong số ba đường cong là đồ thị của một hàm nào đó có miền định nghĩa $|a; b| \subset (Ox)$, lấy các giá trị trong $|c; d| \subset (Oy)$, tức là mỗi đường cong xác định một hàm đồ thị.

Dưới đây là những gì người nộp đơn nên biết về vấn đề gán chức năng bằng đồ họa.

Nghiên cứu chức năng

Giả sử hàm $y = f(x)$ được cho bởi đồ thị của nó. Nó cần được khám phá.

Điều này có nghĩa như sau.

1. Tên định nghĩa hàm
2. Tên các giá trị hàm; tìm hiểu xem chức năng có bị hạn chế không.
3. Tìm xem hàm số có giá trị lớn nhất và nhỏ nhất hay không.
4. Xác định hàm số chẵn (lẻ) hay tuần hoàn.
5. Tên của các khoảng mà hàm số dương là âm; tìm ra nơi hàm số tiến về 0.
6. Tên các khoảng trả về, giảm, hằng số của hàm.

Cơm. 5.

⟦folio 51⟧

Đối với nghiên cứu như vậy, các hàm đòi hỏi các định nghĩa phổ biến: hàm chẵn (lẻ), hàm trả về (giảm) trong khoảng, hàm bị chặn, v.v. Tất cả các định nghĩa này thường được sử dụng để nghiên cứu một hàm được cho bởi một công thức (phân tích), nhưng chúng phù hợp để nghiên cứu bất kỳ hàm số nào, bất kể nó được chỉ định như thế nào. Vì vậy, tất cả các định nghĩa sẽ “làm việc” cho các chức năng được xác định bằng đồ họa. (Bạn chỉ cần lưu ý rằng mỗi hình ảnh của đồ thị hàm số - chẳng hạn như bằng bút chì trên giấy - là gần đúng và chỉ đưa ra ý tưởng chung về hàm, không cho phép bạn xác định chính xác giá trị của hàm tại một điểm nhất định.) Hãy xem một ví dụ.

Trong Hình 4, hàm $y = f(x)$ được đưa ra. Hãy cùng khám phá nó theo sơ đồ đã cho.

1. Miền của hàm $f: X = [-1; 4]$.
2. Tập các giá trị của hàm $f: Y = [-1; 2]$. Hàm $f$ bị giới hạn vì với tất cả $x \in X$ sẽ có $|f(x)| \leq 2$.
3. Hàm $f$ lấy giá trị lớn nhất tại điểm $x = 4$, $f(4) = 2$, nhỏ nhất tại điểm $x = -1$, $f(-1) = -1$.
4. Hàm $f$ không chẵn cũng không lẻ, vì miền định nghĩa $X$ của nó không đối xứng về gốc tọa độ (tuy nhiên, kết luận này không thay đổi nếu giới hạn của hàm $y = f(x)$ theo $a$ đơn vị hướng lên trên (dọc theo trục $Oy$) được chuyển sang đồ thị của hàm $y = f(x)$ $a$ đơn vị sang trái (dọc theo trục) $Ox$) nén đồ thị hàm số $y = f(x)$ sang trục $Ox$ liên quan đến $1/k$

$y = f(x) (k > 0)$
hình chiếu của đồ thị hàm số $y = f(x)$ so với trục $Ox$

$y = f(kx) (k > 0)$
nén đồ thị của hàm $y = f(x)$ vào trục $Oy$ liên quan đến $1:(1/k)$

$y = f(-x)$
hình chiếu của đồ thị hàm số $y = f(x)$ so với trục $Oy$

$y = |f(x)|$
phản xạ so với trục $Ox$ của phần đồ thị của hàm $y = f(x)$ nằm bên dưới trục $Ox$

⟦folio 52⟧

giảm miền định nghĩa của các hàm $f$ thành khoảng $[-1; 1]$, vì $f(-1)=-1$, $f(1)=0$ và $f(1)\neq f(-1)$, $f(1)\neq -f(-1)$. Hàm $f$ không tuần hoàn vì miền định nghĩa của nó bị giới hạn.

5. Hàm $f$ dương trong các khoảng $[-1; -\frac{1}{2}]$ và $[1; 3]$; $3[$. Tại các điểm $x=-\frac{1}{2}$, $x=1$ và $x=3$ hàm biến mất.

6. Hàm $f$ tăng trong khoảng $[-1; 0]$ và $[2; 4]$ và giảm trong khoảng $[0; 2]$.

Đây là cách các hàm được nghiên cứu theo biểu đồ của chúng.

Vẽ đồ thị hàm số bằng cách biến đổi một đồ thị đã cho

Bằng cách biến đổi đồ thị hàm số $y=\sin x$, lớp 10 các bạn đã nhận được đồ thị hàm số $y=A\sin(kx+\theta)$, trong đó $A$, $k$, $\theta$ là các số thực. Tương tự như vậy, bằng cách biến đổi đồ thị hàm số $y=f(x)$, bạn có thể xây dựng đồ thị của một số hàm số khác. Giả sử hàm $y=f(x)$ được cho bởi đồ thị của nó. Sử dụng biểu đồ này, người nộp đơn phải có khả năng xây dựng biểu đồ của các hàm sau: $y=f(x)+a$, $y=f(x+a)$, $y=kf(x)$, $y=f(kx)$, $y=|f(x)|$ ($a$, $k$ là số thực), cũng như biểu đồ của các hàm thu được với sự kết hợp khác nhau của các phép biến đổi này (chẳng hạn như $y=kf(x+a)$ và v.v.). Các phép biến đổi hình học của đồ thị hàm $y=f(x)$, tạo ra đồ thị của các hàm trên, được thu thập trong bảng (xem trang 51 và Hình 5).

Bạn đọc có thể tìm thấy phần mô tả phương pháp xây dựng đồ thị hàm số trong sách giáo khoa toán học, ví dụ: G. V. Dorofeev, M. K. Potapov, N. Kh. Rozov. Sách hướng dẫn toán học. M., “Khoa học”, 1976.

Bài tập

1. Khám phá hàm $y=f(x)$, được cho bằng đồ họa (Hình 6).
2. Đồ thị của hàm $y=f(x)$ được cho (Hình 7). Xây dựng đồ thị của hàm số: a) $y=f(x)-2$; b) $y=f(x)+2$; c) $y=-f(x)$; d) $y=2f(x)$; k) $y=f(2x)$; f) $y=|f(x)|$; g) $y=f(-x)$.
3. Các đồ thị $y=f(x)$ đã cho. Xây dựng đồ thị của các hàm số nêu trong Bài tập 2 nếu: a) $f(x)=x^2$; b) $f(x)=10^x$; c) $f(x)=\lg x$; d) $f(x)=\sin x$.
