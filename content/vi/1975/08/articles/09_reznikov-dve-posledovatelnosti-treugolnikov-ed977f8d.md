---
id: 1975-8-reznikov-dve-posledovatelnosti-treugolnikov-ed977f8d
issue: kvant_1975_8
year: 1975
number: "8"
title: Hai chuỗi hình tam giác
authors:
  - Резников А. Г.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 48
page_last: 49
page_labels: 46-47
tag: QXB0
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 31b38a83929320fa5f68b6a1fe82fa7ed41d509787e0363cebdac095721aa38f
prompt_sha256: draft-1
translated_from: content/ru/1975/08/articles/09_reznikov-dve-posledovatelnosti-treugolnikov-ed977f8d.md
source_content_sha256: 898b0404e7e7d6dd6e003ed598110b739f67650461693980d35a87a29f5169e3
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 46⟧

Xét một tam giác tùy ý $ABC$. Bằng $A_1B_1C_1$, chúng ta biểu thị một tam giác có các đỉnh là điểm tiếp xúc của đường tròn nội tiếp $ABC$ với các cạnh của nó (Hình 1). Tương tự, đối với tam giác $A_1B_1C_1$, chúng ta xác định tam giác $A_2B_2C_2$, v.v. Như vậy, chúng ta thu được một dãy các tam giác nội tiếp nhau

$$ABC, A_1B_1C_1, A_2B_2C_2, \dots$$

(1)

Chúng ta xác định một dãy tam giác khác như sau: bằng $A^{(1)}B^{(1)}C^{(1)}$ chúng ta biểu thị một tam giác có các đỉnh là giao điểm của các đường phân giác của tam giác $ABC$ với đường tròn ngoại tiếp. Tương tự, đối với tam giác $A^{(1)}B^{(1)}C^{(1)}$, chúng ta xác định tam giác $A^{(2)}B^{(2)}C^{(2)}$, v.v. Do đó, chúng ta thu được một dãy các hình tam giác

$$ABC, A^{(1)}B^{(1)}C^{(1)}, A^{(2)}B^{(2)}C^{(2)}, \dots$$

(2)

Trong phần này chúng ta sẽ nghiên cứu một số tính chất của dãy (1) và (2). Nhiều tuyên bố của chúng tôi

Cơm. 1.

Chúng tôi không chứng minh điều đó. Chúng tôi hy vọng bạn sẽ tự mình thực hiện việc này.

1. Dễ dàng biểu diễn các góc của tam giác $A_1B_1C_1$ theo các góc của tam giác ban đầu. Ví dụ: $\hat{A}_1 = 90^\circ - \frac{1}{2}\hat{A}$. Tương tự như vậy, $\hat{A}_2 = 90^\circ - \frac{1}{2}\hat{A}_1$ và nói chung $\hat{A}_n = 90^\circ - \frac{1}{2}\hat{A}_{n-1}$.

Nói cách khác, chuỗi các góc $A, A_1, A_2, \dots, A_n, \dots$ sẽ xử lý cấp số cộng-hình học. Những tiến triển như vậy được mô tả trong bài viết của Ya. N. Sukonika ở vị trí «Kvant» số 1 năm nay. Sử dụng kết quả của bài viết này, chúng tôi nhận được biểu thức sau:

$$\hat{A}_n = 60^\circ + \left(-\frac{1}{2}\right)^n (\hat{A} - 60^\circ).$$

(3)

Các góc của tam giác $A^{(1)}B^{(1)}C^{(1)}$ bằng các góc tương ứng của tam giác $A_1B_1C_1$ (kiểm tra!). Điều này có nghĩa là dãy (1) và (2) là dãy các tam giác đồng dạng.

Từ công thức (3), suy ra rằng nếu $A \neq 60^\circ$ thì tất cả $\hat{A}_n \neq 60^\circ$ và $\lim_{n \to \infty} \hat{A}_n = 60^\circ$. Tương tự như vậy $\lim_{\hat{B}_n \to 60^\circ} \hat{B}_n = 60^\circ$ và điều tương tự cũng đúng với các góc $\hat{A}^{(n)}, \hat{B}^{(n)}, \hat{C}^{(n)}$.

2. Gọi $p_n, S_n R_n, r_n$ lần lượt là nửa chu vi, diện tích và bán kính đường tròn ngoại tiếp và nội tiếp của tam giác $A_nB_nC_n$. Các giá trị $p^{(n)}, S^{(n)}, R^{(n)}, r^{(n)}$ của một tam giác được xác định tương tự

⟦folio 47⟧

$A^{(n)}B^{(n)}C^{(n)}$ và $p_0, S_0, R_0, r_0$ cho tam giác ban đầu $ABC$. Rõ ràng là $R^{(n)}=R_0, R_n=r_{n-1}$.

Hãy chứng minh điều đó

$$S_n = \frac{1}{2} \frac{R_n}{R_{n-1}} S_{n-1}. \tag{4}$$

Chứng minh điều đó là đủ

$$S_1 = \frac{1}{2} \cdot \frac{r_0}{R_0} S_0. \tag{4'}$$

Bằng chứng. Dễ dàng nhận thấy (xem Hình 1) rằng

$$S_{A_1OB_1} = \frac{1}{2} r_0^2 \sin B_1OA_1 = \frac{1}{2} r_0^2 \sin \hat{C},$$

$$S_{B_1OC_1} = \frac{1}{2} r_0^2 \sin \hat{A},$$

$$S_{C_1OA_1} = \frac{1}{2} r_0^2 \sin \hat{B}.$$

Vì vậy $S_1 = \frac{1}{2} r_0^2 (\sin \hat{A} + \sin \hat{B} + \sin \hat{C})$. Nhưng theo định lý sin $AB = 2R_0 \sin \hat{C}, BC = 2R_0 \sin \hat{A}, CA = 2R_0 \sin B$. Vì vậy, $\sin \hat{A} + \sin \hat{B} + \sin \hat{C} = p_0/R_0$. Như vậy,

$$S_1 = \frac{1}{2} r_0^2 \cdot \frac{p_0}{R_0} =$$

$$= \frac{1}{2} \cdot \frac{r_0}{R_0} r_0 p_0 = \frac{1}{2} \frac{r_0}{R_0} S_0.$$

3. Hãy chứng minh rằng dãy $S_0, S^{(1)}, S^{(2)}, \ldots, S^{(n)}$ phụ thuộc vào độ tuổi.

Bởi vì

$$S_0 = 2 R_0^2 \sin \hat{A} \sin \hat{B} \sin \hat{C},$$

$$S^{(1)} = 2 R_0^2 \cos \frac{\hat{A}}{2} \cos \frac{\hat{B}}{2} \cos \frac{\hat{C}}{2}^*),$$

thì bất đẳng thức $S^{(1)} \geq S_0$ tương đương với bất đẳng thức

$$\sin \frac{A}{2} \sin \frac{\hat{B}}{2} \sin \frac{\hat{C}}{2} \leq \frac{1}{8}. \tag{5}$$

Hãy chứng minh bất đẳng thức (5). Sử dụng cái gì

$$\hat{C} = 180^\circ - (\hat{A} + \hat{B}),$$

Hãy biến đổi (5) như thế này:

$$\cos \hat{A} + \cos \hat{B} - \cos (\hat{A} + \hat{B}) \leq \frac{3}{2}$$

hoặc

$$2 \cos \frac{\hat{A} + \hat{B}}{2} \cos \frac{\hat{A} - \hat{B}}{2} - 2 \cos^2 \frac{\hat{A} + \hat{B}}{2} -$$

$$-\frac{1}{2} \leq 0,$$

$$-2 \left( \cos \frac{\hat{A} + \hat{B}}{2} - \frac{1}{2} \cos \frac{\hat{A} - \hat{B}}{2} \right)^2 -$$

$$-\frac{1}{2} \left( 1 - \cos^2 \frac{\hat{A} - \hat{B}}{2} \right) \leq 0. \tag{5'}$$

Bất đẳng thức cuối cùng là hiển nhiên. Từ (5'), suy ra đẳng thức trong (5) chỉ xảy ra trong trường hợp tất cả các góc của tam giác bằng $60^\circ$. Vì các tam giác $A_1B_1C_1$ và $A^{(1)}B^{(1)}C^{(1)}$ giống nhau và hệ số tương tự là $\frac{R_0}{r_0}$, nên

$$S^{(1)} = \frac{1}{2} \frac{R_0}{r_0} S_0 \tag{6}$$

(xem công thức 4'). Nhưng vì $S^{(1)} \geq S_0$, điều này dẫn đến bất đẳng thức nổi tiếng $R_0 \geq 2r_0$.

Vì trình tự $S_0, S^{(1)}, S^{(2)}, \ldots, S^{(n)}$ liên quan đến độ tuổi nên

Vì trình tự $S_0, S^{(1)}, S^{(2)}, \ldots, S^{(n)}$ liên quan đến độ tuổi nên

4. Có thể chứng minh rằng đối với dãy nửa chu vi $p_0, p_1, p_2, \ldots$, bất đẳng thức sau đúng:

$$p_n \leq \frac{1}{2} p_{n-1}. \tag{7}$$

Như trước đây, chỉ cần chứng minh (7) cho $n=1$ là đủ:

$$p_1 \leq \frac{1}{2} p_0. \tag{7'}$$
