---
id: 1981-11-vertgeym-igryi-s-kvadratichnyimi-funktsiyami-18187e5a
issue: kvant_1981_11
year: 1981
number: "11"
title: Trò chơi có hàm bậc hai
authors:
  - Вертгейм Б. А.
rubric: osnovnye-stati
page_first: 8
page_last: 11
page_labels: 6-9
tag: Q6FW
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 3df127c4991babfa07b01788c2368d7d7542a9cbf3a54d741da6a8c798325074
prompt_sha256: draft-1
translated_from: content/ru/1981/11/articles/03_vertgeym-igryi-s-kvadratichnyimi-funktsiyami-18187e5a.md
source_content_sha256: 234640e8479dcd5911970f8958c7e0c0f7d4f54c3d3228955b673630c518409e
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 6⟧

B. Vergeem

hoặc bên phải của bạn. Kỹ năng của họ được phản ánh trong bảng *): nếu người chơi

Trò chơi
với hàm vuông

Có thể học toán thông qua một trò chơi? Hóa ra điều đó là có thể, vì trong toán học có rất nhiều bài toán mô tả “tình huống trò chơi”.

Chúng ta sẽ giải quyết các trò chơi liên quan đến việc tìm ra giá trị lớn nhất và nhiều nhất của hàm số. Nghệ thuật tìm kiếm như vậy có ý nghĩa quan trọng trong nhiều vấn đề kinh tế, quân sự, sinh học, thể thao,…

Quyết định mười mét bằng nhau

Chúng tôi đang ở trên sân bóng. Cầu thủ A và thủ môn B đang chuẩn bị thực hiện loạt 10 cú sút ngang nhau. Người chơi sẽ đi sang phải hoặc sang trái; thủ môn đang cố đoán hướng sút, chuẩn bị nhảy sang trái

đặt cược bên phải (đây là chiến thuật số 1 của anh ta), và thủ môn chuẩn bị nhảy sang trái (đây là chiến lược số 1 cho B), khi đó trung bình sẽ có 7 bàn trên 10; nếu B chuẩn bị nhảy sang phải thì ném 10 quả bóng, v.v.

Cả hai người chơi sẽ luân phiên lựa chọn của mình một cách ngẫu nhiên. Nếu mỗi người trong số họ chọn mỗi chiến lược của mình trong khoảng một nửa thời gian (như người ta nói, với xác suất là 1/2), thì trung bình (7 + 10 + 9 + 6): 4 = 8 bàn thắng sẽ được ghi.

Nếu A áp dụng chiến lược đầu tiên với xác suất 0,6 (trong trường hợp 60%) và chiến lược thứ hai với xác suất 0,4 (trong trường hợp 40%),

*) Trong lý thuyết trò chơi và kinh tế học, những bảng như vậy được gọi là ma trận lương.

⟦folio 7⟧

và thủ môn sử dụng chiến thuật đầu tiên của mình với xác suất 0,8 và chiến thuật thứ hai với xác suất 0,2, khi đó trung bình $(7 \cdot 0,6 + 9 \cdot 0,4) \times 0,8 + (10 \cdot 0,6 + 6 \cdot 0,4) \cdot 0,2 = 7,92$ bàn thắng sẽ được ghi, tức là nhỏ hơn 8. Tất nhiên, không có ý nghĩa gì khi nói rằng trong chuỗi trận cụ thể này sẽ có 7,92 bàn thắng được ghi. Điều muốn nói ở đây là với những loạt trận lặp lại nhiều lần thỏa mãn điều kiện đặt ra, số bàn thắng trung bình ghi được (tỷ lệ giữa tổng số bàn thắng trên số loạt trận) sẽ gần bằng 7,92.

Nói chung, hãy để $A$ chọn chiến lược thứ nhất và thứ hai với xác suất $x$ và $1-x$ ($0 \leq x \leq 1$) và $B$ với xác suất $y$ và $1-y$ ($0 \leq y \leq 1$). Trong trường hợp này, các con số $x$ và $y$ được cho là quyết định chiến lược hỗn hợp của người chơi. thì số bàn thắng trung bình ghi được là $m = (7x + 9(1-x))y + (10x + 6(1-x)) \times (1-y) = -6xy + 4x + 3y + 6$. (*)

Câu hỏi được đặt ra một cách tự nhiên: các giá trị cao nhất của $x$ cho $A$, $y$ cho $B$ là gì? Giá trị tốt nhất $x^*$ cho $A$, được đặt, phải đảm bảo số bàn thắng tối thiểu được ghi (trung bình), bất kể chiến thuật của thủ môn. Giá trị tốt nhất của $y^*$ cho $B$ phải đảm bảo số bàn thắng tối thiểu được ghi (trung bình), bất kể chiến lược của người sút phạt trước đây là gì.

Hóa ra (bạn sẽ thấy điều này bằng cách giải Bài tập 1), $x^* = 1/2$, $y^* = 2/3$; trong trường hợp này, (trung bình) $m^* = 8$ bàn thắng sẽ được ghi. Thật dễ dàng để kiểm tra (hãy chắc chắn làm điều này!) rằng nếu ít nhất một trong số các cầu thủ tuân thủ chiến lược “tốt nhất” đã chỉ định, thì bất kể chiến lược của người kia là gì, $m^* = 8$ bàn thắng sẽ được ghi (trung bình). Nếu một trong những người chơi không tuân theo chiến lược đã chỉ định, thì anh ta không còn có thể đảm bảo bất cứ điều gì - kết quả sẽ phụ thuộc vào hành động của quy tắc.

Vì vậy, nếu thủ môn nhảy sang phải và sang trái thường xuyên như nhau (tức là $y = 1/2$) và cầu thủ luôn ở góc phải ($x = 0$), thì trung bình sẽ có ít bàn thắng được ghi hơn ($m = 7,5$). Nhưng nếu người chơi $A$ bị đánh trúng, anh ta sẽ luôn ở góc trái ($x = 1$) và sau đó sẽ ghi bàn thường xuyên hơn ($m = 8,5$).

Và bây giờ, hãy tạm dừng bóng đá, các giả định và xử lý các hàm “đơn giản”, không hạn chế về $x$ và $y$ - điều này sẽ giúp các bước đầu tiên dễ dàng hơn.

Thắng, thua, hòa

Cho hai người chơi trò chơi sau: $A$ chọn số thực $x$, $B$ chọn số $y$ và mỗi người tự đưa ra lựa chọn của mình mà không biết lựa chọn của đối thủ. Cả hai con số đều được thông báo cho số phận, sau đó, theo các quy tắc mà người chơi đã biết trước, số tiền thắng của $v = f(x, y)$ đầu tiên, bằng với số tiền thua của số thứ hai, được tính; chính xác hơn, ở $v > 0$ A thắng giá trị $B$ $v$, ở $v < 0$ A thua giá trị $B$ $|v|$; nếu $v = 0$, thì trò chơi hòa; ký hiệu $f(x, y)$ có ​​nghĩa là $v$ là hàm cho trước của hai biến ($x, y$).

Ví dụ: đặt quy tắc tính tiền thắng trong trò chơi là:

$$v = y^2 - x^2.$$

Hãy thử chơi lại quy tắc (1) nhiều lần. Sau một số “trò chơi”, người chơi sẽ nhận thấy rằng tốt hơn là mỗi người trong số họ nên giành được giá trị bằng 0: với $x = y = 0$, kết quả là hòa và sẽ bất lợi cho một trong hai người chơi nếu đi chệch khỏi lựa chọn này, ngay cả khi biết lựa chọn của đối thủ.

Thật vậy, vì đối với $x = 0$ $v = y^2$, người chơi $B$ tốt nhất đáp số là lựa chọn của $y = 0$. Tương tự như vậy, với $y = 0$ $v = -x^2$ và nước đi tốt nhất $A$ là $x = 0$.

Bây giờ rõ ràng là việc chơi với chức năng plugin $v = y^2 - x^2$ không thú vị: đảm bảo một kết quả hòa cho cả hai người chơi. Chơi với chức năng plugin sau sẽ khó hơn và thú vị hơn:

$$v = y^2 - x^2 + 8x - 10y + 9.$$

Trong trường hợp này, liệu có những con số $x$ và $y$ nào có thể được khuyến nghị cho người chơi và từ đó họ sẽ phải “tốn kém” nếu đi chệch khỏi con số đó không?

Chìa khóa đơn giản của trò chơi (2) được đưa ra bởi bản mở rộng

⟦folio 8⟧

Cơm. 1.

$$v = (9 - x - y)(x - y + 1).$$

Đã tạo được hệ phương trình
$$\begin{cases} 9 - x - y = 0, \\ x - y + 1 = 0, \end{cases}$$

chỉ có lời giải $x^* = 4, y^* = 5$, chúng tôi kết luận rằng trò chơi (2) có kết quả hòa $v^* = v(x^*, y^*) = 0$ cho $x = x^* = 4, y = y^* = 5$.

Giải thích hình học ở đây như sau (Hình 1): một cặp số $(x^*; y^*) \in R^2$ được xác định bởi điểm giao nhau của các đường tương ứng với phương trình của hệ; nếu một điểm có tọa độ $(x; y)$ nằm trên một trong số chúng thì $v = 0$; đối với các điểm nằm bên trong các góc tạo thành trên đường thẳng lung lay, giá trị $v$ có dấu như hình vẽ. Con số này được bổ sung bằng các tính toán và lý luận sau đây; nếu $x = 4$, thì $v = (5 - y)^2 \geq 0$; $v_{\min} = 0$ tại $y = 5$ (tại các điểm thẳng đứng $x = 4$ luôn luôn $v \geq 0$); nếu $y = 5$, thì $v = -(x - 4)^2 \leq 0$; $v_{\max} = 0$ tại $x = 4$ (dọc theo chiều ngang $y = 5$ chúng ta có $v \leq 0$).

Do đó, nếu $A$ chọn $x = 4$, thì người chơi $B$ với bất kỳ lựa chọn nào khác ngoài $y = 5$ sẽ thua. Tương tự, nếu $A$ chọn $x \neq 4$, người chơi $B$ thắng khi lấy $y = 5$.

Vì vậy, người chơi đầu tiên có một nước đi mà anh ta chắc chắn sẽ không thua. Người chơi thứ hai cũng có động thái tương tự. Vì vậy, trong trò chơi này, người nào mạo hiểm chơi không “theo lý thuyết” sẽ thua (tất nhiên trừ khi đối thủ cũng có nguy cơ từ bỏ lý thuyết).

Chúng ta hãy lấy ví dụ về kết quả gót chân của các trò chơi trong trò chơi của chúng ta (trong mỗi bộ ba, số đầu tiên là $x$, số thứ hai là $y$, số thứ ba là $v$): $(0,0,9), (0,7, -12), (4,7,4), (4,5,0), (5,5, -1)$.

Nghiên cứu những trò chơi này gợi ý một cách khác lời giải (tiếc là không phải lúc nào cũng phù hợp). Chúng tôi cố gắng giải thích cho người chơi đầu tiên: “Nếu $B$ chọn $y = y_0$, thì chúng ta sẽ có một hình tam giác vuông $v(x, y_0) = (9 - y_0 - x)(x - y_0 + 1)$ đối với $x$, mà tôi phải làm cho hình tam giác này càng lớn càng tốt bằng cách chọn $x$ phù hợp; nhưng hình này có tam giác tối đa là $x = 4$, vì vậy tôi muốn $x = 4!$. Lập luận tương tự, người chơi thứ hai sẽ đảm bảo cho mình mức tối thiểu người thua cuộc $y = 5$ (đối với bất kỳ nước đi nào $x = x_0$ của ổ đĩa).

Điểm yên ngựa và lời giải trò chơi

Chúng ta đã thấy rằng trong trò chơi có hàm (2), mỗi người chơi có thể tự bảo đảm mình không bị thua, vì khả năng tìm một cặp số (4:5) sao cho $f(4,5) = 0$ và với tất cả các giá trị $x$ và $y$ ​​của hàm $f$ thỏa mãn bất đẳng thức
$$f(x, 5) \leq f(4, 5) \leq f(4, y).$$

Từ đó, chúng ta có thể thấy rằng người chơi đầu tiên, chọn $x = 4$, trong mọi trường hợp, không thua (điều này diễn ra từ bất đẳng thức cuối cùng), cũng như người chơi thứ hai không thua khi chọn $y = 5$.

Hãy đưa ra một định nghĩa chung.

Định nghĩa điểm yên ngựa.

Cho một hàm $f$ được xác định trên một tập hợp $G$ điểm nào đó trong mặt phẳng. Điểm $(x^*; y^*) \in G$ được gọi là điểm yên của hàm số $f$ hoặc điểm cân bằng nếu tại $(x, y^*) \in G, (x^*, y) \in G,$
$$f(x, y^*) \leq f(x^*, y^*) \leq f(x^*, y).$$

Từ những bất đẳng thức này suy ra $\max f(x, y^*) = f(x^*, y^*) =$
$$= \min f(x^*, y)$$
(ở bên trái có giá trị tối đa trong biến $x$ đối với hàmin $y = y^*$, ở bên phải có giá trị tối thiểu trong $y$ đối với hàmin $x = x^*$).

Về lý thuyết, điểm yên ngựa của người chơi $(x^*; y^*)$ thường được gọi là giải pháp của trò chơi (có chức năng hoàn trả $v = f(x, y)$), số $v^* = f(x^*, y^*)$ được gọi là chi phí của trò chơi và số $x^*, y^*$ lần lượt là chiến lược tối ưu của người chơi thứ nhất và thứ hai.

⟦folio 9⟧

Cơm. 2.

Khách du lịch và nhà leo núi

Khách du lịch muốn đi từ thung lũng $D_1$ đến thung lũng $D_2$, hãy đi qua đèo (yên ngựa) - trong khi độ cao tối đa trên đường từ $D_1$ đến $D_2$ (Hình 2) hóa ra là tối thiểu so với tất cả các tuyến đường gần không đi qua yên ngựa. Những người leo núi muốn thực hiện một chuyến đi từ đỉnh $V_1$ đến đỉnh $V_2$, hãy vượt qua cùng một chiếc yên vì một lý do khác - để không bị “mất độ cao”, tức là sao cho độ cao tối thiểu trên đường từ $V_1$ đến $V_2$ càng cao càng tốt.

Hình 1 hiển thị bản đồ trong đó chiều cao của đường chuyền được lấy bằng 0 và $x$ và $y$ là các điểm đục và vĩ độ. Chúng tôi sẽ coi các đường thẳng song song với các trục là khả năng dẫn đường cho khách du lịch và người leo núi. Giống như các tuyến đường trên núi, các đường thẳng chính của Hình 1 ($y=5$ và $x=4$) được làm nổi bật bởi thực tế là
$$f(x^*, y^*) = \min_{y} \max_{x} f(x, y) = \max_{x} \min_{y} f(x, y),$$
và điều này rất hữu ích khi phân tích trò chơi. Ở đây tối đa $f(x, y)$ là giá trị tối đa của $f$ cho một $y$ và biến $x$ nhất định, tức là tìm kết quả cho $B$ cho một giá trị đã chọn $y$; Rõ ràng, giá trị này tối thiểu ở mức $y=5$. Giải thích sự lựa chọn $x=4$ của người chơi $A$ theo cách tương tự.

Bây giờ hãy xem xét một trò chơi có hàm hoàn trả $v=x^2-y^2$, không có điểm yên ngựa (kiểm tra phần này). Việc phân tích một trò chơi có chức năng như vậy là rất phức tạp. Trong ví dụ này, đối thủ sẽ quan tâm đến việc chọn những con số lớn nhất để đạt được. Nếu chúng tôi đưa ra các hạn chế đối với các biến $x$ và $y$ có ​​dạng $|x| \leq a, |y| \leq b$ thường gặp trong thực tế, 4 điểm yên sẽ xuất hiện: $x^* = \pm a, y^* = \pm b, (v^* = a^2 - b^2)$.

Tuy nhiên, với loại hạn chế này, điểm yên ngựa có thể không xuất hiện (xem Bài tập 3).

Lời giải trò chơi có tính năng thanh toán theo hình vuông

Kết quả xem xét lý thuyết của chúng tôi được tóm tắt bằng định lý sau. Cho một mức giá có chức năng thanh toán
$$v = ax^2 + 2bxy + cy^2 + 2px + 2qy + r.$$
Hàm này có điểm yên và cer lời giải trong bảy trường hợp sau và chỉ trong bảy trường hợp đó:
1) $a < 0, c > 0$;
2) $a < 0, c = 0 \neq b$;
3) $a < 0, c = b = q = 0$;
4) $a = 0 \neq b, c > 0$;
5) $a = b = p = 0, c > 0$;
6) $a = c = 0, b \neq 0$;
7) $a = b = c = p = q = 0$.

Điểm yên ngựa là hệ phương trình lời giải
$$\begin{cases} ax + by + p = 0, \\ bx + cy + q = 0. \end{cases}$$

Đây là lời giải $(x^*, y^*)$ trong tất cả các trường hợp này ngoại trừ cer, độc giả: việc phân tích các ví dụ cụ thể trước đó sẽ giúp anh ta.

Bài tập

1. a) Hãy xem xét trò chơi có hàm hoàn trả $m = 6 + 4x + 3y(1-2x)$ và tìm giá trị $x$ mà $m$ không phụ thuộc vào $y$, cũng như giá trị $y$ mà $m$ không phụ thuộc vào $x$. Cặp ý nghĩa này có mang lại trò chơi lời giải không?

2. Tìm lời giải và đặt giá trò chơi với các tính năng thanh toán sau:
a) $v = -x^2 + 6xy + y^2 - 10x - 10y + 15$;
b) $v = (x + y - a)(y - x - b)$;
c) $v = 10\ln x - x^2 + 2xy + y^2 + 10x - 8y - 40, x > 0$;
d) $v = k(\sqrt{x}, -\sqrt{y}) + \sqrt{a-x} - \sqrt{b-y}$;
d) $v = k(-x^2 + 2pxy + y^2) - x_0^2 - 2px_0y + y_0^2$, trong đó $x_0 = a - x, y_0 = b - x$;
