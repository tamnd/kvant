---
id: 1980-2-zvenigorodskiy-zaochnaya-shkola-programmirovaniya-c37b497b
issue: kvant_1980_2
year: 1980
number: "2"
title: Correspondence School of Programming
authors:
  - Звенигородский Г. А.
rubric: raznoe
rubric_sub: Разное
page_first: 55
page_last: 56
page_labels: 53-54
tag: V4AC
lang: en
source: kvant_digital
extraction: vision
content_sha256: 23066f5de1cc310f0f5245b4d97cdb25a4db22406867d09a5e3bafec94f9e34e
prompt_sha256: draft-1
translated_from: content/ru/1980/02/articles/20_zvenigorodskiy-zaochnaya-shkola-programmirovaniya-c37b497b.md
source_content_sha256: 704ad5af7b1d51101a8bc860e7fd70823976bc0192acca7be3a34da5ec9b5293
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 53⟧

Correspondence School of Programming

Lesson 6: Description and call of procedures on Rapier

In this lesson we continue our study of the educational and production programming language Rapier, which began in the fifth lesson («Kvant», No. 1).

The description of the procedure in Rapier is defined by the following diagram:

The header follows statements separated by semicolons.

Here is an example of a description of the procedure on Rapier:

PERC SELECT A B; A+B->C; A*B->D;
IF C>D THEN C->D ELSE D->C ALL;
KSC;

There are two ways to call a procedure in Rapier. Using the first method, you should write the name of the procedure as the next representation and put curly brackets after it. If the procedure has parameters, then their values ​​are listed separated by commas inside these brackets, as in Robik, for example:

SELECT(10,X+5);

If there are no parameters, parentheses are still required in this calling method:

RESET ( );

If a procedure has at most one parameter, it can be called in the second way: by placing a dot in front of the procedure name. The value of the parameter, if any, is indicated before the dot:

RESET; 5. CIRCLE;

The description begins with the word PERC (instead of the words REMEMBER PROCEDURE in Robik), followed by the name of the procedure. Then the parameter names are listed, if necessary. They are separated from each other by spaces; The parentheses and commas used in Robik are not needed here.

This may be followed by an arrow =>, after which another name is indicated - the so-called result name. In this lesson we will look at procedures that do not use a result name. Therefore, we will postpone the analysis of this construction until the next lesson.

The word PROC, the procedure name, parameters and result name form the so-called procedure header. After

Rapier provides a large number of standard procedures that can be called in any program. These include, in particular, the PRINT procedure, which can have any number of parameters. As a result of using this procedure, the values ​​of all parameters will be printed on a new line, close to each other (just like in the PRINT instruction in the Robik language). All procedures of the Shpag graphic system, described in the article by A. Salikhova and N. Sokolova in the previous issue of the magazine, are also standard.

Let's look at some examples:

1°. Suppose we need to write a program on Rapier using

⟦folio 54⟧

Based on the procedures of the Speech system, this is the robot to illustrate:

CODE 211500000055 SMOG 61M5 SHEET 7
DATE 06.22.79 63 TIME 19.49.31

This can, of course, be done using rays and leads alone. However, in this case the program will turn out to be quite large. It can be significantly shortened if we replace that with figure the same figure is repeated many times - a rectangle. Therefore, it is enough to describe the DIRECT procedures once and then draw any desired rectangle. The procedure below has four parameters: X, Y, B and D, X and Y are the coordinates of the lower left corner, B is the height and D is the length of the rectangle:

PERC DIRECT X Y IN D;
P(X;Y); L(X+D,Y); L(X+D; Y+B);
L(X,Y+B); L(X,Y); KSC;

Now the program that executes figure can be written very simply:
P(50.50); DIRECT(10,10,30,30);
DIRECT(20,15,5,10); DIRECT(23,23,4,4);
DIRECT(15,30,5,7); DIRECT(28,30,5,7);
DIRECT(17,31,3,3); DIRECT(30,31,3,3);
.END;

2°. The next task is to fill the size 100 by 100 mm with a rectangular grid with a step of 5 mm vertically and horizontally (such a grid can serve, for example, as a coordinate grid). It's convenient to use a loop here:
P(100,100); 5—>A; WHILE A=<100::
P(A,0); L(A,100); P(0,A); L(100,A),
A+5—>A ALL; .END;

3°. Another example of using a loop is to print the multiplication table:
2—>A; 2—>B;
PRINT('MULTIPLICATION TABLE'),
WHILE A=<10:: WHILE B=<10::
