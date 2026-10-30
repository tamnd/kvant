---
id: 1970-5-egorov-sravneniya-po-modulyu-i-arifmetika-ostatkov-20d66909
issue: kvant_1970_5
year: 1970
number: "5"
title: So sánh theo mô-đun và số học các số dư
authors:
  - Егоров А. А.
rubric: osnovnye-stati
page_first: 29
page_last: 35
page_labels: 27, 28, 30, 31, 32, 33
tag: 7O65
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 64ef256d9eb4e485e6902b9a6535a8cd2fd16701775047f1fa80d3dff012dd88
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1970/05/articles/05_egorov-sravneniya-po-modulyu-i-arifmetika-ostatkov-20d66909.md
source_content_sha256: 8d2ec17e7576e00de0a044bc73e0c88998476df7c6fa7577912dba326a69beb0
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-30
---

⟦folio 27⟧

1. PHÉP CHIA CÓ DƯ

Bạn sắp đi tàu điện ngầm. Giá vé là 5 cô-pếch; việc kiểm soát ở lối vào là tự động: cần thả một đồng năm cô-pếch vào khe của máy, còn nếu không có, thì đổi tiền của bạn ở quầy đổi tiền lấy các đồng năm cô-pếch.

Giả sử bạn có một đồng 20 cô-pếch. Bạn có thể nhận được bao nhiêu đồng năm cô-pếch ở quầy? Ai cũng sẽ nói là 4.

Thế còn nếu bạn có 19 cô-pếch mà không có đồng năm cô-pếch? Rõ ràng, bạn chỉ có thể nhận được 3 đồng năm cô-pếch và thêm 4 cô-pếch tiền thừa. Viết như sau: $19 = 3 \cdot 5 + 4$. Đó là cách viết phép chia số 19 cho 5 có dư.

Bây giờ hãy tưởng tượng rằng có các đồng xu với mọi mệnh giá, tức là 1 cô-pếch, 2 cô-pếch, 3 cô-pếch, 4 cô-pếch v.v., và bạn cần đổi một đồng $a$ cô-pếch sao cho nhận được số đồng $b$ cô-pếch lớn nhất. Hỏi làm thế nào?

Rõ ràng, nếu bạn biết đếm các đồng $b$ cô-pếch:

$b, 2b, 3b$ v.v.,

thì cuối cùng sẽ đến lúc mà, sau khi nhận được một số đồng $b$ cô-pếch, bạn không thể nhận được đồng tiếp theo; bạn sẽ được một số

⟦folio 28⟧

đồng $b$ cô-pếch nào đó và một số dư nào đó, chẳng hạn $r$ cô-pếch. Khi đó $r$ nhất định nhỏ hơn $b$ (dĩ nhiên không loại trừ trường hợp $r = 0$).

Kết quả của việc đổi như vậy có thể viết như sau:

$$a = kb + r, \quad r < b.$$

Trong công thức này, các số $a, b$ là số tự nhiên, tức là các số nguyên dương, còn $k$ và $r$ là các số nguyên không âm.

Về định nghĩa phép chia có dư. Chia số nguyên $a$ cho số tự nhiên $b$ có nghĩa là biểu diễn $a$ dưới dạng

$$a = kb + r,$$

trong đó $k, r$ là các số nguyên, $b > r \geq 0$.

Khi đó số $k$ được gọi là thương, còn $r$ là số dư của phép chia $a$ cho $b$.

Trong thực tế, phép chia có dư được thực hiện theo cách thông thường, tức là “phép chia dài”. Ví dụ,

$$\frac{175}{14} = \frac{14}{12};$$

$$\frac{28}{7}$$

ở đây số dư và thương được tìm ngay: $175 = 12 \cdot 14 + 7$.

Lưu ý rằng trong định nghĩa này, chúng ta không yêu cầu $a$ nhỏ hơn $b$, thậm chí cũng không yêu cầu $a$ dương. Chẳng hạn, có thể chia

a) 5 cho 7: $5 = 0 \cdot 7 + 5 \quad (k = 0, r = 5)$,

b) -13 cho 7: $-13 = (-2) \cdot 7 + 1 \quad (k = -2, r = 1)$,

b) -224 cho 7: $-224 = (-32) \cdot 7 \quad (k = -32, r = 0)$.

Trong trường hợp số dư bằng không, tức là $a = kb$, người ta nói rằng $a$ chia hết cho $b$.

Rõ ràng rằng nếu các số $a$ và $b$ chia hết cho số $c$, thì cả $a+b$ và $a-b$, cũng như $ka, kb$ (k— số tự nhiên) đều chia hết cho $c$.

2. SO SÁNH CÁC SỐ NGUYÊN THEO MÔĐUN

Thường gặp những bài toán mà vai trò chính không phải do chính các số có trong điều kiện bài toán, mà do các số dư khi chia các số đó.

Ví dụ thứ nhất. Psezid đi từ thành phố $A$ đến thành phố $B$ trong 78 giờ. Anh ta rời $A$ lúc 10 giờ sáng. Anh ta sẽ đến $B$ lúc mấy giờ?

Ta nhớ rằng một ngày có 24 giờ, chia số 78 cho 24:

$$78 = 3 \cdot 24 + 6$$

Vậy anh ta sẽ đi từ $A$ đến $B$ ba ngày và 6 giờ. Do đó, anh ta sẽ đến $B$ lúc 16 giờ.

Hãy chú ý rằng kết quả hoàn toàn giống như vậy cũng sẽ thu được nếu từ $A$ đến $B$ không phải 78 mà là 54, 30 hoặc 126, 102, và nói chung là $24 \cdot k + 6$ giờ với mọi số nguyên $k$.

Ví dụ thứ hai. Giáo viên toán tổ chức trong lớp các bài kiểm tra theo hệ thống sau, theo ông, bảo đảm sự cần thiết phải giúp đỡ lẫn nhau của học sinh. Ông phát liên tiếp cho các em những tờ giấy ghi đề bài («các phương án»), đánh số chúng theo số học sinh trong lớp, và thông báo rằng tất cả các phương án đều khác nhau. Và quả thật, những học sinh ngồi không xa nhau giải các bài khác nhau.

Thực ra giáo viên chỉ chuẩn bị 7 phương án khác nhau: phương án 8 trùng với phương án 1, 9 — với 2, ..., 14 — với 7, 15 — với 1, v.v.

⟦folio 30⟧

Bây giờ ta đưa ra định nghĩa sau:

Định nghĩa. Nếu các số nguyên $a$ và $b$ sao cho hiệu của chúng chia hết cho số tự nhiên $m$, thì nói rằng $a$ và $b$ đồng dư theo môđun $m^*$).

Sự đồng dư của các số $a$ và $b$ theo môđun $m$ được viết như sau:

$$a \equiv b \pmod{m}.$$

Rõ ràng hai số đồng dư theo môđun $m$ khi và chỉ khi chúng cho cùng số dư khi chia cho $m$, nghĩa là thuộc cùng một lớp.

Ví dụ,

$$27 \equiv 7 \pmod{10}, \quad 78 \equiv 6 \pmod{24}, \quad 6 \equiv 0 \pmod{3}, \quad 25 \equiv -1 \pmod{13}.$$

Các đồng dư quen thuộc của các số tỏ ra hữu ích khi giải nhiều bài toán.

Bài toán 1. Với những số tự nhiên $n$ nào thì số $n^2+2$ chia hết cho 3, tức là $n^2+2 \equiv 0 \pmod{3}$?

Lời giải.

Nếu $n \equiv 0 \pmod{3}$, thì $n^2+2 \equiv 2 \pmod{3}$,

» $n \equiv 1 \pmod{3}$, » $n^2+2 \equiv 0 \pmod{3}$,

» $n \equiv 2 \pmod{3}$, » $n^2+2 \equiv 0 \pmod{3}$.

Vậy, $n^2+2 \equiv 0 \pmod{3}$ khi và chỉ khi $n$ không chia hết cho 3.

Các tính chất cơ bản của đồng dư gợi nhớ các tính chất của những đẳng thức thông thường. Cụ thể, các đồng dư có thể được cộng, trừ và nhân:

nếu $a \equiv b \pmod{m}$, và $c \equiv d \pmod{m}$, thì

$$a + c \equiv b + d \pmod{m}, \quad a - c \equiv b - d \pmod{m}, \quad ac \equiv bd \pmod{m}.$$

Chẳng hạn, ta chứng minh rằng có thể nhân các đồng dư. Vì $a \equiv b \pmod{m}$ và $c \equiv d \pmod{m}$, nên $a-b$ và $c-d$ chia hết cho $m$. Từ các đẳng thức

$$ac - bd = ac - ad + ad - bd = a(c-d) + d(a-b)$$

thấy rằng $ac-bd$ cũng chia hết cho $m$, tức là

$$ac \equiv bd \pmod{m}.$$

Bài tập: chứng minh rằng có thể cộng và trừ các đồng dư.

Giả sử $a \equiv b \pmod{m}$. Từ các tính chất của đồng dư đã nêu ở trên suy ra rằng $a^k \equiv b^k \pmod{m}$ với mọi số tự nhiên $k$ (nghĩa là có thể nâng cả hai vế của đồng dư lên lũy thừa) và, ngoài ra, rằng $ac \equiv bc \pmod{m}$, trong đó $c$ là một số nguyên bất kỳ (nghĩa là có thể nhân cả hai vế của đồng dư với một số nguyên bất kỳ).

Bài toán 2. Số $(2^2+1)(3^2+1)(4^2+1) \dots (1000^2+1)$ cho số dư nào khi chia cho 3?

Lời giải. Số dư này không thay đổi nếu thay mỗi số 2, 3, . . . , 1000 trong biểu thức đã cho bằng số dư của nó khi chia cho 3. Do đó, số đang xét theo môđun 3 bằng $(2^2+1)^{333} (3^2+1)^{333} (1^2+1)^{333} \equiv 5^{333} \cdot 10^{333} \cdot 2^{333} \equiv 2^{333} \cdot 1^{333} \cdot 2^{333} \equiv 2^{2 \cdot 333} \equiv 4^{333} \equiv 1^{333} \equiv 1$, tức là số dư cần tìm bằng 1.

*) Từ “môđun” (từ tiếng Latinh “modulus”—thước đo) được dùng trong nhiều lĩnh vực của toán học và các ứng dụng của nó; nó được gán cho một số có ý nghĩa đặc biệt quan trọng; chẳng hạn, việc đếm hoặc đo được tiến hành theo số đó.

⟦folio 31⟧

Bài tập 3. Chứng minh rằng mọi số tự nhiên $n$ đồng dư theo môđun 9 với tổng các chữ số của nó.

Lời giải. Giả sử

$$\overline{a = a_n a_{n-1} \dots a_0},$$

trong đó $a_0, a_1, \dots, a_n$ là các chữ số của số $a$. Ta có

$$a = a_n \cdot 10^n + a_{n-1} \cdot 10^{n-1} + \dots + a_0.$$

Bây giờ hãy viết các đồng dư sau:

$$1 \equiv 1 \pmod{9}, \quad 10 \equiv 1 \pmod{9}, \quad \dots, \quad 10^n \equiv 1 \pmod{9}.$$

Nhân các đồng dư này lần lượt với $a_0, a_1, \dots, a_n$ rồi cộng lại, ta được

$$a_0 + 10 \cdot a_1 + \dots + 10^n a_n = a \equiv (a_0 + a_1 + \dots + a_n) \pmod{9}.$$

Từ đây, nhân tiện, lập tức suy ra dấu hiệu quen thuộc về tính chia hết của các số cho 9 (và cho 3).

3. SỐ HỌC CÁC SỐ DƯ THEO MÔĐUN ĐÃ CHO

Cho số tự nhiên $m$ (môđun). Xét mọi số nguyên, ta sẽ chỉ quan tâm đến các số dư của chúng khi chia cho $m$. Như vậy, ta sẽ không phân biệt các số đồng dư theo môđun $m$. Với điều kiện đó, ta có $m$ đối tượng «khác nhau» — các số dư khi chia cho $m$:

$$0, 1, 2, 3, \dots, m-1,$$

và đối với chúng ta có thể xác định những quy tắc mới về «cộng» và «nhân»: cụ thể, nếu $r_1$ và $r_2$ là hai số dư, thì «tổng» $r_1 + r_2$ sẽ được gọi là số dư mà số $r_1 + r_2$ cho khi chia cho $m$, còn «tích» $r_1 \cdot r_2$ — là số dư khi chia $r_1 \cdot r_2$ cho $m$. Chẳng hạn, với $m = 10$, số dư khi chia một số cho 10 là chữ số cuối trong cách viết thập phân của nó. Vì vậy, trong số học các số dư theo môđun 10, chẳng hạn, cũng đúng các đẳng thức

$$7 + 3 = 0, \quad 1 + 2 = 3, \quad 7 + 5 = 2, \quad 7 \cdot 5 = 5, \quad 7 \cdot 6 = 2, \quad 2 \cdot 5 = 0.$$

Trong số học các số dư theo modulo 2 chỉ có hai số dư: 0 và 1, vì thế số học này rất đơn giản:

$$0 + 0 = 0, \quad 1 + 0 = 1, \quad 1 + 1 = 0,$$

$$0 \cdot 0 = 0, \quad 1 \cdot 0 = 0, \quad 1 \cdot 1 = 1.$$

Với $m = 6$ ta được

$$5 + 3 = 2, \quad 4 + 2 = 0, \quad 3 + 3 = 0, \quad 3 \cdot 2 = 0, \quad 3 \cdot 4 = 0$$ v.v.

Như vậy, mỗi modulo $m$ tương ứng với một số học riêng. Để gọn, ta sẽ gọi nó là số học $m$*).

⟦folio 32⟧

Làm ví dụ, hãy đưa ra các bảng nhân và cộng trong số học 7.

Bảng nhân

| × | 1 | 2 | 3 | 4 | 5 | 6 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | 1 | 2 | 3 | 4 | 5 | 6 |
| 2 | 2 | 4 | 6 | 1 | 3 | 5 |
| 3 | 3 | 6 | 2 | 5 | 1 | 4 |
| 4 | 4 | 1 | 5 | 2 | 6 | 3 |
| 5 | 5 | 3 | 1 | 6 | 4 | 2 |
| 6 | 6 | 5 | 4 | 3 | 2 | 1 |

Bảng cộng

| + | 0 | 1 | 2 | 3 | 4 | 5 | 6 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 0 | 0 | 1 | 2 | 3 | 4 | 5 | 6 |
| 1 | 1 | 2 | 3 | 4 | 5 | 6 | 0 |
| 2 | 2 | 3 | 4 | 5 | 6 | 0 | 1 |
| 3 | 3 | 4 | 5 | 6 | 0 | 1 | 2 |
| 4 | 4 | 5 | 6 | 0 | 1 | 2 | 3 |
| 5 | 5 | 6 | 0 | 1 | 2 | 3 | 4 |
| 6 | 6 | 0 | 1 | 2 | 3 | 4 | 5 |

Các bảng này được lập như sau: tại giao điểm của các hàng và cột, người ta đặt tích (tương ứng là tổng) của các số dư đứng đầu những hàng và cột ấy.

Từ các tính chất của phép đồng dư và các quy tắc thông thường về phép toán trên số, thấy rằng trong số học $m$ các quy tắc đã nêu của số học thông thường đều đúng, tức là với mọi số dư $a, b, c$ ta có

$$a+b = b+a \text{ — коммутиативность (переместительность) сложения},$$
$$(a+b)+c = a+(b+c) \text{ — ассоциативность (сочетательность) сложения},$$
$$ab = ba \text{ — коммутиативность умножения},$$
$$(ab)c = a(bc) \text{ — сочетательность умножения},$$
$$a(b+c) = ab+ac \text{ — дистрибутивность (распределительность) умножения относительно сложения}.$$

Như vậy, chẳng hạn, trong các số học của ta sẽ đúng những công thức sau:

$$(a+b)^2 = a^2 + 2ab + b^2,$$
$$(a+b)(c+d) = ac + ad + bc + bd.$$

Xét vài bài toán về việc sử dụng số học $m$.

Bài tập 4. Tìm số dư khi chia $2^{1000}$ cho 7.

Lời giải. Ta phải xác định $2^{1000}$ bằng bao nhiêu trong số học 7. Dễ thấy rằng $2^{1000} = (2^3)^{333} \cdot 2 = 1^{333} \cdot 2 = 2$.

Bài tập 5. Tìm chữ số cuối cùng của số $7^{7^{1000}}$.

Lời giải. Ta phải xác định số này bằng bao nhiêu trong số học 10. Để làm điều đó, xét các lũy thừa liên tiếp của số 7 trong số học 10:

$$7^1 = 7, 7^2 = 9, 7^3 = 3, 7^4 = 1, 7^5 = 7 \text{ v.v.}$$

Rõ ràng rằng

$$7^{4n} = 1, 7^{4n+1} = 7, 7^{4n+2} = 9, 7^{4n+3} = 3.$$

Vậy ta phải tìm số dư khi chia số $7^{1000}$ cho 4. Để làm điều đó, xét $7^{1000}$ trong số học 4. Vì $7^{1000} = 3^{1000}$, giờ đây ta xét dãy số dư trong số học 4:

$$3^1 = 3, 3^2 = 1, 3^3 = 3, 3^4 = 1, 3^5 = 3, \dots,$$

⟦folio 33⟧

$$3^{2n+1} = 3, \quad 3^{2n} = 1.$$

Nhưng 1000 là số chẵn; do đó, $7^{1000} = 1$, tức là $7^{1000} = 4n+1$. Suy ra, trong số học modulo 10 $7^{71000} = 7^{4n+1} = 7^{4n} \cdot 7 = 7$.

Đáp số: số $7^{71000}$ tận cùng bằng 7.

Bài toán 6. Chứng minh rằng nếu $a^2+b^2$ chia hết cho 3 thì cả $a$ lẫn $b$ đều chia hết cho 3.

Lời giải. Chuyển sang các số dư khi chia cho 3, ta được đẳng thức trong số học modulo 3 $a^2+b^2 = 0$. Trong số học modulo 3 có ba số dư: 0, 1, 2.

Ta có: $1^2 = 1, 2^2 = 1$. Dễ thấy rằng khi $a \neq 0$ thì $a^2+b^2 \neq 0$, tức là từ đẳng thức $a^2+b^2 = 0$ suy ra $a = 0$ và $b = 0$. Điều này có nghĩa là $a$ và $b$ đồng thời chia hết cho 3.

BÀI TOÁN *)
1. Phép chia có dư
1.0. Chia có dư —297 cho 31, —1005 cho 98.
2. Chứng minh rằng số ước của mọi số tự nhiên $N$ không vượt quá $2\sqrt{N}$.
3. Tìm số dư khi chia các số ($n$ — số tự nhiên): a) $n$ cho $(n-1)$ và cho $(n-2)$; b) $(n^2+n+1)$ cho $(n+1)$ và cho $(n+2)$; c) $(n^4+1)$ cho $(n+3)$ (với $n \geqslant 80$).
4. Tìm tất cả các số nguyên $n$ sao cho số $\frac{n^2+1}{n-1}$ cũng là số nguyên.
5. Chứng minh rằng tích của ba số nguyên liên tiếp bất kỳ chia hết cho 6.
6. Chứng minh rằng nếu $a+b+c$ chia hết cho 6, thì $a^3+b^3+c^3$ cũng chia hết cho 6 ($a, b, c$ — các số nguyên).
7*. 15 số nguyên tố lập thành một cấp số cộng. Chứng minh rằng công sai của nó lớn hơn 30 000.

2. So sánh các số nguyên theo môđun
8.0. Tìm tất cả các số tự nhiên $n$ sao cho số $n^3+n+1$ chia hết cho 3.
9.0. Giải đồng dư $6n+5 \equiv 0$ (mod 7).
10. Chứng minh dấu hiệu chia hết cho 11 sau đây:
$$a = \overline{a_n a_{n-1} \dots a_0} \equiv 0 \pmod{11}$$

khi và chỉ khi
$(-1)^n a_n + (-1)^{n-1} a_{n-1} + \dots + a_n \equiv 0 \pmod{11}$.
11. Dùng việc $1000 \equiv -1$ (mod 7), cũng như $1000 \equiv 1$ (mod 37), hãy tìm các dấu hiệu chia hết cho 7 và cho 37.
12. Chứng minh rằng nếu các số $A$ và 5$A$ có cùng tổng các chữ số, thì $A$ chia hết cho 9.
13. Chứng minh rằng phương trình $15x^2-7y^2=9$ không có nghiệm nguyên.
14. Chứng minh rằng với mọi số nguyên $n$, số $n^2+3n+5$ không chia hết cho 11.
15. Chứng minh rằng các số dạng $3n+2, 5n \pm 2, 7n+3, 7n-1, 7n-2$ với mọi $n$ tự nhiên đều không phải là số chính phương.
3. Số học các số dư theo môđun đã cho
16.0. Lập các bảng cộng và nhân trong các số học 4, 6, 8, 11 và 13.
17. Lập các bảng bình phương và lập phương trong số học 9.
18. Dùng bảng lập phương thu được ở bài 17, chứng minh rằng các số dạng $9n+5$ và $9n+4$ không thể biểu diễn thành tổng các lập phương của ba số.
19. Chứng minh rằng trong số học $p$, trong đó $p$ là số nguyên tố, từ đẳng thức $ab=0$ khi $a \neq 0$ suy ra $b=0$.
20. Chứng minh rằng trong số học $m$, với mọi số dư $a$ tồn tại duy nhất số dư — $a$ sao cho $a+(-a)=0$. Suy ra từ đây rằng phương trình $a+x=b$ có nghiệm trong mọi số học $m$ với mọi $a$ và $b$.
21. Chứng minh rằng khi $m$ là hợp số, trong số học $m$ tồn tại các số dư $a \neq 0$ và $b \neq 0$ sao cho $ab=0$.
22. Dùng số học 31, chứng minh rằng $1^{255}+2^{255}+\dots+30^{255}$ chia hết cho 31.

*) Các bài dễ được đánh dấu bằng vòng tròn, các bài khó nhất — bằng dấu sao.
