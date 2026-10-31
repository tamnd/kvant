---
id: 1982-7-hodulev-rasselenie-fishek-67bb3d3c
issue: kvant_1982_7
year: 1982
number: "7"
title: Phân tán chip
authors:
  - Ходулёв А. Б.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 30
page_last: 33
page_labels: 28, 30, 31
tag: MQ6D
lang: vi
source: kvant_digital
extraction: vision
content_sha256: e2ea1bc13945e9197432b31aa3e093fac3f2a8d94a84e071932b8cec6567c540
prompt_sha256: draft-1
translated_from: content/ru/1982/07/articles/08_hodulev-rasselenie-fishek-67bb3d3c.md
source_content_sha256: a7778d566a7024b55058230599e008f7c3f9fe4af5beeacfddabe7b478d247be
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 28⟧

A. Khodulyev

Phân tán chip

Từ biên tập viên

Ghi chú này được dành riêng cho bài toán sau đây của M. Kontsevich (từ số 11, 1981), được độc giả công nhận là một trong những môi trường tốt nhất được xuất bản trong Sách Vấn đề Lượng tử năm ngoái:

M715. Góc bên phải được chia thành các ô. Trên một số ô có chip và sự sắp xếp của các chip có thể được biến đổi như sau: nếu đối với một số chip, ô liền kề trên cùng và ô liền kề bên phải còn trống thì một chip được đặt vào các ô này và chip cũ sẽ bị loại bỏ. Đầu tiên, một con chip được đặt vào ô góc. Có thể giải phóng các góc của a) ba, b) sáu, c) mười ô, được hiển thị trong Hình 1, a, b, c, khỏi bộ đếm bằng cách sử dụng một số phép biến đổi đã chỉ định không?

Chúng tôi cũng thực sự thích điều này bài toán - chúng tôi tìm thấy trong đó nhiều tính năng sẽ được chia sẻ trong các tài liệu mới được gửi tới tạp chí: một công thức trực quan khuyến khích bạn thực hiện một thí nghiệm và sau đó xây dựng một lý thuyết chung; một đối tượng nghiên cứu đặc trưng của toán học ứng dụng và rời rạc hiện đại (một mạng chứa đầy các số 1 và 0, các quy tắc chuyển tiếp cục bộ); sự xuất hiện tự nhiên trong lời giải của toàn bộ các khái niệm và cấu trúc toán học quan trọng (bất biến, tổng vô hạn, nhúng bài toán vào một số “phần mở rộng” của nó, thuật toán hữu hạn, v.v.). Chúng tôi đặc biệt khuyên những ai chưa quyết định bài toán M715 hãy suy nghĩ ít nhất một giờ trước khi đọc bài viết (“chúng tôi đã cố tình gửi phần chính” Hình 8 đến cuối bài viết). Đối với những người còn lại, những người đã trải qua sự hài lòng này, chúng tôi đề xuất chứng minh những sự thật chưa được chứng minh từ phần thứ hai của bài viết, trong đó đưa ra một lý thuyết nhỏ cho phép chúng tôi nghiên cứu khả năng giải được “trò chơi Kontsevich” trong trường hợp tổng quát nhất.

Lời giải bài toán M715. bất biến

Để xác định trình tự di chuyển mong muốn, thuận tiện nhất là sử dụng cờ đam và bàn cờ thông thường. Bằng cách đặt quân cờ ở góc dưới bên trái và thử nghiệm một chút, bạn có thể dễ dàng tìm thấy lời giải bài toán a). Trong bài toán này, bạn có thể giải phóng vùng màu hồng, chẳng hạn như trong Hình 2 - trong 4 nước đi (1,1), (2,1), (2,2), (1,2). (Bản ghi nước đi cho biết tọa độ của ô mà chip bị loại bỏ khi thực hiện một nước đi. Ví dụ: nước đi (2,1) có nghĩa là một chip được loại bỏ khỏi trường (2,1) và các chip mới được đặt trên các trường (2,2) và (3,1).

Cơm. 1.

⟦folio 30⟧

Hãy bắt đầu cả hai loạt bài này cùng nhau thông qua $L$ - xem hình. 3, trong đó $L$ được đánh dấu bằng màu xanh lam) sẽ luôn chỉ có một chip, mỗi chip sẽ đóng góp vào tổng $s_{\text{кон}}$ không vượt quá 1/8 (vì chúng phải nằm bên ngoài $B$). Tổng các số của các chip còn lại phải nhỏ hơn $s(K \setminus B \setminus L) = 3/4$. Do đó, $s_{\text{кон}} < s(K \setminus B \setminus L) + 2 \cdot \frac{1}{8} = 1$, và điều này đã mâu thuẫn với thực tế là $s_{\text{нач}} = 1$.

Nhiệm vụ a), b), c) đã được giải quyết, nhưng thật thú vị khi tìm hiểu cách sử dụng bất kỳ bài toán tương tự nào. Ví dụ: có thể giải phóng vùng $\Gamma$ như trong Hình 4 không? Ở đây $s(K \setminus \Gamma) = 1\frac{1}{2}$ và thậm chí tính đến tính duy nhất của các chip ở hàng ngang và hàng dọc đầu tiên, bạn chỉ có thể nhận được $s_{\text{кон}} < 1\frac{1}{8}$.

Tuy nhiên, việc giải phóng khu vực này đã không thể thực hiện được.

Bây giờ chúng ta sẽ kiểm tra bài toán thuộc loại này: đầu tiên, các mã thông báo điền vào bộ $H$; bạn cần giải phóng tập hợp $F$ trong một số lần di chuyển (ở đây $H$ và $F$ là bất kỳ tập hợp ô hữu hạn nào từ $K$). Hãy gọi nó là vấn đề giải phóng ($H, F$).

Vị trí và di chuyển tổng quát

Trước hết, rất thuận tiện để loại bỏ việc cấm di chuyển khỏi ô $(i, j)$ khi nó trống hoặc khi các ô $(i, j+1)$, $(i+1, j)$ bị chiếm (được đưa ra trong các điều kiện bài toán của quy tắc

⟦folio 31⟧

ngăn cản bạn thay đổi thứ tự di chuyển, điều này rất khó hiểu). Nhưng sau đó chúng ta sẽ phải khái quát hóa khái niệm vị trí một cách rộng rãi. Bây giờ chúng ta sẽ giả định rằng trong ô $(i, j)$ có thể có bất kỳ số nguyên $A_{ij}$ nào của chip - không chỉ dương mà còn âm và đối với mỗi vị trí $A$ chỉ đối với một tập hợp ô hữu hạn, số $A_{ij}$ khác 0. Một bước di chuyển (tổng quát hóa) ở vị trí như vậy là một sự thay thế đồng thời
$$A_{ij} \rightarrow A_{ij} - 1, A_{i+1,j} \rightarrow A_{i+1,j} + 1, A_{i+1,j} \rightarrow A_{i+1,j} + 1.$$
Chúng ta sẽ gọi các vị trí trước đó (trong đó $A_{ij}=1$ hoặc $A_{ij}=0$) và di chuyển bình thường.

Hình 5 cho thấy một động thái dẫn đến một vị trí không bình thường từ một vị trí bình thường. Ở cuối Hình 5, vị trí tương tự được hiển thị bằng ký hiệu số mới.

Kết quả của việc di chuyển từ hình vuông $(i, j)$ là trừ đi các đơn vị từ $A_{ij}$ và cộng các đơn vị vào $A_{i+1,j}$ và $A_{i,j+1}$; kết quả của một số phép trừ và phép cộng như vậy rõ ràng không phụ thuộc vào thứ tự chúng được thực hiện.

Thực tế thay thế sau đây diễn ra, cho phép chúng tôi sử dụng các nước đi tổng quát cho lời giải mà chúng tôi quan tâm bài toán: nếu một vị trí bình thường $P$ có thể được chuyển sang một vị trí bình thường khác $Q$ bằng một chuỗi các nước đi tùy ý (có thể không bình thường) $\{d_1, d_2, \dots, d_n\}$, thì $P$ có thể được chuyển sang $Q$ và một số nước đi bình thường theo trình tự có được bằng cách sắp xếp lại chuyển động của một trình tự nhất định. (Chứng minh đi!)

Tiếp theo, cùng với các bản phát hành bài toán $(H, F)$, chúng ta sẽ xem xét “bài toán chuẩn hóa” sau: cho một vị trí $A$, trong đó tất cả là $A_{ij} \geq 0$ và một số là $A_{ij}>1$; phải mất vài động tác để đưa nó trở lại bình thường. Để giảm bài toán dẫn đầu xuống vị trí thứ hai, chúng ta tạo thành một vị trí $A_{ij}=H_{ij}+F_{ij}$ (hãy biểu thị nó là $A=H+F$), nói cách khác, đối với các chip $H$, chúng ta thêm một chip nữa ở mọi nơi trong $F$ - sau đó trong $F \cap H$ sẽ có hai chip. Hóa ra bài toán giải phóng $(H, F)$ tương đương với bài toán chuẩn hóa $H+F$. (Chứng minh đi!)

Lời giải "bài toán g" (Hình 4)

Bằng cách thêm một mã thông báo vào các ô của vùng $\Gamma$, chúng ta thu được sự chuẩn hóa bài toán như trong Hình 6.

Chúng tôi khuyên bạn nên tiếp tục với những nước đi tiếp theo trên bàn cờ. Cờ kiểm tra chung sẽ làm được - bạn sẽ không nhận được cờ kiểm tra trừ. Nhìn vào vị trí, chúng ta thấy có hai quầy tính tiền trên hình vuông $(1,1)$. Một trong số chúng phải được loại bỏ; điều này chỉ có thể được thực hiện bằng cách di chuyển $(1,1)$. Điều này có nghĩa là nước đi $(1,1)$ phải có trong bất kỳ lời giải nào, tức là đây là nước đi cần thiết. Chúng ta có thể cho rằng nó được thực hiện đầu tiên. Hãy làm điều đó. Chúng ta có được vị trí hiển thị trong hình thứ hai trong Hình 7. Các bước di chuyển tiếp theo (cần thiết) được hiển thị trong cùng một hình ảnh. Kết quả của việc thực thi chúng là vị trí ban đầu xuất hiện trở lại (chỉ di chuyển một ô lên trên và một ô sang phải). Theo đó, bài toán d) ban đầu là không thể quyết định được (hãy suy nghĩ kỹ về điều này!).

Thuật toán chung

Bằng cách sử dụng các bước di chuyển và chuẩn hóa tổng quát, chúng tôi có thể phân chia

Cơm. 7. (Về phần kết, xem trang 55.)
