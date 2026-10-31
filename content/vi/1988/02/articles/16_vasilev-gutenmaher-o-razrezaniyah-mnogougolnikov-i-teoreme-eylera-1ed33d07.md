---
id: 1988-2-vasilev-gutenmaher-o-razrezaniyah-mnogougolnikov-i-teoreme-eylera-1ed33d07
issue: kvant_1988_2
year: 1988
number: "2"
title: Về cắt đa giác và định lý Euler
authors:
  - Васильев Н. Б.
  - Гутенмахер В. Л.
rubric: shkola-v-kvante
page_first: 54
page_last: 56
page_labels: 52-54
tag: TWNF
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 02e75cbe85d8a37a1e57e6ed7e419673a3d4d7ba9178c6d44b5d92fadeaefc37
prompt_sha256: draft-1
translated_from: content/ru/1988/02/articles/16_vasilev-gutenmaher-o-razrezaniyah-mnogougolnikov-i-teoreme-eylera-1ed33d07.md
source_content_sha256: ed694020abeaa445f6c5d4e58a4915c960f88c7b0f76a605b0b1bf2b714f960c
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 52⟧

biệt danh: tổng các góc ngoài của nó là 360° (hình 4).

Vì mỗi góc ngoài cộng với góc trong liền kề của nó cộng lại bằng 180°, nên tổng tất cả các góc trong của một n-giác là 180°n−360°=180°(n−2).

Kết quả này được chứng minh khác trong sách giáo khoa: một n-giác lồi có thể chia thành n−2 hình tam giác bằng các đường chéo vẽ từ một đỉnh; tổng tất cả các góc của chúng, hiển nhiên bằng tổng tất cả n góc của một n-giác, lớn hơn (n−2) lần tổng các góc của một tam giác.

Bất kỳ, không nhất thiết phải lồi, n-giác có tổng các góc bằng nhau. Nhưng bằng chứng có phần phức tạp hơn.

Nếu bạn đang cố gắng đi xung quanh một đa giác "phức tạp" dọc theo một đường viền và tính tổng các góc ngoài - góc quay, thì trước tiên, bạn sẽ cần tính đến các hướng quay: góc quay ngược chiều kim đồng hồ được coi là dương và các phép quay theo chiều kim đồng hồ được coi là âm (các phép quay như vậy tương ứng với các góc trong lớn hơn 180°); thứ hai, không quá rõ ràng là do đi ngang qua đa giác (một đường đa giác không tự giao nhau), nên toàn bộ góc quay sẽ là một góc quay hoàn toàn 360°. Lưu ý khi đi quanh đường đứt đoạn tự giao nhau tại hình 5 - điểm của ngôi sao góc - thước thực hiện hai vòng đầy đủ, tức là tổng các góc ngoài tại các đỉnh của ngôi sao

Hình 3.

Hình 4.

Hình 5.

720° là đúng (có nghĩa là tổng các góc trong của nó luôn bằng 180°×5−720°=180°; kiểm tra kết quả này bằng cách kiểm tra các hình tam giác và góc điểm lồi tạo nên ngôi sao).

Bạn có thể chứng minh định lý về tổng các góc của đa giác bất kỳ (không nhất thiết phải lồi) bằng phương pháp cắt. Nhưng nhiều hơn về điều đó trong bài viết tiếp theo.

Về độ phân giải đa giác và định lý Euler

Theo đa giác bây giờ chúng ta muốn nói đến một phần của mặt phẳng được cắt ra bởi một đường đứt nét không giao nhau. Hãy bắt đầu với thực tế là, như chúng ta đã làm trong ghi chú trước, chúng ta sẽ chứng minh định lý về tổng các góc của bất kỳ đa giác nào (không nhất thiết phải lồi) bằng phương pháp cắt.

Tất nhiên, trong trường hợp tổng quát không thể tìm được một đỉnh mà từ đó tất cả các đỉnh khác đều “nhìn thấy được” (như đối với đa giác lồi). Thậm chí còn không hoàn toàn rõ ràng rằng có thể tìm thấy ít nhất một đường chéo nằm hoàn toàn bên trong n-giác. Nhưng sự thật này là đúng.

Bổ đề. Từ bất kỳ đỉnh nào của newgon, góc tại đó lớn hơn 180°, bạn có thể vẽ một đường chéo nằm hoàn toàn bên trong đa giác này.

Chúng ta hãy xem xét tất cả các tia có thể phát ra từ một đỉnh như vậy bên trong đa giác (hình 1). Chúng “chiếu sáng”, có lẽ một phần, bằng

⟦folio 53⟧

ít nhất hai cạnh của đa giác. Trên thực tế, tất cả các tia chiếu sáng một phía sẽ tạo thành một góc nhỏ hơn 180°. Vì vậy, một góc của đa giác (lớn hơn 180°) được chia thành ít nhất hai góc, được tạo thành bởi các tia chiếu sáng các cạnh khác nhau của đa giác. Khi đó tia phân cách hai góc như vậy hướng tới đỉnh của đa giác - dọc theo một đường chéo nằm hoàn toàn bên trong đa giác.

Bằng cách sử dụng bổ đề nhiều lần, bất kỳ $n$-giác nào cũng có thể được cắt thành hình tam giác. Nhưng chúng ta cũng cần để ý đến số lượng hình tam giác. Giống như nhiều định lý khác liên quan đến số tự nhiên tùy ý $n$, cách thuận tiện nhất để hình thành chứng minh là sử dụng quy nạp toán học.

Về quy nạp toán học

Ở đây chúng tôi sử dụng các nguyên tắc quy nạp toán học ở dạng này. Giả sử một phát biểu nào đó, trong công thức của số tự nhiên $n$, đúng với $n=n_0$, và từ thực tế là nó đúng với mọi $n$ sao cho $n_0 \leq n < N$, suy ra rằng nó đúng với $n=N$. Vậy thì nó đúng với tất cả tự nhiên $n \geq n_0$.

Hãy chứng minh phát biểu cần tìm bằng quy nạp.

Định lý. Tổng các góc của một $n$-gon tùy ý (không nhất thiết phải lồi) là 180°($n-2$).

Đối với $n=3$ điều này đúng. Hãy để tuyên bố của chúng tôi đúng với tất cả $n<N$ ($n \geq 3$). Hãy xem xét một neoctorium $N$-gon. Theo bổ đề, nó có thể được cắt theo đường chéo thành hai đa giác. Giả sử một trong số chúng có $K$ cạnh từ một $N$-giác lớn - tức là nó là $(K+1)$-giác, cái còn lại có $N-K$ các cạnh còn lại - và do đó nó là $(N-K+1)$-giác. Theo giả thuyết quy nạp, tổng các góc của chúng là $180^\circ(K-1)$ và $180^\circ(N-K-1)$. Cộng lại, chúng ta thấy rằng tổng tất cả các góc của $N$-giác là $180^\circ(K-1)+180^\circ(N-K-1)=180^\circ(N-2)$. Định lý đã được chứng minh.

Nhìn nhận lại, chúng ta có thể rút ra kết luận sau: đối với bất kỳ sự cắt nào

⟦folio 54⟧

Hình 2.

Định lý bản đồ Euler. Cho B điểm được chọn trên mặt phẳng và chúng được nối với nhau bằng P đoạn thẳng để tạo thành một đa giác, chia thành M đa giác khác theo đúng cách (hình 2). Khi đó B—P+M=1.

Bằng chứng. Giả sử một đa giác lớn (bên ngoài) có n cạnh (và n đỉnh) và số cạnh của M đa giác mà nó được cắt vào là n1, n2, ..., nM. Trong số các đỉnh B của bản đồ, có n đỉnh nằm trên đường biên và (B-n) nằm bên trong đa giác lớn. Tính tổng các góc của tất cả M đa giác theo hai cách, ta thu được đẳng thức $180^\circ(n_1-2)+...+180^\circ(n_M-2) = 180^\circ(n-2)+360^\circ(B-n)$,

Ở đâu
$$n_1+n_2+...+n_M-2M=2B-n-2.$$

Bây giờ chúng ta hãy lưu ý rằng trong tổng $n_1+n_2+...+n_M+n$ mỗi đoạn P tham gia hai lần - nó đóng vai trò là các cạnh của hai đa giác (tuyến tính
<table><thead><tr><th></th><th>B</th><th>P</th><th>Γ</th></tr></thead><tbody><tr><td>khối lập phương</td><td>8</td><td>12</td><td>6</td></tr><tr><td>tứ diện</td><td>4</td><td>6</td><td>4</td></tr><tr><td>kim tự tháp 5 cạnh</td><td>6</td><td>10</td><td>6</td></tr><tr><td>bát diện</td><td>6</td><td>12</td><td>8</td></tr><tr><td>khối mười hai mặt</td><td>20</td><td>30</td><td>12</td></tr></tbody></table>

Hình 3.

Hình 4.
