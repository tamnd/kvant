---
id: 1972-3-margulis-radunskiy-uchites-rabotat-s-logarifmami-fc3b830c
issue: kvant_1972_3
year: 1972
number: "3"
title: Học cách làm việc với logarit
authors:
  - Маргулис А. Я.
  - Радунский Б. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 52
page_last: 57
page_labels: 50-55
tag: YENX
lang: vi
source: kvant_digital
extraction: vision
content_sha256: f2d2a651d8fa0417f54581bf1e71c3785680d79d33dc278a39b5b072b5b8e847
prompt_sha256: draft-1
translated_from: content/ru/1972/03/articles/15_margulis-radunskiy-uchites-rabotat-s-logarifmami-fc3b830c.md
source_content_sha256: 746a80a55cbfb2ad5cdcc9777c72ae441553aa8c434e9707c8cbe2fc3432e429
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 50⟧

HỌC ĐỂ LÀM VIỆC
VỚI logarit
A. Vâng. Margulis, B. A. Radunsky

Logarit xác định

Như đã biết, logarit của số $N$ cơ số $a$ ($a > 0; a \neq 1$) là số mũ mà cơ số $a$ phải được nâng lên để thu được một số cho trước $N$, tức là đối với $a > 0$, $a \neq 1$ $x = \log_a N$, nếu $a^x = N$.

Ký hiệu toán học cho định nghĩa logarit được gọi là đồng nhất thức logarit cơ bản:

$$a^{\log_a N} = N \quad (a > 0, a \neq 1, N > 0).$$

Chúng ta hãy nhớ lại rằng bất kỳ số dương nào có cơ số bất kỳ (dương và khác 1) đều có logarit, nhưng số âm và số 0 không có logarit.

10 hệ quả từ nhận diện chính

Nếu các số $a$ và $b$ dương và khác một ($M > 0$ và $N > 0$), thì các mối quan hệ sau (tính chất của logarit) là hợp lệ:

$$\log_a MN = \log_a M + \log_a N,$$

$$\log_a \frac{M}{N} = \log_a M - \log_a N,$$

$$\log_a M^\alpha = \alpha \log_a M,$$

$$\log_a N = \frac{\log_b N}{\log_b a},$$

$$\log_b a \times \log_a N = \log_b N,$$

$$\log_a b = \frac{1}{\log_b a},$$

$$\log_a^k N = \frac{1}{k} \log_a N \quad (k \neq 0),$$

$$\log_a^k N^k = \log_a N \quad (k = 0),$$

$$\frac{\log_a N}{\log_a M} = \frac{\log_b N}{\log_b M} \quad (M \neq 1),$$

$$\log_a N \times \log_b M = \log_a M \times \log_b N,$$

$$a^{\log_b c} = c^{\log_b a}.$$

Các công thức (1), (2) và (3) được gọi là quy tắc logarit. Chúng cho phép bạn tìm logarit của tích (1), thương (2) và bậc (hoặc

⟦folio 51⟧

(3). Các công thức tương tự cho phép bạn tìm một số theo logarit của nó, tức là tích của thế năng.

Công thức (4) có một ý nghĩa đặc biệt - đó là công thức chuyển sang một căn cứ mới. Nhờ công thức này, không cần phải có bảng logarit cho các cơ số khác nhau: chẳng hạn chỉ cần có bảng logarit thập phân là đủ để sử dụng công thức (4) để tìm logarit cho bất kỳ cơ số nào giao nhau với chúng ta.

Công thức (8) cho thấy tỉ số logarit của hai số không phụ thuộc cơ số.

Việc chứng minh các công thức (1) - (5) được thực hiện trong một khóa học ở trường *); Người đọc có thể dễ dàng tự mình chứng minh công thức (6) và (7), chuyển về cơ số $a$ bằng công thức (4). Thật dễ dàng để xác minh tính hợp lệ của công thức (8) nếu bạn nhận thấy rằng cả bên trái và bên phải của nó đều bằng số $\log_M N$ (tại sao?); công thức (9) chỉ đơn giản là một cách biểu diễn khác của đẳng thức (8). Và đây là lý do căn bản của công thức (10):

$$a^{\log_b c} = a^{\frac{\log_a c}{\log_a b}} = (a^{\log_a c})^{\log_b a} = c^{\log_b a}.$$

Bình luận

Chúng tôi đã đề xuất rằng $M > 0$ và $N > 0$. Tuy nhiên, đối với các phương trình logarit lời giải (hoặc các bất đẳng thức), khi vai trò của $M$ và $N$ là biểu thức từ ẩn số $x$, các phép biến đổi theo các công thức trên có thể dẫn đến các phương trình (bất đẳng thức) không bằng nhau. Trong những trường hợp như vậy, nên sử dụng các công thức tổng quát hơn **); ví dụ: nếu $M(x) \cdot N(x) > 0$, thì

$$\log_a M(x) \cdot N(x) = \log_a |M(x)| + \log_a |N(x)|.$$

Bây giờ chúng ta cũng sẽ không xem xét các sợi tóc. Mục tiêu của chúng tôi là chỉ ra cách áp dụng các tính chất cơ bản của logarit vào các phương trình, tính toán logarit này theo logarit khác và so sánh chúng về độ lớn.

Rút gọn biểu thức chứa logarit

Kiểm tra cẩn thận các ví dụ được đưa ra bằng bút chì và giấy; Điều quan trọng là phải hiểu các công thức được liệt kê ở trên được sử dụng ở đâu (chúng tôi thực hiện cụ thể các chuyển đổi một cách chi tiết nhưng hầu như không có lời giải thích).

Ví dụ 1. Rút gọn: $\log_3 5 \cdot \log_4 9 \cdot \log_5 2$.

Lời giải. $\log_3 5 \cdot \log_4 9 \cdot \log_5 2 = \log_3 5 \cdot \log_5 2 \cdot \log_2 3 = \log_3 2 \cdot \log_2 3 = \log_3 3 = 1$.

Ví dụ 2. Rút gọn biểu thức:

$$N = \frac{\log_a \left[ \frac{1}{2} \log_b a^2 \right] \cdot \lg a \cdot \log_a \frac{1}{2} 100}{\left(\lg a \cdot 2^{\log_2 \lg a}\right)^{\frac{1}{2}} \cdot \lg^{-\frac{1}{2}} a^2}.$$

Lời giải. Trước tiên, chúng ta hãy xác định phạm vi giá trị tham số cho phép: $a > 0$, $a \neq 1$, $b > 0$, $b \neq 1$ (vì $a$ và $b$ đóng vai trò là cơ số của logarit), $a > 1$ (để tồn tại $\log_2 \lg a$ phải có $\lg a > 0$, do đó $a > 1$), cửa sổ-

*) Ví dụ, xem E. S. Kochetkov, E. S. Kochetkova, Đại số và các hàm cơ bản, M., “Khai sáng”, 1970, §§ 183-186.

**) Để biết thêm chi tiết, xem G.V. Dorofeev, M.K. Potapov, N.Kh. Rozov, Cẩm nang toán học dành cho ứng viên đại học, M., “Nauka”, 1970.

⟦folio 52⟧

Cụ thể

$$a > 1; b > 0; b \neq 1.$$

chúng tôi có
$$\log_a \left[ b^{\frac{1}{2} \log_b a^2} \right] \cdot \lg a \cdot \log_a^{\frac{1}{2}} 100 = \log_a b^{\log_b a} \cdot \lg a \sqrt{2 \log_a 10} =$$
$$= \frac{\log_a a \cdot \lg a \cdot \sqrt{2}}{\sqrt{\lg a}} = \sqrt{2 \lg a}; \quad (\lg a \cdot 2^{\log_2 \lg a})^{\frac{1}{2}} \lg^{-\frac{1}{2}} a^2 =$$
$$= \frac{\sqrt{\lg a \cdot \lg a}}{\sqrt{2 \lg a}} = \sqrt{\frac{\lg a}{2}};$$

cuối cùng, $N = \frac{\sqrt{2 \lg a}}{\sqrt{\frac{\lg a}{2}}} = 2.$

Ví dụ 3. Hãy đơn giản biểu thức:
$$\left( b^{\frac{\log_{1000} a}{\lg a}} \cdot a^{\frac{\log_{1000} b}{\lg a}} \right)^3 \log_{ab} (2a + 3b)$$

Lời giải. Các tham số phải thỏa mãn điều kiện $a > 0; a \neq 1; b > 0; b \neq 1$ (giải thích lý do).

Chúng tôi có $b^{\frac{3 \log_{1000} a}{\lg a}} \cdot a^{\frac{3 \log_{1000} b}{\lg b}} = b^{\frac{\lg a}{\lg a}} \cdot a^{\frac{\lg b}{\lg b}} = ab,$
có thể tạo dáng được

$$N = (ab)^{\log_{ab} (2a + 3b)} = 2a + 3b.$$

Ví dụ 4. Hãy đơn giản biểu thức:
$$N = \left[ \left( \frac{\log_a^2 b + 1}{2 \log_a b} - 1 \right)^{\frac{1}{2}} + \left( \frac{2 \log_a^2 b + 1}{2 \log_a b} + 1 \right)^{\frac{1}{2}} \right] \sqrt{2} \log_a^{\frac{1}{2}} b.$$

Lời giải. Các tham số phải thỏa mãn các điều kiện sau: $a > 0; a \neq 1; b > 0, b \neq 1$ (giải thích lý do); hơn nữa, để $\log_a^{\frac{1}{2}} b$ tồn tại thì phải có $\log_a b \geq 0$. Do đó, dứt khoát: $a > 1$ và $b > 1$ hoặc $0 < a < 1$ và $0 < b < 1$. Kế tiếp,

$$N = \left[ \sqrt{\frac{(\log_a b - 1)^2}{2 \log_a b}} + \sqrt{\frac{(\log_a b + 1)^2}{2 \log_a b}} \right] \sqrt{2 \log_a b} = |\log_a b - 1| + (\log_a b + 1) = \left\{ \begin{array}{l} 2 \log_a b, \text{ если } b \geq a > 1 \text{ или } 0 < b \leq a < 1; \\ 2, \text{ если } a \geq b > 1 \text{ или } 0 < a \leq b < 1. \end{array} \right.$$

Ví dụ 2 và 4 cho thấy rõ tầm quan trọng của việc tính đến phạm vi giá trị tham số cho phép.

Tăng một số logarit thông qua những logarit khác

Ví dụ 5. Cho trước: $\log_{30} 3 = a; \log_{30} 5 = b; \text{ найти } \log_{30} 8.$

Lời giải. $\log_{30} 8 = 3 \log_{30} 2 = 3 \log_{30} \frac{30}{15} = 3 (\log_{30} 30 - \log_{30} 3) - \log_{30} 5) = 3 (1 - a - b).$

Mọi thứ ở đây đều đơn giản, bởi vì, thứ nhất, cơ số của tất cả các logarit đều giống nhau và thứ hai, bạn có thể biểu thị số 2 thông qua các số, logarit

⟦folio 53⟧

được cho trước (hoặc đã biết), tức là thông qua các số 30, 3 và 5. Rõ ràng điều này không phải lúc nào cũng dễ thực hiện.

Ví dụ 6. Cho trước: lg196=a; lg56=b; tìm lg 0.175.

Lời giải. Việc biểu diễn số 0,175 theo các số quen thuộc 196, 56 và 10 không phải là điều dễ dàng như vậy. Hãy biến đổi:

$$\lg 0,175 = \lg \frac{175}{1000} = \lg \frac{7}{40} = \lg 7 - 2 \lg 2 - 1.$$

Do đó, bài toán được rút gọn thành việc tìm lg7 và lg2.

Điều kiện bài toán có thể được viết dưới dạng hai đẳng thức:

$$2\lg 2 + 2\lg 7 = a,$$
$$3\lg 2 + \lg 7 = b.$$

Trong số này là

$$\lg 2 = \frac{2b-a}{4}; \quad \lg 7 = \frac{3a-2b}{4}.$$

Sau đó

$$\lg 0,175 = \frac{3a-2b}{4} - \frac{4b-2a}{4} - 1 = \frac{5a-6b-4}{4}.$$

Ví dụ 7. Cho trước: $\log_{14}7=a; \log_{14}5=b; \text{найти } \log_{25}28.$

Lời giải. Trong trường hợp có nhiều căn cứ khác nhau thì nên đi đến một căn cứ:

$$\log_{35}28 = \frac{\log_{14}28}{\log_{14}35} = \frac{\log_{14}2 \cdot 14}{\log_{14}5 \cdot 7} = \frac{1 + \log_{14} \frac{14}{7}}{a+b} = \frac{2-a}{a+b}.$$

Ví dụ 8. Cho trước: $\log_{12}27=a; \text{найти } \log_{6}16.$

Lời giải. $\log_{6}16 = 4\log_{6}2 = 4\frac{\log_{12}2}{\log_{12}6} = \frac{4\log_{12}2}{\log_{12} \frac{12}{2}} = \frac{4\log_{12}2}{1-\log_{12}2}.$

Tất cả những gì còn lại là tìm $\log_{12}2$. Theo điều kiện bài toán

$$a = \log_{12}27 = 3\log_{12}3 = 3\log_{12} \frac{12}{4} = 3(1-2\log_{12}2).$$

Từ đây $\log_{12}2 = \frac{3-a}{6}$, và sau đó

$$\log_{6}16 = \frac{4 \cdot \frac{3-a}{6}}{1-\frac{3-a}{6}} = \frac{4(3-a)}{3+a}.$$

So sánh logarit theo độ lớn

Biết các tính chất của hàm logarit, bạn có thể dễ dàng trả lời các câu hỏi sau: số nào lớn hơn trong hai số: $\log_{2}3$ hay $\log_{3}2$?

($\log_{2}3 > \log_{3}2$ hoặc $\log_{2}3 > 1$ và $\log_{3}2 < 1$);

$$\log_{\frac{1}{2}}3 \text{ или } \log_{3}1,1? \quad \left( \log_{\frac{1}{2}}3 < 0, \quad \log_{3}1,1 > 0; \quad \log_{\frac{1}{2}}3 < \log_{3}1,1 \right);$$

$$\log_{3}5 \text{ или } \log_{4}5? \quad (\log_{3}5 > \log_{4}5 - \text{объясните почему});$$

$$\log_{\frac{1}{2}}3 \text{ или } \log_{\frac{1}{2}}4? \quad \left( \log_{\frac{1}{2}}3 > \log_{\frac{1}{2}}4 - \text{объясните почему} \right).$$

Đối với lời giải ví dụ phức tạp hơn, ngoài việc sử dụng các thuộc tính của hàm logarit, sẽ cần phải thực hiện nhiều phép biến đổi khác nhau.

⟦folio 54⟧

Ví dụ 9. (MSU, Khoa Hóa học, 1969). Không có bảng, hãy xác định cái nào lớn hơn: $\log_{20}80$ hay $\log_{80}640$?

Lời giải. Chúng tôi sẽ sử dụng các logarit đã cho nhiều nhất có thể và quy chúng về cùng một cơ số:

$$\log_{20}80 = 1 + 2\log_{20}2 = 1 + \frac{2}{\log_{2}20},$$

$$\log_{80}640 = 1 + 3\log_{80}2 = 1 + \frac{3}{\log_{2}80}.$$

Vẫn còn phải so sánh các số $\frac{2}{\log_{2}20}$ và $\frac{3}{\log_{2}80}$. Nhưng $\log_{2}20 > 0; \log_{2}80 > 0$ và $2\log_{2}80 = \log_{2}6400 < 3\log_{2}20 = \log_{2}8000$. Vì vậy $\frac{2}{\log_{2}20} < \frac{3}{\log_{2}80}$, tức là $\log_{20}80 < \log_{80}640$.

Ví dụ 10. (MSU, Khoa Tâm lý học, 1969). Không sử dụng bảng, hãy chứng minh rằng $\log_{3}7 > \log_{7}27$.

Lời giải. Vì $\log_{7}27 = 3\log_{7}3 = \frac{3}{\log_{3}7}$ và $\log_{3}7 > 0$, chỉ cần chứng minh rằng $\log_{3}^27 > 3$ hoặc $\log_{3}7 > \sqrt{3}$ hoặc $7 > 3\sqrt{3}$ là đủ.

Chúng ta hãy thử trình bày chi tiết phép tính gần đúng “thuận tiện” cho số mũ vô tỉ. Cụ thể là, sử dụng thực tế là $\sqrt{3} < 1,75 = \frac{7}{4}$, chúng ta hãy so sánh $7$ và $3^{\frac{7}{4}}$, tức là $7^4$ và $3^7$. Từ đó $7^4 = 2401 > 3^7 = 2187$ được giới thiệu, tiếp theo là $7 > 3^{\frac{7}{4}} > 3^{\sqrt{3}}$ và sau đó là $\log_{3}7 > \log_{7}27$.

Ví dụ 11. Không có bảng, hãy xác định cái nào lớn hơn: $\log_{5}7$ hay $\log_{13}17$?

Lời giải. Giảm xuống một cơ sở không mang lại điều gì tốt đẹp. Tuy nhiên, ví dụ này được giải quyết bằng hai ví dụ trước. Lưu ý rằng $1 < \log_{5}7 < 2$, $1 < \log_{13}17 < 2$. Sau đó hãy so sánh các số

$$\log_{5}7 - 1 = \log_{5}7 - \log_{5}5 = \log_{5}\frac{7}{5}$$

Và

$$\log_{13}17 - 1 = \log_{13}17 - \log_{13}13 = \log_{13}\frac{17}{13}.$$

Nhưng $\log_{5}\frac{7}{5} > \log_{13}\frac{7}{5} > \log_{13}\frac{17}{13}$ (giải thích tại sao), rồi $\log_{5}7 > \log_{13}17$.

Ví dụ 12. Chứng minh rằng với mọi số tự nhiên $n > 1$

$$\log_{n}(n+1) > \log_{n+1}(n+2).$$

Lời giải. Rõ ràng là $\frac{n+1}{n} = 1 + \frac{1}{n} > \frac{n+2}{n+1} = 1 + \frac{1}{n+1}$. Do đó, sử dụng các tính chất của hàm logarit, chúng ta có (với $n > 1$)

$$\log_{n}\frac{n+1}{n} > \log_{n+1}\frac{n+1}{n} > \log_{n+1}\frac{n+2}{n+1}.$$

Biến đổi vế trái và vế phải, ta thu được ngay

$$\log_{n}(n+1) > \log_{n+1}(n+2).$$

Ví dụ, từ đây suy ra rằng

$$\log_{2}3 > \log_{3}4 > \dots > \log_{k+1}(k+2).$$

⟦folio 55⟧

Lễ tân 13. (MSU, Khoa Ngữ văn, 1969). Chứng minh rằng $\log_2 3 > \log_3 5$ mà không cần dùng bảng.

Lời giải. Phương pháp được sử dụng trong hai ví dụ trước không thể được áp dụng trực tiếp (đánh dấu vào phần này). Vì vậy, chúng tôi sẽ làm điều này: $\log_2 3 = \log_8 27$;

$$\log_3 5 = \log_9 25, \text{ а } \frac{27}{8} > \frac{25}{9}.$$

Tiếp theo, $\log_8 \frac{27}{8} > \log_9 \frac{27}{8} > \log_9 \frac{25}{9}$ hoặc $\log_8 27 - 1 > \log_9 25 - 1$, do đó $\log_2 3 > \log_3 5$.

Bài tập

Rút gọn các biểu thức sau:

1. $\frac{1}{5} \left( 2a^{\log_2 b} + 3b^{\log \sqrt{2}} \sqrt{a} \right)$.
2. $\left[ 1 + 2^{\frac{\lg a}{\lg \sqrt{2}}} - a^{1 + \frac{1}{\log_4 a^2}} \right]^{\frac{1}{2}} - 3 \log_3 2 \times \log_4 3 \cdot \log_5 4 \cdot \log_6 5 \cdot \log_7 6 \cdot \log_8 7$.
3. $\sqrt{\log_a b + \log_b a + 2 \cdot \log_{ab} a} \cdot \log_a^2 b$.

Tính toán không dùng bảng:

4. $2^{\sqrt{\log_2 3}} - 3^{\sqrt{\log_3 2}}$.
5. (MSU, Khoa Tâm lý học, 1971).
$$\frac{\log_3 135}{\log_{15} 3} - \frac{\log_3 5}{\log_{405} 3}$$.
6. Tính $\log_6 32$ nếu $\log_12 2 = a$.
7. Tính $\log_5 0,18$ nếu $\lg 2 = a$, $\lg 3 = b$.
8. Tính $\log_{25} 24$ nếu $\log_8 15 = \alpha$, $\log_{12} 18 = \beta$.
Không cần dùng bảng, hãy xác định cái nào lớn hơn:

9. $\log_2 3$ hay $\log \frac{1}{4}$?
10. $\log_4 5$ hay $\log \frac{1}{16}$?
11. $\log_5 7$ hay $\log_8 3$?
12. $\log_2 3$ hay $\log_5 8$?
13. (MSU, cơ chế, 1971). $3 \log_{16} 1862 + \log_{16} 1866$ hay $\log_2 1863$?
14. (MSU, Khoa Hóa học, 1969). $\log_{189} 1323$ hay $\log_6 147$?
15. (MSU, Khoa Tâm lý học, 1969). Chứng minh rằng $\log_3 16 > \log_16 729$ mà không cần dùng bảng.
16. (MSU, Khoa Ngữ văn, 1969). Chứng minh rằng $\log_5 14 > \log_7 18$ mà không cần dùng bảng.
