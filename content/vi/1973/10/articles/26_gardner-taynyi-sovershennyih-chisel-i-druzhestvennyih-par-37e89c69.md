---
id: 1973-10-gardner-taynyi-sovershennyih-chisel-i-druzhestvennyih-par-37e89c69
issue: kvant_1973_10
year: 1973
number: "10"
title: Bí mật của những con số hoàn hảo và những cặp đôi thân thiện
authors:
  - Гарднер М.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 73
page_last: 76
page_labels: 71-74
tag: HSZ9
lang: vi
source: kvant_digital
extraction: vision
content_sha256: a89fdc096fa1f970bda80a5d9515f38e3fe3a1ad346ae0875b517dc88f5533c9
prompt_sha256: draft-1
translated_from: content/ru/1973/10/articles/26_gardner-taynyi-sovershennyih-chisel-i-druzhestvennyih-par-37e89c69.md
source_content_sha256: 40dbe9aa82619463d6fae6365f7265748a4bfb399f3c21b5c1c1f44784c2a475
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 71⟧

A. S. Varpakhovsky
Bí mật của số hoàn hảo và các cặp khác

Trong số thứ tám của tạp chí của chúng tôi năm 1971, có ghi chú của I. Ya. Delman đã được xuất bản về lịch sử của cái gọi là số hoàn hảo - những con số bằng tổng các ước của chúng. Để tiếp tục chủ đề này, chúng tôi đăng một bài viết đã được sửa đổi của M. Gardner *), trong đó nói về những đặc tính đáng chú ý của những con số này. Ấn phẩm dành cho «Kvant» do A. S. Varpakhovsky chuẩn bị.

Làm ơn, không có số nào có lịch sử hấp dẫn như số hoàn hảo và họ hàng gần nhất của chúng - những số khác.

Bước quan trọng đầu tiên trong việc xây dựng lý thuyết về số hoàn hảo được thực hiện bởi Euclid, người đã xác định rằng công thức $2^{n-1} (2^n-1)$ cho một số hoàn hảo bất cứ khi nào thừa số trong ngoặc trở thành số nguyên tố (để làm được điều này, điều cần thiết là $n$ phải là số nguyên tố, mặc dù không phải với mọi số nguyên tố $n$ thì số $2^n-1$ cũng là số nguyên tố).

Đây là bằng chứng của lý thuyết Euclid. Đặt số $2^{n-1} (2^n-1)$ được đặt đơn giản trong ngoặc. thì các ước của số này, khác với chính số đó, sẽ là

$$1, 2, 4, \dots, 2^{n-1},$$
$$2 (2^n-1), 4 (2^n-1), \dots, 2^{n-2} \times (2^n-1).$$

Hãy lấy tổng của tất cả các ước số này:

$$(1 + 2 + 4 + 8 + \dots + 2^{n-1}) + (1 + 2 + 4 + 8 + \dots + 2^{n-2}) \times (2^n-1) = (2^n-1) + (2^{n-1}-1) \times (2^n-1) = 2^{n-1} (2^n-1)$$

Vì vậy, số $2^{n-1} (2^n-1)$ là hoàn hảo.

2000 năm sau, Leonhard Euler đã chứng minh rằng công thức Euclid xác định tất cả các số hoàn hảo chẵn. Điều tò mò là cho đến nay vẫn chưa ai tìm được số hoàn hảo lẻ và có lẽ số đó hoàn toàn không tồn tại. Vì vậy, trong tương lai, khi nói về số hoàn hảo, chúng ta sẽ hiểu là số hoàn hảo chẵn. Công thức tuyệt vời của Euclid liên quan chặt chẽ đến cấp số nhân tổng quát có giá trị 2 (1, 2, 4, 8, 16, . . .).

Chúng ta hãy nhớ lại câu chuyện cổ về vị vua Ba Tư và tác giả của ván cờ. Rất ngưỡng mộ trò chơi này, nhà vua đã mời tác giả chọn rương cho riêng mình. Thoạt nhìn, ông tỏ ra mong muốn rất khiêm tốn, yêu cầu đặt một hạt lúa mì vào ô đầu tiên của bàn cờ, hai hạt ở ô thứ hai, bốn hạt ở ô thứ ba, và bằng cách này sẽ lấp đầy tất cả 64 ô. Hóa ra số hạt ở ô cuối cùng là 9.223.372.036.854.775.808, và gấp đôi con số này không có 1 bằng tổng số hạt trên bảng, gấp vài nghìn lần lượng lúa mì hàng năm trên toàn thế giới. Sau khi viết vào mỗi ô của bàn cờ số hạt cần có trong đó và lấy một hạt từ mỗi ô, chúng ta sẽ thấy phần còn lại trong ô

⟦folio 72⟧

Hình 1.

số hạt trong công thức Euclid được xác định bởi biểu thức $2^n - 1$. Nếu số này là số nguyên tố thì nhân nó với số hạt ở ô trước đó, tức là với $2^{n-1}$, chúng ta sẽ thu được một số hoàn hảo. (xem hình 1).

Các số nguyên tố trong dãy $2^n - 1$ được gọi là số Mersenne theo tên nhà toán học người Pháp thế kỷ 17 đã nghiên cứu chúng *). TRÊN

*) Xem thêm «Kvant», 1971, số 8, tr. 3.

Ở hàng 1, các ô đó được tô bóng, sau khi trừ 1 sẽ thu được số Mersenne. Có 9 ô như vậy trên bảng - chúng tương ứng với hai số đầu tiên ở phía bắc.

Các con số phía bắc có một số tính chất bí ẩn và đồng thời đáng chú ý. Ví dụ: tất cả các số hoàn hảo đều là “tam giác”. Điều này có nghĩa là nếu bạn lấy một số quả bóng bằng một số hoàn hảo thì chúng có thể được sắp xếp sao cho tạo thành một tam giác đều.

Nói cách khác, mọi số hoàn hảo đều là tổng có dạng $1 + 2 + 3 + 4 + ... + n$.

Cũng có thể dễ dàng nhận thấy rằng mọi số hoàn hảo, ngoại trừ 6, đều là tổng một phần của dãy lập phương các số lẻ $1^3 + 3^3 + 5^3 + ...$.

Và đây là một tính chất khác của số hoàn hảo: tổng các giá trị nghịch đảo của ước số của một số hoàn hảo, kể cả chính số đó là ước số, luôn bằng 2. Vì vậy, đối với số 28, chúng ta có

$$\frac{1}{1} + \frac{1}{2} + \frac{1}{4} + \frac{1}{7} + \frac{1}{14} + \frac{1}{28} = 2.$$

Ngày nay có còn thiếu đáp số cho câu hỏi quan trọng: có số hoàn hảo lẻ và có số hoàn hảo chẵn lớn nhất không? Cho đến cxx, người ta vẫn chưa tìm thấy một số hoàn hảo lẻ nào, nhưng đồng thời người ta cũng chưa chứng minh được rằng con số đó không tồn tại. Đáp số cho câu hỏi thứ hai phụ thuộc vào việc chuỗi số nguyên tố Mersenne có phải là vô hạn hay không, vì mỗi số nguyên tố trong chuỗi này đều dẫn đến một số hoàn hảo. Người ta đã quan sát thấy rằng bằng cách thay thế bốn số Mersenne đầu tiên (3, 7, 31, 127) cùng với $n$ vào công thức $2^n - 1$, người ta lại thu được số Mersenne. Hơn 70 nhà toán học đã phát hiện ra rằng mô hình như vậy sẽ dẫn đến kết luận rằng chuỗi số nguyên tố Mersenne là vô hạn. Tuy nhiên, vào năm 1953, một chiếc máy tính đã dập tắt hy vọng của họ. Người ta đã tìm thấy rằng

⟦folio 73⟧

trong trường hợp $n = 2^{13} - 1 = 8191$ (số nguyên tố Mersenne), số $2^{8191} - 1$ không phải là số nguyên tố. Người ta vẫn chưa biết liệu chuỗi Mersenne là vô hạn hay nó chứa số lớn nhất.

Ore, trong cuốn sách Lý thuyết số và lịch sử của nó, đã trích dẫn một phát biểu thú vị của Peter Barlow từ cuốn sách Lý thuyết số, được ông viết vào năm 1811. Barlow, sau khi tính số thứ chín trăm, đã tuyên bố rằng “đây là số nhiều nhất từng được tìm thấy, bởi vì các số hoàn hảo chỉ gây tò mò và liệu việc cố gắng tìm một số hoàn hảo lớn hơn có gây hại cho bất cứ ai hay không”. Tuy nhiên, vào năm 1876, nhà toán học người Pháp Edward Luxas, tác giả của tác phẩm kinh điển gồm bốn tập về toán học phức tạp, đã công bố phát hiện ra số hoàn hảo thứ mười hai $2^{126} (2^{127} - 1)$. Luxas sau đó nghi ngờ rằng $2^{127} - 1$ là số nguyên tố Mersenne, nhưng tính đơn giản của nó sau đó đã được xác nhận. $2^{127} - 1$ là số Mersenne được tìm thấy nhiều nhất mà không cần sự trợ giúp của máy tính. Bảng 1 trình bày các biểu thức sử dụng công thức Euclid cho 23 số hoàn hảo đã biết, số đầu tiên trong số chúng được viết ra (các số tiếp theo chứa danh sách nhiều dấu hiệu) và số vị trí thập phân cho mỗi số này được chỉ định. Số hoàn hảo cuối cùng được biết đến, có 22.425 ước số, ra đời vào năm 1963 sau khi máy tính của Đại học Illinois phát hiện ra số Mersenne thứ 23. Để vinh danh sự kiện này, khoa toán của trường đại học đã dán tem lên các bưu phẩm có dòng chữ: “$2^{11213} - 1$ là số nguyên tố”.

Tổng quát hóa của số hoàn hảo là số thân thiện. Lấy bất kỳ số nào và tổng các ước của nó để có được số thứ hai. Sau đó, chúng ta cộng các thừa số của số thứ hai, v.v., với hy vọng rằng cuối cùng chúng ta sẽ có được số ban đầu. Nếu số ban đầu thu được ở bước đầu tiên thì số nguyên đó chỉ có một liên kết và bản thân số đó là hoàn hảo. Với một số nguyên có hai phần, hai số tạo thành một cặp thân thiện: tổng các ước của một trong các số này bằng số kia. Các số thân thiện nhỏ nhất tạo thành một cặp là 220 và 284.

Năm 1636, Pierre Fermat tìm ra một cặp số thân thiện khác: 17.296 và 18.416. Ông và René Descartes đã độc lập làm việc để tìm ra sự hình thành chính xác của các cặp thân thiện, không nghi ngờ rằng sự hình thành chính xác này đã được hình thành từ thế kỷ thứ 9 bởi một nhà thiên văn học người Ả Rập *. Cặp thứ ba được Descartes tìm ra: 9.363.584 và 9.437.056. Vào thế kỷ 18, Euler đã công bố

*) Một cư dân của thành phố Harran của Potamian - Abu-l-Hasan Sabit ibn Korra ibn Marwan al-Sabi al-Harrani (khoảng 830-901). (Ghi chú của biên tập viên)

⟦folio 74⟧

Tuy nhiên, một danh sách gồm 64 cặp khác, như cuộc kiểm tra sau đó cho thấy, trong hai trường hợp, ông đã nhầm lẫn. Năm 1830, Adrien Marie Legendre tìm ra một cặp khác, và đến năm 1867, chàng trai trẻ người Ý 16 tuổi V. I. Paganini đã khiến giới toán học ngạc nhiên khi tuyên bố rằng các số 1184 và 1210 là những số khác. Đây là cặp lớn thứ hai mà mọi người bỏ qua. Và mặc dù Paganini có thể đã tìm ra cặp này bằng cách thử và sai, nhưng tên tuổi của ông đã đi vào lịch sử lý thuyết số.

Ngày nay, hơn 600 cặp khác đã được biết đến; nhiều cặp số có trên 30 chữ số. Cặp được biết đến cuối cùng được tính toán trên máy tính vào năm 1964. Bảng 2 cho thấy các cặp khác khác trong phạm vi số từ 0 đến 100.000.

Tất cả các cặp đã biết khác đều bao gồm hai số chẵn hoặc (ít phổ biến hơn nhiều) hai số lẻ. Nhưng chưa ai chứng minh được rằng không có cặp hỗn hợp nào khác. Bratley và McKay đưa ra giả thuyết rằng tất cả các số lẻ khác đều chia hết cho 3 và tổng các số tạo thành một cặp số khác là bội số của 9. Chưa có ai đề xuất công thức chung cho tất cả các cặp số khác và cũng không biết số lượng các cặp số đó là hữu hạn hay vô hạn.

Hiện tại, người ta chỉ biết có hai chuỗi số dẫn đến số ban đầu và có
