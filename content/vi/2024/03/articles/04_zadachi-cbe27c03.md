---
id: 2024-3-zadachi-cbe27c03
issue: kvant_2024_3
year: 2024
number: "3"
title: Bài toán
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 37
page_last: 44
page_labels: 37, 40, 42
tag: DS90
lang: vi
source: kvant_digital
extraction: native
content_sha256: e04544f1e6cf83dcc1ec531c8ff06a8937976d2d21a43ee4fdc768a52b69d430
prompt_sha256: draft-1
translated_from: content/ru/2024/03/articles/04_zadachi-cbe27c03.md
source_content_sha256: 3b101c1355182fdecea6e522ff421766dcf93258dbfa4979604673c9269f3707
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

“SỐ LƯỢNG” CHO HỌC SINH THI

⟦column⟧

3.

Đồng hồ điện tử hiển thị thời gian từ 00:00 đến 23:59. Tàu khởi hành vào buổi sáng khi đồng hồ chỉ thời gian $^{ab}$ $:^{cd}$, và đến nơi khi đồng hồ điểm

Mỗi ô của bảng $3^{u} 3$ chứa một số tự nhiên và tất cả chín số đều khác nhau. Được biết, bạn có thể gạch bỏ từng cái một được hiển thị $время^{cd} :^{ab}$. Con tàu đã đi được bao lâu nếu biết rằng nó đã đi hơn 6 giờ nhưng ít hơn 7 giờ? N. Agakhanov viết một số ở mỗi dòng sao cho tổng của hai số còn lại bằng cùng một số x. Bạn cũng có thể gạch bỏ một số trong mỗi cột sao cho trong mỗi cột tổng của hai số còn lại sẽ bằng cùng một số y. Có thể x = y được không? A. Tereshin

2.

Một hình vuông ca rô $27 см^{u} 27$ cm (chiều dài cạnh của ô là 1 cm) được cắt thành 5 hình chữ nhật ca rô có cùng chu vi. Liệu tổng chiều dài của các vết cắt bên trong hình vuông là 82 cm? Văn hóa dân gian

Những bài toán này đã được đưa ra ở cấp thành phố của Olympic Toán học toàn Nga ở khu vực Moscow.

4.

Có 90 thẻ có số từ 1 đến 90 trên bàn. Hai người chơi trò chơi sau. Họ thay phiên nhau. Trong một lần di chuyển, bạn có thể lấy bất kỳ lá bài nào từ bàn. Trò chơi kết thúc khi còn lại hai lá bài trên bàn. Người thứ hai thắng nếu số trên các quân bài còn lại khác nhau đúng 10. Ngược lại, người thứ nhất thắng. Ai thắng khi chơi đúng? O. Podlipsky

Minh họa của D. Grishukova

1.

Bài toán

⟦folio 37⟧

TOÁN HỌC

Petya viết, những con số mà máy tính sẽ in theo chương trình của anh ấy cũng sẽ bắt đầu lặp lại định kỳ. Vì vậy, máy tính chỉ có thể in phần mở rộng thập phân của số hữu tỉ. Như bạn có thể thấy, ý định của Petino là không khả thi do kích thước hạn chế của một chiếc máy tính thực sự. Nếu số lượng ô nhớ của máy tính là không giới hạn thì việc viết chương trình tính căn bậc hai sẽ không khó.

Bài tập 10. Bạn có thể xây dựng một máy tự động với không quá 100 trạng thái có thể in được chuỗi số nào?

Tuy nhiên, có một số bài toán mà ngay cả một máy tính có kích thước vô hạn cũng không thể xử lý được. bài toán như vậy được gọi là không thể giải quyết được về mặt thuật toán. Có thể bạn đã từng giải các phương trình số nguyên và biết việc tìm lời giải khó đến mức nào. Điều này không phải ngẫu nhiên - như định lý đáng chú ý của Matiyasevich cho thấy (xem «Kvant» số 5 năm 1975), bài toán lời giải của các phương trình như vậy là không thể giải được về mặt thuật toán. Tuy nhiên, ngay cả khi không dùng đến các dịch vụ của máy tính, có thể chứng minh rằng ngay cả một thiết bị tự động có khả năng thực thi các chương trình có độ phức tạp và độ dài bất kỳ vẫn không thể giải được nhiều công thức rất đơn giản bài toán. Ý tưởng về tính tuần hoàn sẽ lại giúp chúng ta điều này. Chúng ta hãy nhìn vào một cỗ máy có vẻ ngoài rất đơn giản - Draftsman. Anh ta có thể di chuyển dọc theo một tờ giấy ca rô, tô màu các ô. Chúng ta sẽ mô tả hướng chuyển động của Người soạn thảo bằng một mũi tên. Đối với Người soạn thảo, chỉ được phép thực hiện ba hành động: 1. “SƠN” – sơn lên ô. 2. “TRÁI” – xoay 90 độ sang trái xung quanh đầu mũi tên. 3. “JUMP” – nhảy đến giữa ô liền kề theo hướng mũi tên. Ngoài ra, Người soạn thảo còn biết cách kiểm tra điều kiện “THE EDGE AHEAD”. Thoạt nhìn, có vẻ như Người soạn thảo thậm chí còn thô sơ hơn cả Minotaur: anh ta thậm chí còn không hiểu lệnh “ĐÚNG”. Nhưng sự đơn giản là lừa dối. Để làm quen với Draftsman và đảm bảo rằng nó không tầm thường, hãy thử làm các bài tập 10–11.

VÒNG TRÒN

⟦column⟧

Các chương trình dành cho Người soạn thảo có thể được viết dưới bất kỳ hình thức nào thuận tiện cho bạn, sử dụng bất kỳ phương pháp viết nhánh, vòng lặp và chương trình con nào. Bạn không thể buộc Người soạn thảo thực hiện các lệnh mà anh ta không thể thực hiện được (ví dụ: “ĐÚNG”) và kiểm tra các điều kiện mà anh ta không hiểu (ví dụ: điều kiện “CẠNH TRÁI”). Và điều cũng rất quan trọng - Người soạn thảo không biết đếm. Nó không có khả năng lặp với các tham số hoặc làm việc với các biến số (hoặc bất kỳ biến nào khác). Nếu người đọc không thoải mái khi làm việc với chương trình bằng ngôn ngữ “tùy ý”, thì chúng tôi sẽ sử dụng BLACK BASIC: mỗi dòng chứa một số lệnh và một lệnh chỉ có dạng GOTO N (đi tới lệnh số N), “PAINT”, “LEFT”, “JUMP” hoặc bước nhảy có điều kiện IF EDGE, THEN GOTO N. Và nếu không có chuyển đổi thì lệnh có số tiếp theo sẽ được thực thi tiếp theo.

Bài tập

11. Viết một chương trình cho Người soạn thảo, theo đó anh ta, trên bất kỳ tờ giấy nào: a) sẽ đến góc của tờ giấy, bất cứ nơi nào chúng ta đặt nó; b) sơn tất cả các ô của tờ giấy; c) sẽ di chuyển ra khỏi mép của tờ giấy nếu nó được đặt ở mép; d) xác định xem anh ta có ở trong góc hay không, sơn hình vuông ở góc nếu anh ta ở trong góc và giữ nguyên vị trí ban đầu nếu không. 12. Viết chương trình cho Người soạn thảo, theo đó anh ta, trên một tờ giấy vuông bất kỳ: a) bắt đầu từ vị trí trong Hình 2, vẽ một dải k 2 ô nếu k chẵn và trở về vị trí ban đầu không vẽ gì nếu k lẻ; b*) sẽ tô màu tất cả các ô của hình vuông, ngoại trừ các ô chứa tâm của nó (tuỳ theo độ dài ngang bằng của cạnh trang tính mà tâm là một ô hoặc bốn ô).

Cơm. 2

⟦folio 40⟧

KVA NT 2024/Số 3

⟦column⟧

Tính từ “mô hình” không phải ngẫu nhiên - nó rất giống với những gì các nhà khoa học tự nhiên làm, loại bỏ một phần đặc tính của một hiện tượng tự nhiên để làm cho nó có thể nhìn thấy được. Những ý tưởng thường gặp, “lý luận tiêu chuẩn” (ví dụ nguyên lý Dirichlet, tính tuần hoàn) cũng có thể được coi là mô hình của các tình huống. Những mô hình này sơ đồ đến mức trông tầm thường, nhưng biết được những “điều tầm thường” như vậy sẽ khiến cuộc sống trở nên dễ dàng hơn nhiều.

Bài tập

16. Giả sử rằng Người soạn thảo không chỉ có thể vẽ mà còn có thể xóa sơn khỏi ô đã sơn (giả sử sử dụng lệnh “ERASE”). a) Viết chương trình cho Người soạn thảo, theo đó anh ta sẽ vẽ các ô trung tâm và chỉ chúng. b) Chứng minh rằng không thể tạo một chương trình cho Người soạn thảo “xóa” mà theo đó anh ta sẽ vẽ một hệ các ô vuông lồng nhau trên một tờ giấy vuông bất kỳ (Hình 5).

⟦figure⟧

Cơm. 4

nhưng mô hình sử dụng số mũ cho số nguyên tố - có một chỉ số thì có nhiều. Từ thực tế này, người ta có thể rút ra tính không thể quyết định được về mặt thuật toán của một số phát biểu - ví dụ, định lý Matiyasevich đã được đề cập ở trên. Bạn đã thấy ý tưởng đi xe đạp hoạt động như thế nào. Mặc dù trông khá đơn giản, nhưng bài toán, lấy ý tưởng này làm ý chính, không phải lúc nào cũng dễ dàng. Có chuyện gì thế này? Hóa ra là ngay cả những ý tưởng chính rất đơn giản cũng nên biết trước, nếu không chúng sẽ khó được khám phá giữa những ý tưởng và sự phức tạp về mặt kỹ thuật khác. Nếu chưa xác định được ý chính và có khó khăn về mặt kỹ thuật thì ý tưởng đó phải được “trích xuất”, nhưng không phải trực tiếp mà có sự giúp đỡ của người khác bài toán. Xét cho cùng, bài toán không tồn tại một mình mà được bao quanh bởi những người thân của nó (ngay cả đối với lời giải “một ô” bài toán 1, cần phải xem xét các chữ số cuối cùng của tất cả các lũy thừa của hai). Vì vậy, họ nghiên cứu bài toán, có liên quan về mặt tư tưởng với cái này (đây là cách lời giải bài toán 13 về tâm hình vuông được đặt ra). Thông thường, vì mục đích này, các trường hợp đặc biệt quan trọng nhất hoặc mô hình khác bài toán sẽ được xem xét, trong đó các khó khăn hiện diện ở “dạng yếu hơn” và có ít khó khăn kỹ thuật hơn.

⟦figure⟧

Cơm. 5

17. Viết thông dịch viên cho ngôn ngữ Minotaur và Draftsman.

Khái quát hóa ý tưởng về tính chu kỳ

Khái quát hóa ý tưởng về tính chu kỳ là phổ biến. Chúng ta đã thấy ý tưởng này hoạt động như thế nào trong trường hợp “rời rạc”, khi chúng ta chỉ làm quen với một số ứng dụng của ý tưởng về tính tuần hoàn và với trường hợp “rời rạc” khi số lượng trạng thái là hữu hạn. Nhưng ngay cả trong trường hợp “liên tục”, với vô số trạng thái, tính tuần hoàn hay chính xác hơn là “gần như tuần hoàn” thường phát sinh, khi các trạng thái không được lặp lại một cách tuyệt đối chính xác mà chỉ xấp xỉ. Vì vậy, mùa hè nào cũng giống và khác với mùa hè trước. Người xưa đã nghĩ đến điều này, và chúng tôi sẽ kể cho bạn vào lúc khác. Hãy xem một ví dụ điển hình.

⟦folio 42⟧

KVANT 2024/№3

19**. Gọi a là số vô tỷ và b là số tùy ý trong khoảng 0; 1, q m là phần nhỏ nhất của phần phân số n a, trong đó $n <^{m}$ là số nguyên. Tương tự, r m là giá trị nhỏ nhất của phân số $части^{b} n ^{a}$. Chứng minh rằng q m! r m cho vô hạn $многих^{m.} 20.$ a) Chứng minh rằng các số chia hết cho 2 có thể gần giống với các số $вида^{n} 1 2$, trong đó n là số tự nhiên tùy thích. b*) Chứng minh rằng lũy ​​thừa của hai có thể bắt đầu bằng số chín bất kỳ. Gợi ý. Lấy logarit cơ số 10 của bất đẳng thức $0,9^{…} 9$ $10^{k} 2^{l} 10^{k}$. Sử dụng tính vô tỷ của log 2. c*) Xác suất của lũy thừa được chọn ngẫu nhiên của hai bắt đầu bằng một là bao nhiêu? d*) Chứng minh rằng tồn tại n sao cho các số $2^{n}$ và $3^{n}$ đồng thời bắt đầu bằng các chữ số $1000...^{21*.}$ Cho ánh xạ F lấy bình phương đơn vị K vào chính nó và bảo toàn diện tích mỗi tập con của nó. Chứng minh rằng với mọi tập con của hình vuông U có diện tích lớn hơn 0, luôn tồn tại một điểm x từ U sao cho với một số $n > 0 точка^{F} …^{x}$ ... (n lần) cũng thuộc U. Một phát biểu tổng quát hơn được gọi là định lý truy hồi Poincaré. Định lý này dẫn đến một kết luận có phần bất ngờ: nếu bạn mở một chai nước hoa trong một căn phòng kín thì gần như chắc chắn sau một thời gian tất cả các phân tử của chất có mùi đó sẽ tụ lại trong chai (mặc dù thời gian “một lúc nào đó” dài hơn nhiều so với vòng đời của Vũ trụ). Bằng chứng của thực tế này gợi nhớ đến cách lập luận trong các bài toán về đàn minotaur hoặc nhân mã: vị trí của tất cả các phân tử được mô tả gần giống nhau bởi một điểm trong không gian trạng thái (không gian pha), kết quả trả về được thiết lập bằng định lý Poincaré. Thông thường lý do của tính tuần hoàn về bản chất là nếu tập hợp các trạng thái bị giới hạn thì hai trạng thái sẽ “gần như lặp lại” và sẽ ở gần nhau trong một thời gian. Người xưa đã nghĩ tới điều này. Chúng tôi sẽ kết thúc bài viết về sự trở lại này bằng cách quay trở lại Truyền đạo: “Mặt trời mọc, mặt trời lặn, vội vã về nơi nó mọc. Gió đi về hướng nam, đi về hướng bắc, quay tròn, quay tròn, và gió quay lại theo vòng tròn.”

⟦column⟧

của họ. Mọi sông đều chảy ra biển, nhưng biển không tràn; đến nơi sông chảy, chúng lại chảy trở lại... Cái đã có là cái sẽ có; và những gì đã làm sẽ được thực hiện, và không có gì mới dưới ánh mặt trời.

* * * Hãy cung cấp thêm một vài bài toán về các chủ đề được thảo luận.

1*. Hàm số y cos $x cos^{5} 2 x cos^{5} 4x cos^{5} 8x$ có tuần hoàn không?

2. Tổng của hai hàm tuần hoàn có chu kỳ 1 và 2 nhỏ nhất có thể lại là hàm tuần hoàn không? 3**. Tuyên bố chung: hãy $a_{1}$, … $, a_{n}$ – các số thực sao cho không có số nào trong số chúng có thể được biểu diễn dưới dạng các số khác bằng cách sử dụng tổ hợp tuyến tính với các hệ số hữu tỉ. Sau đó với bất kỳ tập hợp nào $0 b_{i} 1$ và bất kỳ H! 0 tồn tại một L sao cho với mọi i bất đẳng thức L a i b i H là đúng (đối với L được chọn ngẫu nhiên thì điều này đúng với xác suất $H^{n} ). 4.$ Giấy kiểm tra được đưa ra. Các đường song song được vẽ thông qua hai nút. Chứng minh rằng dải kín thu được chứa vô số nút lưới. 5. a) Chứng minh rằng nếu bán kính của một hình tròn tiến tới vô cùng thì khoảng cách từ nó đến điểm nguyên gần nhất có xu hướng bằng 0. b) Tỷ lệ số điểm nguyên rơi trên một đường tròn với bán kính của nó cũng có xu hướng bằng không. 6. Năm nhà khoa học đi dọc hành lang của Viện MIMINO, đến cuối hành lang, mỗi người quay lại. Trong khi Trưởng đi qua hành lang một lần, Trưởng đi qua hai lần, Cấp trên - ba, Cấp trung - năm, Cấp dưới - bảy lần. Chứng minh rằng có một thời điểm tất cả chúng đều hướng về cùng một đích. 7. Chỉ rõ lũy thừa của 5 sao cho trong ký hiệu thập phân của nó sẽ có hơn 1000 số 0 liên tiếp. Và sao cho có sự kết hợp của chính xác 1000 số 0 liên tiếp? 8. Chứng minh rằng có lũy thừa của 3 bắt đầu bằng 1000 chữ số ở cuối. 9. Cho hai đường thẳng tạo thành một góc M. Một điểm M nằm trên một điểm và một con bọ chét đậu ở điểm này và nhảy từ đường thẳng này sang đường thẳng khác đúng 1 cm, và luôn đến một điểm khác điểm trước đó. Chứng minh rằng nếu con bọ chét quay lại điểm xuất phát thì số M S là số hữu tỉ. 10. Nếu cosin của một góc là 1 3 thì số đo của nó là vô tỉ. Chứng minh điều đó. Tóm tắt bài toán.
