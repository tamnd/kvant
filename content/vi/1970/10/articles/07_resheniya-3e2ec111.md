---
id: 1970-10-resheniya-3e2ec111
issue: kvant_1970_10
year: 1970
number: "10"
title: '[Lời giải các bài toán M8—M10; F12—F17]'
rubric: zadachnik-kvanta
page_first: 40
page_last: 53
page_labels: 38, 39, 40, 41, 42, 43, 44, 45, 46, 47, 48, 49, 51
tag: P5Q0
lang: vi
source: kvant_digital
extraction: vision
content_sha256: be1b4c1be136b0e498adfb5ec2796e78cbbf61854862c86fbfe0f90932445a2e
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1970/10/articles/07_resheniya-3e2ec111.md
source_content_sha256: 0ef88b8966c3094f1ac04f975f54fe5dc86ca729ad939639031822e8480e438c
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦folio 38⟧

M8. Hai người chơi một trò như sau. Từ một đống có 25 que diêm, mỗi người lần lượt lấy cho mình một, hai hoặc ba que diêm. Người thắng là người mà khi kết thúc trò chơi — sau khi tất cả que diêm đã được lấy hết — có số que diêm chẵn.

Ai thắng khi chơi đúng — người đi trước hay đối thủ của người ấy? Người ấy phải chơi thế nào để thắng? Đáp án thay đổi thế nào nếu coi người lấy được số que diêm lẻ là người thắng?

Hãy khảo sát trò chơi này trong trường hợp tổng quát, khi có 2n+1 que diêm và được phép lấy bất kỳ số que diêm nào từ 1 đến m.

Lời giải

Để nói về trò chơi, cần gọi tên những người tham gia trò chơi bằng cách nào đó. Điều kiện bài toán một lần và mãi mãi gọi một người là Tôi, người kia là Anh ấy.

Trước hết, hãy khái quát điều kiện bài toán một chút. Số N que diêm nằm trên bàn lúc bắt đầu trò chơi có thể là bất kỳ, không chỉ là số lẻ. Khi đó với N chẵn, một trong các người chơi thắng nếu lúc kết thúc trò chơi tổng số que diêm của người đó là chẵn, còn người kia — nếu là lẻ.

Nói đúng ra, chúng ta xét đồng thời vô số trò chơi, vì N và m có thể là bất kỳ số tự nhiên nào. Hơn nữa, nếu m và N đã cho, có thể có hai phương án: Tôi thắng nếu khi kết thúc trò chơi tôi có 1) số que diêm chẵn, 2) số que diêm lẻ.

Trước hết, ta sẽ nói về tất cả các phương án của trò chơi này cùng một lúc.

Hãy suy nghĩ xem người chơi cần nhớ những gì trong quá trình chơi. Người ấy có cần nhớ tất cả các nước đi của mình và của đối thủ từ đầu trò chơi không? Không, trong mọi phương án người ấy chỉ cần biết những điều sau:

1) còn bao nhiêu que diêm trên bàn,
2) số que diêm của người ấy có chẵn không,
3) đến lượt ai đi.

Nếu ba tham số này đã cho, ta sẽ nói rằng trạng thái đã được xác định. Người chơi có thể thực hiện m nước đi khác nhau (hoặc ít hơn, nếu số que diêm còn lại trên bàn ít hơn m). Mỗi nước đi của người ấy chuyển trò chơi sang một trạng thái khác, khi đối thủ của người ấy đi.

Có thể biểu diễn thuận tiện các trạng thái của trò chơi trên giấy dưới dạng các ô hoặc vòng tròn, còn các nước đi có thể dưới dạng các mũi tên. Ta sẽ làm như vậy.

Bảng ở hình 1 được lập cho trường hợp m=2 (mỗi nước chỉ có thể lấy một hoặc hai que diêm),

Trong các bảng ở hình 1—4:
Cột I — số thứ tự của hàng m, cho biết còn bao nhiêu que diêm trên bàn.
Cột II — tôi có số que diêm chẵn, đến lượt tôi.
Cột III — tôi có số que diêm chẵn, đến lượt anh ấy.
Cột IV — tôi có số que diêm chẵn, đến lượt tôi.
Cột V — tôi có số que diêm chẵn, đến lượt anh ấy.

⟦folio 39⟧

Hình 1. Bảng các trạng thái và nước đi có thể của trò chơi với $m=2$.

và Tôi thắng nếu khi kết thúc trò chơi tôi có số que diêm chẵn. Thực tế chỉ vẽ những trạng thái khi trên bàn còn không quá bảy que diêm.

Các mũi tên màu cho biết người chơi có thể đi như thế nào: người chơi đến lượt trong ô này có thể đi theo bất kỳ mũi tên nào đi ra từ ô đó. Chẳng hạn, ô đầu tiên bên trái ở hàng số 5 (màu xám) tương ứng với trạng thái trò chơi khi trên bàn còn 5 que diêm, tôi có số que diêm chẵn và đến lượt tôi, còn hai mũi tên đi ra từ ô này cho biết Tôi có thể chuyển trò chơi sang những trạng thái nào bằng nước đi tiếp theo.

Có thể tiếp tục bảng bằng trực quan và đặt tương ứng với ô đó chữ В, nếu khi trò chơi bắt đầu từ trạng thái này, Tôi có thể thắng, dù Anh ấy có cố gắng cản trở tôi đến đâu.

Ta gọi trạng thái là thua và đặt tương ứng với ô đó chữ П, nếu khi trò chơi bắt đầu từ trạng thái này, Anh ấy có thể thắng và, nếu Anh ấy không mắc sai lầm, Tôi không thể ngăn cản điều đó.

Bây giờ ta chuyển sang phần chính của lời giải: điền các chữ В và П vào tất cả các ô của bảng. Trước hết ta sẽ làm điều này cho trò chơi tương ứng với hình 1. Ở hàng số không, dĩ nhiên phải đặt các chữ như sau: ВВПП, vì ta coi là Tôi thắng nếu khi trò chơi kết thúc tôi có số que diêm chẵn. Sau đó các chữ phải được điền từ trên xuống dưới theo quy luật sau.

I. Nếu đến lượt tôi đi (tức là ô nằm ở cột II hoặc IV), thì trong đó đặt:

chữ В, nếu có ít nhất một mũi tên từ nó dẫn đến ô có chữ В;

chữ П, nếu mọi mũi tên đi ra từ nó đều dẫn đến ô có chữ П.

II. Nếu đến lượt anh ta đi (tức là ô nằm ở cột III hoặc V), thì trong đó đặt:

chữ П, nếu có ít nhất một mũi tên từ nó dẫn đến ô có chữ П;

chữ В, nếu mọi mũi tên đi ra từ nó đều dẫn đến ô có chữ В.

Vì tất cả các mũi tên trong bảng đều hướng từ dưới lên trên, nên quy luật này cho phép điền toàn bộ bảng, dù ta kéo dài nó đến đâu.

Trong trường hợp của chúng ta ($m=2$), để điền các ô của hàng thứ $n$, chỉ cần biết cách điền các ô của hàng thứ $(n-1)$ và thứ $(n-2)$. Thực ra hoàn toàn không cần vẽ tất cả các mũi tên như ở hình 1. Chỉ cần vẽ riêng (trên một mảnh giấy can) một “mẫu” — tập hợp các mũi tên đi ra từ các ô của một hàng, rồi lần lượt đặt mẫu này lên tất cả các hàng của bảng, điền vào đó các chữ В và П theo những quy tắc ghi trên nền xanh. Hình 2 cho thấy thời điểm khi ta đã điền toàn bộ

⟦folio 40⟧

Hình 2. Bảng các trạng thái thắng và thua của trò chơi với $m=2$.

bảng đến hàng thứ 5 và sẵn sàng điền hàng thứ 6. Bằng cách đó có thể điền bảng đến bất cứ chỗ nào, chẳng hạn đến hàng thứ 25 và xem chữ nào sẽ đứng ở vị trí đầu tiên của hàng thứ 25. Nếu đó là В, thì người bắt đầu trò chơi, lúc đầu trên bàn có 25 que diêm, thắng, còn nếu đó là П, thì thua.

Thực ra, không cần điền toàn bộ bảng. Vấn đề là hàng thứ 4 trùng với hàng số không, còn hàng thứ 5 trùng với hàng thứ nhất. Vì thế hàng thứ 6 nhất thiết trùng với hàng thứ 2 (vì mỗi hàng được xác định bởi hai hàng trước đó). Khi ấy hàng thứ 7 trùng với hàng thứ 3, hàng thứ 8 với hàng thứ 4, hàng thứ 9 với hàng thứ 5, v.v. Các hàng sẽ lặp lại với chu kỳ 4, từ đó suy ra rằng mọi hàng có số 4 $k$ sẽ là ВВПП;
hàng có số $4k+1$ sẽ là ПВВП;
hàng có số $4k+2$ sẽ là ВПВП;
hàng có số $4k+3$ sẽ là ВПВП.

Đặc biệt, hàng thứ 25 sẽ là ПВВП ($25=4\cdot 6+1$).

Có thể dự đoán trước rằng nhất thiết phải có chu kỳ. Thật vậy, giả sử ta đã điền bảng đến một hàng nào đó. Sau đó mọi thứ phụ thuộc vào cách hai hàng cuối được điền. Số mọi cách điền hai hàng bằng các chữ П và В là hữu hạn (nó không vượt quá $2^8$). Vậy nên khi điền bảng, không thể mãi xuất hiện một cặp hàng mới. Và khi một cặp hàng nào đó lặp lại, tính chu kỳ bắt đầu.

Sau khi các chữ В và П đã được đặt trong bảng, chiến lược mà Tôi phải tuân theo để thắng cũng trở nên rõ ràng: mỗi lần cần đi một nước dẫn đến ô có chữ В. Quy luật đặt các chữ В và П nêu trên được xây dựng chính sao cho nếu Tôi một lần rơi vào ô В, thì sau đó Tôi sẽ luôn có thể đi vào В, và đối thủ không thể ngăn cản tôi.

Trường hợp khi Tôi thắng nếu cuối cùng tôi có số que diêm lẻ được khảo sát tương tự. Có thể đặt ở hàng không ППВВ và điền tiếp bảng theo đúng quy luật ấy. Chu kỳ lại bằng 4. Nhưng cũng có thể không làm tất cả những điều đó, mà dùng cho trường hợp này chính hình 2.

Nhận xét rằng không cho người chơi gì trước khi bắt đầu trò chơi và yêu cầu rằng cuối cùng người đó có số que diêm lẻ cũng giống như cho người đó một que diêm trước khi bắt đầu trò chơi và yêu cầu rằng cuối trò chơi người đó có số que diêm chẵn. Như vậy, trong trường hợp mới này Tôi thắng nếu trong bảng ở hình 2 tại ô giao của hàng thứ $N$ và

cột IV có В, nếu Tôi bắt đầu,

cột V có В, nếu Anh ấy bắt đầu.

Cũng nhận xét rằng mẫu không thay đổi nếu đổi chỗ cột П với IV, còn III với V. Ở hàng đầu tiên sau phép đổi chỗ đó, thay vì ВВПП sẽ là ППВВ. Vì vậy, bảng cho trường hợp khi để thắng, Tôi phải có số que diêm lẻ, có thể nhận được từ bảng cho trường hợp đã xét bằng phép đổi chỗ cột đã nêu. Điều này cũng đúng với mọi giá trị khác của $m$.

Bây giờ giả sử $m=3$. Bảng như trước vẫn sẽ gồm cùng

⟦folio 41⟧

Hình 3. Bảng cho trò chơi với $m=3$.

bốn cột ấy. Mẫu thay đổi (xem hình 3). Bây giờ mỗi hàng phụ thuộc vào ba hàng trước. Để sắp xếp các chữ В và П, áp dụng được quy tắc đã viết ở trang 39. Khi sắp xếp các chữ, ta thấy rằng chu kỳ gồm tám hàng. Đặc biệt, hàng thứ 25 trùng với hàng thứ nhất: ПВВП.

Như vậy, trong trường hợp $m=3$ và $N=25$ có đáp án sau

Đáp án: nếu người thắng được coi là người lấy số que diêm chẵn, thì người bắt đầu thua, còn nếu người thắng được coi là người lấy số que diêm lẻ, thì người bắt đầu thắng.

Trường hợp tổng quát được khảo sát tương tự. Độ dài chu kỳ bằng $m+2$, nếu $m$ chẵn, và $2m+2$, nếu $m$ lẻ. Các chu kỳ này được biểu diễn ở hình 4 a, b. Các mẫu cho $m=8$ và $m=9$ cho phép hiểu các mẫu trong trường hợp tổng quát sẽ như thế nào. Vẽ các mũi tên ở đây không tiện. Các ô tô mỗi màu là những trạng thái mà người chơi có thể đi tới từ ô có chấm cùng màu. Quy tắc sắp xếp các chữ В và П vẫn như đã viết ở trang 39. Việc kiểm tra rằng các chu kỳ thực sự như vậy

⟦folio 42⟧

xin để dành cho bạn đọc. Chỉ nhận xét điều sau. Để chắc chắn rằng chu kỳ sẽ lặp lại, cần kiểm tra việc sắp xếp các chữ trong mọi hàng của chu kỳ thứ nhất và trong $m$ hàng đầu của chu kỳ thứ hai.

Như thấy, khi $m$ lớn, phần lớn các chữ tuân theo quy tắc ấy. Tất cả các chữ vi phạm quy tắc này trong hình 4, a, b được khoanh tròn. Vậy người bắt đầu thua trong các trường hợp sau.

| chu kỳ | Người có tổng «chẵn» thắng | Người có tổng «lẻ» thắng |
| :--- | :--- | :--- |
| m chẵn | N cho số dư 1 khi chia cho m+2 | N cho số dư m+1 hoặc 0 khi chia cho m+2 |
| m lẻ | N cho số dư 1 hoặc m+1 khi chia cho 2 m+2 | N cho số dư 0 hoặc m+2 khi chia cho 2 m+2 |

**M9. Xét các tính chất sau của một tứ diện (tứ diện ở đây là một hình chóp tam giác bất kỳ):**
1) mọi mặt có diện tích bằng nhau;
2) mỗi cạnh bằng cạnh đối diện;
3) mọi mặt bằng nhau;
4) tâm các mặt cầu ngoại tiếp và nội tiếp trùng nhau;
5) tổng các góc phẳng tại mỗi đỉnh của tứ diện bằng nhau.
Chứng minh rằng tất cả các tính chất này tương đương.
Hãy cố gắng tìm những tính chất khác của tứ diện tương đương với chúng.

Lời giải. Trong bài này, điều rất quan trọng là chọn một con đường chứng minh hợp lý: phân tích xem tính chất nào dễ suy ra từ tính chất nào hơn. Theo thông lệ, cùng với các từ “từ... suy ra...” ta sẽ đặt mũi tên: ⇒

Ta thấy tiện thêm vào vài tính chất nữa của tứ diện:

6) tổng các góc phẳng tại mỗi đỉnh bằng 180°;
7) hình triển khai của tứ diện là một tam giác nhọn, trong đó kẻ các đường trung bình (hình 5);
8) tất cả các mặt là những tam giác nhọn có cùng bán kính đường tròn ngoại tiếp;

Hình 4, 6. Bảng cho trò chơi với m lẻ và mẫu cho m=9.

⟦folio 43⟧

Hình 5.

9) hình chiếu của tứ diện lên mỗi trong ba mặt phẳng song song với hai cạnh đối diện là hình chữ nhật, —

và chứng minh rằng các tính chất (1)—(9) là tương đương, theo thứ tự sau:

Phần lớn trong mười hai định lý được ký hiệu ở đây bằng các mũi tên là gần như hiển nhiên. Ta sẽ chứng minh chúng theo thứ tự.

(5) ⇒ (6). Tổng tất cả các góc phẳng của mọi mặt của tứ diện bằng tổng các góc của bốn tam giác, tức là $4 \cdot 180^\circ = 720^\circ$, vì thế, nếu tổng các góc tại mỗi đỉnh bằng nhau, thì mỗi tổng trong số đó bằng $180^\circ$. Mệnh đề ngược: (6) ⇒ (5) là hiển nhiên.

(4) ⇒ (8). Nếu $R$ là bán kính mặt cầu ngoại tiếp tứ diện, $r$ là bán kính mặt cầu nội tiếp và tâm của các mặt cầu này trùng nhau, thì tiếp điểm của mặt cầu với mỗi mặt nằm bên trong mặt đó và cách mỗi đỉnh của tam giác một khoảng $\sqrt{R^2-r^2}$, tức là là tâm

Hình 6.

đường tròn ngoại tiếp tam giác này có bán kính $\sqrt{R^2-r^2}$.

(8) ⇒ (4). Rõ ràng rằng trong mọi tứ diện, các đường vuông góc hạ từ tâm $O$ của mặt cầu ngoại tiếp xuống các mặt đi qua tâm các đường tròn ngoại tiếp, và nếu bán kính của tất cả các đường tròn này bằng $R_1$, thì điểm $O$ cách đều tất cả các mặt (một khoảng $r = \sqrt{R^2-R_1^2}$). Nếu chân các đường vuông góc nằm bên trong các mặt, thì $O$ là tâm của mặt cầu ngoại tiếp bán kính $r$.

(8) ⇒ (6). Nếu bán kính các đường tròn ngoại tiếp của các mặt $ABC$ và $DBC$ của tứ diện $ABCD$ bằng nhau, thì $\angle BAC = \angle BDC$, vì các góc này chắn các cung khác $BC$ bằng nhau trong các đường tròn bằng nhau (ở đây điều quan trọng là $\triangle BAC$ và $\triangle BDC$ là các tam giác nhọn!). Điều này cũng đúng với mọi tham số khác của các mặt kề nhau.

Do đó, $\angle BDC + \angle CDA + \angle ADB = \angle BAC + \angle CBA + \angle ACB = 180^\circ$ và tương tự đối với mọi đỉnh khác.

(6) ⇒ (7). Khai triển của một tứ diện tùy ý $ABCD$ là lục giác $D_1AD_2BD_3C$, được chia thành bốn tam giác (hình 6). Hiển nhiên từ (6) suy ra rằng các đoạn thẳng $D_1A$ và $AD_2$, $D_2B$ và $BD_3$, $D_3C$ và $CD_1$ nằm trên cùng một đường thẳng, tức là các điểm $A$,

⟦folio 44⟧

B và C là trung điểm các cạnh của $\Delta D_1D_2D_3$ (như ở hình 5). Tam giác này nhọn, vì trong góc tam diện của tứ diện (tại đỉnh D), mỗi góc phẳng nhỏ hơn tổng của hai góc kia.

(9) $\Rightarrow$ (7), (7) $\Rightarrow$ (8) và (7) $\Rightarrow$ (2) là hiển nhiên. (2) $\Rightarrow$ (3) cũng hiển nhiên (các tam giác bằng nhau theo ba cạnh); (3) $\Rightarrow$ (1) hiển nhiên.

Chỉ còn phải chứng minh rằng (1) $\Rightarrow$ (9). Phần này hóa ra là khó nhất đối với độc giả.

(1) $\Rightarrow$ (9). Nhận xét rằng nếu $p_1$ và $p_2$ là hai mặt phẳng song song, AK và BH là hai đoạn thẳng có các đầu mút A và B nằm trong mặt phẳng $p_1$, còn các đầu mút K và H nằm trong mặt phẳng $p_2$, thì các đoạn thẳng AK và BH bằng nhau khi và chỉ khi hình chiếu của chúng lên mặt phẳng $p_1$ (hoặc $p_2$) bằng nhau. Điều này dễ dàng chứng minh bằng định lý Pythagore (hình 7).

Dựng các mặt phẳng song song $p_1$ và $p_2$ qua các cạnh AB và CD của tứ diện. Gọi $C_1$ và $D_1$ là hình chiếu của các điểm C và D lên mặt phẳng $p_1$ (hình 8, a), O là giao điểm của $C_1D_1$ và AB. Nếu diện tích của $\triangle CAD$ và $\triangle CBD$ bằng nhau thì các đường cao AK và BH của các tam giác này bằng nhau, do đó các hình chiếu của chúng lên $p_1$ cũng bằng nhau: AK$_1$ = BH$_1$, vì thế AO = OB (hình 8, b), từ đây suy ra, đặc biệt, rằng các điểm A và B nằm ở hai phía khác nhau của đường thẳng C$_1$ D$_1$. Tương tự, vì diện tích $\triangle ACB$ và $\triangle ADB$ bằng nhau, nên C$_1O$ = D$_1O$. Do đó, AC$_1BD_1$ là hình bình hành, tức là AC$_1$ = BD$_1$ và C$_1B$ = D$_1A$, suy ra AC = BD và BC = AD. Tương tự chứng minh được rằng AB = CD, vì vậy AC$_1BD_1$ là hình chữ nhật.

M10. Bốn hình tròn có tâm là các đỉnh của một tứ giác lồi, phủ kín hoàn toàn tứ giác này. Chứng minh rằng có thể chọn ba trong số chúng phủ tam giác có các đỉnh là tâm của các hình tròn ấy.

Lời giải. Khó khăn chủ yếu trong bài toán này là nghĩ ra một lập luận bao quát mọi trường hợp có thể xảy ra.

Hình 7.

Hình 8, a. Tứ diện trong không gian.

Hình 8, b. Hình chiếu của tứ diện lên mặt phẳng.

⟦folio 45⟧

Hình 9.

các cách bố trí các đường tròn và mọi tứ giác có thể có về hình dạng.

Ý tưởng của lời giải dưới đây thuộc về H. Vasiliev.

Kí hiệu các hình tròn có tâm A, B, C, D tại các đỉnh của tứ giác đã cho ABCD là Kₐ, Kₑ, K₃, K₄, bán kính của chúng là rₐ, rₑ, r₃, r₄. Giả sử mệnh đề của bài toán sai. Khi đó mỗi hình tròn có một điểm chung với phần của tam giác đối diện nó không được các tam giác phủ:

chẳng hạn, Kₐ phải chứa các điểm của △BCD không được bất kì

Hình 10.

hình tròn nào Kₐ, Kₑ, K₃, K₄ phủ. Gọi O là giao điểm các đường chéo. Với giả thiết của chúng ta, chứng minh rằng rₐ ≥ OA, tức là hình tròn Kₐ chứa điểm O. Phần còn lại đã rõ: hoàn toàn tương tự có thể chứng minh rằng điểm O thuộc Kₐ và K₃, và từ đó hiển nhiên suy ra rằng các hình tròn này phủ △ABC. Hãy xem hình 9,10: nếu OL và ON là các đường vuông góc hạ xuống các đường thẳng AB và BC, thì Kₐ phủ △OAL, K₃ phủ △OCN, K₄ phủ △OBL và △OBN, còn bốn tam giác vuông này hiển nhiên phủ △ABC, ngay cả khi

Hình 11, a.

Hình 11, b.

⟦folio 46⟧

một trong các tam giác AOB hoặc OBC (như ở hình 10) là tù.

Ta đi đến mâu thuẫn với giả thiết của mình, do đó mệnh đề của bài toán là đúng.

Vậy, còn phải chứng minh rằng $r_A \geqslant OA$. Ta sẽ cần mệnh đề sau đây, gần như hiển nhiên.

Bổ đề. Cho một tứ giác lồi PQRS và hình tròn $K_R$ (không chứa toàn bộ $\triangle PQR$). Khi đó trong tất cả các điểm nằm bên trong $\triangle PQR$ và ngoài $K_R$, điểm gần điểm $S$ nhất sẽ là:

a) chân $F$ của đường vuông góc $SF$ hạ từ điểm $S$ xuống đường thẳng $PR$, nếu điểm $F$ này nằm ngoài hình tròn $K_R$ (hình 11, a);

b) điểm $E$ giao của đường tròn $K_R$ với đoạn $PR$, nếu điểm $F$ nằm bên trong hình tròn $K_R$ (hình 11, b). (Ở đây điều quan trọng là góc QRS của tứ giác nhỏ hơn $180^\circ$; dành việc chứng minh bổ đề cho độc giả.)

Có thể coi rằng $\angle AOB \leqslant 90^\circ$ (nếu không thì ta sẽ lấy không phải $B$ mà là $D$). Đặt $BB_1 \perp AC$; $AA_1 \perp BD$; $B_1A_2 \perp BD$ (hình 12). Giả sử rằng $r_A < OA$ và $E - \text{gần nhất } K$ trên đoạn $OA$ và $AE = r_A$, $EM - \text{đường vuông góc}, \text{kẻ từ } E$ xuống $BD$. Rõ ràng khi đó $AM > AE$. Ta sẽ chứng minh rằng tuy vậy $r_A > AM$, từ đó suy ra rằng giả sử của ta ($r_A < OA$) là sai.

Trước hết chứng minh rằng $r_B > BM$. Áp dụng bổ đề cho $\triangle ACD$, đường tròn $K_A$ và điểm $B$. Có hai trường hợp:

a) $E$ nằm giữa $A$ và $B_1$. Khi đó $r_B > BB_1 > BA_2 \geqslant BM$;

b) $E$ nằm giữa $O$ và $B_1$. Khi đó (theo bổ đề)

$$r_B > BE > BM.$$

Vậy, ta biết rằng điểm $M$ thuộc $K_B$. Áp dụng bổ đề cho $\triangle BCD$, đường tròn $K_B$ và điểm $A$ (lưu ý rằng $M$ nằm giữa $O$ và $A_1$, nên luôn xảy ra trường hợp 6)), ta được $r_A > AM$. Vòng tròn đã khép lại, mâu thuẫn cần tìm đã thu được.

Bài 12. Hai viên bi thép nặng giống nhau quay trên các thanh nhẹ có độ dài $l$ và $2l$ quanh các điểm $O_1$, $O$, khoảng cách giữa chúng bằng 3$l$ (hình 13). Ban đầu các viên bi ở các điểm $A$ và $B$, có vận tốc tương ứng là $v$ và $2v$. Trong thời gian $t$ các viên bi va chạm bao nhiêu lần? Trong thời gian bao lâu các viên bi sẽ va chạm $k$ lần? Coi va chạm của các viên bi là đàn hồi tuyệt đối.

Lời giải. Vì các viên bi giống nhau, nên khi va chạm đàn hồi tuyệt đối chúng sẽ trao đổi vận tốc. Điều này suy ra từ các định luật bảo toàn năng lượng và động lượng (lượng chuyển động) của các viên bi khi va chạm. Lần đầu tiên các viên bi sẽ va chạm khi mỗi viên quay được nửa vòng quanh điểm mà nó quay quanh.

Cần thời gian $t_1 = \frac{\pi \cdot 2l}{2v} = \frac{\pi l}{v}$ cho việc đó. Sau va chạm, viên bi bên trái sẽ có vận tốc $2v$, còn viên bi bên phải — vận tốc $v$.

Lần va chạm thứ hai của các viên bi sẽ xảy ra sau thời gian $t_2 = \frac{4\pi l}{v}$ kể từ lần thứ nhất, khi viên bi bên phải thực hiện một vòng quay quanh điểm $O_1$. Trong thời gian đó, viên bi bên trái thực hiện bốn vòng quay quanh điểm $O$ — nó có vận tốc lớn gấp đôi và quay theo đường tròn có bán kính nhỏ hơn hai lần

⟦folio 47⟧

Hình 13.

Khi va chạm, các viên bi lại trao đổi vận tốc, và lần va chạm thứ ba sẽ xảy ra sau thời gian $t_3 = 2t_1 = \frac{2\pi l}{v}$ kể từ lần thứ hai, khi mỗi viên bi thực hiện một vòng quay. Như vậy, sau mỗi lần va chạm lẻ, viên bi bên trái sẽ có vận tốc $2v$, còn viên bi bên phải — vận tốc $v$, và vì thế lần va chạm chẵn tiếp theo sẽ xảy ra sau thời gian $t' = t_2 = t_4 = \cdots = \frac{4\pi l}{v}$.

Sau mỗi lần va chạm lẻ, viên bi bên trái sẽ có vận tốc $v$, còn viên bi bên phải — vận tốc $2v$, và lần va chạm tiếp theo, nay là lẻ, của các viên bi sẽ xảy ra sau thời gian $t'' = 2t_1 = t_3 = \cdots = \frac{2\pi l}{v}$ kể từ lần chẵn.

Bây giờ không khó để tính rằng nếu $k$ là số chẵn, thì va chạm thứ $k$ của các quả cầu sẽ xảy ra sau thời gian
$$t_k = \left( \frac{k}{2} - \frac{1}{2} \right) t'' + \frac{k}{2} t' = (3k - 1) \frac{\pi l}{v},
$$
vì tổng cộng giữa các quả cầu sẽ xảy ra $\frac{k}{2}$ va chạm chẵn và $\frac{k}{2}$ va chạm lẻ. Điều này có nghĩa là quả cầu bên phải phải thực hiện $\frac{k}{2} - \frac{1}{2}$ vòng, với vận tốc $2v$ (ở đây chúng ta đã tính đến rằng trước va chạm đầu tiên quả cầu chỉ thực hiện nửa vòng) và $\frac{k}{2}$ vòng quanh điểm $Q_1$, với vận tốc $v$.

Nếu $k$ lẻ, thì trước va chạm thứ $k$ quả cầu bên phải phải thực hiện vận tốc $v$, và $\frac{k-1}{2} + 1 - \frac{1}{2} = \frac{k}{2}$ vòng, với vận tốc $2v$. Vì vậy, từ thời điểm ban đầu đến thời điểm va chạm thứ $k$ trong trường hợp này phải trôi qua thời gian
$$t_k = \frac{k}{2} t'' + \frac{k-1}{2} t' = \frac{(3k-2)\pi l}{v}.$$

Bây giờ hãy tính xem các quả cầu sẽ va chạm bao nhiêu lần trong thời gian $t$. Ta sẽ coi rằng $t > t_1$. Giữa hai va chạm lẻ liên tiếp của các quả cầu trôi qua thời gian $t_0 = t' + t''$. Sẽ xảy ra số va chạm lẻ sau va chạm đầu tiên bằng số lần $t_0$ va chạm trong $t - t_1$:

$$n = \left[ \frac{t - t_1}{t_0} \right]$$

(dấu [ ] có nghĩa là “phần nguyên của số”).

Tổng cộng giữa các quả cầu sẽ xảy ra $n+1$ va chạm lẻ. Trước va chạm lẻ cuối cùng sẽ trôi qua thời gian bằng $\left[ \frac{t - t_1}{t_0} \right] t_0 + t_1$.

Trong thời gian này, giữa các viên bi còn phải xảy ra $n$ va chạm chẵn. Ngoài ra, nếu thời gian còn lại $t - \left( \frac{t - t_1}{t_0} \right] t_0 + t_1$ lớn hơn $t'$, thì sẽ xảy ra thêm một va chạm lẻ. Do đó, trong thời gian $t$ các viên bi sẽ va chạm

$$N = \left[ \frac{t - t_1}{t_0} \right] + 1 + \left[ \frac{t - t_1}{t_0} \right] + \left[ \frac{t - \left[ \frac{t - t_1}{t_0} \right] (t_1 + t_2)}{t_2} \right] = 2 \left[ \frac{vt - \pi l}{6\pi l} \right] + \left[ \frac{vt - \left[ \frac{vt - \pi l}{6\pi l} \right] 6\pi l}{4\pi l} \right] + 1$$

⟦folio 48⟧

Hình 14.

F13. Hai hình trụ giống nhau có pittông được nối bằng một ống (hình 14). Trong các hình trụ có nước. Trên các pittông đặt những cốc hình trụ giống nhau chứa lượng nước bằng nhau. Sau đó, thả vào một trong các cốc một vật có khối lượng $m$, còn vào cốc kia — một vật có khối lượng $M$, các vật này không chìm.

Các đầu pittông và các mực nước trong cốc sẽ cách nhau những khoảng bao nhiêu khi hệ đạt cân bằng? Diện tích đáy các cốc là $S_1$, diện tích các pittông là $S_2$.

Lời giải. Vì các hình trụ được nối bằng ống, nên áp suất của nước trong các hình trụ ở cùng một độ cao phải bằng nhau. Áp suất trong các hình trụ tại độ cao mà mép dưới của pittông bên trái nằm ở đó cũng bằng nhau. Nhưng áp suất trong hình trụ bên trái (hình 14) ở độ cao này bằng $\frac{(M_0 + M)g}{S_2}$, còn áp suất ở độ cao này trong hình trụ bên phải bằng $\frac{(M_0 + m)g}{S_2} + \rho gy$, trong đó $M_0$ là tổng khối lượng của pittông, cốc và nước trong cốc, còn $\rho gy$ là áp suất của cột nước cao $y$. Khi đó, từ điều kiện cân bằng ta được:

$$\frac{(M_0 + M)g}{S_2} = \frac{(M_0 + m)g}{S_2} + \rho gy.$$

Giải phương trình này, ta tìm được rằng

$$y = \frac{M - m}{\rho S_2}.$$

Bây giờ xác định đại lượng $x$. Khi nhúng vật vào cốc, lực ép lên đáy cốc tăng một lượng bằng trọng lượng của vật này. Mặt khác, vì vật không chìm và bản thân không ép lên đáy, nên sự thay đổi lực ép lên đáy là sự thay đổi lực ép của nước lên đáy do mực nước tăng lên. Nếu mực nước trong cốc tăng lên $\Delta x$, thì áp suất của nước lên đáy tăng thêm $\rho g \Delta x$, còn lực ép tăng thêm $\rho g \Delta x S_1$. Do đó, đối với cốc bên trái $\rho g \Delta x S_1 = Mg$, trong đó $\Delta x_1$ là độ thay đổi mực nước trong cốc bên trái: $\Delta x_1 = \frac{M}{\rho S_1}$. Tương tự, ta thấy rằng trong cốc bên phải, khi nhúng vật vào, mực nước tăng lên $\Delta x_2 = \frac{m}{\rho S_1}$. Vì khoảng cách giữa đáy cốc bên trái và đáy cốc bên phải bằng $y$, nên

$$x = y + \Delta x_2 - \Delta x_1 = \frac{(M - m)(S_1 - S_2)}{\rho S_1 S_2}.$$

B14. Hai ống có tiết diện $S_1$ và $S_2$ được nối với nhau và bị bịt bằng các pít-tông có khối lượng $m_1$ và $m_2$ (hình 15). Sau vụ nổ trong không gian giữa các pít-tông, các pít-tông bay ra khỏi ống. Một trong chúng bay ra với vận tốc $v$. Pít-tông thứ hai bay ra với vận tốc nào, nếu: a) các ống được cố định và không thể dịch chuyển, b) các ống không được cố định và tổng khối lượng của chúng bằng $M$? Bỏ qua ma sát của các pít-tông với thành ống.

Lời giải. Trước hết xét trường hợp ống được cố định. Áp suất của khí lên các pít-tông là như nhau, còn các lực áp suất tỉ lệ với diện tích các pít-tông. Vì các lực này tác dụng lên các pít-tông trong cùng một thời gian (ta coi rằng sau khi một trong các pít-tông bay ra khỏi ống, áp suất lên pít-tông thứ hai giảm đột ngột xuống áp suất bên ngoài), nên tỉ số các lực áp suất trung bình tác dụng lên các pít-tông bằng tỉ số diện tích các pít-tông. Điều này cho phép ta tìm tỉ số các xung lượng của các pít-tông sau khi chúng bay ra khỏi ống. Xung lượng ban đầu của các pít-tông bằng không, còn độ biến thiên xung lượng của chúng bằng các lực trung bình nhân

⟦folio 49⟧

Hình 15.

với thời gian nổ. Vì vậy, tỉ số các xung lượng của các pít-tông sau khi chúng bay ra khỏi ống bằng tỉ số các lực áp suất trung bình tác dụng lên các pít-tông, và do đó bằng tỉ số diện tích các pít-tông.

Để xác định, ta sẽ coi rằng pít-tông bên trái bay ra với vận tốc $v$ (hình 15). Ký hiệu vận tốc của pít-tông bên phải là $u$. Khi đó ta có thể viết $\frac{m_1v}{m_2u} = \frac{S_1}{S_2}$; từ đó $u = v\frac{m_1S_2}{m_2S_1}$.

Bây giờ xét trường hợp các ống không được cố định. Khi đó sau vụ nổ chúng sẽ có vận tốc mà ta ký hiệu là $u_1$. So sánh, giống như đã làm đối với các pít-tông, các lực áp suất trung bình tác dụng lên pít-tông bên trái và lên chỗ nối các ống, ta tìm được rằng $u_1 = v\frac{m_1(S_2 - S_1)}{MS_1}$.

Còn đối với các pít-tông, lập luận của ta vẫn đúng cho chúng trong trường hợp này.

B15. Qua thành tủ lạnh, trong một giờ thâm nhập một lượng nhiệt $Q=190$ kilocalo. Nhiệt độ bên trong tủ lạnh là $T_1=+5^\circ\text{C}$, còn trong phòng là $T_2=+20^\circ\text{C}$. Tủ lạnh này tiêu thụ công suất tối thiểu nào từ mạng điện?

Lời giải. Tủ lạnh là một máy nhiệt hoạt động theo chu trình ngược. Nếu một máy nhiệt thuận hấp thụ một lượng $T_2$ và thải ra một lượng nhiệt nhỏ hơn $Q_1$ ở nhiệt độ thấp $T_1$, thực hiện công $A = Q_2-Q_1$, thì máy lạnh hấp thụ một lượng nhiệt $Q'_1$ từ nguồn lạnh ở nhiệt độ $T_1$ và thải ra một lượng nhiệt $Q'_2$ cho nguồn nóng hơn ở nhiệt độ $T_2$. Khi đó, tất nhiên cần cung cấp cho tủ lạnh năng lượng $A'=Q'_2-Q'_1$.

Hệ số có ích của máy nhiệt thuận $\eta = \frac{A}{Q_2} = \frac{Q_2-Q_1}{Q_2}$ không thể vượt quá giá trị $\frac{T_2-T_1}{T_2}$. Hơn nữa, để hiệu suất của máy là lớn nhất, nó phải làm việc theo chu trình ngược. Nếu máy lạnh làm việc theo cùng chu trình như máy thuận, thì $Q'_1 = Q_1$, $Q_2=Q_2$ và $A'=A$. Hiệu suất của máy lạnh trong trường hợp này sẽ bằng $\eta_x = \frac{Q'_1}{A} = \frac{Q_1}{Q_2-Q_1}$. Nhưng trong trường hợp này hiệu suất của máy thuận bằng $\frac{Q_2-Q_1}{Q_2} = \frac{T_2-T_1}{T_2}$, và vì thế $\frac{Q_1}{Q_2} = \frac{T_1}{T_2}$. Dùng hệ thức này, ta thấy rằng hiệu suất của máy lạnh không thể vượt quá giá trị $\frac{Q_1}{Q_2} = \frac{T_1}{T_2}$.

Hiệu suất của tủ lạnh tính theo công thức này (đôi khi được gọi là «hệ số làm lạnh») có thể lớn hơn một. Điều này liên quan đến việc khi thải ra năng lượng $Q_2$, ta không chỉ tiêu thụ năng lượng $A$, mà còn cả năng lượng $Q_1$, nhận được do làm lạnh vật. Còn khi tính hiệu suất của máy, ta chỉ coi năng lượng $A$, tiêu thụ từ mạng điện, là năng lượng đã hao phí, vì chỉ nó là thứ ta phải trả tiền.

⟦folio 51⟧

Hình 16.
ở những tốc độ chuyển động lớn của ô tô, đã không tính đến tổn thất công suất trong các cơ cấu và ma sát lăn của bánh xe với mặt đường. Hãy suy nghĩ xem việc tính đến các yếu tố này sẽ làm thay đổi các phương trình (1) và (2) như thế nào.

F17. Giữa các bản của một tụ điện phẳng bị nối tắt, người ta đặt một bản mang điện tích $q$. Bản này được dịch chuyển song song với chính nó một đoạn $x$ (hình 17). Khi đó điện tích nào đi qua mạch ngoài của tụ điện, nếu khoảng cách giữa các bản của nó bằng $d$?

Để giải bài toán, ta cần biết một bản lớn tích điện đều tạo ra điện trường nào (lớn so với khoảng cách từ bản đến điểm mà ta quan tâm điện trường tại đó). Ta sẽ xuất phát từ điều mà ta đã biết: điện trường trong tụ điện phẳng bằng $\frac{u}{d} = \frac{Q}{C_d} = \frac{Q}{\varepsilon_0 S}$, trong đó $C$ — điện dung của tụ điện, $u$ — hiệu điện thế giữa các bản của nó, $Q$ — điện tích của tụ điện, $S$ — diện tích các bản, $d$ — khoảng cách giữa các bản và $\varepsilon_0$ — hằng số điện. Nhưng điện trường trong tụ điện bằng tổng các điện trường do các bản của nó tạo ra. Điều đó có nghĩa là mỗi bản của tụ điện tạo ra điện trường bằng $\frac{1}{2} \frac{Q}{\varepsilon_0 S}$. Một bản lớn tích điện đều đơn lẻ cũng phải tạo ra điện trường như vậy.

Như vậy, ta đã tìm được rằng bản chuyển động ở giữa tạo ra trường $\frac{1}{2} \frac{q}{\varepsilon_0 S}$. Nhưng trường của hệ điện tích bằng tổng các trường do từng điện tích riêng rẽ tạo ra. Vì thế trường giữa các bản bằng tổng các trường do các bản và bản chuyển động tạo ra. Ta sẽ coi rằng tổng điện tích của các bản kín bằng không *). Khi đó, nếu điện tích của một trong các bản bằng $Q$, thì điện tích của bản thứ hai bằng trừ $Q$, và trường do các bản này tạo ra, cũng giống như trường trong tụ điện có điện tích $Q$, là $E = \frac{Q}{\varepsilon_0 S}$. Ở một phía của các bản, các trường của các bản và của bản chuyển động cùng hướng, ở phía kia — ngược hướng. Vì thế ở bên trái các bản (hình 18) (để xác định, ta coi rằng $q > 0$) trường $E_1 = \frac{1}{2} \frac{q}{\varepsilon_0 S} + \frac{Q}{\varepsilon_0 S} = \frac{q + 2Q}{\varepsilon_0 S}$, còn ở bên phải nó trường

$$E_2 = \frac{Q}{\varepsilon_0 S} - \frac{1}{2} \frac{q}{\varepsilon_0 S} = \frac{2Q - q}{\varepsilon_0 S}.$$

*) Không khó để tổng quát hóa bài toán cho trường hợp tổng điện tích của các bản tụ điện không bằng không. Đáp số trong trường hợp này vẫn giữ nguyên.
