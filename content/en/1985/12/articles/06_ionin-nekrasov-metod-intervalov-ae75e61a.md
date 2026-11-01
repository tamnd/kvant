---
id: 1985-12-ionin-nekrasov-metod-intervalov-ae75e61a
issue: kvant_1985_12
year: 1985
number: "12"
title: Interval method
authors:
  - Ионин Ю. И.
  - Некрасов В. Б.
rubric: shkola-v-kvante
page_first: 20
page_last: 22
page_labels: 18-20
tag: EQIA
lang: en
source: kvant_digital
extraction: vision
content_sha256: 73743214acb3adc013c22116ac58f54da87cf42d735384d48d34f1069df80b75
prompt_sha256: draft-1
translated_from: content/ru/1985/12/articles/06_ionin-nekrasov-metod-intervalov-ae75e61a.md
source_content_sha256: 50103adba14612d1343f2695e9a0067ae9f40d591a6d7252c740481d52dda64c
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 18⟧

Math 9-10

Integral method

This article is intended for ninth and tenth graders. It can also be used by applicants when preparing for university entrance exams.

In the school algebra course, a significant place is devoted to inequalities: first, these are linear inequalities, then quadratic, then inequalities in which logarithmic, exponential and trigonometric functions are involved. Gradually, inequalities are created—all sorts of combinations of functions studied in school appear. In this article, we will use several examples to illustrate one important method for solving inequalities, which is usually called the “method of integrals.” We will consider here inequalities, the right part of which is equal to zero, and the left part is presented in the form of a product or partial of functions with known intervals of constant sign. The method of integrals is based on the following idea: the sign of the product (partial) is determined by the signs of the factors (delim and divisor).

Problem 1. Solve inequality

$$\frac{(2x-1)(x^2-x-2)}{3-x} < 0.$$

A linear function with a non-zero slope changes sign when passing through the root, and to the right of the root the sign of the function coincides with the sign of the slope (Fig. 1); a square trinomial with a positive discriminant also changes sign when passing each root, and to the right of the root, the sign of the square trinomial coincides with the sign of its leading coefficient (Fig. 2).

These messages lead to the following scheme for solving the inequality.

1. We find the roots of each “component”: $x=\frac{1}{2}; x=-1, x=2; x=3$.

2. The number axis is divided into five intervals. On the rightmost of each of them, the factor coincides with the sign of its leading coefficient: $2x-1>0, x^2-x-2>0, 3-x<0$.

Therefore, the fraction on this interval is negative.

3. When passing through each of the marked roots, one and only one of the factors changes sign, and therefore the sign of the fraction changes each time. Taking this into account, we place signs in these intervals (as shown in figure 3).

4. We select intervals where the fraction is negative.

Answer:

$$]-\infty; -1[\cup]\frac{1}{2}; 2[\cup]3; +\infty.$$

Problem 2. Solve inequality

$$\frac{4-x^2}{(5x-2)\lg x} \ge 0.$$

We will solve this inequality using the same scheme, but not on all axes, but on the interval $]0; +\infty[$ - the region of op-

⟦folio 19⟧

limit of a logarithmic function.

1. Roots "factor": $x=2; x=0,4; x=1$ (Fig. 4).

2. The semi-axis $]0; +\infty[$ was divided into four intervals. On the rightmost one is $4-x^2<0, 5x-2>0, lgx>0$. Consequently, the part of the inequality lying on this interval is negative.

3. When passing through each root, one and only one of the factors changes sign. Taking this into account, we place signs on the remaining intervals (Fig. 4).

4. We have solved the strict inequality. It remains to add to the resulting set of solutions the roots of the equation

$$\frac{4-x^2}{(5x-2)lgx}=0,$$

that is, the roots of the numerator of the fraction (included in the domain of definition of the inequality).

Answer: $]0; 0,4[\cup]1; 2]$.

Problem 3. Solve inequality

$$\frac{(10^x-2)(x^2-5x+7)}{x+3} \leq 0.$$

The solution is depicted on figure 5. The square triple in the numerator of the fraction has no roots and therefore does not change the sign, which coincides with the sign of its leading coefficient.

Answer: $]-3; lg2]$.

Problem 4. Solve inequality

$$(x^2-2x-3)(6+x-x^2) \geq 0.$$

1. Find the roots of the factors: $x=-1, x=3, x=-2, x=3$.

2. For $x>3$ the left-hand side of the inequality is negative.

3. When passing through the point $x=3$, both factors change sign ($x=3$ is their common root), so the sign of the product does not change.

When passing through each of the other two roots, the left side, as in previous examples, changes sign (Fig. 6).

Answer: $[-2; -1]\cup\{3\}$.

From this problem it is clear that, using the method of integrals, it is necessary to monitor how many factors change sign when passing through a given root. Factors are possible that do not change sign when passing through their root (for example, a square trilen with a discriminant equal to zero).

The idea of ​​solving the following is based on an intuitively clear theorem, the exact proof of which is given in courses on mathematical analysis: if a function is continuous on an interval and has no roots in this interval, then it preserves its sign in this interval.

⟦folio 20⟧

Task 7. Solve inequality
$$\sqrt{x+2} > x.$$ (1)

The function $y = \sqrt{x+2} - x$ is defined and continuous on the interval $[-2; +\infty]$.

Let's find the roots of this function, that is, solve the equation
$$\sqrt{x+2} = x.$$ (2)

By squaring both sides of equation (2), we arrive at the quadratic equation $x^2 - x - 2 = 0$ with roots $x = -1$, $x = 2$. Check shows that the root of equation (2) is only $x = 2$. This point divides the domain of definition of inequality (1) into two intervals: $[-2; 2[$ and $]2; +\infty[$. On each of these intervals, the function $y = \sqrt{x+2} - x$ retains its sign, that is, either all points of such an interval satisfy inequality (1), or none of them does. Therefore, it is enough to substitute one point from each interval into inequality (1). Let's select points $x = -2$ and $x = 7$. Since $x = -2$ satisfies inequality (1), but $x = 7$ does not, the set of solutions to inequality (1) is the interval $[-2; 2[$ (Fig. 9).

Answer: $[-2; 2]$.

Problem 8. Solve inequality
$$x\sqrt{10-x^2} \geq x^2 - 6.$$

1. The domains of the function $\sqrt{10-x^2}$: $[-\sqrt{10}; \sqrt{10}]$.

2. We solve the equation:
$$x\sqrt{10-x^2} = x^2 - 6,
x^2(10-x^2) = (x^2 - 6)^2;
x^4 - 11x^2 + 18 = 0.$$

We get four roots: $x = \pm \sqrt{2}, x = \pm 3$. The check leaves two roots: $x = -\sqrt{2}, x = 3$ (Fig. 10).

3. We substitute the numbers $x = -\sqrt{10}, x = 0, x = \sqrt{10}$ into the inequality. The number $x = 0$ satisfies the inequality, but the numbers $x = \pm \sqrt{10}$ do not.

Answer: $[-\sqrt{2}; 3]$.

As is known, linear, quadratic, power, exponential, logarithmic and trigonometric functions, as well as their compositions and functions obtained from them using arithmetic operations, are incorrect in their domain of definition. Therefore, the method of integrals can be used to solve practically all inequalities in the school course. The method of integrals allows you to represent the set of solutions to an inequality as a union of intervals, the boundaries of which are either the roots of the corresponding equation or the boundary points of the domain where the inequality is defined.

The requirement of continuity is essential for the application of the integral method. You can verify this in the next problem.

Task 9. Solve inequality
$$[x] \leq x - \frac{1}{2}.$$

Let's construct graphs of the left and right sides of the inequality (Fig. 11). The roots of the equation $[x] = x - \frac{1}{2}$ are numbers of the form $k + \frac{1}{2}$, where $k$ is any integer. At the same time, the set of solutions to the inequality is a union of intervals of the form $[k + \frac{1}{2}; k + 1]$, the boundary points of which are, in particular, all integers that are neither roots of the equation nor boundary points of the domain of definition.

Yu. I. Ionin, V. V. Nekrasov
