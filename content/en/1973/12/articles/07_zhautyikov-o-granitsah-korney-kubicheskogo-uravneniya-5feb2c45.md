---
id: 1973-12-zhautyikov-o-granitsah-korney-kubicheskogo-uravneniya-5feb2c45
issue: kvant_1973_12
year: 1973
number: "12"
title: On the boundaries of the roots of the cubic equation
authors:
  - Жаутыков О. А.
rubric: osnovnye-stati
page_first: 23
page_last: 25
page_labels: 21-23
tag: KPKG
lang: en
source: kvant_digital
extraction: vision
content_sha256: c4b1aa85056f1b126bbe70587ce4d80ce4782bdb7eff14c4af5350f95a02bed0
prompt_sha256: draft-1
translated_from: content/ru/1973/12/articles/07_zhautyikov-o-granitsah-korney-kubicheskogo-uravneniya-5feb2c45.md
source_content_sha256: 10c5ae07cf2d4d646688d1d014d5277b7a164a4403f4cb4b4a94b82da76cccd5
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 21⟧

On the boundaries of the roots of the cubic equation

As you know, formulas that allow you to accurately express the roots of a cubic equation through its coefficients, the weights of the mass. Therefore, it is often important to approximate the roots of the cubic equation.

This article evaluates the boundaries within which the real roots of a cubic equation can lie.*)

Consider the cubic equation
$$ax^3 + bx^2 + cx + d = 0,$$
(1)
coefficients $a, b, c, d$ are real numbers, $a \neq 0$. The first term $ax^3$ on the left side of equation (1) is called its old term, the last term $d$ is called the free term.

As is known**), equation (1) has three roots, one of which is real, and the other two are either real or complex conjugate. We will be interested only in the real roots of equation (1). Our goal is this: without calculating the roots themselves, we will obtain non-comoric boundaries (estimates) for them, that is, indicating the integrals on the real axis in which these roots lie.

To do this, together with equation (1), we consider a third-degree polynomial
$$y = ax^3 + bx^2 + cx + d.$$

What can be said about the behavior of this function for large absolute values ​​of $x$? If the argument $x$ takes an increase in the absolute value of the value, then the absolute

*) This article is a continuation of the series of materials devoted to the cubic equation (see «Kvant», 1971, No. 11, 1972, No. 6).
**) See «Kvant», 1971, No. 11, p. 20-21.

The lot value of each term on the right side of equation (2) will increase, and the higher the degree of this term, the faster.

It is clear that the absolute value of the leading term $ax^3$ will increase most quickly. Therefore, we can expect that if we choose the value of $|x|$ large enough, then the absolute value of the leading term $ax^3$ will be greater than the absolute value of the sum of all other terms, that is
$$|ax^3| > |bx^2 + cx + d|.$$

Let us prove that this inequality is valid for all $x$ sufficiently large in absolute value.

Since the absolute value of the sum does not exceed the sum of the absolute values ​​of the terms, then
$$|bx^2 + cx + d| \leq |b| \cdot x^2 + |c| \cdot |x| + |d|.$$

Setting $|x| = v$, we rewrite this inequality:
$$|bx^2 + cx + d| \leq |b| \cdot v^2 + |c| \cdot v + |d|.$$

The coefficients $|b|, |c|$ and $|d|$ on the right side of inequality (4) are non-negative real numbers; let us denote the largest of them by $M$:
$$M = \max(|b|, |c|, |d|).$$

If on the right side of inequality (4) instead of each of the coefficients $|b|, |c|, |d|$ we substitute the number $M$,

⟦folio 22⟧

then inequality (4) is only a success. Therefore, the inequality is true
$$|bx^2 + cx + d| \leq M(v^2 + v + 1),$$
which, if we use the well-known identity,
$$v^2 + v + 1 = \frac{v^3 - 1}{v - 1}, \quad v \neq 1,$$
can be written in the form
$$|bx^2 + cx + d| \leq M \frac{v^3 - 1}{v - 1}.$$
Since we are interested in large values ​​of $|x| = v$, we will assume that $v > 1$. But then
$$\frac{M(v^3 - 1)}{v - 1} < \frac{Mv^3}{v - 1},$$
and therefore inequality (6) will take the form
$$|bx^2 + cx + d| < \frac{Mv^3}{v - 1}, \quad |x| = v > 1.$$
(7)

If we manage to show that the absolute value of the leading term $ax^3$ for all values ​​$x$ sufficiently large in absolute value (such that the condition $v > 1$ is also satisfied) is greater than the expression $\frac{Mv^3}{v - 1}$, which is on the right side of inequality (7), then inequality (3) will be proven. Let's see how to choose $|x| = v$ so that the inequality $|ax^3| > \frac{Mv^3}{v - 1}$ is satisfied, that is
$$|a|v^3 > \frac{Mv^3}{v - 1}.$$
Solving the resulting inequality with respect to $v$, we find that it is certainly true for all
$$v > \frac{M+|a|}{|a|}.$$
Since $\frac{M+|a|}{|a|} \geq 1$ (since $M \geq 0$), then under condition (8) the inequality $v > 1$ is always satisfied. This establishes that inequality (3) is valid for
$$|x| \geq \frac{M+|a|}{|a|}.$$
It follows that for values ​​of $x$ satisfying condition (9), function (2) cannot vanish. In other words, all real roots of equation (1) satisfy the inequality
$$|x| \leq \frac{M+|a|}{|a|}.$$
The positive number $A = \frac{M+|a|}{|a|}$ is called the upper bound of the real roots of the cubic equation (1).
It turns out that it is also possible to find a lower bound for the real roots of the cubic equation (1), that is, a non-negative number $B$ such that all real roots of equation (1) satisfy the inequality $|x| \geq B$.
To do this, we need to replace equation (1)
$$x = \frac{1}{z}.$$
(11)

Then after the next transformations we obtain the equation
$$dz^3 + cz^2 + bz + a = 0.$$
(We will assume that in equation (1) the free term $d \neq 0$, or the case $d = 0$ is of no interest (equation (1) in this case has the root $x = 0$, and its remaining roots are determined from the quadratic equation).
Since $|x| = \frac{1}{|z|}$ (see (11)), it is clear that the inequality $|z| < K$, where $K > 0$, implies the inequality $|x| > \frac{1}{K}$.
Pozny, if as $K$ we take the upper bound of the real roots of equation (12), then the number $\frac{1}{K}$ will be the lower bound of the real roots of equation (1). But we already know how to find the upper limit $K$ of the real roots of equation (12) (see (5), (10)):
$$K = \frac{N+|d|}{|d|},$$
Where
$$N = \max(|c|, |b|, |a|).$$
(13)

⟦folio 23⟧

Pozny's lower bound for the real roots of the cubic equation (1) is:

$$B = \frac{|d|}{N + |d|}.$$

It remains to note that this formula is also valid in the case of $d = 0$, then the lower bound is obviously equal to zero (since it has a zero root), and exactly the same result is obtained from formula (14) (in this case, of course, $N \neq 0$, or in equation (1) by assumption $a \neq 0$).

To summarize: all real roots of the cubic equation (1) satisfy the inequality

$$B \leq |x| \leq A,$$

The numbers $A$ and $B$ are determined through the coefficients of the equation using formulas (10), (5) and (14), (13). In other words, the real roots of the cubic equation (1) can only lie on the segments $[-A, -B]$ and $[B, A]$ of the real axis; outside these segments, equation (1) has no real roots.

Example Consider the equation

$$2x^3 + 5x^2 - 4x - 3 = 0.$$

Here $M = 5$, $|a| = 2$, and then $A = \frac{7}{2}$. Thus, the upper bound of real roots is considered to be $\frac{7}{2}$. Next, $N = 5$, $|d| = 3$, and then $B = \frac{3}{8}$. Therefore, the lower bound of real roots is considered to be $\frac{3}{8}$. In other words, the real roots are considered to lie on the segments $(-7/2, -3/8)$ and $(3/8, 7/2)$.

From the old dictionary

(Continuation Beginning see p. 20)

Let's look at the word electric. We read: “... Matter, the subtlest of all known liquid bodies, communicating with almost all bodies, to a greater or lesser extent, and moving with extraordinary speed.”

To this description we can add that at the beginning of the 19th century it was believed that there were two electric fluids corresponding to two charges - positive and negative. To these liquids were added two more magnetic ones (northern and southern magnetism), a liquid associated with the gravity force, and caloric.

It is interesting that the Dictionary distinguishes between “gravity, the force that induces all things to the bottom or to the center of the Earth,” and “universal gravity, the mutual attraction of all celestial bodies.”

One can understand why with heat and electrical binding the existence of specific liquids. Physicists have noticed that there is something in nature that preserves. The simplest and most understandable law was the law of conservation of matter - in part, liquid. This law was widely used in hydrodynamics. Therefore, specific liquids must also be associated with other stored nutritional debts. The fact that these liquids should be unusually easy to penetrate into all bodies was evident at the first stages of the small smoothie: the bodies seemed simple, and the liquids “thin.”

(For the end see p. 28)
