---
id: 1982-2-pervin-zaochnaya-shkola-programmirovaniya-0012c6ff
issue: kvant_1982_2
year: 1982
number: "2"
title: Trường lập trình tương ứng
authors:
  - Первин Ю. А.
rubric: raznoe
rubric_sub: Разное
page_first: 50
page_last: 55
page_labels: 48-53
tag: L620
lang: vi
source: kvant_digital
extraction: vision
content_sha256: d68116f6e92c68ddfefc2da5ee9ba3103d75c5d0c6d963443c5e364f9ca55762
prompt_sha256: draft-1
translated_from: content/ru/1982/02/articles/19_pervin-zaochnaya-shkola-programmirovaniya-0012c6ff.md
source_content_sha256: 72eaa9ecc1670323d935947ee68d61bd2de8497fd8753bd829de453f07ff0da1
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 48⟧

Trường lập trình tương ứng
Bài học 18: Tập tin

Một tập tin là gì?
Tệp là một tập hợp nhỏ các phần tử cùng loại, số lượng phần tử không được xác định trước.

Loại tệp được mô tả bằng sơ đồ cú pháp sau:

```
file of min
```

type là loại chung của các thành phần tệp. Chúng tôi sẽ gọi nó là cơ bản. Có một loại tệp tiêu chuẩn (nghĩa là tồn tại cho bất kỳ chương trình nào và không phụ thuộc vào mô tả trong đó) được gọi là văn bản. Loại cơ sở của nó là char. Các tập tin thuộc loại văn bản được gọi là tập tin văn bản.

Các phần tử của một tệp được coi là được sắp xếp tuần tự, nghĩa là giống như các phần tử của vectơ. Một tệp khác với một vectơ, thứ nhất, ở chỗ kích thước của nó có thể thay đổi, và thứ hai, ở chỗ cách truy cập các phần tử của nó hoàn toàn khác: không thể truy cập vào một phần tử tùy ý của tệp; các phần tử của nó chỉ được xem trong một hàng, từ đầu đến cuối, mỗi lần chỉ có một phần tử. Mỗi tệp f có một biến liên quan biểu thị f↑; loại của nó giống với loại tệp cơ sở. Nó được gọi là bộ đệm hoặc biến bộ đệm của tập tin này. Bộ đệm chỉ có thể chứa một phần tử tệp;

Giá trị của phần tử này đóng vai trò là giá trị bộ đệm. Bộ đệm giống như một cửa sổ mà qua đó bạn có thể xem tệp, chọn từng phần tử một.

Nếu tệp được xem đến cuối (hoặc nếu nó hoàn toàn trống), thì chúng tôi sẽ coi như nó đã hoàn thành. Nếu tệp đã hoàn tất thì giá trị của bộ đệm của nó sẽ không được xác định.

Thủ tục xử lý tập tin
Bạn có thể kiểm tra xem tập tin f đã hoàn thành chưa bằng cách gọi hàm logic tiêu chuẩn

eof(f)
Nó tạo ra giá trị đúng nếu f kết thúc và sai nếu không*).

Giả sử chúng ta cần xem tệp f. Để làm điều này, trước tiên bạn phải gọi thủ tục tiêu chuẩn

reset(f)
(“đặt lại” có nghĩa là “trở lại”). Kết quả của việc thực thi nó là giá trị của bộ đệm f↑ sẽ trở thành phần tử đầu tiên của tệp (nếu tệp không trống).

Bạn có thể di chuyển từ phần tử tệp này sang phần tử tệp tiếp theo bằng cách sử dụng lệnh gọi thủ tục tiêu chuẩn

get(f)
(“get” có nghĩa là “lấy”). Sau khi thực thi, f↑ sẽ chứa giá trị của phần tử tiếp theo này, nếu có. (Nếu không có phần tử tiếp theo, tệp sẽ trở nên hoàn chỉnh.) Thủ tục get không thể áp dụng cho tệp đã được hoàn thành.

Hãy xem một ví dụ. Đặt f1 và f2 là các tệp có kiểu cơ sở real, arovno và b là các biến kiểu boolean. Biến bằng cần được đặt thành true nếu nội dung của f1 và f2 giống nhau (nghĩa là các tệp này có cùng độ dài, có thể bằng 0 và các phần tử tương ứng của chúng bằng nhau theo cặp) và sai nếu không.

*) eof là viết tắt của từ tiếng Anh end of file.

⟦folio 49⟧

bài toán này có thể được thực hiện như thế này:

```python
reset(f1); reset(f2); b:=true;
while b AND NOT eof(f1)
    AND NOT eof(f2)
do begin b:=f1↑=f2↑;
    get(f1); get(f2)
end;
if b then равно:=eof(f1)ANDeof(f2)
else равно:=false;
```

Nếu cả hai tệp đều trống thì phần thân của vòng lặp sẽ không được thực thi dù chỉ một lần và sẽ nhận được cùng một giá trị `true`. Trong khi các phần tử tiếp theo của tệp khớp với nhau theo cặp, `b` nhận giá trị `true` trong nội dung vòng lặp và toán tử vòng lặp tiếp tục hoạt động. Vòng lặp sẽ dừng nếu các phần tử tiếp theo không khớp hoặc nếu một trong các tệp được hoàn thành. Trong trường hợp đầu tiên, `b` có giá trị `false` khi thoát khỏi vòng lặp và câu lệnh cuối cùng sẽ gán giá trị này cho biến `равно`. Nếu khi thoát khỏi vòng lặp, `b` có giá trị `true` thì điều này có nghĩa là một trong các tệp sẽ trùng với đoạn đầu tiên của tệp khác. Trong trường hợp này, câu lệnh cuối cùng sẽ kiểm tra xem tệp thứ hai có kết thúc cùng lúc hay không. Nếu có, thì bằng sẽ nhận giá trị `true` và nếu tệp kia chưa hoàn thành thì sai.

Bây giờ hãy biết rằng tệp `f1` chứa ít nhất 10 phần tử và 10 phần tử đầu tiên trong số chúng cần được chuyển đổi thành một mảng `m`, loại của mảng này là `array [1..10]` của `real`. Điều này có thể được thực hiện như sau (i là một biến có kiểu `integer`):

```python
reset(f1);
for i:=1 to 10 do
begin m[i]:=f1↑;get(f1) end;
```

Trình tự các toán tử `v:=f↑; get(f)` (1) trong đó `v` là một biến và `f` là một tệp khá phổ biến. Do đó, trong Pascal có một quy trình chuẩn `read` sao cho việc gọi `read(f,v)` tương đương với các toán tử nhạt (1). Bây giờ ví dụ của chúng ta có thể được viết lại ngắn hơn:

```python
reset(f1);
for i:=1 to 10 do read(f1, m[i]):
```

Như vậy, chúng ta đã học được cách đọc từ một tập tin. Bây giờ chúng ta hãy xem làm thế nào để điền vào nó. Có một quy trình chuẩn `rewrite` (ghi đè) sao cho sau khi gọi `rewrite(f)`, tệp `f` trở nên trống và sẵn sàng để điền. Để thực thi một tệp có giá trị của một biểu thức nhất định `E`, bạn cần thực hiện phép gán `f↑:=E`, sau đó gọi quy trình chuẩn `put(f)` (“put” có nghĩa là “put”). Lệnh gọi này sẽ nối giá trị `f↑;` vào cuối tệp, do đó loại bỏ một phần tử. Quy trình `put` chỉ có thể được sử dụng nếu tệp đã hoàn tất và sau khi gọi nó, nó vẫn tiếp tục được hoàn thành: bạn không thể ghi các phần tử mới vào giữa tệp. Cặp toán tử

```python
f↑:=E; put(f)
равносильна оператору
write(f, E)
```

trong đó `write` là quy trình chuẩn.

Ví dụ: bạn có thể điền vào tệp `fi`, có loại cơ sở là `integer`, với các số nguyên từ 1 đến 100:

```python
rewrite(fi);
for i:=1 to 100 do write(fi, i)
```

Nhiệm vụ 18.1. Từ hai tệp văn bản `x` và `y`, hãy tạo một tệp `z` sao cho trước tiên nó chứa tất cả các thành phần của tệp `x`, sau đó là `y`.

Điều đặc biệt đặc biệt ở các tệp văn bản là bằng cách sử dụng quy trình `write`, bạn có thể điền vào chúng các giá trị không chỉ thuộc loại cơ sở `char` mà còn cả các loại đơn giản khác và bằng cách sử dụng quy trình `read`, bạn có thể gửi chúng đến các biến thuộc bất kỳ loại đơn giản nào. Ví dụ: nếu tệp `ft` là tệp văn bản thì `write(ft, 51)` sẽ tự động chuyển số 51 thành chuỗi ký tự “5” và “1” rồi ghi chúng vào tệp `ft`. Mặt khác, nếu biết rằng các phần tử tiếp theo trong tệp `ft` là các số, có thể đứng trước dấu cách, thì chúng ta có thể sử dụng lệnh gọi `read(ft, i)`, trong đó `i` là một biến thuộc loại `integer`. Lệnh gọi này, bỏ qua tất cả các khoảng trắng trước chữ số đầu tiên, sẽ lấy tất cả các chữ số theo thứ tự cho đến khi tìm thấy khoảng trắng tiếp theo, chuyển chúng thành một số (ví dụ: dãy các chữ số “5” và “1” thành số 51) và gán số này cho biến `i`.

Nhiệm vụ 18.2. Được biết, file văn bản `f` chứa các số thực cách nhau bởi dấu cách. Sự kết thúc của chuỗi này được biểu thị bằng số 0.

⟦folio 50⟧

sau đó in tổng các số trong dãy này.

Tệp và I/O

Dễ dàng nhận thấy rằng làm việc với các tập tin rất giống với cơ chế I/O. Bây giờ chúng tôi sẽ chỉ ra mối liên hệ giữa chúng là gì.

Gọi một thủ tục
write (x)
với tham số kiểu đơn giản, giá trị x được xuất ra thiết bị in (xem bài 15). Giả định rằng đầu ra tệp văn bản tiêu chuẩn được liên kết với thiết bị in. Việc in ấn không gì khác hơn là bổ sung tập tin này và viết (x) là ký hiệu viết tắt của

write (output, x)
Thiết bị được coi là được liên kết với đầu vào tệp văn bản tiêu chuẩn và
read (x)
Có chữ viết tắt cho
read (input, x)
Không thể bổ sung tệp đầu vào và không thể áp dụng quy trình đặt lại cho tệp đó. (Quy trình này dường như đã được kiểm tra khi bắt đầu thực hiện chương trình). Theo cách tương tự, quy trình đọc và ghi lại không được áp dụng cho tệp đầu ra. Hai tệp này không cần phải mô tả trong chương trình (đó là lý do tại sao chúng là tiêu chuẩn), nhưng, như bạn đã biết từ Bài 15, chúng phải được liệt kê trong tiêu đề chương trình.

Nếu bài toán yêu cầu lưu trữ bất kỳ thông tin nào vào bộ nhớ ngoài thì cần có các tệp bên ngoài bổ sung cho thông tin đó. Chúng phải được mô tả cùng với tất cả các biến chương trình khác và được liệt kê trong tiêu đề cùng với đầu vào và đầu ra. Nếu không có tên tệp trong tiêu đề thì tệp này chỉ dùng để trao đổi thông tin trong chương trình.

Nhiệm vụ 18.3. Một số văn bản được hiển thị trên thiết bị. Bạn cần đặt nó trong tệp văn bản f, đặt dấu “/” sau mỗi ký tự “*”.

Ví dụ về sử dụng tập tin bên ngoài

Trong bài học trước, chúng ta đã xem xét các ví dụ liên quan đến việc mô tả và xử lý thông tin về các quốc gia khác nhau trên thế giới. Những ví dụ này là một minh họa đơn giản về dịch vụ bài toán xử lý khối lượng thông tin rất lớn. Rõ ràng là loại thông tin này không xuất hiện khi bắt đầu thực hiện chương trình và không biến mất khi kết thúc chương trình. Ngược lại, nó phải được lưu trữ trong một thời gian rất dài, có thể trong nhiều năm: nó có thể thay đổi theo thời gian và dữ liệu cần thiết có thể được thay đổi khỏi nó bất cứ lúc nào. Thông tin cũng có thể được lưu trữ trong bộ nhớ ngoài của máy tính (trên đĩa và băng), việc đọc và sửa thông tin được thực hiện bởi các chương trình đặc biệt được thực thi khi có nhu cầu.

Mỗi chương trình như vậy coi thông tin là nội dung của một số tệp bên ngoài. Trong trường hợp của chúng tôi, nó là một tệp có tên arxiv. Các phần tử của tệp này là các bản ghi thuộc loại quốc gia. Một chương trình xử lý tùy chỉnh phải hoạt động với tệp. Tiêu đề của nó trông giống như

xử lý chương trình (đầu vào, đầu ra, arxiv);
phần mô tả biến sẽ chứa mô tả
arxiv: tập tin của
quốc gia;
Trong bài học trước, mỗi bản ghi liên quan đến một trạng thái cụ thể là giá trị của một biến riêng biệt, tên của biến đó trùng với tên của trạng thái tương ứng. Rõ ràng là trong thực tế, thật bất tiện khi mô tả và có một trăm rưỡi biến trong một chương trình. Vì vậy, bây giờ chúng ta sẽ bỏ các biến Australia, ..., Japan. Tên quốc gia sẽ được lưu trong hồ sơ; nó chứa một trường khác có kiểu mảng [1..60] char (và giả sử rằng sáu mươi chữ cái và dấu cách là đủ cho tên của bất kỳ quốc gia nào trên thế giới).

Mô tả về loại quốc gia bây giờ sẽ như thế này:
quốc gia = kỷ lục
tên: mảng [1..60] của char;

⟦folio 51⟧

diện tích, dân số: thực tế;
thiết bị: boolean;
giới thiệu: ngày tháng;
giáo dục: thử thách chấm dứt;
Giả sử chúng ta cần tìm ra quốc gia nào có nhiều cộng đồng nhất. Hãy để chúng tôi mô tả các biến cho điều này
tên: mảng [1..60] của char;
diện tích: thực tế; tôi: số nguyên;
và thực hiện các câu lệnh sau:
diện tích:=0,0; đặt lại (lưu trữ);
trong khi KHÔNG eof (lưu trữ) làm
bắt đầu nếu arxiv↑.area>khu vực
then begin
diện tích:=arxiv↑.khu vực
tiêu đề:=arxiv↑.title
end;
lấy (lưu trữ)
end;
writeln(tên, khu vực);
Nhiệm vụ 18.4. Bắt đầu tên của tất cả các quốc gia có dân số lớn hơn 10 triệu.

Phụ lục Bài 18 A. Rahr
Sắp xếp theo phím văn bản. Sáp nhập

Sắp xếp là hành động tổ chức tập hợp dữ liệu theo giá trị của một đặc tính nào đó. Do đó, các phần tử của tập hợp có thứ tự, ở một mức độ nhất định, là các đối tượng phức tạp, đa thành phần—thuộc các kiểu cấu trúc này; Theo quy định, đối tượng địa lý chỉ là một trong các thành phần của các phần tử được sắp xếp. Trong tài liệu chung về các phương pháp sắp xếp, những đặc điểm đó, theo các giá trị mà tập hợp thứ tự của quần thể được sắp xếp được ước tính, thường được gọi là khóa. Việc sắp xếp trở nên khả thi khi mối quan hệ thứ tự được thiết lập trên một tập hợp các giá trị chính.

Nibaulier tuyên bố rằng các đối tượng được áp dụng sắp xếp là các tập hợp dữ liệu cùng loại. Có hai loại bộ sưu tập như vậy: mảng - bộ sưu tập dữ liệu với số lượng phần tử và tệp cố định đã biết, nói chung, kích thước của chúng không xác định và có thể thay đổi trong quá trình thực hiện chương trình. Theo đó, việc sắp xếp các mảng theo quy luật được thực hiện nội bộ bằng cách sắp xếp, chỉ áp dụng cho dữ liệu nằm trong RAM của máy tính và đối với các tệp, thường cần sử dụng cách sắp xếp bên ngoài, có thể hoạt động với dữ liệu nằm trên các thiết bị lưu trữ bên ngoài - băng từ, đĩa, thiết bị ngoại vi.

Vấn đề tổ chức thông tin luôn xuất hiện. Trong bảng lương, các thành phần dòng của nó có thể được sắp xếp theo thứ tự tăng dần của các số hạng trong bảng. Ở đây các khóa là số bảng, quan hệ thứ tự là trả về các số tự nhiên. Giao thức cuối cùng thực hiện quy trình kiểm soát tần số hợp lệ dựa trên kết quả được hiển thị cho người tham gia cuộc thi. Ở đây các khóa là số thực*) của kết quả.

Danh sách học sinh của một lớp cũng được sắp xếp. Ở đây, các phím họ là văn bản. Thông thường, văn bản được sắp xếp giống như các từ trong từ điển - theo thứ tự bảng chữ cái, theo thứ tự gọi là từ điển: nếu thứ tự các chữ cái trong bảng chữ cái là cố định thì trong hai giá trị khóa k1 và k2 tổng được coi là giá trị mà k1[1]→k2[1] theo thứ tự bảng chữ cái (chữ cái đầu tiên của văn bản đầu tiên đại diện cho chữ cái đầu tiên của văn bản thứ hai) và nếu k1[1] = k2[1] bằng nhau thì với cái nào k1[2]→k2[2], v.v. Vì vậy, 'lớp' → 'con voi', như trong từ điển.

Do đó, thứ tự tương đối của hai chữ cái hoặc hai từ có thể được thiết lập và thậm chí được biểu thị: ký hiệu “→” có nghĩa là “đi trước”. Tuy nhiên, vì mục đích thực tế - xác định và thiết lập thứ tự từ điển của các văn bản trong một chương trình được viết dưới dạng ví dụ trong Pascal - sẽ hữu ích hơn nếu không xử lý mối quan hệ “→”,

*) Điều quan trọng cần nhớ là số thực được định nghĩa khác nhau trong lập trình và trong toán học. Trong máy, chúng ta sẽ chỉ biểu diễn các số có số chữ số giới hạn. Do đó, các số “thực”, theo cách hiểu của các lập trình viên, về cơ bản là các số hữu tỉ.

⟦folio 52⟧

không thể triển khai trực tiếp cho các văn bản trong Pascal, nhưng với mối quan hệ quen thuộc “<”, được biết đến nhiều từ các phép toán trên số. Vì mục đích này, một hằng số `alфавит` thuộc loại `array [1..64]` của `char` được lưu trữ trong bộ nhớ của máy. Ý nghĩa của nó là 'abv...i+ -...!'

Sử dụng hằng số này, mỗi chữ cái trong bảng chữ cái (và nói chung hơn là mỗi ký hiệu) được liên kết với số 1, chữ a với số 2,..., chữ i với số 34. Ký tự “cao nhất” là một dấu chấm than! — được ánh xạ tới số 64. Lưu ý rằng khoảng trắng đại diện cho tất cả các ký tự trong bảng chữ cái.

Bây giờ việc so sánh 2 ký tự rất dễ thực hiện, hãy so sánh các số tương ứng với chúng, nếu bạn có hàm số như vậy:

```javascript
function число(x:char):integer;
var i:integer;
begin
i:=1;
while i<=64 do
if x=alфавит[i]
then begin число:=i;
i:=65 end;
else i:=i+1
end
```

chẳng hạn, với sự trợ giúp của nó, điều kiện được đề cập `κ1/2→κ2/2` có thể được rút gọn thành điều kiện `число(κ1/2)<число(κ2/2)`

Hàm `число` chỉ cần thiết vì thứ tự bảng chữ cái (1) hóa ra lại rất cần thiết đối với chúng ta. Nếu chúng ta hài lòng với bảng chữ cái Pascal tiêu chuẩn, đầu tiên liệt kê các chữ cái từ `a` đến `z`, sau đó là các chữ cái tiếng Nga không khớp với chúng về kiểu dáng, sau đó là số và các ký hiệu khác, sau đó với mục đích chuyển đổi các chữ cái `x` thành một số bằng số của chữ cái này trong bảng chữ cái tiêu chuẩn, chúng ta có thể sử dụng hàm Pascal tiêu chuẩn `ord(x)`.

Sử dụng các quan hệ có dạng (2), người ta có thể xác định thứ tự tương đối của hai văn bản bất kỳ. Ví dụ: đối với 'lớp' và 'con voi', bạn có thể thực hiện một loạt kiểm tra cho chữ cái đầu tiên `число('c')=число('c')` cho chữ cái thứ hai `число('l')=число('l')` cho chữ cái thứ ba `число('o')=число('o') но для четверых буквы имеет место `number('e')<number('n')`

từ đó nó đi theo 'lớp' → 'con voi' đó.

Một loạt kiểm tra như vậy có thể được thực hiện đối với hai văn bản bất kỳ bằng cách sử dụng hàm `сравнение` (x1, x2). Hàm này tạo ra giá trị boolean `true` nếu `x1→x2` hoặc nếu văn bản `x1` và `x2` giống nhau. Nếu `x2→x1` thì giá trị do hàm này tạo ra là `false`. Sau đó, nếu trong một chương trình, điều quan trọng là phải thiết lập tính đúng đắn của điều kiện `x1→x2`, thì bạn có thể sử dụng các điều kiện `сравнения` (x1, x2) = `true` được triển khai trong Pascal. Nếu gõ `type` mảng =
`packed array [1...20] of char`
thì hàm `сравнение` được mô tả như sau:

```javascript
function сравнение(x1,x2: массив):boolean;
var номер:integer;
begin
номер:=0
while номер<=20 do
begin
номер:=номер+1;
if число(x1|номер|)<>
    число(x2|номер|)
then сравнение:=true
else сравнение:=false
номер:=21
end
else if номер>20
then сравнение:=true
end
end;
```

Như được mô tả ở đây, hàm `сравнение` hoạt động trên mảng từ gồm 20 ký tự `x1` và `x2`. Độ dài từ được chọn để cho phép sử dụng chức năng này để so sánh họ: đây là một trong những từ khóa được sử dụng phổ biến nhất trong nhiều ứng dụng sắp xếp. Giới hạn 20 lít luôn có thể được thay thế, nếu muốn, bằng giới hạn mạnh hơn hoặc ngược lại, yếu hơn. Tất nhiên, các thủ tục so sánh dài sẽ gửi từng từ trong mảng so sánh đến một mảng gồm 20 khoảng trắng. Đó là kết quả của quy trình này, rõ ràng là sẽ không khó để người đọc mô tả và đóng vai trò là tham số thực tế khi truy cập hàm `сравнение` (x1, x2). Mặt khác, quy trình sơ bộ như vậy sẽ không cần thiết nếu người dùng chương trình làm việc với hàm `сравнение` ghi các giá trị khóa sao cho chúng chiếm 20 ký tự, trong đó các ký tự sau chủ yếu là khoảng trắng ngẫu nhiên. Và thêm một lưu ý nữa về phần mô tả hàm `сравнение`: mảng tham số của hàm này thuộc loại `packed array` (mảng đóng gói), không phải loại `array`. Loại `packed array` được sử dụng cho mảng, khi trong một từ, bạn có thể đặt không phải một phần tử của mảng mà nhiều phần tử, tức là đóng gói chúng. Loại này

⟦folio 53⟧

thường được sử dụng khi mô tả mảng văn bản gồm các chữ cái.

Vì vậy, cũng có thể sắp xếp trong trường hợp các phím lấy giá trị văn bản.

Khi chọn phương pháp sắp xếp, điều quan trọng là sử dụng mọi kiến ​​thức bạn có về tổ chức hoặc thứ tự của các tập hợp dữ liệu cần sắp xếp. Về vấn đề này, đặc trưng nhất là phương pháp quay. Nó được sử dụng để sắp xếp một tập hợp các phần tử thu được bằng cách kết hợp hai hoặc nhiều bộ sưu tập đã được sắp xếp theo cùng một khóa. Những tình huống như vậy xảy ra thường xuyên. Ví dụ, từ danh sách tất cả các lớp 10 của các trường được sắp xếp “theo bảng chữ cái” (nghĩa là theo thứ tự từ điển), cần lập danh sách chung các học sinh tốt nghiệp nhưng vẫn giữ nguyên thứ tự từ điển. Hãy xem xét một chương trình quay hai tệp danh sách như vậy f1 và f2

Hình 1.

(Hình 1). Do đó chúng ta đang nói về việc sắp xếp bên ngoài. Tuy nhiên, phương pháp quay hầu như chỉ được sử dụng trong việc sắp xếp bên ngoài. Người đọc có thể hiểu phương pháp quay, chạy chương trình quay để sắp xếp bên trong như một điều khiển độc lập - để sắp xếp các mảng chứ không phải các tệp.

Phương thức này yêu cầu dung lượng trống trong bộ nhớ cho một tệp f khác, trong đó kết quả sẽ được đặt. Bạn có thể di chuyển qua các tệp f1 và f2, đọc các phần tử của chúng một cách tuần tự. Đồng thời, ở mỗi bước, giá trị của các khóa trong phần tử đọc cuối cùng của tệp f1 và f2 (trong biến bộ đệm của chúng) được so sánh và theo kết quả so sánh, phần tử trẻ nhất sẽ ở cuối tệp kết quả. Hãy chú ý đến một chi tiết quan trọng: bằng cách di chuyển qua các tệp f1 và f2, bạn có thể thêm vào cuối một trong các tệp khi tệp kia vẫn chưa hoàn thành. Trong trường hợp này, bạn nên viết lại trọng lượng của "đuôi" của tệp hoàn toàn chưa đọc mà không cần so sánh không cần thiết.

Thủ tục kiểm tra phần cuối của file f1 trước khi chuyển sang đọc bản ghi tiếp theo được gọi là record1. Nếu cần, nó sẽ viết lại "đuôi" của tập tin mà không cần so sánh thêm. (Quy trình tương tự đối với tệp f2 là hoàn toàn đối xứng - mô tả quy trình write2 có được bằng cách thay thế tất cả các thủ tục có quy trình write1 bằng một bằng hai và ngược lại.)

hồ sơ thủ tục1;
begin
get(f1);
if eof(f1)
then
begin
while NOT(eof(f2)) do
bắt đầu viết(f,ф2↑); kết thúc (f2)
kết thúc:=đúng
end
end;

Để giải phóng chương trình khỏi các điều kiện không chính tắc (và nhỏ), người ta giả định rằng trong các phần tử của cả hai tệp đã hợp nhất, khóa nằm ở vị trí đầu tiên. Một chương trình bao gồm các thủ tục về cột sống phải chứa các mô tả

gõ file=file của bản ghi
bản ghi=bản ghi
phím: mảng;
bối cảnh: mảng [1..60] của char
end;

(kiểu mảng được mô tả ở trên, trước (3)). Sau đó, thủ tục quay có dạng

thủ tục quay lại(var f1,f2,f: file);
var end:boolean
begin
kết thúc: sai; newrite(f); neset(f1);
reset(f2);
trong khi KHÔNG (kết thúc) làm
nếu f1↑.key-f2↑.key (4)
then
begin
viết(f,f1↑); viết(f,f2↑);
mục 1; mục 2
end
else
nếu so sánh(f1↑key, f2↑.key)
then
