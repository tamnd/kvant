---
id: 1987-12-vozvraschayas-k-napechatannomu-67cb497c
issue: kvant_1987_12
year: 1987
number: "12"
title: Returning to print
rubric: smes
page_first: 44
page_last: 44
page_labels: "42"
tag: TB2U
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6afb678b25ee6961fe9cd776ca5b3dc4deb197c8f947c1c821ca337dd22b1787
prompt_sha256: draft-1
translated_from: content/ru/1987/12/articles/11_vozvraschayas-k-napechatannomu-67cb497c.md
source_content_sha256: 67fa16ebe7ef1f3c2612077dfde479ae206b4f2efc5c665d94c93a2bfe5bf085
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 42⟧

THIS is the name parameters
...
RETURN α
END
Here “name” is the name of the function, “parameters” is a list (possibly empty) of operand parameters, α is an expression.

Let us illustrate the use of functions created by the programmer when drawing a flower with petals in the form of right triangles with legs equal to A and B (Fig. 4). First, we create a procedure that draws the stem, organizes the drawing of four petals, and returns the Turtle to its original position:

THIS IS A FLOWER :A :B
(*DRAW STEVEL*)
DRAW FORWARD 3 * :A LEFT 65
FORWARD 2 * :5 LEFT 65
(*DRAW A FLOWER*)
REPEAT 4 PETAL :A :B RIGHT 90
(*RETURN TO STARTING POSITION*)
DO NOT DRAW TO THE LEFT :65 BACK 2 * :A
RIGHT 65 BACK 3 * :A
END
Here and in the future we will use the brackets “(*” and “*” to write comments - recorded in the program, but not processed by the machine message. The petal draws the games ended in a draw, then the two sections scored equal points. The statement and solution will be correct if it is understood that all sections played the same number of games, in part - all played with each other. (Without this, the first step of the solution is to go to the system scoring, in which 1 is given for a win, 0 for a draw, and -1 for a loss, does not allow one to correctly judge the initial amount of points, as can be seen from the following example: four sections A, B, B, G were played by Γ, B and Γ did not play among themselves, the remaining games ended in a draw.)

Returning to the direction

As many readers have learned, clarification should be made to the formulation of problem M1047 (the solution of which was published in «Kvant» No. 10). The problem required proving that if more than 3/4 of the games played in Turin ended in a draw, then the remaining two sections scored equally points. The statement and solution will be correct if it is understood that all sections played the same amount of games, in part - all played with each other. (Without this, the first step of the solution - the transition to a scoring system in which 1 is given for a win, 0 for a draw, and -1 for a loss - does not allow one to correctly judge the initial amount of points, as can be seen from the following example: four sections A, B, B, G were played by Γ, B and Γ did not play among themselves, the remaining games ended in a draw.)
