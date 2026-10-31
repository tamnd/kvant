---
id: 1979-7-meledin-mozhno-li-proverit-otvet-ddfdbedb
issue: kvant_1979_7
year: 1979
number: "7"
title: Có thể kiểm tra đáp số?
authors:
  - Меледин Г. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 43
page_last: 45
page_labels: 41-43
tag: B10X
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 022a2cd2790e8aaf0fe33534a8272d198a1a1e514c7f04c06157b1a7d71985a4
prompt_sha256: draft-1
translated_from: content/ru/1979/07/articles/11_meledin-mozhno-li-proverit-otvet-ddfdbedb.md
source_content_sha256: 8e649bf525f222fd0a522b50b0e9547d642f8c79bb8ee4446e380458e00ec43a
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 41⟧

Có thể kiểm tra đáp số?

Sau lời giải bài toán, đặc biệt khó khăn, anh ấy luôn muốn đảm bảo rằng kết quả thu được là chính xác hoặc ít nhất là không có sai sót. Có nhiều cách để nhanh chóng phát hiện lỗi. Ví dụ: bạn có thể so sánh đáp số của mình với câu trả lời của người khác hoặc với câu trả lời thu được với lời giải của cùng bài toán bằng các phương pháp khác. Tuy nhiên, cũng có thể điều này không phải lúc nào cũng đúng.

Chúng ta hãy xem xét một vài ví dụ mà các nhà vật lý sử dụng. Đây là kiểm tra đáp số về chiều, kiểm tra tính đối xứng, nghiên cứu các trường hợp đặc biệt (hoặc giới hạn) và cuối cùng là kiểm soát phạm vi các giá trị cho phép.

Để kiểm tra đáp số bằng một trong các phương pháp này, bạn cần lấy nó ở dạng đại số (nghĩa đen).

1. Việc kiểm tra thứ nguyên không yêu cầu nhận xét đặc biệt - khi thay thế thứ nguyên của đại lượng có trong công thức, kết quả phải là thứ nguyên của đại lượng ban đầu. (Tất nhiên, tất cả các tham số phải được biểu thị trong cùng một hệ đơn vị.) Từ quan điểm của một tấm séc như vậy, thật thuận tiện khi viết đáp số sao cho kích thước của nó được hiển thị ngay lập tức. Với mục đích này, tỷ lệ không thứ nguyên hoặc thứ nguyên ổn định của sự kết hợp các tham số như $|v|^2/g$ (thứ nguyên chiều dài), $\rho gh$ (thứ nguyên áp suất), $\sqrt{l/g}$ (thứ nguyên thời gian), v.v. thường được phân biệt.

Ví dụ: hãy xem xét bài toán nổi tiếng:

Bài toán 1. Có một sợi dây không được buộc chặt xuyên qua một khối peroxidum đứng yên, với các khối lượng có khối lượng $m_1$ và $m_2$ lơ lửng ở hai đầu của sợi dây (Hình 1). Tìm lực căng của sợi chỉ $|\vec{T}|$ khi di chuyển tải.

Đáp số: $|\vec{T}| = \frac{2m_1m_2}{m_1 + m_2} g$.

Hãy kiểm tra kích thước. Tích của các khối lượng chia cho tổng của chúng sẽ cho ra thứ nguyên của khối lượng, và nhân với gia tốc sẽ cho thứ nguyên của lực. Do đó, kích thước bên trái và bên phải của công thức tính độ căng chỉ là như nhau.

2. Kiểm tra tính đối xứng ít được biết đến. Nó sẽ bao gồm những điều sau đây. Nếu điều kiện bài toán chứa một số tham số có cùng thứ nguyên theo cách đối xứng sao cho khi các chỉ số đánh số các tham số được sắp xếp lại, bài toán không thay đổi, thì sự đối xứng tương tự phải tồn tại trong đáp số.

Do đó, trong bài toán 1, độ căng của sợi không phụ thuộc vào tải nặng hơn ở bên trái hay bên phải của khối vị trí và chỉ số nào trong hai chỉ số - 1 hoặc 2 - biểu thị khối lượng của nó. Điều này có nghĩa là đáp số không nên thay đổi khi $m_1$ được thay thế bằng $m_2$ và $m_1$. Nói cách khác, biểu thức về độ căng chỉ phải đối xứng với $m_1$ và $m_2$. Tặng đáp số cho hành động này

Hình 1.

⟦folio 42⟧

hoàn toàn thỏa mãn—cả tích và tổng khối lượng đều là sự kết hợp đối xứng của các tham số $m_1$ và $m_2$.

Hãy đưa ra một ví dụ khác trong đó có sự đối xứng tương tự.

Bài toán 2. Ba tụ điện có cùng điện dung lần lượt có điện tích $q_1, q_2$ và $q_3$. Sau đó, chúng được kết nối, như trong Hình 2. Tìm các điện tích đã thiết lập trên tụ điện.

Đáp số: $q_1' = \frac{2q_1 - q_2 - q_3}{3}$;
$q_2' = \frac{2q_2 - q_1 - q_3}{3}$;
$q_3' = \frac{2q_3 - q_1 - q_2}{3}$.

Rõ ràng là sẽ không có gì thay đổi nếu chúng ta liên tục thay đổi cách đánh số các điện tích ($q_1 \rightarrow q_2, q_2 \rightarrow q_3, q_3 \rightarrow q_1$) - đây chỉ là một phép quay của bức tranh. Đáp số phải thể hiện tính đối xứng tương tự đối với các hoán vị tuần hoàn. Thật dễ dàng để xác minh rằng đáp số của chúng tôi có thuộc tính này.

Để thuận tiện cho controlROL, tính đối xứng trên các tham số trong đáp số phải được giữ nguyên.

3. Việc kiểm tra so sánh từng phần được thực hiện như sau. Chọn các giá trị đơn giản nhất của tham số điện tích mà đáp số rất mạnh và xem liệu công thức chung thu được cho các giá trị tham số cụ thể này có cho kết quả tương tự hay không.

Hãy quay lại bài toán về khối. Nếu khối lượng - $m_1$ hoặc $m_2$ - bằng 0 thì khối lượng còn lại rơi tự do và sợi dây không bị căng. Kết quả bằng 0 tương tự đến từ đáp số.

(Lưu ý rằng kết quả thu được chuyển sang 0 khi một trong các tham số bằng 0 thường là do tham số này được bao gồm trong đáp số dưới dạng số nhân, có lẽ ở một mức độ nào đó. Trong các bài toán phức tạp hơn, điều này chỉ xảy ra trong x trường hợp: đối với các giá trị rất lớn hoặc rất nhỏ ​​của tham số đã chọn.)

Chúng ta cũng hãy xem xét trường hợp khối lượng bằng nhau: $m_1 = m_2 = m$. Trong trường hợp này, tải đứng yên hoặc chuyển động đều. Do đó, lực căng không được bằng trọng lượng của một trong các nhóm. Dễ dàng nhận thấy công thức cho kết quả tương tự.

4. Đôi khi, khi kiểm tra so sánh từng phần, người ta phát hiện ra sự khác biệt giữa kết quả trong một trường hợp cụ thể và kết quả thu được từ công thức chung. Rõ ràng điều này được giải thích bởi thực tế là giá trị cụ thể của tham số được lấy ngẫu nhiên không nằm trong phạm vi giá trị có thể chấp nhận được. Khả năng đáng lo ngại như vậy cho thấy cần phải kèm theo đáp số kèm theo chỉ báo về phạm vi giá trị tham số cho phép.

Đây là một ví dụ điển hình:

Bài toán 3. Một lực $\vec{F}$ hướng xuống dưới một góc $\alpha$ so với đường chân trời tác dụng lên phấn có khối lượng $m$, nằm trên một bề mặt nằm ngang (Hình 3). Hệ số thời gian giữa phấn và bề mặt là $k$. Tìm gia tốc của vật.

Điển hình đáp số:

$$\vec{a} = \frac{|\vec{F}| \cos \alpha - k (mg + |\vec{F}| \sin \alpha)}{m x}.$$

Hình 3.

⟦folio 43⟧

Rõ ràng, nếu cơ thể không bị kéo thì nó sẽ không tăng tốc. Hãy kiểm tra điều này: tại $|\vec{F}| = 0$ $|\vec{a}| = -kg \neq 0!$ Có chuyện gì vậy?

Hóa ra đáp số đúng phải như thế này:

$$\begin{align*}
|\vec{a}| &= \frac{|\vec{F}| \cos \alpha - k (mg + |\vec{F}| \sin \alpha)}{m} \\
\text{при } |\vec{F}| > \frac{kmg}{\cos \alpha - k \sin \alpha}, \\
|\vec{a}| = 0 \text{ при } 0 \leq |\vec{F}| \leq \frac{kmg}{\cos \alpha - k \sin \alpha}.
\end{align*}$$

Do đó, đối với $|\vec{F}| = 0$, bạn không cần sử dụng công thức thứ nhất mà là công thức thứ hai, và sau đó không thấy mâu thuẫn.

Tóm lại, chúng tôi lưu ý rằng bất cứ khi nào có sự khác biệt dưới dấu căn hoặc logarit xuất hiện trong đáp số, thì bắt buộc phải tìm phạm vi các giá trị có thể chấp nhận được. Cần đặc biệt chú ý đến sự khác biệt về mẫu số; trong trường hợp này, bạn cần nhanh chóng kiểm tra xem giá trị nào

$$x = \frac{m}{M} L \quad \text{или} \quad x = \frac{m}{M + m} L.$$

(Xem xét các trường hợp giới hạn.)

1. Một chiếc thuyền có chiều dài $L$ và khối lượng $M$ đứng với mũi tàu ép vào bờ. Một người đàn ông to lớn $m$, muốn vào bờ, bắt đầu đi bộ từ đầu thuyền. Hỏi khoảng cách $x$ thuyền sẽ di chuyển ra xa bờ khi một người tới mũi thuyền? Không cần quyết định bài toán, hãy tìm ra cái nào trong hai cái đáp số đúng:

$$x = \frac{m}{M} L \quad \text{или} \quad x = \frac{m}{M + m} L.$$

2. Vẽ đồ thị gần đúng về sự phụ thuộc của phép chiếu $f$ vào trục quang của lực áp suất ánh sáng lên thấu kính từ khoảng cách $x$ đến nguồn sáng chính xác nằm trên trục quang chính của thấu kính. Hãy coi kích thước của thấu kính là lớn không giới hạn và không tính đến sự phản xạ và hấp thụ ánh sáng của thấu kính. (Ví dụ: trong những trường hợp đặc biệt, hãy xem xét những điều sau: $x=0$, $x=F$ (Tiêu cự F của ống kính), $x=2F$, $x \to \infty$.)

(Phần đầu xem trang 20, 32)

27, 29a); A. Nursimov (Alma-Ata) 16a), 6), 21; I. Nyzhnik (Novosibirsk) 21; A. Okropidze (Tbilisi) 26; A. Oparin (Moscow) 16, 18, 19a), 21, 22, 236), 24, 26-29, 30a); A. Pavlychev (Riga) 26; A. Palandein (Yerevan) 26; E. Palosh (Voroshilovgrad) 16a), 21, 26; A. Pantelev (Rostovna-Don) 26; V. Pitenko (quận Pukhovnichiy, vùng Minsk) 27, 28; A. Pizzevsky (Voronezh) 26; T. Podstritsan (Lviv) 19a), 21, 26-28, 30a); L. Polterovich (Moscow) 16, 24; A. Popelokhin (Kyiv) 16, 21, 22, 23a), 24, 26-28; S. Poshekhonov (Engels) 26; V. Protshin (làng Peschanoe, vùng Pavlodar) 16a); Ch. Puritsashashili (Tbilisi) 16a), 26; A. Purzv (MPR) 26; S. Putintsev (Nevinnomysk) 16-25; V. Rabinovich (Tula) 16, 22, 26, 30a); D. Ramzaev (Tbilisi) 26; V. Rozozin (Shelkovo) 16a), 6); I. Roizman (thị trấn Kaliinivka, vùng Vinnytsia) 27, 28, 30a); I. Savenkov (làng Lysye Gory, vùng Saratov) 16, 27, 28, 30a); Yu. Saenko (Zhdanov) 26, 30a); I. Sanartsev (Ufa) 21; A. Sarimelia (Tbilisi) 26-28, 30; S. Sevastyuk (Nevinnomysk) 16a), 6); M. Sevryuk (Moscow) 16-24, 26-30; P. Selivanov (Semipalatin) 21, 22, 23a); A. Sivatsky (Leningrad) 16, 18, 19, 21, 22, 24, 26, 28, 30a); S. Sidorenko (Bryansk) 18; M. Sluts (Moscow) 21; A. Sromin (Leningrad) 21, 26, 28;

S. Stadichenko (Penza) 16a), 6), 21, 22, 24, 26, 28; M. Streshinsky (Donetsk) 21; F. Sukochev (Tashkent) 16-29; O. Tavets (Minsk) 16a), 27; R. Tatsev (quận Masalli của AzSSR) 26; K. Tatalyan (Yerevan) 16, 19a), 21, 27-29, 30a); D. Timofeev (Gorky) 16a); M. Torosyan (Yerevan) 16a), 6), 18, 20-22, 24, 26, 27; N. Trifonov (Kansk) 16a), 6), 19a), 20-22, 25, 26, 28; V. Trofimov (Moscow) 27; Yu. Trofimuk (thị trấn Kaliinivka, vùng Vinnytsia) 26; D. Turaev (Gorky) 18, 19a), 20, 26, 27, 30a); V. Umansky (Baku) 16a), 6), 21, 27, 28; A. Unayan (Sevan) 21, 22, 24; A. Famullayev (Baku) 26; S. Khosid (Alma-Ata) 16, 18, 19, 21, 24, 26, 28; K. Christmov (NRB) 16, 18, 19a); L. Tsalenko (Moscow) 16, 19a), 21, 22, 24, 26, 28; Z. Tsikhistavi (Telavi) 16a), 21; A. Chaplesin (Nikolaev) 16a), 6), 18, 19a); O. Chechel (Moscow) 26-28; V. Sharafyan (Yerevan) 18, 26; N. Sharomet (Moscow) 21, 28; G. Shakhbazyan (Leningrad) 19a); E. Shklarr (Gomel) 21; V. Shamenko (Angarsk) 26; M. Ereshev (Fergana) 16a), 6); A. Yalitsev (Tula) 16, 19a), 26, 30a); V. Yasinsky (Vinnitsa) 21.

Vật lý

V. Abadzhaev (Lviv) 28, 31; K. Abdukhalikov (Alma-Ata) 23, 24; E. Abramochkin (Kuibyshev) 24; E. Alexandrova (Glazov) 24, 26, 28, 29, 31; A. Ashkinazi (Moscow) (Cuối cùng, xem trang 58)
