---
id: 1983-1-shternberg-standartnyie-priemyi-programmirovaniya-e7d4c16d
issue: kvant_1983_1
year: 1983
number: "1"
title: Kỹ thuật lập trình tiêu chuẩn
authors:
  - Штернберг Л. Ф.
rubric: raznoe
rubric_sub: Разное
page_first: 52
page_last: 53
page_labels: 50-51
tag: L0WC
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 5c3728afdd34d0f57669399ad1b9f20248aada95e2d06200f8806fff640bdf84
prompt_sha256: draft-1
translated_from: content/ru/1983/01/articles/13_shternberg-standartnyie-priemyi-programmirovaniya-e7d4c16d.md
source_content_sha256: c797f94aa909457bee19d64912cbacf7efdd9f49cbc236fe71a80aeb080cf544
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 50⟧

Kỹ thuật lập trình tiêu chuẩn

Bài 4. Xử lý mảng đồng bộ và không đồng bộ

Nếu bạn không thể tìm thấy điểm chung và khác biệt trong các điều kiện bài toán, hãy thử trả lời câu hỏi: chẳng hạn, phần tử nào của mảng sẽ được xử lý ở bước thứ 5 của thuật toán (chúng tôi coi bước này là xử lý một phần tử trong bất kỳ mảng nào)? Trong câu hỏi thứ 3 và thứ 4 bài toán đáp số, câu hỏi này rất đơn giản: bước thứ 5 xử lý phần tử thứ 5 trong mảng A và B (thứ 3 bài toán), phần tử thứ 5 trong mảng B và phần tử thứ 10 trong mảng A (thứ 4 bài toán). Đối với hai bài toán đầu tiên, ở bước thứ 5, phần tử thứ 5 của mảng mà chúng tôi đếm các bước được xử lý, nhưng chúng tôi không thể nói bất cứ điều gì về các mảng khác (ngoại trừ phần tử có số cao hơn hoặc thấp hơn trong mảng này được xử lý). Đây là điểm mấu chốt: trong nhiệm vụ 3 và 4, các mảng được xử lý đồng bộ (nghĩa là có một kết nối tương tự, rõ ràng giữa số lượng phần tử được xử lý trong các mảng khác nhau; trong nhiệm vụ 1 và 2, giữa số lượng phần tử được xử lý trong mỗi cặp mảng, không thể chỉ ra một kết nối không phụ thuộc vào các mảng cụ thể, mà có thể biểu thị bằng công thức chỉ kết nối các số này và một số CONSTANT. Do đó, chúng ta có thể nói rằng trong nhiệm vụ 1 và 2, các mảng là được xử lý đồng bộ,

Bây giờ hãy xem xét lời giải đã cho. Tất cả lời giải đều đúng nhưng không phải tất cả đều tốt như nhau. Nhiệm vụ 3 và 4 dường như không gây khó khăn, đơn điệu, đơn điệu và dễ hiểu. Vì trong nhiệm vụ 3 và 4, mảng được xử lý đồng bộ,

Chỉ cần có một chỉ mục để xử lý tất cả các mảng được xử lý đồng bộ là đủ.

Trong nhiệm vụ thứ 1 và thứ 2, các mảng được xử lý đồng bộ, do đó, nỗ lực bỏ qua một chỉ mục sẽ dẫn đến thất bại trước:

khi xử lý mảng không đồng bộ, mỗi mảng được xử lý không đồng bộ yêu cầu chỉ mục riêng (xem lời giải 1a, 16, 2a, 26).

Về nguyên tắc, tất nhiên có thể kết hợp với nhau, chẳng hạn như bộ đếm, bộ đếm cố định

sự tách biệt đáng kể giữa chỉ mục này với chỉ mục khác (xem lời giải 2c), nhưng điều này không đơn giản hóa chương trình mà chỉ vi phạm tính đồng nhất của quá trình xử lý mảng.

Chúng ta hãy xem xét kỹ hơn lời giải 1a và 16. lời giải này dựa trên 2 điểm khác biệt mang tính chiến lược trong cách tiếp cận ban đầu. lời giải đầu tiên có thể được nhận xét như sau: “Chúng tôi thực hiện m+n bước viết lại vào mảng C. Ở mỗi bước, nếu mảng A và B chưa hết thì chúng tôi viết lại phần tử tối thiểu hiện tại, nếu không thì - một phần tử từ mảng chưa hết.” lời giải thứ hai tương ứng với cách tiếp cận "Viết lại phần tử tối thiểu hiện tại cho đến khi hết một trong các mảng. Sau đó, chúng tôi thêm mảng còn lại." Cả hai cách tiếp cận nhìn chung đều giống nhau, mặc dù chương trình 26 sẽ chạy nhanh hơn.

Bây giờ hãy so sánh lời giải 2a và 26. Về mặt hình thức lời giải 26 là đúng, nhưng trong các tình huống tương tự, hai cách tiếp cận khác nhau về mặt kỹ thuật được sử dụng ở đây: i đánh số phần tử tự do đầu tiên của mảng và thay đổi sau khi viết lại và k số

⟦folio 51⟧

Nhiệm vụ 1

i:=1; j:=1; k:=1;
while (i<=n) AND (j<=m) do
begin if a[i]<b[j]
then begin
    c[k]:=a[i]; i:=i+1 end
else begin
    c[k]:=b[j]; j:=j+1 end;
k:=k+1
end;
if j<=m then for j:=j to m do
begin c[k]:=b[j];
k:=k+1 end
else for i:=i to n do
begin c[k]:=a[i];
k:=k+1 end;

Vấn đề 2

j:=1; k:=0;
for i:=1 to n do
begin
    if a[i]>0 then begin nol[j]:=a[i];
    j:=j+1 end;
    if a[i]<0 then begin k:=k+1;
    otrp[k]:=a[i] end
end;
nol[j]:=0; otrp[k+1]:=0;

Nhiệm vụ 4 (Sao chép)

j:=2; for i:=1 to n do
begin b[i]:=a[j]; j:=j+2 end;

phần tử dấu phẩy cuối cùng và được thay đổi trước khi viết lại. Trong những trường hợp phức tạp hơn, việc xử lý các tình huống tương tự khác nhau như vậy có thể dẫn đến sai sót và trong mọi trường hợp, điều đó không làm cho chương trình dễ hiểu hơn. Trong các vấn đề kỹ thuật, mọi lập trình viên đều phải có bất kỳ kỹ thuật kỹ thuật nào và không thay đổi chúng mà không có lý do chính đáng, khi đó sẽ có nhiều lực lượng sáng tạo hơn về các vấn đề chiến lược lời giải.

Trong chương trình 2a, những dòng tương tự được lặp lại hai lần. Điều này có thể tránh được bằng cách trình bày trong chương trình 2c. Mặc dù lời giải 2в chính thức là chính xác, nhưng không nên sử dụng "phù hợp" chẳng hạn như chuyển giao quyền kiểm soát trong điều kiện của toán tử giới tính và lý thuyết hiện đại hoàn toàn không khuyến nghị sử dụng toán tử chuyển tiếp. Lưu ý rằng thường có một câu lệnh if, viết các điều kiện điều tra dân số từ A, chẳng hạn như thế này:
if ((i<=n) AND (j<=m) AND
(a[j]<b[j])) OR (i>n) then
là không thể, vì ngay cả khi điều kiện i<=n không được đáp ứng, máy tính vẫn có thể kiểm tra việc đánh giá biểu thức a[i]<b[j] bằng cách thử xử lý phần tử không tồn tại a[n+1].

Kiểm soát công việc

4.1. Xóa khoảng trắng khỏi văn bản (mảng ký tự) và “nén” văn bản bằng chuột

Nhiệm vụ 1

i:=1; j:=1;
for k:=1 to m+n do
begin if i>n then goto 2;
if j>m then goto 1;
if a[i]<b[j]
then 1: begin c[k]:=a[i];
i:=i+1 end
else 2: begin c[k]:=b[j];
j:=j+1 end
end;

Vấn đề 2

j:=0; k:=0;
for i:=1 to n do
begin
    if a[i]>0 then begin nol[i-j]:=a[i];
    k:=k+1 end;
    if a[i]<0 then begin otrp[i-k]:=a[i];
    j:=j+1 end;
    if a[i]=0 then begin k:=k+1; j:=j+1 end
end;
nol[i-j]:=0; otrp[i-k]:=a[i];

các ký tự còn lại sang cạnh trái. Xử lý xác thực mà không cần thêm mảng.

4.2. (Lắp ráp theo trọng lượng). Cho 2 mảng có độ dài bằng nhau và một mảng trống. Các phần tử của mảng (mảng) thứ 2 có các giá trị true/false. Giá trị sai làm cho phần tử thứ i của mảng trở nên vô hình (xoa bóp) giá trị i-e của mảng ban đầu. Chuyển đổi các phần tử hiển thị (được đánh dấu bằng giá trị chân lý/khối lượng) của mảng đầu tiên thành mảng thứ ba, nhấn chúng vào cạnh trái và điền vào phần còn lại của mảng thứ ba bằng số 0. (Lưu ý rằng 2 mảng ở đây sẽ được xử lý đồng bộ và mảng thứ ba sẽ được xử lý không đồng bộ so với hai mảng đầu tiên.)

4.3. (Tháo rời theo trọng lượng). Cho một mảng, một mặt nạ và một mảng trống. Một số phần tử đầu tiên của mảng ban đầu được gửi đến các phần tử của mảng trống được bù về khối lượng bằng giá trị true / và các phần tử còn lại được điền bằng số 0.

4.4. (Độ phức tạp nâng cao.) Một mảng có thể chứa nhiều phần tử lớn. Trong một khung nhìn của mảng, hãy viết số lượng của tất cả các phần tử lớn của mảng ban đầu vào một mảng khác.

Chuẩn bị bài toán cho bài 5

1. In bảng giá trị của hàm y=x² với x thay đổi từ a thành b theo các bước của h.
2. Tìm giá trị trung bình số học của các phần tử mảng.
3. Cho một dãy số thực. Tìm một số trong đó bằng một số đã cho: lấy số của số này hoặc bằng 0 nếu không có số đó.

L. F. Shteriber
