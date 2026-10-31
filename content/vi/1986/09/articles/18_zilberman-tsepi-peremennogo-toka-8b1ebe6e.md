---
id: 1986-9-zilberman-tsepi-peremennogo-toka-8b1ebe6e
issue: kvant_1986_9
year: 1986
number: "9"
title: mạch điện xoay chiều
authors:
  - Зильберман А. Р.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 53
page_last: 57
page_labels: 51-55
tag: 6GOK
lang: vi
source: kvant_digital
extraction: vision
content_sha256: f753475849124670078a89863a2295ce1350ded38fda39c8c0c8a7ec64b2ec8f
prompt_sha256: draft-1
translated_from: content/ru/1986/09/articles/18_zilberman-tsepi-peremennogo-toka-8b1ebe6e.md
source_content_sha256: e69aa97dcb39fc22e1c8a02046b60b7709115575d7f457bc67c551fdf1d31819
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 51⟧

mạch điện xoay chiều

A. R. ZILBERMAN

Dòng điện xoay chiều (hoặc điện áp) thể hiện sự dao động điện cưỡng bức. Cường độ dòng điện thay đổi theo thời gian tuân theo định luật điều hòa

$$i = I_m \cos(\omega t + \varphi_0),$$

trong đó $I_m$ là biên độ, $\omega$ là tần số dốc (theo chu kỳ) (được đo bằng radian trên giây và được viết đơn giản là $c^{-1}$), $\varphi_0$ là pha ban đầu của dao động. Một lực cưỡng bức tương tự có thể được viết cho điện áp xoay chiều.

Ví dụ. Hãy viết sự phụ thuộc thời gian của điện áp mạng: 220 V, 50 Hz. Trong trường hợp này, biên độ $U_m = U \sqrt{2} = 220 \sqrt{2}$ V≈311 V (hãy nhớ rằng $U = 220$ V là giá trị điện áp hiệu dụng), tần số dốc $\omega = 2\pi v \approx 6,28 \cdot 50 \text{ c}^{-1} \approx 314 \text{ c}^{-1}$. Hãy cho chúng tôi biết rằng tại thời điểm báo cáo bắt đầu ($t=0$), điện áp bằng $u_0 = 50$ V và đang giảm dần. Sau đó, chúng ta có thể tìm thấy pha ban đầu $\varphi_0$:

$$u_0 = U_m \cos \varphi_0,$$

ở đâu $\varphi_0 = \arccos \frac{u_0}{U_m} \approx 1,4$ vui mừng

(hãy tự suy nghĩ - chúng tôi đã dạy cách giảm căng thẳng ở đâu). Vì thế,

$$u = 311 \cos (314t + 1,4).$$

Có thể thấy rằng sự lựa chọn thích hợp của báo cáo đầu thời gian - và điều này nằm trong khả năng của chúng tôi - có thể được thực hiện $\varphi_0$ bất cứ điều gì, đặc biệt là số 0. Điều này thường được sử dụng và viết ra mà không cần đặt trước đặc biệt

$$u = U_m \cos \omega t.$$

Việc tính toán các mạch điện xoay chiều thường dựa trên việc xác định dòng điện ở một điện áp nguồn nhất định. Việc tính toán dòng điện trong mạch chỉ chứa điện trở là khá dễ dàng. Tại bất kỳ điểm nào trong mạch điện như vậy, dòng điện thay đổi “đúng lúc” với

⟦folio 52⟧

Hình 1.

hướng tác dụng, nghĩa là không có sự dịch pha giữa dòng điện và hướng. Tình hình phức tạp hơn nếu mạch chứa các thiết bị lưu trữ năng lượng - cuộn dây và tụ điện. Trong trường hợp này, mômen của hướng và dòng điện cực đại có thể không trùng nhau - xuất hiện sự dịch pha tương ứng. Ví dụ, người ta biết rằng khi một cuộn dây được kết nối với mạng, cực đại hiện tại sẽ trễ hơn cực đại phương một phần tư chu kỳ (độ dịch pha π/2) và khi một tụ điện được nối thì ngược lại, chúng đi trước một phần tư chu kỳ.

Khi tính toán trong mạch DC, bạn có thể chỉ cần cộng các giá trị hướng trên các phần tử nối tiếp và các giá trị dòng điện trên các phần phân nhánh của mạch. Trong trường hợp dòng điện xoay chiều, mọi thứ phức tạp hơn - biên độ của tổng không phải lúc nào cũng bằng tổng biên độ. Ví dụ, biên độ của tổng của hai dòng điện 1 A, mỗi dòng có thể là bất kỳ - từ 0 đến 2 A, bạn cần chỉ định nó có tính đến sự dịch pha. Để tính toán mạch điện xoay chiều, người ta thường sử dụng phương pháp đồ họa thuận tiện - phương pháp sơ đồ vectơ. Nó dựa trên một ý tưởng đơn giản.

Để vectơ $\vec{A}_0$ (chiều dài $A_0$) quay toàn bộ hình tròn có một trong hai đầu của nó ngược chiều kim đồng hồ với vận tốc góc $\omega$. Khi đó hình chiếu của đầu thứ hai lên trục $X$, điểm đầu nằm ở tâm quay (hình 1), bằng $x = A_0 \cos (\omega t + \varphi_0)$.

Tức là chúng ta có được chính xác hàm mà chúng ta quan tâm. (Thực ra phần hình tròn được ký hiệu bằng chữ cái giống như phần góc

Hình 2.

tốc độ, chúng tôi nghĩ đến mô hình này.) Trên cùng hình, chúng ta có thể mô tả một vectơ khác $\vec{A}_1$, tương ứng với một hàm khác có biên độ $A_1$ và pha ban đầu $\varphi_1$. Tại $\varphi_1 > \varphi_0$, vectơ $\vec{A}_1$ “dẫn” vectơ $\vec{A}_0$ một góc $\Delta \varphi = \varphi_1 - \varphi_0$. Điều quan trọng là $A_0$ và $A_1$ có thể có kích thước khác nhau (ví dụ: $A_0$ có thể khác nhau về điện áp và $A_1$ về cường độ ampe).

Bây giờ về phương pháp chính nó. "sơ đồ vectơ" là gì? Đây là bản vẽ mô tả dưới dạng vectơ (theo tỷ lệ mới được chọn và có tính đến sự dịch pha) hướng và dòng điện của mạch đang nghiên cứu. Trong trường hợp dao động điều hòa mà chúng ta đang xem xét (trong các trường hợp khác, điều này không đúng!) tất cả các vectơ này quay theo một hướng với cùng vận tốc góc $\omega$ và góc giữa chúng không đổi, vì vậy chúng ta không cần phải nói về chuyển động quay và vẽ một bức tranh “đứng yên”. Nếu một bản vẽ đã được xây dựng thì bài toán đã được giải vì nó chứa tất cả thông tin cần thiết về hướng và dòng điện tương tác của mạch điện. Phương pháp xây dựng sơ đồ vectơ là cách để có được những hình vẽ như vậy.

Hãy xem xét một vài ví dụ cụ thể.

Nhiệm vụ 1. hình 2 trình bày một mạch điện đơn giản chứa một tụ điện và điện trở mắc nối tiếp. Biên độ của dòng điện trong mạch là $I_m = 0,1$ A. Tìm biên độ của hướng của nguồn và pha giữa hướng này và dòng điện trong mạch.

Chúng ta hãy chọn tỷ lệ thích hợp để mô tả dòng chảy và hướng. Hãy vẽ tùy ý (theo cách thuận tiện cho chúng ta!) vectơ $\vec{I}_m$ (hình 3). Bây giờ chúng ta có thể vẽ vectơ $\vec{U}_{Rm}$, được mô tả bằng hướng trên điện trở (chúng ta sẽ mô tả nó bằng màu khác để không nhầm lẫn giữa vectơ chỉ phương và

⟦folio 53⟧

kov). Mô-đun của nó
$$U_{Rm} = I_m R = 50 \text{ В}.$$
Theo hướng, vectơ $\vec{U}_{Rm}$ trùng với vectơ $\vec{I}_m$ (xét cho cùng, độ lệch pha giữa dòng điện và hướng của điện trở bằng 0). Vectơ chỉ hướng trên tụ điện $\vec{U}_{Cm}$ có ​​độ lớn bằng $U_{Cm} = I_m X_C = 100 \text{ В}$, trong đó $X_C = 1 / (\omega C) = 1 \text{ кОм} - \text{емкостьное сопротивление},$ và trễ $\pi/2$ cùng pha so với dòng điện. Hãy vẽ vector này nữa. Điện áp tại nguồn $\vec{U}_m$ tương ứng với tổng vectơ $\vec{U}_{Rm}$ và $\vec{U}_{Cm}$:
$$U_m = \sqrt{U_{Rm}^2 + U_{Cm}^2} \approx 112 \text{ В}.$$
Lưu ý rằng chúng ta đã tìm thấy (đã vẽ!) góc giữa dòng điện $\vec{I}_m$ và hướng của toàn bộ mạch $\vec{U}_m$. Góc này có thể được thay đổi đơn giản bằng một bộ chuyển đổi hoặc được tính theo lượng giác:
$$\text{tg} \varphi = \frac{U_{Cm}}{U_{Rm}} = 2,$$
$$\varphi = \arctg 2 \approx 1,1 \text{ рад} \approx 64^\circ.$$
bài toán này có thể được xây dựng hơi khác một chút: đặt biên độ hướng của nguồn, ví dụ $U'_m = 220 \text{ В}$ và tìm biên độ của dòng điện trong mạch. bài toán này khó hơn - suy cho cùng, chúng ta phải tìm sơ đồ để vẽ mà không biết biên độ của dòng điện $I'_m$. Có hai khả năng ở đây. Đầu tiên là giải phụ trợ bài toán về việc tìm biên độ của hướng $U_m$ tại một dòng điện cho trước $I_m$ (chúng ta vừa thảo luận về điều này bài toán), sau đó viết ra một phương trình tương tự
$$\frac{U'_m}{U_m} = \frac{I'_m}{I_m}$$
và tìm biên độ hiện tại $I'_m$ từ nó:
$$I'_m = I_m \frac{U'_m}{U_m} \approx 0,18 \text{ А}.$$
Khả năng thứ hai là vẽ sơ đồ không theo thang số cụ thể mà theo cách tổng quát. Trong trường hợp này, tỷ lệ độ dài của các vectơ dư bằng nhau, có nghĩa là góc giữa chúng không thay đổi. Công thức thu được từ sơ đồ
$$U'_m = \sqrt{(U'_{Rm})^2 + (U'_{Cm})^2} = \sqrt{(I'_m R)^2 + (I'_m X_C)^2}$$
chúng tôi sử dụng $I'_m$ để tìm:
$$I'_m = \frac{U'_m}{\sqrt{R^2 + X_C^2}} \approx 0,18 \text{ А}.$$
Các phương pháp này có độ phức tạp xấp xỉ bằng nhau.

Hình 4.
Bài toán 2. Hai nhánh định hướng được nối với nguồn hướng xen kẽ. Biên độ hiện tại ở lần thứ nhất là $I_{1m} = 1 \text{ А}$, ở lần thứ hai là $I_{2m} = 0,3 \text{ А}$. Biên độ của dòng điện chạy qua nguồn có thể nằm trong giới hạn nào? Độ lệch pha cực đại giữa dòng điện và dòng điện trong nhánh thứ nhất có thể là bao nhiêu?

Lời giải rõ ràng từ hình 4, hiển thị sơ đồ vectơ cho mạch này (vectơ $\vec{I}_{2m}$ được vẽ để thuận tiện hơn khi cộng nó với vectơ $\vec{I}_{1m}$):
$$I_{1m} - I_{2m} \leq I_m \leq I_{1m} + I_{2m},$$
$$0,7 \text{ А} \leq I_m \leq 1,3 \text{ А}.$$
Góc tối đa giữa $\vec{I}_m$ và $\vec{I}_{1m}$ tương ứng với:
$$\sin \varphi_{\max} = \frac{I_{2m}}{I_{1m}} = 0,3,$$
$$\varphi_{\max} \approx 0,31 \text{ рад} \approx 18^\circ.$$
Đồng thời $I_m = \sqrt{I_{1m}^2 - I_{2m}^2} \approx 0,95 \text{ А}$. Góc giữa $\vec{I}_m$ và $\vec{I}_{2m}$ có ​​thể là bất kỳ (từ - $\pi$ đến +$\pi$).

Bài toán 3. Trong mạch điện ở hình 5, hãy tìm dòng điện chạy qua nguồn và chạy qua các pha giữa dòng điện này và chiều của nguồn.

Hãy bắt đầu vẽ sơ đồ bằng cách yêu cầu dòng điện chạy qua cuộn dây. Ví dụ: hãy đặt $I_{Lm} = 0,1 \text{ А}$. Khi đó hướng trên cuộn dây $\vec{U}_{Lm}$ có độ lớn bằng $U_{Lm} = I_{Lm} X_L = 100 \text{ В}$, trong đó $X_L = \omega L = 1 \text{ кОм} - \text{индуктивное сопротивление},$ xác định dòng điện $\vec{I}_{Lm}$ cùng pha

Hình 5.

⟦folio 54⟧

bằng π/2 (hình 6). Dòng điện chạy qua một điện trở có điện trở $R_2$ được xác định bởi điện áp này và cùng pha với nó:

$$I_{R_2m} = \frac{U_{Lm}}{R_2} = 0,05 \text{ A}.$$

Khi đó tổng dòng điện

$$I_m = \sqrt{I_{Lm}^2 + I_{R_2m}^2} \approx 0,112 \text{ A}.$$

Điện áp $\vec{U}_{R_1m}$ trên một điện trở có điện trở $R_1$ cùng pha với dòng điện này:

$$U_{R_1m} = I_m R_1 \approx 112 \text{ B}.$$

Sau đó, chúng ta tìm tổng điện áp $\vec{U}_m$ (tổng của các vectơ $\vec{U}_{R_1m}$ và $\vec{U}_{Lm}$). Sau khi tính toán đơn giản (điều này cũng có thể được thực hiện bằng đồ họa, nếu bạn cẩn thận xây dựng sơ đồ!) Chúng ta nhận được

$$U_m \approx 180 \text{ B}, \quad \varphi \approx 0,52 \text{ рад} \approx 30^\circ.$$

Bây giờ bạn có thể tinh chỉnh thang đo và tìm tổng dòng điện trong mạch ở điện áp nguồn nhất định:

$$I'_m = I_m \frac{U'_m}{U_m} \approx 0,112 \frac{200}{180} \text{ A} \approx 0,124 \text{ A}.$$

Tất cả các dòng điện và điện áp khác cũng sẽ tăng $U'_m / U_m \approx 1,1$ lần, trong khi giá trị pha vẫn giữ nguyên.

Các phần tử phản kháng - cuộn dây, tụ điện - thường được sử dụng để thu được dwga pha nhất định giữa điện áp và dòng điện trong mạch. Hãy xem xét một ví dụ cụ thể.

Bài toán 4. Một động cơ điện xoay chiều có hai cuộn dây giống hệt nhau (độ tự cảm của từng pha giữa điện áp và dòng điện trong mạch. Chúng ta hãy xem một ví dụ cụ thể.

Bài toán 4. Một động cơ điện xoay chiều có hai cuộn dây giống hệt nhau (độ tự cảm của từng pha giữa điện áp và dòng điện trong mạch. Chúng ta hãy xem một ví dụ cụ thể.

Khi bật ($U = 220 \text{ B}, \nu = 50 \Gamma_u$), một trong các cuộn dây được kết nối trực tiếp với mạng và cuộn dây còn lại được kết nối thông qua kết nối nối tiếp với tụ điện có điện dung $C$ và điện trở có điện trở $R$. Tính các đại lượng cần thiết $C$ và $R$. Pogerami trong vòng xoáy của những lời tuyên bố.

Dòng điện trong cuộn dây được nối trực tiếp với mạng, lệch pha so với điện áp mạng π/2. Mô-đun của nó

$$I_1 = \frac{U}{X_L} = \frac{U}{2\pi vL} \approx 0,7 \text{ A}.$$

Lưu ý rằng chúng tôi đã tìm thấy giá trị rms của dòng điện vì giá trị đặt $U$ là rms. Rõ ràng là biểu đồ vectơ có thể được xây dựng cho cả biên độ và giá trị hiệu dụng - miễn là một biểu đồ chứa biên độ hoặc giá trị hiệu dụng.

Hãy xây dựng sơ đồ vectơ cho mạch tuần tự $RCL$ (hình 7). Chúng tôi sẽ vẽ mọi thứ ở dạng chung. Hãy vẽ vectơ $\vec{I}_2$ tương ứng với dòng điện trong mạch. Điện áp $\vec{U}_R$ ($U_R = I_2R$) cùng pha với dòng điện, $\vec{U}_C$ ($U_C = I_2X_C$) chậm hơn π/2, $\vec{U}_L$ ($U_L = I_2X_L$) dẫn trước π/2. Tổng điện áp $\vec{U}$ phải cùng pha với dòng điện $\vec{I}_2$, trong khi dòng điện $\vec{I}_1$ và $\vec{I}_2$ sẽ lệch pha π/2.

Từ sơ đồ có thể thấy rằng điều này đòi hỏi

$$X_C = X_L, \frac{1}{\omega C} = \omega L,$$

$$C = \frac{1}{\omega^2 L} = 10^{-5} \Phi = 10 \text{ мкФ}.$$

Đồng thời $I_2 = I_1 = U/R$, từ đâu

$$R = \frac{U}{I_1} \approx 314 \text{ Om}.$$

Lưu ý rằng việc tính toán mạch như vậy trong trường hợp thực tế phức tạp hơn nhiều, vì pha dw giữa điện áp và dòng điện trong cuộn dây của máy đào có tải không bằng π/2, như trong cuộn dây lý tưởng, mà phụ thuộc vào điện áp trên trục máy đào.

Tính toán năng lượng trong mạch điện xoay chiều rất phức tạp bởi thực tế là

⟦folio 55⟧

SỨC MẠNH TỨC THÌ THAY ĐỔI THEO THỜI GIAN. Chúng ta có thể quan tâm đến cả giá trị công suất trung bình - để tính công của nguồn hoặc nhiệt sinh ra trong mạch và giá trị tối đa của CÔNG SUẤT TỨC THỜI.

Bài 5. Biên độ điện áp của nguồn $U_m$, biên độ dòng điện chạy qua nó $I_m$, tính từ các pha giữa điện áp và dòng điện f. Xác định công của nguồn trong khoảng thời gian dài $T$ và giá trị lớn nhất của CÔNG SUẤT TỨC THỜI.

Hãy viết biểu thức cho sức mạnh TỨC THÌ và đưa nó về dạng thuận tiện hơn:
$$p = ui = U_m I_m \cos \omega t \cos (\omega t + \varphi) = \frac{1}{2} U_m I_m \cos (2\omega t + \varphi) + \frac{1}{2} U_m I_m \cos \varphi.$$
Giá trị trung bình của số hạng đầu tiên trong một khoảng thời gian lớn (thời gian dao động dài hơn nhiều) bằng không. Khi đó công suất trung bình
$$\bar{P} = \frac{1}{2} U_m I_m \cos \varphi$$
và nguồn công việc
$$A = \bar{P} T = \frac{1}{2} U_m I_m T \cos \varphi.$$
Giá trị tối đa của số hạng đầu tiên trong giá trị tuyệt đối là $1/2 U_m I_m$ và
$$P_m = \frac{1}{2} U_m I_m (1 + |\cos \varphi|).$$
Có thể thấy, ở mức $|\varphi| \approx \pi/2$ công suất cực đại có thể cao gấp nhiều lần mức trung bình. Điều này là do mạch điện khi làm nóng năng lượng sẽ giải phóng năng lượng trở lại nguồn. Chế độ này rất có hại cho việc cấp nguồn cho mạng - tổn thất nhiệt tỏa ra tăng lên. Một ví dụ về mạch như vậy là đèn huỳnh quang. Dòng điện của nó bị giới hạn bởi một cuộn dây có độ tự cảm cao và các pha được chuyển đổi

Hình 8.

Hình 9.

gần với $\pi/2$. Đầu ra rất đơn giản - kết nối một tụ điện song song với mạch. Nếu bạn chọn đúng điện dung của nó (hãy nghĩ về nó), thì cuộn dây và tụ điện sẽ trao đổi năng lượng với nhau và chỉ có năng lượng hữu ích từ mạng mới là tối ưu.

Nhiệm vụ 6. Giá trị hiệu dụng của điện áp mạng vào buổi tối có thể dao động từ 220 đến 190 V. Để duy trì công suất của lò hơi ở mức thu, nên bật nguồn điện áp DC thu được nối tiếp với nó. Điện áp $U_n$ của nó phải ở mức điện áp mạng tối thiểu là bao nhiêu?

Điện áp cấp vào lò hơi là
$$u_k = U_{2m} \cos \omega t + U_n,$$
trong đó $U_{2m} = 190 \sqrt{2} \text{ В}$ là giá trị biên độ thấp nhất của điện áp mạng. Độ lệch pha giữa điện áp trên nồi hơi và dòng điện bằng 0 (nồi hơi - điện trở). Khi đó công suất trung bình
$$\bar{P} = \frac{u_k^2}{R} = \frac{U_{2m}^2}{2R},$$
ở đâu $U_{1m} = 220 \sqrt{2} \text{ В}$. Nhưng
$$u_k^2 = U_{2m}^2 \cos^2 \omega t + U_n^2 + 2U_n \cdot U_{2m} \cos \omega t = \frac{U_{2m}^2}{2} + U_n^2.$$
Từ đây
$$U_n = \sqrt{\frac{U_{1m}^2}{2} - \frac{U_{2m}^2}{2}} \approx 110 \text{ В}.$$
Bài tập
1. Sơ đồ được mô tả ở hình 8 được gọi là “Cầu thắng”. Tại phần nào độ lệch pha giữa điện áp đầu ra và đầu vào bằng 0? Điện áp đầu ra của bộ phận này nhỏ hơn điện áp đầu vào bao nhiêu lần?
2. Chứng minh rằng trong mạch điện ở hình 9, ở tần số $\omega = 1/\sqrt{LC}$, dòng điện qua điện trở không phụ thuộc vào điện trở của nó. Tìm dòng điện này.
