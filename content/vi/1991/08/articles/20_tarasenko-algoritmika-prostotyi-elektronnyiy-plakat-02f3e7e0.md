---
id: 1991-8-tarasenko-algoritmika-prostotyi-elektronnyiy-plakat-02f3e7e0
issue: kvant_1991_8
year: 1991
number: "8"
title: Thuật toán đơn giản. Áp phích điện tử
authors:
  - Тарасенко Б.
rubric: raznoe
rubric_sub: Разное
page_first: 76
page_last: 78
page_labels: 74-76
lang: vi
source: kvant_digital
extraction: vision
content_sha256: e99bdb70b7f0baa7083e5431c20f09acfe2107ff121ffeecd4c00c9bd5adaaca
prompt_sha256: draft-1
translated_from: content/ru/1991/08/articles/20_tarasenko-algoritmika-prostotyi-elektronnyiy-plakat-02f3e7e0.md
source_content_sha256: 7681736e3ea26820884fd1a0aa49bb6ef1e961368733df89d81da77cd2393010
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 74⟧

---
running_head:
folio:
---

Thuật toán
sự đơn giản
Máy bào điện tử
V. TARASENKO
Đó không phải là một câu hỏi dễ dàng,
Không có nhiều hơn một điều:
Mọi thứ đều phức tạp và đơn giản,
Hãy đếm nó một cách khôn ngoan!

“Bằng cách nào đó, tất cả chúng ta đều học được một điều gì đó.” Và không chỉ trong thời A.S. Pushkin. Trong ngày hôm qua không xa lắm, trong ngày hôm nay vô cùng tầm thường. Có vẻ như ngày mai chúng ta sẽ nghiên cứu nguyên tắc tương tự.

Nếu bạn nhìn vào nó, nó không phải là một nguyên tắc phẳng. Thành thật mà nói, ai có thể thành thật nói rằng họ chỉ học ở trường? Chúng ta học và dạy, định hình bản thân và giáo dục người khác trong những tình huống tưởng chừng như khó tin nhất. Con người được thiết kế theo cách mà mỗi ngày, cùng với miếng bánh mì của mình, anh ta phải tiếp nhận và truyền tải một phần thông tin. Vai trò của người thầy vẫn chưa qua tay ai! Bạn có thể trở thành một người ngay cả ở độ tuổi đi học rất sớm. Đối với những người gặp khó khăn trong việc lựa chọn đối tượng cho nghiên cứu chương trình, sư phạm và xã hội của mình, chúng tôi khuyên bạn nên chú ý đến anh trai hoặc em trai, cha mẹ, ông bà, con cái và nội tâm.

Niklass Wirth, một nhà khoa học nổi tiếng thế giới đến từ Thụy Sĩ, tác giả của ngôn ngữ lập trình Pascal và Modula-2, đồng thời là khách mời gần đây của chương trình truyền hình “Đối thoại với máy tính”, tin rằng việc dạy tất cả trẻ em biết sử dụng máy tính ở trình độ lập trình viên có trình độ cao sẽ là điều phi thực tế và là một điều mới mẻ. Nhưng cần phải cho càng nhiều trẻ em thấy khả năng của máy tính và chương trình càng tốt, càng sớm càng tốt. Chúng tôi muốn nói thêm rằng các thiết bị càng có tính kinh doanh, đơn giản, đơn giản và an toàn thì càng thông minh hơn. Chúng tôi đã đồng ý với độc giả về việc sử dụng những chiếc máy tính đơn giản như vậy cho doanh nghiệp. Nó sẽ là một cái gì đó để hiển thị. Vì vậy, một chương trình khác.

Nếu nhìn thấy một cái búa, chúng ta biết ngay rằng họ đang dùng nó đóng đinh; nếu chúng ta nhìn thấy một cái xẻng thì chúng ta biết rằng họ đang đào đất. Không ai đồng ý về mục đích của chương trình trừ khi mọi thứ đều được nói trước về nó. Hôm nay chúng tôi giới thiệu với độc giả một trình tạo tuần hoàn của 25 số nguyên tố đầu tiên. Nó được cho Svetlana, một học sinh lớp 3 đến từ thành phố Gatchina gần Leningrad xem, người không bị gánh nặng bởi kiến ​​thức sâu rộng và những lo lắng về cuộc sống gia đình. Và sinh vật vui vẻ này đã ngừng giải trí trong 10 phút để làm quen với kết quả công việc của người biểu tình. Hơn nữa, tôi đã nhớ hơn một nửa số nguyên tố được trình bày, đây là lần đầu tiên trong đời tôi biết đến!

Vì vậy, trước khi trực tiếp đến phần mô tả chương trình, chúng tôi xin chúc các bạn cả học viên và giảng viên thành công. Chúng tôi vẫn tin rằng phần lớn độc giả của chúng tôi là các nhà nghiên cứu về số nguyên tố và lập trình. Và mọi nhà nghiên cứu có lòng tự trọng đều có nghĩa vụ phải biết không chỉ một số điều đã được thực hiện trước đó mà còn cả việc điều này liên quan như thế nào đến môi trường trực tiếp của anh ta.

Chương trình 3. Trình diễn 25 số nguyên tố đầu tiên

Tất cả các loại súng phụ từ V3-34 đến MK-61 đều phù hợp. Chương trình giảng dạy cho các lớp lập trình và toán ở mọi lứa tuổi, bắt đầu từ các nhóm mẫu giáo cao cấp. Chương trình trình bày tuần tự các số nguyên tố từ 2 đến 97. Nguyên tắc của bảng tính được sử dụng, trong đó tất cả các số được trình bày đều được viết trước và

⟦folio 75⟧

---
running_head:
folio:
---

Văn bản của chương trình với các bình luận từng bước

00 V↑ 0E /+ Chuyển số bắt đầu AND từ PrX sang PrY
01 2 02 /+ Bộ
02 6 06 /+ hằng số 26
03 ↔ 14 /+ PrX:=Và đồng thời PrY:=26
04 - 11 /+ N:=26 - Tôi
05 BP 51 /+ Nhảy vô điều kiện
06 09 09 /+ mỗi bước 09
07 2 02 /+ Bộ
08 5 05 /+ hằng số 25
09 X→P 0 40 /+ Pr0:=N
10 9 09 /+ Bộ
11 8 08 /+ hằng số 98
12 P→X 0 60 /+ PrX:=N
13 3 03 /+ Hằng số 3
14×12 /+N×3
15 - 11 /+ A=98 - Н×3, địa chỉ bắt đầu của chương trình con
16 X→P 9 49 /+ ghi địa chỉ A của chương trình con vào Pr9
17 Checkpoint 9 —9 /+ Truy cập chương trình con tại địa chỉ A=Pr9
18 S/P 50 /+ Dừng chỉ báo số nguyên tố đã chọn
19 F L0 5Г /+ Pr0=0? Kiểm tra sự kết thúc của một chu kỳ
20 10 10 /+ Chuyển sang bước 10 nếu chu trình chưa hoàn thành
21 BP 51 /+ Nhảy vô điều kiện nếu vòng lặp kết thúc
22 07 07 /+ sang bước 07

Các đội 26-97 gồm 24 đội, mỗi đội 3 đội, tất cả đều giống nhau, 2 đội đầu tiên quay số nguyên tố tiếp theo, đội thứ 3 quay lại chương trình chính. Để tiết kiệm không gian, chúng tôi chỉ trình bày nhóm đầu tiên và nhóm cuối cùng cũng như các số được thu thập trong các nhóm trung gian.

23 0 00 /+ Tuyển dụng theo chương trình con
24 2 02 /+ số nguyên tố 02
25 B/0 52 /+ Quay lại chương trình chính

Tiếp theo, quay các số 03, 05, 07, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47, 53, 59, 61, 67, 71, 73, 79, 83, 89.

95 9 09 /+ Đặt trong chương trình con
96 7 07 /+ số nguyên tố 97
97 B/0 52 /+ Quay lại chương trình chính

sự lựa chọn của họ được kiểm soát bởi phần chính của chương trình.

Các thanh ghi và biến được sử dụng: A=Pr9 - địa chỉ bắt đầu của chương trình con trống; H=Pr0 - số sê-ri bổ sung lên tới thứ 26 của số nguyên tố tiếp theo; Trong số các thanh ghi ngăn xếp, chỉ PrX và PrY được sử dụng rõ ràng.

Mô tả thuật toán

Dựa trên số bắt đầu AND đã cho của số nguyên tố, sử dụng công thức A=98—3×H, trong đó H=26—AND, địa chỉ bắt đầu A của chương trình con được tính toán, hiển thị số nguyên tố này trên chỉ báo, sau đó quá trình chuyển đổi sang chương trình con này được thực hiện và sau khi quay trở lại từ đó, PMC sẽ dừng lại. Trong các lần khởi chạy tiếp theo của PMC (sử dụng phím C/P), N sẽ tự động giảm đi một, do đó số nguyên tố sau được gọi để hiển thị; sau khi xử lý số nguyên tố cuối cùng (tại H=1), quá trình chuyển đổi sang AND=1 của phép gán H:=25 xảy ra, từ đó ghi lại quá trình trình diễn.

Đánh giá tốc độ chương trình: “tính toán” số bắt đầu bằng lệnh B/O, cũng như quá trình chuyển đổi từ 97 sang 2 được hoàn thành trong 6 giây; số nguyên tố lớn hơn tiếp theo được hiển thị sau 4 giây.

Hướng dẫn

Sau khi gõ chương trình và chuyển PMC sang chế độ đếm, nhấn phím B/O. Sau đó quay số VÀ số nguyên tố bắt đầu (trong phạm vi

⟦folio 76⟧

---
running_head:
folio:
---

vùng từ 1 đến 25) và nhấn phím C/P; sau khi PMC dừng, số nguyên tố thứ I sẽ xuất hiện trên chỉ báo. Các lần nhấn phím S/P mới sẽ khiến các số nguyên tố sau xuất hiện trên chỉ báo cho đến số cuối cùng, sau đó là số đầu tiên xuất hiện, v.v.

Để tìm ra số AND của số nguyên tố tiếp theo (sau dãy C/P), bạn cần thực hiện thủ công một chuỗi lệnh

26 P→ХО —
- chỉ báo sẽ hiển thị giá trị I.

Chương trình 3 có hiệu quả nhất nếu được ghi vào bộ nhớ cố định của MK-52. Đối với MK-61 và MK-52, chương trình này có thể được bổ sung (bắt đầu từ bước 98) bằng chương trình con hiển thị số nguyên tố 101. Nó có thể được gọi thủ công bằng một chuỗi lệnh

B/O 26 S/P

và số 101 sẽ xuất hiện trên chỉ báo. Để quay lại vòng lặp chính sau cuộc gọi như vậy, bạn cần nhấn lại phím B/O. Nếu bạn muốn bản thân PMC hiển thị số này sau 97, sau đó quay lại số 2, thì bạn cần thêm một chương trình (bạn hãy tự nghĩ xem). Những người sẽ thử nghiệm phần đuôi của chương trình bộ nhớ PMC phải nhớ rằng bộ đếm địa chỉ hiển thị các bước 100, 101, 102, v.v. ở dạng -0, -1, -2, v.v., nhưng trong chính chương trình, các địa chỉ này phải được tạo ở dạng chung, tức là 100, 101, 102...

Chúng tôi tin tưởng rằng bản thân các giáo viên-lập trình viên tình nguyện của chúng tôi đã hiểu khi nào có thể nói với học sinh về cấu trúc của trình biểu diễn tuần hoàn này và khi nào cần chỉ hiển thị kết quả công việc của nó. Sau này, ví dụ, ở trường mẫu giáo. Phải không?
