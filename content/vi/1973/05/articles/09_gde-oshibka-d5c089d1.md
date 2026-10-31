---
id: 1973-5-gde-oshibka-d5c089d1
issue: kvant_1973_5
year: 1973
number: "5"
title: Sai lầm ở đâu?
rubric: smes
page_first: 44
page_last: 44
page_labels: "42"
tag: CY62
lang: vi
source: kvant_digital
extraction: vision
content_sha256: f6b289ec01a091bda1d0943c6ed4cad95187e88901001770ceb170f05ae5e9a0
prompt_sha256: draft-1
translated_from: content/ru/1973/05/articles/09_gde-oshibka-d5c089d1.md
source_content_sha256: fddcdd823e37f86014e67677d920a5f422269fcf808d99c1d1298daf50d33478
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 42⟧

Đó là dành cho thời kỳ, không phải cho thời kỳ chính.

Định lý 3. Nếu $T_1 > 0$ là khoảng thời gian $f_1(x)$, $T_2 > 0$ là khoảng thời gian $f_2(x)$, thì việc nhận $T_1$ và $T_2$ là đồng chiều và sucestium của giá trị $x$, thuộc miền định nghĩa đồng thời $f_1$ và $f_2$, thì $f(x) = f_1(x) + f_2(x)$ là hàm tuần hoàn có toàn bộ chu kỳ có số $T$, bằng bội số chung (kể cả số nhỏ nhất) của các chu kỳ $T_1$ và $T_2$.

Bằng chứng. Đặt $T$ là bội số chung nhỏ nhất của các phân số tương ứng $T_1$ và $T_2$. Khi đó có các số tự nhiên $k$ và $l$ sao cho $T = kT_1$ và $T = lT_2$. Nếu $x$ là bất kỳ miền nào trong miền $f(x)$ thì

$$f(x) = f_1(x) + f_2(x) = f_1(x + kT_1) + f_2(x + lT_2) = f_1(x + T) + f_2(x + T) = f(x + T).$$

Tất cả các ràng buộc có trong các điều kiện của định lý đều được sử dụng trong chuỗi đẳng thức đã cho.

Nói chung, một định lý tương tự có thể được chứng minh cho một loại tổ hợp hàm $f_1$ và $f_2$ rộng hơn nhiều, bao gồm cả tích số. Tuy nhiên, việc xem xét các tình huống thực tế cụ thể ở đây rõ ràng là hiệu quả hơn nhiều so với việc xây dựng bất kỳ lý thuyết chặt chẽ nào.

Bài tập
Các hàm số sau đây có tuần hoàn không và nếu có hãy tìm chu kỳ chính của chúng:

1. $2 \sin x!$;
2. $\cos 3\pi x - \sin 2\pi x$;
3. $\sin 2x\sin 3x \cos 5x$;
4. $\lg \sin x + \lg \cos x$;
5. $\lg \lg (1 + \sin x) + \lg \lg (1 - \sin x)$;
6. $|\sin \arcsin x|$;
7. $\arcsin \sin x$;
8. $\sin \frac{1}{x}$;
9. $x^2$.
10. Chứng minh rằng hàm số $\cos x^2$ không tuần hoàn.
11. Chứng minh rằng nếu hàm $\cos x + \sin ax$ tuần hoàn thì $a$ là số hữu tỉ.

Giải mã!

1. ***

2. ****** | *6*

- *6** - 6***

- **6** - ******

- ***6** - 0

Sai lầm ở đâu?

- Phương trình bậc hai có bao nhiêu nghiệm?
“Tất nhiên là hai,” bạn trả lời.
- Nhưng có phải luôn luôn không?

Hãy xem xét phương trình này:

$$\frac{(x-a)(x-b)}{(c-a)(c-b)} + \frac{(x-b)(x-c)}{(a-b)(a-c)} + \frac{(x-a)(x-c)}{(b-a)(b-c)} = 1$$

(ở đây $a, b$ và $c$ là các số riêng biệt theo cặp).

Hãy thay thế $x=a$. Số hạng thứ nhất và thứ ba sẽ bằng không. Người thứ hai cho một. Thay thế $x=b$, chúng ta thấy rằng hai số hạng đầu tiên bằng 0 và số hạng thứ ba bằng một.

Thay thế $x=c$ cho kết quả tương tự. Vì vậy, mặc dù chúng ta có một phương trình bậc hai nhưng vẫn có ít nhất ba nghiệm! Phổ biến lời giải: phương trình bậc hai có nhiều hơn hai nghiệm!

Làm thế nào điều này xảy ra?
