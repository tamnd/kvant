---
id: 1985-10-ershov-algoritmicheskiy-yazyik-d36a5fb8
issue: kvant_1985_10
year: 1985
number: "10"
title: Ngôn ngữ thuật toán
authors:
  - Ершов А. П.
rubric: raznoe
rubric_sub: Разное
page_first: 44
page_last: 47
page_labels: 42, 43, 45
tag: DUUZ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 91d8dd979f5d071584adb018dd069e0029927d9b45d822de75ec54a29b8dde0f
prompt_sha256: draft-1
translated_from: content/ru/1985/10/articles/18_ershov-algoritmicheskiy-yazyik-d36a5fb8.md
source_content_sha256: 829c3f3b63f1d7194baff84e755ed8842b85752eefbd4d094271d1019e618094
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 42⟧

Ngôn ngữ thuật toán

Viện sĩ A. P. ERSHOV

Bài viết này tiếp tục phần trao đổi về các khái niệm cơ bản của khoa học thông tin của tác giả ở số trước «Kvant».
Như trước đây, bạn nên chú ý đến những từ in nghiêng - đây là những thuật ngữ mang tính thông tin. Nhưng những từ ngắn in đậm là những từ có ích; chúng chỉ xuất hiện trong các chương trình, thực hiện một số chức năng nhất định trong đó mà bạn nên hiểu.

Trong bài viết trước, chúng ta đã xem xét một số ví dụ về thuật toán. Bây giờ mục tiêu của chúng ta là học cách viết thuật toán “theo tất cả các quy tắc khoa học”. Nhưng trước khi hiểu các quy tắc ra lệnh, bạn nên hiểu lệnh có thể được sử dụng để làm gì. Do đó, chúng tôi sẽ bắt đầu bằng đáp số cho câu hỏi sau:

Người biểu diễn nên có những gì?

1°. Đếm. Người thực hiện không chỉ phải thực hiện nhanh chóng và chính xác cả bốn phép tính số học mà còn phải hiểu thứ tự thực hiện của chúng, “hiểu dấu ngoặc đơn” và tìm ra các giá trị số của các biến. Ví dụ: việc sử dụng tốt sẽ gần như ngay lập tức báo cáo rằng tại $x=0,17$ và $y=1,32$ biểu thức $(x^2+3x)(y^3+5xy)/\sqrt{x^2+xy}$ là 3,66409... và thậm chí sẽ nhanh chóng chỉ ra rằng $\cos 0,29^\circ=0,99998719$... hoặc $\sin(x^2+x)=0,003471$... tại $x=0,17^\circ$. KHÔNG CÓ CON SỐ LỚN HAY KHỐI LƯỢNG TÍNH TOÁN LỚN HƠN CHO NGÀI.

2°. Nhớ. Người biểu diễn có thể nhập dữ liệu được truyền đạt tới anh ta vào những vị trí nhất định (được anh ta biết) trong bộ nhớ của mình. Dữ liệu có thể là giá trị số hoặc văn bản (chữ). Đặc biệt, anh ta có thể nhập một số lệnh hoặc lệnh nối tiếp. Nếu cần thiết, nhà thầu có thể hủy dữ liệu này, thay thế hoặc thay đổi nó. Đặc biệt, các giá trị số thay đổi có thể bị thay đổi nhiều lần trong quá trình thực hiện thuật toán.

3°. Chọn. Người biểu diễn phải có lời giải quyết định về các hành động tiếp theo của mình tùy thuộc vào tình huống. Cụ thể, nó kiểm tra xem một số điều kiện được báo cáo có thỏa mãn hay không và nếu nó được thỏa mãn, nó sẽ sử dụng một lệnh nối tiếp. Sự lựa chọn giữa hai chuỗi lệnh chương trình này được gọi là điều kiện lệnh hoặc nhánh. Tất nhiên, người biểu diễn cũng phải kiểm tra nó.

⟦folio 43⟧

4°. Lặp lại. Người thực thi lặp lại (nhanh chóng và có thể lặp đi lặp lại) cùng một chuỗi lệnh (vòng lặp) cho đến khi đáp ứng một điều kiện nhất định (điều kiện vòng lặp). Anh ta phải kiểm tra điều kiện này trước mỗi lần thực hiện chuỗi lệnh và nếu thấy nó bị vi phạm, anh ta phải chuyển sang điều kiện tiếp theo sau chu kỳ lệnh. Một người biểu diễn giỏi - ví dụ, một máy tính hiện đại - có thể làm việc theo chu trình theo cách này với tốc độ khổng lồ.

5°. Nhớ lại. Trong số các văn bản được ghi lại trong trí nhớ của người biểu diễn, có thể có nhiều dữ liệu khác nhau (số, chữ) mà anh ta phải có khả năng nhớ lại nếu cần. Đặc biệt, các thuật toán phụ trợ có thể được lưu trữ trong bộ nhớ. Người thực hiện tốt ghi nhớ (và thực hiện) từng lệnh một bằng cách hoàn thành mục đích (tên) của họ mà không yêu cầu lặp lại tất cả các lệnh của thuật toán phụ trợ. Chương trình ví dụ này được gọi là một cuộc gọi chương trình con.

6°. Niêm phong. Người thực hiện in (ví dụ: bằng bút chì trên giấy, trên thiết bị in hoặc trên màn hình hiển thị) lời giải bài toán (đáp số), nghĩa là kết quả của chương trình được xây dựng mang tính giáo dục ở đúng vị trí trong trí nhớ của anh ta trong quá trình làm việc. (Nói cách khác, khi làm việc ở chế độ tương tác với khách hàng, người biểu diễn máy tính sử dụng bản in trên màn hình không chỉ khi kết thúc tác phẩm mà còn trong suốt quá trình làm việc để đặt câu hỏi.)

Ví dụ về viết thuật toán

Dưới đây là ví dụ về cách viết thuật toán. Những ví dụ này được thực hiện theo các quy tắc của ngôn ngữ thuật toán được áp dụng trong sách giáo khoa của bạn. Chúng tôi đề xuất đọc chúng cẩn thận và hiểu cách chúng hoạt động, nghĩa là đóng vai trò là người thực thi thuật toán (đối với dữ liệu ban đầu được đề xuất - các giá trị của các đối số). Nếu cách này không hiệu quả ngay lập tức, bạn nên xem lại §§ 2-4 trong sách giáo khoa, đọc các ghi chú chung bên dưới và sau đó quay lại thực hiện các thuật toán. Một bình luận chi tiết lớn được cung cấp ở cuối bài viết. Sau khi đọc chúng, bạn sẽ kiểm tra xem bạn đã thực hiện đúng các thuật toán này chưa và bạn sẽ sẵn sàng viết các chương trình đơn giản bằng ngôn ngữ thuật toán hay chưa.

Đặc biệt, bạn sẽ có thể viết các thuật toán giải bài toán từ bài viết trước trong phần này («Kvant» #9) bằng ngôn ngữ thuật toán. Loại hình tham gia này (bài toán về robot) được trình bày ở trang tiếp theo, phần còn lại sẽ xuất hiện trong một trong những số sắp tới «Kvant».

⟦folio 45⟧

Giải thích chung

Tất cả các mục nhập thuật toán trên đều bắt đầu bằng tiêu đề (được đánh dấu màu xanh lam). Tiêu đề bắt đầu bằng tiêu đề hoặc tên của thuật toán (nó được in bằng chữ in hoa sau thuật toán từ dịch vụ)) và danh sách các tham số (danh sách các đại lượng biến nằm trong ngoặc đơn sau tên của thuật toán). Tiếp theo (sau các từ của đối số) đây là những tham số đầu tiên cần nhập vào máy - nó sẽ điền chúng vào). Tiêu đề kết thúc bằng danh sách kết quả (chúng được liệt kê sau từ res). Chúng ta sẽ giả định rằng máy sẽ in các giá trị của chúng khi sử dụng thuật toán.

Sau khi điền là phần thân của chương trình. Nó bắt đầu bằng từ dịch vụ "bắt đầu", theo sau là tất cả các lệnh kết thúc bằng từ "kết thúc".

Trước tiên chúng ta hãy chú ý đến những lệnh mà máy tính. Có cả những phép tính rất đơn giản (ví dụ: các đơn vị được thêm vào) và những phép tính phức tạp hơn (skem (-b+\sqrt{d})/2a). Những phép tính này được viết theo cách thông thường nhất - cách bạn được dạy trong các bài học toán. Vì vậy, loạt thuật toán ghi này sẽ không gây khó khăn gì cho bạn. Tuy nhiên, cần chú ý đến lệnh gán (dấu :=). Ký hiệu x:=a có nghĩa là máy gán giá trị a cho tham số x (ở đây a có thể là số, văn bản hoặc tham số khác). Trong trường hợp này, máy sẽ cho bạn biết x bằng a. Nếu bây giờ cô ấy phải in x thì cô ấy sẽ in không phải chữ x mà là số (văn bản) a.

Trong phần nội dung của chương trình, để rõ ràng, chúng tôi đã đánh dấu tất cả các nhánh và phần lặp lại bằng màu sắc. Các nhánh được hiển thị ở đây được phân tách bằng mũi tên màu đỏ. Bản ghi nhánh bắt đầu bằng từ dịch vụ if và kết thúc bằng từ dịch vụ all. Sau từ nếu có điều kiện thì đến từ dịch vụ, tiếp theo là chuỗi lệnh đầu tiên, sau đó là giá trị từ dịch vụ và tiếp theo là chuỗi lệnh thứ hai. Chúng ta hãy nhớ lại rằng khi phân nhánh, máy sẽ kiểm tra các điều kiện, sau đó thực hiện chuỗi lệnh đầu tiên (nếu các điều kiện được đáp ứng) hoặc chuỗi lệnh thứ hai (nếu không). Chúng ta có thể nói rằng máy chọn các lệnh nối tiếp mà nó cần. Sau khi sử dụng xong, máy sẽ chuyển sang lệnh tiếp theo.

Sự lặp lại (hoặc chu kỳ) được đánh dấu ở đây bằng các vòng tròn màu vàng. Mỗi chu kỳ mở đầu bằng từ dịch vụ while và kết thúc bằng từ kts (kết thúc chu kỳ). Sau từ bây giờ có các điều kiện vòng lặp, sau đó là từ dịch vụ (bắt đầu vòng lặp), theo sau là một loạt lệnh vòng lặp. Hãy nhớ lại rằng khi sử dụng vòng lặp, máy sẽ chạy vòng quanh để kiểm tra các điều kiện; nếu thỏa mãn, máy sẽ thực hiện một loạt lệnh lặp và kiểm tra lại các điều kiện; nếu nó được đáp ứng một lần nữa, máy sẽ chạy đi kiểm tra chuỗi, v.v. cho đến khi các điều kiện bị vi phạm; sau đó cô ấy chuyển sang lệnh tiếp theo (sau từ kts); nếu không có điều kiện nào bị vi phạm, máy sẽ “hoạt động mãi mãi” - người ta nói rằng nó ở trong một vòng lặp. Để tránh vòng lặp, bạn cần chú ý thoát khỏi vòng lặp, tức là đảm bảo rằng các điều kiện của vòng lặp bị vi phạm.

Thuật toán phụ trợ (chương trình con) được phân biệt bằng tên của nó, cho biết danh sách các biến (trong ngoặc đơn); chỉ định một đối số và kết quả không tuân theo. Máy thực thi chương trình con và gán các giá trị phù hợp cho các biến trong danh sách của nó. Vì vậy, điều quan trọng là phải khớp chính xác tên của các biến này với tên của các biến trong chương trình chính.

Khi tất cả các lệnh chương trình được thực thi (trước từ dịch vụ cuối cùng con), máy sẽ in liên tiếp các giá trị nhận được của các biến đó xuất hiện trong tiêu đề sau từ dịch vụ res (các biến đó không gán bất kỳ giá trị nào). Dấu ngoặc kép đại diện cho giá trị của biến bằng chữ cũng không được in.
