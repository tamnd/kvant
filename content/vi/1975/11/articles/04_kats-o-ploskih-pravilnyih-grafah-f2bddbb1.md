---
id: 1975-11-kats-o-ploskih-pravilnyih-grafah-f2bddbb1
issue: kvant_1975_11
year: 1975
number: "11"
title: Trên đồ thị chính quy phẳng
authors:
  - Кац М. Г.
rubric: osnovnye-stati
page_first: 14
page_last: 17
page_labels: 12-15
tag: 85P8
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c2b5796783d815b2292dbbeefe3b2cc39b154de3c0764046573a0d22aa4cc206
prompt_sha256: draft-1
translated_from: content/ru/1975/11/articles/04_kats-o-ploskih-pravilnyih-grafah-f2bddbb1.md
source_content_sha256: 0f9ab18cac0fc99898f253c6aa43c3fee67e717aa3b18507cb9d613846ade63f
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 12⟧

Trên đồ thị chính quy phẳng

M. G. Katz

Hãy bắt đầu với các định nghĩa.
Đồ thị là một tập hợp hữu hạn các điểm và đường cong nối chúng trên một mặt phẳng (chúng ta sẽ gọi những điểm này là đỉnh và các cạnh của đường cong).
Chúng ta sẽ xem xét các đồ thị có các tính chất sau:
1) các cạnh của đồ thị không giao nhau (đồ thị có thuộc tính này được gọi là phẳng);
2) không có hai đỉnh nào được nối bởi nhiều hơn một cạnh;
3) hai đỉnh bất kỳ của đồ thị được nối với nhau bằng một liên kết các cạnh (đồ thị như vậy được gọi là liên thông);
4) mỗi cạnh nối hai đỉnh khác nhau.

Nếu bạn cắt mặt phẳng dọc theo các cạnh của đồ thị thì nó sẽ chia thành nhiều phần - các mặt của đồ thị. Phần không giới hạn sẽ được gọi là cạnh ngoài. Các mặt còn lại là mặt trong.

Một mặt được gọi là $n$-cạnh nếu số cạnh gặp phải khi đi ngang qua mặt đó dọc theo các ranh giới của nó bằng $n$. Ví dụ. Trong Hình 1,a chỉ có một mặt - sáu vây ngoài, trong Hình 1.6 - hai mặt: ba vây trong và ba vây ngoài.

Một cạnh được gọi là cạnh ngoài (tương ứng là trong) nếu khi đi qua các mặt trong của đồ thị, nó xuất hiện tương ứng một hoặc hai lần. Ví dụ. Trong Hình 2, cạnh $a$ là bên ngoài, cạnh $b$ là bên trong; trong Hình 1,a không có cạnh bên ngoài và bên trong.

Chúng ta hãy biểu thị lần lượt bằng $B$, $P$ và $\Gamma$ số đỉnh, cạnh và tất cả các mặt của đồ thị, bao gồm cả mặt ngoài. Ba đại lượng này có liên hệ với nhau bằng công thức Euler nổi tiếng $^*$

$$B - P + \Gamma = 2.$$

Chúng ta hãy biểu thị bằng $a_i$ số mặt có cạnh $i$, bao gồm cả mặt ngoài. Khi đó mối quan hệ sau đây là hợp lệ:

$$2P = 3a_3 + 4a_4 + 5a_5 + \dots$$

Hãy tự mình chứng minh điều đó.

Vì $\Gamma = a_3 + a_4 + \dots$ nên tương ứng (1) có thể viết dưới dạng

$$2P = 3\Gamma + a_4 + 2a_5 + \dots,$$

hoặc

$$\Gamma = \frac{2}{3}P - \frac{1}{3}(a_4 + 2a_5 + \dots).$$

Thay giá trị này $\Gamma$ vào công thức Euler, chúng ta nhận được

$$B - P + \frac{2}{3}P - \frac{1}{3}(a_4 + 2a_5 + \dots) = 2,$$

*) Xem «Kvant», 1974, số 8.

⟦folio 13⟧

$$3B - P = 6 + \sum_{i=1}^{i+3} i a_{i+3}.$$

Chúng ta gọi bậc $\deg V_i$ của một đỉnh $V_i$ là số cạnh xuất phát từ đỉnh này. Vì mỗi cạnh nối hai đỉnh nên $\sum_{i=1}^{i+3} \deg V_i = 2P$.

Hãy giới thiệu đại lượng $\deg V$, gọi là bậc trung bình của đồ thị:

$$\deg V = \frac{\sum_{i=1}^{i+3} \deg V_i}{B}.$$

Nó tuân theo định nghĩa rằng $\sum_{i=1}^{i+3} \deg V_i = B \deg V$, tức là $2P = B \cdot \deg V$, từ đó $P = \frac{1}{2} B \cdot \deg V$.

Thay biểu thức này cho $P$ vào công thức (2), chúng ta thu được

$$3B - \frac{1}{2} B \cdot \deg V = 6 + \sum_{i=1}^{i+3} i a_{i+3},$$

hoặc

$$B \cdot (6 - \deg V) = 12 + 2 \sum_{i=1}^{i+3} i a_{i+3}.$$

Do đó, bậc trung bình của đồ thị luôn nhỏ hơn 6, nhưng nó có thể gần đến 6 tùy ý bạn—hãy chứng minh điều đó.

Chúng ta gọi đồ thị là $n$-giác nếu mỗi đỉnh của nó có cùng số cạnh. Rõ ràng, bậc trung bình của một đồ thị chính quy bằng số cạnh xuất hiện từ mỗi đỉnh (chúng ta sẽ gọi đơn giản là bậc của một đồ thị chính quy).

Từ công thức (3) suy ra

Định lý 1. Bậc của đồ thị đều không vượt quá 5.

Một loại đồ thị đều rất thú vị là đồ thị bậc 5. Hãy xem một đồ thị đều bậc 5 có thể có bao nhiêu đỉnh.

Rõ ràng (xem công thức (3)) là một đồ thị chính quy ở bậc này không thể có ít hơn 12 đỉnh. Một đồ thị thông thường có 12 đỉnh thực sự tồn tại và được biểu diễn bằng hình chiếu của một khối hai mươi mặt lên một mặt phẳng (Hình 3). Vì tích $B \cdot \deg V = 2P$ là số chẵn nên ta thấy rằng không có đồ thị bậc 5 nào có số đỉnh là lẻ.

Bây giờ chúng ta sẽ mô tả một phương pháp xây dựng đồ thị thông thường với số đỉnh bất kỳ là 4REM (không nhỏ hơn 12), ngoại trừ các đồ thị có 14, 18 và 22 đỉnh. Đối với đồ thị có 14 và 18 đỉnh, hãy xem phần thay thế ở cuối thống kê; Một đồ thị có 22 đỉnh được thể hiện trong Hình 4.

Lấy hàm lồi $n$-gon $A = (A_1, A_2, \dots, A_n)$. Bên trong nó, chúng ta đặt $n$-gon $B = (B_1, B_2, \dots, B_n)$. Bằng cách nối trung điểm của các cạnh liền kề của $n$-giác $B$, chúng ta thu được $n$-giác $C = (C_1, C_2, \dots, C_n)$, trong đó $C_i$ là trung điểm của $B_i B_{i+1}$, $i = 1, 2, \dots, n-1$; $C_n$ - giữa $B_n B_1$.

Hình 3.

Hình 4.

⟦folio 14⟧

Hình 5.

Bằng cách nối trung điểm của các cạnh nối của $n$-giác $C$, ta thu được $n$-gon $D = (D_1, \dots, D_n)$, trong đó $D_i$ là trung điểm của $C_{i-1}C_i$, $i = 2, \dots, n$; $D_1$ là điểm giữa của cạnh $C_nC_1$. Bây giờ kết nối $A_i$ với $B_i$, $B_{i+1}$ và $C_i$ và $B_i$ với $D_i$, chúng ta thu được biểu đồ bậc 5 với $4n$ đỉnh. Một ví dụ về cách xây dựng đồ thị có 20 đỉnh (cho $n = 5$) được hiển thị trong Hình 5.

Bây giờ chúng ta hãy chỉ ra cách có thể thêm 2 đỉnh nữa vào biểu đồ đã được xây dựng với các đỉnh $4n$.

Chúng ta hãy loại bỏ một trong các cạnh ngoài của đồ thị có đỉnh $4n$. Có hai đỉnh trong biểu đồ, mỗi đỉnh có 4 cạnh - trong Hình 6 đây là các đỉnh $A$ và $B$. Hãy chọn một điểm trên cạnh không lân cận—điểm $C$ và kết nối nó với các đỉnh $A$ và $B$. Đỉnh $C$ đã được thêm vào các đỉnh của biểu đồ ban đầu, từ đó xuất hiện 4 cạnh. Hãy loại bỏ thêm một cạnh bên ngoài và xây dựng điểm $C'$ theo cách tương tự. Bằng cách kết nối điểm $C$ với điểm $C'$, chúng ta thu được một biểu đồ mới bậc 5, đã có nhiều hơn 2 đỉnh so với điểm ban đầu (xem Hình 6).

Lưu ý rằng việc cộng hai đỉnh được mô tả vào một đồ thị có $4n$ chỉ có thể thực hiện được trong trường hợp đồ thị ban đầu có ít nhất sáu cạnh ngoài (vì cấu trúc của chúng tôi không cung cấp phương pháp xây dựng cho đồ thị có 14, 18 và 22 đỉnh).

Vì vậy, nó đã được chứng minh.

Định lý 2. Số đỉnh của đồ thị chính quy bậc 5 có thể là

⟦folio 15⟧

hai điểm cuối của hai cạnh không trùng nhau bất kỳ của mặt này. Điều này chứng minh Định lý 3 cho đồ thị bậc 3.

2°. Đồ thị bậc 4. Từ công thức (3) ta thấy đồ thị đều bậc 4 có ít nhất sáu đỉnh. Một đồ thị có sáu đỉnh được thể hiện trong Hình 7. Từ công thức (3), cũng suy ra rằng đồ thị bậc 4 có số đỉnh lớn hơn 6 luôn có một mặt không phải là tam giác. Hãy loại bỏ (xem Hình 8) cạnh AB của mặt này và nối các đỉnh A và B với bất kỳ điểm nào trên một cạnh không liền kề với cạnh AB (một cạnh cũng sẽ được tìm thấy, vì một mặt không có ba cạnh được chọn). Do đó, một đỉnh được thêm vào biểu đồ ban đầu với số đỉnh lớn hơn 6 (ví dụ về cách xây dựng được trình bày trong Hình 8). Cơ sở quy nạp có thể là một đồ thị có 8 đỉnh, được minh họa trên Hình 9.

Như vậy, ta đã chứng minh rằng tồn tại đồ thị bậc 4 có 6 đỉnh và có số đỉnh bất kỳ ít nhất là 8.

Chứng minh rằng không tồn tại đồ thị bậc 4 có 7 đỉnh. Để làm điều này, chúng tôi chứng minh rằng một đồ thị như vậy chứa đồ thị con được hiển thị trong Hình 10, như đã biết, không khớp với mặt phẳng nếu không có các điểm tự giao.

Xét một đỉnh A tùy ý của đồ thị nguồn và các đỉnh A₁, A₂, A₃, A₄ mà từ đó nó được kết nối. Hai đỉnh còn lại của chúng tôi

Hình 9. Hình 10.

Chúng ta biểu thị đồ thị thứ hai bằng A' và A''. Có hai trường hợp có thể xảy ra.

1°. Các đỉnh A' và A'' không được kết nối với nhau.

Sau đó, để bốn cạnh xuất hiện từ A' và A'', chúng phải được nối với cả bốn đỉnh A₁, ..., A₄ (bốn cạnh đã thoát ra khỏi đỉnh A. Trong trường hợp này, thật dễ dàng để chọn đồ thị con mong muốn: như các đỉnh I II, III (xem Hình 10), chúng ta có thể lấy các đỉnh A, A' và A'', và là các đỉnh IV, V, VI - các đỉnh A₁, A₂, A₃.

2°. Các đỉnh A' và A'' được nối với nhau.

Trong trường hợp này, ba cạnh nữa xuất hiện từ các đỉnh A' và A'' đến một số đỉnh A₁, ..., A₄. Do đó, ít nhất hai trong số các đỉnh A₁, ..., A₄ được nối với cả A' và A''. Gọi đây là các đỉnh A₁ và A₂. Khoảng cách lại là hai trường hợp.

1) Một trong các đỉnh A₃ và A₄ được nối với cả A' và A''. Trong trường hợp này, đồ thị con được yêu cầu là đồ thị con có các đỉnh A, A', A'', A₁, A₂, A₃.

2) A₃ và A₄ được kết nối chính xác với một trong các đỉnh A' và A'', chẳng hạn như A₃ với A' và A₄ với A''. Hãy loại bỏ cạnh AA₄ và thay thế hai cạnh A₃A₄*) và A₄A'' bằng một cạnh A₃A'''. Đã thu được đồ thị con yêu cầu - đó là đồ thị con có các đỉnh A, A', A'', A₁, A₂, A₃.

Quét. Từ công thức (3) và (1), suy ra rằng một đồ thị đều bậc 5 với 14 đỉnh chỉ nên có một đỉnh có bốn cạnh và 22 đỉnh có ba cạnh. Bằng cách liệt kê không phải tổng thống, người ta có thể xác minh rằng biểu đồ như vậy không tồn tại.

Đối với đồ thị bậc 5 có 18 đỉnh, có ba khả năng xảy ra:

1) 3 bốn xương sườn, 26 ba xương sườn;
2) 1 năm sườn, 1 bốn sườn, 27 ba sườn;
3) 1 sáu sườn, 28 ba sườn.

Trong trường hợp này, phép liệt kê không được cung cấp và câu hỏi về sự tồn tại của đồ thị đều bậc 5 với 18 đỉnh vẫn còn bỏ ngỏ.

*) Cạnh A₃A₄, rất indo, phải tồn tại.
