---
id: 1971-8-resheniya-03bebc35
issue: kvant_1971_8
year: 1971
number: "8"
title: Lời giải các bài toán M50—M60, M45 (tiếp theo); F66—F71
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 37
page_last: 52
page_labels: 35, 36, 37, 38, 40, 41, 42, 43, 44, 45, 46, 47, 48, 49
tag: 8MA1
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 7e737237f6f834dbbf63e519510fa3e5eea535940989ca4923122af7e5e075d6
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1971/08/articles/08_resheniya-03bebc35.md
source_content_sha256: 54cdc9046bf3a255926094c4d6f446f7c16dbfec8155d7cf8680696411e52ecc
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦folio 35⟧

LỜI GIẢI

Trong số này chúng tôi công bố lời giải các bài M50--M60 và phần cuối lời giải bài M45.

M50

Các đỉnh của một $n$-giác đều được tô bằng một số màu (mỗi đỉnh một màu) sao cho các điểm cùng màu là các đỉnh của một đa giác đều. Chứng minh rằng trong các đa giác ấy có hai đa giác bằng nhau.

Giả sử các đỉnh của một $n$-giác đều nào đó được tô sao cho tất cả các đỉnh tô cùng màu tạo thành các đa giác đều khác nhau: một $m_1$-giác, một $m_2$-giác, một $m_3$-giác, ..., trong đó $m_1 < m_2 < m_3 < ...$. Số nhỏ nhất trong các số ấy, $m_1$, sẽ đóng một vai trò đặc biệt trong lập luận của chúng ta, và ta ký hiệu đơn giản nó là $m$.

Từ tâm $O$ của $n$-giác, kẻ các vectơ tới mọi đỉnh của nó; ký hiệu chúng theo thứ tự là $a_1, a_2, a_3, ..., a_n$ (hình 1a). Khi đó

$$\vec{a}_1 \vec{a}_2 = \vec{a}_2 \vec{a}_3 = \ldots = \vec{a}_{n-1} \vec{a}_n = \vec{a}_n \vec{a}_1 = \frac{2\pi}{n}.$$

Ở đây và dưới đây, qua $\vec{ab}$ chúng tôi ký hiệu số đo của góc (không âm nhỏ nhất) mà cần quay ngược chiều kim đồng hồ vectơ $a$ để nó trùng với vectơ $b$; luôn có $0 \leqslant \vec{ab} < 2\pi$.

Ta sẽ nói rằng các vectơ $c_1, c_2, c_3, ..., c_q$ trên mặt phẳng, xuất phát từ điểm $O$, tạo thành một hệ đều nếu chúng có độ dài bằng nhau và tạo với nhau các góc bằng nhau:

$$\vec{c}_1 \vec{c}_2 = \vec{c}_2 \vec{c}_3 = \ldots = \vec{c}_{q-1} \vec{c}_q = \vec{c}_q \vec{c}_1 = \alpha > 0.$$

Ta sẽ cần sự kiện gần như hiển nhiên sau đây (chứng minh được đưa ở cuối lời giải).

Bổ đề. Tổng các vectơ tạo thành một hệ đều bằng không.

⟦folio 36⟧

Hình 1. Hãy tưởng tượng rằng các điểm màu trên hình $a$ là những hạt cườm xâu trên một sợi dây uốn thành xoắn ốc. Ta nhìn xoắn ốc này từ trên xuống, vì thế hai hạt cườm đỏ ngoài cùng $A'$ và $A''$ chiếu thành một điểm $A$. Nếu bây giờ ta cố định một trong các hạt cườm — $A'$, còn $A''$ kéo dọc theo sợi dây thêm 2 vòng, thì ta sẽ được hình $b$, trong đó các góc giữa những vectơ kề nhau tăng lên 3 lần.

Trước khi sử dụng bổ đề, ta thực hiện phép biến đổi sau với các vectơ của mình. Ta sẽ coi rằng vectơ $a_1$ hướng tới một trong các đỉnh của đa giác $m$ cạnh. Ký hiệu nó đơn giản là $a$ và sẽ đo mọi góc từ nó (theo chiều dương, tức là ngược chiều kim đồng hồ). Ký hiệu $b_i$ là vectơ nhận được từ $a$ bằng phép quay một góc $m \rightarrow aa_i$ (với mỗi $i=1,2,\dots,n$). Dưới ánh xạ $a_i \rightarrow b_i$ mà ta vừa xây dựng*) (trên hình 1, $\delta$ biểu diễn ánh xạ như vậy với $m=3$), các góc giữa các vectơ tăng lên $m$ lần; chính xác hơn: nếu $m \rightarrow a_i a_j < 2\pi$, thì $\rightarrow b_i b_j = m \rightarrow a_i a_j$. Vì vậy, ánh xạ này biến một hệ vectơ chính quy có góc $\alpha < \frac{2\pi}{m}$ thành một hệ vectơ chính quy. Đặc biệt, tổng của tất cả các vectơ $b_1, b_2, \dots, b_n$ bằng không.

Hãy tính tổng này bằng một cách khác: trước hết tìm tổng các vectơ tương ứng với các đỉnh của từng màu, rồi cộng tất cả các tổng đó. Trước hết xét tất cả các vectơ $a_i$, hướng tới các đỉnh của một $m_h$-giác, trong đó $m_h > m$. Đây là một hệ vectơ đều với góc $\frac{2\pi}{m_h} < \frac{2\pi}{m}$. Sau phép ánh xạ, từ nó lại thu được một hệ đều, và tổng các vectơ nhận được sẽ bằng không.

Bây giờ xét các vectơ hướng tới các đỉnh của một $m$-giác. Góc giữa các vectơ kề nhau trong trường hợp này bằng $\frac{2\pi}{m}$, và sau phép ánh xạ tất cả $m$ vectơ này trùng với vectơ $a$, nên tổng của chúng sẽ bằng $m$ (trên hình 1 đây là trường hợp các vectơ đỏ và đen).

Vậy, đã thu được mâu thuẫn: một mặt, tổng của tất cả các $b_i$ bằng không, mặt khác — nó bằng $m$. Do đó giả thiết của chúng ta là sai.

*) Đối với những ai quen với số phức, lưu ý rằng nếu điểm $O$ biểu diễn số không trên mặt phẳng phức, còn đầu mút của vectơ $a$ biểu diễn đơn vị, thì phép ánh xạ này là phép nâng lên lũy thừa $m: z \rightarrow z^m$.

⟦folio 37⟧

Chứng minh bổ đề. Một nhà vật lý sẽ nói rằng mệnh đề này hiển nhiên từ các lập luận đối xứng. Một cách biến các lập luận này thành chứng minh chặt chẽ là như sau. Giả sử $c_1 + c_2 + \dots + c_n = s$. Quay tất cả các vectơ $c_1, c_2, \dots, c_n$ quanh điểm $O$ một góc $\alpha$. Khi đó, dĩ nhiên, tổng của chúng cũng quay một góc $\alpha$. Nhưng theo giả thiết, toàn bộ hệ gồm $n$ vectơ sau khi quay một góc $\alpha$ trùng với chính nó ($c_1$ đến vị trí của $c_2, c_2$ — đến vị trí của $c_3, \dots, c_n$ — đến vị trí của $c_1$). Vì vậy vectơ $s$ sau khi quay một góc $\alpha$ không được thay đổi. Điều này chỉ có thể xảy ra nếu $s = 0$.

Có thể chứng minh rằng trong trường hợp tổng quát, một hệ đúng gồm $q$ vectơ gồm $q = dr$ vectơ được vẽ từ điểm $O$ đến các đỉnh của một $r$-giác đều, sao cho tại mỗi đỉnh có $d$ vectơ bằng nhau (nếu kể cả các «nhị giác» — các cặp vectơ đối nhau, thì chúng tương ứng với $m = 2$); khi đó $\alpha$ có thể bằng bất kỳ số nào trong các số $\frac{2\pi l}{r}$, trong đó $l$ và $r$ nguyên tố cùng nhau, $0 < l < r$. Chúng tôi để nhận xét này đến cuối vì trong chứng minh bằng công thức, chúng tôi đã không cần làm rõ chi tiết hệ đúng các vectơ $b_i$ được cấu tạo như thế nào. Nhưng dĩ nhiên, khi xem xét chứng minh «về thực chất», thì việc làm rõ điều đó là có ích.

Ý tưởng của lời giải bài toán trình bày ở đây do A. Livshits (Leningrad) đề xuất. Xem xét kỹ lời giải này, có thể chứng minh rằng mọi cách chia các đỉnh của một $n$-giác đều thành vài tập hợp, tương ứng với các đa giác đều (không nhất thiết khác nhau), đều có thể nhận được như sau: trước hết chia $n$-giác thành vài $m$-giác (điều này đòi hỏi $n$ chia hết cho $m$), sau đó lại chia một trong các đa giác đều thu được thành vài đa giác đều (xem hình 1), rồi tiếp tục như vậy vài lần. Với những độc giả muốn tìm hiểu kỹ hơn điều này, chúng tôi cũng khuyên suy nghĩ về mối liên hệ giữa bài toán “một chiều” của chúng ta với bài toán “hai chiều” M3, đề bài của nó đã được thảo luận trong “Kvant” số 7 năm 1970 (tr. 54—55), và trước hết xác lập sự tương đương của bài toán M50 của chúng ta với bài toán sau: chứng minh rằng có thể chia tập hợp tất cả các số nguyên thành một số hữu hạn cấp số cộng (vô hạn về cả hai phía), sao cho các công sai của chúng từng đôi một khác nhau.

M51

Chứng minh rằng nếu tích của ba số dương bằng một, còn tổng của các số này lớn hơn nghiêm ngặt tổng các nghịch đảo của chúng, thì đúng một trong các số này lớn hơn một.

Gọi $a, b, c$ là các số đã cho. Khi đó $abc = 1$ và $(a - 1)(b - 1)(c - 1) = abc - ab - bc - ac + a + b + c - 1 = a + b + c - \frac{1}{a} - \frac{1}{b} - \frac{1}{c} > 0$, do đó trong ba số $(a - 1), (b - 1), (c - 1)$ có hai số âm và một số dương (cả ba không thể dương, vì $abc = 1$).

M52

Có năm đoạn thẳng sao cho từ bất kỳ ba đoạn nào cũng có thể lập được một tam giác. Chứng minh rằng ít nhất một trong các tam giác này là tam giác nhọn.

Từ các đoạn $x \leq y \leq z$ có thể lập được một tam giác nếu $z < x + y$, và tam giác đó sẽ nhọn nếu $z^2 < x^2 + y^2$. Giả sử có năm đoạn $a_1 \leq a_2 \leq a_3 \leq a_4 \leq a_5$ sao cho từ bất kỳ ba đoạn nào cũng lập được một tam giác không nhọn. Khi đó

$$a_5^2 \geq a_4^2 + a_3^2, \quad a_4^2 \geq a_3^2 + a_2^2, \quad a_3^2 \geq a_2^2 + a_1^2,$$

và do đó

$$a_5^2 \geq 2a_3^2 + a_2^2 \geq 3a_2^2 + 2a_1^2 \geq 2a_1a_2 + a_1^2 = (a_2 + a_1)^2,$$

nghĩa là $a_5 \geq a_2 + a_1$ và do đó, không thể lập một tam giác từ các đoạn thẳng $a_1, a_2, a_5$.

⟦folio 38⟧

M53

Trong tam giác ABC, qua trung điểm M của cạnh BC và tâm O của đường tròn nội tiếp tam giác này kẻ đường thẳng MO, đường thẳng này cắt đường cao AH tại điểm E. Chứng minh rằng đoạn AE bằng bán kính đường tròn nội tiếp.

Ký hiệu độ dài các cạnh của tam giác đối diện với các đỉnh A, B, C lần lượt là a, b, c. Có thể giả sử rằng b>c (b≠c, vì nếu không thì các đường thẳng MO và AH sẽ không cắt nhau mà trùng nhau). Hạ đường vuông góc OP=r xuống BC (hình 2). Khi đó

$$MC = \frac{a}{2}, \quad PC = \frac{a+b-c}{2}, \quad HC = \frac{a^2+b^2-c^2}{2a}.$$

$$\frac{EH}{OP} = \frac{HM}{PM} = \frac{HC-MC}{PC-MC} = \frac{2HC-a}{b-c} = \frac{a^2+b^2-c^2-a^2}{a(b-c)} = \frac{b+c}{a},$$

$$\frac{AE}{r} = \frac{AH}{r} - \frac{EH}{r} = \frac{a+b+c}{a} - \frac{b+c}{a} = 1.$$

Một lời giải khác, bằng hình học, của bài toán này dựa trên bổ đề sau: nếu kéo dài bán kính PO thành đường kính PQ của đường tròn nội tiếp và kẻ đường thẳng AQ cắt cạnh BC tại điểm R, thì các đoạn BP và CR bằng nhau. Để bạn đọc tự chứng minh và sử dụng bổ đề này.

M54

Hai hình chữ nhật bằng nhau được đặt sao cho các đường biên của chúng cắt nhau tại tám điểm. Chứng minh rằng diện tích phần chung của các hình chữ nhật lớn hơn một nửa diện tích của mỗi hình.

Gọi độ dài các cạnh của hình chữ nhật là a và b. Nhận xét rằng trên các cạnh của mỗi hình chữ nhật có đúng hai điểm giao với hai cạnh kề nhau của hình kia. (Dễ chứng minh rằng nếu tổng số điểm giao là 8, thì trên mỗi cạnh phải có không ít hơn hai điểm và rằng không thể có sự cắt nhau của các cạnh của một hình chữ nhật với hai cạnh song song của hình kia). Gọi A và C là các điểm tại đó các cạnh bằng a của những hình chữ nhật khác nhau cắt nhau; B và D là các điểm tại đó các cạnh bằng b cắt nhau. Khi đó, hiển nhiên, đoạn AC là phân giác của góc giữa các cạnh có độ dài a đi qua điểm A (để chứng minh, chỉ cần hạ từ điểm C các đường vuông góc xuống những cạnh này và xét cặp tam giác bằng nhau tạo thành). Tương tự, BD là phân giác của góc giữa các cạnh có độ dài b đi qua điểm B. Do đó, AC⊥BD, và vì thế diện tích

⟦folio 40⟧

và kiểm tra rằng với mỗi $l$ riêng biệt, tổng các hạng tử dạng $X^{k-l}y^l$ ở vế phải và vế trái của đẳng thức là bằng nhau $^*$) (hệ số $C_k^l$ chúng ta không viết):

| | Các số có tổng chữ số lẻ | Các số có tổng chữ số chẵn |
| :--- | :--- | :--- |
| Tổng các hạng tử dạng $X^k$ | $5 \cdot 10^{n-1} \Sigma A^k + 5 \cdot 10^{n-1} \Sigma B^k$ | $5 \cdot 10^{n-1} \Sigma A^k + 5 \cdot 10^{n-1} \Sigma B^k$ |
| Tổng các hạng tử dạng $X^{k-l}y^l$ $1 \leq l \leq k-1$ | $\Sigma A^{k-l}b^l + \Sigma B^{k-l}a^l = \Sigma b^l \Sigma A^{k-l} + \Sigma a^l \Sigma B^{k-l} = s_l (\Sigma A^{k-l} + \Sigma B^{k-l})$ | $\Sigma A^{k-l}a^l + \Sigma B^{k-l}b^l = \Sigma a^l \Sigma A^{k-l} + \Sigma b^l \Sigma B^{k-l} = s_l (\Sigma A^{k-l} + \Sigma B^{k-l})$ |
| Tổng các hạng tử dạng $y^k$ | $5 \Sigma b^k + 5 \Sigma a^k$ | $5 \Sigma a^k + 5 \Sigma b^k$ |

Nhận xét rằng phép tính ban đầu của chúng ta đối với $n=2$ có thể viết bằng các ký hiệu tương tự như sau:
$$\Sigma (A+b) + \Sigma (b+a) = 5\Sigma A + 5\Sigma a + 5\Sigma b + 5\Sigma a, \quad \Sigma (A+a) + \Sigma (B+b) = 5\Sigma A + 5\Sigma a + 5\Sigma B + 5\Sigma b$$
khi $k=1$ chỉ còn lại hạng tử đầu và hạng tử cuối, tương ứng với $l=0$ và $l=k$).

Không khó thấy rằng khẳng định của bài toán đúng không chỉ trong hệ thập phân, mà trong bất kỳ hệ đếm nào khác có cơ số $d$, trong đó $d$ là số chẵn (hãy nghĩ xem tính chẵn của cơ số $d=10$ được dùng ở đâu trong lời giải của chúng ta). Nếu lấy $d=2$, ta được dãy đẳng thức thú vị sau:
$$\begin{array}{l}
1+2=3 \\
1+2+4+7=3+5+6 \\
1^2+2^2+4^2+7^2=3^2+5^2+6^2 \\
1+2+4+7+8+11+13+14=3+5+6+9+10+12+15 \\
1^2+2^2+4^2+7^2+8^2+11^2+13^2+14^2=3^2+5^2+6^2+9^2+10^2+12^2+15^2 \\
1^3+2^3+4^3+7^3+8^3+11^3+13^3+14^3=3^3+5^3+6^3+9^3+10^3+12^3+15^3
\end{array}$$

**M56**

Trên một đường tròn viết theo thứ tự tùy ý bốn số một và năm số không. Sau đó, trong khoảng giữa hai số giống nhau viết số không, giữa hai chữ số khác nhau viết số một, còn các chữ số ban đầu bị xóa đi. Chứng minh rằng dù lặp lại quá trình bao nhiêu lần, ta cũng không bao giờ nhận được một tập hợp gồm $N$ số không. Thật vậy, giả sử rằng ở bước thứ $t$ nào đó lần đầu tiên ta nhận được một tập hợp chỉ gồm các số không. Khi đó ở bước thứ $(t-1)$ cả $N$ chữ số đều giống nhau, và không phải tất cả đều bằng 0, vì thế tất cả đều bằng 1, còn ở bước thứ $(t-2)$ mỗi hai chữ số kề nhau phải khác nhau, nhưng vì $N$ là lẻ nên không tồn tại cách sắp xếp 0 và 1 như vậy trên đường tròn.

Đồng thời, chúng ta đã trả lời (mới chỉ đối với $N$ lẻ) câu hỏi còn chưa được xét trong lời giải M19 (“Kvant” số 11, năm 1970, tr. 37—38); trong bài toán này các số không được gọi là “ô yên tĩnh”, các số một là “ô kích thích”, còn đúng

*) Chúng ta không cần biết các công thức tính $C_k^l$ (cái gọi là “hệ số nhị thức”). Chỉ quan trọng rằng đó là các số, không phụ thuộc vào các biến $X$ và $y$.

**) Những người đã giải bài toán này trước đây có thể đã nhận thấy rằng trong đề bài chúng ta đã đổi chỗ các từ “số một” và “số không”. Điều đó, dĩ nhiên, không làm thay đổi sự tồn tại của các bài toán M19 và M56, sẽ được nói đến dưới đây.

⟦folio 41⟧

quy tắc chuyển trạng thái hoàn toàn giống nhau. Theo các thuật ngữ này, kết quả của chúng tôi được phát biểu như sau: nếu $N$ lẻ, và ở thời điểm ban đầu không phải mọi ô đều kích thích (và không phải mọi ô đều ở trạng thái nghỉ), thì sự kích thích sẽ không bao giờ tắt.

Điều gì sẽ xảy ra với các $N$ khác? Để làm rõ điều này, ta dùng bổ đề sau (có thể chứng minh bằng quy nạp theo $k$; nó đúng cả cho bài toán trên đường thẳng lẫn trên đường tròn): nếu tại $t=0$ ở vị trí $2^{k-1}-M$ theo cả hai phía của chữ số đã cho $a$ có các chữ số giống nhau, thì sau $t=2^k$ bước tại vị trí $a$ sẽ là số không, còn nếu chúng khác nhau thì là số một. Từ đây lập tức suy ra rằng nếu $N=2^m$, trong đó $m$ là số tự nhiên, thì từ bất kỳ cấu hình nào sau $N$ bước cũng thu được cấu hình chỉ gồm các số không.

Bây giờ giả sử $N=2^m L$, trong đó $L$ là số lẻ. Ta hãy theo dõi những thay đổi xảy ra sau mỗi $T=2^m$ bước. Đối với mỗi nhóm gồm $L$ chữ số, nằm cách nhau $2^m$ («tại các đỉnh của một $L$-giác đều»), những thay đổi này sẽ hoàn toàn giống như thể chỉ $L$ chữ số ấy được xếp trên một đường tròn, cùng quá trình được lặp lại với chúng, và ta theo dõi từng bước. Từ đây không khó tìm được đáp số trong trường hợp tổng quát nhất: trạng thái «toàn số không» đạt được khi và chỉ khi dãy ban đầu gồm 0 và 1 là tuần hoàn với chu kỳ $2^m$ (xem hình 4).

**M57**

a) Tìm số $k$ chia hết cho 2 và 9, đồng thời chỉ có 14 ước (kể cả 1 và $k$).

b) Chứng minh rằng nếu thay 14 bằng 15 thì bài toán có nhiều nghiệm, còn nếu thay 14 bằng 17 thì hoàn toàn không có nghiệm.

Giả sử $M=p_1^{\alpha_1}p_2^{\alpha_2}\dots p_r^{\alpha_r}$ — phân tích số $M$ ra thừa số nguyên tố; để xác định, ta sẽ coi rằng $\alpha_1 \geqslant \alpha_2 \geqslant \dots \alpha_r \geqslant 1$. Các ước của số $M$ có dạng $p_1^{\beta_1}p_2^{\beta_2}\dots p_r^{\beta_r}$, trong đó mỗi $\beta_i$ độc lập với các số còn lại có thể nhận các giá trị 0, 1, ..., $\alpha_i$, và vì vậy tổng số ước của $M$ (kể cả 1 và $M$) bằng $(\alpha_1+1)(\alpha_2+1)\dots(\alpha_r+1)$ (xem lời giải bài toán 1 trong bài “Tổ hợp” trên “Kvant” số 1, năm 1971, tr. 19).

a) 14 chỉ có thể phân tích thành thừa số theo một cách: $14=7 \cdot 2$, vì vậy, nếu $M$ có 14 ước, thì $r=2$, $\alpha_1=6$, $\alpha_2=1$. Ta còn biết rằng 3 xuất hiện trong phân tích của $M$ với số mũ lớn hơn 1, còn 2 — với số mũ lớn hơn 0. Suy ra $M=3^6 \cdot 2=1458$.

b) Với 15 ước, các đáp số có thể là $M=3^2 \cdot 2^4$ và $M=3^4 \cdot 2^2$, còn 17 ước chỉ có thể thuộc về các số dạng $M=p^{16}$, trong đó $p$ là số nguyên tố.

**M58**

Trên mặt phẳng cho ba đường thẳng cắt nhau tại một điểm. Trên một trong các đường thẳng đó đánh dấu một điểm. Biết rằng các đường thẳng là các đường phân giác của một tam giác nào đó, còn điểm đã đánh dấu là một trong các đỉnh của nó. Dựng tam giác này.

Lời giải thứ nhất. Giả sử $O$ là giao điểm của các đường phân giác $AK$, $BL$ và $CM$ của tam giác $ABC$ (hình 5); khi đó

$$\angle MOB = \angle OCB + \angle OBC = \frac{1}{2} (\angle ACB + \angle ABC) = \frac{\pi}{2} - \angle CAK,$$

tức là $\angle CAK = \frac{\pi}{2} - \alpha$. Vì vậy, nếu cho các đường thẳng $AK$, $BL$, $CM$ và điểm $A$, thì dựng ở hai phía của tia $AO$ các góc bằng $\varphi = \frac{\pi}{2} - \alpha$. Ta sẽ tìm được các đỉnh cần tìm $B$ và $C$ (với điều kiện $\varphi > 0$.

⟦folio 42⟧

Hình 5. Hình 6.

φ<β và φ<γ). Còn cần chứng minh rằng trong tam giác ABC đã dựng, các đường thẳng BL và CM đi theo các đường phân giác. Các góc ABL và ACM dễ tính — chúng lần lượt bằng $\frac{\pi}{2} - \beta$ và $\frac{\pi}{2} - \gamma$. Khó khăn chỉ nằm ở việc chứng minh rằng $\Rightarrow LBC = \frac{\pi}{2} - \beta$ và $\Rightarrow MCA = \frac{\pi}{2} - \gamma$ (mặc dù rõ ràng tổng của chúng bằng $\alpha$); chẳng hạn có thể chứng minh điều đó như sau: nếu $\Rightarrow LBC < \Rightarrow ABL$, thì đường phân giác của góc ABC cắt đoạn AO, vì vậy đường phân giác của góc ACB cũng cắt nó, và do đó, $\Rightarrow MCB < \Rightarrow ACM$, nên tổng $\Rightarrow LBC + \Rightarrow MBC$ nhỏ hơn $(\frac{\pi}{2} - \beta) + (\frac{\pi}{2} - \gamma) = \alpha$. Hoàn toàn tương tự có thể chỉ ra rằng trường hợp $\Rightarrow LBC > \Rightarrow ABL$ là không thể.

Lời giải thứ hai. Dựng các điểm $A'$ và $A''$ đối xứng với điểm đã cho $A$ qua các đường phân giác không đi qua $A$. Rõ ràng cả hai điểm $A'$ và $A''$ phải nằm trên đường thẳng BC — trên cạnh của tam giác cần tìm ABC (hoặc trên phần kéo dài của nó). Kẻ đường thẳng qua $A'$ và $A''$, như vậy ta sẽ tìm được các điểm cần tìm B và C (hình 6).

Lưu ý rằng tuy lời giải thứ hai hiệu quả hơn, nhưng với cách tiếp cận này khó viết ra các điều kiện để bài toán có lời giải *). Các điều kiện đó là: $\alpha < \frac{\pi}{2}$, $\beta < \frac{\pi}{2}$, $\gamma < \frac{\pi}{2}$ (vì $\alpha + \beta + \gamma = \pi$, chúng cũng có thể được viết như sau: $\alpha + \beta > \frac{\pi}{2}$, $\beta + \gamma > \frac{\pi}{2}$, $\gamma + \alpha > \frac{\pi}{2}$). Nếu chúng được thỏa mãn thì lời giải là duy nhất. Hãy suy nghĩ xem có thể nhận được các điều kiện này bằng mỗi cách giải đã trình bày ở trên như thế nào.

M59

Có vài quả cân có khối lượng 1 g, 2 g, 3 g,..., n g. Cần chia chúng thành ba nhóm có khối lượng bằng nhau. Với những $n$ nào thì làm được điều đó?

Ta sẽ chỉ ra rằng điều này làm được khi và chỉ khi $n > 3$ và một trong hai số $n$ hoặc $n+1$ chia hết cho 3 (tức là khi $n$ bằng 5, 6, 8, 9, 11, 12, 14, 15, ...).

*) Có thể xảy ra rằng hai trong các đường thẳng đã cho là các đường phân giác của các góc ngoài, chứ không phải các góc trong của tam giác đã dựng, điều đó không ảnh hưởng đến ta.

⟦folio 43⟧

Sự cần thiết của các điều kiện này là hiển nhiên, vì tổng khối lượng các quả cân $1 + 2 + 3 + \dots + n = \frac{n(n+1)}{2}$ phải chia hết cho 3.

Để chứng minh, trước hết chỉ cần thấy rằng việc chia là có thể khi $n$ bằng 5, 6, 8 và 9 (điều này được chỉ ra ở hình 7). Mọi giá trị $n$ khác mà ta quan tâm đều nhận được từ bốn giá trị này bằng cách cộng thêm một số lượng nào đó các nhóm sáu, còn bất kỳ nhóm nào gồm sáu số nguyên liên tiếp $a+1, \dots, a+6$ cũng dễ chia thành ba cặp số có tổng bằng nhau: $a+1$ và $a+6$, $a+2$ và $a+5$, $a+3$ và $a+4$.

Hình 7.

M60

Xét tất cả các số tự nhiên mà trong cách viết thập phân chỉ có các chữ số 1 và 0. Hãy chia các số này thành hai nhóm sao cho tổng của bất kỳ hai số khác nhau thuộc cùng một nhóm đều chứa trong cách viết thập phân của nó ít nhất hai chữ số 1.

Ta xếp vào một nhóm tất cả các số mà trong cách viết có số lẻ chữ số 1, còn vào nhóm kia — tất cả các số mà trong cách viết có số chẵn chữ số 1. Khi đó rõ ràng là hai số chỉ khác nhau ở một hàng không thể thuộc cùng một nhóm, vì thế cách chia này thỏa mãn yêu cầu của bài toán (các chữ số 1 xuất hiện ở những hàng của tổng mà ở một số có 1, còn ở số kia thì không).

Nhiều bạn đọc đã đưa ra lập luận chứng minh rằng cách chia đã mô tả:

nhóm thứ nhất: 1, 10, 100, 111, 1000, 1011, 1101, 1110, ...
nhóm thứ hai: 11, 101, 110, 1001, 1010, 1100, 1111, 10001, ...

là duy nhất thỏa mãn điều kiện của bài toán.

Những lời giải đầy đủ nhất cho các bài toán đã được thảo luận ở trên đã được gửi cho chúng tôi bởi V. Didenko từ làng Vesely Kut, tỉnh Odessa, E. Turkevich từ thành phố Chernivtsi, A. Rubin từ làng Ukladovka, tỉnh Vinnitsa, A. Slinkin từ Moskva, Ya. Tomsinsky từ Leningrad, M. Perelmuter từ Kiev, O. Khudaverdyan từ Yerevan.

M45

(Tiếp theo. Xem phần đầu lời giải trong “Kvant” số 7, tr. 30.)
Ta còn phải chứng minh sự kiện sau.

Định lý. Từ $2p$-1 số nguyên bất kỳ có thể chọn ra $p$ số mà tổng của chúng chia hết cho $p$ ($p$ là một số nguyên tố tùy ý).

Sau đây là chứng minh do S. Voronin (Moskva) đề xuất.

Rõ ràng, trong chứng minh ta có thể xét mọi số “theo môđun $p$”, tức là chỉ quan tâm đến việc một số nào đó cho số dư nào trong các số dư 0, 1, 2, ..., $p-1$ khi chia cho $p$. Thuận tiện là hình dung (đặc biệt khi nói về “phép cộng theo môđun $p$”) rằng $p$ số dư này được xếp trên một vòng tròn (hình 8).

Bổ đề. Cho $r$ số nguyên $b_1, b_2, \dots, b_r$; $0 < b_i < p$ với mọi $i=1, 2, \dots, r$ và $0 < r < p$ ($p$ là số nguyên tố). Khi đó từ các số này có thể lập được ít nhất $r+1$ tổng cho các số dư khác nhau khi chia cho $p$ (trong đó cho phép có tổng của “tập rỗng các số hạng”, được coi là bằng không, các tổng gồm một số hạng, hai số hạng,..., tất cả $r$ số hạng).

Chứng minh. Với $r=1$ điều này hiển nhiên: các tổng cho các số dư 0 và $b_1$. Giả sử điều này đúng với $r=k<p-1$ và sai với $r=k+1$, rồi đi đến mâu thuẫn. Giả sử các tổng gồm $k$ số hạng $b_1, b_2, \dots, b_k$ cho $k+1$ số dư khác nhau 0, $s_1, \dots, s_k$. Khi đó,

⟦folio 44⟧

Hình 8. Để tìm tổng $a+b$ theo môđun $p$, cần đếm từ $a$ ngược chiều kim đồng hồ $b$ đơn vị (trong hình này, ứng với $p=11$, biểu diễn tổng 8+8, theo môđun 11 bằng 5).

Vì sau khi thêm $b=b_{k+1}$ số lượng các tổng khác nhau không được tăng lên, nên mọi tổng

$$0+b, s_1+b, \ldots, s_k+b$$

(theo môđun $p$) nằm trong tập hợp

$$\{0, s_1, \ldots, s_k\}.$$

Nói cách khác, nếu cộng $b$ vào bất kỳ phần tử nào của tập hợp này, thì lại thu được một phần tử của chính tập hợp ấy (hãy thử hình dung một tập hợp như vậy trên hình 8). Như vậy, tập hợp này hiển nhiên chứa các phần tử 0, $b$, $2b$, $3b$, $\ldots$, $(p-1)b$. Nhưng rõ ràng tất cả các phần tử này đều khác nhau (theo môđun): hiệu

$$ib-jb=(i-j)b,$$

trong đó $0<i-j<p$ và $0<b<p$, không thể chia hết cho $p$, vì $p$ là số nguyên tố. Như vậy, ta đã chứng minh rằng tập hợp $\{0,s_1, \ldots, s_k\}$ chứa cả $p$ phần tử khác nhau, mặc dù đã giả sử rằng

$$k+1<p.$$

Bổ đề đã được chứng minh.

Chứng minh định lý. Gọi

$$a_1 \leqslant a_2 \leqslant \ldots \leqslant a_p \leqslant a_{p+1} \leqslant \ldots \leqslant a_{2p-1}$$

là các số dư khi chia $2p-1$ số đã cho cho $p$. Xét thêm $p$ số như vậy:

$$a_{p+1}-a_2, a_{p+2}-a_3, \ldots, a_{2p-1}-a_p.$$

(*)

Nếu một trong các số đó bằng không, chẳng hạn

$$a_{p+1}-a_{l+1}=0,$$ thì $a_{l+1}=a_{l+2}=a_{l+3}=\ldots=a_{l+p}$, và tổng của $p$ số tương ứng chia hết cho $p$. Còn lại xét trường hợp mọi số (*) đều khác không.

Ta tìm số dư $x$ khi chia tổng $a_1+a_2+\ldots+a_p$ cho $p$. Nếu $x=0$, thì mọi việc đều rõ. Nếu $x\neq 0$, thì, dùng bổ đề, ta có thể lập từ các hiệu (*) một tổng cho số dư $p-x$ khi chia cho $p$. Cộng các hiệu tương ứng vào $a_1+a_2+\ldots+a_p$ và thực hiện các phép khử hiển nhiên, ta sẽ nhận được một tổng gồm $p$ số hạng chia hết cho $p$.

Dựa vào kết quả của bài toán M45, không khó để xác lập rằng mệnh đề «Từ bất kỳ $a$ số nguyên nào cũng có thể chọn $b$ số mà tổng của chúng chia hết cho $c$» (trong đó $a, b, c$ là những số tự nhiên cụ thể) đúng khi và chỉ khi $b$ chia hết cho $c$ và $a \geq b+c-1$.

N. B. Vasiliev

Trong số này chúng tôi công bố lời giải các bài toán F66—F71.

F66

Một ampe kế và một vôn kế được mắc nối tiếp với một pin có suất điện động 9 v và điện trở trong chưa biết (hình 9). Điện trở của các dụng cụ không biết. Nếu mắc song song với vôn kế một điện trở (giá trị của nó cũng không biết), thì số chỉ của ampe kế tăng gấp đôi, còn số chỉ của vôn kế giảm đi một nửa. Số chỉ của vôn kế sau khi mắc điện trở là bao nhiêu?

Vôn kế chỉ hiệu điện thế trên chính nó, còn ampe kế chỉ dòng điện đi qua nó. Theo định luật Ôm đối với mạch kín, suất điện động của pin bằng tổng các hiệu điện thế trên các đoạn mạch: $U$ — trên vôn kế và $U_1$ — trên điện trở trong của nguồn và ampe kế:

$$E=U+U_1.$$

⟦folio 45⟧

Hình 9. Hình 10.

Sau khi mắc điện trở, độ giảm điện thế trên vôn kế và trên điện trở mắc song song với nó trở thành $U' = \frac{U}{2}$ (số chỉ của vôn kế). Đồng thời, độ giảm điện thế trên điện trở của nguồn và ampe kế tăng gấp hai lần và trở thành $U'_1 = 2U_1$. Thật vậy, điện trở của đoạn này không thay đổi, còn dòng điện đi qua nó tăng gấp đôi. Vì vậy

$$E = \frac{U}{2} + 2U_1.$$

(2)

Giải đồng thời các phương trình (1) và (2), ta được $U = 6\ \theta$. Do đó, sau khi mắc điện trở, vôn kế chỉ hiệu điện thế

$$U' = \frac{U}{2} = 3\theta.$$

Lời giải đúng được gửi bởi N. Fedin (Omsk), S. Ivanov (Moskva), E. Gubarev (Moskva), V. Sytsev (Alga, tỉnh Aktiubinsk), N. Smirnov (Gorky), A. Anishchenko (Sarapul, CHXHCNXV Udmurt), A. Braverman (Perm), A. Seniavin (Moskva), V. Pomatsev (Gorky), V. Kalinichev (Moskva), M. Preger (Tomsk).

F67

Thiết bị đệm (hình 10) gồm thanh $A$, lò xo $B$ lắp trên thanh, và ống lót dẫn hướng $C$. Ống lót có thể chuyển động bên trong một rãnh được tạo trong bức tường nặng $D$. Khi ống lót chuyển động, giữa mặt ngoài của nó và tường tác dụng một lực ma sát có độ lớn không đổi $F_{Тр}$. Thanh chuyển động trong ống lót, còn lò xo chuyển động dọc theo thanh không ma sát.

Một quả cầu khối lượng $m$ tì vào mặt đầu của thanh $A$, có vận tốc $v_0$ trước va chạm. Quả cầu sẽ bật ra với vận tốc nào?

Khối lượng của thanh, lò xo và ống lót nhỏ không đáng kể so với khối lượng của quả cầu. Hệ số đàn hồi của lò xo là $k$.

Khi quả cầu va chạm, thanh bắt đầu chuyển động, nén lò xo. Khi đó, lò xo bị biến dạng tác dụng lên ống lót một lực $F = kx$, trong đó $x$ là độ biến dạng của lò xo. Nếu vận tốc ban đầu của quả cầu đủ lớn, thì độ biến dạng của lò xo đạt giá trị cực đại $x_{\max}$, tại đó lò xo tác dụng lên ống lót một lực bằng lực ma sát của ống lót với tường. Sau đó ống lót bắt đầu chuyển động, và trong khi ống lót chuyển động, lò xo sẽ không biến dạng: lực nén nó không đổi và bằng $F_{Тр}$. Vì khi ống lót chuyển động, lực ma sát tác dụng lên nó, nên động năng của hệ chuyển thành nhiệt, và sau một thời gian quả cầu và thanh dừng lại. Sau đó lò xo bắt đầu giãn ra. Điều này, dĩ nhiên, sẽ không làm ống lót chuyển động — lực mà nó tác dụng.

⟦folio 46⟧

tác dụng lên nó từ phía lò xo nhỏ hơn $F_{\tau p} = kx_{\max}$, vì $x < x_{\max}$. Vì thế trong hệ sẽ không còn tổn hao năng lượng nữa. Khi lò xo duỗi ra, thế năng biến dạng của nó $W_{\pi} = \frac{kx_{\max}^2}{2}$ sẽ chuyển thành động năng của viên bi.

Trong đó thế năng của viên bi bằng không.
Bây giờ hãy viết định luật bảo toàn năng lượng

$$\frac{mv^2}{2} = \frac{kx_{\max}^2}{2},$$

trong đó $v$ là vận tốc của viên bi sau khi nó bật ra khỏi tường.

Vì $x_{\max} = \frac{F_{\tau p}}{k}$, ta được $v = \sqrt{\frac{F_{\tau p}^2}{km}}$.

Khi vận tốc $v_0$ đủ lớn, vận tốc của viên bi bật ra khỏi thanh không phụ thuộc vào vận tốc ban đầu của nó. Hệ “nuốt” toàn bộ phần dự trữ năng lượng vượt quá giá trị $W = \frac{kx_{\max}^2}{2}$.

Bây giờ hãy làm rõ “vận tốc $v_0$ đủ lớn” nghĩa là gì. Đó là vận tốc mà tại đó lực do lò xo tác dụng lên ống lót đạt giá trị $F_{\tau p}$, và do đó, biến dạng của lò xo đạt giá trị $x_{\max} = \frac{F_{\tau p}}{k}$. Rõ ràng, để điều này xảy ra, động năng ban đầu của viên bi phải lớn hơn giá trị $\frac{kx_{\max}^2}{2} = \frac{F_{\tau p}^2}{2k}$:

$$\frac{mv^2}{2} > \frac{F_{\tau p}^2}{2k}.$$

Điều kiện này cho ta giới hạn của “vận tốc đủ lớn”:

$$v_0 > \sqrt{\frac{F_{\tau p}^2}{km}}.$$

Còn va chạm sẽ xảy ra thế nào nếu vận tốc ban đầu của viên bi nhỏ hơn giá trị này hoặc bằng nó?

Trong trường hợp này, biến dạng của lò xo nhỏ hơn $x_{\max}$ và lò xo sẽ không làm các ống lót dịch chuyển. Điều đó có nghĩa là sẽ không có tổn hao năng lượng và viên bi sẽ bật lại, có cùng động năng, và do đó cùng vận tốc, như trước va chạm. Vậy,

$$v = \begin{cases} v_0 \text{ khi } v_0 \leqslant \sqrt{\frac{F_{\tau p}^2}{km}}, \\ \sqrt{\frac{F_{\tau p}^2}{km}} \text{ khi } v_0 > \sqrt{\frac{F_{\tau p}^2}{km}}. \end{cases}$$

Lời giải đúng đã được gửi bởi P. Mkrtchyan (Yerevan), Kutsek (Rzhev), H. Fedin (Omsk), I. Grishik (David-Gorodok, tỉnh Brest, CHXHCNXV Belarus), A. Vyrodov (Gagra), P. Zaitsev (Gagra), M. Premer (Tomsk).

Ф68

Thành bình chứa khí có nhiệt độ $T$. Nhiệt độ của khí là $T_1$. Trong trường hợp nào áp suất của khí lên thành bình lớn hơn: khi thành bình lạnh hơn khí ($T < T_1$), hay khi nhiệt độ ($T > T_1$)?

Nhiệt độ của khí được xác định bởi động năng trung bình của các phân tử của nó: $\frac{mv^2}{2} = \frac{3}{2} kT$ ($k$ — hằng số Boltzmann). Điều đó có nghĩa là nhiệt độ của khí càng

⟦folio 47⟧

cao, vận tốc trung bình của các phân tử của nó càng lớn, tức là động lượng trung bình của một phân tử càng lớn.

Nếu nhiệt độ của thành trùng với nhiệt độ của khí, thì phân tử, va vào thành, đổi động lượng $p_0$ của nó thành $-p_0$. Vậy độ biến thiên động lượng bằng $2p_0$.

Khi $T > T_1$, khí được đun nóng. Điều đó có nghĩa là các phân tử khí bật khỏi thành với vận tốc lớn hơn khi chúng bay tới, và do đó với động lượng lớn hơn (hình 11, a). Độ biến thiên động lượng trong trường hợp này sẽ lớn hơn $2p_0$.

Nếu $T_1 < T$, thì khí bị làm lạnh, tức là các phân tử khí bật ra khỏi thành với xung lượng nhỏ hơn khi đập vào thành (hình 11, b). Rõ ràng, trong trường hợp này sự thay đổi xung lượng của phân tử cũng nhỏ hơn so với trường hợp $T_1 > T$. Vì theo định luật II Newton, sự thay đổi xung lượng tỉ lệ với lực trung bình tác dụng lên phân tử từ phía thành, còn theo định luật III Newton, lực trung bình tác dụng lên phân tử bằng về độ lớn với lực trung bình tác dụng lên thành, nên khi $T_1 < T$ áp suất của khí lên thành lớn hơn khi $T_1 > T$.

Lời giải đúng được gửi bởi V. Chupin (Torzhok), N. Fedin (Omsk), V. Kalintsev (Moskva), S. Ivanov (Moskva).

Hình dạng bề mặt chất lỏng phải sao cho lực phản ứng N của chất lỏng xung quanh tác dụng lên một phần tử thể tích chất lỏng có khối lượng $\Delta m$ ở gần bề mặt được hướng vuông góc với bề mặt. Nếu không, lực N sẽ có thành phần hướng dọc theo bề mặt chất lỏng, và chất lỏng sẽ không thể ở trạng thái cân bằng.

Bây giờ hãy xét lực N được hướng như thế nào. Nó phải cân bằng hai lực: lực hút $F_1$ của Trái Đất, hướng về tâm Trái Đất, và lực hút bổ sung $F_2$ của quả cầu, hướng về tâm quả cầu (trong hình 12 lực $F_2$ được vẽ lớn không tương xứng so với lực $F_1$). Lực N phải bằng về độ lớn và ngược chiều với hợp lực Q của các lực $F_1$ và $F_2$. Vậy nên nó lệch sang phải so với phương thẳng đứng, và mặt nước phía trên quả cầu là lồi.

Hãy ước lượng độ lớn của “chỗ phồng” trên mặt nước. Xét điểm B nằm cách một khoảng nhỏ x so với đường thẳng đứng AO đi qua tâm quả cầu ($x \ll r$, trong đó r — bán kính quả cầu), O — tâm cong và BO = R — bán kính cong của mặt nước.

$Q \approx F_1$ (vì $F_2 \ll F_1$), và $Q \sin \alpha = F_2 \sin \beta$. Vì các góc α và β nhỏ ($x \ll r$, $x \ll R$), nên

$$\sin \alpha \approx \mathrm{tg} \alpha \approx \frac{x}{R}$$

Do đó có thể coi rằng

$$Q(x/R) = F_2(x/r)$$

⟦folio 48⟧

hoặc
$$R = r \frac{Q}{F_2} = r \frac{F_1}{F_2}.$$

Nhưng
$$F_1 = \gamma \frac{\left( \frac{4}{3} \pi R_3^3 \rho \right) \Delta m}{R_3^2} = \frac{4}{3} \pi \gamma r R_3 \rho \Delta m$$
($R_3$ – bán kính Trái Đất, $\rho$ – khối lượng riêng của nó), còn
$$F_2 = \gamma \frac{\frac{4}{3} \pi r^3 (\rho_1 - \rho_0) \Delta m}{r^2} = \frac{4}{3} \pi \gamma r (\rho_1 - \rho_0) \Delta m$$
($\rho_1$ – khối lượng riêng của quả cầu, $\rho_0$ – khối lượng riêng của nước). Do đó
$$R = r \frac{\frac{4}{3} \pi \gamma R_3 \rho \Delta m}{\frac{4}{3} \pi \gamma r (\rho_1 - \rho_0) \Delta m} = R_3 \frac{\rho}{\rho_1} \approx R_3 \frac{\rho}{\rho_1}$$
(vì $\rho_1 \gg \rho_0$). Thay vào đây các giá trị $R_3 = 6,4 \cdot 10^6 m$, $\rho = 5,5 e/cm^3$ và $\rho_1 = 11,3 e/cm^3$, ta được $R \approx 3,2 \cdot 10^6 m$.

Giả sử phần phồng lan ra đến khoảng cách $x$ từ điểm $A$ (ước lượng này phụ thuộc rất nhiều!), ta tìm được chiều cao của nó
$$h = x \lg \alpha \approx \frac{r^2}{R}.$$

Nếu bán kính của quả cầu chì bằng 1 m, thì $h \approx 3 \cdot 10^{-7} m$.

Điều đó có nghĩa là không thể quan sát thực nghiệm hiệu ứng phồng lên, ngay cả bằng các phương pháp giao thoa. Bởi vì bước sóng ánh sáng là vài nghìn angstrom ($1 \text{Å} = 10^{-10} m$), tức là lớn hơn độ phồng lên.

Lời giải đúng do $H$. Fedin (Omsk) gửi đến.

F70

Người đi xe đạp dễ dàng tạo ra lực kéo 10 kG. Lực cản không vượt quá 5 kG. Có vẻ như, trong vài giờ xe đạp có thể đạt tới vận tốc vũ trụ cấp hai. Tuy nhiên, điều đó vẫn chưa ai làm được. Tại sao?

Lực mà người đi xe đạp có thể đạp lên bàn đạp không cố định và phụ thuộc vào tốc độ đi xe đạp (hình 13). Nó cực đại khi $v = 0$ và trở thành bằng không ở tốc độ mà tại đó chu kì quay của bàn đạp trở nên bằng tốc độ phản ứng của người đi xe đạp. Sau đó tốc độ đi xe đạp không thể tăng thêm nữa.

Nhiều độc giả lập luận như sau: công suất mà xe đạp phát triển không thể vượt quá một giá trị cực đại nào đó. Nhưng

⟦folio 49⟧

$N = F \cdot v$, vì vậy tốc độ không thể lớn hơn

$$v = \frac{N_{\text{max}}}{F - F_{\text{trp}}}.$$

Điều đó, dĩ nhiên, đúng và chính là do sự phụ thuộc của lực mà người đạp lên bàn đạp vào tốc độ chuyển động có dạng như trên hình 13.

F71

Có một đoạn $AB$ mang điện tích phân bố đều. Hướng của điện trường do đoạn này tạo ra tại điểm $C$ là hướng nào: theo trung tuyến của tam giác $ABC$? theo đường phân giác của nó? theo đường cao? không theo đường nào trong các đường này?

Cường độ điện trường là một vectơ, còn trong bài toán của chúng ta chỉ có bốn hướng được xác định: theo trung tuyến, đường phân giác hoặc đường cao của tam giác $ABC$ và song song với đoạn $AB$. Vectơ cường độ điện trường phải hướng theo một trong các hướng đó. Rõ ràng nó không thể song song với đoạn $AB$: cường độ điện trường của đoạn mang điện bằng tổng các cường độ điện trường của các phần của đoạn, và tất cả chúng đều hướng về đoạn hoặc ra xa đoạn (tùy theo dấu điện tích của đoạn).

Đường cao của tam giác $ABC$ cũng không thích hợp: chẳng hạn, nếu điểm $C$ nằm lệch về một phía của đoạn, ở khoảng cách lớn hơn nhiều so với độ dài đoạn, thì rõ ràng cường độ điện trường tại điểm đó phải hướng về đoạn $AB$, chứ không theo đường vuông góc với nó.

Vậy, ta còn lại đường trung tuyến và đường phân giác. hướng của trường $E$ của đoạn thẳng bằng tổng hướng của các trường do các phần của nó tạo ra. Để vectơ $E$ hướng dọc theo đường trung tuyến, cần các đoạn có độ dài bằng nhau $\Delta x$, nằm cách đều trung điểm của đoạn thẳng, tạo ra các trường như nhau tại điểm $C$.

Chỉ trong trường hợp đó tổng các vectơ $\Delta E$ mới hướng dọc theo đường trung tuyến của tam giác $ABC$. Tuy nhiên điều này là không thể: các đoạn có độ dài bằng nhau có điện tích như nhau $\Delta Q = \sigma \Delta x$ (σ — mật độ điện tích dài, tức là điện tích trên một đơn vị độ dài của đoạn thẳng), còn khoảng cách đến điểm $C$ thì khác nhau.

⟦folio none⟧

Vậy vectơ $E$ hướng dọc theo đường phân giác của tam giác $ABC$.
Hãy kiểm chứng điều đó. Ta tìm phương của trường do đoạn $\Delta x$ gây ra sao cho đường thẳng kẻ từ nó đến điểm $C$ tạo với đường cao của tam giác một góc $\alpha$ và $\Delta x \ll r$ (hình 14). $\Delta E = \frac{\Delta x \sigma}{r^2}$. Nếu đoạn $\Delta x$ nhìn từ điểm $C$ dưới góc $\Delta \alpha$, thì $\Delta x_1 = r \Delta \alpha$ (góc $\alpha$ nhỏ, nên $tg \frac{\Delta \alpha}{2} = \frac{\Delta \alpha}{2}$, còn $\frac{\Delta x_1}{2} = r tg \frac{\Delta \alpha}{2}$) và $\Delta x = \frac{\Delta x_1}{\sin(90^\circ - \alpha)} = \frac{r \Delta \alpha}{\cos \alpha}$. Do đó $\Delta E = \frac{r \Delta \alpha \sigma}{r^2 \cos \alpha} = \frac{\Delta \alpha \sigma}{r \cos \alpha}$. Nhưng $r \cos \alpha = h$.
Vì vậy
$$\Delta E = \frac{\Delta \alpha \sigma}{h}.$$

Cường độ trường của một đoạn thẳng, được nhìn từ điểm $C$ dưới góc $\Delta \alpha$, không phụ thuộc vào góc $\alpha$. Mọi đoạn thẳng được nhìn từ điểm $C$ dưới cùng một góc đều tạo ra tại đó trường có cùng độ lớn. Nhưng đối với bất kỳ đoạn $\Delta x$ nào nằm bên trái đường phân giác $CD$ của tam giác $ABC$, có thể tìm được một đoạn ở bên phải nó sao cho đoạn này được nhìn từ điểm $C$ dưới cùng góc $\Delta \alpha$ như đoạn $\Delta x$, và góc $\beta$, được tạo bởi đường thẳng nối nó với điểm $C$, cũng giống như đối với đoạn $\Delta x$. Vì các đoạn này tạo ra tại điểm $C$ những trường như nhau, nên vectơ $\Delta E$ là tổng các vectơ $\Delta E_1$ và $\Delta E_2$ của các trường có hướng do các đoạn tạo ra được hướng theo đường chéo của hình thoi dựng trên các vectơ $\Delta E_1$ và $\Delta E_2$, tức là dọc theo đường phân giác $CD$. Điều này đúng với mọi góc $\beta$, tức là với mọi cặp đoạn thẳng. Vậy vectơ hướng của trường do đoạn $AB$ tạo ra cũng được hướng dọc theo đường phân giác của tam giác $ABC$.

Lời giải đúng được gửi bởi N. Fedin (Omsk) và I. Grichik (David-Gorodok, tỉnh Brest).

I. Sh. Slobodetsky.

Về «Các bài toán trên giấy kẻ ô»

1. Thêm vào mỗi trong bốn đầu của hình chữ thập hai điểm. Số các hình vuông có thể có với các đỉnh tại những nút được đánh dấu sẽ tăng thêm 10 (bốn hình vuông nhỏ màu đỏ (xem hình.]), bốn hình vuông có mẫu được tô màu đen; hai hình vuông, một trong số đó được đánh dấu màu xanh).

Hình chữ thập trong bài toán có thể được xem là các hàng nút bổ sung cho ô trung tâm, ô này chỉ cho phép một hình vuông. Nó cho phép dựng $10 \cdot 8 + 1 = 81$ hình vuông khác nhau.
