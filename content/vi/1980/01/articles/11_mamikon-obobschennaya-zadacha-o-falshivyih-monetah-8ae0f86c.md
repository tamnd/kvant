---
id: 1980-1-mamikon-obobschennaya-zadacha-o-falshivyih-monetah-8ae0f86c
issue: kvant_1980_1
year: 1980
number: "1"
title: Khái quát bài toán về tiền giả
authors:
  - Мамикон М.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 29
page_last: 31
page_labels: 27-29
tag: VL1B
lang: vi
source: kvant_digital
extraction: vision
content_sha256: ba63d2e6a9794263194b894f176e9b6f0847f6bcacbbc31a39ce17e9ab087ac3
prompt_sha256: draft-1
translated_from: content/ru/1980/01/articles/11_mamikon-obobschennaya-zadacha-o-falshivyih-monetah-8ae0f86c.md
source_content_sha256: 78cd4539c8b1737a14fa9ae97bcd2e37926da8155f4bf679adf87465add3ecf2
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 27⟧

M. Mamikon

Khái quát bài toán về tiền giả

Nhiều độc giả đã biết rõ về bài toán cổ điển sau đây về tiền giả, điều này dẫn đến thực tế là nó có thể được quyết định:

Bài toán về một túi tiền giả

Có N túi, mỗi túi chứa đủ số xu. Tất cả các túi, ngoại trừ một túi, đều chứa những đồng xu "bình thường" giống nhau, trong khi trong một túi tất cả các đồng xu đều là giả. Tất cả các đồng xu bình thường đều được biết đến và người ta biết rằng đồng xu 1 gram giả là điều bình thường. Việc phát hiện túi đựng tiền giả là cần thiết bằng cách sử dụng cân trên cân có quả cân.

Đây là cách giải quyết bài toán này. Các túi được đánh số thứ tự và từ mỗi túi lấy ra một số đồng xu bằng số của túi này. Tổng trọng lượng của tất cả các đồng xu được lấy theo cách này sẽ “thiếu” trọng lượng của cùng một số đồng xu bình thường (mà chúng ta biết) theo số gam bằng số lượng túi chính xác chứa đồng tiền giả*).

Tìm hiểu vấn đề này, tôi đi đến một kết luận đáng ngạc nhiên hơn rằng một trọng số có thể là lời giải và phức tạp hơn bài toán:

*) Điều này bài toán có thể được giải quyết - mặc dù xảo quyệt hơn - trong trường hợp tất cả các đồng tiền bình thường đều không xác định và không có trọng lượng khác nhau. Hãy suy nghĩ làm thế nào.

⟦folio 28⟧

Bài toán về vài túi tiền giả

Giả sử rằng trong các điều kiện của bài toán trước đó không phải là một mà là vài túi tiền giả và không rõ số lượng của chúng. Cần phải phát hiện tất cả các túi này bằng cách sử dụng một hệ thống treo Vanya trên cân có quả nặng.

Đã quyết định bài toán này, tôi mới dám đưa ra thêm điều kiện. Bài toán hóa ra có thể giải được trong những điều kiện thậm chí còn đáng ngạc nhiên hơn:

Bài toán về túi xách
với đồng xu nặng và nhẹ
Trong số N túi có một số lượng nhỏ (chưa xác định) túi chứa đồng xu nặng và một số nhỏ (không xác định) túi chứa đồng xu nhẹ. Một đồng xu dòng là 1 sông băng so với bình thường, và một đồng xu nặng thì ngược lại, là 1 sông băng so với bình thường. Cần phải sử dụng một lần cân đồng xu trên cân có quả cân để tìm ra túi nào chứa đồng xu bình thường, túi nào nặng và túi nào nhẹ. (Hãy nhớ rằng bên trong một chiếc túi nhất định, tất cả các đồng xu đều có cùng trọng lượng và tất cả các đồng xu bình thường đều được biết đến.)

Khả năng giải được của bài toán này cũng truyền cảm hứng cho tôi để khái quát hóa hơn nữa, vốn đã tự hướng tới. Cho đến nay, chúng tôi thực sự đã xem xét bài toán về hai hoặc ba loại (loại) tiền xu, vì vậy nó diễn ra một cách tự nhiên

Bài toán về túi xách
với đồng tiền chênh lệch

Giả sử có N túi, mỗi túi đựng đủ số tiền xu. Có nhiều loại xu khác nhau nhưng mỗi túi chỉ chứa một loại xu. Số lượng túi đựng tiền loại này là tùy ý, chúng ta không biết. Các đồng xu thuộc các loại khác nhau khác nhau về trọng lượng và số nguyên gam. Tất cả các đồng tiền của mỗi lớp đều được sửa đổi. Nó được yêu cầu với sự trợ giúp của một huyền phù vanya trên cân với một

Dùng cân xác định xem đồng xu trong mỗi túi thuộc loại nào.

Chúng tôi mời người đọc tự mình thử lời giải của bài toán trước khi chuyển sang lời giải tổng quát bài toán về tiền giả được trình bày bên dưới.

Lời giải bài toán về túi xách
với đồng tiền chênh lệch

Chúng tôi đánh số các túi theo thứ tự từ 0 đến N—1. Chúng ta hãy biểu thị tất cả các đồng tiền nhẹ nhất bằng m. Cho túi số j chứa những đồng xu có trọng lượng m+Δj, tức là Δj xác định loại đồng xu trong túi thứ j. Giả sử, tùy theo loại tiền, các giá trị Δ có thể lấy giá trị (số nguyên) 0, 1, 2,..., nhỏ hơn k, tức là không có số lượng loại tiền nào bằng k.

Bây giờ chúng ta hãy lấy từ túi số j một số đồng xu bằng kj, nghĩa là từ túi thứ nhất - một đồng xu, từ túi thứ hai - k,..., từ túi cuối cùng - kN−1 đồng xu. Sẽ có tổng số tiền được lấy

$$M = \sum_{j=0}^{N-1} k^j = 1 + k + k^2 + \dots + k^{N-1} = \frac{k^N - 1}{k - 1}.$$

Tổng trọng lượng S của chúng trên cân sẽ bằng

$$S = \sum_{j=0}^{N-1} (m + \Delta_j) k_j = m \sum_{j=0}^{N-1} k^j + \sum_{j=0}^{N-1} \Delta_j k^j = m \cdot M + \sum_{j=0}^{N-1} \Delta_j k^j.$$

Vì Δj < k luôn bằng nên tổng thứ hai ở vế phải

$$\Delta = \sum_{j=0}^{N-1} \Delta_j k^j = \Delta_0 + \Delta_1 k + \Delta_2 k^2 + \dots + \Delta_{N-1} k^N - 1$$

biểu thị sự chuyển đổi số Δ từ hệ thống số thập phân (trong đó thang đo hoạt động) thành hệ thống số có cơ số bằng k. Trong hệ thống này, Δ được viết dưới dạng số có dãy sau:

⟦folio 29⟧

giá trị của số:
$$\Delta \rightarrow \Delta_{N-1} \Delta_{N-2} \dots \Delta_{2} \Delta_{1} \Delta_{0}.$$

Chúng ta thấy rằng mỗi chữ số của mục này thể hiện cấp độ của đồng xu theo thứ tự các túi, được lấy theo thứ tự ngược lại. Trạng thái này là bản chất của lời giải của chúng tôi.

Vì vậy, từ tổng trọng lượng S của tất cả M đồng xu đã chọn, chúng tôi trừ đi các giá trị Mm - trọng lượng của cùng một số đồng xu loại nhẹ nhất và số còn lại $\Delta = S - Mm$ được chuyển sang hệ thống số có cơ số $k$ (chúng tôi mở rộng nó thành lũy thừa $k$, bắt đầu từ đầu). Khi đó ta được một số có dạng (*). Chữ số thứ $j$ tính từ cuối (tính từ 0) hiển thị cấp độ của đồng xu $\Delta_j$ trong túi được đánh số $j$.

Ví dụ

Bảng dưới đây cho biết trọng lượng của các đồng xu đựng trong 5 túi. Phía trên các túi được đánh số từ phải sang trái (thứ tự ngược lại), phía dưới các túi là các loại tiền xu. Họ là những gì chúng tôi đang tìm kiếm.

| số túi $j$ | 4 | 3 | 2 | 1 | 0 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| $11\text{ r}$ | $12\text{ r}$ | $10\text{ r}$ | $12\text{ r}$ | $10\text{ r}$ | $10\text{ r}$ |
| $1$ | $2$ | $0$ | $2$ | $0$ | $0$ |
| $81$ | $27$ | $9$ | $3$ | $1$ | $1$ |

Trong trường hợp này, $k=3$ và số xu lấy được tương ứng với các độ, như được hiển thị ở hàng cuối cùng của bảng. Tất cả chúng tôi đều lấy $M=121$ xu. Tổng trọng lượng của chúng trên cân sẽ bằng $S=1351$ g. Trừ các giá trị của $M \cdot m=121 \cdot 10$, ta thu được $\Delta=141$ g. Chuyển đổi $\Delta$ sang hệ thống bậc ba
$$\Delta = 1 \cdot 3^4 + 2 \cdot 3^3 + 0 \cdot 3^2 + 2 \cdot 3^1 + +0 \cdot 3^2,$$
ta thu được số $\overline{12020}$, dãy chữ số của nó trùng với dãy ban đầu của các giống cho trong bảng.

Nếu $k=10$ thì không cần chuyển $\Delta$ từ hệ thống số này sang hệ thống số khác. Đối với trường hợp $k=3$, có một số điểm khác biệt so với cách giải thích của chúng tôi về lời giải bài toán. Chúng tôi để nó cho người đọc tìm thấy nó.

Một chút lịch sử

cổ điển bài toán một túi tiền giả có thể được tìm thấy trong nhiều cuốn sách toán học phổ biến. Người ta nói rằng trong Thế chiến thứ hai người Anh đã “vứt bỏ” thứ này bài toán đối với binh lính Đức với mục đích làm mất tổ chức của họ và họ đã mất hơn 40.000 giờ công để giải quyết vấn đề này.

Trong cuốn sách của D. Bizam và J. Herceg “Logic đa thế giới” (M., “Mir”, 1978), trường hợp hai túi đựng tiền giả cũng được xem xét và lời giải được đưa đến bài toán này bằng cách sử dụng hai lần cân.

bài toán kinh điển về tiền giả gần đây đã được ứng dụng trong mã hóa và lý thuyết thông tin - để phát hiện lỗi trong mã.
