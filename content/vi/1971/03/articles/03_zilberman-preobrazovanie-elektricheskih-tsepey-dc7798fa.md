---
id: 1971-3-zilberman-preobrazovanie-elektricheskih-tsepey-dc7798fa
issue: kvant_1971_3
year: 1971
number: "3"
title: Biến đổi mạch điện
authors:
  - Зильберман А. Р.
rubric: osnovnye-stati
page_first: 12
page_last: 16
page_labels: 10, 12, 13, 14
tag: K0OM
lang: vi
source: kvant_digital
extraction: vision
content_sha256: d5fd6df49a938439819b80002e94df43175da98011379d7a49da8334fb6e4bd4
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1971/03/articles/03_zilberman-preobrazovanie-elektricheskih-tsepey-dc7798fa.md
source_content_sha256: 01dd688f3b4cbb2dfd583e5ea40e2e64724b417dc5de9699fb38bc71c261e9a0
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦folio 10⟧

Bài này nói về một phương pháp cho phép đơn giản hóa các bài toán phức tạp về tính toán mạch điện.

Ta hiểu «biến đổi mạch» là gì? Giả sử ta có một sơ đồ phức tạp gồm các điện trở, có nhiều đầu nối và được nối với các nguồn. Hãy thay sơ đồ này bằng một sơ đồ khác, có cùng số đầu nối, sao cho điện trở giữa bất kỳ hai đầu nối nào của sơ đồ mới cũng giống như của sơ đồ cũ. Rõ ràng, các nguồn sẽ «không biết gì» về sự thay thế này, và các dòng điện mà mạch tiêu thụ sẽ vẫn như cũ. Nhưng có lẽ sẽ dễ tìm các dòng điện ấy hơn.

Do đó, nếu ta muốn tính các dòng điện trong một mạch phức tạp, có thể thay nó bằng một mạch tương đương đơn giản hơn. Khi đó các dòng điện bên trong phần được thay đổi. Vì vậy chỉ có thể làm như thế với phần mạch không trực tiếp quan tâm.

Các bạn đã gặp những sự thay thế như vậy.

Chẳng hạn, nếu trong mạch hai điện trở $r_1$ và $r_2$ được mắc nối tiếp, ta có thể thay chúng bằng một điện trở có giá trị bằng tổng $r_1 + r_2$. Nếu hai điện trở được mắc song song, chúng cũng có thể được thay bằng một điện trở, có giá trị $R = \frac{r_1 r_2}{r_1 + r_2}$

Đó là những ví dụ đơn giản nhất về biến đổi mạch. Còn chúng ta sẽ xét các sơ đồ phức tạp hơn.

Hãy xem các sơ đồ có ba đầu nối — «hình sao» (hình 1, a) và «hình tam giác» (hình 1, b) — được biến đổi qua lại như thế nào.

Các ký hiệu hơi khác thường (hình 1, b) rất tiện lợi, chỉ số cho biết điện trở được mắc giữa những điểm nào. Chẳng hạn, điện trở $R_{13}$ được mắc giữa các điểm 1 và 3, v.v.

Nếu ta muốn thay một trong các sơ đồ này bằng sơ đồ kia, cần tìm các quan hệ giữa $r$ và $R$ sao cho điện trở giữa bất kỳ các điểm nào đều như nhau đối với cả hai sơ đồ.

Trong sơ đồ «hình sao» (hình 1, a) điện trở-

⟦folio 12⟧

Hình 4.

«hình tam giác» ACD bằng «hình sao», như chỉ ra trên hình 4.

Bây giờ rõ ràng điện trở giữa các điểm A và B bằng
$$\frac{1}{3} + \frac{28}{33} = \frac{13}{11} \text{ ома}.$$

Ta đã thay «hình tam giác» ACD bằng «hình sao», nhưng có thể giải bài toán theo cách khác — thay «hình sao» ADB bằng «hình tam giác».

Bây giờ giả sử một pin có điện trở trong nhỏ không đáng kể và có suất điện động E=1 v được nối vào các điểm A và B. Cần tìm dòng điện qua đoạn CB.

Cần biến đổi mạch sao cho không động đến điện trở CB mà ta quan tâm. Phép biến đổi đã thực hiện trước đó (hình 4) là phù hợp.

Dùng $R_{AB} = \frac{13}{11} \text{ ома}$, ta được $I = \frac{E}{R_{AB}} = \frac{11}{13} a$. Sau chỗ phân nhánh, dòng điện chia theo tỉ lệ nghịch với điện trở các nhánh:

$$\frac{I_1}{I_2} = \frac{7}{4}.$$

Trong đó $I_1 + I_2 = I$. (I — dòng điện trước chỗ phân nhánh, $I_1$ — dòng điện trong nhánh trên, $I_2$ — dòng điện trong nhánh dưới).

Suy ra

$$I_1 = \frac{7}{13} a$$

Sẽ hơi phức tạp hơn nếu tìm dòng điện đi qua đoạn CD. Muốn vậy còn phải tìm dòng điện,

⟦folio 13⟧

Hình 6.

chiết áp. Hơn nữa, tổng các điện trở $5r+R_1$ và $7r+R_2$ vẫn không đổi. Hãy xem chúng phải như thế nào để điện trở toàn phần là lớn nhất. Ký hiệu $5r+R_1$ là $r_1$ và $7r+R_2$ là $r_2$. Khi đó điện trở chung của các phần mắc song song của mạch là $r_0 = \frac{r_1 r_2}{r_1 + r_2}$. Nếu tính đến $r_1+r_2 = const = c$, thì điện trở $r_0$ được biểu diễn như sau: $\frac{r_1 (c-r_1)}{c}$. Biểu thức này là lớn nhất khi số lớn nhất sлипель. Nhưng $y = (cr_1-r_1^2)$ — đó là phương trình của một parabol (hình 7), các nhánh của nó cắt trục hoành tại các điểm $O$ và $c$. Vì vậy tử số của phân số là lớn nhất khi $r_1 = \frac{c}{2}$. Vì $r_1+r_2 = c$, điều đó có nghĩa là điện trở giữa các điểm $A$ và $B$ là lớn nhất nếu $r_1=r_2$, tức là $5r+R_1=7r+R_2$, hay $R_1-R_2=2r$.

Rõ ràng điều này chỉ có thể nếu điện trở của toàn bộ biến trở $R=R_1+R_2$ không nhỏ hơn $2r$. Nếu không, điện trở cực đại giữa các điểm $A$ và $B$ đạt được khi con chạy của biến trở ở vị trí край.

Vậy, đáp số: $R \leq 2r$.

Phương pháp mà chúng tôi đã trình bày rất tiện cho việc biến đổi tuần tự một mạch phức tạp về dạng đơn giản. Nó cho phép tính toán hầu như mọi mạch phức tạp gồm các điện trở.

Phương pháp này có thể áp dụng cho các mạch không chỉ chứa điện trở.

Hãy chú ý rằng chúng ta hoàn toàn không nói ở đâu về các quá trình vật lí trong mạch, mà chỉ dùng biểu thức hình thức của định luật Ôm: $U=r \cdot I$. Từ đó suy ra rằng khi mắc nối tiếp, các đại lượng của chúng được cộng lại, còn khi mắc song song — các đại lượng nghịch đảo với điện trở được cộng lại $\left(\frac{1}{r_{06\pi}} = \frac{1}{r_1} + \frac{1}{r_2}\right)$. Rõ ràng, nếu những đại lượng vật lí nào khác được liên hệ bởi một định luật tương tự định luật Ôm, thì mọi kết luận của chúng ta cũng đúng đối với chúng.

Làm ví dụ, xét một mạch có tụ điện (hình 8). Ta biết rằng $Q=C \cdot U$, hay $U = \frac{1}{C} Q$.

⟦folio 14⟧

Hình 9.

So sánh điều này với biểu thức của định luật Ôm $U=r \cdot I$.

Có thể thấy rằng các định luật giống nhau, chỉ có điện tích thay cho dòng điện, còn thay cho điện trở là đại lượng nghịch đảo của điện dung. Điều đó có nghĩa là để tìm, chẳng hạn, điện tích trên các tụ điện, ta có thể làm như sau. Thay vì mạch chứa các tụ điện, vẽ một mạch chứa các điện trở, trong đó tụ điện có điện dung $x$ farađ được thay bằng điện trở $r = \frac{1}{x} \text{ om}$. Sau khi tính dòng điện trong mạch điện trở, có thể viết ngay các điện tích trên tụ điện: nếu qua điện trở có dòng điện $I=y$ ampe, thì trên tụ điện tương ứng sẽ có điện tích $Q=y$ culông.

Suất điện động của các pin trong phép biến đổi mạch như vậy không thay đổi. Nhưng, tất nhiên, trong mạch có tụ điện, điện trở trong của các pin không ảnh hưởng đến kết quả. Vì vậy, khi biến đổi mạch, ta phải bỏ điện trở trong của các pin.

Chẳng hạn, cần tìm điện tích trên tụ điện có điện dung $10 \text{ мкф}$ (hình 9). Tụ điện
