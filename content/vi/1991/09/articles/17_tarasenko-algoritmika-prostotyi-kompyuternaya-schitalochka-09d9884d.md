---
id: 1991-9-tarasenko-algoritmika-prostotyi-kompyuternaya-schitalochka-09d9884d
issue: kvant_1991_9
year: 1991
number: "9"
title: Thuật toán đơn giản. Vần đếm máy tính
authors:
  - Тарасенко Б.
rubric: raznoe
rubric_sub: Разное
page_first: 52
page_last: 53
page_labels: 50-51
lang: vi
source: kvant_digital
extraction: vision
content_sha256: d02a6d682f8fbcb2e5b1647ef3fad8cf31c7dcf74aed235b5b63f2f8fcc8480b
prompt_sha256: draft-1
translated_from: content/ru/1991/09/articles/17_tarasenko-algoritmika-prostotyi-kompyuternaya-schitalochka-09d9884d.md
source_content_sha256: 34817aa8e871bf4203f7a881bd11f06e599859b9e17a4df64c5df94956cd8a79
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 50⟧

---
running_head:
folio:
---

Thuật toán
sự đơn giản

Vần đếm máy tính

V. TARASENKO

Đó không phải là một câu hỏi dễ dàng,
Nhưng hãy tin một điều:
Mọi thứ đều phức tạp và đơn giản,
Hãy đếm nó một cách khôn ngoan!

Ai mà không nhớ những niềm vui dễ thương thuở nhỏ, những vần điệu nho nhỏ? “Tháng đã xuất hiện từ sương mù…”, “Eniki-beniki hoặc bánh bao…”. Ngoài khả năng gợi lại những ký ức êm đềm, chúng còn có một đặc tính nữa: kết quả, hay “kết quả rút thăm xem ai sẽ dẫn đầu” là rõ ràng trong từng trường hợp cụ thể và dễ tính toán. Nhưng theo thỏa thuận ngầm, huyền thoại về sự khó đoán và công lý đáp số cuối cùng đã được coi là được bảo tồn và ủng hộ một cách cẩn thận. Đây là điều kiện không thể thiếu đối với bất kỳ trò chơi nào của trẻ. Đôi khi, để in thành công một bức thư, người ta phải dự đoán một thuật toán đặc biệt.

Trên hiên nhà này ngồi:
Sa hoàng, hoàng tử, vua, hoàng tử, thợ đóng giày, thợ may. Bạn là ai?
Nói nhanh, không cần suy nghĩ!

Người mà âm tiết nhấn mạnh cuối cùng rơi vào, không thực sự suy nghĩ, sẽ thốt ra, chẳng hạn như “thợ may”. Sau đó, việc đếm “trong câu thơ” nhất thiết phải được lặp lại, bắt đầu bằng “thợ may” và kết thúc bằng từ dẫn đầu “thợ may”. Để giữ mọi thứ “công bằng”, đôi khi họ đồng ý trước xem nên đếm “theo chiều kim đồng hồ” hay “ngược chiều kim đồng hồ”.
Với số nguyên tố thì ngược lại. Chúng luôn đếm “theo chiều kim đồng hồ”, tức là theo chiều tăng dần. Và luôn “từ bếp”, từ số nguyên tố thứ hai đầu tiên. Họ chỉ sử dụng một “bảng đếm” - thuật toán đảo ngược của Erathofen, đôi khi chỉ hiển thị được một chút.

Các số nguyên tố phân bố không đều giữa các giá trị tự nhiên. Hãy xem xét một thứ rất nổi tiếng được gọi là “Bảng các số nguyên tố không vượt quá 6000”. Cổ điển. Có bao nhiêu cái đơn giản? Trong cuốn sách “Lý thuyết số” của A. A. Bukhshtab (M., “Prosveshcheniye”, 1966), bảng được sắp xếp cạnh nhau theo sơ đồ 11×38+10×36+5×1, cho kết quả là 783, tức là có khoảng ba số nguyên tố cho mỗi 23 số. Khi đó, số nguyên tố thứ 25 phải ở khoảng 200, nhưng trên thực tế nó bằng 97. Và thật không may, người ta không thể nhanh chóng nói số nguyên tố thứ 25001 sẽ là bao nhiêu, ít nhất là gần đúng, nếu không nhờ đến sự trợ giúp của máy tính, mặc dù các nhà toán học đã tìm ra công thức ước tính gần đúng số lượng số nguyên tố không vượt quá một số tự nhiên nhất định.

Chúng ta hãy cố gắng “làm nổi bật” tình huống một chút, hoặc xem một lần luôn tốt hơn là nghe một lần. Hãy đặt ra vấn đề và điều tra nó chỉ bằng thiết bị máy tính cầm tay. Số số nguyên tố trong mỗi trăm số đầu tiên sau lũy thừa mười tiếp theo là bao nhiêu?

Dưới đây là dữ liệu thử nghiệm. Ở đầu mỗi chuỗi, lũy thừa của mười được đưa ra, sau đó trong ngoặc đơn là số số nguyên tố trong chuỗi này, sau đó là các số nguyên tố trong chuỗi này và ở cuối sau dấu chấm phẩy - số nguyên tố tiếp theo (để tiết kiệm chỗ, chỉ đưa ra hai hoặc ba chữ số cuối của mỗi số). Đối với “hàng trăm bài đánh giá” như vậy, công cụ phần mềm số 1 từ lần xuất bản đầu tiên của chúng tôi (xem «Kvant» Số 6) là đủ đối với chúng tôi; chỉ với các số 10⁸ và lớn hơn mới được thực hiện trên MK-85 và HP-32S.

⟦folio 51⟧

---
running_head:
folio:
---

Chương trình 4. Trình tạo số nguyên tố
Văn bản của chương trình với các bình luận từng bước

53 X→Π 6 46 /+ Nhập số cũ lẻ
54 0 00 /+ Hằng số 0
55 C/Π 50 /+ Chỉ định quay số
56 F X≠0 57 /+ PrX≠0?
57 5 55 /+ KHÔNG (tức là PrX=0), chuyển sang bước 55
58 X→Π 4 44 /+ CÓ, ghi số serial vào Pr4
59 1 01 /+ Hằng số 1
60 X→Π 45 45 /+ Zasylak 1 trong Pr5
61 K P→X 5 Γ5 /+ Thêm 1 vào bộ đếm Pr5
62 K P→X 5 Γ5 /+ Thêm 1 số nữa vào bộ đếm Pr5
63 P→X 6 66 /+ Gọi PrX số kiểm tra hiện tại VÀ
64 P→X 5 65 /+ Gọi bộ chia dòng D từ Pr5 vào PrX
65  13 /+ PHẦN=I/D
66 X→Π 9 49 /+ Zasylak PHẦN trong Pr9
67 K P→X 9 Γ9 /+ K=phần nguyên của PHẦN
68 P→X 6 66 /+ Gọi I trong PrX
69 P→X 9 69 /+ Gọi K trong PrX; Và chuyển đến PrY
70 P→X 5 65 /+ Gọi D trong PrX; PrY=K; PrZ=VÀ
71×12 /+D×K
72 - 11 /+ OST=I-K×D, phần dư của phép chia
73 F X≠0 57 /+ OST≠0?
74 8 4 84 /+ KHÔNG (tức là OST=0), chuyển sang bước 84
75 P→X 9 69 /+ YES (tức là OST≠0), gọi số nguyên PART
76 P→X 5 65 /+ Gọi D từ Pr5 đến PrX
77 - 11 /+ PrX=PHẦN - D
78 F X<0 5C /+ PHẦN - D<0?
79 6 1 61 /+ KHÔNG, chuyển sang bước 61 với giá trị mới D
80 P→X 4 64 /+ CÓ (bộ D đã hết), số gọi
81 P→X 6 66 /+ Gọi số nguyên tố
82 C/Π 50 /+ Cách lưu trữ số nguyên tố
83 K P→X 4 Γ4 /+ Thêm 1 vào bộ đếm Pr4 của số
84 K P→X 6 Γ6 /+ Thêm 1 vào số được kiểm tra trong Pr6
85 K P→X 6 Γ6 /+ Thêm 1 nữa vào số được kiểm tra
86 BP 51 /+ Nhảy vô điều kiện
87 5 9 59 /+ mỗi bước 59

10^0 (25): 2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47, 53, 59, 61, 67, 71, 73, 79, 83, 89, 97; 101.
10^1 (25): 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47, 53, 59, 61, 67, 71, 73, 79, 83, 89, 97; 101, 103, 107, 109; 113.
10^2 (21): 1, 3, 7, 9, 13, 27, 31, 37, 39, 49, 51, 57, 63, 67, 73, 79, 81, 91, 93, 97, 99; 211.
10^3 (16): 9, 13, 19, 21, 31, 33, 39, 49, 51, 61, 63, 69, 87, 91, 93, 97; 103.
10^4 (11): 7, 9, 37, 39, 61, 67, 69, 79, 91, 93, 99; 103.
10^5 (6): 3, 19, 43, 49, 57, 69; 103.
10^6 (6): 3, 33, 37, 39, 81, 99; 117.
10^7 (2): 19, 79; 103.
10^8 (6): 7, 37, 39, 49, 73, 81; 123.
10^9 (7): 7, 9, 21, 33, 87, 93, 97; 103.
10^10 (4): 19, 33, 61, 97; 103.
10^11 (7): 3, 19, 57, 63, 69, 73, 91; 103.

Vì vậy, số lượng số nguyên tố trong mỗi hệ tiếp theo giảm đi nhưng không đồng nhất: 25, 25, 21, 16, 11, 6, 6, 2, 6, 7, 4, 7, ... Và điều này có thể là lý do đặt ra những câu hỏi mới và nghiên cứu mới. Ví dụ: có bao nhiêu số nguyên tố trong một nghìn số tự nhiên, bắt đầu từ số đầu tiên? Cũng xin lưu ý rằng trong số 12 nghiên cứu “cắt”, có bảy nghiên cứu “kết thúc” ở mức 103 và chỉ có một nghiên cứu bắt đầu ở mức một.

Một lĩnh vực mới đòi hỏi những công cụ và tiện nghi mới. Chúng tôi cung cấp cho những ai mong muốn một bộ tạo gia tăng phần mềm cho MK-61. Nó tương tự như cái đầu tiên, nhưng được bổ sung bởi một tử số nguyên tố.

(Về phần kết xem trang 58)
