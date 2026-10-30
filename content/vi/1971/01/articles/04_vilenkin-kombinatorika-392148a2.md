---
id: 1971-1-vilenkin-kombinatorika-392148a2
issue: kvant_1971_1
year: 1971
number: "1"
title: Tổ hợp học
authors:
  - Виленкин Н. Я.
rubric: osnovnye-stati
page_first: 15
page_last: 20
page_labels: 13, 14, 15, 18
tag: RMT7
lang: vi
source: kvant_digital
extraction: vision
content_sha256: cd7a92378018fec0905f6f02b71ad88b9c4625027562bdb2016a216ca5fc4038
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1971/01/articles/04_vilenkin-kombinatorika-392148a2.md
source_content_sha256: ffa07a6cfcaad7123ade77cc474309bd65814a6ebeb40fc5c2340142047fe3b9
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦folio 13⟧

Có lẽ mọi độc giả của “Kvant” đều biết cảm giác hồi hộp bao trùm công chúng trước một cuộc thi đấu thể thao lớn — dù đó là giải vô địch bóng đá thế giới hay “trận đấu thế kỷ” cờ vua. Từ những người không nhớ thật chính xác luật nhập thành, có thể nghe những lời nhận xét sâu sắc kiểu như “tôi sẽ không xếp Larsen mà là Portisch vào bàn đầu của đội tuyển thế giới”. Những người sành và yêu cờ vua tranh luận về cơ hội chiến thắng của Smyslov và Keres, còn những người yêu bóng đá thì gần như đi đến ẩu đả khi bàn về kết quả có thể có của trận đấu giữa đội tuyển Brasil và Anh.

Rất thường trước những cuộc thi đấu như vậy, các báo tổ chức cuộc thi dành cho người sành, đề nghị đoán cả kết quả chung của cuộc thi (dự đoán ai sẽ nhận được “Nữ thần vàng”, hoặc tỉ số mà đội tuyển cờ vua Liên Xô sẽ thắng đội tuyển thế giới), lẫn kết quả của từng cuộc đấu riêng lẻ. Thoạt nhìn, có một cách rất đơn giản để thắng trong cuộc thi như vậy: gửi đến tòa soạn nhiều thư bằng số kết quả có thể có về mặt lý thuyết của cuộc thi, và trong mỗi thư nêu một phương án. Ít nhất một lá thư sẽ trúng đích!

Nhưng sự việc hoàn toàn không đơn giản như vậy — có quá nhiều phương án. Tất nhiên, nếu chỉ cần dự đoán tỉ số mà trận đấu thế kỷ kết thúc, thì chỉ cần gửi 81 lá thư: trận đấu gồm 40 ván, và đội tuyển Liên Xô có thể ghi bất kỳ số điểm nào từ 0 (brr...) đến 40 (thật tuyệt biết bao!). Nhưng nếu còn phải chỉ ra kết quả trận đấu ở mỗi bàn cờ (ít nhất là dự đoán ai thắng), thì số phương án có thể tăng lên một cách thảm khốc.

Những bài toán cần tìm số phương án có thể có cho thao tác hay sự kiện này hoặc khác xuất hiện trong những lĩnh vực rất khác nhau của hoạt động con người. Những bài toán này được gọi là tổ hợp; hiện nay ở trường người ta không học nó, mà học tự chọn).

1. Quy tắc cộng và nhân. Cơ sở để giải các bài toán tổ hợp là hai quy tắc đơn giản — quy tắc cộng và quy tắc nhân.

Quy tắc cộng. Nếu ta có $m$ cách chọn phần tử $a$ và (độc lập với chúng) $n$ cách chọn phần tử $b$, thì lựa chọn “hoặc $a$ hoặc $b$” có thể thực hiện bằng $m+n$ cách.

Chẳng hạn, nếu trên đĩa có 5 quả táo và 9 quả lê, thì lựa chọn “một quả táo hoặc một quả lê” có thể thực hiện bằng 14 cách — chọn hoặc một trong 5 quả táo, hoặc một trong 9 quả lê.

Quy tắc nhân phức tạp hơn đôi chút. Nó nói về việc chọn một cặp phần tử $(a, b)^*$.

Quy tắc nhân. Nếu ta có $m$ cách chọn phần tử $a$ và $n$ cách chọn phần tử $b$, thì cặp $(a,b)$ có thể được chọn bằng $mn$ cách.

Như vậy, nếu trên đĩa có 5 quả táo và 9 quả lê, thì cặp (táo, lê) có thể được chọn bằng $5\cdot 9=45$ cách.

*) Hai cặp nhận được từ nhau bằng cách hoán vị các phần tử được xem là khác nhau, chẳng hạn cặp (1, 4) được xem là không trùng với cặp (4,1).

⟦folio 14⟧

Để kiểm tra tính đúng đắn của quy tắc nhân, ký hiệu mọi cách chọn phần tử $a$ là $a_1, \dots, a_m$, còn mọi cách chọn phần tử $b$ là $b_1, \dots, b_n$. Khi đó mọi cặp có thể lập từ các phần tử này được xếp thành bảng sau gồm $m$ hàng và $n$ cột:

$$(a_1, b_1), \dots, (a_1, b_n),$$
$$(a_m, b_1), \dots, (a_m, b_n).$$

Trong bảng này có đúng $mn$ cặp.

Chú ý rằng đôi khi việc lựa chọn phức tạp hơn — trước hết cần chọn phần tử $a$, rồi tùy theo lựa chọn đó chọn phần tử $b$. Nhưng nếu phần tử $a$ có thể chọn bằng $m$ cách, và sau mỗi lựa chọn đó phần tử $b$ có thể chọn bằng $n$ cách, thì số các cặp khác nhau $(a, b)$ lại bằng $mn$. Hãy tự chứng minh điều này.

Dĩ nhiên, có thể xảy ra rằng ta cần thực hiện không phải hai mà là vài lựa chọn. Trong trường hợp đó cần nhân số phương án của mỗi lựa chọn. Nói cách khác, đúng là quy tắc sau.

Nếu phần tử $a_1$ có thể chọn bằng $n_1$ cách, phần tử $a_2$ — bằng $n_2$ cách, phần tử $a_k$ — bằng $n_k$ cách, thì bộ $(a_1, \dots, a_k)$ có thể chọn bằng $n_1 \dots n_k$ cách (trong đó các bộ chỉ khác nhau về thứ tự các phần tử được coi là khác nhau).

Bây giờ ta đã có thể giải bài toán về số kết quả có thể có của trận đấu thế kỷ. Trên mỗi bàn có thể có 3 kết quả: thắng, hòa và thua. Vì số bàn bằng 10, nên có thể có $3^{10} = 59049$ kết quả khác nhau. Còn nếu cần biểu diễn không chỉ kết quả của mỗi người chiến thắng, mà cả tỉ số của nó, thì đáp số sẽ là $9^{10}$.

Bằng quy tắc nhân, cũng có thể giải những bài toán khá phức tạp, trong đó việc chọn các phương án bị ràng buộc bởi những điều kiện bổ sung.

Ví dụ. Trong bảng chữ cái Nga có 33 chữ cái khác nhau. Có thể lập được bao nhiêu từ gồm 5 chữ cái, nếu không cho phép những từ trong đó hai chữ cái giống nhau đứng liền nhau?

Dĩ nhiên, “từ” ở đây có nghĩa khác với trong ngữ văn học — cho phép những “từ” như аббед hoặc абаба. Nhưng những từ kiểu *ссора*, *пресс*, *аахен* thì không được phép — trong chúng có hai chữ cái giống nhau đứng liền nhau.

Để giải ví dụ này, ta sẽ chọn các chữ cái lần lượt — trước hết chữ thứ nhất, rồi chữ thứ hai, thứ tư, thứ năm, thứ sáu có thể chọn bằng 33 cách — vì ta có đủ cả 33 chữ cái của bảng chữ cái Nga. Nhưng chữ cái thứ hai chỉ có thể chọn bằng 32 cách — vì nó phải khác chữ thứ nhất. Chữ cái thứ ba cũng có thể chọn bằng 32 cách — nó phải khác chữ thứ hai; chữ cái thứ tư và thứ năm cũng có thể chọn bằng 32 cách. Tổng cộng được $33 \cdot 32 \cdot 32 \cdot 32 = 34603008$ từ khác nhau thỏa mãn điều kiện đã đặt ra.

2. Các k-tập con. Bằng quy tắc cộng và quy tắc nhân có thể giải nhiều bài toán tổ hợp khác nhau. Nhưng điều đó không phải lúc nào cũng thuận tiện, cũng như việc quy lời giải của bất kỳ bài toán hình học nào về các tiên đề không phải lúc nào cũng thuận tiện. Bên cạnh các tiên đề, trong hình học ta sử dụng các định lý, điều đó cho phép rút ngắn lời giải bài toán. Tương tự, trong tổ hợp có một số bài toán đơn giản nhất, “chuẩn”, mà thường có thể quy lời giải của các bài toán khác về chúng.

Các bài toán này được phát biểu bằng ngôn ngữ của lý thuyết tập hợp. Nếu độc giả không biết “tập hợp”, “phần tử của tập hợp”, “giao của các tập hợp”, “hợp của các tập hợp” là gì, chúng tôi giới thiệu độc giả đến danh mục tài liệu được nêu ở cuối bài viết. Tuy nhiên, ta sẽ chỉ dùng những khái niệm đơn giản nhất của lý thuyết tập hợp, những khái niệm hiện nay sẽ được học ở lớp 4 và lớp 5 của trường phổ thông, còn làm ví dụ ta sẽ lấy một tập hợp gồm bốn phần tử và sẽ biểu diễn các tập con của nó cùng những từ được lập từ các phần tử của tập hợp này (hình 1-5).

⟦folio 15⟧

Hình 1. Cho tập hợp $N$ gồm bốn phần tử: mã, tượng, hậu và xe.

Giải bài toán sau. 5 sinh viên thi đạt môn bơi. Đạt nếu sinh viên bơi được 100 mét (thời gian bất kỳ). Còn nếu sinh viên đến để vớt, thì không đạt. Cuộc bơi có thể kết thúc bằng bao nhiêu cách?

Có thể có các trường hợp khác nhau. Có thể coi rằng tất cả các sinh viên đều là những người bơi giỏi, cũng có thể coi rằng cả năm người đều phải được cứu. Tổng số kết quả có thể được tính như sau. Sắp xếp tất cả các sinh viên theo một thứ tự nào đó, chẳng hạn theo bảng chữ cái: Andreev, Borisov, Voldin, Grigoriev, Dmitriev. Với mỗi người trong số họ có hai khả năng — hoặc anh ta đạt yêu cầu, hoặc không. Trong trường hợp thứ nhất, ta gán cho sinh viên đó chữ số 1, còn trong trường hợp thứ hai — chữ số 0. Khi đó kết quả của cuộc bơi sẽ được biểu diễn bằng một dãy độ dài 5 gồm các số không và một. Chẳng hạn, dãy 0, 1, 1, 0, 1 có nghĩa là chỉ Borisov, Voldin và Dmitriev bơi đủ tốt. Còn nếu chỉ Grigoriev đạt yêu cầu, thì báo cáo về kết quả cuộc thi sẽ có dạng: 0, 0, 0, 1, 0. Dãy 0, 0, 0, 0 có nghĩa là không một sinh viên nào về đến đích.

Như vậy, bài toán về số kết quả của cuộc bơi được quy về bài toán sau: có thể lập được bao nhiêu dãy độ dài 5 từ các chữ số 0 và 1? Đáp số cho bài toán này được cho bởi quy tắc nhân: vì ở mỗi vị trí của dãy ta có sự lựa chọn giữa hai khả năng, nên tổng số kết quả bằng $2 \cdot 2 \cdot 2 \cdot 2 = 32$. Vậy có 32 kết quả có thể có của cuộc bơi.

Trong bài toán đã xét, ta cần biết có thể lập được bao nhiêu tập con từ tập hợp $N$: {Andreev, Borisov, Voldin, Grigoriev, Dmitriev}.

Ở đây cho phép cả tập con rỗng, cũng như tập con trùng với toàn bộ tập hợp $N$. Đáp số là $32 = 2^5$. Hoàn toàn tương tự, có thể chứng minh rằng nếu tập hợp $N$ chứa $n$ phần tử, thì nó có $2^n$ tập con. Kết quả này cũng có thể chứng minh bằng cách dùng quy nạp toán học.

Trong các kỳ thi Olympic, người ta làm như sau: hai người giỏi nhất vào chung kết. Hãy xác định các cuộc thi trong trường hợp này có thể có bao nhiêu kết quả. Về mặt toán học, bài toán được phát biểu như sau: có thể chọn 2 phần tử từ một tập hợp chứa 5 phần tử bằng bao nhiêu cách? Dễ kiểm tra rằng có thể làm điều đó bằng 10 cách (hãy tự liệt kê tất cả các cách ấy). Nhưng phương pháp “liệt kê trực tiếp” như vậy chỉ thích hợp khi số người tham gia nhỏ. Ta muốn có một công thức cho phép trả lời ngay câu hỏi. Vậy ta cần giải bài toán sau.

Có bao nhiêu $k$-tập con chứa trong tập hợp $N$ gồm $n$ phần tử?

Ở đây để ngắn gọn, ta nói “$k$-tập con” thay cho “tập con chứa $k$ phần tử”.

Việc chọn một tập con từ tập hợp đã cho $N$ có thể hình dung như sau. Ta bỏ các phần tử của tập hợp $N$ vào một cái túi, rồi thò tay vào túi ấy và lấy ra một tập con. Dĩ nhiên, cả $k$ phần tử của tập con được lấy ra cùng một lúc và không thể thiết lập một thứ tự hợp lý nào cho chúng.

⟦folio 18⟧

Hình 5. Có $P_4=4!=24$ hoán vị của các phần tử của tập hợp $N$.

sẽ lần lượt lấy ra khỏi nó các phần tử của tập hợp này. Nhưng lần này chúng ta sẽ không trả các phần tử ấy lại vào túi, mà xếp chúng thành một hàng. Sau $k$ lần chọn, chúng ta lại có một $k$-từ $(a_1, \dots, a_n)$, nhưng lần này trong các phần tử $a_1, \dots, a_n$ không có phần tử lặp lại *). Cũng có thể nói cách khác rằng các $k$-từ không lặp là các $k$-tập con có thứ tự của tập hợp $N$.

Số các $k$-từ không lặp từ $n$ phần tử được ký hiệu là $A_n^k$. Từ quy tắc nhân suy ra ngay rằng

$$A_n^k=n(n-1)\dots(n-k+1).$$

Thật vậy, phần tử thứ nhất có thể chọn bằng $n$ cách, phần tử thứ hai — chỉ bằng $n-1$ cách, vì không thể lấy phần tử đã chọn. Phần tử thứ ba có thể chọn bằng $n-2$ cách, ..., bằng $k-1-(n-k+1)$ cách.

*) Những $k$-từ như vậy được gọi là chỉnh hợp không lặp.

Vậy, tổng số cách thực sự được biểu diễn bởi công thức (3).

Ví dụ, nếu từ 10 thành viên của ủy ban cần chỉ định một đại diện, người thay thế của người đó và thư ký, thì có thể làm điều này bằng $10\cdot 9\cdot 8\cdot 720$ cách.

5. Hoán vị. Nếu từ một túi, các phần tử của tập hợp $N$ được lấy ra và xếp thành hàng lần lượt từng phần tử một (và không phần tử nào được trả lại), thì cuối cùng mọi phần tử của tập hợp $N$ đều được sắp xếp theo một thứ tự nào đó. Trong trường hợp này, người ta nói về các hoán vị không lặp của $n$ phần tử. Như vậy, một hoán vị của $n$ phần tử là một từ $k$ không lặp của $n$ phần tử. Đặt trong công thức (3) $k=n$, ta được rằng số hoán vị của $n$ phần tử bằng $n!$. Nó được ký hiệu bằng $P_n$. Vậy,

$$P_n=n!$$

6. Hoán vị có lặp. Chúng ta đã biết rằng từ $n$ “chữ cái” có thể
