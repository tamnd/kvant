---
id: 1982-10-pogosyants-vokrug-evm-023d5e59
issue: kvant_1982_10
year: 1982
number: "10"
title: Around the computer
authors:
  - Погосянц Э.
rubric: kvant-ulybaetsya
rubric_sub: «Квант» улыбается
page_first: 57
page_last: 59
page_labels: 55, 57
tag: GHLZ
lang: en
source: kvant_digital
extraction: vision
content_sha256: fa8e2ca60d59235b9a90c8e528b4ef4439457db792441dfe4d5b87180743e6d5
prompt_sha256: draft-1
translated_from: content/ru/1982/10/articles/13_pogosyants-vokrug-evm-023d5e59.md
source_content_sha256: 1f503de6edaf45f7330dded9db56b5ecd0ef60f8e9ad18e7c89149ece3eb4aed
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 55⟧

and then “comes out.”

for j: =1 to k do f[j]:=1;
for i: =k+1 to n do
begin s: =0;
for j: =1 to k-1 do s: =s+f[j];
f[k+1]:=s*f[k];
writeln(f[k+1]);
for j: =1 to k do f[j]:=f[j+1];
end;

Here: 1 - initial assignment, 2 - main loop, 3 - calculation of the next value, 4 - use of the value, 5 - reassignment.
(The variable s was introduced to increase the speed of the program: instead of s it was chosen to use f[k+1], but recall that indexing is a very labor-intensive operation for a computer.)

Control job

1.1. Given x. Calculate the approximate value of e^x using the formula
$$e^x \approx 1+x + \frac{x^2}{2!} + \frac{x^3}{3!} + \dots + \frac{x^n}{n!}.$$
Carry out calculations until the next term becomes less than ε.

1.2. Calculate the values ​​of the k-th row of the Pascal trigon (see the article by A. Bendukidze in this issue). The result should be written to an array of length k; two-dimensional arrays and auxiliary arrays are not used.

Programs must be completed in full (not just the body of the program) and sent within two weeks after receiving the journal. Choose the length and type of arrays derivatively.

Preparatory tasks for lesson 2*)

1. Find the first element in the given array (counting the word to the right) that has the given value.

2. Find the last element in a given array that has a given value (the array is scanned from beginning to end, and not vice versa).

3. Find the mth element in the given array that has the given value.

In all tasks, you need to get the index of the desired element if it is in the array, and zero if it is not.

Questions: What is common in the conditions and solutions to problems? Why does it make sense to solve problem 2 as an independent problem, and not look for the first element from the end?

L. Sternberg

*) There is no need to send solutions to these problems!

«Kvant» smiles

Around the computer

First, the man made the machine work for himself, and now he wants it to think for him.

E. Pozosyants Maybe this is the case?

She knew too much!

Enough! I have a lunch break.

If I make a mistake again, I’ll replace it with a human!

⟦folio 57⟧

With this episode from the book by V. Ya. Frenkel and B. E. Yavelov “Eishstein - the Inventor” (M., “Nauka”, 1981) one can find a solution to it - the episode evokes the same feeling as the whole book as a whole: surprise. And the same desire that I felt to immediately get acquainted with the book: to find out - what to do?

The name of Albert Eischstein, one of the most remarkable scientists who ever lived, the great physicist of our century, is familiar in everything without exception. Further, people who are very far from science know that Eischstein was the creator of the theory of relativity, although they may have only vague ideas about the theory itself. Those interested in physics and physicists have the opportunity to learn about the magnitude of Eischstein's physical genius and his unusually attractive personality from the numerous books and articles devoted to the life and work of the scientist.

But we can safely say that a practical person has not heard of Eischstein - the inventor of the refrigerator (and not just one, but several types); about Eischstein - the inventor of the camera used on filming in Hollywood; about Eischstein - inventor of the magnetostrictive loudspeaker; magnetohydridydynamic pumps for pumping liquid metals; induction hydrodynamic suspension, which is widely used in metallurgy today; about Eischstein, who developed a method for determining pore sizes in medical filters. About Eischstein, an experimenter who put forward original ideas for experiments.

There was no way to find out about this. Book by V. Ya. Frenkel and B. E. Yavelov -

New books

(For the beginning, see p. 43)

3. A. G. Kurosh. Alebraic equations of arbitrary degrees. 3rd edition (I quarter). Price 10 k.

The brochure is based on a lecture given by the author, a famous mathematician, for participants in the Moscow Mathematical Olympiad. The book talks about alebraic equations of arbitrary degrees, the fundamental theorem of algebra, methods for solving some algebraic equations, and the solvability of equations in radials. As a rule, the results are presented without proof, but are illustrated with interesting examples.

Library «Kvant»
1. E. Ya. Gik Chess and mathematics (I quarter). Price 40 k.

The author of the book is a mathematician and chess player, who runs the chess page of our magazine. In a popular form, he talks about the various connections between mathematics and chess.

The book discusses computer equations, the ELo coefficient, the mathematics of chess players, and the necessary geometry of a chessboard.

2. V. M. Tikhomirov. Stories about highs and lows (Q4). Price 40 k.

The book talks about the problems of maximum and minimum, which have been hidden in the depths since ancient times. First, the author tells the classical problems that were solved by Euclid, Archimedes, Apollonius, Fermat, Kepler, Newton, Leibniz.

Then he talks about the deep connections of extreme problems with problems of natural significance, economics, space technology and modern methods for solving such problems.

3. I. F. Shargin. Geometry assignments: Stereometry (III quarter). Price 40 k.

The book contains about 350 problems in geometry.

The first section contains tasks of a computational nature. Here are some solid geometry theorems that apply directly to the chocolate course.

The second section contains geometric inequalities, problems on geometric loci of points, elements of spherical geometry, etc.

A. Yeorov
