---
id: 1979-6-bleher-kelbert-algoritmyi-klassifikatsii-884adaf7
issue: kvant_1979_6
year: 1979
number: "6"
title: Thuật toán phân loại
authors:
  - Блехер П. М.
  - Кельберт М. Я.
rubric: osnovnye-stati
page_first: 4
page_last: 9
page_labels: 2-7
tag: 79U4
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 8f3bef25e939f7bd58f4a44e9d97d9d603b2519e1a0d99eed6b5ae2fb9263d36
prompt_sha256: draft-1
translated_from: content/ru/1979/06/articles/03_bleher-kelbert-algoritmyi-klassifikatsii-884adaf7.md
source_content_sha256: 254160ba9dc8bd14f5ef6259b22eb3e04f5cad349ba569850809f384a4e62563
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

P. Blecher, M. Kelbert

Thuật toán phân loại

Trong bài viết này, chúng ta sẽ nói về một trong những lĩnh vực khoa học mới xuất hiện cách đây không lâu - lý thuyết về nhận dạng mẫu *). Cụ thể: chúng ta sẽ nói về các phương pháp phân loại. Phân loại là việc phân chia một tập hợp các đối tượng nhất định thành các nhóm đối tượng gần nhau theo một nghĩa nào đó. Ví dụ: bạn có thể phân loại các nhà máy trong một ngành nhất định đã được quan sát thấy trong một số trận động đất trong khu vực, thời tiết tháng 9 trong nhiều năm, thằn lằn tuyệt chủng, v.v. Điều quan trọng là các đối tượng được phân loại phải được đặc trưng bởi một bộ số và đặc điểm nhất định. Để đơn giản, chúng ta sẽ xem xét trường hợp mỗi đối tượng chỉ được mô tả bằng một tập hợp số.

*) Đối với những ai muốn làm quen với việc sử dụng nó, chúng tôi khuyên bạn nên đọc cuốn sách hấp dẫn, mặc dù không đơn giản lắm của M. M. Bongard “Vấn đề về sự công nhận” (M., “Hayka”, 1967).

Cách phân loại học sinh?

Giả sử chúng ta muốn chia tất cả học sinh lớp 9 của một trường nhất định theo cách các em sử dụng thời gian ngoài giờ học. Chúng tôi yêu cầu mỗi học sinh viết ra phần nào mình dành cho việc học và phần nào để giải trí. Thời gian còn lại (để ăn, ngủ, đi lại, v.v.) hiện không được chúng ta quan tâm. Như vậy, mỗi học sinh sẽ được đặc trưng bởi hai con số: thời gian học và thời gian giải trí. Do đó, nó có thể được biểu diễn bằng một điểm trên mặt phẳng tọa độ. Vì vậy, chúng ta đi đến một câu hỏi toán học thuần túy: làm thế nào để chia một tập hợp đã cho thành các nhóm có số giống nhau?

Nhiều màu xám được áp dụng bài toán cũng dẫn đến câu hỏi tương tự, chỉ có điều ở đó số tọa độ thành phố lớn hơn (khoảng vài chục).

Ví dụ, có rất nhiều doanh nghiệp trong ngành dệt may. Trong số đó có

⟦folio 3⟧

và các nhà máy chuyên biệt với một phạm vi nhỏ các sản phẩm và các nhà máy sản xuất nhiều loại sản phẩm. Có những nhà máy khổng lồ, có những nhà máy cỡ vừa và có những cơ sở sản xuất nhỏ ở địa phương. Để so sánh chi tiết các đối tượng riêng lẻ và lập kế hoạch công việc của chúng, cần phải phân loại tất cả các đối tượng này - chia chúng thành các nhóm đối tượng tương tự. Các doanh nghiệp được phân biệt bởi các chỉ số kinh tế của họ. Chúng tôi sẽ chọn trong số đó một số yếu tố quan trọng nhất (ví dụ: chi phí xây dựng các hạng mục riêng lẻ và quỹ tiền lương) và sẽ phân loại chúng theo chúng. Số lượng chỉ báo được chọn sẽ được ký hiệu là $n$.

Chúng ta hãy liên kết từng đối tượng với một tập hợp số $(x_1; \dots; x_n)$, trong đó $x_1$ là giá trị của chỉ báo đầu tiên, $x_2$ là giá trị của chỉ báo thứ hai, v.v.

Một cặp số $(x_1; x_2)$ xác định một điểm trên mặt phẳng, bộ ba số $(x_1; x_2; x_3)$ xác định một điểm trong không gian và một chuỗi $n$ số $(x_1; x_2; \dots; x_n)$ theo định nghĩa được coi là không gian $n$ chiều mạnh mẽ.

Vì vậy, lần này chúng ta đi đến phân loại bài toán các điểm trong không gian $n$ chiều.

Thật khó khăn khi không có ô tô

Để phân loại lời giải bài toán, nhiều thuật toán khác nhau đã được phát triển cho phép sử dụng máy tính. Nhu cầu sử dụng máy tính xuất phát từ hai lý do. Thứ nhất, theo quy luật, có rất nhiều đối tượng và việc xử lý tất cả dữ liệu theo cách thủ công là không thể. Thứ hai, các đối tượng được phân loại thường đa chiều.

Nếu, như trong ví dụ với học sinh, chỉ có hai tọa độ và số lượng đồ vật ít, thì một người có thể xử lý nhiệm vụ phân loại không thua kém gì một chiếc máy tính. Cụ thể: anh ta sẽ nhìn vào một bức tranh trong đó các điểm tượng trưng cho các vật thể được mô tả và anh ta sẽ nhìn thấy những đám mây tương ứng với sự ngưng tụ của điểm đó. Các thí nghiệm cho thấy tất cả mọi người đều làm điều này theo cách gần giống nhau. Điều này là do họ (con người) vô tình có xu hướng đảm bảo rằng các điểm trong một nhóm ở gần nhau và các nhóm khác nhau ở đủ xa. Nếu số lượng tham số bằng hoặc lớn hơn thì các thông báo trực quan hóa thực tế đã vô dụng và việc phân loại bài toán trở nên khó hiểu đối với con người.

Các nhà tâm lý học đã tiến hành thí nghiệm sau *. Các đối tượng được phát một bộ thẻ có các số tương ứng với tọa độ của các điểm trong không gian. Yêu cầu chia điểm thành hai nhóm tự nhiên. Trên thực tế, đã có một mặt phẳng, nhìn một góc theo tọa độ osm, nó chia tất cả các điểm thành hai nhóm sao cho khoảng cách từ một điểm bất kỳ đến mặt phẳng này là khá lớn so với khoảng cách giữa các điểm trong mỗi nhóm. Hầu hết mọi người đều coi giá trị của một trong các tọa độ, dẫn đến sự phân chia không tự nhiên; Hầu như không ai có thể xây dựng một phân vùng chính xác.

Các thuật toán phân loại đã được phát triển cho các điểm trong không gian đa chiều. Tuy nhiên, một trong những tiêu chí để các thuật toán này hoạt động chính xác là yêu cầu khi phân loại điểm trên mặt phẳng phải đưa ra các phân vùng tự nhiên - giống như những phân vùng mà con người tìm thấy.

Cây có chiều dài tối thiểu

Bây giờ chúng ta sẽ mô tả thuật toán xây dựng kết nối giữa một hệ thống các đoạn mới nối các điểm này với tổng chiều dài tối thiểu (hệ thống các đoạn được gọi là kết nối nếu

*) Thí nghiệm này và một số thí nghiệm tương tự khác được mô tả trong cuốn sách “Các phương pháp nhận dạng và ứng dụng của chúng” của N. G. Zagoruko (M., “Đài phát thanh Liên Xô”, 1972). Trong cuốn sách này, bạn có thể đọc chi tiết hơn về nhiều câu hỏi mà chúng tôi sẽ chỉ đề cập sơ qua.

⟦folio 4⟧

từ bất kỳ điểm nào dọc theo các phân đoạn của hệ thống này, bạn có thể thêm vào bất kỳ điểm nào khác). Để rõ ràng, chúng tôi sẽ xem xét việc xây dựng trên một mặt phẳng. Trong không gian đa chiều, thuật toán giống nhau nhưng bạn không thể vẽ được một bức tranh.

Vì vậy, đường dẫn trên mặt phẳng dữ liệu là $N$ điểm $A_1, \dots, A_N$. Để đơn giản, chúng ta sẽ giả sử rằng tất cả các khoảng cách theo cặp giữa các điểm là khác nhau. Chúng ta hãy viết ra tất cả các cặp điểm $(A_1, A_2), (A_1, A_3), \dots, (A_{N-1}, A_N)$ và sắp xếp chúng sao cho đầu tiên là cặp có khoảng cách tối thiểu giữa các điểm, tiếp theo là cặp có khoảng cách lớn thứ hai, v.v. Bây giờ nối cặp điểm đầu tiên, sau đó đến cặp điểm thứ hai, v.v. Nếu khi vẽ đoạn tiếp theo, một chu trình xuất hiện (nghĩa là, từ hệ thống các đoạn đã vẽ, bạn có thể chọn một số đoạn tạo thành một đường đứt nét khép kín), thì chúng ta sẽ bỏ qua đoạn này và chuyển sang đoạn tiếp theo, v.v. - cho đến khi chúng ta đi qua tất cả các phân đoạn. Bằng cách xây dựng, hệ thống phân đoạn kết quả không chứa chu trình. (Một hệ thống các phân đoạn được kết nối không có chu trình được gọi là *cây*)

Bài toán 1. Chứng minh rằng hệ đoạn được xây dựng có độ dài tối thiểu trong tất cả các hệ liên thông của các đoạn nối các điểm này.

Bài toán 2. Chứng minh rằng có thể thu được cùng một hệ phân đoạn bằng cách xây dựng trước, như các nhà toán học nói, sau đây: nối tất cả các cặp điểm với các đoạn thẳng và sắp xếp các đoạn này theo thứ tự độ dài giảm dần; loại bỏ đoạn dài nhất, sau đó là đoạn dài thứ hai, v.v.; nếu khi loại bỏ phân đoạn tiếp theo, các phân đoạn còn lại không tạo thành một tập hợp được kết nối thì chúng ta sẽ bỏ qua phân đoạn này và chuyển sang phân đoạn tiếp theo, v.v. - cho đến khi chúng ta liệt kê tất cả các phân đoạn.

Bài toán 3*. Giả sử có sự trùng hợp giữa các khoảng cách theo cặp giữa các điểm $A_1, \dots, A_N$. Chúng ta hãy sắp xếp các đoạn có độ dài bằng nhau một cách tùy ý và thực hiện quy trình được mô tả trong văn bản hoặc trong nhiệm vụ 2. Chứng minh rằng hệ thống các đoạn được xây dựng có độ dài tối thiểu không phụ thuộc vào cách sắp xếp các đoạn bằng nhau. Tất nhiên, trong trường hợp này hệ thống các đoạn có độ dài tối thiểu có thể không phải là duy nhất.

Thuật toán chúng tôi đã mô tả để xây dựng một cây có độ dài tối thiểu

tương đối đơn giản nhưng đòi hỏi phải tìm kiếm nhiều và do đó phải được chạy bằng máy tính. Có các thuật toán nhanh hơn (nhưng cũng phức tạp hơn!).

Nhóm

Sau khi xây dựng được cây Г có chiều dài tối thiểu, việc phân chia tập hợp các điểm $A_1, \dots, A_N$ thành các nhóm được thực hiện bằng cách rút ra một số đoạn có trong cây này. Đương nhiên, các đoạn khá dài được vẽ, nhưng sao cho các điểm thuộc một nhóm được đặt càng gần nhau càng tốt. Thông điệp trực quan này có thể được chính thức hóa bằng cách nhập số lượng sau. Chúng ta muốn chia tập hợp các điểm $A_1, \dots, A_N$ thành các nhóm $k + 1$. Chúng ta hãy chọn các đoạn $k$ tùy ý của cây Г và loại bỏ chúng (Hình 1). Chúng tôi nhận được $k + 1$ nhóm điểm được kết nối: $\Gamma_1, \dots, \Gamma_{k+1}$. Đối với mỗi nhóm $\Gamma_i$, chúng ta chia tổng độ dài các đoạn của cây Г, các điểm kết nối có trong cây, cho số đoạn. Chúng tôi thu được độ dài trung bình của các đoạn trong mỗi nhóm $\Gamma_i$. Nếu một nhóm nào đó bao gồm một điểm thì theo định nghĩa độ dài trung bình này bằng không. Chúng ta hãy biểu thị độ dài trung bình được tính toán bằng $l_1, l_2, \dots, l_k, l_{k+1}$. Ngoài ra, hãy để độ dài của các đoạn được lấy lại là $b_1, b_2, \dots, b_k$. Hãy hình thành số lượng

$$F = l_1 + l_2 + \dots + l_{k+1} - b_1 - \dots - b_k.$$

Rõ ràng là giá trị $F$ càng nhỏ thì các điểm của mỗi nhóm càng gần nhau và các nhóm khác nhau càng cách xa nhau.

⟦folio 5⟧

Do đó, việc đề xuất thuật toán sau là điều đương nhiên: từ một cây có độ dài tối thiểu, chúng tôi loại bỏ các phân đoạn $k$ theo mọi cách có thể và tính toán các giá trị $F$; Trong số tất cả các phân vùng thu được, chúng tôi chọn phân vùng có giá trị $F$ là tối thiểu; nếu có một số phân vùng “tối thiểu”, chúng tôi sẽ lấy bất kỳ phân vùng nào trong số đó.

Do các thuật toán được sử dụng, giá trị $F$ được xác định, theo quy luật, theo cách phức tạp hơn.

Thực hành tính toán đã chỉ ra rằng các thuật toán thuộc loại được mô tả dẫn đến các phân vùng khá hợp lý. Nhược điểm chính của các thuật toán này là chúng đòi hỏi quá nhiều sức mạnh. Khi số điểm tăng lên, bài toán sẽ không thể truy cập được ngay cả với các máy tính hiện đại.

Để đối phó với khó khăn này, những ý tưởng sau đây được sử dụng. Các điểm có khoảng cách giữa chúng nhỏ hơn một giá trị nhất định $a$, có xu hướng thuộc về cùng một nhóm. Tất cả việc xây dựng được thực hiện trong hai giai đoạn. Ở giai đoạn đầu tiên, tập hợp các điểm $A_1, \dots, A_N$ được chia thành các nhóm nhỏ hơn $G_1, \dots, G_m$ sao cho mỗi nhóm $G_i$ có một vòng tròn $S_i$ bán kính $R = a/2$ chứa tất cả các điểm của nhóm $G_i$ và chỉ chúng. Chúng tôi sẽ thảo luận về cách thực hiện điều này dưới đây. Ở giai đoạn thứ hai, chỉ xem xét tâm $O_1, \dots, O_m$ của các vòng tròn $S_1, \dots, S_m$ và một cây có độ dài tối thiểu được xây dựng cho tập hợp $O_1, \dots, O_m$. Bằng cách giảm thiểu giá trị $F$ tương ứng với cây này, việc phân vùng tập hợp các điểm $O_1, \dots, O_m$ thành các nhóm được xây dựng như mô tả ở trên. Như vậy, ta cũng thu được phân vùng của tập hợp điểm $A_1, \dots, A_N$. Cụ thể, hai điểm $A_i, A_j$ thuộc cùng một nhóm nếu chúng nằm trong cùng một nhóm nhỏ $G_i$ hoặc nếu tâm của các đường tròn tương ứng với nhóm nhỏ và rơi vào một nhóm khi chia các điểm $O_1, \dots, O_m$. Ý nghĩa của quy trình hai giai đoạn này là giảm số điểm bắt đầu: số $m$ hóa ra nhỏ hơn nhiều so với $N$ và bộ xử lý cũng có thể được triển khai trên máy tính.

Vấn đề chuyển động vòng tròn

Chúng ta vẫn còn phải thảo luận về cách chia tập hợp các điểm $A_1, \dots, A_N$ thành các nhóm nhỏ. Đối với lời giải, bài toán thuật toán Trout được sử dụng (nó phần nào gợi nhớ đến một trong những phương pháp đánh bắt cá hồi). Chúng ta sẽ mô tả thuật toán này cho các điểm trên mặt phẳng, mặc dù nó hoạt động theo cách tương tự trong không gian nhiều chiều.

Vì vậy, hãy cho $N$ điểm $A_1, \dots, A_N$ trên máy bay. Chúng ta hãy đặt những quả bóng có khối lượng đơn vị tại những điểm này và vẽ một số vòng tròn $S_0$ bán kính $R$, trong đó có ít nhất một trong số những quả bóng nằm trong đó. Gọi $O_1$ là trọng tâm của các quả bóng rơi vào đường tròn $S_0$, và $S_1$ là đường tròn có bán kính $R$ có tâm tại điểm $O_1$. Gọi $O_2$ là trọng tâm của các quả bóng rơi vào đường tròn $S_1$, và $S_2$ là đường tròn có bán kính $R$ có ​​tâm tại điểm $O_2$, v.v. Ví dụ: trong Hình 2.

⟦folio 6⟧

Vòng tròn dọc theo tuyến đường $S_0 \rightarrow S_1 \rightarrow S_2 \rightarrow \dots$ không thể kéo dài mãi được. Chúng ta sẽ ấn định những điểm rơi vào vòng tròn cuối cùng cho nhóm đầu tiên. Quy trình tương tự được áp dụng cho các điểm còn lại, tức là một vòng tròn mới được “nhả”, vị trí cuối cùng của nó sẽ xác định nhóm thứ hai. Quá trình này tiếp tục cho đến khi tất cả các điểm được gán vào một nhóm.

Tại sao vòng tròn dừng lại?

Phần còn lại của chỉ số được dành để chứng minh rằng vòng tròn thực sự "dừng lại". Nhìn vào Hình 2, chúng ta nhận thấy các vòng tròn $S_0, S_1, S_2$, ... chiếm số lượng điểm ngày càng lớn và vị trí cuối cùng của chúng tương ứng với nhóm. Thật tự nhiên khi cho rằng đối với bất kỳ vị trí nào của điểm $A_1, \dots, A_N$ và đường tròn $S_0$, số điểm rơi vào các đường tròn $S_0, S_1, S_2$, ..., ít nhất, không giảm. Hình 3 cho thấy điều này không đúng; tuy nhiên, trong một số trường hợp có thể tăng lên, chỉ ngoài số điểm rơi vào đường tròn, người ta phải tính xem chúng nằm gần tâm đường tròn đến mức nào.

Cụ thể là đường dẫn đến một số vòng tròn $S$ có tâm $O$ bao gồm các điểm $A_{i_1}, \dots, A_{i_h}$; hãy xác định các giá trị

$$F(S) = \left(R^2 - |OA_{i_1}|^2\right) + \dots + \left(R^2 - |OA_{i_h}|^2\right).$$

Điểm càng gần tâm của vòng tròn $S$ thì đóng góp của nó vào các giá trị $F(S)$ càng lớn. Hãy chứng minh rằng dãy số $F(S_0), F(S_1)$,

$$F(S_2), \dots$$ tăng cho đến khi vòng tròn dừng lại.

Để chứng minh điều đó, chúng ta sẽ cần mômen phân cấp và hệ vật liệu các điểm $A_1, \dots, A_m$ liên quan đến một số $A$ và định lý Steiner, rất hữu ích cho lời giải nhiều bài toán không chỉ từ hình học mà còn từ cơ học *).

Momen quán tính của hệ vật chất của các điểm $A_1, \dots, A_m$ đối với điểm $A$ là đại lượng

$$I(A) = |AA_1|^2 + \dots + |AA_m|^2.$$

Định lý Steiner cho phép tính $I(A)$ nếu biết mômen quán tính $I(C)$. của hệ điểm này so với trọng tâm của chúng $C$. Định lý này phát biểu rằng

$$I(A) = I(C) + m|CA|^2.$$

Chúng ta hãy chứng minh định lý Steiner. Chúng ta hãy giới thiệu một hệ tọa độ hình chữ nhật, đặt gốc tọa độ của nó tại trọng tâm của điểm $A_1, \dots, A_m$ - điểm $C$. Chúng ta hãy biểu thị tọa độ của điểm $A_1, \dots, A_m$ bằng $(x_1; y_1), \dots, (x_m; y_m)$. Khi đó trọng tâm $C$ có tọa độ $(x_1 + \dots + x_m)/m; (y_1 + \dots + y_m)/m)$, và vì $C$ trùng với gốc tọa độ nên $x_1 + \dots + x_m = y_1 + \dots + y_m = 0$. Cho điểm $A$ có tọa độ $(x; y)$. Sau đó

$$I(A) = \left[ (x_1 - x)^2 + (y_1 - y)^2 \right] + \dots + \left[ (x_m - x)^2 + (y_m - y)^2 \right] = \left( x_1^2 + y_1^2 \right) + \dots + \left( x_m^2 + y_m^2 \right) + m \left( x^2 + y^2 \right) - 2x \left( x_1 + \dots + x_m \right) - 2y \left( y_1 + \dots + y_m \right) = I(C) + m|CA|^2,$$

kể từ $2x(x_1 + \dots + x_m) = 2y(y_1 + \dots + y_m) = 0$. Định lý Steiner đã được chứng minh.

Hãy chứng minh rằng nếu đường tròn $S_1$ không trùng với đường tròn $S_0$ thì $F(S_1) > F(S_0)$. Chúng ta hãy đánh số lại các điểm $A_1, \dots, A_m$ sao cho các điểm rơi vào đường tròn $S_0$ nhưng không rơi vào đường tròn $S_1$, có số từ 1 đến $p$, các điểm rơi vào giao điểm của đường tròn $S_0$ và $S_1$ có số từ $p + 1$ đến $q$, và các điểm

*) Xem cuốn sách của M. B. Balk “Ứng dụng hình học của khái niệm tâm mềm” (M., Fizmatiz, 1959).

⟦folio 7⟧

ki rơi vào $S_1$ nhưng không rơi vào $S_0$, là các số từ $q + 1$ đến $r$. Như vậy, trong đường tròn $S_0$ có các điểm $A_1, \dots, A_q$, và trong đường tròn $S_1$ có các điểm $A_{p+1}, \dots, A_r$. Rõ ràng là các đại lượng $F(S_0)$ có thể được biểu thị thông qua mômen quán tính $I(O)$ của điểm $A_1, \dots, A_q$ so với điểm $O$—tâm của đường tròn $S_0$, cụ thể là,

$$F(S_0) = (R^2 - |OA_1|^2) + \dots + (R^2 - |OA_q|^2) = qR^2 - I(O).$$

Điểm $O_1$ - tâm của đường tròn $S_1$ - là trọng tâm của các điểm $A_1, \dots, A_q$, do đó, theo định lý Steiner

$$I(O) = I(O_1) + q |OO_1|^2,$$

đó là

$$F(S_0) = qR^2 - I(O_1) - q |OO_1|^2 = (R^2 - |O_1A_1|^2) + \dots + (R^2 - |O_1A_q|^2) - q |OO_1|^2.$$

Hãy so sánh biểu thức này với

$$F(S_1) = (R^2 - |O_1A_{p+1}|^2) + \dots + (R^2 - |O_1A_r|^2).$$

Biểu thức $F(S_1)$ thiếu thuật ngữ

$$(R^2 - |O_1A_1|^2), \dots, (R^2 - |O_1A_p|^2),$$

nhưng các điều khoản đã xuất hiện

$$(R^2 - |O_1A_{q+1}|^2), \dots, (R^2 - |O_1A_r|^2).$$

Pozny

$$F(S_1) - F(S_0) = -(R^2 - |O_1A_1|^2) - \dots - (R^2 - |O_1A_p|^2) + (R^2 - |O_1A_{q+1}|^2) + \dots + (R^2 - |O_1A_r|^2) + q |OO_1|^2.$$

Bây giờ chúng ta hãy lưu ý—và đây là tình huống mang tính quyết định—rằng các điểm $A_1, \dots, A_q$, theo cách xây dựng, nằm trong nekurata $S_1$. Vì vậy, đại lượng $R^2 - |O_1A_1|^2, \dots, R^2 - |O_1A_p|^2$ chỉ mang tính chất tương đối. Ví dụ: các điểm $A_{q+1}, \dots, A_r$ nằm bên trong đường tròn $S_1$; do đó số lượng $R^2 - |O_1A_{q+1}|^2, \dots, R^2 - |O_1A_r|^2$ là tương đối. Như vậy,

$$F(S_1) - F(S_0) \geq q |OO_1|^2,$$

nghĩa là, $F(S_1) > F(S_0)$ nếu các điểm $O_1$ và $O$ không trùng nhau.

Tương tự, người ta chứng minh rằng $F(S_{k+1}) > F(S_k)$ nếu điểm $O_{k+1}$ và $O_k$ không trùng nhau. Sử dụng thực tế này, bây giờ dễ dàng chứng minh rằng, bắt đầu từ một số $n$ nào đó, tất cả các đường tròn $S_n, S_{n+1}, \dots$ đều trùng nhau. Theo cách xây dựng, điểm $O_{m+1}$ là trọng tâm của các điểm nằm trong đường tròn $S_m$. Nếu chúng ta xem xét tất cả các tập hợp con của tập hợp điểm $A_1, \dots, A_N$ và trọng tâm của điểm của các tập hợp con này, thì điểm $O_{m+1}$ sẽ là một trong những trọng tâm này. Vì tập hợp các trọng tâm là hữu hạn nên trong dãy các tâm $O, O_1, O_2, \dots$ phải có sự trùng khớp, chẳng hạn như $O_i$ và $O_j$. Tuy nhiên, chúng tôi đã chứng minh rằng

$$F(S_i) \leq F(S_{i+1}) \leq \dots \leq F(S_j),$$

và vì $S_i = S_j$, $F(S_i) = F(S_j)$, do đó $F(S_i) = F(S_{i+1}) = \dots = F(S_j)$.

Bây giờ chúng ta hãy nhớ rằng đẳng thức $F(S_i) = F(S_{i+1})$ có thể xảy ra nếu các đường tròn $S_i$ và $S_{i+1}$ trùng nhau. Cần lưu ý rằng nếu hai đường tròn liên tiếp trùng nhau thì tất cả các đường tròn tiếp theo đều trùng với nó trong cách xây dựng. Như vậy, chúng ta đã chứng minh rằng chuyển động của đường tròn $S_0 \rightarrow S_1 \rightarrow S_2 \rightarrow \dots$ không thể là vô hạn, hay nói về mặt toán học, chúng ta đã chứng minh được sự hội tụ của thuật toán Trout. Trong quá trình thực hiện, chúng tôi đã phân tích lời giải bài toán, được đề xuất tại lần tối ưu hóa toán học gần đây nhất ở Moscow và trong bài toán «Kvant» (xem bài toán M505 trong «Kvant», 1978, số 5).

Hai bài toán mới

Để kết luận, chúng tôi xây dựng thêm hai bài toán. Các quy trình được mô tả trong các bài toán này cũng được sử dụng để phân loại một điểm trong không gian đa chiều. Như trước đây, chúng ta giới hạn mình trong trường hợp máy bay.

Bài toán 4. Hãy chia $N$ các viên đá $A_1, \dots, A_N$ thành các nhóm $l$ (không trống) $G_1, \dots, G_l$. Gọi $O_1, \dots, O_l$ là trọng tâm của mỗi nhóm này. Chúng ta hãy xây dựng một phân vùng mới gồm các viên đá $A_1, \dots, A_N$ theo quy tắc sau: chúng ta gán từng điểm cho nhóm thứ $i$ ($i \leq l$), nếu gần với nó
