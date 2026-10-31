---
id: 1975-4-vinnichenko-kvadratichnyiy-treugolnik-i-nepreryivnyie-tsepochki-5ab25651
issue: kvant_1975_4
year: 1975
number: "4"
title: Tam giác bậc hai và chuỗi liên tục
authors:
  - Винниченко А. П.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 23
page_last: 25
page_labels: 21-23
tag: Q0LG
lang: vi
source: kvant_digital
extraction: vision
content_sha256: a9d4b705e77f432ce3bd1521f69b20751666cd666f4c4382c1436cb5574fe1e7
prompt_sha256: draft-1
translated_from: content/ru/1975/04/articles/06_vinnichenko-kvadratichnyiy-treugolnik-i-nepreryivnyie-tsepochki-5ab25651.md
source_content_sha256: 891ec3bdeb0486fa5957b1936d0fc90082bd92a2860969664e8779b7744c5532
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 21⟧

Tam giác vuông và chuỗi liên tục

A. P. Vinchienko

Có lẽ, một số độc giả đã nhắc đến đường xoắn ốc Ulam (ví dụ, nó được mô tả trong cuốn sách “Truy cập toán học” của M. Gardner). Nếu ai đó không biết gì về vòng xoáy này thì cũng không sao; đây là câu chuyện của cô ấy One day, the American mathematician Stanislav Ulam, attending some uninteresting meeting, wrote a spiral out of boredom on a piece of checkered paper, numbered the cells of this spiral and circled the prime numbers *). Ulam có được bức tranh như trong Hình 1: các số nguyên tố trong đường xoắn ốc của anh ấy dường như nhô ra theo các đường chéo. Bây giờ chúng ta sẽ nói về một thứ tự khác để viết chuỗi tự nhiên, trong đó các số nguyên tố vẫn được đặt như trên các đường chéo.

*) Một số tự nhiên (không bằng 1) được gọi là số nguyên tố nếu nó chỉ chia hết cho chính nó và một.

Chúng ta hãy tạo một “tam giác vuông”: chúng ta chỉ viết một số ở dòng đầu tiên - 1, ở dòng thứ hai - các số từ 2 đến 4, ở dòng thứ ba - các số từ 5 đến 9, v.v., khai báo một dòng mỗi khi chúng ta nhận được một hình vuông của một số tự nhiên nào đó (xem Hình 2). Do đó, dòng đầu tiên của chúng ta kết thúc bằng $1^2$, dòng thứ hai - $2^2$, dòng thứ ba - $3^2$, v.v. (do đó tên của hình kết quả là - “tam giác vuông”; chứng minh rằng mỗi dòng của một tam giác vuông dài hơn chính xác 2 ô so với dòng trước).

Bây giờ chúng ta hãy khoanh tròn các số nguyên tố, giống như trong Hình 3.

Hình 1. Hình 2.

⟦folio 22⟧

⟦figure⟧
Hình 3.

⟦folio 23⟧

Sự khác biệt duy nhất là số 2)? But besides this, in our picture we have “continuous chains” stretching from the “hypotenuse” of the “triangle” to its “leg” - in Figure 3 there are six such chains. Hãy viết các số nguyên tố dọc theo chuỗi này:

2
3, 5
7, 11, 17
23, 31, 41, 53, 67, 83, 101
47, 59, 73, 89, ..., 227, 257
223, 251, 281, 313, ..., 1523, 1601

Chuỗi thứ 1 là giá trị của đa thức $x^2 + x + 2$ Tại $x = 0$ (Tại $x = 1$ chúng tôi nhận được $2^2$),
Chuỗi thứ 2 là giá trị của đa thức $x^2 + x + 3$ Tại $x = 0,1$ (Tại $x = 2$ chúng tôi nhận được $3^2$),
Chuỗi thứ 3 là giá trị của đa thức $x^2 + x + 5$ Tại $x = 1,2,3$ (Tại $x = 4$ chúng tôi nhận được $5^2$),
Chuỗi thứ 4 là các giá trị của đa thức $x^2 + x + 11$ tại $x = 3,4,5,...,8,9$ (tại $x = 10$ ta nhận được $11^2$),
Chuỗi thứ 5 là các giá trị của đa thức $x^2 + x + 17$ tại $x = 5,6,...,14,15$ (tại $x = 16$ ta nhận được $17^2$),
Chuỗi thứ 6 là các giá trị của đa thức $x^2 + x + 41$ tại $x = 13,14,...,38,39$ (tại $x = 40$ ta nhận được $41^2$).

Euler đã biết các đa thức có dạng $x^2 + x + k$; công thức $x^2 + x + k$ cho $k = 2, 3, 5, 11, 17, 41$ cho ra số nguyên tố cho tất cả $x = 0, 1,...,(k-1),(k-2)$.

Do đó, các chuỗi liên tục của chúng ta là các “đuôi” của các giá trị của đa thức $x^2 + x + k$, trong đó $k = 2, 3, 5, 11, 17, 41$. Có chuỗi liên tục dài hơn? Điều này hiện chưa được biết.

Hãy quay lại tam giác vuông của chúng ta - chuyển “reshemo của Eramosthenes” vào đó (xem «Kvant» Số 1 cho năm 1974): lấy một số tự nhiên và gạch bỏ tất cả các số chia hết cho nó. Chúng ta sẽ nhận được một số kiểu mẫu; ví dụ: đối với số 2, đó là mẫu “cờ vua” (Hình 4). Đối với bộ ba, mẫu là mẫu sau (xem Hình 5). Tuy nhiên, có một khuôn mẫu cho những giá trị này. Vì vậy, nếu bạn tạo một hình vuông từ bìa cứng có cạnh 2 và cắt ra hai hình vuông từ đó, đặt trong hình 6 bằng các dấu chéo, thì với sự trợ giúp của con tem như vậy, bạn có thể gạch bỏ tất cả các số chia hết cho 2 khỏi tam giác vuông.

Thật sự:

1) dán tem sao cho chỉ nhìn thấy số 1 phía trên nó;
2) gạch bỏ các số trong câu trả lời;
3) di chuyển tem xuống, sang phải hoặc sang trái hai ô vuông;
4) một lần nữa gạch bỏ các con số trong câu trả lời, v.v.
