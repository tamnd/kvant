---
id: 1978-12-resheniya-zadach-m491-m493-f503-f505-f507-850d2d0b
issue: kvant_1978_12
year: 1978
number: "12"
title: Lời giải bài toán M491—M493; F503, F505—F507
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 26
page_last: 35
page_labels: 24-33
tag: ZOFL
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 236c2e0e1d80faaa505172dfd74f0b8832fb7862b6e07f3372092936b19726be
prompt_sha256: draft-1
translated_from: content/ru/1978/12/articles/08_resheniya-zadach-m491-m493-f503-f505-f507-850d2d0b.md
source_content_sha256: 5c475750fe0dd817338690131b4f3b2f670938a6fdff17716e937a0777ecd7c4
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 24⟧

Lời giải bài toán
M491—M493; F503, F505—F507

M491. Khoảng cách cắt hình học, tất cả các phần đều được điền số. (Ví dụ: 16, 24, 36, 54, 81.)
a) Chứng minh rằng tổng bình phương của ba mục tiêu cắt liên tiếp chia hết cho tổng các mục tiêu này.
b) Tại giá trị n tự nhiên nào thì tổng bình phương của n mục tiêu cắt liên tiếp chia cho tổng của n mục tiêu này?

Trước tiên chúng ta sẽ giải bài toán M491 - chứng minh khẳng định điểm a) và trả lời câu hỏi điểm 6), sau đó xây dựng khẳng định từ đó cả hai điểm bài toán sẽ tuân theo.

a) Chúng ta hãy biểu thị ba mục tiêu liên tiếp mà chúng ta cắt qua $a_1, a_2, a_3$ (tất cả $a_i$ đều là các mục tiêu số). Vì $a_1 a_3 = a_2^2$, chúng ta nhận được
$$\left( a_1 + a_2 + a_3 \right)^2 = \left( a_1^2 + a_2^2 + a_3^2 \right) + 2 a_2 \left( a_1 + a_2 + a_3 \right),$$
theo
$$a_1^2 + a_2^2 + a_3^2 = \left( a_1 + a_2 + a_3 \right) \left( a_1 - a_2 + a_3 \right)$$
- đó là điều cần phải chứng minh.

6) Thật dễ dàng để đưa ra một ví dụ về cách cắt hình học trong đó tổng bình phương của bốn mục tiêu liên tiếp sẽ không chia cho tổng của các mục tiêu này: đối với việc cắt 1, 2, 4, 8, 16, ... tổng $1^2 + 2^2 + 4^2 + 8^2 = 85$ không chia hết cho tổng $1 + 2 + 4 + 8 = 15$. Nói chung, đối với khía cạnh này, tổng bình phương của 2k mục tiêu đầu tiên $1 + 2^2 + 2^4 + \dots + 2^{4k-2} = (2^{4k} - 1)/3$ không chia hết cho tổng của các mục tiêu này $1 + 2 + 2^2 + \dots + 2^{2k-1} = 2^{2k} - 1$, vì $2^{2k} + 1$ không chia hết cho 3 hoặc một số $k$. Vì vậy ngay cả $n$ cũng không phù hợp. Nếu $n$ là số lẻ ($n = 2k + 1$), thì tổng bình phương $n$ luôn chẵn trên đường cắt 所学 nhất thiết phải chia cho tổng của các mục tiêu này. Tuyên bố này là đúng và theo sau phần trình bày
$$a_1^2 + a_2^2 + \dots + a_{2k+1}^2 = \left( a_1 + a_2 + \dots + a_{2k+1} \right) \times \left( a_1 - a_2 + a_3 - a_4 + \dots - a_{2k} + a_{2k+1} \right),$$
điều này dễ chứng minh, chẳng hạn bằng quy nạp.

Bây giờ hãy xây dựng và chứng minh tuyên bố được đề cập ở trên.

Định lý. Nếu các số $k$ và $n$ là số nguyên tố cùng nhau thì tổng lũy ​​thừa $k-x$ $n$ liên tiếp của việc cắt các mục tiêu, tất cả đều là thành phần của số, nhất thiết phải được chia cho tổng của các mục tiêu này.

(Vì số 3 và 2 là nguyên tố cùng nhau nên câu này ngụ ý điểm a) bài toán M491 và đáp số đến điểm b) - cho số lẻ $n$.)
Bằng chứng. Chúng ta hãy biểu thị $n$ mục tiêu cắt liên tiếp này bằng $a_1, a_2, \dots, a_n$. Chúng ta muốn chứng minh rằng tổng $a_1^k + a_2^k + \dots + a_n^k$ chia hết cho tổng $a_1 + a_2 + \dots + a_n$ (giả sử rằng $k$ và $n$ là nguyên tố cùng nhau). Đặt $q$ là mẫu số của vết cắt. Sau đó
$$a_1 + a_2 + \dots + a_n = a_1 (1 + q + \dots + q^{n-1}),$$
$$a_1^k + a_2^k + \dots + a_n^k = a_1^k (1 + q^k + \dots + q^{(n-1)} k).$$
Hãy chứng minh rằng nếu $k$ và $n$ nguyên tố cùng nhau thì đa thức $1 + x^k + \dots + x^{n-1}$ chia hết cho đa thức $1 + x + \dots + x^{n-1}$.*) Trong chứng minh chúng ta sẽ cần hai bổ đề phụ.

*) Ở đây và xuyên suốt bên dưới, khi nói về tính chia hết của đa thức, chúng tôi muốn nói rằng tất cả các hệ số của thương đều là số nguyên.

⟦folio 25⟧

Bổ đề 1. Nếu các số $k$ và $n$ nguyên tố cùng nhau thì các số $k, 2k, 3k, \dots, (n-1)$ $k$ khi chia cho $n$ cho các số dư khác nhau.

Bổ đề 2. Nếu các số $l$ và $m$ khi chia cho $n$ có ​​cùng số dư thì đa thức $x^l - x^m$ chia hết cho đa thức $1 + x + \dots + x^{n-1}$.

Bổ đề 1 chứng minh phương pháp bằng phản chứng. Trên thực tế, nếu đối với một số $i$ và $j$ ($0 < i < j < n$), các số $ik$ và $jk$ có cùng số dư khi chia cho $n$, thì số $(j-i)$ $k$ chia hết cho $n$. Nhưng số $j-i < n$; Điều này có nghĩa là các số $k$ và $n$ phải có ước chung khác một, mâu thuẫn với các số nguyên tố chung.

Vì số phần dư riêng biệt (không phải bằng 0!) khi chia cho $n$ bằng $n-1$, nên từ Bổ đề 1 suy ra rằng nếu các số $k$ và $n$ là nguyên tố cùng nhau, thì trong số các số dư từ phép chia cho $n$ các số $k, 2k, \dots, (n-1)$ $k$ đều là các số từ $1$ đến $n-1$ gặp nhau một lần.

Chúng ta hãy chứng minh Bổ đề 2. Giả sử $l > m$ và $l = m+pn$. Đa thức $x^m - x^l = (1-x^{pn})x^m$ chia hết cho $1-x^n$:

$$1-x^{pn} = (1-x^n) (1+x^n+x^{2n}+\dots+x^{(p-1)n}),$$

và $1-x^n$ chia hết cho $(1-x)$, và

$$(1-x^n) = (1-x) (1+x+x^2+\dots+x^{n-1}).$$

Điều này hàm ý phát biểu của Bổ đề 2.

Bây giờ chúng ta tiến hành chứng minh rằng đa thức $1+x^k + \dots + x^{(n-1)k}$ chia hết cho $1+x + \dots + x^{n-1}$. Chúng ta biểu thị bằng $k_i$ phần dư của phép chia cho $n$ của số $ik$. Khi đó, theo Bổ đề 2, đa thức $(x^k - x^{k_1}) + (x^{2k} - x^{k_2}) + \dots + (x^{(n-1)k} - x^{k_{n-1}})$ chia hết cho đa thức $1+x + \dots + x^{n-1}$. Cần lưu ý rằng, theo hệ quả tất yếu của Bổ đề 1, đa thức $1+x^{k_1} + x^{k_2} + \dots + x^{k_{n-1}}$ trùng với đa thức $1+x + \dots + x^{n-1}$ và do đó, chia hết cho nó. Như vậy,

$$1+x^k + x^{2k} + \dots + x^{(n-1)k} = (1+x + \dots + x^{n-1}) \times (c_0 + c_1x + c_2x^2 + \dots + c_px^p),$$

trong đó $p = (k-1)(n-1)$ và $c_0, c_1, \dots, c_p$ là một số số. Kể từ đây,

$$a_1^k + a_2^k + \dots + a_n^k = a_1^k (1+q^k + \dots + q^{(n-1)k}) = a_1^k (1+q + \dots + q^{n-1}) (c_0 + c_1q + c_2q^2 + \dots + c_pq^p) = (a_1 + a_2 + \dots + a_n) \times (c_0 a_1^{k-1} + c_1 a_1^{k-1} q + \dots + c_p a_1^{k-1} q^p).$$

Để hoàn thành việc chứng minh định lý, chỉ cần chứng minh các số $a_1^{k-1}q, a_1^{k-1}q^2, \dots, a_1^{k-1}q^p$ là số nguyên là đủ. Thật vậy, số $a_1^{k-1}q$ là một số nguyên, vì nó được biểu diễn dưới dạng tích của các số nguyên: $a_1^{k-1}q = a_1^{k-2}a_2$. Tương tự, $a_1^{k-1}q^2 = a_1^{k-2}a_3$, $\dots, a_1^{k-1}q^p = (a_1q^{n-1})^{k-1} = a_n^{k-1}$.

Cố gắng xây dựng các ví dụ cho thấy yêu cầu về tính đơn giản lẫn nhau của $k$ và $n$ trong phát biểu của định lý tồn tại.

A. Adaev, G. Gurevich, F. Kadirov

**M492. Tam giác $A_1B_1C_1$ được mô tả trong tam giác ABC (giả sử các đỉnh $A_1, B_1$ và $C_1$ lần lượt nằm trên các cạnh BC,**

Chúng tôi sẽ trình bày hai lời giải trong số bài toán này: cái thứ nhất mang tính “cơ khí” hơn, cái thứ hai mang tính “hình học” hơn.
Đầu tiên là lời giải. Chúng ta đặt trọng lượng của các khối lượng $a, b$ và $c$ tại các đỉnh của tam giác $ABC$ sao cho trọng tâm của hệ khối lượng này rơi vào điểm $P$. Đủ cho việc này

⟦folio 26⟧

CA và AB), các đoạn AA₁, BB₁ và CC₁ cắt nhau tại một điểm P. Chứng minh rằng các đường thẳng nối trung điểm của các cạnh AB và A₁B₁, BC và B₁C₁, CA và C₁A₁ cắt nhau tại một điểm P, Q và tâm tam giác ABC cùng nằm trên một đường thẳng.

Hình 1.

Hình 2.

việc thỏa mãn hai điều kiện: điều kiện $\frac{|AB_1|}{|B_1C|} = \frac{c}{a}$, đảm bảo rằng trọng tâm thuộc đường thẳng BB₁ và điều kiện $\frac{|AC_1|}{|C_1B|} = \frac{b}{a}$, đảm bảo rằng trọng tâm thuộc về đường thẳng CC₁. (Khi đó $\frac{|BA_1|}{|A_1C|} = \frac{c}{b}$; qua đó ta đã chứng minh thành công định lý Ceva:

$$\frac{|AB_1|}{|B_1C|} \cdot \frac{|CA_1|}{|A_1B|} \cdot \frac{|BC_1|}{|C_1A|} = 1.$$

Bây giờ chúng ta thêm tải có khối lượng $m = a + b + c$ vào mỗi đỉnh (Hình 1). Có thể tìm trọng tâm Q của toàn bộ hệ trọng lượng bằng cách nối các điểm P (trọng tâm của hệ ban đầu thứ nhất) và M (trọng tâm của tam giác ABC) với một đoạn và chia nó theo tỷ lệ $\frac{a+b+c}{3m} = \frac{1}{3}$, tính từ điểm M.

Mặt khác, khối lượng tại các đỉnh A (2a+b+c), B (2b+a+c), C (2c+a+b) có thể được phân bố thành các “hệ con” như sau: các phần của khối lượng A (a+c) và B ((a+c) b/a) được thay thế bằng khối lượng C₁ ((a+c) (a+b)/a); phần của khối lượng A(a+b) và C ((a+b) c/a) - khối lượng B₁ ((a+c) (a+b)/a). Hai khối lượng bằng nhau tạo thành tại các điểm B₁ và C₁ có trọng tâm ở giữa [B₁C₁]. Khối lượng còn lại ở đỉnh B và C cũng hóa ra bằng nhau (mặc dù chúng cũng có thể âm, như trong Hình 2):

$$m+b - \frac{(a+c) b}{a} = m+c - \frac{(a+b) c}{a} = m - \frac{bc}{a},$$

và do đó trọng tâm của chúng nằm ở giữa [BC]. Điều này có nghĩa là trọng tâm Q của toàn hệ nằm trên đường thẳng nối trung điểm của các đoạn B₁C₁ và BC.

Tương tự, chứng minh Q nằm trên hai đường thẳng còn lại nêu ở điều kiện. Để dịch lời giải cơ học của chúng ta sang ngôn ngữ toán học, chỉ cần xác định “trọng tâm” của hệ khối lượng là đủ. Gọi A₁ là các điểm trên mặt phẳng, m₁ là các số tùy ý (i = 1, 2, ..., n), “khối lượng tổng cộng” m₁+m₂+...+mₙ = M ≠ 0. Tâm của chồng trọng số C = C {A₁(m₁)} được xác định bởi điều kiện: đối với một số (và sau đó đối với bất kỳ) điểm O nào của mặt phẳng $\overrightarrow{OC} = (m_1\overrightarrow{OA}_1 + \cdots + m_n\overrightarrow{OA}_n)/M$. (Định nghĩa này cũng đúng với m₁ âm.) Không khó để kiểm tra thực tế duy nhất mà chúng ta thu được trong lời giải: nếu m₁ = m'₁ + m'₂, Σm'₁ = M' và Σm'₂ = M'', thì tâm khối C = C {A₁(m'₁)} nằm trên đường thẳng C'C'', trong đó C' = C {A₁(m'₁)}, C'' = C {A₁(m'₁)} và $\overrightarrow{OC} = (M'\overrightarrow{OC}' + M''\overrightarrow{OC'})/M$.

Để biết thêm thông tin về “phép tính áp kế” mà chúng tôi đã sử dụng trong lời giải này, hãy xem cuốn sách của M. B. Balk “Ứng dụng hình học trên 定理 xếp chồng nặng”. Thứ hai lời giải. Hãy gọi trung điểm của cạnh BC; AC và AB tương ứng đi qua X, Y và Z và trung điểm của các cạnh B₁C₁, A₁C₁ và A₁B₁ - đi qua X₁, Y₁ và Z₁ (Hình 3). Hãy đặt các khối lượng đơn vị tại các điểm A, B, C và P rồi tìm trọng tâm của hệ điểm toán học này.

Gọi X₂, Y₂ và Z₂ là trung điểm của các đoạn AP, BP và CP. Vì trọng tâm của các điểm B và C đặt tại điểm X và trọng tâm của các điểm A và P tại điểm X₂ nên trọng tâm của toàn hệ nằm trên đường thẳng XX₂. Theo nguyên tắc tương tự, nó nằm trên đường YY₂ và ZZ₂. Vì trọng tâm của hệ các điểm toán học tồn tại là trọng tâm duy nhất đồng thời thuộc về tất cả các đường thẳng này nên các đường thẳng này cắt nhau tại một điểm; hãy biểu thị nó bằng Q (xem Hình 3)

⟦folio 27⟧

Hình 3.

Hình 4.

Hình 5.

Mặt khác, nếu $S$ là trọng tâm của tam giác $ABC$ (tức là giao điểm của các đường trung tuyến của nó) thì trọng tâm của hệ điểm $\{A, B, C, P\}$ nằm trên đoạn $PS$. Ở trên chúng ta đã chỉ ra rằng trọng tâm của hệ này nằm ở điểm $Q$; có nghĩa là $Q \in [PS]$. Hơn nữa, vì để tìm trọng tâm của hệ $\{A, B, C, P\}$ theo cách cuối cùng, chúng ta phải đặt một khối lượng ba đơn vị tại điểm $S$, điểm $Q$ chia đoạn $PS$ theo tỷ lệ 3:1.

Nếu chúng ta chứng minh rằng các đường thẳng $XX_2, YY_2, ZZ_2$ lần lượt đi qua các điểm $X_1, Y_1$ và $Z_1$ thì bài toán sẽ được giải. Phát biểu cuối cùng rút ra từ định lý sau đây áp dụng cho các tứ giác $PA_1BC_1, PB_1AC_1$ và $PA_1CB_1$:

Định lý Gauss. Nếu không có cạnh nào của tứ giác song song thì trung điểm của đoạn nối giao điểm của hai đường thẳng kéo dài và đối diện nằm trên đường thẳng nối trung điểm với một đường chéo.

Để chứng minh ba điểm thẳng hàng, người ta sử dụng các khái niệm gần như hiển nhiên sau: tiêu chí (điều kiện cần và đủ); hãy tự mình chứng minh điều đó.

Gọi $K$ là điểm trong của hình bình hành $A_1A_2A_3A_4$. Chúng ta hãy vẽ qua $K$ các đường thẳng song song với các cạnh của hình bình hành và biểu thị qua $B_1, B_2, B_3, B_4$ giao điểm của các đường thẳng này trên cạnh của nó (Hình 4). Điểm $K$ nằm trên đường chéo $A_1A_3$ của hình bình hành của mô hình và sữa của mô hình khi $S_{KB_1A_2B_2} = S_{KB_3A_4B_4}$ (ở đây chúng ta sử dụng $S$ để biểu thị diện tích).

Chứng minh định lý Gauss. Chúng ta hãy biểu thị các đỉnh của tứ giác bằng $A, B, C, D$, giao điểm của phần kéo dài của các cạnh đối diện của nó bằng $E$ và $F$, và trung điểm của các đường chéo $AC, BD$ và đoạn $EF$ tương ứng là $X, Y$ và $Z$. Chúng ta hãy kẻ qua các điểm $D, C$ và $F$ các đường thẳng song song với các đường thẳng $AF$ và $AE$ rồi sử dụng ký hiệu như Hình 5.

Rõ ràng là điểm $C, L$ và $R$ được chuẩn bị tương ứng, điểm $X, Y$ và $Z$ với tâm được chuẩn bị $A$ và hệ số được chuẩn bị $2$. Do đó, điểm $X, Y, Z$ thuộc một đường thẳng tương đương với các điểm $C, L$ và $R$ thuộc cùng một đường thẳng.

⟦folio 28⟧

Từ tiêu chí trên suy ra điểm $L$ thuộc đường $CR$ nếu đẳng thức $S_{LMPQ} = S_{LNTS}$ được thỏa mãn. Hãy để chúng tôi chứng minh rằng đây thực sự là trường hợp.

Vì điểm $C$ thuộc các đường chéo của hình bình hành $AFQD$ và $ABSE$ (xem Hình 5), nên chúng ta có: $S_{AGCH} = S_{CNQP}$ và $S_{AGCH} = S_{CMST}$. Vì vậy, $S_{CNQP} = S_{CMST}$, và do đó, $S_{LMPQ} = S_{LNTS}$, đó là điều bắt buộc. Lời giải hợp pháp.

F. Vayshtein, N. Vasiliev

M493. Chứng minh bất đẳng thức
$0,785n^2 - n < \sqrt{n^2 - 1} + \sqrt{n^2 - 2^2} + \dots + \sqrt{n^2 - (n - 1)^2} < 0,79n^2$.

Hình 6.

Hình 7.

Hãy lấy một phần tư hình tròn có bán kính đơn vị: $O$ là tâm hình tròn, $[OA]$ là bán kính, $|OA| = 1$ (Hình 6). Chúng ta hãy chia đoạn $OA$ thành $n$ phần tắc nghẽn ($n$ là số tự nhiên tùy ý). Trên các đoạn chia $n - 1$ đầu tiên thu được (tính từ điểm $O$), chúng ta dựng một đường thẳng dài sao cho ở đỉnh cao nhất, các đỉnh trên của tất cả các hình chữ nhật nằm trên cung của hình tròn $BA$, giới hạn “một phần tư hình tròn” của chúng ta (xem Hình 6). Chúng ta nhận được $n - 1$ hình chữ nhật, tổng diện tích của chúng nhỏ hơn một phần tư hình tròn có bán kính đơn vị, tức là nhỏ hơn $\frac{\pi}{4} < 0,79$.

Vì số tiền này bằng nhau
$$\frac{1}{n} \sqrt{1 - \left(\frac{1}{n}\right)^2} + \frac{1}{n} \sqrt{1 - \left(\frac{2}{n}\right)^2} + \dots +$$
$$+ \frac{1}{n} \sqrt{1 - \left(\frac{n - 1}{n}\right)^2} = \frac{1}{n^2} \left(\sqrt{n^2 - 1} + \sqrt{n^2 - 2^2} + \dots + \sqrt{n^2 - (n - 1)^2}\right),$$

Từ những gì đã nói, ta có bất đẳng thức đúng.

Để chứng minh bất đẳng thức bên trái, ta tiến hành như sau. Bây giờ chúng ta hãy tạo một hình chữ nhật trên tất cả các đoạn nhận được $[OA]$ trong quá trình chia—tổng cộng $n$ hình chữ nhật và sao cho tất cả các đỉnh trên bên trái của hình chữ nhật nằm trên cung $BA$ của hình tròn (Hình 7). Chúng ta sẽ có được hình bậc thang như trong Hình 7, diện tích của nó đã lớn hơn sáu phần tư vòng tròn bán kính đơn vị, tức là lớn hơn $\frac{\pi}{4} > 0,785$.

Diện tích của một hình bậc bằng tổng diện tích $n$ của các hình chữ nhật có đáy có chiều dài $\frac{1}{n}$ và chiều cao có chiều dài
$$1, \sqrt{1 - \left(\frac{1}{n}\right)^2}, \sqrt{1 - \left(\frac{2}{n}\right)^2}, \dots, \sqrt{1 - \left(\frac{n - 1}{n}\right)^2}$$

tương ứng:
$$\frac{1}{n} \left(1 + \sqrt{\frac{n^2 - 1}{n^2}} + \sqrt{\frac{n^2 - 2^2}{n^2}} + \dots + \sqrt{\frac{n^2 - (n - 1)^2}{n^2}}\right).$$

Vì thế,
$$\frac{1}{n^2} \left(n + \sqrt{n^2 - 1} + \sqrt{n^2 - 2^2} + \dots + \sqrt{n^2 - (n - 1)^2}\right) > 0,785,$$

Ở đâu
$$0,785n^2 - n < \sqrt{n^2 - 1} + \sqrt{n^2 - 2^2} + \dots + \sqrt{n^2 - (n - 1)^2}.$$

A. Sivachky

⟦folio 29⟧

F503. Một sợi dây dài 2l được buộc vào trục thẳng đứng ở đầu và giữa của
những quả bóng giống hệt nhau được gắn vào bầy (Hình 8). Trục được đưa đến bác sĩ bằng một
tốc độ bên trái $\omega$. Tại giá trị nào của tỷ lệ đánh bắt là các đoạn OA và AB
Hãy bắt đầu đi chệch khỏi phương thẳng đứng? Tỷ lệ sai lệch đánh bắt nhỏ sẽ là bao nhiêu
các đoạn ren OA và AB tính từ phương thẳng đứng?

Để ở một tốc độ quay chốt nhất định $\omega$ các sợi OA và AB lệch khỏi phương thẳng đứng lần lượt một góc nhỏ $\alpha$ và $\varphi$ (Hình 9). Trong trường hợp này, các quả bóng quay đều với tốc độ bắt $\omega$ dọc theo các vòng tròn nằm trong mặt phẳng ngang. Bán kính của các vòng tròn này bằng các lực tương ứng tác dụng lên nó - lực căng $mg$ (m là khối lượng của quả bóng), lực $\vec{N}_1$ lực căng của sợi dây OA và lực $\vec{N}_2$ lực căng của sợi dây AB. Gia tốc hướng tâm $\omega^2 r_2$ được truyền tới quả bóng phía dưới bởi các lực bằng nhau $mg$ và $\vec{N}_2$. Hãy tìm các lực $\vec{N}_1$ và $\vec{N}_2$.

Quả bóng phía dưới không di chuyển theo phương thẳng đứng; kể từ đây,

$$|mg| = |\vec{N}_2| \cos \varphi \Rightarrow |\vec{N}_2| = \frac{|mg|}{\cos \varphi}.$$

Quả bóng trên cùng cũng không chuyển động theo phương thẳng đứng; kể từ đây,

$$|mg| + |\vec{N}_2| \cos \varphi = 2 |mg| = |\vec{N}_1| \cos \alpha \Rightarrow |\vec{N}_1| = \frac{2 |mg|}{\cos \alpha}.$$

Bây giờ chúng ta hãy viết phương trình chuyển động của các quả bóng trong một vòng tròn: đối với quả bóng phía dưới—

$$m\omega^2 l (\sin \alpha + \sin \varphi) = |\vec{N}_2| \sin \varphi = |mg| \ tg \ \varphi,$$

(1)

cho quả bóng hàng đầu—

$$m\omega^2 l \sin \alpha = |\vec{N}_1| \sin \alpha - |\vec{N}_2| \sin \varphi =$$

$$= 2 |mg| \ tg \ \alpha - |mg| \ tg \ \varphi.$$

(2)

Vì các góc $\alpha$ và $\varphi$ nhỏ nên chúng ta có thể đếm $\sin \alpha = \alpha$, $\sin \varphi = \varphi$, $tg \alpha = \alpha$, $tg \varphi = \varphi$. Khi tính đến điều này, từ (1) và (2) chúng tôi có được

$$\omega^2 l (\alpha + \varphi) = |\vec{g}| \ \varphi, \ \omega^2 l \alpha = |\vec{g}| (2 \alpha - \varphi),$$

hoặc

$$\omega^2 l \alpha + \varphi (\omega^2 l - |\vec{g}|) = 0,$$

$$(\omega^2 l - 2 |\vec{g}|) \alpha + \varphi |\vec{g}| = 0.$$

Từ hai biểu thức này ta thấy:

$$\frac{\alpha}{\varphi} = \frac{|\vec{g}| - \omega^2 l}{\omega^2 l} = \frac{|\vec{g}|}{2 |\vec{g}| - \omega^2 l},$$

(3)

cho phép chúng ta viết phương trình sau cho $\omega^2$:

$$(\omega^2)^2 l^2 - 4 |\vec{g}| l \omega^2 + 2 |\vec{g}|^2 = 0.$$

Từ đây là

⟦folio 30⟧

F505. Khoảng cách từ mạch sạc tụ điện đến pin (Hình 11). Tụ điện được sạc đến điện áp pin $U$, năng lượng ven biển $\frac{C_1 U^2}{2}$ và sạc $q = C_1 U$. Khoản phí này được lấy từ pin, komorai, châm ngôn, chúng tôi thực hiện công việc $q U = C_1 U^2$. Hệ số hiệu quả là 1/2. Tên của tụ điện sạc để tạo điện áp cho ắc quy có hiệu suất cao. Không có lý do gì để sử dụng các nguồn năng lượng bổ sung.

Hình 10.

$$\omega_1^2 = \frac{|\vec{g}|}{l} (2 \pm \sqrt{2}),$$
$$\omega_1 = \sqrt{\frac{|\vec{g}|}{l}} (2 + \sqrt{2}),$$
$$\omega_2 = \sqrt{\frac{|\vec{g}|}{l}} (2 - \sqrt{2})$$

(các giá trị $\omega'_1 = -\omega_1$ và $\omega'_2 = -\omega_2$ tương ứng với biểu thức theo hướng ngược lại). Vì $\omega_2 < \omega_1$, điều tự nhiên là giả sử rằng các sợi từ bắt đầu lệch khỏi phương thẳng đứng với vận tốc góc quay $\omega = \omega_2$.

Hãy tìm tỉ số giữa các góc lệch nhỏ của ren $OA$ và $AB$ so với phương thẳng đứng. Từ biểu thức (3) ta có

$$\text{при } \omega = \omega_1 - \frac{\alpha}{\varphi} = -\sqrt{2},$$
$$\text{при } \omega = \omega_2 - \frac{\alpha}{\varphi} = \sqrt{2}.$$

Thực tế là ở $\omega = \omega_1$ $\frac{\alpha}{\varphi} < 0$ có nghĩa là ở tốc độ góc như vậy, các sợi $OA$ và $AB$ bị lệch khỏi phương thẳng đứng theo các hướng ngược nhau (Hình 10).

G. Budaenko

◆

I. Lấy một tụ điện khác có điện dung là $C_2 = n C_1$ ($n$ là một số nhất định) và mắc nó vào mục tiêu nối tiếp với tụ điện có điện dung $C_1$ (Hình 12). Điện dung trong mạch như vậy là $C = \frac{C_1 C_2}{C_1 + C_2} = \frac{n}{n+1} C_1$.

Điện tích mà tụ điện thu được bằng

$$q_1 = q_2 = \frac{n}{n+1} C_1 U,$$

và hiệu điện thế trên tụ điện là

$$U_1 = \frac{q_1}{C_1} = \frac{n}{n+1} U,$$
$$U_2 = \frac{q_2}{C_2} = \frac{1}{n+1} U.$$

Sau khi ngắt kết nối các tụ điện đã tích điện khỏi pin, chúng ta lắp ráp mạch như trong Hình 13. Điện áp trên các tụ điện trong mạch như vậy là $U'_1 = U'_2 = \frac{q'_1}{C_1} = \frac{q'_2}{C_2} = \frac{q'_2}{n C_1}$, trong đó $q'_1, q'_2$ là các điện tích sẽ được thiết lập trên các tụ điện. Theo định luật bảo toàn điện tích $q'_1 + q'_2 = \frac{2n}{n+1} C_1 U$. Giải được hệ phương trình

$$\begin{cases} q'_1 + q'_2 = \frac{2n}{n+1} C_1 U, \\ \frac{q'_1}{C_1} = \frac{q'_2}{n C_1}, \end{cases}$$

chúng tôi tìm thấy: $q'_1 = \frac{2 n}{(n+1)^2} C_1 U$, $U'_1 = \frac{2 n}{(n+1)^2} U$.

Bây giờ tụ điện $C_1$, được sạc đến điện áp $U'_1$, tiếp cận pin mới (xem Hình 11). Đồng thời anh ấy

⟦folio 31⟧

sẽ được sạc lại đến điện áp $U$. Điện tích của tụ điện sẽ tăng lên
$$\Delta q = C_1 (U - U'_1) = \frac{n^2 + 1}{(n + 1)^2} C_1 U.$$
Do đó, tổng điện tích $Q$ mà tụ điện $C_1$ nhận được từ pin bằng
$$Q = q_1 + \Delta q = \frac{2 n^2 + n + 1}{(n + 1)^2} C_1 U.$$
Năng lượng mà tụ điện thu được bằng
$$\Pi = \frac{C_1 U^2}{2}.$$
Công $A$ mà pin thực hiện khi nạp tụ điện đến điện áp $U$ bằng
$$A = QU = \frac{2 n^2 + n + 1}{(n + 1)^2} C_1 U^2.$$
Vậy hiệu suất là
$$\eta = \frac{\Pi}{A} = \frac{(n + 1)^2}{2 (2 n^2 + n + 1)}.$$
Để giá trị $\eta$ lớn hơn 1/2 thì bất đẳng thức cần phải
$$\frac{(n + 1)^2}{2 n^2 + n + 1} > 1.$$
Từ đây chúng ta tìm thấy $n < 1$.
Vì vậy, bằng cách sạc tụ điện $C_1$ vào điện áp $U$, chúng ta tăng thêm việc sử dụng pin hiệu quả hơn ($\eta > \frac{1}{2}$), nếu trong quy trình được mô tả ở trên, chúng ta sử dụng thêm tụ điện $C_2$, công suất của tụ điện nhỏ hơn $C_1$.
Những người đã quen với phương pháp tìm cực trị tùy ý có thể tìm thấy điều đó trong quá trình mô tả $\eta = \eta_{\max}$ tại $n = 1/3$ ($\eta_{\max} \approx 57\%$).
Sử dụng không phải một mà là hai, ba hoặc nhiều tụ điện bổ sung, bạn có thể nghĩ ra nhiều phương pháp sạc khác nhau. Với số lượng tụ điện bổ sung đủ lớn, hiệu suất có thể đạt được gần bằng 1 như mong muốn.
II. Hãy để chúng tôi mô tả một phương pháp sạc khác trong đó có thể đạt được hiệu suất gần bằng đơn vị.
Hãy lắp ráp mục tiêu như trong Hình 14. Khi pin được kết nối với mục tiêu (công tắc $K$ ở vị trí 1), dòng điện qua cuộn dây bắt đầu tăng dần. Chúng ta hãy chờ xác định thời gian cho đến khi điện tích $\frac{CU}{2}$ chạy qua mục tiêu.
Trong thời gian này, pin sẽ hoạt động $\frac{CU^2}{2}$, một phần $-\frac{CU^2}{8}$ sẽ chuyển thành năng lượng của tụ điện, phần còn lại sẽ được lưu trữ trong từ trường của cuộn dây. Terrier sẽ nhanh chóng di chuyển phím $K$ sang vị trí 2. Trong một thời gian, dòng điện qua cuộn dây sẽ tiếp tục chạy theo chế độ có chiều, giảm dần. Tụ điện sau đó sẽ được sạc lại. Khi dòng điện trong cuộn dây bằng 0, chúng ta nhanh chóng di chuyển phím $K$ về vị trí 1. Khi phím $K$ ở vị trí 2 thì năng lượng từ trường của cuộn dây được chuyển hóa thành năng lượng của tụ điện. Do đó, vì năng lượng mục tiêu không bị tiêu tán (chúng ta bỏ qua điện trở của cuộn dây, pin, v.v.), nên tất cả năng lượng $\frac{CU^2}{2}$ tiêu thụ từ pin sẽ được chuyển hóa thành năng lượng

⟦folio 32⟧

F506. Dưới pít-tông của hình trụ có một thùng chứa rumv, chiếm thể tích $V_p$ và k mol khí lý tưởng. Diện tích bề mặt của piston là $S$. Piston và đáy xi lanh được làm bằng vật liệu được làm ướt một cách lý tưởng bởi xi lanh. Thể tích dưới pít-tông đối xứng với trục xi-lanh có dạng như hình 15. Lực $F$ tác dụng lên pít-tông. 1) Suy ra phương trình trạng thái của hệ rumv + eaz có dạng $p = f(V, T)$, thực phẩm $p$ – áp suất, $T$ – nhiệt độ tuyệt đối, $V$ – thể tích phần bình đặt dưới pít-tông. 2) Được đặt tên theo $p = 0$. Bề mặt của bề mặt tự nhiên σ. Chúng ta không tính đến sức mạnh của sự dịu dàng. Chúng ta hãy chấp nhận rằng thể tích của căn phòng và diện tích bề mặt σ của nó được xây dựng (nghĩa là chúng không phụ thuộc vào $T$ và $p$) và $h \ll r$.

Hình 15.

Hình 16.

Các lực tác dụng lên piston là lực $\vec{F}_p$ của áp suất chất lỏng và lực $\vec{F}_r$ của áp suất khí. $|\vec{F}_p| = p_p S_p$, $|\vec{F}_r| = p_r (S - S_p)$, trong đó $p_p$, $p_r$ – áp suất của rượu rumv và khí, $S_p$ – diện tích của piston, được bao phủ bởi rượu rum.

Áp suất khí là

$$p_r = \frac{kRT}{V_r} = \frac{kRT}{V - V_p},$$

trong đó $V_r$ là thể tích chiếm bởi khí. Vì bề mặt của ranh giới khí rut bị cong nên áp suất “bên dưới” bề mặt này là áp suất khí, lớn hơn áp suất “phía trên” nó, tức là áp suất vết hằn.

Hãy xem xét một phần nhỏ của bề mặt ranh giới thủy ngân-khí (Hình 16). Vì $r \gg h$, chúng ta có thể giả sử rằng bề mặt này là bề mặt của nửa trụ. Chúng ta hãy làm nổi bật phần song song mà bề mặt này phù hợp (xem Hình 16). Nó chịu tác dụng của lực áp suất khí $|\vec{f}_r| = p_r s = p_r lh$, lực bề mặt khí $|\vec{f}_p| = p_p s = p_p lh$ và lực bề mặt khí $|\vec{f}_{пов}| = \sigma l$. Từ điều kiện cân bằng của song song này suy ra rằng

$$p_r lh = p_p lh + 2 \sigma l,$$

Ở đâu

$$p_p = p_r - \frac{2 \sigma}{h}.$$

Lực do khí và thủy ngân tác dụng lên piston bằng nhau

$$|\vec{F}_r| = p_r (S - S_p) = \frac{kRT}{V - V_p} (S - S_p),$$

$$|\vec{F}_p| = p_p S_p = \left( \frac{kRT}{V - V_p} - \frac{2 \sigma}{h} \right) S_p.$$

Vì $h \ll r$, chúng ta có thể giả sử rằng $S_p = V_p/h$. Xét $h = V/S$, ta tìm được tổng lực tác dụng lên piston:

$$|\vec{F}_r| + |\vec{F}_p| = p_c p S = \frac{kRT}{V - V_p} S - \frac{2 \sigma V_p S^2}{V^2},$$

trong đó $p_c$ là áp suất trung bình tác dụng lên piston. Từ đây

$$p_c = \frac{kRT}{V - V_p} - \frac{2 \sigma V_p S^2}{V^2}.$$

⟦folio 33⟧

Áp suất trung bình bằng 0 trong điều kiện

$$\frac{kRT}{V - V_p} = \frac{2\sigma V_p S}{V^2},$$

nghĩa là, $p_{cp} = 0$ tại

$$T = \frac{2\sigma V_p S (V - V_p)}{V^2 kR}.$$

S. Semenchinsky

F507. Hai lò xo này được làm từ cùng một chất liệu, một lò xo được xếp cạnh nhau. Đường kính lò xo là 3 mm và 9 mm, chiều dài là 1 cm và 7 cm, đường kính dây là 0,2 mm và 0,6 mm. Độ cứng của lò xo thứ nhất là 0,14 N/cm. Hệ số độ cứng của lò xo cuộn là thấp nhất.

Lưu ý rằng một đoạn của lò xo thứ hai dài 3 cm về mặt hình học tương tự như lò xo thứ nhất - tất cả các kích thước của nó đều lớn hơn chính xác ba lần. Chúng ta hãy xem độ cứng của các lò xo tương tự được làm từ cùng một vật liệu tương ứng như thế nào.

Độ cứng của lò xo được xác định duy nhất bởi cấu hình hình học của nó và tính chất đàn hồi của vật liệu làm nên nó. Chúng ta sẽ tìm một công thức xác định độ cứng $k$, công thức này đúng cho bất kỳ lò xo nào có hình học tương tự như lò xo đầu tiên. Cấu hình của một lò xo như vậy hoàn toàn được xác định ngay khi bất kỳ kích thước nào của nó được chỉ định, ví dụ: đường kính của cuộn dây $D$. Thật vậy, bất kỳ kích thước nào khác có thể thu được từ kích thước tương ứng của lò xo thứ nhất bằng cách nhân với hệ số tương tự $n = D/D_1$, trong đó $D_1$ là đường kính của lò xo thứ nhất. Và tính chất đàn hồi của vật liệu được đặc trưng bởi mô hình Young $E$:

Bây giờ chúng ta hãy sử dụng thông điệp kích thước. Từ giá trị $E$ (thứ nguyên $[E] = H/m^2$) và $D$ (thứ nguyên $[D] = m$), người ta có thể tạo một sự kết hợp độc đáo với thứ nguyên $k$ (thứ nguyên $[k] = H/m$): $ED$. Có nghĩa,

$$k = cED,$$

trong đó $c$ là đại lượng không thứ nguyên, tùy thuộc vào các thông số của lò xo, tức là $c = f\left(\frac{l}{D}, \frac{d}{D}\right)$. Không thể xác định giá trị của $c$ bằng phương pháp thứ nguyên. Tuy nhiên, đối với chúng tôi, đối với tất cả các lò xo có hình học tương tự lò xo thứ nhất thì giá trị của $c$ là như nhau.

Kết luận này cho phép chúng ta xác định độ cứng $k_3$ của một lò xo có độ cứng hình học tương tự $n = 3$ với lò xo thứ nhất có độ cứng $k_1 = 0,14$ N/cm:

$$k_3 = 3k_1 = 0,42 \text{ H/cm.}$$

Bây giờ chúng ta hãy so sánh một lò xo có độ cứng $k_3$ và một lò xo thứ hai ở điều kiện bài toán, có độ cứng $k_2$ phải được tìm thấy. Tất cả các tham số của chúng, ngoại trừ chiều dài, đều giống nhau, do đó ít hơn trong số chúng có thể được biểu diễn dưới dạng ba lò xo liên tiếp dài 1 cm và hơn thế nữa - dưới dạng bảy lò xo như vậy. Do đó, dưới tác dụng của cùng một lực $\vec{F}$ việc di chuyển $x_3 = |\vec{F}|/k_3$ nhỏ hơn lò xo và di chuyển nhiều hơn $x_2 = |\vec{F}|/k_2$ so với lò xo theo tỷ lệ 3:7. Kể từ đây,

$$k_2 = \frac{3}{7} k_3 = 0,18 \text{ H/cm.}$$

A. Kuznetsov, S. Kuznetsov
