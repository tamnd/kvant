---
id: 1983-5-shevelev-razlozhenie-na-razlichnyie-mnozhiteli-81e2793c
issue: kvant_1983_5
year: 1983
number: "5"
title: Phân tích thành các yếu tố khác nhau
authors:
  - Шевелёв В. С.
rubric: smes
page_first: 39
page_last: 39
page_labels: "37"
tag: 94JA
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 2eafae2386adcdad2ca2ce818696a5a23a78026d332a5473963d95102a6eaa00
prompt_sha256: draft-1
translated_from: content/ru/1983/05/articles/12_shevelev-razlozhenie-na-razlichnyie-mnozhiteli-81e2793c.md
source_content_sha256: 420f87fadba93a0cf5a5b5b4e08c185dee72fd9ba182b91554d22fa81aaf4eb0
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 37⟧

Phân tích thành các yếu tố khác nhau

Nói chung, khi phân tích một số tự nhiên thành thừa số nguyên tố, các tổ hợp được lặp lại: $4 = 2^2$, $12 = 2^2 \cdot 3$, v.v.

Chúng ta hãy biểu thị bằng $B$ tập hợp các số tự nhiên sao cho mọi số tự nhiên $n > 1$ không có trong $B$ đều có thể được biểu diễn duy nhất! — biểu diễn nó dưới dạng tích của các số khác nhau từ $B$.

1. Xây dựng một bộ như vậy $B$; chứng minh rằng nó được xác định duy nhất. a) Dạng phân tích thành thừa số nguyên tố của các số từ $B$ là gì? Chúng ta hãy biểu thị bằng $b_n$ phần tử lớn thứ $n$ của tập hợp $B$. Dễ dàng nhận thấy rằng $b_1 = 2$, $b_2 = 3$, $b_3 = 4$, $b_4 = 5$, $b_5 = 7$, $b_6 = 9$.

2. Chúng ta hãy xem xét cách biểu diễn các số tự nhiên dưới dạng tích các số từ $B$ (đối với các số $b \in B$, chúng ta sẽ xem xét các cách biểu diễn như vậy của đẳng thức $b = b$). Ví dụ: $2 = 2$, $10 = 2 \cdot 5$, $12 = 3 \cdot 4$, $30 = 2 \cdot 3 \cdot 5$, $90 = 2 \cdot 5 \cdot 9$, $120 = 2 \cdot 3 \cdot 4 \cdot 5$. Đối với $b \in B$, chúng tôi biểu thị bằng $v_b(n)$ số lượng số không vượt quá $n$, biểu diễn được đề cập trong đó bao gồm hệ số $b$. Ví dụ: $v_2(2) = v_2(3) = v_2(4) = v_2(5) = 1$, $v_2(6) = v_2(7) = 2$, $v_2(8) = v_2(9) = 3$, $v_2(10) = 4$. Chứng minh rằng với mỗi $b \in B$ a) $\lim_{n \to \infty} \frac{v_b(n)}{n} = \frac{1}{b+1}$; b) có vô số $n$ sao cho $\frac{v_b(n)}{n} = \frac{1}{b+1}$.

3. Chúng ta đặt $m < n$ nếu mọi thừa số từ cách biểu diễn số $m$ nêu trên đều được đưa vào cách biểu diễn số $n$. Ví dụ: $2 < 2$, $2 < 10$, $30 < 120$, nhưng không phải $30 < 90$. Chúng ta cũng hãy đặt $1 < n$ cho tất cả $n$. Có bao nhiêu $m$ sao cho $m < n$, nếu $n$ bị phân tách thành tích của số $k$ của các số từ $B$? Chúng ta gọi một số $n$ là hài hòa nếu nó bằng tổng của tất cả $m < n$ sao cho $m < n$. Ví dụ: số 6 và 90 hài hòa: $6 = 2 \cdot 3 = 1 + 2 + 3$, $90 = 2 \cdot 5 \cdot 9 = 1 + 2 + 5 + 9 + 10 + 18 + 45$. a) Tìm thêm một số số hài hòa (tác giả không biết chúng là hữu hạn hay tập hợp). b) Chứng minh rằng mọi số hài đều là số chẵn. Tìm những con số vừa hài hòa vừa hoàn hảo.

V. S. Shevelev
