---
id: 2009-2-koshelev-raygorodskiy-zadacha-erdyosha-sekeresha-o-vyipuklyih-mnogougolnikah-f6ec1d5c
issue: kvant_2009_2
year: 2009
number: "2"
title: Bài toán Erdős–Szekeres trên đa giác lồi
authors:
  - Кошелев В. А.
  - Райгородский А. М.
rubric: osnovnye-stati
page_first: 8
page_last: 11
page_labels: 6, 9
tag: CWGR
lang: vi
source: kvant_digital
extraction: native
content_sha256: bf7a117b9b73775d6001285b6f57d68793587e9c72ed294bd82fe08378d02248
prompt_sha256: draft-1
translated_from: content/ru/2009/02/articles/01_koshelev-raygorodskiy-zadacha-erdyosha-sekeresha-o-vyipuklyih-mnogougolnikah-f6ec1d5c.md
source_content_sha256: 0e8a8593eef64d983bf12a5f205f1266802a636fe7ce50111f621b6e17559c5f
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 6⟧

KVANT 2009/№2

Bài toán Erdos–Szekeres trên đa giác lồi

V. KOSHELEV, A. RAIGORODSKY

Lời chia tay

Bài toán, mà chúng tôi muốn nói đến trong bài viết này, được coi là một trong những viên ngọc quý của hình học tổ hợp. Sự đơn giản đặc biệt trong công thức của nó khiến cho một học sinh có thể tiếp cận một câu chuyện về nó, đồng thời tính không tầm thường của lời giải và vô số mối liên hệ của nó với các lĩnh vực toán học khác ngay lập tức đưa người nghe quan tâm đến vị trí hàng đầu của tổ hợp hiện đại. Bài toán điều này nảy sinh vào năm 1934, và mặc dù khả năng đếm nhanh không phải là một đặc điểm nổi bật của một nhà toán học, trái với niềm tin phổ biến, nhưng mỗi chúng ta sẽ ngay lập tức nhận ra rằng năm nay đánh dấu đúng 75 năm kể từ ngày sinh của bà. Đó không phải là một cuộc hẹn hò tròn trịa sao? Nào, hãy ăn mừng nó nào.

Những bước đầu tiên

Sản xuất bài toán

Chúng ta hãy xem xét một tập hợp hữu hạn các điểm X trên mặt phẳng và đặt câu hỏi chẳng hạn như sau: có đúng là trong tập hợp X sẽ luôn có ba điểm là các đỉnh của một tam giác không? Thoạt nhìn, câu hỏi có vẻ buồn cười. Rõ ràng là nếu có một hoặc hai điểm trong X thì không còn gì để nói; nếu X ³ 3 (số lượng của X không nhỏ hơn ba), thì có vẻ như ba phần tử bất kỳ trong tập hợp đều đóng vai trò là các đỉnh của một tam giác. Nó là như vậy, nhưng không hoàn toàn: nếu ba điểm từ tập X nằm trên cùng một đường thẳng thì sao? Khi đó sẽ khó có thể nói về một hình tam giác có các đỉnh trong đó. Và tình huống trong đó tất cả các điểm trong tập hợp của chúng ta được “xâu chuỗi” trên một đường thẳng là hoàn toàn không tốt. Nói tóm lại, đáp số đối với câu hỏi là tiêu cực một cách bất ngờ. Tuy nhiên, nếu ngay từ đầu chúng ta giả định rằng trong tập X không có ba điểm nào nằm trên cùng một đường thẳng, thì logic tự nhiên sẽ đúng và, với điều kiện X ³ 3, chúng ta có thể đảm bảo sự hiện diện của các tam giác trong X. Được rồi, chúng ta đã sắp xếp các tam giác. Vậy làm thế nào mọi thứ có thể tồn tại với $выпуклыми^{1}$ tứ giác, bạn-

1 Một tập hợp được gọi là lồi nếu cùng với hai điểm bất kỳ của nó, nó chứa toàn bộ đoạn thẳng nối chúng.

⟦column⟧

ngũ giác lồi, v.v.? Về lý thuyết, chúng ta muốn thu được đáp số ở dạng giống như trong trường hợp tam giác, cụ thể là: với mỗi n O ¥, n ³ 3, cần tìm một giá trị “biên” $g ( n ) О^{¥}$ sao cho trong mọi tập X không chứa bộ ba điểm trên cùng một đường thẳng và có ít nhất g ( n ) phần tử, có n đỉnh của một n-giác lồi và do đó với g ( n ) - 1 thuộc tính được mô tả không được đáp ứng. Ở đây g ( 3 ) = 3, và g ( 4 ), g ( 5 ), v.v. bằng bao nhiêu? Nói chung, những đại lượng này có tồn tại không (hay nói đúng hơn là chúng có hạn)? Rốt cuộc, rất có thể xảy ra rằng, chẳng hạn, với bất kỳ m nào cũng có một tập X có kích thước m trong đó không có đỉnh của hình thập giác lồi. Ai biết? Bài toán Erdős–Szekeres mà bây giờ chúng ta chuyển sang nghiên cứu, chính xác là việc tìm các giá trị của g ( n ). Dưới đây chúng tôi sẽ cho bạn biết rất nhiều điều thú vị về nó, nhưng bây giờ chúng tôi sẽ ghi chú nhỏ. Đối với công thức của bài toán, điều rất quan trọng là giả sử rằng các tập X không chứa bộ ba điểm trên cùng một đường thẳng. Trên thực tế, một tính chất như vậy hoạt động rất thường xuyên trong hình học, và do đó một thuật ngữ đặc biệt đã được phát minh ra cho nó: một tập X có tính chất này được cho là ở vị trí tổng quát. Nguồn gốc của thuật ngữ này là do theo nghĩa tự nhiên nào đó, “gần như tất cả” các tập hợp trên mặt phẳng đều ở một vị trí tổng quát - do đó có tính tổng quát. Tuy nhiên, chúng tôi sẽ không đưa ra nhận xét chi tiết hơn ở đây, nếu không chúng tôi sẽ đi quá xa lộ trình chính của mình. Điều chính là từ bây giờ, khi xem xét các tập hợp điểm trên mặt phẳng, chúng ta sẽ giả sử rằng chúng ở vị trí tổng quát: đơn giản là chúng ta không quan tâm đến các tập hợp khác.

Hãy giải quyết các hình tứ giác

Hiển nhiên, g ( 4 ) > 3 (không có chỗ nào để một tứ giác xuất hiện tại ba điểm). Có lẽ g(4) = 4? Tất nhiên là không. Chỉ cần nhìn vào hình 1 là đủ để hiểu điều này: các điểm được mô tả trong hình đều ở vị trí tổng quát, tuy nhiên, trong số chúng không có đỉnh của tứ giác lồi. Vì vậy, g ( 4 ) ³ 5. Hãy chứng minh rằng g ( 4 ) = 5, tức là hãy đảm bảo rằng trong bất kỳ

⟦folio 9⟧

NHIỆM VỤ

ERDES

–

SEKERESHA

anh ta đã giao một số tiền nhất định cho bài toán của mình, do đó xếp hạng bài toán theo “độ khó”. Tôi nghĩ số tiền lớn nhất mà anh ấy từng đưa ra là 3.000 USD. Và về giả thuyết 1, ông đã viết ngay trước khi qua đời vào năm 1996 rằng ông chắc chắn sẽ trả 500 USD để chứng minh điều đó. Điều buồn cười là ông không đưa tiền để bác bỏ giả thuyết: rõ ràng, ông tin chắc vào tính đúng đắn của nó và không muốn kích thích sự chuyển động sai lầm của tư duy toán học, theo quan điểm của mình. Với giả thuyết 1, những nỗ lực chứng minh nó và những vấn đề nhiều mặt nảy sinh xung quanh vấn đề này, công việc thực sự nghiêm túc về vấn đề này bắt đầu. Và chúng ta sẽ nói về điều này sau. Trước hết: chúng ta đã chỉ ra ở đâu đó g(n) < ¥ cho mỗi n chưa?

Vậy tại sao g(n) luôn tồn tại?

Đôi lời về định lý Ramsey

Trong toán học, mọi thứ đều có mối liên hệ với nhau và đôi khi đối với lời giải bài toán từ một lĩnh vực, cần phải áp dụng các cân nhắc từ các lĩnh vực mà thoạt nhìn có vẻ rất xa nó. Vì vậy, nó ở đây: chúng ta sẽ sớm thấy rằng bài toán Erdos–Szekeres có quyền truy cập trực tiếp vào định lý Ramsey cổ điển trong tổ hợp. Chúng ta hãy nhớ nó là gì, dần dần chuyển từ những trường hợp đặc biệt đơn giản sang những tình huống chung phức tạp hơn một chút. Vì vậy, chắc hẳn nhiều độc giả đã từng nghe câu nói kinh điển này của trường phái: trong sáu người bất kỳ, có ba cặp người quen hoặc ba cặp người lạ. Tuyên bố này rất dễ chứng minh và mọi người đều có thể dễ dàng tự mình đưa ra lý luận tương ứng. Nhân tiện, chúng ta hãy lưu ý rằng tuyên bố tương tự đối với năm người nói chung là không đúng. Sẽ thuận tiện (và được chấp nhận) khi hình thành tình huống được mô tả dưới dạng biểu đồ. Thật vậy, chúng ta thực sự đang nói về việc xem xét một biểu đồ hoàn chỉnh có sáu đỉnh "người", tô màu tất cả các cạnh $C_{6}^{2} = 15$ của nó là màu đỏ và xanh lam (cạnh màu đỏ có nghĩa là mọi người biết nhau, cạnh màu xanh lam có nghĩa là mọi người không biết nhau) và đảm bảo rằng biểu đồ có một hình tam giác với tất cả các cạnh màu đỏ hoặc biểu đồ có một hình tam giác với tất cả các cạnh màu xanh lam. Trong trường hợp này, một lần nữa, đối với một đồ thị hoàn chỉnh có năm đỉnh, con số như vậy không phù hợp. Và đây là một tuyên bố tổng quát hơn một chút bằng ngôn ngữ đồ thị. Với mọi số tự nhiên s, t, luôn tồn tại số tự nhiên nhỏ nhất $m_{0}$ có tính chất sau. Dù m ³ $m_{0}$ là gì và bất kể màu đỏ và xanh lam của các cạnh của một đồ thị hoàn chỉnh trên m đỉnh là gì, thì đồ thị đó có một đồ thị con hoàn chỉnh trên s đỉnh với tất cả các cạnh màu đỏ hoặc đồ thị có đồ thị con hoàn chỉnh trên t đỉnh với tất cả các cạnh màu xanh. Ví dụ: với s = t = 3 chúng ta có $m_{0} = 6$. Bây giờ hãy lưu ý rằng các cạnh của một đồ thị tất nhiên là các tập con gồm hai phần tử của tập các đỉnh của nó.

VỀ

Lồi

ĐA GIÁC

⟦column⟧

Điều gì sẽ xảy ra nếu từ bây giờ chúng ta bắt đầu vẽ không phải các cạnh mà là các tập hợp con ba, bốn,..., k phần tử của một tập hợp nhất định? Làm thế nào mà điều này tệ hơn? Không có gì! Và cuối cùng, đây là toàn bộ định lý Ramsey. Định lý Ramsey. Với mọi số tự nhiên $k, l_{1},^{K}, l_{r}$ đều có số tự nhiên nhỏ nhất $m_{0}$ có tính chất sau. Dù m ³ $m_{0}$ là gì, nếu mỗi tập con phần tử k của tập {1, …, m} được tô màu bằng một trong r màu có “tên” 1, …, r, thì có i O { 1, K r ​​​​} và một tập con phần tử $l_{i}$ T M { 1, K, m } sao cho tất cả các tập con phần tử k của nó đều có màu tên là i. Kết quả về đồ thị rút ra từ định lý này cho $k = 2, r = 2, l_{1} = s, l_{2} = t.$ Ở đây cũng có một sự tinh tế logic nhỏ mà về mặt lý thuyết, một người đọc tò mò sẽ nhận thấy ngay: điều gì sẽ xảy ra nếu $k > l_{i}$ đối với một số i? Giả sử, vẫn giữ k = 2, r = 2, nhưng $l_{1} = 1, l_{2} = 100.$ Trong trường hợp này, nguyên tắc “tất cả cá sấu ở sông Tumcha đều có màu đỏ” có tác dụng. Vấn đề là có thể nói bất cứ điều gì về các phần tử bị thiếu và do đó, ở đây $m_{0} = 1.$ Lý do tương tự được áp dụng trong các trường hợp tương tự khác. Chứng minh định lý Ramsey thu được bằng cách sử dụng quy nạp lặp lại và, vì tính sơ cấp, vẫn cần quá nhiều chỗ để trình bày trong ghi chú của chúng tôi. May mắn thay, đây là một thực tế cổ điển nên việc tìm ra bằng chứng đầy đủ của nó không khó. Bạn đọc có thể tham khảo cả tác phẩm gốc [5], [2] và nhiều nguồn thông dụng khác như [6], [7], [8]. Lưu ý rằng đối với đại lượng $m_{0}$ xuất hiện trong định lý, ký hiệu tiêu chuẩn ít nhiều $R_{k} ( l_{1},^{K}, l_{r} )$ sẽ được sử dụng. Đặc biệt, chúng tôi đã nói rằng $R_{2} ( 3, 3 ) = 6$ và $R_{2} ( 1, 100 ) = 1$. Nhân tiện, rất ít sự bình đẳng chính xác như vậy được biết đến. Cách dễ nhất để tìm danh sách chúng là trên Wikipedia (xem [9]), nơi có liên kết tới bài đánh giá [10]. Trong phần tiếp theo, chúng ta sẽ áp dụng định lý Ramsey để chứng minh g(n) < ¥.

Hai thủ thuật

Bây giờ chúng ta sẽ chứng minh rằng g(n) £ $R_{4} ( n, 5 )$. Thật vậy, đặt X là tập hợp các điểm bao gồm ít nhất $R_{4} ( n, 5 )$ phần tử. Hãy tô màu đỏ và xanh lam cho bốn điểm trong đó: nếu bốn điểm này là các đỉnh của một tứ giác lồi thì ta khai báo bốn điểm đó là màu đỏ; ngược lại chúng ta nói nó có màu xanh. Theo định lý Ramsey, có thể có hai lựa chọn. Trong một trong số chúng có năm điểm thuộc X, trong đó tất cả bốn điểm đều có màu xanh lam, tức là không có một tứ giác nào có thể tạo ra một tứ giác lồi. Nhưng điều này là vô nghĩa, vì nó mâu thuẫn với khẳng định của Klein rằng g ( 4 ) = 5. Điều này có nghĩa là chỉ còn lại phương án, trong đó có n điểm trong X không có bốn điểm màu xanh. Nói cách khác, mọi tứ giác tạo bởi những điểm này đều lồi. Điều này chỉ có thể thực hiện được nếu bản thân n điểm này là
