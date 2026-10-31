---
id: 1983-2-pontryagin-kompleksnyie-chisla-c1604a8d
issue: kvant_1983_2
year: 1983
number: "2"
title: số phức
authors:
  - Понтрягин Л. С.
rubric: raznoe
page_first: 18
page_last: 20
page_labels: 16-18
tag: "8038"
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 8ae69274ced873fcedf27e2d7ca4866e49c8bdcb1513ba38fae3e832513aa741
prompt_sha256: draft-1
translated_from: content/ru/1983/02/articles/04_pontryagin-kompleksnyie-chisla-c1604a8d.md
source_content_sha256: f7922042e1d98d4d9a266d9f0f4c26fa8016cca995a58ebf0e9918e8f55576b6
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 16⟧

số phức

Viện sĩ L. S. PONTRYAGIN

Ở đây trước hết tôi nói rất ngắn gọn về cách các số phức nảy sinh trong toán học và dần dần hình thành trong đó. Sau đó tôi đưa ra định nghĩa về số phức, các phép tính trên chúng và giải thích hình học của chúng. Đồng thời, các công thức tính cosin và sin của một tổng đã được chứng minh, chúng có liên quan chặt chẽ đến phép nhân số phức.

Bối cảnh lịch sử

Từ quá trình toán học, người ta biết rằng các số âm được đưa vào chủ yếu để phép trừ, nghịch đảo của phép cộng, luôn có thể thực hiện được. Vì lý do tương tự, số phức xuất hiện trong toán học. Nếu chúng ta chỉ xem xét các số thực, thì thao tác trích căn bậc hai, nghịch đảo của phép tính bình phương, không phải lúc nào cũng thực hiện được, vì không thể trích căn bậc hai của một số âm. Tuy nhiên, điều này không đủ để giới thiệu những con số mới trong toán học. Hóa ra là nếu tích của một phép tính theo các quy tắc thông thường đối với các biểu thức trong đó xảy ra căn bậc hai của một số âm, thì người ta có thể đi đến kết quả không còn chứa căn bậc hai nữa.

Định nghĩa số phức

Chúng ta sẽ giả định rằng chúng ta biết các con số thực. Chúng ta biết rằng có hai phép toán cơ bản được xác định cho chúng - phép cộng và phép nhân - và có những hành động nghịch đảo đối với chúng - phép trừ và phép chia. Đối với những hành động này, một số quy tắc được trích xuất sẽ được thực thi, thường được sử dụng hoàn toàn tự động - vì vậy tôi sẽ không xây dựng chúng ở đây. Tập hợp các đối tượng mà các phép tính cộng, nhân và các hành động nghịch đảo của phép trừ và phép chia được xác định và các quy tắc đối tượng áp dụng cho số thực được thực hiện, được gọi là một trường trong đại số trừu tượng hiện đại.

Do đó, theo quan điểm của đại số trừu tượng hiện đại, tập R của tất cả các số thực biểu diễn một trường. Bây giờ chúng ta hãy đặt bài toán để mở rộng khái niệm về số hoặc, như

⟦folio 17⟧

chẳng hạn trong đại số trừu tượng, hãy mở rộng trường $R$ sang trường $K$ sao cho trong trường mới này $K$ phương trình

$$z^2 + 1 = 0$$

(1)

đã có lời giải. Chúng ta biểu thị phần tử trường $K$ thỏa mãn phương trình (1) bằng $i$. Vì vậy, với $i$ chúng ta có

$$i^2 = -1.$$

(2)

Vì trường $K$ chứa tất cả các số thực và phần tử $i$ và vì có thể thực hiện các phép tính cộng và nhân trong đó nên trường $K$ phải chứa tất cả các đa thức có thể có đối với $i$ với các hệ số thực, đặc biệt - tất cả các đa thức bậc một, tức là các biểu thức có dạng

$$z = x + yi = x + iy,$$

trong đó $x$ và $y$ là số thực. Những biểu thức này được gọi là số phức. Chúng ta định nghĩa các hành động trên chúng là các hành động trên đa thức, có tính đến các điều kiện (2). Số phức có dạng

$$z = x + 0i = x$$

là những số thực. Số phức có dạng

$$z = 0 + yi = yi$$

Các số được gọi là số tối thiểu.

Cho $z_1 = x_1 + y_1 i$, $z_2 = x_2 + y_2 i$ là hai số phức. Theo quy tắc đã nêu, tổng và tích của các số phức này được xác định bằng các đẳng thức

$$z_1 + z_2 = (x_1 + y_1 i) + (x_2 + y_2 i) =$$

$$= (x_1 + x_2) + (y_1 + y_2) i;$$

(3)

$$z_1 z_2 = (x_1 + y_1 i) (x_2 + y_2 i) =$$

$$= x_1 x_2 + (x_1 y_2 + y_1 x_2) i + y_1 y_2 i^2 =$$

$$= (x_1 x_2 - y_1 y_2) + (x_1 y_2 + y_1 x_2) i.$$

(4)

Khi đạt được đẳng thức cuối cùng, chúng ta sử dụng kết quả

$$x_1 z_2 = x_1 x_2 + x_1 y_2 i.$$

(5)

Từ công thức (3) và (4) rõ ràng tổng và tích của hai số phức cũng là số phức.

Để đảm bảo rằng hành động trừ, nghịch đảo của hành động cộng, tồn tại, chỉ cần tìm số $-z$, số đối diện với số $z$, và để đảm bảo rằng phép chia có thể thực hiện được, chỉ cần $z \neq 0$ chỉ ra số $z^{-1}$, nghịch đảo của số $z = x + yi$ là đủ. Những con số này, dễ dàng nhận thấy, được đưa ra bởi các công thức

$$-z = -x - yi,$$

$$z^{-1} = \frac{x}{x^2 + y^2} - \frac{y}{x^2 + y^2} i.$$

Do đó, đại lượng $z^{-1}$, nghịch đảo của $z$, tồn tại bất cứ khi nào $z \neq 0$.

Biểu diễn hình học của số phức

Chúng ta hãy biểu thị mặt phẳng của bản vẽ của chúng ta bằng $P$ và chọn hệ tọa độ hình chữ nhật trên đó (Hình 1). Chúng ta sẽ đặt số phức $z = x + yi$ tại điểm $z = (x; y)$ có ​​tọa độ $x, y$. Chúng ta cũng biểu thị bằng $z$ vectơ từ gốc $O$ đến điểm $z$. Do đó, chữ cái $z$ đồng thời biểu thị một số phức, điểm $z$, đại diện cho số phức này và vectơ $z$, tương ứng với số phức này. Trong trường hợp này, ảnh của số thực nằm trên trục hoành - do đó trục hoành được gọi là trục thực của mặt phẳng $P$ của biến phức và số của số rơi trên trục hoành - do đó trục hoành được gọi là trục tối thiểu của mặt phẳng $P$ của biến phức. Số 0 rơi ở gốc tọa độ.

Hình 1.

⟦folio 18⟧

Độ dài của vectơ $z$ được gọi là mô đun của số phức $z = x + yi$ và được ký hiệu là $|z|$:

$$|z| = \sqrt{x^2 + y^2}.$$

Các số phức $z$ thỏa mãn điều kiện $|z| = 1$ tạo thành một đường tròn bán kính 1 có tâm tại gốc tọa độ. Số 1 nằm trên vòng tròn này. Từ điểm 1, chúng ta cắt các cung có độ dài cho trước $\varphi$ dọc theo đường tròn theo hướng ngược chiều kim đồng hồ. Chúng tôi biểu thị sự kết thúc của cung này bằng $(\varphi)$. Nếu $\varphi$ là số âm thì để thu được $(\varphi)$ bạn cần trừ độ dài cung $|\varphi|$ từ điểm 1 theo chiều kim đồng hồ. Như đã biết, trục hoành của điểm $(\varphi)$ được gọi là cos $\varphi$, và tọa độ của nó là sin $\varphi$. Do đó, số phức $(\varphi)$ được cho bởi

$$(\varphi) = \cos \varphi + i \sin \varphi.$$

Vì vậy, mọi số phức $z$, bằng 1 theo mẫu, đều được viết dưới dạng (6). Nếu $z$ là một số phức tùy ý có mô hình $|z| = \varphi$ khác 0, thì số $z/\varphi$ là một số phức, theo mô hình, bằng 1 và do đó được viết dưới dạng (6). Từ sự bình đẳng

$$\frac{z}{\varphi} = \cos \varphi + i \sin \varphi$$

chúng tôi nhận được

$$z = \varphi(\cos \varphi + i \sin \varphi).$$

Ghi (7) được gọi là công thức lượng giác của số phức. Số $\varphi$ được gọi là đối số của số phức. Nếu mô hình $\varphi$ của số phức $z$ khác 0 thì đối số $\varphi$ được xác định theo thuật ngữ $2\pi k$, trong đó $k$ là một số nguyên. Nếu mô hình $\varphi$ của một số phức bằng 0 thì công thức (7) cũng đúng, nhưng trong trường hợp này, đối số của số phức hoàn toàn không được xác định.

Các số $\varphi$ và $\varphi$ được gọi là tọa độ cực của điểm $z$.

Bây giờ chúng ta hãy đưa ra một nguồn tác dụng hình học đối với số phức.

Từ công thức (3) và (5) suy ra rằng số phức được cộng và nhân với số thực, giống như vectơ.

Ý nghĩa hình học của việc cộng số phức rất rõ ràng: vectơ $z_1 + z_2$ là đường chéo của hình bình hành được xây dựng trên các vectơ $z_1$ và $z_2$. Điều này dẫn đến một bất đẳng thức quan trọng:

$$|z_1 + z_2| \leq |z_1| + |z_2|.$$

Để đưa ra phép nhân nguồn hình học của các số phức, bạn cần sử dụng thao tác quay một vectơ hoặc tương tự như một số phức. Xoay vectơ $z$ ngược chiều kim đồng hồ theo góc $\alpha$, chúng ta nhận được một số vectơ mới, được biểu thị bằng $R_\alpha(z)$. Rõ ràng về mặt hình học là phép quay $R_\alpha$ có tính chất sau: nếu $\alpha$ là một số thực thì

$$R_\alpha(az) = aR_\alpha(z),$$

$$R_\alpha(z_1 + z_2) = R_\alpha(z_1) + R_\alpha(z_2).$$

Từ hai công thức này suy ra rằng nếu $a_1$ và $a_2$ là hai số thực thì có sự tương ứng

$$R_\alpha(a_1z_1 + a_2z_2) = a_1R_\alpha(z_1) + a_2R_\alpha(z_2).$$

Cũng rõ ràng ngay rằng

$$R_\alpha(1) = \cos \alpha + i \sin \alpha.$$

Bây giờ chúng ta hãy chứng minh rằng việc xoay số phức $z = x + yi$ theo góc $\alpha$ tương đương với việc nhân nó với số phức $\cos \alpha + i \sin \alpha$, nghĩa là

$$R_\alpha(z) = (\cos \alpha + i \sin \alpha)z.$$

Để làm điều này, trước tiên chúng ta xem xét riêng phép quay qua góc $d = \frac{\pi}{2}$. Trong trường hợp này, $\cos d + i \sin d = i$ và đẳng thức (11) có dạng $R_d(z) = iz$. Một mặt, có các ước tính hình học là $R_d(1) = i$, $R_d(i) = -1$. Mặt khác, $i \cdot 1 = i$, $i \cdot i = -1$. Như vậy,

$$R_d(1) = i \cdot 1, R_d(i) = i \cdot i.$$

Nó suy ra trực tiếp từ công thức (9)
