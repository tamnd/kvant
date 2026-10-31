---
id: 2018-10-eschyo-raz-o-postroenii-kasatelnoy-13a3444b
issue: kvant_2018_10
year: 2018
number: "10"
title: Một lần nữa về việc xây dựng một tiếp tuyến
rubric: raznoe
rubric_sub: Разное
page_first: 16
page_last: 16
page_labels: "14"
tag: P3DR
lang: vi
source: kvant_digital
extraction: native
content_sha256: 694abde8664625496a74c321dc6447395ce16fc28c259d683749883f2cd11bc2
prompt_sha256: draft-1
translated_from: content/ru/2018/10/articles/01_eschyo-raz-o-postroenii-kasatelnoy-13a3444b.md
source_content_sha256: a08dfad445d9b72567ea806ce427093e0e8fed66a072ba325504f2ae7a4c3616
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 14⟧

KVANT 2018/№10

ý tưởng kỹ thuật nhỏ: sử dụng một mảnh có giá trị không bằng nhau để tạo ra khoản dự trữ; thiết kế thuật toán theo kiểu quy nạp; sử dụng các phân vùng có độ chính xác tăng nhanh (chuỗi hội tụ). Nhiều ý tưởng trong số này đã được biết đến rộng rãi và thường được áp dụng trong nhiều tình huống khác nhau. Sẽ rất hữu ích khi có nhiều ý tưởng kỹ thuật như vậy. Kho vũ khí phong phú của họ cho phép bạn tiếp cận bài toán từ nhiều phía khác nhau và điều này đã giúp tìm đường cho lời giải. Điều thú vị là tổ hợp bài toán hoạt động với các phương pháp cường độ nhỏ điển hình cho phân tích. Do đó, thuật toán tìm được không hiệu quả lắm trong thực tế. Chúng tôi thậm chí không thể ước tính số lượng phân vùng sẽ phụ thuộc vào n. Điều này có nghĩa là vẫn còn một số việc phải làm trong bài toán này. Đối với những người quan tâm đến chủ đề này có một bộ bài viết. Có lẽ một trong những độc giả sẽ có thể nghĩ ra thuật toán phần của riêng họ!

Văn học

⟦column⟧

Hội nghị của Giải đấu Thành phố, tập 1, 2009, tr. 71–82. 2. W.Stromquist. Cách cắt bánh sao cho đẹp. – Tạp chí Toán học Hoa Kỳ, tập. 87, số 8, 1980, trang 640–644. 3. S. J. Brams, A. D. Taylor. Một giao thức chia bánh không cần ghen tị. – Tạp chí Toán học Hoa Kỳ, tập. 102, số 1, 1995, trang 9–18. 4. S. J. Brams, A. D. Taylor, W. S. Zwicker. Một giải pháp dao di chuyển cho bộ phận bánh ngọt gồm bốn người không có sự ghen tị. – Kỷ yếu của Hiệp hội Toán học Hoa Kỳ, 125, 1997, trang 547–554. 5. W. Stromquist. Sự phân chia bánh không có ghen tị không thể được tìm thấy bằng các giao thức hữu hạn. – Tạp chí Điện tử Tổ hợp, R11, 15, 2008. 6. A.D.Procaccia. Bạn sẽ thèm muốn chiếc bánh của hàng xóm. – Kỷ yếu IJCAI’09, trang 239–244. 7. H.Aziz, S.Mackenzie. Một giao thức cắt bánh không có sự ghen tị và riêng biệt dành cho bất kỳ số lượng đại lý nào. – Bản in trước, https://arxiv.org/abs/ 1604.03655 8. H. Aziz, S. Mackenzie. Một giao thức cắt bánh riêng biệt và không có giới hạn dành cho bốn đại lý. – Bản in trước, https://arxiv.org/ abs/1508.05143

1. I.A.Ivanov, A.Ya.Kanel-Belov, S.I.Kublanovsky, A.S.Malistov. Bài toán về bọn cướp. – Chất liệu chọn lọc từ Summer Con-

Công trình được hỗ trợ bởi Quỹ Khoa học Nga số 17-11-01337. Tác giả đầu tiên là người đoạt giải “Toán học trẻ nước Nga”.

HỌ VIẾT CHO CHÚNG TÔI

Một lần nữa về việc xây dựng một tiếp tuyến

Bài viết của D. Shvetsov “Polyara” («Kvant» Số 5, 2017) chỉ ra cách vẽ các tiếp tuyến với đường tròn này bằng một thước kẻ từ một điểm bên ngoài đường tròn. Tác giả và độc giả thường xuyên của chúng tôi I. Vainshtein lưu ý rằng cách xây dựng này cho phép chúng ta vẽ tiếp tuyến với đường tròn và đi qua một điểm nằm trên đường tròn. Hãy để chúng tôi trình bày một cấu trúc từ lá thư của I. Weinstein. Cho điểm E trên đường tròn (Hình 1). Qua điểm này ta kẻ cát tuyến (không đi qua tâm đường tròn), đường này sẽ cắt đường tròn tại điểm F. Lấy các điểm B và D tùy ý nằm ngoài đường tròn trên đường thẳng EF rồi từ đó vẽ các tiếp tuyến với đường tròn như đã chỉ ra ở bài “Cực”. Gọi giao điểm tương ứng của các tiếp tuyến là A

⟦figure⟧

Cơm. 1

và C, các điểm tiếp tuyến là K, L, M, N. Giả sử các đường thẳng KL và MN cắt nhau tại điểm P. Khi đó PE là tiếp tuyến mong muốn. Thật vậy, không khó để chứng minh đường thẳng AC cũng đi qua điểm P, đường thẳng NK và ML cắt nhau trên đường thẳng BD và các điểm

(Tiếp theo trang 25)
