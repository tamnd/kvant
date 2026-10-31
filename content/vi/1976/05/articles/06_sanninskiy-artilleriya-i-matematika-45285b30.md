---
id: 1976-5-sanninskiy-artilleriya-i-matematika-45285b30
issue: kvant_1976_5
year: 1976
number: "5"
title: Pháo binh và toán học
authors:
  - Саннинский В. Я.
rubric: osnovnye-stati
page_first: 35
page_last: 40
page_labels: 33-38
tag: Y1FC
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 2ab4047ea3b32a2b50da0426d0f59d45489866c71b1c14469b2d8471bb2c17e5
prompt_sha256: draft-1
translated_from: content/ru/1976/05/articles/06_sanninskiy-artilleriya-i-matematika-45285b30.md
source_content_sha256: 864fa7523202d47287a76462a0e623b58f31f920755fae30d4f5cf4966095ed5
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 33⟧

Trong bài viết này, một cựu chiến binh trong Chiến tranh Vệ quốc vĩ đại nói về những bài toán mà ông phải giải khi chỉ huy một khẩu đội súng cối 120 mm bắn ở cự ly lên tới 6 km. Hơn 30 năm đã trôi qua kể từ đó. Nhiều bài toán liên quan đến điều khiển hỏa lực hiện đã được giải quyết bằng máy tính. Tuy nhiên, sự hồi hộp về toán học của họ vẫn như cũ.
Giả định rằng người đọc biết bản đồ địa lý là gì, tọa độ địa lý của một điểm trên bề mặt trái đất, các cực địa lý và từ trường, đường xích đạo, kinh tuyến, vĩ độ và góc phương vị.

Việc bắn một khẩu đội pháo vào các vật thể trong trại địch bao gồm việc chuẩn bị dữ liệu - xác định tầm bắn và hướng của mũi tên. Để tìm những giá trị này, trước tiên bạn phải “liên kết” pin và mục tiêu - cụ thể là xác định tọa độ địa lý của chúng.

Hãy giải thích điều này có nghĩa là gì. Hãy để chúng tôi giới thiệu một số khái niệm; chúng ta sẽ cần chúng sau này.

Bản đồ địa hình

Bản đồ địa hình (topographic maps) là bản đồ địa lý có tỷ lệ lớn. Các tờ bản đồ địa hình mô tả những diện tích tương đối nhỏ trên bề mặt trái đất nên không thể nghiên cứu được độ cong của trái đất (dưới đây chúng ta luôn coi trái đất là hình cầu).

Bản đồ địa hình chính là bản đồ tỷ lệ 1:1000000; nó được gọi là bản đồ địa hình quốc tế thứ một triệu. Tấm bản đồ địa hình thứ một triệu là những hình thang có thể tích bằng nhau, thu được như thế này. Đầu tiên, bề mặt trái đất được bao phủ bởi các đường song song cứ sau 4° từ xích đạo đến cực - thu được các hàng. Sau đó, bề mặt Trái đất được bao phủ bởi các kinh tuyến cứ sau 6° tính từ kinh tuyến đối diện với kinh tuyến Grivisian, theo hướng đông - thu được các cột. Giao nhau, hàng và cột tạo thành giao

⟦folio 34⟧

các loại gia vị, được mô tả trên các tờ bản đồ địa hình thứ một triệu.

Mỗi tờ bản đồ địa hình thứ một triệu có một “địa chỉ địa lý” bao gồm hai ký tự - một danh pháp. Ký tự đầu tiên cho biết trang tính thuộc về một hàng cụ thể, ký tự thứ hai - thuộc về một cột cụ thể. Trong trường hợp này, các hàng được đánh số bằng các chữ cái trong bảng chữ cái Latinh (A, B, C, D,...) từ xích đạo đến cực và các cột là các số (1, 2, 3, 4, ...) từ kinh tuyến đối diện với kinh tuyến Grivich, theo hướng về phía đông. Như vậy, điểm $M$ trên bề mặt trái đất có tọa độ địa lý $75^\circ 54'$ kinh độ Đông và $13^\circ 12'$ vĩ độ Bắc thuộc tờ bản đồ địa hình thứ một triệu với danh pháp $D-43$ ([13°12' :4°] + 1 = 4 - hàng thứ tư tính từ xích đạo - chữ cái $D$ và cột thứ 43 tính từ đường xích đạo đã chỉ định kinh tuyến:

$$\left[ \frac{180^\circ + 75^\circ 54'}{6^\circ} \right] + 1 = 43^*$$

Để tính toán thêm, chúng tôi sử dụng độ dài cung của quả địa cầu ở $1^\circ$ dọc theo đường xích đạo và dọc theo kinh tuyến bằng 111,0 km. khi đó kích thước của phần bề mặt trái đất hiển thị trên tờ $D-43$ sẽ như sau: các đáy của hình thang là 653,6 km và 640,2 km, chiều cao của hình thang là 444,0 km (hai giá trị đầu tiên được tính là cung 6 độ $12^\circ$ và $16^\circ$ song song:

$$653,6 = 6 \cdot 111 \cdot \cos 12^\circ,$$
$$640,2 = 6 \cdot 111 \cdot \cos 16^\circ,$$

và giá trị thứ ba là 4,111 - giống như cung 4 độ của vòng tròn lớn của địa cầu).

Bằng cách chia liên tục các phần triệu của bản đồ địa hình thành các phần bằng nhau về kinh độ và vĩ độ, sẽ thu được các bản đồ địa hình có tỷ lệ nhỏ hơn: 1:100000, 1:50000, 1:25000 và 1:10000. Để có được bản đồ địa hình 1:100000, tờ bản đồ địa hình thứ một triệu

*) Ở đây $[x]$ là phần nguyên của $x$ - số nguyên gần nhất với $x$, không vượt quá $x$ (xem bài “Antje”, trang 43).

⟦folio 35⟧

chia thành 12 phần theo kinh độ và 12 phần theo vĩ độ: thu được 144 “mảnh”. Để có được bản đồ địa hình 1:50000, bạn cần chia một trong 144 mảnh thu được thành 2 phần bằng nhau về kinh độ và 2 phần bằng nhau về vĩ độ (xem Hình 1). Nếu một trong các phần kết quả lại được chia thành 2 phần bằng nhau về kinh độ và 2 phần bằng nhau về vĩ độ, chúng ta sẽ có được bản đồ địa hình có tỷ lệ 1:25000. Lặp lại thao tác tương tự (chia thành các phần chẵn) với bản đồ địa hình này, chúng ta được bản đồ địa hình tỷ lệ 1:10000.

Khi phân chia các phần của mỗi tờ bản đồ địa hình đều được đánh số: “trái - phải - dưới” (Hình 1). Để chỉ định các phần, mỗi lần một chỉ mục mới được thêm vào danh pháp của bản đồ địa hình thứ một triệu ban đầu: một - nếu bản đồ là 1:100000: một số từ 1 đến 144 (Hình 1, a); hai - nếu bản đồ là 1:50000: chỉ mục của tờ bản đồ địa hình 100 mét mà từ đó nó được lấy, cộng với một trong bốn chữ in hoa đầu tiên của bảng chữ cái tiếng Nga A, B, B, Γ (Hình 1, b); ba - nếu bản đồ là 1:25000: chỉ mục của bản đồ thứ năm mươi nghìn tương ứng, cộng với một trong các chữ cái a, b, c, d (Hình 1, c) và cuối cùng, bốn - nếu bản đồ là 1:10000: chỉ mục của bản đồ tương ứng là 1:25000, cộng với một trong các số 1, 2, 3, 4 (Hình 1, e).

Khi chuẩn bị dữ liệu ban đầu cho mũi tên, bản đồ địa hình tỷ lệ 1:10000 thường được sử dụng. Tờ bản đồ tỷ lệ này có điểm M nêu trên (được xác định theo tọa độ địa lý) có danh pháp D-43-104-B-g-3; kiểm tra nó. Có thể tính toán rằng tấm này nuôi dưỡng một phần hình thang của bề mặt trái đất với đường tâm là 6,8 km và chiều cao là 4,6 km.

tọa độ địa hình

Hệ tọa độ được sử dụng trong địa hình khác với hệ Descartes. Trong hệ thống này, trục X là Myrdian địa lý ở giữa của mỗi cột, song song với 500 km về phía tây và trục Y là đường xích đạo. Ví dụ: chúng ta hãy tìm trong hệ thống báo cáo này tọa độ của điểm M của chúng ta - chúng được gọi là tọa độ đơn hiệu và được đo bằng mét. Điểm M nằm cách xích đạo 1465,2 km và cách kinh tuyến giữa cột số 43 97,26 km. Vì vậy, đối với điểm M

$$\begin{cases} X_M = 1465200, \\ Y_M = 597260. \end{cases}$$

Trên lãnh thổ của mỗi quốc gia, các điểm đào tạo tiền tiểu bang đặc biệt, có thể nhìn thấy đã được lắp đặt. Tất cả chúng, giống như các công trình kiến ​​trúc cao khác trên bề mặt trái đất, đều có tọa độ địa hình được xác định chính xác; Các tọa độ này được lưu trữ trong các thư mục đặc biệt chỉ được sử dụng cho mục đích dịch vụ.

Đối với mục đích giáo dục, các điều kiện được thỏa mãn với tọa độ. tọa độ của điểm đầu tiên, điểm bắt đầu của khu vực được cho tùy ý. Những vật dụng cần thiết đều được “đính kèm” vào nó. Kết quả là một hệ thống điểm phẳng được xác định bằng tọa độ, tương ứng với hệ thống điểm địa hình thực tế. Nếu cần, hãy tìm hiểu tọa độ địa hình của một trong các điểm của hệ thống này, chúng ta có thể tìm ra tọa độ thực tế của toàn bộ mạng lưới các điểm.

Chèn nó vào một điểm nào đó ở bán cầu bắc với bản đồ địa hình tương ứng và cố gắng sắp xếp nó theo hướng chính. Ba kinh tuyến đi qua mỗi điểm: từ, địa lý và địa hình (song song với trung tuyến kinh tuyến địa lý cho tờ chính của bản đồ địa hình tương ứng). Nhắc đến kinh tuyến, nói chung, chúng không trùng nhau. Chúng giao nhau ở những góc nhất định. Những góc này tương đối nhỏ và chúng ta không thể

⟦folio 36⟧

chúng tôi cắt. Chúng ta sẽ xem xét tất cả các kinh tuyến tại điểm trùng với kinh tuyến từ, tức là với hướng về phía bắc của kim la bàn từ tính.

Mọi người đều phải sử dụng la bàn. Do đó, chúng ta có thể cho rằng chúng ta biết cách định hướng bản đồ địa hình mong muốn theo hướng bắc.

Trong phần tiếp theo chúng ta sẽ sử dụng ký hiệu sau:

$X_A$ và $Y_A$ là tọa độ chuyên khảo của điểm $A$ trên mặt đất;

$|AB|$ — khoảng cách giữa các điểm $A$ và $B$ (tính bằng mét);

$[AB]$ là góc phương vị của hướng từ $A$ đến $B$, tức là góc giữa $AB$ và hướng bắc, đo theo chiều kim đồng hồ.

Bài toán

Bây giờ chúng ta hãy xem xét tọa độ bài toán chính cần được giải quyết trong quá trình chuẩn bị dữ liệu ban đầu cho mũi tên.

Bài toán 1. (Đường thẳng bài toán đến tọa độ.) Cho: $X_A$, $Y_A$, $|AB|$ và $[AB]$. Tên: $X_B$, $Y_B$.

Điều này có nghĩa là khoảng cách $|AB|$ (tính bằng mét) sẽ được tìm bằng thước dây, góc $[AB]$ - bằng la bàn hoặc máy kinh vĩ (không tính đến việc hiệu chỉnh các góc giữa các kinh tuyến).

Từ Hình 2 có

$$X_B = X_A + \Delta X$$

Và

$$Y_B = Y_A + \Delta Y,$$

ở đâu $\Delta X = |AB| \cdot \cos [AB]$ và $\Delta Y = |AB| \cdot \sin [AB]$.

Bài toán 1 cho phép chúng ta “liên kết” điểm $B$ của địa hình (xác định tọa độ địa hình của điểm $B$) với điểm “trói” $A$.

Đối với tọa độ lời giải cụ thể bài toán, thông thường sử dụng bảng toán 5 chữ số *). Ví dụ: giải quyết bài toán này:

*) Bạn có thể sử dụng bảng Bradis.

Cơm. 2.

1. Tìm $X_B$ và $Y_B$ nếu $X_A = 53\ 817$, $Y_A = 38\ 629$, $|AB| = 2182$ và $[AB] = 321^\circ 14'$.

Bài toán II. (Đảo ngược bài toán thành tọa độ.) Cho trước: $X_A$, $Y_A$, $X_B$, $Y_B$. Tên: $[AB]$, $|AB|$.

Từ cùng hình 2 có $\Delta X = X_B - X_A$ và $\Delta Y = Y_B - Y_A$. Tiếp theo chúng ta có

$$tg[AB] = \frac{\Delta Y}{\Delta X}.$$

Theo giá trị tính toán $tg[AB]$, có xét đến dấu vị trí, góc $[AB]$.

Cuối cùng, từ $\Delta ABC$ ta có

$$|AB| = \frac{|\Delta Y|}{\sin [AB]} = \frac{|\Delta X|}{\cos [AB]}.$$

Việc tính toán $|AB|$ được thực hiện bằng cả hai công thức. Sự trùng hợp về kết quả là sự đảm bảo nhất định cho sự an toàn của phép tính đạo hàm.

Hãy giải quyết ngay bài toán cụ thể:

2. Tìm $[AB]$ và $|AB|$ nếu $X_A = 12\ 850$, $Y_A = 98\ 713$, $X_B = 13\ 519$ và $Y_B = 97\ 314$.

Sau khi giải quyết xong, bạn có thể ra lệnh cho khẩu đội: "Pin, chiến đấu! Tầm xa..., góc phương vị...!" Xạ thủ của mỗi khẩu súng, sau khi nhận được lệnh như vậy, sẽ sử dụng một thiết bị để nhắm súng chính xác theo chiều dọc (một phần của tầm ngắm là 50 m) và theo chiều ngang (một phần của thước đo góc là 3,6 ').

Giáo viên có thể nhầm lẫn. Tại điểm $A$ vũ khí đầu tiên được đặt, những vũ khí khác ở một khoảng cách nhất định với nó, về bên trái. Có nghĩa

⟦folio 37⟧

Chỉ có thứ tự đầu tiên sẽ rơi vào $B$. Trên thực tế, nếu toàn bộ diện tích $B$ là đáng kể thì mọi thứ sẽ ổn (tại sao?). Nhưng còn khi toàn bộ chuỗi hạt tập trung ở điểm $B$ thì sao? Trong trường hợp này, lệnh được đề cập còn được chỉ định thêm: “hướng lên trên” (nếu mục tiêu $B$ có diện tích lớn thì lệnh là: “song song hướng lên trên”) và người chỉ huy, tùy thuộc vào khoảng cách của họ với mục tiêu đầu tiên, sẽ tính toán và điều chỉnh góc phương vị được chỉ định cho pin.

Người đọc có thể tự mình thực hiện công việc tính toán tương ứng cho người chỉ huy cấp hai, coi khoảng cách của anh ta với người chỉ huy cấp một chẳng hạn là 50 m (trong cùng điều kiện cụ thể bài toán II). Có thể giả định rằng mặt trước của pin vuông góc với hướng bắn của tia thứ nhất.

Vì vậy, chúng tôi đã làm việc cho cả người chỉ huy khẩu đội và người chỉ huy vũ khí. Tuy nhiên, chúng tôi vẫn chưa dạy điều quan trọng nhất: để bắn từ $A$ đến $B$, trước tiên bạn phải “ràng buộc” những điểm này. Trong điều kiện chiến tranh, điểm $A$ nằm trên lãnh thổ của chúng ta và điểm $B$ nằm trên lãnh thổ của kẻ thù: bạn không thể đến đó bằng thước dây. Từ đây phát sinh một “ràng buộc” mới bài toán - bài toán của một điểm vị trí không thể tiếp cận.

Bài toán III. (Vết cắt thẳng từ hai điểm.) Cho: $X_A, Y_A, X_B, Y_B$, nguyên vẹn $\alpha$ và $\beta$ (xem Hình 3). Tên: $X_C, Y_C$.

Điều này có nghĩa là các điểm $A$ và $B$ của địa hình đã được “liên kết”. Cần phải “ràng buộc” mục $C$ với điều kiện là các giá trị $\alpha$ và $\beta$ có thể được tìm thấy bằng cách thay đổi không được biểu thị.

Nếu chúng ta biết các đại lượng $[AC]$ và $|AC|$ hoặc $[BC]$ và $|BC|$, thì bài toán của chúng ta sẽ giảm xuống bài toán I. Hãy xác định các đại lượng này.

Với $\Delta ABC$ (xem Hình 3) theo định lý sin ta có

$$\frac{|AC|}{\sin \beta} = \frac{|BC|}{\sin \alpha} = \frac{|AB|}{\sin (\alpha + \beta)}$$

Từ đây

$$|AC| = \frac{|AB|}{\sin (\alpha + \beta)} \cdot \sin \beta$$

và $|BC| = \frac{|AB|}{\sin (\alpha + \beta)} \cdot \sin \alpha$.

Ngoài ra, $[AC] = [AB] - \alpha$ và $[BC] = [AB] + \beta$.

Các giá trị $|AB|$ và $[AB]$ được tìm thấy theo cách tương tự như trong bài toán II.

Tọa độ điều khiển được tính theo hai cách: cả tại điểm $A$ và tại điểm $B$.

Hãy giải quyết ngay bài toán cụ thể:

3. Tìm $X_C$ và $Y_C$ nếu $X_A = 12850, Y_A = 98713, X_B = 13519, Y_B = 97314, \alpha = 39^\circ43', \beta = 82^\circ25'$.

Bài toán III đi đến quyết định trong tình huống sau. Giả sử $A$ và $B$ là một cặp điểm quan sát nằm cách nhau 1,5–2,5 km, không xa mép trước của hàng phòng thủ. Những điểm này được “liên kết” trước và kẻ thù bị quan sát từ chúng. Khi mục tiêu $C$ xuất hiện trong trại địch, người ta quan sát thấy mục tiêu đó bị “phát hiện”, tức là các góc $\alpha$ và $\beta$ sẽ được đo bằng mọi cách. Tất cả những gì còn lại là giải tam giác $ABC$ cạnh $AB$ và hai góc kề nhau $\alpha$ và $\beta$: phân tích, như mô tả ở trên, hoặc đồ họa - trên máy tính bảng.

Cuối cùng, thêm bài toán vào tọa độ.

Bài toán IV. (Cắt ngược từ ba điểm.) Cho: $X_A, Y_A, X_B, Y_B, X_C, Y_C, ADC = \alpha, BDC = \beta$

⟦folio 38⟧

(xem hình 4). Tìm: $X_D, Y_D$.*

Tọa độ của điểm $D$ có thể được tính thông qua số gia tọa độ của một trong hai điểm: $A, B$ hoặc $C$. Để tránh sai sót, người ta thường tìm chúng thông qua các gia số từ hai điểm, ví dụ: điểm $A$ và $B$.

Chúng ta đã biết cách tính các đại lượng $[AC]$ và $|AC|$, $[BC]$ và $|BC|$. Bằng cách này, chúng ta có thể tìm được góc $\widehat{ACB}$:

$$\widehat{ACB} = [AC] - [BC].$$

Hãy đặt $\widehat{CAD} = \gamma$ và $\widehat{CBD} = \delta$. Hãy xác định các góc này.

Từ tứ giác $ACBD$ ta có

$$\frac{\gamma + \delta}{2} = 180^\circ - \frac{\alpha + \beta + \widehat{ACB}}{2}.$$

Từ các tam giác $ACD$ và $BCD$ sử dụng định lý sin ta tìm được

$$\frac{|CD|}{|AC|} = \frac{\sin \gamma}{\sin \alpha}$$

$$\frac{|CD|}{|BC|} = \frac{\sin \delta}{\sin \beta}.$$

Loại bỏ các đại lượng $|CD|$ khỏi các đẳng thức này, ta thu được

$$\frac{\sin \delta}{\sin \gamma} = \frac{|AC| \sin \beta}{|BC| \sin \alpha}.$$

Hãy đặt nó ở đây

$$\frac{|AC| \sin \beta}{|BC| \sin \alpha} = \text{tg} \lambda.$$

Sau khi tính $\text{tg} \lambda$ bằng công thức này, chúng ta tìm được góc phụ $\lambda$.

*) bài toán này được gọi là bài toán Pomenona. Họ đã được kể trong «Kvant» - xem, bài viết của L. S. Khrenov, «Kvant», 1973, Số 4, tr. 30.

Hiện nay

$$\frac{\sin \gamma}{\sin \delta} = \frac{1}{\text{tg} \lambda},$$

Ở đâu

$$\frac{\sin \gamma + \sin \delta}{\sin \gamma - \sin \delta} = \frac{1 + \text{tg} \lambda}{1 - \text{tg} \lambda},$$

đó là

$$\text{tg} \frac{\gamma - \delta}{2} = \text{tg} \frac{\gamma + \delta}{2} \cdot \text{ctg} (45 + \lambda).$$

Tất cả số lượng ở phía bên phải đều được biết đến. Do đó, chúng ta có thể tìm được nửa hiệu của các góc mong muốn $\gamma$ và $\delta$.

Biết chúng, chúng ta có được sự giống nhau một nửa và dễ dàng tìm thấy những góc này.

Khi đó từ các tam giác $ACD$ và $BCD$ sử dụng định lý sin ta tìm được

$$|AD| = \frac{|AC| \sin (\alpha + \gamma)}{\sin \alpha}$$

$$|BD| = \frac{|BC| \sin (\beta + \delta)}{\sin \beta}.$$

Phương vị $[AD]$ và $[BD]$ được tìm thấy bằng công thức

$$[AD] = [AC] + \gamma$$

$$[BD] = [BC] - \delta.$$

Tiếp theo, như trong bài toán I, $X_D$ và $Y_D$ được tìm thấy.

Đây là một bài toán cụ thể:

4. Tìm $X_D$ và $Y_D$ nếu $X_A = 12850$, $Y_A = 98713$, $X_B = 13519$, $Y_B = 97314$, $X_C = 12406$, $Y_C = 96956$, $\alpha = 72^\circ 28'$, $\beta = 31^\circ 46'$.

Việc cắt bỏ ba điểm thường “buộc” các điểm quan sát được và pin. Bạn có thể “liên kết” mục tiêu theo cách này. Nhưng để làm được điều này, bạn cần phải có đại diện của riêng mình trên lãnh thổ của kẻ thù. Giống như những phần trước, bài toán cuối cùng có thể được giải bằng đồ họa: để làm điều này, bạn cần xây dựng một điểm mà từ đó hai đoạn này có thể nhìn thấy được ở các góc này.

Điều này kết thúc câu chuyện của chúng ta về những nhiệm vụ mà pháo binh phải giải quyết. Chúng ta chỉ cần nói thêm rằng “toán học trong pháo binh” còn lâu mới cạn kiệt khi tháo rời bài toán.
