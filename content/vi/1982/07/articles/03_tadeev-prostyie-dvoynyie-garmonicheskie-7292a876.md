---
id: 1982-7-tadeev-prostyie-dvoynyie-garmonicheskie-7292a876
issue: kvant_1982_7
year: 1982
number: "7"
title: Đơn giản, đôi, hài hòa
authors:
  - Тадеев В. А.
rubric: osnovnye-stati
page_first: 4
page_last: 11
page_labels: 2, 3, 4, 5, 7, 8, 9
tag: PIFQ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: a94d134845e5648e73aa100411b164a1eb1b535940ee42571f22a86aaa3328c6
prompt_sha256: draft-1
translated_from: content/ru/1982/07/articles/03_tadeev-prostyie-dvoynyie-garmonicheskie-7292a876.md
source_content_sha256: ca21bd26bcad3f46a07b9252a88a9c1de54b7cdf0224db5c0895bc336f460005
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

V. Tadeev

Đơn giản, đôi, hài hòa

Bây giờ không ai biết chính xác làm thế nào vào năm 1640, Blaise Pascal, mười bảy tuổi (về cuộc đời ông, xem tập sách “Những câu chuyện về các nhà vật lý và toán học” của S. G. Gindikin (M., “Nauka”, 1981)) đã nghĩ ra định lý mang tên ông. Có lẽ, vì lý do nào đó, khi tiếp tục các cạnh của hình lục giác nội tiếp trong đường tròn, anh ta chỉ đơn giản nhận thấy các giao điểm M, N và K nằm trên cùng một đường thẳng (xem trình bảo vệ màn hình). Có nghe được không? Chàng trai lấy một hình lục giác khác nhưng các điểm M, N và K ngoan cố nằm trên một đường thẳng.

Chúng ta không biết những cảm xúc nào nảy sinh trong tâm hồn anh ấy. Người ta chỉ biết rằng anh ta đã nhanh chóng tiếp tục chứng minh sự thật đỏ mà anh ta đã phát hiện và ngay lập tức khái quát hóa nó. Và rồi... rồi từ định lý, như từ một loại sự phong phú, một hệ quả tất yếu đã được đưa ra. Sau đó, định lý Pascal hóa ra là một trong những quy định quan trọng nhất của một nhánh toán học mới - hình học xạ ảnh, đã tìm ra những ứng dụng thú vị trong trắc địa và bản đồ.

Trong bài viết này, chúng ta sẽ chứng minh định lý Pascal về đường tròn và thảo luận về một số "khái niệm thiết kế" cho phép chúng ta khái quát hóa nó.

Những mối quan hệ đơn giản

Cho các điểm A, B và C trên dòng l (Hình 1). Đối với các vectơ thẳng hàng $\vec{AC}$ và $\vec{CB}$ tồn tại một số (số ít) $\lambda$ sao cho $\vec{AC} = \lambda \cdot \vec{CB}$. Số $\lambda$ này được gọi là tỉ số đơn giản của các điểm A, B, C; nó được ký hiệu là (ABC). Khi điểm B và C trùng nhau thì quan hệ đơn giản (ABC) không được xác định. Từ định nghĩa rõ ràng rằng

$$|(ABC)| = \frac{|\vec{AC}|}{|\vec{CB}|}.$$

Chính xác hơn, $(ABC) = \frac{|\vec{AC}|}{|\vec{CB}|}$, nếu điểm C

⟦folio 3⟧

nằm giữa $A$ và $B$ và $(ABC) = -\frac{|\overrightarrow{AC}|}{|\overrightarrow{CB}|}$ nếu không.

Bây giờ chúng ta sửa các điểm $A$ và $B$ trên $l$ và kiểm tra xem mối quan hệ đơn giản $(ABC)$ thay đổi như thế nào tùy thuộc vào vị trí của điểm $C$. Để làm điều này, chúng ta đặt gốc tọa độ tại điểm $B$ và hướng trục hoành dọc theo $l$ từ $A$ đến $B$ (Hình 2). Nếu chúng ta biểu thị hoành độ của điểm $C$ bằng $x$ và đặt $|AB| = a$, thì $|\overrightarrow{AC}| = a + x$ và $|\overrightarrow{CB}| = x$. Thật dễ dàng để nhận thấy điều đó $(ABC) = v(x) = -\frac{a+x}{x}$. (1)

Từ đồ thị của hàm $v$ (Hình 2), rõ ràng vị trí của điểm $C$ trên đường thẳng $AB$ được xác định duy nhất bởi số $(ABC)$.

Chúng ta hãy lấy các đường $l$, $l'$ trên mặt phẳng và một điểm $P$ bên ngoài chúng. Đối với một điểm tùy ý $A$ của đường thẳng $l$ ta gán điểm $A' = (PA) \cap l'$ cho đường thẳng $l'$. Việc ánh xạ đường $l$ vào đường $l'$ này, đương nhiên được gọi là phép chiếu trung tâm (chủ yếu là $l$ vào đường $l'$), sẽ đóng một vai trò quan trọng trong tương lai.

Thật không may, nếu $l \parallel l'$, mối quan hệ điểm đơn giản trong quá trình chiếu tâm không được giữ nguyên (Hình 3). Tuy nhiên, một mối quan hệ khác có thể dễ dàng được xây dựng từ nó, mối quan hệ này đã có sẵn thuộc tính mà chúng ta cần.

Mối quan hệ kép

Cho các điểm $A, B, C$ và $D$ nằm trên đường thẳng $l$ (Hình 4). Số $\frac{(ABC)}{(ABD)}$ được gọi là tỷ lệ kép (hoặc phức hoặc không điều hòa) của điểm $A, B, C, D$; nó được ký hiệu là $(ABCD)$. Như vậy,

$$|(ABCD)| = \frac{|\overrightarrow{AC}|}{|\overrightarrow{CB}|} : \frac{|\overrightarrow{AD}|}{|\overrightarrow{DB}|}.$$

Khi điểm $A$ và $D$ trùng nhau, $(ABD) = 0$ (xem (1)); trong trường hợp này mối quan hệ kép $(ABCD)$ không được xác định. Tất nhiên, nó cũng không được xác định cho $B = C$. Đối với $B = D$, việc đặt $(ABCD) = 0$ là điều đương nhiên.

Bây giờ chúng tôi sửa các điểm $A, B$ và $C$ trên $l$. Đặt gốc tọa độ tại điểm $B$ và hướng trục x

⟦folio 4⟧

Hình 5.

6) $(BACD) = (ABDC) = (CDBA) = (DCAB) = \frac{1}{\omega}$;
7) $(BDAC) = (DBCA) = (ACBD) = (CADB) = 1 - \omega$;
8) $(DACB) = (ADBC) = (CBDA) = (BCAD) = 1 - \frac{1}{\omega}$;
9) $(DBAC) = (BDCA) = (ACDB) = (CABD) = \frac{1}{1 - \omega}$;
10) $(ADCB) = (DABC) = (CBAD) = (BCDA) = \frac{1}{1 - \frac{1}{\omega}}$.

Hãy để chúng tôi chứng minh rằng mối quan hệ kép được bảo toàn theo thiết kế trung tâm (Hình 5). Chúng ta hãy biểu thị tương ứng bằng $h$ và $h'$ khoảng cách từ $P$ đến các đường $l$ và $l'$. Ví dụ, xét diện tích của hình tam giác $PAC$ và $PA'C'$, chúng ta thu được

$$\frac{h \cdot |AC|}{h' \cdot |A'C'|} = \frac{|PA| \cdot |PC|}{|PA'| \cdot |PC'|}.$$

Từ đây

$$|A'C'| = |AC| \cdot \frac{|PA'| \cdot |PC'|}{|PA| \cdot |PC|} \cdot \frac{h}{h'}$$

Từ các đẳng thức tương tự cho $|C'B'|$, $|A'D'|$ và $|D'B'|$ ta thu được

$$\frac{|A'C'|}{|C'B'|} : \frac{|A'D'|}{|D'B'|} = \frac{|AC|}{|CB|} : \frac{|AD|}{|DB|}$$

Vì các điểm $A, B, C, D$ trên $l$ và $A', B', C', D'$ trên $l'$ có cùng thứ tự nên các quan hệ nguyên tố $(ABC)$ và $(A'B'C')$, $(ABD)$ và $(A'B'D')$ có cùng dấu. Vì vậy, $(A'B'C'D') = (ABCD)$.

Hình 6.

Bộ ba Pascal

Bây giờ chúng ta có thể gặt hái thành quả lao động của mình.

Xây dựng (chỉ cẩn thận) hình lục giác $ABCDEF$ nội tiếp trong đường tròn và phần mở rộng của cặp cạnh $FE$ và $BC$, ED và $AB$, DC và $FA$ đến giao điểm tại các điểm $M, N, K$ tương ứng*). Nếu bạn thực hiện các cách xây dựng này đủ chính xác, bạn sẽ thấy các điểm $M, N, K$ nằm trên cùng một đường thẳng (Hình 6). Bộ ba điểm này được gọi là bộ ba Pascal, và phát biểu về sự thẳng hàng của chúng được gọi là định lý Pascalai.

Nhân tiện, bạn bao nhiêu tuổi? Mười bảy? Nếu bạn để ý thì hãy đọc những phần trước

*) Trường hợp có ít nhất một cặp đường thẳng không giao nhau sẽ được thảo luận dưới đây.

⟦folio 5⟧

trang này, bạn thấy mình ngang hàng với Pascal, người vừa đưa ra quan sát của mình. Bạn có muốn xem bạn mất bao lâu để tự mình tìm ra cách chứng minh định lý Pascal không?

Hãy chứng minh định lý này. Hãy xem xét hai bộ tứ đường thẳng: FE, FD, FC, FA và BE, BD, BH, BN. Chúng bằng nhau vì các góc giữa các đường thẳng tương ứng bằng nhau (ví dụ: EFD = EBD, hoặc chúng dựa trên cung chung DE). Điều này có nghĩa là, theo những gì đã được chứng minh ở phần trước, (RDCK) = (EDHN) (ở đây R = (FE) ∩ (CD), H = (BC) ∩ (ED)).

Gọi giao điểm của hai đường MK và EH là N'. Khi đó (EDHN') = (RDCK). Do đó (EDHN) = (EDHN'), do đó N' trùng với N.

Bài tập

2. Bằng cách chọn mọi cách có thể các cặp đường thẳng nối các đỉnh của hình lục giác ABCDEF nội tiếp trong một đường tròn, đảm bảo rằng có 60 đường thẳng song song.

3*. Khám phá vị trí tương đối của 60 cặp mà các dấu vết này nằm trên đó.

4. Xây dựng và chứng minh định lý Pascal về ngũ giác nội tiếp đường tròn (Gợi ý. Giải nén nó thành một lục giác có các đỉnh E và F trùng nhau và tiếp tuyến tại điểm E là vị trí giới hạn của cát tuyến EF), một tứ giác và một tam giác.

5. Vẽ tiếp tuyến của một đường tròn từ một điểm cho trước bằng một thước kẻ.

* * *

Để có được hệ quả từ định lý Pascal đã được thảo luận ở đầu bài viết, trước tiên bạn sẽ phải bỏ ra một ít thời gian. Chúng ta sẽ nghiên cứu hai loại phép biến đổi mặt phẳng quan trọng - phép chiếu song song và phép chiếu tâm. Những biến đổi này là cơ sở của thiết kế.

Bạn biết rằng chuyển động của mặt phẳng khiến khoảng cách giữa các điểm không thay đổi; do đó, chúng giữ được kích thước và hình dạng của các hình. Với những điểm tương đồng, chỉ có mối quan hệ khoảng cách được giữ nguyên - các hình có thể thay đổi kích thước nhưng vẫn giữ nguyên hình dạng. Tình hình còn tồi tệ hơn với thiết kế song song và trung tâm - chúng cũng làm biến dạng hình dạng của các hình. Ví dụ, trong thiết kế song song

⟦folio 7⟧

lười biếng Sự xuất hiện của bóng từ một vật phẳng trên màn hình mô hình hóa hình chiếu trung tâm (Hình 12).

Định nghĩa toán học ở đây như sau: các mặt phẳng π và π' (song song hoặc cắt nhau) và điểm P bên ngoài các mặt phẳng này trống; Với mỗi điểm A ∈ π chúng ta liên kết một điểm A' ∈ π' giao điểm của đường thẳng PA với mặt phẳng π' (Hình 13); ánh xạ kết quả của mặt phẳng π vào mặt phẳng π' được gọi là phép chiếu tâm (của mặt phẳng π vào mặt phẳng π' tính từ tâm P).

Thật không may, nếu các mặt phẳng π và π' không song song, thì phép chiếu tâm không phải là ánh xạ vào mặt phẳng π cũng như không ánh xạ lên toàn bộ mặt phẳng π'. Trên thực tế, nếu một mặt phẳng π₁ song song với π' được vẽ qua P, thì điểm của đường thẳng l = π₁ ∩ π không được ánh xạ theo bất kỳ cách nào khi chiếu tâm từ P (Hình 14, a). Tương tự, nếu một mặt phẳng π₂ song song với π được vẽ qua P, thì trong phép chiếu tâm từ P, không có điểm nào của mặt phẳng π đi đến các điểm của đường thẳng l' = π₂ ∩ π' (Hình 14, a).

Chúng ta hãy xem những gì được thực hiện trong quá trình chiếu tâm với các đường thẳng của mặt phẳng π. Như đã nói, đường thẳng l (và bất kỳ điểm nào của nó) không biến thành bất cứ thứ gì. Bất kỳ đường thẳng nào của mặt phẳng π song song với l sẽ thành đường thẳng của mặt phẳng π', song song với l' (Hình 14, b). Đưa mặt phẳng π cắt l không có giao điểm - “đường thẳng xuyên qua” của mặt phẳng π' - thành đường thẳng không có giao điểm với l' (Hình 14, c). (Trong tương lai, để không làm lộn xộn cách diễn đạt bằng các từ ngữ, trong những tình huống như vậy, chúng tôi sẽ cho phép lời nói dao động và nói ngắn gọn rằng một đường thẳng sẽ biến thành một đường thẳng.)

Chúng ta hãy lưu ý thêm rằng các đường giao nhau, nếu giao điểm của chúng không nằm trên đường l đã chọn, sẽ chuyển thành các đường giao nhau (Hình 14, f), nếu không thì chúng biến thành các đường thẳng song song (Hình 14, e).

⟦folio 8⟧

Như vậy, có thể nói rằng với thiết kế trung tâm, về cơ bản các đường thẳng sẽ biến thành đường thẳng và các đường giao nhau thành giao nhau. Từ “đáng kể” có nghĩa là “ngoại trừ các trường hợp ngoại lệ và tiêu chuẩn nêu trên”.

Có thể tránh các mệnh đề ngoại lệ trong báo cáo thiết kế bằng cách giả sử rằng “các đường song song cắt nhau tại một điểm ở vô cực” và “tất cả các điểm ở vô cực trong một mặt phẳng nhất định đều nằm trên cùng một đường thẳng (vô cực). Hơn nữa, từ ngữ với tư cách là chất lượng có thể được gán một ý nghĩa toán học chính xác; sau đó, bằng cách thêm “các điểm ở xa vô hạn” của nó vào mặt phẳng cạnh (Euclide) của chúng ta, chúng ta thu được cái gọi là “mặt phẳng xạ ảnh”.

Trên mặt phẳng xạ ảnh, định lý Pascal được giữ vững mà không cần đặt trước: ngay cả trong trường hợp hình lục giác đều, các đường thẳng đối diện (song song) “giao nhau tại ba điểm ở vô cực, tất cả đều nằm trên cùng một đường thẳng (vô cùng xa!)”.

Tuy nhiên, ở đây chúng ta sẽ không đề cập đến đối tượng toán học của các quốc gia này. «Kvant» sẽ sớm quay lại chủ đề này.

phần ốc xà cừ

Bây giờ chúng ta hãy sử dụng ví dụ về đường tròn để xem hình chiếu trung tâm làm biến dạng hình dạng của các hình ở mức độ nào. Chúng ta hãy xem xét một đường tròn S nằm trên mặt phẳng π và một điểm P phía trên mặt phẳng này (Hình 15). Vòng tròn S sẽ trở thành gì?

Hình 15.

Tất nhiên, khi chiếu tâm từ điểm P, điều đó phụ thuộc vào vị trí của mặt phẳng π′ mà chúng ta đang chiếu lên đó. Hình vẽ thể hiện bốn tin đồn (các mặt phẳng π′1, π′2, π′3, π′4); điều này tạo ra một sự tương ứng, một hình elip, một parabol, một hyperbol và một cặp đường thẳng giao nhau. Hình vẽ cho thấy rõ rằng tổng số các đường thẳng chiếu tạo thành một hình nón; Vì vậy, các đường cong được liệt kê được gọi là mặt cắt hình nón.

Nếu hình chiếu trung tâm làm biến dạng hình dạng của các hình nhiều đến vậy thì nó còn bảo toàn được gì? Chúng ta biết rằng nó biến đổi các đường thẳng thành đường thẳng, nghĩa là nó bảo toàn tính chất thẳng hàng của các điểm (ở đây chúng ta chỉ cần nhớ những điều đã đặt trước ở trên!). Ngoài ra, nó còn bảo toàn tỷ lệ kép của bốn điểm, điều mà chúng tôi đã chứng minh trước đó. Hóa ra hai sự kiện này đủ để thu được nhiều định lý hình học sâu sắc, đặc biệt là hệ quả tất yếu của định lý Pascal.

Bài tập

8. Xây dựng và chứng minh định lý Pascal cho hình lục giác nội tiếp trong một hình elip, một parabol và một hyperbol.

9. Chứng minh rằng một hình elip, một parabol và một hyperbol được xác định duy nhất bởi số năm.

10. Chỉ ra phương pháp dựng một thước dọc theo các điểm gót của hình elip của các điểm khác của nó.

11. Sử dụng một thước kẻ, dựng một tiếp tuyến của hình elip đã cho từ một điểm cho trước. Điều tương tự cũng xảy ra với parabol và hyperbol.

Hài hòa bốn

Ngay cả các nhà toán học Hy Lạp cổ đại cũng gọi bốn điểm thẳng hàng A, B C, D là hài hòa nếu (ABCD) = -1.

Hãy đưa ra một ví dụ. Chúng ta hãy lấy một tam giác NAB tùy ý và vẽ bissertis NC của góc “nội” ANB và bissertis ND của góc “ngoài” KNB (Hình 16). Như đã biết ("Hình học 6-8", bài toán 914), $\frac{|AC|}{|CB|} = \frac{|NA|}{|NB|}$. Tuyên bố này cũng có thể được viết như thế này:

$$ABC = \frac{|NA|}{|NB|}.$$

⟦folio 9⟧

Giả sử $A$ là một điểm trên trục quang, $A'$ ảnh của nó, $F$ tiêu điểm của gương, $a$ tâm của nó ($|PF| = |FO|$). Khi đó bốn điểm $P, O, A', A$ là điều hòa. Hãy tự chứng minh, sử dụng công thức

$$\frac{1}{d} + \frac{1}{f} = \frac{1}{F},$$

được biết đến từ một khóa học vật lý.

Các nhà khoa học Hy Lạp cổ đại, ngoài số học ($a - b = c - d$) và hình học ($\frac{a}{b} = \frac{c}{d}$), còn coi tỷ lệ hài hòa:

$$\frac{1}{a} - \frac{1}{b} = \frac{1}{c} - \frac{1}{d}$$ (sự đẳng thức này được thỏa mãn bởi tọa độ $a, b, c, d$ của bộ tứ điểm hài hòa $A, B, C, D$). Trong trường hợp $b = c$ (trong trường hợp này các tỷ lệ được gọi là liên tục), thu được trung bình số học $b = \frac{a+d}{2}$, trung bình hình học $b = \sqrt{ad}$ và trung bình điều hòa $b = \frac{2ad}{a+d}$.

Theo truyền thuyết, ngay cả Pythagoras, khi nghiên cứu lý thuyết toán học về âm nhạc, đã xác định rằng độ dài của dây phát ra âm thanh ở cùng độ căng của nốt $do, mi, colb$ (các thành phần của một nốt ba nốt trưởng) tỷ lệ thuận với số 1, $\frac{4}{5}, \frac{2}{3}$. Nhưng $\frac{4}{5}$ là trung bình điều hòa của số 1 và $\frac{2}{3}$. Đây là nơi khái niệm về sự hài hòa xuất hiện trong toán học.

Cũng dễ dàng chứng minh được điều đó

$$(ABD) = -\frac{|NA|}{|NB|}.$$

(Gợi ý. Hãy xem xét tỷ lệ diện tích của các hình tam giác $NAD$ và $NBD$, lấy cơ sở trước tiên là $[NA]$ và $[NB]$, sau đó là $[AD]$ và $[BD]$.) Do đó, $(ABCD) = -1$, tức là nhân bốn điểm $A, B, C, D$.

Bài tập 12. Nêu phương pháp dựng điểm bằng thước. Gợi ý. Xem hình. 17. Điểm $P$ và $Q$ ở giai đoạn 1 và 5 được chọn ngẫu nhiên.

Bộ tứ hài hòa được tìm thấy trong quang học. Chúng ta hãy xem xét đường đi của tia sáng trong gương lượn sóng 3 (Hình 18).
