---
id: 2020-8-knop-volshebniki-dzhona-konveya-1cd5a016
issue: kvant_2020_8
year: 2020
number: "8"
title: Những phù thủy của John Conway
authors:
  - Кноп К. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 43
page_last: 45
page_labels: 42-43
tag: LF8A
lang: vi
source: kvant_digital
extraction: native
content_sha256: 6a158a692b4a32e501f9b5ebd140934094deb766973c885786e35dd426b4f844
prompt_sha256: draft-1
translated_from: content/ru/2020/08/articles/06_knop-volshebniki-dzhona-konveya-1cd5a016.md
source_content_sha256: 500f4c9043d74d28a7f91d9e644276bc09554c5fb552f7f678f09691120cde36
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

VÒNG TRÒN TOÁN HỌC

Những phù thủy của John Conway

K.KNOP

NHÀ TOÁN HỌC NỔI BẬT John Horton Conway nổi tiếng không chỉ vì sự phát triển lý thuyết trò chơi tổ hợp mà còn vì những đóng góp to lớn của ông cho việc giải trí toán học. Lần đầu tiên tôi nghe một trong những bài toán hấp dẫn nhất của Conway trong một câu chuyện kể lại của T. Khovanova [1], và chính câu chuyện này đã làm cơ sở cho bài viết này. Cái này bài toán: Đêm qua tôi đi cùng xe buýt với hai thầy phù thủy và tình cờ nghe được cuộc trò chuyện của họ: A: Tôi có mấy đứa con, tuổi của mỗi đứa là một số nguyên dương, và tổng của chúng bằng số của chiếc xe buýt này, và tích bằng tuổi của tôi. B: Thật thú vị! Có lẽ nếu bạn cho tôi biết tuổi của bạn và số con của bạn, tôi có thể tính được tuổi của chúng? Đ: Không, bạn không thể. B: Vâng! Cuối cùng tôi đã biết được tuổi của bạn. Số xe buýt chúng ta đã đi là bao nhiêu? Tôi sẽ bắt đầu với một số ý kiến. Tác giả của câu đố, John Conway, đã suy nghĩ cẩn thận về toàn bộ môi trường xung quanh. Đặc biệt, xe buýt (xe buýt) được chọn làm bối cảnh vì cùng với tuổi (tuổi) của thuật sĩ đầu tiên và số con (trẻ em) của mình, Conway đã thu được các ký hiệu thuận tiện cho ba giá trị số - a, b, c. Có lẽ tôi cũng sẽ giữ những danh hiệu này. Vì vậy, gọi a là tuổi của thuật sĩ đầu tiên, b là số xe buýt (chúng tôi không biết, nhưng thuật sĩ thứ hai biết) và c là số con của thuật sĩ đầu tiên. Nhận xét thứ hai liên quan đến cụm từ của thuật sĩ A "Không, bạn không thể." Trong tuyên bố này, thầy phù thủy không hề nghi ngờ gì về khả năng trí tuệ của bạn mình. Điều đó có nghĩa là ngay cả với bộ ba số a, b, c đã biết hoàn toàn cũng không thể

DOI: https://doi.org/10.4213/kvant20200804

⟦column⟧

xác định rõ độ tuổi của trẻ. Nói cách khác, có một số nhóm độ tuổi khác nhau của trẻ em cho cùng các giá trị a, b, c. Hãy gọi những tập hợp độ tuổi như vậy là Conway, hay tập hợp K. Điều khiến câu đố này vô cùng đẹp đẽ là nó rất khó tiếp cận. Nếu chúng ta biết tuổi của phù thủy (số a), thì chúng ta có thể xem qua các ước số của anh ta và tìm thấy tất cả các biến thể của tổng của chúng. Nếu số xe buýt (b) đã biết, thì có thể phân tách nó theo nhiều cách khác nhau thành tổng các số hạng và thu được các biến thể cho sản phẩm của chúng. Và ngay cả khi chúng ta chỉ biết số lượng trẻ em (c), quy mô tìm kiếm vẫn nhỏ hơn đáng kể. Một số người bạn của tôi đã dành vài giờ để lập trình liệt kê các tùy chọn và chỉ sau đó mới tìm ra cách tiếp cận lời giải chính xác. Không phải là bài toán dường như hoàn toàn chưa được xác định rõ ràng, tức là cho phép lời giải khác nhau sao? Đây là một trong những lý lẽ điển hình. Giả sử họ đang đi trên xe buýt số 21 (b 21), thầy phù thủy 96 tuổi (a 96) và có ba người con (c 3). Điều này có nghĩa là tuổi của chúng là ba số tự nhiên có tổng bằng 21 và tích bằng 96. Có hai bộ ba số như vậy: 1, 8, 12 và 2, 3, 16, tức là. Thật vậy, ngay cả khi thuật sĩ thứ hai phát hiện ra tất cả những điều này, anh ta sẽ không thể xác định được tuổi của những đứa trẻ. Cái này đáp số có tốt không? Tại sao? Chẳng phải chúng ta đã tìm thấy những con số thỏa mãn mọi điều kiện trong cuộc đối thoại của các thầy phù thủy sao? Không, họ không tìm thấy nó. Đáp số "96 tuổi, xe buýt số 21, 3 đứa trẻ" không hoạt động vì nó không tính đến dòng cuối cùng - thuật sĩ B đó đã có thể tính ra tuổi của thuật sĩ A. Liệu anh ấy có thể làm được điều này nếu chỉ biết số xe buýt? Nói cách khác, có K-bộ số khác có cùng b nhưng khác a không? Để trả lời câu hỏi này, chúng ta hãy đặt ra nó theo cách khác. Có K-bộ ba số nào khác có b nhỏ hơn và a khác không? Rốt cuộc, nếu chúng được tìm thấy, thì bạn chỉ cần thêm một số trẻ một tuổi vào chúng để tổng các số (số b) trong Tập kết quả bằng 21. Trong trường hợp này, tích (số a, tức là tuổi của phù thủy) sẽ không thay đổi và sẽ vẫn khác với số cũ. Thật vậy, những bộ ba K như vậy rất dễ tìm thấy: ví dụ: đây là 1, 5, 8 và 2, 2, 10. Thêm-

⟦folio 42⟧

KVA NT 2020/Số 8

Bằng cách thêm trẻ một tuổi vào chúng, bạn có thể nhận được bộ K với bất kỳ b! 14 (và tuổi của thầy phù thủy là 40 tuổi). Và từ K-tuple 1, 6, 6 và 2, 2, 9, một thao tác tương tự sẽ cho ra K-tuple với b bất kỳ! 13, trong khi phù thủy đã 36 tuổi. Do đó, số xe buýt không thể nhiều hơn 13 - vì trong trường hợp này, thuật sĩ B sẽ không thể hiểu được đối tác của mình 40 tuổi hay 36 tuổi (và có lẽ sẽ có một số lựa chọn khác). Có vẻ như chúng ta đã nắm bắt được “cái đuôi” bên phải của câu đố này. Chúng ta cần tìm số bus nhỏ nhất cung cấp hai bộ K - và khi đó tất cả các số tiếp theo sẽ không hoạt động.

trữ tình lạc đề

Chẳng lẽ phù thủy A chỉ có một đứa con? Hiển nhiên là không: khi đó tuổi của anh ấy sẽ trùng với cả số xe buýt và tuổi của A, và đây là trường hợp duy nhất khi b a. Do đó, sau khi học (tính toán) a, thuật sĩ B sẽ xác định ngay số con (từ 1) và tuổi của đứa trẻ này - nhưng chúng ta phải tin A, người cho rằng điều này không thể thực hiện được. Thế còn hai đứa trẻ (c 2) thì sao? Sau đó, khi tính tuổi của a và biết số xe buýt của b, thuật sĩ B sẽ biết tổng và tích của hai số tự nhiên. Liệu anh ta có thể tự tìm ra các con số không? Tương tự hình học của bài toán này là bán chu vi và diện tích của hình chữ nhật có các cạnh mà chúng ta muốn tìm đã biết (Hình 1). Hóa ra là trong

⟦figure⟧

Cơm. 1

Trong trường hợp này, bạn có thể tự tìm ra các số (trong phiên bản hình học, các cạnh của hình chữ nhật) ngay cả khi chúng không phải là số nguyên, nhưng để làm được điều này, bạn cần có khả năng giải phương trình bậc hai. Trong trường hợp của chúng tôi, chúng tôi có thể thực hiện bằng một tìm kiếm đơn giản: tìm tất cả các cặp số có tổng cho trước, bắt đầu bằng cặp 1 và b 1, sau đó “gộp” các số lại với nhau - tích của chúng sẽ tăng lên. Tại thời điểm tích bằng a, các số cần tìm sẽ được tìm thấy. Vì thế, ngay cả đối với hai đứa con, A cũng không thể nói “Không”. Vì vậy, khi liệt kê có thể loại bỏ tất cả các phương án có một và hai con.

⟦column⟧

Có thứ gì khác có thể bỏ được không? Đúng. Vì chúng ta muốn tìm số xe buýt tối thiểu mang lại sự mơ hồ trong việc lựa chọn độ tuổi của trẻ em nên không nên có các số trùng khớp trong các KSet khác nhau - bởi vì nếu có, chúng có thể bị xóa khỏi mỗi bộ và khi đó số xe buýt (tổng) thậm chí còn nhỏ hơn. Ví dụ: nếu một trong các bộ có trẻ một tuổi thì bộ kia không nên có. Vì vậy, ở một trong các bộ K, tất cả trẻ em đều trên một tuổi. Hãy tổng hợp các kết quả trung gian. Bây giờ chúng ta sẽ tìm các phân tách của số bus b thành tổng của một số số hạng tự nhiên lớn hơn 1. Trong trường hợp này, chúng ta chỉ xem xét những phân tách trong đó số lượng các số hạng không nhỏ hơn 3 và bản thân số bus không lớn hơn 12 (vì đối với 13, chúng ta đã biết cặp K-tuples cần thiết và chúng ta muốn tìm một bộ thậm chí còn nhỏ hơn hoặc đảm bảo rằng nó không tồn tại). Đi thôi! Xem xét các lựa chọn chắc chắn không phải là công việc dễ chịu nhất, nhưng đôi khi cần thiết cho một lời giải cuộc sống bài toán thành công. Trong tìm kiếm của chúng tôi, chúng tôi sẽ đánh dấu bằng biểu tượng các dòng có các giá trị của a xuất hiện (trong toàn bộ tìm kiếm) nhiều lần và với các giá trị b khác nhau. Đầu tiên, chúng ta liệt kê các khai triển trong đó mỗi số hạng lớn hơn 1: 6 2 + 2 + 2 (a 8) 7 2 + 2 + 3 (a 12) 8 2 + 2 + 2 + 2 (a 16) 8 2 + 2 + 4 (a 16) 8 2 + 3 + 3 (a 18) 9 2 + 2 + 2 + 3 (a 24) 9 2 + 2 + 5 (a 20) 9 2 + 3 + 4 (a 24) 9 3 + 3 + 3 (a 27) 10 2 + 2 + 2 + 2 + 2 (a 32) 10 2 + 2 + 2 + 4 (a 32) 10 2 + 2 + 3 + 3 (a 36) 10 2 + 2 + 6 (a 24) 10 2 + 3 + 5 (a 30) 10 2 + 4 + 4 (a 32) 10 3 + 3 + 4 (a 36) 11 2 + 2 + 2 + 2 + 3 (a 48) 11 2 + 2 + 2 + 5 (a 40) 11 2 + 2 + 3 + 4 (a 48) 11 2 + 3 + 3 + 3 (a 54) 11 2 + 2 + 7 (a 28) 11 2 + 3 + 6 (a 36) 11 2 + 4 + 5 (a 40) 11 3 + 3 + 5 (a 45) 11 3 + 4 + 4 (a 48) 12 2 + 2 + 2 + 2 + 2 + 2 (a 64)

⟦folio 43⟧

TOÁN HỌC

12 2 + 2 + 2 + 2 + 4 (a 64) 12 2 + 2 + 2 + 3 + 3 (a 72) 12 2 + 2 + 2 + 6 (a 48) 12 2 + 2 + 3 + 5 (a 60) 12 2 + 2 + 4 + 4 (a 64) 12 2 + 3 + 3 + 4 (a 72) 12 3 + 3 + 3 + 3 (a 81) 12 2 + 2 + 8 (a 32) 12 2 + 3 + 7 (a 42) 12 2 + 4 + 6 (a 48) 12 2 + 5 + 5 (a 50) 12 3 + 3 + 6 (a 54) 12 3 + 4 + 5 (a 60) 12 4 + 4 + 4 (a 64) Cuộc tìm kiếm vẫn chưa kết thúc: xét cho cùng, vẫn còn những Kset có một, và có lẽ còn nhiều hơn nữa. Phải làm gì với chúng? Chúng tôi sẽ không viết chúng ra một cách riêng biệt mà sẽ thêm các bộ một và hai thuật ngữ vào những thuật ngữ đã được viết ra, sau đó chúng tôi sẽ theo dõi từng tùy chọn theo bảng đã viết sẵn - sau cùng, việc thêm một hoặc một số đơn vị (i) sẽ bảo quản sản phẩm; (ii) tăng số lượng con lên một mức nào đó; (iii) tăng số b lên cùng một lượng, tức là tổng số tuổi của trẻ em. Các bộ đã viết trước đó được thêm vào: 2 2 (a 2) 3 3 (a 3) ... 11 11 (a 11) 4 2 + 2 (a 4) 5 2 + 3 (a 6) 6 3 + 3 (a 9) 6 2 + 4 (a 8) 7 3 + 4 (a 12) 7 2 + 5 (a 10) 8 4 + 4 (a 16) 8 3 + 5 (a 15) 8 2 + 6 (a 12) 9 4 + 5 (a 20) 9 3 + 6 (a 18) 9 2 + 7 (a 14) 10 5 + 5 (a 25) 10 4 + 6 (a 24) 10 3 + 7 (a 21) 10 2 + 8 (a 16) 11 5 + 6 (a 30) 11 4 + 7 (a 28) 11 3 + 8 (a 24) 11 2 + 9 (a 18) Chúng ta sẽ không viết tổng từ 12 trở lên nữa vì sau khi thêm đơn vị, chúng sẽ tăng lên.

VÒNG TRÒN

⟦column⟧

Vì các bộ K phải có cùng a, nên chúng ta sẽ chỉ quan tâm đến các hàng được đánh dấu bằng a. Hãy viết lại tất cả các tập hợp, sắp xếp chúng theo thứ tự tăng dần a: 5 2 + 3 (a 6) 6 6 (a 6)

6 8

2 + 2 + 2 8 (a 8)

2 + 4 (a 8)

6 9

3 + 3 (a 9) 9 (a 9)

7 2 + 5 (a 10) 10 10 (a 10)

7 8

2 + 2 + 3 3 + 4 (a 12) 2 + 6 (a 12)

8 2 + 2 + 2 + 2 2 + 2 + 4 10 2 + 8 (a 16)

4 + 4 (a 16)

8 2 + 3 + 3 (a 18) 9 3 + 6 (a 18) 11 2 + 9 (a 18)

9 2 + 2 + 2 + 3 2 + 3 + 4 (a 24) 10 2 + 2 + 6 (a 24)

10 11

2 + 3 + 5 (a 30) 5 + 6 (a 30),

10 2 + 2 + 2 + 2 + 2 2 + 4 + 4 (a 32) 12 2 + 2 + 8 (a 32)

10 11

2 + 2 + 2 + 4

2 + 2 + 3 + 3 3 + 3 + 4 (a 36) 2 + 3 + 6 (a 36)

11 2 + 2 + 2 + 2 + 3 2 + 2 + 3 + 4 3 + 4 + 4 (a 48) 12 2 + 2 + 2 + 6 2 + 4 + 6 (a 48)

11 2 + 3 + 3 + 3 (a 54) 12 3 + 3 + 6 (a 54) Chà, bây giờ bạn có thể hoàn thành câu đố đến cùng theo bất kỳ cách nào bạn muốn - ví dụ: loại bỏ tất cả các tùy chọn chứa các số hạng bằng nhau (vì nếu có các số hạng như vậy, thì sau khi loại bỏ chúng, bạn sẽ nhận được một bộ khác, với tổng nhỏ hơn và tích nhỏ hơn). Và chúng ta có thể tính đến việc giá trị lớn hơn của tổng b trong một tập K khác tương ứng với số lượng con lớn hơn. Bằng cách này hay cách khác, trong tất cả những dòng được viết ra, chỉ có hai dòng phù hợp với chúng tôi -

11 12

3 + 4 + 4 (a 48) 2 + 2 + 2 + 6 (a 48)

Chúng dẫn đến hai tập hợp K như vậy: 12 1 + 3 + 4 + 4 2 + 2 + 2 + 6. Vì vậy, chúng ta đang lái xe
