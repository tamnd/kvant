---
id: 1982-2-skorovarov-peremennyiy-elektricheskiy-tok-03e844a7
issue: kvant_1982_2
year: 1982
number: "2"
title: Dòng điện xoay chiều
authors:
  - Скороваров В. Е.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 41
page_last: 44
page_labels: 39-42
tag: 90KB
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 9eeaaccdaf0b2010730158811ab38ed34e0fb6f5b9146175952b92666a88780e
prompt_sha256: draft-1
translated_from: content/ru/1982/02/articles/13_skorovarov-peremennyiy-elektricheskiy-tok-03e844a7.md
source_content_sha256: 2be07a1cb5535c0fb6919dc3145a3de07cae30ec4ae9db25ef642669bc884f0a
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 39⟧

Dòng điện xoay chiều

Dòng điện xoay chiều được sử dụng rộng rãi trong công nghiệp (nhà máy, xí nghiệp) và trong mạng lưới chiếu sáng chung.

Được biết, định luật Ohm được thỏa mãn đối với dòng điện tích hợp - cường độ dòng điện trong một phần đồng nhất của mạch tỷ lệ thuận với điện áp đặt vào. Trong mạch điện xoay chiều, dòng điện cũng phụ thuộc vào điện áp nguồn, nhưng theo một định luật phức tạp hơn, vì điện áp và dòng điện thay đổi theo thời gian. Định luật thay đổi điện áp có thể phức tạp, nhưng ứng dụng phổ biến và thực tế nhất là những ứng dụng có điện áp thay đổi theo định luật điều hòa. Ví dụ như thế này:

$$u = U_m \cos \omega t,$$

trong đó $U_m$ là biên độ điện áp, $\omega$ là tần số tuần hoàn, $\omega t = \varphi$ là pha dao động. Lưu ý rằng ở nước ta, tần số được áp dụng cho tất cả các lãnh thổ của nước này là $v = \omega/2\pi = 50$ Hz.

Mạch điện xoay chiều bao gồm nguồn dòng điện và các bộ phận khác nhau như đèn lưu trữ, thiết bị điện, tụ điện, cuộn dây, động cơ điện và máy biến áp.

Nhiệm vụ chính của việc nghiên cứu dòng điện xoay chiều là tính toán mạch điện, tức là xác định cường độ dòng điện ở điện áp cho trước của nguồn dòng và các thông số cho trước của các phần tử mạch.

Trong trường hợp tổng quát, dòng điện trong mạch giống như điện áp nguồn, thay đổi theo thời gian tuân theo định luật điều hòa

$$i = I_m \cos(\omega t + \varphi).$$

Biên độ dòng điện $I_m$ và độ lệch pha $\varphi$ giữa dòng điện và điện áp phụ thuộc vào các thông số của mạch đã cho.

Trước tiên chúng ta hãy xem xét các mạch điện đơn giản nhất, bao gồm một nguồn và một phần tử - điện trở, tụ điện hoặc cuộn dây. Khi nối với nguồn điện trở tác dụng, trong mạch sẽ xuất hiện một dòng điện xoay chiều có biên độ bằng biên độ điện áp chia cho điện trở tác dụng: $I_{RM} = U_m/R$ và pha trùng với pha của điện áp. Trong mạch có tụ điện, dòng điện cùng pha xác định điện áp ở $\pi/2$ và biên độ của dòng điện $I_{CM} = U_m \omega C$, trong đó $C$ là điện dung của tụ điện. Dòng điện xuất hiện trong cuộn dây có độ tự cảm $L$ lệch pha so với điện áp $\pi/2$ và biên độ của nó là $I_{LM} = U_m / (\omega L)$.

Thật thuận tiện để tính toán các mạch điện bằng cách sử dụng sơ đồ vectơ của dòng điện và điện áp. Hãy xây dựng sơ đồ vectơ cho khoảng cách của các trường hợp đơn giản nhất (Hình 1). Hãy bắt đầu với vectơ điện áp đã biết $\vec{U}_m$ và đặt nó theo chiều ngang. Vì dòng điện qua điện trở tác dụng cùng pha với điện áp nên chúng ta sẽ định hướng vectơ dòng điện $\vec{I}_{RM}$ giống như vectơ $\vec{U}_m$. Dòng điện trong mạch với tụ điện xác định điện áp pha trong chu kỳ thứ tư; do đó, vectơ hiện tại $\vec{I}_{CM}$ phải hướng thẳng đứng lên trên. Cuối cùng, dòng điện trong cuộn dây chậm hơn điện áp một khoảng

⟦folio 40⟧

Cơm. 2.

π/2, do đó vectơ hiện tại $I_{LM}$ phải hướng thẳng đứng xuống dưới.

Lưu ý rằng tất cả các mối quan hệ thu được về biên độ của dòng điện và điện áp cũng có giá trị đối với các giá trị hiệu dụng của chúng. Sơ đồ vectơ cũng có thể được xây dựng bằng cách sử dụng các giá trị hiệu dụng của dòng điện và điện áp.

Bây giờ chúng ta hãy xem điều này bài toán:

Bài toán 1. Xác định cường độ dòng điện trong mạch như hình 2, a. Xét các thông số của các phần tử mạch điện và điện áp của nguồn điện theo quy định.

Đầu tiên, hãy xem xét một phần của mạch chứa một kết nối song song của một điện trở có điện trở $R_1$ và một tụ điện có điện trở $C$. Hãy xây dựng sơ đồ vectơ cho nó, coi điện áp $U_1$ trong phần này đã biết (Hình 2, b). Ta thấy cường độ dòng điện trong mạch bằng tổng cường độ dòng điện qua điện trở và tụ điện thứ nhất:

$$\overrightarrow{I} = \overrightarrow{I_{R1}} + \overrightarrow{I_C}.$$

Biên độ của dòng điện này bằng

$$I = \sqrt{I_{R1}^2 + I_C^2} = \sqrt{\left(\frac{U_1}{R_1}\right)^2 + \left(U_1 \omega C\right)^2} = U_1 \sqrt{\frac{1}{R_1^2} + (\omega C)^2}.$$

Cùng một dòng điện chạy qua một điện trở có điện trở $R_2$, nên điện áp trên nó bằng nhau

$$U_2 = IR_2.$$

Rõ ràng là tổng vectơ của $U_1$ và $U_2$ bằng điện áp $\overrightarrow{U}$ tại các cực nguồn:

$$\overrightarrow{U}_1 + \overrightarrow{U}_2 = \overrightarrow{U}.$$

Chúng ta chiếu vectơ $\overrightarrow{U}_2$ lên trục tọa độ $X$ và $Y$ rồi tìm

$$U_{2x} = U_1 \frac{R_1}{R_2}, \quad U_{2y} = U_1 R_1 \omega C.$$

Từ đồ thị vector có thể thấy rằng

$$U^2 = \left(U_1 + U_{2x}\right)^2 + U_{2y}^2,$$

hoặc

$$U = U_1 \sqrt{\left(1 + \frac{R_1}{R_2}\right)^2 + \left(R_1 \omega C\right)^2}.$$

Cuối cùng, từ đẳng thức (1) và (2) chúng ta thu được

$$I = U \sqrt{\frac{1 + \left(R_2 \omega C\right)^2}{\left(R_1 + R_2\right)^2 + \left(R_1 R_2 \omega C\right)^2}}.$$

Năng lượng được giải phóng trong mạch điện có tầm quan trọng thực tế rất lớn. Trong trường hợp dòng điện một chiều, đối với bất kỳ phần nào của mạch điện, công suất được xác định bằng tích của điện áp và dòng điện. Nguồn điện xoay chiều phụ thuộc vào các giá trị hiệu dụng của dòng điện và điện áp, cũng như sự dịch pha giữa dòng điện và điện áp trong phần này:

$$P = UI \cos \varphi,$$

trong đó cos φ là hệ số công suất.

Như bạn đã biết, để có được công suất tối đa từ nguồn DC, bạn cần kết nối một tải có điện trở bằng điện trở trong của nguồn. Nguồn AC cũng có điện trở trong, nó không chỉ hoạt động mà còn có tính cảm ứng. Thật thú vị khi biết loại tải nào cần được kết nối để có được công suất tác dụng tối đa trong mạch điện xoay chiều. Đáp số câu hỏi này được trả lời bởi bài toán sau:

Bài toán 2. Thông số điện áp phải như thế nào để công suất tiêu thụ ở điện áp đó là tối đa? Điện trở hoạt động của nguồn là $R$, độ tự cảm của nó là $L$.

Vì công suất giải phóng ở điện áp phụ thuộc vào độ dịch pha giữa dòng điện và điện áp, nên tự nhiên giả sử rằng một tụ điện nối tiếp với điện trở tác dụng của điện áp được bật lên nhiều hơn (để bù

⟦folio 41⟧

Điều này là do sự dịch pha được tạo ra bởi độ tự cảm của nguồn).

Chúng ta biểu thị bằng $\mathcal{E}$ suất điện động của nguồn, bằng $R_{\mathrm{H}}$ điện trở hiệu dụng và $C$ điện dung của tụ điện. Khi đó dòng điện sẽ chạy trong mạch

$$I = \frac{\mathcal{E}}{\sqrt{(R_{\mathrm{H}}+R)^{2} + (\omega L-1/\omega C)^{2}}},$$

và công suất tác dụng sẽ được giải phóng khi tải

$$P = U_{\mathrm{H}} I \cos \varphi = I^{2} R_{\mathrm{H}} = \frac{\mathcal{E}^{2} R_{\mathrm{H}}}{(R_{\mathrm{H}}+R)^{2} + (\omega L-1/\omega C)^{2}}.$$

Rõ ràng, với bất kỳ giá trị nào của $R_{\mathrm{H}}$ thì lũy thừa sẽ lớn nhất hoặc ngược lại thì đẳng thức

$$\omega L - \frac{1}{\omega C} = 0.$$

Điều này có nghĩa là điện dung của tụ điện phải bằng

$$C = \frac{1}{\omega^{2} L}.$$

Trong trường hợp này công suất bằng nhau

$$P = \frac{\mathcal{E}^{2} R_{\mathrm{H}}}{(R_{\mathrm{H}}+R)^{2}}.$$

Để tìm công suất cực đại tùy thuộc vào điện trở $R_{\mathrm{H}}$, chúng ta đánh đồng đạo hàm của $P$ với $R_{\mathrm{H}}$ bằng 0:

$$P'(R_{\mathrm{H}}) = \frac{\mathcal{E}^{2} ((R_{\mathrm{H}}+R)^{2} - 2 R_{\mathrm{H}} (R_{\mathrm{H}}+R))}{(R_{\mathrm{H}}+R)^{4}} = 0.$$

Từ đây

$$R_{\mathrm{H}} = R, \quad P_{\text{max}} = \frac{\mathcal{E}^{2}}{4 R}.$$

Lưu ý rằng chúng ta thu được các mối quan hệ giống hệt như đối với dòng điện xây dựng.

* * *

Máy biến áp chiếm một vị trí đặc biệt trong mạch điện xoay chiều. Đây là thiết bị truyền năng lượng điện từ mạch này sang mạch khác, đồng thời chuyển đổi dòng điện và điện áp. Đây là nơi xuất phát cái tên "máy biến áp", tức là "bộ chuyển đổi". Nguyên lý hoạt động của máy biến áp dựa trên hiện tượng cảm ứng điện từ nên chỉ có thể hoạt động bằng dòng điện xoay chiều.

Máy biến áp bao gồm một lõi sắt từ khép kín, trên đó có hai cuộn dây đồng (đôi khi nhiều hơn) được quấn. Cuộn dây thường được gọi là cuộn dây máy biến áp. Tuy nhiên, trong số đó, cái chính được nối với nguồn, cái còn lại, cái thứ cấp, được nối với tải. (Tuy nhiên, việc tách các cuộn dây như vậy là có điều kiện, vì tùy thuộc vào chế độ vận hành, kết nối có thể ngược lại.) Các cuộn dây có thể được quấn trên lõi theo hai cách: theo một hướng hoặc theo các hướng khác nhau. Tùy thuộc vào điều này, điện áp trên cuộn dây sẽ thay đổi cùng pha hoặc ngược pha. Để xác định các điều kiện làm việc ở cuối cuộn dây và giả sử rằng tại bất kỳ thời điểm nào điện áp giữa đầu và cuối mỗi cuộn dây có cùng cực tính. Trong tranh ảnh và hình vẽ, phần đầu của cuộn dây thường được đánh dấu bằng dấu hoa thị.

Việc tính toán mạch điện với máy biến áp thực tế là rất khó khăn. Để kiểm soát sự rối loạn, cái gọi là máy biến áp lý tưởng. (Lưu ý rằng kết quả tính toán của máy biến áp lý tưởng và máy biến áp thực tế trùng khớp với nhau.) Đầu tiên, chúng ta giả sử rằng các cuộn dây không có điện trở hoạt động, do đó điện áp phía trước trong chúng bằng 0 và đẳng thức được thỏa mãn

$$\frac{U_{1}}{U_{2}} = \frac{\mathcal{E}_{1}}{\mathcal{E}_{2}} = \frac{n_{1}}{n_{2}} = K.$$

Ở đây $U_{1}$ và $U_{2}$ là điện áp, $\mathcal{E}_{1}$ và $\mathcal{E}_{2}$ là emf cảm ứng, $n_{1}$ và $n_{2}$ là số vòng dây của cuộn sơ cấp và thứ cấp tương ứng; $K = n_{1}/n_{2}$—hệ số biến đổi. Thứ hai, chúng ta sẽ không tính đến tổn thất năng lượng do sinh nhiệt không chỉ trong cuộn dây mà còn trong lõi của máy biến áp. Điều này có nghĩa là công suất đi vào cuộn sơ cấp bằng công suất để cuộn thứ cấp tiếp xúc với tải, hay nói cách khác, tổng công suất vào và ra bằng 0:

$$U_{1} I_{1} + U_{2} I_{2} = 0,$$

trong đó $I_{1}$ và $I_{2}$ là dòng điện trong cuộn sơ cấp và thứ cấp của cuộn dây tương ứng.

⟦folio 42⟧

Từ hai đẳng thức ta có

$$I_1 n_1 + I_2 n_2 = 0.$$
Tầm quan trọng của công thức đơn giản này cho phép bài toán sau:

Bài toán 3. Một máy biến áp có số vòng dây ở cuộn sơ cấp $n_1$ và ở cuộn thứ cấp $n_2$, được nối với nguồn điện xoay chiều có suất điện động $\mathcal{E}$ và điện trở trong $R_B$. Dây có điện trở $R_H$ được nối như hình 3. Xác định điện áp trên mỗi điện áp.

Chúng ta hãy biểu thị bằng $U_1$ và $U_2$, $I_1$ và $I_2$ lần lượt là giá trị hiệu dụng của điện áp và dòng điện trong cuộn sơ cấp và cuộn thứ cấp, và bằng $I_0$ giá trị hiệu dụng của dòng điện trong nguồn. Giả sử tại một thời điểm nào đó dòng điện có hướng như trên Hình 3. Khi đó

$$I_0 R_B = \mathcal{E} - U_1, \quad I_2 R_H = U_1 - U_2,$$
$$I_0 = I_1 + I_2, \quad \frac{U_1}{U_2} = \frac{n_1}{n_2}, \quad I_1 n_1 + I_2 n_2 = 0.$$

Ba đẳng thức đầu tiên không khác với các đẳng thức tương tự đối với mạch điện một chiều và ghi lại, có tính đến quy tắc dấu cho EMF, dòng điện và sụt áp. Ký hiệu điện áp trên các cuộn dây được chọn tùy theo vị trí đầu và cuối cuộn dây. Điều kiện là điện áp được coi là dương nếu khi đi vòng quanh mạch tương ứng, đầu cuối của cuộn dây gặp đầu tiên. Vì vậy, nếu bỏ qua các đường viền của mạch sơ cấp và thứ cấp của một máy biến áp nhất định, chẳng hạn như theo chiều kim đồng hồ, thì điện áp $U_1$ trong phương trình thứ nhất và $U_2$ trong phương trình thứ hai phải được viết bằng dấu “trừ”. Trong phương trình thứ tư, dấu $U_1$ và $U_2$ luôn được coi là dương. Dấu của dòng điện trong cuộn dây theo phương trình thứ năm được chọn như sau: dòng điện được coi là dương nếu nó ở mức

Cơm. 3.

duỗi thẳng từ đầu cuộn dây đến cuối cuộn dây và được in - trong trường hợp ngược lại.

Bằng cách khoanh tròn tất cả năm phương trình trong hệ và giải nó, chúng ta tìm được dòng điện $I_2$ và do đó tìm được hướng tác dụng lên tải:

$$U_H = I_2 R_H = \mathcal{E} \frac{R_H n_1 (n_1 - n_2)}{(n_1 - n_2)^2 R_B + R_H n_1^2}.$$

Bài tập

1. Xác định cường độ dòng điện trong mạch như hình 4. Xét vị trí nguồn điện và các thông số của các phần tử mạch như đã cho.

Cơm. 4.

2. Một mạch gồm hai điện trở giống hệt nhau có điện trở $R$, một cuộn cảm $L$ và một tụ điện $C$ được nối, như trong Hình 5, với một máy phát dòng điện hình sin có tần số thay đổi. Tìm sự tương ứng giữa các tham số của các phần tử mạch mà tại đó mục tiêu sẽ hoạt động giống như một điện trở chỉ có điện trở hoạt động ở bất kỳ tần số nào.

Cơm. 5.

3. Khi truyền năng lượng điện đi một khoảng cách xa, độ tự cảm chủ yếu chịu trách nhiệm cho công suất truyền đi. Giả sử máy phát điện của nhà máy điện tạo ra EMF $\mathcal{E}$, đường dây truyền tải có độ tự cảm $L$ và hướng của hệ thống phải là $U$, hãy xác định công suất tác dụng tối đa có thể truyền đi trong trường hợp này.

Cơm. 6.

4. Một máy biến áp có số vòng dây ở cuộn sơ cấp $n_1$, ở cuộn thứ cấp $n_2$ và hai điện trở có điện trở $R_1$ và $R_2$ được nối vào nguồn điện xoay chiều có điện áp $U$ như hình 6. Xác định điện áp trên các cuộn dây của máy biến áp và cường độ dòng điện qua các điện trở.
