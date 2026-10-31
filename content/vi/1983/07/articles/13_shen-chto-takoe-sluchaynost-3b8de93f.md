---
id: 1983-7-shen-chto-takoe-sluchaynost-3b8de93f
issue: kvant_1983_7
year: 1983
number: "7"
title: Sự ngẫu nhiên là gì?
authors:
  - Шень А. Х.
rubric: raznoe
page_first: 59
page_last: 59
page_labels: "57"
tag: G1S5
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 1259267c580424630d59de28c99b6009c430cab35643ad66c782197cb2390918
prompt_sha256: draft-1
translated_from: content/ru/1983/07/articles/13_shen-chto-takoe-sluchaynost-3b8de93f.md
source_content_sha256: 18646f6031dd528f391b975005776398dfd9ecb27f60c12b0e2c8378cf328cd3
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 57⟧

Dịch vụ là gì?

Sau khi mua vé trên xe buýt, bạn phát hiện ra rằng số của nó chỉ có số bảy. Thật tuyệt vời phải không? Chắc chắn! Rốt cuộc, điều này đã không xảy ra hàng ngày! Bây giờ hãy tưởng tượng rằng số vé là 830877. Có thể bạn sẽ không tìm thấy điều gì đáng ngạc nhiên trong số này. Tại sao chính xác? Rốt cuộc, cả số 777777 và số 830877 đều xuất hiện thường xuyên như nhau (tốt hơn nên nói là hiếm như nhau) - trong một trường hợp trong số một triệu. Vậy tại sao chúng ta lại nhìn nhận vẻ ngoài của chúng một cách khác nhau?

Tại sao nếu đối tác của chúng ta ném mười sáu con liên tiếp vào một con xúc xắc, chúng ta nghi ngờ có điều gì đó không ổn, nhưng nếu anh ta ném 2, 6, 2, 1, 2, 6, 4, 5, 1, 3, chúng ta lại không nghi ngờ?

Tại sao một chuỗi của mỗi "người hầu" lại không phải là chuỗi khác (ví dụ: sáu)? Có thể đưa ra một định nghĩa toán học chính xác về dịch vụ không?

Định nghĩa này lần đầu tiên được đề xuất vào năm 1919 bởi nhà toán học và vật lý học người Đức Richard Mises. Chúng tôi không có cơ hội trình bày chi tiết nhưng chúng tôi sẽ giải thích ý tưởng đó.

Để đơn giản, chúng ta hãy xem xét các chuỗi chỉ bao gồm “số 0” và “số 1”. Trong trường hợp nào chúng ta đồng ý coi chuỗi như vậy là chuỗi dịch vụ? Ví dụ: nếu chúng ta liên tục thêm một đồng xu thông thường và ghi lại kết quả (“ngửa” - 1, “sấp” - 0), thì chuỗi kết quả sẽ là một chuỗi phục vụ.

Trước hết, rõ ràng là trong trường hợp một chuỗi mới phải có số lượng số 0 và số một gần bằng nhau; do đó, một chuỗi toàn các số 0, giống như một chuỗi toàn các số 1, là không hữu ích.

Mặc dù trình tự
0101010101...
và chứa số 0 và số 1 bằng nhau nên hiếm ai coi đó là một dịch vụ. Có chuyện gì vậy? Ví dụ, thực tế là nó không bao giờ chứa hai số 0 hoặc hai số 1 liên tiếp, trong khi trong trường hợp một chuỗi mới, các kết hợp 00, 01, 10, 11 sẽ xảy ra thường xuyên như nhau. Nhưng yêu cầu về sự xuất hiện đồng đều của tất cả các kết hợp có cùng độ dài là không đủ.

Hãy viết các số 0, 1, 2, 3, ... liên tiếp trong hệ kép - ta được dãy
011011100101110111000...

Có thể chứng minh (hãy thử xem!) rằng “trong giới hạn” đối với bất kỳ $n$ nào, tất cả các kết hợp của số 0 và đơn vị độ dài $n$ sẽ xảy ra thường xuyên như nhau trong chuỗi này. Nhưng bất chấp điều này, khó có ai đồng ý coi cô là người hầu.

Vậy chuỗi dịch vụ là gì? Mises đề xuất cách tiếp cận này để xác định khái niệm này. Chúng tôi sẽ chọn một số thành viên của nó từ trình tự, được hướng dẫn bởi một số quy tắc. Ví dụ: bạn có thể chọn tất cả các thành viên có bốn số hoặc tất cả các thành viên có số là số nguyên tố. Nó cũng được phép, khi quyết định có chọn một thành viên hay không, phải tính đến các giá trị của các thành viên trước đó của chuỗi. Ví dụ: bạn có thể chọn những số hạng đứng trước hai số hạng liên tiếp (Không được phép “chọn những số hạng mà chúng bằng một”!) Vì vậy, trình tự von Mises phải sao cho, theo bất kỳ quy tắc chọn số 0 và số 1 nào, chúng xuất hiện thường xuyên như nhau trong số các số hạng được chọn. (Yêu cầu này, như có thể được xác minh, cấm xem xét các điều kiện đã cho
