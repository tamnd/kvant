---
id: 1986-2-arnold-evolyutsionnyie-protsessyi-i-obyiknovennyie-differentsialnyie-uravneniya-22320a02
issue: kvant_1986_2
year: 1986
number: "2"
title: Quá trình tiến hóa và phương trình vi phân thông thường
authors:
  - Арнольд В. И.
rubric: osnovnye-stati
page_first: 15
page_last: 22
page_labels: 13, 14, 15, 16, 17, 18, 20
tag: 0QWV
lang: vi
source: kvant_digital
extraction: vision
content_sha256: d4d6d3411ecb48e730c4d760e7886818658d30b1f6e71ecc90345df42c534292
prompt_sha256: draft-1
translated_from: content/ru/1986/02/articles/06_arnold-evolyutsionnyie-protsessyi-i-obyiknovennyie-differentsialnyie-uravneniya-22320a02.md
source_content_sha256: 54ad80249d699506ab76d4913feee74b8542eb7ba80fa65e6abc89b489286767
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 13⟧

Quá trình tiến hóa và phương trình vi phân thông thường

V. I. ARNOLD

“Phương trình rất phức tạp, nhưng bộ xử lý, với tính khiêm tốn đặc trưng của mình, đã gọi nó là bình thường.”

Từ một cuộc phỏng vấn trên báo với một nhà toán học.

Phương trình vi phân là một trong những công cụ chính của việc đặt tên tự nhiên trong toán học. Chúng được phát minh bởi Isaac Newton (1642-1727). Các vấn đề cơ bản dẫn đến phương trình vi phân đã xuất hiện trước Newton. Tuy nhiên, chỉ những thiên tài như chủ tịch Viện Hàn lâm Khoa học Pháp X. Heugens (1629-1695) và thầy giáo, nhà toán học và thần học của Newton, nhà truyền giáo của vua Anh I. Barrou (1630-1677) mới có thể giải được chúng. Sau Newoton, bất kỳ học sinh nào và thậm chí cả học sinh đều có thể giải được chúng.

Newton coi phát minh của mình quan trọng đến mức ông bảo vệ nó dưới dạng angram*), ý nghĩa của nó theo thuật ngữ hiện đại có thể được diễn đạt như sau: việc giải các phương trình vi phân là “hữu ích” (vì chúng thể hiện các quy luật tự nhiên).

Trong một angram khác, dài hơn, Newton cũng bảo vệ nghiệm lời giải của tất cả các phương trình, bao gồm cả phương trình vi phân mà ông đã phát minh ra.

Lý thuyết phương trình vi phân giải quyết các vấn đề tự nhiên

*) bassdae13eff7i3l9n4o4qrr4s9t12vx. Giải thích: Phương trình dữ liệu quot unque Fluxes định lượng liên quan đến thông lượng phát minh và ngược lại, nghĩa là “đối với một phương trình đã cho chứa một số hàm, hãy tìm đạo hàm và ngược lại”. Angram này có trong “bức thư thứ hai” nổi tiếng của Newton gửi thư ký của Hiệp hội Hoàng gia (Viện Hàn lâm Khoa học Anh) Oldenberg ngày 24 tháng 10 năm 1676. Bức thư được gửi cho Leibniz (1646-1716) và chứa đựng một thông điệp về việc phát minh ra phép phân tích toán học. Newton đã tiến hành trao đổi thư từ với Leibniz, người sống ở Đức, thông qua Oldenburg (người sau đó bị giam trong Tháp vì liên lạc với người nước ngoài).

Kiến thức về hình học bài toán về các đường cong được xác định bởi các trường vectơ (xem bên dưới) tương tự như cách phương pháp tọa độ Descartes biến các câu hỏi về phương trình đại số thành bài toán về đường thẳng và bề mặt.

Trạng thái quá trình

Để nghiên cứu bất kỳ quy trình nào, trước hết bạn phải có khả năng mô tả tập hợp tất cả các trạng thái có thể có của quy trình này. Hãy xem cách thực hiện điều này bằng các ví dụ.

1. Chuyển động của một điểm trên một đường thẳng. Kinh nghiệm cho thấy, để xác định chuyển động của một chất điểm dọc theo đường thẳng khi không có ngoại lực, chỉ cần đặt vận tốc và vị trí của nó trên đường thẳng tại thời điểm ban đầu là đủ. Do đó, tập hợp tất cả các trạng thái được vẽ bằng toán học với mặt phẳng tọa độ (s; v): mỗi điểm trên mặt phẳng này gắn với một điểm ma trận chuyển động với vận tốc v và chiếm một vị trí có tọa độ s, và ngược lại - mỗi trạng thái tương ứng với tính chất của một điểm trong mặt phẳng (hình 1).

2. Ma trận rung động. Trạng thái của ma trận phẳng còn được mô tả bằng hai tham số, ví dụ góc lệch θ so với phương thẳng đứng và vận tốc góc ω của ma trận (hình 2). Tập hợp các trạng thái của ma trận có lại là một mặt phẳng không? Không thực sự. Thực tế là khi góc θ thay đổi 2π thì ma trận sẽ trở về vị trí trước đó. Do đó, trạng thái được đặt ở đây là bề mặt hình trụ (hình 2).

3. Vị trí được trả về trên hai con đường. Thành phố A và B được nối với nhau bằng hai con đường không giao nhau, trên mỗi đường đều có đường quay lại; chúng tôi quan tâm đến vị trí tương đối của họ. Vị trí của đường trở về trên đường thứ nhất (hình 3) có thể được xác định bằng một số - phần khoảng cách từ A đến B (dọc theo đường thứ nhất) nằm giữa A và đường về; tương tự, lợi nhuận phải được xác định bằng cùng một phần dọc theo con đường thứ hai. Do đó, tập hợp các trạng thái mà chúng ta quan tâm được mô tả bằng các điểm (x; y) của bình phương đơn vị (0<x<1, 0<y<1).

Tập hợp trạng thái của một quá trình trong lý thuyết phương trình vi phân được gọi là không gian pha.

⟦folio 14⟧

Vì vậy, mỗi điểm của không gian pha (điểm pha) mô tả trạng thái của quá trình. Và chính dòng chảy của một quá trình cụ thể được mô tả bằng các đường thẳng trong không gian pha; những đường này được gọi là quỹ đạo pha.

Việc đưa ra không gian pha của một quá trình hình học hóa lý thuyết - các câu hỏi về tiến trình của quá trình chuyển thành câu hỏi về hành vi của quỹ đạo pha. Bắt hình học bài toán có thể khó khăn. Tuy nhiên, điều cũng xảy ra là chỉ cần đưa vào không gian pha là có thể giải được bài toán khó bài toán.

Bài toán (H. N. Konstantinov). Hai con đường không cắt nhau dẫn từ thành phố A đến thành phố B. Biết rằng hai ô tô đi dọc theo những con đường khác nhau từ A đến B và được nối với nhau bằng một sợi dây có chiều dài nhỏ hơn 2l, có thể đi từ A đến B mà không bị đứt dây. Hai xe lớn có bán kính l, tâm của chúng di chuyển dọc theo những con đường này về phía nhau, có thể vượt qua nhau mà không chạm vào nhau không?

Không gian pha ở đây là một đơn vị hình vuông. Vị trí ban đầu của ô tô (ở thành phố A) tương ứng với góc dưới bên trái của hình vuông và chuyển động của ô tô từ A đến B được mô tả bằng một đường cong dẫn đến góc đối diện của hình vuông (phía trên bên trái). Nhưng hai đường cong bất kỳ trong một hình vuông nối các cặp đỉnh đối diện khác nhau sẽ cắt nhau. Vì vậy, cho dù xe di chuyển như thế nào, sẽ đến lúc cặp đôi này sẽ thay thế hoàn toàn những quả mâm xôi mà cặp đôi đó đã ở vào một thời điểm nào đó. Lúc này khoảng cách giữa tâm các xe sẽ nhỏ hơn 2l. Vì vậy, không thể bắt kịp được.

Cuộc thảo luận về bài toán không liên quan đến các phương trình vi phân, nhưng lý do gần giống với những gì chúng ta sẽ làm sau này: mô tả diễn biến của một quá trình như một đường tiếp cận không gian pha thường cực kỳ hữu ích.

Sơ đồ chung của lý thuyết phương trình vi phân như sau. Vì trạng thái ban đầu của các quá trình mà chúng ta đang xem xét xác định hướng đi trong tương lai của chúng nên nó cũng xác định tốc độ thay đổi trạng thái, tức là tốc độ chuyển động của điểm pha. Theo Newoton, sự phụ thuộc của tốc độ chuyển động của một điểm pha vào vị trí của nó (hoặc quy luật địa phương về sự tiến hóa của quá trình) được thể hiện một cách chính xác bằng một phương trình vi phân. Về mặt hình học, phương trình này mô tả trường vận tốc pha vectơ (xem ví dụ hình 5.11 bên dưới). Lý thuyết về phương trình vi phân nên mô tả quá trình sử dụng trường vectơ, nghĩa là tìm quỹ đạo chuyển động của các điểm pha, trả lời các câu hỏi về đặc điểm chuyển động của chúng (ví dụ: các câu hỏi sau: quỹ đạo có bị giới hạn không? Chúng có quay trở lại điểm xuất phát không?). Ý nghĩa của những câu hỏi này đối với việc nghiên cứu quá trình là rất thuận tiện.

Phương trình ma trận toán học

Theo các định luật cơ học, gia tốc góc của ma trận tỷ lệ thuận với mômen trọng trường (hình 4)

Hình 1. Chuyển động theo đường thẳng. Hình 2. Dao động ma trận.

Hình 3. Bài toán hai xe đi trên hai con đường.

⟦folio 15⟧

$$I\ddot{\theta} = -mgl \sin \theta,$$

trong đó $m$ là khối lượng, $l$ là chiều dài, $\theta$ là góc lệch; dấu chấm trên cùng nghĩa là đạo hàm theo thời gian $t$ (ở đây và bên dưới), hai dấu chấm nghĩa là đạo hàm bậc hai*), $I = ml^2$ là mô men quán tính. Dấu trừ trong phương trình được giải thích là do mô men của bộ đẩy làm giảm độ lệch. Cái sau chúng ta nhận được $\ddot{\theta} = -k \sin \theta$, trong đó $k = g/l$. Hệ số $k$ có thể được tính bằng 1 bằng cách chọn thang thời gian phù hợp (chia $t$ cho $\sqrt{k}$). Khi đó phương trình của ma trận toán học sẽ có dạng

$$\ddot{\theta} = -\sin \theta.$$

(1)

Không gian pha của ma trận là một hình trụ ($\theta; \omega$), trong đó $\omega = \dot{\theta}$ là vận tốc góc. Chúng ta có thể viết phương trình (1) dưới dạng hệ thống

$$\dot{\theta} = \omega, \dot{\omega} = -\sin \theta,$$

(2)

chỉ bao gồm đạo hàm bậc nhất của ẩn số $\theta$ và $\omega$. Hệ thống này thể hiện quy luật tiến hóa cục bộ của trạng thái ma trận: tốc độ thay đổi được thể hiện thông qua chính trạng thái đó.

Hóa ra việc giải phương trình (1) (hoặc hệ (2)) không dễ dàng như vậy. Nếu chúng ta giới hạn bản thân ở những góc nhỏ $\theta$ (dao động nhỏ), thì $\sin \theta \approx \theta$. Do đó, đối với $\theta$ nhỏ, người ta sử dụng cùng với (1) phương trình gần đúng $\ddot{\theta} = -\theta$. Nó được gọi là phương trình dao động nhỏ của ma trận. Bạn biết lời giải $\theta = C \sin (t + \varphi)$ của nó từ khóa học vật lý: ở các góc lệch nhỏ, một ma trận toán học phẳng tạo ra các dao động tuần hoàn điều hòa (hình sin). Câu hỏi lựa chọn này thay đổi bao nhiêu khi chuyển sang phương trình ma trận thực (1) đòi hỏi phải có nghiên cứu đặc biệt.

Chúng ta hãy sử dụng không gian pha của hệ (2)—hình trụ ($\theta; \omega$). Tại mỗi điểm của không gian pha, chúng ta sẽ xây dựng một vectơ vận tốc pha, tức là một vectơ có tọa độ ($\dot{\theta}; \dot{\omega}$)=(ω; —sin $\theta$) - tương đương hình học của định luật tự nhiên (1). Bản đồ kết quả—trường vận tốc pha—được mô tả trong hình 5 (để rõ ràng, chúng tôi cắt hình trụ dọc theo ma trận và quay nó lại).

Trong hình ảnh này bạn có thể thấy như sau. Tại hai điểm vận tốc pha bằng không. Điểm $A$ obtue là vị trí cân bằng dưới (ổn định), điểm $B$ là vị trí cân bằng trên (không ổn định). Ở các giá trị nhỏ $\theta$, $\dot{\theta}$, rõ ràng là các điểm của không gian pha di chuyển dọc theo các đường cong khép kín, chúng ta hãy đặt chúng trên một vòng tròn (dao động nhỏ), với sự gia tăng $\theta$ các đường cong khép kín tăng dần và kéo dài thành một dạng giống như hình elip (dao động có biên độ lớn)*). Một vai trò đặc biệt được thể hiện bởi các quỹ đạo được tô màu đỏ

$$\lim_{x \to 0} \frac{\sin tg x - tg \sin x}{x - 0} = \arcsin \arctg x - \arctg \arcsin x$$

ngay lập tức từ các thông điệp hình học (hiếm có nhà toán học hiện đại nào tính được giới hạn này trong một giờ).

⟦folio 16⟧

mũi tên: ma trận đã rơi từ vị trí cân bằng không ổn định, thực hiện một vòng quay hoàn toàn và lại đứng yên ở vị trí phía trên. Quỹ đạo này tách các dao động khỏi các chuyển động quay (không đồng đều) mà ma trận tạo ra nếu tốc độ của nó ở $\theta = 0$ vượt quá số 2 trong các đơn vị không thứ nguyên của chúng ta.

Cá diếc (sinh sản bình thường)

Cá diếc được nuôi ở mỏ lớn. Cá diếc không can thiệp lẫn nhau khi đã có đủ. Số lượng cá diếc $x(t)$ sẽ thay đổi như thế nào theo thời gian $t$? Tốc độ tăng trưởng của cá diếc trong những điều kiện này tỷ lệ thuận với số lượng cá thể; vì vậy chúng ta có thể viết

$$\dot{x} = kx, \quad k > 0.$$

(3)

Phương trình này được gọi là phương trình vi phân của tái tạo bình thường hoặc tiếng Malta*). (Hãy nhớ rằng $\dot{x}$ biểu thị đạo hàm theo thời gian.)

Định lý tồn tại. Bất kỳ hàm nào có dạng $x = Ce^{kt}$, trong đó $C$ là hằng số, đều là nghiệm của phương trình (3).

Chứng minh: Thay vào phương trình.

Từ định lý đã được chứng minh suy ra

Định lý duy nhất. Phương trình (3) không có lời giải nào khác.

Bằng chứng. Bất kỳ hàm nào cũng có thể được viết là $x(t) = C(t)e^{kt}$. Sau đó $\dot{x} = Ce^{kt} + kx$. Do đó, để đẳng thức $\dot{x} = kx$ được giữ vững, điều cần và đủ là $C = 0$, tức là $C$ phải là một hằng số.

Đồ thị của phương trình lời giải được gọi là đường cong tích phân. Những đường cong này nằm trong không-thời gian, tức là trên một mặt phẳng có tọa độ $(t; x)$. Để vẽ các đường cong tích phân, một khoảng trống rất hữu ích, được gọi là trường phương trình có hướng và bao gồm các đoạn nhỏ được áp dụng tại mỗi điểm trong không-thời gian một góc với trục thời gian, tiếp tuyến của nó bằng vế phải của phương trình.

*) Trong một số trường hợp, tốc độ sinh sản không tỷ lệ thuận với số lượng cá thể mà tỷ lệ thuận với số lượng cặp. Sự sinh sản đô thị dị thường như vậy thường chậm hơn ở mật độ dân số thấp (ví dụ, cá voi của một số loài gặp khó khăn trong việc tìm bạn tình). Ví dụ: đối với $x$ lớn, việc tái tạo ở tỷ lệ tỷ lệ với $x^2$ dẫn đến một “vụ nổ” trong thời gian hữu hạn: đồ thị $x(t)$ có ​​tiệm cận đứng (tại sao?). Tình huống này được hiện thực hóa trong phương trình động học hóa học, trong đó tốc độ phản ứng tỷ lệ thuận với lượng từng chất phản ứng.

Hình 6. Trường của phương trình tái tạo chuẩn có hướng $\dot{x} = kx$ và lời giải, đi qua điểm bắt đầu $(t_0, x_0)$.

($kx$ đối với phương trình (3), xem hình 6). Đường cong khoảng tại mỗi điểm tiếp xúc với đoạn tương ứng và ngược lại, đường cong tiếp tuyến với các đoạn của chúng ta sẽ là đồ thị lời giải (đây là ý nghĩa hình học của phương trình vi phân).

Chúng ta vừa chứng minh rằng qua mỗi điểm trong không-thời gian có đúng một đường cong tích phân $x = Ce^{kt}$ của phương trình (3). Công thức này thể hiện quy luật sinh sản bình thường: để cân bằng số lượng cá diếc luôn phải mất một khoảng thời gian như nhau, bất kể số lượng của chúng là bao nhiêu. Chu kỳ của phương trình dân số Trái đất hiện nay là khoảng 40 năm. Do đó, số người đang sống sẽ lớn hơn số người đã từng chết nếu tốc độ tăng trưởng không thay đổi. Thời gian tồn tại của con người khi đó là khoảng 2000 năm; do đó, tốc độ tăng dân số sẽ nhỏ hơn 1/v(x). Dọc theo đường cong tích phân (nếu nó không song song với trục $t$), $t$ có ​​thể được biểu thị dưới dạng hàm của $x$. Biểu thị đạo hàm đối với $x$ bằng shrikh, chúng ta thu được $t' = 1/v(x)$. Điều này có nghĩa là $t$ là nguyên hàm của

⟦folio 17⟧

Hình 7. Trường có hướng và đồ thị lời giải của phương trình logic $x=(1-x)x$. Lời giải $x=1$ và $x=0$ sẽ là nguồn tích cực của trạng thái cân bằng không ổn định.

1/v. Điều này cho phép bạn biểu thị $t$ theo $x$ và sau đó $x$ theo $t$. (Tất nhiên, không-thời gian trực tiếp, trong đó $v(x)=0$, bị loại bỏ để không chia cho 0.) Với $v(x)=kx$, chúng ta nhận được $t'=1/kx$, $kt=\ln|x|+const$, $x=Ce^{kl}$.

2. Định lý duy nhất, phát biểu rằng các đường cong khoảng không trùng nhau và không cắt nhau, là một thực tế cực kỳ đáng ngạc nhiên mâu thuẫn với bằng chứng trực quan và kinh nghiệm vật lý. Ví dụ: các đường cong khoảng của phương trình (3) cho $k=1$ đi qua các điểm (0; 0) và (0; 1) cho $t=-5$ không thể phân biệt được bằng mắt và đối với $t=-30$ các nguyên tử giữa chúng không giảm. Tuy nhiên, các nhà toán học coi chúng không giao nhau ngay cả đối với $t=-10^{10}$.

3. Trong các tài liệu vật lý gần đây, việc Newot rút ra các định luật Kepler từ định luật lý thuyết phổ quát (được Hooke chỉ ra trong một lá thư đề ngày 6 tháng 1 năm 1680) của Newot năm 1684 đã bị nghi ngờ: kết luận này không sử dụng định lý duy nhất cho phương trình chuyển động, điều mà Newot không chứng minh được. Tuy nhiên, trên thực tế, điều duy nhất xuất phát từ sự tồn tại của lời giải, sự phụ thuộc của nó vào điểm ban đầu được biểu thị bằng một hàm khả vi. Chứng minh tính duy nhất trong trường hợp này tương tự như chứng minh ở trên đối với phương trình phân tập, nhưng Newoton đưa ra điều kiện cần thiết lời giải. Trong một bức thư gửi Halley về cuộc thảo luận của ông với Hooke, Newton mô tả sự khác biệt giữa cách tiếp cận của các nhà toán học (Newton) và các nhà vật lý (Hooke) đối với khoa học tự nhiên, những điều vẫn còn phù hợp cho đến ngày nay: “Các nhà toán học, những người khám phá và thiết lập mọi thứ và thực hiện mọi công việc, phải bằng lòng với vai trò của những người tính toán khô khan và những người lao động tầm thường; người còn lại, những người chỉ nắm bắt mọi thứ và khẳng định mọi thứ, chiếm đoạt cho mình những phát minh của cả những người theo ông và những người đi trước ông.” Nhiệm vụ của Hooke với tư cách là người phụ trách Hiệp hội Hoàng gia bao gồm việc chứng minh 2 hoặc 3 định luật tự nhiên mới bằng cách sử dụng các thí nghiệm trên việc trồng trọt hàng ngày của xã hội, công việc mà ông đã làm trong 40 năm. Những định luật có thể chứng minh được có thể được người khác khám phá ra, nhưng Hooke đếm tới 500 định luật chỉ được anh ta khám phá ra. Đương nhiên, anh không có thời gian để biện minh mọi thứ bằng toán học.

Tuy nhiên, chúng ta hãy quay lại với hình phạt của mình. Sau một thời gian sẽ có nhiều caramen đến mức không đủ thức ăn và trở nên chật chội; tăng trưởng hơn nữa sẽ không còn thỏa mãn phương trình (3).

Cá diếc thiếu thức ăn (đường cong logistic)

Nếu sản phẩm caramen của chúng tôi không phải là VELik hoặc nếu số lượng carami trong một sản phẩm lớn tăng lên rất nhiều thì sự cạnh tranh về thực phẩm sẽ dẫn đến tốc độ tăng trưởng giảm. Giả định đơn giản nhất là hệ số $k$ phụ thuộc tuyến tính vào số carami, tức là $k=a-bx$ (đối với $x$ không quá lớn, bất kỳ hàm trơn nào cũng có thể được xấp xỉ bằng một hàm tuyến tính). Do đó, chúng tôi đi đến phương trình tái sản xuất có tính đến sự cạnh tranh: $\dot{x}=(a-bx)x$. Các hệ số $a$ và $b$ có thể được chuyển đổi thành đơn vị bằng cách chọn thang đo $t$ và $x$. Chúng ta nhận được cái gọi là phương trình logistic

$$\dot{x}=(1-x)x.$$ (4)

Trường định hướng của phương trình (4) trong không-thời gian được hiển thị trên hình 7 và bên cạnh nó, trên hình 7, b, đồ thị lời giải được hiển thị. Các đường cong khoảng hình chữ S trong dải $0<x<1$ được gọi là đường cong logistic. Chúng ta thấy rằng 1) quá trình có hai vị trí cân bằng: $x=0$ và $x=1$;
2) giữa các đường thẳng $x=0$ và $x=1$ trường hướng lên từ 0 đến 1 và tại $x>1$ - hướng xuống 1.

Do đó, vị trí cân bằng 0 không ổn định (một khi quần thể karama xuất hiện bắt đầu lan rộng) và vị trí cân bằng 1 là ổn định (dân số phân tán ít hơn, dân số giảm nhiều hơn). Bất kể số lượng caramies ban đầu là $x>0$, theo thời gian, quá trình sẽ đạt đến trạng thái cân bằng ổn định $x=1$. Do đó, mỗi ao (các điều kiện khác không đổi) có số lượng caramen “chính xác” riêng và bất kỳ quần thể caramen nào cũng sẽ có xu hướng đạt đến con số này.

⟦folio 18⟧

Câu cá diếc

Cho đến nay, chúng ta vẫn coi một quần thể cá diếc tự do phát triển theo quy luật nội tại của nó. Bây giờ hãy giả sử rằng chúng ta bắt được cá diếc (giả sử ao của trang trại tập thể thường xuyên cung cấp cá sống cho cửa hàng cá địa phương). Giả sử tốc độ bắt giữ là không đổi. Chúng tôi đi đến phương trình bẫy vi sai
$$\dot{x} = (1-x)x-c.$$ (5)

Giá trị $c$ đặc trưng cho tỷ lệ đánh bắt cho phép và được gọi là kvata.

hình 8 hiển thị ba loại biểu đồ lời giải của phương trình (5) cho ba loại $c$ khác nhau.

Ta thấy (hình 8, a) nếu tốc độ bắt không quá cao ($0<c<1/4$) thì có hai vị trí cân bằng ($x=A$ và $x=B$ trên hình). Vị trí cân bằng thấp hơn $A$ không ổn định. Nếu vì lý do nào đó (đánh bắt quá mức, bệnh tật) tại một thời điểm nào đó mà quy mô quần thể $x$ dưới $A$, thì trong tương lai toàn bộ quần thể sẽ biến mất trong một thời gian hữu hạn. Vị trí cân bằng trên $B$ ổn định là chế độ Đứng yên mà quần thể đạt tới khi đánh bắt liên tục $c$. Đương nhiên, quần thể cân bằng của ao nơi đánh bắt cá sẽ nhỏ hơn trong ao không đánh bắt cá.

Nếu $c > 1/4$ (hình 8, b), thì không có trạng thái cân bằng và tất cả cá diếc sẽ bị bắt trong một thời gian hữu hạn (một kế hoạch thổi phồng việc bán cá sống cho một cửa hàng sẽ dẫn đến cái chết của nó; một ví dụ lịch sử về loại này là việc tiêu diệt con bò của Steller).

Tại $c = 1/4$ (hình 8, b) có một trạng thái cân bằng không ổn định $(A=B=1/2)$. Việc đánh bắt với tốc độ như vậy với quần thể ban đầu đủ lớn là có thể về mặt toán học trong một thời gian dài tùy ý, tuy nhiên, một lượng nhỏ tùy ý kích thước của quần thể cân bằng đã được thiết lập (xem điểm $F$) sẽ dẫn đến việc đánh bắt hoàn toàn cá diếc trong một thời gian hữu hạn (kế hoạch đánh bắt $c = 1/4$ cho cửa hàng “Cá” cũng không phù hợp).

Do đó, mặc dù bất kỳ hạn ngạch nào lên tới mức tối đa ($c \leq 1/4$) đều có thể chấp nhận được về mặt lý thuyết, nhưng hạn ngạch tối đa $c = 1/4$ sẽ dẫn đến sự mất ổn định và không thể chấp nhận được*. Hơn nữa, kv gần $1/4$ trên thực tế là không thể chấp nhận được, vì ngưỡng nguy hiểm $A$ của chúng gần với trạng thái ổn định $B$ (những sai lệch ngẫu nhiên nhỏ sẽ đầu độc quần thể dưới ngưỡng $A$, sau đó quần thể sẽ chết).

Hóa ra vẫn có thể tổ chức đánh bắt theo cách sao cho luôn đạt được sản lượng đánh bắt ở tỷ lệ $c = 1/4$. Hãy xem nó được thực hiện như thế nào.

Giới thiệu phản hồi

Chúng tôi cùng nhau ấn định tỷ lệ bắt giữ tuyệt đối so với, nghĩa là chúng tôi ấn định tỷ lệ dân số hiện có của người bị bắt trên một đơn vị thời gian:

$$\dot{x} = (1-x)x - px.$$ (6)

hình 9 hiển thị không-thời gian cho phương trình (6) (tại $p < 1$) và đồ thị của một số lời giải. Có thể thấy, vị trí cân bằng thấp hơn, không ổn định lúc này là điểm $x = 0$, vị trí cân bằng thứ hai là $B$

*) Một kết luận quan trọng đối với kinh tế học từ kinh tế toán học: mong muốn tối đa hóa lợi nhuận, thu nhập hoặc số lượng sản xuất thông qua/đến sự xuất hiện của sự mất ổn định trong hệ thống.

Hình 8. Lời giải phương trình bẫy $\dot{x} = (1-x)x - c$ cho các giá trị khác nhau của hạn ngạch bẫy $c$. Tại $c < 1/4$ bất kỳ quần thể nào cũng có xu hướng đạt đến trạng thái cân bằng ổn định $x = A$, tại $c = 1/4$ vị trí cân bằng không ổn định, tại $c > 1/4$ mọi quần thể đều chết đi.

⟦folio 20⟧

Việc nhân giống cá diếc sẽ dẫn đến việc theo thời gian tôi đang tìm kiếm cá diếc để nhân lên.

Nhưng chúng ta sẽ quay lại điểm A chứ? Nói cách khác, liệu quá trình dao động có được lặp lại một cách tuần hoàn không? Đáp số đối với câu hỏi này phụ thuộc vào việc lựa chọn điểm bắt đầu A (cũng như giá trị của các tham số hệ thống). Chúng tôi sẽ quay lại vấn đề này ở một trong những số tiếp theo của tạp chí.

Bài toán
1. Tìm phương trình của đường cong logistic.
2. Các đường cong tích phân của phương trình (5) và (6) có phải là đường cong logistic khoảng cách không?
3. Chứng minh rằng các đường cong tích phân của phương trình (5) và (6), khoảng cách không dải giữa A và B, có các tiệm cận đứng.

Thành phố dành cho điện tử

(Xem phần đầu ở trang 6)

Sau khi hệ thống dây điện và các điểm tiếp xúc đã được hình thành, LSI đã sẵn sàng. Mỗi người trong số họ đều được kiểm tra cẩn thận về hiệu suất ngay trên tấm. Một máy điều khiển, được điều khiển bởi máy tính, hạ thấp các điểm tiếp xúc kim chính xác lên LSI và gửi một loạt xung dòng điện thử nghiệm vào mạch (như người ta nói, “đặt biệt danh” cho mạch). Nếu mạch chứa một triệu phần tử thì số xung kiểm tra lên tới mười nghìn. Đáp số của mạch kiểm tra được máy tính chấp nhận. Nếu LSI không phản hồi như bình thường hoặc im lặng, máy điều khiển sẽ đặt nó bằng một giọt sơn từ tính. Sau khi tấm wafer silicon được chia thành hàng trăm con chip hoàn thiện (việc này được thực hiện bằng máy cắt kim cương hoặc tia laser), nam châm điện sẽ chọn ra những mạch ít bị loại bỏ nhất.

Và bây giờ tất cả những gì còn lại là đặt các LSI làm sẵn, có thể sử dụng được vào vỏ. Một hộp nhỏ làm bằng gốm, kim loại hoặc nhựa sẽ bảo vệ vi mạch khỏi bị hư hỏng bên ngoài, tiếp xúc với khí quyển, điện trường ngẫu nhiên và đảm bảo làm mát vi mạch đang hoạt động. Vì vậy, mặc dù bên ngoài
Trên thực tế, thiết kế thân tàu đã được tính toán và tính toán kỹ lưỡng. Trong một số loại vi mạch, chi phí cho phần vỏ và công việc “đóng gói” đạt tới mức thứ ba trên tất cả các mặt của LSI.

Bây giờ quá trình sản xuất chip đã kết thúc, việc tương tự với quy hoạch đô thị cũng kết thúc. Không có thành phố xây dựng mới nào phải chịu các cuộc kiểm tra khả năng chịu nhiệt độ cực cao và sương giá -60 ° C, trước trận động đất mạnh 9 độ richter, trước tác động của việc rơi từ độ cao ba mét; thêm thử nghiệm rò rỉ trong sương mù biển, để duy trì các điều kiện hoạt động tối đa, v.v. Nếu LSI có thể chịu được tất cả những điều này, nó có thể được chuyển đến người tiêu dùng.

* * *

Vi điện tử là sự kết hợp của nhiều ngành khoa học: khoa học vật liệu, cơ học chính xác, quang học lượng tử, điện vật lý, quang hóa, điều khiển học,... Không thể nói cái gì ở đây là quan trọng, cái gì là thứ yếu. Công nghệ sản xuất vi mạch tốt hơn những gì khoa học công nghệ hiện nay. Chúng tôi chỉ xem xét các yếu tố kỹ thuật điển hình và tương đối đơn giản nhất để hiểu. Nhưng cả chúng và các lựa chọn kỹ thuật khác cũng như triển vọng gần giống về mặt kỹ thuật đối với LSI luôn đáng tin cậy vì thực tế là đỉnh cao của công nghệ vi điện tử vẫn còn rất xa.
