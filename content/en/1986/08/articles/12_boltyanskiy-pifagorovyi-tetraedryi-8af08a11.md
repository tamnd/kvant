---
id: 1986-8-boltyanskiy-pifagorovyi-tetraedryi-8af08a11
issue: kvant_1986_8
year: 1986
number: "8"
title: Pythagorean tetrahedrons
authors:
  - Болтянский В. Г.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 31
page_last: 33
page_labels: 29-31
tag: YAZW
lang: en
source: kvant_digital
extraction: vision
content_sha256: 23224dce685595995149a979a8a8b38254cc5a39ec98f95b0660ff8d792410f3
prompt_sha256: draft-1
translated_from: content/ru/1986/08/articles/12_boltyanskiy-pifagorovyi-tetraedryi-8af08a11.md
source_content_sha256: 313ce3aa1d57a0328838abe3049d4985fec188f6d9f5a1997b512ccb4cad5cce
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 29⟧

Pythagorean tetrahedrons

Corresponding member of the Academy of Pedagogical Sciences of the USSR
V. G. BOLTYANSKY

Let us recall that a triangle is called Pythagorean if it has one right angle, and the ratio of any other sides is rational (then, using similarity, it is possible to obtain from it a right angled triangle with integral side lengths). By analogy with this, we will call a triangle Pythagorean if its plane angles at one of the vertices are right, and the ratio of any two edges is rational (from it, using similarity, we can obtain a triangle with right plane angles at one of the vertices and integral edge lengths).

In this note we will derive the “respect for Pythagorean tetrahedra,” that is, such a relationship with the unknowns ξ, η, ζ that any Pythagorean tetrahedron gives a rational solution to this equation, and vice versa, any rational solution to this equation gives a Pythagorean tetrahedron. And then, using this, we will find specific examples of Pythagorean tetrahedra.

Pythagorean triangles

First we give a way to describe all Pythagorean triangles. At figure 1 triangle OAB is a right angle triangle; the lengths of its legs are designated by a and b, and the length of the hypotenuse by p (we reserve the letter e for later). Number ξ = a/b+p

Let us agree to call the parameter of the right angle triangle OAB (or, more precisely, the parameter “relative leg a”). Using the correspondence p²=a²+b², we have

$$1+\xi^2 = \frac{(b^2+2bp+p^2)+a^2}{(b+p)^2} = \frac{2p^2+2bp}{(b+p)^2} = \frac{2p}{b+p}.$$

From these equalities we directly obtain formulas expressing the ratio of the sides of a right angle triangle through its parameter:

$$\frac{2\xi}{1-\xi^2} = \frac{a}{b}, \frac{1+\xi^2}{1-\xi^2} = \frac{p}{b}.$$

Problem 1. Let α be the magnitude of the angle OAB. Prove that the parameter ξ of triangle OAB is equal to tan α/2, and use this to give another proof of formulas (2).

Problem 2. Prove that the parameter ξ′ of the triangle OAB with respect to leg b (that is, ξ′ = b/a+p) is related to the parameter ξ by the correspondence ξ′ = \frac{1-\xi}{1+\xi}. Interpret this correspondence using trigonometric functions (see Problem 1).

The following statements directly follow from formulas (1) (2):

In order for a right angle triangle to be Pythagorean, it is necessary and sufficient that the number of rational. Indeed, if the triangle is Pythagogian, then from (1) it follows that ξ is rational. Conversely, if ξ is rational, then according to (2) the ratio of the sides is rational, that is, a Pythagogian triangle.

Equation of Pythagorean tetrahedra

Now let OABC be a tetrahedron whose plane angles at vertex O are right. The lengths of the edges emanating from vertex O are denoted by a, b, c, and the lengths of the other three edges by p, q, r (Fig. 2). Let's consider the parameters of three right angle triangles OAB, OBC, OCA:

$$\xi = \frac{a}{b+p}, \eta = \frac{b}{c+q}, \zeta = \frac{c}{a+r}.$$

Then, using formulas (2), we can express the ratio of the sides of these right angle triangles through their parameters:

Fig. 1. Fig. 2.

⟦folio 30⟧

$$\frac{a}{b} = \frac{2\xi}{1-\xi^2}, \frac{b}{c} = \frac{2\eta}{1-\eta^2}, \frac{c}{a} = \frac{2\varsigma}{1-\varsigma^2};$$

$$\frac{p}{b} = \frac{1+\xi^2}{1-\xi^2}, \frac{q}{c} = \frac{1+\eta^2}{1-\eta^2}, \frac{r}{a} = \frac{1+\varsigma^2}{1-\varsigma^2}.$$

From (4) it follows non-presidentially that the parameters $\xi, \eta, \varsigma$ satisfy the correspondence

$$\frac{2\xi}{1-\xi^2}, \frac{2\eta}{1-\eta^2}, \frac{2\varsigma}{1-\varsigma^2} = 1.$$

This is the common “equation of Pythagorean tetrahedrons.”

Problem 3. Prove that if three positive numbers $\xi, \eta, \varsigma$ each of which is less than one satisfy equation (6), then there exists a tetrahedron with right plane angles at one of the vertices for which (with the notation figure 2) equality (3) (and then equalities (4), (5)) holds.

Problem 4. Prove that if $\xi, \eta, \varsigma$ is a solution to the indeterminate equation (6), then the numbers

$$\xi' = \frac{1-\xi}{1+\xi}, \eta' = \frac{1-\eta}{1+\eta}, \varsigma' = \frac{1-\varsigma}{1+\varsigma}$$

also form a solution to this equation (“conjugation of the solution”). Prove that if each of the numbers $\xi, \eta, \varsigma$ is positive and less than 1, then each of the numbers $\xi', \eta', \varsigma'$ has this property. What is the geometric interaction of two conjugate solutions to equation (6)?

Problem 5. Prove that if $\xi, \eta, \varsigma$ is a solution to the indeterminate equation (6), and each of the numbers $\xi, \eta, \varsigma$ is positive and less than 1, then the tetrahedron $OABC$, which is discussed in Problem 3, can be obtained as follows: from the point $O$ three mutually perpendicular segments $OA, OB, OC$ are drawn, having lengths

$$OA = 1, OB = \frac{1-\xi^2}{2\xi}, OC = \frac{1-\eta^2}{2\eta}$$

Problem 6. The numbers $\xi, \eta, \varsigma$ constitute a solution to the indeterminate equation (6). Is it possible for two of these numbers to be located, and the third to be located? Give a geometric interpretation of the answer.

Problem 7. The numbers $\xi, \eta, \varsigma$ form a solution to the indeterminate equation (6), and each of them is positive and less than 1. Prove that if $\xi = m/n, \eta = p/q$ (where $m, n, p, q$ are natural), then a tetrahedron with right plane angles at one of the vertices and the lengths of the edges emerging from this vertex

$$a = 4mnpq, b = 2pq = (n^2-m^2), c = (n^2-m^2)(q^2-p^2)$$

is Pythagorean.

The following statements directly follow from formulas (3)–(5): in order for the tetrahedron $OABC$ with right plane angles at the vertex $O$ to be Pythagorean, it is necessary and sufficient that the parameters $\xi, \eta, \varsigma$ (satisfying equation (6)) are arranged. In fact, if the tetrahedron

$$\frac{a}{b} = \frac{2\xi}{1-\xi^2}, \frac{b}{c} = \frac{2\eta}{1-\eta^2}, \frac{c}{a} = \frac{2\varsigma}{1-\varsigma^2};$$

Pythagoras (that is, the ratio of any two of its edges is rational), then from (3) it follows that $\xi, \eta, \varsigma$ are rational. Conversely, if $\xi, \eta, \varsigma$ are rational, then according to (4), (5) the relationship of any two edges is rational, that is, the Pythagorean tetrahedron.

Search for Pythagorean tetrahedra

We see that the problem of finding algebraic Pythagorean tetrahedra is equivalent to the problem of finding rational solutions to the indeterminate equation (6) under the conditions $0 < \xi < 1, 0 < \eta < 1, 0 < \varsigma < 1$. It is easy to verify by direct verification that the following triples are solutions.

Table 1.

| | $\xi$ | $\eta$ | $\varsigma$ |
| :--- | :--- | :--- | :--- |
| 1) | 5/6 | 2/11 | 3/13 |
| 2) | 5/8 | 1/11 | 9/13 |
| 3) | 1/7 | 9/11 | 5/16 |
| 4) | 5/6 | 6/11 | 1/17 |
| 5) | 8/9 | 1/11 | 5/17 |
| 6) | 2/5 | 5/11 | 7/18 |
| 7) | 3/4 | 1/10 | 11/21 |
| 8) | 2/13 | 17/22 | 9/25 |
| 9) | 3/7 | 3/8 | 11/25 |
| 10) | 21/23 | 1/24 | 11/25 |
| 11) | 7/18 | 1/22 | 23/25 |

This makes it possible to find identical Pythagorean tetrahedra. To calculate the length of the edges, you can use the method of Problem 7 (production, if necessary, reduction by a common factor). The edges of these tetrahedra are listed in Table 2.

Let us also note that if the Pythagorean tetrahedron $OABC$ is complementary with edges $OA, OB, OC$, then we get a “Pythagorean” parallel

⟦folio 31⟧

lepiped, that is, a rectangular paralleliped with dissimilar (or whole) lengths of all edges and all diagonals of the faces. figure 3 shows the paralleliped thus obtained using the second of the above Pythagorean tetrahedra. However, the diagonal of this paralleliped has an irrational length. It is unknown whether there is a rectangular paralleliped in which all the edges, all the diagonals of the faces and the diagonal of the entire paralleliped have integer lengths.

Fig. 3.

Problem 8. Prove that ten of the given identical solutions to equation (6) are pairwise conjugate (in the sense of the definition given in Problem 4). Find a solution, a “conjugation” to the same solution; find the corresponding Pyphagian paralleliped.

Problem 9. Let’s call a rectangular paralleliped a “Pyphagian paralleliped of the second kind” if all its edges, as well as the diagonal of the paralleliped, have dissimilar lengths. Prove that if $x_1, x_2, x_3$ is the length of the edges of a rectangular paralleliped, and $y$ is the length of its diagonal, then it is a Pythagogian paralleliped of the second kind if and only if it is a number (*parameters*))

$$\xi_1 = \frac{x_1}{x_3 + y}, \quad \xi_2 = \frac{x_2}{x_3 + y}$$

rational. Prove that for this paralleliped there is a fair correspondence

$$\frac{x_1}{y} = \frac{2\xi_1}{1 + \xi_1^2 + \xi_2^2}, \quad \frac{x_2}{y} = \frac{2\xi_2}{1 + \xi_1^2 + \xi_2^2},$$

$$\frac{x_3}{y} = \frac{1 - \xi_1^2 - \xi_2^2}{1 + \xi_1^2 + \xi_2^2}.$$

Problem 10. Generalizing the result of Problem 9, prove that any heterogeneous solution to an indeterminate equation

$$x_1^2 + x_2^2 + \dots + x_n^2 = y^2$$

looks like

$$x_1 = k \cdot 2\xi_1, \quad x_2 = k \cdot 2\xi_2, \dots, \quad x_{n-1} = k \cdot 2\xi_{n-1},$$

$$x_n = k(1 - \xi_1^2 - \dots - \xi_{n-1}^2), \quad y = k(1 + \xi_1^2 + \dots + \xi_{n-1}^2),$$

where $\xi_1, \dots, \xi_{n-1}$ are arbitrary heterogeneous numbers (*parameters*) and the coefficient $k$ is also heterogeneous. Can you give a geometric interpretation of this result?

Problem 11. Generalize the result of Problem 10 to an indeterminate equation

$$x_1^2 + \dots + x_p^2 = y_1^2 + \dots + y_q^2$$

(that is, give formulas for finding all heterogeneous solutions).

***

In conclusion, let us dwell on the question of how the 11 heterogeneous solutions to equation (6) indicated above were found. For this, an electronic computer was used. The algorithm for computing on a computer was compiled based on the following messages. Let

$$\xi = \frac{a}{b}, \quad \eta = \frac{c}{d}, \quad \xi = \frac{e}{f},$$

(7)

where $a, b, c, d, e, f$ are natural numbers. The idea of ​​the algorithm is to go through all such sixes, giving each of the six numbers the values ​​1, 2, ..., 25, using formulas (7) to find the corresponding triple ($\xi, \eta, \zeta$) and from them select those that satisfy equation (6). In fact, it is more expedient, freeing from meanings, to carry out calculations not with $\xi, \eta, \zeta$, but with natural numbers $a, b, c, d, e, f$. The point is that when working with heterogeneous numbers $\xi, \eta, \zeta$ the computer would replace them with some decimal approximations that would definitely not satisfy equation (6).

Task 12. Write an algorithm in an educational algorithmic language. Try to improve it to avoid (in fact it is not necessary) a complete search of all sixes $a, b, c, d, e, f$.
