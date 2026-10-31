---
id: 1982-6-otvet-na-vopros-chitatelya-n-p-ratnikova-o-reshenii-neravenstva-s-integralom-0ac063de
issue: kvant_1982_6
year: 1982
number: "6"
title: '[Đáp số cho câu hỏi của độc giả N.P. Ratnikov về các bất đẳng thức lời giải với tích phân]'
rubric: raznoe
page_first: 16
page_last: 16
page_labels: "14"
tag: WAC8
lang: vi
source: kvant_digital
extraction: vision
content_sha256: adc02d8da528d36dd7dba2b8bf827cc9c635c08718d96809439bbc563401e578
prompt_sha256: draft-1
translated_from: content/ru/1982/06/articles/03_otvet-na-vopros-chitatelya-n-p-ratnikova-o-reshenii-neravenstva-s-integralom-0ac063de.md
source_content_sha256: 72903e98843be94909be87ce61919d804765906f63ad2bc318d92c5d7bd1d93b
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 14⟧

Hỏi - chúng tôi trả lời

Bạn nói đúng: theo định nghĩa của tích phân được đưa ra trong sách giáo khoa (“Đại số và phần đầu của phân tích 9-10”, đoạn 60), để tồn tại tích phân $\int_a^b f(x) dx$ thì hàm bên trong $f$ phải liên tục trên đoạn có điểm cuối $a, b$ (nghĩa là trên $[a; b]$ cho $a < b$ và trên $[b; a]$ cho $a \geq b$).

Đáp số, được chỉ định trong «Kvant», thu được bằng phép nội suy được định dạng quá mức không tính đến các điều kiện mà công thức Newton-Leibniz là đúng

$$\int_a^b f(x) dx = F(x) \bigg|_a^b.$$

Công thức này đúng nếu hàm $f$ liên tục trên $[a; b]$ và $F'(x) = f(x)$ ở mọi nơi trên $[a; b]$.

Pozny

$$\int_0^x \frac{dy}{(y+1)^2} = -\frac{1}{y+1} \bigg|_0^x$$

chỉ với $x > -1$ và bất đẳng thức này tương đương với hệ

$$\left\{ \begin{array}{l} \frac{9x-15}{19} < -\frac{1}{y+1} \bigg|_0^x -1 \\ x > -1. \end{array} \right.$$

Đúng đáp số trong bài toán: $\emptyset$.

Nhân tiện, từ (*) nó suy ra

$$\int_0^x \frac{dy}{(y+1)^2} = \frac{1}{x+1} -1.$$

Với $x < -1$, chúng ta thu được một kết quả nghịch lý: tích phân của hàm dương, nghĩa là, dường như là diện tích, là âm (hãy nhớ rằng $\int_a^b f(x) dx$ là diện tích của $a < b$ và $f(x) \geq 0$ trên $[a; b]$).

Đối với những người quen với khái niệm tích phân suy rộng, hãy lưu ý rằng với $x_0 < -1$ tích phân $\int_0^x \frac{dy}{(y+1)^2}$ không tồn tại.
