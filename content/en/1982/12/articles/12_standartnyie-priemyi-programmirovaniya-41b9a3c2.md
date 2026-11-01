---
id: 1982-12-standartnyie-priemyi-programmirovaniya-41b9a3c2
issue: kvant_1982_12
year: 1982
number: "12"
title: Standard Programming Techniques
rubric: raznoe
rubric_sub: Разное
page_first: 44
page_last: 45
page_labels: 42-43
tag: EX2K
lang: en
source: kvant_digital
extraction: vision
content_sha256: 98b6a18e81a8ec5dd90e3407c6d0ce69593f47b76b5cd581624691562c532d64
prompt_sha256: draft-1
translated_from: content/ru/1982/12/articles/12_standartnyie-priemyi-programmirovaniya-41b9a3c2.md
source_content_sha256: 55500374dcd5d3959cec50cd82ac1bd852ff3bd1efe9be921ac4823d8e3dfe16
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 42⟧

Traditional programming techniques.

Lesson 3. Processing arrays on site

Compare your solutions to the preparatory problems for this lesson (see «Kvant» No. 11, Lesson 2) with those given here. Options a) are correct solutions, options b) are typical errors (programs do not give the desired result), options θ) will work, and yet they cannot be considered techniques.

Just like in the last lesson, let's look at what the problem conditions have in common.

The main general point is that the result should be obtained in the same place where the source data is located. Now look at the calculation formulas in the conditions of the problems (the reader will forgive the use of the program sign “assignment” together with the mathematical sign “equals”, it is natural here) and compare the calculation formulas with solutions b); these solutions are “literal” translations of the formula in a programming language. We encountered the same problem as in previous lessons: differences in the rules of speaking in the language of mathematics and programming language.

When a mathematician writes a formula for the transproduction of a matrix, that is, the reflection of its elements relative to the diagonal (for all i, j a'ij := aji), he apparently means that at the command “Halle-op!” all the elements of the matrix will jump up at once and then all at once fall into place, but with changed values. But the computer cannot do everything at once*, the data processing process occurs in space and time: first one element is processed, then another, etc. And by the time the processing of the i-th element begins, for which the structure of the k-th element is needed, the k-th element

*) Some modern computers have already learned this, but the possibilities are also not reflected in the Pakel language.

Solutions to preparatory problems

a) Task 1 (arithmetic mean and geometric mean)
for i:=1 to n do
begin d:=a[i];
a[i] := (a[i] + b[i])/2;
b[i] := sqrt(d*b[i])
end;
Faster option:
for i:=1 to n do
begin ai:=a[i]; bi:=b[i];
a[i] := (ai+bi)/2;
b[i] := sqrt(ai*bi)
end;

b) Task 2 (division by a diagonal element)
for i:=1 to n do
begin d:=a[i,i];
for j:=1 to n do
a[i,j] := a[i,j]/d;
end;

Task 3 (transproduction)
for i:=1 to n-1 do
for j:=i+1 to n do
begin d:=a[i,j];
a[i,j] := a[j,i];
a[j,i] := d
end;

for i:=1 to n do
for j:=1 to n do
a[i,j] := a[j,i];
second solution:
for i:=1 to n do
for j:=1 to n do
begin d:=a[i,j];
a[i,j] := a[j,i];
a[j,i] := d
end;

⟦folio 43⟧

the new value can already succeed. Similarly, we are accustomed to the fact that we translate the mathematical phrase “for all $i$ with $i \in M$” into a programming language by a loop with the parameter $i$ running through the set $M$. Most often this translation is correct, but there are exceptions, one of which is often the processing of arrays on site. Look at the second solution $6$) of problem 3 and try to understand what the program will do and why, as a result of its operation, the matrix will remain unchanged.

So, it became clear that if one of the elements of the array being processed on site is needed to calculate the new value of another element, then it must be saved somehow. The simplest solution - making a copy of the original array and writing the result to another location - is often not suitable in practice. When programming a large task (or a not very large task, but on a computer with little memory), you may encounter a situation where the array takes up almost all the memory and there is simply no room for a copy. This is the disadvantage of options $b$): with large array sizes, the program will not have enough memory. However, as options $a$ show), there is no need to copy the array: in full, you can bypass one additional element (in programs, this is a variable named $d$) to store the value needed to calculate several new values.

Now we can draw final conclusions.

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

1. When processing arrays in place, it is necessary to take measures to save the values ​​of elements needed for subsequent calculations. As a rule, ONE auxiliary element is enough for this.

As a last resort, when one element is clearly not enough, you can take an array of less dimension (for example, a one-dimensional array together with a matrix). Of course, there are cases when the array cannot be processed on site, and then we end up with a copy.

2. If elements are processed out of order in the array, then loops over the array elements should be organized in a special way.

For example, in task 3, pairs of elements that are symmetrical relative to the diagonal are simultaneously processed, so the organization of the loop differs from the “literal” translation of a mathematical formula.

Let's now see why novice programs don't see the error in the options - this is a variable named $d$) to store the value needed to calculate several new values.

Let's check, for example, option $b$) of problem 1. To do this, take small arrays, say $a=(2,3,4)$, $b=(5,6,7)$, and scroll through the program $n=3$, $i=1$, $a[1]=(2+5)/2=3,5$, $b[1]=\sqrt{2\cdot5}=\sqrt{10}$, etc. This is the very typical mistake: we did what we ourselves want from the computer, and not what the computer will actually do!

Correct scrolling is performed as follows: a) writes out a table of all identifiers and their values ​​valid in the format being checked, b) at each step, the old value is crossed out and replaced with a new one.

Let's scroll through the same example:

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

The error became visible at the very first step.

And finally, the last question: does the program deteriorate in speed when
