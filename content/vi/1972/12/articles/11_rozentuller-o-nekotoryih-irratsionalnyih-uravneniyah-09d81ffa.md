---
id: 1972-12-rozentuller-o-nekotoryih-irratsionalnyih-uravneniyah-09d81ffa
issue: kvant_1972_12
year: 1972
number: "12"
title: Về một số phương trình vô tỉ
authors:
  - Розентуллер В. М.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 53
page_last: 54
page_labels: 51-52
tag: C2O4
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 5ccdb255fc58e93f23e9ea13a3c9533e5ca0089b1567223c4ba18eab5cf56782
prompt_sha256: draft-1
translated_from: content/ru/1972/12/articles/11_rozentuller-o-nekotoryih-irratsionalnyih-uravneniyah-09d81ffa.md
source_content_sha256: 42fcb89791fdeccc9509e02bee6f43dd8ad4ad46dbef7f5e6db3002dcce41101
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 51⟧

Về một số phương trình vô tỉ

V. M. Rosentuller

Các kỹ thuật của phương trình vô tỷ lời giải đã được thảo luận chi tiết trong bài viết của A. M. Grigoriev “Phương trình vô tỷ” («Kvant» Số 1, 1972). Nhưng ví dụ chung không phải lúc nào cũng tốt nhất. Bài viết này sử dụng ba ví dụ để chứng minh một phương pháp cho phép bạn giải một số phương trình nhất định (trên thực tế, không chỉ vô tỷ) một cách nhanh chóng và “đẹp”.

Ví dụ 1. Giải phương trình:

$$\sqrt{x - 30} + \sqrt{2x + 4} = 8.$$

Lời giải. ODZ được xác định bởi hệ bất đẳng thức

$$\begin{cases} x - 30 \geq 0, \\ 2x + 4 \geq 0, \end{cases}$$

Ở đâu

$$x \geq 30.$$

Sau đó bạn có thể tiến hành như thế này. Hãy bình phương cả hai bên và nhận được:

$$x - 30 + 2x + 4 + 2\sqrt{2x^2 - 56x - 120} = 64,$$

$$2\sqrt{2x^2 - 56x - 120} = 90 - 3x.$$

Chúng ta phải bình phương cả hai vế của phương trình này*):

$$8x^2 - 224x - 480 = 8100 - 540x + 9x^2,$$

$$x^2 - 316x + 8580 = 0,$$

$$x_{1,2} = 158 \pm \sqrt{158^2 - 8580} = 158 \pm \sqrt{16884} = 158 \pm 128;$$

$$x_1 = 286, x_2 = 30.$$

*) Trong trường hợp này, phương trình cuối cùng đã rõ ràng rằng $x \leq 30$ và chỉ cần kiểm tra $x = 30$, nhưng đây là một tai nạn.

Việc kiểm tra cho thấy rằng $x_1 = 286$ là một nghiệm được xây dựng và $x_2$ thỏa mãn các điều kiện bài toán.

Đáp số: $x = 30$.

Chúng tôi đã giải được phương trình đòi hỏi phải bình phương nó hai lần và kiểm tra nghiệm. Không có lời giải nào đơn giản hơn sao?

Chúng tôi đã xác định ODZ: $x \geq 30$. Có thể sử dụng ngay điều này cho lời giải của phương trình này không? Hãy thử.

ODZ cho phép: $x = 30$ và $x > 30$. Hãy kiểm tra $x = 30$. Hãy thay thế giá trị $x = 30$ vào phương trình này:

$$\sqrt{30 - 30} + \sqrt{60 + 4} = 8,$$

$$0 + 8 = 8,$$

$$8 = 8.$$

Chúng tôi đã nhận được vinh dự. Do đó, $x = 30$ là nghiệm của phương trình này. Bây giờ tất cả những gì còn lại là kiểm tra $x > 30$.

Với $x > 30$ chúng ta có $\sqrt{x - 30} > 0,$

$$\sqrt{2x + 4} > 8,$$

Ở đâu

$$\sqrt{x - 30} + \sqrt{2x + 4} > 8.$$

Do đó, mọi $x > 30$ đều không thỏa mãn phương trình. Người duy nhất còn lại là đáp số: $x = 30$.

Ví dụ 2. Giải phương trình:

$$5\sqrt{2x - 24} + 3\sqrt{5x - 59} + \sqrt{x - 8} + \sqrt{3x - 20} + \sqrt{x + 13} + 2\sqrt{x + 24} = 26.$$

Lời giải. ADL được xác định

⟦folio 52⟧

hệ bất đẳng thức:

$$\begin{cases} x \geq 12, \\ x \geq 11,8, \\ x \geq 8, \\ x \geq 6\frac{2}{3}, \\ x \geq -13, \\ x \geq -24, \end{cases}$$

từ đâu $x \geq 12$.

Do đó, ODZ cho phép: $x=12$ và $x>12$.

Hãy kiểm tra $x=12$: $5\sqrt{24-24} + 3\sqrt{60-59} + \sqrt{12-8} + \sqrt{36-20} + \sqrt{12+13} + 2\sqrt{12+24} = 0 + 3 + 2 + 4 + 5 + 12 = 26$.

Chúng tôi đã nhận được vinh dự. Do đó, $x=12$ là nghiệm của phương trình.

Bây giờ hãy kiểm tra $x>12$:

$$5\sqrt{2x-24} > 0,$$

$$3\sqrt{5x-59} > 3,$$

$$\sqrt{x-8} > 2,$$

$$\sqrt{3x-20} > 4,$$

$$\sqrt{x+13} > 5,$$

$$2\sqrt{x+24} > 12.$$

Do đó $5\sqrt{2x-24} + 3\sqrt{5x-59} + \sqrt{x-8} + \sqrt{3x-20} + \sqrt{x+13} + 2\sqrt{x+24} > 26,$

mâu thuẫn với điều kiện bài toán. Người duy nhất còn lại là đáp số: $x=12$.

Ví dụ 3. Giải phương trình:

$$\sqrt{x(x+1)} = \sqrt{x+3} - \sqrt{1 + \frac{1}{x^2}}.$$

Lời giải. Hãy nhóm các số hạng của phương trình như thế này:

$$\sqrt{x^2+x} + \sqrt{1 + \frac{1}{x^2}} = \sqrt{x+3}.$$

Hãy bình phương cả hai cạnh:

$$x^2+x+1 + \frac{1}{x^2} +$$

$$+ 2\sqrt{(x^2+x)\left(1 + \frac{1}{x^2}\right)} = x+3,$$

$$2\sqrt{x^2+x+1 + \frac{1}{x}} = x+3 - x^2 - x - 1 - \frac{1}{x^2},$$

$$2\sqrt{x^2+x+1 + \frac{1}{x}} = 2 - \left(x^2 + \frac{1}{x^2}\right).$$

Người ta biết rằng $x^2 + \frac{1}{x^2} \geq 2$, nhưng $\sqrt{x^2+x+1 + \frac{1}{x}} \geq 0$, nên $x^2 + \frac{1}{x^2} = 2$ và $\sqrt{x^2+x+1 + \frac{1}{x}} = 0$.

Đẳng thức đầu tiên có thể xảy ra khi $x^2=1$, từ đó $x_1=1; x_2=-1$ và đẳng thức thứ hai $\sqrt{x^2+x+1 + \frac{1}{x}} = 0$ khi $x=-1$. Việc kiểm tra cho thấy $x=-1$ là nghiệm của phương trình.

Đáp số cho ô chữ (xem trang 4 của bìa)

Nằm ngang:

8. Farad. 9. Đỉnh cao. 10. Chuyển số. 11. Tần số. 12. Gauss. 15. Quán tính. 16. Đường kính. 18. Ebonit, 19. Boron. 20. Budker. 23. Phân đoạn. 25. Kelvin. 28. Lượng tử. 29. Lượng calo. 30. Photon. 33. Làm việc. 34. Hạt nhân.

Thẳng đứng:

1. Dirac. 2. Mặt dây chuyền. 3. Quang phổ. 4. Cato. 5. Vanadi. 6. Con lắc. 7. Descartes. 13. Archimedes. 14. Xung lực. 17. Bsr. 21. Tokamak. 22. Medina. 24. Tantali. 26. Đồng vị. 27. Lorenz. 31. Photon. 32. Jacobi.
