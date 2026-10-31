---
id: 1985-4-stasenko-o-funktsiyah-raspredeleniya-849d122c
issue: kvant_1985_4
year: 1985
number: "4"
title: Về chức năng phân phối
authors:
  - Стасенко А. Л.
rubric: osnovnye-stati
page_first: 10
page_last: 12
page_labels: 8-10
tag: 7VLW
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 8944d002985df026d4619ae9ecf918591a3a06c58bdc97c7c49b3a3823639fec
prompt_sha256: draft-1
translated_from: content/ru/1985/04/articles/04_stasenko-o-funktsiyah-raspredeleniya-849d122c.md
source_content_sha256: 7a055a0f4da95b36e0dfa87fd47e0bd1582365a43159fec3f012b0c16764a2da
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 8⟧

Về chức năng phân phối

(hoặc Cách tưới vườn bằng gió)

Tiến sĩ khoa học kỹ thuật
A. L. STASENKO

“Trên sân ga, ở cuối tàu, hành khách phải được phân bổ đều dọc theo chiều dài của tàu…”
(Trích “Quy tắc sử dụng tàu điện ngầm Moscow mang tên V.I. Lênin”)

Cụm từ trong epigraph, ý nghĩa "hàng ngày" của nó hoàn toàn rõ ràng, gợi nhớ đến khái niệm về hàm phân phối, phổ biến trong vật lý. Chúng ta bắt đầu với các hàm phân phối ở mức lời giải lý thuyết và thực tế bài toán, trong đó các hệ có số lượng hạt lớn được xem xét. Để rút ra sự tương đồng giữa yêu cầu của “Quy tắc” và khái niệm về hàm phân phối, chúng ta hãy “dịch” biểu đồ sang ngôn ngữ toán học.

Chúng ta hãy chia sân ga (chính xác hơn là phần sân ga gần nơi tàu dừng) tuần tự thành các đoạn có chiều dài $\Delta x_1$, $\Delta x_2$, ..., $\Delta x_k$, ..., $\Delta x_m$. Ta biểu thị số lượng hành khách chờ tàu ở mỗi đoạn bằng $\Delta n_1$, $\Delta n_2$, ..., $\Delta n_k$, ..., $\Delta n_m$. Khi đó, "Quy tắc" yêu cầu tỷ lệ $\Delta n_i$ đến $\Delta x_i$ phải giống nhau đối với mọi $i=1, 2, ..., k, ..., m$, nghĩa là

$$\frac{\Delta n_i}{\Delta x_i} = f_0 = \text{const.}$$

Chúng tôi biểu thị mối quan hệ này bằng chữ cái $f$ để nhấn mạnh rằng, trên thực tế, nó cũng có thể là một loại chức năng nào đó của $x$; nhưng trong trường hợp này, nếu công dân cư xử tốt trên nền tảng thì chức năng này sẽ tồn tại vĩnh viễn ($f_0$). Trên hình 1 đồ thị của nó được hiển thị - một đường thẳng.

Nhưng sau đó tàu đến, và thậm chí trước khi cửa các varon mở ra, “rất nhiều” công dân đã tụ tập xung quanh họ. Khi đó, sự phân bố của họ dọc theo sân ga không còn đồng nhất và nó có thể được biểu diễn một cách định tính dưới dạng đường cong $f(x)$, như trong hình 1. Nếu số lượng công dân không thay đổi trong khi chờ tàu, thì thực tế này bằng cách nào đó sẽ được phản ánh trong hai biểu đồ này. Thật vậy, trong khi chờ đợi ở mỗi phần $\Delta x_i$ của sân ga, theo (1), số lượng công dân bằng

$$\Delta n_i = f_0 \cdot \Delta x_i;$$

Điều này có nghĩa là để tìm tổng số hành khách trên toàn bộ sân ga, bạn cần cộng số lượng của họ trên từng khu vực. chúng tôi nhận được

$$N = \sum_{i=1}^{m} \Delta n_i = \sum_{i=1}^{m} f_0 \cdot \Delta x_i = f_0 \sum_{i=1}^{m} \Delta x_i = f_0 \cdot L,$$

trong đó $L$ là chiều dài của sàn. Như có thể thấy từ hình 1, $f_0$ L là diện tích chuyển động trực tiếp $f_0$ và chiều dài $L$. Và đây là tổng số hành khách $N$. Sau khi tàu đến, sự phân bố trên sân ga thay đổi và trở thành một số hàm $f(x)$, tổng của tất cả các giá trị $f(x_i) \cdot \Delta x_i$ cũng là diện tích dưới đường cong $f(x)$ và vẫn là tổng số công dân $N$:

$$\sum_i f(x_i) \cdot \Delta x_i = N.$$

Chỉ là phương trình $f(x)$ là một hằng số $f_0$ và trong công thức (2) chúng tôi đã lấy nó làm dấu tổng, nhưng bây giờ điều này không thể thực hiện được - trong mỗi phần $\Delta x_i$

⟦folio 9⟧

số lượng công dân của họ (họ đã được phân phối lại).

"Bah! - nhà toán học sẽ kêu lên (anh ta chỉ đơn giản là có nghĩa vụ phải thốt lên như vậy), - nhưng những gì được viết trong (1), trong giới hạn, khi các đoạn $\Delta x_i$ ngày càng nhỏ hơn, sẽ biến thành thứ được gọi là đạo hàm của $n$ bởi $x$:

$$f(x_i) = \lim_{x_i \to 0} \frac{\Lambda n_i}{\Lambda x_i} = \frac{dn}{dx},$$

và những gì được viết ở (3) được tính vào tích phân $f(x)$ trên toàn bộ chiều dài $L$ của nền:

$$N = \lim_{x_i \to 0} \sum_{i=1}^{m} f(x_i) \Delta x_i = \int_0^L f(x) dx.$$

Và nếu anh ấy kêu lên như vậy thì anh ấy sẽ hoàn toàn đúng.

Vì vậy, việc phân bổ công dân dọc theo sân ga trong khi chờ tàu có thể được mô tả bằng hàm $f(x) = \frac{dn}{dx}$, đương nhiên được gọi là hàm phân bổ hành khách dọc theo chiều dài của sân ga.

Bây giờ, có lẽ độc giả sẽ thốt lên: “Tại sao, theo cách này, vận tốc tổng quát nhất của một điểm vật chất, tức là đạo hàm của sự dịch chuyển theo thời gian, có thể là

$$\vec{v} = \frac{\vec{ds}}{dt} = \lim_{t \to 0} \frac{\Delta s}{\Delta t},$$

- gọi là phân bố chuyển vị điểm theo thời gian; tăng tốc -

$$\vec{a} = \frac{\vec{dv}}{dt} = \lim_{t \to 0} \frac{\Delta v}{\Delta t}$$

- phân bố tốc độ theo thời gian; và tổng mật độ của một chất, nghĩa là đạo hàm của khối lượng theo thể tích -

$$\varrho = \frac{dm}{dV} = \lim_{V \to 0} \frac{\Delta m}{\Delta V},$$

— phân bố khối lượng theo thể tích!?” Tất cả những điều này đều đúng, tuy nhiên từ “phân phối” lại mang ý nghĩa riêng của nó trong vật lý và trong cuộc sống hàng ngày. Ví dụ, họ nói về sự phân bố của các phân tử khí theo mô đun vận tốc ($\frac{dn}{dv} \frac{\text{молекул}}{\text{м/с}}$); về sự phân phối sản phẩm trong dân chúng ($\frac{dm}{dn} \frac{\text{кг}}{\text{человек}}$), chứ không phải về đạo hàm của khối lượng sản phẩm theo số lượng công dân; về sự phân bố học sinh theo độ tuổi ($\frac{dn}{dt} \frac{\text{школьников}}{\text{лет}}$). Có lẽ, ở đâu đó trong lớp 10, phân bố cuối cùng này có dạng như trong hình 2: giá trị lớn nhất của hàm $f(t)$ tương ứng với (xấp xỉ) 17 năm; khó có thể xảy ra ở lớp 10 của một người nào đó (sau đây gọi là rất có năng lực) từ mẫu giáo hoặc ở tuổi nghỉ hưu - vì vậy hàm phân phối có xu hướng về 0 khá nhanh ở hai bên giá trị tối đa.

Một hàm rất thú vị (có lẽ đặc biệt đối với học sinh lớp 10) là hàm phân phối số người nộp đơn theo số bài toán mà họ đã giải được trong kỳ thi tuyển sinh. Theo quy định, hàm đồ họa này có thể được biểu thị bằng đường cong I hoặc đường cong II trên hình 3. Nếu đó là đường cong I, thì mức tối thiểu của nó tại điểm A dễ dàng cho phép người ta thiết lập “giá” của một đánh giá thỏa đáng - tất cả những người theo dõi từ điểm A đều không vượt qua. Nếu đây là đường cong II thì giám khảo phải suy nghĩ xem giải bài toán bao nhiêu là đủ để đánh giá đạt yêu cầu.

Tầm quan trọng của hàm phân bố trong vật lý được chứng minh bởi thực tế là

⟦folio 10⟧

Nhiều trong số chúng gắn liền với những thay đổi của các nhà khoa học tuyệt vời: chẳng hạn như phân bố Bolshman và Maxwell (phân tử khí theo tốc độ), phân bố Planck (bức xạ lượng tử theo tần số của chúng), phân bố Fermi (năng lượng điện tử).

Bây giờ, sau khi đã học được ý nghĩa của các hàm phân phối, hãy giải một hàm hữu ích bài toán. Giả sử chúng ta cần tưới nước đều cho một mảnh đất nằm ngang, chẳng hạn như một vườn rau hoặc cánh đồng rộng lớn. Tất nhiên, điều này có thể được thực hiện với sự trợ giúp của xô hoặc bình tưới, như người ta nói, "đi bộ"; Bạn có thể lái xe giữa các hạt mưa đá trên máy kéo, đế là một bộ phận đặc biệt - một ống ngang có lỗ và vòi cung cấp nước (đây là cách chế tạo "tàu khu trục nhỏ", thường có thể được nhìn thấy trên đồng ruộng). Nhưng chúng tôi sẽ cố gắng sử dụng gió, loại gió hầu như luôn thổi trong không gian rộng mở.

Hãy đặt một ống nằm ngang được trang bị vòi phun ở độ cao $h$ so với mặt đất. Thông qua đường ống này, nước được cung cấp dưới áp suất, được “phun” thành những giọt bay theo mọi hướng. Bán kính của các giọt có thể khác nhau và chúng ta có thể kiểm soát tập hợp các giọt, tức là chức năng phân bố của chúng trên bán kính của chính chúng ($f(r) = \frac{dn}{dr}$).

bài toán của chúng tôi: tìm chức năng $f(r)$ để khu vực được tưới được tưới đều (nghĩa là khối lượng nước bằng nhau rơi trên bất kỳ khu vực nào có diện tích giống hệt nhau).

Trước hết, chúng ta cần tìm hiểu xem những giọt nước bay ra khỏi đường ống sẽ di chuyển như thế nào. Tất nhiên, tất cả chúng đều có một loại tốc độ ban đầu nào đó; nhưng nếu những giọt nước đủ nhỏ, chúng sẽ nhanh chóng giảm tốc độ trong không khí và khi không có gió, chúng sẽ rơi dưới đường ống xuống một dải đất hẹp song song với đường ống. Để làm rõ điều vừa nói, hãy xem xét một giọt nước có bán kính $r$ được phóng ra từ một ống xoáy thẳng đứng. Chuyển động của giọt nước sau đó xảy ra dưới tác dụng của trọng lực $mg$ và lực cản $f_c$ từ không khí. Lực cản $f_c$ phụ thuộc vào tốc độ rơi và bán kính của nó - nó lớn hơn, $v$ lớn hơn và $r$ càng lớn, đặc biệt, đối với những giọt nhỏ $f_c = bvr$, trong đó $b$ là một hệ số tỷ lệ nhất định. (Lực này được gọi là lực Stokes - theo tên nhà vật lý và toán học người Anh thế kỷ 19 J. Stokes, người đã nghiên cứu chuyển động của các vật thể trong môi trường lỏng. Sự phụ thuộc $f_c(v, r)$ này đúng chính xác trong những điều kiện rất thấp với sự thay đổi của các nhà khoa học đáng chú ý: chẳng hạn, có phân bố Bolshman và Maxwell (của các phân tử khí theo vận tốc), phân bố Planck (bức xạ lượng tử theo tần số của chúng), phân bố Fermi (electron theo năng lượng).

Bây giờ, sau khi đã học được ý nghĩa của các hàm phân phối, hãy giải một hàm hữu ích bài toán. Giả sử chúng ta cần tưới nước đều cho một mảnh đất nằm ngang, chẳng hạn như một vườn rau hoặc cánh đồng rộng lớn. Tất nhiên, điều này có thể được thực hiện với sự trợ giúp của xô hoặc bình tưới, như người ta nói, "đi bộ"; Bạn có thể lái xe giữa các hạt mưa đá trên máy kéo, đế là một bộ phận đặc biệt - một ống ngang có lỗ và vòi cung cấp nước (đây là cách chế tạo "tàu khu trục nhỏ", thường có thể được nhìn thấy trên đồng ruộng). Nhưng chúng tôi sẽ cố gắng sử dụng gió, loại gió lần đầu tiên thổi gần như hoàn toàn trong không gian rộng mở.

Hãy đặt một ống nằm ngang được trang bị vòi phun ở độ cao $h$ so với mặt đất. Thông qua đường ống này, nước được cung cấp dưới áp suất, được “phun” thành những giọt bay theo mọi hướng. Bán kính của các giọt có thể khác nhau và chúng ta có thể kiểm soát tập hợp các giọt, tức là chức năng của cùng một khu vực rơi vào cùng một khối lượng nước).

Trước hết, chúng ta cần tìm hiểu xem những giọt nước bay ra khỏi đường ống sẽ di chuyển như thế nào. Tất nhiên, tất cả chúng đều có một loại tốc độ ban đầu nào đó; nhưng nếu những giọt nước đủ nhỏ, chúng sẽ nhanh chóng giảm tốc độ trong không khí và khi không có gió, chúng sẽ rơi dưới đường ống xuống một dải đất hẹp song song với đường ống. Để làm rõ điều vừa nói, hãy xem xét một giọt nước có bán kính $r$ được phóng ra từ một ống xoáy thẳng đứng. Chuyển động của giọt nước sau đó xảy ra dưới tác dụng của trọng lực $mg$ và lực cản $f_c$ từ không khí. Lực cản $f_c$ phụ thuộc vào tốc độ rơi và bán kính của nó - nó lớn hơn, $v$ lớn hơn và $r$ càng lớn, đặc biệt, đối với những giọt nhỏ $f_c = bvr$, trong đó $b$ là một hệ số tỷ lệ nhất định. (Lực này được gọi là lực Stokes - theo tên nhà vật lý và toán học người Anh thế kỷ 19 J. Stokes, người đã nghiên cứu chuyển động của các vật thể trong môi trường lỏng. Sự phụ thuộc $f_c(v, r)$ này đúng chính xác trong các điều kiện thấp với sự thay đổi của các nhà khoa học đáng chú ý: chẳng hạn, có phân bố Bolshman và Maxwell (của các phân tử khí theo tốc độ), phân bố Planck (bức xạ lượng tử theo tần số của chúng), phân bố Fermi (electron theo năng lượng).

Bây giờ, sau khi đã học được ý nghĩa của các hàm phân phối, hãy giải một hàm hữu ích bài toán. Giả sử chúng ta cần tưới nước đều cho một mảnh đất nằm ngang, chẳng hạn như một vườn rau hoặc cánh đồng rộng lớn. Tất nhiên, điều này có thể được thực hiện với sự trợ giúp của xô hoặc bình tưới, như người ta nói, "đi bộ"; Bạn có thể lái xe giữa các hạt mưa đá trên máy kéo, đế là một bộ phận đặc biệt - một ống ngang có lỗ và vòi cung cấp nước (đây là cách chế tạo "tàu khu trục nhỏ", thường có thể được nhìn thấy trên đồng ruộng). Nhưng chúng tôi sẽ cố gắng sử dụng gió, loại gió lần đầu tiên thổi gần như hoàn toàn trong không gian rộng mở.

Hãy đặt một ống nằm ngang được trang bị vòi phun ở độ cao $h$ so với mặt đất. Thông qua đường ống này, nước được cung cấp dưới áp suất, được “phun” thành những giọt bay theo mọi hướng. Bán kính của các giọt có thể khác nhau và chúng ta có thể kiểm soát tập hợp các giọt, tức là chức năng của cùng một khu vực rơi vào cùng một khối lượng nước).

Trước hết, chúng ta cần tìm hiểu xem những giọt nước bay ra khỏi đường ống sẽ di chuyển như thế nào. Tất nhiên, tất cả chúng đều có một loại tốc độ ban đầu nào đó; nhưng nếu những giọt nước đủ nhỏ, chúng sẽ nhanh chóng giảm tốc độ trong không khí và khi không có gió, chúng sẽ rơi dưới đường ống xuống một dải đất hẹp song song với đường ống. Để làm rõ điều vừa nói, hãy xem xét một giọt nước có bán kính $r$ được phóng ra từ một ống xoáy thẳng đứng. Chuyển động của giọt nước sau đó xảy ra dưới tác dụng của trọng lực $mg$ và lực cản $f_c$ từ không khí. Lực cản $f_c$ phụ thuộc vào tốc độ rơi và bán kính của nó - nó lớn hơn, $v$ lớn hơn và $r$ càng lớn, đặc biệt, đối với những giọt nhỏ $f_c = bvr$, trong đó $b$ là một hệ số tỷ lệ nhất định. (Lực này được gọi là lực Stokes - theo tên nhà vật lý và toán học người Anh thế kỷ 19 J. Stokes, người đã nghiên cứu chuyển động của các vật thể trong môi trường lỏng. Sự phụ thuộc $f_c(v, r)$ này đúng chính xác trong các điều kiện thấp với sự thay đổi của các nhà khoa học đáng chú ý: chẳng hạn, có phân bố Bolshman và Maxwell (của các phân tử khí theo tốc độ), phân bố Planck (bức xạ lượng tử theo tần số của chúng), phân bố Fermi (electron theo năng lượng).

Bây giờ, sau khi đã học được ý nghĩa của các hàm phân phối, chúng ta hãy giải một hàm hữu ích bài toán, với tốc độ không đổi $u$. Có thể chứng minh rằng trong trường hợp này, bất kể tốc độ ban đầu của những giọt nhỏ bị đẩy ra là bao nhiêu thì chúng đều nhanh chóng bị hút vào tốc độ ngang $u$ và tốc độ dọc $v = a r^2$. Vì cả hai chuyển động của giọt nước - rơi và bị gió cuốn đi - đều giống nhau nên tất cả các giọt sẽ chuyển động theo đường thẳng (hình 4).

Thời gian di chuyển tới mặt đất càng dài, bán kính rơi càng nhỏ: $t(r) = \frac{h}{v(r)} = \frac{h}{a r^2}$, do đó những giọt nhỏ (bán kính $r_1$) sẽ rơi xuống đất đối với nguồn này so với những giọt lớn hơn (bán kính $r_2 > r_1$):

$$x(r) = u \cdot t(r) = u \frac{h}{a r^2}.$$ (4)

Tất cả các giọt sẽ rơi ở khu vực nào $\Delta x$, bán kính của chúng khác với bán kính $r$ đã cho một lượng nhỏ $\Delta r$? Vì, như có thể thấy từ (4), $\Delta x / \Delta r = -\left(u \frac{2h}{a}\right) \frac{1}{r^3}$ (chúng tôi đã tiếp tục lấy đạo hàm hàm $x(r)$),

$$\Delta x = -\left(u \frac{2h}{a}\right) \frac{1}{r^3} \cdot \Delta r$$

(dấu trừ chuẩn bị cho một sự thật mà chúng ta đã biết: nếu bán kính giọt nước lớn hơn $r$ ($\Delta r > 0$) thì nó sẽ rơi gần nguồn hơn ($\Delta x < 0$) và ngược lại).
