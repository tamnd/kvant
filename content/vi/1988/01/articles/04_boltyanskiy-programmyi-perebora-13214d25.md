---
id: 1988-1-boltyanskiy-programmyi-perebora-13214d25
issue: kvant_1988_1
year: 1988
number: "1"
title: Tìm kiếm chương trình
authors:
  - Болтянский В. Г.
rubric: osnovnye-stati
page_first: 5
page_last: 8
page_labels: 3-6
tag: UDLQ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 66aeadad29cb9d7b52a6d3861e80a394fae51e5f2a75737d67e03e390940751b
prompt_sha256: draft-1
translated_from: content/ru/1988/01/articles/04_boltyanskiy-programmyi-perebora-13214d25.md
source_content_sha256: 3ec641f87cfad729db71685a86aa6b3311d108f91e6024747f23be6896455d44
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 3⟧

CHƯƠNG TRÌNH TÌM KIẾM

Thành viên tương ứng của Viện Hàn lâm Khoa học Sư phạm Liên Xô
V. G. VOLTYANSKY

Chẳng phải đầu máy hơi nước “chạy” tốt hơn con người - ít nhất là nhanh hơn? Và nếu bạn cần đến một thành phố khác, bạn sẽ rất vui khi nhờ đến sự giúp đỡ của anh ấy. Một người có rất nhiều sự giúp đỡ khác. Robot mang các bộ phận nặng đến nơi xử lý, liên lạc giúp truyền tải thông tin, đồng hồ đáp số cho câu hỏi “mấy giờ rồi?” vân vân.

Và có những trợ lý mới xuất hiện tương đối gần đây, được trang bị hoạt động trí tuệ của con người. Đây là những máy tính. Họ không chỉ có thể nhanh chóng thực hiện các phép tính mà còn có thể xử lý các nhiệm vụ khi nghĩ về việc một người tìm kiếm thông qua các tùy chọn, tìm kiếm đường dẫn lời giải và thực hiện các phép toán logic. Tất nhiên, máy tính không “suy nghĩ” giống như con người theo nghĩa đen (xét cho cùng, đầu máy hơi nước “chạy” theo cách riêng của nó chứ không đi như chúng ta). Mặc dù máy tính ngoan ngoãn thực hiện các hoạt động “tinh thần” theo chương trình do con người biên soạn trước nhưng nhờ tốc độ khủng khiếp nên nó xử lý được nhiều tác vụ nhanh hơn con người rất nhiều. Và không chỉ với các nhiệm vụ tính toán, mà còn với những nhiệm vụ lời giải mà bạn phải suy nghĩ và vắt óc. Hãy xem một ví dụ.

Bài toán 1. Có bao nhiêu số có hai chữ số có tổng bình phương các chữ số chia hết cho 13?

Tất nhiên, đối với lời giải bạn có thể thực hiện một tìm kiếm “ngớ ngẩn”: không có nhiều số có hai chữ số và nếu bạn tìm kiếm một số khác và kiểm tra xem tổng bình phương của các chữ số chia hết cho 13, thì chúng ta có thể tìm thấy đáp số. Tuy nhiên nó dài và nhàm chán. Và chúng tôi sử dụng lý luận logic để có được lời giải dễ dàng và đẹp mắt hơn. Để làm điều này, hãy tạo bảng sau:

| con số | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| hình vuông của nó | 0 | 1 | 4 | 9 | 16 | 25 | 36 | 49 | 64 | 81 |
| phần còn lại | 0 | 1 | 4 | 9 | 3 | 12 | 10 | 10 | 12 | 3 |

Dòng dưới chứa số dư khi chia các số ở dòng thứ hai cho 13. Bạn cần chọn hai số có tổng bình phương chia hết cho 13, tức là hai số ở dòng trên mà tổng các số tương ứng ở dòng dưới là 13. Ví dụ: bạn có thể lấy số 1 và 5 (lấy dòng dưới là 1 và 12); ta được hai số có hai chữ số 15 và 51 thỏa mãn điều kiện. Bạn cũng có thể lấy các số 1 và 8 (trong đó 1 và 12 cũng được ký tên) - điều này mang lại thêm hai số bắt buộc (18 và 81). Một tổ hợp số khác là 2 và 3 (nâng số 4 và 9 đã viết lên), sẽ có thêm hai số (23 và 32). Cuối cùng, bạn có thể kết hợp một trong các số viết số 3 với số viết số 10. Tổng cộng, chúng tôi nhận được 14 số cần thiết:

15 và 51, 18 và 81, 23 và 32, 46 và 64, 47 và 74, 69 và 96, 79 và 97.

Mặc dù ở đây cần phải suy nghĩ một chút và cho biết cách tìm các đường dẫn lời giải, nhưng, tất nhiên, lời giải như vậy vẫn tốt hơn là một tìm kiếm “ngu ngốc”.

Điều gì sẽ xảy ra nếu chúng ta, giống như một chiếc máy tính, có thể thực hiện hàng trăm nghìn, thậm chí hàng triệu thao tác mỗi giây? Trong trường hợp này có nên thử tìm đường đi lời giải không? Chẳng phải các số từ 10 đến 99 sẽ được xử lý nhanh chóng như vậy sao? Rõ ràng là nó đã trôi qua!

Chúng ta hãy xem xét trước 1 cách giải quyết các tìm kiếm bài toán bằng máy tính. Chúng tôi sẽ trình bày chương trình bằng một ngôn ngữ lập trình rất phổ biến và được sử dụng phổ biến.

⟦folio 4⟧

học BASIC (xem SGK tin học lớp 10, tr. 71). Nhưng trước tiên chúng tôi đưa ra mô tả về hàm INT có trong BASIC. Đây là một mục ví dụ:

A=INT(56/13)

Nghĩa là biến A được gán giá trị bằng toàn bộ phần của phân số 56/13 (từ tiếng Anh `integer` - toàn bộ). Vì 56/13==4.30769... nên chúng ta sẽ có A=4.

Bây giờ chúng tôi trình bày chương trình *) lời giải bài toán 1:

```basic
FOR N=10 TO 99
A=INT(N/10)
B=N-10*A
S=A*A+B*B
R=S-13*INT(S/13)
IF R=0 THEN PRINT N;
NEXT N
END
```

Bình luận. Các dòng của chương trình bị bỏ qua, không phải liên tiếp mà sau 10 số. Ví dụ này rất thuận tiện: nếu trong quá trình viết chương trình, bạn phát hiện ra rằng mình đã bỏ lỡ bất kỳ thao tác nào cần thiết cho lời giải, thì chúng có thể được viết ra dưới dạng các dòng có số trung gian.

Dòng 10 chứa một toán tử vòng lặp, được thiết kế đặc biệt để liệt kê tất cả các số tự nhiên từ 10 đến 99 (nghĩa là cả hai số) và mỗi số đó thực hiện hoạt động được chỉ định trong các dòng tiếp theo. Dòng 70 là kết thúc hoạt động được thực hiện với số có chữ số tiếp theo, tức là lệnh chuyển sang số tiếp theo.

Bây giờ chúng ta hãy xem các dòng trung gian 20-60, mô tả hoạt động được thực hiện với số N. Dòng 20 chứa hàm INT tích hợp đã được đề cập ở trên. Như vậy, biến A được gán giá trị bằng phần nguyên của số N/10, tức là A là một chữ số

*) Các chương trình trong bài viết này được viết bằng BASIC MSX.

⟦folio 5⟧

4. Bình phương của một số có ba chữ số được bao quanh bởi ba chữ số tạo thành số chính xác. Tìm tất cả các số như vậy.

5. Tìm một số có bốn chữ số, biết chia cho 133 dư 125, chia cho 134 dư 111.

6. Khâu ba chữ số như vậy ở bên phải thành 523*** sao cho số có sáu chữ số chia hết cho 7, 8 và 9.

7. Khâu ba số bên phải vào ***999 sao cho số có sáu chữ số chia hết cho 13, 17 và 19.

Bây giờ chúng ta hãy xem xét một bài toán, lời giải khác cho phép chúng ta liên kết với các kỹ thuật lập trình tiếp theo bằng ngôn ngữ BASIC.

Bài toán 8. Người mắc nợ (tức là cả một người đã hơn trăm tuổi) nói rằng nếu cộng số ngày sinh của anh ta (tức là một trong các số từ 1 đến 31) vào tổng bình phương các chữ số của tuổi anh ta thì sẽ được tuổi. Nó nên bao nhiêu tuổi?

Đây là chương trình dành cho lời giải này bài toán:

```
FOR K=1 TO 9
FOR L=0 TO 9
FOR M=0 TO 9
N=100*K+10*L+M
S=K*K+L*L+M*M
IF N<S+1 GO TO 90
IF N<S+32 THEN PRINT N;
NEXT M
NEXT L
NEXT K
END
```

Bình luận. Ở đây, thay vì một, nó sử dụng ba vòng lặp lồng nhau. Hãy xem xét các dòng 10, 20, 90, 100:

```
FOR K=1 TO 9
FOR L=0 TO 9
NEXT L
NEXT K
```

Sau khi bắt đầu các hoạt động ở K=1, chúng ta sẽ ngay lập tức thấy mình ở vòng lặp bên trong (dòng 20 và 90) và cho đến khi nó kết thúc, chúng ta sẽ không chuyển sang dòng 90 nữa, tức là chúng ta sẽ không chuyển sang giá trị tiếp theo của K. Do đó, tại K=1, chúng ta sẽ lặp qua tất cả các giá trị L=0,1, ..., 9, sau đó chuyển sang K=2 và lặp lại tất cả các giá trị L=0,1, ..., 9, v.v. Từ đây rõ ràng là các dòng 10, 20, 90, 100 đảm bảo tìm kiếm được tất cả các cặp K, L (trong giới hạn quy định). Hơn nữa, còn có chu trình thứ ba bên trong M (dòng 30, 80). Cùng với nhau, ba chu trình này đưa ra bảng liệt kê cả ba K, L, M (trong giới hạn quy định). Bây giờ dòng 40 cho thấy kết quả là chúng ta đang lặp lại tất cả các số có ba chữ số từ 100 đến 999.

Các dòng 50-70 nhằm kiểm tra xem số có ba chữ số đang nghiên cứu có phù hợp với độ tuổi của người mắc nợ hay không. Trước hết, S được tính - tổng bình phương của các chữ số của số có ba chữ số này (dòng 50). Nếu N<S+1, то рассматриваем трехзначное число не годится и, более того, увеличивая цифру единиц M, мы подавно будем получить непригодные числа. Поэтому в строке 60 применен оператор условия перехода: если N<S+1 то ПЕРЕЙТИ к строке 90. Если же условие N<S+1 не выполнено, т. е. N>S thì bạn cũng cần kiểm tra xem số N lớn hơn S bao nhiêu đơn vị. Nếu N vượt quá S từ 32 trở lên thì chênh lệch N—S không thể là số ngày sinh. Vì vậy, chỉ với điều kiện N<S+32 thì số N mới phù hợp với độ tuổi của người mắc nợ (và sau đó mới in ra).

Nhập chương trình này vào máy tính, bạn sẽ biết được tuổi của người mắc nợ: ông ấy 109 tuổi.

Bài 9. Tìm một số có ba chữ số mà hình vuông của nó được bao quanh bởi ba chữ số khác 0.

10. Thay các số vào ký hiệu 42*4* cùng với dấu hoa thị sao cho số có năm chữ số thu được chia hết cho 72.

11. Tìm một số có bốn chữ số là số chính phương, trong đó hai chữ số đầu giống nhau và hai chữ số cuối giống nhau.

Gợi ý e. BASIC có chức năng SQR tích hợp rất hữu ích cho việc trích xuất căn bậc hai; nói cách khác, toán tử M=SQR(A) gán cho biến M một giá trị bằng căn bậc hai của giá trị của biến A.

12. Cửa hàng có mastic đóng thùng 16kg, 17kg, 21kg. Làm thế nào một tổ chức nào đó có thể lấy được 185 kg mastic mà không cần mở hộp?

13. Nhà toán học vĩ đại Pierre Fermat, người nghiên cứu sâu rộng về lý thuyết số, đã đưa ra giả thuyết rằng tất cả các số có dạng

⟦folio 6⟧

(n tự nhiên) rất đơn giản. Khi $n=1, 2, 3, 4$ đúng, câu này rất dễ kiểm tra, nhưng khi $n=5$, việc kiểm tra “thủ công” trở nên quá khó. Tuy nhiên, một nhà toán học vĩ đại khác, Leonhard Euler, với kỹ thuật nhân tạo thông minh, đã chứng minh rằng ngay tại $n=5$ Phát biểu của Fermat là sai, tức là số (*) hóa ra là hợp số trong trường hợp này. Viết chương trình cho phép bạn kiểm tra tính đúng đắn của phát biểu Euler cho $n=5$, tức là tìm ước số của một số (*) khác với số này và một.

Gợi ý. Sử dụng một chương trình chung được viết bằng BASIC, máy tính thực hiện các phép tính có sáu chữ số. Trong khi đó, số (*) nhận tại $n=5$ có 10 chữ số có nghĩa. Hãy ghi nhớ điều này khi tạo chương trình của bạn. Ký hiệu 2^16 có nghĩa là: nâng 2 lên lũy thừa 16.

14. Tìm tất cả các số có ba chữ số bằng tổng các lập phương của các chữ số của chúng.

15. Trong số có ba chữ số, chữ số đầu tiên bên trái bị gạch bỏ; khi nhân số có hai chữ số với 7 thì được số có ba chữ số ban đầu. Tìm anh ấy.

16. Trong số có ba chữ số, tất cả các chữ số đều là số lẻ thì chữ số ở giữa bị gạch bỏ. Hóa ra số có hai chữ số thu được là ước số của số ban đầu. Tìm tất cả các số có ba chữ số như vậy.

Gợi ý: chuỗi

10 FOR A=1 TO 9 STEP 2
có nghĩa là A chạy qua các số có gia số là 2 (tức là 1, 3, 5, ...).

17. Tổng các chữ số của một số có ba chữ số là bội số của 7. Bản thân số đó cũng chia hết cho 7. Tìm tất cả các số như vậy.

Gợi ý: Ký hiệu R<>0 nghĩa là R không bằng 0.

18. Một số có bốn chữ số, cũng như một số được viết bằng các chữ số giống nhau theo thứ tự ngược lại, đều là số chính phương. Tìm những con số này.

19. Giải số học sau lời giải (thay vì mỗi chữ cái bạn cần thay thế một số nhất định, các chữ cái giống nhau có nghĩa là cùng một số, và các chữ cái khác nhau có nghĩa là các số khác nhau):

a) AI + CAT = HIỆN TẠI;
b) ABBA = AA² + BB²;
b) KIO * IO = TOKYO.

20. Tìm tất cả các số có hai chữ số mà tổng các chữ số của chúng không thay đổi khi nhân với 2, 3, 4, 5, 6, 7, 8, 9.

Thông thường, khi lời giải bài toán, các biến công việc được sử dụng trên máy tính, các biến này trong chương trình sẽ đóng vai trò “bộ đếm”, “lưu trữ”, “người giám sát” các kết quả trung gian. Hãy xem xét điều này bằng cách sử dụng các ví dụ sau.

Bài toán 21. Tìm giá trị lớn nhất của tổng $M^2+N^2$ khi M và N chạy qua tất cả các giá trị từ 1 đến 100,

Bình luận. Ở đây, một hàm ABS tùy chỉnh được sử dụng, được thiết kế để tìm mô-đun (hoặc, như người ta thường nói, giá trị tuyệt đối) của một số; nói cách khác, toán tử H=ABS(Q) gán giá trị |Q| đến biến H. Hơn nữa, P, K, L là các biến làm việc (“người giám sát”), được thiết kế để lưu trữ các kết quả trung gian thu được trong một thời gian trong quá trình hoạt động của chương trình. Biến P nhằm mục đích lưu trữ giá trị khả dụng $M^2+N^2$: ban đầu P=0 (dòng 10) và mỗi lần (trong các điều kiện áp đặt cho M, N) thu được tổng bình phương lớn hơn giá trị đó, biến P được gán một giá trị mới bằng tổng bình phương này. Tuy nhiên, tạm thời các biến K, L nhận (và lưu trữ cho đến lần thay đổi tiếp theo) các giá trị của M, N lớn hơn giá trị của tổng bình phương thu được. Sau toàn bộ tìm kiếm, giá trị cao nhất của tổng bình phương và những M, N lớn hơn giá trị sẵn có sẽ được in. Lưu ý giữa các chữ P, K, L ở dòng 110 có dấu phẩy (chứ không phải dấu chấm phẩy): với cách in này, các số hiển thị trên màn hình cách xa nhau hơn (số này chiếm 15 vị trí).

Bài toán 22. Có bao nhiêu tấm vé sáu chữ số “may mắn” (tức là những tấm vé có số tiền
