---
id: 1986-5-shternberg-zachem-mikrokalkulyatoru-stek-1d61fc9c
issue: kvant_1986_5
year: 1986
number: "5"
title: Tại sao một máy tính vi mô cần một ngăn xếp?
authors:
  - Штернберг Л. Ф.
rubric: raznoe
rubric_sub: Разное
page_first: 41
page_last: 45
page_labels: 39-43
tag: ZTQD
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 5388cf41b7ce3ab72ced8e00bb803f338fe57ef777cff9989a95db6cc21a632e
prompt_sha256: draft-1
translated_from: content/ru/1986/05/articles/15_shternberg-zachem-mikrokalkulyatoru-stek-1d61fc9c.md
source_content_sha256: 80ad97faf14b92ff695791a15e6ec32374842e71cff91e5ffd7c2cffe7b03680
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 39⟧

Tại sao lại có một ngăn xếp máy tính vi mô

Ứng viên Khoa học Vật lý và Toán học
L. F. STERNBERG

Bài viết này chủ yếu dành cho học sinh lớp chín sẽ sử dụng máy tính vi mô có thể lập trình khi nghiên cứu những kiến ​​thức cơ bản của khóa học công nghệ thông tin. Tuy nhiên, bài viết sẽ hữu ích và hữu ích cho những người dùng máy tính khác (có thể lập trình hoặc không), vì nó nói về việc sử dụng ký hiệu - một ví dụ rất đơn giản có thể đơn giản hóa đáng kể việc tổ chức các phép tính.

Trên các máy tính lập trình "Điện tử" BZ-34, MK-56, MK-54 có một thiết bị thú vị - một ngăn xếp, bao gồm bốn đăng ký: X, Y, Z, T, thoạt nhìn được sử dụng theo một cách khá kỳ lạ. Lệnh ↑ nâng cao thông tin trên ngăn xếp - nội dung của T bị hủy, nội dung của Z được nhập vào T, nội dung của Y được nhập vào Z, nội dung của Y được nhập vào Y, vẫn còn trong X:

Lệnh F ↑ di chuyển nội dung của ngăn xếp theo hướng ngược lại, chỉ có nội dung của X là không bị hủy mà được chuyển sang T.

Có một lệnh XY trao đổi nội dung của X và Y và không ảnh hưởng đến các đăng ký còn lại. Nếu một trong các thao tác ↑ hoặc C không được thực hiện trước khi nhập số vào X hoặc gọi một số từ đăng ký, thì trước khi nhập giá trị mới vào X, ↑ sẽ tự động được thực hiện, tức là Z được gửi đến T, Y đến Z và X đến Y.

Khi thực hiện các thao tác trên hai số (ví dụ: X+Y hoặc X×Y), các số này được lấy từ Y và X, kết quả được gửi đến X và trọng số của ngăn xếp được dịch chuyển:

(hãy nhớ rằng đây không phải là cách hoạt động của X^Y). Nhưng khi thực hiện các phép tính trên một số (ví dụ: sin X), mọi thứ được thực hiện theo một cách rất khác: đối số được lấy từ X, kết quả vẫn ở X và không có gì khác di chuyển.

Tại sao ngăn xếp hoạt động theo cách này và nên sử dụng nó như thế nào? Hãy thử làm việc với ngăn xếp.

Hãy tính biểu thức a×b−c/d. Giả sử giá trị của a, b, c và d lần lượt nằm trong đăng ký a, b, c và d. Hãy để kết quả trung gian trên ngăn xếp mà không gửi nó vào bộ nhớ và tiếp tục tính toán - hãy xem kết quả của nó là gì.

Bảng 1

| № | Đội | Nội dung ngăn xếp | X | Y | Z | T |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 00 | IP một | a | | | | |
| 01 | IP b | b | a | | | |
| 02 | × | a×b | | | | |
| 03 | IP c | c | a×b | | | |
| 04 | IP d | d | c | a×b | | |
| 05 | ÷ | c/d | a×b | | | |
| 06 | — | a×b−c/d | | | | |

Có thể dễ dàng nhận thấy rằng chương trình này là chương trình tốt nhất trong số tất cả các chương trình có thể, vì không có một lệnh bổ sung nào trong đó: bạn cần gọi dữ liệu gốc từ quá trình đăng ký - có nghĩa là bạn không thể thực hiện nếu không có bốn lệnh UI và trong quá trình hoạt động, bạn cần phải thực thi,

⟦folio 40⟧

và không có gì khác trong chương trình. Có vẻ như ngăn xếp là một thứ thay thế: hãy thử làm việc với nó thêm một chút nữa, nhưng hãy dùng một biểu thức phức tạp hơn:

$$\frac{p - \frac{d}{(a+b)}}{(e+f)} \times (k+l).$$

Chúng tôi sẽ không phân phối các sổ đăng ký (chúng có thể được phân phối theo ý muốn).

Đội | Nội dung ngăn xếp | X | Y | Z | T | Bình luận
--- | --- | --- | --- | --- | --- | --- | ---

00 | IP một | một | | | | | Như đã học ở lớp một, chúng ta bắt đầu bằng các biểu thức trong ngoặc

01 | IP b | b | một | | | | Hãy để kết quả trung gian trên ngăn xếp: hãy xem nó kết thúc ở đâu.

02 | + | a+b | | | | | Và chúng ta sẽ để kết quả trung gian này vào ngăn xếp.

03 | IP e | e | a+b | | | |

04 | IP f | f | e | a+b | | |

05 | + | e+f | a+b | | | | Và chúng ta sẽ để kết quả trung gian này vào ngăn xếp.

06 | IP k | k | e+f | a+b | | |

07 | IP l | tôi | k | e+f | a+b | Ngăn xếp đã đạt đến giới hạn - bây giờ chúng ta sẽ mất a+b!

08 | + | k+l | e+f | a+b | a+b | Không, nó biến mất rồi! (a+b) được bảo toàn.

09* | F⊙ | e+f | a+b | a+b | k+l | Bây giờ chúng ta nên chia d cho (a+b), nhưng (a+b) ở đâu đó sâu và sâu. Với khó khăn, chúng tôi có thêm ba đội.

10* | F⊙ | a+b | a+b | k+l | e+f |

11* | F⊙ | a+b | k+l | e+f | a+b |

12 | IP d | d | a+b | k+l | e+f | Các giá trị d và a+b được gọi, nhưng chúng không có trong các đăng ký đó: chúng sẽ phải được hoán đổi.

13* | XY | a+b | d | k+l | e+f | Và một lần nữa chúng ta để lại kết quả trên ngăn xếp.

14 | -> | $\frac{d}{a+b}$ | k+l | e+f | e+f | Và một lần nữa chúng ta để lại kết quả trên ngăn xếp.

15 | IP p | p | $\frac{d}{a+b}$ | k+l | e+f |

16* | XY | $\frac{d}{a+b}$ | p | k+l | e+f | Một lần nữa các con số không theo đúng thứ tự và cần ít hơn.

17 | - | $p - \frac{d}{a+b}$ | k+l | e+f | e+f | Có vẻ như ngăn xếp đang hoạt động với chúng tôi: các kết quả trung gian cần thiết nằm ở những nơi bất tiện nhất - không rõ ngay chúng ở đâu và làm cách nào để lấy chúng.

18* | F⊙ | k+l | e+f | e+f | $p - \frac{d}{a+b}$ |

19* | F⊙ | e+f | e+f | $p - \frac{d}{a+b}$ | k+l |

20* | F⊙ | e+f | $p - \frac{d}{a+b}$ | k+l | e+f | Ít nhất thì tôi đã may mắn trong lần phẫu thuật vừa qua: những kết quả trung gian cần thiết đã ở ngay đó.

21 | ÷ | $\frac{(p - \frac{d}{a+b})}{e+f}$ | k+l | e+f | e+f |

22 | × | đáp số | e+f | e+f | e+f |

⟦folio 41⟧

trong chương trình). Rõ ràng, nếu chúng ta ghi nhớ kịp thời những kết quả này trong quá trình đăng ký bộ nhớ, chúng ta sẽ tính đến ít nhất một nửa trong số 8 lệnh bổ sung này. Có, miễn là bạn báo cáo kết quả hiện ở đâu trong ngăn xếp... Sẽ tốt hơn nếu không có ngăn xếp!

Nhưng trước khi chúng ta từ bỏ ngăn xếp, chúng ta hãy cố gắng hiểu tại sao trong chương trình đầu tiên, ngăn xếp lại “hoạt động” rất tốt, và ngược lại, trong chương trình thứ hai, nó lại “hành xử” tệ đến vậy. Để làm được điều này, chúng ta sẽ phải quay ngược lại 60 năm trước để đến thăm nhà toán học hữu ích Jan Łukasiewicz, người không hề có chút ý tưởng nào về máy tính vi mô, nhưng vẫn mô tả một thiết kế đáng chú ý, hiện đã được những người viết trình biên dịch cho máy tính biết đến và gọi là ký hiệu đảo ngược của người dùng.

Khi thực hiện các phép tính trên hai số, chúng ta đặt dấu giữa các số; phía trên một số - trước số này. Lukasiewicz đề nghị đặt dấu luôn trước các số (ký hiệu trực tiếp) hoặc luôn sau chúng (đảo ngược ký hiệu - đây là điều chúng ta sẽ quan tâm), tức là thay vì a-b viết ab - và cùng nhau lg a viết a lg.

Ấn tượng đầu tiên: "Vậy thì sao? Bạn có thể viết như thế này. Nó thật khó chịu và liên tục." Liên tục? Đúng. Nhưng nó có bất tiện không? Chúng ta hãy viết các biểu thức “(a+b)×c” và “a+b×c” ở dạng đảo ngược. Trong biểu thức đầu tiên, biểu thức a+b (bản thân nó phải được viết bằng ab+) và số c được nhân lên; ở câu thứ hai, a và biểu thức b×c (viết là bc×) được thêm vào. Vì thế:

Màu đỏ hiển thị những con số mà hoạt động ghi lại. Nhìn vào ký hiệu của người dùng: dấu ngoặc đơn đã biến mất - chúng không cần thiết, các thao tác được sắp xếp theo thứ tự thực hiện và bạn có thể quên đi thứ tự ưu tiên của các thao tác: các thao tác chỉ được thực hiện theo thứ tự - bên cạnh bên phải. (Giá như chúng ta được dạy những quy tắc số học này từ lớp một! Nó sẽ dễ dàng hơn biết bao!)

Bây giờ chúng ta hãy viết vào ký hiệu người dùng biểu thức mà chúng tôi đã biên soạn chương trình đầu tiên:

$$ab \times cd \div —$$

Bây giờ chỉ cần nhìn vào chương trình... và mọi thứ sẽ trở nên rõ ràng: chương trình của chúng tôi là một bản sao chính xác để sử dụng.

Ký hiệu người dùng cho biểu thức (*) là:

Bây giờ chúng ta hãy xem chương trình tính biểu thức này của chúng ta... và sẽ ngay lập tức hiểu rõ những gì chúng ta đã làm ở đó và tại sao ngăn xếp lại hoạt động không tốt. Nếu bạn viết một chương trình chính xác theo mục đã sử dụng, bạn sẽ nhận được chính xác 15 lệnh - không thêm một lệnh nào!

- Tuyệt vời! - người đọc sẽ nói. — Nhưng làm cách nào để lấy bản ghi người dùng từ bản ghi chung?

Rất đơn giản. Hãy viết biểu thức (*) theo ký hiệu tuyến tính hóa (nghĩa là không có công thức nhiều bước):

$$p - (d/(a+b))/(e+f) \times (k+l)$$

và áp dụng 3 quy tắc đơn giản:

1. Hãy viết ra các số và biến theo thứ tự được viết: pdabefkl.
2. Hãy viết ra các thao tác theo thứ tự chúng sẽ được thực hiện (với điều kiện là thao tác đầu tiên có thể được thực hiện luôn được thực hiện): +/-++/+×
3. Hãy chèn các phép tính ngay sau các số tương ứng.

Trên thực tế, không cần thiết phải tạo trước hồ sơ người dùng; bạn có thể làm điều này trong khi viết chương trình. Chúng tôi lập trình ví dụ tương tự, đọc iso- tuyến tính

⟦folio 42⟧

lối vào phòng tắm có ký hiệu (chỉ có dấu ngoặc không được đọc nhưng được tính đến; xem Bảng 3).
Chúng tôi đã thu được chương trình tối ưu: 8 cuộc gọi dữ liệu và 7 thao tác.
Và ngăn xếp “hoạt động” một cách hoàn hảo: hãy chú ý đến cách các kết quả trung gian “xoay chuyển” trong ngăn xếp, nhưng vào đúng thời điểm, chúng luôn ở đúng vị trí và theo thứ tự thích hợp. Có thể chứng minh về mặt toán học rằng điều này sẽ luôn xảy ra. (Chỉ có thao tác $X^Y$ hoạt động khác: thực tế là... nó chỉ được thực hiện không chính xác - tất cả các thao tác trên hai số đều có số đầu tiên trong $Y$, số thứ hai trong $X$, số này có số ngược lại; tất cả các phép toán trên hai số đều khác nhau)

| Ký tự có thể đọc được | Lý luận | Lệnh đã ghi | |
| :--- | :--- | :--- | :--- |
| $p$ | Các số và biến luôn được ghi vào ngăn xếp | IP $p$ | 1 |
| — | Thao tác không thể được thực hiện - không có gì liên quan đến nó! - chúng tôi bỏ qua. | | |
| $d$ | Biến nằm trên ngăn xếp. | IP $d$ | 2 |
| / | Thao tác này chưa sẵn sàng để thực thi—chúng ta bỏ qua nó. | | |
| $a$ | Biến nằm trên ngăn xếp. Chưa có thao tác nào có thể được thực hiện. | IP $a$ | 3 |
| + | Biến nằm trên ngăn xếp. Chưa có thao tác nào có thể được thực hiện. | | |
| $b$ | Trên ngăn xếp. | IP $b$ | 4 |
| | Cuối cùng chúng tôi đã tìm ra một phép toán mà cả hai số đều nằm trong ngăn xếp. Hãy làm điều đó. | + | 3 |
| | Chúng tôi có bất kỳ hoạt động đang chờ xử lý nào mà dữ liệu đã sẵn sàng không? Có - phân chia. Hãy thực hiện nó (những con số cần thiết ở đâu? - bạn không phải lo lắng - chỉ ở trên mặt đất). | ÷ | 2 |
| | Và một lần nữa, một thao tác đã xuất hiện để dữ liệu đã sẵn sàng - hãy thực hiện nó. | — | 1 |
| / | Không có gì liên quan đến những cái lớn - chúng tôi đọc biểu tượng tiếp theo và hoãn hoạt động - nó chưa sẵn sàng. | | |
| $e$ | Trên ngăn xếp. Hiện chưa có gì để làm. | IP $e$ | 2 |
| + | Hãy vượt qua - cô ấy chưa sẵn sàng. | | |
| $f$ | Trên ngăn xếp. | IP $f$ | 3 |
| | Các con số đã sẵn sàng để cộng - hãy thực hiện thôi. | + | 2 |
| | Dữ liệu đã sẵn sàng để phân chia - hãy thực hiện. | ÷ | 1 |
| × | Hãy bỏ qua - không có gì phải lo lắng | | |
| $k$ | Trên ngăn xếp. Đối với "×" và "+" dữ liệu vẫn chưa sẵn sàng. | IP $k$ | 2 |
| + | Trên ngăn xếp. Và bạn có thể làm “+” | IP $l$ | 3 |
| | Hãy thực hiện phép cộng. Mọi thứ đã sẵn sàng để nhân lên. | + | 2 |
| | Hãy thực hiện phép nhân. Kết thúc. | × | 1 |

Bảng 3

⟦folio 43⟧

chồng, cái này - không; vì vậy khi lập trình nó bằng phương pháp đã chỉ định, bạn sẽ phải viết $\vec{XY}$, $FX^Y$, $\vec{XY}F$ hoặc viết $e^{Y \times \ln X}$ cùng với $X^Y$ - thì mọi thứ sẽ ổn.)

Giờ đây, bạn đã rõ lý do tại sao khối lượng công việc lại như vậy và hóa ra là bạn thậm chí không cần phải theo dõi từng kết quả ở đâu tại mỗi thời điểm: vào đúng thời điểm, nó sẽ ở nơi cần thiết.

Nhưng... nếu chúng ta không có đủ 4 thanh ghi ngăn xếp thì sao? Sau đó, kết quả trung gian phải được ghi vào bộ nhớ. Nhưng làm thế nào chúng ta có thể xác định liệu chúng ta có đủ ngăn xếp hay không? Bạn có cần theo dõi tất cả các thay đổi của ngăn xếp không? Không, thực ra mọi thứ đã diễn ra suôn sẻ: hãy nhìn vào cột trong bảng không có tiêu đề; - có một số con số trong đó - chúng hiển thị số lượng đăng ký ngăn xếp đã được chiếm (bạn không cần phải ghi toàn bộ bảng ngăn xếp, nhưng bạn cần phải viết những con số này). Quy tắc điền vào cột rất đơn giản: lệnh PI nào thêm một, phép toán nào trên hai số sẽ giảm số trước đó đi một, phép toán trên một số không làm thay đổi số đó. Và nếu số 5 xuất hiện, thì tại thời điểm đó, trong lần “bơm” tiếp theo của ngăn xếp, một trong những kết quả trung gian sẽ bị mất.

Cuộc sống lúc đó thế nào? Không thể trả lời chi tiết câu hỏi này bằng cách gian lận các số liệu thống kê. Chúng tôi sẽ chỉ lưu ý rằng trong tình huống như vậy, bạn luôn có thể sử dụng đăng ký bộ nhớ, nhưng thường có thể sắp xếp lại công thức được sử dụng để tính toán để không xảy ra tràn ngăn xếp.

Tóm lại, chúng tôi lưu ý rằng việc sử dụng phép đảo ngược để ghi lại trọng lượng sẽ thuận tiện khi tổ chức các phép tính trên máy tính kỹ thuật (không lập trình được): nó được sử dụng để ngăn việc sao chép các kết quả đa sắc độ từ chỉ báo.

Về toán học dao động điều hòa
(Xem phần đầu ở trang 9)

vào mô hình sóng âm do I. Newot tạo ra: ở cấp độ cơ bản theo hướng truyền âm thanh, một hệ thống các trọng lượng dao động lớn, chính xác được kết nối bằng các lò xo nhỏ không có khối lượng được xem xét. Động năng của hệ thống này tập trung ở các quả nặng, còn thế năng được tích trữ trong các lò xo. Một hệ thống như vậy được gọi là hệ thống các bộ dao động ghép trên sơ cấp. Những hệ thống như vậy có thể được xem xét cả trên mặt phẳng và trong không gian.

Hệ thống dao động ghép đôi được mô hình hóa thuận tiện trong nhiều ngành cơ học và vật lý. Hơn nữa, một ngành khoa học rất đơn giản như vật lý hạt cơ bản sử dụng một trong những hệ thống dao động ghép đôi làm một trong những nền tảng của nó - một mô hình chân không vật lý. Từ quan điểm này, chân không có thể được coi là một nhạc cụ rất phức tạp, phản ứng với những rung động nhất định trước bất kỳ tác động bên ngoài nào.

Sử dụng diện tích...
(Xem phần đầu ở trang 16)

Bài tập

1. Cho một hình tam giác đều $ABC$ và một điểm $O$ bên trong nó; $A', B'$ và $C'$ lần lượt là hình chiếu của điểm này lên các độ cao $AA_1$, $BB_1$ và $CC_1$. Chứng minh rằng giá trị $AA' + BB' + CC'$ không phụ thuộc vào việc chọn điểm $O$.

2. Chứng minh rằng trong một đa giác lồi, tất cả các góc đều bằng nhau, tổng độ dài các đường vuông góc kẻ từ một điểm bên trong bất kỳ $O$ đến các cạnh của đa giác (hoặc với phần kéo dài của chúng) không phụ thuộc vào vị trí của điểm $O$.

3. Chứng minh rằng nếu các cạnh đối của một tứ giác không song song thì trung điểm đoạn nối giao điểm các cạnh đối diện nằm trên đường nối trung điểm các đường chéo.

4. Chứng minh rằng phân giác của góc $B$ của tam giác $ABC$ bằng $\frac{2ac}{a+c} \cos \frac{\beta}{2}$.

5. Chứng minh bằng cách sử dụng diện tích mà mỗi đường trung tuyến của một tam giác được chia cho mọi đường trung tuyến khác theo tỷ lệ 2:1, tính từ đỉnh, và do đó các đường trung tuyến của tam giác cắt nhau tại một điểm.

6. Trên cạnh $AC$ của tam giác $ABC$ lấy điểm $D$. Chứng minh rằng tổng bán kính của các đường tròn nội tiếp tam giác $ABD$ và $BCD$ lớn hơn bán kính của đường tròn nội tiếp tam giác $ABC$.
