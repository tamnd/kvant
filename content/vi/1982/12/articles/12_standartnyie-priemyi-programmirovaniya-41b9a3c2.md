---
id: 1982-12-standartnyie-priemyi-programmirovaniya-41b9a3c2
issue: kvant_1982_12
year: 1982
number: "12"
title: Kỹ thuật lập trình tiêu chuẩn
rubric: raznoe
rubric_sub: Разное
page_first: 44
page_last: 45
page_labels: 42-43
tag: EX2K
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 10a620e13896793035981d3488e37bb5b09fb674c78df1a1039ded1f31f12028
prompt_sha256: draft-1
translated_from: content/ru/1982/12/articles/12_standartnyie-priemyi-programmirovaniya-41b9a3c2.md
source_content_sha256: 55500374dcd5d3959cec50cd82ac1bd852ff3bd1efe9be921ac4823d8e3dfe16
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 42⟧

Kỹ thuật lập trình truyền thống.

Bài 3. Xử lý mảng tại chỗ

So sánh lời giải phần chuẩn bị bài toán của bạn cho bài học này (xem «Kvant» #11, Bài học 2) với những phần được đưa ra ở đây. Tùy chọn a) đúng lời giải, tùy chọn b) là các lỗi điển hình (chương trình không cho kết quả mong muốn), tùy chọn θ) sẽ hoạt động nhưng chúng không thể được coi là được chấp nhận.

Giống như bài học trước, chúng ta hãy xem các điều kiện bài toán có điểm gì chung.

Điểm chung chính là kết quả phải được lấy ở cùng nơi đặt dữ liệu nguồn. Bây giờ hãy nhìn vào các công thức tính toán trong các điều kiện bài toán (bạn đọc sẽ tha thứ cho việc sử dụng ký hiệu chương trình “gán” cùng với ký hiệu toán học “bằng”, ở đây là điều đương nhiên) và so sánh các công thức tính toán với nghiệm b); những lời giải này là bản dịch “theo nghĩa đen” của công thức trong ngôn ngữ lập trình. Chúng ta gặp phải vấn đề tương tự như ở các bài học trước: sự khác biệt trong quy tắc nói của ngôn ngữ toán học và ngôn ngữ lập trình.

Khi một nhà toán học viết một công thức chuyển đổi ma trận, tức là sự phản ánh của các phần tử của nó so với đường chéo (với mọi i, j a'ij := aji), rõ ràng anh ta muốn nói điều đó khi nghe lệnh “Halle-op!” tất cả các phần tử của ma trận sẽ nhảy lên cùng một lúc và sau đó tất cả sẽ rơi vào đúng vị trí, nhưng với các giá trị đã thay đổi. Nhưng máy tính không thể làm mọi thứ cùng một lúc*, quá trình xử lý dữ liệu diễn ra trong không gian và thời gian: đầu tiên một phần tử được xử lý, sau đó là phần tử khác, v.v. Và đến thời điểm quá trình xử lý phần tử thứ i bắt đầu, thì cần có cấu trúc của phần tử thứ k, phần tử thứ k

*) Một số máy tính hiện đại đã học được điều này, nhưng khả năng này cũng không được phản ánh bằng ngôn ngữ Pakel.

Lời giải chuẩn bị bài toán

a) Bài 1 (trung bình số học và trung bình hình học)
for i:=1 to n do
begin d:=a[i];
a[i] := (a[i] + b[i])/2;
b[i] := sqrt(d*b[i])
end;
Tùy chọn nhanh hơn:
for i:=1 to n do
begin ai:=a[i]; bi:=b[i];
a[i] := (ai+bi)/2;
b[i] := sqrt(ai*bi)
end;

b) Bài 2 (chia cho phần tử đường chéo)
for i:=1 to n do
begin d:=a[i,i];
for j:=1 to n do
a[i,j] := a[i,j]/d;
end;

Nhiệm vụ 3 (chuyển đổi)
for i:=1 to n-1 do
for j:=i+1 to n do
begin d:=a[i,j];
a[i,j] := a[j,i];
a[j,i] := d
end;

for i:=1 to n do
for j:=1 to n do
a[i,j] := a[j,i];
thứ hai lời giải:
for i:=1 to n do
for j:=1 to n do
begin d:=a[i,j];
a[i,j] := a[j,i];
a[j,i] := d
end;

⟦folio 43⟧

giá trị mới có thể đã thành công. Tương tự, chúng ta đã quen với việc dịch cụm từ toán học “cho tất cả $i$ với $i \in M$” sang ngôn ngữ lập trình bằng một vòng lặp có tham số $i$ chạy qua tập hợp $M$. Thông thường, bản dịch này là chính xác, nhưng vẫn có những trường hợp ngoại lệ, một trong số đó thường là việc xử lý các mảng tại chỗ. Nhìn vào lời giải $6$) bài toán 3 thứ hai và cố gắng hiểu chương trình sẽ làm gì và tại sao, do hoạt động của nó, ma trận sẽ không thay đổi.

Vì vậy, rõ ràng là nếu cần một trong các phần tử của mảng đang được xử lý tại chỗ để tính giá trị mới của phần tử khác, thì nó phải được lưu bằng cách nào đó. Cách đơn giản nhất lời giải - tạo một bản sao của mảng ban đầu và ghi kết quả vào một vị trí khác - thường không phù hợp trong thực tế. Khi lập trình bài toán có kích thước lớn (hoặc bài toán có ​​kích thước không lớn lắm nhưng trên máy tính có ít bộ nhớ), bạn có thể gặp phải tình huống mảng chiếm gần hết bộ nhớ và đơn giản là không còn chỗ cho bản sao. Đây là nhược điểm của các tùy chọn $b$): với kích thước mảng lớn, chương trình sẽ không có đủ bộ nhớ. Tuy nhiên, như các tùy chọn $a$ hiển thị), không cần phải sao chép mảng: toàn bộ, bạn có thể bỏ qua một phần tử bổ sung (trong chương trình, đây là biến có tên $d$) để lưu trữ giá trị cần thiết để tính toán một số giá trị mới.

Bây giờ chúng ta có thể rút ra kết luận cuối cùng.

$\theta)$
for $i:=1$ to $n$ do
begin $c[i]:=a[i]$;
$a[i]:=(a[i]+b[i])/2$;
$b[i]:=sqrt(c[i]*b[i])$
end;

for $i:=1$ to $n$ do
begin $d[i]:=a[i,i]$;
for $j:=1$ to $n$ do
$a[i,j]:=a[i,j]/d[i]$;
end;

for $i:=1$ to $n$ do
for $j:=1$ to $n$ do
$c[j,i]:=a[i,j]$;
for $i:=1$ to $n$ do
for $j:=1$ to $n$ do
$a[i,j]:=c[i,j]$;

1. Khi xử lý mảng tại chỗ cần có biện pháp lưu lại giá trị của các phần tử cần thiết cho các phép tính tiếp theo. Theo quy định, MỘT yếu tố phụ trợ là đủ cho việc này.

Phương án cuối cùng, khi một phần tử rõ ràng là không đủ, bạn có thể lấy một mảng có ít chiều hơn (ví dụ: mảng một chiều cùng với ma trận). Tất nhiên, có những trường hợp mảng không thể được xử lý tại chỗ và sau đó chúng tôi kết thúc bằng một bản sao.

2. Nếu các phần tử được xử lý không theo thứ tự trong mảng thì các vòng lặp trên các phần tử mảng phải được tổ chức theo một cách đặc biệt.

Ví dụ: trong bài toán 3 cặp phần tử đối xứng theo đường chéo được xử lý đồng thời, do đó, cách tổ chức vòng lặp khác với cách dịch “theo nghĩa đen” của một công thức toán học.

Bây giờ chúng ta hãy xem tại sao các chương trình mới làm quen không thấy lỗi trong các tùy chọn - đây là một biến có tên $d$) để lưu trữ giá trị cần thiết để tính một số giá trị mới.

Ví dụ: hãy kiểm tra tùy chọn $b$) bài toán 1. Để thực hiện việc này, hãy lấy các mảng nhỏ, nói $a=(2,3,4)$, $b=(5,6,7)$ và cuộn qua chương trình $n=3$, $i=1$, $a[1]=(2+5)/2=3,5$, $b[1]=\sqrt{2\cdot5}=\sqrt{10}$, v.v. Đây là một lỗi rất điển hình: chúng ta đã làm những gì chúng ta muốn từ máy tính và không phải những gì máy tính thực sự sẽ làm!

Việc cuộn chính xác được thực hiện như sau: a) viết ra một bảng gồm tất cả các mã định danh và các giá trị của chúng hợp lệ ở định dạng đang được kiểm tra, b) ở mỗi bước, giá trị cũ bị gạch bỏ và thay thế bằng giá trị mới.

Hãy xem qua ví dụ tương tự:

$$\begin{array}{c}
n \\
3 \\
a_1=(a_1+b_1)/2=3.5 \\
1 \\
3.5 \\
b_1=\sqrt{a_1b_1}=\sqrt{(3.5)\times5}=\sqrt{17.5} \\
(2,3,4) \\
b(5,6,7)
\end{array}$$

Lỗi đã xuất hiện ở bước đầu tiên.

Và cuối cùng, câu hỏi cuối cùng: chương trình có giảm tốc độ khi
