---
id: 1972-12-gershunov-irratsionalnyie-neravenstva-f3721fcf
issue: kvant_1972_12
year: 1972
number: "12"
title: Irrational inequalities
authors:
  - Гершунов Е. М.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 51
page_last: 52
page_labels: 49-50
tag: 2ERT
lang: en
source: kvant_digital
extraction: vision
content_sha256: db43ea0b6b9e088946339fa8d06bb385650aa6bff058c8ca4811eba8c5a431f2
prompt_sha256: draft-1
translated_from: content/ru/1972/12/articles/10_gershunov-irratsionalnyie-neravenstva-f3721fcf.md
source_content_sha256: 5c7afdf3eed208611ead835628c935cc1c612e3d9805aa743d6b91c642c0eab1
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 49⟧

IRRATIONAL INEQUALITIES

E. M. Gershunov

At university entrance exams, examples or problems are increasingly being offered, the main or constituent element of which is an inequality containing an unknown quantity under the radical sign (irational inequality). Practice shows that most applicants have difficulty solving irrational inequalities. The reason for this, apparently, is that school curricula and mathematics textbooks do not contain this topic.

This article does not represent a complete coverage of all issues related to the solution of irrational inequalities. The main focus here is on solving irrational inequalities involving radicals of the second degree.

Let us first prove the following theorem, which plays a major role in solving irrational inequalities.

Theorem. If $f(x) \geq 0$ and $\partial(x) \geq 0$, then the inequalities $f(x) \geq g(x)$ and $[f(x)]^2 \geq [g(x)]^2$ are equivalent.

Proof. We need to determine the sign of the difference

$$[f(x)]^2 - [g(x)]^2.$$ (1)

Let's factor (1) into factors:

$$[f(x)]^2 - [g(x)]^2 = [f(x) + g(x)][f(x) - g(x)].$$ (2)

The first factor on the right side is non-negative by condition. If it is positive, then the sign of the difference (1) coincides with the sign of the second factor in (2), and if $f(x) + g(x) = 0$, then $f(x) = 0$ and $g(x) = 0$, and again the inequalities are equivalent.

It is easy to prove that this theorem remains valid if all signs of the non-strict inequality $\geq$ are replaced by

thread on the strictly inequality signs $>$ (do the proof yourself).

Example 1. Solve inequality

$$\sqrt{4 + 3x - x^2} < 2.$$

Solution. First we define OD3: $-1 \leq x \leq 4$. The left side of the inequality is non-negative, and the right side is positive, so let’s square both sides. We obtain an equivalent system of inequalities

$$\begin{cases} -1 \leq x \leq 4, \\ 3x - x^2 < 0, \\ -1 \leq x \leq 4, \\ x > 3, x < 0. \end{cases}$$

Answer: $3 < x \leq 4$, $-1 \leq x < 0$.

Example 2: Solve inequality

$$\sqrt{4 + 3x - x^2} > -2.$$

Solution. OD3 is the same: $-1 \leq x \leq 4$. Note that in OD3 the left side of the inequality is non-negative, and the right side is negative, so the theorem cannot be proven. But this is not necessary. Indeed, the radical has an arithmetic value, therefore, any of its values ​​in OD3 satisfies this inequality. Therefore the answer is $-1 \leq x \leq 4$.

Example 3. Solve inequality

$$\sqrt{x^2 - 5x + 4} < x - 3.$$

Solution. OD3: $x \geq 4$, $x \leq 1$. Since the right side contains an unknown quantity, we will consider two cases sequentially:

1) $x - 3 > 0$, $2) x - 3 \leq 0$.

In the first case we will use

⟦folio 50⟧

proven theorem and obtain an equivalent system
$$\begin{cases} x \geq 4, & x \leq 1, \\ x - 3 > 0, \\ x^2 - 5x + 4 < (x - 3)^2, \end{cases}$$

whence $4 \leq x < 5$.

In the second case, the original inequality has no solutions, since the arithmetic value of the root cannot be less than a non-positive number.

Answer: $4 \leq x < 5$.

Example 4. Solve inequality
$$\sqrt{x^2 - 5x - 24} > x - 2.$$

Solution. ODZ: $x \geq 8, x \leq -3$. Let's consider two cases: 1) $x - 2 \geq 0$, 2) $x - 2 < 0$.

In the first case, the right-hand side is non-negative, and using the theorem, we obtain a system of inequalities
$$\begin{cases} x \geq 8, & x \leq -3, \\ x - 2 \geq 0, \\ x^2 - 5x - 24 > (x - 2)^2, \end{cases}$$

which has no solutions.

In the second case, by the definition of a radical of even degree, the original inequality is satisfied over the entire range of admissible values. Solving the system
$$\begin{cases} x - 2 < 0, \\ x \geq 8, x \leq -3, \end{cases}$$

we find the answer: $x \leq -3$.

Example 5. Solve inequality
$$\sqrt{x - 2} + \sqrt{x - 1} > \sqrt{x + 3}.$$

Solution. ODZ: $x \geq 2$. Since both sides of the inequality are positive, using the main theorem, we obtain an equivalent system of equalities
$$\begin{cases} x \geq 2, \\ 2 \sqrt{(x - 1)(x - 2)} > 6 - x. \end{cases}$$

We solve this system by considering two cases:
$$\begin{cases} x \geq 2, \\ 6 - x \geq 0, \\ 4(x^2 - 3x + 2) > (6 - x)^2, \end{cases}$$

whence $\sqrt{\frac{28}{3}} < x \leq 6$, and
$$\begin{cases} 6 - x < 0 \\ x \geq 2 \end{cases}$$

whence $x > 6$.

Answer: $x > \sqrt{\frac{28}{3}}$.

Example 6. Solve inequality
$$\frac{\sqrt{x^2 - x - 2}}{x^2 + 2x + 3} > 0.$$

Solution. The ODZ is determined by the condition for the existence of the radical: $x \geq 2, x \leq -1$. At $x > 2, x < -1$ the numerator of the fraction takes positive values, so we move on to the equivalent system
$$\begin{cases} x > 2, x < -1, \\ x^2 + 2x + 3 > 0. \end{cases}$$

The second inequality of the system is satisfied for any real values ​​of $x$, from which we obtain the answer: $x > 2, x < -1$.

Exercises

Solve inequalities:
1. $\frac{x - 7}{\sqrt{4x^2 - 19x + 12}} < 0$.
2. $x < \sqrt{2 - x}$.
3. $x + 1 > \sqrt{x + 2}$.
4. $\sqrt{4 + 3x - x^2} < x - 1$.
5. $\sqrt{2x^2 - 8x + 7} < x - 2$.
6. $\sqrt{\frac{4}{x^2} - \frac{3}{4}} > \frac{2}{x} - 1$.
7. $\sqrt{2x - 6} + \sqrt{x + 4} > 5$.
8. $\sqrt{\frac{x + 1}{2 - x}} < 3$.
9. $\frac{1 - \sqrt{1 - 8x^2}}{2x} < 1$.
10. $\sqrt{x^2 - 3x + 2} > 2 - x$.
11. $\sqrt{\sin x} + \sqrt{\cos x} > 1$.
12. $\frac{2x}{\sqrt{2x + 9}} < \sqrt{2x + 1} - 1$.
13. $(x - 3)\sqrt{x^2 + 4} \leq x^2 - 9$.
14. $\sqrt{x^2 - 16} / |x| - |x - 2| < 0$.
