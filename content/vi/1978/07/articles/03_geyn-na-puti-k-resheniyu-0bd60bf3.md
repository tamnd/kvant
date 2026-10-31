---
id: 1978-7-geyn-na-puti-k-resheniyu-0bd60bf3
issue: kvant_1978_7
year: 1978
number: "7"
title: Đang trên đường đến lời giải
authors:
  - Гейн А. Г.
rubric: osnovnye-stati
page_first: 12
page_last: 16
page_labels: 10-14
tag: DITD
lang: vi
source: kvant_digital
extraction: vision
content_sha256: d69cb99f722cba8720ba3e03e4207d1bb83029569ca20e65a6469592a10e1c60
prompt_sha256: draft-1
translated_from: content/ru/1978/07/articles/03_geyn-na-puti-k-resheniyu-0bd60bf3.md
source_content_sha256: 22365aacc3e5f159f83da5ef277bc65256e2effd7828a12ff0947a265eb48cbc
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 10⟧

1. Sự lặp lại

- Bạn không thấy sao?
- KHÔNG.
- Tôi cũng vậy!

Izagrovora Eeyore Winnie the Pooh*)

Bắt đầu từ đâu? Trước hết, với đáp số trong các biến thể trường học bài toán (n=2, 3, 4). Hãy viết những đáp số này vào bảng:

| n = 2 | (1, 1) | (1, 2) | (2, 3) | |
| :--- | :--- | :--- | :--- | :--- |
| n = 3 | (1, 1, 1) | (1, 1, 2) | (1, 2, 3) | (2, 3, 7) |
| n = 4 | (1, 1, 1, 1) | (1, 1, 1, 2) | (1, 1, 2, 3) | (2, 3, 7, 43) |

Có đúng là lời giải đối với n ước tính khác nhau là tương tự nhau không? Chúng tạo thành chuỗi dọc và thu được bằng cách thêm các đơn vị. Quan sát này mở rộng đến tất cả n có thể bằng cách sử dụng bổ đề được đánh giá sau:

Bổ đề 1. Giả sử tập hợp các số (x₁, x₂, ..., xₙ) là nghiệm của bài toán với n=k. Khi đó tập hợp các số (x₁, x₂, ..., xₙ, 1) là lời giải bài toán với n=k+1. Và theo một tập hợp: nếu trong số k+1 số là nghiệm của bài toán cho n=k+1 có một số, thì bằng cách xóa nó khỏi tập hợp, chúng ta nhận được lời giải bài toán cho n=k.

Các bộ truyện mới ra đời như thế nào: (2, 3), (2, 3, 7),...?

Đặt (x₁, ..., xₙ) — lời giải bài toán với n=k. Theo điều kiện bài toán, nếu (x₁, ..., xₙ, xₙ+1) - lời giải bài toán với n=k+1, thì x₁ ... xₙ+1 + 1 = Cxₙ+1, trong đó C là một số tự nhiên. Hãy thử đặt C bằng một (điều này cho ra các số 3=2+1, 7=2·3+1, 43=2·3·7+1). Hãy chứng minh bổ đề sau:

Bổ đề 2. Nếu tập hợp số (x₁, ..., xₙ) là lời giải bài toán cho n=k, thì tập hợp số (x₁, ..., xₙ, xₙ+1) là lời giải bài toán cho n=k+1.

*) Tất cả các đề từ đều được lấy từ truyện cổ tích Milne “Winnie the Pooh and Everything, Everything, Everything.”

Sử dụng Bổ đề 1 và 2, từ mỗi lời giải bài toán cho n=k hai lời giải bài toán cho n=k+1 có thể thu được. Hình 1 cho thấy từ lời giải bài toán cho n=2 bằng cách sử dụng Bổ đề 1 (mũi tên màu đỏ) và sử dụng Bổ đề 2 (mũi tên màu xanh), theo cách này, chúng ta thu được lời giải bài toán đầu tiên cho n=3 và sau đó cho n=4.

Không phải bất cứ nơi nào chúng ta cũng có thể nhận được tất cả lời giải theo cách này. Tuy nhiên, thật dễ dàng để chứng minh rằng tập hợp được chỉ ra trong Hình 1 sử dụng hết tất cả lời giải trong số bài toán của chúng tôi đối với n=2, 3, 4. Thật không may, từ lời giải đối với n=4 không phải tất cả lời giải đối với n=5 đều thu được theo cách này; Ngoài lời giải (2, 3, 7, 43, 1807), thu được bằng sàng của Bổ đề 2, còn có: (2, 3, 7, 47, 395).

2. Chi tiết của phương trình

Ngoài ra chỉ cần một thìa cà phê là đã tốt rồi.

Winnie the Pooh

Bổ đề 1 ở đây cho phép chúng ta không xét đến lời giải chứa 1—mọi thứ đều rõ ràng với chúng. Sau đó, nếu tập hợp (x₁, ..., xₙ) là lời giải bài toán với n=k, thì tất cả xᵢ đều khác biệt (nghĩ xem tại sao).

⟦folio 11⟧

Cơm. 1.

Bằng cách phân tích đáp số bài toán cho $n = 2, 3$ và 4, chúng ta chỉ có thể tạo ra các giả thuyết về cấu trúc của những đáp số này chứ không phải về cách giải quyết bài toán. Bây giờ chúng ta hãy xem làm thế nào để có được những đáp số này cho $n = 3$.

Đặt $(x, y, z)$ là một số lời giải bài toán với ba số. Khi đó đẳng thức phải giữ

$$\begin{cases} xy + 1 = k_1z, \\ xz + 1 = k_2y, \\ yz + 1 = k_3x, \end{cases}$$

trong đó $k_1, k_2, k_3$ là một số số tự nhiên.

Nhân các tỉ số này, ta được

$$xyz (xyz + x + y + z) + xy + xz + yz + 1 = k_1k_2k_3xyz.$$

Suy ra $xy + xz + yz + 1$ chia hết cho $xyz$, tức là

$$xy + xz + yz + 1 = Axyz,$$

trong đó $A$ là số tự nhiên. Chia cả hai vế của đẳng thức này cho $xyz$, chúng ta nhận được

$$\frac{1}{x} + \frac{1}{y} + \frac{1}{z} = A. \quad (1)$$

Vì vậy, mọi lời giải bài toán cho $n = 3$ đều thỏa mãn phương trình (1). Tách chúng ta khỏi mẫu số, dễ dàng nhận thấy điều ngược lại là đúng: nếu $x, y, z$ là các số tự nhiên thỏa mãn - đối với một số $A$ tự nhiên - phương trình (1), thì $(x, y, z)$ - lời giải bài toán đối với $n = 3$.

Vế trái của (1) lấy giá trị lớn nhất cho các giá trị nhỏ nhất $x, y, z$; nếu $2 \leq x < y < z$ thì

$$A \leq \frac{1}{2} + \frac{1}{3} + \frac{1}{4} + \frac{27}{24} < 2.$$

Do đó, $A = 1$ và $x, y, z$ thỏa mãn phương trình

$$\frac{1}{x} + \frac{1}{y} + \frac{1}{z} = 1.$$

Chà, bước đầu tiên rất tự nhiên. Sử dụng định nghĩa về khả năng chia hết, chúng tôi sử dụng một số từ mơ hồ - một số được chia thành các đối tượng cụ thể và quen thuộc. Đúng, những ẩn số mới $k_1, k_2, k_3$ đã xuất hiện mà trước đây chưa từng có, nhưng đây là quả báo chung cho “một số định nghĩa”. Và bước thứ hai khá dễ hiểu - mong muốn loại bỏ những ẩn số “thêm” (bằng cách chuyển từ một hệ thống sang một phương trình duy nhất).

Sau khi thực hiện một thao tác tương tự cho một $n$ tùy ý, chúng ta lại thu được phương trình có dạng

$$\frac{1}{x_1} + \frac{1}{x_2} + \dots + \frac{1}{x_n} + \frac{1}{x_1 \dots x_n} = A, \quad (2)$$

trong đó $A$ là số tự nhiên. Một lần nữa, điều ngược lại rất dễ được xác minh:

nếu $x_1, x_2, \dots, x_n$ là các số tự nhiên thỏa mãn, đối với một số $A$ tự nhiên, phương trình (2), thì tập $(x_1, x_2, \dots, x_n)$ là nghiệm của bài toán của chúng ta.

Vì vậy, bài toán ban đầu tương đương với bài toán tìm lời giải của phương trình (2) với số lượng nhỏ nhất đối với mọi $A$ tự nhiên có thể có. Tất nhiên, thăng tiến không hề dễ dàng, nhưng “chỉ một chút thôi… thế là tốt rồi!”

Lấy cảm hứng từ các điều kiện, chúng ta có thể cố gắng chứng minh rằng trong phương trình

⟦folio 12⟧

(2) $A = 1$. Vì chúng ta có thể giả định rằng $2 \leqslant x_1 < x_2 < \dots < x_n$, nên đối với $A$, chúng ta thu được ước tính:

$$A = \frac{1}{x_1} + \dots + \frac{1}{x_n} + \frac{1}{x_1 \dots x_n} \leqslant \frac{1}{2} + \frac{1}{3} + \dots + \frac{1}{n} + \frac{1}{n!}.$$

Tuy nhiên, đối với $n = 14$ tổng ở vế phải đã lớn hơn 2. Nhưng có lẽ từ ước tính này vẫn có thể kết luận rằng giá trị $A$ bị giới hạn và do đó chỉ có thể nhận một số giá trị hữu hạn? Nhưng không: tổng $\frac{1}{2} + \dots + \frac{1}{n}$ tăng vô hạn khi tăng $n$.

Bài tập 1. Chứng minh điều đó.

Rõ ràng phương pháp ước tính của chúng tôi quá thô sơ. Có thể buộc tội anh ta? Ví dụ, rõ ràng là tất cả các số có trong lời giải đều nguyên tố lẫn nhau theo cặp. Do đó, cụ thể, nếu $x_1 = 2$ thì $x_3 > 4$.

Hãy chứng minh rằng tổng $\frac{1}{x_1} + \dots + \frac{1}{x_n} + \frac{1}{x_1 \dots x_n}$ có thể được ước tính từ trên bằng số $\frac{1}{2} + \frac{1}{3} + \frac{1}{5} + \dots + \frac{1}{p} + \frac{1}{2 \cdot 3 \cdot 5 \cdot \dots p}$, trong đó $p$ chỉ là một số.

Thật vậy, chúng ta hãy biểu thị bằng $p_i$ ước số nguyên tố nào đó của số $x_i$. Lưu ý rằng $p_i \leqslant x_i$. Vì các số $x_i$ là số nguyên tố theo cặp nên tất cả $p_i$ đều khác nhau. Chúng tôi sẽ xem xét chúng theo thứ tự kích thước. Sau đó, $2 \leqslant p_1, 3 \leqslant p_2, 5 \leqslant p_3$, v.v. Thay thế $x_i$ bằng $p_i$, chúng ta thu được ước tính cần thiết.

Có lẽ tổng nghịch đảo của các số nguyên tố không vượt quá một số nguyên tố $M$? Điều này có nghĩa là $A < M + 1$. Hóa ra điều này không đúng: với số lượng ngày càng tăng, tổng $\frac{1}{2} + \frac{1}{3} + \dots + \frac{1}{p}$ tăng không giới hạn *). Tuy nhiên, chúng tôi thu được một ước tính cho phép chúng tôi tuyên bố rằng $A = 1$ cho tất cả $n \leqslant 58$. Có một chút an ủi, nhưng ít nhất cũng rõ ràng tại sao, khi phân tích đáp số, chúng tôi không gặp lời giải với hằng số $A = 2$: khó có ai có thể nghĩ đến việc xem xét bài toán cho sáu mươi con số cùng một lúc.

3. Thêm một - không có gì mới

Miễn phí, nghĩa là không có gì cả.

Ai có thể biết trước con đường nào sẽ dẫn đến thành công? Kiên nhẫn (nhưng không bướng bỉnh) là nguyên tắc của nghiên cứu. Chúng ta hãy quay trở lại điểm bắt đầu cuộc hành trình của chúng ta một lần nữa. Bây giờ chúng tôi đã có trong tay khả năng phân tích đáp số và các phương pháp lời giải bài toán cho các trường hợp đặc biệt. Bổ đề 1 và 2 đáng được chú ý - chúng chứa ít nhất một số thuật toán để tìm một số lời giải. Họ đề xuất cách tiếp cận nào? Cả hai bổ đề đều nói về cách lấy lời giải bài toán cho $n = k + 1$ từ lời giải bài toán cho $n = k$. Cách tiếp cận này khá quen thuộc với chúng ta (hãy nhớ đến phương pháp quy nạp toán học). Hãy thử giả sử rằng bài toán lời giải cho $n = k$ để giải nó cho $n = k + 1$.

Vậy đường dẫn là $(x_1, \dots, x_k)$ - lời giải bài toán cho $n = k$. Hãy để chúng tôi biểu thị sản phẩm $x_1 \dots x_k$ bằng $f_k$. Sau đó $\frac{1}{x_1} + \frac{1}{x_2} + \dots + \frac{1}{x_k} + \frac{1}{f_k} = A$.

Nếu số $x_{k+1}$ được bổ sung bởi tập hợp $x_1, \dots, x_k$ đến lời giải bài toán cho $n = k + 1$ và $x_{k+1} \neq 1$, thì sẽ có sự tương ứng:

$$\frac{1}{x_1} + \dots + \frac{1}{x_k} + \frac{1}{x_{k+1}} + \frac{1}{f_k x_{k+1}} = A$$

với cùng $A$ (hãy suy nghĩ kỹ).

Đánh đồng vế trái của hai đẳng thức này và loại bỏ các vế giống hệt nhau, chúng ta thu được

$$\frac{1}{x_{k+1}} + \frac{1}{f_k x_{k+1}} = \frac{1}{f_k};$$

theo dõi, $x_{k+1} = f_k + 1$. Đây chính xác là cách nó diễn ra lời giải và theo

⟦folio 13⟧

Bổ đề 2! Điều này có nghĩa là đẳng thức $x_1 \dots x_k + 1 = C \cdot x_{k+1}$CONSTANTA $C$ bằng 1 không phải là ngẫu nhiên: vấn đề ở đây không phải ở sự đơn giản mà ở phương trình (2). Nhân tiện, Bổ đề 2 $\delta$-rom suy ra từ phương trình này.

Do đó, nếu lời giải bài toán cho $n = k + 1$ thu được bằng cách thêm một số vào lời giải bài toán cho $n = k$, thì nó được hình thành theo Bổ đề 1 hoặc Bổ đề 2.

4. Nếu chúng ta thêm hai thì sao?

Tôi tự hỏi điều gì đã tạo ra tiếng động đó? Tôi không thể gây ra nhiều tiếng ồn một mình được! Và tôi tự hỏi, quả bóng bay của tôi đã đi đâu?

Heo con

Vì vậy, nguồn gốc của Bổ đề 2 ít nhất đã được làm rõ. Đúng, chúng tôi không thu được lời giải mới và vẫn chưa rõ lời giải đến từ đâu, không được hình thành bằng cách áp dụng Bổ đề 1 và 2 (ví dụ: lời giải (2, 3, 7, 47, 395) cho bài toán với $n = 5$). Lại là ngõ cụt à? Chúng ta hãy suy nghĩ lại trước khi từ bỏ con đường đã chọn. Chúng ta đã sử dụng hết tất cả các khả năng trong cách tiếp cận của mình chưa? Ai đang ngăn chúng ta cộng ít nhất hai số? Hãy thử.

Trước tiên, giả sử rằng $(x_1, \dots, x_k)$—lời giải bài toán cho $n = k$. Sau đó

$$\frac{1}{x_1} + \dots + \frac{1}{x_k} + \frac{1}{f_k} = A.$$ (3)

Đặt $(x_1, \dots, x_k, x_{k+1}, x_{k+2})$—lời giải bài toán cho $n = k + 2$ và $x_{k+1} \neq 1, x_{k+2} \neq 1$. Hóa ra trong trường hợp này cũng vậy

$$\frac{1}{x_1} + \dots + \frac{1}{x_k} + \frac{1}{x_{k+1}} + \frac{1}{x_{k+2}} + \frac{1}{f_k x_{k+1} x_{k+2}} = A$$ (4)

với cùng $A$.

Kể từ đây,

$$\frac{1}{x_{k+1}} + \frac{1}{x_{k+2}} + \frac{1}{f_k x_{k+1} x_{k+2}} = \frac{1}{f_k},$$ (5)

Ở đâu

$$x_{k+2} = f_k + \frac{f_k^2 + 1}{x_{k+1} - f_k}.$$ (6)

Vì $x_{k+2}$ phải là số nguyên nên $d = x_{k+1} - f_k$ là ước số của $f_k^2 + 1$. Vì thế,

$$\begin{cases} x_{k+1} = f_k + d, \\ x_{k+2} = f_k + \frac{f_k^2 + 1}{d}. \end{cases}$$ (7)

Bây giờ chúng ta hãy biểu thị bằng $d$ một ước số tùy ý của số $f_k^2 + 1$ và xác định các số $x_{k+1}, x_{k+2}$ bằng các đẳng thức (7). Sau đó, đối với các số $f_k, x_{k+1}, x_{k+2}$ (6) giữ nguyên, và do đó (5) cũng vậy. Từ (3) và (5) suy ra (4). Điều này có nghĩa là tập hợp mở rộng $(x_1, \dots, x_k, x_{k+1}, x_{k+2})$ là một giải pháp cho bài toán của chúng tôi cho $n = k + 2$. Vì vậy, chúng tôi đã chứng minh điều đó.

Bổ đề 3. Đặt $(x_1, \dots, x_k)$—lời giải bài toán cho $n = k, f_k = x_1 \dots x_k$ và $d$ là ước của $f_k^2 + 1$. Khi đó tập $(x_1, \dots, x_k, f_k + d, f_k + \frac{f_k^2 + 1}{d})$ là nghiệm của bài toán đến $n = k + 2$. Và ngược lại: nếu lời giải bài toán với $n = k$ ta cộng hai số $n = k$ ta cộng hai số khác 1 thì các số được cộng thỏa mãn đẳng thức (7).

Do đó, nếu lời giải bài toán cho $n = k + 2$ thu được bằng cách cộng hai số với lời giải bài toán cho $n = k$, thì nó được hình thành theo Bổ đề 2 hoặc Bổ đề 3.

Hai ước của $y f_k^2 + 1$ luôn là 1 và $f_k^2 + 1$. Tuy nhiên, dễ dàng nhận thấy rằng đối với các ước số như vậy, Bổ đề 3 không đưa ra điều gì mới so với Bổ đề 2. Nhưng khi đó, nếu $f_k^2 + 1$ không phải là số nguyên tố thì Bổ đề 3 dẫn đến một chuỗi mới lời giải $(x_{k+3}$ có thể được xây dựng lại bằng Bổ đề 2, v.v.). Ví dụ: với lời giải (2, 3, 7) chúng ta có $f_k^2 + 1 = 1765 = 5 \cdot 353$ và từ đó chúng ta thu được theo Bổ đề 3 lời giải (2, 3, 7, 47, 395), mà chúng ta đã đề cập trong đoạn 1. Tương tự, từ lời giải (2, 3, 7, 43) theo Bổ đề 3, chúng ta thu được lời giải (2, 3, 7, 43, 1823, 193 667) (ở đây $f_k^2 + 1 = 3261637 = 17 \cdot 191861$).

Xét chuỗi lời giải sinh ra từ lời giải

⟦folio 14⟧

(2, 3) theo Bổ đề 2. Chúng ta hãy làm cho nó trở nên cơ bản. Mỗi khi số $f_k^2 + 1$ trở thành hợp số của nó, thì ít nhất một nhánh được tách ra khỏi nó theo Bổ đề 3 (Hình 2).

Có nhiều hợp số trong số $f_k^2 + 1$ của dãy cơ bản không?

Thì 2. Chứng minh rằng trong dãy cơ bản mọi số $f_{2k+1}^2 + 1$ đều chia hết cho 5.

Từ Bài tập 2, ít nhất với mỗi $n$ lẻ từ dãy cơ sở theo Bổ đề 3 sẽ có một sự phân tách lời giải, tạo ra một dãy mới lời giải theo Bổ đề 2. Dễ dàng kiểm tra rằng lời giải thuộc các dãy khác nhau không trùng nhau.

Vì vậy, chỉ một chuỗi cơ sở cho mỗi $n > 2$ tạo ra ít nhất $\left[\frac{n-1}{2}\right]$ lời giải không chứa 1. Và giả thuyết rằng lời giải không có số 1 thì không quá “nhiều” (chính xác hơn là số lượng của chúng bị giới hạn bởi một hằng số, độc lập với $n$), “bị đập”. Sẽ hợp lệ nếu, bắt đầu từ một số $n$, tất cả lời giải thực tế chỉ thu được bằng cách áp dụng Bổ đề 2.

5. Một cách tiếp cận khác

Và tại sao tất cả? Vì lý do gì?
Và kết luận nào sau đây?

Eeyore

Tất nhiên, người được chọn không phải là người duy nhất. Một lá thư của độc giả A. N. Brotsky từ Knev gợi ý một cách tiếp cận khác: thay vì lấy lời giải bài toán cho $n = k + 1$ hoặc $n = k + 2$ từ lời giải bài toán cho $n = k$, hãy thử lấy những cái khác từ lời giải bài toán cho một số $n$ lời giải bài toán tương tự $n$. Brotsky đề xuất định lý sau:

Đặt $(x_1, \dots, x_{n-2}, x_{n-1}, x_n)$ là lời giải, thu được từ lời giải $(x_1, \dots, x_{n-2}, x_{n-1})$ và $\frac{f_{n-2}x_n + 1}{x_{n-1}} = d_1d_2$ theo Bổ đề 2.

Nếu hệ phương trình

$$\begin{cases} f_{n-2}x + 1 = d_1y, \\ f_{n-2}y + 1 = d_2x \end{cases}$$

chúng ta có lời giải trong số tự nhiên thì tập $(x_1, \dots, x_{n-2}, x, y)$ có thể là lời giải bài toán.

Thì 3. Chứng minh định lý Brotsky.

Sử dụng phương pháp của mình, A. N. Brotsky từ lời giải (2, 3, 7, 47, 395, 779 731) đã thu được lời giải (2, 3, 7, 47, 415, 8111), không được hình thành bằng cách áp dụng Bổ đề 3.

Căng thẳng 4. Kiểm tra xem với lời giải từ dãy cơ sở, hệ (8) luôn có lời giải ở số tự nhiên,

Căng thẳng 5. Kiểm tra xem liệu phương pháp của A. N. Brotsky, áp dụng cho dãy cơ sở, có cho lời giải mà không thu được khi sử dụng Bổ đề 2 và 3 hay không.

Chúng tôi chưa giải quyết được hoàn toàn vấn đề - chúng tôi không biết bao lâu lời giải có bài toán cho một (tùy ý) nhất định $n$. Nhưng chúng ta mới chỉ đi được vài bước và có thể còn phải mất nhiều thời gian nữa. Đây là của chúng tôi bài toán không có gì khác biệt so với những vấn đề mà các nhà toán học vĩ đại phải giải quyết. Quá trình tìm hiểu sự thật là vô tận. Nó thậm chí còn không kết thúc lời giải cách này hay cách khác bài toán, theo sau là những cái mới, tổng quát hơn, đòi hỏi lời giải suy nghĩ lại các phương pháp cũ và phát minh ra những phương pháp mới. Trong bài viết này, bạn đã thấy quá trình suy nghĩ lại diễn ra như thế nào và nhà nghiên cứu nên tuân theo những nguyên tắc nào.
