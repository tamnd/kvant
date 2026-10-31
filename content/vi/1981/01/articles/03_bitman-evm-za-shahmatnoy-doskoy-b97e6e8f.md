---
id: 1981-1-bitman-evm-za-shahmatnoy-doskoy-b97e6e8f
issue: kvant_1981_1
year: 1981
number: "1"
title: Máy tính ở bàn cờ
authors:
  - Битман А. Р.
  - Гик Е. Я.
rubric: osnovnye-stati
page_first: 13
page_last: 19
page_labels: 11-17
tag: GPH8
lang: vi
source: kvant_digital
extraction: vision
content_sha256: ea0c2e2a1096ef85e4216beea2d10cd477c6b2b2f3532b692271e566f83b36cb
prompt_sha256: draft-1
translated_from: content/ru/1981/01/articles/03_bitman-evm-za-shahmatnoy-doskoy-b97e6e8f.md
source_content_sha256: 7b34c53f3c14142ab530d4d2e9233f3133d7f2e8a645a2ce16546f0d5091752b
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 11⟧

A. Bitman, E. Gik

Máy tính ở bàn cờ

Trong kinh tế, trong các vấn đề quản lý, trong việc lập kế hoạch dài hạn, hay nói cách khác là trong cái gọi là hệ thống lớn, việc lựa chọn một lời giải đủ tốt có vẻ khó khăn bài toán. Thực tế là một quyết định phải được đưa ra trong một thời gian giới hạn, trong một tình huống phức tạp, luôn thay đổi, tùy thuộc vào một số lượng lớn các yếu tố không thể đánh giá một cách rõ ràng và tính đến một cách máy móc. Ở đây không thể thực hiện được nếu không có các phương tiện kỹ thuật hiện đại có thể đảm nhận một phần công việc trí tuệ.

Ý nghĩa của tự động hóa hiện đại là chuyển sang máy tính các chức năng như nhận thức tình huống, xử lý các đối tượng thông tin lớn, khả năng so sánh và đánh giá các tình huống khác nhau và đưa ra kết luận hợp lý.

Để máy tính có thể giải được tất cả bài toán này, cần phải chính thức hóa chúng, sau đó phát triển các thuật toán đủ hiệu quả (nghĩa là có thể thu được lời giải) và cuối cùng, triển khai các thuật toán này dưới dạng một chương trình máy tính.

Đây là nơi... cờ vua sẽ giúp ích cho chúng ta. Chúng đại diện cho một mô hình rất tiện lợi của một “hệ thống lớn”. Thật vậy, trong cờ vua, người ta dễ dàng đặt ra các mục tiêu cuối cùng và nhiều mục tiêu trung gian, nhưng không thể đưa ra một công thức chính xác để đạt được chúng. Chọn lối thoát trong ván cờ là sự chấp nhận lời giải trong tình huống khó khăn được mô tả ở trên. Đó là lý do tại sao các nhà khoa học ở nhiều quốc gia nghiên cứu về vấn đề trí tuệ nhân tạo đã chọn cờ vua làm hình mẫu xuất sắc cho nghiên cứu của mình.

Dạy máy chơi cờ không quá khó. Chỉ cần chọn một số cách mã hóa các trường bàn cờ là đủ

⟦folio 12⟧

bảng và các quân cờ, sau đó viết một chương trình xác định tất cả các nước đi hợp pháp ở một vị trí nhất định. Bằng cách thực hiện bất kỳ động thái nào trong số này, máy sẽ chơi cờ. Không khó để tưởng tượng chất lượng của một trò chơi như vậy!
Nhưng dạy một cỗ máy chơi cờ giỏi là bài toán cực kỳ khó. Để giải quyết nó, bạn cần học cách tìm ra nước đi tốt nhất có thể ở vị trí đã trình bày. Làm thế nào để xây dựng một thuật toán tìm ra một động thái như vậy? Đồng thời, điều quan trọng là thuật toán cung cấp lời giải với bài toán đã cho không phải về mặt lý thuyết mà trên thực tế, tức là nó cho phép bạn chọn một nước đi trong thời gian hợp lý. Để chuẩn bị cho lời giải bài toán này, chúng ta sẽ phải tập hợp một số thuật ngữ và khái niệm được sử dụng trong lý thuyết trò chơi nói chung.

Một số thông tin từ lý thuyết trò chơi
Cờ vua là một trò chơi hữu hạn với thông tin đầy đủ. Về mặt này, chúng không khác gì trò chơi tic-tac-toe đơn giản nhất trên bàn cờ $3 \times 3$. Đối với những trò chơi như vậy, hầu hết mọi thứ đều được biết về mặt lý thuyết, cấu trúc của chúng hoàn toàn rõ ràng. Ở mọi vị trí đều có một nước đi tốt nhất (có thể không phải là nước đi duy nhất). Trình tự các nước đi tốt nhất của cả hai bên sẽ dẫn trò chơi tưởng tượng này đến một kết quả rõ ràng. Theo nghĩa này, họ nói rằng kết quả của trò chơi ở bất kỳ vị trí nào, kể cả vị trí ban đầu, đều được xác định trước. Nhưng nếu trong trò chơi tic-tac-toe, trận đấu kết thúc với tỷ số hòa nếu các bên đang chơi, thì trong cờ vua, câu hỏi về vị trí ban đầu được xác định trước chính xác như thế nào rõ ràng sẽ vẫn còn bỏ ngỏ.

Bằng chứng cho thấy kết quả của một ván cờ ở bất kỳ thế cờ nào đều được xác định trước được nhà toán học người Ý Zermelo đưa ra lần đầu tiên vào năm 1913. Chúng tôi trình bày nó ở đây vì nó cần thiết để hiểu rõ hơn.

Chúng ta hãy biểu thị vị trí cờ vua ban đầu (không nhất thiết là vị trí ban đầu) bằng $P_0$ (Hình 1), giả sử có một nước trắng trong đó (vị trí có nước trắng tương ứng với vòng tròn màu trắng và vị trí có nước đi màu đen tương ứng với vòng tròn màu đen). Hãy thực hiện tất cả các nước đi có thể có cho Trắng từ $P_0$, từ mỗi vị trí có được - tất cả các nước đi có thể có cho Đen, v.v. Về mặt đồ họa, quy trình này được gọi là `дерево церры`, bắt đầu tại $P_0$ (gốc của cây).

Các vị trí không thể di chuyển được nữa (tức là bàn cờ đã chiếu hết hoặc bế tắc) được gọi là `заключительный`. Hãy để chúng tôi giới thiệu các ước tính tự nhiên cho họ: $1$—thắng trắng, $1/2$—hòa, $0$—đen thắng. Nếu một vị trí nhất định dọc theo nhánh được lặp lại thì vị trí đó cũng sẽ được coi là vị trí cuối cùng và điểm $1/2$ sẽ được ấn định cho vị trí đó. Vì số lượng thế cờ là hữu hạn nên ván cờ nào cũng sẽ đạt đến vị trí cuối cùng sau một số nước đi hữu hạn.

Đặt độ dài tối đa của một ván đấu bắt đầu từ $P_0$ bằng $N$ nước đi (theo khái niệm nước đi, chỉ một bên di chuyển). Hãy xem xét tất cả các trò chơi có độ dài $N$ một nước đi trước khi kết thúc. Trong Hình 1 bên dưới, các dấu chấm tương ứng với vị trí cuối cùng (mức $N$). Hãy để chúng tôi chứng minh rằng các đánh giá có thể được chuyển từ cấp $N$ sang cấp $(N-1)$ bằng cách sử dụng các quy tắc đơn giản. Đặt $A$ là vị trí mà từ đó tất cả các nước đi đều dẫn đến vị trí cuối cùng. Vì chúng tôi biết ước tính của họ nên chúng tôi cũng có thể thiết lập ước tính cho vị trí $A$. Nếu quân Trắng đi (như trong Hình 1), thì điểm của quân Trắng bằng với số điểm tối đa của quân Trắng.

⟦folio 13⟧

các vị trí quan trọng có thể đạt được từ $A$. Nếu quân Đen đi ở $A$, thì thay vì lấy điểm tối đa, nên lấy điểm tối thiểu. Trong trường hợp của chúng tôi, Trắng có thể thực hiện 4 nước đi từ $A$. Hai trong số đó dẫn đến một trận hòa, hai đến một chiến thắng. Điểm cho vị trí $A$ là 1.

Sau quy trình được mô tả, tất cả các vị trí của cấp độ cây trò chơi ($N-1$) sẽ được đánh giá. Thật vậy, một số vị thế này đã được ký kết ngay từ đầu và đã được định giá, phần còn lại nhận được nó theo quy tắc quy định. Bây giờ bạn có thể xóa tất cả các vị trí của cấp độ $N$ khỏi cây trò chơi và tiếp tục quy trình được mô tả trên một cây mới được cắt tỉa nhẹ. Kết quả là tất cả các vị trí ở cấp độ ($N-2$) sẽ được đánh giá, v.v.

Do đó, mỗi khi một vị trí có độ hội tụ của Trắng được ấn định là mức ước tính tối đa của các vị trí có thể đạt được từ nó và một vị trí có độ hội tụ của Đen được ấn định ở mức tối thiểu. Quy trình này được gọi là *tối thiểu hoặc tối đa*. Áp dụng minimax lần cuối cùng, tức là ở bước thứ $N$, chúng ta tìm thấy ước tính của vị trí ban đầu $P_0$, đồng thời di chuyển tốt nhất từ ​​đó. Điều này kết thúc bằng chứng.

Lưu ý rằng quy trình minimak là nền tảng của hầu hết các chương trình chơi game. Chỉ trong trường hợp này, các vị trí thu được từ vị trí được phân tích trong một số lần di chuyển nhất định, không quá lớn mới được coi là tù nhân.

Dựa trên phương pháp của Zermelo, chúng ta có thể tạo ra một thuật toán giải chính xác bài toán của mình và chọn nước đi tốt nhất ở vị trí đó. Tuy nhiên, từ quan điểm thu được kết quả, đây sẽ là một thuật toán hoàn toàn phi thực tế. Máy sẽ không di chuyển, vì việc duyệt toàn bộ cây trò chơi, cả ở trình độ công nghệ hiện tại và trong tương lai gần, rõ ràng sẽ vượt quá khả năng của nó.

Cách tiếp cận chung để tạo chương trình cờ vua

Năm 1950, nhà toán học nổi tiếng người Mỹ K. Shannon đã xuất bản một bài báo trong đó ông đưa ra cách tiếp cận chung để xây dựng các chương trình cờ vua. Trước hết, ông đưa ra khái niệm *hàm đánh giá*, hàm này liên kết mỗi thế cờ với một con số (điểm) xác định. Ông còn đề xuất thêm việc tìm kiếm thông qua các tùy chọn ở một độ sâu cố định nhất định và đánh giá các vị trí đầu cuối thu được bằng cách sử dụng chức năng đánh giá. Nước đi tốt nhất sau đó được xác định theo các quy tắc của thủ tục minimax.

Shannon đã chỉ ra hai sơ đồ tìm kiếm khả thi. Theo sơ đồ đầu tiên, trong quá trình này, cây trò chơi bị cắt bớt được coi là các cuộc tụ tập được phép theo quy tắc của trò chơi. Kế hoạch thứ hai sẽ chỉ liệt kê những động thái mà theo một số báo cáo được coi là hợp lý. Khi thực hiện sơ đồ bạo lực, rất khó để đạt được độ sâu tính toán lớn, vì cây bạo lực thảm khốc phát triển nhanh chóng. Trong trường hợp thứ hai, các vấn đề nảy sinh liên quan đến việc xác định tính “hợp lý” của các nước đi.

Với tư cách là một hàm đánh giá, Shannon đề xuất sử dụng đa thức có dạng $\sum_{i=1}^{k} a_i p_i$, trong đó $k$ là số lượng đối tượng địa lý của vị trí, $a_i$ là “trọng số” của đối tượng địa lý, $a_p$ bằng 1 hoặc 0 tùy thuộc vào sự hiện diện hay vắng mặt của đối tượng địa lý này trong vị trí. Bằng cách sử dụng chức năng đánh giá, bạn có thể tính đến sự tương ứng vật chất với các yếu tố vị trí: quân tốt yếu, sở hữu trung tâm, đường mở, tính di động của quân cờ, v.v.

Câu hỏi đặt ra: liệu có thể đưa ra hàm đánh giá cột (không nhất thiết phải thuộc loại được chỉ định) cho phép chúng được sử dụng ở bất kỳ vị trí được đề xuất nào không? Với sự trợ giúp của chức năng như vậy, bạn có thể chơi cờ mà không gặp lỗi mà không cần phải thực hiện tìm kiếm tẻ nhạt. Nước đi tốt nhất là nước đi dẫn đến vị trí có số điểm tối đa*).

*) Nói một cách chính xác, để có một ván cờ tối ưu bạn cũng nên học bao nhiêu nước đi để giành được một vị trí. Để làm điều này, theo định lý của Zermelo, chỉ cần ấn định điểm $\pm 1/n$ cho các vị trí chiến thắng và 0 cho các vị trí hòa ($n$ là độ dài của nhánh dẫn đến một vị trí nhất định).

⟦folio 14⟧

Thực tế là hàm đánh giá như vậy tồn tại về nguyên tắc xuất phát từ định lý Zermel. Các giá trị của hàm này có thể được chỉ định dưới dạng bảng, cột bên trái là tập hợp tất cả các vị trí cờ vua và cột bên phải là điểm của chúng (1, 0, 1, 2). Tuy nhiên, bàn cờ này sẽ chỉ rộng bằng cái cây hoàn chỉnh của một ván cờ. Tất nhiên, chúng tôi không quan tâm đến hàm đánh giá bảng mà còn quan tâm đến hàm sử dụng các đặc tính thống kê của vị trí làm đối số. Không thể chứng minh điều này, nhưng rất có thể, một hàm đánh giá lý tưởng dựa trên các đặc điểm đơn giản và rõ ràng của một vị trí sẽ cồng kềnh như hàm bảng. Rõ ràng là có thể xây dựng một hàm nhỏ gọn, nhưng khi đó các biển báo phải quá “thông minh”.

Những khó khăn gặp phải trong việc tạo ra một hàm ước lượng tốt là điều đương nhiên và phản ánh sự phức tạp của ván cờ. Những thông điệp được đưa ra cho thấy khó có thể có được một ván cờ bất bại. Để minh họa, hãy xem xét ví dụ sau.

Ở thế cờ ở Hình 2, Trắng có lợi thế về vật chất nhưng cả hai quân tượng của ông đều đang bị tấn công, dễ dàng nhận thấy kết cục là hòa. Hãy thay đổi vị trí một chút bằng cách thêm một con tốt vào màu đen trên c5. Như thể điều này chỉ có thể làm cho vị thế của Đen trở nên tồi tệ hơn, anh ta cũng thua màu tương tự: 1. h7+! Kr:h7 2. Ca4! R:b2+ 3. Cc2+! R:c2+ 4. Kpf3, và bếp lò của chính anh ta đã ngăn cản quân đen quay trở lại hạng cuối cùng. Vai trò chí mạng của con tốt c5 chỉ được bộc lộ trong quá trình liệt kê các phương án. Bây giờ hãy tưởng tượng một hàm được đánh giá có thể sắp xếp tất cả những điều này, tức là đặt trước (cho Trắng) vị trí thứ hai bằng cây bút!

Các chức năng đánh giá được sử dụng trong các chương trình cờ vua thực tế thường bao gồm hai thành phần - chất liệu và vị trí. Tính toán thành phần vật liệu đơn giản và tùy ý

Cơm. 2.

Một đứa trẻ theo thang giá trị tương đối của một hàm được người chơi cờ áp dụng. Đối với thành phần vị trí, có thể xem xét các đánh giá vị trí khác nhau và như thực tế cho thấy, việc thể hiện hợp lý trọng lượng tính năng không ảnh hưởng đến cường độ chơi của máy. Điều quan trọng hơn nhiều là việc tính đến yếu tố vị trí này hay yếu tố vị trí khác.

Rõ ràng, khi tạo một chương trình, các yếu tố như tính di động của chức năng, quyền sở hữu trung tâm và đường mở, sự an toàn của vua và trong cấu trúc đã giải quyết - phalanx, điểm mạnh, lối đi, con tốt nhân đôi và cô lập, v.v. Hãy xem xét một trong những yếu tố - sở hữu trung tâm. Đây là cách chức năng được đánh giá của chương trình “Kanssa” của Liên Xô diễn giải nó: tâm theo quan điểm của White được coi là các hình vuông e4, d4, e5, d5, e6, d6; một quân tốt hoặc quân phụ đứng ở trung tâm cho 20 đơn vị thông thường; một đòn bằng quân tốt hoặc quân vào ô trung tâm có giá trị 10 đơn vị. Để làm rõ thang đo, chúng tôi thêm rằng tính di động của một hàm được xác định bởi số lượng trường mà nó chứa và một số được thêm vào cho mỗi trường.

Trong các giai đoạn khác nhau của một ván cờ (khai mạc, giữa ván, tàn cuộc), việc đánh giá một số yếu tố thế trận có thể tồn tại. Theo đó, các chương trình mạnh có thiết lập chức năng đánh giá, nghĩa là chức năng mà tập hợp các tính năng và trọng số của chúng được chính chương trình xác định tùy thuộc vào tình huống trên bảng. Đặc biệt, “Kansa” có 4 trạng thái như sau:

⟦folio 15⟧

re - ba dành cho ba giai đoạn của trò chơi và giai đoạn thứ tư được sử dụng để chiếu tướng vua đối phương với lợi thế vật chất áp đảo.

Phương pháp lập trình cờ vua hiện đại

Bất kỳ chương trình cờ vua nào bằng cách này hay cách khác đều thực hiện một số loại sơ đồ tìm kiếm toàn diện. Trong phần này chúng ta sẽ xem xét các phương pháp và thuật toán phổ biến trong các chương trình cờ vua đang chạy quy mô lớn.

1°. Phương pháp các cạnh và ước tính
Một phương pháp giảm thiểu tìm kiếm rất hiệu quả là phương pháp cạnh và ước tính, hiện đang được sử dụng trong tất cả các chương trình chơi game. Chúng ta hãy xem xét nó chi tiết hơn. Để làm điều này, chúng tôi chọn một đoạn nhất định từ cây trò chơi, được hiển thị dưới dạng sơ đồ trong Hình 3.

Để Trắng ở vị trí $A$ đã nghiên cứu nước đi $AB$ (tức là nước đi dẫn từ vị trí $A$ đến vị trí $B$). Trong trường hợp này, tiểu mục tương ứng có đỉnh $B$ do minimka phải có vị trí $B$ điểm $+20^*$). Điều này có nghĩa là, khi thử các nước đi khác từ $A$ khi đi xuống cây, Trắng sẽ không bao giờ đồng ý với số điểm nhỏ hơn hoặc bằng 20 (vì nước đi $AB$ mang lại cho anh ta số điểm này).

Điểm $+20$ là điểm được đảm bảo của vị trí $A$ (đối với Trắng), hay nói cách khác là giới hạn dưới của nó. Khi di chuyển xuống cây, số điểm đảm bảo mỗi lần được chuyển đến vị trí tương ứng qua một cấp độ.

Bây giờ hãy để Trắng tiếp tục tìm kiếm, thử nước đi $AC$ và Đen đáp lại bằng nước đi $CD$. Đối với đỉnh $D$, ước tính của nó cho đến nay được viết là $+20$, được chuyển từ $A$. Nếu bây giờ số điểm được đưa đến vị trí $D$ không quá 20, điều này có nghĩa như sau:

*) Ở đây và những điều tiếp theo, điểm số được hiểu theo quan điểm của Trắng (đối với Đen, điểm của vị trí này là 20).

1. Nước đi $AC$ không tốt hơn $AB$ (với nước đi đáp số Đen $CD$ đúng, điểm của Trắng sẽ không cao hơn nước đi $AB$). Chúng tôi sẽ gọi hành động này là $AC$ xấu.

2. Nước đi $CD$ xác định nước đi $AC$ (theo nghĩa đã chỉ ra). Chúng tôi sẽ gọi nó là kết thúc.

3. Các nước đi khác của quân đen từ vị trí $C$ không cần phải xem xét.

Trong trường hợp này, quá trình đếm ngược được cho là sẽ xảy ra và các bước di chuyển $CE$ và $CF$ không còn được nghiên cứu nữa.

Điều quan trọng cần lưu ý là trong phương pháp mô tả, thứ tự các nước đi được xem xét là quan trọng hơn. Giả sử rằng các bước di chuyển đã được thử trước tiên $CE$ Và $CF$ và chỉ sau đó $CD$. Nếu chúng là một trong những động thái $CE$ Và $CF$ hóa ra không kết thúc thì chúng ta sẽ lãng phí thời gian để xem xét những lựa chọn không cần thiết.

Chúng ta hãy giả sử rằng điểm yếu của vị trí $C$ bằng +30. Điều này có nghĩa là trong tương lai việc tìm kiếm sẽ chỉ xem xét những vị trí có ước tính nằm trong khoảng ]20, 30[.

Giả sử điểm của vị trí $D$ do spiz mang lại bằng 25. Khi đó nước đi $CD$ được gọi là cải thiện, điểm đảm bảo của vị trí $C$ trở thành bằng 25, Đen tiếp tục tìm kiếm với nước đi $CE$ và sẽ thực hiện trong giới hạn ]20, 25[.

There are subsequent countdowns that improve the move. Các nước đi $CE$ và $CF$ có thể cải thiện hơn nữa điểm số cho Đen hoặc thậm chí chứng tỏ là một nước đi kết thúc.

⟦folio 16⟧

Trong mọi trường hợp, việc tìm kiếm sẽ bị giảm nếu nước đi tốt nhất được thử trước.

Finally, if the score of position $D$ turns out to be at least 30, then move $CD$ will be bad. Black will continue the search with $CE$ within the same boundaries. Trong trường hợp tất cả các nước đi từ đỉnh $C$ đều bằng phẳng, nước đi $AC$ của Trắng trở nên khép lại và Đen sẽ phải thay đổi nước đi dẫn đến vị trí $A$.

Trong ví dụ được xem xét, các ranh giới được lấy trực tiếp từ việc tìm kiếm dưới dạng ước tính tối thiểu. Tuy nhiên, khi chúng ta mới bắt đầu tìm kiếm thì vẫn chưa có ranh giới hoặc có thể coi là vô tận. Trong trường hợp này, lần đầu tiên trước vị trí cuối cùng, chương trình thậm chí sẽ chấp nhận việc mất đi nữ hoàng. Nước đi tốt nhất cuối cùng sẽ được tìm ra, nhưng phải trả giá bằng việc xem xét vô số lựa chọn.

To avoid this, it is common to set some boundaries at the beginning of the search. Chúng có thể có được theo nhiều cách khác nhau, chẳng hạn như bằng cách kiểm tra tìm kiếm nông cạn hoặc sử dụng một số loại hình lệnh bảo đảm (xem bên dưới). It is only important that the original boundaries turn out to be more accurate or less reliable.

Trong trường hợp chúng tôi không thể xác định ranh giới và ước tính thu được khi tìm kiếm không rơi vào chúng, chúng tôi phải di chuyển ranh giới theo phía tìm kiếm. Việc lặp lại là bắt buộc nếu việc tìm kiếm đưa chúng ta đến giới hạn dưới - tất cả các nước đi trong giới hạn đã thiết lập đều “thua”. Ở đây cần phải thay đổi ranh giới để chọn ít zoll hơn. Nếu điểm số bằng giới hạn trên và đồng thời nước đi “thắng” (dẫn đến giới hạn này) là nước đi duy nhất thì đó sẽ là nước đi tốt nhất, mặc dù chúng ta chưa biết sức mạnh thực sự của nó. Việc dịch chuyển ranh giới sang bên phải và việc tìm kiếm lại chỉ xảy ra nếu có những nước đi cạnh tranh giành chiến thắng.

Thuật toán được mô tả thường được gọi là quy trình $\alpha$-β, đề cập đến việc chỉ định các mặt $] \alpha, \beta]$. Hiệu quả của thuật toán này phụ thuộc hoàn toàn vào chất lượng của thứ tự di chuyển trong tìm kiếm. Vì vậy, nếu nước đi tốt nhất vượt qua trước, thì nhìn chung sẽ thiếu việc chỉ xem xét khoảng $\sqrt{n}$ vị trí, trong đó $n$ là toàn bộ khối lượng của cây tìm kiếm.

$2^\circ$. Phiên bản cưỡng bức Khi nói về chức năng đánh giá, chúng tôi lưu ý rằng nó chỉ tính đến các đặc tính thống kê của vị trí và do đó nó chỉ có thể được tin cậy trong những tình huống tương đối bình tĩnh, trong đó một trong các bên không thể thay đổi sự tương ứng vật chất của các lực lượng theo hướng có lợi cho mình bằng những nước đi gần. Nếu chúng ta xử lý phép tính hoàn toàn một cách máy móc khi đạt đến độ sâu tìm kiếm tối đa, thì có thể bên có quyền đi tiếp sẽ thắng một quân cờ hoặc thậm chí tuyên bố chiếu tướng.

Để tránh những lỗi tính điểm này, nhiều phương pháp phỏng đoán khác nhau đã được phát minh để tận dụng tốt hơn chức năng tính điểm. Tuy nhiên, một trong những phương pháp này là “phiên bản bắt buộc” hay viết tắt là PV. Được triển khai như một chương trình con, PV được chương trình chính sử dụng tại nhiều điểm khác nhau trong trò chơi và cho các mục đích khác nhau, nhưng mục đích chính của nó là thu được ước tính đáng tin cậy cho các vị trí cuối cùng của cây tìm kiếm.

PV là một sơ đồ tìm kiếm không từ chối với các quy tắc riêng để chọn nước đi ứng cử viên và phương pháp phỏng đoán riêng. Các nước đi hợp lệ trong PV là các bước bắt, biến đổi, kiểm tra và đáp số để kiểm tra, tức là các nước đi có thể tồn tại trong một tình huống trên bàn cờ. Việc tìm kiếm được thực hiện trong một số ranh giới nhất định được thiết lập trước. Ý tưởng chính của PV là như sau: bên nào có quyền di chuyển và không bị kiểm soát có thể đánh giá thế trận đã phát sinh và đưa ra ước tính thống kê này. Theo đó, trong PV, điều hợp lý là nên cân nhắc xem nước đi tốt nhất có được thử trước hay không.

⟦folio 17⟧

Cơm. 4. Bogolyubov-Capablanca (New York, 1924).

Không phải tất cả đều được lấy đi mà chỉ những thứ giữ lại vật liệu ít nhất ở mức giới hạn dưới của chúng.

Nếu ý anh ấy là người cộng tác giữa con người và máy móc, thì việc biết kết quả của PV ở một vị trí nhất định sẽ giúp ích rất nhiều cho người chơi cờ. Thông thường, những sự kết hợp không rõ ràng diễn ra theo hướng một lệnh bắt buộc thuần túy. Hãy xem một ví dụ từ một ván đấu của các đại kiện tướng nổi tiếng (Hình 4).

Quân đen ở vị trí này chơi: 1...K:d4!, và sau 2. cd R8:c5! Bogolyubov đã làm được, vì trên 3. dc nghiệm là 3...Q:c5+ và 4...R:c1.. Một chương trình sử dụng FV sẽ tìm thấy sự kết hợp này ngay cả với độ sâu tính toán là một nửa bước đi.

FV lần đầu tiên được triển khai dưới dạng chương trình vào năm 1962 tại một trong những phiên bản đầu tiên của Kansa. Hiện nay, nó được nhiều chương trình cờ vua sử dụng tích cực.

3°. Thứ tự khoảng cách di chuyển ở một vị trí. Bây giờ chúng ta hãy tập trung vào các phương pháp cho phép chúng ta đạt được thứ tự di chuyển chất lượng cao trong các vị trí của cây tìm kiếm. Như đã trình bày ở trên, vấn đề này rất quan trọng đối với thời gian chạy của một chương trình cờ vua.

Các bước di chuyển từ gốc cây cần được sắp xếp chính xác hơn. Điều này sẽ góp phần vào việc xuất hiện tối đa các đoạn cắt trong quá trình tìm kiếm. Vì mục đích này, sau mỗi nước đi, một PV sẽ được áp dụng, mang lại điểm cho nước đi đó.

Ở cấp độ tìm kiếm sâu hơn, phương tiện chẩn đoán chất lượng chuyến đi sẽ đa dạng hơn. Nếu có thể lấy quân không được bảo vệ hoặc ăn quân mạnh với quân yếu thì nước đi ứng cử viên đó sẽ được xem xét trước tiên. Đây được gọi là những khoản hối lộ có lợi nhuận. Trong số những điều đầu tiên còn có trường hợp không có quân cờ khi chúng bị tấn công (quy tắc “tấn công”). Sẽ rất hiệu quả khi bắt được quân vừa di chuyển của đối thủ. Tất cả những thứ khác đều như nhau, sẽ có lợi hơn khi bắt đầu bằng việc di chuyển đến các ô bất bại, v.v.

Tất cả những thông điệp này phục vụ cho việc đánh giá trước tiến độ. Chúng chắc chắn hữu ích, mặc dù hơi trừu tượng. “Dịch vụ di chuyển tốt nhất” sẽ ra tay giải cứu, cho phép bạn tính đến tính năng động của vị trí. Dịch vụ trợ giúp này ghi nhớ những động thái hóa ra là tốt nhất (nghĩa là kết thúc hoặc cải thiện) ở các cấp độ khác nhau trong quá trình tìm kiếm. Những động thái này sau đó được đề xuất khi ứng cử viên di chuyển vào các vị trí mới nổi. Điều thú vị là khi Kansa lần đầu sử dụng “dịch vụ di chuyển tốt nhất”, thời gian vận hành của máy đã giảm hơn 10 lần.

Tóm lại, cần lưu ý rằng nhiều vấn đề thú vị vẫn chưa được chúng tôi xem xét. Ngoài ra, người ta không nên nghĩ rằng những ý tưởng và phương pháp được sử dụng để lập trình một ván cờ được mô tả trong bài viết này là những ý tưởng và phương pháp duy nhất khả thi. Vì vậy, cựu vô địch thế giới, Tiến sĩ Khoa học Kỹ thuật M. M. Botvinnik, người hiện đang nghiên cứu các vấn đề lập trình cờ vua, lại đi theo một con đường khác *). Tương lai sẽ cho thấy con đường nào lời giải dẫn đến bài toán này sẽ hiệu quả hơn.

*) Xem cuốn sách của M. M. Botvinnik “Từ cờ vua đến cỗ máy” (M., “Văn hóa thể chất và thể thao”, 1979).
