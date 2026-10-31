---
id: 1988-3-faddeev-nikulin-sokolovskiy-osnovnoy-printsip-differentsialnogo-ischisleniya-f6b8cb97
issue: kvant_1988_3
year: 1988
number: "3"
title: Nguyên lý cơ bản của phép tính vi phân
authors:
  - Фаддеев Д. К.
  - Никулин М. С.
  - Соколовский И. Ф.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 48
page_last: 51
page_labels: 46-49
tag: FA5R
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 4d905aa24ec86a5e0c34f682b389643ceeac37567c16d04dea3aa29f23ee539f
prompt_sha256: draft-1
translated_from: content/ru/1988/03/articles/19_faddeev-nikulin-sokolovskiy-osnovnoy-printsip-differentsialnogo-ischisleniya-f6b8cb97.md
source_content_sha256: 55d2bed68dc901a160f429e73c80427eb796d7ba44af3409993402af006aa4c8
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 46⟧

Nguyên lý cơ bản của phép tính vi phân

Phần I:
hàm tuyến tính

Thành viên tương ứng của Viện Hàn lâm Khoa học Liên Xô
D. K. FADDEYEV,
Ứng viên Khoa học Vật lý và Toán học
M. S. NIKULIN,
I. F. SOKOLOVSKY

Trong bài viết này, tác giả muốn xác nhận quan điểm rằng toán học ở phần cơ bản của nó là môn khoa học đơn giản nhất, vì nó nghiên cứu những khía cạnh thô sơ nhất của thực tế. Điều này hoàn toàn áp dụng cho các yếu tố của phân tích toán học, những ý tưởng chính rất đơn giản và rõ ràng nếu chúng được thể hiện ở cấp độ trực quan mà chúng thực sự nảy sinh. Thật không may, rất

Nhiều kết quả phân tích toán học, ý nghĩa hình học và vật lý rõ ràng của chúng thường bị hy sinh ngay từ lần đầu làm quen với các vấn đề chứng minh và cái gọi là cấu trúc toán học.

Về cơ bản, ý tưởng cơ bản của "toán học cao hơn" là quá trình giao tiếp sau đây, mà chúng tôi gọi là nguyên tắc cơ bản của phép tính vi phân:

Trong một phần nhỏ của bất kỳ đường cong đủ “tốt” nào, nó có thể uốn cong một chút và phần được đề cập càng nhỏ thì càng ít. Do đó, một phần nhỏ của đường cong tuyến tính trùng với một đoạn của một số đường thẳng và độ gần nhau của chúng ngày càng trở nên hoàn hảo hơn khi phần đường cong co lại đến một điểm nhất định. Đường thẳng chặt hơn đường thẳng kia ép vào đường cong gần một điểm cho trước được gọi là tiếp tuyến của đường cong tại điểm đó. Một phần là đồ thị hàm số khá “tốt” trên

⟦folio 47⟧

trong một phần nhỏ gần như tuyến tính, và một thay đổi nhỏ trong hàm gần như bằng một thay đổi nhỏ trong tori của hàm tuyến tính. Nói cách khác, một hàm “tốt” gần như tuyến tính cục bộ, nghĩa là, trong một lân cận rút gọn vô hạn của bất kỳ giá trị nào của đối số. Hệ số góc của tiếp tuyến với đồ thị hàm số được gọi là giá trị của hàm số tùy ý tại điểm đang xét.

“Nguyên tắc cơ bản” không phải là một định lý và không có định nghĩa rõ ràng. Đường cong đủ “tốt” và hàm số “tốt” là những khái niệm chỉ có thể được định nghĩa chính xác hơn sau khi khái niệm tùy ý đã được dạy và hình thức hóa. Tuy nhiên, các hàm hữu tỷ, lũy thừa, hàm mũ và logarit, cũng như hàm lượng giác đều “tốt”. Hơn nữa, chức năng phát sinh từ việc nghiên cứu các quá trình tự nhiên và kỹ thuật thường là “tốt”. Hàm $|x|$ trong vùng lân cận số 0 có thể được gọi là “plop”.

Trong bài viết này, bỏ qua vấn đề biện minh, chúng ta sẽ thu được kết quả chính của môn giải tích toán ở trường, dựa trên “nguyên lý cơ bản” của phép tính vi phân. Nhưng trước khi chuyển sang lời giải bài toán này, là chủ đề của phần thứ hai của bài viết này, chúng ta sẽ xem xét kỹ hơn về hàm tuyến tính. Điều này phải được thực hiện theo hai nguyên tắc. Đầu tiên là hàm tuyến tính trong khóa học ở trường được nghiên cứu từ rất sớm và do đó, nó được đơn giản hóa phần nào và tách khỏi các ứng dụng quan trọng nhất của nó. Nguyên nhân thứ hai mang tính cơ bản, nó gắn liền với vai trò đặc biệt của khái niệm hàm tuyến tính trong các khái niệm cơ bản của giải tích toán học.

Định nghĩa hàm tuyến tính

Hàm tuyến tính là hàm có dạng $y=kx+b$, trong đó $k$ và $b$ là hằng số. Tại $k=0$ hàm nhận giá trị không đổi $y=b$. Đối với $b=0$, hàm $y=kx$ được gọi là tỷ lệ thuận và tham số $k$ được gọi là hệ số tỷ lệ.

Tính chất đặc trưng của hàm tuyến tính

Thuộc tính này như sau: mức tăng của hàm tuyến tính tỷ lệ thuận với mức tăng của đối số.

Thật vậy, $y=kx+b$ trống là hàm đã cho và đối số trống thay đổi từ $x_1$ thành $x_2$. Chúng ta hãy biểu thị mức tăng của hàm $\Delta y=y(x_2)-y(x_1)$ thông qua mức tăng của đối số $\Delta x=x_2-x_1$:

$$y(x_2)-y(x_1)=kx_2+b-(kx_1+b)=k(x_2-x_1).$$

Do đó, $\Delta y=k\cdot \Delta x$, tức là, thực sự, mức tăng $\Delta y$ của hàm $y=kx+b$ tỷ lệ thuận với mức tăng $\Delta x$ của đối số có hệ số tỷ lệ bằng $k$.

Câu lệnh ngược lại đúng, cụ thể là: nếu mức tăng của hàm $f(x)$ tỷ lệ thuận với mức tăng của đối số thì $f(x)$ là hàm tuyến tính.

Thật vậy, chúng ta hãy chọn (sửa) một số giá trị $x_0$. Sau đó với bất kỳ $x$ nào, do điều kiện, đẳng thức

$$f(x)-f(x_0)=k(x-x_0),$$

Ở đâu

$$f(x)=kx-kx_0+f(x_0),$$

tức là chức năng trông giống như:

$$f(x)=kx+b,$$ trong đó $b=f(x_0)-kx_0$ có nghĩa là $f(x)$ là hàm tuyến tính.

Vì vậy, chúng tôi đi đến kết luận rằng thuộc tính dịch chuyển được sở hữu bởi một hàm tuyến tính và chỉ tuyến tính, đó là lý do tại sao chúng tôi gọi nó là thuộc tính đặc trưng của hàm tuyến tính.

Tính đơn điệu của hàm tuyến tính

Tại $k>0$ hàm $y=kx+b$ có khả năng xảy ra, tại $k<0$ hàm số này giảm dần.

Hãy chứng minh điều này cho $k>0$; nếu $x_2>x_1$ trống thì $y(x_2)-y(x_1)=kx_2+b-(kx_1+b)=k(x_2-x_1)>0$, tức là $y(x_2)>y(x_1)$, đó là điều cần phải chứng minh.

Thành phần của hàm tuyến tính

Một hàm phức, là thành phần của các hàm tuyến tính, cũng

⟦folio 48⟧

Một hàm tuyến tính có hệ số tỷ lệ bằng tích các hệ số tỷ lệ của các hàm thành phần của nó.

Thật vậy, hãy
$$F(x) = f(g(x)) \text{ и } f(x) = k_1 x + b_1, \quad g(x) = k_2 x + b_2.$$
Sau đó
$$F(x) = k_1 (k_2 x + b_2) + b_1 = k_1 k_2 x + k_1 b_2 + b_1 = kx + b,$$
ở đâu $k = k_1 k_2, b = k_1 b_2 + b_1$.

Rõ ràng, phát biểu này đúng với một hàm phức bao gồm một số hàm tuyến tính bất kỳ.

Đồ thị của hàm tuyến tính

Định lý. Đồ thị của hàm tuyến tính $y = kx + b$ là một đường thẳng.

Người đọc có thể dễ dàng chứng minh định lý này bằng cách sử dụng tam giác vuông tương tự. Tuy nhiên, không khó để xây dựng một chứng minh mà không sử dụng lý thuyết chia nhỏ, dựa vào tính đơn điệu của hàm tuyến tính.

Đặt $y = kx + b$ và chúng ta sẽ xem xét các điểm trên biểu đồ có hoành độ $0, x_1, 2x_1, 3x_1, \dots$. Hãy chứng minh rằng những điểm này nằm trên cùng một đường thẳng. Ý tưởng của bằng chứng rõ ràng từ hình 1. Tất cả các tam giác màu hồng đều bằng nhau và tổng các góc tại bất kỳ điểm nào của chuỗi đang xem xét là $180^\circ$, vì tổng các góc nhọn của một tam giác vuông là $90^\circ$ và góc thứ ba tại mỗi điểm của đường thẳng. Do đó, các cạnh huyền của các tam giác tiếp nối nhau và tạo thành một đường thẳng. Vì lý do tương tự, các điểm của đồ thị có hoành độ $0, x_1/n, 2x_1/n, \dots, nx_1/n$ nằm trên một đường thẳng và trùng với điểm trước đó hoặc chứa một điểm có hoành độ $x_1 = nx_1/n$. Số tự nhiên $n$ có thể được lấy càng lớn càng tốt, sao cho đường thẳng tìm được $L$ chứa các điểm trên đồ thị có các hoành độ cách đều nhau nhất có thể.

Hãy chứng minh rằng tất cả các điểm của đồ thị đều nằm trên một đường thẳng $L$. Giả sử điểm $(x_0, y_0)$ của đồ thị nằm phía trên đường thẳng $L$. (Nếu điểm nằm bên dưới thì lý luận tương tự.) Sau đó, như trước, chúng ta sẽ đảm bảo rằng trên đường thẳng $L'$ nối điểm $(0, b)$ với điểm $(x_0, y_0)$, các điểm đồ thị có hoành độ $0, x_0/m, 2x_0/m$, ... nằm càng dày đặc càng tốt. Do đó, theo giả định này, các điểm trên đồ thị của hàm $y = kx + b$ sẽ “liên hợp” tốt nhất có thể phần từ đường $L$ đến đường $L'$, điều này là không thể do tính đơn điệu của hàm tuyến tính. Vì vậy, bất kỳ điểm nào trên biểu đồ đều nằm trên đường được xây dựng trước đó.

Ngược lại, bất kỳ điểm $(x_2, y_2)$ nào của đường thẳng này đều thuộc đồ thị $y = kx + b$. Thật vậy, điểm $(x_2, kx_2 + b)$ là một điểm trên đồ thị và theo những gì đã được chứng minh, thuộc một đường thẳng, và vì trên một đường thẳng không song song với trục tọa độ nên chỉ có một điểm có hoành độ $x_2$, sau đó là $y_2 = kx_2 + b$.

Từ định lý chứng minh ở trên suy ra đồ thị tỉ lệ thuận ($b=0$) là đường thẳng đi qua gốc tọa độ.

Khi lời giải bài toán người ta thường phải dùng đến nghịch đảo định lý về đồ thị của một hàm tuyến tính: bất kỳ đường thẳng nào không song song với trục tọa độ đều là đồ thị của một hàm tuyến tính nào đó.

Hãy chứng minh điều đó.

Để đường thẳng này đi qua các điểm $(x_0, y_0)$ và $(x_1, y_1)$, trong đó $x_0 \neq x_1$ (hình 2). Bạn luôn có thể chọn một phương trình có dạng $y = kx + b$, trong đó các cặp số $(x_0, y_0)$ và $(x_1, y_1)$ sẽ được giải:

$$\begin{cases} y_0 = kx_0 + b, \\ y_1 = kx_1 + b. \end{cases}$$

Để làm điều này, chỉ cần đặt
$$k = \frac{y_0 - y_1}{x_0 - x_1}, \quad b = y_0 - \frac{y_0 - y_1}{x_0 - x_1} x_0.$$
Đường thẳng - đồ thị của hàm tuyến tính
$$y = \frac{y_0 - y_1}{x_0 - x_1} x + y_0 - \frac{y_0 - y_1}{x_0 - x_1} x_0 -$$
đi qua các điểm $(x_0, y_0)$ và $(x_1, y_1)$; đây là đường thẳng duy nhất đi qua hai điểm này, nghĩa là nó trùng với đường thẳng này, điều này chứng tỏ nhận định của chúng ta.

Ứng dụng tính chất đặc trưng của hàm tuyến tính

Ví dụ 1. Viết phương trình đường thẳng $a)$ có độ dốc $k = 3$ đi qua điểm $(-7, 2)$, $b)$ đi qua điểm $(-8, -10)$ và $(2, 4)$.

⟦folio 49⟧

Lời giải. a) Đặt $M(x, y)$ là một điểm tùy ý của đường thẳng mong muốn; thì $\Delta y = y - 2$ và mức tăng tương ứng của đối số là $\Delta x = x + 7$. Phương trình của đường thẳng là: $y - 2 = 3(x + 7)$.

6) Hãy tính độ dốc $k = \frac{\Delta y}{\Delta x} = \frac{4 + 10}{2 + 8} = 1,4$.

Chúng tôi đã đạt đến bài toán trước đó, nhưng chúng tôi có một điểm “thêm”. Chúng tôi chọn bất kỳ một trong hai và soạn phương trình của đường thẳng, ví dụ: $y - 4 = 1,4(x - 2)$; bạn cũng có thể viết $y + 10 = 1,4(x + 8)$.

Ví dụ 2. Ta nghiên cứu sự phụ thuộc được mô tả bởi hàm tuyến tính $y = kx + b$; các giá trị của đại lượng $x$ thu được do sự thay đổi. Phải thực hiện những thay đổi về số lượng $x$ với độ chính xác như thế nào để tính các giá trị của số lượng $y$ với độ chính xác $\varepsilon$?

Lời giải. Sai số khi đo giá trị $x$ có thể được coi là sự gia tăng trong đối số $x$, tức là được lấy là $\Delta x$. Khi đó, do tính chất đặc trưng của hàm tuyến tính nên sai số khi xác định giá trị $y$ sẽ bằng $\Delta y = k \cdot \Delta x$. Yêu cầu $|\Delta y| \leq \varepsilon$, do đó $|\Delta x| \leq \varepsilon/|k|$.

Đây là một kết quả cơ bản, nhưng nó được sử dụng trong các tình huống rất tổng quát và không hề cơ bản.

Ý nghĩa hình học và vật lý của các tham số $k$ và $b$ trong phương trình đường thẳng $y = kx + b$

Ý nghĩa hình học của tham số $k$ là $k$ bằng tiếp tuyến của góc nghiêng của đường thẳng với trục hoành (có tính đến hướng của góc). Mô-đun $k$ đề cập đến độ tròn (gần với đường thẳng đứng) mà một đường đi qua, do đó $k$ được gọi là hệ số phương trình của đường thẳng. Zakkkat $k$ hiển thị hướng đi của đường (hàm tuyến tính tăng hoặc giảm).

Chúng ta hãy tìm hiểu chi tiết hơn về ý nghĩa vật lý của các tham số $k$ và $b$. Hãy lấy đồ thị của hai hàm tuyến tính (hình 3 a, b) và gán tên khác nhau cho các biến (dọc theo trục tọa độ) sao cho mỗi lần đường thẳng này mô tả một quá trình có thể xảy ra nhất định.

1) Hãy để đồ thị mô tả quá trình thay đổi nhiệt độ của một cơ thể vật lý nhất định. Trục hoành biểu thị nhiệt độ $(y = T)$ tính bằng độ C và trục hoành biểu thị thời gian $(x = t)$ tính bằng giây. Sau đó

$$k = \frac{\Delta T}{\Delta t} \frac{\text{град}}{c}$$

- tốc độ thay đổi nhiệt độ. Trong trường hợp a) $|k|$ là tốc độ gia nhiệt, trong trường hợp b) $|k|$ là tốc độ làm mát, $b = T(0)$ là nhiệt độ ban đầu.

2) Gọi $y = m$ là khối lượng nhiên liệu tính bằng gam, $x = t$ là thời gian tính bằng giây. Sau đó

$$k = \frac{\Delta m}{\Delta t} \frac{\text{г}}{c}$$

— tốc độ thay đổi của công — công suất, $b = A(0)$ — công được thực hiện ở đầu báo cáo.
