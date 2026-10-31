---
id: 1973-4-lebedev-nekotoryie-zadachi-na-progressii-0d66a0a4
issue: kvant_1973_4
year: 1973
number: "4"
title: Một số bài toán đang tiến triển
authors:
  - Лебедев В. П.
rubric: raznoe
rubric_sub: Разное
page_first: 59
page_last: 60
page_labels: 57-58
tag: WG3W
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 9f5a8f02be2cce45ef50721bb7f8303602f4eb17703b27b9e6917e1b8a4d9583
prompt_sha256: draft-1
translated_from: content/ru/1973/04/articles/16_lebedev-nekotoryie-zadachi-na-progressii-0d66a0a4.md
source_content_sha256: 23cb089e1aaf4fd524767aabb3853601cdcb493c21bd2ccf8c7f7a417530112d
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 57⟧

Một số bài toán đang tiến triển

V. P. Lebedev

Bài viết này trình bày các định lý và phân tích đặc trưng của bài toán các tiến trình được đưa ra trong các kỳ thi tuyển sinh đại học.

Hai đặc tính chính của sự tiến triển

I. Trong một cấp số cộng, mỗi số hạng của nó (trừ số hạng đầu tiên và số hạng cuối cùng) nhân với 2 sẽ bằng tổng của một dãy hằng số, nghĩa là
$$2a_k = a_{k-1} + a_{k+1}.$$
Câu lệnh ngược lại cũng đúng: nếu trong một dãy số, mỗi phần tử (trừ phần tử đầu tiên và cuối cùng), nhân với 2, bằng tổng của một chuỗi các hằng số thì chuỗi này là một cấp số cộng.

Bằng chứng. Theo định nghĩa cấp số cộng $a_k = a_{k-1} + d$ và $a_k = a_{k+1} - d$, cộng các biểu thức này ta được $2a_k = a_{k-1} + a_{k+1}$. Ngược lại, đặt $2a_k = a_{k-1} + a_{k+1}$, sau đó đặt $a_{k+1} - a_k = a_k - a_{k-1}$.

Thay $k = 2, 3, \dots$ vào đẳng thức cuối cùng và ký hiệu $a_2 - a_1$ bằng $d$, ta thu được
$$d = a_2 - a_1 = a_3 - a_2 = \dots = a_{k+1} - a_k = \dots$$
Theo định nghĩa, điều này có nghĩa là $a_1, a_2, \dots$ là một cấp số cộng.

II. Trong cấp số nhân, bình phương của bất kỳ số hạng nào của nó (trừ số hạng đầu tiên và số hạng cuối cùng) đều bằng tích của các số hạng lân cận nó, nghĩa là
$$b_k^2 = b_{k-1}b_{k+1}.$$

Ngược lại, nếu trong một dãy số, bình phương của mỗi số (trừ số đầu tiên và số cuối cùng) bằng tích của một dãy hằng số thì dãy số này là một cấp số nhân.

Bằng chứng của những tuyên bố này là độc lập.

Nhiệm vụ và lời giải của họ

Bài tập 1. Tìm một cấp số cộng trong đó tổng của n số hạng đầu tiên bằng $n^2$.

Lời giải. Sử dụng công thức tính tổng các số hạng của một cấp số cộng, chúng ta thấy rằng với mọi n đẳng thức
$$S_n = \left[ \frac{2a_1 + d(n-1)}{2} \right]n = n^2.$$
Từ đây
$$d = \frac{2(n-a_1)}{n-1}.$$
Biểu thức này sẽ không chỉ phụ thuộc vào n với $a_1 = 1$. Điều này có nghĩa là trong cấp số độc quyền $a_1 = 1$, $d = 2$ và cấp số nhân có dạng 1, 3, 5, 7,...

Kết quả tương tự có thể thu được bằng cách khác:
$$a_n = S_n - S_{n-1} = n^2 - (n-1)^2 = 2n - 1.$$
Nhiệm vụ 2. Các số 1, $\sqrt{3}$, 3 có phải là một phần của cùng một cấp số cộng không?

Lời giải. Rằng những con số này tạo thành một cấp số cộng, với $1 = a_m$, $\sqrt{3} = a_n$ và $3 = a_p$. Sau đó
$$1 = a_1 + (m-1)d,$$
$$\sqrt{3} = a_1 + (n-1)d,$$
$$3 = a_1 + (p-1)d.$$
Từ đây
$$a_1 = 1 - (m-1)d = \sqrt{3} - (n-1)d = 3 - (p-1)d,$$
$$\sqrt{3} = 1 + (n-m)d,$$
$$3 = 1 + (p-m)d.$$

⟦folio 58⟧

Giải các đẳng thức cuối cùng cho $d$, ta thu được

$$\frac{n - m}{p - m} = \frac{\sqrt{3} - 1}{2},$$

điều này là không thể, vì số ở vế phải là số hữu tỉ và số ở vế phải là số vô tỉ.

Bài toán 3. Trong điều kiện nào các số $a$, $b$ và $c$ là số nguyên của một cấp số cộng?

Lời giải. Đặt $\{a_i\}$ là cấp số ban đầu, với $a = a_m$, $b = a_k$ và $c = a_p$. Sau đó $a = a_1 + d(m - 1)$, $b = a_1 + d(k - 1)$ và $c = a_1 + d(p - 1)$. Chúng ta hãy loại trừ $a_1$ khỏi các đẳng thức sau:

$$a - b = d(m - k)$$
$$b - c = d(k - p).$$

Chia các đẳng thức này cho từng số hạng, ta được

$$\frac{a - b}{b - c} = \frac{m - k}{k - p}.$$

Vì các số $m$, $k$ và $p$ là số nguyên nên $\frac{a - b}{b - c}$ phải là số hữu tỷ.

Dễ dàng kiểm tra xem nếu $\frac{a - b}{b - c} = \frac{s}{t}$, trong đó $s$ và $t$ là số nguyên thì chúng ta có thể tìm thấy một cấp số cộng với các số hạng $a$, $b$, $c$ (bằng chứng!).

Bài toán 4. Chứng minh rằng giữa mỗi hai số hạng liên tiếp của cấp số nhân $c$ dương và số nguyên, chúng ta có thể để lại các số $k$ sao cho toàn bộ dãy tạo thành một cấp số nhân.

Lời giải. Chúng ta hãy biểu thị các số hạng của cấp số cộng bằng $a$, $b$, $c$, ..., $n$, ... Chúng ta xác định mẫu số của cấp số ban đầu $q$ bằng số hạng đầu tiên $a$ và $(k + 2)$th $b$ (phải cung cấp các số hạng $k$):

$$b = aq^{k + 1},$$

từ đâu $q = \sqrt[k + 1]{\frac{b}{a}}$. Trình tự sẽ trông giống như

$$a, a \sqrt[k + 1]{\frac{b}{a}}, a \sqrt[k + 1]{\left(\frac{b}{a}\right)^2}, \dots, b.$$

Giữa các số $b$ và $c$ cũng có các số hạng $k$ để hình thành một cấp số nhân với giá trị $\sqrt[k + 1]{\frac{c}{b}}$, v.v.

Trong điều kiện bài toán

$$\frac{b}{a} = \frac{c}{b},$$

Điều này có nghĩa là toàn bộ chuỗi sẽ tạo thành một cấp số nhân với giá trị $\sqrt[k + 1]{\frac{c}{b}}$, v.v.

Bài toán 5. Tìm mẫu số của một cấp số nhân trong đó mỗi số hạng, bắt đầu từ số hạng thứ hai, bằng hiệu của hai số hạng lân cận (tiếp theo và trước đó).

Lời giải. Đặt tiến trình là $b_1, qb_1, q^2b_1, \dots$.

Từ sự bình đẳng

$$q^{n + 2}b_1 - q^n b_1 = q^{n + 1}b_1$$

chúng tôi tìm thấy

$$q^2 - q - 1 = 0,$$

Ở đâu

$$q = \frac{1 \pm \sqrt{5}}{2}.$$

Bài toán 6. Tìm điều kiện để bình phương của ba số hạng liên tiếp của một cấp số cộng là số hạng trực tiếp liên tiếp của một cấp số nhân.

Lời giải. Giả sử $a, a + d, a + 2d$ là ba số hạng liên tiếp của một cấp số cộng. Nếu bình phương của những số này tạo thành một cấp số nhân thì

$$(a + d)^4 = a^2 (a + 2d)^2,$$

Ở đâu

$$(a + d)^2 = \pm a (a + 2d).$$

Nếu $(a + d)^2 = a (a + 2d)$ thì $d = 0$.

Nếu $(a + d)^2 = -a (a + 2d)$ thì $d = a (-2 \pm \sqrt{2})$.

Vì vậy, $d = 0$ hoặc $d = a (-2 \pm \sqrt{2})$.
