---
id: 1983-5-kotov-topologiya-avtomobilnoy-razvyazki-f8a18986
issue: kvant_1983_5
year: 1983
number: "5"
title: Cấu trúc liên kết đường giao nhau
authors:
  - Котов Ю. В.
rubric: raznoe
rubric_sub: Разное
page_first: 54
page_last: 54
page_labels: "52"
tag: HGJN
lang: vi
source: kvant_digital
extraction: vision
content_sha256: cfe5b071756627d84b61d07f81731a5720a6f16600296f5d02a1fa67679bfc20
prompt_sha256: draft-1
translated_from: content/ru/1983/05/articles/18_kotov-topologiya-avtomobilnoy-razvyazki-f8a18986.md
source_content_sha256: 6ea9cdbbd240c68214bc8077ee2ee9f0e866f88c015456d54f01586abd5dd063
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 52⟧

Cấu trúc liên kết
ngã ba đường

Bốn điểm trên đường viền của hình tròn hoặc hình vuông (ví dụ: các đỉnh của hình vuông) không thể được kết nối theo cặp bằng các đường (đường dẫn) không giao nhau được vẽ bên trong hình. Không khó để xác minh điều này bằng cách lấy bút chì và giấy, mặc dù cần có kiến ​​thức về lĩnh vực cấu trúc liên kết để có một tài liệu vững chắc. Nếu bạn thay thế hình vuông bằng một mảnh bề mặt như vậy bằng một đường cắt hình và một “cây cầu”, như trong Hình 1, bài toán sẽ dễ dàng được giải quyết.

Các bề mặt phức tạp về mặt tôpô như vậy không chỉ được quan tâm đầu cơ - chúng còn hữu ích trong thực tế thiết kế và xây dựng tự động hóa, đường ray, mạng lưới đường phố thành phố, v.v. Nhìn vào Hình 1, người đọc có thể nhận ra nút giao cắt lá cỏ ba lá tự động hiện đại. Thoạt nhìn, khả năng kết nối bốn điểm theo cặp bằng các đường không giao nhau có nghĩa là có thể tổ chức chuyển động liên tục của các luồng tự động.

Tuy nhiên, nếu quan sát kỹ hơn, bạn sẽ nhận thấy sơ đồ hiển thị trong Hình 1 không đủ chính xác. Trên thực tế, luồng giao thông là hai chiều và các luồng giao thông sắp tới cũng không được giao nhau, do đó cần giảm số lượng điểm và đường đi. Như được hiển thị trong Hình 2, mỗi điểm “khởi hành” $A, B, B, \Gamma$ phải được kết nối bằng một đường dẫn có hướng đến từng điểm “đến” $A', B', B', \Gamma'$. Và trên bề mặt của “lá cỏ ba lá” không thể làm được điều này nếu không có giao lộ.

Các vòng tròn màu đỏ trong hình biểu thị các điểm giao nhau của luồng giao thông. Đúng, những giao lộ này xảy ra ở những nơi có luồng giao thông tương tự nhau (ví dụ: người lái xe di chuyển từ điểm $A$ đến điểm $B'$ phải chuyển làn ngay tại chỗ, vì làn đường của anh ta cắt ngang làn đường của người lái xe di chuyển từ điểm $B$ đến điểm $B'$), nhưng khi mật độ giao thông đông đúc, việc chuyển làn cũng là điều không mong muốn.

Mọi chuyện thế nào rồi? Có lẽ có thể điều hướng các luồng giao thông qua một nút giao thông như vậy theo cách khác? Không, không thể giao nhau theo cách này - đây là một định lý có thể chứng minh cấu trúc liên kết.

Nhưng những thông điệp tôpô tương tự cũng cho chúng ta biết cách thoát khỏi tình huống này: chúng ta phải xác định “cấu trúc tôpô” của điểm nối. Tuy nhiên, từ lời giải, cho phép bạn liên tục điều hướng tất cả các luồng giao thông, được hiển thị trên trang thứ tư của trang bìa của chúng tôi. Ở đây, ở phần giữa của bề mặt, một cấu trúc khác có hình cắt được hình thành, nối các bề mặt của “cây cầu” với con đường ngang nằm bên dưới.

Có lẽ lời giải được hiển thị sẽ không làm hài lòng các nhà thiết kế máy tự động. Nhưng trong thực tế xây dựng hiện đại, có những ví dụ về các nút và điểm nối có trọng số topo.
