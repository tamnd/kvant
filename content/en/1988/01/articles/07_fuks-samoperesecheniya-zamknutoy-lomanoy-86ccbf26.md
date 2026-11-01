---
id: 1988-1-fuks-samoperesecheniya-zamknutoy-lomanoy-86ccbf26
issue: kvant_1988_1
year: 1988
number: "1"
title: Self-intersections of a closed polyline
authors:
  - Фукс Д. Б.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 32
page_last: 36
page_labels: 30, 31, 34
tag: 13Q4
lang: en
source: kvant_digital
extraction: vision
content_sha256: 82f4bd769101854ea6dd1c901ce4035d812c273074ac230168ab41756bd44f9a
prompt_sha256: draft-1
translated_from: content/ru/1988/01/articles/07_fuks-samoperesecheniya-zamknutoy-lomanoy-86ccbf26.md
source_content_sha256: b4403d5a42bed0719bd486844dfc50782fd9765e32ce5df888b165f38977ae2d
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 30⟧

navigation forces. Estimate the time of star formation from a giant spherical cloud of cosmic dust with a density of $Q = 2 \cdot 10^{-20} \text{ e/cm}^3$. We can assume that when rolling down, the particles do not bypass each other. Gravitational constant $G = 6,67 \times 10^{-11} \text{ H} \cdot \text{m}^2/\text{кг}^2$.

I. Sh. Slobodtsky and V. A. Orlov “Weighted Olympiads in Physics”). Since, according to the conditions of the problem, the particles will not overtake each other, the total mass attracting our particle remains unchanged. Let's assume that all this mass is concentrated in the center of the cloud. then the problem will be reduced to finding the time it takes for the particle to fall on the attracting center.

We will consider the movement of a particle towards the center as the limiting case of movement along a very elongated ellipse, the larger of which is equal to $R/2$, and compare this movement with circulation in a circular orbit of radius $R$. Let's use Kepler's third law:

$$\frac{T^2}{T^2} = \frac{R^3}{(R/2)^3},$$

where $T_k$ is the period of motion in a circular orbit, $T_s$ is in an elliptical orbit. Period $T_k$ is easy to find using Newton’s second law and the law of universal gravitation:

$$\frac{mv^2}{R} = F_T = G \frac{mM}{R^2} = G \frac{mQ \cdot \frac{4}{3} \pi R^3}{R^2},$$

whence $T_k = \frac{2\pi R}{v} = \sqrt{\frac{3\pi}{G\rho}}$, and

$$T_s = \frac{T_k}{2^{3/2}} = \sqrt{\frac{3\pi}{8G\rho}}.$$

We found that the period $T_s$ does not depend on $R$. Consequently, the time of falling of a particle onto the attracting center (the time of revolution of the star), equal to half the period of revolution in an elliptical orbit, does not depend on the radius of the cosmic dust cloud and is equal to

$$\tau = \frac{T_s}{2} = \sqrt{\frac{3\pi}{32G\rho}} \approx 1,5 \cdot 10^{13} \text{ c} \approx 10^6 \text{ лет.}$$

V. E. Skorovarov

Self-intersections of a closed polyline

In this note we will provide a solution to problem M1064 and discuss some closer problems.

M1064. What is the maximum number of self-intersection points that a closed n-link flat polygon can have if a) n is odd: 6) n is even? (It is assumed that no three vertices lie on the same line and that no three links intersect at the same point.)

Answer: a) $n(n-3)/2$; b) $n(n-4)/2+1$.

It is necessary to prove that the number of self-intersections under consideration cannot exceed the specified values, and give examples of broken lines for which these values ​​are achieved.

It is clear that two links of a broken line intersect at most at one point and that adjacent links do not intersect (that is, they do not have common points except a common vertex). In total, a closed n-link broken line has $n(n-1)/2$ pairs of links, including n pairs of adjacent links. Thus, the number of closed broken lines with such a number of self-intersections exists: it is sufficient that all n diagonals are drawn in a regular n-gon, least distant from the center (see figure 1 for n=5 and n=7). These links form a closed n-link broken line, all non-

⟦folio 31⟧

adjacent links of which intersect (at different points). Problem a) solved.
Now let $n$ be even. The interior of the vertices of a given $n$-linked polyline in a row, starting from any one, and denote by $A$ the set of vertices with four numbers and by $B$ the set of vertices with four numbers. Any link of the broken line goes from some point in the set $A$ to some point in the set $B$. Let $l$ be a line containing some link. If this link intersects all links not adjacent to it, then all vertices with four numbers lie on the same side of $l$ (we do not, of course, take into account the vertices of the link in question that lie on $l$). This means that the sets $A$ and $B$ lie on opposite sides of the line $l$ and at the same time have one common point with it. There are no more than two such lines. This fact seems very interesting to me, but for those who like constructive reasoning, I will give its proof (see Fig. 2).

Let there be three such straight lines. More precisely, let $A_1, A_2, A_3 \in A$ and $B_1, B_2, B_3 \in B$ be points such that the sets $A$ and $B$ lie on opposite sides of each of the lines $A_1B_1, A_2B_2, A_3B_3$. Since the points $A_2, B_2$ lie on opposite sides of the straight line $A_1B_1$, and the points $A_1, B_1$ lie on opposite sides of the straight line $A_2B_2$, then the segments $A_1B_1$ and $A_2B_2$ intersect; let $C$ be the point of intersection.

Point $A_3$ lies on the same side of line $A_1B_1$ as point $A_2$, and lies on the same side of line $A_2B_2$ as point $A_1$; this means that it is contained in the angle $A_1CA_2$. By similar principles, the point $B_3$ lies in the corner $B_1CB_2$. This means that the line $A_3B_3$ does not intersect at least one of the segments $CA_1, CA_2$ and does not intersect at least one of the segments $CB_1, CB_2$. Let it not intersect $CA_i$ and $CB_j$ (on figure these are $CA_2$ and $CB_1$); then points $A_i$ and $B_j$ lie on one side of it, which contradicts the assumption.

So, there are at most two links that intersect all non-adjacent links. This means that at least $n-2$ links do not intersect at least one of the links not adjacent to them; therefore, there are at least $(n-2)/2$ pairs of disjoint non-adjacent links and the total number of self-intersection points does not exceed $n/(n-3) - \frac{n-2}{2} = \frac{n(n-4)}{2} + 1$.

At any moment, a $n$-link broken line with $n/(n-4)/2+1$ self-intersections remains.

Let us draw in a regular $n$-gon all the diagonals that are close to its center, but do not pass through the center. (Moreover, $n/2$ they form a closed broken line; if $n/2$ is odd, they form two closed broken lines, symmetrical to each other relative to the center.) Each of these diagonals is all non-adjacent diagonals, except one - parallel to ei; this gives $n/(n-4)/2$ intersections. Let's erase two parallel diagonals, and connect their ends crosswise. (See figure 3 for $n=6$ and $n=12$. Thin solid lines are the diagonals of a regular $n$-gon that are closest to the center and do not pass through the center. Dotted lines are the discarded diagonals. Thick solid lines are the diagonals that they replace. Solid dots and thick lines make up our polygon.) Number intersections will increase by 1, and, as is easy to check, $n$ of the drawn segments form a closed broken line. Problem 6) has been solved.

Let us present a few more problems that are similar in form to the problem discussed above. First of all, we can consider the class of broken lines under consideration, allowing the broken line to split into several closed broken lines. To give the task a natural form, we will formulate it like this. There are points on the plane of fixed $n$ points, no three of which lie on the same straight line. Some of these points are connected by segments, with each point connected exactly to two others. What is the most possible number (See page 34 for ending)

⟦folio 34⟧

Search programs
(For the beginning, see p. 7)

square to the previously calculated number of frequent ticket holders for smaller values ​​of S. This is done in line 100. Finally, when the cycle through S (from 0 to 13) is completed, you need to double the resulting number P and subtract 1.

Exercise
23. How many terms of the sum 1+2+3+... must be taken to get a three-digit number consisting of identical digits?
24. How many integers are there from 1 to 1988 that are not divisible by any of the numbers 6, 10, 15?
25. Find the smallest natural number M such that the sum

squares of identical consecutive natural numbers, starting with M, is a perfect square.

26. How many ways can rubles be marked with copper coins (in denominations of 1, 2, 3, 5 kopecks)?

27. In the sequence 19886138... each digit, starting from the fifth, is equal to the last digit of the sum of the even previous digits. After how many digits does the initial combination 1988 appear again (in other words, how many digits are there in the period)?

28. Let X be the sum of the cubes of ten consecutive natural numbers, and Y the sum of these same natural numbers. Prove that X² - ​​Y² is divisible by 300.

29. Determine a) the smallest ratio of a three-digit number to the sum of its digits. For what numbers is this smallest (smallest) value achieved?

30. Find a four-digit number that is four times smaller than the number written in the same digits, but in reverse order.
