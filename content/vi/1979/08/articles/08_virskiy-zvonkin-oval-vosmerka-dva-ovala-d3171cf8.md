---
id: 1979-8-virskiy-zvonkin-oval-vosmerka-dva-ovala-d3171cf8
issue: kvant_1979_8
year: 1979
number: "8"
title: Hình bầu dục, hình số tám, hai hình bầu dục...
authors:
  - Вирский А.
  - Звонкин А. К.
rubric: osnovnye-stati
page_first: 23
page_last: 27
page_labels: 21-25
tag: S0H8
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 04a4835b177634202edc114769ce32a393c77a30b8c2075afd6743de38d951b9
prompt_sha256: draft-1
translated_from: content/ru/1979/08/articles/08_virskiy-zvonkin-oval-vosmerka-dva-ovala-d3171cf8.md
source_content_sha256: db4fae26fc8bdd094e809bd0d33e3344074c9ae116ae65366d8386163602d565
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 21⟧

Hình bầu dục, hình số tám, hai hình bầu dục...

Bài viết này thảo luận về các ví dụ về đường cong đại số theo thứ tự thứ năm. Hãy nhớ lại rằng đường cong đại số cấp n-zo được gọi là đồ thị của phương trình $p_n(x,y) = 0$, trong đó $p_n(x,y)$ là đa thức bậc n trong các biến $x, y$). Ví dụ, đường cong đại số bậc nhất là một đường thẳng; các đường cong đại số bậc hai, đặc biệt là các đường elip, hyperbola, parabola - những đường cong mà bạn đã biết có một số tính chất đáng chú ý **).

Thú vị hơn và cũng chưa được nghiên cứu đầy đủ là các đường cong có bậc cao hơn. Chỉ cần nói rằng “bài toán thứ mười sáu của Hilbert” nổi tiếng cho trường hợp đường cong bậc sáu chỉ mới được giải gần đây, và đối với những bài toán lớn, vẫn còn nhiều bài toán được xây dựng đơn giản nhưng chưa được giải. Tuy nhiên, chúng ta sẽ nói về vấn đề này chi tiết hơn trong phần Aftermath và bây giờ hãy chuyển sang các ví dụ đã hứa.

*) Chúng ta hãy nhớ bậc của đa thức của hai biến là bao nhiêu. Bậc của đơn thức $a \cdot x^k y^l$ được gọi là số $k+l$ (ví dụ $xy$ là đơn thức bậc 2). Bậc của đa thức là bậc lớn nhất của các đơn thức của nó (ví dụ: đa thức $p(x, y) = x^3 + 2xy^4 + 11y^2 - xy$ có bậc 5).

**) Xem «Kvant», 1975, số 2 1, 3, 4.

Hãy thay đổi một từ

Định nghĩa hình học của hình elip đã được biết rõ: hình elip là một tập hợp các điểm (trên một mặt phẳng), với tổng khoảng cách từ đó đến điểm $F_1$ và $F_2$ được xây dựng: $|MF_1| + |MF_2| = 2a$. Lưu ý một từ trong định nghĩa này:

$$|MF_1| \cdot |MF_2| = a^2.$$ (1)

Các điểm $F_1$ và $F_2$, giống như các điểm của hình elip, được gọi là tiêu điểm. Cassini Oval ra đời do một sai lầm. Nó được “phát minh” bởi nhà thiên văn học người Pháp (tên khai sinh là người Ý) Jean Dominic Cassini (1625-1712). Nhà khoa học xuất sắc này, thành viên của Viện Hàn lâm Khoa học Paris, giám đốc Trường Tổng hợp Paris, người đã phát hiện ra chuyển động quay của Sao Mộc và Sao Hỏa, cũng như 4 vệ tinh của Sao Thổ, vì lý do nào đó đã tin rằng quỹ đạo Trái đất có hình dạng chính xác như vậy. Sự phát triển hơn nữa của khoa học cho thấy rằng đáp số càng chính xác thì sẽ là một hình elip tổng quát. Nhưng hình bầu dục Cassini vẫn còn sống. Thực tế là nó có một đặc tính đáng chú ý.

Chúng ta hãy biểu thị khoảng cách giữa các tiêu điểm bằng 2c và xây dựng phương trình cho hình bầu dục Cassini trong hệ tọa độ trong đó $F_1(-c;0)$, $F_2(c;0)$. Thay thế

⟦folio 22⟧

$$|MF_1| = \sqrt{(x+c)^2 + y^2}, \quad |MF_2| = \sqrt{(x-c)^2 + y^2}$$

thành đẳng thức (1) và bình phương, sau khi biến đổi ta thu được

$$(x^2 + y^2 + c^2)^2 - 4c^2x^2 = a^4.$$

Kết quả là một phương trình bốn độ. Loại đường cong cụ thể phụ thuộc và được đặt vào những giá trị mà chúng ta chọn cho tham số $a$ và $c$. Ví dụ: hãy sửa $a$ và tăng $c$ (bạn có thể làm ngược lại: sửa $c$ và giảm $a$—kết quả sẽ giống nhau; xem Hình 1). Đây là nơi điều thú vị nhất sẽ xảy ra: giống như một miếng bột được kéo căng theo các hướng khác nhau, hình bầu dục đầu tiên sẽ dài ra, sau đó sẽ có “vòng eo”, nó sẽ mỏng hơn, cho đến khi cuối cùng hình của chúng ta bị xé thành hai phần, thành hai hình bầu dục nhỏ hơn. Một bức tranh chính xác hơn sẽ như thế này (Hình 2):

1) tại $c=0$ - vòng tròn;
2) tại $0 < c \leq \frac{a}{\sqrt{2}}$ - hình bầu dục lồi, tương tự hình elip;
3) tại $\frac{a}{\sqrt{2}} < c < a$ - hình bầu dục với “câu chuyện”;
4) tại $c=a$ - “nằm tám” (nó có tên riêng - Lemissama của Bernoulli);
5) tại $c>a$ - hai hình bầu dục; một trong số chúng chứa điểm $F_1$, cái còn lại chứa điểm $F_2$.

Tính chất “phân chia” được chỉ định của các hình bầu dục Cassinni lần đầu tiên được phát hiện và nghiên cứu chi tiết bởi một nhà khoa học người Pháp khác - Jean Paul de Gua de Malves (1712-1785). Công trình của ông là một trong những công trình đầu tiên nghiên cứu các điểm kỳ dị của các đường cong đại số (điểm kỳ dị trong trường hợp này là điểm tự giao nhau tại $c=a$). Từ những công trình như vậy, một nhánh rộng lớn của toán học hiện đại đã ra đời - hình học đại số.

Ví dụ thứ hai

Bây giờ chúng ta hãy xem xét tập các thùy $M$ mà tổng các đại lượng có hình dạng như các hình vuông được xét từ

$$\frac{1}{|MF_1|^2} + \frac{1}{|MF_2|^2} = \frac{1}{b^2}.$$

Như trước đây, chúng tôi đặt $|F_1F_2|=2c$. Thay các công thức của $|MF_1|$ và $|MF_2|$ vào (2), ta thu được phương trình $$\frac{1}{(x+c)^2 + y^2} + \frac{1}{(x-c)^2 + y^2} = \frac{1}{b^2}.$$

Câu hỏi bảo mật. Tại sao phương trình (3) là phương trình bốn?

Hoạt động của đường cong thu được rất gợi nhớ đến hình bầu dục Cassinni. Hình 3 mô tả các “giai đoạn chia” liên tiếp mà đường cong trải qua khi tham số $c$ tăng (tham số $b$ không đổi). Chúng ta hãy xem xét quá trình này chi tiết hơn một chút.

⟦folio 23⟧

Cắt bánh mì tròn

Một ý tưởng hình học đơn giản cho phép chúng ta xây dựng một ví dụ khác tương tự như các ví dụ trước. Hãy lấy mor - bề mặt lấp đầy chiếc bánh rán; bề mặt này có được bằng cách quay một đường tròn xung quanh một đường thẳng không cắt nó (và nằm trong cùng mặt phẳng với đường tròn). Chúng ta sẽ cắt hình xuyến với các mặt phẳng song song với nhau và song song với trục quay (Hình 4). Nếu nhấc mặt phẳng cắt lên trên, chúng ta sẽ thấy hình ảnh quen thuộc: lúc đầu mặt cắt sẽ có hình bầu dục lồi, kích thước tăng dần; khi đó hình bầu dục sẽ có phần eo, nó sẽ trở nên mỏng hơn, hình bầu dục sẽ biến thành số tám và số tám sẽ chia thành hai hình bầu dục. Ở đầu hình xuyến, toàn bộ quá trình sẽ được lặp lại theo thứ tự ngược lại: hai hình bầu dục sẽ “lớn lên” thành số tám, số tám sẽ biến thành hình bầu dục có thắt lưng, v.v.

Bây giờ hãy dịch những điều kỳ diệu về hình học của chúng ta sang ngôn ngữ đại số.

Chúng ta hãy rút ra phương trình hình xuyến cho việc này. Cho các trục tọa độ có hướng như Hình 4; đặc biệt trục quay của hình xuyến trùng với trục Oy. Chúng ta hãy cắt hình xuyến với một mặt phẳng tùy ý đi qua trục Oy và xem xét một trong các đường tròn thu được (Hình 5). Phương trình của cô ấy

$$(t-R)^2+y^2=r^2.$$

Ở đây, bằng $r$ chúng ta biểu thị bán kính của hình tròn và $R$ khoảng cách từ tâm của nó đến trục Oy. Nếu bây giờ chúng ta nhớ lại

⟦folio 24⟧

Cơm. 5.

sợi dây $t$ là khoảng cách từ điểm $(x, y, z)$ đến trục $Oy$, tức là $t = \sqrt{x^2 + z^2}$, ta được phương trình:

$$(\sqrt{x^2 + z^2} - R)^2 + y^2 = r^2.$$ (4)

Nếu (4) được giải phóng khỏi căn thức, chúng ta thu được phương trình bậc bốn. Bây giờ, để “đại số” cắt hình xuyến (mặt phẳng $z=c$, theo phương trình 4) cùng với $z$, chúng ta thay thế $c$.

Bài toán 3. Xét (dùng Hình 4) hình dáng của đường cong cho bởi phương trình

$$(\sqrt{x^2 + c^2} - R)^2 + y^2 = r^2,$$

cho $c$ khác nhau.

Bài toán 4*. Hãy xem xét "hình bầu dục có eo"

$$\frac{1}{(x-1)^2 + y^2} + \frac{1}{(x+1)^2 + y^2} = 1.$$

Hãy di chuyển nó sang phải 3 đơn vị (thay thế $x$ bằng $x-3$):

$$\frac{1}{(x-4)^2 + y^2} - \frac{1}{(x-2)^2 + y^2} = 1;$$

bây giờ nó không giao nhau với trục $Oy$. Chúng ta tạo thành một bề mặt giằng bằng cách xoay hình bầu dục này quanh trục $Oy$; phương trình của bề mặt này thu được nếu chúng ta thay thế $\sqrt{x^2 + z^2}$ cùng với $x$; nếu được giải phóng khỏi các gốc (điều này không cần thiết), bạn sẽ nhận được phương trình bậc tám. Kiểm tra hình thức (hình học) của các phần trên bề mặt này của mặt phẳng $z=c$ để biết $c$ khác nhau.

hậu quả

Và bây giờ - phần thú vị nhất. Trong các ví dụ của chúng tôi, một đường cong bậc bốn, nếu nó không có các điểm tự giao nhau, sẽ bao gồm một hoặc hai hình bầu dục (bây giờ chúng ta cũng sẽ coi hình bầu dục có thắt lưng là hình bầu dục). Bạn có thể muốn biết số lượng hình bầu dục tối đa cho một đường cong theo thứ tự này là bao nhiêu và cách chúng có thể được định vị tương đối với nhau. Đây là những gì chúng ta sẽ tìm hiểu bây giờ, nhưng trước tiên chúng ta lưu ý rằng hai câu hỏi này có ý nghĩa khi xây dựng một đường cong cấp bốn bất kỳ; trên thực tế, các nhà toán học đã tự hỏi mình những câu hỏi này từ lâu.

Trở lại năm 1876, A. Harnack đã chứng minh rằng số lượng hình bầu dục tối đa mà một đường cong có bậc $n$ có thể bao gồm là $\frac{(n-1)(n-2)}{2} + 1$.

Đặc biệt, đối với $n=4$ có 4 hình bầu dục, đối với $n=6-11$ hình bầu dục, đối với $n=8-22$ hình bầu dục, v.v. Vấn đề về vị trí tương đối của chúng hóa ra phức tạp hơn nhiều. Vào đầu năm cấp bằng của chúng tôi, vào năm 1900, tại Đại hội Toán học Thế giới lần thứ hai, nhà toán học vĩ đại người Đức D. Hilbert đã đưa ra 23 bài toán quan trọng mà ông cho là quan trọng nhất đối với sự phát triển của toán học thế kỷ 20. Câu hỏi mà chúng ta quan tâm đã được đưa vào danh sách của Hilbert ở vị trí thứ 16. Kể từ đó, bài toán thứ mười sáu của Hilbert vẫn không ngừng tác động đến toán học. D. A. Gudkov cách đây hơn 10 năm. Đối với 11 hình bầu dục, xuất hiện ba loại vị trí tương đối

⟦folio 25⟧

Chức vụ; chúng được hiển thị dưới dạng sơ đồ trong Hình 6 (các cấu hình có ít hình bầu dục hơn không được hiển thị vì có quá nhiều cấu hình; tổng cộng, cùng với các khay được chỉ định, có thể có 56 cấu hình khác nhau). Bạn khó có thể tìm được bằng chứng; Nhưng trước tiên, chúng tôi sẽ thực hiện một nghiên cứu tương tự hoàn chỉnh cho các đường cong bậc bốn. Để làm điều này, bạn được yêu cầu giải bài toán dưới đây.

Câu 5 (dễ). Xây dựng một ví dụ về đường cong bậc bốn bao gồm hai hình bầu dục đặt vào nhau.

Câu 6 (khó). Xây dựng một ví dụ về đường cong bậc bốn với bốn hình bầu dục. (Được biểu thị bằng e. Bắt đầu với một cặp hình elip giao nhau và điều chỉnh phương trình sao cho “bông hoa” trong Hình 7 cháy thành bốn cánh hoa màu xanh lam.)

Vấn đề 7 (theo mức độ của vấn đề trước). Xây dựng một ví dụ về đường cong bậc bốn với các hình bầu dục ở khay.

Nếu bạn giải được bài toán 6, 7 (hoặc nhìn trộm vào đáp số), bạn có thể nhận thấy rằng không có hình bầu dục nào nằm trong hình kia. Đây không phải là tai nạn:

Bài toán 8. Chứng minh rằng đường cong bậc bốn chứa hai hình bầu dục xen kẽ nhau không còn chứa điểm nào khác. (Biểu thị bằng e. Chứng minh rằng mọi đường thẳng cắt đường cong bậc 4 tại nhiều nhất 4 điểm.)

Vấn đề mà chúng tôi quan tâm đã được điều tra đầy đủ, nếu kết quả cuối cùng

Câu 9 (rất khó). Chứng minh rằng một đường cong bậc bốn không thể chứa nhiều hơn bốn hình bầu dục. (Chỉ ra và e. Tận dụng thực tế là có đúng một đường cong bậc hai đi qua bất kỳ điểm nào.)

Nhiệm vụ cho độc giả của chúng tôi

(Để bắt đầu, xem trang 17)

b) $|AG_c|^2 \cdot \text{tg} \frac{\hat{A}}{2} + |BG_a|^2 \cdot \text{tg} \frac{\hat{B}}{2} + |CG_b|^2 \cdot \text{tg} \frac{\hat{C}}{2} = |AN_c|^2 \cdot \text{tg} \frac{B}{2} + |BN_a|^2 \cdot \text{tg} \frac{\hat{C}}{2} + |CN_b|^2 \cdot \text{tg} \frac{\hat{A}}{2} = |AN_b|^2 \cdot \text{tg} \frac{\hat{C}}{2} + |BN_c|^2 \cdot \text{tg} \frac{\hat{A}}{2} + |CN_a|^2 \cdot \text{tg} \frac{\hat{B}}{2} = S,$

trong đó $S$ là diện tích tam giác $ABC$.

2. Từ các đỉnh $B$ và $C$ (C và A, A và B) của tam giác $ABC$, vuông góc với các cạnh $AB$ và $CA$ (BC và AB, CA và BC tương ứng) được khôi phục cho đến khi chúng cắt đường phân giác của góc $\hat{A}$ ($\hat{B}, \hat{C}$, tương ứng) tại các điểm $B_a$ và $C_a$ ($C_b$ và $A_b$, $A_c$ và $B_c$). Gọi $h_a, h_b, h_c$ lần lượt là độ dài của các độ cao bị bỏ qua khỏi các đỉnh $A, B$ và $C$; $a, b, c$ - độ dài các cạnh $BC, CA$ và $AB$, $r$ - bán kính của hình tròn nội tiếp tam giác $ABC$, $p$ - nửa chu vi của nó. Chứng minh rằng:

a) $\frac{1}{h_a |CC_b|} + \frac{1}{h_b |AA_c|} + \frac{1}{h_c |BB_a|} = \frac{1}{h_a |BB_c|} + \frac{1}{h_b |CC_a|} + \frac{1}{h_c |AA_b|} = \frac{1}{2r^2};$

b) $\frac{ab^3}{|CA_c|^2} + \frac{bc^3}{|AB_a|^2} + \frac{ca^3}{|BC_b|^2} = \frac{a^3b}{|CB_c|^2} + \frac{b^3c}{|AC_a|^2} + \frac{c^3a}{|BA_b|^2} = p^2.$

3. $A_0, B_0$ và $C_0$ lần lượt là đáy của các đường cao của tam giác nhọn $ABC$, được thả từ các đỉnh $A, B$ và $C$. Các đường thẳng nối các đỉnh $A, B$ và $C$ với tâm của đường tròn ngoại tiếp tam giác $ABC$ cắt các đường thẳng $B_0C_0, C_0A_0$ và $A_0B_0$ lần lượt tại các điểm $M_a, M_b$ và $M_c$. Chứng minh đẳng thức:

a) $|M_aB_0| = |M_bA_0|, |M_cB_0| = |M_aB_0|, |M_cA_0| = |M_aC_0|;$

b) $|M_aB_0| + |M_bC_0| + |M_cA_0| = d,$

trong đó $d$ là độ dài của đoạn nối hai cạnh đáy của góc nhọn $ABC$ với hai cạnh còn lại của nó.

U. Alla (Võru)
