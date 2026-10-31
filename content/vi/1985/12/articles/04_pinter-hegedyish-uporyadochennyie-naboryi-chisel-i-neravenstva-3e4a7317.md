---
id: 1985-12-pinter-hegedyish-uporyadochennyie-naboryi-chisel-i-neravenstva-3e4a7317
issue: kvant_1985_12
year: 1985
number: "12"
title: Tập hợp số thứ tự và bất đẳng thức
authors:
  - Пинтер Л.
  - Хегедыш Й.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 16
page_last: 17
page_labels: 14-15
tag: MCIF
lang: vi
source: kvant_digital
extraction: vision
content_sha256: cdd76f12cc95f916866be9598a5d7ce3954477d4c3527dd36d56a9c3f9c96a49
prompt_sha256: draft-1
translated_from: content/ru/1985/12/articles/04_pinter-hegedyish-uporyadochennyie-naboryi-chisel-i-neravenstva-3e4a7317.md
source_content_sha256: 8cd9e2e40a3bb466668d4baddc43f09e3485c43ac2595a20f5d86179497baede
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 14⟧

Tập hợp số thứ tự và bất đẳng thức

L. PINTER, I. HEGEDISH

Cha mẹ Kolya đựng tiền giấy trong phong bì. Một ngày nọ, họ lấy ra ba chiếc phong bì và đặt chúng trước mặt anh. Một trong những phong bì chứa đồng rúp, một phong bì khác chứa ba rúp, và phong bì thứ ba chứa năm rúp. Cha mẹ yêu cầu Kolya rút hai mảnh giấy từ một trong các phong bì, ba mảnh từ phong bì khác và bốn mảnh giấy từ phong bì còn lại.

Kolya nên chọn phong bì như thế nào để nhận được số tiền nhiều nhất có thể và làm thế nào để nhận được số tiền nhiều nhất có thể? Để tìm số tiền tích lũy khi chọn phong bì đạo hàm, bạn cần xếp các số 2, 3, 4 theo thứ tự thích hợp ở bảng 1 ở dòng dưới cùng kèm theo dấu chấm hỏi, sau đó lấy tích các số ở cột rồi cộng lại.

Bảng 1

1? 3? 5?

Bảng 1

Nếu Kolya muốn thu số tiền cao nhất có thể, thì anh ta phải lấy ra bốn mảnh giấy từ phong bì có số năm, ba mảnh giấy từ phong bì có số ba và hai mảnh giấy từ phong bì có số rúp:

$$5 \cdot 4 + 3 \cdot 3 + 1 \cdot 2 = 31.$$

Nếu Kolya muốn thu thập số tiền nhiều nhất có thể, thì anh ta phải lấy ra số mảnh giấy nhiều nhất có thể, tức là hai mảnh từ một phong bì có số năm, ba mảnh từ phong bì có ba rúp và bốn mảnh từ một phong bì có rúp, tức là

$$5 \cdot 2 + 3 \cdot 3 + 1 \cdot 4 = 23.$$

Đặt hàng ba lần

Nói chung, bài toán này có thể được hình thành như sau. Giả sử bộ ba số dương đã cho

$$a_1, a_2, a_3,$$

$$b_1, b_2, b_3.$$

Hãy xem xét số tiền

$$S = a_1 b_i + a_2 b_j + a_3 b_k,$$

trong đó $i, j, k$ là các số 1, 2, 3, được viết theo thứ tự nào. Làm cách nào để chọn thứ tự này sao cho tổng $S$ là lớn nhất có thể (tương ứng là lớn nhất) trong số các số có thể?

Rõ ràng là nếu nhân hầu hết các số $a$ với hầu hết các số $b$, trung bình của các số $a$ với trung bình của các số $b$ và cuối cùng là tên của các số $a$ tên của các số $b$ và cộng các tích này, thì sẽ thu được giá trị lớn nhất có thể $S$ (nếu là trung bình của các số $a$ hoặc trung bình cộng của các số $b$ bằng nhau thì giá trị lớn nhất này $S$ không đạt được bằng cách duy nhất). Nếu nhân hầu hết các số $a$ với hầu hết các số $b$, lấy trung bình cộng với trung bình cộng, v.v., thì chúng ta sẽ nhận được giá trị lớn nhất có thể có $S$.

Sử dụng phương pháp này, bạn có thể giải bài toán M762 một cách đơn giản (xem «Kvant», 1982, số 9)*.

Chứng minh rằng với mọi số dương $a, b, c$ các bất đẳng thức sau đều đúng:

$$a + b + c \leq \frac{a^2 + b^2}{2c} +$$

$$+ \frac{b^2 + c^2}{2a} + \frac{c^2 + a^2}{2b} \leq \frac{a^3}{bc} + \frac{b^3}{ca} + \frac{c^3}{ab}. \quad (1)$$

Trước hết ta chứng minh bất đẳng thức thứ nhất. Hãy viết hai bộ ba số

$$a^2, b^2, c^2,$$

$$\frac{1}{a}, \frac{1}{b}, \frac{1}{c}.$$

Vì các số $a, b, c$ là dương nên hầu hết các số của bộ ba thứ nhất nằm phía trên hầu hết các số của bộ ba thứ hai, hầu hết các số của bộ ba thứ nhất nằm phía trên hầu hết các số của bộ ba thứ hai.

⟦folio 15⟧

thứ ba thứ hai. Do đó, đối với những bộ ba này, tổng

$$a^2 \cdot \frac{1}{a} + b^2 \cdot \frac{1}{b} + c^2 \cdot \frac{1}{c}$$

là tối thiểu, và do đó

$$a^2 \frac{1}{a} + b^2 \frac{1}{b} + c^2 \frac{1}{c} \leq a^2 \frac{1}{b} + b^2 \frac{1}{c} + c^2 \frac{1}{a},$$

(2)

$$a^2 \frac{1}{a} + b^2 \frac{1}{b} + c^2 \frac{1}{c} \leq a^2 \frac{1}{c} + b^2 \frac{1}{a} + c^2 \frac{1}{b}.$$

(3)

Cộng các bất đẳng thức (2) và (3), ta thu được:

$$2(a+b+c) \leq a^2 \frac{1}{b} + b^2 \frac{1}{c} + c^2 \frac{1}{a} + a^2 \frac{1}{c} + b^2 \frac{1}{a} + c^2 \frac{1}{b} = \frac{a^2+b^2}{c} + \frac{b^2+c^2}{a} + \frac{c^2+a^2}{b}.$$

Để thu được bất đẳng thức thứ hai (1), hãy xem xét bộ ba số

$$a^3, b^3, c^3,$$

$$\frac{a}{abc}, \frac{b}{abc}, \frac{c}{abc}.$$

Dưới số lớn nhất (tương ứng nhiều nhất) của ba số đầu tiên được viết số lớn nhất (nhỏ nhất) của ba số thứ hai. Đó là lý do tại sao

$$a^3 \frac{a}{abc} + b^3 \frac{b}{abc} + c^3 \frac{c}{abc} \geq a^3 \frac{b}{abc} + b^3 \frac{c}{abc} + c^3 \frac{a}{abc} + b^3 \frac{c}{abc} + c^3 \frac{a}{abc} + c^3 \frac{b}{abc} = \frac{a^2}{c} + \frac{b^2}{a} + \frac{c^2}{b},$$

(4)

$$a^3 \frac{a}{abc} + b^3 \frac{b}{abc} + c^3 \frac{c}{abc} \geq a^3 \frac{c}{abc} + b^3 \frac{a}{abc} + c^3 \frac{b}{abc} + c^3 \frac{a}{abc} + c^3 \frac{b}{abc} = \frac{a^2}{c} + \frac{b^2}{a} + \frac{c^2}{b},$$

(5)

Cộng các bất đẳng thức (4) và (5), ta thu được

$$2\left(\frac{a^3}{bc} + \frac{b^3}{ca} + \frac{c^3}{ab}\right) \geq \frac{a^2}{c} + \frac{b^2}{a} + \frac{c^2}{b} + \frac{b^2}{c} + \frac{c^2}{a},$$

$$+ \frac{c^2}{a} = \frac{a^2+b^2}{c} + \frac{b^2+c^2}{a} + \frac{c^2+a^2}{b},$$

đó là những gì được yêu cầu.

Bài tập
Chứng minh các bất đẳng thức:
1. $a^4 + b^4 \geq a^3 b + ab^3$.
2. $a^3 b + b^3 c + c^3 a \geq a^2 bc + b^2 ca + c^2 ab$.
3. $\frac{a^3 b}{c} + \frac{a^3 c}{b} + \frac{b^3 a}{c} + \frac{c^3 b}{a} \geq 6abc$ (ở đây $a > 0, b > 0, c > 0$).
4. Nếu $a_1 \geq a_2 \geq a_3 \geq a_4, b_1 \geq b_2 \geq b_3$ thì $3(a_1 b_1 + a_2 b_2 + a_3 b_3) \geq (a_1 + a_2 + a_3)(b_1 + b_2 + b_3)$.
5. Nếu $a > 0, b > 0, c > 0$ thì

$$\frac{a}{b+c} + \frac{b}{a+c} + \frac{c}{a+b} \geq \frac{3}{2}.$$

Một số khái quát

Bây giờ hãy cho một bộ số $n$

$$a_1 \geq a_2 \geq a_3 \geq ... \geq a_n,$$

$$b_1 \geq b_2 \geq b_3 \geq ... \geq b_n.$$

Chúng ta hãy xem xét tất cả các tổng có thể có dạng $i$ $\sigma = a_1 b_1 + a_2 b_2 + ... + a_n b_n$, trong đó $i_1, i_2, ..., i_n$ là một số hoán vị của các số 1, 2, ..., $n$.

Số lượng các tổng như vậy là hữu hạn, và do đó trong số chúng có nhiều nhất $S$ và nhiều nhất $s$. Không khó để báo cáo rằng $S = a_1 b_1 + a_2 b_2 + ... + a_n b_n$ và $s = a_1 b_n + a_2 b_n - 1 + ... + a_n b_1$.

Hãy chứng minh điều đó. Trước tiên chúng ta hãy lưu ý rằng với bốn số $a, b, c, d$ bất kỳ sao cho $a \geq b$ và $c \geq d$, bất đẳng thức đúng

$$ac + bd \geq ad + bc,$$

(*) bằng với bất đẳng thức hiển nhiên

$$(a - b)(c - d) \geq 0.$$

Sau đó, việc thay thế tuyên bố của chúng tôi được chứng minh mà không gặp khó khăn gì. Trên thực tế, nếu trong một tổng nào đó $\sigma$ có các $a_e b_q$ và $a_k b_p$ sau đây, trong đó $e < k, q > p$, tức là $b_p \geq b_q$, thì bằng cách sắp xếp lại các số $b_p$ và $b_q$, chúng ta thu được tổng không nhỏ hơn $\sigma'$ với $a_e b_p$ và sau đây $a_k b_q$.

Liên tục thực hiện các hoán vị như vậy, chúng ta đạt được tổng $S$, do đó $S \geq \sigma$.

Tương tự, nếu $b_q \geq b_p$, thì khi hoán đổi các số này, chúng ta thu được tổng không lớn hơn $\sigma$.

Vì nhờ một số hoán vị, chúng ta có thể đạt được tổng $s$, sau đó là $\sigma \geq s$.

Vì vậy, với bất kỳ số tiền nào $\sigma$

$$s \leq \sigma \leq S,$$

(B)

Hơn nữa, đẳng thức (B) chỉ có thể xảy ra khi một trong các bộ $a_1, ..., a_n, \text{ либо } b_1, ..., b_n$ chứa các số bằng nhau.

Tóm lại, chúng ta có thể xây dựng một phương pháp chung để chứng minh bất đẳng thức: nếu các tập hợp số $a_1, a_2, ..., a_n$ và $b_1, b_2, ..., b_n$ có thứ tự bằng nhau (nghĩa là từ $a_k \geq a_l$ kéo theo $b_k \geq b_l$), thì $a_1 b_1 + a_2 b_2 + ... + ... + a_n b_n \geq a_1 b_1 + a_2 b_2 + ... + ... + a_n b_n$, (ở đây $i_1, i_2, ..., i_n$ là một hoán vị tùy ý của các số 1, 2, ..., $n$).
