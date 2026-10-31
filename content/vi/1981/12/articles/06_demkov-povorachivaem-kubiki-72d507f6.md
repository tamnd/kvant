---
id: 1981-12-demkov-povorachivaem-kubiki-72d507f6
issue: kvant_1981_12
year: 1981
number: "12"
title: Xoay các hình khối
authors:
  - Демков Ю.
rubric: osnovnye-stati
page_first: 13
page_last: 18
page_labels: 11-16
tag: NRPA
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 00b0a8838aee60dbfe66dd9d31a6250c26a6b4a9d2574b37bda2609f68539d9c
prompt_sha256: draft-1
translated_from: content/ru/1981/12/articles/06_demkov-povorachivaem-kubiki-72d507f6.md
source_content_sha256: f913ea4c2068a008e991fe1adb24a2a39a8b1a5ea421e063240b4b8e4362d028
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 11⟧

Xoay các hình khối

Không, bài viết này không thảo luận về “khối lập phương khớp nối Hungary” (xem «Kvant», 1980, số 12, trang 17) - một câu đố ra đời dưới bàn tay của kiến ​​trúc sư người Hungary Ernő Rubik và đã thu hút các cổ đông trên toàn thế giới, đặc biệt là ở Hungary và Hoa Kỳ, nơi nó được sản xuất với hàng triệu bản. «Kvant» sẽ sớm quay lại trò chơi khó và thú vị này, nhưng ở đây chúng ta sẽ nói về một câu đố đơn giản hơn nhiều mà bất kỳ ai cũng có thể thành thạo trong vài phút và bạn có thể xây dựng một số lý thuyết toán học hoàn chỉnh.

Lấy 8 cốc và tạo thành khối lập phương có kích thước gấp đôi*). Hãy tô màu ba cặp mặt đối diện của khối lập phương này lần lượt là màu trắng và vàng, đỏ và cam, xanh lá cây và xanh lam. Khi đó mỗi chiếc cốc nhỏ sẽ có ba mặt được sơn màu khác nhau. Bây giờ, chúng ta hãy cầm khối lập phương trong tay và xoay lớp bốn cốc liền kề nhau 180° so với bốn cốc còn lại (theo chiều kim đồng hồ hoặc ngược chiều kim đồng hồ, không thành vấn đề - kết quả không phụ thuộc vào nó). Rõ ràng, điều này có thể được thực hiện theo cách khác thứ ba. Chúng ta hãy sử dụng ba lượt này làm các yếu tố của hoạt động hoặc nước đi. Lặp lại các bước di chuyển này theo thứ tự khác nhau nhiều lần, chúng ta sẽ có được các phân phối khác nhau

màu dọc theo các mặt của hình lập phương. Chúng ta hãy xác định từng phân bố màu sắc như vậy của trạng thái của khối và tất cả các phân bố khác nhau về góc quay của khối nói chung sẽ được coi là một và cùng một trạng thái. Chúng ta hãy định nghĩa trạng thái bằng 0 trong đó mỗi mặt của khối lập phương được tô cùng một màu.

Các câu hỏi sau đây phát sinh. Có bao nhiêu trạng thái khác nhau có thể đạt được từ số 0 bằng một chuỗi các bước di chuyển? Số bước di chuyển nhỏ nhất có thể chuyển một trạng thái tùy ý đã cho về 0 là bao nhiêu? Số lần di chuyển tối thiểu để chuyển đổi một trạng thái tùy ý đã cho thành 0 là bao nhiêu?

Hiển thị trạng thái và ghi lại chuyển động

Để trả lời những câu hỏi này, trước tiên chúng ta sẽ học cách mô tả trạng thái của khối lập phương và giới thiệu một ký hiệu đặc biệt cho các nước đi. Đầu tiên, chúng ta hãy cố định vị trí của khối lập phương trong không gian, giả sử rằng một trong những chiếc cốc nhỏ vẫn đứng yên trong mọi phép biến đổi, chẳng hạn như chiếc cốc có ba mặt ngoài được sơn màu trắng, cam và xanh lục.

Trong Hình 1, hình ảnh một khối lập phương và 12 mặt cốc nhỏ hướng về phía chúng ta được bổ sung bằng hình ảnh 9 mặt sau, như thể được phản chiếu trong một gương lõm tròn. Khi các cạnh của khối lập phương nhỏ phía sau không chuyển động thì trong hình các khối được sơn màu trắng, cam và xanh lục.

Chúng ta hãy biểu thị phép quay của bốn cốc phía trước 180° quanh trục x bằng chữ X, phép quay của bốn cốc bên phải là Y và phép quay của bốn cốc phía trên là Z (Hình 2). Trong tất cả các lần di chuyển này, khối lập phương nhỏ phía sau sẽ bất động, vì vậy khi thực hiện các động tác X, Y, Z, chúng ta sẽ không bao giờ xoay toàn bộ khối lập phương. Các trạng thái thu được từ 0 bằng các phép toán X, Y, Z được hiển thị trong Hình 1, trong đó chúng được đánh số 2-4.

Thành phần di chuyển và kết hợp

Chúng ta sẽ gọi thành phần (thực hiện tuần tự) của các nước đi

⟦folio 12⟧

Cơm. 1.

cũng bằng phép nhân; Chúng ta sẽ viết tích của các bước di chuyển từ trái sang phải. Ví dụ: $YZX$ là việc thực hiện tuần tự các nước đi $Y, Z, X$; $X^3 = XXX$ là việc thực hiện ba nước đi $X$. Chúng ta sẽ coi hai tích của các bước đi là bằng nhau nếu chúng có tác dụng như nhau đối với từng trạng thái của khối.

Tất nhiên, các bước nhân lên không có tính chất giao hoán; ví dụ: tất cả sáu sản phẩm “được ghép nối” đều không bằng nhau (các số 5-10 trong Hình 1).

Chúng ta hãy biểu thị $I$ bước di chuyển “giống hệt nhau” khiến khối lập phương không thay đổi. Rõ ràng,

$$X^2 = Y^2 = Z^2 = I.$$

Có thể dễ dàng kiểm tra xem tất cả các sản phẩm “được ghép nối” được lặp lại ba lần không làm thay đổi trạng thái của khối:

$$(XY)^3 = (YZ)^3 = (ZX)^3 = (YX)^3 = (ZY)^3 = (XZ)^3 = I.$$

Bên cạnh đó,

$$(XYZY)^2 = (XZYZ)^2 = (YXZX)^2 = (YZXZ)^2 = (ZXYX)^2 = (ZYXY)^2 = I$$

Từ các đẳng thức (*), (**), (***) dễ dàng thu được (không cần chuyển sang lập phương!) nhiều đẳng thức mới. Ví dụ (kiểm tra!), $XYX = YXY$ (xem thêm bài toán 1 ở trang 16).

Vì vậy, chúng ta đã thu được ba nhóm đẳng thức, theo đó cả ba nước đi $X, Y, Z$ đều là “căn bậc hai của đơn vị” (*) và tất cả sáu nước đi được ghép đôi là “căn bậc ba của đơn vị” (**), và sáu tổ hợp nước đi khác thuộc loại đặc biệt $(XYZY, YZXZ, ...)$ cũng vậy.

⟦folio 13⟧

Cơm. 2.
là “căn bậc hai của đơn vị” (***).

Đồ thị trạng thái
Chúng tôi đã học cách mô tả các trạng thái của khối lập phương (và gán cho chúng các số 1-24, Hình 1), học cách viết các bước đi và tìm ra sự tương ứng giữa các bước đi. Tôi muốn có thể mô tả rõ ràng hơn mối liên hệ giữa các trạng thái và các bước di chuyển. Với mục đích này, hãy sử dụng biểu đồ trạng thái được hiển thị trong Hình 3. Trên đó, các điểm (đỉnh) biểu thị các trạng thái và các đoạn biểu thị các bước di chuyển cho phép bạn chuyển từ trạng thái này sang trạng thái “lân cận”. Do đó, ở giữa hình, dấu chấm dày tượng trưng cho trạng thái số 0; từ đó xuất hiện ba đoạn tương ứng với các bước di chuyển X, Y, Z; từ điểm cuối của các đoạn này, ba đoạn cũng xuất hiện: một đoạn quay về trạng thái 0, đoạn còn lại dẫn đến hai trạng thái mới, v.v. Tiếp tục quá trình này vô thời hạn, chúng ta có thể coi toàn bộ mặt phẳng được bao phủ bởi một lưới lục giác - một đồ thị trạng thái.

Các mối quan hệ (*) trên biểu đồ tương ứng với chuyển động qua lại dọc theo một trong các đoạn và các mối quan hệ (**) tương ứng với đường truyền của hình lục giác (hãy kiểm tra xem!).

Hình ảnh thu được có một nhược điểm rất lớn - nó có vô số đỉnh (trạng thái), trong khi khối lập phương của chúng ta chỉ có số lượng trạng thái hữu hạn. Điều này có nghĩa là một số đỉnh (khác nhau) tương ứng với cùng một trạng thái. Để tìm ra điều này, hãy lưu ý (ví dụ, ngay trong Hình 3) tất cả các đỉnh của đồ thị được đánh số 1-14, sử dụng Hình 1.

Sau đó, bạn sẽ thấy các đỉnh nào sẽ trùng với nhau. Ví dụ, điểm in đậm ở phần trên của Hình 3 cũng tương ứng với trạng thái 0 (và tổng cộng có 7 điểm như vậy trong hình). Nhân tiện, đường đi từ điểm 0 “trung tâm” tới điểm “trên” tương ứng với các quan hệ

$$XZYZXZYZ = 1,$$

tức là một trong các tỷ số (***).

Cơm. 3. Đồ thị trạng thái của hình lập phương. Các cạnh của hình lục giác biểu thị các phần tử của thao tác (chúng được đặt bằng các chữ cái X, Y, Z), các đỉnh của hình lục giác biểu thị trạng thái và các dấu chấm đậm tương ứng với trạng thái 0. Các đường màu xanh lam, đỏ và xanh lục làm nổi bật các khu vực cơ bản.

⟦folio 14⟧

Có một biểu đồ trạng thái được đánh số trước mắt, bạn có thể dễ dàng trả lời các câu hỏi đặt ra ở đầu bài viết. Chỉ có 24 trạng thái (và 24 lớp có trình tự di chuyển bằng nhau). Trong số này, 3 trạng thái có thể đạt được từ trạng thái 0 trong một nước đi, 6 ở nước đi thứ ba, 9 ở nước đi thứ ba và 5 ở nước đi bốn. Nói chung, để tìm số nguyên tối thiểu nối hai trạng thái này, chỉ cần tìm hai đỉnh trên đồ thị với các số tương ứng và nối chúng với đường đứt nét ngắn nhất biểu thị các bước di chuyển cần thiết và số lần di chuyển này luôn là 4.

Lĩnh vực cơ bản

Trong cụm từ cuối cùng, người đọc cẩn thận lẽ ra phải nhận thấy rằng không phải chỉ lấy bất kỳ “hai đỉnh có số tương ứng” nào mà còn cả những đỉnh nằm “ở lân cận”, nếu không, một đường dẫn bổ sung như (***) có thể xuất hiện.

Về vấn đề này, thật thuận tiện khi “mở” biểu đồ của chúng ta thành các ô, bên trong không có đỉnh trùng nhau và chứa tất cả 24 trạng thái. Hình 3 cho thấy ba cách để thực hiện việc cắt như vậy: thành hình lục giác màu đỏ, hình thoi màu xanh lam và thành “hình chữ nhật có cạnh gãy” màu xanh lá cây.

Trong toán học, các ô cũng thường được gọi là vùng cơ bản. Kiểm tra xem sau các mối quan hệ không tổng quát của các điểm biên của mỗi ô được chỉ định, giá trị thực có chứa 24 đỉnh - trạng thái khác nhau hay không.

Biểu đồ trạng thái không gian

Không sợ điều mới nhất “cái tốt nhất là kẻ thù của cái tốt”, chúng ta hãy cố gắng có được một mô hình chính xác hơn nữa về các trạng thái của khối lập phương của chúng ta, bắt đầu từ các khu vực cơ bản. Để làm được điều này, bạn phải đi ra ngoài không gian ba chiều.

Trước tiên chúng ta hãy chọn vùng cơ bản, được mô tả bằng các đường màu xanh lá cây trong Hình 3 và các đường thẳng gãy ngang. Khi đó vùng biến đổi cơ bản

Cơm. 4.

biến thành một cấu trúc hình chữ nhật và bó đường dẫn sẽ được trình bày dưới dạng một lớp gạch thông thường gồm mười “viên gạch” và bốn “nửa tinh thể” (Hình 4). Bằng cách uốn cong các cạnh trên và dưới của hình chữ nhật, chúng ta sẽ có được một cái ống. Tiếp theo, xoắn ống này nửa vòng và uốn cong, dán các đầu lại với nhau. Chúng ta có được bề mặt như trong Hình 5, được gọi là một ngọn núi. Nó được bao phủ bởi một tấm lưới gồm 12 hình lục giác với 24 đỉnh và 36 cạnh. Nếu đối với mỗi đỉnh chúng ta viết ra số của nó (kết quả là được đánh số trong Hình 3), thì về mặt lý thuyết, đồ thị kết quả sẽ đưa ra một mô tả đầy đủ về trò chơi địa lý của chúng ta. Thật vậy, mỗi đỉnh trong số 24 đỉnh trên lý thuyết tương ứng với một trong 24 trạng thái của khối lập phương của chúng ta, và người ta có thể chuyển từ trạng thái này sang trạng thái khác trong một lần di chuyển khi và chỉ khi các đỉnh tương ứng trên lý thuyết được nối với nhau bằng một cạnh (đen) (xem Hình 5).

Hình học bài toán. Chứng minh rằng tỷ lệ ranh giới của các vùng cơ bản khác (xem Hình 3; hình lục giác màu đỏ và hình thoi màu xanh) theo các quy tắc trên sẽ tạo ra một hình xuyến có đồ thị thuận tay phải trên đó. So sánh biểu đồ này với biểu đồ trước.

Cơm. 5.

⟦folio 15⟧

Nhóm chuyển đổi

Trong khi chúng ta bị mê hoặc bởi hình học bất ngờ nảy sinh ở đây, chúng ta không nên đánh mất bản chất đại số của các cuộc nghiên cứu liên quan đến khái niệm quan trọng của nhóm biến đổi. Một bộ sưu tập không trống $G$ các phép biến đổi của một tập hợp nhất định*) được gọi là *nhóm biến đổi* nếu

$$1^\circ \text{композиция любых двух преобразований из } G \text{ также является преобразованием из } G:$$

$$f, g \in G \Rightarrow f^\circ g \in G;$$

$$2^\circ \text{преобразование, обратное к любому преобразованию из } G, \text{ также содержится в } G:$$

$$f \in G \Rightarrow f^{-1} \in G.$$

Từ các thuộc tính của $1^\circ$ và $2^\circ$, ngay lập tức suy ra rằng phép biến đổi giống hệt $1$ luôn được chứa trong $G$ (kể từ $f^{-1} \circ f = 1$).

Dễ dàng thấy rằng đối với trò chơi của chúng ta, tập hợp tất cả các phép biến đổi (tức là các chuỗi chuyển động) của khối lập phương là nhóm biến đổi của tập hợp tất cả các trạng thái của nó. Thật vậy, thuộc tính $1^\circ$ rất dễ thấy, trong khi thuộc tính $2^\circ$ xuất phát từ thực tế là bất kỳ nước đi nào cũng nghịch đảo với chính nó (xem (*)) và phép biến đổi nghịch đảo với bất kỳ chuỗi nước đi nào cũng giống nhau, chỉ được viết theo thứ tự ngược lại (kiểm tra xem!).

Như các ví dụ khác về nhóm biến đổi, chúng tôi đặt tên họ của tất cả các chuyển vị của mặt phẳng và tập hợp tất cả các phép biến đổi một-một của một tập hữu hạn (của $n$ phần tử) lên chính nó. Nhóm cuối cùng được gọi là *nhóm thay thế* (của $n$ phần tử) và được ký hiệu là $S_n$. (Kiểm tra các thuộc tính $1^\circ$ và $2^\circ$ cho nó và cho thấy rằng $S_n$ có các phần tử $n! = 1 \cdot 2 \cdot \dots \cdot n$.)

Từ quan điểm đại số, không tồn tại bản chất của các phần tử được biến đổi là gì, nhưng điều quan trọng là cấu trúc đại số của chính các phép biến đổi, tức là phép toán nhân $\circ$ (thành phần) trong tổng hợp $G$ được cấu trúc như thế nào. Đại số coi hai nhóm biến đổi $G$ và $H$ giống nhau nếu chúng đẳng cấu; điều này có nghĩa là có một ánh xạ một-một $\alpha : G \rightarrow H$ của nhóm $G$ và $H$ bảo toàn hoạt động hợp thành, nghĩa là thỏa mãn tính chất

$$g, g' \in G \Rightarrow \alpha(g \circ g') = \alpha(g) \circ \alpha(g').$$

Ví dụ: tập hợp tất cả các chuyển vị của một mặt phẳng chứa một số tam giác đều cố định vào chính nó là một nhóm (tại sao?) và nhóm này đẳng cấu với nhóm hoán vị của tập hợp ba phần tử $S_3$ (kiểm tra!).

Bạn có thể đọc thêm chi tiết về các nhóm biến đổi và khái niệm quan trọng của một nhóm * (trừu tượng) trong cuốn sách của P. S. Aleksandrov “Giới thiệu về Lý thuyết nhóm” (Thư viện «Kvant», số 7, M., 1980).

Mô hình đại số của trò chơi

Chúng ta sẽ chỉ ra rằng *nhóm biến đổi* của khối được đặt tên là đẳng hình với *nhóm $S_4$ hoán vị của bốn phần tử*. Để làm điều này, hãy đánh số các đỉnh của khối lập phương (hoặc, giống nhau, các khối nhỏ) với các số từ 1 đến 8, như trong Hình 2. Dễ dàng nhận thấy rằng các đỉnh $1-4$ và $5-8$ là các đỉnh của tứ diện nội tiếp trong khối, và với tất cả các phép biến đổi của chúng ta, các đỉnh $1-4$ và $5-7$ biến đổi thành nhau (và đỉnh $8$ vẫn giữ nguyên). Do đó, các phép biến đổi của chúng tôi thực hiện hoán vị các đỉnh $1-4$ và các phép biến đổi 24REM của khối lập phương được ánh xạ một-một tới các hoán vị $4! = 24$ của bốn REM và bốn REM.

Ba nước đi $X, Y, Z$ tương ứng với hoán vị của hai đỉnh: di chuyển $X$ - đỉnh $1, 2$, di chuyển $Y$ - $1, 3$ và di chuyển $Z$ - $1, 4$. Do đó, chúng tôi đã kết nối bài toán ban đầu của mình với một vấn đề khá đơn giản là biểu diễn tất cả các phần tử của nhóm sắp xếp FourREM FourREM dưới dạng tích của ba cách sắp xếp ghép đôi cơ bản của một phần tử được chọn với các khay của phần tử còn lại và chỉ ra rằng

⟦folio 16⟧

Tất cả các phần tử khác của nhóm có thể được xây dựng dưới dạng sản phẩm của không quá bốn phần tử cơ bản.

Cùng với mô hình hình học, chúng tôi đã nhận được một mô hình đại số của trò chơi của mình.

Đại số bài toán. 1. Chứng minh rằng nhóm biến đổi của khối lập phương của chúng ta được mô tả duy nhất bởi các sự tương ứng cơ bản (*); (**), (***). Điều này có nghĩa là bất kỳ mối quan hệ chính xác nào giữa các bước di chuyển X, Y, Z đều có thể thu được từ các phép chèn và cắt cơ bản. (Chèn là một thao tác trên các quan hệ trong đó một trong các phần bên trái của quan hệ chính được chèn trực tiếp vào bất kỳ vị trí nào của quan hệ đã thu được.

$$XYXY = I \Rightarrow XY(ZZ)XY = I,$$

và rút gọn là thao tác nghịch đảo của phép chèn, ví dụ:

$$ZXY(ZZ)YXZ = I \Rightarrow ZXYYXZ = I).$$

2. Chứng minh rằng hệ thức (*), (**) mô tả duy nhất nhóm các chuyển động phẳng kết hợp lưới lục giác với chính nó. (Gợi ý. Di chuyển X tương ứng với sự đối xứng của mặt phẳng so với đường phân giác vuông góc của đoạn X - xem Hình 3).

Đây chỉ là một trò chơi thôi sao?

Chúng ta hãy lưu ý để kết luận rằng trong tự nhiên có những vật thể có các tính chất tương tự như các tính chất của khối lập phương của chúng ta. Đây là những phân tử được gọi là có tính chất vật lý bên trong.

Phân tử đơn giản nhất như vậy là phân tử ethane CH₃—CH₃, trong đó một gốc metyl có thể quay tương đối với một gốc metyl khác (Hình 6). Tính chất đối xứng của các phân tử như vậy, được mô tả bởi các nhóm biến đổi khiến phân tử không thay đổi, hiện đang được nghiên cứu chuyên sâu. Và mặc dù người ta vẫn chưa biết phân tử có đối xứng bên trong chính xác như khối khoảng cách, nhưng không loại trừ khả năng tìm thấy nó. Có một phân tử "khối" bao gồm tám nguyên tử carbon và tám nguyên tử hydro (Hình 7), tương tự như mô hình được thảo luận ở đây; nhưng rõ ràng là không xảy ra sự căn chỉnh tự do của một mặt so với một mặt song song.

Cũng lưu ý rằng cấu trúc tuần hoàn kép, được thấy trong Hình 3, xảy ra như là kết quả của các tinh thể. Trong trường hợp này, các ô lục giác nhỏ tương ứng với các ô cơ bản của tinh thể, bao gồm các nguyên tử, trong khi các ô lớn hơn liên quan đến các tính chất tinh tế hơn của tinh thể - hướng quay của nguyên tử, vị trí của các đồng vị khác nhau, v.v.

Từ đó, rõ ràng là các nhóm đối xứng được nghiên cứu thuộc loại này cũng có thể trở nên thú vị xét theo quan điểm vật lý.

Sửa đổi

Trong chương trình trên p. 56 «Kvant», 1981, Số 9 bao gồm một số câu lệnh, trong đó nó biểu thị việc thiếu dấu 1 trước câu lệnh thứ năm và việc bỏ qua các dấu hiệu tiếp tục trong mục nhập câu lệnh DATA. Chúng ta. 55 cùng với CALL STR nên đọc là CALL STR.
