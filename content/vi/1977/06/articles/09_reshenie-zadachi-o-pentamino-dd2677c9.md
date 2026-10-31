---
id: 1977-6-reshenie-zadachi-o-pentamino-dd2677c9
issue: kvant_1977_6
year: 1977
number: "6"
title: '[Lời giải bài toán về pentomino]'
rubric: smes
page_first: 39
page_last: 39
page_labels: "37"
tag: PRET
lang: vi
source: kvant_digital
extraction: vision
content_sha256: aa765ab00bcba17274b148f3e0a317356172390c784e77c1a7a7fb427123ef60
prompt_sha256: draft-1
translated_from: content/ru/1977/06/articles/09_reshenie-zadachi-o-pentamino-dd2677c9.md
source_content_sha256: e3d7d308b5557fe46e692bbc709c8a8ab4b9ec6b98cf9142e776b09eab7ba8f4
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 37⟧

rồi hai phổ bậc hai, v.v. Khi bậc của phổ tăng lên, khoảng cách giữa các vạch tương ứng của quang phổ tăng lên, do đó các quang phổ có thể chồng lên nhau. Ví dụ, đối với ánh sáng mặt trời, quang phổ của bậc hai và bậc ba đã chồng chéo một phần.

Bây giờ chúng ta hãy chuyển trực tiếp đến trải nghiệm. Để thay đổi bước sóng tương ứng với một màu nhất định, cần xác định chu kỳ của cách tử $(d)$, sin của góc tới của ánh sáng trên cách tử $(\sin \theta)$ và sin của góc xác định hướng đến mức tối đa nào đó, ví dụ: đến mức tối đa bậc nhất $(\sin \varphi_1)$. Khoảng thời gian lưới rất dễ tìm thấy bằng cách phát một bản ghi:

$$d = \frac{\Delta R}{n \Delta t}.$$

Ở đây $\Delta R$ là giá trị tuyệt đối của chuyển động của kim dọc theo bán kính của tấm trong thời gian $\Delta t$, $n$ là số vòng quay trên một đơn vị thời gian. Thông thường $d \approx 0,01$ xem.

Bạn có thể sử dụng đèn bàn thông thường làm nguồn sáng. Để ngăn ánh sáng từ nó cản trở việc quan sát mẫu nhiễu xạ, hãy tạo một màn hình có một khe bằng bìa cứng và che đèn bằng nó. Trong trường hợp này, dây tóc đèn phải được nhìn thấy qua khe. Đặt đèn gần một bức tường của căn phòng, đặt tấm nằm ngang gần bức tường đối diện và tìm ảnh của khe (Hình 3). Đồng thời, bạn sẽ thấy các sọc màu mờ. Đây là phổ bậc nhất $(k = 1)$. Có thể dễ dàng xác minh rằng thực tế là góc $\theta$ càng lớn thì ảnh màu của khe thu được càng rộng và chúng ta có thể thay đổi góc nhiễu xạ của ánh sáng có bước sóng mà chúng ta quan tâm càng chính xác.

Để xác định $\sin \varphi_1$, bạn cần nhờ một người bạn ngủ và giữ thẻ (hoặc một số vật thể khác) trên khe sao cho hình ảnh của nó dưới ánh sáng phản chiếu từ cách tử (như từ gương phẳng) trùng với phần quang phổ đã chọn (xem Hình 3). Sau khi đo $a$, $b$ và $h$ bằng thước, chúng ta tìm thấy $\sin \varphi_1$ và $\sin \theta$:

$$\sin \varphi_1 = \frac{a}{\sqrt{a^2 + b^2}},$$

$$\sin \theta = \frac{a}{\sqrt{a^2 + h^2}}.$$

Những biểu thức này có thể được đơn giản hóa phần nào. Vì $b \ll a$ và $h \ll a$, $$\frac{a}{\sqrt{a^2 + b^2}} = \frac{1}{\sqrt{1 + b^2/a^2}} \approx 1 - \frac{1}{2} \frac{b^2}{a^2}$$

và $$\frac{a}{\sqrt{a^2 + h^2}} = \frac{1}{\sqrt{1 + h^2/a^2}} \approx 1 - \frac{1}{2} \frac{h^2}{a^2}.$$

Rồi cuối cùng

$$\lambda = d | \sin \varphi_1 - \sin \theta | \approx d \frac{|h^2 - b^2|}{2a^2}.$$

Sau khi đo bước sóng của ánh sáng có màu sắc khác nhau, thật thú vị khi so sánh chúng với các giá trị trong bảng. Trong các thử nghiệm của chúng tôi, với những hình ảnh cẩn thận, sai số vào khoảng $10^{-8}$ m. Đối với bước sóng của ánh sáng khả kiến ​​($\lambda \sim 10^{-7}$ m), độ chính xác của sóng như vậy có thể chấp nhận được.

Trong số thứ hai của tạp chí năm nay, chúng tôi đã cung cấp cho độc giả một số bài toán liên quan đến pentamino. Hai độc giả (L. Mutalup từ vùng Anjan và Yu. Stasevich từ vùng Voroshilgovgrad) đã giải được một trong bộ pentamino hoàn chỉnh đồng thời hai hình chữ nhật $4 \times 5$ và $4 \times 10$. lời giải của chúng giống nhau đối với hình chữ nhật nhỏ và khác nhau đối với Volt lớn, chúng là:
