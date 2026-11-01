---
id: 2024-9-bondarov-kak-nayti-oshibku-b83e4606
issue: kvant_2024_9
year: 2024
number: "9"
title: Cách tìm lỗi
authors:
  - Бондаров М. Н.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 46
page_last: 55
page_labels: 44-53
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 83a024aad9dcd5972e07decea0023c83451b40f4976a25574793932ca9612be6
prompt_sha256: draft-1
translated_from: content/ru/2024/09/articles/12_bondarov-kak-nayti-oshibku-b83e4606.md
source_content_sha256: 704ba09f388273a3a05225482504a6545c588fe692357a9e87933b7caa3fd7c0
translation_model: draft
translation_run: vi-draft-gaps-2026-11-02
translation_quality: draft
---

⟦folio 44⟧

ỨNG DỤNG THỰC HÀNH

Cách tìm lỗi
M.BONDAROV

Như bạn đã biết, không ai tránh khỏi những sai lầm. Ngay cả những người hiểu sâu sắc về vật lý, ngay cả số lượng cũng là nhà khoa học.

Năm 1905, trong luận án tiến sĩ của mình, Albert Einstein đã đề xuất một phương pháp lý thuyết mới để xác định bán kính phân tử và hằng số Avogadro. Luận án đã được phê duyệt và Einstein trở thành bác sĩ. Sau này chúng tôi phát hiện ra rằng cả Einstein lẫn đối thủ của ông đều không nhận thấy một lỗi nghiêm trọng nào trong các phép tính. Chỉ vài năm sau, như một trong những người viết tiểu sử của Einstein [1] viết, người ta đã phát hiện ra lỗi “cơ bản nhưng không tầm thường” này, bởi vì kết quả của thí nghiệm khác với các giá trị thu được từ phương trình rút ra trong luận án.

Bài viết này sẽ không nói về những trường hợp trong lịch sử vật lý mà nói về những lỗi mà học sinh mắc phải trong các kỳ thi lời giải thể chất bài toán, tối ưu hóa và các bài kiểm tra khác. Đồng thời, chúng ta sẽ cho rằng học sinh có thể hiểu thành công các định luật vật lý của bài toán được giao cho mình, viết ra tất cả các phương trình cần thiết cho lời giải, nhưng trong quá trình đi đến kết quả cuối cùng đã mắc lỗi trong các phép biến đổi hoặc tính toán toán học. Và bây giờ vấn đề chính của anh ấy là xác định và loại bỏ các giả định sai sót. Chúng tôi sẽ chỉ tập trung vào việc phân tích bức thư đáp số. Đối với mỗi bài toán, một số đáp số có thể sẽ được đưa ra, trong số đó chắc chắn sẽ có một cái đúng.

Vì vậy, mục tiêu của chúng tôi là có thể nhận ra tất cả đáp số không chính xác mà không cần đến lời giải bài toán không chính xác, chỉ dựa vào sự hiểu biết sâu sắc về mô hình của các quy trình được mô tả trong các điều kiện. Dưới đây là “tên” của những người trợ giúp chính để đạt được mục tiêu này: kích thước, tính đối xứng, trường hợp đặc biệt.

Hãy bắt đầu với bài toán, đối với lời giải đòi hỏi kiến ​​thức của học sinh lớp bảy.

Nhiệm vụ 1. Gonchik.edem nằm trên đường cao tốc và được hướng dẫn bởi các biển báo siêu âm gợn sóng dọc theo đường cao tốc. Tay đua liên tục nhảy tới tốc độ $v_1, v_2, v_3, v_4$ khi chúng tôi vượt qua khối tiếp theo. Tốc độ trung bình $v_{\text{cp}}$metequivla là bao nhiêu?

Phương pháp lời giải bài toán được nhiều người biết đến. Đặt khoảng cách giữa các cột là $l$. Khi đó, tốc độ trung bình $v_{\text{cp}}$ được định nghĩa là tỷ lệ của toàn bộ đường đi $4l$ với thời gian $t$ đi qua, trong đó $t = l/v_1 + l/v_2 + l/v_3 + l/v_4$. Nói cách khác, tất cả những gì còn lại là chia $4l$ cho $(l/v_1 + l/v_2 + l/v_3 + l/v_4)$, giảm $l$ và mục tiêu đã đạt được:

$$v_{\text{cp}} = \frac{4}{\frac{1}{v_1} + \frac{1}{v_2} + \frac{1}{v_3} + \frac{1}{v_4}}.$$

⟦folio 45⟧

---
running_head:
folio:
---

Các lỗi toán học có thể xuất hiện nếu bạn muốn tiếp tục các phép biến đổi để giảm bớt “câu chuyện” của một phân số. Dưới đây là một số đáp số có thể xảy ra, trong số đó bạn cần chọn một câu đúng duy nhất:

A. $v_{cp} = \frac{4v_1v_2v_3v_4}{v_1 + v_2 + v_3 + v_4}$;

V. $v_{cp} = \frac{4v_1v_2v_3v_4}{v_1v_2v_3 + v_1v_2v_4 + v_1v_3v_4}$;

C. $v_{cp} = \frac{4v_1v_2v_3v_4}{v_1v_2v_3 + v_1v_2v_4 + v_1v_3v_4 + v_2v_3v_4}$;

D. $v_{cp} = \frac{v_1v_2v_3v_4}{v_1v_2v_3 + v_1v_2v_4 + v_1v_3v_4 + v_2v_3v_4}$.

Theo nguyên tắc chung, đáp số A và B thường bị loại bỏ trước tiên. Rõ ràng, đáp số A không đạt trong bài kiểm tra thứ nguyên. Trên thực tế, vế trái của công thức này có thứ nguyên là tốc độ (m/s) và vế phải có thứ nguyên là lập phương tốc độ (m/s)³. Trong đáp số B sự bất đối xứng của nó rất đáng chú ý. Lưu ý rằng trong mẫu số của phân số này, các đại lượng $v_1$ xuất hiện 3 lần và các đại lượng $v_2$, $v_3$ và $v_4$ chỉ xuất hiện 2 lần. Nhưng trong điều kiện bài toán tất cả tốc độ đều bằng nhau, vì vậy không có tốc độ nào nổi bật ở đáp số. Chúng ta hãy khái quát hóa quan sát này: nếu có một số đối xứng trong các điều kiện nhất định, thì một đối xứng nhất định chắc chắn phải xuất hiện trong đáp số.¹ Trong trường hợp B, điều này không được quan sát thấy và đáp số này không thể đúng.

Vì vậy, chúng ta chỉ còn lại hai đáp số cuối cùng, mỗi cái đều vượt qua thành công việc kiểm tra chiều và tính đối xứng. Bây giờ chúng ta hãy xem xét một trường hợp đặc biệt như vậy khi đáp số rất IDEN. Hãy để người lái xe ở tất cả các đoạn đường có cùng tốc độ $v_1 = v_2 = v_3 = v_4 = v$, trong trường hợp này rõ ràng là bằng tốc độ trung bình. Chúng ta hãy chú ý tất cả tốc độ trong các câu trả lời C và D đều giống nhau và bằng v. Kết quả là, $v_{cp} = v$ đúng cho đáp số C và biểu thức phản trực giác $v_{cp} = v/4$ cho đáp số D.

¹ Một trường hợp danh dự với một nhân viên đánh máy vật lý có kinh nghiệm đã phát hiện ra lỗi trong đáp số không có nhiệm vụ lời giải được mô tả trong bài viết [2].

Vì vậy, tất cả các đáp số sai đã bị loại bỏ và chúng tôi đã tìm ra đáp số C. Sau khi thực hiện các phép biến đổi toán học một cách cẩn thận, chúng tôi sẽ đảm bảo rằng từ công thức (*) thu được chính xác đáp số C.

Người đọc tinh ý chắc chắn sẽ nhận thấy rằng trong số đáp số có thể không có đáp số sai phổ biến nhất:

E. $v_{cp} = \frac{v_1 + v_2 + v_3 + v_4}{4}$.

Điều này không phải ngẫu nhiên, bởi vì chúng ta sẽ chỉ xem xét những đáp số không phải ngẫu nhiên (ngẫu nhiên), mà là kết quả của sự hiểu biết sâu sắc về các quá trình vật lý được mô tả trong bài toán, tuy nhiên, khi có sai sót toán học. Rõ ràng là các phương trình viết bằng lời giải khó có thể dẫn đến đáp số E.

Tuy nhiên, hãy thử phân tích xác minh và đảm bảo rằng đáp số E không thể đúng. Một lần nữa, một trường hợp đặc biệt sẽ giúp chúng ta: hãy để nó không đổi trong ba phần đầu tiên của cái nồi: $v_1 = v_2 = v_3 = v$, và ở phần cuối cùng nó rất nhỏ: $v_4 \rightarrow 0$. Vận tốc trung bình của người đi xe máy trên suốt quãng đường là bao nhiêu? Rõ ràng là do tốc độ $v_4$ thấp nên thời gian $t$ chuyển động trở nên rất lớn (trong giới hạn một người có xu hướng tiến về vô cực: $t \rightarrow \infty$). Điều này có nghĩa là theo định nghĩa về tốc độ trung bình ($v_{cp} = s/t$), nó cũng phải rất nhỏ, chẳng hạn như $v_4$. Chúng ta hãy lưu ý rằng ở $v_4 \rightarrow 0$ trong trường hợp đúng đáp số C, tốc độ trung bình cũng trở nên rất nhỏ. Nhưng đáp số E cho một kết quả không hợp lý trong trường hợp này: $v_{cp} = 3v/4$. (Rõ ràng là để phân tích, có thể giả định tốc độ thấp ở bất kỳ phần nào khác.)

Hãy xem xét một bài toán khác để tính tốc độ trung bình, trong đó các đoạn đường có độ dài khác nhau.

Bài toán 2. Phần thứ ba của toàn bộ đường dẫn được tự động chiếu ở tốc độ $v_1$ và phần còn lại ở tốc độ $v_2$. Tốc độ trung bình của $v_{cp}$ tự động là bao nhiêu?

Có thể đáp số:

A. $v_{cp} = \frac{2v_1v_2}{v_1 + v_2}$;

B. $v_{cp} = \frac{v_1 + 2v_2}{3}$;

C. $v_{cp} = \frac{2v_1 + v_2}{3v_1v_2}$;

⟦folio 46⟧

---
running_head:
folio:
---

D. $v_{\text{cp}} = \frac{3v_1v_2}{2v_1 + v_2}$;
E. $v_{\text{cp}} = \frac{3v_1v_2}{v_1 + 2v_2}$.

Việc phân tích đáp số trong bài toán này được thực hiện tương tự như lần trước. Bắt đầu bằng việc kiểm tra thứ nguyên, có thể dễ dàng nhận thấy rằng trong trường hợp C, khi giải bài toán, ở biểu thức cuối cùng, hình như họ đã quên lật phân số. đáp số đã cho không thể đúng. Đối xứng duy nhất đáp số A là không phù hợp, vì không có sự đối xứng trong các điều kiện và do đó không nên có một đối xứng trong đáp số. Đáp số B bị loại bỏ vì lý do tương tự như đáp số E ở bài toán trước: trong trường hợp tốc độ rất thấp, ví dụ như ở phần đầu tiên, tốc độ trung bình cũng phải rất nhỏ. Tuy nhiên, khi thay $v_1 \rightarrow 0$ vào công thức, chúng ta có $v_{\text{cp}} = 2v_2/3$ chứ không phải $v_{\text{cp}} \rightarrow 0$.

Vẫn còn phải lựa chọn giữa hai vị trí, câu trả lời D và E, câu trả lời này đã vượt qua thành công tất cả các bài kiểm tra cho phép trả lại sai ba vị trí đáp số đầu tiên. Than ôi, trường hợp đặc biệt về sự bằng nhau về tốc độ, đã giúp chúng ta trong quá khứ bài toán, cũng sẽ không giúp được gì cho chúng ta. Trên thực tế, đối với $v_1 = v_2 = v$ cả hai công thức đều cho kết quả đúng: $v_{\text{cp}} = v$. Chà, hãy thử một trường hợp đặc biệt khác: tốc độ rất cao trong phần thứ hai (trong trường hợp giới hạn $v_2 \rightarrow \infty$). Khi đó mẫu số của công thức D có thể bị bỏ qua bởi giá trị nhỏ $2v_1$ so với giá trị rất lớn $v_2$, dẫn đến đáp số

$$v_{\text{cp}} = \frac{3v_1v_2}{2v_1 + v_2} \approx \frac{3v_1v_2}{v_2} = 3v_1.$$

Chúng ta hãy đảm bảo rằng đáp số D phải đúng trong trường hợp cụ thể của chúng ta. Một phần ba tuyến đường được tự động hóa, di chuyển chậm, và hai phần ba tiếp theo gần như gấp rút ngay lập tức, hầu như không dành thời gian cho nó. Nói cách khác, trong trường hợp này, trong khoảng thời gian mà xe số tự động bỏ ra, vượt qua đoạn đường đầu tiên với tốc độ $v_1$, để đi hết 1/3 đoạn đường đầu tiên $l$, xe số tự động sẽ có thể đi hết toàn bộ đoạn đường $3l$. Đối với điều này, rất indo, tốc độ $v_{\text{cp}}$ của anh ta phải lớn thứ hai so với tốc độ $v_1$ trong một phần ba chặng đường đầu tiên.

Hãy tự lập luận tương tự cho công thức E và chỉ ra rằng điều này dẫn đến kết quả sai $3v_1/2$.

Bây giờ chúng ta hãy kiểm tra kết luận của mình dựa trên phân tích đáp số bằng cách giải bài toán. Đặt trọng số của đường đi bằng $3l$ và luôn bằng $t$. Khi đó tốc độ trung bình

$$v_{\text{cp}} = \frac{3l}{t} = \frac{3l}{\frac{l}{v_1} + \frac{2l}{v_2}} = \frac{3v_1v_2}{2v_1 + v_2}.$$

Đúng vậy.

Vì vậy, chúng tôi tin rằng hướng dẫn làm việc để phát hiện các lỗi có thể xảy ra trong câu trả lời (cũng như trong các công thức trung gian) là ba phương pháp xác minh chính: kích thước, tính đối xứng và trường hợp đặc biệt. Tất nhiên, điều quan trọng nhất là điều đầu tiên: kích thước. Với sự trợ giúp của nó, hầu hết các loại lỗi đều được phát hiện.

Và ở đây, có lẽ, nó có ý nghĩa như sau. Thực phẩm Lily có ít nhất một học sinh bắt đầu giảm chiều cao và nhiệt độ. Đồng thời, ở lời giải bài toán sai sót về kích thước sẽ xảy ra khá thường xuyên. Hơn nữa, trong một số trường hợp, không cần có điều kiện lớn để phát hiện ra chúng. Đây chỉ là một vài cách diễn đạt tương tự mà hầu hết những người kiểm tra bài tập của học sinh đều gặp phải:

1) $s + v/t$; 2) $m - M^2$;
3) $I + R/U$; 4) $(F - m)a$.

Rõ ràng, việc kiểm tra kích thước phải là người bạn đồng hành thường xuyên của bạn nếu bạn muốn giải bài toán một cách chính xác.

Lưu ý rằng việc vượt qua tất cả các bước kiểm tra được thảo luận ở trên không đảm bảo tính chính xác của đáp số. Những lần kiểm tra này chỉ cho phép chúng tôi loại bỏ đáp số mới. Tuy nhiên, theo người này, nó cũng rất hữu ích.

Bây giờ chúng ta hãy chuyển sang bài toán dành cho học sinh lớp chín.

Bài 3. Tìm lực $T$ của lực căng giữa tải trọng 2 và 3 trong hệ như ở hình 1. Biết khối lượng của các tải trọng, bỏ qua khối lượng của khối. Không có ma sát. Gia tốc của nadiya tự do là $g$.

⟦folio 47⟧

---
running_head:
folio:
---

Có thể đáp số:
A. $T = \frac{2m_1m_3g}{m_1 + m_2 + m_3}$;
V. $T = \frac{2m_1m_2g}{m_1 + m_2 + m_3}$;
C. $T = \frac{m_1m_3g}{m_1 + m_2 + m_3}$;
D. $T = \frac{(m_1 + m_2 + m_3)g}{2}$;
E. $T = \frac{2m_1m_3g}{m_1 - m_2 - m_3}$.

Than ôi, hai phương pháp xác minh đầu tiên mà chúng tôi đã sử dụng thành công trong các nhiệm vụ trước đó lần này không giúp ích được gì. Chỉ còn một hy vọng - vào một trường hợp đặc biệt được lựa chọn tốt.

Trong trường hợp nào sợi chỉ giữa tải 2 và 3 sẽ không còn bị căng nữa? Đầu tiên, nếu chúng ta loại bỏ gruz với khối lượng $m_3$: thì không có gì để kéo sợi chỉ. Thứ hai, khi tháo gruz $m_1$, sợi thứ hai và thứ ba sẽ bắt đầu rơi tự do và sợi chỉ sẽ không bị căng nữa. Hóa ra $T = 0$ với $m_1 = 0$ và $m_3 = 0$; Điều này có nghĩa là số lần rung phải bao gồm sản phẩm $m_1m_3$. Kiểm tra này mâu thuẫn với đáp số B và D - chúng tôi loại bỏ chúng. Trong trường hợp E, chúng ta hãy chú ý đến những “điểm trừ” trong mẫu số: chúng phải luôn gây ra một phần ba nào đó ở người đang kiểm tra đáp số về độ tin cậy. Trên thực tế, đường dẫn gruz ở bên trái khối có tổng khối lượng bằng tổng khối lượng của gruz ở bên phải, tức là $m_2 + m_3 = m_1$. Khi đó, theo biểu thức E, sợi dây phải được căng bởi một lực vô cùng lớn. Như đã biết, không thể có những lực như vậy trong hệ thống gruz - chúng tôi loại bỏ một đáp số khác.

Dừng lại lần nữa là hai đáp số, chỉ khác nhau một chút. Điều gì sẽ xảy ra nếu chúng ta thử đoán $m_2 + m_3 = m_1$ lần nữa? Trong trường hợp này, hệ thống không có khả năng tăng tốc và sợi dưới sẽ căng $T = m_3g$. Đây chính xác là những gì xảy ra trong đáp số A, trong khi đáp số C cho kết quả không chính xác $T = m_3g/2$. Tuy nhiên, một kỹ thuật khác có thể đã được sử dụng. Hãy tưởng tượng rằng một chiếc gruz rất nặng ($m_1 \rightarrow \infty$) được treo ở bên phải. Khi đó, tải nhẹ bên trái sẽ không thể ngăn anh ta rơi tự do gần như với gia tốc $g$. Đồng thời, bản thân chúng sẽ tăng lên với cùng một gia tốc về độ lớn (các sợi dây không thể mở rộng được). Và thế là

một tải có khối lượng $m_3$ được nâng lên bởi gia tốc $g$, sợi chỉ phải được căng với một lực $T = 2m_3g$. Thay thế $m_1 \rightarrow \infty$ vào công thức A và C, chúng tôi tin rằng điều này chỉ đúng với đáp số A.

Để kiểm tra lý luận của chúng ta, hãy giải bài toán. Gọi $a$ là gia tốc của tải, $T^*$ là lực căng của sợi dây thứ hai. Khi đó theo định luật II Newton $m_3a = m_3g - T$, $m_2a = m_2g + T - T^*$, $m_1a = T^* - m_3g$. Giải hệ này ta thu được kết quả đúng đáp số A.

Chúng tôi chưa xem xét các chi tiết cụ thể của điện bài toán. Đã đến lúc chuyển sang một môn dành cho học sinh lớp 10.

Bài toán 4. Hai điện trở $R_1$ và $R_2$ và hai tụ điện dung $C_1$ và $C_2$ được nối với nguồn điện áp không đổi $U$ như trong hình 2.

Điện tích nào $\Delta q$ sẽ chạy qua dây dẫn AB trong một khoảng thời gian đủ lớn sau khi đóng công tắc, nếu ban đầu các tụ điện đã được phóng điện?

Có thể đáp số:
A. $\Delta q = \frac{C_2R_2 + C_1R_1}{R_1 + R_2}U$;
V. $\Delta q = \frac{C_1R_2 + C_2R_1}{R_1 - R_2}U$;
C. $\Delta q = \frac{(C_2 - C_1)R_1R_2}{R_1 + R_2}U$;
D. $\Delta q = \frac{C_2R_2 - C_1R_1}{R_1 + R_2}U$;
E. $\Delta q = \frac{C_2R_1 - C_1R_2}{R_1 + R_2}U$.

Như thường lệ, chúng tôi bắt đầu bằng việc kiểm tra tính chiều và nó ngay lập tức cung cấp cho chúng tôi biến đầu tiên trong số các biến đáp số: C. Tiếp theo. Đáng chú ý là “trừ” trong mẫu số đáp số B. Rõ ràng là ở $R_1 = R_2$ (và không có trường hợp nào khác!) một điện tích vô cùng lớn không thể chảy qua phần AB.

Trong trường hợp nào thì điện tích sẽ không chính xác hơn dây nhảy AB? Rõ ràng là điều này

⟦folio 48⟧

---
running_head:
folio:
---

sẽ xảy ra nếu chuỗi đối xứng, tức là cả điện trở của điện trở và điện dung của tụ điện sẽ trở nên giống nhau. Sau đó, khi thay thế vào công thức cuối cùng, $R_1 = R_2$ và $C_1 = C_2$ sẽ cho kết quả là $\Delta q = 0$. Điều này không thỏa mãn đáp số A – chúng tôi loại bỏ nó.

Hai đáp số cuối cùng sẽ vẫn là: D và E. Hãy thay điện trở đầu tiên bằng một dây lý tưởng ($R_1 = 0$). Khi đó toàn bộ điện tích đã đi qua nó sẽ tiếp tục đi qua dây dẫn $AB$ đến tụ điện $C_2$. đáp số D thỏa mãn điều kiện này, vì khi thay $R_1 = 0$ vào nó, chúng ta có $\Delta q = C_2U$. Đồng thời, một sự thay thế tương tự trong đáp số E cho kết quả sai: $\Delta q = C_1U$.

Lưu ý rằng trong các mạch có điện trở và tụ điện, cũng hữu ích khi sử dụng hai trường hợp giới hạn khác: $C = 0$, khi không có tụ điện và $R \rightarrow \infty$, khi không có dây dẫn. Hãy thử tự mình sử dụng chúng để chọn cái đúng trong hai cái cuối cùng đáp số.

Chúng ta hãy xác minh lại tính đúng đắn của kết luận của mình chỉ dựa trên phân tích đáp số bằng cách giải bài toán. Sau khi sạc xong, dòng điện sẽ dừng và điện tích $C_1U$ và $C_2U$ sẽ tích tụ trên các tụ điện được mắc song song. Điều này có nghĩa là tổng điện tích $q = (C_1 + C_2)U$ sẽ chạy qua các điện trở. Các điện trở được mắc song song nên điện tích đi qua chúng phải tỷ lệ nghịch với các điện trở: $q_1 = qR_2 / (R_1 + R_2)$ và $q_2 = qR_1 / (R_1 + R_2)$. Do đó, theo chiều từ điểm A đến điểm B, điện tích sẽ chạy qua dây dẫn

$$\Delta q = q_1 - C_1U = (C_2R_2 - C_1R_1)U / (R_1 + R_2),$$
trùng với đáp số D.

Các ví dụ được xem xét cho thấy rằng việc kiểm tra chiều, tính đối xứng và trường hợp đặc biệt có thể giúp phát hiện các lỗi ở lời giải của các bài toán vật lý khác nhau một cách hiệu quả. Những ví dụ này thực sự cơ bản. Đúng, đôi khi chỉ với sự trợ giúp của họ thì không thể phát hiện ra tất cả các lỗi trong câu trả lời. Sau đó, các ví dụ khác sẽ xuất hiện trong kho phân tích của chúng tôi đáp số; Sẽ rất hữu ích nếu bạn chú ý đến câu trả lời của mình về bản chất của sự phụ thuộc, nguồn gốc và sự không chắc chắn.

Hãy chuyển sang xem xét bài toán tương tự và bắt đầu với bài toán dành cho học sinh lớp chín.

Bài 5. Một hành khách ở toa đầu tiên của đoàn tàu có chiều dài l được vận chuyển dọc theo sân ga. Khi anh đến gần toa cuối cùng, đoàn tàu bắt đầu tăng tốc. Người hành khách ngay lập tức chạy với vận tốc v. Sau bao lâu người đó đến được va-li của mình?

Có thể đáp số:

A. $t = \frac{v}{a} \sqrt{1 - \frac{2al}{v^2}}$;

B. $t = \frac{v}{a} \sqrt{1 + \frac{2al}{v^2}}$;

C. $t = \frac{v}{a} \left(1 - \sqrt{1 - \frac{2al}{v^2}}\right)$;

D. $t = \frac{v}{a} \left(1 + \sqrt{1 - \frac{2al}{v^2}}\right)$;

E. $t = \frac{v}{a} \left(1 - \sqrt{1 + \frac{2al}{v^2}}\right)$;

F. $t = \frac{v}{a} \left(1 + \sqrt{1 + \frac{2al}{v^2}}\right)$.

Đáp số, thoạt nhìn thì rất giống nhau. Kích thước và tính đối xứng sẽ không giúp ích gì cho chúng ta ở đây. Chúng ta sẽ phải khám phá những tình huống khắc nghiệt. Trong điều kiện bài toán, các đại lượng vật lý sau chỉ có thể thay đổi: chiều dài đoàn tàu l, gia tốc a và tốc độ hành khách v. Hãy thử làm việc với một trong số chúng; ví dụ: chúng ta hãy bắt đầu giảm chiều dài của đoàn tàu xuống 0 ($l \rightarrow 0$). Khi đó hành khách tại thời điểm ban đầu đã ở gần ô tô của mình nên thời gian cần thiết là $t = 0$. Điều này trái ngược với tất cả đáp số, ngoại trừ C và E. Chúng tôi đã rất may mắn và chỉ với sự trợ giúp của một đoạn văn đến giới hạn, chúng tôi đã xác định được bốn đáp số sai cùng một lúc.

Bây giờ chúng ta hãy xem xét kỹ hơn từ tăng dần cho các câu trả lời còn lại. Đáp số E không thể đúng và đây là lý do. Đầu tiên, chúng ta hãy chú ý đến bản chất của sự phụ thuộc của thời gian đặc biệt t vào chiều dài của đoàn tàu l. Rõ ràng, khi l giảm thì t nhất thiết phải giảm, nhưng theo công thức E, mọi thứ phải diễn ra ngược lại. Thứ hai, biểu thức căn thức lớn hơn 1, do đó, đối với bất kỳ giá trị nào có trong điều kiện, đại lượng sẽ âm.

Vì vậy, tất cả đáp số sai đều đã được tìm thấy thành công. Tuy nhiên, đừng vội: vẫn còn

⟦folio 49⟧

---
running_head:
folio:
---

một số điểm thú vị hữu ích để đề cập. Chúng ta hãy lưu ý rằng trong biểu thức căn thức, các đại lượng $a$ và $l$ ở gần nhau. Điều gì sẽ xảy ra nếu chúng ta tiếp tục với gốc $a$ theo cách tương tự như với độ dài $l$? Nếu bạn bắt đầu giảm gốc $a$ thì thời gian sẽ tăng lên ở tất cả các câu trả lời ngoại trừ $C$ và $E$. Và điều này hoàn toàn trái ngược với ý nghĩa vật lý. Chúng ta hãy xem xét công thức $C$ để đi đến giới hạn $a \rightarrow 0$. Sau khi thay thế, chúng ta thu được một biểu thức được gọi trong toán học là độ bất định có dạng $0/0$.

Lưu ý rằng chúng ta sẽ phải giải quyết một loại bất định khác nếu chúng ta bắt đầu nghiên cứu sự phụ thuộc của thời gian cần thiết vào tốc độ $v$ của hành khách. Hãy để tốc độ này bắt đầu tăng lên không giới hạn $(v \rightarrow \infty)$. Một lần nữa, tất cả đáp số ngoại trừ $C$ và $E$ đều mâu thuẫn với ý nghĩa vật lý của đáp số $t \rightarrow \infty$ và do đó phải bị loại bỏ. Trong các câu trả lời còn lại, biểu thức trong ngoặc có xu hướng bằng 0 và tập hợp ở phía trước dấu ngoặc có xu hướng vô cùng. Hiện tại, chúng ta đang phải đối mặt với rất nhiều loại tình trạng không chắc chắn khác: $\infty \cdot 0$. Phải làm gì trong tình huống như vậy? Ví dụ: bạn có thể sử dụng mối quan hệ phổ biến $\sqrt{1 \pm x} = 1 \pm \frac{x}{2}$, mối quan hệ này hợp lệ với $x (x \rightarrow 0)$ nhỏ. Khi đó trong trường hợp đáp số $C$ ta nhận được

$$t = \frac{v}{a} \left( 1 - \sqrt{1 - \frac{2al}{v^2}} \right) \approx \frac{v}{a} \left( 1 - \left( 1 - \frac{2al}{2v^2} \right) \right) = \frac{v}{a} \frac{al}{v^2} = \frac{l}{v}.$$

Từ đây có thể thấy ngay rằng ở tốc độ rất cao, thời gian trở nên rất nhỏ, như lẽ ra phải xảy ra khi thực hiện. Lưu ý rằng, hoàn toàn về mặt hình thức, trong điều này bài toán đáp số $D$ cũng đúng.

Tại lời giải bài toán bạn cần so sánh tọa độ của hành khách $x_1 = vt$ và ô tô đầu tiên $x_2 = l + \frac{at^2}{2}$, sau đó bạn được phương trình bậc hai $\frac{at^2}{2} - vt + l = 0$, nghiệm của phương trình này sẽ là hai nghiệm tương ứng với đáp án $C$ và $D$. Rõ ràng khoảng thời gian từ đáp số $D$ tương ứng với tình huống hành khách chạy qua cửa toa xe nhưng sau đó toa tàu lại lao tới.

Và một lưu ý quan trọng nữa. Tại lời giải bài toán, chúng tôi giả định rằng hành khách chắc chắn sẽ dùng hết vali của mình. Tuy nhiên, ở tốc độ hành khách $v < \sqrt{2al}$ điều này không phải ngẫu nhiên. Công thức cuối cùng nhất thiết phải phản ánh rằng chỉ khi đạt tốc độ cao (trong trường hợp của chúng tôi là $v \geq \sqrt{2al}$) thì hành khách mới đồng ý có vali riêng của mình.

Hãy xem xét một bài toán khác dành cho học sinh lớp mười.

Bài toán 6. Một cabin được đặt thẳng đứng có chiều dài $l$, mở bằng dấu, được ngâm một nửa trong bình có rue. Ống được đóng lại bằng ngón tay và lấy ra khỏi rutui. Chiều dài $x$ của lượng rutui còn lại trong ống là bao nhiêu? Áp suất khí quyển được cân bằng rất nhiều.rutui độ cao $H$. Quá trình này được coi là đẳng cự.

Có thể đáp số:

A. $x = \frac{H + l - \sqrt{H^2 + l^2}}{2}$;

B. $x = \frac{H + l + \sqrt{H^2 + l^2}}{2}$;

C. $x = \frac{(H + l)^2 - \sqrt{(H + l)^3 - \frac{Hl}{2}}}{2}$;

D. $x = \frac{H + l - \sqrt{H^2 + \frac{l^2}{2}}}{2}$;

E. $x = \frac{H + l - \sqrt{H^2 + 2Hl + 2l^2}}{2}$.

bài toán này dành cho học sinh lớp 10, nhưng ngay cả học sinh lớp 7 cũng sẽ dễ dàng nhận thấy rằng trong đáp số $C$ có ​​những vấn đề tiềm ẩn về chiều. Tất nhiên, bạn không thể trừ mét vuông khỏi mét khối. May mắn thay, đáp số còn lại đã vượt qua quá trình kiểm tra kích thước.

Chỉ cần xác định rằng hai đáp số – $E$ và $B$ – là không chính xác là đủ. Thật vậy, đáp số $E$ không phù hợp, vì độ dài $x$ là âm đối với rất nhiều rutui:

$$\sqrt{H^2 + 2Hl + 2l^2} = \sqrt{(H + l)^2 + l^2} > H + l.$$

Và trong đáp số $B$ độ dài của $x$ lớn hơn độ dài của $l$.rutui:

$$\sqrt{H^2 + l^2} \geq l, \quad x = \frac{H + l + \sqrt{H^2 + l^2}}{2} > \frac{2l}{2} = l.$$

⟦folio 50⟧

---
running_head:
folio:
---

Vẫn còn phải lựa chọn giữa câu trả lời A và D. Chúng ta có thể tiến hành một thí nghiệm tinh thần... trên Mặt trăng. Vì không có không khí nên không có gì để giữ bánh lái trong ống và nó phải chảy ra ngoài hoàn toàn. Nói cách khác, tại $H \rightarrow 0$ phải có $x \rightarrow 0$. Điều này chỉ tương ứng với đáp số A, điều này đúng.

Điều thú vị là nếu một người ngay lập tức đồng ý chỉ sử dụng đoạn giới hạn $H \rightarrow 0$, thì chỉ với sự trợ giúp của nó, người ta mới có thể loại bỏ tất cả đáp số không chính xác.

Hãy chuyển sang lời giải bài toán. Chúng ta ký hiệu $p$ – áp suất không khí trong ống sau khi lấy ra, $\rho$ – mật độ của thủy ngân. Áp suất khí quyển $p_0 = \rho g H$. Trong quá trình sản xuất $p_0 l/2 = p(l - x)$. Điều kiện cân bằng của lượng thủy ngân trong ống là: $p = p_0 - \rho g x$. Điều này cho kết quả đúng đáp số A.

bài toán được thảo luận ở trên cho thấy nghiên cứu đáp số có thể hiệu quả như thế nào. Tuy nhiên, đôi khi nghiên cứu này có thể bắt đầu khi phân tích chính điều kiện bài toán. Hãy xem xét điều này bằng ví dụ bài toán từ phiên bản Kỳ thi Thống nhất.

Bài toán 7. Dưới tác dụng của một lực nằm ngang không đổi $\vec{F}$, một cái nêm có khối lượng $M = 1$ kg chuyển động dọc theo mặt phẳng nằm ngang nhẵn của bàn (hình 3). Theo Sherakhova-

Hình 3

bề mặt của cái nêm tạo một góc $\alpha = 30^\circ$ với đường chân trời, trượt đều (so với cái nêm) với một khối có khối lượng $m = 0,2$ kg. Hệ số giữa khối và nêm là $\mu = 0,6$. Tìm mô hình gia tốc a của nêm. Bỏ qua sức cản của không khí. Tạo hình biểu thị các lực tác dụng lên khối.

Có thể đáp số:

A. $a = \frac{F - mg(\mu \cos \alpha - \sin \alpha)}{M + m}$;

B. $a = g \frac{\mu + tg \alpha}{\mu tg \alpha + 1}$;

C. $a = \frac{m}{M + m} \frac{\mu - tg \alpha}{\mu tg \alpha + 1} g$;

D. $a = g \frac{\mu - tg \alpha}{\mu tg \alpha + 1}$;

E. $a = g \frac{\mu + tg \alpha}{\mu tg \alpha - 1}$.

Một số vấn đề về SỬ DỤNG có một đặc điểm thú vị: sự hiện diện của dữ liệu được mô tả không nên đưa vào đáp số. Để thành công lời giải như bài toán, bạn nhất định phải học cách nhận biết dữ liệu bổ sung này.

Lưu ý rằng trong các điều kiện của bài toán này, các giá trị số của bốn đại lượng vật lý ($M, m, \alpha$ và $\mu$) và gia tốc trung tính của rơi tự do ($g = 10 \text{ m/c}^2$) được chỉ định rõ ràng. Tuy nhiên, giá trị bằng số của lực $F$ tác dụng lên nêm bị thiếu. Do đó, giá trị của nó không thể được đưa vào đáp số, có nghĩa là đáp số A không đúng. Nhưng còn gia tốc của cái nêm khi không biết độ lớn của lực $F$ thì sao?

Ở đây chúng ta sẽ được trợ giúp bởi thực tế là theo các điều kiện bài toán khối trượt đều trên nêm. Do đó, gia tốc của vật và nêm so với mặt đất là như nhau. Hóa ra là chúng ta không thể sử dụng định luật thứ hai của Newton cho hình nêm và do đó, khối lượng $M$ của hình nêm không được đưa vào đáp số. Tuy nhiên, người đọc tinh ý có thể nhận thấy rằng các điều kiện đòi hỏi phải tránh các hình vẽ biểu thị lực chỉ tác dụng lên khối. Manh mối này xác nhận giả định của chúng ta rằng khối lượng của hình nêm trong lời giải sẽ không được tìm thấy.

Đáng chú ý là đáp số không chỉ bao gồm khối lượng $M$ của hình nêm mà còn bao gồm khối lượng $m$ của khối. Thật vậy, khi phân tích khả năng của đáp số và lại dựa vào thứ nguyên, không khó hiểu rằng để xác định gia tốc $a$ trong cách sắp xếp của chúng ta chỉ có một giá trị ở cùng một vị trí - gia tốc rơi tự do $g$ và hai đại lượng không thứ nguyên - hệ số ma sát $\mu$ và góc $\alpha$. Tỷ lệ khối lượng $m/M$ cũng có thể bằng đáp số, nhưng, như chúng tôi đã phát hiện ra, khối lượng $M$ của hình nêm không nên lọt vào nó, điều đó có nghĩa là khối lượng của khối cũng không thể lọt vào.

Chúng ta còn lại ba "không khối lượng" đáp số. Một trong số chúng – EG – bị loại bỏ, vì nó được phân bổ dưới dạng “trừ” trong mẫu số: tại $\mu tg \alpha = 1$gia tốc của nêm sẽ có xu hướng tiến tới vô cùng. Cuối cùng, bạn cần chọn giữa đáp án B và D. Điểm khác biệt duy nhất trong các đáp án này là dấu ở tử số của phân số. Chúng ta hãy nhớ bài toán về

⟦folio 51⟧

---
running_head:
folio:
---

khối trên mặt phẳng nghiêng. Dễ dàng chứng minh rằng tại $\mu < tg\alpha$ vật trượt xuống dọc theo mặt phẳng, tại $\mu > tg\alpha$ nó đứng yên so với mặt phẳng, và tại $\mu = tg\alpha$ vật hoặc nằm trên nó (tại $v_0 = 0$) hoặc trượt đều (tại $v_0 \neq 0$). Để phân tích sâu hơn về đáp số, chúng ta biến nêm chuyển động thành mặt phẳng nghiêng đứng yên: $a = 0$. Từ đáp số D theo sau là $\mu = tg\alpha$. Trong khi đó đáp số B tạo ra $\mu = -tg\alpha$ vô lý. Chúng tôi mời bạn đọc tự mình tìm hiểu bản chất vật lý của sự xuất hiện của dấu trừ trong biểu thức đúng D của gia tốc tại $\mu < tg\alpha$ là gì.

Bây giờ chúng ta hãy đưa ra kết quả ngắn lời giải bài toán. Vì theo điều kiện, khối chuyển động đều so với nêm nên gia tốc của nêm và khối so với mặt đất là như nhau. Hãy hướng trục $x$ theo chiều ngang và trục $y$ theo chiều dọc. Khi đó, theo định luật II Newton cho hình chiếu lên các trục này

$$ma = F_{\text{tp}} \cos \alpha - N \sin \alpha,$$
$$0 = F_{\text{tp}} \sin \alpha + N \cos \alpha - mg.$$

Có tính đến việc khi trượt $F_{\text{tp}} = \mu N$, chúng ta thu được

$$ma = N (\mu \cos \alpha - \sin \alpha),$$
$$mg = N (\mu \sin \alpha + \cos \alpha).$$

Chia phương trình thứ nhất cho phương trình thứ hai, ta có

$$\frac{a}{g} = \frac{\mu \cos \alpha - \sin \alpha}{\mu \sin \alpha + \cos \alpha},$$

Ở đâu

$$a = \frac{g (\mu - tg\alpha)}{\mu tg\alpha + 1} \approx 0,17 \text{ m/c}^2.$$

Việc gặp phải các trường hợp đáp số vượt qua nhiều giai đoạn xác minh không quá phổ biến và có vẻ rất hợp lý, nhưng một trong những trường hợp đặc biệt lại mâu thuẫn với đáp số. Điều này có thể hiệu quả nếu chúng ta không chú ý đến phạm vi giá trị có thể chấp nhận được. Ví dụ ở đây, thoạt nhìn có một số bài toán.

Bài toán 8. Một lực $\vec{F}$ hướng lên một góc $\alpha$ so với đường chân trời (hình 4) tác dụng lên viên phấn có khối lượng $m$, nằm trên một mặt phẳng nằm ngang. Hệ số tiếp xúc giữa vật và bề mặt là $\mu$. Tìm gia tốc $a$ của vật.

Lời giải bài toán có vẻ là điều hiển nhiên. Viết phương trình định luật II Newton theo hình chiếu lên trục hoành và trục tung:

$$F \cos \alpha - F_{\text{tp}} = ma,$$
$$N + F \sin \alpha - mg = 0.$$

Chúng ta biết được điều đó khi trượt $F_{\text{tp}} = \mu N$. Sau đó, gia tốc mong muốn của cơ thể

$$a = \frac{F \cos \alpha - \mu (mg - F \sin \alpha)}{m}.$$

Đáp số đã nhận được, nhưng... sai. Hãy thử tìm ra lỗi bằng cách đọc lại các điều kiện và phân tích lời giải của chúng tôi. Có sự mâu thuẫn nào trong đó không? Rõ ràng là ở những giá trị nhỏ của lực $F$ vật vẫn chưa bắt đầu chuyển động mà vẫn đứng yên. Để xác định độ lớn của lực ma sát, chúng ta sử dụng công thức $F_{\text{tp}} = \mu N$, giả sử vật đang trượt. Đó là lý do tại sao, khi thay thế đáp số $F = 0$ vào của chúng tôi, chúng tôi nhận được $a = -\mu g$ khó xử.

Nhưng đó không phải là tất cả! Và điều gì sẽ xảy ra với giá trị lực lớn $F$? Xin lưu ý rằng cùng với sự tăng trưởng của $F$, lực của phản lực hỗ trợ thông thường $N$ giảm dần và tại $F = mg/\sin \alpha$ nó trở thành bằng 0, tức là cơ thể tách ra khỏi điểm hỗ trợ. Hai lực đồng thời biến mất: $\vec{N}$ và $\vec{F}_{\text{tp}}$, vật chuyển động dưới tác dụng của hai lực còn lại: $\vec{F}$ và $\vec{m}\vec{g}$. Gia tốc có thể được tìm bằng cách viết phương trình định luật thứ hai Newton dưới dạng vectơ: $\vec{F} + \vec{m}\vec{g} = m\vec{a}$. Từ hình 5 sử dụng định lý cosine $(ma)^2 = F^2 + (mg)^2 - 2Fmg \sin \alpha$ người ta có thể dễ dàng tìm được mô hình gia tốc vật:

$$a = \frac{\sqrt{F^2 + (mg)^2 - 2Fmg \sin \alpha}}{m}.$$

Nếu muốn, sử dụng định lý sin, người ta có thể tìm được góc mà gia tốc của vật hướng về phía chân trời.

⟦folio 52⟧

---
running_head:
folio:
---

Bây giờ cuối cùng chúng ta cũng có thể viết ra đáp số chính xác:
$$a = 0 \text{ при } 0 \leq F \leq \frac{mg}{\cos \alpha + \mu \sin \alpha},$$
$$a = \frac{F \cos \alpha - \mu (mg - F \sin \alpha)}{m}$$
tại $$\frac{mg}{\cos \alpha + \mu \sin \alpha} < F \leq \frac{mg}{\sin \alpha},$$
$$a = \frac{\sqrt{F^2 + (mg)^2 - 2Fmg \sin \alpha}}{m} \text{ при } F \geq \frac{mg}{\sin \alpha}.$$
Khi tiến hành phân tích đáp số đôi khi vô tình gặp phải một tình huống nghịch lý. Và chỉ có sự hiểu biết sâu sắc về bản chất khả năng ứng dụng của các định luật vật lý mới có thể phần nào giúp chúng ta thoát khỏi tình thế khó khăn. Hãy xem xét điều này bằng ví dụ sau bài toán.

Bài toán 9. Một quả bóng có khối lượng $m_1 = 2$ kg, đang chuyển động với tốc độ $v = 3$ m/s, va chạm với một quả bóng đứng yên có khối lượng $m_2 = 3$ kg. Giữa các quả bóng, chúng ta tạo ra tác động vào trung tâm, do đó quả bóng tấn công dừng lại. Bao nhiêu cây chổi $Q$ được thả ra khi va chạm?

Lời giải điều này bài toán, theo quy luật, không gây khó khăn nghiêm trọng. Thật vậy, hiển nhiên rằng việc áp dụng tiêu chuẩn định luật bảo toàn động lượng
$$m_1v = m_2u$$
và định luật bảo toàn năng lượng
$$Q = \frac{m_1v^2}{2} - \frac{m_2u^2}{2},$$
chúng tôi nhanh chóng đến đáp số
$$Q = \frac{m_1v^2}{2}\left(1 - \frac{m_1}{m_2}\right) = \frac{(m_2 - m_1)m_1v^2}{2m_2} = 3 \text{ Дж.}$$

Nếu bạn đã có thói quen phân tích đáp số nhận được, chắc chắn bạn sẽ chú ý đến dấu “trừ” trong ngoặc đơn. Hóa ra một đất nước của sự vật: nếu khối lượng của các quả bóng bằng nhau thì nhiệt sẽ không tỏa ra khi va chạm. Hơn nữa, chúng ta thu được một kết quả bên ngoài thậm chí còn lớn hơn nếu chúng ta giả sử rằng quả bóng tới sẽ nặng hơn quả bóng đứng yên. Thật vậy, với $m_1 > m_2$ $Q < 0$. Hóa ra là trong trường hợp này, khi va chạm, nhiệt không những không được giải phóng mà còn được “bơm” vào hệ thống các quả bóng. Có sự mâu thuẫn giữa những gì chúng tôi thu được đáp số và ý nghĩa vật lý.

Chúng ta hãy thử tìm hiểu lý do. Vì mục đích này, chúng ta không thể tìm được sự giúp đỡ nào tốt hơn các định luật bảo toàn. Nếu động lượng của quả bóng tới bằng $p$ thì quả bóng thứ hai có cùng động lượng sau va chạm. Năng lượng ban đầu của hệ nằm ở quả bóng đầu tiên và bằng $E_1 = p^2/(2m_1)$. Sau va chạm, năng lượng truyền cho quả bóng thứ hai: $E_2 = p^2/(2m_2)$. Với dạng ký hiệu này, có thể thấy ngay rằng nếu khối lượng của các quả bóng bằng nhau thì động năng của chúng bằng nhau, nghĩa là vật không được giải phóng trong hệ. Đây là điều sẽ xảy ra trong một va chạm đàn hồi tuyệt đối của những quả bóng có cùng khối lượng. Một điều hiển nhiên là nếu một quả bóng nặng hơn chạm vào trong các điều kiện thì nó không thể giữ nguyên (nếu không điều này sẽ dẫn đến vi phạm định luật bảo toàn năng lượng). Vì vậy, trường hợp đặc biệt ($m_1 > m_2$) gây ra sự hiểu lầm của chúng ta trong phân tích đáp số đơn giản là không thể xảy ra, vì nó mâu thuẫn với điều kiện bài toán, tức là quả bóng bay ra ngoài ngay sau khi va chạm.

***

Tóm lại, chúng tôi thấy rằng các ví dụ được thảo luận ở trên đã thuyết phục người đọc về sự cần thiết và tầm quan trọng của việc phân tích chữ cái đáp số trong các bài toán vật lý. Các bài tập sau đây được gợi ý như là một bài tập luyện. Tuy nhiên, chúng không nên chỉ giới hạn ở chúng. Điều cực kỳ quan trọng là phát triển thói quen không bỏ đáp số trong một nhiệm vụ mà không phân tích thêm. Mục đích này có thể được phục vụ bằng nhiều tài liệu khác nhau của tạp chí «Kvant», chủ yếu là [3] và [4].

Bài tập

1. Một phần ba toàn bộ đường dẫn được tự động hóa ở tốc độ $v_1$, sau đó một phần tư toàn bộ thời gian ở tốc độ $v_2$, phần còn lại ở tốc độ $v_3$. Tốc độ trung bình của $v_{cp}$ số tự động là bao nhiêu? Có thể đáp số:
A. $v_{cp} = \frac{3v_1v_2v_3}{v_1v_2 + v_2v_3 + v_1v_3}$;
B. $v_{cp} = \frac{3v_1v_2v_3}{v_1 + v_2 + v_3}$;
C. $v_{cp} = \frac{3v_1(v_2 + 3v_3)}{2(4v_1 + v_3)}$;
D. $v_{cp} = \frac{3v_1(v_2 + 3v_3)}{4(2v_1 + v_3)}$.

2. Một hình trụ đồng nhất có khối lượng $m$ có diện tích mặt cắt ngang $S$ nổi trên ranh giới của chất lỏng bất động với mật độ $\rho_1$ và $\rho_2$ (hình 6). Bỏ qua sức cản của chất lỏng, xác định chu kỳ dao động nhỏ theo phương thẳng đứng của hình trụ. Có thể đáp số:
A. $T = 2\pi \sqrt{\frac{m}{\left(\rho_2 + \rho_1\right)gS}}$;
B. $T = 2\pi \sqrt{\frac{m}{\left(\rho_2 - \rho_1\right)gS}}$;
C. $T = 2\pi \sqrt{\frac{m}{\left(\rho_2 \rho_1\right)gS}}$;

⟦folio 53⟧

---
running_head:
folio:
---

3. Hai ô tô đang tiến đến một giao lộ dọc theo những đường vuông góc với nhau với tốc độ không đổi $v_1$ và $v_2$. Tại thời điểm ô tô thứ nhất đến ngã tư thì ô tô thứ hai cách đó một khoảng $l$. Xác định khoảng cách tối thiểu $d_{\min}$ giữa các ô tô khi chúng đang chuyển động. Có thể đáp số:

A. $d_{\min} = l \frac{v_1^2 - v_2^2}{v_1^2}$;
B. $d_{\min} = l \frac{v_1^2 + v_2^2}{v_1}$;
C. $d_{\min} = l \frac{v_2}{\sqrt{v_1^2 + v_2^2}}$;
D. $d_{\min} = l \frac{v_1}{\sqrt{v_1^2 + v_2^2}}$.

4. Trong thời gian nào $t$ một vật có khối lượng $m$ sẽ trượt khỏi một mặt phẳng nghiêng có độ cao $h$ với góc nghiêng $\beta$, nếu nó chuyển động xuống đều dọc theo một mặt phẳng nghiêng với góc nghiêng $\alpha$? Có thể đáp số:

A. $t = \sqrt{\frac{2h \cos \alpha \cos \beta}{g (\sin \alpha + \sin \beta)}}$;
B. $t = \sqrt{\frac{2gh}{\sin \beta \sin (\beta - \alpha)}}$;
C. $t = \sqrt{\frac{2h \cos \alpha}{g \sin \beta \sin (\beta - \alpha)}}$;
D. $t = \sqrt{\frac{2h \sin \alpha}{g (\cos \alpha + \sin \beta)}}$.

5. Xi lanh cách nhiệt được chia thành hai phần bằng vách ngăn cách nhiệt có van. Khi van đóng, trong một phần của hình trụ có thể tích $V_1$ có heli ở áp suất $p_1$ và nhiệt độ $T_1$, còn ở phần còn lại của hình trụ có thể tích $V_2$ có neon ở áp suất $p_2$ và nhiệt độ $T_2$. Tìm nhiệt độ $T$ của khí sẽ tích tụ trong xi lanh sau khi mở van. Có thể đáp số:

A. $T = \frac{T_1 T_2 (p_1 V_1 + p_2 V_2)}{p_1 V_1 T_2 + p_2 V_2 T_1}$;
B. $T = \frac{p_1 V_1 T_2 + p_2 V_2 T_1}{T_1 T_2 (p_1 V_1 + p_2 V_2)}$;
C. $T = \frac{T_1 T_2 (2 p_1 V_1 + p_2 V_2)}{p_1 V_1 T_2 + p_2 V_2 T_1}$;
D. $T = \frac{2 T_1 T_2 (p_1 V_1 + p_2 V_2)}{p_1 V_1 T_2 + p_2 V_2 T_1}$.

6. Một nguồn dòng điện có EMF $\varepsilon$ và điện trở trong $r$ cùng ba điện trở có điện trở $R_1, R_2$ và $R_3$ được nối theo mạch như ở hình 7. Tìm dòng điện chạy qua điện trở $R_1$. Có thể đáp số:

A. $I_1 = \varepsilon R_1 / \left((R_3 + r)(R_1 + R_2) + R_1 R_2\right)$;
B. $I_1 = \varepsilon R_2 / \left((R_3 + r)(R_1 + R_2) + R_1 R_2\right)$;
C. $I_1 = \varepsilon R_2 / \left((R_3 + r)(R_1 + R_2) - R_1 R_2\right)$;
D. $I_1 = \varepsilon R_1 R_2 / \left((R_3 + r)(R_1 + R_2) + R_1 R_2\right)$.

7. Nêm ép lên bức tường thẳng đứng với lực bằng bao nhiêu nếu đặt một tải trọng có khối lượng $m$ (hình 8) lên nó? Góc ở đáy nêm là $\alpha$. Hệ số ma sát giữa tải trọng và bề mặt nêm là $\mu$, giữa sàn và nêm không có ma sát. Có thể đáp số:

A. $F = mg \cos \alpha$;
B. $F = mg \cos \alpha (\sin \alpha + \mu \cos \alpha)$;
C. $F = mg \cos \alpha (\sin \alpha - \mu \cos \alpha)$;
D. $F = mg \cos \alpha (\mu \cos \alpha - \sin \alpha)$.

Chúng tôi cảnh báo ngay cho người đọc: trong số đáp số này không có cái nào đúng. Hãy thử thêm một trong các đáp số được đề xuất để nó trở nên chính xác.

Văn học

1. A. Pais. Hoạt động khoa học và cuộc đời của Albert Einstein. - M.: Nauka, Tòa soạn chính văn học vật lý và toán học, 1989.
2. L. Tarasov. Tính đối xứng trong các bài toán vật lý. - «Kvant», 1978, số 6.
3. R. Bạc hà. Cách kiểm tra đáp số. - «Kvant», 1970, số 12.
4. G. Meledin. Có thể kiểm tra đáp số? - «Kvant», 1979, số 7.
