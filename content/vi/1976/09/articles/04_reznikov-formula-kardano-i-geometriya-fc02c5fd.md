---
id: 1976-9-reznikov-formula-kardano-i-geometriya-fc02c5fd
issue: kvant_1976_9
year: 1976
number: "9"
title: Công thức và hình học Cardano
authors:
  - Резников А. Г.
rubric: osnovnye-stati
page_first: 19
page_last: 19
page_labels: "17"
tag: HDYH
lang: vi
source: kvant_digital
extraction: publisher
content_sha256: d35672f4619e137c381ae2bfaf2009656b06898e81ea2253b5ba020a72c899f8
prompt_sha256: draft-1
translated_from: content/ru/1976/09/articles/04_reznikov-formula-kardano-i-geometriya-fc02c5fd.md
source_content_sha256: 9771af932d31ee2d0f12420d734bdb05ba936e40327e75025e65b0e1ed191ef5
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦figure⟧

## Công thức và hình học Cardano

Bạn đã quen với cách sử dụng các hệ số của phương trình bậc hai $x^2+px+q=0$ để xác định xem nó có bao nhiêu nghiệm thực. Nếu $p^2-4q\gt0$ thì có hai nghiệm, nếu $p^2-4q=0$ thì có một nghiệm, và cuối cùng, nếu $p^2-4q\lt0$ thì không có nghiệm nào.

Trong vấn đề này, điều kiện tương tự được rút ra cho phương trình bậc ba $x^3+px+q=0$. Sử dụng điều kiện này, bạn có thể nhận được một bất đẳng thức thông minh nối các phần tử của một tam giác tùy ý. Đây là cách nó được thực hiện.

Cho $ABC$ là một tam giác có các cạnh $a$, $b$, $c$; $p$ là bán chu vi, $S$ là diện tích của nó và $R$, $r$, $r_a$, $r_b$, $r_c$ là bán kính của các đường tròn ngoại tiếp, nội tiếp và ngoại tiếp. Hóa ra các mối quan hệ sau đây là đúng:
$$
r_a+r_b+r_c=4R+r,\quad r_ar_b+r_br_c+r_cr_a=p^2,\quad r_ar_br_c=pS.\tag1
$$

Đẳng thức (1) có nghĩa là các số $r_a$, $r_b$, $r_c$ là nghiệm của phương trình bậc ba sau:
$$
x^3-(4R+r)x^2+p^2x-pS=0.\tag2
$$
Điều này xuất phát từ thực tế là $r_a$, $r_b$, $r_c$ là nghiệm của đa thức
$$
(x-r_a)(x-r_b)(x-r_c)=x^3-(r_a+r_b+r_c)x^2+(r_ar_b+r_br_c+r_cr_a)a-r_ar_br_c.
$$

Sau khi viết phương trình (2) điều kiện cho tính đúng của cả ba nghiệm của nó, sau khi biến đổi đơn giản và sử dụng công thức $S=pr$, chúng ta đi đến bất đẳng thức sau:
$$
[p^2-(2R^2+10Rr-r^2)]^2\le4R(R-2r)^3.\tag3
$$
Từ (3) suy ra $$
R\ge2r\tag4
$$
và cái gì $$
|p^2-(2R^2+10Rr-r^2)|\le2\sqrt{R(R-2r)^3}.\tag5
$$
Sự bình đẳng ở (3) và (5) đạt được khi hai trong số các số $r_a$, $r_b$, $r_c$ bằng nhau, tức là khi tam giác cân.

### Bài tập

1. Chứng minh công thức (1). Để thực hiện việc này, hãy in các biểu thức sau cho $S$:
$$
S=rp=r_a(p-a)=r_b(p-b)=r_c(p-c)=\dfrac{abc}{4R}=\sqrt{p(p-a)(p-b)(p-c)}.
$$
2. Tìm điều kiện để đạt được đẳng thức trong (4).
3. Chứng minh rằng $16Rr-5r^2\le p^2\le4R^2+4Rr+3r^2$.
4. Xét xem tam giác cân nào có số $p^2-(2R^2+10Rr-r^2)$ không âm.
