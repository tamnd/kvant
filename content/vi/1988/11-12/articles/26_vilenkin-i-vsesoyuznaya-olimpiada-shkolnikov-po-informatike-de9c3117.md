---
id: 1988-11-12-vilenkin-i-vsesoyuznaya-olimpiada-shkolnikov-po-informatike-de9c3117
issue: kvant_1988_11-12
year: 1988
number: 11-12
title: I Olympic Tin học toàn trường dành cho học sinh
authors:
  - Виленкин А. Н.
rubric: olimpiady
rubric_sub: Олимпиады
page_first: 84
page_last: 86
page_labels: 82-84
tag: Z98W
lang: vi
source: kvant_digital
extraction: vision
content_sha256: a603a434987a3af926322ceeb118fd48748a68314f15f328038be3a18789432f
prompt_sha256: draft-1
translated_from: content/ru/1988/11-12/articles/26_vilenkin-i-vsesoyuznaya-olimpiada-shkolnikov-po-informatike-de9c3117.md
source_content_sha256: e959b3397dafd94ad51728a7eee0dddfd52a1bd473bdd4623c7e0c0da1579a7e
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 82⟧

I Olympic toàn Nga dành cho học sinh về khoa học máy tính

A. N. VILENKIN

Giai đoạn cuối cùng của Kỳ thi Olympic toàn Liên minh dành cho học sinh về khoa học máy tính được tổ chức tại Sverdlovsk từ ngày 13 tháng 4 đến ngày 20 tháng 4 năm 1988. 80 học sinh từ tất cả các trung tâm tài nguyên của liên đoàn đã cùng nhau kiểm tra sức mạnh của mình.

Lễ khai mạc Olympic diễn ra vào ngày 14/4 tại Cung Văn hóa Ural - hiện đại, đơn giản và tiện nghi. Những người tham gia Olympic được chào đón bởi trưởng phòng khoa học và các cơ sở giáo dục của CPSU A.G. Zhdanovich khu vực, viện sĩ G.S. Poselov, đại diện ban tổ chức trung ương Olympic toàn liên bang dành cho học sinh T.A. Sarycheva và những người khác. Olympic Zhorgi do học giả N. N. Krasovsky đứng đầu, ban tổ chức là phó. Chủ tịch Giáo dục Công cộng Sverdlovsk A. A. Leonov. Cùng ngày đó, học sinh bắt đầu làm quen với công nghệ máy tính mà các em phải làm việc. Người dân Sverdlovsk đã tặng hơn 80 máy tính Robotron-1715 cho Thế vận hội. Hầu như tất cả mọi người đều phải làm việc mà không làm việc, điều này đặt những người tham gia Olympic vào tình thế bình đẳng. Mặt khác, những chiếc máy tính này là thứ mà những người tham gia Olympic được hứa sẽ sử dụng và trong hai ngày (14 và 16 tháng 4), công việc kỹ thuật đã hoàn thành.

Thế vận hội diễn ra trong hai vòng. Vòng lý thuyết diễn ra vào ngày 15 tháng 4. 4 bài toán đã được đưa ra, với lời giải nhận được phản hồi sau ba tiếng rưỡi. Đồng thời, các thuật toán được phép viết bằng bất kỳ ngôn ngữ lập trình khá phổ biến nào (ngôn ngữ thông tin thuật toán, Pascal, Rapier, BASIC, Algol, Fortran, C, v.v.). Bài toán để biên soạn một thuật toán được coi là đã giải quyết được nếu thuật toán được trình bày là chính xác. Điểm bổ sung được trao vì tính đơn giản và độc đáo của thuật toán, sự chứng minh tính đúng đắn của nó, sự hiện diện của các nhận xét và hiệu quả (thời gian hoạt động thấp, sử dụng bộ nhớ). Khi kiểm tra bài toán, điểm (0-5 điểm) được nhân với hệ số đặc trưng cho độ khó bài toán (tùy thuộc vào số lượng người tham gia giải được câu hỏi này bài toán); hệ số này được cho trong ngoặc đơn sau số bài toán.

Bài toán loại lý thuyết

T1 (*7). Thuật toán được đưa ra:
alg có vấn đề (số nguyên n)
tranh cãi
bắt đầu int k, tôi
k:=n
i:=2
trong khi k≠1
nc
nếu số dư (k, i)=0
sau đó in (i)
k:=k/i
nếu không thì tôi:=i+1
Tất cả
kts
lừa đảo

Lệnh print (i) in số i; số dư (k, i) là số dư khi chia k cho i. Những số nào sẽ được in ra khi sử dụng thuật toán (n) có vấn đề cho số nguyên n ≥1? Căn cứ đáp số.

T2 (*6). Đối với hình chữ nhật có các cạnh song song với các trục tọa độ, chúng ta sẽ chỉ định tọa độ của góc dưới bên trái và góc trên bên phải của nó. (Do đó, tổng cộng, đối với hình chữ nhật bài toán, bạn sẽ cần 4 số). Cho hai hình chữ nhật Pr1 và Pr2. Xác định diện tích phần đó của hình chữ nhật Pr1 không có trong Pr2. (Thuật toán phải phù hợp với mọi phương án về vị trí của Pr1 và Pr2.)

T3 (*9). Nước này có n thành phố, được đánh số từ 1 đến n; Có kết nối không khí giữa một số trong số họ. Bảng is_flight [1:n, 1:n], chứa thông tin về chuyến bay: is_flight [i, j] bằng 1 nếu i≠j và có chuyến bay từ thành phố i đến thành phố j, và bằng 0 nếu ngược lại. (Chuyến bay không có điểm dừng trung gian; việc có chuyến bay từ i đến j không đảm bảo có chuyến bay từ j đến i). Được biết rằng:
1) từ bất kỳ thành phố nào bạn có thể đến bất kỳ thành phố nào khác (có thể bằng chuyển tuyến);
2) Số chuyến bay đến bất kỳ thành phố nào cũng nhiều như số chuyến khởi hành (cột thứ i của bảng has_flight có cùng số đơn vị, cột nằm ở hàng thứ i).
Chứng minh rằng bạn có thể bay ra khỏi một thành phố nhỏ và sử dụng chính xác

⟦folio 83⟧

Chuyến tham quan lý thuyết.
Chuyến tham quan bằng máy.
Những người đoạt giải Olympic và đoạt giải «Kvant» (từ trái sang phải): S. Kovalev, V. Kalashnikov, V. Zavalishin, G. Nischanov, I. Ovcharenko, S. Kalinitsenko, M. Plukas, A. Vashillo.

⟦folio 84⟧

một lần trên mỗi chuyến bay, trở về cùng một thành phố. Tạo một thuật toán để tìm một tuyến đường như vậy.

(Có một thuật toán yêu cầu thực hiện không quá $Cn^4$ lệnh cho một số hằng số $C$, độc lập với $n$).

T4 (*10). 3.000.000 người mang họ khác nhau đứng đối diện nhau. Tất cả mọi người, ngoại trừ người đầu tiên, đều viết vào một tờ giấy họ của người đứng trước mặt và họ của chính mình. Tất cả 2.999.999 mảnh giấy đã được trộn lẫn và thông tin (theo thứ tự các cặp họ) được ghi vào băng từ. Làm thế nào bạn có thể nhanh chóng tìm ra họ của người thứ 1.234.567? Bạn có thể tùy ý sử dụng một máy tính có RAM nhỏ (64 KB) và số lượng máy ghi băng hạn chế (32).

Chuyến tham quan máy được tổ chức vào ngày 17/4 tại Nhà máy đào tạo, sản xuất số 9 và Đại học bang Ural; chương trình có thể được viết bằng BASIC hoặc Pascal. Trong các bài toán ước lượng kiểu máy, kết quả đã có sẵn; sử dụng máy tính chỉ là một phương tiện. Điểm đánh giá bổ sung sẽ được cộng khi trình bày phương pháp lời giải, cơ sở lý luận, nhận xét về chương trình, v.v.

Bài toán chuyến tham quan bằng máy

M1 (*3). Dãy số nguyên dương $a_0, a_1, a_2, \dots$ được xây dựng như sau: nếu $a_n$ chẵn thì $a_{n+1}=a_n/2$; nếu $a_n$ lẻ thì $a_{n+1}=3a_n+1$.

Tìm mức tối thiểu $n$ mà $a_n=1$ nếu
a) $a_0=27$;
b) $a_0=2 000 007$.

M2 (*13). Đối với mỗi số nguyên dương $n$, chúng ta sẽ xem xét tất cả các biểu diễn có thể có của nó dưới dạng tổng của một hoặc một số số nguyên dương. Lập một bảng trong đó chỉ ra số lượng các cách biểu diễn như vậy cho mỗi $n$ (không tính đến thứ tự: các cách biểu diễn $3=2+1$ và $3=1+2$ được coi là giống nhau). Ví dụ: đối với $n=4$ cách biểu diễn như vậy $5(4, 3+1, 2+2, 2+1+1, 1+1+1+1)$. (Càng điền đầy đủ bảng thì bài làm sẽ được chấm điểm càng cao).

Cuộc xem xét bài toán được tổ chức vào buổi sáng ngày 18 tháng 4 và đơn kháng cáo được xem xét vào buổi tối cùng ngày. Vào ngày 19 tháng 4, một lễ hội tổng hợp đã diễn ra tại Cung Văn hóa Ural. Tất nhiên, những người tham gia Olympic đã mang theo rất nhiều

đĩa mềm và băng cassette có các chương trình, và họ muốn trưng bày các chương trình của mình, xem xét những chương trình khác và có lẽ là trao đổi các sản phẩm phần mềm. Đây chính xác là quá trình dello tại lễ hội. Ban tổ chức đã cung cấp cho học sinh và trưởng nhóm các máy tính khác nhau và tất cả các chương trình có sẵn đều được trình diễn trong thực tế. Sắp xếp 纵impads cũng giới thiệu các chương trình phát triển của họ dành cho học sinh trung học.

Chương trình văn hóa bao gồm chuyến thăm các bảo tàng và nhà hát Sverdlovsk, rạp xiếc và chuyến đi đến biên giới Âu-Á.

Lễ trao giải và bế mạc Olympic diễn ra vào tối 19/4. Có 5 học sinh nhận bằng tốt nghiệp độ I (đạt 125-156 điểm), 9 học sinh nhận bằng tốt nghiệp độ II (87-116 điểm) và 15 học sinh nhận bằng tốt nghiệp độ III (59-78 điểm). 10 người tham gia Olympic đã nhận được sự công nhận đặc biệt từ các tổ chức khoa học và công cộng, bao gồm các giải thưởng từ tạp chí «Kvant» về văn hóa toán học cao trong công việc - Zavalishin V. (Moscow, trường số 542), Kalinichenko S. (Kyiv, trường số 145), Kovalev S. (Gorky, trường số 40) và Ovcharenko I. (Khabarovsk, s.sh. số 32).

Còn điều gì còn phải nói về cuộc thi Olympic toàn liên minh đầu tiên dành cho học sinh về thông tin này? Trước hết, chúng ta phải chúc mừng và cảm ơn tất cả những người, ít nhất ở một mức độ nào đó, đã giúp vượt qua mọi khó khăn và tổ chức, tiến hành Thế vận hội. Chúng ta phải chúc mừng người chiến thắng; Ở những nơi đầu tiên của đất nước chúng ta, công việc Olympic đang được tăng cường trong lĩnh vực thông tin. Đỉnh cao của trường Olympic được đánh dấu.
