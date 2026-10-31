---
id: 1976-7-dozorov-zachem-transformatoru-serdechnik-adbfd834
issue: kvant_1976_7
year: 1976
number: "7"
title: Tại sao máy biến áp cần có lõi?
authors:
  - Дозоров А. А.
rubric: osnovnye-stati
page_first: 16
page_last: 19
page_labels: 14-17
tag: 9FIE
lang: vi
source: kvant_digital
extraction: vision
content_sha256: e0b2a9a972938841c8b94bea23637c3e4ba08d617d75e1525142440de49a5267
prompt_sha256: draft-1
translated_from: content/ru/1976/07/articles/05_dozorov-zachem-transformatoru-serdechnik-adbfd834.md
source_content_sha256: b17570371dc02d0303f682125af7fac7f23c41d00d30cd7a1bff5fc634dae84d
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 14⟧

Chúng ta hãy nhớ cách chế tạo một máy biến áp và tại sao nó hoạt động.

Máy biến áp đơn giản nhất (xem hình) bao gồm hai cuộn dây (cuộn dây) quấn trên một lõi thép thông thường. Một cuộn dây (sơ cấp) được nối với nguồn điện xoay chiều. Thiết bị tiêu thụ điện (gọi là tải) được nối với cuộn dây thứ hai (thứ cấp). Cả cuộn dây thứ nhất và thứ hai đều bị xuyên qua bởi cùng một từ thông xoay chiều được tạo ra bởi dòng điện xoay chiều của nguồn. Ở cuộn dây thứ nhất có số vòng $n_1$ E.D. phát sinh. Với. cảm ứng $e_1 = -n_1 \frac{\Delta \Phi}{\Delta t}$ (ΔΦ là sự thay đổi từ thông qua một lượt trong thời gian $\Delta t$), và trong thứ cấp - E.D. Với. индукции $e_2 = -n_2 \frac{\Delta \Phi}{\Delta t}$.

Giả sử cuộn thứ cấp hở, tức là hãy xem xét chế độ chạy nguội của máy biến áp. Chúng ta cũng sẽ giả định rằng điện trở tác dụng của cuộn sơ cấp rất nhỏ so với điện trở cảm ứng của nó. Theo định luật Ohm, tổng của tất cả E.D. Với. trong một mạch kín bằng tổng điện áp rơi trong mạch này (thường định luật Ohm, viết dưới dạng này, được gọi là định luật Kirchhoff):

$$u_1 + e_1 = i_1 R_1.$$

Ở đây $u_1$ là điện áp của nguồn dòng, $i_1$ là dòng điện và $R_1$ là điện trở hoạt động của cuộn sơ cấp. Bởi vì $R_1$ rất ít ($R_1 \rightarrow 0$), $u_1 + e_1 = 0$, hoặc

$$u_1 = -e_1.$$

Khi cuộn thứ cấp mở ($i_2 = 0$), điện áp ở hai đầu của nó

$$u_2 = -e_2.$$

Do đó, tỷ số điện áp $\frac{u_2}{u_1} = \frac{e_2}{e_1}$ hoặc cho hoạt động giật

$$\frac{U_2}{U_1} = \frac{\mathcal{E}_2}{\mathcal{E}_1} = \frac{n_2}{n_1}.$$

Sự tương ứng này làm nảy sinh câu hỏi được đặt ra trong tiêu đề. Thật vậy, tỷ số điện áp chỉ phụ thuộc vào tỷ lệ số vòng dây trong cuộn dây và không có các tham số lõi theo (1). Các tham số này có thể tùy ý không? Có thể vận hành máy biến áp mà không cần lõi không? Nếu có, trong những điều kiện nào?

Khi suy ra sự tương ứng (1), giả sử từ thông qua cuộn sơ cấp và cuộn thứ cấp bằng nhau. Tuy nhiên, điều kiện này có thể không được đáp ứng: một phần từ thông do cuộn sơ cấp tạo ra có thể tiêu tán và không xuyên qua được cuộn thứ cấp của máy biến áp, tất yếu sẽ dẫn đến chi phí kỹ thuật.

⟦folio 15⟧

tính của máy biến áp. Vì vậy, có lẽ mục đích chính của lõi là giảm sự tiêu tán từ thông? Nhưng việc tái định cư có thể tránh được bằng những cách khác! Ví dụ, bằng cách cuộn cuộn thứ cấp trực tiếp lên cuộn sơ cấp hoặc bằng cách cuộn các cuộn dây này vào một hình xuyến (vô lăng). Và một lần nữa câu hỏi được đặt ra, câu hỏi trong tiêu đề: tại sao máy biến áp lại cần một lõi nặng, trong đó, cùng với những thứ khác, phát sinh tổn thất năng lượng - dòng điện Foucault, độ trễ? Nói chung cốt lõi còn rất nhiều thiếu sót. Vậy tại sao nó lại cần thiết?

Vì vậy, câu hỏi được hình thành và bị lên án; đã đến lúc chuyển sang đáp số trên đó.

Theo quy luật, các thiết bị thực có các đặc tính kém hơn so với các mô hình lý tưởng được mô tả bằng lý thuyết, đặc biệt là mô hình đơn giản nhất. Điều này áp dụng cho máy biến áp. Loại máy biến áp nào có thể được gọi là lý tưởng? Chúng ta hãy cố gắng hiểu điều này một cách định tính. Trong máy biến áp, năng lượng điện từ được truyền từ cuộn sơ cấp sang cuộn thứ cấp. Trong trường hợp tốt nhất, năng lượng giải phóng trong mạch cuộn thứ cấp sẽ bằng năng lượng mà cuộn sơ cấp tiêu thụ từ nguồn. Chúng ta có thể nói không phải về năng lượng mà là về sức mạnh. Điều mong muốn là công suất phải tối đa, tức là hệ số công suất với f≈1. Về mặt toán học, những yêu cầu này được ghi lại dưới dạng hệ số.

Xét một cuộn dây dài có số vòng dây lớn (soon). Cảm ứng của từ trường được tạo ra bởi một dây dẫn mang dòng điện luôn tỷ lệ thuận với cường độ dòng điện và còn phụ thuộc vào cấu hình của dây dẫn, vào vị trí của điểm mà từ trường quan tâm đến chúng ta và vào tính chất từ ​​của môi trường. Bên trong nút điện từ, từ trường đều. Có thể chứng minh rằng cảm ứng của trường này là $B = \mu_0 \mu I n/l$. Ở đây $\mu_0$ là hằng số từ, $\mu$ là độ thấm từ tương đối của môi trường, $n$ là số vòng của nút điện từ, $l$ là chiều dài của nó. Thế thì từ đẳng thức (3)
$$\Phi = B S n = \mu_0 \mu I n^2 S/l.$$

So sánh biểu thức này với (4), chúng ta thấy

⟦folio 16⟧

độ tự cảm của điện từ:
$$L = \mu_0 \mu n^2 S/l. \quad (5)$$

Tương tự, người ta đưa ra khái niệm hệ số cảm kháng lẫn nhau (độ tự cảm lẫn nhau) $M$ của hai mạch điện. Trong trường hợp của chúng tôi, khái niệm về độ tự cảm lẫn nhau của cuộn dây sơ cấp và thứ cấp của máy biến áp. Khi cuộn thứ cấp bị nối tắt với tải, sẽ xuất hiện dòng điện trong mạch thứ cấp. Hãy biểu thị giá trị hiệu dụng của nó $I_2$. Đồng thời, dòng điện trong cuộn sơ cấp thay đổi. Bây giờ giá trị hiệu dụng $I_1$ của nó không còn giống như ở chế độ chạy nguội của máy biến áp. Từ thông $\Phi_2$ qua cuộn thứ cấp được tạo ra bởi dòng điện $I_1$ của cuộn sơ cấp tỉ lệ với dòng điện này:
$$\Phi_2 \sim I_1, \text{ или } \Phi_2 = MI_1.$$
Tương tự, từ thông $\Phi_1$ qua cuộn sơ cấp gây ra bởi dòng điện $I_2$ của cuộn thứ cấp,
$$\Phi_1 \sim I_2, \text{ или } \Phi_1 = MI_2.$$
Hệ số tỷ lệ $M$ là hệ số độ tự cảm lẫn nhau, hay độ tự cảm lẫn nhau của cuộn dây máy biến áp. Tương tự như việc suy ra giá trị độ tự cảm Soleno, người ta có thể thu được biểu thức cho $M$:
$$M = \mu_0 \mu n_1 n_2 S/l. \quad (6)$$
Từ biểu thức (5) và (6)
$$M = \frac{n_2}{n_1} L_1 = \frac{n_1}{n_2} L_2. \quad (7)$$

Lưu ý rằng, trên thực tế, tất nhiên chỉ có một từ thông duy nhất trong lõi máy biến áp. Trong thực tế, nó hoàn toàn được xác định bởi điện áp của nguồn dòng nối với mạch cuộn sơ cấp. Tuy nhiên, để rõ ràng, chúng ta có thể xem xét riêng các từ thông được tạo ra bởi dòng điện $I_1$ và $I_2$.

Bây giờ chúng ta quay lại máy biến áp một lần nữa và tiếp tục thảo luận về hoạt động của nó ở chế độ vận hành. Đầu tiên chúng ta hãy viết định luật Ohm (quy tắc Kirchhoff) cho mạch kín của cuộn sơ cấp, sau đó cho cuộn thứ cấp. Trong mỗi

⟦folio 17⟧

Ở đây $A, B, \alpha$ và $\beta$ là hằng số.
Tốc độ thay đổi của dòng điện đầu tiên

$$\frac{\Delta i_1}{\Delta t} = \frac{i_1(t + \Delta t) - i_1(t)}{\Delta t} =$$

$$= A \frac{\sin [\omega(t + \Delta t) - \alpha] - \sin (\omega t - \alpha)}{\Delta t} =$$

$$= 2 \frac{A}{\Delta t} \sin \frac{\omega \Delta t}{2} \cos \left(\omega t - \alpha + \frac{\Delta t}{2}\right).$$

Hướng $\Delta t$ về 0 $\left(\sin \frac{\omega \Delta t}{2} \approx \frac{\omega \Delta t}{2}\right)$,

$$\cos \left(\omega t - \alpha + \frac{\Delta t}{2}\right) \approx \cos (\omega t - \alpha)),$$

chúng tôi nhận được

$$\lim_{\Delta t \to 0} \frac{\Delta i_1}{\Delta t} = A \omega \cos (\omega t - \alpha).$$

Tương tự như vậy

$$\lim_{\Delta t \to 0} \frac{\Delta i_2}{\Delta t} = B \omega \cos (\omega t - \beta).$$

Sau đó các phương trình (8) và (9) chuyển thành phương trình lượng giác:

$$U_0 \sin \omega t - p MA \omega \cos (\omega t - \alpha) - MB \omega \cos (\omega t - \beta) = 0,$$

(8a)

$$- \frac{1}{p} MB \omega \cos (\omega t - \beta) -$$

$$- MA \omega \cos (\omega t - \alpha) = RB \sin (\omega t - \beta).$$

(9a)

Mỗi phương trình sau các phần tử biến đổi (mở ngoặc) có thể được viết dưới dạng

$$a \sin \omega t + b \cos \omega t = 0,$$

(10)

trong đó các hệ số $a$ và $b$ không phụ thuộc vào thời gian.

Phương trình (10) chỉ hợp lệ bất kỳ lúc nào $t$ nếu $a=0$ và $b=0$ đồng thời. Do đó, hai phương trình được chuyển đổi thành bốn:

$$\begin{cases}
U_0 - p MA \omega \sin \alpha - MB \omega \sin \beta = 0, \\
p A \cos \alpha + B \cos \beta = 0, \\
- \frac{1}{p} MB \omega \sin \beta - MA \omega \sin \alpha = RB \cos \beta, \\
\frac{1}{p} MB \omega \cos \beta + MA \omega \cos \alpha = RB \sin \beta.
\end{cases}$$

Giải được hệ này, chúng ta sẽ tìm được biên độ của dòng điện trong mạch sơ cấp và mạch thứ cấp cũng như dwgi của dòng điện cùng pha so với điện áp bên ngoài.

Cuối cùng chúng tôi nhận được

$$I_{0_1} = A = \frac{U_0}{p^2 R} \sqrt{1 + \left(\frac{p R}{M \omega}\right)^2},$$

$$I_{0_2} = B = \frac{U_0}{p R},$$

$\alpha = \arctg \frac{p R}{M \omega}, \beta = \pi$.

lời giải mà chúng tôi tìm thấy có đáp ứng yêu cầu của một máy biến áp lý tưởng (tương ứng (2)) không? Hãy kiểm tra. Hãy tìm tỉ số giữa các giá trị biên độ của dòng điện:

$$\frac{I_{0_1}}{I_{0_2}} = \frac{A}{B} = \frac{1}{p} \sqrt{1 + \left(\frac{p R}{M \omega}\right)^2}.$$

Biểu thức cuối cùng trùng với sự tương ứng (2), nếu dưới gốc số hạng thứ hai có xu hướng bằng 0:

$$\frac{R}{M \omega} = \frac{R l}{\mu_0 \mu S n_1 n_2 \omega} \rightarrow 0$$

(tỷ lệ số vòng $p$ phải không đổi). Vì vậy, một máy biến áp có thể được coi là lý tưởng nếu

a) độ thấm từ của môi trường $\mu$ đủ lớn,

b) tần số của điện áp xoay chiều $\omega$ đủ cao,

b) số vòng dây ở cuộn sơ cấp và thứ cấp lớn,

d) điện trở tác dụng của cuộn thứ cấp nhỏ,

d) chiều dài của cuộn dây là nhỏ nhất, tức là các cuộn dây được quấn chặt.

Để tạo ra một máy biến áp gần đạt mức lý tưởng, bạn cần chọn cách biến đổi thuận tiện nhất về mặt thực tế. Trước hết, đây là sự biến đổi tính thấm từ cao của môi trường. Đối với chân không $\mu=1$ và đối với nam châm sắt $\mu \approx 10000$. Việc tăng số vòng dây thực tế là không có lợi (kích thước và giá thành của máy biến áp tăng mạnh) và việc tăng tần số dòng điện lên vài nghìn lần có liên quan đến các vấn đề kỹ thuật quan trọng. Các máy biến áp tần số cao hiện tại thực sự được sử dụng mà không có lõi và các đặc tính của chúng gần giống với các đặc tính của máy biến áp lý tưởng.
