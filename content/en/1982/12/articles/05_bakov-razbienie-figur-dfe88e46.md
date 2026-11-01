---
id: 1982-12-bakov-razbienie-figur-dfe88e46
issue: kvant_1982_12
year: 1982
number: "12"
title: Splitting shapes
authors:
  - Баков А.
rubric: osnovnye-stati
page_first: 18
page_last: 19
page_labels: 16-17
tag: SIXA
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1319f854199eeb4bb0d8491aab078475b75f1c8085073d5640e10933edeb0302
prompt_sha256: draft-1
translated_from: content/ru/1982/12/articles/05_bakov-razbienie-figur-dfe88e46.md
source_content_sha256: b30a6c17cd00a84c9e387c026761b9a4bb7717aec9911b0a6016237ff05a5c33
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 16⟧

Splitting shapes

Recently, combinatory geometry has received great development - a science that studies the optimal configurations of a point or figures. It is increasingly used in transport (cargo stowage), construction (layout of parts), architecture (layout) and in many other sectors of the national economy.

To clarify one of the very well-known problems of combinatory geometry, we introduce the concept of the diameter of a figure. The diameter of a figure is a number $d$ such that the distance between any two points of the figure does not exceed $d$, but for any number less than $d$, there are points in it the distance between which exceeds $d$. For example, a circle of diameter (in the traditional sense) $d$ is a figure of diameter $d$. A regular triangle with sides $d$ also has a diameter $d$.

A flat (spatial) figure is called bounded if it is contained in a certain circle (ball). If a figure has a diameter, then it is very limited. It can be proven that the opposite is also true.

A point of a plane figure is called boundary if in any circle with the center at this point there are both points belonging to the figure and points not belonging to it. A figure is called closed if it contains all its boundary points. For example, the plane figure $A_1 = \{(x; y) | x^2 + y^2 \leq 1\}$ is closed, but the figures $A_2 = \{(x; y) | x^2 + y^2 < 1\}$ and $A_3 = \{(x; y) | 0 < x^2 + y^2 \leq 1\}$ are not closed.

It turns out that if a bounded figure is closed, then it contains a pair of points

This note is based on a report that in November 1981, ninth-grader Anton Bakov (Sverdlovsk) gave at the XIII Conference of Young Mathematicians in Batumi («Kvant», 1982, No. 4).

Fig. 1.

⟦folio 17⟧

favorite" figures. Neither the “Pala hexagon” (any flat figure of diameter $d$ is contained in it) nor the circle of diameter $d$ (many figures of diameter $d$, for example a regular triangle with side $d$, will not “fit” into it) were suitable here. The desired figures turned out to be so-called figures of constant width.

To prove his theorem, Pal used support lines. A straight line is called *supporting* to a given plane figure if it has at least one common point with the figure and the entire figure lies on one side of it (Fig. 2). The number $h$ is called the *width* of a figure if it has parallel supporting lines, the distance between which is $h$. Generally speaking, a figure can have many "widths" (Fig.3). If the width of the figure does not depend on the direction of the supporting lines, the figure is called *fidura of constant width* (Fig. 4).

It turns out that any flat figure of diameter $d$ is contained in some figure of constant width $d$. It was also proven that a figure of constant width $d$ cannot be 2 parts of diameter less than $d$.

These messages allowed the Soviet mathematician V. G. Boltyansky to prove in 1969 that a flat figure of diameter $d$ cannot be divided into 2 parts of diameter less than $d$ if and only if it is contained in a single figure of constant width $d$.

The solution to the problem considered served as the foundation for the further development of combinatorial geometry.

Today this problem has been solved not only for the plane: the equivalent of Borsuk’s theorem has been proven for three-dimensional space (4 parts are always enough there). There is a conjecture that for a $n$-dimensional space there are always enough $n+1$ parts.

Problems (added by V. G. Boltyansky)

1. Prove that the diameter of a polygon is equal to the largest distance between its vertices.
2. Based on Pal's theorem, prove that any plane figure with diameter $d$ can be divided into three parts, the diameter of each of which does not exceed $\frac{\sqrt{3}}{2} d \approx 0,866 d$.

3. In a regular polygon with an odd number of sides, other circles are drawn, each of which contains the ends of the sides and has a center at the opposite vertex (see Fig. 4). Prove that these others bounding the figure have constant width.

4. Prove that a regular polygon with an odd number of sides, whose longest diagonal has length $d$, cannot be divided into two parts, each of which has a diameter less than $d$.

5. A segment smaller than a semicircle is cut off from a circle of diameter $d$. The resulting figure $F$ still has a diameter $d$. It can be easily divided into two parts of diameter less than $d$ (how?. Therefore, $F$ is contained in different figures of constant width $d$. Give two such figures.

6. Prove that an inscribed polygon with an odd number of sides can be divided into two parts less than its diameter. Is this true for an arbitrary polygon with an odd number of sides?

7. Let $|AB| > d$ and the figures $M$ (“bigon”) represent the intersection of two circles of radius $d$ with centers $A$ and $B$. Prove that if a figure of diameter $d$ is entirely contained in a two-gon $M$, then it can be divided into two parts of diameter less than $d$.
