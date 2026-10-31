---
id: 1976-4-levin-parabola-i-neravenstva-d6e2016c
issue: kvant_1976_4
year: 1976
number: "4"
title: Parabola and inequalities
authors:
  - Левин В.
rubric: osnovnye-stati
page_first: 16
page_last: 20
page_labels: 14, 15, 16, 18
tag: 70UH
lang: en
source: kvant_digital
extraction: vision
content_sha256: e6d1775e9f7fd95f39c03e818b6f9084fb253223609e085a21d4161a9e141d22
prompt_sha256: draft-1
translated_from: content/ru/1976/04/articles/04_levin-parabola-i-neravenstva-d6e2016c.md
source_content_sha256: 8dfdce4c1d0101a47924301d5af41c652c0193f3c03324a2b61d04a02d585a8b
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 14⟧

V. Levin

Parabola and inequalities

The ancestor of all identical inequalities is the fact that the square of any real number is non-negative: $x^2 \geq 0$. This fact can also be formulated as follows: the graph of the function $y = x^2$ (parabola) does not pass below the abscissa axis (Fig. 1). The equal sign in the inequality $x^2 \geq 0$ occurs only at $x = 0$ (the parabola $y = x^2$ touches the x-axis at the origin).

In this note we will talk about how, based on this elemental inequality, more complex inequalities can be constructed.

1. Consider the quadratic trinomial

$$y = Ax^2 + 2Bx + C, \quad A \neq 0;$$

its graph is also a parabola. Let us find necessary and sufficient conditions for the inequality to be satisfied for all real values ​​of $x$

$$Ax^2 + 2Bx + C \geq 0. \quad (1)$$

These conditions are found very easily. First, it is necessary that $A$ be positive, since for $A < 0$ there are always values ​​$x$ for which inequality (1) does not depend (this is clear, of course, from the fact that for $A < 0$ the parabola either intersects the abscissa axis or everything is located below the axis). Take, for example, $x = x_0 = m + \sqrt{m^2 + m}$, where $m$ is selected

Fig. 1.

⟦folio 15⟧

Fig. 2.

$$AC = B^2, \text{ и именно при } x = -\frac{B}{A} \text{ (рис. 2 и 3).}$$

2. Let's take arbitrary real numbers

$$a_1, a_2, \dots, a_N; b_1, b_2, \dots, b_N; N \geqslant 1,$$

and some $x$, and write the following obvious inequality:

$$(a_1x + b_1)^2 + (a_2x + b_2)^2 + \dots + (a_Nx + b_N)^2 \geqslant 0. \tag{3}$$

It can be rewritten as $Ax^2 + 2Bx + C \geqslant 0,$

Where

$$A = a_1^2 + a_2^2 + \dots + a_N^2,$$

$$B = a_1b_1 + a_2b_2 + \dots + a_Nb_N,$$

$$C = b_1^2 + b_2^2 + \dots + b_N^2.$$

Let's assume that not all $a_n$ ($n = 1, 2, \dots, N$) are zero. Then we can state that $A > 0$.

Since we know that inequality (3) must hold for all real values ​​$x$, then, by virtue of condition $AC \geqslant B^2$, there must be

$$(a_1^2 + a_2^2 + \dots + a_N^2) \times (b_1^2 + b_2^2 + \dots + b_N^2) \geqslant (a_1b_1 + a_2b_2 + \dots + a_Nb_N)^2. \tag{4}$$

Obviously, this inequality is true, with an equal sign, and when $a_1 = a_2 = \dots = a_N = 0$, so we can discard the requirement that at least one $a_n$ be different from zero.

Inequality (4) is called Cauchy’s inequality (Augustin Louis Cauchy (1789–1857) - a famous French

⟦folio 16⟧

Fig. 4.

then the simplest Cauchy inequality (5) is represented as
$$|\vec{a}|^2 \cdot |\vec{b}|^2(\cos \alpha \cos \beta + \sin \alpha \sin \beta)^2 \leqslant \frac{|\vec{a}|^2 \cdot |\vec{b}|^2}{c_1^2}, \dots, \frac{|\vec{a}|^2 \cdot |\vec{b}|^2}{c_N^2}.$$
that is, $\cos^2\varphi \leqslant 1$, where $\varphi = |\alpha - \beta|$ is the angle between the vectors $\vec{a} = (a_1, a_2)$ and $\vec{b} = (b_1, b_2)$.

In the case of an arbitrary $N > 2$, inequality (K) can also be written as $\cos^2\varphi \leqslant 1$ by appropriately placing the angle $\varphi$ between two vectors $(a_1, a_2, \dots, a_N)$ and $(b_1, b_2, \dots, b_N)$ in $N$-dimensional space.

3. Cauchy's inequality has numerous applications. We will use it to derive other, somewhat more complex inequalities.

Consider two sequences: the sequence $a_1, a_2, \dots, a_N$ and the sequence $c_1, c_2, \dots, c_N$ with non-zero terms.

By inequality (K) we have
$$(a_1 + a_2 + \dots + a_N)^2 = \left(a_1 c_1 \cdot \frac{1}{c_1} + a_2 c_2 \cdot \frac{1}{c_2} + \dots + a_N c_N \cdot \frac{1}{c_N}\right)^2 \leqslant \left(a_1^2 c_1^2 + a_2^2 c_2^2 + \dots + a_N^2 c_N^2\right) \left(\frac{1}{c_1^2} + \frac{1}{c_2^2} + \dots + \frac{1}{c_N^2}\right).$$
Let's put
$$\frac{1}{c_1^2} + \frac{1}{c_2^2} + \dots + \frac{1}{c_N^2} = C_N,$$
and write inequality (6) in the form
$$(a_1 + a_2 + \dots + a_N)^2 \leqslant C_N \left(a_1^2 c_1^2 + a_2^2 c_2^2 + \dots + a_N^2 c_N^2\right).$$
(7)

The equal sign in (7) holds if and only if the sequences $a_1 c_1, a_2 c_2, \dots, a_N c_N$ and $\frac{1}{c_1}, \frac{1}{c_2}, \dots, \frac{1}{c_N}$ are proportional (it is easy to see that this is equivalent to the strongly proportional sequences $a_1, a_2, \dots, a_N$ and $\frac{1}{c_1^2}, \frac{1}{c_2^2}, \dots, \frac{1}{c_N^2}$).

The coefficient $C_N$ in inequality (7) is called the inequality constant *).

The most interesting inequalities of type (7) are those whose constants are less than a certain number $C$ for any $N$: $C_N < C$. This will be true if there is a limit

$$\lim_{N \to \infty} C_N = \lim_{N \to \infty} \left(\frac{1}{c_1^2} + \frac{1}{c_2^2} + \dots + \frac{1}{c_N^2}\right) = C,$$
that is, if an infinite series
$$\frac{1}{c_1^2} + \frac{1}{c_2^2} + \dots + \frac{1}{c_N^2} + \dots = \sum_{n=1}^{\infty} \frac{1}{c_n^2}$$
converges to the sum $C^*$.

Example. Let's put $c_n = n$, $n = 1, 2, \dots, N$.

Then inequality (7) will take the form $(a_1 + a_2 + \dots + a_N)^2 \leqslant C_N \left(a_1^2 + 2^2 a_2^2 + 3^2 a_3^2 + \dots + N^2 a_N^2\right)$ (8)
with constant
$$C_N = 1 + \frac{1}{2^2} + \dots + \frac{1}{N^2}.$$

*) A constant because $C_N$ is the same for all sequences $a_1, a_2, \dots, a_N$.

**) On limits, see the article by M. Gerver “20 problems on limits”, “Quant”, 1974, No. 3; about infinite series - an article by the same author “From changing the places of terms ...”, “Quant”, 1974, No. 9.

⟦folio 18⟧

where $\alpha_n$ are the values ​​of the angle between the segments $OM_{n-1}$ and $OM_n$, $n = 1, 2, \dots, N$.
Thus, we can write the equality
$$t = \sqrt{t^2 + (n-1)^2} \quad \sqrt{t^2 + n^2} \sin \alpha_n$$
from which
$$\sin \alpha_n = \frac{t}{\sqrt{t^2 + (n-1)^2} \sqrt{t^2 + n^2}} > \frac{t}{t^2 + n^2},$$
that is
$$\frac{t}{t^2 + n^2} < \sin \alpha_n, n = 1, 2, \dots, N.$$
Then
$$C_N = \frac{t}{t^2 + 1} + \frac{t}{t^2 + 2^2} + \dots$$
$$\dots + \frac{t}{t^2 + N^2} < \alpha_1 + \alpha_2 + \dots$$
$$\dots + \alpha_N < \frac{\pi}{2},$$
and we get inequality
$$(a_1 + a_2 + \dots + a_N)^2 < \frac{\pi}{2} \left( tP + \frac{1}{t} Q \right),$$
valid for any positive value of $t$.

Let's put $t = \sqrt{\frac{Q}{P}}$; with this choice of $tP + \frac{1}{t} Q = 2\sqrt{PQ}$, and we obtain Carlson’s inequality which is usually written in the form
$$(a_1 + a_2 + \dots + a_N)^4 < \pi^2 (a_1^2 + a_2^2 + \dots + a_N^2) (a_1^2 + 2^2 a_2^2 + \dots + N^2 a_N^2).$$

This inequality is valid for any $N \geqslant 1$; it can be extended to infinite series. In this inequality CONSTANTA $\pi^2$ —

*) The derivation of Carlson's inequality presented here (except for the elementary estimate $C_N$) belongs to the famous English mathematician Godfrey Harold Hardy (1877-1947).

accurate, but we cannot provide a simple proof of this fact.

The accuracy of the resulting constant $\pi^2$ in Carlon’s inequality means that the above elementary estimate $C_N$ in terms of angles $\alpha_n$ is not too rough.

Carlon's inequality has numerous generalizations. We present only two of them without proof (the sign $\Sigma$ means summation over $n$ from 1 to $N$ or an infinite series, that is, summation over $n$ from 1 to $\infty$):
$$(\Sigma a_n)^6 < 54 (\Sigma a_n^2) (\Sigma na^2) (\Sigma n^2 a_n^2),$$
$$(\Sigma a_n)^15 < 300 000 (\Sigma a_n^3) \times (\Sigma na^3) (\Sigma n^2 a_n^3) (\Sigma n^4 a_n^3).$$

In these inequalities, CONSTANTS 54 and, accordingly, 300,000 are exact. In practice
1. Let
$$a_1^2 + a_2^2 + \dots + a_n^2 = 1$$
$$b_1^2 + b_2^2 + \dots + b_n^2 = 1.$$
Within what limits is the meaning of the expression
$$a_1 b_1 + a_2 b_2 + \dots + a_n b_n?$$
2. Prove that for any positive $a_1, a_2, \dots, a_n$
$$(a_1 + a_2 + a_3 + \dots + a_k)^2 \leqslant k (a_1^2 + a_2^2 + \dots + a_k^2).$$
When is equality observed?
4. Prove that for non-negative $a_1, \dots, a_k, b_1, \dots, b_k$:
$$\sqrt{a_1 b_1} + \sqrt{a_2 b_2} + \dots + \sqrt{a_k b_k} \leqslant \sqrt{a_1 + a_2 + \dots + a_k} \times \sqrt{b_1 + b_2 + \dots + b_k}.$$
5. Hölder's inequality.
Let $p > 1$ and $\frac{1}{p} + \frac{1}{q} = 1$ ($p$ and $q$ be rational positive numbers). Prove that
$$a_1 b_1 + a_2 b_2 + \dots + a_k b_k \leqslant \left( a_1^p + a_2^p + \dots + a_k^p \right)^{\frac{1}{p}} \times \left( b_1^q + b_2^q + \dots + b_k^q \right)^{\frac{1}{q}}.$$
