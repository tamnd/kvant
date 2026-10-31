---
id: 1973-5-borovinskiy-zadachi-na-maksimum-i-minimum-bff64bd0
issue: kvant_1973_5
year: 1973
number: "5"
title: Bài toán cho mức tối đa và tối thiểu
authors:
  - Боровинский Л. А.
rubric: raznoe
rubric_sub: Разное
page_first: 45
page_last: 48
page_labels: 43-46
tag: FJJE
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 0370f3c67078f08abc5a7a1efec649bdcda88fe1d6a6acdbcedea490354055d2
prompt_sha256: draft-1
translated_from: content/ru/1973/05/articles/11_borovinskiy-zadachi-na-maksimum-i-minimum-bff64bd0.md
source_content_sha256: 4dd016b9b5620eca9e1a00d477111249e11e80368e47b408361ad4ce1132b45f
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 43⟧

Nhiệm vụ
đến mức tối đa
và tối thiểu

Trong cuộc sống hàng ngày, trong các vấn đề thực tiễn và khoa học, thường nảy sinh nhu cầu xác định điều kiện để chúng ta thu được nhiều kết quả nhất khi xác định điều kiện. Ngược lại, trong các trường hợp khác, cần phải biết trong những điều kiện nào thì mục tiêu có thể đạt được với nỗ lực hoặc thời gian tối thiểu. Những điều kiện như vậy được gọi là tối ưu.

Thông thường, thậm chí không để ý đến điều đó, chúng ta quyết định bài toán xác định các điều kiện tối ưu, sử dụng kinh nghiệm sống và sự khéo léo. Tuy nhiên, sở thích và trải nghiệm cuộc sống có thể gây hiểu lầm hoặc không chính xác. Tốt nhất, họ sẽ cho chúng tôi biết những điều kiện mang lại kết quả tốt, nhưng không phải là tốt nhất. Để tìm ra điều kiện tối ưu một cách hiệu quả, cần phải sử dụng vũ khí - toán học.

Nhiều định luật vật lý có thể được hình thành dưới dạng một số nguyên tắc cực đoan, tức là yêu cầu về cực trị (tối đa hoặc tối thiểu) của các đại lượng vật lý nhất định. Ví dụ, chúng ta biết rằng trạng thái cân bằng của một hệ cơ học có thể được tìm thấy từ điểm cực trị của thế năng của hệ, và ở trạng thái cân bằng ổn định thì thế năng là tối thiểu, và ở trạng thái cân bằng không ổn định thì thế năng là cực đại. Bất cứ ai quen thuộc với nguyên lý Fermat, theo đó ông luôn đi theo hai điểm dọc theo một con đường đòi hỏi thời gian tối thiểu, tất cả các định luật quang học hình học đều có thể xuất phát từ nguyên lý này.

Có sự khác biệt đáng kể giữa các điều kiện tối ưu cho các quy trình do con người kiểm soát và các quy trình sản xuất trong tự nhiên với quy trình tự sản xuất. Trong trường hợp đầu tiên, các điều kiện tối ưu sẽ quyết định quá trình mang lại nhiều lợi nhuận nhất, nhưng không phải là quá trình duy nhất có thể thực hiện được. Và trong trường hợp thứ hai, các điều kiện cực trị trong giới hạn khả năng áp dụng của các quy luật tự nhiên sẽ xác định diễn biến duy nhất có thể xảy ra hoặc có khả năng xảy ra nhất của quá trình.

Các phép xác định phức tạp bài toán của các điều kiện tối ưu hoặc cực đoan được giải quyết bằng cách sử dụng lý thuyết vi phân, phép tính biểu thức hoặc lập trình tuyến tính.

Tuy nhiên, có nhiều phương pháp bài toán đơn giản để xác định cực trị của hàm số có thể giải được mà không cần sử dụng các lý thuyết toán học phức tạp. Đối với lời giải của chúng, bạn chỉ cần biết các thuộc tính của các phần tử của hàm (ví dụ: hàm tam thức bậc hai hoặc hàm lượng giác). Bạn cũng có thể sử dụng lý thuyết nổi tiếng:

Trung bình hình học của n số dương không lớn hơn trung bình số học của chúng, tức là

$$\sqrt[n]{x_1 \cdot x_2 \cdot \cdots \cdot x_n} \leq \frac{x_1 + x_2 + \cdots + x_n}{n},$$

và dấu bằng diễn ra moeda và molko moeda, koeda

$$x_1 = x_2 = \cdots = x_n.$$

Hãy cùng xem xét một vài bài toán cụ thể.

Bài 1. Thiết bị hồi quy điện tử lai tạo năng lượng từ nguồn moka, e. d. c. bằng E, điện trở trong và điện trở của dây nguồn cộng lại bằng r. Để thiết bị phát ra công suất cực đại thì điện trở R phải bằng bao nhiêu?

⟦folio 44⟧

Theo định luật Ohm, đối với một mạch điện hoàn chỉnh thì dòng điện bằng

$$I = \frac{E}{R + r},$$

và theo định luật Joule-Lenz, công suất phân bổ cho điện trở $R$ bằng

$$P = I^2R = \frac{E^2R}{(R + r)^2} = \frac{E^2}{R + 2r + \frac{r^2}{R}}.$$

Khi $R (R \ll r)$ nhỏ thì công suất hữu ích cũng nhỏ vì gần như toàn bộ công suất lấy từ nguồn sẽ được giải phóng vào dây cấp nguồn và trong nguồn. Nếu $R$ lớn ($R \gg r$), công suất hữu ích lại nhỏ vì dòng điện trong mạch nhỏ. Do đó, có một giá trị nhất định $R$ mà tại đó công suất hữu ích sẽ đạt mức tối đa.

Hãy xem xét biểu thức

$$R + 2r + \frac{r^2}{R} = 2r + \left(R + \frac{r^2}{R}\right).$$

Rõ ràng là công suất hữu ích đạt giá trị lớn nhất khi biểu thức này ở mức tối thiểu. Giá trị $2r$ được cho và tích của các số hạng $R$ và $\frac{r^2}{R}$ trong ngoặc đơn không phụ thuộc vào $R$ và hằng số, do đó, theo định lý đã nêu ở trên, giá trị tối thiểu của giá trị sẽ đạt được khi $R = \frac{r^2}{R}$, tức là $R = r$.

Giá trị nhỏ nhất của công suất hữu ích bằng

$$P_{\max} = \frac{E^2r}{4r^2} = \frac{E^2}{4r}.$$

Lưu ý rằng trong trường hợp này c.p. d. nguồn chỉ là 50%. Do đó, chỉ nên lấy công suất tối đa từ nguồn trong khoảng thời gian ngắn, chẳng hạn như khi bộ khởi động đang vận hành tự động. Để sử dụng hiệu quả hơn nguồn năng lượng dự trữ của nguồn hiện tại, điện trở $R$ phải lớn hơn đáng kể so với $r$. Trong trường hợp này, công suất hữu ích sẽ nhỏ hơn mức tối đa.

Đồng thời, nhưng nhằm mục đích gì? d. sẽ lớn hơn 100%. Hãy kiểm tra nó.

Bài 2. Một chiếc xe trượt có tải di chuyển dọc theo đường chân trời của bề mặt dưới tác dụng của lực $F$ tác dụng lên tâm mềm. Độ dài đường tác dụng của lực $F$ với đường chân trời là bao nhiêu để xe trượt tuyết chuyển động đều dưới tác dụng của lực nhỏ nhất? Hệ số ma sát giữa xe trượt và tuyết là $k$.

Chúng ta hãy phân tách lực $F$ thành các thành phần nằm ngang và dọc $F_x$ và $F_y$ (Hình 1). Lực áp suất bình thường của xe trượt tuyết trên tuyết bằng hiệu giữa trọng lượng của xe trượt và thành phần thẳng đứng của lực $F$:

$$N = P - F \sin \alpha. \tag{1}$$

Do đó lực ma sát

$$F_{\tau p} = kN = k(P - F \sin \alpha). \tag{2}$$

Xe trượt sẽ chuyển động đều khi có lực ngang: $F_x = F_{\tau p}$, tức là

$$F \cos \alpha = k(P - F \sin \alpha). \tag{3}$$

Từ đây chúng ta tìm thấy lực $F$ là hàm của góc $\alpha$:

$$F = \frac{kP}{k \sin \alpha + \cos \alpha}. \tag{4}$$

Rõ ràng lực $F$ sẽ nhỏ nhất tại giá trị của góc $\alpha$ tại đó giá trị trong công thức (4) là lớn nhất. Để xác định góc này ta biến đổi giá trị của biểu thức (4) sao cho

⟦folio 45⟧

nó chỉ bao gồm một hàm lượng giác của góc $\alpha$. Để làm điều này, hãy tưởng tượng hệ số ma sát $k$ là tiếp tuyến của một góc nhất định $\varphi$:

$$\text{tg} \varphi = k; \quad \varphi = \arctg k;$$

$$\sin \varphi = \frac{k}{\sqrt{1+k^2}}; \quad \cos \varphi = \frac{1}{\sqrt{1+k^2}}.$$

Vì đã cho $k$ nên góc $\varphi$ có thể được coi là đã biết. Thay (4) tg $\varphi$ thay cho $k$ rồi nhân tử số và mẫu số với cos $\varphi$, ta được

$$F = \frac{P \text{tg} \varphi}{\text{tg} \varphi \sin \alpha + \cos \alpha} =$$

$$= \frac{P \sin \varphi}{\sin \varphi \sin \alpha + \cos \alpha \cos \alpha} = \frac{P \sin \varphi}{\cos (\alpha - \varphi)} =$$

$$= \frac{P k}{\sqrt{1+k^2} \cos (\alpha - \varphi)}.$$

Bây giờ rõ ràng là lực $F$ sẽ nhỏ nhất khi $\cos (\alpha - \varphi) = 1$, tức là

$$\alpha_{\min} = \varphi = \arctg k.$$

Trong trường hợp này, giá trị tối thiểu của lực $F$ bằng

$$F_{\min} = \frac{k P}{\sqrt{1+k^2}}.$$

Từ lời giải này bài toán người ta có thể rút ra một kết luận thực tế: khi cần nâng tải trên xe trượt trên đường có hệ số ma sát cao (ví dụ: nếu đường cát), bạn cần kéo xe trượt càng ngắn càng tốt. Nếu hệ số ma sát nhỏ thì vít phải dài. Giải thích điều này. Bài toán 3. Điểm 1 và 2 di chuyển dọc theo trục $x$ và $y$ về gốc tọa độ (Hình 2). Hiện tại $t_0 = 0$ lũy thừa 1 đang ở khoảng cách $s_1 = 10$ cm,

![Рис. 2.](image)

Cơm. 3.

⟦folio 46⟧

về phía đáy vuông góc BC rồi bơi về phía phao. Người chiến thắng là người đến phao B nhanh nhất. Từ điểm nào của bờ là thuận tiện nhất để bắt đầu bơi đến phao đối với người phân loại biết rằng khi bơi dọc theo bờ cát, tốc độ của anh ta là 13 km/h và tốc độ bơi của anh ta là 5 km/h.

Gọi $x$ là khoảng cách từ điểm C đến nơi vận động viên bắt đầu bơi về phía phao. sau đó vận động viên chạy một quãng $L - x$, và đổ một quãng $\sqrt{l^2 + x^2}$. Tổng thời gian đi từ điểm xuất phát A đến phao B là

$$t = \frac{L - x}{v_1} + \frac{\sqrt{l^2 + x^2}}{v_2}.$$

Hãy để độ dài của đoạn $x$ tăng một lượng nhỏ $\Delta x$. thì thời gian chuyển động trở nên bằng nhau

$$t' = \frac{L - (x + \Delta x)}{v_1} + \frac{\sqrt{l^2 + (x + \Delta x)^2}}{v_2}.$$

Sự thay đổi về thời gian là

$$\Delta t = t' - t = -\frac{\Delta x}{v_1} + \frac{\sqrt{l^2 + (x + \Delta x)^2} - \sqrt{l^2 + x^2}}{v_2} = -\frac{\Delta x}{v_1} + \frac{l^2 + (x + \Delta x)^2 - l^2 - x^2}{v_2[\sqrt{l^2 + (x + \Delta x)^2} + \sqrt{l^2 + x^2}]} = \left\{ \frac{2x + \Delta x}{v_2[\sqrt{l^2 + (x + \Delta x)^2} + \sqrt{l^2 + x^2}]} - \frac{1}{v_1} \right\} \Delta x.$$

Cơm. 4.

Vì $\Delta x \ll x$, biểu thức của $\Delta t$ có thể bị ngủ quên. Sau đó

$$\Delta t \approx \left\{ \frac{x}{v_2 \sqrt{l^2 + x^2}} - \frac{1}{v_1} \right\} \Delta x.$$

Bởi vì $\Delta x > 0$, dấu của $\Delta t$ khớp với dấu của biểu thức trong dấu ngoặc nhọn.

Đối với $x$ ($x \to 0$ nhỏ), biểu thức trong dấu ngoặc nhọn là âm, có nghĩa là $t$ sẽ bị tiêu diệt khi $x$ tăng lên. Khi $x \gg l$ biểu thức trong dấu ngoặc nhọn là dương và thời gian tăng khi $x$ tăng. Vì hàm $\Delta t$ thay đổi liên tục khi tăng $x$, nên có một giá trị $x_m$ mà tại đó $\Delta t$ trở thành 0, nghĩa là mức giảm của $t$ khi tăng $x$ được thay thế bằng mức tăng của $t$. Giá trị này là $x_m$ và sẽ tương ứng với thời gian tối thiểu $t$.

Vì thế,

$$\frac{x_m}{v_2 \sqrt{x_m^2 + l^2}} - \frac{1}{v_1} = 0,$$

Ở đâu

$$x_m = l \frac{v_2}{\sqrt{v_1^2 - v_2^2}}.$$

Thay thế các giá trị số của tất cả các đại lượng, chúng ta thu được $x_m = 50$ m.

Độ dài $L$ trong lời giải không được sử dụng. Tuy nhiên, cần phải biết điều đó. Hãy suy nghĩ tại sao?

Trận chiến

1. Có nhiều mặt phẳng nghiêng có cùng đáy bằng $b$ nhưng có độ cao khác nhau. Ở độ cao nào $h$ thời gian để một vật trượt xuống một mặt phẳng nghiêng mà không có ma sát là nhỏ nhất?

2. Điểm trên cùng của bàn đạp ở độ cao $H$ so với mặt đất và ở độ cao $h$ hình thành bàn đạp (Hình 4). Độ cao $h$ ở độ cao nhất định $H$ phải bằng bao nhiêu để người trượt tuyết sau khi rời khỏi bàn đạp có thể bay được quãng đường lớn nhất $S$ (tính theo chiều ngang)?

Bỏ qua sức cản của không khí và không khí.
