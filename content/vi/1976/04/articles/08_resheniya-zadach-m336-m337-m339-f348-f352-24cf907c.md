---
id: 1976-4-resheniya-zadach-m336-m337-m339-f348-f352-24cf907c
issue: kvant_1976_4
year: 1976
number: "4"
title: Lời giải bài toán M336, M337, M339; F348—F352
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 34
page_last: 41
page_labels: 32, 34, 35, 36, 37, 38, 39
tag: HG16
lang: vi
source: kvant_digital
extraction: vision
content_sha256: be4ae6a346ccd07674793c60f2e975e5062834eb84b583af511cc4048ebc4475
prompt_sha256: draft-1
translated_from: content/ru/1976/04/articles/08_resheniya-zadach-m336-m337-m339-f348-f352-24cf907c.md
source_content_sha256: 5c4166dc3fd7a5dc76cb6e60282696247fdfb9d82e0afe01f6e48c2324001adc
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 32⟧

Lời giải bài toán
M336, M337, M339; F348—F352

M336. Trong mặt phẳng đã cho có một tập hữu hạn các đa giác, mỗi đa giác có một điểm chung. Hãy chứng minh rằng có một đường thẳng có điểm chung với mỗi đa giác này.

Hình 1.

M337. Cho tam giác đều ABC có cạnh dài 1. Bước đầu tiên là chọn điểm X trên cạnh AB, điểm thứ hai Y trên cạnh BC, sau đó chọn điểm thứ nhất Z trên cạnh AC.
a) Mục tiêu của lần kiểm tra đầu tiên là thu được hình tam giác XYZ có diện tích lớn nhất, hình thứ hai có diện tích lớn nhất. Diện tích lớn nhất cần cung cấp đầu tiên là gì?
b) Mục tiêu của lần kiểm tra đầu tiên là thu được tam giác XYZ có chu vi lớn nhất, mục tiêu thứ hai là có chu vi lớn nhất. Chu vi lớn nhất mà người đầu tiên có thể cung cấp là gì?

Hãy chiếu tất cả các đa giác lên một đường thẳng m nào đó. Hình chiếu của mỗi đa giác sẽ là một đoạn. Trong số các đầu bên phải của các đoạn này, chúng ta chọn đầu bên trái nhất (đặt nó là đầu bên phải A của hình chiếu của đa giác M - xem Hình 1) và vẽ một đường thẳng l qua nó, vuông góc với đường thẳng m. Số nguyên tố l cắt tất cả các đa giác, vì đa giác dưới không thể nằm hoàn toàn về bên trái của nó (khi đó đầu bên phải của hình chiếu của nó sẽ ở bên trái của A), và đa giác dưới không thể nằm hoàn toàn về bên phải (vì khi đó nó sẽ không có điểm chung với đa giác M).

S. Fomin

Hình 2.

Hình 3.

a) Trước tiên chúng ta chứng minh rằng chiến lược của người chơi thứ hai là đặt điểm Y trên cạnh BC sao cho đường thẳng XY song song với cạnh AC. Thật vậy, nếu (XY') || (AC) và Y∈[BY'] (xem Hình 2), sau đó người chơi đầu tiên, với nước đi thứ hai, đặt điểm Z tại đỉnh C; thì SXYC > SXY'C, vì các tam giác này có cùng chiều cao, nhưng đáy của tam giác thứ nhất lớn hơn. Nếu Y∈[Y'C], thì người chơi đầu tiên sẽ đặt điểm Z ở đỉnh A, và một lần nữa sẽ có SXYA > SXY'A, vì các tam giác này có cùng đáy và chiều cao y của tam giác XYA lớn hơn (Hình 3).

Do đó (XY) || (AC) và vị trí trên [AC] người chơi đầu tiên đặt điểm Z, không có gì phụ thuộc:

$$S_{XYZ} = S_{XYA} = \frac{1}{2} \cdot |XY| \cdot (H - h),$$

(ở đây H = \frac{\sqrt{3}}{2} là chiều cao của tam giác ABC, h là chiều cao của tam giác XBY). Thể hiện |XY| qua h, ta được diện tích cần tìm là một tam giác vuông tính từ h. Tam thức này có giá trị tối đa là $\frac{H^2 \sqrt{3}}{12} =$

⟦folio 34⟧

Hình 7.

M339*). Cho một dải nằm ngang trên một mặt phẳng, các cạnh của dải là những đường thẳng song song và n đường thẳng cắt dải này. Hai trong số n đường thẳng này cắt nhau bên trong dải và không có đường thẳng nào đi qua cùng một điểm. Khoảng cách là tất cả các đường đi bắt đầu từ mép dưới của dải, đi theo dữ liệu của đường thẳng và kết thúc ở cạnh trên, có thuộc tính tối đa: một dọc theo mức tối đa của đường đi, chúng ta luôn đi lên; đường kia đi thẳng đến giao điểm thì ta phải đi đến một đường thẳng khác. Hãy chứng minh rằng trong số các cực đại

a) có các đường dẫn gồm ít nhất n đoạn;
b) có nhiều nhất $\frac{n}{2} + 1$ đường đi thẳng;
c) có những đường đi qua tất cả n thẳng hàng.

Hình 8.

Bình phương cả hai vế của phương trình (*), ta có:

$$2x^2 - 3x + 2 = 2(1 - x)\sqrt{x^2 + x + 1},$$

Ở đâu

$$8x^3 - 17x^2 + 8x = 0,$$

$$x = |AE| = \frac{17 - \sqrt{33}}{16}$$

(kiểm tra xem đây có phải là nghiệm hợp lệ của phương trình (*)). Chu vi cần tìm bằng

$$2|EC| = 2\sqrt{x^2 - x + 1} = \frac{3}{8}\sqrt{2(17 - \sqrt{33})}.$$

M. Bronstein

Chúng ta biểu thị các điểm giao nhau của các đường thẳng với cạnh dưới của dải theo thứ tự (từ trái sang phải) bằng $A_1, A_2, \dots, A_n$ (Hình 7). Chúng ta biểu thị các điểm giao nhau của cùng một đường với cạnh trên của dải là $B_1, B_2, \dots, B_n$.

Hãy liệt kê một số thuộc tính của đường dẫn được đề cập trong các điều kiện.

1°. Có đúng một đường đi dọc theo mỗi đoạn của mỗi đường thẳng. Thật vậy, những cái đúng, được xây dựng trong các điều kiện, cho phép cách duy nhất là tiếp tục con đường lên và xuống các cạnh của dải.

2°. Có n đường đi khác nhau: mỗi điểm $A_1, \dots, A_n$ có đường đi riêng. Hãy đặt chúng theo thứ tự: 1, 2, ..., thứ n.

3°. Đường đi bắt đầu tại điểm $A_k$ kết thúc tại điểm $B_k$. Trong thực tế, theo quy luật, mỗi đường đi tại giao điểm của các đường sẽ đi đến một đường thẳng khác, do đó (Hình 8) các đường đi không thể cắt nhau mà chỉ chạm nhau tại các đỉnh của chúng. Do đó, đường dẫn thứ $k$ chia sọc thành hai vùng - vùng bên trái, trong đó tất cả các đường dẫn được đánh số $i < k$ được đặt và vùng bên phải, trong đó tất cả các đường dẫn được đánh số $i > k$ được đặt. Do đó, đường dẫn thứ $k$ sẽ kết thúc ở $B_k$ (Hình 9).

Chúng ta hãy tiến hành chứng minh các phát biểu riêng lẻ bài toán.

a) Chúng ta hãy tính tổng số đoạn trong tất cả các đường đi theo hai cách. Một mặt, mỗi đường được chia thành n đoạn, vì nó bị cắt bởi n-1 đường khác; do đó, tổng số phân đoạn là $n^2$. Mặt khác, chúng ta phải thu được cùng một tổng $n^2$ bằng cách cộng số đoạn trong tất cả n đường dẫn (chúng ta sử dụng $1^\circ$ và $2^\circ$ ở đây). Suy ra rằng ít nhất một trong các đường đi có ít nhất n đoạn.

b) Hãy ước tính số đoạn trong hai đường cực trị: thứ nhất và thứ n. Những đường đi này, rất indo, tập lồi giới hạn: đầu tiên là tập hợp các điểm nằm trên tất cả các đường thẳng, cuối cùng là tập hợp các điểm nằm trên tất cả các đường thẳng (Hình 10). Rõ ràng đường đầu tiên nằm bên trái đường đứt nét $A_1PB_1$, đường cuối cùng bên phải đường đứt nét $A_nPB_n$, trong đó $P$ là giao điểm của ($A_1B_n$) và ($A_nB_1$), và chỉ đoạn đầu và đoạn cuối của cả hai đường đều nằm trên đường thẳng $A_1B_n$ và $A_nB_1$. Đối với mỗi n-2 đường thẳng còn lại $A_2B_{n-1}, A_3B_{n-2}, \dots, A_{n-1}B_n$, chúng có thể có

*) Lời giải bài toán M338 xem trong bài viết của Yu. Ionin và L. Kurlyandik “Bất biến Ponsk”, xuất bản năm «Kvant», 1976, số 2.

⟦folio 35⟧

F348. Tàu vũ trụ tiếp cận Mặt trăng theo quỹ đạo parabol, gần như chạm vào bề mặt Mặt trăng. Để di chuyển đến quỹ đạo hình tròn đầy sao (tức là quỹ đạo tròn rất gần bề mặt Mặt trăng), tại thời điểm gần Mặt trăng nhất, bộ đẩy băng giá sẽ được bật. Xác định tốc độ của tàu sẽ thay đổi bao nhiêu khi thực hiện thao tác này. Gia tốc trọng trường trên bề mặt Mặt trăng $g_{\pi} \approx 1,7 \text{ m/сек}^2$, bán kính Mặt trăng $R_{\pi} \approx 1,7 \cdot 10^6 \text{ m}$.

Câu hỏi bổ sung. Hãy thử ước tính phần nào của khối lượng lớn nhất của con tàu sẽ là nhiên liệu phức tạp nếu chúng ta chọn một sản phẩm có tốc độ tương đối là $v = 4 \cdot 10^3 \text{ m/сек}$.

Khi các vật thể chuyển động trong trường hấp dẫn của một hành tinh (hoặc ngôi sao), tổng năng lượng cơ học (tức là tổng động năng và thế năng) được bảo toàn. Tùy thuộc vào giá trị của tổng năng lượng $E$, quỹ đạo có đặc điểm khác nhau$^*$.

Ở $E < 0$ cơ thể không thể di chuyển đến một khoảng cách vô cùng lớn; trong trường hợp này, quỹ đạo của nó có dạng hình elip (định luật thứ nhất của Kepler). Ở $E > 0$, vật chuyển động ra xa đến vô cùng, được cung cấp thêm động năng (quỹ đạo hyperbol). Tại $E = 0$ vật cũng tiến tới vô cực, nhưng trong trường hợp này tốc độ của nó ở vô cực bằng không; quỹ đạo của vật có dạng parabol.

Khi chuyển động theo quỹ đạo parabol, vận tốc của vật đến gần hành tinh bằng vận tốc vũ trụ thứ hai. Đây là tên được đặt cho tốc độ tối thiểu mà một vật thể, bắt đầu từ bề mặt của một hành tinh, có thể di chuyển ra khỏi nó đến một khoảng cách vô tận. Đối với điểm hội tụ lớn nhất với Mặt trăng (Hình 11), chúng ta có thể viết:

$$E = K + \Pi = \frac{mv^2}{2} - \gamma \frac{M_{\pi} m}{R_{\pi}} = \frac{mv^2}{2} - g_{\pi} R_{\pi} m = 0.$$

Ở đây $v_{\pi}$ là tốc độ của tàu tại thời điểm có gia tốc lớn nhất so với Mặt Trăng (vận tốc thoát thứ hai); $\Pi = -\gamma \frac{M_{\pi} m}{R_{\pi}}$ là thế năng của con tàu ở gần Mặt trăng$^{**}$.

*) Ví dụ, xem bài viết của K. Kovalenko và M. Crane “Đạn đạo bài toán trong không gian”, 1973, số 5.

**) Ví dụ, xem bài viết của S. Kozel “Những chất tương tự vật lý”, 1975, số 11.

⟦folio 36⟧

Đối với tốc độ $v_{II}$ chúng tôi nhận được:

$$v_{II} = \sqrt{2g_{\text{Л}}R_{\text{Л}}} \approx 2,4 \cdot 10^3 \text{ m/сек.}$$

Trong quá trình phanh, tốc độ của tàu theo điều kiện nhất định phải giảm xuống tốc độ vũ trụ đầu tiên (đối với Mặt trăng) $v_I$. Tốc độ này có thể được xác định từ điều kiện tàu chuyển động theo quỹ đạo tròn:

$$\frac{mv_I^2}{R_{\text{Л}}} = \gamma \frac{M_{\text{Л}}m}{R_{\text{Л}}^2} = g_{\text{Л}}m; \quad v_I = \sqrt{g_{\text{Л}}R_{\text{Л}}} \approx 1,7 \cdot 10^3 \text{ m/сек.}$$

Vì vậy, tốc độ của tàu sẽ thay đổi một lượng

$$\Delta v = v_{II} - v_I \approx 0,7 \cdot 10^3 \text{ m/сек.}$$

Để trả lời câu hỏi (bổ sung) và ước tính khối lượng $m$ của nhiên liệu đã đốt cháy, chúng ta có thể sử dụng định luật bảo toàn động lượng. Chúng ta hãy giả sử để kiểm soát tính toán rằng các sản phẩm có khối lượng loại $m$ được đẩy ra khỏi vòi trong các gói dưới dạng một phần với tốc độ tương đối $v$. Ta viết định luật bảo toàn động lượng vào hệ thống báo cáo trường hợp tàu chuyển động với vận tốc $v_{II}$:

$$(M_0 - m)\Delta v = mv,$$

trong đó $M_0$ là khối lượng ban đầu của tàu. Từ đây

$$m = \frac{\Delta v}{v + \Delta v} M_0 \approx 0,15 M_0,$$

tức là nhiên liệu đốt phải xấp xỉ 15% khối lượng ban đầu của tàu.

Bạn có thể tìm thấy khối lượng nhiên liệu chặt chẽ hơn. Để làm điều này, bạn cần sử dụng công thức Tsiolkovsky. Công thức này biểu thị sự thay đổi tốc độ của tàu vũ trụ $\Delta v$ thông qua tỷ lệ giữa khối lượng $M_0$ ban đầu và khối lượng cuối cùng $M$ của nó:

$$\Delta v = v \ln \frac{M_0}{M}$$

(v là tốc độ tương đối của nguồn sản phẩm giống). Từ đây

$$M = M_0 e^{-\frac{\Delta v}{v}} = M_0 e^{-0,175} \approx 0,84 M_0,$$

tức là nhiên liệu đốt cháy xấp xỉ 16% khối lượng ban đầu của tàu.

Lưu ý rằng công thức Tsiolkovsky có tính đến quá trình tìm nguồn cung ứng sản phẩm liên tục từ các gói vòi phun, do đó kết quả thu được với sự trợ giúp của nó sẽ chính xác hơn.

S. Kozel

F349. Một kilomol khí đơn nguyên tử lý tưởng trong điều kiện bình thường được chuyển từ trạng thái 1 sang trạng thái 2 theo hai cách: $1 \rightarrow 3 \rightarrow 2$ và $1 \rightarrow 4 \rightarrow 2$ (Hình 12). Tên lượng nhiệt tỏa ra mà khí phải tạo ra trong hai quá trình này.

Theo định luật nhiệt động thứ nhất, lượng nhiệt năng $Q$ truyền vào chất khí sẽ làm thay đổi nội năng của chất khí $\Delta U$ và thực hiện công $A$ bởi chất khí:

$$Q_I = \Delta U_I + A_I, \quad Q_{II} = \Delta U_{II} + A_{II}.$$

Ở đây chỉ mục I đề cập đến quy trình $1 \rightarrow 3 \rightarrow 2$ và chỉ mục II đề cập đến quy trình $1 \rightarrow 4 \rightarrow 2$.

Vì khí có tính chất đơn nguyên tử nên đối với một mol

$$U = \frac{3}{2} RT, \quad \Delta U = \frac{3}{2} R\Delta T.$$

Điều này chứng tỏ sự biến thiên nội năng của một chất khí khi chuyển từ trạng thái 1 sang trạng thái 2 chỉ phụ thuộc vào sự thay đổi nhiệt độ của chất khí $\Delta T = T_2 - T_1$ chứ không phụ thuộc vào

⟦folio 37⟧

cách thức khí được chuyển từ trạng thái này sang trạng thái khác. Kể từ đây,

$$\Delta U_1 = \Delta U_{II} = \Delta U = \frac{3}{2} R (T_2 - T_1).$$

Để tìm nhiệt độ của khí $T_1$ và $T_2$, chúng ta viết phương trình trạng thái của khí lý tưởng ở trạng thái 1 và 2 (xem Hình 12):

$$p_0 V_0 = RT_1, \quad 2 p_0 \cdot 2 V_0 = RT_2,$$

Ở đâu

$$T_2 - T_1 = \frac{3 p_0 V_0}{R}, \quad \Delta U = \frac{9}{2} p_0 V_0.$$

Bây giờ chúng ta hãy tìm công của khí $A_1$ và $A_{II}$. Trong trường hợp đầu tiên (quá trình $1 \rightarrow 3 \rightarrow 2$), khí không hoạt động ở phần $1 \rightarrow 3$, nhưng trong quá trình giãn nở đẳng áp ở phần $3 \rightarrow 2$ khí đó hoạt động

$$A_1 = p \Delta V = 2 p_0 (2 V_0 - V_0) = 2 p_0 V_0.$$

Trong trường hợp thứ hai (quy trình $1 \rightarrow 4 \rightarrow 2$), khí chỉ hoạt động ở phần $1 \rightarrow 4$:

$$A_{II} = p_0 (2 V_0 - V_0) = p_0 V_0.$$

Như vậy,

$$Q_1 = \Delta U + A_1 = \frac{13}{2} p_0 V_0,$$

$$Q_{II} = \Delta U + A_{II} = \frac{11}{2} p_0 V_0.$$

Tỉ số giữa lượng nhiệt là

$$\frac{Q_1}{Q_{II}} = \frac{13}{11}.$$

F350. Tên của hướng trên điện trở $R$ trong mạch như hình 13 phụ thuộc vào giá trị của điện trở này. E. d. c. tất cả các nguồn đều bằng $\mathcal{E}$, điện trở trong của chúng là $r$. Điốt của sàng là lý tưởng (điện trở của nó theo hướng thuận bằng 0 và theo hướng ngược lại là vô cùng lớn).

Hình 15.

Nếu điện trở $R$ lớn thì dòng điện và dòng chảy qua nó sẽ rất nhỏ và hiệu điện thế giữa các điểm $B$ và $A$ (xem Hình 13) gần bằng $2\mathcal{E}$. Trong trường hợp này, điện thế l của điểm $B$ cao hơn điện thế của điểm $C$ (bằng $\mathcal{E}$, nếu chúng ta coi điện thế của điểm $A$ bằng 0), diode đóng và không có dòng điện chạy qua đoạn mạch $ACB$. Sau đó, mạch này có thể được thay thế bằng một mạch đơn giản với hai nguồn mắc nối tiếp có điện trở $R$ (Hình 14). Trong mạch này có dòng điện $I = \frac{2\mathcal{E}}{2r + R}$ và hướng rơi trên điện trở $R$ bằng

$$U_R = \frac{2\mathcal{E} R}{2r + R}.$$

Khi điện trở $R$ giảm, dòng điện trong mạch tăng, hướng giảm trên điện trở trong của các nguồn tăng và hiệu điện thế giữa các điểm $B$ và $A$ giảm. Điều này sẽ xảy ra cho đến khi điện thế của điểm $B$ bằng với điện thế của điểm $C$, tức là trong khi diode vẫn đóng. Diode sẽ mở tại thời điểm hướng giữa các điểm $B$ và $C$ trở thành 0 và giữa các điểm $B$ và $A$ - $\mathcal{E}$. Điều này có nghĩa là tại thời điểm này hướng giảm trên điện trở $R$ bằng $\mathcal{E}$, tức là.

$$\frac{2\mathcal{E} R}{2r + R} = \mathcal{E},$$ hoặc $R = 2r$.

Bây giờ chúng ta hãy tìm hướng tại mức kháng cự $R$ khi $R < 2r$. Trong trường hợp này, điện trở của diode bằng 0 và mạch điện có thể được biểu diễn như trong Hình 15.

⟦folio 38⟧

Trong trường hợp này
$$U'_R = I'R = \mathcal{E} - I_1 r = 2\mathcal{E} - I_2 \cdot 2r,$$
$$I' = I_1 + I_2.$$

Từ đây
$$I' = \frac{4\mathcal{E}}{2r + 3R} \text{ и } U'_R = \frac{4\mathcal{E}R}{2r + 3R}.$$

Như vậy,
$$U_R = \frac{2\mathcal{E}R}{2r + R} \text{ при } R \geq 2r,$$
$$U_R = \frac{4\mathcal{E}R}{2r + 3R} \text{ при } R \leq 2r.$$

F351. Với một tác động yếu, chức năng của quả bóng đối với tường là biến dạng x của nó, nhỏ hơn nhiều so với bán kính của quả bóng R, và có thể, với một ước tính gần đúng, áp suất không khí p trong quả bóng không thay đổi trong quá trình va chạm.

Bỏ qua độ đàn hồi của lốp, ước tính thời gian quả bóng va vào tường. Thực hiện phép tính số cho nút thắt khi khối lượng của quả bóng là m = 0,5 kg, áp suất trong đó là p = 2 atm và bán kính R = 12,5 cm.

Hãy cùng xem những giấc mơ ảnh hưởng đến quả bóng khi va chạm. Đây là phản lực từ bức tường N và lực áp suất khí quyển Fa.

Theo định luật thứ ba của Newton, lực N có giá trị bằng số và ngược chiều hướng từ bên trái quả bóng lên tường Fd. Vì có thể bỏ qua độ đàn hồi của lốp bi nên
$$N = F_d = pS = p\pi r^2$$
($S = \pi r^2$—diện tích tiếp xúc của quả bóng với tường, xem Hình 16). Lực N hướng vuông góc với tường, tức là theo phương ngang về bên phải.

Để tìm áp suất khí quyển, thể tích bề mặt tiếp xúc của quả bóng với tác dụng xung quanh được chia thành các vùng nhỏ có diện tích $\Delta s_i$. Mỗi khu vực bị ảnh hưởng bởi áp suất khí quyển $\Delta F_i$ (Hình 17), hướng vuông góc với bề mặt và bằng giá trị tuyệt đối $\Delta F_i = p_0 \Delta s_i$ ($p_0$—áp suất khí quyển). Nhờ tính đối xứng, rõ ràng là các quá trình thẳng đứng của tất cả các lực $\Delta F_i$ cộng lại bằng 0, do đó trạng thái cân bằng của quả bóng $= \sum \Delta F_i$ hướng theo phương ngang sang trái và có độ lớn bằng nhau (xem Hình 17)
$$F_a = \sum \Delta F_i \cos \alpha = p_0 \sum \Delta s_i \cos \alpha.$$
Giá trị $\Delta s_i \cos \alpha$ là hình chiếu của mặt phẳng và $\sum \Delta s_i \cos \alpha$ là tổng của các quá trình đó, bằng hình chiếu của mặt phẳng tiếp xúc của quả bóng với tác dụng xung quanh,
$$\sum \Delta s_i \cos \alpha = \pi r^2, \text{ и } F_a = p_0 \pi r^2.$$
Bây giờ chúng ta hãy tìm giá trị abscylotic của những giấc mơ F = N + Fa:
$$F = N - F_a = (p - p_0) \pi r^2 = (p - p_0) \pi [R^2 - (R - x)^2] = (p - p_0) \pi (2Rx - x^2).$$
Vì biến dạng của quả bóng x nhỏ so với bán kính R của nó nên các giá trị $x^2$ có thể bỏ qua so với các giá trị 2Rx. Khi đó F = 2πR (p - p_0) x, hoặc xét rằng lực này có hướng ngược với biến dạng,
$$F = -2\pi R (p - p_0) x = -kx.$$
Như vậy, lực F tỉ lệ thuận với độ lớn biến dạng x ($k = 2\pi R (p - p_0)$ là hệ số tỉ lệ; nó không thay đổi trong quá trình va chạm), tức là nó có bản chất đàn hồi. Dưới ảnh hưởng của giấc ngủ như vậy, cơ thể có thể dao động với chu kỳ $T = 2\pi \sqrt{\frac{m}{k}}$, trong đó m là khối lượng cơ thể.

⟦folio 39⟧

Rõ ràng, thời gian t của quả bóng va chạm vào tường đúng bằng nửa chu kỳ dao động, tức là.

$$\tau = \frac{T}{2} = \pi \sqrt{\frac{m}{k}} = \sqrt{\frac{\pi m}{2R(p-p_0)}} \approx 8 \cdot 10^{-3} \text{ сек}.$$

◆

Chúng ta hãy tìm biểu thức điện áp trên tải trong trường hợp tổng quát.

Chúng ta hãy biểu thị bằng $R_1$ và $R_2$ điện trở của các bộ phận của biến trở mà động cơ chia nó ra và vẽ lại mạch điện như hình 19.

Điện áp trên tải bằng điện áp trên đoạn $AB$, chứa các điện trở $R$ và $R_2$ mắc song song. Chúng có thể được thay thế bằng một điện trở tương đương $R_3 = \frac{R R_2}{R + R_2}$.

Điện áp trên điện trở tương đương này (và do đó trên tải) rõ ràng bằng $U = IR_3$, trong đó $I = \frac{U_{BX}}{R_1 + R_3} - \text{tok в цепи}, \text{ т. е. } U = U_{BX} \frac{R_3}{R_1 + R_3}$.

Vì $R_1 = R - R_2$ thì

$$U = U_{BX} \frac{R_3}{R - R_2 + R_3} = U_{BX} \frac{R R_2}{R^2 - R_2^2 + R R_2}.$$

Chia tử số và mẫu số trong công thức này cho $R^2$:

$$U = U_{BX} \frac{\alpha}{1 - \alpha^2 + \alpha}, \text{ где } \alpha = \frac{R_2}{R}.$$

Trong mạch ban đầu $R_2 = R/2$, tức là $\alpha_1 = 1/2$ và điện áp trên tải

$$U_1 = U_{BX} \frac{1}{2(1 - 1/4 + 1/2)} = \frac{2}{5} U_{BX}. \tag{1}$$

Khi điện áp vào mạch tăng gấp đôi thì điện áp trên tải

$$U_2 = 2U_{BX} \frac{\alpha_2}{1 - \alpha_2^2 + \alpha_2}, \tag{2}$$

trong đó $\alpha_2$ là giá trị mới của $R_2/R$.

Nhưng theo điều kiện bài toán, điện áp trên tải trong trường hợp chung phải giống nhau. Do đó, theo đẳng thức (1) và (2)

$$\frac{2}{5} U_{BX} = 2U_{BX} \frac{\alpha_2}{1 - \alpha_2^2 + \alpha_2}.$$

Từ đây

$$\alpha_2^2 + 4\alpha_2 - 1 = 0.$$

Giải phương trình này, ta được

$$\alpha_2 = -2 \pm \sqrt{4+1} = -2 \pm \sqrt{5}.$$

Vì $\alpha_2 > 0$ nên nó bằng $\sqrt{5} - 2$. Vì vậy, động cơ cần phải được di chuyển sao cho

$$R_2 = (\sqrt{5} - 2) R.$$

N. Tiếng Slovodechkiy
