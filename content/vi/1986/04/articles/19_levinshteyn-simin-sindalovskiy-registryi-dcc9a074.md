---
id: 1986-4-levinshteyn-simin-sindalovskiy-registryi-dcc9a074
issue: kvant_1986_4
year: 1986
number: "4"
title: Đăng ký
authors:
  - Левинштейн М. Е.
  - Симин Г. С.
  - Синдаловский В. Я.
rubric: raznoe
rubric_sub: Разное
page_first: 48
page_last: 49
page_labels: 46-47
tag: U7MX
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 27efb98108eebdc9e4d0f680327b21afea2f84f9e0b04b76a4dec5014e2b4f25
prompt_sha256: draft-1
translated_from: content/ru/1986/04/articles/19_levinshteyn-simin-sindalovskiy-registryi-dcc9a074.md
source_content_sha256: 0730eb4bb342f385368f0c2a7abe4f3181cda73855ad57df582efe0d826bd16d
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 46⟧

VIII. Đăng ký

Tiến sĩ Khoa học Vật lý và Toán học M. E. LEVINSHTEIN, Ứng viên Khoa học Vật lý và Toán học G. S. SIMIN, V. Y. SINDALOVSKY

Một máy tính thường được so sánh với một sinh vật sống. Trong cơ thể phức tạp này, vai trò của trái tim do bộ tạo đồng hồ đảm nhiệm, thiết lập nhịp điệu của máy và vai trò của bộ não do bộ xử lý điều khiển mọi hoạt động bắt nguồn từ máy tính. “Mắt” và “tai” của máy tính là thiết bị đầu vào thông tin, “hệ thần kinh” là một mạng lưới dây dẫn phức tạp hợp nhất các phần tử của máy tính thành một tổng thể duy nhất và “lời nói” là thiết bị nhập kết quả thu được.

Trong sinh vật phức tạp này, chúng tôi đã nghiên cứu hoạt động của các tế bào đơn lẻ - bóng bán dẫn. Chính từ những “tế bào” như vậy – bóng bán dẫn sinh học hoặc hiệu ứng trường – mà hầu hết các bộ phận của máy tính đều được cấu thành. Nếu không nghiên cứu cách cấu trúc và cách thức hoạt động của một tế bào thì không thể hiểu được toàn bộ công việc của một tổ chức. Nhưng mặt khác, rõ ràng là việc giới hạn bản thân chỉ làm quen với một tế bào đơn lẻ sẽ không tiến xa đặc biệt trong việc nghiên cứu về một sinh vật phức tạp.

Trong phần này và các ghi chú tiếp theo, chúng ta sẽ thảo luận, làm ví dụ, làm thế nào, dựa trên các mạch logic và flip-flop đơn giản nhất trên bóng bán dẫn mà chúng ta đã nghiên cứu, các mạch điện tử vô tuyến phức tạp hơn được tạo ra để đóng vai trò trực tiếp như các nút máy tính - đăng ký và bộ cộng.

Như chúng ta biết, tất cả thông tin được lưu trữ và xử lý trong máy tính được trình bày dưới dạng số được viết bằng hệ thống kép. Các thanh ghi được sử dụng trong máy tính để ghi, lưu trữ và đọc số.

hình hiển thị sơ đồ đăng ký đơn giản để ghi các số có bốn chữ số (trên thực tế, đăng ký của máy tính hiện đại có thể chứa tối đa 64 chữ số). Thanh ghi bao gồm các phần tử lưu trữ - flip-flop, mạch “AND” đầu vào cho phép ghi và mạch “AND” đầu ra cho phép đọc một số.

Hãy chú ý đến biểu tượng kích hoạt. Nó tương tự như ký hiệu của các mạch logic khác, nhưng có chữ “T” ở góc trên bên phải. Hai đầu vào của trigger được ký hiệu bằng các chữ cái S (từ tiếng Anh set - set) và R (từ từ reset - return, recovery). Sự khác biệt giữa các đầu vào là tương đối - chúng hoàn toàn chạy bằng điện.

Đây là cách RAM của máy tính hiện đại hoạt động. Mạch tích hợp silicon có thể nhìn thấy trên bảng mạch in. Thời gian ghi và đọc của bộ nhớ như vậy là 50–100 ns.

Khi thực hiện các phép tính với số lớn, chúng ta sử dụng cách biểu diễn số sau:

0.123826·10⁵ Cơ sở thứ tự nam châm của hệ thống số

Trong điện trở máy tính, nó được sử dụng theo cách tương tự để biểu diễn các số với điểm khác biệt duy nhất là cơ số của hệ thống số là 2 (hệ nhị phân), còn mantissa và thứ tự ký hiệu nằm trong hệ nhị phân.

Ghi số 4,5 vào điện trở máy tính 9-rd:

1 2 3 4 5 6 7 8 9

1 0 0 1 1 1 0 0 1

ký thứ tự ký nam châm mantissa.

Chữ số đầu tiên của điện trở được phân bổ để ghi dấu của số (mantissa). Số 1 trong chữ số tương ứng với một phút, 0 - cộng. Chữ số thứ hai hiển thị dấu thứ tự. Trong ví dụ này, lệnh có dấu cộng. Bit 3 đến 5 được dành riêng để ghi thứ tự; trong ví dụ này thứ tự là +3. Các bit từ 6 đến 9 được sử dụng để viết mantissa kép. Đơn vị ở chữ số thứ 6 tương ứng với 2⁻¹, ở chữ số thứ 7 - 2⁻², ở chữ số thứ 8 - 2⁻³, v.v. Do đó, số được viết - (1·1/2 +0×(1/4+0·1/8+1·1/16)). 2³ = -4,5.

Trong ví dụ đã cho, mantissa có thể thay đổi từ

⟦folio 47⟧

- $\frac{15}{16}$ đến + $\frac{15}{16}$ và thứ tự từ - 7 đến + 7. Trong máy tính dòng EC, các số từ $\approx 5,4 \cdot 10^{-79}$ đến $\approx 7,2 \cdot 10^{75}$ được lưu trữ trong các chốt 32 bit.

Trong tương lai gần, VIC silicon sẽ được thay thế bằng IC RAM dựa trên vật liệu bán dẫn. Bức ảnh cho thấy một tế bào của một IC như vậy có kích thước 62×65 micron. Các bóng bán dẫn hiệu ứng trường có trong mạch có cổng dài 1 micron. Con chip có dung lượng bộ nhớ 4 kbit chứa 26.600 bóng bán dẫn hiệu ứng trường và có kích thước 5,6 × 6 mm. Lót IS - 2 IS.

Dung lượng RAM không đủ cho lời giải phức tạp bài toán trên máy tính. Phần chính của thông tin được lưu trữ trong bộ nhớ ngoài, có dung lượng lớn hơn nhiều, mặc dù chậm hơn. Bức ảnh cho thấy một thiết bị bộ nhớ ngoài trên băng từ, hơi giống một magnetfon cuộn-qua-cuộn thông thường. Một đai dài 750 m có thể chứa tới 6 ml. Số 32-bit. Thời gian đọc toàn bộ băng là 6-7 phút.

Chennault là tương đương. Đầu vào $R$ được sử dụng để đặt trạng thái “không” ban đầu của flip-flop và đầu vào $S$ được sử dụng để cung cấp tín hiệu cần lấp đầy. Đầu ra của flip-flop, chẳng hạn như được đặt bằng “1” khi “1” được áp dụng cho $S$, được gọi là đầu ra chính (lựa chọn trên trên hình 1) và lựa chọn thứ hai, chẳng hạn như nó nghịch đảo với tín hiệu đầu vào, được gọi là bổ sung. Đảo ngược, như trong sơ đồ loại “KHÔNG”, được biểu thị bằng một vòng tròn.

Đầu vào “cài đặt không” $R$ của tất cả các flip-flop đều được kết nối; Trước khi ghi, tín hiệu “1” được áp dụng cho chúng, do đó tín hiệu “0” được đặt ở tất cả các đầu ra chính của bộ kích hoạt.

Hãy xem một số được ghi vào sổ đăng ký như thế nào. Mỗi mạch AND đầu vào có hai đầu vào. Một trong số chúng (thấp ở hình 1) là phổ biến cho tất cả các chương trình. Dây kết nối các đầu vào chung này được gọi là bus ghi (RW). Nếu điện áp bằng 0 được đặt vào bus ghi, thì tất cả đầu ra của mạch “AND” cũng sẽ có điện áp bằng 0, bất kể tín hiệu ở đầu vào “tín hiệu” thứ hai - đây là đặc tính của mạch “AND” (xem ghi chú ở số 1, 2 «Kvant», 1986). Tuy nhiên, nếu tín hiệu “1”—quyền ghi—được cung cấp cho bus ghi RAD, thì điện áp ở đầu ra của mạch “AND”, và do đó ở đầu vào $S$ của bộ kích hoạt, sẽ phụ thuộc vào tín hiệu nào được nhận tại thời điểm đó trên tín hiệu đầu vào thứ hai của mạch “AND”.

hình 1 lấy số 9 (1001) làm ví dụ. Ở chữ số thứ nhất và thứ tư ở đầu vào tín hiệu có tín hiệu “1”. Nếu cũng có tín hiệu “1” trên bus RAC, thì tín hiệu “1” sẽ được nhận ở đầu vào $S$ của flip-flop chữ số thứ 1 và thứ 4, tín hiệu này sẽ “lật” các flip-flop này. “1” sẽ được viết ở chữ số thứ 1 và thứ 4. Ở bit 2 và 3, trong đó có “0” ở đầu vào tín hiệu, cũng sẽ có “0” ở đầu ra của mạch “AND” và “0” vẫn được ghi trong bộ kích hoạt.

Hoạt động của mạch “AND” đầu ra tương tự như hoạt động của mạch đầu vào. Ngay khi tín hiệu “1” được áp dụng cho bus đọc (MF), tín hiệu “1” sẽ xuất hiện ở đầu ra của mạch “AND” trong các bit trong đó “1” được ghi ở đầu ra chính của bộ kích hoạt.

Trong các mạch thực hiện flip-flop. Ở những đầu ra này, cái gọi là “mã đảo ngược” của số được viết sẽ được tạo ra, trong đó “0” thay cho “1” và ngược lại. Mã ngược được sử dụng trong máy tính để thực hiện một số phép tính số học với số kép.

Tập hợp các bản ghi sử dụng máy tính để điền vào chương trình làm việc, dữ liệu ban đầu và trung gian của các phép toán được gọi là RAM. RAM của một trong những máy tính nội địa lớn “VESM-6” chứa 32768 (32768=2$^{15}$) thanh ghi, mỗi thanh ghi cho phép lưu trữ các số kép 48 bit.

RAM được yêu cầu phải rất nhanh vì nó phải có khả năng ghi và đọc số với tốc độ tương đương với tốc độ máy thực hiện phép tính. Trong số các giao diện mạch công nghiệp hiện đại, IC dựa trên bóng bán dẫn lưỡng cực silicon được chế tạo nhanh nhất. Vì vậy, RAM của các máy tính lớn được cấu tạo từ các mạch logic và flip-flop trên các bóng bán dẫn lưỡng cực.

Các thanh ghi của máy vi tính được thực hiện trên cơ sở các bóng bán dẫn MOS hữu ích. Tốc độ của bộ nhớ như vậy thấp hơn nhiều, nhưng các bóng bán dẫn MOS này tiêu thụ ít năng lượng hơn nhiều. Nhờ máy tính vi mô này, có thể đạt được hàng chục giờ hoạt động trên một cục pin thu nhỏ.
