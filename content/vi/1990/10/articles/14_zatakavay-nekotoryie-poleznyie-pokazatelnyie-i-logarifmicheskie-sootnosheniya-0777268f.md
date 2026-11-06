---
id: 1990-10-zatakavay-nekotoryie-poleznyie-pokazatelnyie-i-logarifmicheskie-sootnosheniya-0777268f
issue: kvant_1990_10
year: 1990
number: "10"
title: Một số mối quan hệ hàm mũ và logarit hữu ích
authors:
  - Затакавай В. В.
rubric: shkola-v-kvante
page_first: 44
page_last: 45
page_labels: 42-43
lang: vi
source: kvant_digital
extraction: vision
content_sha256: deac17f5f7d8ff73951e6c71d4c404b997f3d25cfdf068195e4d6da3a0416024
prompt_sha256: draft-1
translated_from: content/ru/1990/10/articles/14_zatakavay-nekotoryie-poleznyie-pokazatelnyie-i-logarifmicheskie-sootnosheniya-0777268f.md
source_content_sha256: 70fff0bf14e0b8a754f79cd2aea384b33b5b90411433e35bf3e078b624b10722
translation_model: draft
translation_run: vi-draft-gaps-2026-11-05
translation_quality: draft
---

⟦folio 42⟧

---
running_head:
folio:
---

$x^{\log_2 5} = (5^{\log_5 x})^{\log_2 5} = (5^{\frac{\log_2 x}{\log_2 5}})^{\log_2 5} = 5^{\log_2 x}$, và phương trình có dạng
$5^{\log_2 x} + 2 \cdot 5^{\log_2 x} = 15$.

Từ đây
$5^{\log_2 x} = 5, \log_2 x = 1, x = 2$.

Đáp số: 2.

Bằng cách giải phương trình này, chúng tôi thực sự đã rút ra được công thức
$a^{\log_2 b} = b^{\log_2 a}$. (1)

Dễ dàng kiểm chứng tính đúng đắn của công thức (1) ở dạng tổng quát. Chúng ta hãy tam giác cạnh phải và trái của (1) với đáy $c$. Chúng tôi nhận được $\log_c (a^{\log_2 b}) = \log_c (b^{\log_2 a})$ hoặc $\log_c b \times \log_c a = \log_c a \cdot \log_c b$.

Rõ ràng, điều này cũng đúng với tất cả các giá trị được chấp nhận là $a, b, c$.

Đây là một công thức hữu ích khác được ghi lại trong các trang sách giáo khoa:
$a^{\sqrt{\log_a b}} = b^{\sqrt{\log_b a}}$. (2)

Chứng minh của công thức này tương tự như chứng minh của công thức trước: bạn cần đa giác hóa cả hai vế của công thức (2) về cơ số $a$:
$\log_a (a^{\sqrt{\log_a b}}) = \log_a (b^{\sqrt{\log_b a}})$,

hoặc
$\sqrt{\log_a b} = \sqrt{\log_b a} \cdot \log_a b$.

Di chuyển đến căn cứ $a$, ta được $\sqrt{\log_a b} = \sqrt{\log_b a}$.

Ví dụ 2.
$2^{\sqrt{\log_2 x}} + x^{\sqrt{\log_2 x}} = 4$.

Theo công thức (2)
$x^{\sqrt{\log_2 x}} = 2^{\sqrt{\log_2 x}}$, nên phương trình trở thành
$2^{\sqrt{\log_2 x}} + 2^{\sqrt{\log_2 x}} = 4; 2^{\sqrt{\log_2 x}} = 2;$
$\log_2 x = 1; x = 2$.

Đáp số: 2.

Ví dụ 3.
$\log_3 x (42x^2 - 13x + 1) > 0$.

Lời giải sự bất bình đẳng này theo “quan điểm của trường học” là sử dụng nhiều lao động. Cần xét hai trường hợp

⟦folio 43⟧

---
running_head:
folio:
---

trà: khi $3x > 1$ và khi $0 < 3x < 1$.
Cả hai trường hợp đều dẫn tới những hệ thống bất bình đẳng phức tạp.
Chúng tôi khẳng định rằng nếu $\log_a b > 0$ thì $(a-1) \cdot (b-1) > 0$, tức là $(a-1)$ và $(b-1)$ có cùng dấu.
Thật vậy, nếu $\log_a b > 0$ thì $\log_a b > \log_a 1$.
Với $a > 1$ ta có $b > 1$, mệnh đề này đúng.
Với $0 < a < 1$, chúng ta thu được $b < 1$ đó, nếu không thì câu phát biểu lại đúng, vì $(a-1) < 0$ và $(b-1) < 0$.
Tương tự, bạn có thể chứng minh rằng nếu $\log_a b < 0$ thì $(a-1) \cdot (b-1) < 0$ (tự làm).
Hãy áp dụng tuyên bố của chúng tôi cho ví dụ 3. Vì vậy, chúng tôi có:
$$(42x^2 - 13x)(3x - 1) > 0.$$
Bất đẳng thức này được giải dễ dàng bằng phương pháp tích phân. Tất nhiên, trong trường hợp này, cần phải xem xét sự tương ứng giới hạn phạm vi định nghĩa của hàm logarit:
$3x > 0; \quad 3x \neq 1; \quad 42x^2 - 13x + 1 > 0.$
Đáp số: $\left(0; \frac{1}{7}\right) \cup \left(\frac{1}{6}; \frac{13}{42}\right) \cup \left(\frac{1}{3}; +\infty\right)$.
Kỹ thuật được xem xét cho phép chúng ta giải các bất đẳng thức phức tạp hơn. Ví dụ 4.
$\log_{2-x}(x+2) \cdot \log_{x+3}(3-x) \leq 0.$
Áp dụng khẳng định đã được chứng minh, ta có
$(x+1)(1-x)(2-x)(x+2) \leq 0.$
Xét miền định nghĩa của vế trái của bất đẳng thức: $(-2; 1) \cup (1; 2)$, ta thu được
Đáp số: $(-2; -1] \cup (1; 2)$.
Để kết luận, chúng tôi đưa ra một số ví dụ về lời giải độc lập.
1. $5^{\lg x} + x^{\lg 5} = 50.$
2. $25^{\lg x} = 5 + 4 \cdot x^{\lg 5}$.
3. $x^{\log_2 9} = x^2 \cdot 3^{\log_2 x} - x^{\log_2 3}$.
4. $10^{\sqrt{\lg x}} + x^{\sqrt{\log_2 x}} = 0,2.$
5. $3^{-\sqrt{\log_1 x}} + x^{\sqrt{\log_1 x}} = 4,5^{-1}$.
6. $\log_2 x^2(x^2 + x - 1) < 0.$
7. $\log_2 x(5x - 1) \cdot \log_3 x(7x - 1) > 0.$
8. $\log_2 x(10x + 3) \cdot \log_10 x(3x + 10) \geq 0.$
9. $\log_2 x\left(6x + \frac{1}{7}\right) \cdot \log_5 x\left(3x + \frac{4}{7}\right) \leq 0.$

Cuộc thi "Toán 6-8"
Tạp chí «Kvant» cùng với tạp chí thanh thiếu niên Bulgaria “Mathematika” tiếp tục cuộc thi dành cho học sinh lời giải toán bài toán lớp 6-8. Cuộc thi bao gồm 27 bài toán (không có 3 trong mỗi số) và sẽ kết thúc vào tháng 5 năm sau. Những người chiến thắng sẽ được trao giải thưởng từ các tạp chí «Kvant» và Mathematika. Thật không may, trong điều kiện bài toán của số trước (xem trang 48) đã có những điểm không chính xác hiện có. Các biên tập viên mang đoạn trích của họ đến cho độc giả và lặp lại các điều kiện của bài toán này. Gửi Lời giải tất cả bài toán từ số này không muộn hơn ngày 15 tháng 12 năm 1990 đến địa chỉ: 103006, Moscow K-6, st. Gorky, 32/1, «Kvant» (được chấm “Cuộc thi “Toán 6-8”}). Đừng quên ghi họ, tên, trường và lớp của bạn.
