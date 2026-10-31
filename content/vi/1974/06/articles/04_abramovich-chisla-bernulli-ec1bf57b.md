---
id: 1974-6-abramovich-chisla-bernulli-ec1bf57b
issue: kvant_1974_6
year: 1974
number: "6"
title: số Bernoulli
authors:
  - Абрамович В. С.
rubric: osnovnye-stati
page_first: 12
page_last: 15
page_labels: 10, 12, 13
tag: 8IVA
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 2ef133e6606d6e08afb9077706654aaecfed457ee4a0aff5c2b174965b536d54
prompt_sha256: draft-1
translated_from: content/ru/1974/06/articles/04_abramovich-chisla-bernulli-ec1bf57b.md
source_content_sha256: 2ec9c8f6eec8c8cf1f81a0394a4856b5adb107954b963359701f72b197f1e4ba
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 10⟧

Từ xa xưa, các nhà toán học đã cố gắng xây dựng những bí mật của thế giới tuyệt vời của các con số. Thế giới này thu hút bởi sự đa dạng, nghiêm ngặt và hoàn hảo của luật pháp. Ở đây có những “người vĩ đại” và có những “người lùn”, những “người làm việc chăm chỉ” nói chung và những “người nổi tiếng” như l và e. Nhưng thế giới dãy số còn đa dạng hơn nữa. Đây là dãy số tự nhiên
1, 2, 3, ...,
và một dãy số nguyên tố đầy bí mật sâu sắc
2, 3, 5, 7, ...,
và một chuỗi các “hệ số nhị thức”
$C_1^1, C_2^1, C_2^2, C_3^1, C_3^2, C_3^3, ...,$

xuất hiện khi nâng lên lũy thừa 2, 3, 4, ... “nhị thức” $a + b$:
$(a + b)^k = a^k + C_k^1 a^{k-1} b + C_k^2 a^{k-2} b^2 + \ldots + C_k^{k-1} a b^{k-1} + b^k.$

Các số $C_k^m$ là công cụ cơ bản trong một nhánh toán học hấp dẫn: tổ hợp $^*$. Chúng tôi cũng sẽ cần họ ở đất nước này. Ví dụ: chúng có thể được tính toán rất đơn giản - sử dụng công thức
$$C_k^m = \frac{k(k-1)(k-2)\ldots(k-m+1)}{1 \cdot 2 \ldots m},$$

$1 \leq m \leq k$, nhờ đó bạn có thể dễ dàng lấy được thuộc tính quan trọng nhất của chúng:
$$C_k^{m-1} + C_k^m = C_k^{m+1}$$

(Định lý Pascal). Công thức (2) cũng có thể được viết lại ở dạng “nhỏ gọn” hơn:
$$C_k^m = \frac{k!}{m!(k-m)!},$$

ở đâu $n! = 1 \cdot 2 \cdot \ldots n$ tại $n > 0$; giá trị 0! hóa ra bằng một (ký hiệu ! được gọi là thừa số). Công thức (2*) ngay lập tức hàm ý thêm một tính chất nữa của hệ số nhị thức:
$$C_k^m = C_k^{k-m}.$$

$^*$ Khoa học này được mô tả trong cuốn sách của N. Ya. Vilenkin với chức danh rõ ràng là M., “Khoa học”, 1969.

⟦folio 12⟧

sau đó đặt $n = 0$, chúng ta thu được công thức hồi quy để tính các số $B_k$:

$$B_k = \frac{1}{k+1} \left[ C_{k+1}^2 B_{k-1} - C_{k+1}^3 B_{k-2} + \ldots + (-1)^k C_{k+1}^k B_1 - (-1)^k B_0 \right],$$

(7)

$B_0 = 1$.

Sử dụng công thức này để kiểm tra giá trị của bốn số Bernoulli đầu tiên (xem (6)).

Bernoulli đã có thể chứng minh rằng các hệ số khác của đa thức $S_k(n)$ có thể được tính bằng cách sử dụng các số $B_k$. Hệ số $n^2$ hóa ra bằng $\frac{B_{k-1}}{k-1} C_k^2$, hệ số $n^3$ bằng $\frac{B_{k-2}}{k-2} C_k^3$, và cuối cùng, hệ số bậc $n^k$ hóa ra độc lập với $k$ và luôn bằng $\frac{B_1}{1} C_k^k = \frac{1}{2}$.

Hệ số cho bậc cao nhất $k+1$ nổi bật, có thể tìm thấy ngay từ công thức (5). Nó bằng $\frac{1}{k+1}$.

Do đó, công thức Bernoulli có dạng

$$S_k(n) = B_k n + \frac{B_{k-1}}{k-1} C_k^2 n^2 + \frac{B_{k-2}}{k-2} C_k^3 n^3 + \ldots + \frac{B_1}{1} C_k^k n^k + \frac{n^{k+1}}{k+1}.$$

(8)

Trong đoạn tiếp theo, chúng tôi sẽ chỉ ra rằng công thức (8) thực sự dài bằng một nửa.

2. Số Bernoulli với số lẻ

Định lý. Tất cả các số Bernoulli số lẻ ngoại trừ $B_1$ đều bằng 0: $B_{2m+1} = 0$ tại $m \geqslant 1$.

Để chứng minh điều này, chúng ta sử dụng đẳng thức (1); áp dụng nó vào sự khác biệt $(1+a)^{2m} - (1-a)^{2m}$:

$$(1+a)^{2m} - (1-a)^{2m} = 2 \left( C_{2m}^1 a + C_{2m}^3 a^3 + C_{2m}^5 a^5 + \ldots + C_{2m}^{2m-1} a^{2m-1} \right).$$

Đặt $a = 1, 2, \ldots, n$ vào đây và cộng các kết quả thu được, chúng ta có:

$$(S_{2m}(n) + (n+1)^{2m} - 1) - (S_{2m}(n) - n^{2m}) = (n+1)^{2m} + n^{2m} - 1.$$

Ở bên phải chúng ta nhận được biểu thức

$$2 \left( C_{2m}^1 S_1(n) + C_{2m}^3 S_3(n) + \ldots + C_{2m}^{2m-1} S_{2m-1}(n) \right).$$

(9)

Vì vậy chúng tôi có

$$(n+1)^{2m} + n^{2m} - 1 = 2 \left( C_{2m}^1 S_1(n) + C_{2m}^3 S_3(n) + \ldots + C_{2m}^{2m-1} S_{2m-1}(n) \right).$$

Hãy tính hệ số $n^1$ trong các biểu thức thu được ở phần bên phải và bên trái. Trong biểu thức bên trái, hệ số này sẽ bằng 2$m$ (rõ ràng rồi). Khó hơn một chút để thu được dạng hệ số lũy thừa bậc nhất $n$ trong biểu thức ở vế phải: để làm được điều này, chỉ cần thay các tổng $S_j(n)$ ($j = 1, 3, \ldots, 2m-1$) của các số Bernoulli bằng các số giống nhau trong công thức (9) (tuyên bố này xuất phát từ chính định nghĩa của số Bernoulli). Vì vậy, đây là cách tiếp cận:

$$C_{2m}^1 B_1 + C_{2m}^3 B_3 + C_{2m}^5 B_5 + \ldots + C_{2m}^{2m-1} B_{2m-1} = m.$$

⟦folio 13⟧

Không phải như $C_{2m}^1 = 2m$, mà là $B_1 = \frac{1}{2}$, thì nó phải là:

$$C_{2m}^3 B_3 + C_{2m}^5 B_5 + \ldots + C_{2m}^{2m-1} B_{2m-i} = 0. \tag{10}$$

Đặt $m = 2, 3, 4, \ldots$ ở đây một cách liên tục và tính đến $C_n^k = 0$ cho $k > n$, chúng ta thu được:

$$B_3 = B_5 = B_7 = \ldots = 0.$$

3. Kết nối với số nguyên tố

Christan Staudt (1798-1867), nghiên cứu số Bernoulli, đã thu được một kết quả hay và sâu sắc cho thấy bản chất số học của những con số này. Cho số $B_h$. Xét tất cả các số nguyên tố $p$ không vượt quá $k + 1$, và $p - 1$ được gọi là $k$ (tức là số của một số Bernoulli đã cho). Với tất cả $p$ như vậy, chúng ta soạn một tổng hữu hạn có dạng $\sum \frac{1}{p}$ - hãy gọi nó là tổng tương ứng với số Bernoulli đã cho $B_h$ (chúng ta hãy xem xét những số tiền như vậy mà Staudt xử lý). Hóa ra số $B_h$ và tổng tương ứng $\sum \frac{1}{p}$ bổ sung cho nhau thành một số nguyên. Vì vậy, $B_h + \sum \frac{1}{p}$ luôn là số nguyên!

Hãy lấy một ví dụ để đánh giá tầm quan trọng của kết quả này của Staudt. Hãy cho chúng tôi biết $B_6$ là gì và $0 < B_6 < 1$ là gì. Chúng tôi muốn tìm giá trị chính xác của nó; Hóa ra việc này giờ đây dễ thực hiện.

Thật vậy, các ước của 6 là các số 1, 2, 3, 6. Tăng chúng lên một ta được các số 2, 3, 4, 7. Trong đó các số nguyên tố là 2, 3 và 7. Ta tính tổng $\sum \frac{1}{p}$:

$$\frac{1}{2} + \frac{1}{3} + \frac{1}{7} = \frac{41}{42}.$$

Do đó, theo định lý Staudt $\frac{41}{42} + B_6$ phải là một số nguyên, nhưng vì theo điều kiện $0 < B_6 < 1$ nên số nguyên phù hợp duy nhất là 1. Do đó

$$B_6 = 1 - \frac{41}{42} = \frac{1}{42}.$$

Bài tập 1. Tìm $B_{14}$ nằm giữa số 1 và 2.

4. Về định lý Kummer

Năm 1850, nhà toán học vĩ đại người Đức Ernst Kummer (1810–1893) đã thu được một kết quả quan trọng liên quan đến bài toán tồn tại lời giải trong các số nguyên của phương trình Fermat $x^n + y^n = z^n$, $n \geq 3$ – cho bài toán Fermat. Mặc dù kết quả của việc này không giải quyết được hoàn toàn vấn đề nhưng nó vẫn là một trong những kết quả quan trọng nhất thu được theo hướng này. Kết quả này hóa ra có liên quan chặt chẽ với số Bernoulli.

Trước khi xây dựng định lý Kummer, chúng tôi giới thiệu phần sau (đề xuất của Kummer). Hãy để những điều đã cho trở nên đơn giản
