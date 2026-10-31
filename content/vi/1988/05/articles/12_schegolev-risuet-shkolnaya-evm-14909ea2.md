---
id: 1988-5-schegolev-risuet-shkolnaya-evm-14909ea2
issue: kvant_1988_5
year: 1988
number: "5"
title: Vẽ máy tính trường học
authors:
  - Щёголев А. Г.
rubric: raznoe
rubric_sub: Разное
page_first: 53
page_last: 54
page_labels: 51-52
tag: NDFP
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 1fe9712d353762cf0d8ac959c443d4fdbeabc696634c9054cbf1f3e758f6a1fa
prompt_sha256: draft-1
translated_from: content/ru/1988/05/articles/12_schegolev-risuet-shkolnaya-evm-14909ea2.md
source_content_sha256: fdbb3ce50967fa17b70928af2ea97cd0a94a98e25765c39730696e3ce4a954a2
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 51⟧

Vẽ máy tính trường học

A. G. SHEGOLEV

Bạn có thể tương tác với máy tính của trường được trang bị màn hình ở chế độ tương tác theo một kịch bản đặt trước (ví dụ: xem các bài viết của V. A. Kaimin trong «Kvant», 1986, số 10, 11). Trong trường hợp này, máy tính và người dùng trao đổi các đoạn văn bản và dữ liệu số. Trong khi đó, hầu hết các máy vi tính của trường học không chỉ cho phép “in” mà còn cho phép “vẽ” trên màn hình, tức là chúng có khả năng đồ họa.

Để hình ảnh xuất hiện trên màn hình, chúng ta phải cho người biểu diễn (máy tính của trường) biết vị trí và nội dung cần vẽ. Vì vậy, trước hết cần phải thống nhất về hệ tọa độ.

Hệ tọa độ được sử dụng trong máy vi tính khác với hệ tọa độ bạn biết từ khóa học toán ở trường. Gốc tọa độ (điểm O) được đặt ở góc trên bên trái, trục hoành và trục tọa độ có hướng như hình hình 1. Trường màn hình là một tập hợp các điểm, mỗi điểm có một màu cụ thể và tọa độ của bất kỳ điểm nào là các số nguyên x, y bên trong (đối với màn hình máy tính Yamaha) 0≤x≤255, 0≤y≤191.

Giống như một ngôi nhà được làm bằng gạch, chúng ta sẽ “xây dựng” bất kỳ hình ảnh phức tạp nào từ những yếu tố đơn giản nhất. Để thực hiện điều này, hãy bổ sung ngôn ngữ thuật toán quen thuộc của trường học bằng các lệnh đồ họa sau:

1) điểm (x, y), màu - hiển thị một điểm màu có tọa độ (x, y);
2) đoạn từ (x1, y1) đến (x2, y2),

⟦folio 52⟧

màu sắc - vẽ một đoạn nối các điểm có tọa độ (x1, y1) và (x2, y2) bằng màu màu;
3) Circle(x, y), r, color — vẽ một đường tròn có bán kính r với tâm tại điểm (x, y) màu màu;
4) Buse (x, y), r, om α đến β, color — vẽ các cung của đường tròn (x, y), r, tô màu từ góc α đến góc β (hình 2);
5) tô màu lên (x, y), color — tô màu lên điểm (x, y) cùng với hình tròn nằm trong đường khép kín cùng màu được bao quanh bởi điểm này (viền màn hình có thể được sử dụng như một phần của đường này); nếu không có đường viền như vậy thì toàn bộ màn hình sẽ bị sơn đè lên.
Hóa ra các lệnh được liệt kê là hoàn toàn đủ để mô tả các số liệu khá phức tạp. Ví dụ: hình ảnh của một chiếc đàn violin klion có thể được biểu diễn dưới dạng một tập hợp các đoạn và cung có bán kính khác nhau, biến đổi trơn tru với nhau (hình 3).
Để tạo điều kiện thuận lợi cho việc xây dựng các phần tử thường xuyên lặp lại, chúng tôi giới thiệu thêm hai lệnh:
6) khung từ (x1, y1) đến (x2, y2), màu sắc — vẽ khung hình chữ nhật có các cạnh song song với các cạnh của màn hình, màu sắc; hình chữ nhật được xác định bởi tọa độ của hai đỉnh chéo (x1, y1), (x2, y2) (hình 4);
7) khung - tô từ (x1, y1) đến (x2, y2), màu - sơn khung 6) và khu vực bên trong của nó bằng màu sắc.
Các thuật toán được viết bằng lệnh đồ họa có thể được dịch sang bất kỳ ngôn ngữ lập trình nào có các công cụ thích hợp. Đây là giao diện của bản ghi của người vận hành 1) - 7) bằng ngôn ngữ MSX-BASIC được sử dụng trên máy tính Yamaha.
1) N PSET (X, Y), C (dấu chấm)
2) N LINE (X1, Y1) - (X2, Y2), C (đoạn)
3) N VÒNG TRÒN (X, Y), R, C (vòng tròn)
4) N VÒNG TRÒN (X, Y), R, C, A, B (cung; góc A và B - tính bằng bán kính)
5) N SƠN (X, Y), C (sơn)
6) N LINE(X1, Y1) - (X2, Y2), C, B (khung)
7) N LINE(X1, Y1) - (X2, Y2), C, BF (khung đầy).
Những phần màu xanh lam làm nổi bật các phần tử thay đổi, có thể là số (hằng số) cũng như tên biến. N - số (bắt buộc phải đánh số toán tử trong BASIC), C - một số nguyên từ 1 đến 15, biểu thị màu cần sơn lên đối tượng này:
1 - đen, 6 - đỏ sẫm,
2 - xanh vừa, 7 - xanh lam,
3 - xám nhạt, 8 - đỏ vừa,
4 - xanh đậm, 9 - đỏ nhạt,
5 - xanh nhạt, 10 - vàng đậm,
11 - màu vàng nhạt,
12 - xanh đậm,
13 - hồng,
14 - xám,
15 - trắng.
Ví dụ: toán tử BASIC 20 PSET(50, 100), 6 sẽ tạo ra một chấm màu đỏ sẫm xuất hiện trên màn hình với tọa độ x=50, y=100.
Ngoài ra, máy tính được chuyển sang chế độ đồ họa bằng lệnh đồ họa, trong BASIC sẽ được ghi là SCREEN 2.
Lúc này sẽ lấy hình ảnh được đặt ở đầu stat. Kịch bản trong trường hợp này là hình được thực hiện trên giấy. Nói chung, tập lệnh đồ họa là một chuỗi hình (cảnh) và mô tả logic của chúng thông qua
