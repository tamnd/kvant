---
id: 1986-2-levinshteyn-simin-logicheskie-shemyi-na-tranzistorah-e051e94b
issue: kvant_1986_2
year: 1986
number: "2"
title: Mạch logic bán dẫn
authors:
  - Левинштейн М. Е.
  - Симин Г. С.
rubric: raznoe
rubric_sub: Разное
page_first: 46
page_last: 47
page_labels: 44-45
tag: IDFV
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 74c6eef1274b2dff152ecf145630678952d78d5e98615e277a15a6cbcc556e29
prompt_sha256: draft-1
translated_from: content/ru/1986/02/articles/17_levinshteyn-simin-logicheskie-shemyi-na-tranzistorah-e051e94b.md
source_content_sha256: 3a3e5a12427c778a650d8785ffdf207117e4bf9f07138b65e0c00ca4825a1860
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 44⟧

VI. Mạch logic bán dẫn

Tiến sĩ Khoa học Vật lý và Toán học M. E. LEVINSHTEIN, Ứng viên Khoa học Vật lý và Toán học G. S. SIMIN

Sau khi hiểu biết về các phép toán logic cơ bản (xem «Kvant», 1986, Số 1), giờ đây chúng ta có thể làm quen với cách chúng được thực hiện bằng cách sử dụng mạch bán dẫn.

Mạch logic đơn giản nhất thực hiện thao tác “OR” được hiển thị trong hình 1. Mạch chứa hai bóng bán dẫn phân cực sinh học thuộc loại “n-p-n”.

Ký hiệu này tương ứng với một bóng bán dẫn phân cực sinh học loại p-n-p; ký hiệu tương ứng với một bóng bán dẫn loại n-p-n.

Một mũi tên xiên tương ứng với bộ trống, một dấu gạch dọc tương ứng với phần đế và một dấu gạch ngang xiên không có mũi tên đối với bộ thu.

Bộ thu của các bóng bán dẫn thông thường được kết nối song song với cực “cộng” của nguồn điện E. Bộ phát được kết nối với điện trở tải Rₙ. Nếu hướng giữa cực gốc và cực trống của bóng bán dẫn bằng 0 thì điểm nối cực gốc và cực trống bị đóng, do đó không có dòng chảy qua nó. Do đó, amply thu trong mạch cũng bị mờ (transistor đóng). Từ hình 1, rõ ràng là nếu không có tín hiệu ở đầu vào của bóng bán dẫn, tức là hướng ở đầu vào Uₙ₁ và Uₙ₂ bằng 0, thì bóng bán dẫn đóng. Vì vậy, tôi không chạy qua điện trở tải Rₙ và tín hiệu đầu ra Uₙ₁=IRₙ cũng bằng 0. Nếu ít nhất một trong các hướng cung cấp cho đầu vào của mạch đủ để gửi các bóng bán dẫn T₁ và T₂, thì mạch sẽ đảo ngược mạnh và hướng đầu ra tăng đáng kể.

Các bóng bán dẫn silicon thường đóng nếu hướng đến điểm nối base-amptet nhỏ hơn 0,6 V. Do đó, trong mạch loại này, mức “số 0 logic” thường tương ứng với hướng U⁰, gần bằng 0 và “mức logic” - U¹≈0,8 V.

Hình 2 và 3 thể hiện mạch “AND” và “NOT” trên các bóng bán dẫn phân cực sinh học. Lập luận theo cách tương tự như khi phân tích mạch “OR”, có thể dễ dàng xác minh rằng đối với mạch “AND”, hướng đầu ra Uₙ₁>0 chỉ khi bóng bán dẫn T₁ và T₂ mở đồng thời, nghĩa là hướng tương ứng với đơn vị logic được áp dụng cho cả hai đầu vào (Uₙ₁=U¹, Uₙ₂=U¹). Trong sơ đồ “KHÔNG”, Uₙ₁=U¹ với Uₙ₂=U⁰ và ngược lại, Uₙ₁=U⁰ với Uₙ₂=U¹.

Một nhược điểm quan trọng của mạch logic dựa trên bóng bán dẫn phân cực sinh học là ở một trong các trạng thái của mạch, một dòng điện lớn chạy qua điện trở đầu ra Rₙ. Trong các máy tính chứa hàng triệu mạch logic, điều này dẫn đến tổn thất điện năng đáng kể, làm nóng mạch trong quá trình hoạt động và giảm độ tin cậy của máy tính. Nhược điểm này được loại bỏ trong các mạch logic dựa trên các bóng bán dẫn hữu ích*) bổ sung - mạch CMOS.

Một ví dụ về mạch CMOS được hiển thị trong hình 4.

*) “Bổ sung” dịch từ tiếng Anh có nghĩa là “bổ sung”.

Hình 1. Một ví dụ về việc triển khai mạch “OR” trên hai bóng bán dẫn phân cực sinh học loại n-p-n.

Hình 2. Ví dụ về cách thực hiện mạch “AND”.
Hình 3. Ví dụ về cách triển khai mạch “NOT”.

⟦folio 45⟧

TRONG TƯƠNG LAI TUYỆT VỜI, MÁY TÍNH SẼ XUẤT HIỆN, CÁC SƠ ĐỒ ĐỊA PHƯƠNG SẼ ĐƯỢC SẢN XUẤT BỞI GALLIUM CZAREND (Ga As).
Những kế hoạch này nhanh hơn đáng kể.
Bức ảnh vi mô hiển thị VIS dựa trên các bóng bán dẫn hiệu ứng trường Aspendall. Kích thước của VIS là 2,7×2,25 mm. Độ dài cổng của bóng bán dẫn trong VIS là ~1 µm.
Tốc độ chuyển đổi của các phần tử của ô logic VIS là 150 ps. Về hiệu suất, mạch này nhanh hơn bốn lần so với VIC silicon tốt nhất, tương tự như mục đích dự định của nó.

Sơ đồ chính và ký hiệu các điều kiện của chip logic hiện đại dòng K187 trên các bóng bán dẫn p-p-p silicon sinh học.
Mạch có 5 đầu vào và 2 đầu ra. Tại một trong các đầu ra (chân 6), điện áp tổng logic được tạo ra (thao tác “OR”) của sisal $x_1$—$x_5$, được cung cấp cho đầu ra 1—5, ở đầu ra còn lại (chân 7), một tín hiệu kết hợp hoạt động tổng hợp logic và đảo ngược (thao tác “OR”—“NOT”) được tạo ra.
Sự tồn tại của các điều kiện của mạch logic so với ô đơn giản nhất được hiển thị trong hình 1 là do nhu cầu đảm bảo hiệu suất cao, mức tiêu thụ điện năng thấp, sự không an toàn của các tham số mạch từ điện áp nguồn và số lượng mạch logic khác được kết nối với nó, yêu cầu về khả năng chống nhiễu của tín hiệu đầu ra logic, v.v.
Thời gian so sánh của vi mạch là khoảng $10^{-8}$ s, mức tiêu thụ hiện tại là ~ 10 mA.

Đường thẳng đứng biểu thị kênh bóng bán dẫn. Các đường ngang kéo dài từ nó là nguồn (dưới) và cống (trên). Một đường chạy song song với kênh bên cạnh tượng trưng cho cổng. Đầu ra cổng được vẽ ở cùng mức với đầu ra nguồn.

Máy biến áp MOS $T_1$ và $T_2$ được sử dụng trong mạch có các loại cấu trúc khác nhau. Tranitor $T_1$ thường mở, nghĩa là khi không có điện áp trên cổng, độ dẫn của kênh của nó cao; kẻ phản bội $T_2$ thường đóng; ở điện áp bằng 0 trên cổng, không có dòng điện nào chạy qua kênh của nó. Với điện áp dương đủ lớn trên cổng $U^1$, bộ giám sát thường mở $T_1$ bị khóa và $T_2$ thường đóng sẽ được mở khóa.

Trong mạch hiển thị ở hình 4, với $U_{bx}=0$ $T_1$ mở và $T_2$ đóng, do đó toàn bộ điện áp nguồn giảm xuống trên bộ tranitor $T_2$; vì sigma điện áp đầu ra với bộ tranitor $T_2$, $U_{bx}$ cao. Tại $U_{bx}=U^1$ $T_1$ đóng và $T_2$ mở, vì vậy $U_{bx} \approx 0$. Ở trạng thái chung, dòng điện chạy trong mạch bằng 0, vì một trong các bộ chuyển tiếp ở trạng thái đóng. Do đó, mạch CMOS chỉ tiêu thụ năng lượng từ nguồn tại thời điểm chuyển mạch. Dựa trên các mạch CMOS, các máy vi tính và máy vi tính đã được tạo ra có mức tiêu thụ điện năng thấp kỷ lục - chỉ bằng một phần microwatt. Những máy vi tính như vậy có thể được cung cấp năng lượng bởi một tế bào quang điện, trong đó ánh sáng từ đèn trung tâm là đủ để hoạt động.
