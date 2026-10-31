---
id: 1977-2-makarenkov-algoritmyi-na-slovah-04512798
issue: kvant_1977_2
year: 1977
number: "2"
title: Thuật toán trong từ
authors:
  - Макаренков Ю. А.
rubric: osnovnye-stati
page_first: 4
page_last: 10
page_labels: 2-8
tag: QXP4
lang: vi
source: kvant_digital
extraction: vision
content_sha256: a3b1af0bb62e627026c8f2cb7ce52ac90938a611ec12e84705c0b8dbf637f73c
prompt_sha256: draft-1
translated_from: content/ru/1977/02/articles/03_makarenkov-algoritmyi-na-slovah-04512798.md
source_content_sha256: d1d61b852643309317db1e02efe764d7bb6d4a0990e920cda2ad5c3556afd56f
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

Thuật toán trong từ

Vào cuối thế kỷ 19 và đầu thế kỷ 20, một đối tượng nghiên cứu mới xuất hiện trong toán học: các chuỗi ký hiệu được lấy từ một tập hợp cố định. Trong tài liệu toán học của chúng ta, cel còn được gọi là các từ gà gô.

Nhà toán học nổi tiếng người Đức David Hilbert vào đầu thế kỷ này đã đề xuất một kế hoạch chứng minh tính nhất quán của toán học bằng cách xây dựng một phép tính (tức là quy tắc biến đổi) cho các từ. Vào đầu những năm ba mươi, người ta phát hiện ra rằng “tất cả toán học” (và thậm chí “tất cả số học”) không thể được tóm tắt trong một phép tính (đây là định lý nổi tiếng của Gödel). Mặc dù hy vọng của Hilbert chưa được thực hiện đầy đủ, nhưng một số nhánh toán học nhất định đã được “định dạng hóa” theo cách này, và mọi nghiên cứu hiện đại về nền tảng của toán học đều bắt đầu bằng một hình thức hóa tương tự. Trong nhiều ngành toán học (ví dụ, ngôn ngữ học toán học và đại số tổng quát) và các ứng dụng của nó (ví dụ: ngôn ngữ lập trình), từ đã trở thành một trong những đối tượng nghiên cứu quan trọng nhất.

Lý thuyết về thuật toán chỉ ra đời vào những năm ba mươi của thế kỷ chúng ta. Kể từ đó, khái niệm thuật toán cũng trở thành một trong những khái niệm quan trọng nhất trong toán học.

Mặc dù từ “thuật toán” chỉ xuất hiện ở phần cuối của bài viết này nhưng tất cả đều nói về từ ngữ và thuật toán làm việc với từ ngữ.

Ví dụ giới thiệu

Chúng ta cố định tam giác đều ABC trên mặt phẳng (Hình 1). Chúng ta biểu thị bằng R phép quay của mặt phẳng 120° ngược chiều kim đồng hồ quanh tâm O của tam giác (Hình 2); Gọi S là sự đối xứng trục của mặt phẳng với trục OB (Hình 3). Mỗi phép biến đổi R, S ánh xạ tam giác ABC lên chính nó. Vì vậy, chúng còn được gọi là sự tự thẳng hàng của tam giác ban đầu. Chúng ta sẽ gọi sự tự kết hợp là R và S sơ cấp.

Chúng ta hãy xem xét tất cả các thành phần có thể có của sự tự sắp xếp cơ bản (“Hình học 7”, đoạn 77). Mỗi thành phần như vậy một lần nữa, rất thuận tiện, sẽ là một loại tự kết hợp.

Giống như các phép tính cộng và nhân các số thông thường, phép tính thành phần của các phép tự kết hợp có tính chất tổ hợp hoặc kết hợp: nếu f, g, h là các phép tự kết hợp thì

$$f \circ g) \circ h = f \circ (g \circ h).$$

(Điều này đúng không chỉ với việc tự sắp xếp của một tam giác mà còn đúng với việc ánh xạ tùy ý bất kỳ tập M nào vào chính nó!) Do đó, trong “dài-

Cơm. 1.

Trong các tác phẩm tự kết hợp cơ bản mới, các dấu ngoặc có thể được đặt theo bất kỳ thứ tự nào, điều đó có nghĩa là chúng hoàn toàn không thể được đặt. Ví dụ,

$$(R \circ S) \circ (R \circ R) = R \circ ((S \circ R) \circ R) = R \circ S \circ R \circ R.$$

Khác với phép cộng và phép nhân các số, phép tính thành phần tự tổ hợp không có bất kỳ

⟦folio 3⟧

Cơm. 2.
vorya, tính chất giao hoán, hay giao hoán. Vì vậy, trong trường hợp này $R \circ S \neq S \circ R$ (xem Hình 4 và 5).

Hãy viết ngẫu nhiên một số thành phần “dài” của các tổ hợp tự cơ bản:
$$X = S \circ S \circ R \circ S \circ R \circ S \circ R \circ S \circ R.$$ (1)
Có thể nói gì về việc tự điều chỉnh $X$?

Dễ dàng chứng minh rằng có sáu sự thẳng hàng của tam giác ban đầu: ánh xạ đồng nhất thức $E$, giữ nguyên từng điểm của mặt phẳng; xoay $120^\circ$ ngược chiều kim đồng hồ; xoay $120^\circ$ theo chiều kim đồng hồ; đối xứng trục với trục $OA, OB, OC$. Từ Hình 4 và 5, rõ ràng là đối xứng trục với trục $OA$ trùng với bố cục $S \circ R$ và đối xứng trục với trục $OC$ là bố cục $R \circ S$.

Bài toán. Hãy tưởng tượng một phép quay $120^\circ$ theo chiều kim đồng hồ như một thành phần của các thao tác tự sắp xếp cơ bản.

Cơm. 3.
Vì vậy, thành phần được viết ngẫu nhiên của chúng tôi (1) là một trong sáu thành phần tự kết hợp được liệt kê. Chính xác thì cái nào?

Tất nhiên, câu hỏi này rất dễ giải quyết thuần túy về mặt hình học: tiếp tục với tam giác ban đầu lần lượt tất cả các cách tự sắp xếp đã chỉ định (đừng quên rằng ký hiệu $f \circ g$ có nghĩa là: đầu tiên $g$ khớp, sau đó là $f!$) và nhìn vào vị trí cuối cùng của tam giác.

Đối với mục đích của chúng tôi, điều quan trọng là câu hỏi tương tự này có thể được giải quyết bằng cách sử dụng một số phép tính đại số.

Thật dễ dàng để kiểm tra điều đó
$$\begin{cases} S \circ R = R \circ R \circ S, \\ R \circ R \circ R = E, \\ S \circ S = E. \end{cases}$$

Hơn nữa, trong bất kỳ thành phần tự kết hợp nào, bản đồ nhận dạng $E$ có thể bị bỏ qua.

Vì chúng ta phải so sánh toàn bộ phép tính, vâng-

Cơm. 4.
Cơm. 5.

⟦folio 4⟧

Hãy coi dấu thành phần $\circ$ như dấu chấm khi nhân: chúng ta sẽ không viết dấu này. Khi đó các đẳng thức (1), (2) sẽ có dạng

$$X = SSRSRSSR,$$

$$\begin{cases} SR = RRS, \\ RRR = E, \\ SS = E. \end{cases}$$

Thành phần $X$ có thể được chuyển đổi như thế này:

$$X = SSRSRSSR =$$

$$= (SS)R(SR)(SR)(SS)R =$$

$$= ER(RRS)(RRS)ER =$$

$$= R(RRS)(RRS)R =$$

$$= (RRR)(SR)R(SR) =$$

$$= E(RRS)R(RRS) =$$

$$= (RRS)R(RRS) = RRS(RRR)S =$$

$$= RRSES = RRSS = RR(SS) =$$

$$= RRE = RR.$$

phép tính kết hợp

Trong phép tính vừa thực hiện, chúng tôi thực sự đã xử lý các từ (xem đoạn đầu tiên của thống kê).

Ở phần trước, các chữ cái $R$ và $S$ có ý nghĩa: chúng biểu thị các đối tượng không cụ thể trong trường — sự tự kết hợp không phải totor. Bây giờ chúng ta sẽ bắt đầu nghiên cứu các chữ cái và từ x trừu tượng - những chữ cái và từ được xây dựng từ chúng không có nghĩa gì cả. (Tuy nhiên, bên dưới chúng ta sẽ quay lại ví dụ ở phần trước.)

Tập hợp các chữ cái ban đầu mà các từ được tạo thành được gọi là bảng chữ cái. Số lượng chữ cái trong một từ được gọi là độ dài của nó.

Giả sử bảng chữ cái ban đầu của chúng ta chỉ bao gồm hai chữ cái: $\{a, b\}$. Sau đó có 4 từ có độ dài 2: $aa, ab, ba, bb$; 8 từ có độ dài 3, v.v. Cũng được phép nói về các từ “một chữ cái”, các từ có độ dài 1; chỉ có hai trong số chúng: $a$ và $b$. Thật thuận tiện khi xem xét rằng cũng có những từ không chứa các chữ cái - một từ trống. Hãy để các từ tương tự như một tập hợp trống. Nó được ký hiệu bằng tiếng Hy Lạp bằng chữ cái $\Lambda$. Tất nhiên, độ dài của nó được coi là bằng 0.

“Quy tắc trò chơi” của chúng ta sẽ như thế này:

$$\alpha \leftrightarrow \beta,$$

(5)

Cơm. 6.

Cơm. 7.

trong đó $\alpha$ và $\beta$ là một số từ. Quy tắc (5) có nghĩa là trong bất kỳ từ nào bạn có thể thay thế từ $\beta$ cùng với $\alpha$ và từ $\alpha$ bằng $\beta$. Các quy tắc có dạng (5) được gọi là quy tắc thay thế.

Hãy xem sự thay thế là một ví dụ:

$$abab \leftrightarrow bb.$$

(6)

Trong các từ $\gamma = abababbabb$ các từ $abab$ xuất hiện ở ba vị trí (Hình 6) hoặc, như người ta nói trong toán học, có ba lần xuất hiện. Từ $bb$ có ​​hai lần xuất hiện trong các từ $\gamma$ (Hình 6). Bằng cách sử dụng thay thế (6) một lần, bạn có thể nhận được 5 từ từ từ $\gamma$ (Hình 7). Đối với từ $abaab$, sự thay thế (6) không được áp dụng: nó không bao gồm bên trái hoặc bên phải của sự thay thế này.

Khi chúng tôi đánh giá $(10+2) \times (8-3)) : (15-3) = (12\cdot 5):12 = 60:12 = 5$, về cơ bản chúng tôi đang áp dụng các thay thế $(10+2) \leftrightarrow 12, (8-3) \leftrightarrow 5, (12\cdot 5) \leftrightarrow 60$, v.v.

Thay thế kiểu

$$\alpha \leftrightarrow \Lambda$$

(7)

trước hết có nghĩa là trong bất kỳ từ nào cùng nhau $\alpha$ bạn có thể “thay thế một từ trống”, tức là chỉ cần loại bỏ các từ đến $\alpha$. Ví dụ, nếu sự thay thế

$$bb \leftrightarrow \Lambda$$

(8)

áp dụng theo cách này cho chữ thứ hai trong từ $\gamma$, bạn sẽ có được từ $abababbaba$. Thứ hai, việc thay thế dạng (7) có nghĩa là trong bất kỳ từ nào giữa hai chữ cái bất kỳ, người ta có thể “chèn” các từ $\alpha$: việc cho rằng một từ trống xuất hiện giữa bất kỳ chữ cái nào là điều tự nhiên. Ngoài ra, ta áp dụng thay thế (7) “từ phải sang trái”, ta có thể

⟦folio 5⟧

tất nhiên, các từ "thuộc tính" $\alpha$ cả ở phía trước và phía sau bất kỳ từ nào. Bằng cách sử dụng thay thế (8), bạn có thể nhận được 6 từ từ cùng một từ $\gamma$ (tại sao?).

Để xác định một “trò chơi”, cần phải sửa một số tập hợp thay thế hữu hạn. Một tập hợp như vậy (cùng với bảng chữ cái) trong logic toán học được gọi là phép tính kết hợp.

Hai từ được gọi là liền kề trong một phép tính kết hợp nhất định nếu một trong số chúng có thể được lấy từ từ kia bằng cách áp dụng bất kỳ sự thay thế nào của phép tính này. Hai từ, $\delta$ và $\eta$, được gọi là tương đương trong phép tính này nếu chúng có thể được “kết nối” bởi một chuỗi các từ liên quan, nghĩa là nếu có các từ $\mu_1$, $\mu_2$, ..., $\mu_n$ nằm trong chuỗi $\delta$, $\mu_1$, $\mu_2$ ..., $\mu_n$, $\eta$ mỗi từ có thể có các từ lân cận. Chúng ta sẽ biểu thị sự tương đương của các từ $\delta$, $\eta$ như sau: $\delta \sim \eta$.

Tất nhiên, các từ liên quan là tương đương.

Ví dụ 1

Xem xét trong bảng chữ cái $\{a, b\}$ phép tính kết hợp với sự thay thế

$$\begin{cases} ba \leftrightarrow aab, \\ aaa \leftrightarrow \Lambda, \\ bb \leftrightarrow \Lambda. \end{cases}$$

Những từ nào tương đương trong phép tính này?

Ví dụ: $aababbaaaba \sim a$, vì trong chuỗi $aababbaaaba$, $aabaaaaaba$, $aabaaba$, $aaaaaba$, $ababa, aaabba, bba, a$ mỗi từ được hoán đổi với các từ lân cận.

Có thể chỉ ra cách để tìm ra hai từ bất kỳ trong bảng chữ cái của chúng ta xem chúng có tương đương hay không?

So sánh đẳng thức (4) với sự thay thế (9) gợi ý phương pháp này. Xét tam giác đều $ABC$ và sự tự thẳng hàng của nó $R, S$ (tr. 2).

Đối với bất kỳ từ nào $\alpha$, chúng tôi biểu thị bằng $T_\alpha$ thành phần của các phần tử tự kết hợp $R$ và $S$, là kết quả của việc thay thế các chữ cái $a$ bằng $R$ và các chữ cái $b$ bằng $S$ trong các từ $\alpha$. Ví dụ: $T_{ba} = SR$, $T_{abaa} = RSR$.

Vì trong thành phần của các phép tự kết hợp, ánh xạ hiệu quả $E$ cũng không cần phải được viết nên chúng ta đặt $T_\Lambda = E$ theo định nghĩa.

Mỗi thành phần của các phần tử tự kết hợp rõ ràng có thể được viết dưới dạng $T_\alpha$, trong đó $\alpha$ là một từ nào đó.

Như vậy, chúng ta đã thu được một số sự tương ứng giữa tập hợp tất cả các từ trong bảng chữ cái $\{a, b\}$ và tập hợp các từ tự kết hợp. Sự tương ứng này không nghịch đảo: các từ khác nhau có thể tương ứng với cùng một sự tự kết hợp. Ví dụ: $T_{ba} = SR = RRS = T_{aab}$ (xem Hình 5 và 8).

Phương pháp mà chúng tôi muốn đề xuất để thiết lập sự tương đương của các từ tùy ý dựa trên ba “phê bình”:

(A) Vế trái và phải của mỗi phép thay thế phép tính tương ứng với sự tự kết hợp của riêng tôi:

$$\begin{cases} T_{ba} = T_{aab}, \\ T_{aaa} = T_\Lambda, \\ T_{bb} = T_\Lambda. \end{cases}$$

Cơm. 8.

⟦folio 6⟧

(B) Bất kỳ từ nào trong phép tính của chúng ta đều tương đương với một trong các từ sau: Λ, a, b, aa, ab, aab.
(B) Bất kỳ hai từ nào trong số các từ Λ, a, b, aa, ab, aab đều tương ứng với các cách tự sắp xếp khác nhau.
Trước hết, chúng ta hãy chứng minh tính đúng đắn của các phát biểu (A) - (B).
Tuyên bố (A) theo sau đẳng thức (4). Câu (B) được xác minh về mặt hình học: chúng ta hãy hành động trên tam giác ban đầu với sự tự thẳng hàng $T_\Lambda, T_a, T_b, T_{aa}, T_{ab}, T_{aab}$ và xem rằng thu được các kết quả khác nhau (xem Hình 1-3, 9, 4 và 8).
(B) chứng minh điều sau. Đặt $\alpha$ là một từ tùy ý. Sau khi áp dụng phép thay thế đầu tiên (9) cho nó với số lần cần thiết, chúng ta sẽ “lái” tất cả $a$ về đầu. Như vậy từ $\alpha$ tương đương với một từ có dạng
$$\beta = \underbrace{aa \dots abb \dots b}_{k}$$
$(k \geqslant 0, l \geqslant 0)$. Nếu $l$ chẵn, thì bằng cách áp dụng lần thay thế thứ ba (9) cho $\beta$ số lần cần thiết, chúng ta có thể “xóa” tất cả $b$ khỏi $\beta$. Trong trường hợp này, $\beta$ và do đó $\alpha$, tương đương với một từ có dạng
$$\gamma' = \underbrace{aa \dots a}_{k}$$
Tùy theo số dư khi chia số $k$ cho 3 (bằng 0, 1 hoặc 2)

từ $\gamma'$ sử dụng từ thay thế thứ hai (9) được chuyển thành một trong các từ $\Lambda, a, aa$. Nếu $l$ lẻ thì $\beta$ và $\alpha$ tương đương với một từ có dạng
$$\gamma'' = \underbrace{aa \dots ab}_{k}.$$
Tùy theo phần còn lại của từ $\gamma''$ được dịch thành một trong các từ $b, ab, aab$.
Từ (A), rõ ràng các từ liền kề tương ứng với cùng một sự tự kết hợp. Điều này có nghĩa là điều này cũng đúng với các từ tương đương:
$$\alpha \sim \beta \Rightarrow T_\alpha = T_\beta.$$ (10)
Từ (B), (B) và (10) ta có điều ngược lại:
$$T_\alpha = T_\beta \Rightarrow \alpha \sim \beta.$$ (11)
Hãy để $T_\alpha = T_\beta$. Theo (B), mỗi từ $\alpha, \beta$ tương đương với một trong các từ $\Lambda, a, b, aa, ab, aab$. Hãy đặt $\alpha \sim \alpha', \beta \sim \beta'$, ở đâu $\alpha', \beta' \in \{\Lambda, a, b, aa, ab, aab\}$. Từ (10) $T_\alpha' = T_\alpha$ và $T_\beta' = T_\beta$. Tính đến $T_\alpha = T_\beta$ chúng ta nhận được $T_\alpha' = T_\beta'$. Sau đó từ (B) $\alpha' = \beta'$. Vì vậy, $\alpha \sim \beta$.
Từ (10) và (11) suy ra
$$\alpha \sim \beta \Leftrightarrow T_\alpha = T_\beta.$$ (12)
Hãy nhìn lại chứng minh của mệnh đề (12) và bạn sẽ thấy rằng chứng minh này chỉ dựa trên (A) - (B). Khi (A) - (B) đã được thiết lập, không cần tham khảo thêm phép tính thay thế.

⟦folio 7⟧

Bây giờ, sau khi thiết lập (12), cuối cùng chúng tôi cũng có thể đưa ra phương pháp đã hứa: đường dẫn phải được kiểm tra tính tương đương của các từ $\alpha$ và $\beta$; hành động trên tam giác $ABC$ với sự tự căn chỉnh $T_{\alpha}$ và $T_{\beta}$; nếu bạn nhận được kết quả tương tự thì $T_{\alpha} = T_{\beta}$ và do đó, theo (12) $\alpha$ và $\beta$ là tương đương; ngược lại, một lần nữa do (12), chúng không tương đương.

Ví dụ 2

Bây giờ chúng ta hãy xem xét phép tính kết hợp với các phép thay thế trong cùng một bảng chữ cái $\{a, b\}$:

$$\begin{cases} ab \leftrightarrow ba, \\ aa \leftrightarrow \Lambda, \\ bb \leftrightarrow \Lambda. \end{cases}$$

Đối với phép tính này, thật dễ dàng để chỉ ra hai cách khai báo sự tương đương.

Cách đầu tiên

Phương pháp này tương tự như phương pháp trong ví dụ 1. Chúng tôi sửa một số hình chữ nhật $ABCD$ trên mặt phẳng (Hình 10). Ta biểu thị bằng $S_1$ sự đối xứng trục của mặt phẳng có trục $OM$ đi qua tâm đối xứng của hình chữ nhật $O$ song song với cạnh $AB$ (Hình 11); thông qua $S_2$ chúng ta biểu thị sự đối xứng trục với trục $ON$ (Hình 12). Cả hai sự đối xứng này đều là sự tự sắp xếp của hình chữ nhật ban đầu. Chúng ta sẽ gọi sự tự kết hợp $S_1$ và $S_2$ là cơ bản.

Như trong Ví dụ 1, chúng ta sẽ xem xét tất cả các thành phần có thể có của các tự tổ hợp cơ bản.

Lần này chúng ta sẽ có được khả năng tự căn chỉnh $T_{\alpha}$ từ từ $\alpha$ bằng cách thay thế chữ cái $a$ bằng $S_1$, chữ cái $b$ bằng $S_2$.

Một lần nữa, ba “trụ cột” được hoàn thành:

(A) Vế trái và phải của mỗi phép thay thế phép tính tương ứng với việc áp dụng (13) phép thay thế (13), tìm các từ eton tương đương với các từ $\alpha$ và $\beta$ (cách thực hiện điều này được mô tả trong chứng minh (B) từ Ví dụ 1); nếu $\alpha$ và $\beta$ hóa ra tương đương với cùng một từ eton, thì $\alpha \sim \beta$; nếu không thì $\alpha$ và $\beta$ không tương đương.

Trong ngôn ngữ của bài viết “Bất biến” của A. Tolygo («Kvant», 1976, số 12), phương pháp thứ hai có thể được phát biểu như sau: đối với bất kỳ từ nào

$$\begin{cases} T_{ab} = T_{ba}, \\ T_{aa} = T_{\Lambda}, \\ T_{bb} = T_{\Lambda}. \end{cases}$$

(B) Bất kỳ từ nào trong phép tính của chúng tôi đều tương đương với một trong bốn từ: $\Lambda$, $a$, $b$, $ab$.

(B) Chúng tôi yêu thích hai trong số các từ $\Lambda$, $a$, $b$, $ab$ tương ứng với các cách tự sắp xếp khác nhau.

Từ (A) – (B), như trên ta suy ra

$$\alpha \sim \beta \iff T_{\alpha} = T_{\beta}.$$

Điều này có nghĩa là sự tương đương của các từ tùy ý $\alpha$, $\beta$ được thiết lập như trong Ví dụ 1: tác động lên hình chữ nhật $ABCD$ bằng các phép biến đổi $T_{\alpha}$ và $T_{\beta}$; nếu chúng tôi nhận được kết quả tương tự thì $\alpha \sim \beta$; nếu không thì $\alpha$ và $\beta$ không tương đương.

Cách thứ hai

Xem xét kỹ hơn các từ thay thế (13), bạn có thể nhận thấy rằng chúng lưu lại một trong các từ tráng men $\Lambda$, $a$, $b$, $ab$.

Vì đối với hai từ tráng men bất kỳ, tính chẵn lẻ của chữ cái số $a$ hoặc tính chẵn lẻ của chữ cái số $b$ đều khác nhau (xem Hình 13), nên các từ tráng men không tương đương theo cặp.

Do đó, sự tương đương của các từ tùy ý $\alpha$, $\beta$ rất đơn giản: áp dụng thay thế (13), tìm các từ eton tương đương với các từ $\alpha$ và $\beta$ (cách thực hiện được mô tả trong chứng minh (B) từ Ví dụ 1); nếu $\alpha$ và $\beta$ hóa ra tương đương với cùng một từ eton, thì $\alpha \sim \beta$; nếu không thì $\alpha$ và $\beta$ không tương đương.

Trong ngôn ngữ của bài viết “Bất biến” của A. Tolygo («Kvant», 1976, số 12), phương pháp thứ hai có thể được phát biểu như sau: đối với bất kỳ từ nào

⟦folio 8⟧

α chúng ta hãy đặt

$$f_1(\alpha) = \begin{cases}
0, если число букв a в слова α четно,
1 в противном случае;
\end{cases}$$

$$f_2(\alpha) = \begin{cases}
0, если число букв b в слова α четно,
1 в противном случае.
\end{cases}$$

Các hàm $f_1, f_2$ tạo thành một hệ thống bất biến hoàn chỉnh. Vì vậy, sự tương đương của các từ tùy ý α, β được nhận biết như sau: đếm giá trị của các hàm $f_1$ và $f_2$ trên α và β; nếu bằng

$$\begin{cases}
f_1(\alpha) = f_1(\beta),
f_2(\alpha) = f_2(\beta)
\end{cases}$$

sẽ được ứng nghiệm, α~β; mặt khác α và β không tương đương.

Hãy thử giải bài toán từ Ví dụ 1 theo cách thứ hai, tức là sử dụng bất biến. Điều này khó hơn nhiều so với ví dụ 2.

Thuật toán không phải lúc nào cũng tồn tại

Bài toán tìm cách thiết lập sự tương đương của các từ trong phép tính kết hợp được nhà toán học người Na Uy Thue đặt ra vào năm 1914. Bản thân Thue cũng đã chỉ ra các phương pháp tính toán kết hợp thuộc một loại hình đặc biệt nào đó.

Vào năm 1946 và 1947, nhà toán học Liên Xô Andrei Andreevich Markov và nhà toán học người Mỹ Emil Post đã độc lập xây dựng phép tính kết hợp mà cũng không có phương pháp nào.

Cho đến nay, ở nước ta chúng ta vẫn tránh dùng từ “thuật toán”. Trong toán học, một thuật toán được gọi là biểu diễn chính xác cho lời giải của một số lớp bài toán. Cụm từ này trong mọi trường hợp không thể được coi là một khái niệm cụ thể của thuật toán - xét cho cùng, các từ “biểu diễn chính xác” không phải là một loại thuật ngữ toán học nào đó và không có ý nghĩa rõ ràng.

Cho đến khi các nhà toán học bắt đầu xây dựng các thuật toán cụ thể, họ vẫn thực hiện mô tả lỏng lẻo về khái niệm này ở trên. Nhưng trong những thập kỷ đầu tiên của thế kỷ 20, nhiều lớp bài toán đã tích lũy mà không tìm được thuật toán nào. Các nhà toán học bắt đầu nghi ngờ rằng đó không phải là sự thiếu khéo léo. Họ nảy ra một ý nghĩ: điều gì sẽ xảy ra nếu đối với lớp này hay lớp kia bài toán thuật toán không hoạt động? Điều gì sẽ xảy ra nếu nó đơn giản là không tồn tại?

Để chứng minh rằng một thuật toán không tồn tại, một khái niệm mơ hồ không còn đủ nữa; khái niệm này cần phải được làm rõ. Việc làm rõ này được thực hiện vào giữa thế kỷ 30 của chúng ta *).

Chỉ sau khi làm rõ điều này, về nguyên tắc mới có thể chứng minh được sự không tồn tại của thuật toán. Bằng chứng đầu tiên thuộc loại này được đưa ra bởi nhà logic học người Mỹ Alonzo Church.

Phép tính do A. A. Markov và E. Post xây dựng rất cồng kềnh: chúng chứa hàng trăm phép thay thế. Các nhà toán học bắt đầu tìm kiếm những ví dụ đơn giản hơn về phép tính kết hợp với một bài toán tương đương không thể giải được. Grigory Samuilovich Tseytin đưa rekord theo hướng này: ông đã xây dựng một phép tính như vậy chỉ với 7 lần thay thế **).

Tseitin đã chứng minh rằng đối với phép tính trong bảng chữ cái {a, b, c, d, e} bằng cách thay thế

$$\begin{cases}
ac \leftrightarrow ca,
ad \leftrightarrow da,
bc \leftrightarrow cb,
bd \leftrightarrow db,
eca \leftrightarrow ae,
edb \leftrightarrow be,
abac \leftrightarrow abace
\end{cases}$$

Không có thuật toán để nhận biết sự tương đương của từ.

Điều thú vị là phép tính có một bài toán tương đương có thể giải được và phép tính có bài toán tương đương không giải được “nằm cạnh nhau”. Trong tài liệu quảng cáo của B. A. Trakhtenbrot “Thuật toán và máy lời giải bài toán” (Moscow, Fizmatgiz, 1960) và phép tính Tseytin đã được đưa ra *)

*) Bạn có thể đọc về điều này trong §§ 7, 13 trong tập tài liệu “Thuật toán và máy tính tự động” của B. A. Trakhtenbrot (Moscow, “Đài phát thanh Liên Xô”, 1974) và trên trang. 9-13 của cuốn sách “Máy Tybioring và các hàm đệ quy” (Moscow, “Mir”, 1972).

**) Công thức của ông đã được sử dụng và trình bày bởi Yury Vladimirovich Matiyasevich, người đã xây dựng một phép tính như vậy bằng cách sử dụng ba phép thay thế. Thật không may, chúng quá dài để đưa vào đây.
