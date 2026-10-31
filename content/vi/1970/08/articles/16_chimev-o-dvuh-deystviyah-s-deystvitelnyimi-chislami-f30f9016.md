---
id: 1970-8-chimev-o-dvuh-deystviyah-s-deystvitelnyimi-chislami-f30f9016
issue: kvant_1970_8
year: 1970
number: "8"
title: Về hai phép toán với các số thực
authors:
  - Чимев К.
rubric: raznoe
page_first: 58
page_last: 59
page_labels: 56-57
tag: S6ZL
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 94e5b361fa16ccf87457dd0aec50f1b7794f09babfd3510797dc2486b3e7f94a
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1970/08/articles/16_chimev-o-dvuh-deystviyah-s-deystvitelnyimi-chislami-f30f9016.md
source_content_sha256: f91ff851b3353e3631ea4af12e4b5f94382f92ba3f8c9bffa16f50a8f28dd9d3
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-30
---

⟦folio 56⟧

các đại lượng $a \oplus b$, $(a \oplus b) \oplus c$, $b \oplus c$, $a \oplus (b \oplus c)$. Từ bảng này thấy rằng đẳng thức (1) đúng với mọi số thực $a, b, c$.

Như vậy, ta có thể nói về «tổng» của ba số thực $a \oplus b \oplus c$, xác định nó là $a \oplus (b \oplus c)$ hoặc, cũng vậy, là $(a \oplus b) \oplus c$. Xem xét kỹ hơn bảng 1 này dẫn ta đến kết luận rằng $a \oplus b \oplus c = \max(a, b, c)$.

Tính kết hợp của «phép nhân», tức là các đẳng thức đúng với mọi $a, b, c$ thực

$$(a \otimes b) \otimes c = a \otimes (b \otimes c)$$

hay, cũng vậy, đẳng thức min $(\min(a, b), c) = \min(a, \min(b, c))$ người đọc hãy tự kiểm tra bằng chính cách mà ta đã xác nhận tính kết hợp của «phép cộng».

Bây giờ ta thiết lập tính phân phối của «phép nhân» đối với «phép cộng»:

$$(a \oplus b) \otimes c = (a \otimes c) \oplus (b \otimes c),$$

(2) có thể viết dưới dạng

$$\min(\max(a, b), c) = \max(\min(a, c), \min(b, c))$$.

Để làm điều này, chỉ cần lập bảng 2, từ đó thấy rằng đẳng thức (2) quả thật đúng với ba số thực bất kỳ $a, b, c$.

Như đã biết, đối với các phép toán số học thông thường, tính phân phối của phép cộng đối với phép nhân không đúng: không phải với mọi số thực đều có đẳng thức $(ab) + c = (a + c) \times (b + c)$. Nhưng đối với các phép “cộng” và “nhân” mà chúng ta đã đưa vào, tính phân phối như vậy cũng đúng:

$$(a \otimes b) \oplus c = (a \oplus c) \otimes (b \oplus c).$$

Bạn đọc sẽ tự thấy điều đó khi kiểm tra rằng max $(\min(a, b), c) = \min(\max(a, c), \max(b, c))$ với mọi số thực $a, b, c$.

Điều thú vị là phép “cộng” và “nhân” còn có những tính chất khác không thấy trong số học thông thường của các số thực:

$$a \oplus a = a, a \otimes a = a;$$

$$a \otimes (a \oplus b) = a, a \oplus (a \otimes b) = a.$$

Các hệ thức này trực tiếp suy ra từ định nghĩa của các phép toán $\oplus$ và $\otimes$.

⟦folio 57⟧

Ai cũng biết rằng với mỗi số thực $a$ có thể tương ứng một số đối, tức là số $-a$. Ta quy ước ký hiệu số đối của $a$ bằng biểu tượng $a$. Ví dụ: $\overline{2,5} = -2,5; \overline{-V^2} = \sqrt{2}; \overline{0} = 0$.

Điều đáng chú ý là các phép “cộng” và “nhân” có liên hệ với phép lấy số đối:

$$\overline{a \oplus b} = \overline{a} \otimes \overline{b}; \overline{a \otimes b} = \overline{a} \oplus \overline{b}$$

(6) (trong số học thông thường các công thức này cũng không đúng!).

Hãy tự chứng minh các công thức này.

Cuối cùng, hãy tự giải các bài toán sau:

1. Hãy kiểm tra rằng với $n \geq 2$ số thực tùy ý $a_1, \ldots, a_n$
   $a_1 \oplus \ldots \oplus a_n = \max(a_1, \ldots, a_n), a_1 \otimes \ldots \otimes a_n = \min(a_1, \ldots, a_n)$.

2. Các tương ứng sau có đúng không
   $c \otimes (a \oplus b) = (c \otimes a) \oplus (c \otimes b), c \oplus (a \otimes b) = (c \oplus a) \otimes (c \oplus b)?$

3. Chứng minh rằng với mọi số thực $a, b, c$ đẳng thức sau đúng
   $\min [\min(a, c), \min(\max(a, b), c)] = \min(a, c)$ và viết nó bằng các phép toán $\oplus$ và $\otimes$. Sau đó làm thế nào để có thể lập tức kiểm tra tính đúng đắn của nó?

4. Cho $a, b, c$ là các số thực tùy ý. Hãy tìm một biểu thức đơn giản cho đại lượng
   $\min[a, -\max(\min(a, b), \max(a, c))]$.

5. Với mọi số thực $a, b, c$ có đúng đẳng thức
   $(a \oplus b) \otimes (a \oplus b \oplus c) = a \otimes [c \otimes (c \oplus b)]?$

6. Có thể tìm được một số thực $x$ sao cho
   $\max [\min(a, \max(a, b), x)] = b$?

Dưới đây là một số bài toán lấy từ mục thi đấu đã được xây dựng của tạp chí «Matematika».

1. Ở một vương quốc nào đó, trong một quốc gia nào đó có vài thành phố, và mọi khoảng cách giữa từng cặp thành phố đều khác nhau. Vào một buổi sáng đẹp trời, từ mỗi thành phố có một máy bay bay đến thành phố láng giềng gần nhất.

Có thể có hơn năm máy bay hạ cánh ở một thành phố không?

2. Chứng minh rằng nếu $a, b, c$ là độ dài các cạnh của một tam giác, còn $l_a, l_b, l_c$ là độ dài các đường phân giác trong ứng với chúng, thì
   $$\frac{l_a}{a} + \frac{l_b}{b} + \frac{l_c}{c} \leq \frac{p^2}{2S}$$

trong đó $p$ là nửa chu vi, còn $S$ là diện tích tam giác; dấu bằng chỉ đạt được đối với tam giác đều.

A. Mateev

3. Chứng minh rằng nếu số thực $a$ là nghiệm của phương trình
   $2(x^2 + x)\sin 2x + (2x + 2 - x^3)\cos 2x = x^3 + 2x + 2$,
thì số đó thỏa mãn bất đẳng thức $|a| < 1$.

B. Petkov

4. Giả sử trong mặt phẳng của một đa giác lồi có một điểm với tính chất rằng bất kỳ đường thẳng nào đi qua điểm này đều chia đa giác thành hai phần có diện tích bằng nhau. Chứng minh rằng khi đó đa giác này đối xứng tâm.

P. Grozdanov

5. Một con ruồi, không dừng lại, bò theo một hướng với vận tốc không đổi trên đường tròn của đáy trên của một hộp thiếc hình trụ, có chiều cao gấp 4 lần đường kính $2r$ của đáy. Vào một thời điểm nào đó, từ điểm trên bề mặt hộp xa con ruồi nhất, một con nhện bắt đầu đuổi theo con ruồi, nó bò trên bề mặt hộp với vận tốc không đổi bằng vận tốc của con ruồi (và cũng không dừng lại). Tìm độ dài đường đi ngắn nhất mà con nhện có thể đuổi kịp con ruồi.

I. Dimovski
