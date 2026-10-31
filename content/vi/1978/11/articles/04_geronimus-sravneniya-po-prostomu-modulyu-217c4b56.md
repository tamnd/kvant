---
id: 1978-11-geronimus-sravneniya-po-prostomu-modulyu-217c4b56
issue: kvant_1978_11
year: 1978
number: "11"
title: So sánh modulo số nguyên tố
authors:
  - Геронимус А. Ю.
rubric: osnovnye-stati
page_first: 8
page_last: 11
page_labels: 6-9
tag: M5KF
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 31ed63a0cdb8bdd7030676e7411feecb075636b4cf1c2b7eb40aa235ae6749b2
prompt_sha256: draft-1
translated_from: content/ru/1978/11/articles/04_geronimus-sravneniya-po-prostomu-modulyu-217c4b56.md
source_content_sha256: 0c75e16e721ef0ca27465aaa84f1465f6be23b084a0e0b940d5b381b2315ba55
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 6⟧

So sánh modulo số nguyên tố

Trong bài viết “So sánh và các loại dư lượng”*), tập hợp $F_m$ của các lớp dư lượng modulo $m$ đã được xem xét và ba phép toán đã được xác định - các lớp cộng, trừ và nhân. Ở đó người ta đã chứng minh rằng trong trường hợp mô hình so sánh là số nguyên tố thì phép chia cho bất kỳ lớp nào khác 0 đều có thể được xác định. Nhờ sự so sánh này với một modulo đơn giản, chúng có một số tính chất thú vị và tinh tế mà việc so sánh với một modulo tùy ý không có. Chúng tôi sẽ giới thiệu một số thuộc tính này ở đây. Trong phần tiếp theo, chúng ta sẽ luôn giả định rằng mô hình là số nguyên tố; để không quên điều này, chúng tôi sẽ biểu thị nó bằng $p$.

Sự tồn tại của một gốc nguyên thủy

Chúng ta gọi thứ tự của lớp thặng dư $\bar{a} \in F_p$ là số tự nhiên nhỏ nhất $k$ mà $\bar{a}^k = 1$. Ở cuối bài “So sánh và các loại dư lượng” có nói rằng trong tập $F_p$ có một lớp có thứ tự là $p-1$. Lớp có thuộc tính này được gọi là lớp gốc nguyên thủy. Định lý về sự tồn tại của một lớp như vậy lần đầu tiên được chứng minh bởi Legendre (1752-1833). Chúng ta hãy trình bày một chứng minh định lý Legendre, gần với chứng minh của Legendre.

*) Xem «Kvant» Số 10.

Trước tiên chúng ta hãy chứng minh rằng nếu cấp $l$ và $m$ của hai lớp $\bar{a}$ và $\bar{b}$ là nguyên tố cùng nhau thì cấp của tích $\bar{a}\bar{b}$ bằng $lm$. Thật vậy, $(\bar{a}\bar{b})^{lm} = \bar{a}^{lm} \cdot \bar{b}^{lm} = (\bar{a}^l)^{m} \cdot (\bar{b}^m)^{l} = 1$ (kể từ $\bar{a}^l = 1$ và $\bar{b}^m = 1$). Do đó, thứ tự lớp $\bar{a}\bar{b}$ phải là ước số của số $lm$. Hãy biểu thị nó bằng $l'm'$, trong đó $l'$ là ước số của $l$ và $m'$ là ước số của $m$ (l và m là nguyên tố cùng nhau!)*. Vì thế,

$$\bar{a}^{l'm'} \cdot \bar{b}^{l'm'} = (\bar{a}\bar{b})^{l'm'} = 1.$$

Chúng ta hãy nâng cả hai vế của đẳng thức này lên lũy thừa $l''$ sao cho $l'l'' = l$. Phổ biến khi đó là $(\bar{a}^l)^{m'} \cdot \bar{b}^{lm'} = 1$, và vì $l$ là thứ tự của $\bar{a}$, nên $(\bar{a}^l)^{m'} = 1$ và do đó $\bar{b}^{lm'} = 1$. Điều này có nghĩa là $lm'$ chia hết cho $m$ (cấp $\bar{b}$), nhưng $l$ nguyên tố cùng nhau với $m$ và $m'$ là ước của $m$, vì vậy $m' = m$, tương tự như $l' = l$; tuyên bố của chúng tôi đã được chứng minh.

Bây giờ chúng ta chuyển trực tiếp sang định lý.

Hãy xem xét lớp $\bar{a}$ với thứ tự cao nhất có thể $N$. Ta muốn chứng minh đây là nghiệm nguyên thủy. Để làm điều này, chỉ cần xác minh rằng bất kỳ lớp nào khác $\bar{b}$ đều là lũy thừa của $\bar{a}$. Giả sử thứ tự của $\bar{b}$ bằng $n$. Có hai trường hợp có thể xảy ra tại $n$. Hãy xem xét $n$ lớp $\bar{a}^k \cdot N/n$ với $0 \leq k < n$. Chúng đều là các nghiệm bậc $n$ khác nhau của các đơn vị, tức là nghiệm của phương trình $\bar{x}^n - 1 = 0$ (kiểm tra). Lớp $\bar{b}$ cũng là gốc của lũy thừa $n$ của các đơn vị theo định nghĩa về thứ tự. Trong phần phụ lục của bài viết này, chúng tôi sẽ chứng minh rằng mọi đa thức bậc $n$ có hệ số $F_p$ và đặc biệt, đa thức $\bar{x}^n - 1$ không thể có nhiều hơn $n$ nghiệm. Do đó, $\bar{b}$ là một trong các phần tử của $\bar{a}^k N/n$, tức là nó là lũy thừa của $\bar{a}$.

2) $N$ không chia hết cho $n$. Đặt $r$ là ước chung lớn nhất có thể có của $N$ và $n$.

*) Khả năng biểu diễn một số tùy ý $lm$ như vậy xuất phát từ Định lý cơ bản của số học, được chứng minh trong phần phụ lục của bài viết này.

⟦folio 7⟧

Thứ tự của lớp $\bar{b}^r$ là $n/r$ (đánh dấu). Các số $N$ và $n/r$ là số nguyên tố cùng nhau. Do đó thứ tự của lớp $\bar{ab}^r$ là $N \cdot n/r > N$. Điều này mâu thuẫn với tính cực đại của $N$. Trường hợp thứ hai là không thể.

Định lý về sự tồn tại nghiệm thứ nhất đã được chứng minh.

Giả thuyết của Artin

Chứng minh trên không mang tính xây dựng: chúng ta không thể chỉ ra rõ ràng dư lượng nào $\bar{1}$, ..., $\bar{p-1}$ là nghiệm nguyên thủy modulo $p$.

Nhà toán học người Mỹ E. Artin (1898–1962) đưa ra phỏng đoán sau: nếu số nguyên $n$ không phải là số chính phương thì có vô số số nguyên tố $p$ mà lớp thặng dư mod $p$ chứa $n$ là một mod gốc nguyên thủy $p$. Giả thuyết này vẫn chưa được chứng minh. Nếu chúng ta có thể chỉ định rõ ràng mod gốc nguyên thủy $p$ cho tất cả $p$, thì sẽ dễ dàng biết được liệu phỏng đoán này có đúng hay không. (Kiểm tra xem nếu $n=m^2$ dành cho một số $m$ thì các số nguyên tố $>2$ được đề cập trong phỏng đoán hoàn toàn không tồn tại.)

Chiết xuất rễ

Định lý Legendre cho phép chúng ta tìm ra khi nào các nghiệm có thể được rút ra trong tập $F_p$.

Điều tự nhiên là gọi căn bậc $n$ từ lớp dư $\bar{b}$ là một lớp $\bar{x}$ sao cho $\bar{x}^n = \bar{b}$.

Đặt $\bar{a}$ là một số gốc nguyên thủy trong $F_p$. Có một số tự nhiên $k$ sao cho $\bar{b} = \bar{a}^k$. Nếu, theo $\bar{x}^n = \bar{b}$, $\bar{x}$ được thay thế bằng $\bar{a}^y$ thì có thể viết lại thành $\bar{a}^{yn} = \bar{a}^k$ hoặc $\bar{a}^{yn-k} = \bar{1}$.

Từ trận đấu cuối cùng, chúng ta có thể thấy rằng $yn-k$ chia hết cho $p-1$.

Tính chia hết này tương đương với đẳng thức sau trong tập hợp $F_{p-1} : \bar{yn} = k$.

Ngược lại, nếu $\bar{m}$ trong tập hợp $F_{p-1}$ là nghiệm của phương trình $\bar{yn} = \bar{k}$, thì $\bar{a}^m$ là nghiệm của lũy thừa $n$ của $\bar{b}$ (trong $F_p$).

Do đó, chúng tôi đã giảm bài toán về việc trích xuất các nghiệm trong tập hợp $F_p$ xuống bài toán về phép chia trong tập hợp $F_{p-1}$.

Trong bài “So sánh và phân loại dư lượng” đã nêu rằng nếu $d$ là ước số chung nhất của các số $n$ và $p-1$ và $k$ chia hết cho $d$, thì phương trình $\bar{yn} = \bar{k}$ có chính xác là $d$ lời giải; nếu nó không chia hết thì không có phương trình $\bar{yn} = \bar{k}$ lời giải nào cả.

Bây giờ câu hỏi về nghiệm của bậc $n$ từ lớp dư lượng $\bar{b}$ đã hoàn toàn rõ ràng:

Định lý. Nếu chỉ số*) $k$ của lớp $\bar{b} \in F_p$ được chia cho ước số chung nhất $d$ của các số $n$ và $p-1$, thì có một gốc động $n$ từ lớp $\bar{b}$; trong trường hợp khác, không thể trích xuất gốc $n$ từ lớp $\bar{b}$.

Ví dụ: $p = 11$.

Chúng ta hãy viết ra tất cả các thân của lớp $\bar{2}$ trong tập hợp $F_{11}$. Trong Bảng 1, dòng đầu tiên chứa chỉ báo tấm bia, trong đó bạn cần xây dựng $a$ để nhận được $\bar{b}$. Trong việc xây dựng định lý, không tồn tại nghiệm nguyên hàm nào được chọn.

*) Chúng ta hãy nhớ lại (xem «Kvant» Số 10, trang 8) rằng chỉ số của lớp $\bar{b}$ đến cơ số $\bar{a}$ (sau đây gọi là căn nguyên) là số mũ của thân trong đó $a$ phải được nâng lên để thu được $\bar{b}$. Trong việc xây dựng định lý, không tồn tại nghiệm nguyên hàm nào được chọn.

**) Cách dễ nhất là tính toán thân của hai (hoặc phần tử khác) một cách tuần tự: $\bar{2}^k = \bar{2}.\bar{2}^{k-1}$; đầu tiên dựng 2 ở cột $k$, sau đó đưa mod 11 là công việc tốn nhiều công sức hơn.

⟦folio 8⟧

đã gặp, ví dụ lớp 3. Chỉ số của nó là 8. Chúng ta cần giải phương trình $3y=8$ trong tập $F_{10}$. Chúng tôi sẽ nhân tất cả các lớp trong $F_{10}$ với 3 (Bảng 2). Từ bảng rõ ràng là từ

$$\begin{array}{c|cccccccc}
k \in F_{10} & 1 & 2 & 3 & 4 & 5 & 6 & 7 & 8 & 9 & 0 \\
\hline
3k \in F_{10} & 3 & 6 & 9 & 2 & 5 & 8 & 1 & 4 & 7 & 0
\end{array}$$

vet - 6, có nghĩa là trong tập hợp $F_{11}$ $2^6=9$ là căn bậc ba của 3. Thật vậy, $9^3=3$.

Bây giờ đặt $n=5$, sau đó $d=5$ và từ tất cả các lớp ngoại trừ lớp 1 và 10 (với chỉ số 10 và 5), nghiệm bậc 5 không được trích xuất. Đầu tiên chúng ta hãy tìm nghiệm bậc 5 từ 1. Dễ dàng nói rằng đây đều là các lớp có bốn chỉ số. (Thật vậy, lớp có chỉ số thứ tư 2r bằng $2^2r$; $(2^2r)^5=(2^r)^{10}=1$ theo định lý nhỏ của Fermat cho $p=11$.) Có rất nhiều lớp như vậy, lớp thứ năm là 1, 3, 4, 5 và 9. Theo định lý, trong tập hợp $F_{11}$ phải có căn bậc năm bậc 5 của 1.

Bây giờ chúng ta hãy giải quyết các nghiệm bậc 5 trên 10. Có thể thấy một nghiệm như vậy từ bảng - thực tế đây là 2, $2^5=10$. Để có được tất cả các nghiệm, chúng ta cần nhân 2 với tất cả các nghiệm bậc 5 của 1 mà chúng ta đã tìm được. Thật vậy, nếu $x^5=1$ thì $(2x)^5=2^5\cdot x^5=10\cdot 1=10$. Đáp số: lớp 2, 6, 7, 8, 10, tức là tất cả các lớp có 4 chỉ số. Việc 10 là nghiệm của lũy thừa 5 của chính nó không có gì đáng ngạc nhiên - xét cho cùng, $10=-1$.

Các khoản khấu trừ bình phương và không khấu trừ

Bây giờ chúng ta hãy xem xét một trường hợp đặc biệt - trích căn bậc hai. Trước hết, chúng ta cần xét ước số chung nhất $d$ của số 2 và $p-1$. Nếu $p=2$ thì $d=1$; nếu $p>2$ thì $p$ là số lẻ nên $p-1$ là số chẵn và $d=2$. Xét trường hợp lẻ $p$ (bạn có thể dễ dàng nghiên cứu trường hợp $p=2$). Chúng tôi phát hiện ra rằng căn bậc hai có thể được lấy từ một lớp có chỉ số bốn (và sẽ có hai căn bậc hai cho mỗi lớp), nhưng căn bậc hai không thể được lấy từ một lớp có chỉ số bốn. Các lớp có bốn chỉ số được gọi là phần dư bình phương, và những lớp có chỉ số lẻ được gọi là phần dư bình phương. Vì trong số tất cả các giá trị chỉ số có thể có từ 1 đến $p-1$ có $\frac{p-1}{2}$ số chẵn và $\frac{p-1}{2}$ số lẻ, nên trong số $p-1$ lớp không cảm giác của dư lượng bình phương và không dư lượng bình phương có số lượng bằng nhau. Điều thú vị là tích của một khoản khấu trừ bằng một khoản khấu trừ hoặc một không khấu trừ bằng một khoản khấu trừ sẽ cho một khoản khấu trừ bình phương, và tích của một khoản khấu trừ bình phương bằng một khoản khấu trừ sẽ cho một khoản không khấu trừ. Điều này xuất phát từ thực tế là khi các lớp thay đổi, chỉ số của chúng sẽ cộng lại. Những tuyên bố tương tự cũng đúng cho cái cụ thể. Ví dụ: thương số không được khấu trừ chia cho không được khấu trừ nhất thiết phải là một khoản khấu trừ bình phương.

Hãy quay lại $p=11$. Dư lượng bình phương là các phần tử có bốn chỉ số, nghĩa là tất cả các lớp có bốn chỉ số, tức là tất cả các nghiệm bậc 5 của 1. Sự đối xứng ẩn này xảy ra với tất cả $p$, không chỉ với $11^*$).

Các loại dư lượng hợp lý và không hợp lý

Vì vậy, không phải tất cả các lớp đều có thể được root. Ví dụ, căn bậc hai, như chúng ta đã thấy, chỉ có thể được lấy từ phần dương của các lớp không cảm giác.

Hiện tượng này cũng xảy ra đối với các số tổng quát. Bạn biết rõ rằng trong trường số hữu tỉ, số 2 chẳng hạn, không thể được coi là căn bậc hai. Bạn có biết-

*) Bạn có thể đọc về các khoản khấu trừ bình phương và không khấu trừ trong «Kvant» Số 1 năm 1973 (trang 2-9).

⟦folio 9⟧

Ngoài ra, nếu chúng ta mở rộng tập hợp số hữu tỷ và xem xét tập hợp $R$ của tất cả các số thực, thì trong tập hợp lớn hơn này, chúng ta có thể trích căn bậc hai của số 2 và $\sqrt{2}$ là một số từ tập hợp $R$, chỉ là số vô tỷ.

Hãy làm tương tự với các lớp khấu trừ. Để rõ ràng, hãy xem xét lại $p=11$. Chúng ta đã thấy rằng lớp $\overline{2}$ là một số dư bình phương; căn bậc hai không thể được trích xuất từ ​​nó. Chúng ta hãy xây dựng một tập hợp lớn $G \supset F_{11}$ trong đó sẽ có căn bậc hai của lớp $\overline{2}$, tức là một phần tử $\alpha$ sao cho $\alpha^2=\overline{2}$.

Tương tự như cách xây dựng hình học, chúng tôi sẽ tiến hành phân tích. Trước hết, chúng ta hãy làm rõ công thức của bài toán. Để đẳng thức $\alpha^2=\overline{2}$ có ý nghĩa, điều tự nhiên là giả sử rằng đối với bất kỳ cặp phần tử nào của tập hợp $G$ tích của chúng được xác định. Chúng tôi cũng yêu cầu xác định tổng của hai phần tử bất kỳ trong tập hợp $G$. Trong trường hợp này, $G$ phải chứa tất cả hai phần tử có thể có $\overline{a}+\overline{b}\alpha$, trong đó $\overline{a}, \overline{b} \in F_{11}$. Hóa ra điều này đã khá đủ. Chúng ta thường có thể xác định tổng của hai lenin: $(\overline{a}+\overline{b}\alpha) + (\overline{c}+\overline{d}\alpha) = (\overline{a}+\overline{c}) + (\overline{b}+\overline{d})\alpha$. Ví dụ: $(\overline{5}+\overline{2}\alpha) + \overline{9}\alpha=5$.

Khi nhân, các số hạng có $\alpha^2$ xuất hiện. Chúng tôi sẽ thay thế $\alpha^2$ bằng $\overline{2}$. Ví dụ: $(\overline{3}+\overline{7}\alpha)(\overline{5}+\overline{2}\alpha) = \overline{3}\cdot\overline{5} + (\overline{7}\cdot\overline{5}+\overline{2}\cdot\overline{3})\alpha + \overline{2}\cdot\overline{7}\alpha^2 = 10+\overline{8}\alpha$.

Có nhiều phần tử $\overline{a}+\overline{b}\alpha$ trong tập hợp $G$ bằng số cặp $\overline{a}, \overline{b} \in F_{11}$, tức là $11^2=(121)$. Do đó, ký hiệu $F_{11^2}$ được thông qua cho nó. Không cần thiết phải có tập hợp này với một tập hợp các lớp dư lượng $F_{121}$ modulo 121, cũng có 121 phần tử. Không giống như $F_{121}$, trong $F_{11^2}$ có thương số là $\overline{a}+\overline{b}\alpha$ chia cho $\overline{c}+\overline{d}\alpha$ trừ khi $\overline{c}$ và $\overline{d}$ đều bằng 0. Tuyên bố này được chứng minh trong hai giai đoạn. Đầu tiên, hãy xem xét trường hợp khi $\overline{d}=0$. Thật dễ dàng để kiểm tra điều đó $(\overline{a}+\overline{b}\alpha) : c = \overline{a}/\overline{c} + (\overline{b}/\overline{c})\alpha$. Trường hợp tổng quát là

Điều này có thể đạt được bằng cách nhân số bị chia và số chia với $\overline{c}-\overline{d}\alpha$. Sau đó, bạn phải chia cho $\overline{c}^2-2\overline{d}^2$. Phần tử tập hợp $F_{11}$ này khác với 0, nếu không chúng ta sẽ có $\overline{c}^2=2\overline{d}^2$, $\overline{2}=\left(\frac{\overline{c}}{\overline{d}}\right)^2$ và $2$ sẽ là phần dư bình phương trong $F_{11}$. Vì vậy sự phân chia là có thể.

Trong tập hợp $F_{11^2}$, căn bậc hai không chỉ được biết từ $\overline{2}$ mà còn từ tất cả các lớp $\overline{r} \in F_{11}$. Thật vậy, nếu $\overline{r}$ là số dư bình phương thì căn bậc hai đã được lấy ở $F_{11}$. Nếu $\overline{r}$ là không dư lượng, thì như chúng ta đã thấy trước đó, thương của $\overline{r}$ chia cho $\overline{2}$ là một thặng dư bậc hai và do đó tồn tại một lớp $\overline{s}$ sao cho $\overline{r}=2\overline{s}^2$. Trong trường hợp này $\sqrt{\overline{r}}=\sqrt{2}\cdot\overline{s}^2=\overline{s}\alpha$.

Theo cách tương tự, chúng ta có thể xây dựng $F_{p^2}$ cho một $p$ tùy ý. Liên quan đến kiến ​​thức về căn nguyên ở cấp độ cao hơn, các bộ $F_{p^3}, F_{p^4}$, v.v. sẽ phát sinh. Tập hợp $F_{p^2}$ có nghiệm nguyên thủy, tức là một phần tử có cấp tối đa có thể $p^2-1$. Điều thú vị là chúng ta thực tế đã chứng minh được nhận định này: khi chứng minh định lý Legendre, chúng ta chỉ sử dụng sự tồn tại của bốn tác dụng và tính hữu hạn của tập hợp đang nghiên cứu.

Nhiệm vụ và

1. Tìm tất cả các nghiệm nguyên hàm trong tập $F_{13}$.
2. Phương trình $\overline{x}^2+\overline{y}^2=0$ có lời giải trong tập hợp $F_p$ ($p>2$) khác với $\overline{x}=\overline{y}=0$ khi và chỉ khi phần dư của $\overline{p}$ chia cho 4 bằng 1.
3. Phương trình $\overline{x}^2-\overline{5x}+7=0$ có bao nhiêu lời giải trong tập hợp $F_5$? và trong $F_7$?
4. Có bao nhiêu phần tử là hình khối trong $F_{13}, F_5, F_{11}$, trong $F_p$? k-min độ?
5. Có bao nhiêu nghiệm nguyên thủy trong tập $F_p$?
6. Có bao nhiêu phần tử trong tập hợp $F_{11^2}$ là hình vuông?

Ứng dụng

Định lý cơ bản của số học

Bất kỳ số tự nhiên $n>2$ nào cũng có thể được biểu diễn dưới dạng tích của các thừa số nguyên tố; với một chế độ xem đơn sắc theo thứ tự bội số, một chế độ xem duy nhất có thể được biểu diễn.

A. Đầu tiên sử dụng phương pháp quy nạp toán học, ta chứng minh sự tồn tại
