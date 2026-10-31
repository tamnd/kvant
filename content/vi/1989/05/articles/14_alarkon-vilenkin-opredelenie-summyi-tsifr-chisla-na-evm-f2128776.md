---
id: 1989-5-alarkon-vilenkin-opredelenie-summyi-tsifr-chisla-na-evm-f2128776
issue: kvant_1989_5
year: 1989
number: "5"
title: Xác định tổng các chữ số của một số trên máy tính
authors:
  - Аларкон Е. Х.
  - Виленкин А. Н.
rubric: raznoe
rubric_sub: Разное
page_first: 68
page_last: 69
page_labels: 66-67
tag: 77EJ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 1f1960cb8e7508b9c2915eaa158ab5ba1423ed07384a91df63c1dd82e9c1a729
prompt_sha256: draft-1
translated_from: content/ru/1989/05/articles/14_alarkon-vilenkin-opredelenie-summyi-tsifr-chisla-na-evm-f2128776.md
source_content_sha256: 7c4aa991e3727c5f60e324b01992aa1ff88adce33ef564ce3ac1a30e0f3c6f8d
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 66⟧

Xác định tổng các chữ số của một số trên máy tính

E. H. ALARCON,
A. N. VILENKIN

Tại khoa dự bị thuộc một loại, những người nộp đơn trong tương lai được cung cấp bài toán sau.

Tổng các chữ số của các trang chính là 3684. Tìm số trang của cuốn sách này.

Làm thế nào để giải quyết điều này bài toán? Và làm thế nào để dạy máy tính hoặc máy tính vi mô giải quyết bài toán này? Điều đầu tiên bạn nghĩ đến là dạy từ trang 1 và cộng với tổng S (ban đầu bằng 0) các chữ số mà số trang tiếp theo được viết ra cho đến khi chúng ta đạt đến 3684. Để làm được điều này, trước tiên chúng ta phải dạy máy tính trích xuất từ ​​số trang các chữ số mà số này được viết ra. Ví dụ: từ số n=128, bạn cần lấy ba số: 1, 2, 8 (chúng tôi sẽ giới hạn ở các số có ba chữ số). Hãy sử dụng hàm [x] - “phần nguyên của x”. Nó có sẵn trên máy tính và MK-61; trên các máy tính vi mô (có thể lập trình) khác, nó có thể được thực hiện bằng chương trình con sau.

Dòng số. Mã lệnh
80 1 01
81 + 10
82 X→Π 43
83 KΠ→X Γ3
84 Π→X 63
85 B/O 52

Hoạt động của chương trình con này dựa trên thực tế là lệnh chỉ báo gián tiếp từ thanh ghi RG3 không chỉ giảm nội dung của RG3 đi 1 mà còn giảm nội dung của RG3 xuống một số nguyên, trừ khi nội dung của RG3 lớn hơn 1 và được hiển thị ở vị trí dấu phẩy tự nhiên. Tất nhiên, không nên sử dụng thanh ghi RG3 trong chương trình chính. Khi truy cập một chương trình con, số gốc phải nằm trong thanh ghi X và kết quả cũng sẽ thu được ở đó. (Nếu không thì phải cung cấp lệnh 79 V↑ 52.)

Để có được số hàng trăm của số n có ba chữ số, lấy [n/100]. Đây sẽ chính xác là số nguyên hàng trăm chứa trong số n. Hãy biểu thị nó bằng R2:

R2=[n/100].

Tiếp theo, hãy xóa hàng trăm khỏi số n mà không chạm vào hàng chục và hàng đơn vị, và để làm điều này, hãy trừ [n/100]·100 khỏi số n, gọi đây là số m. Nó có hai chữ số và chứa hàng chục và hàng đơn vị của số n. (Vì vậy, nếu n=128, thì m=28.) Việc cần làm với nó đã rõ ràng:

R1=[m/10]

sẽ là số hàng chục và

R0=m-[m/10]·10

- số lượng đơn vị. Bây giờ chúng ta viết một chương trình con để tính tổng các chữ số của số n, tức là tổng R0+R1+R2 và chương trình chính để tính tổng (lặp qua k từ 1 đến n) của các chữ số của số trang từ 1 đến n. Hãy chạy nó để tính tổng các chữ số của số

⟦folio 67⟧

Hãy bỏ qua các trang “Kwan” (n=80) và xem điều gì sẽ xảy ra.

Nếu chương trình được cài đặt trên máy tính thì đáp số sẽ xuất hiện nhanh chóng. Nhưng rõ ràng là thời gian hoạt động của máy tính phụ thuộc vào n - n càng lớn thì máy tính sẽ hoạt động càng nhiều. Bạn có thể thử mọi thứ trong chương trình, in kết quả và dừng khi nhận được số 3684 (hoặc hơn), chạy chương trình này với n đủ lớn và nhận được đáp số bản gốc bài toán.

Nếu chương trình được cài đặt trên máy tính vi mô thì thời gian hoạt động sẽ là 10-13 phút, vì chu trình xử lý một số trang mất 7-10 giây và có 80 trang.

Nhưng trong 10 phút, chúng ta đã có thể tìm được số tiền ban đầu mà không cần cộng tất cả các số của tất cả các số trang. Đầu tiên chúng ta hãy tìm tổng các đơn vị. Ở đây chúng ta cần cộng các số 1, 2, 3, 4, 5, 6, 7, 8, 9, 0 và lại 1, 2, ..., các tổng như vậy sẽ được sử dụng từ 01 đến 80). 1+2+...+9=45, 45×8=360. Với hàng chục thì thậm chí còn dễ dàng hơn: một sẽ xuất hiện 10 lần (từ 10 đến 19), cũng như hai, và ba... bao gồm cả bảy. Chỉ có 8 chục sẽ chỉ xuất hiện một lần. Ta được tổng của số chục có dạng (1+2+...+7)·10+8=288. Tổng cộng: 288+360=648 - số tiền ban đầu. Máy tính vi mô sẽ sớm cung cấp cho nó.

Bây giờ rõ ràng là phương pháp cộng các số của máy vi tính sẽ cộng số 3684 trong khoảng một giờ. Chuyện này quá dài. Có thể đặt trên máy tính vi mô phép tính tổng các chữ số của các trang từ 1 đến n giống như cách chúng ta tìm tổng các chữ số của các trang của “Kwan” không? Số lượng phép tính sử dụng phương pháp này hầu như không phụ thuộc vào n nên thời gian thực hiện sẽ ngắn.

Hãy thử. Gọi số trang là n và viết bằng số i, j, k. Điều này được ký hiệu như sau: n=ijk. Đầu tiên đặt i=0, j=0 (n là số có một chữ số). Khi đó tổng ban đầu bằng k(k+1)/2 - đây là tổng của cấp số cộng 1, 2, ..., k. Hãy biểu thị tổng này là f1(k): f1(k)=k(k+1)/2. Cụ thể, f1(9)=45.

Bây giờ đặt n=jk và j≠0 (n là số có hai chữ số). Chúng ta sẽ chia tổng cần tìm thành hai phần: từ 01 đến (j−1)9 và từ j0 đến jk. Chúng ta tính tổng đầu tiên giống như cách chúng ta tính tổng các chữ số của số trang Kwan: ​​đơn vị - 45j, hàng chục - 10(j−1)j/2. Trong tổng thứ hai, k+1 là một số, tổng của số chục là j(k+1), tổng đơn vị là f1(k), ngoại trừ tổng f2(jk) có dạng

f2(jk)=45j+5j(j−1)+j(k+1)+f1(k)=j(5j+41+k)+f1(k).

Cụ thể, f2(99)=900 (điều này sẽ hữu ích sau này), công thức “có tác dụng” với các số có một chữ số (j=0).

Bây giờ đặt n=ijk và i≠0. Một lần nữa, chúng ta chia tổng thành hai phần: từ 001 đến (i−1)99 và từ i00 đến ijk. Chúng tôi đếm số tiền đầu tiên. Hàng chục và hàng đơn vị (cùng nhau) cho i·f2(99)=900i (có rõ tại sao không?). Hàng trăm cho 100(i−1)i/2 (mỗi chữ số hàng trăm được dùng 100 lần). Chúng tôi đếm số tiền thứ hai. Hàng trăm cho i(10j+k+1), hàng chục và hàng đơn vị cho f2(jk). Tổng cần tìm f3(ijk) có dạng

f3(ijk)=900i+50i(i−1)+i(10j+k+1)+f2(jk)=i(50i+10j+k+851)+f2(jk).

Công thức này “hoạt động” cho cả số có hai chữ số (i=0) và số có một chữ số (i=j=0).

Vì vậy, các công thức thu được. Chúng có thể dễ dàng cài đặt ngay cả trên máy vi tính có thể lập trình và sau khi nhập số n vào đó, nó sẽ tính số tiền ban đầu sau 15 giây, ví dụ: f3(96)=849, f3(200)=1902, v.v.

Đạt được tốc độ, chúng tôi đã đánh mất một cái gì đó. Bây giờ chúng ta không thể chạy chương trình được nữa và đợi cho đến khi nó đạt đến số 3684. Việc cần làm là sử dụng phương pháp thử và sai (đôi khi được gọi là “phương pháp chọc”). Hãy chỉ vào con số 200 - chưa đủ. Hãy thử f3(400)=4204 - rất nhiều. Hãy thử f3(300)=3003 - không đủ. Và cứ như vậy cho đến khi đạt được bản gốc.

(Cuối cùng xem trang 70)
