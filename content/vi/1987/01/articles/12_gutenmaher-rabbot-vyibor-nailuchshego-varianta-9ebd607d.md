---
id: 1987-1-gutenmaher-rabbot-vyibor-nailuchshego-varianta-9ebd607d
issue: kvant_1987_1
year: 1987
number: "1"
title: Lựa chọn phương án tốt nhất
authors:
  - Гутенмахер В. Л.
  - Раббот Ж. М.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 39
page_last: 44
page_labels: 37, 38, 39, 41, 42
tag: 5VXI
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 1b23dd779ad60a00bff6b1203625285aa64e6fc550c572d5dc1329518b802cfa
prompt_sha256: draft-1
translated_from: content/ru/1987/01/articles/12_gutenmaher-rabbot-vyibor-nailuchshego-varianta-9ebd607d.md
source_content_sha256: 788545c4a791bd53ebfea79050aa5bec984ddb80e74e7f3e8c6ae83dbcb04181
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 37⟧

Lựa chọn phương án tốt nhất

Ứng viên Khoa học Vật lý và Toán học
V. L. GUTENMACHER,
.J.K. M. RABBOT

Ở các lớp trung học cơ sở, cũng như trong các kỳ thi tuyển sinh đại học, người ta thường đưa ra bài toán để soạn phương trình. Trong trường hợp này, trước tiên, cần phải dịch các điều kiện từ ngôn ngữ chung sang ngôn ngữ toán học, và thứ hai là giải các phương trình và bất đẳng thức thu được.
Trong văn bản bài toán một số tình huống được mô tả và cần phải xác định các tình huống khác dựa trên một dữ liệu cụ thể. Ví dụ: đây là cụm từ đầu tiên và cuối cùng của điều kiện bài toán trong sách giáo khoa đại số lớp 7:
“Hai người đánh máy nhận được một bản thảo để đánh lại… Mỗi người đánh máy có thể đánh lại bản thảo trong bao nhiêu giờ?”
“Chiếc thuyền khởi hành từ bến sông về phía hạ lưu… Người đi xe đạp mất bao nhiêu thời gian trên đường từ thành phố đến địa điểm cắm trại?”
“Một hợp kim đồng-kẽm chứa 5 kg kẽm được tạo hợp kim với 15 kg kẽm… Khối lượng ban đầu của hợp kim là bao nhiêu?”
Điều quan trọng là có thể giải quyết được bài toán đó, vì trong thực tiễn kinh tế và tùy tiện, người ta thường phải tóm tắt, đọc lại và tóm tắt các chỉ số khác nhau, phân tích công việc của doanh nghiệp.

tiy, v.v. Kết quả của hoạt động này là sự hiểu biết về tình hình hiện tại. Sau đó, điều tự nhiên là phải thực hiện bước tiếp theo - lập kế hoạch-chương trình cho các hành động tiếp theo. Tất nhiên, ở đây có rất nhiều lựa chọn và bạn muốn chọn cái thuận tiện nhất.

Việc thiết lập và lời giải như vậy bài toán là chủ đề của lập trình toán học. Tuy nhiên, một trong những người đầu tiên sử dụng toán học trong những vấn đề như vậy là nhà toán học, viện sĩ Liên Xô L. V. Kantorovich (1912-1986). Năm 1939, cuốn sách “Các phương pháp toán học tổ chức và lập kế hoạch tùy tiện” của ông được xuất bản. Trong lời giới thiệu cuốn sách này ông viết:

"Có hai cách để tăng hiệu quả của một xưởng, một doanh nghiệp và toàn bộ ngành. Tuy nhiên, con đường đó là những cải tiến khác nhau về công nghệ, tức là sử dụng các thiết bị mới trong một máy riêng biệt, thay đổi quy trình công nghệ, tìm ra các loại nguyên liệu thô mới, tốt hơn. Một cách khác, để sử dụng ít hơn hiện nay, là cải thiện việc tổ chức tính tùy tiện và lập kế hoạch. Điều này bao gồm, ví dụ, các vấn đề như phân bổ công việc giữa các máy riêng lẻ của một doanh nghiệp hoặc các cơ chế, phân bổ hợp lý các đơn đặt hàng giữa các doanh nghiệp, phân bổ hợp lý các loại nguyên liệu thô, nhiên liệu, v.v.”

Đã nhiều năm trôi qua kể từ đó, và lập trình toán học đã trở thành một ngành khoa học hoàn chỉnh dựa trên kinh tế sinh thái.

⟦folio 38⟧

phương pháp toán học và việc sử dụng rộng rãi máy tính.

Kết quả là, việc lập kế hoạch và quản lý bài toán phải giải quyết đồng thời một số lượng rất lớn các biến số. Chúng tôi sẽ phát triển một số ví dụ giáo dục đơn giản với một số lượng nhỏ các biến mà bạn có thể nhận được lời giải bằng cách sử dụng toán học mà học sinh lớp 6-7 đã biết - tỷ lệ, tính chất của hàm tuyến tính của một biến, một tìm kiếm nhỏ các lựa chọn và tất nhiên là sự khéo léo.

Xây nhà tắm ở đâu? Làng Mochalkino có 100 cư dân và làng Veniki có 50 cư dân. Tại điểm nào trên đường cao tốc nối các ngôi làng này nên xây dựng một nhà tắm sao cho tổng khoảng cách mà tất cả 150 cư dân sẽ phải di chuyển dọc theo đường cao tốc đến nhà tắm là nhỏ nhất?

Hãy để chúng tôi dịch điều kiện bài toán sang ngôn ngữ toán học. Giả sử khoảng cách dọc theo đường cao tốc giữa các làng là một km và nhà tắm nằm giữa các làng x km tính từ Mochalkino, do đó 0<x<a. Sau đó, tất cả 100 cư dân của ngôi làng này sẽ đi quãng đường 100x km đến nhà tắm, và tất cả 50 cư dân của làng Veniki sẽ đi quãng đường 50(a-x) km. Tổng cộng, S=100x+50(a-x) km sẽ được đọc.

Vì vậy, chúng ta có được công thức toán học sau bài toán: tìm giá trị nhỏ nhất của đại lượng S=50x+50a, với điều kiện 0≤x<a, trong đó a là một số cố định.

Việc giải bài toán rất dễ dàng: chỉ cần thay thế giá trị của S giảm khi x giảm là đủ, do đó giá trị nhỏ nhất của S sẽ bằng giá trị nhỏ nhất có thể có của x, tức là tại x = 0, và do đó bạn cần xây một nhà tắm ở làng Mochalkino.

Hãy thảo luận về kết quả thu được. Hầu như tất cả những người mà chúng tôi hỏi câu hỏi xây nhà tắm ở đâu đều trả lời ngay rằng nó nên được xây ở một nơi mà khoảng cách đến làng Mochalkino bằng một nửa khoảng cách đến làng Veniki. Có lẽ họ đã nghĩ ra mô hình vật lý sau: họ tưởng tượng ra một chiếc xích đu, với một người ngồi ở một đầu tấm ván, nặng gấp đôi người ngồi ở đầu kia.

Nếu nhà tắm nằm cách Mochalkino 1/3 thì tất cả cư dân sẽ cùng nhau đi theo con đường đến nhà tắm giống như cư dân của Venikov:

100·a/3=50·2a/3. Có lẽ, sẽ công bằng hơn nếu nó không có nghĩa là tất cả cư dân, mà đối chiếu ngôi làng này với ngôi làng khác và tìm kiếm một “điểm cân bằng”. Nhưng đây sẽ là lời giải một toán học hoàn toàn khác bài toán: tại giá trị nào của x, trong đó 0≤x≤a, giá trị f=|100x-50(a-x)| sẽ là nhỏ nhất?

Tất nhiên, từ “lựa chọn tốt nhất” có thể được hiểu theo những cách hoàn toàn khác nhau. Để hiểu chính xác chúng, chúng ta soạn một hàm mục tiêu. Trong bài toán của chúng tôi, đó là hàm S=50x+50a và trong một phiên bản khác, đó là hàm f=|150x-50a|. Sau khi tìm thấy x tại đó hàm mục tiêu có giá trị nhỏ nhất, chúng ta đã thu được phương án tốt nhất (theo một quan điểm nhất định).

Rõ ràng là cư dân của làng Veniki có thể không hài lòng với một trong hai lựa chọn này và có thể sẽ sớm đưa ra lập luận chống lại chúng. Hãy cộng lại rằng họ có nhiều người già và trẻ em hơn, nhưng ít ô tô hơn ở Mochalkino, họ có nước máy, nhưng ở Mochalkino thì không, v.v. Nhưng nếu tính đến tất cả những điều này, chúng ta sẽ có một toán học hoàn toàn khác bài toán - một mô hình toán học khác.

Chúng tôi mong rằng cách xây dựng có phần nhẹ nhàng của cây đa sẽ không gây ấn tượng sai lầm cho độc giả. Tệ hơn một chút, nhưng các máy chủ đã được hoàn thành bài toán: nơi nào trên lãnh thổ của một nhà máy lớn với nhiều xưởng để đặt căng tin? Cách tốt nhất để lập kế hoạch công việc bảo trì trong đó là gì?

Ở đây, việc lựa chọn hàm mục tiêu về nguyên tắc là rõ ràng (tiêu tốn ít thời gian nhất), nhưng lời giải tối ưu không chỉ phụ thuộc vào số lượng công nhân trong các phân xưởng khác nhau mà còn phụ thuộc vào đặc điểm

⟦folio 39⟧

hiệu quả sản xuất và các yếu tố khác.

Cách tốt nhất để đến nhà ga. Petra Petrovich cần phải đến nhà ga gấp. Anh ta có thể gọi một chiếc taxi, mất 24 phút và lái xe với tốc độ 30 km/h, hoặc anh ta có thể đi bộ với tốc độ 6 km/h. Điều tốt nhất anh ta nên làm là gì nếu khoảng cách từ nhà đến ga là: a) 2 km; b) 3 km; c) 5 km?

Để so sánh rõ hơn chuyển động của người đi bộ và xe số tự động, chúng tôi đang tuyển thêm một nhân viên - vợ của Peter Petrovich.

Hãy tưởng tượng rằng Pyotr Petrovich đi bộ đến ga, nhưng vừa ra khỏi nhà, vợ anh ta nhận thấy anh ta đã nhét vé tàu ở nhà, ngay lập tức gọi taxi, lấy và đi trả tiền cho chồng.

Hãy tính thời gian để cô ấy kết liễu được anh ta. Sau thời gian $t$ sau khi rời khỏi nhà, Pyotr Petrovich sẽ ở cách nhà 6t km, và lúc $t > 24$ phút=2/5 giờ xe taxi sẽ đi được 30(t—2/5) km.

Chiếc taxi có thể đuổi kịp Pyotr Petrovich vào lúc này khi

$$6t = 30(t - 2/5),$$

tức là vào lúc $t = 1/2$ giờ. Nếu quãng đường đến ga chưa đến 1/2 tiếng thì người vợ sẽ không kịp đuổi kịp chồng, nhưng nếu quá 1/2 tiếng thì cô ấy sẽ đón và cho chồng chở đến ga. Trong $t = 1/2$ giờ Pyotr Petrovich có thể di chuyển cách nhà mình 3 km. Do những khác biệt này, chúng tôi đi đến kết luận sau.

Nếu khoảng cách đến nhà ga nhỏ hơn 3 km, như trong trường hợp $a$), tốt hơn hết Petro Petrovich nên đi bộ; nếu là 3 km thì không thành vấn đề - đi bộ hoặc taxi; và nếu xa hơn 3 km, như trường hợp $b$) - tốt nhất bạn nên gọi taxi.

Để hiểu rõ hơn về lời giải, việc trình bày bằng đồ họa là rất hữu ích; một số giả định được đưa ra một cách âm thầm: người đi bộ và taxi di chuyển giống nhau, taxi được gọi và khởi hành ngay lập tức (trong thực tế điều này không xảy ra), v.v. Ngoài ra, theo điều kiện của chúng tôi, thời gian là thứ quý giá nhất đối với Pyotr Petrovich. Nhưng trong trường hợp $b$), chúng tôi phải đối mặt với thực tế là có hai lựa chọn tương đương nhau theo quan điểm này. Để chọn một trong số đó, bạn cần một thông báo khác: chi phí của chuyến đi (khi đó rất có thể anh ấy sẽ đi bộ) hoặc sự thuận tiện (khi đó anh ấy sẽ bắt taxi).

Một chiếc xe đạp cho hai người. Hai anh em Kolya và Seryozha đang cố gắng đến gặp bà của họ, người sống cách họ 40 km. Họ có một chiếc xe đạp và họ đã thêm một số thứ vào. Kolya đi bộ với tốc độ 6 km/h và đi xe đạp với tốc độ 20 km/h; Tốc độ của Serezha lần lượt là 4 km/h và 30 km/h. Xe đạp có thể được để trên đường mà không cần phanh. Cách nhanh nhất để họ đến được với bà là gì?

Giả sử rằng anh trai đến nhà bà ngoại cùng lúc và chúng ta sẽ tìm ra thời điểm mà họ có thể làm điều này. Sau đó, chúng tôi sẽ chỉ ra rằng trong thời gian ngắn hơn, một trong số họ sẽ không thể liên lạc được với bà ngoại.

Để Kolya đi xe đạp $x$ km và đi bộ $(40-x)$ km, còn Seryozha thì ngược lại, đạp xe $x$ km và lái xe $(40-x)$ km.

Sau đó Kolya dành $(x/20+(40-x)/6)$ giờ trên đường và Seryozha - $(x/4+(40-x)/30)$ giờ.

Nếu họ đến gần cùng một lúc,

$$\frac{x}{20} + \frac{40-x}{6} = \frac{x}{4} + \frac{40-x}{30}.$$

⟦folio 41⟧

$$m = \frac{2}{15} + \frac{7}{15} y,$$

nhận giá trị nhỏ nhất ở giá trị nhỏ nhất có thể là $y = 0$. Nếu chúng ta biểu thị $m$ không phải thông qua $y$ mà thông qua $x$ hoặc thông qua $z$, thì sẽ khó khăn hơn để tìm ra khoảng nào chúng ta nên tìm giá trị nhỏ nhất của nó. Cách tốt nhất để chọn biến nào để gán hàm cũng là một bài toán quan trọng.

Có thể thực hiện được mà không cần những tính toán này nếu chúng ta lưu ý các trường hợp sau. Để hợp kim mới chứa 40% coban và càng ít đồng càng tốt thì hợp kim đó phải chứa càng nhiều niken càng tốt. Do đó, hợp kim thứ hai, có vẻ tốt vì nó đã chứa 40% coban, tốt hơn hết là bạn không nên chạm vào nó, vì nó hoàn toàn không chứa niken - xem bảng. Điều này có nghĩa là chúng ta cần trộn hợp kim thứ nhất và thứ ba. Chúng ta lấy $a$ kg hợp kim thứ nhất, sau đó chúng ta cần lấy $(1-a)$ kg hợp kim thứ ba. Hợp kim mới sẽ chứa 0,6(1-a) kg coban. Theo điều kiện, 0,6(1-a)=0,4, do đó $a=1/3$, dẫn đến đáp số.

Năm mới bài toán*). Với giá 100 rúp. lời giải buy.elochny cerrushek. Ngược lại, cerrushkas trên cây Giáng sinh được bán theo cách khác. Một bộ 20 chiếc cerrush có giá 4 rúp, một bộ 35 chiếc cerrush có giá 6 rúp, một bộ 50 chiếc cerrush có giá 9 rúp. Bạn nên mua bao nhiêu và bộ nào để mua được ít hoa hồng nhất?

Một cerrushka trong bộ đầu tiên có giá 1/5 chà, trong bộ thứ hai - 6/35 chà, trong bộ thứ ba - 9/50 chà. Hãy sắp xếp các số sau: 6/35<9/50<1/5. Vì vậy, những đồ chơi rẻ nhất nằm ở bộ thứ hai, và những đồ chơi đắt nhất nằm ở bộ thứ nhất.

Để mua với giá 100 rúp. Tất nhiên, càng nhiều cây cerrush càng tốt, bạn cần phải mua những cây cerrush lớn. Nhiều nhất chúng ta có thể mua 16 bộ với giá 6 rúp. và chi 96 rúp cho nó.

Còn lại 4 rúp, bạn có thể dùng số tiền này để mua bộ đầu tiên. Tất cả chúng ta sẽ mua 16·35+20=580 zerrushki theo cách này.

Đây rất có thể là lựa chọn tốt nhất. Tuy nhiên, hãy kiểm tra điều này: nếu bạn mua 15 bộ sáu hộp thì bạn còn lại 10 rúp. Sau đó chúng ta có thể mua một bộ guble thứ chín khác hoặc hai bộ bốn guble. Trong cả hai trường hợp, số lượng cerrush ít hơn trong tùy chọn đầu tiên.

Vì vậy, bạn cần mua 16 bộ với giá 6 rúp. và 1 bộ có giá 4 rúp. Trong trường hợp này, 580 cerrush sẽ được mua.

Chúng tôi đã đạt được điều này đáp số với sự trợ giúp của một thông điệp tự nhiên như vậy: bạn có thể mua những chiếc cerrush lớn hơn thì càng rẻ.

Lý do của chúng tôi là hợp lý, nhưng nói chung, chúng tôi chưa xem xét tất cả các lựa chọn có thể. Vì vậy, chúng tôi đưa ra quy định lời giải nghiêm ngặt hơn.

Gọi $x$ là số bộ loại I, $y$ - loại II, $z$ - loại III. Chúng ta cần tìm số không âm như vậy

⟦folio 42⟧

các số $x$, $y$ và $z$ sao cho các điều kiện $4x+6y+9z \leq 100$ được thỏa mãn và các giá trị $S=20x+35y+50z$ là lớn nhất.

Bởi vì

$$4x+6y+9z = \frac{6}{35}S + \frac{4}{7}x + \frac{3}{7}z \geq \frac{6}{35}S,$$

hóa ra là $\frac{6}{35}S \leq 100$, do đó $S \leq 583\frac{1}{3}$.

Vì $S=20x+35y+50z$ là số nguyên chia hết cho 5 nên ta có $S \leq 580$. Tại $x=1$, $y=16$, $z=0$ mọi điều kiện đều được thỏa mãn và $S=580$.

bài toán này đề cập đến lập trình số nguyên, một trong những nhánh khó nhất của lập trình toán học.

Nhiệm vụ

1. Ba nhân viên bán hàng trẻ - Yury, Ykov và Lev - được phân công làm việc trong một cửa hàng bách hóa. Giám đốc một cửa hàng bách hóa cần phân công một người trong số họ vào bộ phận hàng hóa phát thanh, một người khác vào bộ phận nhạc cụ và một người thứ ba vào bộ phận hàng ảnh. Giám đốc đã nhờ nhà tâm lý học giúp ông xác minh cuộc hẹn này. Chuyên gia tâm lý đã trò chuyện với họ và đánh giá kiến ​​thức của mọi người

| RADIO | HÌNH ẢNH | ÂM NHẠC |
| :--- | :--- | :--- |
| yuri | 5 | 4 | 7 |
| Yakova | 6 | 7 | 3 |
| Loeb | 8 | 11 | 2 |

trong cả ba lĩnh vực trong điểm. Sau đó anh ta lập một bảng và trình cho giám đốc cửa hàng bách hóa. Giám đốc có thể phân bổ người mới như thế nào để tổng số điểm tương ứng là nhiều nhất? (Ví dụ: nếu Yury được phân vào khoa phát thanh, Ykov vào khoa âm nhạc và Lev vào khoa nhiếp ảnh thì tổng điểm sẽ bằng $5+3+11=19$).

2. Trong chảo rán, đặt hai miếng cốt lết lại với nhau, bạn có thể chiên cả hai mặt trong 10 phút. Cách nhanh nhất để chiên 3 miếng cốt lết trong chảo rán này là gì?

3. Cho hai điểm $A$ và $B$, nằm ở một phía của một đường thẳng cho trước. Làm cách nào để đặt đoạn MK có độ dài cho trước $a$ trên đường thẳng này sao cho đoạn thẳng AMKB có độ dài ngắn nhất?

4. Ba anh em đã đầu tư một cái, cần bổ sung thêm vào căn nhà cách cửa hàng 30km. Mỗi anh em đi bộ với vận tốc 4 km/h và đạp xe với vận tốc 20 km/h. Trong thời gian ngắn nhất họ có thể được thêm vào nhà? (Có thể để tệp đính kèm trên đường mà không cần lăng kính.)

5*) Một bé có thể ăn một chiếc bánh trong 10 phút, một lọ mứt trong 8 phút và uống một hộp sữa trong 4 phút. Carlson có thể làm điều này nhanh hơn gấp 2 lần. Trong thời gian ngắn nhất họ có thể cùng nhau ăn xong bữa sáng gồm một chiếc bánh, một lọ mứt và một hộp sữa?

6. Mỗi trong số bốn chứa 1 lít hỗn hợp axit và nước. Tỷ lệ axit trong chúng tương ứng là 10%, 30%, 60%, 80%. Phòng thí nghiệm cần thu được hỗn hợp 50% axit và nước. Lượng hỗn hợp nhỏ nhất mà anh ta có thể thu được bằng cách đổ hỗn hợp từ các bình này là bao nhiêu?

7. Cần phải chế tạo một hợp kim chứa 40% thiếc. Có 3 hợp kim trong kho với hàm lượng thiếc 60%, 10% và 40%. Giá 1 kg mỗi hợp kim là 4,3 rúp, 5,8 rúp. và 5,5 chà. tương ứng. Nên lấy những hợp kim nào và theo tỷ lệ nào từ kho để 1 kg hợp kim mới rẻ nhất có thể?

8. (Bài toán thi tuyển sinh khoa kế hoạch kinh tế và kinh tế, thư viện Khoa Kinh tế của Đại học quốc gia Mátxcơva, 1984). Ba loại nhà có thể được lắp ráp từ hai loại bộ phận của tòa nhà. Để lắp ráp một tòa nhà 12 căn hộ, bạn cần 70 phần thuộc loại thứ nhất và 100 phần thuộc loại thứ hai. Để lắp ráp một tòa nhà 16 căn hộ, cần có 110 và 150 căn hộ, còn đối với một ngôi nhà có 21 căn hộ thì cần 150 và 200 bộ phận của loại thứ nhất và thứ hai của loại tương ứng. Có 900 phần thuộc loại thứ nhất và 1300 phần thuộc loại thứ hai. Cần phải lắp ráp bao nhiêu và loại nhà nào để tổng số căn hộ trong đó là lớn nhất?

9. Trên vành đai đường cao tốc có ba nhà kho và ba cửa hàng; khoảng cách giữa hai điểm lân cận là 1km. hình thể hiện tình trạng sẵn có của hàng hóa trong kho (tính bằng tấn) bằng dấu “+” và nhu cầu hàng hóa của cửa hàng (tính bằng tấn) bằng dấu “-”. Cần lập phương án vận chuyển ít kinh tế nhất để chuyển toàn bộ hàng hóa từ kho đến kho sao cho khối lượng vận chuyển tấn/km là nhỏ nhất. (Trích dẫn các phương án di chuyển có sẵn, theo quan điểm của bạn và nêu rõ những thông điệp đã đưa bạn đến đáp số này.)
