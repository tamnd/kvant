---
id: 1976-11-dozorov-elektricheskie-multipoli-ca62541e
issue: kvant_1976_11
year: 1976
number: "11"
title: Đa cực điện
authors:
  - Дозоров А. А.
rubric: osnovnye-stati
page_first: 4
page_last: 9
page_labels: 2, 4, 5, 6, 7
tag: 69PW
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c6c3d9e3066541793a589d7730a7e1e60656d8a069527450a9b6a27e44949414
prompt_sha256: draft-1
translated_from: content/ru/1976/11/articles/02_dozorov-elektricheskie-multipoli-ca62541e.md
source_content_sha256: 65192a929a8efbc64e51a4eb20e2b2b5c5ea167f2eed6ed9b6649a077d729cb2
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

Đa cực điện

Thế năng của trường tĩnh điện được tạo ra bởi một điện tích chính xác tại một điểm nào đó trong không gian xung quanh tỷ lệ nghịch với khoảng cách từ điện tích đến điểm này (xem phụ lục ở cuối bảng thống kê). Mỗi tập hợp điện tích bất kỳ tập trung ở một khu vực nhất định, cách xa khu vực này, sẽ tạo ra một điện thế tỷ lệ nghịch với khoảng cách. Tuy nhiên, kết luận này không đúng trong trường hợp tổng quát. Hóa ra là bằng cách sắp xếp các điện tích theo một thứ tự nhất định, bạn có thể nhận được điện thế tỷ lệ nghịch với bất kỳ lũy thừa nguyên nào của khoảng cách.

Để bị thuyết phục về tính chất bất thường này, chúng ta chỉ cần một mệnh đề toán học: nếu giá trị $|x|$ nhỏ hơn một thì sự tương ứng là đúng

$$\frac{1}{1-x} = 1 + x + x^2 + x^3 + x^4 + \dots$$

(1)

Đây là biểu thức quen thuộc cho tổng của một cấp số nhân giảm vô hạn.

Chúng ta hãy chuyển sang xem xét các hệ thống tĩnh điện khác nhau. Ở khoảng cách $r$ tính từ điện tích chính xác $q$, độ lớn của điện thế φ do điện tích này tạo ra tỷ lệ nghịch với khoảng cách: $\varphi = \frac{kq}{\varepsilon r}$. Hệ số tỷ lệ $k$ phụ thuộc vào việc lựa chọn hệ đơn vị. Trong SI $k = \frac{1}{4\pi\varepsilon_0}$. Sẽ thuận tiện hơn cho chúng ta khi chọn hệ thống đơn vị trong đó $k = 1$ (hệ thống SGSE). Ngoài ra, chúng ta sẽ giả sử rằng mọi điện tích đều ở trong chân không, tức là $\varepsilon = 1$.

Ví dụ, chúng ta hãy xem xét ba điện tích nằm trên cùng một đường thẳng ở một khoảng cách nhất định với nhau (Hình 1). Cho phép $AB = a$, $AC = b$, và độ lớn của các điện tích bằng nhau $q$, $nq$ Và $mq$, Ở đâu $n$ Và $m$ - một số con số Hãy tìm tiềm năng tại điểm $D$, nằm trên phần tiếp theo của đoạn $AC$ ở một khoảng cách $r$ từ điểm $A$ và nằm đủ xa cả ba điện tích. Về mặt toán học, điều kiện cuối cùng có thể được viết là $r \gg a + b$. Theo nguyên lý chồng chất và điện trường, thế năng $φ$ tại điểm $D$ bằng tổng đại số của các trường thế được tạo bởi mỗi điện tích:

$$\varphi = \frac{q}{r} + \frac{nq}{r-a} + \frac{mq}{r-b} = \frac{q}{r} \left( 1 + \frac{n}{1-a} + \frac{m}{1-b} \right).$$

Vì chúng ta chỉ quan tâm đến trường hợp $r \gg a + b$ nên chúng ta có thể sử dụng thư từ (1). Trong trường hợp này chúng tôi nhận được

$$\varphi = \frac{q}{r} \left[ 1 + n \left( 1 + \frac{a}{r} + \frac{a^2}{r^2} \right) + \frac{a^3}{r^3} + \dots \right] + m \left( 1 + \frac{b}{r} + \frac{b^2}{r^2} + \frac{b^3}{r^3} + \dots \right) = \frac{q + nq + mq}{r} + q \frac{na^2 + mb^2}{r^3} + q \frac{na^3 + mb^3}{r^4} + \dots.$$

Từ biểu thức này, rõ ràng là đối với khoảng cách lớn $r$ giá trị tuyệt đối của mỗi số hạng tiếp theo nhỏ hơn đáng kể so với số hạng trước, trừ khi tử số của số hạng trước bằng 0. Ví dụ: nếu tổng chi phí không

⟦folio 4⟧

đối với trường $2^n$ trước đó, thêm trường $2^n$ tương tự, nhưng chỉ dịch chuyển đối xứng đến một khoảng cách nhất định và hơn nữa, với các điện tích trái dấu. Kết quả là một hệ thống bao gồm, như người ta nói, gồm hai trường $2^n$ đối diện. Hệ thống mới này tạo thành một đa cực theo thứ tự $(n+1)$ $(2^{n+1}-поль)$.

Hãy xem xét một vài ví dụ.

Điện tích điểm - $q$ - đa cực bậc 0. Từ đó, chúng ta tạo thành trường đa cực bậc nhất $(2$-field), thường được gọi là lưỡng cực. Chúng ta hãy dịch chuyển điện tích chính xác - $q$ một khoảng $l$ và thay đổi dấu của điện tích. Trong trường hợp này, chúng ta thu được lưỡng cực như trong Hình 2. Nó thường được đặc trưng bởi cái gọi là mômen lưỡng cực $d = ql$; vectơ $l$ hướng từ điện tích âm sang điện tích dương và chiều dài của nó bằng khoảng cách giữa các điện tích.

Hãy tính điện thế $\varphi_1$ được tạo bởi trường lưỡng cực tại một điểm xa $D$ nằm trên đoạn nối tiếp của các điện tích $(AD = r \gg l)$:

$$\varphi_1 = \frac{-q}{r} + \frac{q}{r-l} = \frac{q}{r} \left( -1 + \frac{1}{1-l} \right).$$

Chấp nhận sự tương ứng (1), chúng ta thu được phần chính của điện thế do lưỡng cực tạo ra:

$$\varphi_{\text{BN}} = \frac{ql}{r^2} = \frac{d}{r^2}.$$

Nếu điểm quan sát không nằm trên đường nối các điện tích thì vị trí của nó có thể được đặc trưng bởi hai tọa độ: khoảng cách đến một trong các điện tích và, ví dụ, góc giữa mômen lưỡng cực

$$\text{Рис. 2.}$$

Hình 3.

vectơ thể tích và bán kính vẽ từ điện tích dương *) đến điểm được quan sát.

Trong Hình 2, điểm $C$ được đặc trưng bởi tọa độ $\rho = BC$ và góc $\theta$. Trong trường hợp này, việc tính toán điện thế trở nên phức tạp hơn một chút. Hãy chỉ đưa ra kết quả:

$$\varphi_1 = \frac{d \cos \theta}{\rho^2}.$$

Để hình thành đa cực bậc hai (trường $(2^2$, thường được gọi là tứ cực) từ một lưỡng cực - đa cực bậc nhất - cần phải thêm vào lưỡng cực trước đó cùng một lưỡng cực, trộn ở một khoảng cách nào đó và thay đổi dấu của các điện tích trong nó thành ngược lại. Hãy làm điều này như trong Hình 3, $a$: chúng ta di chuyển lưỡng cực đến giá trị độ dài của nó $l$. (Việc trộn có thể được thực hiện ở khoảng cách ngắn hơn. Trong trường hợp này, việc tính toán sẽ dài hơn một chút.)

Nếu các điện tích là nhiều cực trên cùng một trục thì đa cực được gọi là trục. Hình 3, $b$ thể hiện phương trình cầu phương trục sinh ra từ hệ điện tích ở Hình 3, $a$, và trong Hình 3, $b$ trường hợp chung của phương trình cầu phương - các điện tích có độ lớn bằng nhau và trái dấu nằm đối xứng nhau tại các đỉnh của hình bình hành. Tiềm năng tăng gấp bốn lần $\varphi_2$,

*) Do $r \gg l$, kết quả không thay đổi nếu vectơ bán kính được vẽ từ điện tích âm.

⟦folio 5⟧

Hình 4.

theo công thức (4) phải tỉ lệ với $1/r^3$. Do đó, trong khai triển (1), chỉ cần tính đến các số hạng của tổng tối đa $x^2$ là đủ.

Hãy xác định hệ số tỉ lệ $C_2$ cho trục tứ cực như hình 3, 6. Phép tính sẽ được thực hiện cho điểm xa $D$ nằm trên trục của tứ cực:

$$\varphi_2 = \frac{q}{r} + \frac{(-2q)}{r-l} + \frac{q}{r-2l} \approx \frac{q}{r} \left[ 1 - 2 \left( 1 + \frac{l}{r} + \frac{l^2}{r^2} \right) + \left( 1 + \frac{2l}{r} + \frac{4l^2}{r^2} \right) \right] = \frac{2ql^2}{r^3}.$$

Bây giờ chúng ta hình thành một đa cực bậc ba, thường được gọi là bát cực, vì trong trường hợp tổng quát, nó bao gồm 8 điện tích có độ lớn bằng nhau. Với mục đích này, một tứ cực bổ sung (Hình 3, 6) đối xứng với tứ cực trục như trong Hình 4, $a$. Trong trường hợp này, chúng ta thu được một bát cực hướng trục (Hình 4, 6). Trong trường hợp chung, từ một tứ cực (Hình 3, 6), người ta thu được một bát cực, như trong Hình 4, $\theta$, các điện tích của chúng nằm ở các đỉnh của hình bình hành. Thế năng trường tĩnh điện của bát cực $\varphi_3$, theo công thức (4), phải tỷ lệ với $1/r^4$. Chúng ta hãy xác định điện thế được tạo ra bởi trường của bát cực dọc trục tại điểm $D$:

$$\varphi_3 = \frac{q}{r} + \frac{(-3q)}{r-l} + \frac{3q}{r-2l} + \frac{(-q)}{r-3l} \approx \frac{q}{r} \left[ 1 - 3 \left( 1 + \frac{l}{r} + \frac{l^2}{r^2} + \frac{l^3}{r^3} \right) + 3 \left( 1 + \frac{2l}{r} + \frac{4l^2}{r^2} + \frac{8l^3}{r^3} \right) - \left( 1 + \frac{3l}{r} + \frac{9l^2}{r^2} + \frac{27l^3}{r^3} \right) \right] = -\frac{6ql^3}{r^4}.$$

Các trường đa cực có bậc cao hơn được tính theo cách tương tự.

Khác xa với bất kỳ hệ thống điện tích nào, trường của hệ thống này có thể được biểu diễn bằng kết quả của việc cộng các trường đa cực có bậc khác nhau. Bậc của đa cực tương ứng với hệ điện tích đang xét càng cao thì toàn bộ hệ thống càng trung hòa và trường giảm càng nhanh theo khoảng cách từ các điện tích.

Chúng tôi đã kiểm tra tiềm năng của trường tĩnh điện được tạo ra bởi các đa cực dọc trục trên trục của chúng. Việc tính toán điện thế tại một điểm tùy ý trong không gian cũng được thực hiện theo cách tương tự, nhưng việc tính toán trở nên cồng kềnh hơn. Nếu biết loại điện thế đa cực $\varphi_n = C_n/r^{n+1}$ thì giá trị của cường độ điện trường $E$, và do đó lực $F = qE$ tác dụng từ đa cực lên điện tích $q$ được xác định duy nhất (xem § 76 trong sách giáo khoa “Vật lý-9”). Nếu $n \geq 0$ (đúng với mọi đa cực), thì

$$E \sim \frac{1}{r^{n+2}}.$$

Bỏ qua những chi tiết toán học, chúng ta hãy xem xét hình ảnh các đường sức của lưỡng cực và trục tứ cực, được trình bày trên các Hình 5, $a$ và 5, $\theta$. Hình 5, $a$ thể hiện trường lưỡng cực. Tổng cường độ điện trường $E$ tại mỗi điểm có được bằng cách cộng hình học trường điện tích dương $E_+$ với trường điện tích âm $E_-: E = E_+ + E_-$.

⟦folio 6⟧

Hình 5.

Trong hình, các vectơ này được hiển thị tại một trong các điểm trong không gian. Một hình ảnh tương tự được thể hiện trong Hình 5, b đối với bộ tứ trục. Tại mỗi điểm trong không gian, trường tổng E là kết quả của tổng của ba vectơ: hai vectơ định hướng $E_+$ của trường được tạo bởi các điện tích dương và một vectơ định hướng $E_-$ của trường được tạo bởi một điện tích âm, có độ lớn bằng tổng các điện tích dương. Sẽ thu được một bức tranh hoàn chỉnh về sự phân bố các đường sức điện trong không gian đối với một lưỡng cực và một bộ tứ nếu Hình 5 được biểu diễn xung quanh các trục đối xứng tương ứng.

Ngoài điện, bạn cũng có thể xem xét các đa mol từ tính - hệ thống bao gồm nam châm hoặc dòng điện kín. Sự khác biệt duy nhất là các điện tích từ riêng lẻ vẫn chưa được phát hiện, do đó việc xem xét phải bắt đầu ngay với lưỡng cực từ. Hình 5, c biểu diễn các đường cảm ứng của một lưỡng cực từ được hình thành bởi một dòng điện tròn $I$, mặt phẳng của nó vuông góc với mặt phẳng của hình. Ở khoảng cách lớn tính từ lưỡng cực, Hình 5, a và 5, c có hình dáng giống nhau.

Sự giống nhau của lưỡng cực từ với lưỡng cực điện có thể được minh họa bằng một ví dụ khác. Kim la bàn từ—một lưỡng cực từ—được định hướng dọc theo các đường chỉ thị từ. Một lưỡng cực điện hoạt động tương tự trong điện trường: nó cũng được lắp đặt dọc theo đường dây điện, tức là nó là một loại “la bàn điện” (Hình 6).

Ví dụ về đa mol điện là các nguyên tử và phân tử. Nếu, trong quá trình hình thành các phân tử do sự phân phối lại electron giữa các nguyên tử, tâm phân bố điện tích dương và âm trong đó không trùng nhau, thì các phân tử có mômen lưỡng cực riêng và được gọi là cực. Các phân tử axit clohydric và nước có tính phân cực (Hình 7). Nếu trong phân tử ULE, các điện tích dương và âm cách nhau một khoảng bằng bán kính của nguyên tử hydro ($l = 0,5 \times 10^{-8} \text{ cm}$), thì mômen lưỡng cực của phân tử phải có thứ tự $d = el^*$), tức là $d \approx 2,4 \cdot 10^{-18} \text{ cm} \times \text{ед. заряд} \text{ СГСЭ.}$. Thứ tự độ lớn của điều này phù hợp với dữ liệu thực nghiệm được hiển thị trong Hình 7. Nếu phân tử bao gồm các nguyên tử giống hệt nhau ($O_2, H_2, Cl_2$), thì các electron, nói theo nghĩa bóng, “không biết” nên chọn nguyên tử nào và sẽ nằm trong phân tửULE đồng đều hơn, dẫn đến giá trị bằng 0

*) Điện tích $e = 4,8 \cdot 10^{-10} \text{ ed. заряд} \text{ СГСЭ.}$

⟦folio 7⟧

Hình 6.

làm thay đổi momen lưỡng cực của phân tử. Các phân tử như vậy được gọi là không phân cực. Hình 7 cho thấy một phân tử carbon dioxide tuyến tính, CO₂, không phân cực. Hơn nữa, “sự xuất hiện” của phân tử này được gọi trên vật thể và sự phân bố lại các electron giữa các nguyên tử sẽ tạo thành một trục tứ cực từ nó (so sánh với Hình 3, 6), và điện trường do phân tử carbon dioxide tạo ra phải có dạng như trong Hình 5, 6.

Sự phân bố phức tạp hơn của các nguyên tử và electron trong phân tử dẫn đến sự hình thành các bậc đa cực được tính toán.

Ứng dụng. Tính điện thế tạo bởi một điện tích chính xác

Trong SGK Vật lý 9, các công thức tính thế điện trường tạo bởi một điện tích chính xác được đưa ra mà không cần dẫn xuất (xem công thức (8.28) và (8.29) trang 144). Chúng ta hãy trình bày một cách dẫn xuất đơn giản của các công thức này cho vykuma.

Nếu điện tích q chính xác nằm ở điểm O (Hình 8), thì thế năng φ của trường do nó tạo ra tại điểm N ở khoảng cách r tính từ điện tích q bằng công A mà điện trường thực hiện khi di chuyển một điện tích dương từ điểm N đến một điểm vô hạn mà tại đó φ = 0. Vì công chuyển vị không phụ thuộc vào hình dạng quỹ đạo mà điện tích di chuyển dọc theo, nên chúng ta sẽ giả sử rằng một điện tích đơn lẻ di chuyển dọc theo đường lực.

Hãy tính xem công việc này đã bằng bao nhiêu? Để làm điều này, chúng ta sẽ chia toàn bộ quãng đường mà một điện tích dương đi được thành các phần rất nhỏ NN₁, N₁N₂, N₂N₃, v.v. (xem Hình 8). Trong mỗi phần này, chúng tôi tính toán công chuyển động của một điện tích. Tổng các công này bằng điện thế trường tại điểm N đối với vô cùng.

Hãy tính công A₁ khi di chuyển một điện tích từ điểm N đến điểm N₁, điểm này nằm cách N một khoảng rất nhỏ (r₁−r). Như trình bày trong sách giáo khoa “Vật lý-9” (xem công thức (8.20)), trong một điện trường đều, công có hướng E để di chuyển một điện tích đơn vị bằng số với

$$A = E(r₁−r).$$

Tất nhiên, trường điện tích chính xác không đồng nhất. Tính định hướng của nó tại điểm N bằng E_N = q/r² và tại điểm N₁E_N = q/r²!.

Chúng ta nên thay thế giá trị nào của E vào công thức (1)? Rõ ràng, cần phải lấy giá trị định hướng trường sẽ là giá trị trung bình giữa hai giá trị này. Vì r và r₁ khác nhau một chút, nên khi kết hợp r² và r₁² trong các biểu thức cho hướng của E_N và E_N₁, chúng ta có thể lấy tích rr₁, lớn hơn r²=rr một chút và nhỏ hơn một chút so với r₁²=r₁r₁. Khi đó chúng ta có thể giả sử rằng trong toàn bộ phần NN₁ hướng của trường được xác định theo công thức

$$E_{NN_1} = \frac{q}{rr_1}.$$

Trong trường hợp này, công việc A₁ sẽ bằng về mặt số lượng

$$A_1 = \frac{q}{rr_1}(r_1−r),$$

hoặc

$$A_1 = \frac{q}{r} - \frac{q}{r_1}.$$

Theo cách tương tự, bạn có thể tính công để di chuyển một điện tích từ điểm N₁ đến
