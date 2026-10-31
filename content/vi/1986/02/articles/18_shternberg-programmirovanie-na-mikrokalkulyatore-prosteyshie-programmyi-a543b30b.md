---
id: 1986-2-shternberg-programmirovanie-na-mikrokalkulyatore-prosteyshie-programmyi-a543b30b
issue: kvant_1986_2
year: 1986
number: "2"
title: 'Lập trình trên máy vi tính: các chương trình đơn giản'
authors:
  - Штернберг Л. Ф.
rubric: raznoe
rubric_sub: Разное
page_first: 48
page_last: 50
page_labels: 46-48
tag: 9WI6
lang: vi
source: kvant_digital
extraction: vision
content_sha256: df42f7cb66a70425e3103a1ec4aa93a33b3bbb7da0c300fe80264167a0542724
prompt_sha256: draft-1
translated_from: content/ru/1986/02/articles/18_shternberg-programmirovanie-na-mikrokalkulyatore-prosteyshie-programmyi-a543b30b.md
source_content_sha256: 925ba80d5790a310410ca8c22349d78e9aca36d620a55099c04a709eb022b1c1
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 46⟧

Lập trình trên máy vi tính: các chương trình đơn giản

Ứng viên Khoa học Vật lý và Toán học L. F. STERNBERG

Bài viết này, dành cho học sinh lớp chín, mô tả cách dịch (dịch) các chương trình (tuyến tính) đơn giản nhất được viết bằng ngôn ngữ thuật toán giáo dục, trong đó lập trình máy tính vi mô (VZ-34, MK-56, MK-54). Vì vậy, nếu bạn được tiếp cận với một chiếc máy tính vi mô như vậy, bài viết sẽ giúp bạn kết nối khóa học thông tin về trường học với việc thực hành lập trình.

Thao tác tính toán. Bạn có một máy tính vi mô có thể lập trình trong tay. Nó có thể được coi là một cỗ máy tính toán không, nhỏ đến mức nào? Hãy xem.

— Bộ nhớ có khả năng lưu trữ chương trình và dữ liệu? - Đúng.
— Có bộ xử lý nào có khả năng tự động thực thi chương trình được lưu trong bộ nhớ và xử lý dữ liệu mà không cần sự can thiệp của con người không? - Đúng.
— Bạn có thiết bị đầu vào không? - Vâng, bàn phím.
— Bạn có thiết bị đầu vào không? - Vâng, một dấu hiệu.

Vì vậy, một máy tính là một máy tính. Tất nhiên, nó tiêu thụ ít năng lượng và tốc độ thấp, nhưng vẫn cho phép bạn thực hiện các phép tính khá phía máy chủ và điều quan trọng nhất đối với chúng tôi là cho phép bạn hiểu rõ ràng những quy trình nào trong bất kỳ máy tính nào - cả lớn và nhỏ. Đó là lý do tại sao chúng ta sẽ lập trình máy tính. Nhưng làm thế nào để lập trình nó nếu nó không hiểu ngôn ngữ thuật toán của chúng ta mà chỉ hiểu các lệnh được đưa ra bằng cách nhấn một phím? Điều này có nghĩa là chúng ta cần học cách dịch các thuật toán từ một ký hiệu thuận tiện cho chúng ta thành các lệnh máy tính.

Bản thân máy tính bao gồm những gì và nó có những gì? Cấu trúc của nó*) được hiển thị trong hình 1. Bây giờ, hãy chú ý đến 14 điện trở bộ nhớ nơi dữ liệu sẽ được lưu trữ; chúng có các số 0,1...9, a, b, c, d (không có đủ số - bạn đã lấy các chữ cái chưa); cũng như hai thanh ghi hoạt động X và Y - chính nội dung của các điện trở này sẽ thực hiện các hoạt động. Chúng tôi không quan tâm đến các màn hình khác của sổ đăng ký. "Đèn" được kết nối với thanh ghi X cho biết nội dung của X đang được truy xuất trên chỉ báo.

Tất nhiên, bạn đã đọc hướng dẫn sử dụng máy tính; bạn cũng đã quen thuộc với máy tính kỹ thuật (không lập trình được), vì vậy chúng tôi sẽ không mô tả mục đích của các phím và các thao tác riêng lẻ**). Hãy cố gắng làm việc.

Cho ba cạnh của một tam giác a=3, b=4, c=5, ta cần tính định lý cosin cho góc đối diện a.

(Công thức: cos a = $\frac{a^2+c^2-b}{2bc}$). Chúng tôi bật máy tính và làm việc với nó ở chế độ tự động, nghĩa là giống như với máy tính kỹ thuật thông thường: chúng tôi nhấn các phím và máy tính thực hiện các hành động sau:

| Lớp học | Ấn Độ. | Bình luận |
| :--- | :--- | :--- |
| 3 | 3 | nhập giá trị a=3 |
| P 0 | 3 | trong P0 (đăng ký 0) |
| 4 | 4 | nhập giá trị b=4 |
| P 1 | 4 | trong P1 |
| 5 | 5 | nhập giá trị c=5 |
| P 2 | 5 | trong P2 |
| Fx² | 25 | chúng ta bình phương giá trị của c và gọi giá trị của b trong X (c² chuyển thành Y) |
| Fx² | 16 | hình vuông b=4 |
| + | 41 | chúng ta nhận được b2+c2 |
| IP 0 | 3 | gọi giá trị của a trong X (kết quả trước đó là Y) |
| Fx² | 9 | chúng tôi nhận được a² |
| — | 32 | lấy giá trị tử số và lưu nó trong P4 |
| 2 | 2 | bắt đầu tính 2 b c |
| IP 1 | 4 | ...
| × | 8 | ...
| IP 2 | 5 | ...
| × | 40 | tính được 2 b c |
| IP 4 | 32 | gọi tử số trong X |
| X→Y | 40 | hoán đổi X và Y (bạn cần chia cho mẫu số) |
| ÷ | 0.8 | chúng tôi nhận được kết quả |

* (Bài thuyết trình được thực hiện liên quan đến các mẫu VZ-34, MK-56, MK-54).

**(Xem “Nuki và Cuộc sống” số 2, 4, 6, 8, 10, 12 (1984), số 2, 4, 6 (1985), “Công nghệ cho tuổi trẻ” số 3 (1985), v.v.)

⟦folio 47⟧

Hình 1.

Bây giờ, bằng cách nhấn các phím B/O, F, PRG, chúng ta sẽ chuyển máy tính sang chế độ chương trình (hai số 0 sẽ sáng trên chỉ báo thay cho thứ tự của số), sau đó nhấn các phím tương tự theo cùng một trình tự, thêm phím C/P ở cuối (tại sao cần thiết, nó sẽ được giải thích thêm). Bây giờ, nhấn bàn phím sẽ tạo ra một hiệu ứng hoàn toàn khác: máy tính không thực hiện các hành động cần thiết mà ghi nhớ chúng. Để làm điều này, nó có một bộ nhớ đặc biệt cho các lệnh, bao gồm 98 ô, được đánh số từ 0 đến 97 và một bộ đếm địa chỉ chứa số ô mà hành động tiếp theo sẽ được ghi lại (xem hình 1). Sử dụng phím B/O (trở về 0), số 0 được ghi vào bộ đếm địa chỉ - đây là những gì chúng ta thấy trên chỉ báo sau khi chuyển sang chế độ chương trình. Việc nhấn một phím (hoặc một cặp phím), ở chế độ ngoại tuyến sẽ thực hiện một hành động, giờ đây sẽ khiến mã số của hành động (lệnh) này được ghi vào ô nhớ và bộ đếm địa chỉ tăng lên một. Các giá trị hiện tại của bộ đếm địa chỉ và ba lệnh cuối cùng được hiển thị trên chỉ báo. Vì vậy, chuỗi hành động của chúng ta, được chuyển thành lệnh, kết thúc bằng cặp bàn phím và là một chương trình dành cho máy tính. Bạn có thể đọc nó và sửa lỗi nếu cần - cách thực hiện việc này được mô tả rõ trong hướng dẫn dành cho máy tính.

Nhấn F, ABT để đưa máy tính về chế độ ngoại tuyến. Bằng cách nhấn B/O, chúng ta sẽ ghi số 0 vào bộ đếm địa chỉ (chúng ta không thấy số 0 này trên chỉ báo, nhưng nó sẽ được ghi vào bộ đếm). Bây giờ phím PP sẽ được nhấn. Mỗi lần nhấn sẽ thực hiện một lệnh từ cặp máy tính - cụ thể là lệnh có địa chỉ trong bộ đếm địa chỉ; sau đó, giá trị trong bộ đếm tăng thêm một và lần sau khi bạn nhấn nó, lệnh tiếp theo sẽ được thực thi, chỉ báo sẽ tuần tự hiển thị các giá trị tương tự được đưa ra trong bảng. Sau lần nhấn thứ 22 chúng ta sẽ thấy kết quả - 0,8.

Bằng cách này, bạn có thể kiểm tra chương trình, nhưng đây là cách nó phải được thực thi. Để thực hiện chương trình, có chế độ thứ ba - tự động. Nhấn B/O, nhập số 0 vào bộ đếm địa chỉ và nhấn phím C/P (Stop/Start). Bây giờ máy tính cũng sẽ chọn một lệnh từ một cặp, thực hiện chúng và tăng bộ đếm địa chỉ, nhưng sẽ không còn tồn tại sau mỗi lệnh. Kết quả trên đèn báo sẽ nhấp nháy nhanh đến mức không thể nhìn thấy được. Để xem kết quả cuối cùng, bạn cần thoát khỏi thao tác tự động - vì điều này chúng tôi đã viết lệnh C/P ở cuối chương trình - khi nó được thực thi, máy tính sẽ chuyển từ chế độ tự động sang chế độ ngoại tuyến và bạn có thể xem kết quả.

Vì vậy, người biểu diễn của chúng tôi - một máy tính vi mô - có thể hoạt động
- ở chế độ ngoại tuyến, thực thi các lệnh khi chúng được đưa ra từ bàn phím;
- ở chế độ chương trình, lưu trữ các lệnh được đưa ra từ bàn phím;
— ở chế độ tự động, thực thi các lệnh vào bộ nhớ.

⟦folio 48⟧

Quá trình chuyển đổi từ chế độ này sang chế độ khác được hoàn thành bằng cách sử dụng các lớp F, PRG, AVT và SP như được hiển thị trong hình 2.

Chúng tôi lập trình một thuật toán tuyến tính. Người biểu diễn của chúng tôi hiểu toàn bộ ngôn ngữ đặc biệt - ngôn ngữ của những cú nhấp chuột sang trọng; đối với chúng tôi, việc ghi bằng ngôn ngữ thuật toán sẽ thuận tiện và quen thuộc hơn (xem «Kvant» 1985, số 9, 10). Để lập trình thành công một trình phân loại, chúng ta cần học cách dịch một chương trình từ ngôn ngữ thuật toán sang ngôn ngữ phân loại - như các chương trình chuyên nghiệp nói: dịch nó sang mã phân loại (từ tiếng Anh dịch - dịch). Nói chung, một máy tính hiện đại hiểu tất cả mã gốc, nhưng nó có trình dịch “tích hợp” riêng để dịch chương trình từ ngôn ngữ lập trình sang mã của nó. Đối với bộ phân loại, việc này sẽ phải được thực hiện thủ công.

Hãy viết chương trình của chúng ta bằng ngôn ngữ thuật toán.

cosin tảo
(thứ a, b, c, k)
apr a, b, c
độ phân giải
trọng lượng bắt đầu k
k := b² + c² - a² / 2bc

lừa đảo

Bây giờ chúng ta hãy xây dựng các quy tắc dịch (phát sóng).

1. Sử dụng từ dịch vụ vesh (bộ phân loại không có loại biến nào khác), chúng tôi sẽ phân phối các thanh ghi bộ nhớ cho các biến, ghi vào bảng thanh ghi nào tương ứng với một biến nhất định.

2. Để yêu cầu một giá trị, bộ phân loại phải ở lại và đợi người đó nhập giá trị mong muốn, sau đó chạy nó vào thanh ghi thích hợp, sau đó đợi giá trị tiếp theo, v.v. Do đó, apr được lập trình với một chuỗi các lệnh gửi bộ nhớ, được phân tách bằng các lệnh C/P.

3. Bài tập được lập trình theo một cách rất khác.

4. Nếu kết quả từ xứng đáng chỉ có một tham số thì không cần dịch kết quả. Nếu có một số tham số như vậy thì ở cuối chương trình, trước từ con, bạn cần lập trình đầu ra của các tham số này bằng một chuỗi lệnh để gọi thanh ghi X

các giá trị đã nhập, mỗi giá trị được theo sau bởi lệnh C/P áp dụng các phép tính.

5. Con được lập trình bằng lệnh C/P.

Lưu ý rằng có thể có nhiều lệnh C/P trong một chương trình. Khi chuyển sang chế độ tự động bằng lệnh C/P, bộ đếm địa chỉ chứa địa chỉ của lệnh tiếp theo (có thể kiểm tra điều này bằng cách nhấn F, PRG, nghĩa là nó sẽ chuyển sang chế độ chương trình khi giá trị của bộ đếm địa chỉ hiển thị trên chỉ báo, sau đó bạn sẽ cần quay lại chế độ tự động bằng cách nhấn F, ABT); Nếu bây giờ bạn nhấn C/P, thì lệnh bắt đầu được thực thi, địa chỉ của lệnh này nằm trong bộ đếm địa chỉ, tức là lệnh tiếp theo sau C/P - lệnh được tính toán thêm.

Hãy phát triển chương trình của chúng tôi.

Mã địa chỉ Com

a — P0
b — P1
c — P2
k — P3

00 40 P0
01 50 C/P
02 41 P1
03 50 C/P
04 42 P2

05 61 IP 1
06 22 F x²
07 62 IP 2
08 22 F x²

09 10 +
10 22 F x²
12 11 —
13 44 P4
14 02 2

15 61 IP 1
16 12

17 62 IP 2
18 12
19 64 IP 4
20 14 X↔Y

21 13 ÷

cosin tảo
sự việc a, b, c, k)
đại số a, b, c
độ phân giải

[Sau đó nhập a, b, c.] [Trước lần gửi đầu tiên bạn không cần nhập C/P (trước chương trình tiếng Nga, bộ phân loại ở chế độ tự động), bạn cần nhập các giá trị của a và nhấn C/P]
k := (b² + c² - a²)/(2bc)
[Chúng tôi làm việc đúng theo công thức: tính giá trị b2, rồi c2, cộng, v.v.]
[Rõ ràng là chúng ta sẽ nhận được kết quả, nhưng chúng ta có thể làm điều đó nhanh hơn: sau khi nhập X vào sổ đăng ký, chúng ta có thể sử dụng nó ngay lập tức.] [Bạn có thể kết hợp một số lệnh, nếu bạn đếm như thế này: k := (b² + c² - a²)/2/b/c và lập trình giá trị thành 2, sau đó đến b và cuối cùng là c.]
Chúng tôi nhận được kết quả. Đừng quên tắt bộ phân loại!

Vì vậy, nó hoạt động theo quy tắc định dạng thuần túy, chúng ta sẽ có một chương trình cho bộ phân loại, nhưng nó sẽ không tối ưu. Một mặt, trên (Cuối cùng, xem trang 57)
