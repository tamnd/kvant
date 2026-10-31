---
id: 1989-1-lvovskiy-toom-mozhno-i-nelzya-79c8a982
issue: kvant_1989_1
year: 1989
number: "1"
title: Có thể và không thể
authors:
  - Львовский С. М.
  - Тоом А. Л.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 54
page_last: 57
page_labels: 52-55
tag: ZKEY
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 950f7d4b6dbebfab2ef01e27c87a189d0b94513b266c6450a10888341e38cb06
prompt_sha256: draft-1
translated_from: content/ru/1989/01/articles/15_lvovskiy-toom-mozhno-i-nelzya-79c8a982.md
source_content_sha256: 9f503fe106f5e77a16a334c4ce3c86d3ca696edd4d9567a5cfaaba62fb0b0558
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 52⟧

Có thể và không thể

Ứng viên Khoa học Vật lý và Toán học
S. M. LVOVSKY,
Ứng viên Khoa học Vật lý và Toán học
A. L. TOOM

Các công thức của trường học bài toán thường bắt đầu bằng những từ như “tính toán” hoặc “tìm”. Tuy nhiên, trong toán học thường có bài toán, trong đó không bắt buộc phải tính toán một cái gì đó mà để tìm hiểu xem một vật thể có một thuộc tính nhất định có tồn tại hay không. Công thức của bài toán như vậy thường bắt đầu bằng các từ “có thể không…” hoặc “có tồn tại không…”. Đáp số Tất nhiên, những câu hỏi như vậy phải có căn cứ. Nếu chúng ta khẳng định rằng điều gì đó có thể thực hiện được thì chỉ cần chỉ ra một cách cụ thể để thực hiện điều đó là đủ. Nếu chúng ta khẳng định rằng điều gì đó không thể làm được thì những tấm gương không còn đủ nữa; chúng ta phải đưa ra một bằng chứng. Không có công thức chung cho loại bằng chứng này; trong bài viết này chúng tôi sẽ chỉ cho bạn một số ví dụ có thể được sử dụng.

Đây là ví dụ đầu tiên về chủ đề “nên và không nên”.

Bài 1. Với số tự nhiên n nào có một đường thẳng đứt đoạn gồm n liên kết cắt mỗi liên kết của nó một lần? Tất cả các giao điểm phải được tìm thấy bên trong các liên kết chứ không phải ở các đỉnh; không có ba liên kết nào giao nhau tại cùng một điểm.

Lời giải. Trước hết, chúng ta lưu ý rằng đối với một số n đường đứt nét như vậy không tồn tại: ví dụ, với n=1, n=2, n=3, n=4. Mặt khác, với một số n có thể tìm thấy một đường đứt đoạn như vậy; ví dụ: hình 1 hiển thị đường đứt nét bắt buộc cho n=6. Chúng ta hãy chú ý đến các đặc tính sau của đường đứt đoạn này: các liên kết của nó tạo thành ba cặp và các liên kết của mỗi cặp giao nhau với nhau và với các liên kết khác

⟦folio 53⟧

không giao nhau (tại hình 1 mỗi cặp liên kết được vẽ bằng một màu khác nhau). Thuộc tính này tuân theo điều kiện bài toán: nếu một đường gãy nào đó cắt mỗi liên kết của nó một lần thì mỗi liên kết sẽ tạo thành một cặp với liên kết cắt nó. Nhưng để các liên kết có thể chia thành từng cặp thì số lượng của chúng phải là số chẵn. Vì vậy, chúng tôi đã chứng minh rằng đối với $n$ lẻ, đường đứt nét yêu cầu không tồn tại. Hóa ra là đối với cả bốn đều tồn tại những đường đứt đoạn. Hãy nghĩ ra một cách chung để xây dựng một đường đứt đoạn như vậy cho thứ Năm hàng tuần $n \geq 6$. hình 2 sẽ giúp bạn điều này.

Bài toán 2. Có số tự nhiên nào khi nhân với 2 sẽ thành số chính phương, khi nhân với 4 sẽ trở thành lũy thừa 4 của một số nguyên?

Lời giải. Giả sử rằng một số $m$ như vậy tồn tại và phân tích nó thành thừa số nguyên tố. Trên thực tế, trong số các thừa số nguyên tố, chúng ta chỉ quan tâm đến số hai; vì vậy chúng tôi sẽ viết:

$$m = 2^k \cdot p,$$

trong đó $p$ là số lẻ. Theo điều kiện đầu tiên, số

$$2m = 2^{k+1} \cdot p$$

bình phương của một số nguyên, trong đó $k+1$ là số chẵn và sau đó $k$ là số lẻ. Theo điều kiện thứ hai, số

$$4m = 2^{k+2} \cdot p$$

lũy thừa thứ tư của một số nguyên, trong đó $k+2$ chia hết cho 4. Nhưng nếu $k$ là số lẻ thì $k+2$ là số lẻ và khi đó không thể chia hết cho 4. Kết quả mâu thuẫn cho thấy rằng một số ngoại lệ không tồn tại.

Hình 1.

Bài toán 3. Có thể đặt tối đa bao nhiêu điểm trong một hình vuông có cạnh 1 sao cho tất cả khoảng cách giữa các điểm này ít nhất là 0,5? (“Trong hình vuông” có nghĩa là “bên trong hoặc trên viền của hình vuông”).

bài toán này cũng nằm trong loạt bài bài toán “có thể hay không”. lời giải của nó phải bao gồm hai phần: bằng chứng cho thấy có thể sắp xếp rất nhiều điểm theo cách yêu cầu và không thể sắp xếp nhiều điểm hơn nữa. Không khó để hiểu cách sắp xếp điểm thứ chín theo đúng yêu cầu; đặt một điểm ở giữa hình vuông, bốn điểm - ở các đỉnh và bốn điểm nữa - ở giữa cạnh (hình 3, a). Giả định nảy sinh là không thể định vị được hơn chín điểm theo cách yêu cầu. Điều này được chứng minh như thế nào? Ví dụ, cách chứng minh này có vẻ rất hấp dẫn: xét khoảng cách trên của chín điểm (tại tâm, các đỉnh và trung điểm của cạnh) rồi thiết lập rằng một điểm khác được thêm vào chín điểm này sẽ cách ít nhất một trong chín điểm đầu tiên một khoảng cách nhỏ hơn 0,5. Tuyên bố này hoàn toàn chính xác (ví dụ: vì các vòng tròn có bán kính 0,5 với tâm ở điểm đầu tiên.chín điểm bao phủ toàn bộ hình vuông - hình 3, b), nhưng thật không may, nó không cho lời giải bài toán của chúng tôi. Trên thực tế, đâu có niềm tin rằng cách duy nhất để sắp xếp chín điểm cần thiết là hình 3 hả? Điều gì sẽ xảy ra nếu chín điểm có thể được sắp xếp theo cách khác, đến mức có thể cộng thêm mười điểm nữa vào chúng?

⟦folio 54⟧

Hình 3.

Để chứng minh rằng không thể đặt nhiều hơn chín điểm trong một hình vuông theo cách thức yêu cầu, hãy sử dụng kỹ thuật này. Chia hình vuông của chúng ta thành 9 ô vuông bằng nhau với trạng thái 1/3 (hình 4). Nếu có nhiều hơn chín điểm trong một hình vuông lớn thì ít nhất hai trong số chúng sẽ rơi vào cùng một hình vuông nhỏ. Khoảng cách giữa hai điểm bất kỳ của hình vuông rõ ràng không vượt quá độ dài đường chéo của hình vuông này. Nhưng đường chéo của hình vuông tính từ cạnh 1/3 là $\sqrt{2/3} \leq 0.5$. Điều này có nghĩa là không thể sắp xếp nhiều hơn chín điểm theo cách yêu cầu và đáp số đến bài toán 2 là chín điểm.

Phép cân nhắc mà chúng tôi đã sử dụng trong lời giải bài toán 2: “nếu có hơn 9 điểm được phân bố trên 9 ô vuông, thì ít nhất hai trong số các điểm này sẽ rơi vào một ô vuông” thường được gọi là “nguyên lý Dirichlet” để vinh danh nhà toán học thay thế người Đức P. G. Dirichlet (1805–1859).

Trong nhiệm vụ 2 và 3, tôi chứng minh phát biểu về sự tồn tại bằng cách xây dựng một ví dụ cụ thể. Trong bài toán 4 sẽ hành động khác đi.

Bài toán 4. Dãy số được xây dựng như sau. Số đầu tiên trong đó là hai. Mỗi số tiếp theo bằng tổng mười lũy thừa của các chữ số của số trước đó. Chứng minh rằng có hai số giống nhau trong dãy này.

Hãy xem chúng ta nhận được loại số nào trong dãy số này. Số thứ hai là $2^{10}=1024$. Số thứ ba là $1^{10}+2^{10}+4^{10}=1+1024+1024^2=1049601$.

Số thứ tư đã lớn đến mức có thể thấy rõ: “bằng tay” chúng ta sẽ không tìm được hai số giống nhau. Hơn nữa, người ta nảy sinh nghi ngờ liệu có đúng là chúng ta dễ chứng minh hay không? Thoạt nhìn, con số này đang tăng lên nhanh chóng và không thể lặp lại. Tuy nhiên, chúng ta đừng vội kết luận; Thay vì tính toán chính xác các con số của chúng ta, hãy xem có bao nhiêu chữ số trong ký hiệu của chúng.

Số thứ tư là $1^{10}+4^{10}+9^{10}+6^{10}+1^{10}$, nhỏ hơn $10^{10}+10^{10}+10^{10}+10^{10}=5 \cdot 10^{10}$. Tuy nhiên, $5 \cdot 10^{10}$ là một số được số hóa như nhau (là số năm theo sau là mười số không); Điều này có nghĩa là số thứ tư không có nhiều hơn các chữ số giống nhau. Số thứ năm là tổng mười lũy thừa của các chữ số của số thứ tư. Mỗi lũy thừa trong mười lũy thừa này nhỏ hơn $10^{10}$, tổng số chữ số không quá 11, nghĩa là số thứ năm nhỏ hơn số có mười hai chữ số $11 \cdot 10^{10}$. Nó sẽ trở thành năm, số thứ năm có không quá 12 chữ số. Lập luận tương tự, chúng ta thấy rằng số thứ sáu nhỏ hơn $12 \cdot 10^{10}$ và lại không có quá 12 chữ số. Do đó, bằng cách sử dụng lý luận tương tự, chúng tôi thấy rằng bản ghi của số thứ bảy, thứ tám và nói chung là tất cả các số tiếp theo trong dãy của chúng tôi chứa không quá 12 chữ số. Vì những số có không quá 12 chữ số là số hữu hạn nên chúng ta sẽ không thể tìm được những số khác với những số trước đó và một ngày nào đó chúng ta sẽ gặp hai số giống hệt nhau.

Tóm lại, chúng tôi cung cấp cho bạn bài toán đối với độc lập lời giải (bài toán 1-12 tạo thành một nhiệm vụ cho

⟦folio 55⟧

học sinh lớp bảy muốn vào Thang Toán Tương ứng Toàn Liên minh - xem câu chuyện về ngôi trường này trên trang. 65).

Zadcic

1. Có ba giải pháp. Dung dịch thứ nhất chứa 2% chất A và 3% chất B. Dung dịch thứ hai chứa 5% chất A và 7% chất B. Dung dịch thứ ba chứa 11% chất A và 12,5% chất B.

Có thể trộn các dung dịch này theo tỷ lệ sao cho hỗn hợp thu được chứa 7,5% chất A và 7% chất B?

2. Các số 1, 2, 3, 4, 5, 6, 7, 8, 9 được viết thành một hàng. Có thể loại bỏ dấu ngoặc và ký hiệu của các phép toán để thu được biểu thức bằng 0 không?

3. Người tiên phong Seryozha đã đưa ra phép kiểm tra sau đây về khả năng chia hết cho 27: nếu tổng các chữ số của một số chia hết cho 27 thì chính số đó chia hết cho 27. Phép thử này có đúng không?

4. Có thể cắt một hình vuông thành 1989 hình vuông (không nhất thiết phải bằng nhau) không?

5. Số 1989 được lập phương và 3 được thêm vào kết quả; số kết quả lại được lập phương và 3 được thêm vào kết quả; số kết quả lại được lập phương, 3 lại được thêm vào kết quả, v.v. Kết quả là một chuỗi các số, mỗi số lớn hơn lập phương của số trước đó 3 đơn vị. Nó có thể chứa một số kết thúc bằng 8 không?

6. Có số tự nhiên nào khi nhân với 2 sẽ thành hình vuông, nhân với 3 sẽ thành lập phương, khi nhân với 5 sẽ thành lũy thừa năm và khi nhân với 7 sẽ thành lũy thừa bảy của một số nguyên?

7. Có số nào có nhiều chữ số mà tổng các chữ số chia hết cho 13 và tổng các chữ số của số lớn hơn một cũng chia hết cho 13? Nếu không, hãy chứng minh điều đó; nếu có, hãy liệt kê tất cả những con số đó.

8. Số nguyên tố là số tự nhiên lớn hơn 2 và không có ước số nào khác ngoài chính nó và 1. Cần phải đặt một số nguyên tố vào mỗi ô của bảng vuông 4x4 sao cho ở mỗi hàng, mỗi cột tích các số bằng 1989. Làm được điều này có được không?

9. Có thể hòa tan các số trong các ô của một bảng hình chữ nhật sao cho tích các số ở mỗi hàng bằng hai và tích các số ở mỗi cột bằng ba?

10. Có thể sắp xếp năm số nguyên tố khác nhau trên một mặt phẳng sao cho mỗi số nguyên tố đó giao nhau một cách chính xác với ba số nguyên tố kia không?

11. Khoảng cách giữa điểm A và B là năm mươi km. Vào buổi trưa, ba người bạn khởi hành từ điểm A đến điểm B. Mỗi người đi với vận tốc 5 km/h. Họ có sẵn một chiếc xe đạp đường trường có thể chạy với tốc độ 10 km/h và một chiếc xe đạp đua có thể chạy với tốc độ 20 km/h. Mỗi chiếc xe đạp chỉ vừa một người; Xe đạp có thể được để trên đường mà không có người bảo vệ. Liệu cả ba có thời gian chỉ sử dụng hai chiếc xe đạp này để thêm điểm B đến sáu giờ tối không?

12. Có thể sắp xếp các điểm trên mặt phẳng 7 sao cho có thể tìm thấy ít nhất hai môi trường của ba điểm bất kỳ cách nhau 1 cm không?

13. 10 đội tham dự giải bóng đá; mỗi người chơi một trận với nhau. Theo kết quả giải đấu được công bố, đội xếp thứ 7 ghi được 11 điểm, đội xếp thứ 8 ghi được 6 điểm và đội xếp cuối ghi được 4 điểm. Điều này có thể là như vậy? (Đội thắng được 2 điểm, đội hòa - 1 điểm, đội thua - 0 điểm. Trong trường hợp số điểm bằng nhau thì số bàn thắng ghi được và số bàn thua được tính.)

14. Một dãy bốn mươi số được xây dựng như sau. Số thứ nhất bằng 0, số thứ hai bằng một. Mỗi số, ngoại trừ số thứ nhất và số thứ hai, đều bằng tổng của hai số trước đó. Liệu một thành viên bằng một triệu có thể xuất hiện theo trình tự như vậy không?

15. Phải lấy bao nhiêu hình tròn bán kính 1 để che hình vuông có cạnh 2?

16. Cần phải chuyển một số mảnh đá cẩm thạch có tổng khối lượng 14 tấn. Khối lượng chính xác của mỗi mảnh vẫn chưa được biết, nhưng khối lượng của mỗi mảnh không quá 400 kg. Phải đặt hàng bao nhiêu xe có sức chở 1500 kg để có thể tăng tải trọng này?

17. Ở đất nước Miggs, bạn có thể lái xe từ bất kỳ thành phố nào đến bất kỳ thành phố nào dọc theo một con đường. Khi các con đường đi qua 4 thành phố của mỗi thành phố thì mỗi con đường có 2 con đường đi qua 3 thành phố và mỗi con đường còn lại có 2 thành phố. Cô gái Ellie cho biết tổng cộng đất nước này có 11 thành phố và 35 con đường. Chứng minh rằng cô ấy đã mắc sai lầm trong tính toán của mình.

18. Vòng tròn được chia thành n khu vực giống hệt nhau, mỗi khu vực chứa một quân cờ. Trong một lần di chuyển, bạn có thể thực hiện các thao tác sau: lấy bất kỳ quân cờ nào và sắp xếp lại chúng: một - ở khu vực liền kề theo chiều kim đồng hồ, quân còn lại - ở khu vực liền kề ngược chiều kim đồng hồ. Để làm gì thì có thể thu thập được tất cả các quân cờ trong một khu vực bằng cách sử dụng những nước đi như vậy?

19. Một hình vuông có cạnh 1 m có hình giọt nước có hai màu. Chứng minh rằng có thể tìm được ba điểm cùng màu là các đỉnh của một tam giác đều có cạnh ít nhất là 30 cm.
