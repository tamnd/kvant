---
id: 1990-3-erdniev-mantsaev-teoremyi-chevyi-i-menelaya-b70c2138
issue: kvant_1990_3
year: 1990
number: "3"
title: Định lý Ceva và Menelaus
authors:
  - Эрдниев Б. П.
  - Манцаев Н.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 58
page_last: 61
page_labels: 56-59
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 31c67a195a0c401806a9ddcca1fa604f61651e276cf0c088146ea91e270ca453
prompt_sha256: draft-1
translated_from: content/ru/1990/03/articles/13_erdniev-mantsaev-teoremyi-chevyi-i-menelaya-b70c2138.md
source_content_sha256: b8b94f135b8b7badcc1379eb1d4cb895454e08edc28e4e01fdbf4a4a36d29f8b
translation_model: draft
translation_run: vi-draft-gaps-2026-11-01
translation_quality: draft
---

⟦folio 56⟧

---
running_head:
folio:
---

Định lý Ceva
và Menelaus

V. ERDNIEV,
N. MANTSAYEV

Từ khóa học ở trường, bạn đã biết các định lý về các điểm đáng chú ý trong một tam giác: ba đường phân giác (đường trung tuyến, đường cao) cắt nhau tại một điểm. Những tính chất này là hệ quả của các định lý mà bài viết này đề cập tới. Vì vậy, chúng ta sẽ nói về các định lý của Ceva và Menelaus, cũng như một số khái quát hóa của chúng đối với không gian ba chiều.

Định lý Menelaus

Định lý này đã được chứng minh bởi nhà toán học Hy Lạp cổ đại Menelaus

Alexandria vào thế kỷ 1 sau Công nguyên.

Định lý 1. Cho các điểm $A_1$ và $C_1$ nằm trên các cạnh BC và AB của tam giác ABC (hình 1), và điểm $B_1$ trên phần kéo dài cạnh AC của tam giác này. Để các điểm $A_1$, $B_1$, $C_1$ nằm trên cùng một đường thẳng thì điều cần và đủ là đẳng thức

$$\frac{AC_1}{C_1B} \cdot \frac{BA_1}{A_1C} \cdot \frac{CB_1}{B_1A} = 1.$$

Bằng chứng. Đầu tiên ta chứng minh sự cần thiết. Cho các điểm $A_1$, $B_1$, $C_1$ nằm trên đường thẳng $l$ và $AA_0 = h_1$, $BB_0 = h_2$, $CC_0 = h_3$ - các đường vuông góc lần lượt rơi từ điểm $A$, $B$, $C$ đến đường thẳng $l$ (xem hình 1). Từ sự giống nhau của các tam giác $AA_0C_1$ và $BB_0C_1$ ta thu được

$$\frac{AC_1}{C_1B} = \frac{h_1}{h_2}.$$

Tương tự, xét các cặp tam giác đồng dạng khác, ta thu được

⟦folio 57⟧

---
running_head:
folio:
---

$$\frac{BA_1}{A_1C} = \frac{h_2}{h_3}, \frac{CB_1}{B_1A} = \frac{h_3}{h_1}.$$

Tỷ lệ thay đổi thu được, chúng tôi đạt được sự bình đẳng cần thiết.

Sự đầy đủ. Đặt các điểm $A_1, B_1, C_1$ (hình 2) nằm trên đường thẳng $BC, AC, AB$ sao cho
$$\frac{AB_1}{B_1C} \cdot \frac{CA_1}{A_1B} \cdot \frac{BC_1}{C_1A} = 1.$$
Hãy chứng minh rằng các điểm $A_1, B_1, C_1$ nằm trên cùng một đường thẳng.
Chúng ta hãy vẽ đường $A_1B_1$ và chứng minh rằng điểm $C_1$ thuộc về nó.
Hãy giả sử rằng đây không phải là trường hợp. Đầu tiên, hãy chú ý rằng đường thẳng $A_1B_1$ không song song với đường thẳng $AB$ (tại sao?). Đặt $T$ là giao điểm của đường $A_1B_1$ và $AB$ (xem hình 2). Sau đó
$$\frac{AB_1}{B_1C} \cdot \frac{CA_1}{A_1B} \cdot \frac{BT}{TA} = 1.$$ (1)

Từ điều kiện và đẳng thức (1) suy ra rằng
$$\frac{BT}{TA} = \frac{BC_1}{C_1A}.$$

Vì các điểm $T$ và $C_1$ nằm ngoài đoạn $AB$ nên sự trùng hợp của chúng dễ dàng suy ra từ bổ đề sau.

Bổ đề. Cho $A$ và $B$ là hai điểm phân biệt. Khi đó, với bất kỳ $k > 0, k \neq 1$ nào trên đường thẳng $AB$ đều có hai và chỉ hai điểm $U$ và $V$ cũng như $\frac{AU}{UB} = \frac{AV}{VB} = k$, và một trong những điểm này thuộc đoạn $AB$, còn điểm kia nằm ngoài đoạn $AB$.

Bằng chứng. Hãy giới thiệu tọa độ trên đường thẳng $AB$, lấy điểm $A$ làm gốc tọa độ (hình 3). Đặt $k > 1$ để xác định. tọa độ của điểm mong muốn $U$, nằm bên trong đoạn $AB$, thỏa mãn phương trình $\frac{u}{b - u} = k$, từ đó $u = \frac{k}{k + 1} b$.

Điểm $V$ bên ngoài đoạn $AB$ được tìm thấy duy nhất từ ​​phương trình $\frac{v}{v - b} = k$, từ đó $v = \frac{kb}{k - 1}$.

Trường hợp $0 < k < 1$ khác với khoảng cách chỉ ở chỗ điểm $V$ phải được tìm ở bên trái điểm $A$.

Định lý Menelaus thường được phát biểu khác nhau, sử dụng khái niệm mối quan hệ giữa hướng

⟦folio 58⟧

---
running_head:
folio:
---

Chúng tôi giả định rằng $\frac{AU}{UB} = k$ nếu $\vec{AU} = k\vec{UB}$. Rõ ràng là nếu các vectơ $\vec{AU}$ và $\vec{UB}$ có hướng bằng nhau thì $k > 0$. Nếu các vectơ này hướng ngược nhau thì $k < 0$, và tất nhiên, số $|k|$ bằng tỷ lệ độ dài của các đoạn $AU$ và $UB$.

Với sự hiểu biết về mối quan hệ giữa các phân đoạn, định lý Menelaus được phát biểu như sau. Cho ba điểm $A_1, B_1, C_1$ lần lượt nằm trên các đường thẳng BC, AC và AB. Để các điểm này thuộc cùng một đường thẳng thì điều cần và đủ là

$$\frac{AC_1}{C_1B} \cdot \frac{BA_1}{A_1C} \cdot \frac{CB_1}{B_1A} = -1.$$

Chúng tôi khuyến khích độc giả chứng minh định lý này như một bài tập.

Định lý Menelaus cho phép khái quát hóa lập thể thú vị.

Định lý 2. Nếu mặt phẳng $\mu$ cắt các cạnh AB, BC, CD và DA của tứ diện ABCD tại các điểm $A_1, B_1, C_1, D_1$ thì

$$\frac{AA_1}{A_1B} \cdot \frac{BB_1}{B_1C} \cdot \frac{CC_1}{C_1D} \cdot \frac{DD_1}{D_1A} = 1.$$ (2)

Ngược lại, nếu đẳng thức (2) thỏa mãn cho bốn điểm $A_1, B_1, C_1, D_1$ lần lượt nằm trên các cạnh AB, BC, CD, DA của tứ diện thì bốn điểm này cùng nằm trong một mặt phẳng.

Bằng chứng. Gọi $h_1, h_2, h_3, h_4$ lần lượt là khoảng cách từ các điểm A, B, C, D đến mặt phẳng $\mu$ (hình 4). Sau đó

$$\frac{AA_1}{A_1B} = \frac{h_1}{h_2}, \frac{BB_1}{B_1C} = \frac{h_2}{h_3}, \frac{CC_1}{C_1D} = \frac{h_3}{h_4},$$

$$\frac{DD_1}{D_1A} = \frac{h_4}{h_1}.$$

Nó vẫn còn để nhân các tỷ lệ kết quả.

Để chứng minh định lý ngược lại, ta vẽ mặt phẳng $A_1B_1C_1$. Cho mặt phẳng này cắt cạnh DA tại điểm T (hình 5). Theo chứng minh

$$\frac{AA_1}{A_1B} \cdot \frac{BB_1}{B_1C} \cdot \frac{CC_1}{C_1D} \cdot \frac{DD_1}{D_1A} = 1,$$

và theo điều kiện

$$\frac{AA_1}{A_1B} \cdot \frac{BB_1}{B_1C} \cdot \frac{CC_1}{C_1D} \cdot \frac{DD_1}{D_1A} = 1.$$

Pozotomu

$$\frac{DT}{TA} = \frac{DD_1}{D_1A},$$

và theo bổ đề, điểm T và D$_1$ trùng nhau. Tuyên bố đã được chứng minh.

⟦folio 59⟧

---
running_head:
folio:
---

1. Chứng minh rằng nếu tất cả các cạnh của một tứ giác không gian tiếp xúc với một mặt cầu nhất định thì bốn điểm tiếp xúc nằm trong cùng một mặt phẳng.
2. Chứng minh rằng các đoạn thẳng nối trung điểm các cạnh đối diện của một tứ diện cắt nhau tại một điểm.

**Định lý Ceva**

Định lý đáng chú ý này đã được chứng minh vào thế kỷ 17 bởi nhà toán học và thành phần Cheva.

Định lý 3. Cho các điểm $A_1, B_1, C_1$ lần lượt nằm trên các cạnh BC, AC và BA của tam giác ABC (hình 6). Để các đoạn $AA_1, BB_1$ và $CC_1$ giao nhau tại một điểm, điều cần thiết và đủ là sự tương ứng

$$\frac{AC_1}{C_1B} \cdot \frac{BA_1}{A_1C} \cdot \frac{CB_1}{B_1A} = 1.$$ (3)

(Các phân đoạn $AA_1, BB_1$ và $CC_1$ đôi khi được gọi.)
Bằng chứng. Sự cần thiết. Để các đoạn $AA_1, BB_1$ và $CC_1$ cắt nhau tại điểm M bên trong tam giác ABC (hình 7). Chúng ta hãy ký hiệu bằng $S_1, S_2, S_3$ diện tích của các tam giác AMC, CMB và AMB, và bằng $h_1, h_2$ lần lượt là khoảng cách từ các điểm A và B đến đường thẳng MC.

Sau đó

$$\frac{AC_1}{C_1B} = \frac{h_1}{h_2} = \frac{S_1}{S_2},$$

thuốc giảm đau

$$\frac{BA_1}{A_1C} = \frac{S_3}{S_1}, \frac{CB_1}{B_1A} = \frac{S_2}{S_3}.$$

Sau khi kiểm tra các tỷ lệ thu được, chúng tôi tin chắc về tính đúng đắn của định lý.

Sự đầy đủ. Cho các điểm $A_1, B_1, C_1$ nằm trên các cạnh BC, CA và AB của tam giác và thỏa mãn (3), M là giao điểm của các đoạn $AA_1$ và $BB_1$, đoạn CM cắt cạnh AB tại điểm Q. Khi đó, theo những gì đã được chứng minh,

$$\frac{AQ}{QB} \cdot \frac{BA_1}{A_1C} \cdot \frac{CB_1}{B_1A} = 1,$$

Vì thế

$$\frac{AQ}{QB} = \frac{AC_1}{C_1B}.$$

Từ bổ đề hàm ý sự trùng hợp của các điểm: $Q=C_1$. Tính đầy đủ đã được chứng minh.

Bài tập

3. Chứng minh rằng các đoạn thẳng sau đây trong một tam giác cắt nhau tại một điểm: a) các đường trung tuyến; b) các đường phân giác; b) chiều cao; d) các đoạn nối các đỉnh của tam giác từ điểm tiếp xúc của các cạnh đối diện với đường tròn nội tiếp (điểm Gergon); d) các đoạn đi qua các đỉnh và chia chu vi làm đôi; e) các đoạn nối các đỉnh của tam giác từ điểm tiếp xúc của các cạnh đối diện với các đường tròn nội tiếp.

Bây giờ chúng ta chuyển sang khái quát hóa không gian của định lý Ceva.

Định lý 4. Cho M là điểm nằm trong tam giác ABCD, $A_1, B_1, C_1$ và $D_1$ là giao điểm của các mặt phẳng CMD, AMD, AMB và CMB với các cạnh (hình 8) AB, BC, CD và DA tương ứng. Sau đó

$$\frac{AA_1}{A_1B} \cdot \frac{BB_1}{B_1C} \cdot \frac{CC_1}{C_1D} \cdot \frac{DD_1}{D_1A} = 1.$$ (4)

Ngược lại, nếu thỏa mãn (4) điểm $A_1, B_1, C_1, D_1$ nằm trên các cạnh tương ứng thì các mặt phẳng ABC, BCD, CDA và DAB đi qua một điểm.

Dễ dàng chứng minh tính cần thiết bằng cách lưu ý rằng các điểm $A_1, B_1, C_1$ và $D_1$ (xem hình 8) nằm trong cùng một mặt phẳng (đây là mặt phẳng đi qua các đường thẳng $A_1C_1$ và $B_1D_1$, cắt nhau tại điểm M) và áp dụng định lý Menelaus.

Định lý ngược có thể được chứng minh giống như định lý ngược của Menelaus trong không gian: bạn cần vẽ một mặt phẳng đi qua các điểm $A_1, B_1, C_1$ và dùng bổ đề chứng minh rằng mặt phẳng này cắt cạnh DA tại điểm $D_1$.

Bài tập

4. Cho tam giác ABC có ba dây chuyền $AA_1, BB_1$ và $CC_1$ cắt nhau tại điểm O. Khi đó

$$\frac{OA_1}{A_1A} + \frac{OB_1}{B_1B} + \frac{OC_1}{C_1C} = 1.$$

5. Chứng minh rằng đường trung tuyến của một tam giác tập trung tại một điểm (đường trung tuyến của tam giác là đoạn nối đỉnh của nó với tâm của mặt đối diện).

6. Trong tam giác ABCD, tổng các cạnh đối diện bằng nhau. Chứng minh rằng có một hình cầu tiếp xúc với tất cả các cạnh của tam giác này.
