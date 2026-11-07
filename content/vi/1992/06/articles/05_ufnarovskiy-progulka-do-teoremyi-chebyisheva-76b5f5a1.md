---
id: 1992-6-ufnarovskiy-progulka-do-teoremyi-chebyisheva-76b5f5a1
issue: kvant_1992_6
year: 1992
number: "6"
title: Đi đến định lý Chebyshev
authors:
  - Уфнаровский В. А.
rubric: osnovnye-stati
page_first: 11
page_last: 14
page_labels: 9, 10, 12
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 4d315fc5eee5092be4c6b10b833301dc51eb8b9937863713a82e10fa5222e3c2
prompt_sha256: draft-1
translated_from: content/ru/1992/06/articles/05_ufnarovskiy-progulka-do-teoremyi-chebyisheva-76b5f5a1.md
source_content_sha256: 8b16fc90e4bd870e4a4b6fb2310eda9c59a162bb0a98f603333dedb7d194a04e
translation_model: draft
translation_run: vi-draft-gaps-2026-11-07
translation_quality: draft
---

⟦folio 9⟧

---
running_head:
folio:
---

Không khó lắm bài toán lời giải:
Vấn đề mang lại cảm hứng.
Nghệ thuật là có thể tìm thấy
Bài toán khi có lời giải.
P. Hayne. Grukki*)

Có một sức hấp dẫn đặc biệt khi đi bộ “xa đến mức bạn có thể nhìn thấy”: bạn đang đi mà không biết ở đâu, và đột nhiên bạn bắt gặp một điều gì đó hoàn toàn bất ngờ, một điều chưa bao giờ xảy ra với bạn khi bạn bắt đầu bước đi. Chúng ta hãy đi dạo dọc theo một con đường toán học phức tạp.

Chúng ta sẽ bắt đầu với tiêu chí chia hết cho 9: số n chia hết cho 9 khi và chỉ khi tổng các chữ số của nó chia hết cho 9. Bạn thậm chí có thể thêu: nếu bạn trừ đi số n thì tổng các chữ số của nó, mà chúng ta biểu thị là σ(n), thì kết quả sẽ luôn chia hết cho 9.

Bây giờ chúng ta hãy ngồi xuống và nói về ký hiệu. Thật kỳ lạ, rất nhiều điều phụ thuộc vào sự lựa chọn của họ, vì vậy các nhà toán học luôn khá bảo thủ trong ký hiệu. Ví dụ, ký hiệu n sẽ cho bất kỳ nhà toán học nào biết rằng chúng ta đang nói về số nguyên, rất có thể là số tự nhiên (nhân tiện, chúng ta có loại nào?). Không phải vô cớ mà chúng tôi chọn ký hiệu σ - xét cho cùng, đó là một chữ cái nhỏ “sigma”, và chữ cái lớn Σ đã được sử dụng từ thời cổ đại để biểu thị tổng. Số tiền của chúng tôi rất nhỏ nên chúng tôi sẽ lấy một lá thư nhỏ.

Chúng ta hãy nhìn vào ký hiệu từ một phía nữa. Tất nhiên, bạn biết rằng người Ả Rập không viết như chúng tôi - từ trái sang phải, mà ngược lại, từ phải sang trái. Nhưng bạn có bao giờ nghĩ rằng chính chúng ta chỉ định các con số bằng tiếng Ả Rập - từ phải sang trái không? Vâng, bạn sẽ không tin đâu, vì chúng ta viết số từ trái sang phải. Đó là sự thật. Bạn gấp như thế nào? Bạn bắt đầu bằng số nào, số đầu tiên hay số cuối cùng? Bạn có nhân lên không? Hãy thử điều ngược lại! Điều này không có gì đáng ngạc nhiên; như chúng ta biết, các con số và ký hiệu của chúng ta là tiếng Ả Rập. Trên thực tế, sẽ thuận tiện hơn nếu viết số từ phải sang trái, nhưng bạn có thể làm gì: thói quen là thói quen thứ hai. Để bỏ thói quen này, chúng ta sẽ viết số ở dạng khác - không phải thông qua các con số, mà thông qua việc mở rộng lũy ​​thừa mười, chẳng hạn như không phải 234 mà là 4 + 3 10 + 2 100. Thói quen của chúng ta không chống lại điều này, vì vậy chúng ta sẽ viết số n của mình dưới dạng này:

$$n = a_0 + a_1 \cdot 10 + a_2 \cdot 10^2 + \dots + a_k \cdot 10^k,$$

trong đó $a_0$ là chữ số cuối cùng, $a_1$ là chữ số áp chót, ..., $a_k$ là chữ số đầu tiên nên tổng số chữ số là ($k+1$) và tổng của chúng là

$$\sigma(n) = a_0 + a_1 + a_2 + \dots + a_k.$$

Chà, bây giờ không mất gì để chứng minh tuyên bố của chúng tôi:

$$n - \sigma(n) = (a_0 - a_0) + a_1(10-1) + a_2(10^2-1) + \dots + a_k(10^k-1) = 0 + 9a_1 + 99a_2 + \dots + 99\dots 9a_k,$$

tất nhiên, số này sẽ được ghép vào số 9 (nhân tiện, có bao nhiêu số chín trong mục cuối cùng?).

Đã tận hưởng thành quả lao động của mình, chúng ta hãy tiếp tục công việc đơn giản một cách dễ dàng, không cần nhiều định hướng? Bạn có thể thay đổi một trong ba: bài toán, bằng chứng và ký hiệu. Anh ta không muốn thay đổi bằng chứng. Chúng ta có thể thay đổi bài toán không? Đúng vậy, không khó để đưa ra và chứng minh phép thử tính chia hết cho 11 - chỉ cần lấy tổng theo dấu xen kẽ ($a_0 - a_1 + a_2 - a_3 + \dots$). Nếu bạn tìm hiểu sâu hơn, bạn sẽ nhận được một cái gì đó giống như một bài kiểm tra phổ quát về tính chia hết (chứng minh nó như một bài tập).

Bài toán. Cho m là số tự nhiên p₁, p₂, ..., pₖ là số dư của các số 10, 10², ..., 10ⁿ khi chia cho m. Sau đó số

$$n - (a_0 + a_1 p_1 + a_2 p_2 + \dots + a_k p_k)$$

chia hết cho m.

Với m=9 chúng ta thu được kết quả đã được chứng minh trước đó. Còn 11 thì sao? Với m=7, chúng ta thu được dãy $\{p_i\}: 3, 2, 6; 4, 5, 1, 3, 2$, v.v. Do đó, phần còn lại của năm 1992 tại

⟦folio 10⟧

---
running_head:
folio:
---

chia cho 7 bằng số dư 2+9·3+9·2+1·6=53, số này bằng số dư 3+5·3=18, do đó... Làm ơn, chúng ta có thể dừng lại và nói rằng đây là 4. Không thú vị lắm...

Hãy đi theo cách khác và cố gắng thay đổi ký hiệu. Chúng ta có thể biểu thị số $n$ của mình bằng cách nào khác? Bất cứ ai ít nhất một chút quen thuộc với lập trình sẽ nói ngay rằng bạn cần sử dụng một hệ thống số khác, chẳng hạn như double:

$$n = b_0 + b_1 \cdot 2 + b_2 \cdot 2^2 + \dots + b_m \cdot 2^m,$$

trong đó $b_i$ là số không và số một. (Ví dụ: $25=1+0 \cdot 2+0 \cdot 4+1 \cdot 8+1 \cdot 6$.) Ở đây cũng có tổng các số: $\sigma_2(n) = b_0 + b_1 + b_2 + \dots$ (Số 2, tất nhiên, gợi ý về cơ sở của hệ thống số, vì vậy $\sigma$ của chúng ta là $\sigma_{10}$.)

Định lý tương ứng có vẻ như sau: $n - \sigma_2(n)$ được chia cho... Và, thực sự, cho cái gì? Trong hệ thập phân, nó chia hết cho $9=10-1$, nên ở đây nó phải chia hết cho $2-1=1$. Sự thật là đúng, nhưng nhỏ. Hoặc có thể thử trong trường hợp tổng quát, trong hệ số $p$-ary, trong đó $p$ là cơ số tùy ý? Hãy viết nó ra

$$n = a_0 + a_1 p + a_2 p^2 + \dots + a_k p^k$$

(ở đâu $a_i < p$)

và biểu thị

$$\sigma_p(n) = a_0 + a_1 + a_2 + \dots + a_k,$$

hóa ra nó đẹp

Định lý 1. $n - \sigma_p(n)$ chia hết cho $(p-1)$.

Hãy chứng minh điều đó. Rất đơn giản - sự kỳ diệu không thay đổi: sự khác biệt

$$n - \sigma_p(n) =$$

$$= (a_0 - a_0) + a_1 (p-1) + a_2 (p^2-1) + \dots + a_k (p^k-1),$$

tất nhiên là chia hết cho $(p-1)$.

Ví dụ, trong hệ số bát giác, một số viết là 124 chia hết cho 7. Hãy kiểm tra xem?

$$4 + 2 \cdot 8 + 1 \cdot 64 = 84$$ - quả thực, nó chia hết cho 7. Đây là một tiêu chí mới về khả năng chia hết cho 7. Chỉ tiếc là chúng ta không quen với hệ thống số hơn.

Tiếp theo bạn sẽ đi đâu? Những gì khác có thể học được từ phép chia? Nếu hành động đó là chia rẽ thì sao? Thật vậy, một câu hỏi hoàn toàn xứng đáng là: thương của phép chia là bao nhiêu:

$$\delta_p(n) = \frac{n - \sigma_p(n)}{p-1}?$$

Thật thú vị... Hãy bắt đầu ít nhất với $p=2$, mặc dù không cần phải chia ở đó. Hãy bắt đầu với một bảng:

$$\begin{array}{c c c c}
n_{10} & n_2 & \sigma_2(n) & \delta(n)=n-\sigma_2(n) \\
0 & 0 & 0 & 0 \\
1 & 1 & 1 & 0 \\
2 & 10 & 1 & 1 \\
3 & 11 & 2 & 1 \\
4 & 100 & 1 & 3 \\
5 & 101 & 2 & 3 \\
6 & 110 & 2 & 4 \\
7 & 111 & 3 & 4 \\
8 & 1000 & 1 & 7 \\
9 & 1001 & 2 & 7 \\
10 & 1010 & 2 & 8 \\
11 & 1011 & 3 & 8 \\
12 & 1100 & 2 & 10 \\
\end{array}$$

Chúng ta thấy gì? Đối với mọi $n$ số lẻ, số $\delta(n)$ không thay đổi, đối với số chẵn thì thay đổi. Bao lâu? Vâng, giống như số số 0 ở cuối ký hiệu kép của số $n$. Và con số này, như chúng ta biết, là lũy thừa tối đa của hai mà $n$ chia hết cho. Ví dụ: $n=12$ chia hết cho $4=2^2$ và chúng tôi tăng từng bước 2 - từ 8 đến 10. Điều này có nghĩa là $\delta(n)$ dường như đếm xem có bao nhiêu lũy thừa của hai trong các số 1, 2, ..., $n$ hay nói đúng hơn là trong tích $1 \cdot 2 \cdot 3 \cdot \dots \cdot n$, thường được ký hiệu là $n!$ và được gọi là giai thừa của số $n$. Vì thế,

⟦folio 12⟧

---
running_head:
folio:
---

Đây là định lý chúng ta đã đạt được! Để học hỏi từ một thực tế không rõ ràng như vậy? Mắt tôi mở to. Chà, hãy bắt đầu những điều đơn giản bằng cách nghiên cứu $C_{2n}^n$ - hệ số sinh học lớn nhất trong số tất cả những hệ số có trong khai triển nhị thức $(x+y)^{2n}$. (Nhân tiện, bạn có thể chứng minh rằng nó thực sự là lớn nhất không?) Mũ tối đa của $p$ mà nó có thể chia cho bằng với số lần mang có được từ việc thêm $n$ vào chính nó trong hệ thống số $p$. Giả sử rằng $n < p < 2n$.

Sau đó, $n$ trong hệ thống $p$-ary được viết bởi một “chữ số” $p$-ary (thực tế là $n$) và $2n$ bởi hai, chẳng hạn như $2n=r+1 \cdot p$. Điều này có nghĩa là xảy ra đúng một lần nhớ và do đó $p$ nhập $C_{2n}^n$ đúng một lần. Do đó, tích của tất cả các số nguyên tố từ $n$ đến $2n$ không vượt quá $C_{2n}^n$. Có thể có được một cái gì đó hấp dẫn hơn? Hãy đánh giá đại khái là $C_{2n}^n$.

Nếu chúng ta đặt $x=y=1$ vào nhị thức Newton, thì hóa ra

$$1 + C_{2n}^1 + C_{2n}^2 + \dots + C_{2n}^n + \dots + C_{2n}^{2n-1} + 1 = 2^{2n},$$

Ở đâu

$$C_{2n}^n < 4^n.$$

Theo cách tương tự, tích của tất cả các số nguyên tố giữa $n/2$ và $n$ nhỏ hơn $4^{n/2}$, giữa $n/4$ và $n/2$ nhỏ hơn $4^{n/4}$, v.v. Khi đó tích của tất cả các số nguyên tố từ 1 đến $n$ nhỏ hơn

$$4^{n/2} \cdot 4^{n/4} \cdot 4^{n/8} \dots = 4^{n/2+n/4+n/8+\dots} < 4^n.$$

Kết quả là chúng tôi đã nhận được một sự thật hoàn toàn không rõ ràng miễn phí:

Định lý 3. Tích của mọi số nguyên tố nhỏ hơn $n$ không vượt quá $4^n$.

Bài tập 3. Chứng minh điều này một cách chặt chẽ: chúng ta chia đôi quá cẩu thả, “quên” rằng cũng có những số lẻ. (Có lẽ cách tốt nhất để tiếp cận vấn đề này một cách chặt chẽ là quy nạp.)

Hãy để bây giờ $p \leq n$. Khi đó khai triển của $n$ có ít nhất hai chữ số $p$-ary. Nếu trong phân tách $2n$ có hai trong số chúng, thì $2n < p^2$ sẽ hoàn thành việc xuất hiện tối đa một lần chuyển. Vì vậy, nó là sự thật

Bổ đề 1. Nếu $p > \sqrt{2n}$ thì lũy thừa cực đại $p$ chia $C_{2n}^n$ không vượt quá 1.

Tôi tự hỏi khi nào không có sự phân chia nào cả? Vì $2n < p^2$, thì $n = a_0 + a_1 p$, trong đó $a_0 < p$, $a_1 < p/2$. Để tránh dấu gạch nối, phải có $a_0 < p/2$. Cụ thể, đối với $a_1 = 1$, chúng ta thu được rằng nếu $a_0 = n - p < p/2$ thì $p$ không phải là ước của $C_{2n}^n$. Nó theo sau

Bổ đề 2. Nếu $n \geq p > 2n/3$ thì $p$ không phải là ước của $C_{2n}^n (n > 2)$.

Bằng chứng. $n < p + p/2 = 3p/2$, từ đâu $p > 2n/3$.

Bây giờ chúng ta hãy ước tính điều gì xảy ra ở các giá trị nhỏ $p \leq \sqrt{2n}$. Có thể đã có một số dấu gạch nối, nhưng trong mọi trường hợp không quá $k$, nếu $2n = a_0 + a_1 p + a_2 p^2 + \dots + a_k p^k$. Vì $2n \geq p^k$, rồi $\log_2 2n \geq k$, và chúng ta có thể nói rằng lũy ​​thừa tối đa của $p$ chia $C_{2n}^n$ không vượt quá $\log_2 2n$. Điều này có nghĩa là $p$ hợp lệ cho một giá trị tùy ý.

Bổ đề 3. Giả sử $N = p^m$ là ước số của $C_{2n}^n$. Sau đó $N \leq 2n$.

Bằng chứng. $p^m \leq p^{\log_2 p^2} = 2n$.

Chà, bây giờ chúng ta ít nhiều tưởng tượng ra cấu trúc của số $C_{2n}^n$. Sự mở rộng của nó sang lũy ​​thừa của số nguyên tố bao gồm ba loại comnutelles:

1) Các số nguyên tố lớn hơn $n$ (và tất nhiên là nhỏ hơn $2n$) - mỗi số một lần.
2) Các số nguyên tố nhỏ hơn $2n/3$ nhưng lớn hơn $\sqrt{2n}$, mỗi số nhiều nhất một lần.
3) Các số nguyên tố nhỏ hơn $\sqrt{2n}$. Ở đây, có thể chia hết cho $p^k$ với $k > 1$ nhưng tổng đóng góp $p^k$ của mỗi số nguyên tố đó không vượt quá $2n$.

Tôi tự hỏi liệu có thể nhóm đầu tiên bị thiếu, tức là không có số nguyên tố nào giữa $n$ và $2n$?
