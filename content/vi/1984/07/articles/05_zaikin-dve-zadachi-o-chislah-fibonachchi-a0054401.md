---
id: 1984-7-zaikin-dve-zadachi-o-chislah-fibonachchi-a0054401
issue: kvant_1984_7
year: 1984
number: "7"
title: Hai bài toán về số Fibonacci
authors:
  - Заикин М. И.
rubric: smes
page_first: 16
page_last: 19
page_labels: 14, 16, 17
tag: TLEQ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: ef03fd85b1d2d7e19a214a80c70e2bcb4893551cd6bbc433b58152a243381381
prompt_sha256: draft-1
translated_from: content/ru/1984/07/articles/05_zaikin-dve-zadachi-o-chislah-fibonachchi-a0054401.md
source_content_sha256: 388cb9e1e685c3fe7824eabb094135a9f246ce73e1b6ad32df80c84dd51b7dc8
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 14⟧

Trong trường hợp một ván cờ kết thúc, bài toán phân tích của nó có thể được giảm bớt bằng cách kiểm tra sự phân rã không phải theo thành phần của các quân cờ mà bằng các vị trí khác nhau của các quân tốt. Điều này có thể thực hiện được vì quân tốt không di chuyển lùi và không di chuyển từ hàng này sang hàng khác mà không bị bắt. Phân rã hóa ra là một kỹ thuật quyết định để đặt trò chơi cuối KLP-KL vào bộ nhớ ngoài của máy tính.

Thiếu không gian không cho phép chúng tôi nói chi tiết hơn về các kỹ thuật khác - việc sử dụng tính đối xứng, phương pháp “xử lý nhóm”, v.v. Những kỹ thuật này được thiết kế để đáp ứng các hạn chế cả về dung lượng bộ nhớ máy tính có sẵn và thời gian tính toán, cho phép chúng tôi hoàn thành việc phân tích các trò chơi có hình dạng nhỏ.

Máy chơi endgame

Tất cả điều này trông như thế nào trong thực tế? Chẳng hạn, có hai đối tác phân chia các bước đi luân phiên trong trò chơi kết thúc KLP-KL. Nhưng trong trường hợp của chúng tôi, một trong những đối tác là con người và người kia là máy tính. Kết quả của quá trình xếp hạng các vị trí được thực hiện một lần và mãi mãi là một “bảng ghi chép” được lưu trữ trong bộ nhớ của máy tính - một danh sách tất cả các vị trí cho biết thứ hạng. Ngồi vào bảng điều khiển hiển thị, một người vào vị trí và báo cáo hành động của mình. Trong máy đáp số, bằng cách sử dụng “các bảng cheat từ một, các số Fibonacci hoàn toàn không phải là số Fibonacci.

Được biết, khi các con số tăng lên thì bản thân các số Fibonacci cũng tăng lên nhanh chóng. Vì vậy, $f_1=1$, nhưng $f_{50}=12586269025$ và $f_{100}=354224848179261915075$. Tuy nhiên, chữ số cuối cùng

Coy”, tìm thứ hạng của vị trí kết quả và xem xét tất cả các nước đi từ vị trí đó cho đến khi tìm được nước đi tối ưu mà nó hiển thị trên màn hình hiển thị.

Bài toán 3 (dành cho người có nhiều thời gian). Ở vị trí từ Hình 5, họ bắt đầu giành được nhiều chiến thắng hơn.

Vị trí này được thay thế bằng thực tế là độ dài của con đường tối ưu từ nó đến việc thăng cấp một con tốt là một kỷ lục - 60 nước đi! Chúng tôi có được một chuỗi nước đi từ nó bằng cách buộc máy phải chơi cho cả hai bên.

Vậy chúng ta nên làm gì?

Vì vậy, cỗ máy đã được dạy chơi trò chơi tàn cuộc KLP-KL, không chỉ chính xác hoàn hảo mà còn rất nhanh, dành 10-15 giây cho mỗi nước đi (so sánh với luật Turin - 2 giờ cho 40 nước đi).

Tương tự như vậy, bạn có thể dạy máy tính chơi một cách tối ưu trong các tàn cuộc năm quân còn lại. Với việc sử dụng các ý tưởng mới để cải thiện thuật toán phân tích trò chơi kết thúc cũng như các máy mạnh hơn, có vẻ như các trò chơi kết thúc gồm 6-7 mảnh đang trở nên sẵn sàng để nghiên cứu. Đồng thời, các chương trình cờ vua giữa trò chơi mà chúng tôi đã nói đến chơi kém ngay cả trong các trò chơi kết thúc nhiều quân cờ (10-12 quân).

Hiện vẫn chưa biết làm thế nào để lấp đầy khoảng trống này. Có lẽ sẽ khá đơn giản để xây dựng các quy tắc ứng xử trong trò chơi cuối cùng, khuyến nghị các nước đi trống rỗng và không tối ưu nhưng gần với các nước đi tối ưu. Những quy tắc như vậy có thể được phát triển bằng cách nghiên cứu các tàn cuộc, phân tích đầy đủ về chúng đã được hoàn thành trên máy tính. Những quy tắc này cũng sẽ rất có giá trị đối với những người chơi cờ vì chúng hữu ích một cách thuận tiện hơn so với các mảng tham chiếu khổng lồ được lưu trữ trong bộ nhớ của máy.

Hai bài toán về số Fibonacci

Chứng minh các tính chất sau của số Fibonacci (xem trang 17).

1. Tích và thương của hai số khác nhau, khác nhau

Các số Fibonacci dựa trên một không phải là số Fibonacci.

Được biết, khi các con số tăng lên thì bản thân các số Fibonacci cũng tăng lên nhanh chóng. Vì vậy, $f_1=1$, nhưng $f_{50}=12586269025$ và $f_{100}=354224848179261915075$. Tuy nhiên, chữ số cuối cùng

Coy”, tìm thứ hạng của vị trí kết quả và xem xét tất cả các nước đi từ vị trí đó cho đến khi tìm được nước đi tối ưu mà nó hiển thị trên màn hình hiển thị.

Bài toán 3 (dành cho người có nhiều thời gian). Ở vị trí từ Hình 5, họ bắt đầu giành được nhiều chiến thắng hơn.

Vị trí này được thay thế bằng thực tế là độ dài của con đường tối ưu từ nó đến việc thăng cấp một con tốt là một kỷ lục - 60 nước đi! Chúng tôi có được một chuỗi nước đi từ nó bằng cách buộc máy phải chơi cho cả hai bên.

Vậy chúng ta nên làm gì?

Vì vậy, cỗ máy đã được dạy chơi trò chơi tàn cuộc KLP-KL, không chỉ chính xác hoàn hảo mà còn rất nhanh, dành 10-15 giây cho mỗi nước đi (so sánh với luật Turin - 2 giờ cho 40 nước đi).

Tương tự như vậy, bạn có thể dạy máy tính chơi một cách tối ưu trong các tàn cuộc năm quân còn lại. Với việc sử dụng các ý tưởng mới để cải thiện thuật toán phân tích trò chơi kết thúc cũng như các máy mạnh hơn, có vẻ như các trò chơi kết thúc gồm 6-7 mảnh đang trở nên sẵn sàng để nghiên cứu. Đồng thời, các chương trình cờ vua giữa trò chơi mà chúng tôi đã nói đến chơi kém ngay cả trong các trò chơi kết thúc nhiều quân cờ (10-12 quân).

Hiện vẫn chưa biết làm thế nào để lấp đầy khoảng trống này. Có thể nhận được một công việc MẶC ĐỊNH

2. Sau đúng 60 số, chữ số cuối cùng của bất kỳ số Fibonacci nào cũng được lặp lại định kỳ.

Chứng minh điều đó.

M. I. Zashchkin

⟦folio 16⟧

Trái Tim Sư Tử (1157-1199). Ở một số thành phố của Ý, ông bắt đầu xây dựng hậu cung, điều này không phù hợp với vị hoàng đế “theo đạo Cơ đốc nhất”. Ông thu hút người Ả Rập và người Do Thái chủ yếu đến giảng dạy tại Đại học Naples, cùng với các học giả Cơ đốc giáo. Hơn nữa, có tin đồn cho rằng ông là tác giả của cuốn sách nhỏ vô thần “Về ba kẻ lừa dối”, có nghĩa là Monsey, Christ và Mohammed.

Những chuyến du lịch của hiệp sĩ, được ông rất yêu thích, trong đó các lính canh chặt xác lẫn nhau để mua vui cho công chúng, đã không được Frederick II công nhận chút nào. Thay vào đó, anh ta xây dựng các thành phố toán học hiện đại ít đẫm máu hơn (chính xác là sự giao thoa giữa tối ưu hóa toán học và KBH), trong đó các đối thủ trao đổi không phải những đòn kiếm mà là các nhiệm vụ.

Chính tại những giải đấu như vậy, tài năng của Leonardo Fibonacci đã tỏa sáng. Điều này được tạo điều kiện thuận lợi nhờ sự giáo dục tốt do thương gia Bonacci trao cho con trai ông, người đã đưa cậu theo về phía Đông và giao cho cậu những giáo viên Ả Rập. Sau đó, Fibonacci nhận được sự bảo trợ liên tục của Frederick II. Sự bảo trợ này đã tạo điều kiện thuận lợi cho Leonardo thực hiện các chuyến đi buôn bán xa hơn tới Bắc Phi, Ai Cập, Syria và Byzantium, trong thời gian đó ông đã làm quen sâu sắc với khoa học Ả Rập và Hy Lạp. (Các tác phẩm kinh điển của khoa học cổ đại khi đó chủ yếu được biết đến qua các bản dịch tiếng Ả Rập.) Sự bảo trợ của Frederick II cũng đã kích thích việc xuất bản các chuyên luận khoa học của Fibonacci: “Sách bàn tính” tổng quát (1202, phiên bản sửa đổi và mở rộng, 1228), “Thực hành hình học” (1220), “Sách hình vuông” (1225). Sử dụng những cuốn sách này, vượt qua các tác phẩm tiếng Ả Rập và châu Âu thời trung cổ về trình độ, toán học đã được dạy cho đến thời Descartes (thế kỷ XVII) và Euler (thế kỷ XVIII).

Bản chất của tất cả các cuốn sách của Leonardo là nguồn gốc của chúng từ các chuyến tham quan toán học. Vai trò chính trong đó do nhiều lời giải đóng và nhận xét bài toán - đôi khi là những điều được đề xuất trong các chuyến lưu diễn bởi chính Leonardo hoặc đối thủ chính của ông, một người gốc trong gia đình thương gia ngớ ngẩn Johann của Palermo, triết gia triều đình của Frederick II. Chúng ta cũng hãy lưu ý rằng bàn tính là một phương pháp đếm cổ xưa, giống như bàn tính của Nga. Tuy nhiên, “Sách bàn tính” không dành cho việc thực hành đếm mà dành cho số học lý thuyết theo nghĩa rộng của thuật ngữ này. Đặc biệt, thông qua cuốn sách này, người châu Âu đã làm quen với các chữ số Ả Rập (chính xác hơn là Ấn Độ) và hệ thống ghi số hiện đại. Tương tự như vậy, “Thực hành Hình học” không dành cho hình học ứng dụng (khảo sát) mà dành cho hình học lý thuyết.

Để mô tả thành tích của Leonardo, chỉ cần nhắc đến hai trong số bài toán mà ông đã giải là đủ: tìm ba số x, y và z sao cho tổng của chúng, tăng cả x² và x²+y² và x²+y²+z², sẽ là một số chính phương (Leonardo's lời giải: x=16/5, y=48/5 và z=144/5) và đặc biệt là bài toán o lời giải phương trình bậc ba x³+2x²+10x=20. Leonardo chứng minh rằng nghiệm của phương trình này không thể biểu diễn bằng căn bậc hai (“bằng chứng về tính bất khả thi” đầu tiên trong toán học châu Âu sau các định lý cổ xưa về tính vô tỉ của √2 và các số khác), rồi tính nghiệm của phương trình với sai số không quá 0,00000000003 (độ chính xác tuyệt vời).

Nhưng trong tất cả những thành tựu của Leonardo, nhân loại vô ơn ngày nay chỉ nhớ đến bài toán sau đây từ “Sách bàn tính”:

“Có người đặt một cặp thỏ ở một nơi nào đó, có rào chắn bốn phía, nhằm tìm hiểu xem trong năm sẽ có bao nhiêu cặp thỏ sinh ra, nếu tính chất của thỏ là trong một tháng một cặp thỏ sẽ sinh ra một cặp khác, và từ tháng thứ hai sau khi sinh ra sẽ sinh ra một con thỏ”.

Rõ ràng là nếu coi cặp thỏ đầu tiên là thỏ sơ sinh (Leonardo không đưa ra giả định này, tuy nhiên điều này ít ảnh hưởng đến kết quả), thì đến tháng thứ 2 chúng ta vẫn sẽ có 1 cặp; vào tháng thứ 3 - 1 + 1 = 2; vào ngày thứ 4 - 2 + 1 = 3 cặp (và trong số hai cặp có sẵn, con của ngày chỉ có một cặp); vào ngày thứ 5 - 3 + 2 = 5 cặp (chỉ có hai cặp sinh vào tháng thứ 3 sinh con vào tháng thứ 5); vào tháng thứ 6 - 5 + 3 = 8 cặp (vì chỉ những cặp sinh vào tháng thứ 4 mới sinh con), v.v. Do đó, nếu chúng ta chỉ định số lượng cặp

⟦folio 17⟧

thỏ có ở vị trí thứ $n$ đến $f_k$, rồi $f_1=1, f_2=1, f_3=2, f_4=3, f_5=5, f_6=8$, v.v. và việc hình thành các số này được quy định bởi một quy luật chung:

$$f_n=f_{n-1}+f_{n-2}$$ cho tất cả $n>2$ (1)

- xét cho cùng, số cặp thỏ $f_n$ ở vị trí thứ $n$ bằng số cặp thỏ ở vị trí thứ $f_{n-1}$ sau số cặp thỏ mới sinh ra, trùng với số cặp thỏ $f_{n-2}$ sinh ra ở vị trí thứ $(n-2)$ (chỉ những cặp thỏ này mới sinh con).

Các số $f_n$ tạo thành dãy 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, 233, 377, ..., được gọi là số mới và có nhiều tính chất đáng ngạc nhiên. Hãy liệt kê một số trong số họ. Người đọc có thể xem bằng chứng của họ dưới dạng bài toán:

1. $f_1+f_2+\dots+f_n=f_{n+2}-1$.
2. a) $f_1+f_3+f_5+\dots+f_{2n-1}=f_{2n}$,
6) $f_2+f_4+f_6+\dots+f_{2n}=f_{2n+1}-1$.
3. $f_1^2+f_2^2+\dots+f_n^2=f_nf_{n+1}$.
4. a) $f_{2n}=f_{n+1}^2-f_{n-1}^2$,
6) $f_{3n}=f_{n+1}^3+f_n^3-f_{n-1}^3$.
5. $f_n^2=f_{n-1}f_{n+1}-(-1)^n$.
6. $f_{n+m}=f_{n-1}f_m+f_nf_{m+1}$.
7. $f_n$ chẵn ⇔ chia hết cho 3.
8. $f_n$ chia hết cho 7 ⇔ chia hết cho 8.
9. $f_n$ chia hết cho $f_m$ ⇔ $n$ chia hết cho $m$.

Danh sách này có thể được tiếp tục. Bạn đọc quan tâm sẽ tìm thấy nhiều điểm hay khác (tính chất của số $f_n$) trong các cuốn sách phổ biến có tên ở cuối bài, một phần trong các tài liệu quảng cáo và sách thay thế của N. N. Vorobyov. Hai tài sản nữa được M.I. gửi đến «Kvant». Zankin có thể được xem trên trang. 14 của con số này.

Mối quan hệ lặp lại (1) giúp dễ dàng tính toán tuần tự các số $f_1, f_2, f_3, \dots$. Nhưng có biểu thức rõ ràng nào cho tổng số $f_n$ của dãy Fibonacci mà không yêu cầu kiến ​​thức về các số hạng trước đó không? Ngoài ra còn có một điều hoàn toàn bất ngờ. Thẩm phán cho chính mình:

$$f_n=\frac{1}{\sqrt{5}}\left[\left(\frac{1+\sqrt{5}}{2}\right)^n-\left(\frac{1-\sqrt{5}}{2}\right)^n\right].$$

Phân tích chi tiết về bằng chứng có sẵn trong Vorobyov, cũng như trong tài liệu quảng cáo của A. I. Markushevich, đọc trong danh sách tài liệu tham khảo; xem thêm «Kvant» 1982, số 1, tr. 19.

Sự phổ biến của số Fibonacci đặc biệt tăng lên trong những năm gần đây, gắn liền với những thay đổi nhất định trong toán học, đặc biệt là tầm quan trọng ngày càng tăng của tổ hợp và các bài toán liên quan đến số nguyên. Một vai trò nổi bật ở đây là sự xuất hiện bất ngờ của các số Fibonacci trong một số nghiên cứu quan trọng gần đây, chẳng hạn như những nghiên cứu về những con số này không liên quan đến nhau. Trước hết, chúng tôi muốn nói đến lời giải giật gân của học sinh lớp Leningrad trẻ tuổi Yury Matiyasevich về cái gọi là bài toán Hilbert thứ mười*, cũng như sự xuất hiện của các số Fibonacci trong một số hướng của toán học ứng dụng (tối ưu hóa) hiện đại lấy cảm hứng từ Richard Bellman người Mỹ.

Số Fibonacci không xuất hiện ở đâu! Chúng có những ứng dụng hình học đẹp mắt, những ứng dụng quan trọng trong sinh học thực vật: ví dụ như trong việc sắp xếp lá của một số loài cây trên cành, trong cấu trúc của vảy dứa hay sắp xếp các hạt hướng dương (hiện tượng Phylotaxis; xem «Kvant», 1979, số 5, trang 53). Vấn đề về một chiến lược tự động hóa tối ưu, muốn tìm ra tốc độ ô tô có lợi nhất cho anh ta, tức là tốc độ mà nó tiêu thụ ít xăng nhất trên mỗi km đã đi, cũng dẫn đến số Fibonacci - giờ đây có thể thấy ngay mối quan hệ của những con số này với bài toán như vậy!

Bạn không thể liệt kê tất cả mọi thứ. Chúng tôi cũng sẽ đề cập đến việc phát triển một chiến lược tối ưu trong trò chơi dân gian cổ đại Yianshizi của Trung Quốc, bạn có thể đọc ở trang này. 18 của vấn đề này.

Tài liệu tham khảo

1. Vorobyov N.N. Số Fibonacci, tái bản lần thứ nhất, M. - Leningrad: Gostekhidat, 1951; Tái bản lần thứ 4, M.: Nauka, 1978.
2. Markushevich A.I. Trình tự trả về, M.: Nauka, 1979.
3. Shklyarsky D. O., Chentsov N. N., Yaglom I. I. Selected bài toán và các định lý của toán học sơ cấp (số học và đại số), M.: Nauka, 1976.
4. Dynkin E. B., Uspensky V. A. Đối thoại toán học, M. - L.: Gostekhidat, 1952.
5. Stakhov A.P. Lý thuyết thuật toán trộn, M.: Znanie, 1979.

* Xem «Kvant», 1971, số 11, tr. 31.
