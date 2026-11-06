---
id: 1991-11-tomu-kto-lyubit-prekrasnoe-cfbbcae4
issue: kvant_1991_11
year: 1991
number: "11"
title: Dành cho những ai yêu cái đẹp
rubric: smes
page_first: 53
page_last: 56
page_labels: 51, 53, 54
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 569ce94edda542037d56901f6a008dd0913d1ba973468aee5962bc3d80c6f1e0
prompt_sha256: draft-1
translated_from: content/ru/1991/11/articles/17_tomu-kto-lyubit-prekrasnoe-cfbbcae4.md
source_content_sha256: 2a35c44822c443bec385b3c7810cc3aa6a48656894814876b42200d7d156a542
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 51⟧

Dành cho những ai yêu cái đẹp

Bạn có thể quan sát các hệ thống tuyệt vời nếu bạn chế tạo một máy quang phổ và sử dụng cách tử nhiễu xạ màu của chúng tôi.

Để nhận được cách tử nhiễu xạ và hướng dẫn lắp ráp quang phổ, hãy gửi 6 rúp theo lệnh bưu điện đến địa chỉ sau:

427600, Glazov, st. K. Marka, 27, PO Box 76, SIP “Arzon”.

Vui lòng ghi rõ địa chỉ trả lại trên ngân hàng chuyển khoản.

⟦folio 53⟧

---
running_head:
folio:
---

họ, và thứ ba - thứ hai. Bây giờ chúng ta có thể chuyển $n$ của các đĩa phía trên từ thanh đầu tiên sang thanh thứ ba bằng cách thực hiện $2^n$ - 1 hành động. Chỉ còn lại một đĩa trên thanh đầu tiên. Hãy thay đổi nó thành thanh thứ hai miễn phí. Chúng ta hãy đổi que một lần nữa: cho que thứ hai số ba, cho que thứ nhất số hai và cho que thứ ba số một. Bây giờ chúng ta có $n$ đĩa trên thanh đầu tiên, đĩa thứ hai trống và đĩa lớn nhất nằm ở thanh thứ ba. Vẫn còn phải chuyển từ thanh đầu tiên sang đĩa $n$ thứ ba, việc này chúng ta có thể thực hiện trong $2^n$ - 1 thao tác. Tất cả chúng tôi đều thu thập tất cả các đĩa $n+1$ trên thanh thứ ba, thực hiện hành động $(2^n-1)+1+(2^n-1)=2^{n+1}-1$.

Từ đây, theo nguyên lý quy nạp toán học, đối với bất kỳ số tự nhiên $k$ nào, đều có thể có một số nguyên với $k$ đĩa, để chuyển chúng từ thanh đầu tiên sang thanh thứ ba, quy tắc tự do, trong $2^k$ - 1 hành động.

Chứng minh trên dễ dàng được xây dựng dưới dạng thuật toán hành động. Chính thuật toán này đã được cung cấp cho các lập trình viên trong các cuốn sách đã đề cập để viết nó bằng ngôn ngữ thuật toán này hoặc ngôn ngữ thuật toán khác.

Không khó để chỉ ra rằng trong chưa đầy $2^k$ - 1 hành động không thể chuyển $k$ đĩa từ thanh thứ nhất sang thanh thứ ba. Vì vậy, Linh mục Huyền thoại sẽ cần $2^{64}$ - 1 hành động để sử dụng tác phẩm của mình. Nếu bạn chỉ dành một giây cho mỗi hành động thì sẽ mất 18.446.744.073.709.551.615 giây, tức là hơn 500 tỷ năm.

Chúng ta hãy xem xét kỹ hơn quá trình chuyển đĩa. Để làm điều này, chúng ta thay đổi chúng theo thứ tự tăng dần: đầu tiên là nhỏ nhất, v.v. Bây giờ chúng ta bắt đầu chuyển đĩa theo thuật toán và ghi số lượng các đĩa được chuyển:

1213121412131215121312141...

Điều thú vị là mỗi lần chuyển lẻ đều là lần chuyển đĩa đầu tiên. Một quan sát khác: đặt các thanh ở các đỉnh của một tam giác đều (hình 2) và theo dõi chuyển động của đĩa thứ nhất. Hóa ra anh ta đang di chuyển theo một vòng tròn theo cùng một hướng; Hơn nữa, nếu số lượng đĩa ban đầu là số chẵn thì theo chiều kim đồng hồ và nếu số lẻ thì ngược chiều kim đồng hồ. Những quan sát này đã giúp cho việc xây dựng thuật toán truyền đĩa sau đây vào năm 1961 có thể thực hiện được:

đầu tiên chúng ta chuyển đĩa đầu tiên, sau đó không phải đĩa đầu tiên, sau đó lại là đĩa đầu tiên, rồi không phải đĩa đầu tiên, v.v. và đĩa đầu tiên được truyền theo một hướng: theo chiều kim đồng hồ trong trường hợp số đĩa chẵn và ngược chiều kim đồng hồ trong trường hợp số lẻ.

Lưu ý rằng gợi ý “không phải đĩa đầu tiên được chuyển” sẽ xác định hoàn toàn đĩa nào sẽ được chuyển và đến đâu tại một thời điểm nhất định, vì đĩa nhỏ hơn luôn được phân loại là đĩa lớn hơn.

Gần đây, một sinh viên từ Perm, Misha Fedorov, đã đề xuất một thuật toán khác, giống như thuật toán vừa mô tả, chuyển $k$ đĩa từ thanh đầu tiên sang thanh thứ ba trong $2^k$ - 1 hành động.

Misha giới thiệu khái niệm “tháp trống”. Anh ta gọi các thanh có đĩa được hạ xuống trên chúng là tháp và gọi tháp không liên quan đến hoạt động chuyển đĩa vào thời điểm này là trống. Thuật toán của M. Fedorov được xây dựng rất ngắn gọn:

Trong quá trình định vị lại, tháp trống phải được gọi theo vòng tròn cùng chiều: theo chiều kim đồng hồ nếu số đĩa là số lẻ và ngược chiều kim đồng hồ nếu số đĩa là số chẵn.

Misha Fedorov đã trình bày thành công công trình của mình tại Hội nghị khoa học và kỹ thuật toàn liên minh dành cho học sinh. Lưu ý rằng nếu thuật toán đầu tiên dẫn đến kết quả cần thiết bằng cách xây dựng thì tính hợp lệ của thuật toán thứ hai và thứ ba phải được chứng minh, và điều này không đơn giản lắm. Mặc dù trên thực tế cả ba thuật toán chỉ đơn giản là các mục khác nhau của cùng một quá trình chuyển đĩa.

Một quy trình khác biệt đáng kể sẽ xảy ra trong trường hợp chuyển giao chính xác thành công sang đĩa thứ ba, trong đó đĩa đầu tiên sẽ không bao giờ bị hỏng.

⟦folio 54⟧

---
running_head:
folio:
---

thanh thứ hai. Ông tuyên bố rằng quy trình như vậy có thể thực hiện được trong $2 \cdot 3^{k-1} - 1$ bước. Tuy nhiên, nếu đĩa thứ hai kết thúc ở thanh thứ hai thì số lần dịch chuyển sẽ bằng $2^2 \cdot 3^{k-2} - 1$. Và nói chung, nếu bạn cấm đặt đĩa $n$ vào thanh thứ hai thì hành động $2^n \cdot 3^{k-n} - 1$ sẽ bị ảnh hưởng.

Chúng tôi đã viết về một sửa đổi khác của câu đố này trong số trước của tạp chí (trên trang 4 của trang bìa). V. Pinaev đề nghị xem xét câu hỏi: liệu có luôn luôn có thể di chuyển các đĩa từ thanh thứ nhất sang thanh thứ ba nếu ban đầu chúng nằm trên thanh đầu tiên theo bất kỳ thứ tự nào. Chúng tôi cung cấp bằng chứng cho thấy sự thay đổi như vậy luôn có thể xảy ra.

Để chứng minh khả năng xảy ra sự dịch chuyển như vậy, trước tiên chúng ta xét một bài toán đơn giản hơn. Giả sử bạn cần lắp ráp một paramid từ các đĩa được xâu chuỗi trên hai thanh, với một đĩa thứ ba trống và các đĩa được đặt trên các thanh với đường kính tăng dần. Ngoài ra, giả sử rằng chúng ta đã phải giải bài toán đó cho bất kỳ số lượng đĩa nhỏ hơn nào.

Đặt đĩa lớn nhất trên thanh thứ nhất, sau đó để lắp ráp paramid trên thanh thứ ba, phải thực hiện ba thao tác:

1) lắp ráp một paramid không có đĩa lớn nhất trên thanh thứ hai;
2) di chuyển đĩa lớn nhất sang thanh thứ ba;
3) di chuyển paramid từ thanh thứ hai sang thanh thứ ba.

Chúng ta có thể thực hiện cả ba thao tác. Thật vậy, chúng ta có thể thực hiện thao tác đầu tiên theo giả định, thao tác thứ hai rất đơn giản và thao tác thứ ba là một chuyển động chung trong câu đố Lưu vực Hà Nội mà chúng ta đã học cách thực hiện.

Bây giờ chúng ta quay lại vấn đề chính bài toán. Thanh đầu tiên chứa các đĩa theo thứ tự ngẫu nhiên, thanh thứ hai và thứ ba là miễn phí. Hãy thử sắp xếp các đĩa ở thanh thứ hai và thứ ba theo thứ tự tăng dần. Chúng ta cũng hãy bắt đầu chuyển dịch và tiếp tục nó càng lâu càng tốt. Trong trường hợp này, chúng tôi sẽ sắp xếp lại ít nhất hai đĩa. Nếu may mắn, chúng tôi sẽ ngay lập tức chuyển tất cả các đĩa và chuyển sang bài toán đã được giải quyết. Nếu bạn không may mắn thì sao? Giả sử một số đĩa không thể đặt được trên thanh thứ hai hoặc thứ ba nữa. Chúng ta hãy phân tách các đĩa trên các thanh nhỏ hơn đĩa đang xem xét trên các thanh này. Hãy kết nối các bộ phận này lại với nhau trên thanh thứ hai. Chúng tôi đã học cách làm điều này. Bây giờ chúng ta sẽ chuyển độ phức tạp của đĩa sang thanh thứ ba và qua đó chúng ta sẽ loại bỏ được khó khăn đã phát sinh. Bạn có thể tiếp tục dịch chuyển. Kết quả là, tất cả các đĩa đều nằm trên thanh thứ hai và thứ ba, và bây giờ chúng ta có thể lắp ráp đế từ chúng. Vì vậy bằng chứng là hợp pháp.

Bạn cũng có thể xem xét điều này bài toán: tất cả các đĩa được sắp xếp theo thứ tự ngẫu nhiên trên cả ba thanh; bạn cần phải tập hợp chúng lại thành một. bài toán này cũng luôn có thể giải được.

V. Pinaev gợi ý tên của câu đố $\Pi$-tháp, à, chúng ta có thể đồng ý với cái tên này. Lưu ý rằng ý tưởng của câu đố này xuất phát từ khối Rubik: chúng ta nhầm lẫn vị trí của mảnh ghép và sau đó đưa nó trở lại dạng ban đầu bằng các hành động được phép.

Trong văn học, “Hanoi Bazni” được coi là có số lượng lớn cốt lõi, chẳng hạn như trong cuốn sách xuất bản gần đây của J. Arsac “Lập trình và bánh răng và câu đố” (M.: Nauka, 1990).

Ấn phẩm được chuẩn bị bởi A. Savin

Sửa đổi

Trong «Kvant» số 9 năm 1991 trên trang. 73 trong điều kiện bài toán Hạng 4 của Olympic Toán học Tây Ban Nha, được phép phẫu thuật. Câu hỏi bài toán nên đọc: “Có số tự nhiên $m$ sao cho

$$\sum_{n=1}^{m} |a_n - a_{n+1}| = 1990?$$

Chúng tôi xin lỗi độc giả của chúng tôi.
