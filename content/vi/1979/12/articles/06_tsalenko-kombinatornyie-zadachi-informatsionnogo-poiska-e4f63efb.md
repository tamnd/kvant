---
id: 1979-12-tsalenko-kombinatornyie-zadachi-informatsionnogo-poiska-e4f63efb
issue: kvant_1979_12
year: 1979
number: "12"
title: Truy xuất thông tin kết hợp bài toán
authors:
  - Цаленко М. Ш.
rubric: osnovnye-stati
page_first: 8
page_last: 14
page_labels: 6-12
tag: MD59
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 9f1e185f142978a6ae91eb26526775f576ea6916a3b290a365b4f54e4322f9f1
prompt_sha256: draft-1
translated_from: content/ru/1979/12/articles/06_tsalenko-kombinatornyie-zadachi-informatsionnogo-poiska-e4f63efb.md
source_content_sha256: 12d604c92f15ac84ccee7c48c2adb69e79db730b6515e8b9479803bf1b1d3634
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 6⟧

M. Tsalenko

Truy xuất thông tin kết hợp bài toán

Cuộc cách mạng khoa học công nghệ hiện nay đang diễn ra ở các nước công nghiệp phát triển có liên quan mật thiết đến sự xuất hiện và phát triển của máy tính điện tử (máy tính). Máy tính hiện đại có thể thực hiện hàng triệu phép tính số học mỗi giây. Tuy nhiên, máy tính cũng đang xâm chiếm các lĩnh vực hoạt động của con người, nơi không có những phép tính lớn và phức tạp và khác xa với toán học. Khoa học thư viện cung cấp một ví dụ mang tính hướng dẫn. Hiện tại, người ta đã giải thích được tại sao máy tính bắt đầu được sử dụng rộng rãi trong thư viện và những điều thú vị cũng như khó khăn về toán học. bài toán phát sinh cùng một lúc.

1. Truy xuất thông tin là gì?

Các thư viện lớn hiện đại chứa hàng triệu cuốn sách, tạp chí, báo và các tài liệu in khác. Để không bị nhầm lẫn trong bộ sưu tập tài liệu khổng lồ này, nhân viên thư viện tạo ra một hệ thống tham khảo từ các danh mục có thẻ chú thích.

Telery tưởng tượng một độc giả đến thư viện để đọc một cuốn sách nổi tiếng nào đó về các phương trình lời giải trong căn thức. Anh ta có thể biết rằng nhiều nhà toán học đã nghiên cứu bài toán khó này và lời giải của nó gắn liền với tên của Abel và Galois, nhưng trình độ toán học của anh ta không đủ để đọc các bài toán đặc biệt.

⟦folio 7⟧

văn học. Do đó, sự xuất hiện của độc giả của chúng tôi trong thư viện dẫn đến cái gọi là yêu cầu thông tin: “TÌM TÀI LIỆU PHỔ BIẾN VỀ GIẢI PHƯƠNG PHÁP TRONG RADICALAX,” và trước khi người đọc thỏa mãn trí tò mò của mình, anh ta phải quyết định bài toán tìm kiếm thông tin: trong số tất cả những cuốn sách được lưu trữ trong thư viện, hãy tìm cuốn sách khiến anh ta hài lòng nhất. Đây là lúc hệ thống danh mục phát huy tác dụng. Trong danh mục chuyên đề, anh ta sẽ tìm thấy một phần chứa danh sách các sách về toán học và bên trong nó - một phần chứa danh sách các sách về đại số. Và trong số các thẻ danh mục của phần này, bạn cần chọn những thẻ chỉ ra tài liệu mà bạn đang tìm kiếm.

Bây giờ chúng ta hãy thực hiện một số phép tính đơn giản. Giả sử rằng bạn chỉ mất trung bình 20 giây để làm quen với thẻ. Điều này có nghĩa là đầu đọc hoạt động rất nhanh: ước tính mất khoảng 10 giây để thực hiện một phép tính số học. Nếu người đọc phải xem qua 200 tấm thẻ, anh ta sẽ dành khoảng 67 phút chỉ để chọn lọc tài liệu mà mình quan tâm. Sự luân chuyển này là một phần không tự nguyện của quá trình tìm kiếm thông tin chung mà độc giả quan tâm. Bản thân quá trình này được gọi là truy xuất thông tin; Tính toán cho thấy khi tìm kiếm thông tin bằng danh mục, một phần thời gian đáng kể được sử dụng không hiệu quả. Vì độc giả của các thư viện lớn nhất ghé thăm hàng trăm thành phố trong một ngày và yêu cầu thông tin của họ có thể phức tạp hơn trong ví dụ trên, thời gian không tự nguyện dành cho việc tìm kiếm thông tin được biểu thị bằng hàng trăm và hàng nghìn giờ.

Để minh họa sự phức tạp của việc truy xuất thông tin, chúng ta hãy đưa ra một con số nữa. Hiện nay có hơn 750 tạp chí và tạp chí định kỳ khác trên khắp thế giới chỉ chuyên viết về công nghệ máy tính. Điều này có nghĩa là trong năm có mười nghìn bài báo được xuất bản bằng nhiều ngôn ngữ khác nhau, chiếm hàng trăm nghìn trang in, chỉ liên quan đến một lĩnh vực hoạt động của con người. Tuy nhiên, lĩnh vực này phù hợp với các chuyên gia thuộc nhiều chuyên ngành khác nhau: kỹ sư, nhà vật lý, nhà hóa học, nhà toán học, nhà xã hội học, nhà triết học và nhiều người khác. Rất khó để hiểu được dòng chảy văn học ngày càng tăng, tìm kiếm những thông tin cần thiết, sử dụng nó trong công việc của bạn và không lặp lại công việc đã hoàn thành. Hệ thống danh mục hóa ra là không đủ và các viện thông tin đặc biệt đang được thành lập ở nhiều nước trên thế giới.

2. Máy tính và truy xuất thông tin

Một tính năng đáng chú ý của máy tính là khả năng “đọc” và so sánh các từ để xác định xem chúng giống hay khác nhau. Thực tế là để viết bất kỳ từ nào trong tiếng Nga, bạn chỉ cần tạo thành 33 chữ cái. Mặt khác, máy tính có thể dễ dàng nhận ra chuỗi số 1 và số 0. Chúng ta hãy xem xét, như thông lệ trong nhiều máy tính hiện đại, tất cả các chuỗi số 1 và số 0 có cùng số lượng số hạng trong tất cả chúng. Ví dụ: điều này cũng sẽ bao gồm các trình tự:

00000000, 01010101, 11110000
(để ngắn gọn, không đặt dấu phẩy giữa các thành viên của chuỗi).

Vì mỗi dãy có chính xác tám số hạng và bất kỳ số hạng nào cũng bằng 0 hoặc một, nên tổng số dãy được xem xét là 2⁸=256. Chúng ta thống nhất viết cùng nhau các chữ cái đầu tiên a, b, c, 2, d, e của bảng chữ cái tiếng Nga theo trình tự:

10000000, 11000000, 11100000, 11110000, 10100000, 10010000

Chúng tôi nhấn mạnh rằng chúng tôi coi mỗi chuỗi là một chứ không phải tám ký tự. Giờ đây, với sự trợ giúp của các ký hiệu mới, bạn có thể viết các từ theo cách mà chúng có thể được

⟦folio 8⟧

"nhận dạng" máy tính. Ví dụ, từ
vấn đề sẽ như thế này:
1100000 10010000 10100000 10000000

Tất nhiên, phương pháp ghi này bất tiện cho con người nhưng nó cho phép máy tính “đọc”. Đồng thời, máy có thể đọc văn bản bằng nhiều ngôn ngữ, vì nó có thể ghi nhớ 256 chuỗi không chỉ các chữ cái tiếng Nga mà còn cả các số, chữ cái Latinh và nhiều ký tự đặc biệt, chẳng hạn như ký hiệu số học.

Sau khi dạy một người đọc, một chiếc máy ngay lập tức vượt qua anh ta về tốc độ đọc: nếu một người cần 67 phút để đọc 200 thẻ mục lục, thì máy tính sẽ xử lý công việc này trong vài giây. Khi đọc, máy có thể so sánh hai văn bản, xác định sự hiện diện của các từ hoặc cách diễn đạt phổ biến trong đó, xác định nghĩa của từng từ riêng lẻ, v.v.

Tuy nhiên, các ngôn ngữ tự nhiên (tiếng Nga, tiếng Anh, tiếng Đức hay bất kỳ ngôn ngữ nào khác) rất khó để máy “hiểu” được: mọi suy nghĩ trong đó đều có thể được diễn đạt bằng nhiều cách. Vì vậy, ngôn ngữ học đang phát triển các ngôn ngữ nhân tạo, được gọi là ngôn ngữ tìm kiếm thông tin, không có nhược điểm này.

Phần chính của thông tin của các ngôn ngữ tìm kiếm là tập hợp các khái niệm, thuật ngữ, cụm từ được sử dụng liên tục trong một lĩnh vực chủ đề cụ thể - trong toán học, hóa học, sinh học, v.v. Khi biên soạn phần tóm tắt của một cuốn sách hoặc phần tóm tắt của một bài báo khoa học, có thể cùng với ngôn ngữ tự nhiên được đề xuất để đưa ra danh sách các thuật ngữ phản ánh rõ nhất nội dung của cuốn sách hoặc bài báo. Điều tương tự có thể được thực hiện với các yêu cầu thông tin từ độc giả. Ví dụ, trong loạt bài “Bài giảng phổ biến về toán học”, một tập tài liệu “Phương trình đại số ở cấp độ cao hơn” của A. G. Kurosh đã được xuất bản. Tóm tắt của nó có thể được viết như sau:

Số phức, lời giải tính theo bán kính của phương trình bậc hai và bậc ba, định lý Abe

về tính không giải được bán kính của phương trình tổng quát của đường thẳng, xấp xỉ, tính nghiệm, nhóm, cọc, trường.

Bản tóm tắt bài viết của B. N. Delaunay “Đại số (lý thuyết về phương trình đại số)”, được đặt trong tập đầu tiên của tác phẩm tổng hợp ba tập “Matematika, nội dung, phương pháp và ý nghĩa của nó”, có thể trông như thế này:

Lời giải trong các bán kính của phương trình bia dưới, công thức Cardnot, định lý Abey về tính không giải được trong bán kính của phương trình tổng quát của bia thẳng, định lý Galois, vị trí các nghiệm của phương trình trên mặt phẳng phức, định lý cơ bản của đại số, phép tính gần đúng, tính nghiệm.

Bây giờ chúng ta hãy nhớ đến độc giả muốn nhận tài liệu về các phương trình lời giải theo bán kính. Yêu cầu của ông có thể được mô tả như sau:

Lời giải trong các bán kính của phương trình cấp dưới, Định lý Abey về tính không giải được trong bán kính của phương trình tổng quát của cấp thẳng.

So sánh truy vấn với hai chú thích trên cho thấy hầu hết tất cả các cụm từ gặp trong đó đều được đưa vào chú thích. Do đó, với khả năng cao có thể cho rằng tập tài liệu của A. G. Kurosh và các bài báo của B. N. Delaunay chứa đựng những thông tin khiến người đọc quan tâm.

Bây giờ đã rõ phần nào của việc tìm kiếm thông tin có thể được chuyển sang máy tính: máy phải kiểm tra xem các thuật ngữ và cụm từ của truy vấn có chứa trong chú thích của một cuốn sách hoặc bài báo được lưu trữ trong thư viện hay không. Các thuật ngữ, khái niệm, cụm từ trong tìm kiếm thông tin được gọi là từ khóa.

3. Máy tính phải được sử dụng hiệu quả

Bây giờ chúng ta hãy xem xét kỹ hơn việc thực hiện các thao tác trên máy tính. Mỗi máy tính hiện đại đều có bốn chương

⟦folio 9⟧

thành phần duy nhất: bộ xử lý trung tâm, RAM, bộ nhớ ngoài và thiết bị vào/ra. Bộ xử lý trung tâm điều khiển hoạt động của toàn bộ hệ thống và các phép tính số học và logic được thực hiện trong đó và một thao tác duy nhất mất một phần triệu giây. Dữ liệu (số, từ) mà bộ xử lý hoạt động được đặt trong RAM. Nó có khối lượng tương đối nhỏ vì giá thành của nó rất cao.

Hãy để chúng tôi nhắc bạn rằng việc viết một ký tự đơn (chữ cái, số, thuật toán ký hiệu đặc biệt) yêu cầu một chuỗi gồm tám chữ cái và số không. Trong RAM của những máy tính hoàn hảo, thường có thể ghi được 256.000 hoặc 512.000 chuỗi hoặc ký tự như vậy. Nó nhiều hay ít? Như thực tế cho thấy, một thẻ thư mục cùng với chú thích chứa 1000-1500 ký tự. Vì vậy, tối đa khoảng 500 thẻ có thể được lưu trữ trong RAM. Rõ ràng là con số này rất ít.

Các thẻ còn lại được đặt trong bộ nhớ ngoài, dung lượng của nó lớn hơn dung lượng RAM hàng trăm lần. Tuy nhiên, quá trình truyền dữ liệu mất nhiều thời gian hơn hàng nghìn lần so với công việc của bộ xử lý trung tâm, bộ xử lý trung tâm đã không thành công trong quá trình truyền dữ liệu đến thiếu niên. Rõ ràng là việc truyền dữ liệu không liên quan trực tiếp đến việc tiêu thụ thông tin và là một sự lãng phí thời gian không thể xác định được. Do đó, bài toán nảy sinh về việc giảm số lượng truy cập vào bộ nhớ ngoài. Có nhiều cách tiếp cận khác nhau đối với lời giải của nó. Tuy nhiên, từ chúng dẫn đến phép toán đỏ và khó bài toán, sẽ được thảo luận ở phần kết luận.

4. Làm sao để giảm “sức nặng” của nhiều từ?

Đặt $A$ là một tập hợp các phần tử $n$. Các phần tử sẽ được biểu thị bằng các chữ cái Latinh nhỏ $a, b, c, \dots$. Chúng ta sẽ gọi một tập hợp con tùy ý gồm các phần tử từ $A$ là một “từ” và cùng với ký hiệu truyền thống $\{a, b, c, d\}$, chúng ta sẽ viết một $abcd$ đơn giản; được đặt, với thành công như nhau, bạn có thể viết $bdac$ hoặc $dcab$, v.v. Một từ không có chữ cái, tức là một từ trống, sẽ không được xem xét. Vì vậy chỉ có $2^n - 1$ từ.

Để kết nối với những cân nhắc trước đó, chúng tôi chỉ ra rằng chúng tôi đã bắt đầu sử dụng các chữ cái để biểu thị các từ khóa của ngôn ngữ tiếng Nhật thông tin, tức là các thuật ngữ, khái niệm, cụm từ. Số lượng của chúng có thể rất lớn, chẳng hạn như khoảng 10.000. Tập hợp từ khóa có thể là một bản tóm tắt hoặc một yêu cầu thông tin.

Giả sử rằng một tập hợp từ $M$ nhất định nằm trong bộ nhớ ngoài $EBM$ và cần tìm tất cả các từ từ $M$ trong đó xuất hiện các chữ cái $a, b$ và $c$. Để đối phó với nhiệm vụ này, bạn cần phải “đọc” từng từ một từ $M$, sau khi sao chép chúng vào RAM trước. Nếu $M$ không xác định thì toàn bộ tập hợp $M$ có thể được di chuyển đến đó cùng một lúc. Trong trường hợp chung, chuyển động như vậy được thực hiện theo từng phần, kích thước của nó được xác định trước. Do đó, số lượng cuộc gọi có kích thước $M$ và kích thước của phần được truyền. Con số này có thể giảm đi nếu các từ có chữ cái $a, b$ và $c$ được viết riêng khi đặt các từ vào bộ nhớ ngoài. Tuy nhiên, đối với bài toán: tìm tất cả các từ có chữ cái $b, c$ và $d$ - việc tiếp tục là vô ích.

Tuy nhiên, việc sắp xếp trước các từ khi ghi chúng vào bộ nhớ ngoài hóa ra lại hữu ích nếu bạn không chỉ nghĩ đến một truy vấn mà là tất cả các truy vấn có thể có. Chúng tôi sẽ chia khối lượng của bộ $M$ thành các phần và đặt từng phần vào một phong bì riêng, và trên phong bì chúng tôi sẽ liệt kê tất cả các chữ cái được tìm thấy ở các vị trí trong các từ trong phong bì. Bây giờ, khi tìm kiếm các từ có các chữ cái $a, b$ và $c$, các phong bì chứa các chữ cái này bắt đầu được tra cứu và sau đó các từ trong các phong bì này được đọc. Các từ trên phong bì phải được đặt sao cho tổng số phong bì “đã mở” trong

⟦folio 10⟧

trong số tất cả các truy vấn có thể hóa ra lại là ví dụ đơn giản nhất. Giả sử tập hợp $M$ chỉ bao gồm ba từ $ab, ac$ và $bc$ và các truy vấn chúng ta sẽ thực hiện phải là các tập hợp con không trống của tập hợp $\{a, b, c\}$. thì tổng số yêu cầu là bảy. Đầu tiên chúng ta hãy đặt mỗi từ vào một phong bì riêng. Sau đó, phong bì có chữ $ab$ sẽ mở ra ba lần: khi tìm kiếm từ $a$, từ $c$ và từ $a$ và $b$. Vì tất cả các phong bì đều bằng nhau nên tổng số được mở là 9. Bây giờ, hãy đặt các từ $ab$ và $ac$ vào một phong bì và từ $bc$ vào phong bì kia. Trong trường hợp này, phong bì thứ nhất được mở bảy lần, phong bì thứ hai vẫn được mở ba lần và tổng số lần mở là 10.

Cuối cùng, hãy bỏ tất cả các từ vào một phong bì. Khi đó tổng số được mở là 7: với mỗi yêu cầu bạn cần mở một phong bì và có tổng cộng 7 yêu cầu. Vì vậy, trong ví dụ của chúng tôi, tốt nhất nên giữ $M$ trong một phong bì. (Kết quả có thay đổi không nếu các từ $a$ và $abc$ được thêm vào $M$ hoặc các từ $bc$ bị xóa khỏi $M$?)

Bây giờ chúng ta đã sẵn sàng xem xét tổng quát bài toán. Đặt $M$ là một tập hợp các từ tùy ý. Số $k$ của các chữ cái khác nhau xuất hiện trong các từ từ $M$ được gọi là mức đặt $M$ và được ký hiệu là $l(M)$. Ví dụ, nếu

$$M = \{abc, bcd, cde, dea, eab\},$$

(1) thì cấp $M$ bằng 5.

Trọng lượng của bộ $M$ là số $2^l(M) - 1$. Trong ví dụ trên, tất cả $M$ bằng 31. Rõ ràng, tất cả $M$ bằng số từ có thể được tạo thành từ các chữ cái $l(M)$.

Vấn đề nảy sinh khi cố gắng giảm số lượng truy cập vào bộ nhớ ngoài của máy tính có thể được hình thành như sau: đối với bất kỳ tập hợp từ $M$ nào, chỉ định phương pháp phân vùng nó thành các tập hợp con rời rạc $S_1, S_2, \dots, S_k$ sao cho tổng của các trọng số

$$P = (2^l(S_1) - 1) + \dots + (2^l(S_k) - 1) = \sum_{i=1}^{k} (2^l(S_i) - 1)$$

là nhỏ nhất.

⟦folio 11⟧

các trường hợp khác nhau của cùng một khối tối thiểu. Trong tương lai, những khối như vậy sẽ có quyền bình đẳng đối với chúng tôi.

Bây giờ chúng ta hãy chứng minh một trong những định lý đưa ra ý tưởng về cấu trúc của các khối tối thiểu.

Định lý. Các khối tối thiểu cấp 5, bao gồm các từ có ba chữ cái, được giới hạn trong danh sách sau, tối đa thay thế chữ cái:

$$S_1 = \{abc, bcd, cde, dea, eab\};$$
$$S_2 = \{abc, abd, abe, acd, ace, ade\};$$
$$S_3 = \{abc, abd, abe, acd, ace, bde\}.$$

Bằng chứng. Mỗi từ gồm ba chữ cái có trọng số $2^3 - 1 = 7$. Tất cả tập hợp bất kỳ ở cấp 5 đều bằng 31. Do đó, bất kỳ khối nào ở cấp 5 đều chứa ít nhất năm từ: nếu không thì tổng trọng số của từng từ sẽ nhỏ hơn 31.

Hơn nữa, trong bất kỳ khối cấp 5 nào, mỗi chữ cái phải xuất hiện ít nhất ba lần. Trên thực tế, chữ trống $a$ xuất hiện ít hơn ba lần. thì tất cả các tập hợp từ không chứa $a$ không vượt quá 15 và tổng trọng số của các từ $a$ không vượt quá 14. Điều này có nghĩa là tổng trọng số nhỏ hơn 29, điều này mâu thuẫn với định nghĩa của một khối.

Bây giờ chúng ta hãy xem xét hai trường hợp.

Trường hợp 1. Khối tối thiểu $S$ chứa năm từ. Vì số lượng tất cả các chữ cái trong $S$ là 15 nên theo nhận xét trước đó, mỗi chữ cái xuất hiện đúng ba lần. Để dễ dàng tính toán, chúng tôi xin giới thiệu một bảng trao đổi hình vuông $5 \times 5$, trong cột đầu tiên sẽ viết chữ cái $a$, trong cột thứ hai - $b$, v.v. (xem bảng 1a-1b).

Giả sử rằng một cặp chữ cái nhất định, chẳng hạn như $a$ và $b$, chỉ xuất hiện một lần. Sau đó nảy sinh tình huống được mô tả trong bảng 1a. Chúng ta hãy biểu thị bằng $c$ chữ cái có trong từ đầu tiên. Chữ cái này phải gặp $a$ và $b$ một lần nữa: nếu nó gặp $a$ hai lần nữa thì hai hàng cuối cùng của bảng sẽ chứa cùng một từ, điều này là không thể. Vì vậy, từ bảng 1a chúng ta chuyển sang bảng 16.

Rõ ràng là các từ ade và bde cần được đặt ở hàng thứ ba và thứ năm của bảng. Nhưng sau đó bạn nên đặt $d$ (hoặc $e$) ở dòng thứ hai và $e$ (hoặc $d$) ở dòng thứ tư; do tính đối xứng giữa $a$ và $b$ trên bảng 16 nên cả hai khả năng đều bằng nhau. Bảng 1c cung cấp một ứng cử viên cho khối tối thiểu. Tập hợp các từ được xây dựng $S$ là một khối tối thiểu thực sự, vì bất kỳ tập hợp con nào gồm ba từ đều có trọng số là 31. Nó trở thành $S_1$ nếu $d$ được thay thế bằng $e$, $e$ bằng $a$ và $a$ bằng $d$.

Không có cặp chữ cái nào có thể xuất hiện ba lần, vì không có đủ chữ cái cho từ thứ năm; Vì vậy, chúng ta chỉ có thể giả định rằng mỗi cặp chữ cái sẽ xuất hiện hai lần. Tuy nhiên, tùy chọn này cũng không thể thực hiện được: các chữ cái $a$, $b$ và $c$ chỉ có thể được đặt như trong Bảng 2 và không có đủ chữ cái cho từ cuối cùng.

Trường hợp 2. Khối tối thiểu $S$ chứa sáu từ. Sau đó bằng lời nói

Bảng 2.

⟦folio 12⟧

Chỉ có 18 chữ cái từ $S$. Số 18 có thể được biểu diễn theo các cách sau dưới dạng tổng của năm số hạng, mỗi số hạng bằng 3, 4, 5 hoặc 6:
a) $18=6+3+3+3+3$;
b) $18=5+4+3+3+3$;
c) $18=4+4+4+3+3$.

Trong phương pháp a) một chữ cái, ví dụ $a$, sẽ xuất hiện sáu lần. Vì vậy $S$ giống với $S_2$; Chúng tôi giả sử rằng người đọc có thể chứng minh độc lập rằng $S_2$ là khối tối thiểu.

Hãy chuyển sang phương pháp 6). Để xác định, hãy để đường dẫn gặp chữ cái $a$ một lần và chữ cái $b$ bốn lần. thì ta được ngay bảng 3a. Ở dòng bốn và năm, một trong các chữ cái: $c$, $d$ hoặc $e$ xuất hiện hai lần; hãy biểu thị nó bằng $c$. Dòng thứ sáu chỉ có thể chứa từ $bde$ và kết quả là chúng ta đến bảng 36.

Bảng 3a. Bảng 36.

Để chứng minh rằng tập hợp từ $S_3$ được xây dựng là một khối, cần lưu ý rằng trong $S$ bất kỳ tập hợp con cấp 4 nào cũng chứa không quá ba từ và các từ còn lại tạo thành tập hợp con cấp 5 và do đó tổng trọng số không thể nhỏ hơn $36=15+7\times 3$ và trọng số của $S$ bằng 31. Tính tối thiểu xuất phát từ thực tế là, bất kể từ nào bị loại bỏ, các từ còn lại chứa một chữ cái $a$ sẽ xuất hiện ít nhất bốn lần, điều này không thể xảy ra ở khối từ thứ năm Cấp 5 do trường hợp đầu tiên.

Hãy chuyển sang phương pháp b). Để các chữ cái $a$, $b$ và $c$ xuất hiện bốn lần mỗi chữ cái. thì một số cặp chữ cái này sẽ xuất hiện ba lần hoặc bất kỳ cặp chữ cái nào sẽ xuất hiện đúng hai lần. Theo đó, chúng ta đến bảng 4a và 46 (có thể thay đổi các chữ cái).

Cấu trúc đầu tiên của bộ này là một khối, nhưng không phải là khối tối thiểu: sau khi xóa từ $abc$ khỏi nó, bạn sẽ nhận được một khối loại $S_1$. Tập thứ hai hoàn toàn không phải là một khối, vì nó là tập hợp của các tập con cấp 4 {abd, acd, bcd} và {abe, ace, bce} và đối với phân vùng này, tổng các trọng số là $30<31$.

Bây giờ cần phải chứng minh rằng không có khối tối thiểu nào khác ở cấp độ 5 bao gồm ba từ chữ cái. Nếu bộ $S$ chứa chín hoặc mười từ thì ít nhất một chữ cái sẽ xuất hiện sáu lần và do đó $S$ chứa một khối loại $S_2$. Điều này có nghĩa là $S$ luôn là khối tối thiểu.

Nếu có bảy hoặc tám từ trong $S$ và không có một chữ cái nào xuất hiện sáu lần thì sẽ luôn có một cặp chữ cái, chẳng hạn như $a$ và $b$, sao cho $a$ sẽ xuất hiện năm lần, $b$ ít nhất bốn lần và cặp $a$, $b$ sẽ xuất hiện ba lần (kiểm tra!). Do đó, hãy cân nhắc (hãy đảm bảo điều này!) rằng $S$ bao gồm năm từ sau: $abc$, $abd$, $abe$, $acd$, $ace$. Đối với chúng, bạn phải thêm ít nhất hai từ trong số bốn từ sau: $bcd$, $bce$, $bde$, $cde$. Nếu một trong các từ $bde$ hoặc $cde$ được thêm vào thì $S$ sẽ chứa một khối loại tối thiểu $S_3$. Nếu các từ $bcd$ và $bce$ được thêm vào thì các từ trong $S$ sẽ không chứa cặp chữ cái $d$ và $e$, không thể có trong khối (xem bên dưới bài toán 3).

Nhiệm vụ 1.
1. Mô tả tất cả các khối tối thiểu của cấp 5 bằng hai từ chữ cái.
2. Tập hợp $S'$ được lấy từ tập hợp $S$ bằng cách thêm chữ cái mới nhất vào chúng. Chứng minh rằng nếu $S$ là khối tối thiểu thì $S'$ là khối tối thiểu.
3. Nếu các từ của khối $S$ chứa các chữ cái $a$ và $b$ thì trong $S$ có một từ chứa $a$ và $b$.

4.**. Mô tả tất cả các khối tối thiểu của cấp độ 6 và 7 từ ba chữ cái.
5*. Chứng minh rằng không có khối từ cấp 8 nào có ba chữ cái.
