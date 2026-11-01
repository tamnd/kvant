---
id: 1981-11-yunerman-zaochnaya-shkola-programmirovaniya-10021a26
issue: kvant_1981_11
year: 1981
number: "11"
title: Correspondence School of Programming
authors:
  - Юнерман Н. А.
rubric: raznoe
rubric_sub: Разное
page_first: 42
page_last: 45
page_labels: 40-43
tag: CZMY
lang: en
source: kvant_digital
extraction: vision
content_sha256: 2da4d9c235a3beb55009ede43f214c1314a2b2070976728efeb868f1d1f0f69d
prompt_sha256: draft-1
translated_from: content/ru/1981/11/articles/13_yunerman-zaochnaya-shkola-programmirovaniya-10021a26.md
source_content_sha256: 27f0ced29809dfb842f3a292659d374e19f3e333f00c98f9b023b0702fd5d76f
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 40⟧

Correspondence School of Programming

Lesson 16: Conditional and selection statements.
Loop operators.
Procedures and functions in Pascal.

When studying the Rapier language, you got used to the fact that in conditional and cyclic instructions after the words TO and ELSE and after the sign :: you can write as many instructions as you like (before the word BCE). In Pascal, these operators have a different structure: they only allow one operator, just like in Robik. If, according to the meaning of the problem, you need to use several operators, you have to use a special construction - a compound operator.

A compound statement is a sequence of statements enclosed in operator brackets `begin-end`. The syntax diagram for describing a compound operator is:

The diagram shows that statements included in a compound statement must be separated by a semicolon.

The conditional statement is described by a diagram:

Here and in all subsequent diagrams, the operator can be compound. The condition may be simple or complex. A complex condition is formed using the logical operators AND, OR and NOT. When writing conditions, the following comparison signs are used: = equals
< > not equal
> more
< less
< = less than or equal to
> = greater than or equal to

For example, after executing a sequence of statements
x:=k mod 5;
a:=k mod 4;
if (x=0) AND (a=1)
then writeln('YES')
else writeln('NO');

YES will be printed if the number k is a multiple of 5 and leaves a remainder of 1 when divided by 4, and NO otherwise.

Using a conditional statement, you can choose one of two options for further program execution. In practice, it is often possible to choose one option not from two, but from a larger number of options. In this case, use the selection operator - operator `case`, which can be described by a diagram:

The select operator works like this. First, the value of the expression is calculated, then a constant equal to the calculated value of the expression is found, and the operator written after this constant is executed. If there is no such constant, then the statement following the selection statement will be executed. Needs replacement

⟦folio 41⟧

Note that the expression and the constant must be of the same type.
Let's look at an example. Each school mark is indicated by a number and has a name. For example, 3 is satisfactory. According to the following program, the value of the assessment, written in numbers, is entered, and its name is printed.

**program evaluation (output, input);**
**var elev:1..5;**
**begin**
  **read(cancel);**
  **case mark of**
    5: **writeln('EXCELLENT');**
    4: **writeln('GOOD');**
    3: **writeln('SATISFIED');**
    2: **writeln('BAD');**
    1: **writeln('VERY BAD')**
  **end**
**end.**

4
The program for this example is written in layers WELL.
Task 16.1. The command system for the Kibik self-propelled vehicle is given:

| team | action |
| :--- | :--- |
| 1 | drive 100 m north |
| 2 | drive 100 m south |
| 3 | drive 100 m west |
| 4 | drive 100 m east |

Write a program that prints the coordinates of Kibik's initial position and one command, and then prints the coordinates of the point where Kibik will be after using this command.

**Comment**

If you try to parse someone else’s rather complex program, you will encounter various difficulties: you will not understand all the notation, the purpose of certain variables, the algorithms used, etc. In order to make it easier for another person to parse your program, it can be supplemented with complex concepts.

opinions, called **commenters**.

Comments do not affect the execution of the program; their purpose is to help the person reading the program to better and faster understand the structure of the program, to understand the meaning and purpose of the selected algorithm, and to note certain features of the program. Comments should be included in the program as it is written.

In Pascal, any text enclosed in curly braces is treated as a comment. A comment can be placed anywhere in the program. Further, when the program text is printed, the comment is printed along with the program.

**Loop Operators**

In Pascal, there are three types of loop operator: a loop with continuation conditions, a loop with termination conditions, and a loop with a parameter.

A cycle with continuation conditions is described by the diagram:

```
while условие do метод цикла
```

The operation of this operator is similar to the operation of the WHILE loop operator in Rapier: the body of the loop is executed as long as the condition is true. The body of a loop is a single (possibly compound) statement.

Consider a program for calculating the values ​​of functions $F(n) = n! = 1*2*...*n$.

Recall that $0! = 1$ and the recurrence relation $F(k) = k*F(k-1)$ holds.

**program fact1 (output, input);**
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
