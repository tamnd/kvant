---
id: 1980-10-miheev-odnoy-lineykoy-119b9263
issue: kvant_1980_10
year: 1980
number: "10"
title: Với một người cai trị
authors:
  - Михеев Ю. В.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 28
page_last: 31
page_labels: 26-29
tag: DTYE
lang: vi
source: kvant_digital
extraction: vision
content_sha256: cd9240e87d8e05cee946be53e0e304333dc86701550c9c7eb31079213461c136
prompt_sha256: draft-1
translated_from: content/ru/1980/10/articles/06_miheev-odnoy-lineykoy-119b9263.md
source_content_sha256: 317e487abced8a4f6f8e1071069c672ff7c6274a4f906f7333a335985f233cf5
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 26⟧

Yu. Mikheev

Với một người cai trị

Trong bài học câu lạc bộ toán học này, chúng ta sẽ giải bài toán để xây dựng bằng một thước kẻ. Những gì có thể được xây dựng theo cách này từ bốn điểm này? Chúng tôi đưa ra một số đáp số cho câu hỏi này. Trên đường đi, bài toán M625 sẽ được giải quyết.

Cho một tập hữu hạn các điểm, một cây thước và một cây bút chì. Khi đó có thể xây dựng được những điểm mới nào?

Hãy để chúng tôi làm rõ tuyên bố bài toán. Một điểm sẽ được coi là được xây dựng nếu nó là một trong các dữ liệu hoặc là giao điểm của hai đường được xây dựng; lần lượt, chúng ta sẽ coi một đường thẳng được dựng nếu nó đi qua các điểm đã cho (một phần đã cho). Tổng quát bài toán là để mô tả tập hợp các điểm có thể được xây dựng từ một tập hợp điểm hữu hạn cho trước.

Rõ ràng là nếu dữ liệu là hai hoặc ba điểm thì không thể xây dựng được điểm mới nào (Hình 1); nếu bốn điểm đã cho, trong đó có ba (hoặc cả bốn điểm) nằm trên cùng một đường thẳng, thì rất thuận tiện, không thể dựng được điểm mới (Hình 2); nếu có bốn điểm trên một, một số trong đó ba (hoặc cả bốn) nằm trên cùng một đường thẳng, thì rất thuận tiện, không thể xây dựng điểm mới (Hình 3).

Cơm. 1.

Cơm. 2.

Cơm. 3.

⟦folio 27⟧

Cơm. 4.

Lời giải được thể hiện trên Hình 5; Nó hiển thị màu đen điểm đã được xây dựng $F$ - giữa $[PQ]$. Đẳng thức $|P'Q'| = |Q'R'|$ xuất phát từ sự đồng dạng của các tam giác $\Delta PMF \sim \Delta R'MQ', \Delta FMQ \sim \Delta Q'MP'$ và đẳng thức $|PF| = |FQ|$.

Bài toán 3. Vẽ một đoạn có độ dài $n \cdot |P'Q'|$.

Để thực hiện việc này, bạn chỉ cần lặp lại quy trình đã sử dụng ở bài toán $n - 1$ lần trước đó. Hình 6 thể hiện cấu trúc của $n = 3$.

Tất nhiên, theo cách tương tự, chúng ta có thể xây dựng một đoạn có độ dài $m \cdot |PQ|$ trên số nguyên tố $PQ$.

Bài toán 4. Chia đoạn $P'Q'$ thành $m$ phần bằng nhau.

Lời giải. Đầu tiên, trên dòng đầu tiên $PQ$ chúng tôi xây dựng $m - 1$ của các đoạn tắc nghẽn $PQ_2, Q_2Q_3, \ldots, Q_{m-1}Q_m$. Sau đó, chúng ta xây dựng $(PP')$ và $(Q_mQ')$ và kết nối điểm giao nhau $A$ của chúng với các điểm $Q_2, Q_3, \ldots, Q_{m-1}$. Các dòng $m - 1$ thu được chia $[P'Q']$ thành $m$ phần bằng nhau. Đối với $m = 4$ thiết kế được hiển thị trong Hình 7.

(Lưu ý rằng việc xây dựng sẽ thất bại nếu $(PP') \parallel (Q_mQ')$. Nhưng khó khăn này rất dễ vượt qua: bạn có thể ngủ

Cơm. 5.

Cơm. 6.

Cơm. 7.

Bắt đầu nhân đôi $[PQ]$, sau đó xây dựng các đoạn $m$ bằng với đoạn nhân đôi, sau đó lặp lại cấu trúc được chỉ ra trong đoạn trước.)

Đối với những gì tiếp theo, chúng ta sẽ phải giả sử rằng những điểm $F, Q, P'Q'$ này là hợp lý, nghĩa là chúng có tọa độ hợp lý đối với một số hệ tọa độ.

Bài toán 5. Xây dựng một điểm hữu tỉ tùy ý $S$ trên số nguyên tố $PQ$.

Lời giải. Đối với các điểm hữu tỷ $P, Q, S$ mối quan hệ $|PS|$: $|PQ|$ là hợp lý (chứng minh!), và do đó $|PS| = \frac{m}{n}|PQ|$, trong đó $m, n \in \mathbb{N}$. Do đó, chỉ cần chia đoạn $PQ$ thành $n$ các phần bằng nhau và hoãn đoạn kết quả $m$ lần kể từ điểm $P$.

Theo cách tương tự, chúng ta có thể xây dựng bất kỳ điểm hữu tỉ nào $T \in (P'Q')$.

Bài toán 6. Xây dựng một điểm hữu tỷ tùy ý $T$ trên mặt phẳng.

⟦folio 28⟧

Lời giải. Giả sử điểm $T$ đã được xây dựng. Hãy vẽ các đường thẳng $TP'$ và $TQ'$; chúng sẽ cắt nhau*) ($PQ$) tại các điểm $E$ và $F$. Vì các đường thẳng $TP'$, $TQ'$, $PQ$ không đồng nhất (nghĩa là được viết dưới dạng phương trình tuyến tính với các hệ số không đồng nhất), nên tọa độ của điểm $E$ và $F$ thu được dưới dạng hệ lời giải của phương trình tuyến tính có hệ số không đồng nhất và do đó cũng không đồng nhất. Biết cách xây dựng $E$ và $F$, chúng ta cũng sẽ xây dựng điểm $T$.

Vì vậy, bắt đầu từ một hình thang có các đỉnh khác nhau, bạn có thể dựng bất kỳ điểm nào có hướng khác nhau! Thật tự nhiên khi hỏi: những điểm nào có thể được xây dựng? Hóa ra - không có.

Bài toán 7. Chứng minh rằng mọi điểm dựng bởi một thước từ một tập hợp các điểm có các góc khác nhau đều khác nhau.

Thật vậy, một đường thẳng đi qua các điểm có các góc khác nhau là không đồng nhất, và giao điểm của các đường dị giác (như lời giải của hệ phương trình tuyến tính với các hệ số có các góc khác nhau) cũng không đồng nhất.

Xin lưu ý rằng chúng tôi đã giải được bài toán $M625a$).

Bây giờ giả sử $A, B, C, D$ là bốn điểm hữu tỉ, dị giác và giao điểm của các đường thẳng dị giác (như lời giải của hệ phương trình tuyến tính có hệ số dị giác) cũng dị loại.

Xin lưu ý rằng chúng tôi đã giải được bài toán $M625a$).

Bây giờ giả sử $A, B, C, D$ là bốn điểm hữu tỉ, dị giác và giao điểm của các đường thẳng dị giác (như lời giải của hệ phương trình tuyến tính có hệ số dị giác) cũng dị loại.

Xin lưu ý rằng chúng tôi đã giải được bài toán $M625a$).

*) Ngược lại $T \in (P'Q')$, và trường hợp này đã được xử lý.

Đường biểu tình. Nhưng đây chính xác là phần khó khăn nhất trong quá trình xây dựng của chúng tôi.

Theo điều kiện, các điểm $A, B, C, D$ tạo thành một tứ giác lồi, khác với hình bình hành hoặc một trong các điểm nằm bên trong một tam giác được tạo thành bởi các tam giác khác. Bằng cách vẽ các đường thẳng trong mỗi trường hợp này, như trong Hình 8 và Hình 6, chúng ta thu được các cấu hình giống nhau. Do đó, chúng tôi đưa ra các ký hiệu mới (xem Hình 9, trong đó dữ liệu và các điểm được xây dựng không khác nhau).

Tuy nhiên, điều kiện của chúng tôi không tuân theo các đường thẳng $EF$ và $MN$ giao nhau: chúng cũng có thể song song. Khi nào điều này sẽ xảy ra?

Bài toán 8. Chứng minh rằng nếu $|MK| = |KN|$ thì $(MN) \parallel (EF)$.

Lời giải rất dễ có được nếu bạn nhớ lời giải bài toán 2.

Bài toán 9. Trong trường hợp $|MK| = 2|KN|$, dựng một đường thẳng song song với $(MN)$.

Lời giải. Đầu tiên chúng ta chứng minh rằng trong trường hợp của chúng ta $|MN| = |NL|$. Để làm được điều này, chúng ta sẽ phải áp dụng các định lý của Cheva và Menelaus (ví dụ, có thể đọc cách chứng minh của chúng trong «Kvant», 1976, số 11, trang 22). Định lý đầu tiên trong số này phát biểu rằng nếu các đỉnh của tam giác $EFK$ (Hình 9) lần lượt nằm trên các đường thẳng $MS, SN, NM$, thì

$$\frac{|MK|}{|KN|} \cdot \frac{|NF|}{|FS|} \cdot \frac{|SE|}{|EM|} = 1.$$ (1)

Điều thứ hai nói rằng nếu các điểm $E, F, L$ lần lượt nằm trên các đường $SM, SN, MN$ và nằm ở vị trí

⟦folio 29⟧

thì chúng ta nằm trên cùng một đường thẳng

$$\frac{|ML|}{|LN|} \cdot \frac{|NF|}{|FS|} \cdot \frac{|SE|}{|EM|} = 1.$$ (2)

So sánh các đẳng thức này, chúng ta thu được $|ML| = 2|NL|$, từ đó $|MN| = |NL|$. Và bây giờ, về cơ bản, việc xây dựng một đường song song có thể dễ dàng đạt được theo cách mà chúng ta đã biết (Hình 10).

Bài toán 10. Trong trường hợp $2|MK| = 3|KN|$, dựng đường thẳng song song với (MN).

Gợi ý. Hãy chỉ ra rằng $|MN| = 2|NL|$, (Hình 11) và áp dụng bài toán 9.

Bài toán 11. Vẽ đường thẳng song song với đường thẳng MN trong trường hợp tổng quát.

Lời giải được đề xuất cho chúng tôi bởi bài toán trước đó. Đặt $|MK|$: $|KN| = p:q$, trong đó $p > q$ (trường hợp $p < q$ là nhân chứng cho biến số điểm này). Chúng ta sẽ suy luận bằng quy nạp trên $l$. Cơ sở quy nạp, tức là trường hợp $l = 1$, đã được xử lý (bài toán 8). Giả sử rằng với $p, q \leq l$, chúng ta có thể dựng một đường thẳng song song với (MN) từ các điểm M, K, L. Bây giờ hãy đặt $|MK|:|KN| = (l + 1):q$. So sánh (1) và (2), ta thu được

$$\frac{|MN|}{|ML|} = \frac{l + 1 - q}{q}$$

và có thể sử dụng giả thuyết quy nạp, theo đó từ các điểm M, N, L dựng được đường thẳng song song với đường thẳng (MN).

Như vậy, ta đã chứng minh được định lý sau (và đã giải thành công bài toán M625):

Định lý. Tập hợp các điểm có thể được dựng bởi một thước duy nhất từ ​​bốn điểm hữu tỉ ở vị trí tổng quát bao gồm tất cả các điểm hữu tỉ của mặt phẳng.

Rõ ràng, việc tăng số lượng điểm hữu tỉ ban đầu không làm thay đổi tập hợp các điểm có thể xây dựng được.

Có lẽ, người đọc muốn biết những điểm nào có thể được xây dựng dựa trên bốn điểm ở vị trí tổng quát, không phải tất cả tọa độ của chúng đều hợp lý. Thật không may, để hình thành đáp số tốt và chính xác, cần phải liên quan đến các khái niệm từ hình học xạ ảnh. Tuy nhiên, bằng trực giác, rõ ràng là trong trường hợp này thu được một tập hợp các điểm rất “tương tự” với tập hợp tất cả các điểm hữu tỉ. Chính xác hơn, tập hợp này “tương đương về mặt xạ ảnh” với tập hợp các điểm hữu tỉ.

Bài tập

1. Dùng compa và thước kẻ, bắt đầu từ bốn điểm ở vị trí tổng quát, dựng một điểm không thể dựng được chỉ bằng thước (với compa cho phép dựng đường tròn $O(A, |AB|)$, trong đó $A, B$ là các điểm dựng; các điểm giao nhau của đường tròn dựng với đường thẳng dựng được coi là dựng nên).

2. Cho ba điểm O, A, B và hai đường thẳng song song l, m, với A, B ∈ l và O∉ l, O∉ m. Xây dựng bằng một thước kẻ

a) đường thẳng đi qua O song song với l;

b) Đường thẳng đi qua A song song với OB.

3*. Cho năm điểm (0,0), (1,0), (1,1), (0,2), ($\sqrt{3}$, 0). Những điểm nào có thể được xây dựng từ chúng bằng một thước kẻ?
