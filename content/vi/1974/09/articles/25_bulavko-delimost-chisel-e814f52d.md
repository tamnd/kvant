---
id: 1974-9-bulavko-delimost-chisel-e814f52d
issue: kvant_1974_9
year: 1974
number: "9"
title: Tính chia hết của số
authors:
  - Булавко И. Г.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 72
page_last: 75
page_labels: 70, 72, 73
tag: E37E
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 2a9ae8539e3de5cdba036ae40bc63805655bc40345afe556253f94d47609ebc1
prompt_sha256: draft-1
translated_from: content/ru/1974/09/articles/25_bulavko-delimost-chisel-e814f52d.md
source_content_sha256: f8d7f92fd2dc44fa109526f3f912db6cdb34a6910330eaaa4f98a4ba63c6e3ce
translation_model: draft
translation_run: vi-draft-2026-11-03
translation_quality: draft
---

⟦folio 70⟧

I. G. Bulavko
Tính chia hết của số

Tất cả các bạn đều biết rõ số chia hết là gì. Bạn có biết cách giải bài toán để chia hết không? Bài toán những môn này thường được tổ chức tại các kỳ thi Olympic toán và trong các kỳ thi tuyển sinh vào các trường toán. Trong bài viết này, chúng tôi xem xét chi tiết một số khả năng chia hết bài toán; cho mỗi bài toán lời khuyên được đưa ra có thể hữu ích cho lời giải khác bài toán.

Chúng ta hãy nhớ lại những thông tin cơ bản từ lý thuyết chia hết.

Về giới hạn. Đặt $a$ và $b$ là số nguyên và $b \neq 0$. Ta sẽ nói $a$ chia hết cho $b$, viết như sau: $a \mid b$, hoặc người ta nói $b$ chia $a$, viết: $b/a$ (theo đó, nếu $a$ không chia hết cho $b$ (tức là $b$ thì không chia $a$), viết $a \neq b$).

Định lý
1) Nếu $a$ chia hết cho $b$, $b$ chia hết cho $c$, thì $a$ chia hết cho $c$:
   $(a \mid b \text{ и } b \mid c) \Rightarrow (a \mid c)$.
2) Nếu $a$ chia hết cho $m$ thì $m$ và $ab$ chia hết cho $m$ ($b$ là số nguyên bất kỳ):
   $(a \mid m) \Rightarrow (ab \mid m)$.
3) Nếu $a$ chia hết cho $m$ và $b$ chia hết cho $m$ thì $m$ và $a + b$ chia hết cho $m$:
   $(a \mid m \text{ и } b \mid m) \Rightarrow (a + b \mid m)$.

*) Lần đầu tiên chúng ta sẽ sử dụng các chữ cái Latinh $a, b, c, d, \dots$ để biểu thị số nguyên; nếu số đó là số nguyên tố, chúng ta biểu thị số đó bằng chữ cái $p$.

4) Nếu $a + b$ chia hết cho $m$ và $a$ chia hết cho $m$:
   $(a + b \mid m \text{ и } a \mid m) \Rightarrow (b \mid m)$.
5) Nếu $a$ chia hết cho $m$ và $a$ chia hết cho $k$, đồng thời $m$ và $k$ là nguyên tố cùng nhau*), thì $a$ chia hết cho tích $mk$:
   $(a \mid m \text{ и } a \mid k \text{ и } (m, k) = 1) \Rightarrow \Rightarrow (a \mid mk)$.
6) Nếu $ab$ chia hết cho $m$ và $a$ nguyên tố cùng nhau $c$ $m$, thì $b$ chia hết cho $m$:
   $(ab \mid m \text{ и } (a, m) = 1) \Rightarrow (b \mid m)$.

Trong phần tiếp theo chúng ta sẽ sử dụng các định lý này mà không cần tham chiếu đặc biệt đến chúng.

Bài toán 1. Nếu với một số trực tiếp**), chúng ta gán chữ số $6$ ở bên phải và nhân số mới thu được với $4$, chúng ta được số ban đầu có chữ số được gán $6$ ở phía trước. Tìm số tốt nhất.

Khuyên bảo. Trước khi giải bài toán, hãy viết ra (nếu có thể thì tốt hơn) văn bản của nó bằng ngôn ngữ toán học.

Lời giải.

$$\frac{\times \frac{abcde}{4}}{6abcde}.$$

Khi thực hiện phép nhân, hãy tìm tuần tự chữ số của số mong muốn: $e = 4$, $d = 8$, v.v.

Đáp số. 615384.

Bài toán 2. Chúng ta lần lượt viết ra bốn chữ số liên tiếp, sau đó thay thế hai chữ số còn lại

*) Người ta nói rằng số $a$ là số nguyên tố cùng nhau $c$ $b$ nếu ước chung nhất của $a$ và $b$ bằng 1. Ước chung nhất của các số $a_1, a_2, \dots, a_n$ được ký hiệu là $(a_1, a_2, \dots, a_n)$. Khi đó, $a$ nguyên tố cùng nhau với $c$ được viết là $(a, b) = 1$.

**) Số có nhiều giá trị, ví dụ $n + 1$ chữ số, thường được ký hiệu như sau: $a_n a_{n-1} \dots a_0$, trong đó $a_i$ ($i = 0, 1, 2, \dots, n$) là các chữ số của số đó; số cũng có thể được biểu thị bằng các chữ cái $a, b, c, \dots$

⟦folio 72⟧

được lấy từ công thức $a = 5q + r$, nghĩa là cùng với các đẳng thức $a = 5q$, hoặc $a = 5q + 1$, hoặc $a = 5q + 2$, hoặc $a = 5q + 3$, hoặc $a = 5q + 4$, tính đến (2), chúng ta có thể viết rằng $a - \text{либо } 5m$, hoặc $5m \pm 1$ hoặc $5m \pm 2$.

Rõ ràng, dạng ký hiệu này nhỏ gọn hơn. (Trong ví dụ trên, chúng ta đã viết $r = 3$ và $r = 4$ cùng nhau thành $(5 - r)$, tức là $-1$ và $-2$.) Lời giải. Cho $a$ và $b$ là hai số thỏa mãn điều kiện bài toán. Hãy cùng tìm hiểu xem số dư có thể nhận những giá trị nào khi chia các số này và bình phương của chúng cho 24. Hãy biểu thị số $a$ là $a = 24q + r$, trong đó $0 \leq r < 24$. Vì $a$ không phải là bội số của 2 và không phải là bội số của 3 nên $r$ chỉ có thể nhận các giá trị 1, 5, 7, 11, 13, 17, 19, 23. Do đó, $a$ có thể được viết dưới một trong các dạng: $a = 24m_1 \pm 1$, $a = 24m_2 \pm 5$, $a = 24m_3 \pm 7$, $a = 24m_4 \pm 11$. Thật dễ dàng để xác minh rằng trong bất kỳ trường hợp nào, số dư khi chia $a^2$ cho 24 là 1.

Tương tự, chúng ta thu được $b^2 = 24n + 1$ đó. Khi đó $a^2 - b^2 = 24(m - n)$, tức là $a^2 - b^2$ chia hết cho 24. Bài toán lời giải.

Bài tập 3. Chứng minh rằng số $5q + 2$ không phải là bình phương của một số nguyên có giá trị nào $q$.

Bài toán 5. Chứng minh rằng $A = n^5 - 5n^3 - 6n$ chia hết cho 10.

Khuyên bảo. Đối với lời giải bài toán tính chia hết thường được trợ giúp bởi định lý sau: trong $n$ số tự nhiên liên tiếp, một số chia hết cho $n$.

Hãy tự mình chứng minh định lý này. Phát biểu và chứng minh các định lý tương tự cho $n$ số lẻ liên tiếp và $n$ số chẵn liên tiếp (ở đây nó đã tồn tại dù $n$ là chẵn hay lẻ).

Lời giải. $A = n(n^4 - 5n^2 - 6) = n(n^4 - 5n^2 + 4) - 10n = n[(n^4 - n^2) - (4n^2 - 4)] - 10n = n(n^2 - 1)(n^2 - 4) - 10n = (n - 2)(n - 1)n(n + 1) \times (n + 2) - 10n$.

Theo định lý đã đề cập, tích $(n - 2)(n - 1)n(n + 1)(n + 2)$ chia hết cho cả 2 và 5, tức là chia hết cho 10. Tuy nhiên, điều này có nghĩa là toàn bộ hiệu (bằng $A$) cũng chia hết cho 10, đây là điều cần phải chứng minh.

Bài toán 6. Chứng minh rằng số $N = \underbrace{11 \dots 1}_{k \text{ цифр}} \underbrace{12 \dots 2}_{k \text{ цифр}} \underbrace{2 \dots 2}_{k \text{ цифр}}$ là tích của hai số tự nhiên liên tiếp.

Khuyên bảo. Nếu bài toán không phù hợp với lời giải ở dạng tổng quát, hãy xem xét một số trường hợp đặc biệt của nó và sau đó cố gắng chuyển từ chúng sang trường hợp tổng quát.

Lời giải. Lưu ý rằng $12 = 3 \cdot 4$, $1122 = 33 \cdot 34$, $111222 = 333 \cdot 334$.

Điều tự nhiên là giả sử rằng trong trường hợp tổng quát $N = \underbrace{11 \dots 1}_{k \text{ цифр}} \underbrace{12 \dots 2}_{k \text{ цифр}} = \underbrace{33 \dots 3}_{k \text{ цифр}} \underbrace{33 \dots 34}_{k \text{ цифр}}$.

Hãy chứng minh đẳng thức (3). Chúng ta có: $33 \dots 3 \cdot 33 \dots 34 = 3 \cdot 11 \dots 1 \times \times (33 \dots 3 + 1) = 11 \dots 1 \times \times (99 \dots 9 + 3) = 11 \dots 1 \times (10^k + 2) = 11 \dots 122 \dots 2$, đó là điều chúng ta cần chứng minh.

Bài toán 7. Chứng minh rằng $A_n = 2^{n+2} \cdot 3^n + 5n - 4$ chia hết cho 25 với mọi số tự nhiên $n$.

Khuyên bảo. Việc chứng minh những phát biểu như vậy bằng phương pháp quy nạp toán học là hợp lý.

Lời giải. 1) Với $n = 1$ câu khẳng định đúng:

$A_1 = 2^3 \cdot 3 + 5 - 4 = 25$ chia hết cho 25.

⟦folio 73⟧

2) Giả sử rằng mệnh đề đã được chứng minh cho tất cả $n \leq k$; Hãy chứng minh điều đó cũng đúng với $n = k + 1$, tức là ta chứng minh rằng $A_{k+1}$ chia hết cho 25. Ta có:

$$A_{k+1} = 2^{k+3} \cdot 3^{k+1} + 5k + 1 = 2 \cdot 2^{k+2} \cdot 3 \cdot 3^k + 5k + 1 = 6 (2^{k+2} \cdot 3^k) + 5k + 1 = 6 (2^{k+2} \cdot 3^k + 5k - 4) - 25k + 25 = 6A_k - 25 (k - 1)$$

chia hết cho 25 vì $A_k$ chia hết cho 25 theo giả thuyết quy nạp.

Do đó, $A_n$ chia hết cho 25 với mọi số tự nhiên $n$.

Bài toán 8. Một số được biểu thị, là một số chính phương, có tính chất sau: nếu tất cả các chữ số của nó bị rút gọn bởi cùng một số, thì bạn sẽ có một chữ số nguyên của số đó, cũng là một số chính phương. Tìm tất cả các chữ số nguyên của một số có thuộc tính được mô tả.

Khuyên bảo. Trong một số trường hợp, nên cố gắng giải bài toán bằng cách chọn lọc. Cần nhớ rằng việc lựa chọn phải đầy đủ, nếu không thì bài toán không thể được coi là giải quyết được.

Lời giải. Nó được cho rằng

$$\frac{abcd}{(a-k)(b-k)(c-k)(d-k)} = B^2.$$

Rõ ràng là vậy

$$a \geq k, b \geq k, c \geq k, d \geq k.$$

Hãy xem xét sự khác biệt $A^2 - B^2$:

$$A^2 - B^2 = (1000a + 100b + 10c + d) - [1000(a-k) + 100(b-k) + 10(c-k) + (d-k)] = 1111k,$$

đó là

$$(A + B)(A - B) = 11 \cdot 101k.$$

Vì $A^2$ và $B^2$ là các chữ số nguyên nên $32 \leq A \leq 99$ và $32 \leq B \leq 99$; điều đó có nghĩa là, trong mọi trường hợp

$$64 < A + B < 200,$$

$$0 < A - B < 67.$$

Ngay sau đó là $A + B = 101$, $A - B = 11 \cdot k$. Razumma $A + B$ là số lẻ thì hiệu $A - B$ là số lẻ. Vì vậy, $k$ cũng phải là số lẻ. Vì $A - B < 67$, các giá trị sau cho $k$ có thể phù hợp: 1, 3, 5. Chỉ $k = 1$ và $k = 3$ là phù hợp.

Đáp số. a) $3136 = 56^2$; $2025 = 45^2$.

6) $4489 = 67^2$, $1156 = 34^2$.

Và cuối cùng, lời khuyên chính: giải quyết càng nhiều bài toán càng tốt, bởi vì hợp đồng và sự khéo léo chỉ có được nhờ kinh nghiệm.

Bài tập

4. Chứng minh rằng $A = m(m^2 - 7)$ chia hết cho 6 với mọi số tự nhiên $m$.

5. Chứng minh rằng nếu cộng số đó vào bên phải của số có ba chữ số bất kỳ thì số có sáu chữ số chia hết cho 7, 11 và 13.

6. Tìm một số có hai chữ số bằng bình phương riêng của tổng các chữ số của nó.

7. Chứng minh rằng một số gồm $3^n$ đơn vị thì chia hết cho $3^n$.

8. Chứng minh rằng không tồn tại số nguyên $a, b, c$ thỏa mãn các đẳng thức: $abc + a = 3333, abc + b = 5555, abc + c = 7777$.

9. Chứng minh rằng nếu $p$ là số nguyên tố lớn hơn 3 thì $N = p^2 + 3n + 2$ là hợp số của mọi số tự nhiên $n$.

10. Chứng minh rằng $S = 3 + 3^3 + 3^5 + \dots + 3^{4n-1}$ chia hết cho 10.

11. Tìm một số có năm chữ số mà tích các chữ số của nó gấp 45 lần.

12. Chứng minh rằng số tiền

$$\underbrace{11 \dots 1}_{m\text{ цифр}} \cdot \underbrace{100 \dots 5}_{m+1\text{ цифра}} + 1$$

là bình phương của một số tự nhiên.
