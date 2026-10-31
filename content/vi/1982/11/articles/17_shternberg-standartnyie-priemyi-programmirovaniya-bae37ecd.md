---
id: 1982-11-shternberg-standartnyie-priemyi-programmirovaniya-bae37ecd
issue: kvant_1982_11
year: 1982
number: "11"
title: Kỹ thuật lập trình tiêu chuẩn
authors:
  - Штернберг Л. Ф.
rubric: raznoe
rubric_sub: Разное
page_first: 64
page_last: 66
page_labels: 62, 64
tag: B1OF
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 18a4b8218761b93a1df9f08fab54eb9e2f579197dab4df8323419c4ff7494551
prompt_sha256: draft-1
translated_from: content/ru/1982/11/articles/17_shternberg-standartnyie-priemyi-programmirovaniya-bae37ecd.md
source_content_sha256: b71b60a5fe3f3f12f5a315692abc813abd608d8dd15bc9e94e4aa8b6d49f50ad
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 62⟧

Nghệ thuật lập trình

Kỹ thuật lập trình tiêu chuẩn
Bài 2. Tìm kiếm tuyến tính

Bài toán tìm kiếm là một trong những tìm kiếm phổ biến nhất: chúng phát sinh khi xây dựng trình dịch và trong nhiều chương trình, lớn và nhỏ mà bạn gặp phải. Nếu tìm kiếm trong một tệp hoặc nếu mảng đang được tìm kiếm không có thứ tự (nghĩa là giá trị của một phần tử không thể biết nó nằm ở đâu), thì loại tìm kiếm duy nhất có thể là tìm kiếm tuyến tính, trong đó thông tin lập trình được thực hiện từ đầu đến cuối, từng phần tử. Hơn nữa, mảng có thứ tự nhưng có độ dài nhỏ; không có ích gì khi sử dụng bất cứ thứ gì phức tạp hơn tìm kiếm tuyến tính. Như vậy cả ba đều là chuẩn bị bài toán*)

*) Xem Bài 1, «Kvant» Số 10.

Lời giải
Trong tất cả các giải pháp: x là giá trị đã cho, k là chỉ số mong muốn

a)
Bài toán 1 (cái đầu tiên khớp)
i:=1; k:=0;
while (i<=n) AND (k=0) do
begin
if a[i]=x then k:=i;
i:=i+1
end;

b)
for k:=1 to n do
if a[k]=x then goto 7;
k:=0;
7:...

Bài toán 2 (cái cuối cùng phù hợp)

k:=0;
for i:=1 to n do
if a[i]=x then k:=i;

bài toán 3 (tháng phù hợp)
k:=0; i:=1; j:=0;
while (i<=n) AND (k=0) do
begin j:=j+1;
if j=m then k:=i
end;
i:=i+1
end;

j:=0;
for k:=1 to n do
if a[k]=x then
begin j:=j+1;
if j=m then goto 7;
end;
k:=0;
7:...

62

⟦folio 64⟧

Hình 1.

Hình 2.

Hình 3.

đầu tiên họ cắt dọc theo những mặt phẳng vuông góc với nhau đi qua tâm của nó - hóa ra là 8 mảnh; sau đó, họ thực hiện một đường cắt xiên thứ tư, chia tất cả các mảnh này, ngoại trừ phần “phía sau”, thành hai - hóa ra là 15 miếng, nhưng một trong số chúng (cụ thể là phần giữa - phần bột giấy có thể gập lại nhiều nhất của phần “tám” phía trước) không có lớp vỏ. Có 14 lớp vỏ còn lại từ arb này. Các lựa chọn cắt khác cũng có thể thực hiện được.

Tổng biên tập - Viện sĩ I. K. Kikoin
Phó Tổng biên tập thứ nhất - Viện sĩ A. N. Kolmogorov
Phó tổng biên tập: M. N. Danilcheva, V. A. Leshkovtsev, Yu. P. Solovyov

Tuyển tập biên tập: L. G. Aslamazov, M. I. Bashmkov, V. E. Belonuchkin, V. G. Boltyansky, A. A. Borovoy, Yu. M. Bruk, V. V. Vavilov, N. B. Vasiliev, S. M. Voronin, V. V. Gnedenko, V. L. Gutenkhmer, N. P. Dolbilin, V. N. Dubrovsky, A. N. Zemlykov, A. R. Zilberman, S. M. Kozel, S. S. Krotov, L. D. Kudryavtsev, A. A. Minailov, E. M. Nikishin, S. P. Novikov, M. K. Potapov, V. G. Razumovsky, N. A. Rodina, N. H. Rozov, A. P. Savin, Ya. A. Smorodinsky, A. B. Sosinsky, V. M. Uroev, V. A. Fabrikant

Ban biên tập: A. M. Baldin, S. T. Belyaev, B. B. Bukhovtsev, E. P. Velikikhov, I. Ya. Verchenko, B. V. Vozdvijzhensky, G. V. Dorofeev, N. A. Ermolaeva, A. P. Ershov, Yu. B. Ivanov, L. V. Kantorovich, P. L. Kapitsa, V. A. Kirillin, G. L. Kotkin, R. N. Kuzmin, A. A. Logunov, V. V. Mozhaev, V. A. Orlov, N. A. Patrikeeva, A. V. Peryshkin, R. Z. Sagdeev, S. L. Sobolev, A. L. Stasenko, I. K. Surin, E. L. Surkov, L. D. Faddeev, V. V. Firsov, G. N. Ykovlev.

Số đã được phát hành:
B. Galkin, L. Denisenko, M. Dubach,
N. Kuzmin, E. Nazarov, A. Permin, E. Tenchurina

Trưởng biên tập L. Chernova
Biên tập nghệ thuật T. Makarova
Người hiệu đính M. Medvedskaya

103006, Mátxcơva, K-6, st. Gorki, 32/1,
«Kvant», điện thoại. 251-82-42

Giao hàng vào ngày 17/9/82. Ký xuất bản ngày 3 tháng 11 năm 1982.
in offset
Giấy 70×108 1/16. Vật lý. lò 4
Lò nướng có điều kiện l. 5.60 Biên tập học thuật. tôi. 7.15 T-20908
Giá 40 kopecks. Đặt hàng 2378 Phát hành 175.067 bản.

Huân chương Lao động Đỏ
Nhà máy in Chekhov
VO "Soizpolgrafprom"
Ủy ban Nhà nước Liên Xô
cho công việc xuất bản và in ấn
và buôn bán sách
Chekhov, khu vực Moscow
