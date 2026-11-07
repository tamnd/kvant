---
id: 1992-6-tarasenko-problema-goldbaha-i-programmirovanie-75d6a8c9
issue: kvant_1992_6
year: 1992
number: "6"
title: Bài toán Goldbach và lập trình
authors:
  - Тарасенко Б.
rubric: raznoe
rubric_sub: Разное
page_first: 52
page_last: 55
page_labels: 50-53
lang: vi
source: kvant_digital
extraction: vision
content_sha256: f52cfe7f5cd5627623cab5dcc70b97ea07d1473acaf88de2c6f1734add14dd3a
prompt_sha256: draft-1
translated_from: content/ru/1992/06/articles/14_tarasenko-problema-goldbaha-i-programmirovanie-75d6a8c9.md
source_content_sha256: 4e47950ade155924d809a5f84874b420fbe46303de2494560909f7a8cca0fed6
translation_model: draft
translation_run: vi-draft-gaps-2026-11-07
translation_quality: draft
---

⟦folio 50⟧

Bài toán Goldbach và lập trình

V. TARASENKO

Năm 1724, Peter I thành lập Viện Hàn lâm Khoa học St. Petersburg. Nhiều nhà khoa học nước ngoài đã được mời làm việc trong đó: các nhà toán học Daniil và Nikolai Bernoulli, nhà thiên văn học J. N. Delisle, nhà vật lý G. V. Vilfinger và những người khác. Không có lời mời, một người rất thú vị đã đến dự khai trương học viện - nhà tư tưởng vĩ đại và không ngừng nghỉ ChristIAN Goldbach (1690-1764). Nhờ nghị lực và sự uyên bác của mình, H. Goldbach đã sớm đảm nhận chức vụ thư ký thường trực của học viện và trở thành thành viên danh dự của học viện. Rõ ràng, Học viện có được tính xác thực nhờ sự xuất hiện của nhà toán học vĩ đại Leonhard Euler (1707-1783) vào năm 1727.

Đối với Euler, điểm chung của anh với D. Bernoulli (người mà anh sống cùng một căn hộ trong 6 năm) và với H. Goldbach là rất quan trọng. Khi việc liên lạc trực tiếp trở nên bất khả thi, Euler bắt đầu trao đổi thư từ với anh ta. Vì vậy, ông đã trao đổi thư từ với Goldbach trong 35 năm, từ 1729 đến 1764.

Năm 1742, Christ IAN Goldbach viết cho Euler ở Berlin: “Ít nhất, mọi số tự nhiên lớn hơn hai đều có thể biểu diễn dưới dạng tổng của ba số nguyên tố”. Cần lưu ý rằng vào thời điểm đó một số được coi là số nguyên tố nên các số $3=1+1+1$, $4=2+1+1$, $5=2+2+1$ thỏa mãn giả định đã đưa ra.

Trong một bức thư trả lời, Euler đã viết về điều này: “... Nhưng mọi số đều là tổng của hai số nguyên tố, tôi tin đó là một định lý hoàn toàn xác định, mặc dù tôi không thể chứng minh nó.” Chính phát biểu này của Euler cho bốn số lớn hơn 4 đã được gọi là “vấn đề”.

⟦folio 51⟧

---
running_head:
folio:
---

my Goldbach", mặc dù nhiều nhà khoa học coi bài toán Goldbach bài toán là về khả năng biểu diễn mọi số tự nhiên lớn hơn 6 dưới dạng tổng của ba số nguyên tố. (Một từ lâu đã không còn được coi là một số đơn giản nữa và có khá nhiều lý do giải thích cho điều này.) Rõ ràng, từ bài toán lời giải trong công thức của Euler, bài toán lời giải trong công thức thứ hai như sau. Thật vậy, trừ 2 cho số chẵn và trình bày số kết quả là tổng của hai số nguyên tố, chúng ta thu được biểu diễn cần thiết dưới dạng ba số nguyên tố; Từ một số lẻ bạn cần trừ không phải 2 mà là 3.

Khá nhiều nhà khoa học nổi tiếng đã bẻ gãy răng của mình về vấn đề này. Nhà toán học lỗi lạc người Đức Edmund Landdu đã phát biểu tại Cuộc thi Toán học Quốc tế lần thứ V năm 1912 rằng ở trạng thái hiện tại, giá trị của không gian Goldbach là không thể tiếp cận được đối với lời giải.

Năm 1922, các nhà toán học người Anh Hardy và Littlewood, dựa vào cái gọi là giả thuyết Riemann tổng quát, đã suy luận rằng mọi số lẻ đủ lớn đều có thể được biểu diễn dưới dạng tổng của ba số nguyên tố. Năm 1937, I.M. Vinogradov đã chứng minh được tuyên bố này mà không cần dựa vào giả thuyết Riemann, giả thuyết này vẫn chưa được chứng minh cho đến ngày nay.

Trong công thức này, có vẻ như khoảng cách Goldbach trên thực tế đã được giải quyết; tất cả những gì còn lại là kiểm tra tính hợp lệ của nó đối với một số hữu hạn các số lẻ, điều này không khó với công nghệ hiện đại. Thật vậy, vào cuối những năm 60, giả thuyết Goldbach trong công thức Euler đã được xác minh cho tất cả các số chẵn lên tới 1.000.000.000 = 10⁹, nhưng số N, bắt đầu từ đó lý thuyết đảm bảo sự thỏa mãn của giả thuyết, thực sự rất lớn:

$$N = e^{16,3} > 10^{5643232}$$

Để kiểm tra số lượng như vậy, ngay cả chiếc máy tính mới nhất hiện nay cũng được thiết kế với độ ngẫu nhiên 10.000.000 = 10⁷

mỗi giây với 10 phép tính, việc kiểm tra từng con số sẽ mất nhiều thời gian hơn so với tuổi giả định của Vũ trụ!

Vì vậy, cần có những ý tưởng mới. Nhưng Euler, để thỏa mãn cái này hay cái khác bài toán, đã tiếp tục một lượng tính toán khổng lồ (người ta nói về anh ấy: “Anh ấy tính toán cách người khác thở”). Khó có ai trong số các bạn tính toán đúng Euler nhất, nhưng các bạn đã có trong tay công nghệ máy tính. Để bắt đầu, chúng ta có thể sử dụng máy tính lập trình MK-52 hoặc MK-61. Chúng tôi xin giới thiệu với bạn một chương trình phân tích tuần tự thành hai số nguyên tố của mỗi số từ 6 đến 99.999.998.

Sau khi vào chương trình, số ban đầu (ít nhất là sáu) được nhập và máy tính bắt đầu đếm. Ví dụ: nếu số bắt đầu là 14 thì khi làm việc với máy tính MK-61 sẽ như sau: F ABT B/O 1 4 "14" S/P "14" S/P "3" S/P "11" S/P "14" S/P "7" S/P "7" S/P "16" S/P "3" S/P "13" S/P "16" S/P "5" S/P “11” S/P “18”, v.v. Như các con số được chỉ định hiển thị trên chỉ báo. Trong thời gian làm việc này, máy tính sẽ chỉ ra tất cả các phân tách của các số 14 và 16 thành tổng của hai số nguyên tố: 14=3+11=7+7, 16=3+13=5+11.

Nhưng máy tính vi mô là một cỗ máy chậm. Vì vậy, để “giải mã” số 6, anh ta phải mất 13 giây và công việc tiếp theo sẽ tăng tỷ lệ với kích thước của số đang được thử. Ví dụ: số 286, có mười hai cách phân tách khác nhau thành tổng của hai số nguyên tố, cần 43 phút. May mắn thay, ngoài máy tính vi mô, còn có máy tính tính toán thành phố nhanh hơn. Đối với những người có quyền truy cập vào chúng, chúng tôi giới thiệu một chương trình trong BASIC.

Hãy để chúng tôi mô tả thuật toán mà chương trình này dựa trên.

Cho số chẵn 2n. Lấy số lẻ đầu tiên k (k=3). Tìm sự khác biệt 2n-k. Chúng tôi kiểm tra tính đơn giản của số này bằng cách sử dụng

⟦folio 52⟧

---
running_head:
folio:
---

Công cụ tìm hệ số nguyên tố cộng cho bốn số

00 X→Π 4 44 / + Cài đặt ban đầu H trong Pr4 từ PrX
01 X→Π 3 43 / + Nhập H từ PrX đến Pr3, thanh ghi nguyên tố đầu tiên
02 K P→X 3 G3 / + Giảm nội dung của Pr3 đi một
03 K P→X 3 G3 / + Giảm nội dung của Pr3 đi một
04 K P→X 3 G3 / + Giảm nội dung của Pr3 đi một
05 P→X 4 64 / + Gọi dòng chẵn H từ Pr4 đến PrX
06 P→X 3 63 / + Thêm C1 từ Pr3 vào PrX, H vào PrY
07 - 11 / + Số hạng C2=H - C1
08 X→Π 2 42 / + Cố định C2 trong Pr2
09 P→X 3 63 / + Gọi C1 tới PrX
10 P→X 2 62 / + Gọi C2 tới PrX, C1 tới PrY
11 - 11 / + Hình thành chênh lệch C1 - C2=F
12 F X ≥0 59 / + F lớn hơn hoặc bằng 0?
13 3 2 32 / + KHÔNG, thậm chí đã kiệt sức, chuyển sang bước 32
14 P→X 2 62 / + CÓ, gọi C2 đến PrX từ Pr2
15 PP 53 / + Chuyển sang chương trình con kiểm tra tính nguyên tố
16 3 7 37 / + có địa chỉ bắt đầu ở bước 37 cho số C2
17 F X≠0 57 / + Sau p/p, số có phải là số nguyên tố và không bằng 0?
18 0 3 03 / + NO, hợp số bằng 0, chuyển sang bước 03
19 P→X 3 63 / + CÓ, số C2 là số nguyên tố, gọi C1 từ Pr3 đến PrX
20 PP 53 / + Chuyển sang chương trình con kiểm tra tính nguyên tố
21 3 7 37 / + có địa chỉ bắt đầu ở bước 37 cho số C1
22 F X≠0 57 / + Sau p/p là số nguyên tố và không bằng 0?
23 0 3 03 / + KHÔNG, hợp số, chuyển sang bước 03
24 P→X 4 64 / + CÓ, số C1 nguyên tố, gọi H từ Pr4 đến PrX
25 C/P 50 / + Chỉ báo dừng của số chẵn H hiện tại
26 P→X 2 62 / + Gọi C2 từ Pr2 đến PrX, ít đơn giản hơn
27 C/P 50 / + Chỉ báo dừng nhỏ hơn thuật ngữ đơn giản C2
28 P→X 3 63 / + Gọi C1 từ Pr3 đến PrX, hơn cả đơn giản
29 C/P 50 / + Chỉ báo dừng lớn hơn thuật ngữ đơn giản C1
30 BP 51 / + Chuyển tiếp vô điều kiện sang bước
31 0 3 03 / + 03 để hình thành các thuật ngữ mới ở cùng H
32 K P→X 4 G4 / + Thêm sự thất bại của hai đội ở bước 32 và 33
33 K P→X 4 G4 / + với nội dung của Pr4
34 P→X 4 64 / + Gọi giá trị mới H từ Pr4 đến PrX
35 BP 51 / + Chuyển tiếp vô điều kiện sang bước
36 0 1 01 / + 01 sang chu kỳ tính toán mới với giá trị mới H
37 X→Π 6 46 / + Kiểm tra nạp lại. số AND từ PrX đến Pr6, đầu p/p
38 3 03 / + Hằng số “ba”, Và đi tới PrY
39 - 11 / + I - ba = K
40 F X≠0 57 / + K không bằng 0?
41 6 3 63 / + NO, K=0, I=3, chuyển sang bước 63 để thoát khỏi p/p
42 1 01 / + CÓ, K=0 và sự hình thành cấu trúc “đơn vị”
43 X→Π 5 45 / + Gửi 1 đến bộ chia bộ đếm Pr5 từ PrX
44 K P→X 5 G5 / + Thêm hai vào nội dung
45 K P→X 5 G5 / + Pr5 Lệnh ở bước 44 và 45
46 P→X 6 66 / + Số hợp chất Và từ Pr6 đến PrX
47 P→X 5 65 / + Gọi bộ chia hiện tại D từ Pr5, Và đi tới PrY
48  13 / + QUATIVE=I/D
49 X→Π 9 49 / + Chuyển tiếp SỐ LƯỢNG=I/D từ PrX sang Pr9
50 K P→X 9 G9 / + K=phần nguyên của I/D
51 P→X 6 66 / + Gọi Và từ Pr6 tới PrX
52 P→X 9 69 / + Gọi K từ Pr9 đến PrX và đi tới PrY
53 P→X 5 65 / + Gọi D trong PrX, PrY=K, PrZ=I
54 × 12 / + D×K, Và đi từ PrZ đến PrY
55 - 11 / + OST=I - K×D, phần dư của phép chia
56 F X≠0 57 / + OST không bằng 0?
57 6 4 64 / + NO (OST=0), chia theo bước 64
58 P→X 9 69 / + YES (OST=0), gọi số nguyên PART trong PrX
59 P→X 5 65 / + Gọi D từ Pr5 đến PrX, K đi PrY
60 – 11 / + PrX=PHẦN – D
61 F X<0 50 / + PHẦN - D nhỏ hơn 0?
62 4 4 44 / + KHÔNG, vẫn còn ước số, chuyển sang bước 44
63 P→X 9 69 / + CÓ, hết ước số, gọi I=P đến PrX từ Pr6
64 B/O 52 / + Trở về chương trình chính từ p/p

⟦folio 53⟧

---
running_head:
folio:
---

chương trình con tương ứng.
Nếu số 2n-k là số nguyên tố thì ta kiểm tra xem số k có phải là số nguyên tố hay không. Nếu nó cũng đơn giản, chúng ta hiển thị tuần tự các số 2n—k và k trên chỉ báo. Nếu ít nhất một trong các số này bằng nhau thì chúng ta chuyển sang số lẻ tiếp theo k+2 và lặp lại các bước trên cho đến khi số lẻ tương ứng không vượt quá n. Sau đó, chúng ta tăng số n lên một, tức là chúng ta chuyển sang số lẻ tiếp theo.

Chương trình con để kiểm tra tính nguyên tố của một số dựa trên thuật toán sau, thuật toán này kiểm tra khả năng chia hết cho tất cả các số lẻ, đây cũng là kiểm tra tính nguyên tố. Số đang được kiểm tra được chia cho p - số lẻ đầu tiên lớn hơn 1, thương được làm tròn thành số nguyên, sau đó tích của số chia và số được làm tròn được trừ vào số đang được kiểm tra. Nếu hiệu này bằng 0 thì số đó không phải là số nguyên tố (ước số p này chia nó có mục đích), nhưng nếu hiệu không bằng 0 thì số r được tăng thêm 2 và quy trình tương tự được lặp lại cho đến khi số chia lớn hơn thương.

Thuật toán này có thể được viết bằng ngôn ngữ thuật toán được nêu trong sách giáo khoa khoa học máy tính của bạn, như sau:

Và đây là chương trình bằng ngôn ngữ BEISIC:
1 IN “GOLDVAKH CHET”
2 INPUT «N», N: N — 2
3 N=N+2: K=1: Y=0
4 K=K+2: P=N-K: M=P-K
5 IF M<0 THEN 3
6 X=K: GOSUB 10: IF X=0 THEN 4
7 X=P: GOSUB 10: IF X=0 THEN 4
8 Y=Y+1: PRINT N, K; «+»; P, «Y»; Y
9 GOTO 4
10 IF X=3; GOTO 16
11 FOR D=3 TO X STEP 2
12 C=X/D: INT C
13 IF C=E; X=0: GOTO 16
14 IF C<D THEN 16
15 NEXT D
16 RETURN
