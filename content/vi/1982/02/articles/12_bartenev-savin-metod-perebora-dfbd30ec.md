---
id: 1982-2-bartenev-savin-metod-perebora-dfbd30ec
issue: kvant_1982_2
year: 1982
number: "2"
title: Phương pháp vũ phu
authors:
  - Бартенев Ф. А.
  - Савин А. П.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 38
page_last: 40
page_labels: 36-38
tag: UJ2R
lang: vi
source: kvant_digital
extraction: vision
content_sha256: faebe45660710a33b587f3fdbc838a36d56f4d64412138c4618c6efdfa9af183
prompt_sha256: draft-1
translated_from: content/ru/1982/02/articles/12_bartenev-savin-metod-perebora-dfbd30ec.md
source_content_sha256: 90c0eee8e4912cc70e5db0754a9d87e47a7d4b2d645a3aa94c5fb21f99a55945
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 36⟧

F. Bartenev, A. Savin

Phương pháp vũ phu

Họ kể rằng một ngày nọ, cháu trai của Sherlock Holmes là Jack đã đến gặp người chú nổi tiếng của mình với yêu cầu giúp đỡ trong lời giải sau bài toán*): Họ đã mua một số cuốn sách và album giống hệt nhau. Họ trả 10 rúp cho những cuốn sách. 56 kopecks Bạn đã mua bao nhiêu cuốn sách nếu giá một cuốn sách cao hơn giá một album hơn 1 rúp và bạn mua nhiều hơn 6 cuốn so với album?

Đọc xong điều kiện, vị thám tử nổi tiếng đi từ bàn đến cửa sổ, rồi quay lại bàn, đứng gần, đứng trên trần nhà và cuối cùng nói: “Đã mua 8 cuốn”.

“Làm thế nào bạn cài đặt được cái này?” - Jack kêu lên một tiếng

*) Trong công thức này, bài toán thực tế đã được đưa ra trong kỳ thi ứng dụng môn toán tại Khoa Vật lý của Đại học Quốc gia Moscow (1968).

và ông Watson, người đã có mặt.

"Ồ, khá đơn giản! - Sherlock Holmes trả lời, ngồi xuống ghế. - Nhìn dòng chữ "họ mua nhiều hơn 6 cuốn so với album", tôi nhận ra ngay rằng họ đã mua ít nhất 7 cuốn. Từ thực tế là "giá một cuốn sách cao hơn giá một cuốn album hơn 1 rúp", tôi kết luận rằng mỗi cuốn sách có giá hơn 1 rúp và vì chúng được trả 10 rúp. 56 kopecks, không quá 10 cuốn được mua. Như vậy, tất cả các số đều lớn hơn hơn 10 và tất cả các số nhỏ hơn 7 đều không còn nghi ngờ gì nữa. Sau khi kiểm tra từng số 7, 8, 9, 10, tôi thấy rằng số tôi đang tìm chỉ có thể là 8: các số còn lại không chia hết cho 1056.”

Phương pháp vũ phu mà Sherlock Holmes sử dụng ở đây rõ ràng là phương pháp lâu đời nhất trong số các phương pháp lời giải bài toán. Trong một thời gian dài nó được xếp vào loại phương pháp “hạng hai”; “quá mức cần thiết” lời giải được coi là xấu xí. Tuy nhiên, trong những năm gần đây, phương pháp Brute Force ngày càng được sử dụng thường xuyên hơn trong các bài toán mà giá trị mong muốn chỉ nhận giá trị nguyên.

⟦folio 37⟧

Việc tìm kiếm được thực hiện bởi máy tính

Có rất nhiều vấn đề bài toán nghiêm trọng mà các nhà toán học không thể giải quyết bằng cách dùng vũ lực. Đúng, trong trường hợp này việc tìm kiếm sẽ được thực hiện bởi một máy tính điện tử và nhà toán học sẽ chỉ hướng dẫn nó cách thực hiện việc tìm kiếm này. Nhà toán học nổi tiếng người Mỹ S. Golomb viết về điều này*): "Không giống như một người, một cỗ máy, giải bài toán, sẽ thực hiện các phép tính đơn điệu, có vẻ rất nhàm chán đối với chúng ta, với tốc độ không thể tưởng tượng được. Nhưng đồng thời, cô ấy sẽ không nhận thấy cách tính toán hoặc cải thiện lời giải, nếu phương pháp này không được lập trình viên đưa ra hướng dẫn chi tiết cho hoạt động của máy tính tính đến trước."

Tuy nhiên, trong những năm gần đây, tốc độ và dung lượng bộ nhớ của máy tính ngày càng tăng, tính khả dụng cao hơn và chi phí thấp khiến chúng ngày càng được sử dụng nhiều hơn để tìm kiếm lời giải bài toán. Do đó, câu hỏi nổi tiếng “bài toán về bốn màu” (Có thể vẽ bản đồ địa lý bằng bốn màu để các quốc gia cùng màu không có các phần biên giới chung không?) đã được giải quyết - bằng một tìm kiếm rất xảo quyệt - chỉ với sự trợ giúp của máy tính. Gần đây, một trong những bài toán nổi tiếng nhất về đa thức trong cuốn sách của S. Golomb cũng đã được giải bằng phương pháp vũ phu sử dụng máy tính.

Ba lô đóng gói du lịch

Trong số bài toán được giải quyết bằng phương pháp vũ lực có cái gọi là “bài toán khi đóng gói ba lô”: Đặt các đồ vật từ một bộ nhất định vào ba lô sao cho tổng khối lượng của chúng lớn nhất (và tổng khối lượng không vượt quá thể tích của ba lô).

Trong bối cảnh này, bài toán trông giống như một món đồ chơi, nhưng hãy thay thế “riokzak” bằng “rebound in the triome of the Tellhod” và bạn sẽ thấy rằng bài toán này có ý nghĩa dân gian quan trọng.

Ở Urazhda, đối với 5 thành phố, số lượng lựa chọn là 24, đối với 6 thành phố là 120, đối với bảy - 720, đối với mười - 362880. Để tránh tìm kiếm đầy đủ, các nhà toán học đã nghĩ ra nhiều thủ thuật khác nhau**. Việc này không được thực hiện một cách vô ích - lời giải như bài toán là cần thiết để tìm ra con đường tốt nhất cho một chiếc xe tải chở tạp chí và báo đến các ki-ốt, xe buýt, một

*) S. V. Golomb. “Polimino” (M., “Mir”, 1975).

Người bán hàng lưu động lên đường

Một vấn đề nổi tiếng khác được giải quyết bằng cách liệt kê các tùy chọn là “bài toán nhân viên bán hàng du lịch”*): Làm thế nào để nén một số thành phố, giữa hai thành phố đó có một kết nối đường sắt, dành ít thời gian nhất có thể, với thành phố mà con đường bắt đầu và kết thúc?

*) Nhân viên bán hàng lưu động là đại diện lưu động của một công ty thương mại.
*) Xem, ví dụ, «Kvant», 1978, số 6, tr. 11.

⟦folio 38⟧

tuyển dụng dân làng làm việc, v.v.

Bài tập 2. Trong hình vẽ bản đồ khu vực có 5 thành phố: Axe, Ox, Ekh, Ukh và their, đồng thời bảng hiển thị khoảng cách giữa chúng bằng đường sắt. Tìm con đường ngắn nhất cho một nhân viên bán hàng du lịch phải rời thành phố Ukh, đi vòng quanh các thành phố khác và trở về Ukh.

| | Ax | Của họ | Ox | Ồ | Ơ |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Ax | 0 | 60 | 40 | 50 | 20 |
| Của họ | 60 | 0 | 30 | 35 | 45 |
| Ox | 40 | 30 | 0 | 55 | 50 |
| Ồ | 50 | 35 | 55 | 0 | 20 |
| Ơ | 20 | 45 | 50 | 20 | 0 |

Hãy giảm tìm kiếm

Đối với lời giải tương tự như bài toán, các phương pháp phức tạp đã được tạo để giảm bớt việc tìm kiếm các tùy chọn. Chúng tạo thành một môn khoa học toán học mới gọi là “lập trình số nguyên”.

Một số ý tưởng về khả năng giảm tìm kiếm có thể được giải quyết như thế này bài toán:

Được biết, $\sqrt[3]{****3}$ là một số tự nhiên. Tìm anh ấy.

Điều đầu tiên bạn nghĩ đến là sắp xếp các số có năm chữ số kết thúc bằng 3 và xem liệu có chính xác số lập phương nào trong số đó không: 10003, 10013, 10023,... Nhưng khi nào chúng ta sẽ có được 99993, và làm sao chúng ta biết một số đã cho có phải là số lập phương hay không?

Tốt hơn hết là lập phương số và xem số nào trong số chúng sẽ có năm chữ số và kết thúc bằng 3. Chúng ta nhận được $1^3=1$, $2^3=8$, $3^3=27$, $4^3=64$, $5^3=125$, $6^3=216$, $7^3=343$, $8^3=512$, $9^3=729$, $10^3=1000$.

Điều đó cũng không có tác dụng. Tại sao chúng ta cần khối số nhỏ? Cùng xem số nhỏ nhất $x$ bằng bao nhiêu, lập phương của nó là một số có năm chữ số. Nó không nhỏ hơn $\sqrt[3]{10000}=10\sqrt[3]{10}$, nhưng $\sqrt[3]{10}$ lớn hơn 2, vì $2^3=8$; do đó $x$ lớn hơn 20. Hãy ước tính số ở trên, tức là hãy xem nó không thể vượt quá số nào. Con số này, rất rõ ràng, bằng $\sqrt[3]{10000}=10\sqrt[3]{100}$. Nhưng $\sqrt[3]{100}$ nhỏ hơn 5, vì $5^3=125$. Điều này có nghĩa là bạn cần sắp xếp các số từ 21 đến 49.

Hãy xem liệu số dưới căn tận cùng bằng 3 có giúp chúng ta rút ngắn quá trình tìm kiếm hay không. Hãy cùng nghiên cứu lập phương của 10 số tự nhiên đầu tiên mà chúng ta đã viết ra. Trong số này, chỉ có 7 số tận cùng là 3. Bây giờ nếu bạn suy nghĩ một chút, không khó để nói rằng lập phương của một số tự nhiên sẽ có tận cùng là 3 khi và chỉ nếu nó có tận cùng là 7.

Bây giờ chúng ta chỉ còn ba số để sắp xếp: 27, 37 và 47. $27^3=19683$, $37^3=50653$, $47^3=103823$, nhưng số cuối cùng đã có sáu chữ số nên chỉ còn lại các số 27 và 37.

Bài tập 3.

30 sinh viên (từ viện sư phạm) từ tất cả các khóa thứ năm đã tham gia tổng hợp 40 bài toán (dành cho học sinh). Bất kỳ hai bạn cùng lớp nào đều đưa ra cùng một số bài toán. Bất kỳ sinh viên nào của các khóa học khác nhau đều đưa ra những con số khác nhau bài toán. Có bao nhiêu học sinh nghĩ ra được một bài toán?

4. Số $9^n+1$ có thể kết thúc bằng bao nhiêu số 0?

5. Tiệc tự chọn bán ippiki với giá 5 kopecks, bánh nướng nhỏ với giá 6 kopecks, bánh nướng nhỏ với giá 7 kopecks, bánh ngọt với giá 8 kopecks và vỏ bánh với giá 10 kopecks. Một nhóm người mua 14 loại sản phẩm khác nhau bằng đồng rúp. Nếu lấy một đại diện của mỗi loài đã mua thì tổng giá của chúng sẽ bằng 21 kopecks. Bao nhiêu và những sản phẩm nào đã được mua, nếu biết thêm rằng không có quá sáu sản phẩm được mua và không có sản phẩm nào được mua bằng nhau?

6. Tìm hai số nguyên dương có hiệu bình phương là 455.

7. Trong suốt 5 năm học, học sinh đã thi 31 bài. Trong mỗi năm tiếp theo, anh ấy đã vượt qua nhiều kỳ thi hơn năm trước. Năm thứ năm có nhiều bài kiểm tra ở năm thứ hai hơn năm thứ nhất. Có bao nhiêu kỳ thi vào năm thứ tư?
