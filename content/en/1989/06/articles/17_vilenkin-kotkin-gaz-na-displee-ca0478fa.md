---
id: 1989-6-vilenkin-kotkin-gaz-na-displee-ca0478fa
issue: kvant_1989_6
year: 1989
number: "6"
title: Gas on display
authors:
  - Виленкин А. Н.
  - Коткин Г. Л.
rubric: raznoe
rubric_sub: Разное
page_first: 63
page_last: 63
page_labels: "61"
tag: M9G4
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7205c7b9b112b7581fe941beec23a2f780f1c4942ac0aa33c8d5e5954811fa11
prompt_sha256: draft-1
translated_from: content/ru/1989/06/articles/17_vilenkin-kotkin-gaz-na-displee-ca0478fa.md
source_content_sha256: 7342104db835310ce43043f9ad1434a6b72978cb0bf071476ba5275061a33a61
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 61⟧

Gas on display

A. N. VILENKIN,
Candidate of Physical and Mathematical Sciences
G. L. KOTKIN

This note, an additional article “Gas of large ore balls” (see p. 2), tells how to create a program that simulates the movement of several large ore balls. The description is presented in such a form that readers can trust the program in a specific programming language.

The “Gas” program (that’s what we’ll call it) is reasonably divided into seven blocks: description of variables and data preparation, initial launch, screen preparation, calculation of a large ore impact, calculation of new coordinates, displaying information on the screen, model control unit.

Description of variables and data preparation. To describe the system, the following variables will be used: N - number of balls; a is the radius of each ball; T — time counter (at the initial moment T=∅), T∘ — time step; A1 and A2 are the screen boundaries. The values ​​of these variables are best set in the program so that they can be changed (by editing the program), but do not have to be entered for each experiment.

The states of the balls are described by 4 variables for each ball: the x and y coordinates of the center of the ball and the velocity components vx and vy. All these variables should be described as one array R(4, N), because the calculation formulas for them are the same. For the old ball positions you will need an RS(2, N) array.

Initial launch. This block consists of requesting the initial values ​​of the coordinates of the centers and components of the balls' velocities. Here you can set T∘ - the “step” of the process.

Screen preparation. A display in high-resolution graphics mode is a portion of the xy coordinate plane consisting of “points” with integer coordinates contained within certain limits (for example, 1≤x≤256, 1≤y≤192). The screen boundaries are specified by the variables A1 and A2, but care must be taken to avoid the balls not only falling outside these boundaries, but also not falling into the images of the table boundaries. So in this block you need to switch the display to high-resolution mode, for example, draw the boundaries of the table and calculate the boundaries of the positions of the centers of the balls (such as G1=1+a+1, G2=A1-a-1).

Calculation of the larger impact. In this block, it is necessary to calculate the moment TC of the first table, describe the type of table in the form of switch value K and the numbers of table balls in the form of values ​​N1, N2, so that the result of the block is as follows: the first table is table N1, with K=1 - with a horizontal wall, K=2 - with a vertical wall, K=3 - with ball N2.

In practice, you must first set a large TC and N1=∅, N2=∅, K=∅. Then in a loop (by ball numbers)
