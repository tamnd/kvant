---
id: 1972-10-matematicheskiy-boy-ca2ccdac
issue: kvant_1972_10
year: 1972
number: "10"
title: Cuộc chiến toán học
rubric: smes
page_first: 18
page_last: 22
page_labels: 18, 20
tag: JOKV
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 4e448cc8e93cf9719ef44849781c915e4731450408c883050103b892f7982939
prompt_sha256: draft-1
translated_from: content/ru/1972/10/articles/03_matematicheskiy-boy-ca2ccdac.md
source_content_sha256: 8d57276f5a5b9e6ccac97a3348d5db161546df26e5bb4db91855b0df2c51d0cc
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

TRẬN CHIẾN TOÁN HỌC

Dưới đây là bài toán, được đề xuất tại một cuộc thi toán học được tổ chức trong một cuộc tập hợp sinh viên từ một trường vật lý và toán học ở Leningrad vào ngày 7 tháng 1 năm 1972 (các quy tắc của nó được mô tả trong bài viết ở trang 71.)

1. Tìm các số nguyên $x$ và $y$ sao cho $(((x^x - y)^y)x - y)^x + x + y = 1972 + 1000x$.

2. Chứng minh rằng từ 1972 số nguyên bất kỳ có thể chọn đúng 972 có tổng chia hết cho 972.

3. Có thể tô màu các điểm trong không gian ba chiều bằng ba màu sao cho không có một đoạn nào được sơn hoàn toàn bằng một màu không?

4. Chứng minh rằng tích của tất cả các số từ $n+1$ đến $2n$ chia hết cho $2n$ và không chia hết cho $2^{n+1}$.

5. Xây dựng một đường tròn chia ba đường tròn đã cho thành hai phần bằng nhau.

6. Trong số các lượng giác của một diện tích cho trước, hãy tìm tam giác có tổng trung bình tương đối lớn nhất của các đường phân giác tương ứng.

7. Vé có một số có sáu chữ số. Một vé được gọi là vé Polingrad thường xuyên nếu tổng của ba chữ số đầu tiên bằng tổng của ba chữ số cuối. Một vé được gọi là chasty ở Vyshbor nếu số của nó chia hết cho 11. Vé nào lớn hơn: chasty ở Leningrad hay ở Vyshbor?

8. Có thể xếp mặt phẳng của một hình tứ giác bằng hình đã cho không?

9. Có thể thu được một hình ngũ giác đều bằng cách sử dụng mặt phẳng của hình lập phương không?

⟦folio 18⟧

Vô thời hạn, từ định nghĩa của tích phân, suy ra rằng hàm tích $S$ là tích phân của hàm số $f$. Cụ thể, diện tích toàn bộ đồ thị con của hàm $f$ bằng $\int_{A}^{B} f(x) \, dx$. Công thức dẫn xuất cho đồ thị con cho thấy ý nghĩa hình học của tích phân: tích phân của hàm không âm là diện tích đồ thị con của hàm này. Đây là cơ sở để sử dụng tích phân để tính diện tích.

Ví dụ: chúng ta hãy tìm diện tích của hàm số bị cắt khỏi các parabol $y = x^2 + 1$ của đường thẳng $y = 2x + 1$.

Parabol và đường thẳng cắt nhau tại các điểm có tọa độ (0, 1) và (2, 5) được tìm thấy dưới dạng lời giải hệ phương trình $y = x^2 + 1$, $y = 2x + 1$.

Diện tích yêu cầu (Hình 6) bằng hiệu giữa diện tích của các đồ thị con của hàm $x \rightarrow 2x + 1$ và $x \rightarrow x^2 + 1$, được xác định trên khoảng [0, 2]:

$$S = \int_{0}^{2} (2x + 1) \, dx - \int_{0}^{2} (x^2 + 1) \, dx =$$

$$= \int_{0}^{2} (2x - x^2) \, dx = 2 \int_{0}^{2} xdx - \int_{0}^{2} x^2 \, dx = \frac{4}{3}.$$

Nói chung, nếu đồ thị của hàm $f$ và $g$ cắt nhau tại các điểm có hoành độ $A$ và $B$ và với tất cả các số $x$ của đoạn $[A, B]$ thì bất đẳng thức $f(x) \geq g(x)$ được thỏa mãn, thì diện tích của hàm nằm giữa các đồ thị con này (Hình 7) bằng $\int_{A}^{B} (f(x) - g(x)) \, dx$.

Bài tập 1. a) Tính diện tích đồ thị con của hàm $x \rightarrow x^2$ trên đoạn [0,1].

b) Tính diện tích giới hạn bởi vòm xoang và trục hoành (Hình 8).

2. Khối lượng cơ thể quay

Giả sử rằng đồ thị con của hàm không âm $f$, xác định trên đoạn $[A, B]$, quay quanh trục x. Chúng ta hãy liên kết từng đoạn $[a, b]$ chứa trong đoạn $[A, B]$ với số $V [a, b]$—thể tích của phần vật thể quay được bao bọc giữa các mặt phẳng $x = a$ và $x = b$ (Hình 9).

⟦folio none⟧

Chúng ta thu được hàm khoảng cộng $V$.

Từ Hình 9, rõ ràng phần được chọn của vật quay chứa một hình trụ tròn thẳng, chiều cao của nó là đoạn $[a, b]$, bán kính đáy là $\min f$ và được chứa trong một hình trụ có cùng chiều cao và bán kính đáy $\max f$. Vì thể tích của các hình trụ này lần lượt bằng $\pi (b-a)(\min f)^2$ và $\pi (b-a)(\max f)^2$ nên

$$\pi (b-a)(\min f)^2 \leq V [a, b] \leq \pi (b-a)(\max f)^2.$$

Nhưng $\pi (\min f)^2$ là giá trị nhỏ nhất của hàm $\pi f^2$ trên đoạn $[a, b]$ và $\pi (\max f)^2$ là giá trị lớn nhất của hàm trên đoạn này. Do đó, $V$ là tích phân của hàm này nên thể tích của toàn bộ vật quay bằng

$$\int \limits_A \pi f^2(x) \, dx.$$

Ví dụ: hãy tính thể tích của hình nón tròn bên phải và thể tích của hình cầu.

Một hình nón tròn nguyên thủy có chiều cao $H$ có thể được coi là kết quả của phép quay đồ thị con của hàm tuyến tính $x \rightarrow kx$ được xác định trên đoạn $[0, H]$ (Hình 10). Nếu bán kính đáy của hình nón là $R$ thì

$$kH = R,$$

Ở đâu

$$k = \frac{R}{H}.$$

Hình 9.

Hình 10.

⟦folio 20⟧

§ 2. ỨNG DỤNG VẬT LÝ
TÍCH HỢP

Để kết luận, chúng tôi đưa ra một số ví dụ về ứng dụng tích phân trong các bài toán vật lý.

Bài 1. Hãy tìm tương tác tĩnh giữa một chất điểm có khối lượng m nằm trên cùng một đường thẳng với một thanh đồng chất có chiều dài l và khối lượng M. Khoảng cách từ điểm đó đến đầu gần nhất của thanh là c.

Tất nhiên, bạn biết định luật vạn vật hấp dẫn, trong đó phát biểu rằng lực tương tác hấp dẫn giữa hai khối lượng chính xác tỷ lệ thuận với tích của các khối lượng này và tỷ lệ nghịch với bình phương khoảng cách giữa chúng. Tuy nhiên, trong trường hợp của chúng tôi, một trong những tương tác khối lượng là không chính xác.

Nếu thanh được chia thành nhiều phần thì tổng lực tương tác của các phần này với khối lượng m bằng lực tương tác của toàn bộ thanh với khối lượng này. Nói chung, các nhà vật lý viết thêm: "chia thanh thành những đoạn rất nhỏ có chiều dài Δx. Một lực $\frac{mM\Delta x}{lx^2}$ tác dụng lên một đoạn nằm cách điểm m một khoảng x thì tổng các lực này bằng..."

Hãy để chúng tôi chỉ ra cách người ta có thể xây dựng cách giải tích chặt chẽ như vậy và sử dụng định nghĩa của chúng tôi về tích phân.

Chúng ta hãy biến đường thẳng mà thanh và điểm nằm trên đó thành một tham chiếu số bằng cách chọn điểm bắt đầu là điểm mà tại đó khối lượng m được đặt và hướng trục sao cho thanh nằm trên dải dương. Khi đó thanh sẽ đi vào đoạn $[c, c + l]$ của trục này. Đối với mỗi đoạn $[a, b]$ chứa trong đoạn $[c, c + l]$, chúng ta gán một số F $[a, b]$—độ lớn của lực tương tác giữa đoạn này của thanh và khối lượng m. Rõ ràng F là hàm cộng của khoảng. Rõ ràng lực này sẽ tăng nếu tổng khối lượng của đoạn $[a, b]$, bằng $\frac{M}{l}(b - a)$, tập trung ở đầu a của đoạn này gần với khối lượng m, và sẽ giảm nếu khối lượng này tập trung tại điểm b. Nhưng trong mọi trường hợp, chúng ta sẽ đi đến sự tương tác của hai khối lượng chính xác. Trong trường hợp đầu tiên, lực tương tác bằng $\frac{\gamma mM}{la^2}(b - a)$, trong trường hợp thứ hai $-\frac{\gamma mM}{lb^2}(b - a)$. Vì vậy, $\frac{\gamma mM}{lb^2}(b - a) \leq F[a, b] \leq \frac{\gamma mM}{la^2}(b - a)$.

Nhưng $\frac{\gamma mM}{lb^2} = \min_{[a, b]} \frac{\gamma mM}{lx^2}, a \frac{\gamma mM}{la^2} = \max_{[a, b]} \frac{\gamma mM}{lx^2}$.

Do đó, hàm cộng của khoảng $F$ là tích phân của hàm $x \rightarrow \frac{\gamma mM}{lx^2}$. Toàn bộ lực hấp dẫn giữa thanh và điểm bằng

$$\int_{c}^{c+l} \frac{\gamma mM}{lx^2} dx = \frac{\gamma mM}{l} \int_{c}^{c+l} x^{-2} dx = \frac{\gamma mM}{l} (-1) \left[ (c+l)^{-1} - c^{-1} \right] = \frac{\gamma mM}{l} \left( \frac{1}{c} - \frac{1}{c+l} \right) = \frac{\gamma mM}{c(c+l)}$$

Bạn biết rằng lực hấp dẫn cũng được tính theo định luật vạn vật hấp dẫn. Bằng chứng có giá trị đối với khối lượng cầu có cùng công thức với khối lượng chính xác, tiếp theo đối với Newton là một trong những điểm hướng tới việc tạo ra số nguyên.

Bài 2. Tìm động năng của một đĩa đồng chất có bán kính R và khối lượng M đang chuyển động với vận tốc góc w không đổi với các vận tốc, đi qua tâm đĩa và vuông góc với mặt phẳng của nó.

Động năng của một điểm chuyển động phụ thuộc vào khối lượng và tốc độ. Mặc dù đĩa được xử lý liên tục
