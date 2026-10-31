---
id: 1978-9-meshoyrer-kombinatornyie-dokazatelstva-formulyi-nyutona-4ffd767d
issue: kvant_1978_9
year: 1978
number: "9"
title: Chứng minh tổ hợp của công thức Newton
authors:
  - Мешойрер Р.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 47
page_last: 48
page_labels: 45-46
tag: FIUF
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 866010bae2dfe912a83067d47c1c936d91cef2d8e833c2b0efd572428cf88254
prompt_sha256: draft-1
translated_from: content/ru/1978/09/articles/15_meshoyrer-kombinatornyie-dokazatelstva-formulyi-nyutona-4ffd767d.md
source_content_sha256: 1ab3ffc507f7977df62f4f554592ed66771aeb8874252833b2c0c5d44daed15f
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 45⟧

Những ngày nghỉ lễ đã đến, những ngày học đã bắt đầu. Trong phần tạp chí của chúng tôi cũng có một năm học mới, đã là năm thứ ba liên tiếp. Trong hai năm qua, các bài viết trong phần này đã đề cập đến những vấn đề khó khăn và quan trọng nhất liên quan trực tiếp đến chương trình học ở trường. Chúng tôi muốn thu hút sự chú ý của bạn đến các bài báo đã được xuất bản - sẽ rất hữu ích khi tham khảo chúng khi bạn nghiên cứu sách giáo khoa ở trường:

Đại số và sự khởi đầu của phân tích

“Khái niệm chức năng nảy sinh và phát triển như thế nào” (1977, số 7),
"Hàm chẵn và kiểm tra" (1977, số 4),
“Chức năng định kỳ” (1976, số 12),
"Chú ý: tối đa!" (1976, số 10),
“Ý nghĩa hình học của sự tùy ý” (1977, số 2),
“Một parabol trông như thế nào?” (1978, số 3),
"Chứng minh tổ hợp công thức Newton" (1978, số 8),
“Bổ sung dao động điều hòa” (1976, số 11),
"Diện tích và tích phân" (1977, số 5),
"Đạo hàm hàm số mũ" (1977, số 12),
“Phân tích giúp đại số” (1978, số 6),
“Câu hỏi về đại số và giải tích” (1978, số 2),
"17 bài toán theo phân tích" (1977, số 1),

Hình học

"Sự làm chủ của sự đối xứng" (1976, số 9),
“Thành phần đối xứng hai trục” (1978, số 2),
“Sự đồng nhất và những điểm đáng chú ý trong một tam giác” (1977, số 10),
“Shchest 驹 chứng minh định lý về số trung vị” (1978, số 4),
"Khoảng cách từ điểm đến mặt phẳng" (1977, số 3),
“Ý cậu ‘nhiều hơn’ là sao?” (1977, số 11),
“Tìm cách xác định diện tích bề mặt” (1978, số 5),

***

"Bài toán lặp lại" (1977, số 9),
“Câu hỏi dành cho sinh viên tốt nghiệp” (1978, số 7).

Năm học này chúng tôi sẽ tập trung nhiều hơn vào việc áp dụng phân tích vào lời giải toán và thực hành bài toán. Nó được kỳ vọng sẽ thể hiện sâu hơn các ứng dụng tùy ý, làm sáng tỏ đầy đủ các vấn đề xác định độ dài của hình tròn và diện tích của bề mặt nhân tạo cũng như phân tích phương pháp xây dựng các phần của khối đa diện.

R. Meschoir

Chứng minh tổ hợp của công thức Newton

Năm học đã bắt đầu. Học sinh lớp 9 sẽ sớm làm quen với các khái niệm như quy nạp, tổ hợp và quần xã Newton. Chứng minh ban đầu của công thức Newton được cậu học sinh lớp 9 năm ngoái, học sinh Trường Moscow số 444, Roman Meschoir, gửi đến biên tập viên. Chúng tôi đã bổ sung thêm hai bằng chứng tổ hợp (nổi tiếng hơn) vào bài báo của anh ấy.

Trong sách giáo khoa “Đại số và sự khởi đầu của phân tích 9”, đoạn 9 cung cấp nguồn gốc của công thức Newton.

$$a + b)^n = a^n + C_n^1 a^{n-1} b + \ldots + C_n^k a^{n-k} b^k + \ldots + b^n,$$

dựa trên phương pháp quy nạp toán học. Ở đây chúng tôi trình bày một bằng chứng tổ hợp của công thức này (mặc dù chỉ cho a và b tự nhiên).

Hãy xem xét điều này bài toán: chúng ta có thể tô màu n bằng bao nhiêu cách?

⟦folio 46⟧

yatsik, nếu có sự hủy bỏ sơn đỏ và b hủy bỏ màu xanh lam.

Một mặt, có $(a + b)^n$ các phương pháp như vậy: hộp đầu tiên có thể được sơn bằng bất kỳ sắc thái nào trong số $a + b$, hộp thứ hai (bất kể sắc thái đầu tiên!) - cũng có bất kỳ sắc thái nào trong số $a + b$, có nghĩa là đối với hai hộp đầu tiên có $(a + b)(a + b) = (a + b)^2$ các màu có thể có, v.v.

Mặt khác, số màu bằng vế phải của đẳng thức (1). Hãy chứng minh điều này bằng cách tính con số này theo cách khác. Đầu tiên, chúng ta hãy tìm số lượng màu mà tất cả $n$ hộp đều có màu đỏ (có rất/không có màu nào - $a^n$); sau đó chúng ta sẽ tìm số lượng màu mà trong đó có chính xác một hộp có màu xanh lam (có $nba^{n-1}$) hoặc có $n$ cách chọn hộp mà chúng ta sẽ sơn màu xanh đỏ, có $b$ sắc thái cho hộp đó và $a^{n-1}$ màu cho các hộp $n-1$ còn lại); ...; Tiếp theo, chúng ta sẽ tìm số lượng màu mà tất cả $n$ hộp đều có màu xanh lam (có $C_n^k b^k a^{n-k}$ trong số đó hoặc có $C_n^k$ cách chọn trong số $n$ hộp $k$ hộp mà chúng ta sẽ sơn màu xanh đỏ *), đối với những hộp $k$ này có $b^k$ màu, cho những hộp còn lại $n-k$ hộp tồn tại $a^{n-k}$ trang tô màu); ...; cuối cùng, chúng tôi tìm thấy số lượng màu mà tất cả $n$ hộp đều có màu xanh lam (có $b^n$ trong số đó). Vậy tổng số màu bằng

$$a^n + nba^{n-1} + \dots + C_n^k b^k a^{n-k} + \dots + b^n,$$

và tổng này trùng với vế phải của công thức (1), từ đó chứng minh được điều này.

Nếu bạn hiểu rõ cách chứng minh này thì bạn sẽ có thể chứng minh sự tổng quát hóa của công thức Newton cho trường hợp số hạng $m$ (tự nhiên):

$$(a_1 + a_2 + \dots + a_m)^n = a_1^n + \dots + N_{k_1 k_2 \dots k_m}^n a_{k_1}^k a_{k_2}^k \dots a_m^k m + \dots + a_m^n,$$

(*) “Đại số và nguyên lý giải tích 9”, đoạn 6.
