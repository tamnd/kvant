---
id: 1981-4-vaguten-formula-ploschadi-5e6826df
issue: kvant_1981_4
year: 1981
number: "4"
title: Area formula
authors:
  - Вагутен Н.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 19
page_last: 21
page_labels: 17-19
tag: BY2X
lang: en
source: kvant_digital
extraction: vision
content_sha256: e7cecdc11e34c2310fc1e43a6ab085ecb490a8001918399b3593d327fb582be0
prompt_sha256: draft-1
translated_from: content/ru/1981/04/articles/06_vaguten-formula-ploschadi-5e6826df.md
source_content_sha256: 5812822130cbbe528ec6c38317cb9c656168da519680c30e27d3189d2c8940e3
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 17⟧

Math circle

N. Vaguten

Area formula

In this article, we will discuss a useful formula that expresses the area of ​​a polygon in terms of the coordinates of its vertices. In preparing the article, A. Startsev was used, added in «Kvant» in 1970 (when the author was still a schoolboy).

Grapecia combinations

Let us be given a polygon located in the positive square $x > 0, y > 0$ and also convex. The interior of its vertices counterclockwise is $A_1(x_1; y_1), A_2(x_2; y_2)$, ..., as shown in figure 1, ​​where the number of vertices is $n = 5$. Let us drop the perpendiculars $A_1H_1, A_2H_2$, ..., $A_nH_n$ from all vertices to the axis $x$; their lengths are $y_1, y_2, ..., y_n$.

The area of ​​the grapecia $A_kH_kH_{k+1}A_{k+1}$ is equal to the modulo of the product $(y_k+y_{k+1})(x_k-x_{k+1})/2$. This product is positive for $x_k > x_{k+1}$ and negative for $x_k < x_{k+1}$ (here $k$ is one of the numbers 1, 2, ..., $n$, and the number $n+1$ following $n$ must be replaced by 1). Remarkably, it turns out that the sum of all $n$ such products of the same type is exactly equal to the area of ​​the polygon $A_1A_2...A_n$.

For example, for a pentagon at figure 1 from the heel the product

$$\frac{(y_1+y_2)(x_1-x_2)}{2}, \frac{(y_2+y_3)(x_2-x_3)}{2}, \frac{(y_3+y_4)(x_3-x_4)}{2}, \frac{(y_4+y_5)(x_4-x_5)}{2}, \frac{(y_5+y_1)(x_5-x_1)}{2}$$

tri, corresponding to the upper sides (blue), are positive, and two, corresponding to the lower sides (red), are negative; By subtracting the sum of the areas of the red trapezoids from the sum of the areas of the blue trapezoids, we find the area of ​​the pentagon.

The resulting sum can be somewhat simplified by reducing the product $x_1y_1, x_2y_2$, ..:

$$S = \frac{(y_1+y_2)(x_1-x_2)}{2} + \frac{(y_2+y_3)(x_2-x_3)}{2} + \frac{(y_3-y_4)(x_3-x_4)}{2} + \frac{(y_4+y_5)(x_4-x_5)}{2} + \frac{(y_5+y_1)(x_5-x_1)}{2} = \frac{(x_1y_2-x_2y_1) + (x_2y_3-x_3y_2) + ... + (x_5y_1-x_1y_5)}{2}.$$

1. Derive the formula for the area of ​​a convex $n$-gon for any $n$.

Basic formula

So, the area $S$ of a convex $n$-gon with vertices $A_k(x_k; y_k)$, $k = 1, 2, ..., n$ is equal to

$$\frac{1}{2} \left[ (x_1y_2-x_2y_1) + (x_2y_3-x_3y_2) + ... + (x_ny_1-x_1y_n) \right].$$

The expression $ad-bc$ is so common in mathematics that a special notation $|a|^2 b|^2$ and the name “determinant” have been adopted for it.

Fig. 1.

⟦folio 18⟧

Fig. 2. The product of numbers connected to it by a segment is taken with the + sign, and in red - with the - sign.

second order"; Using such determinants, the area formula can be written more compactly:

$$S = \frac{\left| x_1 x_2 \right| + \left| x_2 x_3 \right| + \ldots + \left| x_n x_1 \right|}{2}.$$

(To fill out formula (1), figure 2 is convenient. Note that formula (1) assumes that the vertices are numbered counterclockwise.)

2. Check that if you number the vertices in the reverse order, clockwise, then each parenthesis corresponding to a specific side of the polygon: $A_1 A_2$, $A_2 A_3$, ..., $A_n A_1$, changes sign. The same effect will occur if you place the customized axis designations in places - change the orientation of the plane.

In order not to worry about one direction or another of vertex numbering, you can put a modulus sign together with square brackets in formula (1). The resulting formula

$$S = \frac{1}{2} \left| \sum_{k=1}^{n} \left(x_k y_{k+1} - x_{k+1} y_k\right) \right|$$

suitable for any occasion. (Recall again that $y_{n+1}$ and $x_{n+1}$ should be replaced by $y_1$ and $x_1$.)

Note that so far we have considered all the coordinates of the vertices of the polygon to be positive, and the polygon itself to be convex. It would be very disappointing and surprising if our formula turned out to be correct only under such an additional assumption. Fortunately, this is not the case: the formula is valid for any polygon on the plane. We will discuss how to prove it for a non-convex polygon below, in Exercise 13 (see also S. Sefibkov’s note on p. 20). Now we will get rid of the assumption that the polygon is located inside the angle $x > 0$, $y > 0$.

3. Check that the right side of formula (2) does not change if:

a) replace each $x_k$ with $x_k + a$;
b) replace each $y_k$ with $y_k + b$.

We can parallelly transfer any polygon $A_1 A_2 \ldots A_n$ to some vector $(a; b)$ into the corner $x > 0$, $y > 0$. In this case, the coordinates of its vertices change, but neither its area - the left part of formula (2), nor the right part of this formula - changes. Since equality (2) is true to obtain a polygon with positive vertex coordinates, it will also be true for the original polygon $A_1 A_2 \ldots A_n$.

4. Using formula (2), find the areas of quadrilaterals with vertices:
a) $(0; 0), (0; 1), (1; 0), (1; 1)$;
b) $(0; 0), (-1; 1), (2; 3), (1; 2)$;
b) $(0; 5), (3; 0), (0; -4), (2; 0)$. Check your answer by finding this area in another way.

5. a) Write down the formula for the area of ​​a triangle with vertices $(0; 0), (a; b), (c; d)$.
b) Under what condition do three points $(x_1; y_1), (x_2; y_2)$ and $(x_3; y_3)$ lie on the same line?

Triangle combinations
The main formula (2) can be derived differently - so that the geometric meaning of each term $(x_k y_{k+1} - x_{k+1} y_k)/2$ will be clear (note that it includes the coordinates of only two neighboring points $A_k$ and $A_{k+1}$). We can still assume that $x_k > 0$, $y_k > 0$.

It turns out that the expression $(x_k y_{k+1} - x_{k+1} y_k)/2$ is equal to $OA_k A_{k+1}$ according to the triangle model, and is positive if the segment $OA_k+1$ makes a larger angle with the axis $x$ than $OA_k$, and negative if less.

6. Let $B(x_1; y_1)$ and $C(x_2; y_2)$ be two points with positive coordinates, and $y_1/x_1 < y_2/x_2$. Then the area of ​​the parallelgram $OBDC$ (Fig. 3) is $x_1 y_2 - x_2 y_1$.

Now it is clear that the sum of the $n$ terms of $(x_k y_{k+1} - x_{k+1} y_k)/2$ gives the required area of ​​the $n$-gon (see Fig. 4): from the sum of the areas of the lower triangles we subtract the sum of the areas of the red ones - we have already encountered this successful coincidence of signs in the discussion with trapezoids).

7. Check that the geometric meaning of the expression $x_1 y_2 - x_2 y_1$ for points $B(x_1; y_1)$, $C(x_2; y_2)$ with coordinates of any sign is

⟦folio 19⟧

Fig. 3.

oriented area of ​​the parallelogram OBDC, built on the vectors $\vec{OB}$ and $\vec{OC}$*): the area of ​​OBDC is taken with a “plus” sign if the direction $\vec{OC}$ is obtained from the direction $\vec{OB}$ by rotating counterclockwise (at an angle not exceeding 180°) and “minus” if clockwise.

Additional tasks and comments
In conclusion, we propose to prove several more statements related to the formula for the area of ​​a polygon, its proofs and generalizations.

8. For two vectors $\vec{b} = \vec{OB}$, $\vec{c} = \vec{OC}$ on the plane, we will denote the oriented area of ​​the parallelogram OBDC (Exercise 7) by $\vec{b} \wedge \vec{c}$.

Then for any vectors $\vec{a}, \vec{b}, \vec{c}$ and any number $\lambda$ the following equalities hold:
$$1^0. \vec{a} \wedge \vec{b} = -(\vec{b} \wedge \vec{a}).$$
$$2^0. \lambda \vec{a} \wedge \vec{b} = \vec{a} \wedge (\lambda \vec{b}) = \lambda (\vec{a} \wedge \vec{b}).$$
$$3^0. \vec{a} \wedge \vec{b} = 0$$ if and only if the vectors $\vec{a}$ and $\vec{b}$ are collinear.
$$4^0. \vec{a} \wedge (\vec{b} + \vec{c}) = \vec{a} \wedge \vec{b} + \vec{a} \wedge \vec{c}.$$

The quantity $\vec{a} \wedge \vec{b}$ is sometimes called the free product of the vectors $\vec{a}$ and $\vec{b}$.

9. Find the coordinates of the points $A, B$ of intersection of the line $ax + by + c = 0$ with the coordinate axes ($a \neq 0, b \neq 0$) and the area of ​​the triangle $ABM_0$, where $M_0(x_0; y_0)$, derive a formula for the distance from the point $M_0$ to this line:

$$|ax_0 + by_0 + c| / \sqrt{a^2 + b^2}.$$

10. a) Let the vertices $A_1, A_2, \dots, A_n$ of the polygon move along a straight plane and uniformly (each with its own constant speed). Prove that the area of ​​the polygon $A_1A_2\dots A_n$ varies

$$\sum \begin{matrix} x_i x_j x_k \\ y_i y_j y_k \\ z_i z_j z_k \end{matrix} = x_1 y_2 z_3 - x_1 y_3 z_2 + x_2 y_3 z_1 - x_2 y_1 z_3 + x_3 y_1 z_2 - x_3 y_2 z_1.$$

over all its grams $\Delta A_i A_j A_k$, where $A_i(x_i; y_i; z_i)$ is the vertex of the polygon, and the “triangle determinant” is calculated by the formula

$$\begin{matrix} x_1 x_2 x_3 \\ y_1 y_2 y_3 \\ z_1 z_2 z_3 \end{matrix} = x_1 y_2 z_3 - x_1 y_3 z_2 + x_2 y_3 z_1 - x_2 y_1 z_3 + x_3 y_1 z_2 - x_3 y_2 z_1.$$

Moreover, each determinant must be written out by looking at the face $A_i A_j A_k$ from the point $(0; 0; 0)$: the coordinates of the vertices of the visible faces are clockwise, the invisible ones are counterclockwise.

12. a) Check using formula (2) that with rumble $k$ the area increases by $k^2$ times, and with symmetries $(x; y) \rightarrow (-x; y), (x; y) \rightarrow (x; -y), (x; y) \rightarrow (-x; -y)$ it does not change.

*) See also the article by A. Lopshitz “Areas of oriented figures” («Kvant», 1978, No. 3).

2*
