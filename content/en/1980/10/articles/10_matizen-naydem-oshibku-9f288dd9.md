---
id: 1980-10-matizen-naydem-oshibku-9f288dd9
issue: kvant_1980_10
year: 1980
number: "10"
title: Let's find the error
authors:
  - Матизен В. Э.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 45
page_last: 48
page_labels: 43-46
tag: FKVS
lang: en
source: kvant_digital
extraction: vision
content_sha256: 14540ca9e006d369d11edc5209f6d185e78c3bb559f444a1868e10aa5ebe6984
prompt_sha256: draft-1
translated_from: content/ru/1980/10/articles/10_matizen-naydem-oshibku-9f288dd9.md
source_content_sha256: b18427d8f4082750b35f06c0b81808abb4c51496a91fce96c335d5e1029d1299
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 43⟧

V. Matizen

Let's find the error

When solving problems, applicants and schoolchildren often receive answers, the error of which is clear to an experienced person at first glance. The fact is that the incorrectness of the result can often be established by very simple means, without solving the problem again.

This post shows the simplest ways to quickly check. Let's make a reservation right away: none of them gives a stop-point guarantee. But if the answer contains a gross error, it will be detected with a high probability. In addition, checking is much more useful than that method of self-control, which, alas, is the only one that most students have - checking with a neighbor. So, teacher, test yourself!

1. Identities and identical transformations

Let it be necessary to simplify the expression

$$f(x,y) = \sin^2 \frac{x-y}{2} + \sin^2 \frac{x+y}{2} - 2 \sin \frac{x+y}{2} \sin \frac{x-y}{2} \cos y.$$

Carrying out calculations

$$f(x,y) = \frac{1-\cos(x-y)}{2} + \frac{1-\cos(x+y)}{2} - (\cos x+\cos y) \cos y = f_1(x,y) = 1 - \frac{\cos(x-y)+\cos(x+y)}{2} - \cos x \cdot \cos y - \cos^2 y = f_2(x,y)$$

you got a few highlight true. All these formulas turn into true equalities when the point (0;0) is substituted, but only the last one “withstands” the point $\left(\frac{\pi}{2}; \frac{\pi}{6}\right)$. She will be faithful.

Of course, a well-prepared student must know standard formulas and use them accurately. Unfortunately, exam practice shows that errors “eventually” occur in self-control, although they are not absolute, they are very useful in such tasks.

⟦folio 44⟧

Sometimes doubt about the veracity of a story arises for reasons of symmetry. Let us assume that when factoring the polynomial

$$P(x, y, z) = (x + y + z)^3 - x^3 - y^3 - z^3$$

you got

$$3(x + y)(x + z)(y - z); \quad P_1(x, y, z)$$

then you must immediately report that you were mistaken: in the polynomial $P(x, y, z)$ the variables $x, y, z$ are equal (that is, it does not change with any permutations of the variables*):

$$P(x, y, z) = P(x, z, y) = P(z, x, y) = \dots),$$

but in the polynomial $P_1(x, y, z)$ there is no: $(P_1(x, y, z) = -P_1(x, z, y))$.

2. Equations, systems of equations

Having solved the equation, try to substitute the obtained answers into it and, if it is difficult to calculate, at least estimate whether both sides are equal. This is often useful whether or not formula testing is required to weed out extra roots. Let's say, if when solving the equation

$$\sqrt{2x - 6} + \sqrt{x + 4} = 5$$

you have obtained the roots 5 and 170, an estimate will immediately show that at $x = 170$ the left side is clearly larger than the right and the found value of the root $x = 170$ is erroneous. It is also possible to establish from general considerations that a given equation can have no more than one root. In fact, the function $f(x) = \sqrt{2x - 6} + \sqrt{x + 4}$ returns on all domains, that is, at $x \ge 3$ (explain why without calculating an arbitrary one), and due to this it can take the value 5 at most once. If you know a little about the properties of continuous monotonic functions (“Algebra and the beginnings of analysis 10”, paragraph 84), then from the fact that $f(3) = \sqrt{7} < 5$ and $f(10) = 2\sqrt{14} > 5$, we can conclude that between 3 and 10 it is necessary to find also $x_0$, which is $f(x_0) = 5$.

*) Mathematicians call polynomials (and even functions) that have these properties symmetric.

Observations of symmetry often allow one to notice an error in solving a system of equations. For example, the system

$$\begin{cases} x^2 + xy + y^2 = 7, \\ x^4 + x^2y^2 + y^4 = 21 \end{cases}$$

does not change when rearranging the unknowns and when simultaneously replacing $x$ with $-x$ and $y$ with $-y$ (check!). Therefore, if the solution you found includes the pair (2; 1) and does not include at least one of the pairs (1; 2), (-2; -1), (-1; -2), then you have lost the solution somewhere.

Similarly, one can notice that together with the solution $(x_0; y_0)$ of the system

$$\begin{cases} x + \frac{1}{x} + y + \frac{1}{y} = a, \\ x^2 + \frac{1}{x^2} + y^2 + \frac{1}{y^2} = b \end{cases}$$

it will also satisfy the pairs $(x_0; \frac{1}{y_0}), (\frac{1}{x_0}; y_0), (\frac{1}{x_0}; y_0), (\frac{1}{x_0}; \frac{1}{y_0})$ and $(\frac{1}{y_0}; \frac{1}{x_0})$.

3. Inequalities

Let solution $\sqrt{7 + x} \ge 5 - x$ be required.

"Response": [2; 9].

To check, let's start looking at the real axis, looking from “minus infinity” to “plus infinity”. First of all, note that “large” negative numbers are not included in the solution set: for them, the radical expression on the left side of our inequality is negative and the inequality is not defined (check by substituting $x = -10^2; -10$). As $x$ increases, function $7 + x$ returns and function $5 - x$ kills. Starting with $x = -7$ we enter the domain of defining inequality. Let's substitute several to calculate both parts of the values, for example $x = -6; -3; 0$. We see that with these values ​​the left side is still smaller than the right. Let's substitute the lower bound of our answer, that is, $x = 2$. Equality! As $x$ increases further, the right side kills, the left returns -

⟦folio 45⟧

therefore, further values ​​of $x$ are included in the solution set. Let us substitute the right boundary $x=9$ into the inequality. We get $4>-4$. The inequality is true, but disappointing. Why, given such a difference between the parts of the inequality, does the answer show that there is no further solution? Let's substitute a "large" positive number, for example $x=10^3$. The inequality is clearly fair! It is easy to conclude that the weight loss interval is $]9; +\infty$ [: after all, for any $x>9$ the right part is negative, and the left part is positive, and for $x>9$ the inequality is true. Our check not only detected the inequality of the answer, but also allowed us to indicate the correct answer.

(You can get [2; 9] as a set of solutions, for example, like this:

$$\sqrt{7+x} \geq 5-x; 7+x \geq (5-x)^2;$$
$$x^2-11x+18 \leq 0; 2 \leq x \leq 9.$$

To catch the error, we use a marked point that is not included in the answer and satisfies the original inequality, for example $x=18$. Already substitution into the second inequality shows that at the very first step, when squaring, we lost the roots.)

So, having received the answer, it is often advisable to “go through” the entire numerical axis: perhaps a whole interval is missed; maybe in response by including clearly unsatisfactory numbers. Be sure to substitute “large” and “small” values: it is both simple and useful. Pay special attention to the boundaries of the intervals obtained in the answer: these are, as a rule, either the boundaries of the area of ​​definition of inequality or the values ​​at which equality is achieved.

An effective and visual way of control is often graphical. If it's easy to graph both sides of an inequality, do it!

4. Geometric problems

The simplest check of a geometric formula is based on the fact that both parts must have the same dimension. You can only add quantities of the same dimension; in this case, the sum has the same dimension as the terms. The dimension of the product is equal to the sum of the dimensions of the factors, the dimension of the quotient is the difference between the dimensions of the dividend and the divisor. The constant is assigned dimension zero, length is assigned dimension 1. Area and volume have dimensions 2 and 3 corresponding, and the trionometric function has dimension zero. Due to the listed properties of dimension, it is impossible, say, such “formulas”:

$$l = \frac{a+b}{a-b}, \quad V = a^2 \cdot \frac{b}{a+c},$$
$$\sin \varphi = \frac{a^2+b^2}{S^2}, \quad S = a^2 + \frac{b}{c},$$

where $l, S, V$ are length, area and volume, $a, b, c$ are lengths. In the first three formulas, the dimensions of the left and right sides do not match (one and zero, three and two, zero and minus two); on the right side of the fourth formula, the values ​​of dimensions 2 and 0 are added.

It's just as easy to use symmetry to control. The point is that symmetry in the conditions of the problem must be followed by symmetry in the answer. For example, if the problem requires finding the distance from the point of external tangency of two circles with radii $a$ and $b$ to their common tangent, then in the formula for the exclusive distance $a$ and $b$ should be equal, that is, the formula should not change when they are rearranged. Therefore, out of three answers:

$$x = \sqrt{a^2+2b^2}, \quad x = b \left( 1 + \frac{a-b}{a+b} \right),$$
$$x = \frac{2ab}{a+b}$$

the first is clearly not suitable; you can’t immediately say anything about the second one - it should be converted to a symmetric form, which is dan in the third formula.

In order, even before solving the problem, it should be noted that the volume of a terrahedron with an equilateral base and dihedral angles at the base $\alpha, \beta, \gamma$ represent a symmetric function of $\alpha, \beta, \gamma$

⟦folio 46⟧

(defined in the footnote on p. 44) and that in the formula for the median $m_c$ of a triangle with sides $a, b, c$ only $a$ and $b$ must enter in the same way (explain why!).

You can check the answer and confirm and confirm, for example, in the given problem about the distance to the tangent, the result of the geometric estimate: the required distance is equal to the radius. This is also what the formula gives. Checking in limiting cases, when one of the variables tends to the boundary of the domain of definition, requires almost no calculations. In the problem under consideration, at $a \rightarrow 0$ the required distance should also tend to 0; the formula $x = ab/(a+b)$ shows the same thing.

To check a problem with numerical data, you need to imagine the approximate value of the answer. Say, if you want to find the length of the bisector $l_a$ of a triangle with sides $a=7, b=6, c=5$, then the answers $\sqrt{50}$ and $3/\sqrt{7}$ are the first too large, and the second too small.

In conclusion, we formulate the main operational verification techniques that we used:

1. Substitution of private values.
2. Study of border closure.
3. Observations on symmetry.
Try to master them. To do this, you are offered a number of tasks. There are several answers to each, of which only one is correct. Find him.

1. Simplify the expression $3+4\cos 2a + \cos 4a$;
   a. $4\cos^4 a$. 6. $8\cos^3 a$. 8. $8\cos^4 a$. 8. $-6\cos^4 a$.
2. Solve the equation $\sqrt{1+\log_2 x} + \sqrt{4\log_4 x-2} = 4$;

Amendment

In the article “Displacements of Space” («Kvant», 1980, No. 8) on p. 7 - in the formulation of Theorem 2 and in the last paragraph - due to the fault of the author, one movement was missed: the composition of rotation around a line and symmetry with respect to a plane perpendicular to this line.
