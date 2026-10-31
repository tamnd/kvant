---
id: 1980-4-aleksandrov-izmelchayuschiesya-uzoryi-f7730305
issue: kvant_1980_4
year: 1980
number: "4"
title: Mẫu băm nhỏ
authors:
  - Александров С.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 28
page_last: 30
page_labels: 26-28
tag: VKMS
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 6890e1226a282963f4a635fb393bf4d0426e679615889bebda98251957736ebd
prompt_sha256: draft-1
translated_from: content/ru/1980/04/articles/08_aleksandrov-izmelchayuschiesya-uzoryi-f7730305.md
source_content_sha256: 85ce10d3ca5120f5f2268037ecd5d23a3f70ed6701bfbe525745e3abdaa820dd
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 26⟧

Cắt hoa văn

Hãy nhìn kỹ hơn vào trang đầu tiên của trang bìa - trên đó, trong một hình ngũ giác đều, có vô số các ngôi sao năm cánh, thu nhỏ về hai bên. Mục tiêu của bài học câu lạc bộ toán tiếp theo là hiểu cấu trúc tuyệt đẹp này và hiểu cách xây dựng các mô hình tương tự.

Bài toán về hình vuông ngôi sao

Mẫu trên bìa thu được như sau:

Hãy xem xét một hình ngũ giác đều trong đó có tất cả 5 đường chéo được vẽ (hình ngũ giác “đen” ở giữa trên bìa). Các đầu của các đường chéo là các đỉnh bên ngoài của ngôi sao năm cánh thu được và các điểm giao nhau của các đường chéo nằm bên trong hình ngũ giác là các đỉnh bên trong của ngôi sao này.

Đối với ngôi sao này (gọi là sao cấp 0), chúng ta sẽ gắn 5 ngôi sao tương tự có kích thước nhỏ hơn (sao cấp 1) sao cho ba đỉnh ngoài của mỗi sao cấp 1 trùng với ba đỉnh liền kề của sao cấp 0: hai đỉnh bên ngoài và một đỉnh bên trong.

Xung quanh các ngôi sao cấp một, 15 ngôi sao thậm chí còn nhỏ hơn của cấp này cũng được xây dựng theo cách tương tự và một số ngôi sao này nhất thiết phải chồng lên nhau một phần, do đó một cặp sao như vậy có một mặt chung và ngoài ra còn có một đỉnh bên ngoài. Hãy gọi một hình như vậy - được bao quanh bởi hai ngôi sao chồng lên nhau một phần - là một ngôi sao đôi.

Xung quanh các ngôi sao bậc hai, nền không bị chúng chiếm giữ sẽ được xây dựng theo cách tương tự sau ngôi sao. Hình vẽ lấp đầy một chiếc lá nho dại hoặc một người đàn ông vui tính đội chiếc mũ dựng cao được lặp lại nhiều lần với kích thước ngày càng giảm dần và hơn nữa, theo cách mà những hình vẽ này không giao nhau theo cặp và sự kết hợp của chúng tạo thành toàn bộ nền. Xung quanh mỗi hình như vậy, bạn có thể mô tả một hình thoi có góc 72° ở đỉnh (Hình 1).

Bài toán 2. Tìm tỉ số giữa diện tích của phần hình thoi bổ sung cho mục tiêu (và chiếc mũ của anh ta!) so với diện tích của toàn bộ hình thoi.

(Bạn có thể đoán rằng đáp số đến bài toán 2 bằng... đáp số đến bài toán 1.) Trong Hình 2, người đọc sẽ tự tìm thấy*):

$$\alpha = 36^\circ, \quad a = dq,$$
$$b_1 = a \text{tg} \alpha = a \sqrt{5} - 2\sqrt{5},$$
$$b_2 = b_1 q, \quad b_3 = b_2 q = b_1 q^2,$$
$$b_4 = b_3 q = b_1 q^3, \quad b_5 = b_1 q^4,$$
$$q = \frac{\sqrt{5} - 1}{2} \approx 0,618034.$$
Kết quả là tỷ lệ yêu cầu $p$ bằng
$$p = 77\sqrt{5} - \frac{343}{2} \approx 0,677234.$$

*) Nếu những tính toán này gây khó khăn cho bạn, hãy đọc phần tiếp theo trước.

⟦folio 27⟧

Chúng ta hãy chuyển sang Hình 3, hình này hơi khác so với Hình 1. Một hình thoi bậc 0 $ABFB'$, có $|AB| = a_0$, nội tiếp trong góc $LAL'$.

Hai góc giáo dục $LBF$ và $FB'L'$ được nội tiếp hai hình thoi bậc nhất $BCGC'$ và $B'C_1G'C_1'$ từ phía $a_1 = a_0q$, trong đó

$$0,5 \leq q \leq 1.$$ (1)

Để dựng hình thoi bậc hai, ta vẽ các đường thẳng $FG$ và $FG'$ cắt các đường thẳng $CH$ và $C_1'H_1'$, song song với đường chéo $AF$ của hình thoi ban đầu, các đoạn thẳng, đường chéo phục vụ của hình thoi $CDHD'$ và $C_1D_3H_1'D_3'$ tương tự như hình ban đầu. Hai hình thoi này thuộc dãy hình thoi hình nón bậc hai ở cạnh $a_2 = a_1q = a_0q^2$.

Theo cách tương tự, chúng ta sẽ dựng một loạt hình thoi bậc ba từ cạnh $a_3 = a_0q^3$, v.v.

Nếu $q < 1$ thì các đường thẳng $FG$ và $FG'$ không song song với các cạnh của góc ban đầu và cắt chúng tại một số điểm $L$ và $L'$. Điểm $L$ là tâm đồng đẳng của các hình thoi $ABFB'$, $BCGC'$, $CDHD'$, ...

Nhờ tính đối xứng, điểm $L'$ là tâm đồng nhất tương tự của các hình tương ứng. Trên đường thẳng $LL'$, ngoài hai điểm này, còn có vô số tâm đồng nhất khác của các hàng hình thoi khác nhau. Ví dụ, một trong những tâm như vậy là điểm $L''$.

Bài 3. Tìm hệ số sẵn sàng $q$ sao cho các hình thoi bao phủ hoàn toàn phần bên trong của tam giác $LAL'$ (không có khoảng trống hoặc chồng lên nhau).

Đối với điều này, điều cần và đủ là đối với một số $n$ tự nhiên, độ dài cạnh $a_i$ của hình thoi có bậc bất kỳ bằng tổng chiều dài cạnh $n$ của các hình thoi sau:

$$a_i = a_{i+1} + a_{i+2} + \dots + a_{i+n-1} + a_{i+n},$$

do đó $q$ phải thỏa mãn phương trình

$$q^n + q^{n-1} + \dots + q^2 + q - 1 = 0.$$ (2)

Đối với $n = 1$, phương trình (2) có dạng $q - 1 = 0$, do đó $q = 1$. Trong trường hợp này, các điểm $C'$ và $C_1$ trong Hình 3

⟦folio 28⟧

trùng với điểm $F$, điểm $L$ và $L'$ “tiến đến vô cùng”, và hình thoi của tất cả các đơn hàng trở nên đồng dạng (Hình 4) *).

Đối với $n=2$, phương trình (2) có dạng $q^2+q-1=0$ và nghiệm của nó, thỏa mãn điều kiện (1), bằng:

$$q_2=\frac{\sqrt{5}-1}{2}.$$

Bây giờ trong Hình 3, điểm $D'_1$ trùng với đỉnh $F$ của hình thoi ban đầu và sự sắp xếp các hình thoi bên trong góc $LAL'$ có ​​dạng như trong Hình 5. Đây là trường hợp chính mà chúng ta đã xem xét.

Tại $n=3$ nghiệm của phương trình bậc ba

$$q^3+q^2+q-1=0,$$

bị giới hạn bởi điều kiện (1), xấp xỉ bằng $q_3=0,543689$ và sự sắp xếp liên tục của các viên kim cương được minh họa trong Hình 6.

Dễ dàng nhìn thấy; rằng đối với $n>1$ vế trái của phương trình (2) là âm đối với $q=\frac{1}{2}$ và dương đối với $q=1$. Do đó, phương trình này có nghiệm $q_n$ thỏa mãn điều kiện (1) và là duy nhất (vì vế trái của phương trình (1) trả về $q>0$). Cũng dễ dàng chứng minh rằng $q_1>q_2>q_3>...>q_n>...$ và $\lim_{n\to\infty}q_n=1/2$.

Khi số $n$ tăng lên, số nguyên tố $LL'$ ngày càng tiến gần đến đỉnh $F$ của hình thoi ban đầu.

Lưới các hình thoi lấp đầy phần bên trong của góc trong trường hợp giới hạn $q_\infty=1/2$ được hiển thị trong Hình 7. Điểm $F$ và các đỉnh tương tự của hình thoi thuộc tất cả các bậc hiện xuất hiện trên cùng một đường thẳng $LL'$.

Lời giải bài toán 1

Có thể dễ dàng nhận thấy mối liên hệ giữa lưới kim cương dày đặc trong Hình 5 và thiết kế được mô tả trên trang bìa. Mối liên hệ này được minh họa

*) Trong Hình 4-8, để đẹp, vật trang trí được đánh dấu bằng màu đỏ, điều này không ảnh hưởng đến bản chất toán học của vấn đề.
