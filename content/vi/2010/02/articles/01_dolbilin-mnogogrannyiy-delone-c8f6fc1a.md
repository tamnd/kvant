---
id: 2010-2-dolbilin-mnogogrannyiy-delone-c8f6fc1a
issue: kvant_2010_2
year: 2010
number: "2"
title: Delaunay nhiều mặt
authors:
  - Долбилин Н. П.
rubric: osnovnye-stati
page_first: 4
page_last: 11
page_labels: 2, 3, 6, 7, 8, 9
tag: 7G20
lang: vi
source: kvant_digital
extraction: native
content_sha256: fbaa8a63e6bd8f2d50fc6659b1d25ab048debcced5a0c6719bdb74bb5d0625ba
prompt_sha256: draft-1
translated_from: content/ru/2010/02/articles/01_dolbilin-mnogogrannyiy-delone-c8f6fc1a.md
source_content_sha256: f1781319110ebd105eb9efa0ff0c5908f5dfe4778da3fbce8684efcb982ea4ca
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

KVANT 2010/№2

Delaunay nhiều mặt

N. DOLBILIN

Phương pháp hình cầu rỗng và tam giác Delaunay

Boris Nikolaevich Delaunay là một nhà phổ biến khoa học đáng chú ý. Đồng thời, ông tuân thủ nguyên tắc: mọi bài báo phổ biến về toán học phải có bằng chứng của ít nhất một tuyên bố. Chúng tôi sẽ tuân theo nguyên tắc này và trình bày bằng chứng những ý tưởng chính của một lý thuyết hình học rất hữu ích - lý thuyết về ốp lát Delaunay. Lý thuyết này được ông nêu ra vào đầu những năm 20 trong tác phẩm “Trên quả cầu trống”. Trong một số trường hợp đặc biệt, ý tưởng về một phân vùng như vậy đã từng được đề cập đến, chẳng hạn như trong các tác phẩm của Voronoi. Công lao của Boris Nikolaevich là ông, với sự rõ ràng và minh bạch đặc trưng của mình, đã mô tả cách xây dựng hình học đơn giản này cho một lớp tập hợp rất tổng quát. Bây giờ chúng tôi sẽ giải thích những ý tưởng chính của khoa học này - để đơn giản, chỉ trên một mặt phẳng, mặc dù lý thuyết này có thể dễ dàng được chuyển sang không gian ở bất kỳ chiều nào. Chúng ta hãy xem xét một tập hợp điểm X nhất định trên mặt phẳng. Các điểm của tập X để phân biệt chúng với các điểm khác trên mặt phẳng không thuộc X sẽ được gọi là các nút. Giả sử rằng tập X của các nút thỏa mãn hai điều kiện sau. Có hai số dương r và R sao cho (1) bất kỳ đường tròn bán kính r nào chứa bên trong nó nhiều nhất một nút từ X; (2) bất kỳ đường tròn nào có bán kính R chứa bên trong chính nó hoặc trên ranh giới của nó ít nhất một nút từ X. Delaunay gọi tập hợp đó là hệ thống X (r, R). Nhân tiện, điều này không thành công lắm, tên đã được đổi thành tập Delaunay (với tham số r và R). Rõ ràng là các điều kiện (1) và (2) tương đương với các điều kiện $( 1 ' )$ khoảng cách giữa các nút ít nhất là 2r và $( 2 ' )$ khoảng cách từ bất kỳ điểm nào trong mặt phẳng đến nút gần nhất trong X không vượt quá R. Thông thường, một định nghĩa tương đương khác về tập Delaunay hóa ra lại hữu ích. Chúng ta sẽ xem xét các đường tròn chỉ có tâm tại các nút từ X. Sau đó, các điều kiện (1) và (2) có thể được định dạng lại: $( 1 '' )$ các đường tròn có bán kính r với tâm tại các nút từ X không trùng nhau theo cặp, tức là tạo thành một gói (hình 1); $( 2 '' )$ các vòng tròn bán kính R có tâm tại các nút từ X bao phủ toàn bộ mặt phẳng, tức là tạo thành một lớp phủ. Nói cách khác, mọi điểm trên mặt phẳng đều thuộc ít nhất một trong các đường tròn này. Dễ dàng thấy rằng, do điều kiện (2) nên số lượng tất cả các nút trong tập Delaunay là vô hạn.

Kết thúc. Để bắt đầu, hãy xem «Kvant» Số 1.

01-.p65

⟦column⟧

Lưu ý rằng các tham số r và R được chỉ định một cách mơ hồ: từ điều kiện (1) và (2) rõ ràng là tập X thỏa mãn cùng điều kiện (1) và (2) cho mọi giá trị của $r '$ và $R '$, nếu $0 < r ' \le r$ và $R ' \ge R$. Bây giờ, theo Boris Nikolaevich, chúng ta hãy tiến hành $по-^{Рис.} 1$ việc dựng một số phân chia đặc biệt của mặt phẳng thành các đa giác, liên kết duy nhất với tập X. Phân chia mặt phẳng là một thuật ngữ hơi mới, mặc dù ý nghĩa của thuật ngữ này giống với ý nghĩa của một sự kiện đã biết từ thời thơ ấu: làm vỡ kính. Toàn bộ tấm kính được vỡ thành các mảnh mà từ đó có thể tạo ra tổng thể, trong khi các mảnh riêng lẻ không chồng lên nhau $друга.^{1}$ Việc chia một mặt phẳng thành đa giác là một tập hợp các đa giác $M_{1}, M_{2}$, v.v., do đó nằm trên mặt phẳng sao cho (a) không có hai đa giác nào chồng lên nhau (điều kiện đóng gói) và (b) các đa giác ghép lại với nhau bao phủ toàn bộ mặt phẳng (lớp phủ có điều kiện). Sàn gỗ, gạch trên tường, khảm Penrose (hình2) - tất cả đều là những mảnh vỡ giới hạn của phân vùng của mặt phẳng (vô hạn). Bây giờ chúng ta hãy trình bày ý tưởng về “quả cầu trống”, thuộc về Boris $Ни-^{Рис.} 2$ Kolaevich Delaunay. Bước thứ 0. Chúng ta hãy xét mặt phẳng nơi tập hợp X tọa lạc một đường tròn nhỏ, chẳng hạn có bán kính nhỏ hơn r, không nằm trong cũng như không nằm trên biên

1 Sự so sánh này, giống như bất kỳ sự so sánh nào nói chung, còn lâu mới hoàn hảo.

⟦folio 3⟧

ĐA NĂNG

chứa các nút từ X. Một vòng tròn như vậy tồn tại vì khoảng cách giữa các nút ít nhất là 2r. Bước 1. Để tâm $O_{1}$ của hình tròn bất động, chúng ta tăng bán kính của nó, để trống các nút bên trong, cho đến khi ranh giới của hình tròn phồng gặp một số nút x từ X. Một khoảnh khắc như vậy chắc chắn sẽ xảy ra, vì theo điều kiện (2) bán kính của hình tròn trống không vượt quá R (hình3).

DELAUNAIS

⟦column⟧

Lưu ý rằng sau bước thứ ba, một số k nút nhất định, $k \ge 3$, nằm trên đường tròn ranh giới của vòng tròn. Hãy xây dựng một k-giác có các đỉnh tại k nút đã cho (hình6). Rõ ràng là đa giác này

⟦figure⟧

Hình 6

⟦figure⟧

Hình 3

Bước thứ 2. Bây giờ, không xóa vòng tròn khỏi nút x, chúng ta di chuyển tâm của vòng tròn mở rộng ra khỏi nút x dọc theo một đường thẳng $xO_{1}$ cho đến khi nó chạm vào nút y khác (hình4). Một khoảnh khắc như vậy chắc chắn sẽ đến do điều kiện (2). Chúng ta hãy biểu thị tâm của vòng tròn này bằng $O_{2}$.

⟦figure⟧

Hình 4

Bước thứ 3. Không xóa đường tròn khỏi các nút x và y, chúng ta sẽ xóa tâm của nó khỏi các nút x và y dọc theo đường trung tuyến vuông góc với đoạn xy cho đến khi vòng tròn mở rộng gặp một nút z khác (hình5).

⟦figure⟧

Hình 5

Điều này hoàn thành quá trình mở rộng vòng tròn. Chúng ta hãy biểu thị đường tròn cuối cùng là K và tâm của nó là O.

01-.p65

được nội tiếp trong một đường tròn không có nút nào khác từ X cả bên trong hoặc trên đường biên $содержит.^{2}$ Đa giác M được gọi là đa giác Delaunay cho tập X gồm các nút cho trước nếu các đỉnh của nó là các nút từ X và nó được nội tiếp trong một đường tròn K nào đó không chứa bất kỳ nút nào khác ngoại trừ các đỉnh bên trong hoặc trên đường biên. K-giác thu được nhờ “bốn nước đi” được mô tả ở trên là đa giác Delaunay. Như vậy, tập đa giác Delaunay không rỗng. Hơn nữa, dễ dàng nhận thấy rằng bằng cách áp dụng “bốn bước di chuyển” cho các đường tròn nhỏ được lấy ở các phần khác nhau của mặt phẳng, người ta có thể thu được vô số đa giác Delaunay. Lưu ý rằng bất kỳ nút nào trong X đều là đỉnh của ít nhất một trong các đa giác Delaunay. Một đa giác như vậy có thể được xây dựng bằng cách di chuyển bốn bước áp dụng cho một vòng tròn nhỏ khá gần với nút đã cho. Boris Nikolaevich đã chứng minh một định lý không phức tạp lắm nhưng quan trọng: Định lý. Tập hợp tất cả các đa giác Delaunay cho một tập hợp nút X cho trước tạo thành một phân vùng của mặt phẳng. Bằng chứng. Hãy nhớ lại rằng tập hợp các nút X thỏa mãn điều kiện (1) và (2). Trước tiên chúng ta hãy chứng minh rằng không có hai đa giác Delaunay $M_{1}$ và $M_{2}$ trùng nhau, tức là không có điểm chung bên trong. Lấy các vòng tròn "trống" $K_{1}$ và $K_{2}$, được mô tả tương ứng xung quanh $M_{1}$ và $M_{2}$. Không có vòng tròn nào trong số này được chứa trong vòng tròn kia, vì mỗi vòng tròn trong số chúng đều trống các nút từ X bên trong và mỗi vòng tròn chứa một số lượng nút nhất định trên đường biên. Nếu các vòng tròn $K_{1}$ và $K_{2}$ không trùng nhau thì các đa giác $M_{1}$ và $M_{2}$ chứa trong chúng không trùng nhau. Để các vòng tròn chồng lên nhau dọc theo một số “thấu kính” (hình7), bao gồm cung $a_{1}$ của vòng tròn thứ nhất đi vào bên trong vòng tròn thứ hai

2 Một độc giả chú ý có thể đã nhận thấy rằng ngay ở bước đầu tiên, vòng tròn mở rộng có thể đã gặp không phải một mà là hai hoặc thậm chí nhiều nút. Lưu ý rằng trong trường hợp này, chúng ta có thể chuyển trực tiếp từ bước 1 sang bước 3 hoặc thậm chí lấy vòng tròn cuối cùng K.

⟦folio 6⟧

KVANT 2010/№2

mo, trong đó, theo chính Delaunay, ông đã báo cáo rằng ông đã nghiên cứu những vách ngăn này từ những năm 1920. Năm 1924, Delaunay yêu cầu học giả $В.А.Стеклова^{4}$, người đang tham dự Đại hội các nhà toán học quốc tế ở Toronto, báo cáo về công trình của mình. Sau đó, vào năm 1928, tác phẩm này đã được công bố trong kỷ yếu của Quốc hội. Đồng thời, trong thư của mình, Boris Nikolaevich cũng không quên đề cập đến việc đại hội được tổ chức tại Toronto, quê hương của Coxeter. Đáp số Coxetera đã rất đúng. Ông tìm thấy đề cập đến công việc của Delaunay trong các tài liệu của đại hội toán học năm 1924. Trong một lá thư, Coxeter yêu cầu Delaunay tha thứ cho anh ta, đặc biệt là vì vào năm 1924, Coxeter, anh ta còn trẻ đến mức, theo Boris Nikolayevich, anh ta “đi dưới gầm bàn trong chiếc quần ngắn”. Cùng lúc đó, Coxeter viết thư cho Giáo sư K. A. Rogers ở Cambridge, người đang hoàn thiện cuốn sách “Đắp và sơn”, cuốn sách đã trở thành một loại sách bán chạy nhất về toán học. Rogers đã đưa vào cuốn sách một tham chiếu đến phân vùng Delaunay. Rất có thể, thuật ngữ - phân vùng Delaunay (trong hình học tính toán - tam giác Delaunay) - lần đầu tiên xuất hiện trong cuốn sách này. Vào những năm 1980, nó trở nên phổ biến ở phương Tây, từ đó nó đến Nga vào cuối thế kỷ trước. Vào những năm 1990, tôi có cơ hội gặp Giáo sư Coxeter và phát biểu tại hội thảo của ông tại Đại học Toronto. Tôi xin Thầy kể lại câu chuyện này. Coxeter thường xác nhận câu chuyện do Boris Nikolaevich kể, ngoại trừ việc “đi dưới gầm bàn trong chiếc quần ngắn”. Năm 1924, Coxeter (1907–2003) đã 17 tuổi. Và cụm từ “đi dưới gầm bàn” là biểu hiện của lối diễn đạt và sự hài hước đặc trưng của Boris Nikolayevich - những phẩm chất mà Delaunay sở hữu đầy đủ.

4 Vladimir Andreevich Steklov (1864–1926) - nhà toán học, học giả nổi tiếng người Nga. Vào những năm 1920, ông đã tổ chức Viện Vật lý và Toán học của Viện Hàn lâm Khoa học và là giám đốc đầu tiên của nó. Sau đó, vào năm 1934, viện này được chia thành hai viện hàn lâm: V.A. Viện Toán học Steklov và V.A. Viện Vật lý Steklov. P.N. Lebedeva.

⟦column⟧

Thời kỳ Leningrad (1922–1934) Nghiên cứu về các phân vùng không gian đánh dấu một sự thay đổi trong nghiên cứu theo hướng hình học. Nó diễn ra từ từ và tự nhiên. Ở đây, sự tiếp xúc trong nghiên cứu các phương trình bất định với công trình của Voronoi đã đóng một vai trò nhất định. Nhưng lý do chính cho việc hình học hóa nghiên cứu của Boris Nikolaevich nằm ở bản thân ông, ở nhận thức nghệ thuật, tượng hình độc quyền của ông về thế giới. Đặc điểm là Boris Nikolaevich đã không tiếc công sức và thời gian để đưa sự hiểu biết về một kết quả toán học đã hoàn thành đến mức mà kết quả đó sẽ được hình thức hóa dưới dạng hình học. “Điều này đơn giản có nghĩa là gì?” - một câu hỏi yêu thích mà anh ấy tự hỏi mình và các đồng nghiệp mỗi khi thảo luận về một công việc khác. Sự công nhận thành tích khoa học không mất nhiều thời gian để đến: năm 1929, B.N. Delone được bầu làm thành viên tương ứng của Viện Hàn lâm Khoa học. Tính đến thời điểm này, ông đã là giáo sư tại Đại học Leningrad được 7 năm. Những bài giảng cực kỳ rõ ràng và chu đáo của ông khơi dậy sự quan tâm lớn của sinh viên. Sự nổi tiếng của ông lớn đến mức những bài giảng đầu tiên trong các khóa học đặc biệt (tự chọn) của ông đã thu hút hàng trăm sinh viên muốn gặp vị giảng viên huyền thoại. Phải nói rằng Delaunay chưa bao giờ bỏ lỡ cơ hội nói với học sinh về một bài toán khó chưa giải được. Boris Nikolaevich được hướng dẫn bởi một nguyên tắc nổi tiếng, dường như của Plutarch: “Học sinh không phải là một chiếc bình cần được lấp đầy, mà là một ngọn đuốc cần được thắp sáng”. Và người tự thiêu có thể thắp lửa. Thẩm quyền khoa học cao, thái độ cống hiến và đồng thời có tính thẩm mỹ đối với khoa học, sự quyến rũ cá nhân - tất cả những điều này đã thu hút giới trẻ đến với anh. Không có gì đáng ngạc nhiên khi ông có nhiều học trò, trong đó có một số nhà toán học xuất sắc: học giả Alexander Danilovich Alexandrov (1912–1999) và Igor Rostislavovich Shafarevich (sinh năm 1923), thành viên tương ứng của Viện Hàn lâm Khoa học Dmitry Konstantinovich Faddeev (1907–1989).

B.N. Delaunay giảng bài

01-.p65

⟦folio 7⟧

ĐA NĂNG

Vào mùa xuân năm 1934, tại Leningrad, Boris Nikolaevich đã tổ chức Olympic toán học cấp trường đầu tiên, mở đầu cho các Olympic toán học ở nước ta. Những người tham gia Olympic Leningrad đầu tiên đã nhớ lại rất lâu ấn tượng sâu sắc về cuộc gặp gỡ của họ với B.N. Delaunay đã thực hiện chúng (ví dụ, xem «Kvant» Số 9 cho năm 1984, trang 52).

A.D.Alexandrov

B.N.Delone và I.R.Shafarevich (cuối thập niên 1940)

Thời kỳ Mátxcơva (1934–1980)

Năm 1934, V.A. Viện Toán học Steklov được thành lập tại Leningrad, nơi Boris Nikolaevich làm việc kể từ thời điểm thành lập. Cho đến năm 1960, ông đứng đầu bộ môn đại số, rồi hình học cho đến cuối đời. Ngay sau khi thành lập, Viện Toán học (hay đúng hơn là phần lớn nó) đã được chuyển cùng với các tổ chức khoa học hàng đầu khác của Viện Hàn lâm Khoa học đến Moscow. Từ năm 1935, Delaunay làm giáo sư tại Đại học Mátxcơva, nhiều năm ông giữ chức vụ trưởng khoa hình học, nay là khoa hình học cao cấp và cấu trúc liên kết tại Khoa Cơ học và Toán học. Tại Đại học quốc gia Moscow, ông đã tạo ra một khóa học rất độc đáo về hình học giải tích, nổi bật vì sự phong phú đặc biệt của các ý tưởng hình học. Không khó để xác minh điều này bằng cách mở cuốn sách hai tập về hình học giải tích do ông cộng tác với D.E. Raikov. Những sinh viên có may mắn được nghe các bài giảng của ông hầu như không nghi ngờ rằng đằng sau vẻ đẹp lộng lẫy của chúng ẩn chứa sự chuẩn bị kỹ lưỡng nhất. Anh ấy phải mất trọn hai ngày để chuẩn bị một bài giảng dài hai giờ, sau đó là một ngày. Anh ấy đánh bóng mọi ý tưởng, mọi hình. Và kết quả là, trong

01-.p65

DELAUNAIS

⟦column⟧

Trong bài giảng, các khối mười hai mặt và hai mươi mặt rõ ràng, các paraboloid và hyperbol thanh lịch, những “mèo affine” dễ thương, mà ông đã đưa vào khóa học hình học giải tích của mình để minh họa những gì xảy ra với một hình trong quá trình biến đổi affine, xuất hiện nhanh chóng và dễ dàng trên bảng đen. Có một thời, sinh viên Khoa Cơ và Toán tại Đại học Tổng hợp Mátxcơva rất chuộng một loạt giai thoại rất dí dỏm về các giáo sư của họ về chủ đề: “Ai (trong số các giáo sư) nấu súp bằng cái gì?” Theo phiên bản của sinh viên, không phải là không có sự mỉa mai, Boris Nikolaevich đã nấu súp theo n chiều $решетке^{5}$: tuy nhiên, súp đã chảy ra nhưng vẫn giữ được độ rõ hình học. Boris Nikolaevich hoàn toàn không có bất kỳ lý luận hay sự tẻ nhạt nào. Tôi sẽ trích dẫn một tình tiết mà N.Ya. Vilenkin, người học cùng Delaunay, đã kể cho tôi nghe. Một ngày nọ, Boris Nikolaevich xuất hiện tại một bài giảng với vẻ mặt tức giận và bắt đầu nhăn nhó khó chịu và thậm chí là gầm gừ. Các sinh viên, đã quen với việc Delaunay luôn mỉm cười hơi ranh mãnh, đã sửng sốt: chuyện gì đã xảy ra với Boris Nikolaevich? Việc này kéo dài khoảng mười đến mười lăm giây, rồi cái nhăn mặt biến mất, mọi người nhìn thấy một nụ cười quen thuộc và nghe thấy lời giải thích về chuyện đã xảy ra: "Trên đường đến chỗ bạn, tôi gặp người phụ trách của bạn. Cô ấy phàn nàn với tôi rất nhiều về bạn, bạn trốn học, nhiều người không vượt qua các hội thảo chuyên đề, v.v., và thực sự yêu cầu dọa bạn..." Về công việc khoa học thời kỳ Moscow, tôi sẽ chỉ kể tên một số hướng chính mà Boris Nikolaevich đã làm việc chăm chỉ và thu được những kết quả quan trọng. Trước hết, đây là hình học của các dạng bậc hai dương và các ứng dụng của nó vào lý thuyết về cái gọi là lớp phủ mạng và sự đóng gói của không gian. Về cơ bản, các kết quả mới đã thu được trong lý thuyết phân chia đều đặn và phân chia tinh thể của không gian đa chiều, cũng như trong hình học của các con số. Một số kết quả từ những năm 1960–70 đã thu được nhờ sự cộng tác của các đồng nghiệp và sinh viên. B.N. Delaunay là nhà phổ biến toán học và khoa học nói chung một cách xuất sắc. Những bài giảng phổ biến của ông, dành cho nhiều đối tượng, đã thu hút hàng trăm người nghe. Anh ấy đã chuẩn bị trước những kỹ thuật “ngẫu hứng” - những kỹ thuật mà anh ấy sử dụng để làm cho bài giảng trở nên sinh động, thú vị và khó quên. Ví dụ, vào những năm 1940, ông đã nhiều lần giảng về chủ đề “Định lý N.E. Zhukovsky về lực đỡ cánh máy bay”. Boris Nikolayevich bắt đầu bài giảng của mình tại Thính phòng lớn nổi tiếng của Bảo tàng Bách khoa ở Moscow trước hàng trăm người tụ tập như thế này. B.N.: “Chắc bạn biết nhà toán học nổi tiếng Viện sĩ Pavel Sergeevich $Александрова^{6}$?” Giọng nói cá nhân: “Vâng, tất nhiên rồi.”

5 Lưới ở đây có nghĩa là tập hợp các điểm có tọa độ nguyên. 6 giờ chiều Aleksandrov (1896–1982) - một nhà toán học xuất sắc, một trong những người sáng lập trường tôpô quốc gia, viện sĩ, giáo sư cơ học và toán học tại Đại học quốc gia Moscow.

⟦folio 8⟧

KVANT 2010/№2

B.N.: “Bạn có biết rằng nhà toán học nổi tiếng Viện sĩ Alexandrov không bao giờ đi máy bay không?” Một tiếng vo ve nhẹ, khán giả bối rối. B.N.: “Bạn có biết tại sao Viện sĩ Alexandrov lại sợ đi máy bay không?” Tiếng ồn ngày càng lớn. B.N. (với nụ cười ranh mãnh) kết luận: "Viện sĩ Alexandrov không bao giờ bay bằng máy bay vì ông ấy không biết định lý Zhukovsky. Nhưng tôi biết và bay rất nhiều. Hôm nay tôi sẽ giới thiệu với các bạn định lý này, và các bạn sẽ không bao giờ sợ bay." Đến lúc này, khán giả đã “ấm lên” và sẵn sàng lắng nghe câu chuyện về một định lý quan trọng như vậy.

Không chỉ khoa học

01-.p65

Đỉnh Belukha và Đỉnh Delone

Trong số nhiều sở thích phi toán học của Boris Nikolaevich, leo núi chiếm một vị trí đặc biệt. Chắc chắn đây là niềm đam mê mạnh mẽ nhất đã tồn tại trong suốt cuộc đời tôi. Nó bắt nguồn, như đã đề cập, từ thời thơ ấu trong chuyến đi mùa hè của gia đình tới Thụy Sĩ. Trong hoạt động leo núi, anh đặc biệt bị thu hút bởi vẻ đẹp của những bức ảnh toàn cảnh mở rộng, những hình bóng biểu cảm về mặt hình học của các rặng núi và đỉnh núi. Và tất nhiên là niềm đam mê chinh phục đỉnh cao bằng bất cứ giá nào. Anh tham gia leo núi khá chuyên nghiệp. Trên dãy Alps, vào năm 1910, ông đã leo lên đỉnh cao thứ hai sau Mont Blanc, nhưng về mặt kỹ thuật không khó là Monte Rosa. Sau đó là vùng Kavkaz với vô số chặng leo núi khó khăn, kể cả những chặng leo núi đầu tiên. Nhưng Boris Nikolaevich đặc biệt yêu thích Altai. Năm 1926, ông cũng đến thăm ngọn núi mang tên ông. Đỉnh Delone nằm trên vai dẫn lên đỉnh cao nhất Altai - Belukha. Cùng nhau đi du lịch qua Altai $И.Е.Таммом^{7}$, họ phát hiện ra một địa điểm đẹp đến kinh ngạc: Hồ Shavlo, trong làn nước trong vắt có hình ảnh phản chiếu của hai đỉnh núi hùng vĩ phủ đầy tuyết. Delaunay gọi một trong số đó là Người đẹp, Tamm gọi là Truyện cổ tích còn lại. Theo Delaunay, vẻ đẹp của nơi này vượt qua tất cả những địa điểm nổi tiếng trên dãy Alps. Ngày nay, con đường đến Người đẹp và Truyện cổ tích là một trong những con đường hấp dẫn nhất ở Altai. Trong những năm 30 và 40 của thế kỷ trước, Boris Nikolaevich đã tích cực tham gia tổ chức các hoạt động leo núi đại chúng ở nước ta. Vào mùa hè năm 1931, ông tổ chức trại leo núi đầu tiên của đất nước ở Caucasus cho

⟦column⟧

công nhân của nhà máy Leningrad Putilov và tổ chức các lớp học về kỹ thuật leo núi ở đó, đồng thời phân tích các đường đi lên cùng với những người hướng dẫn. Năm 1934, ông được trao danh hiệu bậc thầy leo núi. Vào thời điểm này, leo núi đang trở thành một môn thể thao đại chúng và việc tạo ra một hệ thống phân loại là cần thiết.

7 Igor Evgenievich Tamm (1895–1971) - nhà vật lý lý thuyết kiệt xuất, đoạt giải Nobel (1958).

Hạ hồ Shavlinskoye và các đỉnh núi trắng như tuyết Skazka và Krasavitsa

⟦folio 9⟧

ĐA NĂNG

xác định thành tích thể thao. Delaunay đã phát triển các nguyên tắc để phân loại các đường leo núi (năm giai đoạn) và theo đó, đã phân loại hơn 200 tuyến đường đến các đỉnh Caucasus, Trung Á và Altai. Năm 1938, ông viết cuốn hướng dẫn đầu tiên dành cho những người leo núi, “Đỉnh núi phía Tây Caucasus” (một phần của dãy Caucasus nằm ở phía tây Elbrus). Nó mô tả hàng chục đỉnh núi chính của khu vực này và các tuyến đường để leo lên chúng. Mô tả được kèm theo hình của mỗi đỉnh cùng với các tuyến đường để leo lên đỉnh đó. Trong cuốn sách, trên một phụ trang có một bức tranh toàn cảnh về toàn bộ sườn núi Tây Caucasian, do Boris Nikolaevich thực hiện, di chuyển từ đỉnh này sang đỉnh khác trên một sườn núi song song. Với tuổi tác, leo núi đã được thay thế bằng đi bộ đường dài. Không phải đi bộ 5–10 km mà là đi bộ đường dài 30–40 km thực sự, đôi khi rất khó khăn, luôn diễn ra ở những nơi đẹp nhất trong khu vực Moscow. Boris Nikolaevich là một người đàn ông có thể chất đặc biệt rắn chắc. Và vẫn không khỏi bàng hoàng khi chứng kiến ​​một cụ già khỏa thân đến thắt lưng bước đi vội vã với chiếc ba lô vào cuối mùa đông. Tuyết rơi tan chảy và chảy xuống mái tóc xám của anh ta, đóng băng dưới dạng những cột băng lớn. Boris Nikolaevich rất yêu thiên nhiên và luôn âm thầm ngưỡng mộ vẻ đẹp của nó, như thể đang cố gắng hấp thụ mọi thứ và mọi người. Sự ngưỡng mộ của anh vô tình được truyền sang những người bạn đồng hành. Giao tiếp với thiên nhiên giống như một bí tích, và anh ấy cảm thấy khó chịu, mặc dù anh ấy không thể hiện ra ngoài, khi bí tích này vô tình bị làm phiền bởi cuộc trò chuyện của ai đó. Nhưng xung quanh đống lửa hay trên tàu, những người bạn đồng hành của anh đã trở thành người nghe vô số câu chuyện, câu chuyện này thú vị hơn câu chuyện kia. B.N. Delaunay là một người kể chuyện tuyệt vời... "Tất nhiên, bạn không biết rằng em gái tôi là một vị thánh (tạm dừng, cái nhìn ranh mãnh của người kể chuyện, sự hoang mang của người nghe). Vâng, vâng, khá nghiêm túc đấy, thánh nhân..." ...Rồi bắt đầu một câu chuyện thú vị về người anh họ và người bạn thời thơ ấu Elizaveta Pilenko (đã kết hôn với Kuzmina-Karavaev), một nữ thi sĩ (những bài thơ của cô ấy được Alexander Blok đánh giá cao). Sau cuộc cách mạng năm 1917, Mẹ di cư sang Pháp và trở thành nữ tu (Mẹ Maria là tên tu viện; đó cũng là tên bộ phim chúng tôi đề tặng Mẹ). Trong thời kỳ Đức Quốc xã chiếm đóng nước Pháp, Mẹ Maria gia nhập hàng ngũ kháng chiến, bị bắt và chết trong trại tập trung của Đức. Sau chiến tranh, bà chính thức được Giáo hội Công giáo phong thánh.

"Buổi tối của cuộc sống"

Trong bài phát biểu chào mừng nhân dịp kỷ niệm 80 năm, Học viện các nhà tự nhiên học Đức “Leopoldina” chúc B. N. Delaunay, một thành viên của học viện này, một “buổi tối vui vẻ trong cuộc sống”. “Buổi tối của cuộc đời” kéo dài mười năm. Trong những năm này, ông cùng với các học trò của mình đã thu được những kết quả quan trọng về lý thuyết che phủ không gian tối ưu bằng các quả bóng, về lý thuyết địa phương của cái gọi là

01-.p65

DELAUNAIS

⟦column⟧

hình thành các cấu trúc đều đặn, là một loại mô hình toán học của tinh thể. Boris Nikolaevich là người đứng đầu và hỗ trợ của một gia đình lớn. Ông rất yêu quý các cháu của mình, chúng rất yêu quý ông nội. Boris Nikolaevich đã chăm sóc họ, nhưng ông đặc biệt lo lắng cho số phận của cháu trai cả của mình, Vadik. Vadim Delone (xem http://vadim-delaunay.org), nhà thơ tài năng, đẹp trai, có trái tim dịu dàng và tâm hồn đồng cảm. Năm 18 tuổi, ông trở thành một nhà bất đồng chính kiến và hoạt động nhân quyền. Năm 19 tuổi, ông bị kết tội tổ chức một cuộc biểu tình chính trị ở Mátxcơva. Một năm sau khi được trả tự do, vào ngày 25 tháng 8 năm 1968, ông đi ra ngoài cùng nhóm “bảy” nổi tiếng đến Quảng trường Đỏ để phản đối việc đưa quân đội Liên Xô vào Tiệp Khắc. Với khẩu hiệu “Vì sự tự do của bạn và của chúng tôi", mà anh ta giữ trong vài giây, Vadim đã nhận được 3 năm "không tự do". Boris Nikolaevich đã làm mọi cách để xoa dịu số phận của cháu trai mình. Ông đã thu thập chữ ký từ những người nổi tiếng để bảo vệ Vadim, và với những bức thư này, ông đã đến thăm các văn phòng "cao nhất" ở Lubyanka. Sau phiên tòa, ngay khi nhận được sự cho phép, ông đã đến thăm anh ta trong một trại ở phía bắc vùng Tyumen. Một đối tượng khác được chăm sóc đặc biệt là vợ anh ta đang bị bệnh và cần được chăm sóc. Sau đó Vadim ra nước ngoài và cái chết của vợ, ông, đã 86 tuổi, “lao vào mọi thứ”: công việc, bài giảng, chuyến đi, hai chuyến đi bộ mỗi tuần, mỗi lần 20–40 km. Vào một trong những ngày năng động nhất, ông bị đột quỵ: đột quỵ, mất khả năng nói gần như hoàn toàn, trí nhớ, khả năng vận động hạn chế, tính đến tuổi tác của ông, các bác sĩ cực kỳ keo kiệt trong việc đánh giá triển vọng của ông về một cuộc sống trọn vẹn và giành được chiến thắng cuối cùng, nhưng có lẽ là quan trọng nhất trong cuộc đời (không phải nếu không có sự giúp đỡ của ông). những người thân yêu, học sinh và đồng nghiệp) Những chức năng đã mất của anh ấy được phục hồi và anh ấy trở lại cuộc sống thực. Tất nhiên, những chuyến đi bộ đường dài “chỉ” khoảng 10–15 km, không phải xuyên qua những khu rừng rậm rạp mà là qua những nơi có “cảnh quan công nghiệp”, không phải hai lần mà chỉ một lần một tuần. Tôi sẽ không bao giờ quên một ngày tháng Ba xám xịt (tức là khoảng bốn tháng trước khi kết thúc) Boris Nikolaevich lấy một cuốn sách ra khỏi tủ sách và đọc một đoạn văn đáng chú ý của Poincaré. Hơi thở của anh bị gián đoạn bởi sự phấn khích, giọng anh run rẩy: "... cuộc đời chỉ là một đoạn thoáng qua giữa hai cõi vĩnh hằng của cái chết và... trong đoạn này, thời gian quá khứ và tương lai của ý nghĩ có ý thức không quá một khoảnh khắc. Một ý nghĩ chỉ là một tia sáng lóe lên giữa đêm dài. Nhưng tia sáng này là tất cả. "
