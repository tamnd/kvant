---
id: 1988-7-kasatkin-skolko-tsifr-v-chisle-100-3454c388
issue: kvant_1988_7
year: 1988
number: "7"
title: 100 có bao nhiêu chữ số!?
authors:
  - Касаткин В. Н.
rubric: raznoe
rubric_sub: Разное
page_first: 59
page_last: 61
page_labels: 57-59
tag: CUF9
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 07a25e3540df74703c48b86c945dc411c15f40ee55ff1677a4603c9ab9d72acb
prompt_sha256: draft-1
translated_from: content/ru/1988/07/articles/12_kasatkin-skolko-tsifr-v-chisle-100-3454c388.md
source_content_sha256: 4a2023e4be37ab160af4f22e4dffde582017ad4780d6bba1041131b92e6c1241
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 57⟧

100 có bao nhiêu chữ số!?

V. N. KASATKIN

Có vẻ dễ dàng nhận được điểm đáp số cho câu hỏi này. Trên thực tế, dưới đây là chương trình tính giai thừa của số $N$; làm việc trên một chương trình như vậy, máy tính sẽ tính toán và hiển thị hoặc in ra số 100!. Tất cả những gì chúng ta phải làm là đếm số chữ số trong số do máy tạo ra.

Nhưng những nỗ lực áp dụng cách tiếp cận này với số lượng lớn $N$ đều dẫn đến thất bại - thực tế là hầu hết máy tính cá nhân không thể hiển thị một số có hơn 15 chữ số trên màn hình.

Dưới đây là giai thừa của một số số lớn hơn 10, được tính trên máy tính loại Corvette:
$$10! = 3628800;$$
$$11! = 39916800;$$

$$12! = 479001600;$$
$$13! = 6227020800;$$
$$14! = 87178291200;$$
$$15! = 1307674368000;$$
$$16! = 20922789888000;$$
$$3.55687428096E+14 = 17!$$

Giai thừa số 17 không còn vừa trên màn hình - lưới bit bị tràn và máy tính, cùng với kết quả chính xác 355687428096000, đã đưa ra giá trị của số 17! ở dạng chuẩn hóa. Máy tính gợi ý rằng chúng ta giả định rằng
$$17! = 3.55687428096E+14 = 3,55687428096 \cdot 10^{14}.$$

Phải chăng điều này có nghĩa là về nguyên tắc, chúng ta không thể lấy giai thừa của một số lớn trên máy tính, chẳng hạn như 100!. Đáp số đơn giản: không, không có nghĩa. Chúng ta có thể sử dụng máy tính để có được bản ghi đầy đủ về số 100! mà không mất một chữ số nào.

Điều này đạt được bằng cách sử dụng sự khéo léo của lập trình viên. Bài toán mà chúng ta sắp giải quyết là

⟦folio 58⟧

Hình 1.

khá đáng chú ý cho việc lập trình. Chúng ta sẽ nói về cách một người sử dụng máy tính: anh ta hành động theo khuôn mẫu hay sau khi đi sâu vào các tính năng của máy, khiến nó hoạt động theo cách khác thường, không chuẩn.

Trước khi chúng ta nói về một chương trình gần như tự nhiên để tìm tất cả các chữ số của số 100!, chẳng hạn như về một số công cụ của ngôn ngữ BASIC cần thiết trong tương lai.

Chương trình sẽ sử dụng hàm “phần nguyên của giá trị đối số”. Trong BASIC, hàm này được ký hiệu là INT(X) - đối với bất kỳ X thực nào, giá trị của hàm INT(X) bằng giá trị nguyên của X không vượt quá nó, ví dụ:

$$\text{INT}(2.5) = 2, \text{INT}(0.002) = 0,$$
$$\text{INT}(-6.3) = -7.$$

Điều kiện: Tất cả các chữ số của số giai thừa thu được được coi là giá trị của biến $a_i$, trong đó $i=1, 2, \ldots$. Trước khi bắt đầu tính toán $N!$, mỗi biến $a_i$ bằng 0; Hãy bắt đầu tính toán (hình 1).

Trong quá trình tính toán, giá trị của các biến $a_i$ thay đổi.

Hãy nhớ lại rằng nếu đã biết giai thừa của số $(k-1)$ thì rất dễ tìm được giai thừa của số $k$:

$$k! = k \cdot (k-1)!.$$

Hãy áp dụng quy tắc này để nhận được 4!, nếu chúng ta biết rằng 3!=6. Nó hoạt động như thế này: chúng ta nhân 6 với 4 và nhận được 24. Chúng ta lấy số 4 làm giá trị của biến $a_1$ và số 2 - giá trị của biến $a_2$. Tất cả những hành động này có thể được mô tả dưới dạng sơ đồ như trong hình 2.

Hãy tiếp tục công việc của chúng ta: tính 5!. Để làm điều này, hãy nhân 4!=24 với 5 và biến các số tương ứng thành giá trị của các biến (xem hình 3).

Chúng ta hãy xem xét kỹ hơn quá trình thay đổi các số $k$ và $(k-1)!$. Nhân một số có nhiều chữ số với một số khác dẫn đến nhân và cộng các chữ số. Đồng thời, chúng ta có thể phân biệt rõ ràng chữ số bậc thấp và chữ số bậc cao.

Hãy tạm dừng cuộc thảo luận về bài toán nói chung và tìm hiểu cách giải một số nhỏ nhưng quan trọng hơn nữa bài toán: hãy dạy máy tính cách tách chữ số hàng chục và chữ số hàng đơn vị trong một số thập phân có hai chữ số.

Cần phải tạo một chương trình, công việc của nó trên máy tính, sau khi hiển thị nó bằng một số có hai chữ số, biến $a_1$ cho giá trị bằng số đơn vị và biến $a_2$ cho giá trị bằng số hàng chục.

Đặt biến $A$ có giá trị bằng số thập phân có hai chữ số (ví dụ: 73). Chia giá trị $A$ cho 10 và lấy toàn bộ phần từ kết quả - đây sẽ là chữ số hàng chục:

$$\text{LET}A(2) = \text{INT}(A/10),$$
$$\text{t. e. } a_2 = [7,3] = 7.$$

Nếu bây giờ từ giá trị $A$ thu được $a_2 \cdot 10$, thì chúng ta nhận được chữ số hàng đơn vị trong số ban đầu $A$:

$$\text{LET}A(1) = A - A(2)*10,$$
$$\text{t. e. } a_1 = 73 - 7 \cdot 10 = 3.$$

Hãy quay lại bài toán lấy số 5! Chúng ta nhớ rằng để làm điều này, chúng ta cộng số 4!=24 nhân với 5. Chúng ta cũng nhớ rằng số

⟦folio 59⟧

Hình 4.

4!=24 được lưu trữ một cách bất thường: số 4 là giá trị của biến $a_1$ và số 2 là giá trị của biến $a_2$. Chúng ta có thể nói một cách hình tượng rằng số 2 và số 4 lần lượt được lưu trữ trong các ô $a_2$ và $a_1$.

Nhân nội dung của ô $a_1$ với 5 sẽ cho kết quả có hai chữ số: $4 \times 5=20$. Chúng tôi sẽ coi chữ số bậc thấp (trong trường hợp này là 0) là giá trị mới của biến $a_1$ và tạm thời giữ chữ số 2 “trong tâm trí chúng tôi”. Sau đó, chúng ta nên nhân số được lưu trong $a_2$ với 5 và thêm số 2 vào sản phẩm thu được, trước đó đã lấy nó từ bộ nhớ của chúng ta. Kết quả của hành động: $5!=5 \cdot 4!=5 \cdot 24=120$ (hình 4). Sau khi hoàn thành tất cả các hành động, các biến $a_1$, $a_2$ và $a_3$ nhận được các giá trị mới $a_1\neq0$, $a_2=2$ và $a_3=1$.

Ngay cả khi con số là $(k-1)$! không chứa hai mà là ba chữ số trở lên, một sơ đồ để lấy các chữ số của số $k$! vẫn giữ nguyên (hình 5).

Hình 5.

cent $m_i$ có thể là số có nhiều chữ số.

Sử dụng văn bản chương trình sau:

```basic
REM ВЫЧИСЛЕНИЕ ФАКТОРИАЛА ЧИСЛА N
DIM A(100)
INPUT N
FOR I=2 TO 100
A(I)=0:NEXT I
A(1)=1:L=1
FOR K=1 TO N
R2=0:R1=0:I=1
IF R2=0 THEN IF I>L THEN 80
R=A(I)*K+R2
R2=INT(R/(10000!))
R1=R-R2*(10000!)
A(I)=R1
I=I+1
GOTO 40
L=I-1
NEXT K
FOR J=1 TO I-1
PRINT A(I-J);
NEXT J
END
```

Kết quả của việc sử dụng chương trình chúng tôi nhận được*:

```text
100!=93 326215 443944 152681 699238 856266 700490 715968 264381 6214
963 895217 599993 229915 608941 463976 156518 286253 697920 8272
251 185210 916864 0 0 0
```

Đương nhiên, số $k$ không chỉ có thể có một chữ số mà còn có thể có hai chữ số. Trong trường hợp này, hệ số Itak, số có 100! có 158 chữ số - khái niệm về một con số khổng lồ!

*) Khi máy in ra một số, nó sẽ ghi số đó theo nhóm 6 chữ số, bỏ qua số 0 ban đầu. Vì vậy, trong bản in ở trên, nhóm chữ số 6214 phải được coi là nhóm $\odot 6214$, nhóm 963 - dưới dạng $\odot 963$, 8272 - dưới dạng $\odot 8272$, 251 - dưới dạng $\odot 251$ và $\odot$ khác dưới dạng nhóm $\odot 0$
