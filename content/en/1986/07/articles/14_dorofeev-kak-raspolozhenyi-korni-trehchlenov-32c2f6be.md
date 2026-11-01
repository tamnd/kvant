---
id: 1986-7-dorofeev-kak-raspolozhenyi-korni-trehchlenov-32c2f6be
issue: kvant_1986_7
year: 1986
number: "7"
title: How are the roots of the trinomials located?
authors:
  - Дорофеев Г. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 47
page_last: 51
page_labels: 45-49
tag: NJRM
lang: en
source: kvant_digital
extraction: vision
content_sha256: 4a42d306d5d1dd39e2b11a334d56aa0901f397d49df1b09746a7be92e5d4a7f1
prompt_sha256: draft-1
translated_from: content/ru/1986/07/articles/14_dorofeev-kak-raspolozhenyi-korni-trehchlenov-32c2f6be.md
source_content_sha256: 18be7bc5aa3ab24cd06a0cbd77716483858a583c89a9c741cb3ec07b795ad859
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 45⟧

How are the roots of the trinomials located?

Doctor of Physical and Mathematical Sciences
G. V. DOROFEEV

This article is devoted to solving problems in which one way or another the question is raised about the relative position of the roots (usually irrational) of two square trinomials. In terms of their mathematical content, these problems are quite simple, but from a computational point of view, most of them present serious difficulties. For example, try answering a question.

For what values ​​of a are the roots of the equation

$$x^2 + \frac{8}{a}x - 2a = 0 \quad \text{и} \quad x^2 + \frac{6}{a}x - a = 0$$

Are the variables also different (that is, between two roots of one equation there is exactly one root of another equation)?

You will see that calculating the roots of these trinomials requires painstaking comparison of them with each other for different values ​​of the parameter a.

At the same time, from graphical considerations it is clear that the roots of two square trinomials f(x) and g(x) with identical positive coefficients at x² (and positive discripients) change if and only if the point of intersection of the graphs of the functions f(x) and g(x) is located after the abscissa. In algebraic language this means that the total value of the functions f(x) and g(x) is negative. In our case, f(x) = g(x) ⇔ x = \frac{a^2}{2} and f\left(\frac{a^2}{2}\right) = \frac{a^4}{4} + 2a; therefore, the conditions of the problem satisfy the solution to the inequality a^4 + 8a < 0, or -2 < a < 0.

This example shows that the relative position of the roots of two square trinomials depends on their behavior at the point x₀, in which these trinomials belong to the same value (it is important that the point x₀ is the only one!).

Six criteria
for various occasions
pas root positions

Let the quadratic trinomials f(x) = ax² + px + q and g(x) = ax² + rx + s have which two distinct roots (x₁, x₂ and x₃, x₄, respectively, x₁ > x₂,

⟦folio 46⟧

Fig. 1.

Fig. 2.

Fig. 3.

Fig. 4.

Fig. 5.

Fig. 6.

$x_3 > x_4$), and $y(f(x))$ and $g(x)$ have no common roots and $p \neq r$. Let $x_0$ be the (unique) root of the equation $f(x) = g(x)$. Then the following statement is true:

1. $x_2 < x_1 < x_4 < x_3 \Leftrightarrow \Leftrightarrow (f(x_0) > 0, f'(x_0) > 0, g'(x_0) < 0)$;
2. $x_2 < x_4 < x_1 < x_3 \Leftrightarrow \Leftrightarrow (f(x_0) < 0, f'(x_0) > g'(x_0))$;
3. $x_2 < x_4 < x_3 < x_1 \Leftrightarrow \Leftrightarrow (f(x_0) > 0, g'(x_0) [f'(x_0) - g'(x_0)] > 0)$;
4. $x_4 < x_2 < x_1 < x_3 \Leftrightarrow \Leftrightarrow (f(x_0) < 0, f'(x_0) [g'(x_0) - f'(x_0)] > 0)$;
5. $x_4 < x_2 < x_3 < x_1 \Leftrightarrow \Leftrightarrow (f(x_0) < 0, f'(x_0) < g'(x_0))$;
6. $x_4 < x_3 < x_2 < x_1 \Leftrightarrow \Leftrightarrow (f(x_0) > 0, f'(x_0) < 0, g'(x_0) > 0)$.

The listed statements are illustrated in Figures 1-6. If you forget the wording of some criterion, it’s not a big deal: you can always restore it and use the following drawings. It is also easy to notice that criteria 4, 5, 6 are obtained from criterion 3, 2, 1 with the variables $f(x)$ and $g(x)$ interchanged (this can also be seen from the comparison of the corresponding figure). Therefore, we will prove only the first three criteria.

We will need the following well-known (very useful) properties of the quadratic trinomial:

if $f(x)$ is a quadratic trinomial with positive leading coefficient and discriminant, $x_1$ and $x_2$ are its roots, and $x_0$ is some value of the variable, then

$x_0 < x_2 < x_1 \Leftrightarrow (f(x_0) > 0, f'(x_0) < 0)$;
$x_2 < x_1 < x_0 \Leftrightarrow (f(x_0) > 0, f'(x_0) > 0)$;
$x_2 < x_0 < x_1 \Leftrightarrow f(x_0) < 0$,

(see figure 7).

Let now $h(x) = f(x) - g(x)$. It is easy to see that $h(x)$ is a linear function different from the constant ($p \neq r$). Therefore, it is monotonic (decreasing or increasing). This means that if for some $a < b$ the inequality $h(a) < h(b)$ (or $h(a) > h(b)$) holds, then for any $c < d$ the inequality $h(c) < h(d)$ (or $h(c) > h(d)$) holds.

⟦folio 47⟧

Proof of Criterion 1

Necessity (⇒). Let $x_2 < x_1 < x_4 < x_3$. Then $f(x_4) > 0$, $h(x_4) = f(x_4) - g(x_4) = f(x_4) > 0$. Likewise $g(x_1) > 0$, and therefore $h(x_1) < 0$.

From the inequalities $x_1 < x_4$ and $h(x_1) < h(x_4)$ we obtain that $h(x)$ is an increasing function.

Since $h(x_0) = 0$, we have $h(x_1) < h(x_0) < h(x_4)$, hence $x_1 < x_0 < x_4$. So, both roots $f(x)$ are less than $x_0$, hence $f(x_0) > 0$, $f'(x_0) > 0$. Likewise, both roots $g(x)$ are greater than $x_0$, hence $g'(x_0) < 0$. The necessity of criterion 1 has been proven. Enough (⇔). Let $f(x_0) > 0$, $f'(x_0) > 0$, $g'(x_0) < 0$. From the first two inequalities it follows that both roots $f(x)$ are less than $x_0$, and from the inequalities $g(x_0) > 0$, $g'(x_0) < 0$ it follows that both roots $g(x)$ are greater than $x_0$, and thus $x_2 < x_1 < x_0 < x_4 < x_3$.

Proof of Criterion 2

Necessity (⇒). Let $x_2 < x_4 < x_1 < x_3$. Then $f(x_4) < 0$, $g(x_1) < 0$, so $h(x_4) < 0 < h(x_1)$, and since $x_4 < x_1$, we see that $h(x)$ is an increasing function. Therefore, $h'(x) > 0$ for any $x$, in particular, $h'(x_0) > 0$, whence $f'(x_0) > g'(x_0)$.

On the other hand, from the condition $h(x_4) < h(x_1)$ we obtain that $x_4 < x_0 < x_1$, so $x_2 < x_0 < x_1$, whence $f'(x_0) > g'(x_0)$.

On the other hand, from the condition $h(x_4) < h(x_1)$ we obtain that $x_4 < x_0 < x_1$, so $x_2 < x_0 < x_1$, whence $f'(x_0) > g'(x_0)$.

Enough (⇔). Let $f(x_0) < 0$, $f'(x_0) > g'(x_0)$. Then $h'(x_0) > 0$, and since $h'(x)$ is a constant function, $h'(x) > 0$ for any $x$, that is, $h(x)$ is an increasing function.

From the condition $f(x_0) = g(x_0) < 0$, we obtain $x_2 < x_0 < x_1$, $x_4 < x_0 < x_3$, and since $h(x)$ returns, $0 = h(x_0) < h(x_1)$, $h(x_4) < h(x_0) = 0$, whence $g(x_1) = f(x_1) - h(x_1) < 0$, $f(x_4) = h(x_4) + g(x_4) < 0$;

therefore, $x_4 < x_1 < x_3$, $x_2 < x_4 < x_1$, that is, $x_2 < x_4 < x_1 < x_3$.

Proof of Criterion 3

Necessity (⇒). Let $x_2 < x_4 < x_3 < x_1$. Then $g(x_1) > 0$, $g(x_2) > 0$, whence $h(x_1) < 0$, $h(x_2) < 0$, and therefore on the interval $[x_2; x_1]$ the linear function $h(x)$ does not vanish, so either $x_0 < x_2 < x_1$ or $x_0 < x_2 < x_1$.

If $x_0 < x_2 < x_1$, then $x_0$ lies in the interval of decreasing common three terms, so $f'(x_0) < 0$, $g'(x_0) < 0$. In addition, $h(x_0) > h(x_2)$, so $h(x)$ is a decreasing function, $h'(x) < 0$ for any $x$, and in particular $h'(x_0) < 0$, which is $f'(x_0) - g'(x_0) < 0$. Therefore the product $g'(x_0)|f'(x_0) - g'(x_0)|$ is positive.

The case $x_2 < x_1 < x_0$ is treated similarly.

Enough (⇔). Let $f(x_0) > 0$, and assume first that $g'(x_0) > 0$, $f'(x_0) - g'(x_0) > 0$. Then both roots $g(x)$ are less than $x_0$, that is, $x_4 < x_3 < x_0$. In addition, $h(x)$ is a returning function, so $h(x_4) < x_3 < h(x_0)$, hence $f(x_4) < 0$, $f(x_3) < 0$. Therefore, $x_2 < x_4 < x_1$, $x_2 < x_3 < x_1$, that is, $x_2 < x_4 < x_1 < x_3$.

The case $g'(x_0) < 0$, $f'(x_0) - g'(x_0) < 0$ is treated similarly.

Solving inequalities

The use of proven criteria in many cases facilitates the solution of inequalities. Moving on to specific examples, then, the expression $f'(x_0) - g'(x_0)$ actually functions

Fig. 8.

neck in criteria 2-5, is equal to the difference $p - r$. Therefore, in practice, for example, it is convenient to use criterion 2 in the form $(f(x_0) < 0, p > r)$.

Let us now solve several inequalities.

1. $(x^2 + 13x - 49)(x^2 + 14x - 50) > 0$. Denoting $f(x) = x^2 - 13x - 49$, $g(x) = x^2 + 14x - 50$, we easily find that $x_0 = 1$, $f(1) = -35$, and since $13 < 14$ (see criterion 5), the roots of these three terms are related by the inequalities $x_4 < x_2 < x_3 < x_1$. Using the method of integrals (see «Kvant», No. 12, 1985, p. 18 and figure 8), we find solutions to this inequality: $x < x_4$, $x_2 < x < x_3$, $x > x_1$, or, writing out the roots, $x < -7 - 3\sqrt{11}, -\frac{13 + \sqrt{365}}{2} < x < -7 + 3\sqrt{11}, x > \frac{\sqrt{365} - 13}{2}$.

2. $(x^2 + 6x - 11) < -2x^2 - 13x + 24$. Let us rewrite this inequality in the form $2x^2 + 13x - 24 < x^2 + 6x - 11 < -2x^2 - 13x + 24$.

We must therefore solve the inequality system $f(x) < 0$, $g(x) < 0$, where

$$f(x) = 3x^2 + 21x - 39,$$

$$g(x) = 3x^2 + 19x - 35$$

(we will multiply the threelen $f(x)$ by 3 to equalize the leading coefficients $f(x)$ and $g(x)$).

We have: $x_0 = 2$, $f(2) > 0$, $g'(2) > 0$, $p - r > 0$ and (see criterion 3) $x_2 < x_4 < x_3 < x_1$. Therefore, the solutions to the system $f(x) < 0$, $g(x) < 0$, and therefore to the original inequality, is the value $x_4 < x < x_3$, that is, $-\frac{19 + \sqrt{781}}{2} < x < \frac{\sqrt{781} - 19}{2}$.

3. $(x^2 + 6x - 11) \leq |2x^2 + 13x - 26|$.

Since both sides of the inequality are non-negative, after squaring it can be written as $(x^2 + 6x - 11)^2 \leq (2x^2 + 13x - 26)^2$, and by crossing everything to the right side and factoring the difference of squares, we obtain the inequality $f(x)g(x) \geq 0$, where

⟦folio 48⟧

Fig. 9.

$$f(x) = 3x^2 + 21x - 45,$$
$$g(x) = 3x^2 + 19x - 37.$$

Then $x_0 = 4$, $f(4) > 0$, $g'(4) > 0$, $p - r > 0$ and again by criterion 3 $x_2 < x_4 < x_3 < x_1$. Applying the method of integrals, we obtain a solution to the original inequality (see Fig. 9):

$$x \leq -\frac{7 + \sqrt{109}}{2}, -\frac{19 + \sqrt{805}}{6} \leq x \leq \frac{\sqrt{805} - 19}{6}, x \geq \frac{\sqrt{109} - 7}{2}.$$

4. $$\frac{x^2 - x - 4}{4 - |3x^2 - 2x - 7|} \leq 0.$$

Let's multiply both sides of this inequality by the positive expression $(4 + |3x^2 - 2x - 7|)^{-1}$. Having factorized the difference of squares into the denominator, after simplifying we obtain the inequality

$$\frac{x^2 - x - 4}{(3x^2 - 2x - 3)(3x^2 - 2x - 11)} \geq 0.$$

Putting $f(x) = 3x^2 - 3x - 12$, $g(x) = 3x^2 - 2x - 3$, $h(x) = 3x^2 - 2x - 11$, we will find out the relative location of their roots $x_{1,2}, x_{3,4}, x_{5,6}$.

The coefficients for $x y$ of the trilens $g(x)$ and $h(x)$ are equal, so our criterion is not applicable. However, this circumstance even simplifies the solution. Indeed, $h(x) = g(x) - 8$, so $h(x_{3,4}) = g(x_{3,4}) - 8 = -8 < 0$, and therefore the roots $g(x)$ are located between the roots $h(x)$, that is

$$x_6 < x_4 < x_3 < x_5.$$

For threelens $f(x)$ and $g(x)$ we have $x_0 = -9$, $f(-9) > 0$, $f'(-9) < 0$, $g'(-9) < 0$, $-3 < -2,$

$$x_2 < x_4 < x_3 < x_1.$$

Thus, $x_6 < x_2 < x_4 < x_3 < x_5$, and hence the solution to the inequality (see Fig. 10) is:

$$x < \frac{1 - \sqrt{34}}{3}, \frac{1 - \sqrt{17}}{2} \leq x < \frac{1 - \sqrt{10}}{3},$$

$$\frac{1 + \sqrt{10}}{3} < x < \frac{1 + \sqrt{34}}{3}, x \geq \frac{1 + \sqrt{17}}{2}.$$

5. $(x^2 + 2x + 4 - a)(x^2 - 2x - a) < 0.$

Let's put $f(x) = x^2 + 2x + 4 - a$, $g(x) = x^2 - 2x - a$. Note that if the discriminant of one of these trilens is negative, then this trilen is positive for all $x$, and for the corresponding values ​​of $a$ this inequality is quadratic. These cases considered represent readers and we will assume that both discriminants are positive, which holds for $a > 3$. Then $f(x)$ and $g(x)$ each have two different roots $x_{1,2}$ and $x_{3,4}$. In this case, $x_0 = -1$, $f(-1) = 3 - a < 0$, $2 > -2$ and by criterion 2 $x_2 < x_4 < x_1 < x_3$. Therefore, for $a > 3$ the solutions to this inequality are (see Fig. 11)

$$-1 - \sqrt{a - 3} < x < 1 - \sqrt{a + 1},$$

$$-1 + \sqrt{a - 3} < x < 1 + \sqrt{a + 1}.$$

The complete solution of the inequality, taking into account the “special” values ​​of the parameter $a = 3$ and $a = -1$ (when one of the discriminants is equal to 0) is written in the form: for $a \leq -1$ there are no solutions; with $-1 < a < 3$ we get $1 - \sqrt{a + 1} < x < 1 + \sqrt{a + 1}$; with $a > 3$ we get $-1 - \sqrt{a - 3} < x < 1 - \sqrt{a + 1},$

$$-1 + \sqrt{a - 3} < x < 1 + \sqrt{a + 1}.$$

6. At what values ​​of a does the system of inequality

$$2x^2 - 3ax - 9 \leq 0, x^2 + ax - 2 \geq 0$$

has a solution?

Note that each of the square trilens

$$f(x) = 2x^2 - 3ax - 9$$

And

$$g(x) = 2x^2 + 2ax - 4$$

has two different roots, and

$$f(x) \leq 0 \Leftrightarrow x_2 \leq x \leq x_1,$$

$$g(x) \geq 0 \Leftrightarrow x \leq x_4$$ or $x \geq x_3$.

⟦folio 49⟧

In order for this system to have a solution, it is necessary and sufficient that the segment $[x_2; x_1]$ has at least one common point with one of the rays $|-\infty; x_4|$ and $[x_3; +\infty]$. This is true (without taking into account the possibility of coincidence of roots) in all of our criteria except the fourth: the system has no solutions if and only if $x_4 < x_2 < x_1 < x_3$.

Since $f(x) = g(x) \Leftrightarrow ax = -1$, then for $a \neq 0$ we have $x_0 = -\frac{1}{a}$,

$$f\left(-\frac{1}{a}\right) = \frac{2}{a^2} - 6, \quad f'\left(-\frac{1}{a}\right) = -\frac{4}{a} - 3a,$$

$$g'\left(-\frac{1}{a}\right) = -\frac{4}{a} + 2a$$

and according to criterion 4 the system of inequalities must be satisfied

$$2 - 6a^2 > 0, \quad -\left(\frac{4}{a} + 3a\right) 5a > 0.$$

It is easy to verify that this system has no solutions, so that there are no “bad” values ​​of $a \neq 0$, that is, for any $a \neq 0$ this system has a solution. Since it also has a solution for $a = 0$, solutions to Problem 6 are all values ​​of $a$.

7. For what values ​​of a is the set of solutions of the system of inequalities $x^2 + 2x + a + 1 \geq 0, x^2 + x + 2a - 1 \leq 0$ a segment of length 1? Discriminate trilens

$$f(x) = x^2 + 2x + a + 1 \quad \text{и} \quad g(x) = x^2 + x + 2a - 1$$

are equal to $-4a$ and $5 - 8a$, respectively, therefore for $a > 5/8$ the given system has no solutions, and for $0 < a < 5/8$ it is equivalent to the inequality $g(x) \leq 0$ and is satisfied on the interval $[x_4; x_3]$. From the condition

$$x_3 - x_4 = 1 \Leftrightarrow \sqrt{5 - 8a} = 1 \Leftrightarrow a = 1/2$$

and since $0 < 1/2 < 5/8$, we obtain that $a = 1/2$ is a solution to the problem.

At $a = 0$ and at $a = 5/8$ the solutions of the system are the corresponding ones at $x_1 - x_2 = 1$, from where $a = -1$ is found. Answer: $a = -1$ and $a = 1/2$.

Note that criterion 1-6 does not apply to the case when the trilenes $f(x)$ and $g(x)$ have a common root. In practice, as a rule, it is better to consider cases of coincidence of roots separately, as “specials”.

Exercises.
Solve the inequalities:

1. $|x^2 + 10x + 5| < |2x^2 + 21x + 8|$.
2. $|x - a| < 3x - x^2 - 1$.
3. $16a^3x^4 - 8a^2x^2 + 16x + a - 4 \geq 0$ ($a > 0$).
4. Solve the systems of inequalities $3x^2 + 2kx - k - 1 \leq 0$ ($k = 1, 2, \dots, 10$).
