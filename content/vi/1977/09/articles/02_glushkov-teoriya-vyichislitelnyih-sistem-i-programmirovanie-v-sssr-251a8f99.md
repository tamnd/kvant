---
id: 1977-9-glushkov-teoriya-vyichislitelnyih-sistem-i-programmirovanie-v-sssr-251a8f99
issue: kvant_1977_9
year: 1977
number: "9"
title: Lý thuyết về hệ thống máy tính và lập trình ở Liên Xô
authors:
  - Глушков В. М.
rubric: raznoe
rubric_sub: Разное
page_first: 6
page_last: 11
page_labels: 4-9
tag: U8H7
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 172e38311e16733d961c00da6e8752b3683785e20139d033dbd641f10be5ae6d
prompt_sha256: draft-1
translated_from: content/ru/1977/09/articles/02_glushkov-teoriya-vyichislitelnyih-sistem-i-programmirovanie-v-sssr-251a8f99.md
source_content_sha256: b211f30f484977189bc58301966c56f831ae86cef6cdc2cd34dda229676003f6
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 4⟧

Năm nay nước ta kỷ niệm 60 năm Cách mạng xã hội chủ nghĩa Tháng Mười vĩ đại. Với tư cách là Tổng Bí thư Ban Chấp hành Trung ương CPSU L.I. Brezhnev cho biết, khi trả lời câu hỏi của tổng biên tập tờ báo Asahi S. Hata, "trong 60 năm qua, nhân dân Liên Xô, dưới sự lãnh đạo của Đảng Cộng sản, đã lần đầu tiên đi trên con đường mà chúng ta tự hào. Trong vòng đời một thế hệ, tất nhiên đã có hàng thế kỷ lạc hậu. Đất nước chúng ta đã đạt đến trình độ phát triển kinh tế, khoa học và công nghệ cao. Nếu lòng tin của Nga chỉ chiếm hơn 4% sản lượng công nghiệp thế giới một chút thì ngày nay Liên Xô đã tạo ra một thứ năm trong số đó."

Bước nhảy vọt mới mà nước ta đang hướng tới trong Kế hoạch 5 năm lần thứ 10 đòi hỏi phải tăng cường hơn nữa tốc độ tiến bộ khoa học và công nghệ, vận dụng nhanh những thành tựu của cuộc cách mạng khoa học và công nghệ để nâng cao chất lượng, hiệu quả công việc ở mọi cấp độ của nền kinh tế quốc dân. Công nghệ tính toán điện tử hiện đại là một trong những yếu tố quyết định cuộc cách mạng khoa học công nghệ, trong sự tiến bộ hơn nữa của khoa học, công nghệ và sản xuất.

“Các hướng phát triển chính của nền kinh tế quốc dân Liên Xô trong giai đoạn 1976-1980” đảm bảo tăng sản lượng thiết bị máy tính lên 1,8 lần, phát triển hơn nữa việc sản xuất các tổ hợp máy tính phổ thông và điều khiển, cung cấp thêm bài toán về sự phát triển hơn nữa của các ứng dụng máy tính trong nghiên cứu khoa học, sản xuất và kinh tế.

Bản thân công nghệ máy tính, kể từ khi chiếc máy tính điện tử đầu tiên ra đời, cũng đang trong quá trình phát triển nhanh chóng. Nếu chức năng chính của máy móc thế hệ đầu tiên là thực hiện một hệ thống lệnh đơn giản thì trong các máy móc hiện đại, các thiết bị phải thực hiện một loạt chức năng mới. Trong 5 năm qua, ngành công nghiệp của chúng tôi đã chuyển sang sản xuất một hệ thống thống nhất (EC) cho máy tính thế hệ thứ ba. Việc chuyển đổi sang máy tính của EU làm thay đổi hoàn toàn việc tổ chức sử dụng công nghệ máy tính, bao gồm cả các yếu tố của tổ chức này, chẳng hạn như lập trình kỹ thuật, tổ chức dữ liệu, tổ chức quy trình tính toán, bản chất tương tác của người dùng với máy tính, v.v. Nhu cầu thay đổi dịch vụ như vậy là một giai đoạn hoàn toàn rõ ràng và tất yếu trong lịch sử của máy tính, cụ thể là quá trình chuyển đổi của chúng từ hạng mục có được các công cụ khoa học cho máy tính lời giải đặc biệt phức tạp bài toán vào danh mục công cụ phục vụ mảng (và rất đa dạng) của người tiêu dùng.

Việc cải tiến máy tính và phương pháp sử dụng chúng đòi hỏi lời giải nhiều vấn đề cụ thể mang tính chất cơ bản và thuần túy ứng dụng. Khoảng lời giải một số vấn đề liên quan đến việc tạo ra và sử dụng máy tính được thảo luận trong bài viết dưới đây của Chủ tịch Hội đồng Khoa học về Công nghệ Máy tính và Hệ thống Điều khiển của Ủy ban Nhà nước thuộc Hội đồng Bộ trưởng Khoa học và Công nghệ Liên Xô và Chủ tịch Viện Hàn lâm Khoa học Liên Xô, Viện sĩ V. M. Glushkov.

Bài toán tự động hóa các phép tính phức tạp đã thu hút được sự quan tâm của các nhà khoa học từ lâu. Tuy nhiên, chỉ khoảng 30 năm trước, nó lần đầu tiên được phát hiện đầy đủ lời giải liên quan đến việc tạo ra máy tính điện tử phổ thông - máy tính. Chúng ta sẽ xem xét sự phát triển của các hệ thống máy tính thuộc loại cụ thể này, mặc dù trong thời kỳ tồn tại trước đó đã có các thiết bị máy tính chuyên dụng, các lớp quy trình tính toán riêng biệt được tự động hóa.

Chiếc máy tính đầu tiên của Liên Xô (MESM) được tạo ra tại Viện Hàn lâm Khoa học Cộng hòa Xã hội chủ nghĩa Xô viết Ukraina ở Kyiv dưới sự lãnh đạo của học giả S. A. Lebedev vào năm 1951. Trong quá trình thành lập MESM, những nguyên tắc cơ bản mà dựa trên đó những chiếc máy tính đầu tiên của Mỹ và Anh được chế tạo, cái gọi là nguyên lý von Neumann, đã được khám phá lại một cách độc lập.

⟦folio 5⟧

Thứ nhất, đây là quốc tịch của RAM, được chia thành các ô giống hệt nhau. Mỗi ô được thiết kế để điền vào một từ máy, là một tập hợp có thứ tự gồm hai chữ số 0 và 1. Các ô nhớ được trang bị địa chỉ là các số nguyên không âm liên tiếp 0, 1, ..., n - 1; số lượng ô n là dung lượng bộ nhớ.

Nguyên tắc tiếp theo là thiết kế một đơn vị số học đặc biệt (ALU), được thiết kế để thực hiện các phép toán đơn giản trên các từ, đặc biệt là các phép toán so sánh với một số nguyên để thiết lập sự trùng khớp hoặc khác biệt của hai từ. Một lớp phép toán khác bao gồm các phép toán số học (cộng, trừ, nhân và chia) trên các từ được coi là số trong hệ thống số kép.

Ngoài ra, còn có các hoạt động trao đổi thông tin (một từ máy cho mỗi văn bản trao đổi) giữa ALU và bộ nhớ, cũng như giữa ALU và các thiết bị đầu vào/đầu ra đặc biệt. Một yếu tố quan trọng đang được xem xét là tính đơn giản và tính chất cơ bản của hệ thống vận hành máy.

Hoạt động điều khiển quá trình tính toán gắn liền với nguyên lý thứ ba của von Neumann - nguyên tắc ra lệnh và xử lý của tổ chức quản lý. Một lệnh máy bao gồm điều kiện opcode sẽ được thực thi và địa chỉ của các toán hạng (nghĩa là các từ mà thao tác được thực hiện và kết quả của thao tác đó). Ví dụ: trong phép cộng a + b = c có 3 toán hạng: a, b, c. Nếu một hoặc nhiều toán hạng được lưu trữ trong các vị trí bộ nhớ được xác định trước hoặc trong các vị trí lưu trữ đặc biệt gọi là điện trở ALU thì địa chỉ của các toán hạng tương ứng trong lệnh có thể bị bỏ qua. Ngoài ra còn có khả năng lưu trữ trong RAM không chỉ các toán hạng mà còn cả chương trình của quá trình tính toán, được biểu diễn dưới dạng một chuỗi hữu hạn các lệnh máy được viết bằng mã kép.

Các lệnh chương trình thường được đặt trong các ô nhớ tuần tự và được chọn từ nó bởi một thiết bị điều khiển đặc biệt (CU) lần lượt và sử dụng từng lệnh một. Tuy nhiên, trình tự thực hiện lệnh này có thể bị gián đoạn bởi các lệnh nhảy đặc biệt, khi địa chỉ của lệnh tiếp theo được xác định bởi lệnh điều khiển.

Nguyên tắc thứ tư là tính bất biến của cấu trúc giao tiếp giữa các thiết bị.

Cùng với những chiếc máy tính đầu tiên, lập trình bài toán cũng nảy sinh, tức là biểu diễn dưới dạng một chuỗi lệnh máy của một số quy trình tính toán nhất định hoặc các quy trình khác để chuyển đổi thông tin rời rạc (bộ từ máy).

Hãy xem xét lập trình bài toán để tìm bài toán đơn giản nhất để tìm giai thừa n! cho số tự nhiên n. Để lưu trữ toán hạng, chúng ta sẽ cần bốn ô nhớ, trong đó chúng ta sẽ chọn các ô có địa chỉ 0, 1, 2, 3. Để kiểm soát, chúng ta sẽ bỏ qua chương trình nhập dữ liệu ban đầu và giả sử rằng vào thời điểm chương trình bắt đầu, số n được lưu trong ô 0 và các đơn vị được lưu trong ô thứ nhất, thứ hai và thứ ba. Khi đó chương trình tính giai thừa sẽ được biểu diễn bằng chương trình sau (số của lệnh thông báo tiếp theo); thông qua (i) nội dung của ô có địa chỉ i được chỉ định):

4. So sánh (2) với (0) và, nếu “bằng”, thì bằng 8, nếu không thì bằng lệnh tiếp theo.
5. Cộng (3) vào (2), gửi kết quả về 2.
6. Nhân (2) với (1), gửi kết quả về 1.
7. Tới 4.
8. Dừng lại.

Lệnh đầu tiên của chương trình (có địa chỉ 4) được gọi là lệnh điều kiện nhảy và lệnh thứ tư (có địa chỉ 7) là lệnh nhảy vô điều kiện. Lưu ý rằng

⟦folio 6⟧

Một lệnh nhảy có thể đã được lưu lại, nhưng đối với những gì tiếp theo, ký hiệu này thuận tiện cho chúng ta. Biểu diễn từng thao tác bằng mã kép:

so sánh 001
cộng 010
phép nhân 011
chuyển tiếp 100
dừng 101,

và địa chỉ các ô từ 0 đến 8 với mã kép gồm bốn chữ số tương ứng, ta viết chương trình dưới dạng mã hóa (ký hiệu ~ biểu thị các địa chỉ không được sử dụng):

001 0010 0000 1000
010 0011 0010 0010
011 0010 0001 0001
100 0100 ~ ~
101 ~ ~ ~

Lưu ý rằng chương trình sẽ chỉ hoạt động chính xác khi nó được đặt vào các ô được chỉ định ở trên (thứ 4 đến thứ 8).

Có thể hiểu dễ dàng rằng phương pháp lập trình (bằng mã máy) được mô tả là cực kỳ cồng kềnh và tẻ nhạt, do đó ngay cả những chương trình có kinh nghiệm cũng mắc nhiều lỗi trong các chương trình hơi phức tạp. Các lỗi được sửa trong quá trình gỡ lỗi chương trình - một chương trình tuần tự (theo lệnh) để quản lý các tập dữ liệu (trong trường hợp này là với n = 2 hoặc n = 3) và điều khiển hoạt động của máy.

Sự phức tạp của chương trình điều khiển bài toán càng trở nên trầm trọng hơn khi bắt đầu có nhiều loại thiết bị lưu trữ (3U) khác nhau trong máy tính: trao đổi nhanh 3U tương đối nhỏ (nội bộ) và trao đổi lớn 3U chậm hơn (bên ngoài).

Từ năm 1951 đến năm 1955, các chương trình được thực thi bằng mã máy. Tuy nhiên, ngay trong giai đoạn này, nghiên cứu đã bắt đầu tìm cách quản lý chương trình bằng cách tự động hóa các giai đoạn khác nhau của nó. Một bước quan trọng là các địa chỉ ký hiệu (chữ cái) trong bản ghi chương trình gốc, sau đó là việc chọn các giá trị số cụ thể cho các địa chỉ này bằng một chương trình đặc biệt, dùng một lần. Cấu trúc của công thức toán học bài toán giảm thiểu việc sử dụng bộ nhớ đã xuất hiện. Đối với lời giải phương pháp kết hợp đặc biệt của họ đã được chọn.

Sự ra đời của các địa chỉ tượng trưng, ​​cùng với việc chỉ định ký hiệu cho hoạt động của máy, đã đánh dấu sự xuất hiện của các ngôn ngữ lập trình đầu tiên khác với ngôn ngữ mã máy và thuận tiện hơn khi sử dụng. Tuy nhiên, các ngôn ngữ thuộc lớp này, sau này được gọi là ngôn ngữ hợp ngữ, lấy máy làm trung tâm, vì chúng chỉ sử dụng làm thành phần của toán tử những hoạt động máy có sẵn trong một máy cụ thể.

Một yếu tố quan trọng trong sự phát triển của lập trình là sự ra đời của khái niệm chương trình con và sự ra đời của toán tử để truy cập các chương trình con sang ngôn ngữ hợp ngữ. Việc đưa một chương trình con vào chương trình chính được thực hiện trong quá trình dịch bản ghi gốc của chương trình sang biểu diễn (máy) cuối cùng bằng cách sử dụng một chương trình đặc biệt, được gọi là trình biên dịch chương trình.

Một bước tiến mới trên con đường điều khiển lập trình đã được thực hiện nhờ việc tạo ra các ngôn ngữ chương trình phổ quát theo định hướng quy trình và các trình dịch tương ứng. Những ngôn ngữ như vậy không bị ràng buộc với đặc điểm thực thi chương trình trong các máy cụ thể; họ sử dụng rộng rãi các công thức của ngôn ngữ đại số. Ngôn ngữ hướng quy trình được chú ý đầu tiên là ngôn ngữ địa chỉ, được phát triển vào năm 1955-1956 bởi V. S. Korolyuk và E. L. Yushenko. Ngôn ngữ toán tử do A. A. Lyapuny đề xuất vào năm 1954 đóng một vai trò quan trọng trong sự phát triển của lý thuyết lập trình. Một chương trình trong ngôn ngữ này được biểu diễn dưới dạng một chuỗi hữu hạn các toán tử $P_i$ và các điều kiện logic $\alpha_j$, thuộc về một tập hợp các toán tử và điều kiện nhất định. Sự chuyển đổi do việc kiểm tra các điều kiện logic được biểu thị bằng các mũi tên hoặc ký hiệu đặc biệt. Trong phần trên

⟦folio 7⟧

Phép tính gram $n!$ bao gồm các toán tử cộng $P_1$, phép nhân $P_2$, dừng $P_3$ và điều kiện logic $\alpha$ - điều kiện cho sự bằng nhau của nội dung của ô 0 và ô thứ hai. Chương trình bằng ngôn ngữ toán tử sẽ được viết dưới dạng sau:

$$S = \prod_{i=1}^{n} P_1 P_2 \prod_{j=1}^{n} P_3.$$

Sự hiện diện của một hình thức viết chương trình tương đối đơn giản đã đặt ra câu hỏi về những biến đổi hình thức của chương trình. Yu. I. Yanov, A. P. Ershov và các nhà toán học Liên Xô khác đã đóng góp rất nhiều và thành công vào việc phát triển lý thuyết về những phép biến đổi như vậy.

Một bước quan trọng trong lý thuyết về hệ thống máy tính là sự xuất hiện của khái niệm máy tự động hữu hạn vào đầu những năm 50. Thiết bị này, chỉ có thể ở một trong các trạng thái $a_i$, tạo thành một tập hữu hạn, có thể chuyển từ trạng thái này sang trạng thái khác dưới tác động của tín hiệu đầu vào $x_j$, tạo thành một tập hữu hạn, đến những thời điểm nhất định $t = 1, 2, \dots$ và có thể tạo ra tín hiệu đầu ra $y_k$, là các hàm của cặp $(a, x)$ của trạng thái và tín hiệu đầu vào.

Cùng với bộ máy đại số Boolean, lý thuyết về automata đã tạo thành một bộ máy chính thức, với sự trợ giúp của nó, người ta có thể chính thức hóa và sau đó tự động hóa một phần quan trọng của công việc thiết kế hệ thống máy tính. Hóa ra là có thể biểu diễn bất kỳ chương trình nào (cả máy và người vận hành) dưới dạng một máy tự động hữu hạn.

Vào những năm 60, hệ thống máy tính và lập trình đã có sự phát triển hơn nữa. Ý tưởng nâng cao trình độ ngôn ngữ máy, được tác giả bày tỏ vào năm 1958, đã được đưa vào máy tính mini MIR-1 (1965), và sau đó ở dạng tiên tiến hơn nữa trong máy MIR-2 (1969). Trong máy MIR-2, ngôn ngữ bên trong đặc biệt phong phú. Nó cho phép bạn thao tác không chỉ với số nguyên và phân số thập phân mà còn với các phân số thông thường, cũng như với các công thức sử dụng

⟦folio 8⟧

các hàm cơ bản (logarit, snus, v.v.) và các phép tính vi phân và tích phân.

Nhờ sự phong phú của ngôn ngữ bên trong nên quá trình dịch một chương trình từ ngôn ngữ đầu vào sang đầu ra thực tế của máy. Một thiết bị điều khiển đa giác đặc biệt cung cấp khả năng giải thích nhanh chóng các toán tử phức tạp (ví dụ: toán tử vi phân phân tích và xen kẽ), nhờ đó, MIR-2, khi thực hiện các phép biến đổi hình thức, được biên dịch thành công ở tốc độ làm việc với các máy tính mạnh hơn nhiều được chế tạo theo sơ đồ Neumann truyền thống.

Việc nâng cao trình độ ngôn ngữ máy đồng nghĩa với việc khám phá ra nguyên lý thứ hai của von Neumann một cách hiệu quả. Sau dòng máy MIR, công ty Barrows của Mỹ đã đi theo con đường này và vào những năm 70, hướng này đã trở thành sự phát triển tuyến tính được chấp nhận chung của các hệ thống máy tính. Một hướng khác, được phát triển rộng rãi vào những năm 60, là tạo ra các hệ thống phần mềm đặc biệt (được gọi là hệ điều hành) để quản lý quá trình tính toán và quản lý lập trình trong việc sử dụng các hệ thống bộ nhớ phi kiến ​​trúc phức tạp.

Máy tính trong thời kỳ này đã phát triển thành các hệ thống máy tính phức tạp tích hợp nhiều thiết bị khác nhau, bao gồm nhiều loại thiết bị đầu vào/đầu ra và thiết bị bộ nhớ ngoài. Tổ chức phối hợp hiệu quả hoạt động của tất cả các thiết bị này bằng một trong những chương trình quan trọng nhất của hệ điều hành - bộ điều phối máy. Mỗi thiết bị hoạt động theo tốc độ riêng, trong khi người điều phối điều phối công việc của họ, tổ chức kết nối giữa các thiết bị và trao đổi thông tin tương ứng. Kết quả là, khả năng đa chương trình đã xuất hiện, tức là tải đồng thời không chỉ một mà nhiều chương trình vào hệ thống và thực thi song song chúng theo lệnh của người điều phối: trong khi bộ xử lý trung tâm đang đếm một chương trình, các chương trình khác có thể thực hiện các thao tác đầu vào và đầu ra, tìm kiếm thông tin trong bộ nhớ ngoài (mất một thời gian đặc biệt dài), v.v.

Do đó, ở một mức độ nhất định có thể phân biệt được với nguyên tắc thứ tư của von Neumann - tính bất biến của cấu trúc truyền thông - do xảy ra hiện tượng ngắt kết nối và kết nối hoạt động của nhiều loại thiết bị ngoại vi (đầu vào, đầu ra và 3U bên ngoài). Lập trình viên có cơ hội không chỉ định các hoạt động với các thiết bị ngoại vi cho một số phần thiết bị nhất định: việc lựa chọn và đưa chúng vào quy trình thích hợp được thực hiện bởi hệ điều hành.

Một phần đặc biệt của hệ điều hành quản lý dữ liệu. Nó không chỉ đặt các hệ thống dữ liệu phức tạp ở dạng 3D thuộc nhiều loại khác nhau mà còn tìm kiếm chúng và chuyển chúng vào RAM. Trong một số hệ thống phần mềm hệ điều hành, cái gọi là bộ nhớ ảo được tổ chức. Trong trường hợp này, lập trình viên dường như có sẵn mỗi RAM bằng tổng công suất của toàn bộ 3U của hệ thống. Việc truyền dữ liệu và khối chương trình cần thiết sang RAM thực tế được thực hiện tự động.

Hệ thống tự động hóa chương trình và máy móc trong thời kỳ này bao gồm nhiều ngôn ngữ đầu vào, do đó có thể viết các khối riêng lẻ của cùng một chương trình bằng các ngôn ngữ khác nhau. Khối lượng quốc tế ngày càng tăng của chương trình đã dẫn đến nhu cầu tạo ra các ngôn ngữ định hướng quy trình phổ quát quốc tế. Ngôn ngữ ALGOL-60 nhận được sự quan tâm đặc biệt lớn. Trong các hệ thống tự động hóa hiện đại, các chương trình và máy móc chấp nhận rộng rãi các ngôn ngữ khác (Fortran, PL-1, v.v.).

Các lập trình viên phát triển hệ điều hành và hệ thống tự động hóa lập trình được gọi là các chương trình hệ thống chung, trái ngược với các lập trình viên phát triển ứng dụng.

⟦folio 9⟧

các chương trình có giá trị trong một hoặc một lĩnh vực chủ đề cụ thể khác. Nếu trong trường hợp thứ hai, yêu cầu chính là hiểu biết tốt về chương trình trong lĩnh vực chủ đề tương ứng, thì trong trường hợp đầu tiên, chương trình bắt buộc phải nắm vững tất cả các bí mật về kỹ năng lập trình và hiểu biết về kiến ​​trúc của hệ thống máy tính hiện đại.

Vào những năm 60, Liên Xô đã phát triển các chương trình hệ thống trường học vững mạnh ở Moscow, Novosibirsk, Kyiv và một số thành phố khác.

Mặc dù về nguyên tắc, nhiều bài toán tối ưu hóa hệ điều hành có thể được chuyển thành các công thức toán học chính xác, nhưng theo quy luật, toán học hiện đại vẫn chưa thể giải được chúng. Vì vậy, khi tối ưu hóa hệ điều hành và cấu trúc của hệ thống máy tính, các phương pháp mô hình hóa máy được sử dụng rộng rãi. Các ngôn ngữ đặc biệt hướng tới mô hình hóa như vậy đã được phát triển, chẳng hạn như ngôn ngữ “SLANG” (1968), Nedis (1974), v.v.

Một lĩnh vực lập trình quan trọng kể từ nửa sau những năm 60 là việc tạo ra các gói phần mềm ứng dụng trong nhiều lĩnh vực ứng dụng khác nhau. Một gói không chỉ là sự kết hợp cơ học của nhiều chương trình khác nhau mà còn là một tập hợp các chương trình dịch vụ đặc biệt cho phép sử dụng chúng, tức là một hệ điều hành chuyên dụng nhỏ với ngôn ngữ đầu vào hướng đến vấn đề. Gói tính toán chính thức cho phép đưa các định dạng ở dạng con người có thể đọc được vào máy, ví dụ: $x = \sqrt{5,26 + 7,32 \cdot 8,04}$, $y = \sin(\pi/16)$, v.v.

Trong lý thuyết về hệ thống máy tính, tác giả vào năm 1966 đã tìm ra một cách tiếp cận mới giúp viết chương trình dưới dạng định dạng trong một số thuật toán đại số đặc biệt. Không giống như đại số học thông thường, trong đó giá trị của các biến thuộc miền của tất cả các số thực, trong đại số thuật toán có hai môn học khác nhau. Tuy nhiên, các biến bằng chữ cái Latinh) được hiểu là các toán tử ánh xạ một số tập hợp đã cho $M$ vào chính chúng. Các biến khác (ký hiệu bằng chữ cái Hy Lạp) được hiểu là điều kiện logic nhận hai giá trị trên tập $M$: 0 và 1.

Cả toán tử và điều kiện đều có thể được xác định không phải trên toàn bộ tập hợp $M$ mà trên một phần nào đó của tập hợp đó. Đại số các điều kiện (đại số Boolean) và đại số các toán tử (nửa nhóm) đã được nghiên cứu từ lâu. Bản chất ý tưởng của tác giả là đưa ra các phép toán kết hợp, trong đó có cả điều kiện và toán tử. Đây là hoạt động sau:

$$\alpha - \text{диизjonция} (P \vee Q),$$

$$\alpha - \text{итерация} \left\{ P \right\},$$

phép nhân các điều kiện bởi toán tử $P \cdot \alpha$.

Không đi sâu vào định nghĩa chi tiết về các toán tử này, chương trình $S$ vừa thảo luận ở trên có thể được viết dưới dạng lặp $\alpha$: $S = \left\{ P_1 P_2 \right\}$. Người ta đã chứng minh rằng bất kỳ chương trình nào bao gồm các toán tử $P_1, \dots, P_m$ và các điều kiện $\alpha_1, \dots, \alpha_n$ đều có thể được viết dưới dạng đại số hình thức của các thuật toán với các biến $P_1, \dots, P_m$ và $\alpha_1, \dots, \alpha_n$.

Trong đại số của các thuật toán, cũng như trong đại số trường học thông thường, có các phép biến đổi công thức tương đương, nghĩa là biến đổi chương trình mà không thay đổi định nghĩa toán tử phức tạp của nó (chuyển đổi thành một tập hợp dữ liệu). Việc sử dụng thuật toán như vậy cho phép trong những năm 1969-1973 xây dựng một hệ thống thiết kế máy tính tự động cùng với bất kỳ hệ thống chương trình nào được triển khai trên chúng, tăng năng suất lao động trong quá trình thiết kế lên 20-30 lần.

Trong những năm 70, lý thuyết về lập trình và hệ thống máy tính tiếp tục phát triển với tốc độ chóng mặt. Đặc biệt chú trọng trong giai đoạn này là công nghệ biên soạn và phương pháp xác minh tính pháp lý.
