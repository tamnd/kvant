---
id: 1974-12-resheniya-zadach-m256-m260-f269-f272-48b2f833
issue: kvant_1974_12
year: 1974
number: "12"
title: Lời giải bài toán M256—M260; F269—F272
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 48
page_last: 56
page_labels: 46-54
tag: 2N1O
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 5a88ce5c7a725221cc1adfcd1b07a91cd12610452ae6ff5c35268b80dc13f2af
prompt_sha256: draft-1
translated_from: content/ru/1974/12/articles/13_resheniya-zadach-m256-m260-f269-f272-48b2f833.md
source_content_sha256: 565b24fdb5a1701f5b41bbcbaa85db540ea9bad2fc00dfcb6f9c31a433eb4996
translation_model: draft
translation_run: vi-draft-2026-11-03
translation_quality: draft
---

⟦folio 46⟧

Lời giải bài toán

M256—M260; F269—F272

M256. Một đa giác được mô tả xung quanh một vòng tròn. Điểm tiếp xúc của các cạnh của nó với đường tròn là các đỉnh của đa giác thứ hai nội tiếp trong đường tròn. Chứng minh rằng tích các khoảng cách từ một điểm M tùy ý của đường tròn theo các cạnh của một đa giác bằng tích các khoảng cách từ cùng một điểm M theo các cạnh của đa giác đó.

( Xét từ điểm M do của cạnh, khoảng cách đến đường thẳng mà cạnh này nằm bị giẫm đạp.)

Đầu tiên chúng ta hãy chứng minh bổ đề này. Nếu M, P và Q là ba điểm tùy ý của một đường tròn cho trước thì khoảng cách |MK| từ điểm M đến đường thẳng PQ bằng trung bình hình học của khoảng cách |ML| và |MN| từ M đến các tiếp tuyến tại P và Q:

$$|MK|^2 = |ML| \cdot |MN|.$$ (1)

Hãy tưởng tượng rằng điểm P và Q cố định và M di chuyển quanh đường tròn. Đối với mọi vị trí *) góc

*) Dưới đây chúng ta giả sử rằng M không trùng với P hoặc Q (trong trường hợp đã biểu thị, đẳng thức (1) rất mạnh - cả hai phần của nó đều bằng 0).

$$\Rightarrow MPL \text{ и } \Rightarrow MQK \text{ (не превысющие, разумеется, } 90^\circ \text{) равны по величины — каждый из них изменяется положной дуги PM (не превысшейшей положружности), поэтому прямогольные треугольники MPL и MQK подобны и}$$

$$\frac{|ML|}{|MK|} = \frac{|MP|}{|MQ|}.$$ (2)

(Bình đẳng này, rất indo, cũng đúng trong trường hợp các tam giác vuông suy biến thành các đoạn thẳng - tại thời điểm này điểm M đối xứng đường kính với P.) Bằng cách tương tự, người ta chứng minh rằng $\triangle MQN \sim \triangle MPK$:

$$\frac{|MN|}{|MK|} = \frac{|MQ|}{|MP|}.$$ (3)

Từ (2) và (3) suy ra (1).

Bây giờ chúng ta hãy chứng minh khẳng định bài toán. Để làm điều này, hãy áp dụng bổ đề cho điểm M của đường tròn và cho mỗi cạnh PQ của đa giác nội tiếp, sau đó khắc phục tất cả các đẳng thức có dạng (1).

Những thiếu sót trong lời giải mà độc giả gửi đến chủ yếu là do trong chứng minh Lem chúng ta chưa xét đến tất cả các trường hợp có thể xảy ra về vị trí của các điểm P, Q và M trên đường tròn (một số được thể hiện ở hình 1, a, b, c). lời giải của chúng tôi sử dụng lý luận bao gồm tất cả các trường hợp cùng một lúc.

M257. Với tự nhiên n ≥ 2 thì bất đẳng thức nào

$$x_1^2 + x_2^2 + \dots + x_n^2 \geq p \left( x_1 x_2 + x_2 x_3 + \dots + x_{n-1} x_n \right)$$

đúng với mọi số thực x1, x2, ..., xn, nếu a) p = 1; 6) p = 4/3; b) p = 6/5?

Đáp số. a) với mọi n; 6) với n 3; b) với n ≤ 4.

Hình 1.

⟦folio 47⟧

Hình 2. $p$ càng gần một thì hyperbol càng gần hình tròn và cầu thang càng có nhiều bậc.

Lưu ý rằng nếu chúng ta đặt $x_1^2 + x_2^2 + \dots + x_n^2 - 1 + x_n^2 - px_1x_2 - px_2x_3 - \dots - px_n - 1x_n \geq 0$ (*) vào bất đẳng thức

một vài biến cuối cùng $x_k, x_{k+1}, \dots, x_n$ bằng 0 thì ta thu được bất đẳng thức tương tự tương ứng với biến nhỏ hơn $n$. Theo đó, nếu (*) đúng (với tất cả $x_1, x_2, \dots, x_n$) đối với một số $n$, thì nó đúng với $n$ nhỏ hơn. Do đó, với mọi $p$ cố định đều có một số nguyên $N(p) \geq 2$ sao cho (*) giữ cho $n < N(p)$ và không thành công (đối với một số $x_1, x_2, \dots, x_n$) cho $n \geq N(p)$; cũng có thể (*) đúng với mọi $n$ (trong trường hợp này chúng ta có thể giả sử rằng $N(p) = \infty$).

Trường hợp cuối cùng xảy ra ở $p = 1$. Thật vậy, trong trường hợp này (*) tương đương với bất đẳng thức rất mạnh

$$x_1^2 + (x_1 - x_2)^2 + (x_2 - x_3)^2 + \dots + (x_{n-1} - x_n)^2 + x_n^2 \geq 0.$$

Hãy để $p = \frac{4}{3}$. Khi đó với $n = 3$ (*) tương đương với bất đẳng thức

$$(3x_1 - 2x_2)^2 + x_2^2 + (2x_2 - 3x_3)^2 \geq 0,$$

và đối với $n = 4$ bất đẳng thức (*) bị vi phạm, ví dụ: khi $x_1 = x_4 = 2, x_2 = x_3 = 3$ (đối với bất đẳng thức $n = 4$ (*) tương đương với:

$$(3x_1 - 2x_2)^2 - x_2^2 + 6(x_2 - x_3)^2 - x_3^2 + (2x_3 - 3x_4)^2 \geq 0;$$

Đây là nơi xuất phát của ví dụ của chúng tôi.)

Hãy để $p = \frac{4}{5}$. Khi đó với $n = 4$ (*) tương đương với bất đẳng thức

$$(5x_1 - 3x_2)^2 + x_2^2 + 15(x_2 - x_3)^2 + x_3^2 + (3x_3 - 5x_4)^2 \geq 0,$$

và đối với $n = 5$ đó là một bất đẳng thức, chẳng hạn khi $x_1 = x_5 = 9, x_2 = x_4 = 15, x_3 = 16$ (ví dụ này xuất hiện một cách tự nhiên nếu chúng ta biến đổi (*) thành dạng

$$16(5x_1 - 3x_2)^2 + (16x_2 - 15x_3)^2 - 50x_3^2 + (15x_3 - 16x_4)^2 + 16(3x_4 - 5x_5)^2 \geq 0).$$

Bây giờ hãy thảo luận cách trả lời câu hỏi bài toán với một $p > 0$ tùy ý. Dễ dàng chứng minh rằng $N(p) = \infty$ với mọi $p \in [0, 1]$ và $N(p)$ là hữu hạn với mọi $p > 1$, và $N(p) = 2$ với $p > 2$. Về nguyên tắc, đối với mỗi $p > 1$ bạn có thể tìm thấy $N(p)$ bằng cách biến đổi vế trái (*) thành tổng các bình phương (và không cần thiết phải quan tâm đến công thức đối xứng cũng như các hệ số là số nguyên hay số hữu tỉ; ở trên chúng tôi đã làm điều này để viết lời giải ngắn hơn). Ví dụ: bạn có thể rút gọn (*) về dạng

$$(s_1x_1 - t_1x_2)^2 + (s_2x_2 - t_2x_3)^2 + \dots + (s_{n-1}x_{n-1} - t_{n-1}x_n)^2 + r_nx_n^2,$$

luôn tin tưởng

$$t_k = p/2s_k, s_{k+1} = \sqrt{1 - t_k^2}$$

($s_1 = 1, k = 1, 2, \dots$). Sau đó $r_n = s_n^2 \geq 0$ tại $n < N(p)$ và $r_n < 0$ tại $n = N(p)$. Do đó, $N(p) - 1$ ($n$ lớn nhất mà (*) vẫn giữ) bằng số bước của “thang” nằm giữa các biểu đồ $s^2 + t^2 = 1$, $st = p/2$ và bắt đầu từ điểm $s = 1$, $t = 0$, (hình 2). Đặt $p_k$ là giá trị của $p$ tại đó cầu thang đối xứng với bisserrissa $s = t$ (kết thúc tại điểm $s = 0$, $t = 1$) và chứa $k$ bước; rõ ràng là chuỗi $p_1 = 2 > p_2 > p_3 > \dots$ có xu hướng là 1 và $N(p) = k + 1$ là $p_{k-1} \geq p > p_k$.

Không khó để chứng minh điều đó $p_2 = \sqrt{2}$, nhưng $p_k$ sau đây đã được tìm thấy từ các phương trình phức tạp liên quan đến phương trình đại số cấp cao.

⟦folio 48⟧

Hãy giải bài toán M257, chúng tôi ước tính $p_2$,

$$p_3 \text{ и } p_4: \text{поскольку } N\left(\frac{4}{3}\right)=4, N\left(\frac{6}{5}\right)=5, \text{ то } p_2>\frac{4}{3}>p_3>\frac{6}{5}>p_4.$$

N. B. Vasiliev

**M258.** Cho ba điểm $K, L, N$ trên mặt phẳng. Người ta cũng biết rằng vật nặng là lồi và trung điểm của một số cạnh của nó nằm tại các điểm đã cho $K, L, N$. Chỉ định một tập hợp các điểm có thể đánh:

a) phần giữa của mặt sau;
b) đỉnh của lỗ sâu đục emnoy.

a) Lưu ý rằng nếu các trung điểm của các cạnh nối nối tiếp trong một hình tứ giác thì hình bình hành được tạo thành. Để chứng minh thực tế nổi tiếng này, chỉ cần kiểm tra một trong các đường chéo của tứ giác này (hình 3): trong các tam giác thu được, hai đoạn nối trung điểm của cạnh là đường giữa và do đó chúng song song với đường chéo đã vẽ và bằng một nửa.

Từ nhận xét được đưa ra, có thể suy ra rằng điểm giữa của cạnh đỉnh - điểm $M$ - là đỉnh của hình bình hành, các đỉnh còn lại là $K, L$ và $N$. Dễ dàng nhận thấy tập hợp các điểm mà điểm $M$ có thể rơi gồm ba điểm $\{M_1, M_2, M_3\}$ - các đỉnh của một tam giác, các đường giữa là các cạnh của tam giác $KLN$ (hình 4).

6) Hãy xem xét một trong các hình bình hành, ví dụ: $KLM_1N$. Các đỉnh của một tứ giác lồi có thể nằm ở đâu nếu trung điểm của cạnh đó tại các điểm $K, L, M_1$ và $N$? Hãy nhớ rằng một đa giác là lồi nếu nó nằm trên một cạnh của mỗi đường thẳng tiếp nối cạnh của nó. Do đó, các đỉnh của tứ giác chỉ có thể nằm ở hình bán cầu giữa phần kéo dài các cạnh đối diện của hình bình hành (hình 5, a). Sử dụng thực tế là hai đỉnh liền kề của tứ giác đối xứng với đỉnh của hình bình hành, chúng ta tìm được tập hợp các điểm mà tại đó các đỉnh của tứ giác có thể xuất hiện - nó bao gồm bốn hình bình hành thu được từ $KLM_1N$ bằng cách dịch song song và có một cạnh chung với nó (hình 5, 6); bạn cũng cần đảm bảo rằng bất kỳ điểm nào của “chữ thập” này đều có thể đóng vai trò là đỉnh của một hình tứ giác.

Nếu bây giờ chúng ta xem xét thêm hai điểm $M_2$ và $M_3$, trong đó có thể có phần giữa của cạnh sâu của đa giác và lấy tam giác trưa tương ứng với $M_1, M_2$ và $M_3$, thì cuối cùng chúng ta sẽ có được một đa giác được đánh dấu bằng trihovka ở hình 6; nó bao gồm 15 hình tam giác đồng dạng với $\Delta KLN$.

A. P. Savin

**M259.** Chúng ta hãy vẽ một bộ tứ hình vuông trên giấy ca rô, tâm của chúng nằm ở các đỉnh của hình chữ nhật tính từ cạnh bên, với các đường thẳng song song (Ví dụ: trên hình 7, ba hình vuông được vẽ).

Có thể đặt số lượng tứ giác tối đa không có ô chung là bao nhiêu:

a) bình phương $5 \times 5$?
b) trong một hình chữ nhật gồm $m \times n$ ô?

a) Năm bộ tứ có thể được sắp xếp trong hình vuông $5 \times 5$ (xem hình 8). Không thể đặt gót lớn của bộ tứ vào đó, vì $5 \times 5 = 25$ ô ít nhất năm ô - mỗi ô một hàng - sẽ không vừa với các ô vuông.

6) Nếu $m$ và $n$ chẵn thì rất có thể các ô $mn/4$ có thể được đặt trong hình chữ nhật $m \times n$.

⟦folio 49⟧

Hình 7. Hình 8.

Nếu $m$ chẵn và $n$ lẻ thì có thể đặt $m(n-1)/4$ bộ tứ (công thức tương tự áp dụng cho $m$ lẻ và chẵn $n$).

Nếu $m$ và $n$ lẻ thì phải xét hai trường hợp. (Chúng tôi sẽ giả định rằng $m \geq n$).

1) $n = 4k + 1$. Rõ ràng là trong trường hợp này có thể bao phủ không quá $mn - (m-n) - n = m(n-1)$ ô bằng bộ tứ; hình 9 hướng dẫn cách thực hiện điều này: đường chéo được xóa khỏi hình vuông $n \times n$ (hãy nhớ rằng $n$ là số lẻ) và các bộ tứ được đặt theo cách tương tự như đã thực hiện trên hình 8 trong hình vuông $5 \times 5$; từ hình chữ nhật $(m-n) \times n$ $(m-n)$ đã chẵn) dòng dưới cùng sẽ bị loại ra - sau đó trong hình chữ nhật $k \times l = (m-n) \times (n-1)$ và $k$ và $l$ đều chẵn, và cách trộn các bộ tứ rất indo. Tổng cộng - $m(n-1)/4$ bộ tứ.

2) $n = 4k + 3$. Trong trường hợp này, không thể che $m(n-1)$ ô bằng bộ tứ, vì số $m(n-1)$ không chia hết cho 4. Nhưng $m(n-1) - 2$ ô đã có thể được che - chính xác như cách hiển thị trong hình 10 - $m + 2$ các ô được tô bóng bị loại ra: $n-2$ - trên đường chéo của hình vuông $(n-2) \times (n-2)$, $(m-n+2)$ nằm ở bên phải dòng dưới cùng của hình chữ nhật ban đầu và hai ô nằm ở góc trên bên trái (khi đó $n-3$ được chia cho 4, $m-n+2$ và $n-1$ đều là số chẵn).

A. A. Gritsoryan

M260. Vòng tròn được chia bởi các thánh tích $A_1, A_2, \dots, A_n$ thành $n$ phần bằng nhau, mỗi phần được sơn một màu nhất định. Hai cung (có các đầu ở phần còn lại của phép chia) được gọi là có màu giống hệt nhau nếu, với một số lần lặp lại của vòng tròn, một trong các sọc của chúng, bao gồm cả màu của từng phần, trùng với cung. (Ví dụ: trên hình 11 cung $A_2A_6$ và $A_6A_{10}$ có màu bằng nhau.) Chứng minh rằng nếu với mỗi lũy thừa của phân vùng $A_i$ người ta có thể xác định được hai phân số rời nhau

⟦folio 50⟧

bắt đầu với thực tế là các cung α và β có màu bằng nhau. Trong phần tiếp theo, các cung có màu giống hệt nhau sẽ được gọi là bằng nhau. Thông qua |α| hãy ký hiệu độ dài cung α. Chúng tôi sử dụng chiều kim đồng hồ để đi qua vòng tròn là dương (điều này cho phép chúng tôi trải rộng phần đầu và phần cuối của cung một cách tự nhiên). Gọi βγ là cung được tạo thành nếu chúng ta gắn đầu cung γ vào cuối cung β (hình 12).

Cung đối xứng là cung trên đó có các cung nhỏ bằng nhau nằm ở đầu và cuối, nghĩa là α là cung đối xứng nếu có các cung β, γ và δ sao cho α = βγ = δβ (hình 13).

Theo điều kiện, đối với mỗi điểm phân chia, bạn có thể chỉ định một cặp cung bằng nhau không giao nhau với một điểm cuối chung tại điểm này. Nói chung, có thể có vài cặp cung như vậy cho mỗi điểm—hãy thử đưa ra một ví dụ. Do đó, chúng ta hãy làm rõ chính xác cặp cung nào chúng ta sẽ xem xét: chúng ta liên kết với mỗi điểm phân chia cặp cung bằng nhau không giao nhau (có một đầu chung), các cung của chúng có độ dài tối thiểu; Trong phần tiếp theo, chúng ta sẽ chỉ xem xét những cặp như vậy.

Chúng ta sẽ cần những thứ sau

Bổ đề 1. Nếu cung α là cung nhỏ nhất thì nó không đối xứng (bạn hãy tự chứng minh bổ đề này).

Giả sử rằng trong số tất cả các cặp cung tối thiểu tương ứng với các điểm khác nhau, cặp phân chia tương ứng với điểm A có độ dài lớn nhất và để các đầu của cung này khác với A—các điểm B và C (xem hình 14, a)—không trùng nhau.

Điểm trung tâm của chứng minh là

Bổ đề chính. Nếu bạn cắt các cung BA khỏi một đường tròn và “dán” điểm A vào điểm B, thì đường tròn mới sẽ lại có đặc tính là đối với bất kỳ điểm phân chia nào, bạn có thể chỉ định một cặp cung tròn rời nhau bằng nhau có một đầu chung tại điểm này.

Sử dụng bổ đề này, “tính tuần hoàn” của màu sắc được chứng minh bằng quy nạp theo số điểm của phân vùng. Chúng ta sẽ tiến hành quy nạp sau, nhưng bây giờ chúng ta trình bày cách chứng minh bổ đề chính.

Chúng ta ký hiệu các cung BA và AC bằng chữ α. Hãy xem xét một phần của hình tròn mới thu được từ hình tròn cũ sau khi cắt cung BA và “dán” điểm A vào điểm B (xem hình 14, b); Chúng ta hãy biểu thị các điểm phân chia của hình tròn mới bằng các chữ cái có dấu gạch ngang.

Gọi M' là điểm phân chia trên đường tròn mới không nằm trên cung A'C', và gọi M là điểm tương ứng trên đường tròn cũ. Điểm M tương ứng với cặp điểm bằng tối thiểu (ví dụ: cung v - xem hình 14, a) đối với LM và MK. Theo điều kiện của Bổ đề |α| ≥ |v| nên cung MK nằm hoàn toàn trên cung MA.

Nhưng cung MA bằng cung M'C'; điều này có nghĩa là cung v nằm ở đầu cung M'C', nghĩa là điểm M' đóng vai trò là điểm bắt đầu của cung đó. Lập luận theo cách tương tự, chúng ta hãy dựng, dọc theo cung LM, một cung trên một đường tròn mới bằng v, với điểm cuối của nó là điểm M'.

Tuy nhiên, có thể xảy ra trường hợp hai cung được xây dựng (một cung có điểm bắt đầu tại điểm M', cung còn lại có điểm kết thúc tại điểm này) giao nhau (hình 15). Hãy để chúng tôi chứng minh rằng điều này thực sự không thể xảy ra.

Chúng ta ký hiệu các cung M'L', L'K' và K'M' (theo chiều kim đồng hồ) lần lượt là β, η và δ; thì v = βη = ηδ, tức là v là cung đối xứng; nhưng điều này mâu thuẫn với Bổ đề 1, và do đó các cung L'M' và M'K' không giao nhau.

Như vậy, với những điểm M' không nằm trên cung A'C' thì mọi điều đều được chứng minh.

Bây giờ đặt điểm M' nằm trên cung A'C' và xác định |A'M'| ≤ |M'C'| (xem hình 16, b). Khi đó trên đường tròn cũ điểm M' tương ứng với hai điểm - chúng ta biểu thị chúng bằng M và M1; điểm M nằm trên cung BA, điểm M1 trên cung AC (hình 16, a). Trường hợp khi cung MK (cung v nhỏ nhất có gốc tọa độ tại điểm M)

⟦folio 51⟧

Hình 15.

không cắt cung AC, được chia như lần đầu (khi điểm M' không thuộc A'C'). Tại hình 16, a, trường hợp phức tạp nhất được mô tả, khi các cung MK và AC cắt nhau. Trong trường hợp này (xem ký hiệu hình 16, a) các mối quan hệ sau giữ nguyên:

1) δαα = vvγ;
2) |δ| < |v|, |γ| < |α|.

Bổ đề 2. Nếu sự tương ứng 1) và 2) đúng và nếu tích v và α không đối xứng thì tồn tại một kết hợp β sao cho α = βγ, v = γβ.

Từ bổ đề này suy ra rằng điểm K trùng với điểm M₁ và δ = γ (xem hình 17, a.).

Sử dụng Bổ đề 2 và thực tế là |A'M'| ≤ |M'C'|, dễ dàng chứng minh điểm M₁ ứng với một cặp cung bằng cung v = γβ, từ đó suy ra C là điểm đầu của cung bằng β (hình 17, a); do đó, điểm M' tương ứng với một cặp cung bằng γβ (hình 17, b).

Điều này kết thúc việc chứng minh Bổ đề Chính. Một phần, theo đó, độ dài của cặp cung tối đa trên một đường tròn mới không vượt quá độ dài

Hình 17.

cặp cung lớn nhất trên đường tròn cũ.

Hãy chuyển sang chứng minh tính tuần hoàn của việc tô màu. Ta tiến hành quy nạp theo số n điểm của phân hoạch. Với n = 2 điều này là hiển nhiên. Giả sử rằng chúng ta đã chứng minh được tính tuần hoàn cho n ≤ k, và chúng ta sẽ chứng minh điều đó cho n = k + 1. Giả sử cặp cung có độ dài cực đại tương ứng với định nghĩa về điểm A. Nếu toàn bộ đường tròn là chu vi của cặp cung này thì mệnh đề quy nạp là đúng. Nếu không, chúng ta sẽ thể hiện một trong những cung này và dán các đầu lại với nhau. Theo Bổ đề Chính, đường tròn mới thỏa mãn các điều kiện bài toán, và điểm phân chia trên đó nhỏ hơn trên đường tròn cũ; do đó, theo giả thuyết quy nạp, việc tô màu hình tròn mới là tuần hoàn; và độ dài của khoảng thời gian không vượt quá độ dài của cung bị cắt - chúng ta hãy biểu thị nó bằng α.

Bổ đề 3. Nếu |α| ≥ 0, α là không đối xứng doa u αα...αβ = v ... v, mo |α| = |v|.

Từ bổ đề này suy ra rằng độ dài của chu kỳ bằng α, và do đó đường tròn mới có

⟦folio 52⟧

Xem hiển thị ở hình 18. Sẽ có được hình tròn cũ nếu chúng ta cắt hình tròn mới tại điểm $A'$ và chèn một cung $\alpha$; Rõ ràng là thao tác này sẽ không làm gián đoạn tính tuần hoàn của việc vẽ tranh. Bằng chứng đã hoàn tất.

G. A. Gurevits

F269. Một ma trận toán học bao gồm một quả cầu kim loại mềm có khối lượng $m$ và một sợi dây mỏng có nim và chiều dài $l$, thực hiện một dao động nhỏ trong một từ trường đều nằm ngang có cảm ứng $B$, hướng vuông góc với mặt phẳng dao động của ma trận. Góc tối đa mà ma trận lệch khỏi phương thẳng đứng là $\alpha_0$. Góc này sẽ thay đổi như thế nào nếu tại thời điểm ma trận đi qua vị trí cân bằng, một tụ điện có độ dày $C$ (hình 19) được nối với nó bằng dây nha khoa và trong thời gian tiếp xúc rất ngắn, tụ điện được tích điện thành một sọc.

Do sợi dẫn của ma trận chuyển động trong từ trường nên xuất hiện một hiệu điện thế nhất định ở hai đầu sợi. Nhờ đó, khi nối tụ điện vào ma trận, dòng điện sẽ chạy qua mạch và tụ điện sẽ tích điện. Trong trường hợp này, một phần năng lượng của ma trận $W_M$ sẽ chuyển thành năng lượng của tụ điện $W_K$ và một phần sẽ được giải phóng dưới dạng nhiệt trong dây dẫn. Năng lượng dao động của ma trận có liên quan đến góc lắng đọng ma trận tối đa so với phương thẳng đứng. Do đó, trước tiên chúng ta sẽ tìm năng lượng mới của ma trận $W_M'$, sau đó là góc cực đại $\alpha_1$.

Từ định luật bảo toàn năng lượng suy ra rằng

$$W_M = W_M' + W_K + Q.$$

Đặt chiều tại hai đầu sợi dây khi đi qua vị trí cân bằng bằng $U$. Vì thời gian tiếp xúc với tụ điện rất ngắn nên chúng ta có thể giả sử rằng hướng của tụ điện không thay đổi trong thời gian này. Sau đó hướng tới tụ điện sau khi sạc

$$W_M = mgl(1 - \cos \alpha_0)$$

Và

$$W_M' = mgl(1 - \cos \alpha_1).$$

Pozumu

$$mgl(1 - \cos \alpha_1) = mgl(1 - \cos \alpha_0) - CU^2.$$ (1)

Để tìm $\alpha_1$, chúng ta cần tính $U$. Hãy làm điều này. Electron nằm ở điểm $A$ cách điểm treo của ma trận một khoảng $x$ (hình 20), chịu tác dụng của lực Lorentz

$$F_\pi = evB = e\omega xB,$$

trong đó $v$ là tuyến tính và $\omega$ là vận tốc góc của điểm $A$ khi ma trận đi qua vị trí cân bằng. Dưới tác dụng của lực Lorentz, các electron tự do sẽ trộn lẫn xuống dưới (chúng ta giả sử rằng vectơ cảm ứng trong từ trường hướng ra ngoài hình vẽ) cho đến khi điện trường sinh ra ngăn cản điều này. Như vậy,

$$F_\pi = F_{\text{эл}},$$

hoặc

$$e\omega xB = eE,$$

từ đâu $E = \omega Bx$. Nghĩa là, hướng trường phụ thuộc tuyến tính vào $x$ (hình 21).

⟦folio 53⟧

Hình 21.

Như chúng ta đã biết, công do một lực thực hiện luôn bằng diện tích của hình vẽ dưới đồ thị của lực so với tọa độ. Hiệu điện thế ở hai đầu sợi dây là công thực hiện để truyền một điện tích dương đơn vị dọc theo sợi dây và $E$ là lực tác dụng lên điện tích này. Do đó, bằng cách sử dụng biểu đồ hiển thị trong hình 21, chúng tôi tìm thấy

$$U = \frac{1}{2} l \omega l B = \frac{1}{2} \omega l^2 B.$$

Vì $\omega = v/l$ và theo định luật bảo toàn năng lượng

$$\frac{mv^2}{2} = mgl (1 - \cos \alpha_0),$$

Cái đó

$$\omega = \frac{1}{l} \sqrt{2gl (1 - \cos \alpha_0)}$$

Và

$$U = \frac{1}{2} l B \sqrt{2gl (1 - \cos \alpha_0)}. \quad (2)$$

Thay (2) vào đẳng thức (1), ta được

$$mgl (1 - \cos \alpha_1) = mgl (1 - \cos \alpha_0) - \frac{1}{2} Cl^3 B^2 g (1 - \cos \alpha_0).$$

Từ đây

$$1 - \cos \alpha_1 = (1 - \cos \alpha_0) \left(1 - \frac{Cl^2 B^2}{2m}\right). \quad (3)$$

Bởi vì $1 - \cos \alpha = 2 \sin^2 \frac{\alpha}{2}$, và các góc $\alpha_0$ Và $\alpha_1$ nhỏ nên $\sin \alpha \approx \alpha$, Cái đó

$$1 - \cos \alpha_1 \approx \frac{\alpha_1^2}{2} \quad \text{и} \quad 1 - \cos \alpha_0 \approx \frac{\alpha_0^2}{2}.$$

Do đó, ta viết lại đẳng thức (3) dưới dạng

$$\alpha_1^2 = \alpha_0^2 \left(1 - \frac{Cl^2 B^2}{2m}\right),$$

Ở đâu

$$\alpha_1 = \alpha_0 \sqrt{1 - \frac{Cl^2 B^2}{2m}}.$$

F270. Trong một ống nghiệm dài cách đầu bịt kín một khoảng $l_1$ có một lượng thủy ngân ngắn (hình 22). Khối lượng thủy ngân $m$. Cần phải di chuyển ống nghiệm quanh trục thẳng đứng với tốc độ bao nhiêu $\omega$ để thủy ngân đi đến cuối ống nghiệm? Ống nghiệm có chiều dài $l$, nhiệt độ không khí trong ống nghiệm không thay đổi. Áp suất khí quyển $p_0$.

Trong hệ quy chiếu đứng yên, có hai lực tác dụng lên cột thủy ngân theo phương nằm ngang: lực áp suất nguyên tử $F_1 = p_0 S$ ($S$ là diện tích tiết diện của ống nghiệm) và lực áp suất không khí trong ống nghiệm $F_2 = p S$ (xem hình 22). Sự chênh lệch giữa các lực này truyền cho bình thủy ngân một gia tốc hướng tâm bằng $a = \omega^2 l$ (vì thủy ngân nằm ở mép ống nghiệm). Như vậy,

$$m \omega^2 l = p_0 S - p S.$$

Vì nhiệt độ không khí trong ống nghiệm không thay đổi nên theo định luật Boyle-Mariotte

$$p_0 Sl_1 = pSl,$$

Ở đâu

$$p = p_0 \frac{l_1}{l}.$$

Sau đó

$$m \omega^2 l = p_0 S \left(1 - \frac{l_1}{l}\right)$$

Và

$$\omega = \sqrt{\frac{p_0 S (l - l_1)}{ml^2}}.$$

F271. Tính mật độ trung bình $\rho$ của các điện tích trong tầng nguyên tử, nếu biết hướng của trường điện tử trên bề mặt Trái đất là 100 $\cdot$ $m^{-1}$, và ở độ cao $h = 1,5$ km chiều này tăng lên 25 $\cdot$ $m^{-1}$.

Như đã biết, hướng của điện trường của quả cầu mỏng bên trong

⟦folio 54⟧

lớp ric bằng 0, và bên ngoài lớp này độ định hướng sẽ giống như khi toàn bộ điện tích của lớp tập trung ở tâm của nó. (Điều này có thể được chứng minh dựa trên định luật Coulomb và nguyên lý chồng chất.)

Hãy chia Trái đất và bầu khí quyển của Trái đất thành những con voi hình cầu mỏng. Khi đó rõ ràng trên bề mặt Trái đất hướng của điện trường bằng

$$E_0 = \frac{Q_3}{4\pi\varepsilon_0 R_3^2},$$

trong đó $Q_3$ là tổng điện tích của Trái đất, $R_3$ là bán kính của Trái đất.

Ở độ cao $h$, hướng của điện trường bao gồm hướng của trường được tạo ra bởi điện tích $Q_3$ của Trái đất và từ hướng của trường được tạo ra bởi điện tích $Q_a$ của các lớp khí quyển có bán kính nhỏ hơn $R_3 + h$. Đó là

$$E_h = \frac{Q_3 + Q_a}{4\pi\varepsilon_0 (R_3 + h)^2}.$$

Bởi vì

$$Q_a V_a \rho = \left[ \frac{4}{3} \pi (R_3 + h)^3 - \frac{4}{3} \pi R_3^3 \right] \rho,$$

Cái đó

$$E_h = \frac{Q_3}{4\pi\varepsilon_0 (R_3 + h)^2} + \frac{\rho}{3\varepsilon_0} \left[ R_3 + h - \frac{R_3^3}{(R_3 + h)^2} \right].$$

Bán kính Trái đất $R_3$ lớn hơn nhiều so với chiều cao $h$, do đó trong mẫu số của công thức (2) tổng $R_3 + h$ có ​​thể được thay thế bằng $R_3$. Sau đó

$$E_h = \frac{Q_3}{4\pi\varepsilon_0 R_3^2} + \frac{h}{3\varepsilon_0} \rho = E_0 + \frac{h}{3\varepsilon_0} \rho.$$

Từ đây

$$\rho = \frac{3\varepsilon_0 (E_h - E_0)}{h} = - \frac{3 \cdot 8,85 \cdot 10^{-12} \kappa^2 \cdot h^{-1} \cdot m^{-2} \cdot 75 \cdot \theta \cdot m^{-1}}{1500 \, m} \approx -1,3 \cdot 10^{-12} \kappa \cdot m^{-3}.$$

F272. Một nam châm có chiều dài $l$ (hình 23) được treo vào một bức tường nghiêng một góc $\alpha$ so với phương thẳng đứng. Nam châm bị lệch trong mặt phẳng vuông góc với tường một góc nhỏ $\beta$ so với phương thẳng đứng và được tháo ra. Tên dao động của nam châm, nếu

$$\beta > \alpha \text{ и удар шарика о стенку абсолютино уррушей.}$$

Nếu không có vách ngăn, nam châm sẽ thực hiện dao động điều hòa với biên độ góc (góc lệch cực đại so với phương thẳng đứng) $\beta$ và với một khoảng thời gian

$$T_0 = 2\pi \sqrt{\frac{l}{g}}.$$

Khi va chạm với tường, giá trị tuyệt đối của vận tốc nam châm không thay đổi nhưng hướng chuyển động lại thay đổi ngược lại. Điều này có nghĩa là chu kỳ dao động của nam châm $T$ khi có bức tường không bằng $T_0$, nhưng nhỏ hơn giá trị này trong một thời gian $t$. Trong thời gian này, nam châm $t$ thực hiện dao động tự do sẽ lệch sang phải so với phương thẳng đứng từ góc $\alpha$ sang góc $\beta$ và quay trở lại.

Hãy viết phương trình dao động điều hòa của độ dịch chuyển góc $\varphi$:

$$\varphi = \beta \cos \omega t,$$

ở đâu $\omega = \frac{2\pi}{T_0}$. Tại thời điểm $t = 0$ $\varphi = \beta$ tức là nam châm ở vị trí cực bên phải. Sau một thời gian $t_1$ góc lệch của nam châm so với phương thẳng đứng bằng $\alpha$. Từ phương trình dao động

$$\alpha = \beta \cos \omega t_1,$$

Ở đâu

$$t_1 = \frac{1}{\omega} \arccos \frac{\alpha}{\beta}.$$

Từ sự đối xứng rõ ràng rằng

$$\tau = 2t_1 = \frac{2}{\omega} \arccos \frac{\alpha}{\beta} = \frac{T_0}{\pi} \arccos \frac{\alpha}{\beta}.$$

Rồi cuối cùng

$$T = T_0 - \tau = T_0 \left( 1 - \frac{1}{\pi} \arccos \frac{\alpha}{\beta} \right) = 2 \sqrt{\frac{l}{g}} \left( \pi - \arccos \frac{\alpha}{\beta} \right).$$

I.Sh. Slobodetsky
