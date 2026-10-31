---
id: 1970-8-resheniya-126212f9
issue: kvant_1970_8
year: 1970
number: "8"
title: '[Lời giải các bài toán M3—M5]'
rubric: zadachnik-kvanta
page_first: 44
page_last: 55
page_labels: 42-53
tag: YY42
lang: vi
source: kvant_digital
extraction: vision
content_sha256: b191bccab5b3d549029686cd698f46d1bbe651cbeb9f55efab70b3ed4124de5e
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1970/08/articles/14_resheniya-126212f9.md
source_content_sha256: 1e1c63e577b116e795ad261ce0f5085972efd2d8c0b4f2f1288fd1dbaa64d376
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-30
---

⟦folio 42⟧

M3. (a) Trên hình 1, a mặt phẳng được phủ bởi các hình vuông có năm màu. Tâm các hình vuông cùng màu nằm tại các đỉnh của một lưới vuông. Với số màu nào thì có thể phủ mặt phẳng tương tự?

(b) Trên hình 1, b mặt phẳng được phủ bởi các hình lục giác có bảy màu sao cho tâm các hình lục giác cùng màu tạo thành các đỉnh của một lưới gồm các tam giác đều bằng nhau. Với số màu nào thì có thể xây dựng tương tự?

Ghi chú. Trong bài thứ nhất, số màu có thể bằng một (mọi hình vuông cùng một màu) và bằng hai (như trên bàn cờ). Trong bài thứ hai, bạn dễ dàng tìm được các lời giải với một màu và với ba màu. Nên đưa ra lời giải đầy đủ cho các bài toán, tức là mô tả mọi cách tô màu thỏa mãn các điều kiện đã nêu. Tuy nhiên, cũng hãy gửi các lời giải chưa đầy đủ, nếu chúng có vẻ thú vị đối với bạn. Chẳng hạn, hãy suy nghĩ xem trong bài thứ hai có tồn tại lời giải với mười ba màu không?

Lời giải*)

Từ nay, ta chỉ coi là đúng cách phủ mặt phẳng bằng các hình vuông (hoặc hình lục giác) mà trong đó lưới ứng với một màu nào đó có cùng kích thước và hướng các cạnh của hình vuông (hoặc tam giác) như lưới ứng với bất kỳ màu nào khác. Nói cách khác, mọi lưới phải nhận được từ nhau bằng phép tịnh tiến song song. Dĩ nhiên, các lưới khác nhau không thể được tô cùng một màu. Lời giải của bài toán trong các trường hợp tổng quát (hình vuông và hình lục giác) là tương tự nhau, và ta sẽ xét cả hai trường hợp cùng lúc.

1. Trước hết, hãy chứng minh rằng nếu mặt phẳng được phủ theo cách đã nêu, thì số màu bằng $k^2 + l^2$ trong trường hợp hình vuông và bằng $k^2 + kl + l^2$ trong trường hợp hình lục giác, trong đó $k, l$ là các số nguyên không âm (nhưng không đồng thời bằng không)**).

*) Phần đầu lời giải của bài toán này xem trong «Kvant» số 7, tr. 54.
**) Còn có những công thức khác biểu diễn cùng những tập số đó, chẳng hạn $k^2 - kl + l^2$ đối với hình lục giác,

⟦folio 43⟧

Lấy khoảng cách giữa tâm của hai hình vuông hoặc hình lục giác kề nhau làm đơn vị độ dài.

Vẽ bằng các nét đen đậm lưới đi qua tâm các hình vuông hoặc hình lục giác cùng màu, chẳng hạn màu đỏ (hình 2, 3).

Trong trường hợp hình lục giác, ta chỉ vẽ các đường theo hai hướng, vì vậy lưới sẽ không gồm các tam giác đều mà gồm các hình thoi.

Giả sử $ABCD$ là một hình vuông hoặc một hình thoi của lưới. Hãy suy ra công thức diện tích của nó.

Trong trường hợp hình vuông, qua các điểm $A$ và $B$ vẽ các đường thẳng song song với các cạnh của những hình vuông đang phủ, và ký hiệu giao điểm của chúng là $M$. Các độ dài $AM=k$ và $BM=l$ là các số nguyên (một trong chúng có thể bằng không). Trên hình 1, $k=3$, $l=2$. Khi đó $AB=\sqrt{k^2+l^2}$, còn diện tích $ABCD$ bằng $k^2+l^2$.

Trong trường hợp hình thoi, qua các điểm $A$ và $B$ ta kẻ các đường thẳng song song với các đường cao của các lục giác, và gọi giao điểm của chúng là $M$. Góc $AMB$ có thể bằng $120^\circ$ hoặc $60^\circ$. Ta kẻ các đường thẳng sao cho nó bằng $120^\circ$. Độ dài $AM=k$ và $BM=l$ là các số nguyên (một trong chúng có thể bằng không). Trên hình 2, $k=1$, $l=2$. Khi đó $AB=\sqrt{k^2+kl+l^2}$, còn diện tích hình thoi bằng $\frac{\sqrt{3}}{2}(k^2+kl+l^2)$.

Ta sẽ chứng minh rằng số màu tham gia vào phép tô màu bằng tỉ số diện tích $ABCD$ với diện tích của một hình vuông bao quanh (trường hợp (a)) hoặc một lục giác (trường hợp (6)) và do đó bằng:

trong trường hợp các hình vuông $k^2+l^2$,

trong trường hợp các lục giác $k^2+kl+l^2$

(vì diện tích của một lục giác bằng $\frac{\sqrt{3}}{2}$).

Điều này lập tức suy ra từ bổ đề sau.

Bổ đề cơ bản. Phần $ABCD$, được tô bằng mỗi màu tham gia vào việc tô màu, hoặc là một hình vuông (trong trường hợp (a)), tương ứng là một lục giác (trong trường hợp (6)), hoặc gồm các mảnh (đối với màu đỏ — bốn mảnh, đối với các màu khác — hai mảnh), từ đó có thể ghép thành một hình vuông hoặc tương ứng là một lục giác như vậy.

Chứng minh bổ đề không khó, và chúng tôi đề nghị bạn tự thực hiện

⟦folio 44⟧

Hình 4. Mặt phẳng được lấp đầy bởi các hình giống nhau có diện tích 13 ô vuông. Hãy thử tìm một mảnh “cơ bản” của mặt phẳng được lấp đầy như vậy và ghép từ nó một hình xuyến, như chúng tôi đã làm với hình vuông.

Gợi ý. Cần chọn 13 hình, ghép từ chúng một đa giác không phải là hình vuông, nhưng vẫn dễ dàng ghép thành hình xuyến. Cần làm điều này với một tờ giấy kẻ ô.

Điều này một cách độc lập. Chỉ lưu ý rằng cách tô màu của mọi hình vuông (hình thoi) của lưới đậm là như nhau, nghĩa là nếu cắt hình vuông (hình thoi) $ABCD$ khỏi mặt phẳng và đặt nó, chẳng hạn, lên hình vuông (hình thoi) kề bên, thì phần $ABCD$ được tô bằng bất kỳ màu nào sẽ trùng khít chính xác với phần của hình vuông (hình thoi) kề bên được tô bằng cùng màu đó.

Có một cách khác để trình bày chứng minh này, đẹp hơn, nhưng đòi hỏi một chút công sức của trí tưởng tượng. Trước hết, chỉ xét trường hợp lưới vuông. Hãy cắt một hình vuông $ABCD$ khỏi mặt phẳng và ghép từ nó một ống — một hình trụ, với mặt được tô màu ở ngoài, bằng cách ghép các cạnh $AB$ và $DC$ lại với nhau. Ống này được giới hạn bởi hai đường tròn, tạo thành từ các cạnh $AB$ và $DC$. Hãy ghép các đường tròn này với nhau (cho điểm $A=D$ trùng với điểm $B=C$). Vì vậy sẽ phải ép bẹt ống giấy, nhưng dù sao chúng ta cũng sẽ coi toàn bộ bề mặt được tô màu của nó là một thể thống nhất, không bị chia thành các phần bởi các nếp gấp. Diện tích bề mặt của hình nhận được bằng $k^2+l^2$, còn phần của nó được tô bằng bất kỳ màu nào trong cách tô màu — là một hình vuông nhỏ kích thước $1 \times 1$. Chúng tôi khuyên bạn thực hành tất cả những điều này với một tờ giấy vuông, tô nó bằng năm hoặc nhiều màu hơn.

Trong trường hợp các lục giác, chúng ta sẽ đi đến kết quả tương tự nếu cũng ghép một hình chữ nhật theo cách ấy, có một cạnh chung với hình thoi $ABCD$, còn cạnh kia bằng chiều cao của hình thoi.

Có thể lát kín mặt phẳng bằng những hình bằng nhau khác, trong đó các phần diện tích tô bằng những màu khác nhau là bằng nhau. Chẳng hạn, trong lời giải bài toán (a), gửi từ Kiev (ngõ Belinsky 8, căn hộ 32, không ghi họ tên tác giả), người ta đề nghị lát kín mặt phẳng bằng các hình gồm hai hình vuông có cạnh $k$ và $l$. Ví dụ, với $k=2$ và $l=3$ (13 màu), hình sẽ như ở hình 4.

II. Bây giờ giả sử ta có số $m=k^2+l^2$ hoặc $n=k^2+kl+l^2$. Ta sẽ chứng minh rằng có thể lát kín mặt phẳng theo điều kiện bằng các hình vuông $m$ màu hoặc các hình lục giác $n$ màu.

Ta lát kín mặt phẳng bằng các hình vuông bằng nhau hoặc các hình lục giác đều và bắt đầu tô màu chúng như sau.

Ta tô đỏ một hình trong số đó. Từ nó, đếm $k$ hình vuông nhỏ (lục giác) theo một hướng, rồi quay $90^\circ$ đối với hình vuông và $60^\circ$ đối với hình lục giác, đếm $l$ hình vuông nhỏ (lục giác) theo hướng mới, và hình vuông nhỏ (lục giác) mà ta đến cũng tô đỏ. Trên đoạn nối tâm của hai hình vuông nhỏ (lục giác) đỏ, như trên một cạnh, dựng một hình vuông (a) hoặc một tam giác đều (6). Ghép thêm vào nó các hình vuông bằng nhau (tam giác đều), ta sẽ nhận được tâm của tất cả các hình vuông nhỏ (lục giác) cần tô đỏ; tịnh tiến song song toàn bộ tập hợp

⟦folio 45⟧

các hình vuông nhỏ (lục giác) đỏ, mỗi lần ta sẽ nhận được một tập hợp mới gồm các hình vuông nhỏ (lục giác) chưa tô màu và tô chúng bằng một màu mới, cho đến khi tô màu toàn bộ mặt phẳng. Theo điều đã chứng minh ở trên, số màu sẽ bằng $k^2+l^2$ trong trường hợp (a) và $k^2+kl+l^2$ trong trường hợp (б).

III. Vậy những số tự nhiên nào biểu diễn được dưới dạng $k^2+l^2$ hoặc $k^2+kl+l^2$? Để viết ra vài số đầu tiên như vậy, tiện nhất là lập hai bảng: bảng 1 — cho $k^2+l^2$, bảng 2 — cho $k^2+kl+l^2$.

Các số dưới đường chéo lặp lại những số đã viết, nên không cần viết chúng. Một số số xuất hiện trong bảng hai lần; các ô tương ứng được đánh dấu. Điều đó có nghĩa là với số màu như vậy có hai cách về bản chất khác nhau để lấp đầy mặt phẳng. Bây giờ dễ dàng viết ra các số này theo thứ tự tăng dần.

Bảng thứ nhất: 1, 2, 4, 5, 8, 9, 10, 13, 16, 17, 18, 20, 25, 26, ...
Bảng thứ hai: 1, 3, 4, 7, 9, 12, 13, 16, 19, 21, 25, 27, 28, ...

Giả sử ta đã viết ra các số này đến một chỗ nào đó và đang tìm số tiếp theo theo độ lớn.

Các đường đỏ vẽ trên bảng thứ nhất giúp làm điều đó. Để giải thích cách chúng được vẽ, hãy nhận xét rằng trong bảng thứ nhất mỗi số bằng bình phương khoảng cách từ tâm của ô chứa nó đến điểm 0 ở góc trên bên trái (lấy cạnh ô làm đơn vị độ dài). Vì vậy, nếu vẽ vài đường tròn tâm 0, thì chúng sẽ chia các số của ta (tức là tâm các ô chứa chúng) thành các nhóm theo thứ tự tăng dần. Nếu thử vẽ bằng tay những đường tương tự trong bảng thứ hai, có thể tưởng rằng chúng là những đường thẳng. Nhưng dĩ nhiên không phải vậy. Thực ra đó là các đồ thị tương ứng của dạng

$$k^2+kl+l^2=c=\text{const}$$

trong hệ tọa độ có gốc 0 và các trục đi theo hướng: trục $k$ — sang phải, trục $l$ — xuống dưới. Chuyển sang một cặp biến khác: $x=k+l$, $y=k-l$, có thể thấy rằng đó là các elip kéo dài theo hướng của trục $y^*$).

Theo một nghĩa nào đó, ta đã nhận được đáp án, nhưng có lẽ có thể đơn giản hóa nó. Chẳng hạn, nếu trong một bài toán nào khác ta nhận được đáp án: mọi số có dạng $k^2+l^2+m^2+n^2$, trong đó $k$, $l$, $m$, $n$ là số nguyên, thì có thể viết lại như sau: mọi số nguyên không âm, vì mọi số tự nhiên đều biểu diễn được dưới dạng đó. Có lẽ, cả dãy của chúng ta cũng

*) Những ai đã đọc cuốn sách của N. B. Vasiliev và V. L. Gutenmakher «Đường thẳng và đường cong», hẳn đã nhận thấy rằng các đường màu đỏ là các đường mức của các hàm $k^2+l^2$ và $k^2+kl+l^2$ trên mặt phẳng $(k, l)$.

⟦folio 46⟧

dãy này có chứa mọi số tự nhiên, kể từ một chỗ nào đó không? Để chứng minh rằng không phải như vậy, có thể dùng hệ các đường chấm.

Trong bảng thứ nhất, hãy vẽ một đường tròn đỏ tâm 0 bán kính $n$. Tâm của mọi ô chứa các số không lớn hơn $n^2$ nằm bên trong hoặc trên biên của một cung quạt của đường tròn này có góc ở tâm $45^\circ$. Vì thế mọi ô như vậy nằm bên trong hình thu được từ cung quạt này nếu thêm vào nó một dải viền rộng 1. Diện tích của hình này nhỏ hơn $\frac{\pi n^2}{8} + 3n + 4$.

Suy ra trong $n^2$ số tự nhiên đầu tiên có $\frac{\pi n^2}{8} + 3n + 4$ số biểu diễn được dưới dạng $k^2 + l^2$. Khi $n$ lớn, số thứ hai chiếm xấp xỉ $\frac{\pi}{8}$ số thứ nhất. Thực ra, vì một số số trong bảng bằng nhau, số các số dạng $k^2 + l^2$ còn ít hơn. Dễ thấy rằng tỉ lệ các số biểu diễn được dưới dạng $k^2 + kl + l^2$ còn nhỏ hơn nữa.

**M4.** Cho đoạn thẳng $AB$. Hãy tìm quỹ tích các điểm $C$ trên mặt phẳng sao cho trong tam giác $ABC$, đường trung tuyến kẻ từ đỉnh $A$ bằng đường cao kẻ từ đỉnh $B$.

Lời giải

Tòa soạn đã nhận được nhiều thư gửi lời giải bài toán này, nhưng hầu như tất cả đều không đầy đủ. Nhiều bạn đọc đã quên rằng khi tìm quỹ tích điểm (QTD) cần nhất thiết kiểm tra hai điều: 1) mọi điểm của tập hợp tìm được đều thỏa mãn điều kiện; 2) mọi điểm thỏa mãn điều kiện đều thuộc tập hợp tìm được. Nhiều người chính là đã không xét đến yêu cầu 1). Chúng tôi sẽ đưa ra hai lời giải: một lời giải hoàn toàn hình học, lời giải thứ hai dùng phương pháp tọa độ.

Lời giải thứ nhất. Bắt đầu từ 2). Cho đoạn thẳng $AB$ và giả sử $C$ là điểm thỏa mãn điều kiện, $AD$ là đường trung tuyến của tam giác $ABC$. Hoàn thành tam giác thành hình bình hành bằng cách kéo dài đường trung tuyến $AD$ đến điểm $E$ sao cho $AD=DE$. Ở đây có thể có hai trường hợp: góc $AEB$ nhọn hoặc tù.

(a) Giả sử góc $AEB$ nhọn (hình 5, a). Kẻ $BF \perp AC$, $AK \parallel BF$, khi đó trong tam giác vuông $AEK$ cạnh góc vuông $AK$ bằng một nửa cạnh huyền $AE$, vì vậy $\angle AEB=30^\circ$.

⟦folio 47⟧

(6) Giả sử góc AEB tù (hình 5, 6). Kẻ BF ⊥ AC, AK || BF, tương tự trường hợp (a), ta được ∠AEK=30°, vì vậy ∠AEB=150° (điểm khác với trường hợp (a) là bây giờ các điểm K và B nằm ở hai phía khác nhau của E).

Vậy, nếu C là điểm cần tìm, thì đoạn thẳng AB được nhìn từ điểm E dưới góc 30° hoặc 150°. Như đã biết, mọi điểm E như vậy nằm trên hai đường tròn O₁ và O₂, bị dây AB chia thành các cung 300° và 60° (hình 6, a), và do đó, mọi điểm C nằm trên các đường tròn O'₁ và O'₂ tương tự, nhận được từ O₁ và O₂ bằng phép tịnh tiến theo đoạn l=AB theo hướng từ B đến A (hình 6, 6).

Bây giờ ta chứng minh rằng mọi điểm M của các đường tròn O'₁ và O'₂ đều thuộc tập điểm cần tìm. Giả sử M là một điểm tùy ý của một trong các đường tròn này; khi đó, kẻ MK=AB, MK||AB, ta được điểm K trên một trong các đường tròn O₁ hoặc O₂ (hình 7, a, 6). Trên hình 7, a' $BF \perp MA$, $AL||BF$, $AL=BF$, khi đó (từ ΔAKL) $AL=1/2 AK$, tức là điểm M thỏa mãn các điều kiện. Tương tự, trên hình 7, 6 $BF \perp MA$, $AL=BF$, $AL||BF$, ∠AKB=150°, ∠AKL=180°−∠AKB=30°, tức là $AL=1/2 AK$, và điểm M cũng thỏa mãn các điều kiện. Vậy, mọi điểm của O'₁ và O'₂, trừ các điểm N và A, đều thỏa mãn các điều kiện.

Lưu ý rằng nhiều độc giả giải bài toán bằng hình học đã nhận được trong đáp số các phần của các đường tròn O'₁ và O'₂. (Chẳng hạn, hình 8, a là của V. Mashanov ở thành phố Grodno, hình 8, 6 là của S. Ivanenko ở thành phố Fedosia và hình 8, в là của A. Alyaev ở tỉnh Penza.) Lời giải đúng (tuy hơi khác với lời giải nêu ở đây) được L. Stolyarov ở thành phố Penza gửi đến.

Lời giải thứ hai. (Một sự đơn giản hóa nhỏ của lời giải do A. Grishkov ở thành phố Tomsk gửi đến.) Đưa vào hệ tọa độ vuông góc với gốc tại điểm A, giả sử điểm B có tọa độ (2; 0), còn điểm cần tìm C có tọa độ (x; y). Giả sử AF là trung tuyến trong tam giác ABC, BK ⊥ AC (hình 9). Dễ thấy rằng điểm F có tọa độ (x+2/2; y/2). Khi đó AF²=(x+2/2)²+y²/4. Theo điều kiện BK²=AF², vì vậy

⟦folio 48⟧

Hình 8, a. Hình 8, b. Hình 8, c.

từ sự đồng dạng của các tam giác АКВ và АCD suy ra rằng $\frac{BK^2}{AK^2} = \frac{CD^2}{AD^2}$ hoặc
$$\frac{\left(\frac{x+2}{2}\right)^2 + \frac{y^2}{4}}{4 - \left[\left(\frac{x+2}{2}\right)^2 + \frac{y^2}{4}\right]} = \frac{y^2}{x^2}.$$

Biến đổi (1), ta được
$$y^4 + (2x^2 + 4x - 12)y^2 + (2x + x^2)^2 = 0.$$

Đó chính là phương trình liên hệ các tọa độ của những điểm cần tìm. Một số độc giả viết tiếp rằng nó xác định một đường cong bậc bốn, khá khó vẽ.

Thực ra, vế trái của phương trình (2) phân tích được thành nhân tử:
$$[(x+1)^2 + (y+\sqrt{3})^2 - 4] [(x+1)^2 + (y-\sqrt{3})^2 - 4] = 0.$$

Hình 9. Hình 10.

⟦folio 49⟧

Có thể đoán ra điều này, chẳng hạn, như sau.

Đặt: $y^2 = z$. Khi đó (2) là phương trình bậc hai đối với $z$. Phân tích vế trái của nó thành nhân tử. Để làm điều đó, ta tìm các nghiệm của (2).

$$z_{1,2} = \frac{12 - 2x^2 - 4x \pm \sqrt{(12 - 2x^2 - 4x)^2 - 4(2x + x^2)^2}}{2} =$$

$$= \frac{12 - 2x^2 - 4x \pm \sqrt{48(3 - x^2 - 2x)}}{2} = 6 - x^2 - 2x \pm 2\sqrt{3(3 - x^2 - 2x)} =$$

$$= (\sqrt{3 - x^2 - 2x} \pm \sqrt{3})^2.$$

Phương trình (2) bây giờ có thể viết dưới dạng:

$$\left| z - (\sqrt{3 - x^2 - 2x} + \sqrt{3}) \right| \left| z - \sqrt{3 - x^2 - 2x} - \sqrt{3} \right|^2 = 0$$

hoặc

$$\left| y^2 - (\sqrt{4 - (x + 1)^2} + \sqrt{3}) \right| \left| y^2 - (\sqrt{4 - (x + 1)^2} - \sqrt{3}) \right|^2 = 0.$$

(xem hình 10, trong đó một trong các tập hợp này là màu đỏ, còn tập hợp kia là màu xanh lá).

Biến đổi tiếp (4):

$$\left| y - \sqrt{4 - (x + 1)^2} + \sqrt{3} \right| \left| y + \sqrt{4 - (x + 1)^2} - \sqrt{3} \right| [\dots] [\dots] = 0;$$

từ đó suy ra (3)*.

Học sinh lớp chín P. Kriksunov ở Kiev và một số độc giả khác đã gửi cho chúng tôi lời giải của bài toán này nhận thấy rằng, tương tự, có thể giải bài toán tổng quát hơn sau: tìm tập hợp các điểm $C$ sao cho trong tam giác $ABC$ tỉ số của trung tuyến $AD$ với đường cao $BF$ bằng số cho trước $k$ (có thể dùng một trong hai cách giải đã mô tả ở trên).

M5. Trong tập hợp $E$ gồm $n$ phần tử, có $m$ tập con khác nhau (khác chính $E$) được chọn sao cho với mỗi hai phần tử của $E$ tồn tại đúng một trong các tập con đã cho chứa cả hai phần tử ấy.

Chứng minh rằng $m \geq n$. Trong những trường hợp nào điều đó có thể xảy ra?

Lời giải

Qua thư bạn đọc có thể thấy rằng bài toán này cực kỳ khó, nhưng thú vị. Thực ra, ở đây ta có hai bài toán: 1) chứng minh rằng $m \geq n$, 2) trong những trường hợp nào lời giải là có thể?

Về bài toán thứ nhất, chỉ có $A$. Существ ở thành phố Leningrad giải hoàn toàn. Chứng minh của ông dựa trên một trong những định lý cơ bản của đại số tuyến tính, khẳng định rằng nếu số $n$-vectơ nhiều hơn $n$, thì chúng phụ thuộc tuyến tính.

Đối với những ai quen với các khái niệm này, sẽ thú vị khi nghĩ ra một chứng minh như vậy. Về bài toán thứ hai, nó được chỉ ra, và điều đó cũng không đáng ngạc nhiên, vì dưới đây sẽ chỉ ra rằng nó quy về một bài toán toán học nổi tiếng, nhưng chưa được giải quyết.

Để tiện trình bày, một số bạn đọc đã đề nghị những cách phát biểu khác của bài toán. Đây là hai trong số đó.

*) Phương trình $(x - a)^2 + (y - b)^2 = c^2$ xác định một đường tròn tâm tại điểm $(a; b)$ bán kính $c$ (xem, chẳng hạn, И. М. Гельфанд, Е. Г. Глаголева, А. А. Кирр и лов, Phương pháp tọa độ, “Наука”, 1968).

⟦folio 50⟧

Hình 11.

a) Học sinh của một trường thường tụ tập thành nhóm và đi ăn kem. Sau một lần như vậy, họ cãi nhau đến mức không có hai người nào trong số họ còn ăn kem cùng nhau. Cuối năm, người ta thấy rằng về sau họ chỉ có thể đi đến quán cà phê-kem từng người một. Chứng minh rằng nếu số lần đã đi đến thời điểm đó lớn hơn 1, thì nó không nhỏ hơn số học sinh trong trường.

6) Cho $n$ điểm. Qua mỗi hai điểm đã kẻ đúng một đường thẳng, và trên mỗi đường thẳng có không quá $(n-1)$ điểm. Cần chứng minh rằng số đường thẳng không nhỏ hơn $n$.

Những bài toán này có tương đương với bài toán ban đầu không?

Dù sao, khi suy nghĩ về bài toán này, tiện nhất là hình dung các phần tử là “điểm”, còn các tập con là “đường”, sự đi qua các điểm này, và tự vẽ những hình kiểu như các hình 11 và 12 của chúng tôi. (Nói chung, không thể làm cho tất cả các đường đều là đường thẳng; như bài toán M36 cho thấy, không thể sửa hình 12 để cả đường màu đỏ cũng là đường thẳng, vì vậy bài toán 6) không tương đương với bài toán ban đầu.)

Tiếp theo, chúng tôi trình bày lời giải của bài toán, theo chỉ dẫn của chính tác giả bài toán N. Bourbaki*), và cũng để tiện lợi, chép lại các điều kiện của bài toán.

Cho $n$ phần tử khác nhau và có một hệ gồm $m$ tập hợp, tạo thành từ các phần tử này, sao cho:

1) không tập hợp nào của hệ chúng ta chứa đồng thời tất cả các phần tử;
2) mỗi hai trong số $n$ phần tử đã cho cùng xuất hiện trong một trong các tập hợp của hệ;
3) nếu hai phần tử cùng xuất hiện trong một tập hợp, thì chúng không cùng xuất hiện trong bất kỳ tập hợp nào khác của hệ.

Chứng minh rằng $m \geq n$.

Hãy đưa ra một ví dụ về cách bố trí các phần tử như vậy. Giả sử $n=5$ và có các phần tử: $a, b, c, d, e$. Lập một hệ tập hợp gồm các phần tử này;

$(a, b), (a, c, e,), (b, e), (b, c), (b, d), (a, d), (d, e), (c, d)$.

Rõ ràng, hệ này thỏa mãn các điều kiện 1), 2), 3). Ở đây $m=8$, và nhân tiện $8 \geq 5$.

Để chứng minh được trực quan hơn, đôi khi ta sẽ viện dẫn ví dụ này.

Chứng minh. Nhận thấy rằng $n>2$ và chỉ cần chứng minh bất đẳng thức $m \geq n$ đối với một hệ tập hợp chứa không ít hơn hai phần tử.

1. Hệ gồm không ít hơn hai tập hợp, vì theo điều kiện 2) tập hợp đó sẽ phải chứa ngay tất cả các phần tử, điều này trái với điều kiện 1).

*) Xem N. Bourbaki, Lý thuyết tập hợp, “Mir”, M., 1965, tr. 220.

⟦folio 51⟧

2. Mỗi phần tử thuộc vào không ít hơn hai tập hợp của hệ. Nếu một phần tử chỉ thuộc vào một tập hợp, thì theo 2) tập hợp đó phải chứa tất cả $n$ phần tử, điều này trái với 1).

3. Một phần tử không thể đồng thời thuộc vào tất cả các tập hợp của hệ. Giả sử một phần tử nào đó, gọi nó là $x$, thuộc vào mọi tập hợp của hệ. Khi đó theo điều kiện 3) không có hai tập hợp nào chứa các phần tử giống nhau, trừ phần tử $x$. Do đó, không có hai phần tử nào khác $x$ cùng xuất hiện trong bất kỳ tập hợp nào, nhưng điều này trái với 2).

4. Gán cho mỗi phần tử số lượng tập hợp của hệ mà nó thuộc vào, tức là đếm xem nó lặp lại bao nhiêu lần trong hệ này. Trong ví dụ, phần tử $a$ được gán số 3, phần tử $b$ — 4, v.v.

Gán cho mỗi tập hợp của hệ số lượng phần tử mà nó chứa. Trong ví dụ, tập hợp thứ nhất được gán số 2, tập hợp thứ hai — 3, v.v.

Tổng của tất cả các số tương ứng với các phần tử bằng tổng của tất cả các số tương ứng với các tập hợp. Trong ví dụ $3+4+3+4=2+3+2+2+2+2+2+2=17$.

Thật vậy, nếu coi hai phần tử là khác nhau khi chúng thuộc vào các tập hợp khác nhau, thì cả hai tổng đều bằng số phần tử của tất cả các tập hợp trong hệ.

5. Ký hiệu. Lấy một trong những phần tử thuộc vào số ít nhất các tập hợp của hệ. Trong ví dụ có thể lấy $a$, hoặc $c$, hoặc $e$; lấy $a$. Ký hiệu phần tử này là $a_n$, còn số của tập hợp mà nó thuộc vào là $k_n$. Trong ví dụ $a_5=a$, $k_5=3$. Theo các mục 2 và 3, có $2 \leqslant k_n < m$.

Các tập hợp chứa $a_n$ được ký hiệu theo một thứ tự nào đó là $A_1$, $A_2$, ..., $A_{k_n}$, còn các tập hợp còn lại là $A_{k_n+1}$, ..., $A_m$. Trong ví dụ, $A_1=(a, b)$, $A_2=(a, c, e)$, $A_3=(a, d)$, $A_4=(b, e)$, ..., $A_8=(c, d)$.

Xét $k_n$ tập hợp đầu tiên $A_1$, $A_2$, ..., $A_{k_n}$. Lập luận như ở mục 3, ta thấy rằng không có hai tập hợp nào trong số chúng chứa các phần tử giống nhau, ngoại trừ $\dot{a}_n$. Do đó, ta có thể lấy một phần tử từ mỗi tập hợp này và ký hiệu chúng tương ứng là $a_1$, $a_2$, ..., $a_{k_n}$. Các phần tử còn lại được ký hiệu theo một thứ tự nào đó là $a_{k_n+1}$, $a_{k_n+2}$, ..., $a_n$. Trong ví dụ, $a_1=b$, $a_2=c$, $a_3=d$, $a_4=e$; khi đó $A_1=(a_1, a_5)$, $A_2=(a_2, a_4, a_5)$, $A_3=(a_3, a_5)$, $A_4=(a_1, a_4)$, $A_5=(a_1, a_2)$, $A_6=(a_1, a_3)$, $A_7=(a_3, a_4)$, $A_8=(a_2, a_3)$.

Bây giờ, hãy ký hiệu các số tương ứng với các phần tử $a_1$, $a_2$, ..., $a_{k_n}$, ..., $a_{n-1}$ theo cùng thứ tự là $k_1$, $k_2$, ..., $k_{n-1}$. Chẳng hạn, phần tử $a_n$ tương ứng với số $k_n$, hơn nữa nó là nhỏ nhất trong tất cả các số $k_1$, $k_2$, ..., $k_{n-1}$, $k_n$.

Cuối cùng, ký hiệu các số tương ứng với các tập hợp $A_1$, $A_2$, ..., $A_m$ theo cùng thứ tự là $s_1$, $s_2$, ..., $s_{k_n}$, ..., $s_m$.

Hãy một lần nữa chú ý đến cách chúng ta đã đánh số các phần tử và các tập hợp.

Thứ nhất, $k_n$ là số nhỏ nhất trong các số $k_1, k_2, ..., k_{n-1}$.

Thứ hai, $k_n$ là số thứ tự của tập hợp cuối cùng mà phần tử $a_n$ thuộc vào, và do đó phần tử $a_n$ không thuộc các tập hợp $A_{k_n+1}$, ..., $A_m$.

Tập hợp $A_i$ chứa phần tử $a_i$, nhưng không chứa các phần tử $a_j$, nếu $1 \leqslant i \leqslant k_n$, $1 \leqslant j \leqslant k_n$ và $i \neq j$. Ngoài ra, theo mục 4, $k_1 + \dots + k_n = s_1 + \dots + s_m$.

⟦folio 52⟧

6. Nếu phần tử $a_i$ không thuộc một tập hợp nào đó $A_j$, thì $k_i \geqslant s_j$. Thật vậy, giả sử tập hợp $A_j$ không chứa phần tử $a_i$ và gồm $s_j$ phần tử khác nhau. Khi đó phần tử $a_i$ phải cùng xuất hiện với mỗi phần tử trong số đó ở một tập hợp nào đó khác của hệ. Mặt khác, không có hai phần tử nào trong số đó có thể cùng xuất hiện dù chỉ một lần trong các tập hợp này, vì chúng đã cùng xuất hiện trong $A_j$. Do đó, số tập hợp không chứa phần tử $a_i$ không nhỏ hơn $s_j$.

7. Xét $k_n$ tập hợp đầu tiên $A_1, A_2, \dots, A_{k_n}$ và $k_n$ phần tử đầu tiên $a_1, a_2, \dots, a_{k_n}$. Chúng được chọn sao cho mỗi tập hợp $A_i$ chứa phần tử $a_i$ có cùng số thứ tự, nhưng không chứa các phần tử có số thứ tự khác, khi đó, theo mục 6, $s_1 \leqslant k_2, s_2 \leqslant k_1$, nếu $k_n = 2$ và

$$\begin{align*}
s_1 &\leqslant k_2, \quad s_2 \leqslant k_1, \quad \dots, s_{k_n} \leqslant k_1, \\
s_1 &\leqslant k_{k_n}, \quad s_2 \leqslant k_{k_n}, \quad \dots, s_{k_n} \leqslant k_{k_n-1},
\end{align*}$$

nếu $k_n > 2$.

Trong ví dụ, $k_n = 3$ và

$$\begin{align*}
2 &= s_1 \leqslant k_2 = 3, \quad 3 &= s_2 \leqslant k_1 = 4, \quad 3 &= s_3 \leqslant k_1 = 4, \\
2 &= s_1 \leqslant k_3 = 4, \quad 3 &= s_2 \leqslant k_3 = 4, \quad 3 &= s_3 \leqslant k_2 = 3.
\end{align*}$$

8. Cộng tất cả các bất đẳng thức, ta được

$$(k_n - 1)(s_1 + s_2 + \dots + s_{k_n}) \leqslant (k_n - 1)(k_1 + \dots + k_{k_n})$$

hoặc

$$s_1 + s_2 + \dots + s_{k_n} \leqslant k_1 + \dots + k_{n}.$$

9. Bây giờ ta có thể chứng minh bất đẳng thức $m \geqslant n$ cần có trong bài toán. Giả sử rằng $m < n$. So sánh hai tổng

$$S = (s_1 + s_2 + \dots + s_{k_n}) + s_{k_n+1} + \dots + s_m$$

và

$$K = (k_1 + k_2 + \dots + k_n) + k_{k_n+1} + \dots + k_n.$$

Lưu ý rằng ta đã đánh số lại tập hợp sao cho phần tử $a_n$ không thuộc các tập hợp $A_{k_n+1}, \dots, A_m$; do đó, $s_{k_n+1} \leqslant k_n, \dots, s_m \leqslant k_n$ và càng có $s_{k_n+1} \leqslant k_{k_n+1}, \dots, s_m \leqslant k_m$, vì $k_n$ là nhỏ nhất trong tất cả các số $k_i$. Trong trường hợp đó, vì $m < n$, ta được: $k_{k_n+1} + \dots + k_n > s_{k_n+1} + \dots + s_m$, nhưng khi đó $S < K$, điều này mâu thuẫn với mục 4.

Chứng minh rằng $m \geqslant n$ đã hoàn tất.

10. Hãy thử выяснить trong những trường hợp nào có thể xảy ra đẳng thức. Nếu $m = n$, thì từ các mục 8, 9 và 4 suy ra:

$$k_1 + \dots + k_{k_n} + \dots + k_n = s_1 + \dots + s_{k_n} + \dots + s_n.$$

Hiển nhiên, để điều này xảy ra, cần có đẳng thức

$$k_1 + \dots + k_{k_n} = s_1 + \dots + s_{k_n}$$

và mọi bất đẳng thức ở mục 8 đều trở thành đẳng thức. Vì $k_n$ là số nhỏ nhất trong các số $k_i$, ta có

$$s_{k_n+1} = \dots = s_n = k_{k_n+1} + \dots + k_n.$$

Tiếp theo xét hai trường hợp.

(a) $k_n = 2$. Trong trường hợp này, dễ thấy có thể có một hệ các tập hợp như sau (hình 9): $(a_n, a_1), (a_n, a_2, a_3, \dots, a_{n-1}), (a_1, a_2), (a_1, a_3), \dots, (a_1, a_{n-1})$. Với mọi $n$, nó thỏa mãn các điều kiện của bài toán.

(b) $k_n > 2$. Trong trường hợp này, ta được rằng mọi bất đẳng thức ở mục 7 đều phải trở

⟦folio 53⟧

thành đẳng thức. So sánh tất cả các đẳng thức này, ta được rằng $s_1=s_2=\dots=s_{k_n}=k_1=k_2=\dots=k_{k_n}$.

Và cũng như trong trường hợp (a): $s_{k_n+1}=\dots=s_n=k_{k_n+1}=\dots=k_{n-1}=k_n$.
Hiển nhiên, một trong các số $s_1, s_2, \dots, s_{k_n}$ không lớn hơn một trong các số $k_{k_n+1},\dots,k_{n-1}$ và do đó $s_1=s_2=\dots=s_n=k_1=k_2=\dots=k_n=l>2$.

Cuối cùng ta được rằng trong trường hợp này có điều kiện sau:

4) tập hợp nào chứa đúng $l$ phần tử khác nhau và phần tử nào thuộc đúng $l$ tập hợp khác nhau.

Để điều đó xảy ra, cần có $n=l(l-1)+1$. Thật vậy, xét một phần tử nào đó $x$. Nó phải thuộc đúng $l$ tập hợp, do đó tất cả các tập hợp này phải chứa toàn bộ $n$ phần tử, vì $x$ phải gặp mọi phần tử. Ngoài ra, chúng không thể chứa các phần tử giống nhau, vì tất cả chúng đều chứa phần tử $x$. Từ đó ta nhận được đẳng thức cần tìm.

Với $l=3$, tức là $n=7$, dễ dàng xây dựng hệ tập hợp cần thiết (hình 10). Nhưng câu hỏi về việc với những $n$ dạng $l^2-l+1$ nào thì một tập hợp gồm $n$ phần tử có một hệ các tập con thỏa mãn các điều kiện 1), 2), 3) và 4), hóa ra rất phức tạp.

Một hệ như vậy có tên gọi riêng: mặt phẳng xạ ảnh hữu hạn cấp $l-1$. (Ở hình 12 biểu diễn mặt phẳng xạ ảnh cấp 2, gồm 7 điểm và 7 đường thẳng.) Dễ chứng minh rằng với mọi mặt phẳng xạ ảnh hữu hạn còn có tính chất sau, “đối ngẫu” với tính chất 2):

5) Bất kỳ hai tập hợp nào trong hệ của chúng ta đều có một phần tử chung (hiển nhiên, chỉ một); nói cách khác, bất kỳ hai đường thẳng nào cũng cắt nhau tại một điểm.

Ta sẽ chỉ ra cách xây dựng một mặt phẳng xạ ảnh hữu hạn cấp $p$ (với $n=p^2-p+1$), trong đó $p$ là số nguyên tố. Để làm điều này cần dùng các «số» của số học $p$ (xem bài «Các đồng dư theo môđun và số học các số dư», «Kvant» số 5, tr. 27—33) — số học các số dư theo môđun $p$. Trong số học như vậy, nếu $p$ là số nguyên tố, có thể chia bất kỳ «số» nào cho bất kỳ số nào khác không. Ta gọi một bộ ba «số» $(x_1, x_2, x_3)$, được xét đến tính tỉ lệ (nghĩa là các bộ ba $(x_1, x_2, x_3)$ và $(kx_1, kx_2, kx_3)$ xác định cùng một điểm), là một điểm. Ta quy ước không coi bộ ba $(0, 0, 0)$ là một điểm.

Một đường thẳng được cho bởi một bộ ba số $(a_1, a_2, a_3)$ (trừ bộ ba $(0, 0, 0)$), được xét đến tính tỉ lệ. Điểm $(x_1, x_2, x_3)$ thuộc đường thẳng $(a_1, a_2, a_3)$ khi và chỉ khi $a_1x_1+a_2x_2+a_3x_3=0$.

Hãy kiểm tra rằng đối với các đường thẳng và điểm được xác định như vậy, mọi điều kiện 1)—5) đều được thỏa mãn. Hãy убедиться rằng với $p=2$ ta thu được đúng ví dụ về mặt phẳng xạ ảnh cấp 2 được mô tả ở hình 12.

Tương tự, có thể chứng minh rằng tồn tại mặt phẳng xạ ảnh cấp $p^k$, trong đó $p$ là số nguyên tố, còn $k$ là một số tự nhiên bất kỳ. Đã chứng minh rằng không tồn tại các mặt phẳng xạ ảnh cấp $N$ đối với vô hạn nhiều giá trị $N$ (đặc biệt, với $N=6$, $N=14$). Nhưng ngay cả với $N=10$ cũng chưa biết mặt phẳng xạ ảnh cấp $N$ có tồn tại hay không: không một máy tính nào có thể đơn giản liệt kê hết mọi tổ hợp có thể.

Có thể đọc về lý thuyết các mặt phẳng xạ ảnh hữu hạn và các bài toán tổ hợp liên quan đến chúng trong sách của G. J. Ryser “Toán học tổ hợp” (“Mir”, 1966, bộ “Thư viện tuyển tập ‘Matematika’”).

A. Toom, J. Rabbot, V. Gutenacher
