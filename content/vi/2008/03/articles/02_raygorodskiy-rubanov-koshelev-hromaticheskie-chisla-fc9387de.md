---
id: 2008-3-raygorodskiy-rubanov-koshelev-hromaticheskie-chisla-fc9387de
issue: kvant_2008_3
year: 2008
number: "3"
title: số màu
authors:
  - Райгородский А. М.
  - Рубанов О. И.
  - Кошелев В. А.
rubric: osnovnye-stati
page_first: 15
page_last: 22
page_labels: 13, 20
tag: BQTO
lang: vi
source: kvant_digital
extraction: native
content_sha256: 4e3fc2b6e9591d9eb2a086b5d0bb84f622076ad40119ba01aa94a352769abafd
prompt_sha256: draft-1
translated_from: content/ru/2008/03/articles/02_raygorodskiy-rubanov-koshelev-hromaticheskie-chisla-fc9387de.md
source_content_sha256: 7961fb88bf23dfdcba543d9ead0d81329f13e31870d1d26c7df185cf64656664
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 13⟧

số màu

A.RAIGORODSKY, O.RUBANOV, V.KOSHELEV

Giới thiệu và dàn dựng bài toán

Toán học hiện đại là một ngành khoa học gần như vô biên. Để trở nên quen thuộc một cách hời hợt với vô số phần của nó, phải mất nhiều năm và để hiểu tất cả bài toán nảy sinh trong toán học ở những thời điểm khác nhau sẽ không đủ trong vài kiếp. Tuy nhiên, trong vùng biển vô tận bài toán này cũng có những “ngọn hải đăng” nguyên bản - bài toán, trong nhiều năm đã quyết định sự phát triển của các khu vực mà chúng xuất hiện. Những đèn hiệu này giúp nhà toán học chọn đúng hướng chuyển động. Một trong những tín hiệu này là bài toán về số màu - đó là điều mà chúng ta sẽ nói đến trong bài viết này. Nó thuộc về một trong những phần phổ biến nhất và theo ý kiến ​​của chúng tôi, một trong những phần hay nhất của toán học - phần mà ngày nay thường được gọi là hình học tổ hợp. Về cơ bản, hình học tổ hợp là khoa học về các tính chất tổ hợp của các đối tượng hình học. Nó đã trở thành một môn học độc lập chỉ trong thế kỷ 20, và cần lưu ý rằng các số màu đã đóng góp rất nhiều vào việc này. Cái này bài toán: số lượng màu tối thiểu cần thiết để tô màu mặt phẳng như vậy là bao nhiêu (chúng ta sẽ gọi nó là thông thường) sao cho khoảng cách giữa các điểm cùng màu không thể bằng 1? Chúng ta sẽ gọi số lượng màu nhỏ nhất được đề cập là màu sắc $числом.^{1}$ Thoạt nhìn, câu hỏi vừa đặt ra là hoàn toàn cơ bản, nhưng dần dần chúng ta sẽ tin rằng câu hỏi này rất sâu sắc và không hề tầm thường. Trước hết, tôi muốn hiểu “tô màu mặt phẳng” là gì. Chắc chắn người đọc thiếu kinh nghiệm sẽ ngay lập tức tưởng tượng ra điều gì đó giống như những gì được mô tả trong hình 1. Tuy nhiên, còn nhiều điều hơn thế nữa

⟦figure⟧

Hình 1

những tình huống khó khăn. Ví dụ: giả sử một điểm x trên mặt phẳng có tọa độ $x_{1}, x_{2}$ (sau này chúng ta sẽ viết $x = ( x_{1}, x_{2} ) ).$ Giả sử điểm đó là “màu xanh” nếu các số $x_{1}, x_{2}$ là số hữu tỉ; nếu không thì

1 Từ "màu sắc" có nguồn gốc từ Hy Lạp. Nó thực sự được dịch là “có màu” hoặc “có màu”.

⟦column⟧

Hãy gọi điểm đó là “màu đỏ”. Một bức tranh hai màu về chiếc máy bay xuất hiện, không thể vẽ dễ dàng như vậy được. Rõ ràng cũng cần nhắc lại rằng khoảng cách |x – y| giữa các điểm $x = ( x_{1}, x_{2} )$ và $y = ( y_{1}, y_{2} )$ trên mặt phẳng thường được tìm bằng công thức x - y =

$( x_{1} - y_{1} )^{2} + ( x_{2} - y_{2} )^{2}$.

Hãy đồng ý về ký hiệu. Trong toán học, mặt phẳng thường được ký hiệu bằng ký hiệu $R^{2}$. Đồng thời, từ "chrome" trong tiếng Hy Lạp bắt đầu bằng chữ cái $\chi$ ("hi"). Vì vậy, đối với số màu

( ) ký hiệu $\chi R^{2}$ được thông qua. Cuối cùng là lịch sử ngắn gọn của bài toán. Nó được dàn dựng vào năm 1950 bởi E. Nelson, lúc đó mới 17 tuổi. Điều này rất gây tò mò và sẽ truyền cảm hứng cho độc giả trẻ: nếu Nelson mười bảy tuổi có thể đặt ra một câu hỏi quan trọng như vậy đối với sự phát triển của khoa học, thì tại sao tôi, độc giả lại không dám? bài toán rất giống nhau đã được nhà hình học nổi tiếng G. Hadwiger xem xét vào những năm 40 của thế kỷ 20; tuy nhiên, trước hết, Nelson không biết về điều này, và quan trọng nhất, chính ông là người đưa ra cách giải quyết vấn đề hiện đại - về mặt chất tạo màu. bài toán Các ấn phẩm của Nelson của M. Gardner, P. Erdős và cùng G. Hadwiger đã mang lại sự nổi tiếng to lớn. Bạn có thể tìm thấy một tiểu luận lịch sử rất thú vị về chủ đề này trong ghi chú của A. Soifer ([1]); Ngoài ra còn có một tập tài liệu của A.M. Raigorodsky [2] và bài viết của ông [3]. Chúng ta sẽ chuyển sang nghiên cứu về số màu.

Một cuộc rút lui nhỏ

Như chúng ta đã biết, bài toán của Nelson bao gồm việc vẽ một mặt phẳng một cách chính xác bằng cách sử dụng lượng sơn ít nhất trong “bảng màu”. Chúng ta vẫn còn thời gian để xem bài toán này khó khăn như thế nào. Do đó, điều hợp lý là trước tiên bạn nên thử dùng lời giải, tương tự như bài toán đối với trường hợp đường thẳng thông thường. Tranh thẳng thích hợp là gì? Vâng, nói chung, điều tương tự như trước: bạn chỉ cần yêu cầu các điểm (số) cùng màu x, y không cách nhau một khoảng cách bằng 1, tức là sao cho giá trị |x – y| không bằng một. Rõ ràng, nếu bạn vẽ một đường thẳng một màu thì sẽ có rất nhiều chữ “X” và “I” vi phạm điều kiện trên. Điều này có nghĩa là để vẽ một đường thẳng đúng cách, bạn cần ít nhất hai màu. Trên hình 2 bức tranh như vậy được chỉ định rõ ràng.

⟦folio 20⟧

KVANT 2008/№3

vim $v_{3}$ (hình21, c), bằng cách sử dụng $v_{3}$ và $u_{5}$, chúng tôi sẽ tạo lại $v_{2}$ (hình21, d) và sử dụng $v_{2}$ và w, chúng tôi sẽ tạo lại $v_{1}$ (hình21, d). Độ dài của đoạn $v_{1} v_{5}$ bằng 0,98... Đây gần như là sự thống nhất, tuy nhiên cạnh $v_{1} v_{5}$ không nằm trong bất kỳ biểu đồ khoảng cách nào trên tập hợp các đỉnh hiện có. Tuy nhiên, điều sau đây là đúng. Bạn có thể “di chuyển” điểm $v_{5}$ theo cách như vậy, giữ khoảng cách giữa điểm đó và điểm y bằng 1, do kết quả của các công trình xây dựng tương tự như những công trình được thực hiện ở trên (xem hình21), một biểu đồ khoảng cách $G_{2}$ trên hình 22 xuất hiện, trong đó với cạnh $v_{1} v_{5}$ tất cả

⟦figure⟧

Hình 22

theo thứ tự. Tính toán cho thấy tọa độ “đúng” của điểm $v_{5}$ là (0,3..., 0,285...). Chúng tôi để việc chứng minh thực tế mà chúng tôi đã đưa ra, cũng như tất cả các tính toán kèm theo, nằm ngoài phạm vi của bài viết này. Chúng khá mang tính chất kỹ thuật (xét cho cùng, có thể tìm thấy tọa độ của tất cả các điểm, nếu cần, với bất kỳ độ chính xác nào được xác định trước) và để hiểu ý nghĩa của việc xây dựng, sự rõ ràng của hình cuối cùng là khá đủ. Đặc biệt có thể thấy đồ thị $G_{2}$ có ​​mười bốn đỉnh, hai mươi ba cạnh và không chứa hình tam giác. Hãy xoay toàn bộ cấu trúc $G_{2}$ 90 độ quanh tâm hình vuông. Kết quả là đồ thị $G¢_{2}$. Âm lượng

⟦column⟧

Tiếp theo là gì?

Thực ra mọi chuyện chỉ mới bắt đầu với kết quả của O’Donnell và Hochberg. Đầu tiên, có thể lưu ý rằng, khi chứng minh kết quả này, chúng ta chỉ chú ý đến những đoạn đơn lẻ mà chúng ta cần để chứng minh cho bất đẳng thức $\chi ( G )$ ³ 4. Tam giác không hình thành từ chúng, và điều đó thật tuyệt. Trên thực tế, các cạnh khác có thể xuất hiện trên 23 đỉnh, vì vậy nếu chúng ta cố gắng xem xét tất cả chúng, thì số màu tất nhiên sẽ không trở nên nhỏ hơn, nhưng tất nhiên, các hình tam giác có thể xuất hiện. Vì không muốn bận tâm đến các cạnh bổ sung (có thể) mà chúng tôi đã đưa ra giả định thích hợp về định nghĩa của biểu đồ khoảng cách. Trên thực tế, kết quả của đoạn trước vẫn có giá trị ngay cả khi không có giả định này. Việc chứng minh chỉ trở nên khó khăn hơn một chút về mặt kỹ thuật. Thú vị

Hình 23

Vẽ cột $G_{2}$ Và $G¢_{2}$ (không thêm các cạnh mới), cuối cùng chúng ta tạo thành biểu đồ $G_{3}$ có hai mươi ba đỉnh và bốn mươi hai cạnh. (Ở đây 23 = 14 + + 14 – 5, vì các đỉnh của hình vuông và tâm của nó vẫn giữ nguyên khi quay; tương tự, 42 = = 23 + 23 – 4, trong đó 4 là số cạnh của hình vuông.) Một phép kiểm tra nhàm chán cho thấy rằng $G_{3}$ trông giống hệt như trong hình hình 23. Không có hình tam giác nào trong đó cả. Chẳng phải nó phức tạp hơn trục xoay nhiều sao? Vâng, đó là cái giá phải trả cho việc thiếu hình tam giác. Bây giờ chúng ta hãy chứng minh điều đó $\chi ( G_{3} )$ ³ 4. Thật vậy, giả sử các đỉnh của đồ thị $G_{3}$ được sơn đúng ba màu (các đỉnh nối với nhau bằng một cạnh có nhiều màu). Hãy gọi các màu là đỏ, vàng và xanh lục. Rõ ràng là các điểm y và w có cùng màu hoặc các điểm x và z có cùng màu. Hãy xem xét trường hợp đầu tiên. Chúng ta có quyền tin rằng y và w chẳng hạn, có màu đỏ. Giả định $u_{5}$, ngược lại, không phải màu đỏ - giả sử nó có màu vàng. Thế thì bằng mọi cách $u_{1}$ màu xanh lá cây (do xương sườn $wu_{1}, u_{5} u_{1} ), u_{2}$ màu vàng (sườn $u_{1} u_{2}$ Và $yu_{2} ), u_{3}$ xanh (sườn $u_{2} u_{3}$ Và $wu_{3} )$ Và $u_{4}$ màu vàng (xem hình20, f). Vì vậy, vì những lý do tương tự $u_{5}$ xanh và nảy sinh mâu thuẫn. Vì vậy, các đỉnh của $u_{5}, w$ màu đỏ. Chúng ta hãy nhìn vào hình ngũ giác $v_{1} v_{2} v_{3} v_{4} v_{5}$. đỉnh $v_{1}$ được nối bởi một cạnh với w, và do đó nó không có màu đỏ. Giữa những đỉnh cao $v_{2}$ Và $u_{5}$ cạnh cũng đi qua và điều này không cho phép $v_{2}$ có màu đỏ. Lập luận tương tự cho thấy ba đỉnh còn lại của hình ngũ giác phải có màu vàng hoặc xanh lục. Vì vậy, hình ngũ giác được sơn hai màu. Nhưng điều này rõ ràng là không thể, và chúng tôi mâu thuẫn với tính đúng đắn của bức tranh gốc. Trường hợp các điểm x và z có cùng màu được xử lý theo cùng một cách (đây là lý do tại sao chúng tôi thực hiện phép quay). Như vậy, $\chi ( G_{3} )$ ³ 4, và mẹo nằm trong túi: đếm $G_{3}$ - được săn lùng. Lưu ý là không khó để tô màu $G_{3}$ tất nhiên là có bốn màu $\chi ( G_{3} ) = 4$.
