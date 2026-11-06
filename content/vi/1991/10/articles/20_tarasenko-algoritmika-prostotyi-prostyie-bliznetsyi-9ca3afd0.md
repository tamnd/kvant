---
id: 1991-10-tarasenko-algoritmika-prostotyi-prostyie-bliznetsyi-9ca3afd0
issue: kvant_1991_10
year: 1991
number: "10"
title: Thuật toán đơn giản. Cặp song sinh đơn giản
authors:
  - Тарасенко Б.
rubric: raznoe
rubric_sub: Разное
page_first: 65
page_last: 67
page_labels: 63-65
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 168a0a376c8fd9b8f01046084b1c763c31c456cd490e51f98e5eb2508ab8e4f9
prompt_sha256: draft-1
translated_from: content/ru/1991/10/articles/20_tarasenko-algoritmika-prostotyi-prostyie-bliznetsyi-9ca3afd0.md
source_content_sha256: b3fb60818a8f5b13bdbee5e5989984c4b68d261c4f719dc4f7f21f411e7e838b
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 63⟧

---
running_head:
folio:
---

Thuật toán
sự đơn giản
Cặp song sinh đơn giản
V. TARASENKO

Đó không phải là một câu hỏi dễ dàng,
Không có nhiều hơn một điều:
Mọi thứ đều phức tạp và đơn giản,
Đếm nó ra khỏi tâm trí của bạn!

Về bản chất, điểm tương đồng là những vật thể rất giống nhau; món ăn tuyệt vời là một điều đáng chú ý "hơi". Trong toán học về các số nguyên tố, “một chút” này được định nghĩa một cách chính xác, liên tục và bằng hai. Đây là những “nhân đôi” toán học đầu tiên: (3; 5), (5; 7), (11; 13), (17; 19), (29; 31), (41; 43), (59; 61), (71; 73), (101; 103), (107; 109), v.v. Cặp cặp (3; 5), (5; 7) là duy nhất - đó là cặp song sinh duy nhất có phần tử chung (tính duy nhất dễ dàng được chứng minh bằng cách chia hết cho ba).

Có nhiều số nguyên tố giống nhau không?
Trong mười số đầu tiên có hai cặp (và số nguyên tố là bốn), trong hàng trăm số đầu tiên có tám (với 25 số nguyên tố). Có giả thuyết cho rằng tập hợp các cặp số nguyên tố giống nhau là vô hạn. Giả thuyết này vẫn chưa được chứng minh hoặc bác bỏ. Tuy nhiên, số nguyên tố gần rõ ràng ít phổ biến hơn số nguyên tố. Nhưng ít thường xuyên hơn bao nhiêu?

Bạn có cảm thấy rằng đã có sẵn hai chú dê nhỏ cụ thể trong bộ phim hoạt hình nổi tiếng, những người biết cách và muốn (vì lợi ích của việc luyện tập!) để đếm mọi thứ không? Bạn hiểu rồi. Chúng tôi thực sự muốn cung cấp cho bạn một công cụ phần mềm khác: một công cụ đếm tiên tiến về các trận bão tuyết số đơn giản.

Chủ đề về sự gần gũi hoặc thậm chí hoàn toàn giống nhau nảy sinh nhiều lần trong đó. Mục tiêu chính là tìm các cặp số nguyên tố, nghĩa là chương trình phải kiểm tra tính nguyên tố hai lần. Trong những trường hợp như vậy, lời bài hát sẽ cứu booga bằng cách trích dẫn đoạn đó một lần rồi đề cập đến đoạn đó bằng một từ: “điệp khúc”. Ví dụ:

Có một phong trào của bọn cướp,
Có Kudeyar-ataman,
Bọn cướp uống rất nhiều
Máu của các Kitô hữu thuần khiết.

Điệp khúc:

Chúng ta hãy cầu nguyện với Chúa giàu có,
Chúng tôi cân cái cổ xưa,
Anh ấy đã kể điều đó với chúng tôi ở Solovki
Tu sĩ, Pitirim thuần khiết.

Nhiều của cải bị đánh cắp
Họ sống trong một khu rừng rậm rạp.
Lãnh đạo-Kudeyar từ gần Kiev
Anh ta đưa cô gái xinh đẹp ra ngoài.

Điệp khúc

Trong lập trình, "điệp khúc" được gọi là chương trình con. Khi được truy cập từ chương trình chính, “điệp khúc” này được thực thi và sau đó quyền điều khiển được chuyển trở lại chương trình chính. Vì vậy, chúng tôi đã thực hiện chương trình dưới dạng “bài hát có điệp khúc” - một chương trình con (bước 33-55). Phần chính của nó được hình thành bởi công cụ lập trình nối tiếp số 1 của chúng tôi, được sửa đổi phù hợp. Người đọc có cơ hội biến hai phần tương tự khác thành một chương trình con khác. Tại đây, bạn có thể nhận được cái gọi là chương trình con đầu ra - “điệp khúc” đến “điệp khúc” hoặc bạn có thể tạo một chương trình con mở rộng. Lợi ích mong đợi từ hoạt động này là ba bước lệnh trở lên.

Bạn cũng có thể giành được một bước khi thực hiện các lệnh chỉ báo. Người đọc biết làm thế nào. Nếu không thì không có sự đổi mới cơ bản.

Chúng ta đã thực hiện “phần trăm” sau lũy thừa mười của số nguyên tố. Không dài dòng nữa, chúng ta hãy làm điều tương tự cho cặp song sinh. Ở đây, sau lũy thừa mười, số cặp được ghi trong ngoặc đơn, sau đó

⟦folio 64⟧

---
running_head:
folio:
---

Chương trình số 5. ​​Đếm bộ tạo lũy thừa của các số chớp nhoáng đơn giản

00 X→Π 6 46 /+ Chuyển từ PrX sang Pr6 của số lẻ bắt đầu
01 0 00 /+ Không đổi số 0
02 C/Π 50 /+ Stopp—chỉ báo số 0, lời mời nhập số
03 F X=0 57 /+ Nội dung PrX không bằng 0?
04 02 02 /+ NO, PrX=0, chuyển sang bước 02 (rào cản đối với đầu vào 0)
05 b→Π 4 44 /+ CÓ, một số khác 0 được nhập vào, gửi nó đến Pr4
06 BP 51 /+ Nhảy vô điều kiện
07 10 10 /+ mỗi bước 10
08 K P→X 6 G6 /+ Thêm 1 vào số kiểm tra trong Pr6
09 K P→X 6 G6 /+ Thêm 1 nữa vào số được kiểm tra
10 PP 53 /+ Tới chương trình con
11 33 33 /+ tại địa chỉ 33 để kiểm tra tính nguyên tố của số lẻ. con số
12 F X≠0 57 /+ Nội dung của PrX không bằng 0?
13 08 08 /+ KHÔNG, PrX=0, số đang xét không phải là số nguyên tố, chuyển sang bước 08
14 P→X 6 66 /+ CÓ, PrX≠0, số đang được kiểm tra là số nguyên tố, gọi nó từ Pr6 đến PrX
15 X→Π a 4— /+ Cố định số nguyên tố đầu tiên trong PrA
16 K P→X 6 G6 /+ Thêm 1 vào số kiểm tra trong Pr6
17 K P→X 6 G6 /+ Thêm 1 nữa vào số được kiểm tra
18 PP 53 /+ Tới chương trình con
19 33 33 /+ tại địa chỉ 33 để kiểm tra tính nguyên tố của số lẻ. con số
20 F X≠0 57 /+ Nội dung của PrX không bằng 0?
21 08 08 /+ KHÔNG, PrX=0, số đang xét không phải là số nguyên tố, chuyển sang bước 08
22 P→X 6 66 /+ CÓ, PrX=0, số đang được kiểm tra là số nguyên tố, gọi nó từ Pr6 đến PrX
23 X→Π b 4L /+ Cố định số nguyên tố thứ hai trong PrB
24 P→X a 6— /+ Gọi một người hàng xóm trẻ hơn từ PrA đến PrX
25 C/Π 50 /+ Storp—chỉ số thấp nhất—gần nhất
26 P→X b 6L /+ Gọi hàng xóm cấp cao từ PrB đến PrX
27 C/Π 50 /+ Storp—chỉ số cao nhất—gần nhất
28 P→X 4 64 /+ Gọi PrX nội dung của bộ đếm số sê-ri cặp
29 C/Π 50 /+ Storp—chỉ số sê-ri của một cặp Blizzard
30 K P→X 4 G4 /+ Tăng thêm 1 bộ đếm Pr4 của số sê-ri
31 BP 51 /+ Nhảy vô điều kiện
32 08 08 /+ mỗi bước 08
33 1 01 /+ Bắt đầu chương trình con, hằng số 1
34 X→Π 5 45 /+ Zasylak 1 trong Pr5=D, D là ước số
35 K P→X 5 G5 /+ Thêm 1 vào bộ đếm Pr5
36 K P→X 5 G5 /+ Thêm 1 số nữa vào bộ đếm Pr5
37 P→X 6 66 /+ Gọi số kiểm tra hiện tại trong PrX AND từ Pr6
38 P→X 5 65 /+ Gọi bộ chia hiện tại D từ Pr5 vào PrX, AND đi tới PrX
39 13 /+ PHẦN=I/D
40 b→Π 9 49 /+ Zasylaka PHẦN trong Pr9
41 K P→X 9 G9 /+ K=phần nguyên của PHẦN
42 P→X 6 66 /+ Gọi I trong PrX
43 P→X 9 69 /+ Gọi K trong PrX; Và chuyển đến PrY
44 P→X 5 65 /+ Gọi D trong PrX; PrY=K; PrZ=VÀ
45×12 /+D×K
46 - 11 /+ OST=I-K×D, phần dư của phép chia
47 F X≠0 57 /+ OST≠0?
48 55 55 /+ NO (tức là OST=0), thoát khỏi chương trình con bằng 0 đến bước 55
49 P→X 9 69 /+ CÓ (tức là OST≠0), đầu ra số nguyên PHẦN
50 P→X 5 65 /+ Gọi D từ Pr5 đến PrX
51 — 11 11 /+ PrX=PHẦN—D
52 F X<0 5C /+ PHẦN—D<0?
53 35 35 /+ KHÔNG, chuyển sang bước 35 đến giá trị mới D
54 P→X 6 66 /+ CÓ (bộ D đã hết), gọi AND trong PrX
55 B/O 52 /+ Quay lại chương trình chính với số 0 hoặc số nguyên tố

10⁰(8): (3; 5), (5; 7), (11; 13), (17; 19), (29; 31), (41; 43), (59; 61), (71; 73); (101; 103).

10¹(8): (11; 13), (17; 19), (29; 31), (41; 43), (59; 61), (71; 73), (1; 3), (7, 9); (137, 139).

⟦folio 65⟧

---
running_head:
folio:
---

10^2(7): (1; 3), (7; 9), (37; 39), (49; 51), (79; 81), (91; 93), (97; 99); (227; 229).

10^3(5): (19; 21), (31; 33), (49; 51), (61; 63), (91; 93); (151; 153).

10^4(4): (7; 9), (37; 39), (67; 69), (91; 93); (139; 141).

10^5(0): (151; 153).

10^6(1): (37; 39); (211; 213).

10^7(0): (139; 141).

10^8(1): (37; 39); (167; 169).

Hãy chuyển trực tiếp đến chương trình. Nó hoạt động trên MK-61, nó phù hợp và tất cả các chương trình đều tương thích với gia đình. Để khởi động nó, sau khi nhập chương trình vào PMC, bạn phải thực hiện thủ công các thao tác sau.

Nhấn phím B/O, quay số nguyên dương lẻ ban đầu không nhỏ hơn 5. Sau đó nhấn phím C/P. Số 0 sẽ xuất hiện trên chỉ báo. Đây là lời mời quay số giá trị ban đầu của bộ đếm số sê-ri Blitz. Bạn có thể quay số một. Nếu bạn biết chính xác số sê-ri của cặp Blitzes cũ, hãy quay số nhỏ hơn của Blitzes làm số lẻ ban đầu, sau đó, sau C/P và sự xuất hiện của số 0, số sê-ri đã biết này.

Sau đó nhấn phím C/P và khi súng phụ dừng lại, số đầu tiên trong số đôi sẽ xuất hiện trên đèn báo. Sau khi nhấn phím C/P, phím thứ hai sẽ xuất hiện và sau phím C/P tiếp theo, số sê-ri tương đối của cặp song sinh này sẽ xuất hiện. Những lần nhấn phím C/P mới sẽ dẫn đến sự xuất hiện của các cặp sinh đôi mới, v.v.

(Để bắt đầu, xem trang 62)

4,5 giờ, mỗi bài toán trị giá 10 điểm. Sau số bài toán quốc gia đề xuất nó được ghi trong ngoặc đơn.

Ngày đầu tiên

1 (Argentina). Cho f là một hàm được xác định trên tập hợp các số nguyên không âm và thỏa mãn hai điều kiện sau:

1) nếu n = 2^i - 1 với i = 0,1,2,..., thì f(n) = 0.
2) nếu n ≠ 2^i - 1 với i = 0,1,2,..., thì f(n + 1) = f(n) - 1.
a) Chứng minh rằng với mọi số nguyên n ≥ 0 đều tồn tại số nguyên k ≥ 0 sao cho f(n) + n = 2^k - 1.
b) Tìm f(2^1990).

2 (Colombia). Trong tam giác ABC, điểm I là tâm của đường tròn vẽ vào đó và D, E, F lần lượt là các điểm tiếp tuyến của đường tròn này với các cạnh BC, CA và AB. Gọi P là giao điểm khác của đường thẳng AD với đường tròn cong và M là trung điểm của đoạn EF. Chứng minh rằng các điểm P, I, M, D cùng nằm trên một đường tròn hoặc đường thẳng.

3 (Tây Ban Nha). Đặt f(x) = (x + b)^2 - c là một đa thức trong đó b và c là số nguyên. Cho thấy điều đó

a) nếu p là số nguyên tố và c chia hết cho p nhưng không chia hết cho p^2, thì với mọi số nguyên n, số f(n) không chia hết cho p^2,
b) nếu q là số nguyên tố không bằng 2 sao cho c không chia hết cho q và f(n) chia hết cho q với một số nguyên n, thì với bất kỳ số nguyên r nào cũng tồn tại một số nguyên n' sao cho f(n') chia hết cho q'.

Ngày thứ hai

4 (Venezuela). Gọi AB là đường kính của đường tròn c₁. Lấy t tiếp xúc với đường tròn này tại điểm B. Gọi M là một điểm tùy ý trên đường tròn c₁, khác A và B. Ta dựng đường tròn c₂ tiếp xúc với đường tròn c₁ tại điểm M và đường thẳng t.

a) Tìm điểm P tiếp tuyến của đường tròn c₂ với đường thẳng t, cũng như quỹ tích tâm của các đường tròn c₂ nếu điểm M là một biến.

b) Chứng minh rằng tồn tại một đường tròn trực giao với tất cả các đường tròn c₂.

5 (Mexico). Cho A và B là các đỉnh đối diện của con gái có kích thước n × n, được chia thành các ô vuông đơn vị (n ≥ 1). Trong mỗi hình vuông, một đường chéo được vẽ song song với đường thẳng AB, do đó phải có 2n2 hình tam giác bằng nhau. Con chip di chuyển dọc theo các đoạn trên đĩa này từ A đến B và khi đi qua các cạnh của tam giác, hạt sẽ được đặt vào đó. Mỗi đoạn được truyền không quá một lần. Ở cuối con đường, hóa ra mỗi hình tam giác 2n2 chứa đúng 2 hạt. Với giá trị nào của n thì tình huống như vậy có thể xảy ra?

6 (Uruguay). Cho f(x) là đa thức bậc ba có hệ số hữu tỉ. Chứng minh rằng nếu đồ thị của hàm số f(x) tiếp xúc với trục x thì cả ba nghiệm của đa thức f(x) đều hữu tỉ.

Ấn phẩm được chuẩn bị bởi A. Savin
