---
id: 1971-5-bashmakov-o-postulate-bertrana-85b0ebf2
issue: kvant_1971_5
year: 1971
number: "5"
title: Về định đề Bertrand
authors:
  - Башмаков М. И.
rubric: osnovnye-stati
page_first: 6
page_last: 6
page_labels: "4"
tag: XJWU
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 576bc63a811c84716e8286525d48abb3ecd1b239bbbeeb7b33904227003d3836
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1971/05/articles/02_bashmakov-o-postulate-bertrana-85b0ebf2.md
source_content_sha256: 68a02acb2c654cbb5c9ea9c1e34b11e9f645d18e52f783af48e6f490f8dcdf96
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦folio 4⟧

VỀ TIÊN ĐỀ BERTRAND

M. I. Bashmakov

Trong số 69 công trình của Pafnuty Lvovich Chebyshev, có hai công trình đã đóng vai trò đặc biệt quan trọng trong sự phát triển của lý thuyết số. Đó là các công trình: “Về việc xác định số lượng các số nguyên tố không vượt quá một đại lượng cho trước” và “Về các số nguyên tố”, được ông viết khi còn trẻ, dành cho vấn đề khó nhất của lý thuyết số là sự phân bố của các số nguyên tố.

Trong công trình thứ hai vừa nêu, đã chỉ ra các bất đẳng thức cho phép đánh giá khá chính xác số lượng các số nguyên tố trong một đoạn đã cho của dãy số tự nhiên và, đặc biệt, đã chứng minh sự kiện sau: giữa $x$ và $2x$ (trong đó $x>1$) luôn có ít nhất một số nguyên tố. Khẳng định này đã được nhà toán học Pháp nổi tiếng Bertrand nêu ra; ông đã kiểm tra nó trong phạm vi các bảng số nguyên tố hiện có, nhưng không thể chứng minh và đã chấp nhận nó như một tiên đề.

Chúng ta sẽ theo dõi những ý tưởng chính của Chebyshev đã dẫn ông đến các đánh giá này, rồi đưa ra một loạt bài toán mà lời giải của chúng cho phép các độc giả (đã khá quen thuộc với các tính chất của logarit) phục dựng chứng minh đã nêu về tiên đề Bertrand và thu được các bất đẳng thức về số lượng các số nguyên tố không vượt quá một đại lượng cho trước.

Độc giả có thể ngạc nhiên: logarit có quan hệ gì với các số nguyên tố? Chính ở chỗ này là công lao của Chebyshev: ông đã chỉ ra cách có thể sử dụng các hàm thông thường của giải tích — căn, logarit — khi nghiên cứu các bài toán về số nguyên. Nếu ta muốn phát hiện xem có ít nhất một số nguyên tố trên đoạn từ $n$ đến $2n$ hay không, thì có thể làm như sau:

1) nghĩ ra một hàm nào đó $y=f(x)$ của biến thực $x$, sao cho nó không thay đổi giá trị khi $x$ chạy trên đoạn giữa các số nguyên tố kề nhau, và nhận giá trị lớn hơn khi đi qua một số nguyên tố;

2) chứng minh các bất đẳng thức đối với hàm $f$, giúp đánh giá khá chính xác tốc độ tăng của nó.

Đối với hàm được chọn như vậy, hiệu $f(2n) - f(n)$ sẽ là một số dương khi và chỉ khi hàm $f$ tăng khi chuyển từ $n$ đến $2n$, tức là khi giữa $n$ và $2n$ có ít nhất một số nguyên tố.

Điều kiện thứ nhất dễ thỏa mãn. Có thể xét một hàm như sau: ký hiệu $\pi(x)$ là số các số nguyên tố không vượt quá $x$.

Chẳng hạn, $\pi(1) = 0$ (một không được coi là số nguyên tố), $\pi(3) = 2$, $\pi(9) = 4$, $\pi(9,5) = 4$, $\pi(10,9) = 4$, $\pi(11) = 5$ v.v.

Tất nhiên, nếu chúng ta có thể chứng minh rằng

$$\pi(2x) - \pi(x) > 0,$$

thì chúng ta đã chứng minh được mệnh đề Bertrand, vì

$$\pi(2x) - \pi(x)$$

chính là số các số nguyên tố nằm giữa $x$ và $2x$.
