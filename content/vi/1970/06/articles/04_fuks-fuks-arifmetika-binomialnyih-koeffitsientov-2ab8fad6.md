---
id: 1970-6-fuks-fuks-arifmetika-binomialnyih-koeffitsientov-2ab8fad6
issue: kvant_1970_6
year: 1970
number: "6"
title: Số học các hệ số nhị thức
authors:
  - Фукс Д. Б.
  - Фукс М. Б.
rubric: osnovnye-stati
page_first: 19
page_last: 25
page_labels: 17, 18, 19, 20, 23
tag: 8T3Q
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c941444033cb06c84417e4759cd09bf913e399c2dc09169185995032a724e15b
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1970/06/articles/04_fuks-fuks-arifmetika-binomialnyih-koeffitsientov-2ab8fad6.md
source_content_sha256: 5dc611f72f1af7ee464ada7ee74ae3df84aede3de83d0e5b359318c912615bb5
translation_model: gpt-5-6
translation_run: m10-1970-vi
---

⟦folio 17⟧

SỐ HỌC
CÁC HỆ SỐ
NHỊ THỨC

Đ. B. Phúc, M. B. Phúc

$(1+x)^2=1+2x+x^2$
$(1+x)^3=1+3x+3x^2+x^3$

Mọi học sinh đều biết các công thức này. Các số 1, 2, 1; 1, 3, 3, 1, cũng như các số nhận được theo cách tương tự khi nâng lên các lũy thừa 4, 5, ..., được gọi là các hệ số nhị thức. Bài báo này kể về các tính chất khác nhau của các hệ số nhị thức. Trong phần thứ nhất trình bày «lý thuyết chung»: phần lớn các định lý được chứng minh ở đây trước kia đã nằm trong chương trình học phổ thông. Trong phần thứ hai, chúng tôi chỉ ra cách có thể rất dễ dàng tìm số dư khi chia bất kỳ hệ số nhị thức nào cho bất kỳ số nguyên tố nào. Một số khẳng định của phần này được phát biểu dưới dạng giả thuyết. Có thể các độc giả của «Kvant» sẽ thử chứng minh chúng.

⟦folio 18⟧

§ 1. Định nghĩa và các tính chất đơn giản nhất của các hệ số nhị thức

Nếu nhị thức (binom) $1+x$ được nâng lên một lũy thừa tự nhiên nào đó $n$, thì rõ ràng sẽ thu được một đa thức bậc $n$ (tức là bậc lớn nhất mà $x$ xuất hiện trong đa thức này sẽ bằng $n$). Ví dụ:

$$(1+x)^0 = 1,$$
$$(1+x)^1 = 1+x,$$
$$(1+x)^2 = 1+2x+x^2,$$
$$(1+x)^3 = 1+3x+3x^2+x^3,$$
$$(1+x)^4 = 1+4x+6x^2+4x^3+x^4,$$
$$(1+x)^5 = 1+5x+10x^2+10x^3+$$
$$+5x^4+x^5,$$

Hệ số của các đa thức này được gọi là nhị thức. Đối với chúng có các ký hiệu đặc biệt: hệ số của $x^m$ trong $(1+x)^n$ được ký hiệu là $C_n^m$. Ví dụ, $C_2^1=2$, $C_4^2=6$, $C_5^3=10$. Trong các sách giáo khoa đại số cũ, số $C_n^m$ được gọi là «số tổ hợp chập $m$ của $n$». Điều đó có những lý do riêng, nhưng chúng ta không

Từ đó dễ dàng thu được rằng

$$(a+x)^n = C_n^0a^n + C_n^1a^{n-1}x\ldots$$
$$\ldots + C_n^nx^n$$

(chỉ cần áp dụng công thức (1) vào việc tính $(1+x)a^n$ và nhân cả hai vế của đẳng thức nhận được với $a^n$). Công thức cuối cùng được gọi là nhị thức Newton. Từ đó có tên gọi của các hệ số — hệ số nhị thức.

Rõ ràng $C_n^m$ là các số nguyên không âm và $C_n^m=0$ khi $m>n$ (đa thức $(1+x)^n$ có bậc $n$, và $x^m$ với $m>n$ không xuất hiện trong nó). Tiếp theo, dễ dàng nhận thấy rằng $C_n^0=C_n^1=1$. Các hệ số nhị thức khác $C_n^m$, với $0<m<n$, có thể tìm được bằng cách nâng $1+x$ lên các lũy thừa khác nhau. Các giá trị của chúng với $n\leqslant10$ được đưa ra trong bảng.

Ta thấy rằng các hệ số nhị thức là những số tăng khá nhanh. Độc giả tinh ý sẽ nhận thấy trong cách sắp xếp các số này một loạt quy luật. Thông thường, những quy luật như vậy dễ dàng suy ra từ định nghĩa của các hệ số nhị thức. Ở đây chúng tôi chỉ chứng minh những quy luật chính. Bắt đầu với quy luật quan trọng nhất — cái gọi là đẳng thức Pascal.

Ta sẽ đánh dấu chúng: đối với chúng ta điều này không quan trọng. Vậy,

$$(1+x)^n = C_n^0+C_n^1x+C_n^2x^2+\ldots$$
$$\ldots +C_n^nx^n.$$

(1)

Định lý 1 (đẳng thức Pascal).

$$C_n^m = C_{n-1}^m+C_{n-1}^{m-1}$$

(2)

với mọi số tự nhiên $n, m$.

⟦folio 19⟧

Chứng minh. Theo định nghĩa, $C_n^m$ là hệ số của $x^m$ trong đa thức $(1+x)^n$. Để tìm hệ số này, cần nhân $n$ đa thức đều bằng $1+x$. Nhân $n-1$ trong số đó, ta được đa thức $1+C_{n-1}^1x + C_{n-1}^2x^2 + \dots + x^{n-1}$. Thực hiện phép nhân cuối cùng, ta được

$$(1+x)(1+C_{n-1}^1x + C_{n-1}^2x^2 + \dots + x^{n-1}) = 1 + C_{n-1}^1x + C_{n-1}^2x^2 + \dots + x^{n-1} + x + C_{n-1}^1x^2 + C_{n-1}^2x^3 + \dots + x^n = 1 + (C_{n-1}^1 + 1)x + (C_{n-1}^2 + C_{n-1}^1)x^2 + \dots + x^n.$$

Trong biểu thức thu được, hệ số của $x^m$ bằng $C_{n-1}^m + C_{n-1}^{m-1}$. Do đó,

$$C_n^m = C_{n-1}^m + C_{n-1}^{m-1}.$$

Đồng nhất thức Pascal thuận tiện cho việc tính các hệ số nhị thức. Chẳng hạn, nếu muốn bổ sung thêm một hàng vào bảng của chúng ta (hàng thứ mười một), chỉ cần cộng từng cặp các số đứng cạnh nhau trong hàng trước đó (hàng thứ mười):

$$C_{11}^0 = 1 \quad C_{11}^1 = C_{10}^1 + C_{10}^0 = 11 \quad C_{11}^2 = C_{10}^2 + C_{10}^1 = 55 \quad C_{11}^3 = C_{10}^3 + C_{10}^2 = 165 \quad C_{11}^4 = C_{10}^4 + C_{10}^3 = 330 \quad C_{11}^5 = C_{10}^5 + C_{10}^4 = 462$$

Từ đó thấy rằng các hệ số nhị thức thuận tiện được viết dưới dạng một bảng tam giác (xem chú thích-

3*

⟦folio 20⟧

Như vậy, công thức (3) đúng với $n=1$, và từ tính đúng đắn của nó đối với $n-1$ suy ra rằng nó đúng đối với $n$. Bằng cách đó, công thức (3) được chứng minh với mọi $n$.

Chúng tôi khuyên người đọc, khi lần đầu làm quen với công thức (3), hãy suy ra từ nó những đẳng thức đã biết $C_n^0 = C_n^n = 1$ và $C_n^m = 0$ khi $m>n$.

Công thức (3) thú vị ngay ở chỗ phân số ở vế phải của nó bằng một số nguyên, tức là tất cả các số đứng ở mẫu số của nó sẽ rút gọn với các số đứng ở tử số.

Định lý sau đây sẽ được sử dụng về sau.

Định lý 3. Nếu các số $n$ và $m$ nguyên tố cùng nhau (tức là ước chung lớn nhất của các số $n$ và $m$ bằng 1), thì $C_n^m$ chia hết cho $n$.

Chứng minh:

$$C_n^m = \frac{n(n-1)\ldots(n-m+1)}{1\cdot2\ldots m} = \frac{n}{m} \cdot \frac{(n-1)\ldots(n-m+1)}{1\cdot2\ldots(m-1)} = \frac{n}{m} \cdot C_{n-1}^m$$

Như vậy,

$$mC_n^m = nC_{n-1}^m$$

t. е. число $mC_n^m$ делится на $n$. Но так как $m$ и $n$ взаимно просты, т. е. $m$ не делится ни на один простой делитель числа $n$, то $C_n^m$ делится на $n$.

Ví dụ, $C_9^4 = 126$ chia hết cho 9, $C_{10}^3 = 120$ chia hết cho 10.

Nêu thêm một số tính chất của các hệ số nhị thức:

1. $C_n^m = C_{n-1}^m$
2. $C_n^m + C_{n+1}^m + \ldots + C_{m+k}^m = C_{m+k+1}^m$
3. $C_n^0 + C_n^1 + \ldots + C_n^n = 2^n$
4. $C_n^0 + C_n^2 + C_n^4 + \ldots = C_n^1 + C_n^3 + C_n^5 + \ldots$

Các chứng minh của những tính chất này dành cho bạn đọc.

§ 2. Các phần dư khi chia các hệ số nhị thức cho các số nguyên tố

Trong (cũng như trong đoạn tiếp theo) này, chúng ta sẽ phải thường xuyên sử dụng dạng «các số $a$ và $b$ có các số dư bằng nhau khi chia cho $p$». Người ta thay dạng dài này bằng ký hiệu rút gọn «$a \equiv b$ (mod $p$)». Nói cách khác, công thức «$a \equiv b$ (mod $p$)» có nghĩa là $a-b$ chia hết cho $p$. Ví dụ, $4 \equiv 1$ (mod 3), $999999 \equiv 222222$ (mod 7) v.v. Công thức «$a \equiv b$ (mod $p$)» đôi khi được đọc như sau: «số $a$ đồng dư với số $b$ theo modulo $p$» (tuy nhiên, chúng ta cũng sẽ không dùng các cách diễn đạt này).

Вот два очень важных свойства символа ≡:

1. Если $a \equiv b$ (mod $p$) и $k$ — целое число, то $ka \equiv kb$ (mod $p$).

Действительно, если $a-b$ делится на $p$, то и $ka-kb = k(a-b)$ делится на $p$.

2. Если $a \equiv b$ (mod $p$) и $b \equiv c$ (mod $p$), то $a \equiv c$ (mod $p$).

Thật vậy, nếu $a-b$ chia hết cho $p$ và $b-c$ chia hết cho $p$, thì cả $a-c = (a-b)+(b-c)$ cũng chia hết cho $p$.

Nhắc lại rằng mọi số tự nhiên $a$ đều có thể chia cho số tự nhiên $p$ «có dư», tức là $a$ có thể được viết một cách duy nhất dưới dạng $a=bp+c$, trong đó $b$, $c$ là các số nguyên sao cho $0 \leq c < p$.

Mục đích chính của đoạn này là chứng minh khẳng định sau.ьство khẳng định sau.

Định lý 4. Cho $p$ — là một số nguyên tố, $m$ và $n$ — là các số tự nhiên. Tiếp theo, cho $k$ và $l$ — là các thương khi chia các số $m$ và $n$ cho $p$, còn $s$ và $t$ — là các số dư (tức là $m=kp+s$, $n=lp+t$, trong đó $k$, $l$, $s$, $t$ — là các số nguyên và $0 \leq s < p$, $0 \leq t < p$). Khi đó

$$C_n^* = C_l^* \cdot C_s^* \pmod p.$$

Như chúng ta sẽ thấy dưới đây, định lý này cho phép tìm các số dư khi chia các hệ số nhị thức cho các số nguyên tố, hầu như không cần thực hiện tính toán.

⟦folio 23⟧

sao cho $C_{119}^{33} \equiv 0$ (mod 3), tức là $C_{119}^{33}$ chia hết cho 3.

Lưu ý rằng nếu chúng ta áp dụng định lý 4 của mình cho $C_n^m$, trong đó $n \geq m$, thì, khi viết $m = kp + s$, $n = lp + t$, tất nhiên chúng ta sẽ có $l \geq k$; tuy nhiên không thể dự đoán được số nào trong hai số $s$, $t$ sẽ lớn hơn. Nếu $s > t$, thì theo định lý của chúng ta $C_n^m \equiv C_l^k C_s^t = 0$ (mod $p$), nghĩa là $C_n^m$ chia hết cho $p$. Như đã thấy, để xác định số dư khi chia số $C_n^m$ cho $p$, nói chung cần sử dụng định lý 4 nhiều lần; và mỗi lần có thể xuất hiện hiện tượng tương tự như đã mô tả ở trên, hơn nữa, bất cứ khi nào điều này xảy ra, điều đó có nghĩa là cả số ban đầu $C_n^m$ cũng chia hết cho $p$. Theo cách tương tự, chúng ta đã thu được rằng $C_{119}^{33}$ chia hết cho 3.

Ta thấy rằng $n$ càng lớn thì càng có khả năng số $C_n^m$ chia hết cho $p$. Dễ dàng chứng minh khẳng định chính xác hơn sau đây: tổng cộng có $\frac{p^r (p^r + 1)}{2}$ số $C_n^m$ với $0 \leq n \leq p^r$, $0 \leq m \leq n$, trong số đó không chia hết cho $p$ đúng $\frac{p^r (p + 1)^r}{2^r}$ số (ở đây $p$ là số nguyên tố, $r$ là số tự nhiên; chứng minh chỉ dựa vào định lý 3, chúng tôi để lại cho bạn đọc). Nhấn mạnh rằng khi $r$ lớn, các số $\frac{p^r (p + 1)^r}{2^r}$ nhỏ hơn nhiều lần so với số $\frac{p^r (p^r + 1)}{2}$.

Так, например, из чисел $C_n^m$ с $0 \leq n \leq 3^5$, $0 \leq m \leq n$ не делятся на 3 примерно 26,2%; если $0 \leq n \leq 3^{10}$, то примерно 3,6%, а если $0 \leq n \leq 3^{15}$, то примерно 0,45%.

В заключение скажем несколько слов о весыта наглядной интерпретации теоремы 4, которое можно получить, рассматривая так называемый «треугольник Паскаля по модели $p$». Так называется треугольная таблица, которая получится из треугольника Паскаля, если в нем заменить каждое число его остатком от деления на $p$. Мы не доказываем про этот треугольник никаких теорем, но предлагаем читателю посмотреть две картины (на обложке и на стр. 22), на которых изображены треугольники Паскаля по модулям 2 и 3. Подумайте, как устроены эти треугольники в той части, которая не видна на рисунке. Постраайтесь формулировать теорему 4 таким образом, чтобы она стала теоремой об устройстве треугольника Паскаля по модуляю $p$.

§ 3. Немного об остатках от деления биомиальных коэффициентов на степени простых чисел

Мы не рассматриваем в сколькоибудь общей постановке вопрос об остатках от деления биомиальных коэффициентов на составные числа. (Впрочем, читатель может подумать об этом сам; чему, например, равен остаток от деления числа $C_{119}^{33}$ на 4: единице или trem?) Мы ограничимся тем, что расскажем об одном удивительном, до конца не обьясенном нами явлении.

Начнем с некоторых вычислений. Пользовясь формулой биомиальных коэффициентов (см. § 1, формула (2)), получаем

$$C_2^1 = 2,$$
$$C_4^2 = 6,$$
$$C_8^4 = 70,$$
$$C_{16}^8 = 12870,$$
$$C_{32}^16 = 601080390.$$

(Все знают, конечно, что 1, 2, 4, 8, 16, 32, ... — это последовательные степени двойки.) Сами полученные числа исчем особенным не применять; их последовательные разности, однако, обнаруживают порAZительные свойства. Посмотрим на них:порAZительные свойства. Посмотрим на них:

$$6 - 2 = 4 = 2^2,$$
$$70 - 6 = 64 = 2^6,$$
$$12870 - 70 = 12800 = 2^9 \cdot 25,$$
