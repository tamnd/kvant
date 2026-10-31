---
id: 1984-12-toom-skolko-ploschadey-u-mnogougolnika-f67f7827
issue: kvant_1984_12
year: 1984
number: "12"
title: Một đa giác có bao nhiêu diện tích?
authors:
  - Тоом А. Л.
rubric: osnovnye-stati
page_first: 11
page_last: 14
page_labels: 9-12
tag: PFCS
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 3236f23835481e303938f4671e0506d5815a899455eec0a044744b71fd3fadb2
prompt_sha256: draft-1
translated_from: content/ru/1984/12/articles/03_toom-skolko-ploschadey-u-mnogougolnika-f67f7827.md
source_content_sha256: 9179597f28e74afde38a908ae8472d92b8ad37c454b86e6fcd0d2d016bfe73b1
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 9⟧

Một đa giác có bao nhiêu diện tích?

Ứng viên Khoa học Vật lý và Toán học
A. L. TOOM

Bài viết này không trình bày lý thuyết chung về diện tích mà chỉ nói về các cách tiếp cận khác nhau để xác định diện tích của một đa giác. Trong phần đầu tiên, chúng ta đang nói về một câu hỏi rất đơn giản (nhưng không ngờ tới đối với nhiều người!): liệu phép xác định diện tích của một hình tam giác và một đa giác lồi đã được huấn luyện có đúng không? Phần thứ hai thảo luận về khái niệm diện tích của đa giác "tự thay đổi giới tính"; hóa ra nó được kết nối với hai câu hỏi vật lý hoàn toàn khác nhau.

Diện tích của một tam giác và đa giác lồi

Mọi người đều biết rằng diện tích bằng một nửa tích chiều dài đáy và chiều cao. Nhưng trong một tam giác, một trong hai cạnh có thể được lấy làm đáy. Do đó, tam giác ở Hình 1 có ba diện tích:

$$S_1 = \frac{1}{2} ah_a, \quad S_2 = \frac{1}{2} bh_b, \quad S_3 = \frac{1}{2} ch_c,$$

trong đó $h_a, h_b, h_c$ lần lượt là độ dài của các độ cao được hạ xuống các cạnh có độ dài $a, b, c$. Bạn sẽ nói $S_1 = S_2 = S_3$? Vâng, đúng vậy. Tại sao? Bởi vì cả hai và hình thứ ba đều là hình tam giác có diện tích? Lập luận này không có tác dụng gì cả. Vì chúng ta đặt cùng tên “diện tích” cho ba giá trị nào đó nên chúng không nhất thiết phải bằng nhau. Ngược lại, đây là lý do tại sao chúng ta có thể gọi cả ba đại lượng viết cùng tên là “diện tích” vì chúng bằng nhau. Và rằng chúng bằng nhau - điều này phải được chứng minh.

Bài toán 1. Chứng minh rằng với mọi tam giác

$$ah_a = bh_b = ch_c.$$

Bài toán 2. Giáo sư Honsens đề xuất xem xét một giá trị mới - “đại lộ” của một hình tam giác, bằng tổng chiều dài đáy của nó và chiều cao hạ xuống đáy này. Theo đề xuất này, sự bình đẳng phải xảy ra (xem Hình 1)

$$a + h_a = b + h_b = c + h_c.$$

Điều này có đúng không? Đề xuất của giáo sư Honsens có hợp lệ không? (Đáp số cần phải được chứng minh.)

Hai bài toán được hiển thị minh họa khái niệm toán học quan trọng về tính đúng đắn của định nghĩa. Thường thì một thói quen sẽ thay thế một khái niệm và một bằng chứng, và chúng ta ngây thơ nghĩ rằng ý nghĩa của mỗi từ luôn giống nhau. Tuy nhiên, trong toán học, mọi thứ phải được chứng minh một cách nghiêm ngặt và nếu kết quả của hai phép tính khác nhau được gọi là giống nhau, thì điều đó không có nghĩa là chúng bằng nhau. Ngược lại, người ta phải chứng minh rằng chúng sẽ luôn bằng nhau thì mới có quyền gọi chúng là như nhau. Một định nghĩa mà công thức của nó cho phép thực hiện nhiều đường dẫn tính toán hoặc xây dựng khác nhau được cho là đúng nếu tất cả các đường dẫn này dẫn đến cùng một kết quả. Do đó, định nghĩa đầu tiên (diện tích của một hình tam giác) hóa ra là đúng, nhưng định nghĩa thứ hai (“đại lộ” của Giáo sư Honsens) hóa ra lại sai. Xin lưu ý: chúng tôi phải chứng minh tính đúng đắn của định nghĩa. Điều này phải được thực hiện trong mọi trường hợp khi có sự tùy tiện nào đó trong bản thân định nghĩa - cách xây dựng mơ hồ, quyền tự do lựa chọn một số yếu tố, v.v.

Hãy xem một ví dụ khác. Đến trường

⟦folio 10⟧

Trong sách giáo khoa lớp 9, độ lớn của một góc nhị diện được định nghĩa bằng độ lớn của góc thẳng của nó (góc PAQ trong Hình 2). Nhưng góc thẳng có thể được vẽ từ một điểm A tùy ý trên cạnh AA' của góc nhị diện; Ví dụ, hãy xem xét góc P'A'Q'. Tại sao nó sẽ có cùng giá trị?

Bài toán 3. Chứng minh tính đúng đắn của định nghĩa góc nhị diện.

Bài toán 4. Ghi nhớ định nghĩa góc giữa hai đường thẳng cắt nhau. Định nghĩa này có ý nghĩa gì? Chứng minh tính đúng đắn của nó.

Bây giờ chúng ta hãy nói về diện tích của một hình tứ giác. Nếu đây không phải là một tứ giác đặc biệt nào đó, chẳng hạn như hình thang, thì công thức chung để tính diện tích của nó như sau: cắt tứ giác theo đường chéo thành hai hình tam giác và lấy tổng diện tích của chúng. Nhưng một tứ giác lồi có thể được cắt chéo theo hai cách khác nhau. Điều gì sẽ xảy ra nếu trong trường hợp này nó trở thành một thứ, và trong một trường hợp khác nó lại thành một thứ khác? Và đối với một đa giác có số cạnh lớn, thậm chí còn có nhiều cách hơn để cắt nó thành hình tam giác. Trên cơ sở nào chúng ta chắc chắn (nếu chúng ta chắc chắn) rằng với tất cả những vết cắt này thì tổng diện tích của các mảnh thu được sẽ bằng nhau? Từ thực tiễn? Nhưng tất cả những thay đổi thực tế chỉ đảm bảo độ chính xác ở một số chữ số nhất định. Thuyết tương đối cho thấy công thức tổng quát để cộng vận tốc chỉ gần đúng và chỉ áp dụng cho những vận tốc nhỏ hơn đáng kể so với tốc độ ánh sáng! Có lẽ những ý tưởng truyền thống về diện tích đa giác chỉ gần đúng? Ví dụ, đây là một bức vẽ chúng tôi mượn từ một tập tài liệu quảng cáo của Ya. S. Dubnov*).

Ở đây, hình vuông có cạnh 21 cm được cắt thành nhiều mảnh, từ đó, như Hình 3 cho thấy, có vẻ như có thể gấp một hình chữ nhật ở các cạnh 34 cm và 13 cm.

Từ
$$21^2=441\neq 442=34\cdot 13,$$
Diện tích của hình thay đổi khi các bộ phận của nó được sắp xếp lại. Và tại sao không, thực sự?

Bài toán 5. Tìm xem điều gì sai trong Hình 3.

Bài toán 6. Chứng minh rằng nếu cắt một đa giác thành tam giác bằng phương pháp nhị diện thì

*) Vâng. S. Dubnov. Sai sót trong chứng minh hình học. M., Gostekhidat, 1953, tr. 10.

Diện tích đa giác tự cắt nhau

Chúng tôi đã thảo luận về tính đúng đắn của định nghĩa trường học về diện tích của đa giác và hình tam giác - tính nhất quán bên trong của chúng. Nhưng định nghĩa trong toán học không chỉ phụ thuộc vào yêu cầu về tính chính xác mang tính công thức. Định nghĩa vẫn phải “có tác dụng”. Hãy để chúng tôi giải thích điều này bằng ví dụ sau, cũng liên quan đến diện tích của một đa giác.

Có thể, và nếu vậy, làm thế nào người ta có thể xác định diện tích của các đa giác tự giao nhau một cách hợp lý và tự nhiên? Ví dụ, diện tích của một ngôi sao năm cánh (Hình 4) là gì?

Nói một cách công thức, có nhiều cách chính xác để gán một số cho mỗi đa giác tự giao nhau và gọi số này là diện tích của nó. Nhưng không phải mọi phương pháp như vậy đều đáng được nói đến trong im lặng. Nhìn chung, các định nghĩa trong toán học được hình thành tương đối thiếu nguyên tắc, không hề “bất ngờ”. Trong nhiều trường hợp (và có lẽ trong ước tính cuối cùng và trong tất cả) các trường hợp, các định nghĩa toán học

⟦folio 11⟧

sự khoan dung được bao gồm trong tự nhiên. Chúng ta hãy nhớ vị trí trong vật lý xác định diện tích của một đa giác. Đây là hai trường hợp tôi chợt nghĩ đến.

1) Trong điện tử, một khái niệm quan trọng là dòng cảm ứng từ (từ thông) Ф xuyên qua một phần bề mặt được giới hạn bởi một mạch dẫn điện. Để đường viền nằm trong một mặt phẳng và vectơ $\vec{B}$ của cảm ứng từ giống nhau tại tất cả các điểm trong không gian và bị mặt phẳng của đường viền ghi đè. Sau đó

$$\Phi = BS,$$

(1)

trong đó $S$ là diện tích của hình được giới hạn bởi đường viền. Từ quan điểm vật lý, sóng phù hợp với câu hỏi từ thông F bằng bao nhiêu nếu đường viền có dạng đa giác tự giao nhau.

Trên thực tế, chúng ta hãy sắp xếp một dây cách điện dưới dạng đa giác tự cắt nhau trong một mặt phẳng, vectơ phân phối lại $\vec{B}$ của cảm ứng từ bằng trường (Hình 5) và nối hai đầu dây với một ampe. Ampe sẽ hiển thị điều gì nếu bạn bắt đầu “di chuyển” dây này? Rốt cuộc, anh ấy sẽ thể hiện điều gì đó! Ví dụ: kim ampe có bị lệch khi di chuyển tam giác $MNA$ đến vị trí $M'N'A$ không? Đặt phần tô đậm không thay đổi. Tuy nhiên, dây $MN$ trong chuyển động của nó đi qua các đường sức từ và do đó xảy ra lực điện cảm ứng. Dòng điện nên chảy. Và anh ấy là một hiện tại thực sự!

Điều này có nghĩa là từ thông F thay đổi. Vì chúng ta muốn công thức $\Phi = BS$ được giữ nguyên nên $S$ phải thay đổi (không giống như vùng được tô bóng). Vậy $S$ - “diện tích đa giác tự cắt” là gì?

Dễ hiểu là tổng diện tích các phần giới hạn của mặt phẳng (được tô màu trong Hình 5) không phù hợp ở đây là $S$. Làm thế nào để xác định $S$ trong trường hợp tổng quát?

2) Trong nhiệt động lực học, công được thực hiện bởi chất lỏng làm việc trong một quá trình khép kín tùy ý thay đổi theo diện tích giới hạn bởi một đường thẳng, mô tả quá trình này trên sơ đồ $(p-V)$-sơ đồ $(p - \text{dавление}, V - \text{объем})$. Thật tự nhiên khi cho rằng điều này cũng đúng với quá trình được mô tả trên sơ đồ $(p-V)$ của một đường đứt đoạn tự giao nhau.

Trong cả hai ví dụ vật lý đã cho, chúng ta đều cần chỉ ra diện tích của các đa giác phẳng tự giao nhau. Điều đáng chú ý là trong cả hai trường hợp, khái niệm diện tích giống nhau sẽ nảy sinh, mặc dù thực tế là những ví dụ này được lấy từ các lĩnh vực vật lý khác nhau. Và khái niệm diện tích này đã được các nhà toán học phát triển. Ví dụ, nó được mô tả trong một bài viết của N. Vaguten*). Nó đưa ra một số định nghĩa tương đương với nhau về khái niệm này; Chúng ta sẽ dừng lại ở phần tiếp theo.

Hãy chọn hướng đi ngang của đa giác của chúng ta và chỉ định các đỉnh của nó theo thứ tự chúng ta đi qua nó: $A_1, A_2, ..., A_n$. Chúng ta hãy đánh dấu một điểm tùy ý $P$ trên mặt phẳng không nằm trên đường viền của đa giác. Chúng ta sẽ đi xung quanh đa giác dọc theo đường viền của nó: chia nhỏ dọc theo $A_1A_2$, sau đó dọc theo $A_2A_3$, v.v. và quay lại điểm $A_1$. Trong trường hợp này, vectơ bán kính, bắt đầu từ điểm $P$ và kết thúc tại điểm chúng ta đang ở, sẽ quay theo hướng mặt phẳng (nghĩa là ngược chiều kim đồng hồ) hoặc theo hướng âm. Trong trường hợp cuối cùng, nó bề mặt ở một góc $360^\circ \cdot n$, trong đó $n$ là số nguyên cho biết số lần chúng ta đi quanh điểm $P$ hoặc dọc theo đường dẫn $A_1, A_2, ..., A_n, A_1$. Vì vậy, nếu điểm $P$ được lấy ở tâm gót của ngôi sao cuối cùng (xem Hình 4), thì chúng ta nhận được $n=2$.

Đa giác của chúng ta chia mặt phẳng thành các vùng: một vùng vô hạn và một số vùng hữu hạn. Con số $n$ không đổi ở mọi vùng và vô tận

⟦folio 12⟧

vùng cuối cùng $n=0$ (trong Hình 6, a, b, các giá trị $n$ đều nằm trong tất cả các vùng hữu hạn). Vì vậy, hãy gọi diện tích định hướng của đa giác của chúng ta là tổng

$$S_1n_1 + S_2n_2 + \dots + S_kn_k,$$

Điều thú vị là định nghĩa được phát triển từ những thông điệp toán học thuần túy hóa ra lại phù hợp với hai định luật vật lý hiện đại khác nhau. Điều này đã xảy ra hơn một lần trong lịch sử khoa học và nó sẽ được viết lại trong «Kvant».

Điện trở là một hiện tượng lượng tử

(Để bắt đầu, xem trang 2)

Biểu thị phần y từ công thức (**) và thay nó vào biểu thức cho nhiệt độ Debye - $\theta = \frac{hv}{k}$ - chúng ta thu được kết quả đó

$$\theta = \frac{hc}{k} \sqrt[3]{\frac{n}{4\pi}}.$$

Như vậy, chúng ta đã thu được mối liên hệ giữa nhiệt độ Debye $\theta$ và tốc độ truyền âm trong chất rắn $c$. Sử dụng công thức này và biểu đồ được trình bày trong Hình 8 (xem trang 8), bạn có thể giải bài toán mà chúng tôi sẽ cung cấp cho bạn. Chúng đơn giản và không đòi hỏi sự khéo léo đặc biệt, nhưng thú vị và tôn trọng ở hai khía cạnh. Đầu tiên, bạn sẽ thấy một mối liên hệ bất ngờ giữa những thứ khác nhau như tốc độ âm thanh và sự phụ thuộc của điện trở vào nhiệt độ. Thứ hai, bạn sẽ làm quen với các đường cong tổng quát, rất hữu ích trong nhiều trường hợp không thể sử dụng các công thức lý thuyết. Sự phụ thuộc $R=f(T)$ là như nhau đối với mỗi kim loại, nhưng vì chúng có thể được kết hợp trên một đường cong tổng quát (xem Hình 8), điều đó có nghĩa là những sự phụ thuộc này và cách biểu thị các đường cong của chúng là tương tự nhau. Điều này ở đây có ý nghĩa rộng hơn trong hình học phổ thông: nó có nghĩa là các đường cong có thể được kết hợp bằng cách thay đổi tỷ lệ một cách độc lập dọc theo hai trục tọa độ.

Bây giờ hãy thử giải bài toán sau:

1. Tốc độ truyền âm của sắt là 5200 m/s, điện trở riêng ở âm 100°C là 0,592 Ohm mm2/m. Tìm điện trở suất của sắt ở nhiệt độ +200°C.

2. Sử dụng sự phụ thuộc của điện trở đồng vào nhiệt độ (xem Hình 1 trên trang 3), xác định tốc độ truyền âm trong đồng.
