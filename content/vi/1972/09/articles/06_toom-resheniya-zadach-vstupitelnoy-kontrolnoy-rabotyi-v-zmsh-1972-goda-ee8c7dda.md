---
id: 1972-9-toom-resheniya-zadach-vstupitelnoy-kontrolnoy-rabotyi-v-zmsh-1972-goda-ee8c7dda
issue: kvant_1972_9
year: 1972
number: "9"
title: Lời giải bài toán bài kiểm tra đầu vào tại ZMSH năm 1972
authors:
  - Тоом А. Л.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 34
page_last: 36
page_labels: 32-34
tag: EH1C
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 8e25b44598e72d6ddea7936af943f181579f29810291e1c3be4d02c9d5ce4485
prompt_sha256: draft-1
translated_from: content/ru/1972/09/articles/06_toom-resheniya-zadach-vstupitelnoy-kontrolnoy-rabotyi-v-zmsh-1972-goda-ee8c7dda.md
source_content_sha256: 9da79048461dfd5ac3157d7cb13c170ca3791e10de5588d1a565e7ad7542b417
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 32⟧

Lời giải bài toán kiểm tra đầu vào tại 3MSH 1972
A. L. Toom

Các điều kiện để có được bài toán này và các quy định tuyển sinh vào trường toán tương ứng tại Đại học Bang Moscow và Đại học Bang Leningrad đã được đăng trên số đầu tiên «Kvant» của năm nay. Здесь мы помещаем lời giải и gợi ý к некоторым из этих bài toán.

Tác phẩm giới thiệu mới về Trường Toán học Liên minh sẽ được xuất bản trong số đầu tiên «Kvant» 1973.

1. Trong một tam giác, đầu của đường tròn ngoại tiếp và hướng lên đối xứng qua một trong các đường thẳng. Tìm các góc của hình tam giác.

Chúng ta hãy biểu thị các đầu của cạnh mà tâm đối xứng đối xứng với A và C, và đỉnh thứ ba đối xứng với B (xem Hình 1). Gọi O và D là tâm của đường tròn ngoại tiếp và ngoại tiếp tương ứng. Nếu chúng ta bỏ qua việc phân phối lại AC cho chúng thì chúng sẽ rơi xuống một điểm M - giữa đoạn OD (điều này có nghĩa là O và D đối xứng với AC). Ở đây bạn có thể sử dụng nó: $\angle BAC = \alpha$, $\angle ABC = \beta$, $\angle BCA = \gamma$.

Trước tiên chúng ta hãy chứng minh rằng $\alpha = \gamma$. Действительно, $AD = DC$ (как радиус),

đặt ra $AM = MC$, mở $\triangle AMO = \Delta CMO$. Vì vậy, $\angle OAM = \angle OCM$. Nhưng $\angle OAM = \frac{\alpha}{2} \Rightarrow OCM = \frac{\gamma}{2}$ (tâm của đường tròn kéo dài vào trong tam giác nằm ở giao điểm của các đường phân giác của nó), đặt ra $\alpha = \gamma$.

Suy ra $AB = BC$ thì trung tuyến $BM$ cũng chính là chiều cao, tức là O nằm trên BM.

Có thể các điểm B, O, M, D thẳng hàng và do đó $BD = AD$ (dưới dạng bán kính), thì $\angle BAD = \angle ABD = \frac{\beta}{2}$.

Mặt khác, $\triangle AOM = \Delta ADM$. Đó là lý do tại sao

$\angle MAD = \angle MAO = \frac{\alpha}{2}$.

Sau đó

$\angle BAD = \angle BAM + \angle MAD = \alpha + \frac{\alpha}{2} = \frac{3\alpha}{2}$.

Vì thế,

$\frac{\beta}{2} = \frac{3\alpha}{2}, \beta = 3\alpha$.

Tổng Posny của các góc của một tam giác $ABC$ bằng $5\alpha$, Ở đâu $\alpha = 36^\circ$, $\beta = 108^\circ$.

Đáp số: $36^\circ, 108^\circ, 36^\circ$.

⟦folio 33⟧

2. Hai cerrate vào cerra. Trước mặt anh ta, một số nhược điểm được viết thành một chuỗi trên giấy. Mỗi người lần lượt chuyển một hoặc hai điểm trừ liền kề sang mặt phẳng. Chúng tôi gọi cho mẹ, người sẽ chuyển tiếp điểm trừ cuối cùng. Chúng ta gọi ai là tseregna đúng: người mới bắt đầu hoặc đối tác của anh ta, và anh ta cần tserrat như thế nào cho việc này, nếu ngay từ đầu nó được viết: a) 7 điểm trừ; b) bạn có thích không?

Với tất cả n, người mới bắt đầu sẽ thắng. Hãy mô tả một chiến lược mà anh ta sử dụng chiến lược đó chắc chắn sẽ thắng. Nước đi đầu tiên phải được thực hiện ở giữa sao cho các điểm trừ còn lại tạo thành hai “quân” ​​riêng biệt có chiều dài bằng nhau (Hình 2 thể hiện vị trí sau nước đi đầu tiên với n=7)

Hình 2.

và n=8). Sau đó, người mới bắt đầu, với mỗi bước di chuyển của mình, phải chuyển tiếp những điểm trừ đối xứng với những điểm mà người thứ hai đã chuyển tiếp trước đó. Vì vậy, nếu cái thứ hai chuyển tiếp điểm trừ thứ k (hoặc thứ k và k+1) ở bên phải, thì cần phải chuyển tiếp điểm trừ thứ k (hoặc thứ k và k+1) ở bên trái. Sau mỗi lần di chuyển đầu tiên sẽ có được vị trí đối xứng.

Lần thứ hai, mỗi lần di chuyển, sẽ vận chuyển một hoặc hai điểm trừ, những điểm đối xứng chưa được vận chuyển; do đó, những điểm trừ này không thể là điểm cuối cùng, và điểm thứ hai không thể thắng.

3. Trong tam giác ABC chúng ta tìm được bisserris AK và đường trung tuyến AM. Tỉ số của các cạnh AB và AC có thể bằng bao nhiêu nếu biết rằng một trong các đoạn BM, MK, KC bằng hai đoạn còn lại?

Nghị định và e. Ở đây cần xem xét sáu trường hợp tương ứng với các ô của bảng (xem Hình 3).

đáp số được viết trong các ô.

Hình 3.

4. Có ít nhất một số a sao cho cả hai số $\frac{1}{a} - \sqrt{15}$ và $a + \sqrt{15}$ đều là số nguyên không?

Đặt $a + \sqrt{15} = m$, $\frac{1}{a} - \sqrt{15} = n$.

Hãy biểu diễn a từ đẳng thức thứ nhất và thay thế nó vào đẳng thức thứ hai:

$$\frac{1}{m - \sqrt{15}} - \sqrt{15} = n.$$

Hãy biến đổi:

$$16 - mn = (m - n) \sqrt{15}.$$

Để thực hiện sự bình đẳng này, chỉ cần:

$$\begin{cases} 16 - mn = 0, \\ m - n = 0. \end{cases}$$

(Thực tế, điều này là cần thiết, vì m, n là số nguyên, nhưng có thể bạn không biết điều này: xét cho cùng, chúng ta chỉ cần tìm ít nhất một giá trị của a.)

Hệ thống kết quả có thể được giải quyết dễ dàng:

$$m_1 = n_1 = 4, m_2 = n_2 = -4.$$

Đáp số: tồn tại: ví dụ: $4 - \sqrt{15}$ (trong thực tế chỉ có hai số như vậy).

5. Một trong những cửa sổ grambel trực tiếp. Andrey nói: “Đó là Vitya hoặc Tolya.” Vitya nói: “Không phải tôi hay Yura đã làm việc này.” Tolya nói: "Cả hai bạn đều đang nói dối." Dima nói: “Nim, một người trong số họ làm sự thật, còn người kia làm điều ngu ngốc.” Yura nói: "Này, Dima, chúng ta sai rồi." Cha của họ, tất nhiên, có thể tin cậy được, chắc chắn rằng sự thật đã được nói ra ít nhất ba năm trước. Ai đã phá vỡ cửa sổ?

Hãy biểu diễn các câu lệnh grambel dưới dạng bảng 5 hàng và 5 cột

⟦folio 34⟧

Hình 4.

(Hình 4). Các hàng và cột được đặt tên theo chữ cái đầu tiên của tên anh em. Lời tâm sự của mỗi anh em được ghi vào một cột dưới chữ cái đầu tiên của tên mình. Trong cột này, chúng tôi sẽ sắp xếp dấu cộng và số phút theo quy tắc sau: cộng nếu câu lệnh giả định rằng người anh em mà dòng được đặt tên đã phá vỡ cửa sổ và phút nếu câu lệnh không cho phép điều này.

Vì vậy, trong cột dưới chữ A, dấu cộng chỉ đối diện với chữ B và T, vì Andrei đã nói: “Đây là Vitya hoặc Tolya.” Trong cột bên dưới chữ B, số phút chỉ xuất hiện ở hàng B và S.

Để điền vào cột T, bạn cần tìm ra trường hợp nào Andrey và Vitya đều sai. Ví dụ: nếu Andrei làm vỡ cửa sổ, thì Vitya sẽ đúng, vì anh ấy cho phép điều này, và ở cột B có một điểm cộng so với chữ A. Nói chung, Andrei và Vitya sẽ chỉ sai nếu Yura làm vỡ cửa sổ, vì chỉ ở hai vị trí đầu tiên trong dòng của Yu là phút. Điều này có nghĩa là trong cột T bạn chỉ cần đặt dấu cộng cho Y.

Dima sẽ chỉ đúng nếu chính xác một trong hai anh em đầu tiên - Andrei và Vitya - đúng và người kia sai. Điều này có nghĩa là trong cột D, dấu cộng chỉ được đặt ở những hàng có một dấu trừ và một dấu cộng ở vị trí đầu tiên.

Yura chỉ đơn giản phủ nhận những gì Dima nói; Ở đâu có điểm cộng trong cột của Dima thì ở đó có điểm trừ dành cho anh ấy và ngược lại. Bàn đã đầy. Chúng ta biết rằng ít nhất có ba anh em đã nói sự thật. Điều này có nghĩa là bạn cần tìm một dòng có ít nhất ba dấu cộng. Chỉ có một dòng như vậy - T.

Đáp số: Tolya đã làm vỡ cửa sổ.

6. Hãy nghĩ về bốn số nguyên không âm, sao cho mỗi số từ 1 đến 81 có thể được biểu diễn dưới dạng tổng của bốn số - một số từ mỗi bộ ba.

Bộ tứ sau đây là phù hợp:

1, 2, 3
0, 3, 6
0, 9, 18
0, 27, 54.

Hãy giải thích chúng được phát minh như thế nào. Giải bài toán này ở dạng tổng quát hơn sẽ dễ dàng hơn: tìm ra k bộ ba số nguyên không âm sao cho mỗi số từ 1 đến 3^k có thể được biểu diễn dưới dạng tổng của k số - một từ mỗi bộ ba.

Với k=1 lời giải rất indo: một bộ ba 1, 2, 3. Đặt bài toán cho k bộ ba lời giải. Làm cách nào để chọn một bộ ba khác để nhận được lời giải bài toán cho k+1?

Số đầu tiên phải được lấy bằng 0. Sau đó, cộng nó với tổng của k số lấy từ một trong các bộ ba đầu tiên, chúng ta sẽ có được các số giống nhau từ 1 đến 3^k.

Hãy lấy số thứ hai bằng 3^k. Cộng nó vào các số từ 1 đến 3^k, ta được tất cả các số từ 3^k+1 đến 2,3^k.

Hãy lấy số thứ ba bằng 2,3^k. Thêm nó vào cùng một số, chúng ta nhận được tất cả các số từ 2,3^k+1 đến 3,3^k = 3^k+1.

Vì vậy, bài toán lời giải cũng cho k+1. Đây là cách bốn và ba được xây dựng. Người ta đã chứng minh rằng chúng phù hợp với mọi k, kể cả k=4.
