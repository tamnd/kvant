---
id: 1971-10-shabunin-sistemyi-algebraicheskih-uravneniy-6515cd2d
issue: kvant_1971_10
year: 1971
number: "10"
title: Hệ phương trình đại số
authors:
  - Шабунин М. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 47
page_last: 50
page_labels: 45-48
tag: ITP5
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 0dfc7a9768b874778db58140754c27cafe3033fa0fdcfcd9ca1edd2a5a61955d
prompt_sha256: draft-1
translated_from: content/ru/1971/10/articles/12_shabunin-sistemyi-algebraicheskih-uravneniy-6515cd2d.md
source_content_sha256: a2df8d1a6b8629ccd1695d6a446453c3d349e9a29f840cc1c91cbb177d71b323
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 45⟧

Hệ phương trình đại số

M. I. Shabunin

Trong kỳ thi tuyển sinh đại học, lần đầu tiên hệ phương trình đại số được đề xuất; đặc biệt, những hệ thống như vậy phát sinh trong các vấn đề về soạn phương trình. Kinh nghiệm thi cử cho thấy nhiều học sinh khi vào giải hệ phương trình không đạt yêu cầu.

Thực tế là học sinh thường hiểu câu hỏi tìm hệ lời giải đơn giản là việc thực hiện chính thức một loạt các phép biến đổi đại số “thông thường”. Cần lưu ý rằng một số ví dụ chuyển đổi có thể dẫn đến sự xuất hiện của lời giải không liên quan hoặc làm mất lời giải của hệ thống ban đầu.

Nếu không có sự biện minh thích hợp lời giải của hệ thống, các phương trình logic sẽ không hoàn chỉnh. Đặc biệt, chúng tôi có thể không thay thế tổn thất của một số lời giải. Thật không may, hệ thống lời giải có ​​cơ sở vững chắc, được trình bày tốt là cực kỳ hiếm trong công việc của người nộp đơn.

Trình bày chi tiết tất cả các vấn đề quan trọng liên quan đến hệ phương trình sẽ cần nhiều chỗ*). Vì vậy, chúng tôi sẽ giới hạn ở việc trình bày các nguyên tắc lý thuyết cơ bản liên quan đến lời giải ba phương trình đại số chưa biết, sau đó xem xét một vài ví dụ.

Đầu tiên, chúng ta hãy nhớ lại một số định nghĩa.

Một hệ ba phương trình ẩn có thể được viết dưới dạng

$$\begin{cases}
f_1(x, y, z) = 0, \\
f_2(x, y, z) = 0, \\
f_3(x, y, z) = 0
\end{cases}$$

hoặc, bỏ đi những phần chưa biết để cho ngắn gọn, ở dạng

$$\begin{cases}
f_1 = 0, \\
f_2 = 0, \\
f_3 = 0.
\end{cases}$$

Chúng ta sẽ chỉ xem xét các hệ thống đại số, nghĩa là, chẳng hạn

*) Người đọc có thể được khuyến khích nghiên cứu, chẳng hạn như cuốn sách của V. G. Boltyansky, Yu. V. Sidorov và M. I. Shabunin “Các bài giảng và bài toán về toán tiểu học”, M., “Nauka”, 1971.

các hệ thống trong đó vế trái của mỗi phương trình của hệ thống là đa thức chưa biết.

Nghiệm của hệ (1) là bộ ba số $(x_0, y_0, z_0)$, khi thay số tương ứng vào $x, y, z$ thì mỗi phương trình của hệ (1) trở thành một đẳng thức số thực. Giải hệ thống giới thiệu tìm hết lời giải.

Hai hệ phương trình

$$\begin{cases}
f_1 = 0, \\
f_2 = 0, \\
f_3 = 0.
\end{cases}$$

Và

$$\begin{cases}
g_1 = 0, \\
g_2 = 0, \\
g_3 = 0.
\end{cases}$$

⟦folio 46⟧

được gọi là *tương đương* (tương đương) nếu chúng có cùng lời giải, nghĩa là nếu lời giải của hệ (2) là lời giải của hệ (3) và ngược lại, nếu lời giải của hệ (3) là lời giải của hệ (2). Để biểu thị sự tương đương của hệ (2) và (3), ký hiệu “(2) ⟨=⟩ (3)” được sử dụng.

Lưu ý rằng nếu chúng tôi tìm thấy tất cả các hệ thống lời giải (3) tương đương với hệ thống (2), thì do đó chúng tôi đã tìm thấy tất cả các hệ thống lời giải (2). Trong trường hợp này không cần kiểm tra, tức là không cần thay các giá trị ẩn tìm được tại lời giải của hệ (3) vào hệ ban đầu (2).

phương trình
$$F(x, y, z) = 0$$
(4)
Chúng ta hãy gọi nó là *hệ quả* của hệ (1) nếu mỗi lời giải của hệ (1) thỏa mãn phương trình (4). Mục “(1) ⟨=⟩ (4)” sẽ có nghĩa là phương trình (4) là hệ quả của hệ (1).

Chúng ta sẽ nói rằng hệ thống (1) tương đương với *tổng thể* của hệ thống
$$\begin{cases} F_1 = 0, \\ F_2 = 0, \\ F_3 = 0 \end{cases}$$
Và
$$\begin{cases} G_1 = 0, \\ G_2 = 0, \\ G_3 = 0, \end{cases}$$
nếu các điều kiện sau được đáp ứng:
a) mọi lời giải của hệ (1) là lời giải của ít nhất một trong các hệ (5), (6);
b) mọi lời giải của hệ (5), (6) là một lời giải của hệ (1).

 Ký hiệu “(1) ⟨=⟩ [(5) ∨ (6)]” sẽ có nghĩa là hệ thống (1) tương đương với *bộ* của hệ thống (5) và (6).

Nếu hệ (1) tương đương với *tổng* của hệ (5) và (6), thì có thể giải hệ (5), (6) và kết hợp các tập lời giải của các hệ này; đây là sự thống nhất và dact của tất cả các hệ thống lời giải (1) (*hệ thống tổng thể* xuất hiện khi xem xét các trường hợp khác nhau thuộc loại $x > 0$, $x < 0$, $x = 0$).

Bây giờ chúng ta hãy xây dựng một số tính chất thường được sử dụng nhất trong hệ phương trình lời giải. Chúng tôi sẽ không chứng minh những tính chất này; Sử dụng các định nghĩa đã cho, người đọc có thể dễ dàng tự mình xác minh sự biện minh cần thiết.

I. Giả sử một trong các phương trình của hệ (1), để xác định phương trình thứ nhất, “chia” thành hai phương trình, ví dụ biểu diễn dưới dạng
$$g_1(x, y, z) g_2(x, y, z) = 0,$$
trong đó $g_1$ và $g_2$ là đa thức trong $x, y, z$. Khi đó hệ (1) tương đương với tổ hợp của hai hệ sau:
$$\begin{cases} g_1 = 0, \\ f_2 = 0, \\ f_3 = 0 \end{cases} \quad \text{и} \quad \begin{cases} g_2 = 0, \\ f_2 = 0, \\ f_3 = 0. \end{cases}$$

Tuyên bố này có thể dễ dàng được khái quát hóa cho trường hợp hai hoặc ba phương trình của hệ (1) “chia” thành nhiều phương trình.

II. Nếu phương trình (4) là hệ quả của hệ (1) thì khi nối phương trình (4) với hệ (1), ta thu được hệ {{1}, {4}} gồm bốn phương trình, tương đương với phương trình ban đầu.

III. Giả sử phương trình (4), hệ quả của hệ (1), “phân tích” thành hai phương trình:
$$F_1(x, y, z) \cdot F_2(x, y, z) = 0,$$
trong đó $F_1$, $F_2$ là các đa thức trong $x, y, z$. Khi đó hệ (1) tương đương với tổ hợp của hai hệ sau:
$$\begin{cases} f_1 = 0, \\ f_2 = 0, \\ f_3 = 0, \\ F_1 = 0 \end{cases} \quad \text{и} \quad \begin{cases} f_1 = 0, \\ f_2 = 0, \\ f_3 = 0, \\ F_2 = 0. \end{cases}$$

IV. Hệ phương trình (1) tương đương với mỗi hệ sau:
$$\begin{cases} f_1 - f_2 = 0, \\ f_2 - f_3 = 0, \\ f_3 - f_4 = 0; \end{cases} \quad \text{и} \quad \begin{cases} f_1 - f_2 = 0, \\ f_2 - f_3 = 0, \\ f_3 - f_4 = 0; \end{cases}$$

$$\begin{cases} f_1 + f_2 = 0, \\ f_1 + f_3 = 0, \\ f_2 + f_3 = 0 \end{cases}$$

(khả năng cộng vào một phương trình của hệ một số khác nhân với tích).

V. Giả sử một trong các phương trình của hệ (1), chẳng hạn như phương trình đầu tiên $f_1(x, y, z) = 0$, tương đương với phương trình $x = \varphi(y, z)$ - một đa thức trong $y$ và $z$. Khi đó hệ (1) tương đương với hệ
$$\begin{cases} x = \varphi(y, z), \\ f_2[\varphi(y, z), y, z] = 0, \\ f_3[\varphi(y, z), y, z] = 0. \end{cases}$$

⟦folio 47⟧

Tuyên bố này làm cơ sở cho phương pháp loại bỏ những ẩn số: hệ thống (1) được điều chỉnh cho phù hợp với hệ thống điều khiển
$$\begin{cases} f_2[\varphi(y, z), y, z] = 0, \\ f_3[\varphi(y, z), y, z] = 0 \end{cases}$$
với hai ẩn số $y, z$.

Trước khi chuyển sang phân tích các ví dụ, chúng ta sẽ thực hiện một sự thay thế. Khi xem xét một hệ thống cụ thể, không phải lúc nào cũng có thể nhận thấy ngay sự kết hợp của dữ liệu điều khiển đóng vai trò là “chìa khóa” cho lời giải hoặc tìm ra phương pháp chuyển đổi cho phép đơn giản hóa đầy đủ. Tất nhiên, không thể đưa ra lời giải tổng quát để tìm hệ lời giải. Chỉ có kinh nghiệm đủ phong phú mới có thể giúp “nhìn thấy” những đặc điểm đó của hệ thống được đề xuất để có thể giảm nó thành một hệ thống khác có thể dễ dàng giải quyết.

Ví dụ 1. Giải hệ điều khiển
$$\begin{cases} xy + z^2 = 2, \\ yz + x^2 = 2, \\ xz + y^2 = 2. \end{cases}$$

Lời giải. Trừ điều khiển thứ nhất khỏi điều khiển thứ hai của hệ thống này và tính hiệu của vế trái thành thừa số, chúng ta thu được
$$(x - z)(x - y + z) = 0.$$
Tương tự, trừ điều khiển thứ hai khỏi điều khiển thứ ba của hệ (7), ta tìm được
$$(y - x)(x + y - z) = 0.$$
Do tính chất IV nên hệ (7) bằng ccil trên hệ
$$\begin{cases} (x - z)(x - y + z) = 0, \\ (y - x)(x + y - z) = 0, \\ xz + y^2 = 2. \end{cases}$$

Vì vế trái của hai điều khiển đầu tiên của hệ (8) là tích của hai đa thức, nên hệ (8) bằng (thuộc tính I) tập hợp bốn hệ sau:
$$\begin{cases} x - z = 0, \\ y - x = 0, \\ xz + y^2 = 0; \end{cases}$$

$$\begin{cases} x - z = 0, \\ x + y - z = 0, \\ xz + y^2 = 2; \end{cases}$$

$$\begin{cases} x - y + z = 0, \\ y - x = 0, \\ xz + y^2 = 2; \end{cases}$$

Rõ ràng là mỗi hệ thống trong số bốn hệ thống thu được đều đơn giản hơn hệ thống ban đầu (7).

Bằng cách giải hệ $(8_1), (8_2), (8_3), (8_4)$ bằng cách loại bỏ ẩn số (thuộc tính V) và kết hợp lời giải của các hệ này, chúng ta thu được tám ba số sau:
$$(1, 1, 1), (-1, -1, -1), (\sqrt{2}, 0, \sqrt{2}), (-\sqrt{2}, 0, -\sqrt{2}), (\sqrt{2}, \sqrt{2}, 0), (-\sqrt{2}, -\sqrt{2}, 0), (0, \sqrt{2}, \sqrt{2}), (0, -\sqrt{2}, -\sqrt{2}).$$

Tám bộ số này tạo thành toàn bộ bộ lời giải của hệ ban đầu (7), vì

$$(7) \langle = \rangle (8) \langle = \rangle [(8_1) \vee (8_2) \vee (8_3) \vee (8_4)].$$

Trong trường hợp này, việc kiểm tra là không cần thiết.

Ví dụ 2 (MIPT, 1969). Giải quyết hệ thống điều khiển
$$\begin{cases} x^2y = x + y - z, \\ z^2x = x - y + z, \\ y^2x = y - x + z. \end{cases}$$

Lời giải. Thêm các bộ điều khiển của hệ thống này theo cặp, chúng ta thu được hệ thống
$$\begin{cases} x^2y + z^2x = 2x, \\ x^2y + y^2z = 2y, \\ z^2x + y^2z = 2z, \end{cases}$$

⟦folio 48⟧

(do tính chất IV) bằng hệ (9). Hệ (10) đơn giản hơn hệ (9), vì mỗi phương trình của hệ (10) “chia” thành hai phương trình.

Hệ (10) có thể được viết lại như sau:

$$\begin{cases}
x(z^2+xy-2)=0, \\
y(x^2+yz-2)=0, \\
z(y^2+xz-2)=0;
\end{cases}$$

theo Tuyên bố I, nó bằng hệ thống tổng thể của các hệ thống có thể sau đây:

$$\begin{cases}
x=0, \\
y=0, \\
z=0; \\
(10_1) \\
x=0, \\
x^2+yz-2=0, \\
z=0; \\
(10_3) \\
z^2-xy-2=0, \\
y=0, \\
z=0; \\
(10_4) \\
z^2+xy-2=0, \\
x^2+yz-2=0, \\
z=0; \\
(10_5) \\
x=0, \\
x^2+yz-2=0, \\
y=0, \\
z=0; \\
(10_6) \\
z^2+xy-2=0, \\
y=0, \\
z=0; \\
(10_7) \\
z^2+xy-2=0, \\
x^2+yz-2=0, \\
y=0, \\
z=0; \\
(10_8) \\
z^2+xy-2=0, \\
x^2+yz-2=0, \\
y=0, \\
z=0; \\
(10_9) \\
\end{cases}$$

Hệ thống (10₁) có lời giải (0, 0, 0); hệ thống (10₂), (10₃), (10₄) không có lời giải; hệ thống (10₅) có lời giải ($\sqrt{2}, \sqrt{2}, 0$), ($-\sqrt{2}, -\sqrt{2}, 0$); hệ thống (10₆) có lời giải (0, $\sqrt{2}, \sqrt{2}$), (0, $-\sqrt{2}, -\sqrt{2}$); hệ thống (10₇) có lời giải ($\sqrt{2}, 0, \sqrt{2}$),

(-$\sqrt{2}, 0, -\sqrt{2}$); hệ (10₈) trùng với hệ (7), xét ở ví dụ 1. Vì (9) $\langle = \rangle$ (10) $\langle = \rangle$ $[(10_1)\lor(10_2)\lor\dots\lor(10_7)]$,

thì tập tất cả lời giải của hệ (9) là hợp của tập lời giải của hệ (10₁), (10₅), (10₆), (10₇), (7). Kết quả là lời giải ở trên của hệ thống (7) và lời giải khác (0, 0, 0).

Bài tập

Tìm tất cả lời giải hệ phương trình:

1. (MIPT, 1969).
$$\begin{cases}
xy+x+y=7, \\
yz+y+z=-3, \\
xz+x+z=-5.
\end{cases}$$

2. (MIPT, 1970).
$$\begin{cases}
3xy-\frac{16}{xz}=-5, \\
xz+\frac{8}{yz}=4, \\
yz-\frac{3}{xy}=1.
\end{cases}$$

3. (MIPT, 1970).
$$\begin{cases}
4xy+x^2+y^2=1, \\
8xz+x^2+4z^2=-2, \\
8yz+y^2+4z^2=1.
\end{cases}$$

4. (MIPT, 1969).
$$\begin{cases}
2(x^2+y^2)=xyz, \\
10(y^2+z^2)=29xyz, \\
5(z^2+x^2)=13xyz.
\end{cases}$$

Tìm hệ phương trình lời giải thực:

5. (MIPT, 1969).
$$\begin{cases}
xyz^2=-y-2x, \\
2x^2yz=-y-z, \\
3xy^2z=2x-z.
\end{cases}$$

6. (MIPT, 1969).
$$\begin{cases}
x^3+y^3=19xy+7xz+11yz, \\
x^3+z^3=26(xy+xz+yz), \\
y^3+z^3=47xy+35xz+39yz.
\end{cases}$$

7. (MIPT, 1970).
$$\begin{cases}
3x-6y-8z=xyz^2, \\
2x-5y-7z=-x^2yz, \\
3x-9y-13z=-xy^2z.
\end{cases}$$
