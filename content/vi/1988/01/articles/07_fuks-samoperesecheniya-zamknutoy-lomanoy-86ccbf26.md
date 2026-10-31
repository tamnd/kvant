---
id: 1988-1-fuks-samoperesecheniya-zamknutoy-lomanoy-86ccbf26
issue: kvant_1988_1
year: 1988
number: "1"
title: Tự giao nhau của một đa tuyến khép kín
authors:
  - Фукс Д. Б.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 32
page_last: 36
page_labels: 30, 31, 34
tag: 13Q4
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 55373a4aa098efbf201895d52f2278256893ae02bf9cdceeb66734746551f95d
prompt_sha256: draft-1
translated_from: content/ru/1988/01/articles/07_fuks-samoperesecheniya-zamknutoy-lomanoy-86ccbf26.md
source_content_sha256: b4403d5a42bed0719bd486844dfc50782fd9765e32ce5df888b165f38977ae2d
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 30⟧

lực lượng dẫn đường. Ước tính thời gian hình thành sao từ một đám mây bụi vũ trụ hình cầu khổng lồ với mật độ $Q = 2 \cdot 10^{-20} \text{ e/cm}^3$. Chúng ta có thể giả sử rằng khi lăn xuống, các hạt không bỏ qua nhau. Hằng số hấp dẫn $G = 6,67 \times 10^{-11} \text{ H} \cdot \text{m}^2/\text{кг}^2$.

Tôi. Sh. Slobodtsky và V. A. Orlov “Olympic Vật lý có trọng số”). Vì theo điều kiện bài toán, các hạt sẽ không đuổi kịp nhau nên tổng khối lượng hút hạt của chúng ta không đổi. Giả sử rằng toàn bộ khối lượng này tập trung ở trung tâm đám mây. thì bài toán sẽ quy về việc tìm thời điểm hạt rơi vào tâm hút.

Chúng ta sẽ coi chuyển động của một hạt về phía tâm là trường hợp giới hạn của chuyển động dọc theo một hình elip rất dài, giá trị lớn hơn của nó bằng $R/2$ và so sánh chuyển động này với sự chuyển động theo quỹ đạo tròn có bán kính $R$. Hãy sử dụng định luật thứ ba của Kepler:

$$\frac{T^2}{T^2} = \frac{R^3}{(R/2)^3},$$

trong đó $T_k$ là chu kỳ chuyển động theo quỹ đạo tròn, $T_s$ là chu kỳ chuyển động theo quỹ đạo hình elip. Chu kỳ $T_k$ có ​​thể dễ dàng tìm thấy bằng cách sử dụng định luật thứ hai của Newton và định luật vạn vật hấp dẫn:

$$\frac{mv^2}{R} = F_T = G \frac{mM}{R^2} = G \frac{mQ \cdot \frac{4}{3} \pi R^3}{R^2},$$

từ đâu $T_k = \frac{2\pi R}{v} = \sqrt{\frac{3\pi}{G\rho}}$, và

$$T_s = \frac{T_k}{2^{3/2}} = \sqrt{\frac{3\pi}{8G\rho}}.$$

Chúng tôi thấy rằng khoảng thời gian $T_s$ không phụ thuộc vào $R$. Do đó, thời gian của một hạt rơi vào tâm hút (thời gian quay của ngôi sao), bằng một nửa chu kỳ quay trong quỹ đạo hình elip, không phụ thuộc vào bán kính của đám mây bụi vũ trụ và bằng

$$\tau = \frac{T_s}{2} = \sqrt{\frac{3\pi}{32G\rho}} \approx 1,5 \cdot 10^{13} \text{ c} \approx 10^6 \text{ лет.}$$

V. E. Skorovarov

Tự giao nhau của một đa tuyến khép kín

Trong ghi chú này, chúng ta sẽ làm nổi bật lời giải bài toán M1064 và thảo luận kỹ hơn về bài toán.

M1064. Số lượng giao điểm tối đa mà một đa giác phẳng liên kết n khép kín có thể có là bao nhiêu nếu a) n lẻ: 6) n chẵn? (Giả định rằng không có ba đỉnh nào nằm trên cùng một đường thẳng và không có ba đường liên kết nào cắt nhau tại cùng một điểm.)

Đáp số: a) $n(n-3)/2$; b) $n(n-4)/2+1$.

Cần phải chứng minh rằng số nút giao đang được xem xét không thể vượt quá các giá trị đã chỉ định và đưa ra ví dụ về các đường đứt quãng mà các giá trị này đạt được.

Rõ ràng rằng hai mắt xích của một đường gãy cắt nhau nhiều nhất tại một điểm và các mắt xích liền kề không cắt nhau (nghĩa là chúng không có điểm chung ngoại trừ một đỉnh chung). Tổng cộng, một đường gãy n liên kết kín có $n(n-1)/2$ cặp liên kết, bao gồm n cặp liên kết liền kề. Do đó, tồn tại số lượng đường đứt đoạn khép kín có số giao điểm như vậy: chỉ cần tất cả n đường chéo được vẽ theo n-giác đều, cách xa tâm ít nhất là đủ (xem hình 1 với n=5 và n=7). Các liên kết này tạo thành một đường gãy n liên kết khép kín, tất cả đều không

⟦folio 31⟧

các liên kết liền kề giao nhau (tại các điểm khác nhau). Vấn đề a) đã được giải quyết.
Bây giờ hãy để $n$ chẵn. Phần bên trong các đỉnh của một đa tuyến liên kết $n$ cho trước trong một hàng, bắt đầu từ bất kỳ một hàng nào và biểu thị bằng $A$ tập hợp các đỉnh có bốn số và bằng $B$ tập hợp các đỉnh có bốn số. Bất kỳ liên kết nào của đường gãy đều đi từ một điểm nào đó trong tập hợp $A$ đến một điểm nào đó trong tập hợp $B$. Giả sử $l$ là một dòng chứa một liên kết nào đó. Nếu liên kết này cắt tất cả các liên kết không liền kề với nó, thì tất cả các đỉnh có bốn số nằm trên cùng một phía của $l$ (tất nhiên, chúng tôi không tính đến các đỉnh của liên kết được đề cập nằm trên $l$). Điều này có nghĩa là các tập $A$ và $B$ nằm đối diện nhau trên đường thẳng $l$ và đồng thời có một điểm chung với nó. Không có nhiều hơn hai dòng như vậy. Sự thật này đối với tôi có vẻ rất thú vị, nhưng đối với những người thích lý luận mang tính xây dựng, tôi sẽ đưa ra bằng chứng của nó (xem hình 2).

Cho có ba đường thẳng như vậy. Chính xác hơn, đặt $A_1, A_2, A_3 \in A$ và $B_1, B_2, B_3 \in B$ là các điểm sao cho các tập hợp $A$ và $B$ nằm đối diện nhau trên mỗi đường thẳng $A_1B_1, A_2B_2, A_3B_3$. Vì các điểm $A_2, B_2$ nằm trên các cạnh đối diện của đường thẳng $A_1B_1$ và các điểm $A_1, B_1$ nằm trên các cạnh đối diện của đường thẳng $A_2B_2$ nên các đoạn $A_1B_1$ và $A_2B_2$ cắt nhau; gọi $C$ là giao điểm.

Điểm $A_3$ nằm trên cùng một phía của đường thẳng $A_1B_1$ với điểm $A_2$ và nằm trên cùng một phía của đường thẳng $A_2B_2$ với điểm $A_1$; điều này có nghĩa là nó nằm trong góc $A_1CA_2$. Theo nguyên tắc tương tự, điểm $B_3$ nằm ở góc $B_1CB_2$. Điều này có nghĩa là đường $A_3B_3$ không cắt ít nhất một trong các đoạn $CA_1, CA_2$ và không cắt ít nhất một trong các đoạn $CB_1, CB_2$. Để nó không giao nhau $CA_i$ và $CB_j$ (trên hình đây là $CA_2$ và $CB_1$); thì điểm $A_i$ và $B_j$ nằm về một phía của nó, điều này mâu thuẫn với giả định.

Vì vậy, có nhiều nhất hai liên kết cắt nhau tất cả các liên kết không liền kề. Điều này có nghĩa là ít nhất $n-2$ liên kết không giao nhau với ít nhất một trong các liên kết không liền kề với chúng; do đó có ít nhất $(n-2)/2$ cặp liên kết rời nhau không liền kề và tổng số điểm tự giao không vượt quá $n/(n-3) - \frac{n-2}{2} = \frac{n(n-4)}{2} + 1$.

Tại bất kỳ thời điểm nào, vẫn còn một đường đứt liên kết $n$ với các giao lộ tự $n/(n-4)/2+1$.

Chúng ta hãy vẽ một $n$-giác thông thường tất cả các đường chéo gần tâm của nó nhưng không đi qua tâm. (Hơn nữa, $n/2$ chúng tạo thành một đường đứt nét khép kín; nếu $n/2$ là số lẻ, chúng tạo thành hai đường gãy khép kín, đối xứng với nhau so với tâm.) Mỗi ​​đường chéo này đều là các đường chéo không liền kề, ngoại trừ một đường chéo - song song với ei; điều này mang lại $n/(n-4)/2$ giao lộ. Hãy xóa hai đường chéo song song và nối các đầu của chúng theo chiều ngang. (Xem hình 3 để biết $n=6$ và $n=12$. Các đường liền mảnh là các đường chéo của một $n$-giác đều gần tâm nhất và không đi qua tâm. Các đường chấm là các đường chéo bị loại bỏ. Các đường liền nét dày là các đường chéo mà chúng thay thế. Các chấm liền và đường dày tạo thành đa giác của chúng ta.) Số giao điểm sẽ tăng thêm 1 và, rất dễ kiểm tra, $n$ của các đoạn được vẽ tạo thành một đường đứt nét khép kín. Vấn đề 6) đã được giải quyết.

Hãy cung cấp thêm một vài bài toán, có hình dạng tương tự như bài toán đã được tháo rời. Trước hết, chúng ta có thể xem xét loại đường gãy đang được xem xét, cho phép đường gãy được chia thành nhiều đường gãy khép kín. Để tạo cho nhiệm vụ một hình thức tự nhiên, chúng ta sẽ xây dựng nó như thế này. Có $n$ điểm cố định trên mặt phẳng, không có ba điểm nào thẳng hàng. Một số điểm này được kết nối bằng các đoạn, trong đó mỗi điểm được kết nối chính xác với hai điểm khác. Số có thể lớn nhất là bao nhiêu (Xem phần kết thúc ở trang 34)

⟦folio 34⟧

Tìm kiếm chương trình
(Để bắt đầu, xem trang 7)

bình phương với số lượng người giữ vé thường xuyên đã tính toán trước đó cho các giá trị nhỏ hơn của S. Điều này được thực hiện ở dòng 100. Cuối cùng, khi hoàn thành chu trình qua S (từ 0 đến 13), bạn cần nhân đôi số kết quả P và trừ đi 1.

Bài tập
23. Cần phải lấy bao nhiêu số hạng của tổng 1+2+3+... để có được một số có ba chữ số gồm các chữ số giống nhau?
24. Có bao nhiêu số nguyên từ 1 đến 1988 không chia hết cho bất kỳ số nào trong số 6, 10, 15?
25. Tìm số tự nhiên M nhỏ nhất sao cho tổng

bình phương của các số tự nhiên liên tiếp giống hệt nhau, bắt đầu bằng M, là một hình vuông hoàn hảo.

26. Có bao nhiêu cách đánh dấu đồng rúp bằng đồng xu (với mệnh giá 1, 2, 3, 5 kopecks)?

27. Trong dãy 19886138... mỗi chữ số, bắt đầu từ chữ số thứ năm, bằng chữ số cuối cùng của tổng các chữ số chẵn trước đó. Sau bao nhiêu chữ số thì tổ hợp ban đầu 1988 lại xuất hiện (hay nói cách khác là có bao nhiêu chữ số trong dấu chấm)?

28. Gọi X là tổng lập phương của mười số tự nhiên liên tiếp và Y là tổng của các số tự nhiên đó. Chứng minh rằng X² - ​​​​Y² chia hết cho 300.

29. a) Tính tỉ số nhỏ nhất của một số có ba chữ số với tổng các chữ số của nó. Giá trị nhỏ nhất (nhỏ nhất) này đạt được với những con số nào?

30. Tìm một số có bốn chữ số nhỏ hơn bốn lần số viết cùng các chữ số đó nhưng theo thứ tự ngược lại.
