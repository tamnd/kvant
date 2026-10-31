---
id: 1982-10-pogosyants-vokrug-evm-023d5e59
issue: kvant_1982_10
year: 1982
number: "10"
title: Xung quanh máy tính
authors:
  - Погосянц Э.
rubric: kvant-ulybaetsya
rubric_sub: «Квант» улыбается
page_first: 57
page_last: 59
page_labels: 55, 57
tag: GHLZ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 92618023d69f336f43a0bfc8f96021a60273b2edbf6cbc3bfd9a05c7f26e3bed
prompt_sha256: draft-1
translated_from: content/ru/1982/10/articles/13_pogosyants-vokrug-evm-023d5e59.md
source_content_sha256: 1f503de6edaf45f7330dded9db56b5ecd0ef60f8e9ad18e7c89149ece3eb4aed
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 55⟧

và sau đó "đi ra."

for j: =1 to k do f[j]:=1;
for i: =k+1 to n do
begin s: =0;
for j: =1 to k-1 do s: =s+f[j];
f[k+1]:=s*f[k];
writeln(f[k+1]);
for j: =1 to k do f[j]:=f[j+1];
end;

Ở đây: 1 - gán ban đầu, 2 - vòng lặp chính, 3 - tính giá trị tiếp theo, 4 - sử dụng giá trị, 5 - gán lại.
(Biến s được đưa vào để tăng tốc độ của chương trình: thay vì s nó được chọn sử dụng f[k+1], nhưng hãy nhớ rằng lập chỉ mục là một hoạt động tốn nhiều công sức đối với máy tính.)

Kiểm soát công việc

1.1. Cho x. Tính giá trị gần đúng của e^x bằng công thức
$$e^x \approx 1+x + \frac{x^2}{2!} + \frac{x^3}{3!} + \dots + \frac{x^n}{n!}.$$
Tiến hành tính toán cho đến khi số hạng tiếp theo nhỏ hơn ε.

1.2. Tính các giá trị hàng thứ k của lượng giác Pascal (xem bài viết của A. Bendukidze trong số này). Kết quả phải được ghi vào một mảng có độ dài k; mảng hai chiều và mảng phụ không được sử dụng.

Các chương trình phải được hoàn thành đầy đủ (không chỉ phần nội dung của chương trình) và được gửi trong vòng hai tuần sau khi nhận được tạp chí. Chọn độ dài và loại mảng phái sinh.

Chuẩn bị bài toán cho bài 2*)

1. Tìm phần tử đầu tiên trong mảng đã cho (đếm từ bên phải) có giá trị cho trước.

2. Tìm phần tử cuối cùng trong một mảng nhất định có giá trị nhất định (mảng được quét từ đầu đến cuối chứ không phải ngược lại).

3. Tìm phần tử thứ m trong mảng đã cho có giá trị đã cho.

Trong tất cả các tác vụ, bạn cần lấy chỉ mục của phần tử mong muốn nếu nó nằm trong mảng và bằng 0 nếu không có.

Câu hỏi: Điều kiện và nghiệm của bài toán có điểm gì chung? Tại sao bài toán 2 lại hợp lý khi giải như một bài toán độc lập, thay vì tìm kiếm cái đầu tiên từ cuối phần tử?

L. Sternberg

*) Lời giải những bài toán này không cần phải gửi!

«Kvant» mỉm cười

Xung quanh máy tính

Đầu tiên, người đàn ông làm cho cỗ máy làm việc cho chính mình, và bây giờ anh ta muốn nó suy nghĩ thay anh ta.

E. Pozosyants Có lẽ đúng như vậy chăng?

Cô ấy biết quá nhiều!

Đủ! Tôi được nghỉ trưa.

Nếu tôi mắc lỗi lần nữa, tôi sẽ thay thế nó bằng một con người!

⟦folio 57⟧

Tập này trong cuốn sách của V. Ya. Frenkel và B. E. Yavelov “Eishstein - Nhà phát minh” (M., “Nauka”, 1981) có thể được tìm thấy lời giải Theo ý kiến ​​​​của cô, tình tiết gợi lên cảm giác giống như toàn bộ cuốn sách: sự ngạc nhiên. Và cùng một mong muốn mà tôi cảm thấy là được làm quen ngay với cuốn sách: tìm hiểu - phải làm gì?

Tên của Albert Eischstein, một trong những nhà khoa học đáng chú ý nhất từng sống, nhà vật lý vĩ đại của thế kỷ chúng ta, quen thuộc trong mọi thứ, không có ngoại lệ. Hơn nữa, những người ở rất xa khoa học đều biết rằng Eischstein là người tạo ra thuyết tương đối, mặc dù họ có thể chỉ có những ý tưởng mơ hồ về bản thân lý thuyết này. Những người quan tâm đến vật lý và các nhà vật lý có cơ hội tìm hiểu về tầm quan trọng của thiên tài vật lý Eischstein và tính cách hấp dẫn khác thường của ông từ vô số cuốn sách và bài báo viết về cuộc đời và công việc của nhà khoa học.

Nhưng chúng ta có thể nói một cách an toàn rằng một người thực tế chưa từng nghe nói đến Eischstein - người phát minh ra tủ lạnh (không chỉ một mà là nhiều loại); về Eischstein - người phát minh ra máy ảnh dùng để quay phim ở Hollywood; về Eischstein - người phát minh ra loa từ giảo; máy bơm từ thủy động lực để bơm kim loại lỏng; hệ thống treo thủy động cảm ứng, được sử dụng rộng rãi trong luyện kim ngày nay; về Eischstein, người đã phát triển phương pháp xác định kích thước lỗ trong các bộ lọc y tế. Về Eischstein, một nhà thí nghiệm đã đưa ra những ý tưởng độc đáo cho các thí nghiệm.

Không có cách nào để tìm hiểu về điều này. Sách của V. Ya. Frenkel và B. E. Yavelov -

Sách mới

(Để bắt đầu, xem trang 43)

3. A. G. Kurosh. Phương trình đại số ở mức độ tùy ý. Tái bản lần thứ 3 (quý I). Giá 10k.

Cuốn tài liệu này dựa trên bài giảng của tác giả, một nhà toán học nổi tiếng, dành cho những người tham gia Olympic Toán học Moscow. Cuốn sách nói về phương trình đại số bậc tùy ý, định lý cơ bản của đại số, phương pháp lời giải của một số phương trình đại số và khả năng giải được phương trình theo bán kính. Theo quy định, các kết quả được trình bày không có bằng chứng nhưng được minh họa bằng các ví dụ thú vị.

Thư viện «Kvant»
1. E. Vâng. Gik Cờ vua và toán học (quý I). Giá 40k.

Tác giả cuốn sách là một nhà toán học và kỳ thủ cờ vua, người điều hành trang cờ vua của tạp chí chúng tôi. Bằng một hình thức phổ biến, ông nói về những mối liên hệ khác nhau giữa toán học và cờ vua.

Cuốn sách thảo luận về các phương trình máy tính, hệ số ELo, toán học của người chơi cờ và hình học cần thiết của bàn cờ.

2. V. M. Tikhomirov. Những câu chuyện về thăng trầm (Q4). Giá 40k.

Cuốn sách nói về những vấn đề tối đa và tối thiểu đã ẩn sâu trong lòng từ xa xưa. Đầu tiên, tác giả nói về bài toán cổ điển đã được giải bởi Euclid, Archimedes, Apollonius, Fermat, Kepler, Newton, Leibniz.

Tiếp theo, anh ấy nói về mối liên hệ sâu sắc của cực đoan bài toán với các vấn đề có ý nghĩa tự nhiên, kinh tế, công nghệ vũ trụ và các phương pháp hiện đại lời giải của bài toán như vậy.

3. I. F. Shargin. Bài tập hình học: Lập thể (quý III). Giá 40k.

Cuốn sách chứa khoảng 350 bài toán trong hình học.

Phần đầu tiên chứa bài toán, có tính chất tính toán. Dưới đây là một số định lý hình học rắn áp dụng trực tiếp vào khóa học sô-cô-la.

Phần thứ hai chứa các bất đẳng thức hình học, bài toán về quỹ tích các điểm, các phần tử của hình học hình cầu, v.v.

A. Yeorov
