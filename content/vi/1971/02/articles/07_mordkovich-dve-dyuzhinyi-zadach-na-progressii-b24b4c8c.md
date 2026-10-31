---
id: 1971-2-mordkovich-dve-dyuzhinyi-zadach-na-progressii-b24b4c8c
issue: kvant_1971_2
year: 1971
number: "2"
title: Hai chục bài toán về cấp số cộng და cấp số nhân
authors:
  - Мордкович А. Г.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 39
page_last: 43
page_labels: 37-41
tag: ZWRR
lang: vi
source: kvant_digital
extraction: vision
content_sha256: a665b5fc792f4bd75d798d6dbc757aa05b77a28f475d5b05500047d306a470b0
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1971/02/articles/07_mordkovich-dve-dyuzhinyi-zadach-na-progressii-b24b4c8c.md
source_content_sha256: 149a3527e7b227745e668458f874933447a33a3945ff287d248e65fd922435f5
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦folio 37⟧

HAI CHỤC
BÀI TOÁN VỀ CẤP SỐ

Để giải thành công các bài toán về cấp số cần biết định nghĩa của cấp số cộng, cấp số nhân và cấp số nhân giảm vô hạn, công thức số hạng tổng quát của mỗi cấp số này, công thức tổng $n$ số hạng của cấp số, cũng như định nghĩa và công thức tổng các số hạng của cấp số nhân giảm vô hạn. Ngoài ra, trong các bài toán về cấp số rất thường phải sử dụng các tính chất đặc trưng của cấp số. Kinh nghiệm thi tuyển sinh cho thấy rằng nếu với các công thức số hạng thứ $n$ và tổng $n$ số hạng của cấp số tình hình tương đối tốt, thì không thể nói như vậy về các tính chất đặc trưng. Vì vậy trước hết chúng ta sẽ xét các tính chất này.

Các tính chất đặc trưng của cấp số cộng

Dãy $a_1, a_2, \dots, a_n$, ... là cấp số cộng khi và chỉ khi mỗi số hạng của nó, trừ số hạng đầu tiên (và số hạng cuối cùng, trong trường hợp dãy hữu hạn), bằng trung bình cộng của hai số hạng kề nó.

Chứng minh. Cho dãy $a_1, a_2, \dots, a_n$, ... Giả sử nó là một cấp số cộng. Chứng minh rằng $a_{k+1} = \frac{a_k + a_{k+2}}{2}$ ($k = 1, 2, 3, \dots$).

Thật vậy, $a_{k+1} - a_k = a_{k+2} - a_{k+1}$, suy ra $a_{k+1} = \frac{a_k + a_{k+2}}{2}$.

Bây giờ giả sử $a_{k+1} = \frac{a_k + a_{k+2}}{2}$. Khi đó $a_{k+1} - a_k = a_{k+2} - a_{k+1}$, tức là hiệu giữa số hạng sau và số hạng trước của dãy là không đổi đối với dãy đã cho, và điều đó có nghĩa là $a_1, a_2, \dots, a_n$, ... — một cấp số cộng.

Các tính chất đặc trưng của cấp số nhân

Dãy $b_1, b_2, \dots, b_n$, ... là cấp số nhân khi và chỉ khi mỗi số hạng của nó, trừ số hạng đầu tiên (và số hạng cuối cùng, trong trường hợp dãy hữu hạn), bằng tích của các số hạng kề nó (tức là $b_2^{k+1} = b_k \cdot b_{k+2}$).

Chứng minh. Giả sử dãy $b_1, b_2, \dots, b_n$, ... là một cấp số nhân. Khi đó $\frac{b_{k+1}}{b_k} = \frac{b_{k+2}}{b_{k+1}}$, suy ra $b_2^{k+1} = b_k \cdot b_{k+2}$, điều phải chứng minh.

Ngược lại, giả sử $b_2^{k+1} = b_k \cdot b_{k+2}$. Khi đó $\frac{b_{k+1}}{b_k} = \frac{b_{k+2}}{b_{k+1}}$, tức là tỉ số của các số hạng của dãy với số hạng đứng trước là không đổi đối với dãy đã cho, và điều đó có nghĩa là $b_1, b_2, \dots, b_n$, ... — một cấp số nhân.

⟦folio 38⟧

Trong bài viết này, người đọc sẽ tìm thấy 24 bài toán mà khi giải sử dụng tất cả các tính chất của cấp số. Một nửa số bài toán được đưa ra kèm lời giải, một nửa để người đọc tự làm. Trong toàn bài viết dùng các ký hiệu sau (nếu không có ghi chú nào): $a_1, a_2, \dots, a_n, \dots$ — cấp số cộng, $d$ — công sai; $b_1, b_2, \dots, b_n, \dots$ — cấp số nhân, $q$ — công bội; $S_n$ — tổng của $n$ số hạng của cấp số; $n, k, m, p$ — các số tự nhiên.

Cấp số cộng

Bài 1. Chứng minh rằng $\frac{1}{a_1 a_2} + \frac{1}{a_2 a_3} + \dots + \frac{1}{a_n a_{n+1}} = \frac{n}{a_1 a_{n+1}}$.

Lời giải. $\frac{1}{a_1 a_2} = \frac{d}{a_1 a_2 d} = \frac{1}{d} \frac{a_2 - a_1}{a_1 a_2} = \frac{1}{d} \left( \frac{1}{a_1} - \frac{1}{a_2} \right)$. Tương tự

$$\frac{1}{a_2 a_3} = \frac{1}{d} \left( \frac{1}{a_2} - \frac{1}{a_3} \right), \dots, \frac{1}{a_n a_{n+1}} = \frac{1}{d} \left( \frac{1}{a_n} - \frac{1}{a_{n+1}} \right).$$

Do đó

$$\frac{1}{a_1 a_2} + \frac{1}{a_2 a_3} + \dots + \frac{1}{a_n a_{n+1}} = \frac{1}{d} \left( \frac{1}{a_1} - \frac{1}{a_2} \right) +$$

$$+ \frac{1}{d} \left( \frac{1}{a_2} - \frac{1}{a_3} \right) + \dots + \frac{1}{d} \left( \frac{1}{a_n} - \frac{1}{a_{n+1}} \right) = \frac{1}{d} \left( \frac{1}{a_1} - \frac{1}{a_{n+1}} \right) =$$

$$= \frac{1}{d} \frac{a_{n+1} - a_1}{a_1 a_{n+1}} = \frac{1}{d} \frac{a_1 + dn - a_1}{a_1 a_{n+1}} = \frac{n}{a_1 a_{n+1}}.$$

Bài tập 2. Dãy $u_1, u_2, \dots, u_n, \dots$ có tính chất rằng tổng $S_n$ của $n$ số hạng đầu của nó bằng $2n^2 + 3n$. Chứng minh rằng dãy này là một cấp số cộng.

Lời giải. Sử dụng tính chất đặc trưng của cấp số cộng, ta kết luận rằng chỉ cần chứng minh các hệ thức sau: $2u_{k+1} = u_k + u_{k+2}$, trong đó $k=1, 2, 3, \dots$.

Ta nhận thấy rằng $u_{k+1} = S_{k+1} - S_k$. Thật vậy, $S_{k+1} - S_k = (u_1 + u_2 + \dots + u_k + u_{k+1}) - (u_1 + u_2 + \dots + u_k) = u_{k+1}$. Vậy,

$$u_{k+1} = [2(k+1)^2 + 3(k+1)] - (2k^2 + 3k) = 4k + 5.$$

Tương tự $u_k = S_k - S_{k-1}$ (đặc biệt, đặt $S_0 = 0$), từ đó $u_k = (2k^2 + 3k) - [2(k-1)^2 + 3(k-1)] = 4k + 1$ và, cuối cùng, $u_{k+2} = S_{k+2} - S_{k+1} = 4k + 9$. Vì đối với các số $u_k = 4k + 1$, $u_{k+1} = 4k + 5$, $u_{k+2} = 4k + 9$ tương ứng có $2u_{k+1} = u_k + u_{k+2}$, nên việc chứng minh rằng $u_1, u_2, \dots, u_n, \dots$ là một cấp số cộng đã hoàn tất.

Bài tập 3. Chứng minh rằng đối với một cấp số cộng, hệ thức $\frac{S_n}{n} (m - p) + \frac{S_m}{m} (p - n) + \frac{S_p}{p} (n - m) = 0$ là đúng.

Lời giải. Dùng cho $S_n$ công thức đã biết $S_n = \frac{a_1 + a_n}{2} n$ và các công thức tương tự cho $S_m$ và $S_p$, ta đưa vế trái của đẳng thức cần chứng minh về dạng

$$\frac{a_1 + a_n}{2} (m - p) + \frac{a_1 + a_m}{2} (p - n) + \frac{a_1 + a_p}{2} (n - m).$$

⟦folio 39⟧

Áp dụng cho $a_n$ công thức số hạng tổng quát của cấp số cộng $a_n = a_1 + d(n-1)$ và làm tương tự với $a_m, a_p$, ta được

$$\frac{1}{2} \left\{ [2a_1 + d(n-1)] (m-p) + [2a_1 + d(m-1)] (p-n) + [2a_1 + d(p-1)] (n-m) \right\}$$

và tiếp theo

$$\frac{1}{2} \left\{ 2a_1 [(m-p) + (p-n) + (n-m)] + d [(n-1)(m-p) + (m-1)(p-n) + (p-1)(n-m)] \right\}.$$

Vì các tổng trong cả hai ngoặc vuông đều bằng 0, nên toàn bộ biểu thức cũng bằng 0, điều phải chứng minh.

Bài tập 4. Tìm một số có ba chữ số, chia hết cho 45 và các chữ số của nó lập thành một cấp số cộng.

Lời giải e. Gọi $x$ là chữ số hàng trăm, $y$ là chữ số hàng chục và $z$ là chữ số hàng đơn vị của số cần tìm. Vì theo điều kiện $x, y, z$ là một cấp số cộng, nên

$$2y = x + z. \tag{1}$$

Số cần tìm có dạng $100x + 10y + z$. Vì theo điều kiện nó chia hết cho 45, nên

$$100x + 10y + z = 45p. \tag{2}$$

Vậy số cần tìm được xác định bởi các điều kiện (1) và (2).

Với chữ số hàng đơn vị có hai khả năng: hoặc $z=0$, hoặc $z=5$ (điều này suy ra từ tính chia hết của số cần tìm cho 5). Xét trường hợp $z=0$. Khi đó từ (1) suy ra $x=2y$, còn từ (2) — $100x + 10y = 45p$, hay $20x + 2y = 9p$, $20x + x = 9p$ hay $7x = 3p$. Điều này có nghĩa là $x$ chia hết cho 3. Vì ngoài ra $x$ — là số chẵn ($x=2y$), nên kết luận rằng đối với $x$ chỉ có một khả năng: $x=6$. Khi đó $y=3$, và số cần tìm bằng 630.

Bây giờ xét trường hợp thứ hai: $z=5$. Trong trường hợp này, các điều kiện (1) và (2) có dạng tương ứng:

$$2y = x + 5; 100x + 10y + 5 = 45p.$$

Đẳng thức cuối cùng được biến đổi thành $20x + 2y + 1 = 9p$ và далее, có xét đến đẳng thức $2y=x+5$, ta được $21x+6=9p$, hay $7x+2=3p$. Đẳng thức cuối cùng có thể xảy ra khi $x=1, 4, 7$. Nhưng vì $x+5$ là số chẵn ($x+5=2y$), nên đối với $x$ chỉ còn hai khả năng: $x=1, x=7$. Trong trường hợp thứ nhất $y=3$, trong trường hợp thứ hai $y=6$. Số cần tìm tương ứng trong trường hợp thứ nhất bằng 135, trong trường hợp thứ hai bằng 765. Vậy, điều kiện bài toán được thỏa mãn bởi ba số: 135, 630, 765.

**Cấp số nhân**

Bài tập 5. Tính tổng $2 + 22 + 222 + \ldots + 222\ldots 2$

Lời giải e. $2 + 22 + 222 + \ldots + 222\ldots 2 = 2[1 + (1+10) + (1+10+10^2) + \ldots + (1+10+10^2 + \ldots + 10^{n-1})] = 2[S_1 + S_2 + S_3 + \ldots + S_n]$, trong đó $S_k$ là tổng của $k$ số hạng của cấp số nhân 1, 10, $10^2$, $10^3$, ... ($k=1, 2, \ldots, n$). Áp dụng công thức $S_k = \frac{b_1(q^k - 1)}{q-1}$ tính tổng các số hạng của cấp số nhân, ta được

⟦folio 40⟧

$$2(S_1 + S_2 + S_3 + \ldots + S_n) = 2\left(\frac{10 - 1}{9} + \frac{10^2 - 1}{9} + \ldots + \frac{10^n - 1}{9}\right) = \frac{2}{9}[10(1 + 10 + 10^2 + \ldots + 10^{n-1}) - n] = \frac{2}{9}\left[\frac{10(10^n - 1)}{9} - n\right] = \frac{2(10^{n+1} - 10 - 9n)}{81}.$$

Bài tập 6. Chứng minh rằng dãy $u_1, u_2, u_3$, trong đó
$$u_1 = 9, \quad u_2 = 3^{\frac{1}{2}} \text{tg} x, \quad u_3 = \left(\frac{1}{9}\right)^{\cos 2x},$$
là một cấp số nhân khi và chỉ khi
$$x = \pi l, \quad x = \frac{\pi}{12} + \pi l, \quad x = \frac{5\pi}{12} + \pi l \quad (l = 0, \pm 1, \pm 2, \ldots).$$

Lời giải. Dựa vào tính chất đặc trưng của cấp số nhân, kết luận rằng bài toán quy về việc giải phương trình
$$9^{\frac{1}{2}} \text{tg} x = 9\left(\frac{1}{9}\right)^{\cos 2x}$$

Thực hiện các biến đổi liên tiếp của phương trình này:
$$\frac{1}{2} \text{tg} x = 1 - \cos 2x,$$
$$\text{tg} x = 4 \sin^2 x, \quad \sin x (2 \sin 2x - 1) = 0 \quad (\cos x \neq 0).$$
Như vậy, phải thỏa mãn một trong hai phương trình:
$$\sin x = 0, \quad \sin 2x = \frac{1}{2},$$

từ đó
$$x = \pi l, \quad x = \frac{\pi}{12} + \pi l, \quad x = \frac{5\pi}{12} + \pi l.$$

Các dãy nhận được, và chỉ chúng, thỏa mãn phương trình (3). Do đó, với các giá trị $x$ nhận được, và chỉ với chúng, $u_1, u_2, u_3$ là một cấp số nhân.

Bài toán 7. Các số 10, 11, 12 có thể là các số hạng của cùng một cấp số nhân không?

Lời giải. Giả sử các số đã cho là các số hạng của một cấp số nhân có số hạng đầu $b_1$ và công bội $q$. Khi đó $10 = b_1 q^n, 11 = b_1 q^m, 12 = b_1 q^p$. Từ các hệ thức này ta được
$$\frac{11}{10} = q^{m-n}, \quad \frac{12}{10} = q^{p-n}$$

và tiếp theo
$$\left(\frac{11}{10}\right)^{p-n} = \left(\frac{12}{10}\right)^{m-n},$$
$$\frac{11^{p-n}}{12^{m-n}} = 10^{p-m}.$$

Đẳng thức cuối cùng không thể đúng với bất kỳ $n, m, p$ tự nhiên đôi một khác nhau nào. Điều đó có nghĩa là các số 10, 11, 12 không thể là các số hạng của cùng một cấp số nhân.

⟦folio 41⟧

Bài toán 8. Tổng các số hạng của một cấp số nhân vô hạn giảm bằng 9, còn tổng các bình phương các số hạng của nó bằng 40,5. Tìm số hạng đầu và công bội của cấp số nhân.

Lời giải. Dùng công thức $S = \frac{b_1}{1-q}$ tính tổng các số hạng của một cấp số nhân vô hạn giảm, ta được $\frac{b_1}{1-q} = 9$.

Xét dãy $b_1^2, b_2^2, \ldots, b_n^2, \ldots$. Ta thấy rằng đây là một cấp số nhân giảm vô hạn với số hạng đầu $b_1^2$ và công bội $q^2$. Khi đó tổng các số hạng của cấp số nhân này được xác định bởi công thức $\frac{b_1^2}{1-q^2}$ và bằng 40,5.

Cuối cùng, bài toán quy về giải hệ

$$\frac{b_1}{1-q} = 9, \quad \frac{b_1^2}{1-q^2} = 40,5.$$

Từ hệ này ta được: $b_1 = 6, \quad q = \frac{1}{3}$.

Các bài toán hỗn hợp về cấp số

Bài tập 9. Tìm bốn số, biết rằng ba số đầu lập thành một cấp số nhân, ba số cuối lập thành một cấp số cộng, tổng các số ở hai đầu bằng 21, tổng các số ở giữa bằng 18.

Lời giải. Gọi $a, b, c, d$ là các số cần tìm; $a, b, c$ là một cấp số nhân, do đó $b^2=ac$; $b, c, d$ là một cấp số cộng, do đó $2c=b+d$. Cuối cùng ta đi đến hệ phương trình sau:

$$\begin{cases}
b^2=ac, \\
2c=b+d, \\
a+d=21, \\
b+c=18.
\end{cases}$$

Giải hệ này, ta được $a=3, b=6, c=12, d=18$ hoặc

$$a = \frac{75}{4}, \quad b = \frac{45}{4}, \quad c = \frac{27}{4}, \quad d = \frac{9}{4}.$$

Bài tập 10. Ba số lập thành một cấp số nhân. Nếu tăng số thứ hai thêm 2, thì các số nhận được lập thành một cấp số cộng. Nếu sau đó tăng số thứ ba thêm 9, thì lại nhận được một cấp số nhân. Tìm các số đó.

Lời giải. Viết lại các điều kiện của bài toán như sau:

$$b_1, b_2, b_3 \text{ — cấp số nhân;}$$
$$b_1, b_2+2, b_3 \text{ — cấp số cộng;}$$
$$b_1, b_2+2, b_3+9 \text{ — cấp số nhân.}$$

Sử dụng các tính chất đặc trưng của cấp số, ta được

$$\begin{cases}
2(b_2+2) = b_1+b_3, \\
(b_2+2)^2 = b_1(b_3+9).
\end{cases}$$
