---
id: 1982-4-kasyanov-zaochnaya-shkola-programmirovaniya-49d46137
issue: kvant_1982_4
year: 1982
number: "4"
title: Correspondence School of Programming
authors:
  - Касьянов В.
rubric: raznoe
rubric_sub: Разное
page_first: 52
page_last: 53
page_labels: 50-51
tag: OPP9
lang: en
source: kvant_digital
extraction: vision
content_sha256: 573f0c9092782e4275c559087c19dc4f30944dd370431ab7332241c24d4e10c5
prompt_sha256: draft-1
translated_from: content/ru/1982/04/articles/18_kasyanov-zaochnaya-shkola-programmirovaniya-49d46137.md
source_content_sha256: 5e77b68f1631a4c8242352f7d7a6972db8c9ecce8922d36236a5a013400956c8
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 50⟧

Correspondence School of Programming
Lesson 20: Procedure and Function Parameters

In Pascal, both a procedure and a function can have a list of parameters. Each of the procedure parameters*) is represented within the procedure description by a certain name, called a formal parameter. The formal parameter plays the role of a designation that allows us to describe the sequence of actions that we want to apply during different executions of the procedure to different actual quantities. These values ​​are specified in the procedure call statement or in function processing in the form of a list of actual parameters, the length of which coincides with the length of the list of formal parameters. A simple positional correspondence is established between formal and actual parameters: the first actual parameter corresponds to the first formal one, the second to the second, etc. Each format parameter of a procedure is meaningful only within this procedure. At the beginning of the procedure, the formal parameter is associated with the value specified by the corresponding actual parameter and exists outside this procedure.

Pascal has four types of parameters: value parameters, variable parameters, procedure parameters, and function parameters. The type of one or another parameter of a procedure is specified in its header (see lesson 16).

*) Everything that is said here and below about procedure parameters is completely transferred to function parameters.

Parameters-values
Value parameters are described by a diagram:

The value parameter of a procedure is its local variable (for local and global names in Rapier, see Lesson 7). A formal parameter represents this variable within a procedure description. The actual parameter in this case must be an expression of the same type as the variable denoted by the corresponding format parameter. When the procedure is called, this expression is evaluated, and the resulting value is assigned to the variable as the initial value. Later, when the procedure is executed, this variable is no different from other local variables of this procedure.

The most common divisor of two positive integers can be done using the following function:

```matlab
function nod(x, y:integer):integer;
{0≤y≤X}
begin if y=0
then nod:=x
else nod:=nod(x,x mod y)
end;
```

Task 20.1. The following description of the function is available:

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

Determine the maximum number of instances of parameter x that simultaneously exist when executing access a (2,2).

Variable parameters

The diagram describing the variable parameters looks like:

⟦folio 51⟧

In this case, the actual parameter must be a variable of the specified type, and the formal parameter serves as the designation of that variable for the entire duration of a given execution of the procedure. If the actual parameter contains indexes, they are calculated at the time the procedure is called.

A variable parameter is required in all cases where a parameter is used to represent the result of a procedure or function.

The sorting programs discussed in the second issue «Kvant» have already used this type of parameters.

Let there be the following descriptions:

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

Then, after executing the operators `k:=20; max(k)`, the variable `k` will be assigned the index of the most element of `b[20], b[21], ..., b[100]`.

Task 20.2. Is it possible to use procedures

```python
procedure заменa(var x,y:integer);
var z:integer;
begin
z:=x;
x:=y;
y:=z
end
```

to exchange values ​​for any two variables of integer type? For example, is the value of the variables `k` and `a[20]` placed after the call to replace (`k, a [k+1]`) if its execution value was 19?

Task 20.3. Let there be descriptions

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

and three tables are given

```python
a = (1 1) , b = (2 2) , c = (3 3) .
```

Define the table view `a`, `b` and `c` after each of the above:

`умножение (a, b, c)`, `умножение (a, b, a)`, `умножение (a, b, b)`. What happens in these same calls if parameters `x` and `y` are made parameters values? What happens if z also becomes a value parameter?

Procedure parameters and function parameters

Diagrams describing procedure parameters and function parameters look like:

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
