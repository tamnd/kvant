---
id: 1974-12-priyatel-reshenie-logicheskih-zadach-pri-pomoschi-grafov-s-tsvetnyimi-vershinami-2ac638e4
issue: kvant_1974_12
year: 1974
number: "12"
title: Lời giải logic bài toán sử dụng đồ thị có các đỉnh được tô màu
authors:
  - Приятель А.
rubric: osnovnye-stati
page_first: 17
page_last: 24
page_labels: 15, 16, 17, 18, 20, 21, 22
tag: HG0I
lang: vi
source: kvant_digital
extraction: vision
content_sha256: bdd9196f7de9edf0995312d6193f3f93053a929eaf387929e283e79f932c2fe4
prompt_sha256: draft-1
translated_from: content/ru/1974/12/articles/06_priyatel-reshenie-logicheskih-zadach-pri-pomoschi-grafov-s-tsvetnyimi-vershinami-2ac638e4.md
source_content_sha256: 7dfe36de8ce73c0523f8e300fcd8832f9fa98f2dc974e19f60eee0f513586071
translation_model: draft
translation_run: vi-draft-2026-11-03
translation_quality: draft
---

⟦folio 15⟧

Trong «Kvant» số 8 năm 1973, một bài báo của L. Yu. Berezina “Trên đồ thị có cạnh màu” đã được xuất bản, dành riêng cho lời giải logic bài toán. Không kém phần thú vị là phương pháp lời giải logic bài toán sử dụng đồ thị có các đỉnh được tô màu, cho phép bạn tìm nghiệm của bài toán, thường được Johnson và Smith gọi là “logic bài toán” *). Phương pháp này bao gồm việc mô tả cấu trúc của bài toán bằng một số biểu đồ. Các đỉnh của đồ thị như vậy sẽ biểu thị các phát biểu cơ bản bài toán; và các cạnh của biểu đồ là hàm ý hoặc mối liên hệ giữa các câu lệnh cơ bản. Màu sắc của đỉnh sẽ cho biết sự thật hay sai lầm của tuyên bố được mô tả. Phương pháp được mô tả bao gồm việc xác định màu của các đỉnh của đồ thị. Trong suốt phần sau đây, chúng ta sẽ gọi quá trình xác định màu của đồ thị các đỉnh là màu. Màu của đỉnh không phải lúc nào cũng được xác định một cách duy nhất; có lẽ chúng ta sẽ gọi là tô màu varnatas.

Để mô tả cấu trúc bài toán bằng biểu đồ, chúng ta sẽ thống nhất một ký hiệu cho phép chúng ta thay đổi từ ngôn ngữ logic sang ngôn ngữ biểu đồ:

Bảng 1

Khái niệm logic Phần tử đồ thị

Phát biểu Đỉnh của đồ thị
Phát biểu đúng Mặt trên màu đỏ
Câu sai Top đen
Hàm ý $X \Rightarrow Y$ Cạnh định hướng $\overrightarrow{XY}$ của đồ thị

Việc tô màu đồ thị được thực hiện theo các quy tắc đại số logic được dịch sang ngôn ngữ đồ thị bằng các ký hiệu sau:

Bảng 2

Quy tắc đại số logic Quy tắc tô màu đồ thị

1. Mỗi phát biểu có một và chỉ một trong hai giá trị chân lý: “false”, “true”.
2. Nếu hàm ý $X \Rightarrow Y$ đúng và tiền đề $X$ đúng thì kết luận $Y$ đúng.
3. Nếu hàm ý $X \Rightarrow Y$ đúng và kết luận $Y$ sai thì tiền đề $X$ sai.

1. Mỗi đỉnh của đồ thị có màu đen hoặc đỏ.
2. Nếu cạnh $\overrightarrow{XY}$ hướng từ đỉnh $X$ đến đỉnh $Y$ và đỉnh $X$ có màu đỏ thì đỉnh $Y$ có màu đỏ.
3. Nếu cạnh $\overrightarrow{XY}$ được định hướng từ đỉnh $X$ đến đỉnh $Y$ và $Y$ có màu đen thì $X$ có màu đen.

*) Tất nhiên, bạn có thể nói về “các vấn đề về Vorobyov và Grachev” - mọi người đều nhớ đến đoạn nhại lại họ từ “The Golden Calf”.

⟦folio 16⟧

Ngoài các quy tắc 1–3 này, các quy tắc bổ sung có thể được đưa ra cho từng bài toán cụ thể (tùy thuộc vào cấu trúc của biểu đồ được sử dụng).

Hãy để chúng tôi chứng minh phương pháp này bằng các ví dụ về lời giải cụ thể bài toán.

Bài toán 1

Đối với một cuộc thám hiểm vượt qua tất cả các giả định $A, B, C, D, E, F, G$ và $H^*$, sáu chuyên ngành phải được hiển thị: sinh học, hydroLOGa, cyoptics, bác sĩ, cơ khí và radio. Nhiệm vụ của sinh học có thể được thực hiện bởi $E$ và $G$, hydroLOGа - $B$ và $F$, syoptics - $F$ và $G$, bác sĩ - $A$ và $D$, phóng xạ - $C$ và $D$, cơ học - $C$ và $H$. Mặc dù một số tuyên bố tương thích với hai chuyên ngành, nhưng trong mỗi chuyến thám hiểm chỉ phải thực hiện một nghĩa vụ.

Đây là người nên được đưa vào chuyến thám hiểm nếu chúng ta không muốn đưa $F$. Chúng tôi không muốn đi mà không có $B$, $D$ không có $H$ và không có $C$, $C$. Chúng tôi không muốn chọn $G$ và chúng tôi không muốn chọn $A$. $B$?

Bộ câu lệnh cơ bản bài toán bao gồm tất cả các câu lệnh có dạng “$A, B, C, \dots$” được bao gồm trong cuộc thám hiểm” (chúng tôi sẽ biểu thị chúng tương ứng bằng các chữ cái $A, B, C, \dots$).

Để dễ hiểu điều kiện bài toán hơn, chúng ta hãy mô tả chuyên môn của người nộp đơn bằng cách sử dụng cái gọi là biểu đồ lưỡng cực, tức là một biểu đồ có các đỉnh thuộc hai lớp (hai “dolly”) sao cho các đỉnh của cùng một lớp không được kết nối với nhau (không được kết nối bởi các cạnh). Thật thuận tiện để vẽ đồ thị hai bên bằng cách sắp xếp các đỉnh của một “dolly” trên một đường thẳng và các đỉnh của cái còn lại trên một đường thẳng song song với đường thẳng đầu tiên (hình1).

Trên hình 1, chúng tôi mô tả những người nộp đơn là các đỉnh $A, B, \dots, H^*$ của phần đầu tiên và các chuyên ngành là các đỉnh $6, 8, \dots, c$ (“b”) - nhà sinh vật học, bác sĩ “c”, v.v.) của phần thứ hai. Đỉnh của phần chia thứ nhất được nối với các đỉnh của phần chia thứ hai, nếu người nộp đơn tương ứng có chuyên ngành tương ứng. Sử dụng biểu đồ như vậy, có thể dễ dàng xác định hai ứng viên nào sở hữu ứng viên tương ứng.

Trong hai thí sinh $X$ và $Y$ có cùng chuyên môn thì có ít nhất một người được tiếp quản, tức là phép tách dạng $X \lor Y$ là đúng, tương đương với hàm ý $\bar{X} \Rightarrow Y^{**}$). Dựa vào đó chúng ta có thể viết

$(\bar{E} \Rightarrow G) \wedge (\bar{B} \Rightarrow F) \wedge (\bar{F} \Rightarrow G) \wedge (\bar{A} \Rightarrow D) \wedge (\bar{C} \Rightarrow D) \wedge (\bar{C} \Rightarrow H)$.

Ngoài ra, nếu $X$ không muốn Thoát mà không có $Y$ thì hàm ý $\bar{Y} \Rightarrow \bar{X}$ là đúng và nếu $X$ không muốn Thoát cùng với $Y$ thì hàm ý $Y \Rightarrow \bar{X}$ là đúng. Dựa vào điều này chúng ta có

$(\bar{B} \Rightarrow \bar{F}) \wedge (\bar{H} \Rightarrow \bar{D}) \wedge (\bar{C} \Rightarrow \bar{D}) \wedge$
$(\bar{G} \Rightarrow \bar{C}) \wedge (\bar{B} \Rightarrow \bar{A})$.

Vì vậy, các điều kiện bài toán có thể được biểu diễn dưới dạng kết hợp của hàm ý:

*) Tất nhiên, đây chỉ là tên của họ: Johnson, Smith, Brown, ... (Vorobiev, Grachev, Drozdov, v.v.).
**) Hoặc $\bar{Y} \Rightarrow X$ - không thành vấn đề.

⟦folio 17⟧

Hình 2.

Chúng ta hãy biểu diễn cấu trúc bài toán dưới dạng biểu đồ. Trong trường hợp này, chúng ta sẽ đặt các đỉnh được mô tả dưới dạng các câu lệnh không âm có dạng $X$ trên một đường thẳng và các đỉnh có dạng $\bar{X}$ trên một đường thẳng song song với nó sao cho $A$ và $\bar{A}$, $B$ và $\bar{B}$, v.v. nằm trong các cột dọc. Nội dung của hàm ý (1) trong điều kiện 11 được thể hiện bằng các cạnh định hướng của đồ thị (theo số liệu ở Bảng 1, xem hình 2).

Khi tô màu đồ thị, chúng ta sẽ luôn bắt đầu bằng giả định về màu của một trong các đỉnh $X$ của đồ thị. Chúng ta sẽ chọn đỉnh $X$ này sao cho tổng kết nối của nó $r(X)$ với kết nối $r(\bar{X})$ của đỉnh $\bar{X}$ giống như trong trường hợp này, màu của đỉnh $X$ cung cấp thông tin tối đa về màu của các đỉnh khác. Trong một số trường hợp, một giả định cho phép người ta tô màu hoàn toàn và rõ ràng đồ thị hoặc dẫn đến mâu thuẫn, trong những trường hợp khác, cần phải đưa ra các giả định mới. Tiếp theo là khi thông tin được cung cấp bởi giả định cuối cùng đã cạn kiệt (chuỗi sự xa lánh bị phá vỡ).

Việc tô màu đầy đủ của biểu đồ cho ra lời giải bài toán, sự mâu thuẫn cho thấy giả định đó không chính xác. Có thể đưa ra hai giả định về màu của đỉnh $X$: “$X$ là màu đỏ”, “$X$ là màu đen”. Cả hai giả định phải được sử dụng; Chỉ khi đó mới có thể sử dụng hết tất cả các tùy chọn tô màu.

Bây giờ chúng ta hãy giới thiệu thêm các quy tắc tô màu 4--6:

Quy tắc 4
Nếu phát biểu đúng thì phủ định là sai và ngược lại.

Quy tắc 5
Nếu sáu ứng viên được đưa vào cuộc thám hiểm, những người còn lại sẽ bị loại.

Quy tắc 6
Nếu hai người yêu cầu thực sự đến từ cuộc thám hiểm thì những người còn lại sẽ được bao gồm.

Bây giờ, được hướng dẫn bởi các quy tắc 1-6, chúng ta có thể tô màu biểu đồ hiển thị trong hình 2:

1. Giả sử đỉnh $C$ có màu đỏ. Sau đó:
1) $\bar{C}$ — đen (4) *); 2) $G$ - đen (3); 3) $\bar{E}$, $\bar{F}$ - đen (3); 4) $\bar{B}$ - đen (3); 5) $E$, $F$ và $B$ - đỏ (4); 6) $\bar{G}$ - đỏ (4); 7) $\bar{A}$ - đỏ

*) Ở đây và trong phần tiếp theo, các số trong ngoặc biểu thị số quy tắc, trên cơ sở đó đưa ra kết luận về màu của đỉnh.

⟦folio 18⟧

Hình 3.
naya (2); 8) $A$ - đen (4); 9) $D$ - đỏ (2); 10) $\bar{D}$ - đen (4);
11) $\bar{H}$ - đen (3); 12) $H$ - đỏ (4).

Kết quả thu được phù hợp với quy tắc 5 và 6. Do đó, nếu $C$ được đưa vào cuộc thám hiểm thì chúng ta cũng phải bao gồm $B, D, E, F$ và $H$ và loại trừ $A$ và $G$.

II. Giả sử đỉnh $C$ có màu đen (hình 3):

1) $\bar{C}$ - đỏ (4); 2) $\bar{D}$ - đỏ (2); 3) $D$ - đen (4); 4) $D$ - đỏ (2).

Vì $D$ không thể vừa có màu đỏ vừa có màu đen (1), nên giả định “$C$ là màu đen” dẫn đến mâu thuẫn; Điều này có nghĩa là $C$ có ​​màu đỏ và bài toán có một lời giải:

$B, C, D, E, F, H (\bar{A}, \bar{G})$.

Vẫn còn phải xác định vị trí của mỗi người trong số sáu người trong thành phần của nó sẽ chiếm giữ vị trí nào trong cuộc thám hiểm. Để làm điều này, chúng ta sẽ phải sử dụng biểu đồ có các cạnh được tô màu.

Chúng ta hãy vẽ lại biểu đồ hiển thị trong hình 1, loại trừ các đỉnh $A$ và $G$ và các cạnh liên kết với chúng (hình 4). Các cạnh của đồ thị thường được sơn cùng một màu, để thuận tiện cho việc “trỏ” (tô) chúng bằng các màu khác sau này. Chúng ta hãy đồng ý rằng cạnh nối đỉnh $X$ của phần thứ nhất với đỉnh $a$ của phần thứ hai sẽ có màu đỏ nếu $X$ chiếm vị trí $a$ và màu đen nếu $X$ không chiếm vị trí này (ví dụ: “$Fc$ là màu đỏ” nếu $F$ chiếm vị trí người dự báo thời tiết và “$Dp$ - đen" nghĩa là $D$ không giữ chức vụ nhân viên điều hành đài).

Khi xác định màu sắc của gân, chúng ta sẽ được hướng dẫn theo các quy tắc sau:

Quy tắc 7
Nếu chỉ một trong các giá trị trong đoàn thám hiểm có thể chiếm vị trí $a$ thì anh ta sẽ phải chiếm lấy vị trí đó.

Quy tắc 8
Nếu một số $X$, một thành viên của đoàn thám hiểm, đến chiếm vị trí $a$ do điều kiện 7, thì anh ta không thể chiếm vị trí nào khác.

Được hướng dẫn theo quy tắc 7-8, tô màu biểu đồ trên hình 4:

1) $E\delta$ - đỏ (7); 2) $Fc$ - đỏ (7); 3) $F\epsilon$ - đen (8); 4) $B\epsilon$ —

⟦folio 20⟧

Chúng tôi chủ yếu sẽ dạy năm đỉnh đại diện cho giày trượt: $(D \wedge E), (F \wedge \bar{A}), (\bar{F} \wedge E), (\bar{D} \wedge \bar{H})$ và $(E \wedge \bar{A})$.

Chúng ta sẽ gọi các đỉnh biểu thị các conyon có dạng $X \wedge Y$ là các đỉnh kết quả và các đỉnh $X$ và $Y$ là thành phần của chúng (giả sử, đỉnh $F \wedge \bar{A}$ là kết quả của các thành phần $F$ và $\bar{A}$).

Kết nối thu được với hai cạnh màu đỏ không định hướng cấu thành của nó là gì. Chúng tôi mô tả các hàm ý chứa bài toán trong các điều kiện như trong bài toán 1 (hình 5).

Chúng tôi cũng sẽ sử dụng quy tắc tô màu 1–4 khi tô màu đồ thị trên hình 5. Ngoài ra, chúng tôi giới thiệu các quy tắc bổ sung 9–13:

Quy tắc 9
Nếu $X$ đúng và $Y$ đúng thì $X \wedge Y$ đúng.

Quy tắc 10
Nếu $X \wedge Y$ đúng thì $X$ và $Y$ đều đúng.

Quy tắc 11
Nếu $X$ hoặc $Y$ sai thì $X \wedge Y$ sai.

Quy tắc 12
Nếu $X \wedge Y$ sai và $X$ đúng thì $Y$ sai.

Quy tắc 13
Nếu một số giả định loại trừ khả năng mời một số khách và tất cả những người còn lại có thể được mời mà không nhận được bất kỳ sự phản đối nào, thì điều này nên được thực hiện (để tối đa hóa số lượng khách).

Sử dụng quy tắc 1-4 và 9-13, hãy tô màu đồ thị theo hình 5:
I. Giả sử $G$ có màu đỏ:

⟦folio 21⟧

1) $\bar{G}$ - đen (4); 2) $B$ - đen (3); 3) $C$ - đen (3); 4) $E \wedge \bar{A}$ - đen (3); 5) $\bar{D} \wedge \bar{H}$ - đen (3); 6) $\bar{B}$ và $\bar{C}$ - đỏ (4).
Bây giờ chúng ta giả sử (sử dụng Quy tắc 13) rằng $D$ có màu đỏ:
7) $E$ - đỏ (2); 8) $D \wedge E$ - đỏ (9); 9) $\bar{A}$ - đỏ (2); 10) $E \wedge \bar{A}$ - đỏ (9).

Nhưng theo quy tắc 1, $E \wedge \bar{A}$ không thể vừa đen (bước 4) vừa đỏ (bước 10), nghĩa là nếu $G$ có màu đỏ thì $D$ có ​​màu đen.

Hãy xây dựng một biểu đồ mới (hình 6) và sử dụng kết quả của sáu bước đầu tiên trên đó. Tô màu đồ thị ở hình 6, giả sử rằng $D$ là màu đen:
11) $\bar{D}$ - đỏ (4); 12) $D \wedge E$ - đen (11); 13) $\bar{H}$ - đen (12);
14) $H$ - đỏ (4); 15) $F \wedge \bar{A}$ - đen (3); 16) $\bar{F} \wedge E$ - đen (3).
Giả sử rằng $E$ có màu đỏ (13):
17) $\bar{E}$ - đen (4); 18) $\bar{F}$ - đen (12); 19) $F$ - đỏ (4); 20) $\bar{A}$ - đỏ (12); 21) $A$ - đỏ (4).

Theo quy tắc 13, chúng tôi tô cả ba đỉnh còn lại thành màu đỏ: $E, F$ và $A$. Sau đó, từ biểu đồ hình 6, nếu bạn mời $G$ thì ngoài ra, bạn có thể mời $A, E, F$ và $H$ (tổng cộng 5 khách).

Trong biến thể được xem xét (theo giả định “$G$ là màu đỏ”) ba đỉnh $B, C$ và $D$ hóa ra là màu đen. Hãy kiểm tra xem trong trường hợp “$G$ - đen”, chúng ta có thể nhận được ít nhất năm đỉnh màu đỏ hay không, tức là không quá ba đỉnh màu đen.

II. Giả sử rằng $G$ có màu đen (hình 7). Sau đó:
1) $\bar{G}$ - đỏ (4); 2) $F$ - đen (3); 3) $\bar{F}$ - đỏ (4);
4) $F \wedge \bar{A}$ - đen (11).
Bây giờ hãy để $D$ có màu đỏ (13):
5) $E$ - đỏ (12); 6) $\bar{E}$ - đen (4); 7) $B$ - đen (3);
8) $D \wedge E$ - đỏ (9); 9) $\bar{A}$ - đỏ (2); 10) $A$ - đỏ (4).

Do đó, bốn đỉnh đã trở thành màu đen ($A, B, F, G$).

Hãy vẽ lại biểu đồ hình 7 (hình 8) - sử dụng kết quả của bốn bước đầu tiên và giả sử rằng $D$ có ​​màu đen. Khi đó đã có ba đỉnh màu đen ($D, F$ và $G$), nghĩa là để có được ít nhất năm đỉnh màu đỏ, cần phải làm cho tất cả các đỉnh khác thuộc loại $X$ có màu đỏ.

Nhưng điều này là không thể, vì nếu $A$ có màu đỏ thì

⟦folio 22⟧

11) $\bar{A}$ - đen (4); 12) $B$ - đen (3).

Do đó, giả định “$G$ là màu đen” không tạo ra nhiều hơn bốn đỉnh màu đỏ có dạng $X$. Số lượng lớn nhất của các đỉnh như vậy (năm) được đưa ra bởi giả định “$G$ có ​​màu đỏ”.

Đáp số theo biểu đồ hình 6:
$N$ có thể mời tối đa năm khách: $A, E, F, G$ và $H$.

Sau đó, e. Khi xem xét tất cả bốn tùy chọn tô màu (hình 5–8), chúng ta có thể giới hạn bản thân chỉ ở một biểu đồ. Để làm được điều này, các đỉnh của nó phải được làm dưới dạng các hình tròn có đường kính đủ lớn, chia thành bốn hình vuông, và khi xem xét từng phương án, một hình vuông phải được sơn lên trên.

* *

Để kết luận, chúng tôi lưu ý rằng bài toán 1 (về sự hiện diện của một tam giác với các cạnh có giá trị đơn trong biểu đồ có sáu đỉnh và các cạnh có hai màu) và 5 (về sự hiện diện của một tam giác như vậy trong biểu đồ có mười bảy đỉnh và cạnh ba màu) từ bài viết của L. Yu. Berezina “Trên đồ thị có cạnh màu” cho phép khái quát hóa như sau (được đề xuất tại Olympic trẻ Cộng hòa Ukraine lần thứ XIII):

Bài toán 3

Chuỗi $\{a_n\}$ được đưa ra bằng công thức truy hồi: $a_1 = 2; a_n = n a_{n-1} + 1$. Chứng minh rằng trong đồ thị $c a_n + 1$ có ​​đỉnh có các cạnh được bao quanh bởi $n$ màu, tồn tại một tam giác có các cạnh có một giá trị.

Hãy sử dụng phương pháp quy nạp toán học.

1. Tại $n = 1$ $a_1 = 2$. Số đỉnh $a_1 + 1 = 3$.

Đồ thị là một hình tam giác có các cạnh cùng màu (nghĩa là hình tam giác mong muốn).

2. Giả sử câu khẳng định đúng với $n = k$, tức là trong một đồ thị có số màu $k$ và số đỉnh $a_k + 1$ có ​​một tam giác có các cạnh có một giá trị. Hãy bây giờ $n = k + 1$. Khi đó số đỉnh là

$$a_{k+1} + 1 = [(k + 1) \cdot a_k + 1] + 1.$$

Hãy chọn một trong các đỉnh; Hãy gọi nó là $A$. Nó được kết nối bởi các cạnh $k + 1$ màu với các đỉnh, số lượng là $(k + 1) \cdot a_k + 1$. Trong số các cạnh này, ít nhất $a_k + 1$ có cùng màu (theo nguyên tắc Dirichlet*)) để xác định - blueERO. Nếu một trong các đỉnh $a_k + 1$ $B$ được nối với một $C$ khác bằng một cạnh thì tam giác $\Delta ABC$ là tam giác mong muốn. Nếu không, màu xanh lam không được sử dụng trong biểu đồ bao gồm $a_k + 1$ đỉnh và khi đó chỉ có $k$ màu được sử dụng ở đó. Theo đề xuất, biểu đồ này (là một phần của biểu đồ ban đầu) chứa hình tam giác mong muốn, có nghĩa là nó cũng có hình tam giác đó trong hình ban đầu.

Tuyên bố đã được chứng minh.

Cụ thể, tại $n = 2$ (hai màu) $a_2 = 2 \cdot 2 + 1 = 5, a_2 + 1 = 6$ (sáu đỉnh); tại $n = 3$ (ba màu) $a_3 = 3 \cdot 5 + 1 = 16, a_3 + 1 = 17$ (mười bảy đỉnh).

(Trong tất cả các bài toán này, chúng tôi muốn nói đến các đồ thị hoàn chỉnh trong đó bất kỳ cặp đỉnh nào được nối với nhau bằng một cạnh.)
