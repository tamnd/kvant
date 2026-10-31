---
id: 1989-6-kotkin-gaz-bilyardnyih-sharov-3b9c2cb1
issue: kvant_1989_6
year: 1989
number: "6"
title: Khí bóng bi-a
authors:
  - Коткин Г. Л.
rubric: osnovnye-stati
page_first: 4
page_last: 7
page_labels: 2-5
tag: Q010
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 789934dd4a03755f72e26260b321f9bfe1de0ca3f1fb627047f8a5fec1ffb756
prompt_sha256: draft-1
translated_from: content/ru/1989/06/articles/03_kotkin-gaz-bilyardnyih-sharov-3b9c2cb1.md
source_content_sha256: 89fb66d221aab4242dc9005cbcbd24d06aa13229086169e8850612d892685fec
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

Trong số rất nhiều ứng dụng của máy tính trong khoa học và công nghệ, một trong những ứng dụng quan trọng và phổ biến nhất là mô hình hóa. Các mô hình máy tính về máy bay và dòng hải lưu, chuyển động của hành tinh và quan hệ kinh tế giữa các quốc gia sẽ được tạo ra...

Bài viết này sẽ thảo luận về một trong những mô hình khí đơn giản nhất. Đây là “bàn bida lý tưởng”: những quả bóng hoàn toàn nhẵn và đàn hồi đóng vai trò phân tử khí, các cạnh của bàn bida đóng vai trò thành bình, mặt bàn nhẵn tuyệt đối. Một bàn bida lý tưởng như vậy không tồn tại, nhưng bạn có thể “tạo ra” nó bằng máy tính và quan sát “tuổi thọ” của các quả bóng trên màn hình hiển thị đồ họa.

Có lẽ đối với bạn, “bàn bida lý tưởng” dường như chỉ là một mô hình khí rất đơn giản. Về nguyên tắc, trên máy tính, có thể “xây dựng” một mô hình thực tế hơn - chuyển động theo chuyển động của các quả bóng trong không gian chứ không phải trên mặt phẳng, giới thiệu sự tương tác của các quả bóng-phân tử, v.v. Tuy nhiên, “bi-a” là đối tượng không chỉ dành cho giáo dục, học sinh mà còn cả nghiên cứu khoa học máy chủ.

Rõ ràng là chuyển động của những quả bóng lý tưởng hoàn toàn được xác định bởi các định luật cơ học. Trong khi đó, chuyển động của các bộ phận tạo nên chất khí có thể coi là hỗn loạn, ngẫu nhiên*).

Trong bài viết này, chúng tôi sẽ mô tả các thí nghiệm với mô hình “bàn bida lý tưởng”, cho phép chúng tôi quan sát chuyển động trở nên kỳ lạ như thế nào và cố gắng tìm hiểu lý do tại sao.

*) Bức tranh về sự xuất hiện “xaosa phân tử” trong khí cầu được nhà vật lý Liên Xô N. S. Krylov (1950) nghiên cứu. Nhà toán học Liên Xô Ya. G. Sinai đã thực hiện một nghiên cứu tương tự ở mức độ chặt chẽ khiến các nhà toán học hài lòng (1963). Có rất nhiều công trình khoa học sử dụng mô hình máy tính “khí bóng”.

Hình 1.

⟦folio 3⟧

chà nó vào tường) - đây sẽ là dữ liệu ban đầu mới - và chúng tôi sẽ lặp lại phép tính.

Chúng ta sẽ đặt vị trí của các quả bóng bằng cách sử dụng tọa độ Descartes của tâm của chúng và vận tốc bằng cách sử dụng hình chiếu của chúng trên cùng một trục (hình 1):

$$\vec{r} = (x, y), \quad \vec{v} = (v_x, v_y).$$

Các công thức tính toán hóa ra khá đơn giản. Cho trục Y trùng với cạnh trái của bàn bida. Khi đó thời gian trước khi quả bóng va chạm với bên này là

$$t = -(x-a)/v_x \quad (a \text{ — радиус шара}),$$

và va chạm chỉ xảy ra nếu $v_x < 0$. Giả sử va chạm này là lời giải. Trong khi va chạm, hình chiếu $v_y$ không thay đổi và hình chiếu $v_x$ đổi dấu:

$$v_x \rightarrow -v_x, \quad v_y \rightarrow v_y.$$

Di chuyển từng quả bóng theo thời gian $t$ —

$$\vec{r}_{it} = \vec{r}_i + \vec{v}_i t,$$

tức là $x_{it} = x_i + v_{ix} t, \quad y_{it} = y_i + v_{iy} t$. Các phép tính cho trường hợp bóng va chạm tuy phức tạp hơn một chút nhưng cũng mang tính “trường học”. Chúng tôi khuyên bạn nên tự kiểm tra chúng (xem bài toán ở cuối bài viết).

Mô tả về chương trình hoàn chỉnh mô phỏng chuyển động của các quả bóng $N$ trên màn hình đồ họa được đưa ra trong bài viết “Khí trên màn hình” (xem trang 61).

Tốc độ tính toán bằng sơ đồ tương tự là bao nhiêu? Máy tính được sử dụng trong thực hành sinh viên tại Khoa Vật lý của Đại học Bang Novosibirsk có thể đếm với tốc độ đến mức các khung hình trên màn hình thay đổi nhanh như trong một phim hoạt hình (nếu không có quá mười quả bóng; khi số lượng quả bóng tăng lên, thời gian tính toán cho mỗi khung hình của “phim hoạt hình” sẽ nhanh chóng được tính toán)*.

Máy tính của chúng tôi thực hiện tất cả các phép tính với 7-8 chữ số.

*) Việc tính toán được thực hiện trên máy tính Elektronka-60, có trong Sổ tay Hệ thống Thiết bị đầu cuối (TEVUS - do Đại học Bang Novosibirsk phát triển).

Hình 2.

⟦folio 4⟧

Họ - người đầu tiên, và sau đó là những người còn lại - “lạc đường” và đến một nơi hoàn toàn khác với nơi họ thêu. Như vậy, chuyển động của các quả bóng hóa ra là “sai”. Tại sao?

Toàn bộ phép tính được thực hiện bằng cách sử dụng các công thức chính xác, vì vậy nguyên nhân duy nhất có thể dẫn đến “không chính xác” là do làm tròn số trong quá trình tính toán. Nhưng độ lệch liên quan đến việc làm tròn có giá trị tương đối là $10^{-7} - 10^{-8}$ (như chúng tôi đã nói, máy tính hoạt động với các giá trị 7-8 chữ số) và trên màn hình theo thời gian $2t_0$ các quả bóng đã hoàn toàn “quên” vị trí ban đầu của chúng. Sự “quên” này có thể được giải thích bằng cách làm tròn số không?

Ước tính sai lệch

Để có được ước tính định lượng, chúng ta hãy tưởng tượng rằng, do làm tròn, hướng chuyển động của một trong các quả bóng đã lệch một góc $\varphi_0 \sim 10^{-7}$ và chuyển động tiếp theo được tính toán chính xác.

Đầu tiên, xét trường hợp chỉ có một quả bóng và xảy ra hiện tượng lệch khi nó chạm vào tường. Quỹ đạo của tâm quả bóng được mô tả trong hình 3, và một số công thức cũng được đưa ra ở đó để thuận tiện cho việc tính toán. Hình vuông ở cạnh $(b - 2a)$ là khu vực có thể tiếp cận được với tâm quả bóng $(b - \text{dлина стононы бильярного стола})$. Độ dài của quỹ đạo $1 \rightarrow 2 \rightarrow 3 \rightarrow 4 \rightarrow 5 \rightarrow \dots$ bằng chiều dài của chùm tia $1 \rightarrow 2 \rightarrow 3' \rightarrow 4' \rightarrow 5' \rightarrow \dots$. Nếu tại điểm 1, do làm tròn giá trị $v_x$, hướng vận tốc của quả bóng sau khi va chạm lệch khỏi hướng chính xác một góc nhỏ $\varphi_0$, thì trên đường đi có chiều dài $L$ độ lệch tâm quả bóng sẽ “tích lũy” một khoảng cách $\Delta \sim L\varphi_0$. Giới hạn bản thân trong thời gian $T$, trong đó $v_1 = 1000$ va chạm với tường, chúng ta thu được độ lệch $\Delta_1 \sim v_1 b\varphi_0 \sim 10^{-4}b$. Đối với màn hình đồ họa của chúng tôi, độ dày đường kẻ trên màn hình là khoảng $0,004b$. Vì vậy, trong thời gian $T$ độ lệch tích lũy không thể thay thế được - nó nhỏ hơn độ dày của đường kẻ trên màn hình. Bằng một khoảng cách đáng chú ý bằng, chẳng hạn như đường kính của quả bóng $2a$, tâm của quả bóng sẽ lệch đi $v_2 \sim 2a/b\varphi_0$ va chạm. Thời gian để xảy ra số lượng tác động lên tường như vậy ước tính là 100 (!) giờ.

Rõ ràng, việc làm tròn khi tính toán tác động lên tường không thể quy cho chuyển động “không chính xác” của các quả bóng trong thí nghiệm của chúng tôi.

Chúng ta hãy xem việc làm tròn số ảnh hưởng như thế nào đến việc tính toán va chạm của các quả bóng. Một lần nữa chúng ta hãy giả sử rằng hướng chuyển động của một trong các quả bóng đã lệch một góc $\varphi_0 \sim 10^{-7}$, và chúng ta sẽ nghiên cứu xem góc lệch khi va chạm sẽ nhỏ hơn như thế nào. Trong trường hợp này, chúng tôi sẽ giới hạn bản thân ở những ước tính của chính nhóm. Chúng ta sẽ nhớ rằng giữa các lần va chạm, quả bóng chuyển động theo đường thẳng và đi theo đường trung bình $l$, lớn hơn nhiều so với bán kính của quả bóng $(l \gg a)$. Trong khoảng thời gian giữa hai lần va chạm liên tiếp, tâm của quả bóng sẽ dịch chuyển một đoạn $OO' \sim l\varphi_0$ (hình 4). Sau đó còn có thứ tự dịch chuyển điểm tiếp xúc của các quả bóng khi va chạm. Diện tích bề mặt của quả bóng thứ hai ở gần điểm tiếp xúc đóng vai trò như một “tấm gương” trong quá trình va chạm. Bản thân “tấm gương” này đã chuyển động trước khi va chạm; khi va chạm, nó bật lại nên hướng bóng của chúng ta nảy lên không được xác định theo quy luật “góc tới bằng góc phản xạ”. Tuy nhiên, xoay “gương” nhỏ

⟦folio 5⟧

góc α dẫn đến sự thay đổi hướng chuyển động của quả bóng bật lại một góc φ₁ ~ α (có thể nhiều hơn hoặc ít hơn một lần rưỡi đến hai lần - mức độ chính xác này trong trường hợp này là THẲNG). Vì α ~ (AA'/a) ~ (lφ₀/a), nên chúng ta thu được

φ₁ ~ (l/a) φ₀ >> φ₀

— khi va chạm, độ lệch tốc độ tăng mạnh. Sau k nên mới φₖ ~ (l/a) k φ₀.

Nếu (l/a) ~ 10, thì 8-10 nên mới đủ để φₖ ~ 1 trở thành và hướng chuyển động của quả bóng không còn liên quan gì đến hướng chuyển động đúng.

THÍ NGHIỆM KIỂM SOÁT

Các ước tính được đưa ra có vẻ thuyết phục nhưng chúng tôi sẽ kiểm tra chúng bằng thử nghiệm trên máy tính. Để làm điều này, chúng tôi sẽ thực hiện hai lần “phóng” các quả bóng có điều kiện ban đầu gần như giống hệt nhau, lần thứ hai chỉ thay đổi một chút tốc độ ban đầu (hoặc vị trí ban đầu) của một trong các quả bóng.*) Chúng tôi sẽ “ra lệnh” cho máy tính ghi nhớ tọa độ của một quả bóng trong những khoảng thời gian bằng nhau Δt; trong lần chạy thứ hai, chúng ta sẽ đánh dấu tọa độ của cùng một quả bóng tại cùng một thời điểm tₖ = k Δt, và sau đó chúng ta sẽ xác định “độ phân kỳ” quỹ đạo của quả bóng này thay đổi như thế nào theo thời gian

Δrₖ = √((xₖ - x'ₖ)² + (yₖ - y'ₖ)²),

trong đó xₖ, yₖ là các giá trị tọa độ tại thời điểm tₖ ở lần phóng đầu tiên và x'ₖ, y'ₖ ở lần phóng thứ hai. Có tính đến sự phụ thuộc dự kiến, sẽ thuận tiện khi sử dụng thang logarit dọc theo trục Δrₖ, tức là vẽ các giá trị log (Δrₖ) ​​dọc theo trục này. Sự phụ thuộc có dạng φₖ ~ (l/a) k φ₀ sẽ dẫn đến đồ thị đường thẳng

lg (Δrₖ) ~ lg φ₀ + (t/tₖ) lg (l/a).

Kết quả của các thí nghiệm được hiển thị trong hình 5. Một biểu đồ hiển thị các điểm thu được ở các độ lệch khác nhau trong các điều kiện ban đầu. Phần thẳng dự kiến ​​​​của biểu đồ có thể nhìn thấy khá rõ ràng. Sau thời gian ℭ, giá trị của Δrₖ tăng đến giới hạn do kích thước của bảng đặt, và sau đó thay đổi hỗn loạn, nhưng nói chung, không phải hàng triệu lần (như trong vùng t < ℭ), sao cho trên thang logarit, các điểm tại t > ℭ không lệch ngay cả so với đường thẳng lg (Δrₖ) ~ log l.

Thí nghiệm máy tính này chứng minh tính hợp lý của những ước tính trước đó.

*) Tất nhiên, khi khởi động lại với cùng điều kiện ban đầu, chuyển động được tính toán sẽ được lặp lại chính xác.
