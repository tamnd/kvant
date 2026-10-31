---
id: 1972-12-gershunov-irratsionalnyie-neravenstva-f3721fcf
issue: kvant_1972_12
year: 1972
number: "12"
title: Bất bình đẳng vô lý
authors:
  - Гершунов Е. М.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 51
page_last: 52
page_labels: 49-50
tag: 2ERT
lang: vi
source: kvant_digital
extraction: vision
content_sha256: e54a0f70cea843b5581c368e54375adb8d2643c489c2b6e98c812ae0a7384590
prompt_sha256: draft-1
translated_from: content/ru/1972/12/articles/10_gershunov-irratsionalnyie-neravenstva-f3721fcf.md
source_content_sha256: 5c7afdf3eed208611ead835628c935cc1c612e3d9805aa743d6b91c642c0eab1
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 49⟧

BẤT BÌNH ĐẲNG HẤP DẪN

E. M. Gershunov

Trong các kỳ thi tuyển sinh đại học, các ví dụ hoặc bài toán ngày càng được đưa ra nhiều hơn, yếu tố chính hoặc cấu thành của nó là một bất đẳng thức chứa một đại lượng chưa biết dưới dấu căn (bất đẳng thức vô tỉ). Thực tiễn cho thấy rằng đối với hầu hết người nộp đơn, lời giải sự bất bình đẳng bất hợp lý gây ra khó khăn. Lý do cho điều này rõ ràng là vì chương trình giảng dạy ở trường và sách giáo khoa toán không có chủ đề này.

Bài viết này không trình bày đầy đủ tất cả các vấn đề liên quan đến lời giải sự bất bình đẳng phi lý. Trọng tâm chính ở đây là về lời giải các bất đẳng thức vô tỷ liên quan đến căn thức bậc hai.

Trước tiên chúng ta hãy chứng minh định lý sau, định lý này đóng vai trò chính cho các bất đẳng thức vô tỉ lời giải.

Định lý. Nếu $f(x) \geq 0$ và $\partial(x) \geq 0$ thì các bất đẳng thức $f(x) \geq g(x)$ và $[f(x)]^2 \geq [g(x)]^2$ là tương đương.

Bằng chứng. Ta cần xác định dấu của sự khác biệt

$$[f(x)]^2 - [g(x)]^2.$$ (1)

Hãy phân tích (1) thành thừa số:

$$[f(x)]^2 - [g(x)]^2 = [f(x) + g(x)][f(x) - g(x)].$$ (2)

Thừa số đầu tiên ở vế phải không âm theo điều kiện. Nếu nó dương thì dấu của hiệu (1) trùng với dấu của thừa số thứ hai trong (2), và nếu $f(x) + g(x) = 0$ thì $f(x) = 0$ và $g(x) = 0$, và một lần nữa các bất đẳng thức là tương đương.

Dễ dàng chứng minh định lý này vẫn đúng nếu mọi dấu của bất đẳng thức không chặt chẽ $\geq$ được thay thế bởi

xâu chuỗi về các dấu bất đẳng thức đúng $>$ (tự chứng minh).

Ví dụ 1. Giải bất đẳng thức

$$\sqrt{4 + 3x - x^2} < 2.$$

Lời giải. Đầu tiên chúng ta xác định OD3: $-1 \leq x \leq 4$. Vế trái của bất đẳng thức không âm và vế phải dương, vì vậy hãy bình phương cả hai vế. Ta thu được hệ bất đẳng thức tương đương

$$\begin{cases} -1 \leq x \leq 4, \\ 3x - x^2 < 0, \\ -1 \leq x \leq 4, \\ x > 3, x < 0. \end{cases}$$

Đáp số: $3 < x \leq 4$, $-1 \leq x < 0$.

Ví dụ 2. Giải bất đẳng thức

$$\sqrt{4 + 3x - x^2} > -2.$$

Lời giải. OD3 giống nhau: $-1 \leq x \leq 4$. Lưu ý rằng trong OD3 vế trái của bất đẳng thức không âm và vế phải âm nên định lý không thể được chứng minh. Nhưng điều này là không cần thiết. Thật vậy, căn thức có một giá trị số học, do đó, bất kỳ giá trị nào của nó trong OD3 đều thỏa mãn bất đẳng thức này. Do đó đáp số là $-1 \leq x \leq 4$.

Ví dụ 3. Giải bất đẳng thức

$$\sqrt{x^2 - 5x + 4} < x - 3.$$

Lời giải. OD3: $x \geq 4$, $x \leq 1$. Vì vế phải chứa đại lượng chưa biết nên ta sẽ xét tuần tự hai trường hợp:

1) $x - 3 > 0$, $2) x - 3 \leq 0$.

Trong trường hợp đầu tiên chúng ta sẽ sử dụng

⟦folio 50⟧

định lý đã được chứng minh và thu được hệ tương đương
$$\begin{cases} x \geq 4, & x \leq 1, \\ x - 3 > 0, \\ x^2 - 5x + 4 < (x - 3)^2, \end{cases}$$

từ đâu $4 \leq x < 5$.

Trong trường hợp thứ hai, bất đẳng thức ban đầu không có lời giải, vì giá trị số học của nghiệm không thể nhỏ hơn một số không dương.

Đáp số: $4 \leq x < 5$.

Ví dụ 4. Giải bất đẳng thức
$$\sqrt{x^2 - 5x - 24} > x - 2.$$

Lời giải. ODZ: $x \geq 8, x \leq -3$. Hãy xem xét hai trường hợp: 1) $x - 2 \geq 0$, 2) $x - 2 < 0$.

Trong trường hợp đầu tiên, vế phải không âm và sử dụng định lý, chúng ta thu được hệ bất đẳng thức
$$\begin{cases} x \geq 8, & x \leq -3, \\ x - 2 \geq 0, \\ x^2 - 5x - 24 > (x - 2)^2, \end{cases}$$

không có lời giải.

Trong trường hợp thứ hai, theo định nghĩa căn bậc chẵn, bất đẳng thức ban đầu được thỏa mãn trên toàn bộ khoảng giá trị chấp nhận được. Giải quyết hệ thống
$$\begin{cases} x - 2 < 0, \\ x \geq 8, x \leq -3, \end{cases}$$

chúng tôi tìm thấy đáp số: $x \leq -3$.

Ví dụ 5. Giải bất đẳng thức
$$\sqrt{x - 2} + \sqrt{x - 1} > \sqrt{x + 3}.$$

Lời giải. ODZ: $x \geq 2$. Vì cả hai vế của bất đẳng thức đều dương nên sử dụng định lý chính nên ta thu được hệ bất đẳng thức tương đương
$$\begin{cases} x \geq 2, \\ 2 \sqrt{(x - 1)(x - 2)} > 6 - x. \end{cases}$$

Ta giải hệ này bằng cách xét hai trường hợp:
$$\begin{cases} x \geq 2, \\ 6 - x \geq 0, \\ 4(x^2 - 3x + 2) > (6 - x)^2, \end{cases}$$

từ đâu $\sqrt{\frac{28}{3}} < x \leq 6$, và
$$\begin{cases} 6 - x < 0 \\ x \geq 2 \end{cases}$$

từ đâu $x > 6$.

Đáp số: $x > \sqrt{\frac{28}{3}}$.

Ví dụ 6. Giải bất đẳng thức
$$\frac{\sqrt{x^2 - x - 2}}{x^2 + 2x + 3} > 0.$$

Lời giải. ODZ được xác định bởi điều kiện tồn tại của căn thức: $x \geq 2, x \leq -1$. Tại $x > 2, x < -1$ tử số của phân số nhận giá trị dương nên chúng ta chuyển sang hệ tương đương
$$\begin{cases} x > 2, x < -1, \\ x^2 + 2x + 3 > 0. \end{cases}$$

Bất đẳng thức thứ hai của hệ được thỏa mãn với bất kỳ giá trị thực nào của $x$, từ đó chúng ta thu được đáp số: $x > 2, x < -1$.

Bài tập

Giải bất đẳng thức:
1. $\frac{x - 7}{\sqrt{4x^2 - 19x + 12}} < 0$.
2. $x < \sqrt{2 - x}$.
3. $x + 1 > \sqrt{x + 2}$.
4. $\sqrt{4 + 3x - x^2} < x - 1$.
5. $\sqrt{2x^2 - 8x + 7} < x - 2$.
6. $\sqrt{\frac{4}{x^2} - \frac{3}{4}} > \frac{2}{x} - 1$.
7. $\sqrt{2x - 6} + \sqrt{x + 4} > 5$.
8. $\sqrt{\frac{x + 1}{2 - x}} < 3$.
9. $\frac{1 - \sqrt{1 - 8x^2}}{2x} < 1$.
10. $\sqrt{x^2 - 3x + 2} > 2 - x$.
11. $\sqrt{\sin x} + \sqrt{\cos x} > 1$.
12. $\frac{2x}{\sqrt{2x + 9}} < \sqrt{2x + 1} - 1$.
13. $(x - 3)\sqrt{x^2 + 4} \leq x^2 - 9$.
14. $\sqrt{x^2 - 16} / |x| - |x - 2| < 0$.
