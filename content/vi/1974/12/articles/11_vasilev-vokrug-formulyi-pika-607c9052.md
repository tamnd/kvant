---
id: 1974-12-vasilev-vokrug-formulyi-pika-607c9052
issue: kvant_1974_12
year: 1974
number: "12"
title: Xung quanh công thức Pick
authors:
  - Васильев Н. Б.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 41
page_last: 45
page_labels: 39-43
tag: 11SQ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: ca080c95f7dab47768eeb473b99ea82779e9fd271380bfd030e60a424f6e57a3
prompt_sha256: draft-1
translated_from: content/ru/1974/12/articles/11_vasilev-vokrug-formulyi-pika-607c9052.md
source_content_sha256: a0f19f83239ff3f9b463358045aeac9a1b4bcacb22471dc37f727ed3f3144ad6
translation_model: draft
translation_run: vi-draft-2026-11-03
translation_quality: draft
---

⟦folio 39⟧

Để ước tính diện tích của một đa giác được vẽ trên giấy ca rô, chỉ cần đếm xem có bao nhiêu ô bao phủ đa giác này (chúng ta lấy diện tích của một ô làm một). Chính xác hơn, nếu $S$ là diện tích của đa giác, $N_1$ là số ô nằm hoàn toàn bên trong đa giác và $N_2$ là số ô có ít nhất một điểm chung với phần bên trong của đa giác, thì $N_1 \leqslant S \leqslant N_2$. (Thực tế này có thể được sử dụng để đưa ra định nghĩa chính xác về diện tích của đa giác và các hàm số khác.)

Dưới đây chúng ta sẽ chỉ xem xét các đa giác như vậy, tất cả các đỉnh của chúng nằm ở các nút của tờ giấy ca rô - tại các điểm mà các đường lưới giao nhau. Hóa ra đối với những đa giác như vậy, bạn có thể chỉ định một công thức đơn giản:

$$S = \frac{r}{2} + i - 1,$$

trong đó $S$ là diện tích, $r$ là số nút nằm trên ranh giới của đa giác (nghĩa là ở các cạnh và ở các đỉnh), $i$ là số nút nằm hoàn toàn bên trong đa giác.

Công thức này đôi khi được gọi là “công thức Pick” - theo tên nhà toán học đã phát hiện ra nó vào năm 1899. (Tuy nhiên, chúng tôi không thể chắc chắn rằng chưa có ai nghĩ ra công thức tự nhiên này, công thức này cho phép đưa ra một số cách chứng minh khác nhau.)

⟦folio 40⟧

ke 1, các bạn sẽ thấy diện tích luôn bằng số “nhận” - một số có dạng $m/2$, trong đó $m$ là số nguyên.

Hãy gọi một tam giác là đơn giản nếu không có nút lưới nào bên trong hoặc trên các cạnh của nó, ngoại trừ các đỉnh của nó. (Tên này được chọn vì bất kỳ tam giác nào khác cũng có thể được tạo từ những tam giác đơn giản; đây là một trong những nhận định mà chúng ta gặp dưới đây.) Lưu ý rằng tất cả các tam giác đơn giản trên hình 1 đều có diện tích 1/2. Chúng ta sẽ thấy rằng điều này không phải là ngẫu nhiên.

Trong lời giải bài toán M226, xuất bản năm «Kvant», 1974, số 6, người đọc được yêu cầu suy nghĩ về một vấn đề như vậy. Ba con châu chấu (tại thời điểm đi tiểu) tại thời điểm ban đầu ngồi ở ba đỉnh của một ô, và sau đó bắt đầu “nhảy vọt”: mỗi con có thể nhảy qua một vùng của hai con kia, sau đó nó kết thúc ở một điểm mới tương đối đối xứng (hình 2; rõ ràng là sau bất kỳ số lần nhảy nào, châu chấu sẽ đến các nút của ô). Châu chấu có thể kết thúc theo những dự đoán nào sau một vài cú đâm?

Chúng ta gọi một tam giác là phân phối nếu ba con châu chấu có thể xuất hiện đồng thời ở các đỉnh của nó, ban đầu chúng ở ba đỉnh của một ô; chúng ta sẽ gọi bước nhảy là một phép biến đổi của một tam giác, bao gồm thực tế là một trong các đỉnh đi đến một điểm đối xứng với bất kỳ đỉnh nào trong hai đỉnh còn lại (hai đỉnh này vẫn giữ nguyên).

Định lý 1. Ba tính chất sau của tam giác có đỉnh tại nút giấy kẻ ô là tương đương với nhau:

1) một hình tam giác có diện tích 1/2;
2) hình tam giác rất đơn giản;
3) tam giác có thể phân phối được.

Bạn có thể xác minh tính đúng đắn của định lý này bằng cách chứng minh định lý sau: những ai có chứng minh có gợi ý ở cuối câu sẽ được đánh dấu. Phần còn lại gần như rất tốt nếu bạn chứng minh chúng theo thứ tự sau:

$$3 \Rightarrow 4 \quad 1 \Rightarrow 2 \quad 10$$

$$5 \Rightarrow 6 \Rightarrow 7 \Rightarrow 8 \Rightarrow 9 \Rightarrow 11 \Rightarrow 12$$

1. Diện tích hình tam giác không thay đổi khi nhảy.
2. Bất kỳ hình tam giác nào có sẵn đều có diện tích 1/2.
3*. Nếu bạn hoàn thành một hình tam giác đơn giản $ABC$ thành hình bình hành $ABCD$, thì sẽ không có nút nào (không tính các đỉnh) bên trong hoặc trên các cạnh của hình bình hành này.
4*. Từ một hình tam giác đơn giản, khi nhảy nó biến thành một hình tam giác đơn giản.
5*. Một tam giác đơn giản có một trong các góc - tù hoặc thẳng (và trường hợp thứ hai chỉ có thể xảy ra đối với một tam giác có ba đỉnh thuộc về một ô; chúng ta sẽ gọi một tam giác đơn giản như vậy có các cạnh 1, 1, $\sqrt{2}$ tối thiểu).
6. Từ bất kỳ tam giác không tối thiểu đơn giản nào, bạn có thể chỉ cần nhảy một lần là có được một tam giác có hầu hết các cạnh nhỏ hơn hầu hết các cạnh của tam giác ban đầu.
7*. Bất kỳ hình tam giác đơn giản nào cũng có thể được chuyển đổi thành hình tam giác tối thiểu với số bước nhảy hữu hạn.
8. Bất kỳ hình tam giác đơn giản nào cũng có thể truy cập được.
9. Bất kỳ hình tam giác đơn giản nào cũng có diện tích 1/2.
10*. Bất kỳ hình tam giác nào cũng có thể được cắt thành những hình đơn giản.
11. Diện tích của bất kỳ hình tam giác nào đều bằng $m/2$ và bất cứ khi nào nó được cắt thành số nguyên tố, số của chúng sẽ bằng $m$.

⟦folio 41⟧

12. Bất kỳ tam giác nào có diện tích 1/2 đều đơn giản.
Rõ ràng là Tuyên bố 2, 8 và 12 hàm ý Định lý 1.
Chứng minh thêm một số tính chất của tam giác.
13. Đối với hai nút mạng bất kỳ A và B, trên đoạn thẳng giữa chúng không có nút nào khác, tồn tại nút C sao cho tam giác ABC là đơn.
14. Nút C ở bài toán trước luôn có thể được chọn sao cho góc ACB tù hoặc vuông.
15. Một hình bình hành khi và chỉ khi chúng ta tạo ra một mạng bao gồm tất cả các nút của tờ giấy ca rô (xem bài viết của A. A. Egorov, trang 26) khi mỗi hình tam giác mà đường chéo chia nó thành đơn giản.
Tài sản tương tự có thể được hình thành như thế này.
16. Tam giác ABC đơn khi và chỉ khi tất cả các tam giác có thể có được từ ABC bằng các phép dịch song song đưa nút A đến các nút mạng khác nhau không chồng lên nhau (hình 3).

Bây giờ chúng ta hãy quay lại bài toán về ba người thợ rèn. Hãy để những người thợ rèn ở vị trí ban đầu chiếm một số tam giác tối thiểu cụ thể (và không tùy ý) - trong công thức ban đầu của bài toán đây chính xác là những gì chúng tôi giả định. Vì mỗi con châu chấu sẽ bị trộn lẫn khi nhảy qua một số ô chẵn theo chiều ngang và chiều dọc, nên nó nhất thiết sẽ kết thúc ở một nút “bên trong nó” của một mạng có kích thước ô là 2x2. Vào hình 4, ba trong số bốn "mạng con" tạo nên toàn bộ mạng có màu khác nhau (mỗi con châu chấu nhảy vào các nút của nó

Màu sắc) và màu thứ tư có cùng màu với đường lưới.

Theo Định lý 1, người thợ rèn có thể đồng thời đánh vào các đỉnh của một hình tam giác đơn giản.

Điều này dẫn đến một tính chất thú vị khác của những hình tam giác này.

17. Nếu mạng - các nút của giấy ca rô - được chia thành bốn mạng con với các ô 2x2 (hình 4), thì các đỉnh của một tam giác đơn giản nhất thiết sẽ rơi vào ba mạng con khác nhau (cả ba mạng đều có màu khác nhau).

Bây giờ không khó để chứng minh hai khẳng định sau đây, cho kết quả đáp số đến bài toán về ba con châu chấu (trong trường hợp tam giác ban đầu cố định; hình 4).

18. Ba thợ rèn có thể đồng thời đánh những điểm đó và chỉ những rãnh điểm đóng vai trò là các đỉnh của một tam giác đơn giản và có cùng màu với các đỉnh tương ứng của tam giác ban đầu.

19. Hai thợ rèn có thể đồng thời đánh những nút đó và chỉ những nút có màu tương ứng, trên đoạn mà giữa đó không có nút nào khác.

Tam giác đa giác
Chúng tôi đã nghiên cứu chi tiết một dạng đa giác cụ thể trên giấy ca rô, trong công thức Pick tương ứng với các giá trị i = 0, r = 3, S = 1/2. Nhưng từ trường hợp cụ thể này, bạn có thể đi thẳng đến trường hợp tổng quát nhất, sử dụng định lý về độ phân giải của đa giác tùy ý thành một hình tam giác (không cần giấy ca rô nữa).

⟦folio 42⟧

Hình 5.

Hãy để có một số được đưa ra trên máy bay
cái nào (không nhất thiết phải lồi)
đa giác và một số hữu hạn
tập hợp $K$ điểm nằm bên trong
đa giác và trên ranh giới của nó
(và tất cả các đỉnh của đa giác đều thuộc tập hợp $K$).
Tam giác với các đỉnh $K$ là một phân vùng của một đa giác nhất định thành các tam giác có các đỉnh trong tập hợp $K$ cũng sao cho mỗi điểm từ $K$ đóng vai trò là một đỉnh của mỗi tam giác tam giác mà điểm này thuộc về (nghĩa là các điểm từ $K$ không rơi vào bên trong hoặc trên các cạnh của hình tam giác, xem hình 5).

Định lý 2. a) Mọi $n$-giác đều có thể cắt các đường chéo thành hình tam giác và số hình tam giác sẽ bằng $n-2$.
(Phân vùng này là một tam giác có các đỉnh ở các đỉnh của $n$-giác.)

6) Giả sử có $r$ điểm trên đường viền của đa giác (bao gồm tất cả các đỉnh) và một điểm $i$ khác bên trong. Sau đó, có một tam giác với các đỉnh tại các điểm lệch nhau và số lượng tam giác cực đại sẽ bằng $r+2i-2$.

Tất nhiên, a) là trường hợp đặc biệt, 6), khi $r=n$, $i=0$. Chúng ta sẽ lại chia nhỏ cách chứng minh định lý này thành một loạt các phát biểu đơn giản.

20*. Từ đỉnh của góc lớn nhất của $n$-giác ($n>3$), luôn có thể vẽ một đường chéo nằm hoàn toàn bên trong đa giác.

21. Nếu $n$-giác được cắt chéo thành $p$-giác và $q$-giác thì $n=p+q-2$.

22. Bất kỳ $n$-giác nào cũng có thể được cắt theo đường chéo thành hình tam giác $n-2$.

23. Tổng các góc của $n$-giác là $180^\circ \cdot (n-2)$.

24. Đối với bất kỳ tam giác nào, bên trong và trên đường viền có một số điểm lệch nhau (bao gồm cả ba đỉnh của nó), sẽ có một tam giác với các đỉnh tại các điểm lệch nhau.

25. Điều này cũng đúng với mọi $n$-gon.

26. Số lượng tam giác tam giác là $r+2i-2$, trong đó $i$ và $r$ là số điểm bù của phần tương ứng bên trong và trên đường viền của đa giác.

Điều này hàm ý Định lý 2.

27. Suy ra công thức Pick từ Định lý 1 và 2: $S=r/2+i-1$.

Một kỹ thuật thuận tiện để sử dụng trong chứng minh mệnh đề 26—đếm tổng các góc—cũng giúp ích cho lời giải các tổ hợp khác bài toán trong hình học, đặc biệt là về phân vùng của một đa giác. Hãy cho thêm hai ví dụ nữa.

Chúng tôi gọi phân vùng của $n$-giác thành nhiều đa giác là đúng nếu mỗi đỉnh của một trong các đa giác của phân vùng đóng vai trò là đỉnh của tất cả các đa giác khác của phân vùng mà nó thuộc về.

28. Nếu từ các đỉnh của $k$-giác trên đó một $n$-giác được chia một cách thông thường.

⟦folio 43⟧

Hình 7

nick, $i$ đỉnh nằm bên trong và $r$ đỉnh nằm trên biên của $n$-giác thì số lượng $k$-giác là

$$m = \frac{r + 2i - 2}{k - 2}.$$

29 (Biến thể của “Định lý Euler”). Nếu $N_0$ điểm trong mặt phẳng và $N_1$ đoạn có điểm cuối tại các điểm này tạo thành một đa giác, thường được chia thành $N_2$ đa giác, thì (hình 6) $N_2 - N_1 + N_0 = 1$.

Một số bài toán

Ứng dụng chính của công thức Pick không phải là tính diện tích của các đa giác cụ thể mà là với nhiều bài toán và định lý khác nhau về các đường đứt nét trên giấy ca rô.

30. Giả sử tỷ lệ diện tích của một đa giác với bình phương của một trong các cạnh của nó là vô tỷ (ví dụ, trường hợp này xảy ra với một hình tam giác đều). Chứng minh rằng một đa giác giống nhau không thể đặt được trên giấy ca-rô sao cho các đỉnh nằm tại các nút.

31. Cho $A$ và $B$ là hai nút giấy ca rô, trong đó nút thứ hai nằm ở $p$ ô ở bên phải và cao hơn nút đầu tiên $q$ (tức là khoảng cách giữa các nút là $\sqrt{p^2 + q^2}$). Khoảng cách đến đường $AB$ từ nút gần nó nhất không nằm trên đường này là bao nhiêu?

32. Vua cờ đi vòng quanh bàn cờ $8 \times 8$ các ô vuông, đánh vào mỗi ô đúng một lần và với nước đi cuối cùng, họ quay trở lại ô ban đầu. Đường đứt đoạn nối liền các trung tâm ruộng vua đi qua không có điểm tự giao.

Hình 8.

a) Độ dài lớn nhất mà nó có thể có là bao nhiêu?

6) Đường đứt nét này có thể bao quanh khu vực nào? (Cạnh của ô là 1.)

Bài toán a) đã hiểu «Kvant» Số 5 của năm nay (trang 52) - nó có số M220 trong “Sách Vấn đề” «Kvant». Ở đây chúng tôi sẽ đưa ra một lời giải khác. Nhưng hãy bắt đầu với bài toán 6). Từ công thức của Peak, ngay lập tức diện tích được giới hạn bởi đường đứt nét bằng $64/2 - 1 = 31$ (tâm của 64 trường đóng vai trò là các nút của tờ giấy ca rô; theo điều kiện, tất cả chúng đều nằm trên ranh giới của đa giác). Hãy chuyển sang bài toán a). Tại hình 7 có một ví dụ về đường đi của vua trong đó 36 trong số 64 nước đi dài $\sqrt{2}$ (hướng theo đường chéo). Hãy chứng minh rằng không thể có nhiều hơn 36 nước đi như vậy.

Trên mỗi đoạn có độ dài $\sqrt{2}$ nằm trong đường đi của vua, chúng ta dựng một hình vuông $1 \times 1$, giống như trên một đường chéo. Tuy nhiên, đáy của hình vuông này nằm ngoài đa giác giới hạn đường đi của vua. Nhưng tổng diện tích chiếm giữ của các vị trí đó không vượt quá 49 - 31 = 18, vì chúng đều vượt ra ngoài hình vuông $7 \times 7$ của tờ giấy ca rô. Điều này có nghĩa là số lần di chuyển chéo không vượt quá 36.

Vì vậy, đáp số đến bài toán 32:

a) $28 + 36\sqrt{2}$; 6) 31.

33. Cần kiểm tra dọc theo các đường kẻ của lưới một đường gãy khép kín, không tự giao nhau đi qua tất cả các nút của tờ giấy ca rô nằm bên trong các ô đường thẳng $p \times q$.

a) Điều này có thể xảy ra với $p$ và $q$ nào?

b) Đường đứt nét này sẽ có độ dài bao nhiêu?

b) Nó sẽ bao quanh khu vực nào? (hình8).
