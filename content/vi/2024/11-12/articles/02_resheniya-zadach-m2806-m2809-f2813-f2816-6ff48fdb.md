---
id: 2024-11-12-resheniya-zadach-m2806-m2809-f2813-f2816-6ff48fdb
issue: kvant_2024_11-12
year: 2024
number: 11-12
title: Lời giải bài toán M2806—M2809; F2813—F2816
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 22
page_last: 22
page_labels: "20"
tag: D51Y
lang: vi
source: kvant_digital
extraction: native
content_sha256: 5ca1c7b545557be5391f2df8ab099c72fd1f93985e23878fb082e667db5f0685
prompt_sha256: draft-1
translated_from: content/ru/2024/11-12/articles/02_resheniya-zadach-m2806-m2809-f2813-f2816-6ff48fdb.md
source_content_sha256: 020639a9f514bcaa7d9ba2fb3e233748d0ab18f7e04ba624043345c4cdf89a03
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 20⟧

KVANT 2024/№11-12

F2830. Điện tích Q được phân bố đều trên diện tích của một quả cầu không dẫn điện có bán kính R. Trong thí nghiệm đầu tiên, một quả bóng nhỏ có điện tích q được đặt cách tâm quả cầu một khoảng 2R. Lực mà trường của quả cầu tích điện tác dụng lên quả bóng bằng $F_{1}$. Trong thí nghiệm thứ hai, quả bóng được lấy ra và cùng một điện tích q được phân bố đều dọc theo chiều dài của một thanh mỏng không dẫn điện có chiều dài R. Thanh này được đặt trên một đường thẳng đi qua tâm của quả cầu tích điện. Điểm của thanh gần tâm quả cầu nhất cách tâm quả cầu 2R. Tìm lực $F_{2}$ mà trường của quả cầu tác dụng lên thanh tích điện. Tất cả các thí nghiệm được thực hiện trong chân không cách xa các vật thể khác. Coi tất cả các lực ngoại trừ lực Coulomb là không đáng kể. V.Plis

F2831. Bánh dẫn động của máy phát điện xe đạp được ép vào thành lốp của bánh xe đạp. Đường kính của bánh dẫn động này là d. Phần ứng của máy phát điện, chứa N quay, mỗi phần có diện tích S, quay trong một từ trường đều có cảm ứng B. Người đi xe đạp phải đi với tốc độ bao nhiêu v để bóng đèn trong đèn pha xe đạp, được thiết kế để có giá trị hiệu dụng của điện áp U, phát sáng bình thường khi máy phát điện hoạt động? Điện trở của dây dẫn rôto và bóng đèn (ở điện áp định mức chạy qua nó) là như nhau. V.Plis

F2832. Ba nguồn phát đơn sắc kết hợp cùng pha được đặt trong chân không cách xa các vật thể khác tại các đỉnh của một tam giác đều cạnh a. Các bộ phát hoạt động ở tần số Q 100 MHz. Tại độ dài tối thiểu của cạnh của tam giác ở vùng xa trên phần tiếp theo của bất kỳ cạnh nào của tam giác thì sóng của ba nguồn triệt tiêu lẫn nhau? Tốc độ của sóng điện từ trong chân không là c 3 $10^{8}$ ms. S. Varlamov, V. Plis

Lời giải bài toán M2806–M2809, F2813–F2816

⟦column⟧

M2806. Có thể vẽ một đường đứt nét 20 khâu khép kín trên một mặt phẳng và đánh số các liên kết của nó bằng các số 1, 2, 3, ..., 20 theo thứ tự truyền tải sao cho với mỗi số nguyên dương i = 1, 2, 3, ..., 10 liên kết có số i và 10+i cắt nhau và không cắt các liên kết còn lại?

Đáp số: không thể được. Giả sử điều ngược lại và đặt $A_{1} A_{2}$ ... $A_{20}$ là một đường đứt nét cho trước. Gọi A là giao điểm của liên kết $A_{1} A_{2}$ và $A_{11} A_{12}$. Suy ra từ điều kiện 10 mắt xích đầu tiên của đường đứt nét không có điểm chung, ngoại trừ hai đầu cuối thì ta có một đường đứt đoạn khép kín không tự giao nhau $AA_{2} A_{3} A_{4}$ ... $A_{11} A$, tạm gọi đây là đường đứt nét C (Hình 1). Đồng thời

⟦figure⟧

Cơm. 1

các đỉnh $A_{1}$ và $A_{12}$ sẽ đồng thời ở bên trong hoặc đồng thời bên ngoài đường viền C. Hơn nữa, liên kết $A_{12} A_{13}$ cắt đường viền C đúng một lần, có nghĩa là các đỉnh $A_{12}$ và $A_{13}$ nằm ở các phần khác nhau của mặt phẳng so với đường viền C: một ở bên trong, một ở bên ngoài. Chúng ta suy luận tương tự với các cặp đỉnh $A_{13}$ và $A_{14}, A_{14}$ và $A_{15}$, …, $A_{20}$ và $A_{1}$. Hóa ra $A_{12}, A_{14}$, …, $A_{20}$ nằm ở một phần của mặt phẳng so với đường viền C, và $A_{13}, A_{15}$, …, $A_{19}, A_{1}$ – ở một phần khác. Nhưng điều này mâu thuẫn với kết luận trước đây của chúng tôi rằng $A_{1}$ và $A_{12}$ nằm trong cùng một phần của mặt phẳng đối với C. Điều này hoàn thành lời giải. Đây là sơ đồ của một lời giải khác. Chúng ta hãy sử dụng định lý nổi tiếng sau đây về cách tô màu các miền (thực ra nó khái quát hóa các khái niệm “bên ngoài” và “bên trong” cho các đường đứt nét tự giao nhau).
