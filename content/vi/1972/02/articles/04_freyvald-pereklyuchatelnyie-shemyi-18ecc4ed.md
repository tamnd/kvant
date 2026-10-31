---
id: 1972-2-freyvald-pereklyuchatelnyie-shemyi-18ecc4ed
issue: kvant_1972_2
year: 1972
number: "2"
title: Mạch chuyển mạch
authors:
  - Фрейвалд Р. В.
rubric: osnovnye-stati
page_first: 18
page_last: 21
page_labels: 16, 18, 19
tag: TTKW
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 144e7678cbccbd43716e85dd2386f8f4f03c09550df48a7bea4e91dfe9cfc796
prompt_sha256: draft-1
translated_from: content/ru/1972/02/articles/04_freyvald-pereklyuchatelnyie-shemyi-18ecc4ed.md
source_content_sha256: db500156fa888fb4bb9ddf9c67c29bb62fc2c31f2084e6de9924373a79be11bb
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 16⟧

SƠ ĐỒ CHUYỂN ĐỔI

R. V. Freivald

Tại Tối ưu hóa toán học toàn liên minh V*), bài toán sau đây đã được đề xuất:

Một công tắc (Hình 1) có hai đầu vào và hai đầu ra có thể ở hai trạng thái khác nhau.

Hình 2 cho thấy một mạch liên lạc điện thoại có ba đầu vào và ba đầu ra, có đặc tính “phổ quát” sau:

Cơm. 1. Hình 2. Hình 3.

bằng cách thay đổi trạng thái của công tắc, bạn có thể thực hiện bất kỳ kết nối nào trong sáu kết nối của ba đầu vào với ba đầu ra khác nhau, nghĩa là

(Hãy kiểm tra điều này. Lưu ý rằng tổng số trạng thái khác nhau của mạch này là 2³=8, vì mỗi công tắc có thể ở hai trạng thái.)

a) Xây dựng một mạch có bốn đầu vào và bốn đầu ra sẽ là “phổ quát”, nghĩa là, bất kỳ kết nối nào trong số 24 kết nối có thể có của đầu vào và đầu ra sẽ được thực hiện.

b) Số lượng công tắc tối thiểu cần thiết cho một mạch điện như vậy là bao nhiêu?

b) Chúng ta gọi một mạch có n đầu vào và n đầu ra là n-phổ quát nếu

*) Để biết thêm thông tin về tối ưu hóa ngẫu nhiên, xem «Kvant» Số 11, 1971, trang 35-42.

⟦folio 18⟧

Chia thành các khối $A$ và $B$ sao cho 4 kết nối đi qua $A$ và 4 kết nối đi qua $B$. Khi làm như vậy, chúng ta phải đảm bảo rằng hai kết nối không đi qua cùng một đầu vào hoặc cùng một đầu ra của các khối $A$ và $B$.

Hãy xem xét đầu vào thứ nhất và thứ năm của mạch của chúng tôi. Mỗi trong số chúng có thể được kết nối với đầu vào đầu tiên của khối $A$ hoặc với đầu vào đầu tiên của khối $B$. Do đó, một trong các đầu vào này phải được kết nối với khối $A$, đầu vào còn lại với khối $B$, nếu không, hai kết nối sẽ được kết nối với cùng một đầu vào của một số khối. Các cặp đầu vào sau đây cũng phải được kết nối với các khối khác nhau: thứ 2 và thứ 6, thứ 3 và thứ 7, thứ 4 và thứ 8. Dễ dàng nhận thấy rằng điều kiện phân phối kết nối giữa các khối như vậy không chỉ cần thiết mà còn đủ để đảm bảo rằng các kết nối khác nhau trong mạch không đi qua cùng một đầu vào của các khối $A$ và $B$. Để tạo điều kiện tương tự cho đầu vào của khối $A$ và $B$, rất hữu ích khi chú ý đến tính đối xứng trong cách sắp xếp đầu vào và đầu ra của mạch. Chúng tôi kết luận rằng các cặp đầu ra mạch sau đây phải được kết nối với các khối khác nhau: thứ 1 và thứ 5, thứ 2 và thứ 6, thứ 3 và thứ 7, thứ 4 và thứ 8.

Chúng ta hãy mô tả trong hình những mối quan hệ giữa các liên kết khác nhau của cùng một hợp chất. Mỗi kết nối riêng lẻ sẽ được biểu thị bằng một hình chữ nhật, bên trong ghi đầu vào nào mà kết nối này kết nối với đầu ra nào. Nếu hai kết nối phải đi qua các khối khác nhau thì các hình chữ nhật tương ứng được kết nối bằng một đường thẳng. Trong trường hợp này, chúng ta sẽ vẽ một đường tuyến tính màu đỏ nếu có 4 điểm khác biệt ở đầu vào và màu xanh lam nếu có 4 điểm khác biệt ở đầu ra.

Ví dụ, kết nối

$$
\begin{array}{c c c c c c c c}
1 & 2 & 3 & 4 & 5 & 6 & 7 & 8 \\
\downarrow & \downarrow & \downarrow & \downarrow & \downarrow & \downarrow & \downarrow & \downarrow \\
3 & 8 & 1 & 6 & 2 & 7 & 5 & 4
\end{array}
$$

Cách này được mô tả trong Hình 7.

Dù kết nối là gì, chính xác một đường màu xanh và một đường màu đỏ sẽ xuất hiện từ mỗi hình chữ nhật. Do đó, mẫu luôn bao gồm một hoặc nhiều “vòng”. Hơn nữa, trong mỗi “vòng”, các đường màu đỏ và xanh lam xen kẽ nhau, nếu không thì hai đường cùng màu sẽ xuất hiện từ một hình chữ nhật nhất định. Do đó, mỗi “vòng” chứa một số primogol.

Sử dụng bản vẽ như vậy, có thể dễ dàng phân phối các kết nối giữa các khối để đáp ứng tất cả các hạn chế trên. Để làm điều này, bạn cần đảm bảo rằng các kết nối tương ứng với các hình chữ nhật được kết nối bằng một đường tuyến tính sẽ đi qua các khối. Do đó, trong mỗi “vòng” của hình, bạn cần chọn ngẫu nhiên một squat và tạo kết nối tương ứng với khối slick xuyên qua $A$ này, sau đó tạo kết nối tương ứng với khối sên xuyên qua tương ứng $B$, sau đó kết nối tương ứng

⟦folio 19⟧

shue sang hình chữ nhật tiếp theo, qua $A$, v.v. cho đến khi "vòng" đóng lại. Các kết nối tương ứng với hình chữ nhật đầu tiên và cuối cùng sẽ được thực hiện thông qua các khối khác nhau, vì số lượng hình chữ nhật trong “vòng” là số chẵn. Mạch phổ quát 8 (xem Hình 3) đã được chứng minh. Chúng tôi chỉ lưu ý rằng việc phân phối liên lạc giữa các khối luôn có thể được thực hiện sao cho một trong các công tắc (ví dụ: phía dưới bên trái) ở trạng thái được xác định trước. (Nói cách khác, công tắc này có thể được loại bỏ khỏi mạch, nhưng mạch không thể thay đổi thành phổ quát.) Sau đó, trong “vòng” chứa kết nối đi qua công tắc đã chọn, việc phân phối kết nối giữa các khối phải bắt đầu bằng kết nối này.

Để ước tính số lượng công tắc trong một mạch phổ quát $n$ tối thiểu, chúng ta sẽ xây dựng các mạch phổ quát $n$ với càng ít công tắc càng tốt. Bằng chứng trên của mạch 8 phổ (xem Hình 3) có thể dễ dàng khái quát hóa cho trường hợp có số lượng đầu vào bất kỳ. Phương pháp này giúp cho việc có một mạch 8 phổ có thể xây dựng được một mạch 16 phổ khá tiết kiệm, sau đó là mạch 32 phổ, v.v. Có thể tính toán rằng nếu $n=2^k$ và mạch (Hình 4) được sử dụng làm khối của mạch 4 phổ, thì mạch đó có các công tắc $2k \cdot 2^k - \frac{11}{4} \cdot 2^k = 2n \cdot \log_2 n - \frac{11}{4} \cdot n$. Nếu $n$ không bằng lũy ​​thừa toàn phần của hai thì bạn có thể sử dụng một mạch phổ quát cho một số lượng lớn đầu vào bằng lũy ​​thừa toàn phần của hai. Vì lũy thừa tuyệt đối gần nhất của hai vượt quá số đã cho $n$ không quá hai lần, nên đối với bất kỳ $n$ nào cũng có một mạch phổ quát $n$ chứa tối đa $4n \cdot \log_2 n$ công tắc.

(Về phần kết, xem trang 27.)
