---
id: 1986-8-kolmogorov-parketyi-iz-pravilnyih-mnogougolnikov-3279ea3c
issue: kvant_1986_8
year: 1986
number: "8"
title: Sàn gỗ làm bằng đa giác thông thường
authors:
  - Колмогоров А. Н.
rubric: osnovnye-stati
page_first: 6
page_last: 6
page_labels: "4"
tag: C7GE
lang: vi
source: kvant_digital
extraction: vision
content_sha256: e2ece7d5c75a2fb6d2d6672cc214e2b13903ef3c66ab454ddea23d2fe66725d2
prompt_sha256: draft-1
translated_from: content/ru/1986/08/articles/04_kolmogorov-parketyi-iz-pravilnyih-mnogougolnikov-3279ea3c.md
source_content_sha256: c8a86711ff2468afb19ad8e45fa716b64e351e3443c38b5293983b5e4fcdb49d
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 4⟧

Hình 2.

tự mình xây dựng càng nhiều sàn gỗ chính xác càng tốt.

Chính bài toán

Nó chỉ ra rằng tất cả các loại sàn gỗ chính xác có thể được mô tả. Nếu chiều dài cạnh $h$ của đa giác sàn gỗ được cho trước thì chỉ có một số hữu hạn các sàn gỗ thông thường khác nhau (không chồng chéo). Tôi không muốn nói cho bạn biết chính xác là bao nhiêu.

Liệt kê tất cả chúng và từ đó trả lời câu hỏi về số lượng của chúng là bài toán chính mà bạn phải giải.

Một số gợi ý

Lời giải bài toán việc bắt đầu bằng việc kiểm tra cấu trúc của mặt bàn gỗ là điều đương nhiên. Một $n$-gon thông thường có $n$ góc ngoài (hình 4), tổng của chúng bằng bốn góc vuông REM (bạn hãy xem phần này). Do đó, mỗi góc của $n$-giác đều bằng

$$a_n = 2d - \frac{4d}{n} = 2\left(1 - \frac{2}{n}\right)d.$$

Mặt trên của sàn gỗ phải chứa các đa giác có tổng các góc bằng 4d. Vì thế,

$$a_3 = \frac{2}{3}d, \ a_4 = d, \ a_6 = \frac{4}{3}d, \ a_8 = \frac{3}{2}d,$$

và đối với các loại sàn gỗ được hiển thị trong Hình 1 và 2, chúng ta có:

$$4a_4 = 4d,$$
$$6a_3 = 4d,$$
$$3a_6 = 4d,$$
$$a_4 + 2a_8 = 4d,$$
$$a_3 + 2a_4 + a_6 = 4d.$$

Trong trường hợp tổng quát, biểu thị bằng $m_n$ số các $n$-giác liền kề, ta thu được

$$\sum m_i a_i = 4d,$$

(1)

trong đó trong tổng, chúng tôi bao gồm các số hạng có các số $i$ mà $m_i > 0$ và $a_i = 2(1 - 2/i)d$.

(Cuối cùng xem trang 7)
