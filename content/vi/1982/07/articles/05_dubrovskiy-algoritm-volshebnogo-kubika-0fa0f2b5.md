---
id: 1982-7-dubrovskiy-algoritm-volshebnogo-kubika-0fa0f2b5
issue: kvant_1982_7
year: 1982
number: "7"
title: Thuật toán khối ma thuật
authors:
  - Дубровский В. Н.
rubric: osnovnye-stati
page_first: 24
page_last: 25
page_labels: 22-23
tag: 6OPT
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 103a50bb8544c5af57b4bb9a045136cd948c0e1686875e01dfbd463568956fb7
prompt_sha256: draft-1
translated_from: content/ru/1982/07/articles/05_dubrovskiy-algoritm-volshebnogo-kubika-0fa0f2b5.md
source_content_sha256: db5ce15733a30c5ce7ab94d089269a634e6b0218c1bd065bec12b3225155fab0
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 22⟧

V. Dubrovsky

Thuật toán khối ma thuật

Không dễ để đối phó với “khối ma thuật Hungary” - câu đố phổ biến nhất thế kỷ 20. Vì vậy, những người thiếu kiên nhẫn, mất hy vọng thành công, thường ngừng làm quen với nó, nghiền nát nó thành từng mảnh. Người ta nói rằng sau khi "khối lập phương" xuất hiện ở Nhật Bản, tính tùy tiện trong lao động thậm chí còn giảm đi, và ở Mỹ món đồ chơi này hiện được bán kèm theo một chiếc rìu nhựa: nếu bạn không giải được thì hãy đập nó đi!
«Kvant» áp dụng cho khối Rubik có khả năng cao hơn và phía máy chủ, bằng chứng là bài viết được xuất bản dưới đây.

Trong bài viết này, chúng tôi sẽ hướng dẫn bạn cách giải khối lập phương - câu đố nổi tiếng của E. Rubik*). Nói đúng ra, chúng tôi không trình bày thuật toán lời giải (nghĩa là một bộ quy tắc chính xác để chuyển màu của tất cả các mặt từ tùy ý sang liên kết đơn) ở đây - thuật toán như vậy đã được xuất bản vào năm «Kvant» (1980, số 12, trang 17). Thay vào đó, chúng tôi đưa ra một danh sách lớn các kết hợp hữu ích, chỉ ra từng cách thực hiện (trình tự các lượt) và kết quả (các khối nhỏ nào được trình bày và cách trình bày). Trong số những cách kết hợp khác nhau dẫn đến cùng một kết quả, chúng tôi đã cố gắng chọn cách kết hợp ngắn nhất. Ở cuối bài viết, chúng tôi chỉ ra rằng một khối ma thuật có thể được đưa về trạng thái ban đầu (với các cạnh đơn) trong 79 lượt hoặc ít hơn.

*) Nếu bạn không có bản sao của khối lập phương, bạn có thể xây dựng nó bằng cách sử dụng hướng dẫn trong số liệu thống kê của M. Evgraf năm «Kvant» 1982, Số 3.

Chỉ định hoạt động

Hãy chỉ định từng mặt của khối ma thuật: F (phía trước), T (phía sau), B (trên cùng), H (dưới cùng), Π (phải), L (trái) (xem hình). Xoay mặt X theo chiều kim đồng hồ theo n · 90° sẽ được ký hiệu là X^n, ví dụ quay mặt phải 90°, 180°, 270° được viết là Π, Π^2, Π^{-1}=Π^3. Như vậy, mỗi thao tác (chuỗi quay các mặt) tương ứng với các “từ” từ các chữ cái F, T, B, H, Π, L với độ *), được đọc và thực hiện từ trái sang phải.

Chỉ định kết quả của hoạt động

Chúng ta sẽ viết ra bằng một công thức duy nhất cả chuyển động của những chiếc cốc nhỏ và sự thay đổi hướng của chúng trong không gian.

Để ghi lại chuyển động của các cốc nhỏ, chúng ta đánh số lại các khối góc và các đỉnh tương ứng với các số từ 1 đến 8, các đỉnh ở giữa (và các cạnh tương ứng) với các số từ 1 đến 12 (xem hình; bản ghi của tất cả các phép toán được xem xét trong thống kê tham khảo cách đánh số hiển thị trong hình này).

Giả sử rằng do kết quả của thao tác F, khối góc đầu tiên đã di chuyển đến vị trí của i_1, i_1 đến vị trí của i_2, v.v. Mỗi lần một số mới sẽ xuất hiện trong chuỗi này và một thời điểm chắc chắn sẽ đến khi

*) Một cách thú vị để ghi nhớ những “từ” như vậy được đưa ra trong bài “Khối Hungary” trên tạp chí “Khoa học và Đời sống”, số 3, 1981 (tr. 131).

⟦folio 23⟧

khối lập phương được đánh số $i_{n1}$ sẽ trở về vị trí của khối đầu tiên (tại sao?). Các khối 1, $i_1$, ..., $i_{n1}$ tạo thành một chu trình hoạt động $F$, ký hiệu là $(1i_1 \dots i_{n1})$. Nếu chưa phải tất cả các khối góc đều chưa bước vào chu kỳ này ($n_1 < 7$), thì hãy lấy bất kỳ khối nào còn lại (số trống $i_{n1+1}$) và lặp lại quy trình tương tự - chu kỳ thứ hai $(i_{n1+1} \dots i_{n2})$ sẽ xuất hiện. Cuối cùng, bản ghi các hình khối góc hóa ra bị phân hủy thành các chu trình độc lập (nghĩa là không có phần tử chung): $(1i_1 \dots i_{n1}) \cdot (i_{n1+1} \dots i_{n2})$.

Tình hình tương tự với các hình khối trung bình. Chúng ta sẽ viết các chu trình tương ứng trong ngoặc vuông; Vì vậy, ký hiệu [2 7 6] có nghĩa là phần thứ hai ở giữa và khối lập phương tiến tới phần thứ bảy, phần thứ bảy đến phần thứ sáu, phần thứ sáu đến phần thứ hai.

Giả sử, nhờ một số thao tác, khối ở giữa thứ $i$ thay thế cho khối thứ $j$. Nó có thể được định vị ở nơi này theo hai cách. Nếu hướng của mũi tên gắn vào cạnh của nó (xem Hình 1) hóa ra ngược với hướng mũi tên của khối thứ $j$, thì trong chu trình tương ứng, chúng ta đặt dấu trừ sau số $i$. Việc không có dấu hiệu có nghĩa là hướng của các mũi tên trùng nhau. Do đó, mục nhập $[2^{-7}+6^{-}]$ (hoặc $[2^{-7}6^{-}]$, chúng ta thường bỏ qua “dấu cộng” cho các khối ở giữa) có nghĩa là khối ở giữa thứ hai di chuyển vào khối thứ bảy với các mũi tên đối diện, khối thứ bảy vào khối thứ sáu với các mũi tên trùng nhau, khối thứ sáu vào khối thứ hai với các mũi tên ngược chiều. Mục nhập $[2^{-}]$ có nghĩa là khối ở giữa thứ hai vẫn giữ nguyên nhưng đã chuyển sang $180^{\circ}$.

Khối góc có thể được định vị ở một vị trí mới bằng cách cọ xát theo nhiều cách khác nhau. Theo đó, trong mục chu kỳ sau số khối này sẽ có dấu +, dấu - hoặc không ghi gì cả. dấu hiệu không được viết nếu mặt ngang của khối góc cho trước vẫn nằm ngang sau khi thực hiện thao tác. Nếu không, để đưa mặt này về vị trí nằm ngang ở một vị trí mới, chúng ta sẽ phải xoay khối lập phương quanh đường chéo một khoảng $120^{\circ}$. Nếu xoay ngược chiều kim đồng hồ thì đặt +, nếu theo chiều kim đồng hồ thì đặt -. Giả sử các mục $(5^{+})$, $(5)$, $(5^{-})$ có nghĩa là khối thứ năm vẫn giữ nguyên vị trí nhưng được xoay lần lượt theo $120^{\circ}$, $0^{\circ}$, $240^{\circ}$ theo chiều kim đồng hồ.

Giải thích về bảng (xem trang 24)

Khi ghi lại một thao tác, đầu tiên chúng ta sẽ viết một dãy các phép quay (một lớp chữ F, T, V, N, P, L kèm theo độ), sau đó là dấu ~, sau đó là kết quả, viết dưới dạng chu trình có dấu. Các ví dụ sẽ giúp bạn nắm vững hệ thống ghi âm này; kiểm tra xem $\Pi \sim (1^{+2}-3^{+4})$ [1234], $B^{-} \sim (1276)$ [2$-9-8-7^{-}]$,$\Phi^{2} \sim (15)$ (46) [16] [57], $\Pi\Phi \sim (1^{+2}-3^{-5}-6^{+})$ (4+) [1234567], $\Pi^{2}\Phi^{2} \sim (135)$ (264) [136] [24] [57].

Bảng này liệt kê 47 phép toán được tìm thấy trong trò chơi khối lập phương, đôi khi bằng cách thử và sai, nhưng chủ yếu là nhờ sự trợ giúp của một số phép tính đại số khá thú vị mà việc thiếu không gian không cho phép tái hiện ở đây. Các hoạt động $C_{15}$ và $C_{19}$ được lấy từ “Tạp chí Trường Trung học Hungary”, $C_{18}$ - từ bài viết nêu trên trong “Khoa học và Cuộc sống”.

Sơ đồ thuật toán

Giai đoạn đầu tiên: lắp ráp “cột” $2 \times 2 \times 3$. Chúng ta hãy tạo một “cột” tập hợp tất cả các khối nhỏ không nằm ở hai mặt liền kề của một khối lớn để xác định F và P. Để sắp xếp chính xác tất cả các khối trong một “cột”, không cần thủ thuật đặc biệt nào. Ví dụ: chúng ta hãy đưa ra các thao tác trong đó khối ở giữa thứ nhất di chuyển đến vị trí thứ 8 và trong một trường hợp được giữ nguyên, còn trường hợp kia thay đổi góc quay của nó, với tất cả các khối của “cột”, tất nhiên, ngoại trừ khối thứ 8, vẫn còn nguyên: $A_1 = \Pi TB^2 T^{-1}$, $A_2 = \Phi^{-1} TB T^{-1}$. Giai đoạn này có thể được hoàn thành trong khoảng 25 bước.

Giai đoạn thứ hai: mở rộng các khối ở giữa ở các mặt F và P. Dễ dàng chứng minh rằng với bất kỳ dãy lần lượt nào, số khối ở giữa có hướng mũi tên không trùng với hướng “đúng” (như trong hình) luôn là
