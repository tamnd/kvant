---
id: 1990-2-toom-uravneniya-kotoryie-udaetsya-reshit-8bb28127
issue: kvant_1990_2
year: 1990
number: "2"
title: Các phương trình có thể giải được
authors:
  - Тоом А. Л.
rubric: shkola-v-kvante
page_first: 57
page_last: 59
page_labels: 55-57
lang: vi
source: kvant_digital
extraction: vision
content_sha256: afbbf000d1f7c93e1b681e9180f20df737cfa98493983e33a4a24959de2598d6
prompt_sha256: draft-1
translated_from: content/ru/1990/02/articles/16_toom-uravneniya-kotoryie-udaetsya-reshit-8bb28127.md
source_content_sha256: 38c40da034672abb0ea3b52fe20083e9d7ac493ed3147382df1aedd3947927dc
translation_model: draft
translation_run: vi-draft-gaps-2026-11-01
translation_quality: draft
---

⟦folio 55⟧

---
running_head:
folio:
---

Toán 9-11

phương trình,
có thể giải quyết được

Trong lưu ý này chúng ta sẽ nói về phương trình đại số có dạng
$a_nx^n + a_{n-1}x^{n-1} + \dots + a_1x + a_0 = 0$. (1)

Ở trường, các phương trình cũng chỉ được giải với các giá trị $n \leqslant 2$. Tuy nhiên, trong một số trường hợp, các phương trình có bậc cao hơn bậc hai thu được bằng các kỹ thuật đặc biệt. Chúng tôi sẽ hiển thị một số trong số họ ở đây.

I. Định lý. Đặt tất cả các hệ số $a_n, \dots, a_0$ trong phương trình (1) là số nguyên và đặt phân số tối giản $p/q$ là nghiệm của phương trình này. Khi đó tử số $p$ của nó là ước số của số hạng tự do $a_0$, và mẫu số $q$ của nó là ước số của hệ số dẫn đầu $a_n$.

Bằng chứng. Chúng ta hãy thay thế $x = p/q$ vào phương trình (1). Chúng tôi sẽ nhận được
$a_np^n + a_{n-1}p^{n-1}q + \dots + a_1pq^{n-1} + a_0q^n = 0$.

Hệ số $p$ được bao gồm trong tất cả các số hạng ngoại trừ số hạng cuối cùng. Nhưng khi đó số hạng cuối cùng cũng chia hết cho $p$, vì nó bằng tổng các số hạng còn lại (có dấu trừ). Vì phân số $p/q$ của chúng ta không thể là ước của số $p$, điều đó có nghĩa là để số hạng cuối cùng $a_0q^n$ chia hết cho $p$ thì số hạng tự do $a_0$ phải chia hết cho $p$. Phát biểu đầu tiên của định lý đã được chứng minh. Điều thứ hai có thể được chứng minh theo cách tương tự.

Sử dụng định lý này, chúng ta có thể tìm được tất cả các nghiệm hữu tỉ của bất kỳ phương trình nào có hệ số nguyên (nếu có). Để làm điều này, chỉ cần lập danh sách tất cả các ước số

⟦folio 56⟧

---
running_head:
folio:
---

thuật ngữ tự do, danh sách tất cả các ước của hệ số cao nhất và sau đó thử tất cả các phân số có dạng $p/q$, lấy $p$ từ danh sách đầu tiên và $q$ từ danh sách thứ hai.

II. Bây giờ hãy giả sử rằng chúng ta đã biết một nghiệm của phương trình. (Bây giờ việc chúng ta nhận ra nó bằng cách nào không còn quan trọng nữa.) Làm thế nào chúng ta có thể sử dụng điều này để tìm phần còn lại của các nghiệm? Thủ tục chia đa thức sẽ giúp chúng ta đưa số có nhiều chữ số vào thủ tục. Hãy đưa ra một ví dụ về cách thực hiện việc này. Cho ta được phương trình

$$x^3 - 2x + 1 = 0.$$

Theo định lý trước, nếu phương trình này có nghiệm hữu tỷ thì chỉ có 1 hoặc -1. Bằng cách kiểm tra, chúng tôi đảm bảo rằng số 1 thực sự là gốc.

Bây giờ chúng ta cần phân tích đa thức ở vế trái của phương trình. Điều này có thể được thực hiện bằng cách nhóm các số hạng một cách thông minh, nhưng cũng có một cách đáng tin cậy không yêu cầu rút gọn: chia đa thức của chúng ta cho một góc cho $x - 1$. Cách thực hiện điều này được hiển thị trong hình 1.

$$\begin{array}{c}
x^3 - 2x + 1 \\
x^3 - x^2 \\
x^2 - 2x + 1 \\
x^2 - x \\
- x + 1 \\
- x + 1 \\
0
\end{array}$$

Puc. 1.

Trong trường hợp này phần dư bằng 0 nên ta dám viết đẳng thức

$$x^3 - 2x + 1 = (x - 1)(x^2 + x - 1).$$

Nhưng nói chung, khi chia đa thức sẽ thu được số dư. Một ví dụ khác về phép chia được hiển thị ở hình 2. Điều này cho ra số dư là 2. Chúng ta biết điều này

$$\begin{array}{c}
x^3 - 2x + 1 \\
x^3 + x^2 \\
- x^2 - 2x + 1 \\
- x^2 - x \\
- x + 1 \\
- x + 1 \\
0
\end{array}$$

Puc. 2.

đọc rằng có một danh tính

$$x^3 - 2x + 1 = (x + 1)(x^2 - x - 1) + 2.$$

Số dư là đa thức có bậc nhỏ hơn bậc của số chia. Cụ thể, nếu số chia là nhị thức có dạng $x - x_0$ thì phần dư là một số. Chính trường hợp này khiến chúng ta quan tâm ở đây.

Bây giờ chúng ta chuyển sang các định nghĩa chung.

Chia đa thức $P(x)$ cho nhị thức $x - x_0$ có nghĩa là tìm đa thức $Q(x)$ và một số $R$ sao cho nhận được đẳng thức

$$P(x) = (x - x_0)Q(x) + R.$$

(2)

Bạn có thể tìm kiếm chúng theo bất kỳ cách nào, chẳng hạn như chia cho một góc. Định lý sau đây cho chúng ta biết số dư khi chia cho nhị thức $x - x_0$.

Định lý Bezout. Số dư khi chia đa thức $P(x)$ cho nhị thức $x - x_0$ là $P(x_0)$. Cụ thể, phần dư này bằng 0 khi và chỉ khi số $x_0$ là nghiệm của đa thức $P(x)$.

Bằng chứng. Hãy thay $x = x_0$ vào danh tính (2) và nhận được

$$P(x_0) = R,$$

đó là phát biểu đầu tiên của định lý. Từ đẳng thức này, chúng ta thấy rằng $R$ bằng 0 nếu $P(x_0)$ bằng 0, nghĩa là nếu $x_0$ là nghiệm của $P(x)$.

Vì vậy, nếu chúng ta biết rằng số $x_0$ là nghiệm của đa thức $P(x)$, thì chúng ta chia nó cho $x - x_0$, biết trước (nhờ định lý Bezout) rằng số dư sẽ bằng 0. Vì vậy, chúng ta sẽ tạo lời giải của một phương trình đã cho thành lời giải của một phương trình khác có bậc thấp hơn. Đôi khi bằng cách này có thể giải hoàn toàn phương trình, tức là tìm ra tất cả các nghiệm của nó.

III. Một ví dụ khác hữu ích cho phương trình lời giải là sự thay đổi của các biến. Trường hợp thú vị nhất là phương trình nghịch đảo. Phương trình (1) được gọi là nghịch đảo nếu các hệ số của nó, nằm ở khoảng cách bằng nhau tính từ hai đầu, bằng nhau:

$$a_{n-k} = a_k$$ cho tất cả $k$ từ 0 đến $n$.

Hóa ra bất kỳ sự trở lại nào

⟦folio 57⟧

---
running_head:
folio:
---

$$x + \frac{1}{x} = t.$$ (3)

Hãy chỉ ra cách áp dụng sự thay thế này bằng cách sử dụng ví dụ về phương trình bậc bốn được trả về:

$$ax^4 + bx^3 + cx^2 + bx + a = 0,$$ ở đâu $a \neq 0$.

Hãy chia nó cho $x^2$ và viết lại như thế này:

$$a \left(x^2 + \frac{1}{x^2}\right) + b \left(x + \frac{1}{x}\right) + c = 0.$$

Hãy bình phương đẳng thức (3):

$$t^2 = \left(x + \frac{1}{x}\right)^2 = x^2 + \frac{1}{x^2} + 2,$$

tức là

$$x^2 + \frac{1}{x^2} = t^2 - 2.$$

Giới thiệu biến mới $t$, ta thu được phương trình bậc hai

$$a(t^2 - 2) + bt + c = 0.$$

Đối với các đa thức truy hồi bậc lẻ, chúng đều chia hết cho $x + 1$ và sau khi chia như vậy chúng cho ra các đa thức truy hồi bậc chẵn. Hãy chỉ ra điều này bằng cách sử dụng ví dụ về phương trình bậc năm được trả về

$$ax^5 + bx^4 + cx^3 + bx + a = 0.$$

Dễ dàng nhận thấy $x = -1$ là nghiệm của phương trình này, do đó, theo định lý Bezout, đa thức ở vế trái của phương trình chia hết cho $x + 1$. Tuy nhiên, kết quả của phép chia cũng có thể thu được bằng cách nhóm các số hạng:

$$a(x^5 + 1) + bx(x^3 + 1) + cx^2(x + 1) = 0.$$

Như đã biết, cả $x^3 + 1$ và $x^5 + 1$ đều chia hết cho $x + 1$:

$$x^3 + 1 = (x + 1)(x^2 - x + 1),$$

$$x^5 + 1 = (x + 1)(x^4 - x^3 + x^2 - x + 1).$$

Và nói chung, $x^{2k+1} + 1$ chia hết cho $x + 1$ với mọi $k$:

$$x^{2k+1} + 1 = (x + 1)(x^{2k} - x^{2k-1} + \dots - x + 1)$$

(“phẳng” và “khuyết điểm” bị gạch chéo).

Với điều này, chúng tôi đã thiết lập lý thuyết. Và để tìm hiểu cách sử dụng nó, hãy giải câu bài toán sau.
