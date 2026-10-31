---
id: 1982-1-rar-zaochnaya-shkola-programmirovaniya-959a6844
issue: kvant_1982_1
year: 1982
number: "1"
title: Trường lập trình tương ứng
authors:
  - Рар А.
rubric: raznoe
rubric_sub: Разное
page_first: 51
page_last: 54
page_labels: 49, 51, 52
tag: DAIR
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 4f87e9f64cb606329193c831d6ead9a490952320f2444f276d079a452446ad95
prompt_sha256: draft-1
translated_from: content/ru/1982/01/articles/18_rar-zaochnaya-shkola-programmirovaniya-959a6844.md
source_content_sha256: bbd8ebccfbda4a299ffe25a1ff577f163ff92ef6276973d143e1858e9e633eae
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 49⟧

Nghệ thuật lập trình", chúng tôi tiếp tục xuất bản các bài học từ Trường Lập trình Tương ứng và các bài báo về khoa học máy tính, ngôn ngữ lập trình và công nghệ máy tính. Bài học của sinh viên trường tương ứng, người sẽ hoàn thành khóa học thứ ba và cuối cùng trong số đầu tiên của năm nay, khó có thể tiếp cận được với độc giả mới của tạp chí. Chúng tôi hy vọng các bài viết còn lại sẽ vén lên bức màn bí mật mà đôi khi vẫn bị máy tính bao vây và sẽ giải thích tại sao việc làm chủ công nghệ máy tính đôi khi được gọi là "kiến thức thứ hai".

Trường lập trình tương ứng.

Bài 17: Mảng và bản ghi trong Pascal

Các khả năng khác của Pascal liên quan đến sự hiện diện của các kiểu cấu trúc trong đó, cụ thể là các kiểu mảng, bản ghi và tệp. Hãy bắt đầu với mảng và bản ghi.

Mảng
Mảng là tập hợp của một số phần tử nhất định; tất cả các phần tử này phải cùng loại. Trong trường hợp này, người ta nên tưởng tượng rằng các phần tử của mảng được sắp xếp theo một cách thông thường nào đó: như các hàng, như một bảng hình chữ nhật, như một mạng không gian hình chữ nhật, v.v. Những trường hợp khác nhau này tương ứng với các mảng có kích thước khác nhau: một chiều (hoặc vectơ), hai chiều (hoặc ma trận), ba chiều, v.v.

Để chỉ định một phần tử của mảng có kích thước $n$, bạn cần chỉ định tọa độ $n$ xác định vị trí của phần tử này trong mảng; Chúng tôi sẽ gọi các chỉ số tọa độ này. Ví dụ: một phần tử của ma trận được xác định bằng hai chỉ số, một chỉ số biểu thị hàng của ma trận và chỉ số còn lại biểu thị phần tử trong hàng (về cơ bản là cột của ma trận).

Các giá trị mà chỉ mục lấy (ví dụ: các giá trị biểu thị các hàng trong ma trận của chúng ta hoặc các cột của nó) tạo thành một loại loại vô hướng nào đó (nghĩa là, như chúng ta đã thấy trước đó, một tập hợp có thứ tự). Kiểu vô hướng này có thể là bất cứ thứ gì ngoại trừ số thực, nhưng điều tự nhiên nhất là sử dụng một phân đoạn có kiểu số nguyên trong khả năng này và khi đó rõ ràng là các chỉ số chỉ đơn giản là các số.

Ví dụ, trong một ma trận, các hàng là các số từ 1 đến 5 và các cột là các số từ 0 đến 19. Khi đó, loại chỉ mục đầu tiên là 1..5 và loại chỉ mục thứ hai là 0..19.

Kiểu mảng được chỉ định theo sơ đồ cú pháp sau:

Trong sơ đồ này, “các loại vô hướng” tuần tự là các loại chỉ mục thứ nhất, thứ hai, v.v. và số lượng của chúng tất nhiên bằng với kích thước của mảng. Trường tun chứa loại phần tử mảng (giống nhau cho tất cả các phần tử).

Một phần tử mảng riêng biệt được biểu diễn trong chương trình dưới dạng một biến có chỉ số. Sơ đồ cú pháp của nó cũng là:

"Name" ở đây là tên của mảng tương ứng. Số lượng biểu thức phải bằng số lượng chỉ mục mảng và loại biểu thức phải khớp với loại của chỉ mục tương ứng.

Hãy chuyển sang các ví dụ. Để phần mô tả kiểu trong chương trình có dạng

⟦folio 51⟧

Danh sách các trường lần lượt được xác định bằng sơ đồ

Bây giờ chúng ta sẽ xem xét các loại bản ghi không có bộ phận có thể thay thế được. Phần tử bản ghi được thể hiện trong chương trình dưới dạng một tập hợp các trường, sơ đồ cú pháp của nó như sau:

"Tên" ở đây là tên của mục tương ứng.

Hồ sơ được sử dụng thuận tiện để lưu trữ và xử lý các thông tin khác nhau về các đối tượng nhất định. Trong ví dụ sau, các bản ghi chứa thông tin về các quốc gia khác nhau trên thế giới. Để phần mô tả kiểu trong chương trình có dạng

```text
type data = record
    год, месяц, день: integer
end;
вызы = record
    университеты, технические,
    прочее: integer
end;
страна = record
    плочадь, населенение:real;
    устройство:boolean;
    вступление:дата;
    образование:вызы
end;
```

Lưu ý rằng các kiểu dữ liệu và lệnh gọi là khác nhau: mặc dù chúng chỉ định bộ ba số nguyên nhưng tên trường của chúng lại khác nhau.

Hãy để thêm trong phần mô tả các biến chương trình có mô tả

Úc, Úc, Albania,...
nhật bản:đất nước;

Ẩn dưới đa điểm ở đây là danh sách tất cả các quốc gia là thành viên của Liên hợp quốc. Thông tin về từng cơ sở, được lưu trữ trong các trường tương ứng như sau: diện tích (tính bằng nghìn km vuông), quy mô dân số (tính bằng triệu người), cơ cấu cơ cấu (cộng hòa - đúng, chế độ quân chủ - sai), dữ liệu về việc gia nhập Liên hợp quốc, số lượng các cơ sở giáo dục đại học khác nhau.

Nhiệm vụ 17.5 Trong ví dụ của chúng tôi, một số trường có loại mục nhập “mở rộng”. Thay đổi mô tả để phạm vi thay đổi chỉ mục càng nhỏ càng tốt.

Giả sử rằng tất cả các trường trong tất cả các bản ghi đều đã được điền. Sau đó, ví dụ: toán tử writeln(ukraina.hapopulation/ukraina.area);
sẽ in mật độ dân số ở Ukraine.

Mở rộng khái niệm biến

Hãy để chương trình của chúng tôi mô tả một biến đại học có kiểu số nguyên.

Điều này có thể chấp nhận được: có thể sử dụng cùng một tên (trong ví dụ của chúng tôi là các trường đại học) trong cùng một chương trình cho một biến và cho trường bản ghi (cũng như cho các trường thuộc các loại bản ghi khác nhau).

Chúng tôi muốn gán cho biến này tổng số trường đại học ở Bán đảo Iberia, mà chúng tôi viết toán tử gán các trường đại học: =spain. giáo dục.
 trường đại học + cổng thông tin.
 giáo dục. trường đại học;

Mỗi thuật ngữ là một mẫu, nhưng không phải từ một biến chung mà từ một mẫu khác.

Vì vậy, từ biến Tây Ban Nha (loại quốc gia), lĩnh vực giáo dục (loại cuộc gọi) được trích xuất và từ đó, lĩnh vực trường đại học (loại số nguyên).

Để chỉ định các cấu trúc như vậy, chúng tôi cần đưa ra các thay đổi đối với một số sơ đồ cú pháp của mình. Nhưng chúng tôi sẽ không làm điều này mà chỉ quy định rằng khái niệm biến không chỉ bao gồm các biến chung mà còn bao gồm các biến có chỉ mục và lựa chọn trường. Ngoài ra còn có điều kiện là bất kỳ hành động nào được thực hiện trong chương trình trên một biến ở chế độ cảm giác từ (bao gồm cả trích xuất trường) cũng có thể được thực hiện trên một biến theo nghĩa mở rộng.

Nhiệm vụ 17.6. Viết một thủ tục ở bên phải với tham số loại quốc gia in ra cho quốc gia tương ứng: a) đó là nước cộng hòa hay chế độ quân chủ, b) nước đó có bao nhiêu cư dân trong mỗi cơ sở giáo dục đại học.

Bài viết có biến thể

Cho đến nay chúng tôi vẫn tin rằng các hồ sơ thuộc về cùng một

⟦folio 52⟧

loại, được tổ chức theo cùng một cách. Tuy nhiên, Pascal có thể nới lỏng hạn chế này. Bằng cách sử dụng “bộ phận thay thế” trong mô tả loại bản ghi (xem sơ đồ cú pháp cho mô tả này), các chương trình có thể xác định bản ghi có các biến thể.

Phần thay thế có sơ đồ cú pháp như sau*)

giữa chúng (tính bằng radian: 180° = π radian). Đối với một hình tam giác, chúng ta cũng sẽ chỉ ra liệu việc truyền tải từ x đến y được thực hiện theo chiều kim đồng hồ hay ngược chiều kim đồng hồ (trong trường truyền tải, việc truyền tải sẽ đúng hay sai tương ứng). Không có trường bổ sung được yêu cầu cho vòng tròn.

Chúng ta hãy mô tả thêm một biến loại fcesure f, và đặt nó với

Cặp “tên - tên loại” sau trường hợp chỉ định một trường đặc biệt của bản ghi: trường thuộc tính. Giá trị của trường này sẽ được gọi là dấu hiệu. Dấu (tại bất kỳ thời điểm thực hiện chương trình nào) phải là một trong các hằng số sau. Hằng số đóng vai trò là một dấu hiệu chỉ định biến thể của bản ghi, nghĩa là nó xác định các trường tiếp theo của bản ghi là gì: đây chính xác là những trường đó, danh sách xuất hiện trong ngoặc đơn sau hằng số này.

Chúng ta hãy xem xét một tập hợp gồm tất cả các hình tam giác, hình bình hành và hình tròn có thể nằm trên một mặt phẳng (và chuyển động tự do dọc theo nó). Bộ sưu tập như vậy được chỉ định bởi loại fcesura, có mô tả sau:

fcesura =
recordx:real;
casef:hình thức của
tam giác:(y, el:real);
bỏ qua: boolean;
hình bình hành: (y1, el1:real);
mát mẻ: ()
end

Loại hình được mô tả là hình = (tam giác, hình bình hành, hình tròn));

Trường x chung cho cả ba hình: đối với hình tam giác và hình bình hành, nó là một trong các cạnh, đối với hình tròn, đó là bán kính. Đối với hình tam giác và hình bình hành, bạn cần xác định cạnh và góc thứ hai, vui

*) Do nguyên tắc kỹ thuật, không thể sửa thao tác trong sơ đồ này: mũi tên bỏ qua chỉ bao gồm một trường, danh sách các trường chứ không phải ba trường: (, danh sách các trường,).

Từ điển
mảng - mảng
ghi lại - ghi lại

A. Pap
