---
id: 1977-6-kushnirenko-mnogougolnik-nyutona-9687bd14
issue: kvant_1977_6
year: 1977
number: "6"
title: Newton's polygon
authors:
  - Кушниренко А. Г.
rubric: osnovnye-stati
rubric_sub: Основные статьи
page_first: 21
page_last: 26
page_labels: 19-24
tag: AK6D
lang: en
source: kvant_digital
extraction: vision
content_sha256: 233eee9d5092776467ae7e0abddd9510646ab98baf8ef8c1705d3872c1a8579b
prompt_sha256: draft-1
translated_from: content/ru/1977/06/articles/05_kushnirenko-mnogougolnik-nyutona-9687bd14.md
source_content_sha256: 2dbf0dfe14bc2841a4c740adc44fc137f10fe3a8a88c78b8ab53302dc89094bd
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 19⟧

“The functional role played by Newton’s research in the development of infinitesimal analysis is known. Most of his ideas were considered in the works of later authors, often without preserving either Newton’s name or his method of notation. But in modern mathematics there are many methods and results of a more specific nature that bear the name of Newton. Their significance was revealed only in a much later era, when the general process of mathematics made it possible to evaluate the importance of one or another of Newton’s results, written partly in the form of a small substitution. Among such RESULTS IS Newton’s “polygon”, or, as it is often called, Newton’s “parallelogram...”

N. G. Chebogarev

An important characteristic of a polynomial in one variable is its degree. Knowing the degree, you can say a lot about a polynomial without even knowing its coefficients. For example, a polynomial of odd degree always has a real root, the number of real roots of a polynomial does not exceed its degree, etc.

The simplest and most important generalization of the concept of degree for a polynomial $P(x, y)$ in two variables $x, y$ will be the so-called full degree of a polynomial in variables $x, y$. However, a more subtle generalization of the concept of degree for a polynomial in two variables is not a number, but a more complex thing - namely, a polygon on the plane.

In this article, we will associate each polynomial in two variables with a polygon on the plane. This design is mainly influenced by the English mathematician and physicist Isaac Newton; Since the 18th century, this polygon has been called “Newton’s polygon.” Newton's polygon, a polynomial in two variables, bridges the gap between algebra and geometry. Traffic in this place has not subsided for 300 years, and in recent years it has become especially intense. Obviously a place can move in two different directions - and Newton's polygon is useful in two ways. By considering a polygon on the plane as a Newton polygon of some polynomial, we can use the algebraic properties of polynomials to solve geometric problems on the polygon. On the contrary, the geometric properties of Newton's polygon help solve polynomial problems. Two examples of the use of Newton's polygon in the study of polynomials are discussed in detail in § 2 and § 3. Examples of the use of polynomials in the study of city polygons are more complex, and we will not go into them.

⟦folio 20⟧

§ 1. What is a Newton polygon
Newton diagram polynomial in two variables

Recall that the one-year term in the independent variables $x$ and $y$ is a function of the form $x^m y^n$, where $m$ and $n$ are non-negative integers, and a polynomial in $x$ and $y$ with real coefficients is called a function $P(x, y)$ given by the formula
$$P(x, y) = a_1 O_1 + a_2 O_2 + \dots + a_k O_k,$$
(1)
where $a_1, a_2, \dots, a_k$ are real numbers, and $O_1, O_2, \dots, O_k$ are pairwise distinct ones of the same year *). If in formula (1) the coefficient $a_i$ is different from zero, then the one-year $O_i$ is said to be included in the polynomial $P(x, y)$. For example, the polynomial $2 + 3y - \sqrt{2}x^3y^2$ includes the annuals 1, $y$ and $x^3y^2$, but the polynomial $P(x, y) \equiv 0$ does not include any annuals. It is convenient to represent the annuals included in the polynomial $P(x, y)$ by points on the coordinate plane: we mark the point $M(m_0; n_0)$ on this plane if the annual $x^{m_0}y^{n_0}$ is included in the polynomial $P(x, y)$. Then to each non-zero polynomial $P(x, y)$ we associate a finite set on the plane $Omn$ - we will denote it $D(P)$ - which visually depicts the one-year ones included in $P(x, y)$. We will call a point on the plane for which both coordinates are integers an integer point. For any polynomial $P$, the set $D(P)$ consists only of integer points, so it is convenient to draw it on checkered paper. For example, the polynomial
$$P(x, y) = xy - y^3 + 3x^2y^2 + 0,5x^4 - 2x^3y^4.$$
(2)
depicted on figure 1. By emphasizing that the values ​​of non-zero coefficients of the polynomial $P$ are not taken into account in any way when constructing the polynomial $D(P)$. This set is generally called * the Newton diagram of the polynomial $P$.

A word of caution. We should not confuse the number plane $R^2$, which handles the definition of the polynomial $P$, with the coordinate plane $Omn$, on which we draw the Newton diagram of the polynomial $P$. The points of these planes are of different nature.

How Newton defined the "Newton diagram"

Newton also noted the polynomials included in the polynomial in the variables $x, y$ on checkered paper. Newton drew such paper himself and marked not the corners of the cells, but entire cells. This is how he describes these constructions in a letter to one of his colleagues.

“...For a better understanding of this rule, I will show it in the following diagram. Construct a right angle $BAC$; its sides $BA$ and $AC$ are divided into equal parts and, restoring perpendiculars, the angular area is divided into equal squares or parallelograms, which are marked by the dimensions of the letters $x$ and $y$ inscribed in them (see figure 2). Then, when the equation is given, mark parallelograms with some symbol corresponding to all its terms...”

*) Independent variables $x$ and $y$ take values ​​in the set of real numbers; Thus, the function $P(x, y)$ has the number plane as its domain of definition, and the number line as its polynomial of values.

⟦folio 21⟧

Here we are talking about the construction of a “Newton diagram”, and then Newton describes the construction of a “Newton polygon” (we continue the translated quote):

“... and apply the ruler to two or, sometimes randomly, to several of the parallels marked in this way, of which one is the lowest in the column $AB$ on the left, the other falls on the ruler on the right, and all the rest, not touching the ruler, are above it...”

How do we define Newton's polygon
We see that Newton applies a ruler to the polygon $\Delta(P)$, satisfying two conditions:
(I) At least two points $\Delta(P)$ fall on the ruler.
(II) The set $\Delta(P)$ lies on one side of the ruler.

Consider the convex hull of the polygon $\Delta(P)$, that is, the smallest convex polygon containing all points $\Delta(P)$. We will denote this polygon by $F(P)$ and call it the Newton polygon of the polynomial $P(x, y)$. The Newton polygon of polynomial (2) is depicted in figure 3. The connection of the polygon $F(P)$ with Newton’s method of applying a ruler is completely clear. If you apply a ruler to any side of the Newton polygon, then properties (I) and (II) will be fulfilled. Conversely, if a ruler is applied to the polygon $\Delta(P)$ such that (I) and (II) are satisfied, then the ruler necessarily goes along one of the sides of the polygon $F(P)$.

Fig. 3.

A few simple exercises on Newton's polygon

To become familiar with the definition of a Newton polygon, the reader should fulfill the following conditions:

1. Draw Newton's diagram and Newton's polygon for the polynomials: $x, x + y, 1 + x + xy, x^2 + x^2y + x^5y^7 + x^{10}, (1 + x + x^3)(1 + y^4)^{*}$.
2. Prove that $F(\lambda P) = F(P)$ for $\lambda \neq 0$. Prove that $\Delta(P_1 + P_2) \subset \Delta(P_1) \cup \Delta(P_2)$. Is it true that $F(P_1 + P_2) = F(P_1) \cup F(P_2)$?
3. Let $Q(x, y) = P(x^a, y^b)$, where $a$ and $b$ are natural numbers. How are the polygons $F(P)$ and $F(Q)$ related to each other?
4. Come up with a definition of Newton's diagram and Newton's polygon for a polynomial in three variables.

Naturally they will ask, how is a Newton polygon related to the product of polynomials with Newton polygons combined? It turns out that the operation that you need to sell with $F(P_1)$ and $F(P_2)$ to get $F(P_1 \cdot P_2)$ is well studied in geometry and has a special name: Minkowski sum.

5. Prove that $F(P_1 \cdot P_2) = F(P_1) + F(P_2)$, where “+” is the Minkowski sum (see the article by N. Vasiliev “Addition of figures”, «Kvant», 1976, No. 4).

This property of a Newton polygon generalizes the well-known property of the degree of a polynomial: when polynomials change, their degrees add up. It is this property that helps to use polynomials in solving pure geometric problems.

§ 2. Why did Newton come across the “Newton polygon”?

Newton solved the equation $P(x, y) = 0$, where $P$ is a polynomial in $x, y$. By solution he understood the exact or approximate expression of $y$ through $x$. As was customary in his time, Newton does not explain his method in general terms, but looks for it using specific examples. Let's continue the quote translated into § 1:

“...Then take all the terms of the equation that are contained in the parallel games, touched by the ruler, and find from them the value that should be obtained as a result. So, if you need to determine the root

*) The first two examples show that the Newton polygon of the polynomial $P(x, y)$ may not be a real polygon, i.e., it may coincide with a point or a segment.

⟦folio 22⟧

equations

$$y^6 - 5xy^5 + \frac{x^3}{a} y^4 - 7aaxxyy + 6a^3x^3 + bbx^4 = 0,$$

(3)

then, as we see (see Fig. 2), I denote the parallelograms corresponding to the terms of this equation with an asterisk. I then apply the ruler $DE$ to the lowest of the marked parallelograms in the first column on the left, and rotate the ruler to the right side until it passes through any one or more of the different marked parallelograms. At the same time, I see that the ruler will touch those places that contain the terms $x^3$, $xxyy$ and $y^6$. So I'll put them together into an equation

$$y^6 - 7aaxxyy + 6a^3x^3 = 0$$

(which, if you like, I then, putting $y = u\sqrt{ax}$, leads to $u^6 - 7uu + 6 = 0$) and from it I find $y$, which has even values, namely:

$$+ \sqrt{ax}, - \sqrt{ax}, + \sqrt{2ax}, - \sqrt{2ax}...$$

Newton explains in detail that the solutions found are not exact, but approximate (the more accurate, the closer $x$ and $y$ are to zero). He also indicates how to obtain an exact solution by adding a finite or infinite number of correction terms to the solution already found. Due to lack of space, we will not cite the corresponding expressions from Newton’s works.

What is Newton's method of approximate solution of the equation $P(x, y) = 0$ for small $x$ and $y$?

In general terms, Newton's method can be explained (somewhat schematically) as follows.

For sufficiently small $x$ and $y$ we want to solve the (attached) equation $P(x, y) = 0$ (or draw an approximate set $P(x, y) = 0$). Let $\gamma$ be the “origin-facing” side of the polygon $F(P)$ (such sides on figure 4 are highlighted in red). Let us denote by $P_\gamma(x, y)$ the sum of the same years taken with the old coefficients, included in $P(x, y)$ and corresponding to points $\gamma$. Let the angle coefficient of edge $\gamma$ be equal to $-k$, where $k > 0$. Putting $y = ux^{\frac{1}{k}}$ into equation $P_\gamma(x, y) = 0$, we obtain equation $x^l Q(u) = 0$, where $Q$ are some polynomials in $u$. Let $u_1, u_2, \dots$ be non-zero roots of $Q$.

Then $y_1 = u_1x^{\frac{1}{k}}, y_2 = u_2x^{\frac{1}{k}}, \dots$ are exact solutions of equation $P_\gamma(x, y) = 0$ and approximate solutions of equation $P(x, y) = 0$. Also combine the solutions along all “zero-facing” edges $\gamma$ of the polygon $F(P)$, we obtain all nontrivial*) approximate solutions of equation $P(x, y) = 0$ for small $x$ and $y$. A proof of the last phrase and even an explanation of its exact meaning would take us too far. Our main goal is to teach the reader to practically find approximate solutions of the equation $P(x, y) = 0$ (or, what is the same, to draw approximately the set $P(x, y) = 0$) for small $x$ and $y$.

Learning to work with Newton's polygon

The Newton polygon polynomial (2) has sides $\gamma_1$ and $\gamma_2$ (Fig. 4) facing zero. Let's start from the $\gamma_1$ side: $P_{\gamma_1} = xy + 0,5x^4$. Replacing $y = ux^3$ brings equation $P_{\gamma_2} = 0$ to the form $x^4(u + 0,5) = 0$, hence $y = -0,5x^3$. Next, $P_{\gamma_2} = xy - y^3$; replacing $y = ux^{1/2}$ brings equation $P_{\gamma_2} = 0$ to the form $x^{3/2}(u - u^3) = 0$, whence $y = -\sqrt{x}$ and $y = +\sqrt{x}$. However, the last two solutions can be

*) Trivial names for solutions of the form $x = 0$ or $y = 0$.

Fig. 4.

⟦folio 23⟧

but combine: $x = y^2$. So, we found that for small $x$ and $y$ the equation $P(x, y) = 0$, where $P$ is given by formula (2), has two approximate solutions: $y = -0,5x^3$ and $x = y^2$. (There are no associated solutions in this case, since $P$ is not divisible by either $x$ or $y$.) The form of approximate solutions is shown in figure 5. The same figure for small $x$ and $y$ can be considered as an approximate figure set $P(x, y) = 0$.

The rights are below 6. Solve the approximation of the equation $x^5y + x^3y^2 - 3x^2y^3 + xy^4 + y^7 + 2x^4y^2 + 3x^6y^3 - x^5y^5 + x^6y^6 + 7x^2y^8 = 0$ for small $x$ and $y$ (see Fig. 6).

Newton also indicated a method by which the equation $P(x, y) = 0$ can be solved for very large $x$ and $y$.

The license is below 7. Figure out how to use Newton's polygon to solve (approximately) the equation $P(x, y)$ for very large $x$ and $y$.

§ 3. The number of solutions to a system of two equations with two unknowns and Newton’s polygon
Bezout's Theorema
Consider a system of two equations with two unknowns $x, y$:

$$\begin{cases} P(x, y) = 0, \\ Q(x, y) = 0, \end{cases}$$

(4)

Fig. 5.

Fig. 6.

where $P$ and $Q$ are polynomials with real coefficients. If $P$ and $Q$ are polynomials of the first degree *), then the number of solutions to system (4) is either infinite or does not exceed 1. If $P$ is a polynomial of the first degree, and $Q$ is a polynomial of degree $N$, then, as is easy to see, the number of solutions to system (4) is either infinite or does not exceed $2 \cdot N$. After these examples, the reader will not be surprised by the formulation of a theorem that was well known in the last century.

Bezout's Theorema. If $P$ is a polynomial of degree $M$, and $Q$ is a polynomial of degree $N$, then the number of solutions to system (4) is either infinite or does not exceed $M \cdot N$.

Is it possible to strengthen Bezout's theorem?
Generally speaking, it is impossible: the number $M \cdot N$ in the formulation of Bezout’s theorem cannot be replaced by a smaller number for any $M$ and $N$, since there are examples of systems that have exactly $M \cdot N$ solutions (for example, the system $(x - 1)(x - 2) \cdot \dots \cdot (x - M) = (y - 1)(y - 2) \cdot \dots \cdot (y - N) = 0$).

In many practical cases, however, Bezout's theorem clearly overestimates the number of solutions to system (4).

Example. $P = a + bx + cx^2y^2, Q = d + ey + fx^2y^2$. Bezout's theorem states that if the number of solutions of the system $P = Q = 0$ is finite, then it does not exceed 16. Meanwhile, solving this system directly, it is easy to obtain that if the number of solutions is finite, then it does not exceed 4.

This example and other more complex examples lead to the idea of ​​generalizing Bezout's theorem. It is clear that in this case we must replace the concept of the degree of a polynomial with some more complex concept that fully takes into account the property of polynomials. As *) Let us recall that the degree of a polynomial (sometimes called the full degree) is the maximum of the number $m + n$ over all the same years $x^m y^n$ included in the polynomial.

⟦folio 24⟧

SUBJECT TO SUCH GENERALIZATION OF THE DEGREE, WE WILL CONSTITUTE THE MULTIAGNE OF THE NOOMON SYSTEM.

Let $D(P)$ be the Newton diagram of the polynomial $P$ and $D(Q)$ the Newton diagram of the polynomial $Q$. Let's put $D = D(P) \cup D(Q)$. D is a finite set on the plane $Omn$. The point $M(m_0; n_0)$ belongs to $D$ if the same year $x^{m_0}y^{n_0}$ appears with a nonzero coefficient in at least one of the polynomials $P$ and $Q$. Again, by $F$ we denote the convex hull of the set $D$, that is, the smallest convex polygon in the plane $Omn$ containing all points $D$. We will call the polygon $F$ the Newton polygon of system (4). (If in our example the coefficients $a, b, \dots, f$ of the polynomials $P$ and $Q$ are different from zero, then the set $D$ and the polygon $F$ of system (4) are the same as in Figures 7, a, 6.)

Is it possible, using some characteristics of the polygon $F$, to estimate from above the number of solutions to system (4)?

The answer to this question is given by the following

Theorem 1. The number of incomplete real solutions of system (4) is either infinite or does not exceed those satisfying the Newton polygon of this system (the solution $(x_0; y_0)$ of system (4) is called ineffective if $x_0 \neq 0$ and $y_0 \neq 0$).

Theorem 1 belongs to the author of this article. Its proof is indirect: a theorem is first proven in which not the area of ​​the polygon $F$ is used, but its other characteristics - namely, the number of integer points in the polygon $F$ and in the “double polygon” 2F. Thus, when working with Newton's polygons, interesting geometric questions arise regarding integer points in the polygon. Even more interesting questions in connection with Newton's polygraphs. All this is discussed in detail in the article “Integral points in a polygon and polyhedra” («Kvant», 1977, No. 4).

Is it possible to improve Theorem 1?

Theorem 1 gives a good estimate for the number of solutions in cases where the polygons $F(P)$ and $F(Q)$ are the same or close enough (otherwise the estimate is too grouped: consider the system $x^n + y^{n+1} = y^n + y^{n+1} = 0$). To obtain a more accurate estimate, you need to consider $D(P)$ and $D(Q)$ separately as to how to do this. N. Bernistein, who generalized Theorem 1 as follows.

Theorem 2. Let $A$ be the Newton polygon of the polynomial $P$, $B$ the Newton polygon of the polynomial $Q$, and $C$ the Newton polygon of the polynomial $P \cdot Q$. Then the number of unsuccessful solutions to system (4) is either infinite or does not exceed the number $S(C) - S(A) - S(B)$. (Here $S$ denotes the area of ​​the corresponding polygon.)

The polygon $C$ is nothing more than the Minkowski sum of the polygons $A$ and $B$, and for the number $S(C) - S(A) - S(B)$ there is a geometrically special name: the mixed area of ​​the polygons $A$ and $B$ (see Exercise 5 and the article by N. Vasiliev cited there).

Exercises 8. Apply Theorem 1 to polynomial (2) and the polynomials from Exercise 1.

9. Using Bezout's theorem and Theorem 1, estimate the number of solutions of the system $x^3 + y^4 = axy + bx^2y^2 + cx^3y^2 + dx^4y^3$ for $a \neq 0$ and $d \neq 0$.

10. Generalize Theorem 1 to the case of a system of three algebraic equations with three unknowns $x, y, z$.

LITERATURE

1. Isaac Newton, Mathematical work. Method of fixation and infinite series with its application to geometric critics. Translation from Latin by D. Morduchai-Voltovsky, ONTI, 1937, p. 33-34.

2. Isaac Newton, Newton's Second Letter to Oldenburg, to be reported to Leibniz. October 24, 1976, Ibid., p. 251-252.

3. N. G. Chebotarev, Collected Works. T. 3. “Newton’s polygon” and its role in the modern development of mathematics,” Publishing House of the USSR Academy of Sciences, M.-L., 1950, p. 47-80.
