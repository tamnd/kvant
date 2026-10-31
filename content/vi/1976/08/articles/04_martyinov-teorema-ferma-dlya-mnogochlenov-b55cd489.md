---
id: 1976-8-martyinov-teorema-ferma-dlya-mnogochlenov-b55cd489
issue: kvant_1976_8
year: 1976
number: "8"
title: Định lý Fermat cho đa thức
authors:
  - Мартынов Б.
rubric: osnovnye-stati
page_first: 14
page_last: 17
page_labels: 12, 14, 15
tag: KU23
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 5fcecc91af2ebe30720edb3db0f850491b68cefb4d6c1eb5ebd36693ffd1fd4d
prompt_sha256: draft-1
translated_from: content/ru/1976/08/articles/04_martyinov-teorema-ferma-dlya-mnogochlenov-b55cd489.md
source_content_sha256: c9c2936e1bfe479d641e4a428778da28b852955b45dcccde71d527132b60704c
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 12⟧

Tất nhiên, tất cả các bạn đều đã nghe nói về Định lý cuối cùng của Fermat; nó được ông xây dựng cho các số tự nhiên. Bài viết này chứng minh định lý Fermat cho đa thức. Bài viết này là khó khăn. Một số dữ kiện được sử dụng trong đó nằm ngoài phạm vi chương trình giảng dạy của trường. Bạn đọc quan tâm sẽ tìm thấy mọi thứ mình cần trong cuốn sách “Toán học là gì” của P. Kurat và G. Robbins hoặc trong tập thứ hai của “Bách khoa toàn thư về toán tiểu học”.

Sản xuất bài toán

Giả định được Fermat đưa ra là phương trình $x^n + y^n = z^n$ với $n > 2$ không có lời giải trong số tự nhiên. Một bằng chứng về giả định này cho trường hợp tổng quát vẫn chưa được tìm thấy.

Tuy nhiên, hóa ra là nếu chúng ta thay thế các số tự nhiên $x$, $y$ và $z$ bằng đa thức trong một biến $t$: $x(t), y(t), z(t)$ - và viết phương trình

$$[x(t)]^n + [y(t)]^n = [z(t)]^n,$$

(một định lý tương tự đã được chứng minh).

Hãy để chúng tôi làm rõ tuyên bố bài toán. Trước hết, chúng ta lưu ý rằng các đa thức $x(t), y(t)$ và $z(t)$ thỏa mãn phương trình (1) khi và chỉ khi các đa thức $p(t) \cdot x(t), p(t) \cdot y(t)$ và $p(t) \cdot z(t)$ thỏa mãn phương trình (ở đây $p(t)$ là một đa thức khác 0 tùy ý). Do đó, chỉ cần chứng minh rằng không có bộ ba đa thức nguyên tố cùng nhau là đủ. Các đa thức được gọi là nguyên tố cùng nhau nếu chúng không có ước số chung nào khác ngoài hằng số (hằng số là đa thức bậc 0). Ngoài ra, tất nhiên, chúng ta phải loại trừ số tầm thường lời giải: bộ ba đa thức bậc 0, vì với mọi $a$ và $b$ bộ ba

$$x(t) = a, y(t) = b, z(t) = \sqrt[n]{a^n + b^n},$$

hiển nhiên là nghiệm của phương trình Fermat.

Nhân tiện, tại $n = 1$ phương trình (1) có lời giải hướng $x(t) = t, y(t) = t + 1, z(t) = 2t + 1$.

Nó có lời giải cũng ở $n = 2$. Dễ dàng kiểm tra chỉ đường; thật là ba

$$x(t) = t^2 - 1, y(t) = 2t, z(t) = t^2 + 1$$

là nghiệm của phương trình

$$[x(t)]^2 + [y(t)]^2 = [z(t)]^2.$$

Mục đích của bài viết là chứng minh một dạng tương tự của Định lý cuối cùng của Fermat cho đa thức:

Với $n > 2$ không có ba đa thức nguyên tố cùng nhau $x(t),$

⟦folio 14⟧

Chúng ta hãy chia chứng minh của chúng ta thành nhiều giai đoạn.

1. Từ điều kiện $1^\circ - 3^\circ$ suy ra rằng cứ hai đa thức $x, y, z$ đều có thể được đánh thức. Thật vậy, chẳng hạn, nếu $x$ và $y$ có ước chung $d$ thì $z^n$ chia hết cho $d^n$, và $z$ chia hết cho $d$, tức là $d$ là đa thức chung của các đa thức $x, y$ và $z$. Điều này mâu thuẫn với điều kiện $1^\circ$.

2. Gọi $m$ là bậc cao nhất của đa thức $x, y, z$ (theo điều kiện $3^m > 0$). Chúng ta có thể giả sử rằng bậc $m$ có đa thức $z$. Thật vậy, nếu muốn, phương trình ban đầu có thể được đối xứng với $x, y, z$: cần thay thế $z$ bằng $\varepsilon z$, trong đó $\varepsilon$ là số phức, lũy thừa thứ $n$ của nó bằng $-1: \varepsilon^n = -1$. chúng tôi nhận được

$$x^n + y^n + z^n = 0.$$

3. Đặt $\varepsilon_1, \varepsilon_2, \dots, \varepsilon_n$ là tất cả các nghiệm riêng biệt của bậc $n$ của số $-1$. Chúng ta thu được thực tế là mọi số phức khác 0 đều có chính xác $n$ nghiệm khác nhau ở bậc $n$ (xem điểm 1*). Khi đó đa thức $x^n + y^n$ được phân tích thành đa thức

$$x^n + y^n = (x - \varepsilon_1 y) (x - \varepsilon_2 y) \cdot \dots \cdot (x - \varepsilon_n y).$$

Để chứng minh, bạn có thể xây dựng nó như sau: lấy đa thức $u^n + 1$, gốc của nó là các số $\varepsilon_1, \dots, \varepsilon_n$, phân tách nó thành các đa thức: $u^n + 1 = (u - \varepsilon_1) \cdot (u - \varepsilon_2) \cdot \dots \cdot (u - \varepsilon_n)$ (mục 2*), sau đó thay $u$ cùng với phân số $\frac{x}{y}$ và loại bỏ mẫu số.

4. Đa thức $x - \varepsilon_i y$ được đánh thức lẫn nhau theo cặp. Thật vậy, nếu đa thức không cố định $d$ là ước chung của các đa thức $x - \varepsilon_i y$ và $x - \varepsilon_j y$ ($i \neq k$), thì hiệu của các đa thức này, bằng $(\varepsilon_h - \varepsilon_i) y$, cũng sẽ chia hết cho $d$, và do đó đa thức $y$ sẽ chia hết cho $d$ (được giới thiệu $\varepsilon_h - \varepsilon_i$ là một hằng số khác 0). Khi đó đa thức $x = (x - \varepsilon_i y) + \varepsilon_j y$ sẽ chia hết cho đa thức $d$, điều này mâu thuẫn với tính nguyên tố lẫn nhau của $x$ và $y$ (mục 1).

5. Nếu tích được mở rộng lẫn nhau theo cặp thì mỗi hai đa thức là ước chung của $d$, thì $z^n$ chia hết cho $d^n$, và $z$ chia hết cho $d$, tức là $d$ là đa thức chung của các đa thức $x, y$ và $z$. Điều này mâu thuẫn với điều kiện $1^\circ$.

Chúng tôi cung cấp bằng chứng về điểm 5 trong phần bổ sung quy chế.

6. Vì $x^n + y^n = (x - \varepsilon_i y) \times (x - \varepsilon_2 y) \dots (x - \varepsilon_n y) = z^n$ và đa thức $x - \varepsilon_i y$ là cặp đôi cùng thịnh vượng nên mỗi đa thức $x - \varepsilon_i y$ là bậc $n$ của đa thức. Đặt $x - \varepsilon_i y = u_i^n$, trong đó $u_i$ là đa thức. Chúng ta hãy biểu thị bậc của đa thức $u_i$ bằng $m_i$.

Chúng ta hãy chọn trong số các đa thức $u_i$ cái có đa thức nhất $u_1$. Chúng ta sẽ giả sử rằng đa thức $u_1$ có ​​đa thức lớn nhất.

7. $m_1 < m$.

Thật vậy, hiển nhiên là $m_1 \leq m$ (hãy nhớ rằng $m$ là lũy thừa của $z$). Nếu đẳng thức $m_1 = m$ được giữ nguyên thì tất cả các đa thức khác $x - \varepsilon_i y$ cho $i > 1$ đều là hằng số. Hãy lấy $x - \varepsilon_2 y$ và $x - \varepsilon_3 y$ (điều này có thể xảy ra - xét cho cùng, $n \geq 3$). Nếu $x - \varepsilon_2 y = A$, $x - \varepsilon_3 y = B$ thì

$$(B - A) x - (B \varepsilon_2 - A \varepsilon_3) y = 0,$$

tức là $x = Cy$ (đầu vào $A \neq B$ là bằng chứng) và điều này mâu thuẫn với tính nguyên tố lẫn nhau của $x$ và $y$.

Cũng lưu ý rằng $m_1 > 0$, tức là $u_1$, không phải là hằng số.

Chúng ta muốn chuyển từ đa thức $x, y, z$ sang đa thức tối không có đa thức chung, thỏa mãn Fermat và có bậc tối đa nhỏ hơn $m$. Hãy chứng minh rằng các đa thức $u_1, u_2$ và $u_3$ (xem Phần 6) nhân với một số hằng số có thể được coi là những đa thức như vậy.

⟦folio 15⟧

8. Chúng tôi có:

$$\begin{cases} x - \varepsilon_1 y = u_1^n, \\ x - \varepsilon_2 y = u_2^n, \\ x - \varepsilon_3 y = u_3^n. \end{cases}$$

Chúng ta hãy chọn ba số $c_1, c_2, c_3$ (không phải tất cả đều bằng 0) để khi cộng các đẳng thức này với hệ số $c_1, c_2, c_3$ thì phần nằm bằng 0. Rõ ràng là để làm được điều này cần phải thực thi hệ thống

$$\begin{cases} c_1 + c_2 + c_3 = 0, \\ c_1 \varepsilon_1 + c_2 \varepsilon_2 + c_3 \varepsilon_3 = 0. \end{cases}$$

Có thể dễ dàng tìm thấy ít nhất một lời giải khác 0 - ví dụ: đặt $c_3 = 1$ và giải hệ hai phương trình có hai ẩn số. Hãy tự mình thực hiện phép tính này.

Tìm $c_1, c_2$ và $c_3$ ta có

$$c_1 u_1^n + c_2 u_2^n + c_3 u_3^n = 0.$$

《Điều khiển》 các hệ số theo lũy thừa $n$, chúng ta có:

$$\left[ \sqrt[n]{c_1} u_1 \right]^n + \left[ \sqrt[n]{c_2} u_2 \right]^n = \left[ \sqrt[n]{c_3} u_3 \right]^n.$$

Thật dễ dàng để xác minh rằng ba đa thức mới thỏa mãn các điều kiện tương tự như $x, y, z$. Đồng thời, mức độ của họ giảm nhiều nhất (trong khi vẫn giữ nguyên số dương).

Phương pháp chứng minh của chúng tôi, do Fermat phát minh, được gọi là phương pháp “giảm dần vô hạn”. Thật không may, phương pháp này không có tác dụng chứng minh tính không giải được của phương trình Fermat trong các số tự nhiên, vì định lý về tính duy nhất của sự phân tích thành các đa thức đơn giản không áp dụng được cho các số có dạng $x - \varepsilon_i y$, trong đó $x$ và $y$ là số nguyên (xem đoạn 3*, trang 13). Việc nghiên cứu câu hỏi thú vị này được thực hiện bởi “số học cao hơn” - lý thuyết về số đại số - một lĩnh vực toán học hiện đang phát triển tích cực.

Thêm vào

A. Chúng ta hãy chứng minh mệnh đề được nêu trong đoạn 3* của bài viết (xem trang 13), nghĩa là, chúng ta chứng minh rằng bất kỳ đa thức nào cũng có thể được phân tách duy nhất thành tích của các đa thức tối giản (theo thứ tự của các đa thức và lên đến các đa thức, là một hằng số). (Đa thức tối giản là dạng tương tự của số nguyên tố trong đa thức các số tự nhiên: đa thức $q$ được gọi là tối giản nếu nó không thể phân tích thành tích các đa thức có bậc khác 0 khác $q$.)

Đầu tiên chúng ta chứng minh rằng mọi đa thức đều có thể khai triển thành tích của các bất khả quy. Thật vậy, nếu $Q$ là khả quy thì $Q = Q_1 \cdot G_2$, trong đó $G_1$ và $G_2$ là một số đa thức. Nếu $G_1$ và $G_2$ là không thể tối giản thì thu được sự phân rã cần thiết; nếu bất kỳ $G_i$ ($i=1, 2$) nào có thể rút gọn được thì $G_i = S_1^{(i)} \cdot S_2^{(i)}$, v.v. Rõ ràng là quá trình này sẽ kết thúc sau một số hữu hạn bước, vì bậc của đa thức $Q$ là hữu hạn. Do đó, chúng ta thu được sự phân rã của một đa thức thành tích của các hàm bất khả quy.

Và bây giờ chúng ta muốn chứng minh rằng nếu đối với các đa thức tối giản, chúng ta thỏa mãn đẳng thức $p_1 \cdot p_2 \dots p_l = q_1 \cdot q_2 \dots q_s$, thì $l = s$, và với mỗi i có một $k$ sao cho $q_i = c \cdot p_k$. Để làm điều này, chúng ta cần phát biểu sau: nếu tích $u \cdot v$ của hai đa thức $u$ và $v$ chia hết cho một đa thức tối giản $q$, thì bất kỳ $u, v$ nào cũng chia hết cho $q$. Chúng ta hãy chia đa thức $u$ và $v$ cho đa thức $q$ có ​​phần dư (thuật toán leo Euclide). Chúng ta nhận được phần còn lại của đa thức $u$ và $v$, bậc của mỗi đa thức nhỏ hơn bậc của đa thức $q$ và tích $u \cdot v$ chia hết cho $q$. Ta cần chứng minh rằng mọi $u = 0$ (khi đó $u$ chia hết cho $q$), mọi $v = 0$ (khi đó $v$ chia hết cho $q$). Chúng ta hãy chứng minh nhận định này bằng phương pháp quy nạp toán học (theo bậc của đa thức $q$).

Cơ sở cảm ứng. Bậc tối thiểu của đa thức tối giản không cố định là 1. Giả sử $q$ là một đa thức tuyến tính. Sau đó, nếu không phải $u \neq 0$ hay $v \neq 0$ thì $u = \text{const}$ và $v = \text{const}$. Nhưng khi đó $u \cdot v$ cũng là một hằng số, và do đó $u \cdot v$ không thể chia cho $q$. Do đó, phát biểu đúng với đa thức tuyến tính tối giản.

Bước cảm ứng. Giả sử rằng mệnh đề đúng với mọi đa thức tối giản có bậc nhỏ hơn bậc của đa thức $q$. Hãy chứng minh điều đó cho đa thức $q$. Giả sử rằng $u \cdot v \neq 0$. Vì $u \cdot v$ chia hết cho $q$ nên chúng ta có: $u \cdot v = q \cdot q$, $q \neq 0$ và bậc của đa thức $q$ hoàn toàn nhỏ hơn bậc của đa thức $q$ (vì bậc của tích $u \cdot v$ nhỏ hơn bậc của đa thức $q$). Hãy mở rộng $q$
