---
id: 1985-4-eppel-formula-ploschadi-segmenta-78dfab7b
issue: kvant_1985_4
year: 1985
number: "4"
title: Công thức tính diện tích phần
authors:
  - Эппель Б. С.
rubric: smes
page_first: 48
page_last: 48
page_labels: "46"
tag: XYF9
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 931ed0a4e4fad9a865162f940bff41c50d77e0598ac7a05b3dbe68837325c968
prompt_sha256: draft-1
translated_from: content/ru/1985/04/articles/17_eppel-formula-ploschadi-segmenta-78dfab7b.md
source_content_sha256: e05c471fd0853ac2408eacb85220d65674c0e55df44037bd89ed8f10983a3518
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 46⟧

F912. Dòng điện một chiều được tạo ra trong cuộn dây siêu dẫn, được nối với nguồn dòng điện thông qua công tắc $K_1$ (xem hình). Sau đó, một cục pin gồm hai tụ điện giống hệt nhau mắc song song được nối vào đầu cuộn dây. Công tắc $K_1$ được mở, sau đó dòng điện bắt đầu chạy qua các tụ điện, sạc chúng. Tại thời điểm điện áp trên các tụ đạt cực đại và dòng điện bằng 0, công tắc kép $K_2$ được chuyển từ cơ sở 1 sang cơ sở 2, sao cho các tụ điện mắc nối tiếp và điện áp trên cuộn dây tăng gấp đôi. Vì độ tự cảm của cuộn dây không thay đổi nhưng điện áp tăng lên nên dòng điện cực đại qua cuộn dây và do đó năng lượng tích trữ sẽ lớn hơn dòng điện tương tự đầu tiên. Tìm lỗi trong phép tính trên.

Công thức tính diện tích phần

Diện tích của đoạn $AnB$ (hình 1) có thể được tìm thấy bằng công thức

$$S_{\text{сегм}} = \frac{\pi R^2}{360^\circ} \cdot a - \frac{R^2}{2} \sin a,$$

(1)

trong đó góc ở tâm $\alpha$ được biểu thị bằng độ; hoặc, nếu cùng một góc tính bằng radian là $\varphi$, theo công thức

$$S_{\text{сегм}} = \frac{R^2}{2} (\varphi - \sin \varphi).$$

(2)

Công thức (1) rất dễ suy ra: diện tích của đoạn $AnB$ bằng hiệu giữa diện tích của đoạn $OAnB$ ($\frac{\pi R^2}{360^\circ} \cdot a$, tức là diện tích của đoạn một độ, nhân với số độ) và tam giác $OAB$ ($\left(R^2/2\right) \sin a$).

Công thức hữu ích này không chỉ đúng khi $\alpha < 180^\circ$ (như trên hình 1) mà còn đúng với mọi $\alpha$, bao gồm $\alpha \ge 180^\circ$ (hình 2, 3). Thật vậy, tại $\alpha > 180^\circ$ (hình 2) diện tích của tam giác $OAB$ phải được cộng với diện tích của hình cung $OAnB$, nhưng trong trường hợp này $\sin \alpha < 0$ và công thức (2) một lần nữa cho kết quả đúng đáp số! Trường hợp $\alpha = 180^\circ$ cũng phù hợp với công thức (2), từ đó $\sin \alpha = 0$, và diện tích tam giác suy biến $OAB$ bằng 0 (hình 3).

Khi đi qua góc $\alpha = 180^\circ$, dấu của sin thay đổi từ mặt phẳng sang dấu trừ; trên hình điều này sẽ trả lời chính xác thực tế là không được trừ mà phải cộng các số được tô bóng. Một hiệu ứng tương tự cũng được quan sát thấy trong định lý cosine, khi dấu thay đổi khi đi qua góc $\gamma = 90^\circ$.

V. S. Eppel
