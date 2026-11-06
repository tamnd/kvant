---
id: 1991-12-gurevich-malkov-kak-obmanut-integral-ceb93e27
issue: kvant_1991_12
year: 1991
number: "12"
title: Làm thế nào để gian lận tích phân
authors:
  - Гуревич Б.
  - Малков Р.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 47
page_last: 50
page_labels: 45-48
lang: vi
source: kvant_digital
extraction: vision
content_sha256: b36a7815a56fc1549e2ffaa8533a3b9c3eb1a17d60a7db29bedbb831116710fc
prompt_sha256: draft-1
translated_from: content/ru/1991/12/articles/14_gurevich-malkov-kak-obmanut-integral-ceb93e27.md
source_content_sha256: 2c7d261bf8f2499ce92fb8a1554ea757071561109c0c3e8338130b7e097806a8
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 45⟧

---
running_head:
folio:
---

Làm thế nào để gian lận tích phân

V. GUREVICH, R. MALKOV

Tại các cuộc thi, và đôi khi trong các kỳ thi tuyển sinh môn vật lý, có bài toán, dường như không thể giải được nếu không vượt ra ngoài phạm vi của toán học ở trường. Nhưng thường thì các chìa khóa của lời giải được chứa trong chính công thức bài toán và kết quả của các phép tính rườm rà được “ẩn” trong dữ liệu gốc, điều này giúp đơn giản hóa đáng kể tình huống. Đây là một ví dụ.

Bài toán 1. Hai khách du lịch đang đi dọc theo một con đường thẳng để vượt nhau với vận tốc 5 km/h. Khi khoảng cách giữa họ là 10 km, một con ruồi cất cánh từ vai của du khách chột mắt và bay về phía trước với vận tốc 20 km/h. Gặp chiếc thứ hai, cô quay lại và bay trở lại với tốc độ tương tự. Thế là cô ấy bay giữa hai người

Rastas trước khi họ gặp nhau. Cô ấy bay được khoảng cách bao nhiêu?

Thoạt nhìn, ở đây cần phải thêm tuần tự độ dài của các đoạn thẳng trong quỹ đạo của ruồi. Nhưng bài toán có thể giải được và không thể tóm tắt lại chuỗi nếu bạn để ý rằng con ruồi đã bay được 1 giờ (thời điểm trước khi gặp khách du lịch) với vận tốc 20 km/h nên đường đi của nó là 20 km.

Đã sử dụng ví dụ về bài toán đơn giản và nổi tiếng này, rõ ràng là không phải lúc nào cũng cần thiết phải mô tả chi tiết quy trình. Bây giờ chúng ta hãy xem xét một số bài toán phức tạp hơn.

Bài toán 2. Một chiếc thuyền có khối lượng m đang đứng yên thì bị đẩy với vận tốc v₀. Nó sẽ đi được bao xa trước khi dừng lại, nếu lực cản chuyển động tỉ lệ với tốc độ: F = - αv?

Tại bất kỳ thời điểm chuyển động nào, gia tốc của thuyền, theo định luật thứ hai của Newton, bằng

a = - α/m v,

⟦folio 46⟧

---
running_head:
folio:
---

trong đó $v$ là vận tốc của thuyền lúc này. Đây là một ví dụ về chuyển động có gia tốc thay đổi (tốc độ càng thấp thì tốc độ giảm càng chậm), trong đó, nếu điều kiện bài toán được đáp ứng lý tưởng, con thuyền sẽ chuyển động vô thời hạn (mặc dù về cuối rất chậm). Tuy nhiên, điều này không có nghĩa là quãng đường phanh sẽ là vô hạn. Làm thế nào để tìm thấy anh ta?

Chúng ta hãy nhân cả hai vế của phương trình trước với một khoảng thời gian ngắn $\Delta t$, ngoài khoảng thời gian đó những thay đổi $v$ và $a$ có ​​thể bị bỏ qua:

$$a\Delta t = -\frac{\alpha}{m}v\Delta t.$$

Bây giờ hãy lưu ý rằng $a\Delta t$ là mức tăng tốc độ $\Delta v$ trong thời gian $\Delta t$ và $v\Delta t$ là mức tăng trong đường dẫn $\Delta l$ trong cùng một thời điểm. Vì thời điểm được chọn hoàn toàn tùy ý nên ta có thể kết luận rằng để vận tốc thay đổi thành $\Delta v$ thì thuyền phải đi được một quãng đường

$$\Delta l = -\frac{m}{\alpha}\Delta v$$

(điểm trừ trong biểu thức được giải thích là do $\Delta v$ âm). Từ điều kiện, rõ ràng là trong một thời gian đủ dài, tốc độ của thuyền giảm từ giá trị ban đầu $v_0$ xuống gần như bằng không. Khi đó toàn bộ quãng đường đi được bằng

$$l = \frac{m}{\alpha}v_0.$$

Vấn đề tiếp theo - điện - bài toán được giải theo cách hoàn toàn tương tự.

Bài toán 3. Loại bí ẩn nào sẽ đi qua điện trở trong mạch như hình hình 1 sau khi đóng chìa khóa, nếu không có dòng điện đóng trong cuộn dây? Tất cả các thông số của mạch đều được biết.

Giả sử, một thời gian sau khi đóng chìa khóa, dòng điện chạy từ điểm $A$ đến điểm $B$ qua cuộn dây điện cảm $L_1$ bằng $I_1$ và qua cuộn dây điện cảm $L_2 - I_2$. Sau đó, tại bất kỳ thời điểm nào, theo định luật Ohm, chúng ta có thể viết

$$L_1\Delta I_1 = L_2\Delta I_2 + RI_2\Delta t,$$

trong đó $\Delta I_1$ và $\Delta I_2$ mức tăng hiện tại, $I_2\Delta t$ là mức tăng của mức sạc mong muốn $q$ trong một khoảng thời gian ngắn $\Delta t$. Từ đây chúng ta có được

$$\Delta q = \frac{1}{R}(L_1\Delta I_1 - L_2\Delta I_2).$$

Ngay sau khi đóng phím, cả hai điểm đều bằng 0 và ở chế độ đã đặt

$$I_1 = \frac{\mathcal{F}}{r}, I_2 = 0.$$

Kết quả của việc tổng hợp tất cả các mức tăng phí, chúng tôi thấy

$$q = \frac{L_1\mathcal{F}}{Rr}.$$

Việc biện minh chi tiết hơn về tính đúng đắn trong lý luận của chúng tôi sẽ được thực hiện tại lời giải của bài toán tiếp theo.

Bài toán 4. Một vòng đệm (hình 2) nằm trên một mặt phẳng nghiêng với góc nghiêng $a$. Nó hoàn toàn được cho một tốc độ $v_0$ dọc theo mặt phẳng ngang. Sau thời gian nào máy giặt sẽ dừng lại nếu hệ số ma sát trên mặt phẳng là $\mu$ và $\mu > tg\alpha$?

⟦folio 47⟧

---
running_head:
folio:
---

Quan trọng nhất, chúng tôi lưu ý rằng theo thời gian, tốc độ của quả bóng thay đổi cả về độ lớn và hướng. Trong mặt phẳng chuyển động, có hai lực tác dụng lên quả cầu: lực ma sát $\vec{F}_1$, hướng ngược với vận tốc và bằng

$$F_1 = \mu mg \cos \alpha,$$

và thành phần $\vec{F}_2$ của trọng lực, vuông góc với vận tốc ban đầu và bằng

$$F_2 = mg \sin \alpha.$$

Giả sử tại một thời điểm nào đó tốc độ bằng $v$ và hướng một góc $\beta$ so với góc ban đầu. Từ định luật thứ hai của Newton, ta suy ra rằng trong một khoảng thời gian ngắn $\Delta t$ tốc độ của quả bóng sẽ thay đổi một lượng

$$\Delta v = \frac{1}{m} (-F_1 + F_2 \sin \beta) \Delta t.$$

Trong trường hợp này, sự thay đổi hình chiếu của nó theo hướng của lực $\vec{F}_2$ sẽ bằng

$$\Delta (v \sin \beta) = \frac{1}{m} (-F_1 \sin \beta + F_2) \Delta t.$$

(**)

Hai đẳng thức cuối cùng (*) và (**) là những phương trình vi phân khá phức tạp, bằng cách giải phương trình nào, về nguyên tắc, có thể thu được thời gian chuyển động cần thiết của quả bóng. Nhưng điều này vượt xa phạm vi của toán học ở trường. Vì vậy, chúng tôi sẽ làm điều đó khác nhau.

Lưu ý rằng thông qua định nghĩa về thời gian, cả tốc độ $v$ và hình chiếu của nó $v \sin \beta$ sẽ trở thành 0. Thực tế này, rõ ràng từ điều kiện bài toán, có thể được sử dụng để tránh sự phức tạp của phương trình lời giải. Về mặt toán học nó được thể hiện như thế này:

$$\Sigma \Delta v = -v_0 \text{ и } \Sigma \Delta (v \sin \beta) = 0.$$

Ở đây và bên dưới, ký hiệu $\Sigma$ sẽ biểu thị tổng các giá trị của đại lượng dưới dấu này trong tất cả các khoảng thời gian nhỏ mà quá trình được phân chia. Cụ thể, thời gian cần thiết để quả bóng chuyển động trước khi dừng lại bằng

$$t = \Sigma \Delta t.$$

Hãy chia cả hai vế của phương trình (*) và (**) cho $F_2$ và $F_1$, rồi cộng các đẳng thức thu được. Chúng tôi sẽ nhận được

$$\frac{1}{F_2} \Delta v + \frac{1}{F_1} \Delta (v \sin \beta) = \frac{1}{m} \left( \frac{F_2}{F_1} - \frac{F_1}{F_2} \right) \Delta t,$$

hoặc

$$\Delta t = m \left( \frac{F_1}{F_2} - \frac{F_1}{F_2} \right) \Delta v + \frac{F_2}{F_2} \Delta (v \sin \beta).$$

Thay thế ở đây các giá trị cho $F_1$ và $F_2$ và tính tổng cả hai vế của đẳng thức, chúng ta tìm được thời gian cần thiết:

$$t = \frac{v_0}{g} \frac{\mu \cos \alpha}{\mu^2 \cos^2 \alpha - \sin^2 \alpha}.$$

Bây giờ, cuối cùng, ý chính lời giải có thể được hình thành. Nó bao gồm thực tế là một phương trình được rút ra, ở phía bên trái có sự gia tăng tức thời của giá trị mong muốn tại một thời điểm tùy ý của quá trình và ở phía bên phải có sự kết hợp tuyến tính của các gia số của giá trị, giá trị ban đầu và giá trị cuối cùng được biết hoặc biểu thị thông qua giá trị mong muốn. Tổng của tất cả các giá trị ở bên phải và bên trái của phương trình này trong tất cả các khoảng thời gian nhỏ mà quá trình được chia sẽ cho một phương trình đại số cho giá trị mong muốn. Để thuận tiện, chúng tôi sẽ tóm tắt phương pháp này bằng phương pháp lấy mẫu tổng. Điểm đặc biệt của nó nằm ở chỗ trong một số trường hợp, sẽ thuận tiện hơn cho hệ thống hội tụ không phải về một phương trình với một biến mà về một phương trình có nhiều biến, nhưng với các định nghĩa đã chọn.

Khả năng sử dụng phương pháp lấy mẫu tổng không phải lúc nào cũng giống nhau. Do đó, trong vấn đề 2 và 3, mức tăng của giá trị mong muốn, được biểu thị thông qua mức tăng của giá trị với các giới hạn thay đổi đã biết, được lấy trực tiếp từ hệ thống ban đầu. Trong bài toán 4, cần có một số phép biến đổi đại số để tách riêng mức tăng mong muốn. Nhưng trong các phép biến đổi đại số bài toán tiếp theo thôi là chưa đủ.

⟦folio 48⟧

---
running_head:
folio:
---

Nhiệm vụ 5. Trong mạch điện ở hình 3, lúc đầu các công tắc mở và tụ điện không tích điện. Tìm lượng nhiệt tỏa ra bởi điện trở có điện trở $R_2$ sau khi đóng công tắc. Tất cả các thông số của mạch đều được biết.

Giả sử tại một thời điểm nào đó sau khi đóng chìa khóa từ điểm $A$ đến điểm $B$ một dòng điện $I_1$ chạy qua điện trở thứ nhất, $I_2$ qua điện trở thứ hai và điện tích của tụ điện là $q$. Trong một khoảng thời gian ngắn $\Delta t$ mức tăng của giá trị ban đầu là

$$\Delta Q = I_2^2 R_2 \Delta t,$$

và tăng điện tích của tụ điện -

$$\Delta q = I_2 \Delta t.$$

Kể từ đây,

$$\Delta Q = I_2 R_2 \Delta q.$$

Trong phương trình cuối cùng, không có sự kết hợp tuyến tính của các gia số của một đại lượng có giá trị đầu và cuối đã biết, vì hệ số đứng trước $\Delta q$ là một đại lượng thay đổi. Nhưng từ điều kiện bài toán có thể dễ dàng tìm được giới hạn của sự thay đổi dòng điện, vì vậy chúng ta sẽ cố gắng biểu thị $\Delta Q$ thông qua số gia tức thời $\Delta I_1$ và $\Delta I_2$ của chúng. Chúng tôi làm theo điều này bằng cách sử dụng định luật Ohm:

$$\mathcal{E} - r (I_1 + I_2) = R_1 I_1,$$

$$R_1 I_1 = \frac{q}{C} + R_2 I_2,$$

hoặc

$$- r (\Delta I_1 + \Delta I_2) = R_1 \Delta I_1,$$

$$R_1 \Delta I_1 = \frac{\Delta q}{C} + R_2 \Delta I_2.$$

Biểu thị $\Delta q$ từ đây theo $\Delta I_2$, ta có

$$\Delta Q = - \frac{R_2 C}{2} \left( R_2 + \frac{R_1 r}{R_1 + r} \right) \Delta (I_2^2).$$

Vậy qua điện trở thứ hai ngay sau khi đóng phím thì bằng

$$I_2 = \frac{\mathcal{E} R_1}{R_1 r + R_2 r + R_1 R_2},$$

và giá trị cuối cùng của nó bằng 0. Do đó, tính tổng biểu thức cho $\Delta Q$ sẽ cho lượng nhiệt cần thiết:

$$Q = \frac{\mathcal{E}^2 R_1 R_2 C}{2 (R_1 + r) (R_1 r + R_2 r + R_1 R_2)}.$$

Nếu muốn, kết quả thu được có thể được khái quát hóa cho điện tích ban đầu tùy ý của tụ điện.

Như có thể thấy từ các ví dụ trên, phương pháp được đề xuất trong một số trường hợp cho phép thu gọn đáng kể các phép tính toán học và loại bỏ sự cần thiết của các phương trình vi phân lời giải. Trong các vấn đề khác, các tác giả, vốn là những người từng nộp đơn, chân thành hy vọng rằng các thành viên của ủy ban đăng ký không đủ xảo quyệt để đưa bài toán như vậy vào chương trình thi tuyển sinh. Nhưng - ai biết được?

Ở bên phải
1. Trong điều kiện bài toán 4, hãy tìm đường đi của quả bóng.
2. Trong trường tĩnh điện đồng nhất chéo (có cường độ $\vec{E}$) và từ trường (có cảm ứng $\vec{B}$) ($\vec{E} \perp \vec{B}$), một hạt có khối lượng $m$ và điện tích $q$ được giữ ở trạng thái nghỉ. Tại một thời điểm nào đó hạt được giải phóng. Tìm khoảng cách giữa đường chuyển động đã xác lập và vị trí ban đầu của hạt nếu nó chịu tác dụng của lực ma sát nhớt $\vec{F} = -\beta \vec{v}$.
3. Ở điều kiện bài toán 3, hãy tìm lượng nhiệt tỏa ra bởi điện trở sau khi đóng công tắc.
4. Trong mạch ở hình 4, đầu tiên công tắc mở, sau đó không có điện áp qua cuộn dây và tụ điện không được tích điện. Sau khi đóng công tắc, điện trở sẽ toả bao nhiêu nhiệt lượng? Tất cả các thông số của mạch đều được biết.
