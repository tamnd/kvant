---
id: 1987-1-shternberg-tsiklyi-tsiklyi-tsiklyi-c7696aed
issue: kvant_1987_1
year: 1987
number: "1"
title: Cycles, cycles, cycles...
authors:
  - Штернберг Л. Ф.
rubric: raznoe
rubric_sub: Разное
page_first: 45
page_last: 48
page_labels: 43, 45, 46
tag: DCVI
lang: en
source: kvant_digital
extraction: vision
content_sha256: 414d5123a0b62695dd2dd9dd7a60e30bf2e4bcedf1afcce64150ffc8ac190e81
prompt_sha256: draft-1
translated_from: content/ru/1987/01/articles/13_shternberg-tsiklyi-tsiklyi-tsiklyi-c7696aed.md
source_content_sha256: a1673b5960814355adb71def9cb115f2df52741074c3e69ad8c55647a7b1f8ca
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 43⟧

Cycles, cycles, cycles...

Candidate of Physical and Mathematical Sciences
L. F. STERNBERG

Programming would lose a lot if there were no concept of branching or a helper algorithm, but the heart of a program is still loops. However, since a written command inside a loop will be executed many times, this gives meaning to the work of compiling a program.

The work of the loss team is answered 3 pages in the 9th grade textbook, and many problems are solved with its help. Another 2 pages of theory are answered in the textbook “Informatικά-10” *); an additional construction is introduced - a cycle for, which is convenient, but which could be done without. So what can we say about cycles? Komy is an uninterpreted phrase in Russian

while the condition is to lose the action kts, from which the command is obtained

*) This is how the author briefly calls the textbook “Fundamentals of Informatics and Computer Science,” Note. ed.)

repetitions (if we replace the word “repeat” with the word “ncc”)? We will continue to use the word “repeat” in writing cycle commands - a cycle written this way is easier to read and understand. And yet the cycles are different.

Let's start with the simplest task: using the one described on p. 78-81 of the textbook "Informatικά-9" graphic artist draw a staff with a line length of 50 and a distance between lines of 3. This can be done with the following program (hereinafter we will write only programs, without a title and without descriptions):

k:=1;
until k≤5 repeat
right (90); draw; forward(50);
don't draw; back(50);
left (90); forward (3);
k:=k+1
kts

If our performer was commanded by a person not familiar with programming, then he would say this: “do the following 5 times: to the right (90); draw... forward (3).” And indeed: we need the variable k only to count the number of loop losses; we don’t need it in the body of the loop; but the performer does not know about this, and he will honestly complete the variable k and write the current value of k there: what if it will be used in the future?

⟦folio 45⟧

i:=0; y:=a[0];
until i≠n repeat
i:=i+1; y:=y·x+a[i]
kts

Look at the variable i: at each step of the loop it changes to the same value (in this case, 1), and it is this variable that determines when to end the loop. Read through the textbook - on almost every page you will find a loop in which some variable is changed to the same value each time, and it is by its value that the completion of the loop is determined. This situation occurs very often, so such loops are given a special name - loops with a parameter.

A loop parameter is the same variable that changes in the same way and serves to determine the end of the loop. There is also a special recording form for them:

changing the parameter from value 1 in steps to value 2
up to value 3 repeat steps kts

The meaning of this construction, as always, corresponds to the meaning of the phrase in Russian. With its help, the Horner scheme algorithm can be written
y:=a[0];
changing i from 1 step 1 to n repeat
y:=y·x+a[i]
kts

As you can see, here the loop header returns to itself and sets the initial value of the parameter, and changes it, and checks for the end of the loop. In this case, the step, if it is equal to one, need not be specified. So, in our case we can write

changing i from 1 to n repeat

Such a loop exists in practically all programming languages, but traditionally it has a slightly different form of notation:

for... from... step... to... cycle and is also called a “cycle for”. It is in this form that it is found in the languages ​​Panipa, PL/1, Allol-60, Allol-68, etc. Moreover, in some languages ​​(Fortran, for example, or a school algorithmic language) the final value is first specified, and then the step, and in some (PL/1) you can write both ways.

Why did this cycle design appear in the Information-10 textbook? At first glance, this cycle, like the cycle of repeating... times, does not give us anything new - only the recording has become more similar: together
x:=a;
until x≤b repeat
... x:=x+h;
kts

we write

changing x from a step h to b repeat... kts and that's it. But this is not entirely true: for example, if a=0, b=1, a h=0.1, then both cycles will work out the same, but if h=-0.1, then the cycle will appear (the value of a will never become greater than b), and the cycle with the parameter is simply not executed even once: the fact is that in this cycle the condition “x≤b” is not simply checked, but the parameter value is controlled to be between a and b; when trying to leave the range in any direction, in particular, if the step is directed not towards b, but in the opposite direction, the cycle will not execute. So, a loop with a parameter is like a repeat loop...
times is a defensive construction: such cycles are never protected.

Exercise using a cycle for (cycle changing) the MINELEMENT and ORDERING algorithms (A7, A8 on p. 93, “Information-9”).

But even in a loop with a parameter, a situation may arise when it is not clear in advance how many steps to change the parameter must be taken. For example, let’s say in a table of M elements we need to find the position where the element equal to i occurs. To search for an element, you need to look through the table element by element, changing the index to 1, but how many steps you need to take is unknown in advance. A mushroom from the cycle changing and the cycle while will help us cope with this task:

changing i from 1 step 1 until a[i]≠x repeat kts Please note: the body of the loop is empty - everything that is needed is executed by the loop header; The loop exits when a[i]=x, while i will contain the number of the table element on which the loop ended.

Such a cycle exists in the PL/1 language.

It is clear that a hybrid can also be formed

me... from... step... repeat... until... in which the parameter is changed and the check happens at the end. The above method of finding the desired element in the table will only work when we are sure of

⟦folio 46⟧

that the element you are looking for is in the table. If it is not there, then after $M$ steps the value $i$ will go beyond the table boundary, and we will receive an error message, or the computer will start doing something unpredictable. Let's change our algorithm so that if the required element is missing, it gives us, for example, a zero number value. It would seem that you could do it like this:

changing $i$ from 1 step 1 showing $i \leqslant M$ and $a[i] \neq x$ repeat kts;
if $i > M$ then $i := 0$; All;

but this cannot be done: if there is no element needed, then at step $(M+1)$, even after making sure that $i > M$, the computer will still try to compare the non-existent element $a[M+1]$ with $x$ - and may give an error message. Looking at the textbook on p. 57, we will find a way to get out of this situation at the cost of introducing an additional variable and additional comparisons (the number of comparisons gives no less than double), and having studied it, we admit that not everyone could come up with it on their own. Now, if we could force the computer to first compare $i$ with $M$, and carry out the second comparison only if the result of the first comparison is positive...

But the reader has probably already understood our main idea: if we are uncomfortable working, it means that we are missing something and this “something” needs to be maintained. What we lack is the ability to perform two separate checks and two exits from the loop: upon detection of an element and upon depletion of the table. Considering that the search task is a very common task, then introducing convenient search tools is not a small thing. But recognizing that there can be more than one reason for exit in a cycle is not worth limiting and thinking about. And now a powerful and convenient loop construction appears in our algorithmic language, covering almost all necessary cases:

changing... from... step... to...
bye... repeat... times
cycle body
to ... kts,

where any of the underlined parts may be absent, and should not be present at the same time -
