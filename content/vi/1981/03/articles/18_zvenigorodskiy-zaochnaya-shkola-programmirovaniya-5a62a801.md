---
id: 1981-3-zvenigorodskiy-zaochnaya-shkola-programmirovaniya-5a62a801
issue: kvant_1981_3
year: 1981
number: "3"
title: Trường lập trình tương ứng
authors:
  - Звенигородский Г. А.
rubric: raznoe
rubric_sub: Разное
page_first: 59
page_last: 60
page_labels: 57-58
tag: UZ8P
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 84a3c5cf833c047ce1d30135a8636eac01f83fccf73da9ca545b5df0e414cfa8
prompt_sha256: draft-1
translated_from: content/ru/1981/03/articles/18_zvenigorodskiy-zaochnaya-shkola-programmirovaniya-5a62a801.md
source_content_sha256: 208803e39e6d84b143ebbd2c9e778e1089340a4dd8a1269de283ca5b97121e1e
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 57⟧

Trường lập trình tương ứng
Bài 14: Làm việc với đồ thị

Các trang của «Kvant» đã xuất bản nhiều bài viết về đồ thị và các bài toán liên quan trong những năm gần đây. Hầu hết mọi bài báo đều nói rằng đối với lời giải những máy tính bài toán như vậy đã được sử dụng rộng rãi. Hôm nay chúng ta đang nói về cách làm việc với biểu đồ trên máy tính bằng cách sử dụng các khả năng của ngôn ngữ Rapier.
Sinh viên ZShP chưa quen với các định nghĩa cơ bản của lý thuyết đồ thị có thể đọc chúng trong bài viết của V. Evstigneev trên trang. 18 của số này*).

*) Để hoàn thành nhiệm vụ của bài 14, không cần thiết phải đọc hết bài quy định: chỉ cần các định nghĩa cơ bản được đưa ra ở đầu bài. Tuy nhiên, chúng tôi thực sự khuyên sinh viên SLP nên đọc và phân tích chi tiết bài viết theo vòng lặp.

Đồ thị được khám phá

Cấu trúc của nhiều hệ thống khác nhau mà từ đó mọi thứ được áp dụng vào thực tế có thể được mô tả bằng đồ thị. Rất thường xuyên có bài toán, trong đó cần phải tính đến không chỉ sự hiện diện của các kết nối giữa các phần tử của hệ thống mà còn cả các thuộc tính của các kết nối này, cũng như các thuộc tính của chính các phần tử. Để mô tả các điều kiện của bài toán như vậy cần phải “tải” đồ thị, nghĩa là gán một số số, văn bản hoặc các đối tượng khác cho các cạnh hoặc đỉnh của chúng (và đôi khi là cả hai). Ví dụ: nếu hệ thống đường của hội đồng làng Shpagovsky (Hình 1, a) cần được biểu diễn dưới dạng biểu đồ và không yêu cầu thông tin về độ dài của mỗi con đường, thì sẽ thu được một biểu đồ có các cạnh được tải (Hình 1, b).

Nhiệm vụ 14.1. Vẽ dưới dạng biểu đồ được tải, sơ đồ các đường hữu ích giữa thủ đô của các nguồn lực cấu thành của Liên Xô, biểu thị khoảng cách.

Đồ thị trong bộ nhớ máy tính

Nếu trong lời giải bài toán bạn cần ghi một vài bộ vào bộ nhớ máy tính và thực hiện các phép toán chung trên chúng,

đến thành phố Videoton
làng Robik
làng Malaya Bzsmovka
làng lượng tử
Hoa hồng cuối cùng
Với. Big Shpadi
nước ép làng mát
r. Luồng thông tin

Hình 1.

⟦folio 58⟧

Hình 2.

Ratsini, thì bằng ngôn ngữ Rapier, bạn sẽ có thể thực hiện việc này mà không gặp khó khăn gì. Nhưng không có công cụ đặc biệt nào để làm việc với biểu đồ trong Rapier, vì vậy bạn cần phải tự mình nghĩ ra cách mô tả biểu đồ bằng ngôn ngữ lập trình này.

Hãy xem máy phải nhớ những gì để biết mọi thứ về đồ thị có hướng cần thiết cho lời giải bài toán. Đầu tiên, nó phải nhớ nhiều đỉnh. Tất nhiên, để làm được điều này, bạn cần chỉ định bằng cách nào đó từng đỉnh, chẳng hạn như đánh số nó, như trong Hình 2. Thứ hai, bạn cần nhớ nơi mỗi cung bắt đầu và kết thúc. Thông thường, một cung được mô tả bằng cách sử dụng một bộ gồm các ký hiệu của đỉnh bắt đầu và đỉnh kết thúc của nó. Ví dụ, trong cùng một hình, cung nối đỉnh 1 và 5 có thể được mô tả bằng bộ 〈1,5〉.

Thông tin về tất cả các cung của một sơ đồ có thể được lưu trữ dưới dạng một tập hợp gồm các bộ dữ liệu như vậy. Cuối cùng, một bộ gồm hai tập hợp được mô tả - một tập hợp các đỉnh và một tập hợp các cung - là một mô tả đầy đủ về một đồ thị ghép trên Rapier. Ví dụ: đồ thị trong Hình 2 có thể được mô tả như sau:

«*1,2,3,4,5,6,7*»
«*1,3», «1,5», «1,4», «2,1»
«2,3», «3,5», «5,3», «5,6»
«5,7», «6,5», «6,6», «7,1*»〉.

Nhiệm vụ 14.2. Vẽ một biểu đồ có hướng, mô tả về nó trên Rapier trông như thế này:

«*1,2,3,4,5,6*», «*1,4», «2,1»
«3,1», «3,2», «3,4», «3,5», «4,5»
«5,6», «6,2», «6,3*»〉.

Nếu bạn cần mô tả một đồ thị có các cung được tải thì phần tử thứ ba sẽ xuất hiện trong các bộ dữ liệu mô tả các cung—giá trị tải. Nhiệm vụ 14.3. Đồ thị BOOKOVKA được mô tả trên Rapier như sau:

«*1,2,3,4,5,6*»
«*1,2',T'», «2,3',P'», «2,5'K'», «3,5',A'»
«4,1',H'», «4,4',T'», «5,6',B'», «6,4',A'*»〉
-> THƯ;

Đường viền của mỗi cung là văn bản. Bằng cách di chuyển dọc theo bất kỳ đường dẫn nào trong biểu đồ và viết ra các văn bản tương ứng với các cung liên tiếp, bạn có thể nhận được các từ khác nhau.

a) Đoạn văn nào tương ứng với đường đi qua các đỉnh 2,5,6,4,1,2?

b) Bạn cần nổi bật như thế nào để có được chữ VATA?

b) Có đường nào trong biểu đồ mà người ta có thể nhận được từ UNG THƯ không? Từ GRASS?

Để việc nhập thông tin về đồ thị vào bộ nhớ máy tính trở nên dễ dàng hơn, thật thuận tiện khi mô tả một chức năng sẽ yêu cầu kịp thời tất cả các thông tin cần thiết. Đối với đồ thị có hướng có các đỉnh và cung được đánh số có tải bằng số, hàm này có thể trông như sau:

YÊU CẦU PHẦN TRĂM = >ĐỒ HỌA;
"**" -> CHỨC NĂNG; "**" -> ARCS;
PRINT('BAO NHIÊU ĐỈNH TRONG BIỂU ĐỒ?');
ENTER(1) ->SỐ;1 ->SỐ;
TẠM BIỆT SỐ = <CHIVER::
ĐỈNH + “*SỐ*”
-> ĐỨNG;
SỐ +1 ->SỐ
TẤT CẢ;
'CÓ' -> TIẾP TỤC;
TẠM BIỆT TIẾP TỤC = 'CÓ'::
IN('TÊN ĐỈNH BẮT ĐẦU');
NHẬP(1) ->BẮT ĐẦU;
IN('TÊN CUỐI ĐỨC');
NHẬP(1) ->TẢI;
NẾU (BẮT ĐẦU TỪ TRÊN)
VÀ (CHUYỂN ĐỔI TỪ TRÊN) SANG ARC + “*BẮT ĐẦU,CHUYỂN ĐỔI, LOAD*” ->ARC;
PRINT('Có cung nào không?');
NHẬP(0) -> TIẾP TỤC
