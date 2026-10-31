---
id: 1987-5-krutogin-kto-upravlyaet-gorodom-mk-bc0dfce9
issue: kvant_1987_5
year: 1987
number: "5"
title: Ai điều hành thành phố MK?
authors:
  - Крутогин Д. Г.
rubric: osnovnye-stati
page_first: 18
page_last: 23
page_labels: 16, 17, 18, 20, 21
tag: K8DF
lang: vi
source: kvant_digital
extraction: vision
content_sha256: a62bd542c0ae1043606d8debb0d8faef5d2c8f37887d7be1c2b10449785a169f
prompt_sha256: draft-1
translated_from: content/ru/1987/05/articles/04_krutogin-kto-upravlyaet-gorodom-mk-bc0dfce9.md
source_content_sha256: 97238e5d2b73a5cd5a10d779d70ea23a4e7d6c0ada3e04fdbaf493aa7ef3c910
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 16⟧

AI CHẠY THÀNH PHỐ MK?

(Hành trình qua máy vi tính)

Ứng viên Khoa học Kỹ thuật D. G. KRUTOGIN

Hôm nay chúng ta phải đến thăm trung tâm kiến ​​​​trúc của thành phố, đồng thời là khu vực sản xuất chính - tóm lại là bộ vi xử lý. Không phải ngẫu nhiên mà chúng tôi phát hiện ra hình ảnh này, không phải ngẫu nhiên mà chúng tôi đi đi lại lại. Một bộ vi xử lý cũng khó phân tích như một kiệt tác kiến ​​trúc. Và không dễ để nói về nó. Chúng ta có thể lại vạch ra một kế hoạch, liệt kê các chi tiết về nghị sĩ, sự tương tác của họ trong công việc, nhưng chúng ta sẽ làm việc này sau. Và chúng tôi sẽ dạy bạn bằng cách xây dựng trong trí tưởng tượng của chúng tôi bộ vi xử lý (SMP) đơn giản nhất từ ​​​​các khối cần thiết nhất. Nếu nó có thể “hoạt động” (ở cùng một nơi, trong trí tưởng tượng), thì có lẽ sẽ không khó để làm phức tạp nó một chút để đến gần hơn với kiến ​​​​trúc thực và chức năng thực của MP.

16

⟦folio 17⟧

Vậy bắt đầu từ đâu? Bộ xử lý phải thực hiện tất cả các phép tính số học và logic. Hãy để chúng tôi nhắc bạn rằng không có quá nhiều phép toán: số học - phép cộng có tính đến dấu (tức là phép trừ) và phép nhân (chia) bằng phép chia c của một số kép ở bên phải - bên trái cho một số nguyên các chữ số; logic - “VÀ”, “HOẶC”, “KHÔNG”. Các hoạt động này được thực hiện trong Đơn vị logic số học PMP của chúng tôi, viết tắt là ALU. Đây đã là viên ngọc kiến ​​trúc của thành phố MK và công nghệ máy tính nói chung.

Nhân viên quan trọng nhất

ALU là một tập hợp các bộ cộng nhiều bit (8, 16 và đôi khi nhiều hơn), tùy thuộc vào các xung điều khiển, có thể thay đổi từ các phép toán số học sang logic hoặc ngược lại. “Kvaant” đã nói về công việc của một bộ cộng một giá trị vào năm ngoái (xem số tháng 5). Và tại hình 1, bạn có thể thấy ALU bốn bit (rất đơn giản). Thông qua các dây bus dữ liệu, các toán hạng bit $A$ và $B$ được cung cấp cho đầu vào $A_0$ - $A_3$ và $B_0$ - $B_3$, kết quả là đầu ra từ đầu ra $F_0$ - $F_3$, đầu vào $S_0$ - $S_3$ được sử dụng để điều khiển ALU, chuyển nó sang một số thao tác nhất định (cộng, trừ, phủ định, v.v.).

Nhìn vào hình 1, hãy tưởng tượng một mê cung lớn với những con đường thẳng. Nó có tám đầu vào và bốn đầu ra; nhưng, không giống như mê cung thông thường, trong mê cung này, một neko (“tên” của neko này là UFC, và chúng ta sẽ làm quen với anh ta sau) liên tục di chuyển các bức tường, thay đổi cấu hình của các lối đi. Do đó, ALU sẽ thực hiện các hành động khác nhau với cùng toán hạng cho các tín hiệu điều khiển khác nhau và đầu ra sẽ có đáp số khác nhau.

ALU hoạt động với tốc độ cực lớn và tuyệt vời; những gì nó có thể làm, nó thực hiện trong một phần triệu giây (và các thiết bị ALU nhanh nhất còn nhanh hơn hàng trăm lần). Phẩm chất này rất có giá trị và chúng ta có thể nói rằng mọi thứ khác có trong MK đều được sắp xếp sao cho ALU, nếu có thể, không bị lỗi.

Opera có nguồn gốc từ đâu? Thông thường từ vùng RAM hoặc ROM. Tuy nhiên, theo quy định, bạn chỉ có thể gọi từng cái một từ đó, ví dụ: đầu tiên là $A$, sau đó là $B$. Điều này có nghĩa là trong khi PMP đang chờ $B$ xuất hiện, toán hạng $A$ phải đợi một chút ở đâu đó. “Bộ thu” gần nhất là một thanh ghi bộ nhớ đặc biệt được gọi là bộ tích lũy. Nó có cùng số bit như trong ALU. Bộ tích lũy không chỉ cung cấp một toán hạng cho ALU mà còn nhận được kết quả của phép toán - từ $F$. Sau đó, bộ tích lũy sẽ chuyển từ này sang RAM hoặc một số thanh ghi bộ nhớ khác trong quy trình, nhưng trước tiên, điều quan trọng là phải đảo ngược tình thế!

Điểm quan trọng tiếp theo là quản lý. Chúng tôi đã lưu ý rằng ALU cần được kiểm soát và thiết lập thứ tự vận hành của nó. Điều này có nghĩa là PMP của chúng tôi cần có cơ quan quản lý phù hợp. (Đây là cách lật ngược tình thế! Trước đây, chúng tôi đã bác bỏ thực tế rằng mọi thứ đều được kiểm soát bởi bộ xử lý, nhưng hóa ra cũng có ai đó kiểm soát nó.)

"Bộ xử lý" cho một quy trình

Thiết bị điều khiển và tạo lệnh (gọi là UVK)

Hình 1. Sơ đồ biểu diễn giao tiếp của ALU bốn bit. C—chỉ số bán hàng sdbila và sự thay đổi cấp bậc. M - công tắc số học - logic.

⟦folio 18⟧

Nó chiếm một diện tích vi mô có kích thước tương tự trong khu vực PMP. Nhiệm vụ của micropaon này là nhận lệnh tiếp theo từ văn bản chương trình và giải mã nó đến mức xung đơn giản nhất được cung cấp cho đầu vào $S_i$ và $M$ của thiết bị logic số học.

Về cơ bản, micropaion UFK được xây dựng bằng các thiết bị logic, được gọi là bộ giải mã. Họ thực sự điền vào các thẻ viết, các lỗ trong đó chọn một số chữ cái quyên góp bí mật từ văn bản ngẫu nhiên nhất. Và vai trò phản hồi là thực hiện các tùy chọn khác nhau để kết nối các phần tử giải mã với bus mang văn bản lệnh. Mặc dù các phần tử xây dựng là điển hình - đây là các phần tử logic *) VÀ - KHÔNG, HOẶC - KHÔNG, kiến ​​​​trúc kỳ lạ của chúng cho phép thực hiện hàng tá kết hợp cung cấp khả năng kiểm soát PMP. Hệ thống UFC không chỉ kiểm soát ALU mà còn cả pin và các khu vực khác của bộ vi điều khiển. Một trong những bộ tứ UVK chuyên phục vụ các hệ thống đầu vào và đầu ra; nó cũng quản lý bộ đệm của các bus tương ứng trong thời gian tiếp xúc với các thiết bị bên ngoài. Có tới hàng trăm kênh điều khiển phát ra từ khu vực UFK.

Câu hỏi tiếp theo là UFC nhận lệnh giải mã ở đâu? Tất nhiên là từ trí nhớ (nơi bắt nguồn của các vở opera). Nhưng trong quá trình giải mã, hình thành các lệnh vi mô và cách sử dụng chúng, lệnh đến từ bộ nhớ phải được đặt bên cạnh UVK (trong tầm tay), nghĩa là trong một thanh ghi bộ nhớ đặc biệt - thanh ghi lệnh (PK). Có nhiều bit trong PK cũng như trong ALU và pin.

Rõ ràng là pin và PK là bộ nhớ siêu RAM gần nhất của bộ xử lý.

Sẽ thật tuyệt nếu bây giờ người đọc chú ý vẽ sơ đồ khối của phần PMP được mô tả ở trên. Hai hình chữ nhật với nhau cần được nối với nhau bằng một hành lang hẹp, trong đó có mũi tên chỉ hai hướng - đây là ALU và pin (A). Bên dưới sẽ có một đường thẳng lớn hơn một chút - UVK, các mũi tên từ nó đi tới ALU và pin. Đặt hình vuông PK ở bên phải, các mũi tên từ nó hướng vào khối UVK. Bây giờ, phía trên pin, vẽ một hình vuông nhỏ nhưng quan trọng - bộ đệm (B), sau đó kết nối bus dữ liệu với bộ đệm và đăng ký ở bên phải (để làm được điều này, bạn sẽ phải tạo một nhánh trên đó). Bộ đệm B (trước đây chúng tôi đã so sánh nó với đồn cảnh sát giao thông) có thể truyền dữ liệu từ bộ nhớ (RAM) trong một tiến trình, ở trạng thái khác - ngược lại - từ tiến trình đó sang RAM. Nhưng anh ta cũng có trạng thái thứ ba, khi anh ta thường tránh việc trao đổi dữ liệu, như thể “đang xem xét nó”. Bộ đệm “cung cấp” trạng thái này (tất nhiên, theo tín hiệu UVK!) tại thời điểm một từ lệnh đến qua bus dữ liệu. Kết quả là lệnh kết thúc trong thanh ghi lệnh nhưng không có trong ALU. Nếu bây giờ chúng ta nhớ rằng lệnh và "đã giải quyết" nằm trong RAM tách biệt với các toán hạng và được gọi để không đi vào thiết bị logic số học, thì sẽ rõ máy tính được chia thành các lệnh như thế nào. Chúng tôi sẽ kiểm tra xem hình của bạn có chính xác sau đó không, nhưng bây giờ hãy quay lại các lệnh. Đây là câu hỏi: ai gọi đội tiếp theo và khi nào? Nhiệm vụ này được thực hiện bởi một thanh ghi bộ nhớ khác, được gọi là bộ đếm khả trình hoặc bộ đếm chương trình (SC).

Các bộ đếm này được điều khiển bởi cùng một đơn vị UFK. Khi bạn bắt đầu sử dụng chương trình, địa chỉ của lệnh đầu tiên theo thứ tự sẽ được ghi vào bộ đếm. Ngay khi lệnh này được nhập vào PK và bắt đầu được giải mã trong UFK, bộ đếm sẽ nhận được tín hiệu tăng dần, chẳng hạn như một tín hiệu, và do đó ghi lại địa chỉ của lệnh tiếp theo (hoặc phần thứ hai của cùng một lệnh, nếu nó dài).

Quy trình tương tự được lặp lại với lệnh tiếp theo và cứ như vậy cho đến khi có lệnh dừng. Nhưng đôi khi lệnh tiếp theo chứa gợi ý để bộ đếm không chuyển sang lệnh tiếp theo mà đến một số lệnh khác vượt xa (hoặc ngược lại, phía sau) lệnh tiếp theo. Sau đó, nó được tính-

⟦folio 20⟧

Các mạch logic của bộ khử trong mạch UVK và bộ đệm bus.

Các bus truyền thông nội bộ giữa các phần tử bộ xử lý riêng lẻ.

Tất nhiên, một bộ vi xử lý thực sự phức tạp hơn nhiều so với bộ vi xử lý đơn giản nhất của chúng ta. Nó giới thiệu một số đăng ký quan trọng hơn cho các mục đích chuyên biệt, cung cấp khả năng khởi động lại chương trình và quay lại chương trình, cũng như các cách khác nhau để truy cập bộ nhớ. Độ phức tạp tổng thể của cấu trúc bộ vi xử lý có thể được đánh giá cao nếu chúng ta nhớ rằng đằng sau mỗi thanh ghi, bộ cộng hoặc bộ giải mã có mười hoặc thậm chí hàng trăm bóng bán dẫn và có mười hoặc hàng trăm nghìn bóng bán dẫn trong toàn bộ bộ vi xử lý.

Nhưng chúng ta hãy nhìn bộ vi xử lý không phải từ quan điểm kiến ​​trúc mà từ quan điểm chức năng. Nó làm gì trong máy vi tính, bộ xử lý làm gì trong máy tính lớn? Bộ xử lý mới để làm gì?

Robot nâng

Trong số tháng 1 «Kvant» năm ngoái, trong bài viết “Hoạt động logic cơ bản”, một ví dụ về điều khiển thang máy đã được xem xét: một tòa nhà nhiều tầng, một hoặc nhiều thang máy, một nút gọi ở mỗi tầng. Thang máy được điều khiển bởi nhân viên chỉ huy. Trong đáp số, đối với nhiều tình huống bài toán có ​​thể xảy ra, thiết bị sẽ tạo ra một trong ba lời giải: lên, xuống, dừng (nếu có hai thang máy thì độc lập lời giải 2×3=6). Lời giải được chuẩn bị trước và tồn tại dưới dạng sơ đồ đấu nối điện cho các công tắc hoặc rơle thông thường. Các kết nối này có thể được mô tả bằng các thao tác logic (xem hình 4, a): nếu nút “e10” (tầng) HOẶC “e9” (v.v.) được bật VÀ (đồng thời!) nút “l12” được bật (thang máy trống ở tầng 12) VÀ nút “stop1” KHÔNG được bật (quá tải!) VÀ nút “stop2” KHÔNG được bật (cửa đang mở!), thì lời giải bài toán - XUỐNG. Nếu không - DỪNG LẠI. Khi thang máy di chuyển đến các tiếp điểm của các công tắc đã lắp đặt, sơ đồ kết nối sẽ thay đổi và trước tầng 10, KHÔNG “l10” được bật, tức là DỪNG (hình 4, b).

Do đó, thiết bị lệnh ghi nhớ và so sánh các lệnh gọi, toán hạng - trạng thái hiện tại, các lệnh cấm (chúng thường cao hơn tất cả các lệnh khác!), rồi đưa ra lệnh - đáp số. Mỗi lệnh được thể hiện dễ dàng: 1 - nút được nhấn, 0 - nút được nhả. Đây là một mã kép được thấm nhuần trong chúng tôi.

Bộ xử lý (hoặc bộ vi xử lý) là một thiết bị đa lệnh, được nén có kích thước đến vài milimét vuông của một vi mạch. Anh ấy không có ba mà có hơn một trăm lựa chọn lời giải, anh ấy so sánh rất nhiều dữ liệu,

Hình 3. Sơ đồ bộ vi xử lý đơn giản nhất. Khối màu hồng làm nổi bật phần chính của sơ đồ mà chúng ta bắt đầu “xây dựng”.

⟦folio 21⟧

Hình 4. Logic điều khiển thang máy.

hàng chục điều cấm. Bộ xử lý gửi đáp số của nó tới hàng trăm, hàng nghìn địa chỉ khác nhau. Nói một cách dễ hiểu, nó mạnh hơn nhiều so với một bộ máy chỉ huy khiêm tốn về tốc độ và khả năng, nhưng xét về ý nghĩa hành động và chức năng của nó - nó cũng là một bộ máy chỉ huy! Các tùy chọn lời giải (vi lệnh) được bộ vi xử lý sử dụng được ghi vào bộ nhớ vĩnh viễn của khối UVK. Vì vậy, kết thúc hành trình quanh thành phố, Máy vi tính, thu gọn bộ vi xử lý với khu hành chính văn hóa và thiết bị quản lý và thành lập nhóm (UFK) để trao tư cách Ban chấp hành thành phố (điều hành quản lý hiện hành đời sống thành phố).

Thay vì một kết luận

Bài toán hội đồng thành phố, tức là xác định mục tiêu chung, triển vọng, trình tự thực hiện công việc, triển khai chương trình mà người dùng MK, tức là bạn và tôi. Do đó, với tất cả sự hoàn hảo trong thiết kế của máy tính và bộ vi điều khiển, chúng không chứa đựng nguyên tắc sáng tạo; nó được một người đưa vào chúng, được đưa vào dưới dạng các chương trình vĩnh viễn hoặc có thể thay thế.

TẠI SAO chúng ta không nhìn thấy thành phố MK từ những gì mà những người du ngoạn phải nhìn thấy? Không có tượng đài nào cho những người sáng lập và xây dựng thành phố đầu tiên. Không có chỗ cho anh ta trong sự kiểm chứng và tính hợp lý tột độ của thành phố chúng ta. Nhưng nếu có thì sẽ có một đám đông ở trên đó đáp số nơi vinh danh các nhà khoa học trem: Michael Faradenko - nhà vật lý là người đầu tiên chú ý đến các tính chất đặc biệt của chất bán dẫn, Charles Babbage - “kiến trúc sư” và người chế tạo máy tính đầu tiên, George Boole - nhà toán học, nhà phát minh đại số logic - khoa học làm nền tảng cho mạch máy tính. Ba người này có thể đã biết nhau hoặc sống ở Anh cùng thời điểm.

Tầng thứ hai của tượng đài phải bao gồm mười nhà khoa học lớn: từ D. Mendeleev và N. Bohr, J. Frenkel và W. Schottky đến những người phát minh ra bóng bán dẫn - J. Bardeen và W. Bratein.

Tầng thứ ba của tượng đài xứng đáng là nơi ở của hàng nghìn kỹ sư từ các quốc gia khác nhau, đại diện của nhiều thế hệ nhà vật lý, nhà hóa học, nhà toán học, nhà luyện kim, công nghệ, lao động chim và tài năng đã tạo ra một thành phố xinh đẹp và tìm kiếm vi mô. Trên thực tế, đó là tượng đài tốt nhất cho tác phẩm đầy cảm hứng của họ.
