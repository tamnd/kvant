---
id: 1979-2-ovchinnikov-sharyigin-reshenie-neravenstv-s-modulem-f43cc6a1
issue: kvant_1979_2
year: 1979
number: "2"
title: Solving inequalities with modulus
authors:
  - Овчинников С. В.
  - Шарыгин И. Ф.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 50
page_last: 53
page_labels: 48-51
tag: YI3I
lang: en
source: kvant_digital
extraction: vision
content_sha256: 8cd396e31740b710494bd8fbc1fc4b24e36aa58ce12ddbddc2a0954739ad24b5
prompt_sha256: draft-1
translated_from: content/ru/1979/02/articles/17_ovchinnikov-sharyigin-reshenie-neravenstv-s-modulem-f43cc6a1.md
source_content_sha256: c3755d71a3aa205d6354a10a5457da892503273ac46275af27091af76a5b94e9
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 48⟧

Solving inequalities with a model

This note outlines a technique that, in some senses, will “automatically” match the solution of inequalities containing a variable under the model sign to the solution of systems and sets of inequalities where the variables are already free from the model sign.

Let these be several inequalities - say, for simplicity, for an inequality with the same (same) variable:

$$f(x) > 0,$$
$$g(x) > 0.$$

Let us denote the set of solutions to inequality (1) by $A$, and to inequality (2) by $B$.

If you need to find a set of numbers that simultaneously satisfy inequality (1) and inequality (2), that is, find the intersection $C = A \cap B$ of the set $A$ and $B$, then inequalities (1), (2) are connected by a figure with a bracket

$$\begin{cases} f(x) > 0, \\ g(x) > 0 \end{cases}$$

and is called a system of inequalities (“Algebra and principles of analysis 10”, paragraph 123).

If you want to find a set of numbers that satisfy inequality (1) or inequality (2), that is, the union $D = A \cup B$ set $A$ and $B$, then inequalities (1), (2) are connected by square brackets

$$\begin{cases} f(x) > 0, \\ g(x) > 0 \end{cases}$$

and is called a set of non-

properties *).

Let us repeat once again: when they are looking for an intersection, they say “system”; when they are looking for an association, they say “totality.” The table shows three pairs of corresponding understood characters **).

When solving problems, as we will now see, we often have to consider combinations of systems and aggregates; To avoid mistakes in such cases, you should carefully use the following notations.

* *

A general example of solving inequalities containing a variable under the model sign—“uncovering” the model—is as follows. Based on the model definition

$$|x| = \begin{cases} x, \text{ если } x \geqslant 0, \\ -x, \text{ если } x < 0, \end{cases}$$

the set of permissible values ​​of the variable is divided into disjoint subsets, on each of which all functions containing under the sign .modula retain their sign. After this, solving the original problem is reduced to solving a set of system of inequalities.

Let, for example, you need to solve the inequality

$$|x-1| + |x-2| > 3+x$$

Dimension of the numerical axis at non-intersection

*) Absolutely similar to the definition of the terms “system of equation” and “set of equation” (“Algebra and principles of analysis 10”, paragraph 122).

**) The table could be continued with a pair of terms “conjunction - disjunction”; about these terms, see, for example, «Kvant», 1971, No. 4, p. 15, or 1947, No. 12, p. 14, or 1975, No. 1, p. 29.

⟦folio 49⟧

Choose intervals $|x| < 1$, $-(x-1)-(x-2) > 3+x$, $1 \leqslant x < 2$, $(x-1)-(x-2) > 3+x$, $x \geqslant 2$, $(x-1)+(x-2) > 3+x$.

The solution set of the upper system is the intersection $|x| < \infty$; $1[\cap] < \infty$; $0[$, that is, the interval $|x| < \infty$; $0[$, the average system has no solutions; finally, the set of solutions of the lower system is the intersection $[2; +\infty][\cap]; 6 +\infty[$, that is, the interval $|x| < \infty$; $0[$, Combining (the totality!) of the resulting sets, we get the answer: $|x| < \infty$; $0[ \cup ] 6; +\infty[$.

With this method of solution, it is often necessary to consider many cases, and sometimes subcases. In addition, sometimes revealing a model involves technical difficulties (see example 4 below).

* *

The example promised above is based on a simple theorem:

1) $|f(x)| \leqslant g(x)$ $\Leftrightarrow$ $\begin{cases} f(x) \leqslant g(x), \\ f(x) \geqslant -g(x); \end{cases}$
2) $|f(x)| \geqslant g(x)$ $\Leftrightarrow$ $\begin{cases} f(x) \geqslant g(x), \\ f(x) \leqslant -g(x). \end{cases}$

It can be easily proven by “revealing” the model. Let, for example, $x_0$ be a solution to the inequality $|f(x)| \leqslant g(x)$, that is, $|f(x_0)| \leqslant g(x_0)$.

Then $g(x_0) \geqslant 0$. If $f(x_0) \geqslant 0$, then $|f(x_0)| = f(x_0)$ and inequality (3) takes the form $f(x_0) \leqslant g(x_0)$.

Since $f(x_0) \geqslant 0$ and $g(x_0) \geqslant 0$, $f(x_0) \geqslant -g(x_0)$.

Inequalities (4), (5) mean that in the case under consideration $x_0$ is a solution to the system $\begin{cases} f(x) \leqslant g(x), \\ f(x) \geqslant -g(x). \end{cases}$ If $f(x_0) < 0$, then $|f(x_0)| = -f(x_0)$ and inequality (3) takes the form $-f(x_0) \leqslant g(x_0)$, which is equivalent to inequality (5). Inequality (4) holds in this case from the fact that $f(x_0) < 0$ and $g(x_0) \geqslant 0$.

Complete the proof of the theorem on your own.

The theorem, of course, remains valid when replacing the raising sign of the strict inequality $\leqslant$ with the sign of the strict inequality $<$.

* *

Example 1. (Georgian Faculty of Moscow State University, 1977). Solve inequality
$2|x+1| > x+4$.

Solution.
$2|x+1| > x+4 \Leftrightarrow \begin{cases} 2x+2 > x+4, \\ 2x+2 < -x-4 \end{cases} \Leftrightarrow \begin{cases} x > 2, \\ x < -2. \end{cases}$

Example 2. (Geological Faculty of Moscow State University, 1977). Solve inequality
$|x-2| \leqslant 2x^2-9x+9$.

Solution.
$|x-2| \leqslant 2x^2-9x+9 \Leftrightarrow \begin{cases} x-2 \leqslant 2x^2-9x+9, \\ x-2 \geqslant -2x^2+9x-9 \end{cases} \Leftrightarrow \begin{cases} 2x^2-10x+11 \geqslant 0, \\ 2x^2-8x+7 \geqslant 0. \end{cases}$

The solutions to the inequalities included in the resulting system are depicted with different widths on figure 1. Taking their intersection, we obtain the answer:
$-\infty; \frac{4-\sqrt{2}}{2} \cup \left[ \frac{5+\sqrt{3}}{2}; +\infty \right]$.

Let us return to the inequality that was initially solved by “opening” the model.

Example 3. Solve inequality
$|x-1| + |x-2| > 3+x$.

Fig. 1.

⟦folio 50⟧

Solution. Applying the theorem twice, we have
$$|x-1|+|x-2| > 3+x \Leftrightarrow
\Leftrightarrow |x-1| > 3+x-|x-2| \Leftrightarrow
\Leftrightarrow \begin{cases} x-1 > 3+x-|x-2|, \\ x-1 < -3-x+|x-2| \end{cases} \Leftrightarrow
\Leftrightarrow \begin{cases} |x-2| > 4, \\ |x-2| > 2x+2 \end{cases} \Leftrightarrow
\Leftrightarrow \begin{cases} x-2 > 4, \\ x-2 < -4, \\ x-2 > 2x+2, \\ x-2 < -2x-2 \end{cases} \Leftrightarrow
\Leftrightarrow \begin{cases} x > 6, \\ x < -2, \\ x < -\frac{4}{3}, \\ x < 0 \end{cases} \Leftrightarrow
\Leftrightarrow \begin{cases} x \leq 2, \\ 3^x \geq 1, \\ 3^x \geq 9, \\ x \leq 0 \end{cases} \Leftrightarrow
\Leftrightarrow \begin{cases} x \leq 2, \\ x \geq 0, \\ x \geq 2, \\ x \leq 0 \end{cases}$$

Answer: $]-\infty;0[ \cup ]6;+8[$.

Solutions to all previous problems can be easily obtained by “expanding” the model. The following example is quite difficult to solve, whereas the theorem proved makes it very easy to solve.

Example 4. Solve inequality
$$|3^x+4x-9|-8| \leq 3^x-4x-1.$$

Solution. Again applying the theorem twice:
$$||3^x+4x-9|-8| \leq 3^x-4x-1 \Leftrightarrow
\Leftrightarrow \begin{cases} |3^x+4x-9| \leq 3^x-4x+7, \\ |3^x+4x-9| \geq -3^x+4x+9 \end{cases} \Leftrightarrow
\Leftrightarrow \begin{cases} 3^x+4x-9 \leq 3^x-4x+7, \\ 3^x+4x-9 \geq -3^x+4x-7, \\ 3^x+4x-9 \geq -3^x+4x+9, \\ 3^x+4x-9 \leq 3^x-4x-9 \end{cases}$$
Thus, the required set is equal to $[0; 2] \cap (1-\infty; 0] \cup [2; +\infty]$.

Answer: $\{0, 2\}$.

We will end this note with an inequality with a parameter.

Example 5. Solve inequality
$$|1-|x||<a-x.$$

Solution.
$$1-|x||<a-x \Leftrightarrow
\Leftrightarrow \begin{cases} 1-|x| < a-x, \\ 1-|x| > -a+x \end{cases}$$

⟦folio 51⟧

solved system
$$\begin{cases} x < \frac{a+1}{2}, \\ a > -1. \end{cases}$$

On figure 4 the intersection of these two sets is shaded, that is, the set of solutions of the system equivalent to the original inequality. From this figure it is already quite easy to write down the answer: for $a \in ] -\infty; -1]$ there are no solutions, for $a \in ] 1; +\infty[$

We have $x \in ] -\infty; \frac{a-1}{2}$[$,$ for $a \in ] 1; +\infty[$

We have $x \in ] -\infty; \frac{a+1}{2}$[$.$

An attentive reader may notice the following: if the authors have already resorted to the plane $Oxa$, then wouldn’t it have been easier from the very beginning to depict the graph of the function on this plane
$$a=x+|1-|x|$$
and, looking at the area above this graph, write down the answer. This reader is certainly right. (The red line at figure 4 is the graph of the function $a=x+|1-|x|$.)

The method using a coordinate plane, one of whose axes is the axis of parameter values, is very powerful, and many difficult problems are solved with its help.

Shocked
Solve the following inequalities (problems 1-4):
1. (Biology Faculty of Moscow State University, 1968) $|3x+2| \leq x^2+x$.
2. (Faculty of Physics, Moscow State University, 1974) $3|x-1| > (x-1)^2+1$.
3. (Georgian Faculty of Moscow State University, 1977)
a) $3|x-1| \leq x+3$;
b) $4|x+2| < 2x+10$;
b) $3|x+1| \geq x+5$.
4. (Geological Faculty of Moscow State University, 1977)
a) $3x^2-|x-3| > 9x-2$;
b) $x^2+4 \geq |3x-2|-7x$;
b) $x^2-|5x-3| < x<2$.
5. (Department of Political Economics, Faculty of Economics, Moscow State University, 1977)
a) Determine for which $a$ the inequality $3-|x-a| > x^2$ has at least one negative solution.
b) Determine for which $a$ the inequality $2>|x+a|+x^2$ has at least one positive solution.

*) See «Kvant», 1970, No. 9, p. 19.
