---
id: 1990-8-resheniya-zadach-m1211-m1215-f1223-f1227-f3ce64c1
issue: kvant_1990_8
year: 1990
number: "8"
title: Lời giải bài toán M1211—M1215; F1223—F1227
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 46
page_last: 48
page_labels: 44-46
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 3e4af15b8d24d2a314dbeebda3a26d6ef49b6c1e8cf06011f5f8ef34153fbde0
prompt_sha256: draft-1
translated_from: content/ru/1990/08/articles/06_resheniya-zadach-m1211-m1215-f1223-f1227-f3ce64c1.md
source_content_sha256: 727883b67c2b95e4d5cc67916d0f1ed848c30977cba7635ccb86ec53095aa727
translation_model: draft
translation_run: vi-draft-gaps-2026-11-05
translation_quality: draft
---

⟦folio 44⟧

K. Zuev

Lời giải bài toán
M1211—M1215, F1223—F1227

Chúng ta sẽ coi mặt phẳng được chọn là nằm ngang. Chúng ta vẽ hai mặt phẳng nằm ngang tiếp xúc với quả bóng và dựng một khối đa diện trong đó hai cạnh đối diện nằm trong các mặt phẳng này, vuông góc với nhau và bằng $a$ (hình 1); chúng ta sẽ chọn sự tương ứng giữa $a$ và bán kính $R$ của quả bóng bên dưới.

Một phần của quả bóng theo mặt phẳng nằm ngang nằm cách tâm quả bóng một khoảng $R—h$, tức là cách một trong các mặt phẳng tiếp tuyến một khoảng $h$ và cách mặt kia $2R—h$, là một hình tròn có diện tích $\pi(R^2—(R—h)^2)=\pi h(2R—h)$ (hình 2).

Một phần của khối đa diện trên cùng một mặt phẳng là một hình chữ nhật tính từ các cạnh $ah/2R$ và $a(2R—h)/2R$ (rõ ràng độ dài mỗi cạnh của hình chữ nhật được biểu thị

⟦folio 45⟧

---
running_head:
folio:
---

hàm tuyến tính của $h$, ở cuối đoạn $0 \leq h \leq 2R$ nhận các giá trị 0 và $a$). Diện tích của phần này là $a^2 h(2R - h)/4R^2$. Vì vậy, chỉ cần lấy $a = 2\sqrt{\pi}R$ sao cho diện tích của các phần tương ứng bằng nhau là đủ.

N. Vasiliev

M1212. Tập hợp tất cả các số nguyên được chia thành các cấp số cộng vô hạn rời rạc từng cặp có hiệu dương $d_1$, $d_2$, $d_3$, ... Liệu điều đó có xảy ra không?

$$\frac{1}{d_1} + \frac{1}{d_2} + \frac{1}{d_3} + \dots < 0,9?$$ (*)

Hãy xem xét hai trường hợp: a) số cấp số nhân là hữu hạn;
b) số cấp số là vô hạn (trong trường hợp này, điều kiện (*) có nghĩa là tổng của số hữu hạn số hạng bất kỳ ở vế trái (*) nhỏ hơn 0,9).

Giả sử số cấp tiến là hữu hạn và bằng $k$. Hãy chứng minh rằng tổng của $1/d_1 + 1/d_2 + \dots + 1/d_k$ bằng 1. Giả sử $M$ là bội số chung (ví dụ: nhỏ nhất) của các số $d_1$, $d_2$, ..., $d_k$. Xem xét bất kỳ phân đoạn nào của $M$ số nguyên liên tiếp; nó sẽ có $M/d_i$ số hạng của cấp số $i$ với chênh lệch là $d_i$ ($i = 1, 2, \dots, k$). Vì vậy $M/d_1 + M/d_2 + \dots + M/d_k = M$.

6) Đáp số: có thể.

Chúng ta hãy đưa ra một ví dụ về vô số cấp số mà tổng $1/d_1 + 1/d_2 + 1/d_3 + \dots$ nhỏ hơn 0,9. Ta lấy $d_1$, $d_2$, $d_3$, ... các số 4, 8, 16, ..., $d_k = 2^{k+1}$, ...; thì $1/4 + 1/8 + 1/16 + \dots \leq 1/2$. Chúng ta sẽ xây dựng các tiến trình một cách tuần tự, bằng quy nạp. Cấp số đầu tiên là các số là bội số của 4. Đối với mỗi $k > 1$, giả sử rằng $k - 1$ đầu tiên đã được tạo, chúng ta sẽ chọn một trong các số hạng của cấp số $k$ có chênh lệch $d_k = 2^{k+1}$ là số nguyên modulo nhỏ nhất không có trong các số nguyên modulo đã được tạo. Vì $d_k$ chia hết cho mọi $d_i$ ($i < k$), nên tiến trình thứ $k$ không giao nhau với tiến trình trước đó. Mặt khác, cấp số chứa tất cả các số nguyên không có ngoại lệ: không quá $2k$ bước, chúng tôi sẽ đưa vào cấp số mọi số nguyên không vượt quá modulo $k - 1$.

Tương tự, với bất kỳ $\varepsilon > 0$ nào, người ta có thể xây dựng một ví dụ trong đó $1/d_1 + 1/d_2 + 1/d_3 + \dots < \varepsilon$.

A. Tolpygo, N. Konstatinov

M1213. a) Chứng minh rằng nếu cắt một hình lục giác lồi thành hình bình hành thì nó có tâm đối xứng. b) Chứng minh rằng nếu một hình lục giác lồi có mỗi đường chéo nối các đỉnh đối diện song song với hai cạnh có thể cắt thành $N$ para-
a) Xét tất cả các hình bình hành của phân chia trong đó một cạnh song song với cạnh kia $a$ của hình lục giác. Chúng tạo thành một “dòng chảy”, phần của bất kỳ đường thẳng nào song song với $a$ có cùng chiều rộng (hình 1). Trên thực tế, mỗi đoạn $a$ song song, bao gồm một hoặc nhiều cạnh song song, được nối bên trên và bên dưới bởi một “dòng” có cùng chiều rộng. Do đó, cạnh thứ hai của hình lục giác, nơi dòng chảy này đi ra, sẽ song song và bằng $a$.

(Nhân tiện, chúng ta thấy rằng mỗi cạnh của hình bình hành bất kỳ có trong phân hoạch đều song song với một

⟦folio 46⟧

---
running_head:
folio:
---

các hình có diện tích bằng nhau thì N chia cho 3.

Hình 1.

Hình 2.

một trong các cạnh của hình lục giác: nó cũng được bao gồm trong một số "dòng" đi đến đường viền của hình lục giác.)

Suy luận tương tự cho thấy bốn cạnh còn lại của hình lục giác được chia thành hai cặp cạnh song song và bằng nhau. Hiển nhiên các cạnh song song thì ngược nhau.

Cần lưu ý rằng một hình lục giác lồi có các cạnh đối song song và bằng nhau nhất thiết phải có tâm đối xứng: ba đường chéo lớn hơn của nó nối các đỉnh đối diện cắt nhau tại một điểm - điểm giữa của các đường chéo này.

6) Bây giờ hãy để hình lục giác sao cho các đường chéo của nó song song với các cạnh của nó. Theo lời giải bài toán a), chúng cắt nhau tại tâm đối xứng của hình lục giác nên chia nó thành sáu hình tam giác có diện tích bằng nhau (hình 2). Gọi S là diện tích của mỗi hình tam giác này và s là diện tích của mỗi N khung song song mà hình lục giác được chia vào, khi đó Ns=6S. Tổng diện tích các hình bình hành của mỗi ren nối hai cạnh đối diện của hình lục giác là 4S: nó bằng diện tích của hai hình bình hành được bảo vệ bởi hình 2. Do đó, ren phải bao gồm 4S/s=2N/3 hình bình hành. Suy ra N chia hết cho 3.

V. Proizvolov

M1214*. Trong một số ô của bảng hình chữ nhật có n hàng và m>n cột, các dấu hoa thị được đặt sao cho mỗi cột chứa ít nhất một dấu hoa thị. Chứng minh rằng tồn tại một dấu hoa thị sao cho số dấu hoa thị ở hàng của nó nhiều hơn số dấu hoa thị ở cột.

Từ bảng A ban đầu có dấu hoa thị, chúng ta sẽ xây dựng hai bảng mới - “đỏ” và “xanh lam”, trong đó các dấu hoa thị được thay thế bằng các số: trong bảng màu đỏ các số này bằng 1/k, trong đó k là số dấu hoa thị theo cột và màu xanh lam các số này bằng 1/l, trong đó l là số dấu hoa thị theo cột. Khi đó tổng của tất cả các số màu đỏ bằng m - số cột (trong mỗi cột tổng là 1) và tổng của tất cả các số màu xanh không quá n - số hàng (trong mỗi hàng tổng là 0 hoặc 1). Vì m>n nên tồn tại một dấu hoa thị sao cho số màu đỏ tương ứng 1/k lớn hơn số màu xanh 1/l: 1/k>1/l, do đó k<l, tức là, điều kiện bắt buộc được đáp ứng cho dấu hoa thị này.

Theo cách tương tự, chúng ta có thể chứng minh một mệnh đề mạnh mẽ hơn: trong điều kiện bài toán có một dấu sao cho
