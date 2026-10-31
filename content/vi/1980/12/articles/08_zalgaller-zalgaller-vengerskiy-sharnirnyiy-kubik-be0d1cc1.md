---
id: 1980-12-zalgaller-zalgaller-vengerskiy-sharnirnyiy-kubik-be0d1cc1
issue: kvant_1980_12
year: 1980
number: "12"
title: Khối bản lề Hungary
authors:
  - Залгаллер В. А.
  - Залгаллер С. И.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 19
page_last: 22
page_labels: 17, 18, 20
tag: D22T
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 0b53b00809d1c57d96d1c5f050488606cd3a4c60727d7fea0e84850ead1a767d
prompt_sha256: draft-1
translated_from: content/ru/1980/12/articles/08_zalgaller-zalgaller-vengerskiy-sharnirnyiy-kubik-be0d1cc1.md
source_content_sha256: b6567d5ea7802a05f85e44fd6b1694a2e91640f80742d468070cc03f2312675a
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 17⟧

Sở thích giải các câu đố toán học, được sáng tạo vào năm 1975 bởi kiến ​​trúc sư người Hungary, Giáo sư Ernő Rubik, đang lan rộng ở Cộng hòa Nhân dân Hungary. Hình dáng của nó được thể hiện ở trang thứ tư của bìa: nó là một khối nhựa được chia thành 27 khối tắc nghẽn. Khối bên trong được lấy ra và 26 khối bên ngoài được lồng vào nhau bằng cách sử dụng các phần nhô ra đặc biệt để bất kỳ viên gạch nào trong số 9 khối liền kề với một cạnh của khối có thể xoay 90° theo bất kỳ hướng nào. (Phần đầu của hai phép quay như vậy được hiển thị trong Hình 1.) Sau một phép quay 90°, toàn bộ hệ thống vẫn giữ nguyên khả năng tự do quay: một lần nữa, bất kỳ ô nào theo bất kỳ hướng nào đều có thể được quay 90° trong mặt phẳng của nó.

Có thể viết một bài viết riêng về thiết kế bản lề của những chiếc cốc này - bây giờ chúng ta sẽ thảo luận về một vấn đề khác.

Ban đầu, mỗi mặt của khối lập phương lớn được sơn một màu khác nhau (đỏ, cam, vàng, lục, lam, trắng). Sau một loạt các phép quay được chọn ngẫu nhiên, màu sắc của các mặt của khối lập phương trở nên đa dạng: có các ô có màu khác nhau trên cạnh. Câu đố là, khi nhận được một khối lập phương đầy màu sắc như vậy trong tay, hãy thêm, bằng cách xoay, sắp xếp *chính xác* các hình khối, nghĩa là sắp xếp sao cho mỗi mặt của khối lập phương sẽ lại có cùng một màu.

Bài toán việc này không đơn giản chút nào. Một người không được trang bị lý thuyết, thậm chí là một người có năng lực, hiếm khi có thể thu thập ngay được nhiều hơn một khía cạnh. Số lượng sắp xếp khối lập phương có thể đạt được (ước tính là có $N=43\ 252\ 003\ 274\ 489\ 856\ 000$) khiến nó không thể truy cập được bằng vũ lực ngay cả trên máy tính. Tuy nhiên, lưu ý rằng không thể đạt được bất kỳ sự sắp xếp nào bằng cách xoay các khối lập phương: nếu bạn cho phép tách khối thành 26 khối, thì bạn có thể tạo $12 \cdot N=529\ 024\ 039\ 393\ 878\ 272\ 000$ các cách sắp xếp khác nhau (xem bài toán 8 từ Phụ lục).

Hiện tại, chúng tôi cung cấp các quy tắc dành cho người đọc (chúng không phải là quy tắc tiết kiệm nhất về số vòng quay) cho phép bất kỳ cách sắp xếp hình khối nào trong số $N$ có thể được đưa trở lại cách sắp xếp chính xác của chúng.

Mô tả các phép quay

Để phác thảo các quy tắc, điều khoản và điều kiện được đề xuất trước tiên về thuật ngữ.

Chúng ta sẽ gọi *trung tâm* là các hình khối nằm ở tâm các mặt của hình lập phương. Mỗi khối trung tâm luôn là trung tâm và hướng ra ngoài từ một hình vuông có màu được chỉ định.

Vì chúng ta không quan tâm đến sự thay đổi vị trí của toàn bộ khối lập phương trong không gian mà chỉ quan tâm đến sự thay đổi vị trí tương đối của phần của nó, nên chúng ta sẽ coi vị trí của nó trong không gian là cố định. Nó có nghĩa là:

Hình 1.

⟦folio 18⟧

Điều đó có nghĩa là vị trí của tất cả các cốc trung tâm trong không gian không thay đổi. Điều này cũng có nghĩa là trong số chín mặt phẳng của khối lập phương, chúng ta sẽ chỉ xoay được sáu mặt phẳng.

Nếu trong hình, một ô trung tâm nhất định được đánh dấu bằng chữ cái $A$ thì chúng ta sẽ biểu thị phép quay (không phải “giữa”) của ô chứa ô này theo $90^\circ$ theo chiều kim đồng hồ là $A$ và phép quay của cùng một ô đó theo $90^\circ$ ngược chiều kim đồng hồ sẽ được biểu thị là $A^{-1}$. Rõ ràng là $A^{-1}A^{-1}A^{-1}=A$ và $A^2=A^{-2}$, trong đó $A^2=A$ và $A^{-2}=A^{-1}$ $A^{-1}$.

Các hình lập phương chứa phần giữa của cạnh của hình lập phương lớn sẽ được gọi là hình trung bình. Khối ở giữa luôn ở mức trung bình và hướng ra ngoài với hai ô có màu xác định. Đối với mỗi cặp màu (ngoại trừ những cặp màu ban đầu được sơn ở các cạnh đối diện của khối lập phương), có một khối ở giữa duy nhất chứa các ô có các màu này.

Khối Uel là khối chiếm các vị trí góc trong khối lập phương. Mỗi khối góc luôn là khối góc và hướng ra ngoài tới hình vuông thứ ba được bao quanh bởi các màu khác nhau. Sự tương ứng của ba màu này là khác nhau đối với mỗi cốc ở góc.

Giai đoạn chính

Thoạt nhìn, một con đường hấp dẫn: tăng dần vị trí của các ô thanh đơn, lấy cạnh một thanh, rồi lấy một cạnh khác - dường như chỉ dẫn đến những khó khăn không thể vượt qua. Không thể so sánh với câu đố, họ sẽ xé nó ra - vì tức giận hoặc vì tò mò về cấu trúc của bản lề. Chúng tôi đang trên

Chúng tôi hy vọng rằng phương pháp lời giải được đề xuất dưới đây sẽ giúp câu đố có thể tiếp cận được nhưng nó cũng yêu cầu một số điều kiện nhất định để thực hiện.

Chúng tôi sẽ chia các hành động đề xuất thành bốn giai đoạn lớn. Chúng ta đã đồng ý rằng trong lời giải của câu đố, các khối trung tâm không thay đổi vị trí của chúng trong không gian. Đối với các cốc ở giữa, trong quá trình xử lý lời giải, mỗi cốc phải chiếm một vị trí nhất định trong sóng: xuất hiện ở cạnh giữa hai mặt “riêng” của hình lập phương, tức là những mặt đó có các ô trung tâm cùng màu với hai ô của hình lập phương ở giữa đã cho. Ngoài ra, nó phải được xoay chính xác: các ô màu của nó phải liền kề với các ô trung tâm cùng màu. Tình huống hoàn toàn tương tự với các cốc góc: mỗi cốc có một vị trí riêng (tại điểm giao nhau của ba mặt với các ô trung tâm cùng màu của nó) và một lượt rẽ đúng duy nhất. Theo đó, quy trình của chúng tôi sẽ như sau:

1. Đặt tất cả các khối ở giữa vào đúng vị trí.
2. Xoay tất cả các hình khối ở giữa một cách chính xác vào đúng vị trí của chúng.
3. Đặt tất cả các khối góc vào đúng vị trí.
4. Xoay tất cả các khối góc một cách chính xác.

Chúng tôi sẽ chỉ thực hiện từng giai đoạn sau khi giai đoạn trước đã hoàn thành. Đồng thời, chúng tôi sẽ thực hiện giai đoạn tiếp theo sao cho sau khi hoàn thành, chúng tôi sẽ không bị gián đoạn bởi thành quả của các giai đoạn trước.

⟦folio 20⟧

Rõ ràng, hoán vị từng cặp của các khối ở giữa cho phép chúng ta thực hiện giai đoạn 1: đặt tất cả các khối ở giữa vào vị trí của chúng.

Giai đoạn 2: Xoay các khối ở giữa

Mười hai vòng xoắn kết hợp
$$K_2 = (AB^{-1}A^{-1}B)(BC^{-1}B^{-1}C)(CA^{-1}C^{-1}A)$$
đồng thời xoay các khối 1 và 2 trong tổ của chúng (Hình 4) và không thay đổi vị trí hoặc góc quay của các khối ở giữa còn lại (kiểm tra!).

Sự kết hợp $K_2$ cho phép bạn xoay hai khối ở giữa bất kỳ vào vị trí của chúng. Thật vậy, nếu chúng không liền kề với cùng một cạnh hoặc không liền kề với nó, thì bạn luôn có thể sử dụng các lượt quay phụ (hãy nhớ các lượt này theo màu của tâm ô được xoay) để đưa hai khối mong muốn đến vị trí 1, 2 (Hình 4), xoay chúng với tổ hợp $K_2$, sau đó, theo thứ tự ngược lại và theo hướng ngược lại, hãy xoay các lượt phụ.

Việc xoay các khối ở giữa theo từng cặp có thể thực hiện được giai đoạn 2, vì (do tính chất 1) không thể xảy ra trường hợp chỉ một khối ở giữa cần quay.

Giai đoạn 3: khối góc - tại chỗ

Mười hai vòng xoắn kết hợp
$$K_3 = (ABA^{-1}B^{-1})^3$$
thực hiện việc sắp xếp lại đồng thời các khối 1, 2 và các khối 3, 4 (Hình 5), bảo toàn tất cả thành tích của giai đoạn 1, 2 và không thay đổi vị trí của các khối góc ngoài 1, 2, 3, 4 (kiểm tra!)

Sự kết hợp của mười hai bốn lượt
$$K_4 = (ACA^{-1}C^{-1})^3(B^{-1}A^{-1}BA)^3$$
sắp xếp lại các khối 1, 2, 3 (Hình 6) theo sơ đồ $1 \rightarrow 2 \rightarrow 3 \rightarrow 1$, lưu tất cả thành tích của giai đoạn 1, 2 và không thay đổi vị trí của các khối góc ngoài 1, 2, 3.

Hãy để chúng tôi giải thích cách sử dụng kết hợp $K_3$ và $K_4$ để thực hiện giai đoạn 3.

Giả sử rằng sau khi hoàn thành giai đoạn 2, một số khối ở góc không còn ở đúng vị trí của chúng. Do tính chất P nên sẽ có ít nhất ba hình lập phương như vậy. Hãy chọn một trong số chúng và đánh dấu nó bằng số 1. Khối chiếm vị trí mà khối 1 phải đến sẽ được đánh dấu bằng số 2.

Nếu bản thân khối 2 sẽ di chuyển đến vị trí của khối 1, thì với số 3, chúng ta sẽ đánh dấu bất kỳ khối góc nào khác với hai khối đầu tiên và đứng lệch vị trí, và với số 4 - khối đứng ở vị trí của khối 3. Sau đó, sử dụng các lượt rẽ phụ (hãy nhớ chúng), chúng ta sẽ đặt các khối 1, 2 và 3, 4 vào vị trí của các cặp 1, 2 và 3, 4 như trong Hình 5. Sử dụng tổ hợp $K_3$ chúng ta sẽ tiến hành sắp xếp lại $1 \rightarrow 2, 3 \rightarrow 4$, sau đó theo thứ tự ngược lại và các lượt quay có chủ ý ngược lại.

Kết quả là, ngoài các khối góc đã đứng ở vị trí trước đó, việc xoay các khối 1, 2, 3 vào vị trí của chúng đã hoàn thành.

Nếu khối 2 không được cho là ở vị trí của khối 1, thì chúng ta đánh dấu khối 3 bằng số 3 ở vị trí của khối 2. Nếu khối 3 không đến vị trí của khối 1, thì chúng ta đánh dấu khối 4 bằng số 4 ở vị trí khối 3. Sau đó, như trên, tức là với sự trợ giúp của các phép quay phụ và sự kết hợp $K_3$, việc sắp xếp lại $1 \rightarrow 2, 3 \rightarrow 4$ được thực hiện, đặt nó vào vị trí của các khối 1 và 3.

Vẫn còn trường hợp cần phải sắp xếp lại các hình khối $1 \rightarrow 2 \rightarrow 3 \rightarrow 1$. Trong trường hợp này, với sự trợ giúp của các vòng quay phụ (hãy nhớ chúng), chúng ta đặt các khối 1, 2, 3 theo thứ tự nào đó thay cho 1, 2, 3 (Hình 6). Tuy nhiên, trong hai tổ hợp $K_4, K_4^{-1}$ thực hiện sắp xếp lại các vị trí $1 \rightarrow 2 \rightarrow 3 \rightarrow 1, 1 \rightarrow 3 \rightarrow 2 \rightarrow 1$, các khối $1 \rightarrow 2 \rightarrow 3 \rightarrow 1$ (nằm ở vị trí 1, 2, 3) sẽ thực hiện việc sắp xếp lại. Hãy thực hiện sự kết hợp chính xác này. Sau đó, chúng ta sẽ rẽ các ngã rẽ phụ theo thứ tự ngược lại và theo hướng ngược lại. Kết quả là các khối 1, 2, 3 sẽ rơi vào đúng vị trí.

Lặp lại quá trình này, chúng ta sẽ hoàn thành bước 3 - chúng ta sẽ đặt tất cả các hình khối ở góc vào đúng vị trí của chúng.

Bước 4: Xoay các khối góc

Chúng ta sẽ cần hai sự kết hợp sau:
$$K_5 = [(A^{-1}CAC^{-1})(C^{-1}BCB^{-1})(B^{-1}ABA^{-1})]^2, K_5^{-1} = [(AB^{-1}A^{-1}B)(BC^{-1}B^{-1}B)(BA^{-1}B^{-1}A)]^2.$$

Sự kết hợp $K_5$ đồng thời xoay từng khối 1, 2, 3 (Hình 7) của bộ đi từ tâm của nó đến tâm của khối. 120° theo chiều kim đồng hồ. Tổ hợp $K_5^{-1}$ xoay các hình khối giống nhau ngược chiều kim đồng hồ. Vị trí và góc quay của bất kỳ khối nào khác không thay đổi.

Biết sự kết hợp của $K_5$ và $K_5^{-1}$ cho phép bạn cùng nhau rẽ theo hướng mong muốn (nhưng cùng hướng) hoặc ba khối góc. Chỉ cần thu thập chúng bằng cách sử dụng các vòng quay phụ thành một mặt, xoay chúng lại với nhau bằng cách sử dụng tổ hợp $K_5$ hoặc $K_5^{-1}$ (tùy thuộc vào hướng quay mong muốn), sau đó đưa chúng trở lại vị trí bằng các vòng quay ngược với các vòng quay phụ.

Bây giờ chúng tôi sẽ giải thích cách sử dụng kết hợp $K_5$ và $K_5^{-1}$ để thực hiện bước 4.

Nếu sau khi hoàn thành giai đoạn 3 mà có các khối góc bị xoay sai thì do tính chất III nên có ít nhất hai khối như vậy.

Giả sử có nhiều hơn hai. Hãy lấy ba trong số chúng. Ít nhất hai trong số ba viên xúc xắc này yêu cầu quay cùng một hướng. Xoay cả ba hình khối theo hướng này, chúng ta sẽ giảm được số hình khối bị xoay sai. Vì vậy, chúng ta sẽ đi đến một tình huống trong đó việc xoay các hình khối là sai, hoặc chính xác là hai.
