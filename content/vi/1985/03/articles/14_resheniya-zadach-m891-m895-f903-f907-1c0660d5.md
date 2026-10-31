---
id: 1985-3-resheniya-zadach-m891-m895-f903-f907-1c0660d5
issue: kvant_1985_3
year: 1985
number: "3"
title: Lời giải bài toán M891—M895; F903—F907
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 30
page_last: 33
page_labels: 28-31
tag: T8MA
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 345add5e0c8571f815d1c7e45cda2e921b3e18d9e9720b342f212fa7bb872805
prompt_sha256: draft-1
translated_from: content/ru/1985/03/articles/14_resheniya-zadach-m891-m895-f903-f907-1c0660d5.md
source_content_sha256: 745b7593093f06d36e4cf134ddebb58f92107bd67201a45314dc9004ba934ab1
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 28⟧

—4q, ..., —1984q, 1985q (q>0), respectively.
Prove that one of the balls has an everywhere positive charge density on its surface. The distances between the balls are finite.

V. A. Yasinski

P927. A charged particle flies through a scintillation counter; the scintillating molecules along its trajectory emit light. The light is emitted isotropically (i.e. uniformly in all directions) at each point. What part of the emitted light will leave the scintillator into the air, if the refraction coefficient of the scintillating matter is $n=1.6$? Light absorption in the scintillator may be neglected.

Remark. The solid angle at the vertex of a cone equals $\Omega=2\pi(1-\cos\theta)$, where $\theta$ is the angle between the cone's axis and its generator.

S. A. Khorozov

Lời giải bài toán

M891 — M895; F903 — F907

Trong tam giác $ABC$ này, chúng ta biểu thị độ dài các cạnh $BC$ và $CA$ bằng $a$ và $b$, độ dài của các đường trung tuyến $AA_1$ và $BB_1$ bằng $m_a$ và $m_b$, giao điểm của các đường trung tuyến bằng $M$ (xem. hình). Vì khoảng cách từ giữa một cạnh đến giao điểm của các đường trung tuyến bằng một phần ba của nó và tứ giác $MA_1CB_1$ được mô tả xung quanh một đường tròn nên đẳng thức $m_a/3+b/2=m_b/3+a/2$ hoặc

$$m_a + \frac{3b}{2} = m_b + \frac{3a}{2}. \tag{1}$$

Hơn nữa, các tam giác $AA_1C$ và $BB_1C$ có diện tích bằng nhau (bằng diện tích tam giác $ABC$) và có chung đường tròn nội tiếp nên chu vi của chúng bằng nhau: $m_a+a/2+b=m_b+b/2+a$, tức là

$$m_a + \frac{b}{2} = m_b + \frac{a}{2}. \tag{2}$$

Trừ đẳng thức (2) từ (1), chúng ta thu được $a=b$.

Lưu ý rằng câu bài toán cũng đúng khi đường tròn tiếp xúc với phần kéo dài hai cạnh của tam giác và hai đường trung tuyến.

A. A. Muragov

M892. a) Chứng minh rằng trong các số $2^m+2^k$ cũng như trong các số $3^m+3^k$ có vô số bậc và trong các số $4^m+4^k$, $5^m+5^k$ và $6^m+6^k$ không có một số nguyên chính phương nào (ở đây $m$ và $k$ là các số tự nhiên, $m \neq k$).
b)* Có hình vuông nào giữa các số $7^m+7^k$ không?

a) Trước tiên chúng ta lưu ý rằng nếu số $a^m+a^k$ là số bình phương thì có vô số số bình phương loại này: $a^{m+2n}+a^{k+2n}=(a^n)^2 \cdot (a^m+a^k)$ (ở đây $m$ hoặc $k$ cũng có thể bằng 0). Do đó, mệnh đề bài toán cho $a=2$ và $a=3$ suy ra từ các đẳng thức $2^3+2^0=8+1=3^2$, $3^1+3^0=2^2$.

Trường hợp $a=4$. Đặt $4^m+4^k=b^2$, trong đó $b$ là số nguyên và $m>k$; sau đó $4^{m-k}+1=(b/2^k)^2$ hoặc $4^n+1=c^2 (n=m-k, c=b/2^k)$. Theo sau đó là $(c+2^n)(c-2^n)=1$, điều này rất khó xảy ra.

⟦folio 29⟧

Trường hợp $a=5$. Dễ dàng nhận thấy rằng số $5^m$ với bất kỳ $m>1$ nào đều có chữ số tận cùng là 25, vì vậy $5^m+5^k$ chỉ có thể kết thúc bằng 30 (đối với $k=1$) hoặc 50 (đối với $k>1$) và do đó, không thể là số chính phương (hình vuông tận cùng bằng 0 phải chia hết cho 100).

Trường hợp $a=6$. lũy thừa của 6 luôn tận cùng bằng 6, nghĩa là số $6^m+6^k$ luôn tận cùng bằng 2. Nhưng bình phương các số nguyên chỉ có thể tận cùng bằng 0, 1, 4, 6, 9.

6) Đáp số: không. Vì 7 khi chia cho 3 dư 1 nên mọi lũy thừa của 7 cũng có cùng số dư. Do đó, số $7^m+7^k$ chia cho 3 dư 2 và do đó, không thể là số bình phương $((3n)^2$ chia hết cho 3 mà là $(3n \pm 1)^2 = 3(3n^2 \pm 2n) + 1)$.

A. I. Zaichik, V. N. Dubrovsky

M893. Hai trong số n khối máy tính được kết nối bằng một sợi dây. Có thể phủ mỗi dây này bằng một trong n—1 màu sao cho n—1 dây có màu khác nhau thoát ra khỏi mỗi khối nếu a) $n=6$; b) $n=13$?

a) Đáp số: bạn có thể. Màu yêu cầu được hiển thị ở hình.

6) Đáp số: không thể được. Thật vậy, nếu sử dụng $m$ các lỗ có một màu bất kỳ thì số khối là $2m$ (số đầu của tất cả các lỗ này và mỗi đầu được kết nối với chính xác một khối). Nhưng 13 là số lẻ.

bài toán này thường được xây dựng dưới dạng bài toán về việc lên lịch cho một chuyến tham quan vòng tròn - trong trường hợp này, các dây cùng màu được trả lời bằng cách chia các phần của chuyến tham quan thành từng cặp cho cùng một loại. Chúng ta đã thấy rằng đối với $n$ lẻ thì bài toán này là không thể quyết định được. Có thể chứng minh rằng với số chẵn $n$ nó luôn có lời giải (ví dụ, xem cuốn sách của O. Ore “Lời mời đến lý thuyết số” (M.: Нayka, 1980, Ch. 8, § 3), cũng như lời giải bài toán 1.16 trong cuốn “Mô tả toán học tương ứng” (M.: Hayka, 1981, tr.19)).

V. V. Alekseev

M894. a) Tổng gót của các số không âm bằng 1. Chứng minh rằng chúng có thể đặt cách nhau xung quanh một đường tròn sao cho tổng gót của tích từng cặp của các số lân cận không vượt quá 1/5.

b)* Xung quanh hình tròn có $n \geqslant 4$ các số không âm, tổng bằng 1. Chứng minh rằng tổng n tích từng cặp của các số lân cận không vượt quá 1/4.

a) Ta sẽ chứng minh bằng phản chứng. Giả sử rằng đối với mọi cách sắp xếp số $a, b, c, d, e$, chúng ta xem xét tổng lớn hơn 1/5, cụ thể là (xem hình 1 và 2):

$$ab+bc+cd+de+ea > 1/5,$$
$$ac+ce+eb+bd+da > 1/5.$$

Từ đây ta có mâu thuẫn:

$$1 = (a+b+c+d+e)^2 = \frac{a^2+b^2}{2} + \frac{b^2+c^2}{2} + \frac{c^2+d^2}{2} +$$
$$+ \frac{d^2+e^2}{2} + \frac{e^2+a^2}{2} + 2[(ab+bc+cd+de+ea) +$$
$$+(ac+ce+eb+bd+da)] \geqslant$$
$$\geqslant 3(ab+bc+cd+de+ea) +$$
$$+ 2(ac+ce+eb+bd+da) > 1$$

(chúng tôi đã sử dụng bất đẳng thức $x^2+y^2 \geqslant 2xy$).

Từ lời giải rõ ràng không tồn tại điều kiện không âm của các số. Tuyên bố bài toán

⟦folio 30⟧

(với 1/5 được thay thế bằng 1/n) có giá trị cho mọi số $n$.

6) Chúng ta phải chứng minh rằng với mọi $n \geqslant 4$ số không âm $a_1, \dots, a_n$ có tổng bằng 1 thì bất đẳng thức đúng
$$a_1a_2 + a_2a_3 + \dots + a_{n-1}a_n + a_na_1 \leqslant 1/4.$$

Với ngay cả $n (n=2m)$, bất đẳng thức này được chứng minh vô thời hạn: đặt $a_1 + a_3 + \dots + a_{2m-1} = a$; thì rõ ràng là
$$a_1a_2 + \dots + a_na_1 \leqslant (a_1 + a_3 + \dots + a_{2m-1}) \times \times (a_2 + a_4 + \dots + a_{2m}) = a(1-a) \leqslant 1/4.$$

Bây giờ đặt $n$ là số lẻ và đặt $a_k$ là số nhỏ nhất trong các số đã cho. (Để thuận tiện, chúng tôi sẽ giả sử rằng $1 < k < n-1$ - điều này không giới hạn tính tổng quát cho $n \geqslant 4$.) Chúng ta hãy đặt $b_i = a_i$ cho $i=1, \dots, k-1$, $b_k = a_k + a_{k+1}$ và $b_i = a_{i+1}$ cho $i=k+1, \dots, n-1$. Áp dụng bất đẳng thức cho các số $b_1, \dots, b_{n-1}$, ta có:
$$a_1a_2 + \dots + a_{k-2}a_{k-1} + (a_{k-1} + a_{k+2})b_k + a_{k+2}a_{k+3} + \dots + a_{n-1}a_n + a_na_1 \leqslant 1/4.$$

Nó vẫn còn để tận dụng thực tế là
$$a_{k-1}a_k + a_ka_{k+1} + a_{k+1}a_{k+2} \leqslant a_{k-1}a_k + a_{k-1}a_{k+1} + a_{k+1}a_{k+2} \leqslant (a_{k-1} + a_{k+2})b_k.$$

Lưu ý rằng nhìn chung, các ước tính được chỉ ra là chính xác (không thể giảm bớt); ở điểm a) ước tính $1/n$ đạt được khi tất cả các số $n$ đều bằng nhau và ở điểm 6) - khi hai trong số chúng bằng 1/2 và các số còn lại bằng 0.
S. V. Gashkov, A. N. Dranshinkov

**M895*. Chứng minh rằng diện tích một phần của hình lập phương bởi mặt phẳng tiếp xúc với hình cầu nội tiếp trong đó không vượt quá một nửa diện tích mặt của hình lập phương. Giải quyết trường hợp khi phần này là a) hình tam giác, b) hình tứ giác. b) Chứng minh rằng trong trường hợp a) diện tích toàn phần của hình lập phương nhỏ hơn diện tích mặt. (Các hình chiếu trực giao của ba mặt này lên mặt phẳng của mặt thứ nhất che phủ hoàn toàn nó và diện tích của các hình chiếu nhỏ hơn diện tích của các mặt đó.) Tuy nhiên, chúng ta sẽ chứng minh a) một cách độc lập, vì điều này sẽ cho một kết quả tổng quát hơn một chút.

Chúng ta hãy biểu thị các đỉnh của phần tam giác của hình lập phương đang xét bằng $A, B, C$, đỉnh chung của ba cạnh; trên đó chúng nằm - qua $V$, các điểm tiếp xúc của hình cầu nội tiếp với các mặt phẳng $ABC, VAB, VBC, VCA$ - qua $T, K, L, M$ (ba điểm cuối cùng, rất thuận tiện, là tâm của mặt khối lập phương; hình 1). Do các tiếp tuyến vẽ với hình cầu bằng nhau từ một điểm, $AT=AK=AM, BT=BK=BL, CT=CL=CM$, nên các tam giác $ABK$ và $ABT, BCL$ và $BCT, CAM$ và $CAT$ (hình 1), cũng như $AVK$ và $AVM, BVK$ và $BVL, CVL$ và $CVM$ (hình 2) theo cặp bằng nhau và hơn nữa, có kích thước bằng nhau. Do đó, diện tích của phần $ABC$ bằng tổng $S_1$ diện tích của các hình tam giác trên hình 1 và diện tích $S_{\text{тетр}}$ của toàn bộ bề mặt của tam giác $VABC$ bằng tổng diện tích của các hình tứ giác $AKBV, BLCV$ và $CMAV$, tức là hai lần tổng

⟦folio 31⟧

$S_2$ vùng hình tam giác xanh lục, đỏ và vàng trên hình 2:
$$S_{\text{тетр}} = 2S_2 = 2(S_{AKV} + S_{BKV} + S_{CLV}) = 2(S_{AKBV} + S_{CLV}).$$

Gọi $S_0$ là diện tích của mặt hình lập phương. Hãy chứng minh rằng với ba điểm bất kỳ $A, B, C$ trên các cạnh của hình lập phương, xuất phát từ đỉnh $V$,
$$S_1 = S_{ABK} + S_{BCL} + S_{CAM} \leq S_0 / 2$$
(1)
(và cụ thể là câu a)).

Để làm điều này, hãy lưu ý rằng nếu hai trong số ba điểm, chẳng hạn như $B$ và $C$, là đóng, thì diện tích của các tam giác $ABK$ và $ACM$, và do đó luôn là tổng $S_1$, phụ thuộc tuyến tính vào $x=VA$ (để chứng minh, xem hình 3). Do đó, bạn luôn có thể di chuyển điểm $A$ đến cuối cạnh để giá trị $S_1$ tăng (hoặc trong mọi trường hợp không giảm). Điều tương tự có thể được thực hiện tuần tự từ các điểm $B$ và $C$; do đó, chỉ cần chứng minh bất đẳng thức (1) cho các điểm $A, B$ và $C$ nằm ở các đỉnh của hình lập phương là đủ. Chỉ có 4 địa điểm như vậy (có thể sắp xếp lại); chúng được hiển thị ở hình 4. Trong hai trường hợp $S_1=0$, trong hai trường hợp còn lại $S_1=S_0 / 2$. Dễ hiểu rằng, ngoại trừ hai trường hợp cuối, bất đẳng thức ở (1) luôn chặt chẽ, nhưng tam giác $ABC$ trên hình 4, in có thể coi là vị trí giới hạn của phần tiếp tuyến với hình cầu viết nên ước lượng ở bài toán a) là chính xác.

Bây giờ chúng ta chứng minh bất đẳng thức
$$S_2 = S_{AKBV} + S_{CLV} < S_0 / 2$$
(và cùng với nó - câu lệnh b)).

Hãy để định nghĩa $KB \geqslant KA$. Rõ ràng, đường $KB$ chia mặt hình lập phương thành hai hình thang bằng nhau có diện tích $S_0 / 2$, một trong số đó - $VBB_1U$ (hình 2) bao gồm bốn hình tam giác $AKBV$ và $AKB_1U$. Như vậy đủ để chứng minh rằng
$$S_{CLV} < S_{AKB_1U}.$$
Chúng ta hãy vẽ đoạn $UC_1=VC$ (hình 5) trên cạnh $UV$; thì các tam giác $C_1KU$ và $CLV$ bằng nhau và $\angle C_1KU = \angle CLV = \angle AKB_1$.

(Thật vậy, từ đẳng thức của các tam giác một cạnh trên hình 2 suy ra $2(\angle CLV + \angle AKB) = \angle AKB + \angle BLC + \angle CMA = \angle ATB + \angle BTC + \angle CTA = 360^\circ = 2(\angle AKB_1 + \angle AKB)$.) Do đó, $\angle B_1KU = \angle C_1KA$ (hình 5) và, ngoài ra, $KB_1 = KB \geqslant KA$, $KU > KC_1$, do đó, $S_{AKC_1} < S_{B_1KU}$, đó là
$$S_{CLV} = S_{C_1KU} = S_{AKC_1} + S_{AKU} < S_{B_1KU} + S_{AKU} = S_{AKB_1U}.$$
Các thông báo tương tự như ở điểm a) cho thấy ước tính ở đây là chính xác.

6) Đặt $ABCD$ là một phần tứ giác của khối ngăn cách cạnh $UV$ với nó và giao các mặt với tâm $K, L, M, N$ (hình 6). Như trên dễ thấy diện tích của nó bằng tổng $S_3$ diện tích của các tam giác $ABK, BCL, CDM$ và $DAN$, hiển nhiên nhỏ hơn tổng
$$S_4 = S_{ABK} + S_{BLCV} + S_{CDM} + S_{DNAU}.$$

(Cuối cùng xem trang 34)
