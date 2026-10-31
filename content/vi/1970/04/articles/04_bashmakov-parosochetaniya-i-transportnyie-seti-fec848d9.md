---
id: 1970-4-bashmakov-parosochetaniya-i-transportnyie-seti-fec848d9
issue: kvant_1970_4
year: 1970
number: "4"
title: Mạng lưới giao thông và kết nối
authors:
  - Башмаков М. И.
rubric: osnovnye-stati
page_first: 18
page_last: 25
page_labels: 16, 17, 18, 19, 21, 22, 23
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 2278c181575ea2c13721dede24a6395dc737f1935c34893b65b4ee67be01113d
prompt_sha256: draft-1
translated_from: content/ru/1970/04/articles/04_bashmakov-parosochetaniya-i-transportnyie-seti-fec848d9.md
source_content_sha256: a95995f5dfbf55f88111a3ff194dbf54e2d1fdc28ddd22f2b1b06b509f8a3002
translation_model: draft
translation_run: vi-draft-gaps-2026-10-31
translation_quality: draft
---

⟦folio 16⟧

1. Định lý về mai mối

Chúng ta hãy suy nghĩ về việc xây dựng định lý. Có một công ty gồm $n$ thanh niên, mỗi người là bạn của một hoặc vài căn hộ hai phòng. Câu hỏi mà chúng tôi quan tâm là như sau: trong những điều kiện nào mỗi chàng trai trẻ trong số $n$ có thể chọn một cô dâu trong số những người bạn gái của mình (vì vậy, tất nhiên, không một cô gái hai phòng nào được hai chàng trai chọn cùng một lúc).

Hãy thử tìm hiểu xem có thể sắp xếp việc mai mối như vậy theo hai ví dụ $a$ và $b$) được đưa ra ở hình 1. Đây $n=6$; Đồng kopeck và những chàng trai trẻ được miêu tả dưới dạng các dấu chấm, và từ mỗi đồng kopeck, các mũi tên được vẽ về những chàng trai trẻ là bạn của nó. Sắp xếp mai mối có nghĩa là chọn (ví dụ: khoanh tròn bằng bút chì) sáu mũi tên, nhìn từ sáu căn hộ hai phòng khác nhau đến tất cả sáu chàng trai trẻ khác nhau.

Hóa ra ví dụ $a$ điều này có thể được thực hiện *). Và trong ví dụ $b$), dù có cố gắng đến mấy cũng không thể thuyết phục được tất cả các chàng trai trẻ kết hôn. Không khó để giải thích tại sao. Sự thật là bốn chàng trai trẻ - Ilya, Kolya, Mark và Nikita - chỉ là bạn kể từ mảnh kopeck thứ ba - Belaya, Ve*

*) Một trong lời giải bài toán được nêu ở trang 18 (hình 2). Có lời giải khác.

Hình 1

16

⟦folio 17⟧

Chỉ có thể có hai trường hợp:
Trường hợp 1. Đối với một số $k$ ($1 \leq k < n$) có một nhóm gồm $k$ con trai là bạn (tất cả cùng nhau) với đúng $k$ con gái.

Chúng ta hãy biểu thị tập hợp những chàng trai trẻ này bằng $IO_k$ và tập hợp bạn gái của họ bằng $Д_k$. Đối với nhóm nam $IO_k$ câu cảm ứng đã hoàn thành. Đồng thời, cô dâu của họ cạn kiệt toàn bộ bộ $Д_k$ (các cô gái $k$ không đồng đều). Chúng ta hãy loại những chàng trai và cô gái này ra khỏi sự xem xét và chứng minh bằng phản chứng rằng điều kiện của định lý được thỏa mãn đối với $n - k$ chàng trai còn lại.

Chúng ta hãy chọn từ $n - k$ thanh niên này một công ty có $r$ thanh niên. Giả sử rằng số lượng bạn bè của họ $s$ hóa ra ít hơn $r$. Hãy quay trở lại đúng hướng và đoàn kết những chàng trai trẻ $r$ này với nhóm $IO_k$. Có $r + k$ nam thanh niên trong nhóm mới. Vì bộ $D_k$ chứa tất cả bạn gái của các chàng trai từ $IO_k$ (và, có thể, một số bạn gái khác của các chàng trai $r$ từ công ty được hiển thị), nên những chàng trai $k + r$ này đã có $k + s$ bạn gái ngay từ đầu. Theo điều kiện ban đầu $k + r \leq k + s$. Vì vậy, $r \leq s$. Kết quả là mâu thuẫn với đề xuất $s < r$. Điều này có nghĩa là trong trường hợp này định lý là đúng.

Trường hợp 2. Bất kỳ nhóm $k$ con trai ($1 \leq k < n$) nào cũng là bạn của ít nhất $k + 1$ con gái.

Trong trường hợp này mọi thứ đều đơn giản. Chúng tôi gả bất kỳ chàng trai trẻ nào cho bất kỳ bạn gái nào của anh ta. Hãy loại trừ cặp này khỏi việc xem xét. Hãy chứng minh rằng các điều kiện của định lý được thỏa mãn với $n - 1$ bé trai còn lại. Hãy lấy bất kỳ nhóm $k$ nam thanh niên nào ($k \leq n - 1$). Lúc đầu họ có ít nhất $k + 1$ bạn gái. Rồi cô dâu của chàng trai được chọn sẽ đến đây, rồi vẫn còn lại $k$ cô gái. Điều này hoàn toàn chứng minh định lý.

Niềm tin, bạn phải bỏ ra một số điều kiện để hiểu được cách chứng minh này. Nhưng, bên cạnh việc chứng minh không đơn giản, nó còn có một nhược điểm quan trọng - nó không chỉ ra một cách đơn giản để tìm hiểu xem điều kiện của định lý mai mối có thỏa mãn cho từng trường hợp cụ thể hay không, và nếu thỏa mãn thì làm thế nào để chọn được cô dâu, bạn cần phải đi qua tất cả các tập hợp con không công bằng (và có $2^6 - 1 = 63$) tập hợp nam thanh niên và với mỗi tập hợp con nam thanh niên này hãy kiểm tra xem họ có đủ bạn gái hay không. Nhưng ngay cả khi chúng tôi làm điều này và đảm bảo rằng, về nguyên tắc, có thể sắp xếp tất cả các đám cưới, thì từ đây chúng tôi sẽ không nhận được gợi ý ai sẽ cưới ai. Đúng, trong ví dụ này $a$ bạn chắc chắn đã dễ dàng chọn được sáu cặp cần thiết (thậm chí có một số tùy chọn khả thi), nhưng khi các bộ rất lớn thì việc chọn ngẫu nhiên chỉ mất rất nhiều thời gian. Điều đặc biệt quan trọng là phải có quy tắc lựa chọn rõ ràng và tiết kiệm để giao phó lời giải bài toán loại này cho một chiếc máy tính.

Chúng tôi sẽ xây dựng một số thuật toán *), thuật toán này không chỉ chứng minh lại định lý mai mối mà còn cung cấp một cách nhanh chóng để sắp xếp việc mai mối cần thiết, và nếu điều này là không thể thì hãy chỉ ra phương án cho số lượng đám cưới tối đa.

3. TIỆC CƯỚI VÀ TÒA ÁN

Một hệ thống các điểm được kết nối bằng cách nào đó bằng các mũi tên được gọi là đồ thị có hướng*). Trong trường hợp này, các điểm được gọi là các đỉnh của đồ thị và các đoạn được gọi là các đường hoặc cạnh của đồ thị. Ví dụ về đồ thị có hướng đã được trình bày trong cuộc thảo luận hình 1, cũng như trong Hình 3 và 5. Trong trường hợp của Hình 1, tập hợp tất cả các đỉnh của đồ thị được chia thành hai tập hợp - bé gái và bé trai - sao cho các cạnh đi từ điểm của tập hợp này đến điểm của tập hợp kia. Trong tình huống như vậy

*) Chuỗi hành động cho lời giải thuộc một loại nhất định bài toán. Người Muscites đã được hứa hẹn về một thuật toán, Leningraders - một thuật toán. Hiện tại là trang thứ hai của trang.

⟦folio 18⟧

biểu đồ được gọi là đơn giản hoặc lưỡng cực, và bài toán, điều khiến chúng tôi bận tâm cho đến nay, là sắp xếp một cách an toàn cuộc sống cá nhân của số lượng bé gái và bé trai tối đa - vấn đề khớp tối đa.

Bài toán về mai mối có thể được xây dựng bằng biểu đồ như sau. Chọn từng cặp gái-trai có nghĩa là chọn một cạnh của đồ thị. Chúng ta gán số 1 cho mỗi cặp ở cạnh brane của đồ thị và số 0 cho mỗi cặp còn lại. Sau khi sắp xếp tất cả các đám cưới, chúng ta thu được một hàm có miền là tất cả các cạnh của biểu đồ và tập hợp các giá trị là hai số 0 và 1*). Làm cách nào chúng ta có thể đặt tất cả các điều kiện khác bài toán vào hàm này? Chúng ta cần mỗi chàng trai chọn một cô gái, và mỗi cô gái chỉ được chọn bởi một chàng trai. Nói cách khác, đối với mỗi đỉnh của đồ thị mô tả một cô gái, tổng các giá trị hàm dọc theo tất cả các cạnh rời khỏi nó không được lớn hơn một, và đối với mỗi đỉnh mô tả một cậu bé, tổng các giá trị hàm cho tất cả các cạnh đi vào nó phải chính xác bằng một.

Do đó, bài toán của chúng tôi được xây dựng dưới dạng bài toán tìm một số hàm được xác định trên các cạnh của biểu đồ và thỏa mãn một số bất đẳng thức**).

Một trong lời giải của bài toán này (trong trường hợp ví dụ a)) được mô tả trong hình 2, trong đó các cạnh được chọn là đầu. Hàm cần tìm có dạng sau:

Anya - Kolya, Bela - Ilya, Vera - Leva, Dasha - Osya, Zhanna - Mark, Zina - Nikita, Anya - Nikita, Vera - Ilya, Galya - Kolya, Dasha - Leva, Dasha - Mark, Dasha - Nikita, Eva - Leva, Zhanna - Leva

*) Xem bài viết của A. N. Kolmogorov “Hàm là gì” ở số 1 «Kvant».
**) Lưu ý rằng đẳng thức f=1 có thể được viết dưới dạng hệ gồm hai bất đẳng thức: f ≥1 và f<1.

⟦folio 19⟧

Naimporta từ phần còn lại của chủ đề hôn nhân. Bản thân các hệ thống truyền thông được biểu diễn bằng đồ thị. Ví dụ: khi giám sát việc thực hiện một nhóm công việc phức tạp, các giai đoạn trung gian riêng lẻ được chỉ định bởi các đỉnh của biểu đồ và các mũi tên kết nối những giai đoạn phụ thuộc lẫn nhau (hình 3). Biểu đồ được đặt ở trang 14 (màn hình giới thiệu cho trạng thái này) hiển thị cách các phần của nó được kết nối; từ đó có thể thấy rõ ngay lập tức, ví dụ, mệnh đề 3 có thể được đọc bất kể mệnh đề 2 có rõ ràng hay không. Khi một biểu đồ được đưa ra, thì bài toán thường được đặt cho nó, điều này được kết nối về mặt toán học với việc tìm các hàm thỏa mãn các bất đẳng thức nhất định. Onunu của họ - bài toán về sravvostvo chúng tôi đã xem xét. Hãy đặt một bài toán tương tự khác (không giải nó).

Nhiệm vụ. Di chuyển quân mã xung quanh bàn cờ $8 \times 8$, bắt đầu và kết thúc ở các ô đã cho.

Chúng ta vẽ một biểu đồ (hình 4) với 64 đỉnh (các trường của bàn cờ) và nối các cạnh (trong trường hợp này là các đoạn thẳng) của mỗi đỉnh với các cạnh có thể tới được bằng cách di chuyển quân mã. Cho đến khi chúng ta bắt đầu với lời giải bài toán, hướng chuyển động không quan trọng đối với chúng ta và chúng ta có thể vẽ các cạnh của biểu đồ mà không cần mũi tên (đồ thị vô hướng); Hoặc bạn có thể vẽ một cặp mũi tên theo hai hướng ngược nhau trên mỗi cạnh.

Hàm được yêu cầu phải cung cấp số 2 cho mỗi đỉnh trung gian và một cho đỉnh đầu tiên và đỉnh cuối cùng.

4. MẠNG VÀ Stream

Bây giờ chúng ta sẽ xem xét một số loại biểu đồ đặc biệt - mạng và một loại hàm đặc biệt trên biểu đồ - luồng như vậy. Hãy nhìn lại biểu đồ (xem trang 14). Nó có hai đỉnh cực trị - “đầu vào” (1. Định lý mai mối) và “đầu ra” (Bài toán). Đồ thị có hướng có đầu vào và đầu ra được gọi là *nhóm truyền tải* hoặc đơn giản là *nhóm*. Một ví dụ về mạng như vậy được hiển thị trong hình 5, a.

*Trợ giúp* trên một mạng nhất định là một hàm trên các cạnh của biểu đồ lấy (trong trường hợp đơn giản nhất) các giá trị 0 và 1 và thỏa mãn điều kiện sau: đối với mỗi đỉnh trung gian (tức là khác với đầu vào và đầu ra), tổng các giá trị luồng dọc theo tất cả các cạnh đi vào đỉnh này bằng tổng các giá trị trên tất cả các cạnh rời khỏi nó.

Tên “vận chuyển bảy” và “dòng chảy” có thể được tính như sau.

Hãy tưởng tượng một thành phố với sự phát triển của hệ thống đường (cạnh) và nút giao (đỉnh), trên mỗi đường có giao thông một chiều và chỉ có một ở mọi nơi vào thành phố và một ở khắp mọi nơi từ thành phố.

Dòng xe ô tô liên tục đi qua thành phố và giao thông được tổ chức sao cho không xảy ra ùn tắc giao thông ở bất kỳ ngã tư nào. Trong trường hợp đơn giản nhất đang được xem xét, chúng tôi giả sử rằng tất cả các đường phố mà dòng xe chạy qua đều có tải trọng như nhau (có cùng sức chứa, thường được coi là một).

Trong trường hợp tổng quát hơn, mỗi cạnh được gán một số nguyên dương - trọng số hoặc dung lượng. (Trong ví dụ của chúng tôi

⟦folio 21⟧

Sức chứa của đường phố là số lượng ô tô có thể đi qua một “mặt cắt ngang” đường phố trong một đơn vị thời gian.)

Thay vì nói “một luồng được xác định trên mạng”, người ta thường nói “một luồng được truyền qua mạng”. Rõ ràng, dòng chảy không để lại gì ở các đỉnh trung gian, và do đó mang đến lối ra cùng số lượng va chạm đã đi qua lối vào. Tổng giá trị thông lượng dọc theo tất cả các cạnh rời khỏi đầu vào, bằng tổng giá trị dọc theo tất cả các cạnh đi ra đầu ra, được gọi là giá trị thông lượng.

hình 5,6 hiển thị luồng trên mạng hình 5,a. Các cạnh mạng mà trên đó các giá trị của luồng này bằng 1 được mô tả dưới dạng các đầu. Giá trị dòng chảy là 3.

Có thể dễ dàng nói rằng để một luồng có kích thước n đi qua mạng thì phải đáp ứng các điều kiện cần thiết sau: nếu bất kỳ k cạnh nào bị ngắt kết nối khỏi mạng, trong đó k<n, thì có thể chuyển từ đầu vào đến đầu ra dọc theo các cạnh còn lại.

Điều đáng chú ý là (giống như trong định lý mai mối) điều kiện cần này hóa ra lại đủ.

Một chuỗi kinh tế thực bài toán dẫn đến việc tìm ra luồng tối đa, tức là luồng có giá trị cao nhất có thể được truyền qua một mạng nhất định.

Bây giờ chúng ta sẽ giải quyết việc mô tả thuật toán giúp xây dựng luồng cực đại.

5. Thuật toán
FORD-FALKERSON

Hãy để chúng tôi có một mạng lưới giao thông (hình 5,a). Nhiệm vụ của chúng tôi là xây dựng luồng tối đa cho nó.

Giả sử có một số luồng ban đầu dọc theo mạng này (trong trường hợp cực đoan là 0, nghĩa là luồng có giá trị trên mỗi cạnh bằng 0).

Chúng ta sẽ bắt đầu với thông lượng khác 0 (hình 5,6). Các cạnh mà dòng chảy này đi qua (chúng được tạo bởi các đầu) sẽ được gọi là bão hòa và phần còn lại (màu vàng) - tự do. Kiểm tra xem luồng của chúng tôi không thể tăng lên nếu không chạm vào những luồng đã bị chiếm dụng (bạn không thể kết nối đầu vào với đầu ra bằng cách chỉ di chuyển dọc theo các mũi tên tự do).

Bây giờ chúng ta sẽ thực hiện một số thao tác dẫn đến hai kết quả có thể xảy ra: hoặc nó sẽ được hiển thị cách tăng luồng này hoặc người ta sẽ thấy rằng luồng hiện có là lớn nhất.

Hãy đặt "cộng" và "trừ" lên trên cùng của mảnh đất. Chúng ta hãy đánh dấu bằng khóa phẳng tất cả các đỉnh có thể đạt được từ lối vào dọc theo các cạnh tự do. Quá trình đặt tiếp theo sẽ tùy ý: từ đỉnh đã được đặt, chúng ta sẽ đặt phẳng các đỉnh mà người ta có thể lấy từ nó dọc theo các cạnh tự do và trong một phút - tất cả các đỉnh mà người ta có thể quay trở lại từ nó (theo hướng đối diện với mũi tên) dọc theo các cung bão hòa. Đừng nhầm lẫn bởi thực tế là quá trình đặt không đáng kể - thường thì cùng một đỉnh có thể được đặt bằng cả dấu cộng và phút.

Chúng ta hãy đánh dấu tất cả các đỉnh có thể có theo cách này (không có đỉnh nào không được đặt trên hình 5,6; nhưng trong các trường hợp khác chúng có thể xuất hiện!).

Có thể xảy ra hai trường hợp: 1) chúng tôi đã cố gắng đặt đầu ra (tất nhiên là có dấu cộng); 2) không thể tạo thêm mặt bằng mà lối ra vẫn chưa xong.

1) Hóa ra m đã được đặt ở đầu ra. (Điều này xảy ra ở hình 5,6.) Hãy để chúng tôi khôi phục thứ tự mà chúng tôi đã quản lý để đặt đầu ra*), nghĩa là chúng tôi kết nối đầu ra với đầu vào bằng một đường đi dọc theo các đỉnh dự định (trong một số trường hợp, đường dẫn này có thể đi

*) Các vị trí thực tế (trong đồ thị có số đỉnh lớn) làm cho chi tiết trở nên phức tạp hơn nhằm lưu trữ thông tin về thứ tự đặt các đỉnh.

⟦folio 22⟧

theo hướng ngược lại với hướng mũi tên).

Đường dẫn này ở hình 5.6 được đánh dấu bằng đường màu đỏ.

Bây giờ chúng ta sẽ làm như sau: trong đường dẫn màu đỏ đã chọn, chúng ta sẽ làm cho các mũi tên tự do bão hòa và ngược lại (hình 5,8), tức là chúng ta sẽ thay đổi luồng trên đường màu đỏ để nó nhận trên mỗi cạnh của nó giá trị 1 cùng với 0 và 0 cùng với 1*). Dễ dàng nhận thấy rằng hàm mới lại là một luồng, tức là tại các đỉnh trung gian, số lượng mũi tên bão hòa đến và đi lại giống nhau - sự cân bằng không bị vi phạm. Đồng thời, bề mặt của dòng chảy tăng thêm một đơn vị.

Vì vậy, trong trường hợp đầu tiên, chúng ta có thể tăng lưu lượng. Nếu thao tác này có thể được thực hiện lại, chúng tôi sẽ lặp lại nó càng lâu càng tốt.

2) ĐẦU RA KHÔNG ĐƯỢC ĐÁNH DẤU (hình 5,2). Phương pháp của chúng tôi không thể tăng lưu lượng. Nhưng từ đó nó vẫn chưa đạt mức tối đa. Có thể phương pháp tăng của chúng tôi không tốt và chúng tôi có thể tăng lưu lượng theo cách khác. Hãy để chúng tôi chứng minh rằng đây không phải là trường hợp, tức là chúng tôi sẽ chứng minh rằng luồng hiện tại là tối đa. Hãy xem xét tập hợp tất cả các đỉnh không được đặt. Theo điều kiện, bộ này bao gồm đầu ra. Hãy đếm số lượng mũi tên dẫn đến bộ này, tức là những mũi tên có đầu bên trái được đặt nhưng đầu bên phải thì không. Rõ ràng là độ lớn của bất kỳ dòng chảy nào cũng không lớn hơn con số này. Đồng thời, đối với luồng của chúng ta, tất cả các mũi tên này đều bão hòa, vì nếu không thì đầu bên phải có thể được đặt phẳng. Ngoài ra, tất cả các mũi tên đến từ tập hợp các đỉnh không được đặt (nghĩa là những mũi tên có đầu bên trái không được đặt và đầu bên phải được đặt) đều tự do, nếu không thì đầu bên trái có thể được đặt trong một phút. Điều này có nghĩa là kích thước của luồng ban đầu bằng số lượng mũi tên rời khỏi

6. ĐỊNH NGHĨA GAYLE
GIỚI THIỆU VỀ BÃO HÒA

Sử dụng thuật toán Ford-Falkerson, bây giờ chúng ta sẽ xây dựng và chứng minh định lý trung tâm của lý thuyết mạng lưới giao thông. Công thức này sẽ sử dụng một số thuật ngữ kinh tế tự nhiên, nhưng bạn sẽ cảm thấy nó gần với định lý mai mối đến mức nào.

Hãy để chúng tôi được cung cấp một mạng lưới giao thông. Hãy xem xét một tập hợp các đỉnh tùy ý $A$ (tức là không chứa đầu vào cũng như đầu ra). Chúng ta hãy xác định công suất của bộ $A$ này là số lượng mũi tên đi tới $A$. Hãy ký hiệu con số này

⟦folio 23⟧

qua $c(A)$. Chúng ta hãy xác định theo tổng yêu cầu của tập hợp $A$ số cạnh dẫn từ $A$ trực tiếp đến lối ra. Hãy biểu thị số này bằng $d(A)$.

Chúng ta hãy nghiên cứu câu hỏi sau: trong những điều kiện nào tồn tại một luồng bão hòa tất cả các cạnh đầu ra, tức là một luồng có giá trị trên tất cả các cạnh dẫn đến đầu ra bằng một. Rõ ràng là dòng chảy như vậy phải đạt mức tối đa.

Định lý Gale. Đối với bất kỳ số nào, có một luồng bão hòa tất cả các cung đầu ra; điều cần và đủ là đối với bất kỳ bộ $A$ nào, tổng nhu cầu của nó không vượt quá khả năng:

$$d(A) \leq c(A).$$

Bằng chứng. Giống như định lý mai mối, tính tất yếu gần như là một bước ngoặt. Thật vậy, nếu chúng ta có thể xây dựng một luồng đi dọc theo tất cả các cạnh dẫn đến lối ra, thì đối với bất kỳ tập hợp $A$ nào, nó cũng đi dọc theo các cạnh dẫn đến lối ra chỉ từ $A$. Đồng thời, số luồng dẫn đến tập hợp $A$ không thể lớn hơn số cạnh dẫn đến $A$, tức là các số $c(A)$. Nhưng lượng dòng chảy này phải hoàn toàn rời khỏi $A$ dọc theo tất cả các cạnh dẫn đầu đến lối ra và có thể dọc theo một số cạnh khác. Từ đó rõ ràng là $d(A) \leq c(A)$.

Sự đầy đủ. Hãy để có lưu lượng tối đa thông qua mạng của chúng tôi. Hãy để chúng tôi chứng minh rằng nó đi dọc theo tất cả các cung đầu ra. Hãy dán nhãn các đỉnh bằng phương pháp Ford-Folkerson và xem xét tập hợp các đỉnh không được gắn nhãn. Hãy loại bỏ đầu ra khỏi bộ này. Chúng tôi biểu thị tập hợp kết quả bằng $A^*$. Các đường gân dẫn đến lối ra có thể có hai loại.

Thứ nhất, đây cũng là những cạnh có điểm cuối nằm ở $A$, tức là là một đỉnh được gắn nhãn. Chúng sẽ bị bão hòa, vì theo phương pháp xây dựng luồng, tất cả các cạnh có đầu bên trái được đặt nhưng đầu bên phải thì không, đều bị bão hòa.

Thứ hai, đây là các cạnh dẫn đến việc thoát khỏi tập hợp. Vì $A$ cùng với lối ra tạo thành tập hợp tất cả các đỉnh không được gắn nhãn, nên tất cả các cạnh $c(A)$ dẫn đến $A$ sẽ bị bão hòa và tất cả các cạnh dẫn từ $A$ không trực tiếp đến lối ra sẽ được tự do.

*) Tập $A$ có thể trống - lý luận của chúng ta vẫn đúng. Nhưng trong trường hợp này, giá trị của định lý Gale được thể hiện ngay lập tức. Tại sao?

Điều này có nghĩa là toàn bộ luồng giá trị $c(A)$ đã nhập $A$ phải thoát trực tiếp $A$ đến lối ra. Nhưng từ $A$ chỉ có $d(A)$ mỗi cái đều dẫn đến lối ra và chúng ta biết rằng $d(A) \leq c(A)$. Do đó, tất cả các cạnh này đều bão hòa và $d(A) = c(A)$.

Bạn có thể nhận thấy rằng các điều kiện của định lý Gale tương ứng với các điều kiện của định lý đám cưới. Hãy thử tự mình suy ra định lý này như một hệ quả của định lý Gale. Để làm điều này, bạn cần tạo một mạng lưới xuyên suốt từ biểu đồ lưỡng cực về sự quen biết giữa con trai và con gái, kết nối đầu vào với tất cả con gái và đầu ra với tất cả con trai (khi đó sẽ thuận tiện khi gán trọng số $N$ cho mỗi mũi tên nối con gái với con trai, trong đó $N$ lớn hơn số con trai).

Điều quan trọng hơn nhiều đối với chúng ta bây giờ không phải là chúng ta đã thu được một bằng chứng khác về định lý mai mối, mà là chúng ta có một thuật toán đơn giản để xây dựng các luồng cực đại.

Đối với bài toán về thuật toán mai mối, quy trình được xây dựng một cách tự nhiên như sau: đối với mỗi cô gái không phải là cô dâu, tất cả bạn bè của cô ấy sẽ được xếp phẳng, sau đó trong một phút - cô dâu của những người bạn này, sau đó những người bạn còn lại của những cô dâu này sẽ được xếp phẳng, v.v.; nếu một chàng trai trẻ không có người ở được bố trí, thì số lượng đám cưới có thể tăng lên bằng cách thay thế dọc theo sợi dây được vẽ (như đường màu đỏ trên hình 5,6) dọc theo các dấu từ cô gái không có người ở đến chàng trai không có người ở.

Việc sắp xếp đám cưới cho tất cả các chàng trai trẻ không gì khác hơn là xây dựng một dòng chảy bão hòa tất cả các lối ra; nếu không có thứ đó thì thuật toán Ford-Folkerson sẽ đưa ra thuật toán mới thú vị nhất có thể cho chuỗi lời giải của toán học hữu hạn bài toán khó.
