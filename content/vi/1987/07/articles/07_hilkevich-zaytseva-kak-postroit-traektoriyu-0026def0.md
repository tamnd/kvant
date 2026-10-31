---
id: 1987-7-hilkevich-zaytseva-kak-postroit-traektoriyu-0026def0
issue: kvant_1987_7
year: 1987
number: "7"
title: Làm thế nào để xây dựng một quỹ đạo?
authors:
  - Хилькевич С. С.
  - Зайцева О. А.
rubric: raznoe
page_first: 28
page_last: 32
page_labels: 26, 28, 29, 30
tag: DGVW
lang: vi
source: kvant_digital
extraction: vision
content_sha256: d2cc35a313ea5ce4075fccc5e99d4ffd82f2983b6f585199b5917222ac1f4a0a
prompt_sha256: draft-1
translated_from: content/ru/1987/07/articles/07_hilkevich-zaytseva-kak-postroit-traektoriyu-0026def0.md
source_content_sha256: 6abe958734e9192f4001adcf90e72d762fc3d895ad872f9e453f928e5148c886
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 26⟧

LÀM THẾ NÀO ĐỂ XÂY DỰNG QUỸ ĐẠO?

Nhu cầu tính toán quỹ đạo của một chuyển động cụ thể của con người là rất thường xuyên. bài toán này xuất hiện cả trước khi một thổ dân Úc lẻn vào một đàn chim với chiếc boomerang và trước khi một nhà toán học tính toán vị trí của một con tàu vũ trụ.

Trong bài viết này, chúng tôi muốn nói về một phương pháp xây dựng gần đúng quỹ đạo của các chuyển động phức tạp, minh họa nó bằng các ví dụ cụ thể và cung cấp cho người đọc một số trò chơi dựa trên phương pháp này.

Hãy bắt đầu lại từ đầu

Không ngại bắt đầu và tôi vẫn đang hoàn thiện.
Trước khi bạn đọc xong một câu chuyện cổ tích, đừng chỉ trỏ.
V. Dal. Tục ngữ của người dân Nga

Ý tưởng chính của phương pháp này rất đơn giản và dựa trên mối quan hệ quen thuộc nối vectơ dịch chuyển của một điểm vật chất với vectơ tốc độ trung bình của nó. Chúng ta hãy nhớ lại rằng tốc độ trung bình $\vec{v}_{\text{cp}}$ của chuyển động không đều được gọi là đại lượng vật lý bằng tỷ lệ giữa chuyển động $\vec{s}$ của cơ thể trong một khoảng thời gian nhất định $\Delta t$ với khoảng thời gian của khoảng thời gian này:

$$\vec{v}_{\text{cp}} = \frac{\vec{s}}{\Delta t}.$$

Từ đây

$$\vec{s} = \vec{v}_{\text{cp}} \Delta t.$$

Cả tốc độ trung bình và độ dịch chuyển đều là các đại lượng vectơ, vì vậy trong các hình vẽ chúng được mô tả dưới dạng các đoạn có hướng. Trong trường hợp này, hướng của cả hai vectơ đều giống nhau nhưng độ dài khác nhau $\Delta t$ lần. Rõ ràng, với sự lựa chọn tỷ lệ thích hợp, có thể làm cho các đoạn có hướng mô tả tốc độ trung bình và độ dịch chuyển trùng nhau.

$$\vec{v}_0$$

Hình 1.

hoàn toàn - cả về hướng và chiều dài. Tất nhiên, chính hoàn cảnh này đã giúp chúng ta có thể nhanh chóng và phần nào xây dựng các quỹ đạo khác nhau một cách gần đúng.

Trước tiên chúng ta hãy xem xét trường hợp đơn giản nhất – chuyển động thẳng đều. Giả sử tại thời điểm ban đầu vật ở điểm $A_0$ và có tốc độ $\vec{v}_0$ (hình 1). Vì (như chúng ta đã đồng ý) vectơ dịch chuyển trong khoảng thời gian $\Delta t$ trùng với vectơ vận tốc, nên sau khoảng thời gian này, vật sẽ ở điểm $A_1$, tại đó vectơ vận tốc ban đầu $\vec{v}_0$, bị trễ từ $A_0$, xuất hiện. Đặt một vectơ khác $\vec{v}_0$ từ điểm $A_1$, chúng ta thu được điểm $A_2$, tại đó phần thân kết thúc sau hai khoảng $\Delta t$. Tiếp tục quy trình này, chúng ta thu được một chuỗi các điểm $A_n$ mà tại đó vật sẽ nằm sau $n$ khoảng thời gian đã chọn kể từ khi bắt đầu chuyển động. Đi qua các điểm đó là quỹ đạo chuyển động thẳng đều.

Ý tưởng khái quát hóa phương pháp

Họ là những người đầu tiên xem xét khái quát hóa CRA cho trường hợp “người chơi nhiều tay”, tức là người chơi có nhiều hơn hai tay.

Từ bộ sưu tập “Vườn hoa toán học”

Trường hợp chuyển động thẳng đều được thảo luận ở trên là trường hợp đơn giản nhất, nhưng ý tưởng chính của phương pháp vẫn không thay đổi trong các tình huống phức tạp hơn.

Ý tưởng của phương pháp như sau.

Để ước chừng việc xây dựng quỹ đạo, chúng tôi chia toàn bộ thời gian chuyển động của cơ thể thành những khoảng nhỏ *),

*) Tùy thuộc vào các điều kiện chuyển động, khoảng thời gian của một khoảng thời gian “nhỏ” có thể thay đổi từ một phần micro giây đến hàng tỷ năm. Điều quan trọng là nó phải ít hơn nhiều so với thời lượng của quá trình được đề cập.

⟦folio 28⟧

điểm $A_3$. Cơ thể sẽ kết thúc trong đó sau khoảng $\Delta t$ sau khi vượt qua điểm $A_2$, v.v. Công trình đưa ra một quỹ đạo gần đúng - một đường đứt nét, tương tự như parabol nổi tiếng, là quỹ đạo thực sự.

Lời giải cái bài toán này có vẻ không có gì đặc biệt, vì đáp số đã được biết trước từ khóa học vật lý ở trường. Hơn nữa, việc so sánh kết quả thu được với kết quả đã biết cho phép bạn kiểm tra phương pháp và việc xác minh luôn hữu ích.

Bây giờ chúng ta đã sẵn sàng xem xét bài toán phức tạp hơn và chưa được nghiên cứu ở trường về chuyển động của một vật thể trong trường trọng lực khi có lực cản không khí. Giả sử tại thời điểm ban đầu vật ở điểm $A_0$ và có tốc độ $\vec{v}_0$ (hình 4), và lực cản của không khí $\vec{F}_c$ liên hệ với vectơ vận tốc của vật $v$ bởi sự tương ứng $\vec{F}_c = -\alpha \vec{v}$ (α là hệ số không đổi). Cần phải xác định quỹ đạo của cơ thể sẽ như thế nào trong trường hợp này.

Gia tốc $\vec{a}$, gây ra bởi hai sự hợp nhất - trọng lực và lực cản, có thể được xác định từ định luật thứ hai của Newton. Tuy nhiên, để xây dựng, sẽ thuận tiện hơn khi biểu diễn gia tốc $\vec{a}$ dưới dạng tổng của hai thành phần: gia tốc $a_t = g$, do trọng lực truyền và gia tốc $\vec{a}_c = \vec{F}_c / m = -(\alpha / m)\vec{v}$. Nếu bạn mô tả sự phụ thuộc của $a_c$ vào $v$ dưới dạng biểu đồ, thì từ đó có thể dễ dàng xác định độ lớn của gia tốc $\vec{a}_c$ đối với bất kỳ giá trị nào của tốc độ cơ thể. Ví dụ, gia tốc này luôn ngược chiều với hướng của vectơ vận tốc $\vec{v}$.

Hãy bắt đầu xây dựng quỹ đạo. Sau một khoảng thời gian ngắn $\Delta t$ sau khi vật bắt đầu chuyển động từ điểm $A_0$ (xem hình 4), nó kết thúc ở điểm $A_1$. Để dựng vectơ vận tốc ở bước tiếp theo, bạn cần tắt vectơ vận tốc ban đầu $\vec{v}_0$ khỏi điểm $A_1$ và thêm vectơ gia tốc $\vec{a} = \vec{g} + \vec{a}_c$ vào đó (chúng ta đã biết cách dựng vectơ $\vec{g}$ và $\vec{a}_c$ riêng biệt). Kết quả của việc xây dựng, chúng ta thu được điểm $A_2$ - vectơ vận tốc mới sẽ hướng tới nó. Như vậy, sau hai khoảng thời gian kể từ khi vật bắt đầu chuyển động, nó sẽ kết thúc ở điểm $A_2$.

Lặp lại quy trình này, chúng ta nhận được điểm $A_3$, tại đó vật sẽ kết thúc sau một khoảng thời gian khác, sau đó là các điểm $A_4$, $A_5$, v.v. Lưu ý rằng gia tốc $\vec{a} = \vec{g} + \vec{a}_c$ sau mỗi khoảng thời gian phải được xác định lại, vì thành phần $\vec{a}_c$ phụ thuộc vào tốc độ và do đó không giữ nguyên trong quá trình chuyển động.

Đường đứt nét đi qua các điểm $A_0$, $A_1$, $A_2$, ..., thể hiện quỹ đạo bay gần đúng của vật thể khi có lực cản không khí. Điểm đặc biệt của đường cong này là, không giống như một parabol (xem hình 3), nó không đối xứng so với phương thẳng đứng đi qua điểm bay: nhánh đi của quỹ đạo có hình tròn hơn nhánh đi lên. Bây giờ hãy xem mô hình mà chúng tôi đã tạo từ sách giáo khoa cầu lông*) hình 5, hiển thị đường bay của sóng cho các cú giao bóng khác nhau. Bạn có thấy không?

Hầu hết tất cả các quỹ đạo đều có một đặc điểm nổi bật - chúng không đối xứng. Điều này được sử dụng rất rộng rãi trong thể thao. Ví dụ, một quả giao bóng cao thường được giao ở độ cao bằng chiều cao trần nhà và sức mạnh của người chơi cho phép - đồng thời, ở đường cuối sân đối phương, quả còn rơi gần như thẳng đứng và quả còn trả lại không thể bị đánh trả mạnh vì bộ lông bị cản trở.

Bây giờ các điều kiện ngưng tụ là tự nhiên, chẳng hạn như thêm một lực khác tác dụng lên vật. Cung cấp

*) Rybkov D. P., Shtilman M. I. Những nguyên tắc cơ bản của cơ sở thể thao. (M., Văn hóa thể chất và thể thao, 1978.)

⟦folio 29⟧

Hóa ra điều này cho phép chúng ta xem xét một bài toán o...

Ở đây, chúng tôi khuyên người đọc nên ngừng đọc trong vài phút, gấp một mảnh giấy thành một “máy bay” và chỉ ra những thủ thuật mà nó thực hiện trên không khi được phóng ở các tốc độ khác nhau và ở các góc khác nhau so với đường chân trời. Thứ nhất, điều này mang đến cho bạn cơ hội thư giãn một chút, và thứ hai, sau những thử nghiệm như vậy, bạn sẽ thích thú hơn nhiều khi đọc những gì được viết tiếp theo.

Máy bay giấy bay như thế nào?

Không có gì có thể được nói trước ở đây. Và điều này, tất nhiên, là thú vị nhất!

A. A. Mill. Vinits-Pooh và tất cả-tất cả

Các thí nghiệm được thực hiện có thể đã thuyết phục bạn rằng một chiếc máy bay giấy hoạt động phức tạp và thú vị hơn nhiều so với một hòn đá ném hoặc một quả cầu lông. Sau đó ném nó theo chiều ngang mọi lúc, sau đó, tùy thuộc vào tốc độ ban đầu, nó lao gần như thẳng đứng xuống sàn hoặc bay lên trần nhà. Hầu như không thể đoán trước quỹ đạo chuyến bay của nó, nhưng điều này không có nghĩa là không thể phân tích được hành vi của một chiếc ví rơi trong không khí.

Bài toán bay của một chiếc máy bay giấy là một phần của bài toán tổng quát hơn bài toán về chuyến bay không điều khiển được của một chiếc máy bay không có động cơ. bài toán này lần đầu tiên được lắp đặt và quyết định thay thế bởi nhà khoa học người Nga, người sáng lập ngành khí động học N. E. Zhukovsky (1847-1921). Ở đây chúng tôi sẽ chỉ phân tích phương án đó bài toán, mà chính Zhukovsky gọi là “bài toán tàu lượn”.

Hãy để một chiếc tàu lượn đối xứng (hình6) bay trong không trung. Ba lực tác dụng lên nó: trọng lực

$$\vec{F}_T$$, lực kéo $$\vec{F}_c$$ và lực nâng $$\vec{F}_n$$. Lực hấp dẫn $$\vec{F}_T = m\vec{g}$$ có độ lớn thay đổi và luôn hướng thẳng đứng xuống dưới. Lực kéo của kết nối với tốc độ $$\vec{v}$$ tương ứng với $$\vec{F}_c = -\alpha \vec{v}$$, tức là hoàn toàn giống như trường hợp trước. Lực nâng nằm trong mặt phẳng thẳng đứng và hướng vuông góc với vectơ vận tốc và độ lớn của nó, theo cái gọi là. Định lý Zhukovsky liên hệ với tốc độ bởi sự tương ứng $$\vec{F}_n = \beta v^2$$. Cả ba lực đều tác dụng vào trọng tâm, nằm trong mặt phẳng thẳng đứng của khung máy bay đối xứng. Câu hỏi đặt ra là quỹ đạo bay sẽ như thế nào nếu tàu lượn được phóng từ điểm A₀ với tốc độ ban đầu $$\vec{v}_0$$ một góc φ so với đường chân trời (hình 7)?

Quỹ đạo được xây dựng theo cách giống hệt như trước, chỉ bây giờ để tìm tổng gia tốc, bạn sẽ phải thêm không phải hai vectơ mà là ba: $$\vec{g}, \vec{a}_c$$ và $$\vec{a}_n$$, trong đó gia tốc $$\vec{a}_c = \vec{F}_n/m$$ do lực nâng gây ra hướng vuông góc với vectơ vận tốc $$\vec{v}$$ và có độ lớn bằng ($\beta/m)v^2$. Để đơn giản hóa việc xây dựng, rất hữu ích khi sử dụng những giá trị cho trong hình 7 đồ thị biểu diễn sự phụ thuộc của $$a_c$$ và $$a_n$$ vào $$\vec{v}$$.

Việc xây dựng quỹ đạo tàu lượn, như bạn có thể thấy, mặc dù cồng kềnh nhưng không hề phức tạp. Hãy nhìn xem chúng ta có một đường cong tuyệt vời như thế nào! Tàu lượn của chúng tôi đã mô tả một “vòng chết” thực sự! Trong trường hợp này, chỉ có một vòng, nhưng về nguyên tắc, tàu lượn có thể mô tả một số vòng như vậy, sau đó nó chuyển sang chế độ vòng lặp “rung rinh” đặc trưng: nó rơi xuống, sau đó lấy lại độ cao và giảm dần biên độ của những “điểm lõm” như vậy, điều chỉnh chuyến bay của nó và di chuyển đều dọc theo một đường thẳng nghiêng nhất định.

⟦folio 30⟧

Vì vậy, chúng tôi đã xây dựng một quỹ đạo và thu được mô tả về các đặc điểm đặc trưng nhất của chuyến bay của tàu lượn đối xứng, mặc dù thực tế là lời giải bài toán chính xác về tàu lượn (lời giải của một hệ phương trình vi phân phức tạp) là hoàn toàn không thể dịch sang ngôn ngữ dễ hiểu đối với học sinh.

Người đọc tinh ý có thể sẽ nhận thấy rằng máy bay giấy khác với chiếc tàu lượn lý tưởng ở một số khía cạnh mà chúng ta đã xem xét. Ví dụ, một chiếc máy bay có thể không đối xứng hoàn hảo: nó có thể có lực hấp dẫn, lực nâng và lực cản không khí khác nhau tác động lên cánh phải và cánh trái. Điều này dẫn đến thực tế là trong chuyến bay, một cánh của máy bay sẽ ở vị trí cao hơn cánh kia và máy bay bắt đầu, như thể đang ở trên một mặt phẳng nghiêng, "trượt" về phía cánh đã hạ xuống.

Với một cú “trượt” ngang như vậy, mũi và đuôi máy bay sẽ chịu lực cản không khí không đồng đều nên máy bay bắt đầu quay quanh một trục thẳng đứng, tức là nó sẽ không bay thẳng về phía trước mà quay sang phải hoặc sang trái. Tóm lại, ngoài việc xem xét sự “lắc lư” và “lắc lư” của tàu lượn trong mặt phẳng thẳng đứng, chúng ta còn thêm các ngã rẽ sang phải hoặc trái.

Vì các loại lực khác nhau tác dụng lên máy bay phụ thuộc vào tốc độ một cách khác nhau nên bán kính quay vòng và thậm chí cả hướng của nó cũng sẽ phụ thuộc vào tốc độ. Hành vi của máy bay rẽ phải ở tốc độ cao và sang trái ở tốc độ thấp hóa ra lại đặc biệt thú vị. Hãy phóng một số máy bay thuộc nhiều loại khác nhau, làm quen với chuyến bay của chúng - và bạn sẽ thấy rằng phần lớn hành vi của chúng giờ đây sẽ dễ hiểu hơn đối với bạn.

Về nguyên tắc, bằng cách sử dụng phương pháp được mô tả, có thể xem xét bài toán phức tạp hơn nữa liên quan đến sự phát triển của máy bay. Ví dụ, một chuyến bay trên máy bay. Để làm được điều này, chỉ cần nhớ rằng máy bay cũng là một chiếc tàu lượn, chỉ khác là có động cơ. Do đó, bằng cách cộng thêm các lực đã xét ở bài toán về độ rung của tàu lượn, một hằng số độ lớn của lực đẩy chuyển động $\vec{F}$, hướng dọc theo vectơ vận tốc, chúng ta sẽ có thể xây dựng được đường bay của máy bay. Nếu chúng ta tưởng tượng rằng một phi công ngồi trong buồng lái của chiếc máy bay này và điều khiển động cơ và thang máy (tức là thay đổi các giá trị $\vec{F}$ và tham số $\beta$), thì chúng ta thậm chí có thể mô phỏng quá trình bay lên của máy bay trong chuyến bay có kiểm soát. Bằng cách bật và tắt định kỳ động cơ của những chiếc máy bay như vậy, người đọc kiên nhẫn có thể tương đối dễ dàng đảm bảo rằng máy bay chuyển sang chế độ bay giống như sóng, gợi nhớ đến chuyến bay của chim ngực, chim yến và các loài chim nhỏ khác. Và bằng cách thay đổi khối lượng $m$ ở chế độ này và tăng các tham số $\alpha$ và $\beta$, bạn có thể thu được quỹ đạo tái tạo khá chính xác khả năng xaotic.
