---
id: 1977-4-boltyanskiy-metod-otdelyayuschih-konstant-776cfc1b
issue: kvant_1977_4
year: 1977
number: "4"
title: Method of separating constants
authors:
  - Болтянский В. Г.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 48
page_last: 51
page_labels: 46, 47, 49
tag: 678B
lang: en
source: kvant_digital
extraction: vision
content_sha256: 882948b9530e633974bd428c2cfb792ae123a02918144b459f1571d5e419a6db
prompt_sha256: draft-1
translated_from: content/ru/1977/04/articles/18_boltyanskiy-metod-otdelyayuschih-konstant-776cfc1b.md
source_content_sha256: fbce771986a5556946ca65fe6ed010ecf565da35df73c074b5eed5edc28623a5
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 46⟧

In most cases, the practice of written examinations for university applicants includes problems whose solution is convenient starting with finding the set of values ​​​​accepted by certain functions. There is no other solution to the problem and the answer immediately follows from the results obtained; in other cases, the value of a set of function values ​​dramatically reduces the amount of work, indicating the shortest path to the answer.

Some features of the application of this method are discussed in this article.

Proof of inequality
Let's start with the next task.

Example 1. Prove an inequality
$$x^2 - 2x \geq -3 + \sin x.$$ (1)

To solve it, it is enough to note that the ray [−1;∞], which is a set of function values
$$f(x) = x^2 - 2x = (x - 1)^2 - 1,
$$ does not intersect with the set of function values
$$g(x) = -3 + \sin x,
$$ that is, with the segment [−4; −2].

We can say it another way: sucestium is any number c (for example, c = −3/2), that for all x ∈ R $$f(x) > c, c > g(x)$$ (Fig. 1) is true, which opens all only inequalities (1), but also a stronger one: $$f(x) > g(y)$$ for any x, y ∈ R, that is, always
$$x^2 - 2x > -3 + \sin y.$$

In more complex examples, it is no longer possible to find the constant c that “separates” the values ​​of the function f(x) from the values ​​of the function g(x) over the entire domain of their specification, but the number line can be divided into several intervals, each of which has its own separating constant.

Example 2. Prove inequality
$$\arctg x > 4\sqrt{3}x - x^2 - 11.$$ (2)

In this case, on the ray ] −∞; √3[ (that is, for −∞ < x < √3) such a separating constant is c₁ = −2 (Fig. 2), and on the ray [√3;∞] we can take the separating constant c₂ = 1.01.

Of course, the graph at figure 2 only illustrates what has been said; the complete proof, based on the idea of ​​separating constants, can be stated, for example, as follows. Function
$$f(x) = \arctg x$$
for all x ∈ R (and, in particular, for x < √3) satisfies the inequality
$$f(x) > -\frac{\pi}{2} > -2,$$ that is, f(x) > c₁.
On the other hand, the function g(x) = 4√3x - x² - 11 =
$$= -(x - 2\sqrt{3})^2 + 1$$
at x = √3 takes the value

⟦folio 47⟧

$$g(\sqrt{3}) = -2 = c_1,$$
and following the point $x = \sqrt{3}$ this function increases, therefore $g(x) < c_1$ at $x < \sqrt{3}$. So, $f(x) > c_1 > g(x)$ for $x < \sqrt{3}$, that is, for these values ​​of $x$ inequality (2) is valid. It remains to consider the values ​​of $x \geqslant \sqrt{3}$.

Note that $f(\sqrt{3}) = \arctg \sqrt{3} = \pi/3 > 1,01$, and the function $f(x)$ is increasing, therefore $f(x) > c_2$ for $x \geqslant \sqrt{3}$. As for the function $g(x)$, then for any $x \in \mathbb{R}$ (and, in particular, for $x \geqslant \sqrt{3}$) we have $g(x) \leqslant 1 < c_2$.

Thus, $f(x) > c_2 > g(x)$ for $x \geqslant \sqrt{3}$, that is, for these values ​​of $x$, inequality (2) is valid.

The considered method of proving inequalities in everything should be considered somehow elegant, random, rarely used. For example, for continuous functions this technique can be considered universal. In fact, let, for example, continuous functions $f(x)$ and $g(x)$ be given on the interval $[a; b]$, and having estimated the form of these graphs, we discover that the inequality $f(x) > g(x)$ seems to be valid on this entire interval. How could one prove this inequality to be true?

If the inequality $f(x) > g(x)$ is true for all $x \in [a; b]$, then the graphs of the function $f(x)$ and $g(x)$ do not have common points, and therefore it is possible* to draw a “step broken line” (Fig. 3), separating the graph of the function $y = f(x)$ from the graph of the function $y = g(x)$. But this means that the segment $[a; b]$ can be divided into several smaller segments, on each of which there is a separate constant $c_i$.

Of course, in this reasoning the decision is only about the fundamental emergence of the proof of the inequalities $f(x) > g(x)$ by the method of a separate constant. In each specific case, the art of using this technique is to find suitable divisions of the segment $[a; b]$ into parts and for each of these parts indicate the constant corresponding to the part.

**Iterations**

In the general case, it is difficult to give recommendations on how to select the partitioning and the corresponding individual constants. However, in some cases recommendations can be offered.

Let, for example, both functions $f(x)$, $g(x)$ be increasing (or non-decreasing), and $f(a) > g(a)$. Let's draw a straight line $y = f(a)$ (Fig. 4) and consider the point of its intersection with the graph of the function $y = g(x)$. The abscissa of this point is denoted by $x_1$. On the segment $[a; x_1]$ we can take the number $c_1 = f(a)$ as a separate constant. Indeed, on this entire segment the inequalities $f(x) \geqslant c_1$, $g(x) \leqslant c_1$ are satisfied, and the first inequality turns into equality only at the left end of the segment $[a; x_1]$, and the second only at the right. From here

*) In fact, this word “can” hides a whole complex mathematical theorem, which we, of course, will not prove here.

⟦folio 49⟧

Solving the equation

The method of separating constants can be used not only to prove a deficiency, but also, in some cases, to solve an equation, and not an approximate, but an exact solution.

Example 4. Solution of equation $x^2 - 2x\sin x - 2\cos x + 2 = 0$. (4) Let us write the equation in the form

$$(x - \sin x)^2 = -(1 - \cos x)^2,$$

that is, in the form $f(x) = g(x)$, where

$$f(x) = (x - \sin x)^2,$$

$$g(x) = -(1 - \cos x)^2.$$

Obviously, for any $x \in \mathbb{R}$ the inequalities $f(x) \geq 0$, $g(x) \leq 0$ are valid. From here it is clear that a certain number $x_0$ can only satisfy the equality $f(x_0) = g(x_0)$, that is, be a root of equation (4), if the equality $f(x_0) = 0$, $g(x_0) = 0$ is satisfied, that is, if $x_0$ is a solution to the system

$$\begin{cases} x - \sin x = 0, \\ 1 - \cos x = 0. \end{cases}$$

The second equation of this system has roots $x = 2k\pi (k = 0, \pm 1, \pm 2, \ldots)$, of which only the root $x = 0$ satisfies the first equation. Thus, the original equation has a single root $x = 0$.

Example 5. Solving the equation

$$x^3 - 2x^2 + x + 1 = \sqrt{\sin \frac{\pi x}{2}}.$$ (5)

This equation can be written as $f(x) = g(x)$, where

$$f(x) = x^2 - 2x^2 + x + 1,$$

$$g(x) = \sqrt{\sin \frac{\pi x}{2}}.$$

Since $f(x) = 1 + x(x - 1)^2$, then $f(x) \geq 1$ for all $x \geq 0$. At the same time, $g(x) \leq 1$ for all $x$ belonging to the domain of definition of the functions $g(x)$. Therefore, on the ray $x \geq 0$ the number $c = 1$ is a separating constant for the function $f(x)$ and $g(x)$. It follows that the non-negative number $x_1 = 1$, $x_2 = 0$, of which only $x_1$ satisfies the second equation. So, equation (5) has only one non-negative root $x_1 = 1$.

Now let's see if there are any negative roots. Since at $-2 < x < 0$ the function $g(x)$ is not defined, then negative roots must be sought only on the ray $x \leq -2$. But for $x \leq -2$ we have $f(x) = 1 + x(x - 1)^2 \leq 1 - 2 \cdot 3^2 = -17$, and $g(x) \geq 0$ by the definition of the function $\sqrt{x}$. Thus, the separator for $f(x)$ and $g(x)$ on the ray $x \leq -2$ (at those points $x$ at which the function $g(x)$ is defined) is, for example, the number $c = -10$. Consequently, the equation of non-negative roots is considered, that is, $x_1 = 1$ is the only root of equation (5).

Let us note in conclusion that, despite its universality, the method of separating CONSTANT is not always the most convenient means for proving a particular inequality. For example, to prove the inequality $tg x > 4x - 2,5$ on the interval $[0; \pi/2]$ (see Example 3), one could use the fact that an arbitrary function $\varphi(x) = tg x - 4x + 2,5$ equal to $\frac{1}{\cos^2 x} - 4$ vanishes only at one point in this interval, namely at $x = \pi/3$. At this point the value of the function $\varphi(x)$ is positive:

$$\varphi(\pi/3) = tg \frac{\pi}{3} - 4 \cdot \frac{\pi}{3} + 2,5 \approx 0,04.$$

At the end of the integral, the function $\varphi(x)$ takes on large values: $\varphi(0) = 2,5$ and $\varphi(x) \to \infty$, if $x \to \pi/2$ (but $x < \pi/2$). From here you can
