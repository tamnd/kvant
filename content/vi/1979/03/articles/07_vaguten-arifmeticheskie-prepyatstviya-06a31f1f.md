---
id: 1979-3-vaguten-arifmeticheskie-prepyatstviya-06a31f1f
issue: kvant_1979_3
year: 1979
number: "3"
title: Trở ngại số học
authors:
  - Вагутен Н.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 24
page_last: 32
page_labels: 22, 23, 24, 25, 26, 27, 29, 30
tag: 9DYL
lang: vi
source: kvant_digital
extraction: vision
content_sha256: bd734741d99de61c18170abb58d03b64ceb4a9080f7d6bd121dbca9e6cd1a0e1
prompt_sha256: draft-1
translated_from: content/ru/1979/03/articles/07_vaguten-arifmeticheskie-prepyatstviya-06a31f1f.md
source_content_sha256: d7398fb1284f2729dbbe77303c84d1239c729752211260ee0c5cc29d3dc8bedb
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 22⟧

Trở ngại số học

Trong nhiều lý thuyết toán học và các bài toán ứng dụng, cũng như trong các trò chơi và câu đố toán học, các câu hỏi thuộc loại này nảy sinh: liệu có thể di chuyển từ vị trí này sang vị trí khác bằng cách sử dụng một số thao tác (di chuyển) “hợp lệ” không? Làm cách nào để tìm số nguyên cần di chuyển nếu nó tồn tại hoặc chứng minh rằng việc chuyển đổi là không thể? Trong bài viết này, chúng ta sẽ xem xét một số bài toán thuộc loại này. Chúng cũng được thống nhất bởi trạng thái bên ngoài của chúng: trong mỗi chúng đều xuất hiện các số nguyên và “các trở ngại” đối với các quá trình chuyển đổi, như một quy luật, có tính chất số học.

Ngay cả học sinh tiểu học cũng có sẵn các ví dụ để bắt đầu cuộc thảo luận về từng làn sóng bài toán. Các bài tập về chòm sao và cách chứng minh các kết quả tổng quát đòi hỏi người đọc phải suy nghĩ nghiêm túc. Bài viết kết thúc với những bài toán khó Olympic, bài cuối cùng được áp dụng cho lý thuyết không sơ cấp, đang phát triển nhanh chóng về các nhóm khớp.

1. Vấn đề về con ngựa

Bài 1. Cho các số tự nhiên m và n. Trên một trong các sân của một điểm cờ vô hạn có một hình di chuyển “với chữ Γ” trên m trường theo một trong các hướng và trên n theo hướng vuông góc; gọi nó là {m; n}-kone. Con ngựa này có thể đi đến cánh đồng nào?

Một hiệp sĩ cờ vua bình thường ({1; 2}-mã) có thể đi từ bất kỳ ô O ban đầu nào đến bất kỳ ô nào khác: trong ba nước đi, nó có thể đi đến một ô liền kề với O và với các bước cơ bản, tất nhiên, người ta có thể đến bất cứ đâu.

Nhưng {1; 3}-quân mã, một số nước đi được hiển thị trong Hình 1, không thể tiến tới hình vuông liền kề (theo chiều ngang) với hình vuông ban đầu bằng bất kỳ cách nào. Trên bàn cờ, rất dễ giải thích điều gì ngăn cản sự chuyển đổi như vậy: {1; 3}-Mã luôn di chuyển trên các ô cùng màu. Mặt khác, không khó để chứng minh rằng {1; Một quân mã 3} có thể bỏ qua tất cả các ô vuông cùng màu: trong ba nước đi, nó có thể hợp nhất theo đường chéo vào một hình vuông liền kề cùng màu (Hình 1) và với các bước cơ bản, nó có thể dễ dàng bỏ qua tất cả các ô vuông một điểm.

Hãy thử giải bài toán 1 cho các số a) 2 và 5; b) 10 và 25; d) 19 và 79.

Hóa ra là {m; Mã n} có thể xuất hiện trong mọi trường hợp trong đó m và n có số chẵn lẻ khác nhau và ước số chung nhất của chúng là 1.

Phần hoàn chỉnh từ đáp số đến bài toán 1 được đưa ra ở cuối đoạn 3 (Bài tập 10). Bây giờ chúng ta sẽ giải quyết một vấn đề đơn giản hơn. Kết quả mà chúng tôi nhận được rất hữu ích cho cả bài toán về hiệp sĩ và cho toán học phía máy chủ hơn bài toán.

Cơm. 1. {1; 3}-mã có thể đến ô liền kề (theo đường chéo) cùng màu; Với những bước như vậy, anh ta có thể bỏ qua tất cả các trường có trọng số đơn.

⟦folio 23⟧

2. Đại diện GCD
Bài 2. Cho các số tự nhiên a và b. Trong một nước đi, phép cắt là cộng một trong các số a, b với một số nguyên nào đó hoặc trừ đi một trong các số này khỏi số đó. Có thể lấy số c từ số 0 một cách tối đa được không?

Trong bài toán này có thể có các “vị trí” - đây là tập Z của tất cả các điểm nguyên trên trục số.

Hãy bắt đầu với một ví dụ cụ thể. Giả sử rằng người mua và nhân viên thu ngân chỉ có các tờ 10 và 25 rúp và (chúng không tồn tại trong các bài toán!) với số lượng không giới hạn. Rõ ràng là người mua có thể đặt c rúp cho người thu ngân khi và chỉ khi c là bội số của 5.

Một ví dụ khác. Cho phép di chuyển ±19 và ±79 trên tập Z. Với những bước di chuyển này, bạn có thể nhận được bất kỳ số nguyên nào: sự kết hợp của chúng cho phép bạn di chuyển đến khoảng cách 3, sau đó đến khoảng cách 1 (Hình 2, a).

Một ví dụ phức tạp hơn: a=819, b=357. Trong trường hợp này, sử dụng kỹ thuật tương tự, có thể tìm ra khoảng cách ngắn nhất - ở mức 21 (Hình 3, a). Do đó, ở đây có thể thực hiện chuyển đổi sang bất kỳ khoảng cách nào là bội số của 21. Mặt khác, cả a và b đều chia hết cho 21 nên không thể thực hiện chuyển đổi nào khác.

Lưu ý rằng 21 là ước số chung nhất của 819 và 357 (hãy xem phần này!).

Sự khác biệt 1. a) Chứng minh rằng nếu người mua và nhân viên thu ngân có (với số lượng không giới hạn) ba rúp và năm xu, thì người mua có thể lập kế hoạch với số lượng rúp bất kỳ.

6) Có thể đi từ 0 đến 1000 nếu a=123, b=456 không? nếu a=589, b=1984?

b) Những chuyển đổi nào có thể xảy ra tại a=18, b=81?

Bây giờ hãy tạo đáp số đến bài toán 2 ở dạng tổng quát. Hãy để nhiều nhất

⟦folio 24⟧

Ước chung lớn nhất (GCD) của các số a và b bằng d. Khi đó việc chuyển từ 0 sang c có thể xảy ra trong cả hai trường hợp, khi số c chia hết cho d. Hãy cố gắng chứng minh điều đó.

Chúng ta sẽ thu được kết quả này ở một dạng hơi khác trong phần tiếp theo.

Có một người phụ nữ
2. Chứng minh rằng đáp số đến bài toán 2 không thay đổi nếu số a chỉ có thể cộng, b chỉ có thể trừ.
3. Có thể trả lời a) 150 g trên cân cốc khi sử dụng các quả cân 36 g và 60 g (các quả cân này có số lượng không giới hạn và có thể đặt trên cả hai cốc cân); b) 132 g?

3. Thuật toán Euclid
Trong bài toán tiếp theo, các vị trí sẽ là các cặp số nguyên.

Bài toán 3. Ba nguyên tử được in trên thẻ với các cặp số nguyên. Mỗi nguyên tử, sau khi đọc một thẻ nhất định, sẽ được cấp một thẻ mới: nguyên tử đầu tiên, sau khi đọc một thẻ có cặp (x; y), được cấp một thẻ (x-y; y), nguyên tử thứ hai được cấp một thẻ (x+y; y), nguyên tử thứ ba được cấp một thẻ (y; x).

Giả sử ban đầu có một củ khoai tây có một cặp số (1; 2). Có thể sử dụng các nguyên tử theo thứ tự bất kỳ để lấy được một lá bài (19; 79) không? (819; 357)?

Bạn có thể nhận được những lá bài chung nào nếu ban đầu bạn có một củ khoai tây có một cặp số (a; b)?

Cơm. 4. Mỗi “cuộc hành quân” ​​của cầu thang này là một bước của thuật toán Euclide.

Hãy biểu thị các hoạt động mà máy tự động thực hiện lần lượt là L, R và S. Hãy bắt đầu lại với các ví dụ bằng số.

Một cặp (19; 79) có thể được lấy từ cặp (1; 2) bằng cách sử dụng các phép toán L, R, S. Để thực hiện chuyển đổi cần thiết, sẽ thuận tiện hơn là không đi lên từ (1; 2) đến (19; 79), mà đi xuống theo hướng ngược lại (Hình 4).

Bằng cách viết số nguyên kết quả theo thứ tự ngược lại (và tất nhiên, thay thế L và R), chúng ta nhận được “sự tăng” từ (1; 2) lên (19; 79).

Trong Hình 4, chúng tôi tiếp tục “giảm dần” từ (19; 79) sang (1; 2) thành cặp (1; 0); một bản ghi viết tắt của “đi xuống” này được hiển thị trong Hình 2, trong (Lᵉ có nghĩa là thao tác L được thực hiện k lần liên tiếp). Trên thực tế, chúng tôi đã thực hiện quá trình giảm dần tương tự theo ví dụ đối với bài toán trước đó (Hình 2, a).

Phần gốc bắt đầu bằng cặp (819; 357) được viết tắt trong Hình 3; viết nó ra một cách chi tiết. Ở đây cặp (1; 2) (hoặc 1; 0) không hoạt động. Và không có gì ngạc nhiên khi điều này có một lợi thế: tất cả các số thu được đều chia hết cho 21. Bất kể chúng ta áp dụng các phép toán L, R, S theo thứ tự nào, chúng ta có thể loại bỏ lợi thế về tính không thể tiếp cận này, vì, rất dễ chứng minh, các phép tính này bảo toàn các ước chung của các số trên thẻ: GCD (x-y, x) = GCD (x+y, y) = GCD (x, y). Vì vậy, đáp số từ cặp = (819; 357) sang cặp (1; 2) hoặc ngược lại là không thể.

Razzhenne 4. Có thể sử dụng các phép toán L, R, S để di chuyển a) từ cặp (1; 10) sang cặp (5; 25) không? 6) từ (18; 81) đến (36; 63)? từ (589; 1984) đến (31; 1953)?

Bây giờ chúng ta có thể tạo đáp số cho câu hỏi chung cuối cùng bài toán 3: cặp (a; b) có thể được dịch thành cặp (p; q) trong cả hai trường hợp, khi gcd (a; b) = gcd (p; q). Điều kiện này là cần thiết bởi vì, như chúng tôi đã nói, hoạt động của chúng tôi bảo toàn gcd. Nhưng cũng đủ: nếu gcd(a,b) = gcd(p,q) = d thì mỗi cặp phép toán L,R,S này có thể rút gọn thành một cặp (d; 0); bằng cách bắt đầu từ (a; b) đến (d; 0) rồi tăng dần từ (d; 0) lên (p; q), chúng ta nhận được một số nguyên từ (a; b) đến (p; q).

⟦folio 25⟧

Cơm. 5. Sử dụng các thao tác L, R, S bạn có thể đổi dấu một số trên thẻ.

Hãy để chúng tôi chỉ ra lý do tại sao chúng tôi có thể chuyển từ bất kỳ cặp $(a; b)$ nào sang cặp $(d; 0)$. Lưu ý rằng nếu một trong các phần tử của cặp là âm thì nó có thể dễ dàng chuyển thành dương (Hình 5). Và cặp $(a; b)$ với tự nhiên và $b$ có thể được rút gọn thành cặp $(d; 0)$ theo cách tương tự mà chúng ta đã sử dụng trong các ví dụ: ở mỗi bước (ngoại trừ hoán vị đối xứng), phần tử lớn hơn của cặp sẽ bị giảm cho đến khi chúng ta đi đến bước cuối cùng $\rightarrow (d; d) \rightarrow (0; d) \rightarrow (d; 0)$.

Giải bài toán 3, chúng ta có một cách thuận tiện để tìm ước chung nhất của hai số: từ cặp $(a; b)$, trong đó $a > b > 0$, chúng ta đi đến cặp $(b; r)$, trong đó $r$ là phần còn lại của phép chia $a$ cho $b$ và lặp lại thao tác này cho đến khi chúng ta nhận được một cặp $(d; 0)$. Phần dư cuối cùng khác 0 $d$ là GCD $(a; b)$ (Hình 2, b, 3, b). Phương pháp này được gọi là thuật toán Euclide.

Ở bên phải
5. Chứng minh rằng từ cặp (1357; 2468) không thể thu được cặp (1234; 5678); từ cặp (123; 457) không thể có được (7890; 1979).

6. Cho ví dụ cho thấy phép toán bài toán 3 không thể hoán vị: $LS \neq SL, RS \neq SR$ (tất nhiên là $LR=RL$).

7. Dùng thuật toán Euclide tìm GCD (589, 1984), GCD (123456789, 987654321).

Mạng nguyên $Z^2$ là tập hợp tất cả các điểm của mặt phẳng có tọa độ nguyên.

Cơm. 6. “Rìa trái” $L(x; b) \rightarrow (x-b; b)$, “viền phải” $R(x; b) \rightarrow (x+b; b)$, “đối xứng” $S(x; b) \rightarrow (b; x)$ là các phép biến đổi tuyến tính của mặt phẳng thực hiện ánh xạ một-một của mạng số nguyên $Z^2$ lên chính nó.

⟦folio 26⟧

Các bài tập và Hình 6 sau đây làm rõ ý nghĩa hình học của bài toán 3:

8. Chứng minh rằng nếu đoạn $OA$, trong đó $O$ là gốc tọa độ, $A$ là một nút của mạng số nguyên $Z^2$, được chia bởi các nút khác thành $d$ phần, thì các phép toán $L$, $R$ và nút $S$ $A$ có thể được dịch thành các nút $(d; 0)$ và $(-d; 0)$ và không thể dịch sang bất kỳ điểm nào khác trên trục $Ox$.

Bài tập 9 và 10 khái quát hóa bài toán 1 và 2:

9*. Cho $n$ số tự nhiên $a_1, a_2, \dots, a_n$. Chứng minh rằng số nguyên $c$ có ​​thể thu được từ 0 bằng cách di chuyển $\pm a_1, \pm a_2, \dots, \pm a_n$ khi và chỉ khi $c$ chia hết cho $HOД$ ($a_1, a_2, \dots, a_n$).

10*. a) Cho vectơ $n$ $v_1, v_2, \dots, v_n$ có ​​tọa độ nguyên trên mặt phẳng $Oxy$. Chứng minh rằng tập hợp các điểm $D$ của mặt phẳng có thể đến từ điểm $O$ bằng cách di chuyển $\pm v_1, \pm v_2, \dots, \pm v_n$, là tập hợp các đỉnh của một số mạng hình cầu (đây là tên tập hợp các đỉnh của hình bình hành trên đó hai họ đường thẳng song song đều cắt mặt phẳng).

6) Giả sử, cùng với mỗi vectơ $v_i$, trong họ vectơ $v_1, v_2, \dots, v_n$ có một vectơ có chiều dài bằng nhau và vuông góc. Khi đó tập hợp các điểm “có thể tới được” $D$ sẽ là tập hợp các đỉnh của một mạng hình vuông nào đó.

Bây giờ không khó để tìm đáp số đến bài toán 1: let $m=dm_1, n=dn_1$, ở đâu $d=HOД(m, n)$; khi đó, nếu $m_1+n_1$ là số lẻ thì tất cả các trường $(dx; dy)$ đều có thể truy cập được, trong đó $x$ và $y$ là số nguyên tùy ý (lưới có bước $d$); nếu $m_1+n_1$ chẵn - các trường $(dx; dy)$, trong đó $x \in Z, y \in Z$ và $x+y$ chẵn (lưới có bước $d\sqrt{2}$, xoay một góc $45^\circ$ đối với các bến tuyến tính).

4. Một số kết quả

Ở phần cuối của bài viết, chúng tôi sẽ giới thiệu tới các bạn hai vấn đề khá khó khăn. Nhưng trước tiên, nhìn lại, chúng ta hãy cố gắng diễn đạt những thông điệp chung đã giúp chúng ta - và sẽ giúp chúng ta trong tương lai - để tìm hiểu xem liệu có thể chuyển từ “vị trí” này sang “vị trí” khác hay không, đồng thời hãy đặt tên cho những “tên” toán học của những khái niệm mà chúng ta gặp phải trong các bài toán.

1°. Để chứng minh sự bất khả thi của quá trình chuyển đổi này hoặc quá trình chuyển đổi kia, chúng tôi đã phát hiện ra một số lời giải - một đặc điểm của vị trí vẫn giữ nguyên (như người ta nói, bất biến) đối với tất cả các nước đi được chấp nhận, nhưng khác nhau đối với vị trí ban đầu và vị trí cuối cùng; Do đó, bằng chứng về sự không thể xảy ra của một quá trình chuyển đổi này hay quá trình chuyển đổi khác đã được rút gọn thành sự phủ nhận tính bất biến. Như vậy là bất biến trong bài toán o {1; 3}-kone là màu của trường, ở bài toán 2 là số dư của phép chia số cho $HOД(a, b)$, ở bài toán 3 là gcd của cặp số trên thẻ. Bạn có thể đọc thêm về điều này trong «Kvant» 1974, Số 2 (trang 26), 1976, Số 2 (trang 32) và 1976, Số 12 (trang 19).

2°. Để xây dựng một chuyển đổi tích phân trên một mạng, thường hữu ích khi tìm một số chuyển động “khóa” cơ bản (hoặc kết hợp các chuyển động), hoặc giảm nó xuống một số vị trí chính tắc đơn giản, sau đó xây dựng một quy tắc (thuật toán) chung để tìm các chuyển đổi. Vì vậy, trong bài toán o {1; 3}-hiệp sĩ chỉ cần học cách di chuyển theo đường chéo, ở bài toán 2 - chuyển sang $d=HOД(a, b)$, ở bài toán 3 - “đi xuống” của vị trí chuẩn (d; 0).

3°. Trong tất cả các màn hình được xem xét, các chuyển đổi được hướng đến vị trí $A$, có thể di chuyển đến vị trí $B$, sau đó có thể quay lại - từ $B$ đến $A$. Trong những bài toán như vậy, toàn bộ tập hợp các vị trí được chia thành các lớp tương đương: trong một lớp, người ta có thể đi từ vị trí này sang vị trí khác và không thể chuyển đổi giữa các vị trí từ các lớp khác nhau.

Bây giờ chúng ta sẽ xem xét bài toán, trong đó tính khả nghịch như vậy đúng với $1^\circ$ và $2^\circ$.

5. Loại bỏ cả hai

Bài toán 4. Ba tác giả in các cặp số tự nhiên lên thẻ. Máy hoạt động như sau: tác giả thứ nhất đọc thẻ $(a; b)$, phát thẻ $(a+1; b+1)$; tác giả thứ hai, sau khi đọc thẻ $(a; b)$, sẽ phát thẻ $(a/2; b/2)$ (nó chỉ hoạt động nếu số a và b là số chẵn); cơ quan thứ ba sử dụng hai thẻ $(a; b)$ và $(b; c)$, cấp thẻ $(a; c)$.

Ban đầu để thẻ $c$ có một cặp số (5; 19). Có thể sử dụng quyền hạn trong

⟦folio 27⟧

được rồi, lấy thẻ a) (1; 50)? b) (1; 100)?

c) Giả sử ban đầu có một quân bài (a; b), a < b, và ta muốn có một quân bài (1; n). Trong những điều kiện nào nó có thể được thực hiện?

bài toán này đã được cung cấp tại Cuộc thi Tối ưu hóa Toán học Toàn Liên minh lần thứ XII cho học sinh lớp 8–10*. Tuy nhiên, ngay cả một học sinh lớp năm cũng sẽ có đủ kiến ​​thức để giải.

Hãy để chúng tôi biểu thị các thao tác mà máy tự động mới của chúng tôi thực hiện tương ứng bằng I, H và T. Hình 7 cho thấy cách lấy thẻ “đơn giản nhất” (1; 8) từ thẻ (5; 19) và sau đó là thẻ (1; 50) (thay vì “áp dụng thao tác I k lần”, chúng tôi lại viết I^k). Như vậy, ở bài toán a) đáp số cơ thể đã được đảm bảo.

Nhưng thẻ (1; 100), mà anh ta hỏi ở bài toán 6), không thể lấy được từ thẻ (5; 19). Trở ngại có thể được phát hiện bằng cách nghiên cứu cẩn thận Hình 7: sự khác biệt giữa các số trên mỗi thẻ chia hết cho 7. Cho dù chúng ta sử dụng máy theo thứ tự nào, chúng ta cũng không thể loại bỏ tính chất này - nó được bảo toàn bởi các phép toán I, H và T. (Đối với I, điều này rất indo. Với H: nếu a và b chẵn và b-a chia hết cho 7 thì b/2-a/2 chia hết cho 7. Đối với T: nếu chênh lệch b-a và c-a đều chia hết cho 7, thì c—a=(c-b)+(b—a) chia hết cho 7.) Nhưng hiệu 100—1=99 không chia hết cho 7, vì vậy đáp số đến 6) là số âm.

Bài tập 11. Có thể sử dụng các máy I, H và T, a) từ thẻ (3; 33) để lấy được thẻ (5; 29), (1; 101), (1; 1978)?

6) Từ lá bài (5; 29) được (3; 33), (1; 100), (1; 1979)?

Bây giờ chúng ta hãy tạo đáp số cho câu hỏi chung cuối cùng trong) bài toán 4: từ một thẻ (a; b), trong đó b—a=2^md, trong đó d>0 và lẻ, chúng ta có thể thu được các thẻ tôi và chỉ tôi (p; q), trong đó hiệu p—q>0 chia hết cho d. Như vậy, có thể loại bỏ cả hai trong khai triển b-a, nhưng ước số lẻ của hiệu b-a là một trở ngại không thể vượt qua.

*) Xem thêm bài toán M516 từ Bài toán Kvant («Kvant», 1978, số 8).

Cơm. 7. Sử dụng các phép toán I^q (tăng q), H (giảm một nửa), T (“chuyển đổi” chuyển tiếp) từ 519, chúng ta nhận được 150

Cơm. 8. Số lớn b trên thẻ có thể giảm đi (d=b-a; a>1 hoặc a=1, b lẻ).

Trên thực tế, như chúng tôi đã nói (với d=7), từ các thẻ có hiệu chia hết cho số lẻ d, sử dụng các phép toán I, H, T, chỉ thu được các thẻ có cùng thuộc tính. Mặt khác, từ thẻ (a; b), trong đó b—a=2^md (d lẻ), bạn có thể chuyển sang thẻ (1; d+1). (Một bước của quá trình chuyển đổi như vậy được hiển thị trong Hình 8.) Sau khi nhận được thẻ (1; d+1), bạn có thể dễ dàng tạo bất kỳ thẻ nào (1; kd+1) (như

⟦folio 29⟧

Cơm. 9. Rút gọn về dạng kinh điển. Đối với tất cả các phép biến đổi $L, R, S$ diện tích hình bình hành và vị trí của các nút của mạng số nguyên bên trong nó được giữ nguyên.

$\begin{pmatrix} 1 & 1 \\ 2 & 2 \end{pmatrix}$ sẽ tạo ra một ma trận có các cột giống hệt nhau $\begin{pmatrix} p & p \\ q & q \end{pmatrix}$.

c) Ma trận $\begin{pmatrix} 1 & 5 \\ 2 & 7 \end{pmatrix}$ và $\begin{pmatrix} 1 & 0 \\ 0 & 1 \end{pmatrix}$ cũng không tương đương; ở đây một trở ngại mới nảy sinh: tầm quan trọng

$$\Delta = \Delta \begin{pmatrix} a & c \\ b & d \end{pmatrix} = |ad - bc|.$$

Nó được bảo toàn dưới mọi phép biến đổi $L, R, S$ của ma trận $\begin{pmatrix} a & c \\ b & d \end{pmatrix}$. Hãy kiểm tra điều này để biết $L: (a-b)d-b(c-d) = ad-bc$. (Đối với $R$ và $S$, hãy tự kiểm tra.) Vì $\Delta \begin{pmatrix} 1 & 5 \\ 2 & 7 \end{pmatrix} = 3,$ là $\Delta \begin{pmatrix} 1 & 0 \\ 0 & 1 \end{pmatrix} = 1$, các ma trận này không tương đương. Lưu ý rằng

$$\Delta \begin{pmatrix} p & p \\ q & q \end{pmatrix} = 0.$$

Đại lượng $ad-bc$ xuất hiện rất thường xuyên trong nhiều bài toán khác nhau về ma trận và được gọi là *định nghĩa* của ma trận $\begin{pmatrix} a & c \\ b & d \end{pmatrix}$.

d) Ma trận $\begin{pmatrix} 1 & 5 \\ 2 & 7 \end{pmatrix}$ và $\begin{pmatrix} 1 & 2 \\ 0 & 3 \end{pmatrix}$ là tương đương: các phép biến đổi số nguyên dẫn vectơ đầu tiên $\begin{pmatrix} 1 \\ 2 \end{pmatrix}$ sang dạng chính tắc $\begin{pmatrix} 1 \\ 0 \end{pmatrix}$ và các sửa đổi bổ sung nhỏ của chúng dẫn đến số nguyên (Hình 9). Trong Hình 9, có thể thấy rõ bất biến $\Delta$ của chúng ta: đây là diện tích của hình bình hành được xây dựng trên các vectơ $\begin{pmatrix} a \\ b \end{pmatrix}$ và $\begin{pmatrix} c \\ d \end{pmatrix}$.

⟦folio 30⟧

Cơm. 10. Trong hình bình hành của ma trận $(\begin{matrix} 1 & 1 \\ 0 & 3 \end{matrix})$ và $(\begin{matrix} 1 & 2 \\ 0 & 3 \end{matrix})$ vị trí các nút của mạng số nguyên là khác nhau.

Vẫn còn phải tìm hiểu xem ma trận $(\begin{matrix} 1 & 1 \\ 0 & 3 \end{matrix})$ và $(\begin{matrix} 1 & 2 \\ 0 & 3 \end{matrix})$ có tương đương hay không. Hóa ra không phải vậy, mặc dù không dễ để chỉ ra mức độ ưu tiên ở đây. Ý nghĩa hình học của nó được thể hiện rõ ràng từ Hình 9 và 10.

Bây giờ chúng ta có thể đưa ra đáp số cho câu hỏi chung bài toán 5. Bất kỳ ma trận rút gọn nào của phép toán $L, R, S$ đều có thể được chuyển đổi sang dạng chính tắc

$$\begin{pmatrix} 1 & r \\ 0 & \Delta \end{pmatrix}, \quad \text{где } 0 \leq r < \Delta,$$

(1)

$$\text{НОД}(r, \Delta) = 1,$$

hoặc

$$\begin{pmatrix} 1 & 1 \\ 0 & 0 \end{pmatrix} \quad (\text{если } \Delta = 0).$$

Hai ma trận tương đương với một mô hình và một mô hình molko khi thỏa mãn các điều kiện (*) và các ma trận rút gọn tương ứng có cùng dạng chính tắc. (Tiêu chí tương đương được xây dựng hơi khác trong Bài tập 20.)

Trên thực tế, bất kỳ ma trận rút gọn nào cũng có thể được chuyển đổi sang dạng chính tắc giống như cách chúng ta chuyển đổi ma trận $(\begin{matrix} 1 & 5 \\ 2 & 7 \end{matrix})$ (xem Hình 9). Việc $r$ là bất biến được rút ra từ Bài tập 14, 15.

Bài tập

14*. Cho ma trận $\begin{pmatrix} a & c \\ b & d \end{pmatrix}$ có dạng chính tắc (1). Khi đó, bên trong hình bình hành $OABC$, được xây dựng trên các vectơ $\overrightarrow{OA} = (a; b)$ và $\overrightarrow{OC} = (c; d)$, có $\Delta-1$ một điểm nguyên. Tất cả các điểm $M_1, M_2, \dots, M_{\Delta-1}$ này có thể đạt được bằng cách sử dụng các đẳng thức vectơ:

$$\overrightarrow{OM}_j = \{j/\Delta\} \overrightarrow{OC} + \{j(1-r/\Delta)\} \overrightarrow{OA},$$

trong đó $\{x\}$ là phần phân số của số $x$.

15. Hãy để $\text{НОД}(a, b) = \text{НОД}(c, d) = 1, \Delta = |ad-bc| \neq 0$. Khi đó có một $r$ duy nhất sao cho $0 \leq r < \Delta$, $\text{НОД}(r, \Delta) = 1$ và các số $ra-c, rb-d$ chia hết cho $\Delta$, và $r$ này được bảo toàn dưới phép biến đổi $L, R, S$ của ma trận $(\begin{pmatrix} a & c \\ b & d \end{pmatrix})$.

Bài tập này hữu ích cho các phép tính cụ thể của số $r$ nếu $\Delta$ không lớn.

16. Ma trận môi trường nào sau đây là tương đương và ma trận nào không:

$$\begin{pmatrix} 5 & 1 \\ 7 & 2 \end{pmatrix}, \quad \begin{pmatrix} 1 & -5 \\ 2 & 7 \end{pmatrix}, \quad \begin{pmatrix} 1 & 3 \\ 3 & 9 \end{pmatrix}, \quad \begin{pmatrix} 4 & 7 \\ 5 & 8 \end{pmatrix},$$

$$\begin{pmatrix} 6 & 14 \\ 17 & 39 \end{pmatrix}, \quad \begin{pmatrix} 5 & 13 \\ 19 & 50 \end{pmatrix}, \quad \begin{pmatrix} 19 & 1 \\ 79 & 4 \end{pmatrix}, \quad \begin{pmatrix} 39 & 60 \\ 50 & 77 \end{pmatrix}?$$

17. Ở trên, chúng ta chưa xét các ma trận trong đó một trong các cột bằng 0. Khi nào ma trận tương đương?

18. Chứng minh rằng mọi ma trận có $\Delta=1$ đều tương đương.

19*. Có bao nhiêu lớp ma trận không tương đương với $\Delta=3, \Delta=4, \Delta=5, \Delta=10, \Delta=12$? Trung bình có bao nhiêu chữ viết tắt? Với mỗi lớp ma trận, vẽ vị trí các nút theo hình bình hành (như Hình 10).

20. Chứng minh rằng với bất kỳ ma trận nào, ma trận tương đương thiết yếu là $(\begin{pmatrix} k & l \\ 0 & m \end{pmatrix})$, trong đó $k \geq 0, m \geq 0, l \geq 0$ và $l < m$ cho $m \neq 0$.

Một cách tiếp cận khả thi khác cho bài toán 3 và 5 là tìm ra loại biến đổi nào của một mạng số nguyên có thể thu được bằng cách kết hợp các phép toán $L, R, S$ (tương tự như cách trong bài toán 2, chúng ta đã tìm ra loại cdwgi nào có thể thu được bằng cách kết hợp các phép toán cdwgov ±a, ±b). Hóa ra tất cả các phép biến đổi mạng này đều có dạng $(x; y) \rightarrow (ax+by; cx+dy)$, trong đó $a, b, c, d$ là số nguyên và $|ad-bc|=1$. Nhưng đây đã là chủ đề của một bài viết riêng về đại số tuyến tính.
