---
id: 1975-3-resheniya-zadach-m273-m279-f285-f290-e3d146e5
issue: kvant_1975_3
year: 1975
number: "3"
title: Lời giải bài toán M273—M279; F285—F290
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 50
page_last: 60
page_labels: 48-58
tag: 74GG
lang: vi
source: kvant_digital
extraction: vision
content_sha256: d5739cc11132c9d626a40780da3a94fcf6985ec41b68bbedae9543a3b10a6775
prompt_sha256: draft-1
translated_from: content/ru/1975/03/articles/13_resheniya-zadach-m273-m279-f285-f290-e3d146e5.md
source_content_sha256: 9f857def718b22d059e026d49054091b997dfe800d0307e5c575a7c41e3c2d7b
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 48⟧

M273. Trên đoạn $0 \leq x \leq 1$ hàm $f$ được đưa ra. Được biết, hàm này không âm và $f(1) = 1$. Hơn nữa, với hai số bất kỳ $x_1$ và $x_2$ thì giá trị lớn nhất mà $x_1 \geq 0$, $x_2 \geq 0$ và $x_1 + x_2 \leq 1$ thỏa mãn bất đẳng thức
$$f(x_1 + x_2) \geq f(x_1) + f(x_2).$$
a) Chứng minh rằng bất kỳ hàm số $f$ nào cũng thỏa mãn điều kiện trên thì với mọi $x$ thì bất đẳng thức $f(x) \leq 2x$ sẽ được thỏa mãn.
6) Điều đó có đúng với tất cả $x$ $f(x) \leq 1,9x$ không?

M274. Tìm số nhỏ nhất có dạng
a) $|11^k - 5^l|$;
b) $|36^k - 5^l|$;
c) $|53^k - 37^l|$,
trong đó $k$ và $l$ là số tự nhiên.

a) Hàm thỏa mãn điều kiện bài toán trả về đa âm. Thật vậy, nếu $x_2 \geq x_1$ và $x_2 \leq 1$, thì $f(x_2) \geq f(x_1) + f(x_2 - x_1)$ và $f(x_2 - x_1) \geq 0$; do đó $f(x_2) \geq f(x_1)$. Do đó, nếu $\frac{1}{2} < x \leq 1$, vì $f(1) = 1$, chúng ta có
$$f(x) \leq 1 \leq 2x.$$
Hãy để bây giờ $0 < x \leq \frac{1}{2}$. Hãy lấy $n$ tự nhiên sao cho $\frac{1}{2} < nx \leq 1$ (rõ ràng là điều này luôn có thể được thực hiện). Dễ dàng chứng minh (bằng quy nạp) rằng nếu $x \geq 0$ và $nx \leq 1$ thì $f(nx) \geq nf(x)$. Đối với $\frac{1}{2} < nx \leq 1$ người ta đã chứng minh rằng $f(nx) \leq 2 \cdot nx$.
Posny $nf(x) \leq f(nx) \leq 2 \cdot nx$, mở $f(x) \leq 2x$ và cho $0 < x \leq \frac{1}{2}$.
Tất cả những gì còn lại là tìm hiểu điều gì sẽ xảy ra ở mức 0. Hãy lấy $0 < x_1 \leq 1$; Sau đó
$$f(x_1) = f(0 + x_1) \geq f(0) + f(x_1).$$
Nhưng theo định nghĩa, $f(0) \geq 0$ có nghĩa là $f(0) = 0$.
6) Đáp số: không, điều đó không đúng.
Hãy đưa ra một ví dụ. Hãy xác định hàm như sau:
$$f(x) = \begin{cases} 1, & \frac{1}{2} < x \leq 1, \\ 0, & 0 \leq x \leq \frac{1}{2}. \end{cases}$$
Nếu $1 \geq x_1 \geq x_2 \geq 0$ và $x_1 + x_2 \leq 1$ thì $x_2 \leq \frac{1}{2}$ và $f(x_2) = 0$.
Do đó, $f(x_1 + x_2) \geq f(x_1) + f(x_2)$ và ta coi hàm thỏa mãn yêu cầu bài toán.
Đồng thời
$$f\left(\frac{51}{100}\right) = 1 > 1,9 \cdot \frac{51}{100}.$$

◆
a) Nếu $11^k > 5^l$ thì số $|11^k - 5^l|$ là 6; nếu $11^k < 5^l$ thì bằng 4.
Dễ dàng nhận thấy $|11^k - 5^l| = 4$ đối với $l = 3$, $k = 2$, tức là 4 là số nhỏ nhất của dạng $|11^k - 5^l|$.
6) Nếu $36^k > 5^l$ thì số $|36^k - 5^l|$ là 1; nếu $36^k < 5^l$ thì bằng 9.
Với $k = 1$, $l = 2$ chúng ta có $|36^k - 5^l| = 11$.
Hãy chứng minh rằng 11 là số nhỏ nhất thuộc loại này. Để làm điều này, chúng ta cần chứng minh rằng $|36^k - 5^l|$ không thể bằng 1 hoặc 9.

⟦folio 49⟧

1) Nếu $36^k - 5^l = 1$ thì $(6^k - 1)(6^k + 1) = 5^l$.
Không có số $6^k + 1$ nào không thể là lũy thừa của 5, vì nó có tận cùng là 7 (tại $k > 0$).

2) Nếu $5^l - 36^k = 9$ thì $5^l = 9 + 36^k$, điều này cũng không thể xảy ra, vì vế phải của $k > 0$ chia hết cho 9, còn vế trái thì không. Điều này có nghĩa là 11 là số nhỏ nhất có dạng $|36^k - 5^l|$.

c) Số $N = |53^k - 37^l|$ có thể kết thúc bằng chữ số chẵn bất kỳ. Ngoài ra, vì $|53^k - 37^l| = |(52 + 1)^k - (36 + 1)^l| = |(4.13 + 1)^k - (4.9 + 1)^l|$ nên $N$ chia hết cho 4. Đối với $k = l = 1$ $N = 53 - 37 = 16$. Hãy chứng minh rằng 16 là số nhỏ nhất có dạng $|53^k - 37^l|$. Để làm điều này, chỉ cần chứng minh rằng $N$ không thể bằng 4, 8 và 12 ($N$, rất rõ ràng, không bằng 0, vì 53 và 37 là nguyên tố cùng nhau).

Chúng tôi có $N = |53^k - 37^l| = |(54 - 1)^k - (36 + 1)^l| = |(6.9 - 1)^k - (4.9 + 1)^l|$.

Pozny, khi chia $N$ cho 9 thì số dư chỉ có thể là 0,2 và - 2 (tức là 7). Nhưng cả 4, 8, 12 đều không có số dư này khi chia cho 9.

I. N. Klimova

M275. a) Trên mặt phẳng dữ liệu của vectơ $n$, độ dài của mỗi comorbix là ​​1. Tổng của tất cả các vectơ $n$ bằng vectơ 0. Chứng minh rằng các vectơ có thể đo được sao cho mọi $k = 1, 2, \dots, n$ đều thỏa mãn các điều kiện sau: tổng các vectơ $k$ đầu tiên có độ dài không quá 3.
b) Chứng minh khẳng định tương tự cho vectơ $n$ có tổng bằng 0, độ dài mỗi comorbix là 1. b) Có thể thay số 3 trong bài toán a) bằng ít hơn không? Xây dựng đánh giá buộc tội cũng ở bài toán 6).

Trước tiên chúng ta hãy xem xét “một chiều” bài toán.
Bổ đề 1. Cho trước $n$ số sao cho mỗi mô đun không vượt quá 1 và tổng của tất cả bằng 0. Sau đó, chúng có thể được đo sao cho với bất kỳ $i \leq n$ nào thì tổng của $i$ đầu tiên trong số chúng nhiều nhất là 1 tính theo mô đun.

Hãy để chúng tôi chỉ ra một trong các phương pháp điền: $a_1, \dots, a_k$ và không tích cực: $b_1, \dots, b_{n-k}$. Hãy đặt $c_1 = a_1, c_2 = b_1$. Nếu $c_1 + c_2 < 0$, đặt $c_3 = a_2$; nếu $c_1 + c_2 \geq 0$, đặt $c_3 = b_2$. Và nói chung, nếu $c_1, \dots, c_l$ đã được chọn thì đối với $c_1 + \dots + c_l < 0$ hãy sử dụng số dương tiếp theo cho $c_{l+1}$ và cho $c_1 + \dots + c_l \geq 0$ cho số dương tiếp theo.

Dựa vào Bổ đề 1, chúng ta giải được bài toán M275 6). Chúng ta hãy áp dụng tất cả các vectơ này cho một số điểm $O$ và chọn hệ tọa độ trực tiếp $Oxy$ sao cho tổng $s$ của tất cả các vectơ hướng lên trên ($v > 0$) được định hướng chính xác dọc theo trục $y$. (Chúng ta sẽ thảo luận về câu hỏi làm thế nào để xây dựng một hệ tọa độ như vậy sau.) Các vectơ còn lại (smogrizia xuống) khi đó cho tổng cộng là $s$.

Đầu tiên, hãy đo các vectơ nhìn lên. Chúng tôi biểu thị các thành phần của chúng dọc theo trục $x$ bằng $p_1, \dots, p_k$. Vì thành phần $s$ dọc theo trục $x$ bằng 0 nên $p_1 + \dots + p_k = 0$. Trong mô đun, mỗi số $p_1, \dots, p_k$ không vượt quá 1. Theo Bổ đề 1, chúng ta đo các số $p_1, \dots, p_k$ sao cho với bất kỳ $i \leq k$ nào thì tổng của $i$ đầu tiên trong số chúng tối đa là 1 về giá trị tuyệt đối. Do đó, chúng tôi đo các vectơ hướng lên trên, sao cho với bất kỳ $i \leq k$ nào, tổng của $i$ đầu tiên trong số chúng sẽ nằm trong dải $|x| \leq 1$ (Hình 1). Các thành phần của các vectơ này dọc theo trục $y$ (theo thứ tự đã chọn) sẽ được ký hiệu là $a_1, \dots, a_k$.

Chúng tôi cũng đo các vectơ tra cứu và gọi các thành phần của chúng dọc theo trục $y$ $b_1, \dots, b_{n-k}$.

Bây giờ chúng ta chuyển sang đánh số liên tục tất cả các vectơ này. Mỗi số $a_1, \dots, a_k$ nằm trong khoảng từ 0 đến 1, mỗi số $b_1, \dots, b_{n-k}$ nằm trong khoảng từ 0 đến - 1 và tổng của chúng là 0. Không thay đổi thứ tự tương đối của các số $a_1, \dots, a_k$ và thứ tự tương đối của các số $b_1, \dots, b_{n-k}$, chúng ta viết chúng theo Bổ đề 1 dưới dạng một tập hợp $c_1, \dots, c_n$ sao cho với bất kỳ $i \leq n$ nào chúng ta thu được bất bình đẳng $|c_1 + \dots + c_i| \leq 1$. Do đó, chúng tôi đo tất cả các vectơ này sao cho với bất kỳ $i \leq n$ nào, tổng của $i$ đầu tiên trong số chúng sẽ được định vị

⟦folio 50⟧

nằm trong dải $|y| \leq 1$. Ngoài ra (do cách đánh số sơ bộ của các số $a_1, \dots, a_k$ và $b_1, \dots, b_{n-k}$) bất kỳ tổng nào như vậy đều nằm trong dải $|x| \leq 2$.

Vì vậy, chúng tôi đã chứng minh rằng $n$ của các vectơ đã cho có thể được tạo thông qua $v_1, \dots, v_n$ sao cho với bất kỳ $i \leq n$ nào thì tổng $v_1 + \dots + v_i$ nằm trong hình chữ nhật $|x| \leq 2$, $|y| \leq 1$ và do đó $|v_1 + \dots + v_i| \leq \sqrt{5}$.

Chúng ta cũng hãy lưu ý 1. Vẫn cần chứng minh việc xây dựng hệ thống $Oxy$.

Chúng ta hãy chia tất cả các vectơ này thành hai lớp; tổng vectơ của lớp thứ nhất sẽ được ký hiệu là $s$ (khi đó tổng vectơ của lớp thứ hai sẽ là $s$). Chỉ có $2^n$ tất cả các phân vùng có thể thành hai lớp (điều quan trọng là có số lượng hữu hạn trong số chúng). Chúng ta hãy chọn trong số chúng giá trị mà $|s|$ nhận giá trị cao nhất và hướng của vectơ cụ thể $s$ này sẽ được lấy làm hướng của trục $y$.

(Đảm bảo rằng hệ thống được xây dựng $Oxy$ có thuộc tính mà chúng ta cần.)

Lưu ý rằng nó không phải là e2. Từ cách xây dựng trục $y$ ở trên, rõ ràng là không có vectơ nào trong số này vuông góc với nó, do đó, chúng ta đã nói một cách chính xác về vectơ “nhìn xuống” (thay vì cẩn thận hơn là “không nhìn lên”).

Trong không gian của một vectơ $n$ cho trước, sao cho mỗi modulo không vượt quá 1 và tổng của tất cả đều bằng 0. Chứng minh rằng chúng có thể được đánh số sao cho với bất kỳ $i \leq n$ nào thì tổng của $i$ đầu tiên trong số chúng có độ dài nhỏ hơn $C$, trong đó: a) $C = \sqrt{21}, 6)$* $C = \sqrt{20,5}$.

Hãy chuyển sang bài toán $M275$ a).

Bổ đề 2. Đặt mỗi vectơ $e_1, \dots, e_r$ có độ dài 1, độ dài $e_0$ nhiều nhất là 1 và $e_0 + e_1 + \dots + e_r = 0$. Sau đó, trong số các vectơ $e_1, \dots, e_r$ có một vectơ $e_i$ hoặc một cặp vectơ $e_j$ và $e_k$, tổng bằng $e_0$ cho ra một vectơ $e$ có độ dài không quá 1 ($|e_0 + e_i| \leq 1$ hoặc $|e_0 + e_j + e_k| \leq 1$). Trong trường hợp thứ hai $|e_0 + e_j| < \sqrt{2}$.

Bằng chứng. Chúng ta hãy vẽ hai tia, $OA$ và $OB$, tạo thành các góc với $e_0$ tại $120^\circ$ (Hình 2). Nếu trong $e_1, \dots, e_r$ có một vectơ nằm bên trong (hoặc ở hai bên) $AOB$ thì chúng ta sẽ coi đó là $e_i$.

Giả sử không có vectơ nào như vậy trong $e_1, \dots, e_r$. Sau đó chúng ta vẽ một đường thẳng $CD \perp e_0$ đi qua điểm $O$. Trong số các vectơ $e_1, \dots, e_r$ hóa ra có một vectơ nằm bên trong $AOC$ hoặc bên trong $BOD$ (nếu không thì điều kiện $e_0 + e_1 + \dots + e_r = 0$ không được thỏa mãn). Để định nghĩa, hãy để ít nhất một trong các vectơ $e_1, \dots, e_r$ nằm bên trong $BOD$. Vectơ gần nhất với $OB$ được gọi là $e_j$ và tia hướng đối diện với nó được ký hiệu là $OE$. Ít nhất một trong các vectơ $e_1, \dots, e_r$ nằm bên trong $AOE$ (nếu không thì điều kiện $e_0 + e_1 + \dots + e_r = 0$ lại không được thỏa mãn). Vector gần nhất với $OA$ trong số các vectơ này được gọi là $e_k$, các góc $e_j$ và $e_k$ biểu thị cả hai góc $e_j$ và $e_k$, lớn hơn 60°. Điều này có nghĩa là vectơ $e_j + e_k$ nằm bên trong $AOB$, và do đó $|e_0 + e_j + e_k| \leq 1$. Đồng thời $|e_0 + e_j| < \sqrt{2}$.

Từ Bổ đề 2, ngay lập tức suy ra rằng trong bài toán $M275$ a) các vectơ có thể được đánh số sao cho với mỗi $k \leq n$ thì tổng của các vectơ $k$ đầu tiên có độ dài $\sqrt{2}$ (chứng minh bằng quy nạp trên $n$).

Để làm phức tạp việc chứng minh, chúng ta có thể cải thiện hơn nữa ước tính trong bài toán $M275$ a), cụ thể là thay thế $\sqrt{2}$ bằng $\frac{\sqrt{5}}{2}$.

Trong sợi 2. Đạt bài toán $M275$ a) điểm $\frac{\sqrt{5}}{2}$. Chứng minh rằng không thể cải thiện được ước lượng này nữa, nghĩa là,

⟦folio 51⟧

Hình 3.

**M276.** Cho hình vuông ABCD. Điểm P và Q lần lượt nằm trên cạnh AB và BC với $|BP| = |BQ|$. Điểm H là đáy của đường vuông góc thả từ điểm B lên đoạn PC. Chứng minh rằng Huelol DHQ là trực tiếp.

Hình 4.

**M277.** Một số đèn đỏ và một số đèn đồng bộ được chỉ định. Một số trong số chúng được kết nối bởi các phân đoạn. Đất thùy là “đặc biệt” nếu phần được tưới nước nhiều nhất trong các thùy nối với nó có màu khác với màu của nó. Nếu có ít nhất một mocka đặc biệt thì bất kỳ mocka đặc biệt nào cũng sẽ được chọn và sơn lại bằng một màu khác. Chứng minh rằng sau hữu hạn các bóng sẽ không còn một thùy đặc biệt nào.

**M278. a) Mỗi ​​cạnh của ô lục giác lồi có độ dài lớn hơn 1. Có phải nó luôn nằm trong đó không? Chứng minh rằng đối với bất kỳ $C < \frac{\sqrt{5}}{2}$ dương nào, có thể biểu thị trên mặt phẳng $n$ vectơ đơn vị có tổng bằng 0, sao cho, như được ký hiệu là $v_1, \dots, v_n$, đối với một số $k$ thì bất đẳng thức $|v_1 + \dots + v_k| > C$ hóa ra là hợp lệ.

Sẽ rất thú vị nếu có được một ước tính không thể cải thiện được trong bài toán M275 6) (tác giả chưa biết). Tuy nhiên, vì mục đích mà bài toán M275 được đề xuất, không cần phải đánh giá chính xác. Mục tiêu được đề cập - chứng minh định lý phức tạp Riemann (xem «Kvant», 1973, số 9, “Từ sự đảo ngược các số hạng,” bài tập 22 và 23).

Trong sợi và 3. Dựa vào M275 6), hoàn thành bài tập 22 từ bài “Từ việc thay đổi vị trí của các thuật ngữ”.

**M. L. Gerver**

Xét một phép biến đổi mặt phẳng tương tự biến tam giác BHC thành tam giác PHB; đây là phép quay giống tâm một góc 90° với tâm ở điểm H và hệ số tương tự $k = \frac{|BH|}{|HC|} = \frac{|PH|}{|HB|}$ (Hình 4). Với phép biến đổi tương tự này, ba đỉnh B, C, D của hình vuông ABCD tất nhiên phải chia thành ba đỉnh của hình vuông: B - đến P, C - đến B, do đó, D - đến Q (nhập $|PB| \perp |BQ|$ và $|PB| = |BQ|$ theo điều kiện). Theo đó, Q thu được từ D bằng một phép biến đổi tương tự bao gồm một chế phẩm có hệ số $k$ và góc quay 90° quanh điểm H.

Do đó, $DHQ = 90^\circ$ (đồng thời chúng tôi đã chứng minh rằng $\frac{|QH|}{|HD|} = \frac{|BH|}{|HC|}$).

Độc giả và những người tham gia Olympic Thế giới năm ngoái, trong đó bài toán này được đề xuất, đã chỉ ra nhiều lời giải khác nhau không sử dụng “các phép biến đổi hình học”. Ví dụ: $\triangle BHQ \sim \triangle CHD$, vì $\frac{|HB|}{|HC|} = \frac{|PB|}{|BC|} = \frac{|BQ|}{|CD|}$ và $HBQ \cong HCD$ (các cạnh của các góc này đã được phân phối lại); do đó $BHQ \cong CHD$, do đó $QHD = BHC = 90^\circ$.

**H. B. Vasiliev**

Một đoạn được coi là “đặc biệt” nếu các đầu của nó có màu khác nhau. Lưu ý rằng một điểm được coi là “đặc biệt” nếu các đoạn ra khỏi đó được tưới nhiều hơn—“đặc biệt”. Vì vậy, khi tô màu lại bất kỳ điểm “đặc biệt” nào, tổng số đoạn “đặc biệt” sẽ giảm đi. Vì tất cả các phân đoạn “đặc biệt” ít nhất bằng 0 và tại mỗi bước, số lượng của chúng giảm đi ít nhất một, nên sau một số hữu hạn bước, chúng ta thu được một hệ thống trong đó không có điểm nào có thể được tô màu lại và do đó, không có điểm đặc biệt nào.

**VÀ. N. Klumova**

Đáp số. a) Không phải luôn luôn; 6) luôn luôn.

a) Lấy một hình tam giác đều có cạnh 2 (trong Hình 5 là hình chấm). Từ giữa phía của nó, chúng tôi khôi phục lại phía phân phối lại của nó, đặt nó lên chúng

⟦folio 52⟧

Độ dài đường chéo có lớn hơn 2 không?
6) Trong hình lục giác lồi ABCDEF, độ dài các đường chéo AD, BE và CF lớn hơn 2. Có phải nó luôn có cạnh dài hơn 1 không?

Hình 5.

M279. Các số được viết trên n thẻ xếp thành một vòng tròn, mỗi số bằng +1 hoặc -1. Trong số câu hỏi nhỏ nhất bạn có thể xác định chắc chắn tích của tất cả n số, nếu trong một câu hỏi bạn có thể tìm ra:
a) tích của các số trên ba tấm thẻ bất kỳ?
b) tích của các số trên ba tấm thẻ bất kỳ nằm trên một hàng? (n là số tự nhiên lớn hơn 3.)

Hình 6.

Chúng ta hãy biểu thị các số được ghi trên thẻ bằng $a_1, a_2, \dots, a_n$ và loại bỏ số câu hỏi bằng $p$.

a) Trước hết, chúng tôi lưu ý rằng mỗi số này phải có trong ít nhất một trong các tích, ý nghĩa của chúng mà chúng tôi sẽ tìm ra bằng cách đặt câu hỏi, hoặc nếu không, bằng cách thay đổi dấu của số được ghi trên một thẻ chưa sử dụng, chúng tôi sẽ thay đổi dấu của tích của tất cả các số, đồng thời giữ nguyên đáp số cho tất cả các câu hỏi được hỏi. (Điều này cho thấy rằng dựa trên đáp số thu được thì không thể xác định tích của tất cả các số.) Vì với một câu hỏi, chúng ta đã học được tích của ba số, nên $p \geq \frac{n}{3}$.

Nếu $n=3k$ thì k câu hỏi là đủ. Sau khi tìm ra tích k $a_1a_2a_3, a_4a_5a_6, a_7a_8a_9, \dots, a_{3k-2}a_{3k-1}a_{3k}$ và các biến kết quả bằng nhau, chúng ta sẽ tìm được tích của tất cả các số.

Nếu $n=3k+1$ thì $p \geq k+1$. Hãy để chúng tôi chứng minh rằng với $k>1$ trong các câu hỏi $(k+1)$, bạn có thể tìm ra tích của tất cả các số.

Hãy cùng tìm hiểu xem $(k+1)$ tích $a_1a_2a_3, a_1a_2a_4, a_1a_2a_5, a_6a_7a_8, a_9a_10a_11, \dots, a_{3k}a_{3k+1}a_{3k+2}$ bằng bao nhiêu và đặt các câu hỏi $k+2$ (các tích liên quan đến hệ số 3k một lần và các hệ số $a_1$ và $a_2$ mỗi hệ số ba lần, tức là hệ số $3k+6$). Chúng tôi sẽ chỉ ra rằng $k+1$ câu hỏi là chưa đủ.

Các sản phẩm $k+1$ bao gồm hệ số $3k+3=n+1$; nhưng vì mỗi số $n$ ghi trên thẻ phải thuộc ít nhất một trong các sản phẩm này, nên một số (hãy gọi nó là a) được bao gồm trong hai sản phẩm: $abc$ và $ade$, và mỗi số còn lại được bao gồm trong một sản phẩm. Nhưng bằng cách thay thế các số a, b và d, chúng ta sẽ không thay đổi bất kỳ kết quả đáp số nào, đồng thời thay đổi tích của tất cả chúng bằng các thẻ số; Điều này có nghĩa là trên cơ sở thu được $k+1$ đáp số sản phẩm này là không thể.

⟦folio 53⟧

Vì vậy, đáp số trong bài toán a) là:
nếu $n=3k$, thì $p=k$,
nếu $n=3k+1$, thì $p=k+1$ (ngoại trừ trường hợp $n=4$),
nếu $n=3k+2$ thì $p=k+2$.

b) Nếu $n=3k$, thì như trong bài toán a), $p=k$. Để $n$ không chia hết cho 3.

Lưu ý rằng trong điều kiện bài toán b) chỉ có thể hỏi các câu hỏi về giá trị của các tích $n$ đó:
$a_1a_2a_3,\ a_2a_3a_4,\ \dots,\ a_{n-2}a_{n-1}a_n,\ a_{n-1}a_na_1,\ a_na_1a_2.$ (*)

Sau khi hỏi tất cả $n$ câu hỏi, chúng tôi tìm ra khối lập phương của sản phẩm $a_1a_2\dots a_n$, và do đó, bản thân sản phẩm - xét cho cùng, nó bằng 1 hoặc $-1$. Hãy để chúng tôi chứng minh rằng $n-1$ câu hỏi là không đủ để tìm ra sản phẩm $a_1a_2\dots a_n$.

Bằng cách đặt câu hỏi $n-1$, chúng ta sẽ biết tất cả các tác phẩm (*), ngoại trừ một tác phẩm. Vì chúng ta có thể bắt đầu đánh số các thẻ bằng bất kỳ thẻ nào trong số chúng, nên chúng ta có thể giả định rằng câu hỏi về ý nghĩa của sản phẩm $a_1a_2a_3$ không được hỏi.

Hãy để $n=3k+1$. Bằng cách thay thế $a_2$ và $a_3$, $a_5$ và $a_6$, $a_8$ và $a_9$, ..., $a_{3k-1}$ và $a_{3k}$ bằng các số đối diện, cũng như số $a_1$, chúng ta thay đổi dấu của toàn bộ sản phẩm $a_1a_2\dots a_n$ (vì chúng đã được thay thế $2k+1$ số). Nhưng vì trong mỗi sản phẩm (*), ngoại trừ sản phẩm $a_1a_2a_3$, chúng tôi không hỏi gì, hai yếu tố thay đổi, nên chúng tôi sẽ không tìm hiểu gì về sự thay đổi dấu hiệu này của toàn bộ sản phẩm bằng cách đặt câu hỏi $n-1$.

Hãy để $n=3k+2$. Một lần nữa, bằng cách thay thế $a_4$ và $a_5$, $a_7$ và $a_8$, $a_{10}$ và $a_{11}$, ..., $a_{3k+1}$ và $a_{3k+2}$ và $a_2$ bằng các số đối diện, chúng ta thay đổi dấu của toàn bộ kết quả $a_1a_2\dots a_n$ (vì một lần nữa nó được thay thế bằng số lẻ của các số) và một lần nữa chúng ta không nhận ra sự thay đổi này, vì một lần nữa trong tất cả các tích (*), ngoại trừ tích $a_1a_2a_3$, có hai yếu tố thay đổi.

Vì vậy, câu trả lời cho bài toán b) là:
nếu $n$ không chia hết cho 3 thì $p=n$;
nếu $n$ chia hết cho 3 thì $p=\dfrac{n}{3}$.

Bây giờ chúng ta thấy điều đó ở bài toán a) tại $n=4$ $p=4$.

Yu. I. Ionin

⟦figure⟧
Hình 7.

⟦column⟧

F285. Một tủ lạnh có bộ điều nhiệt hoạt động trong phòng không có hệ thống sưởi. Khi tủ lạnh được kết nối mạng, nhiệt độ bên ngoài, trong nhà và trong tủ lạnh là như nhau. Giả sử nhiệt độ bên ngoài không đổi, hãy mô tả sơ bộ trên đồ thị nhiệt độ trong phòng thay đổi như thế nào sau khi kết nối tủ lạnh.
Hãy xem xét ba trường hợp:
1) tủ lạnh trống rỗng;
2) chứa đầy sản phẩm;
3) Cửa tủ lạnh đang mở.
Vẽ cả ba đồ thị nhiệt độ theo thời gian trong một hình.

◆

Máy làm lạnh hoạt động theo nguyên lý ngược lại của động cơ nhiệt: một lượng công nhất định được thực hiện lên chất lỏng làm việc—khí tác nhân—và nhiệt được truyền từ vật lạnh sang vật nóng. Trong trường hợp này, không chỉ nhiệt lấy từ vật lạnh được truyền sang vật nóng mà còn có nhiệt tương đương với công thực hiện. Trong tủ lạnh gia đình (xem Hình 7), chất khí hóa lỏng bay hơi sẽ lấy nhiệt từ thành buồng bay hơi. Khí này sau đó được hóa lỏng lại trong bình ngưng, truyền nhiệt ra không khí xung quanh.

Nếu cửa tủ lạnh mở, nhiệt sẽ được thiết bị bay hơi loại bỏ khỏi không khí xung quanh và được thiết bị ngưng tụ truyền đến cùng không khí trong phòng. Không khí cũng nhận nhiệt tương đương với công và nhiệt sinh ra trong dây dẫn và trong cuộn dây động cơ máy nén. Vì vậy, khi cửa tủ lạnh mở, nhiệt độ trong phòng sẽ liên tục tăng cho đến khi lượng nhiệt vào phòng bằng lượng nhiệt thoát ra khỏi phòng bên ngoài. Bộ điều chỉnh nhiệt sẽ không hoạt động trong trường hợp này. Biểu đồ thay đổi nhiệt độ trong phòng được thể hiện trên Hình 8 bằng một đường màu đen.

Bây giờ hãy xem xét một tủ lạnh đóng kín. Ban đầu, nhiệt độ bên trong tủ lạnh (trong ngăn tủ lạnh) sẽ giảm, sau đó trong phòng sẽ tăng lên và hơi nóng.

⟦folio 54⟧

nhanh hơn so với trường hợp tủ lạnh mở, vì lúc này nhiệt được lấy không phải từ không khí trong phòng mà từ không khí, nằm trong một thể tích hạn chế của tủ và được tách ra khỏi không khí trong phòng. Nhiệt độ trong phòng có thể cao hơn $T_1$ hoặc thấp hơn. Điều này phụ thuộc vào cường độ trao đổi nhiệt giữa phòng và đường phố cũng như nhiệt độ bên trong tủ lạnh mà tại đó bộ điều chỉnh nhiệt trở nên bằng nhau (tức là từ khi tủ lạnh chạy cho đến khi tắt). Khi nhiệt độ trong tủ lạnh đạt đến nhiệt độ cài đặt, bộ điều chỉnh nhiệt sẽ ngắt tủ lạnh khỏi mạng và nhiệt độ bên trong tủ lạnh sẽ tăng dần do trao đổi nhiệt qua thành tủ lạnh. Sau đó tủ lạnh bật lại, nhiệt độ trong phòng sẽ thay đổi, v.v. Đồ thị nhiệt độ bên trong tủ lạnh theo thời gian là đường màu xanh lam trên Hình 8.

Cùng với sự biến động nhiệt độ trong ngăn tủ lạnh, nhiệt độ trong phòng cũng thay đổi. Nhưng cũng giống như khi tủ lạnh bị ngắt mạng, nhiệt độ của dàn ngưng cao hơn nhiệt độ trong phòng, nhiệt độ trong phòng vẫn tiếp tục tăng một thời gian, mặc dù tủ lạnh không hoạt động. Sau đó nhiệt độ trong phòng giảm dần cho đến khi tủ lạnh bật trở lại,… Nếu bộ điều chỉnh nhiệt tốt tức là bật tủ lạnh khi cần tăng nhiệt độ bên trong tủ thì tủ lạnh hoạt động gần như liên tục.

Vì một lượng nhiệt tương đối nhỏ được truyền từ tủ lạnh vào phòng qua các vách của tủ lạnh nên tủ lạnh ít sinh công. Nhiệt độ trong phòng giảm dần, có xu hướng ổn định ở mức nào đó (dưới $T_1$). Nếu bộ điều chỉnh nhiệt bị hỏng thì tủ lạnh sẽ tắt trong thời gian dài nếu khả năng trao đổi nhiệt với phòng kém và trong thời gian tương đối ngắn nếu quá trình trao đổi nhiệt này tốt. Điều này xác định sự dao động nhiệt độ và giá trị trung bình mà nhiệt độ trong phòng có xu hướng. Một trong những đường cong của nhiệt độ trong phòng theo thời gian được thể hiện trên Hình 8, đường màu đỏ.

Khi tủ lạnh chứa đầy thực phẩm, cả thời gian tủ lạnh bật và thời gian tắt đều tăng lên. Theo đó, chu kỳ (dao động nhiệt độ trong phòng) cũng thay đổi.

Hãy xem xét một trong các vòng quay của cuộn dây, chẳng hạn như vòng ABC (Hình 9). Khi lò xo bị biến dạng, một nửa vòng này quay lệch khỏi mặt phẳng nằm ngang.

⟦folio 55⟧

Có thể xảy ra trường hợp nếu một đầu cố định và đầu kia quay một góc φ quanh trục thì xuất hiện mômen lực đàn hồi $M=k\varphi$. Sau đó, một lò xo có bán kính $R$ được quấn từ dây với một bước nhỏ hơn nhiều so với $R$. Tính hệ số đàn hồi của lò xo (giả sử tính chất đàn hồi của thép được phục hồi hoàn toàn sau khi cuộn lò xo).

⟦figure⟧
MỘT)

⟦figure⟧
b)

⟦figure⟧
V)

⟦figure⟧
G)

Hình 10.

F287. *Kênh đi qua một cây cầu bắc qua đường cao tốc. Liệu áp lực lên cầu có thay đổi nếu một sà lan rỗng di chuyển dọc theo kênh một lần và một sà lan chở hàng di chuyển vào lần khác không?*

F288. *Bình C (Hình 11) giao tiếp với không gian xung quanh thông qua một lỗ nhỏ. Nhiệt độ của khí trong không gian xung quanh T, áp suất p. Khí loãng đến mức các phân tử không va chạm với nhau khi bay vào và ra khỏi bình trên kích thước của lỗ. Nhiệt độ trong tàu được duy trì ở mức 4T. Áp suất trong bình sẽ là bao nhiêu?*

⟦column⟧

tốc độ ở các góc bằng nhau α. Nếu độ biến dạng của lò xo nhỏ thì góc α này cũng nhỏ. Trong phần B, một lực F và mômen của lực F bằng $M=FR$ tác dụng lên dây từ phía dưới của lò xo, trong đó R là bán kính của cuộn dây lò xo. Các ứng suất cân bằng lực F nhỏ hơn R/r lần so với các ứng suất cân bằng mômen M (chứng minh điều này; r là bán kính tiết diện của dây), và chúng có thể bỏ qua. Điều này có nghĩa là khi xét sự biến dạng của lò xo, chúng ta có thể giả sử rằng nó liên quan đến sự xoắn của dây quanh trục của nó. Chúng ta hãy tìm xem lực căng của lò xo liên hệ như thế nào với góc φ mà dây xoắn được. Rõ ràng phần C không quay khi lò xo bị kéo dãn. Thật vậy, khi lò xo bị kéo căng, phần AC trên và phần NE dưới của cuộn dây sẽ quay cùng một góc theo các hướng khác nhau. Rõ ràng là phần A và B không quay. (Chúng chỉ lệch một chút trong mặt phẳng vuông góc với hình vẽ, phù hợp với sự thay đổi độ nghiêng của cuộn dây.)

Chỉ cần nghiêng một nửa vòng quay BC một góc α sẽ làm cho phần B và C quay một góc α (Hình 10, a, b). Nhưng phần B và C phải giữ nguyên hướng như ở một lò xo không bị biến dạng. Hãy xoay chúng tuần tự theo góc α. Phần quay C sẽ làm cho một nửa vòng quay xoắn một góc α theo chiều kim đồng hồ (Hình 10, c). Dây được xoắn cùng một góc khi xoay đoạn B qua một góc α (Hình 10, d). Do đó, một nửa vòng quay quay một góc 2α. Toàn bộ cuộn dây được xoắn một góc 4α, toàn bộ dây được xoắn một góc φ=4nα, trong đó n là số vòng của lò xo.

Vì chiều dài của một vòng là $2\pi R$ và chiều dài của dây là $l$ nên $n=\dfrac{l}{2\pi R}$ và $\varphi=\dfrac{2l\alpha}{\pi R}$.

Rõ ràng là độ giãn dài của lò xo trong một vòng (xem Hình 9) bằng $2\Delta h=4R\sin\alpha$, hoặc, vì góc α nhỏ và $\sin\alpha\approx\alpha$, $2\Delta h\approx4R\alpha$. Độ giãn dài của toàn bộ lò xo (trên n vòng) là $\Delta H=4nR\alpha$. Gọi hệ số đàn hồi của lò xo là μ. Sau đó $F=\mu\Delta H$. Mặt khác, $M=FR$, tức là $F=\dfrac{M}{R}$. Vì vậy, $\mu\Delta H=\dfrac{M}{R}=\dfrac{k\varphi}{R}$. Từ đây

$$\mu=\dfrac{k\varphi}{R\Delta H}=\dfrac{k4n\alpha}{R4nR\alpha}=\dfrac{k}{R^2}.$$

◆

Áp lực lên cầu được xác định bởi mực nước trong kênh. Nếu sà lan di chuyển dọc theo một con kênh thì nói đúng ra, mực nước càng dâng cao thì sà lan càng nặng. Tuy nhiên, trên thực tế, mực nước trong toàn bộ kênh tất nhiên vẫn giữ nguyên vì lượng nước bị sà lan chiếm chỗ là rất nhỏ so với tổng lượng nước trong kênh.

◆

Áp suất khí trong bình bằng $p_1=n_1kT_1=4n_1kT$, trong đó $n_1$ là nồng độ của các phân tử trong bình (số lượng phân tử trên một đơn vị thể tích) và k là hằng số Boltzmann. Bên ngoài bình, áp suất là $p=n_2kT$ ($n_2$ là nồng độ của các phân tử trong không gian xung quanh). Kể từ đây,

$$p_1=4p\dfrac{n_1}{n_2}.$$

Vì vậy, để tìm áp suất trong bình, việc xác định tỷ lệ nồng độ của các phân tử khí trong bình và trong không gian xung quanh là đủ. Để tìm tỷ lệ này, chúng ta lợi dụng thực tế là khí trong bình ở trạng thái cân bằng.

Ở trạng thái cân bằng, số phân tử khí thoát ra

⟦folio 56⟧

⟦figure⟧
Hình 11.

bình bằng số phân tử khí bay vào bình trong cùng thời gian. Để đơn giản cho lý luận, chúng ta sẽ giả sử rằng tốc độ của tất cả các phân tử khí ở nhiệt độ ổn định là như nhau và bằng căn bậc hai tốc độ bình phương tương ứng với nhiệt độ này. Ngoài ra, chúng ta sẽ giả sử rằng các phân tử chuyển động dọc theo ba hướng vuông góc với nhau, một trong số đó vuông góc với mặt phẳng cắt ngang của lỗ, và tất cả các hướng đều có khả năng xảy ra như nhau. Sau đó $1/6$ một phần của tất cả các phân tử có trong bình sẽ di chuyển về phía lỗ. Trong thời gian $\Delta t$, những phân tử nằm cách lỗ một khoảng bằng $v_1\Delta t$ bay ra khỏi bình, trong đó $v_1$ là tốc độ của các phân tử trong bình. Vì nồng độ của các phân tử trong bình là $n_1$ nên theo thời gian $\Delta t$ $1/6\, n_1 v_1 \Delta t \Delta S$ các phân tử bay ra khỏi bình ($\Delta S$ là diện tích của lỗ). Tương tự, chúng ta thấy rằng các phân tử $1/6\, n_2 v_2 \Delta t \Delta S$ bay vào trong bình từ bên ngoài, trong đó $v_2$ là tốc độ của các phân tử khí trong không gian xung quanh. Trong điều kiện cân bằng $n_1 v_1 = n_2 v_2$. Từ đó chúng ta thấy rằng tỷ lệ nồng độ của các phân tử bằng

$$\frac{n_1}{n_2} = \frac{v_2}{v_1}.$$

Nhưng, như đã biết, tốc độ bình phương trung bình gốc của các phân tử có liên quan đến nhiệt độ khí theo công thức $\dfrac{m\overline{v^2}}{2} = \dfrac{3kT}{2}$

($m$ là khối lượng của phân tử). Kể từ đây,

$$v_1 = \sqrt{\frac{12kT}{m}}, \quad v_2 = \sqrt{\frac{3kT}{m}} \quad \text{и} \quad \frac{n_1}{n_2} = \frac{1}{2}.$$

Sử dụng mối quan hệ này, chúng tôi tìm thấy áp suất khí trong bình:
$$p_1 = 2p.$$

◆

⟦figure⟧
Hình 12, A.

**F289.** Một thanh cứng có chiều dài $2l$ trượt dọc theo các cạnh của góc vuông, ở giữa có một hạt có khối lượng $m$ được cố định. Tốc độ của điểm $B$ không đổi và bằng $v$ (Hình 12, a). Xác định lực mà hạt tác dụng lên thanh tại thời điểm $\alpha=45°$.

⟦figure⟧
Hình 12, b.

⟦column⟧

Hãy xem xét một hạt. Có hai lực tác dụng lên nó - lực hấp dẫn $m\mathbf{g}$ và lực $\mathbf{Q}$ phản lực của thanh. Theo định luật thứ hai của Newton

$$m\mathbf{g}+\mathbf{Q}=m\mathbf{a}.$$

Do đó, nếu tìm được gia tốc của hạt thì từ đó chúng ta sẽ xác định được lực $\mathbf{Q}$. Và theo định luật thứ ba của Newton, lực $\mathbf{N}$ mà hạt tác dụng lên cây gậy có giá trị tuyệt đối bằng lực $\mathbf{Q}$.

Hãy vẽ một số vị trí của cây gậy (Hình 12, b). Từ hình vẽ có thể thấy hạt (điểm $C$) luôn cách đỉnh của góc vuông một khoảng bằng nhau. Điều này xuất phát từ thực tế là trong một tam giác vuông, đường trung tuyến nối đỉnh của góc vuông với giữa cạnh huyền bằng một nửa cạnh huyền.

Vì vậy, hạt chuyển động dọc theo một đường tròn có bán kính $l$, tốc độ $v_c$ của hạt luôn hướng tiếp tuyến với đường tròn này và gia tốc hướng tâm bằng

$$a_\mathrm{ц} = \frac{v_c^2}{l}.$$

Tại bất kỳ thời điểm nào, tổng tốc độ của hạt là tổng của các thành phần ngang và dọc. Theo điều kiện bài toán tốc độ của điểm $B$ không đổi và bằng $v$. Vì lý do giống nhau, vận tốc theo phương ngang của tất cả các điểm khác cũng không đổi và vận tốc theo phương ngang của hạt bằng $\dfrac{v}{2}$. Điều này có nghĩa là gia tốc và lực $\mathbf{Q}$ của hạt được hướng theo phương thẳng đứng!

Tại thời điểm $\alpha=45°$, tốc độ $v_c$ của hạt hướng dọc theo thanh và đồng thời theo chiều dọc và chiều ngang của nó

⟦folio 57⟧

⟦figure⟧
Hình thế kỷ 12

các thành phần có độ lớn giống hệt nhau và bằng $\dfrac{v}{2}$ (Hình 12, c).

Do đó, tốc độ tổng cộng của hạt tại thời điểm này bằng

$$\sqrt{2}\,\dfrac{v}{2}\ .\ \text{Поэтому}\ a_{\text{ц}} = \dfrac{v_c^2}{l} = \dfrac{v^2}{2l}\ \text{и}$$

$$a = \sqrt{2}a_{\text{ц}} = \dfrac{v^2}{\sqrt{2}\,l}\ .$$

Khi đó từ định luật II Newton

$$Q = mg - ma = m\left(g - \dfrac{v^2}{\sqrt{2}\,l}\right),$$

Và

$$|\mathbf{N}| = |\mathbf{Q}| = m\left(g - \dfrac{v^2}{\sqrt{2}\,l}\right).$$

◆

F290. Ống chứa một lò xo có gắn một quả cầu, có thể quay quanh một trục thẳng đứng đi qua đầu ống. Đầu tự do của lò xo được gắn vào ống (Hình 13). Đồ thị lực đàn hồi của lò xo $F$ theo biến dạng được trình bày trên Hình 14.

Vẽ đồ thị gần đúng về sự phụ thuộc của độ dịch chuyển của quả bóng dọc theo ống vào vận tốc góc khi nó tăng từ 0 đến một giá trị sao cho $F=5\text{н}$. Mối quan hệ này sẽ thay đổi như thế nào khi vận tốc góc giảm? $l_0 = 2$ xem

⟦figure⟧
Hình 13.

⟦figure⟧
Hình 14.

⟦column⟧

Chúng ta sẽ giả sử rằng vận tốc góc $\omega$ quay của ống thay đổi chậm, sao cho tại mỗi giá trị $\omega$ quả bóng ở trạng thái cân bằng so với ống và trong hệ quy chiếu đứng yên, quả bóng chuyển động dọc theo một đường tròn có bán kính $l_0+\Delta l$ ($\Delta l$ là sự thay đổi độ dài của lò xo). Vì gia tốc hướng tâm $a=\omega^2(l_0+\Delta l)$ được truyền vào quả bóng nhờ lực đàn hồi của lò xo nên theo định luật Newton

$$m\omega^2(l_0+\Delta l)=F_{\text{упр}}. \qquad (*)$$

Để giải bài toán, cần tìm từ phương trình (*) sự phụ thuộc của $\Delta l$ vào $\omega$ hoặc thuận tiện hơn là $l=l_0+\Delta l$ vào $m\omega^2$.

Sự phụ thuộc của lực đàn hồi của lò xo vào độ giãn dài của lò xo được cho bằng đồ thị nên ta cũng sẽ giải phương trình (*) bằng đồ thị. Hãy vẽ lại đồ thị, di chuyển gốc tọa độ đến điểm có tọa độ $-l_0$ (Hình 15). Bây giờ dọc theo trục hoành chúng ta có tổng chiều dài $l$ của lò xo. Nếu chúng ta vẽ một đường thẳng từ gốc tọa độ thì tọa độ giao điểm của đường thẳng này với đồ thị sẽ là các giá trị $F_{\text{упр}}$ và độ dài tương ứng của lò xo $l$, và tiếp tuyến của góc nghiêng của đường thẳng với trục abscissa sẽ bằng $F_{\text{упр}}/l$, tức là $m\omega^2$.

Để xây dựng đồ thị về sự phụ thuộc của $l$ vào $m\omega^2$, chúng ta vẽ một loạt đường thẳng từ gốc tọa độ và đánh dấu tất cả các điểm giao nhau của các đường thẳng với đồ thị. Sau đó, khi biết các giá trị của $l$ và các giá trị tương ứng của $m\omega^2=\mathrm{tg}\alpha$, chúng ta sẽ đánh dấu chúng trên đồ thị sự phụ thuộc của $l$ vào $m\omega^2$. Từ Hình 15, rõ ràng là ở các góc $\alpha<\alpha_1$, tức là ở $m\omega^2<\mathrm{tg}\alpha_1$, mỗi đường thẳng vẽ cắt đồ thị $F_{\text{упр}}(l)$ chỉ tại một điểm và mỗi giá trị $m\omega^2$ tương ứng với một giá trị $l$. Tại $\alpha_1<\alpha<\alpha_2$ đường thẳng cắt đồ thị tại ba điểm (tại $\alpha=\alpha_1$ và $\alpha=\alpha_2$ - tại hai điểm), tức là cùng một giá trị $m\omega^2$ tương ứng với ba giá trị $l$. Chúng ta hãy đánh dấu tất cả chúng trên biểu đồ, tạm thời gác lại câu hỏi về ý nghĩa của từ đa nghĩa đó. Tại $\alpha>\alpha_2$, tức là tại $m\omega^2>\mathrm{tg}\alpha_2$, mỗi đường lại cắt đồ thị tại một điểm duy nhất và mỗi giá trị $m\omega^2$ tương ứng với một giá trị $l$. Bằng cách kết nối tất cả các điểm được vẽ bằng một đường cong trơn, chúng ta có được biểu đồ như trong Hình 16 với một đường màu đen. Chúng ta hãy nhìn vào biểu đồ này chi tiết hơn.

Tại $m\omega^2<\mathrm{tg}\alpha_1$ và tại $m\omega^2>\mathrm{tg}\alpha_2$ mỗi giá trị vận tốc góc tương ứng với một giá trị $l$. Mọi thứ đều rõ ràng ở đây. Nhưng với $\mathrm{tg}\alpha_1<m\omega^2<\mathrm{tg}\alpha_2$ có ba giá trị khác nhau của $l$ cho mỗi giá trị $m\omega^2$. Quả bóng cách trục quay một khoảng bằng bao nhiêu? Trước hết, rõ ràng là quả bóng không

⟦folio 58⟧

có thể ở khoảng cách tương ứng với điểm $B_2$ của đồ thị (xem Hình 15). Thật vậy, giả sử rằng do một số nguyên nhân ngẫu nhiên mà quả bóng lệch khỏi vị trí cân bằng này, do đó $l$ tăng thêm $\Delta x$. Để quả bóng quay khi ở cách trục $l + \Delta x$ thì lực nén phải tăng. Trong trường hợp của chúng tôi, lực nén, như có thể thấy trên hình, đã giảm. Do đó, lực này không thể truyền cho quả bóng gia tốc hướng tâm cần thiết cho chuyển động của nó và quả bóng sẽ tiếp tục chuyển động dọc theo ống đến vị trí $B_3$. Như vậy, điểm $B_2$ ứng với vị trí mất cân bằng không ổn định của quả bóng. Tương tự, có thể chứng minh rằng các điểm $B_1$ và $B_3$ tương ứng với vị trí cân bằng ổn định của quả bóng.

Posny tại $tg\alpha_1 < m\omega^2 < tg\alpha_2$ quả bóng có thể ở các vị trí tương ứng với các phần của đồ thị $A_1C_1$ và $A_2C_2$.

Hình 15

Hình 16.

Quả bóng sẽ ở vị trí ổn định nào? Đáp số cho câu hỏi này phụ thuộc vào tốc độ góc quay của ống thay đổi như thế nào. Nếu $\omega$ tăng thì quả bóng không thể đến các vị trí tương ứng với phần $A_2C_2$ của đồ thị mà không đến các vị trí tương ứng với phần $A_1C_1$, phần nào ổn định. Do đó, khi vận tốc góc tăng dần $l$ sẽ ít hơn theo đồ thị trên Hình 16 đường màu đỏ (tại điểm $m\omega^2 = tg\alpha_2$ giá trị $l$ thay đổi đột ngột từ giá trị tương ứng với điểm $C_1$ thành giá trị tương ứng với điểm $C_2$). Khi vận tốc góc tăng, đồ thị của $l$ so với $m\omega^2$ sẽ có dạng đường màu xanh lam. Cần lưu ý rằng nếu ống quay với vận tốc góc sao cho $tg\alpha_1 < m\omega^2 < tg\alpha_2$, thì nếu chỉ có quả bóng bằng 0, nó có thể được di chuyển đến vị trí tương ứng với phần “ngoài hành tinh” của đồ thị, theo đó $l$ sẽ tiếp tục thay đổi khi $\omega$ thay đổi.

Tôi. Sh. Tiếng Slovodetsky
