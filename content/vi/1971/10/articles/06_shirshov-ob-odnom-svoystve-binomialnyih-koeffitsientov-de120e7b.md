---
id: 1971-10-shirshov-ob-odnom-svoystve-binomialnyih-koeffitsientov-de120e7b
issue: kvant_1971_10
year: 1971
number: "10"
title: Về một tính chất của hệ số nhị thức
authors:
  - Ширшов А. И.
rubric: osnovnye-stati
page_first: 18
page_last: 22
page_labels: 16, 20
tag: 0H1J
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c9c729880cc191ce5cf73a618f8d6c980d215ab6b5c02825497254c0c1bcb4ad
prompt_sha256: draft-1
translated_from: content/ru/1971/10/articles/06_shirshov-ob-odnom-svoystve-binomialnyih-koeffitsientov-de120e7b.md
source_content_sha256: b30baeeb85f07444e3de8a0555091d2115bfc2d487f20eab9371136a9ba1b59f
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 16⟧

A. I. Shirshov

Trong «Kvant» Số 6 năm 1970, một bài báo của D. B. Fuks và M. B. Fuks “Số học của các hệ số sinh học” đã được xuất bản. Trong bài báo này, các tác giả đã đề xuất bài toán như sau: Đặt $p$ là số nguyên tố; tìm ra lũy thừa nào $p$ số $C_{p^{n+1}}^{p^n} - C_{p^n}^{p^{n-1}}$ chia hết

bài toán này đã thu hút sự chú ý của nhiều độc giả. Các biên tập viên đã nhận được thư từ V. G. Gaidalovich (Tashkent), S. P. Krutik (stanitsa Staro-Sherbinskaya, Lãnh thổ Krasnodar), học sinh lớp 9 A. Merkuverev (Leningrad), V. V. Prlensky (Moscow) và các mặt hàng khác sẽ cung cấp các mức độ khác nhau của lời giải trong số này bài toán.

Chúng tôi đã hỏi nhà đại số nổi tiếng của Liên Xô, thành viên tương ứng của Viện Hàn lâm Khoa học Liên Xô A.I. Shirshov làm sáng tỏ chi tiết về lời giải đặt bài toán.

Học sinh đã quen thuộc với nhiều cuốn sách và bài báo khoa học phổ thông về toán học. Chúng được viết đơn giản nhất có thể, chi tiết và dễ tiếp cận, bằng ngôn ngữ tươi sáng và sống động, với các ví dụ hấp dẫn và hình ảnh đầy màu sắc - để gây hứng thú cho người đọc và giúp họ có cơ hội dễ dàng hiểu tài liệu.

Các bài báo toán học phía máy chủ được viết trên các tạp chí khoa học uy tín như thế nào? Bài báo của A. I. Shirshov, thu hút sự chú ý của độc giả, đưa ra ý tưởng về phong cách trình bày toán học khoa học. Về nội dung, học sinh trung học có thể truy cập được, nhưng nó được viết cụ thể giống như cách viết các ghi chú, chẳng hạn như trên tạp chí “Báo cáo của Viện Hàn lâm Khoa học Liên Xô”.

Phong cách khoa học và toán học được đặc trưng bởi độ dốc và ngắn gọn. Theo quy định, phần trình bày được chia thành các bước riêng biệt - bổ đề, leo dần để chúng ta đạt được kết quả cuối cùng - định lý. Bài viết đầu tiên luôn chứa tuyên bố bài toán, giải thích về các khái niệm được giới thiệu và các ký hiệu được sử dụng cũng như tài liệu tham khảo về tài liệu. Các bằng chứng không được sao chép chi tiết - chỉ có ý tưởng của họ và quá trình lập luận chung được phác thảo. Do đó, bạn chỉ có thể đọc một bài báo như vậy bằng bút chì và giấy trên tay, khôi phục các phép tính trung gian; để hiểu được nội dung của nó đòi hỏi một lượng nỗ lực nhất định và sự suy ngẫm độc lập.

Người yêu toán chắc chắn sẽ thích thú tìm hiểu về phong cách trình bày toán học khoa học.

Trong bài viết [1], người ta đề xuất rằng các số có dạng $C_{p^{k+1}}^{p^k} - C_{p^{k-1}}^{p^{k-2}}$, trong đó $p$ là số nguyên tố, chia hết cho một số đủ cao $p$. Tuy nhiên, nhận định này chỉ được chứng minh trong trường hợp $p=2$ (Định lý 5 trong [1]).

Ghi chú này được dành cho việc chứng minh một định lý tổng quát hơn.

Tất cả các số $m, k, t, s$, v.v., được xem xét dưới đây đều là số tự nhiên và $p$ là số nguyên tố. Ký hiệu $(m, n)$, như thường lệ, có nghĩa là ước số phổ biến nhất của các số $m$ và $n$. Chúng ta sẽ sử dụng ký hiệu $[k, s]_n$ để biểu thị tích của tất cả các số tự nhiên $t$ sao cho $k \leq t \leq s$ và $(t, n)=1$; TRÊN-

⟦folio 20⟧

Nhận thấy rằng
$$1(p^{k-1}-1) \cdot 2(p^{k-1}-2) \dots \frac{1}{2}(p^{k-1}-1) \frac{1}{2}(p^{k-1}+1) = [1, p^{k-1}]_p,$$

chúng ta có thể viết:
$$[p^k - p^{k-1}, p^k]_p = [1, p^{k-1}]_p + p^{2k-1}(p-1)[1, p^{k-1}]_p \cdot \frac{1}{2} \left\{ \frac{2}{1(p^{k-1}-1)} + \dots \right\} + p^{4k-2}Q =$$
$$= [1, p^{k-1}]_p + \frac{1}{2} p^{2k-1}(p-1)[1, p^{k-1}]_p \times$$
$$\times \left\{ \frac{1}{1(p^{k-1}-1)} + \dots + \frac{1}{(p^{k-1}-1)1} \right\} + p^{4k-2}Q,$$

đó là điều lemmy chứng minh ở $p > 2$.
Trường hợp $p = 2$ được xét theo sơ đồ tương tự.
Bổ đề 12.

$$1^2 + 2^2 + \dots + (p-1)^2 + (p+1)^2 + \dots + (p^{k-1}-1)^2 =$$
$$= \frac{1}{6} p^{k-1}(p^{k-1}+1)(2p^{k-1}+1) - p^k L, \quad p > 2$$
(tất cả các số nguyên tố cùng nhau đến $p$ được viết ở phía bên trái).
Bằng chứng. Chỉ cần biểu diễn vế trái dưới dạng là đủ
$$\sum_{i=1}^{p^{k-1}} i^2 - p^2 \sum_{i=1}^{p^{k-2}} i^2$$

và tính cả hai tổng theo Bổ đề 1.
Định lý. Sự bình đẳng sau đây là công bằng:
$$C_{p^k}^{p^{k-1}} - C_{p^{k-1}}^{p^{k-2}} = p^{3k-1} R, \quad p > 3;$$
$$C_{3k}^{3k-1} - C_{3k-1}^{3k-2} = 3^{3k-2} S;$$
$$C_{2k}^{2k-1} - C_{2k-1}^{2k-2} = 2^{3k-3} T,$$

trong đó $k \geqslant 3$ và $R, S, T$ là số nguyên.
Việc chứng minh định lý được thực hiện bằng cách sử dụng tuần tự bổ đề 9, 11, 6, 12, 2.

Bình luận. Từ chứng minh định lý, người ta cũng thấy rằng các số $S$ và $T$ chỉ ra trong định lý lần lượt không chia hết cho 3 và 2. Tác giả không biết mọi việc diễn ra như thế nào trong trường hợp tổng quát - số $R$ chia hết hay không chia hết cho $p$.

Văn học được trích dẫn

1. Fuchs D. B., Fuchs M. B., Tính toán các hệ số biomp. «Kvant» Số 6, 1970, trang 17-25.
2. Sominsky I. S., Phương pháp quy nạp toán học. M., Fizmatgiz, 1961.
3. Egorov A. A., So sánh theo mô đun và số học của phần dư. «Kvant» Số 5, 1970, trang 27-33.

Ghi chú của biên tập viên. Là độc giả Yu. Trakhtman (Dnepropetrovsk) nói với chúng tôi rằng ông đã thu được một số số nhất định mà các số $R, S, T$ xuất hiện trong định lý lần lượt không chia hết cho $p, 3, 2$. Tuy nhiên, kết quả này được xây dựng dưới dạng thuật ngữ xa lạ với học sinh và được chứng minh bằng những phương pháp không tầm thường.
