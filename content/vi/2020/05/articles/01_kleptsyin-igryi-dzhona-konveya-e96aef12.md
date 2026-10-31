---
id: 2020-5-kleptsyin-igryi-dzhona-konveya-e96aef12
issue: kvant_2020_5
year: 2020
number: "5"
title: Trò chơi John Conway
authors:
  - Клепцын В. А.
rubric: osnovnye-stati
page_first: 12
page_last: 15
page_labels: "13"
tag: 0NNG
lang: vi
source: kvant_digital
extraction: native
content_sha256: 785013d74fbd6b35386fe4e834b5e4c19947e1ba266678a1386ad0816711c649
prompt_sha256: draft-1
translated_from: content/ru/2020/05/articles/01_kleptsyin-igryi-dzhona-konveya-e96aef12.md
source_content_sha256: b9188d96b4ab466bb2b8c382eb1e021d3bc6ce01c3f2a6b23df23788d1158687
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

Trò chơi John Conway

V.KLEPTSYN

John Conway (26/12/1937–04/11/2020) cho biết ông không làm việc một ngày nào mà chỉ chơi. Là một nhà toán học xuất sắc của thời đại chúng ta, anh ấy đã làm việc “vui vẻ” trong nhiều lĩnh vực, và tôi muốn nhớ lại một số điều anh ấy đã làm và hãy nhớ.

Trò chơi cuộc sống

Có lẽ khám phá được biết đến rộng rãi nhất của Conway là phát minh ra Trò chơi cuộc sống. Nó hoạt động như thế này: trên giấy ca rô (vô tận), một số ô được khai báo là "sống" (hoặc "được lấp đầy" và chúng thường được sơn đè lên) và phần còn lại là "chết" (hoặc "trống"). Sau đó, cấu hình của chúng bắt đầu (tất cả cùng một lúc!) phát triển theo những quy tắc cực kỳ đơn giản sau: 1. Nếu một tế bào sống tại một thời điểm nào đó có 2 hoặc 3 tế bào sống trong số 8 tế bào lân cận, thì ở lượt tiếp theo, nó sẽ sống sót, nếu không thì nó sẽ chết (người ta thường nói rằng nếu có 1 hoặc 0 tế bào lân cận còn sống thì nó sẽ chết “vì cô đơn”, và nếu nhiều hơn 3 tế bào thì “do quá đông đúc”). 2. Nếu một ô trống có đúng 3 ô lân cận còn sống, thì ở lần di chuyển tiếp theo, sự sống sẽ được sinh ra trong đó (nếu không ô đó vẫn trống). Vì vậy (Hình 1), hình vuông 2 u 2 (“khối”) đứng yên (mỗi ô của nó có 3 ô lân cận), một dòng gồm 3 ô quay 90 độ quanh tâm trong 1 lần di chuyển (đó là lý do tại sao nó được gọi là “nhấp nháy”)

Cơm. 1. Khối, đèn hiệu và tổ ong

DOI: https://doi.org/10.4213/kvant20200502

⟦column⟧

⟦figure⟧

Cơm. 2. Năm vị trí liên tiếp của tàu lượn bay sang phải và bay xuống

coy" hoặc "semaphore"), và hình chữ nhật 2 u 3 trong một nước đi sẽ trở thành một "tổ ong" (một cấu hình không thay đổi khác). Từ "trò chơi" ở đây không hoàn toàn chính xác, bởi vì tất cả những gì mà "người chơi" ảnh hưởng là sự sắp xếp ban đầu của các ô, mọi thứ xa hơn không phụ thuộc vào anh ta. Nhưng cuộc sống của một "đàn ô" như vậy có thể rất thú vị để quan sát. Tàu lượn (hoặc tàu lượn), như trong Hình 2, là một cấu hình di chuyển sang phải và xuống với tốc độ không đổi một góc 45 độ Và một cấu hình năm tế bào trông có vẻ ngây thơ khác, r-pentamino (Hình 3), đã phát triển qua 1.103 thế hệ. Nhìn vào r-pentamino, Conway hỏi một câu hỏi thú vị sau: có những cấu hình tăng trưởng vô hạn không? lời giải câu hỏi này - được nhận bởi Bill Gosper, người đã phát hiện ra súng lượn, một cấu hình liên tục “bắn” tàu lượn. Việc tạo ra súng lượn sau một thời gian đã giúp chứng minh rằng Trò chơi cuộc sống đã hoàn tất: bất kỳ chương trình nào có thể chạy trên bất kỳ máy tính nào đều có thể được “mô phỏng” bằng

⟦folio 13⟧

TRÒ CHƠI

JOHN

⟦figure⟧

Hình.9. Vị trí có giá trị 1 2 và phương trình của nó; gốc vô hạn có giá trị 1 3; hai thân cây vô tận có giá trị phi vật chất

bằng không (tức là người mới bắt đầu thua). Đối với đồ thị hữu hạn trong trò chơi Hackenbush, các số đi kèm với chúng luôn là số hữu tỉ nhị phân. Nhưng bằng cách cho phép chúng ta xét “cây tre” vô hạn (tuy nhiên, trò chơi luôn hoàn thành trong một thời gian hữu hạn), chúng ta cũng có thể thu được các vị trí có thể liên kết với bất kỳ số thực nào. Hơn nữa, hóa ra “trong lý thuyết trò chơi” có thể chọn những trò chơi có thể được khai báo là “những con số”. Và việc xác định các phép toán trên chúng là điều tự nhiên - phép cộng, phép nhân, v.v. Tuy nhiên, trong số những số như vậy sẽ không chỉ có tất cả các số thực mà còn có nhiều số khác. Hãy nhìn vào ba bức tranh bên phải trong Hình 9. Trò chơi thứ hai trong ba trò chơi này, “thân tre” vô hạn màu xanh lam, sẽ tương ứng với “số vô hạn” - số thứ tự Z. Và thân cây vô hạn, trong đó cạnh xanh lam chỉ ở dưới cùng, sẽ tương ứng với “số” nghịch đảo của nó là 1 Z. Và tất cả đây đều là những con số siêu thực do Conway phát minh ra - tuy nhiên, điều mà tôi không định nghĩa ở đây. Bạn có thể đọc về điều này trong cuốn sách của Pierre Dehornoy [3]; và bài viết [4] trong «Kvant» năm 1979 được dành cho những con số siêu thực (không có bất kỳ mối liên hệ nào với lý thuyết trò chơi). Để hoàn thiện câu chuyện về trò chơi, chúng ta có thể kể đến hai cuốn sách của Conway - “Về những con số và trò chơi” và “Những cách chiến thắng trong trò chơi toán học của bạn”, đồng tác giả với Berlekamp và Guy. Cả hai đều trở thành sách bán chạy nhất ngay sau khi phát hành.

Tính vô tỉ của nghiệm số 2 Tôi xin nhắc lại một bài viết rất thú vị – đặc biệt dành cho học sinh

CONWAY

⟦column⟧

Conway và Shipman [5], nơi thu thập nhiều bằng chứng khác nhau về tính vô tỉ của căn bậc 2 (và các căn bậc hai khác). Đây thực sự là một bài đọc thú vị: làm thế nào có thể thu được cùng một kết quả bằng các phương pháp hoàn toàn khác nhau. Tất nhiên, nó cũng đề cập đến cách chứng minh cổ điển, trong đó hóa ra cả tử số và mẫu số đều phải chẵn, nhưng không chỉ vậy. Vì vậy, chứng minh của Tannenbaum xuất hiện ở đó. Cụ thể, nếu 2 là số hữu tỉ thì ta có thể lấy cặp số nguyên p, q nhỏ nhất sao cho diện tích hình vuông có cạnh p bằng tổng diện tích của hai hình vuông có cạnh q. Nhưng đặt hai hình vuông như vậy bên trong một hình vuông có cạnh p (Hình 10, bên trái), chúng ta thấy rằng trong trường hợp này diện tích được bao phủ hai lần (và đây là hình vuông có cạnh 2q p ) bằng diện tích không được che phủ (và đây là hai hình vuông có cạnh p q). Và ta gặp mâu thuẫn với tính cực tiểu của cặp p, q. Và Conway nhận thấy rằng tính vô tỉ của nghiệm của 3 có thể được chứng minh theo cách tương tự - nó được mô tả trong Hình 10 bên phải $.^{1}$ Một bằng chứng khác được thu thập trong cùng bài viết thuộc về Miklos Lackovic: nếu bạn mở dấu ngoặc đơn trong biểu thức n

2 1 thì ta được số có dạng

A 2 B, trong đó A và B là số nguyên. И если бы 2

⟦figure⟧

Cơm. 10. Chứng minh của Tannenbaum về tính vô tỉ 2 và phép sửa đổi Conway cho 3

1 Có bằng chứng tương tự cho

5

và 6: chúng có thể được tìm thấy trong bài viết của A. Spivak “Sự vô tỷ của các nghiệm từ 2, 3, 5 và 6” («Kvant», 2010, Số 1).
