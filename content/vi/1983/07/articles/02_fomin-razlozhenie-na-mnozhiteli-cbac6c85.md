---
id: 1983-7-fomin-razlozhenie-na-mnozhiteli-cbac6c85
issue: kvant_1983_7
year: 1983
number: "7"
title: Nhân tố hóa
authors:
  - Фомин С. В.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 25
page_last: 26
page_labels: 23-24
tag: K3XU
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 4ef42f3bf34f443aaa74802d2e13fae17a2070aff1876f21710aab6d80f1e5b4
prompt_sha256: draft-1
translated_from: content/ru/1983/07/articles/02_fomin-razlozhenie-na-mnozhiteli-cbac6c85.md
source_content_sha256: 8b8e96aecdec3c75df84e8e42747cb29c66f9d2b8b7323c68d66ff72ec828850
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 23⟧

Nhân tố hóa

Ứng viên Khoa học Vật lý và Toán học S. V. FOMIN

Ở trường bạn thường phải giải các phương trình đại số. Các phương trình tuyến tính đã có thể được giải bởi học sinh lớp sáu. Trong lớp học ở làng, học sinh được học công thức của phương trình bậc hai lời giải. Các công thức khá phức tạp cho lời giải phương trình bậc ba và phương trình bậc bốn, được tìm thấy vào thế kỷ 16, hóa ra lại ít được sử dụng trong thực tế (xem cuốn sách “Những câu chuyện về các nhà vật lý và toán học” của S. G. Gindikin (M., “Nauka”, 1981)). Các phương trình bậc 5 trở lên trong trường hợp tổng quát không thể giải được bằng radiacalx.

Chưa hết, trong nhiều trường hợp, phương trình bậc $n>2$ rất dễ giải. Thông thường, bao thanh toán sẽ giúp ích. Từ khẳng định “số $a$ là nghiệm của đa thức $P(x)$ khi và chỉ nếu $P(x)$ chia hết cho $x-a$” và Định lý cơ bản của đại số («Kvant», 1982, số 4), suy ra rằng mọi đa thức có hệ số thực bậc $n>2$ đều bị rối loạn trong tích của các thừa số thứ nhất bậc và trieles vuông không thể phân tách được.

Hãy giải một số phương trình.

$$2x^3 - x^2 - 7x + 2 = 0.$$

(1)

Đa thức ở vế trái của phương trình (1) có hệ số nguyên. Dễ dàng chứng minh rằng nếu một phương trình như vậy có nghiệm nguyên thì nghiệm này là ước số của số hạng tự do (chứng minh đi!). Số 2 là nghiệm của phương trình (1). Điều này có nghĩa là đa thức $2x^3 - x^2 - 7x + 2$ chia hết cho $x-2$. Rõ ràng, phương trình riêng phần là phương trình bậc hai

một bội tam thức có hệ số cao nhất là 2, do đó

$$2x^3 - x^2 - 7x + 2 = (x-2)(2x^2 + Bx + C),$$

trong đó $B$ và $C$ là các hệ số hiển thị không xác định. Sự đẳng thức này đúng với mọi $x$. Bằng cách nhấp vào $x=0$, chúng tôi nhận được $-2C=2$, $C=-1$. Ví dụ: bằng cách che chắn $x=1$, chúng tôi nhận được $-(B+1) = -4$, $B=3$.

Do đó, phương trình (1) được viết lại thành

$$(x-2)(2x^2 + 3x - 1) = 0.$$

Đáp số. $\left\{2, \frac{-3+\sqrt{17}}{4}, \frac{3\sqrt{17}}{4}\right\}$

$$\frac{x^4 - 3x^3 + x^2 - 2}{x^3 + 1} = \frac{2}{3x-1}$$

Nếu loại bỏ ngay mẫu số, chúng ta sẽ có phương trình bậc 5. Vì vậy, “chúng ta hãy thử đếm” - chúng ta hãy thử tìm hiểu xem có thể giảm phân số ở vế bên trái hay không. Mẫu số của nó được nhân tử hóa:

$$x^3 + 1 = (x+1)(x^2 - x + 1).$$

Tử số không chia hết cho thừa số thứ nhất (xét cho cùng, số - 1 không phải là nghiệm của đa thức $x^4 - 3x^3 + x^2 - 2$). Hãy thử chia nó cho $x^2 - x + 1$. Tất nhiên, bạn có thể áp dụng lại “phương pháp hệ số không xác định”:

$$x^4 - 3x^3 + x^2 - 2 = (x^2 - x + 1)(x^2 + Ax + B) + C.$$

Xin vui lòng chia bằng một “góc” dễ dàng hơn - cách chúng ta chia số có nhiều chữ số cho số có nhiều chữ số:

$$\frac{x^4 - 3x^3 + x^2 - 2}{x^4 - x^3 + x^2 - 2} = \frac{x^2 - x + 1}{x^2 - 2x - 2}$$

$$- \frac{2x^3 + 2x^2 - 2x}{2x^2 + 2x - 2}$$

$$- \frac{2x^2 + 2x - 2}{0}$$

(Chúng ta chia số hạng dẫn đầu của số bị chia cho số hạng đứng đầu của số chia: $\frac{x^4}{x^2} = x^2$ - đây sẽ là số hạng dẫn đầu của thương. Sau đó, chúng ta nhân số hạng kết quả của thương với số chia và trừ tích của số chia. Tiếp theo, chúng ta chia số hạng dẫn đầu của hiệu một lần nữa

⟦folio 24⟧

ước số cho số hạng dẫn đầu: $\frac{-2x^3}{x^2} = -2x$ - chúng ta nhận được số hạng tiếp theo của thương, v.v.)

Chúng tôi đã “may mắn” - chúng tôi bị chia cắt không dấu vết. Do đó, phương trình (2) được viết lại thành
$$\frac{(x^2-x+1)(x^2-2x-2)}{(x+1)(x^2-x+1)} = \frac{2}{3x-1},
$$
$$\frac{x^2-2x-2}{x+1} = \frac{2}{3x-1}$$

và dễ dàng khớp với phương trình
$$x(x-3)(3x+2) = 0.$$
Đáp số. $\{0, 3, -\frac{2}{3}\}$.
$$\frac{2}{x+1} + \frac{4}{x-2} - \frac{2}{x} + x+4 = 0.$$ (3)

Bạn có thể ngay lập tức loại bỏ mẫu số và nhân vế trái của phương trình bậc bốn thu được. Tuy nhiên, việc phân tích trực tiếp vế trái của phương trình (3) sẽ dễ dàng hơn. Lưu ý rằng số 1 là gốc của nó. Tại $x=1$, năm số hạng ở vế trái nhận các giá trị 1, -4, -2, 1 và 4. Chúng ta hãy biến đổi phương trình này bằng cách trừ giá trị của nó tại $x=1$ từ mỗi số hạng:
$$\left(\frac{2}{x+1}-1\right) + \left(\frac{4}{x-2}+4\right) +
\left(-\frac{2}{x}+2\right) + (x-1) + (4-4) = 0$$
(tổng các số hạng được thêm vào bằng 0). Hãy thực hiện các hành động trong mỗi dấu ngoặc:
$$-\frac{x-1}{x+1} + \frac{4(x-1)}{x-2} + \frac{2(x-1)}{x} + (x-1) = 0.$$
Thừa số $x-1$ xuất hiện ở mỗi số hạng. Điều này không có gì đáng ngạc nhiên - xét cho cùng, giá trị của mỗi số hạng tại $x=1$ phải bằng 0! Bây giờ bài toán đã được rút gọn thành phương trình lời giải
$$-\frac{1}{x+1} + \frac{4}{x-2} + \frac{2}{x} + 1 = 0.$$
Không khó để đoán một trong những gốc của nó: $x=-2$ và áp dụng lại ví dụ tương tự:
$$\left(-\frac{1}{x+1}-1\right) + \left(\frac{4}{x-2}+1\right) +$$

$$+\left(\frac{2}{x}+1\right) + (1-1) = 0,$$
hoặc
$$-\frac{x+2}{x+1} + \frac{x+2}{x-2} + \frac{x+2}{x} = 0,$$
từ đâu $x=-2$ hoặc
$$-\frac{1}{x+1} + \frac{1}{x-2} + \frac{1}{x} = 0,$$
$$\frac{x^2+2x-2}{x(x+1)(x-2)} = 0.$$
Giải phương trình bậc hai ta tìm được các nghiệm còn lại.

Đáp số. $\{1, -2, -1-\sqrt{3}, -1+\sqrt{3}\}$.
$$(x^2+3x-2)^2 + 3(x^2+3x-2) - 2 = x.$$ (4)

Lưu ý rằng nếu x là nghiệm của phương trình
$$x^2+3x-2=x,$$
thì nó thỏa mãn phương trình (4). Do đó, chúng ta biết hai nghiệm của phương trình (4): $x_1 = -1-\sqrt{3}$ và $x_2 = -1+\sqrt{3}$. Mở ngoặc và di chuyển $x$ sang bên trái, ta thu được phương trình
$$x^4+6x^3+8x^2-4x-4=0.$$
Vế trái của nó chia hết cho $x-x_1$ và $x-x_2$, và do đó cũng chia hết cho $(x-x_1)(x-x_2) = x^2+2x-2$. Chia theo cách này hay cách khác, chúng ta nhận được $(x^2+2x-2)(x^2+4x+2) = 0.$
Đáp số. $\{-1+\sqrt{3}, -1-\sqrt{3}, -2+\sqrt{2}, -2-\sqrt{2}\}$.

Tóm lại ta giải hệ phương trình
$$\left\{ \begin{array}{l} (x+1)(13x-2y-15) - 2(y-1)(3y+2) = 0, \\ (x+1)(x+4y-15) - 28(y-1) = 0. \end{array} \right.$$ (5)

Dễ dàng nhận thấy cặp $(-1; 1)$ thỏa mãn điều đó. Không khó để tìm được một cặp $(1; 0)$ khác.

Và bây giờ - một động thái không chuẩn. Hãy vẽ một đường thẳng đi qua các điểm $(-1; 1)$ và $(1; 0)$ (phương trình của nó là $y=-\frac{x}{2}+\frac{1}{2}$) và lấy một điểm khác trên đó, ví dụ (3; -1). Tại $x=3; y=-1$ vế trái của phương trình thứ nhất của hệ (5) bằng 100 và vế thứ hai bằng -8. Kế tiếp
