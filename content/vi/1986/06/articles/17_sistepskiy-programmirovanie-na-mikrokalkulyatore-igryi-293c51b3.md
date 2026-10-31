---
id: 1986-6-sistepskiy-programmirovanie-na-mikrokalkulyatore-igryi-293c51b3
issue: kvant_1986_6
year: 1986
number: "6"
title: 'Lập trình trên máy vi tính: trò chơi'
authors:
  - Систепский Л. Н.
rubric: raznoe
rubric_sub: Разное
page_first: 44
page_last: 45
page_labels: 42-43
tag: GDCK
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 4c2e1cd327215678eb44a95ba74da6e07e8d3dbc97b18be9e33fb8d6c68a061e
prompt_sha256: draft-1
translated_from: content/ru/1986/06/articles/17_sistepskiy-programmirovanie-na-mikrokalkulyatore-igryi-293c51b3.md
source_content_sha256: 6ba947e60237a63557a03f85207d4060b7ff848f405e4e5b7a4190fe7f70cac7
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 42⟧

Lập trình trên máy vi tính: trò chơi

L. N. SISTEPSKY

Bài viết chủ yếu dành cho học sinh lớp chín đang nghiên cứu các nguyên tắc cơ bản của công nghệ thông tin và máy tính cũng như có quyền truy cập vào máy tính vi mô có thể lập trình, nhưng nó cũng sẽ thu hút sự quan tâm của tất cả những người sử dụng máy tính vi mô như vậy.

Trong năm học, bạn đã học viết chương trình bằng ngôn ngữ thuật toán. Trên các trang của tạp chí «Kvant», chúng tôi đã giải thích cách dịch các chương trình này thành mã cho máy tính vi mô có thể lập trình (xem «Kvant», 1985, Số 2, 3). Những kỹ năng này cho phép bạn sử dụng cáp của mình cho các khóa học toán lời giải ở trường bài toán, chẳng hạn như tìm nghiệm của các phương trình đại số.

Đây không phải là vấn đề của tương lai. Và bây giờ, trước kỳ nghỉ hè, chúng tôi mời bạn tạm dừng môn toán bài toán và chơi trò chơi bằng máy tính vi mô có thể lập trình của bạn.

trò chơi basshe

Từ một chồng chứa $p$ vật phẩm, chẳng hạn như que diêm, hai người chơi thay phiên nhau tham gia một số lượng que diêm nhất định. Bạn có thể lấy ít nhất một và không quá $k$ trận đấu cùng một lúc. Số $k$ (tốt hơn nên chọn ít hơn $p$) do người chơi ấn định trước. Người phải thực hiện trận đấu cuối cùng sẽ thua.

Nhập chương trình trong Bảng 1 vào máy, trước tiên lấy một bộ diêm, di chuyển cùng các vật phẩm khác và đọc kỹ hướng dẫn, bắt đầu trò chơi. Bạn có thể chơi với máy một chọi một. Sau khi chắc chắn rằng máy là một đối tác mạnh mẽ, hãy cho phép một người bạn giúp đỡ và cố gắng cùng nhau chơi với máy.

Hướng dẫn

1. Nhập chương trình B/O.
2. 1 VP 7 P 7 1, 8 F 1/x P/8.
3. $p$ C/P $(p)$, $k$ C/P (0).
4. Nếu máy thực hiện nước đi đầu tiên, sau đó nhập C/P (số trận đấu được máy thực hiện), nhập nước đi C/P của bạn (nước đi của máy) và nhập lại nước đi của bạn, v.v.
5. Nếu bạn muốn thực hiện nước đi đầu tiên thì hãy nhập số trận đấu bạn đã thực hiện, C/P (nước đi về của máy), nước đi C/P của bạn (nước đi của máy), v.v.
6. Đối với trò chơi mới: B/O và chuyển sang bước 3 của hướng dẫn.
7. Bài toán
1 (dành cho người yêu toán). Cho $p$ và $k$, hãy tìm chiến lược chiến thắng trong trò chơi Basshe.
2* (dành cho người đam mê lập trình). Cố gắng giải mã chiến lược của máy.

trò chơi đạn đạo

Hình ảnh hệ tọa độ trên giấy ca rô, một khung cảnh kỳ lạ và hai thành phố của người Gulpians, đối lập nhau (hình). Trong mỗi thành phố, hãy đặt ra quy trình xuất phát và đánh dấu bằng các dấu chấm vị trí của súng (đại bác), từ đó những cư dân vô lý của thành phố đối phương sẽ bắn pháo vào nhau. Nhập chương trình ở Bảng 2 vào máy, nhấn B/O, nhập dữ liệu theo hướng dẫn.

Bảng 1

00 P 0 40 24 F Trong 0
01 C/P 50 25 – 11
02 ↑ 0E 26 IP 1 61
03  1 01 27  /-/ 0L
04  + 10 28  × 12
05 P 1 41 29 IP 0 60
06  0 00 30  + 10
07 C/P 50 31 1 01
08  F x≠0 57 32  — 11
09  15 15 33  F x≠0 57
10  /-/ 0L 34 44 44
11 ↑ 0E 35 P 2 42
12 IP 0 60 36 /-/ 0L
13  + 10 37  ↑ 0E
14 P 0 40 38 IP 0 60
15 IP 0 60 39 + 10
16 1 01 40 P 0 40
17 - 11 41 IP 2 62
18 IP 1 61 42 BP 51
19  ÷ 13 43 07 07
20 IP 8 68 44 1 01
21 - 11 45 P 2 42
22 IP 7 67 46 BP 51
23  + 10 47 36 36

⟦folio 43⟧

Bảng 2

| | | | | | |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 00 | IP 3 | 63 | 34 | + | 10 |
| 01 | F sin | 1[ | 35 | P 0 | 40 |
| 02 | IP 2 | 62 | 36 | IP A | 6— |
| 03 | × | 12 | 37 | IP 3 | 63 |
| 04 | P 0 | 40 | 38 | + | 10 |
| 05 | IP 3 | 63 | 39 | P A | 4— |
| 06 | F cos | 1G | 40 | IP S | 6[ |
| 07 | IP 2 | 62 | 41 | IP 6 | 66 |
| 08 | × | 12 | 42 | — | 11 |
| 09 | IP 8 | 68 | 43 | P S | 4[ |
| 10 | × | 13 | 44 | IP 0 | 60 |
| 11 | P 3 | 43 | 45 | IP 9 | 69 |
| 12 | IP 0 | 60 | 46 | × | 12 |
| 13 | P 2 | 42 | 47 | IP 2 | 62 |
| 14 | IP 6 | 66 | 48 | + | 10 |
| 15 | F sin | 1[ | 49 | IP 0 | 60 |
| 16 | IP 5 | 65 | 50 | × | 12 |
| 17 | × | 12 | 51 | IP 1 | 61 |
| 18 | P 0 | 40 | 52 | + | 10 |
| 19 | IP 6 | 66 | 53 | P V | 4↓ |
| 20 | F cos | 1G | 54 | IP 0 | 60 |
| 21 | IP 5 | 65 | 55 | IP 9 | 69 |
| 22 | × | 12 | 56 | × | 12 |
| 23 | IP 8 | 68 | 57 | IP 5 | 65 |
| 24 | × | 12 | 58 | + | 10 |
| 25 | P 6 | 46 | 59 | IP 0 | 60 |
| 26 | IP 0 | 60 | 60 | × | 12 |
| 27 | P 5 | 45 | 61 | IP 4 | 64 |
| 28 | 0 | 00 | 62 | + | 10 |
| 29 | P 0 | 40 | 63 | P D | 4G |
| 30 | P V | 4↓ | 64 | C/P | 50 |
| 31 | P D | 4G | 65 | phó chủ tịch | 51 |
| 32 | IP 0 | 60 | 66 | 32 | 32 |
| 33 | IP 8 | 68 | | | |

Hướng dẫn

1. Nhập chương trình. Di chuyển công tắc đo góc sang vị trí Г (độ), В/О;
2. Nhập dữ liệu:
   $Y_1$; P 1; $v_1$; P2; $\alpha_1$; P3; $Y_2$, P 4; $v_2$; P 5; $\alpha_2$; P6; 1; P 8; 5; /—/; P 9; $X_1$; PA; $X_2$; Tái bút.
3. S/P;
4. Kết quả: IP A ($X_1$) IP B ($Y_1$) IP C ($X_2$) IP D ($Y_2$)
5. Tiếp tục đến bước 3 của hướng dẫn.
Ý nghĩa của dữ liệu như sau:
$Y_1$ — khẩu pháo của thành phố đầu tiên (ở bên trái); $v_1$ là tốc độ ban đầu của pháo bay ra khỏi khẩu pháo này;
$\alpha_1$ — góc ngắm của khẩu pháo đầu tiên (xem hình) tính bằng độ;
$Y_2$ — thứ tự của khẩu pháo được lắp đặt ở thành phố thứ hai (bên phải);
$v_2$ là tốc độ ban đầu của pháo thứ hai;
$\alpha_2$ — góc ngắm của khẩu pháo thứ hai (xem hình) tính bằng độ;

Khởi động chương trình bằng phím C/P. Trục hoành và tọa độ của khẩu pháo bắn từ thành phố thứ hai sẽ được nhập vào thanh ghi A và B. Bằng cách nhấn C/P, bạn sẽ có được vị trí của khẩu pháo sau 1 giây nữa, v.v. Trong khi máy đang tính toán, hãy offset các vị trí của khẩu pháo trên bản vẽ. Người chiến thắng là người (đầu tiên) đánh được phần sân cũ của đối phương.

Trong sổ đăng ký 8 (xem hướng dẫn) trước khi bắt đầu trò chơi, 1 sẽ được ghi. Bạn có thể nhập bất kỳ số t nào, từ đó thay đổi khoảng thời gian giữa các lần đọc riêng lẻ của máy (bạn có thể ngắt các vị trí của cái vỗ không phải mỗi giây mà cứ sau 2 giây hoặc 0,5 giây, v.v.). Thanh ghi 9 sẽ chứa các giá trị - g/2, trong đó g là độ lớn của gia tốc rơi tự do tính bằng m/giây². Chúng tôi đặt g=10. Nếu người Gulepian không sống trên Trái đất mà trên Mặt trăng, thì bạn cần chọn g ít hơn 6 lần. Nói tóm lại, bạn có rất nhiều khả năng để tưởng tượng về sự phẫn nộ có thể xảy ra của người Guleptians. Bất kỳ ai hiểu rõ hơn về vật lý và các điều kiện chuyển động sẽ có cơ hội tốt để mô phỏng quá trình chuyển động của vật thể trong trường hấp dẫn.
