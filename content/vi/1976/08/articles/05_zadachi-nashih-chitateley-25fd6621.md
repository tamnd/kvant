---
id: 1976-8-zadachi-nashih-chitateley-25fd6621
issue: kvant_1976_8
year: 1976
number: "8"
title: Bài toán độc giả của chúng tôi
rubric: smes
page_first: 18
page_last: 18
tag: GZ6A
lang: vi
source: kvant_digital
extraction: vision
content_sha256: d0fd2d4782b1337d15d266e85b774cc4c4da9b17c1fcf4b1d01bd2baa15a4ffc
prompt_sha256: draft-1
translated_from: content/ru/1976/08/articles/05_zadachi-nashih-chitateley-25fd6621.md
source_content_sha256: 515c228dbde0bd0032dfaeb9157de7be553467fc38a64554502f88b1e9a1f78c
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

trong tích của đa thức tối giản:
$$\bar{q} = \bar{q}_1 \cdot \dots \cdot \bar{q}_s.$$
Bậc của mỗi đa thức $q_i$ nhỏ hơn bậc của đa thức $q$. Sau đó $\bar{u} \cdot \bar{v} = q \cdot \bar{q}_1 \cdot \dots \cdot \bar{q}_s$. Bằng quy nạp, nếu $\bar{u} \cdot \bar{v}$ chia hết cho $\bar{q}_i$ (với mỗi $i$), thì $\bar{u}$ hoặc $\bar{v}$ chia hết cho $\bar{q}_i$. Hủy liên tiếp tích $u \cdot v$ bằng $\bar{q}_1, \dots, \bar{q}_i$, chúng ta thu được đẳng thức $\tilde{u} \cdot \tilde{v} = q$ ($\tilde{u}$ và $\tilde{v}$ là các đa thức thu được từ $u$ và $v$ bằng cách rút gọn tương ứng các đa thức $\bar{q}_i$). Nhưng $q$ là một đa thức tối giản, nên $\tilde{u} = c \cdot q$ hoặc $\tilde{v} = c \cdot q$. Tuy nhiên, những đẳng thức này không thể được thỏa mãn (do bậc của đa thức đang xét). Do đó, giả định rằng $\bar{u} \cdot \tilde{v} \neq 0$, tức là $\bar{q} \neq 0$, là không chính xác; điều này có nghĩa là $\bar{u} = 0$ hoặc $\tilde{v} = 0$ và tuyên bố đã được chứng minh.

Bây giờ chúng ta hãy chứng minh tính duy nhất của khai triển thành tích của các đa thức tối giản. Chúng tôi có:

$$p_1 \cdot p_2 \cdot \dots \cdot p_l = q_1 \cdot q_2 \cdot \dots \cdot q_s.$$
Đặt $u = p_1$, $v = p_2 \cdot \dots \cdot p_l$, chúng ta thu được rằng $u$ chia hết cho $q_1$, và sau đó $p_1 = cq_1$, vì $p_1$ là tối giản; hoặc $v$ được chia cho $q_1$. Trong trường hợp thứ hai, chúng tôi đặt $p_2 = u_1$ và $p_3 \cdot \dots \cdot p_l = v_1$; chúng tôi thấy rằng $p_2 = c \cdot q_1$ hoặc $p_3 \cdot \dots \cdot p_l$ chia hết cho $q_1$, v.v. cho đến khi chúng tôi tìm thấy số $i$ mà $p_i = c \cdot q_1$. Làm tương tự với $q_2$, chúng ta tìm thấy $k$ sao cho $p_k = c \cdot q_2$, v.v., cho tất cả $m = 1, \dots, s$. Từ đây chúng ta cũng thu được $l = s$ đó.

B. Hãy chứng minh rằng nếu tích của các đa thức xen kẽ từng cặp $p_1 \cdot p_2 \cdot \dots \cdot p_k$ bằng bậc $n$ của một số đa thức $q$: $p_1 \cdot p_2 \cdot \dots \cdot p_k = q^n$, thì mỗi đa thức là bậc $n$ của một số đa thức $f_i : p_i = f_i^n$.

Ta hãy phân tích đa thức $q$ thành các đa thức không dẫn được: $q = q_1 \cdot q_2 \cdot \dots \cdot q_m$. Sau đó $q^n = q_1^n \cdot q_2^n \cdot \dots \cdot q_m^n$. Lấy đa thức $p_1$ và đặt $p_{11}$ là đa thức tối giản được đưa vào khai triển của nó. Do tính duy nhất của việc phân tích thành các đa thức tối giản nên $p_{11}$ trùng với một số đa thức $q_l$, tức là đa thức $p_1$ chia hết cho $q_l$. Nhưng các đa thức $p_i$, trong đó $i \neq 1$, không chia hết cho $q_l$ (vì $p_1, \dots, p_k$ là các đa thức ghép đôi), và khi đó đa thức $p_1$ cũng chia hết cho $q_l^n$, tức là $p_1 = q_l^n \cdot \bar{p}_1$. Áp dụng lý luận tương tự cho đa thức $\bar{p}_1$, chúng ta thấy rằng $p_1 = q_l^n \cdot q_s^n \cdot \dots \cdot q_r^n = f_i^n$, trong đó $f_1 = q_l \cdot q_s \cdot \dots \cdot q_r$. Chúng ta sẽ làm tương tự với các đa thức còn lại $p_i$; $i \neq 1$.

Bài toán
của chúng tôi
độc giả

1. Cho một tam giác $ABC$ có cạnh $a, b, c$ và các đường trung tuyến $m_a, m_b, m_c$. Chứng minh sự bình đẳng của cô ấy

a) $\frac{m_a^2}{a^2} + \frac{m_b^2}{b^2} + \frac{m_c^2}{c^2} \geq \frac{9}{4}$;

b) $\frac{m_a}{a} + \frac{m_b}{b} + \frac{m_c}{c} \geq \frac{3\sqrt{3}}{2}$.

Khi nào sự bình đẳng đạt được trong những bất bình đẳng này?

2. Cho một tứ giác lồi tùy ý $ABCD$ (có thể suy biến - hai đỉnh của nó có thể trùng nhau). Điểm $P, K, S, N$ lần lượt là trung điểm của cạnh $AB, BC, CD, DA$. Hãy để $(AK) \cap (BN) = L; (KD) \cap (NC) = M; (PC) \cap (BS) = Q; (AS) \cap (PD) = T$. Chứng minh rằng

a) $\frac{S_{KMN}}{S_{ABCD}} \leq \frac{1}{3}$;

b) $\frac{1}{3} \leq \frac{S_{KMN} + S_{PQST}}{S_{ABCD}} \leq \frac{1}{2}$.

3. Lại $ABCD$ là một tứ giác lồi tùy ý, các điểm $E, F, G, H$ lần lượt là trung điểm của cạnh $AB, BC, CD, DA$. Hãy biểu thị nó bằng $(AF) \cap (BG) = K; (BG) \cap (CH) = L; (CH) \cap (DE) = M; (DE) \cap (AF) = N$. Chứng minh rằng

$$\frac{1}{6} \leq \frac{S_{KLMN}}{S_{ABCD}} \leq \frac{1}{5}.$$

V. Matizen
(Novosibirsk)
