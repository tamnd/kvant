---
id: 1991-3-uoker-dvizhenie-v-chas-pik-fc4659a2
issue: kvant_1991_3
year: 1991
number: "3"
title: Giao thông giờ cao điểm
authors:
  - Уокер Дж.
rubric: raznoe
page_first: 34
page_last: 39
page_labels: 32-37
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 78e2d89d6a9f03655b5834cb4a963c879e8d97f10778ffa1cec0f4330bab5f06
prompt_sha256: draft-1
translated_from: content/ru/1991/03/articles/09_uoker-dvizhenie-v-chas-pik-fc4659a2.md
source_content_sha256: b750488f3fe6d61f70a54d38f236a39772c8cf7da7a0c25c6a736ae2e78f00ab
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 32⟧

GIAO THÔNG TRONG GIỜ CAO ĐẠI

J. Walker

⟦folio 33⟧

---
running_head:
folio:
---

Đèn giao thông ở một thị trấn nhỏ thường không cần nhiều quy định. Luồng giao thông qua hệ thống đèn giao thông có thể ngẫu nhiên, nhưng hàng đợi đèn đỏ hiếm khi dài. Nhưng ở thành phố lớn, nhất là vào giờ cao điểm, việc điều chỉnh cẩn thận là cần thiết. Nếu không có nó, đuôi ô tô sẽ giãn ra và chặn các giao lộ, tạo ra cái gọi là ùn tắc giao thông và có thể mất hàng giờ để giải phóng ô tô khỏi bị giam cầm.

Giả sử bạn phải thiết kế hệ thống tín hiệu giao thông cho đường một chiều có nhiều làn đường. Mỗi đèn giao thông có màu xanh trong 50 giây, màu vàng trong 5 giây và màu đỏ trong 25 giây (đèn giao thông điển hình cho khu vực đô thị đông đúc). Bạn có thể muốn tăng thời gian đèn xanh và giảm thời gian đèn đỏ để "duy trì" luồng giao thông. Tuy nhiên, chúng ta phải nhớ rằng giao thông trên những con đường vuông góc không thể bị ứ đọng quá lâu, nếu không sẽ có hàng dài người xếp hàng ở đó.

Cách tính thời gian bật đèn xanh tại các nút giao nhau? Rõ ràng là nếu bạn bật tất cả các tín hiệu xanh cùng một lúc thì chuyển động sẽ chỉ có thể thực hiện được trong 50 giây. Mỗi khi đèn chuyển sang màu xanh, giao thông sẽ di chuyển dọc đường cho đến khi tất cả đèn giao thông chuyển sang màu đỏ. Để đi được càng xa càng tốt, người lái xe cố gắng tăng tốc độ cho xe. Những dòng ô tô lớn di chuyển với tốc độ 55 mph (≈90 km/h) qua các đường phố của một thành phố đông dân sẽ giống như đua xe tự động và rõ ràng là sẽ nguy hiểm.

Một dự án tốt hơn và an toàn hơn sẽ là một dự án trong đó đèn giao thông ở mỗi ngã tư không chuyển sang màu xanh cho đến khi những chiếc xe phía trước của nhóm từ ngã tư trước đó đang tiến đến. Ví dụ: giả sử một nhóm ô tô đang ở ngã tư I và đang di chuyển về phía ngã tư II. Sau bao lâu đèn xanh bật ở ngã tư I thì đèn xanh ở ngã tư II bật? Gọi $d$ là khoảng cách giữa hai nút giao thông và $v_r$ là tốc độ mà bạn nghĩ nhóm ô tô nên có (có thể là tốc độ giới hạn). Thời gian trễ cần thiết để bật đèn xanh ở ngã tư II là $d/v_r$. Nếu khoảng cách giữa các giao lộ bằng nhau thì độ trễ tín hiệu xanh từ giao lộ này sang giao lộ tiếp theo luôn là $d/v_r$ và người lái xe đi ở $v_r$ sẽ đi qua toàn bộ hệ thống đèn giao thông mà không dừng lại. Sơ đồ này cũng hoạt động tốt nếu khoảng cách giữa các nút giao thông khác nhau. Bạn chỉ cần xem xét các giá trị mong muốn của $d$ để xác định độ trễ thời gian cho tín hiệu xanh tại một giao lộ nhất định. Lái xe với tốc độ lớn hơn $v_r$ qua hệ thống đèn giao thông cũng được miễn phí vì bạn sẽ phải dừng lại khi đèn đỏ.

Đề án được thay đổi một chút bởi hai yếu tố. Trưởng nhóm phải nhìn thấy đèn xanh bật trước khi đến gần ngã tư, nếu không sẽ giảm tốc độ, sợ vượt đèn đỏ. Xem xét yếu tố này, bạn nên giảm thời gian trễ để bật tín hiệu xanh xuống vài giây. Tuy nhiên, nếu một nhóm ô tô dừng đèn đỏ ở Giao lộ I trong vài giây, xe dẫn đầu sẽ mất thêm vài giây để phản ứng với đèn xanh ở đó và tăng tốc. Như vậy, xe phía trước không di chuyển với tốc độ $v_r$ trong suốt khoảng cách giữa các nút giao thông. Yếu tố này yêu cầu tăng thời gian trễ để bật tín hiệu xanh thêm vài giây. Trong một số trường hợp, hai yếu tố này có thể triệt tiêu lẫn nhau.

Tất cả những điều này được thể hiện ở hình 1. Bên trái là hệ thống đèn giao thông, bên phải là biểu đồ các đoạn đường mà ô tô đi qua của nhóm đứng ở thời điểm $t=0$ trước ngã tư.

⟦folio 34⟧

---
running_head:
folio:
---

Hình 1. Minh họa bằng đồ họa về cách một nhóm ô tô rời khỏi ngã tư tôi di chuyển qua hệ thống đèn giao thông.

com I. Các phần cong của đồ thị tương ứng với sự tăng tốc và giảm tốc chuyển động của ô tô khi chuyển đèn giao thông. Lưu ý đèn giao thông ở ngã tư II chuyển sang màu xanh vài giây trước khi xe dẫn đầu tiếp cận đèn đó.

Nhưng ngay cả khi hệ thống đèn giao thông hoạt động chậm trễ thì giao thông vẫn có thể bị ùn tắc. Vấn đề là nếu nhóm đã dừng lại và bắt đầu di chuyển khi đèn xanh bật lên, họ sẽ tự động tăng tốc không phải cùng lúc mà theo thứ tự quay. Một làn sóng khởi đầu xuất phát từ lidar khắp nhóm ô tô. (Bạn có thể thay đổi tốc độ của làn sóng xuất phát bằng cách định vị mình gần một nhóm ô tô đang dừng. Xác định độ dài của nhóm bằng cách nhân số ô tô với khoảng cách gần đúng giữa các thanh cản gấp. Sau đó thay đổi thời gian từ đèn xanh đến ô tô cuối cùng đang di chuyển. Tốc độ của làn sóng xuất phát là chiều dài của nhóm chia cho thời gian đã thay đổi. Thông thường là 5 m/s (11 mph.) Vì vậy, so với người dẫn đầu, người cuối cùng tự động không những phải lái một quãng đường dài hơn đến giao lộ II mà còn phải chờ cho đến khi đến đó. Có làn sóng xuất phát. Như vậy, với một “đuôi” dài trước đèn giao thông, chiếc xe cuối cùng sẽ luôn phải mất một thời gian dài mới đến được ngã tư tiếp theo.

Nếu người cuối nhóm không kịp vượt đèn xanh với những xe còn lại (đây chính xác là tình huống mà hình 1), các nhóm tiếp theo có thể bắt đầu dài ra. Ta xét trường hợp phần đuôi ô tô vẫn ở giao lộ II như hình vẽ. hình 2. Gọi đoạn này là A. Trong lúc A đang chờ đèn đỏ, nhóm B đến ngã tư tôi nhận được tín hiệu xanh và bắt đầu di chuyển (tình huống 2, 3). Nếu đèn giao thông ở ngã tư II được điều chỉnh thành lidar nhóm B (tức là tốc độ trung bình của nó thấp hơn $v_r$), đèn xanh tại ngã tư II bị trễ, các xe phía trước của nhóm B chạy lên “đuôi” của nhóm A trước khi những chiếc Atron số tự động đầu tiên xuất phát. Mọi thứ còn phức tạp hơn bởi những chiếc xe cuối cùng của nhóm A phải đợi cho đến khi làn sóng xuất phát đến với họ.

Hình 2. Nếu đèn xanh bị trễ ở ngã tư II, nhóm xe đang dừng có thể đông hơn (C+D lớn hơn A+B).

⟦folio 35⟧

---
running_head:
folio:
---

Kết quả là $A$ và $B$ hợp nhất, tạo thành một nhóm mới tại ngã tư II. Có thể còn quá lâu để hoàn thành nút giao II. Gọi $C$ là đuôi của nhóm vượt đèn đỏ tiếp theo tại ngã tư II (tình huống 7 tại hình 2). Nếu $C$ dài hơn $A$, tình trạng này sẽ biến mất. Trong khi $C$ đang vượt đèn đỏ, nhóm tiếp theo tiến đến từ ngã tư I (hãy gọi là $D$). Khi đó, nhóm đã hợp nhất của $C$ và $D$ có thể dài hơn nhóm trước đó của $A$ và $B$, và kết quả là phần đuôi tiếp theo còn lại ở giao lộ II sẽ dài hơn $C$.

Nếu với mỗi lần chuyển tín hiệu, “đuôi” mới còn lại ở ngã tư II dài hơn “đuôi” trước đó thì tình hình có thể nhanh chóng trở nên vô vọng. Cuối cùng, “đuôi” dài đến mức kéo dài đến giao lộ I. Giả sử tại giao lộ này có một nhóm ô tô ở phía trước đèn giao thông màu đỏ I. Khi đèn chuyển sang màu xanh, họ đi vào giao lộ I. Vì những ô tô này không thể di chuyển cho đến khi có làn sóng xuất phát từ giao lộ II đến chỗ họ, nên họ ở cùng một chỗ khi đèn chuyển sang màu đỏ tại giao lộ I. Người lái xe trên đường vuông góc không thể đi tiếp khi đèn giao thông chuyển sang màu xanh—nút giao thông I bị chặn. Dòng người xếp hàng trên các con đường phụ ngày càng dài và các giao lộ khác đang bị phong tỏa. Tình trạng tắc nghẽn nhanh chóng lan rộng cho đến khi toàn bộ khu vực trở thành một bãi đậu xe lớn.

Ùn tắc giao thông có thể xảy ra ngay cả khi có hệ thống đèn giao thông tốt. Tuy nhiên, tôi lại bị kẹt xe ở Cleveland khi tuyết bắt đầu rơi dày đặc vào giờ cao điểm buổi chiều. Vì đường tôi đang lái xe trơn trượt nên các xe dẫn đầu trong đoàn đều chạy chậm. Các đợt xuất phát cũng di chuyển chậm hơn bình thường. Khoảng 20 phút sau, những “đuôi” kéo dài gần hết các nút giao thông trước đó, chặn đường. 2 dặm dọc theo tuyến đường của tôi và năm song song

Giao thông trên các trục đường Lelny gần như dừng lại. Tôi hơi bị bán chỉ vì những chiếc xe ở cuối tuyến đang dần di chuyển vào vùng ngoại ô. Ngay sau khi họ tách khỏi nhóm, làn sóng khởi đầu bắt đầu di chuyển dần dần qua biệt đội hai triệu người và tạo cơ hội cho tôi điều động một số quân đoàn súng máy về phía trước. Một chuyến đi đáng lẽ phải mất năm phút nhưng lại mất hơn hai giờ!

Tình trạng ùn tắc giao thông do tuyết rơi bên ngoài không thể giảm bớt. Tuy nhiên, có thể tránh được tình trạng ùn tắc giao thông do độ dài nhóm máy không mong muốn nếu kỹ sư hoặc máy tính làm việc cùng nhau theo trình tự thay đổi tín hiệu bình thường. Giả sử rằng thông qua hệ thống cảm biến từ xa, bạn phát hiện ra sự tích tụ dần dần của giao thông tự động tại giao lộ II. Đặt $A$ là một nhóm ô tô bị giữ ở đó tại thời điểm chúng ta ở bên nhau, và $B$ là một nhóm ô tô bị bỏ lại ở ngã tư I. Tùy thuộc vào độ dài của $A$ là bao nhiêu, c-

Hình 3. Các yếu tố quan trọng trong việc xác định thời điểm tương đối của đèn xanh tại các nút giao I và II liền kề.

⟦folio 36⟧

---
running_head:
folio:
---

Tuatsyumo có thể được “xả” theo hai cách. Có thể bật đèn xanh ở cả hai nút giao thông cùng một lúc; nhưng với một “đuôi” dài $A$ đường dẫn này có thể không hoạt động. Bạn có thể bật đèn xanh ở ngã tư II sớm hơn ở ngã tư I. Bạn nên đi đường nào? Điều này phụ thuộc vào sự tương ứng giữa độ dài $l$ của “đuôi” $A$ và khoảng cách $d$ giữa các giao lộ.

Nếu các xe phía trước $B$ di chuyển về phía “đuôi” $A$ với tốc độ không đổi $v_r$, chúng cần thời gian $(d-l)/v_r$ để hoàn thành đoạn này (xem hình 3). Trong khi đó, sóng bắt đầu di chuyển dọc theo $A$ với tốc độ $v_c$ và phải mất thời gian $l/v_c$ để đến được phía sau $A$. Để đội tiên phong của nhóm $B$ đạt $A$ vào thời điểm những xe đó bắt đầu di chuyển thì khoảng thời gian giữa đèn xanh ở giao lộ I và II phải là

$$t = \frac{d-l}{v_r} - \frac{l}{v_c} = \frac{1}{v_r} \left( d-l \left( 1 + \frac{v_r}{v_c} \right) \right).$$

Nếu như

$$\frac{l}{d} = \frac{v_c}{v_c + v_r},$$

thì $t=0$ - điều này có nghĩa là với sự tương ứng như vậy giữa $l$ và $d$ giao lộ I và II phải được “mở” đồng thời. Tại

$$l > d \frac{v_c}{v_c + v_r}$$

thời gian $t$ chuyển sang âm, tức là đèn giao thông II phải chuyển sang đèn xanh vào thời điểm $t$ sớm hơn đèn giao thông I. Nếu

$$l < d \frac{v_c}{v_c + v_r},$$

sau đó đèn xanh bật trước ở ngã tư I. Với tốc độ giao thông thông thường là 10 m/s (22 mph) và tốc độ sóng khởi đầu là 5 m/s, cần bật đồng thời đèn xanh ở $l/d=1/3$. Nếu $l/d>1/3$ thì nên bật đèn xanh ở ngã tư II sớm hơn ở ngã tư I.

Có thể nói rằng chúng tôi đã tìm ra tốc độ di chuyển của “làn sóng” bật đèn xanh dọc đường phố. Nếu $l/d<1/3$, sóng này di chuyển theo hướng của ô tô và có cùng tốc độ với ô tô. Tại $l/d=1/3$ đèn chuyển sang màu xanh ở tất cả các giao lộ. Nếu $l/d>1/3$, làn sóng xanh đang di chuyển ngược hướng với ô tô.

Kết quả này chỉ là ước tính sơ bộ vì phép tính đã bỏ qua ba sự kiện. Các xe phía trước của nhóm $B$ bắt đầu di chuyển, sau khi dừng lại tăng tốc. Người lái xe của họ phải thấy rằng đuôi $A$ đã bắt đầu di chuyển tốt trước khi họ đến gần nó, nếu không họ sẽ giảm tốc độ hoặc dừng lại để đề phòng. Tất nhiên, những chiếc xe cuối cùng $A$ phải tăng tốc trước khi những chiếc xe $B$ đến gần. Tôi hy vọng bạn thích thực hiện một phép tính chính xác có tính đến các yếu tố bổ sung này.

Bạn sẽ thiết kế hệ thống đèn giao thông như thế nào để tối ưu hóa luồng giao thông trên đường hai chiều? Có cách nào để ngăn ô tô dừng lại trên đường như vậy không? Có thể sử dụng máy tính để hỗ trợ chuyển động của một nhóm ô tô thông qua hệ thống đèn giao thông không? Nếu vậy, bạn sẽ có thể khám phá vấn đề ùn tắc giao thông mà không cần vướng vào chúng.

⟦folio 37⟧

---
running_head:
folio:
---

Vật lý 9, 10, 11

Ghi chú được xuất bản bên dưới “Về hai phương pháp tương tác” dành cho tác phẩm kinh điển, ghi chú “Về sông băng, nồi áp suất và định lý Carnot” dành cho tác phẩm kinh điển, “Quang phổ của nguyên tử hydro nói về điều gì” cũng cổ điển không kém.
Ngoài ra, chúng tôi tiếp tục xuất bản “Trường được chọn bài toán môn Vật lý”.
