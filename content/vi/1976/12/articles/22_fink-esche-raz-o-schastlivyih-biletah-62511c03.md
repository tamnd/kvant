---
id: 1976-12-fink-esche-raz-o-schastlivyih-biletah-62511c03
issue: kvant_1976_12
year: 1976
number: "12"
title: Một lần nữa về tấm vé may mắn
authors:
  - Финк Л. М.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 70
page_last: 72
page_labels: 68-70
tag: XMDA
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 52756edb964341cafa602f3581f20773f41213c23cbb059e4c53543b2348fc14
prompt_sha256: draft-1
translated_from: content/ru/1976/12/articles/22_fink-esche-raz-o-schastlivyih-biletah-62511c03.md
source_content_sha256: 8a940217e4568c7566f48dba402cb83074dbe860fcdbada4b429a4a9e8a67541
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 68⟧

L. Fink

Một lần nữa về tấm vé may mắn

Hôm qua, cháu trai Misha của tôi chạy đến chỗ tôi và kêu lên: “Chú ơi, cháu nghĩ cháu đã quyết định rồi!”
- Cậu đã quyết định thế nào?
— Bài toán về tấm vé may mắn. Bạn có nhớ có lần trên xe điện, bạn và tôi cùng đếm xem có bao nhiêu tấm vé xe điện “may mắn” mà tổng của ba chữ số đầu bằng tổng của ba chữ số cuối?
- Tất nhiên là tôi nhớ. Cuộc trò chuyện này của chúng tôi thậm chí còn được xuất bản trên «Kvant» (xem số 7, 1975, trang 67-70). Vì vậy, bạn đã tìm thấy chính xác số lượng vé may mắn mà không cần sử dụng phương pháp vũ phu?
- Hầu hết.
– Ý cậu “gần như” là sao? Con số gần đúng?
- Không, con số chính xác. Nhưng tôi vẫn sử dụng phương pháp vũ phu. Đúng, tôi không nhìn vào một triệu số có sáu chữ số, mà ít hơn một nghìn lần.
- Hãy nói cho tôi biết bạn làm thế nào.
— Tôi đã tính xem có bao nhiêu vé may mắn có tổng của ba chữ số đầu và cuối bằng một số nhất định, ví dụ: $k$. Chúng ta hãy biểu thị số lượng ba giá trị của các số có tổng các chữ số bằng $k$ bằng $N(k)$. Để nhận được tấm vé may mắn có tổng của ba chữ số đầu và ba chữ số cuối bằng $k$, bạn có thể chọn bất kỳ số có ba chữ số nào trong số $N(k)$ này cho nửa bên trái của số vé và bất kỳ số nào khác (hoặc giống nhau) cho nửa bên phải. Ví dụ: với tổng các chữ số $k = 1$ có ba số có ba chữ số: 001, 010 và 100. Kết hợp chúng lại ta được 9 số vé may mắn có sáu chữ số:

$$\begin{array}{ccc}
001001 & 001010 & 001100 \\
010001 & 010010 & 010100 \\
100001 & 100010 & 100100
\end{array}$$

Trong trường hợp chung, vé may mắn có tổng các chữ số bằng $k$ trong mỗi “nửa” sẽ là $[N(k)]^2$. Giá trị nhỏ nhất có thể có của $k$ là 0 (đối với số 000) và cao nhất là 27 (đối với số 999). Bằng cách tổng hợp giá trị của $[N(k)]^2$ với $k$ từ 0 đến 27, chúng ta sẽ có được số lượng vé may mắn có thể có. Làm xong việc này tôi tìm thấy đáp số - số vé may mắn $C = 55252$. Tức là trung bình cứ 18 tấm vé thì có một tấm là may mắn.

Misha vui mừng như thể xé được nhiều tấm vé may mắn cùng một lúc.

“Chúc mừng quyết định của anh,” tôi nói. — Nhưng tôi không rõ bạn xác định giá trị của $N(k)$ bằng cách nào.

- Rất đơn giản. Tôi viết ra một nghìn số có ba chữ số từ 000 đến 999 và tính tổng các chữ số của mỗi số đó. “Tôi đã quản lý nó mà không cần bất kỳ máy tính nào - chỉ trong một ngày Chủ nhật,” Misha tự hào trả lời.

- Làm ơn, sẽ hữu ích hơn nếu hiểu công thức hoặc quy tắc cho phép bạn tìm $N(k)$ mà không cần dùng đến vũ lực.
- Con đã cố rồi chú ạ, lời thật lòng đấy! Nhưng không có gì hiệu quả.

- Chúng ta cùng cố gắng nhé. Đầu tiên, bạn cần thay đổi ký hiệu: thay vì $N(k)$ nó sẽ được viết $N_3(k)$.

— Thị thực ba lần này có ý nghĩa gì?

⟦folio 69⟧

Rằng chúng ta sẽ xem xét các số có ba chữ số.
Nhưng điều này đã rõ ràng rồi!
Đó không phải là vấn đề. Chúng ta sẽ tổng quát hóa bài toán và tìm $N_n(k)$, số các số có $n$ chữ số có tổng các chữ số bằng $k$.
Bạn ơi, mình không giải được bài toán cho số có ba chữ số, nhưng bạn muốn giải cho cả số có bốn chữ số và năm chữ số... Rốt cuộc thì khó hơn nhiều!
Tất nhiên, sẽ khó khăn hơn nếu bạn sử dụng vũ lực. Nhưng sẽ dễ dàng hơn nếu bạn suy nghĩ logic. Nhân tiện, trong lịch sử toán học có rất nhiều bài toán đã biết, chỉ được giải sau khi chúng được hình thành ở dạng tổng quát. Trước tiên hãy thử tìm $N_1(k)$.
Tôi sẽ nghĩ về nó bây giờ. Chúng ta cần xác định tổng các chữ số $k$ có bao nhiêu số có một chữ số. Nhưng đối với số có một chữ số thì tổng các chữ số bằng chính số đó. Không có gì để quyết định ở đây. Có một số có một chữ số có tổng các chữ số bằng 0 - đây là 0; một số có một chữ số có tổng các chữ số bằng một là 1, một số có tổng các chữ số bằng hai là 2, v.v. Vậy $N_1(k) = 1$ nếu $k$ nhận các giá trị từ 0 đến 9 và đối với các giá trị khác $k - N_1(k) = 0$.
Tuyệt vời! Hãy tiếp tục. Bây giờ chúng ta giả sử rằng chúng ta đã biết các giá trị của $N_{n-1}(k)$ cho tất cả $k$. Hãy thử thể hiện $N_n(k)$ thông qua chúng. Nói cách khác, chúng ta hãy thử tìm số các số có $n$ chữ số có tổng các chữ số bằng $k$, giả sử rằng đối với các số có $(n-1)$ chữ số bài toán đã được giải.
“Tôi hiểu rồi,” Misha trả lời. Chúng ta đã biết ý nghĩa của $N_1(k)$; nên chúng ta chỉ cần tìm cách chuyển từ $n-1$ sang $n$. Sau đó, chúng ta có thể xác định tuần tự các giá trị của $N_2(k)$, $N_3(k)$, v.v. Hãy thử xem. Gọi chữ số đầu tiên của số có $n$ chữ số là số $l$. Để tổng các chữ số của số này bằng $k$ thì tổng các chữ số còn lại phải bằng $k-l$. Có $N_{n-1}(k) - l$ số có $(n-1)$ chữ số như vậy. Chữ số $l$ có thể là bất kỳ số nguyên có một chữ số nào không vượt quá $k$ (tức là $0 \leqslant l \leqslant 9$, $l \leqslant k$) và mỗi chữ số này tương ứng với các số có $N_{n-1}(k-l)$ $n$ chữ số có tổng các chữ số bằng $k$, tất cả các chữ số này đều khác nhau. Điều này có nghĩa là sẽ có tổng số số như vậy
$N_n(k) = N_{n-1}(k) + N_{n-1}(k-1) + N_{n-1}(k-2) + N_{n-1}(k-3) + N_{n-1}(k-4) + N_{n-1}(k-5) + N_{n-1}(k-6) + N_{n-1}(k-7) + N_{n-1}(k-8) + N_{n-1}(k-9)$; (*) hơn nữa, nếu $k < 9$ thì với $l > k$ giá trị tương ứng $N_{n-1}(k-l)$ ta sẽ coi bằng 0.
Sử dụng công thức (*), bạn có thể tính các giá trị của $N_n(k)$ cho tất cả $k$ nếu biết các giá trị của $N_{n-1}(k)$. Và vì chúng ta đã biết các giá trị của $N_1(k)$, nên bài toán đã được giải quyết!
Hoàn toàn đúng,” tôi nói. Các công thức tương tự như công thức (*) được gọi là *recurrent*. Tất nhiên, để tính tất cả các giá trị của $N_3(k)$ bằng công thức (*), sẽ mất 10-15 phút, nhưng không phải cả ngày. Nhưng vấn đề không phải là kịp thời mà là để có được lời giải đều đặn, không đầy đủ. Sử dụng công thức kết quả, bạn có thể tính số lượng vé may mắn không chỉ cho xe điện của chúng tôi mà còn cho cả xe điện với Các số có tám chữ số, mười chữ số và thường là 2$n$ chữ số. Tôi nhớ mình đã đọc trong một cuốn tiểu thuyết khoa học viễn tưởng rằng trong các hiệu sách ô tô của hành tinh chính của hệ $\alpha$ Centauri, các số có tám chữ số được sử dụng để mua vé. Hãy cùng tìm hiểu xem cư dân trên hành tinh này có nhận được vé may mắn thường xuyên hơn chúng ta không?
Misha lấy một tờ giấy và bắt đầu vẽ một cái bàn. Trước hết, anh ấy điền vào cột cho $n=1$ bằng các cột cho $k$ nằm trong khoảng từ 0 đến 9. Các ô còn lại của cột này có thể chứa đầy số 0, nhưng anh ấy quyết định không viết chúng. Misha lấy cột cho $n=2$ bằng cách sử dụng công thức truy hồi (*), cộng các giá trị tương ứng $N_1(k)$, $N_1(k-1)$, ..., $N_1(0)$

⟦folio 70⟧

Có, $N_2(6) = N_1(6) + N_1(5) + N_1(4) + N_1(3) + N_1(2) + N_1(1) + N_1(0) = 7$. Các cột cho $n = 3$ và $n = 4$ sau đó được xây dựng bằng cách sử dụng cùng một công thức.

Bảng giá trị $N_n(k)$

| $k$ | 1 | 2 | 3 | 4 |
| :--- | :--- | :--- | :--- | :--- |
| 0 | 1 | 1 | 1 | 1 |
| 1 | 1 | 2 | 3 | 4 |
| 2 | 1 | 3 | 6 | 10 |
| 3 | 1 | 4 | 10 | 20 |
| 4 | 1 | 5. | 15 | 35 |
| 5 | 1 | 6 | 21 | 56 |
| 6 | 1 | 7 | 28 | 84 |
| 7 | 1 | 8 | 36 | 120 |
| 8 | 1 | 9 | 45 | 165 |
| 9 | 1 | 10 | 55 | 220 |
| 10 | | 9 | 63 | 282 |
| 11 | | 8 | 69 | 348 |
| 12 | | 7 | 73 | 415 |
| 13 | | 6 | 75 | 480 |
| 14 | | 5 | 75 | 540 |
| 15 | | 4 | 73 | 592 |
| 16 | | 3 | 69 | 633 |
| 17 | | 2 | 63 | 660 |
| 18 | | 1 | 55 | 670 |
| 19 | | | 45 | 660 |
| 20 | | | 36 | 633 |
| 21 | | | 28 | 592 |
| 22 | | | 21 | 540 |
| 23 | | | 15 | 480 |
| 24 | | | 10 | 415 |
| 25 | | | 6 | 348 |
| 26 | | | 3 | 282 |
| 27 | | | 1 | 220 |
| 28 | | | | 165 |
| 29 | | | | 120 |
| 30 | | | | 84 |
| 31 | | | | 56 |
| 32 | | | | 35 |
| 33 | | | | 20 |
| 34 | | | | 10 |
| 35 | | | | 4 |
| 36 | | | | 1 |

Làm xong việc này, Misha nhận được:
đối với số có hai chữ số $C = 10$,
cho bốn chữ số $C = 670$,
đối với các ký tự có sáu chữ số $C = 55252$,
để gợi nhớ $C = 4840030$.

“Như vậy,” Misha tóm tắt, “trên hành tinh của hệ thống α Centauri, cứ 100 triệu vé thì có hơn 4,8 triệu vé hạnh phúc một chút.” Trung bình có khoảng một vé may mắn trong số 21 vé chứ không phải trên 18 vé như của chúng tôi. Họ khó hơn chúng ta để thêm “hạnh phúc” cho chính họ.

“Bây giờ,” tôi nói, “chúng ta có thể coi như câu hỏi bài toán đã được giải quyết.”

- Có cách nào khác để lời giải cô ấy không? - Misha hỏi.

- Có lẽ là có. Biết đâu độc giả «Kvant» sẽ nghĩ ra và chia sẻ với chúng tôi? Không cần thiết phải tìm chính xác số lượng vé may mắn; bạn có thể giới hạn bản thân ở một ước tính hoặc một công thức gần đúng; những ước tính này cung cấp một sai số tương đối nhỏ. Ví dụ: đây là một công thức đơn giản biểu thị số lượng vé $2n$-may mắn cho bất kỳ $n$ nào với sai số tương đối không quá 4%:

$$C \approx 10^{2n} / \sqrt{33n\pi}.$$

Khi $n$ tăng, sai số tương đối giảm nhanh.

- Làm sao chú có được công thức này vậy chú?

- Bây giờ thật khó để giải thích. Tôi đã sử dụng phương pháp lý thuyết xác suất; Tôi thấy rằng sau một vài năm bạn đã quen với lý thuyết này.

“Bây giờ,” Misha nói sau khi kết thúc bàn, “bạn có thể tính số vé may mắn với hai giá trị, bốn chữ số, sáu chữ số và số nhớ lại.” Để làm điều này, các số trong cột thứ $n$ của bảng của tôi cần phải được bình phương và cộng lại.
