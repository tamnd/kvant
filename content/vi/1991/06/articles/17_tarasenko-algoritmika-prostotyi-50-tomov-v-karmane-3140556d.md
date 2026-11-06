---
id: 1991-6-tarasenko-algoritmika-prostotyi-50-tomov-v-karmane-3140556d
issue: kvant_1991_6
year: 1991
number: "6"
title: Thuật toán đơn giản. 50 tập trong túi của bạn
authors:
  - Тарасенко Б.
rubric: raznoe
rubric_sub: Разное
page_first: 60
page_last: 61
page_labels: 58-59
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 5fcdc897ff27d99d9f741363bef78284c3804f2406b595b03da18531b3c1b91f
prompt_sha256: draft-1
translated_from: content/ru/1991/06/articles/17_tarasenko-algoritmika-prostotyi-50-tomov-v-karmane-3140556d.md
source_content_sha256: 0d8fd2ae4e401e560557630a36210274de07c65c97ac3371ba4d0a6dd78f5d34
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 58⟧

Thuật toán đơn giản

50 tập trong túi của bạn

V. TARASENKO

Đó không phải là một câu hỏi dễ dàng, nhưng hãy tin một điều:
Mọi thứ đều phức tạp và đơn giản, Hãy tính nó một cách khôn ngoan!

Một ngày nọ vào năm 1948, khi tác giả của những dòng này đang học lớp ba, anh ấy đã mua một cuốn sách tuyệt vời của G. N. Berman, “Số và Khoa học về Nó,” cùng với một ít kem Chủ nhật. Cuốn sách này mãi mãi khiến tôi trở thành người yêu thích môn toán số nguyên, đặc biệt là số nguyên tố. Cuốn sách nhỏ này có thể sẽ được thế hệ những người tìm kiếm bên ngoài quan tâm.

Số nguyên tố từ lâu đã là chủ đề luôn được những người nghiệp dư và chuyên nghiệp chú ý. Hãy nhớ rằng số nguyên tố là số tự nhiên khác 1 và chỉ chia hết cho chính nó và một. Các số nguyên tố đầu tiên là: 2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41,... Dãy số nguyên tố là vô hạn.

Trong các bảng số nguyên tố được công bố, giới hạn trên chung là 6000, ít thường xuyên hơn 10.000. Có thể tạo một bảng gồm các số nguyên tố lên tới 10^8, nhưng hóa ra nó là một ấn bản có nhiều phần (khoảng 50 tập). Có cần thiết không?

Hóa ra nó có thể được thay thế bằng những thứ “đơn giản nhất” trong thế giới máy tính - máy vi tính có thể lập trình. B3-34, MK-52, MK-54, MK-56, MK-61, được trang bị yếu với chương trình thích hợp, có thể đưa ra đáp số chính xác cho nhiều câu hỏi. Hãy bắt đầu với một trình tạo số nguyên tố. Chương trình bên dưới cho phép bạn tạo, bắt đầu từ một số lẻ VÀ, các số nguyên tố liên tiếp. Đồng thời, nó kiểm tra số AND đang nghiên cứu không chia hết cho bất kỳ số lẻ nào trong khoảng từ 3 đến √I. Chương trình được áp dụng từ I=5 đến I=99999989.

Một vài lời về hình thức mô tả chương trình. Chúng tôi tin rằng chúng tôi đang đối phó với loại độc giả mà đối với họ, một chút “thể thao” về tài liệu chỉ hữu ích và mang lại hiệu quả cao hơn. Vì vậy, cuộc hôn nhân của chúng ta sẽ ở mức tối thiểu - vừa đủ để chủ nhân của B3-34 (dòng chữ trên phím khác với dòng chữ trên MK-61) có thể tự mình tìm ra những gì họ cần nhấn.

Chương trình 1. Trình tạo số nguyên tố tuần tự

Tất cả các loại súng phụ từ B3-34 đến MK-61 đều phù hợp. Các biến và thanh ghi: D=Pr5 - ước số lẻ hiện tại; And=Pr6 - sử dụng số lẻ được xếp hạng; PARTIAL=Pr9=I/D - thương của phép chia I cho D (đầu tiên là số thực, sau đó là phần nguyên của nó).

Mô tả thuật toán

Đặt I ban đầu. Đối với D lẻ liên tiếp, bắt đầu từ D=3, tính PART=I/D, sau đó K -

⟦folio 59⟧

---
running_head:
folio:
---

Chương trình TEXT có nhận xét từng bước

00 X→Π 6 46 /+ Nhập điểm bắt đầu AND từ PrX vào Pr6
01 1 01 /+ Hằng số 1
02 X→Π 5 45 /+ Nhập 1 vào Pr5, chuẩn bị bộ đếm D
03 K P→X 5 Γ5 /+ D : =D + 1, pha ban đầu của hoạt động đếm D
04 K P→X 5 Γ5 /+ D : =D + 1; kết quả: newD = starD + 2
05 P→X 6 66 /+ Gọi I = Pr6 trong PrX
06 P→X 5 65 /+ Gọi D trong PrX; Và chuyển đến PrY
07 13 /+ PHẦN = I/D
08 X→Π 9 49 /+ GỬI RIÊNG tới Pr9
09 K P→X 9 Γ9 /+ K = phần nguyên của PART
10 P→X 6 66 /+ Gọi I trong PrX
11 P→X 9 69 /+ Gọi K trong PrX; Và chuyển đến PrY
12 P→X 5 65 /+ Gọi bộ chia D trong PrX; PrY = K; PrZ=VÀ
13 x 12 /+D×K
14 - 11 /+ OST = I - K×D, phần dư của phép chia
15 F X≠0 57 /+ OST≠ 0?
16 24 24 /+ KHÔNG (tức là OST = 0), chuyển sang bước 24
17 P→X 9 69 /+ YES (tức là OST ≠ 0), gọi số nguyên PART
18 P→X 5 65 /+ Gọi D
19 - 11 /+ PrX = PHẦN - D
20 F X<0 5C /+ PHẦN - D < 0?
21 03 03 /+ KHÔNG, chuyển sang bước 03 tới giá trị mới D
22 P→X 6 66 /+ CÓ (bộ D đã hết)
23 S/P 50 /+ Chỉ báo dừng I
24 К П→X 6 Γ6 /+ И = И + 1, bắt đầu thế hệ И mới
25 K P→X 6 Γ6 /+ И = И + 1, kết thúc thế hệ; mới = cũ + 2
26 VP 51 /+ Nhảy vô điều kiện
27 01 01 /+ sang bước 01

toàn bộ phần I/D và phần còn lại OST=I-K×D. Trong trường hợp OST = 0, tiến hành chỉ định giá trị mới cho AND. Nếu D lớn hơn PHẦN (I là số nguyên tố), thì thực hiện chỉ thị AND và dừng tính toán. Sau đó đặt new=oldI+2 và tiến hành nghiên cứu AND này.

Đánh giá hiệu suất của chương trình: tính nguyên tố của số 5 được xác nhận trong 7 giây, tính nguyên thủy của số 99999989 được xác nhận trong khoảng 7 giờ.

Lệnh thú vị nhất trong chương trình là 09. Kết quả của việc thực thi lệnh này là số trong Pr9 trở thành số nguyên. Phương pháp chọn phần nguyên của số này cũng có thể áp dụng cho các mẫu PMK trước MK-61, về mặt danh nghĩa không có thao tác chọn phần nguyên của số.

Hướng dẫn

Sau khi gõ chương trình và chuyển PMC sang chế độ đếm, nhấn phím B/O. Sau đó quay số nguyên lẻ ban đầu AND và nhấn phím C/P, quá trình đếm sẽ bắt đầu; sau khi dừng đếm, chỉ báo hiển thị một số nguyên tố khác. Nhấn C/P sẽ bắt đầu một chu kỳ hoạt động mới, kết thúc bằng sự xuất hiện của số nguyên tố mới trên chỉ báo, v.v.

Sử dụng chương trình này, bạn có thể dễ dàng xác minh rằng các số nguyên 3, 31, 331, 3331, 33331, 333331, 3333331 chỉ bao gồm các số nguyên tố. Vẻ đẹp của những khám phá và chiến thắng cá nhân nhỏ sẽ phai nhạt nếu chúng ta đưa ra quá nhiều gợi ý và đưa ra những kết quả có sẵn. Vì vậy, đối với số tiếp theo của loạt bài, chúng tôi dành tặng những người yêu thích toán học, các nhà nghiên cứu#define bằng máy tính máy tính cá nhân cầm tay và chương trình này.
