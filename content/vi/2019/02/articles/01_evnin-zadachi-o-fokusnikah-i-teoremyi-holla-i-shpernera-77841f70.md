---
id: 2019-2-evnin-zadachi-o-fokusnikah-i-teoremyi-holla-i-shpernera-77841f70
issue: kvant_2019_2
year: 2019
number: "2"
title: Bài toán về các nhà ảo thuật và các định lý của Hall và Sperner
authors:
  - Эвнин А. Ю.
rubric: osnovnye-stati
page_first: 16
page_last: 25
page_labels: 15, 17, 22, 23
tag: CBDG
lang: vi
source: kvant_digital
extraction: native
content_sha256: e898320bc7488ec9f89d3a62ffef71b45a4b09e9d520bf23d0f5397b3d211efc
prompt_sha256: draft-1
translated_from: content/ru/2019/02/articles/01_evnin-zadachi-o-fokusnikah-i-teoremyi-holla-i-shpernera-77841f70.md
source_content_sha256: f406cc9699b7c27a9cd4f66bf102f9ef921a7089562ca1d60ececf67013a086f
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

Bài toán về các nhà ảo thuật và các định lý của Hall và Sperner

A.EVNIN

Định lý Hall

bài toán sau đây đã được biết đến rộng rãi trong các tài liệu toán học phổ thông. Bài toán về đám cưới. Có rất nhiều chàng trai, mỗi người đều biết một số cô gái. Trong những điều kiện nào có thể cưới tất cả các chàng trai trẻ cùng một lúc để mỗi người trong số họ cưới một cô gái mà anh ta biết? Đáp số là: bài toán có thể giải được khi và chỉ khi bất kỳ k chàng trai nào trong một tập hợp nhất định quen biết chung với ít nhất k cô gái. Lưu ý rằng nhu cầu ở đây là hiển nhiên. Thật vậy, nếu với k thanh niên nào đó số lượng cô dâu tiềm năng nhỏ hơn k thì k thanh niên này sẽ không thể kết hôn cùng một lúc. Chứng minh đủ không dễ dàng như vậy! Để xây dựng bài toán về đám cưới bằng ngôn ngữ toán học, chúng tôi trình bày một số định nghĩa từ lý thuyết đồ thị [1]. Các đỉnh của đồ thị sẽ liền kề nhau nếu chúng được nối bởi một cạnh. Các cạnh của đồ thị được gọi là liền kề nếu chúng có một đỉnh chung và nếu không thì không liền kề. Các cạnh không liền kề theo cặp của biểu đồ tạo thành một khớp. Ví dụ: trong biểu đồ ở Hình 1, bạn có thể chỉ định một số kết quả khớp của bốn cạnh. Một trong số đó là ^ $aa_{1}, bb_{1}, cc_{1}, dd_{1}$ `. Giả sử $G V_{1}, V_{2}$ là một biểu đồ hai bên có phần chia $V_{1}$ và $V_{2}$ (trong biểu đồ này, bất kỳ cạnh nào kết nối một số đỉnh từ $V_{1}$ với một số đỉnh từ $V_{2} ).$ Một kết quả khớp hoàn hảo từ $V_{1}$ đến $V_{2}$ là một kết quả khớp trong biểu đồ này, bao gồm

DOI: https://doi.org/10.4213/kvant20190202

⟦column⟧

⟦figure⟧

Cơm. 1

$V_{1}$ (tức là, với mọi đỉnh từ $V_{1}$ đều có một cạnh đi ra khỏi đỉnh đó trong kết quả khớp). Ví dụ: Hình 2 hiển thị biểu đồ có lượt chia sẻ $V_{1}$ ^ $x_{1}, x_{2}, x_{3}$ ` và

⟦figure⟧

Cơm. 2

$V_{2}$^$y_{1}, y_{2}, y_{3}, y_{4}$`. Các cạnh $x_{1} y_{1}, x_{2} y_{2}$ và $x_{3} y_{4}$ tạo thành sự kết hợp hoàn hảo từ $V_{1}$ đến $V_{2}$. Cho G là đồ thị có tập đỉnh V và A là tập con của V. Môi trường của tập A là tập

* A

$\cup$ * v, v A trong đó * v là tập các đỉnh liền kề với v.

⟦folio 15⟧

NHIỆM VỤ

VỀ

ảo thuật gia

VÀ

CÁC ĐỊNH LÝ

Cũng nhớ lại rằng phần tử của một tập hợp hữu hạn là số phần tử của nó. Bây giờ lời giải bài toán về đám cưới có thể được hình thành như sau. Định lý 1 (F. Hall, 1935). Sự kết hợp hoàn hảo từ $V_{1}$ đến $V_{2}$ trong biểu đồ lưỡng cực $G V_{1}, V_{2}$ tồn tại khi và chỉ khi đối với bất kỳ tập hợp A $V_{1}$ nào thì lực lượng của xung quanh nó không nhỏ hơn lực lượng của A, tức là * A tại A. Có thể tìm thấy bốn cách khác nhau để chứng minh định lý Hall trong cuốn sách [2].

Đủ điều kiện

Trong bài viết này, chúng ta sẽ nói về một điều kiện đủ (đơn giản nhưng ít được biết đến) để tồn tại một kết quả khớp hoàn hảo trong đồ thị hai bên. Định lý 2. Giả sử trong một đồ thị lưỡng cực không trống (tức là có ít nhất một cạnh) $G V_{1}, V_{2}$ bậc của bất kỳ đỉnh nào từ phần $V_{1}$ không nhỏ hơn bậc của bất kỳ đỉnh nào từ phần $V_{2}$. Khi đó sẽ có sự kết hợp hoàn hảo từ $V_{1}$ đến $V_{2}$ trong biểu đồ này. Bằng chứng. Gọi q là một số không lớn hơn bậc của bất kỳ đỉnh nào trong $V_{1}$ và không nhỏ hơn bậc của bất kỳ đỉnh nào trong $V_{2}$. Ta lấy k đỉnh tùy ý của phần thứ nhất $b_{1}, b_{2}$, … $, b_{k}$ và các đỉnh liền kề $g_{1}, g_{2}$, … $, g_{l}$ của phần thứ hai. Xét đồ thị con G c của đồ thị gốc được tạo bởi các đỉnh k + l này (G c bao gồm các đỉnh được chỉ định và tất cả các cạnh giữa chúng có trong đồ thị gốc). Rõ ràng là trong đồ thị G c, bậc của bất kỳ đỉnh nào tính từ phần thứ nhất ít nhất là q và từ phần thứ hai không lớn hơn q. Số cạnh của đồ thị lưỡng cực bằng tổng bậc của các đỉnh của bất kỳ phần nào của nó. Do đó k kq d ¦ độ $b_{i}$ i 1 l

¦ độ $g_{j} d lq$, j 1 từ đâu k d l. Như vậy, các điều kiện của định lý Hall về sự tồn tại của một kết quả khớp hoàn hảo trong đồ thị hai bên được thỏa mãn.

SẢNH

VÀ

SPERNER

⟦column⟧

Một đồ thị được gọi là chính quy nếu bậc của tất cả các đỉnh của nó bằng nhau. Chúng ta gọi đồ thị hai bên là bán chính quy nếu trong mỗi phân vùng bậc của tất cả các đỉnh của nó bằng nhau. Chúng ta hãy rút ra các hệ quả sau đây từ Định lý 2. Hệ quả 1. Trong bất kỳ đồ thị lưỡng cực đều rỗng nào cũng có một sự so khớp hoàn hảo. Hệ quả 2. Trong một đồ thị lưỡng cực bán chính quy khác rỗng $G V_{1}, V_{2}$, một kết quả khớp hoàn hảo tồn tại khi và chỉ khi không có nhiều đỉnh trong phân vùng $V_{1}$ hơn trong $V_{2}$. Bằng chứng. Sự cần thiết là hiển nhiên. Sự đầy đủ. Đặt bậc của các đỉnh trong $V_{1}$ và $V_{2}$ lần lượt là a và b. Bằng cách đếm số cạnh trong đồ thị lưỡng cực theo hai cách, chúng ta nhận được $a V_{1} b V_{2}$. Khi tính đến bất đẳng thức $V_{1} d V_{2}$, chúng ta thu được a t b. Vẫn phải sử dụng Định lý 2.

Bài toán về pháp sư

Có một chuỗi bài toán, có thể giải dễ dàng bằng Định lý 2 và các hệ quả của nó. Cốt truyện của bài toán này như sau. Khán giả đưa cho trợ lý của ảo thuật gia một số đồ vật được chọn ngẫu nhiên (ví dụ: một số lá bài), sau đó bằng cách nào đó, trợ lý sẽ thay đổi đồ vật này theo lựa chọn của mình. Tiếp theo, ảo thuật gia sử dụng vật thể mới để khôi phục lại vật thể ban đầu. Chúng ta hãy xây dựng một biểu đồ lưỡng cực $G V_{1}, V_{2}$ như sau. Đặt các đỉnh từ $V_{1}$ là tất cả các cấu hình có thể có mà khán giả có thể trình bày với trợ lý của ảo thuật gia và các đỉnh từ $V_{2}$ là các cấu hình mà trợ lý có thể nhận được. Nếu có thể lấy cấu hình b $V_{2}$ từ cấu hình a $V_{1}$ thì đồ thị phải chứa cạnh ab; không có cạnh nào khác trong đồ thị. Nếu trong một biểu đồ nhất định có sự khớp hoàn hảo từ $V_{1}$ đến $V_{2}$, thì ảo thuật gia và trợ lý của anh ta, bằng cách sử dụng nó, sẽ có thể thực hiện thủ thuật: ảo thuật gia, dựa trên cấu hình b, sẽ xác định duy nhất cấu hình a.

⟦folio 17⟧

NHIỆM VỤ

VỀ

ảo thuật gia

VÀ

CÁC ĐỊNH LÝ

Bài toán 4. Khán giả viết n số lên bảng từ trái sang phải. Trợ lý của ảo thuật gia che một trong các số bằng thẻ đỏ, số khác bằng thẻ xanh và số khác bằng thẻ xanh. Sau đó, ảo thuật gia bước vào và gọi các số đã đóng. Với n nhỏ nhất thì thủ thuật đó có thể thực hiện được là bao nhiêu? Đáp số: với n = 12. Lời giải. Đặt $V_{1}$ và $V_{2}$ lần lượt là tập hợp các “bức tranh” mà trợ lý và ảo thuật gia có thể nhìn thấy. Hãy xem xét một biểu đồ lưỡng cực $G V_{1}, V_{2}$, các cạnh của biểu đồ này mô tả các chuyển đổi có thể có từ hình ảnh từ $V_{1}$ sang hình ảnh từ $V_{2}$. Đồ thị có dạng bán chính quy, $V_{1} 10^{n}, V_{2} n n 1 n 2$ • $10^{n} 3$. Theo Hệ quả 2, để tồn tại một kết quả khớp hoàn hảo từ $V_{1}$ đến $V_{2}$ thì điều cần thiết và đủ là phần $V_{2}$ không có ít đỉnh hơn $V_{1}$. Do đó $n n 1 n 2 t t 10^{3}$, tương đương với bất đẳng thức n t 12. Do đó, giá trị nhỏ nhất của n là 12. Chúng ta hãy chỉ ra cách thực hiện thủ thuật một cách thực tế với n t 12. Chúng ta đánh số các vị trí có 12 chữ số đầu tiên được viết từ trái sang phải: 1, 2, ..., 9, 0, 11, 12 (chúng tôi không đánh số các vị trí còn lại, nếu có!). Gọi S là tổng của tất cả các chữ số được người xem ghi lại. Chúng tôi sẽ hành động cho trợ lý như sau. Chúng ta hãy dùng thẻ đỏ che địa điểm có số là chữ số cuối cùng của số S, sau đó chúng ta sẽ xóa địa điểm này một cách tinh thần và bằng thẻ xanh, chúng ta sẽ che địa điểm đó bằng một số bằng chữ số được ẩn dưới thẻ đỏ. Sau đó, bằng thẻ xanh, chúng ta sẽ che chỗ có số (được tính sau khi “xóa” số dưới thẻ xanh và đỏ) ẩn dưới thẻ xanh. Bây giờ ảo thuật gia sẽ hiểu vị trí của lá bài màu xanh lá cây có số nào nằm dưới số màu xanh lam và vị trí của lá bài màu xanh lam - số nào nằm dưới số màu đỏ. Tất cả các số, ngoại trừ số dưới thẻ xanh, ảo thuật gia đều đã biết và vị trí của thẻ đỏ biểu thị chữ số cuối cùng của tổng tất cả các số mà khán giả viết ra. Vì vậy, ảo thuật gia sẽ xác định được số theo thẻ xanh.

SẢNH

VÀ

SPERNER

Bài toán dành cho độc lập lời giải

⟦column⟧

Hãy để chúng tôi trình bày một lựa chọn $задач^{1}$ mà lời giải có thể áp dụng định lý Hall. Một số bài toán khá đơn giản (có thể giải bằng cách tham chiếu đơn giản, chẳng hạn như Hệ quả 1; bạn chỉ cần xem biểu đồ lưỡng cực tương ứng!), một số đã được đề xuất tại các cuộc thi của trường và học sinh ở nhiều cấp độ khác nhau. Bài toán 11–15 được dành cho việc chứng minh và ứng dụng định lý Sperner.

1. Có vô số con trai và vô số con gái. Với mọi số tự nhiên k, đúng là k chàng trai nào cũng biết tổng cộng ít nhất k cô gái. Có phải tất cả các chàng trai trẻ đều có thể cưới những cô gái mà họ quen biết cùng một lúc? Nói cách khác, định lý Hall có đúng trong trường hợp đồ thị vô hạn không? 2. Giải bài toán 1 với giả định rằng tập hợp $^{2}$ bé trai và bé gái là đếm được. 3. Ở một khu vực gồm nhiều làng, số lượng chú rể bằng số lượng cô dâu. Ở mỗi làng, tổng số cô dâu và chú rể không quá một nửa tổng số của họ. Chứng minh rằng có thể tái hôn với tất cả mọi người sao cho trong mỗi cặp cô dâu và chú rể đều đến từ các làng khác nhau. 4. Giải bóng chuyền một vòng gồm 2n đội kéo dài 2n – 1 ngày. Mỗi ngày có n trận đấu, mỗi đội chơi đúng một trận trong một ngày. Kết thúc giải đấu, ban tổ chức quyết định thưởng bánh cho một số đội: cho mỗi trận đấu

1 Bài toán 3 được đưa ra ở giai đoạn III của Olympic Nga dành cho học sinh năm 1995, bài toán 4 – tại Cuộc thi Putnam năm 2012, bài toán 14 – tại Olympic Moscow 2017, bài toán 15 – tại FML 239 Open Olympiad 2004. Phần còn lại bài toán được lấy từ các bộ sưu tập [3, $4].^{2}$ Một tập hợp được gọi là đếm được nếu có sự tương ứng một-một giữa nó và tập hợp các số tự nhiên (nói cách khác, các phần tử của một tập hợp vô hạn đã cho có thể được đánh số bằng số tự nhiên). Tập hợp số tự nhiên, số nguyên không âm, số nguyên và số hữu tỉ đều đếm được.

⟦folio 22⟧

KVAN T 2019/№2

và có đúng một ô của M nằm trên một ô trắng của mặt phẳng, ô trắng này được sơn đen và thực hiện phép dịch tiếp theo. Chứng minh rằng có một ô màu trắng không bao giờ bị sơn đen, cho dù chúng ta dịch chuyển M bao nhiêu lần theo quy tắc đã mô tả.

Thay vì xem xét các ô, chúng ta sẽ xem xét các trung tâm của chúng, chúng ta sẽ gọi là các nút. Do đó, chúng ta có một tập hữu hạn gồm các nút màu đen ban đầu và một mẫu - tập hợp các tâm của đa giác giấy M. Trong bài toán quá trình sau xảy ra: nếu chúng ta có thể đặt mẫu sao cho trong số các nút của nó có chính xác một nút là màu trắng, thì chúng ta có thể đổi màu nút này thành màu đen. Hãy sửa một số vị trí của mẫu $K_{0}$ và vẽ một đường thẳng đứng qua nút ngoài cùng bên trái thuộc $K_{0}$ (Hình 1). (Bởi vì chúng ta không biết

⟦figure⟧

Cơm. 1

các nút đen hoặc trắng rơi vào $K_{0}$; trong Hình 1, chúng được mô tả bằng màu thứ ba - đỏ.) Nếu dòng này không chứa các nút khác của mẫu, thì chúng ta sẽ xoay dòng theo chiều kim đồng hồ cho đến khi một nút khác thuộc $K_{0}$ rơi vào nó. Chúng tôi đã tìm thấy cho mẫu của mình cái gọi là đường thẳng tham chiếu l, chứa ít nhất hai nút mẫu, sao cho tất cả các nút mẫu nằm trong cùng một nửa mặt phẳng L so với đường thẳng l. Bây giờ chúng ta hãy di chuyển song song đường thẳng l cùng với nửa mặt phẳng L sao cho nửa mặt phẳng bao phủ mọi thứ ban đầu

⟦column⟧

⟦figure⟧

Cơm. 2

các nút đen (Hình 2). Trong trường hợp này, đường thẳng l đã đi vào một đường thẳng m nào đó, song song với đường thẳng l. Hãy để chúng tôi chứng minh rằng tất cả các nút trắng ban đầu nằm trong nửa mặt phẳng đối diện với m sẽ luôn giữ nguyên màu trắng. Giả sử điều ngược lại và xem xét thời điểm nút A đầu tiên chuyển sang màu đen. Điều này có nghĩa là nó được bao phủ bởi độ dịch chuyển K của mẫu của chúng tôi. Vẽ đường thẳng a qua A song song với đường thẳng l. Ở một bên của a, tất cả các nút vẫn có màu trắng (vì A là nút duy nhất có thể được tô màu lại), có nghĩa là a là đường tham chiếu cho K. Nhưng sau đó, phép dịch đưa K đến $K_{0}$ đưa đường a đến l, do đó, trên đường a, ngoài A, còn có ít nhất một nút nữa thuộc về K. Như chúng ta thấy, tại thời điểm đổi màu nút A, mẫu K bao phủ ít nhất hai nút trắng. Ta thu được mâu thuẫn hoàn thành lời giải bài toán. Bình luận. Như chúng ta thấy từ lời giải, mẫu có thể tùy ý, do đó tính liên thông của đa giác M từ điều kiện bài toán là không quan trọng. Ngoài ra, từ lời giải bài toán dễ dàng suy ra rằng nếu mẫu không vừa với hàng ngang hoặc hàng dọc thì quá trình sơn lại sẽ là hữu hạn (tức là cuối cùng sẽ có số ô hữu hạn trên mặt phẳng). Lưu ý rằng bài toán có sự khái quát hóa tự nhiên thành một mạng không gian (trong một quy trình tương tự, người ta được phép đổi màu hai nút trắng) hoặc một mạng của không gian hữu hạn chiều. D. Zakharov

$M2537^{*}$. Trên trục số có vô số điểm có tọa độ tự nhiên.

⟦folio 23⟧

NHÂN VIÊN VẤN ĐỀ

dinat. Khi một bánh xe lăn dọc theo trục, mỗi điểm được đánh dấu mà bánh xe đi qua sẽ để lại một dấu chấm trên đó. Chứng minh rằng bạn có thể chọn một R thực sao cho nếu bạn lăn một bánh xe có bán kính R dọc theo trục, bắt đầu từ 0 thì trên mỗi cung của bánh xe có kích thước 1q sẽ có ít nhất một vết được đánh dấu.

Hãy chia chu vi bánh xe thành n = 720 cung có kích thước 0,5q và sơn mỗi cung bằng một màu riêng (chúng ta không sơn các đầu của cung). Hãy lăn bánh xe theo đường thẳng sao cho số 0 tương ứng với ranh giới giữa màu thứ 1 và màu thứ n. Chúng ta giả sử rằng mỗi điểm của đường thẳng được tô màu theo màu của cung đi qua điểm đó. Khi đó đoạn thẳng sẽ được chia thành các đoạn có n màu khác nhau tương ứng với các cung. Chúng ta cần tìm bán kính R hoặc chiều dài của bánh xe S 2 S R sao cho với mỗi màu trong số n màu có một điểm được đánh dấu có màu này. Giả sử chúng ta đã chọn S sao cho với một số k < n thì điều kiện k sau được thỏa mãn: đối với các màu thứ 1, 2, ..., k có một điểm được đánh dấu của màu này. Để thỏa mãn điều kiện thứ nhất, ta lấy S đủ lớn sao cho đoạn đầu tiên của màu thứ nhất che phủ điểm đã đánh dấu. Hãy để chúng tôi chỉ ra rằng, trong khi duy trì điều kiện k, chúng ta có thể thay đổi một chút chiều dài của bánh xe sao cho một số điểm được đánh dấu được tô bằng màu thứ k k, tức là sao cho điều kiện k 1 được đáp ứng. Bằng cách lặp lại quy trình này, cuối cùng chúng ta sẽ đạt được sự đáp ứng của điều kiện n, đó là điều chúng ta cần. Vì vậy, hãy thỏa mãn điều kiện k đối với chiều dài bánh xe S với k < n. Hãy sửa điểm đã đánh dấu của từng màu 1, 2, ..., k. Một sự thay đổi nhỏ về chiều dài của bánh xe tương ứng với tính đồng nhất của một đường thẳng có tâm ở điểm 0 và hệ số gần bằng 1. Rõ ràng là chúng ta có thể chọn hệ số đồng nhất gần bằng 1 để hình ảnh cho k điểm được đánh dấu cố định của chúng ta sẽ không thay đổi: tất cả chúng sẽ vẫn nằm trong các khoảng “kéo dài” có cùng màu. Vì thế,

"QUANTA"

⟦column⟧

có một chữ H như vậy! 0 là khi chiều dài bánh xe thuộc khoảng S; S 1H cho màu thứ 1, thứ 2, ..., thứ k thì vẫn có điểm đánh dấu của màu này. Bây giờ hãy xem xét một điểm Z được đánh dấu “đủ xa”, Z sẽ phù hợp với chúng ta! S 1 H H. Xét màu của đường thẳng sau khi lăn một bánh xe có chiều dài S. Trên đoạn Z S; Bánh xe Z đã tạo thành một vòng tròn nên chắc chắn sẽ có điểm T k màu thứ nhất trên đó. Bây giờ hãy tăng chiều dài của bánh xe lên Z T lần. Nếu bạn lăn một bánh xe có chiều dài mới ZS T thì điểm Z sẽ trở thành màu thứ k. Từ

1 Z T Z Z S

1 S Z S 1 H, điều kiện k vẫn giữ nguyên. Điều này kết thúc bằng lời giải. Bình luận. Như có thể thấy từ lời giải, điều kiện các điểm được đánh dấu có tọa độ tự nhiên có thể được nới lỏng. Chỉ cần tập hợp các điểm được đánh dấu không bị giới hạn ở phía trên là đủ. I. Mitrofanov, P. Kozhevnikov

F2541. Một vòng nhỏ lăn xuống từ đỉnh của một hình trụ nằm ngang không có tốc độ ban đầu (tỷ lệ giữa bán kính vòng và bán kính hình trụ là nhỏ). Hệ số ma sát giữa các bề mặt của hình trụ và vòng là P = 1. Ở góc nào giữa phương thẳng đứng và đường thẳng đi qua tâm vòng và trục của hình trụ (Hình 1) sẽ bắt đầu trượt? 1 gọi một cái vòng trên một hình trụ? Ở góc nào giữa các đường thẳng đó thì cái vòng sẽ tách khỏi hình trụ?

Chuyển động của vòng được chia thành hai giai đoạn: không trượt và có trượt, khi chuyển động quay của vòng chậm hơn chuyển động tịnh tiến của khối tâm. Đầu tiên chúng ta hãy xem xét giai đoạn đầu tiên của phong trào
