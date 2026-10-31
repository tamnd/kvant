---
id: 1979-11-ageev-regulyarnoe-polimino-d6073072
issue: kvant_1979_11
year: 1979
number: "11"
title: Đa thức thông thường
authors:
  - Агеев С.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 24
page_last: 25
page_labels: 22-23
tag: M9AE
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 98c75719e91c36fb37ced314c689438de908788ed202ed3b124c9039ccd43d05
prompt_sha256: draft-1
translated_from: content/ru/1979/11/articles/07_ageev-regulyarnoe-polimino-d6073072.md
source_content_sha256: d3784751c4e17d6ad3ca507554fc80178332cd07b516a57a9a148883a22d4dd7
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 22⟧

S. Adeev

Đa thức thông thường

Tên của S. V. Golomb, một nhà khoa học người Mỹ, chuyên gia trong lĩnh vực lý thuyết thông tin và thống kê, đã được nhiều người hâm mộ toán học giải trí biết đến. Golomb đã phát minh ra một loạt trò chơi đáng chú ý mà ông đặt tên chung là "polyominoes". Trò chơi này đã là chủ đề của nhiều ấn phẩm trên nhiều tạp chí. «Kvant» cũng nhiều lần đề cập đến chủ đề này, và vào năm 1975, nhà xuất bản Mir đã xuất bản một cuốn sách của tác giả của phát minh này, trong đó có nhiều toán học hay và thú vị bài toán *).

Đây là một ví dụ về “đa thức” bài toán (nó được đặt ở một trong các số «Kvant»): Chứng minh điều đó từ ba góc và số ô tương ứng, nhưng nó cực kỳ khó chứng minh. Theo quy định, bài toán như vậy không thể khám phá phương pháp vũ phu ngay cả với một máy tính nhanh. Vì vậy, đối với lời giải của họ có những phương pháp rất khéo léo. Một trong số đó, chủ yếu là trên các trang tô màu, được mô tả trong «Kvant» Số 11 năm 1972. Trong bài viết này, chúng ta sẽ nói về một cách tiếp cận hoàn toàn khác liên quan đến... địa lý và xúc xắc.

Địa lý trên giấy ca rô và xúc xắc

Tất cả các sự kiện tiếp theo trong bài viết của chúng tôi sẽ diễn ra trên giấy ca rô được đánh dấu “định hướng địa lý” (Hình 2). Trên tờ giấy ca rô này, theo một số quy tắc nhất định, chúng ta sẽ tung một con xúc xắc thông thường - một khối lập phương có cạnh có chiều dài đơn vị và các mặt được đánh số. Khối lập phương sẽ luôn được đặt trên giấy sao cho tâm của cạnh dưới trùng với nút lưới và các cạnh bên song song với các đường lưới. Đối với mỗi vị trí của khối lập phương trên tờ giấy ca rô, chúng ta sẽ gán hai số - số mặt nam và mặt trên. Hãy xác định cặp số này theo hướng của khối lập phương.

Bài tập 1. Hình lập phương có bao nhiêu hướng khác nhau?

Cho một đường dẫn Γ nối các nút A và B của lưới. Tất nhiên, chúng tôi sẽ xem xét các đường dẫn chỉ có ở Ấn Độ dọc theo các đường lưới. Nếu khối nằm trên nút A thì nó có thể

*) “Polymino” (M., “Mir”, 1975)

Hình 1.

Hình 2.

⟦folio 23⟧

cuộn dọc theo đường Γ đến nút B (Hình 3). Trong trường hợp này, hướng ban đầu α của nó sẽ được thay thế bằng hướng β nào đó. Chúng ta sẽ viết điều này như sau: β = Γ(α).

Làm mềm Y 2. Đặt các nút A và B và hướng ban đầu α cố định. Chứng minh rằng bằng cách lăn khối lập phương dọc theo tất cả các đường có thể từ A đến B, bạn chỉ có thể thu được không quá một nửa hướng của khối lập phương. Đảm bảo luôn có sẵn những hướng dẫn hữu ích.

Nếu điểm cuối của đường dẫn Γ₁ trùng với điểm bắt đầu của đường dẫn Γ₂, thì đường dẫn Γ₂°Γ₁ sẽ xuất hiện, bao gồm hai đường dẫn này (Hình 4). Ngoài ra, đối với mỗi đường dẫn Γ, đường dẫn "đảo ngược" Γ⁻¹ được xác định một cách tự nhiên, điều này có được bằng cách thay thế hướng dọc theo đường dẫn Γ bằng hướng đối diện. Thật dễ dàng để xác minh (làm điều này) rằng (Γ₂°Γ₁)(α) = Γ₂(Γ₁(α)) và Γ⁻¹(Γ(α)) = α.

Chúng ta gọi đường đi là Γ hình cầu nếu Γ(α) = α đối với một hướng α nào đó.

Y làm mềm 3. Chứng minh rằng a) nếu Γ là đường chính quy thì Γ(β) = β với mọi hướng β;
b) nếu Γ là đường đi chính quy thì Γ⁻¹ là đường đi chính quy;
c) nếu Γ₁ và Γ₂ là các đường dẫn thông thường và đường dẫn Γ₂°Γ₁ được xác định thì Γ₂°Γ₁ là đường dẫn thông thường.

4. Chứng minh rằng mọi đường đi chính quy đều có độ dài chẵn và cho ví dụ về đường đi không chính quy có độ dài chẵn.

Đa thức thường xuyên

Bây giờ chúng ta hãy quay trở lại đa thức. Hãy nhớ lại rằng polymno là một đa

năm, một hình vuông được tạo thành từ các ô vuông đơn, với bất kỳ ô nào liền kề với ít nhất một ô liền kề ở một bên (nghĩa là quân cờ có thể di chuyển từ bất kỳ ô nào sang bất kỳ ô nào khác). bài toán tổng quát từ lý thuyết đa thức được xây dựng như sau: có thể thêm một hình đã cho từ một tập hợp các đa thức nhất định không? Chúng ta sẽ có thể giải được cả một lớp bài toán như vậy. Chúng ta sẽ coi đa thức là một đa giác được vẽ trên giấy ca rô của chúng ta. Chúng ta là đa chính quy tại nút A nếu đường đi tìm kiếm dọc theo đường viền của nó với điểm bắt đầu và kết thúc tại nút A nằm trên đường viền này là chính quy. Hóa ra định nghĩa này không phụ thuộc vào nút được chọn.

Độ pha loãng là 5. Nếu một polymnoy chính quy tại một nút nào đó trên đường viền của nó thì nó chính quy ở bất kỳ nút nào khác. Chứng minh điều đó.

Bài tập 5 cho chúng ta cơ hội nói đơn giản về đa thức chính quy. Một số đa thức như vậy được thể hiện trong Hình 5.

U pha loãng 6. Chứng minh rằng các đa thức này là đều.

Hóa ra là bạn không thể sử dụng một polymno không thông thường từ các polymno thông thường. Để chứng minh điều này, chỉ cần chứng minh điều sau là đủ:

Định lý tổng hợp. Nếu đa thức P và Q là dạng rezular và đa thức T được tạo thành từ chúng thì nó có thể là dạng rezular.

Giải thích cho việc chứng minh định lý này được đưa ra trong Hình 6.

Cũng có thể chứng minh định lý sai phân: nếu đa thức T gồm đa thức P và Q là dạng rezular và đa thức P là rezular thì đa thức Q cũng là rezular.

Pha loãng Y 7. Chứng minh định lý về sự khác biệt đa thức.

Phép giãn Y 8. Chứng minh rằng một đa thức hình chữ nhật là chính quy khi và chỉ khi diện tích của nó là bội số của 4.

Từ định lý tổng và bài tập 6 và 8, ngay lập tức suy ra lời giải bài toán, tương tự như bài toán về nút thắt, để chứng minh rằng từ bất kỳ số đa thức nào được hiển thị trong Hình 5, không thể cộng một hình chữ nhật có diện tích không phải là bội số của 4.
