---
id: 1988-6-gabovich-gornshteyn-resheniya-nestrogih-neravenstv-a5daa9f4
issue: kvant_1988_6
year: 1988
number: "6"
title: Solutions to non-strict inequalities
authors:
  - Габович И. Г.
  - Горнштейн П. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 61
page_last: 62
page_labels: 59-60
tag: GJ84
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7054e81f9d2cc333c017ef3da338d121a184b9366873453a8767012ca7d045ae
prompt_sha256: draft-1
translated_from: content/ru/1988/06/articles/14_gabovich-gornshteyn-resheniya-nestrogih-neravenstv-a5daa9f4.md
source_content_sha256: b08eb8c8d10ab037d97aebbe74ed05f37e85fdb9e92807f70146f3e46fb3c197
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 59⟧

Solutions to non-strict inequalities

I. G. GABOVICH, P. I. GORNSTEIN

This article will discuss the solution to the non-strict inequality $f(x) \geq 0$, or rather, how much this solution differs from the solution to the corresponding non-strict inequality $f(x) > 0$.

From the most point of view, the situation is simple: the solution to inequality $f(x) > 0$ is the union of several finite or infinite intervals*, and in order to obtain a solution to inequality $f(x) \geq 0$, you need to add their ends to these intervals.

In some cases, this rule gives the correct result. For example, this will happen in the case of linear inequalities:

*) Strictly speaking, this is true if $f(x)$ is a continuous function defined on all lines or on some union of intervals.

solving a non-strict inequality
$ax + b > 0$

the set $(-b/a; \infty)$ occurs, and the solution to the non-strict inequality
$ax + b \geq 0$

is the set $[ -b/a; \infty)$, obtained from the previous set by adding the end of the interval $-b/a$. But already in the case of quadratic inequalities our rule becomes flawed. The simplest example: solving the inequality
$-x^2 > 0$

there will be an empty set, and the solution to the inequality
$-x^2 \geq 0$

is not an empty set, as one might think, but a set consisting of one point $x = 0$. Otherwise, this was only the case if the discriminant of the square trinomial on the left side of the inequality is equal to zero; for example, if the quadratic trinomial $ax^2 + bx + c$ has two times

⟦folio 60⟧

The personal roots $x_1$ and $x_2$ ($x_1 < x_2$) and $a > 0$, then solving the inequality
$$ax^2 + bx + c > 0$$
deunification $(-\infty; x_1) \cup (x_2; \infty)$ will occur, and the solution to the inequality
$$ax^2 + bx + c \geq 0$$
— unification $(-\infty; x_1] \cup [x_2; \infty)$.

What's the matter? If at the points of the graph of the function $y = f(x)$ lying on the axis $Ox$, the function $f(x)$ changes sign, that is, its graph passes from one side of the axis $Ox$ to the other, then the “rule” formulated above is correct; for example, for the function $f(x)$, the graph of which is shown in figure 1, the solution to the inequality $f(x) > 0$ is the defusion $(a; b) \cup (c; d)$, and the solution to the inequality $f(x) \geq 0$ is the defusion $[a, b] \cup [c, d]$. For the function whose graph is shown in figure 2, inequality $f(x) > 0$ has a solution $(a, b)$, and inequality $f(x) \geq 0$ has a solution $[a, b] \cup \{c\}$! Another example: the function $y = f(x)$ is defined at $x \geq a$ and has the graph shown in figure 3. Then the inequality $f(x) > 0$ has a solution $(b, c)$, and the inequality $f(x) \geq 0$ has a solution $\{a\} \cup [b, c]$!

If $A$ is the union of intervals, then the set obtained from $A$ by adding the ends of the intervals to the set $A$ is called the closure of the set $A$ and is denoted by $\bar{A}$. The above can be given the following form: if $A$ is a solution to the inequality $f(x) > 0$, and $B$ is a solution to the inequality $f(x) \geq 0$, then $B$ contains $\bar{A}$, but may not coincide with it.

How can one solve the natural inequality $f(x) \geq 0$, knowing the solution strictly to the inequality $f(x) > 0$?

It’s very simple: you need to add all solutions to the equation $f(x) = 0$ to the solution of the strict inequality $f(x) > 0$.

To this very important remark we will add one more very important remark, which may be useful in practice: the solution to the inequality $f(x)g(x) \geq 0$ is the union of solutions to the system of inequalities
$$\begin{cases} f(x) \geq 0, \\ g(x) \geq 0; \end{cases}$$

(Similarly for inequality $f(x)g(x) \leq 0$.) Now let's look at a few examples (some of them are taken from competitive exams of different years).

Example 1. Solve inequality
$$\sqrt{-25x^2+15x-2}(8x^2-6x+1) \geq 0.$$

Let's solve four inequalities:
$$\sqrt{-25x^2+15x-2} \geq 0;$$
solution: $\frac{1}{5} \leq x \leq \frac{2}{5}$.
$$\sqrt{-25x^2+15x-2} \leq 0;$$
solution: $x = \frac{1}{5}$ and $x = \frac{2}{5}$.
$$8x^2-6x+1 \geq 0;$$
solution: $x \leq \frac{1}{4}$ and $x \geq \frac{1}{2}$.
$$8x^2-6x+1 \leq 0;$$
solution: $\frac{1}{4} \leq x \leq \frac{1}{2}$.

Having denoted the four found corresponding sets by $A, B, C, D$, we can say that the solution to the original inequality is the set $(A \cap C) \cup (B \cap D)$. Having performed the above actions, we get

Answer: $$\left[ \frac{1}{5}; \frac{1}{4} \right] \cup \left\{ \frac{2}{5} \right\}.$$

Example 2: Solve inequality
$$\sqrt{x^2-7,5x+14}\log_2|x-3| \leq 0.$$

(For the ending see p. 66)
