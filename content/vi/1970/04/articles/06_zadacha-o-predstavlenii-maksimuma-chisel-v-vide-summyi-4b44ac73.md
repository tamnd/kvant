---
id: 1970-4-zadacha-o-predstavlenii-maksimuma-chisel-v-vide-summyi-4b44ac73
issue: kvant_1970_4
year: 1970
number: "4"
title: Bài toán về biểu diễn số lớn nhất của các số dưới dạng tổng
rubric: smes
page_first: 26
page_last: 29
page_labels: 24, 26, 27
tag: 2HDA
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 87beb5ffe263ff450a8534b558bf133769ba922ca53b645afc05dbab6cfc359f
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1970/04/articles/06_zadacha-o-predstavlenii-maksimuma-chisel-v-vide-summyi-4b44ac73.md
source_content_sha256: b4935daff891c585da12b5c0958455f1eb99e253859d31a441749b7a34eaf089
translation_model: gpt-5-6-mini
translation_run: m10-1970-vi
---

⟦folio 24⟧

BÀI TẬP

1. Cho rằng mỗi nam thanh niên kết bạn với không ít hơn $m$ cô gái, còn mỗi cô gái — không quá $m$ nam thanh niên ($m$ là một số tự nhiên tùy ý). Chứng minh rằng trong trường hợp này điều kiện của định lý về việc ghép đôi được thỏa mãn.

2. Các học sinh trong câu lạc bộ đã giải bài tập. Hóa ra mỗi người giải được 4 bài và mỗi bài được giải bởi bốn học sinh. Chứng minh rằng có thể tổ chức việc trình bày lời giải sao cho mỗi học sinh trình bày đúng một bài và tất cả các bài đều được trình bày (mỗi bài một lần).

3. Cho một mạng vận chuyển. Tập hợp các đỉnh chứa lối ra nhưng không chứa lối vào được gọi là một lát cắt của mạng. Khả năng thông qua của lát cắt $B$ được gọi là số $c(B)$, bằng số cung đi vào $B$. Nếu $\phi$ ký hiệu dòng chảy, thì $|\phi|$ sẽ ký hiệu độ lớn của dòng chảy. Chứng minh rằng với mọi dòng chảy $\phi$ và mọi lát cắt $B$ đều đúng bất đẳng thức: $|\phi| \leq c(B)$.

4. Lát cắt $B$ được gọi là tối thiểu nếu khả năng thông qua $c(B)$ của nó là nhỏ nhất trong số các khả năng thông qua của tất cả các lát cắt. Dùng thuật toán Ford—Fulkerson, suy ra rằng khả năng thông qua của lát cắt tối thiểu bằng độ lớn của dòng chảy cực đại — max $|\phi| = \min c(B)$ (định lý Ford—Fulkerson).

5. Kiểm tra rằng nếu $\phi$ — là luồng cực đại, thì lát cắt nhận được bằng cách hợp tất cả các đỉnh không được đánh dấu (các đánh dấu được thực hiện xuất phát từ luồng $\phi$, bằng phương pháp Ford—Fulkerson) là lát cắt tối thiểu.

6. Chứng minh rằng hợp và giao của bất kỳ hai lát cắt tối thiểu nào cũng lại là lát cắt tối thiểu.

7. Chứng minh rằng lát cắt tạo bởi các đỉnh không được đánh dấu (đối với luồng cực đại) là hợp của tất cả các lát cắt tối thiểu. Suy ra từ đó rằng lát cắt này không phụ thuộc vào việc các luồng được thực hiện bằng lát cắt cực đại nào.

TÀI LIỆU THAM KHẢO

1. A. Kofman, R. For, Nghiên cứu vận trù học, «Mir», 1966.
2. C. Berge, Lý thuyết đồ thị và ứng dụng của nó, IL, 1962.
3. L. Ford, D. Fulkerson, Luồng trong mạng, «Mir», 1966.
4. O. Ore, Lý thuyết đồ thị, «Nauka», 1968.
5. D. Gale, Lý thuyết các mô hình kinh tế tuyến tính, IL, 1963.

PARI CỦA CÁC NHÀ TOÁN HỌC VÀ VẬT LÝ HỌC

Ở Paris có nhiều tòa nhà gắn liền với ký ức về những nhà khoa học lỗi lạc của các thế kỷ trước. Cạnh Louvre, nơi trước kia từng là thành lũy của các vị vua, ngay trước cuộc cách mạng năm 1789 đã trở thành nơi họp của các viện sĩ. Mặc dù sau đó, dưới thời Napoléon I, Louvre trở thành bảo tàng, nhưng khi ấy trong đó vẫn có một số nhà khoa học được bố trí nơi ở. Còn lưu lại bức thư của Legendre, trong đó nhà toán học này khẩn cầu được cho ở trong phần cũ của cung điện.

Ở Paris có những đường phố mang tên các nhà toán học, nhà vật lý và nhà thiên văn học, trong đó không phải tất cả các nhà khoa học này đều là người Pháp. Những cái tên đó là: Legendre, Réaumur, Pascal, Pierre Curie, Marie Curie, Lambert, Buffon, Franklin, Carnot, Arago, Descartes, Leibniz...

Câu «Số $z$ là số lớn hơn trong hai số $x$ và $y$» có thể được viết bằng công thức như sau:

$$z = \frac{1}{2} (|x - y| + x + y).$$

Còn viết câu «Số $u$ là số lớn nhất trong ba số $x, y$ và $z$» như thế nào?

Chứng minh rằng từ АБАБАБ chia hết cho 7 (А và Б — là những chữ số bất kỳ).

CÂU HỎI BÓNG ĐÁ

Như đã biết, các trận đấu tranh cúp bóng đá được tiến hành theo cái gọi là hệ thống Olympic: đội thua bị loại, trong trường hợp hòa — đấu lại.

Trong năm đó không có các trận đấu lại, và có 75 đội tham gia thi đấu.

Đã diễn ra bao nhiêu trận đấu tranh cúp?

⟦trang 26⟧

F19. Hình dạng của các bình thông nhau được thể hiện trong hình 1. Nước sẽ chảy theo hướng nào qua ống nối các bình, nếu đun nóng nước trong một bình?

F20. Song song với trục của một hình trụ bán kính $R$ người ta khoan một lỗ ở khoảng cách $\frac{R}{2}$ từ tâm của nó. Bán kính lỗ bằng $\frac{R}{2}$. Hình trụ nằm trên một tấm ván, tấm ván được nâng chậm lên ở một đầu (hình 2). Tìm góc nghiêng giới hạn của tấm ván mà tại đó hình trụ vẫn còn ở trạng thái cân bằng. Hệ số ma sát của hình trụ với tấm ván bằng 0,2.

Olympiad vật lý toàn Liên Xô qua đường bưu điện, năm 1967.

F21. Trục phần ứng của hai động cơ điện một chiều giống nhau được nối cứng với nhau. Nếu các cuộn dây phần ứng được nối với những nguồn điện giống nhau có sức điện động ε, thì tốc độ góc quay của các phần ứng khi không tải bằng $\omega_0$; nếu hãm các động cơ để chúng không quay, thì qua các cuộn dây phần ứng có dòng điện $I_0$. Một trong các nguồn điện được chuyển mạch sao cho mômen quay của các động cơ ngược chiều nhau. Cần tác dụng mômen ngoài nào lên trục phần ứng để chúng quay với tốc độ góc đã cho $\omega$? Ma sát trong các động cơ có thể bỏ qua; từ trường của stato được tạo ra bởi nam châm vĩnh cửu.

Olympiad vật lý toàn Liên Xô lần thứ III, năm 1969.

Ф22. Hai thợ rèn gia công một miếng sắt. Trước hết đặt nó lên đe và lần lượt dùng búa đập, sau đó treo nó lên trần nhà và đồng thời đập từ các phía khác nhau. Lực đập của mỗi thợ rèn trong cả hai trường hợp là như nhau. Trong trường hợp nào miếng sắt sẽ nóng lên nhiều hơn sau một lần đập?

A. M. Budker

Ф23. Trên mặt phẳng nằm ngang có hai ống mỏng giống nhau, mỗi ống có khối lượng $m$. Trục của chúng song song với nhau, còn bán kính bằng $R$. Ban đầu một trong các ống đứng yên, còn ống thứ hai lăn không trượt theo hướng về phía ống thứ nhất cho đến khi va chạm. Vận tốc chuyển động tịnh tiến của ống bằng $v_0$. Các vận tốc tịnh tiến và vận tốc góc quay của các ống phụ thuộc vào thời gian như thế nào (hãy vẽ đồ thị)? Hệ số ma sát trượt của các ống với mặt phẳng nằm ngang bằng $k$, ma sát giữa các ống khi va chạm có thể bỏ qua, va chạm hoàn toàn đàn hồi.

Olympiad vật lý toàn Liên Xô lần thứ III, năm 1969.

⟦folio 27⟧

М16. Chứng minh rằng đa thức $p(x)$ với các hệ số nguyên, nhận giá trị 1 tại ba giá trị nguyên khác nhau của $x$, không thể có bất kỳ nghiệm nguyên nào.

М17. Một người nông dân, khi đến chỗ rẽ của hai con đường tạo với nhau góc $60^\circ$, hỏi: «Làm thế nào để đi đến làng $NN$?» Người ta trả lời: «Đi theo con đường bên trái đến làng $N$ — nó cách đây tám dặm, — ở đó anh sẽ thấy rằng một con đường lớn thẳng tắp rẽ sang bên phải vuông góc với đường này — đó chính là con đường đến $NN$. Cũng có thể đi theo cách khác: bây giờ đi theo con đường bên phải; khi ra đến đường sắt — tức là đã đi được một nửa quãng đường, — ở đó rẽ trái và đi thẳng theo đường ray đến tận $NN$.» — «Thế còn đường nào ngắn hơn?» — «Đằng nào cũng vậy, đi cách này hay cách kia cũng không khác gì cả». Và người nông dân đi theo con đường bên phải.

Anh ta sẽ phải đi bao nhiêu dặm đến $NN$? Lớn hơn mười hay nhỏ hơn? Còn nếu đi thẳng từ chỗ rẽ đến $NN$ thì sao? (Tất cả các con đường đều được coi là thẳng.)

M18. a) Chứng minh rằng đối với mọi điểm $M$ trên đường tròn ngoại tiếp tam giác đều $ABC$, một trong ba đoạn thẳng $MA, MB, MC$ bằng tổng của hai đoạn còn lại.

6) Ba đường tròn bằng nhau $\gamma_1, \gamma_2, \gamma_3$ đôi một tiếp xúc với nhau, và có một đường tròn $\gamma$ ngoại tiếp chúng, tiếp xúc với cả ba đường tròn: $\gamma_1, \gamma_2$ và $\gamma_3$. Chứng minh rằng đối với mọi điểm $M$ trên đường tròn $\gamma$, tiếp tuyến kẻ từ điểm $M$ đến một trong ba đường tròn $\gamma_1, \gamma_2, \gamma_3$ bằng tổng các tiếp tuyến kẻ từ điểm $M$ đến hai đường tròn còn lại.

M19. Trong một chuỗi vô hạn các ô kề nhau, mỗi ô có thể ở một trong hai trạng thái: «nghỉ» và «kích thích». Nếu tại thời điểm hiện tại một ô bị kích thích, thì nó phát ra tín hiệu, tín hiệu này sau một đơn vị thời gian (chẳng hạn, sau một mili giây) đến hai ô kề với nó. Mỗi ô bị kích thích khi và chỉ khi nó nhận được tín hiệu từ một trong các ô kề;

nếu tín hiệu đến đồng thời từ hai phía, thì chúng triệt tiêu nhau và ô không bị kích thích. Ví dụ, nếu tại thời điểm ban đầu $t=0$ kích thích ba ô kề nhau, còn các ô khác để ở trạng thái nghỉ, thì sự kích thích sẽ lan truyền như chỉ ra trong hình 3). (Các ô bị kích thích — màu xanh).

Giả sử tại thời điểm ban đầu chỉ có một ô bị kích thích. Sau 15 mili giây sẽ có bao nhiêu ô ở trạng thái kích thích? Sau 65 mili giây? Sau 1000 mili giây? Nói chung, sau $t$ mili giây?

Điều gì xảy ra trong trường hợp chuỗi không vô hạn mà chỉ chứa $N$ ô, được nối thành một vòng tròn (hình 4) — sự kích thích có duy trì mãi mãi hay sẽ tắt dần?

H. Vasiliev

M20. Có thể chia một tam giác đều thành một triệu đa giác lồi sao cho bất kỳ đường thẳng nào cũng cắt không quá bốn mươi đa giác trong số đó hay không? (Ta nói rằng một đường thẳng cắt một đa giác nếu nó có ít nhất một điểm chung với đa giác đó.)

Olympiad Toán học Moskva lần thứ XXXI

*) Giả thiết này không phản ánh hành vi thực tế của các tế bào thần kinh trong hệ thần kinh của các cơ thể sống.
