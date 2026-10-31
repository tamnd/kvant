---
id: 1984-9-kushnir-prostoy-priem-v-neprostyih-zadachah-39207606
issue: kvant_1984_9
year: 1984
number: "9"
title: Một thủ thuật đơn giản cho những nhiệm vụ khó khăn
authors:
  - Кушнир И. А.
rubric: shkola-v-kvante
page_first: 27
page_last: 28
page_labels: 25-26
tag: MHGB
lang: vi
source: kvant_digital
extraction: vision
content_sha256: d56be829dfa87e85bb207a4fdcefab8012abf3d0956a47d97b5da851ddfbe303
prompt_sha256: draft-1
translated_from: content/ru/1984/09/articles/13_kushnir-prostoy-priem-v-neprostyih-zadachah-39207606.md
source_content_sha256: 7d6fd2eebd6007cf4e76de0f29cfaa6b9dedca17e265389e3aa8082e5b69bc7c
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 25⟧

tìm giá trị $Q_T$ thỏa mãn điều kiện

$$\frac{Q-Q_T}{d} = \text{целое число},$$

(1)

trong đó $d$ là ước số nguyên tố trong cột của giá trị tìm thấy $Q_T$.

Trong hàng $R=27$, điều kiện (1) tương ứng với các giá trị bảng $Q_T=38$ trong cột ước số $d=89$ và $d=43$. Đây là các thừa số nguyên tố của số đã cho $(89 \times 43=3827)$.

Bây giờ chúng ta hãy phân tích số 5251. Khi chia nó cho 100, chúng ta được thương $Q=52$ và số dư $R=51$. Đối với các số có $R>49$, chúng ta gộp $R$ vào bảng, nhập giá trị “giảm” $R'=100-R$, tức là trong trường hợp này là $R'=100-51=49$. Trong trường hợp này, cùng với điều kiện (1), phải đáp ứng các điều kiện sau:

$$\frac{Q'+Q_T}{d} = \text{целое число},$$

(2)

ở đâu $Q'=Q+1$. Trong trường hợp này $Q'=52+1=53$.

Trong hàng $R=49$, điều kiện (2) được đáp ứng bởi $Q_T=36$, trong cột ước số $d=89$ $(53+36=89)$ và $Q_T=6$ trong cột ước số $d=59$ $(53+6=59)$. Do đó, các thừa số nguyên tố của một số đã cho là $89 \times 59=5251$.

Số đó là 51620. Sau khi chia cho 20, tất cả những gì còn lại là phân tích số 2581. Đây $R=81$. Vì vậy, $R'=100-81=19$, $Q=25$. Vì vậy, $Q'=25+1=26$.

Điều kiện (2) ở đây được ghi bằng $Q_T=63$ trong cột chia $d=89$ và $Q_T=3$ trong cột chia $d=29$. Vì vậy, $89 \times 29 \times 20=51620$.

Lưu ý rằng ước chung của cả ba số là số nguyên tố 89.

Sử dụng bảng, không khó để xác định số 10607 nêu trên là số nguyên tố. Thật vậy, trong hàng $R=07$ không có một giá trị nào $Q_T$ mà khi trừ từ $Q=106$ sẽ thỏa mãn điều kiện (1).

V. S. Khitruk

Có khả năng đương đầu với những nhiệm vụ khó khăn

Học sinh lớp 6 đã quen thuộc với công thức tính bình phương tổng hoặc hiệu của hai số. Không khó để học cách tách một hình vuông hoàn hảo khỏi một biểu thức đại số, “nhận dạng” nó và sau đó rút ra nghiệm. Những hành động này thường giúp ích cho lời giải cụ thể bài toán. Tất nhiên, bài toán bên dưới cho phép các phương pháp khác lời giải, tuy nhiên, việc biết cách sử dụng các ví dụ được chỉ định sẽ giúp người nộp đơn “tiết kiệm” thời gian rất cần thiết cho bài kiểm tra.

Rút gọn biểu thức

Ví dụ 1 (MSU, cơ chế, 1978). Hiệu $\sqrt{|40\sqrt{2}-57|}-\sqrt{40\sqrt{2}+57}$ là số nguyên. Tìm số này.

Trong cuốn sách của Yu. V. Nesterenko, S. N. OLEXNIK, M. K. Potapov “Bài toán kỳ thi tuyển sinh môn toán” (M., Nauka, 1980), các tác giả biểu thị số mong muốn bằng $x$, nhận thấy rằng $x$ là một trong các số 10 hoặc -10 và bằng cách so sánh số bị trừ và bị trừ, họ đi đến kết luận rằng $x=-10$ (tr. 132).

Hãy giải ví dụ tương tự bằng cách chọn một hình vuông hoàn chỉnh; ví dụ này sẽ hữu ích cho chúng ta sau này.

$$A=\sqrt{40\sqrt{2}+57}=\sqrt{25+40\sqrt{2}+32}=\sqrt{(5+4\sqrt{2})^2}=5+4\sqrt{2},$$

$$B=\sqrt{|40\sqrt{2}-57|}=\sqrt{|(5-4\sqrt{2})^2|}=-5+4\sqrt{2}.$$

Vì vậy, $B-A=-10$.

Ví dụ 2 (MSU, cơ chế, 1969; KPI, 1980). Đơn giản hóa:

$$\sqrt{x+2\sqrt{x-1}}+\sqrt{x-2\sqrt{x-1}}.$$

Lời giải:

$$A=\sqrt{x+2\sqrt{x-1}+1-1}+\sqrt{x-2\sqrt{x-1}+1-1}=\sqrt{(\sqrt{x-1}+1)^2}+\sqrt{(\sqrt{x-1}-1)^2}=|\sqrt{x-1}+1|+|\sqrt{x-1}-1|=\sqrt{x-1}+1+|\sqrt{x-1}-1|.$$

Rõ ràng là $x \geqslant 1$;

a) với $2 \geqslant x \geqslant 1$, ta có

⟦folio 26⟧

$$A = \sqrt{x-1} + 1 - \sqrt{x-1} + 1 = 2;$$
6) tại $x \geqslant 2$
$$A = \sqrt{x-1} + 1 + \sqrt{x-1} - 1 = 2\sqrt{x-1}.$$
Ví dụ 3 (KPI, 1980). Đơn giản hóa:
$$\frac{\sin^4 \alpha + \cos^4 \alpha - 1}{\sin^6 \alpha + \cos^6 \alpha - 1}.$$
Lời giải:
$$\frac{\sin^4 \alpha + \cos^4 \alpha - 1}{\sin^6 \alpha + \cos^6 \alpha - 1} = \frac{\sin^4 \alpha + \cos^4 \alpha + 2 \sin^2 \alpha \cos^2 \alpha - 2 \sin^2 \alpha \cos^2 \alpha - 1}{\sin^4 \alpha + \cos^4 \alpha + 2 \sin^2 \alpha \cos^2 \alpha - 3 \sin^2 \alpha \cos^2 \alpha - 1} = \frac{(\sin^2 \alpha + \cos^2 \alpha)^2 - 2 \sin^2 \alpha \cos^2 \alpha - 1}{(\sin^2 \alpha + \cos^2 \alpha)^2 - 3 \sin^2 \alpha \cos^2 \alpha - 1} = \frac{2}{3}.$$
Lời giải phương trình
Đối với lời giải phương trình vô tỷ, người ta không nên vội bình phương chúng; thật đáng để xem liệu có thể cô lập nó không?
Ví dụ 4 (KPI, 1979). Giải phương trình:
$$\sqrt{x-2} + \sqrt{2x-5} + \sqrt{x+2+3\sqrt{2x-5}} = 7\sqrt{2}.$$
Lời giải:
chúng tôi có
$$\frac{1}{\sqrt{2}}(\sqrt{2x-5} + 2\sqrt{2x-5} + 1) + \sqrt{2x-5} + 6\sqrt{2x-5} + 9) = \frac{1}{\sqrt{2}}(\sqrt{(\sqrt{2x-5}+1)^2} + \sqrt{(\sqrt{2x-5}+3)^2} = \frac{1}{\sqrt{2}}(|\sqrt{2x-5}+1| + |\sqrt{2x-5}+3|).$$
Vậy phương trình đã cho tương đương với phương trình
$$\frac{1}{\sqrt{2}}(\sqrt{2x-5} + 1 + \sqrt{2x-5} + 3) = 7\sqrt{2}$$
hoặc $2\sqrt{2x-5} = 10$, từ đâu $x = 15$.
Ví dụ 5 (KSU, Khoa Kinh tế, 1978). Giải phương trình:
$(\sqrt{4+2\sqrt{3}} - \sqrt{4-2\sqrt{3}})^{2x} + 2^{2x+3} = 144.$
Lời giải:
chúng tôi có
$$\sqrt{4+2\sqrt{3}} = \sqrt{3+2\sqrt{3}} + 1 = \sqrt{(\sqrt{3}+1)^2} = \sqrt{3}+1;$$
tương tự như $\sqrt{4-2\sqrt{3}} = \sqrt{3}-1$. Do đó, phương trình đã cho sẽ có dạng
$$4^x + 8\cdot 4^x = 144, x = 2.$$
Ví dụ 6 (MSU, 1978, Khoa Ngữ văn). Số $\alpha$ được chọn sao cho phương trình $\sqrt{x-\sqrt{3}} + \alpha^2 x^2 + 2\alpha x(\sqrt{6}-\sqrt{3}) = 6\sqrt{2}-9$ có lời giải. Tìm lời giải.
Lời giải: Biểu thị $x_1$ nghiệm của phương trình. Sau đó $x_1 \neq 0$ và $\sqrt{x_1-\sqrt{3}} + \alpha^2 x_1^2 + 2\alpha x_1(\sqrt{6}-\sqrt{3}) - 6\sqrt{2}+9 = 0$, hoặc
$$\alpha^2 + 2\alpha \left(\frac{\sqrt{6}-\sqrt{3}}{x_1}\right) + \frac{\sqrt{x_1-\sqrt{3}} + 9 - 6\sqrt{2}}{x_1^2} = 0.$$
Chúng ta hãy chọn một hình vuông hoàn chỉnh đối với các số $x_1$ và $\alpha$. chúng tôi có
$$\left(\alpha + \frac{\sqrt{6}-\sqrt{3}}{x_1}\right)^2 + \frac{\sqrt{x_1-\sqrt{3}}}{x_1^2} = 0.$$
Vì mỗi số hạng không âm nên $x_1 = \sqrt{3}$ và $\alpha = 1 - \sqrt{2}$.
Ví dụ 7. Giải phương trình $\sin^2 x + \sin^2 y = \sin x \sin y + \sin x \sin y - 1.$
Lời giải: Phương trình này tương đương với:
$(\sin^2 x - 2 \sin x + 1) + (\sin^2 y - 2 \sin y + 1) + (\sin^2 x + \sin^2 y - 2 \sin x \sin y) = 0$ hoặc $(\sin x - 1)^2 + (\sin y - 1)^2 + (\sin x - \sin y)^2 = 0$, từ đâu $x = \sin y = 1$, $x = \sin y$. Do đó, phương trình lời giải sẽ có dạng bất kỳ cặp nào
$$x = \frac{\pi}{2} + 2\pi k, y = \frac{\pi}{2} + 2\pi n, k, n \in Z.$$
Bài tập
1. (MSU, 1979, Khoa Kinh tế) Giải phương trình: $\log_{3x+7}(9+12x+4x^2) + \log_{2x+3}\times(6x^2+23x+21) = 4.$
2. (KSU, 1978, Khoa Hóa học) Giải phương trình: $(\sqrt{6+2\sqrt{5}} - \sqrt{6-2\sqrt{5}})^{2x} + 2^{2(x+1)} = 320.$
3. (MSU, 1965, cơ học) Tìm tất cả các cặp số thỏa mãn phương trình
$$\cos x + \cos y - \cos(x+y) = \frac{3}{2}.$$
4. (KSU, 1973, cơ học) Giải bất đẳng thức $\sqrt{x+4\sqrt{x-4}} - \sqrt{x-4\sqrt{x-4}} \geq 3.$
5. (MSU, 1982, Khoa Sinh học) Tìm giá trị lớn nhất và lớn nhất của hàm số
$$y(x) = x + \sqrt{(x^2+6x+9)(x^2+2x+1)}$$
trên đoạn $[-4; -\frac{5}{4}].$

I. A. Kushinr
