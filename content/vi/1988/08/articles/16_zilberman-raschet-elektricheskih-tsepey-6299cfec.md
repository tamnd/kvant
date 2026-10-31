---
id: 1988-8-zilberman-raschet-elektricheskih-tsepey-6299cfec
issue: kvant_1988_8
year: 1988
number: "8"
title: Tính toán mạch điện
authors:
  - Зильберман А. Р.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 60
page_last: 62
page_labels: 58-60
tag: 7XZX
lang: vi
source: kvant_digital
extraction: vision
content_sha256: bd8a3738c597892c274328b2ba94aa39b4ffe79a6bf2f1eb230adfbe9e6dc376
prompt_sha256: draft-1
translated_from: content/ru/1988/08/articles/16_zilberman-raschet-elektricheskih-tsepey-6299cfec.md
source_content_sha256: 2fe1f02fb1079800ad1d2b1f17e48b204ddb2cbf9041a510badfc81b2a87475d
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 58⟧

Tính toán mạch điện

A. R. ZILBERMAN

Có nhiều cách tính mạch điện gồm pin và điện trở. Hầu như bất kỳ trong số chúng (với ký hiệu biến đơn giản) cũng phù hợp với mạch pin và tụ điện. (Và nếu bạn tự tin với những con số đầy đủ thì bạn cũng có thể tính bất kỳ mạch nào cho dòng điện xoay chiều.) Bài viết này sẽ xem xét hai cách đơn giản để tính mạch điện một chiều bằng điện trở và tụ điện.

Phương pháp đầu tiên phù hợp với các mạch tương đối đơn giản. Chúng ta hãy cho một mạch bao gồm một pin và một số điện trở. Để tính toán trong các nhánh mạch, trước tiên chúng ta đơn giản hóa mạch một cách có hệ thống, sau đó nối các điện trở song song hoặc nối tiếp với các giá trị tương đương của chúng. Sau khi đơn giản hóa mạch đến mức có thể dễ dàng tìm được dòng điện trong đó, chúng ta thực hiện quá trình ngược lại, tìm dòng điện của các phần tử ban đầu. Phương pháp này được nhiều bạn biết đến từ lớp tóc bạc.

Hãy xem xét một vài ví dụ.

Bài toán 1. Trong mạch điện ở hình 1, hãy tìm dòng điện chạy qua dây nối AB.

Hãy đơn giản hóa mạch điện bằng cách thay thế các điện trở kết nối song song 1 và 3, cũng như 2 và 4 bằng các điện trở tương đương của chúng. Kết quả là một mạch đơn giản có điện trở chung

$$R = \frac{R_1 R_3}{R_1 + R_3} + \frac{R_2 R_4}{R_2 + R_4}$$

và tổng dòng điện

$$I = \frac{U}{R} = \frac{U}{R_1 R_3 + R_2 R_4}.$$

Điện áp trên điện trở 1 và 3 bằng nhau, nghĩa là $I_1:I_3 = R_3:R_1$. Nhưng $I_1 + I_3 = I$. Sau đó

⟦folio 59⟧

$$I_1 = I \frac{R_3}{R_1 + R_3}, \quad I_3 = I \frac{R_1}{R_1 + R_3}.$$
Tương tự như vậy
$$I_2 = I \frac{R_4}{R_2 + R_4}, \quad I_4 = I \frac{R_2}{R_2 + R_4}.$$
Bây giờ chúng ta hãy tìm dòng điện qua jumper $AB$:
$$I_{AB} = I_1 - I_2 = \frac{U(R_2R_3 - R_1R_4)}{R_1R_3(R_2 + R_4) + R_2R_4(R_1 + R_3)}.$$
Từ biểu thức thu được, rõ ràng là với điều kiện $R_1:R_2=R_3:R_4$ thì dòng điện qua jumper bằng 0. Điều này thường được sử dụng để đo chính xác điện trở chưa biết.
Phương pháp được xem xét tuy đơn giản nhưng lại rất cồng kềnh. Ngoài ra, nó không phổ biến - không phải mọi sơ đồ đều có thể được đơn giản hóa theo cách này. Ví dụ: nếu bạn thay thế nút nhảy trên hình 1 bằng một điện trở, thì mạch thu được không chứa các điện trở kết nối song song hay nối tiếp.
Phương pháp tính toán thứ hai, thuận tiện hơn, dựa trên sự lựa chọn hợp lý các ẩn số cho các phương trình được biên soạn sau đó.
Hãy xem xét một phần không phân nhánh của mạch chứa điện trở và nguồn dòng điện (hình 2). Theo định luật bảo toàn năng lượng thì dòng điện trong đoạn này bằng
$$I = \frac{\varphi_A - \varphi_B - \mathcal{E}}{R + r},$$
từ đó rõ ràng là để tìm dòng điện trong mỗi nhánh thì chỉ cần biết điện thế ở hai đầu của nó (chính xác hơn là hiệu điện thế). Các điểm kết nối của các phần không phân nhánh của chuỗi được gọi là các nút, do đó tên của phương pháp là phương pháp điện thế nút.
Vì vậy, vì chưa biết đại lượng nên chúng tôi chọn điện thế của các nút mạch. Thật thuận tiện khi đặt tiềm năng của một trong số chúng - bất kỳ - bằng nhau

![Puc. 1.](Puc. 1.)

![Puc. 2.](Puc. 2.)

![Puc. 3.](Puc. 3.)

![Puc. 4.](Puc. 4.)

Bằng 0 (khi đó điện thế của các nút còn lại là điện áp thay đổi so với nút chúng ta đã chọn). Các phương trình xác định điện thế nút được viết cho các dòng điện có trong dòng điện và chạy từ chúng: tổng dòng điện chạy vào một nút bằng tổng dòng điện chạy ra. Nếu có $N$ nút trong mạch, thì sẽ có ít điện thế chưa biết hơn (hãy nhớ rằng chúng ta tự đặt điện thế của một trong các nút). Điều này có nghĩa là chúng ta cần viết phương trình dòng điện của tất cả các nút ngoại trừ một nút. (Tuy nhiên, nếu chúng ta viết phương trình cho tất cả các nút, chúng ta sẽ nhanh chóng thấy rằng một trong số chúng - bất kỳ nút nào! - là thừa; nó có thể thu được bằng cách kết hợp các phương trình còn lại.)

Để làm ví dụ, chúng ta hãy xem bài toán này.
Nhiệm vụ 2. Tìm dòng điện qua điện áp $R$ nối với pin nối song song có emf $\mathcal{E}_1$ và $\mathcal{E}_2$ và các điện trở trong $r_1$ và $r_2$ (hình 3).
Hãy vẽ lại sơ đồ như trong hình 4 và đặt $\varphi_A = 0$. Bây giờ chỉ cần đặt điện thế của điểm $B$ để biểu thị tất cả các dòng điện trong mạch là đủ. Đối với nút $B$:
$$\frac{\mathcal{E}_1 - \varphi_B}{r_1} + \frac{\mathcal{E}_2 - \varphi_B}{r_2} = \frac{\varphi_B}{R},$$
Thế năng của điểm $B$ đến từ đâu?
$$\varphi_B = \frac{\mathcal{E}_1/r_1 + \mathcal{E}_2/r_2}{1/r_1 + 1/r_2 + 1/R},$$
và dòng điện áp
$$I = \frac{\varphi_B}{R} = \frac{\mathcal{E}_1 r_2 + \mathcal{E}_2 r_1}{R(r_1 + r_2) + r_1 r_2}.$$

Đôi khi câu hỏi trong bài toán được đặt ra khác nhau: có thể thay pin kết nối song song ($\mathcal{E}_1$, $r_1$ và $\mathcal{E}_2$, $r_2$) bằng pin tương đương không và chúng nên là loại pin nào (nếu

⟦folio 60⟧

nó có thể được thay thế không!) EMF và điện trở trong của nó? Đối với đáp số những câu hỏi này, bạn cần thử biểu thức thu được cho cường độ dòng điện, đưa nó về dạng

$$I = \frac{\mathcal{E}_{\text{экв}}}{R + r_{\text{экв}}}.$$

Nếu thành công thì sẽ là đáp số cho cả hai câu hỏi. Trong trường hợp của chúng tôi, mọi thứ đều đơn giản:

$$I = \frac{(\mathcal{E}_1 r_2 + \mathcal{E}_2 r_1) / (r_1 + r_2)}{R + r_1 r_2 / (r_1 + r_2)},$$

$$\mathcal{E}_{\text{экв}} = \frac{\mathcal{E}_1 r_2 + \mathcal{E}_2 r_1}{r_1 + r_2}, \quad r_{\text{экв}} = \frac{r_1 r_2}{r_1 + r_2}.$$

(Lưu ý rằng bất kỳ hệ thống pin và điện trở nào được kết nối với mạch ngoài bằng hai dây đều có thể được thay thế bằng pin tương đương. Việc chứng minh điểm này nằm ngoài phạm vi chương trình giảng dạy ở trường.)

Bây giờ chúng ta hãy giải quyết vấn đề phức tạp hơn bài toán.

Bài toán 3. Trong mạch điện ở hình 5, hãy tìm điện trở giữa các điểm A và B.

Cách dễ nghĩ nhất là: nối một cục pin có điện áp U cho trước với các điểm này, tìm dòng điện qua pin và tính tổng điện trở bằng công thức $R = U/I$. Hãy vẽ sơ đồ kết quả (hình 6) và đặt $\varphi_A = 0$. Khi đó đã biết thế năng của điểm B: $\varphi_B = U$. Chúng ta hãy biểu thị thế năng của điểm C bằng $\varphi_1$, của điểm D bằng $\varphi_2$. Hãy viết hai phương trình cho nút C:

$$-(U - \varphi) C_1 + \varphi C_2 + \varphi C_3 = 0,$$

từ đâu $\varphi = \frac{C_1 U}{C_1 + C_2 + C_3}.$
