---
id: 1973-1-kolotov-ob-odnom-razbienii-pryamougolnika-a459b3f6
issue: kvant_1973_1
year: 1973
number: "1"
title: About one division of a rectangle
authors:
  - Колотов А. Т.
rubric: osnovnye-stati
page_first: 16
page_last: 18
page_labels: 14-16
tag: SUJ7
lang: en
source: kvant_digital
extraction: vision
content_sha256: 3a5192573c990d8b0f5731ce316e7f88bd064227b97339e319610075254e8fd9
prompt_sha256: draft-1
translated_from: content/ru/1973/01/articles/06_kolotov-ob-odnom-razbienii-pryamougolnika-a459b3f6.md
source_content_sha256: d1bdbad7a42fea910176b979d976bc5fee1ea502f6259f597040644568da47a6
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 14⟧

About one partition of a rectangle

A. T. Kolomov

This note solves problem M144. Find the necessary and sufficiently conditional conditions that the numbers a, b, α, β must satisfy so that the rectangle a×b can be cut into several rectangles α×β.

For example, is it possible to cut a 50x60 rectangle into rectangles with dimensions:
a) 20×15; b) 5×8; c) 6.25×15;
e) (2−√2)×(2+√2).

The solution generalizes the solution to Problem 1 from Soifer’s article “Checkered boards and polymnos” («Kvant» No. 11, 1972).

The complete solution to problem M144 is given by the following theorem. In order for a rectangle a×b to be cut into rectangles α×β, it is necessary and sufficient that the following conditions be simultaneously satisfied:

1) each of the numbers α and β must be an integer less than at least one of the numbers a, b.

3) Each of the numbers a and b must be represented in the form mα + nβ, where m and n are non-negative numbers α and β.

Proof. Let's denote the large rectangle by R, and the small one by p.

There is enough to eat. If a=nα, b=mβ (m and n are natural numbers), then by dividing one of the sides of the rectangle R into m, and the adjacent sides into n equal parts, and then drawing straight lines parallel to the sides of R through the division points, we will thereby divide it into rectangles equal to p (Fig. 1).

If a=n α=mβ, then by virtue of the second condition b admits the representation b=kα+lβ, where k and l can be considered positive integers. Then, dividing the rectangle R into two rectangles P and Q with dimensions a×kα and a×lβ, respectively, we reduce this case to the one already considered (Fig. 2).

The necessity of the second condition is obvious. Let us prove the necessity of the first condition. There are two possible cases:

1. The numbers α and β consist of us. Then, without loss of generality, we can consider the numbers α, β, a and b to be integers, since this can always be achieved

Fig. 1.

choosing the appropriate scale units. Let us now assume that our statement is not true, and to define a desert a, b are not divisible by α. Having divided the rectangle R into unit squares, we carry out the following correct coloring of the resulting grid in α different colors (a coloring is called correct if any adjacent α squares at the vertex

⟦folio 15⟧

ticks or horizontals represent all α colors). Namely, we will color the cells located on the diagonal and the cells from top to bottom and from left to right with the same color, and we will choose the colors so that any two such diagonals, between which α-1 others are located, are colored the same. It is easy to see that if we deign to carry out the required partition of the rectangle R, then each of the given α colors will be represented by the same number of unit squares in any of the resulting rectangles, and therefore, the number of squares in the entire rectangle R, painted in a given color, does not depend on the choice of this color. (On figure 3 the correct 4-color coloring is presented).

Fig. 3.

Let $r_a$ and $r_b$ be the remainders obtained by dividing a and b by α. Divide the rectangle R into three rectangles A, B and C of dimensions $r_a \times r_b$, $(a - r_a) \times r_b$ and $a \times (b - r_b)$ respectively so that A occupies the upper left corner of the original rectangle R, B is adjacent to A, and C is located to the right of A and B (Fig. 4).

Fig. 4.

Fig. 5.

In rectangle B, each color is represented by the same number of squares, since α—r_a is divided by α. The same statement is also true for rectangle C. Therefore, by virtue of the previous remark, it must also hold for A.

Let's look at rectangle A more closely. We are interested in three diagonals located in it, one of which goes from the left upper corner of A and is colored in the $i_1$th color, and the other two are direct to it from both sides and are colored in the $i_2$th and $i_\alpha$th colors. Obviously, each of the named colors can occur in rectangle A only on the indicated diagonals. But then, if $r_a \leqslant r_b$, then the number of cells of the $i_\alpha$ color is one less than the number of cells of the $i_1$ color (Fig. 5), if $r_a > r_b$, then the number of cells of the $i_2$ color is one less than the number of cells of the $i_1$ color (Fig. 6). In both cases we come to a contradiction.

2. Let α and β be incommensurable, and to define α<β.

If any two rectangles of the partition are oriented identically with respect to the sides of R (in other words, more of the sides of these rectangles are parallel to the same side of the original rectangle), then the theorem is obvious.

Let us show that the case with different orientations of rectangles p is impossible. Assuming the opposite,

⟦folio 16⟧

It can be assumed without loss of generality that rectangles $\rho$ of various orientations are already applied to the base of the rectangle $R$. Divide the layer of rectangles $\rho$, direct coefficients $R$, into fragments of identically oriented rectangles so that the rectangles of two adjacent fragments have different orientations.

Fig. 6.

Since any two adjacent fragments have different heights, the rectangles of any “low” fragment lie at the bottom of the “well” (Fig. 7), the walls of which are formed by the sides of adjacent fragments (one of the walls, however, can also be the side side of the rectangle $R$).

Due to the incommensurability of $\alpha$ and $\beta$ each, such a well must be filled with rectangles of the same orientation as the rectangles of the fragment located at its bottom. As soon as this filling occurs, then immediately each of the “high” fragments finds itself at the bottom of the “well”, the walls of which will be formed by the lateral sides of neighboring complexes, consisting of rectangles of a different orientation, filled with the previous “co-

Fig. 7.

boats." After filling the new formed wells, we will immediately have a new one (Fig. 8) and so on.

Therefore, at each step of the filling area, the rectangles will be bounded from above by a broken line that has at least one depression, and, therefore, in this case, filling all $R$ rectangles $\rho$ is impossible.

Thus, the theorem is completely proven.

Now let's see which of the rectangles listed in the conditions can be divided into rectangle $50 \times 60$.

Fig. 8.

a) $20 \times 15$ can be divided into rectangles (by theorem).

b) $5 \times 8$ cannot be divided into rectangles, since neither 50 nor 60 is divisible by 8.

b) Partitioning into rectangles $6,25 \times 15$ is very indo (both numbers 50/6.25 and 60/15 are integers).

d) $(2 + \sqrt{2}) \times (2 - \sqrt{2})$ cannot be divided into rectangles (condition (1) of the theorem is not satisfied).

Try to give a primer yourself for such a case when in the theorem conditions (1) are satisfied, but conditions (2) are not.
