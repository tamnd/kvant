---
id: 1984-10-belkin-postoyannyiy-i-peremennyiy-elektricheskiy-tok-f2e77e26
issue: kvant_1984_10
year: 1984
number: "10"
title: Dòng điện một chiều và xoay chiều
authors:
  - Белкин И. К.
rubric: shkola-v-kvante
page_first: 30
page_last: 31
page_labels: 28-29
tag: 812G
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 01e786c20371a9e90b1491998731857bf99f0b02d5ee0caccb7564e4f96f091f
prompt_sha256: draft-1
translated_from: content/ru/1984/10/articles/11_belkin-postoyannyiy-i-peremennyiy-elektricheskiy-tok-f2e77e26.md
source_content_sha256: 3346da8bc46b67f56ae83511e739e5ee44a6df6c6db2b700d47de5f3ba531692
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 28⟧

Dòng điện một chiều và xoay chiều

Trong một thời gian dài, nguồn dòng điện duy nhất là nguyên tố điện, xuất hiện vào đầu thế kỷ 19. Trong mạch nối với nguồn như vậy có một dòng điện không đổi chạy qua.

Thành công trong nghiên cứu điện từ đã dẫn đến việc phát minh ra máy phát điện xoay chiều, và kể từ đó dòng điện xoay chiều đã trở thành nền tảng của kỹ thuật điện hiện đại.

Tại sao? Tại sao dòng điện xoay chiều lại tốt hơn dòng điện một chiều?

Dòng điện xoay chiều cũng như dòng điện một chiều là sự chuyển động có trật tự của các hạt tích điện, đặc biệt là trong kim loại - electron. Nhưng trong mạch điện xoay chiều, các electron thay đổi hướng chuyển động có trật tự của chúng nhiều lần. Khối lượng điện thấp cho phép chúng “có thời gian” để thay đổi hướng chuyển động không chỉ 100 lần mỗi giây, như xảy ra trong mạng công nghiệp, mà còn mười triệu lần mỗi giây, chẳng hạn như trong ăng-ten của đài phát thanh.

Nếu dòng điện xoay chiều chạy trong mạch điện, mục tiêu phải được kết nối với nguồn điện xoay chiều. Ở đây nó hoạt động như một lực dẫn động tuần hoàn, và dòng điện trong mạch thực hiện các dao động cưỡng bức, tất nhiên, với tần số của lực dẫn động. Nếu EMF trong nguồn thay đổi theo thời gian theo định luật $e = \mathcal{E}_m \cos \omega t$ và nguồn được kết nối với mục tiêu có điện trở hoạt động $R$, thì dòng điện cũng thay đổi theo định luật cosin (“Vật lý 10”, § 17):

$$i = \frac{e}{R} = \frac{\mathcal{E}_m}{R} \cos \omega t = I_m \cos \omega t.$$

Ở đây $\mathcal{E}_m$ và $I_m$ là biên độ (giá trị tối đa) của EMF và cường độ dòng điện. Nhưng các tính chất của hàm cosine sao cho trung bình trong suốt chu kỳ dao động cường độ dòng điện bằng không. Tuy nhiên, điều này không có nghĩa là dòng điện như vậy là vô ích và không biểu hiện ở bất cứ điều gì. Bởi vì mặc dù trung bình dòng điện bằng 0 nhưng bình phương của dòng điện không bằng 0. Và cường độ dòng điện được xác định chính xác bằng bình phương của dòng điện. Tại bất kỳ thời điểm nào, cường độ dòng điện xoay chiều trong mạch có điện trở tác dụng được biểu thị bằng đẳng thức

$$p = i^2 R = I_m^2 R \cos^2 \omega t.$$

Giá trị trung bình của cosin bình phương trong một khoảng thời gian không phải bằng 0 mà là $1/2$, do đó công suất trung bình

$$\bar{p} = \bar{i}^2 R = \frac{1}{2} I_m^2 R = \left( \frac{I_m}{\sqrt{2}} \right)^2 R.$$

Giá trị $I = I_m / \sqrt{2}$ được gọi là giá trị hiệu dụng của dòng điện. Trong trường hợp của chúng tôi, công suất cũng có thể được biểu thị dưới dạng điện áp trên điện trở:

$$p = \frac{u^2}{R}, \bar{p} = \frac{\bar{u}^2}{R} = \frac{1}{2} \frac{U_m^2}{R} = \frac{U^2}{R},$$

trong đó $U = U_m / \sqrt{2}$ là giá trị điện áp hiệu dụng.

Điều kiện này là một trong những tính chất tiêu cực của dòng điện xoay chiều. Rốt cuộc, các dây dẫn dòng điện chạy qua phải được thiết kế để có giá trị dòng điện tối đa và các dây thực tế sử dụng hơn 2/3 giá trị này một chút. Có những hậu quả tiêu cực khác. Ví dụ, hiện tượng cảm ứng điện từ dẫn đến hiện tượng dòng điện xoay chiều trong dây dẫn không được phân bố đều trên toàn bộ mặt cắt mà chủ yếu ở gần bề mặt. (Hiện tượng này được gọi là hiệu ứng bề mặt, nó không được thảo luận trong Vật lý 10. Về đặc điểm, độ sâu thâm nhập của dòng điện xoay chiều phụ thuộc vào nhiều yếu tố, bao gồm cả tần số dao động. Do đó, ở tần số 50 Hz trong một dây dẫn đồng, độ sâu này là ≈ 9 mm. Với tần số ngày càng tăng, độ sâu thâm nhập của dòng điện giảm.) Do không phải tất cả các mặt cắt của dây đều được sử dụng nên điện trở của chúng cũng bị ảnh hưởng. Hơn nữa, dòng điện xoay chiều, giống như dòng điện một chiều, được bao quanh bởi một từ trường, nhưng là một trường xoay chiều. Và một trường như vậy, theo định luật cảm ứng điện từ, gây ra các trường lân cận

⟦folio 29⟧

dây điện và các vật liệu dẫn điện khác mang dòng điện, dẫn đến tiêu thụ năng lượng lãng phí.

Tất cả những nhược điểm này hoàn toàn không có ở dòng điện một chiều. Tại sao dòng điện xoay chiều gần như chiếm ưu thế hoàn toàn trong công nghệ và đời sống?

Trước hết, nguyên lý hoạt động của máy phát điện là biến EMF phát sinh trong chúng (“Vật lý 10”, § 23). Nhưng đó không phải là vấn đề. Sử dụng một thiết bị đơn giản, bạn có thể biến cùng một máy phát điện thành nguồn dòng điện một chiều. Lý do chính khiến dòng điện xoay chiều “phổ biến” là do năng lượng điện được truyền từ nơi sản xuất ra (nhà máy điện) đến nơi tiêu thụ và thường đi những khoảng cách xa. Trong trường hợp này, một phần năng lượng truyền đi chắc chắn bị thất thoát dưới dạng nhiệt, qua đó nó được truyền trong đường dây truyền tải điện (PTL). Để đảm bảo tổn thất không quá cao, cần phải sử dụng điện áp cao để truyền tải.

Sự cần thiết của điện áp cao có thể được nhìn thấy từ phép tính đơn giản sau đây. Giả sử rằng năng lượng điện $P=66$ kW được truyền từ nhà máy điện đến thành phố dưới điện áp 220 V (đây là điện áp thường được người tiêu dùng sử dụng). Gọi điện trở của đường dây là 0,4 Ohm. Khi đó cường độ dòng điện trong đường dây là $I=66000 \text{ Вт}/220 \text{ В}=300 \text{ А}$ và lượng nhiệt tỏa ra trong đường dây là $Q=I^2R=(300 \text{ А})^20,4 \text{ Ом}=36000 \text{ Вт}$. Một tỷ lệ lớn công suất truyền tải (54,5%) sẽ bị thất thoát dưới dạng nhiệt trong đường dây điện! Bây giờ hãy tưởng tượng rằng cùng một công suất được truyền dọc theo cùng một đường dây điện ở điện áp 22000 V. Bây giờ dòng điện trong mạch sẽ bằng $I=66000 \text{ Вт}/22000 \text{ В}=3 \text{ А}$ và lượng nhiệt tỏa ra sẽ là $Q=(3 \text{ А})^20,4 \text{ Ом}=3,6 \text{ Вт}$. Yêu cầu chỉ khoảng 0,005%! Đó là lý do tại sao năng lượng điện luôn được truyền dọc theo đường dây điện ở điện áp rất cao - 110.220.330.400.500 và thậm chí 750 kilovolt.

Nhưng tại các cực của máy phát điện nhà máy điện, điện áp thấp hơn đáng kể - chỉ vài nghìn volt. Điều này có nghĩa là khi bắt đầu đường dây truyền tải điện, điện áp này phải được tăng lên và trước khi phân phối năng lượng đến các hộ tiêu thụ, nó phải được hạ xuống để hộ tiêu thụ nhận được ở điện áp 220 volt. Việc tăng giảm điện áp như vậy chỉ có thể thực hiện được đối với dòng điện xoay chiều. Điều này được thực hiện bằng cách sử dụng một thiết bị hoạt động dựa trên hiện tượng cảm ứng điện từ - máy biến áp (“Vật lý 10”, § 24). Sự tồn tại của máy biến áp có lẽ là lý do duy nhất khiến việc sử dụng dòng điện xoay chiều trong công nghệ ngày càng tăng.

Tuy nhiên, những nhược điểm của dòng điện xoay chiều đã nêu ở trên khiến chúng ta phải suy nghĩ xem liệu có còn sử dụng được dòng điện một chiều, tất nhiên là cả điện áp cao, để truyền tải năng lượng điện hay không? Điều này không dễ thực hiện. Thật vậy, trước tiên, bạn cần chuyển đổi điện áp xoay chiều, sau khi tăng nó, thành điện áp một chiều (bộ chỉnh lưu được sử dụng cho việc này), sau đó ở đầu bên kia của đường dây điện, chuyển đổi điện áp một chiều xoay chiều thành điện áp xoay chiều (điều này có thể được thực hiện bằng cách sử dụng các thiết bị gọi là bộ biến tần), để có thể hạ điện áp xuống giá trị bạn cần tiêu thụ. Tuy nhiên, đường dây điện một chiều có điện áp 400 kV như vậy đã hoạt động ở Liên Xô.

Những gì đã nói trong ghi chú này không thể được hiểu là dòng điện một chiều là dòng điện “tốt” và dòng điện xoay chiều là dòng điện “xấu”. Cả hai đều là hiện tượng tự nhiên và không thể đánh giá chúng bằng từ “tốt hơn” hay “tệ hơn”. Điều trên chỉ có nghĩa là dòng điện một chiều là tối ưu để truyền năng lượng trên khoảng cách xa. Và nếu việc sử dụng dòng điện xoay chiều cho mục đích này vẫn đang được chuyển hóa thì điều này được giải thích là do việc chuyển đổi dòng điện xoay chiều thành dòng điện một chiều vẫn còn khó khăn. bài toán, tuy nhiên, đã được giải quyết thành công. Đối với một kỹ thuật viên, cả hai dòng điện đều cần thiết và hữu ích như nhau. Trong một số trường hợp, dòng điện một chiều là không thể thiếu, ví dụ như khi sử dụng điện phân. Nhưng nếu không có dòng điện xoay chiều thì sẽ không có đài phát thanh, tivi, v.v. Viết lại bài thơ thiếu nhi nổi tiếng, chúng ta có thể nói: cần có đủ loại dòng điện!
