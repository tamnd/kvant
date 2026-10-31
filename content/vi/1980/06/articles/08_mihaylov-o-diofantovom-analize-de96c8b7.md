---
id: 1980-6-mihaylov-o-diofantovom-analize-de96c8b7
issue: kvant_1980_6
year: 1980
number: "6"
title: Về phân tích Diophantine
authors:
  - Михайлов И. И.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 18
page_last: 19
page_labels: 16-17
tag: WUIL
lang: vi
source: kvant_digital
extraction: vision
content_sha256: b41d3f24b8ba06096bb1c7ea608797d695903dfb27fa9b2a08b5bf8fb226f747
prompt_sha256: draft-1
translated_from: content/ru/1980/06/articles/08_mihaylov-o-diofantovom-analize-de96c8b7.md
source_content_sha256: 77ea0ad92c4455dd7bf095d38a5183c8573d9d70b02155066b37d2d5972299da
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 16⟧

Về phân tích Diophantine

Lĩnh vực lý thuyết số nghiên cứu các phương trình số nguyên lời giải có dạng $P(x, y, ..., z) = 0$, trong đó $P(x, y, ..., z)$ là đa thức của một số biến có hệ số nguyên, được gọi là phân tích Diophantine và bản thân các phương trình này được gọi là Diophantine. Chúng tôi đã viết về một số phương trình Diophantine và phương pháp của chúng lời giải*).

Chúng ta hãy nhớ lại rằng phương trình lời giải Diophantine có nghĩa như sau:

1. nó có ít nhất một số nguyên lời giải;
2. số các số nguyên lời giải của nó là hữu hạn hoặc vô hạn;
3. tìm tất cả các số nguyên của nó lời giải.

Ví dụ: đối với phương trình $x^3 + y^3 + z^3 = 30$, không có số nguyên lời giải nào được hiển thị. Tuy nhiên, có lẽ lời giải sẽ được tìm thấy sau này. Hoặc có thể nó sẽ được chứng minh rằng chúng không tồn tại.

Nhưng đối với phương trình $x^3 + y^3 + z^3 = 3$, thậm chí lời giải đã biết: (1; 1; 1), (4; 4; -5), (4; -5; 4), (-5; 4; 4). Nhưng hiện tại câu hỏi vẫn còn bỏ ngỏ: có lời giải nào khác không?

Một ví dụ khác. Người ta đã chứng minh rằng phương trình $x^3 + y^3 + z^3 = 2$ có tập vô hạn lời giải dưới dạng số nguyên $(x; y; z) = (1 + 6\alpha^3; 1 - 6\alpha^3; -6\alpha^2)$, trong đó $\alpha$ là số nguyên. Nhưng trước đó

*) Xem «Kvant», 1971, số 3, tr. 15; 1978, không. 1, tr. 25; Số 12, tr. 2.

Vẫn chưa rõ liệu tất cả lời giải của nó có được đưa ra bởi các công thức này hay không.

Một phương tiện mạnh mẽ để chứng minh tính vô hạn của tập hợp số nguyên lời giải phương trình Diophantine là phương pháp tham số hóa. Bản chất của phương pháp này là biểu diễn các biến $x, y, ..., z$ dưới dạng hàm tùy thuộc vào các tham số nguyên $\alpha, \beta, ..., \gamma$: $x = A(\alpha, \beta, ..., \gamma), y = B(\alpha, \beta, ..., \gamma), ..., z = C(\alpha, \beta, ..., \gamma)$, trong đó $A, B, ..., C$ là đa thức có hệ số nguyên. Các phương pháp tham số hóa, đôi khi rất nhân tạo, nhưng cực kỳ độc đáo, đòi hỏi sự khéo léo cao độ, và do đó góp phần tiếp thu và phát triển các kỹ năng hoạt động sáng tạo độc lập trong toán học.

Hãy quay lại phương trình $x^3 + y^3 + z^3 + z^3 = 2$ và thử tham số hóa nó. Để làm điều này, hãy đặt $x = a + b, y = a - b$, trong đó $a$ và $b$ là số nguyên; chúng tôi nhận được $2a^3 + 6ab^2 + z^3 = 2$. Đặt $a = 1$, sau đó $6b^2 = -z^3$, từ đó $z = 6c$ ($c$ là số nguyên), tức là $b^2 = -36c^3$. Trong trường hợp này, $c = -\alpha^2$ ($\alpha$ là số nguyên), nhưng sau đó là $b = 6\alpha^3$. Kết quả cuối cùng là $(1 + 6\alpha^3)^3 + (1 - 6\alpha^3)^3 + (-6\alpha^2)^3 = 2$.

Đó là $x = A(\alpha) = 1 + 6\alpha^3, y = B(\alpha) = 1 - 6\alpha^3, z = C(\alpha) = -6\alpha^2$. Thay thế các số nguyên thay vì $\alpha$, chúng ta thu được lời giải khác nhau.

Bài toán 1. Tham số hóa phương trình $x^3 + y^3 + z^3 = 2t^3$ và chứng minh rằng tập hợp các số nguyên lời giải của nó là vô hạn.

Các nhà toán học lý thuyết số đã bị mê hoặc trong nhiều năm bởi câu hỏi vẫn chưa được giải quyết bài toán: phương trình $x^4 + y^4 + z^4 = t^4$ có thể giải được bằng số nguyên không?

Năm 1914, A. Verebryusov đề xuất một bằng chứng về tính không thể quyết định được của nó. Tuy nhiên, như chúng ta đã phát hiện ra sau này, chứng minh của ông về phương trình này bằng số nguyên đã được Euler phát biểu. Năm 1945, người ta đã chứng minh rằng phương trình $x^4 + y^4 + z^4 = t^4$ không có lời giải trong số nguyên của $|t| < 10^8$. Nhưng tất nhiên, điều này vẫn chưa hoàn thành lời giải.

⟦folio 17⟧

Hãy thử giải bài toán đơn giản hơn, mặc dù bề ngoài “phức tạp hơn”: chúng ta sẽ chứng minh tính vô hạn của tập phương trình số nguyên lời giải $x^4 + y^6 + z^{12} = t^4$.

Đặt $x = a - b$, $t = a + b$, trong đó $a$ và $b$ là số nguyên. Sau đó $y^6 + z^{12} = 8a^3b + 8ab^3$. Hãy đặt $y^6 = 8a^3b$, $z^{12} = 8ab^3$; thì $a = c^3$, $b = d^3$ (c và $d$ là số nguyên) và $y^2 = 2c^3d$, $z^4 = 2cd^3$.

Theo đó $2cd$ là bình phương của một số nguyên. Bằng cách điền $c = a^4$, $d = 2\beta^4$ ($\alpha, \beta$ là số nguyên), chúng ta cũng nhận được giá trị hợp lệ

$$\left( \alpha^{12} - 8\beta^{12} \right)^4 + \left( 2\alpha^6\beta^2 \right)^6 + \left( 2\alpha\beta^3 \right)^{12} = \left( \alpha^{12} + 8\beta^{12} \right)^4,$$

chứng minh điều cần thiết.

Bài toán 2. Tìm một đẳng thức khác mô tả phương trình lời giải $x^4 + y^6 + z^{12} = t^4$.

Nhưng để chứng minh tính không thể giải được của một phương trình Diophantine nhất định, rất hữu ích cần lưu ý rằng chúng ta xem phương trình này “theo một modulo nhất định”*). Hãy để chúng tôi giải thích những gì chúng tôi muốn nói.

Hai số nguyên $a$ và $b$ được gọi là so sánh được theo modulo $k$ nếu hiệu $a - b$ chia hết cho $k$. Dễ dàng nhận thấy hai số $a$ và $b$ so sánh được theo modulo $k$ khi và chỉ nếu chúng có cùng số dư khi chia cho $k$. Việc $a$ và $b$ có thể so sánh được với modulo $k$ được viết như sau:

$$a \equiv b \pmod{k}.$$

Giả sử chúng ta cần giải phương trình Diophantine

$$x^3 + 117y^3 = 5.$$

Chúng ta hãy xem phương trình này là “modulo 9”, tức là các số hạng là bội số của chín. Không khó để chứng minh rằng bất kỳ số lập phương nào cũng chia hết cho 9 hoặc khi chia cho 9 thì dư 1 hoặc 8, tức là $x^3 \equiv 0 \pmod{9}$ hoặc $x^3 \equiv 8 \pmod{9}$.

Vì 117 chia hết cho 9 nên $117y^3 \equiv 0 \pmod{9}$. Như vậy,

$$x^3 + 117y^3 \equiv 0 \pmod{9}.$$

hoặc

$$x^3 + 117y^3 \equiv 1 \pmod{9}.$$

hoặc

$$x^3 + 117y^3 \equiv 8 \pmod{9}.$$

Do đó phương trình $x^3 + 117y^3 = 5$ không có số nguyên lời giải.

Bài toán 3. Chứng minh các phương trình a) $x^3 + y^3 = 9t \pm 4$; b) $x^3 + y^3 = 9t \pm 3$; b) $x^3 + y^3 + z^3 = 9t \pm 4$ không có số nguyên lời giải.

Các số hình tam giác và số hình vuông*) lần lượt được liên kết với một hình tam giác đều và một hình vuông (xem Hình 1, 2).

Chúng ta hãy biểu thị số hình tam giác thứ $n$ bằng $T_n$ và số bình phương thứ $n$ bằng $K_n$.

Bài toán 4. Chứng minh các công thức sau: $T_n = \frac{1}{2}n(n+1)$; $K_n = n^2$.

Bài toán tìm tất cả các số tam giác là số vuông, nối với lời giải của phương trình $T_n = K_n$, tức là phương trình $n(n+1) = 2m^2$.

Phương trình $x^2 - 2y^2 = 1$ có thể giúp chúng ta giải phương trình này. Nó có một tập vô hạn lời giải (bằng số tự nhiên), cho trước tuần hoàn: $x_{k+1} = 3x_k + 4y_k$ và $y_{k+1} = 2x_k + 3y_k$, $x_1 = 3$, $y_1 = 2$ (hãy tự chứng minh điều này hoặc xem cách chứng minh trong «Kvant», 1978, Số 1, trang 26).

(Cuối cùng xem trang 35)

*) Xem các bài viết của M. Bashmkov («Kvant», 1971, số 3) và A. Geronimus («Kvant», 1978, số 12).

2 «Kvant» № 6
