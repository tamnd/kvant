---
id: 1987-10-igrushka-e-rubika-a79142bd
issue: kvant_1987_10
year: 1987
number: "10"
title: '[E. Đồ chơi Rubik]'
rubric: smes
page_first: 68
page_last: 68
tag: A393
lang: vi
source: kvant_digital
extraction: vision
content_sha256: f61aab6f643f15c99b20824d4878a3781b314b7a955e1da5993fdca3ef66977b
prompt_sha256: draft-1
translated_from: content/ru/1987/10/articles/01_igrushka-e-rubika-a79142bd.md
source_content_sha256: 9615413c7aea447ea771af1d4891f958a44cf4447157448d1020ddaa740d8ca2
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

Một vài năm trước, Erpö Rubik không ngừng nghỉ đã nghĩ ra một tserrushka trong đó có 11 con chip, nằm ở các nút của một mạng hình vuông, với sự trợ giúp của ba cỗ xe tạo nên “hàm lời giải” xuống - lên (3 hàng 3 con chip cùng một lúc) và trái - phải (2 hàng 4 con chip riêng biệt). Như thường lệ, bài toán đổi mới ở chỗ, sau vài lần dịch chuyển tùy ý, nó sẽ khôi phục thứ tự ban đầu của các ô được hiển thị trong hình 1. Với câu đố này, chúng tôi sẽ một lần nữa chứng minh tính hiệu quả của các kỹ thuật mà chúng tôi đã giới thiệu cho độc giả ở «Kvant» Số 5.
Trước hết, chúng ta hãy xem các chip được thể hiện như thế nào dưới tác động của các bộ chuyển mạch khác nhau - các hoạt động như “ở đó - ở đây - từ đó - ra ngoài”. Nếu “ở đó” là viz, và “siod” là bleiben (“từ đó” và “otsioda”, tự nhiên, lên trên và sang phải), thì tùy thuộc vào hàng nào trong hai hàng ngang được dịch chuyển, lên trên hoặc xuống dưới, sẽ thu được hai thao tác - A và B (hình 2). Cả hai đều đại diện cho các chip tuần hoàn: A - dọc theo các mũi tên, B - dọc theo các mũi tên màu xanh lá cây. Tùy chọn thứ ba tự nhiên là di chuyển sang trái và phải ngay lập tức trên các thẻ ngang. Hoạt động đầu tiên C đại diện cho các con chip dọc theo chu vi của bức tường ngược chiều kim đồng hồ. Nếu lúc đầu chúng theo thứ tự ban đầu thì sau khi áp dụng C chúng sẽ di chuyển như sau:

Hình 1.

7→8→9→ô→đỏ→3→2→1→4→7. Bước tiếp theo là xem xét các bộ chuyển đổi của các phép toán A, B và C. Tuy nhiên, chỉ có thể bỏ qua một trong số chúng - K=AB^{-1} A^{-1} B. Nó hoán đổi vị trí của các mã thông báo 1 và 7, đồng thời 5 và 6 (ở vị trí ban đầu). Bây giờ chúng ta sẽ có thể tưởng tượng hai viên gạch bất kỳ đứng nối tiếp nhau dọc theo chu vi của câu đố (đồng thời 5 và 6 được biểu thị cùng một lúc). Ví dụ: đối với chip 1 và 3, việc này được thực hiện như sau: chúng tôi di chuyển chúng bằng C² đến vị trí 7 và 1, thực hiện K và trả chúng trở lại. Các hoạt động thuộc loại này (C^n K C^{-n}, n=0, ±1,±2,±3) cho phép bạn có được bất kỳ hoán vị nào của tất cả các mã thông báo ngoại trừ 5 và 6; kiểm tra xem nó ra! Nhưng chẳng phải tất cả những con chip này sẽ vào đúng vị trí, nhưng 5 và 6 sẽ được sắp xếp lại? Hóa ra là không. Chúng ta hãy giải thích điều này bằng cách bỏ qua điều quan trọng nhất - bằng chứng vì thiếu chỗ. Bất kỳ hoán vị nào cũng có thể được biểu diễn theo những cách sau. (Ví dụ: sẽ đạt được chu kỳ A nếu đổi tuần tự chip đỏ với chip 6, 5, 4, 1, 2, 3 hoặc chip 6 với 5, 4, 1, ...). Trong trường hợp này, số lần trao đổi sẽ luôn là số chẵn - khi đó hoán vị được gọi là chẵn hoặc lẻ - khi đó hoán vị được gọi là số lẻ. Nếu sau nhiều ca, các thẻ trở về vị trí ban đầu thì mỗi thẻ sẽ được dịch chuyển số lần chẵn. Từ đó, hoán vị thu được sẽ chẵn, có nghĩa là không thể có được chính xác một trao đổi theo cặp. Nhân tiện, đây là đáp số câu trả lời cho câu hỏi của chúng tôi về các câu đố từ số 5-20 và 6-20 của tạp chí.

Bạn đọc thân mến! Theo lịch biên tập, Năm mới đã sắp đến gần và nguồn cung cấp câu đố của chúng tôi còn lâu mới cạn kiệt. Của chúng tôi, bạn có thích ghi chú của chúng tôi về họ không? Bộ truyện này có nên tiếp tục không?
