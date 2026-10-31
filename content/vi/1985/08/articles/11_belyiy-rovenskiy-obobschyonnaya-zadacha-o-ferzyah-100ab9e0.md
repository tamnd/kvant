---
id: 1985-8-belyiy-rovenskiy-obobschyonnaya-zadacha-o-ferzyah-100ab9e0
issue: kvant_1985_8
year: 1985
number: "8"
title: Tổng quát bài toán về quân hậu
authors:
  - Белый С. Б.
  - Ровенский Е. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 28
page_last: 29
page_labels: 26-27
tag: E7MN
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 57166dc65c62daae3001533500238af395738b8dc3708bdbeaf6e38c3e41119f
prompt_sha256: draft-1
translated_from: content/ru/1985/08/articles/11_belyiy-rovenskiy-obobschyonnaya-zadacha-o-ferzyah-100ab9e0.md
source_content_sha256: 6b4d13b5b98ebfc2522b15cdbe2a0555492c82dbfc91aecc10af9d7b0f8ff7cd
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 26⟧

Tổng quát bài toán về quân hậu

S. V. BELY,
E. A. ROVENSKY

Bài toán về quân hậu - việc đặt số quân hậu tối đa trên bàn cờ để chúng không đe dọa lẫn nhau và việc tìm ra số lượng tất cả các vị trí như vậy - từ lâu đã trở thành kinh điển. Vào thế kỷ 19, nhà toán học vĩ đại người Đức Carl Friedrich Gauss (1777–1855) đã giải quyết vấn đề này, và trong thế kỷ của chúng ta, nhà toán học và cyberNETIK Kolod Shenon xuất sắc người Mỹ (sinh năm 1916) đã chỉ ra mối liên quan trực tiếp của nó với các vấn đề về mã hóa chống ồn.

Gần đây, một khái quát thú vị về điều này bài toán đã xuất hiện liên quan đến việc sắp xếp số lượng quân hậu tối đa (Science and Life, 1982, No. 3, p. 73; «Kvant», 1983, No. 1, trang 3 khu vực): trên một bàn cờ, đặt số lượng quân hậu p tối đa sao cho mỗi quân hậu tấn công đúng k quân hậu (1<k<4). bài toán này do nhà toán học người Mỹ Scott Kim đặt ra và xuất bản trên J. Giải trí Toán học, 1979-80, tập. 12, không. 1, tr. 53 (một tạp chí của Mỹ chuyên xuất bản các bài báo có tính chất thú vị bài toán về toán học). Với k=0, chúng ta thu được bài toán cổ điển, với p_max=8. Hãy xem xét lý do tại sao công thức bài toán tạo ra ràng buộc k<4. Bài toán Kim đã giải được thương số (J. Toán giải trí, 1980-81, tập 13, số 1, trang 61-62). Được đặt tên:

$$p_{\text{max}} = 10 \text{ для } k = 1,$$
$$p_{\text{max}} = 14 \text{ для } k = 2.$$

Ví dụ về cách sắp xếp tương ứng được thể hiện trên Hình 1 và Hình 2.

Với k=3 và k=4, sự sắp xếp lần lượt là p=16 (ibid.) và p=21 (Scientific American, 1981, tập 245, số 6, trang 19), nhưng vẫn chưa rõ liệu những con số này có phải là mức tối đa hay không.

Trong bài toán này chúng ta sẽ chứng minh rằng $p_{\text{max}} = 18$ với k=3, (3)
$p_{\text{max}} = 21$ với k=4. (4)

Hình 3 và 4 cho thấy rằng đội hình có số lượng nữ hoàng này tồn tại. Lưu ý rằng sự sắp xếp với p=18 cho k=3 chưa được biết đến. Bây giờ chúng ta hãy thử tìm giới hạn trên của p.

Gọi p là số quân hậu và q là số hàng (dọc, ngang và chéo) mà trên đó có ít nhất một quân hậu đứng. Khi đó, nếu các quân hậu không tấn công lẫn nhau thì q=4p. Nhưng vì tổng số trận đánh bằng pk (mỗi quân hậu tấn công đúng k quân hậu) nên

$$q = 4p - \frac{pk}{2} \text{ или } r = \frac{2k}{8-k}.$$

Bây giờ chúng ta chứng minh (3). Tổng số chiều dọc, chiều ngang và đường chéo trên bảng n×n là 6n−2, do đó

$$q \leq 6n-2.$$

Từ (5) và (6) đối với bảng 8×8 ta thu được p<18.

⟦folio 27⟧

Hãy chứng minh (4). Vì các ô vuông ở góc của bàn cờ không thể bị quân hậu chiếm giữ (tại sao?), nên chúng ta có
$$q \leq 6n - 6.$$

Từ (5) và (7) cho bảng $8 \times 8$ ta tìm được $p \leq 21$.

Vậy là, bài toán Kima đã hoàn toàn giải quyết được. Chúng tôi chỉ cần nói thêm rằng cách sắp xếp tối đa các con hậu trong Hình 3 và 4 được tìm thấy bằng máy tính (việc này mất khoảng 30 phút tính toán trên máy tính với số phép tính 200 nghìn mỗi giây). Những độc giả biết cách lập trình có thể thử sức mình trong việc tạo ra một chương trình như vậy.

Bài toán cho nghiên cứu.
Một cách khái quát tự nhiên về bài toán của S. Kim là bài toán như sau:
Trên bàn cờ $n \times n$ đặt số quân hậu tối đa $p_{\max} = p(n, k)$ sao cho mỗi quân hậu tấn công chính xác $k$ quân hậu ($0 \leq k \leq 4$) và tìm số $N = N(n, k)$ đó

Khám phá tia X

(Để bắt đầu, xem trang 25)

cho bức xạ mạnh hơn (về cơ bản nó là ống tia X đầu tiên).

Roentgen tóm tắt các kết quả thu được trong tập tài liệu “Về một loại tia mới” xuất bản vào đầu tháng 1 năm 1896. Đồng thời, ông gửi những bức ảnh X-quang đầu tiên tới các nhà vật lý hàng đầu thế giới, trong đó có hình ảnh bàn tay của vợ ông. Xin vui lòng, không một khám phá vật lý nào đã khơi dậy được sự quan tâm to lớn và phổ quát như khám phá bằng tia X về những tia xuyên qua tường và cho phép người ta nhìn thấy những thứ vô hình. Các nhà vật lý ngay lập tức bắt đầu lặp lại những thí nghiệm đáng kinh ngạc, các nhà báo lấp đầy các trang báo bằng những báo cáo giật gân. Năm 1901, Roentgen trở thành người đầu tiên đoạt giải Nobel vật lý.

Các lĩnh vực ứng dụng tia X hiện đại rất khó liệt kê - y học, di truyền học, khiếm khuyết, phân tích cấu trúc tia X, phân tích quang phổ tia X, nghiên cứu các bức tranh cổ, pháp y...

Việc phát hiện ra tia X chiếm một vị trí nổi bật trong lịch sử khoa học - chính nhờ nó mà buổi bình minh của vật lý nguyên tử và hạt nhân đã bắt đầu. “Vào đầu năm 1896, vào đúng ngày ở Paris, người ta biết đến các thí nghiệm của Roentgen và nhu cầu về tia sáng phát ra từ các bức tường phát sáng... có hiệu quả,” A. Becquerel nói, “Tôi quyết định sử dụng xem có bất kỳ chất phát quang nào khác cũng phát ra tia hay không.” Giả định này hóa ra không chính xác, nhưng chất phóng xạ đã được phát hiện trong các thí nghiệm của Becquerel.

Và J. J. Thomson nhớ lại: "Tôi đã từng nghiên cứu tính dẫn điện của chất khí dưới tác dụng của lực điện trong một thời gian, nhưng thật khó để tìm ra bất kỳ phương pháp tạo ra tính dẫn điện nào hiệu quả và đáng tin cậy. Các tia mới đã loại bỏ khó khăn này... Các thí nghiệm vô cùng khó khăn trước khi phát hiện ra tia đã trở nên dễ dàng." Kết quả của những “thí nghiệm ánh sáng” này là sự khám phá ra electron của Thomson (vào mùa xuân năm 1897).

V. E. Yavelov
