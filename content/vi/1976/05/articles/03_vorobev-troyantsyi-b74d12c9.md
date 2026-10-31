---
id: 1976-5-vorobev-troyantsyi-b74d12c9
issue: kvant_1976_5
year: 1976
number: "5"
title: Trojan
authors:
  - Воробьёв И. И.
rubric: osnovnye-stati
page_first: 13
page_last: 18
page_labels: 11, 12, 13, 16
tag: XJGK
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 44336b3faf54e753f416d934e3592406e5ae161f3809ec9e229c572cf77b1a64
prompt_sha256: draft-1
translated_from: content/ru/1976/05/articles/03_vorobev-troyantsyi-b74d12c9.md
source_content_sha256: a4644791de4d402ba056c9c82c204fca65911506c8bec7fcc75965771eb1701a
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 11⟧

Có thể hiểu được các vật tương tác với nhau theo định luật vạn vật hấp dẫn sẽ chuyển động như thế nào không? Ví dụ, các hành tinh chuyển động như thế nào? Giả sử rằng tại một số thời điểm ban đầu, chúng ta biết tọa độ chính xác của các hành tinh $n$, vận tốc của chúng và được biết rằng mỗi hành tinh chỉ bị ảnh hưởng bởi lực hấp dẫn từ các hành tinh ($n-1$) còn lại. Dựa trên những điều kiện ban đầu này cần xác định sự chuyển động của các hành tinh trong tương lai.

Các định luật điều chỉnh chuyển động này là định luật thứ hai quen thuộc của Newton và định luật vạn vật hấp dẫn. Sử dụng immi, bạn có thể tưởng tượng được chuyển động của các hành tinh. Đối với hệ hai vật ($n=2$), bài toán này lần đầu tiên được Newton giải. Trong trường hợp này, dựa trên các điều kiện ban đầu, có thể xác định trạng thái của hệ (tọa độ của các vật thể, vận tốc của chúng, v.v.) bất kỳ lúc nào với bất kỳ độ chính xác nào.

Nhưng khi các nhà khoa học bắt đầu nghiên cứu một hệ gồm nhiều vật thể, họ gặp phải những khó khăn to lớn trong việc mô tả đặc tính toán học thuần túy. Đối với trường hợp $n=3$, không thể thu được chính xác lời giải bài toán trong trường hợp chung. Và cho đến giữa trưa, bất chấp nỗ lực suốt hai trăm năm mươi năm của các nhà toán học trên khắp thế giới, vẫn không thể giải chính xác được bài toán này bằng các phương tiện toán học đã biết. Đó là lý do tại sao “bài toán $n$ vật thể”—như tên gọi của bài toán cơ học này—đã thu hút sự chú ý của các nhà toán học.

Một động lực khác là tầm quan trọng to lớn của các vật thể bài toán $n$ đối với cơ học thiên thể và du hành vũ trụ. Do đó, không có gì đáng ngạc nhiên khi tổng số công trình liên quan đến nó lên tới hai nghìn và 15-20 nghiên cứu mới xuất hiện hàng năm.

⟦folio 12⟧

Hiện nay, có một số phương pháp dành cho các vật thể lời giải bài toán $n$ gần đúng, cho phép mỗi hệ thống vật thể cụ thể với các điều kiện ban đầu cụ thể nhất định xây dựng quỹ đạo chuyển động với bất kỳ độ chính xác nào cần thiết để thực hành trong bất kỳ khoảng thời gian giới hạn nào.

Tính hiệu quả và độ tin cậy của các phương pháp này chưa được thử nghiệm nhiều lần, đặc biệt là khi tính toán quỹ đạo của tàu vũ trụ và các trạm liên hành tinh.

Bằng cách sử dụng chính xác những phương pháp này, Adams và Le Verrier đã có thể khám phá ra hành tinh Sao Hải Vương “ở đầu ngòi bút của họ”.
- Xin lỗi, nhưng khó khăn có liên quan gì đến nó? - người đọc sẽ ngạc nhiên. Chỉ là các nhà thiên văn học rất hâm mộ thần thoại và một nhóm các nhà thiên văn có cái tên chung như vậy được kết nối với chủ đề của các bài viết theo cách sau. Nhưng chúng ta sẽ nói về Trojan sau một lát, còn bây giờ chúng ta hãy tiếp tục nói về bài toán $n$ tel.

Bài toán Lagrange

Vì vậy, chắc chắn có lời giải bài toán $n$ thể. Nhưng đối với trường hợp từng phần $n = 3$ dưới một số điều kiện ban đầu “đặc biệt”, thì lời giải chính xác đã được nhà toán học nổi tiếng người Pháp Lagrange tìm ra cách đây 200 năm.

lời giải của anh ấy - đây được gọi là nghiệm Lagrange của các vật thể bài toán $n$ - là lời giải chính xác duy nhất của bài toán này được biết đến hiện nay.

Trong bài viết này chúng ta sẽ xem xét phần đơn giản nhất bài toán của Lagrange.

Cho ba vật không nằm trên cùng một đường thẳng quay theo những đường tròn đồng tâm nằm trong cùng một mặt phẳng với vận tốc góc bằng nhau. Nghĩa là, những vật thể này có thể được coi là những điểm của một vật thể tam giác tưởng tượng, quay một trục chuyển động quanh nó (rất

Hình.1.
rõ ràng là trục này đi qua tâm của các đường tròn đồng tâm - “quỹ đạo” của các vật thể).

Điều này có thể xảy ra ở sự sắp xếp nào của khối lượng? Vật thể hình tam giác tưởng tượng này phải quay với tốc độ bao nhiêu để không bị “phân tán” thành nhiều phần? Đây là cách Lagrange thiết lập bài toán của mình.

Vì vậy, chúng ta hãy thử giải bài toán này theo Lagrange.

Tam giác khối

Cho ba vật có khối lượng $m_1, m_2, m_3$ quay theo các đường tròn đồng tâm, tâm của chúng ở điểm $O$ (xem Hình 1). Bán kính quỹ đạo của các vật thể lần lượt là $r_1, r_2$ và $r_3$, khoảng cách $R_1, R_2, R_3$ giữa các vật thể lớn hơn nhiều so với kích thước của các vật thể. Gia tốc hướng tâm của mỗi điểm được truyền bởi lực hấp dẫn tác dụng lên nó từ các điểm lân cận, tức là một lực bằng tổng (vectơ!) của các lực này. Hãy viết phương trình chuyển động của vật:

$$\begin{align*}
F_{12} + F_{13} &= m_1 a_1, \\
F_{21} + F_{23} &= m_2 a_2, \\
F_{31} + F_{32} &= m_3 a_3.
\end{align*}$$

Ở đây $|F_{ij}| = \gamma \frac{m_i m_j}{r_{ij}^2}$ là giá trị của lực Newton mà vật $m_j$ tác dụng lên vật $m_i$. Vì mọi vật đều quay với cùng một vận tốc góc $\omega$ (theo điều kiện bài toán), nên

$$a_1 = -\omega^2 r_1, \quad a_2 = -\omega^2 r_2, \quad a_3 = -\omega^2 r_3,$$

⟦folio 13⟧

Cơm. 2.
trong đó $r_i$ là vectơ bán kính của điểm $m_i$ so với tâm quay $O$. (Khoảng cách giữa các vật thể lớn hơn nhiều so với kích thước của các vật thể nên có thể coi các vật thể là điểm).

Tất cả những lý luận sâu hơn của chúng ta sẽ thuần túy là “số học”, và thoạt đầu có vẻ như chúng chẳng liên quan gì đến bài toán. Nhưng chúng sẽ dẫn chúng ta đến lời giải bài toán (hay đúng hơn là phần đầu tiên của nó) - chúng sẽ cho phép chúng ta xác định cấu hình của các vật thể.

Chúng ta hãy cộng các đẳng thức từ hệ (1) theo từng số hạng:

$$F_{12} + F_{13} + F_{21} + F_{23} + F_{31} + F_{32} = m_1 a_1 + m_2 a_2 + m_3 a_3 = -\omega^2 (m_1 r_1 + m_2 r_2 + m_3 r_3).$$

Vế trái của đẳng thức này bằng 0 - xét cho cùng, theo định luật III của Newton, tổng của tất cả các nội lực trong một hệ kín bằng 0. (Vế trái có thể viết như sau:

$$\sum_{i,j=1}^{3} F_{ij} + \sum_{i,j=1}^{3} F_{ji} = 0, \text{ так как } F_{ij} = -F_{ji}.$$

Vì vậy chúng tôi có

$$m_1 r_1 + m_2 r_2 + m_3 r_3 = 0$$

(kể từ $\omega \neq 0$). Đẳng thức (2) về cơ bản xác định vị trí của tâm quay: nó nằm ở điểm $O$ sao cho vectơ bán kính của vật thể $m_1, m_2, m_3$ so với điểm này phải thỏa mãn điều kiện (2).

Hãy giới thiệu các vectơ $R_2$ và $R_3$ như trong Hình 2. Sau đó

$$r_1 = r_2 + R_3,$$

$$r_1 = r_3 + R_2.$$

Cơm. 3.
Chúng ta hãy biểu thị vectơ $r_1$ theo các vectơ $R_2$ và $R_3$. Để làm điều này, nhân đẳng thức thứ nhất từ ​​(3) với $m_2$ và nhân đẳng thức thứ hai với $m_3$ rồi cộng các đẳng thức thu được theo từng số hạng:

$$m_2 r_1 + m_3 r_1 = m_2 r_2 + m_3 r_3 = -m_1 r_1$$

(theo (2)), ta có:

$$(m_1 + m_2 + m_3) r_1 = m_2 R_3 + m_3 R_2.$$

Từ đây

$$r_1 = \frac{m_2}{m_1 + m_2 + m_3} R_3 + \frac{m_3}{m_1 + m_2 + m_3} R_2$$

Như vậy, vectơ $r_1$ là tổng của các vectơ $\rho_2 = \frac{m_3}{m_1 + m_2 + m_3} R_2$ và $\rho_3 = \frac{m_2}{m_1 + m_2 + m_3} R_3$ song song với các cạnh $R_2$ và $R_3$ của tam giác khối.

Bây giờ chúng ta hãy vẽ trên sơ đồ của tam giác khối các vectơ của lực tác dụng lên vật $m_1$ (xem Hình 3). $F_{12}$ là lực tác dụng từ cơ thể $m_2$, $F_{13}$ là lực tác dụng từ cơ thể $m_3$. Các lực này hướng dọc theo các cạnh $R_3$ và $R_2$ của tam giác khối. Kết quả của chúng hướng dọc theo vectơ $r_1$ đến điểm $O$ (vectơ gia tốc vật $m_1$ hướng vào tâm quay). Nhưng điều này có nghĩa là hình bình hành lực và hình bình hành dựng trên vectơ $\rho_2$ và $\rho_3$ là tương tự nhau! Sau đó

$$|F_{12}|:|\rho_3| = |F_{13}|:|\rho_2|,$$

⟦folio 16⟧

các tam giác đều có đáy Trái Đất - Mặt Trăng; những đám mây bụi vũ trụ rộng lớn. Ở đây, vai trò của Trojan được thực hiện bởi vô số hạt bụi bị thu giữ bởi lực hút tương thích của Trái đất và Mặt trăng.

Do đó, lời giải, được Lagrange xuất bản năm 1772 và đối với chính tác giả chỉ là một vấn đề lý thuyết thú vị, hóa ra lại có liên quan đến những khám phá thiên văn học sau này.

Ổn định chuyển động

Nhưng chúng ta đã tìm thấy tất cả các cấu hình của ba cơ thể chưa? Không, chúng ta chưa phân tích trường hợp các vật thể sắp xếp theo đường thẳng; Ngoài ra còn có một cấu hình tương tự gồm ba vật thể có thể xoay làm một. Hóa ra cấu hình này không ổn định. Ngay khi bạn “di chuyển” khỏi đường thẳng một chút, sự phối hợp các lực ngay lập tức bị gián đoạn và độ lệch bắt đầu tăng lên.

Cấu hình tam giác có ổn định không? Không phải lúc nào cũng vậy. Năm 1843, Gachot lần đầu tiên xác định được các điều kiện ổn định của tam giác Lagrange. Ông đã chỉ ra rằng cấu hình sẽ ổn định nếu khối lượng của các vật thể lớn (nằm ở đáy tam giác) sao cho tỷ số của chúng (tỷ lệ giữa khối lượng nhỏ hơn và khối lượng lớn hơn) đủ nhỏ và các điều kiện được đáp ứng.

$$\frac{(m_1 + m_2)^2}{m_1 m_2} > 27.$$

Nếu một hạt vũ trụ, có khối lượng nhỏ hơn $m_1$ và $m_2$, chuyển động với tốc độ tương đối thấp, vô tình chạm vào đỉnh của một tam giác đều, ở đáy của nó có khối lượng $m_1$ và $m_2$, thì nó thấy mình bị “mắc kẹt”. Trong trường hợp này, hạt có thể mô tả một quỹ đạo rất phức tạp ở gần đỉnh

Tam giác Langrange nhưng toàn bộ cấu hình sẽ xoay làm một.

Khối lượng của Sao Mộc nhỏ hơn khối lượng của Mặt trời một nghìn lần. So với bất kỳ loại nào trong số chúng, tổng khối lượng của Trojan là không đáng kể. Điều kiện ổn định được đáp ứng với biên độ lớn. Sự bất bình đẳng cũng đúng với hệ Trái đất-Mặt trăng: khối lượng khác nhau theo hệ số 81.

Làm thế nào để rút ra điều kiện này? Có thể có một kết luận đơn giản, nhưng vấn đề này vẫn phức tạp và trong mọi trường hợp, cần phải có một cuộc thảo luận đặc biệt.

Bài tập

1. Bài báo không tính được vận tốc góc quay của tam giác khối. Chứng minh rằng $\omega^2 = \gamma \frac{m_1 + m_2 + m_3}{R^3}$, trong đó $R$ là khoảng cách giữa các khối lượng.

2. Chúng ta coi tam giác khối lượng là “cứng nhắc”. Nhưng hóa ra là nếu các vectơ vận tốc có độ lớn tỷ lệ thuận với khoảng cách đến tâm quay và tất cả đều hướng cùng một góc với các đoạn nối các vật thể với tâm, thì cấu hình của vật thể vẫn giống như ban đầu tại bất kỳ thời điểm nào. Một tam giác đều khi quay sẽ giãn ra hoặc co lại. Hãy cố gắng chứng minh điều đó.

Từ biên tập viên

Chúng tôi xin lỗi độc giả vì sai sót trong số thứ ba của tạp chí. Trên nền trang bìa thứ hai, chữ ký của Niels Bohr được theo sau bởi chữ ký không phải của Felix Klein mà của nhà vật lý Auguste Klein, một người bạn lớn của Niels Bohr.
