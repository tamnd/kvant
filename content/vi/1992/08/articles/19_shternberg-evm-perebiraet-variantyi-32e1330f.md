---
id: 1992-8-shternberg-evm-perebiraet-variantyi-32e1330f
issue: kvant_1992_8
year: 1992
number: "8"
title: Máy tính đi qua các tùy chọn
authors:
  - Штернберг Л. Ф.
rubric: raznoe
rubric_sub: Разное
page_first: 64
page_last: 68
page_labels: 62-66
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 6df10d600e9d8684a334ba8662dcccfbb6e3962fef5a69c4664a02dd7fc79588
prompt_sha256: draft-1
translated_from: content/ru/1992/08/articles/19_shternberg-evm-perebiraet-variantyi-32e1330f.md
source_content_sha256: dccbd396bc235d828149f713f5bf9101de212ad2a011bf7f7826b0a278711a19
translation_model: draft
translation_run: vi-draft-gaps-2026-11-07
translation_quality: draft
---

⟦folio 62⟧

---
running_head:
folio:
---

Máy tính sắp xếp thông qua các tùy chọn
L. STERNBERG
đoạn 6
NƯỚC ÉP
đã ở đây
VASYA
đã ở đây
VASYA
điểm 4
điểm 2
điểm 5
đã ở đây
VASYA
điểm 3
CƠ SỞ DU LỊCH 1
62

⟦folio 63⟧

---
running_head:
folio:
---

Trong vòng vài giây, máy tính đã phân tích một số lượng lớn các tùy chọn có thể và đưa ra lựa chọn tốt nhất - bạn có thể thấy cụm từ này hoặc cụm từ tương tự trên báo khi họ nói về khả năng rộng rãi của máy tính. Nhưng để sắp xếp các lựa chọn, máy tính phải có chương trình thích hợp. Cái nào?

Nếu bạn cần xem qua bảng và chọn phần tử mới nhất (nhỏ nhất, nai...) thì chỉ cần sử dụng chương trình với một vòng lặp đơn giản là đủ. Nếu bạn cần lặp qua tất cả các kết hợp có thể có của các cặp phần tử, một trong số đó được lấy từ một bảng và phần còn lại từ bảng thứ hai, thì bạn sẽ phải tạo một vòng lặp lồng nhau:

...tab A [1:M], ...tab B [1:N]
không dành cho tôi từ chu kỳ 1 đến M
cũng như đối với cặp xử lý vòng lặp j từ 1 đến N (A[i], B[j])
ki

Chà, nếu bạn cần xem qua tất cả các kết hợp của 10 phần tử, bạn nên làm gì: 10 vòng lặp lồng nhau? Nếu có 100 phần tử thì sao? Nhưng nếu số lượng phần tử không được biết trước và thường khác nhau ở các phiên bản khác nhau thì phải làm gì?

Ví dụ: giả sử bạn cần xác định tuyến đường ngắn nhất từ ​​điểm A đến điểm B mà bạn có thể thêm vào theo nhiều cách khác nhau. Để làm điều này, bạn sẽ phải xem xét tất cả các tuyến đường, một trong số đó chỉ chứa một lần chuyển và 5 hoặc 6 lần chuyển còn lại.

Làm cách nào để tổ chức các chu kỳ tìm kiếm thông qua các tùy chọn có thể? Và nên có bao nhiêu? Một vòng lặp lồng nhau đơn giản sẽ không giúp ích gì ở đây; rõ ràng là chúng ta cần một số ý tưởng khác.

Vì vậy, chúng ta có trước một phần tử của cốt truyện lập trình viên ở trên - tìm kiếm bài toán. Nhưng hóa ra đối với cô ấy lời giải chỉ cần hai chu kỳ và một tạp chí là đủ. Chúng ta sẽ cần một cửa hàng, không phải cửa hàng nơi họ mua thứ gì đó, mà là cửa hàng bán súng trường hoặc súng máy, hay đúng hơn là phần mềm tương tự của nó. Điều đặc biệt ở băng đạn là hộp mực chỉ có thể được đưa vào từ một đầu (qua cửa sổ tạp chí), trong khi các hộp mực ở đó được đẩy vào trong. Và bạn chỉ có thể lấy đủ hộp mực qua cửa sổ, từ cùng một đầu, trong khi hộp mực mới xuất hiện trong cửa sổ từ độ sâu của băng đạn. Có thể dễ dàng nhận thấy rằng bạn chỉ có thể lấy hộp mực ra theo thứ tự ngược lại với hộp mực mà chúng được đặt - đây chính là đặc điểm của cửa hàng mà chúng tôi cần. Các lập trình viên cũng gọi cửa hàng là một ngăn xếp (từ tiếng Anh Stack - một gói: họ đặt nó vào một gói ở trên cùng và lấy nó từ trên xuống).

Phần mềm tương tự của một cửa hàng là một mảng và một biến chỉ mục cho biết mảng này đầy trong bao lâu:

...tab MAG [1:K] còn nguyên vẹn

Giá trị im hiển thị ô trống đầu tiên của tạp chí.*) Giá trị E được ghi vào tạp chí như sau (hình 1):

MAG [im]:=E; tôi:=tôi+1,

và nó được biết đến nhiều hơn như sau (hình 2, 3):

im:=im-1; E:=MAG [im].

Hãy thử phân tích tìm kiếm đơn giản nhất bài toán. Giả sử rằng người hướng dẫn du lịch đã được giao bài toán để xem lại tất cả các tuyến đường N trong ngày (chúng tôi sẽ đi N=3) bắt đầu từ địa điểm cắm trại của Vasya, kiểm tra lối đi của các con đường mòn, thiết lập các bãi đậu xe, v.v., tức là nói một cách đơn giản, lần lượt đi qua tất cả các tuyến đường. Bạn có thể đi qua chúng theo bất kỳ thứ tự nào và Vasya, không cần phải đắn đo thêm nữa, luôn bắt đầu từ con đường bên trái. Lộ trình đầu tiên rất cụ thể: 1—2—4—6. Nhưng có những ngã ba trên đường. Điều này có nghĩa là chúng ta cần quay lại và đi theo các nhánh. Từ điểm 2 bạn có thể xuất phát lúc 5, rồi lúc 1, hoặc 6, hoặc 4. Chúng tôi đi theo lộ trình 1-2-5-1, quay về

*) Có một tùy chọn lưu trữ trong đó im chỉ ra ô bị chiếm giữ cuối cùng.

⟦folio 64⟧

---
running_head:
folio:
---

rời đi lúc 5 giờ; và chúng ta đến từ đâu lúc 5 giờ: từ 1, 2 hay 3? Và trên đường đi sẽ có bao nhiêu ngày: nếu bạn đi bộ cứ sau 1-2-5 thì 2 ngày, và nếu sau 1-5 thì một ngày? Thế là xong, Vasya hoàn toàn bối rối. (Và chúng tôi cũng vậy.) Tất nhiên, các tuyến đường được viết ra, nhưng trong thời buổi hỗn loạn hiện đại, thật khó để tìm ra tuyến đường bạn đã đi và xác định tuyến đường nào bạn cần tiếp theo.

Và rồi Vasya nhớ ra rằng trong ba lô mình có một cuốn tạp chí, và quyết định rằng khi rời điểm, anh ta sẽ viết số điểm lên một tờ giấy, cho mảnh giấy vào hộp mực và hộp mực vào tạp chí: khi đó đường đến tạp chí sẽ nóng lên và số lượng hộp mực sẽ quyết định độ dài của nó. Để thuận tiện (đừng quên địa điểm cắm trại bản địa), một hộp mực màu đỏ có số “1” được đặt trước cửa hàng. Vào ngày thứ ba, Vasya bổ sung điểm 5 và ghi lại lộ trình đầu tiên vào nhật ký của mình: 1-2-4-5.

Vào buổi sáng, việc nhớ ra rằng anh ấy đã mở nó lúc 5 giờ là không cần thiết: ​​trong cửa sổ cửa hàng có một hộp mực có ghi “điểm 4” - nghĩa là chúng tôi cần quay lại điểm 4. Xử lý xong lộ trình 1-2-4-6 và quay lại điểm 4 một lần nữa, Vasya phát hiện ra rằng không còn nơi nào khác để đi từ điểm 4. Chúng ta cần quay lại, nhưng đi đâu? Và sau đó anh ấy lấy hộp mực ra khỏi tạp chí, và trong cửa sổ cửa hàng, anh ấy nhìn thấy một hộp mực có ghi “điểm 2”. Chúng tôi quay lại điểm 2, anh ấy đi từ ngã ba bên phải - đến điểm 5 và nghiên cứu các tuyến 1-2-5-1, 1-2-5-6.

Sau khi đi qua tất cả các tuyến đường của dạng 1-2-..., anh ta rút ra một hộp mực có mục "điểm 2" từ cửa hàng, quay lại điểm 1, đi theo các tuyến đường dọc theo con đường bên phải tiếp theo: 1-3-2-4, 1-3-2-5, 1-3-5-1, v.v., dọc theo hộp mực bên phải: 1-5-... và cuối cùng, hết tất cả các lựa chọn để thoát khỏi điểm 1. Bây giờ bạn cần vứt hộp mực màu đỏ đi và di chuyển quay lại, nhưng không rút lui được nữa: cửa hàng trống rỗng, nghĩa là mọi tuyến đường đã cạn kiệt. Và chúng được sắp xếp theo thứ tự từ điển (tức là được sắp xếp như trong từ điển: các từ đầu tiên bắt đầu bằng “A”, sau đó là “B”, v.v., với các từ “AB…” xuất hiện trước “AB…”).

Hãy viết lại thuật toán mà Vasya đã sử dụng.

Chuẩn bị thuyết trình
Đánh dấu phương án 1 (đường bên trái) tại điểm xuất phát
không cho đến khi cửa hàng trống rỗng
tìm kiếm một lựa chọn tuyến đường khác (một con đường chưa được đi)
nếu không có đường
sau đó ném hộp mực ra khỏi băng đạn;
quay lại mục được ghi trong cửa sổ cửa hàng
Tuyến đường Inchete đã hoàn thành
sau đó xử lý lộ trình (viết nó ra)
Nếu bạn muốn đặt hộp mực vào tạp chí, hãy ghi số điểm bạn còn lại; đi đến một điểm mới; đánh dấu đường 1 (đường bên trái) tại điểm này

⟦folio 65⟧

---
running_head:
folio:
---

Nhưng đây là một thuật toán dành cho Vasya, nhưng làm sao nó có thể được viết ra cho máy tính? Từ quan điểm toán học, mạng lưới đường là một biểu đồ, tức là một tập hợp các điểm $M$ được kết nối bởi hai (hoặc các cạnh), được chỉ định bằng bảng có kích thước $M \times M$ được gọi là ma trận kề. Phần tử $c_{ij}$ của nó bằng 1 nếu có một đường dẫn (tức là một cung) từ điểm $i$ đến điểm $j$ và bằng 0 nếu không có đường dẫn. Đồ thị có thể được định hướng—một cạnh có thể được đi qua chỉ theo một hướng—hoặc vô hướng nếu mỗi cạnh có thể đi qua theo các hướng chung. Trong trường hợp này, ma trận trở nên đối xứng, tức là $c_{ij} = c_{ji}$ (điều này giống như việc nối các đỉnh với một cặp cung có hướng: một cung ở đó, cung thứ hai - quay lại). Nếu chúng ta giả định rằng khách du lịch chỉ có thể được đưa dọc theo những con đường mòn của Vasya theo hướng được hiển thị bằng mũi tên (vì lý do nào đó), thì lưới này được đưa ra bởi biểu đồ:

$$C = \begin{pmatrix}
0 & 1 & 0 & 1 & 0 \\
0 & 0 & 0 & 1 & 0 \\
0 & 1 & 0 & 1 & 0 \\
0 & 0 & 0 & 1 & 1 \\
1 & 0 & 1 & 0 & 0 \\
0 & 0 & 0 & 1 & 0
\end{pmatrix}$$

Việc chuẩn bị bài thuyết trình bao gồm việc đặt một hộp mực màu đỏ vào tạp chí. Nói một cách chính xác thì bạn không cần phải đặt nó vào: điểm bắt đầu rất dễ nhớ, nhưng lập trình có nó sẽ thuận tiện hơn, hoặc không có nó thì việc quay lại điểm xuất phát sẽ phải được lập trình khác với những điểm khác. Vì vậy, chúng tôi cũng sẽ cung cấp ô số 0 cho hộp mực màu đỏ trong cửa hàng. Chúng ta sẽ thực hiện điều này với việc lựa chọn đường: vì chúng cần được sắp xếp theo thứ tự nào đó và đường nào ở bên trái không thể xác định được từ ma trận, chúng ta sẽ chỉ cần sắp xếp các điểm theo thứ tự tăng dần của số lượng của chúng và lấy điểm có đường. Nghĩa là, chúng tôi coi đường tại điểm có số thấp hơn là “trái” hơn. Biến Нп sẽ xác định số điểm mà chúng ta muốn đến. Để đánh dấu cho tùy chọn thứ 1, chúng tôi sẽ gán giá trị 0, tức là chúng tôi sẽ chỉ ra rằng chúng tôi chưa kiểm tra đường dẫn đến bất kỳ điểm nào. Việc kiểm tra việc hoàn thành tuyến đường rất đơn giản: nếu có $N$ phần tử trong cửa hàng thì tuyến đường đó đã được yêu cầu. Vitor chúng ta nhận được chương trình:

tab int MAG [0: $N$], int $i$, $j$, np; $N$;
MAG [0] := số điểm bắt đầu; tôi := 1
Np := 0; {chưa có con đường nào được thử nghiệm}
Np := tôi + 1

chưa $im > 0$ chu kỳ {lưu trữ không trống}
chưa Нп ≤ $M$ và С[MAG[im - 1], Нп] = 0
chưa Nn := $M$ và C[MAG[im - 1], Nn] = 0
không có gì nếu $im = N$ {tuyến đường đã hoàn thành}
sau đó in (MAG[0]...MAG[im - 1], Np)
không có gì MAG[im] := Np; im := im + 1 {đặt hộp mực vào tạp chí với số điểm mà nó rời đi}
Np := 0 {chưa có gì được kiểm tra từ đây}

Lưu ý rằng vòng lặp bên trong hiển thị hoạt động của nó trong hai trường hợp: a) Нп > $M$, tức là tìm kiếm tất cả các con đường và không tìm thấy gì, b) hoặc C[MAG[im - 1], Нп] = 1, tức là từ điểm chúng ta ghi trong cửa hàng là còn lại, có một đường dẫn tại điểm Нп. Trong trường hợp thứ hai, chúng ta đến điểm Np và ghi ngay Np vào cửa hàng, vì bây giờ chúng ta sẽ rời khỏi điểm này. Sẽ chẳng ích gì khi ghi lại điểm cuối cùng của tuyến đường trong cửa hàng vì nó sẽ phải được lấy từ đó. Như vậy, khi in điểm lộ trình phải lấy từ kho lưu trữ, còn điểm cuối cùng phải lấy từ Np. Khi quay trở lại bất kỳ điểm nào, hộp mực sẽ bị ném ra khỏi cửa hàng, nhưng nội dung của nó kết thúc bằng Np, tức là số điểm mà chúng quay trở lại xuất hiện trong Np và bạn có thể kiểm tra đường dẫn đến các điểm có số cao hơn.

Bây giờ hãy thử điều kiện bài toán. Hãy cấm các tuyến đường vòng và tự băng qua, tức là tuyến đường không được đi qua hai lần

⟦folio 66⟧

---
running_head:
folio:
---

Điều gì sẽ thay đổi trong thuật toán? Hầu như không có gì. Để chỉ làm phức tạp vòng lặp bên trong: nếu trước đây nó đang tìm kiếm bất kỳ điểm nào có đường từ điểm hiện tại thì bây giờ nó phải kiểm tra xem nó đã nằm trên đường đi của chúng ta hay chưa, tức là bằng cách xem nội dung của cửa hàng.

Bài toán 1. Tìm một chương trình cung cấp tất cả các tuyến đường có độ dài $N$, không tự phản ánh, xuất phát từ một điểm nhất định.

Hãy thay đổi bài toán: đường đi chúng ta cần là tất cả các tuyến đường không có độ dài nhất định mà dẫn từ điểm $A$ đến điểm $B$. Những thay đổi nào trong thuật toán? Chỉ kiểm tra phần cuối của tuyến đường: nó trông như thế này:

nếu $H_1 = B$ thì...

Chúng ta không phải lúc nào cũng cần tất cả các tuyến đường. Giả sử chúng ta muốn tìm đường đi ngắn nhất từ ​​$A$ đến $B$. Điều gì đang thay đổi? Một lần nữa, không nhiều: chỉ là một đơn vị xử lý. Nếu trước đó chúng ta chỉ in tuyến đường tiếp theo thì bây giờ chúng ta cần nhớ tuyến đường đầu tiên trong một bảng khác, và nếu tuyến đường tiếp theo ngắn hơn thì hãy nhớ nó. (Tuy nhiên, ở đây, các bài tập bổ sung sẽ được yêu cầu trong quá trình chuẩn bị bài thuyết trình.)

Bài toán 2. Hoàn thiện thuật toán tìm đường đi ngắn nhất.

Cho đến nay, chúng tôi đã làm việc với một biểu đồ không phải là đường mà là mạng điện thoại: quá trình chuyển đổi từ điểm này sang điểm khác luôn mất cùng thời gian. Để xác định mạng lưới đường, bạn sẽ phải thay đổi một chút ma trận $C$: các phần tử của nó sẽ nhận bất kỳ giá trị dương nào chỉ định độ dài đường đi (hoặc thời gian di chuyển). Teler nên tính toán độ dài của đường đi (thời gian di chuyển) không phải bằng số điểm đã đi mà bằng cách tính tổng trọng số của cung (tức là giá trị số của phần tử $c_{ij}$) khi đi qua điểm tiếp theo và trừ đi khi quay lại.

Bài toán 3 (vấn đề về công tác bảo trì đầu máy).

Cho một biểu đồ có trọng số (tức là một biểu đồ trên các cung có số trọng số được đưa ra) mô tả mạng lưới đường bộ. Tại điểm $A$ có hoạt động kinh doanh đầu máy xe lửa. Xác định các điểm cần xây dựng bản demo để thay đổi đầu máy, dựa trên thực tế là đầu máy (chính xác hơn là đầu máy của nó) phải chạy trên đường không quá $T$ giờ.

Trong dữ liệu lặp, một kho lưu trữ đôi khi bao gồm một số mảng và đôi khi cần có các mảng bổ sung cho các mục đích khác nhau. Chúng tôi đã thấy việc sử dụng các mảng bổ sung trong việc chỉ định đường dẫn tối thiểu. Một ví dụ về cửa hàng hai khối được đưa ra như sau

Bài toán 4. Để cùng một biểu đồ có trọng số xác định mạng lưới đường ống: các số trên các cung xác định độ dày (thông lượng). Độ dày của tuyến đường được xác định bởi độ dày tối thiểu của các cung có trong đó. Chúng ta cần tìm tuyến đường dày nhất từ ​​$A$ đến $B$.

Ở đây thật thuận tiện khi lấy một cửa hàng từ hai mảng: MAG và TOL (phần tử của mảng TOL hiển thị độ dày hiện tại của tuyến đường). Một mục cửa hàng trông như thế này:

$$\begin{array}{l}
MAГ [im] := H_1; \\
TOЛ [im] := \min \{TOЛ [im-1], C[MAГ [im-1], H_1]\};
\end{array}$$

(nếu cung từ điểm có số MAG [im-1] đến Np mỏng thì nó sẽ làm giảm độ dày của toàn bộ tuyến đường) và lực phóng từ băng đạn không thay đổi. Cửa sổ lưu trữ hiện bao gồm hai giá trị: TOL [im-1] hiển thị độ dày hiện tại của tuyến đường.

Bài toán 5. Hoàn thành việc tìm kiếm con đường dày nhất.

Tóm lại, chúng tôi lưu ý rằng việc giảm lập trình các nhiệm vụ đầy đủ cho phép chúng tôi chuyển sang hoạt động của máy móc một cách chính xác công việc mà máy móc không thể thay thế: khi các phương pháp toán học bất lực trong việc tìm ra phương án tối ưu, các phép tính rất đơn giản, nhưng cần phải kiểm tra các phương án, phương án,
