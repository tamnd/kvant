---
id: 2025-9-panyunin-basseynyi-nyutona-2621b4dc
issue: kvant_2025_9
year: 2025
number: "9"
title: Bể bơi Newton
authors:
  - Панюнин Н. М.
rubric: kaleydoskop-kvanta
rubric_sub: Калейдоскоп
page_first: 34
page_last: 35
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 167bdb050e396f853749fccfb6344a6fecde77f0270784741143b3832f23013d
prompt_sha256: draft-1
translated_from: content/ru/2025/09/articles/08_panyunin-basseynyi-nyutona-2621b4dc.md
source_content_sha256: b07551880ab4d42d82d853038da6bbbbffa0a105fa583c14547c8e8179dc6543
translation_model: draft
translation_run: vi-draft-gaps-2026-11-04
translation_quality: draft
---

⟦folio none⟧

---
running_head:
folio:
---

$z - \{n + 1\} = Z$
$f(z) = Z^5 - Z^4 - Z - 1$
KÍNH KÍNH KÍNH “QUANTA”

Bể bơi Newton

Hãy xem xét cách "làm việc-
et” Phương pháp Newton trên máy tính
máy bay lek và làm thế nào
Thực tế của Newton không tồn tại.
Chúng tôi sẽ dựa vào thuật ngữ
khoa học được đặt ra ở Sta-
cấp "Phương pháp Newton" trong phần này
số tạp chí, vậy
Đầu tiên chúng tôi khuyên bạn nên làm quen với
đi chơi với cô ấy.

Ví dụ, hãy lấy
phương trình
$z^5 - \frac{3}{4} z^4 - \left(\frac{1}{2} - \frac{3}{4} i\right) z^3$
$- (1 + i) z - 1 - i = 0$.

Phương trình này được chọn dựa trên
của sự rõ ràng. Nó có
5 gốc khác nhau:
$w_1 \approx -0,8 + 0,3 i,$
$w_2 \approx -0,7 - 0,4 i,$
$w_3 \approx i,$
$w_4 \approx 0,7 - i,$
$w_5 \approx 1,5$.

Hình 2

Hãy gán một màu khác nhau cho mỗi gốc và
Chúng ta hãy đánh dấu các nghiệm trên mặt phẳng phức (hình 1).

Hãy xem xét quá trình lặp lại của phương pháp Newton: $z_{n+1} = N(z_n)$, trong đó $N(z)$ là bản đồ Newton. Chúng ta hãy chọn một số điểm ban đầu trên mặt phẳng phức, biểu thị chúng bằng các hình tam giác và theo dõi quỹ đạo của các điểm này trong 19 lần lặp (xem hình 1). Như bạn có thể thấy, bắt đầu từ các điểm gần nhau, bạn có thể đi đến các nghiệm khác nhau. Trong trường hợp này, quỹ đạo của các điểm có thể khá phức tạp.

Chúng ta hãy lấy một thể tích trên mặt phẳng phức
diện tích $\{z : |Rez| \leq 2,5, |Imz| \leq 2,5\}$ và với mỗi điểm $z_0$ của diện tích này chúng ta sẽ thực hiện 19 bước theo phương pháp Newton. Chúng tôi nhận được một số

⟦folio none⟧

---
running_head:
folio:
---

Tôi chỉ $z_{19}$. Hãy sơn điểm bắt đầu $z_0$ bằng màu đặt tên cho gốc mà $z_{19}$ gần nhất. Kết quả là, việc tiếp nhận hình ảnh fractal tiếp theo (hình 2).

Một lần nữa, chúng tôi tin rằng, trái ngược với giả định tự nhiên về lưu vực Newton là diện tích bao gồm các điểm gần nghiệm này hoặc nghiệm khác, trên thực tế thì không phải như vậy. Điều đáng chú ý là việc chia mặt phẳng thành các vùng có các điểm gần với dữ liệu được gọi là sơ đồ Voronoi (ví dụ, xem bài viết của N. Dolbilin “Multifaceted Delaunay” trong «Kvant» Số 1 và 2 năm 2010). Lưu ý rằng nếu chúng ta không lặp lại 19 lần phương pháp của Newton mà là 0, và vẽ mặt phẳng theo các quy tắc tương tự, thì chúng ta sẽ có được sơ đồ Voronoi - một bước 0 trong việc tiếp cận cấu trúc fractal.

hình 3 hiển thị các cấu trúc thu được sau 0, 1, 2, 5

lặp đi lặp lại tương ứng. Có thể thấy rằng bức tranh được thiết lập khá nhanh chóng và sau khi lặp lại gót chân, cấu trúc fractal được đoán ra. Fragtal chỉ trong trường hợp số bước “vô hạn”, tức là trong giới hạn, nhưng các hình ảnh hình thành sau 19 bước và sau 100 bước trong bản vẽ có kích thước được đề cập thì không thể phân biệt được bằng mắt.

Thực hiện những thí nghiệm không quá phức tạp này trên máy tính. Quan sát cấu trúc của các bể hấp dẫn thay đổi như thế nào tùy thuộc vào sự thay đổi nghiệm của đa thức. Nó được xác định bởi các điểm tới hạn của bản đồ Newton, tức là các điểm mà đạo hàm của bản đồ Newton bằng 0: $N'(z) = 0$. Đánh dấu các điểm tới hạn và theo dõi mối liên hệ giữa số lượng của chúng trong một khu vực cụ thể và hình dạng của khu vực đó. Tìm ra cách xác định các điểm bắt đầu từ đó phương pháp của Newton lặp lại.

Tài liệu do N. Paponin chuẩn bị
