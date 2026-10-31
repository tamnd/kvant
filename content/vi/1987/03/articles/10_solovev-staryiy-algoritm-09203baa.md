---
id: 1987-3-solovev-staryiy-algoritm-09203baa
issue: kvant_1987_3
year: 1987
number: "3"
title: Thuật toán cũ
authors:
  - Соловьёв Ю. П.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 36
page_last: 39
page_labels: 34-37
tag: EURS
lang: vi
source: kvant_digital
extraction: vision
content_sha256: e5b9ab55c8ae55c080710b2838fa376ecfb671ae94d473f2b2f0c39a16dcbe06
prompt_sha256: draft-1
translated_from: content/ru/1987/03/articles/10_solovev-staryiy-algoritm-09203baa.md
source_content_sha256: 16017a28ac0436ffeca98ae09957bbcf5bcb2095f3a1dfb7e27964ba06dfd0f3
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 34⟧

Hôm nọ, con trai Sasha của tôi (nó là học sinh lớp bảy) đến gặp tôi:
— Mua cho tôi một chiếc máy tính như của Vova!
- Trước hết, bạn có một chiếc máy tính, nhưng bạn đã biến nó thành cái gì? Bây giờ anh ấy cùng nhau trưng bày một số hình chạm khắc! Thứ hai, học sinh phải có khả năng đếm mà không cần máy tính. Thứ ba, vậy thôi, tuần này tôi sẽ mang máy tính đi sửa.
“Bạn không cần phải mang máy tính đến xưởng,” Sasha trả lời tôi, “Tôi có thể cộng, nhân và chia một cách khéo léo.” Tôi cần giải một phương trình bậc hai và nghiệm là số nào: 16229! Trong sách giáo khoa, số lớn nhất trong bảng là 10.000. Nhưng máy tính của Vova tính căn bậc hai.
- Bạn có muốn tôi dạy bạn cách tính căn thức mà không cần máy tính không?
- Có khó không?
- Không khó hơn nhiều so với phép chia. Nghe đây.

Nhiều phương pháp rút căn bậc hai “bằng tay” đã có từ thời cổ đại. Tôi sẽ kể cho bạn nghe về một phương pháp như vậy, được tạo ra vào thế kỷ 15 và đã phục vụ cả học sinh và các nhà khoa học trong nhiều năm.

Để giải phóng phương pháp này, chỉ cần xem xét một vài ví dụ là đủ.

Đầu tiên, hãy xem xét trường hợp căn nguyên được trích xuất hoàn toàn, nghĩa là khi số đó là một số chính phương. Ví dụ, chúng ta hãy tìm gốc của số 294.849.

Thể tích của các chữ số có trong số này được chia từ phải sang trái thành nhóm gồm hai chữ số (hình 1, a). Nhóm ngoài cùng bên trái sẽ được gọi là nhóm thứ nhất, nhóm tiếp theo - nhóm thứ hai, v.v. Tổng số nhóm được hình thành xác định số chữ số của gốc độc quyền.

Chữ số đầu tiên được tìm thấy là giá trị nguyên của gốc từ nhóm đầu tiên có nhược điểm. Trong trường hợp của chúng tôi, đây là chữ số 5. ​​Chúng tôi viết nó bằng đáp số, sau đó bình phương nó, trừ nó khỏi nhóm đầu tiên và phương thức để có kết quả trừ nhóm tiếp theo. (Nếu kết quả của phép trừ bằng 0 thì chúng ta chỉ cần loại bỏ nhóm tiếp theo.) Trong ví dụ đang xem xét, sẽ thu được số 448 (hình 1, b).

Hãy chuyển sang việc xác định số thứ hai. Để làm điều này, ở bên trái của số kết quả 448, hãy vẽ một đường thẳng đứng và viết đằng sau nó vị trí của hàng chục, chữ số đầu tiên nhân đôi: $2 \times 5 = 10$ (hình 1, s).

Thay cho đơn vị, chúng ta đặt một tổng lớn hơn chữ số $a$, trong đó hiệu $448 - 10a \cdot a$ không âm, tức là dương hoặc bằng 0. Rõ ràng rằng trong trường hợp của chúng ta đây là chữ số 4. Chúng ta nhập chữ số này vào đáp số (hình 1, e).

Nhân 104 với 4 và viết kết quả vào bên phải hàng dọc. Chúng tôi tính toán sự khác biệt $448 - 416 = 32$ và phương pháp tính chênh lệch như sau. Thay cho đơn vị, chúng ta đặt một tổng lớn hơn chữ số $b$, trong đó hiệu $3249 - 108b \cdot b$ là không âm. Bằng cách lựa chọn, chúng tôi tin rằng với $b = 3$ sự khác biệt này bằng

⟦folio 35⟧

không. Chúng ta đặt $b=3$ vào đáp số (hình 1, ​​​​e).

Chúng ta nhân 1083 với 3, viết kết quả vào bên phải đường thẳng đứng rồi trừ đi 3249 (hình 1, g).

Vì chênh lệch bằng 0 nên quá trình tính nghiệm đã hoàn tất.

Bây giờ, nhìn vào hình 2 và 3, hãy thử lặp lại tất cả các bước cần thiết để tự mình tính căn bậc hai $\sqrt{212521}$ và $\sqrt{165649}$.

Cho đến cxx chúng ta đã xem xét các số có bốn chữ số. Nếu tổng số chữ số là số lẻ thì nhóm đầu tiên bên trái sẽ chỉ gồm một chữ số (hình 4, 5).

Chà, phải làm gì nếu số đó không phải là một hình vuông hoàn hảo? Trong trường hợp này, thuật toán không thay đổi; bạn chỉ cần chuẩn bị số lượng chính xác. Vì vậy, giả sử $N$ là một số nào đó (không nhất thiết phải là số nguyên) được biểu thị bằng phân số thập phân và chúng tôi muốn tính toán gốc của nó một cách chính xác

⟦folio 36⟧

đến $\frac{1}{10^{10}}$, tức là chúng ta muốn tìm các số ở dạng thập phân của gốc ban đầu bao gồm cả vị trí thập phân $m$. Sau đó chúng ta sẽ build như sau. Các chữ số nằm trong phần nguyên của số $N$ được chia thành các nhóm gồm hai chữ số, mỗi chữ số từ phải sang trái và các chữ số tạo thành phần phân số được chia thành các nhóm giống nhau, nhưng từ trái sang phải. Nếu tổng số chữ số ở phần nguyên là số lẻ thì nhóm đầu tiên bên trái sẽ gồm một chữ số, nhưng nếu số chữ số ở phần phân số là số lẻ thì chúng ta gán số 0 cho chữ số cuối cùng bên trái. Khi số lượng nhóm trong phần phân số lớn hơn $m$, chúng tôi loại bỏ các nhóm bổ sung ở bên phải; khi nó nhỏ hơn $m$, chúng ta tạo thành các nhóm còn thiếu từ 0. Bây giờ mọi người đã sẵn sàng sử dụng thuật toán của chúng tôi. Hình 6 và 7 thể hiện cách tính

⟦folio 37⟧

căn bậc hai $\sqrt{2}$ và $\sqrt{12,5}$ lên đến $\frac{1}{1000}$.

Để kiểm tra xem bạn có nắm vững thuật toán này hay không, hãy tiếp tục làm các bài tập sau: Tính căn bậc hai của $\sqrt{18769}, \sqrt{24336}, \sqrt{35721}, \sqrt{232324}, \sqrt{243049}, \sqrt{104,2441}, \sqrt{1867,1041}, \sqrt{7}, \sqrt{10}$, chính xác đến $\frac{1}{1000}$.

Chúng tôi sẽ không giải quyết vấn đề biện minh cho thuật toán được mô tả. Chúng tôi chỉ lưu ý rằng việc thu được mỗi chữ số mới có liên quan đến số lượng phép tính ngày càng tăng, do đó, sẽ hợp lý khi sử dụng thuật toán khi độ chính xác yêu cầu không vượt quá ba đến bốn chữ số có nghĩa (theo quy luật là đủ cho các phép tính thực tế).

Độ chính xác của các phép tính sử dụng thuật toán đã chỉ định có thể tăng lên nếu bạn sử dụng câu lệnh sau:

Nếu sau khi tính $n$ chữ số có nghĩa của căn, phần vôi hóa còn lại được chia cho hai lần giá trị tìm được của căn, thì thương sẽ cho $n-1$ của các chữ số tiếp theo của căn.

Hãy chứng minh nhận định này. Trước tiên, chúng ta hãy giả sử rằng số $a$ mà gốc được lấy có phần nguyên của các nhóm $n$. Hãy tìm $n$ trong số các chữ số đầu tiên của căn thức tạo thành số $c$. Khi đó $\sqrt{a}=c+x$, trong đó $x$ là phần phân số của nghiệm cần tìm. Kể từ đây,

$$a=c^2+2cx+x^2,$$
$$\frac{a-c^2}{2c}=x+\frac{x^2}{2c}.$$

Sự khác biệt $a-c^2$ là số dư thu được sau khi tìm các chữ số $n$ của gốc. Phân số $\frac{a-c^2}{2c}$ đại diện cho thương số được đề cập trong câu lệnh.

Đó là lý do tại sao

$$x=\frac{a-c^2}{2c}-\frac{x^2}{2c}.$$

Đếm $x \approx \frac{a-c^2}{2c}$, chúng tôi cho phép sai số bằng $\frac{x^2}{2c}$. Vì $x<1$, $a \geq 10^{n-1}$, chúng tôi có những gì được yêu cầu. Nếu dấu phẩy ngăn cách phần nguyên và phần phân số trong số $a$ không phải là nơi chúng ta mong đợi, thì nó luôn có thể được chuyển đến vị trí thích hợp bằng cách nhân hoặc chia số $a$ cho lũy thừa nào đó $10$ với số mũ chẵn, sau đó chia hoặc nhân căn nghiệm tìm được với lũy thừa $10$ với số mũ lớn bằng một nửa.

Hãy xem một ví dụ. Hãy tính $\sqrt{2}$ với giá trị có bảy chữ số, nghĩa là có sáu chữ số sau dấu thập phân. Trước đây chúng tôi đã tính $\sqrt{2}$ với các chữ số thập phân (hình 6). Chia phần còn lại cho hai lần căn sẽ có ba (hình8) sau đây.

Tất nhiên, ở thời đại chúng ta, khi hầu hết học sinh lớp một đều mang theo một chiếc máy tính vi mô trong cặp, không dễ để gây ngạc nhiên cho một học sinh bằng phương pháp trích căn bậc hai thủ công. Nhưng chúng tôi vẫn hy vọng. Nhà toán học nổi tiếng người Mỹ, Viện sĩ Graham kể lại rằng lần đầu tiên ông cảm thấy rất hứng thú với toán học ở trường tiểu học, sau khi nhìn thấy chính thuật toán nhận biết căn bậc hai mà chúng ta vừa nói đến. Ông tự hỏi liệu có thể làm điều gì đó tương tự đối với các căn bậc ba và các căn bậc cao hơn hay không. Anh đã tìm ra một phương pháp tương tự lời giải, và kể từ đó toán học luôn đi vào cuộc sống của anh.

Danh sách độc giả gửi đúng lời giải

(Bắt đầu trang trên trang 29)

09, 11; S. Tyurin (làng Pravdinsk, vùng Gorky) 09, 11; A. Usinsky (làng Ptichya, vùng Rivne) 09; D. Feldman (làng Chernogolovka, vùng Moscow) 03, 05; D. Filatev (Alma-Ata) 99; G. Finkelshtein (làng Chernogolovka, vùng Moscow) 03–05, 07–12; F. Fot (Tomsk) 03, 05; A. Lông thú (p/o Drichin, vùng Minsk) 09, 11; M. Kharaba (làng Nadrechnoye, vùng Ternovol) 04; P. Khil (làng Ovidno-pol, vùng Odessa) 03; D. Khodorovskaya (Kyiv) 04; I. Chaika (làng Kuznetsov, vùng Rivne) 99, 05, 07, 08, 11; O. Chepikov (Mogilev) 03, 09, 11; I. Shekhtman (Kyiv) 04, 05, 09; A. Shshikin (Novy Urengoy) 09; A. Shulyak (làng Molodetskoe, vùng Cherkasy) 11; N. Yudina (làng Maina, vùng Ulyanovsk) 11; V. Yaylyan (Shostka) 03; I. Ykovleva (Kyiv) 04; Yu. Yarovoy (Kyiv) 99, 09.
