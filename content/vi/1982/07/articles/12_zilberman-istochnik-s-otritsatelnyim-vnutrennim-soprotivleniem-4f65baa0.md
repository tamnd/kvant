---
id: 1982-7-zilberman-istochnik-s-otritsatelnyim-vnutrennim-soprotivleniem-4f65baa0
issue: kvant_1982_7
year: 1982
number: "7"
title: Nguồn có điện trở trong "âm"
authors:
  - Зильберман А. Р.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 56
page_last: 57
page_labels: 54-55
tag: Y5N3
lang: vi
source: kvant_digital
extraction: vision
content_sha256: b0099e58c0c471b56b127521572818008cd0f19434da2769314338a956ade832
prompt_sha256: draft-1
translated_from: content/ru/1982/07/articles/12_zilberman-istochnik-s-otritsatelnyim-vnutrennim-soprotivleniem-4f65baa0.md
source_content_sha256: 3950f0e08dc7444ca502e5095adedde8c5685cbb296daf99e2a4aa7b871babe4
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 54⟧

A. Zilberman

Nguồn
với "tiêu cực"
nội bộ
các môn thể thao

Nhiều câu hỏi thú vị nảy sinh liên quan đến tính chất của nguồn trong đó sự phụ thuộc của điện áp vào dòng điện khác với sự phụ thuộc chung $U = \mathcal{E} - rI$ ($\mathcal{E} - \text{ЭДС}, r$ là điện trở trong của nguồn). Chúng ta sẽ xem xét một số câu hỏi này bằng ví dụ bài toán F727.

F727. Sự phụ thuộc của điện áp vào dòng điện đối với một nguồn năng lượng điện nhất định được thể hiện trong Hình 1. Vẽ đồ thị giữa điện áp và điện áp tại đó nguồn đóng và điện trở của điện áp.

Hãy nối một điện trở có điện trở $R$ với nguồn. Điện áp trên nó liên hệ với dòng điện bằng một mối quan hệ đơn giản - $U_H = RI$. Trong cùng một hình minh họa sự phụ thuộc $U(I)$ của điện áp nguồn vào dòng điện chạy qua nó, ví dụ như đường thẳng $U_H = RI$. Điểm giao nhau của đồ thị $U(I)$ và đường thẳng $U_H = RI$ không bao gồm dòng điện và điện áp. Đối với nguồn thông thường, trong đó điện áp áp suất thấp hơn, dòng điện càng cao thì không có vấn đề gì phát sinh nữa - chỉ có một điểm giao nhau và kết quả xác định là rõ ràng.

Cơm. 1.

Cơm. 2.

Cơm. 3.

⟦folio 55⟧

(Thật thú vị khi lưu ý rằng bằng cách sử dụng các nguồn như vậy, có thể thu được một lượng chuỗi độc lập. Được rồi, để làm được điều này, bạn cần có nguồn thứ hai.

Ví dụ, đối với một nguồn thông thường, mức tiêu thụ dòng điện giảm khi mức tiêu thụ dòng điện tăng, có thể xác định các giá trị của điện trở trong - bằng tỷ lệ thay đổi điện áp đầu ra với thay đổi dòng điện:

$$r = -\frac{\Delta U}{\Delta I}$$

Trong trường hợp của chúng tôi, ở một khu vực nhất định - trong phần $bd$ phụ thuộc $U(I)$ - điện trở trong của nguồn hóa ra là âm. Trong trường hợp này, tiết diện $bd$ lớn đến mức ngay cả tổng điện trở của mạch ($r + R$) cũng âm. Do đó có sự mất ổn định của điểm “ở giữa” và các “điều kỳ lạ” khác (bao gồm khả năng thu được các dao động độc lập: điện trở “âm” có thể bù đắp cho sự tổn thất trong hệ dao động; một cách tự nhiên, tất cả những điều này xảy ra mà không vi phạm định luật bảo toàn năng lượng - do năng lượng của nguồn).

Làm thế nào có thể đạt được toàn bộ sự phụ thuộc của đường cong $U(I)$, nếu cả hai đều giảm và tăng điện trở

Phân tán chip

(Để bắt đầu, xem trang 28)

thực hiện nhiệm vụ d). Hóa ra những khái niệm này đủ để giải bài toán Kontsevich cho bất kỳ tập hợp $G$ nào. Hơn nữa, có một thuật toán (khá phù hợp với lập trình máy tính) cho phép người ta giải bài toán của Kontsevich cho $G$ trong một số bước hữu hạn - hoặc để thiết lập tính không thể quyết định của nó hoặc để chỉ ra chuỗi các bước di chuyển bình thường bị xóa bởi $G$. Thuật toán này dựa trên các thông báo sau.

Chúng ta hãy giảm giải phóng bài toán xuống mức chuẩn hóa bài toán với vị trí ban đầu $A$. Sau đó, chúng ta vẽ các đường ngang và dọc giới hạn vị trí đã cho $A$ từ phía trên và bên phải; chúng ta thu được một hình chữ nhật $m \times n$ chứa tất cả các mã thông báo của vị trí - cái gọi là hình chữ nhật bài toán ($A_{ij} \geq 0$, với $A_{ij} = 0$ tại $i > m$ hoặc $j > n$). Di chuyển các đường thẳng sang phải trở lên hai ô, chúng ta sẽ có một hình chữ nhật nằm ở $P$ bài toán $(m + 2) \times (n + 2)$. Thuật toán của chúng tôi như sau.

Xác định vị trí, xây dựng một hình chữ nhật mở rộng $P$ và thực hiện các bước di chuyển cần thiết (theo bất kỳ thứ tự nào - chẳng hạn như theo chiều ngang, ở ô đầu tiên, sau đó ở ô thứ 2, v.v.).

Cơm. 8.

Nếu bạn cần đặt mã thông báo ngoài $P$ thì bài toán là không thể giải quyết được. Ngược lại, nếu chúng ta hoàn thành tất cả các bước di chuyển cần thiết, chúng ta sẽ nhận được lời giải (trong giới hạn $P$!).

Thiếu không gian không cho phép chúng tôi cung cấp bằng chứng về thực tế đã nêu. Có lẽ độc giả sẽ có thể chứng minh được điều đó. Và đối với sinh viên Lập trình Trường Tương ứng, chúng tôi khuyên bạn nên viết chương trình giải quyết bài toán Kontsevich trong trường hợp tổng quát.
