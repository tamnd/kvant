---
id: 1978-2-zazelo-mnozhestva-znacheniy-chislovyih-funktsiy-7f039538
issue: kvant_1978_2
year: 1978
number: "2"
title: Sets of values ​​of numerical functions
authors:
  - Зазело А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 51
page_last: 52
page_labels: 49-50
tag: A2VQ
lang: en
source: kvant_digital
extraction: vision
content_sha256: fb921a7e937633a1bed78d8085efc285211966e8af235368c89e0b6f6ea2fffb
prompt_sha256: draft-1
translated_from: content/ru/1978/02/articles/19_zazelo-mnozhestva-znacheniy-chislovyih-funktsiy-7f039538.md
source_content_sha256: ac676888f2cf4174fffd1bc61f4de9c89379201237d4b00a340a487223b65a6d
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 49⟧

Sets of values ​​of numerical functions

Recall that the set of values ​​$E(f)$ of a numerical function $f$ is called the set of all $a \in \mathbb{R}$ for which there exists at least one $x \in D(f)$ such that $f(x) = a$. We can say it differently: $E(f)$ consists of those $a$ for which the equation $f(x) = a$ has at least one solution. In simple cases, this equation can be examined and thereby found $E(f)$.

Example 1. Find the set of function values

$$f(x) = \frac{2x}{1+x^2}.$$

The equation $f(x) = a$ is rewritten as $ax^2 - 2x + a = 0$; for $a = 0$ it is satisfied by $x = 0$, and in the case of $a \neq 0$ we have a quadratic equation that has a solution only for those $a$ for which its discriminant is non-negative: $D = 4 - 4a^2 \geq 0$, i.e. $a^2 \leq 1$, or $a \in [-1; 1]$ (and $a \neq 0$). So the equation $f(x) = a$ has a solution if and only if $a \in [-1; 1]$, so $E(f) = [-1; 1]$. Note that at the same time we found the smallest and largest values ​​of the function $f$ - $\min f = -1$, $\max f = 1$.

Task 1-3. Find the set of values ​​of the specified functions, as well as their smallest and smallest values ​​(in cases where they exist).

1. a) $\frac{2x}{1+x}$; 6) $\frac{1}{1+x^2}$; 8) $\frac{1}{1-x^2}$.
2. a) $\pi^x - 3$; 6) $\log_2 x + \log_x 2$;
b) $tg x + ctg x$.
3. a) $\cos^2 x + \cos 2x$; 6) $\sin x \cdot \cos x$;
b) $\sin^4 x + \cos^4 x$.

In some cases, noting the set of values ​​of a given function is

moves towards the study of a quadratic function on a particular interval. To avoid mistakes, it is useful to draw a graph of this quadratic function.

Example 2. Find the set of function values

$$f(x) = 2\cos x + \cos 2x.$$

Let us rewrite $f(x)$ in the form $f(x) = 2\cos x + 2\cos^2 x - 1 = 2z^2 + 2z - 1$, where $z$ denotes the function $\cos x$. Since $z \in [-1; 1]$, it remains to find out what is the set of values ​​of the quadratic function $g(z) = 2z^2 + 2z - 1$ on the interval $[-1; 1]$. The graph of the function $g(z)$ is a parabola with its vertex at the point with the abscissa $z_0 = -1/2$ (explain), with its branches pointing upward. We have: $g(z_0) = -3/2$, $g(-1) = -1$, $g(1) = 3$. If we plot a graph of a quadratic trinomial, then it is clear that the set of values ​​$g$ on the segment $[-1; 1]$ (or the set of those $a$ for which the equation $g(z) = a$ has at least one root $z \in [-1; 1]$) is the segment $[-3/2; 3]$. Consequently, the set of values ​​of the function $f(x) = 2\cos x + \cos 2x$ is the segment $[-3/2; 3]$. Back we found $\min f = -3/2$ and $\max f = 3$.

Task 4-5. By examining the approximations of quadratic functions on the corresponding intervals, we will find the set of values ​​of the following functions, as well as their smallest and smallest values.

4. a) $6\cos x + \cos 2x$; 6) $\sin x + \cos 2x$.
5. a) $4x - 2x^2 + 3$; 6) $4\sin x - 2\sin x + 2$.

In the absence of many values ​​of a function of the form

$$f(x) = A\cos x + B\sin x$$

you can express cos $x$ and sin $x$ in terms of $t = tg(x/2)$ (see “Algebra and Elements” 10”, paragraph 91) and then examine the resulting equation (with respect to $t$ it will be quadratic).

However, it is done faster and easier this way:

$$A\cos x + B\sin x = \sqrt{A^2 + B^2} \times \left( \frac{A}{\sqrt{A^2 + B^2}} \cos x + \frac{B}{\sqrt{A^2 + B^2}} \sin x \right);$$

because

$$\left( \frac{A}{\sqrt{A^2 + B^2}} \right)^2 + \left( \frac{B}{\sqrt{A^2 + B^2}} \right)^2 = 1,$$

⟦folio 50⟧

there is a value $\alpha$ such that
$$\cos \alpha = \frac{A}{\sqrt{A^2 + B^2}}, \sin \alpha = \frac{B}{\sqrt{A^2 + B^2}}$$
(explain) and therefore
$$A \cos x + B \sin x = \sqrt{A^2 + B^2} \left( \cos x \cos \alpha + \sin x \sin \alpha \right) = \sqrt{A^2 + B^2} \cos (x - \alpha)$$.

Therefore, the set of values ​​of the function $f(x) = A \cos x + B \sin x$ is the segment $[-\sqrt{A^2 + B^2}, \sqrt{A^2 + B^2}]$, and the same applies to a function of the form $A \cos \omega x + B \sin \omega x$, where $\omega \neq 0$.

Task 6. Specify the set of values ​​for the following functions:

a) $\cos x - \sin x + 1; 6)$ $3 \cos \frac{x}{2} + 4 \sin \frac{x}{2};$
b) $\cos^2 x - \sin x \cos x$.

In fact, in all the analyzed examples and given problems, solutions to equation $f(x) = a$ can be written out explicitly, i.e. equation $f(x) = a$ with parameter $a$ is “solved” (reduced to linear, quadratic or simple exponential, logarithmic and trigonometric equations). Thanks to this, the smallest and largest values ​​of the functions under consideration are found without using an arbitrary function (moreover, research using an arbitrary function here would often be more cumbersome than algebraic research). In the case when the equation $f(x) = a$ is not submitted to a non-presidential solution (“not solved”), it is reasonable to take the opposite route, which we will now describe.

Example 3. (This problem is taken from “Approximate options for entrance exams in mathematics at universities in 1977”, «Kvant», 1977, No. 6, p. 89). Let's find the set of function values

$$f(x) = \sin x \cdot \cos 2x$$

Denoting $\sin x = z$, we can write: $f(x) = g(z) = z (1 - 2z^2) = z - 2z^3$. As in example 2, the problem of the property is to find the set of values ​​of the function $g$ on the segment $[-1; 1]$. Note that the equation is $g(z) = a - кубическое$, and we cannot solve it. Let us find the smallest and largest values ​​of the function $g$ on the segment $[-1; 1]$. Acting according to the general scheme for studying a function on a segment (see “Algebra and Basic Analysis 9”, paragraph 59), we find the critical points of the function: $g'(z) = 1 - 6z^2 = 0$ at $z^2 = 1/6$, i.e. $z = \pm \sqrt{1/6}$; both critical points belong to the segment $[-1; 1]$, and the values ​​of the function in them are as follows:

$$g(\sqrt{1/6}) = \sqrt{6}/9, g(-\sqrt{1/6}) = -\sqrt{6}/9.$$

Comparing these values ​​with the values ​​at the ends of the segment - with $g(-1) = 1$ and $g(1) = 1$ - we get: $\min(z - 2z^3) = -1, \max(z - 2z^3) = 1.$

Since the function $g$ is always non-discontinuous, it will naturally conclude that $g$ takes any value between the smallest and the largest, i.e. $E(g) = E(f) = [-1; 1]$. To prove this, we will use an important theorem about the set of values ​​of a continuous monotonic function:

if the function $F$ is not discontinuous and increases (or decreases) on the interval $[a; b]$, then the set of values ​​taken by the function $F$ on this interval is also an interval: $[F(a); F(b)]$ (or $[F(b); F(a)]$ if $F$ is decreasing).

This theorem in a more general and complete formulation is given in paragraph 84 of the textbook “Algebra and Beginning Analysis 10” (without proof). Returning to our function, we find that $g$ increases on the segment $[-\sqrt{1/6}; \sqrt{1/6}]$ and decreases on the segments $[-1; -\sqrt{1/6}], [\sqrt{1/6}, 1]$.

According to the last theorem, the sets $g$ on these segments will have the corresponding segments $[-\sqrt{6}/9; \sqrt{6}/9], [-\sqrt{6}/9; 1]$ and $[-1; \sqrt{6}/9]$;

their union gives the set of values ​​of the function $g$ on the entire interval $[-1; 1] - E(g) = [-1; 1]$.

Tasks 7-8. Find the set of values ​​of the specified functions.

7. $x^3 - 6x^2 + 9x$ if: a) $x \in [2; 4]$; b) $x \in [-2; 2]$.

8. a) $\cos x \cdot \sin 2x$; b) $\sin x + \sin 3x$.

Problem 9. Within what limits can the volume of a cone with a generatrix of length 1 dm vary?

Problem 10. Within what limits can the total surface area of ​​a cylinder with a volume of 1 dm2 be limited?
