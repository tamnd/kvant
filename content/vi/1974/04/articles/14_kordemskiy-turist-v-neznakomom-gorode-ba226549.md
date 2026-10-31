---
id: 1974-4-kordemskiy-turist-v-neznakomom-gorode-ba226549
issue: kvant_1974_4
year: 1974
number: "4"
title: Du khách ở một thành phố xa lạ
authors:
  - Кордемский Б. А.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 57
page_last: 58
page_labels: 55-56
tag: WD5K
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 892a82b15957b58fb8a7ad5dfcd397025a283271721605db34ebc61487597bf6
prompt_sha256: draft-1
translated_from: content/ru/1974/04/articles/14_kordemskiy-turist-v-neznakomom-gorode-ba226549.md
source_content_sha256: 421d0adddfb92695034cc08ab938ab61400cdfb738444bdccfeb401335657305
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 55⟧

Du khách ở một thành phố xa lạ
V. A. Kordemsky

Hãy tưởng tượng một thành phố có đường phố giống như những hình tứ giác ca rô - một số trải dài từ nam tới nam, một số khác từ đông sang tây. Có một trung tâm du lịch ở thành phố này. Một khách du lịch ở điểm A cần đến địa điểm cắm trại này. Nhưng anh ta không có bản đồ, không có biển báo trong thành phố, và khách du lịch không thể hỏi người dân - anh ta không biết ngôn ngữ. Mỗi lần anh ta muốn xác định ngẫu nhiên cả hướng chuyển động và số khối anh ta cần đi theo hướng này trước khi thay đổi lại. Nhưng “xác định ngẫu nhiên” có nghĩa như thế nào; Làm thế nào chúng ta có thể thực hiện “tính ngẫu nhiên” nói chung?

Eureka! Khách du lịch cần một bộ cái gọi là "số ngẫu nhiên", kết hợp theo cặp. Giá trị tuyệt đối của số đầu tiên sẽ cho biết khách du lịch cần đi bao nhiêu dãy nhà theo hướng ngang (ngang đương nhiên được gọi là hướng “đông - tây”, “tây - đông”; và dọc - “bắc - nam”, “nam - bắc”) và ký hiệu của số chính là hướng: đông nếu bằng phẳng và tây nếu trừ. Tương tự như vậy, giá trị tuyệt đối của số thứ hai sẽ cho biết bạn cần đi bao nhiêu khối nhà theo hướng thẳng đứng, về phía nam nếu số này âm và về phía bắc nếu số này là dương.

Nhưng bạn lấy "số ngẫu nhiên" ở đâu? Chúng có thể được phát hành bằng máy tính nếu bạn cung cấp cho nó chương trình thích hợp, nhưng tất nhiên, khách du lịch không có máy tính. Nhưng anh ta có một tờ báo có bảng số trúng thưởng của vé số. Khách du lịch chọn ngẫu nhiên một phần của bàn

Nghệ sĩ M. Zlatkovsky

tsy, vậy thì trong số mỗi vé logerina sẽ lấy hai vé cuối cùng

31013 179 Máy ảnh 90
31019 110 25 rúp —
31026 060 25 rúp —
31030 199 50 rúp —
31031 115 Xem “Chuyến bay” 35
31045 026 100 rúp —
31047 101 Máy ảnh 15
31068 178 50 rúp —
31069 100 Xem “Chuyến bay” 35
31070 096 50 rúp —

⟦folio 56⟧

số và coi chúng như một cặp. Kết quả là tập hợp các cặp số ngẫu nhiên sau: (7, 9), (1, 0), (6, 0), (9, 9), (1, 5), (2, 6), (0, 1), (7, 8), (0, 0), (9, 6). Nhược điểm của những con số này là cuối cùng chúng đều dương. Nhưng nhược điểm này rất dễ khắc phục: ví dụ: trừ đi một số cố định trong tập hợp số ngẫu nhiên, chẳng hạn như 5. Trong trường hợp này, cặp (7, 9) sẽ biến thành một cặp (2, 4), nghĩa là: “bạn cần đi hai dãy nhà về phía đông, sau đó bốn dãy nhà về phía bắc”; cặp (1, 0) - thành cặp (-4, -5), tức là “bốn khối ở phía tây và năm khối ở phía nam”. Một tập hợp các cặp như vậy đã thiết lập lộ trình cho khách du lịch. Trong trường hợp này, “mã” của tuyến đường ngẫu nhiên thu được sẽ được viết như sau: (2, 4), (-4, -5), (1, -5), (4, 4), (-4, 0), (-3, 1), (-5, -4), (2, 3), (-5, -5), (4, 1).

Bây giờ du khách có thể lên đường.

Lưu ý rằng khách du lịch có thể không bao giờ tham gia được chuyến tham quan; tuy nhiên, chỉ cần anh ta ở bất kỳ khu vực lân cận nào là đủ, vì từ đó anh ta đã biết đường.

Tuyến đường đã chọn được hiển thị trong hình; Dễ dàng nhận thấy rằng nó vô tình hóa ra không dài lắm, mặc dù không phải là ngắn nhất: xét cho cùng, tuyến đường của khách du lịch chỉ cách đó 15 $\frac{1}{2}$ dãy nhà, và anh ta phải đi bộ hơn 66!

Trong ví dụ này, các số ngẫu nhiên cho phép chúng ta mô phỏng tính ngẫu nhiên thực sự, cụ thể là tính ngẫu nhiên cho phép khách du lịch chọn hướng này hay hướng khác. Tuy nhiên, đồng thời, đối với mỗi liên kết của tuyến đường, cần phải đưa ra các hạn chế một cách giả tạo - không quá bốn khối theo hướng được gán cho số dương (đông và bắc) và không quá năm khối theo hướng được xác định bằng số âm (nam và tây). Và một điều nữa: bằng cách thay các số 0, 1, 2, 3, 4, 5, 6, 7, 8, 9 bằng -5, -4, -3, -2, -1, 0, 1, 2, 3, 4, chúng ta đã “sửa” các số ngẫu nhiên sao cho các hướng “âm” - Nam và Tây - hóa ra được ưu tiên hơn (-5, -4, -3, -2, -1 - có 5 trên 10) “tích cực” - phía bắc và phía đông (bốn trên mười).

Các nhà toán học gọi mô hình “ngẫu nhiên” này là “nặng”, nhưng không cho rằng nó không thể chấp nhận được.

Vấn đề. Hãy để khách du lịch biết rằng trung tâm du lịch nằm ở phía Tây Nam thành phố. Điều này có nghĩa là, tuy vẫn duy trì nguyên tắc ngẫu nhiên trong việc chọn hướng, nhưng ưu tiên chọn hướng Nam và hướng Tây vẫn hợp lý hơn. Nhưng những hướng này được đưa ra bởi số âm; do đó, trong một tập hợp số ngẫu nhiên có một chữ số, bạn cần có nhiều số âm hơn số dương. Để thực hiện yêu cầu này, chẳng hạn, bạn có thể giảm tất cả các số trong bộ viết không phải xuống 5 mà là 7. Tôi tự hỏi liệu khách du lịch có đến căn cứ sớm hơn lần đầu không? Tạo một “mã” mới và sơ đồ lộ trình ngẫu nhiên của nó.

Trong bài viết của chúng tôi, các con số ngẫu nhiên hóa ra lại rất hữu ích: chúng giúp khách du lịch tìm được chuyến tham quan. Họ cũng giúp đỡ trong nhiều nhiệm vụ khác. Đó là lý do tại sao chúng tôi đã nói với bạn về họ.
