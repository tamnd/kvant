---
id: 1980-2-kerimov-kak-nayti-tselyiy-koren-2196fff2
issue: kvant_1980_2
year: 1980
number: "2"
title: How to find a whole root?
authors:
  - Керимов З.
rubric: osnovnye-stati
page_first: 24
page_last: 24
page_labels: "22"
tag: WSO6
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7aef0a6bf29d5644ebd363e993e9b0af69fc67a54ad77ebaf0b52517cbe27fc7
prompt_sha256: draft-1
translated_from: content/ru/1980/02/articles/06_kerimov-kak-nayti-tselyiy-koren-2196fff2.md
source_content_sha256: 7842d5a1e61f767dc5de07c41e0b6372dbf71a50ee08a20334cc62963c3afcbf
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 22⟧

3. Kerimov

How to find a whole root?

Suppose we need to solve the equation
$$a_0x^n + a_1x^{n-1} + \dots + a_{n-1}x + a_n = 0.$$ (1)

If $n = 1$ or $n = 2$, we can do it - there are formulas in school textbooks. If $n = 3$ or $n = 4$, then the same formulas exist («Kvant», 1976, No. 9), however, they are quite cumbersome. If $n > 4$, then such formulas simply do not exist - not “not found”, but it has been proven that they do not exist («Kvant», 1976, No. 5, p. 6). How can this be? How are the roots of the equation of “higher powers” ​​found?

To find integer roots of an equation with integer coefficients*), you can use the following sufficient condition: if $l$ is an integer root of equation (1) with integer coefficients, then $l$ is a divisor of the free celene $a_n$.

Indeed, if $l$ is the root of equation (1), then
$$a_n = l(-a_0l^{n-1}-a_1l^{n-2}-\dots-a_{n-1}).$$ (2)

If $l \in \mathbb{Z}$ and coefficients $a_0,a_1,\dots,a_{n-1}$, $a_n$ are also integers, then $-a_0l^{n-1}-a_1l^{n-2}-\dots-a_{n-1} \in \mathbb{Z}$ and (2) means that $a_n$ is divisible by $l^{**}$).

So if we look at everything - positive and negative! are divisors of the number $a_n$ and we will check each of them whether it is a root; we will find (if there are!) all the integer roots.

*) However, an equation with rational coefficients can easily be replaced by an equivalent equation with integer coefficients. How?

**) The concepts of “divisor” and “divided” are defined for integers.

Example 1. The free term of the equation
$$3x^3+5x^2+x-46=0$$ (3)

the following divisors: ±1, ±2, ±23, ±46. By checking the “small” divisors (±1, ±2), we see that 2 is the root of equation (3). Further, one could check the “large” divisors (however, for this particular equation it is easy to see, without fully calculating, that none of the numbers ±23, ±46 are roots), but it is easier, as they say, to lower the degree of the equation, using an easy to prove statement: the number $l$ if and only then is a root of the polynomial $f(x)$ when $f(x)$ is divisible by $x-l^*$): Since 2 is the root of equation (3), the polynomial $3x^3+5x^2+x-46$ is divisible by $x-2$. Let's find the quotient.

$$\frac{3x^3+5x^2+x-46}{3x^3-6x^2} = \frac{x-2}{3x^2+11x+23}$$

So, $3x^3+5x^2+x-46 = (x-2)(3x^2+11x+23)$. This means that together with the cubic equation (3) we can now solve the quadratic equation $3x^2+11x+23 = 0$. This last equation has no (real) roots. This means that equation (3) has one root 2.

Example 2. The free term of the equation
$$x^4-17x^3+77x^2-85x+360=0$$ (4)

there are a lot of divisors: ±1, ±2, ±3, ±4, ±5, ±6, ±8, ±9, ±10, ±12, ±15, ±18, ±20, ±24, ±30, ±36, ±40, ±45, ±60, ±72, ±90, ±120, ±180, ±360. Substituting them all on the left side of the equation is not very rewarding work. True, it is immediately clear that this equation cannot have negative roots, but there will still be 24 divisors left.

Let us use the following generalization from the above statement about integer roots: if $l$ is an integer root of equation (1) with integer coefficients, then for any $m \in \mathbb{Z}$ difference $m-l$ is a divisor of a number $f(m)$ (here via $f(x)$ marked with many

*) See the article by S. Ashmanov “Numbers and polynomials”, p. 17.
