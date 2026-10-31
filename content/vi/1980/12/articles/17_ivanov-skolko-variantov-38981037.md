---
id: 1980-12-ivanov-skolko-variantov-38981037
issue: kvant_1980_12
year: 1980
number: "12"
title: Có bao nhiêu lựa chọn?
authors:
  - Иванов Ю.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 38
page_last: 41
page_labels: 36-39
tag: 88V1
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 15c9eab71382902206938b13468f6e79155cb93cca7eaed7026e3ebebddffc12
prompt_sha256: draft-1
translated_from: content/ru/1980/12/articles/17_ivanov-skolko-variantov-38981037.md
source_content_sha256: c25268fb11eda21df7542a0ae2972c47cada38bd26e1b937a67c3abdaae90dc0
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 36⟧

Có bao nhiêu lựa chọn?

Sau đây chúng ta tiếp tục nghiên cứu tổ hợp bài toán theo chương trình tự chọn lớp IX đã bắt đầu ở số trước.

Trong tất cả bài toán được thảo luận ở bài viết trước (và các bài tập được cung cấp cho bạn cho lời giải), để có được đáp số chỉ cần một hành động tranh luận - phép nhân. Hãy để chúng tôi chỉ ra trong trường hợp nào các đối số hành động khác được sử dụng để đếm số lượng tùy chọn.

Phép trừ và phép cộng

Bài toán 1. Có bao nhiêu số có bốn chữ số có ký hiệu thập phân giống nhau?

Lời giải. Các thao tác thực hiện theo sơ đồ tương tự như bài viết trước, chia việc xây dựng số có bốn chữ số thành bốn bước: chọn chữ số thứ nhất, thứ hai, thứ ba, thứ tư. Ở bước đầu tiên chúng ta có 9 khả năng, ở bước thứ hai và thứ ba chúng ta có 10 khả năng. Nhưng số phương án thực hiện bước bốn chữ số phụ thuộc vào kết quả của ba bước đầu tiên: nếu trung bình của ba chữ số bằng nhau thì ở bước thứ tư chúng ta có 10 khả năng, nhưng nếu ba chữ số đầu tiên khác nhau thì chúng ta phải lấy một trong các chữ số này làm chữ số có bốn chữ số và do đó, chúng ta sẽ chỉ có ba khả năng ở bước này.

Vì vậy, sản phẩm chính xác không được áp dụng. Sắp xếp lại các bước cũng không giúp ích được gì: chúng ta vẫn sẽ gặp khó khăn tương tự. Tuy nhiên, chúng ta hãy nhớ rằng ở phần đầu của thống kê trước, chúng ta đã giải bài toán, ngược lại với số được phân chia - chúng ta đã tìm thấy số các số có bốn chữ số trong đó không có chữ số nào giống hệt nhau. Trừ số này (bằng 9·9·8·7=4536) cho số của tất cả các số có bốn chữ số (nó bằng 9·10·10·10=9000), chúng ta thu được số có bốn chữ số thỏa mãn điều kiện bài toán bằng 9000—4536=4464.

Bài tập

1. Có bao nhiêu số có sáu chữ số trong đó có ít nhất một chữ số là số chẵn?
2. Có bao nhiêu hoán vị của các chữ số 0, 1, 2,..., 9 trong đó ít nhất một trong 3 chữ số đầu chia hết cho 3?
3. Bài toán 2. Có bao nhiêu số tự nhiên nhỏ hơn 10^5 có ký hiệu thập phân chứa các chữ số giống nhau?

Lời giải. Nếu bạn chia việc xây dựng một số như vậy thành các bước, tại mỗi bước được chọn một chữ số, thì đối với các số khác nhau, số bước sẽ khác nhau. Đồng thời, sử dụng quy tắc tích, không khó để tìm riêng các số có một chữ số, hai chữ số, ba chữ số, bốn chữ số và năm chữ số thỏa mãn điều kiện bài toán: 9, 9^2, 9^3, 9^4, 9^5. Điều này có nghĩa là tổng cộng có 9+9^2+9^3+9^4+9^5=66429 số tự nhiên nhỏ hơn 10^5, với các chữ số lân cận khác nhau.

Bài tập

3. Bảng chữ cái bao gồm 10 chữ cái. Chúng ta hãy định nghĩa một số nguyên là bất kỳ chuỗi chữ cái nào trong bảng chữ cái này trong đó không có chữ cái nào xuất hiện trong cùng một chuỗi. Có bao nhiêu số nguyên không quá 4 chữ cái?
4. Có bao nhiêu số có sáu chữ số chấp nhận được các chữ số chẵn và lẻ?
Ở bài toán 2 và bài tập 3, 4 không thể bôi trực tiếp đúng sản phẩm được. Trong mỗi bài toán này bạn có thể 逐个

⟦folio 37⟧

Hình 1.
Các mục đang được đọc có thể được chia thành nhiều phần theo cách có thể áp dụng quy tắc tích để đếm số phần tử trong mỗi phần này. Cộng các số kết quả, chúng ta tìm thấy lời giải trong số này bài toán.

Bài toán 3. Có bao nhiêu hoán vị của các số 0, 1, 2,..., 9, trong đó số 0 chiếm một trong sáu vị trí đầu tiên và số 1 chiếm một trong sáu vị trí cuối cùng (Hình 1)?

Lời giải. Nếu trước tiên chúng ta chọn một vị trí cho số 0, sau đó là một vị trí cho các đơn vị và sau đó chúng ta đặt tám chữ số còn lại vào tám vị trí còn lại, thì ở bước thứ hai, số khả năng sẽ phụ thuộc vào lời giải, được áp dụng ở bước đầu tiên; cụ thể là, nếu ở bước đầu tiên chúng ta đặt số 0 vào một trong bốn vị trí đầu tiên, thì chúng ta có thể chọn vị trí cho các số đó theo sáu cách; nếu số 0 đứng ở vị trí thứ năm hoặc thứ sáu thì chỉ có năm vị trí dành cho số 1. Do đó, ngay từ đầu, chúng ta hãy chia tập hợp tất cả các hoán vị thỏa mãn điều kiện bài toán thành hai tập con: các hoán vị trong đó chữ số 0 chiếm một trong bốn vị trí đầu tiên và các hoán vị trong đó chữ số này chiếm vị trí thứ năm hoặc thứ sáu. Số phần tử trong mỗi tập hợp con này có thể được tính toán dễ dàng bằng cách sử dụng quy tắc tích: $4 \cdot 6 \cdot 8! = 24 \cdot 8!$ và $2 \cdot 5 \cdot 8!$. Đáp số: $24 \cdot 8! + 10 \cdot 8! = 34 \cdot 8!$.

Bài tập

5. Có bao nhiêu bốn chữ số 0, 1, 2,..., 9 thỏa mãn điều kiện bài toán?

6. Có bao nhiêu hoán vị của các chữ số 0, 1, 2,..., 9 thỏa mãn điều kiện bài toán?

6) giữa số 0 và số 1 có ba số khác, giữa số 1 và số 2 có hai số khác?

7. Có bao nhiêu hàm số f thỏa mãn các điều kiện sau: miền định nghĩa của hàm f là tập [1, 2, 3, 4, 5], mỗi giá trị của hàm f thuộc tập [1, 2, 3, 4], số f(5) chia hết cho f(3) không có số dư?

Phân công

Hành động đối số thứ tư cũng hữu ích cho các tổ hợp lời giải bài toán.

Bài toán 4. Có bao nhiêu cách xếp 12 người ngồi vào một bàn tròn nếu bàn có 12 ghế?

Lời giải. Số cách sắp xếp khác nhau của 12 người ở 12 vị trí, tức là số hoán vị của những cây người này là 12!, bất kể những chiếc ghế này được đặt ở đâu - trên bàn, dựa vào tường, hay một nơi nào khác. Vậy thì tại sao trong bài toán lại bỏ qua việc những chiếc ghế ở bàn tròn? Trong bài toán 4 - không mất gì. Nhưng bàn tròn cho phép bạn đưa ra những “biến thể” tự nhiên bài toán.

A. Nếu đối với mỗi người, việc mình chiếm vị trí nào trên bàn không quan trọng mà chỉ quan trọng ai là người hàng xóm bên phải và ai là người hàng xóm bên phải, thì hai sự sắp xếp nên được hoãn lại nếu, khi chuyển từ cách sắp xếp này sang cách sắp xếp khác, cả người hàng xóm và người hàng xóm đều không thay đổi đối với mỗi người ngồi cùng bàn.

B. Nếu đối với mỗi người, điều duy nhất quan trọng là người hàng xóm của anh ta là ai (và không quan trọng người hàng xóm nào ngồi bên phải và người nào ngồi bên trái), thì hai sự sắp xếp sẽ được hoãn lại nếu mỗi người ngồi cùng bàn đều có những người hàng xóm giống nhau trong cả hai trường hợp.

B. Nếu điều duy nhất quan trọng đối với mỗi người là ai ngồi trong nhóm mới, thì hai cách sắp xếp này sẽ được đặt sang một bên nếu bất kỳ hai người nào chiếm các ghế đối diện theo đường kính trong một cách sắp xếp cũng chiếm các ghế đối diện theo đường kính trong một cách sắp xếp khác.

Hãy chuyển sang lựa chọn A. Hãy phá vỡ tất cả 12! các địa điểm thành các nhóm, gán cho một nhóm những địa điểm và chỉ những địa điểm cần được đặt sang một bên. Số lượng dữ liệu nhận được

⟦folio 38⟧

Do đó các nhóm là đáp số bài toán. Để tìm thấy nó, trước tiên chúng ta tìm hiểu xem có bao nhiêu địa điểm trong một nhóm. Hãy chọn một nhóm tùy ý và xem xét các vị trí thuộc nhóm đó. Mỗi người ở tất cả các địa điểm này đều có một người hàng xóm cố định ở bên phải và một người hàng xóm cố định ở bên trái. Do đó, để xây dựng một sự sắp xếp tùy ý từ một nhóm nhất định, chỉ cần chỉ ra người sẽ ngồi ghế số 1 (trong cả hai phương án này bài toán, và trong phương án B và C, chúng ta sẽ giả sử rằng những chiếc ghế được bao quanh bởi các số từ 1 đến 12), sau đó vị trí của những người còn lại được xác định rõ ràng. Vì bất kỳ ai trong số 12 người đều có thể ngồi ở ghế số 1 nên mỗi nhóm gồm có 12 địa điểm. Bây giờ để tìm số nhóm, tất cả những gì còn lại là chia tổng số vị trí cho số vị trí trong một nhóm: $\frac{12!}{12} = 11!$

Bây giờ chúng ta hãy xem lựa chọn B. Và ở đây chúng ta sẽ chia nhỏ tất cả 12 lựa chọn! sắp xếp thành các nhóm sao cho hai cách sắp xếp rơi vào cùng một nhóm khi và chỉ nếu chúng cần được xác định. Hãy chọn một nhóm và đếm xem có bao nhiêu địa điểm trong đó. Vì mỗi người trong những sự sắp xếp này có một người hàng xóm cố định, nên một sự sắp xếp tùy ý từ nhóm này có thể được xây dựng theo hai bước: đầu tiên, chúng ta chọn người sẽ chiếm chiếc ghế số 1 (12 khả năng), sau đó chúng ta quyết định ai trong số hai người hàng xóm của anh ta sẽ chiếm vị trí số 2 (2 khả năng), sau đó vị trí của mười người còn lại được xác định “trong một” một cách rõ ràng. Theo quy tắc sản phẩm, mỗi nhóm bao gồm 24 cách sắp xếp và do đó số lượng nhóm là $\frac{12!}{24} = \frac{11!}{2}$.

Và cuối cùng, trong tùy chọn B, cũng như trong các tùy chọn trước đó, hàng xóm, có bao nhiêu vị trí trong một nhóm của tùy chọn này. Cho $A$ ngồi ở tất cả các vị trí trong nhóm này để chỉ đạo $A'$, $B$ chỉ đạo $B'$, $C$ chỉ đạo $C'$, $D$ chỉ đạo $D'$, $E$ chỉ đạo $E'$ và cuối cùng là $F$ - bằng cách gửi $F'$. Sáu cặp người này cần ngồi trên sáu cặp ghế: (1, 7), (2, 8), (3, 9), (4, 10), (5, 11) và (6, 12) - mỗi cặp người một cặp ghế. Do đó, việc xây dựng một sự sắp xếp tùy ý từ nhóm này có thể được chia thành bảy bước: đầu tiên, sắp xếp 6 cặp vị trí giữa sáu cặp người (6! Khả năng), ở bước thứ hai, đặt $A$ và $A'$ ở hai vị trí riêng biệt cho họ, ở bước thứ ba, đặt $B$ và $B'$ ở những vị trí riêng biệt cho họ, v.v., ở bước tiếp theo - đặt các vị trí ở giữa $F$ và $F'$. Vì ở mỗi bước trong số sáu bước cuối cùng, chúng ta có hai khả năng, do quy tắc tích số, sẽ có sự sắp xếp $6! \cdot 2^6$ trong nhóm này (như trong bất kỳ bước nào khác). Số lượng nhóm yêu cầu là bằng nhau, do đó, được định vị, do đó, được định vị,

$$\frac{12!}{6! \cdot 2^6} = 3 \cdot 5 \cdot 7 \cdot 9 \cdot 11 = 10395.$$

Bài toán 5. Một số cạnh [AB], [BC], [CD], [DA] và đường chéo [AC] của hình vuông ABCD phải được sơn bằng một trong năm màu đã cho và phải sử dụng tất cả các màu. Hai màu được coi là giống nhau nếu một trong những màu còn lại có thể thu được bằng chuyển động không phanh. Có bao nhiêu trang tô màu khác nhau?

Lời giải. Nếu bạn không chú ý đến chuyển động thì hãy quyết định phân bổ năm màu trên năm đoạn. Có 5 cách phân phối như vậy, rất tiện lợi! Điều kiện bài toán phá vỡ 5 điều này! phân phối thành các nhóm, mỗi nhóm bao gồm tất cả các cách sắp xếp màu sắc, màu sắc nhất định, màu sắc trung tính. Số lượng các nhóm này đóng vai trò là đáp số bài toán. Chúng ta sẽ tìm thấy, như trước đây,

**Hình 2.**

⟦folio 39⟧

de, số phần tử trong một nhóm. Con số này rõ ràng bằng với số lượng các biến khác nhau chuyển hình được hiển thị trong Hình 2 thành chính nó. Vì với mỗi chuyển động như vậy, đường chéo $[AC]$ phải biến thành chính nó nên các đỉnh $A$ và $C$ vẫn giữ nguyên vị trí hoặc được đặt ở các vị trí. Do đó, đối với các đỉnh $B$ và $D$, cũng có hai khả năng còn lại: giữ nguyên vị trí hoặc được đặt vào các vị trí. Bằng cách kết hợp từng tùy chọn trong số hai tùy chọn để di chuyển đỉnh $A$ và $C$ với mỗi tùy chọn trong số hai tùy chọn để di chuyển đỉnh $B$ và $D$, chúng ta có được bốn chuyển động khác nhau: giống hệt nhau ($A$ và $C$ giữ nguyên, $B$ và $D$ giữ nguyên), đối xứng so với đường thẳng $BD$ ($A$ và $C$ được đặt ở các vị trí, còn $B$ và $D$ vẫn được giữ nguyên), tính đối xứng so với đường thẳng $AC$ ($A$ và $C$ vẫn giữ nguyên, $B$ và $D$ được đặt ở các vị trí) và thành phần của hai đối xứng này - sự đối xứng so với tâm hình vuông (trong trường hợp này, cả $A$ với $C$ và $B$ với $D$ đều được di chuyển ở các vị trí). Như vậy, mỗi nhóm bao gồm bốn phần tử và đáp số bài toán là số $\frac{5!}{4} = 30$.

Bài tập

8. Có thể xây dựng bao nhiêu hình không tắc nghẽn theo cặp từ một hình tròn $n$-giác đều và $n$ có bán kính từng cặp khác nhau, nếu mỗi cạnh của $n$-giác phải chạm vào tâm của nó một và chỉ một trong số các hình tròn đã cho?

9. Đối với một bữa tiệc dành cho 100 người, chín bàn tròn đã được chuẩn bị: ba bàn tám chỗ, bốn bàn mười chỗ và hai bàn mười tám chỗ. Hai phương án sắp xếp người vào bàn được coi là giống nhau nếu mỗi người trong cả hai phương án đều có cùng một người hàng xóm và cùng một người hàng xóm. Có bao nhiêu cách khác nhau để sắp xếp các bảng này?

Bài toán 6. Có bao nhiêu số có sáu chữ số trong đó số 1 và 2 xuất hiện hai lần, số 3 và 4 - không xuất hiện một lần?

Lời giải. Một số có sáu chữ số với tất cả các chữ số đã cho về cơ bản là một hoán vị của sáu chữ số đó. Nhưng chúng ta biết công thức tính số hoán vị của các đối tượng x khác nhau và các thành viên của x, trong khi trong số các chữ số của các số có sáu chữ số đang được xem xét có những số giống hệt nhau. Để vẫn sử dụng công thức tính số hoán vị, chúng ta giả sử rằng chúng ta có hai số hoán vị khác nhau: 1 và 1 và hai số hai khác nhau: 2 và 2, do đó số rebit là khoảng 6! hoán vị của số có sáu chữ số không bằng số hoán vị đó, vì một số hoán vị, ví dụ 3 1 2 1 4 2 và 3 1 2 1 4 2, dẫn đến cùng một số. Hai hoán vị sẽ xác định cùng một số có sáu chữ số nếu lấy được một trong số còn lại, chỉ có tôi ở vị trí 1 và 1 hoặc 2 và 2. Chúng ta đến với dấu hiệu ký hiệu: tất cả 6! hoán vị được chia thành các nhóm, số trong đó là số độc quyền của các số có sáu chữ số. Vì có bốn hoán vị trong mỗi nhóm nên đáp số: $\frac{6!}{4} = 30$.

Bài tập

10. Bạn có thể có được bao nhiêu từ có bảy chữ cái khác nhau bằng cách sắp xếp lại các chữ cái của từ "chuông"? (Trong toán học, một từ là một chuỗi hữu hạn các chữ cái của một bảng chữ cái nào đó.)

11. Có bao nhiêu từ có 7 chữ cái chia hết cho 25 mà không chứa các số 0 và 2?

12. Có bao nhiêu số có 5 chữ số chia hết cho 25 mà không chứa các chữ số 0 và 2?

13. Một số bảng chữ cái có 5 chữ cái. Có bao nhiêu từ có sáu chữ cái trong bảng chữ cái này, mỗi từ chỉ chứa hai chữ cái khác nhau, một trong số chúng có năm lần?

14. Có bao nhiêu hoán vị của các số 0, 1, 2,..., 9 trong đó các số 0, 1, 2; 3 liên tiếp

a) theo thứ tự tăng dần;
b) không theo thứ tự cụ thể nào?

15. Có thể lập được bao nhiêu số có 4 chữ số chia hết cho 9 từ các chữ số 0, 1, 2, 3, 4, 5, 6 với điều kiện là

a) mỗi số chứa mỗi chữ số không quá một lần;
b) trong mỗi số, mỗi chữ số xuất hiện không quá một lần;

16. Có bao nhiêu hoán vị của các chữ số 0, 1, 2,..., 9 trong đó chữ số 0 chiếm một trong những vị trí đầu tiên, chữ số 1 là một trong những vị trí đầu tiên và hai chữ số còn lại nằm giữa các chữ số 0 và 1?

17. Có thể tạo ra bao nhiêu từ có $(m+n)$ chữ cái từ $m$ chữ cái $A$ và $n$ chữ cái $B$?
