---
id: 1991-7-konvey-odin-staryiy-fakt-i-neskolko-novyih-100a19a3
issue: kvant_1991_7
year: 1991
number: "7"
title: Một sự thật cũ và một vài sự thật mới
authors:
  - Конвей Дж.
rubric: raznoe
rubric_sub: Разное
page_first: 66
page_last: 68
page_labels: 64-66
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 76a7934ede6720f87dd926a9a7519be6bccf07ced40f2ae0e2520cbdcf0491a0
prompt_sha256: draft-1
translated_from: content/ru/1991/07/articles/21_konvey-odin-staryiy-fakt-i-neskolko-novyih-100a19a3.md
source_content_sha256: ca26826b20eb8253b22cf0d41ed0ead10517433df77d5b51d147103211069a08
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 64⟧

---
running_head:
folio:
---

Một sự thật cũ và một vài sự thật mới
MỚI
(Một cuộc hành trình khác vào thế giới của những con số tượng hình và những con số bằng số: những con số khó hiểu có thể khiến bạn mê mẩn)

J. CONWAY

Thêm $n$ số lẻ đầu tiên, bắt đầu bằng 1. Bạn nhận được gì?

$$
\begin{array}{l}
1 = 1, \\
1 + 3 = 4, \\
1 + 3 + 5 = 9, \\
1 + 3 + 5 + 7 = 16, \\
1 + 3 + 5 + 7 + 9 = 25.
\end{array}
$$

Trong số thứ ba của tạp chí, chúng tôi bắt đầu xuất bản bản dịch các bài báo từ tạp chí Mỹ Xô-Mỹ «Kvant». Hôm nay chúng tôi mang đến cho bạn sự chú ý của bài viết tiếp theo trong loạt bài này.

Bạn có nhận ra những con số này không? Chắc chắn! Đây là những số "bình phương" (hãy nhớ lý do tại sao bình phương của các số nguyên được gọi như vậy):

$$
1 = 1 \cdot 1, \quad 4 = 2 \cdot 2, \quad 9 = 3 \cdot 3, \quad 16 = 4 \cdot 4, \quad 25 = 5 \cdot 5, \dots
$$

Và đây là sự thật cũ của chúng tôi. Nó có thể được giải thích? Tóm tắt? Có thể lấy số "khối" theo cách tương tự không?

$$
1 = 1 \cdot 1 \cdot 1, \quad 8 = 2 \cdot 2 \cdot 2, \quad 27 = 3 \cdot 3 \cdot 3, \quad 64 = 4 \cdot 4 \cdot 4, \dots?
$$

Vâng, có nhiều cách giải thích khác nhau và chúng dẫn đến nhiều sự thật khác nhau. Chúng ta hãy thử nhìn trước

Theo quan điểm đại số

Ta phải chứng minh rằng hiệu giữa các số bình phương liên tiếp 0, 1, 4, 9, 16, 25,... chính là các số lẻ 1, 3, 5, 7, 9, 11,...

Nhưng điều này rất đơn giản: phép tính đại số hiển nhiên cho thấy rằng sự khác biệt như vậy ở dạng tổng quát bằng

$$(n + 1)^2 - n^2 = (n^2 + 2n + 1) - n^2 = 2n + 1,$$

Theo cách tương tự, bạn có thể xác minh rằng sự khác biệt giữa các giá trị liên tiếp của bất kỳ đa thức nào là giá trị của một đa thức nào đó nhỏ hơn bậc. Ví dụ: các khối lân cận khác nhau bởi các số có dạng $3n^2 + 3n + 1$, tức là bởi các số bí ẩn

$$
1, 7, 19, 37, 61, \dots
$$

Các hình khối là tổng của một vài số đầu tiên của dãy này:

$$
1 = 1, \quad 1 + 7 = 8, \quad 1 + 7 + 19 = 27, \dots
$$

Buồn thay!.. Tại sao người ta lại phải quan tâm đến những con số bí ẩn này?

Hãy thử lại.

Theo quan điểm số học

Tổng của một số số bằng tích của số đó và giá trị trung bình số học của chúng. Vì vậy, ví dụ: tổng của $1 + 3 + 5 + 7 + 9$ là $5 \times 5$. Trung bình

⟦folio 65⟧

---
running_head:
folio:
---

tổng số học
1, 1+3, 1+3+5, 1+3+5+7,...
là nửa tổng của số hạng đầu tiên và số hạng cuối cùng, và rõ ràng chúng bằng nhau
1, 2, 3, 4,...
Điều này đưa chúng ta đến một cách tuyệt vời để có được hình khối. Thay vì luôn lấy tổng của các số lẻ $n$ đầu tiên, chúng ta sẽ lấy các số $n$ tiếp theo, bắt đầu từ nơi chúng ta đã dừng lại.
Sau đó cùng nhau các đẳng thức
$$
\begin{align*}
1 &= 1^2, \\
1+3 &= 2^2, \\
1+3+5 &= 3^2,
\end{align*}
$$
chúng tôi sẽ có
$$
\begin{align*}
1 &= 1^3, \\
3+5 &= 2^3, \\
7+9+11 &= 3^3,
\end{align*}
$$
Cách này tốt hơn, nhưng hãy thử ý tưởng khác.

Theo quan điểm hình học
Hãy nhìn vào mô hình này:

Nó cho thấy rất rõ ràng một số bình phương được chia thành các số lẻ liên tiếp như thế nào. Chúng ta có thể xem những con số bí ẩn 1, 7, 9, 37, 61 như những hình chấm không? Bảy đồng xu phù hợp một cách tự nhiên với một hình dáng gọn gàng có thể cho chúng ta biết... Ồ, tất nhiên rồi! Những con số bí ẩn của chúng ta

được biết đến trong tổ hợp là “số hex” (“sáu” trong tiếng Hy Lạp; đừng nhầm lẫn với thuật ngữ “lục giác” - số lục giác, hãy giới thiệu một cái gì đó khác).

Có đúng là tổng của một vài số hex đầu tiên là số thực? Phải! Và để thấy điều này, việc kiểm tra một vài dòng khá đơn giản hơn - và

các mẫu dấu chấm biến thành các ô hình khối có thể lồng vào nhau để tạo thành một khối chứa đầy các dấu chấm.

Bảng của tôi có các "khối" lục giác giống như những khối được hiển thị trong hình, mà cô ấy đã sử dụng để tạo ra các paramit lục giác. Cô ấy cần bao nhiêu khối lập phương cho một paramida có $n$ tầng?

Có vẻ như thực sự có nhiều cách khái quát hóa khác nhau về thực tế cơ bản của chúng ta, và điều đó không sao cả, hoặc điều đó có nghĩa là luôn có hy vọng tìm ra điều gì đó mới mẻ. Tuy nhiên, một số trong những cái nổi bật nhất chỉ được phát hiện gần đây.

⟦folio 66⟧

---
running_head:
folio:
---

Hãy bắt đầu với hình vuông. Hãy viết ra một vài số tự nhiên đầu tiên, khoanh tròn mỗi giây và cộng phần còn lại:
1 2 3 4 5 6 7 8 9 ...
$\textcircled{1}$ $\textcircled{4}$ $\textcircled{9}$ $\textcircled{16}$ $\textcircled{25}$...

Tất nhiên, nó hóa ra là hình vuông.
Bây giờ, hãy thay đổi quy trình - khoanh tròn mọi số thứ ba ở hàng trên cùng, tạo thành hàng tiếp theo, như trước, khoanh tròn mọi số thứ hai trong đó và cộng các số chưa được khoanh tròn.
Số tiền sẽ là hàng thứ ba:
1 2 3 4 5 6 7 8 9 ...
1 3 7 12 19 27 ...
$\textcircled{1}$ $\textcircled{8}$ $\textcircled{27}$...

Storpriz! Hình khối đã xuất hiện! Bạn có thể chứng minh rằng điều này sẽ tiếp tục?
Điều này dường như cũng áp dụng cho tất cả các mức độ khác. Giả sử, nếu chúng ta khoanh tròn mọi số thứ năm ở hàng đầu tiên, mọi số thứ tư ở hàng thứ hai, v.v., chúng ta sẽ làm đúng ít nhất với năm lũy thừa đầu tiên.

1 2 3 4 5 6 7 8 9 10 11 ...
1 3 6 10 16 23 31 40 51 ...
1 4 10 26 49 80 131 ...
1 5 31 80 211 ...
$\textcircled{1}$ $\textcircled{32}$ $\textcircled{243}$...

Bạn có thể kiểm tra xem mô hình này có luôn đúng không?
Nói chung, bạn có thể khoanh tròn bất kỳ bộ số nào ở hàng trên cùng, chia các số còn lại thành chuỗi. Ở các hàng tiếp theo, số cuối cùng của mỗi chuỗi được khoanh tròn, tạo thành một hàng mới từ tổng các số không được khoanh tròn, v.v.
Chúng ta thấy rằng nếu khoanh tròn các số ở hàng trên cùng
1+1, 2+2, 3+3, 4+4, ...
sau đó hình vuông xuất hiện, tức là số
1·1, 2·2, 3·3, 4·4,...

Và khoanh tròn các con số
1+1+1, 2+2+2, 3+3+3, ...
chúng tôi nhận được hình khối
1·1·1, 2·2·2, 3·3·3, ...

Điều gì xảy ra khi bạn khoanh tròn các số "tam giác"?
1, 1+2, 1+2+3, 1+2+3+4,
1+2+3+4+5,...?

Đáp số
Tất nhiên, con gái tôi cần $n^3$ cốc cho tầng cao 6 tầng.
Có, khi tiếp tục dòng trên cùng, chúng ta sẽ nhận được tất cả các hình khối liên tiếp ở dòng dưới cùng (thứ ba). Điều này hoàn toàn không khó chứng minh bằng cách viết ra dãy số ở dạng tổng quát:
... $3n-1$ $3n+1$ $3n+2$ $3n+3$
$3n^2$ $3n^2+3n+1$ $3(n+1)^2$
$n^3$ $(n+1)^3$

Sẽ khó hơn một chút để chứng minh rằng quy tắc cho bậc $k$ áp dụng cho tất cả $k$. Chúng tôi sẽ công bố bằng chứng tốt nhất được gửi.
Số tam giác
1, 1+2, 1+2+3, 1+2+3+4,
1+2+3+4+5

Phép biến đổi Messner được thêm vào sẽ chuyển đổi (tất nhiên!) thành giai thừa:
1, 1·2, 1·2·3, 1·2·3·4,
1·2·3·4·5, ...

Đã chuẩn bị xuất bản
V. Dubrovsky
