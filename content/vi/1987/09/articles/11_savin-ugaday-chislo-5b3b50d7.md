---
id: 1987-9-savin-ugaday-chislo-5b3b50d7
issue: kvant_1987_9
year: 1987
number: "9"
title: Đoán số
authors:
  - Савин А. П.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 36
page_last: 38
page_labels: 34-36
tag: SYOC
lang: vi
source: kvant_digital
extraction: vision
content_sha256: fbe0201d572f08f1fbfe118ce7bb9013976b79b46c42bdf8d37916c7c84ac115
prompt_sha256: draft-1
translated_from: content/ru/1987/09/articles/11_savin-ugaday-chislo-5b3b50d7.md
source_content_sha256: 2272daebffa6a406f2821361972699f1d515b22b42e32b73d95c31d626c8585e
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 34⟧

ĐOÁN SỐ

Bạn đã chơi trò chơi "Đoán Số" chưa? Bạn thậm chí chưa nghe nói? Đây là một trò chơi rất đơn giản. Giả sử tôi đoán một số tự nhiên, nhỏ hơn 100, bằng cách viết nó ra giấy (để không có khả năng gian lận) và bạn cố gắng đoán nó bằng cách đặt những câu hỏi chỉ có thể trả lời là “có” hoặc “không”. Sau đó, bạn đoán một con số, và tôi cố gắng đoán nó. Ai đoán được số câu hỏi cho mình sẽ thắng.

Bạn sẽ phải trả lời bao nhiêu câu hỏi để đoán được số của tôi? Bạn không biết? Bạn nói điều đó có thể ngay lập tức, hoặc có thể những câu hỏi này sẽ xuất hiện? Tôi cam kết đoán số của bạn chỉ trong bảy câu hỏi. Làm sao? Đây là cách làm, ví dụ. Hãy để bạn đoán một con số. Tôi hỏi: “Có khác gì 64 không?” - "Đúng." - “Dưới 32?” - "Đúng." - “Dưới 16?” - "Đúng." - “Ít hơn 8?” - "KHÔNG". - “Dưới 12?” - "KHÔNG". - “Dưới 14?” - "Đúng." - “Dưới 13?” - "KHÔNG". - “Số 13 đã được lên kế hoạch.”

Rõ ràng chứ? Tôi chia tập hợp các số có thể có làm đôi, sao cho nửa còn lại lại giảm đi một nửa, v.v., cho đến khi nửa còn lại chỉ chứa một số. Tại sao tôi lại bắt đầu bằng số 64 mà không phải số 50? Thông tin thêm về điều đó sau; Có thể bắt đầu từ số 50. Không khó để kiểm tra xem đối với các số thay đổi 64, sáu câu hỏi là đủ và trong bảy câu hỏi, bạn có thể đoán bất kỳ số nào không vượt quá 128.

34

⟦folio 35⟧

Xin chào, tôi đang xem bảng cheat này:

| màu xanh da trời | màu đỏ | đen | màu xanh lá |
| :--- | :--- | :--- | :--- |
| 1 | 0 | 1 | 2 |
| 2 | 0 | 4 | 8 |
| 3 | 0 | 16 | 32 |

Nếu bạn trả lời các câu hỏi, giả sử: “Blue, green, red”, tôi cộng ba số 0, 12, 16, đứng tại giao điểm của các cột và hàng tương ứng với các màu được đặt tên trong các bảng tương ứng. Kiểm tra xem số 28 có hợp lệ không và có các màu được đặt tên trong bảng (và chỉ có nó).

Bây giờ hãy tiết lộ bí mật của thủ thuật này. Ngay từ nhỏ chúng ta đã được dạy viết số trong hệ thập phân. Ví dụ: chúng tôi đã giải mã dãy số 1987 là $1 \cdot 10^3 + 9 \cdot 10^2 + 8 \cdot 10^1 + 7 \cdot 10^0$. Việc đếm được thực hiện theo số chục, mười đơn vị của một chữ số là đơn vị của chữ số tiếp theo. Nếu cơ số của hệ thống số được lấy là số 4 chứ không phải 10 thì sẽ chỉ xuất hiện 4 số: 0, 1, 2 và 3. Nhưng tại sao lại là số? Ví dụ: bạn có thể sử dụng các vòng tròn màu: © - cho số 0, ¶ - cho 1, ¶ - cho 2 và 3 - cho 3. Số 28 được viết trong hệ thống số tứ giác là $1 \cdot 4^2 + 3 \cdot 4^1 + 0 \cdot 4^0 = 130_4$ (bốn trong số 130 có nghĩa là nó được viết trong hệ thống số tứ giác). Và trong ký hiệu màu của chúng tôi, nó sẽ được viết là $\textcircled{3}$$\textcircled{3}$$\textcircled{3}$.

Nếu bạn đọc mục này từ phải sang trái, bạn sẽ nhận được “blue - green - red”. Chúng tôi gọi sự kết hợp màu sắc này khi hình thành số 28, chúng tôi đã báo cáo màu sắc của nó trong các bảng A, B, B!

Chúng ta hãy nhìn vào bảng của chúng tôi. Trong bảng A, màu của các số được di chuyển qua bốn theo cách này để xác định chữ số thứ hai trong bản ghi tứ giác của số và trong bảng B - chữ số thứ ba. Điều tương tự cũng được nói bởi “cipar-galka”, với sự trợ giúp của nó, chúng tôi đã xác định được số bằng màu sắc của nó trong bảng. (Chúng tôi đặt các số trong bảng A, B, B có kích thước $7 \times 9$ nhằm làm bạn bối rối một chút: nếu bạn sử dụng

⟦folio 36⟧

các bảng $A_1, B_1, B_1$ có kích thước $8 \times 8$, hệ thống có thể được phát hiện nhanh hơn nhiều.) Các bảng được biên soạn theo cách tương tự nhưng sử dụng 3 màu sẽ tương ứng với cách biểu diễn số trong hệ thống số ba; sử dụng 2 màu - nữ tính. Số 100 được viết như thế nào trong hệ thống số kép? Cái này
$$64 + 32 + 4 = 1 \cdot 2^6 + 1 \cdot 2^5 + 0 \cdot 2^4 + 0 \cdot 2^3 + 1 \cdot 2^2 + 0 \cdot 2^1 + 0 \cdot 2^0,$$
tức là $1100100_2$. Ta thấy các số thay đổi một trăm (sau đây đổi thành 128) được viết theo hệ số kép không quá bảy dấu. Hãy nhớ rằng tôi đã thực hiện bảy câu hỏi để đoán số 100 đang thay đổi!
Đối với số 13, chúng ta có chuỗi sau đáp số: có-có-có-không-không-không. Hãy viết số 13 trong hệ thống số kép và thêm ba số 0: 0001101$_2$. Mối liên hệ giữa chuỗi đáp số “có-không” và các số kết quả là gì? Tất nhiên, điều đó hoàn toàn đơn giản: đáp số “có” tương ứng với số 0 và đáp số “không” tương ứng với số 1.

Vì vậy, thay vì những câu hỏi “cỡ lớn” của tôi, người ta có thể trình bày bảy bảng với các số màu xanh và đỏ. Không biết bạn thế nào, nhưng phương pháp giảm một nửa hiệu quả hơn với tôi. Nhân tiện, nó được sử dụng khá thường xuyên trong thực tế. Giả sử tôi cần tìm bài toán Số 1372 trong nhiệm vụ. Tôi mở các trung gian của nó và xem một số số bài toán trên trang này. Nếu nó lớn hơn 1372, tôi chia nửa công việc đầu tiên và nhìn vào các con số ở đó; và nếu ít hơn thì tôi thực hiện thủ tục này với nửa còn lại. Số lượng trang có thể chứa bài toán này mỗi lần giảm đi một nửa và bạn sẽ nhanh chóng tìm thấy những gì mình đang tìm kiếm hai lần. Phương pháp này được gọi là "phân đôi" từ tiếng Hy Lạp "dikha" - thành hai phần - và phần "tom" -.

Nguyên tắc phân đôi cũng được đưa vào hệ thống Optimian để xác định nhà vô địch: đầu tiên, tất cả các phần được chia thành từng cặp và người mạnh nhất được xác định trong mỗi cặp, các chiến thắng tiếp theo - một nửa số phần - bị loại khỏi phần hoàn hảo và những người chiến thắng lại được chia thành các cặp, v.v. Cho đến khi chỉ dừng lại một cặp, trong cuộc họp xác định nhà vô địch. Hệ thống này hoàn hảo nếu số phần là lũy thừa của 2; thì trong mỗi krita hoàn hảo, tất cả các khu vực đều bị chiếm giữ, nhưng điều gì sẽ xảy ra nếu ở một số krita số khu vực là số lẻ? Sau đó, một trong các đội chuyển sang lần phê bình tiếp theo mà không tiếp tục với các lần phê bình khác. Điều tò mò là nếu một phần lớn hơn lũy thừa của hai, thì tình huống được mô tả sẽ xảy ra trong mọi crit hoàn hảo (ví dụ: với 9 hoặc 17 phần), và bạn cần đảm bảo rằng cùng một đội không trở thành “phụ” trong mỗi crit và do đó không lọt vào trận chung kết nếu không chơi một trận nào.

(Cuối cùng xem trang 50)
