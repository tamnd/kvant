---
id: 1983-10-pecherskiy-nx-xn-0b008072
issue: kvant_1983_10
year: 1983
number: "10"
title: n^x = x^n
authors:
  - Печерский Л. Б.
rubric: shkola-v-kvante
rubric_sub: Школа в «Кванте»
page_first: 33
page_last: 33
page_labels: "31"
tag: Q8RI
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 13bc13939e5efa7e7d46ab2685aeaaa3e448ff7a7ecf3b34098ceeec0800151a
prompt_sha256: draft-1
translated_from: content/ru/1983/10/articles/10_pecherskiy-nx-xn-0b008072.md
source_content_sha256: f1b91d6d0c974a690a22190dc1258b92be3ef24414064fbddb73868bf27eb1f1
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 31⟧

$$n^x = X^n$$

L. B. PECHERSKY

Phương trình này có bao nhiêu nghiệm nếu $n \in \mathbb{N}$ và $n \neq 1$?

Với các nghiệm mở, mọi thứ đều đơn giản và rõ ràng: nếu $n$ chẵn, phương trình có một nghiệm âm (vẽ đồ thị!); nếu $n$ lẻ thì không có nghiệm nào như vậy.

Sẽ mất rễ tích cực. Phương trình này hoàn toàn tương đương với các phương trình

$$\ln (n^x) = \ln (x^n),$$
$$x \cdot \ln n = n \cdot \ln x,$$
$$x \cdot \ln n - n \cdot \ln x = 0.$$

Hàm $y(x) = x \cdot \ln n - n \cdot \ln x$ có bao nhiêu số 0*) trên $]0; +\infty[$?

Tích của $y'(x) = \ln n - \frac{n}{x}$ nhân với $]0; +\infty[$ trả về (vẽ đồ thị!). Tại điểm $x_0 = \frac{n}{\ln n} y'(x_0) = 0$; điều đó có nghĩa là vào $]0; x_0[$ $y'(x) < 0$, vào $]x_0; +\infty[$ $y'(x) > 0$. Vì hàm $y$ không phải là số nguyên tố tại điểm $x_0$ nên $x_0$ là điểm tối thiểu của nó. Tại $]0; x_0[$ hàm $y$ giảm, tại $[x_0; +\infty[$ nó trả về.

Hàm số $y$ có dấu gì tại điểm $x_0$?

$$y(x_0) = n(1 - \ln n + \ln \ln n).$$

Để xác định dấu của số $y(x_0)$, chúng ta kiểm tra hàm $z(x) = 1 - \ln x + \ln \ln x$. Vì $z'(x) = \frac{1 - \ln x}{x \cdot \ln x}$, $x_1 = e$ là điểm cực đại của hàm $z$ và tại $]1; e]$ $z$ trả về, tại $[e; +\infty[$ nó giảm. Vì $z(x_1) = 0$, tại các điểm khác của miền định nghĩa $z(x) < 0$; một phần, tại $n \in \mathbb{N}$, $n \neq 1$ $z(n) < 0$. Vì vậy, $y(x_0) < 0$.

Hàm $y$ không phải là số nguyên tố trên $]0; +\infty[$ và nó đang giảm dần. Vì “gần 0” (ví dụ: rõ ràng là tại $x < 1$) $y(x) > 0$ và $y(x_0) < 0$, trên khoảng $]0; x_0[$ nên hàm $y$ có chính xác một số 0 (xem hình).

Hãy để chúng tôi chứng minh điều đó đối với “lớn” $x$ (“trên mặt phẳng vô cực”) $y(x) > 0$. Để làm điều này, hãy xem xét hàm $u(x) = \frac{x}{\ln x}$. Vì $u'(x) = \frac{\ln x - 1}{\ln^2 x}$, $u$ trở về $[e; +\infty[$. Nếu $n \geq 3$ thì tại $x > n \geq 3$

$$\frac{x}{\ln x} > \frac{n}{\ln n},$$
$$x \cdot \ln n > n \cdot \ln x,$$
$$x \cdot \ln n - n \cdot \ln x > 0,$$
$$y(x) > 0.$$

Hãy tự chứng minh rằng với $n = 2$ $y(x) > 0$ cho “lớn” $x$.

Vì $y(x_0) < 0$, $y$ trả về $[x_0; +\infty[$ và $y(x) > 0$, đối với “lớn” $x$, trên khoảng $]x_0; +\infty[$ hàm $y$ cũng có chính xác một số 0 (xem hình).

Vì vậy, đối với $n \geq 2$, phương trình trong tiêu đề có hai nghiệm trên $]0; +\infty[$: một trên $]0; x_0[$, một trên $]x_0; +\infty[$.

Nhân tiện, một trong những gốc của nó: $x = n$ - rất rõ ràng ngay lập tức.

Bài toán về số nghiệm của một phương trình nhất định $f(x) = g(x)$ được tìm thấy trong các kỳ thi tuyển sinh. Theo quy luật, các phương trình được đưa ra không thể tiếp cận được bằng các phương tiện đại số. Trong những trường hợp như vậy, việc kiểm tra hàm $f$, $g$ có trong phương trình thường rất hữu ích và ở đây việc sử dụng các công cụ phân tích là điều khá tự nhiên.
