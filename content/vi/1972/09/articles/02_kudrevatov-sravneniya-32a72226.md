---
id: 1972-9-kudrevatov-sravneniya-32a72226
issue: kvant_1972_9
year: 1972
number: "9"
title: So sánh
authors:
  - Кудреватов Г. А.
rubric: osnovnye-stati
page_first: 18
page_last: 20
page_labels: 16, 18
tag: 9DNE
lang: vi
source: kvant_digital
extraction: vision
content_sha256: a03d77196ce988e809c7048eb693d93288dfe740699a159bcde51e52959ca5bf
prompt_sha256: draft-1
translated_from: content/ru/1972/09/articles/02_kudrevatov-sravneniya-32a72226.md
source_content_sha256: c20f55aa0b6ab1fb0562c022c7223e13013c786b74d2caaa4f80b294f2ee54c8
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 16⟧

Liệu nó có bị chia cắt hay không? Câu hỏi này thường phát sinh trong số học số nguyên. Và điều này không phải ngẫu nhiên - xét cho cùng, phép chia là phép tính số học phức tạp nhất.

Chúng ta hãy biểu thị số bị chia và số chia bằng các chữ cái $a$ và $m$ (chúng ta sẽ giới hạn trong trường hợp $m > 0$), thương và số dư tương ứng bằng các chữ cái $q$ và $r$. Sau đó (xem hình) $a = mq + r$, $0 \leq r < m$ (định nghĩa phép chia có số dư).

Nếu $r = 0$ thì $a = mq$ và chúng ta nói rằng “a chia hết cho $m$” hoặc “a là bội số của $m$”. Điều này được biểu thị bằng ba mắt: $a : m$; ký hiệu: có nghĩa là “chia cho…”

Trong một số trường hợp, dấu hiệu chia hết giúp trả lời câu hỏi nó có chia hết hay không. Nhưng trong khóa học ở trường, chỉ những điều đơn giản nhất mới được xem xét: 2, 3, 5 và 9. Các dấu hiệu chia hết, chẳng hạn như cho 7, 11, nằm ngoài phạm vi khóa học ở trường. Kiến thức thu được trong các bài học số học không đủ để tìm số dư của phép chia $2^{25} + 1$ cho 641, 1971$^{1972}$ cho 7, $22^{11} + 11^{22}$ cho 3. Những câu hỏi này và nhiều câu hỏi khác được trả lời bằng lý thuyết so sánh đáp số, các yếu tố của lý thuyết này sẽ được thảo luận trong bài viết này.

1. Phần dư của phép chia

Thường thì phần còn lại $r$ được quan tâm nhiều hơn thương $q$. Ví dụ, để xác định GCD

$$mq \cdot a \cdot m(q+1)$$

Hình 1.

(*) Điều này được mô tả chi tiết trong bài viết của V. N. Vaguten “Thuật toán Euclide và Định lý cơ bản của số học”, «Kvant» Số 6, 1972.

⟦folio 18⟧

có thể, nhiều modulo. Trong trường hợp này, điều đáng chú ý là so sánh không chỉ có hình dáng bên ngoài giống với các đẳng thức chung mà còn có hầu hết tất cả các tính chất cơ bản của chúng.
Do đó, có thể thu được sự so sánh trên cùng một modulo bằng cách cộng, trừ và nhân:

$$a \equiv b, c \equiv d \pmod{m} \Rightarrow a \pm c \equiv b \pm d, ac \equiv bd \pmod{m}.$$ (C)

Điều này cũng dẫn tới hệ quả sau:
cùng một số có thể được thêm vào một phần của phép so sánh đã cho, chúng có thể được nhân với cùng một số và cũng có thể được nâng lên cùng một lũy thừa tự nhiên, nghĩa là

$$a \equiv b \pmod{m} \Rightarrow a + c \equiv b + c, ac \equiv bc, a^k \equiv b^k \pmod{m}.$$

Bài tập

1. Chứng minh tiêu chí (K) và tính chất so sánh (C).
2. Chứng minh rằng các phần của phép so sánh có thể rút gọn đi một số nguyên tố cùng nhau trong mô hình (tất nhiên nếu cả hai phần của phép so sánh đều chia hết cho số này).
3. Chứng minh rằng phép so sánh 3x ≡ 4(mod5) đúng với mọi x so sánh được với 3 trong một modulo đã cho.
4. Kiểm tra rằng không có số nguyên x thỏa mãn 3x ≡ 2(mod 6).

3. So sánh modulo và phân vùng lớp

Các thuộc tính so sánh được đưa ra trong đoạn 2 giúp bạn có thể giải quyết tương đối đơn giản nhiều lý thuyết chia hết bài toán, thường thấy trong các kỳ thi Olympic, các cuộc thi, v.v. Hãy xem xét một số trong số chúng, nhưng trước tiên hãy lưu ý rằng đối với lời giải những bài toán này, bạn có thể tự mình quyết định chia thành các lớp số có thể so sánh theo một modulo nhất định (trong trường hợp này, mô hình được chọn tùy thuộc vào hoàn cảnh hoặc được xác định bởi điều kiện bài toán chính nó).

Với mỗi phép so sánh, x ≡ a(mod m) thỏa mãn các lớp số x mà khi chia cho m sẽ cho số dư r(a, m). Đối với mỗi x một trong những so sánh được thực hiện

$$x \equiv 0, x \equiv 1, x \equiv 2, \dots, x \equiv m - 2, x \equiv m - 1 \pmod{m}$$

hoặc, cái gì giống nhau, một trong những đẳng thức

$$x = mt, x = 1 + mt, x = 2 + mt, \dots, x = m - 2 + mt, x = m - 1 + mt,$$

trong đó t là số nguyên tương ứng. Vì vậy, mỗi số nguyên thuộc về một trong m lớp; các số không thể so sánh được trong một modulo nhất định sẽ thuộc các lớp khác nhau.

Bài tập

5. Kiểm tra xem quan hệ so sánh có phải là quan hệ tương đương hay không và phân chia tất cả các số thành các lớp so sánh được, cụ thể là chứng minh rằng

a) x ≡ x(mod m);
b) x ≡ y(mod m) ⇒ y ≡ x(mod m);
b) x ≡ y, y ≡ z(mod m) ⇒ x ≡ z(mod m).

Việc phân chia thành các lớp được thảo luận chi tiết trong bài viết của M. M. Glukhov “Quan hệ tương đương và phân vùng của một tập hợp”, “Quant” số 2, 1972.

4. Một số bài toán

Để sử dụng “ngôn ngữ so sánh” cho lời giải bài toán một cách tự do hơn, hãy xem xét các câu hỏi sau: ví dụ: lớp nào, theo modulo 6, chứa số nguyên tố? Số nguyên tố 37 thuộc lớp nào sau đây? Lớp modulo 6 nào chứa lũy thừa đích của các số?

Dễ dàng thấy rằng lớp x ≡ 0(mod 6) không chứa các số nguyên tố: nó bao gồm các số là bội số của 6. Lớp x ≡ 4(mod 6) không chứa các số nguyên tố, vì nó bao gồm bốn số 4+6t = 2(2+3t) (và không chứa số 2). các lớp x ≡ 2 và x ≡ 3(mod 6) mỗi lớp chứa một số nguyên tố lần lượt là 2 và 3. các lớp x ≡ 1, x ≡ 5(mod 6) chứa tất cả các số nguyên tố khác; ví dụ: cái đầu tiên bao gồm 7 và 13, và cái thứ hai bao gồm 11 và 17.
