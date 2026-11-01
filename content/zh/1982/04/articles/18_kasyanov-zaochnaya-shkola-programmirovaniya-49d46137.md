---
id: 1982-4-kasyanov-zaochnaya-shkola-programmirovaniya-49d46137
issue: kvant_1982_4
year: 1982
number: "4"
title: 函授编程学院
authors:
  - Касьянов В.
rubric: raznoe
rubric_sub: Разное
page_first: 52
page_last: 53
page_labels: 50-51
tag: OPP9
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 53d9d7e391fbe3a30959bc40851ec163a6e6af24940ade245915b611076faa83
prompt_sha256: draft-1
translated_from: content/ru/1982/04/articles/18_kasyanov-zaochnaya-shkola-programmirovaniya-49d46137.md
source_content_sha256: 5e77b68f1631a4c8242352f7d7a6972db8c9ecce8922d36236a5a013400956c8
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 50⟧

函授编程学院
第 20 课：过程和函数参数

在 Pascal 中，过程和函数都可以有参数列表。每个过程参数*) 在过程描述中都由特定名称表示，称为形式参数。形式参数起着指定的作用，它允许我们描述在过程的不同执行过程中要应用到不同实际数量的操作序列。这些值在过程调用语句或函数处理中以实参列表的形式指定，其长度与形参列表的长度一致。形参和实参之间建立了简单的位置对应关系：第一个实参对应第一个形参，第二个实参对应第二个形参，以此类推。过程的每个格式参数仅在该过程内有意义。在过程开始时，形参与相应实参指定的值相关联，并且存在于该过程之外。

Pascal 有四种类型的参数：值参数、变量参数、过程参数和函数参数。过程的一个或另一个参数的类型在其标头中指定（参见第 16 课）。

*) 这里和下面所说的有关过程参数的所有内容都完全转移到函数参数。

参数值
值参数用图来描述：

过程的 value 参数是它的局部变量（Rapier 中的局部和全局名称，请参阅第 7 课）。形式参数表示过程描述中的该变量。这种情况下的实际参数必须是与相应格式参数表示的变量类型相同的表达式。当调用该过程时，将计算该表达式，并将结果值分配给该变量作为初始值。稍后，当该过程被执行时，该变量与该过程的其他局部变量没有什么不同。

两个正整数的最公约数可以使用以下函数完成：

```matlab
function nod(x, y:integer):integer;
{0≤y≤X}
begin if y=0
then nod:=x
else nod:=nod(x,x mod y)
end;
```

任务 20.1。该功能的描述如下：

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

确定执行访问a(2,2)时同时存在的参数x的最大实例数。

可变参数

描述变量参数的图表如下所示：

⟦folio 51⟧

在这种情况下，实际参数必须是指定类型的变量，而形式参数在给定过程执行的整个持续时间内充当该变量的名称。如果实际参数包含索引，则它们在调用过程时计算。

在使用参数来表示过程或函数的结果的所有情况下都需要可变参数。

第二期«Kvant»讨论的排序程序已经使用了此类参数。

设有以下描述：

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

然后，执行完运算符`k:=20; max(k)`后，变量`k`将被赋予`b[20], b[21], ..., b[100]`的最大元素的索引。

任务 20.2。是否可以使用程序

```python
procedure заменa(var x,y:integer);
var z:integer;
begin
z:=x;
x:=y;
y:=z
end
```

任意两个整数类型的变量交换值？例如，如果执行值为 19，则变量 `k` 和 `a[20]` 的值是否放置在调用替换 (`k, a [k+1]`) 之后？

任务 20.3。要有描述

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

并给出了三​​个表

```python
a = (1 1) , b = (2 2) , c = (3 3) .
```

在上述各项之后定义表视图 `a`、`b` 和 `c`：

`умножение (a, b, c)`、`умножение (a, b, a)`、`умножение (a, b, b)`。如果将参数 `x` 和 `y` 设置为参数值，那么在这些相同的调用中会发生什么？如果 z 也成为值参数会发生什么？

过程参数和函数参数

描述过程参数和函数参数的图表如下所示：

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
