---
id: 1989-6-tihomirov-50-let-lineynomu-programmirovaniyu-5aa63db5
issue: kvant_1989_6
year: 1989
number: "6"
title: 50 năm lập trình tuyến tính
authors:
  - Тихомиров В. М.
rubric: osnovnye-stati
page_first: 11
page_last: 16
page_labels: 9, 10, 12, 13, 14
tag: X33E
lang: vi
source: kvant_digital
extraction: vision
content_sha256: d2ec7ae4346d8968173815e4abf5bee8f8ac60c58af4537e4eff6631171d92a2
prompt_sha256: draft-1
translated_from: content/ru/1989/06/articles/04_tihomirov-50-let-lineynomu-programmirovaniyu-5aa63db5.md
source_content_sha256: 96a8bc57c1d4c96e32ab3a3dd7efca5da57a091acffbba9c1d3e2784ff61d851
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 9⟧

Năm 1975, nhà toán học Liên Xô L. V. Kantorovich và nhà kinh tế học người Mỹ T. Koopmans được trao giải Nobel.

Những giải thưởng này được đặt theo tên người sáng lập, nhà hóa học và nhà phát minh nổi tiếng Alfred Nobel. Theo Nobel, họ được trao cho những khám phá khoa học trong lĩnh vực vật lý, hóa học, sinh lý học hoặc y học, cho những tác phẩm văn học “phản ánh lý tưởng của nhân loại”, cũng như cho những người “sẽ đóng góp đáng kể vào sự đoàn kết các dân tộc, phá hủy công việc, giảm số lượng quân đội hiện có và các hiệp định hòa bình chung”. Giải thưởng không dành cho các nhà toán học. Tuy nhiên, vào năm 1969, Ngân hàng Thụy Điển, nhân dịp kỷ niệm 300 năm thành lập, đã thành lập một giải thưởng để tưởng nhớ A. Nobel - về khoa học kinh tế. Nó được trao vào năm 1975 cho L.V. Kantorovich và T. Koopmans vì đã tạo ra một lý thuyết toán học mới (được gọi là quy hoạch tuyến tính) và ứng dụng lý thuyết này vào kinh tế học.

Trong chữ ký gửi tới Ủy ban Nobel, Leonid Vitalievich Kantorovich nói về trải nghiệm của mình vào năm 1939. Ông, một giáo sư toán học 26 tuổi, đã được các nhân viên của phòng thí nghiệm của ủy thác ván ép tiếp cận để xin lời khuyên, nơi cần quyết định bài toán về sự phân bổ vật liệu cao nhất giữa các máy. bài toán này trùng hợp với việc tìm giá trị lớn nhất của hàm tuyến tính xác định trên một đa giác. Hàm như vậy đạt được mức tối đa ở một đỉnh, nhưng số đỉnh trong bài toán này đã lên tới một tỷ... Do đó, việc liệt kê các đỉnh đơn giản là không phù hợp.

Leonid Vitalievich đã viết:

"Hóa ra bài toán này không phải ngẫu nhiên. Tôi phát hiện ra một số lượng lớn bài toán, đa dạng về nội dung, có tính chất toán học tương tự: sử dụng trái cây gieo tốt hơn, lựa chọn thiết bị bốc xếp, định vị cắt nguyên liệu, sử dụng nguyên liệu thô, phân bổ luồng giao thông vận tải... Điều này thực sự thôi thúc tôi tìm kiếm một phương pháp hiệu quả cho lời giải của họ".

Và vào mùa hè năm 1939, cuốn sách “Các phương pháp tổ chức và lập kế hoạch sản xuất bằng toán học” của L. V. Kantorovich đã được xuất bản, trong đó có nền tảng của cái gọi là kinh tế toán học.

Để hiểu toán học bài toán, trong đó toán học có thể cung cấp sự trợ giúp đáng kể, hãy bắt đầu bằng một ví dụ - chính là ví dụ mà Leonid Vitalievich bắt đầu cuốn sách của mình.

Giả sử công việc yêu cầu sản xuất số lượng lớn nhất các bộ gồm hai phần. Có ba loại máy I, II và III, chi tiết được nêu trong bảng.

“Phân phối tự nhiên” được sử dụng trong thực tế là mỗi nhóm máy tạo ra số lượng bộ lớn nhất. Máy loại thứ nhất có thể sản xuất 20 bộ (ví dụ như thế này: máy thứ nhất và máy thứ hai, mỗi máy sản xuất 10 bộ phận thứ nhất, còn máy thứ ba - 20 bộ phận thứ hai) và không thể sản xuất thêm. Số 36 có ý nghĩa tương tự đối với máy loại thứ hai: máy thứ nhất chỉ sản xuất

⟦folio 10⟧

đối với phần đầu tiên, phần thứ hai - chỉ phần thứ hai và phần thứ ba - 4/5 thời gian tạo ra phần đầu tiên và 1/5 thời gian - phần thứ hai. Tương tự như vậy đối với máy loại thứ ba.

Như có thể thấy từ bảng, sự phân bổ tối ưu mang lại lợi ích đáng kể - 9 hiệp bổ sung! - không cần thêm chi phí.

Để tìm ra phân phối không hề tối ưu, chúng ta cần dịch bài toán sang ngôn ngữ toán học. Vì vậy, chúng tôi có sẵn bảy máy - máy thứ nhất, thứ hai và thứ ba tạo thành loại thứ nhất, máy thứ tư, thứ năm và thứ sáu - loại thứ hai và cuối cùng, loại thứ bảy - loại thứ ba. Cần chỉ ra khoảng thời gian mà mỗi máy phải sản xuất bộ phận thứ nhất và thứ hai. Gọi $\alpha_i$ là khoảng thời gian mà máy thứ $i$ sẽ sản xuất phần đầu tiên và $\alpha'_i$ là phần thời gian nó sẽ làm việc ở phần thứ hai. Sau đó $\alpha_i \geq 0$, $\alpha'_i \geq 0$, $\alpha_i + \alpha'_i \leq 1$, $i = 1, 2, \dots, 7$. Số chi tiết đầu tiên được máy làm ra sẽ bằng

$$10(\alpha_1 + \alpha_2 + \alpha_3) + 20(\alpha_4 + \alpha_5 + \alpha_6) + 30\alpha_7.$$

Tương tự, số phần thứ hai bằng

$$20(\alpha'_1 + \alpha'_2 + \alpha'_3) + 30(\alpha'_4 + \alpha'_5 + \alpha'_6) + 80\alpha'_7.$$

Số lượng phần thứ nhất và thứ hai phải giống nhau và càng lớn càng tốt. Vì vậy, chúng tôi đi đến bài toán:

tìm số lớn nhất $s$ sao cho

$$s = 10(\alpha_1 + \alpha_2 + \alpha_3) + 20(\alpha_4 + \alpha_5 + \alpha_6) + 30\alpha_7,$$

và thay thế nó vào biểu thức cho $s$. chúng tôi nhận được

$$s = \frac{230}{3} + \left(20 - \frac{50}{3}\right)y + \left(30 - \frac{110}{3}\right)z = \frac{230}{3} + \frac{10}{3}y - \frac{20}{3}z.$$

Bây giờ rõ ràng là giá trị lớn nhất của tổng sẽ đạt được khi $y = 3,$

⟦folio 12⟧

kah cũng trông như thế này:

$$\begin{cases}
s = 10x + 20y + 30z, \\
10x + 20y + 30z \geq 20(3-x) + 30(3-y) + 80(1-z), \\
20(3-x) + 30(3-y) + 80(1-z) \geq 10x + 20y + 30z, \\
x \geq 0, 3 \geq x, y \geq 0, 3 \geq y, \\
z \geq 0, 1 \geq z.
\end{cases}$$

“Khối đa diện” được xác định bởi hệ bất đẳng thức được mô tả bằng cùng màu tại hình 1 - nó trùng với một hình phẳng. Đỉnh mà hàm s đạt cực đại được tô màu đỏ.

L. V. Kantorovich đã đề xuất một số cách tiếp cận đối với công thức chung lời giải bài toán. Một trong số đó dựa trên ý tưởng về tính hai mặt. Để hiểu nó, hãy giải bài toán về máy công cụ theo một cách khác.

Một lần nữa, chúng ta biểu thị $\alpha_1 + \alpha_2 + \alpha_3$ là $x$, $\alpha_4 + \alpha_5 + \alpha_6$ là $y$ và $\alpha_7$ là $z$; Hãy để chúng tôi giới thiệu các ký hiệu mới: $x' = \alpha'_1 + \alpha'_2 + \alpha'_3$, $y' = \alpha'_4 + \alpha'_5 + \alpha'_6$, $z' = \alpha'_7$. Chúng ta hãy liên kết từng bộ $(x, y, z, x', y', z')$, trong đó tất cả các số đều không âm và liên quan bởi các bất đẳng thức

$$x + x' \leq 3, y + y' \leq 3, z + z' \leq 1,$$

(1) một điểm trong mặt phẳng $(a; b)$ có tọa độ $a = 10x + 20y + 30z$, $b = 20x' + 30y' + 80z'$. (2)

Tập $C$ của tất cả các điểm được cho bởi quan hệ (1) và (2) là gì? Bộ này là tổng của ba bộ: $C_1$, được hình thành bởi các điểm $(a; b)$ mà $a = 10x, b = 20x'$; $C_2$, bao gồm các điểm $(a; b)$, trong đó $a = 20y$, $b = 30y'$; $C_3$, bao gồm các điểm $(a; b)$, trong đó $a = 30z, b = 80z'$. Tất nhiên, trong trường hợp này, bất đẳng thức (1) được thỏa mãn. Các bộ $C_1, C_2$ và $C_3$ là các hình tam giác được hiển thị trong hình 2.

Để xây dựng tập hợp yêu cầu $C$, trước tiên chúng ta tìm tổng $C_1$ và $C_2$, tức là tập hợp các điểm $(a; b)$ có tọa độ

$$a = 10x + 20y, b = 20x' + 30y'.$$

Để làm điều này, tam giác $C_2$ được đặt ra khỏi đỉnh trên của tam giác $C_1$, sau đó $C_2$ “trượt xuống ngọn đồi” được tạo thành bởi cạnh huyền $C_1$. Kết quả là một hình tứ giác như trong hình 3.

Bây giờ chúng ta có thể xây dựng tập $C$. Hãy di chuyển hình tam giác $C_3$ từ đỉnh trên cùng đến hình 3 và để nó “trượt xuống ngọn đồi” được tạo thành bởi đường gãy hai liên kết. Điều này tạo ra hình ngũ giác $C$ được hiển thị trong hình 4.

Yêu cầu gì trong bài toán? Cần phải tìm điểm $A = (a; b)$ sao cho thứ nhất là $a = b$ và thứ hai là $a$ có giá trị cao nhất. Điểm này nằm ở giao điểm của đường phân giác và đường gãy $KLMN$ (xem hình 4) và có tọa độ $(86^2/3, 86^2/3)$.

Làm cách nào để thêm vào điểm $A$? Hãy tiếp cận nó từ cả hai phía. Chúng ta hãy bước một bước dọc theo đoạn $KL$ từ điểm $K$ đến điểm $L$. Đồng thời, chúng tôi sẽ tăng thêm 80 đơn vị. Điều này tương ứng với thực tế là máy hình tam giác phải tạo ra các bộ phận 80 giây. Tiếp theo chúng ta sẽ thực hiện một bước từ điểm $N$ đến điểm $M$. Đồng thời, chúng ta sẽ ngạc nhiên về phía bên phải 60 đơn vị. Cái này

⟦folio 13⟧

tương ứng với thực tế là máy loại thứ hai chỉ hoạt động được trên các bộ phận đầu tiên và tạo ra 60 bộ phận trong số đó.

Và bây giờ chúng ta chuyển từ $L$ sang $A$ và từ $M$ sang $A$. Điều này tương ứng với thực tế là chiếc máy đầu tiên hoạt động $2^2/3$ trong tổng số ba đơn vị thời gian ở phần đầu tiên (và chúng ta di chuyển lên bên phải $26^2/3$) và $1/3$ thời gian ở phần thứ hai (và chúng ta di chuyển lên $6^2/3$). Kết quả là chúng ta đạt được điểm $A$.

Nhân tiện, chúng ta sẽ thấy rõ phải làm gì nếu chúng ta không có ba mà là $n$ loại máy. Khi đó, tập hợp $n$ sẽ là một đa giác giới hạn của các liên kết $C$, các góc nghiêng của chúng sẽ được sắp xếp từ điểm dưới lên điểm trên theo thứ tự giảm dần. Và một lần nữa chúng ta cần đi từ điểm trên và điểm dưới về phía nhau. Tất cả các loại máy, ngoại trừ một loại, sẽ chỉ xử lý một phần - “trên” - phần thứ nhất, “dưới” - phần thứ hai. Và chỉ đến phần cuối cùng một loại máy mới phải “chia sẻ” - một phần thời gian để xử lý phần đầu, một phần thời gian để xử lý phần thứ hai.

Trong lời giải thứ hai của chúng tôi, vai trò chính được thực hiện bởi các đường thẳng mà trên đó bộ ngắt liên kết KLMN nằm. Theo thuật ngữ chung nhất, ý tưởng về tính đối ngẫu là một khối đa diện có thể được định nghĩa là một tập hợp các đỉnh của nó hoặc là giao điểm của một tập hợp các nửa không gian chứa nó.

Sau khi chính thức hóa đạo hàm bài toán và chỉ ra một số lời giải, L. V. Kantorovich cũng nhìn thấy những triển vọng tuyệt vời trong lĩnh vực kinh tế. Hãy tưởng tượng bạn ở vị trí của một quản đốc có bảy công nhân dưới quyền. Chúng hoạt động trên chính những chiếc máy mà chúng tôi đã gặp nhiều lần. Bạn phải tổ chức sản xuất theo cách sao cho sản xuất được càng nhiều bộ phận càng lớn càng tốt.

Một cách là chỉ thị. Người quản đốc gọi một đội và ra lệnh bằng cái đầu của mình: “Bạn, Peter, hãy tạo phần thứ hai trên máy loại thứ ba; Ivan, Nikolay và Alexander - tạo phần đầu tiên trên máy loại thứ nhất”, v.v.

Nhưng có một cách khác, tế nhị hơn. Bạn có thể gọi cho một nhóm và nói: "Các bạn, các bạn cần chế tạo hai loại bộ phận trên máy của mình. Loại thứ nhất có giá 2 rúp và loại thứ hai có giá 1 rúp; đối với mỗi bộ gồm hai loại bộ phận - tiền thưởng 10 kopecks. Hãy nghĩ về cách bạn có thể kiếm được nhiều tiền hơn."

Có lẽ lựa chọn đầu tiên xuất hiện trong đầu người lao động là cái được gọi là “phân phối tự nhiên” trong bảng của chúng ta. Đồng thời, họ sẽ kiếm được 238 rúp 70 kopecks. Nhưng rồi họ

⟦folio 14⟧

có lẽ đồng ý rằng có một cách có lợi hơn - "phân phối tối ưu".

Câu hỏi: Số tiền tối đa mà một lữ đoàn có thể kiếm được là bao nhiêu?

Giá các bộ phận đến từ đâu? Nhìn vào hình 4. Đường thẳng LM chứa điểm tối ưu A có phương trình 2a+b=260. Hệ số 2 và 1 của nó là giá. Nếu không có phí bảo hiểm cho sự hoàn thiện, thì với giá cho các phần 2 và 1 rúp, thu nhập lớn nhất của phi hành đoàn sẽ đến từ bất kỳ điểm nào trên phân khúc ML. Và một khoản phí bảo hiểm nhỏ 10 kopecks khiến điểm A có lợi nhất. Đây là nghệ thuật chọn giá đúng!

Nhưng chúng ta hãy quay trở lại năm 1939. Người ta nói rằng sự thật được phân phối như dị giáo... Than ôi, đây cũng là một sự tình cờ với những ý tưởng của L. V. Kantorovich trong lĩnh vực kinh tế. Họ không đáp ứng được khái niệm vào thời điểm thành lập, bị tuyên bố là dị giáo, và tác phẩm của ông đã bị cải đạo.

Các khái niệm của Leonid Vitalievich đã được khám phá lại ở phương Tây ngay sau khi chiến tranh kết thúc. Nhà kinh tế học người Mỹ T. Koopmans trong nhiều năm đã thu hút sự chú ý của các nhà toán học về một số bài toán liên quan đến chủ đề quân sự. Ông đã tích cực đóng góp vào việc thành lập một nhóm toán học để phát triển những vấn đề này. Kết quả là người ta nhận ra rằng cần phải học cách giải bài toán về việc tìm cực trị của hàm tuyến tính trên khối đa diện xác định bởi bất đẳng thức tuyến tính. Theo gợi ý của Koopmans, nhánh toán học này được gọi là quy hoạch tuyến tính.

Nhà toán học người Mỹ D. Danzgg vào năm 1947 đã phát triển một phương pháp cụ thể rất hiệu quả về lập trình tuyến tính số lời giải bài toán (nó được gọi là phương pháp sumplex). Ý tưởng về quy hoạch tuyến tính lan truyền nhanh chóng khắp thế giới trong vòng 5 đến 6 năm, và chính Koopmans và Danzgg đã được biết đến rộng rãi khắp nơi.

Vào khoảng thời gian này, Koopmans biết được rằng ngay cả trước chiến tranh, một điều gì đó khác biệt đã được thực hiện ở nước Nga xa xôi.

tương tự như sự phát triển của sự khởi đầu của quy hoạch tuyến tính. Danzgg và Koopmans thật dễ dàng bỏ qua thông tin này! Một cuốn sách nhỏ, được xuất bản với số tiền không đáng kể, thậm chí không dành cho các nhà kinh tế, mà dành cho các nhà tổ chức sản xuất, với tối thiểu toán học, không có thuật toán được mô tả rõ ràng, không có định lý chứng minh - nói một cách dễ hiểu, đó là một cuốn sách đáng được tính đến... Nhưng Koopmans nhất quyết yêu cầu dịch và xuất bản cuốn sách của Kantorovich ở phương Tây. Tên và ý tưởng của anh ấy được mọi người biết đến. Chúng ta hãy tri ân sự cao quý của nhà khoa học Mỹ!

Và bản thân Leonid Vitalievich - lẽ ra phải tự nhiên biết bao đối với anh ta, sau khi trải qua những cú sốc đầu tiên của sự thụt lùi, từ bỏ “tội lỗi” của tuổi trẻ, quên đi tất cả những điều kinh tế học này và quay trở lại với toán học. Nhưng L. V. Kantorovich vẫn tiếp tục viết các công trình toán học dựa trên các ý tưởng kinh tế một cách rõ ràng và cũng tham gia vào những phát triển cụ thể trong sản xuất. Đồng thời (đồng thời với Danzgg, nhưng không biết công việc của anh ấy), ông đã phát triển một phương pháp, sau này được gọi là phương pháp đơn giản sửa đổi. Ngay khi một khoảng trống nhỏ hình thành vào những năm 50 và một số điều bị cấm trước đây trở thành hiện thực, ông đã tổ chức một nhóm sinh viên Khoa Kinh tế của Đại học bang Leningrad nghiên cứu phương pháp lập kế hoạch tối ưu. Và năm 1960 bắt đầu, Leonid Vitalievich chỉ giải quyết vấn đề kinh tế và các vấn đề toán học liên quan. Sự tham gia của ông vào các lĩnh vực này đã được trao Giải thưởng Lênin năm 1965 (được trao cho ông cùng với V.S. Nemchinov và V.V. Novozhilov) và, như đã đề cập, giải Nobel năm 1975.
