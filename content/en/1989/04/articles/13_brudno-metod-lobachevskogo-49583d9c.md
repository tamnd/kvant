---
id: 1989-4-brudno-metod-lobachevskogo-49583d9c
issue: kvant_1989_4
year: 1989
number: "4"
title: Lobachevsky method
authors:
  - Брудно А. Л.
rubric: raznoe
rubric_sub: Разное
page_first: 53
page_last: 54
page_labels: 51-52
tag: X2EG
lang: en
source: kvant_digital
extraction: vision
content_sha256: 15dc9f22c92b2654c883469391048fd48d86d8be8835debe5b3a7791f46e29f2
prompt_sha256: draft-1
translated_from: content/ru/1989/04/articles/13_brudno-metod-lobachevskogo-49583d9c.md
source_content_sha256: be6e66586612f57e3b48e8b8de6bb3fa75fa38b425b43fd0e83ea475d98d0191
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 51⟧

Lobachevsky method

Doctor of Physical and Mathematical Sciences
A. L. BRUDNO

The creator of non-Euclidean geometry N. I. Lobachevsky also came up with a method for approximate solution of an algebraic equation (with real coefficients)

$$a_0 + a_1x + a_2x^2 + \dots + a_nx^n = 0. \quad (1)$$

The method allows you to find the absolute value of the root having the maximum modulus. After this, the sign of the root can be easily determined by substitution into the given equation. The only restriction on the use of the method is that the root with the maximum absolute value must be unique. If, for example, it is complete, then there are already two of them (that is, it is also complex conjugate) and the method is not applicable. Subsequently, this method was improved, and it became possible to find all the roots of an equation if their modules are different.

Lobachevsky's idea is as follows. Let us replace the given equation (1) with another whose roots are equal to the squares of the roots of the given one. We will repeat this technique many times. Then the roots of the equation will be “squared”, then to the 4th power, to the 8th, etc. As a result, the root with the maximum modulus begins to play an overwhelming role over the others and can be easily calculated from the coefficients of the resulting equation (see below). If now the answer requires a root in powers, then we get (approximately) the absolute value of the root of the original equation.

1. So, Lobachevsky needed to find a polynomial whose roots were equal to the squares of the roots of the original polynomial, and he had to find it without calculating the roots of the original polynomial. Let's see what Lobachevsky did. We are given a polynomial

$$P(x) = a_0 + a_1x + a_2x^2 + \dots + a_nx^n. \quad (2)$$

There is a theorem: the polynomial $P(x)$ can be represented as

$$P(x) = a_n(x - x_1)(x - x_2) \dots (x - x_n),$$

where $x_1, x_2, \dots, x_n$ are the roots of the equation $P(x) = 0$ (at school this is studied only for $n=2$ and is called “factorization of a quadratic trinomial”). Let's take the polynomial $P(-x)$. It can be written in the form

$$P(-x) = a_0 - a_1x + a_2x^2 - \dots + (-1)^n a_nx^n.$$

or

$$P(-x) = a_n(-x - x_1)(-x - x_2) \dots (-x - x_n),$$

or even like this:

$$P(-x) = (-1)^n a_n(x + x_1)(x + x_2) \dots (x + x_n).$$

Consider the product of polynomials

$$P(x)P(-x) = (-1)^n a_n^2(x^2 - x_1^2)(x^2 - x_2^2) \dots (x^2 - x_n^2).$$

⟦folio 52⟧

Note that it does not contain odd powers $x$. If we replace $x^2$ with $t$ in this product, we get the polynomial we need

$$Q(t) = (-1)^n a_n^2 (t - x_1^2) (t - x_2^2) \dots (t - x_n^2),$$

whose roots are equal to the squares of the roots of the given polynomial $P(x)$. To calculate the coefficients $b_k$ of the polynomial $Q(t)$

$$Q(t) = b_0 + b_1 t + b_2 t^2 + \dots + b_{n-1} t^{n-1} + b_n t^n$$

you can change $P(x)$ and $P(-x)$, bring similar terms for the same powers $x$ (odd powers will disappear) and replace $x^2, x^4, \dots$ with $t, t^2, \dots$.

Here are the formulas for the coefficients $b_k$ for $n=3$ and $n=4$:

$$n = 3; a_0 + a_1 x + a_2 x^2 + a_3 x^3 = 0$$
$$b_0 = a_0 a_0$$
$$b_1 = a_0 a_2 - a_1 a_1 + a_2 a_0$$
$$b_2 = -a_1 a_3 + a_2 a_2 - a_3 a_1$$
$$b_3 = -a_3 a_3$$

$$n = 4; a_0 + a_1 x + a_2 x^2 + a_3 x^3 + a_4 x^4 = 0$$
$$b_0 = a_0 a_0$$
$$b_1 = a_0 a_2 - a_1 a_1 + a_2 a_0$$
$$b_2 = a_0 a_4 - a_1 a_3 + a_2 a_2 - a_3 a_1 + a_4 a_0$$
$$b_3 = a_2 a_4 - a_3 a_3 + a_4 a_2$$
$$b_4 = a_4 a_4$$

The calculation of coefficients $b_k$ is not difficult to put on a computer or even a programmable microcalculator. After calculating the coefficients $b_k$, their values ​​are assigned to the coefficients $a_k$, new ones $b_k$ are calculated, etc., until the root with the maximum modulus becomes dominant.

To find the value of this root, let's return to the formulas

$$Q(t) = b_0 + b_1 t + \dots + b_{n-1} t^{n-1} + b_n t^n$$
$$Q(t) = b_n (t - t_1) (t - t_2) \dots (t - t_n).$$

If you open the brackets and the reduced terms in the bottom line, you should get the top line. Hence,

$$b_{n-1} = -(t_1 + t_2 + \dots + t_n) b_n$$

or

$$t_1 (1 + t_2/t_1 + t_3/t_1 + \dots + t_n/t_1) = -b_{n-1}/b_n.$$

If the root $t_1$ significantly exceeds the others in modulus, then the expression in parentheses is close to 1 and the approximation

$$t_1 \approx -b_{n-1}/b_n.$$

It is interesting that the Lobachevsky method can also be used to find the values ​​of the remaining roots of the equation (if they are all different in modulus). Let the root $t_2$ be less than $t_1$, but the significant one exceeds the rest. Then in the expression for $b_{n-2}$

$$b_{n-2} = (t_1 t_2 + t_1 t_3 + \dots + t_2 t_3 + \dots) b_n$$

in brackets, the main role will be played by $t_1 t_2$, and we can approximately assume that $b_{n-2} \approx t_1 t_2 b_n$, from which

$$t_2 \approx -b_{n-2}/b_{n-1}.$$

Same as $t_k \approx -b_{n-k}/b_{n-k+1}$.

2. Approximations obtained using Lobachevsky's method very quickly converge to an exact solution. When calculating on a computer or microcalculator, you need to set up a counter for the number of iterations (denote it by $p$) and add 1 to it after each iterations. For the roots $x_k$ of the original equation it will be

$$|x_k| = t_k^{1/2^p},$$

since the polynomial $Q(t)$ is obtained as a result of $p$ iterations (repeatedly going from the polynomial $P$ to the polynomial $Q$ and replacing the roots with their squares). $|x_k|$ should only be calculated if $t_k > 0$. The value of $t_k$ can be negative if there are roots that are equal in magnitude, or during the first iterations. It is convenient to display the approximate values ​​of the root model $x_k$ on the screen after each iterations and monitor how they are established. It was precisely this method, but with hand calculations, that Lobachevsky came up with.

Experiment with the MK-61 microcalculator for the cubic equation 0.76—1.37x—1.3x²+2x³=0, having roots $x_1=0,95$; $x_2=-0,8$; $x_3=0,5$, gave the following picture of convergence (2-3 decimal places are given; each iteration took 15 seconds):
