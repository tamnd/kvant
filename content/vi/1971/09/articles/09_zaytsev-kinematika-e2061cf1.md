---
id: 1971-9-zaytsev-kinematika-e2061cf1
issue: kvant_1971_9
year: 1971
number: "9"
title: Động học
authors:
  - Зайцев И. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 49
page_last: 51
page_labels: 47, 49
tag: RNGQ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: eb6da33f30dd9961b88288470d27df176c11668dd0b5c55da1430c2ac4f2d97a
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1971/09/articles/09_zaytsev-kinematika-e2061cf1.md
source_content_sha256: 3b910c4278b37d6fd6347890b8ddacdbc4e67ddfae0f40d3c48a94c2cd35a986
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦folio 47⟧

Bạn giải các bài toán động học như thế nào? Bạn nhớ bao nhiêu công thức? 5? 10? 15? Rất thường, lời giải bài toán bắt đầu bằng việc viết ra một số lượng lớn công thức — công thức về quãng đường vật đi được trong giây thứ $n$, công thức về tỉ số các quãng đường vật đi được trong những khoảng thời gian liên tiếp, công thức về hiệu các bình phương vận tốc của vật, vân vân. Sau đó người ta cố thế các công thức này vào nhau, chia, nhân... Đôi khi bằng cách ấy có thể tìm được đáp số. Nhưng thường hơn, các bài toán động học là một chướng ngại không thể vượt qua. Có lẽ đây là một trong những phần khó nhất đối với thí sinh. Trong khi lẽ ra nó phải là một trong những phần đơn giản nhất. Hãy tìm hiểu nó.

Trước hết, ta sẽ nói về chuyển động thẳng của vật. Nếu lấy đường thẳng mà vật chuyển động dọc theo làm trục tọa độ $OX$ (điểm $O$ là gốc tọa độ), thì vị trí của vật được xác định bởi tọa độ $x$ của nó. Khi chuyển động với gia tốc không đổi, tọa độ của vật thay đổi theo thời gian theo quy luật

$$x = x_0 + v_0 t + \frac{at^2}{2},$$

(*)

trong đó $x_0$ là tọa độ ban đầu của vật (khi $t=0$), $v_0$ là vận tốc ban đầu của nó và $a$ là gia tốc. Phương trình (*) chính là phương trình động học của chuyển động của vật. Tất nhiên, phương trình (*) là hình chiếu lên trục $x$ của phương trình vectơ đối với bán kính-vectơ $r$, xác định vị trí của khối tâm của vật (hình 1). Vì vậy, hình chiếu lên trục $OX$ của những đại lượng vectơ nào cùng hướng với trục $OX$ thì dương, còn của những đại lượng nào hướng ngược lại thì âm. Cần tính đến điều này khi thế các đại lượng ấy vào phương trình (*).

Nhấn mạnh một lần nữa: phương trình (*) là phương trình cho tọa độ của vật, chứ không phải cho quãng đường vật đi được. Quãng đường là một đại lượng vô hướng dương, không thể giảm. Đồng thời, tọa độ của vật có thể biến đổi thế nào cũng được. Ví dụ, nếu $v_0$ dương và $a=-a_0$ âm (vectơ vận tốc $v_0$ hướng về cùng phía)

⟦folio 49⟧

nghĩa là tại thời điểm chạm đất, vận tốc của hòn đá bằng vận tốc ban đầu, nhưng hướng theo phía ngược lại.

Phương trình (**) cho phép dễ dàng tìm thời gian $t_\pi$ hòn đá bay lên. Vì tại điểm lên cao nhất vận tốc của hòn đá bằng không, nên

$$0 = v_0 - gt_n.$$

Suy ra $t_\pi = \frac{v_0}{g}$. Thời gian hòn đá bay lên bằng một nửa thời gian bay.

Ta thấy rằng hai phương trình — cho tọa độ và cho vận tốc — cho phép nhận được câu trả lời cho bất kỳ câu hỏi nào về chuyển động của hòn đá. Chính chúng cần luôn nhớ.

Giải thêm một bài toán.

Bài toán 2. Một vật rơi tự do trong giây cuối cùng đã đi được $1/3$ quãng đường của mình. Vật đã rơi bao nhiêu giây ($n$) và từ độ cao nào ($h$)?

Lấy điểm ném làm gốc tọa độ, và hướng trục tọa độ thẳng đứng xuống dưới. Khi đó tọa độ của vật phụ thuộc vào thời gian theo quy luật

$$x = \frac{gt^2}{2}$$

($v_0 = 0, x_0 = 0, a = g$). Nếu vật rơi trong $n$ giây, thời gian rơi bằng $n \cdot \tau$ ($\tau = 1$ giây), và

$$h = \frac{gn^2\tau^2}{2}.$$

(1)

Sau thời gian $(n-1)\tau$ kể từ khi bắt đầu chuyển động, tọa độ của vật bằng $\frac{2}{3}h$. Do đó

$$\frac{2}{3}h = \frac{g(n-1)^2\tau^2}{2}.$$

(2)

Giải đồng thời các phương trình (1) và (2), ta được

$$n = \frac{\sqrt{3}}{\sqrt{3} - \sqrt{2}} \approx 5,45, \quad h \approx 145 \text{ m}.$$

Cũng có thể chọn một hệ tọa độ khác, chẳng hạn gắn với mặt đất và có trục tọa độ hướng lên trên. Khi đó phương trình chuyển động của vật sẽ là:

$$x = h - \frac{gt^2}{2} \left( x_0 = h, v_0 = 0, a = -g \right).$$

Ở đây khi $t=n\tau$ thì $x=0$, còn khi $t=(n-1)\tau$ thì $x=\frac{1}{3}h$.

Cũng có thể chọn thêm một hệ tọa độ nữa — có gốc tại điểm ném và trục hướng lên trên. Trong hệ này

$$x = -\frac{gt^2}{2};$$

khi $t=n\tau$ thì $x=-h$, khi $t=(n-1)\tau$ thì $x=-\frac{2}{3}h$.

Trong bài toán này, việc chọn hệ tọa độ không thật sự quan trọng, nhưng thường thì bằng cách chọn thích hợp hệ tọa độ, có thể đơn giản hóa đáng kể lời giải.

Chẳng hạn, hãy giải bài toán sau.

Bài toán 3. Hai giọt mưa rời khỏi mái nhà cách nhau một khoảng thời gian $\tau$ là bao nhiêu, nếu sau thời gian $t_0$ kể từ khi giọt thứ hai bắt đầu rơi, khoảng cách giữa các giọt bằng $l$?

Tất nhiên, có thể giải bài toán này trong hệ tọa độ gắn với mái nhà (hãy tự làm điều đó).

Nhưng thuận tiện hơn là chuyển sang hệ tọa độ gắn với giọt thứ hai. Vì các giọt rơi với cùng gia tốc đối với mặt đất, nên gia tốc tương đối của chúng bằng không: các giọt chuyển động đều tương đối với nhau. Vận tốc tương đối của chúng bằng vận tốc của giọt thứ nhất đối với mặt đất tại thời điểm giọt thứ hai rời đi $v_0=g\tau$. Phương trình chuyển động của giọt thứ nhất trong hệ tọa độ gắn với giọt thứ hai có dạng:

$$x = v_0 t + x_0,$$

trong đó $x_0 = \frac{gt^2}{2}$. Khi $t=t_0$ thì $x=l$, tức là

$$l = g\tau t_0 + \frac{gt^2}{2}.$$

Giải phương trình này, ta được đáp số:

$$\tau = \sqrt{t_0^2 + \frac{l}{g}} - t_0.$$

Hãy giải thêm bài toán sau.
