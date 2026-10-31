---
id: 1982-9-kamyishko-pol-dirak-i-zadacha-o-treh-ryibakah-fe0a667b
issue: kvant_1982_9
year: 1982
number: "9"
title: Paul Dirac và bài toán về ba ngư dân
authors:
  - Камышко И.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 33
page_last: 33
page_labels: "31"
tag: 7SRE
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 5e90ffc4480b346af850402e595d62eef6dae42873c35b8602148f5af00bfa7d
prompt_sha256: draft-1
translated_from: content/ru/1982/09/articles/09_kamyishko-pol-dirak-i-zadacha-o-treh-ryibakah-fe0a667b.md
source_content_sha256: 7bf86d67d92aa8e611288dccdb8e722059b9434d29b889023a75cccbecad08a5
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 31⟧

Rất có thể, chính tình tiết này trong cuộc đời của Paul Dirac, người giàu chiến thắng sáng tạo, đã góp phần làm xuất hiện một huyền thoại, đã kết thúc cách đây nhiều năm dưới nhiều phiên bản khác nhau theo các cuốn sách khoa học phổ thông.

Anh ấy nói rằng khi còn trẻ, anh ấy đã tình cờ gặp được bài toán này: Ba ngư dân đang đánh cá trong một đêm tối. Mệt mỏi, họ đi ngủ mà không chia mẻ đánh bắt được. Vào lúc bình minh, một người trong số họ thức dậy và không muốn làm phiền đồng đội của mình nên chia con cá thành ba phần bằng nhau; Sau khi nhận phần của mình, anh ấy về nhà. Trong quá trình chia, một con cá thừa và anh ta đã ném nó xuống biển. Sau đó người thứ hai tỉnh dậy. Không biết người đầu tiên đã bỏ đi phần của mình, anh ta cũng chia con cá thành ba phần, lấy một phần cho mình rồi bỏ đi, còn anh ta cũng như người đầu tiên, ném số cá thừa mình có xuống biển. Cuối cùng, người đánh cá thứ ba cũng tỉnh dậy. Không biết hai người đầu đã làm gì, anh ta làm theo ý họ, tức là chia con cá thành ba phần, lấy một phần ba cho mình, còn lại thì vớt số cá còn lại xuống biển rồi về nhà. Câu hỏi là, có bao nhiêu con cá đã được đánh bắt?

Đáp số (do Dirac): "Bắt được... khoảng hai con cá." Thật dễ dàng để kiểm tra xem mọi thứ đều chính xác về mặt hình thức. Người đánh cá đầu tiên, chỉ phát hiện được hai con cá (!), ném ra một con cá và lấy riêng một phần ba (-3) con cá còn lại. Người đánh cá thứ hai và thứ ba sẽ làm điều tương tự, mỗi người cũng sẽ câu cá trong một khoảng thời gian đáng kinh ngạc. Và mặc dù, theo lời khai của chính nhà vật lý nổi tiếng, điều này lời giải là do giáo sư toán học J. Whitehead từ Oxford* kể cho ông nghe), có thể hiểu được các tác giả của “truyền thuyết về Dirac và những con cá tiêu cực”. Thật khó để tìm ra một ví dụ đơn giản và tao nhã hơn có thể minh họa rõ ràng tính xác thực của ý tưởng và niềm tin vào “hiệu quả đáng xấu hổ của toán học trong khoa học tự nhiên” (như một người đoạt giải Tiểu thuyết khác, nhà vật lý người Mỹ Yu. Wigner, đã nói) - những phẩm chất là trụ cột của vật lý và các nhà vật lý hiện đại.

Nhưng bài toán về ngư dân tự nó đã là tình yêu rồi. Hãy cố gắng giải quyết nó. Hãy dịch các điều kiện sang ngôn ngữ phương trình. Gọi $N = N_0$ là số lượng cá đánh được, $N_1$ số cá còn lại sau lần chia đầu tiên, $N_2$ - sau lần chia thứ hai, $N_3$ - sau lần chia thứ ba. Khi đó, hiển nhiên là, $N_1 = \frac{2}{3}(N_0 - 1)$ và nói chung, cho $k = 0, 1, 2$
$$N_{k+1} = \frac{2}{3}(N_k - 1).$$

Chúng ta cần tìm một số nguyên $N$ sao cho cả hai số $N_1, N_2$ và $N_3$ đều là số nguyên. Chúng tôi cũng yêu cầu tất cả chúng đều không âm. Hơn nữa, với ràng buộc này, bài toán, được đặt, có vô số lời giải. Chúng ta sẽ cố gắng rút ra công thức tổng quát cho số $N$.

Bây giờ chúng ta hãy từ bỏ điều kiện không tiêu cực (!). Lưu ý rằng bài toán thừa nhận lời giải và chỉ một sao cho tất cả $N_k$ đều bằng cùng một số $D$. Từ (1) cho số $D$ ta thu được phương trình $D = \frac{2}{3}(D - 1)$, từ đó $D = -2$. Đây là "lời giải Dirac". Bây giờ giả sử $(N_k)$ là một chuỗi tùy ý thỏa mãn mối quan hệ (1). Hãy xem xét sự khác biệt $N'_k$ của hai lời giải bài toán - $N_k$ và lời giải Dirac: $N'_k = N_k - D = N_k + 2$. Từ

$$N'_{k+1} = N_{k+1} - D = \frac{2}{3}(N_k - 1) - \frac{2}{3}(D - 1) = \frac{2}{3}(N_k - D) = \frac{2}{3}N'_k,$$

dãy $(N'_k)$ là một cấp số nhân có giá trị $\frac{2}{3}$. Kể từ đây,

$$N_k = N'_k - 2 = \left(\frac{2}{3}\right)^k N'_0 - 2 = \left(\frac{2}{3}\right)^k (N + 2) - 2.$$

(Cuối cùng xem trang 62)
