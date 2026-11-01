---
id: 1980-4-aleksandrov-izmelchayuschiesya-uzoryi-f7730305
issue: kvant_1980_4
year: 1980
number: "4"
title: Shredding patterns
authors:
  - Александров С.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 28
page_last: 30
page_labels: 26-28
tag: VKMS
lang: en
source: kvant_digital
extraction: vision
content_sha256: 63a1721e4aac9230c4732e8403549bfeaa4cc047bde8293cb5e3966a823c8164
prompt_sha256: draft-1
translated_from: content/ru/1980/04/articles/08_aleksandrov-izmelchayuschiesya-uzoryi-f7730305.md
source_content_sha256: 85ce10d3ca5120f5f2268037ecd5d23a3f70ed6701bfbe525745e3abdaa820dd
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 26⟧

Chopping patterns

Take a closer look at the first page of the cover - on it, in a regular pentagon, there is an endless set of five-pointed stars, shrinking towards its sides. The goal of the next math club lesson is to understand this beautiful structure and understand how similar patterns can be built.

Star Square Problem

The pattern on the cover is obtained as follows:

Let's consider a regular pentagon in which all 5 diagonals are drawn (the central “black” pentagon on the cover). The ends of the diagonals are the outer vertices of the resulting five-pointed star, and the intersection points of the diagonals, lying inside the pentagon, are the inner vertices of this star.

To this star (call it a star of zero order) we will attach 5 similar stars of smaller size (stars of the first order) so that the three external vertices of each star of the first order coincide with the three adjacent vertices of the star of zero order: two external and one internal.

Around the stars of the first order, 15 even smaller stars of the order are built in a similar way, and some of these stars necessarily partially overlap each other, so that a pair of such stars has one side in common and, in addition, one outer vertex. Let's call such a figure - circled by two partially overlapping stars - a double star.

Around the stars of the second order, the background that is not occupied by them is built in the same way after the star. The figure filling a leaf of wild grapes or a funny man with a raised hat is repeated many times in ever decreasing size and, moreover, in such a way that these figures do not intersect in pairs, and their combination constitutes the entire background. Around each such figure you can describe a rhombus with an angle of 72° at the apex (Fig. 1).

Problem 2. Find the ratio of the area of ​​the part of the rhombus that complements the target (and his hat!) to the area of ​​the entire rhombus.

(You may have guessed that the answer to problem 2 is equal to... the answer to problem 1.) At figure 2 the reader will find on his own*):

$$\alpha = 36^\circ, \quad a = dq,$$
$$b_1 = a \text{tg} \alpha = a \sqrt{5} - 2\sqrt{5},$$
$$b_2 = b_1 q, \quad b_3 = b_2 q = b_1 q^2,$$
$$b_4 = b_3 q = b_1 q^3, \quad b_5 = b_1 q^4,$$
$$q = \frac{\sqrt{5} - 1}{2} \approx 0,618034.$$
As a result, the required ratio $p$ is equal to
$$p = 77\sqrt{5} - \frac{343}{2} \approx 0,677234.$$

*) If these calculations cause you difficulties, read the next section first.

⟦folio 27⟧

Let us turn to figure 3, which is slightly different from figure 1. A zero-order rhombus $ABFB'$, which has $|AB| = a_0$, is inscribed in the corner $LAL'$.

Two educational angles $LBF$ and $FB'L'$ are inscribed with two first-order rhombuses $BCGC'$ and $B'C_1G'C_1'$ from the side $a_1 = a_0q$, where

$$0,5 \leq q \leq 1.$$ (1)

To construct rhombuses of the second order, we draw straight lines $FG$ and $FG'$, which will cut off on straight lines $CH$ and $C_1'H_1'$, parallel to the diagonal $AF$ of the original rhombus, segments, service diagonals of rhombuses $CDHD'$ and $C_1D_3H_1'D_3'$, similar to the original one. These two rhombuses belong to the series of second-order conical rhombuses on the $a_2 = a_1q = a_0q^2$ side.

In the same way, we will construct a series of third-order rhombuses from the side $a_3 = a_0q^3$, etc.

If $q < 1$, then the lines $FG$ and $FG'$ are not parallel to the sides of the original angle and intersect them at some points $L$ and $L'$. The point $L$ is the homothety center for rhombuses $ABFB'$, $BCGC'$, $CDHD'$, ...

By virtue of symmetry, the point $L'$ is the same homothety center for the corresponding figures. On the straight line $LL'$ there is, in addition to these two points, an infinite number of other homothety centers for various rows of rhombuses. One of such centers, for example, is the point $L''$.

Problem 3. Find a readiness coefficient $q$ such that the rhombuses completely cover the interior of the triangle $LAL'$ (without gaps or overlaps).

For this, it is necessary and sufficient that for some natural $n$ the length of the side $a_i$ of a rhombus of any order is equal to the sum of the length of the side $n$ of the following rhombuses:

$$a_i = a_{i+1} + a_{i+2} + \dots + a_{i+n-1} + a_{i+n},$$

whence it follows that $q$ must satisfy the equation

$$q^n + q^{n-1} + \dots + q^2 + q - 1 = 0.$$ (2)

For $n = 1$, equation (2) takes the form $q - 1 = 0$, hence $q = 1$. In this case, the points $C'$ and $C_1$ on figure 3

⟦folio 28⟧

coincide with the point $F$, points $L$ and $L'$ “go to infinity”, and rhombuses of all orders become congruent (Fig. 4) *).

For $n=2$, equation (2) has the form $q^2+q-1=0$, and its root, satisfying condition (1), is equal to:

$$q_2=\frac{\sqrt{5}-1}{2}.$$

Now on figure 3 the point $D'_1$ coincides with the vertex $F$ of the original rhombus, and the arrangement of rhombuses inside the angle $LAL'$ takes on the form shown in figure 5. This is the main case we have already examined.

At $n=3$ the root of the cubic equation

$$q^3+q^2+q-1=0,$$

constrained by condition (1), is approximately equal to $q_3=0,543689$, and the solid arrangement of diamonds is illustrated by figure 6.

Easy to see; that for $n>1$ the left-hand side of equation (2) is negative for $q=\frac{1}{2}$ and positive for $q=1$. Consequently, this equation has a root $q_n$ that satisfies condition (1), and is unique (since the left side of equation (1) returns at $q>0$). It is also easy to prove that $q_1>q_2>q_3>...>q_n>...$, and $\lim_{n\to\infty}q_n=1/2$.

As the number $n$ increases, the prime $LL'$ gets closer and closer to the vertex $F$ of the original rhombus.

The network of rhombuses filling the interior of the angle in the limiting case $q_\infty=1/2$ is shown in figure 7. Point $F$ and similar vertices of rhombuses of all orders now appear on the same straight line $LL'$.

Solution to problem 1

It is easy to see the connection between the grid of tightly packed diamonds on figure 5 and the design depicted on the cover. This connection is illustrated

*) In Figures 4-8, for beauty, the ornament is highlighted in red, which does not affect the mathematical essence of the matter.
