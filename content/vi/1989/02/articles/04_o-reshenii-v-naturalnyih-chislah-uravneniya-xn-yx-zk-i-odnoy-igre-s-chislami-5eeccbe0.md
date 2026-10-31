---
id: 1989-2-o-reshenii-v-naturalnyih-chislah-uravneniya-xn-yx-zk-i-odnoy-igre-s-chislami-5eeccbe0
issue: kvant_1989_2
year: 1989
number: "2"
title: '[Về lời giải trong các số tự nhiên của phương trình x^n + y^x = z^k và một trò chơi với các con số]'
rubric: nam-pishut
page_first: 16
page_last: 24
page_labels: 14, 15, 17, 18, 19, 20, 21, 22
tag: 7F7Y
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 2817f4cffece1248a11ee9f07938a91f335720cd9ad80b39608c6687d09e5cb0
prompt_sha256: draft-1
translated_from: content/ru/1989/02/articles/04_o-reshenii-v-naturalnyih-chislah-uravneniya-xn-yx-zk-i-odnoy-igre-s-chislami-5eeccbe0.md
source_content_sha256: f75ea6b4c08cc050b01e1168c38d2734d7b9009f44c7aae895e3178ddeb45104
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 14⟧

Nghiên cứu có hệ thống về lý thuyết nút được khởi xướng bởi nhà vật lý vĩ đại người Anh J. Maxwell. Ông đi đến kết luận rằng sóng thực hiện các tương tác điện từ, và rồi một ý tưởng thậm chí còn táo bạo hơn nảy ra trong đầu ông: bản thân các hạt tương tác cũng là sóng; nhưng vì các hạt (nguyên tử) rất nhỏ và sóng dài nên các nguyên tử sóng phải khép lại trong một vùng không gian nhỏ: đây là những nút thắt trong ký ức của chúng, tất cả thông tin vật lý cụ thể về nguyên tử được lưu trữ, được mã hóa theo đúng bản chất của nút thắt của nguyên tử. Maxwell và các học trò của ông bắt đầu nghiên cứu các nút thắt và bắt đầu phân loại một cách có hệ thống dưới dạng bảng.

Các nhà toán học, đã ở trường của chúng tôi, bắt đầu nghiên cứu về các nút thắt, và khá thẳng thắn: họ bị thu hút bởi chính vẻ đẹp của chủ đề này. Các bất biến tinh tế do IMMI tạo ra (và bài viết “Nút thắt, bảo vệ và đa thức của chúng” trong số thứ 4 «Kvant» sẽ được dành cho chúng) đã giúp có thể tiến bộ đáng kể trong nghiên cứu về nút thắt,

tính bốc đồng

F. P. Grosu từ Chisinau nghiên cứu lời giải về số tự nhiên của phương trình $x^n + y^m = z^k$. Hóa ra nếu $k \geq n > m$, $x \geq y$ và $k/n = p$ là số tự nhiên thì không có nghiệm nào cả. Bằng chứng. Bởi vì $x \geq y$, $x^m \geq y^m$ và $x^n + x^m \geq z^k$. Kể từ $(x+1)^n > x^n + x^m$, $(x+1)^n > z^k$. Vì vậy, $x > z^p - 1$. Mặt khác, $x = \sqrt[n]{z^k - y^m} < z^p$. Vậy $z^p > x > z^p - 1$, vậy $x$ không thể là số nguyên.

Mệnh đề sau được chứng minh tương tự:

nếu hệ phương trình

$$\begin{cases} x^n + y^m = a \\ x^m + y^n = b \end{cases}$$

vì $n > m \geq 1$, $a > b$ có lời giải tự nhiên, nên lời giải này có dạng

$$x = \sqrt[n]{a}, y = \sqrt[m]{a - \sqrt[n]{a}} = \sqrt[n]{b - \sqrt[n]{a}}^m,$$

trong đó dấu ngoặc vuông biểu thị phần nguyên của số. Ví dụ,

$$\begin{cases} x^3 + y^2 = 134 \\ x^2 + y^3 = 52 \end{cases}$$

Nhà kinh điển học mười I. Grigoriev từ Aktyubinsk thay thế điều đó để nhân bốn số với 6, bạn có thể sử dụng công thức $ab...xy \cdot 6 = ky$, trong đó $k = ab...x + 1/2ab...xy$.

Phương pháp thổi này thường đơn giản hơn so với cách thổi thông thường “theo cột”.

V. E. Koshakov đến từ Leningrad đưa ra trò chơi sau đây với các con số. Hãy lấy một số tự nhiên lẻ $N$ và biểu diễn nó dưới dạng tổng của hai số hạng. Đối với mỗi phân vùng $N$ thành tổng có dạng $p+q$, trong đó $p < q$, chúng ta tạo một phân vùng mới có dạng $(2p) + (q-p)$. Điều gì xảy ra nếu bạn tiếp tục quá trình này? Ví dụ: chia số $17 = 1 + 16$ sẽ ra số nguyên

$$1 + 16 \rightarrow 2 + 15 \rightarrow 4 + 13 \rightarrow 8 + 9 \rightarrow 16 + 1.$$

Sau khi việc chia tách này được lặp lại. Tác giả gọi những chuỗi như vậy là lưới. Đây là một vòng lặp số 17 khác:

$$3 + 14 \rightarrow 6 + 11 \rightarrow 5 + 12 \rightarrow 7 + 10 \rightarrow 3 + 14.$$

Các vòng lặp được viết ra chứa tất cả các phân số của số 17 thành tổng của hai số hạng. Xin lưu ý rằng cả hai vòng đều có cùng độ dài. Đây không phải là sự trùng hợp ngẫu nhiên: tất cả các vòng lặp của số nguyên tố đều có độ dài bằng nhau. Hãy cố gắng tự mình chứng minh tuyên bố này.

V. E. Koshakov tiếp tục thực hiện một số lượng lớn các phép tính và phát hiện ra những con số có nhiều vòng lặp. Ví dụ: số 65537 có 2048 vòng. Hãy nghĩ xem điều gì sẽ xảy ra nếu bạn thay thế số đó bằng số đó trong một vòng lặp nhất định.

⟦folio 15⟧

Bàn tròn của chúng tôi

(Xem phần đầu ở trang 2)

Ở đây chúng ta đang nói về cách tính toán chuyến bay của món đồ chơi “đĩa bay” phổ biến.

D. L. Abarov. Bây giờ thực tập sinh trở thành một bộ phận của trường Đại học *, thực hiện ý tưởng của Lomonosov: “Trường đại học nên có thôi miên.” Tất nhiên, sự hỗ trợ vật chất sẽ tốt hơn so với trường học bình thường. Thật không may, cho đến nay trình độ vật chất và kỹ thuật của chúng tôi không tương ứng với trình độ giảng dạy. Ví dụ, hiện nay chúng tôi có 2 lớp học công nghệ máy tính nhưng cần 4-5 lớp. Trở thành một phần của Đại học Tổng hợp Moscow cho phép chúng tôi tận dụng tối đa tiềm năng to lớn của Trường. Một sân tập đang được thành lập để thực hành các khóa đào tạo, viết sách, xuất bản văn học - đủ loại đồ dùng dạy học, sách giải toán. Rốt cuộc, thành thật mà nói, nhiều khám phá về phương pháp luận đã biến mất.

A. A. Egorov. Người ta nói thêm rằng những năm đầu tiên trường nội trú tồn tại là thời điểm, dưới sự lãnh đạo của A. N. Kolmogorov, quá trình hiện đại hóa các chương trình toán học ở trường đã diễn ra. Và chính tại trường nội trú, những ý tưởng của Andrei Nikolaevich đã được thực hiện. Anh ấy thực sự muốn viết một cuốn sách giáo khoa cho trường nội trú. Thật không may, anh ấy không còn có thể làm được điều này nữa.

G. Sh. Friedman. Tôi là học viên của trường đầu tiên ở Novosibirsk. Nó diễn ra vào mùa hè năm 1962. Hơn 600 học sinh từ khắp nơi trên đất nước đã tập trung tại Akademgorodok. Ý tưởng về một ngôi trường như vậy đã ra đời từ những năm 30, nhưng không phải ngẫu nhiên mà nó chỉ được thực hiện vào đầu những năm 60 (thời điểm băng tan) - và ở Siberia (xa Moscow). Trường học kéo dài 45 ngày! Giáo viên - nhân viên trẻ của Chi nhánh Siberia của Viện Hàn lâm Khoa học Liên Xô, nghiên cứu sinh,

*) Vào tháng 10 năm 1988, một nghị định của Hội đồng Bộ trưởng Liên Xô đã được ban hành về việc tổ chức các chuyên ngành của các trung tâm giáo dục tiểu học của các trường đại học quốc gia Moscow và Novosibirsk, trong đó bao gồm các chuyên ngành tương ứng của các trường nội trú.

Sinh viên NSU - tập hợp người thay thế. Các bài giảng được trình bày bởi ban tổ chức của trường, các học giả M. A. Lavrentyev, G. I. Budker, và thành viên tương ứng của Viện Hàn lâm Khoa học Liên Xô A. A. Lyapunov. Bọn trẻ chuyển đi, tan học... Chúng tôi nghĩ: có nên đưa chúng về không? M.A. Lavrentiev đã chấp nhận ý tưởng này và tán thành nó. Chúng tôi đã tìm thấy giá trị và cách thức tài trợ. Và thế là, vào tháng 1 năm 1963, chúng tôi bắt đầu theo học tại Trường Vật lý và Toán học của NSU.

Giám đốc khoa học đầu tiên của trường là A. A. Lyapunov. Chúng tôi dạy xuất sắc không chỉ toán và vật lý mà còn cả sinh học (ngôi trường duy nhất trong cả nước nghiên cứu về di truyền học!). Một tạp chí về lãnh đạo được xuất bản và một câu lạc bộ tạo dáng được vận hành. A. A. Lyapunov, ngoài các khóa học toán, còn dạy một khóa học thú vị, “Khoa học Trái đất”, do chính ông phát minh ra. Tại nhà, ông tổ chức các lớp học theo vòng tròn về lý thuyết tập hợp, sau giờ học, trong bữa trà, có những cuộc trò chuyện về mọi thứ: khoa học, âm nhạc, hội họa, văn học.

V. N. Dubrovsky. Tôi học ở trường nội trú vào năm 1965-67, và vào năm 1969, khi còn là sinh viên, tôi bắt đầu đi dạy. Tinh thần của những năm đầu tiên đến trường được ghi nhớ một cách vô cùng hài lòng. Giảng viên và giáo viên yêu thích của chúng tôi A.V. Sosinsky dạy chúng tôi không chỉ toán mà còn cả tiếng Anh. Hầu hết các bài học toán đều được dạy bằng tiếng Anh. Tôi nhớ những buổi tối “Đèn xanh”: tại họ Yu. A. Kim và E. V. Gaidukov đọc những bài thơ của những người theo chủ nghĩa Tượng trưng, ​​“The Master and Margarita,” Gumilyov, Balmont. Và những bài học văn của N.I. Gerasimov - dưới ảnh hưởng của ông, chúng tôi đọc rất say mê, bất chấp các lớp học toán rất chuyên sâu. Những bài học lịch sử của R. A. Ostroy thực sự hấp dẫn. Kiến thức khổng lồ của cô ấy, cách tiếp cận tiêu chuẩn, phần giới thiệu về văn học lịch sử (ví dụ, “Napoléon” của E.V. Tarle) đã mang lại cho chúng tôi rất nhiều điều: chúng tôi biết lịch sử tốt hơn nhiều so với những sinh viên tốt nghiệp các trường đào tạo.

⟦folio 17⟧

"Đá bông"
và các bộ phận riêng của bộ cộng hưởng

Ở vùng lân cận Baku, nơi bắt đầu sa mạc đá Kobystan - "Đất nước của khe núi" - có một hòn đá đáng kinh ngạc. Anh ấy trở nên nổi tiếng đến mức thậm chí còn có tên riêng của mình - Nagaradash, tức là “Stone tambourine” (nagara là một loại nhạc cụ gõ của Azerbaijan, dash là một hòn đá). Khối đá này có đặc tính âm học vượt trội. Nếu bạn dùng một hòn đá đập vào nó (và tất cả những người ở gần đó tiếp tục việc này một cách vô cùng vui vẻ), thì một âm thanh to và rõ ràng sẽ phát ra đến mức dường như họ đã chạm vào một chiếc chuông hay...

Chúng ta hãy thử mô tả các đặc tính âm thanh của đá pyosh đá bằng ngôn ngữ vật lý. Rõ ràng là còn quá sớm trong trường hợp này để nói về tần số mà hòn đá phát ra. Chúng ta hãy xem một phần dao động của âm thanh $f$ có liên quan như thế nào đến kích thước của “tambourine” $l$.

Khi va chạm, đá sẽ bị biến dạng trong thời gian ngắn và sóng âm sẽ lan truyền theo mọi hướng kể từ điểm va chạm. Chúng chạy với tốc độ nhất định $v$, không phụ thuộc vào kích thước của viên đá. Nhưng sóng chỉ lan truyền liên tục trong một môi trường đồng nhất vô biên và tất cả các vật thể đều có ranh giới nơi chất này tiếp xúc với chất khác (trong trường hợp của chúng ta là một hòn đá bị va chạm). Khi đạt đến ranh giới, sóng thâm nhập một phần vào môi trường khác (âm thanh từ đá xuyên qua tác động, sau đó đến tai chúng ta) và bị phản xạ một phần trở lại. Sự khác biệt về tốc độ âm thanh ở hai môi trường càng lớn thì khả năng phản xạ của nó càng hiệu quả. Ở đá granite là $v \approx 4 \cdot 10^3$ m/s, khi va chạm là $v \approx 3,3 \cdot 10^2$ m/s nên chỉ một phần nhỏ năng lượng âm thanh phát ra khi va chạm, còn phần chính của nó phải bị “cấm” bên trong đá. (Âm thanh cũng có thể phát ra từ đất đá, nhưng một “hòn đá cồng kềnh” nằm trên những tảng đá khác có “kết nối âm thanh” yếu với đất - nó chỉ tiếp xúc với đất ở một vài điểm.)

Những vật thể như vậy, trong đó năng lượng rung động được sử dụng nhanh chóng, được gọi là bộ cộng hưởng (từ tiếng Latin resonо - tôi phát âm là đáp số, tôi đáp lại). Nếu các dao động trong bộ cộng hưởng bị tắt dần yếu thì bộ cộng hưởng được cho là có hệ số chất lượng cao.

Tuy nhiên, chúng ta hãy quay lại những gì xảy ra bên trong “viên đá puosh” sau cú va chạm. Các sóng âm thanh được phản xạ nhiều lần từ các bức tường và giao thoa với nhau, bị hấp thụ hoặc bị suy yếu lẫn nhau. Sự gia tăng dao động xảy ra khi một sóng sau khi trải qua một hoặc nhiều phản xạ, quay trở lại một điểm nhất định trong cùng pha mà đường đi của nó bắt đầu. Xét rằng thời gian để sóng truyền qua lại dọc theo vật truyền âm là khoảng $2l/v$, ta thu được điều kiện khuếch đại dao động: $2l/v \approx nT=n/f$ ($n=1, 2, 3, ...$ là số nguyên). Từ đó tuân theo công thức tính tần số, được gọi là tần số tự nhiên của bộ cộng hưởng:

$$f_n \approx \frac{v}{2l} n.$$

Với $n=1$, chúng ta nhận được phần đóng đinh, hoặc như chúng ta nói, phần chính $f_1 \approx v/2l$.

Câu hỏi có thể nảy sinh: tại sao đẳng thức trong công thức (1) lại gần đúng mà không chính xác? Điều này thật dễ hiểu nếu chúng ta nhớ rằng chúng ta đã biểu thị “kích thước” của bộ cộng hưởng bằng chữ cái $l$.

⟦folio 18⟧

Điều này có ý nghĩa gì đối với một “viên đá mịn” không rõ ràng lắm - chiều dài hoặc chiều cao. Để viết được công thức chính xác cho phần thích hợp của chất cộng hưởng, bạn cần biết công thức của nó.

Ví dụ, chúng ta hãy xem xét bộ cộng hưởng "một chiều" đơn giản nhất - một sợi dây mỏng được kéo căng. Ở đây, câu hỏi $l$ là gì không nảy sinh - đó là độ dài của sợi dây giữa các đầu cố định của nó. Do đó, đẳng thức gần đúng (1) trong trường hợp chuỗi trở nên chính xác.*)

Trong tương lai, chúng ta cũng sẽ cần một công thức tính tần số tự nhiên của bộ cộng hưởng “hai chiều” - một lớp vỏ hình cầu mỏng có bán kính $R$:

$$f_n = \frac{v}{2\pi R} \sqrt{n(n+1)}.$$

Công thức này tương tự như công thức trước: đường đi đầy đủ của sóng trong chuỗi từ đầu này đến đầu kia và ngược lại, bằng $2l$, được thay thế trong trường hợp hình cầu bằng chiều dài của màn hình $2\pi R$. Với cộng hưởng ba chiều (thể tích), tình huống phức tạp hơn một chút và ở đây chúng tôi sẽ chỉ trình bày biểu thức cho phần chính của dao động âm thanh tự nhiên của một quả bóng có bán kính $R$:

$$f_1 \approx 0.33 \frac{v}{R}.$$

Rõ ràng là trong trường hợp này, $f_1$ khác rất ít so với giá trị gần đúng của giá trị gần đúng này (1), nếu chúng ta tính $l=R$ và $n=1$ trong giá trị sau.

Bộ cộng hưởng có thể phát ra âm thanh ở các tần số khác nhau

Trong các công thức được viết ở trên, số nguyên $n$ xuất hiện. Mặc dù người ta không biết nó bằng bao nhiêu, nhưng không thể nói các dao động sẽ được tạo ra ở tần số nào (hoặc ở tần số nào). Nó phụ thuộc vào nguồn cung cấp năng lượng cho bộ cộng hưởng. Trong quá trình kích thích ngắn hạn (tác động), năng lượng âm thanh được phân phối giữa các tần số của chính nó,

*) Tất nhiên, giá trị của $f_n$ phụ thuộc vào đường kính của dây, tính chất của vật liệu và lực căng. Nhưng tất cả các phần phụ thuộc này đều được bao gồm trong $v$, vì vậy chúng tôi đang xem xét các chuỗi có độ dài khác nhau.

hoặc các hòa âm sẽ phát ra đồng thời (toàn bộ $n$ xuất hiện trong công thức (1). Hòa âm nào mạnh hơn và hòa âm nào yếu hơn tùy thuộc vào vị trí tác động. Do đó, bằng cách nhấn “đá đẩy” ở những vị trí khác nhau, bạn có thể trích xuất một giai điệu nhất định từ đó, tức là Nagaradash “hoạt động” giống như một nhạc cụ thực sự!

Tình huống hoàn toàn khác nếu bộ cộng hưởng bị kích thích không phải bởi một cú sốc ngắn hạn mà bởi một máy rung điều hòa hoạt động liên tục (một nguồn sóng hình sin). Trong trường hợp này, các dao động sẽ xảy ra ở tần số kích thích $f$, tần số này có thể khác với tất cả $f_n$. Tuy nhiên, khi $f$ trùng với một trong các tần số tự nhiên thì biên độ dao động tăng mạnh. Đây là bản chất của hiện tượng cộng hưởng.

Trái đất “rung chuông” ở tần số nào?

Từ một “hòn đá bông xốp” có kích thước vài mét, người ta có thể dễ dàng chuyển suy nghĩ của mình đến một tảng đá khổng lồ và thậm chí xa hơn - đến toàn bộ Trái đất nói chung. Thật thú vị khi tìm hiểu xem bộ cộng hưởng có thể “phát ra âm thanh” ở tần số nào trên toàn cầu, tức là bao phủ toàn bộ hành tinh và những nguồn nào có khả năng tạo ra nó.

Quả địa cầu, có cấu trúc bên trong phức tạp, cũng được bao quanh bởi bầu khí quyển, các lớp trên của nó (không phải tầng) có độ dẫn điện cao. Khi tính đến tất cả những điều này, chúng ta có thể mong đợi sự xuất hiện của ba loại cộng hưởng toàn cầu. Hai trong số chúng liên quan đến các rung động cơ học bên trong Trái đất và trong bầu khí quyển của nó, và thứ ba là với sóng điện từ trong khoảng trống giữa bề mặt Trái đất và tầng điện ly. Sự tương ứng Có ba chuỗi tần số tự nhiên của cộng hưởng toàn cầu, có thể được ước tính bằng các công thức trên.

Hãy bắt đầu với những rung động cơ học bên trong Trái đất. Theo số liệu hiện nay, tốc độ của âm thanh (sóng địa chấn) trong lòng trái đất là

⟦folio 19⟧

Mỗi trận động đất được đặc trưng bởi dấu hiệu riêng trên địa chấn đồ, nhưng ở các tần số nhất định, giống nhau đối với tất cả các trận động đất, các đỉnh cộng hưởng được quan sát thấy. cho thấy sự kích thích của sự rung động của Trái đất.

sẽ tan chảy với độ sâu từ 4-8 km/s ở bề mặt Trái đất đến 7-13 km/s ở ranh giới dưới của lớp phủ.*) Tại địa chỉ, tốc độ âm thanh lại giảm. Để ước tính tần số dao động địa chấn tự nhiên chính (thấp nhất) của Trái đất, chúng ta sẽ sử dụng công thức (3), đặt vào đó $v \approx 6$ km/s và $R = 6400$ km. Do đó, chúng tôi tìm thấy $f_1 \approx \frac{0,33 \cdot 6}{6,4 \cdot 10^3} \approx 3 \cdot 10^{-4}$ Hz và khoảng thời gian tương ứng là $T_1 \approx 55$ phút.

Tất nhiên, không thể nghe thấy “tiếng nói của Trái đất” do tần số rất thấp, nhưng nó sẽ tự biểu hiện trên băng ghi địa chấn nếu chỉ tìm thấy nguồn kích thích đủ mạnh. Vì thế có động đất và nổ. Mỗi trận động đất được đặc trưng bởi “chữ viết tay” riêng trên địa chấn đồ, nhưng vào đầu những năm 60 của thế kỷ chúng ta, người ta phát hiện ra rằng ở một số tần số (giống nhau đối với tất cả các trận động đất!) Các đỉnh cộng hưởng được quan sát thấy, cho thấy sự kích thích các dao động của Trái đất. Các khoảng thời gian tương ứng là 54; 35,5; 25,8; ... phút, không mâu thuẫn với các ước tính về tần số cơ bản $f_1$ theo công thức (3) (mặc dù công thức sau, có tính đến cấu trúc phức tạp của Trái đất).

Có thể lấy thứ tự ước tính cường độ của tốc độ lan truyền IGW từ các báo cáo thứ nguyên.

*) Sóng âm (địa chấn) gồm hai loại (dọc và ngang) có thể truyền trong lòng Trái đất với tốc độ khác nhau.

Lee, rất gần đúng). Sự rung động của Trái đất phân rã tương đối chậm. Chỉ cần nói rằng việc ghi lại lâu dài trên địa chấn đồ sau trận động đất có thể kéo dài vài phút và mười phút, mặc dù bản thân sự kiện - một trận động đất, một vụ nổ - kéo dài vài giây hoặc thậm chí một phần giây. Việc phát hiện các dao động của Trái đất là một trong những thành tựu lớn nhất của địa vật lý hiện đại. Với sự trợ giúp của cộng hưởng toàn cầu, dữ liệu thực nghiệm và tính toán có thể so sánh, tính chính xác của một số mô hình cấu trúc bên trong hành tinh của chúng ta đã được xác minh.

Bầu khí quyển của Trái đất cũng là một thiết bị cộng hưởng

Phần lớn toàn bộ khối lượng không khí trong khí quyển được chứa trong một lớp có độ dày ~6 km và nếu bạn tăng lên độ cao 30 km thì ~99% toàn bộ bầu khí quyển vẫn có thể nhìn thấy được. Vì vậy, chúng ta có thể nói một cách có điều kiện về “biên giới” của khí quyển. Hãy tưởng tượng rằng ở một nơi nào đó, “biên giới”, dưới tác động của một số lực nhất định, tăng lên một chút, sau đó lực đó không còn tác dụng nữa. Lực hấp dẫn sẽ đẩy “cái bướu” đã nhô lên trở lại, nhưng cái đã nhô lên, di chuyển theo quán tính, sẽ chìm xuống thấp hơn nữa, và một “cái rỗng” sẽ xuất hiện ở vị trí của “cái bướu”. Sự dao động về độ dày của khí quyển lan truyền theo mọi hướng từ vị trí nhiễu loạn ở dạng sóng tương tự như sóng quan sát được trên bề mặt đại dương. Nhưng vì không có ranh giới rõ ràng của khí quyển nên các rung động giống như sóng bao phủ toàn bộ độ dày của nó, chúng được gọi là sóng granit bên trong (IGW)*.

Có thể lấy thứ tự ước tính cường độ của tốc độ lan truyền IGW từ các báo cáo thứ nguyên.

*) Từ “hấp dẫn” trong trường hợp này chỉ ra rằng các sóng này chỉ có thể lan truyền trong trường hấp dẫn (không giống như sóng âm). Trong vật lý, thuật ngữ tương tự được sử dụng theo một nghĩa hoàn toàn khác: đây là tên của sóng granit truyền đi với tốc độ ánh sáng thông qua những thay đổi của trường hấp dẫn trong chân không.

⟦folio 20⟧

Công thức mong muốn phải bao gồm gia tốc trọng trường $g$ ($\text{m/c}^2$) và mô tả thang đo $H$ ($\text{m}$) của sự thay đổi mật độ không khí theo chiều cao. Từ hai đại lượng này, số ba được tạo thành duy nhất, có thứ nguyên là tốc độ $v$ ($\text{m/c}$): $v \sim \sqrt{gH}$. Vì $g \approx 10 \text{ m/c}^2$ và $H \approx 10 \text{ km}=10^4 \text{ m}$, chúng ta nhận được $v \sim 300 \text{ m/c}$. IGW suy giảm rất yếu và không giống như sóng âm thanh, chúng có thể bay vòng quanh địa cầu nhiều lần. Sóng chu vi trong khí quyển (chúng được ghi lại bằng phong vũ biểu) lần đầu tiên được phát hiện vào năm 1883 sau vụ nổ núi lửa mạnh trên đảo Krakatay ở Indonesia. Vụ thiên thạch Tunguska rơi vào năm 1908 cũng kéo theo những hiện tượng tương tự.

Độ dày của khí quyển rất nhỏ so với bán kính Trái đất nên có thể sử dụng công thức (2) để ước tính tần số tự nhiên của cộng hưởng khí quyển toàn cầu. Với giá trị trên $v$ ta tìm được tần số $f_1 \sim 10^{-5}$ Hz và chu kỳ tương ứng $T_1 \sim 30$ h. Tất nhiên, đây chỉ là một mức độ ước tính độ lớn, nhưng theo đó, để xảy ra sự cộng hưởng, cần có một nguồn có thể làm rung động toàn bộ độ dày của khí quyển với khoảng thời gian khoảng mười giờ. Lực thủy triều tác động lên bầu khí quyển ở các bang Lunya và Mặt trời bị chi phối theo cách này.*) Mọi người đều biết về thủy triều ở biển và đại dương, nhưng điều này không chỉ được quan sát thấy ở những vùng nước rộng lớn. Có những thăng trầm cả trong quả bóng vỏ rắn, mặc dù độ cao của sóng thủy triều ở đây rất nhỏ (ở vĩ độ Moscow là ~ 40 cm) và trong vỏ không khí, ngược lại, biên độ của trọng lượng là đáng kể.

Trước tiên hãy nhìn vào thủy triều mặt trời. Tác động của lực hấp dẫn của Mặt trời lên khí quyển (cũng như trên nước và trên lớp vỏ rắn) dẫn đến thực tế là dọc theo đường nối

*) Bạn có thể đọc về sự lên xuống của thủy triều trong bài viết “Lunar Hormosis” của L. G. Aslamazov trên tạp chí “Kvat” số 8 năm 1987.

tâm Trái Đất và Mặt Trời xuất hiện hai bướu thủy triều, theo phương ngang có hai vùng trũng (thủy triều thấp). Giả sử rằng tại thời điểm ban đầu chúng ta đang ở nơi thủy triều cực đại - tại điểm 1 (xem hình). Sau 6 giờ, do Trái đất tự quay hàng ngày, điểm 1 sẽ chuyển sang điểm 2 và người ta sẽ quan sát thấy điểm suy thoái mạnh nhất ở đó, do các bướu thủy triều không thay đổi trên đường Mặt trời-Trái đất. Sau 6 giờ nữa, điểm 2 sẽ chuyển sang điểm 3, nơi thủy triều lại đạt mức tối đa. Do đó, sự biến dạng thủy triều của bầu khí quyển liên quan đến Mặt trời có chu kỳ $T_\odot=12$ giờ. Mặt trăng cũng tác động lên bầu khí quyển theo cách tương tự, nhưng do nó tự quay quanh Trái đất, nên sẽ phát sinh một khoảng thời gian biến dạng thủy triều hơi khác - $T_2 \approx 12,4$ giờ. Vì Mặt trăng ở gần Trái đất hơn Mặt trời rất nhiều nên lực thủy triều liên quan đến nó, theo tính toán, phải mạnh hơn 2,5 lần so với lực thủy triều của Mặt trời.

Đối với thủy triều, kết luận này được khẳng định rõ ràng trong thực tế. Tuy nhiên, các thủy triều quan sát được trong khí quyển (đặc biệt, chúng biểu hiện dưới dạng dao động định kỳ đều đặn của áp suất khí quyển ở vùng nhiệt đới với biên độ ~ 2 mm Hg) cho thấy biên độ của thủy triều “mặt trời” (với chu kỳ 12 giờ) lớn hơn khoảng 16 lần so với thủy triều “mặt trăng”. Do đó, tỷ lệ biên độ quan sát được của hai nhiễu loạn thủy triều trong khí quyển (mặt trời và mặt trăng) khác với tỷ lệ tính toán tới 40 lần! Sự khác biệt lớn như vậy cho thấy thiếu một điều gì đó thiết yếu trong lý luận lý thuyết.

Giả thuyết giải thích sự chiếm ưu thế của thủy triều trong khí quyển mặt trời lần đầu tiên được đưa ra vào cuối thế kỷ trước bởi nhà vật lý người Anh W. Thomson (sau này ông nhận được danh hiệu Lord Kelvin). Bản chất của nó là như sau. Nếu chu kỳ dao động của khí quyển chính xác là 12 giờ thì tác dụng của lực thủy triều mặt trời (với chu kỳ 12 giờ) sẽ dẫn đến

⟦folio 21⟧

cộng hưởng - biên độ dao động của khí quyển tăng mạnh. Những ước tính rất sơ bộ của chúng tôi về $T_1$ không phù hợp để kiểm tra giả thuyết cộng hưởng, vì vậy chúng tôi nên chuyển sang dữ liệu thực nghiệm. Chu kỳ dao động của khí quyển tự nhiên được xác định dựa trên các quan sát về các sóng áp suất trên toàn thế giới phát sinh sau vụ nổ của núi lửa Krakatoo và sự sụp đổ của thiên thạch Tunguska mà chúng tôi đã đề cập. Khoảng thời gian $T_1$ tìm được theo cách này hóa ra bằng 10,5 giờ. Giá trị này không mâu thuẫn với ước tính sơ bộ của chúng tôi $T_1$ về bậc độ lớn, nhưng hoàn toàn không mâu thuẫn với giả định về cộng hưởng. Có vẻ như giả thuyết cộng hưởng nên bị loại bỏ. Nhưng vào cuối những năm 30 của thế kỷ chúng ta, nó lại được hồi sinh, trong một phiên bản phức tạp hơn.

Đặc điểm chính của lý thuyết mới là giả định hai chu kỳ dao động tự nhiên của khí quyển: $T_{1\text{н}}=10,5$ h đối với các lớp bên dưới và $T_{1\text{в}}=12$ h đối với các lớp trên (trên ~50 km). Nếu điều này thực sự đúng thì người ta có thể tưởng tượng rằng các vụ nổ trên bề mặt Trái đất là do dao động khí quyển trong thời gian ngắn gây ra, và thủy triều bao phủ toàn bộ độ dày của khí quyển là do dao động trong thời gian dài gây ra. Tuy nhiên, các giám mục cấp dưới và cấp trên cách ly nhau như thế nào? Vai trò của rào cản giữa chúng có thể được thực hiện bởi một lớp không khí có nhiệt độ cao, lớp này truyền IGW lên trên một cách yếu ớt và không truyền các sóng bắt nguồn từ phía trên.

Các tính toán cho thấy chu kỳ dao động kéo dài 12 giờ ở tầng trên của khí quyển có thể xảy ra nếu nhiệt độ không khí ở độ cao 50-60 km đạt 320-340 K. Sau mức tối đa này, nhiệt độ giảm xuống và bắt đầu từ độ cao 80-100 km, nhiệt độ lại tăng lên. Những thay đổi được chấp nhận bắt đầu nảy sinh cùng với sự ra đời của các gói khí tượng đã xác nhận sự hiện diện của mức tối đa được dự đoán! Tuy nhiên, sự tăng nhiệt độ hóa ra không đáng kể ($T_{\text{макс}} \approx 270—280$ K) như lý thuyết cộng hưởng cho thấy.

Như vậy, lý thuyết được quan sát định kỳ do sự thay đổi của các thông số khí quyển cho đến khi hoàn thiện hoàn toàn.

Cộng hưởng điện từ toàn cầu

Dưới tác động của bức xạ mặt trời ở các tầng trên của khí quyển, các nguyên tử và phân tử bị ion hóa, xuất hiện các điện tích tự do và độ dẫn điện của không khí, bắt đầu từ độ cao 50-60 km, tăng lên rất nhiều. Đây là nơi tầng điện ly bắt đầu, ở khoảng cách lớn so với Trái đất, “đóng lại” với không gian liên hành tinh. Các tầng thấp hơn của khí quyển, dày vài chục km, có sóng điện từ (sóng vô tuyến) rất thấp. Tần số tự nhiên của cộng hưởng hình cầu này là gì? Đáp số được biểu thị bằng công thức (2), nhưng với tốc độ âm thanh $v$ được thay thế bằng tốc độ ánh sáng $c=3 \cdot 10^8$ m/s. Kết quả là tập hợp tần số tự nhiên của cộng hưởng điện từ toàn cầu sau đây:

$$f_n = \frac{3 \cdot 10^8 \cdot \sqrt{n(n+1)}}{2 \cdot 3,14 \cdot 6,4 \cdot 10^6} \approx 10,6; 18,3; 25,9; \dots$$

Nguồn phản hồi cộng hưởng chính là sét. Trên mọi thứ

⟦folio 22⟧

Trên phổ nhiễu điện từ không có cực đại nhìn thấy được tương ứng với tần số tự nhiên của tầng điện ly cộng hưởng điện từ toàn cầu.

Hàng nghìn cơn giông đang hoành hành trên toàn cầu vào bất kỳ thời điểm nào, với trung bình khoảng 100 tia sét mỗi giây. Sau mỗi lần phóng điện, bộ cộng hưởng tầng điện ly Trái đất “rung” như một chiếc chuông ở tần số riêng của nó. Nhưng trước khi tiếng chuông này có thời gian lắng xuống, lần phóng điện tiếp theo xảy ra và các rung động lại xuất hiện. Do tia sét xảy ra ngẫu nhiên nên chuỗi liên tục của chúng kích thích nhiễu điện từ trong bộ cộng hưởng, có thể dễ dàng phát hiện bằng thiết bị thu đơn giản bao gồm ăng-ten, bộ khuếch đại (không có máy dò) và thiết bị ghi âm. Sau này, một máy phân tích phổ được sử dụng, cho phép người ta xác định biên độ của dao động điện từ ở các tần số khác nhau (từ đơn vị đến hàng chục Hz). Trong phổ nhiễu điện từ thu được theo cách này (xem hình), không có cực đại nhìn thấy được ở tần số tự nhiên gần với tần số được tính toán ở trên. Việc quan sát có thể được thực hiện ở bất cứ đâu trên thế giới (cộng hưởng mang tính toàn cầu), tốt nhất là

22
