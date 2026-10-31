---
id: 1982-8-dubrovskiy-matematika-volshebnogo-kubika-4b89e44f
issue: kvant_1982_8
year: 1982
number: "8"
title: Khối lập phương Toán học kỳ diệu
authors:
  - Дубровский В. Н.
rubric: osnovnye-stati
page_first: 24
page_last: 29
page_labels: 22, 23, 24, 26, 27
tag: O2V3
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 29e479f6fd5c040b115292705f3721bd6dc637595ef5ca23841b093c5336f1e9
prompt_sha256: draft-1
translated_from: content/ru/1982/08/articles/08_dubrovskiy-matematika-volshebnogo-kubika-4b89e44f.md
source_content_sha256: b3f5d8b2938c16a27a5325d6aed22202a70b639c0f24111d0f38a5d29d5325e4
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 22⟧

V. Dubrovsky

Toán học
khối ma thuật

«Kvant» đã nói chi tiết về thiết kế của “khối ma thuật” Hungary và các thuật toán lời giải của câu đố này*). Tiếp theo khối lập phương, hàng loạt trò chơi tương tự như nó đã ra đời. Bài viết của chúng tôi dành cho lý thuyết toán học của những trò chơi như vậy. Và đối với những người hâm mộ trò chơi lập phương thực tế, chúng tôi trình bày sơ đồ của thuật toán lập khối ma thuật ngắn phá kỷ lục dựa trên lý thuyết này.

Khối ma thuật đặt câu hỏi
Chúng ta hãy đồng ý gọi các phương án khác nhau để lắp ráp một khối ma thuật phát sinh khi 8 chiếc cốc nhỏ ở góc được đặt ngẫu nhiên dọc theo các đỉnh của khối ma thuật và 12 chiếc cốc vừa dọc theo các cạnh, trạng thái của nó. Các khối trung tâm ở tất cả các trạng thái đều được đặt theo cùng một cách - giống như ở trạng thái 0, khi mỗi mặt của khối ma thuật trở thành hợp pháp, nghĩa là có thể bằng cách thu thập các khối nhỏ theo thứ tự ngẫu nhiên, để sau đó đạt được trạng thái 0 bằng cách xoay các mặt? Nếu không, làm thế nào bạn có thể biết liệu một trạng thái nhất định có hợp pháp hay không và nói chung liệu hai trạng thái nhất định có liên quan với nhau hay không? Có bao nhiêu cái hợp pháp?

*) «Kvant», 1980, số 12, tr. 17; 1982, số 3, tr. 20 và số 7, tr. 22; xem thêm “Nuuka và Life”, 1981, số 3, tr. 131 và 1982, không. 2, tr. 97.

⟦folio 23⟧

Cơm. 1. Trạng thái không. Khối góc ẩn có số 9, khối góc ẩn có số 10, 11, 12. Trên các cạnh ẩn, các mũi tên thẳng hàng với các mũi tên trên các cạnh đối xứng với chúng so với tâm của khối.

nói cách khác, bạn có thể nhận được bao nhiêu màu sắc khác nhau của khối ma thuật bằng cách xoay các mặt của nó? Số lượng trạng thái không kết nối theo cặp tối đa là bao nhiêu? Trước hết chúng ta hãy tìm hiểu nó

Cách thiết lập trạng thái

Để mô tả đầy đủ trạng thái của khối ma thuật, bạn cần chỉ ra cho mỗi khối nhỏ vị trí mà nó chiếm giữ và hướng của nó ở vị trí này - mỗi khối góc có thể được đặt vào cùng một “khe” của khay và khối ở giữa có thể được đặt theo hai cách.

Hãy tưởng tượng khối ma thuật ở trạng thái số 0. Hãy đánh số lại các đỉnh của nó và các khối góc trong đó bằng các số từ 1 đến 8, các cạnh và các khối ở giữa tương ứng với các số từ 1 đến 12. Ngoài ra, trên mỗi cạnh của khối ma thuật, chúng ta sẽ chọn một hướng nhất định (trong hình. 1) và vẽ một mũi tên theo cùng hướng trên khối ở giữa tương ứng (Hình 1).

Bây giờ, vị trí của khối góc thứ $i$ ($j$-giữa) ở trạng thái $S$ có ​​thể được chỉ định bằng số $\sigma_s(i)(\tau_s(j))$ của đỉnh (của cạnh đó) nơi nó tọa lạc (ở đây $i=1$, ..., 8, $j=1$, ..., 12).

Để đặt hướng của các cốc góc, hãy chọn một cặp mặt đối diện của khối ma thuật, ví dụ như các mặt nằm ngang của nó. Để xác định điều này, chúng ta hãy giả sử rằng khối trung tâm trên cùng là

màu xanh lam và phần dưới cùng có màu xanh lá cây*). Mỗi khối lập phương ở góc có một mặt màu xanh lam hoặc một mặt màu xanh lá cây; góc $\alpha(\alpha=0^\circ, 120^\circ$ hoặc $240^\circ)$, tại đó khối này nằm trong “tổ” của nó xung quanh đường chéo của khối lớn ngược chiều kim đồng hồ**), sao cho mặt (xanh dương hoặc xanh lục) này nằm ngang, chúng ta sẽ gọi góc quay của khối góc này ở trạng thái $S$ và ký hiệu là $\alpha_s(i)$, trong đó $i$ là số của khối lập phương.

Hướng của khối ở giữa thứ $j$ ở trạng thái $S$ theo một góc cho trước $\beta_s(j)$ giữa hướng của mũi tên trên nó và hướng của cạnh mà nó nằm trên đó (cạnh $\tau_s(j)$-th). Góc $\beta_s(j)$ có thể bằng $0^\circ$ hoặc $180^\circ$; chúng ta sẽ gọi nó là góc quay của khối ở giữa thứ $j$ ở trạng thái $S$.

Các trạng thái liên kết có điểm gì chung?

Chúng ta cần tìm hiểu trong trường hợp nào hai trạng thái có liên quan với nhau. Với mục đích này, chúng ta hãy theo dõi xem các đặc điểm của trạng thái $\alpha_s, \beta_s, \sigma_s$ và $\tau_s$ thay đổi như thế nào khi xoay các mặt. Hãy bắt đầu với những góc rẽ. Thật dễ dàng để kiểm tra điều đó

A. Góc quay của các cốc góc không thay đổi khi xoay bốn mặt thẳng đứng một góc $180^\circ$ và khi xoay các mặt ngang tùy ý.

B. Góc quay của cốc ở giữa không thay đổi khi hai mặt đối diện (phải và trái trong Hình 1) được quay một góc $180^\circ$ và khi các mặt 对立 được xoay tùy ý.

B. Khi bất kỳ mặt thẳng đứng nào được quay một góc $\pm 90^\circ$, $120^\circ***$) sẽ được thêm vào các góc quay $\alpha_s$ của hai chiếc cốc đứng ở các đỉnh đối diện của nó và vào các góc

*) Nhân tiện, khối lập phương có màu khác. Ý của chúng tôi là một khối lập phương có các cạnh màu xanh lá cây và màu xanh lam đối diện nhau.

**) Tất nhiên, nếu không phá hủy khối ma thuật thì không thể thực sự xoay khối góc của nó trong tổ của nó - ở đây chúng tôi đang xác định một khái niệm lý thuyết.

***) Theo thông lệ, chúng tôi thêm các góc quay với độ chính xác $360^\circ$, ví dụ $240^\circ + 240^\circ = 120^\circ, 180^\circ + 180^\circ = 0^\circ$, v.v.

⟦folio 24⟧

Cơm. 2. Sau khi xoay bên phải 90° theo chiều kim đồng hồ. Đây $\tau(1)=2$, $\tau(4)=1$, $\tau(2)=3$, $\alpha(1)=\alpha(3)=120^\circ$, $\alpha(2)=\alpha(4)=240^\circ$, $\beta(1)=\beta(2)=\beta(3)=\beta(4)=180^\circ$.

góc quay của hai cốc góc còn lại được cộng thêm 240°.

D. Khi xoay mặt phải hoặc trái (Hình 2) ±90°, góc quay của cả bốn cốc giữa của mặt này sẽ thay đổi.

Từ đây suy ra ngay tổng các góc quay của tất cả các góc và tất cả các cốc ở giữa

$$A(S) = \alpha_S(1) + \alpha_S(2) + \ldots + \alpha_S(8),$$
$$B(S) = \beta_S(1) + \beta_S(2) + \ldots + \beta_S(12)$$
không đổi trong mọi phép quay của mặt. Những đặc điểm như vậy của một trạng thái được gọi là bất biến (từ tiếng Latin “không thay đổi”). Giá trị của bất kỳ bất biến nào đối với hai trạng thái ràng buộc $S_1$ và $S_2$ rõ ràng là trùng khớp. Vì vậy, các đẳng thức $A(S_1) = A(S_2)$ và $B(S_1) = B(S_2)$ là điều kiện cần cho sự liên thông của các trạng thái. Chúng ta sẽ sớm thấy rằng bằng cách thêm vào chúng một đẳng thức tương tự cho một bất biến khác, chúng ta sẽ có đủ điều kiện. Tuy nhiên, trước khi định nghĩa bất biến thứ ba này, chúng ta phải bỏ qua một chút

Về hoán vị

Hoán vị của một tập hợp hữu hạn là bất kỳ ánh xạ nào của tập hợp này lên chính nó. Như vậy, hàm $\sigma_S$ được xác định ở trên, được xác định trên tập {1, ..., 8}, là một hoán vị của tập hợp này và $\tau_S$ là một hoán vị của tập hợp {1, ..., 12}. Bất kỳ thao tác $F$ nào cũng được liên kết với hai hoán vị $\sigma_F$ và $\tau_F$ của cùng một bộ: nếu trạng thái 0 $S_0$ được phép toán $F$ chuyển sang trạng thái $S$, thì theo định nghĩa, $\sigma_F(i) = \sigma_S(i)$, $\tau_F(j) = \tau_S(j)$. Nói cách khác, $\sigma_F(i)$ và $\tau_F(j)$ là số của những vị trí đó (xem Hình 1), do kết quả của phép toán $F$, bị chiếm bởi khối góc đứng ở vị trí thứ $i$ và khối ở giữa đứng ở vị trí thứ $j$.

Thực hiện lần lượt các hoán vị $\sigma_1$ và $\sigma_2$ của cùng một tập hợp, chúng ta lại thu được ánh xạ của nó lên chính nó - hoán vị $\sigma$. Nó được gọi là `композицией` $\sigma_1$ và $\sigma_2$: $\sigma = \sigma_1 \circ \sigma_2$.

Bài toán 2. Cho phép thao tác $F$ di chuyển khối ma thuật từ trạng thái $S'$. Chứng minh rằng $\sigma_S' = \sigma_S \circ \sigma_F$, $\tau_S' = \tau_S \circ \tau_F$. Chứng minh rằng $\sigma_{F_1} \circ F_2 = \sigma_{F_1} \circ \sigma_F, \tau_{F_1} \circ F_1 = \tau_{F_1} \circ \tau_F$, trong đó $F_1 \circ F_2$ là hợp của các phép toán $F_1$ và $F_2$.

Đặt $\sigma$ là một hoán vị tùy ý của tập hợp {1, 2, ..., $n$}. Hãy vẽ hai đường có $n$ dấu chấm, cái này ở dưới cái kia. Nếu, trong quá trình hoán vị $\sigma$, số $i$ đi vào $j$, chúng ta nối điểm thứ $i$ của dòng trên với một đoạn có điểm thứ $j$ của dòng dưới - chúng ta thu được biểu đồ hoán vị $\sigma$ (Hình 3). Chúng ta hãy biểu thị bằng $N(\sigma)$ số giao điểm của các đoạn đồ thị (chúng ta đếm điểm tại đó có nhiều hơn hai đoạn giao nhau với số lần bằng số cặp đoạn thẳng mà nó chứa). Hoán vị $\sigma$ được gọi là `четной` (lẻ) nếu

⟦folio 26⟧

Cạnh của khối vừa đã chọn được đánh dấu bằng nhãn dán màu trắng và cạnh màu trắng được đánh dấu bằng nhãn dán màu xanh lam. Chúng tôi nhận được trạng thái $S_1^1$. Hãy dịch nó thành $S_2^1$ và tính đối xứng của nhãn dán - chúng ta có trạng thái $S_2^1$. Do đó, các trạng thái $S_1$ và $S_2$ được kết nối. Tương tự, người ta chứng minh rằng hai trạng thái bất kỳ có cùng bất biến đều có liên quan với nhau. Do đó, mỗi bộ $3 \times 2 \times 2 = 12$ giá trị của các bất biến $A$, $B$ và $E$ (A nhận ba giá trị: $0^\circ$, $120^\circ$ và $240^\circ$, $B$ - hai: $0^\circ$ và $180^\circ$, $\varepsilon$ - cũng là hai: 1 và -1) xác định một lớp các trạng thái liên quan theo cặp với tập hợp bất biến này và các trạng thái từ các lớp khác nhau không liên quan; một trong các giai cấp được hình thành bởi các nhà nước pháp quyền.

Bài toán 4. Chứng minh rằng số trạng thái ở tất cả các lớp bằng nhau và bằng $8! \cdot 3^8 \cdot 11! \cdot 2^{12}$.

Bài toán 5. Chứng minh rằng giá trị của các bất biến $A$, $B$, $\varepsilon$ chỉ phụ thuộc vào trạng thái của khối ma thuật chứ không phụ thuộc vào việc chọn cặp mặt hướng đến các cạnh và cách đánh số các đỉnh, cạnh.

Thuật toán ghi

Tạp chí Scientific American (1981, số 3) mô tả ý tưởng chung về một thuật toán khối ma thuật cực ngắn, được phát minh bởi nhà toán học người Anh M. Thistlethwaite. Sau khi có được thuật toán này, bạn có thể chuyển từ bất kỳ trạng thái pháp lý nào sang trạng thái 0 trong không quá 52 lần di chuyển*). Thuật toán của Thistlethwaite về cơ bản khác với các thuật toán được mô tả trong các bài viết mà chúng tôi đã đề cập ở trên. Nói chung, sơ đồ của nó như sau.

Hãy để chúng tôi giới thiệu ba hạn chế đối với việc quay các mặt được phép:

1) cấm xoay hai mặt thẳng đứng đối diện nhau (ví dụ: mặt bên phải hoặc bên trái trong Hình 1) theo góc ±90°;
2) cấm xoay bất kỳ cạnh thẳng đứng nào ±90°;
3) Tất cả các góc quay của các cạnh ±90° đều bị cấm.

Chúng ta hãy biểu thị bằng $\Phi_1$, $\Phi_2$, $\Phi_3$ tập hợp tất cả các thao tác thỏa mãn sự tương ứng (ví dụ: $\Phi_3$ là tất cả các chuỗi có thể quay của các mặt trên

*) Cùng một tạp chí cho biết trên thực tế 23 nước đi luôn là đủ (!), và con số này không thể giảm được. Rõ ràng, một cột ngắn của thuật toán có thể thực hiện được để giải khối lập phương vẫn chưa được tìm thấy.

180°) và thông qua $\Sigma_1$, $\Sigma_2$, $\Sigma_3$ lớp của tất cả các trạng thái thu được từ phép toán 0 từ $\Phi_1$, $\Phi_2$, $\Phi_3$. Rõ ràng là $\Sigma_1 \supset \Sigma_2 \supset \Sigma_3 \supset S_0$ và hai trạng thái bất kỳ từ lớp $\Sigma_k$ có liên quan với nhau bằng phép toán từ $\Phi_k$. Toàn bộ thuật toán được chia thành bốn giai đoạn. Thao tác đầu tiên thực hiện thao tác sau $F$ (không hạn chế di chuyển), chuyển trạng thái ban đầu $S$ sang trạng thái nào đó $S_1 \in \Sigma_1$. Trong tương lai, chỉ các hoạt động từ $\Phi_1$ mới được mở rộng. Ở giai đoạn thứ hai, sử dụng thao tác $F_1 \in \Phi_1$, nó được thực thi ở trạng thái $S_2 \in \Sigma_2$, ở giai đoạn thứ ba, sử dụng thao tác $F_2 \in \Phi_2$, nó được thực thi ở trạng thái $S_3 \in \Sigma_3$. Cuối cùng, ở giai đoạn thứ tư, chỉ xoay các mặt 180°, chúng ta phải thu được từ trạng thái $S_3$ trạng thái 0 $S_0$.

Rõ ràng, khi chúng tôi đến lớp $\Sigma_k$ sau màn tiếp theo, chúng tôi sẽ không bao giờ rời khỏi nó, vì vậy thành tích của tất cả các màn trước đó sẽ được lưu tự động. Ngoài ra, cho đến giai đoạn cuối cùng không cần thiết phải “tắm nắng” những chỗ nhỏ. Nhưng ưu điểm chính của sơ đồ này là nó tốt hơn nhiều so với các thiết bị cảm biến để tính toán trên máy tính. Người ta tin rằng điều này đóng vai trò quyết định trong việc “lập kỷ lục thế giới”.

Trước khi xây dựng thuật toán theo sơ đồ này, cần tìm hiểu các lớp trạng thái $\Sigma_1$, $\Sigma_2$, $\Sigma_3$ là gì. Đây là nơi bất biến có ích. Các lớp $\Sigma_1$ và $\Sigma_2$ rất dễ hiểu. Nhắc lại tính chất $A$ và $B$ của góc quay của cốc nhỏ, ta thấy nụ cười của cốc ở giữa lặp đi lặp lại $\beta_S(j)$ là bất biến đối với phép toán tương đối từ $\Phi_1$ (thuộc tính $B$), nụ cười của cốc góc lặp lại $a_S(i)$ là bất biến với phép toán tương đối từ $\Phi_2$ (thuộc tính $A$). Cũng dễ dàng nhận thấy rằng trong quá trình hoạt động từ $\Phi_2$, bốn khối ở giữa nằm ở “lớp giữa” nằm ngang giữa mặt trên và mặt dưới chỉ có thể thay đổi vị trí giữa chúng, do đó thành phần của lớp này không thay đổi.

Bài toán 6. Chứng minh rằng các đại lượng $A(S)$, $\varepsilon(S)$ và $\beta_j(S)$ (j=1, ..., 12) tạo thành một hệ đầy đủ các bất biến của phép toán tương đối từ $\Phi_1$, và $\varepsilon(S)$, $\alpha_i(S)$ (i=1, ..., 8), $\beta_j(S)$ (j=1, ..., 12) và thành phần của lớp giữa nằm ngang - hoạt động tương đối của $\Phi_2$.

Cũng dễ dàng không kém để xác minh rằng với các phép toán từ $\Phi_3$, ngoài các bất biến được liệt kê trong nhiệm vụ 6, thành phần của hai lớp ở giữa thẳng đứng và thành phần của hai tứ giác cốc góc tạo thành các tứ diện đều cũng được bảo toàn (trong Hình 1 thành một).

⟦folio 27⟧

một trong số chúng bao gồm các khối góc 1, 3, 5, 7 và khối còn lại - 2, 4, 6, 8). Nhưng đó không phải là tất cả! Còn một bất biến nữa đối với tập hợp các phép toán $\Phi_3$, mô tả sự phụ thuộc giữa các hoán vị của các cốc góc bên trong bộ tứ. Lấy hai khối bất kỳ của một trong bốn. Chúng liền kề với một trong các mặt của khối lập phương. Nếu đây là bên phải hoặc bên trái, thì chúng ta nói rằng các hình khối này chiếm vị trí thứ nhất, nếu mặt trước hoặc mặt sau - thì thứ 2, nếu trên cùng hoặc dưới cùng - thì thứ 3. Rõ ràng là cặp cốc thứ hai trong bộ tứ này luôn chiếm vị trí giống như cặp cốc đầu tiên. Để đơn giản, chúng tôi giới hạn bản thân ở các trạng thái $S$, trong đó thành phần của bộ tứ là “chính xác” (như ở trạng thái 0). Xét bộ tứ thứ nhất và xác định hoán vị $p_S$ tập {1, 2, 3} bằng cách đặt $p_S(i) = j$ nếu cặp cốc của bộ tứ này, chiếm vị trí thứ i trong trạng thái $S_0$, chiếm vị trí thứ j trong trạng thái $S$. Tương tự, đối với bộ tứ thứ hai, chúng ta xác định hoán vị $q_S$. Bất biến cuối cùng của chúng ta là hoán vị $\delta_S = p_S \cdot q_S^{-1}$). Nó có thể nhận bất kỳ giá trị nào trong số 3!=6 giá trị.

Bài toán 7. Chứng minh rằng $\delta_S$ thực sự là bất biến theo $\Phi_3$ và rằng cùng với các bất biến được liệt kê ở trên, nó tạo thành một hệ thống hoàn chỉnh cho $\Phi_3$.

Bây giờ rõ ràng là ở mỗi giai đoạn của thuật toán, chúng ta nên cố gắng đảm bảo rằng các giá trị của phần bất biến tiếp theo mà chúng ta tìm thấy trở nên giống như đối với trạng thái 0.

Chúng tôi mời độc giả phát triển độc lập một thuật toán hoặc các giai đoạn riêng lẻ của nó theo sơ đồ đã chỉ định và gửi phiên bản của chúng cho người chỉnh sửa. Điều tốt nhất trong số đó sẽ được xuất bản.

Pongogram cho các trò chơi khác

Hơn nữa, những người không tinh vi trong toán học sẽ ngay lập tức nhận ra khối ma thuật là “họ hàng” của câu đố được thay thế “15” của Sam Loyd, mặc dù về hình thức thì chúng hoàn toàn khác nhau. Điểm giống nhau nằm ở cấu trúc chung của các trò chơi này, có thể được mô tả như sau: có một hệ thống nhất định có khả năng hoạt động ở nhiều trạng thái khác nhau, trong đó nổi bật là một trạng thái (“không”). Nhiệm vụ là chuyển một trạng thái nhất định tùy ý về 0, sử dụng một tập hợp các phép biến đổi tiêu chuẩn nhất định của hệ thống (trong trường hợp khối ma thuật - phép quay các mặt theo $\pm 90^\circ$ hoặc $180^\circ$), có thể được gọi là các thao tác hoặc bước di chuyển cơ bản. Hơn nữa, bất kỳ nước đi nào cũng có thể đảo ngược được (nghĩa là sau khi thực hiện xong nước đi đó, chúng ta luôn có thể quay lại trạng thái ban đầu chỉ bằng một nước đi).

Cũng giống như đối với khối ma thuật, trong trường hợp tổng quát, các khái niệm về phép toán, liên kết với các trạng thái và một bất biến đều được xác định. Một khái niệm hữu ích khác là quỹ đạo trạng thái: đây là tên được đặt cho tập hợp tất cả các trạng thái liên kết với một trạng thái nhất định. Cụ thể, như chúng ta đã thấy, tập trạng thái của khối ma thuật được chia thành 12 quỹ đạo.

Chúng tôi cung cấp cho người đọc một loạt bài toán dành cho việc nghiên cứu loại hình chơi. Các bài toán 8-10 yêu cầu chứng minh một số tính chất chung của các trò chơi này (chỉ đưa ra công thức của chúng). Các vấn đề 11-16 xem xét nhiều ví dụ khác nhau và chỉ đưa ra mô tả về trò chơi, nhưng bạn cần trả lời các câu hỏi sau: 1) tập hợp đầy đủ các bất biến của trò chơi này là gì? 2) làm thế nào để chuyển một trong hai trạng thái được kết nối sang trạng thái khác? 3) số lượng quỹ đạo và trạng thái trong một quỹ đạo là bao nhiêu?

Nhiệm vụ 8.

8. Chúng ta sẽ viết $S_1 \approx S_2$ nếu trạng thái $S_1$ và $S_2$ được kết nối. Sau đó với bất kỳ trạng thái nào $S_1, S_2, S_3$ 1) $S_1 \approx S_1, 2) S_1 \approx S_2 \Rightarrow S_2 \approx S_1, 3) S_1 \approx S_2, S_2 \approx S_3 \Rightarrow S_1 \approx S_3$. Nói cách khác, quan hệ $S_1 \approx S_2$ là quan hệ tương đương.

9. Quỹ đạo của hai trạng thái bất kỳ $S_1$ và $S_2$ đều trùng nhau (nếu $S_1 \approx S_2$) hoặc không có các phần tử chung.

10. Nếu bất kỳ hoạt động nào biến đổi ít nhất một trạng thái thành chính nó cũng biến đổi bất kỳ trạng thái nào khác, thì số trạng thái $N_0$ trong tất cả các quỹ đạo là như nhau và số lượng tất cả các trạng thái là $N = N_0 \cdot k$, trong đó $k$ là số lượng quỹ đạo. Kiểm tra xem các thuộc tính được chỉ định của thao tác có đúng với khối ma thuật hay không.

11. Khám phá các trò chơi chỉ khác với “khối ma thuật” ở một tập hợp các yếu tố thao tác: 1) chỉ được phép xoay 2 (3, 4 hoặc 5) mặt; 2) chuyển động là chuyển động quay của một cặp mặt đối diện (một mặt theo chiều kim đồng hồ và mặt kia ngược chiều kim đồng hồ) ở cùng một góc; 3) tương ứng, cả hai mặt theo chiều kim đồng hồ.

(Cuối cùng xem trang 48)
