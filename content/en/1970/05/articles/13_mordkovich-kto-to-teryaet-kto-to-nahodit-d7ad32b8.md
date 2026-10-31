---
id: 1970-5-mordkovich-kto-to-teryaet-kto-to-nahodit-d7ad32b8
issue: kvant_1970_5
year: 1970
number: "5"
title: Some people lose, some people find
authors:
  - Мордкович А. Г.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 50
page_last: 53
page_labels: 48-51
tag: B39Q
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0c26d60e48165101c0310bc9f5e6dad7118528f93a25e4c7fc6c45ddc28de16a
prompt_sha256: draft-1
translated_from: content/ru/1970/05/articles/13_mordkovich-kto-to-teryaet-kto-to-nahodit-d7ad32b8.md
source_content_sha256: 96ab34872b6a93e1a5a38e4f6e28a49c3c150a45358367e4dcbbf4faae62e823
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 48⟧

How we solve the equation! Based on this equation, we write in a row one, another, third, ... - a chain of equations in which each is obtained from the previous transformation of one or both parts at once, and so on until we get a completely simple equation, the solutions of which we already know how to find. If, in this case, all transitions from this equation to the next are “reversible”, that is, we see that the transformation of the fourth equation can be obtained by the third, from the third - the second, etc., then it is clear that the last process of the equation has the same roots as the original one. But we often encounter such equations with radicals, logarithms, and trigonometric functions, the solution of which involves resorting to rather complex transformations, so that the “reverse transition” is not very clear. If, when solving such equations, you make transformations formulaically, without delving into their meaning, then it is easy to make a mistake: lose a root or add an extra one. This article explains how this happens and how to avoid such troubles.

1. SOME NOTATIONS.

Let the data be number sets $X$ and $Y$. The notation $X \subset Y$ means that each element of the set $X$ is at the same time an element of the set $Y$, and in $Y$ there may be elements that do not belong to the set $X$. The notation $x \in X$ (respectively $x \in X$) means that the element $x$ belongs (does not belong) to the set $X$.

The conditions below together with the phrase “the set $X$ consists of all real numbers $x$” also use the notation: $X = \{x| -\infty < x < \infty\}$. Similarly, the notation $X = \{x|x \ge 3\}$ means that the set $X$ consists of all those numbers $x$ that satisfy the inequality $x \ge 3$, and the notation $X = \{x|x \neq \pi\}$ means that the set $X$ contains all real numbers except $x = \pi n^*$).

And, finally, the conditions for the range of permissible values ​​of the VA (recall that the range

*) Throughout what follows it is assumed that $n, k=0, \pm 1, \pm 2, \ldots$

⟦folio 49⟧

The admissible values ​​of the equation $f(x)=g(x)$ are the set of those $x$ for which the function $f(x)$ and $g(x)$ are defined) the given equation is denoted by the letter $X$, and the OD of the equation obtained from the original one as a result of some transformation is denoted by the letter $Y$.

2. WHERE DO THIRD-PARTY ROOTS COME FROM?

The first reason is the expansion of ODZ. When solving an equation, a variety of transformations are constantly applied. Quite often, it happens that the OD of the equation obtained from the original one as a result of some transformation turns out to be wider than the OD of the original equation (the phrase “wider OD” means $X \subset Y$). Expansion of the ODZ can lead to the appearance of permanent roots. The point is that the resulting equation may have roots that, being elements of the set $Y$, do not belong to the set $X$. They will be constant for the original equation.

Example 1: Solve the equation
$$\frac{2}{2-x} + \frac{1}{2} = \frac{4}{2x-x^2}.$$
Solution. Let us first write down the ODZ of equation (1): $X=\{x|x \neq 0;2\}$. Reducing to a common denominator, we get
$$4x+2x-x^2=8.$$

Equation (2) already has another ODZ: $Y=\{x|-\infty < x < \infty\}$. Solving equation (2), we obtain two roots: $x_1=4$, $x_2=2$, with $x_1 \in X$, while $x_2 \in X$, and therefore $x_2$ is a constant root for equation (1). Thus, equation (1) has a single root $x=4$.

Example 2: Solve the equation
$$\lg (x^2+3x-4) = \lg (2x+2).$$
Solution. Having solved the system of inequalities
$$\begin{cases} x^2+3x-4 > 0, \\ 2x+2 > 0, \end{cases}$$
we find the ODZ of equation (3): $X=\{x|x > 1\}$. By potentiating, we transform equation (3) into the equation
$$x^2+3x-4=2x+2$$
with wider ODZ: $Y=\{x|-\infty < x < \infty\}$. Equation (4) has two roots: $x_1=2$, $x_2=-3$, with $x_1 \in X$ and $x_2 \in X$. This means that $x_2$ is a constant root for equation (3) and, therefore, equation (3) has a single root $x=2$.

The expansion of ODZ sometimes results from the use of certain formulas known from the secondary school course. These are formulas related to various properties of logarithms, radicals of even degree, as well as certain

$$\log_a f(x) + \log_a g(x) = \log_a [f(x) \cdot g(x)],$$
$$\frac{1-\cos x}{\sin x} = \tg \frac{x}{2}.$$

It is easy to see that a function containing these equalities on the right-hand sides has a wider domain of definition than a function containing on the left-hand sides.

Thus, the domain of definition of the function $\log_a f(x)+\log_a g(x)$ is determined by the system of inequalities
$$\begin{cases} f(x) > 0, \\ g(x) > 0, \end{cases}$$
whereas the domain of definition of the function $\log_a [f(x) \cdot g(x)]$ consists of solutions to system (7) and solutions to another system of inequalities
$$\begin{cases} f(x) < 0, \\ g(x) < 0. \end{cases}$$

The domain of definition of the function $\frac{1-\cos x}{\sin x}$ is: $X=\{x|x \neq \pi n\}$. The function $tg \frac{x}{2}$ has a wider scope of definition: $X=\{x|x \neq \pi(2k+1)\}$. Therefore, when solving an equation, using formulas (5), (6) and the like “from left to right” can lead to the appearance of constant roots.

Example 3: Solve the equation
$$\frac{1-\cos x}{\sin x} + \tg^3 \frac{x}{2} = 0.$$

Solution. Let us write down the ODZ of equation (8): $X=\{x|x \neq \pi n\}$. Applying formula (6), we obtain the equation
$$tg \frac{x}{2} + \tg^3 \frac{x}{2} = 0$$

with wider ODZ: $Y=\{x|x \neq \pi(2k+1)\}$. The solutions to equation (9) are the values ​​of $x=2\pi n$. All these values ​​are not included in the ODZ of equation (8), and therefore are constant roots. Thus, equation (8) has no solutions.

The second reason is the reduction of both sides of the equation to the same function. Let me give the equation
$$f(x)=g(x).$$
Let's multiply both sides by the function $h(x)$. Let's learn the equation
$$f(x)\cdot h(x)=g(x)\cdot h(x),$$
the roots of which are both the roots of equation (10) and the roots of the equation $h(x)=0$ (or, as they also say, the roots of the function $h(x)$. The averages of these latter may also be roots that do not satisfy the equation

⟦folio 50⟧

(10), that is, it is a construction for it (by the way, in example 1, both sides of equation (1) were multiplied by the same function $2x(2-x)$. As a result, the constructed root $x=2$ appeared, but we owe its appearance to expanding the ODZ).

Example 4: Solve the equation

$$x = (\sqrt{1+x} + 1)(\sqrt{10+x} - 4).$$

Solution. Let us write down the ODZ of equation (12): $X = \{x|x \geq -1\}$. Let's multiply both sides of the equation by the function $h(x) = \sqrt{1+x} - 1$. After the transformation, we obtain the equation $x(\sqrt{1+x} - \sqrt{10+x} + 3) = 0$, which has 2 roots: $x_1 = 0$, $x_2 = -1$ (note that the extended ODZ will not occur). Both roots belong to the set $X$, however, verification convinces us that $x_1 = 0$ is a constructed root (it is easy to see that $x = 0$ is the root of the function $h(x)$). Thus, equation (12) has a single root $x = -1$.

The third reason is the construction of both sides of the equation in the central one. Consider equation (10). Let's square both sides of this equation. We obtain the equation $[f(x)]^2 = [g(x)]^2$, the roots of which are both the roots of equation (10) and the roots of the “extraneous” equation $f(x) = -g(x)$. The averages of these latter may also turn out to be roots that do not satisfy the original equation (10). They will be constructed for equation (10).

Example 5: Solve the equation

$$\sqrt{2x+5} + \sqrt{x-1} = 8.$$

Solution. Let us write the ODZ of equation (13): $X = \{x|x \geq 1\}$. Let's square both sides of the equation. After transformation we get

$$2\sqrt{2x^2 + 3x} - 5 = 60 - 3x$$

and onwards

$$4(2x^2 + 3x - 5) = (60 - 3x)^2,$$

whence $x_1 = 10$, $x_2 = 362$. Consequently, the solutions found, we replace that only $x_1 = 10$ satisfies equation (13), while $x_2 = 362$ is the constructed root (although it belongs to the ODZ of equation (10). The extraneous root appeared as a result of squaring both sides of equation (14).

3. WHAT CAUSES ROOTS LOSS?

The first reason is the narrowing of the ODZ. There are also transformations that lead to an equation with a narrower OD. Narrowing the ODZ can lead to the loss of roots, namely, those roots of the original equation that belonged to the set $X$, but do not belong to the “narrower” set $Y$, $(Y \subset X)$, can “lose”.

Example 6: Solve the equation

$$\text{tg} \left( x + \frac{\pi}{4} \right) = 2 \text{ctg} x - 1.$$

Solution. Let us transform equation (12) to the form

$$\frac{\text{tg} x + \text{tg} \frac{\pi}{4}}{1 - \text{tg} x \cdot \text{tg} \frac{\pi}{4}} = \frac{2}{\text{tg} x} - 1.$$

Putting $y = \text{tg} x$, we arrive at an algebraic equation for $y$, solving which we obtain $y = \frac{1}{2}$, that is, $x = \text{arctg} \frac{1}{2} + \pi k$.

But verification convinces us that the values ​​of $x = \frac{\pi}{2} + \pi n$ also satisfy equation (15). When did we lose these roots? Let us compare the ODZ of equations (14) and (15). X consists of all values ​​of $x$ except those for which $ctg x$ and $\text{tg} \left( x + \frac{\pi}{4} \right)$ do not exist. Means,

$$X = \left\{ x \mid x \neq \pi n, x \neq \frac{\pi}{4} + \pi n \right\}.$$

The ODZ of equation (16) - $Y$ - consists of all values ​​of $x$, except for those for which $ctg x = 0$, $\text{tg} x = 1$ and $\text{tg} x$ do not exist. Means,

$$Y = \left\{ x \mid x \neq \pi n, x \neq \frac{\pi}{4} + \pi n \right\}.$$

It follows that $Y \subset X$, that is, the ODZ of equation (16) is narrower than the ODZ of equation (15). The values ​​$x = \frac{\pi}{2} + \pi n$ belong to the set $X$, but do not belong to the set of roots of the original equation.

Now, one important question arises: what led to the narrowing of DL? Analysis of the solution to Example 6 shows that the use of tangent sum formulas led to narrowing the OD; in our example, the formula belonged to the set $X$, but did not belong to the “narrower” set $Y$, $(Y \subset X)$.

The second reason is dividing both sides of the equation by the same function. Let $x_1$ be the root of equation (11), but it does not necessarily satisfy equation (10). Thus,

⟦folio 51⟧

At the same time, dividing both sides of the equation by the same function can lead to the loss of roots (namely, the roots of the divisor functions).

INSTEAD OF CONCLUSION

What general rule guides you when solving an equation? Only one way: to solve any equation consciously, not mechanically, not to bypass any critical transition where the appearance of constructed roots or the loss of roots is possible. Before starting to solve the equation, it is useful to write down all the constraints that define OD3 (they do not even have to be resolved relative to the unknown); for example, when solving equation (3), it was enough to write down the conditions: $x^2 + 3x - 4 > 0$ and $2x + 2 > 0$; When checking, it is immediately clear that one of the found roots $x_2 = -3$ does not satisfy the condition $2x + 2 > 0$. If you have to make transitions during which constructed roots may appear, then at the end you need to do a check, which in this case is part of the solution to the problem, and not just an additional control. Sometimes, during the solution process, it is convenient to split the set of values ​​of a variable into two or more parts and examine the equation separately on each of them; for example, equation (14) at $60 - 3x < 0$ is complete and has no solutions, and at $60 - 3x \ge 0$ squaring both sides will not lead to the appearance of new roots, since both sides of the equation are non-negative (the extraneous root $x_2 = 362$ is automatically eliminated as not satisfying the condition $60 - 3x \ge 0$).

The solution to each equation should look like a proof of the theorem that a given equation is satisfied by those and only those numbers that are written in the answer; as well as the “struggle” with built roots and with the loss of roots during transformation must be flexible.

Exercises

Solve the following equations:

1. $\frac{x}{2x-1} + \frac{25}{4x^2-1} = \frac{1}{27} - \frac{13}{1-2x}$.
2. $\frac{x^2 - 3x + 2}{x} \left( \frac{x}{3^2 - 1} - 1 \right) = 0$.
3. $\sqrt{x+1} = 1 - \sqrt{2x+3}$.
4. $\sqrt{(x+16)(x-5)} + \sqrt{x^2 - 5x} + \sqrt{x^2 - 5x} + x = 40$.
5. $\log_{5x-2} 2 + 2 \log_{5x-2} x = \log_{5x-2} (x+1)$.
6. $\frac{\lg 2 + \lg (4 - 5x - 6x^2)}{\lg \sqrt{2x-1}} = 3$.
7. $tg x + tg 2x = tg 3x$.
8. $3 tg 2x + 2 ctg x + 3 = 0$.
