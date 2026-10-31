---
id: 1982-10-bendukidze-treugolnik-paskalya-13aab871
issue: kvant_1982_10
year: 1982
number: "10"
title: Tam giác Pascal
authors:
  - Бендукидзе А. Д.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 47
page_last: 49
page_labels: 45-47
tag: 19WV
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 157de333c7200d8458e4a666f32acbb3545dd613621b27ac8b3aee2b0547a3cf
prompt_sha256: draft-1
translated_from: content/ru/1982/10/articles/11_bendukidze-treugolnik-paskalya-13aab871.md
source_content_sha256: 7a21c31785027e834127d0c3b72e17b36b294440c6a36fa7518621c3c493719a
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 45⟧

A. Bendukidze

Tam giác Pascal

Lấy một tờ giấy và vẽ lên đó một bảng hình vuông gồm 100 ô (mười hàng và cùng số cột). Khi chọn kích thước của bảng, hãy nhớ rằng bạn sẽ phải nhập số vào các ô của bảng, một số trong số đó sẽ có ba chữ số.

Vì vậy, bạn đã sẵn sàng chưa?

Tuyệt vời! Bắt đầu điền vào bảng.

Trong các ô của cột đầu tiên, chúng ta đặt số 1, và trong các ô của hàng đầu tiên, tất nhiên, ngoại trừ ô ngoài cùng bên trái, trong đó đã có đơn vị, có số 0. Lần lượt điền vào các ô còn lại của bảng, di chuyển từ trái sang phải và từ trên xuống dưới, theo quy luật chuyển tiếp như trong Hình 1.

Bây giờ hãy nhìn vào bảng kết quả. Its zero elements form a triangle, two sides of which (vertical and oblique) are made up of units, and the third (horizontal) has the form

1 9 36 84 126 126 84 36 9 1

(Tất nhiên, việc xây dựng có thể được tiếp tục xa hơn hoặc bị gián đoạn trước khi đến đường thứ mười.)

Tam giác thu được được gọi là tam giác Pascal, để vinh danh nhà khoa học vĩ đại người Pháp Blaise Pascal (1623-1662), người đã phát minh và nghiên cứu nó. Hình tam giác này được thay thế bằng gì? Và đây là những gì chúng ta sẽ thấy bây giờ.

Hãy theo dõi các tập hợp con

Hãy xem xét tập hợp $M_4$, bao gồm bốn quả bóng khác nhau - quần vợt, bóng chuyền, bóng đá và bóng rổ (Hình 2). Hãy tìm tất cả các tập con của nó (bao gồm cả tập trống $\varnothing$ và tất cả đám đông $M_4$), nhóm

Cơm. 1. Hình 2.

Ozelementov 1 phần tử 2 phần tử 3 phần tử 4 phần tử

Cơm. 3.

⟦folio 46⟧

Cơm. 4.

phân loại chúng theo số lượng phần tử (Hình 3) và viết ra một dòng có bao nhiêu tập hợp con polluchils trong mỗi nhóm:

1 4 6 4 1

Dòng này có quen không? Vâng, hóa ra đó là đường thẳng thứ năm của tam giác Pascal. Đây không phải là tai nạn. Nếu lấy tập hợp $M_3$ gồm ba phần tử, thì chúng ta sẽ nhận được 1 3 3 1 - hàng thứ tư của tam giác Pascal. Nói chung, nếu bạn lấy một tập hợp $M_n$ gồm $n$ phần tử và tạo một hàng từ số tập hợp con 0 phần tử của nó, số tập hợp con 1 phần tử, số tập hợp con phần tử (n-1) và số tập hợp con phần tử n, bạn sẽ nhận được hàng thứ $(n+1)$ của tam giác Pascal.

Hãy kiểm tra lại điều này để biết $n=0, 1, 2$. Thật vậy, mọi thứ đều theo thứ tự (Hình 4).

Để chứng minh điều này trong trường hợp tổng quát, chỉ cần kiểm tra xem mỗi đường thẳng có được từ đường trước đó theo cùng một quy luật chuyển tiếp như tam giác Pascal hay không là đủ. Và điều này thực sự đúng.

Ví dụ: hãy xem cách thu được số lượng tập hợp con 2 phần tử $M_4$. Để làm điều này, hãy tạm thời giấu một quả bóng tennis trong túi của chúng ta - polluch bộ $M_3$. Nó đã có ba tập con 2 phần tử:

Cơm. 5.

Để có phần còn lại, bạn cần lấy một quả bóng tennis ra khỏi túi và thêm nó vào các tập con 1 phần tử $M_3$:

Cơm. 6.

Chúng tôi nhận được $3+3=6$, như mong đợi theo luật chuyển tiếp. Rõ ràng là lý do này mang tính tổng quát; có thể tiến hành tìm quy luật chuyển đổi sang số tập con phần tử $k$ của phần tử $n$ cho bất kỳ $k \leq n$ nào.

Bây giờ, để thiết lập số tập hợp con của năm phần tử thành một tập hợp gồm tám phần tử, không cần phải thực hiện các phép liệt kê phức tạp. đáp số (70) kết thúc được viết ở vị trí thứ năm của dòng thứ chín trong tam giác Pascal.

Không, tam giác Pascal còn hữu ích hơn thế.

Hãy mở dấu ngoặc

Bằng cách lần lượt mở ngoặc và dẫn các thuật ngữ tương tự, không khó để tìm ra rằng

$$(1+x)^2=1+2x+1x$$
$$(1+x)^3=1+3x+3x^2+1x^3$$
$$(1+x)^4=1+4x+6x^2+4x^3+1x^4$$

Việc tìm $(1+x)^5$ theo cách này đã khó hơn và những bạn siêng năng nhất sẽ không muốn đếm $(1+x)^8$. Nhưng có cần thiết phải đếm không? Không phải đáp số được chuẩn bị theo đường thẳng của tam giác Pascal sao?

⟦folio 47⟧

Ở đầu dòng tỷ lệ cược
1 2 1
1 3 3 1
1 4 6 4 1

trùng với các dòng đầu tiên của tam giác Pascal. Để chứng minh rằng điều này sẽ tiếp tục xảy ra, chỉ cần tìm quy luật chuyển tiếp vận hành ở đây là đủ. Nhưng, ví dụ,
$(1+x)^5 = (1+x)(1+x)^4 = (1+x)(1+4x+6x^2+4x^3+1x^4)$;
chẳng hạn, hệ số cho $x^3$ được lấy (khi mở dấu ngoặc cuối cùng) dưới dạng tổng của các hệ số cho $x^2$ và $x^3$ từ dòng trước - chúng ta nhận được $10=6+4$, như trong tam giác Pascal. Rõ ràng là lý do này là chung chung.

Chúng ta đã chứng minh rằng dãy hệ số để tăng lũy ​​thừa $x$ trong việc khai triển song song $(1+x)^n$ trùng với hàng thứ $(n+1)$ của tam giác Pascal.

Một lần nữa, tam giác Pascal giúp chúng ta tiết kiệm thời gian: chỉ cần nhìn vào nó, chúng ta có thể viết ngay mà không cần tính toán
$(a+b)^9 = a^9 + 9a^8b + 36a^7b^2 + 84a^6b^3 + 126a^5b^4 + 126a^4b^5 + 84a^3b^6 + 36a^2b^7 + 9ab^8 + b^9$.

Tính chất của tam giác Pascal

Bằng cách loại bỏ các số 0, bảng của chúng ta có thể được viết lại dưới dạng tam giác, đối xứng hơn:

Cơm. 7.
2. Có bao nhiêu a) hai chữ số b) có ba chữ số, các chữ số được sắp xếp theo thứ tự giảm dần?
3. Số tam giác là số điểm trong các tam giác có kiểu như trên Hình 8. Làm thế nào để tìm các số tam giác trong tam giác Pascal?

Cơm. 8.
4. Biểu thị dưới dạng tổng của các đơn thức a) $(a-b)^6$; 6) $(x-2y)^5$.
