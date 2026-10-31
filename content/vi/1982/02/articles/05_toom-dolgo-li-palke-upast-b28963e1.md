---
id: 1982-2-toom-dolgo-li-palke-upast-b28963e1
issue: kvant_1982_2
year: 1982
number: "2"
title: Sau bao lâu thì cây gậy rơi xuống?
authors:
  - Тоом А. Л.
rubric: osnovnye-stati
page_first: 12
page_last: 15
page_labels: 10-13
tag: IYSU
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 8878571d56041e4fa47089ff27a8a17f3c3e06337f5a9054a2bdf413405c239d
prompt_sha256: draft-1
translated_from: content/ru/1982/02/articles/05_toom-dolgo-li-palke-upast-b28963e1.md
source_content_sha256: 95aafb65796ba1689e8eb7c24b0c9d3d598c882d1a420e2fe5bb7814fc331750
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 10⟧

Sau bao lâu thì cây gậy rơi xuống?

Từ biên tập viên. Khi giải một bài toán vật lý thực, chúng ta thường chọn mô hình lý tưởng hóa của nó, mô hình này cho phép chúng ta áp dụng các phương pháp toán học cho lời giải của nó. Tất nhiên, điều quan trọng là phải chọn đúng thiết bị cho sự lựa chọn này. Những khó khăn không mong muốn có thể nảy sinh trong trường hợp này sẽ được đề cập trong bài viết dưới đây dưới góc nhìn của một nhà toán học.

Hãy làm thí nghiệm vật lý sau. Đặt một cây gậy thẳng đứng trên sàn (bạn có thể dùng bàn chải, cây lăn, thước kẻ, v.v.) và nhẹ nhàng, không cần đẩy, bỏ tay ra rồi thả ra. Cây gậy sẽ rơi. Tất nhiên, nếu thanh dày (ví dụ: một khúc gỗ) và đầu dưới của nó khá chắc chắn thì nó sẽ vẫn đứng vững, nhưng chúng tôi không xem xét trường hợp này. Những chiếc gậy mỏng có đầu dưới nhọn, đặt thẳng đứng trên sàn, luôn rơi nếu không có gì đỡ chúng - đây là một thực tế thực nghiệm.

Bây giờ chúng ta thử so sánh thực tế này với một tính toán lý thuyết.

Khi điều này được thực hiện với lời giải vật lý bài toán, chúng ta hãy lý tưởng hóa đối tượng đang xem xét: cùng với những chiếc gậy, hãy xem xét một thanh không có độ dày, được gắn thẳng đứng trên một bề mặt nằm ngang; thanh nằm trong trường trọng lực và môi trường không cản trở chuyển động; anh ấy sẽ tiếp tục nad trong bao lâu?

Với một số lần xuất hiện, bạn có thể nhận thấy rằng đầu dưới của cây gậy chỉ bất động trong giai đoạn đầu rơi; sau đó anh ta đi ngang qua sàn nhà. Người đó đi theo hướng nào phụ thuộc vào hệ số ma sát của thanh trên sàn*. Để tránh khó khăn này, giả sử rằng đầu dưới của thanh lý tưởng của chúng ta được cố định trong một bản lề; không có đào tạo.

Chúng ta biểu thị bằng $l$ khoảng cách từ tâm khối lượng của thanh đến đầu dưới của nó và bằng $m$ khối lượng của thanh. Khoảng cách là thời điểm mà thanh tạo thành một góc thẳng đứng $\alpha$, $0 < \alpha \leq \frac{\pi}{2}$ (Hình 1). Tại thời điểm này, khối tâm sẽ giảm $l$ (1—cos $\alpha$). Điều này có nghĩa là thế năng giảm $mgl$ (1—cos $\alpha$). Nó chuyển thành động năng, chúng ta sẽ viết dưới dạng $K = I \frac{\omega^2}{2}$, vì nó tỉ lệ với bình phương vận tốc góc $\omega$ (ở đây $I$ là hằng số**), và $\omega$ phụ thuộc vào $\alpha$).

Thật vậy, nếu khối lượng của thanh được coi là tập trung ở khối tâm của nó thì

$$K = \frac{1}{2} m v_0^2 = \frac{1}{2} m (l \omega)^2 = (ml^2) \frac{\omega^2}{2}.$$ (0)

Nếu thanh được coi là đồng nhất thì

*) Ví dụ, xem bài toán 196, 197 trong bài tập của B.B. Bukhovtsev et al. “Bộ sưu tập bài toán về vật lý cơ bản” (M., “Hayka”, 1974).

**) I gọi là mômen quán tính; định nghĩa của khái niệm này có thể được đọc trong số trước «Kvant» trên trang. 6, nhưng chúng tôi sẽ không cần nó.

⟦folio 11⟧

Hình 1.

$$K = \int_{0}^{2l} \frac{m(v(y))^2}{2l \cdot 2} \, dy = \frac{m}{2l} \int_{0}^{2l} \frac{(\omega y)^2}{2} \, dy = \left( \frac{4}{3} m l^2 \right) \frac{\omega^2}{2}.$$ (00)

Cân bằng thế năng bị mất và động năng thu được, ta có

$$\frac{1}{2} I \omega^2 = m g l (1 - \cos \alpha),$$

Ở đâu

$$\omega = \sqrt{\frac{2}{l} m g l (1 - \cos \alpha)} = 2 \sqrt{\frac{m g l}{l} \sin \frac{\alpha}{2}}$$

Vận tốc góc $\omega$ là tốc độ thay đổi góc $\alpha$, tức là tùy ý $\alpha$ theo thời gian:

$$\omega = \frac{d\alpha}{dt}.$$

Do đó (theo định lý về hàm nghịch đảo tùy ý)

$$\frac{dt}{d\alpha} = \frac{1}{\omega} = \frac{1}{2} \sqrt{\frac{I}{m g l}} \cdot \frac{1}{\sin \frac{\alpha}{2}}.$$ (1)

Biểu hiện này có ý nghĩa không? Tích phân của các hàm giới hạn liên tục được dạy ở trường. Ở đây, dưới dấu tích phân có một hàm không xác định tại $\alpha = 0$ và tiến tới vô cùng tại $\alpha \to 0$. Một "đường nho cong" giữa trục $\alpha$, các đường $\alpha = 0$ và $\alpha = \frac{\pi}{2}$ và đồ thị của hàm này

Hình 2.

tsini, vô hạn (Hình 2). Làm thế nào chúng ta có thể nói về diện tích của hàm vô hạn? Hóa ra là có thể, và với một định nghĩa hợp lý, diện tích này đôi khi thậm chí còn hữu hạn. Tích của một hàm không giới hạn thuộc loại như (1) được gọi là không đúng và, theo định nghĩa, được coi là bằng phần mở đầu của một liên liên thông thường, “đúng” với sự thay đổi phù hợp trong ranh giới của nó*). Trong trường hợp này

$$\int_{0}^{\frac{\pi}{2}} \frac{d\alpha}{\sin \frac{\alpha}{2}} = \lim_{\varepsilon \to 0} \int_{\varepsilon}^{\frac{\pi}{2}} \frac{d\alpha}{\sin \frac{\alpha}{2}}$$

Tích số bên dưới dấu giới hạn, tương ứng với vùng tô bóng trong Hình 2, có thể được tính toán chính xác, nhưng hiện tại chúng ta thậm chí chưa cần đến nó.

Hãy nhớ lại rằng $\sin \alpha < \alpha$ tại $0 < \alpha < \frac{\pi}{2}$.

Vì thế $\sin \frac{\alpha}{2} < \frac{\alpha}{2}$, từ đâu

$$\int_{0}^{\frac{\pi}{2}} \frac{d\alpha}{\sin \frac{\alpha}{2}} > 2 \int_{\varepsilon}^{\frac{\pi}{2}} \frac{d\alpha}{\sin \frac{\alpha}{2}} = 2 \left( \ln \frac{\pi}{2} - \ln \varepsilon \right).$$

Biểu thức cuối cùng có xu hướng vô cùng là $\varepsilon \to 0$.

Đây rồi! Hóa ra thời gian cây gậy rơi là vô cùng! Nhưng trong một thí nghiệm, cây gậy rơi xuống - điều đó có nghĩa là lý thuyết mâu thuẫn với thực tiễn?

Tất nhiên, tình hình không quá rõ ràng. Nếu lúc đầu thanh thẳng đứng thì nó

*) Ví dụ, hãy xem định nghĩa về tích phân suy rộng trong bài toán 12, đoạn 1 của Chương V trong cuốn sách của B. M. Ivlev et al. “Bộ sưu tập bài toán về đại số và phần đầu của bài phân tích lớp 9 và 10.” (M., “Khai sáng”, 1978).

⟦folio 12⟧

sẽ không giảm chút nào, nghĩa là α sẽ luôn bằng 0. Thực tế, chúng tôi đã bắt đầu tính toán của mình với một số α dương.

Vì trong thực tế cây gậy vẫn rơi nên về lý thuyết phải so sánh với cây gậy rơi xuống. Về mặt vật lý, đương nhiên có thể xét một trong hai trường hợp sau:

1) lúc đầu thanh thẳng đứng và có vận tốc góc nhỏ nhưng khác 0;
2) Lúc đầu thanh đứng yên và lệch khỏi phương thẳng đứng một góc nhỏ nhưng khác 0.

Nhưng trong những trường hợp này, các công thức sẽ phải được viết lại và chúng phức tạp hơn những công thức đã được viết trước đó. Do đó, chúng ta hãy xem xét trường hợp đơn giản nhất theo quan điểm toán học: thanh rơi theo thời gian (xem 1))

$$T = \frac{1}{2} \sqrt{\frac{I}{mgl}} \int_{\varepsilon}^{\frac{\pi}{2}} \frac{d\alpha}{\sin \frac{\alpha}{2}}.$$

Ý nghĩa vật lý của trường hợp này là ban đầu thanh bị lệch so với phương thẳng đứng một góc nhỏ ε > 0 và có vận tốc góc ban đầu bằng

$$2 \sqrt{\frac{mgl}{I}} \sin \frac{\varepsilon}{2}.$$

Bây giờ không có nghịch lý nào cả, vì khoảng viết đã có định nghĩa đầy đủ về một giá trị hữu hạn.

Nó thậm chí có thể được tính toán chính xác. Sử dụng công thức tính đạo hàm của một hàm phức, bạn có thể xác minh rằng

$$\left(2 \ln tg \frac{x}{4}\right)' = \frac{1}{\sin \frac{x}{2}},$$

Ở đâu

$$\int_{\varepsilon}^{\frac{\pi}{2}} \frac{d\alpha}{\sin \frac{\alpha}{2}} = 2 \left(\ln tg \frac{\pi}{8} - \ln tg \frac{\varepsilon}{4}\right).$$

Vậy thời điểm rơi của thanh là

$$T = Q \left(\ln tg \frac{\pi}{8} - \ln tg \frac{\varepsilon}{4}\right),$$

ở đâu $Q = \sqrt{\frac{I}{mgl}}$.

Nếu toàn bộ khối lượng của thanh tập trung ở khối tâm của nó thì (xem (0))

$$I = ml^2 \text{ и } Q = \sqrt{\frac{l}{g}}.$$

Nếu thanh đồng nhất thì (xem (0))

$$I = \frac{4}{3} ml^2 \text{ и } Q = \sqrt{\frac{4}{3} \frac{l}{g}}.$$

Trong cả hai trường hợp, thời gian rơi $T$ không phụ thuộc vào khối lượng $m$ và tỷ lệ thuận với căn bậc hai của $l$. Điều này tương ứng với thực tế quan sát được là gậy dài rơi nhanh hơn gậy ngắn.

Lưu ý rằng các chỉ số nghịch lý thu được lúc đầu sẽ không phải lúc nào cũng được thay thế. Ví dụ: bài toán 195 trong cuốn sách bài toán được đề cập của B.B. Bukhovtsev và cộng sự. được xây dựng như sau: Một quả bóng nặng được gắn trên một thanh nhẹ (Hình 3). Trong trường hợp nào thanh sẽ rơi nhanh hơn: nếu nó được đặt thẳng đứng ở đầu $A$, hay ở đầu $B$? Đứng trên mặt đất, đầu thanh không bị trượt.

Vì lời giải này bài toán công thức tính vận tốc góc được suy ra

$$\omega = 2 \sin \frac{\alpha}{2} \sqrt{\frac{g}{R}},$$

trong đó $R$ là khoảng cách từ đầu thanh đến tâm khối lượng của quả bóng (công thức này trùng với công thức của chúng ta ở $l = R, I = mR^2$), và xa hơn nữa: "Với một α cho trước, $R$ càng lớn thì nó càng nhỏ. Do đó, thanh sẽ rơi nhanh hơn nếu nó được đặt ở đầu $B$" (tr. 227). Lập luận này không đúng, bởi vì, như chúng ta đã thấy, tích phân của công thức viết ở trên là vô hạn với mọi $R > 0$. Có ý nghĩa gì không khi nói rằng một vô cực lớn hơn các vô cực khác? Điều gì sẽ xảy ra trong một số

Hình 3.

⟦folio 13⟧

Để giải bài toán được trích dẫn, ví dụ, người ta có thể xem xét các thanh ban đầu bị lệch khỏi phương thẳng đứng bởi một góc nhỏ nào đó hoặc có một số vận tốc góc ban đầu nhỏ, hoặc cả hai - như đã làm ở trên.

Nhân tiện, ở một khía cạnh nào đó, chúng tôi cũng đã quyết định bài toán số 56 từ mức xuất sắc bài toán của I. Sh. Slobodetsky và L. G. Aslamazov “Bài toán in Physics” (M., “Nuka”, 1980): Tại sao việc giữ một mảnh vụn trên ngón tay lại dễ dàng hơn nhiều so với một miếng paluta có cùng chiều dài?

Trong lời giải bài toán nêu trong bài toán (tr. 77), mời độc giả xem xét độc lập thời gian rơi phụ thuộc vào độ dài của thanh như thế nào và không đề cập đến những khó khăn mà chúng ta đang cố gắng vượt qua ở đây. Sự gọn gàng của lời giải của bài toán này thực sự đòi hỏi phải xem xét thời gian cây gậy rơi, nhưng để thời gian này là hữu hạn (và chỉ có thể so sánh các giá trị hữu hạn với nhau), cần phải xem xét điều kiện ban đầu, bằng cách nào đó khác với điều kiện cân bằng. Việc xem xét này mang lại một ý nghĩa chặt chẽ cho một phép tính không chính thức như “trọng tâm của cây gậy càng cao thì nó nghiêng càng chậm và bạn càng dễ dàng di chuyển ngón tay của mình theo cùng một hướng”.

Trong quá trình thảo luận về bài toán ban đầu, chúng tôi đã phải từ bỏ mô hình đơn giản nhất của nó (một thanh bản lề lý tưởng đứng thẳng đứng) và xem xét một mô hình phức tạp hơn, vì một thanh lý tưởng thẳng đứng không rơi. Tuy nhiên, mô hình đơn giản nhất là hoàn toàn chính xác nếu bạn đảo ngược thời gian, nói cách khác, nó xử lý không phải một cây gậy rơi xuống mà là một cây gậy giơ lên. Chính xác hơn, hãy xem xét bài toán sau: một đầu của thanh lý tưởng nằm ngang có chiều dài l được cố định trong một bản lề, và đầu kia được truyền một tốc độ hướng lên trên và bằng $\sqrt{8gl/3}$; thanh sẽ tăng lên như thế nào?

đáp số đúng cho tích phân (1): thanh sẽ nâng lên vô hạn, có xu hướng chuyển sang vị trí thẳng đứng nhưng không bao giờ đạt tới vị trí đó. Như vậy, người thôi miên khi chuyển sang tư thế trên trên xà ngang, để không lên đến điểm cân bằng trong thời gian dài vô thời hạn, do chuyển động tối đa, phải tạo cho mình một tốc độ đảm bảo chuyển động xa hơn điểm này và giữ nguyên trong đó do ma sát (dùng tay kẹp xà ngang).

Nhưng đây là điều vẫn chưa rõ ràng về bản gốc bài toán.

Giả sử chúng ta đang thực hiện một số thí nghiệm với cùng một cây gậy. Mỗi lần chúng ta đặt nó trên sàn, dường như chúng ta đặt nó theo chiều dọc và buông ra. Cây gậy rơi xuống và bạn có thể đảm bảo rằng khoảng thời gian rơi không khác nhau nhiều trong mọi trường hợp. Và điều này thật kỳ lạ. Rốt cuộc, mỗi lần thanh thực sự lệch khỏi phương thẳng đứng một góc khác 0 khác và có tốc độ ban đầu khác 0 khác. Điều này có nghĩa là thời gian rơi phải khác nhau. Trong một số trường hợp, có vẻ như góc ban đầu và tốc độ làm việc phải rất nhỏ, sau đó thời gian rơi sẽ rất lớn, nhưng điều này không được quan sát thấy. Có chuyện gì vậy?

Chúng tôi chỉ có thể trả lời câu hỏi này một cách không chính thức. Hãy xem xét công thức (2). Nó chứa một số hạng không đổi $Q \ln tg \frac{\pi}{8}$ và một số hạng biến đổi $Q \ln tg \frac{\varepsilon}{4}$. Đối với $\varepsilon$ nhỏ (cũng là điều chúng ta quan tâm), $tg \frac{\varepsilon}{4}$ gần với $\frac{\varepsilon}{4}$ và số hạng biến gần với

$$-Q \ln \frac{\varepsilon}{4} = Q \ln 4 - Q \ln \varepsilon.$$

Vì vậy, thực tế là số lượng - $\ln \varepsilon$, mặc dù nó có xu hướng tiến đến vô cùng ở $\varepsilon \rightarrow 0$, nhưng rất chậm.

Ví dụ: giảm $\varepsilon$ 10 lần tương ứng với mức tăng - $\ln \varepsilon$ theo giá trị không đổi $\ln 10 \approx 2,3$.

(Cuối cùng xem trang 24)
