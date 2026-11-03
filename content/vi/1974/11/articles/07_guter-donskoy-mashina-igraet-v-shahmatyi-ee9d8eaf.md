---
id: 1974-11-guter-donskoy-mashina-igraet-v-shahmatyi-ee9d8eaf
issue: kvant_1974_11
year: 1974
number: "11"
title: Máy chơi cờ
authors:
  - Гутер Р. С.
  - Донской М. В.
rubric: osnovnye-stati
page_first: 19
page_last: 24
page_labels: 17-22
tag: KYFY
lang: vi
source: kvant_digital
extraction: vision
content_sha256: a70571046381951e0c263a88526023a9818a147c0b743fc6879f4beac040502f
prompt_sha256: draft-1
translated_from: content/ru/1974/11/articles/07_guter-donskoy-mashina-igraet-v-shahmatyi-ee9d8eaf.md
source_content_sha256: da388e5603ff53a3277b741e200a5574dc4a93973cb84d04fde211ce443ce0f7
translation_model: draft
translation_run: vi-draft-2026-11-03
translation_quality: draft
---

⟦folio 17⟧

Biên dịch chương trình trò chơi cờ vua cho máy tính điện tử yêu cầu lời giải các vấn đề sau:

1) tạo ra phương pháp ghi và lưu trữ thông tin về vị trí trên bảng và chuyển động trong máy;
2) tạo ra một thuật toán mà máy phải chọn bước tiếp theo;
3) triển khai thuật toán này dưới dạng một chương trình sử dụng phương pháp ghi và lưu trữ thông tin đã biết.

Ghi lại một vị trí

Hãy đánh số các ô của bàn cờ bằng hai số bắt đầu, chữ số đầu tiên là số dọc (trong ký hiệu cờ vua thông thường, nó được biểu thị bằng một chữ cái) và chữ số thứ hai là số ngang (cả hai số đều bắt đầu từ số 0). Vì có tám đường ngang và dọc nên bạn có thể sử dụng hệ thống số tám chữ số thân thiện với máy, sử dụng các số 0, 1, 2, ..., 7 *). Như vậy, sau a1 sẽ có số 00, sau a8 - số 07, sau d5 - số 34, sau h8 - số 77.

Chúng ta cũng đánh số các quân cờ, gán số 1 cho quân Tốt, 2 cho quân Mã, 3 cho quân Tượng, 4 cho quân Xe, 5 cho quân Hậu và 6 cho quân Vua, trong đó các số màu trắng là số dương và số màu đen là số âm. Mỗi doxy ở một vị trí có thể so sánh với một số - số của chữ số trong trường này hoặc 0 nếu trường trống.

Trong cách đánh số được đề xuất, số có một chữ số là tám chữ số, trong đó ba chữ số kép là đủ để biểu thị và một dấu (màu của chữ số), yêu cầu viết một chữ số khác. Qua-

*) Sẽ rất hữu ích cho người đọc khi nhớ hoặc đọc các bài: P. C. Guter, Máy tính và hệ thống số, «Kvant», 1971, Số 9, Ngôn ngữ con người và ngôn ngữ máy, «Kvant», 1971, Số 10,

⟦folio 18⟧

điều này yêu cầu bốn chữ số cho mỗi trường để ghi lại vị trí. Chúng tôi sẽ dành chữ số đầu tiên để ghi dấu (0 - “cộng”, 1 - “trừ”) và ba chữ số tiếp theo - để ghi số của hình. Một ô nhớ sẽ chứa thông tin về một đường ngang, trong khi 32 bit sẽ được chiếm trong ô nhớ. Tất cả thông tin về vị trí trên bảng sẽ chiếm 8 ô (1 ô cho mỗi đường ngang).

hình 1 hiển thị mục nhập của đường ngang đầu tiên của vị trí bắt đầu. Người đọc có thể dễ dàng hiểu nó bằng cách nhớ cách biểu diễn các chữ số bát phân dưới dạng mười ba nhân đôi:
$$0_8 = 000_2, 1_8 = 001_2, 2_8 = 010_2, 3_8 = 011_2, 4_8 = 100_2, 5_8 = 101_2, 6_8 = 110_2, 7_8 = 111_2$$
(ở đây chỉ số của số cho biết hệ thống số mà nó được viết).

Ghi lại một động thái
Một nước đi có thể được biểu diễn dưới dạng một cặp số: số ô vuông chứa quân cờ và số ô vuông mà quân cờ di chuyển. Tuy nhiên, sẽ thuận tiện hơn như được thực hiện trong thế cờ vua, khi báo cáo cả hai trường cũng như tên và màu sắc (tức là số và ký hiệu) của quân di chuyển. Sau đó, bạn sẽ cần ba số và số đầu tiên sẽ có một chữ số (nhưng có dấu) và hai số còn lại sẽ có hai chữ số.

Có, ghi lại
+1 41 43
nghĩa là việc di chuyển quân trắng (+) (1) từ ô e2 (41) đến ô e4 (43), tức là ở thế cờ chung toàn bộ

chiêu thức phổ biến của ma e2 - e4, thậm chí còn được biết đến với O. Bender. Ghi
—5 37 64
tương ứng với nước đi của Đen, thường được viết là Qd8 - g5.

Lựa chọn di chuyển
Việc “dạy máy” thực hiện một nước đi khá đơn giản, tức là kiểm tra khả năng của nó và nhập thay đổi tương ứng vào bản ghi vị trí. Việc dạy cô ấy một cách nhanh chóng sẽ khó khăn hơn nhiều, mặc dù có một số khả năng có thể xảy ra ở một vị trí nhất định, một vị trí “tốt nhất”. Để làm được điều này, bạn cần có khả năng so sánh các nước đi khác nhau.

Một cách là sắp xếp thông qua các tùy chọn. Nhưng việc tìm kiếm “đến cùng”, tức là đến vị trí mà kết quả được biết, là không thể do số lượng tùy chọn yêu cầu quá lớn. Chúng ta phải hạn chế xem xét một số nước đi nhất định. Nhưng sau đó bạn cần có khả năng so sánh các vị trí và trả lời câu hỏi cái nào tốt hơn. Khi đó chúng ta có thể coi nước đi tốt nhất là nước đi dẫn đến vị trí tốt nhất.

Đánh giá đơn giản hơn nhiều sẽ là sự khác biệt giữa vật liệu tài nguyên trắng và đen. Trong trường hợp này, mỗi con số được đánh giá bằng một số điểm (điểm) nhất định. Để đánh giá một vị trí, chỉ cần tính tổng số điểm tương ứng với quân trắng và quân đen trên bảng và tìm ra sự khác biệt của chúng là đủ. Tất nhiên, đánh giá như vậy là quá thô: người ta biết rằng thường phải hy sinh vật chất vì lợi ích của mình.

Nằm ngang
Số trường
Nhập vào ô

Hình 1.

⟦folio 19⟧

đạt được lợi thế về vị trí hoặc chiến thuật. Do đó, những đánh giá tinh tế hơn cũng bao gồm các yếu tố chiến thuật: khả năng hình thành vật liệu chiến thắng, sự hiện diện của những con tốt áp đảo đối với bản thân hoặc đối thủ, khả năng nhập thành, chiếm phòng trống với quân xe hoặc quân hậu, v.v.

Làm cách nào để sử dụng khả năng đánh giá vị trí bằng chức năng đánh giá đã chọn này hoặc chức năng đánh giá đã chọn khác? Rõ ràng là việc đánh giá vị trí nhận được nước đi cuối cùng của một nước đi là chưa đủ mà cần phải xem xét tất cả các vị trí có thể có trong một số nước đi phía trước. Đương nhiên, “độ sâu tìm kiếm” càng lớn, tức là số lượng nước đi được đánh giá sau đó thì lựa chọn nước đi càng tốt. Tuy nhiên, cần lưu ý rằng việc tăng độ sâu thêm 1 nước đi sẽ tăng thời gian chọn nước đi lên khoảng 40 lần.

Việc lựa chọn nước đi được thực hiện bằng cách sử dụng một quy trình tối thiểu mà chúng tôi sẽ minh họa bằng ví dụ về tìm kiếm 1 nước đi. Để từ vị trí $A$ (nước đi của chúng ta) di chuyển dẫn đến vị trí $B_1, B_2, B_3$ ... (hình 2) đều có thể. Từ các vị trí kết quả, các nước đi của đối thủ có thể xảy ra, dẫn đến các vị trí $C_1, C_2, C_3, C_4$, ..., những ước tính mà chúng tôi đã biết. Vì ở một vị trí, chẳng hạn như $B_1$, đối thủ rất có thể sẽ chọn nước đi mạnh nhất có thể, nên điểm $B_1$ phải được lấy là điểm tối thiểu của điểm vị trí $C_1, C_2, C_3$. Ước tính của các vị trí còn lại $B_2, B_3$, ..., thu được sau nhiều lần di chuyển khác nhau của chúng tôi, cũng được xác định.

Biết được các ước tính vị trí $B_1, B_2, B_3$, ..., chúng ta có thể lựa chọn vị trí phù hợp nhất. Nước đi dẫn đến vị trí có số điểm tối đa này sẽ là nước đi tốt nhất cho độ sâu tìm kiếm đã chọn.

Chiến lược lựa chọn nước đi tương tự được sử dụng cho bất kỳ độ sâu tìm kiếm nào khác: một số nước đi nhất định được thực hiện từ một vị trí nhất định và vị trí kết quả được ước tính bằng cách sử dụng hàm đánh giá đã chọn. Sau đó nước đi cuối cùng được thay đổi và vị trí mới thu được sẽ được đánh giá. Khi tất cả các nước đi cuối cùng có thể đã được kiểm tra, nước đi thứ hai đến nước đi cuối cùng sẽ được thay đổi, v.v. để cuối cùng tất cả các vị trí có thể đạt được từ số nước đi cuối cùng ban đầu đều được đánh giá. Các ước tính thu được "ở cấp thấp hơn" được khôi phục "lên trên" và đối với các vị trí có kẻ địch di chuyển, mức tối thiểu được chọn và đối với các vị trí có bước di chuyển của chúng ta, mức tối đa được chọn từ ước tính của các vị trí "thấp hơn".

Vì vậy, nước đi của bạn và nước đi của đối thủ nên được xem xét khác nhau. Trong tương lai chúng tôi sẽ gọi chúng là *nửa bước*. Ví dụ về sơ đồ chọn nước đi khi tìm kiếm

⟦folio 20⟧

ba nửa giờ được hiển thị trên hình 3. Ở đây, các vòng tròn biểu thị vị trí, các đoạn màu đỏ biểu thị nước đi của bạn và các đoạn màu xanh biểu thị nước đi của đối thủ.

Các số trong vòng tròn biểu thị ước tính vị trí thu được theo cách được mô tả ở trên (đối với các vị trí “thấp” - sử dụng hàm đánh giá, đối với “cao hơn” - sử dụng quy trình tối thiểu). Các con số bên cạnh các đoạn thể hiện trình tự khoảng cách của các bước di chuyển tương ứng trong quá trình tìm kiếm. Những nước đi tốt nhất từ ​​mỗi vị trí được đánh dấu bằng các đường đôi.

Chúng tôi chỉ lưu ý rằng để rõ ràng hơn hình chúng tôi đã giới hạn bản thân ở một số lượng nhỏ các bước di chuyển có thể có từ mỗi vị trí. Kết quả là dịch thuật toán này sang ngôn ngữ máy, biến nó thành một chương trình trò chơi. Đây là công việc nặng nhọc, đòi hỏi kỹ năng lập trình, vì thời gian chạy chương trình, tức là thời gian chọn nước đi, phần lớn phụ thuộc vào chất lượng của chương trình thực hiện thuật toán. Đương nhiên, chúng tôi không thể tái tạo cấu trúc của một chương trình như vậy một cách chi tiết; chúng tôi sẽ chỉ mô tả nó bằng những thuật ngữ chung nhất.

Có sáu chương trình con $P_1$—$P_6$ (một chương trình con cho mỗi loại trò chơi). Mỗi người trong số họ biên soạn một danh sách các nước đi có thể thực hiện được từ một vị trí nhất định trong một trò chơi thuộc loại nhất định. Chương trình con $P_7$ điều phối sáu chương trình con này và viết ra tất cả các nước đi có thể thực hiện được ở một vị trí nhất định.

Ngoài các chương trình con được liệt kê, còn có một chương trình con $P_8$, thực hiện ước tính di chuyển, lấy vị trí mới, chương trình con $P_9$, tính toán ước tính

vị trí kết quả, một chương trình con $P_{10}$ thực hiện thủ tục tối thiểu và cuối cùng là chương trình điều khiển $P_0$. Cái sau quyết định chương trình con nào sẽ liên hệ, chỉ định vị trí nào được xem xét và nước đi nào được thực hiện từ đó và thực sự thực hiện thuật toán lựa chọn nước đi.

Các chương trình con $P_1$—$P_7$ có thể sử dụng thông tin phụ trợ vị trí. Vì vậy, khi xây dựng các bước đi có thể xảy ra, sẽ thuận tiện hơn khi sử dụng “raster khả năng”, đối với mỗi trò chơi được viết như sau. Một chữ số được phân bổ cho mỗi bàn cờ; đối với tất cả các bo mạch, chỉ cần chiếm hai ô nhớ, mỗi ô 32 bit là đủ. Trong các bit tương ứng với các trường mà trò chơi này có thể đi vào, 1 được đặt, các bit còn lại chứa 0.

Ví dụ: đối với vị trí hiển thị trên hình 4, raster khả năng dành cho quân Rc4 được hiển thị trên hình 5. Ô dưới cùng ở đây tương ứng với dòng dưới cùng của bàn cờ (ngang 4-1 trong thuật ngữ cờ vua).

Công việc của chương trình con $P_4$, xây dựng raster này, có thể được hình dung như sau. Trong bản ghi vị trí, chương trình con chọn bộ tứ (bốn dấu kép) tương ứng với trường liền kề trên cùng một đường ngang và phân tích nó.

Nếu bộ tứ này bằng 0 thì trường đó trống, quân xe có thể đi đến đó - nó sẽ xếp 1 vào thứ hạng tương ứng với trường này. Sau đó, nó sẽ được kiểm tra xem trường này có phải là trường ngoài cùng của bảng hay không. Nếu không thì sẽ được xem xét tiếp theo

⟦folio 21⟧

Thổi ruộng lân cận; nếu trường cực trị thì chương trình con sẽ chuyển sang hướng khác.

Nếu địa hình được chọn khác 0 thì chương trình con $P_4$ sẽ phân tích chữ số đầu tiên của nó, xác định màu của hình chiếm trường này. Nếu số này là 0 (+ dấu, hình màu trắng), thì trường đó bị chiếm bởi hình của chính nó. Chương trình con $P_4$ đặt 0 vào chữ số tương ứng của raster và tiến tới phân kỳ theo hướng mới. Khi số là 1 (dấu -, quân đen), chương trình con cũng tiến hành khám phá hướng đi mới nhưng đặt 1 vào hàng tương ứng với trường này: quân Xe có thể di chuyển đến ô này, bắt quân đen đang đứng ở đây.

Khi các bước di chuyển theo chiều ngang có thể có của một quân xe khác nhau, bạn cần chọn các địa hình từ cùng một ô. Đối với chiều dọc, bạn cần chọn các địa hình chiếm cùng một vị trí ở các ô liền kề tương ứng với các ô nằm ngang khác nhau.

Công việc của các chương trình con khác cũng dựa trên nguyên tắc tương tự. Do đó, chương trình con $P_3$, xác định các bước di chuyển của giám mục, để chọn bậc thang của trường lân cận, tạo ra sự dịch chuyển 4 bit và di chuyển đến ô lân cận. Chương trình con $P_5$ dành cho quân hậu sẽ xây dựng tất cả các nước đi có thể có cho quân xe bằng cách sử dụng chương trình con $P_4$ và tất cả các nước đi có thể có cho quân cờ bằng cách sử dụng chương trình con $P_3$, sau đó kết hợp chúng.

Thông thường, chương trình "chọn nước đi" sẽ kết thúc bằng việc chọn một nước đi để thực hiện tại một vị trí nhất định, in nước đi đó và để lại nước đi đó. Nước đi có thể được in theo mẫu được mô tả ở trên, ví dụ:

$$+2\ 10\ 22,$$

Hoặc bạn có thể sử dụng thiết bị in chữ và số và in cùng một nước đi theo hình thức tương tự như cờ vua

Đến b1 - c3.

Bây giờ không khó để tổ chức một “trận đấu đầy đủ”. Để làm được điều này, ngoài chương trình “chọn nước đi”, cần có một chương trình kết nối chương trình cờ vua “với thế giới bên ngoài”. Chương trình này phải có khả năng nhập vào máy vị trí cần chọn nước đi, các điều kiện để chọn nước đi (ví dụ: độ sâu tìm kiếm) và cung cấp khả năng kiểm soát tính chính xác của thông tin đã nhập.

Chương trình này có "doxa chính", vị trí của nó không thay đổi trong quá trình chọn nước đi, nó chỉ thay đổi sau khi nước đi được chọn và in.

Bạn không nên nghĩ rằng các phương pháp lời giải của các vấn đề chính khi lập trình một ván cờ mà chúng tôi đã mô tả là những phương pháp duy nhất. Điều này hoàn toàn không đúng, có thể có những điều khác. Bằng cách xem xét từng vấn đề một cách riêng biệt, bạn có thể tìm cách đơn giản hóa hoặc cải thiện một số chi tiết nhất định lời giải một trong số chúng, một trong số đó bị bóp méo, ảnh hưởng tiêu cực đến các phần khác của chương trình. Ví dụ: bạn có thể chọn một cách khác để ghi vị trí, nhỏ gọn hơn nhiều, tức là tiết kiệm dung lượng bộ nhớ máy tính. Nhưng việc ước tính vị trí bằng phương pháp ghi này có thể yêu cầu số lượng hành động lớn hơn nhiều. Mặc dù có thể đạt được những cải tiến “ở mọi thông số” nhưng điều đó là rất khó khăn.

Sự hình thành của ba vấn đề chính khi lập trình một ván cờ không được coi là ngang nhau và trọng số lời giải của chúng ảnh hưởng khác nhau đến chất lượng của chương trình. Nếu phương pháp sớm hơn lời giải đầu tiên

⟦folio 22⟧

và vấn đề thứ ba phần nào có thể ảnh hưởng đến thời gian chạy của chương trình nhưng hiện tại hầu như không còn dự trữ. Tình hình hoàn toàn khác với thuật toán chọn nước đi: ảnh hưởng của nó đến chất lượng và sức mạnh là quyết định.

Trong “Kanssa-72”, vấn đề này được giải quyết như sau: tất cả các tùy chọn được sắp xếp theo độ sâu 7 nửa ngày, sau độ sâu này, chỉ những cái gọi là “di chuyển bắt buộc” được sắp xếp - chụp, kiểm tra và đáp số trên chúng. Tổng độ sâu tìm kiếm thay đổi từ 7 đến 30 nửa ngày.

Người đọc có thể nhận thấy rằng với một cuộc tìm kiếm đầy đủ trong 7 nửa ngày (với trung bình 40 nước đi từ mỗi vị trí), 40⁷ vị trí sẽ phải được xem xét, thậm chí không tính những nước đi bắt buộc. Nó quá nhiều. Tuy nhiên, các tác giả của “Kanssa-72” đã làm rất tốt khi phát triển các quy tắc cho phép họ tìm ra một số vị trí hoặc chuyển động, giúp sinh vật giảm bớt việc tìm kiếm. Trên thực tế, khi tìm kiếm trong 7 tiếng rưỡi (cùng với các tùy chọn bắt buộc), khoảng 750.000 vị trí đã được xem xét, tức là máy hoạt động chưa đầy một giờ.

Trong chương trình cờ vua hay nhất của Mỹ, do Greenblatt tạo ra tại Viện Công nghệ Massachusetts, ở mỗi vị trí, 10 nước đi được xem xét, những nước “tốt nhất” theo một số đánh giá khác với đánh giá về vị trí nảy sinh sau nước đi tương ứng và tìm kiếm tùy ý, độ sâu của nước này thay đổi từ 6 đến 16 nửa ngày. Có nhiều cách khác lời giải của vấn đề này.

Tuy nhiên, bất chấp các điều kiện hiện có, vẫn chưa có thuật toán chọn nước đi nào cho phép nước đi đủ mạnh với giới hạn tự nhiên về thời gian lựa chọn. Để tìm ra một thuật toán như vậy, về cơ bản cần có những ý tưởng mới. Việc tìm kiếm những ý tưởng này đòi hỏi phải nghiên cứu chi tiết về “hành vi” của chương trình khi chọn nước đi, những nguyên nhân ảnh hưởng đến cả nước đi đã chọn và thời điểm lựa chọn. Điều này có thể được nhìn thấy trong một số lượng lớn các thí nghiệm lập trình cờ vua.
