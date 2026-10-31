---
id: 1978-11-integralom-po-schastlivyim-biletam-4a118026
issue: kvant_1978_11
year: 1978
number: "11"
title: Tích hợp - với vé may mắn!
rubric: raznoe
rubric_sub: Разное
page_first: 54
page_last: 55
page_labels: 52-53
tag: DSYF
lang: vi
source: kvant_digital
extraction: vision
content_sha256: e31305625e59729aba62fcba401a2bd89d82bbe04af1b07b2352fb75c8173079
prompt_sha256: draft-1
translated_from: content/ru/1978/11/articles/24_integralom-po-schastlivyim-biletam-4a118026.md
source_content_sha256: 5f56c8dd39ef40e15b21e14707705986703f349ca4afbb7e429e1857d19c2645
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 52⟧

Integalom - với vé riêng!

Người biên tập đã nhận được một lá thư từ độc giả cũ của chúng tôi B. Ivyakin. Trong đó ông đặt câu hỏi sau:
"Tạp chí đã xuất bản một số bài báo về vé may mắn. Tuy nhiên, chưa có công thức cuối cùng nào trong số đó. Mặc dù tôi thấy rõ rằng không thể thiết lập số lượng vé may mắn có 2 chữ số bằng một công thức đơn giản, nhưng đối với tôi, dường như một công thức như vậy nên tồn tại. Tôi đúng hay sai?
Rõ ràng là chúng tôi không trả lời những câu hỏi mơ hồ như vậy. Tuy nhiên, Boris thật may mắn - sau khi nhận được lá thư của anh ấy, chúng tôi ngay lập tức nhận được hai đáp số cho câu hỏi của anh ấy.
Chúng tôi nghĩ rằng những độc giả khác sẽ quan tâm đến công thức chứa trong đó.
(Chúng tôi xin nhắc bạn rằng một vé được gọi là may mắn nếu tổng của ba chữ số đầu tiên bằng tổng của ba chữ số cuối.)

Có nhiều vé may mắn không? Bạn có thường xuyên gặp họ không?

Vấn đề này đã được thảo luận trên các trang tạp chí của chúng tôi; Người ta thấy rằng trong số một triệu vé có số có sáu chữ số (từ 000.000 đến 999.999), có 55.252 vé may mắn, tức là cứ 18 vé thì có khoảng một vé may mắn.

Như thường lệ với các nhà toán học, bài toán tổng quát hơn cũng đã được giải - về số $C_{2n}$ số may mắn có 2 chữ số (rõ ràng khái niệm này là gì; ví dụ: 0 035 120 115 là số thứ mười may mắn). Một công thức rõ ràng cho $C_{2n}$ chưa được thiết lập - chỉ thu được các mối quan hệ lặp lại («Kvant», 1976, Số 12, trang 68).

Nhưng sau đó có hai lá thư được gửi tới người biên tập. Bức đầu tiên được gửi vào tháng 2 bởi M. Mnatsakanyan và A. Melikyan, và bức thứ hai - vào tháng 3 - bởi R. Aydagulov. Cả hai đều chứa cùng một công thức rõ ràng cho $C_{2n}$. Đây là công thức tuyệt vời này:

$$C_{2n} = \frac{1}{\pi} \int_{0}^{\pi} \left( \frac{\sin 10x}{\sin x} \right)^{2n} dx. \tag{1}$$

Điều thú vị là công thức này thu được bằng các phương pháp hoàn toàn khác nhau: M. Mnatsakanyan và A. Melikyan sử dụng các hàm tùy ý (tức là phân tích hàm), trong khi R. Aydagulov sử dụng phương pháp tổng lượng giác (lý thuyết số phân tích). Thật không may, những chứng minh của họ tuy không phức tạp nhưng vẫn vượt quá phạm vi toán học phổ thông và không thể đăng trên tạp chí của chúng tôi. Bây giờ chúng ta đưa ra một chứng minh cơ bản về công thức (1), sử dụng các quan hệ truy hồi đã thảo luận ở trên. Hãy nhắc nhở họ.

Để làm điều này, chúng ta hãy biểu thị bằng $P_m(s)$ số lượng các số có $m$ chữ số ($m=1, 2, 3,...$), tổng các chữ số của mỗi số đó bằng $s$. Do đó, $P_m(s)=0$ tại $s<0$ và $s>9m$. Rõ ràng là $P_m(0)=1$.

Vì số có $m$ chữ số có tổng các chữ số $s$ được lấy từ số có $(m-1)$ chữ số có tổng các chữ số $j$ (trong đó $s-9 \leq j \leq s$) nên chúng ta cộng các chữ số $s-j$, nên chúng ta có thể viết

$$P_m(s) = \sum_{j=s-9}^{s} P_{m-1}(j).$$

Đây là tỷ lệ được thảo luận ở trên. Thay $s+1$ cùng với $s$ vào chúng, sau khi trừ ta được

$$P_m(s+1) - P_m(s) = P_{m-1}(s+1) - P_{m-1}(s-9). \tag{2}$$

Làm cách nào để sử dụng mối quan hệ này để tính $P_m(s)$? Hãy nhìn vào hình. 1. Đối với một $m$ cố định, tất cả $P_{m-1}(s)$ (tức là tất cả hàng $(m-1)$) và ít nhất một phần tử của hàng thứ $P_m(s_0)$ $m$ đều đã biết, thì công thức (2) cho phép, di chuyển sang phải và ngược lại, để tính các phần tử còn lại của hàng thứ $m$ (giải thích!). Nhưng đối với bất cứ ai $m$

$$P_m(0) = 1 \tag{2'}$$

Và

$$P_1(s) = \begin{cases} 1, \text{ если } 0 \leq s \leq 9, \\ 0, \text{ если } s < 0 \text{ или } s > 9. \end{cases} \tag{2''}$$

⟦folio 53⟧

Như vậy, công thức (2), (2′), (2”) cho phép chúng ta tính được tất cả các số $P_m(s)$.

Hãy lấy bất kỳ số có 2 chữ số nào và thay thế các chữ số $n$ cuối cùng bằng phần bù của chúng lên đến 9. Sau đó, chúng ta nhận được một số có 2 chữ số có tổng các chữ số là 9n. Thật dễ hiểu rằng

$$C_{2n} = P_{2n}(9n).$$

Công thức (3) giúp tính được số $C_{2n}$.

Để chứng minh (1), ta đặt

$$\bar{P}_m(s) = \frac{1}{\pi} \int_0^{\pi} \left( \frac{\sin 10x}{\sin x} \right)^m \cos(9m-2s) x dx.$$

Hóa ra,

$$\bar{P}_m(s) = P_m(s).$$

Từ các công thức (3), (5) và (4) (1) suy ra ngay. Vì vậy, chúng ta chỉ cần chứng minh (5), trong đó chỉ cần kiểm tra xem các số $P_m(s)$ có thỏa mãn các đẳng thức (2), (2′), (2”) hay không là đủ. Thay (4) vào (2), ta thu được sự tương ứng

$$\frac{1}{\pi} \left\{ \int_0^{\pi} \left( \frac{\sin 10x}{\sin x} \right)^m \left[ \cos(9m-2s-2) x - \cos(9m-2s) \right] dx \right\} = \frac{1}{\pi} \left\{ \int_0^{\pi} \left( \frac{\sin 10x}{\sin x} \right)^m - 1 \left[ \cos(9m-9-2s-2) x - \cos(9m-9-2s+18) x \right] dx \right\},$$

trận đấu bình đẳng

$$\int_0^{\pi} \left( \frac{\sin 10x}{\sin x} \right)^m - 1 \left[ \frac{\sin 10x}{\sin x} \right] \left[ \cos(9m-2s-2) x - \cos(9m-2s-11) x - \cos(9m-2s+9) x \right] dx = 0,$$

điều này đúng (dễ dàng coi rằng biểu thức lượng giác trong ngoặc vuông cũng thực tế bằng 0).

Do đó, sự tương ứng lặp lại (2) cho $\bar{P}_m(s)$ được thỏa mãn. Vẫn còn phải kiểm tra cơ sở quy nạp (2′) và (2”). Sự tương ứng thứ hai trong số này có thể được xác minh trực tiếp (ví dụ: đối với $m=1$ và $s>9$ biểu thức số nguyên được chuyển thành tổng các cosin của các góc là bội số của $x$), nhưng (2′) không dễ chứng minh và chúng ta sẽ phải thực hiện một giải pháp thay thế.

Chúng ta hãy nhớ rằng cùng với (2′), việc kiểm tra bất kỳ sự tương ứng nào khác trên hàng thứ $m$ là đủ, ví dụ $\bar{P}_m(10m) = 0$ Đây không còn là một bài tập khó (nhưng rườm rà) về các phép biến đổi lượng giác mà chúng tôi sẽ dành cho người đọc. Điều này kết thúc việc chứng minh công thức (5).

Người đọc chăm chú có lẽ đã tự hỏi mình câu hỏi: công thức (4) đến từ đâu? Tất nhiên, về mặt công thức, chúng ta có thể giả định rằng chúng ta đã đoán nó giống như cách chúng ta “đoán” công thức (1). Trên thực tế, công thức (4), giống như công thức (1), được trích từ một bức thư của M. Mnatsakanyan và A. Melikayan, tức là kết quả cuối cùng đã được sử dụng. Xét cho cùng, phương pháp chứng minh của chúng tôi, không giống như phương pháp của P. Aydagulov và phương pháp của M. Mnatsakanyan và A. Melikayan, không giúp chúng tôi khám phá ra công thức (1) mà chỉ cho phép chúng tôi kiểm tra nó.

Để kết luận, xin mời bạn đọc chứng minh công thức (1) sau đây về số lượng cil trong hệ cil dựa trên cơ số $k$:

$$C_{2n}^k = \frac{1}{\pi} \int_0^{\pi} \left( \frac{\sin kx}{\sin x} \right)^2n dx.$$
