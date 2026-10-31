---
id: 1979-9-resheniya-zadach-m528-m529-f538-f541-3bcc6f04
issue: kvant_1979_9
year: 1979
number: "9"
title: Lời giải bài toán M528, M529; F538—F541
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 26
page_last: 30
page_labels: 24, 25, 26, 28
tag: T94V
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 6b8efcf5348f44d086e7e1d85f65e3eb08ffdd26cf14489e70cf0eda185def57
prompt_sha256: draft-1
translated_from: content/ru/1979/09/articles/10_resheniya-zadach-m528-m529-f538-f541-3bcc6f04.md
source_content_sha256: c4e941ba32bb8af880ff755a3f8231a07dfa3cb5b6ac8aba91b6d8b7d0003d1b
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 24⟧

Lời giải bài toán

M528, M529; F538 — F541

M528. Có một quân cờ trên mỗi ô vuông của bàn cờ. Các chip phải được sắp xếp lại sao cho khoảng cách giữa mỗi cặp chip không giảm so với khoảng cách giữa chúng tại vị trí ban đầu. Có bao nhiêu cách có thể thực hiện được điều này? (Hãy xem xét khoảng cách giữa các mã thông báo được nén giữa tâm của các ô mà chúng chiếm giữ.)

Cơm. 1.

Cơm. 2.

Trước hết, chúng ta hãy chứng minh rằng việc sắp xếp lại các token là cần thiết để duy trì khoảng cách giữa hai token bất kỳ. Điều này có thể được thực hiện theo nhiều cách khác nhau.

Cách đầu tiên. Tổng tất cả khoảng cách theo cặp giữa các chip không thay đổi. Theo đó, không có khoảng cách nào có thể tăng lên (thực vậy, nếu sau khi sắp xếp lại các chip, khoảng cách giữa mỗi cặp chip không giảm, thì vì tổng của tất cả các khoảng cách không đổi nên sẽ có các chip mà khoảng cách giữa chúng sẽ giảm đi, điều này mâu thuẫn với các điều kiện sắp xếp lại).

Cách thứ hai. Các quân góc A, B, C, D (Hình 1) vẫn phải là quân góc, vì khoảng cách từ mỗi quân này đến quân ở góc đối diện (chéo) không thể thay đổi (khoảng cách này bằng độ dài đường chéo của bàn cờ, tối đa: $|AC| = |BD| \ge |KL|$, trong đó K và L là các ô tùy ý). Như vậy, bốn quân này vẫn chiếm bốn góc của bàn cờ và các vị trí mới A', B', C', D' vẫn là bốn đỉnh liên tiếp của hình vuông (Hình 2). Khi đó, khoảng cách từ mã thông báo M đến cạnh của hình vuông ABCD phải bằng khoảng cách từ ảnh của nó - mã thông báo M' - đến các cạnh tương ứng của hình vuông A'B'C'D': nếu không thì khoảng cách từ M đến hai cạnh liền kề của hình vuông sẽ không tăng và một trong số chúng sẽ giảm đi; nhưng khi đó khoảng cách tới đỉnh chung của các cạnh này cũng sẽ giảm đi.

Từ các bằng chứng của chúng tôi, rõ ràng rằng việc sắp xếp lại các thẻ cần thiết sẽ xác định một số chuyển động của hình vuông ABCD trên chính nó. Sự tự sắp xếp như vậy tồn tại trong mọi thứ (kể cả một điểm giống hệt nhau, trong đó tất cả các điểm vẫn giữ nguyên): đỉnh A có thể rơi vào bất kỳ đỉnh nào trong bốn đỉnh còn lại và đỉnh B có thể rơi vào một trong hai đỉnh lân cận của nó.

Lưu ý rằng kết quả chính bài toán thừa nhận sự tổng quát hóa màu đỏ sau: nếu f là ánh xạ liên tục của một tập màu cam đóng (trên mặt phẳng hoặc trong không gian) vào chính nó sao cho với hai điểm M, N bất kỳ

$$\rho(f(M), f(N)) \ge \rho(M, N),$$

(*) nhưng với hai điểm M và N bất kỳ thì bất đẳng thức (*) sẽ bằng nhau. Tuy nhiên, việc chứng minh thực tế này khá khó khăn (xem N. Burbak và “Cấu trúc liên kết tổng quát” (Moscow, “Nauka”, 1975), bài toán 11 đến § 2 của Chương IX).

N. Vasiliev

M529. a) Đa giác M' là ảnh của đa giác lồi M cùng lúc với hệ số k = -1/2. Chứng minh rằng có một bản dịch song song của T bằng cách tạo T(M') ⊂ M.
b) Với hệ số nào k < 0 là đúng, tương tự như phát biểu về đa giác lồi M trong không gian?

Một). Thoạt nhìn, có sự không chắc chắn về điều kiện bài toán: người ta không cho biết loại đa giác M' làm sẵn nào được tạo ra. Chúng tôi mời người đọc chứng minh bổ đề sau đây về các đa giác M, M' của chúng ta: ảnh của đa giác M' dưới bất kỳ phép truyền song song nào có thể thu được từ M của một số danh pháp có hệ số k (nhưng có tâm khác), và ngược lại, ảnh của đa giác M dưới bất kỳ hình học nào có hệ số k có thể thu được từ M bằng một phép truyền song song nào đó.

Hãy chuyển sang lời giải. Chúng ta hãy chọn trong số các đỉnh của đa giác M tại (ví dụ: A, B và C), tạo thành tam giác ABC trên diện tích lớn nhất có thể (như vậy sẽ được tìm thấy, vì M là hữu hạn số đỉnh). Gọi O là giao điểm các đường trung tuyến của tam giác ABC. Ảnh khoảng cách M'' của đa giác M bằng thước dây Γ có tâm O và hệ số k = -1/2 (Hình 3). Làm thế nào chúng ta

⟦folio 25⟧

lưu ý, đa giác $M''$ có thể thu được từ đa giác $M'$ bằng cách dịch song song. Rõ ràng là nếu $M''$ hóa ra nằm bên trong tam giác $ABC$ (và hơn nữa, bên trong đa giác $M$), thì bài toán sẽ được giải.

Xét tam giác $A'B'C'$ được tạo bởi các đường trung bình của tam giác $ABC$. Vì $\Delta A'B'C' = \Gamma (\triangle ABC)$, các điểm $A', B', C'$ là các đỉnh của đa giác $M''$, với tam giác $A'B'C'$ có diện tích lớn nhất trong số các tam giác được tạo thành bởi các đỉnh của đa giác $M''$. Bây giờ, giả sử một số đỉnh - chẳng hạn như $X$ - của đa giác $M''$ nằm trong tam giác $ABC$, ví dụ: ở các cạnh đối diện của $[AB]$ (Hình 4). Nhưng khi đó tam giác $XA'C'$, rõ ràng nằm bên trong đa giác $M''$, sẽ có diện tích lớn hơn tam giác $ABC$, điều này là không thể. Vì vậy, $M'' \subset \triangle ABC$.

Vấn đề a) đã được giải quyết.

6) Lời giải của đoạn 6) bài toán gần như lặp lại hoàn toàn những điều trên. Trước hết, nếu từ “đa giác” được thay thế bằng “đa diện” thì bổ đề sẽ đúng. Hơn nữa, vai trò của tam giác $ABC$ (diện tích tối đa) sẽ do tứ diện $ABCD$, các đỉnh của chúng là các đỉnh của khối đa diện $M$, và thể tích là lớn nhất trong số các thể tích của tất cả các tứ diện như vậy. Vai trò của tâm đã được chuẩn bị $O$ đóng vai trò hoàn hảo là trọng tâm của khối tứ diện $ABCD$ (như đã biết, nó chia các đoạn nối các đỉnh của khối tứ diện với trọng tâm của các mặt đối diện, theo tỷ lệ 1:3). Người đọc chú ý có lẽ đã đoán được rằng phát biểu ở đoạn 6) sẽ đúng nếu chúng ta đặt $k = -1/3$. Vì, rõ ràng, nó thậm chí còn đúng hơn với $-1/3 \leq k < 0$, đối với lời giải bài toán đầy đủ, vẫn chứng tỏ rằng không thể giảm giá trị của $k = -1/3$. Để chứng minh sự phủ nhận của bất kỳ tuyên bố nào, việc bác bỏ nó trong một số trường hợp cụ thể là đủ. Chúng ta hãy bác bỏ nó khi khối đa diện $M$ là một tứ diện đều.

Để làm điều này, chúng ta hãy chứng minh khẳng định sau: cho $ABCD$ là một khối đa diện đều và $A'B'C'D'$ ảnh của nó với hệ số $k' > -3$ (Hình 5); trung tâm chuẩn bị, như chúng ta đã thấy, không đóng vai trò gì); Không có sự truyền song song nào trong đó ảnh của khối trung diện $ABCD$ sẽ nằm bên trong khối trung diện $A'B'C'D'$.

Thật ra, chúng ta hãy vẽ qua các đỉnh của các mặt phẳng tứ diện $ABCD$ song song với các mặt đối diện của tứ diện (qua đỉnh $A$ có một mặt phẳng song song với mặt $BCD$, v.v.). Khối đa diện (hãy ký hiệu là $A''B''C''D''$), được hình thành bởi các mặt phẳng này, sẽ là một khối tứ diện đều, chuẩn bị khối tứ diện $ABCD$ với hệ số chuẩn bị $k'' = -3$ (tâm được chuẩn bị - ở trọng tâm của khối tứ diện $ABCD$). Điều này có nghĩa là tứ diện mới này “lớn hơn” tứ diện $A'B'C'D'$ (ít nhất là về thể tích)

⟦folio 26⟧

và do đó không thể bị “đẩy” vào nó bằng bất kỳ sự chuyển giao song song nào. Bây giờ chúng ta giả sử rằng có một bản dịch song song $T$ sao cho $T$ ($ABCD$) $\subset A'B'C'D'$. Hãy “đẩy” các cạnh của khối đa diện $A'B'C'D'$ “hướng vào trong” một chút, để chúng song song với chính nó, cho đến khi chạm vào các đỉnh của ảnh của khối đa diện $ABCD$ với phép dịch song song $T$ (tức là với các đỉnh của khối đa diện $T$ ($ABCD$)). Khối đa diện thu được rõ ràng bị tắc nghẽn do việc xây dựng khối đa diện $A''B''C''D''$ trước đó (“lớn hơn” so với khối đa diện $A'B'C'D'$) và nằm bên trong khối đa diện $A'B'C'D'$, điều này là không thể. Điều này có nghĩa là việc truyền song song được yêu cầu không tồn tại.

Lưu ý rằng tứ diện đúng $ABCD$ chỉ cần thiết để làm rõ.

Đối với các khối đa diện không phải khối đa diện, giá trị $k = -1/3$ có thể giảm đi; ví dụ, đối với các vật thể lồi đối xứng tâm (không nhất thiết phải là khối đa diện), hệ số chuẩn bị “tối thiểu” bằng -1. Do đó, các cạnh và hệ số chuẩn bị có thể đóng vai trò là thước đo mức độ “bất đối xứng” của một vật thể lồi. Những câu hỏi tương tự được thảo luận trong tập tài liệu của B. Grew và Baum trong “Etides on combinatorial hình học và lý thuyết về vật lồi” (M., “Nauka”, 1971) và trong cuốn sách của V. G. Boltyansky và I. M. Yaglom “Viupklitse fizura” (M. - L., Gostekhidat, 1951).

Ngoài lời giải bài toán a ở trên), chúng ta còn biết thêm hai lời giải của nó: cái đầu tiên rất đơn giản, nhưng sử dụng định lý Helly “khó” (xem lời giải bài toán 19 từ cuốn sách đã chỉ ra của Boltyansky và Yaglom; ở đó bạn cũng có thể tìm thấy bản phân tích và ứng dụng định lý Helly); ở lần chuẩn bị thứ hai, trọng tâm O của đa giác $M$ được lấy làm mặt phẳng. Rất dễ dàng để xác minh rằng O có các thuộc tính cần thiết.

N. Netsvetaev

F538. Một sợi dây nặng được treo ở các điểm $A$ và $B$ (Hình 6). Giá trị tuyệt đối của lực căng của dây tại điểm $C$ là 20 N. Tìm khối lượng của dây.

Chúng ta biểu thị $m$ khối lượng của dây, $\vec{T}_A$ và $\vec{T}_B$ lực căng của dây tại các điểm $A$ và $B$. (Lực đẩy tại mỗi điểm có phương tiếp tuyến với sợi dây). Vì dây ở trạng thái cân bằng nên tổng các lực tác dụng lên nó bằng 0:

$$\vec{T}_A + \vec{T}_B + mg = 0.$$

Tổng các hình chiếu của các lực tác dụng lên sợi dây lên bất kỳ trục nào, một phần lên trục thẳng đứng $OY$, cũng bằng 0. Kể từ đây,

$$T_{Ay} + T_{By} - m|\vec{g}| = 0,$$

Ở đâu

$$m = \frac{T_{Ay} + T_{By}}{|\vec{g}|}.$$

Vì vậy, để xác định khối lượng của sợi dây, phải xác định $T_{Ay}$ và $T_{By}$. Hãy tìm chúng.

Tiết diện CB của sợi dây ở trạng thái cân bằng. Điều này có nghĩa là tổng các hình chiếu lên trục hoành $OX$ của lực căng tác dụng lên dây tại các điểm $C$ và $B$ bằng 0:

$$T_{Cx} + T_{Bx} = 0.$$

Chúng ta hãy vẽ các lực $\vec{T}_C$ theo thang đo thuận tiện tùy ý (Hình 7). Nó hướng tiếp tuyến với sợi dây tại điểm $C$. Chúng ta hãy tìm hình chiếu của lực $\vec{T}_C$ lên trục $OX$. Bây giờ chúng ta vẽ một đường tiếp tuyến với sợi dây tại điểm $B$. Lực $\vec{T}_B$ hướng dọc theo tiếp tuyến này. Trên trục hoành, chúng ta vẽ hình chiếu của lực $T_{Bx}$ lên trục $OX$, bằng $-T_{Cx}$. Đã khôi phục lại đường vuông góc tại điểm $K$ với

⟦folio none⟧

Cơm. 7.

Cơm. 8.

phần tiếp tuyến tại điểm $B$, ta tìm được lực $\vec{T}_B$. Bây giờ không khó để tìm hình chiếu của lực $\vec{T}_B$ lên trục thẳng đứng. Nó được xác định bởi độ dài của đoạn $KE$, có tính đến tỷ lệ mà chúng ta đã vẽ lực $\vec{T}_C$. Trong trường hợp của chúng tôi $T_{By} \approx 22$ N.

Tương tự, xây dựng lực $\vec{T}_A$ kéo sợi dây tại điểm $A$ (Hình 8) và tìm thấy hình chiếu của nó lên trục $OY$. Trong trường hợp của chúng tôi, nó bằng $\approx 9$ N.

Vì vậy, $m = \frac{22 + 9}{9,8} \text{ кг} \approx 3,2 \text{ кг}$.

I. Slobodetsky

F539. Hình 9 cho thấy hai chu trình nhiệt động khép kín được thực hiện với khí đơn nguyên tử lý tưởng: $1 \rightarrow 2 \rightarrow 3 \rightarrow 4 \rightarrow 1$ và $1 \rightarrow 5 \rightarrow 6 \rightarrow 4 \rightarrow 1$. Chu trình nào có hiệu suất cao hơn? Bao nhiêu lần?

Hiệu suất của chu trình bằng tỷ lệ giữa công $A$ được thực hiện bởi khí với lượng nhiệt $Q$ truyền cho khí trong mỗi chu kỳ. Về mặt số lượng, công việc bằng diện tích được giới hạn bởi lịch trình chu kỳ. Đối với chu kỳ đầu tiên -

$$A_1 = (2 p_0 - p_0)(2 V_0 - V_0) = p_0 V_0,$$

cho chu kỳ thứ hai -

$$A_2 = (4 p_0 - p_0)(2 V_0 - V_0) = 3 p_0 V_0.$$

Hãy tìm điểm nóng $Q_1$ và $Q_2$. Trong trường hợp đầu tiên, nhiệt được truyền sang chất khí theo các phần $1-2$ và $2-3$. Trong trường hợp này, khí nóng lên và ở phần $2-3$ nó cũng hoạt động $A' = 2 p_0 V_0$. Do đó, $Q_1 = A' + \Delta U'$, $\Delta U'$ là độ biến thiên nội năng của chất khí. Vì nhiệt độ của khí tối thiểu tại điểm $1$ và tối đa tại điểm $3$, và nhiệt dung của một kmol khí đơn nguyên tử lý tưởng là $\frac{3}{2} R$,

$$\Delta U' = \frac{3}{2} R v (T_3 - T_1).$$

Ở đây $v$ là số kilomol khí, $T_1 = \frac{p_0 V_0}{\nu R}$, $T_3 = \frac{4 p_0 V_0}{\nu R}$. Do đó $\Delta U' = \frac{9}{2} p_0 V_0$ và $Q_1 = \frac{13}{2} p_0 V_0$. Tương tự, chúng ta tìm chu kỳ thứ hai $A' = 4 p_0 V_0$ (trong vùng $5-6$), $\Delta U'' = \frac{3}{2} R v (T_6 - T_1) = \frac{21}{2} p_0 V_0$ và $Q_2 = \frac{29}{2} p_0 V_0$. Sử dụng dữ liệu thu được, chúng tôi tìm thấy:

$$\eta_1 = \frac{2}{13}, \eta_2 = \frac{6}{29}, \eta_1 / \eta_2 \approx 0,74.$$

A. Zilberman

⟦folio 28⟧

F540. Hai cuộn dây điện cảm $L_1$ và $L_2$ được mắc song song. Cuộn dây sẽ có điểm cực đại trong cuộn dây nếu một tụ điện có điện dung $C$ (Hình 10), được sạc trước đến điện áp $U$?

Cơm. 10.

Vì các cuộn dây được mắc song song nên điện áp trên chúng bằng nhau: $U_{L_1} = U_{L_2}$. Nhưng $U_{L_1} = L_1 \frac{\Delta I_1}{\Delta t}$, $U_{L_2} = L_2 \frac{\Delta I_2}{\Delta t}$.

Kể từ đây,

$$L_1 \frac{\Delta I_1}{\Delta t} = L_2 \frac{\Delta I_2}{\Delta t}.$$

(1)

Tại thời điểm ban đầu, các điểm trong cả hai cuộn dây đều bằng 0, do đó từ (1) suy ra các điểm $I_1$ và $I_2$ tại bất kỳ thời điểm nào đều sao cho

$$L_1 I_1 = L_2 I_2.$$

(2)

(Điều này có nghĩa là dòng điện tối đa trong cuộn dây đạt được đồng thời.)

Rõ ràng là điểm $I_1$ và $I_2$ là lớn nhất khi tụ điện được tích điện. Từ định luật bảo toàn năng lượng suy ra rằng tại thời điểm này

$$\frac{CU^2}{2} = \frac{L_1 I_1^2}{2} + \frac{L_2 I_2^2}{2}.$$

(3)

Từ phương trình (2) và (3) chúng ta tìm thấy:

$$I_1 = U \sqrt{\frac{L_2 C}{L_1 (L_1 + L_2)}}, I_2 = U \sqrt{\frac{L_1 C}{L_2 (L_1 + L_2)}}.$$

O. Savigan

F541. Khe hở của bộ tạo tia lửa điện (Hình 11) được điều chỉnh theo điện áp $U$ và điện trở $R$ của điện trở được chọn ở mức tối đa; Xác định công suất trung bình được giải phóng trên điện trở nếu tụ điện được phóng điện thành công trong quá trình sạc.

Cơm. 11.

Để nguồn phát tia lửa hoạt động ổn định, việc phóng điện trong khe hở tia lửa điện không được ảnh hưởng đến quá trình nạp tụ điện. Điều này có thể xảy ra trong trường hợp thời gian nạp tụ điện qua khe phóng điện nhỏ hơn nhiều so với thời gian nạp tụ điện từ nguồn đến điện áp $U$.

Trong trường hợp này, ở điện áp bằng 0 trên tụ điện, không có dòng điện trong khe hở tia lửa và khe hở được khôi phục về đặc tính điện môi của nó. Sự cố tiếp theo sẽ xảy ra khi điện áp trên khe hở, và do đó trên tụ điện, đạt $U$.

Trong thời gian tụ điện được sạc đến điện áp $U$, pin hoạt động $A = q\varepsilon$, trong đó $q = CU - \varepsilon$ được thực hiện trên tụ điện. Theo định luật bảo toàn năng lượng $A = Q + CU^2/2$, trong đó $Q - \varepsilon$ là năng lượng giải phóng trong quá trình tích điện của tụ điện trên điện trở, $CU^2/2 - \varepsilon$ là năng lượng tích trữ trong tụ điện. Như vậy,

$$CU\varepsilon = Q + CU^2/2,$$

Ở đâu

$$Q = CU\varepsilon (1 - U/2\varepsilon).$$

Vì thời gian nạp của tụ điện qua khe phóng điện ngắn nên có thể tránh được năng lượng giải phóng trong thời gian này trên điện trở.

Nếu trong 1 giây tụ điện được tích điện $n$ lần thì công suất trung bình tỏa ra trên điện trở bằng

$$N = nCU\varepsilon \left(1 - \frac{1}{2} \frac{U}{2}\varepsilon\right).$$

P. Zubkov
