---
id: 1980-3-usov-chubarev-zakruchennyie-mnogougolniki-64e46024
issue: kvant_1980_3
year: 1980
number: "3"
title: Đa giác xoắn
authors:
  - Усов В.
  - Чубарев А.
rubric: raznoe
rubric_sub: Разное
page_first: 49
page_last: 49
page_labels: "47"
tag: VCR4
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 5f8718ea182634594a961e02a0432d311ad444a0a8ad8e0124b00132b91fd01b
prompt_sha256: draft-1
translated_from: content/ru/1980/03/articles/16_usov-chubarev-zakruchennyie-mnogougolniki-64e46024.md
source_content_sha256: cc3bd8973f35b7ecf78e287f837e4613b1a64a80d42adc39f6acd36edb6c39df
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 47⟧

Đa giác xoắn

Mẫu đặc trưng trên trang bìa thứ hai được tạo thành từ “đa giác xoắn”. Một đa giác xoắn bao gồm một chuỗi các đa giác bên phải: mỗi đa giác tiếp theo $M'$ được nội tiếp trong $M$ trước đó (các đỉnh $M'$ nằm trên cạnh $M$) và $M'$ là tập hợp con $M$ (hệ số tương tự được cố định cho chuỗi này).

Những chuỗi như vậy trông đặc biệt hiệu quả nếu chúng được xây dựng trên một họ các đa giác giống hệt nhau; bao phủ mặt phẳng (không chồng lên nhau hoặc chạy), chẳng hạn như trên một họ hình vuông, hình tam giác vuông hoặc hình lục giác.

Làm thế nào mà máy tính vẽ hình của chúng ta có thể xây dựng được các đa giác xoắn? Máy được “cho” đa giác ban đầu $P_1P_2...P_n$ (gọi là đa giác cấp 1), tức là danh sách các đỉnh được xác định theo tọa độ của chúng

$$P_1(x_1; y_1), P_2(x_2; y_2), ..., P_n(x_n; y_n).$$

Tiếp theo, sử dụng máy vẽ, máy vẽ các cạnh của đa giác, nối tuần tự các đỉnh với các đoạn. Sau đó, nó tìm tọa độ các đỉnh $P_1', P_2', ..., P_n'$ của đa giác tiếp theo (hạng hai) bằng quy tắc này:

$$(x'_i; y'_i) = (x_i; y_{i-1}) + k(x_{i+1} - x_i; y_{i+1} - y_i)$$

(chúng tôi khuyên người đọc nên vẽ, ví dụ: cho $n=6$ và đảm bảo rằng hệ số $k$ trong công thức giới hạn bằng

$$k = \frac{|P_i P'_i|}{|P_i P_{i+1}|}.$$

Tiếp theo, máy nối tuần tự các đỉnh $P_1', P_2', ..., P_n', P'_i$, từ đó thu được bản vẽ đa giác hạng thứ hai. Từ đa giác hạng thứ hai, máy tính thu được đa giác hạng thứ ba. Và vân vân.

Để tránh hiện tượng đốm màu (xảy ra khi các đa giác nhỏ tích tụ về phía tâm của đa giác bậc ba), chương trình giới hạn số lượng đa giác trong chuỗi.

Chúng tôi khuyên sinh viên của Trường Lập trình Tương ứng nên tạo một chương trình trong Rappre (sử dụng Lời nói) để xây dựng mẫu thuộc loại này và gửi cho chúng tôi dưới dạng bài tập tùy chọn.

V. Usov, A. Chubarev
