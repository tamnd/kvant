---
id: 1976-1-haplanov-transtsendentnyie-chisla-7f19f713
issue: kvant_1976_1
year: 1976
number: "1"
title: Những con số siêu việt
authors:
  - Хапланов М. Г.
rubric: osnovnye-stati
page_first: 26
page_last: 29
page_labels: 24-27
tag: OA6W
lang: vi
source: kvant_digital
extraction: publisher
content_sha256: d6827d9f85ce30c3498914109d7e07169ac71248f60fecf33dbb3ebaa15d199f
prompt_sha256: draft-1
translated_from: content/ru/1976/01/articles/06_haplanov-transtsendentnyie-chisla-7f19f713.md
source_content_sha256: 7043e2607631f2d2c5b0d672b3fac3899b057728e3d5daa8387695d921d8b2d4
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

## Những con số siêu việt

Khái niệm *số* đã được hình thành qua hàng nghìn năm. Và chỉ hai trăm năm trước - chủ yếu trong các tác phẩm của L. Euler (1707-1783) - số phức đã đi vào toán học và sự phát triển của khái niệm số đã hoàn thành.

Chúng ta hãy nhớ lại các giai đoạn (không theo trình tự thời gian) của sự phát triển này:

1. *số tự nhiên* 1, 2, 3, $\ldots$;
2. *số nguyên* $\ldots$, $-3$, $-2$, $-1$, 0, 1, 2, 3, $\ldots$;
3. *số hữu tỷ*, tức là các số có dạng $\dfrac pq$, trong đó $p$ là số nguyên, $q$ là số tự nhiên;
4. *số thực*, tức là các số được biểu thị bằng phân số thập phân vô hạn;
5. *số phức*, tức là các số có dạng $a+bi$, trong đó $a$ và $b$ là số thực và ký hiệu $i$ được xác định bởi điều kiện $i^2=-1$.

Trong chuỗi này, mỗi lớp tiếp theo chứa tất cả các số của lớp trước và thêm các số “mới”. Với mỗi lần mở rộng lớp số, chúng ta có được khả năng thực hiện trong mọi trường hợp một số hành động nhất định không phải lúc nào cũng khả thi đối với các số “cũ”. Như vậy, trong lớp số nguyên, phép trừ luôn thực hiện được, còn trong lớp số hữu tỷ, phép chia luôn thực hiện được; trong lớp số thực, không chỉ bốn phép tính số học luôn khả thi, mà - đối với các số dương - rút ra căn bậc hai và nói chung là nâng lên lũy thừa thực bất kỳ, cũng như tìm logarit. Cuối cùng, như Gauss (1777–1855) đã chứng minh vào năm 1799, *các phương trình đại số* ở bất kỳ mức độ nào luôn có thể giải được dưới dạng số phức: phương trình
$$
a_0z^n+a_1z^{n-1}+\ldots+a_n=0,\tag1
$$
trong đó $n$ là số tự nhiên và các hệ số phức, có nghiệm phức $n$. Thậm chí trước đó (1748), Euler đã xây dựng lý thuyết về hàm mũ, logarit, lượng giác và hàm nghịch đảo của chúng trong một lập luận phức.

Trong bài viết này, chúng ta sẽ xem xét một cách phân loại số khác, cụ thể là chia chúng thành *đại số* và *không đại số* (nếu không thì - *siêu nghiệm*).

Sự định nghĩa. *Một số được gọi là đại số nếu có một phương trình đại số với các hệ số nguyên có nghiệm của nó.*

Chúng tôi nhấn mạnh rằng để một số có tính chất đại số thì phương trình (1) mà nó thỏa mãn phải có hệ số nguyên (hoặc có thể rút gọn thành phương trình như vậy).

Rõ ràng, các số hữu tỷ là đại số: $\dfrac pq$ là nghiệm của phương trình $qz-p=0$ với các hệ số nguyên $q$ và $-p$. Số đại số là nghiệm của phương trình bậc hai có hệ số nguyên, ví dụ: số $i$ (gốc của phương trình $z^2+1=0$), số $-\sqrt5-1$ (gốc của phương trình $z^2+2z-4=0$), số $1-i\sqrt5$ (gốc của phương trình $z^2-2z+6=0$).

### Các số siêu việt có tồn tại không?

Câu hỏi được đặt ra một cách tự nhiên: có những con số siêu việt nào không?

Số dương đáp số được nhà toán học người Pháp Liouville (1809–1882) đưa ra cho nó vào năm 1844. Năm 1873, Hermite chứng minh sự siêu việt của số $e$, năm 1882 Lindemann - sự siêu việt của số $\pi$. Năm 1900, tại Đại hội các nhà toán học quốc tế lần thứ II ở Paris, D. Hilbert (1860-1940), trong số 23 bài toán ông đặt ra và trở nên nổi tiếng, đã đưa ra bài toán thứ bảy: *là các số có dạng $\alpha^\beta$ siêu việt, trong đó $\alpha$ là số đại số khác 0 và 1, và $\beta$ là số đại số vô tỷ*?

Câu trả lời tích cực đáp số cho câu hỏi này được nhà toán học xuất sắc Liên Xô A. O. Gelfond (1906-1968) đưa ra vào năm 1934.

### kết quả Liouville

Trong phần tiếp theo, chúng ta sẽ giả sử rằng số đại số và số siêu việt là số thực, mặc dù mọi thứ vẫn đúng đối với số phức (xem bài tập ở cuối bài viết).

Định lý 1. *Cho $\alpha$ là một số vô tỷ là nghiệm của phương trình*
$$
f(z)\equiv a_0z^n+a_1z^{n-1}+\ldots+a_n=0.\tag2
$$
*Sử dụng các hệ số của phương trình và $A\ge|\alpha|$ tùy ý, người ta có thể tìm thấy một số $M$ sao cho mọi phân số $\dfrac pq$, $\left|\dfrac pq\right|\le A$ không phải là nghiệm của phương trình (2), thì bất đẳng thức sau đây đúng*
$$
\left|\alpha-\dfrac pq\right|\ge\dfrac1{Mq^n}.\tag3
$$

Bằng chứng. Theo điều kiện của định lý ta có:
$$
\begin{gather*}
f(\alpha)=a_0\alpha^n+a_1\alpha^{n-1}+\ldots+a_{n-1}\alpha+a_n=0,\\
f{\left(\dfrac pq\right)}=a_0{\left(\dfrac pq\right)^n}+a_1{\left(\dfrac pq\right)^{n-1}}+
a_{n-1}\dfrac pq+a_n\ne0.
\end{gather*}
$$
Từ đây
$$
\begin{gather*}
f{\left(\dfrac pq\right)}=f{\left(\dfrac pq\right)}-f(\alpha)=a_0{\left[{\left(\dfrac pq\right)^n}-\alpha^n\right]}+a_1{\left[{\left(\dfrac pq\right)^{n-1}}-\alpha^{n-1}\right]}+
\ldots+a_{n-1}{\left(\dfrac pq-\alpha\right)}=\\
={\left(\dfrac pq-\alpha\right)}{\left\{a_0{\left[{\left(\dfrac pq\right)^{n-1}}+
{\left(\dfrac pq\right)^{n-2}}\alpha+\ldots+\dfrac pq\alpha^{n-2}+\alpha^{n-1}\right]}+{}\right.}\\
{\left.{}+a_1{\left[{\left(\dfrac pq\right)^{n-2}}+{\left(\dfrac pq\right)^{n-3}}\alpha+\ldots+\alpha^{n-2}\right]}+\ldots+a_{n-1}\right\}}.
\end{gather*}
$$
Vì $|\alpha|\lt A$, $\left|\dfrac pq\right|\le A$, thì $$
\left|f{\left(\dfrac pq\right)}\right|\le{\left|\dfrac pq-\alpha\right|}M,\tag4
$$
ở đâu $$
M=|a_0|nA^{n-1}+|a_1|(n-1)A^{n-2}+\ldots+|a_{n-1}|.\tag5
$$
Nhưng $$
\left|f{\left(\dfrac pq\right)}\right|=\dfrac{|a_0p^n+a_1p^{n-1}q+\ldots+a_nq^n|}{q^n}.\tag6
$$

Trong tử số của phân số (6) $a_0$, $a_1$, $\ldots$, $a_n$, $p$, $q$ là số nguyên nên tử số (6) là số nguyên và vì $f{\left(\dfrac pq\right)}\ne0$ nên không nhỏ hơn một. Kể từ đây,
$$
\left|f{\left(\dfrac pq\right)}\right|\ge\dfrac1{q^n}.\tag7
$$
Từ (4) và (7) suy ra (3). Định lý đã được chứng minh.

Định lý 2. *Số*
$$
\alpha=c_0+\dfrac{c_1}{10}+\dfrac{c_2}{10^{2!}}+\dfrac{c_3}{10^{3!}}+\ldots+\dfrac{c_k}{10^{k!}}+{\ldots},
$$
*trong đó $c_0$ là số nguyên tùy ý và $c_1$, $c_2$, $\ldots$ lấy một trong các giá trị* 0, 1, 2, $\ldots$, 9 *và không bằng 0 trong một hàng, bắt đầu từ một điểm nhất định - siêu việt.*

Bằng chứng. Hãy đặt
$$
c_0+\dfrac{c_1}{10}+\dfrac{c_2}{10^{2!}}+\ldots+\dfrac{c_k}{10^{k!}}=\dfrac pq.\tag8
$$
Sau đó
$$
\alpha-\dfrac pq=\dfrac{c_{k+1}}{10^{(k+1)!}}+\dfrac{c_{k+2}}{10^{(k+2)!}}+\ldots\gt0,
$$
và vì $q=10^{k!}$, nên $$
\alpha-\dfrac pq=\dfrac{c_{k+1}}{q^{k+1}}+\dfrac{c_{k+2}}{q^{(k+1)(k+2)}}+{\ldots}.
$$
Từ đây
$$
\alpha-\dfrac pq\le9{\left(\dfrac1{q^{k+1}}+\dfrac1{q^{(k+1)(k+2)}}+\ldots\right)}\lt\dfrac9{(q-1)q^k}.\tag9
$$

Để chứng minh tính siêu việt của số $\alpha$, chúng ta hãy giả sử điều ngược lại—rằng nó là đại số; thì $\alpha$ thỏa mãn phương trình (1), các hệ số của nó là số nguyên. Chúng ta hãy biểu thị bằng $d$ khoảng cách ngắn nhất từ ​​nghiệm $\alpha$ đến các nghiệm thực khác của phương trình.

Đặt $A=|\alpha|+d$, ta tính số $M$ theo công thức (5) và chọn số tự nhiên $k$ lớn sao cho đồng thời thỏa mãn ba bất đẳng thức sau:
$$
k\gt n,\quad\dfrac9{(q-1)q^k}\lt d,\quad\dfrac9{(q-1)q^{k-n}}\lt\dfrac1M.\tag{10}
$$

Do bất đẳng thức (9) và trung bình của các điều kiện (10), $\dfrac pq$ nhỏ hơn $\alpha$. trên $d$, và do đó không phải là nghiệm của phương trình (1). Kể từ $$
\left|\dfrac pq\right|=\left|\alpha-\left(\alpha-\dfrac pq\right)\right|\le|\alpha|+\left|\alpha-\dfrac pq\right|\lt|\alpha|+d=A,
$$
thì các điều kiện của Định lý 1 được thỏa mãn, và do đó,
$$
\left|\alpha-\dfrac pq\right|\ge\dfrac1{Mq^n}.\tag{11}
$$

Mặt khác, từ bất đẳng thức (9) và điều kiện cuối cùng (10)
$$
\left|\alpha-\dfrac pq\right|\lt\dfrac1{Mq^n}.\tag{12}
$$

Như vậy, giả sử $\alpha$ là số đại số dẫn đến các bất đẳng thức trái ngược nhau (11) và (12). Do đó, $\alpha$ là một số siêu việt.

Vì vậy, Định lý 2 cho phép chúng ta xây dựng các số siêu việt. Cụ thể, một số siêu việt có thể thu được từ bất kỳ phân số vô hạn nào trong đó không phải tất cả các chữ số, bắt đầu từ một số, đều là số 0, bằng cách sử dụng phương pháp sau: bạn cần đặt chữ số thứ $k$ sau dấu thập phân vào vị trí của số $k!$ và điền số 0 vào các vị trí còn lại. Ví dụ: từ số $0{,}314159\ldots$ thu được số siêu việt sau:
$$
\def\A#1{\mathclap{\footnotesize\begin{array}{c}\text{#1-е}\\\text{место}\end{array}}}
\def\colsep#1#2{#2}
\colsep{0pt}{\begin{array}{ccccccc}
0{,}31000&4&0\ldots0&1&0\ldots0&5&0\ldots\\
&\mathclap\downarrow&&\mathclap\downarrow&&\mathclap\downarrow&\\
&\A{6}&&\A{24}&&\A{120}&
\end{array}}
$$

### Phần kết luận

Một mặt, các số thực siêu việt là một phần của mọi số thực. Nhưng ví dụ được đưa ra ở cuối đoạn trước cho thấy rằng theo một nghĩa nào đó, có “nhiều” số siêu việt như số thực, chính xác theo nghĩa là từ mọi số thực (trừ số thập phân hữu hạn) có thể hình thành một số siêu việt.

Tuy nhiên, theo một nghĩa khác *hầu hết mọi số thực đều là số siêu việt, trong khi số đại số chỉ chiếm một phần không đáng kể của số thực*!

Năm 1878, nhà toán học người Đức G. Cantor (1845-1918) đã chứng minh rằng các số đại số có thể được đánh số sao cho mỗi số đại số sẽ nhận được một số riêng và dưới mỗi số sẽ có một số đại số (xem Phụ lục). Ta lấy một đoạn có độ dài nhỏ tùy ý, ví dụ chiều dài $\eps=10^{-15}$ cm (nhớ lại rằng bán kính electron xấp xỉ $10^{-12}$ cmt). Sau khi mô tả số thực dưới dạng các điểm trên trục số, ta phủ điểm đại số số 1 bằng một đoạn có độ dài $\dfrac12\eps$, điểm đại số số 2 - đoạn có độ dài $\dfrac1{2^2}\eps$, điểm đại số số$n$ - một đoạn dài - $\dfrac1{2^n}\eps$ v.v. Tổng chiều dài của các đoạn phủ bằng $\eps$, mặc dù chúng trùng nhau một phần và không chỉ bao gồm tất cả các số đại số mà còn bao gồm một số số siêu việt. Toàn bộ trục số là vô hạn và tổng độ dài của các đoạn bao phủ các điểm đại số chỉ bằng một phần nghìn bán kính của electron! Điều này cho thấy rõ ràng rằng hầu hết mọi số đều là số siêu việt, trong khi số đại số là những trường hợp ngoại lệ hiếm hoi.

### Ứng dụng

Chúng ta hãy gọi *thứ hạng của phương trình* (1) là số $r$:
$$
r=n+|a_0|+|a_1|+\ldots+|a_n|;\tag{13}
$$
ở đây $n\ge1$, $|a_0|\ge1$, do đó $r\ge2$.

Với mọi số tự nhiên $r\ge2$, phương trình bất định (13) có số hữu hạn lời giải là số nguyên không âm. Do đó, có một số hữu hạn các phương trình của mỗi hạng. Ví dụ: xếp hạng 2 - hai phương trình: $\pm x=0$; hạng 3 - sáu phương trình:
$$
\pm x^2=0,\quad \pm x\pm1=0;
$$
hạng 4 - phương trình
$$
\pm x^3=0,\quad\pm x^2\pm x=0,\quad\pm x^2\pm1=0,\quad\pm x\pm2=0,\quad\pm2x\pm1=0.
$$
Chúng ta hãy tìm nghiệm của các phương trình này và viết chúng lần lượt: đầu tiên là nghiệm của phương trình bậc 2, sau đó là nghiệm của phương trình bậc 3, v.v.; Chúng ta viết ra nghiệm của các phương trình cùng hạng theo bất kỳ thứ tự nào và nếu một số là nghiệm của một số phương trình thì chúng ta chỉ viết nó ra một lần. Ta được dãy số:
$$
0,~1,~{-1},~i,~{-i},~2,~{-2},~\dfrac12,~{-\dfrac12},
$$
hơn nữa - nghiệm của phương trình hạng 5, v.v.

Do đó, mỗi số đại số sẽ được viết ra và nhận số sê-ri riêng trong dãy. Nếu người ta chỉ quan tâm đến số đại số thực thì số phức sẽ bị bỏ qua.

### Bài tập

1. Chứng minh rằng số
$$
\alpha=c_0+\dfrac{c_1}2+\dfrac{c_2}{2^{2!}}+\ldots+\dfrac{c_k}{2^{k!}}+{\ldots},
$$
trong đó $c_0$ là số nguyên và $c_1$, $c_2$, $\ldots$ lấy một trong các giá trị 0 hoặc 1 và là giá trị siêu việt.
2. Chứng minh rằng Định lý 2 cũng đúng nếu các số $\{c_k\}$ lấy bất kỳ giá trị nguyên nào bị giới hạn trong tổng, nghĩa là nếu có một hằng số $B$ sao cho $|c_k|\lt B$ cho tất cả các giá trị của chỉ số $k$.
3. Chứng minh rằng trong Định lý 2 ta có thể đặt
$$
\alpha=c_0+\dfrac{c_1}{10^{n_1}}+\dfrac{c_2}{10^{n_2}}+{\ldots},
$$
trong đó $\{n_k\}$ là dãy số tự nhiên bất kỳ tuân theo điều kiện
$$
n_{k+1}\ge\lambda_kn_k,\quad k=1{,}~2{,}~{\ldots},
$$
và $\{\lambda_k\}$ là một dãy số thực tăng vô hạn tùy ý, ví dụ: $\lambda_k=\lg k$.

Trong các bài tập sau, khi *số phức nguyên* chúng tôi muốn nói đến một số có dạng $a+bi$, khi *phức hợp hữu tỷ* chúng tôi muốn nói đến số $\dfrac{a+bi}q$, trong đó $a$, $b$ là số nguyên, $q$ là số tự nhiên và $i$ là số sao cho $i^2=-1$.

1. Chứng minh rằng nếu số $\alpha$ thỏa mãn phương trình (1) với hệ số nguyên phức thì đó là số đại số.
2. Chứng minh rằng Định lý 1 đúng nếu, trong điều kiện của nó, $\alpha$ là số vô tỷ phức và $\dfrac pq$ là số hữu tỉ phức.
3. Chứng minh Định lý 2 và các mệnh đề trong bài tập 1, 2, 3 cũng đúng khi các hệ số $\{c_k\}$ lấy giá trị nguyên phức.
