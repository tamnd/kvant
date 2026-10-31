---
id: 1975-8-yaglom-o-zadache-rado-9b3c83f2
issue: kvant_1975_8
year: 1975
number: "8"
title: Ôi bài toán Rado
authors:
  - Яглом И. М.
rubric: osnovnye-stati
page_first: 42
page_last: 47
page_labels: 40-45
tag: OZQ8
lang: vi
source: kvant_digital
extraction: publisher
content_sha256: 7e0898ef8f6acf2c06b37480faa7eb909de4302844127d592263a23159b47c8a
prompt_sha256: draft-1
translated_from: content/ru/1975/08/articles/08_yaglom-o-zadache-rado-9b3c83f2.md
source_content_sha256: d827a06e94f6300ac7e7b1c5142857d314ffa5be328ae38e4df959920b951498
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦figure⟧

## Ôi bài toán Rado

Năm «Kvant» số 5 năm 1975, trong phần “Sách vấn đề lượng tử”, bài toán M321 (tác giả A.V. Brailov) đã được xuất bản. Chúng ta hãy nhớ lại tình trạng của nó.

Tồn tại một bảng hình chữ nhật có diện tích 1. Chứng minh rằng với bất kỳ $\eps\gt0$ nào, người ta có thể chỉ định một hệ khăn ăn hình chữ nhật phủ lên bảng này (các cạnh của khăn ăn song song với các cạnh của bàn), sao cho bất kỳ hệ thống con nào của nó bao gồm các khăn ăn không chồng lên nhau đều có diện tích nhỏ hơn $\eps$.

Ghi chú này nói về các tùy chọn khác nhau bài toán cho "hệ thống khăn ăn không chồng chéo". Một số trong số chúng có cả một lịch sử, một số khác khá đơn giản và được giải quyết với sự trợ giúp của một ý tưởng, giống như “Olympiad” thông thường bài toán.

Rõ ràng, một ví dụ giả thuyết (và chỉ liên quan đến toán học chứ không phải sinh học) về các sinh vật sống mà thế giới bên ngoài là mặt phẳng hai chiều chứ không phải không gian ba chiều, thuộc về nhà tự nhiên học và toán học nổi tiếng người Đức G. Helmholtz: đây là những con nhện nước - "nhện nước", chuyển động trượt dọc theo bề mặt nước có thể được nhìn thấy trong bất kỳ vùng nước tù đọng nào. “Những con nhện nước” của Helmholtz không thể tưởng tượng được thế giới “ba chiều” mà chúng ta quen thuộc, cũng như con người không thể tưởng tượng được “không gian bốn chiều”.

Chúng ta sẽ bắt đầu với một thế giới bên ngoài thậm chí còn nguyên thủy hơn thế giới của nhện nước: với sự tương tự một chiều của bài toán M321. Ngay cả trong một phiên bản “nhẹ nhàng” như vậy, nó không hề trở nên vô nghĩa.

### Cắt lớp phủ

Bây giờ chúng ta có cả "bàn" và "khăn ăn" - không phải hình chữ nhật mà là các đoạn thẳng. Chúng tôi quan tâm đến điều này

Tuyên bố. Cho một đoạn $o$ có độ dài 1 (“bảng”) và một số $\eps\gt0$. Sau đó, chúng ta có thể chỉ định một hệ thống các phân đoạn (“khăn ăn”) bao phủ “bảng” $o$ sao cho bất kỳ hệ thống con nào của các phân đoạn không chồng chéo (“khăn ăn” không chồng chéo) có tổng chiều dài nhỏ hơn $\eps$.

Tuyên bố này đúng hay sai?

Trước tiên chúng ta hãy thử nghiệm các hệ thống “khăn ăn” đơn giản nhất. Trong Hình 1, *a* “cái bàn” được phủ ba “khăn ăn” có chiều dài $\dfrac13$. Từ đó, chúng ta có thể chọn một hệ thống con gồm hai “khăn ăn” không chồng lên nhau với tổng chiều dài là $\dfrac23$. (Tất nhiên, bạn có thể chọn một hệ thống con từ một "khăn ăn", nhưng độ dài của hệ thống con đó ít hơn.) Vì vậy, nếu $\eps\gt\dfrac23$, thì tuyên bố của chúng tôi là đúng: chúng tôi đã chỉ ra một hệ thống các phân đoạn sao cho bất kỳ hệ thống con nào của nó bao gồm các phân đoạn rời rạc có tổng chiều dài không lớn hơn $\dfrac23$, tức là nhỏ hơn $\eps$.

Bài tập 1. Chứng minh rằng với $\eps\gt\dfrac12$ mệnh đề cũng đúng. (Tạo lớp phủ tương ứng của phần “bàn” $o$ với các đoạn “khăn ăn” nhỏ hơn.)

Rõ ràng là mỗi ví dụ về hệ thống phân đoạn $K$ đảm bảo tính hợp lệ của tuyên bố của chúng tôi chỉ cho $\eps\gt d_k$, trong đó $d_k$ là một số dương tùy thuộc vào hệ thống này $K$. Vì vậy, đối với ví dụ trong Hình 1, *a* $d_k=\dfrac23$; trong Hình 1, *b* $d_k=\dfrac35$. Nói chung, $d_k$ là độ dài lớn nhất của hệ thống con $K'\subset K$, bao gồm các phân đoạn rời rạc. Rõ ràng là $\eps$ càng nhỏ thì việc xây dựng một ví dụ càng khó khăn hơn. Có thể xảy ra trường hợp đối với $\eps$ lớn hơn một số $\eps$ Tuyên bố của chúng tôi là đúng, nhưng đối với $\eps$ nhỏ hơn thì điều đó không còn đúng nữa. Hãy để chúng tôi chứng minh rằng đối với phiên bản một chiều của bài toán thì điều này đúng như vậy.

Tại $\eps=\dfrac13$ Câu khẳng định sai.

Nói cách khác, *không có hệ thống "khăn ăn" nào có thể đóng vai trò là ví dụ bắt buộc cho $\eps=\dfrac13$, tức là bất kỳ hệ thống "khăn ăn" nào cũng chứa một hệ thống con gồm các "khăn ăn" không chồng chéo bao phủ một phần của "bàn" $o$ có chiều dài $\dfrac13$* $\Big($ trở lên $\dfrac13\Big)$.

⟦figure⟧
Cơm. 1

⟦figure⟧
Cơm. 2

Cho một hệ thống các đoạn $K$ bao phủ đoạn $o$ có độ dài 1. Chúng ta hãy chọn đoạn lớn nhất từ ​​$K$ và biểu thị nó là $i_1$. Bây giờ chúng ta hãy xóa khỏi hệ thống $K$ tất cả các đoạn của lớp phủ giao nhau với đoạn đã chọn $i_1$ (chúng bao gồm một đoạn có độ dài không quá $3|i_1|$, trong đó $|i|$ là độ dài của đoạn $i$). Từ các phân đoạn phủ sóng còn lại, chúng tôi lại chọn phân đoạn lớn nhất (chúng tôi ký hiệu là $i_2$) và loại bỏ tất cả các phân đoạn giao nhau với $i_2$ (chúng bao gồm một đoạn có độ dài không quá $3|i_2|$), v.v., cho đến khi chúng tôi sử dụng hết tất cả các phân đoạn phủ sóng. Hệ thống con được chọn gồm các đoạn rời rạc $i_1$, $i_2$, $\ldots$ sao cho $$
3|i_1|+3|i_2|+\ldots\ge1,
$$
vì tổng các đoạn có độ dài $3|i_1|$, $3|i_2|$, $\ldots$ bao trùm toàn bộ hệ thống đã cho $K$ và do đó, toàn bộ đoạn $o$ có độ dài 1. Do đó, tổng độ dài $|i_1|+|i_2|+\ldots$ không nhỏ hơn $\dfrac13$.

Hình 2 cho thấy quy trình chọn hệ thống con $\{i_1,i_2,i_3\}$ như vậy cho hệ thống gồm bảy phân đoạn.

Bài tập 2.

1. Chứng minh rằng từ bất kỳ hệ “khăn ăn” nào che phủ “bàn”, người ta có thể chọn một hệ thống con gồm các “khăn ăn” cũng bao phủ “bàn” và sao cho không có điểm nào của “bàn” được bao phủ bởi nhiều hơn hai “khăn ăn”.
2. Chứng minh rằng với $\eps=\dfrac12$ mệnh đề là sai.

Bài tập 3. Chứng minh rằng nếu “cái bàn” vẫn là một đoạn có độ dài 1 và “khăn ăn” cũng có thể là “holey”, tức là mỗi “khăn ăn” có thể bao gồm một hoặc nhiều đoạn, thì Mệnh đề ở đầu đoạn này đúng với mọi $\eps\gt0$.

Bằng cách giải bài tập 1 và 2, bạn sẽ chứng minh được sự thật sau:

Định lý 1. *Cho “cái bàn” và “khăn ăn” là các đoạn thẳng, chiều dài của “cái bàn” bằng $1$.*

1. Từ bất kỳ hệ thống “khăn ăn” nào bao phủ “bàn”, người ta có thể chọn một hệ thống con gồm các “khăn ăn” không chồng lên nhau với tổng chiều dài ít nhất là $\dfrac12$.
2. Nếu $\eps\gt\dfrac12$, thì luôn có thể chỉ định một hệ thống "khăn ăn" sao cho bất kỳ hệ thống con nào của "khăn ăn" không chồng chéo của nó có chiều dài nhỏ hơn $\eps$.

Nói cách khác, *Phát biểu đúng với $\eps\gt\dfrac12$ và sai với* $\eps\le\dfrac12$.

Bài tập 4. Chứng minh định lý tương tự cho “cái bàn” - đường tròn có chiều dài 1, và “khăn ăn” - các cung của đường tròn này.

### Khăn ăn vuông

Năm 1928, nhà toán học nổi tiếng người Hungary Tibor Rado (T. Radó) đã báo cáo trong một bức thư gửi biên tập viên tạp chí toán học hàng đầu Ba Lan Fundamenta Mathematicae, người đứng đầu trường toán học Ba Lan, Wacław Sierpinski, rằng ông không thể giải được bài toán hình học có vẻ đơn giản bài toán liên quan đến lý thuyết hàm số nhiều biến. Sau khi phác thảo những cân nhắc và kết quả mà chúng tôi đã biết về việc bao phủ một phân khúc theo các phân đoạn, T. Rado đặt ra câu hỏi về việc thu được các ước tính tương tự cho “hai chiều” bài toán, trong đó “khăn ăn” là *hình vuông* (có kích thước khác nhau) và “bảng” chẳng hạn là *hình vuông* (hoặc *hình chữ nhật*) của khu vực 1 và các cạnh của khăn ăn song song với các cạnh của bàn (Hình 3).

⟦figure⟧
Cơm. 3

Vì vậy, sự khác biệt giữa bài toán của Rado và bài toán M321 (Brailov) chỉ ở dạng “khăn ăn”: trong M321 chúng có thể là bất kỳ hình chữ nhật nào, nhưng trong Rado, chúng chỉ có thể là hình vuông. Nhưng sự khác biệt “nhỏ” này, như thường lệ, đã thay đổi hoàn toàn vấn đề.

Phương pháp mà chúng tôi trích xuất một hệ thống con có độ dài ít nhất $\dfrac13$ từ hệ thống các đoạn bao phủ một đoạn có độ dài 1 cũng hoạt động trong trường hợp hai chiều. Với sự giúp đỡ của anh ấy, T. Rado đã chứng minh được sự thật này.

Định lý 2. *Từ bất kỳ lớp phủ nào của một “cái bàn” phẳng có diện tích 1 với những “khăn ăn” hình vuông, người ta có thể chọn một lớp phủ có những “khăn ăn” không chồng lên nhau có tổng diện tích không nhỏ hơn $\dfrac19$.*

Bài tập 5.

1. Chứng minh Định lý 2.
2. Hãy đưa ra một ví dụ chứng tỏ rằng trong công thức của Định lý 2, số $\dfrac19$ không thể thay thế bằng số $\dfrac14$.

Do đó, trong bài toán Rado (không giống bài toán Brailov) cũng tồn tại một giá trị tới hạn nào đó $\eps_0$ sao cho

tại $\eps\gt\eps_0$, đúng

Phát biểu 1. Chúng ta có thể chỉ định một ví dụ về hệ thống “khăn ăn” sao cho bất kỳ hệ thống con nào của “khăn ăn” không chồng lên nhau đều có tổng diện tích nhỏ hơn $\eps$,

và với $\eps\lt\eps_0$ điều đó đúng

Tuyên bố 2. Từ bất kỳ hệ thống “khăn ăn” nào, người ta có thể chọn một hệ thống con gồm các “khăn ăn” không chồng lên nhau với tổng diện tích ít nhất là $\eps$.

Tất nhiên, chúng ta luôn coi diện tích của “cái bàn” bằng 1.

T. Rado đã có thể chứng minh rằng với giá trị tới hạn $\eps_0$ thì các ước tính sau đây là đúng:
$$
\dfrac19\le\eps_0\le\dfrac14,\tag1
$$
nhưng tôi chắc chắn rằng thực tế nó là $\eps_0=\dfrac14$.

Ông đề nghị chứng minh sự bình đẳng này trong một lá thư gửi Waclaw Sierpinski.

Tuy nhiên, cả Sierpinski và các nhà toán học khác đều không thành công trong việc làm này, mặc dù nhiều người đã coi Rado với giá bài toán. Và chỉ 55 năm sau, vào năm 1973, người ta mới biết rõ lý do. Hóa ra giả thuyết của T. Rado đơn giản là sai! Một ghi chú giật gân của nhà toán học Hungary M. Ajtai đã xuất hiện trong Bản tin của Viện Hàn lâm Khoa học Ba Lan, trong đó nó chỉ ra khá đơn giản rằng với các hình vuông chỉ có hai kích thước khác nhau thì có thể bao phủ một hình chữ nhật có diện tích 1 theo cách mà không thể chọn từ chúng một hệ thống con rời rạc có diện tích $\dfrac14$ hoặc lớn hơn. Bây giờ người ta biết rằng $$
\dfrac1{8{,}6}\lt\eps_0\lt\dfrac14;\tag2
$$
bất đẳng thức bên trái là kết quả của các cải tiến liên tiếp của bất đẳng thức (1) bởi T. Rado, bất đẳng thức cuối cùng thuộc về nhà hình học Leningrad V. A. Zalgaller (rõ ràng, nó cũng không phải là cuối cùng, gần với kết quả “thô” của Định lý 2 hơn là ước tính giả thuyết của T. Rado).

Giải pháp đẹp và đơn giản nhất cho trường hợp đặc biệt bài toán Rado là khi tất cả các “khăn ăn” đều là hình vuông có cùng kích thước. Trong trường hợp này, giá trị tới hạn $\eps_0$ hóa ra thực sự bằng $\dfrac14$. Kết quả này đã được chứng minh vào năm 1940 bởi nhà toán học trẻ tuổi Leningrad A. S. Sokolin (và sau đó, độc lập với ông, bởi nhiều người khác và theo nhiều cách khác nhau).

### Định lý Blichfeld và kết quả Sokolin

Trước tiên chúng ta hãy chứng minh một định lý thú vị như vậy, một trong những biến thể của nó được dành cho trang bìa thứ hai «Kvant», 1973, số 10.

Định lý Blichfeld. *Nếu diện tích của một hình nằm trên một tờ giấy ca rô lớn hơn $n-1$ (trong đó $n$ là một số nguyên; cạnh của ô được lấy là $1$), thì hình này có thể được di chuyển bằng cách chuyển song song đến vị trí sao cho nó bao phủ ít nhất $n$ nút lưới. (Nút là điểm nơi các đường giao nhau, chia mặt phẳng thành các ô vuông.)*

Bằng chứng. Hãy cắt một tờ giấy ca rô thành các ô riêng biệt và xếp tất cả các ô có thể chứa ít nhất một phần của hình lại thành một chồng (từ Hình 4, *a* hãy chuyển sang Hình 4, *b*). Vì tổng diện tích của các phần trong hình của chúng ta lớn hơn $n-1$ nên một số điểm trong ngăn xếp sẽ được bao phủ bởi ít nhất $n$ phần của hình. Hãy dùng kim đâm vào một trong những điểm này; Sẽ có một vết thủng trên mỗi mảnh. Nếu bây giờ chúng ta đặt các ô xếp chồng lên nhau trên mặt phẳng theo cùng một thứ tự (tất nhiên, chúng ta giả sử rằng các ô được kết hợp bằng cách chuyển song song), thì các vết thủng sẽ được đặt “theo cách chính xác” - tại các đỉnh của lưới hình vuông mới có cạnh 1 (Hình 4, *c*). Vẫn phải di chuyển hình song song sao cho các lỗ này thẳng hàng với các nút (Hình 4, *d*).

⟦figure⟧
Cơm. 4

Bài tập 6. Chứng minh rằng nếu diện tích của một hình nhỏ hơn $n+1$ thì có thể di chuyển hình đó sao cho nó chạm không quá $n$ nút lưới ($n$ là số nguyên).

Sử dụng định lý Blichfeld, chúng ta thu được kết quả cần tìm.

Định lý 3. *Nếu một hệ các hình vuông bằng nhau có các cạnh song song bao phủ một hình có diện tích $S$ thì từ đó ta chọn được một hệ con gồm các hình vuông rời nhau (không có điểm chung bên trong) với nhau có tổng diện tích không nhỏ hơn $\dfrac S4$.*

Hình vuông bao gồm loại hình nào, ở đây, cũng như trong bài toán Rado, không quan trọng. Chỉ có khu vực của nó là quan trọng.

Bằng chứng. Chúng tôi đã cố tình xây dựng định lý hơi khác so với các định lý trước đó (diện tích của “bảng” bây giờ là $S$, không phải 1) để có thể chọn một đơn vị chiều dài khác. Chúng ta sẽ giả sử rằng chiều dài cạnh của mỗi “khăn ăn” bằng $\dfrac12$. Theo định lý Blichfeld, chúng ta có thể đặt hình của mình (diện tích $S$) trên giấy ca-rô (có cạnh là hình vuông 1) sao cho nó bao phủ các nút lưới $n\ge S$. Hãy để một “khăn ăn” che mỗi nút $n$ này. Rõ ràng là các “khăn ăn” đã chọn không thể chồng lên nhau và tổng diện tích của chúng bằng
$$
\dfrac14n\ge\dfrac S4.
$$
Định lý Sokolin đã được chứng minh.

### Tùy chọn bài toán Rado

Một nhà toán học nổi tiếng khác của Hungary, R. Rado, đã dành nhiều công sức nhất cho bài toán T. Rado. Vào các năm 1950, 1951, 1968, ông xuất bản ba bài báo chuyên sâu trên các tạp chí tiếng Anh: “Một số định lý về lớp phủ”, I-III, hoàn toàn lấy cảm hứng từ bài toán của T. Rado (vì vậy chúng tôi có lý do gọi bài báo là “O bài toán Rado” mà không ghi tên viết tắt). Chúng tôi chỉ liệt kê một số kết quả và vấn đề chưa được giải quyết liên quan đến vấn đề này.

Đối với bài toán về “bàn” hình tam giác $\mathrm{T}$ và “khăn ăn” hình tam giác tương tự (với các cạnh tương ứng) có thể thu được một số ước tính cho $\eps_0$; đặc biệt, để bao phủ $\mathrm{T}$ bằng các tam giác đồng dạng (và song song) (tương tự kết quả của Sokolin), chúng ta có thể chỉ định chính xác giá trị tới hạn $\eps_0$: $\eps_0=\dfrac16$. (Tất nhiên, trong bài toán này chúng ta luôn có thể nói về một “cái bàn” có hình dạng giống như một hình tam giác đều.)

Một số ước tính cũng được đưa ra cho các loại “khăn ăn” hình tròn (có cùng kích cỡ và khác nhau) và cho các loại “khăn ăn” khác tương tự nhau.

Bài tập 7. Chứng minh rằng nếu tất cả các “khăn ăn” đều giống với một hình $\Phi$ (mà chúng che phủ), thì tồn tại $\eps_0\gt0$ sao cho từ bất kỳ cách che phủ nào của một “bàn” diện tích 1, chúng ta có thể chọn một hệ thống con gồm các “khăn ăn” không chồng lên nhau với tổng diện tích ít nhất là $\eps_0$ ($\eps_0$, tất nhiên, phụ thuộc vào hình dạng $\Phi$).

Do đó, ở đây giá trị tới hạn $\eps_0$ luôn dương, trái ngược với bài toán Brailov, trong đó $\eps_0=0$ (“khăn ăn” là hình chữ nhật, không nhất thiết phải giống nhau!).

Các khái quát hóa khác bài toán Rado cũng đã được xem xét, chẳng hạn: tổng diện tích lớn nhất mà tổng diện tích của hai hệ thống con có thể có là bao nhiêu, trong đó các “khăn ăn” không chồng lên nhau là bao nhiêu; các ước tính cho sự tương tự về mặt không gian của bài toán Rado là gì - nhưng theo tất cả các hướng này, chỉ thu được một phần kết quả và ước tính khá sơ bộ.

Bài tập 8.

1. Chứng minh các bất đẳng thức tương tự trong không gian của bài toán Rado (về việc bao phủ một hình lập phương bằng các hình khối)
$$
\dfrac1{27}\lt\eps_0\le\dfrac18.\tag3
$$
2. Hãy xây dựng và chứng minh sự tương tự của Định lý 3 cho trường hợp này.

Bạn có thể tìm thấy một loạt bài toán gần với bài toán Rado (bao gồm cả những đề xuất ở trên dưới dạng bài tập), cùng với lời giải của chúng, trong các số mới nhất của loạt bài “Thư viện vòng tròn toán học” và “Thư viện trường Vật lý và Toán học”:

D. O. Shklyarsky và cộng sự, “Ước tính hình học và bài toán từ hình học tổ hợp”, M., Nauka, 1974, chu kỳ bài toán 3;

N. B. Vasiliev và cộng sự, “Các cuộc thi toán học; hình học”, M., Nauka, 1974, bài toán 7.6—7.9.
