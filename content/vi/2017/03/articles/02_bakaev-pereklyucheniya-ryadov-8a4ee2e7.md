---
id: 2017-3-bakaev-pereklyucheniya-ryadov-8a4ee2e7
issue: kvant_2017_3
year: 2017
number: "3"
title: Chuyển đổi hàng
authors:
  - Бакаев Е. В.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 41
page_last: 47
page_labels: 40-45
tag: DI3H
lang: vi
source: kvant_digital
extraction: native
content_sha256: d930b2b388a20068da7e979e7babc056bbda7215aad18da4ddc2e70243027fb3
prompt_sha256: draft-1
translated_from: content/ru/2017/03/articles/02_bakaev-pereklyucheniya-ryadov-8a4ee2e7.md
source_content_sha256: 4d680d3f3468c5e384a40f2dd977dfa19e66c1cbab1543cf6c4de5ddc00d97ca
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

VÒNG TRÒN TOÁN HỌC

Chuyển đổi hàng

E.BAKAEV

Hãy bắt đầu với bài toán hợp lý để xem xét, đây là $2 \times 2$. Chúng ta hãy tìm hiểu xem chất trám nào có thể được lấy từ chất trám nào. Có $2^{4} = 16$ cách để điền vào các ô của bảng $2 \times 2$ với những ưu và nhược điểm. Bạn có thể xem xét tất cả và lập sơ đồ (đồ thị). Chúng ta sẽ kết nối hai miếng trám bằng một đường thẳng (cạnh) nếu có thể lấy được một miếng trám từ miếng trám kia chỉ bằng cách chuyển đổi hàng (hình2).

Bài toán 1. Tất cả các ô của bảng $8 \times 8$ chứa đầy các dấu cộng và dấu trừ (mỗi ô một ký tự). Một thao tác cho phép bạn chọn bất kỳ hàng (hàng hoặc cột) nào và thay đổi dấu trong mỗi ô của nó thành ô đối diện. Lúc đầu tất cả các dấu hiệu đều tích cực. Phải chăng sau một vài thao tác như vậy, hóa ra chỉ có một điểm trừ trong bảng? hình 1 hiển thị một ví dụ về thao tác như vậy.

⟦figure⟧

Hình 1

Chúng tôi sẽ không chỉ giải quyết bài toán này mà còn tìm ra bảng nào có thể được lấy từ bảng nào bằng cách sử dụng các thao tác này. Chúng ta sẽ gọi hàng và cột là hàng. Thao tác được mô tả ở bài toán 1 sẽ được gọi là chuyển đổi hàng.

Bảng $2 \times 2$

Thay vì giải bài toán về bảng $8 \times 8$, trước tiên chúng ta hãy xử lý một bảng nhỏ trong đó tất cả các tùy chọn đổi màu có thể có đều có thể được sắp xếp theo cách thủ công. Bàn nhỏ nhất

Các vấn đề trong bài viết đều được đưa ra lời giải, nhưng bạn nên tự mình suy nghĩ về vấn đề trước khi đọc lời giải - điều này sẽ mang lại nhiều lợi ích hơn. Bài viết cũng có các bài tập, chúng thường đơn giản hơn bài toán, chúng cũng có giá trị giải, điều này có thể giúp bạn hiểu nội dung tiếp theo. Đáp số và gợi ý cho các bài tập được đưa ra ở cuối con số.

⟦figure⟧

Hình 2

Có thể thấy rằng tất cả các miếng trám được chia thành hai nhóm (hai thành phần được kết nối của biểu đồ): các miếng trám của một nhóm không thể lấy được từ các miếng trám của nhóm khác. Các mục trong mỗi nhóm có điểm gì chung? Chất trám của các nhóm khác nhau khác nhau như thế nào? Bạn có thể nhận thấy rằng trong các miếng trám của một nhóm có số dấu cộng chẵn và trong các miếng trám của nhóm kia có một số lẻ. Điều này có thể được chứng minh mà không cần xem qua tất cả các tùy chọn điền. Thật vậy, với mỗi nước đi chúng ta đổi hai dấu, tức là đổi 2 dấu cộng thành 2 dấu trừ, hoặc đổi 2 dấu trừ thành 2 dấu cộng, hoặc số dấu cộng và dấu trừ không thay đổi. Điều này có nghĩa là số lượng điểm cộng vẫn giữ nguyên tính chẵn lẻ khi chuyển hàng.

Bài tập 1. Trên bàn có 5 cái ly úp ngược. Được phép lật 2 ly bất kỳ cùng lúc. Có thể lặp lại được không

⟦folio 40⟧

KVANT 2017/№3

Khi thực hiện thao tác này, hãy đặt tất cả các kính đúng cách?

Số điểm cộng chẵn

Chúng tôi đã tìm ra hoàn toàn các bảng $2 \times 2$. Những cân nhắc tương tự sẽ giúp ích trong lời giải bài toán 1. Thật vậy, trong trường hợp này, tính chẵn lẻ của số dấu cộng trong toàn bộ bảng sẽ không thay đổi. Hãy chứng minh điều đó. Giả sử có x dấu cộng ở hàng nào đó thì sau khi đổi chỗ sẽ có 8 - x dấu cộng ở hàng này, còn ở phần còn lại của bảng dấu cộng sẽ giữ nguyên. Nhưng các số x và 8 – x có cùng tính chẵn lẻ. Điều này có nghĩa là tính chẵn lẻ của số dấu cộng trong toàn bộ bảng sẽ không thay đổi - đó là một bất biến. (Bất biến là một thuộc tính không thay đổi dưới các phép biến đổi đã cho.) Vì vậy, lúc đầu có 64 điểm cộng trong bảng, nghĩa là số của chúng sẽ luôn chẵn và không thể bằng 63. Bài toán 1 đã được giải.

⟦column⟧

tế bào cuối cùng - lợi thế. Có thể chuyển đổi hàng để tất cả các dấu hiệu trở thành điểm cộng? Liệu lời giải, tương tự như lời giải của bài toán đầu tiên, có phù hợp với họ không? Không: trong bài toán 2 3 chữ số thay đổi mỗi lần, có nghĩa là tính chẵn lẻ của số dấu cộng thay đổi mỗi lần và có thể là bất kỳ. Trong bài toán 3, tính chẵn lẻ của số dấu cộng thực sự là bất biến, nhưng điều này không gây ra mâu thuẫn - ở vị trí ban đầu và vị trí cuối cùng, tính chẵn lẻ của chúng là như nhau. Làm thế nào để giải quyết bài toán 2? Hãy nhìn vào vị trí bắt đầu và kết thúc (hình3). Hãy giả sử rằng người ta có thể có được một cái khác.

⟦figure⟧

Hình 3

Bài tập

2. Có 15 cái ly đặt úp ngược trên bàn. Được phép lật bất kỳ số ly chẵn nào cùng một lúc. Có thể lặp lại thao tác này và đặt tất cả các kính một cách chính xác không? 3. Từ bảng A, bằng cách chuyển đổi các hàng, chúng ta thu được bảng B. Chứng minh rằng từ bảng B, bằng cách chuyển đổi các hàng, chúng ta có được bảng A. 4. Bảng $8 \times 8$ chứa đầy các điểm cộng và điểm trừ, sau đó chúng ta thực hiện một số lần chuyển đổi các hàng. a) Có thể thấy rằng việc điền các dấu cuối cùng vào bảng khác với lần điền đầu tiên trong đúng một ô không? b) Phần trám cuối cùng và phần trám ban đầu có thể khác nhau ở tất cả các ô không? c) Có thể thu được “màu cờ vua” bằng cách chỉ điền các dấu cộng, tức là cách điền như vậy trong đó hai dấu hiệu liền kề ở một bên khác nhau không?

Hãy xem xét hai bài toán nữa, tương tự như cái đầu tiên. Bài toán 2. Trong bảng $3 \times 3$ có ​​dấu trừ ở một ô ở góc và dấu cộng ở các ô còn lại. Có thể chuyển đổi hàng để tất cả các dấu hiệu trở thành điểm cộng? Bài toán 3. Trong bảng $8 \times 8$ có các điểm trừ ở bốn ô góc;

Chúng ta hãy nhìn vào ô trên cùng bên trái. Có một điểm trừ trong đó, nhưng cũng phải có một điểm cộng. Điều này có nghĩa là nó phải được thay đổi một số lần lẻ. Biển báo thay đổi khi một trong hai hàng tại giao điểm của nó được chuyển đổi, do đó một trong các hàng phải được thay đổi số lần lẻ và hàng còn lại là số chẵn. Do tính đối xứng của tình huống, chúng ta có thể giả sử rằng hàng được chuyển đổi số lần lẻ và cột (hình4,a) được chuyển đổi số lần chẵn.

⟦figure⟧

Hình 4

Bây giờ chúng ta hãy nhìn vào dấu hiệu ở giữa ở hàng trên cùng. Anh ấy là một điểm cộng và nên tiếp tục như vậy. Điều này có nghĩa là nó phải được thay đổi một số lần chẵn. Nhưng hàng đầu tiên thay đổi số lần lẻ, nghĩa là cột thứ hai cũng thay đổi số lần lẻ. Lý do tương tự, nhưng bây giờ xét đến ô giữa của cột đầu tiên, chúng ta có thể kết luận rằng hàng thứ hai thay đổi số lần chẵn (hình4,b).

⟦folio 41⟧

TOÁN HỌC

Nhưng khi đó cột giữa và hàng giữa sẽ thay đổi tổng số lần lẻ, tức là dấu ở giữa bảng sẽ thay đổi số lần lẻ và trở thành dấu trừ chứ không phải dấu cộng (hình4,c). Chúng tôi gặp mâu thuẫn - bạn không thể chuyển từ vị trí này sang vị trí khác bằng cách chuyển hàng. Bài toán2 đã giải quyết. Lưu ý rằng để đạt được sự mâu thuẫn, chúng ta chỉ cần coi 4 dấu tạo thành hình vuông $2 \times 2$ là đủ, còn các dấu ở các ô còn lại cho lời giải là không quan trọng. Chúng ta hãy nhớ rằng khi chuyển đổi các hàng trong hình vuông $2 \times 2$ tính chẵn lẻ của số dấu cộng trong đó không thay đổi, vì mỗi lần 2 chữ số thay đổi. Nhưng điều này cũng đúng với hình vuông $2 \times 2$, được đánh dấu bên trong hình vuông lớn hơn! Theo đó, lời giải bài toán 2 có thể được phát biểu ngắn gọn hơn bằng cách xét bình phương $2 \times 2$ (xem hình4,c) và lưu ý rằng tính chẵn lẻ của số dấu cộng trong đó là bất biến.

Bài tập 5. Đảm bảo rằng bài toán 3 được giải theo cách tương tự.

Một số bài toán được giải bằng cách sử dụng cùng một bất biến có vẻ đơn giản như trong bài toán 2 và 3 (tính chẵn lẻ của số dấu cộng), nhưng có thể khó đoán được vùng nào (trong trường hợp của chúng tôi đó là một hình vuông nhất định $2 \times 2 )$ một bất biến như vậy có tác dụng. Bạn có thể tìm thấy bài toán như vậy trong bài viết của Yu. Ionin, L. Kurlyandchik “Tìm kiếm một bất biến” trong «Kvant» Số 2 cho năm 1976, xem thêm bài toán 2 và 3 ở cuối bài viết này.

Bài tập

6. Trong bảng $8 \times 8$ ban đầu tất cả các dấu hiệu đều là dấu cộng. Sau đó, chúng tôi thực hiện một số chuyển đổi hàng. Có bao nhiêu điểm cộng có thể xuất hiện trên đường chéo chính sau một số phép tính lẻ? 7. Trong bảng $8 \times 8$ ban đầu tất cả các dấu hiệu đều là dấu cộng. Sau đó, chúng tôi thực hiện một số chuyển đổi hàng, sau đó một số biển báo đã bị ẩn đi. a) Một số dấu hiệu đã biết (hình5,a). Tìm các ký tự được đánh dấu bằng dấu chấm hỏi. b) Câu hỏi tương tự cho bảng ở hình 5, b. c) Một số dấu hiệu đã biết (hình5,c). Có thể sử dụng thông tin này để xác định xem số thao tác chẵn hay lẻ đã được thực hiện không? d) Một số dấu hiệu đã biết (hình5,d). Hãy tìm cái được đánh dấu bằng dấu chấm hỏi.

VÒNG TRÒN

⟦column⟧

⟦figure⟧

Hình 5

Số lượng hành động

Như chúng ta đã biết, dấu trong một ô sẽ chỉ thay đổi nếu một số lẻ các thao tác chứa ô này được thực hiện. Trước tiên, thứ tự thực hiện các thao tác không ảnh hưởng đến kết quả. Thứ hai, chỉ có tính chẵn lẻ của số lượng các thao tác như vậy mới quan trọng, tức là kết quả sẽ không thay đổi, ví dụ: nếu bạn thay đổi hàng không phải 13 lần mà là 1 lần. Điều này có nghĩa là chúng ta có thể giả định rằng mỗi hàng có thể không được chuyển đổi chút nào hoặc được chuyển đổi một lần và việc chuyển đổi nhiều lần hơn là vô nghĩa. Hóa ra là nếu có thể lấy được một số phần điền vào bảng $n \times n$ từ một bảng khác, thì việc này có thể được thực hiện không quá 2n thao tác (vì có tổng cộng 2n hàng). Nhưng đánh giá mạnh mẽ hơn cũng đúng. Bài toán 4 (A. Kanel-Belov, Giải đấu các thành phố XXXIII, 2012). Các ô của bảng $n \times n$ chứa ưu và nhược điểm. Trong một nước đi, bạn được phép đổi tất cả các dấu ở hàng tùy ý hoặc ở cột tùy ý sang dấu ngược lại. Được biết, từ sự sắp xếp ban đầu, người ta có thể thu được một trong đó tất cả các ô đều chứa dấu cộng. Chứng minh rằng điều này có thể đạt được không quá n bước. Chúng tôi đã chỉ ra rằng luôn có thể thực hiện được điều đó trong vòng 2n nước đi. Nhưng khi nào chúng ta có thể cần chính xác 2n bước di chuyển? Khi chúng tôi chuyển đổi mỗi hàng một lần. Nhưng sau đó mỗi ký tự sẽ thay đổi 2 lần, vì dòng và cột của nó đã thay đổi. Điều này có nghĩa là việc lấp đầy bàn sẽ không thay đổi, vì vậy nó có thể được lấy nhanh hơn - mà không cần thực hiện một động thái nào! Vì thế

⟦folio 42⟧

KVANT 2017/№3

Như vậy, chúng ta đã chứng minh được rằng không cần thiết phải thực hiện 2n nước đi. Hãy tiếp tục. Khi nào bạn có thể cần chính xác 2n – 1 nước đi? Khi họ chuyển đổi tất cả các hàng ngoại trừ một hàng. Sau đó, các dấu hiệu của chuỗi này sẽ thay đổi một lần và các dấu hiệu còn lại - 2 lần. Một lần nữa, việc lấp đầy này có thể đạt được nhanh hơn - chỉ cần chuyển một hàng là đủ, chúng tôi không chuyển đổi. Nhưng điều tương tự có thể được thực hiện trong các trường hợp khác! Giả sử rằng chúng ta đã chuyển đổi một số hàng x. Nếu đổi không phải những hàng này mà đổi tất cả các hàng khác thì sẽ có 2n – x nước đi nhưng kết quả không thay đổi (nếu dấu thay đổi 2 lần thì bây giờ không thay đổi; nếu không thay đổi thì bây giờ nó sẽ thay đổi 2 lần; nếu dấu thay đổi 1 lần thì bây giờ nó sẽ thay đổi 1 lần). Theo đó, nếu có nhiều hơn n nước đi, thì sau khi “đảo ngược” hành động như vậy, chúng ta sẽ nhận được kết quả tương tự với ít hơn n hành động. Bài toán 4 đã được giải quyết.

Bài tập 8. Có thể củng cố điểm ở bài toán 4 không? Nói cách khác, có phải lúc nào bạn cũng có thể đạt được điều mình muốn chỉ sau n – 1 nước đi không?

Tiêu chí khả thi

Chúng ta hãy quay trở lại câu hỏi chất trám nào có thể được lấy từ chất trám nào. Chúng ta sẽ gọi phần điền có thể thực hiện được nếu nó có thể thu được bằng cách chuyển đổi các hàng từ phần điền trong đó tất cả các dấu hiệu đều là dấu cộng. Đối với lời giải bài toán 2, chúng tôi đã phát hiện ra rằng nếu phần điền chứa hình vuông $2 \times 2$ trong đó có số dấu cộng lẻ thì điều đó là không thể thực hiện được. Thay vì hình vuông $2 \times 2$, bạn có thể coi 4 ô bất kỳ là các đỉnh của hình chữ nhật có các cạnh song song với các cạnh của bảng (ví dụ về 4 ô như vậy là trong hình 5,a). Trong bốn ô như vậy, số chẵn lẻ của số điểm cộng cũng không thay đổi nên nếu ban đầu chúng đều là điểm cộng thì giữa chúng sẽ luôn có số điểm cộng chẵn. Điều này có nghĩa là nếu có 4 ô trong đó có số dấu cộng lẻ thì việc điền là không khả thi. Nhưng nếu chúng không được tìm thấy, điều này có nghĩa là nó khả thi? Vâng, hóa ra tiêu chí sau đây của chủ nghĩa hiện thực là đúng. Tương đương

⟦column⟧

Có ba thuộc tính của sự lấp đầy (tức là, nếu một trong những thuộc tính này được thỏa mãn thì hai thuộc tính còn lại cũng được thỏa mãn): 1) nó có thể thực hiện được; 2) trong bất kỳ hình vuông nào $2 \times 2$ số điểm cộng chẵn; 3) Trong 4 ô bất kỳ là các đỉnh của hình chữ nhật có cạnh song song với các cạnh của bàn thì có số chẵn. Thuộc tính thứ hai tiếp nối trực tiếp từ thuộc tính thứ ba, bởi vì một hình vuông $2 \times 2$ - một trường hợp đặc biệt của hình chữ nhật như vậy. Chúng tôi đã chỉ ra cách thứ hai và thứ ba tiếp nối thuộc tính đầu tiên. Để hoàn thành việc chứng minh tính tương đương của ba tính chất, chúng ta sẽ chỉ ra tính chất thứ nhất nối tiếp tính chất thứ hai như thế nào. Hãy xem xét một cách điền tùy ý mà thuộc tính thứ hai chứa: trong đó trong bất kỳ hình vuông nào $2 \times 2$ số lợi ích chẵn. Hãy để chúng tôi chứng minh rằng nó có thể thực hiện được, tức là. Hãy để chúng tôi chứng minh rằng bằng cách chuyển đổi các hàng, nó có thể dẫn đến tình huống trong đó tất cả các dấu hiệu đều là dấu cộng. Hãy thực hiện những thay đổi như vậy Hình Bao gồm 6 hàng sao cho tất cả các dấu của cột đầu tiên và hàng đầu tiên đều trở thành dấu cộng. Xem ví dụ tại hình 6.

Bài tập 9. Chứng minh rằng luôn có thể thực hiện được việc chuyển đổi như vậy.

Bây giờ chúng ta sẽ chứng minh rằng sau những lần chuyển đổi như vậy, tất cả các ký hiệu khác của bảng đều trở thành điểm cộng. Bất kỳ hình vuông nào $2 \times 2$ vẫn có số điểm cộng chẵn vì việc chuyển đổi hàng không vi phạm thuộc tính này. Bây giờ hãy xem xét hình vuông phía trên bên trái $2 \times 2$ (hình7,a). Ba dấu hiệu của nó là điểm cộng,

⟦figure⟧

Hình 7

điều đó có nghĩa là điều thứ tư là một điểm cộng. Hãy xem xét hình vuông tiếp theo $2 \times 2$, di chuyển một ô sang phải (hình7,b), tình huống cũng tương tự. Xem xét tất cả các ô vuông như vậy một cách tuần tự, chúng ta thấy rằng tất cả các ký hiệu của bảng đều là điểm cộng.

⟦folio 43⟧

TOÁN HỌC

Bài tập

10. Sự tương đương của tính chất thứ hai và tính chất thứ ba có thể được chứng minh mà không cần sử dụng tính chất thứ nhất hoặc dấu hiệu chuyển đổi. Hãy thử điều này. 11. Một trong các hàng của bảng đã triển khai $8 \times 8$ chứa x dấu cộng. Chứng minh rằng mỗi dòng của phần điền này chứa x hoặc 8 – x dấu cộng. 12. Hãy xem xét một số cách điền bảng $8 \times 8$ có thể thực hiện được. Giả sử có x điểm trừ ở một trong các hàng của nó và điểm trừ y ở một trong các cột và tại giao điểm của chúng có một điểm cộng. Có bao nhiêu điểm trừ trong cách điền này? 13. Có cách nào khả thi để hoàn thành bảng $8 \times 8$ chứa chính xác 6 điểm cộng không?

Số lượng điền đã bán

Hãy điền vào hàng đầu tiên và cột đầu tiên của bảng $m \times n$ một cách tùy ý. Sau đó: trước tiên, các ô còn lại có thể được điền theo cách khả thi; thứ hai, điều này có thể được thực hiện theo cách duy nhất.

Bài tập 14. Chứng minh các khẳng định trên. Gợi ý. Sử dụng tiêu chí khả thi và kết quả của Bài tập 9.

Như vậy, số cách điền vào bảng những ưu và nhược điểm để việc điền có thể thực hiện được bằng số cách điền vào hàng đầu tiên và cột đầu tiên của nó một cách tùy ý. Ở hàng đầu tiên và cột đầu tiên của bảng $m \times n$ có tổng cộng m + n – 1 ô, nghĩa là có $2 m + n - 1$ phần điền có thể thực hiện được của bảng như vậy.

Điền đồ thị

Trong phần về bảng $2 \times 2$, chúng tôi đã xây dựng một biểu đồ trong đó một cạnh kết nối các đỉnh tương ứng với các phần lấp đầy bảng đó mà có thể lấy được từ nhau chỉ bằng cách chuyển đổi một hàng. Chúng ta có thể xem xét cùng một biểu đồ, nhưng đối với bảng $m \times n$ (nó có $2^{mn}$ đỉnh). Mỗi phần điền thuộc về một số thành phần được kết nối của biểu đồ này. Hai miếng trám thuộc về cùng một thành phần nếu cái này có thể lấy được từ cái kia bằng cách chuyển đổi hàng.

VÒNG TRÒN

Bài tập

15. Có bao nhiêu miếng trám trong thành phần được kết nối chứa miếng trám, trong đó tất cả các dấu hiệu đều là dấu cộng? 16. Có bao nhiêu thành phần liên thông trong biểu đồ này và có bao nhiêu phần lấp đầy trong mỗi thành phần đó? Gợi ý. Bất kỳ phần điền nào cũng có thể được thực hiện bằng cách chuyển các hàng sang phần điền trong đó ở hàng đầu tiên và cột đầu tiên tất cả các dấu hiệu đều là dấu cộng. Trong trường hợp này, tính chẵn lẻ của số dấu cộng ở 4 ô bất kỳ là các đỉnh của hình chữ nhật có cạnh song song với các cạnh của bảng sẽ không thay đổi.

Tìm số lượng miếng trám có thể thực hiện được là phần b) bài toán M665 “Bài toán Kvant. Hãy gặp cô ấy lời giải trong «Kvant» Số 9 năm 1981.

⟦column⟧

Chuyển đổi ký tự phụ trợ

Điều kiện của bài toán tiếp theo không nói lên điều gì về các phép toán đổi dấu, tuy nhiên, các phép toán đó có thể được xem xét và khi đó bài toán sẽ giúp giải được tiêu chí khả năng thực hiện được. Bài toán 5 (E. Bakaev, Giải đấu các thành phố XXXIV, 2012, M2289). Một số ô của hình vuông $11 \times 11$ chứa các dấu cộng và có một số dấu cộng chẵn. Mỗi ô vuông $2 \times 2$ cũng có số điểm cộng chẵn. Chứng minh rằng số điểm cộng trong 11 ô vuông trên đường chéo chính của hình vuông là số chẵn. Đối với bảng từ bài toán này, thuộc tính thứ hai được thỏa mãn, điều đó có nghĩa là việc điền nó là khả thi. Sau đó, chúng ta có thể xem xét trình tự chuyển đổi các hàng, điều này cho phép chúng ta có được phần điền nhất định từ phần điền chỉ có điểm cộng. Hãy xem xét số lượng điểm cộng trong toàn bộ bảng. Mỗi chuyển đổi hàng thay đổi 11 dấu, có nghĩa là nó thay đổi tính chẵn lẻ của số dấu cộng trong toàn bộ bảng. Vì theo điều kiện, có số chẵn trong toàn bộ bảng và ban đầu số dấu cộng $11^{2} = 121$ là số lẻ nên sau đó có số phép toán lẻ. Mỗi thao tác thay đổi một dấu trên đường chéo và do đó làm thay đổi tính chẵn lẻ của số dấu cộng trên đường chéo. Vì ban đầu có 11 điểm cộng và có số phép tính lẻ nên sẽ có số điểm cộng chẵn trên đường chéo.

Bài tập 17. Giải bài toán 5 theo cách khác, không xét đến thao tác đổi dấu.

⟦folio 44⟧

KVANT 2017/№3

Hãy thử giải bài toán tiếp theo bằng cách chuyển đổi hàng phụ.

Bài tập 18 (V. Proizvolov, Olympic toàn liên minh XXIII, M1181). Có 8 quân xe được đặt trên bàn cờ sao cho chúng không tấn công lẫn nhau. Chứng minh rằng có số chẵn xe nằm trên các ô màu đen.

Dấu hiệu bị xóa

Như chúng tôi đã tìm ra, bằng cách sử dụng m + n – 1 dấu của bảng, bạn có thể khôi phục phần còn lại nếu biết rằng việc điền là khả thi. Ví dụ: điều này có thể được thực hiện bằng các ký tự của một hàng và một cột. Nhưng các dấu m + n – 1, từ đó việc điền có thể thực hiện được có thể được xây dựng lại, có thể được định vị theo cách khác, như có thể thấy khi giải Bài tập 19.

Bài tập

19. Chứng minh rằng tất cả các dấu hiệu điền chưa biết trên hình 5,r đều có thể được khôi phục duy nhất. 20. Phần điền có được khôi phục duy nhất cho 50 ký tự bất kỳ của bảng $8 \times 8$ không?

Vì vậy, đối với một số cách sắp xếp m + n – 1 dấu hiệu đã biết, có thể tái tạo lại một cách rõ ràng các dấu hiệu còn lại từ chúng. Nhưng có đúng là đây là số lượng ký tự nhỏ nhất được yêu cầu không? Vâng, đúng vậy, và đó chính xác là nội dung bài toán 15 của Cuộc thi A.P. Savin (xem «Kvant» số 1 cho năm 2017). Bài toán 6. Petya đã vẽ một bảng $10 \times 10$ và điền dấu cộng vào tất cả các ô của nó. Sau đó, anh ấy đã làm một số việc theo quy tắc sau. Với mỗi hành động, anh chọn ngẫu nhiên một hàng (hàng hoặc cột) và thay đổi từng dấu trong số 10 dấu hiệu của nó thành ngược lại (cộng thành trừ, trừ thành cộng). Khi Petya rời đi sau đó, kẻ bắt nạt Vasya đã xóa một số biển báo - chỉ còn lại N biển báo. Với N nhỏ nhất nào thì bảng kết quả của Petya có thể được xây dựng lại một cách duy nhất từ ​​dữ liệu còn lại? Hãy để chúng tôi trình bày lời giải trong trường hợp tổng quát hơn – cho bảng $m \times n$. Đáp số: m + n – 1 (tương ứng với bảng $10 \times 10$ đáp số: 19). Vì vậy, vẫn còn phải chứng minh rằng nếu biết ít hơn m + n – 1 ký tự thì phần điền không thể được khôi phục một cách duy nhất.

⟦column⟧

Xét một đồ thị trong đó các đỉnh tương ứng với các hàng (có tổng cộng m + n đỉnh) và hai đỉnh được nối với nhau bằng một cạnh khi và chỉ khi có dấu đã biết tại giao điểm của hai hàng này. Đồ thị này có m + n đỉnh và có số cạnh bằng số dấu đã biết, nghĩa là có ít hơn m + n – 1. Từ tỷ lệ này về số đỉnh và số cạnh, chúng ta có thể kết luận rằng đồ thị bị ngắt kết nối. Hãy xem xét một trong các thành phần được kết nối, gọi tất cả các đỉnh của nó (và tất cả các hàng tương ứng) là màu đỏ và tất cả các đỉnh khác (và các hàng của chúng) là màu xanh lam. Giả sử rằng bằng cách sử dụng các dấu hiệu đã biết, có thể khôi phục rõ ràng toàn bộ phần trám. Hãy xem xét nó. Hãy lần lượt đổi dấu ở từng hàng màu đỏ. Mỗi dấu hiệu đã biết đứng ở giao điểm của hai hàng màu xanh hoặc hai hàng màu đỏ, có nghĩa là với chuỗi hành động này, mỗi dấu hiệu đã biết sẽ không thay đổi chút nào hoặc sẽ thay đổi 2 lần, trong mọi trường hợp nó sẽ giữ nguyên. Đồng thời, việc lấp đầy không còn như cũ, vì mỗi biển báo đứng ở giao điểm của hàng đỏ và xanh đều thay đổi. Vì vậy, chúng tôi đã nhận được một thông tin điền khác trong đó các dấu hiệu đã biết hoàn toàn giống nhau. Điều này có nghĩa là chất trám không thể được khôi phục một cách rõ ràng bằng các dấu hiệu đã biết. Bài viết của P. Kozhevnikov và A. Shapovalov “Liên hệ với biểu đồ” ở «Kvant» Số 4 năm 2014 dành cho nhiều vấn đề khác nhau với ý tưởng này lời giải (xem xét một biểu đồ phụ và sử dụng tính kết nối hoặc ngắt kết nối của nó). Bây giờ chúng ta hãy xem xét bài toán M112 «Bài toán Kvant tương tự. Bài toán 7. Trong một bảng có kích thước $m \times n$ các số được viết sao cho với hai hàng và hai cột bất kỳ, tổng các số ở hai đỉnh đối diện của hình chữ nhật mà chúng tạo thành bằng tổng các số ở hai đỉnh còn lại của nó. Một số số đã bị xóa nhưng những số còn lại có thể được sử dụng để khôi phục các số đã bị xóa. Chứng minh rằng còn lại ít nhất (n + m – 1) số. Trong bài toán 6 chúng ta đang nói về việc điền có thể thực hiện được, có nghĩa là trong cả bốn ô giống nhau đứng ở giao điểm của 2 hàng và 2 cột, số dấu cộng là chẵn. Chúng tôi không nói về việc sơn lại ở đây.

⟦folio 45⟧

TOÁN HỌC

yakh hoặc về ưu và nhược điểm, nhưng một lần nữa một điều kiện được áp đặt cho cả bốn ô như vậy. Hãy thử giải quyết bài toán này theo cách tương tự. Hãy xem xét cùng một đồ thị bị ngắt kết nối. Một lần nữa, hãy gọi các đỉnh của một thành phần là màu đỏ và tất cả các thành phần còn lại là màu xanh. Trong bài toán trước chúng ta đã nói về việc chuyển đổi hàng, nhưng ở đây không có thao tác nào được đề cập trong điều kiện, nhưng bản thân chúng ta có thể giới thiệu một số thao tác phụ trợ với hàng. Chúng ta muốn gì từ những hoạt động này? Chúng ta muốn các số trong các ô tại giao điểm của các hàng đơn màu không thay đổi mà tại giao điểm của các hàng nhiều màu thay đổi. Hơn nữa, phép toán không vi phạm tính chất là đối với hai hàng và hai cột bất kỳ, tổng các số ở hai đỉnh đối diện của hình chữ nhật mà chúng tạo thành bằng tổng các số ở hai đỉnh còn lại của nó. Ví dụ: thao tác sau là phù hợp: đối với một cột, chúng ta tăng tất cả các số trong cột lên 1 và đối với một hàng, chúng ta giảm tất cả các số trong hàng đi 1. Dễ dàng kiểm tra xem thao tác này có thỏa mãn các yêu cầu cần thiết hay không. Do đó, sau khi thực hiện một thao tác như vậy với mỗi hàng màu đỏ, chúng ta thu được một bảng trong đó các dấu hiệu đã biết là giống nhau, nhưng một số dấu hiệu chưa biết đã thay đổi. Điều này có nghĩa là bảng không thể được xây dựng lại một cách duy nhất khi biết ít hơn n + m – 1 số. bài toán này nói về tính duy nhất của hệ phương trình tuyến tính lời giải. Một lời giải khác của bài toán này, chỉ sử dụng đại số tuyến tính, được đưa ra trong «Kvant» Số 8 cho năm 1972. Trên thực tế, bài toán trước đó cũng giống như bài toán, nhưng thay vì các phương trình tuyến tính thông thường - so sánh modulo 2. Cách tiếp cận này (xem xét bài toán về việc chuyển dấu theo quan điểm tuyến tính đại số) được dành cho bài viết của V. Dorofeev, A. Spivak “Màu đồ thị và phương trình tuyến tính” trong «Kvant» Số 4 cho năm 2011. Chúng tôi khuyên bạn nên nghiên cứu thêm về vấn đề này.

Bổ sung bài toán

1. 30 niken nằm với quốc huy hướng lên trên. Bạn được phép lật lại 29 cái bất kỳ cùng một lúc. Có thể đảm bảo rằng tất cả các đồng xu đều úp xuống không? 2 (Giải đấu các thành phố lần thứ IX, 1987). Một tam giác đều được chia bởi các đường thẳng song song

VÒNG TRÒN

các cạnh của nó thành các tam giác đều bằng nhau. Một trong những hình tam giác nhỏ có màu đen, phần còn lại có màu trắng. Được phép tô màu đồng thời tất cả các hình tam giác giao nhau bởi một đường thẳng song song với bất kỳ cạnh nào của tam giác ban đầu. Có phải luôn luôn có thể, với sự trợ giúp của một số cách đổi màu như vậy, để đảm bảo rằng tất cả các hình tam giác nhỏ đều có màu trắng? 3 (E. Bakaev, Giải đấu giao đấu tưởng nhớ A.P. Savin, 2015). Cho một hình vuông ca rô: a) $5 \times 5$; b) $8 \times 8$. Với một thao tác, bạn có thể chọn bất kỳ hình vuông $3 \times 3$ hoặc bất kỳ hàng hoặc cột bất kỳ và thay đổi màu của tất cả các ô trong khu vực này thành các ô đối diện. Với sự trợ giúp của các thao tác như vậy, từ một hình vuông hoàn toàn màu trắng, chúng ta thu được một hình vuông chứa đúng một ô màu đen. Tế bào này có thể kết thúc ở đâu? Vui lòng cho biết tất cả các lựa chọn. 4. Có bao nhiêu cách tô màu các ô của bảng $10 \times 10$ thành đen trắng sao cho mỗi ô vuông $3 \times 3$ đều có số ô đen chẵn? 5 (A. Zelevinsky, Olympic Moscow, 1970, M32). Tất cả các ô của bảng có kích thước $100 \times 100$ đều chứa dấu cộng. Cho phép đổi dấu đồng thời ở tất cả các ô của một hàng hoặc tất cả các ô của một cột. Liệu sau khi thực hiện các thao tác như vậy nhiều lần, có thể thu được một bảng có chính xác 1970 điểm trừ không? 6 (V. Alekseev, Olympic Moscow, 2007). Trong bảng gồm $n \times n$ ô, hai ô ở góc đối diện có màu đen và các ô còn lại có màu trắng. Số lượng ô trắng nhỏ nhất cần được sơn lại thành màu đen là bao nhiêu để sau đó, bằng cách sử dụng các phép biến đổi bao gồm sơn lại tất cả các ô của cột hoặc hàng bất kỳ bằng màu đối diện, có thể làm cho tất cả các ô của bảng thành màu đen? 7 (A. Bystrikov, Giải đấu các thành phố XXV, 2003). Bảng $m \times n$ liệt kê những ưu và nhược điểm. Trong một nước đi, bạn được phép đổi dấu thành dấu đối diện ở bất kỳ hàng, cột nào hoặc trên bất kỳ đường chéo nào (các ô góc cũng được coi là đường chéo). Chứng minh rằng nếu bảng không bị rút gọn bằng những thao tác như vậy thành bảng chỉ có điểm cộng thì bảng đó chứa hình vuông $4 \times 4$ cũng không bị rút gọn.
