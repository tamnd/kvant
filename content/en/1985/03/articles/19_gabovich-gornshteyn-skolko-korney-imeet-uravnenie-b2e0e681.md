---
id: 1985-3-gabovich-gornshteyn-skolko-korney-imeet-uravnenie-b2e0e681
issue: kvant_1985_3
year: 1985
number: "3"
title: How many roots does the equation have?
authors:
  - Габович И. Г.
  - Горнштейн П. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 45
page_last: 48
page_labels: 43, 44, 46
tag: LJ5F
lang: en
source: kvant_digital
extraction: vision
content_sha256: 808feca7b8b2b9ec05e83e0ce31035b3f99cdd88df14ceb2e8ee3a9b7db2a3c8
prompt_sha256: draft-1
translated_from: content/ru/1985/03/articles/19_gabovich-gornshteyn-skolko-korney-imeet-uravnenie-b2e0e681.md
source_content_sha256: eaf9370ee3c1e4cd759a58324b4312a3fa321ffe3257ea2eef3f13fee06d209b
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 43⟧

How many roots does the equation have?

I. G. GABOVICH,
P. I. GORNITEIN

In advanced university exams, examples are often offered in which it is required to determine how many roots a given equation has. Note that in these examples it is most often necessary to find only the number of roots, and not the roots themselves.

A more difficult analytical question is with respect to an equation containing a parameter. In this case, it is proposed to determine at what value of the parameter the given equation has one, two or other finite number of roots.

This article is aimed at solving such examples.

Example 1 (KSU, Mechanics and Mathematics, 1981). How many roots does the equation have?
$$x^2 - 2x - \log_2|1-x| = 3?$$
(1)

Solution. Let us rewrite equation (1) in the form
$$x^2 - 2x - 3 = \log_2|x - 1|.$$
(2)

It is clear that (2) ⇔ (1). Note also that the sign of the expression under the abscissa sign can be changed to the opposite.

The number of roots of equation (2) is equal to the number of intersection points of the graphs of functions that are the left and right sides of equation (2). The graphs of these functions (Fig. 1) intersect at four points ($A, B, C$ and $D$). Consequently, equation (2), and hence the equivalent equation (1), has even roots (equal to the abscissa of the intersection points).

Example 2 (MSU, VMK, 1980). At what values ​​of the parameter a does the equation
$$(a+1)x^2 - ax + (a-3) = 0$$
(3)
has at most one real root?

Solution. 1) Let $a \neq -1$. Then equation (3) is quadratic and has at most one real root if $D \leqslant 0$, that is
$$a^2 - 4(a+1)(a-3) \leqslant 0 \Leftrightarrow 3a^2 - 8a - 12 \geqslant 0.$$
(4)

The square trinomial $3a^2 - 8a - 12$ has roots: $a_1 = (4-2\sqrt{13})/3$ and $a_2 = (4+2\sqrt{13})/3$. It is clear that $a_2 > -1$. Let us show that $a_1 < -1$:
$$-1 - (4-2\sqrt{13})/3 = (2\sqrt{13} - 7)/3 = (\sqrt{52} - 7)/3 > 0;$$
this means that $a_1 < -1$.

Therefore, the solution to (4) will be to merge the intervals:
$$] -\infty; (4-2\sqrt{13})/3] \cup \cup[(4+2\sqrt{13})/3; \infty[.$$
2) At $a = -1$, equation (3) turns into an equation of the first degree: $x - 4 = 0$, which has one real root.

Thus, we get the following answer:
$$a \in ] -\infty; (4-2\sqrt{13})/3] \cup \cup\{-1\} \cup [(4+2\sqrt{13})/3; \infty[.$$
Example 3 (MIEM, 1982). Solve the equation
$$|2x+2| = ax^2 + 4$$
(5)
and determine the values ​​of $a$ for which it has a unique solution.

Solution. Equation (5) is equivalent to a set of two mixed systems:
$$\begin{cases} x < -1; \\ -2x - 2 = ax^2 + 4; \\ x \geqslant -1; \\ 2x + 2 = ax^2 + 4; \end{cases} \Leftrightarrow \begin{cases} x < -1; \\ ax^2 + 2x + 6 = 0; \\ x \geqslant -1; \\ ax^2 - 2x + 2 = 0. \end{cases}$$

⟦folio 44⟧

Taking into account that $x \neq 0$, we obtain the dependence $a=f(x)$, which has different similar expressions on each of the intervals to be sorted:

$$a = (-2x - 6)/x^2 = f_1(x) \text{ при } x < -1 \text{ и } a = (2x - 2)/x^2 = f_2(x) \text{ при } x \geq -1.$$

Let's plot this dependence in the coordinate system $xOa$ (Fig. 2). The graphs of functions $f_1(x)$ and $f_2(x)$ are “solid” blue and red curves, respectively. The union of these lines is the $a=f(x)$ plot. (The dotted blue and red curves are graphs of the dependence $f_1(x)$ and $f_2(x)$ outside the intervals on which they are plotted. These dotted lines are found below when selecting solutions.) The blue and red curves intersect at the point with coordinates $(-1; -4)$.

An examination of the functions $f_1(x)$ and $f_2(x)$ shows (as can also be seen in figure 2) that $\max f_1(x) = f_1(-6) = \frac{1}{6}$ and $\max f_2(x) = f_2(2) = \frac{1}{2}$.

The abscissas of the points at which the straight line parallel to the $Ox$ axis intersects the solid lines are solutions to equation (5).

From the given figure and the comments made above, it follows that equation (5) has:

a) For $a \in ]-\infty; -4]$ there are two solutions: $x_{1,2} = (1 \pm \sqrt{1-2a})/a$, determined from the equation

$$ax^2 - 2x + 2 = 0.$$

6) At $a \in ]-4; 0[$ there are two solutions: $x_1 = (-1 + \sqrt{1-6a})/a$ and $x_2 = (1 - \sqrt{1-2a})/a$

Table

| Meanings of $a$ | Number of solutions | Solutions |
| :--- | :--- | :--- |
| $a \in ]-\infty; -4]$ | two | $x_{1,2} = (1 \pm \sqrt{1-2a})/a$ |
| $a \in ]-4; 0[$ | two | $x_1 = (-1 + \sqrt{1-6a})/a; x_2 = (1 - \sqrt{1-2a})/a$ |
| $a=0$ | two | $x_1 = -3$ and $x_2 = 1$ |
| $a \in ]0; 1/6[$ | four | $x_{1,2} = (-1 \pm \sqrt{1-6a})/a; x_{3,4} = (1 \pm \sqrt{1-2a})/a$ |
| $a=1/6$ | three | $x_1 = -6; x_{2,3} = 6 \pm 2\sqrt{6}$ |
| $a \in ]1/6; 1/2[$ | two | $x_{1,2} = (1 \pm \sqrt{1-2a})/a$ |
| $a=1/2$ | one | $x=2$ |
| $a \in ]1/2; \infty[$ | 0 | - |

⟦folio 46⟧

]1; ∞[, that is, when
$$0 < a < a_m,$$
(12)

equation (11) has three roots. This is due to the fact that for the values ​​of $a$ indicated in (12), the straight line $y = ax$ intersects the graph of the function $f(x)$ at three points: at one point - a branch of the curve on the interval ]0; 1[ and at two points - on the interval ]1; ∞[. The abscissas of these points will be the roots of equation (11).

It may seem that for small positive $a$ the straight line $y = ax$ will intersect the branch of the graph of the function $f(x)$ on the interval ]1; ∞[ only at one point, the abscissa of which is close to one. But this opinion is wrong. It is known that as $x$ increases, a power function grows rapidly logarithmically (“Algebra and Principles of Analysis 9-10” 1980, paragraph 70, p. 214). Therefore, for any $a > 0$ and any small abscissa value, the straight line $y = ax$ will twice intersect the branch $f(x)$ corresponding to the interval ]1; ∞[.

Let us now determine at what value $a$ the straight line $y = ax$ touches the mentioned branch.

Let $A(x_0, y_0)$ be the point of tangency. Then the desired value $a$ is found from the system
$$\begin{cases} f(x_0) = g_a(x_0), \\ f'(x_0) = g'_a(x_0) \end{cases}$$ or $$\begin{cases} \ln x_0 = ax_0, \\ \frac{1}{x_0} = a, \end{cases}$$

whence $x_0 = 1/a$; $\ln(1/a) = 1 \Rightarrow a = e^{-1}$.

So, $a_m = e^{-1}$. Therefore, for $a \in ]0; e^{-1}$[ equation (10) has three roots.

The examples discussed in the article are different in content. To solve some, we used graphs for clarity, while others were solved only analytically.

At the same time, having familiarized yourself with the solutions given, you have acquired some skills that you will be able to apply in solving other similar examples and, in particular, those given in the exercises.

Exercises
1 (MSU, Khimak, 1982). For what values ​​of the parameter $p$ the equation
Does $$(x - p)^2 \cdot [p(x - p)^2 - p - 1] = -1$$ have more positive roots than negative ones?
2 (LSU, Math., 1979). How many roots does the equation have?
$$(x + 2)e^{-x/2} - x^4/6 - x^8/20 = x^2 + 1$$

3 (NSU, mechanics, 1977). Determine for what values ​​of $a$ the equation $\log_2(x + 1) = 1/2$ has a unique solution.
4 (LSU, Math., 1980). For what values ​​of the parameter $a$ the equation
$$\sin x \cdot \cos 2x \cdot \sin 3x = a$$ has exactly two roots on the segment $[\pi/4; \pi/2]$?
5 (MSU, VMK, 1980). For what values ​​of the parameter $a$ the equation
Does $$(3a - 1)x^2 + 2ax + 3a - 2 = 0$$ have two real roots?
6 (MSU, mechanics, 1980). For what values ​​of the parameter $a$ the equation
Does $$4^{-|x - a|} \cdot \log_3(x^2 - 2x + 3) + 2^{-x^2 + 2x} \times \log_1/3(2|x - a| + 2) = 0$$ have exactly three distinct roots?
7 (MSU, general geology, 1979). Find all values ​​of $a$ for which the equation
$$x^2 + 6x/(\sqrt{\sin a} + 9\sqrt{3}/\cos a + 36) = 0$$ has a unique solution.
8 (Ural State University, mathematics, 1981). For what values ​​of the parameter $a$ the equation
Does $$\log_{\sqrt{ax - 6}}(2x^2 - 3x + 2) = 2\log_{ax - 6}(x^2 + 2x - 4)$$ have a unique solution?
9 (MSU, Khimak, 1980). Find all such values ​​of $k$, for each of which the number of solutions with respect to $x$ of the equation
$$2x^3 + 6x = (3^6k - 9)\sqrt{2^8k - 1/6} - (3k - 1)^2 \cdot 12^x$$ is not less than the number of solutions with respect to $y$ of the equation
$$3(5y^2 - k^4) - 2y = 2k^2(6y - 1).$$
10 (MEPhI, 1980). Find the value of $c$ for which the equation
$$2\log_7(cx - 2) = \log_7(-x^2 - 9x - 18)$$ has only one solution.
11 (MIEM, 1980). Find for $a = 1$ all solutions of the equation
$$\sin(2(x - \pi)) - \sin(3x - \pi) = a \sin x$$ located on the segment $[0; \pi/2]$, and find out at what values ​​the equation has a unique solution on this segment.
12 (LETI, 1982). Given a function $y = f(x)$, where
$$f(x) = x^2 + x + 9/(x^2 + x + 1).$$ For what values ​​does $f(x) = a$ have 4 roots?
13 (LETI, 1982). How many roots does the equation have?
$$\log_2\sin x = x^2 - 36?$$
14 (LETI, 1982). For what values ​​of $a$ the equation
Does $$\sqrt{x + a} = x$$ have 2 roots?
15 (MISiS, 1983). At what $a$ the equation
Does $$|x + 2| - |2x + 8| = a^2$$ have a unique solution?
16 (MISiS, 1983). For what values ​​of the parameter $a$ does the equation $|x^2 - 6x + 8| + |x^2 - 6x + 5| = a$ have more than three solutions?
17 (MSU, VMK, 1983). For all $a$, solve the equation
$$(x + 2)(x + 4) + 5(x + 2)\sqrt{\frac{x + 4}{x + 2}} = (a + 2)(a - 3).$$
