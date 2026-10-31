---
id: 1987-9-tabachnikov-soobrazheniya-nepreryivnosti-be3e63dd
issue: kvant_1987_9
year: 1987
number: "9"
title: Cân nhắc tính liên tục
authors:
  - Табачников С. Л.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 47
page_last: 52
page_labels: 45-50
tag: XQK0
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 9460b64385a173f84e7ee53c1c224c3530e2d927b33c6b5b86d36b0810268ae0
prompt_sha256: draft-1
translated_from: content/ru/1987/09/articles/17_tabachnikov-soobrazheniya-nepreryivnosti-be3e63dd.md
source_content_sha256: 9f2bfb51797c3e5fe2d908a99f2ef2d03f8e488b220413ea8721a7963e93d48d
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 45⟧

Cân nhắc tính liên tục

S. L. TAVACHNIKOV

Hầu hết bài toán trong sách giáo khoa toán học ở trường yêu cầu giải một phương trình, tìm giá trị của một đại lượng nào đó, xây dựng một số với các tính chất cho trước, v.v. Bài viết này dành cho các vấn đề thuộc một loại khác - chúng chỉ yêu cầu chứng minh rằng nghiệm, số, hình, v.v. mong muốn tồn tại. Phương pháp lời giải mà chúng tôi sẽ sử dụng là cân nhắc tính liên tục.

Bài toán về hình ảnh mặt phẳng

Hãy bắt đầu với điều này bài toán. Có một hình dáng nào đó trên một chiếc máy bay. Chứng minh

Hình 1.

biết rằng có một đường thẳng đứng chia diện tích của nó làm đôi.

Hãy lấy một đường thẳng đứng nằm ở bên trái của hình này (hình 1, a) và bắt đầu di chuyển nó sang bên phải. Tại một số thời điểm, đường thẳng sẽ chạm vào viền của hình (hình 1, b), sau đó nó sẽ trượt dọc theo hình (hình 1, ​​​​c-e) và cuối cùng đến bên phải của hình (hình 1, g). Làm thế nào một chuyển động như vậy làm thay đổi diện tích của phần hình nằm bên trái đường thẳng (phần màu xanh ở hình 1)? Diện tích này liên tục thay đổi từ 0 (hình 1, a) đến diện tích của toàn bộ hình S (hình 1, g). Do đó, tại một số điểm, diện tích này bằng một nửa diện tích của toàn bộ hình. Lúc này, một đường thẳng đứng chia diện tích của hình làm đôi.

⟦folio 46⟧

Cuộc thảo luận là lời giải. Thứ nhất, nó không thể xây dựng được đường thẳng mong muốn mà chỉ chứng minh bản chất của nó dưới dạng một hình cho sẵn, hoàn toàn tùy ý.

Thứ hai, lời giải của chúng tôi cho thấy rằng có một đường thẳng theo bất kỳ hướng nào chia diện tích của hình làm đôi. Hơn nữa, từ lời giải cũng suy ra rằng một đường thẳng đi theo một hướng cho trước và chia diện tích của một hình làm đôi được xác định một cách duy nhất. Chúng tôi sẽ sử dụng cái này trong tương lai.

Hãy nhìn vào lời giải của chúng tôi từ một quan điểm hơi khác. Chúng ta chọn trục số (hình 2, a) trên mặt phẳng ngang. Vị trí của đường thẳng đứng tùy ý $l$ được đặc trưng bởi số $x$ (điểm mà đường thẳng $l$ cắt trục). Khoảng cách diện tích của phần hình nằm bên trái của đường thẳng $l$ là hàm của $f(x)$. Đồ thị của hàm số liên tục này được thể hiện ở hình 2, b). Tìm đường thẳng chia đôi diện tích của hình có nghĩa là tìm điểm $c$ trên trục số mà $f(c)=S/2$.

Xét hình 2, b) đường ngang $y=S/2$. Đầu bên trái của đồ thị hàm $f(x)$ nằm bên dưới đường thẳng và đầu bên phải của nó nằm phía trên, vì $f(a)=0<S/2$ và $f(b)=S>S/2$. Do đó, có một điểm giao nhau của đường ngang $y=S/2$ với đồ thị $f(x)$. Lúc này đẳng thức $f(c)=S/2$ được thỏa mãn.

Thuộc tính của các hàm liên tục mà chúng ta sử dụng cho lời giải được gọi là định lý giá trị trung gian:

Giữa hai giá trị, hàm liên tục nhận tất cả các giá trị trung gian.

Vollee hình thức: nếu $f(x)$ là hàm liên tục trên khoảng $[a; b]$ và $c$ là một số nào đó nằm giữa $f(a)$ và $f(b)$, thì trên khoảng $[a; b]$ có một điểm $x_0$ sao cho $f(x_0)=c$.

Ví dụ: trong bài toán của chúng tôi, hàm $f(x)$ nhận giá trị $S/2$, nằm giữa $f(a)=0$ và $f(b)=S$.

Định lý giá trị trung gian gần như hiển nhiên. Và giống như nhiều phát biểu hiển nhiên khác, việc chứng minh nó không hoàn toàn dễ dàng. Để chứng minh điều này chúng ta phải đi sâu hơn vào định nghĩa của hàm liên tục và số thực. Chúng tôi biết rằng chúng tôi đã đi quá xa chủ đề của bài viết, vì vậy định lý giá trị trung gian vẫn đơn giản là hiển nhiên đối với chúng tôi. Và một điều nữa: chúng ta đã không chứng minh được diện tích của phần hàm số nằm trên đường thẳng phụ thuộc liên tục vào vị trí của đường thẳng này (tức là $f(x)$ là hàm số liên tục). Điều này cũng gần như hiển nhiên; và trong các bài toán khác của bài này chúng ta sẽ không chứng minh riêng rẽ tính liên tục của các hàm số tại lời giải.

Bài tập
1. a) Cho một hình lồi*) và một điểm tại eee. Chứng minh rằng có một đường thẳng đi theo một hướng cho trước và chia diện tích của hình làm đôi.
6. bài toán trước đó sẽ biến thành gì nếu điểm tiến tới vô cùng?
b) Giải bước a trong trường hợp điểm nằm bên trong hình.
d) Có đúng là phần a và b chỉ có một đường thẳng không?
2. a) Cho hai hình lồi (có thể cắt nhau). Chứng minh rằng có một đường thẳng chia diện tích mỗi hình làm đôi.
6) bài toán này sẽ biến thành gì nếu một trong các hình co lại thành một điểm?

*) Một hình lồi cùng với hai điểm bất kỳ chứa toàn bộ và đoạn thẳng nối chúng. Ví dụ, hình tròn là hình lồi, nhưng hình tròn thì không.

Hình 3.

⟦folio 47⟧

Tại sao chiếc ghế lại có hình vuông?

Hãy tưởng tượng rằng sàn nhà bếp của bạn không chắc chắn lắm (điều này thường xảy ra, đặc biệt nếu nó được phủ bằng vải sơn). Vì vậy, một chiếc ghế đẩu vuông chỉ đứng trên sàn bằng hai chân trong khi bốn chân treo lơ lửng trên không. Có thể di chuyển chiếc ghế đẩu để nó đứng trên sàn bằng cả bốn chân, hay có thể xảy ra trường hợp dù bạn có ngạc nhiên đến đâu thì chiếc ghế vẫn lắc lư? Tất nhiên, chúng ta giả định rằng khi chiếc ghế đứng vững trên bốn chân, bề mặt của nó có thể hơi nghiêng so với sàn.

(Trước khi bạn bắt đầu phép toán lời giải về bài toán này, hãy làm một thí nghiệm trong nhà bếp của bạn. Sau khi thí nghiệm này cho kết quả dương tính đáp số cho câu hỏi của chúng ta, hãy chuyển sang phép toán lời giải bài toán.)

Chúng ta sẽ giả định rằng bề mặt sàn tuy không bằng phẳng nhưng không khác quá nhiều so với bề mặt phẳng. Giả định này cho phép sử dụng các tầng có hình dạng "bệnh lý" - chẳng hạn như sàn của một hang động được bao phủ bởi thạch nhũ, tức là các cột băng vôi mọc lên trên.

Vì vậy, hãy để chiếc ghế có chân A, B và C trên sàn và bốn chân D treo lơ lửng trên không (hình 4; a).

Không nhấc chân A và C lên khỏi sàn, đặt ghế lên trên một AC tương đối thẳng sao cho chân B và D ở trên không và cách sàn một khoảng bằng nhau (hình 4, b); không có khoảng cách tới sàn dọc theo hướng của chân). Ở vị trí này (hai chân ghế đặt trên sàn và hai chân còn lại cách sàn một khoảng bằng nhau), ghế có thể được di chuyển.

Hãy tưởng tượng rằng sàn nhà được làm bằng đập và chân ghế có thể tự do đi qua nó. Hãy hạ ghế xuống theo hướng chân của nó sao cho chân B và D nằm trên sàn, còn chân A và C ở dưới mặt sàn và cách nó một khoảng bằng nhau (hình 4, c).

Chúng ta bắt đầu xoay ghế quanh tâm ngược chiều kim đồng hồ từ vị trí 4, b, không nhấc chân A và C lên khỏi sàn và giữ khoảng cách bằng nhau giữa chân B và D với sàn. Sau khi quay 90°, chân A và C sẽ lần lượt giữ vị trí của chân D và B tại hình 4, b, còn chân B và D sẽ lần lượt đảm nhận vị trí của chân A và C tại hình 4, b. Khi ghế di chuyển, khoảng cách từ chân B, D đến sàn thay đổi liên tục. Tại thời điểm ban đầu - hình 4, b - khoảng cách này là dương, vì hai chân ở trên mặt sàn và tại thời điểm cuối cùng, được hiển thị ở hình 4, b, khoảng cách này là âm vì hai chân ở dưới mặt sàn. Do đó, đã có lúc khoảng cách này bằng 0. Lúc đó chiếc ghế đã đứng vững trên cả bốn chân.

Những gì chúng tôi tìm thấy không chỉ có giá trị về mặt lý thuyết mà còn có giá trị thực tế - bằng cách xoay chiếc ghế 90° quanh tâm, bạn có thể tìm được một vị trí ổn định. Kiểm tra điều này bằng thực nghiệm. Và một lưu ý nữa. Những gì chúng tôi tìm thấy dựa trên thực tế là chân của chiếc ghế đẩu nằm ở các đỉnh của hình vuông. Nếu chúng nằm ở các đỉnh của một đường thẳng

⟦folio 48⟧

Một hình vuông hay một hình tứ giác khác, lý luận của chúng ta sẽ không hiệu quả. Tác giả không biết nhận định bài toán có đúng với các tứ giác không phải là hình vuông hay không (trong mọi trường hợp rõ ràng là tứ giác nội tiếp phải là hình tròn). Nếu bạn đọc nào hiểu được vấn đề này thì hãy cho chúng tôi biết nhé.

Bài tập

7. Giáo viên yêu cầu chứng minh một hình lồi có thể chia một cặp đường thẳng vuông góc với nhau thành bốn phần có vận tốc bằng nhau. Một sinh viên đã đề xuất điều này lời giải. "Theo bất kỳ hướng nào, bạn có thể vẽ một đường thẳng l chia diện tích của hình làm đôi (hình 5, a). Mỗi hình phẳng thu được có thể được chia thành hai phần có vận tốc bằng nhau bằng các đường thẳng vuông góc với l (hình 5, b). Hãy bắt đầu thay đổi hướng của đường thẳng l, giữ nguyên hình dáng của hình vẽ. Sau khi đổi hướng 180°, các điểm A và B sẽ đổi chỗ cho nhau. Điều này có nghĩa là tại một thời điểm nào đó chúng trùng khớp lúc này hình 5, b sẽ biến thành hình 5, c và chúng ta sẽ thu được cặp đường vuông góc như mong muốn chia diện tích hình thành bốn phần có vận tốc bằng nhau.

a) Tìm lỗi trong lời giải này.
b) Tìm ra kết quả đúng lời giải bài toán.

8. Chứng minh rằng một hình vuông có thể viết được thành một hình lồi đối xứng tâm. (Trên thực tế, một hình vuông có thể được viết thành bất kỳ hình nào. Nhưng để chứng minh định lý này của nhà toán học xuất sắc Liên Xô L. G. Shirelman (1905-1938), chỉ thông điệp liên tục thôi thì không còn đủ nữa.)

9. Cho hai hình lồi, một hình nằm trong hình kia. Chứng minh rằng:
a) có hai dây cung song song của hình ngoài tiếp xúc với hình trong và có cùng độ dài (hình 6, a);
b) có một điểm X của hình bên ngoài mà từ đó vẽ hai dây tiếp tuyến bằng nhau với hình bên trong (hình 6, b).
Nghị định và e. Trong số các dây của hình ngoài tiếp xúc với hình trong, có dây có độ dài lớn nhất. Vẽ các tiếp tuyến từ đầu của nó tới hình bên trong.

10. Cho ba hình lồi, kéo dài vào nhau (hình 7). Chứng minh rằng tồn tại một điểm X của hình bên ngoài mà từ đó có thể vẽ một dây tiếp tuyến với hình bên trong sao cho các đoạn ở hình ở giữa bằng nhau.

Về nghiệm của đa thức và dây của đồ thị hàm số

Tất nhiên, bạn biết rằng một tam giác vuông có thể không có nghiệm - ví dụ như đa thức x2+x+1. Còn đa thức bậc ba thì sao? Bây giờ chúng ta sẽ chứng minh điều đó

mọi đa thức bậc ba đều có ít nhất một nghiệm

Trước tiên chúng ta hãy xem xét một đa thức bậc ba có hệ số cao nhất là 1:

f(x)=x³+bx²+cx+d

Hãy viết nó ở dạng này: f(x)=x³(1+b/x+c/x²+d/x³). Nếu các giá trị |x| rất lớn thì các số hạng b/x, c/x² và d/x³ trở nên rất nhỏ. Do đó, số trong ngoặc gần bằng 1 và trong mọi trường hợp đều là số dương. Do đó, dấu của f(x) đối với |x| lớn được xác định bởi dấu của số x³. Do đó, f(x)<0 đối với x âm lớn ở giá trị tuyệt đối và f(x)>0 đối với x dương lớn.

Đa thức bậc ba, giống như bất kỳ đa thức nào, là một hàm liên tục. Do đó, định lý giá trị trung gian có thể được áp dụng. Từ đó suy ra rằng có một x sao cho f(x)=0. Do đó, đa thức bậc ba có nghiệm.

Trường hợp của đa thức bậc ba tổng quát f(x)=ax³+bx²+cx+d tương tự như trường hợp đã được thảo luận: chỉ cần chia f(x) cho a là đủ.

Bằng chứng của chúng ta về lòng tốt hay tuyến tiền liệt là sự hợp nhất và điểm yếu của các thông điệp liên tục. Chúng tôi đã "miễn phí" nhận được một tuyên bố không rõ ràng về sự tồn tại của một nghiệm, nhưng vẫn chưa rõ gốc của một đa thức cụ thể trên đó như thế nào (các công thức tính nghiệm của một đa thức bậc ba tồn tại, nhưng ... đây là một vấn đề hoàn toàn khác và chúng tôi sẽ không đề cập đến nó).

⟦folio 49⟧

Một ví dụ khác. Giả sử $f(x)$ là hàm tuần hoàn liên tục trên đường thẳng có chu kỳ $T$. Chứng minh rằng đồ thị của nó có dây cung ngang có độ dài $T/2$.

Sự tồn tại của dây ngang có độ dài $l$ tương đương với đẳng thức $f(x)=f(x+l)$ (hình 8). Vì vậy, ta cần chứng minh rằng tồn tại $x$ sao cho $f(x+T/2)=f(x)$. Nói cách khác, chúng ta cần chứng minh rằng hàm $g(x)=f(x+T/2)-f(x)$ có nghiệm, tức là $g(x)=0$ với một số $x$.

Hãy lấy một số tùy ý $a$. Nếu $g(a)=0$, thì mọi thứ đã được chứng minh; vì vậy giả sử rằng $g(a)\neq 0$. Đối với định nghĩa, chúng ta sẽ giả sử rằng $g(a)<0$. Hãy để $b=a+T/2$. Hãy tìm giá trị của $g(b)$:

$$g(b)=g(a+T/2)=f(a+T/2+T/2)-f(a+T/2)=f(a+T)-f(a+T/2)=-f(a)-f(a+T/2)=-g(a).$$

Vì vậy, $g(b)>0$.

Hàm $g(x)$ là hàm liên tục, giống như hiệu của các hàm liên tục. Vì vậy, chúng ta có thể sử dụng định lý giá trị trung gian. Từ định lý này suy ra rằng giữa các số $a$ và $b$ có ​​một $x$ sao cho $g(x)=0$.

Phát biểu về dây ngang của đồ thị hàm tuần hoàn có thể được biết thành công: đồ thị của hàm số đó có dây ngang có độ dài tùy ý.

Nhưng với đồ thị hàm số liên tục trên một đoạn thì tình hình lại khác. Cho một hàm liên tục trên một đoạn có độ dài $T$ có giá trị ở hai đầu của đoạn đó trùng nhau.

Hình 6.

Hình 7.

Khi đó, nếu số $l$ có dạng $T/n$ đối với một số tự nhiên $n$, thì đồ thị của hàm số nhất thiết phải có dây cung ngang có độ dài $l$; nếu $l$ không có dạng này thì tồn tại một hàm liên tục có các giá trị giống nhau ở hai đầu của đoạn, đồ thị của nó không có dây ngang có độ dài $l$. (Bạn sẽ tìm thấy câu chuyện chi tiết về điều này trong bài viết của I.M. Yaglom “Về hợp âm của các đường cong liên tục”, «Kvant», 1977, số 4.)

Bài toán

11. Chứng minh rằng đa thức bậc lẻ có nghiệm.

12. Hôm qua trời lạnh hơn hẳn ngày hôm kia và hôm nay. Chứng minh rằng hôm nay có một thời điểm giống nhau khi nhiệt độ không đổi.

13. Đặt $f(x)$ là một hàm liên tục trên một phân đoạn nhất định và để tất cả các giá trị được gán cho cùng một phân đoạn. Chứng minh rằng tồn tại $x$ sao cho $f(x)=x$.

14. Đa thức $f(x)=ax^2+bx+c$ sao cho phương trình $f(x)=x$ không có lời giải. Chứng minh rằng phương trình $f(f(x))=x$ cũng không có lời giải.

15. Giả sử $f(x)$ là hàm tuần hoàn liên tục trên đường thẳng có chu kỳ $T$. Chứng minh rằng đồ thị của nó có dây cung có độ dài tùy ý.

17. Giá trị trung bình của hàm $f(x)$ trên đoạn $[a; b]$ là giá trị $\frac{1}{b-a}\int_a^b f(x)dx$.

Chứng minh rằng nếu giá trị trung bình của hàm số liên tục trên một khoảng nào đó bằng 0 thì nó sẽ có giá trị bằng 0 trên khoảng này.

18. Hãy xem xét một hàm có dạng $f(x)=a_1\sin x+a_2\sin 2x+\dots+a_n\sin nx+b_1\cos x+b_2\cos 2x+\dots+b_k\cos kx$, trong đó $a_1, \dots, a_n, b_1, \dots, b_k$ là một số hệ số. Chứng minh rằng phương trình $f(x)=0$ có ​​nghiệm.

Phần kết luận

Chúng tôi đã phân tích một số bài toán, trong đó lời giải trong đó việc cân nhắc tính liên tục đóng vai trò chính. Trong mỗi

⟦folio 50⟧

Từ bài toán, giá trị mà chúng ta quan tâm phụ thuộc vào một tham số - ví dụ: diện tích của một phần hình nằm trên một cạnh của đường thẳng phụ thuộc vào góc nghiêng của đường thẳng này. Thông báo liên tục có thể được mở rộng cho trường hợp có nhiều hơn một tham số. Cuộc thảo luận chi tiết về vấn đề này không nằm trong kế hoạch của chúng tôi; Chúng ta hãy giới hạn ở việc xây dựng một vài định lý.

1. Ba cơ thể được đặt ngẫu nhiên trong không gian. Có một mặt phẳng chia thể tích của mỗi vật làm đôi. Tuyên bố này được gọi là “định lý bánh sandwich giăm bông” (phần đầu tiên là một miếng bánh mì, phần thứ hai là một lớp bơ và phần thứ ba là một lát giăm bông).

2. Có hai điểm đối xứng nhau như vậy trên trái đất, tại đó nhiệt độ và áp suất trùng nhau.

3. Một khối lập phương có thể được mô tả xung quanh một vật thể lồi. (Định lý này khái quát hóa phát biểu bài toán 6 cho trường hợp không gian).

4. Hãy tưởng tượng một quả bóng phủ đầy tóc. Liệu có thể “chải” sao cho mỗi sợi tóc chạm vào bề mặt quả bóng và hướng của các sợi tóc đặt gần nhau không khác nhau nhiều không? Hóa ra điều này là không thể - ít nhất một sợi tóc vẫn vuông góc với bề mặt quả bóng. Tuyên bố này được gọi là "định lý con nhím" hay "định lý chải bóng".

5 (dành cho người biết số phức). Ta đã chứng minh được rằng đa thức bậc lẻ phải có nghiệm thực. Còn rễ phức tạp thì sao? Hóa ra là bất kỳ đa thức nào (không phải hằng số) đều có ít nhất một nghiệm phức. Tuyên bố này của hiện tại quan trọng đến mức nó được gọi là định lý cơ bản của đại số. Một cách tiếp cận để chứng minh nó cũng dựa trên các thông điệp liên tục.

Đoán số

(Để bắt đầu, xem trang 34)

Hãy thử trả lời câu hỏi sau: “133 đội tham gia thi đấu cúp bóng chuyền, các cuộc thi được tổ chức theo hệ thống Olympic; sẽ thi đấu bao nhiêu trận để phân định đội thắng?

Đầu tiên, mỗi người phải đếm rất lâu mới có được đáp số, nhưng lời giải hóa ra lại cực kỳ đơn giản. Cần lưu ý rằng trong mỗi trận đấu có đúng một đội bị loại, nhưng chỉ cần ở lại một đội; Điều này có nghĩa là để 132 đội bị loại thì phải thi đấu 132 trận.

Ý tưởng tương tự cũng xuất hiện trong lời giải, một bài toán phổ biến khác. Sô cô la bao gồm các miếng 3x8. Bạn cần thực hiện bao nhiêu lần ngắt dọc theo đường để bẻ hoàn toàn thành từng mảnh? Lúc đầu, họ quyết định đi vào ngõ cụt: suy cho cùng, bạn có thể phá vỡ mọi thứ theo những cách hoàn toàn khác nhau! Nhưng hãy làm rõ về bài toán. Có một miếng sô cô la, bạn cần lấy 24 miếng, và với mỗi lần bẻ, số miếng sẽ tăng thêm đúng một miếng. Điều này có nghĩa là bạn sẽ phải bẻ nó 23 lần và việc bạn làm theo thứ tự nào không quan trọng.

Ấn phẩm được A. P. Savin biên soạn dựa trên tài liệu của V. A. Dalingar và F. N. Fazylov
