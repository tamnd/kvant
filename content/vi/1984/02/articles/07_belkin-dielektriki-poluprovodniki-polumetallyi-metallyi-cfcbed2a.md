---
id: 1984-2-belkin-dielektriki-poluprovodniki-polumetallyi-metallyi-cfcbed2a
issue: kvant_1984_2
year: 1984
number: "2"
title: Chất điện môi, chất bán dẫn, bán kim loại, kim loại
authors:
  - Белкин И. К.
rubric: shkola-v-kvante
page_first: 27
page_last: 29
page_labels: 25, 27
tag: U2JR
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c3925afac5e157060b0b22f990d2637efaed2ddcffd8276ce7e9a4183c7dfae7
prompt_sha256: draft-1
translated_from: content/ru/1984/02/articles/07_belkin-dielektriki-poluprovodniki-polumetallyi-metallyi-cfcbed2a.md
source_content_sha256: cbe758225beae6c217896aa8b6a1de0319e3e7970c2fcfb7397e6a38ec9b6154
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 25⟧

(tọa độ ban đầu) và tốc độ là $v_{0x}$ (tốc độ ban đầu). Chúng ta hãy chọn khoảng $\Delta t$ sao cho trong thời gian này lực $F_x$, và do đó gia tốc $a_x$, có thể được coi là không đổi. Chúng ta biết lực $F_{0x}$ vì chúng ta biết lực phụ thuộc như thế nào vào tọa độ; Chúng tôi cũng biết $a_{0x}$, vì $a_{0x} = F_{0x}/m$. Do đó, theo các công thức chuyển động có gia tốc đều mà chúng ta đã biết về tốc độ $v_{1x}$ và tọa độ $x_1$ ở cuối khoảng thời gian $\Delta t$, chúng ta có thể viết:

$$v_{1x} = v_{0x} + a_{0x} \Delta t,$$

$$x_1 = x_0 + v_{0x} \Delta t + \frac{a_{0x} \Delta t^2}{2}.$$

Sau đó xem xét chuyển động của vật trong khoảng thời gian nhỏ không kém tiếp theo $\Delta t$. Tọa độ ban đầu bây giờ sẽ là giá trị $x_1$ mà chúng tôi đã tìm thấy và tốc độ ban đầu sẽ là giá trị $v_{1x}$. Trong khoảng thời gian thứ hai này, một lực khác sẽ tác động lên cơ thể - $F_{1x}$. Chúng ta sẽ tìm giá trị của nó bằng cách biết sự phụ thuộc của lực vào tọa độ. Gia tốc của cơ thể $a_{1x}$ cũng sẽ tương ứng với những người khác. Như vậy, đến hết thời gian thứ hai vận tốc của vật sẽ bằng

$$v_{2x} = v_{1x} + a_{1x} \Delta t,$$

và tọa độ là

$$x_2 = x_1 + v_{1x} \Delta t + \frac{a_{1x} \Delta t^2}{2}.$$

Các giá trị tốc độ và tọa độ này sẽ là giá trị ban đầu cho chuyển động của cơ thể trong quãng tiếp theo, quãng ba, và chúng ta sẽ tìm các giá trị tốc độ và tọa độ ở cuối quãng này theo cách tương tự. Như vậy, “di chuyển” từng bước một, chúng ta sẽ có thể xác định được tọa độ $x$ của vật bất cứ lúc nào. Tương tự, chúng ta có thể tìm tọa độ $y$ và $z$.

Trong quy trình mà chúng tôi đã xem xét, không khó để nhận thấy lỗi hệ thống mà chúng tôi mắc phải. Nó nằm ở chỗ lực và gia tốc được coi là không đổi trong mỗi khoảng thời gian nhỏ $\Delta t$, và khi kết thúc khoảng thời gian đó chúng thay đổi đột ngột. Trong khi đó, trên thực tế, cả lực và gia tốc luôn thay đổi liên tục. Bạn có thể giảm thiểu lỗi này bằng cách giảm giá trị $\Delta t$. Lỗi sẽ gần như biến mất hoàn toàn nếu khoảng thời gian được thực hiện vô cùng nhỏ. Nhưng khi đó số lượng “bước” sẽ trở nên vô cùng lớn và điều này sẽ khiến quá trình này không thể thực hiện được.

Đặc biệt đối với những trường hợp như vậy, một bộ máy toán học đặc biệt đã được phát triển, được gọi là phép tính vi phân và tích phân (Newton đã phát minh ra nó chính xác cho mục đích này). Với sự trợ giúp của nó, cơ chế bài toán chính đã được giải quyết. Nhưng nguyên tắc lời giải chính xác là nguyên tắc mà chúng tôi đã xem xét ở đây. Bằng cách này, các máy tính hiện đại tính toán các chuyển động cơ học phức tạp (ví dụ: vệ tinh và tên lửa).

Để kết luận, chúng tôi lưu ý những điều sau đây. Khi chúng ta nói rằng bài toán chính của cơ học là tìm tọa độ chuyển động của một vật bằng cách sử dụng các lực đã biết và các điều kiện ban đầu, điều này không có nghĩa là tất cả những gì cơ học đều làm. Điều cũng xảy ra là chuyển động của một vật, tức là vị trí của nó tại bất kỳ thời điểm nào, đều được biết qua các quan sát. Khi đó các định luật chuyển động cho phép chúng ta tìm lực tác dụng lên vật. bài toán này, cái gọi là cơ chế bài toán nghịch đảo, cũng quan trọng như cơ chế bài toán cơ bản mà chúng tôi đã xem xét, nhưng, để dễ hiểu, nó đơn giản hơn nhiều.

Chất điện môi, chất bán dẫn, bán kim loại, kim loại

Trong vật lý cổ điển, người ta thường phân chia tất cả các chất theo tính chất điện của chúng thành chất dẫn điện và chất điện môi (“Vật lý 9”, §§ 44 và 46). Vật lý hiện đại phân biệt hai trạng thái trung gian hơn - chất bán dẫn (Vật lý 9, § 78) và bán kim loại. Chỉ với sự ra đời của cơ học lượng tử, người ta mới biết rõ sự khác biệt giữa tất cả các loại chất này. Trong lưu ý này, chúng tôi sẽ cố gắng đưa vào bản chất của lượng tử hiện đại

⟦folio 27⟧

cung cấp cho nó thêm năng lượng, và theo định luật cơ học lượng tử, điều này chỉ có thể thực hiện được bằng cách chuyển nó lên mức năng lượng cao hơn. Nhưng nguyên tắc Pauli cấm thợ điện chiếm giữ các tầng đã có người sử dụng và họ không thể đi vào vùng được phép tiếp theo, vùng này hoàn toàn trống, vì năng lượng nhận được từ điện trường nhỏ hơn nhiều so với chiều rộng Δ của vùng cấm.

Ở nhiệt độ khác 0, về nguyên tắc, các electron có thể di chuyển vào vùng dẫn và trở thành chất mang dòng điện. Tuy nhiên, để số lượng electron chuyển sang vùng này đủ lớn, chất điện môi phải được nung nóng đến nhiệt độ cao đến mức tan chảy trước khi dòng điện đạt đến giá trị thay đổi. Ở nhiệt độ phòng, dòng điện trong chất điện môi thực tế là lẻ.

Chất bán dẫn. Chất bán dẫn chỉ khác chất điện môi ở chỗ chiều rộng Δ của vùng cấm ngăn cách vùng hóa trị với vùng dẫn nhỏ hơn nhiều (mười lần). Tại T=0, dải hóa trị trong chất bán dẫn, cũng như trong chất điện môi, được lấp đầy hoàn toàn và dòng điện không thể chạy qua mẫu. Nhưng do năng lượng Δ không cao nên ngay cả khi nhiệt độ tăng nhẹ, một số electron có thể di chuyển vào vùng dẫn (Hình 3). Sau đó, một dòng điện sẽ xuất hiện trong chất đó và thông qua hai “kênh” cùng một lúc.

Thứ nhất, trong vùng dẫn, các electron tiết kiệm năng lượng trong điện trường sẽ chuyển lên mức năng lượng cao hơn. Thứ hai, nó bao gồm trong dòng điện... các mức trống còn lại trong vùng hóa trị bởi các electron đã chạy vào vùng dẫn. Thật vậy, nguyên lý Pauli cho phép bất kỳ electron nào cũng chiếm một mức trống trong vùng hóa trị. Tuy nhiên, sau khi chiếm giữ cấp độ này, nó sẽ để cấp độ riêng của mình tự do, v.v. Nếu bạn không theo dõi chuyển động của các electron dọc theo cấp độ trong dải hóa trị mà là chuyển động của chính các cấp độ trống, thì hóa ra các cấp độ này, có tên ban đầu là *lỗ*, cũng trở thành chất mang dòng điện. Số lượng lỗ trống, rất indo, bằng số lượng electron đi vào vùng dẫn (còn gọi là *electron dẫn*), nhưng lỗ trống có điện tích dương vì lỗ trống là một electron bị thiếu.

Như vậy, trong chất bán dẫn, dòng điện là dòng điện của các electron trong vùng dẫn và các lỗ trống trong vùng hóa trị. Độ dẫn điện này của chất bán dẫn được gọi là *nội tại*.

Các electron và lỗ trống khi di chuyển trong tinh thể sẽ tương tác với các nguyên tử của mạng tinh thể, làm mất năng lượng. Liên quan đến sự mất mát này là điện trở của vật chất. Khi nhiệt độ tăng, tổn thất năng lượng tăng, do đó điện trở của chất bán dẫn cũng tăng khi nhiệt độ tăng. Nhưng khi nhiệt độ tăng, số lượng electron di chuyển vào vùng dẫn tăng lên, và do đó, số lượng lỗ trống trong vùng hóa trị cũng tăng lên. Điều này có nghĩa là nó đang phát triển (và rất
