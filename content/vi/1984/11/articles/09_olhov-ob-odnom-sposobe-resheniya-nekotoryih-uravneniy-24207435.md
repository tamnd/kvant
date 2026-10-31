---
id: 1984-11-olhov-ob-odnom-sposobe-resheniya-nekotoryih-uravneniy-24207435
issue: kvant_1984_11
year: 1984
number: "11"
title: Về một chiều lời giải của một số phương trình
authors:
  - Ольхов В. Е.
rubric: shkola-v-kvante
page_first: 31
page_last: 31
page_labels: "29"
tag: 95KQ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: edac3c0fb5e22e13c09935ec8daa238234f54cabe2e82b891aba303d42acb215
prompt_sha256: draft-1
translated_from: content/ru/1984/11/articles/09_olhov-ob-odnom-sposobe-resheniya-nekotoryih-uravneniy-24207435.md
source_content_sha256: fc3509050bcc0af204455730cdcdfe797772fc0ec771e761664411e711727de2
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 29⟧

Toán 8,9,10

Ghi chú được xuất bản bên dưới “Về một phương pháp lời giải của một số phương trình” trình bày khả năng suy luận ở từng mức độ có điều kiện, vì mỗi ghi chú này có thể hữu ích không chỉ cho học sinh của các lớp được chỉ định.

Về một chiều lời giải của một số phương trình

Hãy xem xét những điều sau bài toán:
1. Giải phương trình
$$ (2x-1)\sqrt{x-2}=7\sqrt{2}. $$
(1)

Bình phương truyền thống của cả hai bên dẫn đến một phương trình bậc ba
$$ 4x^3-12x^2+9x-100=0, $$
và nhiều nỗ lực mang tính quyết định để tìm ra cách khác của phương trình bài toán.

Có lẽ nhiều người đồng ý rằng chúng ta có thể cố gắng tìm ra một trong những nghiệm của phương trình bằng cách đánh đồng các thừa số tương ứng:
$$ \begin{cases} 2x-1=7, \\ \sqrt{x-2}=\sqrt{2}, \end{cases} $$
từ đâu $x=4$.

Thật không may, họ dừng lại ở đó và viết ra đáp số. Kết quả là, lời giải có sai số nghiêm trọng, mặc dù đáp số đúng: chúng tôi “đoán” nghiệm (đơn) của phương trình nhưng không chứng minh được rằng không còn nghiệm nào nữa.

Trong trường hợp này, thật dễ dàng để chứng minh rằng phương trình (1) không có nghiệm nào khác, vì với $x>4$ chúng ta có $2x-1>7$, $\sqrt{x-2}>\sqrt{2}$ và vế trái lớn hơn vế phải, và với $x<4$ (từ miền định nghĩa của phương trình) $2x-1<7$, $\sqrt{x-2}<\sqrt{2}$, do đó vế trái nhỏ hơn vế phải.

Hãy để chúng tôi nhấn mạnh một lần nữa rằng lời giải bao gồm hai phần:
1) chúng tôi “đoán” nghiệm (hoặc nghiệm) của phương trình;
2) Ta chứng minh rằng phương trình không còn nghiệm nữa.

Lưu ý rằng phương pháp phương trình nghiệm được sử dụng cho lời giải (1) cũng phù hợp trong trường hợp thay vì lấy tích thì người ta đưa tổng vào phương trình. Ví dụ: trong bài toán này:
2. Giải phương trình:
$$ 2x+\sqrt{x-2}=8+\sqrt{2}. $$

Số lượng các yếu tố (thuật ngữ) trong những bài toán như vậy có thể rất lớn; trong trường hợp này, một số hệ số phải được đặt bằng 1, chẳng hạn như trong bài toán sau:
3. Giải phương trình:
$$ (2y-1)\sqrt{y-2}\sqrt{y-3}=7\sqrt{2}. $$
Lưu ý rằng các phương pháp đoán gốc có thể khác nhau. Ví dụ: hãy xem xét bài toán sau:
4. Giải phương trình:
$$ 2a+\sqrt{a-2}+\sqrt{a-3}=9+\sqrt{2}. $$
(2)

Điều tự nhiên là giả sử rằng $\sqrt{a-2}=\sqrt{2}$, do đó $a=4$. Sau đó, thật dễ dàng để kiểm tra xem $a=4$
$$ 2a+\sqrt{a-3}=2\cdot4+\sqrt{1}=9. $$

Bây giờ chúng ta hãy chứng minh (tương tự như bài toán 1) rằng phương trình (2) không có nghiệm nào khác:
1) Đối với $a>4$ chúng ta có $2a>8$, $\sqrt{a-2}>\sqrt{2}$, $\sqrt{a-3}>1$, vì vậy bên trái lớn hơn bên phải;
2) tại $a<4$ (từ miền định nghĩa của phương trình), vế trái nhỏ hơn vế phải.

V. E. Olkhov

Ba lời giải một bài toán

Thường thì chúng ta không kết thúc lý luận của mình và bỏ rơi những ý tưởng nảy sinh trong đầu. Trong bài toán này, bằng cách sử dụng ví dụ về một bài toán, nó cho thấy các ý tưởng khác nhau, khác xa nhau trong giai đoạn đầu, có thể dẫn đến mục tiêu như thế nào nếu bạn thể hiện tính thực tế ở các giai đoạn thấp hơn của lời giải.

Vấn đề. Vẽ một tam giác vuông bằng cách sử dụng cạnh huyền và đường phân giác của góc vuông.

Vấn đề có vẻ tương đối đơn giản, nhưng không thể giải quyết nó một cách “nhanh chóng”.

Như bạn đã biết, lời giải bài toán đối với xây dựng bao gồm 4 điểm: 1) phân tích,
