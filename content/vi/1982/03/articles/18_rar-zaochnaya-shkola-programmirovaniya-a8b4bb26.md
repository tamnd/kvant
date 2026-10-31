---
id: 1982-3-rar-zaochnaya-shkola-programmirovaniya-a8b4bb26
issue: kvant_1982_3
year: 1982
number: "3"
title: Trường lập trình tương ứng
authors:
  - Рар А.
rubric: raznoe
rubric_sub: Разное
page_first: 54
page_last: 58
page_labels: 52, 55, 56
tag: AL95
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 67e3b52ed6500919ccab0692eb3ae03a1e7b9096d4bb8ea074c93dc15cb7dc03
prompt_sha256: draft-1
translated_from: content/ru/1982/03/articles/18_rar-zaochnaya-shkola-programmirovaniya-a8b4bb26.md
source_content_sha256: 635ddf15ceb240dbf518964151bf160f5b2ba594dcc6e757e70004c0de716511
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 52⟧

trường thông tin
lập trình
Bài học 19:
Cấu trúc động

Có bài toán, trong đó thuận tiện hơn khi có cấu trúc dữ liệu linh hoạt hơn mảng, bản ghi và tệp. Ví dụ: tôi muốn có thể thay đổi thứ tự các phần tử của cấu trúc dữ liệu, chèn các phần tử mới vào đó và loại bỏ các phần tử không cần thiết. Vấn đề ở đây là cấu trúc có thể thay đổi phạm vi trong quá trình lời giải bài toán (cho đến nay trong Pascal chúng ta chỉ xử lý các cấu trúc tĩnh được xác định một lần và mãi mãi tại thời điểm chương trình được viết). Các cấu trúc động không được xác định cụ thể trong ngôn ngữ, chẳng hạn như các mảng được xác định, nhưng chúng có thể được xây dựng bằng một số công cụ ngôn ngữ mà bây giờ chúng ta sẽ nói đến.

Con trỏ và biến trỏ được
Ví dụ, trong các chương trình Pascal, bạn có thể sử dụng các kiểu con trỏ với các kiểu đã biết. Kiểu con trỏ được xác định bằng sơ đồ cú pháp.

Do đó, mỗi loại $t$, tiêu chuẩn hoặc được mô tả trong chương trình, có thể được liên kết với một loại con trỏ $\uparrow t$. Giá trị thuộc loại $\uparrow t$ là một con trỏ (hoặc tương đương, tham chiếu tham chiếu) trỏ đến một số giá trị thuộc loại $t$.

Sẽ thuận tiện nhất khi coi con trỏ là địa chỉ của vị trí trong bộ nhớ máy nơi chứa giá trị mà nó trỏ tới.

Giống như trong toán học, bạn cần số 0 để biểu thị sự vắng mặt của các đối tượng, trong lập trình, bạn cần có một con trỏ null để không trỏ đến bất kỳ thứ gì (hoặc, giống như vậy, không trỏ đến không có gì). Hằng số tiêu chuẩn nil đóng vai trò như một con trỏ như vậy. Bất kỳ loại con trỏ nào cũng có nó trong số các giá trị của nó.

Đặt một số biến $P$ (chúng tôi gọi nó là biến con trỏ) có loại $\uparrow t$. Gọi một thủ tục tiêu chuẩn

new(P)

sẽ phân bổ không gian trong bộ nhớ cho giá trị *) mới thuộc loại $t$ và biến giá trị của biến $P$ trở thành con trỏ tới giá trị mới này, được biểu thị trong chương trình dưới dạng biến nhọn. Sơ đồ cú pháp của biến được chỉ định như sau:

Break, cuối cùng chúng ta có thể định nghĩa biến là gì trong ngôn ngữ Pascal: đó là tên được mô tả trong phần mô tả biến hoặc biến có chỉ mục hoặc lựa chọn trường hoặc biến đệm hoặc cuối cùng là biến nhọn.

Danh sách xâu chuỗi
Chúng ta hãy áp dụng các công cụ ngôn ngữ mà chúng ta vừa xem xét vào dạng cấu trúc phạm vi đơn giản nhất - danh sách chuỗi. Danh sách này là một chuỗi các bản ghi cùng loại $t$; Hơn nữa, một trong các trường trong các bản ghi này thuộc loại $\uparrow t$. Thông qua trường này, các bản ghi được nối thành một danh sách - mỗi phần tử chứa một con trỏ tới phần tử tiếp theo của danh sách. Trong mục cuối cùng của danh sách, trường này chứa con trỏ nil.

*)mới trong tiếng Anh - “mới”.

⟦folio 55⟧

Hình 3.
Kho
mới
105 48
112 55
893 11 nil

Hình 4.
mới
sự chuyển đổi
sau đó
105 48
112 55
893 11 nil

Hình 5.
mới
sự chuyển đổi
sau đó
105 48
112 55
200 13
nil

Hình 6.
mới
sự chuyển đổi
sau đó
105 48
112 55
893 11 nil

nil
sau đó
mới
200 13

Hình 7.
sự chuyển đổi
sau đó
105 48
112 55
893 11
900 13 nil

nil
sau đó
mới
Hình 8.
105 48
112 55
893 11
900 13 nil

Hình 9

55

⟦folio 56⟧

Hình 10.

người = ghi tên họ:
array [1..40] of char;
sau đây: ↑ khuôn mặt
end;
item = ghi địa chỉ, tổ chức:
array [1..30] of char;
học sinh: ↑ mặt;
sau đây: ↑ điểm
end;

Trong phần mô tả biến bây giờ chúng ta sẽ đặt một mô tả
cấu trúc: ↑ điểm;

Chúng ta thấy rằng trong mỗi mục của loại mục có hai con trỏ - loại mục ↑ để kết nối với mục tiếp theo và loại người ↑ để kết nối danh sách những người được gán cho mục này.

Các toán tử sau đây sẽ in họ và tên của tất cả học sinh kèm theo dấu hiệu của cố vấn-

từng điểm riêng lẻ (biến point thuộc loại ↑ point, biến people thuộc loại ↑ people):
điểm: = cấu trúc;
trong khi các mục <> không làm được
người bắt đầu: = điểm ↑. sinh viên;
trong khi người <> không làm gì
begin
writeln (người ↑. tên, họ,
điểm ↑ địa chỉ, điểm ↑
tổ chức);
khuôn mặt: = khuôn mặt ↑. tiếp theo
end;
điểm: = điểm ↑. tiếp theo
end;

Nhiệm vụ 19.4. Viết chương trình xác định số lượng sinh viên nên đăng ký thi công các công trình tại địa chỉ được chỉ định đầu tiên trong danh sách hạng mục công trình.

A. Rahr

Viện Dệt May Moscow
họ. A. N. Kosygina
(Để bắt đầu, xem trang 51)

3. Ở độ cao bao nhiêu so với bề mặt Trái đất thì sức lực của cơ thể sẽ mạnh bằng một nửa so với trên bề mặt Trái đất?
4. Một vật có khối lượng m=0,5kg được thả chìm trong nước ở độ sâu h=2m. Sau bao lâu thì vật nổi lên mặt nước? Mật độ vật chất q_T=0,7 g/cm³. Mật độ của nước q_B=1 g/cm³.
5. Hai thiên thạch băng giống hệt nhau bay về phía nhau với tốc độ bằng nhau và biến thành hơi nước khi chúng di chuyển ra xa. Tốc độ tối thiểu của thiên thạch sẽ là bao nhiêu nếu nhiệt độ của chúng trước khi va chạm là t=-20°C? Nhiệt dung riêng của nước đá và nước lần lượt là c_π=2100 J/(kg·K) và c_B=4190 J/(kg·K). Nhiệt dung riêng bay hơi của nước r=23·10⁵ J/kg. Nhiệt dung riêng nóng chảy của nước đá λ=3,35·10⁵ J/kg.
6. Trong một bình kín chứa một lượng khí có áp suất p=5·10⁵ Pa. Áp suất được thiết lập trong bình là bao nhiêu nếu sau khi mở vòi, 4/5 khối lượng khí thoát ra khỏi bình? Quá trình này có thể được coi là sản xuất.
7. Các quả bóng có bán kính r₁=15 cm và r₂=10 cm được tích điện lần lượt với điện thế φ₁=20 kV và φ₂=40 kV. Tiềm năng sẽ là bao nhiêu sau khi các quả bóng chạm vào? Điện tích nào sẽ chuyển từ quả bóng này sang quả bóng khác? Hãy xem xét trường hợp các quả bóng được tích điện cùng loại.
8. Hai dây dẫn mắc song song được nối với các cực của nguồn dòng điện có điện trở trong r=10 Ohms, các điện trở trong đó là R₁=10 Ohms và R₂=2 Ohms. Xác định tỉ số dòng điện chạy qua dây dẫn thứ nhất trước và sau khi hở mạch ở dây dẫn thứ hai.
9. Có một tờ giấy trên bàn. Một tia sáng chiếu tới tờ giấy với góc α=45° sẽ tạo ra một điểm sáng trên đó. Điểm này sẽ dịch chuyển bao nhiêu nếu đặt một tấm thủy tinh dày d=2 cm lên tờ giấy? Chiết suất của ống khói n=1,5.
10. Một vật cách thấu kính phân kì có công suất quang D = -2 dtr một khoảng bằng bao nhiêu để ảnh tối thiểu của nó xuất hiện ở giữa khoảng cách giữa thấu kính và tiêu điểm tối thiểu của nó?

Ấn phẩm đã được chuẩn bị
M. Boris, I. Turchin
