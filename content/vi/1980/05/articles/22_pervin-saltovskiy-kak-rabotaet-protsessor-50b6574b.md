---
id: 1980-5-pervin-saltovskiy-kak-rabotaet-protsessor-50b6574b
issue: kvant_1980_5
year: 1980
number: "5"
title: Bộ xử lý hoạt động như thế nào
authors:
  - Первин Ю. А.
  - Салтовский А. Н.
rubric: raznoe
rubric_sub: Разное
page_first: 58
page_last: 63
page_labels: 56-61
tag: QZG4
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 05b4eb378af1aa3f7acffbc3db31cd7c10dbfa937291bda2bb12a6720c907977
prompt_sha256: draft-1
translated_from: content/ru/1980/05/articles/22_pervin-saltovskiy-kak-rabotaet-protsessor-50b6574b.md
source_content_sha256: 80c0214044bd370f850d24b87624ef1b652843e9ec97835c76eb462be1ba493f
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 56⟧

Bộ xử lý hoạt động như thế nào

Kiến trúc máy tính

Máy tính điện tử hiện đại là một tổ hợp phức tạp gồm các thiết bị và bộ phận, được ngưỡng mộ vì sự hoàn hảo về mặt công nghệ và sự đa dạng của các nguyên tắc hoạt động vật lý. Hãy nhìn chiếc máy qua con mắt của một lập trình viên: hãy làm quen với các thiết bị chính của nó, mục đích của chúng, các kết nối tồn tại giữa chúng và nguyên lý hoạt động của các thiết bị này.

Sơ đồ khối đơn giản hóa (Hình 1) hiển thị các thiết bị sau tạo nên máy tính:

— Đơn vị logic số học (ALU) thực hiện các phép toán số học và logic trên dữ liệu đến từ Bộ nhớ. ALU có trong máy tính hiện đại có thể thực hiện nhiều hoặc nhiều hành động (thao tác) khác nhau. Ngoài các phép tính số học thông thường - cộng, trừ, nhân, chia - tập hợp các phép toán mà ALU có chứa các phép toán cho phép bạn chỉnh sửa thông tin. bài toán chính của thiết bị này là chuyển đổi thông tin nhận được từ Bộ nhớ.

- Bộ nhớ (P) (hoặc thiết bị lưu trữ - xem «Kvant», 1980, số 4) lưu trữ dữ liệu, cũng như thông tin điều khiển mọi công việc trong máy tính, tức là chương trình.

— Thiết bị đầu vào-đầu ra (IOU) là cơ quan giao tiếp giữa máy và con người. Với sự trợ giúp của máy tính, một người nhập chương trình và dữ liệu cần thiết để thực hiện chương trình vào máy tính, đồng thời nhận được kết quả ở dạng thuận tiện cho công việc tiếp theo: bảng, đồ thị, sơ đồ và bản vẽ. Thiết bị đầu vào là tai và mắt của máy, thiết bị đầu ra là lưỡi và tay.

— Thiết bị điều khiển (CU) điều phối toàn bộ hoạt động của máy tính và dẫn dắt các “nhà ngoại giao” trong việc liên lạc lẫn nhau giữa các thiết bị riêng lẻ.

Các phép toán số học và logic được thực hiện trong ALU với tốc độ cao, ước tính trong các máy tính hiện đại từ hàng trăm nghìn đến hàng chục triệu phép tính mỗi giây. Để đảm bảo toàn bộ hoạt động của máy có tốc độ cao, các quy trình liên quan đến truyền thông tin giữa các thiết bị - thay đổi dữ liệu, nhận nhiệm vụ mới, ghi lại kết quả - hoàn toàn tự động; đây là những gì CU điều khiển. Thiết bị điều khiển là một loại thiết bị điều khiển tập hợp các thiết bị tạo nên máy tính. “Bản nhạc” dành cho đạo diễn là một chương trình được ghi trước đó trong bộ nhớ. Mỗi thước đo của một bản nhạc, được chơi dưới sự hướng dẫn của UU, là một hành động cơ bản hoàn chỉnh: cộng hai số, so sánh hai đại lượng, v.v. Chính UU “thiết lập”

⟦folio 57⟧

ALU ra lệnh thực hiện một thao tác cụ thể, “quan tâm” đến việc lấy thông tin cần thiết cho thao tác này từ bộ nhớ và không “quên” ghi kết quả vào bộ nhớ khi kết thúc hành động hoặc gửi nó đến bộ điều khiển trên không.

Trong dòng thiết bị tạo nên máy tính, phức tạp nhất về mặt kỹ thuật là bộ nhớ tương đối của bộ điều khiển và ALU. Thực tế là bộ điều khiển không chỉ “thiết lập” ALU để thực hiện một thao tác nhất định, chẳng hạn như so sánh hai giá trị, mà còn “quan tâm” đến kết quả, tùy thuộc vào giá trị của kết quả này, lời giải được chấp nhận về việc thực hiện thêm chương trình. Mối quan hệ giữa ALU và bộ điều khiển được gọi là một tiến trình.

Tổ chức logic của một cỗ máy được gọi là kiến ​​trúc. Kiến trúc thể hiện trong Hình 1 được coi là cổ điển. Nó được đề xuất vào năm 1947 bởi nhà khoa học người Mỹ Von Neumann và chứa các tính năng chính của máy tính lời giải kiến ​​trúc hiện đại.

Thông tin kiểm soát là gì?

Theo phép tính gần đúng đầu tiên, hoạt động của máy tính có thể được biểu diễn như sau:

- thông tin điều khiển được lấy từ bộ nhớ. Theo quy định, đây là nội dung của một trong các ô của nó - một từ máy. Từ điều khiển này mã hóa các hướng dẫn toàn diện về hoạt động của các thiết bị của máy trong khoảng thời gian tiếp theo - trong một chu kỳ hoạt động của máy;

— Bộ điều khiển giải mã thông tin có trong từ điều khiển và tùy theo nghĩa của từ này sẽ đưa ra lệnh thực hiện các hành động cụ thể cho thiết bị máy tính tham gia thao tác;

— sau khi các thiết bị thực hiện công việc được giao, chúng sẽ báo cáo việc này cho Bộ điều khiển; sau đó các từ điều khiển tiếp theo sẽ được lấy từ bộ nhớ hoặc hai

Hình 2. Định dạng gần đúng của lệnh ba địa chỉ.

Nhiều luồng thông tin vào máy tính sẽ bị đình chỉ.

Từ điều khiển được gọi là lệnh. Một chuỗi các lệnh đại diện cho một chương trình ngôn ngữ máy. Các lệnh và dữ liệu dùng để xử lý cũng như kết quả thu được được lưu trữ trong bộ nhớ.

Mỗi ô nhớ, kể cả ô lưu trữ lệnh, đều có một địa chỉ (số của ô này). Mọi thông tin đều được tìm kiếm theo địa chỉ trong bộ nhớ, giống như một cuốn sách được tìm kiếm trong thư viện theo mục lục của nó, và một chiếc áo khoác để cất trong tủ quần áo được tìm kiếm theo số đã cấp.

Một nhóm thường được tạo thành từ nhiều thành phần (Hình 2).

Bản chất của việc quản lý thông tin mà nhóm cung cấp cho máy tính đang được xác định sớm. Nhìn chung, đây là một phần nhỏ của định dạng lệnh, chiếm 6-8 bit đối với nhiều mẫu máy tính. Ngoài hoạt động, lệnh còn chứa thông tin điều khiển sau:

- phần địa chỉ, bao gồm dữ liệu mà thao tác phải được thực hiện và địa chỉ của kết quả;

- địa chỉ của lệnh tiếp theo được chỉ định rõ ràng hoặc ngầm định, địa chỉ này sẽ cần được lấy từ bộ nhớ và được chấp nhận để sử dụng sau khi thực hiện lệnh hiện tại (hiện đang thực thi).

Máy bao gồm những gì?

Các thiết bị máy móc khác nhau là sự kết hợp của một số lượng lớn các phần tử - "gạch". Tuy nhiên, sự đa dạng của các yếu tố không quá lớn. Vì vậy, để làm quen chi tiết hơn với hoạt động của các thiết bị máy tính, cần tìm hiểu nguyên nhân hoạt động của các yếu tố này. Kiểm tra thiết bị bộ nhớ («Kvant», 1980, số 4), đầu đọc,

⟦folio 58⟧

Rõ ràng, ông đã thu hút sự chú ý đến bản chất rời rạc của thông tin được lưu trữ trong máy: cuối cùng, tất cả các thuộc tính được chia thành hai trạng thái, được gọi là 0 và 1. Các thiết kế phần tử khác nhau chỉ có thể đưa ra các triển khai kỹ thuật khác nhau đảm bảo nhận dạng được hai trạng thái như vậy. Ví dụ, hai mức điện áp - "cao" và "thấp" - có thể được nhận biết bằng các mạch điện tử sao cho "cao" có nghĩa là một và "thấp" có nghĩa là không.

Một trong những phần tử đơn giản nhất được thiết kế để điền vào một bit thông tin là bộ kích hoạt, về nguyên tắc rất giống với một công tắc hai vị trí thông thường, với điểm khác biệt duy nhất là nó được điều khiển không phải bằng tay mà bằng một tín hiệu điện duy nhất đến đầu vào của nó: nếu bộ kích hoạt ở trạng thái 0 thì nó “ghi nhớ” trạng thái này cho đến khi tín hiệu đơn tiếp theo đến; nếu bộ kích hoạt ở một trạng thái duy nhất, thì một tín hiệu duy nhất nhận được ở đầu vào của nó sẽ “đặt lại” nó về trạng thái 0, trạng thái này cũng được lưu trữ trong một thời gian dài vô tận cho đến khi có tín hiệu đơn tiếp theo.

Khả năng lưu trữ thông tin của bộ kích hoạt được sử dụng rộng rãi trong nhiều thiết bị lưu trữ khác nhau, trong đó đơn giản nhất là điện trở - một nhóm bộ kích hoạt được kết hợp để lưu trữ hoạt động của một số bit cố định, đặc biệt là từ máy. Sổ đăng ký là một phương tiện thuận tiện để lưu trữ trước thông tin. Với sự trợ giúp của điện trở, việc trao đổi thông tin giữa các thiết bị máy tính, thường hoạt động ở tốc độ khác nhau, được phối hợp một cách hiệu quả.

Trong quá trình thực hiện lệnh, các công tắc điều khiển điều khiển các tín hiệu và luồng thông tin. Việc chuyển đổi được thực hiện bằng cách sử dụng các mạch điện tử khác nhau. Đơn giản và phổ biến nhất trong số đó là:

- mạch trùng khớp (“và”) - tín hiệu tương ứng với giá trị “1” sẽ chỉ xuất hiện ở đầu ra của mạch “và” khi giá trị của tất cả các tín hiệu đầu vào tương ứng với giá trị “1” (Hình 3a);

- mạch lắp ráp (“hoặc”) - mạch này ít “nhạy cảm” hơn với các đặc tính của thông tin đầu vào: giá trị “1” xuất hiện ở đầu ra của nó mỗi khi giá trị “1” xuất hiện ở một đầu vào (Hình 36);

— mạch biến tần (“không”) tạo ra giá trị đầu ra ngược lại với đầu vào. Đã nhận

⟦folio 59⟧

Hình 4a. Lựa chọn các lệnh. Hình 46. ​​​​Giải mã mã hoạt động. Hình 4c. Chuyển học kỳ 1 sang ALU.

Với sự trợ giúp của bộ biến tần, hình ảnh thông tin “âm bản” (Hình 3c) đặc biệt được sử dụng để thực hiện thao tác trừ.

Các phần tử “và”, “hoặc”, “không” được sử dụng khi tạo các khối chức năng, là các thành phần của thiết bị máy tính: với sự trợ giúp của các phần tử này, có thể tạo ra các thiết bị có bất kỳ thuộc tính nào được xác định trước. Đặc điểm đặc trưng trong công việc tầm thường của các khối chức năng là tính chuyên môn hóa hẹp của chúng, đảm bảo rằng mỗi khối thực hiện một loạt trách nhiệm nghiêm ngặt. Các khối chức năng sau đây được ứng dụng rộng rãi trong việc tạo ra các thiết bị máy tính cá nhân:

— bộ cộng — trái tim của ALU; bộ cộng nhận biểu diễn kép của hai số làm đầu vào và tạo ra biểu diễn kép của tổng của chúng làm đầu ra;

- bộ mã hóa - chuyển đổi tín hiệu ở một trong các đầu vào của nó thành một bộ tín hiệu đầu ra tương ứng (ví dụ: thành mã hoạt động);

- bộ giải mã - thực hiện chức năng ngược lại với bộ mã hóa, nghĩa là, đối với mỗi tổ hợp tín hiệu đầu vào, nó chỉ phát ra tín hiệu đến một đường đầu ra; bộ giải mã được sử dụng, ví dụ,

trong bộ điều khiển để giải mã mã thao tác lệnh;

— bộ đếm — đếm số lượng tín hiệu rời rạc xuất hiện ở đầu vào của nó; Một bộ đếm, giống như một thanh ghi, bao gồm một số lượng hữu hạn các flip-flop.

Bộ xử lý thực hiện lệnh

Các quá trình xảy ra trong máy khi thực hiện lệnh được minh họa trong Hình 4a-4e. Đây là một loại hình ảnh tĩnh của một sự kiện, bao gồm việc thực hiện một lệnh. Các quá trình, như có thể thấy từ “chaas”, xuất hiện trong mỗi bức tranh và diễn ra theo thời gian. Tốc độ hoạt động chung của máy tính cao đòi hỏi phải có quy định chặt chẽ về thời gian cho mỗi lần trao đổi thông tin riêng biệt. Máy đếm nhịp, đồng hồ bên trong của máy, được gọi là máy tạo hạt đồng hồ.

Trước khi bắt đầu công việc, người vận hành máy tính chuẩn bị thông tin bắt đầu từ bảng điều khiển - địa chỉ của lệnh, người thực hiện trong chương trình này là địa chỉ đầu tiên. Thứ tự “khởi động” mà người vận hành đưa ra cho máy chủ yếu liên quan đến bộ điều khiển (Hình 4a). Các sự kiện tiếp theo diễn ra như sau:

— trước hết là quảng cáo-

⟦folio 60⟧

res của lệnh thực thi đầu tiên của chương trình; Điều này xác định vị trí trong bộ nhớ mà từ đó lệnh đang được xử lý có thể được truy xuất;
- sau khi nhận được lệnh bắt đầu công việc, bộ điều khiển chuyển nội dung của bộ đếm chương trình vào bộ nhớ dưới dạng địa chỉ của thông tin đang được tìm kiếm;
- việc truyền này đi kèm với lệnh cho bộ nhớ "cung cấp nội dung của ô được chỉ định vào thanh ghi lệnh";
- sau đó, lệnh được đọc từ ô nhớ có địa chỉ bằng nội dung của SC và được đặt trong điện trở lệnh (PK);
— Bộ điều khiển, sử dụng bộ giải mã, giải mã mã hoạt động của lệnh và thiết lập ALU để thực hiện thao tác (trong ví dụ của chúng tôi, “cộng hai số”, bắt đầu thực hiện thuật toán lệnh (Hình 46));
— địa chỉ của thuật ngữ đầu tiên (địa chỉ đầu tiên trong phần địa chỉ của lệnh nằm trong PK) được chuyển vào bộ nhớ; Bộ điều khiển cần xuất nội dung của địa chỉ này tới ALU; Điểm truyền trong đường truyền này là điện trở đọc thông tin (RSI) (Hình 4c);
- sau khi ALU chấp nhận nội dung của RSI là số hạng đầu tiên, đơn vị điều khiển bắt đầu lấy mẫu số hạng tiếp theo. Để thực hiện điều này, số ô lưu trữ thuật ngữ thứ hai (địa chỉ thứ hai trong phần địa chỉ của lệnh từ RK) sẽ được chuyển vào bộ nhớ và nội dung của ô này sẽ được chuyển qua RSI đến ALU (Hình 4d);
- sau khi nhận được cả hai thuật ngữ, ALU, sử dụng bộ cộng, thực hiện thao tác cộng và truyền kết quả đến điện trở thông tin đã ghi (REI) (Hình 4d);
— việc thực hiện lệnh cuối cùng là ghi lại nội dung của REI (kết quả) tại địa chỉ kết quả (địa chỉ thứ ba trong phần địa chỉ của lệnh tại Cộng hòa Kazakhstan) (Hình 4e).

Thứ tự thực hiện các lệnh được xác định như thế nào?

Lệnh tiếp theo sẽ được tự động truy xuất từ ​​bộ nhớ: việc hoàn thành lệnh được ghi lại bằng cách thêm 1 vào nội dung của bộ đếm chương trình, do đó lệnh tiếp theo được thực thi sẽ là lệnh được lưu trong ô tiếp theo, liền kề. Hai lệnh đặc biệt có thể thay đổi trình tự này: nhảy không điều kiện và nhảy có điều kiện. Mục đích chính của chúng là thay đổi nội dung của bộ đếm chương trình. Lệnh nhảy vô điều kiện chứa trong phần địa chỉ của nó thông tin về địa chỉ của lệnh tiếp theo. Cái này

⟦folio 61⟧

thông tin thay thế (thay thế) nội dung của bộ đếm lệnh, bất kể mọi tình huống có thể xảy ra trong quá trình thực hiện lệnh trước đó. Ví dụ: một lệnh điều kiện kết quả chọn một hoặc một lệnh khác làm lệnh tiếp theo: địa chỉ của các lệnh tiếp theo có thể có (rõ ràng hoặc ngầm định) trong phần địa chỉ của lệnh điều kiện.

Tại sao cần có sự gián đoạn trong quá trình thực hiện chương trình?

Ngoài cách thay đổi trình tự lệnh có chủ ý mà các chương trình cung cấp với các lệnh nhảy có điều kiện và vô điều kiện, còn có các cách thay đổi trình tự thông thường bằng “phần cứng” (máy bên trong), cho phép, theo một số nguyên tắc quan trọng và đặc biệt, làm gián đoạn việc thực hiện chương trình và bắt đầu thực hiện một chương trình khác. Khi một nguyên tắc gây ra ngắt xuất hiện, nội dung của bộ đếm chương trình trước tiên sẽ thay đổi: nó nhận được địa chỉ ngắt. Thực tế là thông thường mỗi lớp được gán địa chỉ cố định riêng; nó thường được "tìm thấy" bằng cách sử dụng bộ mã hóa. Các địa chỉ ngắt cố định chứa các hướng dẫn để chuyển sang chương trình con (xử lý ngắt tương ứng). Các lệnh này là “họ hàng gần” của lệnh chuyển giao vô điều kiện đã được biết đến rộng rãi. Sự kết hợp đáng chú ý giữa phần mềm và phần cứng được thiết kế để phản ứng nhanh với các sự kiện khẩn cấp được gọi là hệ thống ngắt. Các hành động của liên minh này nhằm mục đích “chụp ảnh” các sự kiện xảy ra trong máy tính tại thời điểm xảy ra gián đoạn. "Chụp ảnh" giúp khôi phục máy về chế độ trình tự sau khi nguyên tắc gián đoạn đã được thỏa mãn hoặc loại bỏ. Những thứ kia-

Cuộc điện thoại làm gián đoạn việc đọc sách và sau khi nói chuyện với người nhận, bạn quay lại cuốn sách. Đặc biệt là cho cuốn sách, không phải cho ấm đun nước. Hơn nữa, bạn tiếp tục đọc chính xác từ trang mà việc đọc bị gián đoạn. Máy tính “nhận ra” lý do gián đoạn giống như cách bạn nhận ra giọng nói của một trong những người bạn của mình.

Có thể có nhiều lý do cho sự gián đoạn. Dưới đây là một số trong số họ:
- máy liên tục giám sát tính chính xác của thông tin được truyền hoặc nhận: phát hiện lỗi;
- xảy ra lỗi xử lý;
- có lỗi trong chương trình.
Khả năng gián đoạn trong khi sử dụng chương trình cho phép bạn kiểm soát các quy trình bằng máy tính, trường hợp xảy ra rất khó dự đoán.

Nó có đơn giản vậy không?

Nói về các sự kiện xảy ra trong quá trình thực hiện chương trình, chúng tôi đồng ý với sự trợ giúp của các quy trình máy tính cho phép chúng tôi quản lý thông tin điều khiển - lệnh (Hình 2) - trạng thái từ mã hoạt động và ba địa chỉ trong phần địa chỉ. Không khó hiểu khi loại lệnh này có tác động tới toàn bộ quá trình hoạt động của máy tính. Các máy có định dạng lệnh này được gọi là "ba địa chỉ". Tuy nhiên, máy ba địa chỉ không phải là loại máy tính duy nhất. Trong số tiếp theo của Kvast, chúng tôi sẽ giới thiệu cho bạn các máy tính có địa chỉ khác nhau - máy một và hai địa chỉ, nửa địa chỉ và thậm chí cả máy "không địa chỉ". Trên các máy này, việc thực hiện một lệnh như phép cộng tất nhiên là khó khăn hơn.
