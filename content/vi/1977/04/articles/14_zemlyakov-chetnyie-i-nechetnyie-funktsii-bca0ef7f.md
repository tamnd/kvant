---
id: 1977-4-zemlyakov-chetnyie-i-nechetnyie-funktsii-bca0ef7f
issue: kvant_1977_4
year: 1977
number: "4"
title: Hàm chẵn và hàm lẻ
authors:
  - Земляков А. Н.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 40
page_last: 43
page_labels: 38-41
tag: 6MLD
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c5ce23129e714fd9992ff9f4e83bf275ec6ec2efd748e854a11a7a6d4512e5c1
prompt_sha256: draft-1
translated_from: content/ru/1977/04/articles/14_zemlyakov-chetnyie-i-nechetnyie-funktsii-bca0ef7f.md
source_content_sha256: ac5ba11609923767434a15873956b72bfe681aa6e6ecdd89af13773fc6dd8062
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 38⟧

Hàm chẵn và hàm lẻ

"Kết nối với thế giới,
Rõ ràng vĩnh viễn
Chẵn và lẻ thu hút chúng ta"
K. Balmont

Bài viết này dành cho học sinh lớp 9 và là một minh họa, bổ sung cho đoạn 68 của sách giáo khoa “Đại số và sự khởi đầu của phân tích 9”.

Hàm chẵn

Hãy nhớ lại rằng hàm số $f$ được gọi là số nguyên nếu đáp ứng hai điều kiện sau:

(C) nếu $x \in D(f)$, thì $u - x \in D(f)$, tức là miền định nghĩa $D(f)$ của hàm $f$ đối xứng đối với điểm $0$ trên đường tọa độ $Ox$;

(H) $f(-x) = f(x)$ đối với bất kỳ $x \in D(f)$ nào, tức là ở điểm đối xứng (so với điểm $0$ trên trục $Ox$) điểm $x$ và $-x$ thì hàm $f$ có cùng giá trị.

Ví dụ về bốn hàm: mang tính xây dựng $c$ ($y = c$ với mọi $x \in \mathbb{R}$), $x^2$, cos $x$.

Đồ thị của hàm số thứ tư trên mặt phẳng tọa độ $Oxy$ đối xứng qua trục tọa độ. Nó được chứng minh theo cách này. Nếu điểm $M$ có tọa độ $(x_0; y_0)$ thuộc đồ thị hàm số $f$ (Hình 1), tức là $f(x_0) = y_0$, thì theo định nghĩa của hàm thứ tư, $-x_0 \in D(f)$ và $f(-x_0) = y_0$, rồi điểm $M'$ có tọa độ $(-x_0; y_0)$ thuộc đồ thị hàm số $f$. Nhưng điểm $M'$ chỉ đối xứng với điểm $M$ so với trục $Oy$. Do đó, cùng với bất kỳ điểm $M$ nào, đồ thị của hàm số thứ tư $f$ cũng chứa điểm $M'$, đối xứng với nó và điều này có nghĩa là đồ thị này đối xứng qua trục tọa độ.

Hàm chẵn

Hàm $f$ được gọi là hàm số lẻ nếu điều kiện đối xứng (C) được thỏa mãn (xem ở trên) và điều kiện sau của bốn hàm số cũng là hàm số lẻ (bạn hãy tự chứng minh điều này).

Hàm lẻ

Hàm $f$ được gọi là hàm số lẻ nếu điều kiện đối xứng (C) được thỏa mãn (xem ở trên) và điều kiện sau của bốn hàm số cũng là hàm số lẻ (bạn hãy tự chứng minh điều này).

Dễ dàng thấy rằng tổng và hiệu của hai hàm số lẻ cũng như

⟦folio 39⟧

Tích của một hàm lẻ và một số là các hàm lẻ.

Câu hỏi kiểm soát

1. Tích của hai hàm số lẻ là chẵn hay lẻ?
2. Hàm nào là tích của hàm chẵn và hàm lẻ?

Không có hàm chẵn cũng không có hàm lẻ

Lưu ý rằng “hàm lẻ” không giống với “hàm lẻ” (tức là hàm không chẵn). Theo quy luật, một hàm “lấy ngẫu nhiên” sẽ không chẵn cũng không lẻ: đồ thị của hàm “tùy ý” không bắt buộc phải có bất kỳ tính chất đối xứng nào.

Ví dụ 1. Hàm $f(x) = \frac{1}{(x+1)}$ không chẵn cũng không lẻ, vì miền xác định $D(f) = \{x | x \neq -1\}$ của nó không thỏa mãn điều kiện đối xứng (C): điểm $x_0 = 1$ thuộc về $D(f)$ và điểm $-x_0 = -1$ không thuộc về $D(f)$.

Ví dụ 2. Hàm $f(x) = x^2 + x + 1$ cũng không chẵn cũng không lẻ. Hàm này được xác định bởi lực và do đó điều kiện đối xứng (C) được thỏa mãn nhưng cả điều kiện (H) và điều kiện (H) đều không được thỏa mãn. Thật vậy, $f(-x) = x^2 - x + 1$. Đặt $x = 1$, chúng ta thấy $f(1) = 1 + 1 + 1 = 3$, $f(-1) = 1 - 1 + 1 = 1$ và $f(-1)$ không bằng $f(1)$ hoặc $-f(1)$.

Cũng lưu ý e. Việc đề cập đến thực tế là các biểu thức cho $f(x)$ và $f(-x)$ là “khác nhau”, do đó “$f(-x) \neq f(x)$” không chứng minh được điều gì khác: thứ nhất, các biểu thức hoàn toàn khác nhau về hình thức có thể định nghĩa cùng một chức năng; thứ hai, giả định “$f(-x) \neq f(x)$” chứa biến $x$ và tính đúng hay sai của nó phụ thuộc vào giá trị của $x$ (ví dụ: trong ví dụ đang xem xét tại $x = 0$ nó chỉ là $f(-x) = f(x)$). Điều kiện (H) cho tính chẵn lẻ của một hàm nằm ở tính đúng của mệnh đề “với mọi $x \in D(f)$ thì đẳng thức số $f(-x) = f(x)$” được thỏa mãn và khẳng định rằng điều kiện (H) không được thỏa mãn nằm ở tính đúng của mệnh đề, tức là phủ định của mệnh đề trước:

“có $x \in D(f)$ đẳng thức số $f(-x) = f(x)$ được thỏa mãn”, và khẳng định điều kiện (H) không được thỏa mãn nằm ở tính đúng của mệnh đề, tức là phủ định của mệnh đề trước:

“có $x \in D(f)$ đẳng thức số $f(-x) = f(x)$ được thỏa mãn”, và khẳng định điều kiện (H) không được thỏa mãn nằm ở tính đúng của mệnh đề, tức là phủ định của mệnh đề trước:

Câu hỏi được đặt ra: tại sao lại đưa ra khái niệm số chẵn, số lẻ của một hàm số nếu “phần lớn” của hàm số đó không chẵn cũng không lẻ? Đây là những gì chúng tôi sẽ giải thích bây giờ.

Ví dụ vật lý

Nếu một hệ vật lý có một dạng đối xứng nào đó thì các hàm liên quan đến nó thường có những tính chất đối xứng nhất định. Trong những trường hợp đơn giản nhất, chỉ phát sinh các hàm chẵn hoặc lẻ.

Ví dụ. Trên thanh ngang - trục $Ox$ - có một lò xo một quả, các đầu của lò xo được cố định tại các điểm đối xứng $x = -d$ và $x = d$, và một vòng đệm được gắn vào giữa lò xo - tại điểm $x = 0$, chuyển động tự do (không có ma sát) dọc theo thanh (Hình 3, a). Để quả bóng được di chuyển đến điểm có tọa độ $x$. Chúng ta hãy biểu thị bằng $F(x)$ độ lớn của lực tác dụng lên vòng đệm từ phía lò xo (chính xác hơn là hình chiếu của lực này lên trục $Ox$) và bằng $U(x)$ thế năng của vòng đệm ở vị trí này. Rõ ràng, lò xo không quan tâm vòng đệm được rút về bên phải hay bên trái: độ lớn tuyệt đối của lực và thế năng trong quá trình dịch chuyển $x$ và $-x$ là như nhau, tức là

$$|F(-x)| = |F(x)|$$

Và

$$U(-x) = U(x).$$

Xét rằng lực ở các vị trí $x$ và $-x$ hướng ngược chiều nhau (xem Hình 3, b, b), có thể viết

$$F(-x) = -F(x).$$

Do đó, chỉ từ việc xem xét tính đối xứng, chúng ta thu được kết quả sau:

⟦folio 40⟧

1) hàm $F(x)$, biểu thị sự phụ thuộc của lực $F$ vào sự trộn $x$, số lẻ;
2) hàm $U(x)$, biểu thị sự phụ thuộc của thế năng vào quá trình trộn, là số lẻ.

Ví dụ toán học
Rõ ràng, hàm lũy thừa $f(x) = x^n$, trong đó $n \in \mathbb{N}$, sẽ chẵn nếu $n$ chẵn và lẻ nếu $n$ lẻ (trên thực tế, đây là nguồn gốc của thuật ngữ này). Nói chung, một đa thức tùy ý $p(x)$ sẽ không phải là hàm chẵn hay hàm lẻ *). Tuy nhiên, nó có thể được biểu diễn dưới dạng tổng của hai đa thức $p_+(x)$ và $p_-(x)$, là các hàm chẵn và lẻ tương ứng. Ví dụ,

$$p(x) = x^7 + 2x^6 - x^5 - 3x^4 - 13x^2 + x + 17 = p_+(x) + p_-(x),$$

trong đó $p_+(x) = 2x^6 - 3x^4 - 13x^2 + 17$ là tổng các đơn thức từ $p(x)$ chứa $x$ đến lũy thừa chẵn và $p_-(x) = x^7 - x^5 + x$ là tổng các đơn thức từ $p(x)$ chứa $x$ đến lũy thừa lẻ.

Nó chỉ ra rằng không chỉ một đa thức, mà bất kỳ hàm nào có miền định nghĩa đối xứng đều có thể được biểu diễn dưới dạng tổng của hàm chẵn và hàm lẻ!

Định lý
Nếu hàm $f$ thỏa mãn điều kiện đối xứng (C), thì nó có thể được biểu diễn dưới dạng tổng của hai hàm - chẵn $f_+(x)$ và lẻ $f_-(x)$:

$$f(x) = f_+(x) + f_-(x),$$

(1) các miền định nghĩa của các phần tử phức hợp có hàm $f$: $D(f_+) = D(f_-) = D(f)$ và cách biểu diễn này là duy nhất.

Bằng chứng. Giả sử rằng hàm $f(x)$ đã được biểu diễn ở dạng (1) và các hàm $f_+$ và $f_-$ thỏa mãn điều kiện tương ứng

$$f_+(-x) = f_+(x),$$
$$f_-(-x) = -f_-(x).$$

(*) Ở đây và bên dưới, chúng tôi xem xét đa thức trong một biến $x$ và chúng tôi xác định đa thức $p(x)$ với hàm $x \rightarrow p(x)$.

Thay các giá trị $-x$ vào công thức (1) thay vì $x$, từ công thức (2) ta thu được

$$f(-x) = f_+(x) - f_-(x).$$

(3)

Cộng các đẳng thức (1) và (3), ta thu được

$$f(x) + f(-x) = 2f_+(x),$$

Ở đâu

$$f_+(x) = \frac{f(x) + f(-x)}{2}.$$

(4a)

Tương tự, trừ (3) cho (1), ta tìm được

$$f_-(x) = \frac{f(x) - f(-x)}{2}.$$

(46)

Do đó, nếu hàm $f$ được biểu thị ở dạng (1), thì các hàm $f_+$ và $f_-$ được tìm thấy duy nhất từ ​​hàm $f$ - sử dụng công thức (4). Do đó, nếu biểu diễn (1) tồn tại thì nó là duy nhất.

Và bây giờ - một bộ ba nhỏ: đối với một hàm tùy ý $f$ anh ấy đã xác định các hàm $f_+$ và $f_-$ tương ứng với (4).

Sau đó, từ công thức (4), suy ra rằng, thứ nhất, $f_+(x) + f_-(x) = f(x)$, tức là (1) thỏa mãn, và thứ hai, các hàm $f_+$ và $f_-$ tương ứng, chẵn và lẻ. Ví dụ: hãy kiểm tra điều kiện (H) cho hàm $f_-$. Đối với $x$ tùy ý, chúng ta có

$$f_-(-x) = \frac{f(-x) - f(-x)}{2} =$$

$$= \frac{f(x) - f(-x)}{2} =$$

$$= -f_-(x),$$

Q.E.D. Tính chẵn lẻ của hàm $f_+$ được kiểm tra theo cách tương tự.

Quét. Chứng minh trên, như chúng tôi nói, có bản chất mang tính xây dựng: chúng tôi không chỉ chứng minh sự tồn tại và duy nhất của biểu diễn (1), mà còn chỉ ra các công thức (4), nhờ đó người ta có thể tìm được “phần” chẵn và lẻ của một hàm số đã cho.

Câu hỏi kiểm soát

3. Giả định đối xứng $D(f)$ được sử dụng ở đâu trong chứng minh?

4. Theo định lý của chúng tôi, bất kỳ hàm nào có miền định nghĩa đối xứng, bao gồm bất kỳ hàm chẵn (hoặc lẻ) nào, đều được biểu diễn dưới dạng tổng của các phần chẵn và lẻ của nó. Tìm các hàm $f_+$ và $f_-$ nếu

a) hàm $f$-chẵn;
b) $f$ là hàm lẻ.

⟦folio 41⟧

5. Trong “ví dụ toán học”, chúng tôi đã mở rộng một đa thức $p(x)$ nhất định thành tổng của một hàm chẵn và lẻ, “thu thập” vào một hàm tất cả các hàm một năm chứa $x$ lũy thừa chẵn và thành một hàm khác - các hàm một năm chứa $x$ lũy thừa chẵn.

Rút ra sự khai triển này bằng cách sử dụng công thức (4).

6. Chứng minh rằng nếu một số đa thức là
a) một hàm chẵn thì nó chỉ chứa các hàm một năm với lũy thừa chẵn $x$;
6) hàm số lẻ thì nó chỉ chứa các số một năm có lũy thừa lẻ $x$.

Bài tập

1. Cho 11 hàm: $f_1(x) = \sqrt{x^2-1}$, $f_2(x) = \sqrt{x+1}$, $f_3(x) = \frac{x^2+1}{x^2-1}$, $f_4(x) = x^2 + \sin x$, $f_5(x) = x^2 \cdot 2^x$, $f_6(x) = x^3 + x^4 - x^2$, $f_7(x) = x^3 + \cos x$, $f_8(x) = x^3 + \mathrm{tg} x$, $f_9(x) = x^3 \cdot \sin x$, $f_{10}(x) = \frac{2^x-1}{2^x+1}$, $f_{11}(x) = \lg(x + \sqrt{x^2+1})$.

Xác định hàm số nào trong số này là hàm chẵn, hàm số lẻ và hàm số nào không chẵn cũng không lẻ (sau đó biểu diễn chúng dưới dạng tổng của hàm chẵn và hàm lẻ). Đưa ra bằng chứng liên quan. (Khi chứng minh một số tính chất chẵn lẻ, đừng quên phép thay thế sau Ví dụ 2!)

2. Tìm tất cả các hàm chẵn và tất cả các hàm lẻ của môi trường:
a) hàm tuyến tính
$f(x) = ax + b$;
6) hàm vuông
$f(x) = ax^2 + bx + c$;
b) chức năng của biểu mẫu
$f(x) = a \cos x + b \sin x$.

3. Biểu diễn các hàm sau dưới dạng tổng của hàm chẵn và hàm lẻ:
a) $f(x) = x^2 + x - \frac{1}{x} + 2$;
6) $f(x) = \frac{x^2 + 2x + 1}{x^3 - x}$;
b) $f(x) = (x^2 + 2x + 1) \mathrm{tg} x$;
d) $f(x) = 2^x$.

4. Được biết, hàm $f$ là số lẻ và $0 \in D(f)$. Tìm $f(0)$.

5. Tìm tất cả các hàm $f$ vừa chẵn vừa lẻ. (Phân đoạn trước và phân đoạn tích cực trên $R$?)
6. Có tất cả các chức năng đồng thời được thực hiện đồng thời không?
a) chẵn và tăng $R$;
6) lẻ và giảm dần $R$;
b) lẻ và dương bằng $R$?
7. Có thể
a) chẵn;
b) lẻ
chức năng có chính xác
1) một;
2) hai;
3) ba điểm cực trị?

8. a) Chứng minh rằng đạo hàm của hàm chẵn là đạo hàm số lẻ và đạo hàm của hàm số lẻ là số chẵn.

6) Các phát biểu ngược lại có đúng không:
1) nếu $f'(x)$ là hàm chẵn thì $f(x)$ là hàm lẻ;
2) nếu $f'(x)$ là hàm lẻ thì $f(x)$ là hàm lẻ?

9. $(a - e)$. Hoàn thiện đồ thị của hàm số ở Hình 4 thành đồ thị của một hàm số liên tục nhất định trên $R$ và
1) hàm chẵn;
2) hàm lẻ.

Trong trường hợp nào điều này là không thể? Trong trường hợp nào điều này có thể được thực hiện theo nhiều cách?

10 $(a - e)$. Được biết, hàm $f$ được xác định, chẵn và tuần hoàn với chu kỳ $T = 4$. Xây dựng lại đồ thị của nó theo số phận như trong Hình 5. Trong trường hợp nào điều này không thể thực hiện được? Trong trường hợp nào điều này có thể được thực hiện, nhưng nó không rõ ràng?

11 (lớp 10). Vẽ đồ thị của các hàm số sau:
a) $y = \arccos(\cos x)$;
6) $y = \arcsin(\sin x)$;
b) $y = \arctg(tg x)$;
d) $y = \arcsin(\cos x)$.
