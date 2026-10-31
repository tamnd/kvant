---
id: 1981-11-yunerman-zaochnaya-shkola-programmirovaniya-10021a26
issue: kvant_1981_11
year: 1981
number: "11"
title: Trường lập trình tương ứng
authors:
  - Юнерман Н. А.
rubric: raznoe
rubric_sub: Разное
page_first: 42
page_last: 45
page_labels: 40-43
tag: CZMY
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 41713956562da108e7995e7ab723858df7ee9b89f57bf4d768d4b6ca0a52b8fd
prompt_sha256: draft-1
translated_from: content/ru/1981/11/articles/13_yunerman-zaochnaya-shkola-programmirovaniya-10021a26.md
source_content_sha256: 27f0ced29809dfb842f3a292659d374e19f3e333f00c98f9b023b0702fd5d76f
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 40⟧

Trường lập trình tương ứng

Bài 16: Câu điều kiện và câu lệnh lựa chọn.
Toán tử vòng lặp.
Thủ tục và hàm trong Pascal.

Khi học ngôn ngữ Rapier, bạn đã quen với thực tế là trong các lệnh có điều kiện và tuần hoàn sau các từ TO và ELSE và sau dấu :: bạn có thể viết bao nhiêu lệnh tùy thích (trước từ BCE). Trong Pascal, các toán tử này có cấu trúc khác: chúng chỉ cho phép một toán tử, giống như trong Robik. Nếu, theo nghĩa của bài toán, nếu bạn cần sử dụng một số toán tử, thì bạn phải sử dụng một cấu trúc đặc biệt - toán tử ghép.

Câu lệnh ghép là một chuỗi các câu lệnh được đặt trong dấu ngoặc toán tử `begin-end`. Sơ đồ cú pháp để mô tả một toán tử ghép là:

Sơ đồ cho thấy các câu lệnh trong câu lệnh ghép phải được phân tách bằng dấu chấm phẩy.

Câu lệnh điều kiện được mô tả bằng sơ đồ:

Ở đây và trong tất cả các sơ đồ tiếp theo, toán tử có thể là phép ghép. Điều kiện có thể đơn giản hoặc phức tạp. Một điều kiện phức tạp được hình thành bằng cách sử dụng các toán tử logic AND, OR và NOT. Khi viết điều kiện, các dấu so sánh sau được sử dụng: = bằng
< > không bằng
> hơn
< ít hơn
< = nhỏ hơn hoặc bằng
> = lớn hơn hoặc bằng

Ví dụ: sau khi thực hiện một chuỗi câu lệnh
x:=k mod 5;
a:=k mod 4;
if (x=0) AND (a=1)
sau đó viếtln('CÓ')
khác writeln('NO');

CÓ sẽ được in nếu số k là bội số của 5 và để lại 1 khi chia cho 4, và KHÔNG nếu ngược lại.

Sử dụng câu lệnh điều kiện, bạn có thể chọn một trong hai tùy chọn để thực hiện chương trình tiếp theo. Trong thực tế, thường có thể chọn một phương án không phải từ hai phương án mà từ số lượng phương án lớn hơn. Trong trường hợp này, hãy sử dụng toán tử lựa chọn - toán tử `case`, có thể được mô tả bằng sơ đồ:

Toán tử chọn hoạt động như thế này. Đầu tiên, giá trị của biểu thức được tính toán, sau đó tìm thấy một hằng số bằng giá trị được tính toán của biểu thức và toán tử được viết sau hằng số này được thực thi. Nếu không có hằng số đó thì câu lệnh theo sau câu lệnh lựa chọn sẽ được thực thi. Cần thay thế

⟦folio 41⟧

Lưu ý rằng biểu thức và hằng số phải cùng loại.
Hãy xem một ví dụ. Mỗi điểm trường được đánh dấu bằng một con số và có tên. Ví dụ: 3 là thỏa đáng. Theo chương trình sau đây, giá trị của đánh giá, được viết bằng số, được nhập và tên của nó được in ra.

**đánh giá chương trình (đầu ra, đầu vào);**
**độ cao var:1..5;**
**begin**
  **đọc(hủy);**
  **dấu trường hợp của**
    5: **writeln('TUYỆT VỜI');**
    4: **writeln('TỐT');**
    3: **writeln('HÀI LÒNG');**
    2: **writeln('BAD');**
    1: **writeln('RẤT TỆ')**
  **end**
**end.**

4
Chương trình cho ví dụ này được viết theo lớp WELL.
Nhiệm vụ 16.1. Hệ thống chỉ huy cho xe tự hành Kibik được đưa ra:

| đội | hoạt động |
| :--- | :--- |
| 1 | lái xe 100 m về phía bắc |
| 2 | lái xe 100 m về phía nam |
| 3 | lái xe 100 m về phía tây |
| 4 | lái xe 100 m về phía đông |

Viết chương trình in tọa độ vị trí ban đầu của Kibik và một lệnh, sau đó in tọa độ của điểm mà Kibik sẽ ở sau khi sử dụng lệnh này.

**Bình luận**

Nếu bạn cố gắng phân tích chương trình khá phức tạp của người khác, bạn sẽ gặp nhiều khó khăn khác nhau: bạn sẽ không hiểu tất cả các ký hiệu, mục đích của một số biến, thuật toán được sử dụng, v.v. Để giúp người khác phân tích chương trình của bạn dễ dàng hơn, nó có thể được bổ sung bằng các khái niệm phức tạp.

ý kiến, được gọi là **người bình luận**.

Chú thích không ảnh hưởng đến việc thực hiện chương trình; mục đích của chúng là giúp người đọc chương trình hiểu rõ hơn và nhanh hơn cấu trúc của chương trình, hiểu ý nghĩa và mục đích của thuật toán đã chọn cũng như ghi chú một số tính năng nhất định của chương trình. Các nhận xét nên được đưa vào chương trình khi nó được viết.

Trong Pascal, bất kỳ văn bản nào nằm trong dấu ngoặc nhọn đều được coi là một nhận xét. Một bình luận có thể được đặt ở bất cứ đâu trong chương trình. Hơn nữa, khi văn bản chương trình được in, chú thích sẽ được in cùng với chương trình.

**Các toán tử vòng lặp**

Trong Pascal, có ba loại toán tử vòng lặp: vòng lặp có điều kiện tiếp tục, vòng lặp có điều kiện kết thúc và vòng lặp có tham số.

Một chu trình với các điều kiện tiếp tục được mô tả bằng sơ đồ:

```
while условие do метод цикла
```

Hoạt động của toán tử này tương tự như hoạt động của toán tử vòng lặp WHILE trong Rapier: phần thân của vòng lặp được thực thi miễn là điều kiện còn đúng. Phần thân của vòng lặp là một câu lệnh đơn (có thể là câu lệnh ghép).

Hãy xem xét một chương trình tính giá trị của hàm $F(n) = n! = 1*2*...*n$.

Hãy nhớ lại rằng $0! = 1$ và mối quan hệ truy hồi $F(k) = k*F(k-1)$ được giữ nguyên.

**thực tế chương trình1 (đầu ra, đầu vào);**
**var f,k,n; integer;**
**begin**
  **read(n); {n≥0}**
  **f:=1; k:=0;**
  **while k<>n do**
    **begin {f=k!}**
      k:=k+1; f:=f*k
    **end;**
    {f=n!}
    **writeln('n-',n,' n!=',f)}
**end.**
```

⟦folio 42⟧

После использования этой программы будет напечатано: $n=5 \ n!=120$.

Задание 16.2. Система команд Кибика дополнения командой 0 — законить работу. Используя задание 16.1, составьте программу, которая выводит координаты начального положения Кибика и программу его движения (одну команду за другой), а также печатает координаты конечной точки марсирута и чертит путь движения Кибика (с помощью процедуры ШПАГА).

Цикл с условиям окончания описывается diagramмой:

В этом случае сначала выполняется тело цикла, а потом проверяется условия. Выход из цикла происходит в случае, когда условия истинно. Особенность этого цикла состоит в том, что тело цикла всегда выполняется хотя бы один раз, даже если условия сразу истинно.

Запишем теперь программу, вычисляющую значения функции $F(n)=n!$, использующая оператор цикла с условиям окончания.

program факт2(output, input);
var f,k,n:integer;
begin
read(n); f:=1; k:=1;
repeat
f:=f*k; k:=k+1
until k>n;
writeln('n=',n,' n!=',f)
end.

Сравните условия в этих двух программы! В первом случае тело цикла повторяется при истинном значении условия, а во втором истинное условия — признак окончания цикла.

Цикл с параметром описывается diagramмой:

Значение выражения -1 — начальное значение переменной цикла, а значение выражения -2 — ее конечное значение. Тип переменной цикла должен быть скалярным (кроме real). Работа этого оператора цикла состоит в следующем. Сначала переменная цикла получает начальное значение, и если оно не превыходит конечного значения, выполняется тело цикла. Затем переменная цикла принимает следующое значение, полученное при помощи функций `succ*()` (в случае `to`) или `pred` (в случае `downto`), и опять выполняется тело цикла. В наиболее распространенном случае, когда переменная цикла принимает значения типа `integer`, ее значение изменяется на +1 (в случае `to`) и на -1 (в случае `downto`). Так происходит до тех пор, пока значение переменной цикла не превышает конечного значения.

Обратите внимание, что в первых двух типах цикла должна быть содержать оператор, изменяющий значение переменной цикла (начие произойдет зацикливание!), а в цикле с параметром наличие такого оператора приводит к ошибке.

Следующая программа отпадает все пары целых чисел $(x; y)$, являющиеся решениями уравнения $2y-x^2=4$, если $x \in [-50; 25]$, $y \in [100; 300]$.

program корни (output);
var сикор,x,y,i,j:integer;
begin
сикор:=0; {число корней}
for i:=-50 to 25 do
for j:=100 to 300 do
if 2*y-x*x=4 then
begin
сикор:=сикор+1;
writeln('x=',x,' y=',y)
end;
if сикор=0
then writeln('корней нет')
end.

Задание 16.3. Составьте программу для нахождения суммы $s=1+\frac{1}{2}+\ldots+\frac{1}{n}$. Предусмотрите вывод числа $n$.

*) О функциях `succ` и `pred` расссказано ниже.

⟦folio 43⟧

Процедуры и функции
Описания процедуры и функции в Паскале имеют такое структуру, как и вся программа. Отличие состоит только в форме заголовка. Задоловок процедуры описывается диаграммой:

Формальные параметры описываются диаграммой:

Подробно о видах параметров и способах их передачи при вызове процедур будет расссказано в одном из следующих уроков.

Задоловок функции описывается диаграммой*):

Тип результата функции должен быть скалярным. Описем в виде процедуры, а затем в виде функции, программы, вычисляющего значения функции $F(n) = n!$.

procedure факт1 (n:integer);
var k,f:integer;
begin
f:=1; k:=0;
while k<>n do
begin
k:=k+1; f:=f*k
end;
writeln('n=',n,n!='',f)
end;
function факт2 (n:integer) :integer;
var k,f:integer;
begin
f:=1; k:=1;
repeat
f:=f*k; k:=k+1
until k>n;
факт2:=f
end;

Пусть теперь нужно найти значение $C = \frac{n!}{k!(n-k)!}$. Используя функцию факт 2, легко записать соответствующий оператор присваивания:
$c: = \text{факт2}(n) / (\text{факт2}(k)*\text{факт2}(n-k))$

Стандартные функции

В Паскале можно использовать все стандартные функции. Парниры: sin, cos, exp, ln, arctan и функции abs, sqr, sqrt, arcsin, odd, round, trunc, succ, pred.

$abs(x) = |x|$, $sqr(x) = x^2$, $sqrt(x) = \sqrt{x}$.

Результат функции odd(x) есть true, если $x$ — нечетное число, и false при $x$ четном.

Функция round округляет значение действительного числа, а функция trunc отбрасывает его дробную часть. Например, round (5.7) = 6, trunc (5.7) = 5.

Функция succ и pred применены к любому скалярному типу (кроме real). Результат функции succ(x) есть следующее за $x$ значение в описании типа, а функция pred(x) — предшествующего $x$ значение.

Описем тип неделя — (nн, вт, cp, чт, nт, сб, вск). Тогда succ(cp) = чт, pred(cp) = вт.

Результатом выполнения цикла for дены: = nn to вск do
writeln(дены);
будет печать всех значений данного типа:
nn вт cp чт nт сб вск*).

Задание 16.4. Описите функцию стен для вычисления $x^n$ с параметрами $x: \text{real}, n: \text{integer}$.

Задание 16.5. Описите процедуру с параметром $n: \text{integer}$ для вычисления суммы $S = 1^3 + 2^3 + \ldots + n^3$.

Указаны е. Используйте функцию стен из задания 16.4.

H. Юнерман

*) На диаграмме не показана обходная стрелка, начинашаяся после поля имя и кончащаяся перед полем с двоечением.

*) Разумеется, машина напечает эти значения в столбик.
