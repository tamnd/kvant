---
id: 1976-2-sukonnik-gornshteyn-prostoy-otvet-v-slozhnoy-zadache-edb188a9
issue: kvant_1976_2
year: 1976
number: "2"
title: Đơn giản đáp số đến "phức tạp" bài toán
authors:
  - Суконник Я. Н.
  - Горнштейн П. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 48
page_last: 52
page_labels: 46-50
tag: R33P
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 55dc8f9097fd0b5c5423bb85b854cacad63774781c98dd1979ad7194f68faf1f
prompt_sha256: draft-1
translated_from: content/ru/1976/02/articles/13_sukonnik-gornshteyn-prostoy-otvet-v-slozhnoy-zadache-edb188a9.md
source_content_sha256: a89877da8f813be4e46cd67feec7cc2052cc769082f344efe0b3816fe512257f
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 46⟧

Đơn giản đáp số đến Phức tạp bài toán

Bài viết này một lần nữa đặt ra câu hỏi nên giải phương trình phẳng bài toán như thế nào - “đại số” hay “hình học thuần túy”? *) Tất nhiên, sẽ không hợp lý nếu so sánh hai phương pháp này; bài toán chính khi chuẩn bị cho kỳ thi tuyển sinh là học cách kết hợp chúng. Ngôn ngữ “hình học thuần túy” lời giải không phải lúc nào cũng phù hợp - chỉ khi nó xuất hiện trong đầu bạn đủ nhanh. Chúng tôi chỉ muốn cảnh báo người nộp đơn tương lai về những phép tính khó hiểu trong một hình học tương đối đơn giản bài toán, có thể giải dễ dàng bằng cách sử dụng ý tưởng “hình học thuần túy”. Các vấn đề được xem xét trong bài viết này cho phép lời giải khác nhau, đôi khi rất cồng kềnh, mặc dù đáp số luôn đơn giản. Sử dụng các ví dụ của họ, bạn có thể dễ dàng thấy tầm quan trọng của việc có thể suy nghĩ “về mặt hình học” và áp dụng các định lý phổ biến chung của thuyết hành tinh. Tất nhiên, việc tìm một hình học đơn giản lời giải đòi hỏi một chút sáng tạo. Khả năng “giải bài toán đỏ” là một nghệ thuật mà bạn chỉ có thể thành thạo bằng cách không ngừng phát triển tư duy hình học và trực giác của mình. Và để làm được điều này, hãy giải càng nhiều bài toán càng tốt và hãy nhớ rằng tiếng Nhật lời giải là một quá trình sáng tạo.

*) Xem thêm bài viết của S. V. Romanov và I. F. Shara G. Trong “Phương pháp đại số của lời giải hình học bài toán”, «Kvant», 1975, Số 11.

Hãy bắt đầu với hai bài toán này.

Bài toán 1 (MAI, 1973). Trong một tam giác vuông, một trong các góc nhọn bằng α. Trên các đoạn zion được hình thành bởi đáy có chiều cao được hạ xuống trên nó, cũng như trên các đường kính, các hình bán nguyệt được tạo ra, nằm cùng phía với tam giác đã cho. Tên độ dài của các đoạn kamet được bao bọc bên trong các hình bán nguyệt này.

Đầu tiên là lời giải. Cho $CAB$ là một tam giác cho trước (góc $A$ là góc vuông), $AD$ chiều cao của nó, các điểm $E$ và $F$ các điểm giao nhau của hình bán nguyệt với hai chân $AC$ và $AB$ (xem Hình 1). Rõ ràng là $(DE) \perp (AC)$ và $(DF) \perp (AB)$. Pozotomu

$$\begin{cases} |DF|^2 = |AF| \cdot |FB|, \\ |DE|^2 = |AE| \cdot |EC|. \end{cases}$$

Hãy giới thiệu những ẩn số: $x = |DF| = |AE|$ và $y = |AF| = |DE|$.

Sau đó, ký hiệu $|AC| = b$ và $|AB| = c$, ta thu được hệ:

$$\begin{cases} x^2 = y(c - y), \\ y^2 = x(b - x), \end{cases}$$

Ở đâu

$$x = \frac{bc^2}{b^2 + c^2}, \quad y = \frac{b^2c}{b^2 + c^2}.$$

Nhưng

$$|FB| = c - y = \frac{c^3}{b^2 + c^2}, \quad |EC| = b - x = \frac{b^3}{b^2 + c^2}.$$

⟦folio 47⟧

Kể từ đây,

$$\frac{|FB|}{|EC|} = \frac{c^3}{b^3}.$$

Nhưng $\frac{c}{b} = \text{tg}\alpha$ có nghĩa là $\frac{|FB|}{|EC|} = \text{tg}^3\alpha$.

Thứ hai lời giải. Lưu ý rằng

$$\widehat{DCE} = \widehat{DAF} = \widehat{BDF} = x.$$

Bởi vì

$$\frac{|FB|}{|EC|} = \frac{|DF| \cdot \text{tg}\alpha}{|EC|} = \frac{(|AF| \cdot \text{tg}\alpha) \cdot \text{tg}\alpha}{|EC|} = \frac{|DE| \cdot \text{tg}^2\alpha}{|EC|} = \text{tg}^3\alpha.$$

Chúng ta thấy rằng để thu được đáp số thì không cần phải đưa vào bất kỳ ẩn số nào hoặc soạn hệ đại số - chỉ cần lưu ý rằng ba góc được liệt kê là bằng nhau là đủ.

Bài toán 2. Cho tam giác ABC. Vẽ một đường tròn tiếp xúc với cạnh BC tại đáy đường cao AD có độ dài h và đi qua trung điểm của cạnh AC có độ dài b. Tên là đường kính của vòng tròn này.

Đầu tiên là lời giải. Hình 2 thể hiện một trong các cách sắp xếp: đường kính DF của đường tròn nhỏ hơn chiều cao, đường tròn này cắt cạnh AC tại hai điểm K và E, trong đó điểm E ở trên là chính giữa và không cắt cạnh thứ hai của tam giác.

Chúng ta hãy biểu thị đường kính của vòng tròn loại trừ bằng x: $|DF| = x$ và độ dài của dây cung $KE$ bằng y: $|KE| = y$.

Cơm. 2.

Áp dụng các định lý cho tiếp tuyến và cát tuyến, cũng như trên hai cát tuyến vẽ đường tròn đi từ một điểm (C và A, tương ứng), chúng ta thu được

$$|CD|^2 = |CK| \cdot |CE|,$$

$$|AF| \cdot |AD| = |AE| \cdot |AK|.$$

Từ đây chúng ta có

$$\begin{cases}
b^2 - h^2 = \frac{b}{2} \left( \frac{b}{2} - y \right), \\
h(h - x) = \frac{b}{2} \left( \frac{b}{2} + y \right).
\end{cases}$$

Giải hệ này để tìm x, ta tìm được $|DF| = x = \frac{b^2}{2h}$.

Tuy nhiên, lời giải này không thể được coi là đầy đủ - xét cho cùng, các khả năng khác vẫn chưa được xem xét (ví dụ: khi $|DF| > |AD|$ và điểm giao nhau thứ hai nằm trên phần tiếp theo của cạnh AC). Việc phân tích từng trường hợp này dẫn đến các hệ thống khác nhau và hơn nữa, đòi hỏi phải sử dụng các định lý khác nhau (trong trường hợp $|DF| > |AD|$ sẽ cần đến định lý về hai dây cung giao nhau).

Bây giờ chúng ta sẽ đưa ra một lời giải hình học khác của bài toán này; Hãy tự mình nhận ra rằng nó không còn phụ thuộc vào cách đường tròn cắt các cạnh của một tam giác đã cho nữa.

Thứ hai lời giải. Hãy nối điểm E với các điểm D và F. Vì DE là đường trung tuyến của cạnh huyền của tam giác vuông CAD nên chúng ta có: $|DE| = |AE| = \frac{b}{2}$ và $\widehat{EDF} = \widehat{EAD}$ (các góc ở đáy của một tam giác đều). Do đó, các tam giác vuông DEF và ADC đồng dạng. Từ đây

$$\frac{|DF|}{|AC|} = \frac{|DE|}{|AD|},$$

hoặc

$$|DF| = \frac{|AC| \cdot |DE|}{|AD|},$$

đó là

$$|DF| = \frac{b^2}{2h}.$$

⟦folio 48⟧

Cơm. 3.

Thông thường, phương pháp đại số lời giải hình học bài toán dẫn đến các phương trình vô tỉ phức tạp. Đôi khi, nhờ có thêm tin nhắn, điều này có thể tránh được. Đây là hai bài toán điển hình.

Bài toán 3 (LSU, 1973). Xác định chiều cao của hình thang nếu độ dài hai đáy của nó là 6 và 11, độ dài một cạnh là 4 và tổng các góc ở đáy là $\frac{\pi}{2}$.

Đầu tiên là lời giải. Chúng ta hãy vẽ các đường cao $BE$ và $CF$ trong hình thang $ABCD$ (Hình 3) và đặt $|BE| = |CF| = x$. Chúng tôi sẽ giả định rằng $|AB| = 4$. Từ tam giác vuông $AEB$ ta tìm được $|AE| = \sqrt{16-x^2}$. Đó là lý do tại sao

$$|FD| = |AD| - (|AE| + |EF|) = (|AD| - |BC|) - |AE| = 5 - \sqrt{16-x^2}.$$

Vì tổng các góc ở đáy $AD$ là $\frac{\pi}{2}$ nên các tam giác vuông $AEB$ và $CF$ là tương tự nhau; kể từ đây,

$$\frac{|BE|}{|FD|} = \frac{|AE|}{|CF|}.$$

Chúng ta thu được phương trình vô tỉ

$$\frac{x}{5 - \sqrt{16-x^2}} = \frac{\sqrt{16-x^2}}{x},$$

từ đó ta tìm được chiều cao của hình thang:

$$x = |BE| = 2,4.$$

Thứ hai lời giải. Hãy tạo một cấu trúc bổ sung: vẽ $(BK)$ song song với $(CD)$. Chúng ta thu được (xem Hình 3 và điều kiện bài toán) một tam giác vuông $ABK$, từ đó có thể dễ dàng tìm được chiều cao của hình thang:

$$|BE| = \frac{|AB| \cdot |BK|}{|AK|} = \frac{|AB| \cdot \sqrt{|AK|^2 - |AB|^2}}{|AK|} = \frac{|AB| \cdot \sqrt{(|AD| - |BC|)^2 - |AB|^2}}{|AD| - |BC|} = \frac{4 \cdot \sqrt{(11-6)^2 - 16}}{11-6} = 2,4.$$

Bài toán 4. Trên các cạnh $AD$ và $CD$ của hình vuông $ABCD$, từ cạnh 3 lấy hai điểm $M$ và $N$ sao cho độ dài của đoạn thẳng gãy $MDN$ bằng hình vuông. Các đường $AM$ và $BN$ cắt nhau tại điểm $E$. Tìm độ dài của đoạn $ME$ nếu $|NE| = 4$.

Đầu tiên là lời giải. Chúng ta hãy biểu thị độ dài của đoạn $DN$ (Hình 4) bằng $x$. Sau đó $|DE| = \sqrt{16-x^2}$. Từ sự giống nhau của các tam giác $NDE$ và $BAE$ ta có

$$\frac{|DN|}{|AB|} = \frac{|DE|}{|AE|},$$

đó là

$$\frac{x}{3} = \frac{\sqrt{16-x^2}}{3 + \sqrt{16-x^2}}.$$

Phương trình vô tỷ này liên quan đến các phương trình bậc bốn sau đây

$$x^4 - 6x^3 + 2x^2 + 96x - 144 = 0.$$

⟦folio 49⟧

Cơm. 5.

Đa thức thu được ở vế trái được phân tích thành tích của hai tam giác vuông: $x^2 + 2x - 6$ và $x^2 - 8x + 24$. Vì vậy $(x^2 + 2x - 6)(x^2 - 8x + 24) = 0$.

Phương trình này có một nghiệm dương duy nhất:

$$x = |DN| = \sqrt{7} - 1.$$

Bây giờ chúng ta có thể dễ dàng tìm thấy

$$|ME| = |MD| + |DE| = 3 - |DN| + \sqrt{16 - |DN|^2} = 3 - \sqrt{7} + 1 + \sqrt{16 - (\sqrt{7} - 1)^2} = 4 - \sqrt{7} + \sqrt{(V\overline{7} + 1)^2} = 5.$$

đáp số đơn giản gợi ý rằng có một lời giải khác ít phức tạp hơn. Đây rồi.

Thứ hai lời giải. Vì tam giác BCN và NDE đồng dạng nên

$$\frac{|BC|}{|CN|} = \frac{|DE|}{|DN|},$$

hoặc

$$\frac{3}{3 - |DN|} = \frac{|DE|}{|DN|},$$

đó là

$$3(|DE| - |DN|) - |DN| \cdot |DE| = 0.$$

Có tính đến $|MD| = 3 - |DN|$ và $|DN|^2 + |DE|^2 = 16$, chúng tôi thu được

$$|ME| = |MD| + |DE| = (3 - |DN|) + |DE| = \sqrt{(3 - |DN| + |DE|)^2} = \sqrt{9 + 16 + 2 \cdot 0} = 5.$$

Với một chút khéo léo, chúng tôi đã có thể giải được phương trình vô tỷ mà theo chúng tôi, phương trình này không quá phổ biến để giải!

Một trong những phương pháp lời giải phẳng bài toán phổ biến nhất trong số những người nộp đơn là việc sử dụng lượng giác. Tất nhiên, đây là một phương pháp rất quan trọng và hữu ích - đôi khi việc giới thiệu các hàm lượng giác là một con đường tự nhiên và hợp lý dẫn đến lời giải. Tuy nhiên, trong từng trường hợp cụ thể, bạn nên suy nghĩ xem liệu có một lời giải hình học đơn giản hơn hay không. Đây là một trường hợp điển hình.

Bài toán 5 (MSU, Khoa Toán tính toán và Mạng điều khiển học, 1971). Cho tam giác ABC, cạnh AC lớn hơn cạnh AB và góc tại đỉnh A bằng α. Lấy điểm R trên cạnh AC nên $|AB| = |RC|$. Gọi E là trung điểm của đoạn AR, D là trung điểm của cạnh BC. Tìm góc CED.

Cái đầu tiên là lời giải (lượng giác). Chúng ta hãy biểu thị độ dài các cạnh của tam giác ABC bằng các chữ cái a, b, c, giá trị các góc của nó lần lượt bằng các chữ cái A, B, C và giá trị của góc mong muốn CED bằng chữ x.

Sau đó (xem hình 5):

$$\widehat{CDE} = 180^\circ - (C + x),$$

$$|CD| = \frac{a}{2},$$

$$|CE| = |CR| + |RE| = c + \frac{b - c}{2} = \frac{b + c}{2}.$$

Áp dụng định lý sin để tìm tam giác CDE:

$$\frac{|CE|}{\sin CDE} = \frac{|CD|}{\sin CED},$$

đó là

$$\frac{b + c}{\sin (C + x)} = \frac{a}{\sin x};$$

từ tam giác ABC:

$$\frac{a}{\sin A} = \frac{b}{\sin B} = \frac{c}{\sin C},$$

⟦folio 50⟧

đó là
$$\frac{b+c}{\sin B+\sin C} = \frac{a}{\sin A}.$$

Chia tương ứng (1) cho tương ứng (2), ta được
$$\frac{\sin B + \sin C}{\sin(C+x)} = \frac{\sin A}{\sin x},$$
hoặc, vì $B = 180^\circ - (A+C)$,
$$\frac{\sin(A+C) + \sin C}{\sin A} = \frac{\sin(C+x)}{\sin x},$$

đó là
$$\frac{2\sin\left(\frac{A}{2} + C\right)\cos\frac{A}{2}}{2\sin\frac{A}{2}\cos\frac{A}{2}} = \frac{\sin(C+x)}{\sin x},$$
Ở đâu
$$x = \frac{A}{2} = \frac{\alpha}{2}.$$

Thứ hai là lời giải (hình học). Bây giờ chúng tôi thậm chí sẽ trình bày hai hình học lời giải.

1°. Chúng ta hãy vẽ đường giữa $DF$ trong tam giác $ABC$. chúng tôi có
$$|FE| = |CE| - |CF| = \frac{b+c}{2} - \frac{b}{2} = \frac{c}{2} = |DF|,$$
tức là tam giác $DFE$ là tam giác cân. Pozny
$$\widehat{CED} = \frac{1}{2}\widehat{CFD} = \frac{1}{2}\widehat{CAB} = \frac{\alpha}{2}.$$

2°. Chúng ta hãy thực hiện bissertis $AK$ của góc $A$ của tam giác $ABC$. Sau đó
$$\frac{|CK|}{|CA|} = \frac{a}{b+c}.$$
mà còn $\frac{|CD|}{|CE|} = \frac{a}{b+c}$, có nghĩa là các tam giác $CDE$ và $CKA$ tương tự nhau và đoạn $DE$ song song với $AK$.
Vì vậy, $\widehat{CED} = \widehat{CAK} = \frac{\alpha}{2}$.

Đúng không, phép đo lượng giác lời giải của bài toán này không thể gọi là thành công được sao? - cả hai hình học lời giải đều thanh lịch hơn. Nhưng ở một khía cạnh nào đó, chúng khó khăn hơn - xét cho cùng, cần phải thực hiện các hợp đồng bổ sung

Bài tập
1 (LSU, 1973). Trong hình chữ nhật $ABCD$ ta có: $|AB| = a$, $|AD| = b$ ($a > b$). Tìm ở bên $AB$ điểm $E$ sao cho $\angle CED \cong \angle AED$.
2 (NSU, 1967). Trong một tứ giác lồi phẳng $ABCD$, các điểm $E, F, K, L$ là trung điểm của cạnh $AB, BC, CD, DA$. Các đoạn $EK$ và $FL$ chia tứ giác này thành bốn tứ giác nhỏ hơn. Chứng minh rằng tổng diện tích các tứ giác có đỉnh tại các điểm $A$ và $C$ bằng tổng diện tích của hai tứ giác còn lại.
3 (NSU, 1974). Trong hình thang $ABCD$, cạnh $CD$ vuông góc với đáy $AD$, $|BC| = a$, $|AD| = b$, $a < b$. Dựa vào $AD$, tồn tại một điểm $M$ sao cho ($MB$) vuông góc với ($AC$) và ($MC$) vuông góc với ($BD$). Tìm chiều cao của hình thang.
4 (MIPT, 1970). Cho một hình thang $ABCD$ có các đáy $|AB| = a$, $|CD| = b$ ($a < b$). Đường tròn đi qua đỉnh $A, B$ và $C$ chạm vào [AD]. Tìm độ dài đường chéo $AC$.
5 (MIPT, 1973). Hai đường tròn bán kính $R$ và $r$ ($R > r$) có tiếp tuyến ngoài tại điểm $A$. Qua điểm $B$ lấy trên đường tròn lớn vẽ một đường thẳng tiếp xúc với đường tròn nhỏ tại điểm $C$. Tìm độ dài của đoạn $BC$ nếu độ dài của dây cung $AB$ bằng $a$.
6 (MIPT, 1973). Trong một hình thang bằng nhau $ABCD$ góc ở đáy $AD$ bằng $\frac{24}{25}$. Một đường tròn có bán kính $R$ chạm vào đáy $AD$, cạnh $AB$ và đi qua đỉnh $C$; nó cắt các đoạn tương ứng $MC$ và $NC$ ở cạnh $BC$ và $CD$. Tìm độ dài của đoạn $BM$.
7 (MSU, Binofak, 1973). Trong một đường tròn có hai đường kính $AB$ và $CD$, $M$ là một điểm nhất định. Được biết, $|AM| = 15$, $|BM| = 20$ và $|CM| = 24$. $|DM|$ bằng bao nhiêu?
8 (MSU, Khoa Địa chất, 1974). Cho một tam giác vuông $ABC$ có một góc vuông ở đỉnh $C$. Góc $CAB$ bằng $\alpha$. Các bissertis của góc $ABC$ cắt chân $AC$ tại điểm $K$. Trên cạnh $BC$, là đường kính, một đường tròn được dựng để cắt cạnh huyền $AB$ tại điểm $M$. Tìm góc $AMK$.
