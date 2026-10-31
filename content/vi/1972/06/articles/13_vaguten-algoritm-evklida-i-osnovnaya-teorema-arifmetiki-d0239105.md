---
id: 1972-6-vaguten-algoritm-evklida-i-osnovnaya-teorema-arifmetiki-d0239105
issue: kvant_1972_6
year: 1972
number: "6"
title: Thuật toán Euclid và định lý cơ bản của số học
authors:
  - Вагутен В. Н.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 32
page_last: 36
page_labels: 30, 32, 34
tag: KIHS
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 4c4fdf95a952aa7692bd406a1a0039194ca68d8af995cce98e4cfbe5e0c831a0
prompt_sha256: draft-1
translated_from: content/ru/1972/06/articles/13_vaguten-algoritm-evklida-i-osnovnaya-teorema-arifmetiki-d0239105.md
source_content_sha256: 9c36138ddc815187212d04d736cb569cef0b645b5099630d46cca35e523d57bf
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 30⟧

V.N. VAGUTEN
Thuật toán Euclise và định lý cơ bản của số học

Bài viết này được viết dựa trên tài liệu từ một bài tập thí nghiệm dành cho lớp 8-9 tại Trường Toán Báo chí Liên bang thuộc Viện Hàn lâm Khoa học Sư phạm Liên Xô tại Đại học Tổng hợp Moscow mang tên M.V. Lomonosov.

Mọi người đều biết rằng bất kỳ số nguyên dương nào cũng có thể được phân tích thành tích của các thừa số nguyên tố; vì vậy, ví dụ,

$$400 = 2^4 \cdot 5^2, \quad 1001 = 7 \cdot 11 \cdot 13, \quad 290981 = 43 \cdot 67 \cdot 101.$$

Tại sao sự phân hủy này là duy nhất? Một thực tế đơn giản hơn: nếu tích mn chia hết cho 43 thì ít nhất một trong các số m và n phải chia hết cho 43. Làm thế nào để chứng minh điều này?

Những sự thật này được coi là hiển nhiên. Tuy nhiên, việc chứng minh chúng không hề dễ dàng. Chúng tôi sẽ làm điều này ở cuối bài viết và chúng tôi sẽ bắt đầu với những câu đơn giản nhất liên quan đến tính chia hết của số nguyên và chúng tôi sẽ nói về cách tìm ước số chung nhất của hai số mà không cần phân tách chúng thành thừa số nguyên tố.

Xuyên suốt, chúng tôi sử dụng các chữ cái Latinh (a, b, c, d, v.v.) để biểu thị số nguyên.

1. Khoảng cách của tổng, hiệu và tích

Ta nói số nguyên a chia hết cho số nguyên b nếu tồn tại số nguyên k sao cho a = kb. Trong trường hợp này, số b được gọi là ước số của số a.

Chúng ta hãy rút ra ngay hai phát biểu đơn giản:

1°. Nếu các số a và b chia hết cho c thì u tổng của chúng a + b, u hiệu của chúng a - b chia cho c;
2°. Nếu a chia hết cho c và b chia hết cho d thì tích ab của chúng chia hết cho cd.

Hãy chứng minh 1°. Vì a chia hết cho c nên a = kc, trong đó k là số nguyên nào đó. Tương tự, b = mc, trong đó m là số nguyên. Do đó, a + b = (k + m)c, a - b = (k - m)c, nghĩa là mỗi số a + b và a - b đều chia hết cho c.

Hãy chứng minh 2°. Đặt a = kc, b = md. Khi đó ab = (km)cd, ngụ ý Tuyên bố 2°.

Bài 1. Chứng minh rằng nếu a chia hết cho b, a b chia hết cho c thì a chia hết cho c.

Bài tập 2. Câu nào sau đây đúng, câu nào sai:

a) nếu một số hạng chia hết cho 6 và số hạng kia không chia hết cho 6 thì tổng của chúng không chia hết cho 6;
b) nếu tổng của hai số hạng không chia hết cho 6 thì ít nhất một số hạng không chia hết cho 6;
g) nếu tổng của hai số hạng không chia hết cho 6 thì mỗi số hạng không chia hết cho 6;

⟦folio 32⟧

4. Thuật toán Euclid

Tất nhiên, để tìm gcd của hai số, bạn có thể làm như sau: viết ra tất cả các ước của mỗi số, chọn các ước chung rồi lấy giá trị lớn nhất của chúng. Bạn có thể làm khác đi mà không cần tìm riêng các ước của từng số.

Hãy chứng minh bổ đề quan trọng sau đây.

Bổ đề 1. Cho $a = bq + r$, $m=d a$ GCD $(a, b) = \text{НОД}(b, r)$.

Để đạt được mục đích này, chúng ta sẽ chỉ ra rằng cặp số $(a, b)$ có cùng một tập ước chung giống như cặp số $(b, r)$. Tất nhiên, từ đây, GCD của các cặp này sẽ giống nhau. Vì vậy, chúng ta hãy chứng minh rằng mọi ước chung của các số $a$ và $b$ cũng là ước của số $r$ và ngược lại, mọi ước chung của các số $b$ và $r$ đều là ước của số $a$.

Đầu tiên chúng ta hãy chứng minh khẳng định đầu tiên. Đặt $a$ và $b$ chia hết cho $k$. Khi đó $bq$ chia hết cho $k$ (xem 2° từ điểm 1) và $r = a - bq$ chia hết cho $k$ (xem 1° từ điểm 1).

Hãy chuyển sang tuyên bố thứ hai. Nếu $b$ và $r$ chia hết cho $m$ thì $bq$ chia hết cho $m$ và $a = bq + r$ chia hết cho $m$ (ở đây chúng ta lại sử dụng câu 1° và 2° từ điểm 1).

Bổ đề đã được chứng minh cho phép bạn tìm gcd của hai số một cách dễ dàng và nhanh chóng. Hãy xem nó được thực hiện như thế nào.

Ví dụ. Hãy tìm GCD bằng (6069, 663).

Lời giải. Chia 6069 cho 663 có số dư:

$$6069 = 663 \cdot 9 + 102.$$

Từ bổ đề suy ra GCD (6069, 663) = GCD (663, 102).

Chúng tôi đang tìm kiếm gcd (663, 102). Để làm điều này, hãy chia 663 cho 102:

$$663 = 102 \cdot 6 + 51.$$

Một lần nữa, áp dụng bổ đề, ta được gcd (663, 102) = gcd (102, 51). Nhưng 102 chia hết cho 51 không có số dư:

$$102 = 51 \cdot 2,$$

đặt ra GCD (102, 51) = 51, do đó,

$$51 = \text{НОД} (102, 51) = \text{НОД} (663, 102) = \text{НОД} (6069, 663).$$

Đáp số. GCD (6069, 663) = 51.

Phương pháp tìm ước số chung nhất, dựa trên ứng dụng tuần tự của Bổ đề 1, có một tên đặc biệt - thuật toán Euclide.

Bài toán 13. Tìm ước số chung nhất của các số:

a) 987 654 321 và 123 456 789,
b) 7.777.777.777 và 777.777.

Bài 14. Từ một đường thẳng 324 $cm \times 141$ $cm$ một số hình vuông bị cắt khỏi cạnh 141 $cm$ cho đến khi còn lại một đường thẳng với một trong các cạnh

Hình 3.

nhỏ hơn 141 $cm$. Từ đường thẳng thu được, các hình vuông lại được cắt bỏ, các cạnh của chúng bằng cạnh nhỏ hơn của nó, miễn là điều này có thể, v.v. (Hình 3).

Đường thẳng sẽ được cắt thành những hình vuông nào? (Cho biết kích thước và số lượng của chúng).

Vì vậy, thuật toán Euclid là một phương pháp đơn giản để tìm ước chung nhất của hai số. Nếu chúng ta có hai số $a$ và $b$ và $a > b > 0$ thì trước tiên chúng ta chia $a$ cho $b$ và lấy phần dư $r_1$, nhỏ hơn $b$. Sau đó, chúng tôi chia số $b$ cho $r_1$ và tìm số dư $r_2$, nhỏ hơn $r_1$. Tiếp theo, chúng ta chia số $r_1$ cho số $r_2$ và chúng ta nhận được phần dư $r_3$, nhỏ hơn $r_2$, v.v. cho đến khi phần dư $r_{n-1}$ được chia hoàn toàn cho phần dư $r_n$, không có phần dư (tức là $r_{n+1} = 0$).

Rõ ràng là quá trình này chắc chắn sẽ kết thúc, vì mỗi phần còn lại ít hơn phần trước và

⟦folio 34⟧

Lời giải $x = -6, y = 55$ phù hợp cho cả hai phương trình.

Một lưu ý nữa. Chúng tôi đã đưa ra một phương pháp cho phép chúng tôi chỉ tìm thấy một lời giải của phương trình như vậy. Trên thực tế, nếu có một lời giải thì có vô số chúng.

Ví dụ, số

$$x = -6 + 13t, y = 55 - 119t$$

($t$ là số nguyên bất kỳ) cũng là nghiệm của cả hai phương trình của chúng ta. Trong thực tế,

$$119 (-6 + 13t) + 13 (55 - 119t) = 1$$
và tất nhiên
$$51 \cdot 119 (-6 + 13t) + 51 \cdot 13 (55 - 119t) = 51,$$
đó là
$$6069 (-6 + 13t) + 663 (55 - 119t) = 51.$$

Công thức (*) cho tất cả lời giải của các phương trình này ở dạng số nguyên. Hãy chứng minh điều đó. Đặt $(x, y)$ là một số lời giải:

$$119x + 13y = 1.$$

Chúng ta hãy trừ số hạng của phương trình này theo số hạng đẳng thức mà chúng ta đã biết

$$119 \cdot (-6) + 13 \cdot 55 = 1.$$

chúng tôi nhận được

$$119 (x + 6) + 13 (y - 55) = 0$$
hoặc

$$119 (x + 6) = 13 (55 - y).$$

Vì vế trái của đẳng thức cuối cùng chia hết cho 13 và số 119 và 13 bị đổ lẫn nhau nên số $x + 6$ phải chia hết cho 13: $x + 6 = 13t$, trong đó $t$ là một số nguyên. Sau đó $y = 55 - 119t$. Vì vậy, về cơ bản, chúng tôi đã tìm ra cách tìm lời giải của bất kỳ phương trình tuyến tính nào $ax + by = c$ dưới dạng số nguyên. Nói chung kết quả là:

Để phương trình $ax + by = c$ có lời giải ở dạng số nguyên $(x, y)$, điều cần và đủ là $c$ chia hết cho gcd $(a, b) = d$. Nếu điều kiện này được thỏa mãn $u (x_0, y_0)$ là một trong lời giải của phương trình này thì tất cả lời giải của nó được cho bởi các công thức

$$x = x_0 + b_1t, y = y_0 - a_1t,$$
$$a_1 = \frac{a}{d}, b_1 = \frac{b}{d}.$$

Bài 16. Tìm các số nguyên $x$ và $y$ sao cho $85x + 204y = 17$.

Bài tập 17. Các phương trình sau có lời giải là số nguyên hay không:

a) $105x + 56y = 42$;
b) $104x + 65y = 43$?

Bài tập 18. a) Có thể chế tạo một cục pin có điện áp 220 $\theta$ bằng cách mắc nối tiếp các phần tử thuộc hai loại: điện áp $6 \theta$ và $16 \theta$ - và nếu vậy thì nên lấy bao nhiêu phần tử cả hai?

b) Câu hỏi tương tự nếu điện áp của các phần tử $6 \theta$ và $15 \theta$.

Nhiệm vụ 19. Có thể trộn 45 rúp thành các tờ tiền rúp, ba rúp và năm rúp để chỉ có 20 tờ tiền không?

6. Định lý cơ bản của số học

Để chứng minh định lý chính, chúng ta sẽ thực hiện thêm một bước nữa - chúng ta sẽ chứng minh bổ đề.

Bổ đề 3. Nếu tích ab chia hết cho c và b và c nguyên tố cùng nhau thì a chia hết cho c.

Thật vậy, vì các số nguyên $x$ và $y$ nên $1 = bx + cy$. Nhân cả hai vế của đẳng thức với $a$, chúng ta thu được $a = abx + acy$. Vì ab chia hết cho $c$, nên $abx$ và tất nhiên, acy chia hết cho $c$, có nghĩa là tổng $a$ của chúng cũng chia hết cho $c$.

Bổ đề 3 rất thường được sử dụng cho lời giải bài toán, và đôi khi khá “không thể nhận ra”. Ví dụ: chúng tôi đã dựa vào nó trong đoạn trước khi rút ra các công thức cho tất cả các phương trình lời giải $119x + 13y = 1$ (ở đó chúng tôi thấy dạng tương ứng được in nghiêng).

Bài 20. Chứng minh rằng nếu số $a$ chia hết cho các số nguyên tố cùng nhau $b$ và $c$ thì $a$ chia hết cho $bc$.

Nhiệm vụ 21. Câu nào sau đây đúng:

a) nếu $ab$ chia hết cho 15 thì ít nhất một trong các thành phần chia hết cho 15;
b) nếu $ab$ chia hết cho 17 thì ít nhất một trong các thành phần chia hết cho 17;
b) nếu $a$ chia hết cho 6 và $b$ chia hết cho 10 thì $ab$ chia hết cho 15;
g) nếu $ab$ chia hết cho 60 và $b$ nguyên tố cùng nhau với 10 thì $a$ chia hết cho 20.

Bây giờ hãy nhớ lại rằng số tự nhiên $p$ được gọi là số nguyên tố nếu nó có số chia bằng nhau $p$ và 1.
