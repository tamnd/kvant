---
id: 1979-5-sevryuk-variatsii-na-temu-klassicheskih-neravenstv-9fd48ec4
issue: kvant_1979_5
year: 1979
number: "5"
title: Các biến thể về chủ đề của bất đẳng thức cổ điển
authors:
  - Севрюк М. Б.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 20
page_last: 22
page_labels: 18-20
tag: BKFN
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c4c21d4cadccbaa8d8bb5f89041bf83af183f95c2e711ed1db264b6a146ed5d9
prompt_sha256: draft-1
translated_from: content/ru/1979/05/articles/05_sevryuk-variatsii-na-temu-klassicheskih-neravenstv-9fd48ec4.md
source_content_sha256: abba9462a930ff67d0dfa9baba6b6a4757307714873df878c61bde5c6edc2950
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 18⟧

Sự thay đổi về chủ đề của bất đẳng thức cổ điển

Ghi chú này được viết bởi học sinh lớp 10 Misha Sevriok dựa trên báo cáo của em tại hội nghị Trường Moscow số 2. Nó chứng minh những bất đẳng thức mà tác giả đã tìm ra, những bất đẳng thức dễ thấy và khái quát về trung bình số học và trung bình hình học. Tất nhiên, chúng không phải là mới: trong các lĩnh vực toán học cổ điển, thực tế không có “điểm trống” nào có thể đạt được nếu không được đào tạo về máy chủ. Ví dụ, bằng chứng về các bất đẳng thức đã đề cập có trong cuốn sách tuyệt vời nhưng khó tiếp cận của Hardy, Leathwood và Polyan *); tuy nhiên, các chứng minh tổ hợp thuần túy của M. Sevriok là nguyên bản và đơn giản hơn đáng kể.

Những bất đẳng thức thuộc loại này cũng được nhiều độc giả khác của chúng tôi quan tâm. Ngoài ghi chú của M. Sevriok, trong số này chúng tôi xuất bản dưới dạng bài toán (M565) bất đẳng thức Maclaurin, các chứng minh thú vị được gửi bởi M. Rosenberg, cũng như bài toán P. Vinokur, cho thấy khả năng ứng dụng của bất đẳng thức loại này trong nhiều tình huống khác nhau.

Trong thời đại máy tính điện tử của chúng ta, thật vui khi biết rằng nghệ thuật sống động của các phép biến đổi đại số vẫn không mất đi sự hấp dẫn và không ngừng hữu ích...

Ngay cả người Hy Lạp cổ đại cũng biết rằng trung bình hình học $\sqrt{ab}$ của hai số không âm không vượt quá trung bình số học $\frac{a+b}{2}$ của chúng. Định lý này đúng với mọi số không âm $a_1, a_2, \dots, a_n$:

$$\frac{1}{n} (a_1 + \cdots + a_n) \geq (a_1 \dots a_n)^{1/n}$$

(sự bình đẳng chỉ xảy ra khi tất cả $a_i$ khớp); nó sẽ làm cơ sở cho mọi thứ tiếp theo.

Chuỗi bất đẳng thức đầu tiên

Ở đây, như trước đây, $a_1, a_2, \dots, a_n$ là các số không âm tùy ý. Ngoài tổng $S_1$ của tất cả $a_i$ riêng biệt, như trong bất đẳng thức (1), chúng ta sẽ quan tâm đến tổng các tích cặp có thể có của chúng $S_2 = a_1 a_2 + a_1 a_3 + \dots + a_{n-1} a_n$,

tổng các tích có thể có của ba

$$S_3 = a_1 a_2 a_3 + a_1 a_2 a_4 + \dots + a_{n-2} a_{n-1} a_n$$

và nói chung là tổng $S_k$ sản phẩm của họ trên $k$ thành phần ($k \leq n$). Tương tự, ngoài tích $P_1$ của tất cả $a_i$ riêng lẻ, chúng ta sẽ quan tâm đến tích của tất cả các tổng theo cặp có thể có

$$P_2 = (a_1 + a_2) (a_1 + a_3) \dots \dots (a_{n-1} + a_n)$$

tích của tổng ba

$$P_3 = (a_1 + a_2 + a_3) (a_1 + a_2 + a_4) \dots \dots (a_{n-2} + a_{n-1} + a_n)$$

và nói chung là tích $P_k$ của tổng của chúng trên $k$ số hạng ($k \leq n$).

Hóa ra các đại lượng $S_k$ và $P_k$ cho $k=1, 2, \dots, n$ có ​​thể có các giới hạn trên và giới hạn dưới sau (theo $S_1 = a_1 + \dots + a_n$ và $P_1 = a_1 \dots a_n$):

$$C_n^k \left( \frac{S_1}{n} \right)^k \geq S_k \geq C_n^k P_k^{\frac{k}{n}}$$

$$\left( \frac{k}{n} \right)^{C_n^k} S_1^{C_n^k} \geq P_k \geq k^{C_n^k} P_1^{\frac{k}{n}}$$

Mở rộng việc ghi lại các công thức này trông rất nội bộ. Đừng tự bắn mình! Tốt hơn hết hãy giải mã một trong những công thức này (đối với các giá trị cụ thể, không quá lớn của $k, n$) và bạn sẽ thấy rằng tất cả những điều này không quá đáng sợ. Ví dụ: với $k=3, n=4$, biểu mẫu

⟦folio 19⟧

mula $(I_2)$ trông như thế này:

$$4 \left( \frac{a_1 + a_2 + a_3 + a_4}{4} \right)^3 \geq a_1 a_2 a_3 + a_1 a_2 a_4 + a_1 a_3 a_4 + a_2 a_3 a_4 \geq 4 \left( a_1 a_2 a_3 a_4 \right)^{3/4}.$$

Tại $k=1$ các bất đẳng thức $(I_2)$, $(II_1)$ chuyển thành $(1)$; $(I_1)$ và $(II_2)$ trở thành $(1)$ tại $k=n$ (kiểm tra!). Như vậy, cả bốn bất đẳng thức $(I)$, $(II)$ đều có thể coi là dạng tổng quát hóa của bất đẳng thức $(1)$.

Chứng minh bất đẳng thức $(I_2)$. Để ngắn gọn, chúng ta hãy đặt $C = C_n^k$ và bằng $\tilde{p}_1, \tilde{p}_2, \dots, \tilde{p}_{C_n^k}$ chúng ta biểu thị các số hạng của tổng $S_k$ (trên thực tế, có $C = C_n^k$ trong số chúng). Vì $\frac{S_k}{C}$ là trung bình số học của các số $\tilde{p}_1, \tilde{p}_2, \dots, \tilde{p}_c$, theo (1)

$$\frac{S_k}{C} \geq \left( \tilde{p}_1 \tilde{p}_2 \dots \tilde{p}_c \right)^{1/C}.$$

Mỗi $a_i$ là thành phần của chính xác $C_{n-1}^{k-1}$ các số $\tilde{p}_1, \tilde{p}_2, \dots, \tilde{p}_c$. Vì vậy, $\left( \tilde{p}_1 \tilde{p}_2 \dots \tilde{p}_c \right)^{1/C} = P_1^v$, ở đâu $v = \frac{C_{n-1}^{k-1}}{C} = \frac{C_{n-1}^{k-1}}{C_n^k} = \frac{k}{n}$. Do đó, $\frac{S_k}{C} \geq P_1^{k/n}$, tức là $S_k \geq CP_1^{k/n}$, là điều bắt buộc.

Đẳng thức trong $(I_2)$ xảy ra khi $k=n$, khi $a_1 = \dots = a_n$ hoặc khi ít nhất $n-k+1$ số từ tập hợp $\{a_1, a_2, \dots, a_n\}$ bằng 0.

Chứng minh bất đẳng thức $(II_2)$. Chúng ta hãy biểu thị bằng $\tilde{s}_1, \tilde{s}_2, \dots, \tilde{s}_C$ các thành phần của sản phẩm $P_k$ (như trước $C = C_n^k$). Chúng ta hãy đặt $q = k^C$ cho ngắn gọn. Ở phía bên trái của bất đẳng thức, tức là trong biểu thức $P_k$, chúng ta mở ngoặc. Chúng ta thu được tổng $q$ số hạng, mỗi số hạng là tích của $C$ số từ tập hợp $\{a_1, a_2, \dots, a_n\}$, lấy một số từ mỗi $\tilde{s}_i$. Trong tích của các số hạng này, mỗi $a_i$ chứa một thành phần, do tính đối xứng, có cùng số lần (chúng tôi biểu thị số này bằng $\mu$). Do đó tích này bằng $P_1^\mu$, do đó

$$\frac{P_k}{q} = \left( P_1^\mu \right)^{1/q},$$

hơn nữa, sự bình đẳng diễn ra khi và chỉ nếu tất cả các số hạng $q$ của chúng ta đều bằng nhau, đặc biệt là xảy ra với $a_1 = \dots = a_n$; sử dụng cái này, tìm $\mu$.

Hãy để $a_1 = a_2 = \dots = a_n = 2$. Khi đó trong (2) đẳng thức $\tilde{s}_1 = \tilde{s}_2 = \dots = \tilde{s}_C = 2k, P_1 = 2^n$ giữ nguyên, do đó $\frac{(2k)^C}{q} = \left( 2^n \right)^{\frac{\mu}{q}}, 2^C = 2^{\frac{n\mu}{q}}, \mu = \frac{Cq}{n}$.

Thay giá trị này vào (2), chúng ta thu được $(II_2)$.

Rõ ràng là sự bằng nhau xảy ra khi $k=1$ hoặc khi $a_1 = \dots = a_n$ hoặc khi ít nhất $k$ số từ tập hợp $\{a_1, a_2, \dots, a_n\}$ bằng 0.

Để chứng minh bất đẳng thức $(I_1)$ ta cần đến bất đẳng thức Maclaurin. Hãy đặt $S_k = \frac{S_k}{C_n^k}$. Sau đó

$$\bar{S}_1 \geq \bar{S}_2^{\frac{1}{2}} \geq \bar{S}_3^{\frac{1}{3}} \geq \dots \geq \bar{S}_n^{\frac{1}{n}}$$

(nếu tất cả $a_i$ đều dương và không phải tất cả $a_i$ đều giống nhau thì hãy nhập dấu dừng >).

Chứng minh của bất đẳng thức này có thể tìm thấy trong HLP, trang 69 *).

Chứng minh bất đẳng thức $(I_1)$ ngay sau đây từ (3). Quả thực $S_k C^{-1} = \bar{S}_k, S_1 n^{-1} = \bar{S}_1$, vì $C_n^k = n$. Điều này có nghĩa là $(I_1)$ có dạng $\bar{S}_1 \geq \bar{S}_k^{\frac{1}{k}}$ và được chứa trong (3).

Hãy tự chứng minh điều đó bằng cách sử dụng bất đẳng thức Maclaurin cho $(I_2)$.

Bất đẳng thức $(II_1)$ được chứng minh tương tự như $(I_2)$; Chúng tôi để lại bằng chứng này cho người đọc.

Điều kiện đẳng thức trong $(I_1)$: $a_1 = a_2 = \dots = a_n$ hoặc $k=1$, trong $(II_1)$: $a_1 = a_2 = \dots = a_n$ hoặc $k=n$.

*) Một bằng chứng khác do M. Rosenberg gửi sẽ được công bố dưới dạng lời giải bài toán M565.

⟦folio 20⟧

Chuỗi bất đẳng thức thứ hai

Ở đây $a_1, a_2, \dots, a_n - n$ là các số x dương. Hãy để chúng tôi giới thiệu ký hiệu sau (chúng tôi giả sử rằng $k \leq n - 1$):

$$\Sigma_i = \frac{\tilde{s}_i}{S_1 - \tilde{s}_i},$$

$$\Pi_i = \frac{\tilde{p}_i}{P_1 - \tilde{p}_i} \left( i = 1, 2, \dots, C = C_n^k \right).$$

Chúng tôi quan tâm đến ranh giới của những thay đổi trong giá trị $^*$ $\Sigma_1 + \Sigma_2 + \dots + \Sigma_C, \Pi_1 + \Pi_2 + \dots + \Pi_C, \Sigma_1 \Sigma_2 \dots \Sigma_C, \Pi_1 \Pi_2 \dots \Pi_C$. Hóa ra các giới hạn này của biểu thức $\Sigma_1 \Sigma_2 \dots \Sigma_C$ phụ thuộc vào $k$; chính xác:

$$\text{при } k \in \left[ 1, \frac{n}{2} \right] \quad \text{имеем}$$
$$\Sigma_1 \dots \dots \Sigma_C \in \left[ 0, \left( \frac{k}{n-k} \right)^C \right], \quad (\text{III}_1)$$

$$\text{при } k = \frac{n}{2} \quad \text{(если } n \text{ четно)}$$
$$\Sigma_1 \dots \dots \Sigma_C = 1, \quad (\text{III}_2)$$

$$\text{при } k \in \left[ \frac{n}{2}, n-1 \right] \quad \text{имеем}$$
$$\Sigma_1 \dots \dots \Sigma_C \in \left[ \left( \frac{k}{n-k} \right)^C, +\infty \right]. \quad (\text{III}_3)$$

Bằng chứng cho lời khai (III$_3$). Hãy gọi quan hệ loại thứ nhất là quan hệ từ $n$ số $a_1, a_2, \dots, a_n$ đến $k$, quan hệ loại thứ hai - quan hệ từ cùng số đến $n-k$. Cũng sẽ có $C$, kể từ $C_n^k = C_n^{n-k}$. Phần bên trong của quan hệ loại thứ hai theo thứ tự tùy ý và tổng các số trong quan hệ loại thứ $i$ sẽ được ký hiệu là $\tilde{s}_i'$. Rõ ràng là $\tilde{s}_1' \cdot \tilde{s}_2' \dots \tilde{s}_C' = \left( S_1 - \tilde{s}_1 \right) \times \left( S_1 - \tilde{s}_2 \right) \dots \left( S_1 - \tilde{s}_C \right)$. Chúng ta hãy xem xét một mối quan hệ tùy ý thuộc loại thứ nhất với số $i - \left( a_{i_1}, a_{i_2}, \dots, a_{i_k} \right)$. Từ $k > \frac{n}{2}$ suy ra $k > n-k$ và từ các số có trong quan hệ này, có thể tạo ra các quan hệ $C_n^{n-k}$ thuộc loại thứ hai (với một số số $\gamma_1, \gamma_2, \dots, \gamma_R$, trong đó $R = C_n^{n-k}$) và mỗi số từ tập hợp $\{ a_{i_1}, a_{i_2}, \dots, a_{i_k} \}$ sẽ được đưa vào chính xác $C_n^{n-k-1}$ các quan hệ thuộc loại thứ hai như vậy. Vì vậy, $C_n^{n-k-1} \tilde{s}_i = \tilde{s}'_{\gamma_1} + \tilde{s}'_{\gamma_2} + \dots + \tilde{s}'_{\gamma_R}$.

Từ (1) và (4) suy ra $C_n^{n-k-1} \tilde{s}_i \geq R \left( \tilde{s}'_{\gamma_1} \tilde{s}'_{\gamma_2} \dots \tilde{s}'_{\gamma_R} \right)^{1/R}$. (5)

*) Những đại lượng này rất thú vị cho một số câu hỏi trong lý thuyết xác suất (ed.).
