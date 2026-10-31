---
id: 1982-6-byistryiy-o-sokraschenii-pokazateley-3bb7848f
issue: kvant_1982_6
year: 1982
number: "6"
title: Về việc giảm chỉ số
authors:
  - Быстрый И. М.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 42
page_last: 42
page_labels: "40"
tag: U0X8
lang: vi
source: kvant_digital
extraction: vision
content_sha256: aa6ebd90532360daf68479a404ff7aa27f72d7341e0830b54147aecc98ba2b32
prompt_sha256: draft-1
translated_from: content/ru/1982/06/articles/11_byistryiy-o-sokraschenii-pokazateley-3bb7848f.md
source_content_sha256: 97d0817ea44aadd3d1e3f65dcc81eab0db92e29c280e004bc19d4e30c7e9735b
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 40⟧

Về việc giảm chỉ số

Trong sách giáo khoa hiện tại “Đại số 8” (M., “Prosveshchenie”, ấn bản 1979 trở về sau), căn bậc n của a là một số có bậc thứ n bằng a. (Ở đây n là một số tự nhiên tùy ý, ở phần 1.) Do đó, số dương a với n chẵn có hai nghiệm bậc n là a - dương (ký hiệu là $\sqrt{a}$) và âm (-$\sqrt{a}$). Đối với n lẻ, mọi số a đều có một gốc (ký hiệu là $\sqrt{a}$). Cuối cùng, với mọi số tự nhiên n $\sqrt{0} = 0$.

Việc giảm số mũ cho a không âm không gây khó khăn gì: $\sqrt[n]{a^m} = \sqrt[n]{a^m}$ (mục 26 của sổ tay đã đề cập). Nhưng đối với a tùy ý (đặc biệt khi a là biểu thức chứa một biến), tình huống sẽ tinh tế hơn. Bạn biết rõ rằng $\sqrt{a^2} = |a|$ (ở đây m=n=1, k=2). Trong trường hợp tổng quát,

$$\sqrt[n]{a^m} = \begin{cases} \sqrt[n]{|a|}^m, \text{ если } mk \text{ четно и } m \text{ нечетно} \\ \sqrt[n]{a^m} \text{ во всех остальных случаях} \end{cases}$$

Ví dụ: $\sqrt[4]{a^2} = \sqrt{|a|}$ và $\sqrt[6]{a^2} = \sqrt[3]{|a|}$ (bình đẳng $\sqrt[6]{a^2} = \sqrt[3]{a}$ chỉ đúng với a ≥0, mặc dù cả hai biểu thức $\sqrt[6]{a^2}, \sqrt[3]{a}$ đều được xác định cho bất kỳ a nào!).

Chúng ta hãy chỉ ra cách áp dụng quy tắc rút gọn số mũ bằng ví dụ về hệ phương trình vô tỷ

$$\begin{cases} \sqrt{x+y} + \sqrt[3]{x-y} = 6 \\ \sqrt[6]{(x+y)^3(x-y)^2} = 8 \end{cases}$$

Với mọi x và y, chúng ta thu được hai hệ lời giải (5): (12; 4), (34; -30).

Giải hệ phụ trợ

$$\begin{cases} u+v = 6 \\ u \cdot v = 8 \end{cases}$$

chúng tôi nhận được hai lời giải: $u_1 = 4$, $v_1 = 2$ và $u_2 = 2$, $v_2 = 4$. Hệ thống giải quyết

$$\begin{cases} \sqrt{x+y} = 4 \\ \sqrt[3]{x-y} = 2 \end{cases}$$

lời giải không có (tại sao?),

$$\sqrt[3]{(x+y)^3(x-y)^2} = \sqrt[6]{(x+y)^3(x-y)^2}$$

Sửa đổi

Trong bài viết “Số phức” của L. Pontryagin («Kvant», 1982, số 3), do lỗi của người biên tập, lỗi chính tả đã được đưa vào chứng minh công thức (11), gây khó hiểu. Chúng ta thoải mái trình bày phần chứng minh này (tr. 5-6): “Từ công thức (9) suy ra không cần ưu tiên

$$iz = i \cdot (x+iy) = x \cdot i + y(-1) = xR_d(1) + yR_d(i) = R_d(x \cdot 1 + y \cdot i) = R_d(x+iy) = R_d(z).$$

Như vậy, công thức (11) được chứng minh cho a = $\frac{\pi}{2}$.

Giả sử a là một số thực tùy ý. Với z = cos a + i sin a ta có

$$z \cdot i = i \hat{z} = R_d(\hat{z}) = R_d(\cos a + i \sin a) = \cos(a + \frac{\pi}{2}) + i \sin(a + \frac{\pi}{2}) = R_a(\cos \frac{\pi}{2} + i \sin \frac{\pi}{2}) = R_a(i).$$

Như vậy, công thức (11) đã được chứng minh cho z = i. Ngoài ra, trong bài viết của cùng tác giả “Định lý cơ bản của đại số” («Kvant», 1982, số 4), do lỗi của nhà in tr. 9 được in $f(z) = f(\bar{z})$ cùng nhau một cách chính xác $f(z) = f(\bar{z})$.
