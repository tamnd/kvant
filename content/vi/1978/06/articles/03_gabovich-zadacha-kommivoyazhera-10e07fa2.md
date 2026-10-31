---
id: 1978-6-gabovich-zadacha-kommivoyazhera-10e07fa2
issue: kvant_1978_6
year: 1978
number: "6"
title: Bài toán nhân viên bán hàng du lịch
authors:
  - Габович Е. Я.
rubric: osnovnye-stati
page_first: 13
page_last: 22
page_labels: 11, 12, 13, 15, 16, 17, 18, 19, 20
tag: FRSF
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 805efd1abe81eb66fbd718462bb2e050741d6be3a11a42154cc763b0d311ad34
prompt_sha256: draft-1
translated_from: content/ru/1978/06/articles/03_gabovich-zadacha-kommivoyazhera-10e07fa2.md
source_content_sha256: 2b1e15e33b5a24ce2b54c92f93b63c7591c40f2ae90784a032fa734b814bdfc5
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 11⟧

E. Gabovich

Bài toán
nhân viên bán hàng du lịch

“Hãy sử dụng dịch vụ của Aeroflot!”
Hai chiếc xe, kỹ sư A. Nevsky và nhà kinh tế B. Liteiny, quyết định đến Transcaucasia, thăm Baku và Tbilisi, dừng chân ở Moscow, Kyiv và Gorky, rồi trở về quê hương Leningrad. Chúng tôi bắt đầu thảo luận về lộ trình du lịch. Nevsky nhìn vào bản đồ và gợi ý trình tự tham quan các thành phố sau đây:
L → M → G → B → T → K → L
Liteiny, sau khi lấy ra một bản đồ đường bộ, viết ra một bảng khoảng cách giữa các thành phố mà họ cần (xem Bảng 1) và tính toán độ dài của tuyến đường được đề xuất:
696 + 410 + 2937 + 579 + 1863 + 1207 = 7692 km. "Quá dài! - anh ấy nói. - Khoảng cách của Aeroflot! Có thể làm cho nó ngắn hơn không? Bạn có chắc tuyến đường này là ngắn nhất không?
Nevsky không có sự tự tin như vậy. Hơn nữa, Nevsky cũng không thể giải thích được tại sao mình lại quyết định đi theo con đường này. Trực giác đơn giản cho anh biết con đường như vậy sẽ như thế nào, nếu, v.v.

Bảng 1

| Thành phố | L | M | ĐẾN | B | T | G |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Leningrad | — | 696 | 1207 | 3223 | 2797 | 1106 |
| Mátxcơva | 696 | — | 858 | 2527 | 2101 | 410 |
| Kiev | 1207 | 858 | — | 2283 | 1863 | 1268 |
| Baku | 3223 | 2527 | 2283 | — | 579 | 2937 |
| Tbilisi | 2797 | 2101 | 1863 | 579 | — | 2511 |
| Vị đắng | 1106 | 410 | 1286 | 2937 | 2511 | — |

⟦folio 12⟧

không ngắn hơn tất cả những cái khác, thì nó gần như ngắn nhất.

“Chúng ta có nên xem xét tất cả các tuyến đường không? - Liteiny gợi ý. “Có nhiều tuyến đường không?” Anh bắt đầu đếm. “Từ Leningrad bạn có thể đi đến bất kỳ thành phố nào trong số năm thành phố. Ví dụ: nếu chúng ta đến Moscow, thì từ đó chúng ta có thể đi đến bất kỳ thành phố nào ngoài Leningrad và Moscow. Vì vậy, có 20 hành trình có dạng $Л \rightarrow X \rightarrow Y$, trong đó $Л \neq X \neq Y \neq Л$. Đã có 60 chuyến đi loại $Л \rightarrow X \rightarrow Y \rightarrow Z$, nhưng từ $Y$ bạn có thể đi đến bất kỳ thành phố nào trong ba thành phố còn lại. Nếu chọn $Z$, chúng ta có thể coi thành phố tiếp theo sau $Z$ là một trong hai thành phố tiếp theo. Vì vậy, 120 tuyến đường, hay hành trình kết thúc một cách rõ ràng: trên đường về nhà, bạn sẽ ghé thăm thành phố cuối cùng trong số sáu thành phố. Rất nhiều thứ! Vì vậy, đây không phải là một phương pháp để thử tất cả các tuyến đường! Rốt cuộc, nếu chúng tôi muốn đến thăm sáu thành phố, chúng tôi sẽ có 720, và nếu chúng tôi muốn đến thăm bảy thành phố, thì chúng tôi sẽ có 5040 tuyến đường!

"Vậy thì hãy làm điều này," Nevsky gợi ý, "chúng ta hãy đi từ Leningrad đến thành phố gần nhất, từ đó đến thành phố gần nhất chưa được ghé thăm, v.v. Điều này cho chúng ta tuyến đường $Л \rightarrow M \rightarrow Γ \rightarrow K \rightarrow T \rightarrow Б \rightarrow Л$. Chiều dài của nó, hiện được tính toán, là 8057 km. Dài hơn 365 km!"

Bài toán nhân viên bán hàng du lịch

Bài toán, mà Nevsky và Liteiny giải được, được biết đến trong toán học với cái tên bài toán của một người bán hàng lưu động *) (thương gia lưu động).

Hãy xây dựng nó ở dạng tổng quát: có $k$ thành phố, khoảng cách giữa chúng đã biết; nhân viên bán hàng lưu động cần rời khỏi một trong những thành phố này, ghé thăm các thành phố $k-1$ còn lại, ghé thăm mỗi thành phố đúng một lần và quay trở lại

*) Có lẽ người đầu tiên hình thành nhân viên bán hàng du lịch bài toán là nhà toán học nổi tiếng Carl Menger. Điều này xảy ra vào ngày 5 tháng 2 năm 1930 tại hội thảo toán học ở Vienna. Menger đã sử dụng câu nói nổi tiếng “Bài toán về người đưa tin”.

Cơm. 1.

thành phố nguồn; làm thế nào để tìm được con đường ngắn nhất?

Rõ ràng, việc lựa chọn điểm xuất phát của tuyến đường là không quan trọng - nhân viên bán hàng du lịch bài toán có thể được xây dựng như sau: tìm tuyến đường khép kín ngắn nhất, đi qua từng thành phố trong số $k$ một lần.

Bài tập 1. Chứng minh tổng số tuyến đường đi của nhân viên bán hàng là $(k-1)! = 1 \cdot 2 \cdot 3 \cdot \dots \cdot (k-1)$.

Lưu ý rằng bảng khoảng cách do B. Liteiny biên soạn (các nhà toán học gọi những bảng ma trận như vậy) hóa ra là đối xứng theo đường chéo mà đường thẳng được vẽ trên đó. Trong bài toán nhân viên bán hàng lưu động, các bảng không đối xứng cũng được phép. Ví dụ: bảng khoảng cách không đối xứng có thể xuất hiện trong bài toán sau đây (về tuyến xe buýt vòng tròn). Trong thành phố, trên một số đường thành phố chỉ được phép lưu thông một chiều, $k$ điểm (vị trí các điểm dừng trong tương lai) được cố định. Một tuyến xe buýt kín sẽ đi qua chúng. Cũng cần phải tìm một chuỗi tuần hoàn đi qua điểm dừng, trong đó mỗi chuỗi xảy ra một lần và chỉ một lần và toàn bộ tuyến đường có độ dài tối thiểu.

Bài tập 2. Trong một tấm có kích thước $7 \times 9$, chùm tia laser phải cắt qua các khe theo hướng chỉ bởi các mũi tên trên Hình 1 và đưa nó về vị trí ban đầu. Bài toán giảm thiểu tình trạng chạy nguội của đầu laser là bài toán nhân viên bán hàng lưu động. Viết ma trận khoảng cách cho nó. (Lưu ý rằng nó không đối xứng.)

⟦folio 13⟧

Từ Bài tập 2, chúng ta thấy rằng các “thành phố” trong bài toán của commuvozher có thể hoàn toàn không phải là thành phố, và “rastoyans” có thể không phải là rastoynya chút nào. Ví dụ: trong mục “khoảng cách” giữa hai thành phố, bạn có thể thử hoặc tiếp tục di chuyển giữa chúng. Trong trường hợp này, tổng chi phí của chuyến đi hoặc thời gian của chuyến đi sẽ được giảm thiểu tương ứng.

Hãy lấy một ví dụ khác về bài toán về trại. Trong quá trình xử lý trên máy nghiền, bộ phận này trải qua hoạt động $k$. Khi chuyển từ thao tác này sang thao tác khác, máy phải setup lại dẫn đến mất thời gian. Cần phải tìm ra thứ tự thực hiện mọi thao tác (với việc đưa máy về trạng thái ban đầu) sao cho tổng tổn thất là tối thiểu. Rõ ràng là ở đây chúng ta đang giải quyết vấn đề về cổ góp - với bảng thời gian bị mất khi xây dựng lại máy dưới dạng ma trận khoảng cách. “Thành phố” là trạng thái của máy sau nhiều hoạt động khác nhau.

Nhân viên bán hàng bài toán được lãnh đạo bởi bài toán lập kế hoạch sản xuất và thiết kế truyền thông tuyến tính (ví dụ: mạng điện thoại), bài toán vẽ ra lộ trình cho nhân viên bưu điện (bác sĩ, nhân viên điều khiển điện thoại trả tiền, v.v.) và thậm chí một số thiết kế máy tính bài toán.

Hoàn thành tìm kiếm

Vì vậy, trong mỗi bài toán commuvoger cụ thể, cần phải tìm hành trình ngắn nhất cho một ma trận khoảng cách nhất định. Có thể là tình cờ

| Số giao dịch | I | II | III | IV | V |
| :--- | :--- | :--- | :--- | :--- | :--- |
| I | — | 0 | 11 | 5 | 20 |
| II | 31 | — | 0 | 52 | 8 |
| III | 9 | 16 | — | 0 | 41 |
| IV | 64 | 31 | 61 | — | 0 |
| V | 0 | 93 | 19 | 7 | — |

điều này sẽ cực kỳ dễ thực hiện. Ví dụ: nếu tổn thất chuyển tải trong bài toán của máy nghiền được cho trong Bảng 2, thì rất có thể trình tự vận hành tối ưu là: $I \rightarrow II \rightarrow III \rightarrow IV \rightarrow V \rightarrow I$ (với tổng thời gian chuyển tải bằng 0).

Bài tập 3. Giải phương trình bài toán của Bài tập 2 nếu bạn biết rằng trong quá trình di chuyển khó khăn, đầu laser chỉ có thể di chuyển song song với các cạnh của tấm.

Tuy nhiên, thông thường nhất đối với các bảng khoảng cách cụ thể, lời giải không nổi bật. Và ngay cả khi ai đó cho chúng ta biết con đường nào là ngắn nhất, nó có thể khó khăn hơn khi chúng ta muốn kiểm tra xem điều này có thực sự đúng như vậy hay không.

Các nhà toán học không mấy quan tâm đến lời giải cụ thể bài toán nhân viên bán hàng, bao nhiêu là phổ biến lời giải tất cả những thứ này bài toán (hoặc ít nhất là tất cả bài toán nhân viên bán hàng tại $k \leq m$, Ở đâu $m$ - một số số cố định).

Tất nhiên, lưu ý rằng trong mỗi bài toán commuvoger cụ thể, bạn có thể thực hiện tất cả các tuyến đường. Do đó, bạn có thể tổ chức tìm kiếm đầy đủ tất cả các tuyến đường, tính toán độ dài của chúng và chọn tuyến đường ngắn nhất. Về nguyên tắc, việc tìm kiếm toàn diện như vậy là một phương pháp giao tiếp chung lời giải bài toán.

Tuy nhiên, chúng ta hãy nhớ đến Nevsky và Liteiny. Mặc dù họ phải vẽ một tuyến đường khép kín chỉ qua sáu thành phố nhưng họ không muốn đi qua hết 120 turii (tuy nhiên, họ không tự động nhận thấy rằng, do tính đối xứng của Bảng 1, chỉ có 60 turii có độ dài khác nhau). Trong trường hợp tổng quát, người đi lại phải chọn con đường ngắn nhất là $(k-1)$! khả năng của các tuyến đường. Con số này tăng rất nhanh khi $k$ tăng, và do đó phương pháp chỉ báo lời giải thực tế không áp dụng được cho các giá trị lớn của $k$. Do đó, tác giả biết một ví dụ trong đó máy tính M-220A dành 4 giờ 45 phút để thực hiện tìm kiếm trong bài toán cho một người lái xe đi lại ở mười thành phố $(k=10)$! Nhanh

⟦folio 15⟧

Các thí nghiệm đã chỉ ra rằng không cần sử dụng các thuộc tính cụ thể của từng thiết bị giao tiếp bài toán cụ thể, sẽ có một máy tính và các phương pháp lập trình tuyến tính số nguyên lời giải bài toán cho phép bạn chỉ xử lý với bài toán thiết bị giao tiếp nếu cần thiết, số lượng thành phố (không quá mười). Đồng thời, công trình gần đây nhất trong lĩnh vực này cho thấy rằng việc rút gọn quy hoạch tuyến tính số nguyên xuống bài toán có thể được sử dụng một cách hiệu quả khi kết hợp với một phương pháp giao tiếp lời giải bài toán khác - phương pháp nhánh và giới hạn.

Phương pháp phân nhánh và ràng buộc

Phương pháp giao tiếp lời giải bài toán tốt nhất hiện nay là phương pháp liệt kê giới hạn hoặc phương pháp phân nhánh và ràng buộc. Nó được sử dụng trong một số sửa đổi với hiệu quả khác nhau.

Tất nhiên, khi thực hiện một tìm kiếm hoàn chỉnh, chúng tôi có thể viết ra tất cả các chuyến tham quan lần lượt. Bạn có thể làm khác đi: vẽ một cây về những chuyến đi có thể thực hiện được. Đối với trường hợp của bốn thành phố, nó được thể hiện trong Hình 2. Trong các vòng tròn là số thành phố; Các mũi tên chỉ các chuyến đi. Rõ ràng là khi di chuyển đến cây chuyến đi, số lượng mũi tên giảm so với số lượng của chúng trong bản ghi của tất cả các tuyến đường (tại $k > 3$). Ví dụ, khi viết tất cả các tuyến đường liên tiếp, mũi tên I → II sẽ phải được vẽ hai lần. Nhưng chúng ta sẽ tiết kiệm được nhiều hơn nếu không xây dựng toàn bộ sơ đồ hành trình mà chỉ xây dựng một phần trong đó. Một cây bị cắt cụt như vậy được đặt tên, khác với cây của tất cả các chuyến đi do không có các nhánh không thể đưa ra lộ trình ngắn nhất và được xây dựng theo phiên bản của phương pháp nhánh và ràng buộc được trình bày bên dưới.

Chúng ta hãy mô tả trình tự các giai đoạn của một phương thức giao tiếp lời giải bài toán như vậy (sơ đồ luồng của thuật toán được mô tả được hiển thị trong Hình 3). Hoàn thành màn chơi, chuyển sang màn tiếp theo, trừ khi có hướng dẫn khác.

1. Chúng ta vẽ đỉnh gốc của cây (để định nghĩa, chúng ta sẽ giả sử rằng nó tương ứng với thành phố I). Chúng tôi chỉ định nó xếp hạng 0.

2. Chúng tôi phân nhánh từ bất kỳ đỉnh nào có số điểm tối thiểu (ban đầu là từ gốc). Điều này có nghĩa là chúng ta vẽ từ đỉnh đã chọn tất cả các mũi tên sẽ xuất phát từ đỉnh đó trong cây các chuyến đi có thể xảy ra và vẽ các đỉnh tương ứng của cây.

3. Chúng tôi gán cho mỗi đỉnh mới một điểm bằng độ dài của phần tuyến đường được mô tả bằng các mũi tên dẫn từ đỉnh gốc đến đỉnh này.

⟦folio 16⟧

Cơm. 3.

4. Nếu đạt được một đỉnh tương ứng với thành phố I thì chúng ta tìm thấy
Dim chiều dài G ngắn nhất thu được
các tour du lịch có sẵn cho đến thời điểm này. Nếu không,
đi đến giai đoạn 2.

5. Chúng tôi cắt bỏ tất cả các đỉnh mà việc phân nhánh chưa được thực hiện (các đỉnh cuối) và ước tính hệ số co-
trong đó không nhỏ hơn G. Điều này có nghĩa là việc phân nhánh từ các đỉnh như vậy sẽ không được thực hiện trong tương lai. Nếu không thì mọi chuyện đã kết thúc -
tất cả các đỉnh bị cắt bỏ, chuyển sang giai đoạn 2. Nếu tất cả, thì bài toán lời giải: chuyến tham quan tối ưu có độ dài Г và được khôi phục từ đỉnh cuối nơi thu được giá trị cuối cùng của Г (xem giai đoạn 4).

Giai đoạn 2 mô tả quy tắc phân nhánh, giai đoạn 3 mô tả các quy trình đánh giá, giai đoạn 4 mô tả các giới hạn và giai đoạn 5 mô tả các quy trình cắt tỉa.

Chúng ta hãy giải phương pháp rẽ nhánh và ràng buộc bài toán của người bán hàng du lịch với các khoảng cách cho trong Bảng 3.

Lời giải được hiển thị trong Hình 4. Per-
Bốn nhánh cuối cùng được hiển thị bằng mũi tên màu xanh lá cây. Gán giá trị cho G

G=8 và cắt hai đỉnh. Nhánh thứ năm tương ứng với mũi tên màu xanh. Trong số hai đỉnh cuối có điểm tối thiểu là 4, chúng tôi đã chọn đỉnh ở xa gốc hơn (với hy vọng đạt được một vòng khác nhanh hơn và giảm giá trị của G). Các nhánh sau được đánh dấu bằng mũi tên màu đỏ. Teleri G=5 và chúng tôi cắt bỏ tất cả các đỉnh cuối khác. Giải pháp là vòng I→II→III→IV→I có độ dài 5.

Phiên bản được mô tả của phương pháp nhánh và ràng buộc cho phép bạn giải bài toán nhân viên bán hàng du lịch bài toán với k<20 trên máy tính. Rõ ràng là nó luôn dẫn đến chuyến đi ngắn nhất hoặc nó sử dụng một cây có thể

Bảng 3

N I II III IV

I — 4 0 9

II 5 — 0 3

III 6 4 — 1

IV 0 2 6 —

⟦folio 17⟧

các chuyến đi, và chỉ những nhánh đó bị loại bỏ mà rõ ràng là không thể cung cấp các chuyến tham quan ngắn hơn những chuyến đã được tìm thấy.

Bạn có thể đối phó với một trăm thành phố!

Năm 1963, một phiên bản rất thành công của phương pháp nhánh và giới hạn đã được xuất bản, trong đó, khi tính toán ước tính, một con số đã được thêm vào độ dài của phần tuyến đường đã hoàn thành, ước tính độ dài của phần còn lại. Quy tắc phân nhánh trong phương pháp này (tác giả của nó là Katta Murthy, một nhà toán học người Mỹ gốc Ấn Độ) là với mỗi nhánh, hai nhánh mới được hình thành *). Phương pháp của Murthy giúp người ta có thể giải được bài toán nhân viên bán hàng du lịch với giá $k \leq 40$ trên máy tính trong một thời gian tương đối ngắn.

Sau đó, một phiên bản khác của phương pháp rẽ nhánh và ràng buộc đã được phát triển (phương pháp Eastman-Shapiro). Sử dụng phương pháp này, có thể giải được một số nhân viên bán hàng du lịch bài toán tại $k \leq 70$. Sự phát triển hơn nữa của phương pháp Eastman-Shapiro giúp có thể tăng quy mô bài toán thành phố được giải quyết trên máy tính lên 100-120 thành phố.

Phương pháp Eastman-Shapiro để tính toán ước tính sử dụng thực tế là có các phương pháp máy hiệu quả lời giải được gọi là bài toán phép gán *), liên quan chặt chẽ đến bài toán nhân viên bán hàng lưu động. Về nội dung, bài toán về việc bổ nhiệm được xây dựng như sau: có $k$ người và $k$ chức vụ, đã biết ma trận các điểm không phù hợp giữa người và chức vụ. Cần phải tìm cách phân công công nhân vào các vị trí sao cho tổng số điểm không nhất quán là nhỏ nhất. Ở đây, ma trận điểm đóng vai trò tương tự như ma trận khoảng cách trong nhân viên bán hàng du lịch bài toán. Và các cuộc hẹn, như pozedki, có thể được viết dưới dạng $x \rightarrow y$. Điểm khác biệt duy nhất là các điểm đến không nhất thiết phải hình thành một lộ trình khép kín (tour). Ví dụ, có thể bổ nhiệm như vậy $I \rightarrow V \rightarrow I$, $II \rightarrow II$, $III \rightarrow IV \rightarrow VI \rightarrow III$ (điều này có nghĩa là người đầu tiên sẽ được bổ nhiệm vào vị trí thứ năm, người thứ năm lên vị trí thứ nhất, người thứ hai lên vị trí thứ hai, người thứ ba lên vị trí thứ tư, v.v.).

Vì vậy, mỗi vòng có thể coi là một cuộc hẹn (nhưng việc hẹn $k$ người

*) Để biết mô tả về phương pháp Murthy, chẳng hạn, hãy xem trong tài liệu quảng cáo của V. I. Mudrov “Vấn đề của người bán hàng du lịch”, M., “Kiến thức”, 1969.

*) Khoảng bài toán cuộc hẹn đã được M. I. Reitman mô tả trong bài viết “Giao thông vận tải bài toán” («Kvant», 1974, số 7).

Cơm. 4.

⟦folio 18⟧

Hóa ra, trung bình nó chỉ là một chuyến tham quan trong một trong các trường hợp $k$: xét cho cùng, có ($k-1$!) các chuyến tham quan và tổng số $k$-bài tập bằng $k!$. Do đó, tổng điểm cho phép gán $k$ tối ưu không vượt quá độ dài của loại tối ưu. Và, như chúng tôi đã lưu ý, máy tính tìm thấy số điểm này tương đối nhanh chóng. Đây là những gì được sử dụng làm ước tính trong phương pháp Eastman-Shapiro, trong đó không phải cây hành động được xây dựng mà là một cây hoàn toàn khác, các đỉnh của chúng là phụ trợ bài toán về các bài tập (một ví dụ về cây như vậy được hiển thị trong Hình 5).

Trong phương pháp này, các bài tập được quyết định trước tiên bài toán với ma trận khoảng cách bài toán của người giao tiếp làm ma trận tính điểm. Nó tương ứng với đỉnh gốc của cây. Tổng số điểm cho phép gán tối ưu được coi là điểm của nút gốc (và bộ giao tiếp bài toán ban đầu). Nếu giải pháp là một chuyến tham quan thì bài toán của người giao tiếp đã được giải quyết: chuyến tham quan tìm được là tối ưu. Nếu phép gán $k$ bao gồm một số chuỗi tuần hoàn, ví dụ: $I \rightarrow III \rightarrow VII \rightarrow V \rightarrow I$, $IV \rightarrow VI \rightarrow II \rightarrow IV$, thì vì loại tối ưu không thể có “chu trình phụ” nên tất cả các chuỗi tuần hoàn này phải bị phá vỡ. Trong phương pháp Eastman-Shapiro, điều này được thực hiện trong quá trình giới thiệu và một - chuỗi nhiệm vụ ngắn nhất - luôn hoạt động, để sau đó quyết định số lượng nhiệm vụ bài toán mới ít hơn.

Trong ví dụ của chúng tôi, đó là trường hợp thứ hai; nó bao gồm ba thành phố: $II$, $IV$ và $VI$. Chúng tôi áp đặt các lệnh cấm đối với các vị trí $IV \rightarrow VI$, $VI \rightarrow II$ và $II \rightarrow IV$, sau đó chúng tôi quyết định ba phép gán bài toán mới với các khay ma trận điểm mới thu được từ ma trận tương ứng với đỉnh gốc: ở phần đầu tiên là phần tử $c_{46}$, ở phần thứ hai - phần tử $c_{62}$ và ở phần thứ ba - phần tử $c_{24}$ được thay thế bằng biểu tượng $\infty$, chúng tôi sẽ giới thiệu một cách có ý nghĩa việc cấm tạo dáng tương ứng (thông qua $c_{ab}$ chúng tôi lại chỉ ra khoảng cách giữa các thành phố $a$ và $b$). Nếu có các chuyến tham quan trong số lời giải thì $\Gamma$ được coi là bằng độ dài của chuyến đi ngắn nhất trong số đó. Bài toán với số điểm không thay đổi hơn $\Gamma$ sẽ bị “cắt”. Phần giới thiệu tiếp theo được thực hiện cho một trong số bài toán này, bài tập $k$ không phải là một vòng và điểm (tổng số điểm chênh lệch) hóa ra là nhỏ nhất.

Chúng ta hãy nhận xét về quá trình lời giải, sơ đồ của quá trình này được hiển thị trong Hình 5.

Hai lần giới thiệu đã được thực hiện và sáu cuộc hẹn bài toán đã được quyết định. Giải pháp cho bài toán 4 hóa ra là một chu trình. Kể từ thời điểm này trở đi, $\Gamma = 44$ và bài toán với số điểm 45 và 44 sẽ bị loại bỏ.

lời giải bài toán 3 bao gồm phép gán $IV \rightarrow V \rightarrow IV$. Lần tiêm thứ hai dẫn đến hai bài toán mới: 5 và 6. Lời giải bài toán 5 là một chu kỳ có độ dài 42. Giá trị mới $\Gamma$ này cho phép cắt.

Phương pháp heuristic

Nếu không thể giải chính xác bài toán của người giao tiếp thì sẽ cố gắng giải gần đúng. Trong trường hợp này, tuyến đường được tìm kiếm tương đối khác một chút so với tuyến đường ngắn nhất. Các phương pháp tìm đường như vậy thường là gần đúng, dưới mức tối ưu hoặc theo kinh nghiệm.

Ví dụ: dưới mức tối ưu là phương pháp “đi tới điểm gần nhất”, tức là đến điểm gần nhất trong số chưa được di chuyển.

⟦folio 19⟧

sinh con Dễ dàng nhận thấy phương pháp này không chính xác khi sử dụng ma trận khoảng cách đơn giản sau (xem Bảng 4).

Đối với cô ấy, thủ tục “đi đến gần” đưa ra một tuyến đường I→III→II→I có độ dài 10, trong khi thủ tục nonlenian “đi đến xa” dẫn đến một chuyến tham quan I→II→III→I có độ dài 8. Vì giao tiếp hiện không có tuyến đường nào khác, ví dụ này có nghĩa là phương pháp heuristic của chúng tôi đôi khi có thể đưa ra ngay cả những chuyến đi phẳng nhất.

Tuy nhiên, mục tiêu “đi đến gần nhất” (và các phương pháp phỏng đoán khác) thường được sử dụng trong thực tế - đặc biệt khi lời giải bài toán giao tiếp với một số lượng rất lớn các thành phố. Điều này được thực hiện theo một số nguyên tắc. Thứ nhất, phương pháp này hoạt động khá nhanh. Thứ hai, thực tế cho thấy rằng khi $k$ tăng lên, phương pháp “đi đến nơi gần nhất” ngày càng tạo ra các chuyến tham quan có độ dài hơi khác so với độ dài của chuyến tham quan ngắn nhất (và đôi khi trùng với nó). Và cuối cùng, một tình huống chung cho tất cả các phương pháp heuristic: trong nhiều bài toán thực tế, chúng ta không quan tâm đến giá trị chính xác lời giải mà chỉ quan tâm đến việc xấp xỉ nó đủ tốt (xét cho cùng, đôi khi khoảng cách giữa các thành phố không được xác định khá chính xác). Ngoài ra, độ chính xác của thuật toán “đi đến hàng xóm của bạn” tăng lên (nhưng cường độ lao động cũng tăng lên) nếu trong quá trình hoạt động của nó, $k$ vòng được xây dựng, vòng đầu tiên bắt đầu được xây dựng từ thành phố đầu tiên, vòng thứ hai từ thành phố thứ hai, v.v.; Một số chuyến tham quan này có thể khác nhau và cuối cùng chuyến tham quan ngắn nhất sẽ được chọn.

Đối với nhiệm vụ của nhân viên bán hàng du lịch, nhiều phương pháp heuristic hiệu quả đã được tạo ra. Đặc biệt, các phương pháp rẽ nhánh và ràng buộc đã được chứng minh là khá tốt; công việc của họ dừng lại ở một trong các loại được tìm thấy (không nhất thiết phải là loại tối ưu). Vì vậy, vào năm 1976, hai nhà toán học người Nhật đã giải được bài toán người bán hàng du lịch cho 300 thành phố trên máy tính NITAC-8800 bài toán. Đồng thời, lời giải được tìm thấy trong 2 phút, chênh lệch 0,2% so với mức tối ưu.

đất nước tuyệt vời

Hãy tưởng tượng rằng A. Nevsky và B. Liteiny, vốn đã quen thuộc với chúng ta, quyết định đi du lịch vòng quanh một đất nước nhỏ (hãy gọi nó là Constantius). Sau khi đến thủ đô của nó và tìm thấy bảy thành phố thú vị nhất của Constantia trong hành trình của mình, họ lên kế hoạch cho chuyến tàu của mình. Lần này, khoảng cách giữa các thành phố không chỉ lớn (xem Bảng 5). Do đó, những người bạn quyết định không theo đuổi mức tối thiểu mà tính toán độ dài của một số chuyến tham quan được thực hiện ngẫu nhiên và chọn chuyến đi ngắn nhất trong số đó (quy trình này cũng là một phương pháp dưới mức tối ưu, được gọi là *phương pháp Monme-Karlo*). Sự lựa chọn rơi vào các chuyến tham quan sau:

I→II→III→IV→V→VI→VII→VIII→I;
I→III→VII→II→IV→VI→VIII→I;
I→IV→VII→II→V→VIII→I.

Chúng tôi đã tính toán chiều dài của chúng; Hóa ra cả ba chuyến tham quan đều dài 794 km! Trở nên quan tâm, chúng tôi

⟦folio 20⟧

các anh hùng đã phân tích thêm mười tuyến đường. Mỗi chiếc dài 794 km! Bạn có thể tưởng tượng những anh hùng của chúng ta đã xấu hổ như thế nào. Nhưng sự ngạc nhiên của họ sẽ còn lớn hơn nếu họ biết rằng với một ma trận khoảng cách nhất định, tất cả các chuyến đi nói chung đều có độ dài như nhau.

Tại sao? Việc mở quan tài rất đơn giản: tất cả các số 5 có được bằng cách cộng các số 48, 55, 66, 38, 61, 42, 50 và 37. Ví dụ: ở dòng thứ ba, các tổng là 66+48=114, 66+55=121, 0, 66+38=104, v.v. thời gian và chỉ một số từ mỗi hàng và từ mỗi cột của Bảng 5, thì kết quả là độ dài của bất kỳ loại nào sẽ bằng hai lần tổng của các số dự định (tổng của tám số dự định là 397 và 794 = 397 × 2).

Câu hỏi đặt ra là: không thể mô tả tất cả các ma trận khoảng cách trong đó hai vòng bất kỳ có cùng độ dài? Hóa ra là có thể: đối với bất kỳ ma trận nào như vậy, cần phải tìm các số $a_1, a_2, \dots, a_k$ và các số $b_1, b_2, \dots, b_k$ sao cho khoảng cách $c_{xy}$ từ thành phố $x$ đến thành phố $y$ ($x \neq y$) sẽ bằng tổng $a_x + b_y$.

Chúng ta hãy chứng minh định lý này cho trường hợp ba thành phố.

Gọi $c$ là độ dài của mỗi vòng trong hai vòng:
$$c = c_{12} + c_{23} + c_{31} = c_{13} + c_{21} + c_{32}.$$
Hãy để chúng tôi biểu thị $c_{31}$ và $c_{32}$ từ các mối quan hệ này:
$$c_{31} = c - c_{12} - c_{23},$$
$$c_{32} = c - c_{13} - c_{21}.$$
Ta cần giải hệ phương trình
$$x_1 + y_2 = c_{12}, x_1 + y_3 = c_{13},$$
$$x_2 + y_1 = c_{21}, x_2 + y_3 = c_{23},$$
$$x_3 + y_1 = c - c_{12} - c_{23},$$
$$x_3 + y_2 = c - c_{13} - c_{21}.$$
Chúng tôi cung cấp cho ẩn số $y_3$ một giá trị tùy ý $d$. Khi đó từ năm phương trình đầu tiên người ta tìm thấy rằng $x_1 = c_{13} - d, x_2 = c_{23} - d, y_2 = c_{12} - c_{13} + d, y_1 = c_{21} - c_{23} + d,$
$$x_3 = c - c_{12} - c_{23} - c_{21} + c_{23} - d = c - d - c_{12} - c_{21}.$$
Trong trường hợp này, phương trình thứ sáu cũng được thỏa mãn. Đặt $d = 0$, chúng ta nhận được một tập hợp các số $a_1 = c_{13}, a_2 = c_{23}, a_3 = c - c_{12} - c_{21}, b_1 = c_{21} - c_{23}, b_2 = c_{12} - c_{13}, b_3 = 0$ có thuộc tính chúng ta cần.

Định lý được đưa ra ở trên khá điển hình cho những nghiên cứu lý thuyết về công việc của một người bán hàng lưu động. Các trường hợp đặc biệt khác nhau đóng một vai trò quan trọng trong đó. (Sự trùng hợp về độ dài của tất cả các chuyến tham quan cũng là một trường hợp đặc biệt. Tuy nhiên, trọng số hẹp.) Đối với các trường hợp đặc biệt, đôi khi không chỉ khó xây dựng một phương pháp làm việc nhanh (trong trường hợp này chúng ta nói về một trường hợp có thể giải được), mà còn tìm ra độ dài mà một chuyến tham quan tối ưu có thể có.

Bạn đọc có thể tiếp tục khám phá những trường hợp giải được bài toán của người bán hàng lưu động bằng cách giải bài toán gợi ý dưới đây. Trong một số trường hợp, họ quyết định du hành trên một bàn cờ, nơi các quân cờ đóng vai trò như một người bán hàng lưu động. Trong trường hợp này, chúng ta sẽ không nói về kiểu người bán hàng rong mà nói về kiểu quân mã, quân xe, v.v. Hành trình của quân cờ tiếp tục một lần dọc theo tất cả các ô của bàn cờ và kết thúc bằng việc quay trở lại ô ban đầu.

Bài tập
1. Các thành phố nằm ở các đỉnh của một đa giác lồi. Chứng minh rằng độ dài của loại tối ưu bằng chu vi của đa giác.
2. Nhiệm vụ của nhân viên bán hàng du lịch bài toán về con đường ngắn nhất cho một du khách xuất phát từ điểm 1, đi theo điểm 2, 3, ..., $k-1$ và rời khỏi đất nước từ điểm $k$? Câu hỏi tương tự dành cho bài toán về việc giảm thiểu đường đi của trình nhắn tin, được gửi từ điểm 1 đến điểm 2, 3, ..., $k$. Thông tin này có áp dụng được cho bài toán về những kẻ phá hoại, những người để làm nổ tung các vật thể nằm ở các điểm 1, 2, ..., $k$, hãy lên kế hoạch cho địa điểm gạn và con đường ngắn nhất qua tất cả các điểm?
3. Có 30 thành phố trên máy bay. Tọa độ của chúng: $y = 0, 1, 2$ tại $x = 0; y = 0, 1, 2, 4, 5, 6$ tại $x = 1; y = 1, 2, 3, 4, 6, 7, 8$ tại $x = 2; y = 0, 1, 3, 4, 6, 7, 8$ tại $x = 3; y = 0, 1, 2, 3, 4, 5, 6$ tại $x = 4$. Giải quyết bài toán nhân viên bán hàng du lịch. Chứng minh rằng kết quả chuyến tham quan là tối ưu.
4. Ở bàn cờ có kích thước bao nhiêu thì quân Xe bật lên? Chuyến tham quan của một quân xe suy yếu chỉ di chuyển đến các ô lân cận?
5. Trên một bàn cờ có số ô vuông lẻ, người ta cắt ra một ô vuông. Đối với những phân rã nào của một hình vuông bị cắt thì tồn tại một chuyến đi xe bị suy yếu?
6. Tìm lượt của hiệp sĩ trên một "bảng" không gian có dạng hình chữ nhật song song có kích thước $3 \times 4 \times 6$. “Cánh đồng” hiện được coi là 72 khối của một đơn vị thể tích, trên đó “bảng” của chúng ta được phân chia một cách tự nhiên.
7. Cho các số $k$ và $m$. Cách xây dựng ma trận khoảng cách cho một nhân viên bán hàng du lịch bài toán với $k$ thành phố có giải pháp là một chuyến tham quan có độ dài $km?$
