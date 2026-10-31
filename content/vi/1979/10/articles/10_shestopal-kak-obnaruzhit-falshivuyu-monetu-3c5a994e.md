---
id: 1979-10-shestopal-kak-obnaruzhit-falshivuyu-monetu-3c5a994e
issue: kvant_1979_10
year: 1979
number: "10"
title: Cách nhận biết tiền giả
authors:
  - Шестопал Г. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 23
page_last: 27
page_labels: 21-25
tag: KGYW
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 04874c9530745d938bb91d357260a5b13b2a763ee53e00c6d805442b30915748
prompt_sha256: draft-1
translated_from: content/ru/1979/10/articles/10_shestopal-kak-obnaruzhit-falshivuyu-monetu-3c5a994e.md
source_content_sha256: bf7393e7736d5d546416399243966ccc15f27de1d92d4764543d0cbab32f87ff
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 21⟧

G. Shestomal

Cách nhận biết tiền giả

Hãy tưởng tượng rằng một đống đồng xu trông giống hệt nhau được đổ lên bàn, nhưng bạn được thông báo rằng một trong những đồng xu này là tiền giả. Nó có trọng lượng khác với những đồng xu khác nhưng bạn không thể biết nó nhẹ hơn hay nặng hơn. Bạn có thể tùy ý sử dụng cân theo giờ không có nấm. Bạn nên tiến hành tách đồng xu này như thế nào và tìm ra loại của nó (nghĩa là tìm xem nó nhẹ hơn hay nặng hơn) sau một số lần cân tối thiểu?

Nhiều người trong số các bạn có thể đã giải được bài toán này với 12 xu. Hình này hiển thị một trong lời giải của bài toán này. Kết quả có thể xảy ra của lần cân đầu tiên tương ứng với ba lựa chọn khác nhau để chọn đồng xu cho lần cân thứ hai. (Trong hình, các đồng xu được thay đổi kích thước, chữ l và t đọc tương ứng, nhẹ và nặng.)

Một đặc điểm đặc trưng của lời giải này là sự phụ thuộc của việc lựa chọn đồng xu cho lần cân tiếp theo vào kết quả của lần cân trước.

Bây giờ chúng ta đặt bài toán ở dạng tổng quát.

Có $m \geq 3$ đồng xu cùng loại. Tất cả các đồng xu, ngoại trừ một đồng xu, đều có cùng trọng lượng và một đồng khác nhau về trọng lượng, nhưng không biết theo hướng nào. Số lần cân nhỏ nhất trên một chiếc cân đồng hồ không có zip có thể được sử dụng để tìm đồng xu này và tìm ra số min của nó là bao nhiêu? *)

Công trình bài toán này cách đây nhiều năm đã thu hút sự chú ý của nhiều nhà toán học, chủ yếu là:

*) Rõ ràng, đối với các giá trị $m < 3$ bài toán, việc quyết định là không có ý nghĩa: đối với $m = 1$ đồng xu sẽ là giả, nhưng không xác định loại; ở mức $m = 2$ các đồng xu sẽ có trọng lượng khác nhau và không thể chọn được tiền giả.

⟦folio 22⟧

ở Anh và Mỹ. Năm 1945, trên tạp chí tiếng Anh “The Mathematical Gazette”, theo hướng «Kvant», lời giải của bài toán này đã xuất hiện. Tác giả của nó, R. L. Goodstein, sau đó đã trở thành một chuyên gia nổi tiếng trong lĩnh vực logic toán học.

Goodstein cung cấp phương pháp xác định đồng xu giả và loại của nó bằng cách cân $n \geq 3$ nếu số lượng đồng xu

$$m \leq \frac{1}{2} \left( 3^n - 2n + 3 \right)$$

(lưu ý rằng đối với $n = 3$ $m \leq 12$).

Tuy nhiên, hóa ra đối với $n > 3$, lời giải của nó không phải là tốt nhất: trong các lần cân $n$, có thể xác định được đồng xu giả và xác định loại của nó từ một số lượng lớn đồng xu:

$$m \leq \frac{1}{2} \left( 3^n - 3 \right).$$

Điều này đã được phát hiện bởi một số nhà khoa học toán học, không liên quan gì đến nhau, và vào năm sau, 1946, cùng một tạp chí đã công bố một danh sách khá dài về tên của họ và mức độ thành công khác nhau trong việc tìm kiếm một đồng xu giả. Trong cùng số tạp chí, bài viết hay nhất lời giải – lời giải của F. J. Dyson, nhà vật lý lý thuyết nổi tiếng trong tương lai, đã được xuất bản.

Ý tưởng của Dyson dựa trên việc sử dụng hệ thống số ba ngôi: tất cả các đồng xu đều được đánh dấu bằng các số ba ngôi được lựa chọn đặc biệt - các điểm đánh dấu giúp phản ánh thuận tiện tiến trình của các lần cân liên tiếp. Đặc biệt hấp dẫn với phương pháp này lời giải là sự độc lập của việc lựa chọn đồng xu cho lần cân tiếp theo so với kết quả của lần cân trước.

Trong những năm tiếp theo, lời giải khác trong số bài toán *) này đã được in và phương pháp của Dyson chưa bao giờ bị lãng quên.

Pozny muốn nói chi tiết về anh ấy.

Tất cả lời giải của Dyson có thể được chia thành hai giai đoạn.

*) Nalrimer, trong cuốn sách của A. Yaglom, II. Yaglom “Xác suất và Thông tin” (M., “Nauka”, 1973).

A. Nếu

$$m = \frac{1}{2} \left( 3^n - 3 \right), n = 2, 3, \dots,$$

sau đó để tách một đồng tiền giả khỏi tổng số $m$ đồng xu và xác định loại của nó, chỉ cần thực hiện các lần cân $n$ là đủ.

B. Nếu số lượng xu

$$m < \frac{1}{2} \left( 3^n - 3 \right), m \geq 3,$$

thì để đạt được mục tiêu tương tự, việc cân nhắc $n$ cũng là đủ.

Chúng ta hãy xem xét từng giai đoạn riêng biệt.

Giai đoạn đầu tiên

Gọi số xu là $m = \frac{1}{2} \left( 3^n - 3 \right)$.

Xét tất cả các số có $n$ chữ số (bộ chữ số 0, 1, 2) 00 ... 00, 00 ... 01, ..., 22 ... 22. Có $3^n$. Chúng tôi sử dụng chúng để đánh dấu đồng xu như sau: làm điểm đánh dấu, chúng tôi lấy tất cả các số, ngoại trừ ba số, bao gồm các số giống hệt nhau: 0 ... 0, 1 ... 1, 2 ... 2.

《Hãy xây dựng》 tất cả các điểm đánh dấu theo cặp: trong một cặp, chúng ta sẽ “đặt” hai điểm đánh dấu bổ sung - những điểm có số tương ứng với 2 (nói cách khác, các điểm đánh dấu bổ sung sẽ là những điểm có tổng bằng 22... 22).

Hãy gọi điểm đánh dấu là *right* nếu nó chứa cặp số không bằng nhau đầu tiên - 01, 12 hoặc 20. Nếu không, điểm đánh dấu sẽ được gọi là bên trái. Rõ ràng, trong mỗi cặp điểm đánh dấu bổ sung có một cặp điểm đánh dấu. Ví dụ: 12 đồng xu có thể được “đánh dấu” như trong bảng.

Chúng ta hãy biểu thị bằng $M(i, 0), M(i, 1)$ và $M(i, 2)$ tập hợp đồng xu tương ứng có chữ số thứ $i$ của dấu bên phải tương ứng bằng 0, 1 hoặc 2.

⟦folio 23⟧

Dễ dàng nhận thấy rằng số lượng xu trong mỗi bộ $M(i, 0)$, $M(i, 1)$ và $M(i, 2)$ là như nhau và các bộ này không có phần tử chung nào (xem bảng chẳng hạn).

Phương pháp cân tiền xu của Dyson như sau:

Các đồng xu được cân tuần tự $n$.

Ở lần cân thứ $i$ ($i = 1, 2, \dots, n$), tất cả các đồng xu của bộ $M(i, 0)$ được đặt trên đĩa cân bên trái và tất cả các đồng xu của bộ $M(i, 2)$ được đặt trên đĩa cân bên phải. Kết quả của mỗi lần cân sẽ được biểu thị bằng số 0 nếu đĩa cân bên trái nặng hơn, số 1 nếu cả hai cốc có cùng trọng lượng và số 2 nếu đĩa cân bên phải nặng hơn (xem hình). Kết quả của trọng số $i$ sẽ được ký hiệu là $l_i$.

Từ các số $l_1, l_2, \dots, l_n$ chúng ta tạo điểm đánh dấu

$$l = l_1 l_2 \dots l_n^*).$$

Hóa ra $l$ là điểm đánh dấu của đồng xu giả $F$ và nếu $l$ là điểm đánh dấu bên phải thì $F$ nặng hơn phần còn lại của đồng xu và nếu $l$ là điểm đánh dấu bên trái thì $F$ nhẹ hơn phần còn lại của đồng xu.

Thật vậy, hãy xem điều gì tạo ra khi $i$-e được tạo ra

*) Chứng minh rằng đây thực sự là một điểm đánh dấu, tức là các số $l_1, l_2, \dots, l_n$ không thể giống nhau.

$$l_i = 0$$

cân. Kết quả của việc cân này là các cân vẫn ở trạng thái cân bằng hoặc một trong các cốc bị đặt chéo.

Nếu cân vẫn cân bằng thì trên cân không có đồng giả nên nó nằm trong bộ $M(i, 1)$. Nhưng điều này có nghĩa là chữ số thứ $i$ của điểm đánh dấu bên phải (và bên trái) của nó bằng 1, như được biểu thị bằng kết quả trọng số $l_i = 1$.

Nếu gạch chéo một trong các cân thì đồng tiền giả nằm trên cân. Ví dụ: đặt cốc bên phải chéo nhau, tức là $l_i = 2$. Kết quả này có thể xảy ra trong hai trường hợp:

- Đồng tiền giả nằm trên cốc bên phải (khi đó nặng hơn các đồng tiền còn lại), tức là thuộc bộ $M(i, 2)$, chữ số thứ $i$ của vạch bên phải bằng 2 nên kết quả cân trùng với chữ số thứ $i$ của vạch bên phải;

— đồng xu giả nằm trên cốc bên trái (khi đó nó nhẹ hơn các đồng xu khác), nghĩa là nó nằm trong bộ $M(i, 0)$, do đó, chữ số thứ $i$ của điểm đánh dấu bên phải của nó là 0 và kết quả cân trùng với chữ số thứ $i$ của điểm đánh dấu bên trái của nó.

Trường hợp “đối xứng” hoàn toàn tương tự, khi trục bên trái của thang đo ($l_i = 0$) giao nhau.

Quả thực, Pozny, điểm đánh dấu $l = l_1 l_2 \dots l_n$ được hình thành do kết quả của các lần cân liên tiếp là điểm đánh dấu của một đồng tiền giả, với bên phải trong trường hợp đồng xu nặng hơn và bên trái trong trường hợp đồng xu nhẹ hơn, đó là điều cần phải được chứng minh.

Điều thú vị cần lưu ý là loại đồng xu thường được xác định bởi nisse, đây là nơi thực hiện tất cả các phép cân - ngay khi hai chữ số khác nhau xuất hiện trong quá trình hình thành điểm đánh dấu $l$.

Một đặc điểm cơ bản của phương pháp được mô tả, như Ravnisse đã lưu ý, là việc lựa chọn đồng xu cho mỗi bộ cân không phụ thuộc vào kết quả của lần cân trước đó.

⟦folio 24⟧

Ví dụ: đối với 12 đồng xu được đánh dấu như trong bảng, bạn cần thực hiện ba lần cân sau: (1,4,7,10), (3,6,9,12); (3,6,9,10), (2,5,8,12); (3,4,8,12), (2,6,7,11).

Giai đoạn thứ hai

Chúng ta hãy phác thảo ngắn gọn phương pháp Dyson cho trường hợp $m < \frac{1}{2} (3^n - 3)$. Nếu trong trường hợp này các điểm đánh dấu được gán cho các đồng xu một cách tùy ý thì các bộ $M(i, 0)$ và $M(i, 2)$ có ​​thể chứa số lượng đồng xu khác nhau. Chúng ta hãy hành động như một nhà thơ như sau. Chia tất cả các điểm đánh dấu thành các nhóm sáu: thành một nhóm, chúng tôi bao gồm các điểm đánh dấu bên phải, các điểm này nhận lẫn nhau bằng cách thay thế theo chu kỳ các số $0 \rightarrow 1$, $1 \rightarrow 2$, $2 \rightarrow 0$ và các điểm đánh dấu bên trái tương ứng.

Mỗi nhóm có ba điểm đánh dấu bên phải và ba điểm đánh dấu bên trái. Hãy để chúng tôi đánh dấu nhóm chứa các điểm đánh dấu phù hợp $00 \ldots 01, 11 \ldots 12, 22 \ldots 20$. Chia các đồng xu thành nhóm ba càng dài càng tốt và đánh dấu chúng như sau. Monetam từ một nhóm, chúng tôi so sánh các cặp điểm đánh dấu từ một nhóm và đối với phần còn lại, nếu có, chúng tôi sử dụng các cặp điểm đánh dấu từ nhóm đã chọn. Nếu còn lại một đồng xu không có trong bộ ba, thì ghép điểm đánh dấu bên phải $11 \ldots 12$ với nó và nếu có hai đồng xu thì khớp điểm đánh dấu bên phải $00 \ldots 01$ và $22 \ldots 20$ (và điểm đánh dấu bên trái tương ứng).

Với dấu hiệu này, lần cân $n — 1$ đầu tiên sẽ được bắt đầu ở bên phải. Vui lòng cho chúng tôi biết cách tự bạn thực hiện lần cân cuối cùng.

Phương pháp Dyson được mô tả. Bây giờ chúng ta hãy đảm bảo rằng theo một nghĩa nào đó đó là sự hiện diện. Cụ thể, chúng tôi sẽ chỉ ra rằng nếu từ $m$ đồng xu có thể chọn $n$ một đồng xu giả bằng cách cân và xác định loại của nó, thì $2m \leq 3^n — 3$. Tất nhiên, chúng tôi sẽ không tính đến khả năng “may mắn”: với nó, hai lần cân có thể đủ để xác định một đồng tiền giả từ bất kỳ số lượng đồng xu nào.

Vì vậy, hãy giả sử rằng trọng số $n$ là đủ.

Hãy đánh số các đồng xu có số $1,2, \ldots, m$ và chuẩn bị $2m$ mảnh giấy. Hãy viết tất cả các phương án có thể có lên chúng: đồng xu thứ nhất nhẹ hơn, đồng xu thứ nhất nặng hơn, đồng xu thứ hai nhẹ hơn, v.v. Rõ ràng là trong trường hợp này, tất cả $2m$ mảnh giấy sẽ được sử dụng và không bỏ sót một phương án nào trong số các phương án có thể có. Như chúng tôi đã nêu ở trên, chúng tôi sẽ biểu thị kết quả của việc cân bằng các số $0, 1$ hoặc $2$. Mỗi lần cân cho thấy một số đáp số có thể không phù hợp và một số vẫn còn nghi ngờ. Chúng tôi sẽ chọn đồng xu cho lần cân đầu tiên. Nếu không thực sự làm điều đó, chúng tôi sẽ viết lên từng mảnh giấy kết quả của lần cân đầu tiên khiến nó bị nghi ngờ. Rõ ràng là trên mỗi tờ giấy sẽ có viết một trong các số $0, 1$ hoặc $2$. Vì vậy, tất cả các giấy tờ sẽ được chia thành ba nhóm. Do đó, nhóm lớn nhất chứa không ít hơn $2m/3$ mảnh giấy. Điều này có nghĩa là cho dù chúng tôi tổ chức lần kiểm tra đầu tiên như thế nào đi chăng nữa, có thể sau đó không ít hơn $2m/3$ mảnh giấy sẽ vẫn bị nghi ngờ.

Tương tự như vậy, lần cân thứ hai sẽ sắp xếp nhóm đáng ngờ này thành ba nhóm nhỏ. Do đó, nhiều nhất trong số chúng sẽ chứa ít nhất $2m/9$ mảnh giấy. Tương tự như vậy, sau khi cân $n$, chúng ta có thể nhận được $2m/3^n$ những mảnh giấy đáng ngờ trong một nhóm. Do đó, nếu $2m/3^n > 1$, thì nói chung, không thể xác định được đồng giả và loại của nó bằng cách cân $n$. Do đó cân $n$ là đủ thì $2m \leq 3^n$.

Nhưng đó không phải là tất cả! Chúng ta chưa xử lý trường hợp $2m = 3^n — 1$ (số chẵn $2m$ không thể bằng $3^n — 2$ hoặc $3^n$). Đối với anh, những thông điệp trên là chưa đủ.

⟦folio 25⟧

Chúng ta hãy xem xét kỹ hơn về lần cân đầu tiên. Rõ ràng số tờ giấy ghi số 0 bằng số tờ giấy ghi số 2. Giả sử mỗi cái có $p$ mảnh thì 1 mảnh sẽ được viết trên $2m - 2p$ mảnh giấy.

Lưu ý rằng $p$ là số chẵn. Thật vậy, nếu có $k$ đồng xu ở bên trái và bên phải của cân thì $p = 2k$. Nếu $p$ hoặc $2m - 2p$ lớn hơn $3^{n-1}$ thì theo cân nhắc, trọng lượng $n - 1$ còn lại có thể không đủ để xác định mảnh giấy cần thiết. Nếu $p = 2k \leq 3^{n-1}$ và $2m - 2p \leq 3^{n-1} - 1$ thì vì $3^{n-1} - 1$ là số lẻ nên $p \leq 3^{n-1} - 1$, $2m - 2p \leq 3^{n-1} - 1$. Nhưng sau đó $2m = (2m - 2p) + 2p \leq 3^{n-1} - 1 + 2(3^{n-1} - 1) = 3^n - 3$. Vì vậy, nếu cân $n$ là đủ thì $2m \leq 3^n - 3$.

Tóm lại, có một số bài toán có thể được giải bằng phương pháp Dyson.

Danh sách độc giả đã gửi quy tắc lời giải bài toán của Bài toán Kvant

(Phần đầu xem trang 7, 14)

A. Petrosli (Yerevan) 6a; L. Petrusevich (làng Kozly, vùng Minsk) 6; I. Pikovsky (Kyiv) 3; A. Podvyaznikov (Mosalsk) 7; V. Podstritsan (Lviv) 6, 8, 1; A. Popelokhin (Kyiv) 6, 7; A. Popov (Moscow) 7; V. Pomanov (Novosibirsk) 3; S. Poshekhonov (Engels) 7; G. Purichamishili (Tbinis) 6a; B. Rabinovich (Tula) 6, 7, 1, 3, 4; V. Radchenko (Kyiv) 6a, 2-4; M. Reitman (Moscow) 6a, 7, 2; S. Rekhvashili (Pavlodar) 6; I. Roizman (thị trấn Kalinovka, vùng Vinnytsia) 6-8; N. Rubinmeshin (Leningrad) 6a; B. Rublev (Kyiv) 2, 3; I. Savenkov (khu định cư đô thị Levye Gory, vùng Saratov) 6, 7; G. Samelson (Leningrad) 3; M. Sevryuk (Moscow) 6-9, 1-3; P. Selivanov (Semipalatinsk) 6a, 7, 2; A. Sivatsky (Leningrad) 6a, 7, 9, 0, 2, 3; A. Smirnov (Kurgan) 6, 7; A. Smyslov (Konkovo) 6; A. Sromin (Leningrad) 6, 7; S. Smadinitsenko (Moscow) 6—8, 3; F. Sukoev (Tashkent) 6-9; N. Sumovsky (Lviv) 7, 8; O. Taven (Minsk) 6a, 7; K. Tatalyan (Yerevan) 6; L. Tener (làng Yaltushkov, vùng Vinnytsia) 6, 7; K. Terekhov (Ryazan) 6a; V. Titenko (làng Bluzha, vùng Minsk) 7; A. Ulivanov (Gorky) 9; V. Umansky (Baku) 6, 7; R. Ushakov (Kyiv) 3; D. Faingauz (Leningrad) 6, 7, 0; V. Farber (Baku) 3; A. Famullayev (Baku) 3; N. Fedin (Omsk) 2; A. Fedorov (Moscow) 7, 3; O. Horuzhsky (Chernivtsi) 7; S. Khosid (Alma-Ata) 6a, 7; Z. Tsikhistavi (Telavi) 3; I. Chernaya (Leningrad) 3; O. Chechel (Moscow) 6—8, 1, 4; A. Shatsyan (Yerevan) 7; P. Shaprin (Kyiv) 7; N. Sharomet (Moscow) 6, 7, 2, 4; Yu. Shirman (Kharkov) 6; G. Shteren (Orsk) 6a; M. Ykovlev (Kemerovo) 2; A. Yalytsev (Tula) 6, 7; L. Yanovskaya (Kharkov) 7; A. Yatsenko (Tbilisi) 7.

F và zika

Hầu hết tất cả độc giả đều hoàn thành các nhiệm vụ F539 và F542. Phần còn lại bài toán giải quyết chính xác:

V. Abidzhaev (Lviv) 33; E. Alexandrova (Glazov) 35, 40, 41; Yu. Anisimov (huyện Toropetsk, vùng Kalinin) 35; A. Arbamsky (Blagoveshchensk-on-Amur) 40, 41; A. Bazirov (làng Kirovka AzSSR) 40; L. Baraz (Sverdlovsk) 38-41; I. Baranets (làng Dzerzhinsky, vùng Moscow) 38-41; A. Barzikin (làng Chernogolovka, vùng Moscow) 33, 35-41; A. Belousov (Kalinerrad) 36; A. Vasiliev (Võru) 40, 41; D. Vinogradov (Dzerzhinsk) 35; M. Gavrilov (làng Chernogolovka, vùng Moscow) 35, 38—44, 47; M. Goltsman (Dnepropetrovsk) 43, 44, 47; I. Gopchi (Novosibirsk) 38, 41; V. Gorpinenko (Kolchugino) 40; I. Danilovsky (Gorky) 33, 38; V. Didukh (Lviv) 35, 37, 38, 40-44, 47; S. Dovbishch (Moscow) 33, 35, 38—41, 47; S. Dovzhenko (Donetsk) 34-36, 38-41; E. Emelyanov (Moscow) 43, 47; A. Ermolin (Petrozavodsk) 36, 38; V. Zhordochki (Orsk) 38; A. Zhuravlev (Leningrad) 38-41; E. Zernysh (làng Kuzmovka, vùng Leningrad) 40, 41; E. Zudin (Alexandrov) 34, 35, 37, 40, 41-44, 46; S. Zuev (làng Chernogolovka, vùng Moscow) 40; A. Iovasha (Cuối cùng, xem trang 38)
