---
id: 1972-2-hatset-metodyi-rascheta-ekvivalentnyih-soprotivleniy-520e8cb1
issue: kvant_1972_2
year: 1972
number: "2"
title: Phương pháp tính điện trở tương đương
authors:
  - Хацет А. Б.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 56
page_last: 60
page_labels: 54, 56, 58
tag: J1P3
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 7a0bed42ccd3f99ae1b6b9ff5e34fb59ba448fd662c50a5091473be6f2439fd5
prompt_sha256: draft-1
translated_from: content/ru/1972/02/articles/13_hatset-metodyi-rascheta-ekvivalentnyih-soprotivleniy-520e8cb1.md
source_content_sha256: e5f645ce8109633dc00855dc538629629b33c84238a796db636f41a14bd1e017
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 54⟧

1. Phương pháp nút tương đương

Ý tưởng đằng sau phương pháp này là coi các nút khác nhau của mạch điện có điện thế bằng nhau như một nút. Trong trường hợp này, điện thế trong nút “được dán” thu được bằng tổng điện thế của các nút ban đầu.

Nếu các nút tương đương được kết nối bằng một dây dẫn (không có điện trở), thì trạng thái điện ở tất cả các nút và nhánh của mạch không thay đổi, vì sẽ không có dòng điện chạy qua dây dẫn này.

Hãy xem xét các ví dụ.

Bài toán 1. Tìm điện trở tương đương với đoạn mạch như hình 1, $a$ (tất cả các điện trở trong sơ đồ đều giống nhau và bằng $r$).

Lời giải. Dễ hiểu là các nút 1, 2 và 3 có tiềm năng như nhau. Trên thực tế, từ các thông điệp đối xứng, rõ ràng dòng điện chạy qua các nhánh A-1, A-2 và A-3 là như nhau. Do đó, do điện trở của các nhánh này bằng nhau nên độ sụt điện thế trên chúng cũng như nhau và điện thế ở các nút 1, 2 và 3 cũng như nhau.

Tương tự, có thể chỉ ra rằng các nút 4, 5 và 6 cũng có điện thế bằng nhau (tương đương).

Rõ ràng là điện trở mạch sẽ không thay đổi nếu các nút tương đương 1, 2 và 3 được kết nối với nhau. Điện trở của mạch sẽ không thay đổi nếu bạn kết nối ba nút tương đương thứ hai.

Sau khi thực hiện điều này, chúng ta thu được một mạch tương đương với mạch này (Hình 1, 6). Điện trở của mạch này không khó tìm: điện trở của đoạn $AN$ là $\frac{1}{3} r \left( \frac{1}{R_{AN}} = \frac{1}{r} + \frac{1}{r} \right)$, điện trở của đoạn $NM$ là $\frac{1}{6} r$, và điện trở của đoạn $MB$ là $\frac{1}{3} r$. Vì vậy $R_{AB} = \frac{5}{6} r$.

⟦folio 56⟧

Cơm. 3.

Trên thực tế không có dòng điện chạy qua phần $FF'$. Pozny có thể loại bỏ phần $FF'$ và ta có được mạch tương đương như Hình 4, b. Sau khi biến đổi đơn giản mạch điện (Hình 4, θ), có thể dễ dàng tính được điện trở của nó là $R = \frac{7}{6} r$.

3. Phương pháp "tái tạo" các nút

Phương pháp này cũng liên quan chặt chẽ với phương pháp các nút tương đương. Nếu việc thay thế một số nút tương đương bằng một (nút kết nối) dẫn đến một mạch tương đương, thì việc thay thế ngược lại một nút bằng một số nút tương đương sẽ không vi phạm các điều kiện điện trong phần còn lại của mạch.

Hãy để chúng tôi đưa ra ví dụ về các mạch mà sự chuyển đổi như vậy là phù hợp.

Bài 5. Tìm điện trở của đoạn mạch như hình 5, a.

Hãy thay thế nút $O$ bằng các nút khay; $O_1$, $O_2$ và $O_3$ (Hình 5, b). Tuy nhiên, chúng ta vẫn cần chứng minh rằng các mạch này là tương đương. Để tương đương với mạch, các nút $O_1$, $O_2$ và $O_3$ phải tương đương. Nhưng điều này rất indo, vì hiệu điện thế $\varphi_{O_2}$ - $\varphi_A$ bằng một nửa hiệu điện thế của các điểm $A$ và $B$: $\varphi_{O_2} - \varphi_A = \frac{1}{2} u_{AB}$.

Tương tự, từ các báo cáo đối xứng về sự bao gồm điện trở, không khó để tìm thấy $\varphi_{O_1} - \varphi_A = \frac{1}{2} u_{AB}$ và $\varphi_{O_3} - \varphi_A = \frac{1}{2} u_{AB}$. Do đó, $\varphi_{O_1} = \varphi_{O_2} = \varphi_{O_3}$, tức là các nút $O_1$, $O_2$ và $O_3$ là tương đương nhau. Bây giờ việc tìm ra điện trở mạch không khó. Nó bằng 0,8 $r$ (Hình 5, θ).

⟦folio 58⟧

Cơm. 7.

Bài 7. Tìm điện trở $R$ của mạch điện như hình 7, a.

Lời giải. Hãy thay nhánh $OC$ bằng hai nhánh song song có điện trở bằng nhau $2 r$. Sau đó, chúng tôi chia nút $C$ thành các nút tương đương $C_1$ và $C_2$ (sự tương đương của chúng tuân theo các thông điệp tương đối đối xứng của các nút $A$ và $O$). Mạch điện ở Hình 7, 6 tương đương với mạch điện ở Hình 7, a. Hãy tìm điện trở của nó. Phần $BO$ và $BC_1O$ được kết nối song song. Khả năng chống tư thế $R_{BO} = \frac{3}{4} r$.

Tương tự như vậy, $R_{OD} = \frac{3}{4} r$. Bây giờ các nút $A$ và $O$ được kết nối bằng ba nhánh song song có điện trở $\frac{7}{4} r, r, \frac{7}{4} r$. Tổng điện trở của mạch là $R = \frac{7}{15} r$ (Hình 7, d).

5. Phương pháp lặp lại

Phương pháp lặp lại lời giải bài toán là các phương pháp chung trong đó bài toán được giải theo các bước và ở bước $n$ cần sử dụng kết quả thu được ở các bước trước. Phương pháp hồi quy trong bài toán tính điện trở mạch đặc biệt thuận tiện khi mạch có cấu trúc lặp và số lượng điện trở lớn.

Bài tập 8. Tìm điện trở của mạch điện như hình 8, a, trong đó $r_1 = \frac{r}{2}, r_2 = \frac{r}{2}, r_3 = r_4 = r_5 = r_6 = r$.

Lời giải. Chúng ta hãy vẽ lại mạch điện như hình 8, 6. Rõ ràng là phép tính phải được thực hiện từ đầu $B$. Thay điện trở $r_3, r_6$ và $r_2$ bằng điện trở tương đương $R = r_2 + \frac{r_3 r_6}{r_3 + r_6} = r$, ta thu được mạch như hình 8, c. Bây giờ, các điện trở $R, r_5$ và $r_1$ một lần nữa có thể được thay thế bằng $R_1 = r_1 + \frac{R r_5}{R + r_5} = r$ tương đương (Hình 8, d). Tổng điện trở của mạch là

$$\frac{R_1 r_4}{R_1 + r_4} = \frac{r}{2}.$$
