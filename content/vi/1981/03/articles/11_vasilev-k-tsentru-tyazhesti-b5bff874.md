---
id: 1981-3-vasilev-k-tsentru-tyazhesti-b5bff874
issue: kvant_1981_3
year: 1981
number: "3"
title: Về phía trọng tâm
authors:
  - Васильев Н. Б.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 35
page_last: 35
page_labels: "33"
tag: 1BIJ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 5f79722fc714f914e60cba58b6646cca10867cf435b92e0641fd7c1f149ef3b6
prompt_sha256: draft-1
translated_from: content/ru/1981/03/articles/11_vasilev-k-tsentru-tyazhesti-b5bff874.md
source_content_sha256: 984095cf853260ae74d95c3e4045646c4ebf2a0e174ebaa936dca06edcf5892a
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 33⟧

Về phía trọng tâm

Trong trường hợp đầu tiên
$$\frac{I_{(1)}}{I_0} = 1 + \frac{L_1}{L_2}.$$
Năng lượng của hệ khi kết thúc quá trình trong trường hợp này bằng
$$E_{(1)} = \frac{L_2 I_1^2}{2} = \frac{L_1 + L_2}{2} I_0^2 \left(1 + \frac{L_1}{L_2}\right) = E_0 \left(1 + \frac{L_1}{L_2}\right),$$
Ở đâu
$$\frac{E_{(1)}}{E_{(0)}} = 1 + \frac{L_1}{L_2}.$$
Trong trường hợp thứ hai
$$\frac{I_{(2)}}{I_0} = 1 - \frac{L_1}{L_2}.$$
$$E_{(2)} = \frac{L_2 I_2^2}{2} = \frac{(L_2 - L_1)^2}{2 L_2} I_0^2,$$
$$\frac{E_{(2)}}{E_0} = \frac{(L_2 - L_1)^2}{L_2 (L_1 + L_2)}.$$
P. Zubkov

Về phía trọng tâm

Một hệ thống gồm các bộ phận giống hệt nhau hoạt động như thế nào, quy luật chuyển động của mỗi bộ phận chỉ phụ thuộc vào một số lượng nhỏ trục? Những câu hỏi như vậy nảy sinh trong nhiều mô hình toán học của các đối tượng vật lý, hóa học, sinh học và đáp số đối với chúng, theo quy luật, là rất khó đạt được. Trong lưu ý này, chúng ta sẽ giải một bài toán thuộc loại này (M604 từ Bài toán Kvant), trong đó các quy luật chuyển động của hạt được biểu thị bằng các đường và hàm, cho phép chúng ta thu được một đáp số đơn giản: các hạt hợp nhất về một trọng tâm chung.

Công thức bài toán
a) Andrey, Victor, Sergey, bơi dưới nước, đồng thời chọn các điểm $A_0, B_0, C_0$ và ngay lập tức lặn trở lại, và Andrey quyết định bơi một phần ba quãng đường đến chỗ Victor trong một phút, Victor - một phần ba quãng đường đến chỗ Sergey, Sergey - một phần ba quãng đường đến chỗ Andrey. Sau một vài phút, họ chọn lại (điểm $A_1, B_1, C_1$ - xem Hình 1) và quyết định lặp lại thao tác này - sau nửa phút; sau đó trong một phần tư phút, v.v.

Họ sẽ gặp nhau ở đâu và khi nào?
b) Bên trong hình cầu bán kính 1 km có một triệu điểm được đánh số từ 1 đến một triệu. Mỗi điểm cùng lúc di chuyển đến 1/3 khoảng cách được đánh số tiếp theo đến điểm này là bao nhiêu giây; điểm cuối cùng của cùng một chuyển động về phía điểm đầu tiên. Chứng minh rằng sau một thời gian mọi điểm sẽ nằm trong một mặt cầu có bán kính 1 cm.

Lời giải bài toán a)
Hãy chứng minh rằng mọi điểm $A_k, B_k$ và $C_k$ đều hướng tới giới hạn về trọng tâm. Tam giác Q - giao điểm các đường trung tuyến của nó; theo nghĩa này, chúng ta có thể nói rằng Andrey, Victor và Sergey sẽ gặp nhau sau $1 + \frac{1}{2} + \frac{1}{4} + \frac{1}{8} + \ldots = 2$ phút tại điểm $Q$ (mặc dù, tất nhiên, ngay cả cá heo cũng không thể quay đầu và nhào lộn nhanh như những người bơi lội của chúng ta vào cuối phút thứ hai).

Lấy $Q$ làm gốc tọa độ và sử dụng ký hiệu vectơ của phép biến đổi $(A_k, B_k, C_k) \rightarrow (A_{k+1}, B_{k+1}, C_{k+1})$.

Như dễ thấy (Hình 2), với mỗi $k = 0, 1, 2, \ldots$
$$\vec{Q}A_{k+1} = \frac{2\vec{Q}A_k + \vec{Q}B_k}{3},$$
$$\vec{Q}B_{k+1} = \frac{2\vec{Q}B_k + \vec{Q}C_k}{3},$$
$$\vec{Q}C_{k+1} = \frac{2\vec{Q}C_k + \vec{Q}A_k}{3}.$$
Từ các công thức này, suy ra rằng điểm $Q$ là trọng tâm chung của tất cả các tam giác $A_k B_k C_k$: $\vec{Q}A_k + \vec{Q}B_k + \vec{Q}C_k = \vec{0}$ (Hình 3).

Hơn nữa, phép biến đổi $L^2 = L \cdot L$, như có thể thấy từ các công thức
$$\vec{Q}A_{k+2} = \frac{4\vec{Q}A_k + 4\vec{Q}B_k + \vec{Q}C_k}{9} = -\frac{\vec{Q}C_k}{3},$$
$$\vec{Q}B_{k+2} = -\frac{\vec{Q}A_k}{3},$$
$$\vec{Q}C_{k+2} = -\frac{\vec{Q}B_k}{3},$$
— được chuẩn bị với hệ số $(-1/3)$ và tâm $Q$ (xem Hình 1). Do đó, nếu tam giác $A_0 B_0 C_0$ nằm trong đường tròn bán kính $R$ có tâm tại điểm $Q$ thì tam giác $A_{2k} B_{2k} C_{2k}$ và tất cả các tam giác tiếp theo sẽ là
