---
id: 1984-9-kushnir-prostoy-priem-v-neprostyih-zadachah-39207606
issue: kvant_1984_9
year: 1984
number: "9"
title: A simple trick for difficult tasks
authors:
  - Кушнир И. А.
rubric: shkola-v-kvante
page_first: 27
page_last: 28
page_labels: 25-26
tag: MHGB
lang: en
source: kvant_digital
extraction: vision
content_sha256: 948cea788248817231acfeabd892137daf791d34a94176af3bf062c5efd2b4dd
prompt_sha256: draft-1
translated_from: content/ru/1984/09/articles/13_kushnir-prostoy-priem-v-neprostyih-zadachah-39207606.md
source_content_sha256: 7d6fd2eebd6007cf4e76de0f29cfaa6b9dedca17e265389e3aa8082e5b69bc7c
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 25⟧

find a value of $Q_T$ that would satisfy the conditions

$$\frac{Q-Q_T}{d} = \text{целое число},$$

(1)

where $d$ is a prime divisor in the column of the found value $Q_T$.

In the row $R=27$, condition (1) corresponds to the table values ​​$Q_T=38$ in the divisor columns $d=89$ and $d=43$. These are the prime factors of the given number $(89 \times 43=3827)$.

Let us now analyze the number 5251. When we divide it by 100, we get the quotient $Q=52$ and the remainder $R=51$. For numbers with $R>49$, we take together $R$ in the table input its “reduced” value $R'=100-R$, i.e. in this case $R'=100-51=49$. In this case, together with conditions (1), the following conditions must be met:

$$\frac{Q'+Q_T}{d} = \text{целое число},$$

(2)

where $Q'=Q+1$. In this case $Q'=52+1=53$.

In the row $R=49$, condition (2) is met by $Q_T=36$, in the divisor column $d=89$ $(53+36=89)$ and $Q_T=6$ in the divisor column $d=59$ $(53+6=59)$. Thus, the prime factors of a given number are $89 \times 59=5251$.

The number is 51620. After dividing it by 20, all that remains is to analyze the number 2581. Here $R=81$. Therefore, $R'=100-81=19$, $Q=25$. Therefore, $Q'=25+1=26$.

Condition (2) here is obtueed by $Q_T=63$ in the divisor column $d=89$ and $Q_T=3$ in the divisor column $d=29$. So, $89 \times 29 \times 20=51620$.

Note that the common factor for all three numbers is the prime number 89.

Using the table, it is not difficult to determine that the number 10607 mentioned above is prime. Indeed, in the row $R=07$ there is not a single value $Q_T$ that, when subtracted from $Q=106$, would satisfy conditions (1).

V. S. Khitruk

Able to cope with difficult tasks

A sixth grader is familiar with the formula for the square of the sum or difference of two numbers. It is not difficult to learn how to isolate a perfect square from an algebraic expression, “recognize” it, and then extract the root. These actions often help in solving specific problems. Of course, the problems given below can also be solved in other ways, but knowing how to use the examples indicated allows the applicant to “save” the much-needed time on the exam.

Simplifying Expressions

Example 1 (MSU, mechanism, 1978). The difference $\sqrt{|40\sqrt{2}-57|}-\sqrt{40\sqrt{2}+57}$ is an integer. Find this number.

In the book by Yu. V. Nesterenko, S. N. OLEXNIKA, M. K. Potapov “Problems of entrance exams in mathematics” (M., Nauka, 1980), the authors denote the desired number by $x$, find that $x$ is one of the numbers 10 or -10 and by comparing the subtracted and subtracted they come to the conclusion that $x=-10$ (p. 132).

Let's solve the same example by selecting a complete square; this example will be useful to us later.

$$A=\sqrt{40\sqrt{2}+57}=\sqrt{25+40\sqrt{2}+32}=\sqrt{(5+4\sqrt{2})^2}=5+4\sqrt{2},$$

$$B=\sqrt{|40\sqrt{2}-57|}=\sqrt{|(5-4\sqrt{2})^2|}=-5+4\sqrt{2}.$$

Thus, $B-A=-10$.

Example 2 (MSU, mechanism, 1969; KPI, 1980). Simplify:

$$\sqrt{x+2\sqrt{x-1}}+\sqrt{x-2\sqrt{x-1}}.$$

Solution:

$$A=\sqrt{x+2\sqrt{x-1}+1-1}+\sqrt{x-2\sqrt{x-1}+1-1}=\sqrt{(\sqrt{x-1}+1)^2}+\sqrt{(\sqrt{x-1}-1)^2}=|\sqrt{x-1}+1|+|\sqrt{x-1}-1|=\sqrt{x-1}+1+|\sqrt{x-1}-1|.$$

It is obvious that $x \geqslant 1$;

a) for $2 \geqslant x \geqslant 1$, we have

⟦folio 26⟧

$$A = \sqrt{x-1} + 1 - \sqrt{x-1} + 1 = 2;$$
6) at $x \geqslant 2$
$$A = \sqrt{x-1} + 1 + \sqrt{x-1} - 1 = 2\sqrt{x-1}.$$
Example 3 (KPI, 1980). Simplify:
$$\frac{\sin^4 \alpha + \cos^4 \alpha - 1}{\sin^6 \alpha + \cos^6 \alpha - 1}.$$
Solution:
$$\frac{\sin^4 \alpha + \cos^4 \alpha - 1}{\sin^6 \alpha + \cos^6 \alpha - 1} = \frac{\sin^4 \alpha + \cos^4 \alpha + 2 \sin^2 \alpha \cos^2 \alpha - 2 \sin^2 \alpha \cos^2 \alpha - 1}{\sin^4 \alpha + \cos^4 \alpha + 2 \sin^2 \alpha \cos^2 \alpha - 3 \sin^2 \alpha \cos^2 \alpha - 1} = \frac{(\sin^2 \alpha + \cos^2 \alpha)^2 - 2 \sin^2 \alpha \cos^2 \alpha - 1}{(\sin^2 \alpha + \cos^2 \alpha)^2 - 3 \sin^2 \alpha \cos^2 \alpha - 1} = \frac{2}{3}.$$
Solving the equation
When solving irrational equations, one should not rush to square them; it is worth looking to see if it is possible to isolate it?
Example 4 (KPI, 1979). Solve the equation:
$$\sqrt{x-2} + \sqrt{2x-5} + \sqrt{x+2+3\sqrt{2x-5}} = 7\sqrt{2}.$$
Solution:
We have
$$\frac{1}{\sqrt{2}}(\sqrt{2x-5} + 2\sqrt{2x-5} + 1) + \sqrt{2x-5} + 6\sqrt{2x-5} + 9) = \frac{1}{\sqrt{2}}(\sqrt{(\sqrt{2x-5}+1)^2} + \sqrt{(\sqrt{2x-5}+3)^2} = \frac{1}{\sqrt{2}}(|\sqrt{2x-5}+1| + |\sqrt{2x-5}+3|).$$
So the given equation is equivalent to the equation
$$\frac{1}{\sqrt{2}}(\sqrt{2x-5} + 1 + \sqrt{2x-5} + 3) = 7\sqrt{2}$$
or $2\sqrt{2x-5} = 10$, from where $x = 15$.
Example 5 (KSU, Faculty of Economics, 1978). Solve the equation:
$(\sqrt{4+2\sqrt{3}} - \sqrt{4-2\sqrt{3}})^{2x} + 2^{2x+3} = 144.$
Solution:
We have
$$\sqrt{4+2\sqrt{3}} = \sqrt{3+2\sqrt{3}} + 1 = \sqrt{(\sqrt{3}+1)^2} = \sqrt{3}+1;$$
similar to $\sqrt{4-2\sqrt{3}} = \sqrt{3}-1$. Therefore, the given equation will take the form
$$4^x + 8\cdot 4^x = 144, x = 2.$$
Example 6 (MSU, 1978, Faculty of Philology). The number $\alpha$ is chosen so that the equation $\sqrt{x-\sqrt{3}} + \alpha^2 x^2 + 2\alpha x(\sqrt{6}-\sqrt{3}) = 6\sqrt{2}-9$ has a solution. Find a solution.
Solution: Let $x_1$ be the root of the equation. Then $x_1 \neq 0$ and $\sqrt{x_1-\sqrt{3}} + \alpha^2 x_1^2 + 2\alpha x_1(\sqrt{6}-\sqrt{3}) - 6\sqrt{2}+9 = 0$, or
$$\alpha^2 + 2\alpha \left(\frac{\sqrt{6}-\sqrt{3}}{x_1}\right) + \frac{\sqrt{x_1-\sqrt{3}} + 9 - 6\sqrt{2}}{x_1^2} = 0.$$
Let us select a complete square with respect to the numbers $x_1$ and $\alpha$. We have
$$\left(\alpha + \frac{\sqrt{6}-\sqrt{3}}{x_1}\right)^2 + \frac{\sqrt{x_1-\sqrt{3}}}{x_1^2} = 0.$$
Since each term is not negative, then $x_1 = \sqrt{3}$, and $\alpha = 1 - \sqrt{2}$.
Example 7. Solve equation $\sin^2 x + \sin^2 y = \sin x \sin y + \sin x \sin y - 1.$
Solution: This equation is equivalent to:
$(\sin^2 x - 2 \sin x + 1) + (\sin^2 y - 2 \sin y + 1) + (\sin^2 x + \sin^2 y - 2 \sin x \sin y) = 0$, or $(\sin x - 1)^2 + (\sin y - 1)^2 + (\sin x - \sin y)^2 = 0$, from where $x = \sin y = 1$, $x = \sin y$. Thus, the solution to the equation will be any pair of the form
$$x = \frac{\pi}{2} + 2\pi k, y = \frac{\pi}{2} + 2\pi n, k, n \in Z.$$
Exercises
1. (MSU, 1979, Faculty of Economics) Solve the equation: $\log_{3x+7}(9+12x+4x^2) + \log_{2x+3}\times(6x^2+23x+21) = 4.$
2. (KSU, 1978, Faculty of Chemistry) Solve the equation: $(\sqrt{6+2\sqrt{5}} - \sqrt{6-2\sqrt{5}})^{2x} + 2^{2(x+1)} = 320.$
3. (MSU, 1965, mechanics) Find all pairs of numbers that satisfy the equation
$$\cos x + \cos y - \cos(x+y) = \frac{3}{2}.$$
4. (KSU, 1973, mechanics) Solve inequality $\sqrt{x+4\sqrt{x-4}} - \sqrt{x-4\sqrt{x-4}} \geq 3.$
5. (MSU, 1982, Faculty of Biology) Find the most and most values ​​of the function
$$y(x) = x + \sqrt{(x^2+6x+9)(x^2+2x+1)}$$
on the segment $[-4; -\frac{5}{4}].$

I. A. Kushinr
