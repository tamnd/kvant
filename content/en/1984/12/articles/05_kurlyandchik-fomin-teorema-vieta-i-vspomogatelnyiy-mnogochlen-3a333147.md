---
id: 1984-12-kurlyandchik-fomin-teorema-vieta-i-vspomogatelnyiy-mnogochlen-3a333147
issue: kvant_1984_12
year: 1984
number: "12"
title: Vieta's theorem and auxiliary polynomial
authors:
  - Курляндчик Л. Д.
  - Фомин С. В.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 16
page_last: 17
page_labels: 14-15
tag: A6YU
lang: en
source: kvant_digital
extraction: vision
content_sha256: a16a2fb6f680f0eeb0f16eed0186e8e210690e9b690b540d457480403d0a7998
prompt_sha256: draft-1
translated_from: content/ru/1984/12/articles/05_kurlyandchik-fomin-teorema-vieta-i-vspomogatelnyiy-mnogochlen-3a333147.md
source_content_sha256: b605927b70c7d486e9ef7bf98e70b0a56601b5e1f92c63f9e79ce2f3ca3f89d0
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 14⟧

Vieta's Theorema and auxiliary polynomial

L. D. KURLYANDCHIK,
Candidate of Physical and Mathematical Sciences
S. V. FOMIN

Most problems, one way or another, boil down to finding the roots of algebraic equations. But there are times—and this will be discussed in our country—that to solve a problem, it is useful, on the contrary, to construct a polynomial whose roots are given, known numbers. The technique associated with the introduction of an auxiliary polynomial allows us to solve several completely different-looking problems. Their averages are problem M879 and M882 from Problem «Kvant» and one of the problems from the last international olympiad.

Let $u$ and $v$ be two real numbers. How to construct a quadratic trinomial whose roots are $u$ and $v$? The easiest way is to consider the polynomial
$$P(t)=(t-u)(t-v)=t^2+pt+q.$$
Its coefficients are:
$$p=-(u+v), q=uv,$$
(1) that is, the sum (with a minus sign) and the product of the original numbers. Formulas (1) are called Vieta formulas. Two theorems from a school textbook are associated with it:
if the quadratic equation $t^2+pt+q=0$ has roots $u$ and $v$, then equalities (1) are satisfied (Vieta’s theorem);
the numbers $u$ and $v$ are the roots of the quadratic equation $t^2-(u+v)t+uv=0$ (converse theorem).
Let us give several examples of the application of the inverse Vieta theorem. Let's start with a very simple task.
Problem 1. Compose a quadratic equation with integer coefficients whose root is the number $2+\sqrt{3}$.
The solution to this problem, like many others, can be based on the fact that a quadratic equation with “conjugate” roots $a+b\sqrt{d}$ and $a-b\sqrt{d}$ (where $a, b$ and $d$ are integers) has

integer coefficients*). This fact, of course, immediately follows from Vieta’s formulas (1).

So, the original equation has roots $t_1=2+\sqrt{3}$ and $t_2=2-\sqrt{3}$, so its coefficients are equal: $p=-(t_1+t_2)=-4$, $q=t_1t_2=1$.

Answer: $t^2-4t+1=0$.

Problem 2. Is the number $t_1=\sqrt{37}-\sqrt{20}$ a solution to the inequality $t^2+9t-17>0$?

Solution. Let's create a quadratic equation whose roots are the numbers $t_1$ and $t_2=-\sqrt{37}-\sqrt{20}$:
$$t^2+2\sqrt{20}t-17=0.$$
Since $2\sqrt{20}=\sqrt{80}<9$, the inequality $t_1^2+9t_1-17>t_1^2+2\sqrt{20}t_1-17=0$ is valid.

Answer: the number $t_1$ is the solution to this inequality.

Calculating the value of functions at a given point is often simplified if you first construct a polynomial that vanishes at this point. Here's a typical example.

Problem 3. Calculate $u^4-5u^3+6u^2-5u$ if $u=2+\sqrt{3}$.

Solution. Let's remember the result of problem 1: $u^2-4u+1=0$ or $u^2=4u-1$. Using this relation, we express it linearly in terms of $u$ powers $u^3$ and $u^4$:
$$u^3=u^2\cdot u=(4u-1)u=4u^2-u=4(4u-1)-u=15u-4,$$
$$u^4=u^3\cdot u=(15u-4)u=15u^2-4u=15(4u-1)-4u=56u-15.$$
Hence $u^4-5u^3+6u^2-5u=56u-15-5(15u-4)+6(4u-1)-5u=-1$.

Answer: -1.

Operating in the same way as in the above solution, the value of any polynomial with integer coefficients at the point $u=a+b\sqrt{d}$ can be represented as $ku+l$ ($a, b, d, k, l$ are integers).
Problem 4. Prove that the number $(7+\sqrt{48})^{13}+(7-\sqrt{48})^{13}$ is an integer and divisible by 14.

Solution. The numbers $u=7+\sqrt{48}$ and $v=7-\sqrt{48}$ are the roots of the square trinomial $t^2-14t+1$. Using formulas $u^2=14u-1$ and $v^2=14v-1$, we obtain a “recurrence relation” for the value $a_n=u^n+v^n$:

* (The reader will find many beautiful examples related to this idea in N. Vaguten’s article “Conjugate Numbers” (Kvant, 1980, No. 2, p. 26).

⟦folio 15⟧

$$a_0 = 2$$
$$a_1 = u + v = 14$$
$$a_2 = u^2 + v^2 = (14u - 1) + (14v - 1) = 14a_1 - a_0$$
$$a_3 = u^3 + v^3 = u(14u - 1) + v(14v - 1) = 14a_2 - a_1$$
$$a_n = u^n + v^n = u^{n-2}(14u - 1) + v^{n-2}(14v - 1) = 14a_{n-1} - a_{n-2}.$$

From these relations it follows that all numbers $a_n$ are integers. In addition, if $n$ is odd, then $a_n$ is divisible by 14. This statement can be proven by induction: if $a_{n-2}$ is divisible by 14, then $a_n$ is divisible by 14.

Problem 5. Find $u^8 + \frac{1}{u^8}$ if $u = \sqrt{2} + 1$.

Vieta formulas, similar to formulas (1) for a quadratic trinomial, can also be written for a polynomial of the $n$th degree

$$P(t) = (t - x_1)(t - x_2) \dots (t - x_n) = t^n + a_1 t^{n-1} + a_2 t^{n-2} + \dots + a_n$$

with roots $x_1, \dots, x_n$. To do this, you need to open the brackets, bring similar terms and equate the coefficients at the same powers of $t$ on the left and right sides.

Let us write these formulas explicitly for the third degree polynomial

$$P(t) = (t - x)(t - y)(t - z) = t^3 + pt^2 + qt + r$$

with roots $x, y$ and $z$:

$$p = -x - y - z$$
$$q = xy + yz + zx$$
$$r = -xyz$$

Now let's move on to the most interesting examples of using the auxiliary polynomial - they are associated precisely with the case when the polynomial is constructed from several (at least three) roots.

Problem 6. The numbers $x, y, z$ satisfy the relations:

$$x + y + z = a, \frac{1}{x} + \frac{1}{y} + \frac{1}{z} = \frac{1}{a}.$$

Prove that at least one of these numbers is equal to $a$.

Solution. Let us accept formulas (2). In our case $p = -a$, $q = xyz/a = -r/a$. That's why

$$P(t) = t^3 - at^2 - \frac{r}{a} t + r = (t - a)\left(t^2 - \frac{r}{a}\right).$$

Therefore, the number $a$ is the root of the polynomial $P(t)$ and therefore coincides with one of the numbers $x, y, z$.

Problem 7. (M882) The sum of three integers $u, v$ and $w$ is zero. Prove that the number $2u^4 + 2v^4 + 2w^4$ is the square of an integer.

Solution. Let $P(t) = t^3 + pt^2 + qt + r$ be a polynomial whose roots are the numbers $u, v$ and $w$. By Vieta's theorem, $p = -(u + v + w) = 0$. We have:

$$u^3 + qu + r = 0$$
$$v^3 + qv + r = 0$$
$$w^3 + qw + r = 0.$$

To obtain an expression that functions in the conditions, we multiply these equations by $2u, 2v$ and $2w$, respectively, and add:

$$2u^4 + 2v^4 + 2w^4 + 2q(u^2 + v^2 + w^2) = 0$$

(we use what $u + v + w = 0$). But $u^2 + v^2 + w^2 = (u + v + w)^2 - 2q = -2q$, therefore $2u^4 + 2v^4 + 2w^4 = (2q)^2$.

The previously included problem is solved in a similar way by the definition

$$x^3 + px^2 + qx + r = 0$$
$$y^3 + py^2 + qy + r = 0$$
$$z^3 + pz^2 + qz + r = 0$$,

and then we will use Vieta’s formulas (2) and the derivation already encountered in the previous problem

$$x^2 + y^2 + z^2 = (x + y + z)^2 - 2(xy + yz + zx) = p^2 - 2q.$$

We get

$$x^3 + y^3 + z^3 + p(p^2 - 2q) - qp + 3r = 0,$$

where

$$x^3 + y^3 + z^3 - 3xyz = -p(p^2 - 3q) = (x + y + z)(x^2 + y^2 + z^2 - xy - yz - zx)$$.

Comment. The expression $x^2 + y^2 + z^2 - xy - yz - zx$ is non-negative (since $(x - y)^2 + (y - z)^2 + (z - x)^2 \geq 0)$. Therefore, from the proven fact it follows the inequality

$$\frac{a + b + c}{3} \geq \sqrt[3]{abc}$$

(3)

for the arithmetic mean and geometric mean of three non-negative numbers: it is enough to put $x = \sqrt[3]{a}$, $y = \sqrt[3]{b}$, $z = \sqrt[3]{c}$ in this definition.

Let's now see how we can use the auxiliary polynomial when solving a system of equations.

Problem 9. Solve the system

$$\begin{cases} x + y + z = 2 \\ x^2 + y^2 + z^2 = 14 \\ x^3 + y^3 + z^3 = 20. \end{cases}$$

Solution. Following our method, we introduce the polynomial

$$P(t) = (t - x)(t - y)(t - z) = t^3 + pt^2 + qt + r.$$

By Vieta's theorem

$$p = -(x + y + z) = -2$$
$$q = xy + yz + zx = \frac{(x + y + z)^2 - (x^2 + y^2 + z^2)}{2} = -5.$$

To find the coefficient $r$, multiply the system equations by $q$, $p$ and $1$, respectively, and add them. Since $P(x) = P(y) = P(z) = 0$, we get:

$$-3r = 2q + 14p + 20 = -10 - 28 + 20 = -18.$$

So, $P(t) = t^3 - 2t^2 - 5t + 6$. This is a polynomial with integer coefficients, and its leading coefficient is 1. Therefore, any integer coefficient equal to $P(t)$ must be a divisor of a free number. In this case, all three roots are integers (and the divisor of the number 6 is 1, -2, and 3$^*$). Thus, $\{x, y, z\} = \{1, -2, 3\}$.

$\cdot$) In principle, it is enough to resolve - or find - at least one root, and then use the polynomial expansion. We use this in more detail in the article by S. V. Fomin “Decomposition into a polynomial” (Kvant, 1983, No. 7, p. 23).
