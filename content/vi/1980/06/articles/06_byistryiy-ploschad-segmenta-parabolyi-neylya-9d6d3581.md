---
id: 1980-6-byistryiy-ploschad-segmenta-parabolyi-neylya-9d6d3581
issue: kvant_1980_6
year: 1980
number: "6"
title: Diện tích một đoạn của parabol Neil
authors:
  - Быстрый И. М.
rubric: osnovnye-stati
page_first: 16
page_last: 16
page_labels: "14"
tag: V8LA
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 45d988269017c8db76559a802af65fed2cbb293a01e01ca143e3b90a295593b5
prompt_sha256: draft-1
translated_from: content/ru/1980/06/articles/06_byistryiy-ploschad-segmenta-parabolyi-neylya-9d6d3581.md
source_content_sha256: d7766c52de411272b9a32de330b210da952b0d2cf323b56066e07a255e035116
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 14⟧

I. Bystry

Diện tích một đoạn của parabol Neil

Năm 1657, một sinh viên hai mươi tuổi tại Đại học Oxford, William Neil (1637–1670), đã tìm ra độ dài cung của một "parabol bán nguyệt" $y = a^3\sqrt{x^2}$. Khám phá này cho phép những người đương thời, và để tưởng nhớ nhà toán học tài năng đã mất sớm, parabol bán khối được gọi là parabol Neil.

Ngày nay, parabol của Neil không chỉ có thể được tìm thấy trong khóa học phân tích ở trường đại học mà còn trong sách giáo khoa ở trường *). Và gần đây, tại một buổi giảng dành cho các ứng viên, tôi nhận được thông báo sau:

Làm thế nào để tìm diện tích của một hình được tạo bởi đường cong $y = 3\sqrt{x^2}$ và tiếp tuyến với nó tại điểm $x = -8$?

Đây là những gì tôi đã trả lời sau đó.

bài toán này, mặc dù có vẻ đơn giản, nhưng lại gắn liền với định nghĩa về khó khăn.

Khó khăn đầu tiên nảy sinh trong việc tìm tiếp tuyến của parabol Neil

$$f_1(x) = 3\sqrt{x^2}$$

tại điểm $x = -8$. Như đã biết, phương trình tiếp tuyến được xác định theo công thức

$$y - f_1(-8) = f'_1(-8)(x + 8).$$

Đây

$$f_1(-8) = 12,$$

*) “Đại số và sự khởi đầu của phân tích 9”, bài toán 438, 4746, “Đại số và sự khởi đầu của phân tích 10”, bài toán 393a.

$$f'_1(-8) = 3\left(\frac{2}{3}\right)' \mid_{x = -8} = -3 \cdot \frac{2}{3}x^{-1} \mid_{x = -8} = 2 \cdot (-8)^{-1/3}.$$

Điều này có nghĩa là đạo hàm không tồn tại (vì biểu thức $(-8)^{-1/3}$ không có ý nghĩa), do đó, tiếp tuyến của đường cong (1) cũng không tồn tại.

Trong khi đó, từ hình vẽ cho thấy lựa chọn sai: đường thẳng $(AB)$ là tiếp tuyến! Có chuyện gì vậy? Làm thế nào để tìm độ dốc của một tiếp tuyến? Vấn đề là công thức

$$(\sqrt[n]{x^m})' = \left(x^{\frac{m}{n}}\right)' = \frac{m}{n}x^{\frac{m}{n}-1},$$

đúng với $x \geq 0$, không áp dụng ở đây. Để tính đạo hàm (tại $x < 0$), bạn nên sử dụng công thức

$$(\sqrt[n]{x^m})' = \frac{m}{n}\frac{\sqrt[n]{x^m}}{x},$$

$x \neq 0, n \in \mathbb{N}, m \in \mathbb{Z},$

(tất nhiên, điều này cũng áp dụng cho số dương $x$). Theo đó chúng ta có

$$f'_1(-8) = (3\sqrt{x^2})' \mid_{x = -8} = -3 \cdot \frac{2}{3}\frac{\sqrt[n]{(-8)^2}}{(-8)} = -1.$$

Thay $f_1(-8) = 12$ và $f'_1(-8) = -1$ vào đẳng thức (2), chúng ta thu được phương trình tiếp tuyến mong muốn:

$$y = 4 - x.$$

Bài tập 1. Tìm giao điểm của đường $f_1(x) = 3\sqrt{x^2}$ và $f_2(x) = 4 - x$.

Bây giờ đã biết hoành độ của điểm $B$, ta dễ dàng tìm được diện tích đường cong của tam giác thẳng AOB. Làm sao
