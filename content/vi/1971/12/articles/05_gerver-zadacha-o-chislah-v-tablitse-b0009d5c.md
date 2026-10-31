---
id: 1971-12-gerver-zadacha-o-chislah-v-tablitse-b0009d5c
issue: kvant_1971_12
year: 1971
number: "12"
title: Bài toán về các số trong bảng
authors:
  - Гервер М. Л.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 26
page_last: 28
page_labels: 24-26
tag: 551W
lang: vi
source: kvant_digital
extraction: vision
content_sha256: e6a00e941fa6e768d2b029f7ec5abdc5933c1524a9072d92a0cffee62daf28ca
prompt_sha256: draft-1
translated_from: content/ru/1971/12/articles/05_gerver-zadacha-o-chislah-v-tablitse-b0009d5c.md
source_content_sha256: d00ac8e132264ce4b1b8f10d31a604c1646e78980d5dc6a2e5e74325cc4b5d3a
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 24⟧

Thắc mắc về số trong bảng

M. L. Gerver

Trong «Kvant» số 7 năm 1971 ở trang 21, bài toán sau đây đã được hình thành.

Trong bảng vuông $6 \times 6$ các số 1, 2, 3, ..., 36 được xét tùy ý. Chứng minh rằng có hai số trung bình a và b đứng trong các ô liền kề và a—b $\geq 5$.

Vài năm trước, một bài toán tương tự đã được đề xuất tại Olympic Toán học Moscow: để chứng minh rằng trong bảng $9 \times 9$ chứa đầy các số cực, có hai số liền kề có hiệu lớn hơn hoặc bằng 6.

Dưới đây chúng ta sẽ giải tổng quát bài toán cho bảng $n \times n$ và thu được ước tính chính xác (không thể cải thiện) về chênh lệch tối đa giữa các số lân cận.

Công thức bài toán

Trong bảng $n \times n$ các số 1, 2, ..., $n^2$ được xét tùy ý. Chứng minh rằng có hai số liền kề có hiệu không nhỏ hơn n.

Giải thích. Chúng ta hãy làm rõ thuật ngữ “các số lân cận”. Chúng ta gọi hai số là liền kề nếu các ô trong bảng chứa chúng có cạnh chung.

Nhận xét sơ bộ

Dễ dàng xét các số 1, ..., $n^2$ trong bảng $n \times n$ sao cho hiệu của hai số liền kề bất kỳ không vượt quá 了她. Ví dụ về sự sắp xếp như vậy tại $n=5$ được đưa ra trong Bảng 1 và 2.

Từ Bảng 1, có thể (bằng cách sắp xếp lại các cột) thu được 119 = 5!—1 bảng khác trong đó không có sự khác biệt giữa các số liền kề

Bảng 1.

1 2 3 4 5

6 7 8 9 10

11 12 13 14 15

16 17 18 19 20

21 22 23 24 25

Bảng 2.

1 3 6 10 15

2 5 9 14 19

4 8 13 18 22

7 12 17 21 24

11 16 20 23 25

tăng dần 5. Trong bảng 2, không tăng chênh lệch tối đa giữa các số liền kề, bạn có thể sắp xếp lại các số nằm xa đường chéo đi từ góc dưới bên trái lên góc trên bên phải của bảng; ví dụ: bạn có thể hoán đổi 1 và 2 hoặc 23 và 24, v.v. Các ví dụ hoàn toàn tương tự có thể được xây dựng cho bất kỳ n nào.

Có nhiều cách xét các số 1,..., $n^2$ trong bảng $n \times n$ sao cho chênh lệch lớn nhất giữa các số liền kề là n. Anh ta hỏi, có thể xét các số sao cho chênh lệch lớn nhất nhỏ hơn n không?

Hóa ra điều này không thể thực hiện được - đây chính xác là điều chúng ta sắp chứng minh.

⟦folio 25⟧

Lời giải bài toán cho $n=4$

Ý tưởng làm cơ sở cho lời giải đặc biệt dễ diễn đạt bằng $n$ nhỏ. Hãy lấy bảng $4 \times 4$, chọn 4 ô trong đó chứa các số 1, 2, 3 và 4. Hãy đặt dấu hoa thị vào các ô còn lại của bảng liền kề với các ô đã chọn (Bảng 3). Lưu ý rằng ngay cả khi các ô được chọn nằm ở cạnh hoặc góc của bảng, sẽ không có ít hơn bốn ngôi sao (bạn hãy tự kiểm tra điều này). Bây giờ, cho dù chúng ta sắp xếp các số 5, 6, ..., 16 trong bảng như thế nào thì một trong các ô có dấu hoa thị sẽ chứa số $a$, lớn hơn hoặc bằng 8 (vì có ít nhất 4 dấu hoa thị và chỉ còn lại ba số nhỏ hơn 8: 5, 6 và 7). Ô này liền kề với ít nhất một trong các ô chứa các số 1, 2, 3 và 4. Vì vậy, số $a \geq 8$ liền kề với một số $b \leq 4$ nào đó. Vì vậy $a-b \geq 4$.

Chúng tôi đã chứng minh rằng với mọi cách sắp xếp các số 1, 2, 3, 4, ..., 16 trong bảng, $4 \times 4$ sẽ tìm thấy hai số lân cận $a$ và $b$ sao cho $a-b \geq 4$.

Tiếp theo là gì?

Những điều trên có thể dẫn đến kết luận cuối cùng sau đây.

Chúng ta hãy chọn các ô trong bảng $n \times n$ chứa các số 1, 2, ..., $n$. Hãy đặt các ngôi sao vào các ô còn lại liền kề với các ô đã chọn. Hãy cho họ $n$ một số ngôi sao. Vì vậy, dù bạn xếp các số $n+1$, ..., $n^2$ vào bảng như thế nào thì cũng sẽ có một số $a \geq 2n$ rơi vào ô có dấu hoa thị và hóa ra là liền kề với một số $b \leq n$ nào đó. Hiệu của các số $a-b$ rõ ràng là lớn hơn hoặc bằng $n$.

Trong cách lập luận trên có một lỗi: câu in nghiêng là sai. Đối với $n=5$ đã sai rồi: nếu chúng ta sắp xếp các số 1, ..., $n^2$. Sau đó, có một số $m$ ($1 < m < n^2$), có tính chất sau: nếu chúng ta đánh dấu các ô chuột mà chuột ở cạnh hoặc góc bàn thì sẽ có không dưới bốn sao (bạn tự kiểm tra cái này). Bây giờ, cho dù chúng ta sắp xếp các số 5, 6, ..., 16 trong bảng như thế nào thì một trong các ô có dấu hoa thị sẽ chứa số $a$, lớn hơn hoặc bằng 8 (vì có ít nhất 4 dấu hoa thị và chỉ còn lại ba số nhỏ hơn 8: 5, 6 và 7). Ô này liền kề với ít nhất một trong các ô chứa các số 1, 2, 3 và 4. Vì vậy, số $a \geq 8$ liền kề với một số $b \leq 4$ nào đó. Vì vậy $a-b \geq 4$.

Bổ đề. Hãy sắp xếp các số 1, ..., $n^2$ trong bảng $n \times n$. Sau đó, có một số $m$ ($1 < m < n^2$), có tính chất sau: nếu chúng ta đánh dấu các ô chuột mà chuột ở cạnh hoặc góc bàn thì sẽ có không dưới bốn sao (bạn tự kiểm tra cái này). Bây giờ, cho dù chúng ta sắp xếp các số 5, 6, ..., 16 trong bảng như thế nào thì một trong các ô có dấu hoa thị sẽ chứa số $a$, lớn hơn hoặc bằng 8 (vì có ít nhất 4 dấu hoa thị và chỉ còn lại ba số nhỏ hơn 8: 5, 6 và 7). Ô này là 相邻 trong bảng số 1, ..., $n^2$, có số $a \geq 2n$ rơi vào ô có dấu hoa thị và hóa ra lại liền kề với số $b \leq n$ nào đó. Sự khác biệt của các số $a-b$ rõ ràng là lớn hơn hoặc bằng $n$.

1 trường hợp. Mỗi cột chứa một số không vượt quá $k-1$, nhưng có một hàng không chứa bất kỳ số nào trong số 1, ..., $k-1$.

⟦folio 26⟧

Bảng 5.

| 1 | 2 | 3 | 4 | 5 |
| :---: | :---: | :---: | :---: | :---: |
| 6 | 7 | 8 | 9 | 10 |
| 11 | 12 | 13 | 14 | 15 |
| 16 | 17 | 81 | 19 | 20 |

Bảng 6.

| 1 | 2 | 4 | 6 | 8 |
| :---: | :---: | :---: | :---: | :---: |
| 3 | * | * | * | * |
| 5 | * | | | |
| 7 | * | | | |

Trong trường hợp này, chúng tôi đặt $m=k-1$ (ví dụ: $m=20$ trong Bảng 1 và $m=8$ trong Bảng 4).

Hãy chứng minh rằng $m$ thỏa mãn yêu cầu của bổ đề.

Hãy đánh dấu các ô chứa các số 1, ..., $m=k-1$ và đặt dấu hoa thị vào các ô còn lại liền kề với các ô đã đánh dấu (Bảng 5, 6).

Mỗi cột chứa các hộp kiểm. Ngoài ra, mỗi cột có ít nhất một ô không được đánh dấu (vì toàn bộ hàng không chứa các ô được đánh dấu). Vì vậy, có ít nhất một dấu hoa thị trong mỗi cột. Tất cả các cột $n$; điều này có nghĩa là dấu hoa thị ít nhất là $n$.

Psluay. Mỗi dòng chứa một số không vượt quá $k-1$, nhưng có một dòng không chứa bất kỳ số nào trong số 1, ..., $k-1$.

Trường hợp này sẽ trùng với trường hợp đã được thảo luận: chỉ cần phản chiếu bảng so với đường chéo chính là đủ (thao tác này được gọi là *vẽ*).
