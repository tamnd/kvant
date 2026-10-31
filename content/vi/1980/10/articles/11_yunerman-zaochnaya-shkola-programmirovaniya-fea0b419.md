---
id: 1980-10-yunerman-zaochnaya-shkola-programmirovaniya-fea0b419
issue: kvant_1980_10
year: 1980
number: "10"
title: Trường lập trình tương ứng
authors:
  - Юнерман Н. А.
rubric: raznoe
rubric_sub: Разное
page_first: 49
page_last: 51
page_labels: 47-49
tag: I2VE
lang: vi
source: kvant_digital
extraction: vision
content_sha256: eb190c323b3b25494fa1568fa4d79ae5692fed19eb0e3dfe1dd2cbd98d5d5637
prompt_sha256: draft-1
translated_from: content/ru/1980/10/articles/11_yunerman-zaochnaya-shkola-programmirovaniya-fea0b419.md
source_content_sha256: b0b86e95690d1c1224b5ec152dce8a5530aa814cbe833d86059125db38a774cc
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 47⟧

Trường lập trình tương ứng
Bài 10: Lập trình bài toán trong Hệ tọa độ cực

Tài liệu trong bài học này dành cho học sinh lớp 8-10. Đối với học sinh tiểu học, tài liệu này được coi là tùy chọn.

Về hệ tọa độ cực
Để xác định vị trí của một điểm trên mặt phẳng, có nhiều hệ tọa độ khác nhau. Cùng với hệ thống bạn biết từ sách giáo khoa ở trường (nó được gọi là `dekartовой`), đối với lời giải nhiều bài toán sử dụng hệ tọa độ `полярную`.

Tọa độ cực của một điểm trên mặt phẳng là hai số xác định vị trí của điểm này so với một điểm cố định $O$ nào đó, gọi là `полюсом`, chứ không phải

$$\rho = \sqrt{x^2 + y^2}, \quad \sin \varphi = \frac{y}{\sqrt{x^2 + y^2}},$$

trong quá trình biến đổi nghịch đảo - theo các công thức

$$x = \varphi \cos \varphi, \quad y = \varphi \sin \varphi.$$

Archimedes xoắn ốc
Giả sử rằng chúng ta cần xây dựng một đường cong được mô tả bởi một điểm chuyển động với tốc độ không đổi $v$ dọc theo một tia quay quanh cực $O$ với tốc độ góc không đổi $\omega$. Phương trình của đường cong này trong tọa độ cực là

$$\rho = a\varphi,$$

ở đâu $a = \frac{v}{\omega}$. Đường cong (1) được gọi là `спирали Архимеда` (Hình 3).

Để xây dựng đường xoắn ốc Archimedes trên máy tính bằng hệ thống đồ họa Shpar, thuận tiện là sử dụng quy trình POLAR («Kvant», 1980, Số 1, trang 56).

Hãy tự kiểm tra xem chương trình (2), được viết bằng ngôn ngữ Rapier, là hình vẽ của đường xoắn ốc Archimedean (cạnh của chu trình BYE được chọn ở mặt $5 \times 2\pi$, cung cấp p-

⟦folio 48⟧

đẩy gót của vòng xoắn ốc). Hãy nhớ rằng khi sử dụng quy trình ỨNG DỤNG và CHÙM, đường kính thứ nhất đóng vai trò là bán kính cực và đường kính thứ hai đóng vai trò là góc cực.
P(100.100); H(50,50);
.POLAR; 2->A; 0->FI;
3.1416->PI; P(0,0);
(2)
KHI FI<10*PI::
FI+0,01->FI;
L(A*FI,FI)
TẤT CẢ;
.KẾT THÚC;
Nhiệm vụ 10.1. Viết chương trình xây dựng các đường cong được mô tả bởi các phương trình:
a) $\varphi = a (1 + \cos \varphi)$ – hình tim,
b) $\varphi = \frac{a}{\varphi}$ là một đường xoắn ốc hyperbol.

Gia đình “hoa”
Trên trang thứ hai của trang bìa có in lại các hình vẽ về một họ “bông hoa” được làm trên máy tính. Phương trình của họ đường cong này trong tọa độ cực có dạng
$\varphi = A \sin B \varphi$.
(3)

Nhiệm vụ 10.2.
1) Điều gì quyết định hệ số $A$?
2) Các cánh hoa riêng lẻ xuất hiện theo thứ tự nào?
3) Hình ảnh sẽ thay đổi như thế nào nếu trong phương trình (3) chúng ta thay thế sin Vf bằng |sin Vf|?

4) Số lượng cánh hoa liên quan như thế nào đến giá trị của hệ số B?
Xét riêng trường hợp B chẵn và B lẻ.
5) Cách tổ chức vòng lặp sao cho:
a) vẽ những “bông hoa” theo thứ tự hiển thị trên trang bìa (khôi phục chương trình)?
b) chỉ miêu tả trong họ “những bông hoa” những thứ có giá trị phi nhân loại của tham số B?
b) vẽ một họ “hoa” chỉ có các giá trị nguyên là B?
(Không cần lập trình chú thích dưới ảnh.)

Hình lục giác đều
Trong Olympic Lập trình («Kvant», 1980, số 3), hai bài toán đã được đề xuất, sẽ dễ giải hơn nếu bạn sử dụng hệ tọa độ cực.
Bài toán đầu tiên trong số chúng (bài toán 3) được xây dựng như sau: tạo một chương trình mô tả một hình 16 cạnh đều trong đó tất cả các đường chéo được vẽ không đi qua tâm.
Chúng ta hãy xem xét một hệ tọa độ cực có một cực ở tâm đa giác $O$ và một trục cực $OX$ hướng dọc theo tia $OA_{16}$ (Hình 4).
Hãy tìm tọa độ cực của các đỉnh của đa giác này. Tọa độ đầu tiên (chiều cực)

⟦folio 49⟧

dius) đối với tất cả các đỉnh đều bằng nhau và bằng bán kính của đường tròn ngoại tiếp R, tọa độ thứ hai (góc cực) được tính theo công thức $\varphi_K = (\pi/8)*K$, trong đó K là số đỉnh.

Để vẽ được hình theo yêu cầu, bạn cần nối đỉnh có số N (1<N<16) với tất cả các đỉnh có số lớn hơn N, ngoại trừ đỉnh có số (N+8) (rốt cuộc là đoạn nối các đỉnh có số N và N+8 đi qua tâm). Nếu chúng ta nối mỗi đỉnh N với tất cả các đỉnh khác thì mỗi đoạn sẽ được vẽ hai lần.

Cho tham số R các giá trị khác nhau, ta sẽ thu được 16 giác đều tương tự.

Các tham số thủ tục có thể là bất kỳ biểu thức số học nào. Ví dụ: trong quy trình TIẾP CẬN và BEAM, tọa độ của điểm tương ứng được tính toán trước bằng cách sử dụng các biểu thức. Trong thủ tục FRAME và BEGIN, các biểu thức được sử dụng làm tham số để đảm bảo rằng đa giác được định vị chính xác, nằm chính giữa trường vẽ. Theo thủ tục DIAG với tham số K, đỉnh số N sẽ được nối với đỉnh số K. PERCENT DIAG K;
P(R, N*PI/8);
L(R, K*PI/8);
KSC;
Chương trình cuối cùng trông như sau:
50—>R;
P(2*R+50,2*R+50);
H(R+25, R+25); 3.1416—>PI;
.POLAR; 1—>N;
TẠM BIỆT <16::
1+N—>K;
TẠM BIỆT<16::
NẾU K/=N+8 ĐẾN
DIAG(K); K+1—>K
TẤT CẢ;
N+1—>N
TẤT CẢ;
.KẾT THÚC;
Kết quả của chương trình này là Hình 5.

Nhiệm vụ 10.3. Viết thủ tục vẽ bức tường N đúng.
