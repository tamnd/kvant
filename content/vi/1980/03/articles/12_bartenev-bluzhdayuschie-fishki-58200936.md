---
id: 1980-3-bartenev-bluzhdayuschie-fishki-58200936
issue: kvant_1980_3
year: 1980
number: "3"
title: chip lang thang
authors:
  - Бартенев Ф. А.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 40
page_last: 41
page_labels: 38-39
tag: WTXB
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 8b978c9605eab1a6e07e42ce2ad824f0b87d48c853b36f07525c888580fe9cc3
prompt_sha256: draft-1
translated_from: content/ru/1980/03/articles/12_bartenev-bluzhdayuschie-fishki-58200936.md
source_content_sha256: 71c45beb26e1ca9c9e525991ee7be7835d086eccabeb1835bb89cba19a725d37
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 38⟧

F. Bartenev

chip lang thang

Chúng ta thường cho rằng mọi người dành phần lớn khả năng sáng tạo của mình cho các mục đích, và do đó, các vấn đề toán học đáng được quan tâm không phải vì bản thân chúng mà vì chúng phát triển khả năng khám phá.

Leibniz

Chắc hẳn nhiều độc giả đã quen thuộc với trò chơi “góc” trên bàn cờ. Cô ấy là nguyên mẫu của nhiều loại trò chơi, giải trí, bài toán với nội dung thú vị và đáng trân trọng. Tiếp theo chúng ta sẽ xem xét một số trong số họ.

Là bảng, chúng ta sẽ xem xét các hình chữ nhật tùy ý, được chia thành các phần bằng nhau

Hình 1.

Hình 2.

hình vuông mới (xem hình ảnh). Chúng tôi sẽ chỉ ra vị trí ban đầu của các con chip bằng các vòng tròn màu đen và vị trí cuối cùng bằng các đường chấm chấm.

Mỗi trường (ô) của bàn cờ đều có ký hiệu riêng, “địa chỉ” riêng, “tọa độ” riêng, giống như trên bàn cờ. Ví dụ, trong Hình 1, một trong các quân cờ nằm ​​ở ô c2. Tất nhiên, thông thường những ký hiệu này không được viết ở lề bảng, nhưng chúng không khó để xác định, vì hình luôn chỉ ra các ký hiệu chữ cái của chiều dọc và các số của chiều ngang.

Bây giờ hãy nói về chuyển động chính xác của chip. Mỗi mảnh có thể di chuyển đến bất kỳ trường liền kề nào (theo chiều ngang hoặc chiều dọc). Ví dụ: một con chip đứng trên ô c2 có thể đi đến một trong các ô sau: b2; d2; c3; c1. Ta sẽ viết các nước đi tương ứng như sau:

c2—b2; c2—d2; c2—c3; c2—c1.

Một quân cờ có thể “nhảy” qua “hàng xóm” của nó (theo một trong các hướng được chỉ định) đến một trường tự do. Ví dụ, trong Hình 1 nước đi có thể là d6-d8. Trong một lần di chuyển, một con chip thậm chí có thể tạo ra một số khóa như vậy và hướng của chúng có thể khác nhau. Vì vậy, trong Hình 1, một quân cờ từ hình vuông d6 có thể di chuyển bằng cách di chuyển d6-f6-f8 sang hình vuông f8 hoặc bằng cách di chuyển d6-f6-h6 sang hình vuông h6.

Ví dụ 1. Hình 2 hiển thị một bảng 1x25, vị trí của ba quân cờ được chỉ định và vị trí mà chúng cần được di chuyển đến cũng được chỉ định.

Hóa ra chuyển động cần thiết có thể được thực hiện trong 33 bước di chuyển: bạn cần di chuyển toàn bộ cấu hình chip dưới dạng một đơn vị hai ô vuông về bên phải với ba bước di chuyển sau:

1. c1—d1;
2. a1—c1—e1;
3. b1—c1.

⟦folio 39⟧

Hình 3.

Vì cấu hình cần phải di chuyển 22 trường sang bên phải nên bạn có thể áp dụng kỹ thuật này 11 lần, tốn chính xác 33 lần di chuyển cho tất cả các lần di chuyển.

Nhiệm vụ 1. Bốn con chip được đặt trên cùng một bảng 1x25 (Hình 3). Có thể thực hiện động tác tương ứng trong ít hơn 33 động tác không?

Bài tập 2. Có một bảng vô hạn có chiều rộng bằng 1. Chứng minh rằng luôn có thể đặt n quân cờ lên đó (n ≥3) sao cho sau khi thực hiện ba nước đi, ban đầu có thể thu được cấu hình các quân cờ được dịch chuyển hai ô sang bên phải.

Chúng ta đã xem xét một số ví dụ về các quân di chuyển trên một tấm ván có chiều rộng bằng một. Nếu chúng ta xem xét chuyển động của các con chip trên một bàn cờ có kích thước $m \times n (m > 2, n > 2)$, thì có thể sử dụng các kỹ thuật đa dạng hơn. Hãy xem xét một số ví dụ.

Nhiệm vụ 3. Có thể thực hiện động tác nêu trong Hình 4 với ít hơn 40 động tác không?

Ví dụ 2. Cần phải di chuyển từng con chip từ phần trung tâm của bảng (Hình 5) sang một trong các trường góc.

Hóa ra một chuyển động nhất định có thể được hoàn thành trong 22 bước, chẳng hạn như sau:

1. d4—d6; 7. c8—b8;
2. d5—d7; 8. b8—a8;
3. d6—d8; 9. e8—f8;
4. d8—e8; 10. f8—g8;
5. d7—d8; 11. g8—h8;
6. d8—c8; 12. e5-e3, v.v.

Ở đây, chúng ta phải đối mặt với nhu cầu xem các bước hoặc giai đoạn mà chúng ta mong muốn chia quá trình lời giải bài toán. Đồng thời, chúng tôi không đặt ra câu hỏi về việc xác định số lần di chuyển nhỏ nhất cần thiết.
