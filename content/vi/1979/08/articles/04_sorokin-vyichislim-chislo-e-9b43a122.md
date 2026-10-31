---
id: 1979-8-sorokin-vyichislim-chislo-e-9b43a122
issue: kvant_1979_8
year: 1979
number: "8"
title: Hãy tính số e
authors:
  - Сорокин Г. А.
rubric: smes
page_first: 10
page_last: 10
page_labels: "8"
tag: T40F
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 4e5d86718c2434a7d86647f634a9037065106f0bb78800f656b94dc2f157f945
prompt_sha256: draft-1
translated_from: content/ru/1979/08/articles/04_sorokin-vyichislim-chislo-e-9b43a122.md
source_content_sha256: 51ae9c7c6f4d207f3f4dc5cc5e3f54f566b39e59adc22e6c3e0914484054aaa7
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 8⟧

HÃY TÍNH SỐ $e$

Chúng ta. 4 người ta đã chứng minh rằng số $e = \lim_{n \to \infty} \left(1 + \frac{1}{n}\right)^n$ bằng tổng của chuỗi $1 + \frac{1}{1!} + \frac{1}{2!} + \dots$. Tuy nhiên, có thể chỉ định một chuỗi có tổng từng phần hội tụ về $e$ nhanh nhất so với tổng từng phần của chuỗi $1 + \frac{1}{1!} + \frac{1}{2!} + \dots$. Dưới đây là một số bài toán, cách giải mà với sự trợ giúp của một số phép tính, bạn sẽ học cách tính chính xác nhiều chữ số của số $e$.

1. Chứng minh rằng với $n \geqslant 2$ đẳng thức sau đúng:

$$1 + 1 + \frac{1}{2!} +$$

$$+ \frac{1}{3!} + \dots + \frac{1}{n!} +$$

$$+ \frac{1}{n \cdot n!} = 3 - \frac{1}{1 \cdot 2 \cdot 2!} -$$

$$-\frac{1}{2 \cdot 3 \cdot 3!} - \dots - \frac{1}{(n-1) \cdot n \cdot n!}$$

Gợi ý. Áp dụng phương pháp quy nạp toán học.

2. Chứng minh rằng

$$e = 3 -$$

$$- \sum_{n=0}^{\infty} \frac{1}{(n+1) \cdot (n+2) \cdot (n+2)!}$$

3. Chứng minh rằng

$$e = \frac{87}{32} -$$

$$- \sum_{n=0}^{\infty} \frac{1}{(n+4) \cdot (n+5) \cdot (n+5)!}$$

4. $e = \frac{87}{32} -$$

$$- \sum_{n=0}^{\infty} \frac{1}{(n+4) \cdot (n+5) \cdot (n+5)!} -$$

$$- R_k$. Đánh giá phần còn lại $R_k$.

5. Tính giá trị gần đúng của $e$, lấy mục tiêu của chuỗi (1) và ước tính độ chính xác của phép tính gần đúng.

6. Chứng minh rằng

$$\sum_{n=0}^{\infty} \frac{1}{(n+4) \cdot (n+5) \cdot (n+5)!} < 0,00047.$$

G. Sorokin
