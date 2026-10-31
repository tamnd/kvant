---
id: 1976-5-mordkovich-smyishlyaev-ante-a80c75c7
issue: kvant_1976_5
year: 1976
number: "5"
title: Antje
authors:
  - Мордкович А. Г.
  - Смышляев В. К.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 45
page_last: 49
page_labels: 43, 44, 46, 47
tag: H4XM
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 7ad945051242ff52a97e29b973db45af479f268d881a71e87453977211d4ba18
prompt_sha256: draft-1
translated_from: content/ru/1976/05/articles/09_mordkovich-smyishlyaev-ante-a80c75c7.md
source_content_sha256: c98edfc659a69591a93b61a05ce7406ffc574a69c42c3ae09154164fe475eefe
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 43⟧

1. Sự định nghĩa

Trong nhiều bài toán đại số, lý thuyết số, phân tích toán học và lý thuyết xác suất, sự xuất hiện của một số nguyên không vượt quá một số cho trước (ví dụ, hãy nhớ việc xác định đặc tính của logarit thập phân). Số nguyên như vậy nhận được một tên đặc biệt: “phần nguyên của một số”.

Vậy phần nguyên của hệ là số nguyên lớn nhất $n$, không vượt quá $x$; phần nguyên của số $x$ được biểu thị bằng ký hiệu $[x]$ hoặc (ít phổ biến hơn) $E(x)$ (từ Entier tiếng Pháp (“anteche”) - “toàn bộ”). Ví dụ: $[2,3]=2$, $[-2,3]=-3$.

Nếu $n \leqslant x < n+1$ và $n$ là số nguyên thì $[x]=n$. Vì $[x] \leqslant x < [x]+1$, chúng ta có $0 \leqslant x-[x] < 1$. Số $\alpha=x-[x]$ được gọi là phần phân số của số $x$ và là viết tắt của $\{x\}$. Vì vậy, $0 \leqslant \{x\} < 1$. Rõ ràng là $x=[x]+\{x\}$.

Đồ thị của hàm $y=[x]$ được hiển thị trong Hình 1 và hàm $y=\{x\}$ được hiển thị trong Hình 2.

2. Một số tài sản

$1^\circ$. Nếu $p$ là số nguyên thì $[x+p]=[x]+p$.

$2^\circ$. Đối với mọi số thực $x$ và $y$: $[x+y] \geqslant [x]+[y]$.

Bằng chứng. Chúng tôi có $x=[x]+\alpha, 0 \leqslant \alpha < 1; y=[y]+\beta, 0 \leqslant \beta < 1$. Sau đó $x+y=[x]+\alpha+[y]+\beta=[x]+[y]+\gamma$, ở đâu $\gamma=\alpha+\beta$. Vì vậy, $0 \leqslant \gamma < 2$.

Nếu $0 \leqslant \gamma < 1$ thì $[x+y]=[x]+[y]$.

Nếu $1 \leqslant \gamma < 2$, tức là $\gamma=1+\gamma'$, trong đó $0 \leqslant \gamma' < 1$, thì $x+y=[x]+[y]+1+\gamma'$ và $[x+y]=[x]+[y]+1>[x]+[y]$.

Quét. Thuộc tính $2^\circ$ mở rộng đến bất kỳ số hạng hữu hạn nào: $[x_1+x_2+\ldots+x_n] \geqslant [x_1]+[x_2]+\ldots+[x_n]$.

Cơm. 1. Hình 2.

⟦folio 44⟧

3°. Nếu $[x] = [y]$ thì $|x - y| < 1$.
4°. Nếu $n$ là số tự nhiên thì $\left[\frac{x}{n}\right] = \left[\frac{x}{n}\right]$.

Bằng chứng. Hãy đặt $\left[\frac{x}{n}\right] = a$. Sau đó $a \leqslant \frac{[x]}{n} < a + 1$ hoặc $a \leqslant [x] < n (a + 1)$.

Vì các số $an$ và $n (a + 1)$ là số nguyên nên số $x$ cũng phải thỏa mãn bất đẳng thức $an \leqslant x < n (a + 1)$, do đó $a \leqslant \frac{x}{n} < a + 1$, tức là $\left[\frac{x}{n}\right] = a$.

3. Phản kháng trong phương trình
Lời giải phương trình có biến dưới dấu “phần nguyên” thường trùng với bất đẳng thức lời giải hoặc hệ bất đẳng thức.
Hãy xem xét một vài ví dụ.
Bài toán 1. Giải phương trình
$$\left[\frac{5 + 6x}{8}\right] = \frac{15x - 7}{5}.$$
Lời giải. Hãy đặt $\frac{15x - 7}{5} = t$. Sau đó $x = \frac{5t + 7}{15}$, và phương trình trở thành
$$\left[\frac{10t + 39}{40}\right] = t.$$
Từ định nghĩa của phần nguyên, suy ra $0 \leqslant \frac{10t + 39}{40} - t < 1$. Giải các bất đẳng thức này, ta tìm được
$$-\frac{1}{30} < t \leqslant 1, 3.$$

Cơm. 3.
Cơm. 4.

⟦folio 46⟧

Bài 5. Chứng minh số $C_{1976}^{976}$ chia hết cho $76^2$.

Lời giải. Vì $76 = 2^2 \times 19$, nên để chia hết cho $76^2$ điều cần và đủ là $C_{1976}^{976}$ chia hết cho $2^4$ và $19^2$.

Chúng tôi có $C_{1976}^{976} = \frac{1976!}{976! \cdot 1000!}$. Hãy cùng tìm xem số mũ $\alpha_1, \alpha_2, \alpha_3$ và $\beta_1, \beta_2, \beta_3$ bằng bao nhiêu, trong đó số 2 và 19 xuất hiện trong hệ số nguyên tố của các số 1976!, 976! và 1000!. chúng tôi có

$$\alpha_1 = \left[ \frac{1976}{2} \right] + \left[ \frac{1976}{2^2} \right] + \dots$$

$$\dots + \left[ \frac{1976}{2^{10}} \right] = 1969,$$

$$\alpha_2 = \left[ \frac{976}{2} \right] + \left[ \frac{976}{2^2} \right] + \dots$$

$$\dots + \left[ \frac{976}{2^{9}} \right] = 971,$$

$$\alpha_3 = \left[ \frac{1000}{2} \right] + \left[ \frac{1000}{2^2} \right] + \dots$$

$$\dots + \left[ \frac{1000}{2^9} \right] = 994$$

và $\alpha_1 - \alpha_2 - \alpha_3 = 4$, tức là $C_{1976}^{976}$ chia hết cho $2^4$.

Tương tự như vậy

$$\beta_1 = \left[ \frac{1976}{19} \right] + \left[ \frac{1976}{19^2} \right] = 109,$$

$$\beta_2 = \left[ \frac{976}{19} \right] + \left[ \frac{976}{19^2} \right] = 53,$$

$$\beta_3 = \left[ \frac{1000}{19} \right] + \left[ \frac{1000}{19^2} \right] = 54$$

và $\beta_1 - \beta_2 - \beta_3 = 2$, tức là $C_{1976}^{976}$ chia hết cho $19^2$.

Do đó, $C_{1976}^{976}$ chia hết cho $76^2$.

5. “Điểm mục tiêu”

Bằng điểm nguyên chúng ta sẽ hiểu điểm $(x, y)$ của mặt phẳng tọa độ có tọa độ nguyên $x$ và $y$. Chúng ta hỏi làm thế nào để đếm số điểm nguyên nằm trong một hình phẳng cho trước?

Bài tập 6. Có bao nhiêu thùy nguyên nằm ở các cạnh và bên trong tam giác tạo thành bởi đường thẳng $y = \frac{2}{3} x - \frac{1}{2}$, $x = 10$ và trục x (Hình 5)?

Lời giải. Chúng ta hãy tìm các giá trị của hàm $y = \frac{2}{3} x - \frac{1}{2}$ cho số nguyên $x = 1, 2, \dots, 10$ (lưu ý rằng $y = 0$ cho $x = \frac{3}{4}$); chúng ta nhận được tọa độ $\frac{1}{6}, \frac{5}{6}, \frac{3}{2}, \frac{13}{6}, \frac{17}{6}, \frac{7}{2}, \frac{25}{6}, \frac{29}{6}, \frac{11}{2}$ và $\frac{37}{6}$. Dễ dàng nói rằng tổng số điểm nguyên nằm trong một tam giác đã cho (kể cả trên biên) bằng tổng các phần nguyên của các tọa độ này của mặt phẳng các điểm nằm trên trục hoành:

$$\left[ \frac{1}{6} \right] + \left[ \frac{5}{6} \right] + \left[ \frac{3}{2} \right] + \left[ \frac{13}{6} \right] + \left[ \frac{17}{6} \right] + \left[ \frac{7}{2} \right] + \left[ \frac{25}{6} \right] + \left[ \frac{29}{6} \right] + \left[ \frac{11}{2} \right] + \left[ \frac{37}{6} \right] + 10 = 1 + 2 + 2 + 3 + 4 + 4 + 5 + 6 + 10 = 37.$$

Đáp số: 37 chấm tròn.

Lưu ý rằng bên trong tam giác này chỉ có 37-10-6=21 điểm nguyên.

Hóa ra các điểm nguyên có thể hữu ích trong việc chứng minh các điểm hành động!

⟦folio 47⟧

Nhiệm vụ 7. Chứng minh khả năng
chất lượng

$$\left[ \frac{q}{p} \right] + \left[ \frac{2q}{p} \right] + \left[ \frac{3q}{p} \right] + \dots$$

$$\dots + \left[ \frac{(p-1)q}{p} \right] = \frac{(p-1)(q-1)}{2}$$

(p và q là các số tự nhiên nguyên tố cùng nhau).

Lời giải. Chúng ta hãy nhìn thẳng vào
một hình vuông có các đỉnh $O = (0; 0)$, $A = (p; 0)$, $B = (p; q)$, $C = (0; q)$ (Hình 6). Đánh dấu tất cả các điểm nguyên $(x, y)$ bên trong hình chữ nhật: $1 \leqslant x \leqslant p-1$, $1 \leqslant y \leqslant q-1$ (các chấm màu đỏ trong hình). Số điểm này bằng tích $(p-1)(q-1)$.

Hãy vẽ đường chéo $OB$ của hình chữ nhật của chúng ta; phương trình của nó là $y = \frac{q}{p} x$. Vì $p$ và $q$ là nguyên tố cùng nhau và $x = 1$, ..., $p-1$, nên các số có dạng $\frac{q}{p} x$ không phải là số nguyên, tức là không có điểm nguyên trên đường chéo $OB$, và do đó trong tam giác nằm dưới đường chéo $OB$ sẽ có $\frac{(p-1)(q-1)}{2}$ màu đỏ (toàn bộ) dấu chấm.

Mặt khác, sử dụng phương pháp mô tả ở nhiệm vụ 6, chúng ta thấy rằng số điểm này bằng tổng $$\left[ \frac{q \cdot 1}{p} \right] + \left[ \frac{q \cdot (p-1)}{p} \right],$$ và do đó, đẳng thức phải được chứng minh.

Cơm. 6.

Bài tập

1. Xây dựng đồ thị của các hàm $y = [-x]$, $y = [2x]$, $y = [\sin x]$.
2. Chứng minh điểm hành động:
a) $$\left[ \frac{n}{k} \right] + \left[ \frac{n+1}{k} \right] + \left[ \frac{n+2}{k} \right] + \dots$$
$$\dots + \left[ \frac{n+k-1}{k} \right] = n,$$
trong đó $n$ và $k$ là số tự nhiên.
b) $(n+1)(n+2)(n+3) \dots (2n-1)2n = 2^n \cdot (2n-1)!!$.
($S!!$ biểu thị tích của các số tự nhiên từ 1 đến $S$ có cùng chẵn lẻ với $S$: ví dụ: $8!! = 2 \cdot 4 \cdot 6 \cdot 8; 9!! = 1 \cdot 3 \cdot 5 \cdot 7 \cdot 9$.)
3. Đặt $a, b, \dots, l$ là số tự nhiên, $a+b+\dots+l=n$. Chứng minh phân số $$\frac{n!}{a!b! \dots l!}$$ là số nguyên.
4. Chứng minh rằng nếu $[nx] + [ny] = [n(x+y)]$ với mọi $n$ tự nhiên thì $x$ hoặc $y$ là số nguyên.
5. Với số mũ nào thì số nguyên tố $p$ tham gia khai triển số đó
a) $(2n)!!;$ 6) $(2n+1)!!$.
6. Giải các phương trình:
a) $$\left[ \frac{8x+19}{7} \right] = \frac{16(x+1)}{11};$$
b) $$\left[ \frac{x^2-2}{3} \right] = [x];$$
b) $x^4 - [x+1] = 2$.
7. Người đi bộ đi với tốc độ 5 km/h, cứ 4 km lại dừng lại ở những khoảng cách riêng biệt. Thời gian của mỗi điểm dừng, ngoại trừ điểm dừng thứ tư, là 10 phút và thời gian của điểm dừng thứ tư là 1 giờ. Người đi bộ đó đã đi được bao xa nếu khởi hành lúc 4 giờ sáng và đến nơi vào buổi trưa?
8. Có bao nhiêu điểm nguyên trong hình thang cong $a \leqslant x \leqslant b$, $0 \leqslant y \leqslant f(x)$, trong đó $a$ và $b$ là các số tự nhiên, $a = f(x)$ là hàm liên tục và dương trên đoạn $[a, b]$ (các điểm nguyên nằm trên biên của hình thang cũng được tính)?
9. Có bao nhiêu điểm nguyên trong đường tròn bán kính 6,5 có tâm là gốc tọa độ?
10. Có 500 quả bóng trong nước tiểu, được tạo ra từ 1 đến 500. Xác suất để một quả bóng được rút ngẫu nhiên sẽ có số là bội số của bất kỳ số nào trong số 10, 14, 21 là bao nhiêu?
