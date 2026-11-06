---
id: 1991-6-dubrovskiy-kommutativnaya-golovolomka-erne-rubika-ffda7f22
issue: kvant_1991_6
year: 1991
number: "6"
title: Câu đố giao hoán của Erne Rubik
authors:
  - Дубровский В. Н.
rubric: igry-i-golovolomki
rubric_sub: Игры и головоломки
page_first: 62
page_last: 65
page_labels: 60, 61, 63
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 40b97f1d55148830606d2bb1346a3569a4914896e7bda3feaa8c0c274fffdb47
prompt_sha256: draft-1
translated_from: content/ru/1991/06/articles/18_dubrovskiy-kommutativnaya-golovolomka-erne-rubika-ffda7f22.md
source_content_sha256: f158af4b8f0376a4fde9bbebf5278a743fc052ab87e25433b89cf23d7fbaca25
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 60⟧

---
running_head:
folio:
---

giao hoán
câu đố
Erne Rubik

Năm ngoái chúng tôi đã giới thiệu với độc giả «Kvant» về “đồng hồ Rubik” (xem trang 4 của bìa số 4). Mặc dù câu đố này đã được cấp bằng sáng chế bởi nhà phát minh nổi tiếng vào năm 1988, nhưng nó vẫn ít được chúng ta biết đến (và có lẽ, nó sẽ vẫn như vậy). Tuy nhiên, chúng tôi đã nhận được những lá thư yêu cầu chúng tôi thực hiện lời hứa đã đưa ra gần một năm trước và cho chúng tôi biết thêm về “chiếc đồng hồ”. Chúng tôi hy vọng rằng câu chuyện của chúng tôi sẽ được tất cả những người yêu thích trò chơi giải đố quan tâm, chứ không chỉ một số ít người sở hữu “đồng hồ Rubik”, đặc biệt vì câu đố này vừa được cấu trúc vừa giải dễ dàng hơn, chẳng hạn như “khối ma thuật”, và do đó, khi đã hiểu cách hoạt động của “đồng hồ”, bạn có thể thử nghĩ ra một thuật toán “ở đầu bút”.

Hình 1 cho thấy đồng hồ Rubik có hai

Ở mỗi bên của vỏ tròn có 9 cửa sổ với các vòng tròn quay số xoay trên đó có vẽ các mũi tên. Có 4 bánh răng nhô ra từ bên hông thân, có thể xoay để di chuyển các mũi tên. Một cơ cấu bánh răng ẩn—“hộp số”—cho phép các bộ mặt số khác nhau được kết nối với vòng quay. “Hộp số” được điều khiển bằng nút bấm; Mỗi bên thùng có 4 cái nhưng thực tế có 4 thanh nhô ra từ 2 bên: nếu ấn vào thanh ở mặt trước thì nó sẽ bật ra từ phía sau và ngược lại. Vấn đề được đặt ra tương tự như đối với “khối lập phương” và nhiều câu đố tương tự khác - khi đã “nhầm lẫn” các chỉ số trên đồng hồ, bạn cần đưa tất cả chúng về trạng thái “chính xác”, cụ thể là đặt chúng ở vị trí 12 giờ.

Tất nhiên, trước khi giải quyết bài toán này, chúng ta phải tìm hiểu cách điều khiển “đồng hồ”, kim nào được kết nối với bánh răng quay khi sử dụng tùy chọn này hoặc tùy chọn khác để ép ngựa (“bánh răng”). Bất cứ ai có câu đố chỉ cần thử tất cả các tùy chọn. Đối với phần còn lại, chúng tôi khuyên bạn nên xem ngay bên trong “đồng hồ”. Trên hình 2 bạn thấy các bánh răng dẫn động (góc) nhô ra khỏi thân xe có 2 mặt số - ở mặt sau và mặt trước; Ngoài ra, các mặt số được ghép nối luôn xoay đồng bộ. Số sáu này có sáu trên nút gần nhất và đến lượt nó, được kết nối với số sáu của ba mặt số phía sau liền kề (trung tâm và hai mặt), nếu nút được nhấn hoặc với vương miện của các mặt số tương ứng ở mặt trước, nếu nút được nhấn. Với những bánh răng này, tùy thuộc vào “bánh răng”, chuyển động quay có thể lan rộng hơn nữa. Rõ ràng, các mặt số lồng vào nhau chỉ có thể quay đồng thời, theo một hướng và cùng tốc độ. Có thể nói, “đồng hồ Rubik” có 14 “bậc tự do”, tương ứng với 4 mặt số góc và thêm 10 mặt số đơn, mỗi mặt số

⟦folio 61⟧

---
running_head:
folio:
---

Hình 2. Phần “Đồng hồ Rubrik” (có mặt phẳng đi qua trục của góc và mặt số trung tâm): a) một cặp mặt số góc được gắn trên bánh răng dẫn động, b) một nút có bánh răng đảo chiều, c) mặt số trung tâm phía trước, d) mặt số trung tâm nghiêng, e) thân khối đố.

về nguyên tắc, trong đó có thể được chuyển độc lập với những cái khác. Vì vậy, số cách sắp xếp mũi tên khác nhau không vượt quá $12^{14} \approx 1,28 \cdot 10^{15}$. Sau này chúng ta sẽ thấy rằng tất cả những khai triển này thực sự có thể đạt được.

Bây giờ hãy xem chúng ta có những lựa chọn nào khi dịch các mũi tên. Mỗi nút có thể ở hai vị trí, do đó có tổng cộng $2^4 = 16$ “bánh răng” trong câu đố. Bất cứ khi nào nhấn các nút, bạn có thể phân biệt hai nhóm mặt số được kết nối với nhau: một nhóm bao gồm các cặp góc cạnh và mặt số bao quanh các nút không được nhấn, nhóm còn lại chỉ được xác định theo cách tương tự nếu bạn nhìn vào “đồng hồ” từ mặt sau. Mỗi cặp mặt số ở góc nhất thiết sẽ thuộc một trong các nhóm, nhưng các mặt số “đơn” không quay có thể không được liên kết với các mặt số khác. Do đó, với vị trí của các nút, nói chung có hai cách để xoay mũi tên - bạn có thể xoay bất kỳ nhóm nào trong hai nhóm. Nhưng trong hai trường hợp - khi tất cả các nút được nhấn hoặc nhả - chỉ có một nhóm được hình thành, do đó tổng số phương pháp xoay là $2 \cdot 16 - 2 = 30$. Tuy nhiên, nếu chúng ta coi các phương pháp xoay có được từ nhau bằng cách xoay câu đố trong mặt phẳng của nó hoặc bằng cách lật nó là tương đương, thì chỉ còn lại 5 phương án tương đương. Tất cả chúng đều được hiển thị trên hình 3. (Kiểm tra xem có 2 cách xoay tương đương với tùy chọn A, 8 cách mỗi cách tương đương với B, C và E và 4 cách tương đương với D.) Nếu bạn quay bánh lái đến $360^\circ/12 = 30^\circ$, thì tùy thuộc vào “bánh răng” được gài, một số mặt số nhất định (trên hình 3 chúng được đặt bằng các mũi tên) sẽ quay theo cùng một góc đó, tức là trong 1 giờ. Chúng tôi sẽ gọi những hoạt động đó là cơ bản; đối với các "bánh răng" hiển thị ở hình 3, chúng ta sẽ ký hiệu chúng tương ứng với A, B, C, D, E. Kết quả của thao tác có thể được viết bằng bảng số 0 và số 1:

$$
\begin{align*}
A &= \begin{pmatrix} 1 & 1 & 1 \\ 1 & 1 & 1 \\ 1 & 1 & 1 \end{pmatrix}, \\
B &= \begin{pmatrix} 0 & 1 & 1 \\ 1 & 1 & 1 \\ 1 & 1 & 1 \end{pmatrix} \\
C &= \begin{pmatrix} 0 & 0 & 0 \\ 1 & 1 & 1 \\ 1 & 1 & 1 \end{pmatrix}
\end{align*}
$$

Hình 3. Năm bánh răng khác nhau cơ bản của “Đồng hồ Rubik” (nhìn từ mặt trước): các nút không nhấn có màu vàng, các nút được nhấn có màu đen, các răng được đánh dấu trên bánh răng quay.

⟦folio 63⟧

---
running_head:
folio:
---

3). Thao tác $t(A-B)$, trong đó $t=0, 1, \dots, 11$, xoay cặp mặt số ở góc phía trên bên trái theo $t$ phần chia. Tương tự, bạn có thể xoay riêng 3 cặp góc còn lại. Các thao tác này rất thuận tiện khi sử dụng khi kết thúc lời giải, vì chúng sẽ không phá hủy những gì đã đạt được.

Bây giờ tôi muốn tìm một thao tác tương tự cho các mặt số bên. Hơn nữa, nó cũng có thể xoay các mặt số ở góc, vì dù sao thì chúng ta cũng sẽ cài đặt chúng sau. Có thể bạn đã tìm thấy đáp số:

$$A-C = \begin{pmatrix} 1 & 1 & 1 \\ 0 & 0 & 0 \\ 0 & 0 & 0 \end{pmatrix}.$$

Thao tác này di chuyển bàn tay trên cùng ở hàng trước (và các bàn tay ở góc liền kề) về phía trước 1 giờ. Rõ ràng là mảnh ghép có thể được xoay sao cho bất kỳ mặt số nào trong số 7 mặt số còn lại đều ở vị trí “mặt trên”.

Vì vậy, chúng ta có 8 thao tác tương đương để lắp mặt số bên và 4 thao tác cho mặt số góc. Hãy thêm hai thao tác nữa cho chúng cho mặt số trung tâm, ví dụ: $A$ và một thao tác “phía sau” tương tự. Điều này dẫn đến 14 phép tính, đủ cho câu đố lời giải (hãy nhớ hệ 14 phương trình!). Bạn có thể làm điều này:

1) bằng thao tác $A$ (chính xác hơn là $tA$, trong đó $t=0, 1, \dots, 11$), chúng ta đặt kim trung tâm của mặt trước ở vị trí 12 giờ;
2) bằng cách sử dụng các thao tác có dạng $t(A-C)$, chúng ta đặt các mũi tên phía trước (mũi tên ở giữa vẫn bất động);
3) lật lại câu đố và lặp lại hai bước đầu tiên;
4) Sử dụng các phép toán có dạng $t(A-B)$ chúng ta đặt các mũi tên góc.

Có thể kết thúc ở đây, nhưng thuật toán của chúng tôi cho phép cải tiến, hay nói đúng hơn là có thể rút ngắn nó. Nếu chúng ta coi chuyển động quay của một trong các bánh răng với một "bánh răng" cố định là một "chuyển động", thì số chuyển động của bước 1 là 1, đối với bước thứ 2 - 2·4=8 (đối với mỗi mặt số đường có 2 chuyển động - $tA$ và - $tC$), đối với bước thứ 3 - 1+8=9 khác, đối với bước thứ 4 - 2·4=8, và tổng cộng - 26. Nhưng sau tất cả, chúng tôi chỉ sử dụng 14 yếu tố hoạt động khác nhau ($A, B, C$ và các câu đố tạo ra từ chúng bằng cách xoay), có nghĩa là bằng cách thay đổi thứ tự của chúng, chúng tôi có thể giảm mọi thứ xuống còn 14 bước. Đây là cách nó được thực hiện:

1) bằng cách sử dụng thao tác có dạng $tC$, chúng ta đặt mũi tên phía trước ở giữa song song với mũi tên phía trước trên cùng; xoay cơ thể $90^\circ$, chúng ta lặp lại quy trình này thêm 3 lần nữa - kết quả là 5 mũi tên (giữa và bên) ở mặt trước sẽ song song;
2) bằng cách sử dụng thao tác dạng $tA$ chúng ta đặt 5 kim này ở vị trí 12 giờ;
3) lật câu đố lại và lặp lại bước 1;
4) bằng cách sử dụng thao tác dạng $tC$ (ở mặt sau!) chúng ta đặt tất cả 5 mũi tên không góc song song với góc trên bên trái và lặp lại điều này thêm 3 lần nữa, xoay câu đố theo $90^\circ$ - kết quả là cả 9 mũi tên sẽ trở nên song song;
5) Sử dụng thao tác $tA$ (một lần nữa đối với câu đố ngược, tức là ở mặt sau), chúng tôi đặt tất cả các kim ở vị trí 12 giờ. Tất cả.

Chúng ta hãy kết thúc bằng một vài nhận xét nữa. Rõ ràng là thuật toán của chúng tôi cho phép chúng tôi có được bất kỳ cách sắp xếp mũi tên nào có thể có trong số $12^{14}$. Trong trường hợp này, chúng tôi sử dụng 14 bước di chuyển, mỗi bước là sự lặp lại (từ 0 đến 11) của một trong 14 thành phần của phép toán $A, B, C$ và các thành phần tương đương. Khi tính đến tính giao hoán, chỉ có $12^{14}$ sự kết hợp khác nhau của các phép toán này. Điều này có nghĩa là tất cả chúng đều khác nhau và chỉ có một sự kết hợp như vậy tương ứng với từng cách sắp xếp mũi tên.

Vì vậy, nếu thao tác chỉ bao gồm 14 thao tác mà chúng tôi đã xác định, chúng tôi có thể nói rằng

Bạn có thể di chuyển từ bất kỳ cách sắp xếp mũi tên nào sang bất kỳ cách sắp xếp nào khác mà không cần
