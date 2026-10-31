---
id: 1982-6-krotov-ob-optimalnyih-traektoriyah-dvizheniya-3702fb91
issue: kvant_1982_6
year: 1982
number: "6"
title: Về quỹ đạo chuyển động tối ưu
authors:
  - Кротов С. С.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 32
page_last: 35
page_labels: 30, 31, 33
tag: 4GXT
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 63fd8db0b94cac9b1136c2f415e425b4ffe04b226a60b4589d9670a433834af3
prompt_sha256: draft-1
translated_from: content/ru/1982/06/articles/07_krotov-ob-optimalnyih-traektoriyah-dvizheniya-3702fb91.md
source_content_sha256: d3e9762232b5b8ef2613e129c54b438b5031802c3507ece9caa7f611f9c2c1f3
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 30⟧

S. Krotov

Về chuyển động quỹ đạo tối ưu

Nhiều bạn đã phải giải bài toán để xác định quỹ đạo chuyển động tối ưu - bài toán gõ “để xác định quỹ đạo mà - dựa trên việc xác định điều kiện giao thông - người ta có thể đi từ điểm A đến điểm B trong thời gian tối thiểu.” Ở thời điểm hiện tại, chúng ta đang thảo luận về một phương pháp cho phép thực hiện một nhiệm vụ nhất định thuộc loại này chỉ bằng một.

Hãy bắt đầu với bài toán đơn giản. Hãy tưởng tượng một cậu bé thấy mình ở một thời điểm nào đó $t_0$ của trường trung bình tại điểm A. Chúng ta biết rằng từ điểm A này, cậu bé có thể di chuyển với tốc độ $v$ theo bất kỳ hướng nào (chúng tôi muốn nói rằng các điều kiện để cậu bé chuyển động từ điểm A là như nhau theo mọi hướng). Hãy đặt câu hỏi sau: cậu bé có thể đi về đâu sau một khoảng thời gian ngắn $\Delta t$?

Chúng ta sẽ giả định rằng ở phía đối diện của khoảng thời gian này, cậu bé bắt đầu

⟦folio 31⟧

không thay đổi hướng đi và tốc độ của nó không đổi. Trong trường hợp này, đáp số rất quan trọng: cậu bé có thể đến bất kỳ điểm nào trên đường tròn với tâm ở vị trí ban đầu - tại điểm $A$ - và bán kính $v \cdot \Delta t$.

Bây giờ chúng ta hãy giả sử rằng một cậu bé đang trong quá trình chuyển động có thể bất cứ lúc nào, tại bất kỳ điểm nào trên quỹ đạo của cậu ấy, ngay lập tức thay đổi hướng của tốc độ một cách tùy ý, giữ cho nó không đổi về độ lớn (trong trường hợp này chúng ta sẽ phải ban cho cậu bé sức mạnh siêu nhiên). Và trong trường hợp này, đáp số để đặt câu hỏi bài toán khá đơn giản: vì độ dài của tất cả các quỹ đạo có thể có của cậu bé bằng $v \cdot \Delta t$, điểm cuối của một quỹ đạo tùy ý có thể kết thúc tại bất kỳ điểm nào của đường tròn bán kính $v \cdot \Delta t$ với tâm là điểm $A$. Điều này xuất phát từ thực tế là chuyển động của cậu bé, tức là khoảng cách giữa điểm bắt đầu và điểm cuối của một quỹ đạo tùy ý trên một đường thẳng, dọc theo giá trị abscid, không lớn hơn chiều dài của quỹ đạo, bằng $v \cdot \Delta t$. Do đó, vùng có thể tiếp cận (hãy gọi nó là tập hợp các điểm trong trường mà cậu bé có thể ở đó theo thời gian $t_0 + \Delta t$) sẽ là một đường tròn có bán kính $v \cdot \Delta t$.

Chúng ta hãy lưu ý rằng đối với bất kỳ điểm bên trong nào của vùng khả năng tiếp cận (ví dụ: điểm $B$ trong Hình 1), có thể chỉ ra vô số quỹ đạo mà cậu bé có thể đi tới đó. Đối với bất kỳ điểm nào trên ranh giới của vùng khả năng tiếp cận (ví dụ: điểm $C$ trong Hình 1), có một quỹ đạo duy nhất là “đâm trúng” (đến điểm $C$ - dọc theo bán kính $AC$).

Nếu trong tương lai (tại $t > t_0 + \Delta t$) các điều kiện để cậu bé chuyển động trên sân vẫn giữ nguyên, thì ở những lần tiếp theo, ranh giới của vùng có thể tiếp cận cũng sẽ là hình tròn (với tâm là điểm $A$). Ranh giới của khu vực có thể tiếp cận ở phía trước của tất cả các chuyển động có thể có hoặc đơn giản là ở phía trước. Trong cuộc thảo luận trước, mặt trước là một hình tròn, bán kính của nó tăng với tốc độ $v$. Hình dạng đơn giản này của mặt trước là do các điều kiện để cậu bé chuyển động từ điểm $A$ (và từ bất kỳ điểm nào trong vùng 过剩ness) theo mọi hướng đều giống nhau. Dễ dàng nhận thấy rằng trong trường hợp chuyển động tổng quát hơn, mặt trước có các tính chất sau:

1) sớm hay muộn mặt trận sẽ đi qua bất kỳ điểm nào (có nghĩa là những điểm mà nhìn chung có thể đi tới);

2) không có phương pháp chuyển tiếp thì có thể lùi xa hơn về phía trước tùy theo thời điểm;

3) đối với mỗi điểm của mặt trước, theo quy luật, bạn có thể chỉ ra một quỹ đạo duy nhất kết thúc ở đó;

4) khi xác định mặt trước tại các thời điểm tiếp theo (nghĩa là khi xác định sự thay đổi của mặt trước theo thời gian), tất cả các điểm của mặt trước ban đầu sẽ đồng thời đóng vai trò là điểm $A$, sao cho tại bất kỳ thời điểm nào mặt trước sẽ là một đường bao gồm một tập hợp các vòng tròn, tâm của chúng nằm trên mặt trước ban đầu và bán kính được xác định bởi các điều kiện “chạy xa” khỏi các điểm tương ứng của mặt trước (Hình 2);

5) Chúng ta hãy lấy hai vị trí của mặt trước - $M$ và $M'$, cách nhau một khoảng thời gian $\Delta t$ (xem Hình 2). Đối với bất kỳ điểm $E$ nào của mặt trước $M$, có một điểm duy nhất $E'$ của mặt trước $M'$ mà tại đó người ta có thể thêm vào lúc $\Delta t$; chỉ có một quỹ đạo chuyển động. Tất cả các điểm khác của mặt trước $M'$ chỉ có thể được thêm từ điểm $E$ trong thời gian dài.

Phương pháp xem xét chuyển động bằng cách xây dựng mặt trước chuyển động theo thời gian ở trên có thể được áp dụng thành công khi lời giải bài toán xác định quỹ đạo chuyển động tối ưu. Nếu như

1) chúng ta biết mặt trước thay đổi như thế nào theo thời gian, nghĩa là chúng ta có thể xây dựng nó vào từng thời điểm,

2) để giảm bớt một trong toàn bộ quỹ đạo chuyển động dẫn đến một điểm tùy ý của mặt trước, sau đó bài toán việc xác định đường chuyển động tối ưu được giải quyết như sau: chúng tôi thiết lập loại mặt trước theo thời gian, xác định thời điểm mà mặt trước đạt đến điểm trong phạm vi của chúng tôi và xây dựng một quỹ đạo nhận ra việc chạm chính xác điểm này của mặt trước.

Để sử dụng ở trên, hãy xem xét một phụ trợ bài toán.

Vấn đề. Cậu bé sống trên bờ Vịnh OR MOR (Hình 3). Bờ vịnh tạo thành một trung tâm. Nhà cậu bé ở điểm $A$. Khoảng cách từ nhà đến bờ là $h$, và khoảng cách từ nhà đến điểm $O$ (xem Hình 3) là $l$. Cậu bé yêu cá từ bờ biển OM. Hỏi người đó nên chọn chỗ cho cá cách điểm $O$ bao nhiêu để từ nhà đến nơi này trong thời gian ngắn nhất? Tại sao

⟦folio 33⟧

Cơm. 6.

lịch sử từ đó đến điểm $A$ bằng $|AE| = v \cdot \Delta t_1$ ($|AE| = |AE'|$). Có thể dễ dàng xác minh rằng theo thời gian $\Delta t$ mặt trước sẽ là một đường cong $M'K'KM$, trong đó $M'K'$ và $KM$ là tiếp tuyến của hình bán nguyệt bán kính $u \cdot \Delta t$. tập trung tại $A$. Các tiếp tuyến này tạo một góc $\alpha$ với bờ sao cho $\sin \alpha = u/v$. (Trong tương lai, mặt trước sẽ là một đường cong $M'K'KM$ và một hình tròn có bán kính $AM$ ($AM'$) với tâm tại điểm $A$, nằm trên bờ. Nhưng chúng tôi chỉ quan tâm đến phần mặt trước nằm trong vùng “sông”. Tại bất kỳ thời điểm nào khác, mặt trước sẽ giống với mặt trước $M'K'KM$ mà chúng tôi đã xây dựng.

Bây giờ đã rõ làm thế nào để tìm ra quỹ đạo tác động tối ưu (tức là quỹ đạo tác động trong thời gian ngắn nhất) từ điểm $A$ đến điểm $B$ của dòng sông, nằm cách bờ một khoảng $h$. Quỹ đạo này sẽ là một đường đứt nét ACB (xem Hình 5), đoạn CB vuông góc với mặt trước đi qua điểm $B$. Điểm $C$ là điểm của bờ mà từ đó điểm nhỏ sẽ bắt đầu tan chảy. Nếu khoảng cách dọc bờ biển từ điểm $A$ đến điểm $B$ là $|AD| = l$ thì $|AC| = |AD| - |CD| = l - h$ tg $\alpha = l - h \frac{u}{\sqrt{v^2 - u^2}}$.

Bây giờ chúng ta hãy tính đến điều đó, theo điều kiện bài toán, tốc độ dòng chảy của sông là $w \neq 0$. Mặt trước sẽ trông như thế nào sau thời gian $\Delta t$ kể từ khi bắt đầu chuyển động? Rõ ràng, điểm $M$ của mặt trước (xem Hình 5) sẽ giữ nguyên; tâm hình bán nguyệt bán kính $u \cdot \Delta t$ sẽ dịch chuyển từ điểm $A$ sang trái (theo hướng $w$) đến một khoảng cách $|AO| = w \cdot \Delta t$. Mặt tiền ở vùng “sông” sẽ là đường cong $M'N'NM$ (Hình 6 thể hiện phần NM của mặt tiền); tiếp tuyến $MN$ tạo một góc $\alpha_1$ với bờ sao cho

$$\sin \alpha_1 = u/(w + v).$$

Về cơ bản, chúng tôi chia việc xây dựng các điểm của phần $MN$ của mặt trước thành hai giai đoạn: đối với mỗi điểm $M_i$ của bờ, trong đó điểm nhỏ kết thúc sau thời gian $\Delta t_i$, chúng tôi xây dựng một “mặt trận phụ” - ranh giới của khu vực sông mà điểm nhỏ có thể kết thúc sau thời gian $\Delta t - \Delta t_i$. Ranh giới này là hình bán nguyệt có bán kính $u \cdot (\Delta t - \Delta t_i)$ có tâm tại điểm $M_i$. Sau đó, chúng ta di chuyển các hình bán nguyệt này sang trái (theo hướng $w$) một khoảng bằng $w \cdot (\Delta t - \Delta t_i)$. tiếp tuyến của tất cả các hình bán nguyệt dịch chuyển như vậy là phần $MN$ của mặt trước.

Do đó, để đi từ điểm $A$ đến điểm $B$ trong thời gian ít nhất, vật nhỏ phải tan chảy từ điểm $C_1$ của bờ, nằm ở bên phải điểm $C$ (xem Hình 6) ở khoảng cách $|CC_1| = w\tau$, trong đó $\tau$ là thời gian mà vật nhỏ sẽ tan chảy. (Rõ ràng đoạn $C_1B$ của quỹ đạo tối ưu phải song song với đoạn $AN$.) Khoảng cách giữa các điểm $A$ và $C_1$ là

$$x = |AC_1| = |AD| + |DC_1| = l + |DC_1|.$$

Hãy tìm độ dài của đoạn $DC_1$:

$$|DC_1| = |CC_1| - |CD| = w\tau - h \ tg \alpha_1;$$

của $\Delta BDC$ nằm

$$\frac{h}{u\tau} = \cos \alpha_1 \Rightarrow \tau = \frac{h}{u \cos \alpha_1} =$$

$$= \frac{h}{u} \frac{(w + v)}{\sqrt{(w + v)^2 - u^2}}$$

(nhớ lại $\sin \alpha_1 = u/(w + v)$ $\cos \alpha_1 = \sqrt{1 - \sin^2 \alpha_1}$); Như vậy

$$|DC_1| = \frac{hw}{u \cos \alpha_1} - \frac{h \sin \alpha_1}{\cos \alpha_1} =$$

$$= \frac{h(w^2 - u^2 + wv)}{u \sqrt{(w + v)^2 - u^2}}.$$

Vì vậy, để đến được phao $B$ trong thời gian ngắn nhất, phao nhỏ phải tan chảy từ điểm $C_1$, ở khoảng cách xa

$$x = l + h \frac{(w^2 - u^2 + wv)}{u \sqrt{(w + v)^2 - u^2}}.$$

Phương pháp lời giải động học bài toán mà chúng tôi đã xem xét bằng cách xây dựng mặt trước của tất cả các chuyển động có thể xảy ra dựa trên bức tranh vật lý nổi tiếng về sự phân bố các khả năng trong môi trường; mặt trước trong trường hợp này là ranh giới thực của khu vực nơi nhiễu loạn xảy ra tại một thời điểm nhất định. Dễ dàng nhận thấy rằng khi tìm kiếm quỹ đạo tối ưu, chúng ta đã lợi dụng mối quan hệ lý thuyết tồn tại giữa mặt trước và tia, cụ thể là tia là tuyến tính mà nhiễu loạn truyền đi trong thời gian ngắn nhất. Nguyên lý xây dựng mặt trước mà chúng tôi đề xuất không gì khác hơn là nguyên lý Heugen - một phương pháp xây dựng mặt trước truyền sóng khả năng.
