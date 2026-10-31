---
id: 2019-7-shevtsova-mnogokratnaya-lemma-holla-v-zadachah-pro-mudretsov-1c4fb1b3
issue: kvant_2019_7
year: 2019
number: "7"
title: Bổ đề Hall trong các bài toán Sage
authors:
  - Шевцова М.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 29
page_last: 33
page_labels: 28, 30, 31
tag: TJ4H
lang: vi
source: kvant_digital
extraction: native
content_sha256: fbe616f2c13b7284640e84012cec75b27e2754dc5ab88d4e431b88447255981e
prompt_sha256: draft-1
translated_from: content/ru/2019/07/articles/04_shevtsova-mnogokratnaya-lemma-holla-v-zadachah-pro-mudretsov-1c4fb1b3.md
source_content_sha256: 2c70edc58a314a5e86ebcb3aba5c85b79fe619a557755fec675d4aa21f5c9f26
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

VÒNG TRÒN TOÁN HỌC

Bổ đề Hall trong các bài toán Sage

M.SHEVTSOVA

Giới thiệu

Bài toán liên quan đến các thuật toán hợp tác (nói một cách đơn giản hơn là bài toán của các nhà hiền triết) theo truyền thống được coi là khá khó. Thực tế là thường rất khó đưa ra một chiến lược hành động phù hợp để đảm bảo thành công cho các nhà hiền triết (ví dụ, khi đoán màu mũ họ đang đội); Không có những cân nhắc chung nào cho phép chúng tôi xây dựng các chiến lược cần thiết. Tất nhiên, có những ý tưởng tiêu chuẩn về đánh số, mã hóa, v.v., nhưng cách đánh số, mã hóa chính xác và từ đó truyền tải thông tin cần thiết phải được phát minh lại mỗi lần. Trong bài viết này, chúng tôi sẽ nói về một cách tiếp cận thú vị cho những vấn đề như vậy, trong đó không cần phải đưa ra các chiến lược hành động như vậy. Điều này có vẻ khó tin, nhưng có một cách để chứng minh sự tồn tại của một chiến lược mà không cần trình bày nó một cách rõ ràng! Những ý tưởng tương tự cũng áp dụng cho các bài toán về ảo thuật gia: bạn có thể chứng minh rằng một trò lừa có thể xảy ra mà không cần tiết lộ cách thực hiện nó! Chúng ta sẽ học cách thực hiện điều này bằng cách xem xét một kết quả tổ hợp cổ điển: Bổ đề Hall.

Bổ đề Hall thông thường và bội

Hãy bắt đầu với việc xây dựng bổ đề Hall cổ điển. Hãy tưởng tượng rằng các chàng trai và cô gái đến khiêu vũ vào buổi tối. Một số chàng trai và cô gái biết nhau. Như thường lệ, mọi chàng trai trẻ chỉ muốn khiêu vũ với người mình biết.

DOI: https://doi.org/10.4213/kvant20190705

⟦column⟧

anh ấy là một cô gái. Câu hỏi đặt ra là liệu tất cả các chàng trai có thể mời những cô gái mà họ biết khiêu vũ không? Hóa ra có một điều kiện cần và đủ đơn giản, theo đó mọi chàng trai sẽ tìm được bạn đời (mặc dù, có lẽ, một số cô gái sẽ không có bạn tình). Đây là bản chất của bổ đề Hall. Định lý 1. Bổ đề Hall. Xét một đồ thị hai bên, trong đó các đỉnh của phần thứ nhất là con trai và các đỉnh của phần thứ hai là con gái. Hãy kết nối một chàng trai và một cô gái có lợi thế nếu họ biết nhau. Giả sử rằng k chàng trai bất kỳ biết ít nhất k cô gái, với k bất kỳ từ 1 đến tổng số chàng trai. Sau đó tất cả các chàng trai sẽ có thể mời những cô gái mà họ biết đến khiêu vũ. Có nhiều cách khác nhau để chứng minh bổ đề Hall. Chúng tôi sẽ trình bày một chứng minh cổ điển, còn được gọi là phương pháp chuỗi xen kẽ. Các chứng minh khác có thể tìm thấy ở bài viết [1]. Bằng chứng. Hãy giả sử điều ngược lại: đừng để tất cả các chàng trai có thể khiêu vũ với những cô gái mà họ biết. Hãy xem xét số lượng lớn nhất các cặp nhảy có thể được hình thành. Tiếp theo, chúng ta hãy nhìn vào một chàng trai trẻ không có tên trong những cặp này. Anh ta bắt đầu tổ chức hội kín của mình. Vào ngày đầu tiên, chỉ có anh ấy ở trong xã hội này. Mỗi ngày tiếp theo, mỗi chàng trai trẻ bước vào hội này đều mời tất cả các cô gái mà anh ta biết đến đó và họ mang theo bạn nhảy (nếu có) đến đó.

Bài tập

1. Chứng minh rằng sớm hay muộn một cô gái chưa có bạn đời cũng sẽ bước vào xã hội. 2. Chứng minh rằng trong trường hợp này có thể chia nam và nữ thành từng cặp sao cho số lượng cặp tăng lên. 3. Suy ra bổ đề Hall từ đây.

Bản chất của bổ đề Hall là thiết lập sự tương ứng giữa hai loại đối tượng (trai và gái) khi đáp ứng các điều kiện kết nối nhất định giữa các đối tượng này. Không có nhiều mệnh đề như thế này trong tổ hợp, và bổ đề Hall có lẽ là mệnh đề mạnh mẽ nhất trong số đó. Để thực hành sử dụng nó, hãy thử giải câu bài toán sau.

⟦folio 28⟧

KVAN T 2019/№7

Bài tập

4. Mỗi hình vuông bằng nhau được chia thành 100 phần bằng nhau. Chứng minh rằng bạn có thể xếp chồng các hình vuông này lại và chọc thủng chúng ở 100 điểm sao cho mỗi phần trong số 100 phần của mỗi hình vuông đều bị xuyên thủng. 5. 7 ô vuông được cắt ra từ bàn cờ. Chứng minh rằng trên các ô còn lại có thể đặt 8 quân xe không tấn công lẫn nhau. Gợi ý. Xét một đồ thị hai phía có các đỉnh là các hàng (phần đầu tiên) và các cột (phần thứ hai) của một bảng đã cho.

Trong thực tế, chúng ta sẽ sử dụng bổ đề Hall trong một tình huống rất cụ thể, tương ứng với cái gọi là đồ thị lưỡng cực đều. Chúng ta hãy xây dựng riêng tuyên bố tương ứng, đây sẽ là câu nói then chốt cho lời giải bài toán với các nhà hiền triết. Định lý 2. Bổ đề Hall cho đồ thị chính quy. Giả sử rằng với một số l > 0 mỗi chàng trai biết chính xác l cô gái và mỗi cô gái biết chính xác l chàng trai. Sau đó tất cả các chàng trai sẽ có thể mời những cô gái mà họ biết đến khiêu vũ. Về mặt đồ thị, phát biểu này nghe như sau: nếu trong một đồ thị hai bên, bậc của tất cả các đỉnh là như nhau, thì các đỉnh của một phần có thể được liên kết với chính xác một đỉnh liền kề của một phần khác. Bằng chứng. Chúng ta hãy xem xét k chàng trai tùy ý và chứng minh rằng họ biết ít nhất k cô gái (trong trường hợp này, tuyên bố của chúng tôi tuân theo bổ đề Hall). Giả sử k chàng trai biết x cô gái. Hãy đếm số cạnh đến từ k chàng trai này và số cạnh đi vào x cô gái mà họ biết. Rõ ràng là không có nhiều xương sườn ra khỏi con trai hơn số xương sườn đi vào con gái. Khi đó kl d ​​​​xl, từ đó x t k, đây là điều cần chứng minh.

Bài tập 6. Một công ty bảo vệ tư nhân thuê n nhân viên bảo vệ. Mỗi ngày chúng cần được phân phối trên n đối tượng. Sau k ngày, hóa ra không có ai trực ở cùng một cơ sở hai lần. Chứng minh rằng có thể lập lịch cho n – k ngày còn lại sao cho tất cả lính canh đều trực một lần ở tất cả các đồ vật.

Trong phần tiếp theo, những ý tưởng liên quan đến việc áp dụng bổ đề Hall cho lời giải bài toán về các nhà ảo thuật sẽ rất quan trọng đối với chúng ta. Chúng tôi sẽ mang lại

⟦column⟧

Chúng tôi sẽ chỉ đưa ra một bài toán về chủ đề này, giới thiệu người đọc quan tâm đến bài viết [2]. Bài toán 1 (Olympic Toán toàn Nga, 2007). Một ảo thuật gia và một trợ lý sắp thực hiện một trò lừa như vậy. Khán giả viết một dãy N số lên bảng. Trợ lý của ảo thuật gia che hai số liền kề bằng một vòng tròn màu đen. Sau đó, ảo thuật gia bước vào. bài toán của anh ấy là đoán cả hai chữ số đóng (và thứ tự chúng nằm). Ở mức tối thiểu N nhà ảo thuật có thể đồng ý với trợ lý của mình để trò lừa được đảm bảo thành công? Đáp số: 101. Lời giải. Trước khi chuyển sang lời giải, chúng ta hãy cố gắng hiểu cách chúng ta có thể chính thức hóa việc đoán của nhà ảo thuật về cách sắp xếp các con số ban đầu. Chúng ta có một tập hợp gồm N chữ số ban đầu. Một trong những bộ này được viết bởi khán giả và ảo thuật gia phải đoán nó. Những bộ này sẽ tạo thành phần đầu tiên trong biểu đồ lưỡng cực của chúng tôi. Bản thân ảo thuật gia chỉ nhìn thấy một phần của bộ này với hai con số được trợ lý giấu đi. Các bộ này sẽ tạo thành các đỉnh của phần thứ hai của đồ thị lưỡng cực. Việc xem xét đơn giản này, cho phép chúng tôi đưa biểu đồ lưỡng cực vào bài toán của mình, gợi ý ước tính cho số N. Hãy xem xét tất cả các đỉnh của phần thứ hai. Có chính xác N 1 $10^{N} 2$ các đỉnh này. Mặt khác, có chính xác $10^{N}$ đỉnh trong nhịp đầu tiên. Rõ ràng là nếu phần thứ hai có ít đỉnh hơn phần thứ nhất thì thủ thuật sẽ thất bại. Thật vậy, trong trường hợp này sẽ có hai bộ N số bắt đầu, sau khi đóng các số sẽ cho ra bộ giống nhau mà ảo thuật gia sẽ nhìn thấy nên sẽ không đoán được bộ mong muốn. Từ đây ta có giới hạn về N:

N 1 $10^{N} 2 t 10^{N}$, từ đó N t 101. Vẫn còn phải đưa ra thuật toán cho các hành động của nhà ảo thuật để anh ta có thể đoán các số đóng theo một chuỗi có độ dài $N_{0} 101$. Đây là nơi chúng ta áp dụng bổ đề Hall. Chúng ta cần phải làm gì? Chúng ta có các đỉnh của nhịp thứ hai mà ảo thuật gia nhìn thấy và các đỉnh của nhịp đầu tiên mà khán giả mong muốn. Chúng ta cần thiết lập một song ánh, tức là.

⟦folio 30⟧

KVAN T 2019/№7

Định lý 4. Bổ đề bội Hall trong trường hợp chính quy. Xét một đồ thị hai bên, trong đó các đỉnh của phần thứ nhất là con trai và các đỉnh của phần thứ hai là con gái. Hãy kết nối một chàng trai và một cô gái có lợi thế nếu họ biết nhau. Giả sử rằng bậc của tất cả các đỉnh tương ứng với con gái là như nhau và bằng m và bậc của tất cả các đỉnh tương ứng với con gái cũng bằng nhau và bằng d. Chứng minh rằng mọi chàng trai đều có thể khiêu vũ với ª m ` « и » ¼ cô gái mà anh ấy biết và mỗi cô gái sẽ nhảy không quá một lần.

Bài tập 7. Chứng minh định lý này.

Bổ đề Sage và Hall

Vì vậy, chúng tôi đã tìm ra cách chứng minh khả năng thực hiện các thủ thuật bằng cách sử dụng bổ đề Hall: điều quan trọng cần cân nhắc là khả năng thiết lập sự xen kẽ giữa tập hợp các trạng thái bắt đầu mà ảo thuật gia nhìn thấy và tập hợp các trạng thái cuối cùng (do người xem nghĩ) cần phải đoán. Việc tiêm là một sự tương ứng sao cho các trạng thái bắt đầu khác nhau được liên kết với các trạng thái cuối cùng khác nhau. Tuy nhiên, trong các vấn đề về hiền nhân và chiến lược hợp tác, tình hình phức tạp hơn. Thứ nhất, trong đại đa số bài toán những nhà thông thái như vậy có thể (và nên) mắc sai lầm, tức là Đơn giản là không có cái gọi là phỏng đoán không thể sai lầm. Thứ hai, khả năng xảy ra lỗi khiến quá trình giải mã trở nên mơ hồ. Nói cách khác, tình huống cuối cùng có thể đạt được ngay từ đầu không phải là rõ ràng. Nhưng chúng ta có bổ đề Hall cho trường hợp như vậy! Vấn đề quan trọng cần cân nhắc để làm cho đa bổ đề của Hall hoạt động được trong các bài toán hiền triết là như sau. Giả sử các nhà thông thái được tặng những chiếc mũ có nhiều màu sắc khác nhau và họ cần đoán màu mũ của mình, chỉ nhìn thấy mũ của những nhà thông thái khác trước mặt họ. Hãy đánh số những nhà thông thái và đặt mũ cho họ bằng mọi cách có thể. Hãy trang bị cho mình một chiếc máy ảnh và bắt đầu chụp ảnh chúng. Chúng tôi sẽ chụp ảnh từng tình huống từ trên cao để có

⟦column⟧

tất cả những chiếc mũ đều có thể nhìn thấy được, và sau đó chúng tôi sẽ đưa máy ảnh cho từng nhà thông thái để chính anh ta có thể chụp ảnh tất cả những nhà thông thái khác mà anh ta nhìn thấy từ vị trí của mình. Chúng ta hãy xem xét một biểu đồ hai bên trong đó các đỉnh của phần đầu tiên là tất cả các bức ảnh do chúng ta chụp (trên thực tế, chỉ là tất cả các cách sắp xếp ban đầu có thể có của các mũ trên các cây hiền triết), và phần thứ hai là tất cả các bức ảnh được chụp bởi tất cả các nhà hiền triết. Tiếp theo, chúng ta nối đỉnh v từ phần thứ hai với đỉnh u từ phần đầu tiên nếu bức ảnh v được chụp bởi một trong những nhà thông thái trong tình huống u. Người khôn ngoan nên làm gì? Với mỗi bức ảnh chụp, nhà hiền triết phải cố gắng khôi phục lại màu sắc của chiếc mũ của mình. Tất nhiên, trong một số trường hợp, người khôn ngoan sẽ sai. Chúng ta cần tìm những nhà thông thái đảm bảo sẽ trả lời đúng. Chính xác hơn, chúng ta nên phân bổ đều đáp số của tất cả các nhà thông thái trong số các bức ảnh u, sao cho mỗi bức ảnh có đủ số lượng đáp số đúng. Để làm điều này, chúng ta sử dụng bổ đề bội Hall. Những nhà hiền triết có quan điểm được chọn theo một bức ảnh chung nhất định sẽ trả lời với giả định rằng họ đang ở trong tình huống này và do đó đúng. Do đó, nếu mỗi bức ảnh u được liên kết với ít nhất m bức ảnh $u_{1},......, u_{m}$ do các nhà hiền triết thực hiện, thì trong mỗi tình huống có ít nhất m nhà hiền triết sẽ trả lời đúng. Chúng ta sẽ xác định số m từ tham số bài toán. Chúng ta hãy xem kế hoạch này hoạt động như thế nào trong thực tế. Bài toán 2 (Olympic Toán học Mátxcơva, 2010). Một đội gồm n nhà thông thái tham gia trò chơi: mỗi người đội một chiếc mũ có k màu đã biết trước, sau đó khi tiếng còi thổi, tất cả các nhà thông thái đồng loạt chọn cho mình một chiếc khăn. Một đội nhận được số điểm bằng bao nhiêu người tham gia có mũ cùng màu với khăn quàng cổ của mình (có đủ số lượng khăn quàng cổ và mũ màu bất kỳ; trong quá trình chơi, mỗi người tham gia không nhìn thấy mũ của mình mà nhìn thấy mũ của người khác nhưng không có quyền đưa ra bất kỳ thông tin nào trước khi tiếng còi vang lên). Số điểm lớn nhất mà đội đã lên kế hoạch trước là bao nhiêu?

⟦folio 31⟧

TOÁN HỌC

kế hoạch hành động của từng thành viên, liệu kế hoạch đó có được đảm bảo sẽ nhận được không? Đáp số: > n k @. Lời giải. Hãy xem xét biểu đồ được mô tả ở trên, trong đó các đỉnh của phần thứ nhất là tất cả các vị trí xuất phát có thể có của đội các nhà thông thái (tức là tất cả các phương án có thể có để đội những chiếc mũ màu k lên họ) và các đỉnh của phần thứ hai là những bức ảnh được chụp bởi mỗi nhà thông thái trong mỗi tình huống xuất phát có thể xảy ra. Rõ ràng là trong phần đầu tiên có $k^{n}$, và trong phần thứ hai có $nk^{n} 1$ đỉnh. Mỗi đỉnh của phần thứ nhất được nối với n đỉnh của phần thứ hai, vì mỗi người trong số n nhà thông thái có thể thấy cách sắp xếp chỗ ngồi như vậy. Mặt khác, mỗi đỉnh của phần thứ hai được kết nối với k đỉnh của phần thứ nhất, vì mỗi nhà hiền triết có k lựa chọn màu cho chiếc khăn quàng cổ của mình. Bây giờ chúng ta hãy xây dựng một thuật toán hành động cho các nhà thông thái, trong đó họ được đảm bảo ghi được > n k @ điểm. Để làm được điều này, chỉ cần chứng minh rằng có thể liên kết với từng đỉnh từ phần thứ nhất > n k @ đỉnh từ phần thứ hai là đủ. Chúng ta hãy sử dụng bổ đề bội Hall trong trường hợp thông thường. Chúng ta hãy áp dụng bổ đề này bằng cách gán cho mỗi cách sắp xếp ban đầu u hiền nhân từ phần thứ nhất m > n k @ đỉnh từ phần thứ hai. Chính những bậc hiền nhân này sẽ trả lời đúng trong sự sắp xếp ban đầu của bạn. Như vậy, hiền nhân có thể đảm bảo sẽ đạt được > n k @ điểm. Vẫn còn phải chứng minh rằng không thể đảm bảo có thêm > n k @ điểm. Trên thực tế, điều này cũng được giải thích bằng khả năng áp dụng bổ đề Hall: nếu có thể liên kết với mỗi đỉnh của phần thứ nhất nhiều > n k @ đỉnh từ phần thứ hai, thì đơn giản là chúng ta sẽ không có đủ đỉnh trong phần thứ hai. Về mặt hình thức, điều này có thể được chứng minh như sau. Giả sử có một chiến lược dành cho các hiền nhân đảm bảo ít nhất > n k @ 1 điểm. Lưu ý rằng đáp số của mỗi hiền nhân được xác định duy nhất bởi màu mũ của các hiền nhân khác. Hãy nối từng bức ảnh trong phần đầu tiên với quan điểm của những nhà thông thái trả lời đúng trong tình huống này. Nếu với mỗi màu có nhiều màu hơn > n k @, thì

$nk^{n} 1 t k^{n} > n k$ @ 1! $k^{n} > n k$ @ $nk^{n} 1$ – mâu thuẫn. Như vậy, tối đa

VÒNG TRÒN

Tổng số điểm mà các hiền nhân ghi được là > n k@.

⟦column⟧

Có một lớp bài toán về các nhà hiền triết, nơi bạn cần tìm xác suất cao nhất để đảm bảo đoán được màu mũ của bạn. Ví dụ: hãy xem xét các sửa đổi sau của bài toán trước đó.

Bài tập

8. Theo các điều kiện của bài toán trước đó, chúng ta sẽ giả sử rằng n < k. Xác suất tối đa để ít nhất một nhà thông thái đoán được màu mũ của mình là bao nhiêu? 9. Lần này các nhà thông thái viết màu sắc mong đợi của mũ r lần, nhưng họ không nhìn thấy hàng xóm của mình viết gì. Xác suất tối đa mà ít nhất một người trong số họ đoán đúng trong r lần thử mà các nhà hiền triết có thể đảm bảo là bao nhiêu?

Bài toán 3 (Olympic Leonard Euler, 2013). 99 nhà thông thái ngồi vào một chiếc bàn tròn. Họ biết rằng năm mươi người trong số họ đội mũ có một trong hai màu, và bốn mươi chín người khác - một màu khác (nhưng không biết trước màu nào trong hai màu có 50 mũ, và màu nào - 49). Mỗi nhà hiền triết nhìn thấy màu sắc của tất cả các mũ ngoại trừ mũ của mình. Tất cả các nhà thông thái phải đồng thời viết (mỗi người trên một tờ giấy riêng) màu mũ của mình. Liệu các nhà thông thái có thể thống nhất trước câu trả lời để ít nhất 74 người trong số họ đưa ra câu trả lời đúng đáp số? Đáp số: vâng. Lời giải. Rõ ràng là nếu một nhà hiền triết nhìn thấy 50 chiếc mũ cùng màu, thì ông ta có một chiếc mũ có màu khác với chiếc mũ trong số đó có 50 chiếc, tức là ông ta biết chiếc mũ của mình. Điều này có nghĩa là 49 nhà thông thái biết màu mũ của mình và sẽ trả lời đúng. 50 nhà thông thái còn lại nhìn thấy 49 chiếc mũ cùng màu và 49 chiếc mũ khác sẽ bị coi là xui xẻo. Hãy đảm bảo rằng 25 nhà thông thái kém may mắn luôn đoán đúng giới hạn. Hãy xem xét biểu đồ được mô tả ở trên, trong đó các đỉnh của phần đầu tiên là tất cả các vị trí có thể có của đội các nhà thông thái, và các đỉnh của phần thứ hai là những bức ảnh được chụp bởi mỗi nhà thông thái kém may mắn trong mỗi tình huống xuất phát có thể xảy ra. Mỗi đỉnh từ nhịp đầu tiên được kết nối với 50

(Tiếp theo trang 34)
