---
id: 1970-11-savin-maksimum-minimum-i-teorema-o-srednih-b9df3da7
issue: kvant_1970_11
year: 1970
number: "11"
title: Cực đại, cực tiểu và định lý giá trị trung bình
authors:
  - Савин А. П.
rubric: osnovnye-stati
page_first: 26
page_last: 26
page_labels: "24"
tag: B5MV
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 20e404f4dd8866289229be1874360ff45dc1842bc6651b67403d72c42dd0ee17
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1970/11/articles/07_savin-maksimum-minimum-i-teorema-o-srednih-b9df3da7.md
source_content_sha256: a7dd1c1f832a57617c4df11ff17d90f0d60d29e646e4201b6872d2be06ca38b2
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦trang 24⟧

Cực đại, cực tiểu và định lý về trung bình

A. P. Savin

Trong toán học, người ta gọi là định lý những mệnh đề có thể được sử dụng nhiều lần khi suy ra các mệnh đề khác, đặc biệt khi giải bài toán. Tôi muốn kể về việc áp dụng định lý sau:

Trung bình cộng của một số số dương không nhỏ hơn trung bình nhân của chúng, và sự bằng nhau của các trung bình này chỉ xảy ra khi tất cả các số đã cho bằng nhau:

$$\frac{a_1 + a_2 + \dots + a_n}{n} \geq \sqrt[n]{a_1 a_2 \dots a_n}$$

hoặc

$$\left(\frac{a_1 + a_2 + \dots + a_n}{n}\right)^n \geq a_1 a_2 \dots a_n.$$

Có nhiều chứng minh khác nhau cho mệnh đề này, một trong số đó các bạn có thể đọc trong bài của S. T. Berkolayko và S. B. Katok*). Định lý này được áp dụng ở đâu?

Dĩ nhiên, biết nó, bạn có thể dùng trung bình cộng làm trung bình nếu muốn trung bình lớn hơn, và trung bình nhân nếu muốn nó nhỏ hơn. Chẳng hạn, khi tính thành tích trung bình trong lớp. Tất nhiên, đó là chuyện đùa. Còn nếu nói nghiêm túc?

Hóa ra, với sự giúp đỡ của định lý này có thể tìm được các giá trị lớn nhất hoặc nhỏ nhất của các biểu thức đại số. Hãy bắt đầu từ những ví dụ đơn giản nhất.

*) S. T. Berkolayko, S. B. Katok, Về một phương pháp quy nạp chứng minh bất đẳng thức, “Kvant”, số 8, tr. 33.

Ví dụ 1. Đa thức $2x - x^2$ có thể có giá trị lớn nhất nào?

Lời giải. Biến đổi đa thức như sau: $2x - x^2 = x (2 - x)$ và ký hiệu $2 - x$ là $y$.

Theo định lý

$$2x - x^2 = xy \leq \left(\frac{x + y}{2}\right)^2 = \left(\frac{x + 2 - x}{2}\right)^2 = 1.$$

Suy ra giá trị lớn nhất của đa thức bằng 1, và nó đạt được nếu $x = 2 - x$, tức là khi $x = 1$ (không khó kiểm tra rằng $x$ và $2 - x$ không thể đồng thời âm; vì ta tìm giá trị lớn nhất, chỉ cần xét chúng khi cả hai đều dương).

Ví dụ 2. Biểu thức $x + \frac{1}{x}$ có thể có giá trị lớn nhất nào với các giá trị dương của $x$?

Lời giải. Ký hiệu $\frac{1}{x}$ là $y$. Theo định lý

$$x + \frac{1}{x} = 2 \left(\frac{x + y}{2}\right) \geq 2 \sqrt{xy} = 2 \sqrt{\frac{x}{x}} = 2.$$

Vậy giá trị nhỏ nhất bằng 2, đạt được khi $x = \frac{1}{x} = 1^*$.

*) Ở trường học phương pháp hoàn thành bình phương, bằng phương pháp này giải được cả hai ví dụ sau:

1) $2x - x^2 = 1 - (1 - x)^2 \leq 1$;
2) $x + \frac{1}{x} = \left(\sqrt{x} - \frac{1}{\sqrt{x}}\right)^2 + 2 \geq 2$.

Nhưng ví dụ 3 không giải được bằng phương pháp hoàn thành bình phương.
