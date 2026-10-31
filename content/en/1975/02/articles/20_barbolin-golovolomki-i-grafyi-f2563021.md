---
id: 1975-2-barbolin-golovolomki-i-grafyi-f2563021
issue: kvant_1975_2
year: 1975
number: "2"
title: Puzzles and graphs
authors:
  - Барболин М. П.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 61
page_last: 62
page_labels: 59-60
tag: U62Z
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0778915e3be872e24d2d163c5eb8e86fd3b89e3a97b84031ea250bb153f07f02
prompt_sha256: draft-1
translated_from: content/ru/1975/02/articles/20_barbolin-golovolomki-i-grafyi-f2563021.md
source_content_sha256: 800d68a767e403ecd05f4d138c2232ec4eb25e90b7894d5a949ce18adaf493cb
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 59⟧

Puzzles and graphs

M.P. Barbolin

Everyone knows the tasks of pouring and crossing; divisions. They have become firmly established in the practice of mathematical circles, Quizzes, mathematical evenings, etc. Typically, such problems are solved “in the mind” and require considerable wit and ingenuity. Finding a solution to such a problem in any one way is not difficult. It is much more difficult to indicate the shortest way or all possible solutions.

Answers to these questions can be easily obtained using graphic diagrams consisting of dots connected by arrows. Such schemes are called graphs.

Problem 1. Two targets have a full jug of milk of 8 liters, as well as two empty jugs of 5 and 3 liters. How can they divide the milk equally?

To solve the problem, we will use graphs. Let's assign a number to each jug: an 8-liter jug ​​is No. 1, a 5-liter jug ​​is No. 2, a 3-liter jug ​​is No. 3. Let's consider possible options for filling jugs resulting from one transfusion.

At the initial moment, jug No. 1 is full, and No. 2 and No. 3 are empty.

Let us represent this state as a point (8.0.0.) (Fig. 1). Now from jug No. 1 you can pour five liters into jug No. 2 or three liters into jug No. 3. The result is two new options for filling jugs (3.5.0.) and (5.0.3.). We will also depict them with dots, and with arrows we will show that they are obtained from the original version (8.0.0.) (Fig. 2). Other options cannot be obtained with one transfusion.

We do the second transfusion. To make sure you don't miss any opportunities, let's look at the pitchers in numerical order. We take option (3.5.0.) (in jug No. 1 - 3 liters, in jug No. 2 - 5 liters, jug No. 3 - empty). From jug No. 1 you can only pour milk into No. 3, resulting in a new filling option: (0.5.3.). On the graph, from point (3.5.0.) we draw an arrow to point (0.5.3.) (Fig. 3). From jug No. 2 you can pour milk into No. 1 or No. 3 (transferring into two jugs is considered two consecutive transfusions!), but pouring into jug No. 1 does not give a new option (the resulting options (8.0.0.) are already being considered), so transfusion is not advisable. Transferring milk from No. 2 to No. 3, we get a new option (3.2.3.), we show this on the graph with a point (3.2.3.) (Fig. 3). The jug with number three is empty, so it can be ignored.

Next we move on to option (5.0.3.). Reasoning similarly to the previous one, we get another option

⟦folio 60⟧

(5.3.0.) and accordingly the graph is reachable.

It is now clear that the solution process involves “growing” a graph tree. Continuing the reasoning, proceed to the graph depicted in figure 4.

It shows two chains coming from the point (8.0.0.) and ending with the desired option (4.4.0.). They correspond to two different ways

Fig. 1
(8.0.0.)
(3.5.0.) (5.0.3.)

Fig. 2.
(8.0.0.)
(3.5.0.) (5.0.3.)
(0.5.3.) (3.2.3.) (5.3.0.)

Fig. 3.
(8.0.0.)
(3.5.0.) (5.0.3.)
(0.5.3.) (3.2.3.) (5.3.0.)
(6.2.0.) (2.3.3.)
(6.0.2.) (2.5.1.)
(1.5.2.) (7.0.1.)
(1.4.3.) (7.1.0.)
(4.4.0.) (4.1.3.)

Fig. 4.
(4.4.0.)

desired spill:
Method I: (8.0.0.) → (3.5.0.) → (3.2.3.) → (6.2.0.)→ (6.0.2.)→ (1.5.2.)→ (1.4.3.)→ (4.4.0.).
Method II: (8.0.0.) → (5.0.3.) → (5.3.0.)→ (2.3.3.)→ (2.5.1.)→ (7.0.1.)→ (7.1.0.)→ (4.1.3.)→ (4.4.0.)

Task 2. The carriers (P) need to transport a wolf (B), a goat (K) and a bag of cabbage (M) across the river. The boat is so small that in addition to the carrier, only one of the objects can be taken. In addition, cabbage cannot be left with a goat, and a goat cannot be left with a wolf. How to make the crossing?

For the purpose of definition, let everyone be on the left bank at the initial moment (L.B.). Let us depict the initial situation as a point and denote it as follows: (V.K.M.P. || —) (Fig. 5). On the first flight, the carrier can only take a goat (since it cannot be left with either the wolf or the cabbage). As a result, we obtain a new situation: (V.M. || K.P.). (the wolf and the bag are on the left bank, the goat and the carrier are on the right). Let's depict it as a point and draw an arrow to it -

Fig. 5.
