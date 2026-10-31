---
id: 1985-1-belkin-na-chto-sposoben-mikroskop-a8155239
issue: kvant_1985_1
year: 1985
number: "1"
title: Kính hiển vi có thể làm được gì?
authors:
  - Белкин И. К.
rubric: shkola-v-kvante
page_first: 29
page_last: 30
page_labels: 27-28
tag: 8PL1
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 84b67612714d44816909d180fa9497ecf5d96dd02be161250284fe5b653e84ef
prompt_sha256: draft-1
translated_from: content/ru/1985/01/articles/09_belkin-na-chto-sposoben-mikroskop-a8155239.md
source_content_sha256: 75294d9abece799add0667849147d9cb0fcbd27aad027a9ee994aae71bb71a9f
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 27⟧

may một công việc lớn hơn hoặc nhỏ hơn $I_1R_1$. Trong phần này, nguồn dòng điện có EMF $\varepsilon_1$ làm giảm sự chênh lệch điện thế (các lực bên trong bên ngoài thực hiện công dương), và do đó chúng ta có thể viết:

$$U_{AB} = \varphi_A - \varphi_B = I_1R_1 - \varepsilon_1.$$  (1)

Ở phần $BC$ mọi thứ sẽ giống hệt nhau:

$$U_{BC} = \varphi_B - \varphi_C = I_2R_2 - \varepsilon_2.$$  (2)

Trong trường hợp phần $CD$, nguồn dòng điện có cực tính ngược so với các nguồn trước đó nên không giảm mà làm tăng độ chênh lệch điện thế (nội lực bên ngoài thực hiện công âm):

$$U_{CD} = \varphi_C - \varphi_D = I_3R_3 + \varepsilon_3.$$  (3)

Trong phần cuối cùng, mạch điện được xem xét; theo giả định của chúng tôi, dòng điện chạy từ điểm $A$ đến điểm $D$ và số đọc hoàn toàn tương ứng với phần $AB$:

$$U_{AD} = I_4R_4 - \varepsilon_4,$$

hoặc, với hướng di chuyển đã chọn,

$$U_{DA} = \varphi_D - \varphi_A = -U_{AD} = -I_4R_4 + \varepsilon_4.$$  (4)

Cộng các đẳng thức theo từng số hạng (1)-(4), chúng ta thu được:

$$I_1R_1 + I_2R_2 + I_3R_3 - I_4R_4 = \varepsilon_1 + \varepsilon_2 - \varepsilon_3 - \varepsilon_4.$$  (5)

Sự tương ứng này thể hiện quy tắc thứ hai của Kirchhoff: đối với bất kỳ mạch kín nào, tổng đại số của hướng đã cho bằng tổng đại số của suất điện động.

Các quy tắc Kirchhoff không thể hiện bất kỳ tính chất mới nào của điện trường và do đó không thể được coi là các định luật vật lý. Cái đầu tiên, như chúng ta đã nói, là hệ quả của định luật bảo toàn điện tích, cái thứ hai là hệ quả của định luật bảo toàn năng lượng. Tuy nhiên, chúng cực kỳ hữu ích khi không có dòng điện trong mạch phân nhánh.

Chúng ta hãy quay lại sơ đồ trong hình và viết ra các phương trình biểu thị quy tắc Kirchhoff cho các nút $A$, $B$, $C$, $F$ và các đường viền $ABCDA$, $AFDA$, $DFCD$:

$$I_5 - I_1 - I_4 = 0,$$
$$I_1 - I_2 = 0,$$
$$I_2 - I_3 - I_6 = 0,$$

$$I_6 + I_7 - I_5 = 0,$$
$$I_1R_1 + I_2R_2 + I_3R_3 - I_4R_4 = \varepsilon_1 + \varepsilon_2 - \varepsilon_3 - \varepsilon_4,$$
$$-I_4R_4 - I_5R_5 - I_7R_7 = -\varepsilon_4,$$
$$I_7R_7 - I_6R_6 + I_3R_3 = -\varepsilon_3.$$  (6)

Chúng ta một lần nữa chú ý đến việc lựa chọn dấu cộng hoặc dấu trừ khi lập phương trình. Trước khi giảm hướng trên điện trở, một dấu cộng “cộng” được đặt nếu hướng chúng ta đã chọn cho dòng điện trong phần này trùng với hướng bỏ qua đã chọn và dấu cộng “trừ” - nếu không thì. Emf của nguồn được coi là “cộng” nếu hướng của dòng điện mà nó có thể tạo ra trong mạch trùng với hướng đi vòng của mạch, và như vậy với dấu “trừ” trong trường hợp ngược lại.

Hướng thực sự của dòng điện chỉ có thể được xác định sau hệ phương trình lời giải: nếu giá trị thu được của bất kỳ dòng điện nào là dương, thì điều này có nghĩa là hướng của dòng điện này đã được chọn đúng; nếu dòng điện âm thì hướng thực của nó ngược với hướng đã chọn.

Không khó để chỉ ra rằng bằng cách áp dụng các quy tắc Kirchhoff, luôn có thể thu được chính xác số phương trình độc lập bằng số lượng dòng điện chưa biết, nghĩa là giải được một cách hoàn toàn và duy nhất bài toán đặt ra bài toán*).

Kính hiển vi có thể làm được gì?

Khi tạo ra các dụng cụ quang học “cánh tay” với mắt, câu hỏi tự nhiên đặt ra là về khả năng tối đa của chúng. Ví dụ, đối với kính hiển vi, đặc tính như vậy đóng vai trò là thông báo của nó. Từ quan điểm của quang học hình học, tương tự như thị kính và vật kính tương ứng, kính hiển vi có thể được chế tạo càng lớn càng tốt. Tuy nhiên, trên thực tế điều này không phải như vậy và nguyên nhân của điều này là do bản chất sóng của ánh sáng. Ý tưởng coi các tia sáng là tuyến tính hình học.

*) Một bằng chứng toán học chi tiết về thực tế này được đưa ra trong bài báo của O. V. Lyashko trên tạp chí này. (Ghi chú của biên tập viên)

⟦folio 28⟧

chỉ là một giá trị gần đúng, có giá trị miễn là bước sóng ánh sáng nhỏ hơn nhiều so với kích thước của vật thể đang nghiên cứu.

Trước khi nói về "khả năng" của microsop, chúng ta hãy xem xét một số bài toán cơ học. Không giống nhau về mặt nghĩa đen, nó vẫn sẽ giúp hiểu được mục tiêu về khả năng của một thiết bị quang học nằm ở đâu.

Hãy tưởng tượng rằng một nhà nghiên cứu nào đó quyết định nghiên cứu hình dạng của một bề mặt lạnh. Đặc biệt, để làm được điều này, ông đã tình cờ giảm độ vuông góc đã khôi phục với bề mặt tại bất kỳ điểm nào. Nhà nghiên cứu đã tiếp cận bài toán này theo một cách hơi khác thường - anh ta bắt đầu ném những quả bóng urtug lên bề mặt, mỗi lần đo góc giữa hướng tới và hướng phản xạ của quả bóng và xây dựng một bissertis của góc này. Rõ ràng, bằng cách này, thực sự có thể thu được tập hợp các đường vuông góc cần thiết, nhưng chỉ khi đường kính của quả bóng nhỏ hơn nhiều so với khoảng cách giữa các “bướu” gần và bán kính cong của chúng (Hình 1, a). Mặt khác (Hình 1, b) không thể thu được thông tin về hình dạng của bề mặt.

Điều gì đó tương tự cũng xảy ra khi quan sát một vật thể trong kính hiển vi, mặc dù có sự khác biệt đáng kể giữa tia sáng và quả bóng. Như chúng tôi muốn

Cơm. 1.

Cơm. 2.

Để kiểm tra ngày càng nhiều chi tiết đẹp của một vật thể, chúng ta thay đổi độ phóng đại của kính hiển vi. Hóa ra ở độ phóng đại khoảng 2000 lần, có thể phân biệt được hai điểm nếu chúng nằm ở khoảng cách khoảng 0,2 micron với nhau, tức là khoảng một nửa bước sóng đối với ánh sáng khả kiến. Về mặt hình thức, bạn có thể thêm độ phóng đại của kính hiển vi lên tới 5000 và 10.000, tuy nhiên, trong trường hợp này, các điểm nằm ở khoảng cách dưới 0,2 micron sẽ không thể phân biệt được.

Chúng ta hãy thử tìm hiểu tại sao điều này xảy ra bằng cách chuyển sang tính chất sóng của ánh sáng. Hãy xem xét một thấu kính mỏng (có thể dùng làm vật kính hiển vi của chúng ta). Đặt ảnh của một điểm A nào đó tại điểm B (Hình 2). Chúng ta hãy lấy điểm A', gần điểm A. Từ quang học hình học, ta suy ra rằng ảnh của nó sẽ ở một điểm nào đó B', điểm này rõ ràng không trùng với điểm B. Tuy nhiên, liệu luôn có thể phân biệt được điểm B và B' từ xa, tức là xem chúng chính xác là hai điểm?

Theo quan điểm của quang học sóng, ảnh trong thấu kính của mỗi điểm được hình thành bởi tổng số tia truyền qua thấu kính. Trong ví dụ của chúng ta, điều này có nghĩa là ảnh của điểm A' sẽ không trùng với điểm B nếu thời gian truyền của tia cực đại A'MB và A'NB qua thấu kính là khác nhau. Điều này có nghĩa là gì? Ở đây cần lưu ý rằng thời gian có thể được coi là khác nhau nếu chúng khác nhau ít nhất một chu kỳ T của dao động của sóng ánh sáng. Trong bài toán được xem xét, đây là thang thời gian duy nhất có sẵn cho chúng tôi.

Vì vậy cần phải thỏa mãn điều kiện
