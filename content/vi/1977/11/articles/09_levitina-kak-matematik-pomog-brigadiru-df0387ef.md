---
id: 1977-11-levitina-kak-matematik-pomog-brigadiru-df0387ef
issue: kvant_1977_11
year: 1977
number: "11"
title: Nhà toán học đã giúp Chuẩn tướng như thế nào
authors:
  - Левитина В.
rubric: raznoe
page_first: 42
page_last: 45
page_labels: 40-43
tag: RPLO
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 56b75182def17e3a59bef88520a42565c8cf8c8f6a0da30c2c99009f25ffccfe
prompt_sha256: draft-1
translated_from: content/ru/1977/11/articles/09_levitina-kak-matematik-pomog-brigadiru-df0387ef.md
source_content_sha256: 703fc8a9eb652169e2390217c796f98ea652bdc624fd3067784c51c4342b2096
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 40⟧

V. Levitina

Nhà toán học đã giúp Chuẩn tướng như thế nào

Mục tiêu chính của bài viết là chỉ ra rằng bài toán đơn giản nhất nảy sinh trong thực tế sẽ dẫn đến các khái niệm cơ bản của toán học một cách tự nhiên.

1. Quản đốc nhận được bài toán

Quản đốc của chúng tôi dẫn đầu một đội gồm 10 người phải xếp gạch ở hai nhà kho. Kho thứ nhất có 4 nghìn viên gạch, kho thứ hai có 8 nghìn viên. Kho được bố trí sao cho ít nhất sáu công nhân phải bốc hàng đồng thời vào kho thứ nhất và từ ba đến sáu công nhân có thể làm việc ở kho thứ hai. Quản đốc cần phân công công nhân sao cho mọi công việc được hoàn thành trong thời gian tối thiểu.

Thiếu tướng có thể làm gì? Ví dụ, như thế này: đầu tiên cử tất cả công nhân đến kho đầu tiên, và sau khi xếp hàng, sáu công nhân - số lượng tối đa cho phép - được chuyển sang kho thứ hai. Để đơn giản, giả sử mỗi công nhân mất một giờ để cắt một số viên gạch. Khi đó thời gian mà nhóm sẽ hoàn thành mọi công việc theo tiến độ này là rất cao, bằng $\frac{4}{10} + \frac{8}{6} = 1\frac{11}{15}$ (giờ).

Liệu cách tổ chức công việc như vậy có phải là tốt nhất? Nếu vậy thì tại sao? Và nếu không thì nó còn cách mức tối ưu bao xa? Bản thân Chuẩn tướng không thể trả lời những câu hỏi này. Còn bạn thì sao? Hãy thử xem - khi đó bạn sẽ đọc những đoạn văn sau về cuộc gặp gỡ của Chuẩn tướng với Nhà toán học mà Chuẩn tướng hướng tới nhiệm vụ của mình.

2. Nhà toán học tạo ra mô hình bài toán

Trước khi thực hiện lời giải bài toán, Nhà toán học phải tạo ra một mô hình toán học về nó.

Nếu chúng ta biểu thị bằng $u$ và $v$ số lượng ở kho thứ nhất và kho thứ hai thì tại từng thời điểm, các số $u$ và $v$ thỏa mãn các điều kiện sau:

1) $u \in \mathbb{Z}$ và $v \in \mathbb{Z}$,
2) $6 \leq u \leq 10$ hoặc $u=0$,
3) $3 \leq v \leq 6$ hoặc $v=0$,
4) $u + v \leq 10$.

Các điều kiện này được đáp ứng bởi mười ba chế độ hoạt động sau: $\langle 6,4 \rangle$ (6 người làm việc ở kho thứ nhất, 4 người ở kho thứ hai), $\langle 7,3 \rangle$, $\langle 6,3 \rangle$, $\langle 10,0 \rangle$, $\langle 9,0 \rangle$, $\langle 8,0 \rangle$, $\langle 7,0 \rangle$, $\langle 6,0 \rangle$, $\langle 0,0 \rangle$, $\langle 0,3 \rangle$, $\langle 0,4 \rangle$, $\langle 0,5 \rangle$ và $\langle 0,6 \rangle$. Chúng ta hãy mô tả chúng dưới dạng các điểm trên mặt phẳng tọa độ (Hình 1).

Thứ tự áp dụng các chế độ vận hành khác nhau không quan trọng. Ví dụ: nếu Quản đốc lần đầu tiên cử sáu công nhân dỡ hàng ở nhà kho thứ hai, sau đó cử toàn bộ nhóm đến nhà kho đầu tiên thì công việc sẽ được hoàn thành trong cùng $1\frac{11}{15}$ giờ. Do đó, chúng ta có thể giả định rằng quá trình tải được tổ chức như sau: đầu tiên là $t_1$ giờ, chế độ $\alpha_1$ được áp dụng, sau đó là $t_2$ giờ - chế độ $\alpha_2$, v.v. Trong trường hợp này, $t_i$ có thể bằng 0, tức là chế độ $\alpha_i$ có thể không được sử dụng. Ví dụ: khi tải ở khoảng cách ở bước 1, chỉ $t_4 = \frac{4}{10}$ và $t_{13} = \frac{8}{6}$ không bằng 0.

Chúng ta bỏ qua thời gian chuyển từ kho này sang kho khác. Khi đó tổng thời gian tải $t$ sẽ bằng

$$t = t_1 + t_2 + \dots + t_{12} + t_{13}. \tag{1}$$

Vì mỗi công nhân chất gạch trong một giờ nên số công nhân được chất từ ​​kho thứ nhất ($x$ nghìn viên) và từ kho thứ hai

⟦folio 41⟧

Hình 1.

(đối với hàng nghìn mảnh), sẽ được biểu thị bằng đẳng thức
$$x = 6t_1 + 7t_2 + \ldots + 0t_{12} + 0t_{13},$$
$$y = 4t_1 + 3t_2 + \ldots + 5t_{12} + 6t_{13}.$$
Chúng tôi sửa $t$. Thay vào (2) và (3) các số không âm $t_1, t_2, \ldots, t_{13}$ thỏa mãn điều kiện (1), ta sẽ được các điểm khác nhau của mặt phẳng $\langle x, y \rangle$. Chúng tôi biểu thị tập hợp tất cả các điểm như vậy bằng $A_t$; Hãy gọi nó là bộ khả năng truy cập thời gian $t$. Tên này là tự nhiên: $A_t$ bao gồm các điểm trên mặt phẳng có tọa độ bằng số viên gạch (tính bằng nghìn viên) mà đội có thể tải - tương ứng, từ kho thứ nhất và kho thứ hai - trong thời gian $t$.

Bây giờ bài toán Quản đốc có thể được hình thành như sau: tạo lịch xếp hàng sao cho điểm có tọa độ $\langle 4, 8 \rangle$ (điểm này tương ứng với số lượng gạch đã cho trong kho) thuộc tập $A_t$ và $t$ tối thiểu.

3. Nhà toán học giải bài toán

Trước hết, Nhà toán học yêu cầu bài toán: anh ta sẽ hạn chế tìm tập $A_1$, vì bất kỳ tập hợp nào $A_t$ đều chuẩn bị một tập hợp $A_1$ với hệ số sẵn sàng $t$ và tâm sẵn sàng - gốc tọa độ.

Chứng minh rằng tập $A_1$ là bao lồi của một số điểm $\alpha_1, \alpha_2, \ldots, \alpha_{13}$.

Hãy nhớ lại rằng tập hợp $M$ các điểm trên một mặt phẳng được gọi là lồi nếu cùng với bất kỳ cặp điểm nào của nó, nó chứa toàn bộ đoạn thẳng có các điểm cuối tại các điểm này (“Hình học 6”, đoạn 39). Ví dụ về các tập lồi được thể hiện trong Hình 2; các tập hợp trong Hình 3 không lồi.

Bao lồi của tập $M$ là tập lồi nhỏ nhất chứa $M$ (Hình 4). Vì giao của một số tập lồi bất kỳ là lồi (chứng minh đi!), nên bao lồi của một tập hợp tùy ý $M$ trùng với giao của tất cả các tập lồi chứa $M$ (những tập hợp như vậy luôn - bất kể $M$ - tồn tại; tại sao?). Bao lồi của tập $M$ thường được ký hiệu là bao lồi $M^*$).

Để chứng minh rằng tập có thể tới được $A_1$ là bao lồi của tập $\{\alpha_1, \alpha_2, \ldots, \alpha_{13}\}$, chúng ta đưa ra một định nghĩa khác cho khái niệm bao lồi.

Hình 2.

Hình 3.

Hình 4. Trong cả hai cặp, tập bên phải là bao lồi của tập bên trái.

*) Từ tiếng Latin conprhius (“lồi”).

⟦folio 42⟧

Để làm điều này, chúng tôi giới thiệu hai thao tác với các điểm trên mặt phẳng tọa độ. Chúng ta sẽ gọi tổng số điểm là $\langle x_1, y_1 \rangle$ và $\langle x_2, y_2 \rangle$ là điểm $\langle x_1 + x_2, y_1 + y_2 \rangle$. Tích của điểm $\langle x, y \rangle$ và số $t$ là điểm $\langle tx, ty \rangle$. Nếu mỗi điểm $\alpha$ được liên kết với một vectơ xác định bởi một cặp điểm $O$, $\alpha$ ($O$ là gốc tọa độ), thì các phép toán được giới thiệu với điểm sẽ trùng với các phép toán thông thường trên vectơ.

Chứng minh rằng nếu tập $M$ lồi thì tập $tM$ (tức là tập các điểm $t\beta$, trong đó $\beta \in M$) cũng lồi.

Sự định nghĩa. Điểm $\beta$ được gọi là tổ hợp lồi của các điểm $\beta_1, \beta_2, \dots, \beta_n$ nếu cũng có các số không âm $t_1, t_2, \dots, t_n$, chẳng hạn như $t_1 + t_2 + \dots + t_n = 1$ và $\beta = t_1\beta_1 + t_2\beta_2 + \dots + t_n\beta_n$.

Định lý. Bộ bao lồi $M$ bao gồm tất cả các tổ hợp lồi có thể có của các điểm từ $M$.

Bằng chứng. Chúng ta hãy biểu thị tập hợp các tổ hợp lồi của các điểm từ $M$ đến $Q$. Nếu $\gamma$ và $\delta$ là các điểm tùy ý thì tập hợp các điểm có dạng $t\gamma + (1-t)\delta$, trong đó $0 \leq t \leq 1$, trùng với đoạn có các điểm cuối $\gamma$, $\delta$. Từ đây dễ dàng suy ra $Q$ là một tập lồi (làm cái này nhé!). Ngoài ra, rất/không, $M \subset Q$. Vì vậy, trùng hợp ngẫu nhiên $M \subset Q$. Bây giờ chúng ta hãy chứng minh bằng quy nạp trên $n$ rằng mọi tổ hợp lồi $t_1\beta_1 + t_2\beta_2 + \dots + t_n\beta_n(t_1 + t_2 + \dots + t_n = 1)$ của các điểm từ $M$ đều chấp nhận sự trùng hợp $M$. Điều này có nghĩa là $Q \subset \text{conv } M$. Đối với $n = 1$, câu lệnh tương ứng có dạng: nếu $\beta \in M$, thì $\beta \in \text{conv } M$. Điều này đúng theo định nghĩa của bao lồi. Bây giờ hãy để tất cả các kết hợp lồi $n$ của các điểm từ $M$ chấp nhận sự trùng hợp $M$. Hãy chứng minh rằng khi đó tổ hợp lồi $\delta = t_1\beta_1 + t_2\beta_2 + \dots + t_n\beta_n + t_{n+1}\beta_{n+1}$ (trong đó $\beta_1, \beta_2, \dots, \beta_n, \beta_{n+1}$ là các điểm từ $M$) cũng lấy $M$:

$$\delta = (1 - t_{n+1}) \left[ \frac{t_1}{1 - t_{n+1}}\beta_1 + \frac{t_2}{1 - t_{n+1}}\beta_2 + \dots + \frac{t_n}{1 - t_{n+1}}\beta_n \right] + t_{n+1}\beta_{n+1}.$$

Từ $t_1 + t_2 + \dots + t_n + t_{n+1} = 1$ nó theo sau

$$\frac{t_1}{1 - t_{n+1}} + \frac{t_2}{1 - t_{n+1}} + \dots + \frac{t_n}{1 - t_{n+1}} = 1.$$

Bằng giả thuyết quy nạp

$$\eta = \frac{t_1}{1 - t_{n+1}}\beta_1 + \frac{t_2}{1 - t_{n+1}}\beta_2 + \dots + \frac{t_n}{1 - t_{n+1}}\beta_n \in \text{conv } M.$$

Từ (4) suy ra điểm $\delta$ nằm trên đoạn có các điểm cuối $\eta$ và $\beta_{n+1}$. Vì $\beta_{n+1} \in M \subset \text{conv } M$ và đối lưu $M$ là một tập lồi nên chúng ta thu được $\delta \in \text{conv } M$. Định lý đã được chứng minh.

Do đó, mỗi điểm trong đối lưu $M$ là tổ hợp lồi của một số điểm cuối trong $M$. Nếu tập $M$ là hữu hạn thì chúng ta có thể giả sử rằng mỗi điểm từ đối lưu $M$ là tổ hợp lồi của tất cả các điểm từ $M$.

Hóa ra là đối với một tập hợp tùy ý $M$ trên mặt phẳng của mỗi điểm $\beta$, tập hợp trùng khớp $M$ có ​​thể thu được dưới dạng tổ hợp lồi của ba điểm $\beta_1, \beta_2, \beta_3$ từ $M$ (tất nhiên, đối với các $\beta$ khác nhau thì các điểm $\beta_1, \beta_2, \beta_3$ nói chung là khác nhau). Định lý này, hay đúng hơn là định lý tương tự $n$ chiều của nó, được gọi là *định lý Carmedori*. Hãy thử chứng minh điều đó!

Theo định nghĩa, bộ khả năng tiếp cận $A_1$ bao gồm tất cả các điểm có thể có $t_1\alpha_1 + t_2\alpha_2 + \dots + t_{13}\alpha_{13}$ mà $t_1 + t_2 + \dots + t_{13} = 1$ (mục 2). Nói cách khác, $A_1$ bao gồm tất cả các tổ hợp lồi có thể có của các điểm $\alpha_1, \alpha_2, \dots, \alpha_{13}$. Theo định lý đã được chứng minh

$$A_1 = \text{conv} \{ \alpha_1, \alpha_2, \dots, \alpha_{13} \}.$$

Từ Hình 1 cho thấy rõ $A_1$ là tập hợp các điểm của tứ giác $\alpha_1\alpha_2\alpha_3\alpha_{13}$ (điểm $\alpha_2$ nằm trên đường thẳng $\alpha_1\alpha_4$).

Để tìm mức tối thiểu $t$ mà tập hợp $A_t = t \cdot A_1$ chứa điểm $\beta$ ($\langle 4, 8 \rangle$ (Hình 5), chúng ta tính tọa độ của điểm $\gamma$ giao điểm của các đường $\alpha_9$ $\beta$ và $\alpha_1\alpha_{13}$.

⟦folio 43⟧

Nhấn nút làm việc $\alpha_1$ trong $t \cdot t_1 = \frac{8}{9}$ (giờ) và chế độ làm việc $\alpha_{13}$ trong $t \cdot t_{13} = \frac{2}{3}$ (giờ). Thời gian mà tất cả công việc lẽ ra phải thực hiện theo lịch trình do Quản đốc vạch ra ở đoạn 1 bằng $1 \frac{11}{15}$ giờ, tức là nhiều hơn $1 \frac{4}{35}$ lần so với thời gian tối thiểu được tìm thấy.

Hãy tóm tắt. Chúng ta thấy rằng bài toán hoàn toàn không phải hình học của Brigadier đã dẫn chúng ta đến các hình lồi trên mặt phẳng. Hóa ra khái niệm độ lồi có thể được định nghĩa không chỉ cho các vật thể hình học - phẳng hoặc không gian - mà còn trong một tình huống tổng quát hơn nhiều (ví dụ, trong cái gọi là không gian vectơ - xem «Kvant», 1976, Số 4, trang 2). Ở dạng tổng quát này, nó “hoạt động” trong nhiều lĩnh vực toán học (giải tích hàm, lập trình toán học, lý thuyết trò chơi).

Bạn có thể làm quen với các bài toán thú vị được giải bằng cách sử dụng khái niệm độ lồi trong cuốn sách “Các hình lồi” của I. M. Yaglom và V. G. Boltyansky (M. - Leningrad, Gostekhidat, 1951).

Bài toán Quản đốc cũng có thể được giải hoàn toàn bằng đại số - sử dụng phương pháp quy hoạch tuyến tính. Cách thực hiện điều này đã được mô tả trong «Kvant», 1976, Số 7, tr. 2. Với cách tiếp cận này, cần lưu ý rằng có thể (xem Hình 1) chỉ xem xét những lịch trình mà

$$t_3 = t_5 = t_6 = t_7 = t_8 = t_9 = t_{10} = t_{11} = t_{12} = 0.$$

Bài tập

1. Lập lịch trình cho Quản đốc nếu
a) ở kho thứ nhất - 16 nghìn viên gạch, ở kho thứ hai - 4 nghìn;
b) Phải có ít nhất 7 người làm việc cùng lúc ở kho thứ nhất.
2. Có một chiếc chảo rán trong đó bạn có thể chiên hai miếng cốt lết cùng một lúc. Mỗi miếng cốt lết được chiên một mặt trong một phút. Mất bao lâu để chiên ba miếng cốt lết?
