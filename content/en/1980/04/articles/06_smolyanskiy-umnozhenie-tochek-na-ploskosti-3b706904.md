---
id: 1980-4-smolyanskiy-umnozhenie-tochek-na-ploskosti-3b706904
issue: kvant_1980_4
year: 1980
number: "4"
title: Multiplication... of points on a plane
authors:
  - Смолянский М. Л.
rubric: osnovnye-stati
page_first: 21
page_last: 24
page_labels: 19-22
tag: AXNS
lang: en
source: kvant_digital
extraction: vision
content_sha256: 80ed6a67ba780618962995232fc0272983f39059381f755efed51e98a6934814
prompt_sha256: draft-1
translated_from: content/ru/1980/04/articles/06_smolyanskiy-umnozhenie-tochek-na-ploskosti-3b706904.md
source_content_sha256: 7b8e9f0fdd875d3774fd0a804d8552f416ec52e15642028c85d2d62d6194e1cb
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 19⟧

M. Smolyansky

Multiplication...
points on the plane

“Multiplying points—is that possible? - the surprised reader will ask. “After all, they multiply (and add) numbers, not points!” It is easy for such a reader to object: first, real numbers are often considered as points on a number line, so in this sense one can multiply points; secondly, in modern mathematics they multiply not just points, but almost anything: functions, matrices, displacements...

In this article we will try to show the reader how and why you need to multiply points on a plane. On this path we will obtain a geometric model of complex numbers and study some of their properties. And besides, we will show that it is no longer possible to intelligently multiply points in space.

Before learning how to multiply points on a plane, it will be useful to look...

How to multiply points on a line
To add two points on a straight line, it is enough to function

start $O$: then the points can be added as vectors. If we fix the point $A$ and add it to each point $X$ on the line, we obtain a mapping $X \rightarrow X + A$ of the line onto itself. It is clear that this will be a parallel transfer of the entire line to the vector $\vec{OA}$ (Fig. 1a). For multiplication, the unit $1$ must also function: then coordinates are acquired, and with their help points can be multiplied (like numbers); Moreover, as is easy to see, the multiplication of all points of the line by the functioned point $A$ is an etometry with center $O$, which takes the point $1$ to the point $A$ (Fig. 1, 6).

Let's define multiplication on the plane

First of all, let's find out what kind of multiplication we want to define on our plane, in which the number axis $Ox$ with unit $1$ (Fig. 2) has already been selected. (Note that the addition of points is already defined: the presence of the origin $O$ allows the points to be added as vectors, according to the parallelogram rule.) We, of course, want the new multiplication to coincide with the one already on the $Ox$ axis (we will call this axis the real one). Therefore we will require:

I. Multiplication by any point $A$ of the real axis $Ox$ is a geometry with center $O$ and coefficient $x$, where $x$ is the abscissa of point $A$.

But this, of course, is not enough. We also need our multiplication to have the general properties of arithmetic operations. Exactly:

II. Multiplication is associative, distributive with respect to addition, and division by any point $A$ other than $O$ is defined.

Let's write down these properties in more detail:

Pa. Associativity. For any points $A, B, C: A(BC) = A(BC)$.

Fig. 1.

⟦folio 20⟧

Pis. 2.

IIb. Distributivity. For any points $A, B, C$

$$A(B+C) = AB+AC,$$
$$ (B+C)A = BA+CA.$$

II century Division (existence of inverse). For any (other than $O$) point $A$ there is a point $A^{-1}$ also, such that

$$A^{-1}A = AA^{-1} = 1.$$

So, we need to construct a multiplication operation on the plane that satisfies conditions I and II. Stop: don’t read further yet, but first think about how to do this.

Well, did you come up with it? Of course, the easiest way to define multiplication is “the same” as for points on the real axis. Namely, multiplication by the point $A$ is a semblance of a plane that takes point 1 to point $A$, leaving point $O$ in place and preserving the orientation. You can clearly imagine that we rotate the plane near the beginning so that the ray [O1) coincides with the ray [OA], and then we make a finished one that transfers point 1 to point $A$.

It is clear that for such multiplication condition I is satisfied.

Exercise 1. Prove that II is also true and, moreover, multiplication is commutative.

Before reading further, understand how multiplication by specific points, for example, $I(0,1)$, $J(-1,0)$, $C(1,1)$, works.

One will naturally ask whether the multiplication we introduced is the only one that has properties I and II.

Exercise 2*. Prove that such multiplication is not unique.

If this exercise does not work out, we advise you to return to it after reading further. In the next section we reveal in space?

Like the plane, our space first has a number axis $Ox$ with unit 1; we will look for multiplication that satisfies the same conditions as in the previous section, that is, to answer the following question: is it possible in the space of a thing to multiply that satisfies conditions I and II?

Inspired by the previous conditions, you will say: of course, you can, in the same way as before: multiplication by the point $A$ is a kind of space that takes 1 to $A$ and $O$ to $O$. But there's a little snag here:

Exercise 3. Show that for $A$ not lying on the real axis, there are an infinite number of such similarities.

Which one should I take? Let’s take any, the optimist will say. To this we will object to him that it is unlikely that anything good will come out of this: after all, multiplications by different points must be consistent (so that condition II is satisfied). How to reconcile them?

Don't try - it won't work. The fact is that multiplication in space with properties I and II does not exist! We will prove this by contradiction.

Let's say we managed to determine some multiplication. Let's take an arbitrary point $X$ outside the axis $Ox$ and consider its degree $X^2$ and $X^3$ (that is, points $X \cdot X$ and $(X \cdot X) \cdot X$).

By virtue of one of the axioms of geometry proposed by G. Weylem (“Geometry 9–10”, p. 234), for any four vectors of the space $\vec{a}, \vec{b}, \vec{c}, \vec{d}$ one can find real numbers $k, l, m, n$, not all equal to zero, such that the equality

$$k\vec{a} + l\vec{b} + m\vec{c} + n\vec{d} = \vec{0}.$$

Let us apply this fact to the four vectors connecting the point $O$ to the four points $1, X, X^2, X^3$; then there are real numbers (in our terminology -

⟦folio 21⟧

Fig. 3.
points of the real axis) $A, B, C, D$ such that the equality holds:
$$A + BX + CX^2 + DX^3 = 0$$
(1)

Pravanitsa has 4. Explain why $A \cdot 1 = A$.

Now we need the following fact:
Pravanitsa has 5*. Any third degree equation has a real root.
(If you find it difficult to solve this equation, see «Kvant», 1980, No. 2, p. 20.)

Let us denote this root (a point on the real axis) by $X_0$; then for some numbers (points on the real axis) $C', B'$
$$X - X_0) (DX^2 + C'X + B') = A + BX + CX^2 + DX^3.$$

Since the product of non-zero factors cannot give zero (this follows from condition Pa, PV: if $Q \neq 0$, $P \neq 0$ and $P \cdot Q = 0$, then $0 = 0 \cdot Q^{-1} = P \cdot Q \cdot Q^{-1} = P \cdot 1 = P \neq 0$), one of these brackets is equal to zero. Since $X$ is not a “real” point, $D \neq 0$ and points 0, 1, $X$ and $X^2$ lie in the same plane. Let us consider the point $Y$, which does not lie in this plane (Fig. 3).

Consider four points 1, $X$, $Y$, $YX$, lying in space; once again applying the (same) axiom, one can select points $B_1$, $B_2$, $B_3$, $B_4$ on the real axis, not all equal to zero, such that
$$B_1 + B_2X + B_3Y + B_4YX = 0.$$

Otherwise it can be written like this:
$$(B_1 + B_2X) + Y(B_3 + B_4X) = 0.$$ (2)

Note that in the plane containing 0, 1, $X$, there is a point $Y_0$ satisfying (2).

Fig. 4.
Pravanice has 6. Write it as $C_1 + C_2X$ and find $C_1$ and $C_2$ using equations $DX^2 + C'X + B' = 0$.

But then $(Y - Y_0)(B_3 + B_4X) = 0$, whence $Y = Y_0$, that is, the point $Y$ lies in the plane outside of which it was chosen. Contradiction. There is no multiplication in space that we need!

For those who know what a four-dimensional space is, we note that it is possible to introduce multiplication in it (satisfying conditions I and II), but this multiplication will not be commutative. It's not easy, but try it!

Let's now return to the plane. What did we get there?

Points as complex numbers

We will assume that the real line is horizontal, and consider a vector of unit length sticking up (Fig. 4). Let's denote it by $i$. It is easy to see that $i^2 = -1$. So, for the plane we solve the equation $x^2 + 1 = 0$; Having expanded the real straight line to a plane, we were able to solve an equation that is not solvable for a straight line.

Any point in the plane can be written as $a + bi$, where $a$ and $b$ are real points; addition and multiplication of a point written in this way is given by the formulas:
$$(a_1 + ib_1) + (a_2 + ib_2) = (a_1 + a_2) + i(b_1 + b_2),$$
$$(a_1 + ib_1) \cdot (a_2 + ib_2) = (a_1a_2 - b_1b_2) + i(a_1b_2 + b_1a_2).$$

U pravanice 7. Derive these formulas from geometric definitions.

⟦folio 22⟧

Fig. 5.

These formulas show that our points, their addition and multiplication are a geometric model of complex numbers *). It is easy to obtain such a remarkable fact: any equation $AX^2 + BX + C = 0$ (where $A, B, C$ are points of the plane and $A \neq 0$) is cut - there is a point on the plane that turns it into an identity. In fact, any algebraic equation can be cut on the plane (see «Kvant», 1980, No. 2, p. 17).

Exercise 8. Write a formula for solving quadratic equations on a plane.

Formulas for roots of the $n$th degree

As you know, for real numbers, and therefore for a real line, the equation $X^n = A$ for $A \neq 0$ and even $n$ is not always cuttable. Moreover, it is either not cuttable, or cuttable between two meanings. (For example, 1 and -1 squared give one.) For the condensation plane it is much more elegant: for each non-zero point $A$ the equation $X^n = A$, $n$ is a natural number, there are exactly $n$ roots.

In order to prove this, we will first learn to raise to powers the points lying on the circle $\Gamma$ of unit radius with center at zeros (Fig. 5). This circle has such a remarkable property: the product of two points from $\Gamma$ is again a point of the circle $\Gamma$. In fact, multiplying a plane by a point on this circle is simply a rotation centered at zeros. Since when turning a unit circle,

*) See «Kvant», 1980, No. 2, p. 17.

Fig. 6.

like all other circles with a center at zeros, transforms into itself, our statement is true. In hindsight, we got a new way of recording a rotation - as multiplication by the corresponding point.

Now it is clear what $X^n$ is for $X \in \Gamma$. Multiplication by $X^n$ is the composition of $n$ rotations by the angle corresponding to point $X$, so point $X^n$ corresponds to an angle $n$ times larger than angle $XO1$. So $X^n$ is the point $\Gamma$ for which

$$X^n \widehat{O1} = n \cdot X \widehat{O1}.$$

Taking into account the sign of the angle of the point $X^n$ is determined uniquely by this formula.

But now it is clear how to obtain the root of the equation $X^n = A$, if $A \in \Gamma$: this is a point $X \in \Gamma$ such that

$$\widehat{XO1} = \frac{1}{n} \widehat{AO1}.$$

Well, where are the common $n$ values? It turns out that they are hidden in this formula. Indeed, we can determine the magnitude of the angle $AO1$ up to the number of radians divisible by 2π: angles $\widehat{AO1}, \widehat{AO1} + 2\pi, \widehat{AO1} + 4\pi, \dots$, in general $\widehat{AO1} + 2\pi k$, where $k$ is an integer, correspond to the same point. And when defining $X$ for different $k$ we get different points. It is easy to see that you will get exactly $n$ different points corresponding to angles of magnitude $\frac{1}{n} \widehat{AO1} + 2\pi \frac{k}{n}$ ($k = 0, 1, \dots, n-1$). figure 6 shows the roots of the next one. It can be seen that they form the vertices of a regular heptagon.

(For the end see p. 29)
