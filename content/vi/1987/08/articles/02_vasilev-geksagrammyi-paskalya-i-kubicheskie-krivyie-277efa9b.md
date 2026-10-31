---
id: 1987-8-vasilev-geksagrammyi-paskalya-i-kubicheskie-krivyie-277efa9b
issue: kvant_1987_8
year: 1987
number: "8"
title: Quẻ Pascal và đường cong bậc ba
authors:
  - Васильев Н. Б.
rubric: osnovnye-stati
page_first: 4
page_last: 10
page_labels: 2-8
tag: A6G7
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 86a814205cb9da678bdb2ee316dedc52d3139567643d50b6032fd0163e16c224
prompt_sha256: draft-1
translated_from: content/ru/1987/08/articles/02_vasilev-geksagrammyi-paskalya-i-kubicheskie-krivyie-277efa9b.md
source_content_sha256: 10f89639b1e20ad21b8660b38c2d927006ea04d3bd2fb5da2e0561969848fb7d
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

CÁC QUÁC VỤ CỦA PASCAL
VÀ ĐƯỜNG CONG KHỐI

Ứng viên Khoa học Vật lý và Toán học
N. B. VASILIEV

Năm 1640, Blaise Pascal (lúc đó ông mới 17 tuổi) đã phát hiện ra tính chất đáng chú ý của đường đứt gãy sáu khâu nội tiếp trong một vòng tròn. Trong cấu hình mới nổi (hình 1), mà Pascal gọi là “quẻ thần bí”, một số điểm giao nhau chắc chắn nằm trên cùng một đường thẳng. Pascal đã công bố khám phá của mình dưới dạng một tấm áp phích, xuất bản thành 50 bản để phân phát và chuyển tiếp cho từng nhà khoa học. Công trình của Pascal và tác phẩm ngắn của Gerard Desargues, “Một ví dụ về một trong những phương pháp chung để sử dụng phối cảnh,” xuất bản bốn năm trước, đã đặt nền móng cho một môn toán học mới—hình học dự án. Khi đó, người ta nhận ra rằng “kiến thức cổ xưa không phải là tất cả” (cách nói của Pierre Fermat) - cho đến thời điểm đó, thành tựu của các nhà hình học Hy Lạp cổ đại được coi là vượt trội.

Với tên của một trong những nhà hình học cổ đại cuối cùng - Pappus of Alexandria, sống ở thế kỷ thứ 3 sau Công nguyên. e., - một định lý liên quan về đường đứt nét sáu khâu, tương tự như định lý Pascal; Đây là nơi chúng ta sẽ bắt đầu câu chuyện.

Chúng tôi thực sự khuyên bạn nên tiến hành kiểm tra thực nghiệm các định lý này:

tạo một vài bức vẽ tròn và gọn gàng - điều này không chỉ thuyết phục bạn về tính hợp lệ của các định lý mà còn cho phép bạn hiểu được niềm vui bao trùm Pascal và những người cùng thời với ông (và có lẽ cả Pappus) trong thời đại của họ.

Chúng ta sẽ không tập trung vào các chứng minh hình học và vô số hệ quả của các định lý Pappus và Pascal mà chỉ đề cập đến một chủ đề quan trọng - việc sử dụng các phép biến đổi hình học, bao gồm cả phép chiếu tâm. Mục tiêu chính của chúng tôi là chỉ ra rằng các tính chất của “quẻ” chỉ là một phần biểu hiện của một thực tế tổng quát hơn liên quan đến hình học đại số, một trong những nhánh toán học sâu sắc nhất của thế kỷ 19 và 20. Chúng ta sẽ thấy rằng thực tế tương tự đòi hỏi tính chất chính của phép toán “cộng điểm” trên đường cong bậc ba (các ứng dụng của nó trong lý thuyết số sẽ được thảo luận trong số trước của Kwan).

Trong loạt bài cuối cùng hình, các điểm có ba màu và các đường thẳng nối chúng tạo thành các cấu hình trong đó có sự trùng hợp đáng kinh ngạc của các điểm giao nhau (xuất hiện trong cấu hình của Pappus và Pascal).

Hình 1. Định lý Pascal. Dù sáu điểm được lấy trên đường tròn và dù các số của chúng được đánh số 1, 2, 3, 4, 5, 6 như thế nào thì giao điểm của các đường 12 và 45, 23 và 56, 34 và 61 sẽ nằm trên một đường thẳng (nó được gọi là đường Pascal của hình lục giác sáu khâu nội tiếp 123456). Một công thức khác: giao điểm của các cạnh giả khác của một hình lục giác nội tiếp hoặc phần mở rộng của chúng nằm trên cùng một đường thẳng.

⟦folio 3⟧

Định lý Pappus

Hãy bắt đầu với một định lý tương đối đơn giản về 6 điểm nằm trên hai đường thẳng a và b (hình 2a).

Định lý 1a. Cho các đỉnh của đường gãy kín sáu khâu nằm xen kẽ trên hai đường thẳng. Nếu hai cặp liên kết đối diện của đường đứt đoạn này (1-e và 4-e, 2-e và 5-e) song song thì cặp liên kết còn lại (3-e và 6-e) song song.

Ý tưởng chứng minh cho học sinh sử dụng các phép biến đổi hình học. Cho các đường thẳng a và b cắt nhau tại điểm O (hình 2b). Hãy xem xét hai hình học có tâm O: một hình lấy đường thẳng $A_1B_1$ đến $A_3B_2$ và hình còn lại lấy $A_3B_3$ đến $A_2B_1$. Thành phần của chúng—kết quả của việc thực hiện tuần tự các hình học này—chuyển đường $A_1B_3$ thành $A_2B_2$, do đó $A_1B_3 \parallel A_2B_2$. Lưu ý rằng sẽ thuận tiện khi theo dõi các phép biến đổi của điểm $A_1$ bằng cách áp dụng các hình học theo một thứ tự: $A_1 \rightarrow A_3 \rightarrow A_2$ và các điểm $B_3$ theo thứ tự khác: $B_3 \rightarrow B_1 \rightarrow B_2$. Tất nhiên, kết quả không phụ thuộc vào thứ tự áp dụng hai hình học này: thành phần của chúng cũng là một hình học có tâm O, hệ số của nó bằng tích của các hệ số của hai hình học này. Trong trường hợp các đường a và b song song (hình 2b), theo lý do tương tự, hình học phải được thay thế bằng các phép tịnh tiến song song.

Vì vậy, Định lý 1a đơn giản là một biểu thức hình học

Hình 3. Pappus xác nhận 9 điểm và 9 dòng. Bất kỳ rãnh nào của các điểm $A_1$, $A_2$, $A_3$ và $B_1$, $B_2$, $B_3$ trên đường thẳng a và b, các điểm $C_1$, $C_2$, $C_3$ là giao điểm của đường $A_1B_1$ và $A_3B_2$, $A_2B_2$ và $A_1B_3$, $A_3B_3$ và $A_2B_1$ sẽ nằm trên cùng một đường thẳng (Định lý 1).

tính giao hoán của phép nhân (và phép cộng) các số; điều này giải thích vai trò quan trọng của định lý Pappus trong nền tảng của hình học (ví dụ, xem cuốn sách [5]).

Định lý 6 điểm của Pappus chỉ là một trường hợp rất đặc biệt của một định lý sâu sắc hơn nhiều (cũng được đặt theo tên ông) về một cấu hình gồm 9 điểm và 9 đường thẳng (hình 3).

Định lý 1. Cho ba đường màu đỏ cắt ba đường màu đỏ tại hai điểm thẳng. Nếu hai dãy chấm đen nằm trên hai đường thẳng (trừ đỏ và xanh) thì dãy chấm đen còn lại nằm trên một đường thẳng.

Cấu hình Pappus được thay thế bằng thực tế là cả ba đường thẳng - xanh, đỏ và đen - đều tham gia vào nó: tại mỗi điểm trong số 9 điểm, ba đường thẳng có màu khác nhau giao nhau.

Sau khi bắt đầu xây dựng cấu hình như vậy, chúng ta sẽ thấy rằng nếu sáu điểm đầu tiên $A_1$ được chọn không thành công,

Hình 2. Lục giác Pappus. Các cực của các đỉnh của đường đứt nét $A_1B_1A_2B_2A_3B_3$ nằm xen kẽ trên hai đường thẳng a và b: bốn đường thẳng đầu tiên được chọn tùy ý, sau đó $A_3$ và $B_3$ được dựng sao cho $B_2A_3 \parallel A_1B_1$, $A_3B_3 \parallel B_1A_2$ thì nhất thiết phải là $B_3A_1 \parallel A_2B_2$ (Định lý 1 a). Chứng minh: a), b) biến đẳng thức $OA_1/OA_3 = OB_1/OB_2$ và $OA_3/OA_2 = OB_3/OB_1$; c) cộng các đẳng thức $\overrightarrow{A_1A_3} = \overrightarrow{B_1B_2}$ và $\overrightarrow{A_3A_2} = \overrightarrow{B_3B_1}$, chúng ta thu được $\overrightarrow{A_1A_2} = \overrightarrow{B_3B_2}$.

⟦folio 4⟧

Hình 4. Rút gọn định lý tổng quát Pappus về trường hợp đặc biệt (Định lý 1a). Chúng ta vẽ cấu hình Pappus trên kính hoặc các kích thước tùy ý, đặt trong mặt phẳng nghiêng sao cho đường thẳng $C_1C_2$ nằm ngang và chiếu lên mặt phẳng nằm ngang bằng nguồn sáng $S$ - tâm hình chiếu - nằm phía trên mặt phẳng có cùng độ cao với đường thẳng $C_1C_2$. Phép chiếu tạo ra một kịch bản heskadrama Pappian: các cặp đường thẳng có hướng khác nhau giao nhau tại các điểm $C_1, C_2$ và $C_3$ được chiếu thành các cặp đường thẳng song song, do đó $C_3$ nằm trên đường thẳng $C_1C_2$.

$B_1, A_2, B_2, A_3, B_3$ điểm mới $C_1, C_2, C_3$ có thể nằm xa bản vẽ. Ví dụ: tại $A_1B_1 \parallel A_3B_2$ điểm $C_1$ sẽ chỉ đơn giản là “tiến đến vô cùng”. (Trong trường hợp này, đường thẳng $C_2C_3$ cũng sẽ song song với $A_1B_1$ và $B_2A_3$.) Nếu hai trong ba điểm $C_1, C_2$ và $C_3$ “tiến đến vô cùng”, thì theo Định lý 1 a và điểm thứ ba cũng phải “ở vô cùng”; trong trường hợp này, thật thuận tiện khi nói rằng cả ba điểm $C_1, C_2, C_3$ đều nằm trên cùng một “hình chiếu veclon” (hình 4); các nghệ sĩ kể từ Leonardo da Vinci và Albrecht Dürer đã gọi nó là “phối cảnh tuyến tính”. Hình chiếu có tâm $S$ gán cho mỗi điểm $M$ giao điểm $M'$ của đường thẳng $SM$ với một mặt phẳng nào đó $p$ (mặt phẳng chiếu). Điều quan trọng là trong trường hợp này, ảnh của điểm của một đường thẳng mới nằm trên cùng một đường thẳng, mặc dù một số đường giao nhau biến thành các đường song song (điểm giao nhau của chúng “đi đến vô cùng”) và ngược lại.

Ý tưởng cơ bản của hình học thiết kế của Desargues rất đáng chú ý: bổ sung về mặt tinh thần các “điểm ở vô cực”, trong đó mỗi đường thẳng song song với nhau giao nhau và coi tất cả các điểm này nằm trên một “đường thẳng ở vô cực” - sau đó với hình chiếu tâm của mặt phẳng này lên mặt phẳng khác, không có điểm loại trừ nào phát sinh, sự biến đổi này trở nên có ý nghĩa lẫn nhau. Quan điểm “dự án” này sẽ là chủ đề phụ thường xuyên trong câu chuyện của chúng tôi, nhưng chúng tôi sẽ không phát triển nó một cách chi tiết ở đây (xem [1], [2]).

Cấu hình Pascal

Định lý Pascal có thể có hình thức đầy màu sắc giống như định lý 9 điểm của Pappus.

Định lý 2. Cho ba đường màu đỏ cắt ba nửa đường thẳng tại mười điểm màu đen. Nếu sáu điểm trong số này nằm trên cùng một đường tròn thì ba điểm còn lại nằm trên cùng một đường thẳng (hình 1).

Ở một khía cạnh nào đó, định lý “nghịch đảo” cũng đúng.

Định lý 2'. Nếu trong số các điểm đen mà các vệt đỏ giao nhau bằng ba nửa đường thẳng, có ba điểm nằm trên một đường thẳng và năm điểm còn lại nằm trên một đường tròn thì điểm đó cũng nằm trên cùng một đường tròn.

Như chính Pascal đã ngay lập tức nhận ra, định lý của ông có thể được khái quát hóa một cách đáng kể: cùng với một hình tròn, một hình elip, một hyperbol hoặc một parabol có thể xuất hiện trong đó, hoặc bất kỳ đường cong nào trong số này có thể thu được bằng hình chiếu tâm của một đường tròn. Do đó, từ cấu hình Pascal cho đường tròn, người ta có thể thu được cấu hình cho bất kỳ đường cong nào trong số này.

Tất cả những đường cong này được gọi là đường cong bậc hai, vì từ chúng chúng ta có thể định nghĩa một phương trình có dạng $P(x, y) = 0$, trong đó $P$ là đa thức bậc hai:

$$P(x, y) = ax^2 + bxy + cy^2 + dx + ey + f.$$

Điều tò mò là định lý Pascal vẫn đúng cho trường hợp suy biến khi đa thức $P$ bị phân tách thành hai thừa số tuyến tính: trong trường hợp này bậc hai $P(x, y) = 0$ biến thành một cặp đường thẳng, và định lý Pascal biến thành định lý Pappus.

Có nhiều cách chứng minh khác nhau về định lý Pascal cho đường tròn (ví dụ, xem «Kvant» 1982, số 7, trang 2, sách [1], [2], [3]).

⟦folio 5⟧

Đường cong hình khối

Đường cong đại số có bậc tam giác, hay đường cong bậc ba, là tập hợp các điểm $(x, y)$ thỏa mãn $P(x, y) = 0$, trong đó $P$ là đa thức bậc tam giác: $P(x, y) = ax^3 + bx^2y + \dots + l$ (tổng cộng 10 số hạng). Lưu ý rằng định nghĩa này không phụ thuộc vào việc lựa chọn hệ tọa độ: khi chuyển từ hệ tọa độ này sang hệ tọa độ khác, thậm chí là xiên, tọa độ cũ được thể hiện qua tọa độ mới bằng công thức tuyến tính

$$x = a_1x' + b_1y' + c_1, \quad y = a_2x' + b_2y' + c_2,$$

Trong tọa độ mới, đường cong cũng sẽ được xác định bằng đa thức bậc tam giác.

Một đường cong bậc ba được gọi là có thể rút gọn nếu đa thức $P(x, y)$ bị phân hủy thành tích của các đa thức bậc thấp hơn (thứ nhất và thứ hai) và mặt khác không dẫn điện. Đôi khi chúng ta sẽ biểu thị một đường cong như vậy bằng chữ cái $\Omega$ - một số đường cong hình khối rất đa dạng về hình dạng có dạng dương. Ví dụ: đường cong $(x + 1)(x^2 + y^2 - 1) + \varepsilon = 0$ đối với $\varepsilon$ nhỏ (giả sử $\varepsilon = 0,001$) rất gần với đường cong rút gọn $(x + 1)(x^2 + y^2 - 1) = 0$, bao gồm một đường thẳng $x = -1$ và một đường tròn $x^2 + y^2 = 1$. Nếu khai triển đa thức thành tích của ba đa thức tuyến tính: $P = L_0L_1L_2$ thì đường cong $P(x, y) = 0$ sẽ là giao của ba đường thẳng $L_0 = 0$, $L_1 = 0$, $L_2 = 0$.

Hóa ra là bất kỳ đa thức bậc tam giác nào cũng có thể được biểu diễn dưới dạng tổng của hai đa thức “có thể rút gọn” như vậy; điều này sẽ rõ ràng từ việc chứng minh định lý sau đây về 9 điểm trên một đường cong bậc ba.

Định lý 3. Cho ba đường thẳng cắt ba điểm đen. Nếu bạn dùng ba chấm đen trên một đường cong bậc ba nào đó thì bài giảng thứ chín cũng trên đường cong bậc ba đó.

Trong trường hợp đặc biệt khi đường cong khả quy, điều này dẫn đến định lý Pappus và Pascal: nếu đường cong chia thành ba đường thẳng (màu đen) thì Định lý 3 chuyển thành Định lý 1, và nếu thành đường thẳng và đường cong bậc hai thì chuyển thành Định lý 2 và 2'. Do đó, sau khi chứng minh Định lý 3, chúng ta sẽ thu được tất cả các kết quả trước đó một cách đồng thời và ngay lập tức trong trường hợp tổng quát!

Cho các đường $R_i = 0$ và $L_j = 0$ cắt nhau tại điểm $A_{ij}$ (hình 5; $i$ và $j$ thuộc giá trị 0,1 và 2). Hãy để chúng tôi chứng minh rằng nếu tất cả các điểm $A_{ij}$, ngoại trừ $A_{22}$, nằm trên đường cong bậc ba $P(x, y) = 0$, thì $A_{22}$ cũng vậy. Chúng ta đặt $K = L_0L_1L_2$, $\Gamma = R_0R_1R_2$ và chứng minh rằng với một số số $\lambda$ và $\mu$ thì hành động hiện tại $P = \lambda K + \mu \Gamma$ thỏa mãn. Từ đây sẽ suy ra rằng $P = 0$ nằm tại điểm $A_{22}$: xét cho cùng, $K = 0$ nằm trên đường màu đỏ, $\Gamma = 0$ nằm trên đường màu xanh lam, vì vậy cả hai đẳng thức này đều thỏa mãn tại các điểm màu đen.

Thật thuận tiện khi giả sử rằng các đường $L_0 = 0$ và $R_0 = 0$ là trục tọa độ, do đó $L_0(x, y) = x$, $R_0(x, y) = y$ (điều này có thể đạt được bằng cách thay thế các biến theo công thức (1)); trong khi $K(x, y)$

⟦folio 6⟧

trông giống như
$$x(x - \alpha_1 - \gamma_1 y)(x - \alpha_2 - \gamma_2 y),$$
trong đó $\alpha_1$ và $\alpha_2$ là tọa độ của các điểm $A_{01}$ và $A_{02}$ trên trục $Ox$. Vì đường cong $P(x, y) = 0$ đi qua các điểm $A_{00}$, $A_{01}$ và $A_{02}$ nên đa thức $P(x, 0)$ - tức là $P$, xét trên trục $y = 0$, được tạo thành tại 0 với $x$ bằng 0, $\alpha_1$ và $\alpha_2$, do đó $P(x, 0) = \lambda x(x - \alpha_1)(x - \alpha_2)$ với một số $\lambda$, do đó $P(x, 0) = \lambda K(x, 0)$. Tương tự, chúng ta chứng minh rằng $P(0, y) = \mu \Gamma(0, y)$ đối với một số $\mu$ (ở đây các điểm $A_{00}$, $A_{10}$ và $A_{20}$ được sử dụng).

Bây giờ chúng ta xét đa thức $G = P - \lambda K - \mu \Gamma$. Nó bằng 0 đối với $x = 0$ (xét cho cùng, $K$ chứa đa thức $x$), cũng như đối với $y = 0$, vì vậy nó phải có dạng $G = xyG_1$, trong đó $G_1$ là đa thức bậc không cao hơn một (xét cho cùng, bậc $G$ không cao hơn ba). Mặt khác, tại các điểm $A_{11}$, $A_{12}$ và $A_{21}$, trong đó $G = 0$ và $xy \neq 0$, đa thức $G_1$ phải biến mất và các điểm này không nằm trên cùng một đường thẳng. Điều này chỉ có thể thực hiện được nếu $G_1$ và với nó $G$, giống nhau, bằng 0.

Định lý 3 đã được chứng minh.

Thêm điểm trên đường cong bậc ba

Nhiều tính chất hình học thú vị của đường cong bậc ba, cũng như các ứng dụng khác nhau của chúng trong giải tích, lý thuyết số và thậm chí cả tổ hợp (lý thuyết mã hóa), đều liên quan đến phép cộng điểm. Sự tồn tại của một phép toán tự nhiên như vậy là một tính chất đặc trưng của các đường cong (không thể rút gọn) bậc ba, và định nghĩa hình học của nó dựa trên thực tế là một đường thẳng cắt đường cong $\Omega$ tại hai điểm cũng phải có điểm giao nhau thứ ba với nó. Chúng ta sẽ thấy Định lý 3 thể hiện một tính chất đáng chú ý của phép toán này - tính kết hợp: $A + (B + C) = (A + B) + C$.

Tổng $A + B$ của hai điểm $A, B$ của đường cong $\Omega$ được xác định như sau. Tại $\Omega$ một số điểm “bắt đầu” $E$ được chọn. Sử dụng hai điểm $A, B$, điểm thứ ba $D$ của giao điểm của đường thẳng $AB$ với $\Omega$ được dựng, sau đó là điểm giao nhau thứ ba.

Hình 6. Cộng các điểm trên đồ thị $y = x^3$. Khi các điểm của đồ thị này nằm trên cùng một đường thẳng khi và chỉ khi tổng hoành độ của chúng bằng 0.

Hình 7. Tính kết hợp của phép cộng một điểm trên đường cong bậc ba. Đẳng thức $A + (B + C) = (A + B) + C$ suy ra từ định lý 9 điểm.

các phần có dòng $\Omega$ $DE$; theo định nghĩa, đây là điểm $A + B$.

Các điểm trên đường cong $y = x^3$ (hình 6) đặc biệt dễ cộng: nếu chúng ta lấy gốc tọa độ (0; 0) làm điểm ban đầu $E$ thì tổng của điểm với hoành độ $x_1$ và $x_2$ sẽ là điểm có hoành độ $x_1 + x_2!$. Thật vậy, ba điểm $A(x_1; x_1^3), B(x_2; x_2^3), D(x_3; x_3^3)$ nằm trên cùng một đường thẳng nếu điều kiện được thỏa mãn

$$\frac{x_1^3 - x_2^3}{x_1 - x_2} = \frac{x_2^3 - x_3^3}{x_2 - x_3},$$

mà sau khi đơn giản hóa có dạng

$$x_1 + x_2 + x_3 = 0;$$

và vì $E$ là tâm đối xứng của đồ thị $y = x^3$ nên điểm $A + B$ (điểm giao thứ ba của đường thẳng $DE$ với đồ thị này) có tọa độ $(-x_3; -x_3^3)$, tức là trục hoành $-x_3 = x_1 + x_2$.

Để thao tác cộng điểm xác định cho hai điểm bất kỳ, cần làm rõ một số điểm: xét các điểm tiếp tuyến của các đường có $\Omega$ là điểm giao nhau kép (và đối với các điểm giao nhau - gấp ba), thêm các điểm “vô nghĩa” vào đường cong, loại bỏ các điểm “đặc biệt” xuất hiện trên một số đường cong. Điều này đã được thảo luận chi tiết hơn ở bài 10. P. Solviev ở số trước «Kvant».

Đối với phép cộng như vậy, một điểm trên đường cong $\Omega$ có tính chất giao hoán $A + B = B + A$ rất/không (đường $AB$ trùng với đường $BA$). Nhưng tính kết hợp không dễ chứng minh. Điều này có thể được thực hiện bằng Định lý 3 bằng cách vẽ 7 đường thẳng (hình 7). Theo định lý này, điểm $X$ giao điểm của các đường nối $A$ với $B + C$ và $A + B$ với $C$ nằm trên $\Omega$ nên

$$A + (B + C) = (A + B) + C = Y.$$

Xây dựng đa giác

Chúng ta hãy gọi một đa giác là bộ ba chuỗi vô hạn các điểm trên mặt phẳng - đỏ ($A_k$), đen ($B_l$) và xanh lam ($C_m$), thỏa mãn điều kiện sau: nếu $k + l +$

⟦folio 7⟧

+m=0 thì các điểm $A_k$, $B_l$ và $C_m$ cùng nằm trên một đường thẳng ($k, l, m=0, \pm 1, \pm 2, \dots$).

Cấu hình vô hạn này được dành riêng cho bài toán M585 của "Bài toán Lượng tử". (Điều thú vị là tác giả của bài toán V.V. Batyrev đã viết cho chúng tôi bài toán khi anh ấy vẫn còn là học sinh lớp 10, và bây giờ anh ấy đã tốt nghiệp cơ chế của Đại học quốc gia Moscow và trở thành trợ lý nghiên cứu của anh ấy - chuyên về hình học đại số.) Hình đa giác đơn giản nhất rất dễ xây dựng trên giấy ca rô (hình 8), nhưng hóa ra có rất nhiều đa giác khác nhau và mô tả của chúng về định lý không phải lúc nào cũng nhất quán với toàn bộ nội dung thống kê của chúng ta, kể cả việc “cộng điểm” trên đường cong bậc ba.

Hãy thử kiểm tra bằng thực nghiệm và sau đó chứng minh các nhận định sau (hình 9-11 sẽ giúp giải quyết vấn đề này, trong đó mô tả một số ví dụ về đa giác; các số chỉ được đặt ở một số điểm đầu tiên - phần còn lại có thể dễ dàng khôi phục từ chúng).

1. Đối với ba đường thẳng $a, b, c$ bất kỳ, sử dụng các điểm cho trước tùy ý $A_0$ (trên $a$), $B_0$ và $B_1$ (trên $b$), một đa giác duy nhất được xây dựng trong đó tất cả các điểm $A_k$ nằm trên $a, B_l$ trên $b$ và $C_m$ trên $c$.

2. Cho một đường tròn $\sigma$ (nó cũng có thể là hình elip, hyperbol hoặc parabol) và ba điểm: $A_0$ trên $\sigma$, $B_0$ và $B_1$ không nằm trên $\sigma$. Sau đó, có một đa giác duy nhất trong đó tất cả các điểm $A_k$ và $C_m$ nằm trên $\sigma$ và $B_l$ trên đường thẳng $B_0B_1$.

3. Nếu một đường cong bậc ba tối giản $\Omega$ được cho và có ba điểm $A_0, B_0$ và $B_1$ trên đó, thì từ chúng, đa giác nằm trên $\Omega$ có thể được xây dựng lại một cách duy nhất và nó có thể được viết dưới dạng bộ ba cấp số tranh luận $A_k=A_0+kD$, $B_l=B_0+lD$, $C_m=C_0+mD$ (D là một điểm trên $\Omega$, được xác định bởi điều kiện $B_0+D=B_1$); tuy nhiên, nếu D là một điểm trên đường cong (không số ít) $\Omega$ sao cho $nD=D+\dots+D=E$, thì đa giác sẽ không phải là vô hạn mà là tuần hoàn (các cấu hình như vậy được xem xét trong bài viết [4] liên quan đến bài toán có bao nhiêu rãnh từ một số điểm nhất định trong mặt phẳng có thể nằm trên các đường thẳng).

4. Cho sáu điểm $A_0, A_{-1}, A_1, B_0, B_1$ và $B_2$ trên mặt phẳng (ở vị trí tổng quát). Bằng cách sử dụng chúng, một đa giác được xây dựng lại một cách duy nhất, tất cả các điểm trong đó tự động xuất hiện trên một đường cong không đơn lẻ.

Để chứng minh các phát biểu chung về polygram, các thông báo sau đây rất hữu ích. Hình chiếu trung tâm của bất kỳ hình đa giác nào cũng là một hình đa giác. Mỗi 9 điểm của đa giác $A_k, A_{k+r}, A_{k+s}, B_l, B_{l+r}, B_{l+s}, C_m, C_{m+r}, C_{m+s}$, trong đó $k+l+m+r+s=0$, tạo thành một cấu hình thỏa mãn các điều kiện của Định lý 3; đặc biệt, đối với một đa giác trên ba đường thẳng (hình 9) chúng tạo thành 9 điểm

Hình 8. Ví dụ về đa hình. Cho vô số chuỗi các điểm đỏ, đen và xanh, được đánh số bằng số nguyên, chúng tạo thành một đa giác: ba điểm khác nhau $A_k, B_l$ và $C_m$ nằm trên cùng một đường thẳng nếu tổng các số $k+l+m$ của chúng bằng 0. (Trong ví dụ này, $B_{-k-m}$ là trung điểm của đoạn $A_kC_m$ với mọi $k$ và $m$).

Hình 9. Đa giác trên ba đường thẳng. Trên mỗi điểm đó, có vô số cách để chọn ba điểm thuộc các điểm khác nhau, đóng vai trò là các đỉnh của cấu hình Papna gồm 9 điểm.

a) Tập hợp các điểm đỏ và xanh là hệ mét đối với mỗi điểm đen $B_l$, với hệ số mét bằng $k_n=k_0q^l$.

b) Đa giác này, được sắp xếp hoàn toàn thành ba cực, có thể thu được tập trung bởi các số 1, 1/2, 1/3, ….

Cũng có thể xây dựng các đa giác trên ba đường thẳng cắt nhau thành từng cặp tại ba điểm khác nhau. Các đa giác như vậy có thể thu được tập trung theo số 1, 1/2, 1/3, ….

⟦folio 8⟧

Hình 10. Đa giác trên đường thẳng và đường tròn (hình 10) - Cấu hình Pascal.

Có vô số cách để làm nổi bật cấu hình Pascal.
a) Tỷ lệ khoảng cách từ các điểm của mỗi cet đến các đầu của đường kính PQ: $A_kP/A_kQ$, $C_mP/C_mQ$ và $B_lQ/B_lP$ tạo thành các mặt cắt hình học có cùng giá trị q.

6) Nếu bát quái này được thiết kế sao cho đường thẳng b với các chấm đen hiển thị ở khoảng cách vô hạn và vòng tròn - lại thành một vòng tròn, thì hình ảnh của các điểm màu (cũng như đầu) với các số liền kề sẽ cách nhau một cung $\Theta \cdot 360^\circ$ của vòng tròn; với $\Theta$ có thể chơi được, các chấm màu đỏ và xanh lam sẽ lấp đầy vòng tròn và với $\Theta$ hợp lý, đa giác sẽ trở thành tuần hoàn.

Hình 11. Đa giác trên biểu đồ $y=x^3 - ax$. Hình chiếu của các điểm của mỗi cet lên tiếp tuyến Ot theo hướng của trục Oy tạo thành một chuỗi các điểm đẳng lịch sử - một đường cắt số học.

Cấu hình Pascal và cho đa giác trên đường thẳng và đường tròn (hình 10) - Cấu hình Pascal.

Thang điểm với số nguyên phát sinh trong quá trình xây dựng đa giác cho thấy rằng có sự tương tự liên tục của đa giác; trên thực tế, hóa ra các điểm của bất kỳ đường cong bậc ba nào - có thể rút gọn hoặc không thể rút gọn - $\Omega$ đều có thể được liên kết với các giá trị số ​​$t$ - đưa ra một “tham số hóa tốt” trên đường cong $\Omega$ - sao cho đối với bất kỳ đường thẳng nào cắt nhau $\Omega$ tại ba điểm có tham số $t_1, t_2, t_3$, điều kiện $t_1 + t_2 + t_3 = 0$ được thỏa mãn. (Nếu đường cong $\Omega$ chứa một hình bầu dục, một hình tròn ở hình 106 thì giá trị của tham số $t$ được xác định bằng phép cộng bội số nguyên của “dấu chấm”, $T$, tại đó giá trị $t$ thay đổi khi đi quanh hình bầu dục.) Như chúng ta đã thấy (hình 6), trên đường cong $y=x^3$ “tham số tốt” là hoành độ của điểm $(x, y)$. Hãy đưa ra một ví dụ khác. Cho $\Omega$ gồm ba đường thẳng $AB, BC, CA$. Điều kiện để các điểm $M, N, L$ lần lượt nằm trên các đường thẳng này nằm trên cùng một đường thẳng có dạng

$$\frac{MA}{MB} \cdot \frac{NB}{NC} \cdot \frac{LC}{LA} = 1$$

(Định lý Menelaus). Ở đây, “tham số tốt” $t$ trên mỗi dòng có thể được coi là logarit của tỷ lệ tương ứng: nếu tích của ba số là 1 thì tổng logarit của chúng là 0. Theo cách tương tự, bạn có thể biểu thị rõ ràng “tham số hóa tốt” cho các đường cong khối đặc biệt và có thể rút gọn khác, chẳng hạn như $y^2=x^3$ và “lá Descartes” $y^2=x^3-x^2$ (xem trang đầu tiên của cuốn sách [6]).

Đối với các đường cong bậc ba tối giản, sự tồn tại của một “tham số hóa tốt” có liên quan chặt chẽ đến hoạt động của phép cộng điểm và biểu thức rõ ràng của nó đòi hỏi phải làm quen với lý thuyết về hàm elip, một lĩnh vực giải tích toán học hay đã được nghiên cứu bởi nhiều nhà toán học vĩ đại nhất thế kỷ 19.

Gần đây (1976), nhà toán học người Mỹ F. Griffithist đã lưu ý rằng một "tham số hóa tốt" đã được viết - một tính chất đặc trưng của các đường cong danh nghĩa bậc ba: nếu ba đoạn đường cong có tham số $t_1, t_2$ và $t_3$ nằm trên mặt phẳng, sao cho qua mỗi điểm của một trong số chúng có thể vẽ một đường thẳng cắt nhau, đồng thời điều kiện luôn được thỏa mãn đối với các tham số của ba điểm giao nhau $t_1+t_2+t_3=0$, thì cả ba phần này được chứa trong một đường cong hình khối. (Đây là một sự tương tự liên tục của tuyên bố rằng bất kỳ đồ thị nói dối nào cũng nằm trên một đường cong hình khối.)

1. Yaglom I. M. Các phép biến đổi hình học, phần II - M.: Leningrad: Gostekhidat, 1956.
2. Prasolov V.V. Bài toán về phép đo mặt phẳng, phần II - M.: Nayka, 1986.
3. Sharygin I.F. Bài toán trong hình học. Phép đo phẳng. - M.: Nayka, 1986.
4. Vườn hoa toán học. - M.: Mir, 1983 (bài viết của S. Barr “Cách nhận biết cây”, trang 117-129).
5. Artin E. Đại số hình học. - M.: Nayka, 1969.
6. Shafarevich I. R. Nguyên tắc cơ bản của hình học đại số. - M.: Nayka, 1972 (và kế hoạch 1988).
