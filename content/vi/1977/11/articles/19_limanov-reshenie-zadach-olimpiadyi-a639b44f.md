---
id: 1977-11-limanov-reshenie-zadach-olimpiadyi-a639b44f
issue: kvant_1977_11
year: 1977
number: "11"
title: Lời giải bài toán thế vận hội
authors:
  - Лиманов Л. Г.
rubric: raznoe
rubric_sub: Разное
page_first: 65
page_last: 66
page_labels: 63-64
tag: YRV0
lang: vi
source: kvant_digital
extraction: vision
content_sha256: ab4fe87329298d29b21129f56d5cb1978f6c5597514929aaa8c27e3cd578b0d3
prompt_sha256: draft-1
translated_from: content/ru/1977/11/articles/19_limanov-reshenie-zadach-olimpiadyi-a639b44f.md
source_content_sha256: 01091850d89ed740f57603287da92b81b3436a468a998c964492597b38eb73f1
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 63⟧

định lý. «Kvant» có thể cung cấp thêm trợ giúp cho bạn về vấn đề này.

Lễ bế mạc Thế vận hội diễn ra vào ngày 19/4. Phó đại diện của jorri, M.I. Bashmkov, đọc to lời giải zhorri của Olympic Toán học toàn Liên minh lần thứ XI. Vì vậy, dựa trên kết quả của hai ngày thi đấu các bang đã quyết định trao 13 giải nhất, 24 giải nhì, 24 giải ba và vinh danh 32 thí sinh đạt danh dự cấp một và đánh giá danh dự cấp hai - 36 người tham gia. Chúng tôi công bố tên của những người chiến thắng trong Olympic toàn Liên minh lần thứ XI trên trang. 72.

Ngoài ra, nhiều tổ chức và doanh nghiệp khác nhau ở Estonia đã thành lập các giải thưởng đặc biệt (cho kết quả tốt nhất, cho lời giải nguyên bản nhất, tài nguyên tốt nhất, đại diện cho một góc biệt lập nhất của Liên Xô, v.v.), được trao cho nhiều học sinh. Giải thưởng zhorral đặc biệt «Kvant» - tập sách zhorral năm 1976 của tác giả tổng biên tập, viện sĩ I. K. Kikon - được trao cho Mark Levin, một học sinh lớp 8 đến từ Tallinn (cậu ấy tham gia cuộc thi ngoài cuộc thi nên không được trao vị trí chính thức nào). Tám tác phẩm kinh điển cũng đã được gửi qua đăng ký tạp chí «Kvant» cho năm 1978: Lyakhovets Andrey (Krasnodar), Khlebutin Sergey (Perm), Bernotas Andrius (Vilnius), Vlasov Vyacheslav (Kyiv), Irmatov Andar (Namangan UzSSR).

Dựa trên kết quả Olympic, một đội đã được thành lập để tham gia Olympic Toán học sinh quốc tế lần thứ 19. Nhóm bao gồm: A. Ambroladze (Tbilisi), A. Auzinsh (Riga), Y. Vinnishin (Kyiv), V. Galperin (Moscow), A. Kodryan (Rybnitsa), G. Rybnikov (Moscow), D. Flaass (Novosibirsk) và A. Churbanov (Moscow). Olympic quốc tế lần thứ 19 được tổ chức tại Belgrade (Nam Tư). Chúng ta sẽ nói về Olympic này trong một trong những số tiếp theo của tạp chí.

L. Limanov

Lời giải
bài toán
Olympic

Bài viết này xem xét ba loại bài toán cuối cùng của Kỳ thi Olympic Toán toàn Liên minh lần thứ XI, không có trong Sách bài toán Zhvant. Lời giải bài toán, được xuất bản trong Sách Vấn đề Zhvant, sẽ xuất hiện theo các số zhorral vào năm tới. (Điều kiện bài toán xem trang 58-61.)

lớp 8. Vấn đề 4.

Thay vì loại bỏ chip, chúng ta sẽ đặt cược vào chúng, bắt đầu với một chip đen. Chúng ta hãy thêm các chip trắng vào đó để mỗi chip có một chip lân cận màu đen (một hoặc hai). Sau đó, chúng ta sẽ đặt một số quân đen sao cho mỗi quân cờ có một quân cờ lân cận màu trắng và sao cho quân đen “cũ” không có quân cờ trắng hàng xóm. Ở nước đi tiếp theo, quân trắng được đặt lại, tuân theo hai điều kiện này, v.v.

Chúng ta hãy biểu thị bằng $b_i$ số quân đen được đặt sau $i$ nước đi và $w_i$ số quân trắng. Nếu quân đen được đặt ở nước đi $i+1$ ($i$ là chẵn), thì $b_{i+1} = b_i + 2w_i$, $w_{i+1} = w_i$. Nếu chip có màu trắng ($i$ chẵn), thì $b_{i+1} = b_i$, $w_{i+1} = w_i + 2b_i$; Mỗi lần di chuyển, chúng ta bao quanh tất cả các quân cờ cùng màu bằng hai quân cờ có màu khác nhau. Rõ ràng là không thể ấn định một con số lớn hơn.

Các điều kiện được viết ra vị trí của các quân chip trên vòng tròn sau nước đi thứ $i$ dưới dạng vectơ $\langle b_i; w_i \rangle$ và tính toán một số vectơ:

$$\langle 1;0 \rangle \rightarrow \langle 1;2 \rangle \rightarrow \langle 5;2 \rangle \rightarrow \langle 5;12 \rangle \rightarrow \langle 29;12 \rangle \rightarrow \langle 29;70 \rangle \rightarrow \langle 169;70 \rangle \rightarrow \langle 169;408 \rangle \rightarrow \langle 985;408 \rangle.$$

Bây giờ chúng ta hãy đảm bảo rằng trong bài toán a) đáp số là dương và trong bài toán b) tên của số lần di chuyển là tám.

Thật vậy, sau nước đi thứ tư, $29+12=41$ chip sẽ lộ ra. Khi chuyển từ $\langle 5;12 \rangle$ sang $\langle 29;12 \rangle$, 24 chip sẽ được thêm vào. Trong số này, không quá $2 \times 5=10$ đáp số để đáp ứng điều kiện thứ hai - chúng sẽ tách các chip đen cũ ra khỏi các chip màu trắng. Hãy gọi những tính năng này là bắt buộc. Hãy đánh dấu chúng

⟦folio 64⟧

Ta chứng minh bằng quy nạp theo $i$ bất đẳng thức sau:

$$\frac{1}{2^i} a_n - 2\varepsilon < a_{n+i} < \frac{1}{2^i} a_n + 2\varepsilon,$$

trong đó $n$ là số bất kỳ lớn hơn $m$. Thật sự,

$$\frac{1}{2^{i+1}} a_n - 2\varepsilon = \frac{1}{2} \left( \frac{1}{2^i} a_n - 2\varepsilon \right) -$$

$$-\varepsilon < \frac{1}{2} a_{n+i} - \varepsilon < a_{n+i+1} <$$

$$< \frac{1}{2} a_{n+i} + \varepsilon < \frac{1}{2} \left( \frac{1}{2^i} a_n + 2\varepsilon \right) + \varepsilon =$$

$$= \frac{1}{2^{i+1}} a_n + 2\varepsilon.$$

Nhưng đối với bất kỳ $\varepsilon > 0$ nào, người ta có thể chỉ định $i$ sao cho $\left| \frac{a_n}{2^i} \right| < \varepsilon$. Từ đó, đối với một $\varepsilon > 0$ tùy ý, người ta có thể chỉ định một $k$ sao cho với mọi $l > k$ thì bất đẳng thức $-3\varepsilon < a_l < 3\varepsilon$ đúng. Theo định nghĩa của giới hạn, điều này có nghĩa là $\lim_{n \to \infty} a_n = 0$.

lớp 9. Nhiệm vụ 5.

Chúng ta sẽ giả định rằng không có nút trống nào trên ranh giới của hình vuông. Hãy để chúng tôi chứng minh rằng bất kỳ hệ thống đường đứt nét nào thỏa mãn các điều kiện bài toán và điều kiện này đi qua số lượng nút gấp bốn lần.

Đặt các nút trên ranh giới của hình vuông như trong Hình 2. Có thể dễ dàng nói rằng đường đứt nét nối các điểm được đánh số $i$ và $j$ đi qua các nút $1+i-j+2l$, trong đó giá trị của $l$ phụ thuộc vào đường gãy. Bây giờ chúng ta hãy tính số nút gấp đôi mà các đường đứt quãng của chúng ta đi qua. Vì mọi điểm của hình vuông, ngoại trừ các đỉnh, đều có một đường đứt nét nên số này bằng $4.99 + \sum i - \sum j + 2\sum l (i,j)$, trong đó $l(i,j)$ là giá trị của $l$ đối với đường đứt nét bắt đầu tại điểm $i$ và kết thúc tại điểm $j$. Dễ dàng thấy rằng $\sum l(i,j)$ là số chẵn vì mỗi số hạng xuất hiện hai lần trong đó: $l(i,j) = l(j,i)$. Do đó, hệ thống các đường đứt nét của chúng ta đi qua số lượng nút và tổng số nút không nằm trên ranh giới của trang tính của chúng ta là $99^2$ - một số lẻ. Vì vậy, ít nhất một nút thực sự không được truyền tải.
