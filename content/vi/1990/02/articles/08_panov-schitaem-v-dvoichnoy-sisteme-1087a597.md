---
id: 1990-2-panov-schitaem-v-dvoichnoy-sisteme-1087a597
issue: kvant_1990_2
year: 1990
number: "2"
title: Chúng tôi đếm trong hệ thống nhị phân
authors:
  - Панов А.
rubric: nam-pishut
rubric_sub: Нам пишут
page_first: 32
page_last: 32
page_labels: "30"
lang: vi
source: kvant_digital
extraction: vision
content_sha256: e2183b935e6974d3f9c31e6cccd1dc1b5fd1367cdd764741f19c347057867e01
prompt_sha256: draft-1
translated_from: content/ru/1990/02/articles/08_panov-schitaem-v-dvoichnoy-sisteme-1087a597.md
source_content_sha256: 1c522c1e5d40dd01144d17f11ef69b670040de157a02f360674c9532bb4a74c0
translation_model: draft
translation_run: vi-draft-gaps-2026-11-01
translation_quality: draft
---

⟦folio 30⟧

Chúng tôi tính vào hệ thống kép
Giả sử có một số đồ vật ở trước mặt chúng ta và chúng ta cần đếm chúng. Như thường lệ, chúng ta thực hiện việc này bằng cách tính toán lại tuần tự: chúng ta lấy mục đầu tiên và nói “một”, lấy mục tiếp theo – “hai”, mục tiếp theo – “tri”, v.v. cho đến mục cuối cùng. Vì đang đếm trong hệ thập phân nên chúng ta cũng sẽ thu được số đối tượng $N$ trong hệ thập phân

$$N = a_k a_{k-1} \dots a_1 a_0.$$
Ở đây mỗi chữ số $a_i$ là 0, 1, 2, 3, 4, 5, 6, 7, 8 hoặc 9 và $N = a_k \cdot 10^k + a_{k-1} \cdot 10^{k-1} + \dots + a_1 \cdot 10 + a_0$.

Bây giờ hãy tưởng tượng rằng khi kết hợp, chúng ta chỉ sử dụng một hệ thống kép (ở thời đại chúng ta, thời đại tin học hóa phổ cập, điều này có lẽ không quá khó tưởng tượng).

Trong hệ thống này, số $N$ được biểu diễn dưới dạng

$$N = b_l b_{l-1} \dots b_1 b_0,$$

trong đó mỗi chữ số $b_i$ là 0 hoặc 1 và

$$N = b_l \cdot 2^l + b_{l-1} \cdot 2^{l-1} + \dots + b_1 \cdot 2 + b_0.$$

Để đếm số lượng đối tượng trong hệ thống kép, chúng ta có thể sử dụng cách tính toán tuần tự tương tự: tuần tự duyệt qua từng đối tượng một và lần lượt đặt tên cho các số trong hệ thống kép.

Tuy nhiên, trong hệ thống kép có một phương pháp đếm khác về cơ bản mà tôi muốn giới thiệu với bạn. Hãy chuyển sang hình: cấu trúc tất cả các mục theo tham số. Trong trường hợp này, sẽ không còn gì hoặc sẽ còn lại một đối tượng chưa ghép nối. Hãy cộng nó như thế này: sẽ còn lại 0 mục hoặc 1 mục. Ở giai đoạn thứ hai, chúng tôi kết hợp hai cặp thành bốn phần. Trong trường hợp này, vẫn còn lại 0 cặp hoặc 1 cặp. Tiếp theo, chúng ta sẽ kết hợp số bốn theo cặp, rồi số tám, v.v. Sau lần thống nhất cuối cùng, chúng ta có được sự phân chia tất cả các đối tượng thành các nhóm và số phần tử trong mỗi nhóm là lũy thừa của hai. Nếu phân vùng chứa các nhóm có phần tử $2^i$ thì chúng ta đặt $b_i = 1$, nếu không có nhóm như vậy - $b_i = 0$. Và sau đó

$$N = b_l b_{l-1} \dots b_1 b_0$$

- hồ sơ về số lượng đối tượng trong hệ thống kép.

Phương pháp nào trong hai phương pháp này là thích hợp hơn? Tôi đề nghị bạn tự giải quyết vấn đề này.

A. Panov
