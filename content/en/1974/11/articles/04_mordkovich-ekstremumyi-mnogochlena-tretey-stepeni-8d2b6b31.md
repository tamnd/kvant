---
id: 1974-11-mordkovich-ekstremumyi-mnogochlena-tretey-stepeni-8d2b6b31
issue: kvant_1974_11
year: 1974
number: "11"
title: Extrema of a polynomial of the third degree
authors:
  - Мордкович А. Г.
rubric: osnovnye-stati
page_first: 10
page_last: 12
page_labels: 8-10
tag: NU4P
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6e7b4db221cee12e2856cc2f048015f4340480bf884499d62bb4bc6ceb5a253b
prompt_sha256: draft-1
translated_from: content/ru/1974/11/articles/04_mordkovich-ekstremumyi-mnogochlena-tretey-stepeni-8d2b6b31.md
source_content_sha256: e2a2f8ee39b85c52880236241828a4a73a75c81e1abfc889cb4ea6e20ee5e849
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 8⟧

Extrema of a polynomial of the third degree

This article is the fourth in a series of articles devoted to cubic functions and equations *) It will focus on finding the maximum and minimum points of the functions $y = ax^3 + bx^2 + cx + d$

First, let's look at the function $y = ax^2 + bx + c$ (1)
$(a \neq 0)$. Let $x = \alpha$ be the root of function (1). What does the graph of this function look like in a fairly small neighborhood of the point $x = \alpha$?

There are four possible cases here - they are presented in Figures 1-4. In the first and second cases we say that the function is monomonous at the point $x = \alpha$ (in the first case it increases, in the second it kills). In the third and fourth cases the function is said to have an extremum at point $x = \alpha$

*) See articles: V. G. Yankelevich, 《Irreducible》 case, 《Kvant》, 1971, No. 11; O. A. Zhautykov, Graph of cubic tetraevent, 《Kvant》, 1972, No. 6; O. A. Zhautykov, On the boundaries of the roots of the cubic equation, 《Kvant》, 1973, No. 12.

(in the third case - minimum, in the fourth - maximum)*.

What is the fundamental difference between the first and second cases from the third and fourth? The fact is that in the first two cases the function changes sign when passing the point $x = \alpha$ (for example, in the first case $y < 0$ at $x < \alpha$ and $y > 0$ at $x > \alpha$;

*) Sometimes they say that a function has a local extremum (maximum, minimum). 《Local》means “local”: in some neighborhoods of the point $x = \alpha$ the function values ​​do not exceed $f(\alpha)$, although “far” from the point $x = \alpha$ the values ​​$f(x)$ may exceed $f(\alpha)$. In the terminology we have adopted (see also B. E. Weitz, I. T. Demidov, Algebra and the beginnings of analysis, grade 9, professional textbook edited by academician A. N. Kolmogorov, § 69) a function can have many maxims and minimms, which are defined as local concepts.

Fig. 1. Fig. 2. Fig. 3. Fig. 4.

⟦folio 9⟧

here the values ​​of $x$ are chosen sufficiently close to the point $x = \alpha$), and in the last two cases the function does not change sign when passing the point $x = \alpha$.

Let's try to find a necessary and sufficient condition for the point $x = \alpha$ the root of the polynomial $y = ax^2 + bx + c$ to be an extremum point. Let us transform function (1) to the form

$$y = a (x - \alpha)(x - \beta)$$

($\alpha$ and $\beta$ are the roots of a square triangle; try to prove that if $x = \alpha$ is the root of function (1), then it can be represented in the form where $\beta$ is a real number).

If $\alpha \neq \beta$, then in a sufficiently small neighborhood of the point $x = \alpha$ (at $|x - \alpha| < |\alpha - \beta|$) the expression $a (x - \beta)$ retains a constant sign, which means that the function $y = a (x - \alpha) \times (x - \beta)$ changes sign when passing through the point $x = \alpha$. In this case there is no extremum. If $\alpha = \beta$, then we get $y = a (x - \alpha)^2$; this function does not change sign when passing the point $x = \alpha$.

So, the root of a square triangle is its extremum point of the model and the mol of the model, when this root is double.

The generalization of the obtained result is as follows:

Theorem 1. In order for the point $x = \alpha$ to be an extremum point of the function $y = ax^2 + bx + c$, it is necessary and sufficient that there exist a maximum number $m$ for which the polynomial $ax^2 + bx + c - m$ has a double root $x = \alpha$.

To prove this theorem, it is enough to know the point $x = \alpha$ if and only if the function $y = f(x) - m$, where $m = f(\alpha)$, has an extremum at this point.

This result is used in practice.

Example 1. Find the extremum points of the function

$$y = ax^2 + bx + c.$$

Let us select the numbers $\alpha, m$ so that the identity holds

$$ax^2 + bx + c - m = a (x - \alpha)^2.$$

We have

$$ax^2 + bx + c - m = ax^2 - 2a\alpha x + a\alpha^2.$$

But two polynomials are also equal if and only if their coefficients are equal for the same powers; therefore we get a system of equations

$$\begin{cases} -2a\alpha = b, \\ a\alpha^2 = c - m, \end{cases}$$

from which it is located

$$\alpha = -\frac{b}{2a}, \quad m = \frac{4ac - b^2}{4a}.$$

So, $x = -\frac{b}{2a}$ is the extremum point of the function $y = ax^2 + bx + c$ (and the point of local maximum, if $a > 0$, and local minimum, if $a < 0$).

Now let's look at the function

$$y = ax^3 + bx^2 + cx + d.$$

Below we will prove that for it it is possible to formulate and prove a theorem similar to Theorem 1. But first we will prove some auxiliary results.

Lemma. Let a polynomial of degrees $y = ax^3 + bx^2 + cx + d$ ($a \neq 0$) be given, and let $x = \alpha$ be its real root. Then

$$ax^3 + bx^2 + cx + d = a (x - \alpha)(x^2 + px + q),$$

$p$ and $q$ are also some real numbers.

Proof. Under conditions $a\alpha^3 + b\alpha^2 + c\alpha + d = 0$.

Then

$$ax^3 + bx^2 + cx + d = (ax^3 + bx^2 + cx + d) - (a\alpha^3 + b\alpha^2 + c\alpha + d) = a (x^3 - \alpha^3) + b (x^2 - \alpha^2) + c (x - \alpha) = (x - \alpha) [ax^2 + (a\alpha + b) x + (a\alpha^2 + b\alpha + c)] = a (x - \alpha)(x^2 + px + q),$$

Where

$$p = \frac{a\alpha + b}{a}, \quad q = \frac{a\alpha^2 + b\alpha + c}{a}.$$

⟦folio 10⟧

Let us now try to find the necessary and sufficiently conditional conditions for the point $x = \alpha$ the root of the polynomial (2) to be the extremum point of the function $y = ax^3 + bx^2 + cx + d$.

Let's use formula (3). If $x = \alpha$ is not the root of the square trinomial $x^2 + px + q$, then in a sufficiently small neighborhood of the point $x = \alpha$ this trinomial retains a constant sign, and therefore the function $y = a(x - \alpha)(x^2 + px + q)$ changes sign when passing the point $x = \alpha$. The same will be the case when $x = \alpha$ is the double root of a trinomial, that is, $x^2 + px + q = (x - \alpha)^2$ and therefore $y = a(x - \alpha)^3$. In the cases considered, there is no extremum. And only in one case does the function not change sign when passing the point $x = \alpha$ - when $x = \alpha$ is the single root of the square trinomial, that is, $x^2 + px + q = (x - \alpha)(x - \beta)$, or, what is the same, $x = \alpha$ is the double root of the polynomial (2), that is

$$y = a(x - \alpha)^2(x - \beta),$$

where $\alpha \neq \beta$.

So, the root of a polynomial has a degree that is its extremum point and its mole when this root is double.

The result obtained is summarized as follows:

Theorem 2. In order for the point $x = \alpha$ to be an extremum point of the function $y = ax^3 + bx^2 + cx + d$, it is necessary and sufficient that there exist any number $m$ for which the polynomial $P(x) = ax^3 + bx^2 + cx + d$ has a double root $x = \alpha$, that is

$$P(x) = a(x - \alpha)^2(x - \beta),$$

(4)

food $\alpha \neq \beta$.

Theorem 3 (sufficient conditions for maximum and minimum). Let the function $y = ax^3 + bx^2 + cx + d$ have an extremum at the point $x = \alpha$ and $m$ be the value of the function at the point $x = \alpha$. Let us represent the polynomial $P(x) = ax^3 + bx^2 + cx + d$ in the form (4). Then, if $a(\beta - \alpha) > 0$, then $x = \alpha$ is the maximum point; if $a(\beta - \alpha) < 0$, then $x = \alpha$ is the minimum point.

Proof. If $a > 0$ and $\alpha < \beta$, then in a neighborhood of the point $x = \alpha$, which does not contain the point $x = \beta$ (Fig. 5), we have $P(x) \leq 0$, that is, $y \leq m$. This means that $x = \alpha$ is the maximum point. If $a < 0$ and $\alpha > \beta$, then the maximum point is also obtained. Combining these two cases, we find that if $a(\beta - \alpha) > 0$, then at the point $x = \alpha$ the function $y$ has a maximum. The second part of the theorem is proved in a similar way.

Example 2. Examine the function for extremum

$$y = x^3 - 3x^2 - 9x + 5$$

(5)

and plot it.

Let's try to choose the numbers $m$, $\alpha$, $\beta$ so that the identity $x^3 - 3x^2 - 9x + 5 - m = (x - \alpha)^2 \times (x - \beta)$ holds (and $\alpha \neq \beta$). Hence $x^3 - 3x^2 - 9x + 5 - m = x^3 - (\beta + 2\alpha)x^2 + (2\alpha\beta + \alpha^2)x - \alpha^2\beta$. To find the values ​​of $m$, $\alpha$, $\beta$ we received a system of equations:

$$\begin{align*}
\alpha_1 &= -1, \quad \beta_1 &= 5, \quad m_1 &= 10; \\
\alpha_2 &= 3, \quad \beta_2 &= -3, \quad m_2 &= -22.
\end{align*}$$

Fig. 5.
