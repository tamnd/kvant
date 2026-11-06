---
id: 1991-7-tarasenko-algoritmika-prostotyi-chislovyie-atomyi-ebdf4242
issue: kvant_1991_7
year: 1991
number: "7"
title: Thuật toán đơn giản. Những "nguyên tử" số
authors:
  - Тарасенко Б.
rubric: raznoe
rubric_sub: Разное
page_first: 72
page_last: 74
page_labels: 70-72
lang: vi
source: kvant_digital
extraction: vision
content_sha256: e5f2ab17fde9ecab30594422087914c85a8538ee205121a78dcfc5974b77d8c9
prompt_sha256: draft-1
translated_from: content/ru/1991/07/articles/23_tarasenko-algoritmika-prostotyi-chislovyie-atomyi-ebdf4242.md
source_content_sha256: c9168032cb242c199641ae7db07f0ecfa72174dc8823174e26820649926f2ca7
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 70⟧

---
running_head:
folio:
---

Thuật toán
sự đơn giản

Những "nguyên tử" số

V. TARASENKO

Đó không phải là một câu hỏi dễ dàng,
Nhưng hãy tin một điều:
Mọi thứ đều phức tạp và đơn giản,
Hãy đếm nó một cách khôn ngoan!

Số nguyên tố có thể được gọi là "nguyên tử của vũ trụ số". Vì vậy, ngay khi ai đó bắt đầu “thu thập các số nguyên tố”, anh ta sẽ nhanh chóng tiếp cận bài toán phân tích các số tự nhiên thành số nguyên tố. Nếu có chương trình số 1 từ số trước đó, «Kvant» bài toán được giải quyết độc lập.

Nếu số đang nghiên cứu là số chẵn thì trước tiên bạn cần tách số tối đa khỏi nó.
Sức mạnh lớn nhất của hai bằng cách chia liên tiếp cho hai. Điều này rất dễ thực hiện trên bất kỳ loại máy tính nào. Bây giờ bài toán đã được rút gọn thành phân tích thành thừa số một số lẻ. Công cụ chúng ta cần sẽ bị ô nhiễm nếu trong chương trình nguyên mẫu, chúng ta thay thế các lệnh 24-27 bằng lệnh nhảy vô điều kiện về đầu chương trình và ở bước 16, chúng ta thay thế phần địa chỉ của lệnh nhảy có điều kiện từ 24 lên 23.

Khi làm việc với một chương trình gây ô nhiễm, mỗi lần đọc hệ số tiếp theo, bạn sẽ phải thực hiện thủ công thêm ba lệnh quan trọng. Điều này chắc chắn là bất tiện. Mặt tích cực của “đồng xu” là tính đa dạng gần như tối đa của văn bản chính của chương trình mới, cũng như việc dễ dàng loại bỏ nó khỏi nguyên mẫu. Chúng tôi vẫn sẽ có các chương trình phân tích đơn giản với dịch vụ tốt hơn nhưng có dung lượng lớn hơn. Không có gì miễn phí, kể cả những tiện ích bổ sung tại nơi làm việc.

Chương trình số 2, giống như chương trình trước, được xuất bản dưới dạng mà theo quan điểm của chúng tôi, nó có thể được cung cấp cho bất kỳ người dùng đã chuẩn bị nào mà không phải trả thêm phí.

Chương trình 2. Máy phân tích số lẻ

Tất cả các loại súng phụ từ B3-34 đến MK-61 đều phù hợp. Các biến và thanh ghi sử dụng: D=Pr5 - ước số lẻ hiện tại; И=Pr6 - số lẻ bắt đầu hoặc tiếp theo; PARTIAL=Pr9=I/D - thương của phép chia I cho D (đầu tiên là số thực, sau đó là phần nguyên của nó).

Mô tả thuật toán

Đặt I ban đầu. Đối với D lẻ liên tiếp, bắt đầu từ D=3 và cho đến khi PHẦN>D, tính PART=I/D, sau đó tính K - toàn bộ phần I/D và phần còn lại OCT=I-K×D. Trong trường hợp OCT = 0, đếm D (đây là một ước nguyên tố khác của số thử nghiệm), đặt newI = I/D và tiến hành nghiên cứu I này.

⟦folio 71⟧

---
running_head:
folio:
---

Nếu OST≠0 cho tất cả D được kiểm tra thì bản thân số được kiểm tra là đơn giản, việc mở rộng là hợp pháp.
Đánh giá hiệu quả của chương trình: số 11111 có ước số là 47 trong 2 phút, số 10001 có ước số là 73 trong 3 phút 20 giây.

Hướng dẫn
Sau khi gõ chương trình và chuyển PMC sang chế độ đếm, nhấn phím B/O. Sau đó quay số nguyên lẻ ban đầu AND và nhấn phím C/P, quá trình đếm sẽ bắt đầu; sau khi dừng đếm, nếu PMC dừng ở số khác 0 trên chỉ báo thì số được kiểm tra cuối cùng là đơn giản, việc mở rộng là hợp pháp; nếu chỉ báo hiển thị 0 (phát hiện một ước số đơn giản), thì hãy thực hiện thủ công
P→X 6
P→X 5
và đọc số từ chỉ báo (đây là ước số đơn giản tiếp theo của số đang được nghiên cứu), sau đó nhấn phím ø và nếu chỉ báo hiển thị 3 thì đây là ước số đơn giản cuối cùng; nếu chỉ báo không hiển thị 3, thì nhấn phím C/P, sau đó quá trình tìm kiếm ước nguyên tố sẽ tiếp tục.

Một công cụ mới thường sẽ được thử nghiệm trên vật liệu tốt. Chúng tôi lấy lũy thừa của hai số phẳng và trừ một, số Fibonacci, số rebonite (các số chỉ gồm những số 1, xem «Kvant» Số 8 cho năm 1989), cũng như các số gồm hai số 1 và một số số 0 chia chúng. "Giao thức được thử nghiệm" được đưa ra dưới đây. Chúng tôi sẽ không bình luận về họ. Chúng tôi tin chắc rằng độc giả sẽ tự tìm ra được điều đó.

2^n+1
n mở rộng

1 3=3
2 5=5
3 9=3 × 3
4 17=17
5 33=3 × 11
6 65=5 × 13
7 129=3 × 43
8 257=257
9 513=3 × 3 × 19
10 1025=5 × 5 × 41
11 2049=3 × 683
12 4097=17 × 241

⟦folio 72⟧

---
running_head:
folio:
---

2^n — 1
n mở rộng
1 1=1
2 3=3
3 7=7
4 15=3×5
5 31=31
6 63=3×3×7
7 127=127
8 255=3×5×17
9 511=7×73
10 1023=3×11×31
11 2047=23×89
12 4095=3×3×5×7×13

dãy số Fibonacci
n mở rộng
1 1=1
2 1=1
3 2=2
4 3=3
5 5=5
6 8=2×2×2
7 13=13
8 21=3×7
9 34=2×17
10 55=5×11
11 89=89
12 144=2×2×2×2×3×3

(10^n — 1):9
n mở rộng
1 1=1
2 11=11
3 111=3×37

4 1111=11×101
5 11111=41×271
6 3×7×11×13×37
7 239×4649
8 11×73×101×137
9 3×3×37×333667
10 11×41×271×9091
11 21649×513239
12 3×7×11×13×37×101×9901

10^n — 1 + 1(n > 1)
n mở rộng
1=1
2 11=11
3 101=101
4 1001=7×11×13
5 73×137
6 11×9091
7 101×9901
8 11×90901
9 17×5882353
10 7×11×13×19×52579
11 101×3541×27961
12 11×11×23×4093×8779

Bên trong mỗi chuỗi giữa các số thứ tự và sự phân tách các số thành các thành phần đơn giản của không gian bốn đều có các kết nối, nghiên cứu mà chúng tôi cung cấp cho người đọc và cho đến số tiếp theo của loạt bài, chúng tôi lại để tất cả những người yêu thích toán học yên tâm với một máy tính cá nhân cầm tay và chương trình này.

Bạn đọc thân mến!

Đăng ký cho năm 1992 bắt đầu.
Bất chấp tất cả những khó khăn tê liệt liên quan đến việc chuẩn bị tạp chí, cũng như chi phí giấy, in ấn và phân phối các ấn phẩm ngày càng tăng, người biên tập vẫn có ý định giữ nguyên bộ mặt và số lượng của tạp chí «Kvant».
Tạp chí «Kvant» không có bán lẻ nên chúng tôi khuyên bạn không nên trì hoãn việc đăng ký tạp chí này.
Chi phí của một phòng là 1 chà. 10 k., tạp chí định kỳ - 12 số mỗi năm.
Nó có thể được viết ra không nhất thiết phải trong một năm, mà trong bất kỳ khoảng thời gian nào và từ bất kỳ tháng nào.
Đăng ký được chấp nhận mà không có hạn chế tại các cơ quan Soyuzpechat, bưu điện và bưu điện.

Chỉ số tạp chí «Kvant» trong danh mục Soyuzpechat 70465.
