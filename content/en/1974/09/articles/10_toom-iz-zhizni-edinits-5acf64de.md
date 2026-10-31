---
id: 1974-9-toom-iz-zhizni-edinits-5acf64de
issue: kvant_1974_9
year: 1974
number: "9"
title: From the life of units
authors:
  - Тоом А. Л.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 33
page_last: 41
page_labels: 31, 32, 33, 34, 35, 37, 38, 39
tag: 0T22
lang: en
source: kvant_digital
extraction: vision
content_sha256: 2ff12966f5b9bf1046a62c8f4e06876538e95d77dd4614a4ea643cabfcacf498
prompt_sha256: draft-1
translated_from: content/ru/1974/09/articles/10_toom-iz-zhizni-edinits-5acf64de.md
source_content_sha256: 64a02d5b3cb8639eb8c6fd21d36b3f24a719fd542f0369e8c39125ba65b4cc56
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 31⟧

From the life of one
A. L. Toom

Alas! - said Saturnits,
- we live only five hundred
large revolutions of the Sun...
Our existence is a period, a period
our life - opinion, our
planet - atom.

Voltaire. "Micromedas".

Not long ago it became known that some, at first glance, completely different phenomena and processes occurring in life, for example, the transformation of polymers, the vital activity of biological tissues, the growth of crystals, and even the operation of a computer that calculates the derivative in all working cells (such a computer is not shown, but it would be very tedious to build one), nevertheless have something in common. This commonality is revealed when an attempt is made to describe these processes in the language of mathematics, to create what scientists call a mathematical model.

The famous Soviet physicist Ya. I. Frenkel said that the mathematical model should be more like a caricature than a “realistic” figure. The main requirement for the model is simplicity: life processes are infused with mathematics, to create something that is difficult for scientists to study mathematically. Currently, the so-called “lattice models” have become more popular, describing processes that produce identical “cells” on a sieve. In such models, difficulties arise even when each cell can be in only two states. We will talk about this in the article.

1. Colonies and operators

For mathematicians, checkered paper has many attractive possibilities. Let's use one of them here. Open the page of your squared notebook. You see on it a grid of vertical and horizontal lines. For brevity, we will call their intersection points nodes. Let's imagine a world that consists only of all these nodes. True, let us imagine the page as endless. Let some shchetva: units live in these nodes. In the figures, we will denote units with bold dots, as in figure 1. Each node can contain only one unit at a time, and if there is no unit in the node, then there is a zero there. The set of all nodes occupied by units will be called colonies. If one is a finite number, then the column is called finite. If there is not a single unit, then we will say that we have an empty colony. (Time, like space, is discrete. This means that it is numbered with integers: 0, 1, 2,...) An operator P must be specified, that is, a rule that for any colony K, exists at some time t, determines which colony PK will turn out from it at the next time t + 1.

Let such an operator P be given. The main question we will try to figure out is this. For a given operator P, does there exist an immortal finite colony, that is, a dummy finite colony K such that, no matter how many times the operator P is applied to it, the result will always be an inadvertent colony? Or, as a set, the operator P can mean that every finite colony dies out after some time, that is, not a single unit remains?

Let's look at two examples first. Let's enter the coordinates of the axis by taking one of the nodes as the origin of coordinates O and directing, as usual, the abscissa axis to the right, the ordinate axis upward (see Fig. 1) and taking the side of the cell as one.

⟦folio 32⟧

Example 1. Let at moment $t + 1$ there be a unit in node $A = (x, y)$ if and only if at moment $t$ more than five nodes were occupied by ones: this node $A$ and four adjacent to it: on the right $(x + 1, y)$, on the left $(x - 1, y)$, on top $(x, y + 1)$ below $(x, y - 1)$. The $P$ operator is given.

Exercise 1. What do the colonies shown in figure 1 (“bold” dots and crosses) generate under the influence of this operator? Trace the further evolution of the colony. Is there an immortal finite colony for this operator?

Example 2 (see problem M215). Let there be a unit at the moment $t + 1$ in the node $A = (x, y)$ if and only if at the moment $t$ more than three nodes were occupied by ones: this node $A$ and two neighboring ones: on the right $(x + 1, y)$ and on top $(x, y + 1)$. The $P$ operator is given.

From the solution to problem M215 (published in «Kvant» No. 3, 1974) it follows that under the action of this operator any finite colony dies out. (Check it out for the colony at Fig. 1). Let us prove this fact once again in a way that will be useful to us later.

Let us study the evolution of colonies of a special type that fill an equilateral right triangle with legs directed to the right and upward from the vertex of the right angle (Fig. 2). It turns out that such a triangle at the next moment of time transforms into a triangle of the same type, but with a length of legs less by one. Only the smallest triangle with leg length 1 goes to one point, and it disappears at the next step. (Check this by tracing the evolution of figure 2.) Therefore, what kind of triangle dies out in a time equal to the original length of the legs.

Let us now have an arbitrary finite colony $K$. It can be enclosed in an equilateral right triangle, which is done at figure 3. Then the colony resulting from it at the next moment will be placed inside a smaller triangle of the same type, and so on.

Here we will use an important property of the operator $P$: if colony $K_1$ is part of colony $K_2$ (this can be written as $K_1 \subset K_2^*$), then $PK_1$ is part of $PK_2$: $PK_1 \subset PK_2$ (which does not exclude the possibility that $PK_1$ and $PK_2$ coincide). Naozem is a property that can be briefly written as follows:

$$K_1 \subset K_2 \Rightarrow PK_1 \subset PK_2,$$

monotonicity of the operator $P$. This article only covers monotonic operators.

For non-monotonic operators, the question of when immortal finite colonies exist is not solved in general terms and may be very difficult. Interesting and general material about the study of one specific non-monotonic operator, called the game “Life”, is collected in the book “Mathematical Leisure” by M. Gardner (Chapter 38). You can get acquainted with this game on p. 26 of this issue of the magazine.

Let us now describe exactly what type of operator $P$ we will consider.

*) The sign $\subset$ means inclusion of a set. We will also continue to use understandable intersections, unions and complements of a set (on operations on sets, see, for example, the article by S. G. Gindin and “How many operations on sets exist,” «Kvant», 1973, No. 7).

⟦folio 33⟧

Let $O$ be the “zero” node, the origin. The description $\mathbf{P}$ includes a *list* $\mathbf{U}$, consisting of $r$ nodes $u_1, \dots, u_r$, the states of which at time $t$ determine the state of node $O$ at time $t + 1$. In example 1 the number of these nodes is $r = 5$, in example 2 $r = 3$. The state of any node $A$ at time $t + 1$ depends on the state of nodes $A + u_1, \dots, A + u_r$ at time $t$. The + sign here means vector addition. For example, if $A = (x, y), u_1 = (x', y')$, then $A + u_1 = (x + x', y + y')$.

Exercise 2. Write the coordinates of the vectors $u_1, \dots, u_5$ in example 1 and the vectors $u_1, u_2, u_3$ in example 2.

In addition to the list $\mathbf{U}$, the specification of the operator $\mathbf{P}$ includes a function that determines exactly how the state of node $A$ at time $t + 1$ depends on the state of nodes $A + u_1, \dots, A + u_r$ at time $t$. To define such a function, you need to indicate what will be in node $A$ at time $t + 1$—one or zero—for each combination of ones and zeros in nodes $A + u_1, \dots, A + u_r$ at time $t$. There are $2^r$ such combinations. You can, for example, create a table in which you put either a one or a zero against each combination of ones and zeros, which is what you did on figure 4 (check that the function defined by this table defines the operator $\mathbf{P}$ from Example 2).

| Node states | At moment $t$ | $t + 1$ |
| :--- | :--- | :--- |
| $(0,0)$ | $(0,1)$ | $(1,0)$ | $(0,0)$ |
| 0 | 0 | 0 | 0 |
| 0 | 0 | 1 | 0 |
| 0 | 1 | 0 | 0 |
| 0 | 1 | 1 | 1 |
| 1 | 0 | 0 | 0 |
| 1 | 0 | 1 | 1 |
| 1 | 1 | 0 | 1 |
| 1 | 1 | 1 | 1 |

Fig. 4.

Of course, it is not necessary to create a table; you can define the function in a complex way, but in such a way that for a complex task it would be possible to unambiguously create such a table.

Functions $f = f(a_1, a_2, \dots, a_r)$ whose arguments and values ​​take only two values, 0 and 1, are called *Boolean or double*. A Boolean function is said to be *monotonic* if

$$a_1 \leqslant a'_1, \dots, a_r \leqslant a'_r$$

should

$$f(a_1, \dots, a_r) \leqslant f(a'_1, \dots, a'_r).$$

As already mentioned, we will only consider monotonic operators. They are specified by monotonic functions. In addition, we set $f(0, \dots, 0) = 0$, $f(1, \dots, 1) = 1$.

These restrictions do not exist, since the only monotonic functions that do not satisfy them are constants - functions that take only one value (always zero or always one). Constant functions are very simple and therefore uninteresting.

Example 3. Let there be a zero at moment $t + 1$ at node $A = (x, y)$ if and only if at moment $t$ at least one of two conditions is met:

a) zeros are at common nodes $(x, y)$ and $(x, y + 1)$;
b) zeros are at common nodes $(x + 1, y)$ and $(x + 1, y + 1)$.

The $\mathbf{P}$ operator is specified.

Exercise 3. a) Trace the evolution of the columns shown in figure 1 under the action of this operator.

Isn’t it true, the impression is created that the columns are continuous on the right side, but the impression is set in motion?

b) Prove that under the action of the operator of Example 3, every finite column dies out.

Example 4. Let at the moment $t + 1$ there be a zero at the node $A = (x, y)$ if and only if at the moment $t$ at least one of two conditions is satisfied:

a) zeros are at common nodes $(x, y)$ and $(x + 1, y + 1)$;
b) zeros are at common nodes $(x + 1, y)$ and $(x, y + 1)$.

The $\mathbf{P}$ operator is specified.

⟦folio 34⟧

Fig. 5. Fig. 6.

For this operator, there are petless finite colonies, which, it is true, are constantly changing, but in no way dying out. Find one of them.

2. Null sets.
Survival theorem

Let us now remember that on the plane, in addition to nodes, there are also other points. Of course, from the point of view of individuals living only in nodes, no other points exist in nature, but for us they exist. We will consider all kinds of geometric figures - sets of points on a plane. Let's say that a figure M is filled with zeros if all nodes belonging to this figure have zeros.

Definition 1. A figure M is called zero (for a given operator P) if from the fact that it is filled with zeros at time t, it follows that node O will have a zero at time t + 1.

So, in examples 1, 2, a figure is zero if it contains a majority of the five - in example 1 - or three - in example 2 - nodes that make up the set U.

Let a straight line l be drawn on the plane. Let us semi-permanently define the set of points located on one side of a line, including this line itself.

In accordance with Definition 1, a half-space is called zero if, from the fact that it is filled with zeros at time t, it follows that there will be a zero at node O at time t + 1.

Let us denote by σₚ the intersection of all half-spaces that are zero for a given operator P.

Survival theorem. Under the action of the operator P, any finite colony model and molecular mode die out if the set σₚ is empty.

Exercise 4. (Check the theorem for examples 1-4.) Prove the following statements.

a) In Example 2, the three half-lines protected on figure 5 are zeros. In Example 3, the two half-planes protected on figure 6 are zeros.

In either case, protected half-lines do not have common points, that is, their intersection is empty. Therefore σₚ is the intersection of all zero half-spaces, all the more empty. According to the theorem, all finite colonies die out.

b) In Example 1, the set σₚ consists of one point O (and in accordance with the theorem, there is a petless finite colony).

In Example 4, the set σₚ consists of one point ξ = (1/2, 1/2). (Point ξ is not a node. That's why we didn't have enough nodes!)

In example 1, point O enters σₚ, and the final petless colony remains in place. In Example 4, the simplest petless colony consists of four nodes—the vertices of one unit square (Fig. 7). At the next moment of time it generates a “cross”, and this cross, in turn, is the same as a square, but with a diinut

⟦folio 35⟧

one unit to the left and down. Let us add that the colony $K$ fills the figure $M$ if it contains all the nodes included in $M$. Both the cross and the square on figure 7 can be thought of as colonies filling the equal shapes—the squares—shown in these pictures. Thus, colonies spawned at successive times can be represented as filling the same square, shifting ασs per unit time by the vector $-\vec{\xi} = \left(-\frac{1}{2}, -\frac{1}{2}\right)$. Note that the sides of this square are parallel to the lines $u_i$ and $\xi$, where $u_i \in U$. In example 1, the sides of the unit square filled by the colony are also parallel to the lines $u_i O$.

U pravannye 5 (production) If you were one and lived in a world controlled by the operator of example 4, would the point $\xi = \left(\frac{1}{2}, \frac{1}{2}\right)$ exist for you or not?

3. Set convexes and hull convexes

A set of points $M$ on a plane is called convex if it satisfies the following conditions:

if the points $A$, $B$ belong to $M$, then all points of the segment with endpoints $A$, $B$ belong to $M$.

Right 6. Prove that every half-plane is a convex set.

Right 7. Prove that the intersection of several convex sets is a convex set.

Right 8. In some conditions, a polygon is called convex if it is located on one side of a straight line drawn through each of its sides. Prove that a polygon will be convex in this sense if and only if the set of points located on its contour and inside it is convex.

So, if the convex set $M$ contains points $A_1, \dots, A_h$, then it also contains all line segments with endpoints at these points, and all triangles with vertices at these points. The union of all points $A_1, \dots, A_h$ on the plane, segments with endpoints at these points and triangles with vertices at these points is called the convex hull of points $A_1, \dots, A_k$ (at figure 8 the convex hull of points $A_1, \dots, A_k$ is shaded). We can say that the convex hull of the points $A_1, \dots, A_k$ is something that must be included in all convex sets containing the points $A_1, \dots, A_k$.

Right 9. a) Prove that a set consisting of four points (on a plane) can always be divided into two subsets whose convex hulls intersect.

6) The same if the set consists of $n > 4$ points.

Let us recall the definition of the set $\sigma_P$. If we search for $\sigma_P$ following this definition, we will have to construct all the zero half-planes, and there are infinitely many of them. True, in Examples 1-4 we summed up finding $\sigma_P$, but it is not yet clear how to do this in the general case. It turns out that with the help of convex hulls it is possible to construct $\sigma_P$ for any operator $P$.

Consider all subsets $U$. In accordance with Definition 1, a set $U' \subset U$ is called zero if from the fact that $U'$ is filled with zeros at time $t$, it follows that at point $O$ there will be a zero at time $t + 1$.

Lemma 1. The set $\sigma_P$ coincides with the intersection of the convex hulls of all zero subsets $U$.

Prove this lemma yourself. Not indicated. A half-plane is null if and only if it contains at least one null subset $U$.

Using Lemmo 1, we can construct $\sigma_P$ for any operator $P$ given by the set $U$ and the function $f$. Namely, we need to write down all the subsets $U$ (there are $2^r$ of them), then, knowing the function $f$, select the zero ones from them, construct their convex

⟦folio 37⟧

Fig. 12.

after $t$ applications of the operator $P$ according to the following remarks and because of edom the half-planes receiving from $\Pi'_1, \Pi'_2, \Pi'_3$ shifts by $t v_1, t v_2, t v_3$ will be filled with zero; for $t \geq d$ these half-planes cover the entire plane. This means that the entire plane will be filled with zero, and this means that the colony $K$ is dying out.

Lemma 3. Let two half-planes bounded by two parallel lines and located on the outer sides of them be zero for the operator $P$ (as in Fig. 6). Then, under the action of this operator, every finite colony of individuals dies out.

Prove this lemma yourself. Not indicated. Summarize the solution to Exercise 3.

Lemmas 2 and 3 can be combined into the following statement:

Lemma 4. If the intersection of three zero half-planes is empty, then every finite colony of units dies out.

Proof. If the intersection of three half-planes is empty, then either they are located as on figure 10, or some two of them are located as on figure 6, and for these two cases the statement of Lemma 4 is proven.

B. Now let the set $\sigma_p$ contain at least one point. Let us prove that then there exists a finite dimensionless colony.

Lemma 5. Let the infinite colony $K$ be filled $t$ by the half-plane $\Pi$, which has at least one common point with the set $\sigma_p$. Then the colony $PK$ contains the node $O$.

Proof. Let us assume that $PK$ does not contain $O$. This means that at moment $t + 1$ there is 0 at point $O$, that is, at moment $t$ some zero subset $U$ was completely filled with zeros. This means that this zero subset did not have a single common point with $\Pi$, that is, it additionally belonged to $\Pi$. But the complement of $\Pi$ is a convex set. Therefore, the convex hull of this zero subset also belonged entirely in addition to $\Pi$. This means (see Lemma 1) $\sigma_p$ belonged entirely in addition to $\Pi$, which contradicts the conditions.

Consequence. Let the infinite colony $K$ be filled with a half-plane $\Pi$ that has at least one common point with the set $A + \sigma_p$, where $A$ is a node. Then the colony $PK$ contains the node $A$.

The main one for case B is Lemma 6. Let the point $\xi$ belong to $\sigma_p$ (like the point $(1/2, 1/2)$ in Example 4). Then there exists a convex polygon $M$ such that if colony $K$ is filled by $M$, then colony $PK$ is filled by polygon $M - \vec{\xi}$ (Fig. 12), colony $P^2 K$ is filled by $M - 2\vec{\xi}$, and so on; in general, a colony $P^n K$, obtained from $K$ through $n$ moments of time, a filled polygon $M - n\vec{\xi}$, equal to $M$ and obtained from $M$ with a connection to the vector $-n\vec{\xi}^*$). Moreover, all colonies $K$, $PK$, $P^2 K$, ... are non-empty.

*) We claim that all nodes belonging to $M - n\vec{\xi}$ are occupied by units, but perhaps not only them: it is possible that there will be units outside this mnestagon.

⟦folio 38⟧

From this lemma, in particular, it follows that if the point $O$ belongs to $\sigma_p$, then there is a “stable” colony that does not lose any of its nodes in the process of evolution (but, possibly, gains new ones).

Proof. Note that we do not claim to have found the smallest immortal colony (as we found for Examples 1 and 4). All we have to do is find one. Therefore, from the very beginning we will assume that the polygon $M$ is very large. We'll tell you exactly what below.

It is enough to prove the statement of the lemma only for $n = 1$; for large $n$ this will follow by induction. So suppose that the colony $K$, existing at time $t$, is filled by $M$; Let us prove that the colony $PK$ fills the polygon $M - \xi$.

Let some node $A$ belong to $M - \xi$ (see Fig. 14). Let us show that $A$ belongs to $PK$ (this is written like this: $A \in PK$). Obviously $(A + \xi) \in M$. Let us denote by $R$ the longest distance from the point $\xi$ to the nodes $u_1, \dots, u_r$. Then a circle with center $A + \xi$ and radius $R$ will cover all nodes $A + u_1, \dots, A + u_r$. Let us choose $M$ columns so that any circle with center inside $M$ belonging to $R$ either does not cover a point on the side of the polygon $M$, or covers points of only one side $M$, or covers points of only two adjacent sides, but no more. (On figure 13 there is a circle covering the points of three sides of a triangle - this should not happen!) Let's consider three cases.

a) A circle with center $A + \xi$ of radius $R$ is placed entirely inside $M$ (see Fig. 14). Then all nodes $A + u_i$ are especially inside $M$, that is, they are included in $K$; this means that node $A$ is included in $PK$.

b) A circle with center $A + \xi$ and radius $R$ covers points on only one of the sides $M$ (as in figure 15). Let's draw a straight line $l$ through this side. If the colony $K$ fills the entire half-plane $\Pi$ bounded by $l$ (at figure 15 this half-plane is protected), then the colony $PK$ would contain the node $A$ by corollary to Lemma 5 (the half-plane $\Pi$ contains point $A + \xi$, and therefore intersects with the set $A + \sigma_p$). But the colony $PK$ will contain node $A$ even if $K$ fills only $M$, since the state of node $A$ at time $t + 1$ depends only on the state of nodes $A + u_i$ at time $t$, and these nodes are not included in the difference between $\Pi$ and $M$.

b) A circle with center $A + \xi$ of radius $R$ covers the points of two adjacent sides $M$ (see Fig. 16). We want to prove that in order for there to be a unit at node $A$ at time $t + 1$, it is sufficient that at time $t$ there are units at those points

⟦folio 39⟧

Fig. 16.

$A + u_1, \dots, A + u_r$, which fall into the area of ​​intersection of $M$ with the circle. We will prove that in fact, for this it is enough to have units even in a smaller area - the intersection of the same circle with a polygon $M'$ obtained from $M$ such a digon such that the common vertex of two adjacent sides $M$, part of which is covered by the circle, falls at the point $A + \xi$ (Fig. 16). To do this, we need to impose one more, now last, condition on $M$.

Let's draw straight lines through the point $\xi$ and each of the nodes $u_1, \dots, u_r$, different from $\xi$ (if all $u_i$ are different from $\xi$, then we get $r$ straight lines; if one of them coincides with $\xi$, then we get $r - 1$ straight line). They will require that for each of these ($r$ or $r - 1$) lines, find two sides of the polygon $M$ parallel to it. Then each line parallel to the line passing through $\xi$ and any point $u_1, \dots, u_r$ other than $\xi_2$ either does not intersect $M$ at all, or has a whole common segment with $M$. This condition, for example, is satisfied by the square on figure 7 (example 4).

Let us now draw through the point $A + \xi$ a line $l$, which has only one common point $A + \xi$ with the polygon $M'$ (see Fig. 16). If only $K$ fills the entire populian $\Pi$ bounded by the line $l$ (at figure 16 it is shaded blue), then by the corollary of Lemma 5, at the point $A$ at the moment $t + 1$ there would be one. But the colony $PK$ will contain the node $A$ even if $K$ fills only $M$, since there are no nodes $A + u_i$ lying in the populian $\Pi$, but outside $M'$. Let's prove it. Let us assume that some node $A + u_i$ is in the difference between $\Pi$ and $M'$. But at the same time, it is located in a circle with center $A + \xi$ of radius $R$. This means that node $A + U_i$ lies in one of the two sectors shaded in black. Then the line passing through $A + u_i$ and $A + \xi$ has only one common point $C'$, which is impossible due to the choice of $M$. This proves Lemma 6.

B. Helly's theorem. So, we also examined two cases:

A) let the intersection of some three zeros be populian (lemma 4);

B) Let the intersection of all zeros be populian (Lemma 6).

It turns out that these are the only cases and possibilities. This follows from the famous Helly theorem.

This is a very important and beautiful theorem, which has many different formulations, proofs and applications. We will need it only in the next version (for its proof, see p. 77).

Helly's theorem. Let there be $n \geq 4$ convex sets on the plane, some of which have a common point. Then all these $n$ sets have a common point.

Let's apply it to our case. By the corollary to Lemma 1, it is possible that $\sigma_p$ is the intersection of a finite number Populian, and this is the case $A$. Thus, the survival theorem is proven.
