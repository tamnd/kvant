---
id: 1991-6-egorov-delenie-s-ostatkom-i-sravneniya-po-modulyu-87b22086
issue: kvant_1991_6
year: 1991
number: "6"
title: Phép chia với phần dư và so sánh modulo
authors:
  - Егоров А. А.
rubric: shkola-v-kvante
page_first: 38
page_last: 42
page_labels: 36-40
lang: vi
source: kvant_digital
extraction: vision
content_sha256: a7364abeb91f2ded6d3abbd9ea7f953cebeef9db04dd89fb4f941bf5870fdff1
prompt_sha256: draft-1
translated_from: content/ru/1991/06/articles/12_egorov-delenie-s-ostatkom-i-sravneniya-po-modulyu-87b22086.md
source_content_sha256: 5c21f85f86170f232eb665af757702498220b5170c6e654a3aff8ae7bdd72e93
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 36⟧

Phép chia với phần dư và so sánh modulo

Vào ngày 3 tháng 9 năm 1990, tôi cần tìm hiểu ngày 20 tháng 12 năm 1991 là ngày thứ mấy trong tuần. Tôi không có lịch trong tay nên phải tính toán một chút. Tôi biết ngày 3 tháng 9 là thứ Hai và từ ngày 3 tháng 9 năm 1990 đến ngày 20 tháng 12 năm 1991

27+31+30+20+365=473 ngày, tức là có 67 tuần trọn vẹn và 4 ngày nữa (473=67·7+4). Vì vậy ngày 20 tháng 12 năm 1991 là thứ Sáu.

Bằng cách bình phương một số có nhiều chữ số, học sinh nhận được đáp số 46.991.075. Giáo viên nhìn vào vở rồi nói ngay: “Đáp số sai!” Làm sao anh ấy hiểu được điều này?

Bài tập 1. Hãy suy nghĩ xem liệu bình phương của một số nguyên có thể là các chữ số 75 hay không.

Tiếp theo, chúng ta sẽ thấy rằng lời giải và bài toán đơn giản này, cùng nhiều thứ khác, đều dựa trên thông điệp chia hết. Tuy nhiên, trước tiên chúng ta cần nhớ phép chia có số dư là gì.

Phép chia có số dư

Sự định nghĩa. Chia số tự nhiên a cho số tự nhiên b có dư có nghĩa là viết a dưới dạng a=qb+r, trong đó q và r là số nguyên không âm và r<b. Số q được gọi là thương, a r là số dư của phép chia a cho b.

Trong thực tế, phép chia có số dư được thực hiện theo cách tổng quát, tức là “chia cho một góc”. Ví dụ:

$$\frac{179}{14} \frac{14}{12}$$

Ở đây số dư là 11 và thương là 12: 179=12·14+11.

Lưu ý rằng trong định nghĩa này chúng ta không yêu cầu a phải lớn hơn b. Ví dụ: bạn có thể chia 5 cho 7: 5=0·7+5. Nói chung, nếu a<b, thì a=0·b+a, tức là trong trường hợp này q=0, r=a.

Quét. Bạn có thể định nghĩa phép chia với phần dư của số nguyên a bất kỳ cho số nguyên bất kỳ b≠0 như sau: chia a cho b với số dư có nghĩa là biểu diễn a ở dạng a=qb+r, trong đó q là số nguyên, a 0 ≈ r ₫|b|. Ví dụ: với a=-15, b=7: -15=(-3)·7+6; với a=-224, b=-9: -224=15·(-9)+1, v.v.

Nếu phần dư bằng 0, tức là a=qb, a được gọi là chia hết cho b.

Quan sát đơn giản sau đây là rất quan trọng. Nếu a và b chia hết cho c thì với mọi số nguyên k và l thì số ka+lb chia hết cho c.

⟦folio 37⟧

---
running_head:
folio:
---

Bài tập 1. Các số $7n+1$ và $8n+3$ đều chia hết cho một số tự nhiên $d \neq 1$. Tìm $d$.

Lời giải. Vì $7(8n+3) - 8(7n+1) = 13$ nên số 13 chia hết cho $d$ nên $d = 13$ (vì $d \neq 1$ và 13 là số nguyên tố).

Bạn có kết hôn không?
2. Chia cho số dư
a) 1931 đến 17; 6) - 295 đến 31;
c) - 1005 đến - 98.
3. Số $17x+3y$ chia hết cho 61. Chứng minh rằng $8x+5y$ cũng chia hết cho 61 ($x$ và $y$ là số nguyên).
4. Tìm số dư khi chia số
a) $n$ trên $n-1$ và trên $n-2$;
b) $n^2+n+1$ trên $n+1$ và $n+2$;
c) $n^4+1$ đến $n+3$ ($n \geqslant 80$).
5. Tìm tất cả các số nguyên $n$ sao cho a) $\frac{n^2+1}{n-1}$ là số nguyên; 6) $\frac{n^5+3}{n^2+1}$.

So sánh modulo
Chúng ta hãy quy định ngay rằng tất cả các số sẽ được thảo luận dưới đây sẽ là số nguyên, do đó điều này sẽ không được nêu cụ thể trong tương lai. Hãy nhìn vào cái khác bài toán.

Bài 2. Số $2^{999}$ kết thúc bằng chữ số nào?

Lời giải. Hãy viết lũy thừa liên tiếp của hai:
2, 4, 8, 16, 32, 64,...
Dễ dàng nhận thấy rằng các chữ số cuối của những số này được lặp lại sau 4, do đó chữ số cuối cùng của số $2^n$ chỉ phụ thuộc vào số dư mà số mũ $n$ cho khi chia cho 4. Vì $999=996+3=4 \cdot 249+3$, đáp số trong bài toán: 8 của chúng ta.

Trong ví dụ này, toàn bộ tập hợp số mũ được chia thành 4 lớp, bao gồm các số $n$ có dạng $4k, 4k+1, 4k+2, 4k+3$.

Hơn nữa, đối với bất kỳ số tự nhiên $m$ nào, tất cả các số nguyên (không chỉ số nguyên dương!) đều được chia thành các lớp $m$. Mỗi lớp bao gồm các số có số dư giống nhau khi chia cho $m$.

Đây là các lớp:
0) các số $a$ có dạng $a=km$,
1) - a - a=km+1,
$m-1)$ — а — а=km+m-1.

Rõ ràng là bất kỳ số nào cũng thuộc về một trong các lớp trên. Trong trường hợp này, hiệu của hai số bất kỳ trong cùng một lớp sẽ chia hết cho $m$, nhưng hiệu của hai số từ các lớp khác nhau không chia hết cho $m$.

Sự định nghĩa. Nếu hiệu của các số nguyên $a$ và $b$ chia hết cho số tự nhiên $m$ thì $a$ và $b$ được cho là có thể so sánh được về mô đun.

Khả năng so sánh của các số modulo $m$ được viết như sau:

$a \equiv b(\text{mod } m)$.

Các số $a$ và $b$ có thể so sánh được theo modulo $m$ khi và chỉ nếu chúng thuộc cùng một lớp, nghĩa là chúng cho cùng số dư khi chia cho $m$. Nói cách khác, $a \equiv b(\text{mod } m)$ có nghĩa là $a=b+km$, trong đó $k$ là số nguyên. Ví dụ: $27 \equiv 7(\text{mod } 10)$, $78 \equiv 6(\text{mod } 24)$, $6 \equiv 0(\text{mod } 3)$, $25 \equiv -4(\text{mod } 29)$.

Bạn có kết hôn không?
6. Chứng minh rằng
a) $a^3 \equiv a(\text{mod } 6)$, 6) $a^4 \equiv a(\text{mod } 5)$.
7. Chứng minh số $a(a+1)...(a+k-1)$ là số nguyên.

8. Chứng minh rằng $2^{100} \equiv 3^{100}$ modulo 5, 13, 211.
9. Chứng minh rằng $11^{10} - 1$ chia hết cho 100.
10. Gọi $S(N)$ là tổng các chữ số của số $N$. Chứng minh rằng $N \equiv S(N)$ mod 3 và 9.
11. Hãy để $S(A)=S(5A)$. Chứng minh rằng $A \equiv 0(\text{mod } 9)$.
12. Một số số được viết trong hệ thập phân sử dụng số 1991 và một số số không. Chúng có thể là một hình vuông hoàn hảo không?
13. Sử dụng thực tế $10 \equiv -1(\text{mod } 11)$, hãy chứng minh phép kiểm tra tính chia hết của một số cho 11: số $a=a_na_{n-1}...a_0 \equiv 0(\text{mod } 11)$ khi và chỉ khi $(-1)^n a_n + (-1)^{n-1} a_{n-1} + ... + a_0$ chia hết cho 11.

Thuộc tính so sánh
So sánh điền vào các đẳng thức chung với các thuộc tính của chúng:
1) nếu $a \equiv b(\text{mod } m)$ và $b \equiv c(\text{mod } m)$ thì $a \equiv c(\text{mod } m)$.
2) $a+c \equiv b+d(\text{mod } m)$.
3) $a-c \equiv b-d(\text{mod } m)$.
4) $ac \equiv bd(\text{mod } m)$.
nghĩa là, các phép so sánh, giống như các đẳng thức tổng quát, có thể được cộng, trừ và có thể thay đổi.

⟦folio 38⟧

---
running_head:
folio:
---

Ví dụ, chúng ta hãy chứng minh tính chất 4. Vì $a \equiv b$ và $c \equiv d$, nên $a - b$ và $c - d$ chia hết cho $m$.

Từ đẳng thức $ac - bd = a(c - d) + d(a - b)$ hóa ra số $ac - bd$ chia hết cho $m$, tức là.

$$ac \equiv bd(\text{mod } m).$$

Bài tập 14. Chứng minh các tính chất còn lại của phép so sánh.

Hãy để $a \equiv b(\text{mod } m)$. Từ các thuộc tính so sánh đã được thiết lập, nó suy ra
5) cho bất kỳ tự nhiên $k$
$$a^k \equiv b^k.$$

Ngoài ra, trong một số trường hợp, sự so sánh có thể bị giảm đi bởi một yếu tố chung của bên trái và bên phải:
6) nếu $ac \equiv bc(\text{mod } m)$ và các số $c$ và $m$ là nguyên tố cùng nhau thì
$$a \equiv b(\text{mod } m);$$
7) nếu $a \equiv b(\text{mod } m)$, $k$ là số nguyên và $a = ka_1$, $b = kb_1$, $m = km_1$, thì
$$a_1 \equiv b_1(\text{mod } m_1).$$

Nói cách khác, cả hai vế của phép so sánh và mô hình đều có thể được chia cho ước số chung của chúng. Hãy chứng minh tính chất 6. Số $c(a - b)$ chia hết cho $m$. Vì $c$ và $m$ là số nguyên tố cùng nhau nên số $a - b$ chia hết cho $m$. Đó là lý do tại sao
$$a \equiv b(\text{mod } m).$$

Bài tập 15. Chứng minh tính chất 7.

Từ đó, trong bất kỳ biểu thức đại số nào thu được từ các số nguyên $a, b, c, \dots$, $z$ bằng cách sử dụng phép cộng, phép nhân và phép trừ, bạn có thể thay thế các số này bằng số dư của chúng khi chia cho $m$ mà không thay đổi phần dư mà biểu thức này mang lại khi chia cho $m$.

Bây giờ chúng ta hãy giải quyết bài toán sau.
Bài toán 3. Tìm số dư khi chia cho 3 số
$$N = (1^2 + 1)(2^2 + 1)(3^2 + 1)...(1000^2 + 1).$$

Lời giải. Từ nhận xét trên suy ra rằng
$$N \equiv (1^2 + 1)^{333} \cdot (2^2 + 1)^{333} \cdot (3^2 + 1)^{333} \equiv 2^{333} \cdot 2^{333} \cdot 1^{333} \equiv 2^{666} \equiv (2^2)^{333} \equiv 1^{333} \equiv 1.$$

Bài toán 4. Vì số $n$ tự nhiên nào mà số $8n + 3$ chia hết cho 13 (xem bài toán 1)?

Lời giải. Chúng ta hãy viết, sử dụng các tính chất so sánh, sự tương ứng số nguyên sau:
Đặt $8n + 3 \equiv 0(\text{mod } 13)$, sau đó
$$8n \equiv -3(\text{mod } 13),$$
$$8 \times 8n \equiv -24(\text{mod } 13),$$
$$-n \equiv -24 \equiv -11(\text{mod } 13).$$

$n \equiv 11(\text{mod } 13)$ đến từ đâu.

Cuối cùng, $8n + 3$ chia hết cho 13 khi và chỉ khi $n = 13k + 11$.

Bài tập 16. Tìm số dư khi chia số
a) $2^{1991} + 1$ vào 17;
b) $(3^{20} + 11)^{55}$ vào ngày 13.
17. Chứng minh rằng số
a) $2^{50} + 1$ chia hết cho 125;
b) $2^{48} - 1$ chia hết cho 105.
b) $2^{3^n} + 1$ chia hết cho $3^{n+1}$ và không chia hết cho $3^{n+2}$.
18. Tìm tất cả các số nguyên tố $p$ mà $20p^2 + 1$ cũng là số nguyên tố.
19. Chứng minh rằng số
a) $1^{1991} + 2^{1991} + \dots + 30^{1991}$ chia hết cho 31;
b) $1^m + 2^m + \dots + (n - 1)^m$ chia hết cho $n$ cho mọi $m$ và $n$ lẻ.
20. Với số tự nhiên nào $n$ thì số $20^4 + 16^4 - 3^4 - 1$ chia hết cho 323?
21. Chứng minh rằng số $5^{2n+1} + 3^{n+2} \cdot 2^{n-1}$ chia hết cho 19 với mọi số tự nhiên $n$.
22. Tại $n$ thì phân số sẽ hủy bỏ ở mức nào?
$$\frac{15n + 2}{14n + 3}?$$

Định lý phần dư Trung Hoa

Xét $m$ số hạng của cấp số cộng
$$a, a + d, \dots, a + (m - 1) \cdot d,$$ (*)
trong đó $a$ là số nguyên, $a$ nguyên tố cùng nhau với $m$. Những điều sau đây thường rất hữu ích

Định lý 1. Trong các số (*) có một số lẻ chia hết cho $m$.

Bằng chứng. Hiệu giữa số thứ $k$ và số thứ $l$ (*), bằng $d(k - l)$, không chia hết cho $m$. Ngược lại, hóa ra $k - l$ chia hết cho $m$, điều này là không thể, vì $|k - l| < m$.

Do đó, các số (*) là cặp không thể so sánh được theo modulo $m$ và do đó tạo ra sự chênh lệch về số dư khi chia cho $m$.

Vậy trong số (*) có

⟦folio 39⟧

---
running_head:
folio:
---

tất cả các lớp được đặt theo modulo $m$, tức là với mỗi phần dư 0, 1, 2, ..., $m-1$, chính xác một trong các số (*) có thể so sánh với nó theo modulo $m$.

Chúng ta đã chứng minh một phát biểu thậm chí còn mạnh hơn Định lý 1.
Bài tập
23. Tìm tất cả các bộ ba số nguyên tố có dạng $p, p+2, p+4$.
24. Tìm một cấp số cộng hữu hạn có chênh lệch độ dài tối đa là 6 và chứa các số nguyên tố.
25. Mười lăm số nguyên tố tạo thành một cấp số cộng có hiệu $d$.
Chứng minh rằng $d > 30000$.

Bây giờ chúng ta áp dụng Định lý 1 để chứng minh định lý số dư Trung Hoa. Định lý này đã được biết đến hơn 2000 năm trước ở Trung Quốc cổ đại.

Định lý 2. Giả sử dữ liệu $n$ là các số nguyên tố cùng nhau $m_1, m_2, ..., m_n$ và các số $r_1, r_2, ..., r_n$ sao cho $0 \leqslant r_i \leqslant m_i-1$ ($i=1, 2, ..., n$). Khi đó có một số $N$ khi chia cho $m_i$ thì có số dư $r_i$.

Nói cách khác, $N \equiv r_i(\text{mod } m_i)$ cho mọi $i=1, 2, ..., n$.

Bằng chứng. Chúng ta hãy áp dụng quy nạp theo $n$. Với $n=1$ phát biểu của định lý là hiển nhiên. Giả sử định lý đúng với $n=k$. Khi đó có một số $M$ sao cho $M \equiv r_i(\text{mod } m_i)$ cho $i=1, 2, ..., k$.

Hãy để $d=m_1m_2...m_{k-1}$.

Chúng ta hãy nhìn vào những con số
$M, M+d, M+2d, ..., M+(m_k-1)d$.

Bởi vì $d$ đối ứng chỉ với $m_k$, từ chứng minh Định lý 1 suy ra rằng trong số các số được viết có một số $N$, cho kết quả khi chia cho $m_k$ phần còn lại $r_k$. Đồng thời khi chia cho $m_1, m_2, ..., m_{k-1}$ con số $N$ đưa thức ăn thừa $r_1, r_2, ..., r_{k-1}$ tương ứng.

Định lý đã được chứng minh.
Và cuối cùng, một định lý nữa.
Định lý 3. Với mọi cặp số nguyên tố cùng nhau $m_1, m_2, ..., m_n$ và số dư $r_1, r_2, ..., r_n$ modulo $m_1, m_2, ..., m_n$ đều có $n$ số liên tiếp $a, a+1, ..., a+n-1$ sao cho $a \equiv r_1(\text{mod } m_1), a+1 \equiv r_2(\text{mod } m_2), ..., a+n-1 \equiv r_n(\text{mod } m_n)$.

Nói cách khác, đối với bất kỳ mô-đun nguyên tố cùng cặp theo cặp nào $m_1, m_2, ..., m_n$ đều có $n$ các số tự nhiên liên tiếp cho ra số dư có hướng tương ứng khi chia cho các số này.

Bằng chứng. Theo định lý phần dư Trung Hoa, tồn tại $a$ sao cho
$a \equiv r_1(\text{mod } m_1),$
$a \equiv r_2-1(\text{mod } m_2),$
$a \equiv r_n-n+1(\text{mod } m_n)$.

Nhưng khi đó các số $a, a+1, ..., a+n-1$ thỏa mãn điều kiện của định lý.

Bài tập
25. Chứng minh rằng a) trong số mười;
6) Trong 16 số tự nhiên liên tiếp bất kỳ đều có một số nguyên tố cùng nhau.
c) khẳng định bài toán đúng với 17 số tự nhiên liên tiếp bất kỳ.
26. Chứng minh rằng với mọi $n$ đều có $n$ số tự nhiên liên tiếp, mỗi số đều chia hết cho bình phương của một số nào đó.
27. Có thời điểm nào trong ngày mà kim phút và kim giây của một chiếc đồng hồ đang chạy đều đặn, nằm trên trục chung của đồng hồ, tạo thành các cặp góc $120^\circ$ không?
28. Tìm số tự nhiên nhỏ nhất mà khi chia cho 2, 3, 5, 7 thì có số dư 1, 2, 4, 6.
29. Tìm số nhỏ nhất $a$ sao cho $a+1$ chia hết cho 3, $a+2$ chia hết cho 5, $a+3$ chia hết cho 7, $a+4$ chia hết cho 11, $a+5$ chia hết cho 13.

Cách giải quyết so sánh

Nếu bạn còn nhớ, khi giải bài toán 4, chúng ta đã tìm thấy tất cả các số nguyên $n$ mà $8n+3$ chia hết cho 13.
Nói cách khác, chúng tôi quyết định so sánh
$8n+3 \equiv 0(\text{mod } 13)$.

Định lý chúng ta có thể giải bài toán này ở dạng tổng quát. Vì vậy, hãy để các số nguyên $a$ và $m$ là tích của nhau.
Hãy giải quyết sự so sánh
$ax \equiv b(\text{mod } m)$, trong đó $b$ là số bất kỳ.
Theo Định lý 1, tồn tại $k$ sao cho $ak \equiv 1(\text{mod } m)$.
Nhân vế trái và vế phải của phép so sánh này với $k$, ta được

(Về phần kết xem trang 49)

⟦folio 40⟧

---
running_head:
folio:
---

Tôi chấp nhận rằng trong Vũ trụ... có một cái khác đã được biết đến, sau đó nó mất đi quá nhiều chuyển động đến mức không thể, không thể, và do đó,

R. Descartes
