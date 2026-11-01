---
id: 1980-6-mihaylov-o-diofantovom-analize-de96c8b7
issue: kvant_1980_6
year: 1980
number: "6"
title: About Diophantine analysis
authors:
  - Михайлов И. И.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 18
page_last: 19
page_labels: 16-17
tag: WUIL
lang: en
source: kvant_digital
extraction: vision
content_sha256: 16b6d1476ab31183f2f50b206bc8955c6b2513be58b14c749f033e88a49d73cd
prompt_sha256: draft-1
translated_from: content/ru/1980/06/articles/08_mihaylov-o-diofantovom-analize-de96c8b7.md
source_content_sha256: 77ea0ad92c4455dd7bf095d38a5183c8573d9d70b02155066b37d2d5972299da
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 16⟧

About Diophantine analysis

The field of number theory that studies integer solutions to equations of the form $P(x, y, ..., z) = 0$, where $P(x, y, ..., z)$ is a polynomial in several variables with integer coefficients, is called Diophantine analysis, and these equations themselves are called Diophantine. We have already written about some Diophantine equations and methods for solving them*).

Recall that solving a Diophantine equation means the following:

1. does it have at least one integer solution;
2. the number of its integer solutions is finite or infinite;
3. find all its integer solutions.

For example, for the equation $x^3 + y^3 + z^3 = 30$, no integer solutions are shown. However, perhaps a solution will be found later. Or maybe it will be proven that they do not exist.

But for the equation $x^3 + y^3 + z^3 = 3$ four solutions are known: (1; 1; 1), (4; 4; -5), (4; -5; 4), (-5; 4; 4). But the question remains open: are there other solutions?

Another example. It is proven that the equation $x^3 + y^3 + z^3 = 2$ has an infinite number of solutions in integers $(x; y; z) = (1 + 6\alpha^3; 1 - 6\alpha^3; -6\alpha^2)$, where $\alpha$ is an integer. But before

*) See «Kvant», 1971, No. 3, p. 15; 1978, no. 1, p. 25; No. 12, p. 2.

It is still not clear whether all of its solutions are given by these formulas.

A powerful means of proving the infinity of the set of integer solutions of Diophantine equations is the parameterization method. The essence of this method is to represent the variables $x, y, ..., z$ as a function depending on the integer parameters $\alpha, \beta, ..., \gamma$: $x = A(\alpha, \beta, ..., \gamma), y = B(\alpha, \beta, ..., \gamma), ..., z = C(\alpha, \beta, ..., \gamma)$, where $A, B, ..., C$ are polynomials with integer coefficients. Parameterization methods, sometimes very artificial, but extremely original, require, as a rule, great ingenuity, and therefore contribute to the acquisition and development of skills of independent creative activity in mathematics.

Let's return to the equation $x^3 + y^3 + z^3 + z^3 = 2$ and try to parameterize it. To do this, let's put $x = a + b, y = a - b$, where $a$ and $b$ are integers; we get $2a^3 + 6ab^2 + z^3 = 2$. Let $a = 1$, then $6b^2 = -z^3$, whence $z = 6c$ ($c$ is an integer), that is, $b^2 = -36c^3$. In this case, $c = -\alpha^2$ ($\alpha$ is an integer), but then $b = 6\alpha^3$. The final result is $(1 + 6\alpha^3)^3 + (1 - 6\alpha^3)^3 + (-6\alpha^2)^3 = 2$.

That is $x = A(\alpha) = 1 + 6\alpha^3, y = B(\alpha) = 1 - 6\alpha^3, z = C(\alpha) = -6\alpha^2$. Substituting integers instead of $\alpha$, we obtain different solutions.

Problem 1. Parameterize the equation $x^3 + y^3 + z^3 = 2t^3$ and prove that the set of its integer solutions is infinite.

Mathematicians interested in number theory have been attracted for many years by a hitherto unsolved problem: is the equation $x^4 + y^4 + z^4 = t^4$ solvable in integers?

In 1914, A. Verebryusov proposed a proof of its undecidability. However, as we found out later, his proof of this equation in integers was already stated by Euler. In 1945, the equation $x^4 + y^4 + z^4 = t^4$ was proven to have no integer solutions for $|t| < 10^8$. But, of course, this is not yet a complete solution.

⟦folio 17⟧

Let’s try to solve a simpler problem, although “more complex” in appearance: we will prove the infinity of the set of integer solutions to the equation $x^4 + y^6 + z^{12} = t^4$.

Let $x = a - b$, $t = a + b$, where $a$ and $b$ be integers. Then $y^6 + z^{12} = 8a^3b + 8ab^3$. Let's put $y^6 = 8a^3b$, $z^{12} = 8ab^3$; then $a = c^3$, $b = d^3$ (c and $d$ are integers) and $y^2 = 2c^3d$, $z^4 = 2cd^3$.

It follows that $2cd$ is the square of an integer. By fielding $c = a^4$, $d = 2\beta^4$ ($\alpha, \beta$ are integers), we also get the valid

$$\left( \alpha^{12} - 8\beta^{12} \right)^4 + \left( 2\alpha^6\beta^2 \right)^6 + \left( 2\alpha\beta^3 \right)^{12} = \left( \alpha^{12} + 8\beta^{12} \right)^4,$$

proving what is required.

Problem 2. Find another identity that describes the solution to the equation $x^4 + y^6 + z^{12} = t^4$.

But to prove the unsolvability of a certain Diophantine equation, it was very useful to note that we consider this equation “according to a certain modulo”*). Let us explain what we mean.

Two integers $a$ and $b$ are said to be comparable modulo $k$ if the difference $a - b$ is divisible by $k$. It is easy to see that two numbers $a$ and $b$ are comparable modulo $k$ if and only if they have the same remainders when divided by $k$. The fact that $a$ and $b$ are comparable modulo $k$ is written as follows:

$$a \equiv b \pmod{k}.$$

Suppose we need to solve the Diophantine equation

$$x^3 + 117y^3 = 5.$$

Let's consider this equation “modulo 9,” that is, up to terms that are multiples of nine. It is not difficult to show that any number cubed is either divisible by 9 or, when divided by 9, leaves a remainder of 1 or 8, that is, $x^3 \equiv 0 \pmod{9}$ or $x^3 \equiv 8 \pmod{9}$.

Since 117 is divisible by 9, $117y^3 \equiv 0 \pmod{9}$. Thus,

$$x^3 + 117y^3 \equiv 0 \pmod{9}.$$

or

$$x^3 + 117y^3 \equiv 1 \pmod{9}.$$

or

$$x^3 + 117y^3 \equiv 8 \pmod{9}.$$

Therefore, the equation $x^3 + 117y^3 = 5$ has no integer solutions.

Problem 3. Prove that the equations a) $x^3 + y^3 = 9t \pm 4$; b) $x^3 + y^3 = 9t \pm 3$; b) $x^3 + y^3 + z^3 = 9t \pm 4$ has no integer solutions.

Triangular and square numbers*) are related to the regular triangle and square, respectively (see figure 1, 2).

Let us denote the $n$th triangular number by $T_n$, and the $n$th square number by $K_n$.

Problem 4. Prove the following formulas: $T_n = \frac{1}{2}n(n+1)$; $K_n = n^2$.

The task is to find all triangular numbers that are square, connected to the solution of the equation $T_n = K_n$, that is, the equation $n(n+1) = 2m^2$.

The equation $x^2 - 2y^2 = 1$ can help us solve this equation. It has an infinite set of solutions (in natural numbers), given recurrently: $x_{k+1} = 3x_k + 4y_k$ and $y_{k+1} = 2x_k + 3y_k$, $x_1 = 3$, $y_1 = 2$ (prove this yourself or see the proof in «Kvant», 1978, No. 1, p. 26).

(For the end see p. 35)

*) See articles by M. Bashmakov («Kvant», 1971, No. 3) and A. Geronimus («Kvant», 1978, No. 12).

2 «Kvant» № 6
