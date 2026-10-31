---
id: 1971-5-petrov-chto-zdes-teryaem-ili-nahodim-3b8645f8
issue: kvant_1971_5
year: 1971
number: "5"
title: Ở đây — mất hay tìm thấy?
authors:
  - Петров В. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 42
page_last: 43
page_labels: 40-41
tag: 1QIU
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 2ed9bbf2fbb619723fb3f99552b7a516d8e888192cd642883a144f7e49924285
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1971/05/articles/10_petrov-chto-zdes-teryaem-ili-nahodim-3b8645f8.md
source_content_sha256: 97fe5dc4ab9a79753b0b4e2ffabccd53b938a2bbe589894eb51d1ab7738b5f5e
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦folio 40⟧

Ở ĐÂY—MẤT HAY TÌM THẤY?

V. A. Petrov

Hầu như mỗi bài thi viết môn toán đều có một phương trình nào đó. Khi giải nó, người dự thi không những phải thực hiện không sai các phép tính cần thiết để nhận được đáp số, mà còn phải chứng minh tính đúng đắn của các phép tính ấy. Cần biết phân tích từng phép biến đổi được đề xuất: nó có dẫn đến một phương trình tương đương không, có đe dọa làm mất hay xuất hiện nghiệm không.

Các vấn đề về chiến thuật “đấu tranh” với các nghiệm dựng thêm và với sự mất nghiệm đã được xét trong bài viết của A. G. Mordkovich “Có người mất, có người tìm thấy” (“Kvant” Số 5, 1970)*). Bây giờ chúng tôi đề nghị bạn kiểm tra xem bạn đã nắm vững chiến thuật này đủ chắc chưa. Trước hết đưa ra các lời giải phương trình. Bạn cần phân tích các lời giải này và trả lời câu hỏi sau. Đáp số nhận được có đúng không? Nếu không, thì ở đây — mất nghiệm hay xuất hiện nghiệm ngoại lai? Vì sao? Đáp số đúng là gì? Hãy so sánh những suy nghĩ của bạn với của chúng tôi, được đăng ở trang 62.

1. $2\sin 4x = \sqrt{2(1 - \cos 4x)}$.

Lời giải. Dùng công thức
$$2\sin^2\alpha = 1 - \cos 2\alpha,$$
ta được
$$2\sin 4x = \sqrt{4\sin^2 2x}$$
hay
$$\sin 4x = \sin 2x,$$
điều này đã được giải rất dễ dàng.

Đáp số: $x = n\pi$ và $x = \frac{\pi}{6} + n\frac{\pi}{3}$, trong đó $n = 0, \pm 1, \pm 2, \dots$

*) Chi tiết hơn, “chiến thuật” này được trình bày trong cuốn sách rất bổ ích cho thí sinh vào đại học của G. V. Dorofeev, M. K. Potanov, N. Kh. Rozov “Sách hướng dẫn toán học cho người vào đại học”, M., “Nauka”, 1970.

2. $8\cos x\cos 2x\cos 4x = 1$.

Lời giải. Nhân cả hai vế của phương trình với sin $x$ và ba lần dùng công thức sin của góc gấp đôi, ta nhận được phương trình đơn giản
$$\sin 8x = \sin x.$$
Đáp số: $x = (2n + 1)\frac{\pi}{9}$ và $x = 2n\frac{\pi}{7}$, trong đó $n$ — một số nguyên bất kỳ.

3. $\sin \left(\frac{1}{5}\arccos x\right) = 1$.

Lời giải. Từ phương trình đã cho, ta tìm được
$$\arccos x = \frac{5\pi}{2} + 10n\pi$$
($n = 0, \pm 1, \pm 2, \dots$).

⟦folio 41⟧

Từ đây, theo định nghĩa của arccos $x$, ta có $x = \cos \left( \frac{5\pi}{2} + 10n\pi \right) = 0$.

Đáp số: $x = 0$.

4. $\log_{x-1} (x^2 - 5x + 7) = 1$.

Lời giải. Ta tìm miền xác định:

$$x^2 - 5x + 7 > 0, \quad x - 1 > 0,$$

suy ra $x > 1$. Theo định nghĩa của hàm lôgarit, ta có $x^2 - 5x + 7 = x - 1; \quad x_1 = 2, \quad x_2 = 4$.

Vì cả hai giá trị đều thuộc miền xác định, nên chúng là nghiệm của phương trình ban đầu.

5. $\sqrt[3]{2x - 1} + \sqrt[3]{x - 1} = 1$.

Lời giải. Nâng hai vế của phương trình lên lũy thừa ba:

$$3x - 2 + 3\sqrt[3]{(2x - 1)(x - 1)} \times (\sqrt[3]{2x - 1} + \sqrt[3]{x - 1}) = 1.$$

Biểu thức trong ngoặc là vế trái của phương trình ban đầu — có thể thay nó bằng vế phải. Khi đó phương trình có dạng

$$(2x - 1) (x - 1) = (1 - x)^3.$$

Đáp số: $x_1 = 0, \quad x_2 = 1$.

6. Phương trình

$$\sqrt{x + a\sqrt{x + b}} + \sqrt{x} = c$$

có thể có vô số nghiệm không?

Lời giải. Chuyển $\sqrt{x}$ sang vế phải và nâng hai vế lên bình phương:

$$x + a\sqrt{x + b} = c^2 - 2c\sqrt{x} + x.$$

Sau khi thu gọn các hạng tử đồng dạng, ta được: $(a + 2c)\sqrt{x} = c^2 - b$. Khi $a + 2c = 0$ và $c^2 - b = 0$ (và chỉ trong trường hợp này), phương trình trở thành đồng nhất thức, đúng với mọi $x$ không âm.

Đáp số: phương trình có vô số nghiệm khi $a = -2c$ và $b = c^2$. Các nghiệm trong trường hợp này là $x \ge 0$.

7. $$\cos \frac{x}{2} \sqrt{x^2 + (7-\pi)x - 7\pi} = 1.$$

Lời giải. Nếu khi nâng lên lũy thừa một số dương-
