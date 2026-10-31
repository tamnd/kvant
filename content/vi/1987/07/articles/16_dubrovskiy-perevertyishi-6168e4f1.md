---
id: 1987-7-dubrovskiy-perevertyishi-6168e4f1
issue: kvant_1987_7
year: 1987
number: "7"
title: Thay Đổi
authors:
  - Дубровский В. Н.
rubric: igry-i-golovolomki
rubric_sub: Игры и головоломки
page_first: 56
page_last: 59
page_labels: 54, 55, 57
tag: 3PHZ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 7539f8dfee00df3b1d06f4b7f2a94c3b72f2fec1c5f8947fc224f1489bd65042
prompt_sha256: draft-1
translated_from: content/ru/1987/07/articles/16_dubrovskiy-perevertyishi-6168e4f1.md
source_content_sha256: 421ff9818d4d2dc3ed8571fa869daa823fb2860fd70e52f35dc3e3390f3ac490
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 54⟧

Thay đổi

Ứng viên Khoa học Vật lý và Toán học
V. N. DUBROVSKY

Tiết lộ bí mật của câu đố lời giải cũng không trung thực như kể cho một người hâm mộ cuồng nhiệt về một trận bóng đá trước khi truyền hình phát sóng vào ngày hôm sau. Vì vậy, trong cuốn sách tô màu của chúng tôi về hai câu đố “đảo ngược”, quen thuộc với độc giả từ trang bìa số 1 và số 2 «Kvant» năm nay, sẽ có nhiều câu hỏi hơn đáp số. Nhưng trước khi hỏi và trả lời các câu hỏi, hãy để chúng tôi nhắc bạn cách hoạt động của những câu đố này.

Trong một câu đố, 8 khối có kích thước 1x1x1, có sáu màu giống hệt nhau, được đặt cạnh nhau trong một hộp vuông có kích thước 3x3 (hình 1). Trong một câu đố khác, cùng với các hình khối, 23 paramidics giống hệt nhau (sổ ghi chép thông thường) được lấy với các đỉnh được sơn bốn màu (hình 2,a), được đặt trong một hộp có hình lục giác đều với các cạnh lớn gấp đôi các cạnh của paramidiki (hình 2,b). Trong cả hai câu đố, một nơi trống - một "lỗ", cho phép bạn sắp xếp lại các phần tử (hình khối và nhân viên y tế) bằng cách lăn chúng qua một cạnh. Bài toán chúng ta sẽ thảo luận có âm thanh khác nhau đối với hai câu đố. Paramaidiki phải được học cách chuyển sang vị trí “đúng” hoặc “ban đầu” được hiển thị trong hình 2, b, sau khi nó bị phá hủy do lăn tùy ý. Các hình khối có nhiều vị trí chính xác (những vị trí này được nêu rõ từ hình 1; kiểm tra xem có 24 vị trí chính xác); cần phải chuyển đổi cái này thành cái khác. Nhưng cả hai bài toán này đều là trường hợp đặc biệt của câu đố “hoán vị” chung bài toán cho tất cả các câu đố “hoán vị”: đối với hai vị trí của phần tử bất kỳ, hãy tìm hiểu xem cái này có dịch sang cái kia hay không, và nếu vậy thì bằng cách nào.

Hình khối

Chúng ta hãy thử nghĩ ra các thao tác có thể xoay khối lập phương trong khi vẫn để nó đúng vị trí - sau đó có thể xoay từng khối một. Chúng ta hãy chỉ đặt một khối lập phương vào hộp và lăn nó dọc theo hình vuông 2x2 xung quanh một trong các đỉnh của đáy A (hình 3). Khi nó trở về vị trí của nó, chúng ta sẽ thấy rằng nó đã quay tương ứng với vị trí ban đầu 120° gần đường chéo xuất hiện từ đỉnh A. Tương tự như vậy, bạn có thể lăn 3 khối quanh hình vuông - toàn bộ: sau bốn lần di chuyển, lỗ sẽ trở về vị trí của nó và các khối tuần hoàn sẽ được sắp xếp lại (hình 4) - thao tác này, khi việc sắp xếp lại xảy ra ngược chiều kim đồng hồ quanh điểm A, được ký hiệu là C_A. Rõ ràng là thao tác C^3_A (C_A lặp lại ba lần) sẽ trả cả 3 khối về vị trí ban đầu, mỗi khối được quay 120° quanh đường chéo của nó phát ra từ A (xem hình 4). Để xoay các khối này theo hướng ngược lại, bạn cần thực hiện thao tác ngược lại C^-3_A =

⟦folio 55⟧

$$= \left( C_A^{-1} \right)^3,$$
trong đó $C_A^{-1}$ là đường đi theo chiều kim đồng hồ của lỗ xung quanh điểm $A$.

Vì vậy, chúng ta có thể xoay các hình khối ở vị trí của chúng, nhưng cho đến nay chỉ xoay theo nhóm 3. Bây giờ không khó để đưa ra các thao tác chỉ xoay một khối. Một trường có kích thước $3 \times 2$ ô là đủ cho chúng. Đặt ô tự do ở trên cùng (hình 5), ô này thuộc hai ô vuông $2 \times 2$ có ​​tâm $A$ và $B$. Thao tác $C_A$ không ảnh hưởng đến hai khối bên phải và thao tác $C_B$ không ảnh hưởng đến hai khối bên trái, do đó, các thao tác $R_1 = C_A^3 C_B^3 C_A^{-3} C_B^{-3}, R_2 = C_A^{-3} C_B^3 \times C_A^3 C_B^{-3}$) và các thao tác tương tự (xem bài toán 1) thường xuyên để 4 khối bên ngoài này bất động; khối thứ năm (hãy gọi nó là “cạnh”), như bạn có thể kiểm tra, quay trong cả hai trường hợp theo $180^\circ$: với $R_1$ - quanh một trục song song với $AB$, với $R_2$ - quanh một trục “ngang” vuông góc với $AB$. Một phép toán có dạng $[X, Y] = XYX^{-1}Y^{-1}$ được gọi là giao hoán của các phép toán $X$ và $Y$. Công tắc tỏ ra rất hữu ích trong tất cả các câu đố hoán đổi; chẳng hạn, có các thuật toán để giải khối Rubik, hoàn toàn dựa trên các bộ chuyển mạch (xem bài viết của V. và S. Zalgallerov “Khối bản lề Hungary” trong «Kvant» Số 12 năm 1980).

Bài tập
1. Xem xét tất cả các công tắc hoạt động có thể có $C_A^{\pm 3}, C_B^{\pm 3}$. Chứng tỏ rằng chúng đều hoạt động như $R_1$ hoặc $R_2$ hoặc giống như $R_1 R_2$ (xoay khối lập phương bằng $180^\circ$ quanh một trục thẳng đứng).

2. Chứng minh rằng có 24 cách đặt một hình lập phương vào một hình vuông cho trước; trong số này, chỉ có thể lấy được 12 cái từ vị trí ban đầu bằng cách lăn dọc theo một tuyến đường kín, và trong số 12 cái này chỉ có được 4 cái

*) Thứ tự thực hiện từ trái qua phải; ví dụ: đối với $R_1 = C_A^3 C_B^3 C_A^{-3} C_B^{-3}$, thao tác $C_A^3$ được thực hiện trước, sau đó là $C_B^3, C_A^{-3}$ và cuối cùng là $C_B^{-3}$.

Hình 3.

Hình 4. Mũi tên màu xanh biểu thị chuyển động của cốc trong quá trình vận hành $C_A$, mũi tên màu đỏ biểu thị chuyển động quay của cốc trong quá trình vận hành $C_A^3$.

Hình 5.

dưới tác dụng của cổ góp $[X, Y]$, trong đó $X$ và $Y$ là các phép toán tùy ý đưa khối về vị trí ban đầu. Đưa ra chuỗi chuyển động ngắn nhất khi cổ góp thực hiện các thao tác $X$ và $Y$. Công tắc tỏ ra rất hữu ích trong tất cả các câu đố hoán đổi; chẳng hạn, có các thuật toán để giải khối Rubik, hoàn toàn dựa trên các giao tử (xem bài viết của V. và S. Zalgaller “Khối bản lề Hungary” trong «Kvant» Số 12 năm 1980).

Như vậy, chúng ta đã học được cách xoay 4 khối lập phương “cạnh”. Để xoay khối góc, chỉ cần đặt nó vào vị trí của cạnh bên, áp dụng thao tác $R_1$ hoặc $R_2$, sau đó trả lại: ví dụ (xem hình 5), thao tác $R_2' = C_A R_2 C_A^{-1} = C_A^{-2} C_B^3 C_A^{-3} C_B^{-3} C_A^{-1}$ xoay khối phía dưới bên trái một khoảng $180^\circ$ quanh trục “ngang”, hình chữ nhật $AB$ (một thao tác tương tự đối với phía dưới bên phải tạo ra tự mình lập khối).

Bây giờ chúng ta giảm tất cả các hình khối, nhưng có lẽ không phải theo cách ngắn nhất (số bước di chuyển chúng ta có là 8·48=384): xét cho cùng, mỗi khối được xoay riêng biệt và cũng giữ nguyên vị trí, điều này không cần thiết*).

*) Đối với trường hợp khoảng trống không nằm ở giữa mà ở phía dưới bên trái, A.V. MoveULEV do lời giải phát minh trong 100 lần di chuyển và ở đây các hình khối được xoay không phải theo $180^\circ$ mà theo $90^\circ$: $JH^2 \Pi B^2 \Pi H(\Pi B J H)^3 H J B^2 \Pi H(J B J H)^2 H J B J H^2 B^2 J^2 H^2 J B J H^2 H J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2$.

*) Đối với trường hợp khoảng trống không nằm ở giữa mà ở phía dưới bên trái, A.V. MoveULEV do lời giải phát minh trong 100 lần di chuyển và ở đây các hình khối được xoay không phải theo $180^\circ$ mà theo $90^\circ$: $JH^2 \Pi B^2 \Pi H(\Pi B J H)^3 H J B^2 \Pi H(J B J H)^2 H J B J H^2 B^2 J^2 H^2 J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2 J^2 H J B J H^2$.

Hình 5.

⟦folio 57⟧

Jan Heveli

(Để bắt đầu, xem trang 53)

hướng dẫn thiên văn. Vụ cháy cũng thiêu rụi toàn bộ tài sản của ông. Nhưng anh đã dũng cảm chịu đựng nỗi bất hạnh này và ngay lần gặp quả báo đầu tiên, anh đã tiếp tục nghiên cứu.

Ngày nay chúng ta biết nhiều về Mặt trăng hơn thời Hevelius. Hình nổi ở mặt sau của nó đã được chụp ảnh và nghiên cứu chi tiết. Tàu vũ trụ đã kiểm tra bề mặt của nó và mang về cho chúng tôi mẫu đất tia. Nhiều phi hành gia đã đến Mặt trăng.

Trên trang thứ hai của trang bìa có in một mảnh bản đồ Mặt Trăng, trong đó mô tả một phần mặt sau tiếp giáp với Biển Mátxcơva (đường kính của biển này là 460 km). Nó được phát hiện lần đầu tiên trong các bức ảnh do trạm quốc tế tự động Luna 3 của Liên Xô chụp vào năm 1959. Năm 1961, Liên minh Thiên văn Quốc tế đã phê duyệt mười tám vật thể được đặt tên ở phía xa của Mặt trăng và những vật thể ở giữa - Biển Moscow. Bên dưới chúng, thậm chí nhiều patiscot hơn đã được thêm vào, được gọi là chi tiết về bức phù điêu mặt trăng ở phía xa của Mặt trăng. Liên minh Thiên văn Quốc tế đã phê duyệt các vật thể được đặt tên ở phía xa của Mặt trăng. Liên minh Thiên văn Quốc tế đã phê duyệt các vật thể được đặt tên ở phía xa của Mặt trăng và các chi tiết kỹ thuật của khoa học và công nghệ - Lomonosov, Tsiolkovsky, Korolev, Lebedev, Mandelstam, Kurchatov, Artsimovich, Pasteur, Curie, Fermi và nhiều người khác. Danh pháp bắn cung cũng bao gồm tên của các phi hành gia đã chết - Komarov, Volkov, Dobrovolsky, Patsaev, Grissom, White, Chaffee. Ở vùng lân cận Biển Moscow có những miệng núi lửa được đặt theo tên của các phi hành gia Liên Xô Titov, Nikolaev, Tereshkova, Belyaev, Leonarov, Shatalov, Feoktistov. Chúng có thể nhìn thấy rõ ràng trên mảnh bản đồ mặt trăng ở trang thứ hai của trang bìa. Trong khu vực lòng chảo Apollo và Biển yên bình, sáu miệng núi lửa mang tên các phi hành gia người Mỹ - những người tham gia chuyến thám hiểm mặt trăng. Đây là các miệng hố Armstrong, Aldin, Collins, Anders, Borman và Lovell.

Zh. F. Rodionova, V. A. Leshkovtsev
