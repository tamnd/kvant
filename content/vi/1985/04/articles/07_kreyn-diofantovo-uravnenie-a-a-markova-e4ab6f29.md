---
id: 1985-4-kreyn-diofantovo-uravnenie-a-a-markova-e4ab6f29
issue: kvant_1985_4
year: 1985
number: "4"
title: Phương trình Diophantine của A. A. Markov
authors:
  - Крейн М. Г.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 15
page_last: 18
page_labels: 13-16
tag: ZV53
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 02410f8385d7debb2eb539adff9fb30daf10ece2e9ac17612607005ff278a8ad
prompt_sha256: draft-1
translated_from: content/ru/1985/04/articles/07_kreyn-diofantovo-uravnenie-a-a-markova-e4ab6f29.md
source_content_sha256: 8a14d7184dc4f8ed2f7488d25436257a3fbbe05c5ae92d1af5a72537d0047f62
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 13⟧

Phương trình Diophantine
A. A. Markova

Thành viên tương ứng của Viện Hàn lâm Khoa học Liên Xô M. G. KERIN

Bài viết này kể câu chuyện về một phương trình với số chẵn và cho kết quả lời giải của nó. Lời giải chỉ sử dụng các tính chất đơn giản nhất của số và định lý Vieta cho tam thức bình phương, do đó có thể sử dụng phép toán tròn một. Nó dựa trên loạt bài bài toán “để chứng minh”, phần phân tích mà chúng ta sẽ tạo thành chủ đề của một bài học toán. (Bằng chứng chi tiết có thể được tìm thấy ở cuối số tiếp theo của tạp chí.)

Năm 1879, tại Đại học St. Petersburg, một chàng trai trẻ 23 tuổi đã hoàn thành luận án thạc sĩ mang tên “Về dạng hình vuông nhị phân của định thức dương”. Nó giải quyết được những câu hỏi khó nhất trong lý thuyết số và xác định một hướng đi mới trong lý thuyết này. Tác giả của nó là học giả nổi tiếng tương lai Andrei Andreevich Markov (1856-1922).

Luận án dựa trên hai bài báo của ông xuất bản ở Đức vào năm 1879 và 1880 trên một trong những tạp chí toán học nổi tiếng nhất thế giới - "Mathematische Annalen". Mặc dù vậy, phải hơn 30 năm trôi qua, tác phẩm của Markov mới được “phát hiện” ở phương Tây. Năm 1913, nhà toán học vĩ đại người Đức Georg Frobenius (1849–1917) đã xuất bản một chủ đề có tựa đề “Về số Markov”. Trong lời nói đầu của nó, ông đã viết rằng những câu hỏi về thực tế là nghiên cứu của A. A. Markov là “cực kỳ có thể thay thế được và quan trọng”, chúng dường như vẫn còn ít được biết đến. G. Frobenius giải thích sự phức tạp trong cách trình bày của họ (A. A. Markov đã sử dụng một cách có hệ thống bộ máy phân số liên tục, vốn không được ưa chuộng vào thời điểm đó trong những vấn đề này)*.

Tất nhiên, bài viết này không nhằm mục đích đưa ra ít nhất một số ý tưởng về nghiên cứu toàn cầu của A. A. Markov. Nhưng thực tế là trong các công trình của mình, A. A. Markov đã bất ngờ đi đến một phương trình Diophantine phụ (bây giờ được gọi là chúng ta có nó), có dạng

$$x^2 + y^2 + z^2 = 3xyz.$$

Và bây giờ - một cảm giác! A. A. Markov đã thu được mô tả của tất cả lời giải của phương trình (1), chỉ sử dụng các phương tiện toán học phổ thông (trong số đó, định lý Vieta cho tam thức bậc hai đóng một vai trò). Nhưng trước khi chúng ta phân tích lời giải của phương trình (1), cần nói một vài từ nói chung:

Về phương trình Diophantine

Như đã biết, phương trình Diophantine cho biến số nguyên $x, y, ..., w$ là phương trình có thể rút gọn về dạng

$$P(x, y, ..., w) = 0,$$

trong đó $P$ là một số đa thức trong các biến được chỉ định có hệ số nguyên.

Đôi khi những câu hỏi tương đối đơn giản sẽ dẫn đến phương trình Diophantine. Ví dụ: giải câu hỏi làm thế nào có thể chia số lượng $n$ kopecks thành các đồng xu có mệnh giá 1, 2, 3 và 5 kopecks, chúng ta đi đến phương trình Diophantine:

$$x + 2y + 3z + 5w = n^*$$.

Rõ ràng, ở Babylon cổ đại, bài toán được sinh ra để xây dựng một tam giác vuông có các cạnh tỉ lệ theo cặp. Khả năng tương xứng của các cạnh có nghĩa là người ta sẽ tìm thấy một thang đo trong đó các cạnh huyền và cạnh huyền sẽ được biểu thị bằng các số tự nhiên $x, y$ và $z$, nhưng sau đó

$$*) О непрерывных (или целых) дробях можно прочитать в «Кванте», 1983, № 5, c. 16 и № 6, c. 26.
**) О решении этого уравнения см. «Кванте», 1984, № 5, c. 11.$$

⟦folio 14⟧

$$x^2 + y^2 = z^2.$$

Do đó, bài toán của Babylon bao gồm bài toán xây dựng tất cả các bộ ba số tự nhiên $x, y, z$ thỏa mãn phương trình trước đó. Những người theo trường phái Pythagore đã tìm ra cách xây dựng tất cả lời giải của nó. Nhưng có lẽ phương pháp này thậm chí còn được tìm thấy sớm hơn ở Babylon và Ấn Độ. Bằng cách này hay cách khác, các phương trình lời giải $(x, y, z)$ $x^2 + y^2 = z^2$ thường được gọi là *bộ ba Pythagore*).

Bài toán về việc tìm tất cả lời giải Ngay cả một phương trình Diophantine có vẻ đơn giản cũng thường phức tạp. Được biết, không có một cách thống nhất (thuật toán tổng quát) nào để tìm hiểu ngay cả khi phương trình Diophantine có lời giải là số nguyên hay không **). Việc tìm kiếm lời giải các phương trình Diophantine cụ thể vẫn tiếp tục cho đến ngày nay; ở đây, với sự trợ giúp của bộ máy phức tạp của hình học đại số hiện đại, những điều kiện quan trọng đã được đưa ra trong những năm gần đây ***). Tuy nhiên, điều thú vị hơn đối với chúng ta là phương trình Markov (1) được giải một cách cơ bản - hãy quay lại nó.

**Cây phả hệ của phương trình Markov**

Bộ ba số nguyên thứ tự $(a, b, c)$ được gọi là *giải của phương trình Diophantine với các biến $x, y, z$ nếu phương trình này trở thành một đẳng thức số thực sự là $x=a, y=b, z=c$. Chúng ta sẽ gọi các số $a, b, c$ lời giải $(a, b, c)$ *tọa độ* lời giải. Đối với phương trình Markov (1), chúng ta đồng ý chỉ xem xét những lời giải không có tọa độ bằng 0, nói cách khác, chúng ta sẽ loại trừ bộ ba $(0, 0, 0)$ khỏi lời giải (dễ dàng thấy rằng nếu một trong các tọa độ lời giải của phương trình (1) bằng 0 thì các tọa độ còn lại lời giải bằng 0).

Vế trái của (1) dương với mọi lời giải $(a, b, c)$, do đó tất cả $a, b, c$ đều dương hoặc hai

*) Về bộ ba Pythagore và khoảng lời giải của một số phương trình Diophantine khác, xem: A. O. Gelfond. Lời giải Phương trình số nguyên, tái bản lần thứ 4. - M.: Nauka, 1973. O. Ore. Lời mời đến với lý thuyết số. - M.: Nauka, 1980. - (Series: Thư viện *Lượng tử*).
**) Xem *Kvant*, 1970, số 7, tr. 39.
***) Xem *Kvant*, 1983, số 3, tr. 19.

trong số đó là tiêu cực. Trong trường hợp sau, việc chuyển đổi từ $(a, b, c)$ sang $(|a|, |b|, |c|)$ dẫn đến lời giải của phương trình (1) có tọa độ dương. Ngược lại, nếu tất cả tọa độ lời giải $(a, b, c)$ đều dương thì bằng cách thay đổi dấu của hai tọa độ bất kỳ, chúng ta lại thu được lời giải. Do đó, trong phần tiếp theo, không mất tính tổng quát, chúng ta sẽ chỉ xét lời giải $(a, b, c)$ với tọa độ dương.

Từ phương trình đối xứng (1), suy ra rằng nếu $(a, b, c)$ - lời giải của phương trình (1), thì nghiệm sẽ là:

$$(a, b, c), (c, a, b), (b, c, a),$$
$$(b, a, c), (a, c, b), (c, b, a),$$

nghĩa là, cùng với $(a, b, c)$, các nghiệm sẽ là tất cả các bộ ba thu được bằng các hoán vị khác nhau của tọa độ của một lời giải đã cho.

Theo quan điểm này, chúng ta có thể đồng ý rằng tất cả sáu phương trình lời giải Markov, thu được từ nhau bằng hoán vị, đều được coi là một nghiệm, nghĩa là, chúng ta giả sử rằng đối với lời giải chỉ tồn tại các giá trị của tọa độ chứ không phải thứ tự của chúng.

Phương trình Markov có lời giải (1, 1, 1) hiển nhiên. Bây giờ chúng ta sẽ tìm hiểu làm thế nào, khi biết một số lời giải, chúng ta có thể tìm thấy lời giải khác. Nếu $(a, b, c)$ - lời giải phương trình Markov, thì chúng ta có thể nói rằng a là nghiệm của phương trình bậc hai

$$\Phi_a(x) = x^2 + b^2 + c^2 - 3bcx = 0.$$

Nhưng theo định lý Vieta thì phương trình này sẽ có thêm một nghiệm $x=a'$, sao cho

$$a + a' = 3bc, \quad aa' = b^2 + c^2.$$

Rõ ràng, $a' > 0$ và $(a', b, c)$ cũng là nghiệm của phương trình (1). Nó được gọi là *giải lân cận dọc theo tọa độ a*. Rõ ràng, nếu $(a', b, c)$ là lân cận của lời giải đối với $(a, b, c)$, thì $(a, b, c)$ là nghiệm lân cận của $(a', b, c)$ dọc theo tọa độ $a'$.

Tương tự, lời giải, lân cận tại tọa độ 1 lời giải $(1, 1, 1)$, được giới thiệu. Để làm được điều này bạn cần giải phương trình bậc hai

⟦folio 15⟧

$$x^2 + 1^2 + 1^2 - 3 \cdot 1 \cdot 1 \cdot x = 0.$$

Ngoài nghiệm $x=1$, phương trình này còn có nghiệm $x=2$. Do đó, thu được lời giải (2, 1, 1) khác.
Trong phần tiếp theo, lời giải (1, 1, 1) và (2, 1, 1) sẽ đóng một vai trò quan trọng. Chúng ta hãy gọi họ, theo Markov, là số ít.

Số ít lời giải được phân biệt với tập hợp tất cả lời giải bởi thuộc tính sau.

Bài toán 1. Nếu hai tọa độ của phương trình lời giải $(a, b, c)$ Markov bằng nhau, thì trong trường hợp này và chỉ trường hợp này lời giải là số ít. Chứng minh điều đó.

Số ít đầu tiên lời giải (1, 1, 1) chỉ có một hàng xóm lời giải. Số ít thứ hai lời giải có ​​hai lân cận: một trong số chúng là (1, 1, 1), số còn lại (láng giềng dọc theo tọa độ 1), được lấy từ phương trình

$$2^2 + y^2 + 1^2 = 3 \cdot 2 \cdot y \cdot 1$$

và có dạng (2, 5, 1). Lần lượt, lời giải (2, 5, 1) có ba hàng xóm: một, tất nhiên (2, 1, 1) và hai hàng xóm mới - (13, 5, 1) và (2, 5, 29). Nói chung, mọi lời giải $(a, b, c)$ không số ít tạo ra ba cái lân cận

$$(a', b, c), (a, b', c), (a, b, c')$$

ở đâu (so sánh với (2))

$$a' = 3bc - a, b' = 3ac - b, c' = 3ab - c.$$

Bài toán 2. Nếu lời giải $(a, b, c)$ không số ít thì một trong các lân cận của nó lời giải có tọa độ tối đa nhỏ hơn và hai tọa độ còn lại có tọa độ tối đa lớn hơn. Chứng minh điều đó.

Định lý Markov. Bất kỳ lời giải nào của phương trình (1) đều được chứa bởi một số nguyên lân cận lời giải với nghiệm số ít (1, 1, 1).

Bằng chứng. Cho $(a, b, c)$ - lời giải là một phương trình Markov khác số ít. Sau đó, nó có một láng giềng lời giải $(a_1, b_1, c_1)$ với tọa độ tối đa nhỏ hơn (bài toán 2). Nếu lời giải này cũng không phải là số ít thì nó sẽ tạo ra lời giải $(a_2, b_2, c_2)$ với tọa độ tối đa nhỏ hơn, v.v. Vì không thể chỉ định một dãy số tự nhiên giảm vô hạn nên quá trình này phải kết thúc khi chúng ta đến một số lời giải $(a_n, b_n, c_n)$, có tọa độ bằng nhau, tức là (bài toán 1) số ít. Nếu là (1, 1, 1) thì định lý đã được chứng minh, nhưng nếu là lời giải (2, 1, 1), thì vẫn phải nhớ rằng nghiệm lân cận của (2, 1, 1) dọc theo tọa độ 2 sẽ là (1, 1, 1). Định lý đã được chứng minh.

Từ định lý Markov, suy ra rằng, bắt đầu từ số ít lời giải (1, 1, 1) và lần lượt chuyển sang các nghiệm lân cận có tọa độ cực đại lớn, chúng ta thu được tất cả các phương trình lời giải Markov. Thao tác này tạo ra bảng sau - cây gia phả (xem hình). Bảng này cho phép, đối với một hành động số hữu hạn $N (\geqslant 1)$ nhất định, tìm tất cả các phương trình lời giải Markov có tọa độ không vượt quá $N$.

Bài toán 3. Chứng minh rằng với mỗi lời giải của phương trình Markov thì tọa độ là cặp nguyên tố cùng nhau.

Phương trình Markov đặc biệt

Chúng ta hãy đặt ra câu hỏi sau đây, thoạt nhìn có vẻ như đối với các quốc gia. Nếu tổng bình phương của ba số tự nhiên được chia cho tích của chúng thì thương có thể bằng bao nhiêu?

Câu hỏi này tương đương với câu hỏi sau: $k$ Diophantines tự nhiên nào thực hiện phương trình

$$X^2 + Y^2 + Z^2 = kXYZ$$

(3)

⟦folio 16⟧

có số khác không lời giải? Tại $k=3$ phương trình này trùng với phương trình Markov. Dễ dàng nhận thấy rằng khi $k=1$ phương trình (3) có lời giải, ví dụ (3, 3, 3). Sau khi phân tích phương trình (3), Hurwitz và Frobenus đi đến một kết quả đáng kinh ngạc: phương trình (3) có lời giải chỉ khi $k=3$ Và $k=1$. Kết quả này cũng có thể thu được bằng các phương pháp cơ bản.

Hãy bắt đầu với trường hợp $k=1$. Trong trường hợp này, hóa ra việc tìm kiếm lời giải của phương trình (3) cho $k=1$ trùng khớp với việc tìm kiếm lời giải của phương trình Markov.

Bài toán 4. Cho $A, B, C$ là số tự nhiên. Khi đó, phần còn lại của việc chia số $A^2+B^2+C^2$ cho 3 bằng số các số thứ Tư $A, B, C$ không chia hết cho 3, nếu có ít hơn ba số đó và bằng 0 trong các trường hợp khác. Chứng minh điều đó.

Bài toán 5. Tất cả các phương trình lời giải $(A, B, C)$

$$X^2+Y^2+Z^2=XYZ$$

thu được bằng công thức

$$A=3a, B=3b, C=3c,$$

trong đó $(a, b, c)$ là phương trình lời giải Markov tùy ý

$$x^2+y^2+z^2=3xyz.$$

Chứng minh điều đó.

Chúng ta hãy chuyển sang trường hợp $k=2$.

Bài toán 6. Cho $A, B, C$ là số tự nhiên. Khi đó phần dư của phép chia số $A^2+B^2+C^2$ cho 4 bằng số các số không chia của phương tiện $A, B, C$. Chứng minh điều đó.

Bài toán 7. Chứng minh rằng phương trình (3) không có lời giải cho $k=2$.

Định lý. Phương trình (3) có lời giải khác 0 chỉ cho $k=1$ và $k=3$.

Bằng chứng. Với $k=1$, lời giải phù hợp với Bài toán 5. Đối với $k=2$, phương trình (3) không có lời giải do bài toán 7. Vẫn còn phải xem xét trường hợp $k>3$.

Giả sử rằng đối với một số phương trình $k>3$ (3) có lời giải $(a, b, c)$. Hãy để chúng tôi chỉ ra rằng tọa độ $a, b, c$ của lời giải này là riêng biệt theo từng cặp. Ví dụ: đặt $b=c$; thì $a^2=kab^2-2b^2=(ka-2)b^2$, nên $a=bd$, trong đó $d$ là số nguyên. Do đó $b^2d^2=(kbd-2)b^2$, $d^2=kbd-2$, $2=d(kb-d)$. Do đó, 2 chia hết cho $d$ và do đó, $d=1$ hoặc 2. Trong cả hai trường hợp, $kb=3$, điều này mâu thuẫn với điều kiện $k>3$.

Vì vậy, đối với bất kỳ lời giải nào của phương trình (3) tại $k>3$ thì tọa độ sẽ khác nhau theo từng cặp. Không có giới hạn, chúng ta thường có thể giả sử rằng $a>b>c$. Đối với lời giải $(a, b, c)$ sử dụng tam thức bậc hai

$$\Psi_a(x)=x^2+b^2+c^2-kxbc$$

tạo thành một hàng xóm tại tọa độ $a$ lời giải $(a', b, c)$. Bởi vì

$$\Psi_a(b)=2b^2+c^2-kb^2c<3b^2-kb^2<0,$$

ta thấy rằng $b$ nằm giữa các nghiệm $a$ và $a'$ của đa thức $\Psi_a(x)$, tức là $a>b>a'$. Do đó, lời giải $(a', b, c)$ có tọa độ tối đa nhỏ hơn tọa độ tối đa là lời giải $(a, b, c)$. Vì vậy, với mỗi lời giải $(a, b, c)$ chúng ta có thể xây dựng lời giải $(a_1, b_1, c_1)$ với tọa độ tối đa nhỏ hơn. Việc xây dựng này có thể được lặp lại, thu được lời giải $(a_2, b_2, c_2)$ với tọa độ tối đa thậm chí còn nhỏ hơn. Vì mỗi tọa độ lời giải khác nhau theo từng cặp nên quá trình này có thể được tiếp tục vô thời hạn và thu được chuỗi vô hạn lời giải của phương trình (3) với tọa độ tối đa ngày càng nhỏ hơn. Nhưng điều này là không thể vì tọa độ là số tự nhiên. Định lý đã được chứng minh.

Kết quả. Đối với bất kỳ phương trình lời giải $(a, b, c)$ Markov nào, các số $a, b, c$ là cặp số nguyên tố cùng nhau.

Bằng chứng. Ví dụ: nếu $a$ và $b$ có ước chung $d$ ($>1$), thì theo phương trình (1), số $d$ cũng sẽ là ước số của số $c$. Do đó, tồn tại các số tự nhiên $X, Y, Z$ cũng bằng $a=dX, b=dY, c=dZ$ và theo (1) sẽ có $X^2+Y^2+Z^2=3dXYZ$, điều này mâu thuẫn với định lý vừa chứng minh.

Tổng quát hóa trực tiếp phương trình Markov cho trường hợp biến $n$ ($n \geqslant 3$) là phương trình

$$x_1^2+x_2^2+\dots+x_n^2=nx_1x_2\dots x_n.$$

Dễ dàng nhận thấy rằng một số mệnh đề trên áp dụng cho trường hợp này (có một lời giải $x_1=1, x_2=1, \dots, x_n=1$ số ít, với mỗi lời giải đều có các lời giải lân cận, v.v.). Tuy nhiên, tác giả không biết rằng lý thuyết trạm biến áp hoàn chỉnh của phương trình (7) đã được trình bày ở đâu đó. Việc tìm kiếm một lý thuyết như vậy có thể trở thành nền tảng của một nghiên cứu độc lập nhỏ.
