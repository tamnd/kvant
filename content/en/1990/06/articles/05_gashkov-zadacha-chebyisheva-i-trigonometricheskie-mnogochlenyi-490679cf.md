---
id: 1990-6-gashkov-zadacha-chebyisheva-i-trigonometricheskie-mnogochlenyi-490679cf
issue: kvant_1990_6
year: 1990
number: "6"
title: Chebyshev problem and trigonometric polynomials
authors:
  - Гашков С. Б.
rubric: osnovnye-stati
page_first: 27
page_last: 30
page_labels: 25-28
lang: en
source: kvant_digital
extraction: vision
content_sha256: a5b36646c8f1893182b5625816aefecca8444ddc6017d82ffe5cd1446606bdfe
prompt_sha256: draft-1
translated_from: content/ru/1990/06/articles/05_gashkov-zadacha-chebyisheva-i-trigonometricheskie-mnogochlenyi-490679cf.md
source_content_sha256: a5e5d5648d0aa4faf0c27f74fb3fafc39b111ac71769ffb5976862354e7f1f67
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 25⟧

---
running_head:
folio:
---

CHEBYSHEV PROBLEM
AND TRIGONOMETRIC
POLYNOMIALS

Candidate of Physical and Mathematical Sciences
S. GASHKOV

From the editor. In the previous article, we talked about polygons that least deviate from zero. In it, the properties of Chebyshev polylens were derived from the geometry of their graphs. The article we bring to your attention offers a different approach to this problem - an approach based on the study of trionometric polylens. Which is better - decide for yourself. We proceeded from the fact that it is more useful to solve one problem in several ways than to solve several problems in one...

Algebraic and trionometric polygons

A trionometric polygonal function is called

$$f(\alpha) = a_0 + a_1 \cos \alpha + a_2 \cos 2\alpha + \dots + a_n \cos n\alpha,$$

(1)

where $a_0, a_1, \dots, a_n$ are numerical coefficients. The number $n$ is called the degree, and the number $a_n$ is the leading coefficient of the trionometric polylen.

You probably have a question: why is the trionometric function (1) called “multiple”? The reason is that $f(\alpha)$ is an ordinary, algebraic polygon of the functions $\cos \alpha$. In the previous article, “Polylens that Least Deviate from Zero,” it was proven that $2\cos n\alpha$ is a polylen of the $n$th degree of $2\cos \alpha$ with leading coefficient 1. If you read that article, you know that this is easy to prove by induction; and if not, I suggest you do it yourself. In any case, for any $n$

$$\cos n\alpha = p_n(\cos \alpha),$$

where $p_n(x)$ is a polygon of the $n$th degree with the leading coefficient $2^{n-1}$:

$$\cos \alpha = x = p_1(x),$$

$$\cos 2\alpha = 2 \cos^2 \alpha - 1 = 2x^2 - 1 = p_2(x),$$

$$\cos 3\alpha = 4 \cos^3 \alpha - 3 \cos \alpha = 4x^3 - 3x = p_3(x),$$

$$\cos n\alpha = 2^{n-1}x^n + \dots = p_n(x),$$

$(x = \cos \alpha)$.

Multiplying the previous equalities by the coefficients $a_0, a_1, \dots, a_n$ and adding, we see that every trionometric polygon (1) is an algebraic polygon of the $n$th degree from $\cos \alpha$.

Let us now try to “read” equalities (2) from right to left and from bottom to top. From the last equality it follows that

$$x^n = 1/2^{n-1} \cos n\alpha + \dots,$$

(3)

where multi-relative denotes annual $x^k$ degrees, less than $n$. From the penultimate equality it follows that

$$x^{n-1} = 1/2^{n-2} \cos(n-1)\alpha + \dots,$$

(4)

where multi-relative replaces annual $x^k$ degrees, less than $n-1$. And so on. Substituting (4) and similar equalities together with a polynegative of the $n$th degree with the leading coefficient $1/2^{n-1}$.

It follows that every algebraic polygon of the $n$th degree $p_n(x)$ with the leading coefficient 1 at $x = \cos \alpha$ is a trionometric polygon of the $n$th degree with the leading coefficient $1/2^{n-1}$.

⟦folio 26⟧

---
running_head:
folio:
---

Average value
trigonometric polynomial
Consider the trigonometric polynomial $f(\alpha)$ with leading coefficient $a_n$. Let us divide its domain of definition [0; 2π] into 2n equal parts by points
$0, \pi/n, 2\pi/n, 3\pi/n, \dots, (2n-1)\pi/n$
and consider its average value at these points with intersecting signs:
$$\frac{1}{2n}(f(0) - f(\pi/n) + f(2\pi/n) - f(3\pi/n) + \dots - f(2n-1)\pi/n)$$ (5)
Lemma. This number is equal to $a_n$.
Proof. Trigonometric polynomial (1) consists of terms of the form $g_k(\alpha) = \cos k\alpha$, where $0 \leq k \leq n$. We will prove that the sum (5) for all $g_k$, except the last one, is equal to zero. If $k = 0$; then $g_0(\alpha) = 1$, so
$$g_0(0) - g_0(\pi/n) + g_0(2\pi/n) - \dots = 1 - 1 + 1 - \dots - 1 = 0.$$
Let now $0 < k < n$. Sum (5) is equal to the difference of two terms:
$$\cos(0) + \cos(2\pi/k) + \cos(4\pi/k) + \dots + \cos((2n-2)\pi/k),$$ (6₁)
$$\cos(\pi/k) + \cos(\pi/k + 2\pi/k) + \cos(\pi/k + 4\pi/k) + \dots + \cos(\pi/k + (2n-2)\pi/k).$$ (6₂)
Each of these amounts is zero. Indeed, consider two regular $n$-gons (on figure $n=6$). Let's go around the vertices of the $n$-gon in this order: $A_1, A_{1+k}, A_{1+2k}$, ... After a few steps our path will close (at figure $a$) $k=2$. Due to symmetry, the sum of vectors with a beginning at the center of the polygon and ends at offset points is zero. Therefore, the sum of their projections on the abscissa axis is also equal to zero. But this is the amount (6₁)! Similar reasoning with figure 6) - on it $k=1$ - proves that the sum (6₂) is also zero.

So, it remains to calculate the sum (5) at $f(\alpha) = a_n \cos n\alpha$. But in this case $f(\pi/k) = a \cos(\pi k) = (-1)^k a.$
Pozny's sum (5) is equal to
$$1/2n(1 - (-1) + 1 - (-1) + \dots)a_n = 1/2n \cdot 2n \cdot a_n = a_n.$$
The lemma is proven.

Solution
Chebyshev problems
All work is rewarded: we are now able to solve Chebyshev’s problem. Recall that the deviation of functions from zero on some interval is the most significant modulus on this interval. The task is to find the greatest possible deviation from zero on the segment [-1; 1] polynomial of $n$th degree with leading coefficient 1.

First of all, let us estimate the strength of the deviation from zero of the trigonometric polynomial (1). This is done like this:
$$1/2n(|f(0)| + |f(\pi/n)| + |f(2\pi/n)| + \dots + |f((2n-1)\pi/n)|) \geq 1/2n(f(0) - f(\pi/n) + f(2\pi/n) - f(3\pi/n) + \dots - f((2n-1)\pi/n)| = |a_n|.$$
Inequality means that the sum of the model is no less than the model sum; and equality is the statement of the lemma from the previous paragraph. From inequality (7) it follows that although for one $k$ the inequality $|f(\pi/k)| \geq |a_n|$ holds. Pozny

⟦folio 27⟧

---
running_head:
folio:
---

the deviation from zero of a trionometric polynomial is not less than the modulus of its leading coefficient.
Now Chebyshev’s problem can be solved “in one move.” According to what was said at the beginning of the article, the reduced polynomial of the $n$th degree $p_n(x)$, with the substitution $x = \cos \alpha$, turns into a trionometric polynomial $f(\alpha)$ with the leading coefficient $1/2^{n-1}$; Moreover, when $\alpha$ the segment [0; 2π], $x$ runs through the segment [−1; 1]. On the other hand, the deviation from zero $f(\alpha)$ is not less than its leading coefficient. Means,

deviation from zero of a reduced polynomial of $n$th degree on the interval [−1; 1] no less than $1/2^{n-1}$.
It is easy to see that the deviation from zero on the interval [−1; 1], equal to $1/2^{n-1}$, has a reduced polynomial $p_n(x)$, for which
$$p_n(\cos \alpha) = 1/2^{n-1}\cos n\alpha, \text{ т. е.}$$
$$p_n(x) = 1/2^{n-1}\cos (n\arccos x).$$
In conclusion, a few tasks.

Polynomials that deviate least from zero

(For the beginning, see p. 23)

As you agreed, the polynomials $f_n(x)$ are what we need. Indeed, empty $\alpha$ runs through the segment [0; π]. Then $n\alpha$ varies from 0 to $n\pi$, and the function $x = 2\cos \alpha$ and $f_n(x) = 2\cos n\alpha$ takes values ​​on the interval [−2; 2]. In this case, $x$ runs through this segment once, and $f_n(x) - n$ once, alternately taking $\pm 2$ with $x = \arccos \left(\frac{\pi k}{n}\right), k = 0, 1, \dots, n$. This means that the graph of the polynomial $f_n(x)$ lies in the strip $|y| \leq 2$ and contains an alternating $n+1$ point of its upper and lower boundaries. That is, $f_n(x)$ is the polynomial that least deviates from zero on the interval [−2; 2] (and the evasion is 2). These polynomials are called Chebyshev polynomials.

From the above, the necessary conclusion follows:
whatever the reduced polynomial $g(x)$ is, such a point of the segment [−2; 2], in which_module its value is not less than 2.

It would, in my opinion, be impossible to foresee such a result. After the problem of polynomials that deviate least from zero has been solved on the interval [−2; 2], it is not difficult to solve it on any other segment. To do this, it is enough to make a linear change of variable in the Chebyshev polynomials.

Exercise 3. Find the name of the deviation from zero of the reduced polynomials of the $n$th degree on the segments a) [0; 4]; b) [−1; 1].

Chebyshev polynomials certainly deserve a more detailed discussion. The story about their combinational properties already appears in «Kvant» - in No. 1 for 1982. To him I refer those who are interested in polynomials that deviate least from zero.

⟦folio 28⟧

---
running_head:
folio:
---

We have been running this section from issue to issue since our founding.
new magazine. The problems published in it are non-standard
we are, but solving them does not require knowledge beyond the scope of the school curriculum.
The most difficult tasks are marked with an asterisk. After formulating the problem, we usually indicate who proposed it to us. Of course, not all of these problems are published for the first time.
Solutions to the problem from this issue should be sent no later than August 15, 1990 to the address: 103006, Moscow K-6, st. Gorky, 32/1, «Kvant». Solutions to problems from different issues of the journal or in different subjects (mathematics and physics) are assigned in different envelopes. On the envelope, in the “To” column, write: “Problem book «Kvant» No. 6 - 90” and the numbers of the problems whose solutions you are sending, for example “M1226” or “F1233”. In the column “...sender’s address”, please write your first and last name legibly.
in. Include an envelope with your address written on it (in this envelope you will receive the result of checking the solution).
The condition of each original problem proposed for publication is assigned in a separate envelope in duplicate along with your solution to this problem (on the envelope place: “Problem book «Kvant», new problem in physics” or “...new problem in mathematics”).
At the beginning of each letter, please indicate the school number and the class in which you will study.
