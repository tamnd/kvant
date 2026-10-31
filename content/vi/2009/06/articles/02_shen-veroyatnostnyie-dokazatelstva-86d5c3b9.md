---
id: 2009-6-shen-veroyatnostnyie-dokazatelstva-86d5c3b9
issue: kvant_2009_6
year: 2009
number: "6"
title: Bằng chứng xác suất
authors:
  - Шень А. Х.
rubric: osnovnye-stati
page_first: 13
page_last: 27
page_labels: 11, 13, 14, 25
tag: NKA5
lang: vi
source: kvant_digital
extraction: native
content_sha256: bd5a58968e3347bfe450aef8c198041b1bf059ea09fc3c320a3e94765c5b7e51
prompt_sha256: draft-1
translated_from: content/ru/2009/06/articles/02_shen-veroyatnostnyie-dokazatelstva-86d5c3b9.md
source_content_sha256: d33668184ca25de70b8ab9e7ebee22c0d5c88f96a070920737013d3ea42e8e99
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 11⟧

Bằng chứng xác suất

A.SHEN

Bất đẳng thức và ước lượng Hãy bắt đầu với bài toán rất đơn giản. 1. 10 con số được viết trên bảng. Tổng của hai số bất kỳ không nhỏ hơn 5. Chứng minh rằng tổng của tất cả các số không nhỏ hơn 25. ⊳ Không cần chứng minh gì nhiều ở đây: hãy chia các số thành năm cặp. Trong mỗi cặp tổng không nhỏ hơn 5, tổng số là 25. ⊲

Bây giờ phức tạp hơn một chút bài toán. 2. 9 số được viết trên bảng. Tổng của hai số bất kỳ không nhỏ hơn 5. Chứng minh rằng tổng của tất cả các số không nhỏ hơn 22,5. (Nếu tất cả các số là 2,5 thì kết quả là 22,5.) ⊳ Sử dụng cách lập luận tương tự như bài toán trước đó, bạn có thể chọn bốn cặp và sẽ giữ lại một số. Trong mỗi cặp, tổng không nhỏ hơn 5, tổng cộng là 20. Nếu biết số còn lại không có cặp không nhỏ hơn 2,5 thì chúng ta sẽ được số cần tìm. Nhưng chúng tôi không thể đảm bảo điều này. Giả sử, nếu một trong các số bằng 0 và các số còn lại là 5, thì tổng của hai số bất kỳ sẽ ít nhất là 5 (cụ thể là 5 hoặc 10). Trong trường hợp này, số 0 có thể không được ghép đôi. Có lẽ bạn đã tìm ra cách hoàn thành lập luận. Việc phân vùng thành từng cặp nằm trong tay chúng ta và chúng ta có thể để bất kỳ số nào không ghép đôi. Trong bất kỳ cặp nào, ít nhất một trong các số là 2,5 hoặc lớn hơn. Chúng ta

⟦column⟧

trong đó tổng không nhỏ hơn 5. Tổng ít nhất là 3 ◊ 5 + ( 5 3 ) = 50 3. ⊲

Trong hai bài toán trước chỉ còn lại một số. Điều gì xảy ra nếu còn lại hai người? 4. Có 11 số được viết trên bảng. Tổng của ba số bất kỳ không nhỏ hơn 5. Chứng minh rằng tổng của tất cả các số không nhỏ hơn 55/3. Bạn có thể giải bài toán này tương tự như các câu trước (xem bài toán 14 và gợi ý cho nó). Nhưng chúng tôi sẽ đưa ra một lời giải khác, khái quát hóa cho bất kỳ số lượng nào. ⊳ Hãy biểu thị các số của chúng ta $a_{1}$, … $, a_{11}$ và viết chúng thành một vòng tròn. Tổng của ba lân cận bất kỳ không nhỏ hơn 5 (theo điều kiện):

$a_{1} + a_{2} + a_{3} \ge 5,$

$a_{2} + a_{3} + a_{4} \ge 5,$

… $a_{9} + a_{10} + a_{11} \ge 5,$

$a_{10} + a_{11} + a_{1} \ge 5, a_{11} + a_{1} + a_{2} \ge 5.$

Hãy cộng mười một bất đẳng thức này lại. Mỗi số xuất hiện ba lần (gồm ba bộ ba), vậy ra

$3 ( a_{1} + a_{2} +^{…} + a_{11} ) \ge 55$, từ đó có yêu cầu sau. ⊲

Xác suất và kỳ vọng là đủ để biết rằng ít nhất một trong các con số giống như thế này - bạn có thể để con số cụ thể này không ghép đôi và mọi thứ sẽ ổn thỏa. ⊲ Hãy phức tạp hóa bài toán thêm một chút. 3. Có 10 số được viết trên bảng. Tổng của ba số bất kỳ không nhỏ hơn 5. Chứng minh rằng tổng của tất cả các số không nhỏ hơn 50/3. ⊳ Chúng ta sử dụng kỹ thuật tương tự: trong ba số bất kỳ, số lớn hơn là 5/3 trở lên (nếu không thì cả ba số đều nhỏ hơn 5/3 và tổng nhỏ hơn 5). Hãy lấy một trong những số này (không nhỏ hơn 5/3), sẽ còn lại ba số ba,

Bây giờ chúng ta sẽ xem xét lời giải khác của bài toán cuối cùng – theo ngôn ngữ của lý thuyết xác suất. Đặt 11 quả bóng trong một hộp (hoặc, như người ta hay nói trong lý thuyết xác suất, trong một chiếc bình) với các số $a_{1}, a_{2}$, ... $, a_{11}$ được viết trên đó. Chúng tôi lấy ra một trong những quả bóng mà không cần nhìn, và họ đưa cho chúng tôi số rúp được viết trên đó. Trung bình chúng ta sẽ thắng bao nhiêu mỗi trận nếu chơi nhiều lần? Ý của chúng tôi là mỗi khi quả bóng được lấy ra, nó sẽ được đưa trở lại bình và những thứ bên trong nó được trộn lẫn. Thật dễ dàng để nhận ra rằng đáp số ở đây –

⟦folio 13⟧

XÁC ĐỊNH

đường. Với số lượng thử lớn, tỷ lệ trường hợp đỉnh A rơi vào vị trí (xác suất xảy ra sự kiện “A đen”) là 1/10, vì đỉnh A phân bố đều trên toàn bộ mặt cầu. Vì những lý do tương tự, đỉnh B có 10% màu đen và điều tương tự cũng có thể xảy ra với bất kỳ đỉnh nào trong số 8 đỉnh. Điều này có nghĩa là vẫn còn ít nhất 20% = 100% – 80% trường hợp tất cả các đỉnh đều có màu trắng (có thể nhiều hơn do trường hợp có một số đỉnh có màu đen). Do đó, khối lập phương có thể được ghi theo cách yêu cầu. ⊲ Trên thực tế, ở đây chúng ta đang nghiêm túc gian lận và che giấu phần chính của lập luận: tại sao từ “khối nội tiếp ngẫu nhiên” lại có ý nghĩa và tại sao đỉnh lại phân bố đều trên mặt cầu. Về mặt trực quan, điều này có vẻ hợp lý và thực sự có thể được biện minh một cách chặt chẽ (mặc dù tôi không biết bất kỳ lời giải nào về bài toán này trong chương trình giảng dạy ở trường).

Trang màu ngẫu nhiên

Hãy xem xét một biểu đồ tùy ý - một số điểm (đỉnh) được nối với nhau bằng các đường (cạnh). Hãy tô màu các đỉnh của đồ thị bằng hai màu (ví dụ: đen và trắng). Chúng ta sẽ gọi một cạnh là nhiều màu nếu nó (như bạn đoán) kết nối các đỉnh có màu khác nhau. Số cạnh nhiều màu phụ thuộc vào màu sắc. Nếu chúng ta muốn làm cho con số này ở mức tối thiểu thì không có gì đơn giản hơn - chỉ cần sơn tất cả các đỉnh cùng một màu. Điều gì xảy ra nếu chúng ta muốn đạt giá trị tối đa (đối với một biểu đồ nhất định)? Đáp số phụ thuộc vào biểu đồ, nhưng hóa ra bạn luôn có thể đảm bảo ít nhất một nửa số cạnh có màu khác nhau. 8. Chứng minh rằng trong một đồ thị tùy ý có thể tô các đỉnh bằng hai màu sao cho ít nhất một nửa số cạnh có màu khác nhau. ⊳ Chúng tôi sẽ tô màu các đỉnh một cách ngẫu nhiên (đối với đồ thị có n đỉnh, có thể tô màu $2^{n}$ và chúng tôi coi tất cả chúng đều có xác suất như nhau). Đối với mỗi màu, chúng ta đếm xem có bao nhiêu cạnh sẽ có nhiều màu. Như người ta nói, đây là một “biến ngẫu nhiên” - nó phụ thuộc vào việc lựa chọn màu sắc. Kỳ vọng toán học của nó (giá trị trung bình qua một số lượng lớn các thử nghiệm) là gì? Nói cách khác, hãy ném một đồng xu vào mỗi đỉnh của đồ thị (độc lập với các đỉnh khác, sao cho tất cả các kết hợp đều có khả năng xảy ra như nhau) và trên mỗi cạnh có một người chơi nhận được một đồng rúp nếu cạnh đó có màu khác nhau (đồng xu ở hai đầu của nó sẽ rơi ra khác nhau). Người chơi sẽ kiếm được trung bình bao nhiêu mỗi trận? Trung bình, mỗi người chơi thắng một nửa số trò chơi (có thể có bốn tổ hợp màu ở hai đầu của cạnh và hai trong số đó có nhiều màu). Điều này có nghĩa là trung bình mỗi người chơi thắng 50 rúp mỗi trận và toàn đội thắng trung bình V/2 rúp, trong đó V là số cạnh.

BẰNG CHỨNG

⟦column⟧

Rõ ràng là có những chất tạo màu khi ít nhất một nửa số cạnh có màu khác nhau (nếu không, đội sẽ thắng ít hơn V/2 trong mỗi trận đấu và trung bình cũng sẽ nhỏ hơn V/2). ⊲ Trên thực tế, mệnh đề này có một bằng chứng mang tính xây dựng đơn giản (xem bài toán 19).

Dự đoán ngẫu nhiên

Trong phần này, chúng ta sẽ áp dụng các cân nhắc xác suất cho lời giải chẳng hạn như bài toán. 9. Một hình lồi được vẽ trên một mặt phẳng, giới hạn bởi một đường cong có chiều dài L. Chứng minh rằng đường kính của nó, tức là khoảng cách lớn nhất giữa hai điểm của nó không nhỏ hơn $L \pi$. Sự xuất hiện của số $\pi$ ở đây không phải ngẫu nhiên: bất đẳng thức bài toán trở thành đẳng thức trong trường hợp đường tròn có đường kính $D = L \pi$. ⊳ Chúng tôi sẽ chứng minh một phát biểu mạnh mẽ hơn: độ dài trung bình của hình chiếu của hình của chúng tôi lên một hướng ngẫu nhiên là $L \pi$. (Chúng ta vẽ một đường thẳng theo hướng được chọn ngẫu nhiên, sau đó từ mỗi điểm của hình chúng ta hạ thấp một đường vuông góc với đường thẳng này. Kết quả là một đoạn - hình chiếu của hình lên đường thẳng.) Từ tuyên bố này, suy ra rằng có một hướng, hình chiếu lên đó có chiều dài ít nhất là $L \pi$ (giá trị trung bình không thể lớn hơn tất cả). Khi đó các điểm của hình rơi ở hai đầu hình chiếu có khoảng cách bằng nhau hoặc lớn hơn (điểm nghiêng dài hơn đường vuông góc). Làm thế nào để chứng minh những gì đã hứa? Xét một đường cong giới hạn một hình. Hình chiếu của một hình cũng giống như hình chiếu của đường biên của nó. Hãy chia đường cong này thành nhiều phần rất nhỏ - nhỏ đến mức mỗi phần có thể được coi là một đoạn. Hãy để tất cả các đoạn này có độ dài bằng nhau. Hình chiếu của toàn bộ ranh giới bao gồm các hình chiếu của các đoạn này. Chính xác hơn, hình chiếu kép của toàn bộ ranh giới bằng tổng các hình chiếu của các đoạn (vì chúng bao phủ nó hai lần - qua lại). Điều này đúng với bất kỳ hướng thiết kế nào - có nghĩa là chiều dài trung bình gấp đôi của hình chiếu của một hình bằng tổng chiều dài trung bình của các hình chiếu của từng đoạn tạo nên ranh giới của nó. Nhưng các đoạn này có độ dài bằng nhau và do đó độ dài trung bình của các hình chiếu của chúng là như nhau (vì chúng ta chiếu theo một hướng ngẫu nhiên nên bản thân hướng của đoạn đó không quan trọng). Điều này có nghĩa là chiều dài hình chiếu trung bình

⟦folio 14⟧

KVANT 2009/№6

đường cong chỉ phụ thuộc vào số lượng các đoạn này, tức là tỷ lệ thuận với độ dài của đường cong và hệ số tỷ lệ có thể được tính bằng ví dụ về đường tròn. ⊲

Hai hộp

10. Trong tàu điện ngầm Moscow, bạn có thể vận chuyển các hộp có tổng kích thước (chiều dài, chiều rộng và chiều cao) không vượt quá một giới hạn nhất định. Câu hỏi được đặt ra: liệu có thể phá vỡ các quy tắc bằng cách đặt hộp này vào hộp khác không? Nói cách khác, hãy để một hình khối hoàn toàn nằm trong một hình khối khác. Tổng kích thước bên trong có thể lớn hơn tổng kích thước bên ngoài không? ⊳ Hóa ra là không, nhưng việc chứng minh không dễ dàng như vậy. Có một số cách chứng minh hay và một trong số đó sử dụng các cân nhắc xác suất (tương tự như trong phần trước). Chúng ta sẽ chiếu chiếc hộp lên một đường thẳng có hướng được chọn ngẫu nhiên (trong không gian). Từ hình ảnh bạn có thể thấy hình chiếu của hộp bao gồm hình chiếu của ba đoạn chạy dọc theo chiều cao, chiều dài và chiều rộng của nó. Do đó, độ dài trung bình của hình chiếu (kỳ vọng toán học) bằng tổng độ dài trung bình của các hình chiếu của các đoạn này. Và độ dài trung bình của hình chiếu của một đoạn tỷ lệ thuận với độ dài của chính nó (với một số hệ số, bây giờ đối với chúng tôi không quan trọng - với cái gì). Do đó, chiều dài hình chiếu trung bình của hình hộp tỷ lệ thuận với tổng kích thước của nó. Bây giờ hãy tưởng tượng hai cái hộp, cái này ở trong cái kia. Dù bạn chiếu chúng lên đường thẳng nào thì hình chiếu của hộp bên trong luôn nằm bên trong hình chiếu của hộp bên ngoài và do đó có chiều dài nhỏ hơn hoặc bằng nhau. Điều này có nghĩa là độ dài trung bình của các hình chiếu có cùng tỷ lệ và chúng tỷ lệ thuận với tổng các phép đo. ⊲

Bước đi ngẫu nhiên

11. Một mê cung được vẽ trên một mảnh giấy vở hình vuông và có một robot trong đó, tuân theo các lệnh “lên”, “xuống”, “trái” và “phải”, đi từ ô này sang ô khác. Các bức tường của mê cung chạy dọc theo các cạnh của ô; không có lối ra khỏi mê cung. Nếu khi bắt đầu di chuyển theo lệnh, robot va vào tường thì nó vẫn giữ nguyên vị trí. Chúng ta không biết mê cung nào được vẽ, nhưng chúng ta biết kích thước của chiếc lá, được đo bằng hình vuông. Chứng minh rằng có thể tạo một chuỗi lệnh đảm bảo rằng robot sẽ truy cập vào tất cả các ô của phần mê cung mà nó có thể truy cập được. ⊳ Chúng ta thừa nhận ngay rằng lý luận của chúng ta không chỉ là một bằng chứng thuần túy về sự tồn tại (không đưa ra phương pháp xây dựng một chuỗi như vậy), mà độ dài của một chuỗi như vậy cũng sẽ rất lớn. Chúng tôi sẽ đưa ra các lệnh ngẫu nhiên cho robot và xem

⟦column⟧

với xác suất nào anh ta sẽ đi vòng qua mê cung? Cho mê cung có một mạch kín không quá N bước. Khi đó, đối với bất kỳ vị trí ban đầu nào của robot, có một xác suất nào đó là khi N lệnh ngẫu nhiên được đưa ra cho nó, nó sẽ đi theo chính xác con đường này và đi vòng quanh mê cung. Nó không nhỏ hơn $4^{-} N$ và xác suất

(

) không thể đi vòng quanh mê cung nhiều hơn $1 - 4^{-} N$. Quá trình có thể được lặp lại: nếu chúng ta đưa ra 2N lệnh ngẫu nhiên thì xác suất không thể vượt qua mê cung sẽ không còn nữa

$( 1 - 4 )$ (thất bại ở giai đoạn đầu tiên xảy ra ở một phần nhỏ trong số $( 1 - 4 )$ trường hợp trở xuống và trong mỗi trường hợp đó

$- N^{2}$

$- N$ xác suất giảm đi một lượng tương tự do ở giai đoạn thứ hai). Nói chung, sau Nk lệnh ngẫu nhiên, xác suất thất bại (trong một mê cung nhất định với giá trị ban đầu cho trước

(

) k vị trí) không quá $1 - 4^{-} N$. Mặc dù cơ số của bậc gần bằng 1 nhưng con số này vẫn có thể nhỏ đi như mong muốn bằng cách tăng k. Lưu ý rằng đối với tất cả các mê cung trên một bảng có kích thước nhất định, có thể chọn một N chung.

(

) k

Sau đó, chúng ta lấy k sao cho $1 - 4^{-} N$ trở thành nhỏ hơn 1/M, trong đó M là số cách khác nhau để vẽ một mê cung và một robot bên trong nó (có một số hữu hạn các cách vẽ trên một tờ giấy có kích thước nhất định). Sau đó, đối với mỗi tùy chọn bố trí M, xác suất thất bại nhỏ hơn 1/M và do đó, với xác suất dương, một chuỗi lệnh có độ dài Nk sẽ thành công cho tất cả các tùy chọn. Điều này có nghĩa là tồn tại một chuỗi thành công như vậy và đó là điều cần được chứng minh. ⊲

Bộ không thể so sánh được

Trong phần này chúng ta giả định rằng chúng ta đã quen thuộc với các phần tử của tổ hợp (tập hợp, tập hợp con, số lượng tổ hợp). 12. Cho A là tập hợp gồm 2n phần tử. Chúng tôi muốn chọn một số tập hợp con của tập A và chúng tôi yêu cầu chúng không thể so sánh được: không tập nào trong số chúng phải là tập con của tập kia. Số lượng tập hợp con tối đa có thể được chọn là bao nhiêu? ⊳ Lưu ý rằng yêu cầu được thỏa mãn nếu tất cả các tập con được chọn có cùng kích thước (và khác nhau). Để số lượng của chúng là tối đa, cần phải lấy kích thước n, vì số lượng kết hợp $C_{2} kn$ cho một n nhất định

⟦folio 25⟧

THÔNG TIN

phân tích logic, so sánh kết quả phản ánh với sự thật hoặc với những điều tương tự từ các khái niệm khác. Tư duy độc lập không chỉ là sự hiểu biết về bản chất và nền tảng của một lý thuyết cũng như phạm vi áp dụng của nó, khả năng rút ra hệ quả trong khuôn khổ của nó đối với các trường hợp cụ thể, v.v. Cũng cần phải hiểu rằng mọi lý thuyết đều có những lựa chọn thay thế, thừa nhận những lựa chọn thay thế này, sẵn sàng từ bỏ bất cứ lúc nào những khái niệm quen thuộc nếu những sự kiện mới phù hợp với khuôn khổ của chúng một cách “khó khăn” (đặc biệt là khi chúng vượt ra ngoài những khuôn khổ này). Tất nhiên, có những khái niệm mà giá trị của nó khó có thể nghi ngờ. Ví dụ, thực tế xung quanh chúng ta với tất cả các quá trình diễn ra trong đó thường chứng tỏ tính bất khả xâm phạm và tính phổ quát của ba tính chất sau: tính kinh tế, tính đối xứng và tính tương đối (hai tính chất sau, ở một mức độ nào đó, là trường hợp đặc biệt của tính chất đầu tiên). Danh sách này có thể chưa đầy đủ và cần được bổ sung (điều này rất có thể sẽ xảy ra trong tương lai). Nhưng dù vậy, có thể liệt kê một số điều khoản không thể đưa vào danh sách các khái niệm phổ quát này, mặc dù thực tế là chúng được coi là cơ bản. Ví dụ, không thể thừa nhận rằng một electron trên trái đất và một electron ở cách nó hàng tỷ năm ánh sáng có khối lượng nghỉ hoàn toàn giống nhau. Thật khó để coi những đại lượng không thứ nguyên như hằng số cấu trúc nguyên tử mịn, tỷ lệ khối lượng của các hạt cơ bản, v.v., là hằng số vật lý không thể lay chuyển. Có thể nói, Einstein cũng nghi ngờ về bản chất ngẫu nhiên của chúng. Hoặc đây là những hằng số toán học (nghĩa là chúng được rút ra trong khuôn khổ của một số lý thuyết mà chúng ta chưa biết) hoặc chúng không phải là hằng số (nghĩa là chúng thay đổi theo thời gian và (hoặc) trong không gian). Tính ba chiều của không gian xung quanh chúng ta cũng là một trong những tiên đề của lý thuyết hiện đại, nhưng cho đến nay vẫn chưa có lý do gì để coi nó là không thể lay chuyển. Chúng ta hãy kết thúc những ví dụ này bằng tuyên bố sau: khả năng xảy ra một điều gì đó là không thể bác bỏ được! Nói cách khác, không thể chứng minh được điều gì đó là không thể trong thực tế. Đây là một trong những thuộc tính của vô cực, thể hiện sự hạn chế của logic. Khi công bố cuộc thi của mình, chúng tôi cố tình không chỉ định nhiệm vụ cho những người tham gia. Nội dung của đáp số được biết là phụ thuộc vào chất lượng của câu hỏi. Như người ta nói, một câu hỏi hay là một nửa đáp số. Vì vậy, việc hình thành vấn đề cũng sẽ được đánh giá. Hơn nữa, lời giải có ​​thể không phải là thành công nhất hoặc thậm chí không chính xác, nhưng điều này được bù đắp bằng chất lượng và mức độ phù hợp của câu hỏi. Hãy nhớ rằng các câu hỏi, tín hiệu đến từ thế giới xung quanh (sự kiện, hiện tượng, v.v.) là nguyên tắc cơ bản, nguyên liệu thô vẫn phải được xử lý trong quá trình nghiên cứu, được biến thành bài toán. Và sau đó, cần phải phân tích bài toán đã nêu rõ ràng, xác định phạm vi của hiện tượng được mô tả, phạm vi thay đổi và độ chính xác của việc thiết lập các thông số mà lời giải sẽ đúng, v.v. Chúng tôi không giới hạn cụ thể người tham gia cuộc thi trong việc lựa chọn và xây dựng câu hỏi. Hãy để nó là bất cứ điều gì, miễn là nó có ý nghĩa nào đó. Có rất nhiều vấn đề trong khoa học hiện đại và phát triển công nghệ. Đặc biệt, đó là những phân kỳ đã biết trong lý thuyết lượng tử, định nghĩa đúng về tenxơ năng lượng-động lượng trong thuyết tương đối rộng, nghịch lý trong lý thuyết tập hợp, các chương trình máy tính tự phát triển (bao gồm cả ngẫu nhiên).

⟦column⟧

bầu cử, có tính đến kinh nghiệm mắc sai lầm, v.v.). Và trong cuộc sống hàng ngày, có rất nhiều điều bạn có thể cố gắng hình thức hóa bằng ngôn ngữ toán học (ví dụ, khi phát hiện ra một điểm tương đồng nào đó, hãy thử áp dụng các định luật động lực học chất khí để ... phân tích chuyển động của ô tô trên đường cao tốc). Bạn có thể đặt bài toán từ chuỗi “điều gì sẽ xảy ra nếu…” Hoặc nghĩ ra một kiểu tương tác mới. Hoặc tìm hiểu thực tế sẽ như thế nào nếu chẳng hạn như hằng số Planck hóa ra lớn hơn (hoặc nhỏ hơn) đáng kể so với hằng số chúng ta biết. Nó không phải là giả thuyết bài toán, trong đó bất kỳ hằng số thế giới nào cũng có thể được coi là không cố định. Ví dụ, sự dịch chuyển đỏ có thể được giải thích không chỉ bởi sự rút lui của các thiên hà, mà còn bởi thực tế là khối lượng electron hay hằng số Planck thay đổi theo thời gian. Vì vậy, chúng tôi không mong đợi những khám phá từ bạn. Chúng tôi không đặc biệt quan tâm đến sự uyên bác của bạn nên đừng sợ bị coi là dốt nát. Rất có thể, những gì chúng tôi mong đợi ở bạn (và những gì bạn gửi cho chúng tôi) sẽ không được bất kỳ tạp chí khoa học nghiêm túc nào chấp nhận. Có lẽ, các nhà khoa học nghiêm túc rất có thể sẽ ném “sự sáng tạo” như vậy vào thùng rác, giống như một nhà điều tra loại bỏ những phiên bản không tự biện minh cho mình. Nhưng ai biết được, biết đâu một ngày nào đó trong số những buổi “tập luyện” như vậy sẽ có điều gì đó mà trước đây đã bỏ lỡ. Ví dụ, ai đó khi lục lọi chiếc giỏ chung này sẽ bắt gặp những ý tưởng khác thường sẽ đóng vai trò là động lực cho những khám phá mới. Nhưng ngay cả khi mọi thứ không như ý muốn, chúng tôi hy vọng đạt được mục tiêu chính của mình: giúp những người có khả năng tư duy độc lập và tìm kiếm không chuẩn mực nhận ra chính mình. Đây là cách sự đổi mới được sinh ra. Hãy nghi ngờ điều đó! Bác bỏ! Lời đề nghị!

Điều kiện của cuộc thi

Mỗi người tham gia nộp dự án của mình cho ban giám khảo để xem xét, bao gồm công thức bài toán và lời giải của nó. (Trong một số trường hợp, ban giám khảo sẵn sàng xem xét bài toán với những giải pháp chưa hoàn thành.) Tổng khối lượng của báo cáo dự án không quá 10 trang đánh máy và mọi tính toán rườm rà phải được đưa vào phần phụ lục là một phần không thể thiếu của báo cáo. Bản in của báo cáo (1 bản) phải được gửi qua đường bưu điện đến tòa soạn tạp chí «Kvant» theo địa chỉ: 119296 Moscow, Leninsky Prospekt, 64-A, và báo cáo điện tử dưới dạng file riêng biệt phải được gửi đến địa chỉ email của tòa soạn: admin@kvant.info. Trang tiêu đề của báo cáo phải chứa các thông tin sau về đối thủ cạnh tranh: họ, tên, họ viết tắt; địa chỉ bưu chính, địa chỉ email, điện thoại; dữ liệu về trình độ học vấn, trình độ khoa học (nếu có). Hạn chót nhận đơn đăng ký tham gia cuộc thi là ngày 15 tháng 4 năm 2010. Kết quả của cuộc thi sẽ được công bố vào cuối tháng 5 năm 2010. Các tác phẩm, với sự đồng ý của tác giả và đáng được ban giám khảo quan tâm, sẽ được đăng trên một trang web đặc biệt của Quỹ Tư tưởng Mới, chỉ rõ những tác phẩm đã được trao giải. Tạp chí «Kvant», bất kể kết quả tác phẩm tham gia cuộc thi như thế nào, có thể (theo thỏa thuận của tác giả) xuất bản một số tác phẩm phù hợp với hình thức và tư tưởng của tạp chí.
