---
id: 2025-5-6-gribalko-knop-kogda-falshivyie-monetyi-sosednie-152ed558
issue: kvant_2025_5-6
year: 2025
number: 5-6
title: Khi tiền giả ở gần
authors:
  - Грибалко А. В.
  - Кноп К. А.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 32
page_last: 34
page_labels: 30-31
lang: vi
source: kvant_digital
content_sha256: 764a2d3ef0d921cba3d318e367ffe61d3a7e305edc74bf6df9923c88e9a3a508
prompt_sha256: draft-1
translated_from: content/ru/2025/05-06/articles/07_gribalko-knop-kogda-falshivyie-monetyi-sosednie-152ed558.md
source_content_sha256: bfe4c2db63a78a1ad2e166807fd44ae5b88d740b086102b443c81de9a6dcc74e
translation_model: draft
translation_run: vi-draft-gaps-2026-11-03
translation_quality: draft
---

⟦folio 30⟧

---
running_head:
folio:
---

Khi
giả mạo
đồng xu
láng giềng

A. GRIBALKO, K. KNOP

Trong bài viết này, chúng tôi sẽ trình bày lời giải khó bài toán M2833 từ bài toán «Kvant».
Hãy xem xét công thức đã hứa của nó.
Có N đồng xu giống nhau nằm trong một vòng tròn. Được biết, chính xác hai trong số đó là giả. Đồng tiền thật có trọng lượng tương đương với tiền giả nhưng nhẹ hơn tiền giả. Cần xác định K cân trên cân không có hình vuông, đặt các đồng tiền giả cạnh nhau hoặc nem.
Ngoài ra, tôi muốn hiểu số lượng N xu tối đa có thể được thực hiện đối với K có trọng số.
Lưu ý rằng các biến thể của bài toán này đã từng gặp trước đây: trường hợp K = 2, N = 8 – xem «Kvant» số 9 cho năm 2023 (nhiệm vụ 3 ở trang 22); trường hợp K = 3, N = 20 – xem «Kvant» số 9 cho năm 2023 (nhiệm vụ 16 ở trang 39).
Cuối cùng, trong bài toán M2833 chúng ta cần tìm thuật toán cho K = 3 và a) N = 26, 6) N = 30.
Chúng tôi sẽ đánh số các đồng xu theo chiều kim đồng hồ từ 1 đến N. Những đồng xu chưa được chứng minh là giả hay thật theo truyền thống sẽ bị coi là đáng ngờ. Trong bài toán những đồng tiền đáng ngờ của chúng tôi được chia thành hai loại: những loại vẫn có khả năng bị làm giả cùng với một số đồng tiền lân cận và những loại không còn có khả năng này nữa.
Chúng tôi sẽ trình bày một số thuật toán lời giải cho từng trường hợp đang được xem xét để nhấn mạnh tính đa dạng của chúng.

Trường hợp K = 1, N = 4
Trong một lần cân, có thể giải bài toán cho N = 4 đồng xu bằng phương pháp cân này:
(1,3) ? (2,4).
Nếu có sự bình đẳng trong đó thì đáp số đến bài toán “có”, tức là các đồng tiền giả nằm liền kề nhau, còn nếu không bằng nhau thì “không”.
Một thuật toán khả thi khác
1 ? 3.
Tính tốt nhất của kết quả này có thể được chứng minh bằng vũ lực.

Trường hợp K = 2, N = 8
Kết quả này cũng có thể thu được bằng các thuật toán khác nhau; chúng tôi trình bày hai trong số họ.
Thuật toán đầu tiên
Cân lần đầu:
(2,3) ? (6,7).
1) Trong trường hợp đẳng thức (2.3) = (6.7), rõ ràng là ở mỗi bước của thang đo có số lượng đồng tiền giả bằng nhau (0 hoặc 1 mỗi đồng). Trong trường hợp này, tất cả các đồng tiền 2, 3, 6, 7 vẫn là những đồng tiền đáng ngờ, nhưng không có đồng xu nào có thể bị làm giả cùng với đồng tiền lân cận. Chúng ta chỉ có thể có hai cặp đồng xu (4,5) và (8,1) làm tiền giả lân cận.
Lần cân thứ hai là so sánh các cặp này với nhau:
(4,5) ? (8,1).
Bây giờ sau đẳng thức (4,5) = (8,1), chúng ta đi đến đáp số “không”, và sau bất đẳng thức, chúng ta hiểu rằng có một đồng tiền giả, nghĩa là không có đồng tiền giả nào trong số các đồng tiền ở lần cân đầu tiên cũng như ở phần nặng hơn của cân - do đó, cả hai đều là tiền giả ở phần nhẹ hơn, nghĩa là chúng ta có thể cho đáp số “có”.
2) Trong trường hợp bất đẳng thức, không mất tính tổng quát, chúng ta sẽ giả sử rằng (2.3) < (6.7), và chúng ta hiểu rằng trong số đồng tiền 2 và 3, một trong hai đồng tiền là giả hoặc cả hai đều là giả; trong trường hợp đầu tiên, các tham số của các giá trị sai lân cận có thể là (1,2) và (3,4). Sau đó là lần cân thứ hai:
(1,3) ? (2,4).
Sự bình đẳng trong đó chứng tỏ rằng cả hai đồng xu đều là giả trên cân và cả cặp đó

⟦folio 31⟧

---
running_head:
folio:
---

giả - một trong ba cặp hàng xóm hoặc cặp (1,4). Nhưng trường hợp thứ hai là không thể, vì vậy sự bình đẳng trên thang đo có nghĩa là đáp số “có” đối với câu hỏi chính bài toán.
Như vậy, sự bất bình đẳng trong trọng số thứ hai có nghĩa là "không".
Thuật toán hai
Cân lần đầu:
(2,3) ? (5,8).
1) Khi bằng nhau thì cặp tiền giả liền kề duy nhất có thể là (6,7). Đồng thời, các cặp tiền giả khác có thể tính đến đồng 6 và 7 không chứa đồng 2,3,5,8, tức là nhất thiết phải chứa một trong các đồng 1 và 4. Do đó, bằng lần cân thứ hai sau đẳng thức, ta có thể so sánh
(6,7) ? (1,4)
và trong trường hợp (6,7) < (1,4) cho đáp số “có”, và trong bất kỳ kết quả nào khác - “không”.
2) Trường hợp bất đẳng thức (2.3) ≠ (5.8) ở đây lại khác.
a) Nếu bát bên trái nhẹ hơn thì ít nhất một trong hai đồng xu 2 và 3 là giả, khi đó có thể thực hiện lần cân thứ hai như ở thuật toán thứ nhất:
(1,3) ? (2,4).
6) Nếu bát bên phải nhẹ hơn thì 2 và 3 là đồng thật, còn các cặp đồng giả lân cận có thể còn lại (4,5), (5,6), (7,8), (8,1), nên đến lần cân thứ hai chúng ta có thể so sánh
(4,5,6) ? (1,7,8).
Bình đẳng, rất nhiều indo, có nghĩa là đáp số "không".
Chúng ta hãy chứng minh rằng mỗi bất đẳng thức đều quen thuộc và chúng ta sẽ giả sử rằng cái bát bên phải nặng hơn. Sau đó, chúng ta giải tương tự như thuật toán đầu tiên lấy 8 xu cho các đồng xu liên tiếp từ 20 đến 7. Câu trả lời duy nhất là: nếu (1,2) = (5,6) thì một cặp tiền giả liền kề chỉ có thể là (3,4), nhưng không biết một là giả hay hai đồng trong nhóm (20,1,2,3,4,5,6,7). Do đó, để kiểm tra, chúng tôi thêm số thực hiển nhiên vào đồng xu 3, 4 và thực hiện lần cân thứ ba:
(3,4,11,12,13,14,15,16) ?
(7,8,9,10,17,18,19,20).
Thuật toán hai
Lần cân đầu tiên (hình 2):
(2,4,6,8,10) ? (12,14,16,18,20).
Nếu (2,4,6,8,10) = (12,14,16,18,20), thì đáp số ngay lập tức là “không”. Nếu bất đẳng thức thì không mất tính tổng quát ta sẽ giả sử rằng
(Tiếp theo trang 34)

⟦folio none⟧

Bức thư này dài quá vì tôi không có thời gian viết ngắn hơn. Blaise Pascal

Một vực thẳm đã mở ra và đầy sao; Những ngôi sao không có số, vực thẳm không có đáy. Mikhail Lomonosov

Con người hữu hạn không dám coi cái vô hạn như một thứ gì đó được cho sẵn và có thể tiếp cận được bằng trực giác thói quen của mình. Carl Friedrich Gauss

Nếu bạn truyền... một lượng nhiệt cực nhỏ vào cơ thể, thì câu hỏi đặt ra là nó sẽ tạo ra tác dụng gì... Rudolf Clausius

⟦column⟧

Chỉ có hai thứ vô hạn: Vũ trụ và sự ngu ngốc. Mặc dù tôi không hoàn toàn chắc chắn về Vũ trụ. Albert Einstein

... tại sao chỉ cần thừa hoặc thiếu một chút điện tích dương hoặc âm cũng đủ để tạo ra hiệu ứng điện đáng chú ý? Richard Feynman

Hãy để tôi vẽ các hình tam giác vô hạn lớn hơn. Từ bài giảng
