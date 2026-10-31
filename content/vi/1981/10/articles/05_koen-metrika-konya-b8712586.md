---
id: 1981-10-koen-metrika-konya-b8712586
issue: kvant_1981_10
year: 1981
number: "10"
title: Chỉ số hiệp sĩ
authors:
  - Коэн Д.
rubric: osnovnye-stati
page_first: 15
page_last: 18
page_labels: 13-16
tag: ZC9G
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 56486c288a9124a421226cc96dc4abaabf4ed729d4d8e89d55a79e1ac0b0a79c
prompt_sha256: draft-1
translated_from: content/ru/1981/10/articles/05_koen-metrika-konya-b8712586.md
source_content_sha256: 5837367e0af25d26af345ddd68e7b37c7486536016aae893bb497804396d2c1e
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 13⟧

D. Cohen

Chỉ số hiệp sĩ

Ở đây chúng ta sẽ quan tâm đến các nước đi của quân mã trên bàn cờ, mà ban đầu chúng ta sẽ đề xuất là nước đi vô hạn. Chúng ta hãy biểu thị các ô của bảng số tham số (theo tọa độ của tâm ô - xem Hình 1). Nước đi của quân mã nằm ở gốc tọa độ (0;0) là bước chuyển sang một trong 8 ô có tọa độ (±1; ±2), (±2; ±1). Nếu quân mã ở trong ô (x; y), thì một nước đi sẽ chuyển quân mã đó đến một trong các ô (x±1; y±2), (x±2; y±1).

Chúng ta hãy xác định khoảng cách từ ô P đến ô Q là số lượng nước đi hiệp sĩ tối thiểu và nhỏ cần thiết để di chuyển từ P đến Q. Chúng ta hãy biểu thị số này bằng q (P, Q). Ví dụ,

Tác giả, một nhà toán học người Mỹ, đã viết bài này cho «Kvant» bằng tiếng Anh. Bản dịch do A. Sosinsky biên tập.

Cơm. 1.

Mer, khoảng cách từ đầu O(0;0) đến ô E(1;0) bằng khoảng cách từ đầu đến ô F(3;6) - cả hai đều bằng 3. Hàm q, được xác định trên một tập hợp các cặp (P, Q) ô, có ba thuộc tính cơ bản về khoảng cách*):

q(P, Q) > 0, với P ≠ Q; q(P, P) = 0;
q(P, Q) = q(Q, P); (II)
q(P, R) ≤ q(P, Q) + q(Q, R). (III)

Hai tính chất đầu tiên rất đơn giản, nhưng tính chất thứ ba – gọi là bất đẳng thức tam giác – xuất phát từ thực tế là người ta có thể tìm được đường đi từ P đến R không đi qua Q và ngắn hơn bất kỳ đường đi nào từ P đến R đi qua Q.

Khoảng cách này—hệ mét của con ngựa—làm nảy sinh một “hình học” rất khó dạy. Trong đó, chúng ta có thể định nghĩa khái niệm đoạn [AB]** là một tập hợp các ô M sao cho q(A, M) + λ(M, B) = q(A, B), nhưng các đoạn này hóa ra rất xấu (hai đoạn có thể giao nhau trong một số ô). Bạn cũng có thể xác định các vòng tròn có bán kính r, trông đẹp hơn một chút (ít nhất là với r ≥ 5).

Bây giờ, chúng ta hãy lưu ý tính chất ước lượng sau đây của hàm q:

q((x; y), (x'; y')) =
= q((0; 0), (x' − x; y'' − y)). (*)

nó cho phép cùng nhau hàm q từ các cặp ô nghiên cứu hàm từ một ô - khoảng cách từ đầu:

d(P) = q(O, P).

Chúng ta hãy đặt vào mỗi ô P giá trị của hàm d(P). Hãy tưởng tượng rằng chúng ta đã làm điều này trên một mảnh giấy can. Khi đó tính chất (*) có nghĩa là nếu vẽ giấy can song song và kết hợp O với điểm P ở đầu thì q(P, Q) sẽ được viết trên giấy can phía trên điểm Q.

Hình 2 nêu bật tất cả các giá trị của d(P) nhỏ hơn hoặc bằng 4. Hình này gợi ý như sau:

*) Xem “Hình học 6-8”, đoạn 4 - khoảng. biên tập.
**) Xem đoạn “Hình học 6-8”. 5-6 - khoảng. biên tập.

⟦folio 14⟧

Công thức khoảng cách $d((a; b))$
Do tính chất (1) và (2), việc tính $d((a; b))$ trong trường hợp $0 \leq a \leq b$ là đủ. Ngoài ra, để tránh nhầm lẫn, tồn tại gần gốc tọa độ, chúng ta sẽ giả sử rằng $a+b \geq 6$. Khoảng cách là hai trường hợp tùy thuộc vào việc ô $P(a; b)$ có nằm trong dải ngang của đai thứ $n$ hay không, tức là $2a \leq b$. Đối với $d=d((a; b))$ cố định, điểm $P$ có 4 khả năng khác nhau.

Trường hợp đầu tiên: ô $P(a; b)$ nằm trong dải ngang của đai thứ $n$, tức là $2a \leq b$. Đối với $d=d((a; b))$ cố định, điểm $P$ có thể có 4 điểm khác nhau.

* Chúng tôi đưa ra bằng chứng, hơi khác so với của tác giả (ed.)

Cơm. 2.
Dưới đây là các thuộc tính của hàm $d$:
$$d((a; b))=d((b; a)),$$
(1)
$$d((a; b))=d((|a| |b|)),$$
(2)
số $d((a; b))$ và $a+b$
có cùng tính chẵn lẻ, (3) rõ ràng là theo định nghĩa.

Chúng ta hãy lưu ý thêm rằng trong Hình 2, bên trong đường màu đỏ có các số 0, 1, 2, 3, 4, khá lệch vị trí, mặc dù nằm đối xứng (do tính chất (1) và (2)). Theo thứ tự giữa các đường màu đỏ và xanh lam chỉ có bốn đường và biểu tượng $\times$ (thực ra là $\times=5$). Ở vành đai tiếp theo như vậy sẽ chỉ có 5 và 6, ở vành đai tiếp theo - 6 và 7, v.v. (Hình 3). Hình 4 chỉ hiển thị quý đầu tiên $(x, y \geq 0)$. Hình này cũng hiển thị phần $n-20$ của dây đai, chỉ chứa các số $n$ và $n+1$.

Nói một cách đại khái, đai thứ $n$ có dạng ranh giới hình vuông (ở cạnh có chiều dài $4n+1$) với các góc ở giữa (các tam giác vuông có góc bằng nhau được cắt bỏ ở cạnh có chiều dài $n-1$). Đai bao gồm các dải ngang và dọc có độ dày 2 và bốn đoạn chéo có dạng bậc thang; một trong số chúng được tô màu trong hình.

Vì vậy, nếu chúng ta bỏ qua sự nhầm lẫn tồn tại gần gốc tọa độ, bức tranh hình học của thước đo hiệp sĩ sẽ trở nên rõ ràng hơn. Tuy nhiên, điều này là chưa đủ đối với chúng tôi: chúng tôi muốn tìm hiểu cách tìm $d((a; b))$ hoàn toàn tương tự - sử dụng các số $a$ và $b$. Tóm lại, chúng ta cần

Cơm. 3.
Cơm. 4.

⟦folio 15⟧

ity tùy thuộc vào mức độ thẳng đứng của nó (Hình 5). Ở cấp độ cao nhất, điểm $P$ đạt được với số nguyên tối thiểu là $d$ bước di chuyển, tăng tọa độ thứ hai lên 2; ở cấp độ tiếp theo - toàn bộ $d-1$ bước di chuyển thuộc loại này và một bước di chuyển tăng tọa độ thứ hai lên 1; cấp độ tiếp theo yêu cầu $d-2$ và 2 lần di chuyển thuộc loại này; ở cấp độ thấp hơn - lần lượt là $d-3$ và 3. Trong những trường hợp này, chiều cao của $b$ lần lượt là $2d$, $2(d-1)+1=2d-1$, $2(d-2)+2=2d-2$, $2(d-3)+3=2d-3$. Từ đây, chúng ta có thể biểu thị $d$ theo $b$, nhưng $b$ là một số nguyên và chúng ta không thể viết đáp số nếu không biết tính chẵn lẻ của $b!$ Chúng ta sẽ làm thế nào?

Hóa ra đáp số đúng cho một trong các số $[(b+1)/2]$ hoặc $[(b+1)/2]+1$ (ở đây dấu ngoặc vuông biểu thị phần nguyên), cụ thể là số có số chẵn lẻ trùng với số chẵn lẻ của số $a+b$ (xem thuộc tính (3)). Người đọc có thể dễ dàng kiểm tra điều này bằng Hình 5 và chú thích của nó.

Trường hợp thứ hai: ô $P(a; b)$ nằm trên tiết diện chéo của đai thứ $n$, tức là $2a>b$. Dễ dàng nhận thấy rằng tại bất kỳ điểm nào trên đường chéo của phần tư thứ nhất của đai thứ $n$, người ta có thể đạt mức tối thiểu bằng một chuỗi nước đi hiệp sĩ sao cho trên mỗi nước đi tổng tọa độ tăng đúng 3 (tức là theo nước đi $(a; b) \rightarrow (a+1; b+2)$ và $(a; b) \rightarrow (a+2; b+1)$). Do đó $a+b=3n$ hoặc $a+b=3(n+1)$, do đó $d((a; b)) = [(a+b+1)/3]$ hoặc $d((a; b)) = [(a+b+1)/3]+1$. Số nào trong hai số này có thể được lấy là rõ ràng từ các thông báo chẵn lẻ (xem (3)).

Chúng ta hãy tóm tắt nghiên cứu của chúng ta về hàm $d((a; b))$. Trong điều kiện $0 \leq a \leq b$ và $a+b \geq 6$, số $d((a; b))$ có cùng tính chẵn lẻ với $a+b$, là $[(b+1)/2]$ hoặc $[(b+1)/2]+1$ trong trường hợp $2a \leq b$, $[(a+b+1)/3]$ hoặc $[(a+b+1)/3]+1$ trong trường hợp $2a>b$.

Trên thực tế, các công thức này cho kết quả đúng đáp số và cho $a+b<6$ ở mọi nơi ngoại trừ các ô (0; 1) và (2; 2), trong đó chúng cho kết quả lần lượt là 1 và 2, cùng với 3 và 4 đúng (xem Hình 2).

Số liệu của một con ngựa trên một tấm ván thẳng

Bây giờ chúng ta hãy giới hạn bàn cờ vô hạn của mình: chúng ta sẽ xem xét nước đi của quân mã trên bàn cờ hình chữ nhật $a \times b$ ($a \leq b$). Với $a=1$ thì không có gì phải cân nhắc (“Đồng chí đại kiện tướng, hiệp sĩ không được di chuyển như vậy!”), với $a=2$ mọi thứ đều rất đơn giản. Chúng tôi sẽ để lại những trường hợp có ý nghĩa hơn $a=3$ và $a=4$ cho người đọc và chuyển sang trường hợp $5 \leq a \leq b$. Hóa ra,

Tại $5 \leq a \leq b$ có các nước đi hiệp sĩ có chiều dài $d((a; b))$ bên trong hình chữ nhật từ các cạnh $x=0$, $x=a$, $y=0$, $y=b$ kết nối các điểm (0; 0) và $(a; b)$, và đường đi này là ngắn nhất.

Thật vậy, chúng ta bắt đầu từ một điểm trong vành đai thứ $n$ và tạo một điểm về phía đầu. Sau đó, chúng ta vẫn ở bên trong hình chữ nhật và kết thúc ở đai thứ $(n-1)$. Tiếp tục quá trình này, chúng ta sẽ đến được vành đai thứ tư. Tiếp theo, vẫn còn phải kiểm tra tính hợp lệ của tuyên bố của chúng tôi đối với các ô của ô thứ tư.

⟦folio 16⟧

Thắt lưng. Chúng tôi để việc tìm kiếm này cho người đọc.

Số liệu hiệp sĩ trên một bảng vuông
Bây giờ hãy xem xét một bảng hình vuông $n \times n$, được giới hạn bởi một hình chữ nhật $x=0, x=n-1, y=0, y=n-1$. Đường đẳng cự có đường kính của bảng này là khoảng cách lớn nhất (theo nghĩa của thước đo ngựa) giữa các ô của nó. Để lại trường hợp kích thước nhỏ cho bạn đọc, chúng ta xét trường hợp $n \geq 5$. Từ phần trước dễ dàng nhận thấy đường kính sẽ là khoảng cách từ ô (0; 0) đến một trong các ô $(n-1; n-1)$ hoặc $(n-1; n-2)$. Sử dụng nhận xét này và trước khi thu được công thức khoảng cách, chúng tôi chỉ ra rằng
Đường kính của bàn cờ $n \times n$ bằng số $2n/3$ được làm tròn đến số nguyên gần nhất.

Thật vậy, theo công thức khoảng cách, $d((n-1; n-1))$ bằng $[(2n-1)/3]$ hoặc $[(2n-1)/3] + 1$ (cụ thể là, số nào trong số này là số chẵn); và $d((n-1; n-2))$ bằng $[(2n-2)/3]$ hoặc $[(2n-2)/3] + 1$ (lẻ). Xét ba trường hợp tính theo số dư khi chia số $n$ cho 3.

Trường hợp đầu tiên: $n=3k$. Sau đó
$$[(2n-1)/3] = [(2n-2)/3] = 2k-1,$$
vậy khoảng cách tới $(n-1; n-1)$ là $2k$ và tới $(n-1; n-2)$ là $2k-1$. Đường kính là $2a$, tức là $2n/3$ mà không làm tròn.

Trường hợp thứ hai: $n=3k+1$. Sau đó
$$[(2n-1)/3] = [(2n-2)/3] = 2k,$$
vì vậy khoảng cách đến $(n-1; n-1)$ và $(n-1; n-2)$ lần lượt là $2k$ và $2k+1$. Đường kính bằng $2k+1$, là số được làm tròn $2n/3$.

Trường hợp thứ ba: $n=3k+2$. Sau đó
$$[(2n-1)/3] = 2k+1,$$
vì vậy khoảng cách chúng ta quan tâm lần lượt là $2k+2$ và $2k+1$. Điều này có nghĩa là đường kính bằng $2k+2$, lại là số được làm tròn $2n/3$.

Lưu ý rằng khoảng cách lớn nhất được thực hiện trong trường hợp này bởi các ô không nằm trên đường chéo chính.

Các công thức khác
Hàm $d((a; b))$ đã được nghiên cứu trước đó và người ta đã thu được các biểu thức tương tự khác (phức tạp hơn) cho nó (cho $a+b \geq 8$, $0 \leq a \leq b$). M. Goldberg (Mỹ) tìm thấy
$$d((a; b)) = \begin{cases} b-a-2[(b-2a)/4] \\ \text{при } 2a \leq b, \\ b-a+[(8a-4b+2)/3] - [(4a-2b)/3] \\ \text{при } 2a > b, \end{cases}$$

và D. Cvetkovic và S. Simch (Nam Tư) được tìm thấy
$$d((a; b)) = \begin{cases} a+b-2\left[\frac{b}{2}\right] - \left[\frac{a-[b/2]}{2}\right] \\ \text{при } 2a \leq b, \\ a+b-2\left[\frac{a+b}{3}\right] \end{cases}$$

Có thể chứng minh rằng những công thức này tương đương với công thức của chúng ta, nhưng sẽ thú vị hơn nếu bạn thử đoán xem tác giả đã sử dụng lý do gì để đưa ra chúng.

Để kết luận, chúng tôi cung cấp cho người đọc bài toán sau: tìm diện tích của một hình tròn có bán kính $r$, tức là số ô $(a; b)$ mà $d((a; b)) \leq r$.

Giải đấu mang tên M.V. Lomonosov
Theo dữ liệu cập nhật, chuyến tham quan năm nay (xem «Kvant», 1981, số 8, trang 51) sẽ diễn ra tại Moscow vào ngày 25 tháng 10 lúc 10 giờ trong khuôn viên của các chuyến bay sau: MAI, MATI, MGPI, MIIGAIK, MINHIGP, MISS, MISIS; Mời học sinh lớp 6-9.
