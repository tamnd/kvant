---
id: 1976-5-shihanovich-formula-dlya-prostyih-chisel-8decfc36
issue: kvant_1976_5
year: 1976
number: "5"
title: Công thức tính số nguyên tố
authors:
  - Шиханович Ю. А.
rubric: smes
page_first: 44
page_last: 44
page_labels: "42"
tag: TQEU
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 218f3952f6d6ca984ffc5205c861187411b838d4512f9250ae6a8019182c32e1
prompt_sha256: draft-1
translated_from: content/ru/1976/05/articles/08_shihanovich-formula-dlya-prostyih-chisel-8decfc36.md
source_content_sha256: 5557cf9ad53fee213edb31bedf31801136e9596d0b32f1d42f3b10fa8f53c79c
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 42⟧

CÔNG THỨC
ĐỐI VỚI SỐ CHÍNH

Chúng ta hãy biểu thị bằng $p_n$ số nguyên tố thứ $(n+1)$ theo thứ tự tăng dần: $p_0 = 2, p_1 = 3, p_2 = 5, p_3 = 7, p_4 = 11, p_5 = 13$, v.v.

Nhiều người tin rằng không có công thức nào biểu thị công thức (1), có thể thấy rằng $a$ được xây dựng là bước sóng dương truyền trong một tờ giấy!

Vì vậy, thí nghiệm đã rõ ràng: từ đầu của một ống dao động, một sóng tròn truyền qua tờ giấy, sóng này bị phản xạ bởi mép tờ giấy mà không đổi pha; sóng tới và sóng phản xạ là chính xác và do đó gây nhiễu; các tinh thể kali mangan được giải phóng khỏi cường độ dao động cực đại (các phản âm của sóng đứng) và được thu thập ở cực tiểu (các nút), sự hoàn hảo của nó đại diện cho một họ hyperbol.

Để kết luận, chúng tôi giao cho bạn một nhiệm vụ không hề bình thường: tìm trong bài viết những phát biểu được đưa ra mà không có bằng chứng và cố gắng chứng minh chúng bằng thực nghiệm.

$$sg(n) = \begin{cases} 1, \text{ если } n > 0, \\ 0, \text{ если } n \leqslant 0, \end{cases}$$

làm thế nào một công thức như vậy có thể được viết (trên cùng bên phải, ở đây $E(x)$ là phần nguyên của số $x$). Một công thức tương tự đã được giáo viên lớp tráng miệng Moscow V. Gugin gửi đến biên tập viên.

Vấn đề là những công thức như vậy ít được sử dụng. Thứ nhất, phép tính sử dụng chúng không ngắn hơn phép tính sử dụng thuật toán sàng Eratovsen («Kvant», 1973, số 4, tr. 72 và 1974, không. 1, tr. 77). Thứ hai, với sự trợ giúp của chúng, thật khó để nghiên cứu “hành vi” của một tập hợp số nguyên tố “ở vô cùng” (tức là tại $n \rightarrow +\infty$ hoặc, như các nhà toán học nói, “hành vi tiệm cận” của một tập hợp các số nguyên tố.

Tuy nhiên, rõ ràng công thức đưa ra sẽ đáp ứng được nhu cầu của một bộ phận nhỏ độc giả «Kvant».

Làm thế nào để chứng minh công thức được đề xuất? Trong lý thuyết số, $\pi(m)$ biểu thị số lượng số nguyên tố không vượt quá $m$. Dễ lắp ráp đó

$$sg(n + 1 - \pi(m)) = \begin{cases} 1, \text{ если } m < p_n, \\ 0, \text{ если } m \geqslant p_n. \end{cases}$$

Bây giờ, giả sử $\mu$ là một “ước tính trên” tùy ý cho $p_n$, tức là một hàm sao cho với tất cả $n$ chúng ta có $p_n \leqslant \mu(n)$.

Sau đó

$$p_n = \sum_{m=0}^{n^2+1} sg(n + 1 - \pi(m)).$$

Giả sử thêm $\chi - \chi_{\text{карактическая функция}}$ có thể biểu diễn được, tức là một hàm sao cho

$$\chi(k) = \begin{cases} 1, \text{ если } k - \text{ простое число}, \\ 0, \text{ если } k - \text{ составное число}. \end{cases}$$

Rõ ràng,

$$\pi(m) = \sum_{k=2}^{m} \chi(k).$$

Sau đó

$$p_n = \sum_{m=0}^{n^2+1} sg(n + 1 - \sum_{k=2}^{m} \chi(k)).$$

Để có được một công thức cụ thể từ công thức (1), cần thay thế các biểu thức của hàm $x$ và $\mu$ vào đó.

Công thức của chúng tôi được lấy chính xác từ công thức (1) cho $\mu(n) = n^2 + 1$ (trong lý thuyết số người ta đã chứng minh rằng $p_n \leqslant n^2 + 1$ cho mọi $n$) và

$$\chi(k) = \frac{[(k - 1)!]^2 - k \cdot E \left( \frac{[(k - 1)!]^2}{k} \right)}{2}.$$

Công thức (2) thu được bằng định lý Wilson: nếu $k - \text{ простое число},$ thì $(k - 1)! + 1$ chia hết cho $k$.
