---
id: 1975-10-manevich-slutskin-evm-v-konstruktorskom-byuro-e7f6965e
issue: kvant_1975_10
year: 1975
number: "10"
title: Máy tính tại phòng thiết kế
authors:
  - Маневич М. А.
  - Слуцкин М. М.
rubric: raznoe
page_first: 26
page_last: 31
page_labels: 24-29
tag: DYOM
lang: vi
source: kvant_digital
extraction: vision
content_sha256: b1336e81384e0cf66fcb8887ebc97c4cf2e855d743c19c83248f7738543cdba6
prompt_sha256: draft-1
translated_from: content/ru/1975/10/articles/14_manevich-slutskin-evm-v-konstruktorskom-byuro-e7f6965e.md
source_content_sha256: 9fda681d8b29bcf7d0c6362d4a5a2ee25a129edba5dc4d52715dd60c209e4492
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 24⟧

Hiện nay, cùng với sự ra đời của máy vẽ được điều khiển bằng máy tính điện tử kỹ thuật số, đã nảy sinh khả năng thực sự về việc tự động hóa nhiều tác phẩm đồ họa được thực hiện tại các phòng thiết kế. Công việc như vậy bao gồm các bản vẽ quy trình của các bộ phận kỹ thuật cơ khí, sự phát triển bề mặt, hình ảnh đo trục (thể tích), v.v. Việc sử dụng máy vẽ tự động và máy tính cung cấp một dịch vụ vô giá cho các kỹ sư thiết kế phát triển các bản vẽ bề mặt của các dạng kỹ thuật.

Epirus Monge
Trước tiên chúng ta hãy giải thích cách xây dựng một bản vẽ hình chiếu.
Chúng ta hãy chọn hệ tọa độ Descartes hình chữ nhật $Oxyz$ trong không gian (Hình 1, a). Chúng ta hãy biểu thị tọa độ của mặt phẳng $xOy, xOz, yOz$ tương ứng bằng $H, V, W$ và chúng ta sẽ gọi chúng là các mặt phẳng chiếu.
Chúng ta hãy hạ chúng xuống từ một điểm tùy ý $A$ bên trong trị số octan đầu tiên $x \geq 0, y \geq 0, z \geq 0$ các đường vuông góc $Aa, Aa'$ và $Aa''$: a - ngang, a' - mặt trước, a' - hình chiếu biên dạng của điểm $A$. Bằng cách xoay các mặt phẳng $H$ và $W$ xung quanh trục $Ox$ và $Oz$, chúng ta kết hợp chúng với mặt phẳng $V$. Sau đó, trên một mặt phẳng $V$, chúng ta sẽ nhận được hình ảnh của hệ tọa độ không gian $Oxyz$ và các hình chiếu của điểm $A$ (Hình 1, 6; trong tương lai, chúng ta sẽ biểu thị các điểm không gian bằng chữ in hoa và các hình chiếu của chúng bằng cùng một chữ cái viết thường với số nguyên tố). Hình chiếu của các hình được xây dựng theo cách tương tự - có thể vẽ được các điểm.

Phân tích Hình 1, chúng ta đi đến kết luận rằng điểm $A$ của không gian được xác định hoàn toàn bởi hai thuộc tính, ví dụ: $a$ và $a'$. Cái này

⟦folio 25⟧

xuất phát từ thực tế là trục hoành $x = Oa_x$, tọa độ $y = a_x a'$ và áp dụng $z = a_x a'$ của nó được xác định duy nhất từ ​​bản vẽ. Vì vậy, để xác định một hình, chỉ cần có các hình chiếu của nó là đủ.

Bản vẽ thu được bằng phương pháp được mô tả được gọi là bản vẽ chiếu, sơ đồ Monge*) hoặc bản vẽ hoàn chỉnh.

Xây dựng đường giao nhau của các bề mặt

Nhà thiết kế đang đứng đằng sau cống. Anh ấy vẽ một hình ảnh của một số chi tiết. Ở một số nơi, bề mặt của bộ phận có các đường chuyển tiếp, gờ, lỗ và rãnh sắc nét. Ở đây xuất hiện trong hình ảnh vẽ của hai bề mặt hình trụ, được tạo thành giống như một bậc thang trong bộ phận. Nhà thiết kế ở lại. "Có chuyện gì thế?" - bạn hỏi. Nhà thiết kế cho biết: "Chúng ta lại chạm vào đường giao nhau, nhưng điều đó không thành vấn đề! Bây giờ, tôi sẽ xây dựng một số điểm thuộc về hai bề mặt và sau đó tôi sẽ vẽ một đường cong mượt mà xuyên qua chúng dọc theo mẫu". Và thế là các điểm riêng lẻ của các đường giao nhau bắt đầu xuất hiện trên bản vẽ.

Từ quan điểm của các phép toán đồ họa, xây dựng các đường giao nhau của một bề mặt cho đến việc tìm các điểm riêng lẻ của nó. Vì điều này

*) Gaspard Monge (1746-1818) - nhà hình học người Pháp.

Hình 2.

Các bề mặt dữ liệu $\Phi_1$ và $\Phi_2$ (Hình 2) phân tích bề mặt phụ thứ ba T (nếu các bề mặt giằng giao nhau thì hình cầu và mặt phẳng thường được sử dụng làm bề mặt phụ), sau đó xác định các đường giao nhau $m$ và $n$ của bề mặt phụ T với hai dữ liệu $\Phi_1$ và $\Phi_2$ và điểm giao nhau K của các đường đã dựng. Kỹ thuật này được lặp lại nhiều lần để các điểm thu được có thể được nối bằng một đường thẳng.

Ví dụ 1. Vẽ giao tuyến của hình cầu và hình nón thẳng đứng xác định trong hình chiếu (Hình 3).

Ta chọn mặt phẳng T tùy ý song song với mặt phẳng chiếu ngang. Mặt phẳng này cắt hình cầu và hình nón lần lượt dọc theo các đường tròn $m$ và $n$, giao nhau tại các điểm $K_1$ và $K_2$. Bằng cách dựng các đường tròn này trên mặt phẳng chiếu ngang, ta thu được điểm

⟦folio 26⟧

$k_1$ và $k_2$, thuộc hình chiếu ngang của các đường giao nhau (Hình 3). Các hình chiếu phía trước $k'_1$ và $k'_2$ của các điểm $K_1$ và $K_2$ sẽ trùng nhau trong trường hợp này. Sau khi thực hiện điều này cho một số mặt phẳng phụ song song với $T$, chúng ta thu được các điểm chung cho hình cầu và hình nón, đồng thời bằng cách kết nối chúng với các đường cong trơn trên mỗi hình chiếu, chúng ta thu được các hình chiếu gần đúng của các đường giao nhau. Càng vẽ nhiều điểm thì đường cong sẽ càng chính xác.

Nhưng dù chúng ta có cố gắng thế nào đi chăng nữa thì độ chính xác của những công trình như vậy vẫn bị hạn chế, kết quả là đường giao nhau không còn lý tưởng và thời gian sử dụng là rất đáng kể. Những thiếu sót này có thể được loại bỏ với sự trợ giúp của máy tính và máy vẽ. Thật vậy, một máy tính thực hiện hàng triệu hành động chỉ trong vài giây và một số máy vẽ hiện đại vẽ các đoạn thẳng dài hơn 300 mm trong một giây.

Khi tự động hóa quá trình xây dựng các đường giao nhau trong bản vẽ, các bước sau được thực hiện.

1) Các phương trình của các bề mặt xác định trong bản vẽ được viết.

2) Sử dụng máy tính, tọa độ $x$, $y$, $z$ của các điểm riêng lẻ của các đường giao nhau được xác định (theo quan điểm phân tích, việc xác định các đường giao nhau thuộc tính chất của hệ phương trình lời giải).

3) Tọa độ của các điểm thu được được đưa vào máy vẽ dưới dạng lệnh di chuyển bút đặc biệt.

Mỗi giai đoạn là một nhiệm vụ độc lập, đôi khi không hề dễ dàng. Chúng ta hãy giải thích chúng chi tiết hơn bằng ví dụ 2, tương tự như ví dụ 1. Để đơn giản cho việc suy luận sâu hơn, chúng ta chọn hệ tọa độ sao cho trục $Oz$ thẳng hàng với trục hình nón và trục $x$ đi qua tâm của hình cầu.

Ví dụ 2. Tên giao tuyến của hình cầu bán kính $r=50$, tâm

có tọa độ $x_0=30$, $y_0=0$, $z_0=0$ trong hệ tọa độ trực tiếp Cartesian $Oxyz$ và một hình nón tròn bên phải, đỉnh của nó nằm trên trục $Oz$ tại điểm $x_1=y_1=0$, $z_1=70$, trục trùng với trục $Oz$ và đường kính của đáy chạm vào hình cầu là 120 (dữ liệu này được lấy từ Hình 4, tỷ lệ được thể hiện trong hình).

Giai đoạn đầu tiên. Trước tiên chúng ta hãy xem xét một hình cầu có tâm ở gốc tọa độ và bán kính $r$ (Hình 5). Chúng ta hãy lấy một điểm tùy ý $M$ trên bề mặt của nó. Đặt tọa độ của nó là $x$, $y$, $z$. Không khó để chứng minh (sử dụng định lý Pythagore) rằng đối với điểm $M$ đẳng thức sau sẽ đúng:

$$x^2 + y^2 + z^2 = r^2.$$

Sự đẳng thức này được thỏa mãn bởi tọa độ của bất kỳ điểm nào nằm trên bề mặt hình cầu chứ không phải bởi tọa độ của các điểm không nằm trên bề mặt hình cầu. Sự bình đẳng này là phương trình của hình cầu.

⟦folio 27⟧

Hình 5.

Phương trình của một hình cầu có bán kính 50, tâm của nó cao hơn 30 đơn vị dọc theo trục $Ox$ (đây là hình cầu cho trong ví dụ 2), sẽ là

$$(x-30)^2+y^2+z^2=50^2.$$

Nó có thể được hiển thị rằng

$$x^2+y^2-\frac{1}{4}(z-70)^2=0$$

là phương trình của hình nón tròn bên phải được cho trong Hình 4. Đối với $z=z_0$ cố định, nó có dạng $x^2+y^2=\frac{(z_0-70)^2}{4}$ và xác định độ tròn - tiết diện của hình nón với mặt phẳng $z=z_0$.

Trong ví dụ này, chúng ta viết nhanh phương trình bề mặt do tính đơn giản của nó. Nhưng nói chung, phương trình của bề mặt xác định trong bản vẽ phải được suy ra. Đây là bài toán của giai đoạn đầu tiên.

Vậy ta có hệ phương trình sau:

$$\begin{cases}
x^2+y^2-\frac{1}{4}(z-70)^2=0, \\
(x-30)^2+y^2+z^2=50^2.
\end{cases}$$

Giai đoạn thứ hai. Chúng ta hãy trừ đi số thứ hai từ phương trình đầu tiên của hệ thu được. Sau khi biến đổi đơn giản, chúng ta thu được biểu thức

$$x=\frac{1}{48}z^2-\frac{7}{12}z-\frac{75}{12},$$

đó là phương trình hình chiếu trực diện của các đường giao nhau.

Phương trình (*) chỉ rõ parabol, một phần của nó được hiển thị trong Hình 4.

Bây giờ xem xét phép chiếu ngang, từ hệ thống chúng ta thu được:

$$x^2+y^2-\frac{1}{4}(V\sqrt{50^2-(x-30)^2-y^2}-70)^2=0.$$

Bạn không thể biết ngay phương trình này mô tả dòng nào.

Để xây dựng cả hai đường cong trên các hình chiếu, biến $z$ trong phương trình (*) sẽ được cung cấp các giá trị tuần tự (ví dụ: với bước $\Delta z=0,1$) trong giới hạn - 42,5 $\leq z \leq 46,5$ (các giới hạn này tương ứng với các điểm cực trị $1'$ và $2'$ trên hình chiếu chính diện, xem Hình 4). Đối với mỗi giá trị của biến $z$, trước tiên chúng ta tính giá trị của biến $x$ bằng công thức (*), sau đó (từ phương trình hình cầu) tìm giá trị $y$ bằng công thức

$$y=\pm \sqrt{50^2-z^2-(x-30)^2}.$$

Quá trình tính toán này được thực hiện dễ dàng trên máy tính. Như vậy, máy tính sẽ tính toán và in ra tọa độ $x, y, z$ của hơn 200 điểm giao nhau trong một khoảng thời gian ngắn. Các tọa độ này phải được gửi dưới dạng lệnh tới máy vẽ. Giai đoạn thứ ba bắt đầu.

Máy vẽ

Có nhiều loại máy vẽ khác nhau giao tiếp với máy tính theo những cách khác nhau. Các máy vẽ hiện đại (chúng thường được gọi là *máy chế tạo dây đeo*) như Itecan (Liên Xô), Benson (Pháp; xem Hình 6), Digigraph (Tiệp Khắc) có thể hoạt động từ cả băng giấy đục lỗ và băng từ mà máy tính cung cấp thông tin. Máy vẽ có thể được giao tiếp với máy tính thông qua kết nối thiết bị điện tử đặc biệt.

Hầu hết các máy vẽ hiện có đều được chế tạo bằng đường thẳng

⟦folio 28⟧

Hình 6.

nội suy tuyến tính và tròn. Điều này có nghĩa là nếu bạn chỉ định tọa độ của hai điểm $A$ và $B$ thì bút của máy vẽ có thể vẽ đoạn thẳng $AB$ hoặc cung tròn đi qua các điểm $A$ và $B$ (trong trường hợp này, tâm của nó được chỉ định thêm). Do máy tính tính toán tọa độ của một số điểm đủ lớn nên đường đứt nét được vẽ bằng bút của máy (sau đây gọi là dạng đoạn) hóa ra khá trơn tru.

Xây dựng hình ảnh aconometric

Khi thiết kế các khuôn khác nhau, không chỉ cần vẽ bản vẽ chiếu mà còn phải vẽ hình ảnh đo lường của bề mặt. Làm thế nào để dạy một máy vẽ vẽ một hình ảnh đo lường?

Hình 7 hiển thị hình ảnh của một điểm tùy ý $A$ trên trục đo hình học $Ox, Oy, Oz$. Điểm này có ba tọa độ và hình ảnh của nó được xây dựng theo các quy tắc hình học nhất định. Nhưng máy vẽ không biết những quy tắc này cũng như tọa độ hình học $x, y$ và $z$ là gì. Nó hoạt động trên hai trục, ví dụ $x'$ và $y'$. Một điểm tùy ý $A (x, y, z)$ có hai tọa độ dọc theo các trục này. Rõ ràng phải có sự liên hệ giữa các tọa độ $x'$

và $y'$ và tọa độ hình học $x, y, z$ cho một điểm tùy ý trên mặt phẳng. Kết nối này được biết đến và viết như sau:

$$x' = a_{11}x + a_{12}y + a_{13}z,$$
$$y' = a_{21}x + a_{22}y + a_{23}z,$$

(**)

trong đó $a_{ij} (i=1,2; j=1,2,3)$ là các số mang các giá trị nhất định cho một lựa chọn trục nhất định.

Ví dụ, đối với phép đẳng cự (trong trường hợp này các trục được vẽ theo các góc $120^\circ$ với nhau) các phương trình (**) có dạng sau:

$$x' = -\frac{\sqrt{3}}{2}x + \frac{\sqrt{3}}{2}y,$$
$$y' = -\frac{1}{2}x - \frac{1}{2}y + z.$$

Vì vậy, máy tính phải đọc lại tọa độ $x, y, z$ bằng các công thức (**) và gửi chúng theo trình tự yêu cầu đến máy vẽ để vẽ hình ảnh đo đạc.

Thi công phát triển bề mặt

Chúng ta hãy tưởng tượng các bề mặt như một màng cong linh hoạt nhưng không thể mở rộng. Có những bề mặt có thể bị biến dạng và thẳng hàng với mặt phẳng để không bị đứt hoặc gấp. Các bề mặt như vậy được gọi là các bề mặt khai triển và hình thu được sau khi kết hợp chúng với một mặt phẳng được gọi là khai triển.

⟦folio 29⟧

Hình 8.

Ý tưởng xây dựng đồ họa của sự phát triển bề mặt như sau: một bề mặt F đa dạng vừa khít với bề mặt, các mặt phẳng thường là hình tam giác. Sau đó, tất cả các khuôn mặt có kích thước thật sẽ được tạo trên mặt phẳng theo một trình tự nhất định.

Ví dụ 3. Xây dựng hình nón nghiêng có đáy tròn được xác định trong hình chiếu (Hình 8).

Chúng tôi tiến hành như sau. Chúng ta chia đáy của hình nón có các điểm $A_1, A_2, \dots$ thành $n$ các phần bằng nhau, ví dụ: thành 16 và nối chúng với đỉnh $S$. Khi đó trong hình vẽ chúng ta sẽ có hai hình chiếu của một paramid nghiêng (có các mặt hình tam giác) nội tiếp trong một hình nón. Bây giờ chúng ta cần xây dựng các mặt của paramid ở kích thước đầy đủ. Hãy xem xét khuôn mặt $SA_1A_2$. Hình chiếu ngang của nó sẽ là $s_a1a_2$, phía trước - $s'a'1a_2$. Dễ dàng nhận thấy $s'a'1$ là giá trị tự nhiên của cạnh $SA_1, a_1a_2$ là giá trị tự nhiên của cạnh $A_1A_2$. Để tìm kích thước tự nhiên của cạnh $SA_2$, chúng ta bao quanh trục tung đi qua đỉnh $S$, sao cho nó song song với mặt phẳng phía trước của hình chiếu $V$ ($s_a2$ trên hình chiếu ngang). Từ điểm kết quả $a_2$ chúng ta vẽ một đường nối cho đến khi nó giao với hình chiếu trực diện của đáy hình nón tại điểm $a_2'$ - $s'a'2'$ và kích thước tự nhiên của cạnh $SA_2$ sẽ là. Các cạnh của dòng $SA_3, SA_4$, v.v. cũng được tìm thấy tương tự.

Bây giờ, trên một tờ giấy riêng, chúng ta sẽ xây dựng mặt $SA_1A_2$ (Hình 9), gắn mặt $SA_2A_3$ vào đó, v.v. Kết quả là, chúng ta sẽ có được sự phát triển của một paramid nghiêng, đây sẽ là sự phát triển gần đúng của một hình nón nghiêng.

Khi số lượng mặt của paramid được ghi tăng lên, quá trình phát triển ngày càng trở nên chính xác hơn, nhưng việc xây dựng nó theo cách thủ công trên thực tế trở nên bất khả thi. Vị trí giảm do máy tính, theo một chương trình nhất định, sẽ tính toán tọa độ của điểm $A_1, A_2, A_3, \dots$ trong một hệ tọa độ nhất định và gửi chúng đến máy vẽ dưới dạng lệnh chuyển động của bút. Nếu có số lượng điểm lớn thì các đoạn của đường đứt nét sẽ nhỏ và đường do máy vẽ sẽ là một đường cong trơn.
