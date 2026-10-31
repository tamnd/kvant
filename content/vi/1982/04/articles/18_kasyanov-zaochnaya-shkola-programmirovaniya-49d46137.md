---
id: 1982-4-kasyanov-zaochnaya-shkola-programmirovaniya-49d46137
issue: kvant_1982_4
year: 1982
number: "4"
title: Trường lập trình tương ứng
authors:
  - Касьянов В.
rubric: raznoe
rubric_sub: Разное
page_first: 52
page_last: 53
page_labels: 50-51
tag: OPP9
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 90b42609ef3db8396e222a5b9e142331593657ef041fb7d10465673bfe8c1c1a
prompt_sha256: draft-1
translated_from: content/ru/1982/04/articles/18_kasyanov-zaochnaya-shkola-programmirovaniya-49d46137.md
source_content_sha256: 5e77b68f1631a4c8242352f7d7a6972db8c9ecce8922d36236a5a013400956c8
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 50⟧

Trường lập trình tương ứng
Bài 20: Tham số thủ tục và hàm

Trong Pascal, cả thủ tục và hàm đều có thể có danh sách các tham số. Mỗi tham số thủ tục*) được biểu diễn trong phần mô tả thủ tục bằng một tên nhất định, được gọi là tham số hình thức. Tham số hình thức đóng vai trò là một chỉ định cho phép chúng ta mô tả chuỗi hành động mà chúng ta muốn áp dụng trong các lần thực hiện thủ tục khác nhau với các đại lượng thực tế khác nhau. Các giá trị này được chỉ định trong câu lệnh gọi thủ tục hoặc trong xử lý hàm dưới dạng danh sách các tham số thực tế, độ dài của nó trùng với độ dài của danh sách các tham số hình thức. Sự tương ứng vị trí đơn giản được thiết lập giữa các tham số hình thức và thực tế: tham số thực tế đầu tiên tương ứng với tham số hình thức đầu tiên, tham số thứ hai với tham số thứ hai, v.v. Mỗi tham số định dạng của một thủ tục chỉ có ý nghĩa trong phạm vi thủ tục này. Khi bắt đầu thủ tục, tham số hình thức được liên kết với giá trị được chỉ định bởi tham số thực tế tương ứng và tồn tại bên ngoài thủ tục này.

Pascal có bốn loại tham số: tham số giá trị, tham số biến, tham số thủ tục và tham số hàm. Loại tham số này hoặc tham số khác của thủ tục được chỉ định trong tiêu đề của nó (xem bài 16).

*) Mọi điều được nói ở đây và bên dưới về tham số thủ tục đều được chuyển hoàn toàn sang tham số hàm.

Thông số-giá trị
Các thông số giá trị được mô tả bằng sơ đồ:

Tham số giá trị của một thủ tục là biến cục bộ của nó (đối với tên cục bộ và tên chung trong Rapier, xem Bài 7). Một tham số hình thức đại diện cho biến này trong phần mô tả thủ tục. Tham số thực tế trong trường hợp này phải là biểu thức cùng loại với biến được biểu thị bằng tham số định dạng tương ứng. Khi thủ tục được gọi, biểu thức này được đánh giá và giá trị kết quả được gán cho biến làm giá trị ban đầu. Sau này, khi thủ tục được thực thi, biến này không khác gì các biến cục bộ khác của thủ tục này.

Ước số chung nhất của hai số nguyên dương có thể được thực hiện bằng hàm sau:

```matlab
function nod(x, y:integer):integer;
{0≤y≤X}
begin if y=0
then nod:=x
else nod:=nod(x,x mod y)
end;
```

Nhiệm vụ 20.1. Mô tả chức năng sau đây có sẵn:

```matlab
function a(x,y:integer):integer;
{x≥0,y≥0}
begin if x=0
then a:=y+1
else if y=0
then a:=a(x-1,1)
else a:=a(x-1,a(x,y-1))
end;
```

Xác định số lượng phiên bản tối đa của tham số x tồn tại đồng thời khi thực hiện truy cập a (2,2).

Thông số biến

Sơ đồ mô tả các tham số biến trông như sau:

⟦folio 51⟧

Trong trường hợp này, tham số thực tế phải là một biến thuộc loại đã chỉ định và tham số hình thức đóng vai trò là chỉ định của biến đó trong toàn bộ thời gian thực hiện quy trình nhất định. Nếu tham số thực tế chứa các chỉ mục, chúng sẽ được tính tại thời điểm thủ tục được gọi.

Tham số biến là bắt buộc trong mọi trường hợp tham số được sử dụng để biểu thị kết quả của một thủ tục hoặc hàm.

Các chương trình sắp xếp được thảo luận trong số thứ hai «Kvant» đã sử dụng loại tham số này.

Cho có những mô tả sau:

```python
var k:integer;
b:array [1...100]of real;
procedure max(var i:integer);
{1≤i<100}
var j:integer;
begin
for j:=i+1 to 100 do
if b[i]<b[j]then i:=j
end;
```

Sau đó, sau khi thực thi các toán tử `k:=20; max(k)`, biến `k` sẽ được gán chỉ mục của phần tử lớn nhất của `b[20], b[21], ..., b[100]`.

Nhiệm vụ 20.2. Có thể sử dụng thủ tục

```python
procedure заменa(var x,y:integer);
var z:integer;
begin
z:=x;
x:=y;
y:=z
end
```

để trao đổi giá trị cho hai biến kiểu số nguyên bất kỳ? Ví dụ: giá trị của các biến `k` và `a[20]` có được đặt sau lệnh gọi thay thế (`k, a [k+1]`) nếu giá trị thực thi của nó là 19 không?

Nhiệm vụ 20.3. Hãy để có những mô tả

```python
type табличца=array[1..2,1..2] of integer;
procedure умножение(var x,y,z:tabличца);
begin
z[1,1]:=x[1,1]*y[1,1]+x[1,2]*y[2,1];
z[1,2]:=x[1,1]*y[1,2]+x[1,2]*y[2,2];
z[2,1]:=x[2,1]*y[1,1]+x[2,2]*y[2,1];
z[2,2]:=x[2,1]*y[1,2]+x[2,2]*y[2,2]
end;
```

và ba bảng được đưa ra

```python
a = (1 1) , b = (2 2) , c = (3 3) .
```

Xác định chế độ xem bảng `a`, `b` và `c` sau mỗi mục trên:

`умножение (a, b, c)`, `умножение (a, b, a)`, `умножение (a, b, b)`. Điều gì sẽ xảy ra trong cùng các lệnh gọi này nếu tham số `x` và `y` được tạo thành giá trị tham số? Điều gì xảy ra nếu z cũng trở thành một tham số giá trị?

Tham số thủ tục và tham số chức năng

Sơ đồ mô tả các tham số thủ tục và tham số hàm có dạng như sau:

```python
function function(экспilon, a,b:real;
function f:real):real;
{f(x) — вещественная функция с одним параметром типа real. Функция непрерывна в интервале a≤x≤b и имеет в точках а и b значения разных значений}
var c:real; d:boolean;
begin
if f(a)>0 then
begin c:=a; a:=b; c:=b end;
d:=true;
```
