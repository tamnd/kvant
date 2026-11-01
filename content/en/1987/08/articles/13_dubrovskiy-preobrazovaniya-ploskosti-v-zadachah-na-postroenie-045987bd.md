---
id: 1987-8-dubrovskiy-preobrazovaniya-ploskosti-v-zadachah-na-postroenie-045987bd
issue: kvant_1987_8
year: 1987
number: "8"
title: Plane transformations in construction problems
authors:
  - Дубровский В. Н.
rubric: shkola-v-kvante
page_first: 42
page_last: 44
page_labels: 40-42
tag: 4OJV
lang: en
source: kvant_digital
extraction: vision
content_sha256: 8dc09a1d8d887092205fd33e510abe4b4f5d24627aad2f4fbadbb98a65ecbaaf
prompt_sha256: draft-1
translated_from: content/ru/1987/08/articles/13_dubrovskiy-preobrazovaniya-ploskosti-v-zadachah-na-postroenie-045987bd.md
source_content_sha256: ac7a689670f6a7ff049a497aefa0fc0c7be74ee4cd25671587e9630ffebdbe3f
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 40⟧

Math 8, 9

The article “Transformation of a plane in construction problems” is intended primarily for use, and the article “The Cauchy-Bunyakovsky Inequality” is intended for ninth-graders.

Transforming a plane in construction problems

In this note, we talked about one method of converting planes into construction - the simplest, but, please, the most common. Let's start by discussing two problems from «Kvant» No. 1 (p. 36).

Problem 1. Given a straight line and two circles on opposite sides of it. Construct a square whose diagonal lies on the given line, and the ends of the other diagonals lie on the given circle.

Let vertices A and C of the required square ABCD lie on a given line l, and vertices B and D on given circles ω₁ and ω₂ (Fig. 1; we assume that circles ω₁ and ω₂ are not symmetrical with respect to line l). Since points B and D must be symmetrical with respect to line l and D∈ω₁, point B must lie on the circle ω₁', symmetrical with respect to circle ω₁ with respect to l. Having constructed a circle ω₁' and found its points of intersection with ω₂ (there may be two, one, or none - and the problem has the same number of solutions), we obtain the possibility of the position of vertex B. After this, it is quite easy to find the remaining vertices.

Problem 2. Given a point A, a circle and a straight line. Construct a square ABCD such that its vertex B lies on a given circle, and its vertex C lies on a given line.

Fig. 1.

⟦folio 41⟧

Here, as in Problem 1, you need to guess that the vertex $C$ is obtained from the vertex $B$ when performing the transformation $F$ of the plane; this transformation consists of sequentially performing a turn of $45^\circ$ around the center $A$ ($\angle BAC = 45^\circ$) and preparing with a coefficient of $AC/AB = \sqrt{2}$ and a center of $A$ (the order in which the turn and preparation are performed does not play a field in this case; $F$ is said to be a composition of the said turn and preparation*). Thus, to solve the problem, it is enough to construct the circle $\omega' = F(\omega)$, i.e., the image of the given circle $\omega$ under the transformation $F$, and take as the vertex $C$ any of the points of intersection of the circle $\omega'$ with the given line. The center $O'$ of circle $\omega'$ can be constructed as the vertex of a right isosceles triangle $AOO'$ ($\angle AOO' = 90^\circ$), and the radius of circle $\omega'$ is $\sqrt{2}$ times greater than the radius of circle $\omega$. Note that the turn to $45^\circ$ can be done either clockwise or counterclockwise; this produces two transformations $F_1$ and $F_2$, which correspond to two circles $\omega'$ and $\omega''$, so that the problem can have from 0 to 4 solutions (Fig. 2).

Both of these problems fit into the following scheme (Fig. 3):

Given two figures $M_1$ and $M_2$ and some transformation of the plane $F$; it is required to find on these figures such points $X$ (on $M_1$) and $Y$ (on $M_2$), such that under the transformation $F$ the point $X$ goes to the point $Y$.

To solve, you need to construct the figure $F(M_1)$, into which the figure $M_1$ goes during the transformation $F$, and find its intersection with the figure $M_2$; then $Y$ is any of the intersection points of the figure $M_2$ and $F(M_1)$, and $X = F^{-1}(Y)$, where $F^{-1}$ is the inverse transformation of $F$.

Of course, the transformation $F$, and the part and figures $M_1$ and $M_2$ are not specified explicitly. You need to be able to “fish” them out of the conditions - and here everything depends on the art of solving. To make it easier for readers to navigate, we provide a complete list, names and designations of all similarity transformations and, in particular,

*) You can read about the composition of transformations, for example, in the textbook: Geometry 6-8, ed. A. N. Kolmogorov. — M.: Education, 1980.— P. 191.

Moved plane. (Some of them are not studied in school, but are transformation compositions known from the 7th grade course.)

Movements:
parallel transfer $T_a$ to vector $a$;
rotate $R_a^\alpha$ by angle $\alpha$ around center $O$;
connects symmetry $S_l$ with axis $l$;
sliding symmetry $S_l, a = T_a^\circ S_l$, where $l \parallel a$, is the composition of the axes of symmetry and the parallel reversal of the axis ($\circ$ is the composition sign).
Similarity transformation not included in the list of movements:
homothety $H_o^k$ with center $O$ and coefficient $k$;
rotary homothety (in other terminology, spiral similarity) with center $O$, angle $\alpha$ and coefficient $k$ is a composition of $H_o^k \circ R_o^\alpha$ homothety and symmetry about the axis passing through the center of homothety.
For the convenience of some transformations, we actually included in this list twice (rotation, coupled symmetry and homothety are special cases of other transformations - which ones?), however, it can be proven that all possible plane similarity transformations are listed here.

According to our scheme, the figures $M_1$, $M_2$ and the transformation $F$ in problem 1 are the data of a circle and symmetry with respect to a straight line, and in problem 2 - a circle, a straight line and a rotary homothesis $H_a^\alpha \circ R_a^\alpha$.

Let us now consider two problems, in which

⟦folio 42⟧

which our diagram of space does not demonstrate explicitly.

Problem 3. Inscribe a parallelogram similar to the given one into another given parallelogram so that on each side of the described parallelogram lies one vertex of the inscribed one.

Let ABCD be the given circumscribed parallelogram, and KLMN the desired inscribed one (Fig. 4). Their centers must coincide, since with central symmetry relative to the center of the parallelogram KLMN, the parallelogram ABCD must transform into itself. Consequently, the center O of the desired parallelogram is known to us; $\angle KOL = \alpha$ and the relation $LO:KO = k$ are also known, since the parallelogram shape KLMN is given. This means that we can apply our scheme by taking the straight lines AB and BC as $M_1$ and $M_2$, the ready-made rotary $H_0^\circ R_0^\alpha$ as F, and the required points K and L ($L = F(K)$) as X and Y. No further explanation is needed. We only note that in this problem it is interesting to conduct a complete study.

Problem 4. Construct triangle ABC if the length of its bisserline AD and the side lengths AB and AC are known.

Let's construct a segment AD and draw circles β and γ of radii AB and AC with center A (Fig. 5). This will be the set M1 and M2, and points B and C are points X and Y in our diagram. What will be the transformation F? According to the bissergris theorem (see, for example, «Kvant» No. 2 of 1985, p. 29), the ratio $k = CD:DB$, in which the side CB is divided by the base of the bissergris, is equal to the ratio AC:AB of the sides of the triangle, and therefore we know. And since $C = H_D^{-k}(B)$, we can take the ready-made $H_D^{-k}$ as F, i.e. C is the intersection point of circles γ and $H_D^{-k}(\beta)$.

Problems to solve independently

1. Construct a triangle using the bissergris and the segments into which the base of the bissergris divides the side of the triangle.
2. Construct a circle with a given center so that one of the segments connecting its points of intersection with the sides of a given angle is parallel to the given line.
3. At two of the known moments in time with cows, the angles between the directions of two lighthouses marked on the map were measured. The direction and speed of the cow's movement are also known. How to find the position of the cow on the map at these moments?
4. Construct triangle ABC using media AA1 and BB1 and angle C.
5 (for readers familiar with inversion). Inscribe a rhombus of given area in a given parallelogram so that one vertex of the rhombus lies on each side of the parallelogram.

V. N. Dubrovsky

Cauchy-Bunyakovsky inequality

The Cauchy-Bunyakovsky inequality can safely be considered one of the most popular in mathematics. It has appeared more than once on the pages of our magazine (see, for example, «Kvant», 1986, No. 12, p. 31). The Cauchy-Bunyakovsky inequality looks like this:

$$\begin{align*}
|a_1b_1 + a_2b_2 + \dots + a_nb_n| &\leq \\
\leq \sqrt{a_1^2 + a_2^2 + \dots + a_n^2} \cdot \sqrt{b_1^2 + b_2^2 + \dots + b_n^2}.
\end{align*}$$

However, there is little proof of it. Here we give one very simple proof of the Cauchy-Bunyakovsky inequality, discuss its geometric meaning and, with its help, once again solve one problem proposed in 1984
