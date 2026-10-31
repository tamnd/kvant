---
id: 2017-4-resheniya-zadach-m2446-m2449-f2453-f2456-2d2fd0f5
issue: kvant_2017_4
year: 2017
number: "4"
title: Solutions to problems M2446—M2449; F2453—F2456
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 19
page_last: 20
page_labels: 17-18
tag: X63G
lang: en
source: kvant_digital
extraction: native
content_sha256: 3f1fcc993f19648e22e08c0695f59f9c56f26f81e6ae6bd7990cf7274ad8f961
prompt_sha256: draft-1
translated_from: content/ru/2017/04/articles/03_resheniya-zadach-m2446-m2449-f2453-f2456-2d2fd0f5.md
source_content_sha256: f7d54f86097523fe51e5c58a0a8282b6630788551e022feab39b61612509146e
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 17⟧

PROBLEM WORKER

⟦figure⟧

Fig. 1

F2467. When heat of an amount Q = 600 J is added to a mixture of helium and nitrogen at a constant volume, the mixture heats up by $\Delta T_{1} = 15$ K. And if the same amount of heat is added to the same amount of the same mixture at constant pressure, then the temperature of the mixture will increase by $\Delta T_{2} = = 10$ K. Find the ratio of the number of nitrogen molecules to the number of helium molecules in the mixture.

F2468. In the electrical circuit shown in figure 2, all elements can be

⟦figure⟧

Fig. 2

considered ideal. At some point after the switch is closed, the thermal powers released by resistors with resistances R and 2R are equal to $P_{1} = 9$ W and $P_{2} = 2$ W, respectively. At what rate does the energy of the capacitor increase at this moment?

Solutions to problems M2446–M2449, F2453–F2456

M2446. a) Ten children were given 100 pasta on their plates. The guys didn’t want to eat and started playing. In one action, one of the children transfers one pasta from his plate to all the other children. After what is the least number of steps that everyone can have different amounts of pasta on their plates? b) The same question if there are 100 children and in one action one of the children transfers one pasta from his plate to some (whoever he wants) of the rest.

"QUANTA"

a) Answer. After 45 actions. Grade. Let's consider the difference in the number of macaroni in two children; let's say Vasya's number is subtracted from Petya's number. Petya's action will reduce this difference by 10, Vasya will increase it by 10, and the actions of other children do not change it. Therefore, this difference will be non-zero if and only if Petya and Vasya perform different numbers of actions. Therefore, in order for all children to have a different number of pasta, it is necessary to do at least 0 + + 1 + 2 + ... + 9 = 45 actions. Example. The first one will do one action, then the second one will do 2, the third one will do 3 actions, etc. up to the ninth inclusive. Each gave no more than 9 ◊ 9 = 81 pasta; his original 100 pasta was enough for this. b) Answer. After 50 actions. Example. Let's show how the quantities of pasta could become different after 50 actions. Let's number the children from 1 to 100. Let the kth child, where 1 £ k £ 50, transfer each pasta to the children with numbers from 51 to 50 + k. After all the actions, the children will have 99, 98, ..., 50, 150, 149, ..., 101 pasta, respectively. Grade. Let's assume that no more than 49 actions were taken. Let's consider all the children who did not give away pasta; there are at least 51 such children. For each of them, the number of pasta did not decrease compared to the initial one, but it could increase by no more than 49. This means that for each of these children the final number of pasta is in the range from 100 to 149 (50 possibilities), so there will be two of them with the same number of pasta. S. Dorichenko, N. Chernyatiev

M2447. For the solution to this problem, see the article by A. Zaslavsky “On the inscribed circle of a right triangle.”

M2448. There are 100 points marked on the line, and one more point is marked outside the line. Consider all triangles with vertices at these points. What is the largest number of them that can be isosceles?

⟦folio 18⟧

KVANT 2017/№4

Answer. 150. Let l be the given line, O the marked point outside it, H the base of the perpendicular dropped from O to l. Grade. Isosceles triangles can be of two types: those whose base lies on the line l, and those whose base does not. In the first case, the triangle must be symmetrical with respect to OH, so there are no more than 50 such triangles (for one vertex X of the base, the second is uniquely defined as symmetrical to point X with respect to OH). There can be no more than one triangle of the second type with a given base OA, since the vertex is determined by the intersection of l and the perpendicular bisector to OA. Therefore, there are no more than 100 triangles of the second type. Example. Let us draw rays from beam OH at an angle $18\infty$ (see figure). They will intersect l at points $A_{1}$ and $B_{1}$, let’s mark them. Let us put the segment $A_{1} A_{2} = A_{1} O$ on l in the other direction from $A_{1} B_{1}$, then the angles of triangle $OB_{1} A_{2}$ will be equal to $72\infty, 72\infty, 36\infty$. Then we set aside the segment $A_{2} A_{3} = A_{2} O$, …, segment $A_{49} A_{50} = A_{49} O$. Similarly, we mark the points $B_{2}$, … $, B_{50}$. 50 triangles $OA_{i} B_{i}$, 49 triangles $OA_{i} A_{i} +_{1}$ and $OB_{i} B_{i} +_{1}$, as well as triangles $OA_{1} B_{2}$ and $OB_{1} A_{2}$ will be isosceles. Another idea leading to the solution is to perform an inversion with center O. With the inversion, the line will turn into a circle, and we will get an inscribed 101-gon, one of the vertices of which is the point O. If X¢ and Y¢ are the images when the points X and Y are inverted, then the triangles OXY and OY ¢ X ¢ are similar. This means that the question of the problem is reformulated as follows: what is the largest number of isosceles triangles among triangles of the form OXY, where X and Y are the vertices of the 101-gon? One of the best examples

⟦column⟧

will be a regular 101-gon. E. Bakaev, I. Bogdanov

M2449*. There are a finite number of frogs sitting on a line at different integer points. During a turn, exactly one frog jumps 1 to the right, and the frogs must still be at different points. We calculated how many ways the frogs can make n moves (for some initial position of the frogs). Prove that if we allowed the same frogs to jump to the left, but forbade them to jump to the right, then there would be the same number of ways to make n moves.

Let's call a pattern a sequence of n commands “Left” or “Right”, where the kth command indicates in which direction one of the frogs should jump on the kth move. Let's prove a more general statement: the number of ways to make n moves from a given position (by executing commands) so that the frogs do not jump on each other does not depend on the pattern. (The problem statement is then a special case for a pattern consisting of only “Right” commands and a pattern consisting of only “Left” commands.) Lemma 1. Changing the last command of the pattern does not change the number of ways. Proof. Let's consider an arbitrary position before the last move. Each position is divided into groups of frogs sitting in a row. The number of ways to get the final position from it, regardless of the last command of the template, is equal to the number of groups, since from each group only one frog can jump to the left and one to the right. Lemma 2. Replacing two adjacent template commands does not change the number of ways. Proof. Let the two patterns differ only in moves k and k + 1, so that in the first pattern the kth team is “Left” and the (k + 1)th team is “Right”, and in the second pattern it’s the other way around: the kth team is “Right” and the (k + 1)th team is “Left”. Consider an arbitrary position A before the kth move. We will show how to compare each method of doing the following two:
