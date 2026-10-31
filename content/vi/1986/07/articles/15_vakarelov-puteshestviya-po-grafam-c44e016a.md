---
id: 1986-7-vakarelov-puteshestviya-po-grafam-c44e016a
issue: kvant_1986_7
year: 1986
number: "7"
title: Di chuyển qua đồ thị
authors:
  - Вакарелов Д. И.
rubric: igry-i-golovolomki
rubric_sub: Игры и головоломки
page_first: 52
page_last: 59
tag: XK3E
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 5a0565f2f825287b4f210f1bca164f7aec04d18cc284e722a80fdb2501435020
prompt_sha256: draft-1
translated_from: content/ru/1986/07/articles/15_vakarelov-puteshestviya-po-grafam-c44e016a.md
source_content_sha256: 76c09c20871a9a7130df3cbf61f2aceac9b6638a75812f4fc53af2de8b461f22
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

Trò chơi và câu đố

Chuyến đi
bằng đồ thị

D. I. VAKARELOV (NRB)

Sự xuất hiện của khối Rubik nổi tiếng đã khơi dậy sự quan tâm lớn đến các câu đố và trò chơi dựa trên việc sắp xếp lại các đồ vật. Đối với một nhà toán học, các câu đố còn thú vị chủ yếu vì việc tìm kiếm lời giải của họ đôi khi đại diện cho một phép toán bài toán rất khó, đòi hỏi nhiều nỗ lực trí tuệ và trí thông minh.

Chúng tôi cung cấp cho bạn một loạt trò chơi tổng hợp trò chơi nổi tiếng "Mười lăm" của Sam Lluyd. Một số trong số chúng khó như khối Rubik, và không giống như nó, chúng rất dễ thực hiện, vì vậy bất kỳ ai cũng có thể nghĩ ra và tạo ra bao nhiêu câu đố này tùy thích. Chúng ta sẽ nói về hai trò chơi trong lớp này và sau đó đưa ra mô tả chung về chúng.

Câu đố KIÊN NHẪN

Cắt tám vòng tròn có kích thước bằng đồng xu năm đô la từ bìa cứng và viết

A= 2,1,4,6,7,0.

A^{-1}= 7,6,4,1,2,0.

Hình 2 A

Hình 2 A^{-1}

⟦folio none⟧

trên mỗi cái là một trong những chữ cái của từ KIÊN NHẪN. Trên một tờ giấy, hãy vẽ biểu đồ ở hình 1, mà chúng ta sẽ gọi là trường cổ tử cung. Chúng ta sẽ gọi các vòng tròn của các ô sân chơi và các số viết bên cạnh chúng - số ô. Các ô được kết nối bằng các đoạn sẽ được gọi là liền kề. Đặt các chip hình tròn theo thứ tự ngẫu nhiên vào các ô của sân chơi sao cho ô trung tâm (số 0) vẫn trống. Để di chuyển, chúng tôi sẽ cố gắng di chuyển một con chip nhất định sang một ô trống liền kề với nó. Nước đi đầu tiên của trò chơi có thể là di chuyển một quân cờ từ ô số 2 hoặc 7 sang ô số 0. Mục tiêu của trò chơi là, thông qua một loạt nước đi, sắp xếp ngẫu nhiên các quân cờ vào cấu hình như minh họa trong hình 1.

Trong lúc chờ đợi, hãy thử, không cần đọc thêm bài viết, hãy kiên nhẫn và tự mình giải câu đố KIÊN NHẪN. Để thực hiện việc này, trước tiên hãy sử dụng bài toán dễ dàng hơn.

Bài toán 1. Từ một cấu hình tùy ý của các con chip trên trường cerra, thông qua một loạt các bước di chuyển, sẽ thu được cấu hình trong đó các chữ cái T, P, N và I ở vị trí của chúng.

Kết quả là chúng ta sẽ có được cấu hình tiêu chuẩn hoặc một trong ba cấu hình sau:

$$\begin{array}{cccc}
T & P & E & T & E & T & E \\
a = \Pi & E & b = \Pi & P & c = \Pi & E \\
H & I & E & H & I & E & H & I
\end{array}$$

Pozny xuất hiện bài toán tiếp theo.

Bài 2. Tìm ba chuỗi nước đi X, Y và Z lần lượt biến cấu hình a, b và c thành cấu hình chuẩn. Trình tự các bước đi được ghi lại bằng dãy số ô chứa các chip mà bước đi tiếp theo được thực hiện.

Đây là một trong lời giải bài toán 2, cùng với lời giải bài toán 1 đưa ra thuật toán lời giải của trò chơi KIÊN NHẪN. X=2,3,5,8,7,0,2,1,4,6,7,8,5,3,2,0,7,8,5,3,2,0,7,6,4,1,2,3,5,8, 7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0 ,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2 ,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1, 4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4, 6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7 ,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0 ,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2, 1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1, 4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6 ,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7 ,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0, 2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2, 1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4 ,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6 ,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7, 0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0, 2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1 ,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4 ,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6, 7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7, 0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2 ,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1 ,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4, 6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6, 7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0 ,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2 ,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1, 4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4, 6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7 ,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0 ,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2, 1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1, 4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6 ,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7 ,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0, 2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2, 1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4 ,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6 ,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7, 0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0, 2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1 ,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4 ,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6, 7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7, 0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2 ,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1 ,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4, 6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6, 7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0 ,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2 ,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1, 4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4, 6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7 ,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0 ,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2, 1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1, 4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6 ,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7 ,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0, 2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2, 1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4 ,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6 ,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7, 0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0, 2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1 ,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4 ,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6, 7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7, 0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2 ,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1 ,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4, 6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6, 7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0 ,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2 ,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1, 4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4, 6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7 ,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0 ,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2, 1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1, 4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6 ,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7 ,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0, 2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2, 1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4 ,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6 ,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7, 0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0, 2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1 ,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4 ,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6, 7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7, 0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2 ,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1 ,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4, 6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6, 7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0 ,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2 ,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1, 4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4, 6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7 ,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0 ,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2, 1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1, 4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6 ,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7 ,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0, 2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2, 1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4 ,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6 ,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7, 0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0, 2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1 ,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4 ,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6, 7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7, 0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2 ,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1 ,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4, 6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6, 7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0 ,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2 ,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1, 4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4, 6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7 ,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0 ,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2, 1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1, 4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6 ,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7 ,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0, 2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2, 1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4 ,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6 ,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7, 0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0, 2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1 ,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4 ,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6, 7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7, 0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2 ,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1 ,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4, 6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6, 7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0 ,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2 ,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1, 4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4, 6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7 ,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0 ,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2, 1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1, 4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6 ,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7 ,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0, 2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2, 1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4 ,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6 ,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7, 0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0, 2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1 ,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4 ,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6, 7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7, 0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2 ,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1 ,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4, 6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6, 7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0 ,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2 ,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1, 4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4, 6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7 ,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0 ,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2, 1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1, 4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6 ,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7 ,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0, 2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2, 1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4 ,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6 ,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7, 0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0, 2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1 ,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4 ,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6, 7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7, 0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2 ,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1 ,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4, 6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0 ,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1, 4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7 ,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1 ,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6, 7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2, 1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6 ,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2,1,4,6,7,0,2

⟦folio none⟧

chuỗi hành động có thể quan sát được và dễ nhớ, sau đó soạn ra bất kỳ chuỗi hành động nào từ chúng. Trong trường hợp này, bốn chuỗi sau đây rất hữu ích (ô số 0 trống trước khi chúng được thực thi):
$$A=2,1,4,6,7,0, A^{-1}=7,6,4,1,2,0, B=7,8,5,3,2,0, B^{-1}=2,3,5,8,7,0.$$
Các ký hiệu $A^{-1}$ và $B^{-1}$ cho thấy hành động của chuỗi này tương tự như hành động của chuỗi $A$ và $B$.

Các điều kiện $A, A^{-1}, B$ và $B^{-1}$ được gọi là chuỗi cơ bản và các phép biến đổi mà chúng tạo ra được gọi là các phép biến đổi cơ bản (có thể chấp nhận được). hình 2 hiển thị sơ đồ trực quan thể hiện hoạt động của các chuỗi này trên các chip trên sân chơi.

Chuỗi sơ cấp có một thuộc tính trường: sau khi chúng được hoàn thành, ô trung tâm lại trở nên tự do, điều này cho phép thực hiện chúng theo bất kỳ thứ tự nào lần lượt. Một chuỗi hữu hạn của chuỗi cơ bản, chẳng hạn như $A, AB, A^{-1}BA$, sẽ được gọi là chuỗi hoặc công thức có thể chấp nhận được và tác động của nó lên các phần sân chơi là một phép biến đổi có thể chấp nhận được. Khi nghiên cứu tác dụng của các công thức khác nhau, điều kiện được sử dụng là các con chip trên đó viết các số từ 1 đến 8 thay vì các chữ cái. Sau đó, chúng ta sẽ coi cấu hình tiêu chuẩn của chip là cấu hình trong đó mỗi chip nằm trong một ô có số tương ứng.

Chúng ta hãy mô tả “đại số của chuỗi chấp nhận được”, nó sẽ giúp chúng ta biến đổi đại số tùy ý của chuỗi chấp nhận được để đơn giản hóa chúng.

Nếu hai công thức $X$ và $Y$ tạo ra các phép biến đổi giống nhau thì chúng ta sẽ viết $X=Y$. Giả sử một chuỗi nước đi không làm thay đổi cấu hình được biểu thị bằng ký hiệu 1. Nếu $X$ và $Y$ là hai chuỗi có thể chấp nhận được thì tích $XY$ cũng là một chuỗi có thể chấp nhận được, hành động của nó là thực hiện tuần tự $X$ và $Y$. Không khó để nhận ra điều đó $A^{-1}A=AA^{-1}=1, B^{-1}B=BB^{-1}=1$. Tương tự, đối với bất kỳ phép biến đổi được chấp nhận nào $X$ đều có một nghịch đảo, nghĩa là sao cho $X^{-1}X=XX^{-1}=1$.

Đặt $G_1$ là tập hợp tất cả các phép biến đổi được chấp nhận. Trong tập hợp này, phép toán nhân được xác định, nghĩa là, đối với bất kỳ $X$ và $Y$ nào từ $G_1$ thì tích $XY$ được xác định, bao gồm việc thực hiện tuần tự phép biến đổi $X$ và sau đó là phép biến đổi $Y$.

Phép nhân này có các tính chất sau: 1) $(XY)Z=X(YZ)$; 2) tồn tại một phép biến đổi 1 sao cho $X \cdot 1=1 \cdot X=X$; 3) với mọi $X$ đều có $X^{-1}$ sao cho $X^{-1}X=XX^{-1}=1$.

Trong toán học, một tập hợp tùy ý $G$, trong đó phép nhân có các thuộc tính 1–3 được giới thiệu, được gọi là một nhóm. Chúng ta đã chỉ ra rằng tập các phép biến đổi chấp nhận được $G_1$ mà chúng ta đã xây dựng là một nhóm. Chúng ta cũng có thể thêm rằng nhóm $G_1$ tạo ra các phép biến đổi $A$ và $B$.

Hóa ra nhóm đã xây dựng

⟦folio none⟧

pa $G_1$ có đủ bộ biến đổi cho câu đố lời giải KIÊN NHẪN.

Bài toán 3. Cho phép cung cấp cấu hình tùy ý của chip TsRA PATIENCE với một ô trung tâm miễn phí. Chứng minh rằng có một công thức $X$ từ $G$ mang lại lời giải tsry KIÊN NHẪN.

Lời giải trong số bài toán này sẽ có được sau khi chúng tôi tìm thấy thuật toán lời giải của trò chơi KIÊN NHẪN.

Chúng ta cũng sẽ tìm hiểu cấu hình nào của chip, trên đó có ghi các số từ 1 đến 8, có thể được giảm xuống cấu hình tiêu chuẩn.

Bài tập
1. Hãy để một số phép biến đổi $X \in G_1$ thừa nhận ký hiệu $X = X_1X_2...X_n$, trong đó $X_i \in G_1$. Chứng minh rằng $X^{-1} = X_n^{-1} \cdot X_{n-1}^{-1} \cdot ... \cdot X_1^{-1}$.
2. Vẽ đồ thị diễn biến của phép biến đổi $A^2, A^3, B^2, B^3, ABAB^{-1}A^{-1}$.
3. Để một số mã thông báo đứng yên trong quá trình chuyển đổi $X$. Chứng minh rằng nó vẫn cố định dưới phép biến đổi $P^{-1}XP$, trong đó $P$ là phép biến đổi được chấp nhận.
4. Chứng minh các đẳng thức $A^5 = B^5 = 1$, $A^4 = A^{-1}, A^3 = A^{-2}, (ABA^{-1})^4 = AB^{-1}A^{-1}$.

Các nhận dạng như những gì được đưa ra trong Bài tập 4 giúp đơn giản hóa các công thức, làm cho văn bản của chúng gọn hơn và trong một số trường hợp, thiết lập nhận dạng của các công thức.

"Lập trình công thức"
Khi tìm thuật toán giải đố lời giải, phần khó nhất là mô tả các công thức bằng đồ thị được xác định trước. Đó là một chút

giống như lập trình, trong đó các lệnh là các phép biến đổi cơ bản và các chương trình là các công thức, nghĩa là các chuỗi lệnh.

Chúng ta hãy xem xét một số ví dụ thực tế của nền giáo dục này.

A. Các phép biến đổi $ABA^{-1}B^{-1}$ và $A^{-1}B^{-1}AB$, hành động được thể hiện trong hình 3, thành 2, được gọi là cổ góp. Chúng thú vị vì chúng đại diện cho một số cặp điểm trong khi vẫn giữ nguyên các điểm khác.

B. Phép biến đổi $ABA$ (hình 3, $\partial$), chia thành hai chu kỳ, rất thú vị. Đối với anh ta, $(ABA)^5$ là chu kỳ được hiển thị tại hình 3, $e$.

Trong bài toán 2, để chuyển đổi cấu hình $a$ sang dạng chuẩn, cần phải tìm một chuỗi các bước di chuyển trong đó các chữ cái $P$ và $E$ kết thúc ở vị trí của chúng. Dễ dàng nhận thấy rằng điều này có thể đạt được bằng cách sử dụng phép biến đổi $X_2$, biểu đồ của nó được hiển thị trong hình 4, $6$.

B. Xét phép toán mà trong lý thuyết nhóm gọi là phép chia. Với sự trợ giúp của nó, bạn có thể chuyển hành động của một số chuyển đổi sang một khu vực khác của sân chơi. Ví dụ: hãy tìm công thức biến đổi $X_1$ (xem hình 4, $\delta$). Để thực hiện điều này, bằng cách sử dụng phép biến đổi $B^{-2}$, chúng ta di chuyển chip 3 đến vị trí của chip 7 và chip 5 đến vị trí của chip 2. Sau đó, chúng ta sử dụng chu trình $(ABA)^5$ và cuối cùng, phép biến đổi $B^2$ chúng ta đưa chip 2 và 7 về vị trí cũ của chúng.

⟦folio none⟧

Kết quả là một chu trình $4 \rightarrow 3 \rightarrow 5 \rightarrow 4$ với công thức $B^{-2}(ABA)^5B^2$.

Trong trường hợp tổng quát, phép chia động từ có dạng $Q_1 = PQP^{-1}$. Trong trường hợp này, họ nói rằng phép biến đổi $Q$ được liên hợp với phép biến đổi $Q_1$. Trong trường hợp của chúng tôi $Q = (ABA)^5$, $P = B^{-2}$.

Tương tự như $X_2 = A^{-2}X_1A^2$ và $X_3 = B^{-1}X_2B$. Lưu ý rằng $X_2$ và $X_3$ thực hiện các hành động tương tự như các phép biến đổi $X$ và $Z$ từ bài toán 2, nhưng dài hơn đáng kể. Phép biến đổi $Y$, rất dễ hiểu, cho phép ký hiệu $Y = Z^2$.

Liên hợp cổ góp $A^{-1}B^{-1}AB$ với $B^{-2}$ chúng ta nhận được công thức cho $X_4 = B^{-2}(A^{-1}B^{-1}AB)$ $B^2 = B^{-2}A^{-1}B^{-1}AB^{-2}$ (chúng tôi đã sử dụng thực tế là $B^3 = B^{-2}$).

D. Khi xây dựng công thức với các thuộc tính mong muốn, bạn có thể hành động khác đi. Hãy triển khai chu trình $3 \rightarrow 5 \rightarrow 8 \rightarrow 3$ làm ví dụ. Chúng ta sẽ thực hiện chuyển động của các chip 3, 5, 8 mà không quan tâm đến số phận của các chip còn lại, như trong hình 5. Kết quả là chúng ta sẽ thu được hoán vị mong muốn với công thức $B^{-2}ABA^{-1}BAB^{-2}$. Bây giờ bạn cần theo dõi điều gì xảy ra với phần còn lại của chip. Để làm điều này, chúng ta vẽ sơ đồ biến đổi kết quả (hình 6, a). Kết quả là một chu kỳ khác có độ dài 5, có thể bị phá hủy mà không cần nâng nó lên lũy thừa thứ 5 mà bằng cách thực hiện thao tác $A^{-1}$ trước tiên. Vì vậy, $X_3 = A^{-1}B^{-2}ABA^{-1}BAB^{-2}$.

Bài tập 5. Viết các công thức biến đổi cho bởi các đồ thị ở Hình 6, 7, 8.

Thuật toán lời giải của trò chơi KIÊN NHẪN

Chúng ta sẽ sử dụng công thức cho $X_4$ và phép chia động từ. Lời giải được thực hiện theo hai giai đoạn.

Giai đoạn đầu tiên. Đặt ba chữ E vào đúng vị trí. Đối với điều này, không cần các công thức đặc biệt, mặc dù nếu muốn, bạn có thể viết chúng ra cho từng vị trí cụ thể.

Giai đoạn thứ hai. Đặt các chữ cái còn lại vào đúng vị trí. Nó được thực hiện tùy thuộc vào nội dung của ô bằng 3 phép biến đổi như trong bảng sau:

| Thư trong ô, 3 | Một sự biến đổi đặt cô ấy vào vị trí của mình |
| :--- | :--- |
| T | $A^{-2}X_4A^2 = A^{-2}B^{-2}A^{-1}B^{-1}AB^{-2}A^2$ |
| P | $A^{-1}X_4A = A^{-1}B^{-2}A^{-1}B^{-1}AB^{-2}A$ |
| N | $X_4 = B^{-2}A^{-1}B^{-1}AB^{-2}$ |
| VÀ | $AX_4A^{-1} = AB^{-2}A^{-1}B^{-1}AB^{-2}A^{-1}$ |
| R | $X_4$ - nếu chưa có cấu hình tiêu chuẩn |

Trong thuật toán đã cho, trong từ KIÊN NHẪN có hai chữ cái E.

Thuật toán tìm thấy lời giải của trò chơi PATIENCE giải quyết hoàn toàn bài toán 3. Nhưng chúng tôi vẫn chưa biết cấu hình nào được giảm xuống mức tiêu chuẩn. Trong các bài tập sau, sân chơi trùng với sân chơi KIÊN NHẪN.

Bài tập 6. Tìm thuật toán lời giải cho trò chơi từ PATIENCE trong tiếng Anh và từ PATIENCE trong tiếng Bungari.

⟦folio none⟧

7. Xây dựng lý thuyết về trò chơi KIÊN TRÌ, CUỘN, CƯA - những từ này có hai chữ cái lặp lại, nhưng chúng không ở cùng một vị trí như trong trò chơi KIÊN NHẪN.

Trò chơi lê KIÊN NHẪN

Mỗi phần tử α của nhóm $G_1$ sắp xếp lại các mã thông báo. Gọi $\alpha(i)$ là số chip, vị trí của chip được thay thế bằng chip từ ô $i$. Tập hợp số $\alpha(1), \alpha(2), \dots, \alpha(8)$ gọi là hoán vị của các số 1,2,...,8. Vì vậy, mỗi phần tử của nhóm $G_1$ tương ứng với một số hoán vị.

Tập $S_n$ của tất cả các hoán vị của một tập hợp gồm các phần tử $n$ tạo thành một nhóm (tích $\alpha\beta$ của các hoán vị $\alpha$ và $\beta$ là thực hiện chúng một cách tuần tự, tức là $(\alpha\beta)(i) = \beta(\alpha(i))$. Nhóm này được gọi là nhóm đối xứng. Chúng ta đã thấy rằng nhóm $G_1$ có thể được coi là một phần của nhóm $S_8$.

Giả sử $f = f(x_1, x_2, \dots, x_8)$ là một đa thức nào đó trong tất cả các biến và $\alpha \in S_8$ là một hoán vị nào đó. Bây giờ chúng ta hãy thay thế biến $x_1$ bằng $x_{a(1)}$ trong đa thức $f$, biến $x_2$ bằng $x_{a(2)}$, ..., biến $x_8$ bằng $x_{a(8)}$. Chúng ta nhận được một đa thức mới $\alpha f = f(x_{a(1)}, x_{a(2)}, \dots, x_{a(8)})$.

Rõ ràng là với hai hoán vị $\alpha$ và $\beta$ sẽ có $(\alpha\beta)f = \beta(\alpha f)$.
Xét đa thức $P_n(x_1, x_2, \dots, x_n) = (x_1 - x_2)(x_1 - x_3) \dots (x_1 - x_n) \dots (x_2 - x_3) \dots (x_2 - x_n) \dots (x_{n-1} - x_n)$.

Hoán vị $\alpha \in S_n$ được gọi ngay cả khi $\alpha P_n = P_n$ và lẻ nếu $\alpha P_n = -P_n$.

Bài tập

8. Chứng minh rằng khi đổi chỗ bất kỳ hai biến $x_i$ và $x_j$ thì đa thức $P_n$ trở thành $-P_n$.

9. Mọi hoán vị đều là chẵn hoặc lẻ.

10. Nếu $\alpha$ và $\beta$ là các hoán vị có cùng chẵn lẻ thì $\alpha\beta$ là hoán vị chẵn.

11. Nếu $\alpha$ và $\beta$ là các hoán vị có số chẵn lẻ khác nhau thì $\alpha\beta$ là một hoán vị lẻ.

12. Các hoán vị $\alpha$ và $\alpha^{-1}$ có cùng tính chẵn lẻ.

13. Các hoán vị tương ứng với chuỗi cơ bản $A, A^{-1}, B, B^{-1}$ là số chẵn.

Từ Bài tập 8-12, tập hợp $A_n$ của tất cả các hoán vị chẵn tạo thành một nhóm. Nhóm này được gọi là nhóm trật tự xen kẽ dấu $n$.

Từ Bài tập 13, $A_8 \supset G_1$. Lấy sự tồn tại của thuật toán lời giải của trò chơi KIÊN NHẪN và kết quả của bài tập 10-12, chúng ta có thể chứng minh rằng $A_8 = G_1$. Do đó, với sự trợ giúp của $G_1$, bất kỳ hoán vị chẵn nào của mã thông báo 1,2,...,8 đều có thể được thực hiện và không thể thực hiện hoán vị lẻ.

Bài tập 14. Chứng minh rằng bất kỳ vị trí nào cũng có thể được chuyển sang vị trí tiêu chuẩn hoặc sang vị trí khác với vị trí tiêu chuẩn bằng cách sắp xếp lại các chip 5 và 8.

NHÀ giải đố

Sân chơi của trò chơi này được hiển thị ở hình 7. Các phần của trò chơi được đánh số từ 1 đến 9. Các phần sau đây được sử dụng làm chuỗi cơ bản của trò chơi:

$A = 1, 4, 7, 8, 5, 2, 0; \quad A^{-1} = 2, 5, 8, 7, 4, 1, 0; \quad B = 2, 5, 8, 9, 6, 3, 0; \quad B^{-1} = 3, 6, 9, 8, 5, 2, 0; \quad C = AB = 1, 4, 7, 8, 9, 6, 3, 0; \quad C^{-1} = 3, 6, 9, 8, 7, 4, 1, 0.$

⟦folio none⟧

Thuật toán lời giải sử dụng hai công thức sau:

$$X_5 = A^2 B^{-2} (ABA^{-1} B^{-1}) B^2 A^{-2} = A^2 B^{-2} CA^{-1} BA^{-2};$$

$$X_6 = (ABAB^{-1} ABA^{-2} B^{-1})^3 = (CAB^{-1} CA^{-2} B^{-1})^3.$$

Những công thức này có thể thu được bằng cách sử dụng các số nguyên tố được mô tả ở trên.

Giai đoạn 1. Cài đặt lại chip 1,4,7 và 8. Để thực hiện việc này, công thức $X_5$ là cellulose (tương tự như cách sử dụng công thức $X_4$ ở giai đoạn 2 của thuật toán trò chơi KIÊN NHẪN). Lưu ý rằng mỗi lần sử dụng công thức $X_5$, quân 1 và quân 4 sẽ thay đổi vị trí. Vì vậy, ở cuối giai đoạn chúng có thể được sắp xếp lại. Sau đó, sử dụng công thức $X_6$, chúng ta đặt chúng vào đúng vị trí. Đặt $G_2$ là nhóm trò chơi DOM.

Bài tập 15. Chứng minh nhóm $G_2$ trùng với nhóm đối xứng $S_9$. Gợi ý. Chứng minh rằng nó phù hợp với sự tồn tại của thuật toán lời giải mô tả ở trên.

Di chuyển qua đồ thị

Người đọc đã rõ cách bạn có thể độc lập nghĩ ra các trò chơi mới như KIÊN NHẪN và DOM. Tại hình 9 có thêm một số ví dụ về những trò chơi như vậy.

Bài tập

16. Tìm các thuật toán lời giải của các trò chơi MƯỜI LƯỜI, SUY NGHĨ NHANH HƠN, KẾT HỢP và CUBOLOGY. Chứng minh rằng các nhóm tương ứng là các nhóm xen kẽ dấu (thuộc loại $A_n$).

Xin lưu ý rằng tất cả các trò chơi trong Bài tập 16 đều có hai ô giống nhau (trong trò chơi đầu tiên là ô 6 và 9).

17. Tìm thuật toán lời giải của game STADIUM, CROSS, TEN. Chứng minh rằng các nhóm tương ứng là đối xứng (như $S_n$).

18. Chứng minh rằng các nhóm $S_n$ và $A_n$ chứa các phần tử $n! = 1,2...n$ và $\frac{1}{2} n!$ tương ứng.

Các hình tương tự như sân chơi của các câu đố đang xem xét được gọi là đồ thị. Do đó tên chung của họ - "du lịch qua đồ thị". Chính xác hơn, đồ thị là một tập hợp hữu hạn các điểm, được gọi là các đỉnh, một số điểm được nối với nhau bằng các cung, được gọi là các cạnh của đồ thị. Rõ ràng, bất kỳ biểu đồ nào cũng có thể được liên kết với một hoặc nhiều lần lặp và nhóm hoán vị tương ứng với chúng. Người đọc có thể đã nhận thấy rằng các nhóm trò chơi được xem xét là biến có dấu (loại $A_n$) hoặc đối xứng (loại $S_n$). Hóa ra điều này không phải ngẫu nhiên: dưới một số trọng số của các hạn chế chung đối với cấu trúc của đồ thị, chúng sẽ luôn tương ứng với các nhóm thuộc loại $A_n$ hoặc loại $S_n$. Để hình thành một mẫu biên tập chính xác hơn, chúng ta sẽ cần các định nghĩa sau.

Theo một chu trình đơn giản $k$ ($k \geqslant 3$), chúng tôi muốn nói đến một chuỗi các đỉnh của đồ thị $P_1,...,P_k$ thỏa mãn các điều kiện sau:

1) $P_1 = P_k$ (nghĩa là đỉnh đầu và đỉnh cuối của chu trình trùng nhau);
2) $P_i$ và $P_{i+1}$ được kết nối bằng một cạnh ($i=1,...,k-1$),

⟦folio none⟧

3) $P_i \neq P_j$ tại $i \neq j$ ($i, j=1, \dots, k-1$).

Chúng ta sẽ gọi một đồ thị là đồ thị tuần hoàn nếu hai đỉnh bất kỳ của đồ thị này thuộc một chu trình đơn nào đó.

Định lý. Giả sử $\Gamma$ là một đồ thị tuần hoàn tùy ý có các đỉnh $P_0, P_1, \dots, P_n$ và $G(\Gamma)$ là một nhóm cerra “di chuyển dọc theo $\Gamma$” với các mã thông báo 1,..., $n$. Khi đó khẳng định sau đây là đúng:

1) nếu tất cả các chu trình đơn $\Gamma$ có độ dài chẵn thì $G(\Gamma)$ trùng với nhóm $A_n$;

2) nếu đồ thị $\Gamma$ khác với đồ thị $\Gamma_6$ được mô tả trong hình 10 và chứa ít nhất một chu trình đơn giản có độ dài lẻ thì $G(\Gamma)$ trùng với nhóm $S_n$.

Chúng ta bỏ qua chứng minh của khẳng định này. Lưu ý rằng một phần trường hợp của định lý này đã được chứng minh trước đó. Một ngoại lệ thú vị có liên quan đến biểu đồ $\Gamma_6$ (hình 10). Tất cả các hoán vị của nhóm $G(\Gamma_6)$ đều được tính toán trên máy tính và người ta thấy rằng đó là tập con thực sự của nhóm $S_6$, bao gồm 120 phần tử. Nếu chúng ta muốn trò chơi “di chuyển dọc theo biểu đồ $\Gamma_6$” luôn có lời giải thì chúng ta phải sử dụng ít nhất ba ô giống hệt nhau. Đây là biểu đồ duy nhất có thuộc tính này.

Sửa đổi trò chơi

Bây giờ chúng ta hãy xem xét một số sửa đổi của “di chuyển qua đồ thị” liên quan đến việc lật chip và các hạn chế đối với “quy tắc di chuyển”.

Hãy để các viên gạch của trò chơi NHÀ có hình vuông và sơn hai mặt: một mặt trắng và mặt còn lại màu đen. Hãy đặt các quân chip lên sân chơi như minh họa ở hình 7, và một số trong số chúng sẽ được đặt với mặt trắng hướng lên và một số có mặt đen hướng lên. Ngoài các quy tắc cũ về di chuyển chip trên sân chơi, chúng tôi sẽ giới thiệu một thao tác mới $R$: nếu ô số 0 trống, thì bạn có thể đồng thời lật tất cả các chip nằm trong các ô 4, 5 và 6. Mục tiêu của trò chơi là sử dụng các phép biến đổi và thao tác hợp lệ $R$ để lật tất cả các chip có mặt trắng lên (“bật đèn trong cửa sổ”). Vấn đề được đặt ra bằng cách viết các số tương ứng từ 1 đến 9 lên mặt trắng của mỗi con chip và yêu cầu khi kết thúc trò chơi, mỗi con chip không chỉ có mặt trắng hướng lên mà còn phải chiếm ô có số tương ứng. Chúng tôi sẽ gọi trò chơi này là CỬA SỔ GLOWING.

Bài tập 19. Tìm thuật toán lời giải cho các biến thể chung của trò chơi CỬA SỔ GLOWING.

Tất nhiên, đây không phải là ví dụ duy nhất về việc giới thiệu khả năng định hướng lại các quân cờ một cách hiệu quả trong các trò chơi như “di chuyển dọc theo biểu đồ”. Ví dụ, trong bài viết của A. Kalinin “Lúc đầu chỉ có một khối lập phương” (“Khoa học và Cuộc sống”),

(Phần kết xem trang 60)
