---
id: 2024-8-leonovich-a-tak-li-horosho-znakomyi-vam-fizika-proizvodnaya-d25db41e
issue: kvant_2024_8
year: 2024
number: "8"
title: Bạn đã quá quen thuộc với vật lý + đạo hàm?
authors:
  - Леонович А. А.
rubric: kaleydoskop-kvanta
rubric_sub: Калейдоскоп
page_first: 34
page_last: 35
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 6f5f790f55a3b77e96e098c303019ec018f70ff48abb95a993f9ec66fb72ff28
prompt_sha256: draft-1
translated_from: content/ru/2024/08/articles/07_leonovich-a-tak-li-horosho-znakomyi-vam-fizika-proizvodnaya-d25db41e.md
source_content_sha256: c6416ade1873c56fbf84d4d71f066c73a98e6869d925271d66f1869c40b8faf0
translation_model: draft
translation_run: vi-draft-gaps-2026-11-02
translation_quality: draft
---

⟦folio none⟧

Bạn có biết người tốt nào không?
VẬT LÝ + PHÁT SINH?

Đạo hàm và tích phân là những khái niệm cơ bản
tya của phân tích toán học. Dù tôi đã quen
nó chỉ xảy ra ở những năm lớn hơn
các lớp học ở trường, với một số bài toán thể chất,
yêu cầu sử dụng chúng có thể được giải quyết sớm hơn. Trong những trường hợp như vậy bạn thấy mình
ở vị trí ưu tiên dành cho các nhà khoa học đã hoàn thành
việc tạo ra các phép tính vi phân và tích phân. Những yếu tố trước
stvennik đã có cơ hội miêu tả toàn bộ cali-
một danh sách các cách để tìm
các tùy chọn thay thế lời giải, ví dụ: khi tìm kiếm cực trị của hàm số,
mô tả các quá trình vật lý

Hãy thử ngay hôm nay
cách tiếp cận tương tự. Bắt đầu với đạo hàm.
Theo Feynman, nếu về nguyên tắc, bạn không thể làm gì nếu không có đạo hàm, thì bạn có thể làm gì, làm quen với các từ và khái niệm mới, theo Feynman, và cố gắng nắm vững chúng nhanh hơn.

Và về tích phân lần sau.

Câu hỏi và bài toán

1. Hàm đạo hàm có thể có ý nghĩa vật lý gì: a) $v(t)$ – tốc độ; b) $q(t)$ – điện tích đi qua tiết diện của dây dẫn; c) $Q(T)$ – lượng nhiệt truyền; d) $A(t)$ – công việc đã hoàn thành; e) $\Phi(t)$ – từ thông, đường viền tùy ý; e) $N(t)$ – số lượng nguyên tử phóng xạ?

2. Một vận động viên trượt tuyết trượt xuống một ngọn núi có độ cao $H$, kết thúc bằng cú nhảy ngang. Ở độ cao nào của bẫy $h$ người đánh bẫy sẽ di chuyển quãng đường lớn nhất $s$ theo chiều ngang và đó là bao nhiêu? Bỏ qua ma sát và lực cản của không khí.

3. Khi hành khách còn khoảng cách $s = 25$ m để tới cửa, tàu sẽ
zerous từ một nơi và bắt đầu tăng tốc với gia tốc $a = 0,5 \text{ m/c}^2$. Người hành khách chạy với tốc độ không đổi. Ở tốc độ tối thiểu nào anh ta tốn trục của mình?

4. Chiếc đèn lồng đặt cách bức tường thẳng đứng $R_0 = 3$ m, quay đều quanh trục thẳng đứng với tần số $n = 0,5 \text{ c}^{-1}$ và ném một chú thỏ nhẹ lên tường. Tốc độ của con thỏ $t = 0,1$ s sau khi chùm sáng vuông góc với tường là bao nhiêu?

5. Một chiếc thuyền có tốc độ $v_0$ hạ buồm tại thời điểm $t_0$, nhưng vẫn tiếp tục chuyển động với tốc độ hyperbol so với sự phụ thuộc thời gian $\left(v \sim \frac{1}{t}\right)$. Gia tốc của thuyền sẽ phụ thuộc vào vận tốc của nó như thế nào?

6. Sự phụ thuộc của khối lượng của một thanh không đồng nhất vào chiều dài $m(l) = kl^2$ của nó, trong đó $k = 3 \text{ кг/m}^2$. Mật độ tuyến tính của thanh tại điểm $l = 2$ m, nhỏ hơn tổng chiều dài của nó $L$ là bao nhiêu?

⟦folio none⟧

---
running_head:
folio:
---

7. Làm thế nào bạn có thể chứng minh bằng đồ thị rằng khi thế năng của một vật $U$ thay đổi một giá trị không đổi $U_0$ thì lực tác dụng lên vật tại mỗi điểm sẽ không thay đổi?
8. Một vật chuyển động dọc theo trục $x$ theo hướng dương với tốc độ không đổi 5 m/s. Thế năng của vật thay đổi dọc theo trục theo định luật $U(x) = -10^{-2}x$ J. Tìm công suất do các lực cản lại chuyển động phát triển.
9. Một chất khí lý tưởng giãn nở theo định luật $p(V) = aV + b$, trong đó biết $a < 0$ và $b > 0$. Ở thể tích khí nào trong quá trình này nhiệt độ đạt cực đại?
10. Xác định áp suất lớn nhất có thể có $v$ mol của khí lý tưởng trong quá trình xảy ra theo định luật $T = T_0 \left(1 - \frac{V_0}{V}\right)$, trong đó $T_0$, $V_0$ là các hằng số dương đã biết ($V > V_0$).
11. Một nguồn dòng điện có emf $\varepsilon$ và điện trở trong $r$ được nối với một biến trở. Ở điện trở nào thì nó sẽ tạo ra công suất cực đại? Nó bằng gì?
12. Có thể có được một điện trường đầu ra không đổi?
13. Liệu suất điện động tự cảm ứng có xuất hiện trong cuộn dây mang dòng điện một chiều không?
14. Tại sao khi nối nam châm điện vào mạch điện thì cường độ dòng điện toàn phần không được thiết lập ngay lập tức?

Kinh nghiệm vi mô
Hóa ra, đạo hàm có thể được “cảm nhận” rõ ràng nếu bạn nhớ lại những gì bạn trải qua ở hộp số tự động khi chuyển từ trạng thái dừng hoặc khi phanh gấp. Đại lượng vật lý chính xác mà chúng ta đang nói đến trong trường hợp này là gì?

Thật thú vị rằng...
...Archimedes còn nghiên cứu các vấn đề liên quan đến việc xác định cực trị và vẽ tiếp tuyến. Các phương pháp mà ông phát triển đã xác định trước phép tính vi phân xuất hiện vào thế kỷ 17.
...một đóng góp đáng kể cho sự phát triển của giải tích toán học được thực hiện bởi Galileo và các học trò của ông là Vivani và Torricelli, các phương pháp xây dựng tiếp tuyến đã được phát triển, và các nhà khoa học người Pháp Roberval, Descartes và Fermat, cuộc tranh cãi giữa họ đã dẫn đến định nghĩa được chấp nhận rộng rãi của tiếp tuyến là vị trí giới hạn của cát tuyến.
...Phương pháp vẽ tiếp tuyến của Pierre Fermat đã mang lại cho Newton, như ông thừa nhận, một gợi ý về việc tạo ra phép tính vi phân. Leibniz, người có cùng danh tiếng với Newton, người sáng tạo ra lý thuyết này, đã lưu ý rằng Blaise Pascal gần với cách xây dựng nó đến mức nào, và thuật toán tìm cực trị nổi tiếng của Fermat đã cho phép Leibniz suy ra định luật Snell về tiền đô ánh sáng.
...toán học mới của Newton và Leibnitz dựa trên một ý tưởng đơn giản - chuyển động của bất kỳ vật thể nào trong một khoảng thời gian ngắn có thể được coi gần đúng là chuyển động thẳng và đều.
... các phương trình không chỉ chứa bản thân các hàm mà còn chứa các phương trình tùy ý của chúng, tức là cái gọi là phương trình vi phân giúp mở rộng mô tả các quy luật tự nhiên và giải quyết các vấn đề chưa được trình bày trong một thời gian dài lời giải. Vì vậy, trong cơ học thiên thể, người ta không chỉ có thể giải thích những sự thật đã biết mà còn có thể thực hiện những khám phá mới. Một ví dụ có thể là việc phát hiện ra hành tinh Sao Hải Vương vào năm 1846 hoặc việc phát hiện ra sóng điện từ.
... sử dụng các bậc khác nhau tùy ý, định luật II Newton, các định luật bảo toàn năng lượng, động lượng, mô men động lượng, các phương trình Maxwell biểu diễn tất cả các định luật cơ bản của hiện tượng điện từ, ý nghĩa của phương trình Schrödinger, có vai trò chức năng tương tự trong các quá trình nguyên tử như các định luật Newton trong cơ học cổ điển, đều được viết ra.

Đọc gì trong «Kvant»
về vật lý và miễn phí
(xuất bản những năm gần đây)
1. “Priizz Fermat và hành vi không được huấn luyện của ánh sáng” – 2017, số 2, tr.27;
2. “Đổ nước…” – 2019, số 10, tr.29;
3. “Chân dung thực tế là gì” – 2019, số 11, tr.29;
4. “Phương trình động học đúng nhất” – 2019, số 12, tr.24;
5. “Archimedes và Vật lý thiên văn” – 2020, Số 9, tr.2;
6. “Sông từ xa chảy dài…” – 2021, số 6, tr.36;
7. “Dòng chảy xung lực” – 2024, số 2, tr.41.
Tài liệu do A. Leonov chuẩn bị
