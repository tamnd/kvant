---
id: 1978-10-gik-vash-reyting-grossmeyster-2de30e52
issue: kvant_1978_10
year: 1978
number: "10"
title: Đánh giá của bạn là gì, thưa ông?
authors:
  - Гик Е. Я.
rubric: osnovnye-stati
page_first: 22
page_last: 25
page_labels: 20-23
tag: FACK
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 723fd0d2e6d9d6fb1bcf3893e0b411c309304bad7c6c21edc4cfc1350cdac180
prompt_sha256: draft-1
translated_from: content/ru/1978/10/articles/06_gik-vash-reyting-grossmeyster-2de30e52.md
source_content_sha256: 579b67c8ba5426a1849418baeeaaa9461b617d9e0a1d77c700c6416c7ce10513
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 20⟧

E. Gik

Đánh giá của bạn là gì, thưa ông?

Trên các trang «Kvant» chúng tôi chưa viết về các mối liên hệ khác nhau tồn tại giữa toán học và cờ vua. Trong bài viết này chúng ta sẽ thảo luận về hệ số Elyu, hệ số được sử dụng rộng rãi để đánh giá và dự đoán kết quả của các kỳ thủ trong các giải đấu, trận đấu hiện đại.

Vào thời xa xưa, khi chỉ có vài chục cao thủ tranh tài ở các giải cờ vua trên toàn thế giới, không khó để so sánh kết quả của các kỳ thủ ngày nay. Câu hỏi về việc ai trong số hai võ sư chơi mạnh hơn đã được giải quyết một cách đơn giản: trong một khoảng thời gian nhất định họ gặp nhau trong các giải đấu, và nếu một cơ quan quản lý mạnh hơn người kia, điều đó có nghĩa là anh ta mạnh hơn; nếu chỉ có một người ở phía trước, người ta có thể cho rằng sức mạnh của họ gần như ngang nhau; trong những trường hợp đặc biệt gây tranh cãi, trận đấu giữa họ đã bị loại.

Ngày nay cờ vua hiện đại diễn ra đồng thời ở nhiều quốc gia và thậm chí ở nhiều thành phố của một quốc gia. Chỉ riêng trong các giải đấu vòng loại quốc tế hiện đại (tức là những giải đấu được ấn định giá trị quốc tế), có hàng nghìn kỳ thủ giỏi tham gia, những người trong số họ chỉ biết nhiều về nhau qua kinh nghiệm. Trong điều kiện như vậy, việc so sánh sức mạnh của các bậc thầy trở nên khó khăn hơn.

Những nỗ lực đầu tiên nhằm xây dựng một hệ thống đánh giá sức mạnh của người chơi cờ đã có từ đầu thế kỷ này. Và vào cuối những năm 50, các thử nghiệm thực tế của một số hệ thống đã bắt đầu, dựa trên thực tế là mỗi cờ vua được gán một hệ số riêng, thay đổi từ đương đại đến hiện đại, hay nói cách khác là xếp hạng (từ xếp hạng từ tiếng Anh - "đánh giá"), được tính theo một công thức nhất định và tùy thuộc vào hệ số của đối thủ và thể hiện

⟦folio 21⟧

kết quả mong muốn. Sau nhiều năm thảo luận về các hệ số khác nhau (về cơ bản không khác nhau), Liên đoàn Cờ vua Quốc tế (FIDE) vào năm 1970 đã chính thức áp dụng hệ số riêng do giáo sư toán học người Mỹ Arpad Elo phát triển.

Trước tiên chúng ta hãy trình bày cách tính các hệ số bằng hệ thống Elo và sau đó thảo luận về một số tính năng của nó.

Đặt hệ số “cũ” của một người tham gia nhất định (tức là hệ số trước khi bắt đầu cuộc thi) là $K_{ct}$. Hệ số “mới” (hệ số sau khi kết thúc cuộc thi) $K_{now}$ được tìm bằng công thức sau:

$$K_{now} = K_{ct} + 10 (N - N_{ojk}),$$

(1) trong đó $N$ là số điểm ghi được (kết quả của ván cờ trong cuộc thi) và $N_{ojk}$ là cái gọi là cửa sổ và số điểm đã cho.

Để tính $N_{ojk}$, trước hết, hệ số trung bình $K_{cp}$ của tất cả các đối thủ trong một ván cờ nhất định được tính (trong trường hợp một trận đấu, $K_{cp}$ trùng với $K_{ct}$ của đồng đội mình), sau đó được làm tròn thành số nguyên *).

*) Các số “đường biên” (như 2377.5) được làm tròn, theo quy ước, theo bất kỳ hướng nào - ví dụ: về phía các số nhỏ hơn.

Sau đó chúng ta tìm độ lệch của hệ số $K_{ct}$ so với $K_{cp}$:

$$\Delta K = K_{ct} - K_{cp}.$$

(2)

Bây giờ từ bảng 1 đến $|\Delta K|$ cửa sổ và phần trăm số điểm đã cho được xác định:

$$h = \begin{cases} h_6, если \Delta K \geqslant 0. \\ h_m, если \Delta K < 0. \end{cases}$$

(3)

Cuối cùng, số điểm dự kiến ​​có được bằng cách làm tròn đến 0,5 điểm gần nhất theo công thức sau:

$$N_{ojk} = \frac{h}{100} \cdot m,$$

(4)

trong đó $m$ là số ván cờ mà cờ vua sẽ có mặt trong cuộc thi. Nói một cách không chính thức, $N_{ojk}$ là kết quả cờ vua đáng tin cậy nhất trong cuộc thi và $h$ là tỷ lệ phần trăm số điểm ghi được đáng tin cậy nhất; điều này giải thích sự tương ứng (4).

Lưu ý rằng ở Liên Xô, khi tính xếp hạng của cờ vua Liên Xô, hệ Elo chính thức được sử dụng từ ngày 1 tháng 1 năm 1977, với điểm khác biệt duy nhất là làm tròn trong công thức (4) được thực hiện đến 0,1 điểm.

Nếu trước khi bắt đầu chuyến tham quan, chúng ta muốn tìm $K_{i_{now}}$ của mỗi người tham gia chuyến tham quan, thì theo đẳng thức (2), chúng ta phải tính xếp hạng trung bình $K_{i_{cp}}$ của đối thủ của mỗi người tham gia ($i = 1, 2, ..., n$). Hóa ra công việc này có thể

⟦folio 22⟧

đơn giản hóa. Gọi $K_{cT}^1, K_{cT}^2, \dots, K_{cT}^n$ là xếp hạng của những người tham gia giải đấu trước khi giải đấu bắt đầu. Hãy giới thiệu số lượng

$$K_T = \frac{K_{cT}^1 + K_{cT}^2 + \dots + K_{cT}^n}{n}$$

(được làm tròn đến số nguyên gần nhất), gọi là hệ số giải đấu. Thật dễ dàng để chứng minh điều đó

$$\Delta K = \frac{n}{n-1} (K_{cT} - K_T),$$

(5)

trong đó việc làm tròn sẽ lại được thực hiện thành một số nguyên (kết quả làm tròn trong các công thức (2) và (5) là như nhau). Như vậy, thay vì tính hệ số $K_{cP}^i$ $n$ lần, chúng ta chỉ cần tìm hệ số $K_T$ một lần, sau đó sử dụng công thức (5) để xác định $\Delta K$.

Để đủ điều kiện tham gia một giải đấu quốc tế sử dụng hệ thống Elo, điều cần thiết là: 1) ít nhất 2/3 số người tham gia có xếp hạng; 2) hệ số giải đấu $K_T$ ít nhất là 2250. Nếu trước khi bắt đầu giải đấu như vậy, một trong những người tham gia chưa có xếp hạng thì anh ta sẽ nhận được hệ số ban đầu $K_0 = 2200$ (rất thuận tiện, hệ số này có thể giảm sau giải đấu). Vì $K_0$ là số nguyên và các số $N_{ojk}$ được làm tròn thành 0,5 hoặc 0,1 nên xếp hạng của người chơi cờ luôn là số nguyên và đối với Elo, chúng kết thúc bằng 0 hoặc 5.

Xem xét kỹ Bảng 1, chúng ta sẽ nhận thấy rằng phần trăm $h$ thay đổi từ hàng này sang hàng khác và khi đạt đến $h_6 = 100$ (tương ứng, $h_M = 0$) không còn thay đổi nữa (chúng ta sẽ thấy mình đang ở “vùng bão hòa”).

Để hiểu rõ hơn về Bảng 1, chúng tôi cung cấp hình ảnh đồ họa của $h$ từ $\Delta K$ và $h$ sẽ được cảm nhận theo ý nghĩa trực quan của từ “quá trình mắt mong đợi”.

Nếu tỷ lệ cược của một đấu thủ nhất định $K_{cT}$ trùng với tỷ lệ cược của đối thủ $K_{cp}$, thì anh ta dự kiến ​​​​sẽ ghi được $50\%$ điểm; do đó, đường cong cần tìm phải đi qua điểm có tọa độ $\Delta K = 0$, $h = 50$. Điều tự nhiên là coi nó đối xứng so với điểm này. Nếu $K_{cT} > K_{cp}$ thì tất nhiên là $h > 50$ và nếu $K_{cT} < K_{cp}$ thì $h < 50$. Vì $h$ thay đổi từ 0 đến 100, nên đường cong sẽ có xu hướng tiệm cận với đường $h = 100$ tại $\Delta K \rightarrow +\infty$ và tới trục x tại $\Delta K \rightarrow -\infty$.

Thống kê rất lớn về thành tích cho thấy nếu trong hai kỳ thủ chơi một ván cờ mà một người nói thế này, người này xếp hạng cao hơn người kia thì trung bình người đó ghi được 75% số điểm.

Elo đã tính đến trường hợp này khi xây dựng đường cong như sau: giả sử rằng sự khác biệt giữa hai bước liền kề trong cờ vua không chính thống là 200 đơn vị xếp hạng, anh ấy đã vẽ đường cong qua điểm có tọa độ $\Delta K = 200$, $h = 75$ (và theo đó, $\Delta K = -200$, $h = 25$).

Vì vậy, hình dạng đường cong của chúng ta khá rõ ràng (xem hình) và có thể được sử dụng để xác định các giá trị của $h$ cho $\Delta K$. Tuy nhiên, phương pháp tìm $h$ này bất tiện vì nhiều lý do. Thứ nhất, bản thân đường cong, mặc dù có những đặc tính trên, nhưng không được xác định duy nhất; thứ hai, có vô số giá trị nguyên của $\Delta K$ và chúng không thể được lập bảng; Cuối cùng, đừng thay đổi giá trị của $h$ bằng thước mỗi lần! Do đó, nảy sinh ý tưởng chia trục hoành thành một số hữu hạn các đoạn (và hai nửa khoảng vô hạn) với hằng số $h$ trên mỗi đoạn sao cho giá trị của $h$ trên các đoạn liền kề khác nhau 1.

Kết quả là, cùng với đường cong chính, chúng ta có được một “cái thang” (xem hình). Chiều cao của các bậc thang của nó bằng nhau và bằng 1, đồng thời chiều dài của chúng tăng lên khi chúng di chuyển ra khỏi tâm theo độ cao của đường cong.

⟦folio 23⟧

Tất nhiên, Bảng 1, được xây dựng bằng cách sử dụng “thang” này, có thể trông hơi khác (nếu bạn chọn các phân đoạn hẹp hơn hoặc rộng hơn một chút với $h$ cố định), nhưng điều này không có ý nghĩa cơ bản - miễn là bản chất chung của sự phụ thuộc $h$ vào $\Delta K$ được giữ nguyên.

Hiện tại, trước khi bắt đầu bất kỳ giải đấu lớn nào, các con số $N_{ojk}$ được tính cho tất cả những người tham gia, điều này giúp ước tính kết quả cuối cùng của giải đấu và khả năng phân bổ các vị trí trong đó nhiều nhất. Tuy nhiên, phương pháp dự báo phổ biến này có thể được sử dụng không chỉ trước khi bắt đầu di chuyển về phía bắc mà còn trước mỗi turims của nó. Nếu chúng ta cộng số điểm mà một người tham gia các giải đấu đã tổ chức ghi được với số điểm “hứa hẹn” với anh ta về hệ số Elue trong các giải đấu còn lại, chúng ta sẽ nhận được kết quả như mong đợi trong giải đấu, có tính đến các trò chơi đã chơi. Điều tự nhiên là tin rằng những dự báo này mô tả chính xác hơn vị trí của những người tham gia tại một thời điểm nhất định so với số điểm mà anh ta thực sự ghi được, vì chúng có tính đến thông tin về các đối thủ còn lại.

Phương pháp dự báo được đề cập có một số khó khăn về mặt kỹ thuật. Rốt cuộc, giả sử, với 22 người tham gia chuyến tham quan, để tìm các số $N_{ojk}$ trước mỗi chuyến tham quan, việc tính kết quả mong đợi sẽ được đưa ra trong bảng 21 lần. Theo cách thủ công, công việc như vậy sẽ cần vài giờ tính toán và nó chỉ có thể được bắt đầu sau lễ bốc thăm của giải đấu. Tuy nhiên, máy tính sẽ xử lý nhiệm vụ này chỉ trong một phút!

Khi áp dụng công thức (1), một nghịch lý nảy sinh, đáng để xem xét chi tiết hơn. Hãy tưởng tượng rằng bạn quyết định chơi một trận đấu với người bạn của mình, chẳng hạn như từ bữa tiệc thứ 1000. Cả hai bạn đều là những người chơi hạng nhất và có cùng đánh giá là 2000. Hãy để bạn giành được chiếc điện thoại bản đồ này với số điểm 580:420. Theo dự đoán, lẽ ra bạn phải làm cho trận đấu có kết quả hòa, tức là ghi được $N_{ojk} = 500$ điểm. Chênh lệch 80 điểm sẽ giúp bạn tăng xếp hạng thêm 800 đơn vị. Vì vậy, khi kết thúc trận đấu này, bạn sẽ nhận được xếp hạng 2800 - nhiều hơn cả chính nhà vô địch thế giới!

Không khó để nhận thấy rằng với việc tăng số lượng ván trong một trận đấu, xếp hạng của một ván cờ nói chung có thể tăng vô thời hạn, trong khi xếp hạng của một ván cờ khác có thể giảm vô thời hạn.

Do đó, mối quan hệ tuyến tính giữa kết quả của cờ vua ở phương Bắc và việc tăng thứ hạng của một người là không hoàn toàn chính đáng. Họ cố gắng thoát khỏi tình huống này bằng nhiều cách khác nhau. Phổ biến nhất trong số đó là việc đưa vào công thức (1) cùng với hệ số 10 của tham số biến $\alpha$, phụ thuộc vào số lượng lô:

$$K_{нов} = K_{ст} + \alpha (N - N_{ojk}).$$

Trong trường hợp này, nghịch lý có thể được loại bỏ, nhưng việc tính toán các hệ số trở nên phức tạp hơn đáng kể.

Nguồn gốc của nghịch lý là do các hệ số của cờ vua thực sự thay đổi không chỉ ở cuối hướng bắc mà còn trong suốt thời gian đó. Vì vậy, trong trận đấu 1000 trận đã đề cập, ngay sau khi bắt đầu, bạn sẽ dẫn đầu về điểm số, điều này sẽ dẫn đến xếp hạng của bạn tăng và xếp hạng giảm. Nếu bạn đạt trung bình 58% số điểm (theo điểm cuối cùng), thì ngay khi chênh lệch tỷ lệ của bạn đạt 60 đơn vị (2030 so với 1070), tỷ lệ cược sẽ ổn định và không thay đổi nhiều trong tương lai (chênh lệch tỷ lệ 60 đơn vị tương ứng với 58% số điểm - xem bảng 1).

Từ những điều trên, hệ thống Elyu được sửa chữa rất đơn giản - các hệ số phải được vượt qua sau mỗi trận đấu! Tuy nhiên, sự giao cắt một phần như vậy, được chứng minh bằng toán học, sẽ không phù hợp với bất kỳ ai trong thực tế. Vì vậy, việc tính xếp hạng sau một số lượng lớn trò chơi hoặc sau mỗi trò chơi là không phù hợp.

Sự thật, như mọi khi, nằm sau định nghĩa. Công thức (1) đơn giản và tiện lợi, tôi không muốn từ bỏ nó, nhưng cần phải giới hạn ở số lượng “trung bình” của lô. Bản thân Elyu tin rằng nếu $m \leq 25$ thì không có
