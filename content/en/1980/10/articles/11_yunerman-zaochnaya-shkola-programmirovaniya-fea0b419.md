---
id: 1980-10-yunerman-zaochnaya-shkola-programmirovaniya-fea0b419
issue: kvant_1980_10
year: 1980
number: "10"
title: Correspondence School of Programming
authors:
  - Юнерман Н. А.
rubric: raznoe
rubric_sub: Разное
page_first: 49
page_last: 51
page_labels: 47-49
tag: I2VE
lang: en
source: kvant_digital
extraction: vision
content_sha256: 565ddae7737327ee80d9be9dd607994f606e706ac994d2567f28f27822df4b0f
prompt_sha256: draft-1
translated_from: content/ru/1980/10/articles/11_yunerman-zaochnaya-shkola-programmirovaniya-fea0b419.md
source_content_sha256: b0b86e95690d1c1224b5ec152dce8a5530aa814cbe833d86059125db38a774cc
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 47⟧

Correspondence School of Programming
Lesson 10: Programming problems in the polar coordinate system

The material in this lesson is intended for students in grades 8-10. For elementary school students, this material is considered optional.

About the polar coordinate system
To determine the position of a point on a plane, there are various coordinate systems. Along with the system you know from school textbooks (it's called `dekartовой`), it uses the `полярную` coordinate system to solve many problems.

The polar coordinates of a point on a plane are two numbers that determine the position of this point relative to some fixed point $O$, called `полюсом`, and not

$$\rho = \sqrt{x^2 + y^2}, \quad \sin \varphi = \frac{y}{\sqrt{x^2 + y^2}},$$

during inverse transformation - according to the formulas

$$x = \varphi \cos \varphi, \quad y = \varphi \sin \varphi.$$

Archimedes spiral
Let us assume that we need to construct a curve that is described by a point moving with a constant speed $v$ along a ray rotating around the pole $O$ with a constant angular speed $\omega$. The equation of this curve in polar coordinates is

$$\rho = a\varphi,$$

where $a = \frac{v}{\omega}$. Curve (1) is known as `спирали Архимеда` (Fig. 3).

To construct an Archimedes spiral on a computer using the Shpar graphic system, it is convenient to use the POLAR procedure («Kvant», 1980, No. 1, p. 56).

Check for yourself that program (2), written in the Rapier language, figure Archimedes' spiral (the face of the cycle BYE is selected in the face $5 \times 2\pi$, providing p-

⟦folio 48⟧

pushing the heel of the spiral turns). Remember that when using the APPLICATION and BEAM procedures, the first diameter acts as the polar radius, and the second as the polar angle.
P(100,100); H(50.50);
.POLAR; 2->A; 0->FI;
3.1416->PI; P(0,0);
(2)
WHILE FI<10*PI::
FI+0.01->FI;
L(A*FI,FI)
ALL;
.END;
Task 10.1. Write a program to construct curves described by the equations:
a) $\varphi = a (1 + \cos \varphi)$ – cardioid,
b) $\varphi = \frac{a}{\varphi}$ is a hyperbolic spiral.

Family of "flowers"
On the second page of the cover, families of “flowers” ​​made on a computer figure are reproduced. The equation of this family of curves in polar coordinates has the form
$\varphi = A \sin B \varphi$.
(3)

Task 10.2.
1) What determines the coefficient $A$?
2) In what order does the individual petals appear?
3) How will figure change if in equation (3) we replace sin Vf by |sin Vf|?

4) How is the number of petals related to the value of coefficient B?
Consider separately the case when B is even and when B is odd.
5) How to organize a loop so that:
a) draw the “flowers” ​​in the order in which they are shown on the cover (restore the program)?
b) depict in the family of “flowers” ​​only those that have nonhuman values ​​of parameter B?
b) draw a family of “flowers” ​​with only integer values ​​of B?
(There is no need to program captions under the pictures.)

Regular hexagon
In the Programming Olympiad («Kvant», 1980, No. 3), two problems were proposed that are easier to solve if you use a polar coordinate system.
The first of them (problem 3) is formulated as follows: create a program to depict a regular 16-gon in which all diagonals are drawn that do not pass through the center.
Consider a polar coordinate system with a pole at the center of the polygon $O$ and a polar axis $OX$ directed along the ray $OA_{16}$ (Fig. 4).
Let's find the polar coordinates of the vertices of this polygon. The first coordinate (polar dimension)

⟦folio 49⟧

dius) for all vertices is the same and equal to the radius of the circumscribed circle R, and the second coordinate (polar angle) is calculated by the formula $\varphi_K = (\pi/8)*K$, where K is the number of the vertex.

To draw the required figure, you need to connect the vertex with number N (1≤N<16) to all vertices whose numbers are greater than N, except for the vertex with number (N+8) (after all, it is the segment connecting the vertices with numbers N and N+8 that passes through the center). If we connected each vertex N with all other vertices, then each segment would be drawn twice.

Giving the parameter R different values, we will obtain similar regular 16-gons.

Procedure parameters can be any arithmetic expressions. For example, in the APPROACH and BEAM procedures, the coordinates of the corresponding point are pre-calculated using expressions. In the FRAME and BEGIN procedures, expressions are used as parameters to ensure that the polygon is positioned correctly, strictly in the middle of the drawing field. According to the DIAG procedure with parameter K, vertex number N will be connected to vertex number K. PERCENT DIAG K;
P(R, N*PI/8);
L(R, K*PI/8);
KSC;
The final program looks like:
50—>R;
P(2*R+50,2*R+50);
H(R+25, R+25); 3.1416—>PI;
.POLAR; 1—>N;
BYE N<16::
1+N—>K;
BYE K<16::
IF K/=N+8 TO
DIAG(K); K+1—>K
ALL;
N+1—>N
ALL;
.END;
The result of this program is figure 5.

Task 10.3. Write a procedure that draws the correct N-wall.
