---
id: 1989-6-vilenkin-kotkin-gaz-na-displee-ca0478fa
issue: kvant_1989_6
year: 1989
number: "6"
title: Khí được trưng bày
authors:
  - Виленкин А. Н.
  - Коткин Г. Л.
rubric: raznoe
rubric_sub: Разное
page_first: 63
page_last: 63
page_labels: "61"
tag: M9G4
lang: vi
source: kvant_digital
extraction: vision
content_sha256: f4ed05249bd102ab807fec081d787a261387c199b46992f506a722605e97b470
prompt_sha256: draft-1
translated_from: content/ru/1989/06/articles/17_vilenkin-kotkin-gaz-na-displee-ca0478fa.md
source_content_sha256: 7342104db835310ce43043f9ad1434a6b72978cb0bf071476ba5275061a33a61
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 61⟧

Khí được trưng bày

A. N. VILENKIN,
Ứng viên Khoa học Vật lý và Toán học
G. L. KOTKIN

Ghi chú này, một bài viết bổ sung “Khí của các quả cầu quặng lớn” (xem trang 2), cho biết cách tạo một chương trình mô phỏng chuyển động của một số quả cầu quặng lớn. Mô tả được trình bày dưới dạng sao cho người đọc có thể tin tưởng vào chương trình bằng ngôn ngữ lập trình cụ thể.

Chương trình “Khí” (chúng tôi sẽ gọi nó như vậy) được chia hợp lý thành bảy khối: mô tả các biến và chuẩn bị dữ liệu, khởi chạy ban đầu, chuẩn bị màn hình, tính toán tác động quặng lớn, tính toán tọa độ mới, hiển thị thông tin trên màn hình, bộ điều khiển mô hình.

Mô tả các biến và chuẩn bị dữ liệu. Để mô tả hệ thống, các biến sau sẽ được sử dụng: N - số lượng bóng; a là bán kính của mỗi quả bóng; T — bộ đếm thời gian (tại thời điểm ban đầu T=∅), T∘ — bước thời gian; A1 và A2 là ranh giới của màn hình. Giá trị của các biến này tốt nhất nên được đặt trong chương trình để có thể thay đổi (bằng cách chỉnh sửa chương trình), nhưng không cần phải nhập cho mỗi thử nghiệm.

Trạng thái của các quả bóng được mô tả bằng 4 biến cho mỗi quả bóng: tọa độ x và y của tâm quả bóng và các thành phần vận tốc vx và vy. Tất cả các biến này phải được mô tả dưới dạng một mảng R(4, N), vì công thức tính toán cho chúng giống nhau. Đối với các vị trí bóng cũ, bạn sẽ cần một mảng RS(2, N).

Ra mắt ban đầu. Khối này bao gồm việc yêu cầu các giá trị ban đầu của tọa độ tâm và các thành phần vận tốc của quả bóng. Tại đây bạn có thể đặt T∘ - “bước” của quy trình.

Chuẩn bị màn hình. Màn hình hiển thị ở chế độ đồ họa có độ phân giải cao là một phần của mặt phẳng tọa độ xy bao gồm các “điểm” có tọa độ nguyên nằm trong các giới hạn nhất định (ví dụ: 1<x<256, 1<y<192). Các ranh giới của màn hình được xác định bởi các biến A1 và A2, nhưng phải cẩn thận để tránh các quả bóng không những rơi ra ngoài các ranh giới này mà còn không rơi vào các hình ảnh của ranh giới bàn. Vì vậy, trong khối này bạn cần chuyển màn hình sang chế độ phân giải cao, ví dụ vẽ ranh giới của bảng và tính ranh giới vị trí các tâm của các quả bóng (chẳng hạn như G1=1+a+1, G2=A1-a-1).

Tính toán tác động lớn hơn. Trong khối này cần tính mômen TC của bảng thứ nhất, mô tả loại bàn dưới dạng công tắc giá trị K và số lượng bi bàn dưới dạng giá trị N1, N2 sao cho kết quả của khối như sau: bảng thứ nhất là bảng N1, có K=1 - có tường ngang, K=2 - có tường thẳng đứng, K=3 - có bóng N2.

Trong thực tế, trước tiên bạn phải đặt TC lớn và N1=∅, N2=∅, K=∅. Sau đó trong một vòng lặp (theo số bóng)
