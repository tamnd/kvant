---
id: 1986-3-levinshteyn-simin-element-pamyati-trigger-0ef817b8
issue: kvant_1986_3
year: 1986
number: "3"
title: Yếu tố bộ nhớ - kích hoạt
authors:
  - Левинштейн М. Е.
  - Симин Г. С.
rubric: raznoe
rubric_sub: Разное
page_first: 50
page_last: 50
page_labels: "48"
tag: FU5Z
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 8f4e9595d702e5026f70de32137c26b8bc9ed50849d4c3f8b5a5c7206cb21ff2
prompt_sha256: draft-1
translated_from: content/ru/1986/03/articles/17_levinshteyn-simin-element-pamyati-trigger-0ef817b8.md
source_content_sha256: a8a53fed2ca4fd1e761d84086db18d2c46dc303d4757f2fa24d7365af669ee9f
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 48⟧

VII. Yếu tố bộ nhớ - kích hoạt

Tiến sĩ Khoa học Vật lý và Toán học M. E. LEVINSHTEIN,
Ứng viên Khoa học Vật lý và Toán học G. S. SIMIN

Chúng ta bắt đầu phần trước về mạch logic (xem «Kvant», 1986, số 1, 2) bằng việc thảo luận về mạch logic bài toán, vấn đề này sẽ được giải quyết bằng một thiết bị điều khiển chuyển động của thang máy trong một ngôi nhà chung. Bây giờ có lẽ là thời điểm thích hợp để đề cập rằng ngay cả một thiết bị đơn giản như vậy cũng không thể hoạt động nếu nó không chứa các phần tử bộ nhớ. Một số dữ liệu được ghi lại trong “bộ nhớ” của thiết bị điều khiển thang máy: cửa sẽ mở bao nhiêu giây sau khi thang máy được nhả ra; phải làm gì nếu cửa tự động đóng lại và gặp sự cố; trình tự các thao tác khi nhấn nút “dừng” khẩn cấp là gì, v.v. Ngoài những dữ liệu có sẵn này, dữ liệu vận hành được nhập và ghi vào “bộ nhớ” của thang máy, thay đổi trong quá trình vận hành - các nút được nhấn ở tầng nào; nơi thang máy đang di chuyển vào lúc này: lên, xuống, đứng yên.

Hàng trăm nghìn và đôi khi hàng triệu dữ liệu được ghi vào bộ nhớ của tổ hợp giải toán máy tính bài toán. Dữ liệu này, như đã đề cập, được ghi ở dạng mà máy tính có thể nhận biết và xử lý, nghĩa là sử dụng “số 0” và “số 1” (trong hệ thống số kép).*

Rõ ràng là cả các phần tử của công nghệ máy tính mà chúng ta đã xem xét - bóng bán dẫn, cũng như các mạch logic dựa trên chúng - bản thân chúng đều không thể là phần tử bộ nhớ. Tất cả chúng sau khi ngừng xung đầu vào sẽ ngay lập tức trở về trạng thái ban đầu.

Đối với phần tử bộ nhớ, bạn cần một thiết bị, dưới tác động của xung đầu vào, có thể chuyển từ trạng thái “0” sang trạng thái “1” và ngược lại; đồng thời, sau khi kết thúc xung đầu vào, nó sẽ lấp đầy trạng thái của nó và có thể duy trì ở trạng thái đó vô thời hạn (cho đến khi có xung đầu vào chuyển tiếp tiếp theo).

Mạch vô tuyến đáp ứng được các yêu cầu này được gọi là trigger (từ tiếng Anh trigger).

Cách dễ nhất để hiểu nguyên lý hoạt động của flip-flop là sử dụng thuộc tính đã biết của mạch logic NOT (biến tần).

Hãy xem xét hai bộ biến tần được mắc nối tiếp (hình 1). Ví dụ: ở đầu vào của biến tần đầu tiên, $U_{bx} = x$ có thể bằng $U^0$ (số 0 logic) hoặc $U^1$ (số logic). Ví dụ: đầu ra của biến tần đầu tiên luôn là $x$ (không phải $x$), tức là $U^1$ cho $U_{bx} = U^0$ và $U^0$ cho $U_{bx} = U^1$. Điện áp đầu ra đầu tiên

*) Bài thơ hài hước “Cô gái phi thường” (tr. 50) sẽ giúp các em tìm hiểu mối liên hệ giữa hệ số kép và số thập phân.
