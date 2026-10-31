---
id: 1981-1-dvoryaninov-uzoryi-i-arifmetika-eb68fcd0
issue: kvant_1981_1
year: 1981
number: "1"
title: Các mẫu và... số học
authors:
  - Дворянинов С. В.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 36
page_last: 38
page_labels: 34-36
tag: CZH2
lang: vi
source: kvant_digital
extraction: vision
content_sha256: a39a91d7d5d1aad6679c437e370c585113efb3d017cbca06b88312867b140238
prompt_sha256: draft-1
translated_from: content/ru/1981/01/articles/11_dvoryaninov-uzoryi-i-arifmetika-eb68fcd0.md
source_content_sha256: bd6d19855541e83238bf17a4074e13f994637826e682a6902e1083d0092dd77c
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 34⟧

S. Dvoryaninov

Các mẫu và...
số học

Hình vẽ mà bạn nhìn thấy trước mặt (Hình 1) được tạo ra bằng cách sử dụng một thiết bị đơn giản gọi là máy ghi nhịp tim. Và mặc dù máy đo nhịp thở được bán trong các cửa hàng đồ chơi nhưng nó không chỉ được học sinh tiểu học mà cả học sinh trung học và người lớn tuổi quan tâm. Nó có thể được sử dụng để vẽ nhiều đường cong khác nhau. Chắc hẳn nhiều người sau khi nhận được một vài bức vẽ đẹp sẽ muốn tìm hiểu xem chúng sẽ ra sao?

Spirograph bao gồm một bộ bánh xe và hai bánh xe có răng có cùng kích thước. Chúng được làm từ nhựa ngẫu nhiên. Bánh xe có 24, 32, 52, 60, 63, 72 và 80 răng. Có 96 chiếc răng ở bên trong một chiếc nhẫn, 144 chiếc ở bên ngoài; trên vòng kia có lần lượt là 105 và 150 răng. Mỗi bánh xe và vòng có nhiều lỗ nhỏ. Để kích hoạt máy đo chức năng hô hấp, bạn cần ấn vòng vào giấy bằng một tay hoặc cố định nó bằng ghim trên máy tính bảng, đặt bánh xe vào bên trong vòng (hoặc bên ngoài nó) và căn chỉnh răng của chúng (Hình 2). Sau đó, bạn nên tăng cường điểm của bút bi trong một

Hình 1

⟦folio 35⟧

từ quầy trong bánh xe và quay bánh xe mà không bị trượt dọc theo vòng. Trong trường hợp này, đầu bút sẽ vẽ một đường cong nhất định lên giấy. Sau vài vòng quay, đường cong sẽ khép lại. Bây giờ chúng tôi sẽ giải thích tại sao lại như vậy.

Gọi $R$ là bán kính của vòng tròn, $r$ bán kính của bánh xe, $\varphi$ khoảng cách từ tâm bánh xe đến đáp án trong đó tay cầm được cố định. Khi bánh xe quay, đầu bút sẽ di chuyển dọc theo tờ giấy trong một khu vực cọc nhất định. Bán kính ngoài của nó là $R_{\text{внешн.}} = R - r + \varphi$, bán kính trong của nó là $R_{\text{внутр.}} = R - r - \varphi$. Từ công thức cuối cùng, có thể thấy rõ rằng, chẳng hạn, nếu $r = \frac{3}{4}R$, $\varphi = \frac{1}{4}R$, thì đường cong sẽ không còn ở dạng vòng nữa mà ở dạng hình tròn, vì trong trường hợp này là $R_{\text{внутр.}} = 0$.

Đặt $N$ răng trên vòng và $n$ trên vòng. Giả sử sau khi bánh xe quay $K$ vòng quanh tâm và $k$ vòng quanh vòng, nó đã trở về vị trí ban đầu và đầu tay cầm ở điểm xuất phát. Trong trường hợp này, đường cong đã vẽ sẽ bị đóng và khi bánh xe quay thêm, sẽ không thu được một đường cong mới - đầu bút sẽ lặp lại đường đi đã đi. Dễ dàng báo cáo rằng tại thời điểm khi đường cong đóng lại, đẳng thức

$$Kn = kN = D. \quad (*)$$

Vì đối với mọi số tự nhiên $N$ và $n$ đều có các số $K$ và $k$ thỏa mãn đẳng thức (*), nên bất kỳ đường cong nào được vẽ bằng biểu đồ trục sẽ bị đóng. Hơn nữa, các số $K$ và $k$ là những số nguyên nhỏ nhất có đẳng thức (*) và $D$ là bội số chung nhỏ nhất của các số $N$ và $n$. Dựa vào đó, người ta có thể tính LCM của hai số $m$ và $M$: làm một bánh xe có răng $m$, một cọc có $M$ và quay bánh xe bên trong vòng cho đến khi đường cong khép lại, đếm xem bánh xe quay được bao nhiêu vòng quanh tâm của nó (số $K$) hoặc bao nhiêu vòng - theo vòng (số $k$). Sau đó, sử dụng công thức (*), các giá trị $D = \text{НОK}(m, M)$ được tính toán.

Cho $N$ và $n$, hình dạng của đường cong phụ thuộc vào $\varphi$. Trong Hình 3 và 4 $N = 96$, $n = 60$, $K = 8$, $k = 5$, nhưng trong Hình 3, các giá trị $\varphi$ lớn hơn trong Hình 4. Bằng cách tăng hoặc giảm dần $\varphi$, tức là sử dụng các phản hồi khác nhau trong bánh xe, bạn có thể theo dõi xem các đường cong thu được bị biến dạng như thế nào khi giá trị thay đổi $\varphi$.

Số $K$ rất dễ xác định từ hình - nó trùng với số điểm đường cong xa tâm vòng nhất. Trong Hình 3 và 4, các điểm này được xếp theo thứ tự chúng được truyền qua.

Khi vẽ đường cong, tốt hơn là làm ngược lại. Trong trường hợp $N$ và $n$ có ít thừa số chung (ví dụ: $N = 105$, $n = 72$), bánh xe phải quay nhiều vòng hơn để có được đường cong khép kín. Để xác định thời điểm đường cong khép lại, bạn nên đếm trước số $K$ và lăn bánh xe quanh vòng thật nhiều lần.

Những người quen thuộc với các số vô tỷ có thể tưởng tượng ra một máy ghi trục quay lý tưởng - không có răng trên bánh xe và vòng, nhưng bánh xe

⟦folio 36⟧

di chuyển xung quanh vòng mà không bỏ qua
đang gọi. Gọi $l$ là chu vi của bánh xe, $L$ là chu vi của vòng mà bánh xe di chuyển dọc theo. Nếu các số $l$ và $L$ không giống nhau (ví dụ số $l$ là số hữu tỉ, $L$ là số vô tỉ) thì đường cong đã vẽ sẽ không bao giờ đóng, vì không có số tự nhiên $K$ và $k$ thì đẳng thức $Kl=kL$ tương ứng với (*) không thể thỏa mãn. Tuy nhiên, dấu từ đầu bút có chiều rộng hữu hạn nên sau một số vòng quay đủ lớn của bánh xe, chúng ta sẽ có được một vòng sơn hoàn toàn trên giấy. Một bức tranh tương tự sẽ xuất hiện đối với các số nguyên tố lớn $N$ và $n$ (ví dụ: 105 và 52). Nếu chúng ta giả sử rằng vết từ đầu bút là một đường toán học lý tưởng, thì đường cong kết quả cho vô tỷ $l$ và $L$ sẽ nằm trong vùng hình khuyên tương ứng *có mật độ dày đặc ở khắp mọi nơi* (nghĩa là quỹ đạo của đầu bút tiếp cận bất kỳ điểm nào bên trong vùng dưới dạng gần góc). Những quỹ đạo tương tự xuất hiện trong nhiều bài toán toán học khác nhau và được nghiên cứu, ví dụ, trong lý thuyết phương trình vi phân.

Trong trường hợp giá trị của $q$ gần với $r$, quỹ đạo được mô tả bởi máy đo phế dung gần với các đường cong đã biết có tên đặc biệt*). Khi bánh xe lăn vào bên trong vòng, kết quả là *zipoclopda*. Cụ thể, với $N=96$, $n=24$ thu được *astrode* (Hình 5). Nếu bánh xe lăn dọc theo một vòng từ bên ngoài hoặc trên một bánh xe khác thì đường cong được vẽ gần với *epcclopde* (với $q$ gần với $r$; Hình 6). *Cardioid* (Hình 7) thu được bằng cách sử dụng hai bánh xe giống hệt nhau. Nếu chúng ta buộc bánh xe lăn không trượt theo đường thẳng và lấy giá trị $q$ vẫn gần với $r$, thì chúng ta sẽ có một đường cong tương tự như *cyclops*.

Và kết luận lại, một số lời khuyên dành cho những ai muốn tự mình làm một máy đo chức năng hô hấp. Vòng có thể được cắt từ cao su dày hoặc vải sơn, bánh xe có thể được làm từ tấm mica, một số loại nhựa hoặc làm từ vật liệu khác có hệ số ma sát khá cao. Bạn chỉ cần tính trước tỷ lệ $L:l$; ví dụ: bạn có thể lấy tỷ lệ là 4:3, 3:1, 7:5. Ở các bánh xe, ở các khoảng cách khác nhau tính từ tâm, bạn nên khoan một thanh tay cầm có phần chịu trách nhiệm về đường kính.

*) Bạn có thể đọc thêm chi tiết về những đường cong này trong các số sau «Kvant»: 1975, No. 8, No. 12; 1977, không. 12.
