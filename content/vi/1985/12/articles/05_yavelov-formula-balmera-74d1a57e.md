---
id: 1985-12-yavelov-formula-balmera-74d1a57e
issue: kvant_1985_12
year: 1985
number: "12"
title: Công thức Balmer
authors:
  - Явелов Б. Е.
rubric: raznoe
rubric_sub: Разное
page_first: 18
page_last: 19
page_labels: 16-17
tag: S7J1
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 1f3e9ce22521db850cc2091d5884ce32fadfc83c9fa4472e317deb8b7cf6633c
prompt_sha256: draft-1
translated_from: content/ru/1985/12/articles/05_yavelov-formula-balmera-74d1a57e.md
source_content_sha256: 3719af10778ff930ed3a4e655821798c6b1c1d9d8b8fe999c46d7e061ef4ee9c
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 16⟧

Một số bất đẳng thức đáng chú ý

1. Bất đẳng thức Cauchy:
$$\frac{a_1 + a_2 + \dots + a_n}{n} \geq \sqrt[n]{a_1 \dots a_n} = G.$$

Bằng chứng. Chúng ta có thể giả định rằng $a_1 \geq a_2 \geq \dots \geq a_n$. Xét tập hợp số
$$\frac{a_1}{G}; \frac{a_1 a_2}{G^2}, \dots, \frac{a_1 a_2 \dots a_n}{G^n} = 1,$$
$$\frac{G}{a_1}; \frac{G^2}{a_1 a_2}, \dots, \frac{G^n}{a_1 \dots a_n} = 1.$$

Những bộ này được sắp xếp theo những cách ngược lại. Đó là lý do tại sao
$$n = \frac{a_1}{G} \cdot \frac{G}{a_1} + \frac{a_1 a_2}{G^2} \cdot \frac{G^2}{a_1 a_2} + \dots + \frac{a_1 \dots a_n}{G^n} \leq \frac{a_1}{G} \cdot 1 + \frac{a_1 a_2}{G^2} \cdot \frac{G}{a_1} + \dots + \frac{a_1 a_2 \dots a_n}{G^n} \times \frac{G^{n-1}}{a_1 a_2 \dots a_{n-1}} = \frac{a_1 + a_2 + \dots + a_n}{G}.$$

2. Bất đẳng thức Chebyshev. Nếu $a_1 \geq a_2 \geq \dots \geq a_n > i$ và $b_1 \geq b_2 \geq \dots \geq b_n \geq 0$ thì
$$n (a_1 b_1 + a_2 b_2 + \dots + a_n b_n) \geq \geq (a_1 + a_2 + \dots + a_n) (b_1 + b_2 + \dots + b_n).$$

Bằng chứng. Cộng các bất đẳng thức $n$
$$a_1 b_1 + \dots + a_n b_n \geq a_1 b_1 + a_2 b_2 + \dots + a_n b_n,$$
$$a_1 b_1 + \dots + a_n b_n \geq a_1 b_2 + a_2 b_3 + \dots + a_n b_1,$$
$$a_1 b_1 + \dots + a_n b_n \geq a_1 b_n + a_2 b_1 + \dots + a_n b_n,$$
chúng tôi có được những gì chúng tôi cần.

Lịch của chúng tôi

Công thức Balmer

“Ngay khi tôi nhìn thấy công thức của Balmer, mọi thứ ngay lập tức trở nên rõ ràng với tôi,” N. Bohr nói một cách tổng quát về giai đoạn cuối cùng trong công trình xây dựng lý thuyết lượng tử của nguyên tử của ông.*)

Năm nay đánh dấu 100 năm kể từ khi công thức này, vốn đóng một vai trò nổi bật trong lịch sử khoa học, được nhiều nhà khoa học biết đến. Nó được Balmer công bố lần đầu tiên vào năm 1884, nhưng hầu như không ai biết về nó cho đến khi một bài báo xuất hiện trên một tạp chí vật lý của Đức vào năm 1885.

Johann Jacob Balmer người Thụy Sĩ (1825-1898), đã được đào tạo đại học về toán học từ những năm 60 đến những năm 90, đã dạy toán ở Basel tại một phòng tập thể dục dành cho nữ và dạy các lớp về hình học mô tả tại trường đại học địa phương.

Phạm vi sở thích của Balmer rất rộng - triết học và văn học, âm nhạc và kiến ​​trúc, lịch sử cổ đại và lịch sử thế giới tự nhiên, y học. Nhưng toán học hữu ích đến mức nào, điều thu hút ông nhất là việc tìm kiếm sự hài hòa toán học, các mối quan hệ số học cụ thể - đều đặn: trong các hình dạng tinh thể, trong các thông số hình học của các thông số quan trọng của kiến ​​trúc, v.v. Chính niềm đam mê với “sự kỳ diệu của các con số” đã đưa giáo viên Basel đến với khám phá đáng chú ý của mình.

Đây là bài toán, chính là

⟦folio 17⟧

Khiên Balmer. Dữ liệu là bốn giờ.

6562,10; 4860,74; 4340,10; 4101,2.

Cần phải tìm ra “luật” mà họ tuân theo.

Bất cứ ai muốn tự mình giải bài toán này (và để làm được điều này, bạn sẽ không cần bất cứ thứ gì khác ngoài toán tiểu học) nên dừng đọc ghi chú ở đây một lúc, vì đáp số được cung cấp thêm một chút.

Các con số, tính đều đặn của Neil Balmer, là bước sóng (10⁻¹⁰ m) của bốn vạch trong vùng nhìn thấy của quang phổ của nguyên tử hydro. Trong vật lý, Balmer có đường kính lớn nhất và tình cờ đi đến công thức bài toán - sau khi nghe bài giảng của một giáo sư vật lý về nghiên cứu quang phổ. Cần phải nói rằng chuỗi vạch trong phổ hydro đã được các nhà vật lý chuyên nghiệp biết đến ít nhất từ ​​năm 1868. Nhưng trong nỗ lực thiết lập định luật quang phổ, các nhà vật lý luôn được hướng dẫn, như sau này hóa ra, bởi một sự tương tự thực tế không liên quan gì đến vấn đề: các vạch của chuỗi được ví như một âm bội của âm thanh và các biểu thức có dạng λ/n được tìm kiếm cho chúng, trong đó λ là bước sóng cơ bản nào đó, và n là một số nguyên. Đồng thời, đối với phổ của các nguyên tố khác nhau, thu được các bộ số nguyên khác nhau, giữa chúng không có kết nối nào được tạo ra.

Có lẽ Balmer đã được giúp đỡ bởi thực tế là ông không phải là nhà vật lý. Không bị cản trở bởi bất kỳ yêu cầu nào, ông chỉ tìm kiếm một công thức đơn giản có thể tái tạo chính xác nhất bước sóng được phát hiện của chuỗi quang phổ. Và kết quả của những nỗ lực này đã trở thành “công thức Balmer” nổi tiếng:

$$\lambda = \frac{n^2}{n^2 - 2^2}.$$

Ở đây λ là bước sóng của vạch quang phổ, d là một hằng số nào đó (bằng 3645,6 · 10⁻¹⁰ m) và n là số nguyên. Bốn dòng hydro hiển thị thu được từ công thức này bằng cách thay thế n các giá trị tương ứng 3, 4, 5 và 6. Người ta vẫn chưa biết làm thế nào nhà khoa học đi đến công thức này, nhưng có bằng chứng gián tiếp gợi ý cho thấy ông đã dựa vào một không gian hình học khá đơn giản.

Nhận được công thức mô tả chính xác bốn sóng của mình một cách đáng ngạc nhiên, Balmer vẫn đồng ý - liệu ông đã tìm ra một hình mẫu vật lý hay kết quả của nó chỉ là hệ quả của một sự trùng hợp đáng kinh ngạc. Sau khi đọc một cuốn sách tham khảo phổ biến về những thành tựu khoa học mới nhất, anh biết được rằng một dòng thứ năm khác của dãy hydro có bước sóng 3969 · 10⁻¹⁰ m đã được biết đến (đây là vùng cực tím vô hình của quang phổ). Thay n=7 vào công thức của mình, Balmer nhận được λ=3969 · 10⁻¹⁰ m! Thành công này đã củng cố đáng kể niềm tin của ông vào công thức và ông đã đưa số lượng của nó cho Đại học Basel, giáo sư vật lý. Ông đã báo cáo khám phá này một cách hết sức quan tâm và nói với Balmer rằng, trên thực tế, người ta đã biết thêm 9 vạch nữa ở phần tử ngoại của quang phổ hydro. Không khó để kiểm chứng rằng những dòng này được mô tả một cách hoàn hảo bằng công thức “ma thuật” (với phép thay thế n = 8, 9, ..., 16). Không có lựa chọn nào khác ngoài việc tìm ra một định luật cơ bản mới nào đó của tự nhiên.

Năm 1890, nhà vật lý người Thụy Điển I. Rydberg (1854-1919) đã viết công thức Balmer hơi khác một chút:

$$v = \frac{c}{\lambda} = Rc \left( \frac{1}{2^2} - \frac{1}{n^2} \right)$$

(v là tần số của vạch quang phổ, c là tốc độ ánh sáng và R là hằng số vật lý chức năng, ngày nay được gọi là “hằng số Rydberg”). Được đặt tên trong mục này, công thức Balmer được Bohr trình bày vào tháng 2 năm 1913. Khi tính đến biểu thức của năng lượng lượng tử hv (h là hằng số Planck), Bohr ngay lập tức làm sáng tỏ ý nghĩa vật lý của công thức, ý nghĩa này vẫn hoàn hảo trong gần ba thập kỷ. Và ý nghĩa này được thể hiện chính xác và rõ ràng - các vạch phổ tương ứng với một lượng tử bức xạ điện từ do các electron phát ra khi nhảy từ quỹ đạo có số n (n = 3, 4, v.v.) sang quỹ đạo thứ 2 gần hạt nhân hơn.

Hai câu nói thường được lặp đi lặp lại: 1) các nhà khoa học chỉ thực hiện những khám phá khoa học quan trọng khi còn trẻ; 2) such discoveries cannot be arrived at. Câu chuyện về phát hiện của Balmer chứng minh rõ ràng rằng vẫn có những trường hợp ngoại lệ.

V. E. Yavelov
