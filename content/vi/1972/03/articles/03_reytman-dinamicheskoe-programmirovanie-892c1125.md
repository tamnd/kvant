---
id: 1972-3-reytman-dinamicheskoe-programmirovanie-892c1125
issue: kvant_1972_3
year: 1972
number: "3"
title: Lập trình động
authors:
  - Рейтман М. И.
rubric: osnovnye-stati
page_first: 8
page_last: 14
page_labels: 6, 8, 10, 11, 12
tag: QZQV
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 476b01c910f47928eb8435924dd4e38bc449cc15c0c890cfa78b58313a53c4b8
prompt_sha256: draft-1
translated_from: content/ru/1972/03/articles/03_reytman-dinamicheskoe-programmirovanie-892c1125.md
source_content_sha256: e9d03df10ffda295c867aea6e7da4957c9aa039af0450cb516cd062a39b09750
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 6⟧

NĂNG ĐỘNG
LẬP TRÌNH

Cầu thang của Pharaoh

Cung điện của pharaoh nổi tiếng với phong cách Nga: rèm ngọc trai, tường trang trí bằng hổ phách, bát đĩa bằng vàng - có quá nhiều thứ để liệt kê. Nhưng điều khiến những người được phép vào phòng ngai vàng của cung điện ấn tượng nhất chính là chiếc cầu thang vàng dẫn lên ngai vàng. Cầu thang này trông như thế nào về mặt cắt ngang, nếu bạn chuyển đổi các thước đo của người Ai Cập cổ đại thành thước đo thực tế, bạn có thể thấy trong Hình 1.
Các nhà khảo cổ không cần phải vắt óc lâu để hiểu rằng các bậc thang quá thấp, mọi thứ đều được giải thích một cách đơn giản: vị pharaoh được trình bày không muốn thần dân của mình thấy việc leo lên ngai vàng của ông khó đến mức nào, họ có thể mất đi sự tôn trọng, và ai biết được điều này có thể kết thúc như thế nào?
Khi đó ông đã ra lệnh cho những người thợ kim hoàn hàng đầu làm một chiếc cầu thang có bậc thấp như vậy, không cao quá 1,5 inch.
Nhưng thời gian trôi qua, vị pharaoh già qua đời. Con trai nhỏ của ông đã tiếp quản vương quốc.
Vị pharaoh trẻ tuổi đã từng nghe kể về việc các cận thần thay phiên nhau trước sự xảo quyệt ngây thơ của cha ông. Và mặc dù bản thân ông đã lên ngôi, nhảy ba bước nhưng những tin đồn vẫn tiếp tục. Và vị pharaoh trẻ tuổi quyết định chấm dứt hắn bằng cách dựng lên một chiếc thang. Để làm điều này, ông gọi các thợ kim hoàn của triều đình và thủ quỹ và nói với họ:
- Nghe tôi này! Tôi ra lệnh cho bạn xây cái thang sao cho nó có nhiều nhất là bốn bậc. Sắp xếp chúng ở bất cứ đâu bạn muốn, nhưng hãy đảm bảo không có quá bốn cái!
“Nhưng thưa ông,” thủ quỹ rụt rè bước tới, “ông lấy đâu ra nhiều vàng thế?” Ở đây tôi đã ghim nó lên một mảnh giấy paprius (và thủ quỹ đã cho xem những gì được thể hiện bằng đường chấm trong hình vẽ cầu thang). Cầu thang rộng 1 m hoặc 10 dm. Điều này có nghĩa là để tăng nó, bạn sẽ cần [3×1,5+1,2×(5+1)+1×1+1×3+0,8(3+4)+1,2×11]×10 = 345 dm³ vàng! Than ôi, thưa ngài, sẽ không có rất nhiều thứ được tìm thấy trong kho bạc của chúng tôi, nơi bị tàn phá bởi cuộc chiến với Efyupne.
- Đáng khinh! Bạn phủ bóng lên sức mạnh của tôi! Nếu trong 7 ngày nữa, chiếc thang vẫn chưa sẵn sàng, chính tôi sẽ dìm bạn xuống sông Holy Nile, và những người thợ kim hoàn sẽ bị bán ở nơi làm việc. Và đừng nghĩ đến việc can thiệp vào những bức vẽ ngu ngốc của bạn nữa!
Người thủ quỹ chán nản rời bỏ pharaoh và quay lại với người bạn của mình. Không có người nào khéo léo hơn trong việc quy hoạch một thiên đường hay tính toán việc phân chia đất đai. Mặc dù người bạn này là thầy tu của ngôi chùa kinh đô, nhưng người ta nghe nói ông là một người thận trọng và thực tế. Biết được sự việc, ông hỏi:
- Kho bạc còn lại bao nhiêu vàng?
- 200 dm³.
- Không nhiều lắm đâu! Hoặc có thể bạn có thể đạt được ít hơn nếu bạn lên kế hoạch cho các bước khác nhau?

⟦folio 8⟧

tăng bước thứ hai hoặc bước đầu tiên và dấu min cho biết rằng bạn cần thực hiện bước nhỏ nhất trong số đó. Chúng ta thay các giá trị $f_1(1)$ và $f_1(2)$ vào ngoặc, thấy bằng nhau:
$$f_2(3) = \min\{(0+0,7\times4), (4,5+0)\} = 2,8.$$
Bây giờ đã rõ ràng rằng nếu chỉ có ba bước trong lá và số lượng của chúng cần giảm xuống còn hai, thì bước thứ hai cần phải tăng lên.
— Nếu có 4 bước thì sao?
- Sau đó
$$f_2(4) = \min\{(f_1(1) + 0,7\times4 + 1\times(4+1)), (f_1(2) + 1\times1), (f_1(3) + 0)\} = \min\{(0+7,8), (4,5+1), (9,4+0)\} = 5,5$$
nghĩa là, nếu có 4 bước trong chiếc lá và chúng ta thay thế chúng bằng hai bước, thì bước đầu tiên sẽ kết thúc tốt nhất trên bước cũ thứ hai (Hình 4).
“Đợi đã, tôi muốn chắc chắn rằng mình hiểu,” người đầu tiên là thủ quỹ của anh ta. — Vì vậy, để tìm $f_2(5)$, bạn cần thực hiện như sau:
$$f_2(5) = \min\{(0+7,8+1,2\times(4+1+5)), (4,5+1\times1+1,2\times(1+5)), (9,4+1,2\times5), (17,4)\} = \min\{(19,8), (12,7), (15,4), (17,4)\} = 12,7.$$
Họ nói: “Vấn đề là những người khôn ngoan sẽ trông coi kho bạc nhà nước”.

Hình 2.
8

linh mục. - Và sau đó
$$f_2(6) = \min\{(0+19,8 + 1\times(4+1+5)), (4,5+8,2+1\times(1+5+3)), (9,4+1,2\times5+8), (17,4+1\times3), (33+0)\} = \min\{(0+32,8), (4,5+17,2), (9,4+14,0), (17,4+3), (33+0)\} = \min\{(32,8), (21,7), (23,4), (20,4), 33\} = 20,4.$$
Chúng ta có thể tiếp tục và tìm $f_2(7)$, nhưng điều này là không cần thiết, như bạn sẽ sớm thấy. Bây giờ chúng ta chuyển sang trường hợp thang được thay thế bằng ba bậc.
Hãy bắt đầu bằng việc tìm $f_3(4)$, tức là phương án hợp lý nhất để tăng bốn bước đầu tiên. Xét cho cùng, $f_3(1)$ và $f_3(2)$ là vô nghĩa (bạn không nên thay thế một hoặc hai bước bằng khay) và $f_3(3)=0$ - tăng ba bước lên ba không yêu cầu tiêu tốn vàng. Để tìm $f_3(4)$, chúng ta hãy xem bậc thang thứ hai có thể kết thúc ở đâu. Tất nhiên là ở cái cũ thứ 2 hoặc thứ 3. Có nghĩa,
$$f_3(4) = \min\{f_2(2)+1\times1), (f_2(3)+0)\} = \min\{0+1), (2,8+0)\} = 1.$$
Vì vậy, xây dựng 4 bước sao cho có 3 bước thì bạn cần hoàn thành bước thứ 2 mới.

⟦folio 10⟧

hành động - phép cộng và phép nhân (ngoại trừ một khoản phí nhất định đối với linh mục, khi yêu cầu phép trừ), và chúng rất nổi tiếng ở Ai Cập cổ đại. Vâng, một chút ý nghĩa thông thường hơn được sử dụng. Trong khi đó, một công cụ toán học được sử dụng ở đây chỉ mới trở nên phổ biến cách đây khoảng hai mươi năm; nó được gọi là lập trình động.

Hãy nghĩ xem tại sao chúng ta tìm được lời giải tối ưu mà không xem xét tất cả các phương án có thể có để xây cầu thang (và có rất nhiều phương án, và vị linh mục thực sự sẽ không có đủ thời gian để nghiên cứu chúng một cách đầy đủ). Thực tế là ở mỗi bước, chúng tôi chia bài toán chung thành một số bước đơn giản hơn.

Cần phải xây một cầu thang có $N$ bậc, sao cho nó có $n$, trong đó $N \gg n$, tức là $N$ lớn hơn nhiều so với $n$. Giả sử rằng chúng ta đã biết cách phân bổ các bước tối ưu khi có $j$ trong cầu thang mới, trong đó $j \leq n$. Gọi $S_j$ là số bước cũ mà trên đó bước mới thứ $j$ kết thúc. Rõ ràng, bước thứ $j$ này bắt đầu từ bước thứ $(S_{j-1}+1)$ cũ. Diện tích bổ sung của cầu thang, được hiển thị trong Hình 6 bằng cách nở, sẽ phụ thuộc vào $S_{j-1}$ và $S_j$, tức là vào nơi bước $j$ bắt đầu và kết thúc; hãy biểu thị nó bằng $g(S_{j-1}, S_j)$. Đặt $f_j(S_j)$ là diện tích tối thiểu cho cầu thang có $S_j$ bậc được thay thế bằng $j$ bậc và $f_{j-1}(S_{j-1})$ là diện tích tối thiểu của cầu thang có $S_{j-1}$ bậc được thay thế bằng $j-1$ bậc. Chúng ta hãy thiết lập mối quan hệ giữa các đại lượng này, nghĩa là chúng ta sẽ tìm các giá trị như vậy của các biến $S_j$ cho giá trị nhỏ nhất của diện tích bổ sung:

$$g(S_1, S_2) + g(S_2, S_3) + \dots + g(S_{n-1}, S_n), \quad S_n = N.$$

Hãy giới thiệu chức năng

$$f_j(S_j) = \min \left[ g(S_1, S_2) + \dots + g(S_{j-1}, S_j) \right],$$

ở đâu $j=1, 2, \dots, n$. Lưu ý rằng $g(S_{j-1}, S_j)$ độc lập với $S_1, \dots, S_{j-2}$. Do đó, $g(S_{j-1}, S_j)$ có thể được coi là dấu hiệu giảm thiểu dọc theo $S_1, S_2, \dots, S_{j-2}$ (tương tự như cách lấy paraboly dọc theo trục $OY$ - điểm thấp nhất của paraboly sẽ không thay đổi so với điểm này):

$$f_j(S_j) = \min \left\{ g(S_{j-1}, S_j) + \min \left[ g(S_1, S_2), \dots, g(S_{j-2}, S_{j-1}) \right] \right\}.$$

Nhưng chúng tôi biểu thị số hạng thứ hai trong công thức trong ngoặc bằng $f_{j-1}(S_{j-1})$. Từ đây chúng ta có được

$$f_f(S_f) = \min \left\{ g(S_{j-1}, S_f) + f_{j-1}(S_{j-1}) \right\}.$$

Đây là phương trình R. Bellan, làm cơ sở cho quy hoạch động. Khả năng thực hiện các phép tính số và bạn sẽ thấy rằng chúng tôi đạt được chúng

⟦folio 11⟧

Ở mỗi bước. Nên hiểu như sau: để tìm mức tối thiểu, người ta phải gán $S_j$ tất cả các giá trị có thể, bắt đầu từ 1, và với mỗi giá trị, hãy tìm và điền giá trị $S_{j-1}$, mang lại giá trị nhỏ nhất $f_j(S_j)$. Và sau đó, làm việc cho đến giá trị cuối cùng $j=n$, bạn cần “lùi lại” và quay lại tìm tất cả các giá trị tối ưu $S_j$.

Giới thiệu về phương pháp và một chút lịch sử

Chúng ta hãy chú ý đến thực tế là trong phương pháp được mô tả không có điều kiện nào được áp đặt cho dạng của hàm $g(S_{j-1}, S_j)$. Theo cách này, quy hoạch động khác với quy hoạch tuyến tính *), trong đó yêu cầu tất cả các phụ thuộc được xem xét phải tuyến tính và các biến thay đổi liên tục. Vì vậy, phương trình R. Bellan và phương pháp trên hiện nay đã được sử dụng rất rộng rãi. Nhưng tất nhiên không phải để thỏa mãn ý muốn bất chợt của các pharaoh. Nếu không có nó, hãy cố gắng tìm ra sự phù hợp tối ưu cho trọng lượng của các giai đoạn của tên lửa vũ trụ, xác định nguyên tắc tốt nhất để thống nhất các bộ phận và xây dựng một lịch trình có ít thời gian ngừng hoạt động nhất! Bạn sẽ rơi vào tình thế tuyệt vọng với tư cách là thủ quỹ, bị choáng ngợp trước vô số lựa chọn khả thi. Tất nhiên, bằng cách sử dụng quy hoạch động, bạn gần như có thể

*) Xem ví dụ bài viết: A. V. Katok, Kinh tế học và bất bình đẳng tuyến tính, «Kvant» Số 3, 4, 1971.

không tính. Phương pháp này rất phù hợp để tính toán trên máy tính điện tử; phương pháp này rất dễ lập trình và không chứa bất kỳ “cạm bẫy” nào thường thấy trong lập trình tuyến tính.

Ý tưởng về phương pháp lập trình động đã có từ rất lâu. Ở một mức độ nào đó, nó cũng được C. Maclaurin (1698-1746) sử dụng. Tuy nhiên, cuối cùng nó đã thành hình trong các tác phẩm của nhà toán học người Mỹ R. Bellan và gắn liền với tên tuổi của ông.

Ở đây chúng tôi đã trình bày ứng dụng của quy hoạch động ở thang đo đơn giản bài toán. Ý nghĩ ngay lập tức nảy sinh: phương pháp này có thể áp dụng được cho những vấn đề phức tạp hơn như thế nào? Nó phải được trả lời một cách thận trọng. Thực tế là điều này tạo ra một khó khăn về đặc điểm kỹ thuật, được gọi là “lời nguyền về chiều hướng”. Bạn phải thử rất nhiều khả năng khác nhau và ghi nhớ nhiều kết quả đến mức phương pháp này mất đi những đặc điểm tích cực.

Một ứng dụng khác

Những âm thanh của sự sống hoặc trở nên đe dọa hoặc xa dần, nhưng rõ ràng mọi thứ đều là cuối cùng. Khi vắng mặt, pharaoh ngồi trước shagar của mình, xung quanh là các cận thần chán nản. Một người đưa tin đẫm máu chạy tới loạng choạng:

- Có chủ quyền! Quân tiếp viện du mục đang đến gần! Chúng tôi đang chết dần!

- Chúng ta sẽ phải rút lui. Chúng ta cần xem làm thế nào để vượt qua nó,” pharaoh rên rỉ, mắt nhìn vào bản đồ. - Nhưng chúng ta nên đi đường nào? Hãy nói cho tôi biết! “Ông rất giỏi tính toán và đã giúp tôi một lần,” ông quay sang thủ quỹ.

- Ôi, Osiris! - thủ quỹ kêu lên. - Nhưng đó là một bài toán hoàn toàn khác! Bây giờ hãy hỏi chỉ huy của bạn!

- Tôi không tin họ. Những kẻ ngốc này đã dự đoán chiến thắng cho tôi.

“Bây giờ tôi bị lạc,” thủ quỹ nghĩ khi nhìn vào bản đồ (Hình 7).

⟦folio 12⟧

Hình 7. Tên của các điểm được thay thế bằng các số trong vòng tròn và các số giữa chúng hiển thị độ dài của quá trình chuyển đổi tính bằng ngày.

Đột nhiên anh chợt nhận ra: “Nhưng suy nghĩ của linh mục cũng có thể được sử dụng ở đây!”

Trước tiên, chúng ta hãy xem xét đường đi từ địa điểm chiến đấu 1 đến các điểm 2, 3 và 4 gần nhất, các số mà chúng ta sẽ viết vào mỗi vòng tròn bên trái (Hình 8) và ở bên phải, chúng ta sẽ hiển thị độ dài của đường đi (màu đỏ). Ví dụ: phải mất 8 ngày để đạt đến điểm 4.

Bây giờ chúng ta sẽ xem xét toàn bộ đường đi từ điểm 2, 3, 4 mà không chú ý đến điểm 1 (Hình 9). Một số con đường đã dẫn đến mục tiêu. Vì vậy, trong đoạn 5 có hai cách được đưa ra. Hãy để lại những điều tốt nhất trong số chúng (mất 18 ngày) và loại trừ điều tồi tệ nhất bằng cách đánh dấu nó bằng dấu trừ. Đồng thời, chúng tôi loại bỏ đường đi đến điểm 7 (mất 21 ngày), đến điểm 6 (mất 24 ngày) và đến điểm 2 (ở bước đầu tiên chúng tôi đã có đường đi tốt nhất trong 2 ngày). Chỉ còn 3 điểm cần kiểm tra: 3, 4, 5.

Phân tích Hình 10 cho thấy đường đi tốt nhất mất 16 ngày và dẫn qua các điểm 2, 3, 5.

Lưu ý rằng ở giai đoạn cuối, thủ quỹ không còn quan tâm đến việc làm thế nào quân đội đạt được điểm 3, 4 (so sánh với bài toán bậc thang!). Nghĩa là, con đường xa hơn tốt nhất không phụ thuộc vào việc chúng ta đã kết thúc như thế nào tại bất kỳ thời điểm nào. Quy tắc chung này được gọi là “lý do tối ưu” và là cơ sở của lập trình Dianic.

Bài tập

1. Đối với xưởng của trường, lần đầu tiên chúng tôi quyết định mua 9 chiếc máy tiện khác nhau với giá 10, 20, 40, 60, 75, 100, 130, 160,
