---
id: 1986-11-shapiro-nomogrammyi-v-geometricheskoy-optike-24cee53a
issue: kvant_1986_11
year: 1986
number: "11"
title: Danh pháp trong quang học hình học
authors:
  - Шапиро А. И.
rubric: shkola-v-kvante
page_first: 22
page_last: 23
page_labels: 20-21
tag: DFT7
lang: vi
source: kvant_digital
extraction: vision
content_sha256: b2848d8ecb2f04dd06ae3233d0204eaad597ae7df99a5dbb953aba4e35e9361d
prompt_sha256: draft-1
translated_from: content/ru/1986/11/articles/08_shapiro-nomogrammyi-v-geometricheskoy-optike-24cee53a.md
source_content_sha256: 8372cbdff32db06ee1a4bf39addb5f1febc5dcd3d67b1b0b2f0cac10921d7280
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 20⟧

của một chiếc tủ lạnh lý tưởng nó bằng (hình 2)

$$\eta_{\text{x max}} = \frac{Q_2}{A} = \frac{Q_2}{Q_1 - Q_2} = \frac{T_2}{T_1 - T_2} = \frac{1 - \eta_{\text{max}}}{\eta_{\text{max}}}$$

Lưu ý rằng, như sau từ công thức này, hệ số làm mát có thể lớn hơn đơn vị.

Và bây giờ không khó để chứng minh cách bạn có thể sử dụng tủ lạnh để sưởi ấm căn phòng trong mùa lạnh - để làm được điều này, ngăn tủ lạnh cần được đưa ra bên ngoài (và tất cả các bộ phận khác của “bộ phận” còn lại trong phòng!)! Sau đó, thực hiện công $A$ (hiển thị năng lượng từ mạng điện) và lượng nhiệt $Q_2$ từ đường phố, chúng ta truyền lượng nhiệt $Q_1 = A + Q_2 > A$ vào phòng. Rõ ràng là không có gì mâu thuẫn với định luật bảo toàn năng lượng - năng lượng bổ sung dưới dạng nhiệt được lấy từ không khí tải lạnh.

Máy làm lạnh hoạt động theo cách này được gọi là “bơm nhiệt”, vì nhiệt được “bơm” từ ngoài vào trong phòng. Do hoạt động của máy bơm nhiệt, căn phòng trở nên ấm hơn và đường phố càng trở nên lạnh hơn (tất nhiên, hiệu ứng sau là hoàn toàn hoàn hảo). Hiệu suất của bơm nhiệt $\eta_{\text{h}}$ được xác định bằng tỷ lệ giữa lượng nhiệt mà căn phòng nhận được với công bên ngoài cần thiết cho việc này. Lý tưởng nhất là nó bằng

$$\eta_{\text{h max}} = \frac{Q_1}{A} = \frac{Q_1}{Q_1 - Q_2} = \frac{T_1}{T_1 - T_2} = \frac{1}{\eta_{\text{max}}}$$

và luôn lớn hơn một.

Ví dụ: hãy xem xét trường hợp khi nhiệt độ không khí tải là $-20^{\circ}\text{C}$ ($T_2 = 253\ \text{K}$) và nhiệt độ bên trong phải được duy trì ở $+20^{\circ}\text{C}$ ($T_1 = 293\ \text{K}$). Sau đó

$$\eta_{\text{h}} = \frac{293}{40} \approx 7,3$$

nghĩa là, nó sử dụng năng lượng điện để vận hành máy bơm nhiệt, chúng ta có thể thu được nhiệt lượng gấp bảy lần so với một thiết bị tùy chỉnh. Tất nhiên, hiệu suất thực tế luôn thấp hơn và động cơ bơm nhiệt cũng không chuyển toàn bộ năng lượng tiêu thụ thành công. Tuy nhiên, việc sử dụng máy bơm nhiệt vẫn tiết kiệm chi phí hơn gấp nhiều lần so với việc sử dụng quang điện.

Từ khóa học vật lý ở trường, bạn đã học về cách giải các bài toán quang học hình học bài toán khác nhau bằng đồ họa. Ví dụ, để tìm vị trí ảnh của một nguồn sáng chính xác trên một khuôn mặt mỏng, chỉ cần xây dựng đường đi của hai tia tùy ý rời khỏi nguồn và truyền qua thấu kính là đủ.

Trong lưu ý này, chúng ta sẽ nói về một phương pháp đồ họa khác, chưa qua đào tạo lời giải tương tự như bài toán. Đồng thời, trong các hình vẽ được cung cấp cho bạn, bạn sẽ không nhìn thấy bất kỳ tia sáng nào, trục quang học của thấu kính hoặc thậm chí chính thấu kính. Chúng ta đang nói về loại đồ họa nào?

Trong toán học, có một phần đặc biệt gọi là danh pháp học (từ tiếng Hy Lạp pomos - luật và grapho - thực phẩm), nghiên cứu các phương pháp xây dựng các hình vẽ đặc biệt - danh pháp học. Với sự giúp đỡ của họ, chẳng hạn, bạn có thể không tính toán tùy tiện, thu được kết quả gần đúng

⟦folio 21⟧

lời giải phương trình hoặc giá trị gần đúng của các hàm liên xã hội được tìm thấy. Chúng tôi cũng sẽ tận dụng cơ hội này.

Đặt vật sáng cách một khoảng $d$ so với đường thẳng có tiêu cự $F$ và ảnh của nó ở khoảng cách $f$. Có thể chứng minh (điều này được thực hiện ở § 60 của Vật lý 10) rằng ba đại lượng này có liên hệ với nhau bằng một mối quan hệ đơn giản - công thức đường mảnh:

$$\frac{1}{d} + \frac{1}{f} = \frac{1}{F}.$$

Lưu ý rằng mỗi số hạng trong công thức có thể dương hoặc âm. Nếu vật hoặc ảnh của nó hoặc tiêu điểm của đường thẳng là thật thì các đại lượng $d$, hoặc $f$ hoặc $F$ được lấy bằng dấu cộng, nhưng trong trường hợp vật, ảnh hoặc tiêu điểm của đường thẳng là tối thiểu thì các đại lượng tương ứng được coi là âm.

Hãy xây dựng một biểu đồ cho công thức đường thẳng và chỉ ra cách sử dụng nó để giải bài toán cụ thể.

Chúng ta hãy mô tả một hệ tọa độ hình chữ nhật $XOY$ (hình 1) trên mặt phẳng. Dọc theo trục $X$, chúng ta vẽ đoạn $OA$ có chiều dài $d$ và dọc theo trục $Y$, chúng ta vẽ đoạn $OB$ có chiều dài $f$. Hiện tại, để xác định $d$ và $f$, chúng ta sẽ đếm các phân đoạn dương $KM$ và $KN$ đến $F$. Từ sự giống nhau của các tam giác $AOB$ và $AMK$ suy ra $$\frac{OB}{OA} = \frac{KM}{MA},$$ hoặc $$\frac{f}{d} = \frac{F}{d-F},$$ từ đâu ra

dễ dàng thu được phương trình quen thuộc (*).

Như vậy, ta thu được các độ dài $d$, $f$ và $F$ được xây dựng dựa trên hình vẽ các đoạn thẳng nối nhau theo phương trình đường mảnh (vì thế khi dựng ta sử dụng ký hiệu như vậy cho độ dài của các đoạn thẳng). Và điều này có nghĩa là chúng ta có thể xây dựng một biểu đồ cho công thức đường thẳng. Thật vậy, nếu khoảng cách $d$ từ vật đến đường thẳng được vẽ dọc theo trục hoành của hệ tọa độ hình chữ nhật và khoảng cách $f$ từ đường thẳng đến ảnh được vẽ dọc theo trục tung, thì tất cả các đường thẳng nối hai đầu của các đoạn tương ứng sẽ cắt nhau tại một điểm (hình 2). Các hình chiếu của điểm này lên các trục tọa độ đều giống nhau và bằng tiêu cự $F$ của đường thẳng này.

Như bạn đã biết, để xác định một đường thẳng trên một mặt phẳng, chỉ cần biết tất cả các điểm thuộc về nó là đủ. Do đó, bằng cách sử dụng biểu đồ được xây dựng, dựa trên hai trong ba giá trị đã biết $d$, $f$ và $F$, luôn có thể xác định bằng đồ họa phần ba còn thiếu. Vì vậy, ví dụ, trong cấu trúc được hiển thị ở hình 1, chúng tôi thực tế đã xác định tiêu cự của đường thẳng ($F$) từ khoảng cách đã biết từ đường thẳng đến vật thể ($d$) và từ đường thẳng đến hình ảnh ($f$).

Thật dễ dàng để xác minh rằng phương pháp được đề xuất không chỉ phù hợp với các đường nội tại mà còn phù hợp với các đường phân tán, cũng như cho bất kỳ vị trí nào của vật thể và hình ảnh so với đường thẳng. Ví dụ: nếu đối tượng hoặc hình ảnh là tối thiểu thì các giá trị tương ứng $d$ hoặc $f$ là âm và do đó,
