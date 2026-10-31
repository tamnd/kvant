---
id: 1985-11-boltyanskiy-otgadat-den-rozhdeniya-bcb6f96d
issue: kvant_1985_11
year: 1985
number: "11"
title: Đoán ngày sinh nhật
authors:
  - Болтянский В. Г.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 30
page_last: 32
page_labels: 28-30
tag: C0A0
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 59d042e247d5b63fb8e5ea0927cfbf90c19d6ece0c9b62433547f623e23ef08b
prompt_sha256: draft-1
translated_from: content/ru/1985/11/articles/13_boltyanskiy-otgadat-den-rozhdeniya-bcb6f96d.md
source_content_sha256: c53b1f01603da90705b1c2855b6796997b2db7b4c9ff1cfb611386bdb376bcbb
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 28⟧

Đoán ngày sinh nhật

Thành viên tương ứng
Viện Hàn lâm Khoa học Sư phạm Liên Xô
V. G. BOLTYANSKY

Một ghi chú nhỏ với tiêu đề sau: “Đoán ngày sinh nhật” nằm ở Ya. I. Cuốn sách “Đại số giải trí” của Perelman. Ghi chú này mô tả một thủ thuật số nhất định. Đây là những gì nó bao gồm.

Hãy tưởng tượng một người quen của bố bạn đến gặp bạn nhưng bạn không biết ngày sinh của người đó. Mời anh ta nhân số ngày sinh của anh ta với 12, số tháng anh ta sinh ra, nhân với 31, rồi cộng các kết quả thu được. Hãy để anh ấy nói cho bạn biết anh ấy đã làm gì. Hóa ra bằng cách lấy tổng của hai sản phẩm này, bạn có thể tìm ra cả hai số cần thiết (ngày và tháng sinh). Bạn có thể xem thủ thuật này được thực hiện như thế nào trong Ya. I. Cuốn sách của Perelman. Bây giờ chúng tôi sẽ mách bạn một cách khác để thực hiện thủ thuật tương tự; Phương pháp này được đề xuất bởi Pedro dela Risco Padron, một độc giả người Cuba của Ya. I. Cuốn sách của Perelman.

Chúng ta hãy biểu thị bằng $x$ ngày sinh của người quen đến thăm và $y$ số tháng sinh của anh ta. Một người bạn cho bạn biết số tiền $12x+31y$. Hãy xét hai trường hợp: a) $y$ chẵn; b) $y$ là số lẻ.

a) $y$ là số chẵn, tức là $y=2k$. Sau đó $12x+31y=12x+62k=$
$$=12(x+5k)+2k=12(x+5k)+y.$$
Điều này chứng tỏ số $12x+31y$ có cùng số dư khi chia cho 12 (chúng ta ký hiệu là $r$) là số $y$. Số $y$ thường nhận các giá trị từ 1 đến 12 và trong trường hợp của chúng tôi ($y$ là số chẵn) $y$ có thể bằng 2, 4, 6, 8, 10 hoặc 12. Người ta hiểu rằng $y=12$ khi $r=0$. Nếu $r \neq 0$ và $r$ chẵn thì chúng ta có $y=r$.

b) $y$ là số lẻ, tức là $y=2k+1.$

Sau đó
$$12x+31y=12x+31(2k+1)=
=12(x+5k)+2k+7=
=12(x+5k+2)+y+6,$$
từ đó rõ ràng là số $12x+31y$ có cùng số dư $r$ khi chia cho 12 như số $y+6$, nghĩa là, $y$ trùng với số $r-6$ hoặc khác với số 12. Điều này có nghĩa là nếu $r$ là số lẻ và $r>6$ thì $y=r-6$; nếu $r$ là số lẻ và $r<6$ thì $r-6$ là âm và do đó $y=(r-6)+12=r+6$.

Đây là nơi Pedro dela Risco Padron đề xuất thực hiện thủ thuật:

1) nếu $r$ chẵn, nhưng $r \neq 0$, thì $y=r$;
2) nếu $r=0$, thì $y=12$;
3) nếu $r$ là số lẻ và $r>6$, thì $y=r-6$;
4) nếu $r$ là số lẻ và $r<6$ thì $y=r+6$.

Tìm $y$ và tính tích $31y$, bạn trừ tích này khỏi số $12x+31y$ đã cho, tìm số $12x$, sau đó chia kết quả cho 12, tìm $x$. Ngày sinh đã được xác định.

Bây giờ chúng ta hãy xem thủ thuật này từ một góc nhìn khác. Một năm có 365 hoặc 366 ngày và bất kỳ ngày nào trong số đó cũng có thể là ngày sinh nhật của một người bạn của bố tôi. Do đó, “khối lượng” thông tin có thể được báo cáo bằng 366. Nếu thay vì biểu thức $12x+31y$, một biểu thức khác được sử dụng và sao cho trong hai ngày khác nhau trong năm, biểu thức đó sẽ nhận được các giá trị giống nhau, thì biểu thức đó sẽ không phù hợp để thực hiện thủ thuật. Sau khi nhận được giá trị này, bạn sẽ không thể xác định ngày nào trong số hai ngày tương ứng với giá trị này của biểu thức sẽ diễn ra ngày sinh nhật. Biểu thức $12x+31y$ được lấy vì trong tất cả 366 ngày trong năm (năm nhuận), nó có các giá trị số khác nhau.

Nhưng $12x+31y$ không phải là biểu thức duy nhất có thuộc tính này. Các biểu thức $12x+35y$, $12x+37y$, $2x+31y$, $3x+31y$, $4x+31y$, $12x+7y$, $12x+5y$, $12x+y$ và các biểu thức khác có cùng thuộc tính. Ví dụ: lấy biểu thức $12x+y$, bạn có thể đưa ra một phiên bản đơn giản của thủ thuật: nhân số lần sinh với 12, cộng số tháng sinh và báo cáo kết quả. Và “thuật toán” để thực hiện một thủ thuật như sau:

⟦folio 29⟧

phiên bản đơn giản hóa sẽ hoàn toàn đơn giản: bạn cần xác định số dư $r$ từ việc chia số được báo cáo $12x+y$ cho 12, sau đó với $r \neq 0$ chúng ta có $y=r$ và với $r=0$ sẽ có $y=12$. Đúng, phiên bản đơn giản hóa của thủ thuật này rất dễ giải quyết.

Cuối cùng, bạn có thể lấy biểu thức $100x+y$, sau đó ngày chia được xác định khá đơn giản và không thú vị（《tầm thường》，như các nhà toán học nói): số hàng trăm bằng số phép chia và hai chữ số cuối cho biết vị trí của phép chia. Ví dụ: đối với ngày 16 tháng 7 (tức là $x=16$, $y=7$), chúng ta có $100x+y=1607$; bây giờ chỉ cần đặt một dấu chấm là đủ, tức là viết 16/07 và bạn sẽ có được một phương pháp viết ngày, thường được sử dụng trên các tài liệu (chỉ họ thêm một năm khác: 16/07/72).

Bài toán
1. Hãy tự thực hiện thủ thuật được mô tả và “đoán” ngày sinh của bạn bằng cách sử dụng các biểu thức: a) $100x+y$; b) $12x+y$; b) $12x+31y$.
2. Chứng minh rằng nếu các số tự nhiên $a, b$ thỏa mãn bất đẳng thức $31a+12b \leq 366$ thì biểu thức $ax+by$ không cho phép thủ thuật được mô tả.
3. Chứng minh rằng nếu các số tự nhiên $a, b$ thỏa mãn bất đẳng thức $a<12$ và $b<31$ thì biểu thức $ax+by$ không cho phép thực hiện thủ thuật này.
4. Chứng minh rằng mỗi biểu thức a) $x+31y$, b) $16x+31y$; b) $12x+7y$ phù hợp để thực hiện thủ thuật được mô tả.

Biên tập. Liên quan đến ghi chú này, chúng ta hãy nhớ lại một thủ thuật thú vị khác. Đây là bài toán thanh lịch, được D. B. Fuchs phát minh ra nhiều năm trước. Đúng vậy, trong bài toán này chúng ta không nói về những ngày xa cách và về những cuộc hẹn hò nói chung, nhưng bạn cũng cần đoán một số con số.

Hai người quay đang chơi trò chơi đoán số. Người đầu tiên nghĩ về 10 trong các số tự nhiên (chúng ta biểu thị chúng bằng $x_1, \dots, x_{10}$). Người thứ hai cố gắng trấn an họ, đặt câu hỏi. Như một câu hỏi, anh ấy đưa ra câu đầu tiên là 10 số tự nhiên của mình - hãy biểu thị chúng bằng $a_1, \dots, a_{10}$. Cái đầu tiên trong đáp số cho anh ta biết biểu thức $a_1x_1+...+a_{10}x_{10}$ bằng gì. Sau khi nghe đáp số, người tham gia thứ hai hỏi câu hỏi tiếp theo - tương tự như câu hỏi đầu tiên, nhưng với câu hỏi còn lại $a_1, \dots, a_{10}$. Và vân vân. Trong số câu hỏi nhỏ nhất có thể giải được tất cả các số $x_1, \dots, x_{10}$ là bao nhiêu?

bài toán này từng được phát minh cho Olympic Toán học Moscow, nhưng đã không thành công: các thành viên của Ban tổ chức Olympic không thể cưỡng lại việc tặng nó trước tiên cho nhau, sau đó cho người quen của họ, và bài toán đã được biết đến rộng rãi. Đáp số còn nhiều điều hơn thế nữa so với cái nhìn đầu tiên: hóa ra chỉ cần hai câu hỏi (!).

Đối với câu hỏi đầu tiên, hãy lấy $a_1 = ...=a_{10}=1$. Trong đáp số cho câu hỏi này, chúng ta nhận được tổng $x_1+...+x_{10}$, được hoàn thành bằng số lớn hơn của mỗi $x_1, \dots, x_{10}$ (đó mới là vấn đề). Bây giờ chúng ta hãy lấy $m$ sao cho số được viết thành một với $m$ số 0 không nhỏ hơn đáp số cho câu hỏi đầu tiên và đặt câu hỏi sau: $a_1=1, a_2=10...0, a_3=10...0, a_4=10...0, ..., a_{10}=10...0$. Trong đáp số, chúng ta sẽ nhận được một số dài, trong đó số dự định đầu tiên sẽ được viết bằng các chữ số $m$ cuối cùng (có lẽ một số số 0 được gán ở đầu), ở các số tiếp theo từ cuối

⟦folio 30⟧

m chữ số - số thứ hai, sau đó là số thứ ba, v.v.

Ví dụ: $x_1=4, x_2=11, x_3=21, x_4=14, x_5=9, x_6=7, x_7=1, x_8=12, x_9=3, x_{10}=11$. Đáp số cho câu hỏi đầu tiên: 90. Câu hỏi thứ hai: $a_1=1, a_2=100, a_3=10000, \dots, a_{10}=10...0$.

Đáp số cho câu hỏi thứ hai: 11031201070914211104. Lấy hai chữ số từ cuối, ta được các số dự định: 04, 11, 21, ...

Ba tác phẩm quan trọng của Albert Einstein
(Xem phần đầu ở trang 26)

các phân tử va vào nó từ phía đối diện, và sau đó một lực nhất định tác dụng lên hạt, khiến nó chuyển động. Hướng của lực này thay đổi ngẫu nhiên nên hướng chuyển động của hạt cũng thay đổi ngẫu nhiên. Einstein đã phát triển một phương pháp đơn giản nhưng rất hiệu quả giúp người ta có thể “theo dõi” một hạt thực hiện chuyển động kiểu này.

Công trình này của Einstein là một trong những xác nhận thuyết phục nhất về thuyết động học phân tử.

Thứ ba, nhưng không quan trọng, công trình của Einstein, được xuất bản trên cùng tạp chí “Annalen der Physik” và cùng năm 1905, có tên là “Hướng tới khoa học điện tử về các vật thể chuyển động”. Bài viết được người biên tập nhận vào ngày 30 tháng 6 năm 1905. Tác phẩm này trình bày một cách thực tiễn, đầy đủ về lý thuyết đặc biệt của lý thuyết tương đối.

(Tuy nhiên, trong cùng năm đó và trên cùng một tạp chí, một tác phẩm ngắn và quan trọng khác của Einstein đã viết, “Liệu quán tính của một vật có phụ thuộc vào năng lượng mà nó chứa không?”, dành cho sự tương ứng có thể suy ra được giữa khối lượng của một vật và năng lượng của nó.)

Thật khó để nói ngắn gọn về lý thuyết tương đối của lý thuyết tương đối, và không thể kể một câu chuyện chi tiết do khuôn khổ bài viết có hạn. Chúng tôi chỉ nói thêm rằng sự ra đời của lý thuyết này gắn liền với sự xem xét lại căn bản các khái niệm cơ bản hình thành nên vật lý, như thời gian, không gian, độ dài, thời lượng, năng lượng, động lượng, khối lượng, v.v. Xét về tầm quan trọng của nó đối với thế giới tự nhiên, sự xuất hiện của lý thuyết lý thuyết tương đối của lý thuyết tương đối có thể được so sánh với sự xuất hiện của cơ học Newton hai thế kỷ trước đó.

Có vẻ khó tin khi một người có thể tạo ra ba cột trong một năm, khắc phục hậu quả của công việc trong ba lĩnh vực vật lý khác nhau (lý thuyết lượng tử về bức xạ, lý thuyết động học phân tử, lý thuyết tương đối).

Cần phải nói rằng mặc dù hiện nay chúng ta đánh giá rất cao công trình của Einstein vào năm 1905 nhưng khi đó không phải ai cũng hiểu ngay được ý nghĩa của nó. Đặc biệt, người sáng lập vật lý lượng tử, Max Planck, phải đồng ý với những ý tưởng về bản chất của ánh sáng được Einstein thể hiện theo ý nghĩa đầu tiên trong ba ý nghĩa của bài báo năm 1905 của ông. Tuy nhiên, một số nhà vật lý vĩ đại nhất thời bấy giờ đã nhận ra chúng ngay lập tức. Marie Curie cũng ở mức trung bình:

"Tôi chân thành ngưỡng mộ những công trình do ông Einstein xuất bản về các vấn đề của vật lý lý thuyết hiện đại. Tuy nhiên, tôi nghĩ rằng các nhà vật lý học công nhận rằng đây là công trình có đẳng cấp cao nhất. Tại một cuộc thi khoa học ở Brussels mà họ đã tham gia và kiến ​​thức sâu rộng! Chúng tôi biết rằng ông Einstein vẫn còn rất trẻ, nhưng điều này cho chúng tôi quyền đặt hy vọng cao nhất vào ông, nhìn thấy ở ông một trong những nhân vật lý thuyết vĩ đại nhất trong tương lai."

Những hy vọng này hoàn toàn chính đáng.

V. M. Bolotovsky
