---
id: 1970-7-nikolaev-sluchay-s-metodom-matematicheskoy-induktsii-1d822952
issue: kvant_1970_7
year: 1970
number: "7"
title: Trường hợp với phương pháp quy nạp toán học
authors:
  - Николаев Е. Г.
rubric: osnovnye-stati
page_first: 39
page_last: 39
page_labels: "37"
tag: LCG3
lang: vi
source: kvant_digital
extraction: vision
content_sha256: dcf96d373c7b8cf2478613f66f7d631bba2286bf2a1c86c3015336d39a50deec
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1970/07/articles/05_nikolaev-sluchay-s-metodom-matematicheskoy-induktsii-1d822952.md
source_content_sha256: 9e725fd59a4e5a787dc1a883eae219ea517aa4825279ca3be6ef00353b7b9790
translation_model: gpt-5-6-mini
translation_run: m10-1970-vi
---

⟦folio 37⟧

Trường hợp với phương pháp quy nạp toán học

Một lần nọ, thầy giáo giao cho học sinh lớp 10 bài tập về nhà sau:

Chứng minh, bằng cách thử dùng phương pháp quy nạp toán học, rằng với mọi $n$ tự nhiên, bất đẳng thức sau đúng:

$$P_n = \frac{1 \cdot 3 \cdot 5 \dots (2n-1)}{2 \cdot 4 \cdot 6 \dots 2n} < \frac{1}{\sqrt{n+1}}.$$

Kolya V. đã tìm được ở nhà lời giải sau;

a) Với $n = 1$ bất đẳng thức đúng, vì

$$P_1 = \frac{1}{2} < \frac{1}{\sqrt{2}}.$$

6) Ta chỉ ra rằng từ điều kiện $P_n < \frac{1}{\sqrt{n+1}}$ suy ra tính đúng đắn của bất đẳng thức $P_{n+1} < \frac{1}{\sqrt{n+2}}$. Để làm điều này, chỉ cần chỉ ra rằng

$$\frac{P_{n+1}}{P_n} < \frac{\sqrt{n+1}}{\sqrt{n+2}},$$

hoặc

$$\frac{2n+1}{2n+2} < \sqrt{\frac{n+1}{n+2}},$$

hoặc

$$(2n+1)^2(n+2) < 4(n+1)^3.$$

hoặc

$$4n^3 + 12n^2 + 9n + 2 < 4n^3 + 12n^2 + 12n + 4,$$

hoặc

$$0 < 3n + 2,$$

điều này hiển nhiên đúng. Như vậy, bất đẳng thức cần chứng minh được suy ra một cách đúng đắn từ nguyên lý quy nạp toán học.

Tuy nhiên, khi kể lời giải này ở trường, Kolya quên đặt số một ở mẫu số và bắt đầu chứng minh một bất đẳng thức «thô» hơn:

$$P_n < \frac{1}{\sqrt{n}}.$$

Đây là điều cậu ấy thu được:

a) Với $n = 1$ bất đẳng thức đúng, vì

$$P_1 = \frac{1}{2} < \frac{1}{1}.$$

6) Ta chứng minh rằng từ điều kiện $P_n < \frac{1}{\sqrt{n}}$ suy ra $P_{n+1} < \frac{1}{\sqrt{n+1}}$. Để làm điều này, chỉ cần chứng minh rằng

$$\frac{P_{n+1}}{P_n} < \frac{\sqrt{n}}{\sqrt{n+1}},$$

hoặc

$$\frac{2n+1}{2n+2} < \sqrt{\frac{n}{n+1}},$$

hoặc

$$(2n+1)^2(n+2) < 4(n+1)^3n,$$

hoặc

$$4n^3 + 12n^2 + 9n + 2 < 4n^3 + 12n^2 + 12n + 4,$$

hoặc

$$0 < 3n + 2,$$

điều này hiển nhiên đúng. Như vậy, bất đẳng thức cần chứng minh được suy ra một cách chặt chẽ từ nguyên lý quy nạp toán học.

Đối với những người đã hiểu vấn đề này, đề nghị chứng minh hai bất đẳng thức:

1. $P_n < \frac{1}{\sqrt{3,1n}}$.

Điều thú vị là trong bất đẳng thức này hệ số 3,1 không thể thay bằng 3,2. Hệ số lớn nhất mà với nó bất đẳng thức vẫn đúng bằng π (tỉ số giữa độ dài đường tròn và đường kính).

2. $\frac{1}{2^3} + \frac{1}{3^3} + \dots + \frac{1}{n^3} < \frac{1}{4}$.
