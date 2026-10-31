---
id: 1976-4-vasilev-slozhenie-figur-79e77233
issue: kvant_1976_4
year: 1976
number: "4"
title: Addition of figures
authors:
  - Васильев Н. Б.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 24
page_last: 31
page_labels: 22-29
tag: D3I4
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0af158ac07d9b0837fb66371e862808dd88cbc53a314cdc5b3ca45de769515ff
prompt_sha256: draft-1
translated_from: content/ru/1976/04/articles/06_vasilev-slozhenie-figur-79e77233.md
source_content_sha256: 4dbeb36802be01812a8f909e4a934d1e03f6d213f9c4263521445520deaa9b60
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 22⟧

N. Vasiliev

Addition of figures

Apparently, each of the readers understands what is required of him if he is asked to make a trapezoid from three identical triangles or from four corners - a corner twice as large. But in our article we will talk about “addition” of a completely different kind. The sum of two triangles will, as a rule, be a convex hexagon, the sum of two identical circles will be a circle with twice the radius, and the sum of two segments will be a parallelogram. To distinguish the operation we are going to talk about from the general “unification”, it is called “vector sum” or “Minkowski sum” - after the name of the remarkable German mathematician Hermann Minkowski (1864-1909) who studied it. The most interesting applications of this concept relate to convex bodies in three-dimensional and generally n-dimensional space. But we will deal mainly with flat figures.

The reason for this note was problem M330 from “task «Kvant», which we will solve here. Here is the wording.

There are two convex polygons F and G on the plane. Let us denote by H the set of points that can contain the midpoint of a segment, one end of which belongs to F and the other to G. Prove that H is a convex polygon.

a) How many sides can H have if F has n₁ and G has n₂?

b) What can be the perimeter of H if the perimeter of F is equal to P₁ and G is equal to P₂?

c)* What can be the area of ​​H if the area of ​​F is equal to S₁ and the area of ​​G is S₂?

§ 1. The set of midpoints

Let's start by analyzing a simpler problem.

Problem 1. Given two segments: [AB] and [CD]. Find the set of points where the midpoint of a segment can fall, one end of which P lies on [AB] and the other end Q on [CD].

Solution. Let us first consider the general case when the segments [AB] and [CD] are not parallel. (We will discuss the special case [AB] || [CD] below.) Let us denote the midpoint of the segment [PQ] by M. First fix the position of the point Q. If P runs through the entire segment [AB], then M runs through the midline of the triangle QAB (Fig. 1a) - a segment with endpoints at the midpoints of the segments [QA] and

Fig. 1a.

Fig. 16.

⟦folio 23⟧

[QB]. If we now force the point Q to go through the entire segment [CD], then the middle line of the triangle QAB will obviously sweep out an entire parallelogram (Fig. 16)—its vertices will be the midpoints of the segments [AC], [AD], [BC] and [BD].

Note that if [AB] and [CD] intersect, then the desired set is a parallelogram with vertices at the midpoints of the sides of the convex quadrilateral ACBD, and if [AB] and [CD] do not lie in the same plane, then our parallelogram will be obtained in the section of the tetrahedron ABCD by a plane parallel to [AB] and [CD] and passing in the middle between them.

Let's find out what this parallelogram turns into when the segments [AB] and [CD] are parallel. (We can assume that they are equally directed.) If [AB] and [CD] belong to different parallel lines, then ABDC is a trapezoid, and the midpoints of M segments PQ will fill the midline of this trapezoid (Fig. 1c)—a segment with ends at the midpoints of segments [AC] and [BD].

The same answer is obtained in the case when [AB] and [CD] belong to the same line. Here, in order not to analyze the various locations of points A, B, C, D on a straight line, it is convenient to translate the problem into the language of algebra. We will assume that our straight line is the number axis, the coordinates of these points are $k_A, k_B, k_C, k_D$ ($k_A < k_B, k_C < k_D$), and we will use this fact: the set of numbers ($x_P + x_Q)/2$, where $x_P \in [k_A, k_B]$, $x_Q \in [k_C, k_D]$ is the segment $[(k_A + k_B)/2, (k_C + k_D)/2]$

Fig. 1st century.

Fig. 1y.

⟦folio 24⟧

Fig. 2.

Example 2. The half-sum of two rectangles F and G of dimensions $a \times b$ and $c \times d$, whose sides $a$ and $c$ are parallel, is a rectangle of dimensions $(a+c)/2 \times (b+d)/2$ (Fig. 2).

Indeed, in the coordinate system $Oxy$, in which the axis $Ox$ is parallel to the sides $a$ and $c$, the coordinates $x$ of the points of rectangles F and G run through segments of length $a$ and $c$, coordinates $y$ are segments of length $b$ and $d$, and the half-sums of these coordinates are segments of corresponding lengths $(a+c)/2$ and $(b+d)/2$. (Here again the “obvious fact” that we used at the end of solving Problem 1 is useful.)

Task 2. Find the half-sum of the following rectangles;

a) two non-parallel rectangles;

b) a regular triangle and its sides;

c) two triangles into which the square is cut diagonally;

d) a square and a regular triangle that have one common side;

e) segment and circle;

e) two circles of different radii;

g) semicircles with themselves;

h) semicircles that together make up a circle;

i) one figure is two adjacent sides of a regular pentagon, the other is its three remaining sides.

Solution to problem 2a). We will proceed in the same way as when solving Problem 1. Let us fix the point $P$ of the rectangle $F$ (Fig. 3). Then the set of points $P, Q$, where $Q$ runs through $G$, is the rectangle $\{P\}$. Gromothety $G$ with coefficient 1/2 (and with homothety center $P$). We must now unify all the rectangles $\{P\} \ast G$, where $P$ runs through $F$. It is not difficult to see that we need a demerger $F \ast G$ (the figure swept by the blue rectangle at Fig. 3, when the lower blue vertex runs through the pink rectangle homothetic to the rectangle $F$ with a similarity coefficient $\frac{1}{2}$—a convex rectangle whose sides are parallel to the data sides rectangles, and their length is equal to half.

Comparing problem 2a) with the preceding example 2, we see that the shape of the figure $F \ast G$ can change significantly when one of the figures $F$ or $G$ is rotated.

Eight answers to points 6)—i) of problem 2 are given in disorder on figure 4.

Task 3. Find the half-sum of the following figures in space:

a) two parallel parallelepid rectangles;

⟦folio 25⟧

§ 2. Half-sum of convex polygons

Recall that a set of points F is called convex if for any two points P and Q from F the entire segment [PQ] is contained in F.

You may have noticed that finding the half-sum of convex figures is more than non-convex, and if F and G are convex figures, then F*G is also convex.

Let's prove it. Let $M_1$ and $M_2$ be arbitrary points in F*G. then $M_1 = P_1 * Q_1$, $M_2 = P_2 * Q_2$ for some $P_1 \in F$, $P_2 \in F$, $Q_1 \in G$, $Q_2 \in G^*$). Since F and G are convex, then $[P_1 P_2] \subset F$ and $[Q_1 Q_2] \subset G$. then $[P_1 P_2] * [Q_1 Q_2] \subset F * G$. But, as we know (example 1), the half-sum of segments is a parallelogram, and the points $M_1$ and $M_2$ are its vertices (the parallelogram can degenerate into a segment containing the points $M_1$ and $M_2$). Since the figure F*G contains this parallelogram, it contains

$$*) Мы используем общие обозначения: F \cap G — пересечение фигур F и G, F \cup G — их объединение, G \subset F (или F \supset G) означает, что G содержится в F, P \in F — что точка P принадлежит F.$$

and the segment $[M_1 M_2] : F * G \supset ([P_1 P_2] * [Q_1 Q_2]) \supset [M_1 M_2]$.

From the examples encountered in problems 2 a)-i), it is clear that we obtain convex polygons F and G - a polygon whose sides are parallel to the sides F and G, but half as long. The only way to prove this fact (and even to formulate it precisely) was to represent a convex polygon as the intersection of half-planes.

Bydem say that two half-planes $σ_1$ and $σ_2$ have the same direction if $σ_1 \supset σ_2$ or $σ_2 \supset σ_1$. Of course, the edges of such half-planes $l_1$ and $l_2$ are parallel lines, and their resulting $σ_1 * σ_2$ is a half-plane of the same direction, the edges of which are the straight line $l_1 * l_2$, located in the middle between $l_1$ and $l_2$. (Prove it carefully!)

We call the half-plane $σ_F$ support for the polygon F if $σ_F \supset F$ and the intersection of F with the boundary line $l_F$ of the half-plane $σ_F$ is not empty. We will call this intersection $l_F \cap F$ a support polygesture. It is clear that for each direction σ there is its own supporting half-plane. Its corresponding support set is either one point (the vertex of the polygon) or a segment (the side of the polygon).

We denote the support set by $F_\sigma$.

Let F and G be two convex polygons, $σ_F$ and $σ_G$ their support half-planes of the same direction, $F_\sigma$ and $G_\sigma$ the corresponding support polysets. It is easy to find a support set of the same direction for the half-sum F*G: it is equal to the half-sum of the support polygests $F_\sigma$ and $G_\sigma$, that is

$$(F * G)_\sigma = F_\sigma * G_\sigma.$$

Indeed (Fig. 6), the midpoint M of any segment PQ, where P ∈ F, Q ∈ G, lies in the half-plane $σ_F * σ_G = \sigma_F * G$, and a point M can fall on the boundary straight line of the half-plane $σ_F * G$ if and only if simultaneously P ∈ F_\sigma$ и Q ∈ G_\sigma$.

⟦folio 26⟧

Now we can formulate a convenient rule that allows us to find the half-sum F * G of convex polygons F and G.

It is necessary to consider which direction σ for which at least one of the corresponding support sets Fσ and Gσ is a segment (side F or G), and construct the half-sum of Fσ and Gσ - the segment Fσ * Gσ (using examples 16), c)). The union of all these segments Fσ * Gσ in different directions σ is the boundary of the figures F * G.

The application of this rule is illustrated by figure 6, where each of the directions σ has its own color. It is clear that the support sets Fσ, Gσ, and therefore (F * G)σ = Fσ * Gσ for the remaining “intermediate” directions consists of individual points (vertices of the corresponding polygons). We have already proven that the figure F * G is convex. Now, having found its boundary, we see that F * G is a convex polygon.

Fig. 6.

the shin has k, and the directions of its sides are the same as those of F and G.

Problem 4. a) Prove that if σ and τ are half-planes of different directions, then σ*τ is the entire plane.

b) Try to solve problems 2a) - d), using the rule formed above.

c) Give an example of a pentagon F and a triangle G for which F * G has 5, 6, 7 and 8 sides.

Now it’s easy to give answers to questions a) and b) of the M330 problem:

a) the number of sides of the half-sum of an n1-outliner and an n2-outliner can be any number that is not more than n1+n2 and not less than the most of the numbers n1, n2;

b) the perimeter F * G is equal to half the sum of the perimeters F and G *).

Finding an answer to question b) of the M330 problem and justifying it is much more difficult. We learned it in § 4. For now, let's talk about what a sum and a linear combination of figures are.

§ 3. Sums and linear combinations of figures

We have used the word “half-sum” and the symbol * that replaces it a lot. It's time to say what the sum of two figures is.

Let us fix some point O (the beginning of the cut off or stripes).

On the limit 2. The power of all ends of M vectors

$\vec{OM} = \vec{OP} + \vec{OQ}$, where P and Q are arbitrary points of the figures F and G, respectively, is called the sum (or Minkowski sum) of the figures F and G (Fig. 7). The sum of F and G denotes F + G.

On the limit 3. The power of all ends of M vectors

$\vec{OM} = \lambda \cdot \vec{OP}$, where P is an arbitrary point of the figures F, λ is a given positive number, is called the product of F and λ (Fig. 8). This figure denotes λF.

*) Indeed, if the length of a point is considered equal to 0, then the length (F * G)σ is equal to half the sum of the lengths Fσ and Gσ for each direction σ.

⟦folio 27⟧

Example 3. The “half-sum” $F*G$ (Definition 1) is precisely $\frac{1}{2}(F_1 + F_2)$: after all, the condition $\vec{OM} = \frac{1}{2}(\vec{OP} + \vec{OQ})$ indicates that $M$ is the midpoint of the segment $[PQ]$.

We will call the figure $\lambda F + \mu G$, where $\lambda$ and $\mu$ are positive numbers, a linear combination of the figure $F$ and $G$.

Example 4. Linear combination $\lambda F + \mu G$ of rectangles $a \times b$ and $c \times d$, whose sides $a$ and $c$ are parallel (as in Example 2), rectangle $(\lambda a + \mu c) \times (\lambda b + \mu d)$.

Problem 5. What do the linear combinations $\lambda F + \mu G$ of those figures $F$ and $G$ look like, which we needed to find in problems 2-4?

Problem 6. Prove the following properties of the introduced operations:
1°) $F_1 + F_2 = F_2 + F_1$;
2°) $(F_1 + F_2) + F_3 = F_1 + (F_2 + F_3)$;
3°) $\lambda(\mu F) = (\lambda \mu) F$;
4°) $\lambda(F_1 + F_2) = \lambda F_1 + \lambda F_2$;
5°) if $F_1 \subset F_2$, $G_1 \subset G_2$, then $\lambda F_1 + \mu G_1 \subset \lambda F_2 + \mu G_2$;
6°) $\lambda F + \mu F \supset (\lambda + \mu) F$; if $F$ is convex, then $\lambda F + \mu F = (\lambda + \mu) F$;
7°) $\lambda(F \cup G) = \lambda F \cup \lambda G$ and $H + (F \cup G) = (H + F) \cup (H + G)$;
8°) $\lambda(F \cap G) = \lambda F \cap \lambda G$ and $H + (F \cap G) \subset (H + F) \cap (H + G)$;

9°) if $\lambda + \mu = 1$, then the linear combination $\lambda F + \mu G$ does not depend on at which point $O$ the “pole” is placed.

Generally speaking, with a different choice of pole $O$ and with parallel transfer of data, the figure $F$ and $G$, the linear combination $\lambda F + \mu G$ changes, but does not exist - it simply undergoes parallel re-assignment. Thus, if the conditions of two figures that receive each other from each other by parallel transformations do not differ, are considered equivalent, then you can not indicate where the stripes are chosen - the result $\lambda F + \mu G$ will be uniquely determined.

Note that any linear combination $\lambda F + \mu G$ figure $F$ and $G$ is obtained from the “normalized” combination $\frac{\lambda}{\lambda + \mu} F + \frac{\mu}{\lambda + \mu} G$ (such that the coordinates have a sum of coefficients equal to 1) by multiplying by the number $(\lambda + \mu)$, that is, just ready. Thus, linear combinations are $c \lambda + \mu \neq 1$. They won’t give you new figures in shape.

Let us describe one way to imagine all normalized linear combinations of two convex polygons $F$ and $G$. Let us intersect one of them (without turning) into a parallel plane and construct a “convex hull” $F$ and $G$ - a convex polygon, all of whose vertices coincide with the vertices $F$ and $G$ (for example, a regular octadron on figure 5 - the convex hull of the upper and lower triangles; its “middle section” is the half-sum of these triangles). Then the section of this polygon of the plane, parallel to $F$ and $G$, gives just the linear combinations $\lambda F + \mu G$, where $\lambda + \mu = 1$; the ratio $\lambda/\mu$ is equal to the ratio of the distances from the cutting plane to the plane $F$ and $G$.

The following five problems illustrate the concept of the “Minkowski sum” from different angles.

Problem 7. From the point $O$ lying on the boundary of the half-plane, $n$ vectors of length 1 are directed inside the half-plane. Proof

Fig. 7.

Fig. 8.

⟦folio 28⟧

Remember that if $n$ is odd, then the length of their sum is at least 1.

Task 8. Let $F$ be a convex polygon, $S$ its area, $P$ its perimeter, $K$ a circle of radius $1$ with center $O$. Prove that the area of ​​the figure $F + \rho K$ (ρ-neighborhood of the polygon $F$) is $S + \rho P + \rho^2\pi$. Write a similar formula for the volume of the $\rho$-neighborhood of a convex polygon.

Task 9. Prove that the following three properties of the convex polygon $F$ are equivalent: (1) $F$ has a center of symmetry; (2) $F$ can be cut into parallelograms; (3) $F$ is the sum of several segments.

Task 10. Prove that the following two properties of a convex polygon are equivalent: (1) all faces $F$ are parallelograms; (2) $F$ is the sum of several segments, no three of which are parallel to the same plane. How many faces does such a polygon have if the number of segments is $k$?

Task 11. A forest caught fire at one point in an uncontaminated area. The wind blew for time $t_1$ at speed $v_1$, then $t_2$ at speed $v_2$, ..., $t_n$ at speed $v_n$. The fire spreads from the ignited areas at the speed of the wind (and these areas continue to burn). Which area burned during this time? What if the fire, in addition, spreads evenly in all directions at a speed of $u$? (A. Savin)

§ 4. Area of ​​the sum of a figure

The area of ​​the figure $F$ will be denoted by $S_F$. The theorem on the areas of homothetic figures states:

$$S_{\lambda F} = \lambda^2 S_F.$$

Let's see what can be said about the area of ​​the sum and, in general, the linear combination of two figures. Let's start with the special case when $F$ and $G$ are rectangles $a \times b$ and $c \times d$, and the sides of length $a$ and $c$ are parallel. Then $\lambda F + \mu G$ is the rectangle $(\lambda a + \mu c) \times (\lambda b + \mu d)$ and

$$S_{\lambda F + \mu G} = (\lambda a + \mu c)(\lambda b + \mu d) = \lambda^2 ab + \mu^2 cd + \lambda \mu (ad + bc) \geq \lambda^2 ab + \mu^2 cd + 2\lambda \mu \sqrt{abcd} = (\lambda \sqrt{ab} + \mu \sqrt{cd})^2,$$

that is

$$S_{\lambda F + \mu G} \geq (\lambda \sqrt{S_F} + \mu \sqrt{S_G})^2.$$

(we used the inequality $p + q \geq 2\sqrt{pq}$). It is impossible to obtain any restrictions other than inequality (2) on the values ​​of $S_{\lambda F} + \mu G$ for given $S_F$ and $S_G$. Indeed, putting in (2) $b = a$, $c = ke$, $d = e|k$ ($k$ is some positive number), we get: $S_F = a^2$, $S_G = e^2$, $S_{\lambda F} + \mu G = \lambda^2 a^2 + \mu^2 e^2 + \lambda \mu e \left( k + \frac{1}{k} \right) = (\lambda a + \mu e)^2 + \left( k + \frac{1}{k} - 2 \right) \lambda \mu e$.

With $a$, $e$ and $\lambda$, $\mu$ fixed, the second parenthesis takes any non-negative value (depending on $k$), so $S_{\lambda F} + \mu G$ can take any value, no less than $(\lambda \sqrt{S_F} + \mu \sqrt{S_G})^2$.

Now we can finally give the answer to the question in problem M330: the area of ​​the resulting convex polygons of areas $S_1$ and $S_2$ can take any value greater than or equal to $(\sqrt{S_1} + \sqrt{S_2})^2/4$.

The fact that the resulting area cannot take a smaller value follows from the following remarkable theorem.

Brunn-Minkowski theorem. Unequal (2) execution for any two convex figures $F$, $G$ and any positive numbers $\lambda$, $\mu$.

Proof. First of all, using similarity considerations and formula (1), it is easy to reduce to the case when the areas of the given figures are equal, and the linear combination is normalized. For this case, inequality (2) looks very simple:

$$\text{если } S_F = S_G = S \text{ и } \lambda + \mu = 1, \text{ то } S_{\lambda F} + \mu G \geq S.$$

Let us show how inequality (2) is derived from (3) for any $F$, $G$, $\lambda$ and $\mu$. Let's look at the figures of area $S$ together with $F$ and $G$:

$$F^* = \sqrt{S/S_F} F, \quad G^* = \sqrt{S/S_G} G.$$

⟦folio 29⟧

Then
$$\lambda F + \mu G = \lambda \sqrt{S_F/S} F^* + \mu \sqrt{S_G/S} G^* = \left( \lambda \sqrt{S_F/S} + \mu \sqrt{S_G/S} \right) \left( \lambda^* F^* + \mu^* G^* \right),$$
where $\lambda^* + \mu^* = 1$. Applying (3) to $\lambda^* F^* + \mu^* G^*$ we get (2):
$$\sqrt{S_{\lambda F} + \mu G} \geq \left( \lambda \sqrt{S_F/S} + \mu \sqrt{S_G/S} \right) \sqrt{S} = \lambda \sqrt{S_F} + \mu \sqrt{S_G}.$$

Here is the main message used to prove inequality (3). If the figure F is divided by the horizontal line $l$ into two parts: the upper $F_B$ and the lower $F_H$, and similarly, the G of another horizontal line $m$ is divided into two parts $G_B$ and $G_H$, then the set $\lambda F_B + \mu G_B$ and $\lambda F_H + \mu G_H$ do not overlap each other: the first lies above the line $\lambda l + \mu m$, the second is below.

Now the proof in a nutshell can be completed like this.

Let's divide the polygons $F$ and $G$ into $N$ narrow horizontal strips and number them in order from top to bottom: $F_1 \cup F_2 \cup ... \cup F_N = F$, $G_1 \cup G_2 \cup ... \cup G_N = G$. Each strip can be considered a straight line of area $S/N$ (if $N$ is large, this “up to an arbitrarily small ε” does not affect the areas of figures $F$, $G$ and $\lambda F + \mu G$). But for rectangles with parallel sides, the main inequality (2) has already been proven, therefore the area of ​​each of the strips $\lambda F_i + \mu G_i$, $i=1,2,...,N$ (we add only strips with the same numbers!) is not less than $S/N$. And since these $N$ strips do not overlap each other and, of course, are contained in $\lambda F + \mu G$, then the area of ​​$S_{\lambda F} + \mu G$ is no less than $S$.

So, the Brunn-Minkowski inequality is proven. We present here only one of its consequences. This is also a replacement for the operator theorem: the area of ​​any figure with perimeter $P$ is no more

higher than the area of ​​the crud with circumference $P$. Let us prove it for the convex polygon $F$. Using the notation and the result of Problem 8, we apply Brunn’s inequality to the sum $F + K$ (K is a circle of unit radius). We get:

$$\sqrt{S + P + \pi} \geq \sqrt{S} + \sqrt{\pi},$$

or, after simplification, $S \leq P^2/4\pi$. This is the desired inequality!

Problem 12. a) Prove that for the areas of a linear combination of two convex polygons the formula $S_{\lambda F} + \mu G = S_F \lambda^2 + 2S_F G \lambda \mu + S_G \mu^2$ is true, where the number $S_F,G$ depends only on $F$ and $G$ (this number is called the mixed area of ​​the figures $F$ and $G$). Find $S_F,G$ for figures $F$, $G$ from problem 2a) - e).

6) Prove that $S_F,G \geq S_F S_G$ is always, and the equality holds only if the polygons $F$ and $G$ are prepared.

Problem 13. Prove that inequality (2) is true for arbitrary figures (not necessarily convex). Think about how to formulate and prove a similar theorem for the volumes of spatial figures.

To conclude our famous introduction to the Minkowski sum, we list some books and articles that talk about the addition of figures, the application of this operation to the theory of convex sets, in particular, about various proofs of the Brunn-Minkowski inequality, its generalization and geometric consequences.

I. M. Yaglom, V. G. Boltyansky. “Convex figures” (book from the “Mathematics Circle Library” series, issue 4). Gostekhteorizdat, 1951

L. A. Lyusternik. "Convex figures and polygons." Gostekhteorizdat, 1956

B. N. Delaunay. Proof of the Brunn–Minkowski inequality. "Success of Mathematical Sciences", vol. II (1936).

N. B. Vasiliev. A family of parallel $n$-gons. «Kvant», No. 11, 1974; decision problem M295, «Kvant», No. 6, 1975

G. Hadwiger. Lectures on volume, surface area and isopermethrins. M., “Hayka”, 1966
