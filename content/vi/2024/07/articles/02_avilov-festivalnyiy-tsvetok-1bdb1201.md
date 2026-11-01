---
id: 2024-7-avilov-festivalnyiy-tsvetok-1bdb1201
issue: kvant_2024_7
year: 2024
number: "7"
title: lễ hội hoa
authors:
  - Авилов Н. И.
rubric: igry-i-golovolomki
rubric_sub: Игры и головоломки
page_first: 2
page_last: 3
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 5ea9b47d733cf76c8725112318cee674b64cf3c1b381e21a6832967e36ab33c6
prompt_sha256: draft-1
translated_from: content/ru/2024/07/articles/02_avilov-festivalnyiy-tsvetok-1bdb1201.md
source_content_sha256: 938b690341ac15701a349f145b9ae0986adc02633b978a146fd11c07222b2548
translation_model: draft
translation_run: vi-draft-gaps-2026-11-02
translation_quality: draft
---

⟦folio none⟧

---
running_head:
folio:
---

Ước tính
Hoa

Câu đố được thực hiện cho Đại hội Giới trẻ Thế giới lần thứ 19 và
sinh viên, được tổ chức tại Sochi vào năm 2017. Không giống như một câu đố
“Chốt lễ hội”, được mô tả trong «Kvant» số 3 năm 2018, câu đố này không được sản xuất hàng loạt. Chỉ có một vài bản sao tự chế của nó.

Câu đố bao gồm hai chiếc đĩa giống hệt nhau có hình bông hoa lễ hội với các cửa sổ trong đó các cánh hoa hai lớp nhô ra với một trục quay chung. Các cặp cánh hoa ở mỗi cửa sổ trong số năm cửa sổ có thể được lật sang phía bên kia xung quanh trục. Cả hai đĩa đều được gắn chặt bằng vít ở giữa, do đó chúng có thể xoay tương đối với nhau một góc là bội số của 72°. Nếu bạn thực hiện lần lượt nhiều thao tác như vậy, màu sắc ban đầu của cánh hoa cúc sẽ bị phá vỡ. Mục tiêu của người chơi là khôi phục màu này. Hóa ra nó là một loại khối Rubik phẳng.

Câu đố có thể được thực hiện ở nhà. Các đĩa và cửa sổ của chúng được cắt ra bằng ghép hình từ một tấm dày 4mm. Kích thước được hiển thị ở hình. Một lỗ được khoan ở giữa mỗi đĩa; các đĩa xếp chồng lên nhau được cố định bằng vít. Các đĩa được gắn chặt được đặt trong một cái kẹp và năm lỗ xuyên qua được khoan, dọc theo trục đối xứng cho mỗi cửa sổ, trong đó trục của các cặp cánh hoa gặp nhau.

Bằng cách xoay các phần tử câu đố một cách ngẫu nhiên, không thể tìm thấy lời giải - xét cho cùng, câu đố có hơn 100 nghìn (10!/2^5) trạng thái khác nhau và chỉ có một trạng thái đúng. Để thành công, bạn cần hiểu mô hình chuyển động của cánh hoa cúc trong trò chơi và phát triển thuật toán lời giải cho câu đố này.

Chúc may mắn!

N. Avilov

⟦folio none⟧

---
running_head:
folio:
---

QUANTUM THÁNG 7 NĂM 2024 Số 7
Tạp chí VẬT LÝ VÀ TOÁN HỌC PHỔ BIẾN
XUẤT BẢN TỪ THÁNG 1 NĂM 1970

Trong phòng:

NHÀ SÁNG LẬP
Viện Hàn lâm Khoa học Nga
Viện toán học
họ. V.A. Steklova RAS
Viện vật lý
họ. P.N.Lebedev RAS
Mátxcơva
Viện Vật lý và Công nghệ
Trung tâm liên tục Moscow
giáo dục toán học

TỔNG BIÊN TẬP
A.A.Gaifullin
BAN BIÊN TẬP
L.K. Belopukhov, M.N. Bondarov,
S.D.Varlamov, A.P.Veselov,
MỘT. Vilenkin, N.P. cá heo,
S.A. Dorichenko, V.N. Dubrovsky,
A.A.Zaslavsky, A.Ya.Kanel-Belov,
K.A.Knop, P.A.Kozhevnikov,
S.P.Konovalov, K.P.Kokhas, S.L.Kuznetsov,
A.A.Leonovich, A.B.Mineev, V.IO.Protasov,
A.M.Raigorodsky, A.B.Sosinsky,
A.L. Stasenko, V.G. Surdin,
V.M.Tikhomirov, V.A.Tikhomirova,
A.V. Ustinov (phó giám đốc
biên tập viên), A.I. Chernoutsan
(Phó tổng biên tập)

BAN BIÊN TẬP
V.I. Bernik, AA Borovoy,
V.V. Kozlov, S.P. Novikov,
A.J.L. Semenov, S.K. Smirnov,
A.P.Khokhlov

BAN BIÊN TẬP
1970
TỔNG BIÊN TẬP
I.K.Kikon
PHÓ THỨ NHẤT
TỔNG BIÊN TẬP
MỘT. Kolmogorov
L.A. Artsimovich, M.I. Bashmkov, V.G. Boltyansky,
TRONG. Bronshtein, N.B. Vasiliev, I.F. Ginzburg,
V.G.Zubov, P.L.Kapitsa, V.A.Kirilin,
G.I.Kosurov, V.A.Leshkovtsev, V.P.Lishevsky,
A.I. Markushevich, MD Milliontskov,
N.A. Patrikeva, N.X. Rozov, A.P. Savin,
I.Sh.Slobodetsky, M.L.Smolyansky,
Y.A. Smorodinsky, V.A. Nhà chế tạo, Y.E. Schneider

2 chuyến bay giữa các vì sao: giấc mơ và hiện thực.
M.Nikitin
11 Ứng dụng của định lý Bolzano-Cauchy.
D. Bavrin

THẾ GIỚI TOÁN HỌC
15 Để tưởng nhớ Sergei Petrovich Novikov
16 Vật lý lý thuyết và hiện đại
toán học. S. Novikov

VẤN ĐỀ "Lượng tử"
18 Bài toán M2802-M2805, F2809-F2812
19 Lời giải bài toán M2786-M2793, F2793-F2796

CUỘC THI ĐẶT THEO A.P. SAVINA
29 Kết quả thi đua năm học 2023/24

“SỐ LƯỢNG” CHO HỌC SINH THI
30 Bài toán

VÒNG TRÒN TOÁN HỌC
31 "Dễ lời giải một khó
hình học bài toán". K. Kozerenko,
A.Gerasimova, A.Luzgina

KÍNH KÍNH KÍNH “QUANTA”
32 quỹ đạo

PHÒNG THÍ NGHIỆM "QUANTA"
36 Dòng Foucault và trọng lực. S.Gerasimov

Thế Vận Hội
40 Giai đoạn cuối cùng của L Toàn Nga
Olympic toán học dành cho học sinh

VẬT LIỆU KIỂM TRA
43 Đại học Nghiên cứu Quốc gia
"Miệt"

47 Đáp số, gợi ý, lời giải

TRÊN BÌA
Ⅰ Minh họa bài viết của M. Nikitin
Ⅱ Bộ sưu tập câu đố
Ⅲ Trang cờ vua
Ⅳ Đi bộ kết hợp tập thể dục
