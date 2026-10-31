---
id: 1980-11-ivanov-skolko-variantov-d3e8e034
issue: kvant_1980_11
year: 1980
number: "11"
title: Có bao nhiêu lựa chọn?
authors:
  - Иванов Ю.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 36
page_last: 38
page_labels: 34-36
tag: JOKO
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 1a12122b36f241d517d357a44a1dcfab64f6d368a42a7c5440ecbf6cd15ac202
prompt_sha256: draft-1
translated_from: content/ru/1980/11/articles/11_ivanov-skolko-variantov-d3e8e034.md
source_content_sha256: e7b11c06856972291653ad31aa9dc0b936bcea22f3d81b0dbf926ebd0ce41a2f
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 34⟧

xsem, tương tự như trong Hình 1. Trong trường hợp này, không cần thiết phải vẽ sơ đồ - chỉ cần tưởng tượng là đủ, đặc biệt vì với số lượng lớn các tùy chọn thì không thể vẽ sơ đồ.

Bây giờ chúng ta hãy phân tích một số bài toán.

Bài toán 1. Có bao nhiêu số có bốn chữ số mà ký hiệu thập phân của tất cả các chữ số đều khác nhau?

Lời giải. Việc xây dựng mỗi số có bốn chữ số thỏa mãn điều kiện bài toán có thể được chia thành bốn bước. Ở bước đầu tiên, chữ số đầu tiên của số được chọn. Sự lựa chọn này có thể được thực hiện theo chín cách (chữ số 0 không thể là chữ số đầu tiên của số), sao cho dòng đầu tiên của sơ đồ tưởng tượng có 9 chữ số. Ở bước thứ hai, chữ số thứ hai của số được chọn. Mặc dù việc chọn chữ số thứ hai phụ thuộc vào việc chọn chữ số thứ nhất (chữ số thứ hai phải khác chữ số thứ nhất), nhưng số khả năng chọn chữ số thứ hai, bất kể số được chọn ở ngôi nhà thứ nhất, là 9. Do đó, từ mỗi chữ số của dòng đầu tiên của sơ đồ tưởng tượng, 9 mũi tên sẽ đi ra dòng thứ hai, do đó sẽ có 9 9 chữ số. Ở căn nhà gỗ thứ ba, chọn số thứ ba; vì nó phải khác với số đã chọn trong hai bước đầu tiên, bất kể lời giải mà chúng tôi đã chấp nhận trong hai bước đầu tiên, trong căn nhà gỗ thứ ba, chúng tôi được lựa chọn các khả năng. Do đó, dòng thứ ba của sơ đồ sẽ có 9·9·8 chữ số. Ở ngôi nhà thứ tư, chúng ta có thể chọn bất kỳ chữ số nào trong bảy chữ số không được sử dụng trong ba bước đầu tiên, và do đó số chữ số ở dòng dưới cùng là 9 9 8 7 = 4536. Vì số chữ số ở dòng dưới cùng hiển nhiên bằng số đường đi từ dòng trên xuống dòng dưới cùng nên 4536 là số cần tìm.

Bài tập 1. Có bao nhiêu số có bốn chữ số mà ký hiệu thập phân của tất cả các chữ số đều khác nhau?

Bài toán 2. Số 2³·3¹⁰·7¹⁵·11⁹ có bao nhiêu ước số tự nhiên khác nhau?

Lời giải. Rõ ràng mỗi ước số của một số như vậy đều có dạng

2ⁿ·3¹ⁿ·7ⁿ·11ⁿ, trong đó 0<k<7, 0<l<10, 0<m<15, 0<n<9. Do đó, việc lựa chọn mỗi ước số có thể được chia thành bốn bước: chọn k, chọn l, chọn m, chọn n. Vì chúng ta có thể thực hiện bước đầu tiên theo tám cách, nên ở ngôi nhà gỗ thứ hai, bất kể hai bước đầu tiên, có 16 khả năng và cuối cùng, bất kể ba bước đầu tiên, chúng ta có thể thực hiện bước thứ tư theo mười cách, tính toán theo cách tương tự như trong các bài toán trước, chúng ta sẽ đạt được đáp số 8 11 16 10 = 14080.

Lập luận tương tự dẫn đến công thức tổng quát cho số chia τ(n) của số tự nhiên n, nếu biết phân tích n thành thừa số nguyên tố. Cụ thể, nếu n=p₁^k₁·p₂^k₂·…·p₅^k₅, trong đó p₁, p₂, …, p₅ là các số nguyên tố riêng biệt, k₁, k₂, …, k₅ là các số tự nhiên, thì

τ(n)=(k₁+1)(k₂+1)…·(k₅+1).

Bài tập 2. Số 20 có bao nhiêu ước số tự nhiên khác nhau!=1·2·3·…·20?

Quy tắc sản phẩm

Trong tất cả bài toán được phân tích, việc tính toán số lượng đối tượng có liên quan với nhau (số Varinian, số có bốn chữ số có chữ số không lặp lại, ước số của một số đã cho) được thực hiện theo cùng một sơ đồ: chúng tôi tưởng tượng việc xây dựng bất kỳ đối tượng nào được liệt kê dưới dạng một chuỗi gồm nhiều bước, tại mỗi bước, số lượng lựa chọn có thể có được dễ dàng tìm thấy và không phụ thuộc vào lời giải được thực hiện ở các bước trước. Tích của những số này cho kết quả đáp số bài toán. Các sơ đồ lời giải này thường được gọi là “quy tắc sản phẩm”:

Giả sử chúng ta cần đếm số lượng vật phẩm thỏa mãn các điều kiện nhất định. Giả sử rằng việc xây dựng một vật thể tùy ý như vậy cần thực hiện một số bước liên tiếp và tại ngôi nhà gỗ đầu tiên, chúng ta có một lựa chọn từ a₁ có thể.

⟦folio 35⟧

ste; bất kể kết quả của bước đầu tiên là gì, chúng tôi có $a_2$ khả năng khác nhau ở căn nhà gỗ thứ hai; Bất kể kết quả của hai bước đầu tiên như thế nào, vẫn có $a_3$ cách để thực hiện bước thứ ba, v.v.; cuối cùng, bất kể lời giải được thực hiện ở các bước trước, chúng ta có $a_n$ khả năng để thực hiện bước cuối cùng. Khi đó tổng số mặt hàng liệt kê bằng sản phẩm $a_1 \cdot a_2 \cdot \dots \cdot a_n$.

Pravanne có 3. Trong số automatizite, có ba chữ cái trong bảng chữ cái tiếng Nga (chứa 33 chữ cái) ở đầu, sau đó là bốn số. Bạn có thể tạo bao nhiêu số tự động hóa khác nhau?

Pravanne có 4. Đàn piano có 88 phím. Có bao nhiêu cách tạo ra 6 âm liên tiếp?

Bây giờ chúng ta hãy phân tích bài toán khó khăn hơn một chút.

Bài toán 3. Có bao nhiêu số có bốn chữ số, được tạo thành từ các chữ số 1, 3, 4, 6, 7, trong đó các chữ số liền kề khác nhau?

Lời giải. Nếu ở nhà gỗ thứ nhất, chúng ta chọn chữ số đầu tiên của một số như vậy, ở nhà gỗ thứ hai - chữ số thứ hai, v.v., thì ở nhà gỗ thứ nhất, chúng ta có 5 khả năng, ở bước thứ hai và thứ ba có 4 khả năng cho mỗi số (ở mỗi bước này, chúng ta có thể chọn bất kỳ số nào ngoại trừ số đã chọn ở nhà gỗ trước đó). Tuy nhiên, khi thực hiện bước thứ tư, số khả năng phụ thuộc vào kết quả của bước trước: vì chữ số cuối cùng phải chẵn và khác chữ số áp chót, nên chúng ta có hai khả năng ở ô cuối cùng nếu một trong các số 1, 3, 7 được chọn ở ô thứ ba và một khả năng nếu chúng ta chọn 4 hoặc 6 làm chữ số thứ ba.

Hóa ra quy tắc tích số không áp dụng cho lời giải cho bài toán? Kết luận này trước đây đã được thực hiện quá mức. Quy tắc tích số không thể áp dụng do trình tự các bước chúng tôi đã chọn để xây dựng một số có bốn chữ số với các thuộc tính được yêu cầu không thành công. Nếu chúng ta chọn số thứ tư ở nhà gỗ đầu tiên, sau đó là số thứ ba, thứ hai và thứ ba, thì chúng ta sẽ có 2 khả năng ở nhà gỗ đầu tiên và 4 khả năng ở mỗi bước tiếp theo. Theo quy tắc sản phẩm, số số có bốn chữ số cần thiết là $2 \cdot 4^3 = 128$.

Nghệ thuật của các tổ hợp lời giải bài toán (đây là tên được đặt cho các giao lộ bài toán mà chúng ta đang xem xét) phần lớn nằm ở khả năng chọn trình tự các bước dẫn đến việc xây dựng các đối tượng giao nhau. Theo quy định, trình tự này được chọn sao cho trong các bước đầu tiên, nó đáp ứng số lượng hạn chế tối đa được áp đặt bởi các điều kiện bài toán đến 0.

Pravanne có 5. Có bao nhiêu số có năm chữ số $n$ thỏa mãn điều kiện:

a) $n$ kết thúc bằng hai số bảy;
b) $n$ bắt đầu bằng hai chữ số giống nhau;
b) tất cả các chữ số của số $n$ đều khác nhau, với chữ số thứ hai và thứ tư là số lẻ;
d) $n$ chia hết cho 4, các chữ số lân cận của nó có khác biệt và khác 0, 4, 8 không?

Pravanne có 6*. Tất cả các loại đường đứt nét được vẽ trên mặt phẳng tọa độ, tất cả các đỉnh của chúng đều có tọa độ nguyên và các liên kết song song với đường tọa độ và không đi qua cùng một đỉnh hai lần; $L_n$ là số đoạn nét đứt kéo dài từ gốc và có độ dài $n$. Chứng minh rằng $4 \cdot 2^n \leq L_n \leq 4 \cdot 3^n$.

Sắp xếp lại

Hãy bắt đầu với điều này bài toán.

Bài toán 4. Có bao nhiêu cách viết tên 30 học sinh vào một cột?

Lời giải. Ở đây, trình tự các bước được thực hiện: đầu tiên chúng tôi chọn một học sinh cho vị trí đầu tiên, sau đó là một học sinh cho vị trí thứ hai, v.v. Ở ngôi nhà thứ nhất, chúng tôi có 30 khả năng, ở ngôi nhà thứ hai - 29 khả năng, ở ngôi nhà thứ ba - 28 khả năng, v.v., cuối cùng, ở ngôi nhà cuối cùng, thứ ba mươi, chúng tôi còn lại 1 khả năng: ghi lại một học sinh có họ không được viết ở bất kỳ bước nào trong số 29 bước trước đó. Đáp số bài toán do đó là số $30! = 30 \cdot 29 \cdot 28 \cdot \dots \cdot 3 \cdot 2 \cdot 1$.

Chúng tôi đã đưa bài toán này vào đây chỉ vì nó là một phần của bài toán quan trọng tiếp theo.

⟦folio 36⟧

Nhiệm vụ 5 (số hoán vị của phần tử $n$). Có bao nhiêu cách có thể sắp xếp một tập hợp đã cho gồm $n$ phần tử?

Sắp xếp một tập hợp có nghĩa là sắp xếp các phần tử của nó theo một thứ tự nào đó. Mỗi sự sắp xếp như vậy được gọi là một hoán vị của tập dữ liệu. Do đó, bài toán có thể được phát biểu như sau: có bao nhiêu hoán vị của tập hợp các phần tử $n$? Lập luận tương tự như trong danh sách bài toán học sinh (danh sách đó là một hoán vị của tập hợp học sinh), ta thấy rằng số hoán vị của tập hợp phần tử $n$ là $n! = 1 \cdot 2 \cdot 3 \cdot \dots \cdot n$.

Bài tập 7. Có bao nhiêu hoán vị của các số 0, 1, 2, ..., 9 trong đó số 0 đứng ở vị trí thứ ba, số 4 ở vị trí thứ năm, số 7 ở vị trí thứ bảy?

Bài tập 8. Có bao nhiêu cách xếp 8 quân xe giống hệt nhau lên bàn cờ sao cho không có hai quân nào đứng cạnh nhau?

Bài tập 9. Có bao nhiêu hoán vị của các số 0, 1, 2, ..., 9 trong đó số 6 liền kề với số 9?

Bây giờ chúng ta hãy phân tích hai bài toán, cho lời giải mà cả công thức tính số hoán vị và quy tắc tích đều được sử dụng.

Bài 6. Có bao nhiêu hoán vị của các số 0, 1, 2, ..., 9 trong đó số 0 chiếm một trong bốn vị trí đầu tiên, số 9 chiếm một trong ba vị trí cuối cùng?

Lời giải. Chúng ta sẽ chia việc xây dựng một hoán vị tùy ý như vậy thành ba bước: chọn vị trí cho số 0 (bước đầu tiên), chọn vị trí cho số 9 (bước thứ hai), đặt tám chữ số còn lại vào tám vị trí còn lại (bước thứ ba). Ở bước đầu tiên chúng ta có 4 khả năng; dù chọn phương án nào thì chúng ta cũng có 3 khả năng ở bước thứ hai và cuối cùng, dù sắp xếp các số 0 và 9 như thế nào thì chúng ta cũng sẽ có 8! khả năng đặt tám chữ số còn lại vào tám vị trí. Theo quy tắc tích, số $4 \cdot 3 \cdot 8! = 12 \cdot 8!$ là nghiệm của bài toán.

Như bạn có thể thấy, ở bước thứ ba, chúng ta đã sử dụng bài toán đã giải trước đó về số hoán vị của tám đối tượng. Với lời giải tổ hợp bài toán để liệt kê các tùy chọn, bạn có thể sử dụng hiệu quả kinh nghiệm tích lũy: bất kỳ bài toán nào được giải quyết đều có thể trợ giúp tại một trong các bước trong bài toán phức tạp hơn.

Bài tập 7. Có bao nhiêu cách xếp 15 bạn nam và 15 bạn nữ ngồi thành 15 cặp sao cho mỗi cặp có một bạn nam và một bạn nữ ở bên phải?

Lời giải. Chúng ta sẽ chia việc xây dựng cách sắp xếp chỗ ngồi tùy ý thành hai bước: chúng ta sẽ xếp chỗ cho 15 bé trai ở mười lăm chỗ, và sau đó chúng ta sẽ xếp chỗ cho 15 bé gái ở mười lăm chỗ. Ở mỗi bước, chúng tôi quyết định bài toán về việc sắp xếp lại bộ sưu tập thứ mười lăm của bộ sưu tập cô đọng sao cho các tập của mỗi bộ sưu tập cô đọng xếp thành một hàng, mặc dù không nhất thiết phải theo thứ tự các tập?

Bài tập 10. Có bao nhiêu cách sắp xếp bốn tuyển tập gồm mười tập trên một giá sao cho các tập của mỗi tuyển tập nằm thành một hàng, mặc dù không nhất thiết phải theo thứ tự các tập?

Bài tập 11. Có bao nhiêu hoán vị của các số 0, 1, 2, ..., 9 trong đó có 3 số khác nằm giữa các số 2 và 3?

Số tập con của một tập hợp hữu hạn

Con số được đưa ra trong phụ đề thường được tìm thấy trong các vấn đề. Hãy cố gắng tìm nó trong những trường hợp đặc biệt.

Hãy viết ra tất cả các tập hợp con của mỗi bộ:

$A = \{a_1; a_2\}, B = \{a_1; a_2; a_3\},$
$C = \{a_1; a_2; a_3; a_4\}$.

Các tập con của tập hợp $A$:
$\emptyset, \{a_1\}, \{a_2\}, \{a_1; a_2\}$.

Các tập con của tập hợp $B$:
$\emptyset, \{a_1\}, \{a_2\}, \{a_3\}, \{a_1; a_2\},$
$\{a_1; a_3\}, \{a_2; a_3\}, \{a_1; a_2; a_3\}$.

Các tập con của tập hợp $C$:
$\emptyset, \{a_1\}, \{a_2\}, \{a_3\}, \{a_1; a_2\}, \{a_1; a_3\},$
$\{a_1; a_4\}, \{a_2; a_3\}, \{a_2; a_4\}, \{a_3; a_4\},$
