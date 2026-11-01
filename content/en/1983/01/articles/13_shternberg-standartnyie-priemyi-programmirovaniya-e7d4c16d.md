---
id: 1983-1-shternberg-standartnyie-priemyi-programmirovaniya-e7d4c16d
issue: kvant_1983_1
year: 1983
number: "1"
title: Standard Programming Techniques
authors:
  - Штернберг Л. Ф.
rubric: raznoe
rubric_sub: Разное
page_first: 52
page_last: 53
page_labels: 50-51
tag: L0WC
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7d002bc91b23e073cb90d207e05353a8fb1edcda331d92645a704ebfa7f73633
prompt_sha256: draft-1
translated_from: content/ru/1983/01/articles/13_shternberg-standartnyie-priemyi-programmirovaniya-e7d4c16d.md
source_content_sha256: c797f94aa909457bee19d64912cbacf7efdd9f49cbc236fe71a80aeb080cf544
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 50⟧

Standard programming techniques

Lesson 4. Synchronous and asynchronous processing of arrays

If you were unable to find commonality and differences in the conditions of the problems, try to answer the question: what elements of the arrays will be worked with, say, at the 5th step of the algorithm (we consider the step to be the processing of one element in any array)? In the 3rd and 4th tasks, the answer to this question is simple: at the 5th step, the 5th elements in arrays A and B (3rd task), the 5th element in array B and the 10th element in array A (4th task) are processed. As for the first two tasks, at the 5th step the 5th element of the array by which we count the steps is processed, but we cannot say anything about other arrays (except that an element with a higher or lower number than in this array is processed). This is the key point: in tasks 3 and 4, the arrays are processed synchronously (that is, there is an explicit, analogous connection between the numbers of processed elements in different arrays; in tasks 1 and 2, between the numbers of processed elements in each pair of arrays, it is impossible to indicate a connection that does not depend on specific arrays, which can be expressed by a formula connecting only these numbers and some CONSTANTS. Therefore, we can say that in tasks 1 and 2 the arrays are processed synchronously,

Now let's look at the solutions given. All decisions are correct, but not all are equally good. Tasks 3 and 4 did not seem to cause difficulty, monocretion, monocretion and ease of understanding. Since in tasks 3 and 4 the arrays are processed synchronously,

It is enough to have one index to process all synchronously processed arrays.

In the 1st and 2nd tasks, arrays are processed synchronously, so an attempt to bypass one index is doomed to failure in advance:

When processing arrays asynchronously, each of the asynchronously processed arrays requires its own index (see solutions 1a, 16, 2a, 26).

In principle, of course, it is possible to introduce together, for example, counters, fixed

There is a significant separation of one index from another (see solutions 2c), but this does not simplify the program, but only violates the uniformity of array processing.

Let's take a closer look at solutions 1a and 16. These solutions are based on 2 strategic differences in the original approach. The first solution can be commented as follows: “We perform m+n steps of rewriting into array C. At each step, if the array A and B have not yet been exhausted, then we rewrite the current minimum element, otherwise - an element from the not yet exhausted array.” The second solution corresponds to the approach “Rewrite the current minimum element until one of the arrays is exhausted. Then we add the remaining array.” Both approaches are generally equal, although program 26 will run faster.

Now let's compare solutions 2a and 26. Formally, solution 26 is correct, but in similar situations two technically different approaches are used here: i numbers the first free element of the array and changes after rewriting, and k numbers

⟦folio 51⟧

Task 1

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

Problem 2

j:=1; k:=0;
for i:=1 to n do
begin
    if a[i]>0 then begin nol[j]:=a[i];
    j:=j+1 end;
    if a[i]<0 then begin k:=k+1;
    otrp[k]:=a[i] end
end;
nol[j]:=0; otrp[k+1]:=0;

Task 4 (Copying)

j:=2; for i:=1 to n do
begin b[i]:=a[j]; j:=j+2 end;

the last comma element and is changed before rewriting. In more complex cases, such different handling of similar situations can lead to errors, and in any case it does not make the program easier to understand. In technical matters, every programmer must have any technical techniques and not change them without good reason, then more creative forces will be left to solve strategic issues.

In program 2a the same lines are repeated twice. This can be avoided in the way shown in program 2c. Although the formal solution 2c is correct, it is not necessary to use “fits” such as transfer of control within the condition of the gender operator, and modern theory does not recommend using the transition operator at all. Note that there is usually one if statement, writing the census conditions from A, for example, like this:
if ((i<=n) AND (j<=m) AND
(a[j]<b[j])) OR (i>n) then
is impossible, since even if the condition i<=n is not met, the computer can still check the evaluation of the expression a[i]<b[j] by trying to process the non-existent element a[n+1].

Control job

4.1. Remove spaces from the text (character array) and “compress” the text, with a mouse

Task 1

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

Problem 2

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

the remaining characters to the left edge. Validation processing without an additional array.

4.2. (Assembly by weight). Given 2 arrays of equal length and an empty array. The elements of the 2nd array (array) have the values ​​true/false. The value false makes the i-th element of the array invisible (massages) the i-e value of the original array. Convert the visible (marked by the value of truths/a masses) elements of the first array into a third array, pressing them to the left edge and filling the rest of the third array with zeros. (Note that 2 arrays here will be processed synchronously, and the third one will be processed asynchronously with respect to the first two.)

4.3. (Disassembly by weight). Given an array, a mask and an empty array. The first few elements of the original array are sent to those elements of the empty array that are offset in the mass by the value of true / and the remaining elements are filled with zeros.

4.4. (Advanced complexity.) An array can contain several massive elements. In one view of the array, write out the numbers of all massive elements of the original array into another array.

Preparatory tasks for lesson 5

1. Print a table of values ​​of the function y=x² with x changing from a to b in steps of h.
2. Find the arithmetic mean of the array elements.
3. Given an array of real numbers. Find a number in it equal to a given one: get the number of this number or zero if there is no such number.

L. F. Shteriber
