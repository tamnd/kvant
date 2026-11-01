---
id: 1983-3-shternberg-standartnyie-priemyi-programmirovaniya-4b94d1b8
issue: kvant_1983_3
year: 1983
number: "3"
title: Standard Programming Techniques
authors:
  - Штернберг Л. Ф.
rubric: raznoe
rubric_sub: Разное
page_first: 57
page_last: 57
page_labels: "55"
tag: 35JZ
lang: en
source: kvant_digital
extraction: vision
content_sha256: 3fec6f6a9f72f08e9b03c7c91630f0ea88bfe176265e9212fe6202f3c354179a
prompt_sha256: draft-1
translated_from: content/ru/1983/03/articles/16_shternberg-standartnyie-priemyi-programmirovaniya-4b94d1b8.md
source_content_sha256: e5c3b7b5dd75863ecc0a3719b81e22d8d1a30d6f400bdb893a097691be2d210b
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 55⟧

Traditional programming techniques

Lesson 6. Configuring the program using parameters

The following program is considered:

```python
program primer(input, output);
var a: array [1..100] of real;
i: integer; s: real;
begin for i:=1 to 100 read(a[i]);
s:=0;
for i:=1 to 100 do s:=s+a[i];
s:=s/100; writeln(s);
```

Promotion of the program
1. What does this part of the program do?
2. Is she correct? Is she graceful?
3. Do you see any defects in this program?
4. How should the program be modified so that it produces an array of 115 elements?

* * *

Imagine this dialogue between airplane passengers and a flight attendant:
- Stewardess! Why doesn't it fly? WHAT are we waiting for?
— You see, our plane is designed for 100 seats, but only 98 passengers came. The design of the plane is such that it cannot take off with empty seats, so you will have to wait until latecomers arrive or someone wants to fly on a shimmy flight.
- What if we put mannequins in chairs? Shall we take off then?
- Yes, sure.
“Tell me,” the second passenger embroiders, “what if we just remove the empty seats?”
“That’s possible,” the flight attendant answers, and passengers rush to unscrew their seats or look for mannequins.

Of course, such a dialogue is absurd, and one cannot encounter such a situation at Aeroflot. But look at the above program: can it take off with 98 array elements on board? No!! But why? After all, there is nothing in the algorithm that would require exactly 100 elements (as, say, the division operation requires exactly two numbers: the dividend and the divisor). Regarding such programs, it often comes with beginner programs like:

— What will you do if you need to form not 100, but 98 elements?
— I’ll change “100” to “98” here, here and here. (That is, I dismantle the chairs).
- Well, will you change half of the program statements? And besides, you forgot to change it here too. And where is the guarantee that nothing else needs to be changed?
- Well... then I’ll add an empty punched card to the original data: zeros will be entered from it and everything will be fine. (I’ll put mannequins in chairs).
— And if you don’t need to add the elements, is it possible?
“Then I’ll enter the units.”
- And if you need to fold it, it’s possible?
— ??!

So, we have partially answered questions 2 and 3. The program, of course, is correct from the form’s point of view, but it can hardly be called elegant, since it has a major defect: for no apparent reason, the program is strictly tailored to the size of the array being formed.

The remaining questions are difficult to answer. We can say that the program calculates the arithmetic mean, then to process an array of 115 elements it is necessary to replace “100” with “115” in four places; but we can say that it calculates the sum and divides it by 100 (translating, for example, the result from percentages into common fractions), then the replacements must be arbitrary only in three places. Three defects are immediately visible here: firstly, there are no comments appearing in the program, secondly, “silent” numerical constants are scattered throughout the program and it is unclear whether some of them coincide by chance, and thirdly, the program is adjusted to the size of the array in many places and many corrections must be made to change the size.

Let's introduce minor changes to our program:

```python
program primer(input, output);
const n=100; m=100; {n — размер массива}
var a:array [1..n] of real
i:integer; s:real;
begin for i:=1 to n do read(a[i]);
s:=0;
for i:=1 to n do s:=s+a[i];
s:=s/m; writeln(s);
```

Promotion of the program
Telegra and without comment it became clear that the program does not calculate the arithmetic mean.

To change the size of the array, you need to change one line (regardless of the size of the program), and you must look for it: it is located at the beginning of the program.

Thus, our program has become easily customizable: you need to change the settings block, placed at the beginning of the program and having a small size, does not depend on the size of the program. The settings block contains the values ​​of all program parameters. This method of program settings is called static settings: the program is configured during the process of entering into the computer (more precisely, during trans-
