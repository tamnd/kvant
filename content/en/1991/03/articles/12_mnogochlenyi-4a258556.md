---
id: 1991-3-mnogochlenyi-4a258556
issue: kvant_1991_3
year: 1991
number: "3"
title: Polynomials
rubric: kaleydoskop-kvanta
rubric_sub: Калейдоскоп
page_first: 42
page_last: 43
page_labels: 40-41
lang: en
source: kvant_digital
extraction: vision
content_sha256: ec9dfd9c7ff612eca19447e96c7dad6cbda460d304c45405504135d5d8c10f12
prompt_sha256: draft-1
translated_from: content/ru/1991/03/articles/12_mnogochlenyi-4a258556.md
source_content_sha256: 53fe0c5f43d9b8329bc59b6c89cf0a7376697e7b0d7dd5e136ba6d2b9e01cded
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 40⟧

---
running_head:
folio:
---

Polynomials

Among the most important mathematical concepts, polynomials occupy one of the first places. As is known, a polynomial in one variable is a function of the form $P_n(x) = a_nx^n + a_{n-1}x^{n-1} + \dots + a_1x + a_0$. The number $n$ is called the degree of the polynomial. If we consider the set of all polynomials, then their properties are completely similar to the properties of integers. Indeed, the sum, difference and product of polynomials are always polynomials. In this case, commutative, associative and distributive laws are fulfilled. The ratio of two polynomials will no longer always be a polynomial, and for them, as for numbers, “division with a remainder” takes place, i.e. for any two polynomials $P_n(x)$ and $Q_m(x)$, where $n \geqslant m$, there is a polynomial $D_{n-m}(x)$ degree $n-m$ - the quotient and a polynomial $R_k(x)$ degree $k < m$ — the remainder for which the equality $P_n(x) = Q_m(x) \times D_{n-m}(x) + R_k(x)$ holds. In the case where $Q(x) = x-a$, the remainder $R_0(x)$ will have degree zero, i.e. it will be a number. At the end of the 18th century, the French mathematician E. Bezout (1730-1783) discovered that this remainder is equal to $P(a)$. Similarly, polynomials with integers could be continued. But polynomials have a more complex structure than integers. One of the most important characteristics of a polynomial is the set of numbers $x$ for which it is processed to zero—the roots of the polynomial. The scribes of Ancient Egypt and Ancient Babylon were able to find the roots of polynomials of the first degree. Babylon also knew how to find roots of polynomials of the second degree, that is, he knew how to solve quadratic equations.

People only learned to find roots of polynomials of the third degree, that is, to solve cubic equations, only in the 16th century. The history of the discovery of the formula for the roots of a cubic equation is one of the most striking and dramatic pages in the history of mathematics. It is not difficult to show that by a simple change of variable any cubic equation can be reduced to the form $x^3 + px = q$. For the case of positive $p$ and $q$ this problem was solved by C. Ferro (1465–1526). However, at that time negative numbers were not included in the bypass of mathematicians, and he had to learn to solve the equations $x^3 + q = px$, $x^3 + px + q = 0$ and $x^3 = px + q$. S. Ferro communicated his method of this to his student A. Fiore, and he challenged the remarkable Italian mathematician Niccolo Tartaglia (1499-1557) to a mathematical tournament on solving an equation of the third degree. A few days before the start of the tour, Tartaglia found a general method for solving cubic equations and during the execution, in two hours, he solved all 30 problems proposed to him; his opponent could not solve any of the 30 problems proposed to him by Tartaglia.

The formula found by Tartaglia for solving the equation $x^3 + px + q = 0$
$x =$
$\sqrt{-q/2} + \sqrt{q^2/4} + \sqrt{p^3/27}$
$\sqrt{-q/2} - \sqrt{q^2/4} + \sqrt{p^3/27}$

received the name “Cardan Formula” in honor of another Italian mathematician J. Cardan (1501-1576), who learned it from N. Tartaglia and according to the agreement, published it in his book. Soon, one of J. Cardan’s students, L. Ferrari (1522–1565), found a formula for solving a fourth-degree equation.

And only two more years later in the work of the outstanding mathematician J. Lagrange (1736-1813), P. Ruffini (1765-1822) and N. Abel (1802-1829) it was shown that there is no general formula for finding the roots of an equation of the fifth and higher degrees. And in the work of E. Galois (1811-1832) a method was found by which for any polynomial one can determine whether its roots are expressed in terms of radicals.

Further development of the theory of polynomials is associated with the introduction of complex numbers in mathematics. In 1799, the outstanding German mathematician K. F. Gauss (1777-1855) proved a theorem that is rightly called the “fundamental theorem of algebra”: every polynomial of non-zero degree has at least one root (sixth or complex).

⟦folio 41⟧

---
running_head:
folio:
---

From this and from Bezout’s theorem it follows that an equation of the $n$th degree has exactly $n$ roots (their averages can be multiple).
Back in the 16th century, the French mathematician F. Viète (1540–1603) discovered correspondences between the roots of the polynomial $x^n + a_1x^{n-1} + \dots + a_{n-1}x + a_n = 0$ and its coefficients:
$$x_1 + x_2 + \dots + x_n = -a_1,$$
$$x_1x_2 + x_2x_3 + \dots +$$
$$\dots + x_{n-1}x_n = a_2,$$
$$x_1x_2 \dots x_n = (-1)^n a.$$

It is easy to see that the degree of this polynomial is $n$.

The so-called Vieta formulas are also true if some (or all) roots are complex numbers. You know Vieta's formula for the quadratic trinomial $x^2 + px + q$:
$$x_1 + x_2 = -p,$$
$$x_1x_2 = q.$$

Polynomials are the simplest and most studied functions in mathematics.

guarantee that the corresponding polynomial can always be written. It was once proposed by I. Newoton (1643-1727), and it was called “Newoton’s integration polynomial”. At given points $x_0, x_1, \dots, x_n$ this polynomial takes given values ​​$y_0, y_1, \dots, y_n$.

This polynomial
$$\frac{(x-x_1)(x-x_2) \dots (x-x_n)}{(x_0-x_1)(x_0-x_2) \dots (x_0-x_n)} +$$
$$\frac{(x-x_0)(x-x_2) \dots (x-x_n)}{(x_1-x_0)(x_1-x_2) \dots (x_1-x_n)} +$$
$$\frac{(x-x_0)(x-x_1) \dots (x-x_{n-1})}{(x_n-x_0)(x_n-x_1) \dots (x_n-x_{n-1})}.$$

If we want to use some function $f(x)$ in a neighborhood of the point $x_0$, then it is very useful to approximate with a polynomial
$$f(x_0) + \frac{f'(x_0)}{1!} (x-x_0) +$$
$$+ \frac{f''(x_0)}{2!} (x-x_0)^2 + \dots$$
$$+ \frac{f^{(n)}(x_0)}{n!} (x-x_0)^n,$$
proposed by the English mathematician W. Taylor (1685-1731).

Outstanding mathematicians, in particular K. Weierstrass (1815-1897) and P. L. Chebyshev (1821-1894), dealt with the issues of approximating a function given on a segment using polynomials for which the value of the function of the value of the polynomial at each point is no more than a given number, for example, 0.001. The “Chebyshev polynomials” are widely known.
These are polynomials of the form $x^n + a_1x^{n-1} + \dots + a_{n-1}x + a_n$ whose values ​​deviate least from zero (note that the coefficient of $x^n$ is 1). Chebyshev proved that such polynomials are the polynomials $T_n(x) = \frac{1}{2} \cos(n \arccos x)$.

In mathematics, polynomials in several variables are also considered

nykh. Thus, polynomials of the first degree in two variables are described by the expression $ax + by + c$, and polynomials of the second degree in two variables by the expression $ax^2 + bxy + cy^2 + dx + ey + f$. If we equate this expression to zero, we obtain a second-order curve equation. These include the circle, ellipse, hyperbola and parabola.
