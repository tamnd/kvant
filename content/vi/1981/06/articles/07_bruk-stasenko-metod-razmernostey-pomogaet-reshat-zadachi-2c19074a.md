---
id: 1981-6-bruk-stasenko-metod-razmernostey-pomogaet-reshat-zadachi-2c19074a
issue: kvant_1981_6
year: 1981
number: "6"
title: Phương pháp thứ nguyên giúp giải bài toán
authors:
  - Брук Ю. М.
  - Стасенко А. Л.
rubric: osnovnye-stati
page_first: 13
page_last: 20
page_labels: 11-18
tag: KEUR
lang: vi
source: kvant_digital
extraction: vision
content_sha256: ac3f78dc87051e0b8d8cf954933174b85d4f338e20126866884b8ebaa8d0c094
prompt_sha256: draft-1
translated_from: content/ru/1981/06/articles/07_bruk-stasenko-metod-razmernostey-pomogaet-reshat-zadachi-2c19074a.md
source_content_sha256: 4f4426bb0074749ba514e2d600f04265c3cf78ec6a869182ecc7701f5de29bf9
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 11⟧

Y. Brook, A. Stasenko

Phương pháp thứ nguyên đặt giải bài toán

Trong vật lý... không có chỗ cho những suy nghĩ trống rỗng... Quả thực, khái niệm về bản chất của hiện tượng này hay hiện tượng kia phải tiếp nhận những định luật cơ bản từ những thông điệp của chiều không gian.

E. Fermi

Giới thiệu. Ý tưởng chính

Hầu hết mọi bài thuyết trình tại các hội thảo hoặc hội nghị khoa học nơi thảo luận về công trình lý thuyết hoặc thực nghiệm mới đều bắt đầu bằng phần mô tả và đánh giá định tính về tác động mà diễn giả muốn nói đến. Hơn nữa, trong một báo cáo, bài giảng hoặc bài báo rất chi tiết, không thể nói về tất cả các chi tiết thử nghiệm hoặc tất cả các thủ thuật lý thuyết cần thiết để thực hiện công việc, vì lời giải cái này hay cái kia bài toán. Nhưng có những câu hỏi luôn cần được nói ra mà không cần được chứng minh bằng câu hỏi của người hầu hay độc giả.

Những câu hỏi như vậy luôn luôn và chủ yếu bao gồm việc đánh giá thứ tự độ lớn của hiệu ứng dự kiến, các trường hợp giới hạn đơn giản và bản chất của mối liên hệ chức năng trong việc xác định hiện tượng độ lớn. Tất cả những câu hỏi này đều có liên quan chặt chẽ với nhau, việc phân tích chúng về cơ bản là cái mà chúng ta gọi là mô tả định tính về tình hình vật lý.

Một trong những phương pháp phân tích hiệu quả nhất là phương pháp thứ nguyên. Chúng ta sẽ xem xét những điều cơ bản của nó trong bài viết này. Sẽ không quá lời khi nói rằng phương pháp thứ nguyên có “hiệu quả tối đa”, tiết kiệm hàng núi giấy cho các nhà lý thuyết cũng như tiền bạc và thời gian cho những người thực nghiệm. Đánh giá nhanh quy mô của hiện tượng đang nghiên cứu,

⟦folio 12⟧

xây dựng sơ đồ cơ bản của một thí nghiệm, thu được các phụ thuộc về chất lượng và chức năng, khôi phục các công thức bị lãng quên trong các kỳ thi - đây chỉ là một số ưu điểm và ứng dụng của phương pháp thứ nguyên.

Phân tích thứ nguyên đã được sử dụng trong vật lý kể từ thời Newton. Chính Newton là người đã xây dựng nguyên lý tương tự, liên quan chặt chẽ đến phương pháp đo kích thước, mà bây giờ chúng ta sẽ minh họa bằng một ví dụ rất đơn giản và dễ hiểu.

Hãy tưởng tượng rằng một vật có khối lượng $m$ chuyển động theo đường thẳng dưới tác dụng của một lực không đổi $F$. Nếu tốc độ ban đầu của vật bằng 0 và tốc độ ở cuối đoạn dài hoàn chỉnh $s$ bằng $v$, thì chúng ta có thể viết đẳng thức biểu thị bằng định luật bảo toàn năng lượng: $mv^2/2 = Fs$. Giữa các giá trị $v$, $F$, $m$ và $s$ tồn tại. Rất thường xuyên (nhưng tất nhiên không phải luôn luôn như vậy!) sự phụ thuộc hàm của một đại lượng vật lý có các đặc tính của định luật lũy thừa. Hãy giả sử rằng đây là trường hợp trong ví dụ của chúng tôi. Chúng ta có thể nói điều này theo cách khác: chúng ta tin rằng công thức xác định tốc độ $v$ là hàm của $F$, $m$ và $s$ có ​​dạng lũy ​​thừa $v \sim F^x m^y s^z$.

Đây $x$, $y$ và $z$ là một số con số mà chúng tôi vẫn chưa xác định được. Dấu ~ có nghĩa là vế trái của công thức tỷ lệ với vế phải, tức là $v = kF^x m^y s^z$, trong đó $k$ là một hệ số bằng số. Vì $k$ là đại lượng không thứ nguyên nên đương nhiên không thể xác định hệ số này bằng phương pháp thứ nguyên.

Tất nhiên, bên trái và bên phải của sự tương ứng (*) phải thay đổi theo cùng một đơn vị, nghĩa là chúng có cùng kích thước. Chúng tôi sẽ thay đổi $v$ thành “m/s”, $F$ thành “H”, $m$ thành “kg” và $s$ thành “m”.

Nói cách khác, chúng ta chọn thứ nguyên của các đại lượng $v$, $F$, $m$ và $s$ như sau: $[v] = m/c = m \cdot c^{-1}$, $[F] = H = k \cdot m \cdot c^{-2}$, $[r] = k \Gamma$, $[s] = m$. (Ký hiệu [A] biểu thị thứ nguyên của đại lượng $A$.) Ta viết điều kiện để kích thước bên trái và bên phải của hàm số (*) bằng nhau:

$$m \cdot c^{-1} = k \Gamma^x \cdot m^x \cdot c^{-2x} \cdot k \Gamma^y \cdot m^z = k \Gamma^{x+y} \cdot m^{x+z} \cdot c^{-2x}.$$

Lưu ý rằng bây giờ chúng ta đã viết được đẳng thức. Không có kg nào ở bên trái cả, nên chắc chắn không có kg nào ở bên phải. Điều này có nghĩa là

$$x + y = 0.$$

Ở bên phải, mét có lũy thừa $x + z$ và ở bên phải - có lũy thừa là 1, do đó, $x + z = 1$.

Tương tự, từ việc so sánh số mũ của giây, $-2x = -1$ suy ra.

Các phương trình chúng ta thu được giúp tìm được các số $x$, $y$ và $z$:

$$x = 1/2, \quad y = -1/2, \quad z = 1/2.$$

Bây giờ chúng ta chỉ cần viết ra công thức cuối cùng

$$v \sim \left( \frac{F}{m} \right)^{1/2} s^{1/2}.$$

Bằng cách bình phương bên trái và bên phải của sự tương ứng này, chúng ta thấy rằng $v^2 \sim \frac{F}{m} s$ hoặc $mv^2 \sim Fs$. Ở công thức cuối cùng, người đọc có thể dễ dàng nhận ra định luật bảo toàn năng lượng mặc dù không có hệ số bằng số.

Nguyên lý tương tự do Newton xây dựng là tỷ lệ $v^2/s$ tỷ lệ thuận với tỷ lệ $F/m$. Ví dụ: chúng ta hãy lấy hai vật có khối lượng khác nhau $m_1$ và $m_2$; chúng ta sẽ tác động lên chúng bằng các lực khác nhau $F_1$ và $F_2$, nhưng sao cho tỷ lệ $F_1/m_1$ và $F_2/m_2$ sẽ giống nhau. Dưới tác dụng của các lực này, cơ thể bắt đầu chuyển động. Nếu vận tốc ban đầu của các vật thể công bằng 0 thì vận tốc mà các vật thu được trên một đoạn đường có độ dài $s$ sẽ bằng nhau. Chúng ta đi đến định luật tương tự bằng cách sử dụng sự bằng nhau về kích thước của bên phải và bên trái của công thức mô tả mối quan hệ lũy thừa của giá trị

⟦folio 13⟧

kết nối tốc độ cuối cùng với các giá trị lực, khối lượng và chiều dài đường đi.

Điều đáng nói ở đây là, mặc dù phương pháp đo kích thước về cơ bản đã được giới thiệu trong quá trình xây dựng nền tảng của cơ học cổ điển, nhưng ứng dụng hiệu quả của nó cho lời giải vật lý bài toán đã bắt đầu vào cuối thế kỷ này - vào đầu thế kỷ của chúng ta. Phần lớn công lao cho việc quảng bá phương pháp này và lời giải với sự trợ giúp của nó, một số bài toán thú vị và quan trọng thuộc về nhà vật lý John William Strutt (Lord Rayleigh). Vào năm 1915, Rayleigh đã viết: "Tôi thường ngạc nhiên vì ngay cả nhiều nhà khoa học vĩ đại cũng ít chú ý đến nguyên lý tương tự vĩ đại. Điều thường xảy ra là các kết quả nghiên cứu cần mẫn được trình bày dưới dạng những "định luật" mới được phát hiện, tuy nhiên, có thể thu được bằng thực nghiệm trong vòng vài phút."

Trong vật lý học của chúng ta, người ta không còn có thể bị buộc tội là bỏ bê hoặc không chú ý đầy đủ đến nguyên lý tương tự và phương pháp đo kích thước. Chúng ta sẽ phân tích dưới đây hai bài toán cổ điển, thường được gọi là bài toán Rayleigh. Bài toán được Rayleigh xem xét, bao gồm cả sự trợ giúp của thông báo thứ nguyên, tất nhiên là lớn hơn nhiều, nhưng những thứ mà chúng ta sẽ nói đến là khá điển hình. Bằng cách sử dụng các ví dụ này và các ví dụ khác, chúng ta sẽ tìm hiểu chi tiết hơn về thời điểm và cách thức sử dụng phương pháp thứ nguyên cho lời giải bài toán.

Bài toán Rayleigh về dao động của quả bóng trên một sợi dây

Cho một sợi dây căng giữa hai điểm A và B. Lực căng của sợi dây là F. Ở giữa sợi dây này tại điểm C có một quả cầu nặng. Độ dài đoạn AC (và CB tương ứng) bằng l. Khối lượng M của quả cầu lớn hơn khối lượng của sợi dây rất nhiều. Sợi dây được kéo lại và thả ra. Rõ ràng là quả bóng sẽ dao động. Nếu biên độ của những dao động này nhỏ hơn nhiều so với chiều dài của dây thì quá trình đó sẽ điều hòa.

Rayleigh đã chỉ ra cách tìm sự phụ thuộc của tần số của các dao động ω này vào lực căng của dây F, khối lượng của quả cầu M và kích thước l. Bây giờ chúng ta sẽ tái tạo lại lý luận của anh ấy.

Giả sử rằng các đại lượng ω, F, M và l có liên hệ theo định luật lũy thừa:

$$\omega \sim F^x M^y l^z.$$  (**)

Các số mũ x, y và z là các số ta cần xác định. Như trong bài toán, đã thảo luận ở trên, chúng ta viết ra thứ nguyên của các đại lượng mà chúng ta quan tâm trong một số hệ đơn vị, ví dụ: trong hệ SI:

$$[\omega] = c^{-1}, [F] = H = \kappa \Gamma \cdot M \cdot c^{-2}, [M] = \kappa \Gamma, [l] = m.$$

Nếu công thức (**) biểu thị một mẫu hình vật lý thực thì kích thước bên phải và bên trái của công thức này phải trùng nhau, nghĩa là chúng phải thỏa mãn đẳng thức

$$c^{-1} = \kappa \Gamma^x \cdot M^x \cdot c^{-2x} \cdot \kappa \Gamma^y \cdot M^z = \kappa \Gamma^{x+y} \cdot M^{x+z} \cdot c^{-2x}.$$

Vế trái của phương trình này hoàn toàn không bao gồm mét và kilôgam và giây được tính theo lũy thừa -1. Điều này có nghĩa là các điều kiện sau phải được thỏa mãn đối với các số x, y và z:

$$x + y = 0, x + z = 0, -2x = -1.$$

Giải hệ này, ta tìm được:

$$x = 1/2, y = -1/2, z = -1/2.$$

Kể từ đây,

$$\omega \sim F^{1/2} M^{-1/2} l^{-1/2}.$$

Chúng tôi đã nói trước đó rằng do hệ số không đáng kể nên chúng tôi phải thay thế dấu bằng bằng ký hiệu tỷ lệ. Thật thú vị để lưu ý

⟦folio 14⟧

tuy nhiên, công thức chính xác cho tần số chỉ khác với những gì chúng tôi tìm thấy $\sqrt{2}$ lần ($\omega^2 = 2F/Ml$). Nói cách khác, trong trường hợp này, chúng ta có thể coi rằng chúng ta đã thu được ước tính cho $\omega$ không chỉ về mặt chất lượng (theo nghĩa bản chất của sự phụ thuộc vào giá trị của $F$, $M$ và $l$), mà còn về mặt định lượng. Theo thứ tự độ lớn, sự kết hợp định luật lũy thừa tìm được của $F$, $M$ và $l$ cho giá trị tần số chính xác. Chúng tôi sẽ tiếp tục quan tâm đến thứ tự ước tính cường độ. Trong các bài toán đơn giản, thường thì các hệ số không thể xác định được bằng phương pháp thứ nguyên có thể được coi là số bậc một. Tất nhiên, cần lưu ý rằng đây không phải là một quy tắc nghiêm ngặt. Kết luận cuối cùng về giá trị của hệ số chỉ có thể được rút ra từ một số thông báo bổ sung. (Nhân tiện, xin lưu ý rằng trong ví dụ được thảo luận ở phần “Giới thiệu”, hệ số bằng số trong công thức xác định tốc độ $v$ là hàm của lực, khối lượng và độ dài đường đi cũng là một số bậc một.)

Không cần phải nói rằng khi quyết định bài toán về số lượng dây, ngay từ đầu chúng ta có thể giới thiệu các tần số $\omega$ và chu kỳ dao động $T = 2\pi/\omega$ liên kết duy nhất với nó và tìm sự phụ thuộc định luật lũy thừa của chu kỳ $T$ vào độ căng của dây $F$, khối lượng $M$ và kích thước $l$. Hệ số $2\pi$ ở đây hoàn toàn không “làm hỏng” (nhưng cũng không “cải thiện”!) Công thức thu được từ thông điệp về kích thước - xét cho cùng, chúng ta vẫn không thể viết một hệ số số nếu không có phương trình rung động lời giải chính xác.

Điều tò mò là trong một ví dụ khác, rất đơn giản và nổi tiếng - về số lượng của ma trận toán học - về tần số dao động, từ các thông điệp thứ nguyên, chúng ta đã nhận được công thức chính xác $\omega^2 = g/l$. Phương pháp kích thước không xác định, hệ số số bằng một trong trường hợp này. Nếu ngay từ đầu chúng ta tìm kiếm mối liên hệ giữa chu kỳ dao động của ma trận toán học với độ dài $l$ của nó và gia tốc rơi tự do $g$, thì chúng ta sẽ đi đến công thức $T \sim \sqrt{l/g}$, khác với công thức chính xác một hệ số $2\pi$. Nhưng ngay cả từ ví dụ này cũng không hề suy ra rằng khi sử dụng phương pháp thứ nguyên, tần số dao động có sự hiện diện nào đó của một chu kỳ; nguồn gốc của thừa số $2\pi$ chỉ được kết nối với định nghĩa của $\omega = 2\pi/T$.

Chúng ta hãy quay lại việc xem xét bài toán của Rayleigh và một lần nữa hình thành các giả định cho phép chúng ta giải phương pháp thứ nguyên của nó.

Đầu tiên, chúng tôi giả định rằng có một mối liên hệ thực sự giữa các đại lượng $\omega$, $F$, $M$ và $l$. Thứ hai, chúng tôi tin rằng công thức thể hiện mối quan hệ này có dạng lũy ​​thừa: $\omega \sim F^x M^y l^z$.

Phương pháp thứ nguyên giúp tìm ra hàm ý nghĩa giữa các đại lượng vật lý khác nhau, nhưng chỉ trong những trường hợp mà những ý nghĩa này là độ. May mắn thay, có khá nhiều giá trị như vậy trong tự nhiên và phương pháp đo kích thước sẽ giúp ích rất nhiều cho chúng ta.

**Quy tắc $N—K=1$**

Khái niệm thứ nguyên của một đại lượng vật lý được đưa ra khi một số đại lượng vật lý cơ bản đã được chọn và đơn vị đo của chúng đã được thiết lập. Trong cơ học, chúng ta coi khối lượng, độ dài và thời gian là những đại lượng cơ bản truyền thống. Trong hệ SI, các đại lượng này được đo tương ứng bằng kilôgam, mét và giây, trong hệ thống GHS - tính bằng gam, centimet và giây.

Chúng ta hãy nhớ lại rằng đơn vị đo lường chính trong mỗi hệ thống (các thứ nguyên chính) là số đo (thứ nguyên) của các đại lượng chính. Đơn vị đo của tất cả các đại lượng không cơ bản khác được thể hiện thông qua các đơn vị đo cơ bản. Ví dụ, trong hệ SI, đơn vị của lực “Newton” là $\text{kg} \cdot \text{m/c}^2$, đơn vị năng lượng “Joules” là $\text{kg} \cdot \text{m}^2/c^2$; trong hệ thống GHS, chúng lần lượt là “dyna” - $\text{г} \cdot \text{cm/c}^2$ và “ergg” - $\text{г} \cdot \text{cm}^2/c^2$. Các đơn vị như vậy được gọi là tùy ý.

Nếu chúng ta xem xét bài toán, trong đó các đại lượng phi cơ học được vật lý hóa (ví dụ: điện tích, nhiệt độ, v.v.), chúng ta có thể tăng số lượng đại lượng cơ bản. Trong hệ SI, các đại lượng chính bao gồm dòng điện (đo bằng Ampe), nhiệt độ (đơn vị đo - Kelvin), v.v.

Nói chung, các đại lượng và đơn vị đo lường cơ bản có thể được chọn theo nhiều cách khác nhau. Phần lớn phụ thuộc vào sự thuận tiện, truyền thống cũng như các tiêu chuẩn và quy ước hiện có. Điều rất quan trọng chúng ta cần lưu ý là phương pháp thứ nguyên có thể được sử dụng trong bất kỳ hệ đơn vị nào. Tất nhiên, mỗi lần, các biểu thức về thứ nguyên của một đại lượng phải được viết theo cùng một hệ thống đã chọn trước.

Hãy tưởng tượng rằng tại một số bài toán chúng ta cần tìm hàm ý nghĩa giữa các giá trị $N$. Giả sử rằng ý nghĩa này có đặc tính định luật lũy thừa, chúng ta có thể cố gắng giải bài toán bằng phương pháp thứ nguyên. Nếu thứ nguyên của tất cả các đại lượng $N$ được biểu thị thông qua thứ nguyên của đại lượng cơ bản $K$ và nếu đây là $N—K=1$, thì sẽ có một công thức duy nhất xác định mối quan hệ lũy thừa giữa các đại lượng $N$,

⟦folio 15⟧

và công thức này có thể được tìm thấy bằng phương pháp kích thước.

Không khó để kiểm chứng điều này. Chúng ta viết dạng tổng quát của công thức ban đầu như sau: ở bên trái có một trong các đại lượng được nâng lên lũy thừa 1, và ở bên phải là tích lũy thừa của các đại lượng $N-1$ còn lại. Số mũ vẫn chưa được biết. Tổng số chỉ số chưa biết cũng là $N-1$. Để xác định các chỉ số này, chúng ta cần phương trình $N-1$. Chúng ta thu được từng phương trình bằng cách so sánh số mũ ở bên trái và bên phải của một trong các chiều chính. Nếu bài toán của chúng tôi chứa chính xác $N-1$ thứ nguyên cơ bản, chúng tôi sẽ nhận được chính xác số phương trình mà chúng tôi cần. Các phương trình này là tuyến tính, sự tồn tại và duy nhất của hệ lời giải của các phương trình đó đảm bảo cho chúng ta sự tồn tại và duy nhất của công thức lũy thừa ban đầu. Quy tắc này được minh họa rõ ràng bằng các ví dụ trên. Khi viết công thức $v \sim F^x m^y s^z$ hoặc $\omega \sim F^x M^y l^z$, mỗi lần đặt tên cho đại lượng $N=4$, số chỉ tiêu chưa biết $N-1=3$ trùng với số thứ nguyên cơ bản $K=3$ (kg, m, s). Hệ ba phương trình tuyến tính cho ba tên chưa biết là những phương trình duy nhất lời giải, các công thức cuối cùng cho $v$ và $\omega$ cũng là những phương trình duy nhất có thể có. Do đó, đối với bốn đại lượng hoạt động, chỉ có thể xây dựng một công thức nếu số thứ nguyên cơ bản tìm thấy trong bài toán là ba.

Bài toán Rayleigh về dao động của một giọt hình cầu

Hãy để một giọt chảy ra khỏi lỗ tròn. Hoàn toàn tự nhiên khi cho rằng ở trạng thái cân bằng, giọt nước phải có dạng hình cầu - năng lượng bề mặt là tối thiểu và bất kỳ hệ thống nào cũng có xu hướng chuyển sang trạng thái có năng lượng tối thiểu. Hơn nữa, những biến dạng rất nhỏ của giọt nước sẽ dẫn đến thực tế là các lực căng bề mặt sẽ “ép” nó dao động - hình dạng của giọt nước sẽ có tính tuần hoàn.

Cơm. 2.

thay đổi về thể chất. Chúng ta giả định rằng các dao động tiếp tục trong thời gian dài và độ suy giảm của chúng nhỏ. Chúng tôi quan tâm đến câu hỏi về tần suất (hoặc thời gian) của quá trình. Tần số này có thể phụ thuộc rất nhiều vào độ lớn của sức căng bề mặt của chất lỏng $\sigma$, mật độ của chất lỏng $\rho$ và bán kính giọt nước $r^*$. Chúng ta sẽ tìm sự phụ thuộc này dưới dạng

$$\omega \sim \sigma^x \rho^y r^z.$$

Hãy viết thứ nguyên của tất cả các đại lượng trong hệ SI:

$$[\omega] = c^{-1}, [\sigma] = H \cdot M^{-1} = \kappa \Gamma \cdot M \cdot c^{-2} \cdot M^{-1} = \kappa \Gamma \cdot c^{-2},$$

$$[\varrho] = \kappa \Gamma \cdot M^{-3}, [r] = M.$$

Số lượng đại lượng, mối liên hệ giữa chúng ta đang tìm kiếm, lại lớn hơn số chiều cơ bản một đơn vị. Quy tắc $N-K=1$ cho chúng ta biết rằng công thức tần số phải tạo ra một công thức duy nhất. Phương trình xác định $x, y$ và $z$ thu được từ sự tương ứng:

$$c^{-1} = \kappa \Gamma^x \cdot c^{-2x} \cdot \kappa \Gamma^y \cdot M^{-3y} \cdot M^z = \kappa \Gamma^x + y \cdot c^{-2x} \cdot M^{-3y + z}.$$

Với ba số chưa biết có ba phương trình:

$$-2x = -1, x + y = 0, -3y + z = 0.$$

Hệ thống này có một lời giải

$$x = 1/2, y = -1/2, z = -3/2.$$

Cuối cùng, công thức chúng ta quan tâm về tần số dao động được viết như sau:

$$\omega \sim \sqrt{\frac{\sigma}{q r^3}}.$$

Công thức này cũng gợi ý khả năng của một phương pháp xác định bằng thực nghiệm giá trị $\sigma$. Để làm điều này, bạn cần biết mật độ của chất lỏng $\rho$, bán kính giọt nước $r$ và xác định tần số $\omega$ bằng thí nghiệm. Việc chúng ta không biết hệ số trong công thức này không phải là một bất lợi về dịch vụ. Chúng ta có thể định nghĩa nó, ví dụ, tiếp tục uống với chất lỏng, điều đó thật tuyệt

*) Có lẽ đến đây bạn có một câu hỏi: tại sao không giả sử rằng tần số cũng có thể phụ thuộc vào lực hấp dẫn tác dụng lên giọt nước? Câu hỏi này rất tự nhiên và chúng ta chắc chắn sẽ thảo luận về nó. Nhưng một lát sau.

⟦folio 16⟧

Sức căng bề mặt đã biết.

Về cơ bản, bây giờ chúng ta phải đối mặt với một trường hợp mô hình hóa đơn giản - dao động của một giọt chất lỏng đang nghiên cứu có thể được mô phỏng bằng dao động của một giọt chất lỏng đã biết σ và q. Ở đây chúng ta cũng có thể nói về sự giống nhau về dao động của công thức rơi vào hai chất lỏng khác nhau.

Bạn có thể tích phân công thức tính tần số dao động ω theo cách khác. Hãy viết lại nó như thế này: $(\sigma/\rho) \sim r^3 \omega^2$.

Coi σ và q là các tham số đặc trưng cho chất lỏng và do đó giống hệt nhau đối với các giọt chất lỏng này có kích thước khác nhau, chúng ta đi đến kết luận rằng các chu kỳ $T_1 = 2\pi/\omega_1$ và $T_2 = 2\pi/\omega_2$ của dao động của hai giọt cùng một chất lỏng và bán kính $r_1$ và $r_2$ của những giọt này có liên quan với nhau bởi sự tương ứng

$$\frac{T_1^2}{T_2^2} = \frac{r_1^3}{r_2^3}$$

- bình phương chu kỳ dao động của hai giọt nước được coi là lập phương có kích thước của chúng! Điều này có làm bạn nhớ đến một trong những định luật của Kepler không? Làm ơn, sự tương tự còn xa lắm, nhưng trong cả hai trường hợp, chúng ta đang nói về các quá trình tuần hoàn!

Hãy đưa ra một nhận xét nữa. Ngay khi viết ra một tập hợp các đại lượng, mối liên hệ giữa chúng mà chúng ta muốn tìm, chúng ta cần nhận thức được điều gì là cần thiết và điều gì không cần thiết đối với một hiện tượng vật lý cụ thể. Nếu chúng ta đang nói về động lực học (ví dụ: dao động), thì các đặc tính lực và khối lượng sẽ xuất hiện trong bài toán. Vai trò của vai trò đầu tiên trong bài toán về dao động của giọt nước được thực hiện bởi đại lượng σ, vai trò của vai trò thứ hai được thực hiện bởi mật độ của chất lỏng q. Về cơ bản, chúng tôi tin rằng dao động chỉ được xác định bởi sức căng bề mặt. lời giải mà chúng tôi thu được chắc chắn phù hợp nếu giọt nước dao động trong cabin của tàu vũ trụ. Nó có phù hợp ở gần Trái đất không? Chẳng phải chúng ta cũng nên tính đến lực hấp dẫn tác dụng lên giọt nước sao?

Chúng ta hãy suy nghĩ như thế này. Lực hấp dẫn là $F_T \sim \rho r^3 g$, và lực căng bề mặt là $F_{n,h} \sim \sigma r$. Rõ ràng là ở mức đủ nhỏ $r$ lực căng bề mặt lớn hơn lực hấp dẫn. Bỏ qua các thừa số, chúng ta viết ra bất đẳng thức biểu thị điều kiện để người ta có thể chạy qua trọng lực: $\sigma r \gg \rho r^3 g$. Bất đẳng thức này tương đương với: $r \ll (\sigma/\rho g)^{1/2}$. Có thể lập luận rằng đối với những giọt đủ nhỏ, trọng lực sẽ không ảnh hưởng đến dao động. Hãy tự ước tính kích thước tối đa của giọt nước mà tại đó bạn vẫn có thể sử dụng công thức mà chúng tôi thu được ở trên để tính tần số dao động.

Hạt nhân nguyên tử dao động ở tần số nào?

Hóa ra câu trả lời cho câu hỏi được đặt ra có thể là đáp số, sử dụng công thức tính tần số dao động của giọt nước.

Trong mô hình giọt của hạt nhân nguyên tử, hạt nhân được coi là một giọt vật chất hạt nhân - một “chất lỏng”, bao gồm các proton và neutron. Lõi giọt nước được giữ không bị phân hủy bởi lực căng bề mặt.

Các hạt nhân (proton và neutron) nằm bên trong hạt nhân ở trạng thái liên kết. Điều này có nghĩa là để “tách rời” chúng khỏi nhau, bạn cần tiêu tốn một lượng năng lượng nhất định. Mỗi nucleon, năng lượng này bằng $\varepsilon \approx 13 \cdot 10^{-13}$ J/nucleon. Bán kính của hạt nhân là $r \approx 10^{-14}$ m, khối lượng của proton là $m_p \approx 1,7 \cdot 10^{-27}$ kg. Chúng ta hãy thử sử dụng tất cả thông tin này để tính toán các tần số đặc trưng mà tại đó hạt nhân nguyên tử—các giọt vật chất hạt nhân—dao động*).

Đối với tần số dao động của một giọt vật chất hạt nhân, chúng ta có thể sử dụng công thức tương tự như đối với dao động của các giọt chất lỏng vật lý, giá như chúng ta đã dạy

*) Hiện nay chúng ta chỉ quan tâm đến sự phụ thuộc định tính của tần số dao động vào các thông số của hạt nhân và ước lượng định lượng theo bậc độ lớn; do đó, chúng ta có thể bỏ qua sự khác biệt giữa proton và neutron và coi khối lượng của nucleon bằng, chẳng hạn, với khối lượng của proton.

⟦folio 17⟧

đã cố gắng tính toán sức căng bề mặt của “chất lỏng hạt nhân”. Tổng năng lượng bề mặt trong mô hình giọt nước phải có cùng độ lớn với năng lượng liên kết của tất cả các hạt nằm bên trong giọt nước. Nếu số nucleon trong hạt nhân là $A$ (con số này được gọi là “số khối”), thì tổng năng lượng liên kết của tất cả các nucleon là $A\varepsilon$ và năng lượng bề mặt của hạt nhân giọt nước cũng là $A\varepsilon$ theo thứ tự độ lớn. Chia nó cho diện tích bề mặt của giọt nước $S=4\pi r^2$, chúng ta thu được ước tính về độ căng bề mặt: $\sigma \sim A\varepsilon/4\pi r^2$. Khối lượng của hạt nhân gồm $A$ nucleon vào cỡ $Am_p$, thể tích của hạt nhân là $\frac{4}{3}\pi r^3$; do đó, mật độ của “chất lỏng hạt nhân” có độ lớn bằng $\omega \sim 3Am_p/4\pi r^3$. Thay thế các biểu thức thu được cho σ và q vào công thức $\omega \sim (\sigma/\rho)^{1/2}r^{-3/2}$, chúng ta thu được kết quả mà chúng ta quan tâm:

$$\omega \sim \frac{1}{\sqrt{3}r} \left( \frac{\varepsilon}{m_p} \right)^{1/2} \sim \frac{1}{r} \left( \frac{\varepsilon}{m_p} \right)^{1/2}.$$

Các hạt “hạt nhân” điển hình có cấp độ $10^{22}c^{-1}$. Kiểm tra xem công thức viết có cho kết quả gần đúng không, hệ số bằng số không do chúng tôi xác định - theo thứ tự thống nhất.

Mét “dọc” và “ngang”
Te bài toán, mà chúng ta đã xem xét cho đến nay, đã được giải quyết một cách cơ bản, giống hệt và rõ ràng. Đừng nghĩ rằng điều này luôn luôn như vậy. Có những tình huống khi quy tắc $N-K=1$ không được thực hiện và sau đó phải dùng đến những ý tưởng mới. Một ý tưởng như vậy là người ta có thể cố gắng tăng số lượng đại lượng cơ bản, nghĩa là về cơ bản chuyển sang nghiên cứu bài toán trong một hệ thống có số lượng lớn các chiều cơ bản.

Để minh họa ý tưởng như vậy, hãy xem xét hai bài toán đơn giản.

Tất nhiên, điều đầu tiên được mọi người biết đến. Hãy tưởng tượng một quả bóng rơi từ một cái bàn có độ cao $H$ xuống sàn. Vận tốc của quả bóng tại thời điểm nó rời khỏi bàn nằm ngang và bằng $v_0$. Tất nhiên, phạm vi bay của nó có thể được liên kết với $H$ và $v_0$. Chúng tôi khuyên người đọc nên tiếp tục thực hiện những phép tính đơn giản này trước khi đọc thêm trong bài viết này. Bạn đã làm điều đó phải không? Bây giờ hãy nghĩ về điều đó: liệu có thể tìm thấy mối liên hệ giữa $H$ và $v_0$ bằng phương pháp thứ nguyên không? Hãy thử. Đặt chuyến bay tiếp theo bằng $x_0$. Ngoài $H$ và $v_0$, gia tốc rơi tự do $g$ chắc chắn là một giá trị cần thiết để xác định. Nó không nên phụ thuộc vào khối lượng của quả bóng đáp số - xét cho cùng, nó hoàn toàn là động học bài toán. Do đó, chúng ta có bốn giá trị - $x_0$, $v_0$, $H$ và $g$. Trong biểu thức kích thước của tất cả các đại lượng này, chỉ bao gồm mét và giây, nghĩa là $N=4$, $K=2$ và $N-K=2>1$! Nếu chúng ta viết $x_0 \sim v_0^a H^\beta g^\gamma$, thì với ba số chưa biết $\alpha$, $\beta$, $\gamma$ chúng ta chỉ có thể viết hai phương trình. Cuộc sống thế nào?

Hãy giới thiệu các đơn vị đo khoảng cách dọc và ngang riêng biệt: khoảng cách dọc theo trục tung $Y$ sẽ được đo bằng mét “dọc” - $M_y$, và khoảng cách dọc theo trục hoành $X$ - tính bằng mét “nằm ngang” - $M_x$. Khi đó các kích thước là:

$$[g] = M_y c^{-2}, [v_0] = M_x c^{-1}, [H] = M_y, [x_0] = M_x.$$

Cơm. 3.

⟦folio 18⟧

Bây giờ đối với $N=4$ nó đã là $K=3$ - các kích thước chính là $M_x$, $M_y$ và $c$. Công thức $x_0 \sim v_0^\alpha H^\beta g^\gamma$ cho kết quả tương ứng
$$M_x = M_x^\alpha \cdot c^{-\alpha} \cdot M_y^\beta \cdot M_y^\gamma \cdot c^{-2\gamma} = M_x^\alpha \cdot c^{-\alpha-2\gamma} \cdot M_y^\beta+y.$$
Hệ thống điều khiển
$$\alpha=1, -\alpha-2\gamma=0, \beta+\gamma=0$$
có một lời giải
$$\alpha=1, \beta=1/2, \gamma=-1/2,$$
và chúng tôi nhận được đáp số độc quyền:
$$x_0 \sim v_0 \sqrt{\Pi}/g.$$
So sánh lời giải này với kết quả bạn nhận được từ phép tính chính xác của mình.
Thứ hai là bài toán, minh họa ý tưởng tương tự, liên quan đến lý thuyết động học của chất khí. Các phân tử khí có kích thước hữu hạn và có thể dính vào nhau ngay cả trong khí hiếm. Khoảng cách trung bình mà các phân tử đi được giữa hai lần va chạm liên tiếp được gọi là độ dài tự do. Chúng tôi quan tâm đến việc độ dài tự do $l$ phụ thuộc như thế nào vào kích thước của các phân tử $r$ và nồng độ của chúng $n$.
Hãy viết kích thước: $[n] = M^{-3}, [l] = M, [r] = M$. Rõ ràng là, cố gắng kết nối $l, r$ và $n$, chúng ta lại thấy rằng quy tắc $N-K=1$ không giữ: $N=3$ và $K=1$ - trong bài toán chỉ có một chiều cơ bản - $M$.
Trong trường hợp này, việc nhập chiều dài "dọc" và "ngang" cũng rất thuận tiện. Chúng ta hãy coi các phân tử là những quả bóng có điều kiện và theo dõi một trong những quả bóng này. Hãy đồng ý đo khoảng cách dọc theo quỹ đạo của phân tử bóng bằng “mét dọc” - $M_\parallel$. Rõ ràng là những phân tử rơi vào một hình trụ có ma trận song song với quỹ đạo và đáy là tiết diện của các phân tử hình cầu vuông góc với quỹ đạo có thể “đặt” chuyển động của phân tử mà chúng ta đã chọn. Diện tích của phần này tỷ lệ với $r^2$. Điều tự nhiên là giả định trong tình huống như vậy rằng $r$ được đo bằng “mét ngang” - $M_\perp$. Sau đó, âm lượng được đo bằng đơn vị $M_\parallel \cdot M_\perp^2$ và kích thước của $n$ là $M_\parallel^{-1} \cdot M_\perp^{-2}$. Sau những khác biệt này, chúng ta có hai thứ nguyên chính - $M_\parallel$ và $M_\perp$ - cho ba giá trị $l, r$ và $n$. Điều này đã đủ để có được một công thức rõ ràng kết nối chúng. Dễ dàng kiểm tra được công thức này là:
$$l \sim 1/nr^2.$$
Bài toán và khuyến nghị
Ở trên chúng tôi đã giới thiệu các yếu tố cơ bản của phân tích bài toán bằng phương pháp thứ nguyên. Một lần nữa, chúng tôi nhấn mạnh rằng các công thức thu được từ những khác biệt như vậy thường cho phép người ta đưa ra những ước tính định lượng. Tất nhiên, ở đây cần phải có một sự thận trọng nhất định, tuy nhiên, sẽ là một tội lỗi nếu không lợi dụng thực tế là các hệ số số trong các công thức thường có trật tự thống nhất.
Không cần phải nói rằng việc đánh giá, xây dựng các mô hình đơn giản và sử dụng các phép tương tự luôn chỉ là giai đoạn đầu tiên của việc nghiên cứu các quá trình vật lý. Giai đoạn này nên được theo sau bởi một nghiên cứu chính xác hơn và nếu có thể, chính xác hơn về các hiện tượng đang được thảo luận. Chúng tôi hoàn toàn không muốn bạn có ấn tượng rằng phương pháp đo lường này rất thú vị. Trước khi sử dụng nó dưới hình thức này hay hình thức khác, chúng ta cần xây dựng một bức tranh rõ ràng về quá trình vật lý và suy nghĩ cẩn thận về những đặc điểm mà chúng ta quan tâm. Chỉ trong những điều kiện này, người ta mới có thể hy vọng thành công.
Dưới đây chúng tôi cung cấp cho bạn các kích thước độc lập bài toán.

Bài toán
1. Tìm công thức mô tả mối quan hệ giữa khối lượng của hành tinh $M$, bán kính của nó $R$ và chu kỳ quay tối thiểu của hành tinh quanh trục của nó. Xin lưu ý rằng sự tồn tại của những “quả bóng” đá granit như vậy, tức là các hành tinh, là do sự tương tác của đá granit nói riêng, trong đó có các “quả bóng”. Chu kỳ quay tối thiểu của một hành tinh có cùng khối lượng và bán kính với Trái đất là bao nhiêu? Bạn cần có được một thứ tự ước tính cường độ.
2. Kích thước tuyến tính của hai máy quay thép hình học tương tự nhau khác nhau gấp ba lần. Tần số của những Cameron này khác nhau như thế nào?
3. Tìm sự phụ thuộc của chu kỳ dao động của xung khí hình thành trong một vụ nổ chính xác dưới nước sâu, nếu biết rằng vụ nổ giải phóng năng lượng $E$ và áp suất nước là $p$. Cũng cố gắng ước tính kích thước tối đa của xung khí. Nhịp đập phụ thuộc vào độ sâu $H$ như thế nào?
