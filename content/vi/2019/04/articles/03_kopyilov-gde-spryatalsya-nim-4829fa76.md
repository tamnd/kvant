---
id: 2019-4-kopyilov-gde-spryatalsya-nim-4829fa76
issue: kvant_2019_4
year: 2019
number: "4"
title: Nim đã trốn ở đâu?
authors:
  - Копылов И.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 33
page_last: 40
page_labels: 34, 35, 36, 38
tag: DEB3
lang: vi
source: kvant_digital
extraction: native
content_sha256: 7b09df311264ff27a70e13a308d58fa13ba18cfa75437314213efc80d953c6d2
prompt_sha256: draft-1
translated_from: content/ru/2019/04/articles/03_kopyilov-gde-spryatalsya-nim-4829fa76.md
source_content_sha256: 2f372bdb6788e254d9b7715d7c6e611d4bba5af76c2ae0ac2b30961d7636e3b0
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

MẠCH TOÁN OK

Nim đã trốn ở đâu?

I.KOPYLOV

ĐIỀU KHOẢN “ƯU ĐIỂM VÀ NHƯỢC ĐIỂM VÀ TRÒ CHƠI VỚI NIM”

(xem «Kvant» số 7, 8 năm 2018) chiến lược của trò chơi Nim đã được mô tả, chiến lược này đóng một vai trò đặc biệt trong lý thuyết trò chơi. Trò chơi Nim như sau. Có m cọc, số viên đá trong đó bằng $a_{1}, a_{2}$, … $, a_{m}$. Hai người thay phiên nhau đi bộ; Mỗi người chơi, trong lượt của mình, chọn một trong các cọc và lấy bất kỳ số viên đá nào khác 0 từ đó. Người nào lấy được viên đá cuối cùng sẽ thắng. Nhiều trò chơi đến với Nim. Nếu trò chơi nhận ra được Nim thì ngay lập tức một chiến lược mượn từ Nim sẽ xuất hiện cho nó. Trong bài viết này, chúng tôi sẽ giảm bớt một số trò chơi khác nhau cho Nim. Trò chơi 1. Năm con chip nằm trên các ô của một dải ngang gồm 25 ô. Đối với mỗi lần di chuyển, bạn phải di chuyển một trong các quân cờ sang trái đến bất kỳ ô nào; được phép nhảy qua các con chip khác; một số chip có thể ở trên một ô. Người chơi thắng, sau khi di chuyển tất cả 5 chip sẽ ở ô ngoài cùng bên trái của dải. Trò chơi rõ ràng thuộc về Nim với 5 đống đá. Hãy đánh số các ô của dải, bắt đầu từ 0, từ trái sang phải (Hình 1). Khi đó, một con chip đứng trên ô số n có thể được di chuyển trong 1 lần di chuyển đến bất kỳ ô nào trong số các ô 0, 1, ..., n 1, bất kể vị trí của các chip còn lại. Tương tự, trong trò chơi Nim, số lượng quân cờ ở một trong các cọc trong mỗi lượt giảm xuống còn 0. Do đó, để giảm về Nim, quân chip ở ô n phải được thay thế bằng quân cờ có n quân cờ. Khi đó chip nằm ở ô vuông ngoài cùng bên trái

⟦column⟧

tương đương với một đống trống. Trò chơi kết thúc khi tất cả các cọc đều trống, tức là tất cả các chip được thu thập trên ô đánh số 0. Vì vậy, nếu có 5 chip nằm trên các ô được đánh số a, b, c, d và e, thì Nim-sum được tổng hợp cho các số a, b, c, d và e. Chúng ta hãy nhớ lại rằng Nim-sum được tính từng bit một như sau: Các số Nim-sum được viết trong hệ nhị phân, và nếu có một số lẻ đơn vị trong một chữ số cho trước thì trong tổng kết quả ở chữ số tương ứng chúng ta đặt 1, nếu nó chẵn - 0. Nim-sum của các số a, b, c, d, e được ký hiệu là a b c d e. Đến lượt của mình, người chơi phải thiết lập lại Nimsumma. Hãy xem một ví dụ. Để các quân chip đứng trên các ô vuông 5, 10, 14, 16 và 22 sọc (xem Hình 1). Việc tính toán Nimsum tương ứng được thể hiện trong Hình 2.

⟦figure⟧

Hình 2. Tính tổng Nim để xác định nước đi ở ván 1

Vì thế,

5  10  14  16  22

$= 101_{2}$  $1010_{2}$  $1110_{2}$  $10000_{2}$  $10110_{2} 111_{2} 7$.

Số tiền nim khác 0. Người chơi thực hiện nước đi phải đặt lại về 0. Đơn vị cao nhất trong tổng Nim là chữ số nhị phân thứ 2, nếu đếm các chữ số từ phải sang trái, bắt đầu từ 0. Đơn vị ở chữ số thứ hai có mặt trong bản ghi số lượng quân cờ ở cọc 1, 3 và 5. Do đó, trong ví dụ đang xem xét, người chơi có 3 lựa chọn để đi nước đi: hoặc để $10_{2} 2$ đá ở cọc đầu tiên, tức là di chuyển quân bằng

⟦figure⟧

Hình 1. Đánh số các ô dải và vị trí của chip trong ví dụ

DOI: https://doi.org/10.4213/kvant20190405

(Tiếp theo trang 34)

⟦folio 34⟧

KVANT 2019/№4

ô 5 đến ô 2, hoặc để $1001_{2} 9$ đá ở cọc thứ ba, tức là di chuyển chip từ ô 14 sang ô 9, hoặc để $10001_{2} 17$ đá ở cọc thứ năm, nghĩa là di chuyển chip từ ô 22 sang ô $17. Игра^{2.}$ Con sâu bướm gồm 20 mắt xích. Một số mắt xích sâu bướm được sơn màu xanh lá cây, số còn lại có màu trắng. Hai người chơi lần lượt sơn lại các mắt xích: mắt xanh làm màu trắng, mắt trắng làm màu xanh lá cây. Trong lượt của mình, người chơi phải sơn lại một trong các mắt xích màu xanh lá cây thành màu trắng và có thể sơn lại mắt xích khác nằm gần đuôi của mắt xích được sơn lại. Người chơi thắng, sau khi di chuyển tất cả các liên kết sâu bướm chuyển sang màu trắng. Trò chơi này là một Nim ẩn. Hãy đánh số các mắt xích của sâu bướm, bắt đầu từ phần đuôi. Liên kết đuôi sẽ nhận được số 1, liên kết đầu – 20 (Hình 3). Liên kết xanh

⟦column⟧

⟦figure⟧

Hình 4. Tính tổng Nim để xác định nước đi ở ván 2

với 7 cọc có số đá 2, 5, 6, 9, 14, 16 và 19. Vì Nim-sum tương ứng bằng (Hình 4)

2  5  6  9  14  16  19

$= 10_{2}$  $101_{2}$  $110_{2}$  $1001_{2}$  $1110_{2}$ 

$10000_{2}$  $10011_{2}$ 

101 2

5 và có một đống 5 viên đá, sau đó người chơi thực hiện -

⟦figure⟧

Hình 3. Đánh số các liên kết sâu bướm

chúng ta thay những con sâu bướm có số k bằng một đống đá k. Trong quá trình di chuyển của mình, người chơi tô màu lại một liên kết màu xanh lá cây với một số k và có thể đổi màu một liên kết khác có số nhỏ hơn k. Nếu người chơi chỉ tô màu lại một liên kết, thì chúng tôi coi như anh ta đã làm trống một đống k viên đá. Nếu mắt xích thứ hai được tô màu lại có số m (m < k) và có màu trắng trước khi người chơi di chuyển, thì chúng ta giả sử rằng người chơi đã lấy k – m quân từ đống k quân và để lại m quân trong đó. Và trong trường hợp khi liên kết được đổi màu thứ hai với số m có màu xanh lá cây và trở thành màu trắng, thì chúng ta sẽ giả định rằng người chơi đã bỏ m viên đá vào đống có k viên đá. Vì trước đó đã có một đống đá nên bây giờ có hai viên. Và hai cọc giống hệt nhau đóng góp bằng 0 vào tổng Nim. Vì vậy, sau này trong trò chơi Nim không thể xem xét và loại trừ chúng khỏi trò chơi. Như vậy, trò chơi này về tay Nim với số cọc bằng số mắt xích sâu xanh. Số lượng đá trong đống trùng với số lượng liên kết màu xanh lá cây tương ứng. Ví dụ, trong Hình 3, trò chơi vẽ lại các mắt xích sâu bướm tương đương với nước đi Nim; chỉ cần đặt lại một đống 5 viên đá là đủ, và Nim-sum của các cọc còn lại sẽ bằng 0. Do đó, nước đi thắng từ trạng thái trong Hình 3 là sơn lại mắt xích xanh 5 màu trắng. $Игра^{3.}$ Hai người chơi lần lượt bẻ một thanh sô cô la được chia rãnh thành 8 và 12 miếng. Một trong những hạt gạch được đánh dấu bằng một cây thánh giá. Với mỗi bước di chuyển của mình, người chơi sẽ phá vỡ một ô dọc theo một trong các rãnh và ăn phần ô đó không chứa mảnh có hình chữ thập. Người chiến thắng là người chơi có nước đi chỉ để lại một miếng sô cô la có hình chữ thập. Trò chơi này cũng là một Ngài che mặt. Người chơi có 4 lựa chọn để di chuyển: phá ô dọc theo rãnh phía trên quân cờ có hình chữ thập, ở bên phải quân cờ có hình chữ thập, ở dưới hoặc ở bên trái của quân cờ đó. Nếu khi bắt đầu trò chơi, một hạt có hình chữ thập được đặt, chẳng hạn như trong Hình 5, thì có 4 hàng phía trên hạt có hình chữ thập, 5 hàng ở bên phải, 3 hàng bên dưới, 6 hàng ở bên trái. Việc di chuyển một trong bốn tùy chọn sẽ làm giảm số lượng hàng theo hướng tương ứng.

⟦folio 35⟧

MATEM ATI CHES KY

⟦figure⟧

Hình 5. Hình ảnh thanh sô cô la có phần được đánh dấu bằng hình chữ thập

Vì thế trò chơi tương đương với Nim với 4 đống đá. Ở chồng đầu tiên, số lượng viên đá trùng với số hàng phía trên mảnh có hình chữ thập, ở chồng thứ hai - với số hàng ở bên phải của mảnh có hình chữ thập, ở chồng thứ ba - bên dưới và ở hàng thứ tư - ở bên trái của nó. Trong ví dụ ở Hình 5, khi bắt đầu trò chơi có 4, 5, 3 và 6 viên đá xếp thành chồng. Trong lượt của mình, người chơi chọn một cọc và giảm số lượng đá trong đó. Để xác định nước đi, chúng tôi biên soạn Nimsumma. Trong ví dụ đang xem xét, việc tính tổng Nim được thực hiện trong Hình 6. Chúng ta thu được 4 5 3 $6 100_{2}$ $101_{2}$ $11_{2}$ $110_{2}$

$100_{2} 4$. Như có thể thấy trong Hình 6, tổng Nim khác 0. Để đặt lại nó, bạn cần xóa

⟦figure⟧

Hình 6. Tổng hợp Nim-sum để xác định nước đi ở ván 3

một đơn vị ở chữ số nhị phân có ý nghĩa nhất, tức là loại bỏ 4 viên đá khỏi một trong các cọc 1, 2 hoặc 4. Trong trò chơi được đề cập, người chơi phải loại bỏ 4 hàng ở trên, bên phải hoặc bên trái của hình vuông có hình chữ thập. Trò chơi 4. Có một con chip trên năm ô của một dải ngang gồm 25 ô. Đối với mỗi lần di chuyển, bạn được phép di chuyển bất kỳ con chip nào sang trái sang một ô trống mà không cần nhảy qua các con chip khác. Người chơi không thể di chuyển sẽ thua. Hãy đánh số các ô của dải từ trái qua phải với các số từ 1 đến 25. Các chip trên dải cũng sẽ được đánh số từ trái sang phải. Người chơi không phải

KR UZH OK

⟦column⟧

có thể thực hiện một nước đi khi có năm quân cờ chiếm các ô được đánh số từ 1 đến 5. Để tìm ra chiến lược, trước tiên chúng ta hãy đơn giản hóa trò chơi. Để chỉ có một con chip trên dải. Sau đó, người mới bắt đầu chiến thắng bằng cách đặt một con chip vào ô 1. Nếu có hai con chip trên một dải, thì chiến lược được xác định mà không cần nỗ lực nhiều. Người chơi nên đặt chip vào các ô liền kề. Đối thủ sẽ chỉ được thực hiện nước đi với chip 1. Người chơi, với nước đi tiếp theo, di chuyển chip 2 sang trái để các chip lại nằm ở các ô liền kề. Kết quả là sau một vài nước đi, quân chip sẽ ở ô 1 và 2, và đối thủ sẽ không thể di chuyển được. Tiếp theo, hãy xem xét trường hợp của một trò chơi có ba con chip trên một dải. Để xây dựng chiến lược, chúng ta sẽ sử dụng quy tắc đặt dấu “+” và “–” được đưa ra trong bài “Ưu nhược điểm và trò chơi Nim”. Trạng thái của trò chơi được xác định bởi 3 số - số ô có chip. Vì vậy, việc đặt các dấu hiệu vào các ô của bảng ba chiều là cần thiết. Tọa độ của các ô $a_{1}, a_{2}, a_{3}$ thỏa mãn quan hệ

$0 a_{1} a_{2} a_{3}$,

(1) trong đó $a_{1}$ là số ô có chip $1, a_{2}$ – với chip $2, a_{3}$ – với chip 3. Do việc di chuyển của một trong những người chơi, một trong ba tọa độ giảm xuống và mối quan hệ (1) vẫn có hiệu lực. Chúng ta sẽ điền vào bảng các dấu hiệu theo từng lớp. Ở lớp dưới cùng, nơi $a_{1} 1$, quân 1 không thể di chuyển. Và đối với hai con chip, chúng tôi đã thiết lập rằng ở trạng thái âm, các con chip được đặt trong các ô liền kề của dải. Điều này có nghĩa là $a_{2} 1 a_{3}$ và trong tất cả các ô có tọa độ $1, a_{2}, a_{2} 1, 1 a_{2}$, có dấu “-” và trong tất cả các ô khác của lớp đầu tiên có dấu “+”. Trong các ô của lớp thứ hai của bảng, trong đó $a_{1} 2$, các điểm trừ nằm trong các ô có tọa độ 2,3,5, 2,4,6, 2,5,7, …, tức là trong các ô thuộc loại $2, a_{2}, a_{2} 2, 2 a_{2}$. Khi điền vào các ô của lớp thứ ba bằng dấu “+” và “–”, chúng ta nhận thấy các điểm trừ xuất hiện trong các ô có tọa độ có dạng $3, a_{2}, a_{2} 3, 3 a_{2}$. Nhìn vào việc lấp đầy ba lớp đầu tiên của bảng bằng các điểm trừ, chúng ta có thể giả sử rằng dấu “-” nằm trong các ô có tọa độ

⟦folio 36⟧

KVANT 2019/№4

natami $a_{1}, a_{2}, a_{2} a_{1}, 0 a_{1} a_{2}$. Hoặc ở dạng khác, tọa độ $a_{1}, a_{2}, a_{3}$ của các ô trừ có liên hệ với nhau bằng quan hệ a 1

$a_{3} a_{2}$.

(2)

Phỏng đoán này được chứng minh bằng phương pháp quy nạp toán học trên $a_{1}$. Chúng ta hãy viết lại quan hệ (2) dưới dạng

$a_{1} 0$ a 3 a 2

(3) và giả sử rằng một ô khác có số 0 đã được thêm vào dải bên trái, trên đó có chip fiat 0. Khi đó, khoảng cách trong các ô giữa chip thứ nhất và chip 0 trùng với khoảng cách trong các ô giữa chip thứ ba và chip thứ hai. Nếu việc sắp xếp chip thỏa mãn mối quan hệ (3), thì bất kỳ nước đi nào của đối thủ

họ đồng ý với tỷ lệ

⟦column⟧

a 2 a 1

$a_{4} a_{3}$.

Và cuối cùng, đối với 5 chip trên một dải, chúng tôi sẽ lại giới thiệu một chip số 0 cố định có điều kiện, chúng tôi sẽ đặt chip này trên một ô số 0 có điều kiện được gắn vào dải bên trái. Trò chơi đến với Nim với 3 đống đá. Chúng tôi giả định rằng số lượng viên đá trong đống thứ nhất bằng số lượng ô tự do giữa các chip 0 và 1. Kích thước của đống thứ hai được xác định bởi số lượng ô tự do trên dải giữa các chip 2 và 3. Số lượng đá ở đống thứ ba chính xác bằng số lượng ô tự do trên dải giữa chip thứ 4 và thứ 5. Hình 7 trình bày một ví dụ về xác định kích thước của ba cọc ở Nimes tương đương.

⟦figure⟧

Hình 7. Ví dụ xác định số quân trong ván 4

sẽ dẫn đến vi phạm và người chơi phải khôi phục lại sự đáp ứng của mối quan hệ (3) bằng nước đi phản ứng của mình. Có sự tương ứng giữa Nim và hai đống đá. Số lượng đá trong đống đầu tiên trùng với số lượng ô tự do giữa chip 0 và chip thứ nhất, và ở đống thứ hai - giữa chip thứ hai và chip thứ ba. Ở Nimes có hai cọc, người chơi phải cân bằng số lượng đá trong cọc với mỗi lần di chuyển. Không giống như Nim, trong trò chơi này, đối thủ có thể, bằng cách di chuyển chip 2, tăng số ô trống giữa chip 2 và 3, điều này trong trò chơi Nim tương ứng với việc tăng số lượng đá ở cọc thứ hai. Trong trường hợp này, người chơi phải phản ứng bằng cách di chuyển chip 3 sang trái, trả lại số ô trống trước đó giữa chip thứ hai và thứ ba. Trường hợp 3 chip trên một dải đã được xử lý. Hãy để trò chơi bây giờ được chơi với 4 chip trên một dải. Sau đó, chip có điều kiện được giới thiệu khi xem xét trường hợp trước sẽ nhận được phương án. Chúng ta hãy biểu thị bằng $a_{i}$ số ô chứa chip thứ i (i = 1, 2, 3, 4). Bằng cách tương tự với trường hợp trước, số lượng ô có chip ở trạng thái trừ được thỏa mãn

Trong ví dụ, số quân trong cọc là 4, 1 và 5. Để giành chiến thắng, người chơi phải đặt lại Nim-sum tương ứng cho ba cọc với mỗi nước đi của mình. Di chuyển các chip số lẻ sẽ làm giảm số lượng đá ở một trong các cọc. Nếu đối thủ di chuyển một quân 2 hoặc 4, chẳng hạn như k ô sang trái, thì ở một đống 2 hoặc 3 quân tương ứng, số lượng quân cờ sẽ tăng lên. Trong trường hợp này, người chơi phải sử dụng chiêu thức của riêng mình để khôi phục lại số lượng đá trong đống bằng cách di chuyển các ô k chip số lẻ tương ứng sang trái. Trong ví dụ đang xem xét, Nim-sum bằng 0 (Hình 8). Vì vậy, người chơi đến lượt đi sẽ thua.

⟦figure⟧

Hình 8. Tính Nim-sum cho 3 cọc ở ván 4

Trò chơi 5. Các ô của dải 10 ô được đánh số từ 1 đến 10. Trên mỗi ô

⟦folio 38⟧

KVANT 2019/№4

⟦figure⟧

Hình 10. Tính tổng Nim cho các số trong ván 5

Bạn nên di chuyển một chip từ ô 9, để lại ba chip trên đó. Số tiền nim sau một động thái như vậy sẽ trở thành số không. Ván 6. Trò chơi diễn ra với 4 đường đứt nét. Số lượng mắt xích trong một đường gãy không vượt quá 20. Ba đường gãy được gắn vào một đế cố định ở một đầu và đường thứ tư - ở cả hai đầu (Hình 11). Vì

⟦figure⟧

Hình 11. Ví dụ về trạng thái ban đầu của trò chơi

Mỗi lần di chuyển bạn được phép loại bỏ một liên kết khỏi bất kỳ dòng bị hỏng nào. Nếu sau khi di chuyển có các liên kết bị rách khỏi đế thì tất cả chúng cũng bị loại bỏ. Người chơi thắng, sau khi di chuyển, các liên kết của tất cả các đường gãy sẽ bị loại bỏ. Hãy rút gọn trò chơi về Nim với 4 đống đá. Để các đường gãy A, B và C được gắn vào đế bằng một đầu và đường đứt D bằng hai đầu. Chúng ta hãy đánh số các liên kết của từng dòng bị hỏng một cách tuần tự. Đối với các đường gãy A, B và C, số 1 sẽ nhận được một mắt xích gắn vào đế (Hình 11). Hãy chứng minh rằng mỗi đường gãy A, B và C có thể được thay thế bằng một cọc, số viên đá trong đó bằng số mắt xích trong đường gãy tương ứng. Ví dụ, cho dòng đứt gãy A chứa k liên kết. Khi loại bỏ liên kết thứ i của đường đứt A, 1 d i d k, nó còn lại liên kết i –1 với các số từ 1 đến i –1. Như vậy, việc loại bỏ liên kết thứ i tương đương với việc bỏ lại i –1 viên đá trong đống. Chúng ta cũng thay thế đường D gãy bằng một số đống đá tổng quát. Hãy để nó bị phá vỡ

⟦column⟧

D ban đầu chứa m liên kết. Sau khi loại bỏ một trong các mắt xích của nó, chẳng hạn như mắt xích i, 1 di d m, đường gãy chia thành 2 nét đứt với các mắt xích i – 1 và m – i, mỗi mắt xích được gắn vào đế ở một đầu. Hãy chứng minh rằng 2 đường gãy mới trong trò chơi có thể được thay thế bằng một đống đá ở Nîmes. Nếu có số mắt xích chẵn ở vạch gãy D thì sau khi bỏ đi một mắt xích, kết quả là hai vạch gãy sẽ có số mắt xích không bằng nhau, đối thủ có cơ hội dùng chiêu thức của mình để cân bằng số mắt xích ở các vạch gãy mới. Hai cọc giống hệt nhau có cùng biểu diễn nhị phân và đóng góp bằng 0 vào Nimsum. Chúng tôi thấy rằng đống tổng quát mà chúng tôi muốn thay thế dòng D bị hỏng cũng không đóng góp gì cho Nim-sum, tức là trống. Sự khác biệt giữa một đống đá tổng quát và một đống đá đơn giản khi chơi Nim là ngay cả khi đống đá tổng quát trống, người chơi vẫn có thể thực hiện một động tác để chuyển nó sang một đống không trống. Trong trường hợp này, đối thủ sẽ tự mình vô hiệu hóa nó. Và một lần nữa người chơi phải di chuyển, và cọc tổng quát sẽ trống. Chúng tôi trở lại trạng thái đã tồn tại. Sau mỗi lần di chuyển, tổng số mắt xích trong các đường gãy giảm đi nên không thể quay lại trạng thái cũ của cọc tổng quát vô số lần. Bây giờ chúng ta hãy xem xét trường hợp đường đứt nét D có số lượng liên kết lẻ. Sau đó, bằng cách loại bỏ liên kết ở giữa, người chơi có thể nhận được hai đường gãy có cùng số liên kết, không đóng góp gì cho Nimsumma. Chúng ta hãy chứng minh rằng khi loại bỏ bất kỳ mắt xích nào khác của đường gãy D, đối thủ có thể, sau nước đi tiếp theo, để lại hai đường gãy có đóng góp cho Nim-sum tương đương với đóng góp của một cọc với một viên đá. Một dòng gãy D, sau khi loại bỏ một liên kết, không thể chia thành hai dòng gãy, số lượng liên kết trong đó chênh lệch đúng 1. Nhưng khi đó, đối phương, bằng cách giảm số lượng liên kết trong một dòng gãy với một số lượng lớn các liên kết, có thể thu được trong các dòng gãy mới số lượng liên kết là hai số liên tiếp, chẳng hạn như 2n và 2n + 1, trong đó số nhỏ nhất là 2n là số chẵn. Sự đóng góp của hai số như vậy vào
