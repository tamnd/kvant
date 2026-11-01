---
id: 1978-5-litovchenko-luchshiy-variant-2f6b29fd
issue: kvant_1978_5
year: 1978
number: "5"
title: Best option
authors:
  - Литовченко З. М.
rubric: osnovnye-stati
page_first: 15
page_last: 17
page_labels: 13-15
tag: RAUP
lang: en
source: kvant_digital
extraction: vision
content_sha256: a1e235c252a497991282d31025880059b7f4d058bfc57b7f903f2aa05d59f563
prompt_sha256: draft-1
translated_from: content/ru/1978/05/articles/04_litovchenko-luchshiy-variant-2f6b29fd.md
source_content_sha256: 31c18f154e0a6455d98caddac01823003632cf5e80cd3df9cab9dc3c730a523f
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 13⟧

3. Litovchenko

Best option

Imagine that you are the director of a boarding school and you need to create a menu for the canteen for the week. Detailed drawing up of the menu, of course, is the job of the cook, but you need to make sure that not too much money is spent.

You know what products you can buy and their prices. But, besides prices, they have many other qualities, for example, calorie content, content of certain vitamins, etc. Therefore, in addition to prices, you need to consider quite a few conditions when purchasing products. If, moreover, there are a lot of products in the warehouse, then the problem becomes very confusing and difficult to solve without a computer. However, if the product and conditions are few, it is not difficult to cope with it.

Let's consider this example. Let the menu be almost completely drawn up, and you only need to make sure that it contains enough vitamins A and C, and there are cherries and apricots in the warehouse. One table with two fruits A (gw1 kg) and C (gw1 kg)

Cherries 3 150
Apricots 24 75

$$\begin{cases} 0,003x + 0,024y \geq 6, \\ 0,15x + 0,075y \geq 75, \\ x \geq 0, y \geq 0, \end{cases}$$

and $z = 0,25x + 0,3y$ would be minimal. On the plane $xOy$ it is easy to indicate the set of points $M$ satisfying the system (Fig. 1). It is called the solution polygon of the system. It is clear that the lines $z = 0,25x + 0,3y$ at different $z$ are parallel to the same direction, and with increment $z$ they move away from the origin. Therefore, we need to find one of the lines in this direction that has a common point with the polygon $M$ and is closest to the origin. It is easy to say that such a line should not intersect $M$ at internal points - then it would not be the “lowest” (Fig. 2). Therefore, it must pass through one of the vertices of the polygon. But then this point is the vertex $C$. So, you need to buy 400 kg of lice and 200 kg of apricots - the best option!

A task similar to the one analyzed is called a linear programming problem. In them, you need to find a line (in three-dimensional space - a plane, in multidimensional space - the so-called hyperplane), belonging to a bundle of parallel lines (planes, hyperplanes), which intersects with a certain polygon (polygon) and is located closest to the origin of coordinates. You can also give a purely algebraic form -

⟦folio 14⟧

Fig. 1.

Do you need to raise arctic foxes and foxes so that the average cost of one skin is minimal, if the cost of raising one fox is 45 rubles, and one arctic fox is 25 rubles?

Solution. Let $x$ be the number of foxes raised, and $y$ the number of arctic foxes. Then

$$\begin{cases}
4x + 5y \leq 80000 \\
\frac{1}{2}x + y \leq 10000 \\
x \geq 3000 \\
y \geq 6000.
\end{cases}$$

Average cost of one skin

$$z = \frac{45x + 25y}{x + y}.$$

Muliku: there is a system of linear inequalities

$$\begin{cases}
a_{11}x_1 + a_{12}x_2 + \dots + a_{1n}x_n \geq b_1, \\
a_{21}x_1 + a_{22}x_2 + \dots + a_{2n}x_n \geq b_2, \\
\dots \\
a_{k1}x_1 + a_{k2}x_2 + \dots + a_{kn}x_n \geq b_k
\end{cases}$$

and linear function $z = c_1x_1 + \dots + c_nx_n$. We need to find a solution to this system for which the value of the function $z$ is minimal. There have already been many articles about linear programming in «Kvant» (1971 - No. 3, p. 1 and No. 4, p. 1, 1974 - No. 7, p. 13, 1975 - No. 10, p. 17, 1976 - No. 7, p. 2, 1977 - No. 8, p. 29).

Let's solve one more problem: animal carriers raise arctic foxes and foxes; it has 10,000 cells, and two foxes or one arctic fox can live in one cell; According to the plan, it is necessary to grow at least 3,000 foxes and at least 6,000 arctic foxes; per day one fox is fed 4 food units, and an arctic fox - 5 units; in just one day it is allowed to eliminate no more than 80,000 feed units; How many

⟦folio 15⟧

Fig. 3.

the position of the value on the lines passing through the origin of coordinates. We need to find the one of these lines that intersects the polygon F and on which the value of the function z is minimal. Just as above, it is clear that this line should not contain the interior points of the polygon F. Therefore, it is enough to compare the lines OA and OB with each other. ANSWER: $x=3000$, and $y=8500$.

Note that in solving this problem we were lucky - we received a complete answer. After all, if the number of foxes or arctic foxes had not turned out to be integer, we would not have been able to use the answer. Moreover, if we did not receive a complete answer, we could not say anything about the correct answer. It turns out that you can choose the conditions of the problem in such a way that these answers will differ as much as possible.

In cases where the answer must be given in integers, we are dealing with integer programming problems. Solving such problems is much more difficult than solving the problem of this limitation.

In conclusion, an exercise for readers:

Two vessels must transfer cargo in accordance with Table 2.

It is known that the first ship can make no more than 5 trips, and the second - no more than 9. Draw up a transportation plan that would ensure a) maximum approximation;
b) the lowest cost of transporting one ton of cargo.

Amendments

In No. 3 of “Quaita” for 1978 on p. 11 in the eighth line from the top left column should read “M. P. Bronstein."
In No. 11 of “Quaita” for 1977 on p. 27 in the second line from the bottom in the right column should read “In 1928”.
