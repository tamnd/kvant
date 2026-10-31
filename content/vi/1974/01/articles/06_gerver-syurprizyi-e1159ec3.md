---
id: 1974-1-gerver-syurprizyi-e1159ec3
issue: kvant_1974_1
year: 1974
number: "1"
title: bất ngờ
authors:
  - Гервер М. Л.
rubric: osnovnye-stati
page_first: 15
page_last: 23
page_labels: 13-21
tag: 7T9S
lang: vi
source: kvant_digital
extraction: vision
content_sha256: f403726d24def901e8adb9654bb81d0688741360604d030cdd9dbeb5a29e56e2
prompt_sha256: draft-1
translated_from: content/ru/1974/01/articles/06_gerver-syurprizyi-e1159ec3.md
source_content_sha256: 619229a4fbdc009ce5b0e0e569e6b5fe8a3aed8a8895f4752cf3416729116248
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 13⟧

Một vài lời về tên.
Đầu tiên chúng ta sẽ phân tích bài toán M195 từ Sách Vấn đề Lượng tử. Người ta sẽ thấy rằng nó có liên quan chặt chẽ với một cách xây dựng cổ điển của các vòng tròn hình học. Sau đó, những kết nối và sự kiện bất ngờ khác sẽ xuất hiện.
Điều quan trọng nhất là xin lỗi... Nhưng, suỵt! Nếu không thì sẽ phải hối tiếc như thế nào?

§ 1. Bài toán về ba hình tứ giác
M195. Dân $\Delta ABC$. Có bao nhiêu điểm $D$ sao cho chu vi của các tứ giác ADBC, ABDC và ABCD bằng nhau*)?

Lời giải. Hãy dựng ba vòng tròn ($\alpha$, $\beta$ và $\gamma$) với tâm $A$, $B$ và $C$, tiếp xúc với nhau từ bên ngoài theo cặp (Hình 1).

*) Chỉ có điểm $D$ được coi là nằm trong mặt phẳng $\Delta ABC$.

Bán kính của các đường tròn $a, b$ và $c$ này được xác định từ hệ phương trình
$$a + b = AB, a + c = AC, b + c = BC.$$
Như vậy,
$$a = p - BC, b = p - AC, c = p - AB,$$
trong đó $p$ là nửa chu vi $\Delta ABC$.

Đặt $D$ là tâm của đường tròn $\delta$, tiếp xúc bên ngoài các đường tròn $\alpha$, $\beta$ và $\gamma$. Bán kính $\delta$ được ký hiệu là $d$.

Chúng ta giả định rằng vòng tròn $\delta$ tồn tại. Việc xây dựng một đường tròn như vậy chính là nội dung ý nghĩa nhiệm vụ của Apollonius*), được Apollonius xứ Perga giải vào thế kỷ thứ 3 trước Công nguyên. đ.

Từ Hình 1, có thể thấy ngay rằng mỗi hình tứ giác ADBC, ABDC và ABCD đều có chu vi $2(p+d)=2(a+b+c+d)$. Do đó, mặc dù tồn tại một điểm Izsky $D$.

Có thể có nhiều hơn một điểm như vậy? Chuyển sang lời giải của câu hỏi này, trước hết chúng ta sẽ đảm bảo rằng nếu các chu vi ADBC, ABDC và ABCD bằng nhau thì điểm $D$ nằm bên ngoài các vòng tròn $\alpha$, $\beta$ và $\gamma$ và điều đó làm cho chúng bằng nhau. Hãy đặt $AD=x, BD=y, CD=z$. thì sự bằng nhau về chu vi của các tứ giác đang xét sẽ được viết như sau:
$$2p - AB + x + y = 2p - AC + x + z = 2p - BC + y + z.$$ (2)

Trừ đẳng thức (2) theo số hạng cho số $p+x+y+z$, ta được
$$z - (p - AB) = y - (p - AC) = x - (p - BC).$$

*) Tôi đã nói về điều này bài toán trong bài viết của Savin A.P., Đảo ngược và bài toán Apollonius. «Kvant», 1971, số 8.

⟦folio 14⟧

Sử dụng công thức (1), chúng tôi tìm thấy
$$z-c=y-b=x-a.$$

Theo (3) thì các số $x-a, y-b$ và $z-c$ cùng dấu. Hơn nữa, $x-a>0$, nếu điểm $D$ nằm bên ngoài $\alpha$ và $x-a\leq 0$, nếu $D$ nằm bên trong hoặc trên $\alpha$; các dấu hiệu $y-b$ và $z-c$ có ý nghĩa tương tự nhau. Vì không có điểm nào ngay lập tức thuộc về tất cả các đường tròn được giới hạn bởi các đường tròn $\alpha$, $\beta$ và $\gamma$, nên nó tuân theo
$$x-a=y-b=z-c\leq 0$$
sẽ bị loại trừ. Có nghĩa,
$$x-a=y-b=z-c>0,$$
$D$ nằm ngoài $\alpha$, $\beta$ và $\gamma$ và bằng chúng.

Hoạt động trên điều này, chúng tôi sẽ chứng minh điểm duy nhất $D$.

Đặt (để định nghĩa) $\alpha$ là nhỏ nhất trong các vòng tròn $\alpha$, $\beta$ và $\gamma$:
$$a\leq b, a\leq c.$$ Sử dụng bán kính $b-a$ và $c-a$, chúng tôi mô tả các vòng tròn $\beta'$ và $\gamma'$ có tâm $B$ và $C$. Điểm $D$ nằm bên ngoài $\alpha$, $\beta$ và $\gamma$ và bằng chúng, cũng bằng điểm $A$ và đường tròn $\beta'$ và $\gamma'$ (Hình 2). Chúng ta hãy dựng thêm ba vòng tròn nữa ($\alpha''$, $\beta''$ và $\gamma''$) với tâm $A$, $B$ và $C$ và bán kính $AD$, $BD$ và $CD$. Cho $T$ là một điểm tùy ý nằm bên trong $\alpha''$ hoặc trên $\alpha''$ và khác với $D$. Sau đó (Hình 2) $T$ nằm bên ngoài $\beta''$ hoặc bên ngoài $\gamma''$ hoặc bên ngoài cả hai vòng tròn này. Do đó, $T$ nằm gần $A$ hơn là với một trong các vòng tròn $\beta'$ hoặc $\gamma'$.

Lý do cuối cùng cho thấy hai điểm phân biệt $D_1$ và $D_2$ không thể cách đều $A$, $\beta'$ và $\gamma'$: giả sử ngược lại (trống $D_1$ và $D_2$ là các điểm như vậy và $AD_1\geq AD_2$) và ký hiệu $D_1$ bằng $D$, $a$ $D_2$ đến $T$, chúng tôi ngay lập tức phản đối.

Điểm duy nhất $D$ đã được chứng minh.

§ 2. Kép ​​bài toán

Trong § 1 tôi đã phát hiện ra mối liên hệ kỹ thuật giữa bài toán ba hình tứ giác và bài toán Apollo. Công thức sau (“Xây dựng một đường tròn tiếp xúc với ba đường tròn đã cho”) không cho biết tiếp tuyến là bên ngoài hay bên trong. Trong § 1, vòng tròn $\delta$ chạm vào $\alpha$, $\beta$ và $\gamma$ từ bên ngoài. Chúng ta hãy biểu thị bằng $\epsilon$ vòng tròn mà cả ba vòng tròn $\alpha$, $\beta$ và $\gamma$ chạm vào từ bên trong; chúng tôi gọi tâm của nó là $E$ (Hình 3).

Anh ta hỏi: không phải việc tìm ra điểm $E$ là nghiệm của một số bài toán, hoặc bài toán, về ba hình tứ giác sao? (Tất nhiên, trước khi đọc thêm, hãy cố gắng tự mình nghĩ ra bài toán như vậy.)

Chúng ta đặt $AE=x, BE=y, CE=z$ và biểu thị bán kính của hình tròn $\epsilon$ bằng $e$. Sau đó (Hình 3) $x+a=y+b=z+c=e$. Do đó $x+y+a+b=2e$, tức là $x+y+AB=2e$. Nó cũng được xác định rằng $x+z+AC=y+z+BC=2e$. Các đại lượng $x+y+AB, x+z+AC$ và $y+z+BC$ là chu vi của hình tam giác $AEB, AEC$

Cơm. 2.

Cơm. 3

⟦folio 15⟧

và TRỌNG LƯỢNG. Như vậy, tâm $E$ của đường tròn e hóa ra là nghiệm bài toán “của ba tam giác có chu vi bằng nhau”, hoàn toàn giống với bài toán ban đầu của tứ giác.

Công thức tính điểm của bài toán mới:

“Dan $\Delta ABC$. Có bao nhiêu câu châm ngôn $E$ sao cho chu vi của hình tam giác $AEB, AEC$ và $BEC$ bằng nhau*)?>

Ở trên chúng tôi đã xác định rằng tồn tại ít nhất một điểm như vậy $E$.

bạn đang làm việc
1. Chứng minh rằng không còn điểm nào khác như vậy.
2. Chứng minh điều ngược lại của phát biểu trên: giả sử điểm $E$ sao cho chu vi của mỗi tam giác $AEB, AEC$ và $BEC$ bằng $2e$, khi đó $\alpha$, $\beta$ và $\gamma$ tiếp tuyến từ trong ra ngoài với một đường tròn bán kính $e$ có tâm $E$.

Trong các bài toán ba hình tứ giác và ba hình tam giác, chúng ta không chỉ chứng minh sự tồn tại và duy nhất của các điểm $D$ và $E$ mà còn tìm ra công thức tính chu vi: $2(p+d)=2(a+b+c+d)$ và $2e$. Anh ta hỏi: có thể tính được những chu vi này khi biết các cạnh $\Delta ABC$ không? Bán kính $a, b$ và $c$ được tính bằng các công thức đơn giản (1). $d$ và $e$ có được thể hiện bằng $a, b$ và $c$ không?

Câu trả lời tích cực đáp số cho câu hỏi này được đưa ra trong § 3.

§ 3. Công thức Frederick Soddy

Chúng tôi đã lưu ý rằng bài toán Apollonia đã được giải quyết vào thế kỷ thứ 3 trước Công nguyên. Có vẻ như những ngày này cô không còn chứa đựng được điều gì mới mẻ và bất ngờ nữa. Tuy nhiên, tương đối gần đây, người ta đã thu được một công thức hay cho thấy các kích thước của một vòng tròn tương ứng với nhau như thế nào trong bài toán Apollonius.

Công thức này khiến việc gõ phím trở nên tệ hơn khi bạn phát hiện ra nó không phải do một chuyên gia tạo ra.

*) Chỉ xét các điểm $E$ nằm trong mặt phẳng $\Delta ABC$.

nhà toán học và nhà hóa học - Frederick Soddy.

Chúng ta hãy biểu thị bằng $k, l, m$ và $n$ nghịch đảo của bán kính các đường tròn $\alpha, \beta, \gamma$ và $\delta$ từ § 1:

$k=1/a, l=1/b, m=1/c, n=1/d$.

Sau đó

$2(k^2+l^2+m^2+n^2)=(k+l+m+n)^2$.

Mối quan hệ tao nhã này là công thức của Soddy.

Nó có thể được coi là một phương trình bậc hai cho $n$ (các số $k, l$ và $m$ được coi là đã biết). Giải phương trình này, ta được

$n_{1,2}=k+l+m\pm 2\sqrt{kl+lm+mk}$.

Căn nguyên dương $n_1$ tất nhiên là $1/d$. $n_2$ là gì?

Hóa ra $n_2=-1/e$, trong đó $e$ là bán kính của hình tròn tính từ § 2.

Ý nghĩa của dấu cộng và dấu trừ là gì: tại sao $1/d$ được lấy bằng dấu phẳng và $1/e$ được lấy bằng dấu trừ?

Nghịch đảo của bán kính có một tên đặc biệt: "độ cong". Bán kính càng lớn thì “đường cong” hình tròn càng mượt mà - độ cong của nó càng ít.

Một đường thẳng (trường hợp giới hạn của hình tròn - "đường tròn có bán kính vô hạn") có độ cong bằng không. Sẽ là điều tự nhiên khi sử dụng các dấu hiệu để phân biệt giữa độ cong của độ cong “lồi” và “lõm”. Nhưng vòng tròn lồi và lõm là gì?

Tất nhiên, tất cả các vòng tròn đều “giống nhau”. Nhưng khi nó ở ngoài đường tròn thì đương nhiên coi nó là lồi, còn nếu nó nằm trong cùng một đường tròn thì nó có vẻ lõm. Do đó, “theo quan điểm của các vòng tròn $\alpha, \beta$ và $\gamma$” là vòng tròn và thật hợp lý khi xem xét “khác nhau”: vòng tròn thứ nhất là lồi, vòng tròn thứ hai là lõm.

Chúng tôi sẽ trình bày cách dẫn xuất công thức Soddy trong § 6.

§ 4. Sorpiriz chính

Chúng ta đã gặp một số thử thách: trong § 1 bài toán về các tứ giác có chu vi bằng nhau đột nhiên được rút gọn thành trường hợp đặc biệt của bài toán Apollonius, trong § 2 cần phải chứng minh thứ tự hành động - trước tiên chúng ta đã giải và sau đó lập công thức bài toán về các tam giác có chu vi bằng nhau, trong § 3 chúng tôi trình bày dạng -

⟦folio 16⟧

mulu, được một nhà hóa học hiện đại trang trí thành một trong những hình học bài toán lâu đời nhất.

Nhưng vấn đề tranh cãi chính sẽ được trình bày ngay bây giờ.

Trong chứng minh của mình, chúng tôi đã sử dụng các sự kiện hình học “hiển nhiên” sau đây:

I. Để ba vòng tròn $\alpha$, $\beta$ và $\gamma$ chạm vào nhau ở bên ngoài theo cặp. Khi đó, có đúng một vòng tròn $\delta$ chạm vào $\alpha$, $\beta$ và $\gamma$ ở bên ngoài và đúng một vòng tròn $\varepsilon$ chạm vào $\alpha$, $\beta$ và $\gamma$ chạm vào bên trong.

II. Cho ba đường tròn $\alpha''$, $\beta''$ và $\gamma''$ đi qua một điểm $D$. Khi đó, bất kỳ điểm nào $T$ nằm bên trong $\alpha''$ đều nằm ở bên ngoài $\beta''$ hoặc bên ngoài $\gamma''$ (hoặc bên ngoài cả hai đường tròn này).

Cả hai sự thật đều ... không chính xác. (Pozny và lời giải bài toán M195 cũng sai.)

§ 5. Sửa chữa lớn

Hình 4 hiển thị các vòng tròn $\alpha$, $\beta$ và $\gamma$ trong đó có hai vòng tròn ($\delta_1$ và $\delta_2$) tiếp xúc bên ngoài với $\alpha$, $\beta$ và $\gamma$ và không có vòng tròn $\varepsilon$ nào có $\alpha$, $\beta$ và $\gamma$ cảm ứng bên trong.

Hình 5 định nghĩa “sự thật” II.

Tất nhiên, những kết luận dựa trên “sự thật” I và II cũng không chính xác – mọi dữ liệu được xây dựng trên nền tảng lung lay đều sụp đổ!

May mắn thay, sự tàn phá không quá thảm khốc.

Định lý. Để các vòng tròn $\alpha$, $\beta$ và $\gamma$ chạm vào nhau ở bên ngoài theo cặp. Khi đó có thể xảy ra ba (và chỉ ba) trường hợp:

I. Có chính xác một vòng tròn $\delta$ chạm vào $\alpha$, $\beta$ và $\gamma$ ở bên ngoài và đúng một vòng tròn $\varepsilon$ chạm vào $\alpha$, $\beta$ và $\gamma$ chạm vào bên trong.

II. $\alpha$, $\beta$ và $\gamma$ có một tiếp tuyến chung (và nằm dọc theo một đường thẳng từ nó), trong khi chính xác một đường tròn $\delta$ chạm vào $\alpha$, $\beta$ và $\gamma$ ở bên ngoài và không một đường tròn nào $\alpha$, $\beta$ và $\gamma$ không chạm từ bên trong.

III. Có chính xác hai vòng tròn $\delta_1$ và $\delta_2$, mỗi vòng tròn chạm vào $\alpha$, $\beta$ và $\gamma$ ở bên ngoài và không có vòng tròn nào chạm vào bên trong $\alpha$, $\beta$ và $\gamma$.

Một vài lời về sự đảo ngược.

Để chứng minh định lý này, chúng ta sẽ sử dụng phương pháp nghịch đảo*).

Chúng ta hãy nhắc lại định nghĩa và một số tính chất của nghịch đảo.

Về giới hạn. Cho $Q$ là một đường tròn có tâm $O$ bán kính $R$, nằm trong mặt phẳng $P$. Phép nghịch đảo đối với đường tròn $Q$ được gọi là phép biến đổi sau của mặt phẳng $P$: mỗi điểm của mặt phẳng $M$

*) Savin A.P., Đảo ngược và bài toán Apollo. «Kvant», 1971, số 8.

Cơm. 4.

Cơm. 5.

⟦folio 17⟧

Cơm. 6.

$\Pi$, nằm cách $r$ một khoảng dương $O$, đi đến điểm $M'$, nằm trên tia $OM$ cách $r'$ cách $O$ sao cho $rr' = R^2$; $O$ gọi là tâm nghịch đảo, $R^2$ là hệ số nghịch đảo.

Thuộc tính 1. Nếu $M$ thuộc về $Q$ thì $M' = M$; nếu $M$ nằm bên trong $Q$ và khác với $O$ thì $M'$ nằm bên ngoài $Q$; nếu $M$ nằm ngoài $Q$ thì $M'$ nằm bên trong $Q$.

2. Đường thẳng và đường tròn biến đổi trong quá trình đảo ngược thành đường thẳng và đường tròn, và:

a) các điểm nằm trên một đường thẳng đi qua $O$ đi đến các điểm trên cùng một đường thẳng;

b) một đường thẳng không đi qua $O$ đi vào đường tròn đi qua $O$;

b) đường tròn đi qua $O$ đi vào đường thẳng không đi qua $O$;

d) đường tròn không đi qua $O$ đi vào đường tròn không đi qua $O$; trong trường hợp này $O$ nằm bên ngoài cả hai vòng tròn này hoặc bên trong cả hai vòng tròn này.

3. Nếu hai đường tròn (hoặc một đường thẳng và một đường tròn) chạm vào một điểm $M$ khác với $O$, thì ảnh $^*$ của chúng cũng chạm vào một điểm $M'$; nếu tiếp điểm trùng với $O$ thì các đường tròn này (hoặc một đường thẳng và một đường tròn) biến thành các đường thẳng song song.

*) Tức là chúng biến thành gì sau khi đảo ngược.

Cơm. 7.

Đối với những người lần đầu tiên tìm hiểu về nghịch đảo, chúng tôi khuyên bạn nên tự mình chứng minh các tính chất được liệt kê hoặc đọc bài viết nêu trên của A.P. Savin.

Là một công cụ kiểm soát giúp bạn tìm hiểu mức độ hiểu biết của mình về phương pháp đảo ngược, chúng tôi khuyên bạn nên tìm lỗi trong “lời giải” tiếp theo bài toán.

Để các vòng tròn $\alpha$ và $\beta$ chạm vào bên ngoài tại điểm $O$ (Hình 6). Chúng ta hãy biểu thị vị trí hình học của một điểm bằng $\Gamma$. Trong quá trình đảo ngược với tâm đảo ngược $O$, các vòng tròn $\alpha$ và $\beta$ sẽ biến thành các đường thẳng song song $\alpha'$ và $\beta'$ (Hình 6). Vòng tròn $\gamma$ chạm vào $\alpha$ và $\beta$ sẽ chuyển thành vòng tròn $\gamma'$ chạm vào $\alpha'$ và $\beta'$. Đường chấm chấm $\Gamma'$ trong Hình 6 là quỹ tích của điểm là tâm của các đường tròn $\gamma'$. Vì vậy, đường cong $\Gamma$ đã biến thành đường thẳng trong quá trình đảo ngược. Điều này có nghĩa là $\Gamma$ là đường tròn hoặc đường thẳng.

Nếu bạn tìm thấy lỗi trong “lời giải” ở trên, đã đến lúc chuyển sang chứng minh định lý được xây dựng ở đầu § 5.

Chứng minh định lý. Các vòng tròn $\alpha$, $\beta$ và $\gamma$, theo điều kiện, chạm vào nhau từ bên ngoài theo cặp (Hình 7, a). Điểm tiếp xúc giữa $\alpha$ và $\beta$ sẽ được ký hiệu là $O$.

⟦folio 18⟧

Chúng ta hãy lấy một đường tròn tùy ý $Q$ có tâm $O$ và đảo ngược đường tròn tương đối (Hình 6).

Trong quá trình đảo ngược, các vòng tròn $\alpha$ và $\beta$ sẽ biến thành các đường thẳng song song $\alpha'$ và $\beta'$, đồng thời vòng tròn $\gamma$ thành vòng tròn $\gamma'$, tiếp xúc với các đường thẳng này (Hình 7, b). Tâm nghịch đảo $O$ nằm (hãy kiểm tra xem!) trong dải giữa các đường $\alpha'$ và $\beta'$ bên ngoài vòng tròn $\gamma'$.

Rõ ràng có chính xác hai vòng tròn tiếp xúc với cả $\alpha'$, $\beta'$ và $\gamma'$ (Hình 7, f). Trong trường hợp này, có thể xảy ra ba trường hợp:

I. Điểm $O$ nằm bên trong một trong các đường tròn này (và nằm bên ngoài đường tròn kia).

II. Điểm $O$ nằm trên một trong số chúng (và nằm ngoài điểm kia).

III. Điểm $O$ nằm ngoài cả hai đường tròn này.

Trong trường hợp I và II, chúng tôi biểu thị các vòng tròn đang được xem xét là $\delta'$ và $\varepsilon'$ (và $\delta'$ - vòng tròn bên ngoài mà điểm $O$ nằm), trong trường hợp III, chúng tôi biểu thị chúng bằng $\delta'_1$ và $\delta'_2$.

Bất kỳ đường tròn hoặc đường thẳng nào tiếp xúc với cả $\alpha$, $\beta$ và $\gamma$ đều được định hình lại khi đảo ngược thành đường tròn tiếp xúc với $\alpha'$, $\beta'$ và $\gamma'$. Trong trường hợp I, các vòng tròn $\delta'$ và $\varepsilon'$ đã giao nhau với các vòng tròn—hãy gọi chúng là $\delta$ và $\varepsilon$. Trong trường hợp II, $\delta'$ đã đi qua một đường tròn (gọi là $\delta$) và $\varepsilon'$ đã đi qua một đường thẳng (tức là $\alpha$, $\beta$ và $\gamma$ có một tiếp tuyến chung trong trường hợp này, trong khi $\alpha$, $\beta$ và $\gamma$ rõ ràng là nằm ở một bên của nó). Trong trường hợp III, $\delta'_1$ và $\delta'_2$ các vòng tròn giao nhau (hãy gọi chúng là $\delta_1$ và $\delta_2$).

Vì vậy, các vòng tròn chạm vào $\alpha$, $\beta$ và $\gamma$ là hai hoặc một. Trong trường hợp điểm I, $O$ nằm bên ngoài $\delta$ và bên trong $\varepsilon$, tức là $\delta$ có tiếp tuyến ngoài với $\alpha$, $\beta$ và $\gamma$, còn $\varepsilon$ có tiếp tuyến bên trong. Trong trường hợp điểm II, $O$ nằm ngoài $\delta$ - lại $\delta$ có tiếp tuyến ngoài với $\alpha$, $\beta$ và $\gamma$. Trong trường hợp III, các điểm nằm cả bên ngoài $\delta_1$ và bên ngoài $\delta_2$, sao cho cả hai đều chạm vào bên ngoài $\alpha$, $\beta$ và $\gamma$.

Định lý đã được chứng minh.

Hệ quả 1. Trong trường hợp $I$ Và $II$ bài toán khoảng ba lần chúng ta có thứ duy nhất lời giải (trung tâm $D$ vòng tròn $\delta$), trong trường hợp $III$ - hai lời giải (trung tâm $D_1$ Và $D_2$ vòng tròn $\delta_1$ Và $\delta_2$).

Hệ quả 2. Trong trường hợp $I$ bài toán về ba hình tứ giác ta chỉ có lời giải (tâm $E$ của hình tròn $\varepsilon$), trong trường hợp $II$ và $III$ lời giải thì đó là tiếng Đức.

Quét. Trong §3, chúng tôi đã lập luận (theo lý thuyết không chính xác được phát triển trong §§1 và 2) rằng $n_1 = 1/d$ và $n_2 = -1/e$. Điều này đúng trong trường hợp I. Trong trường hợp này $n_2 < 0$. Trong trường hợp II $n_2 = 0$ (điều này tương ứng với việc đường thẳng - tiếp tuyến chung của $\alpha$, $\beta$ và $\gamma$ - có độ cong bằng 0). Trong trường hợp III, $n_1 = 1/d_1$ và $n_2 = 1/d_2$, trong đó $d_1$ và $d_2$ là bán kính của đường tròn $\delta_1$ và $\delta_2$; trong trường hợp này $n_2 > 0$. Chúng tôi sẽ xác minh tính hợp lệ của các tuyên bố vừa được đưa ra trong § 6.

Cho các cạnh của tam giác $ABC$, chúng ta có thể tính $n_{1,2}$ và xác định trường hợp nào trong ba trường hợp xảy ra.

Đôi khi bạn có thể thực hiện mà không cần tính toán như vậy - chúng ta sẽ nói về điều này trong § 7.

§ 6. Dẫn xuất công thức Soddy

1. Đặt $U, V$ và $W$ là ba số không âm tùy ý có tổng là $π$. Sau đó
$$\sin^2 U = \sin^2 V + \sin^2 W - 2 \sin V \sin W \cos U.$$
Bằng chứng. Hãy dựng một hình tam giác có các góc $U, V$ và $W$. Gọi độ dài các cạnh đối diện là $u, v$ và $w$. Theo định lý cosin
$$u^2 = v^2 + w^2 - 2 vw \cos U.$$
Theo định lý sin
$$u/\sin U = v/\sin V = w/\sin W.$$
Từ đây thu được công thức cần thiết cho mọi góc khác 0. Nếu ít nhất một trong các góc $U, V$ và $W$ bằng 0 thì công thức sẽ được kiểm tra trực tiếp.

⟦folio 19⟧

2. Đặt $A, B, C$ và $D$ là bốn điểm tùy ý của mặt phẳng. Sau đó
$$\sin^2 \frac{\angle ADB}{2} + \sin^2 \frac{\angle ADC}{2} - \sin^2 \frac{\angle BDC}{2})^2 = 4\sin^2 \frac{\angle ADB}{2} \times \sin^2 \frac{\angle ADC}{2} \cos^2 \frac{\angle BDC}{2}.$$
Bằng chứng. Có bốn trường hợp có thể xảy ra (Hình 8) về vị trí tương đối của điểm $A, B, C$ và $D$. Trong mỗi mục, chúng tôi sẽ chọn $U, V$ và $W$ theo bảng bên dưới. Trong mọi trường hợp, $U \geq 0$, $V \geq 0$, $W \geq 0$ và $U + V + W = \pi$ vì vậy, theo điểm 1,
$(\sin^2 V + \sin^2 W - \sin^2 U)^2 = 4\sin^2 V \cdot \sin^2 W \cdot \cos^2 U$.
Vẫn còn phải tận dụng thực tế là trong mọi trường hợp
$$\sin U = \sin \frac{\angle BDC}{2}, \\
\sin V = \sin \frac{\angle ADC}{2}, \\
\sin W = \sin \frac{\angle ADB}{2}, \\
\cos^2 U = \cos^2 \frac{\angle BDC}{2}.$$
3. Đặt một trong các góc của tam giác là $\theta$, cạnh đối diện $-u$, liền kề $-v$ và $w$, ta được mét của tam giác $-q$. Sau đó
$$\cos^2 \frac{\theta}{2} = \frac{q(q - u)}{v \cdot w}, \quad \sin^2 \frac{\theta}{2} = \frac{(q - v)(q - w)}{v \cdot w}.$$
Bằng chứng. Theo định lý cosin
$$u^2 = v^2 + w^2 - 2vw \cos \theta, \quad \cos \theta = (v^2 + w^2 - u^2)/2vw.$$
Có nghĩa,
$$\cos^2 \frac{\theta}{2} = \frac{1 + \cos \theta}{2} = \frac{(v + w)^2 - u^2}{4v \cdot w} = \frac{(v + w + u)(v + w - u)}{4v \cdot w} = \frac{q(q - u)}{v \cdot w},$$

⟦folio 20⟧

$$\sin^2 \frac{\theta}{2} = \frac{1 - \cos \theta}{2} = \frac{u^2 - (v - w)^2}{4v \cdot w} = \frac{(u + v - w)(u + w - v)}{4v \cdot w} = \frac{(q - w)(q - v)}{v \cdot w}.$$

4. Để các vòng tròn $\alpha, \beta, \gamma$ và $\delta$ có tâm $A, B, C$ và $D$ cũng như bán kính $a, b, c$ và $d$ chạm vào nhau từ bên ngoài theo cặp. Sau đó
$$\cos^2 \frac{\angle BDC}{2} = \frac{(b + d + c)d}{(b + d)(d + c)},$$
$$\sin^2 \frac{\angle BDC}{2} = \frac{bc}{(b + d)(d + c)},$$
$$\sin^2 \frac{\angle ADB}{2} = \frac{ab}{(a + d)(d + b)},$$
$$\sin^2 \frac{\angle ADC}{2} = \frac{ac}{(a + d)(d + c)}.$$

Bằng chứng. Trong $\triangle BDC$ chúng ta biểu thị các cạnh và nửa chu vi thông qua $b, d$ và $c$:
$$BC = b + c, \quad BD = b + d, \quad DC = d + c,$$
$$\frac{1}{2}(BC + BD + DC) = b + d + c$$

và sử dụng các công thức ở điểm 3. Chúng ta thu được hai công thức còn lại tương tự từ $\triangle ADB$ và $\triangle ADC$.
4'. Để các vòng tròn $\alpha, \beta, \gamma$ có tâm $A, B, C$ và bán kính $a, b, c$ chạm vào nhau từ bên ngoài theo cặp và để cả ba chạm vào nhau từ bên trong với tâm $E$ và bán kính $e$. Sau đó
$$\cos^2 \frac{\angle BEC}{2} = \frac{(b - e + c)(-e)}{(b - e)(-e + c)},$$
$$\sin^2 \frac{\angle BEC}{2} = \frac{bc}{(b - e)(-e + c)},$$
$$\sin^2 \frac{\angle AEB}{2} = \frac{ab}{(a - e)(-e + b)},$$
$$\sin^2 \frac{\angle AEC}{2} = \frac{ac}{(a - e)(-e + c)}.$$

Chứng minh tương tự như ở điểm 4.
5. Theo các điều kiện của điểm 4, chúng ta đặt $k = 1/a, l = 1/b, m = 1/c, n = 1/d$.

Sau đó
$(-k + l + m + n)^2 = 4(lm + mn + nl).$

Bằng chứng. Theo đoạn 2 và 4
$$\left[ \frac{ab}{(a + d)(d + b)} + \frac{ac}{(a + d)(d + c)} \right]^2 = 4 \frac{ab}{(a + d)(d + b)} \times \frac{ac}{(a + d)(d + c)} \cdot \frac{(b + d + c)d}{(b + d)(d + c)}.$$

Nhân cả hai vế của đẳng thức với $[(a + d)(b + d)(c + d)/abcd]^2$, ta được
$$\left[ \frac{c + d}{cd} + \frac{b + d}{bd} - \frac{a + d}{ad} \right]^2 = 4 \frac{b + d + c}{bdc},$$

hoặc cuối cùng
$(-k + l + m + n)^2 = 4(lm + mn + nl).$

Quét. Các công thức của đoạn 4' được lấy từ các công thức của đoạn 4 nếu chúng ta thay thế $d$ bằng $(-e)$. Do đó, công thức chứng minh ở đoạn 5 cũng đúng với các điều kiện ở đoạn 4' cho $n = -1/e$.

6. Độ cong $k, l, m$ và $n$ của các đường tròn $\alpha, \beta, \gamma$ và $\delta$ tiếp xúc theo cặp với nhau ở bên ngoài, liên quan bởi công thức Soddy
$(k + l + m + n)^2 = 2(k^2 + l^2 + m^2 + n^2).$

Công thức tương tự cũng đúng nếu $n$ là độ cong của đường tròn $\varepsilon$ mà $\alpha, \beta$ và $\gamma$ tiếp xúc từ bên trong.

Bằng chứng. Hãy chuyển đổi danh tính
$(k + l + m + n)^2 = (-k + l + m + n)^2 + 4k(l + m + n)$

có tính đến điểm 5:
$(k + l + m + n)^2 = 4(kl + km + kn + lm + ln + mn).$

Lợi dụng danh tính
$(k + l + m + n)^2 - (k^2 + l^2 + m^2 + n^2) = 2(kl + km + kn + lm + ln + mn),$

chúng tôi nhận được
$(k + l + m + n)^2 = 2[(k + l + m + n)^2 - (k^2 + l^2 + m^2 + n^2)].$

Đưa các số hạng tương tự, chúng ta thu được công thức Soddy.

7. Từ tuyên bố đã được chứng minh ở đoạn 6, ngay sau đó

⟦folio 21⟧

Hệ quả 1. Ta đặt (như ở § 3)
$$n_{1,2} = k + l + m \pm 2\sqrt{kl + lm + mk}.$$
Sau đó, xét theo điều § 5, nếu trường hợp I xảy ra thì $n_2 < 0$, và nếu trường hợp III xảy ra thì $n_2 > 0$.

Bài tập 3. Chứng minh trường hợp II $n_2 = 0$.

Kết hợp Hệ quả 1 và bài tập, ta được

Hệ quả 2. Nếu $n_2 < 0$ thì xảy ra trường hợp I, nếu $n_2 = 0$ thì xảy ra trường hợp II, nếu $n_2 > 0$ thì xảy ra trường hợp III.

§ 7. Một điều cần thiết khác

Vào tháng 6, Bài toán Kvant đã xuất bản bài toán M209.

Với mọi tam giác ABC, bạn có thể tính tổng sau:
$$S = \text{tg}^2 \frac{A}{2} + \text{tg}^2 \frac{B}{2} + \text{tg}^2 \frac{C}{2}.$$
Chứng minh rằng:
a) $S < 2$ cho tất cả các tam giác nhọn và tam giác vuông;
b) $S > 2$ đối với tam giác tù có góc tù lớn hơn 2 cung tan $^4/3$;
b) với mọi φ sao cho $\frac{\pi}{2} < \varphi < 2\arctg \frac{4}{3}$, trong số các tam giác tù có góc tù bằng $\varphi$, có những tam giác sao cho $S > 2$ và những tam giác sao cho $S < 2$.

Thoạt nhìn, vấn đề M195 và M209 nói lên những điều hoàn toàn khác nhau. Nhưng hóa ra - một điều ngạc nhiên khác - giữa họ có một mối liên hệ sâu sắc.

Sử dụng § 6 (điểm 3 và 4), dễ dàng chứng minh được điều sau:

Phát biểu 1. Cho các vòng tròn $\alpha, \beta, \gamma$ có tâm A, B, C và bán kính a, b, c theo cặp tiếp xúc với nhau ở bên ngoài và để $a + b + c = p$. Sau đó
$$\text{tg}^2 \frac{A}{2} = \frac{bc}{ap}, \text{tg}^2 \frac{B}{2} = \frac{ac}{bp},$$
$$\text{tg}^2 \frac{C}{2} = \frac{ab}{cp}.$$

Vì vậy, $(a + b + c)S = \frac{bc}{a} + \frac{ac}{b} + \frac{ab}{c}$. Chia cả hai vế của đẳng thức này cho abc, ta được
$$S \left( \frac{1}{ab} + \frac{1}{bc} + \frac{1}{ca} \right) = \frac{1}{a^2} + \frac{1}{b^2} + \frac{1}{c^2}$$
hoặc $S(kl + lm + mk) = k^2 + l^2 + m^2$. Sử dụng đồng nhất thức $k^2 + l^2 + m^2 = (k + l + m)^2 - 2(kl + lm + mk)$, chúng ta tìm thấy: $(S + 2)(kl + lm + mk) = (k + l + m)^2$.

Vì vậy, các điều kiện sau đây là tương đương theo cặp:
$$S < 2 \text{ и } (k + l + m)^2 < 4(kl + lm + mk),$$
$$S = 2 \text{ и } (k + l + m)^2 = 4(kl + lm + mk),$$
$$S > 2 \text{ и } (k + l + m)^2 > 4(kl + lm + mk).$$

Chúng ta hãy nhớ công thức
$$n_{1,2} = (k + l + m) \pm 2\sqrt{kl + lm + mk},$$
chúng tôi nhận được nó từ đây.

Phát biểu 2. Các điều kiện S<2, S=2 và S>2 đặc trưng (tương ứng với) các trường hợp I ($n_2 < 0$), II ($n_2 = 0$) và III ($n_2 > 0$).

Do đó, kết quả bài toán M209 cho phép xem khá một phần △ ABC để cho biết trường hợp nào trong các trường hợp I, II, III đúng: nếu △ ABC là nhọn hoặc hình chữ nhật, thì trường hợp I (bài toán M195 trong trường hợp này có chính xác một lời giải D), nếu △ ABC "rất tù" ($\varphi > 2\arctg^4/3$), thì trường hợp III (bài toán) M195 có hai lời giải D$_1$ và D$_2$). “Lưu vực” (trường hợp II) chạy dọc theo các hình tam giác “không quá tù” ($\pi/2 < \varphi < 2\arctg^4/3$). Bạn sẽ có thêm một số thông tin về "đầu nguồn" này bằng cách giải bài toán M209 hoặc đọc lời giải của cô ấy trong "Bài toán Kvant".
