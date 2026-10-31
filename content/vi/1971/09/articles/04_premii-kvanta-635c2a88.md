---
id: 1971-9-premii-kvanta-635c2a88
issue: kvant_1971_9
year: 1971
number: "9"
title: Giải thưởng của «Kvant»
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 35
page_last: 40
page_labels: 35, 36, 38
tag: 9BN5
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 419717cb75822995113535593cddc55adf92de6a80b84b8e6a26004c2117aa6f
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1971/09/articles/04_premii-kvanta-635c2a88.md
source_content_sha256: 1515494e9543d7c0e7a59033c52e7f481928192ca1ea34f82447feb760db6840
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦folio none⟧

Tòa soạn tạp chí đã nhận được hơn 2000 lá thư có lời giải các bài toán đăng trong mục “Bài toán của «Kvant»”. Trong số các tác giả của những lá thư này, ban biên tập đã chọn những học sinh thường xuyên gửi các lời giải đặc biệt độc đáo và thành công. Các em được tặng một năm đặt báo tạp chí “Kvant” cho năm 1972.

Đây là tên những người thắng cuộc thi của chúng tôi:

Dmitry Grigoriev — Leningrad, trường nội trú số 45 trực thuộc ĐHTH Leningrad;
Yury Obolonkov — Voronezh, trường số 58;
Eduard Turkevich — Chernivtsi, trường số 9;
Mikhail Preger — Tomsk, trường số 51;
Arkady Chernyak — Minsk, trường số 50;
Leonid Braginsky — Frunze, trường số 61;
Viktor Krivitsky — làng Kletnoye, huyện Borisov, tỉnh Minsk;
Aleksandr Grigoryan — Baku, trường số 211;
Grigory Zaitsev — Gagra, trường số 2;
Ivan Grichik — David-Gorodok, tỉnh Brest, trường số 1;
Aleksandr Zhukov — Kirovsk, huyện Khartsyzsk, tỉnh Donetsk, trường số 11;
Anatoly Anishchenko — Sarapul, trường số 13 của CHXHCNXV tự trị Udmurt;
Yevgeny Gubarev — Moskva, trường số 144.

⟦folio 35⟧

Để chứng minh khẳng định 1), chúng tôi sẽ chỉ ra một chiến lược của người chơi thứ nhất, không phụ thuộc vào các nước đi của người thứ hai và bảo đảm rằng hiệu của hai số còn lại không nhỏ hơn 32. Chiến lược này rất đơn giản: ở mỗi nước đi gạch bỏ cách một số, tức là gạch bỏ số thứ hai, thứ tư, ... trong các số còn lại (chúng tôi coi các số được sắp theo thứ tự tăng dần). Khi đó sau nước đi thứ 1, hiệu giữa bất kỳ hai số kề nhau nào trong các số còn lại sẽ không nhỏ hơn 2, sau nước đi thứ 2 — không nhỏ hơn 4, sau nước đi thứ 3 — không nhỏ hơn 8, sau nước đi thứ 4 — không nhỏ hơn 16 và sau nước đi thứ 5 — không nhỏ hơn 32.

Để chứng minh khẳng định 2), chỉ cần chỉ ra một chiến lược của người chơi thứ hai, không phụ thuộc vào các nước đi của người thứ nhất, cho phép anh ta thua không quá 32. Chiến lược đó như sau. Ở nước đi đầu tiên, anh ta gạch bỏ tất cả các số nhỏ hơn 512, hoặc tất cả các số lớn hơn 512 (rõ ràng hoặc loại này, hoặc loại kia còn lại không quá 256 số). Sau đó hiệu giữa các số biên trong những số còn lại sẽ không lớn hơn 512. Tương tự, ở nước đi thứ hai anh ta có thể đạt được sao cho tất cả các số còn lại chỉ nằm trong một trong các đoạn [0,256]; [256, 512]; [512, 768]; [768, 1024], tức là giảm hiệu giữa các số biên ít nhất xuống 256. Cũng như vậy, ở nước đi thứ 3 anh ta có thể giảm hiệu này xuống 128, ở nước đi thứ 4 — xuống 64 và ở nước đi thứ 5 — xuống 32.

Lời giải đầy đủ nhất của bài toán này được Y. Obolonkov từ Voronezh và V. Luzey từ Moskva gửi đến.

Dĩ nhiên, tương tự có thể chứng minh rằng nếu trò chơi gồm n nước đi và bắt đầu với các số 0, 1, 2, ... 2^n, thì “giá trị của trò chơi” bằng 2^n. Nhưng việc nghiên cứu chi tiết một trò chơi tương tự bắt đầu từ một tập hợp số tùy ý (không nhất thiết là một cấp số cộng) là một bài toán khó hơn đáng kể.

**M62**

Chứng minh rằng với mọi số lẻ a, tồn tại một số tự nhiên b sao cho 2^b — 1 chia hết cho a.

Đây là chứng minh ngắn nhất.

Xét các số 2^0 — 1, 2^1 — 1, ..., 2^a — 1. Có (a+1) số như vậy. Hai số nào đó trong chúng cho cùng số dư khi chia cho a, vì chỉ có tất cả a số dư khác nhau như thế (lập luận này được gọi là “nguyên lý Dirichlet”, về các ứng dụng của nó có kể trong bài của A. Orlov trên “Kvant” số 7). Giả sử, chẳng hạn, các số 2^k — 1 và 2^m — 1 cho cùng số dư khi chia cho a và k < m. Khi đó số (2^m — 1) — (2^k — 1) = 2^k (2^m — k — 1) chia hết cho a và, vì a lẻ, 2^m — k — 1 chia hết cho a.

Cũng chứng minh được một sự kiện tổng quát hơn: nếu các số tự nhiên a và c nguyên tố cùng nhau, thì sẽ tìm được một số tự nhiên b sao cho c^b — 1 chia hết cho a. Nhiều độc giả đã nhận thấy rằng mệnh đề của bài toán suy ra từ định lý Euler sau đây*): với mọi số tự nhiên a và c, số c^φ(a)+1 — c chia hết cho a, trong đó φ(a) là số lượng các số tự nhiên nhỏ hơn a và nguyên tố cùng nhau với nó, và thậm chí còn nêu công thức tính “hàm Euler”

$$\varphi\left(p_1^{\alpha_1} p_2^{\alpha_2} \cdots p_r^{\alpha_r}\right) = \left(p_1^{\alpha_1} - p_1^{\alpha_1}-1\right) \times \left(p_2^{\alpha_2} - p_2^{\alpha_2}-1\right) \cdots \left(p_r^{\alpha_r} - p_r^{\alpha_r}-1\right).$$

Lời giải đúng được gửi bởi A. Chernyak từ Minsk, E. Turkevich, Sh. Slepoy từ Chernovtsy, G. Levin từ Kuibyshev, N. Demidenko từ làng Kolbovka, tỉnh Gomel, A. Pukhalsky từ Moskva, Yu. Semenok từ thị trấn Mirny, vùng Krasnodar và các độc giả khác.

**M63**

Có thể lát một hình vuông bằng 18 viên gạch kích thước 1×2 sao cho không có một hình chữ nhật nào có cạnh trùng với cạnh của hình vuông và đi theo các mép gạch không? (Chẳng hạn, cách xếp gạch như ở hình 2 không được, vì ở đây có “đường nối” AB.)

Giả sử ta đã lát được một hình vuông 6×6 bằng các viên gạch 1×2 không có “đường nối”. Khi đó mỗi trong số mười đường thẳng chia hình vuông này

*) Xem, chẳng hạn, sách của I. M. Vinogradov “Cơ sở lý thuyết số”, GITTL, M., 1953 hoặc một giáo trình lý thuyết số khác.

⟦folio 36⟧

Hình 2.
Hình 3.
Hình 4.
Hình 5.

thành các ô 1×1, phải cắt ít nhất một viên gạch 1×2. Không khó chứng minh rằng mỗi đường thẳng như vậy cắt một số chẵn viên gạch. Thật vậy, nó cắt từ hình vuông 6×6 một hình chữ nhật 6×k, gồm một số chẵn ô 1×1; hình chữ nhật này chứa một số viên gạch nguyên vẹn 1×2 và thêm một số chẵn ô 1×1 — các nửa viên gạch bị đường thẳng cắt qua (hình 3).

Nhưng nếu mỗi đường thẳng cắt không ít hơn hai viên gạch, thì tổng số viên gạch phải không nhỏ hơn 2·10=20, trong khi chỉ có 18 viên.

Như vậy, ta đã chứng minh rằng không thể chia hình vuông 6×6 thành các viên gạch theo cách yêu cầu.

Lời giải đúng của bài này được gửi bởi A. Kostyurin từ tỉnh Moskva, I. Kashanov từ Ufa, V. Shvarts từ Leningrad và những người khác. Trong phần lớn các thư gửi đến, người ta bàn về câu hỏi tổng quát: khi nào một hình chữ nhật m×n có thể được chia thành các viên gạch 1×2 không có đường nối. Dễ chứng minh rằng không thể chia hình chữ nhật 2×n, 3×n và 4×n theo cách này. Nếu m≥5, n≥5 và mn chẵn (điều kiện cuối cùng, dĩ nhiên, là cần thiết), thì trong mọi trường hợp, trừ trường hợp 6×6 đã xét ở trên, sự phân chia cần thiết đều tồn tại. Để chứng minh, chỉ cần nghĩ ra cách chia các hình chữ nhật 5×6 và 6×8, rồi nhận thấy rằng từ cách chia hình chữ nhật m×n dễ dàng nhận được cách chia hình chữ nhật (m+2)×n (hình 4 và 5).

N. B. Vasilyev

Ф72

Vì sao vào tháng Ba độ dài ngày thay đổi nhanh hơn vào tháng Mười Hai?

Sự thay đổi độ dài ngày liên quan đến góc nghiêng của trục Trái Đất so với mặt phẳng quỹ đạo chuyển động của Trái Đất quanh Mặt Trời (≈23,5°). Nếu trục Trái Đất vuông góc với mặt phẳng quỹ đạo, thì độ dài ngày trên thực tế sẽ không thay đổi.

Độ nghiêng của trục trong không gian không thay đổi, và vì Trái Đất quay quanh Mặt Trời, nên từ Mặt Trời nó được nhìn thấy khác nhau (hình 6) — Mặt Trời chiếu sáng các vùng trên bề mặt Trái Đất trong những khoảng thời gian khác nhau, và độ dài ngày không cố định. Rõ ràng, vào tháng Mười Hai và tháng Sáu, khi ở bán cầu nam độ dài ngày tương ứng là nhỏ nhất hoặc lớn nhất, còn cực bắc nghiêng xa Mặt Trời hoặc về phía Mặt Trời, vị trí trục Trái Đất so với Mặt Trời thay đổi rất chậm. Độ dài ngày cũng thay đổi chậm. Đồng thời vào tháng Ba và tháng Chín vị trí của trục thay đổi nhanh — độ dài ngày cũng thay đổi nhanh.

Thú vị là vẽ một đồ thị gần đúng của sự phụ thuộc độ dài ngày vào mùa trong năm. Đại khái — đó là một đường hình sin (hình 7). Tốc độ thay đổi độ dài ngày, rất nhanh, tỉ lệ với tang của góc

⟦folio 38⟧

của áp suất do các phân tử chất tan gây ra. Áp suất này được gọi là áp suất thẩm thấu. Điều kiện cân bằng của chất lỏng trong các bình không phải là sự bằng nhau của các áp suất thủy tĩnh ở hai phía của vách ngăn, mà, nói gần đúng, là sự bằng nhau của áp suất của các phân tử dung môi.

Các phân tử chất tan cư xử giống như các phân tử khí. Chúng стремятся chiếm thể tích lớn nhất có thể, bằng cách dịch chuyển vách ngăn (chúng đã làm được điều đó nếu vách ngăn có thể chuyển động). Nhưng vì vách ngăn được cố định, nên không phải nó dịch chuyển mà là mức dung dịch.

Sự tương tự giữa hành vi của các phân tử khí và các phân tử chất tan là hoàn toàn. Nếu dung dịch loãng, thì các phân tử chất tan ở xa nhau hơn và tương tác yếu với nhau — cũng như các phân tử khí lý tưởng (chúng chỉ tương tác với nhau khi va chạm). Vì vậy áp suất thẩm thấu $p$ phải liên hệ với thể tích dung dịch $V$, nhiệt độ $T$ và số mol $n$ chất tan bằng cùng công thức như áp suất của khí lý tưởng:

$$pV=nRT$$

(R — hằng số khí).

Định luật này được Vant-Hoff phát hiện và chứng minh bằng thực nghiệm. Áp suất thẩm thấu không phụ thuộc vào bản chất của chất tan và chỉ được xác định bởi nồng độ dung dịch. Đối với các dung dịch đậm đặc (dung dịch có nồng độ lớn), có thể viết một phương trình tương tự phương trình Van der Waals cho khí thực. Nếu trong dung dịch có các chất khác nhau, thì, theo sự tương tự với khí, áp suất thẩm thấu bằng tổng các áp suất riêng phần thẩm thấu của từng chất tan. Tương tự khí lý tưởng, dung dịch sẽ ứng xử trong trường trọng lực: sự phân bố số phân tử theo độ cao sẽ hoàn toàn giống như vậy. Điều này đã cho phép Perrin

“cân” nguyên tử (xem bài của M. P. Bronstein “Nguyên tử đã được cân như thế nào”, “Kvant” số 2, năm 1970).

Năng lượng để nâng chất lỏng được lấy từ năng lượng nhiệt của chuyển động các hạt chất tan. Hoàn toàn giống như khí thật, “khí” các hạt chất tan, khi giãn nở và thực hiện công, sẽ lạnh đi. Khi đó, dĩ nhiên, toàn bộ dung dịch cũng lạnh đi.

Áp suất thẩm thấu đóng vai trò rất quan trọng trong đời sống của con người, động vật và thực vật. Vỏ của nhiều cơ quan là một vách ngăn bán thấm — chẳng hạn, thành mạch máu và ruột, bề mặt rễ cây vân vân. Chính áp suất thẩm thấu quyết định thể tích các chất.

Nhiều bạn đọc đã giải đúng bài này: V. Sokolov (thị trấn Myshansk, tỉnh Gomel, CHXHCNXV Belorussia), C. Araslanova (thị trấn Nizhnevinko, huyện Kumensky, tỉnh Kirov), H. Fedin (Omsk), H. Kolenko (Bondar, tỉnh Odessa), H. Egorov (làng Maya, huyện Mechinokangalassky, CHXHCNXV Yakut), M. Kozlovsky (Moskva), C. Panfin (Novosibirsk), P. Khmara (Voroshilovgrad), A. Fialkov (Karaganda), T. Rudakova (Irkutsk), O. Kim (Ulyanovsk), V. Tapezyan (làng Mshcharskoe, huyện Gudautsky, CHXHCNXV Abkhazia), K. Kirilov (Minusinsk, vùng Krasnoyarsk), O. Maslok (Novomirgorod, tỉnh Kirovograd, CHXHCNXV Ukraina), M. Maksimenko (Balaklya, tỉnh Kharkov), A. Veretsada (Orekhov, tỉnh Zaporozhye, CHXHCNXV Ukraina), S. Ivakov (Moskva).

Ф74

Hai tụ điện được mắc nối tiếp. Tụ thứ nhất có điện dung $C_1$ và được tính cho điện áp cực đại $U_1$, tụ thứ hai — điện dung $C_2$ và được tính cho điện áp $U_2$. Có thể nối bộ tụ điện này vào điện áp nào?

Vì các tụ điện được nối với nhau nên điện tích của chúng bằng nhau, còn điện dung của bộ tụ bằng $C = \frac{C_1C_2}{C_1 + C_2}$. Nếu đặt điện áp $U$ vào bộ tụ điện, thì điện tích của nó sẽ bằng $q = CU = \frac{C_1C_2}{C_1 + C_2} U$. Điện tích này không được
