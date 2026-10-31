---
id: 1971-3-bashmakov-nravitsya-li-vam-vozitsya-s-tselyimi-chislami-94974d2e
issue: kvant_1971_3
year: 1971
number: "3"
title: Bạn có thích mày mò với các số nguyên không?
authors:
  - Башмаков М. И.
rubric: osnovnye-stati
page_first: 17
page_last: 21
page_labels: 15, 16, 18, 19
tag: WS2Q
lang: vi
source: kvant_digital
extraction: vision
content_sha256: b1a2eab495eed70806c4f025fb1625ba992063ab439d83be1b69c4f65d640b52
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1971/03/articles/04_bashmakov-nravitsya-li-vam-vozitsya-s-tselyimi-chislami-94974d2e.md
source_content_sha256: 07b818e65eb548c95b33773f45fb68806e240a67a2de1c7005063224d733ac64
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦folio 15⟧

BẠN CÓ THÍCH LOAY HOAY
VỚI CÁC SỐ NGUYÊN KHÔNG?

M. I. Bashmakov

Một số học sinh được đề nghị trả lời câu hỏi sau:
Hãy xác định xem đẳng thức $3^{100} + 7^{100} = 8^{100}$ có đúng hay không.
Vài phút sau, tất cả đều trả lời rằng đẳng thức này không đúng.
Dưới đây là những lập luận điển hình nhất.

1) Hãy xét chữ số cuối cùng của các số ở vế phải và vế trái. 3 bình phương là 9, 3 lập phương tận cùng bằng 7, lũy thừa bậc bốn tận cùng bằng 1, bậc năm — bằng 3, bậc sáu — bằng 9, v.v. Sau bốn lũy thừa, chữ số cuối cùng lặp lại, vì vậy số $3^{100}$ có chữ số cuối cùng giống $3^4$, tức là 1. Cũng dễ thấy rằng $7^{100}$ cũng có chữ số cuối cùng là 1, còn $8^{100}$ — là 6. Vậy số ở vế trái có chữ số cuối cùng là 2, còn ở vế phải — là 6. Do đó, các số ở vế trái và vế phải khác nhau.

2) $3 + 7$ lớn hơn 8. Nhưng $3^2 + 7^2 = 58$ nhỏ hơn $8^2 = 64$. Hơn nữa, $3^{100} + 7^{100} = (3^2)^{50} + (7^2)^{50} < (3^2 + 7^2)^{50} = 58^{50} < 64^{50} = 8^{100}$. Ta được rằng số ở vế trái nhỏ hơn số ở vế phải.

3) Số ở vế trái chia hết cho 2, nhưng không chia hết cho 4. Thật vậy, bình phương của bất kỳ số lẻ nào khi chia cho 4 đều dư 1: $(2n + 1)^2 = 4n^2 + 4n + 1$. Tổng của hai số như vậy $(3^{50})^2 + (7^{50})^2$ khi chia cho 4 dư 2. Còn ở vế phải là một số chia hết cho 4.

Các chứng minh trên có giống nhau không? Dễ nhận thấy sự giống nhau giữa chứng minh thứ nhất và thứ ba: trong cả hai, người ta so sánh các số dư khi chia cho một số nguyên nào đó, trong một trường hợp — chia cho 10 (chữ số cuối cùng), còn trong trường hợp kia — chia cho 4. Nhưng tìm sự tương tự giữa các chứng minh này và chứng minh thứ hai thì hoàn toàn không đơn giản. Chúng ta sẽ thử làm rõ điều đó ở cuối bài viết này. Còn bây giờ, hãy học cách áp dụng phương pháp lập luận thứ nhất vào một số bài toán khác.

Tính toán «theo môđun»

Bài toán 1. Chứng minh rằng phương trình $x^3 = 2 + 3 y^2$ không có nghiệm nguyên.

Xét phương trình này “theo môđun 9”, nghĩa là chính xác đến các số hạng chia hết cho 9 *). Vì mỗi số nguyên $x$ có dạng $3n$, $3n - 1$ hoặc $3n + 1$, trong đó $n$ là số nguyên, $a(3n \pm 1)^3 = 27n^3 \pm 27n^2 + 9n \pm 1 = 9k \pm 1$, trong đó $k$ là số nguyên, nên mọi số lập phương hoặc chia hết cho 9, hoặc khi chia cho 9 có số dư là 1 hoặc 8.

*) Nói chung, hai số nguyên $a$ và $b$ được gọi là đồng dư theo môđun $k$, nếu hiệu $a - b$ chia hết cho $k$. Những ai chưa biết khái niệm này, chúng tôi khuyên xem bài của A. A. Egorov “Số học các số dư” trong “Kvant” số 5, 1970.

Tương tự, vì $3(3n \pm 1)^2 = 27n^2 \pm 18n + 3$,

$3y^2$ khi chia cho 9 cho số dư 0 hoặc 3. Vậy vế phải của phương trình chúng ta theo môđun 9 chỉ có thể bằng 2 hoặc 5, còn vế trái — chỉ bằng 0, 1 hoặc 8, do đó chúng không thể trùng nhau với bất kỳ số nguyên nào. Bản thân các phép tính “theo môđun” thực hiện rất đơn giản. Hãy phát biểu quy tắc cơ bản của các phép tính này: nếu khi cộng (hoặc khi nhân) ta thay các số bằng những số đồng dư với chúng theo

⟦folio 16⟧

theo môđun $k$, thì ta được một số đồng dư với tổng (hoặc tích) theo môđun $k$. Nói cách khác, trong một đẳng thức có các phép cộng và nhân, có thể thay các số bằng những số đồng dư với chúng theo môđun $k$ bất cứ khi nào trong kết quả ta chỉ quan tâm đến số dư của phép chia cho $k$.

Việc $a$ và $b$ đồng dư theo môđun $k$ được viết như sau: $a \equiv b \pmod{k}$. Các quy tắc phép toán với các đồng dư có thể viết như sau:

$$\text{nếu } \begin{cases} a \equiv b \pmod{k}, \\ c \equiv d \pmod{k}, \end{cases}$$

$$\text{thì } \begin{cases} a + c \equiv b + d \pmod{k}, \\ ac \equiv bd \pmod{k}. \end{cases}$$

Nhắc lại rằng theo định nghĩa, $a \equiv b \pmod{k}$ có nghĩa là $a - b = k \cdot q^*$.

Xét bài toán khá nhân tạo sau.

Bài tập 2. Chứng minh rằng đẳng thức $1153^{60} + 211^{60} = 27027 \cdot 100^x + 2$ là không thể với bất kỳ số nguyên $x$ nào.

Rõ ràng, nếu theo một môđun nào đó ta không thu được đẳng thức, thì đẳng thức đó cũng không thể đúng theo nghĩa thông thường. Theo môđun 2 không phát hiện mâu thuẫn nào — ở vế phải và vế trái là các số chẵn (các số dư bằng không theo môđun 2). Xét môđun 3. $1153 \equiv 1 \pmod{3} = 1153^{60} \equiv 1 \pmod{3}$; $211 \equiv 1 \pmod{3} = 211^{60} \equiv 1 \pmod{3}$. Vế phải $27027 \equiv 0 \pmod{3}$. Vì thế toàn bộ vế phải có số dư là 2. Lại không thu được mâu thuẫn. Nếu bạn đủ kiên nhẫn, hãy kiểm tra rằng theo môđun của mọi số đến 16 kể cả 16, đẳng thức đã viết là đúng. (Bạn sẽ nhận thấy rằng $27027 \cdot 100^x, x \geq 2$, chia hết cho từng số này, còn vế trái sẽ cho số dư 2.)

*) Hãy cẩn thận khi chia một đồng dư. Nếu $ac \equiv bc \pmod{k}$, thì không nhất thiết đúng rằng $a \equiv b \pmod{k}$. Chẳng hạn, $27 \equiv 3 \pmod{6}$, nhưng $9 \neq 1 \pmod{6}$. Tuy nhiên, nếu $c$ nguyên tố cùng nhau với môđun $k$, thì có thể rút gọn cho $c$. Điều này là hệ quả của một sự thật không đơn giản để chứng minh: nếu $c$ nguyên tố cùng nhau với $k$, thì tồn tại một số $x$ sao cho $cx \equiv 1 \pmod{k}$.

Nếu bạn kiên trì, thì theo môđun 17 bạn sẽ nhận được đẳng thức sau: $(-3)(-2)^x + 2 \equiv 0 \pmod{17}$. Lần lượt thử các giá trị của $x$ (chu kỳ ở đây sẽ có độ dài 8), bạn sẽ không một lần nào nhận được đẳng thức cần thiết. Bạn sẽ tìm thấy mâu thuẫn.

Những tính toán đã làm lập tức đặt ra nhiều câu hỏi:

(1) Nếu đẳng thức là sai, thì có thể phát hiện điều đó theo một môđun nào đó không?

(2) Có thể bằng cách nào đó chỉ ra những môđun mà theo đó có nhiều khả năng nhận được mâu thuẫn hơn không?

(3) Hành vi của đẳng thức theo các môđun khác nhau có liên hệ với nhau không?

Nếu nói về một đẳng thức số cụ thể nào đó (như ở ví dụ đầu tiên của chúng ta), thì dĩ nhiên luôn có những số mà khi xét theo môđun đó ta sẽ tìm được mâu thuẫn (chẳng hạn, có thể lấy một số lớn hơn các vế của đẳng thức). Thú vị hơn nhiều là những đẳng thức có biến số (như trong hai ví dụ cuối). Đối với phương trình nguyên, mỗi trong ba câu hỏi đã nêu đều thú vị và không phải lúc nào cũng được nghiên cứu đến cùng.

**Một chút điều chưa được chứng minh**

Những phương trình nguyên đầu tiên mà khi giải xuất hiện những khó khăn nghiêm trọng là các phương trình bậc hai*. Từ lâu, các nhà toán học đã quan tâm đến những câu hỏi thuộc loại này: có thể biểu diễn một số đã cho dưới dạng tổng của hai bình phương không? Hóa ra tính giải được của phương trình dạng $x^2 + y^2 = a$ và những phương trình tổng quát hơn khác, được cho bởi các đa thức bậc hai, dẫn đến việc kiểm tra tính giải được của đồng dư (đặt-

*) Lý thuyết các phương trình nguyên tuyến tính khá đơn giản. Đồng thời, nó chứa một loạt bài toán thú vị, gần với các bài toán sơ cấp, và xứng đáng có một bài riêng.

⟦folio 18⟧

nghiên cứu các câu hỏi liên quan đến số nguyên: đặt các câu hỏi ấy “theo môđun $p$”, rồi từ hành vi theo mọi $p$ rút ra những kết luận chung. Cách lập luận như vậy được gọi là “nguyên lý Minkowski — Hasse”. Đã có và vẫn còn xuất hiện những bài toán mà nó cho kết quả: bài toán có nghiệm trong số nguyên khi và chỉ khi nó giải được theo mọi môđun. Càng thất vọng hơn khi tìm ra các ví dụ mà nguyên lý này không hoạt động. Một trong những ví dụ đầu tiên thuộc loại đó (nhưng không phải sớm nhất về mặt thời gian) là ví dụ do nhà toán học Na Uy Selmer tìm ra. Phương trình $3x^3+4y^3+5z^3=0$ hóa ra giải được theo mọi môđun (và, dĩ nhiên, trong các số thực), nhưng không giải được trong các số nguyên (không đồng thời bằng không). Ví dụ này đã trở thành điểm xuất phát của nhiều nghiên cứu về các phương trình Diophantine (tức là các phương trình trong số nguyên) trong 15 năm gần đây. Chỉ cần nói rằng trong thời gian đó, số câu hỏi chưa rõ và các giả thuyết đã tăng lên rất nhiều, còn những cội rễ thực sự của điều đang xảy ra trên thực tế vẫn chưa được làm sáng tỏ.

Khoảng cách giữa các số hữu tỉ

Thành tựu hiện đại quan trọng nhất trong lý thuyết số là sự hiểu biết mới về ý nghĩa của “các phép tính theo môđun”. Để đơn giản, ta chuyển từ số nguyên sang số hữu tỉ. (Sự chuyển đổi này thường được thực hiện không đau đớn — chẳng hạn, các nghiệm của phương trình $x^n+y^n=z^n$ trong số nguyên liên hệ rất chặt chẽ với các nghiệm của phương trình $x^n+y^n=1$ trong số hữu tỉ.) Rõ ràng rằng nếu muốn giải một phương trình trong các số hữu tỉ, ta phải biết liệu nó có giải được trong các số thực hay không. Việc kiểm tra tính giải được này đơn giản hơn nhiều: có thể khai căn các loại, lấy logarit, viết các bất đẳng thức, v.v.

Nhưng hãy nhớ lại, các số thực đã được tạo ra từ các số hữu tỉ như thế nào? Một trong các quan điểm là như sau: có thể xét các dãy số hữu tỉ mà khoảng cách giữa các số hạng kề nhau giảm không bị chặn. Chẳng hạn, 1; 1,4; 1,41; 1,4142; ... Một dãy như vậy (có thể hình dung nó như một dãy các phép đo với độ chính xác tăng dần) xác định một số thực. Độ lệch giữa các số hạng kề nhau của dãy thay đổi như thế nào? Nếu viết dãy như sau: $a_1; a_2; a_3; ...$, thì khoảng cách giữa các số hạng được viết là $|a_m-a_n|$. Như vậy, cơ sở để tạo ra các số thực từ các số hữu tỉ là khoảng cách, được xác định như giá trị tuyệt đối của hiệu. Kí hiệu khoảng cách giữa hai số như sau: $d(a, b) = |b-a|$. Hãy thử suy ra các tính chất sau của khoảng cách*:

1) $d(a, b) \geq 0$, trong đó $d(a, b) = 0 \Rightarrow a=b$;
2) $d(a, b) = d(b, a)$;
3) $d(a, c) \leq d(a, b) + d(b, c)$ (bất đẳng thức tam giác);
4) $d(a+c, b+c) = d(a, b)$;
5) $d(ab, 0) = d(a, 0) \cdot d(b, 0)$.

Hóa ra rằng, ngoài giá trị tuyệt đối thông thường, các số hữu tỉ còn có nhiều khoảng cách khác, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các tính chất, có các հատկություններ,

⟦folio 19⟧

dưới dạng phân số tối giản, $p$ không xuất hiện cả ở tử số lẫn mẫu số. (Lưu ý rằng $v(a)$ có thể bằng không, cũng có thể là một số nguyên âm. Chẳng hạn, nếu $p=3$, $a=\frac{73}{324}=3^{-4}\cdot\frac{73}{4}$, thì $v(a)=-4$.) Bây giờ lấy một số dương tùy ý $\lambda<1$. Xác định khoảng cách $d_p$ như sau: $d_p(a,b)=\lambda v(a-b)$, nếu $a\neq b$, và $d_p(a,a)=0$. Không khó kiểm tra (hãy thử tự làm điều đó) rằng mọi tính chất của khoảng cách đều được thỏa mãn.

Một khi có khoảng cách mới, ta có thể thử thu được những số mới, bằng cách xây dựng các dãy số hữu tỉ $a_1, a_2, \ldots$ sao cho khoảng cách giữa các số hạng kề nhau giảm dần. Điều này có nghĩa là $\lambda v(a_{n+1}-a_n)$ khi $n$ tăng phải ngày càng nhỏ và tiến tới không, và khi đó $v(a_{n+1}-a_n)$ phải tăng.

Cuối cùng ta sẽ nhận được những số mới, được gọi là $p$-adic $^*$. Chúng rất giống các số thực. Cũng dễ như đối với các số thực, có thể nghiên cứu các vấn đề khi nào có thể lấy căn, lấy lôgarit và thực hiện các phép toán khác trên các số $p$-adic. Khi đó bài toán về khả năng giải được của phương trình theo môđun một lũy thừa của số nguyên tố đã cho sẽ được thay bằng bài toán về khả năng giải được của nó trong các số $p$-adic.

Nảy sinh câu hỏi liệu ta đã tìm được mọi khoảng cách giữa các số hữu tỉ hay chưa. Hóa ra là rồi. Có một định lý đáng chú ý của Ostrovsky (có thể làm quen với nó trong cuốn sách về lý thuyết số đã được trích dẫn ở trên), cho thấy rằng mọi khoảng cách đều được bao quát bởi trị tuyệt đối thông thường và các khoảng cách $p$-adic mà ta đã đưa vào đối với mỗi số nguyên tố $p$.

Ta dường như đã đặt ngang hàng cách ứng xử của một phương trình theo môđun một số nguyên tố riêng lẻ và lũy thừa của nó, một mặt, với cách ứng xử của nó trong các số thực thông thường

$^*)$ Dễ chứng minh rằng việc chọn $\lambda$ không ảnh hưởng đến sự xây dựng và các tính chất của các số $p$-adic. Nếu muốn, có thể ở mọi nơi coi rằng $\lambda=\frac{1}{2}$ hoặc $\lambda=\frac{1}{p}$.

mặt khác. Trong cả hai trường hợp, các số được so sánh theo khoảng cách của chúng với nhau, nhưng những khoảng cách này được chọn khác nhau. (Bây giờ ta thấy lời giải thứ hai và thứ ba của bài toán mà bài viết của chúng ta bắt đầu giống nhau ở điểm nào.)

Sự hiểu biết về sự kiện này đã làm phong phú mạnh mẽ lý thuyết số, lại đưa vào đó những phương pháp mạnh của lý thuyết hàm và hình học, trước đây được phát triển cho các số thực thông thường, nhưng cũng được áp dụng thành công cho các số $p$-adic, khiến ngành toán học cổ xưa này trở thành một trong những ngành phát triển rực rỡ nhất.)

Bài tập

1. Chứng minh rằng không phương trình nào trong các phương trình a) $x^2+y^2=1971$, b) $19x^3-17y^3=50$, b) $3x^2-y^2=5^z$, r) $x^3+y^3+7z=3$ có nghiệm nguyên.

2. Chứng minh rằng từ các chữ số 1, 2, 3, 4, 5, 6, 7 không thể lập được hai số có bảy chữ số khác nhau, trong đó số này chia hết cho số kia. (Trong mỗi số phải dùng tất cả các chữ số.)

3. Chứng minh rằng số có biểu diễn thập phân gồm ba mươi chữ số một, một số lượng chữ số không và một số lượng chữ số chín, không phải là một số chính phương.

4. Tìm khoảng cách 5-adic (nghĩa là khoảng cách $d_5$) giữa các số: a) 0 và $\frac{2}{5}$; b) $1\frac{31}{45}$ và $6\frac{2}{15}$; b) 6 và 631.

5. Chứng minh rằng đối với các số 3-adic, đẳng thức sau đúng

$$1+3+9+27+\ldots=-\frac{1}{2}$$

(nói cách khác, dãy các khoảng cách

$$\alpha_n=d_3\left(1+3+\ldots+3^n,-\frac{1}{2}\right)$$

tiến tới không).

Tổng $1+3^2+3^4+3^6+\ldots$ bằng bao nhiêu?
