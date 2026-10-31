---
id: 1970-11-kak-nayti-oshibku-65f9e002
issue: kvant_1970_11
year: 1970
number: "11"
title: Cách tìm lỗi
rubric: smes
page_first: 28
page_last: 28
page_labels: "26"
tag: QVQB
lang: vi
source: kvant_digital
extraction: vision
content_sha256: aa6da2a3c54dd1455ba17f8c74c0df3088cf8212461d80c7cfaeaf6e513f7fd9
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1970/11/articles/08_kak-nayti-oshibku-65f9e002.md
source_content_sha256: 047f0462fcc9fecaba27dc957dad934bd013ae2c96bb4df8bac4d0aab3cd3180
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦trang 26⟧

CÁCH TÌM LỖI

Bạn đã nhân hai đa thức dài. Làm thế nào kiểm tra xem có sai sót trong tính toán hay không?

Chúng tôi nêu hai cách cho phép phát hiện một số khả năng sai sót (nhưng, dĩ nhiên, không bảo đảm hoàn toàn tính đúng đắn của các phép tính đã kiểm tra).

Cách 1. Lấy tổng các hệ số của đa thức thứ nhất nhân với tổng các hệ số của đa thức thứ hai. Kết quả phải bằng tổng các hệ số của tích. Đó là giá trị của đa thức tại $x=1$.

Cách trên cho phép phát hiện lỗi trong số học (chẳng hạn, nếu đã dùng “đẳng thức” $2 \cdot 3=5$), nhưng không phát hiện lỗi trong đại số. Chẳng hạn, nếu ở một bước nào đó bạn đã viết $2x^2 \cdot 3x^3=6x^4$, thì cách này sẽ không phát hiện được lỗi.

Cách 2. Khác với cách thứ nhất ở chỗ các hệ số của các lũy thừa chẵn của $x$ được lấy với dấu cộng, còn các hệ số của các lũy thừa lẻ thì với dấu trừ. Còn lại, cách này trùng với cách thứ nhất. Ở đây ta nhận được giá trị của đa thức tại $x=-1$.

Cách thứ hai phức tạp hơn cách thứ nhất, nhưng nó cho phép phát hiện cả một số sai lầm đại số. Khi kiểm tra «đẳng thức» $2x^2 \cdot 3x^3=6x^4$ ta được $2 \cdot (-3)=6$. Đẳng thức này vô lý, vậy là trong các phép tính đã có sai sót.
