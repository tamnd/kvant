---
id: 2009-5-koshelev-raygorodskiy-zadacha-erdyosha-sekeresha-prodolzhenie-istorii-4a0e7c49
issue: kvant_2009_5
year: 2009
number: "5"
title: 'Bài toán Erdős-Szekeres: tiếp tục câu chuyện'
authors:
  - Кошелев В. А.
  - Райгородский А. М.
rubric: raznoe
page_first: 15
page_last: 15
page_labels: "13"
tag: MXFD
lang: vi
source: kvant_digital
extraction: native
content_sha256: f0f59cdd71eba66bca142ab7429b87ee59ead1962e52ce48467b51c71e354e0d
prompt_sha256: draft-1
translated_from: content/ru/2009/05/articles/01_koshelev-raygorodskiy-zadacha-erdyosha-sekeresha-prodolzhenie-istorii-4a0e7c49.md
source_content_sha256: 367dd31716bbf3708f5e7f55d29e6fa945d7a3ad349ccbbeece42b34635dfef4
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 13⟧

Bài toán Erdos – Szekeres: tiếp nối câu chuyện

V. KOSHELEV, A. RAIGORODSKY

Lại lên đường

Ở «Kvant» số 2 năm nay, bài viết của chúng tôi “Bài toán Erdős–Szekeres về đa giác lồi” [1] đã được xuất bản. Ở đó, chúng tôi kể câu chuyện đáng kinh ngạc (và đôi khi thậm chí lãng mạn) về một trong những bài toán hay nhất và phổ biến nhất trong hình học tổ hợp - một câu chuyện bắt đầu từ 75 năm trước và còn rất lâu mới kết thúc. Tất nhiên, người đọc muốn hiểu rõ nguồn gốc của những gì chúng ta sẽ nói trong bài viết này phải trang bị cho mình bài viết nói trên, bởi vì ở đây chúng ta sẽ chỉ nhớ lại một bản tóm tắt ngắn gọn về “loạt bài trước”, và sau đó chúng ta sẽ chuyển sang những lĩnh vực cơ bản mới đối với chúng ta, cho đến nay vẫn chưa được khám phá. Vì vậy, đối tượng nghiên cứu chính của chúng tôi là tập hợp các điểm ở vị trí tổng quát trên mặt phẳng. Hãy nhớ rằng đây là tất cả các tập hợp trong đó không có ba phần tử nào nằm trên cùng một đường thẳng. Mục tiêu của chúng tôi là tìm cho mỗi số tự nhiên n giá trị của hàm g(n), mà chúng tôi giả sử bằng g nhỏ nhất sao cho ở bất kỳ vị trí tổng quát nào được đặt trên mặt phẳng với số lượng g, nhất thiết phải có n điểm là các đỉnh của một n-giác lồi. Đầu tiên, chúng ta thảo luận về hành vi của hàm g(n) đối với $n \in { 3,4,5,6 }$ và phát hiện ra rằng mọi lúc $g ( n ) = 2^{n} -^{2} + 1$. Sau đó, chúng tôi tin rằng nói chung với mọi $n \ge 3$ giá trị của g(n) là hữu hạn và hơn nữa, $g ( n ) \le 4^{n}$, chính xác hơn là $g ( n ) \le C_{2} nn --_{5}^{2} + 1$ đối với $n \ge 5$. Cuối cùng, một lần nữa, chúng tôi đã chứng minh điều đó với bất kỳ $n g ( n ) \ge 2^{n} -^{2} + 1$ nào. Về cơ bản đó là tất cả. Tuy nhiên, hóa ra đây mới chỉ là khởi đầu của cuộc hành trình. Và vấn đề không chỉ là dạng chính xác của hàm g ( n ) vẫn chưa được biết (theo các tác giả của bài toán, chúng ta chỉ có thể tin rằng $g ( n ) = 2^{n} -^{2} + 1 );$ vấn đề còn nằm ở chỗ bài toán ban đầu cho phép thực hiện một số khái quát hóa rất tự nhiên, không kém phần đẹp đẽ và, như người ta nói trong khoa học, là các sửa đổi. Bây giờ chúng ta sẽ nói về chúng.

Đa giác lồi và rỗng

Sửa đổi bài toán của Erdős–Szekeres

Gần nửa thế kỷ sau khi xuất bản bài báo đáng chú ý [2], hay chính xác hơn là vào năm 1978, P. Erdős đã đề xuất sửa đổi một chút điều kiện của bài toán ban đầu, mà vào thời điểm đó đã trở thành cổ điển.

⟦column⟧

Anh ta đặt câu hỏi: điều gì sẽ xảy ra nếu chúng ta tìm kiếm vị trí tổng quát $множестве^{X}$ này hay vị trí tổng quát khác trên mặt phẳng không chỉ các đỉnh của đa giác lồi, mà cả các đỉnh của đa giác lồi đó, bên trong không có điểm nào khác $множества^{X}$? Điều tự nhiên là gọi những đa giác như vậy là trống hoặc lỗ. hình1 hiển thị ví dụ về lỗ và ví dụ về không lỗ. Chúng ta hãy giới thiệu đại lượng h(n), đại lượng này sẽ đóng vai trò tương tự với đại lượng g(n) trong khuôn khổ của Hình 1 mới. Ví dụ về tiếng hú có lỗ và không có lỗ bài toán. Nó có nghĩa là gì? Về lý thuyết, mọi thứ rất đơn giản. Giả sử rằng với một số tự nhiên cho trước $n \ge 3$, chúng ta đã tìm được một số h sao cho trong bất kỳ vị trí tổng quát nào đặt trên mặt phẳng với số lượng h đều có một n-giác trống và có một tập hợp vị trí tổng quát trên mặt phẳng có kích thước h – 1 và không chứa lỗ trống trên n đỉnh. Vậy hãy đặt h ( n ) = h. Chỉ? Không thực sự. Vấn đề là vẫn chưa rõ tại sao sự hiện diện của các đa giác trống trong một tập hợp điểm h tùy ý đảm bảo cho chúng ta sự hiện diện của chúng trong mọi tập hợp kích thước h + 1. Một vấn đề nảy sinh khi thỏa mãn điều kiện trống rỗng, điều kiện này không có trước đó (tức là khi xác định giá trị của g(n)). Nói cách khác, nếu trước đây chúng ta bình tĩnh nói về giá trị biên g(n), bắt đầu từ đó mọi tập hợp có kích thước phù hợp đều chứa một đa giác lồi, thì từ nay trở đi vẫn cần phải đạt được sự bình tĩnh như vậy. May mắn thay, vấn đề có thể dễ dàng khắc phục được. Phát biểu 1. Giả sử, với một số h, bất kỳ vị trí tổng quát nào đặt trên mặt phẳng với số lượng h đều chứa một n-giác lồi và rỗng. Khi đó điều tương tự cũng đúng với mọi tập tổng quát có kích thước h + 1. Chứng minh. Xét một tập X tùy ý có số lượng $h + 1. Пусть^{H}$ – một đa giác là bao lồi của nó (xem [1]). Hãy xóa $из^{X}$ bất kỳ đỉnh nào của đa giác này. Những gì còn lại là một tập hợp có kích thước h, theo giả định của chúng tôi, chứa một n-giác lồi và rỗng. Rõ ràng, đỉnh chúng ta ném ra nằm ngoài n-giác này. Điều này có nghĩa là X chứa một n-giác lồi và rỗng. Tuyên bố đã được chứng minh. Nếu với mỗi h tồn tại một tập hợp
