---
id: 1987-7-panov-genealogicheskie-derevya-6694edad
issue: kvant_1987_7
year: 1987
number: "7"
title: Cây gia phả
authors:
  - Панов А. А.
rubric: osnovnye-stati
page_first: 10
page_last: 15
page_labels: 8, 10, 11, 12, 13
tag: 9VI4
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c0e3259c2b68c3cc653bceb2b28f4da5dd93a3a156952fd9e662a9df0169f6eb
prompt_sha256: draft-1
translated_from: content/ru/1987/07/articles/03_panov-genealogicheskie-derevya-6694edad.md
source_content_sha256: bcc0ed2b54bdb8df8437b0c26460c154739dd644f163613e59f778f378dadf45
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 8⟧

CÂY PHỔ PHÁP

A. A. PANOV

Bài viết này sẽ nói về toán học kinh điển - thuật toán Euclid và bộ ba Pythagore. Thuật toán Euclid được mô tả trong Eklid's Elements (khoảng năm 300 trước Công nguyên) và có lẽ đã được biết đến từ rất lâu trước đó. Lịch sử của bộ ba Pythagore thậm chí còn có thể được truy nguyên xa hơn. Một tượng đài đáng chú ý của văn hóa nhân loại là chiếc bàn đất sét Avilonian cổ chứa mười lăm bộ ba Pythagore. Nó có từ năm 1700 trước Công nguyên. đ.

Ở đây chúng tôi sẽ cố gắng xây dựng bụi với những nhân chứng cổ xưa này, nói về họ bằng “ngôn ngữ của cây cối” trực quan. Ngôn ngữ này tỏ ra hữu ích cho lời giải một số phương trình và chỉ ra mối liên hệ nào tồn tại giữa thuật toán Euclid và phương pháp xây dựng bộ ba Pythagore do nhà toán học người Anh A. Hall đề xuất gần đây.

Thuật toán Euclid
Thuật toán Euclid được sử dụng để tìm ước chung nhất (GCD) của hai số tự nhiên.

Cho $(m, n)$ là một cặp số nguyên dương:
1) nếu $m=n$ thì số $d=m=n$ là ước chung nhất của cặp số ban đầu, nếu $m \neq n$ thì về 2);
2) thay thế số lớn hơn bằng hiệu của nó bằng số nhỏ hơn và chuyển về 1).

Bạn có thể được dẫn đến phiên bản sau của bước 2 nhiều hơn:

2') thay số lớn hơn bằng số dư của nó khi chia cho số nhỏ hơn và tiến tới 1),
nhưng đây là vấn đề về hương vị.

Bài toán 0. Chứng minh rằng cả hai thuật toán 1), 2) và 1), 2') đều dẫn đến cùng một kết quả.

Gợi ý. Hãy nhớ rằng phép chia là phép trừ lặp đi lặp lại.

Trong mọi trường hợp, bản thân Euclid nói về thuật toán của mình là “sự khác biệt không đổi giữa ít hơn và nhiều hơn” (“Các nguyên tắc”, Quyển 7, Mệnh đề P, do D. D. Morduchai-Boltovsky dịch). Thuật toán này, dựa trên phép trừ lặp đi lặp lại, sẽ là đối tượng nghiên cứu của chúng tôi.

Hãy để chúng tôi chứng minh hoạt động của thuật toán bằng một ví dụ cụ thể. Hãy để $(m, n)=(20, 12)$. Sau đó, viết các hành động của thuật toán từ phải sang trái, chúng ta thu được chuỗi sau:

$(4, 4) \leftarrow (8, 4) \leftarrow (8, 12) \leftarrow (20, 12)$.

Điều này có nghĩa là GCD $(20, 12)=4$. Làm tương tự với cặp $(5, 3)$ ta được sợi dây chuyền

$(1, 1) \leftarrow (2, 1) \leftarrow (2, 3) \leftarrow (5, 3)$.

Rõ ràng là mỗi số trong chuỗi thứ hai được lấy từ số tương ứng trong chuỗi thứ nhất bằng cách chia cho 4.

Sau khi hiểu ví dụ này, hãy trả lời câu hỏi sau.

Bài toán 1. Đặt $d=НОД (M, N)$. Hãy đặt $m=M/d, n=N/d$. Gcd của $(m, n)$ là gì và điểm giống nhau giữa hành động của thuật toán Euclide trên cặp $(M, N)$ và trên cặp $(m, n)$ là gì?

Trong phần tiếp theo, chúng tôi sẽ chỉ giới hạn các cặp $(m, n)$ có GCD là $(m, n)=1$. Chúng ta sẽ gọi những cặp như vậy là cặp đơn giản.

Gia phả của các cặp vợ chồng đơn giản
Hãy xem một ví dụ khác. Hãy áp dụng thuật toán Euclide cho cặp đơn giản $(3, 4)$:

$(1, 1) \leftarrow (2, 1) \leftarrow (3, 1) \leftarrow (3, 4)$.

Chuỗi này có một phần chung với chuỗi dành cho cặp $(5, 3)$ và do đó chúng có thể được kết hợp:

$(3, 1) \leftarrow (3, 4)$
$(2, 3) \leftarrow (5, 3)$

Bạn có thể thêm một cặp đơn giản khác $(3, 2)$ và hình ảnh về điều kiện là:

$(3, 1) \leftarrow (3, 4)$
$(2, 1) \leftarrow (2, 3) \leftarrow (5, 3)$
$(1, 2) \leftarrow (3, 2)$

⟦folio 10⟧

Dường như tất cả các cặp đơn giản đều phải có một bức tranh tổng quát. Để tìm ra cấu trúc của nó, chúng ta có thể thêm một vài cặp đơn giản hơn. Bằng cách này hay cách khác, tại một thời điểm nào đó, câu hỏi đúng phải xuất hiện trong đầu chúng ta: đường đi có một cặp đơn giản $(m, n)$; mũi tên có thể đi tới nó từ cặp nào?

Bài toán 2. Chứng minh rằng nếu từ cặp $(M, N)$ trong thuật toán Euclide có mũi tên chỉ đến cặp $(m, n)$ thì $M=m+n$, $N=n$ hoặc $M=m$, $N=m+n$.

bài toán này gợi ý rằng chúng ta cần đưa ra hai phép biến đổi $t_1$ và $t_2$ để đưa cặp $(m, n)$ thành cặp
$$t_1(m, n)=(m+n, n),$$
$$t_2(m, n)=(m, m+n).$$
(1).

Bây giờ chúng ta có thể di chuyển theo thứ tự ngược lại. Hãy bắt đầu với cặp $(1, 1)$ và áp dụng cả hai phép biến đổi $t_1$ và $t_2$ cho nó ($t_1$ tác động lên mũi tên hướng lên, $t_2$ trên mũi tên hướng xuống). Chúng tôi nhận được hai cặp mới - $(2, 1)$ và $(1, 2)$. Đối với mỗi người trong số họ, chúng tôi lại áp dụng $t_1$ và $t_2$, v.v.

Mỗi cặp ở đây tạo ra hai cặp mới và quá trình này tiếp tục lần đầu tiên đến vô tận. Như bạn mong đợi, hình 1 chứa toàn bộ hình ảnh trước đó dưới dạng các mảnh vỡ, chỉ có các mũi tên ở đây hướng về hướng khác.

Hình 1.

Bài toán 3. Chứng minh rằng mọi cặp $(m, n)$ trên hình 1 đều đơn.

Bài toán 4. Chứng minh rằng mọi cặp đơn đều chứa trên hình 1 và chỉ một lần.

Sau bài toán này đến những gì được mô tả trong hình 1, việc gọi cây gia phả của các cặp đơn giản là điều đương nhiên.

Bài toán 5. Để cặp $(m, n)$ nằm trên cây phả hệ tại hình 1. Có một đường dẫn duy nhất nối nó với cặp ban đầu $(1, 1)$. Chứng minh rằng việc di chuyển dọc theo đường đi này theo các mũi tên tương ứng với việc áp dụng thuật toán Euclide cho cặp $(m, n)$.

Vì vậy, cây phả hệ trên hình 1 chứa tất cả các cặp đơn giản. Áp dụng thuật toán Euclide cho cặp $(m, n)$ tương đương với việc di chuyển dọc theo cây theo hướng mũi tên.

Phương trình $XY=Z^2$
Bây giờ chúng ta hãy thay đổi chủ đề và cố gắng tìm tất cả các phương trình số nguyên lời giải $(X, Y, Z)$
$$XY=Z^2.$$

Chúng tôi chỉ hạn chế tích cực $X, Y, Z$. Ví dụ: $X=3$, $Y=12$, $Z=6$.

Có vẻ như, những gì để nói về? Đối với một $Z$ cho trước, việc tìm một phương trình lời giải là tính chất phân tách số $Z^2$ thành hai thừa số và với mỗi thừa số $Z$ người ta thậm chí có thể tính được số lời giải.

Bài toán 6. Chúng ta hãy sửa $Z$ và đường dẫn $Z=p_1^{a_1}p_2^{a_2}...p_l^{a_l}$—sự phân tách $Z$ thành các thừa số đơn giản. Chứng minh rằng số lời giải của phương trình (2) bằng $(2a_1+1)(2a_2+1)...(2a_l+1)$.

Tuy nhiên, tôi muốn đưa ra một quan điểm khác.

Bài toán 7. Đặt $(X, Y, Z)$ — lời giải của phương trình (2); chứng minh rằng với $d>0$ bộ ba $(dX, dY, dZ)$ cũng bằng lời giải. Đặt $(X, Y, Z)$ — lời giải của phương trình (2) và gcd $(X, Y)=d$; chứng minh rằng $(X/d, Y/d, Z/d)$ cũng là lời giải của phương trình (2) và đồng thời gcd $(X/d, Y/d)=1$.

Do đó, khi tìm kiếm tất cả lời giải $(X, Y, Z)$ của phương trình (2), chúng ta có thể giới hạn chỉ những phương trình có GCD $(X, Y)=1$; Hãy gọi chúng là nguyên thủy. Tất cả phần còn lại được lấy từ những cái nguyên thủy bằng phép nhân đơn giản.

Bài toán 8. Đặt $(X, Y, Z)$ là lời giải nguyên thủy của phương trình (2). Chứng minh rằng tồn tại một cặp đơn giản $(m, n)$ sao cho $X=m^2$, $Y=n^2$, $Z=mn$.

Bây giờ rõ ràng là các sự tương ứng $X=m^2$, $Y=n^2$, $Z=mn$ (3) cung cấp sự tương ứng một-một giữa các cặp đơn giản $(m, n)$ và các nghiệm nguyên thủy $(X, Y, Z)$ của phương trình (2).

Điều này có nghĩa là chúng ta có thể tận dụng tối đa kết quả trước đó của mình trên các cặp đơn giản. Ví dụ: bằng cách sử dụng sự tương ứng (3), chúng tôi thay thế từng cặp đơn giản $(m, n)$ bằng hình 1 bằng nghiệm nguyên thủy tương ứng $(X, Y, Z)$. Cây kết quả đương nhiên có thể được gọi là cây gen của phương trình lời giải nguyên thủy (2). Nó chứa mọi thứ mà không có

⟦folio 11⟧

ngoại lệ là nguyên thủy lời giải. Có thể đề xuất một cách trực tiếp và thuận tiện hơn để xây dựng cây này.

Nhiệm vụ 9. Để cặp $(m, n)$ tạo lời giải $(X, Y, Z)$ bằng cách sử dụng (3). Hãy để chúng tôi biểu thị lời giải được tạo bởi cặp $t_1(m, n) = (m+n, n)$ bởi $T_1(X, Y, Z)$ và lời giải, được tạo bởi $t_2(m, n) = (m, m+n)$ bởi $T_2(X, Y, Z)$. Chứng minh rằng

$$T_1(X, Y, Z) = (X+Y+2Z, Y, Y+Z),$$
$$T_2(X, Y, Z) = (X, X+Y+2Z, X+Z).$$

Tất cả điều này có nghĩa là cây phả hệ trên hình 2 phát sinh trực tiếp từ phép biến đổi $T_1$ và $T_2$. Chúng ta bắt đầu từ lời giải (1, 1, 1) tiếp theo và bắt đầu áp dụng các phép biến đổi $T_1$ và $T_2$ trên đó. Mũi tên đi lên tương ứng với hành động $T_1$, mũi tên đi xuống tương ứng với hành động $T_2$.

Hình 2.

Hình 2 trông rất hấp dẫn và cho phép chúng ta hình dung rõ ràng về cấu trúc của tập hợp tất cả các phương trình lời giải nguyên thủy (2). Tuy nhiên, phương trình $XY=Z^2$, như chúng ta đã nói, cho phép một cách tiếp cận đơn giản hơn. Vì vậy, hãy chuyển sang xem xét một ví dụ có ý nghĩa hơn.

Bộ ba Pythagoron

Vậy phương trình
$$X^2+Y^2=Z^2.$$
Số nguyên dương lời giải $(X, Y, Z)$ của nó được gọi là *bộ ba Pythagoron*. Ví dụ đầu tiên về bộ ba Pythagore tất nhiên là bộ ba (3, 4, 5). Chúng tôi cũng muốn xây dựng một cây lời giải cho phương trình này - một cây gia phả của bộ ba Pythagore, tương tự như cây trong hình 2. Làm thế nào để thực hiện điều này? Nếu chúng ta làm theo những gì đã được thực hiện cho phương trình $XY=Z^2$, thì chúng ta cần:

(I) trong số tất cả các bộ ba Pythagore, hãy chọn những bộ nguyên thủy;

(II) đối với các bộ ba Pythagore nguyên thủy $(X, Y, Z)$ viết các tương ứng phù hợp $X=X(m,n), Y=Y(m,n), Z=Z(m,n)$ với các tương ứng tương tự (3);

(III) xây dựng cây phả hệ cho các cặp $(m, n)$ và thay thế mỗi cặp $(m, n)$ trên đó bằng bộ ba $(X(m, n), Y(m, n), Z(m, n))$ do nó tạo ra.

Những gì được kết nối với điểm (I) và (II) đã được biết đến từ lâu. Chúng tôi sẽ báo cáo những sự thật cần thiết mà không có bất kỳ bình luận hay bằng chứng nào, giới thiệu cho người đọc, nếu cần, bài viết của S. M. Voronin và A. G. Kulagin («Kvant», 1987, Số 1, trang 11).

Bộ ba Pythagore $(X, Y, Z)$ được gọi là *nguyên thủy* nếu GCD $(X, Y)=1$ và $X$ là số lẻ và $Y$ là số chẵn. Ví dụ, bộ ba (3, 4, 5) là nguyên thủy.

Người ta biết rằng với bất kỳ bộ ba Pythagore $(x, y, z)$ nào đều có một bộ ba Pythagore nguyên thủy duy nhất $(X, Y, Z)$ và một số tự nhiên duy nhất $d$ sao cho $(x, y, z)=(dX, dY, dZ)$ hoặc $(x, y, z)=(dY, dX, dZ)$. Do đó, sau khi liệt kê tất cả các bộ ba Pythagoron nguyên thủy, chúng ta có cơ hội liệt kê tất cả các bộ ba Pythagoron tổng quát.

Một cặp số nguyên $(m, n)$ được gọi là *nguyên thủy* nếu $m>n, n>0$, gcd $(m, n)=1$ và các số $m, n$ có các số chẵn lẻ khác nhau. Ví dụ: cặp (2, 1) là nguyên thủy.

Người ta biết rằng sự tương ứng $X=m^2-n^2, Y=2mn, Z=m^2+n^2$ (4) cung cấp sự tương ứng một-một giữa tập hợp tất cả các cặp nguyên thủy và tập hợp tất cả các bộ ba Pythagore nguyên thủy. Ví dụ, cặp (2, 1), với sự trợ giúp của các tương ứng (4) sẽ tạo ra bộ ba (3, 4, 5).

Đối với điểm (III) trong chương trình xây dựng cây phả hệ của chúng tôi, nó đã được thực hiện bởi nhà toán học người Anh A. Hall.

Phả hệ của bộ ba Pythagore

Trong một ghi chú ngắn xuất bản năm 1970 trên Công báo Toán học, A. Hall gợi ý

⟦folio 12⟧

Sau đây là phương pháp xây dựng cây phả hệ cho các cặp nguyên thủy và bộ ba Pythagore nguyên thủy. Ba phép biến đổi $t_1, t_2$ và $t_3$ được giới thiệu:

$$t_1(m, n) = (2m - n, m),$$
$$t_2(m, n) = (2m + n, m),$$
$$t_3(m, n) = (m + 2n, n).$$

Sử dụng các phép biến đổi này, bắt đầu từ cặp (2, 1), một cây phả hệ sẽ được xây dựng. Ở đây hướng đi lên tương ứng với phép biến đổi $t_1$, hướng ngang tương ứng với phép biến đổi $t_2$ và hướng đi xuống tương ứng với phép biến đổi $t_3$.

Bài toán 10. Để cặp $(m, n)$ tạo ra bộ ba số Pythagore $(X, Y, Z)$ bằng cách sử dụng các phép tương ứng (4). Bộ ba số Pythagore do cặp $t_1$ $(m, n)$ tạo ra được ký hiệu là $T_1(X, Y, Z)$; bộ ba được tạo bởi cặp $t_2$ $(m, n)$, đến $T_2(X, Y, Z)$; cuối cùng là bộ ba được tạo bởi cặp $t_3$ $(m, n)$ đến $T_3(X, Y, Z)$. Chứng minh rằng

$$T_1(X, Y, Z) = (X - 2Y + 2Z, 2X - Y + 2Z, 2X - 2Y + 3Z),$$
$$T_2(X, Y, Z) = (X + 2Y + 2Z, 2X + Y + 2Z, 2X + 2Y + 3Z),$$
$$T_3(X, Y, Z) = (-X + 2Y + 2Z, -2X + Y + 2Z, -2X + 2Y + 3Z).$$

Bây giờ, bằng cách sử dụng phép biến đổi $T_1, T_2, T_3$, chúng ta sẽ xây dựng một cây gia phả khác, nhưng nó đã bắt đầu bằng bộ ba (3, 4, 5).

Kết quả đáng chú ý của Hall là cây phả hệ trên hình 3 chứa tất cả các cặp nguyên thủy không có ngoại lệ; Điều này có nghĩa là cây phả hệ trên hình 4 chứa tất cả các cặp (2, 1) không có ngoại lệ.

Mỗi cặp $(m, n)$ đến hình 3 khớp chính xác một mũi tên. Đối với phép biến đổi $u_1, u_2, u_3$, điều này tương ứng với thực tế sau.

Bài toán 13. Đặt cặp $(M, N)$ là nguyên thủy và $(M, N) \neq (2, 1)$. Chứng minh rằng khi đó chỉ có một trong ba cặp $(m, n) = u_i(M, N)$, $i = 1, 2, 3$ là nguyên thủy. Đồng thời $m + n < M + N$.

Và cuối cùng, cái cuối cùng

Bài toán 14. Chứng minh rằng mọi cặp nguyên thủy đều có trên cây phả hệ tại hình 3 và chỉ một lần (cũng như mọi bộ ba Pythagogian nguyên thủy tại hình 4).

Các nhà phả hệ khác

Năm 1978, một bài báo của E. Selmar được đăng trên tạp chí toán học Scandinavian Nomat, trong đó người ta khẳng định rằng có

⟦folio 13⟧

thêm hai cây gen chứa tất cả các bộ ba Pythagore nguyên thủy không có ngoại lệ hoặc lặp lại (hình 5).

Đầu tiên trong số chúng được xây dựng bằng cách sử dụng phép biến đổi
$$T_1(X, Y, Z) = (2X - Y + Z, 2X + 2Y + 2Z, 2X + Y + 3Z),$$
$$T_2(X, Y, Z) = (2X + Y + Z, 2X - 2Y + 2Z, 2X - Y + 3Z),$$
$$T_3(X, Y, Z) = (2X + Y - Z, -2X + 2Y + 2Z, -2X + Y + 3Z).$$

Thứ hai - sử dụng phép biến đổi
$$T_1(X, Y, Z) = (X - 2Y + 2Z, 2X - Y + 2Z, 2X - 2Y + 3Z),$$
$$T_2(X, Y, Z) = (2X + Y + Z, 2X - 2Y + 2Z, 2X - Y + 3Z),$$
$$T_3(X, Y, Z) = (-2X + 3Y + 3Z, -6X + 2Y + 6Z, -6X + 3Y + 7Z).$$

Xe ba bánh Pythagore luôn thu hút sự chú ý của các nhà toán học trong hàng ngàn năm. Nhưng chúng tôi thấy rằng chủ đề này vẫn chưa cạn kiệt và những sự thật thú vị mới tiếp tục được khám phá ở đây.

Tóm tắt
Liên quan đến những gì đã nói, có một số câu hỏi cần được đặt ra, nếu không được giải quyết thì ít nhất cũng phải hỏi. Ví dụ: tại sao đối với điều khiển $XY = Z^2$ lại có hai mũi tên từ mỗi lời giải và ba mũi tên trên cây phả hệ cho $X^2 + Y^2 = Z^2$? Hơn nữa, tại sao ba cây gen được xây dựng để kiểm soát $X^2 + Y^2 = Z^2$ và chỉ một cây để kiểm soát $XY = Z^2$, và có những cây khác cho những điều khiển này không? Cuối cùng, làm thế nào để tìm ra các phép biến đổi $T_1$, $T_2$, $T_3$, cho phép người ta xây dựng cây gen cho xe đạp Pythagore?

Việc xây dựng cây gia phả để kiểm soát $XY = Z^2$ của chúng tôi liên quan trực tiếp đến thuật toán Euclide và dường như khá có động lực, điều này không thể nói về điều khiển $X^2 + Y^2 = Z^2$. Tuy nhiên, có một mối liên hệ giữa các bộ phận này giúp biện minh cho những nỗ lực thực hiện cho một trong số họ những gì đã được thực hiện cho bộ phận kia. Thật vậy, chúng ta hãy viết điều khiển $X^2 + Y^2 = Z^2$ dưới dạng $Z^2 - X^2 = Y^2$ và phân tích vế trái: $(Z - X)(Z + X) = Y^2$. Sau khi thực hiện thay thế $U = Z - X$, $V = Z + X$, $W = Y$, chúng ta đạt được mức kiểm soát $UV = W^2$. Vì vậy, có một sự thay thế chuyển điều khiển $X^2 + Y^2 = Z^2$ sang điều khiển $XY = Z^2$.

Ngoài ra còn có mục tiêu là một loạt điều khiển có thể được thay thế, chuyển đổi chúng thành $XY = Z^2$. Các biện pháp kiểm soát như vậy sẽ là $X^2 + Y^2 = 2Z^2$ và $X^2 + 3Y^2 = Z^2$. Bạn cũng có thể thử xây dựng cây phả hệ cho các phòng ban này.

Cần phải nói thêm về một bộ điều khiển thay thế nữa - bộ điều khiển Markov:
$$X^2 + Y^2 + Z^2 = 3XYZ.$$

Nó đã có một thuộc tính vốn có của chúng ta - tất cả lời giải của nó, ngoại trừ hai thuộc tính rất thấp (1, 1, 1) và (2, 1, 1), được tổ chức thành cây gen. Điều này được mô tả chi tiết trong bài báo phóng đại của M. G. Kerin («Kvant», 1985, No. 4, p. 13). Cây này khá giống với cây gia phả để quản lý $XY = Z^2$. Có mối liên hệ nào giữa các điều khiển này không? Những điều khiển nào khác có thuộc tính tương tự?

Vì vậy, có điều gì đó khác để suy nghĩ ở đây.
