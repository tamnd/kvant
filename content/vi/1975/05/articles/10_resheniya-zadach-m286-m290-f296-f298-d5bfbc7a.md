---
id: 1975-5-resheniya-zadach-m286-m290-f296-f298-d5bfbc7a
issue: kvant_1975_5
year: 1975
number: "5"
title: Lời giải bài toán M286—M290; F296—F298
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 54
page_last: 58
page_labels: 52-56
tag: XTGK
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 23f9e61e7bcee702e169928132d3b3d5888e0749217b73b3092518d420b2d96b
prompt_sha256: draft-1
translated_from: content/ru/1975/05/articles/10_resheniya-zadach-m286-m290-f296-f298-d5bfbc7a.md
source_content_sha256: 7ce9720b6e36f153a1fc551ba6c5312b14315b73503f6c92e22c3d115ce6e038
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 52⟧

Lời giải bài toán

M286. Có N điểm trên mặt phẳng. Hãy đánh dấu tất cả các điểm giữa của các đoạn có điểm cuối tại các điểm này. Hỏi số điểm nhỏ nhất trên mặt phẳng có thể dịch chuyển là bao nhiêu?

Hãy xem xét càng nhiều khoảng cách càng tốt giữa N điểm cho trước và chọn khoảng cách lớn nhất trong số các khoảng cách này - gọi đây là khoảng cách giữa hai điểm A và B. Hãy nối điểm A với N - 1 điểm còn lại; chúng tôi nhận được phân đoạn N-1. Trung điểm của các đoạn này khác nhau và đều nằm bên trong hoặc trên ranh giới của đường tròn có tâm tại điểm A có bán kính $\frac{1}{2} |AB|$ (Hình 1).

Tương tự, bằng cách nối điểm B với N-1 điểm còn lại, ta thu được N-1 điểm sưng (trung điểm) nằm bên trong hoặc trên viền của một đường tròn có cùng bán kính với tâm tại điểm B.

Hai đường tròn được dựng chỉ có một điểm là điểm giữa của đoạn AB. Do đó, luôn có ít nhất 2 (N-1) - 1 (vì chúng ta đếm trung điểm của đoạn AB hai lần) điểm sưng ở giữa, tức là có ít nhất (2N-3) điểm sưng.

Hãy chứng minh rằng 2N—3 là số điểm sưng nhỏ nhất. Giả sử N điểm đã cho nằm trên cùng một đường thẳng và khoảng cách giữa các điểm lân cận là như nhau (Hình 2). Dễ dàng nhận thấy trong trường hợp này số điểm sưng - điểm giữa (trong Hình 2 là các điểm màu đỏ) bằng (N-2) + N-1 = 2N-3. Như vậy mọi thứ đã được chứng minh.

Để kết luận, chúng tôi mời độc giả suy nghĩ về vấn đề sau. Với N điểm nào có thể đặt N điểm trên mặt phẳng sao cho chúng không nằm trên cùng một đường thẳng và sao cho số trung điểm sưng của các đoạn có hai đầu tại các điểm này bằng 2N-3?

S. V. Konyazin

M287. Có dãy số tự nhiên nào mà bất kỳ số 1, 2, 3,... nhỏ nhất nào cũng có thể được biểu diễn dưới dạng hiệu của hai số trong dãy này theo đơn vị không?

Một trình tự như vậy tồn tại. Hãy để chúng tôi giải thích ngắn gọn cách xây dựng nó.

Giả sử chúng ta đã xây dựng một dãy hữu hạn với các tính chất sau:

1) tất cả sự khác biệt theo cặp giữa các thành viên của chuỗi này là khác nhau;
2) các số 1,2,...,k có thể được biểu diễn dưới dạng hiệu của hai số hạng của nó;
3) số k+1 không thể được biểu diễn dưới dạng hiệu của hai số hạng của nó.

Giả sử số hạng lớn nhất của dãy này bằng M. Bây giờ chúng ta “cộng” dãy này: thêm vào đó các số 2M và 2M+k+1. Hãy tự kiểm tra xem dãy mới có thỏa mãn tính chất 1.2 (với việc thay thế k bằng k+i, trong đó i là một số tự nhiên nào đó, phụ thuộc vào số hiện tại đầu tiên của dãy, i ≥1) và tính chất 3 (với việc thay thế số k+1 bằng số k+i+1). Ví dụ: áp dụng mô tả “cộng” cho các số 1,2, chúng ta thu được một dãy vô hạn thỏa mãn điều kiện bài toán.

L. G. Limanov

⟦folio 53⟧

**M288.** *Các nhà khoa học, trong đó có bạn bè, tập trung tại hội nghị. Hóa ra không có hai nhà khoa học nào có số bạn bè ngang nhau tại đại hội lại có bạn chung. Chứng minh rằng có một nhà khoa học có đúng một người bạn.*

**M289.** *N quả cân, mỗi quả nặng một số nguyên gam, được xếp thành K đống có trọng lượng bằng nhau. Chứng minh rằng có thể loại bỏ một trong các quả cân bằng ít nhất K cách khác nhau sao cho (N - 1) quả cân còn lại không thể chia thành K đống có trọng lượng bằng nhau.*

⟦figure⟧
Cơm. 3.

**M290.** *Vì cái gì n tồn tại một đường đứt rời khép kín gồm n liên kết sao cho bất kỳ đường thẳng nào chứa một trong các liên kết của đường gãy này đều chứa ít nhất một liên kết nữa?*

⟦column⟧

Hãy lấy nhà khoa học $A$, người có số lượng bạn bè nhiều nhất (nếu có một số nhà khoa học như vậy, hãy lấy bất kỳ ai trong số họ); hãy biểu thị số này bằng $N$. Nếu không ai trong số bạn bè $N$ của nhà khoa học $A$ có chính xác một người bạn, thì vì nhà khoa học $A$ có số lượng bạn bè tối đa nên mỗi người bạn của anh ta có thể có $2, 3, \ldots, N$ bạn bè—tổng cộng $N-1$ khả năng. Vì số bạn bè của nhà khoa học $A$ bằng $N$, điều đó có nghĩa là hai trong số những người bạn của nhà khoa học $A$ có số lượng bạn bè bằng nhau và ngoài ra, một người bạn chung - nhà khoa học $A$. Nhưng điều này mâu thuẫn với điều kiện bài toán, và do đó, ít nhất một trong số các nhà khoa học (bạn của nhà khoa học $A$) có *chính xác một* người bạn.

*VỚI. Landau*

◆

Hãy lấy hai hộp và sắp xếp các quả cân của chúng ta vào trong đó sao cho hộp đầu tiên chứa ít hơn $K$ trọng lượng. Chúng ta sẽ sắp xếp các trọng số như sau.

Đầu tiên, hãy lấy các trọng số có trọng số không chia hết cho $K$. Nếu có ít hơn $K$ trọng lượng như vậy thì hãy đặt chúng vào ô đầu tiên và chuyển sang bước tiếp theo. Nếu có nhiều trọng số như vậy $K$ thì chúng ta đặt tất cả các trọng số vào ô thứ hai.

Trong trường hợp đầu tiên, chúng tôi lấy những trọng số có trọng số chia hết cho $K$ nhưng không chia hết cho $K^2$. Nếu chúng vừa với hộp đầu tiên thì hãy đặt chúng vào đó; nếu không thì đặt tất cả các trọng số không có ở ô đầu tiên vào ô thứ hai.

Nếu trường hợp đầu tiên xảy ra lần nữa, thì chúng ta lấy những trọng số có trọng số chia hết cho $K^2$ nhưng không chia hết cho $K^3$, v.v. Vì có tổng cộng ít nhất $K$ trọng lượng nên một số trọng số chắc chắn sẽ nằm trong hộp thứ hai. Đặt nhóm trọng số đầu tiên không vừa với ô đầu tiên là các trọng số có trọng số chia hết cho $K^r$ nhưng không chia hết cho $K^{r+1}$. Hộp thứ hai sẽ chứa những trọng số có trọng số chia hết cho $K^r$ và hộp đầu tiên sẽ chứa những trọng số có trọng số không chia hết cho $K^r$.

Theo điều kiện bài toán, các trọng số có thể được chia thành các nhóm $K$ có trọng số bằng nhau. Vì có ít hơn $K$ trọng số trong hộp đầu tiên nên tất cả các nhóm $K$ không thể được biểu thị trong đó, điều đó có nghĩa là có một nhóm, tất cả các nhóm đều nằm trong hộp thứ hai. Do đó, tổng trọng số của nhóm này (và do đó của mỗi nhóm) được chia cho $K^r$. Vì chúng ta có tổng cộng $K$ nhóm có trọng số bằng nhau nên tổng trọng lượng của các trọng số được chia cho $K^{r+1}$.

Bây giờ, giả sử rằng chúng tôi đã loại bỏ một số trọng số và các trọng số còn lại có thể được chia thành các nhóm $K$ có trọng số bằng nhau. Như trước đây, chúng ta thấy rằng tổng trọng số của các trọng số còn lại được chia cho $K^{r+1}$.

Trọng lượng của tạ mà chúng ta đã loại bỏ bằng chênh lệch về tổng trọng lượng của tất cả các tạ và các tạ còn lại; do đó, trọng số của trọng số này được chia cho $K^{r+1}$ (lưu ý rằng $r$ có thể bằng 0; điều này tương ứng với tất cả các trọng số nằm ở ô thứ hai, để trống ô đầu tiên). Điều này có nghĩa là nếu chúng ta loại bỏ một trọng số có trọng số không chia hết cho $K^{r+1}$ thì các trọng số còn lại không thể chia thành các nhóm $K$ có trọng số bằng nhau. Nhưng do chọn số $r$ trọng số, các trọng số không chia hết cho $K^{r+1}$, không nhỏ hơn $K$, vì nếu không thì tất cả chúng sẽ được đặt vào ô đầu tiên. Như vậy mọi thứ đã được chứng minh.

*VỚI. V. Konyagin.*

◆

Chúng ta hãy lưu ý ngay rằng số lượng liên kết $n$ phải khá lớn, trong mọi trường hợp là $n > 8$. Trước tiên chúng ta hãy chứng minh (có tính đến nhận xét đã đưa ra) rằng bất kỳ đường gãy khép kín không tự giao nhau nào có số mắt xích lẻ không vượt quá 13 đều có tính chất là luôn có một đường thẳng chứa đúng một mắt xích của đường gãy này. Chúng ta hãy giả sử điều ngược lại, nghĩa là đối với những

⟦folio 54⟧

đường đứt nét ($n = 2k + 1, n \leqslant 13$) không có đường thẳng nào chứa đúng một liên kết. Khi đó ít nhất ba mắt xích của đường gãy của chúng ta phải nằm trên một trong các đường thẳng. Ba mắt xích này có sáu đầu, từ mỗi đầu có một mắt xích gãy, tức là có tổng cộng sáu mắt xích mới và không có mắt xích nào nằm trên cùng một đường thẳng. Do đó, mỗi đường thẳng chứa một trong sáu liên kết đa giác này, theo giả định đã đưa ra, phải chứa ít nhất một liên kết khác với RANES đã được xem xét (liên kết $3 + 6$); Điều này có nghĩa là dòng đứt đoạn được đề cập phải có ít nhất sáu liên kết nữa. Ta thấy số liên kết trong một đường đứt nét như vậy không được nhỏ hơn $3 + 6 + 6 = 15$ - mâu thuẫn.

Bây giờ chúng ta hãy chứng minh rằng đối với mọi đường đứt nét $n \geqslant 10$ chẵn và lẻ $n \geqslant 15$, được thảo luận trong bài toán, đều tồn tại $n \geqslant 10$ đây là những ngôi sao hữu hạn $\frac{n}{2}$ nổi tiếng (Hình 3; trong hình này $n = 10$ và $n = 12$). Việc xây dựng một đường đa tuyến khép kín không tự giao nhau với số lượng liên kết lẻ lớn hơn 13 có thuộc tính được chỉ định sẽ khó khăn hơn. Một đường gãy có 15 mắt xích được hiển thị trong Hình 4. Bằng cách cắt liên tiếp hai đường thẳng từ nó, chúng ta sẽ có được một đường gãy có 17 mắt xích, 19, v.v. (Hình 5).

S. Lando

F296. Mỗi $k$ tụ điện khác nhau có cực trị $C_1, C_2, \dots, C_k$ được tích điện đến hiệu hiệu $U$. Sau đó tất cả các tụ điện được nối nối tiếp với các dải có kích thước khác nhau thành một mạch kín. Tên trên mỗi tụ điện trong mạch này.

Trước khi nối các tụ điện vào mạch điện, điện tích của chúng là $q_1 = C_1U, q_2 = C_2U, \dots, q_i = C_iU, \dots, q_k = C_kU$. Chúng ta hãy biểu thị điện tích của các tụ điện sau khi nối chúng vào mạch tương ứng bằng $q'_1, q'_2, \dots, q'_k$. Sự phân bố điện tích trên các bản tụ điện sẽ như trong Hình 6. Theo định luật bảo toàn điện tích, tổng điện tích của các tụ điện được nối với nhau bằng một tấm (một trong những phần như vậy của mạch được đánh dấu trong Hình 6 bằng một đường chấm chấm) phải bằng tổng điện tích trên các bản này trước khi nối các tụ điện. Đó là (có tính đến các dấu hiệu của phí)

$$q'_2 - q'_1 = q_2 - q_1 = (C_2 - C_1)U,$$

$$q'_3 - q'_2 = q_3 - q_2 = (C_3 - C_2)U,$$

$$q'_k - q'_{k-1} = q_k - q_{k-1} = (C_k - C_{k-1})U.$$

Ngoài ra, công truyền một điện tích dọc theo một bộ đếm kín trong trường nhà máy điện bằng 0, do đó tổng hướng trên các tụ điện riêng lẻ bằng 0: $U_1 + U_2 + \dots + U_k = 0$, hoặc

$$\frac{q'_1}{C_1} + \frac{q'_2}{C_2} + \dots + \frac{q_k}{C_k} = 0.$$

Từ hệ phương trình (*) và (**), chúng ta xác định điện tích mới của tụ điện và sau đó là hướng của chúng. Trước hết, hãy biểu thị tất cả các điện tích thông qua điện tích $q'_1$ của tụ điện thứ nhất. Từ phương trình đầu tiên của hệ (*) suy ra $q'_2 = q'_1 + (C_2 - C_1)U$. Cộng các phương trình thứ nhất và thứ hai của hệ (*), ta thu được $q'_3 = q'_1 + (C_3 - C_1)U$.

⟦folio 55⟧

Tương tự, đối với điện tích của tụ điện thứ $i$ ta thu được
$$q'_i = q'_1 + (C_i - C_1) U.$$
Chúng ta hãy thay thế các biểu thức thu được vào phương trình (**):
$$\frac{q'_1}{C_1} + \left[ \frac{q'_1}{C_2} + \left( 1 - \frac{C_1}{C_2} \right) U \right] + \dots + \left[ \frac{q'_1}{C_k} + \left( 1 - \frac{C_1}{C_k} \right) U \right] = 0,$$
hoặc
$$q'_1 \left( \frac{1}{C_1} + \frac{1}{C_2} + \dots + \frac{1}{C_k} \right) + kU - C_1 U \left( \frac{1}{C_1} + \frac{1}{C_2} + \dots + \frac{1}{C_k} \right) = 0.$$
Do đó $q'_1 = (C_1 - kC_0) U$, trong đó $C_0$ là điện dung của các đầu nối cân bằng của tụ điện:
$$\frac{1}{C_0} = \frac{1}{C_1} + \frac{1}{C_2} + \dots + \frac{1}{C_k}.$$
Vì $q'_i = q'_1 + (C_i - C_1) U$ thì
$$q'_i = (C_1 - kC_0) U + (C_i - C_1) U = (C_i - kC_0) U.$$
Điều này có nghĩa là điện áp trên tụ điện thứ $i$ là
$$U'_i = \frac{q'_i}{C_i} = \left( 1 - k \frac{C_0}{C_i} \right) U.$$

F297. Chúng tôi đóng hai lỗ cùng một lúc bằng phích cắm hình nón trong một bình phẳng chứa đầy p. Bán kính lỗ R và r. Xác định tổng lực tác dụng lên nút của chất lỏng. Chúng tôi không tính đến lĩnh vực mềm mại.

Cơm. 6.

Cơm. 7.

Mỗi phần tử nhỏ của bề mặt bên của phích cắm có diện tích $\Delta s_i$ chịu tác dụng của một lực áp suất chất lỏng $\Delta F_i = p \Delta s_i$, hướng vuông góc với bề mặt bên của phích cắm (Hình 7). Từ tính đối xứng, có thể thấy rõ các thành phần nằm ngang của các lực như vậy tác dụng lên các phần tử nhỏ khác nhau của bề mặt nút chai cộng lại sẽ tiêu diệt lẫn nhau. Do đó, hợp lực của các lực ép có phương thẳng đứng và bằng tổng các thành phần thẳng đứng của các lực này. Đó là
$$F = \Sigma F_i \sin \alpha = \Sigma p \Delta s_i \sin \alpha = p \Sigma \Delta s_i \sin \alpha.$$
Tích $\Delta s_i \sin \alpha$ là hình chiếu diện tích của phần tử lên một mặt phẳng song song với thành bình. Do đó, tổng $\Sigma \Delta s_i \sin \alpha$ bằng diện tích hình chiếu của bề mặt bên của phích cắm lên mặt phẳng này, tức là $\pi (R^2 - r^2)$. Đó là lý do tại sao
$$F = p \pi (R^2 - r^2).$$
Hãy cho thêm một lời giải trong số bài toán này. Chúng ta hãy xem xét một mặt phẳng tương tự như mặt phẳng đã cho, bằng thể tích của nút chặn giữa các thành bình (Hình 8). Vì thể tích chất lỏng được phân bổ ở trạng thái cân bằng nên tổng hợp các lực tác dụng lên nó bằng 0. Những lực nào tác dụng lên thể tích chất lỏng thoát ra? Đây là các phản lực từ thành bình, có giá trị tuyệt đối bằng nhau $N_1 = p \pi R^2$ và $N_2 = p \pi r^2$, và kết quả là $F$

⟦folio 56⟧

Cơm. 8.

F298. Bên trong máy ảnh, vuông góc với tấm đồng nhất, có một gương phẳng, chiều dài của DB bằng một nửa tiêu cự của vật (Hình 9). Ảnh A của sao Vega nằm tính từ tâm của tấm đồng nhất ở khoảng cách bằng một nửa bán kính của vật thể. Độ sáng của “ảnh phản chiếu” C của sao Vega nhỏ hơn độ sáng của ảnh A của nó khi có gương bao nhiêu lần?

Lực ép từ chất lỏng xung quanh hướng thẳng đứng lên trên. Vì $N_1 - N_2 = \pi p (R^2 - r^2)$.

Rõ ràng, lực tương tự tác dụng lên phích cắm từ phía chất lỏng.

♦

Hãy tìm tỷ lệ các luồng ánh sáng phát ra từ một ngôi sao ở xa và rơi xuống tấm ảnh tại các điểm A và C (Hình 9). Tại điểm A, những tia sáng đi qua thấu kính của vật ở phía dưới điểm G, giao điểm của đường thẳng AD với thấu kính, sẽ được thu lại. Các tia tới phía trên điểm G rơi vào gương và bị phản xạ từ gương và tập trung tại điểm C.

Xét thấu kính của một vật trong mặt phẳng vuông góc với chùm tia tới (Hình 10). Đường thẳng EK chia thấu kính thành hai đoạn, qua đó các tia tới điểm A hoặc điểm C. Vì thấu kính được chiếu sáng đều bởi ánh sáng của ngôi sao nên tỉ số quang thông bằng tỉ số diện tích của các đoạn tương ứng. Hãy tìm mối quan hệ này.

Tấm ảnh nằm trong mặt phẳng tiêu điểm của vật, chiều dài của gương bằng một nửa tiêu cự của vật nên $DB = OD$ (xem Hình 9) và $\Delta GDO = \Delta ADB$. Do đó, $GO = AB = R/2$, trong đó $R$ là bán kính của vật thể.

Cơm. 10.

sự vật. Sau đó (xem Hình 10) $\angle GKO = 30^\circ$, $\angle KOG = 60^\circ$ và $\angle EOK = 120^\circ$. Bây giờ chúng ta biểu thị diện tích của các đoạn $S_1$ và $S_2$ thông qua diện tích của các cung tương ứng và tam giác EOK:

$$S_1 = \frac{\pi R^2}{360} \cdot 120 - R^2 \frac{\sqrt{3}}{4} \quad \text{и} \quad S_2 = \frac{\pi R^2}{360} \cdot 240 + R^2 \frac{\sqrt{3}}{4}.$$

Tỷ lệ $S_1/S_2$ bằng

$$\frac{S_1}{S_2} = \frac{\pi R^2/3 - R^2}{\pi R^2/3 + R^2} \cdot \frac{\sqrt{3}}{4} = \frac{4\pi - 3\sqrt{3}}{8\pi + 3\sqrt{3}} \approx 0,25.$$

Tôi. Sh. Tiếng Slovodechkiy
