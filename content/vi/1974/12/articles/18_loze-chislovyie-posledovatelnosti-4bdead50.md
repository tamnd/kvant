---
id: 1974-12-loze-chislovyie-posledovatelnosti-4bdead50
issue: kvant_1974_12
year: 1974
number: "12"
title: Dãy số
authors:
  - Лозе Х.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 68
page_last: 71
page_labels: 66, 67, 69
tag: 1HAB
lang: vi
source: kvant_digital
extraction: vision
content_sha256: fa3daafb95ae2dc1805d98bb26efb32a7f7cae63d2d0f1ee1d1c58694d88c745
prompt_sha256: draft-1
translated_from: content/ru/1974/12/articles/18_loze-chislovyie-posledovatelnosti-4bdead50.md
source_content_sha256: 42831cc57fd4a7d9e46656c371b5cddb08961bc9b2394d81adcfccf3b9f187c9
translation_model: draft
translation_run: vi-draft-2026-11-03
translation_quality: draft
---

⟦folio 66⟧

Dãy số xảy ra thường xuyên. Ví dụ, hãy nhớ dãy số mà tác phẩm kinh điển thứ hai lặp lại khi lặp lại bảng nhân với 2:
$$\Pi_1 = (2, 4, 6, 8, 10, \dots);$$
vào ngày 5:
$$\Pi_2 = (5, 10, 15, 20, 25, \dots);$$
lúc 6 giờ:
$$\Pi_3 = (6, 12, 18, 24, 30, \dots)$$
và nhiều hơn nữa

Hãy nhớ những dòng chữ trên ống kính máy ảnh; và ở đó bạn sẽ tìm thấy một dãy số, cụ thể là:
$$\Pi_4 = (2; 2,8; 4; 5,6; 8; 11; 16; 22).$$

Dưới đây là một số trình tự ví dụ khác:

$$\Pi_5 = \left(1, \frac{1}{2}, \frac{1}{3}, \frac{1}{4}, \frac{1}{5}, \dots\right);$$
$$\Pi_6 = (1, 4, 9, 16, 25, \dots);$$
$$\Pi_7 = (7, 4, 1, -2, -5, -8);$$
$$\Pi_8 = (-2, +4, -8, +16, -32, +64, -128, +256, -512, \dots).$$

Các số riêng lẻ có trong một dãy số được gọi là thành viên của dãy đó. Nếu một dãy bao gồm một số hữu hạn các số hạng thì nó được gọi là hữu hạn; nếu không thì gọi là vô hạn **).

*) Dozent Dr. H. Lohse “Elementare Zahlenfolgen”, “Alpha” (CHDC Đức), 1968, Số 3-6. Bản dịch và xử lý của A. Ya. Khalamizer.
**) Trong tài liệu của chúng ta, dãy số thường được gọi là dãy vô hạn. (Bản dịch ước chừng)

Dãy số xuất hiện trong bảng nhân với 2 của trường (nếu không thì theo dãy số) chỉ được xét ở cấp tiểu học đến 20, cụ thể là:

$$\Pi_9 = (2, 4, 6, 8, 10, 12, 14, 16, 18, 20).$$

Ở đây số 20 là số hạng cuối cùng trong mười số hạng của dãy. Nếu chuỗi được tiếp tục vô tận, nghĩa là không có phần tử cuối cùng (cuối cùng), thì kết quả là một chuỗi số vô hạn.

$$\Pi_{10} = (2, 4, 6, 8, 10, 12, 14, 16, 18, 20, \dots).$$

Ở đây dấu ba chấm có nghĩa là dãy số này là vô hạn - nó không có “kết thúc” (thuật ngữ cuối cùng).

Bằng cách thiết lập trình tự, chúng tôi chỉ ra một số thành viên đầu tiên của nhóm có khả năng xảy ra lỗi. Ví dụ, người ta giả định rằng chuỗi $\Pi_5$ nên được tiếp tục như thế này:

$$\Pi_5 = \left(\dots, \frac{1}{6}, \frac{1}{7}, \frac{1}{8}, \frac{1}{9}, \frac{1}{10}, \dots\right),$$

nhưng không có gì đảm bảo điều này. Ví dụ: sau thành viên $1/5$ có thể có thành viên

$$\frac{1}{4}, \frac{1}{3}, \frac{1}{2}, 1, \frac{2}{1}, \dots$$

⟦folio 67⟧

hoặc, giả sử, $\frac{1}{5}, \frac{1}{5}, \frac{1}{5}, \dots$;

bạn có thể tiếp tục chuỗi $\Pi_5$ theo những cách khác. Chúng ta thấy rằng một dãy vô hạn không thể được xác định duy nhất bởi một số hữu hạn các số hạng đầu tiên. Điều này có nghĩa là chúng ta cần tìm những cách tốt hơn để xác định một dãy số.

Trình tự đặc biệt đơn giản

$$\Pi_{11} = (1, 2, 3, 4, 5, \dots),$$

gọi là dãy số tự nhiên, trong đó số hạng sau lớn hơn số trước 1 đơn vị.

Chuỗi này có thể được so sánh với bất kỳ chuỗi vô hạn nào khác - mỗi thành viên của chuỗi được gán số sê-ri: thành viên đầu tiên là số 1; số hạng thứ hai là số 2, ... số hạng thứ $k$, thường gọi là số hạng tổng quát, là số $k$. Bản thân các thành viên này thường được chỉ định như sau:

$$(a_1, a_2, a_3, \dots, a_k, \dots).$$

Vì vậy, ví dụ, trong dãy $\Pi_1$ số hạng thứ hai là $a_2 = 4$; học kỳ thứ ba $a_3 = 6$, $k$ học kỳ thứ $a_k = 2k$. Do đó, dãy số là một tập hợp các cặp số có thứ tự $[k, a_k]$, trong đó số đầu tiên (số) là số tự nhiên và số thứ hai (chính thuật ngữ đó) là số thực. Ngoài ra, có một bản đồ tự nhiên một-một không gì khác hơn là một chức năng. Vì vậy, dãy số là một lớp hàm đặc biệt. Miền định nghĩa của các hàm như vậy là tập hợp các số tự nhiên $[1, 2, 3, 4, 5, \dots, k, \dots]$ cho các chuỗi vô hạn và mns-

$\{1, 2, 3, \dots, n\}$ dành cho số hữu hạn (ở đây $n$ là số thành viên cuối cùng của dãy hữu hạn). Ví dụ: dãy $\Pi_7$ bao gồm sáu số hạng, cho nó $n = 6$.

Bây giờ không khó để chúng ta đưa ra một định nghĩa rõ ràng về khái niệm “chuỗi số”.

Dãy số là một hàm, miền định nghĩa của componkh là tập hợp các số tự nhiên $\{1, 2, 3, \dots, k, \dots\}$ hoặc tập hợp con của các phần tử $n$ đầu tiên của nó $\{1, 2, 3, \dots, n\}$ và miền thay đổi là tập hợp các số tự nhiên.

Biểu thị thuật ngữ thứ $k$ thông qua số $k$ của nó: $a_k = f(k)$ cho phép bạn chỉ định toàn bộ chuỗi.

Phương pháp xác định trình tự này được gọi là phân tích.

Ví dụ: lưu ý rằng số hạng chung của dãy $\Pi_6 = (1, 4, 9, 16, 25, \dots)$ là $a_k = k^2$.

Trình tự phân tích rất giống với cách phân tích để xác định hàm - chỉ khi viết hàm, biến độc lập được ký hiệu là $x$ và biến phụ thuộc là $y$. Giả sử công thức $y = 2x$ là ký hiệu phân tích cho hàm tuyến tính. Nếu miền định nghĩa của nó được coi là tập hợp tất cả các số thực thì đồ thị của hàm $y = 2x$ sẽ là một đường thẳng (hình 1). Đẳng thức $a_k = 2k$ là phép gán phân tích của một chuỗi gồm bốn số (biến độc lập $k$ chỉ nhận các giá trị tự nhiên).

Biểu diễn đồ họa của chuỗi $a_k = 2k$ sẽ không phải là toàn bộ dòng mà chỉ là các điểm riêng lẻ của nó (hình 2). Một nhà toán học sẽ nói về chúng: một chuỗi các điểm rời rạc. Những điểm như vậy cho bất kỳ chuỗi nào chỉ có thể được đặt trong ô I và IV

⟦folio 69⟧

Dãy số Fibonacci *)

$$\Pi_{12} = (1, 1, 2, 3, 5, 8, 13, 21, \dots)$$

cũng được cho bởi hệ thức truy hồi $a_{k+1} = a_k + a_{k-1}$ đối với $k > 2$ và các điều kiện ban đầu $a_1 = a_2 = 1$.

Chúng tôi đã xem xét bốn cách để xác định một chuỗi số: phân tích, dạng bảng, đồ họa và định kỳ. Đương nhiên, có một phương pháp nữa - thuần túy (mô tả bằng lời nói). Ví dụ: từ “chuỗi bình phương” (hay chính xác hơn là “chuỗi bình phương các số tự nhiên”) là một mô tả bằng lời của chuỗi

$$\Pi_6 = (1, 4, 9, 16, 25, \dots, k^2, \dots).$$

Phương pháp phân tích là quan trọng nhất; phương pháp này có thể chỉ ra ngắn gọn và rõ ràng nhất quy luật xây dựng trình tự. Tuy nhiên, cũng có những chuỗi mà nhiệm vụ phân tích nói chung là không thể thực hiện được (ví dụ: chuỗi số nguyên tố) hoặc rất cồng kềnh.

Vì vậy, bây giờ chúng ta đã biết tất cả các cách chính để thiết lập trình tự. Như đã đề cập, dãy số đóng vai trò quan trọng không chỉ trong toán học mà còn trong khoa học và công nghệ. Đặc biệt ứng dụng thường ở dạng dãy số: cấp số cộng và cấp số nhân. Bạn sẽ học chúng ở lớp 8.

*) Leonardo Fibonacci là nhà toán học người Ý thế kỷ 13. Các số Fibonacci lần đầu tiên xuất hiện ở lời giải bài toán cũ về chăn nuôi thỏ. Sau đó, các số Fibonacci đã được tìm thấy trong một số bài toán thực tế và lý thuyết. Điều này được mô tả chi tiết hơn trong tập tài liệu “Số Fibonacci” của N. N. Vorobyov (Moscow, “Nauka”, 1969), được thiết kế cho học sinh trung học. (Bản dịch gần đúng)
