---
id: 1986-10-oleynikov-irratsionalnost-i-neprivodimost-8ad956ae
issue: kvant_1986_10
year: 1986
number: "10"
title: Irrationality and irreducibility
authors:
  - Олейников В. А.
rubric: osnovnye-stati
page_first: 8
page_last: 11
page_labels: 6, 7, 9
tag: 4FKL
lang: en
source: kvant_digital
extraction: vision
content_sha256: 03c6f93dde2648e946855866440055ff8da72de3313c6ac61135573aa5f9184e
prompt_sha256: draft-1
translated_from: content/ru/1986/10/articles/03_oleynikov-irratsionalnost-i-neprivodimost-8ad956ae.md
source_content_sha256: 03c9487bca4ec10d7120eba72479ad373759aaf7442f8a26e363a24a344e19ea
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 6⟧

non-crimal fraction $\sqrt{2} = a/b$, then
$$2 = \frac{a^2}{b^2}, \quad 2b^2 = a^2.$$
It is clear that the number $a$ is divisible by 2, $a^2$ —
by 4 and therefore $b$ is by 2. So
$a/b$ - fractionating contractions.

The fraction $a/b = \sqrt{2}$ cannot be contractible and non-cratic at the same time, which means that the quantity $\sqrt{2}$ is not a fraction. This quality made $\sqrt{2}$ an unwelcome guest in the world of numbers, where harmony and order, simplicity and perfection reigned.

$\sqrt{2}$ owed its appearance to the diagonal of the unit square and unsuccessful attempts to measure it by rational segments. Bad luck greatly worried the ancient Greeks, causing ferment in their minds. Reality, expressed in a geometric manner, was truly knocking on the world of the pure and beautiful.

Many centuries passed, $\sqrt{2}$ won its place among numbers, becoming another reality - the root of the equation $x^2 - 2 = 0$, and it turned out that

the number $\sqrt{2}$ is irrational

because

the polynomial $x^2 - 2$ is irreducible.

Our story is about the connection between the irrational and irreducibility.

Irreducibility

Polynomial

$$P(x) = a_0 + a_1x + \ldots + a_nx^n$$

powers $n$ by $x$ with integer coefficients

$$a_0, a_1, \ldots, a_n; \quad a_n \neq 0$$

called inrational if it cannot be represented as a product

$$P(x) = L(x) \cdot Q(x)$$

polynomials $L(x)$ and $Q(x)$ also with integer coefficients, but degrees less than $n$. If this is possible, then $P(x)$ is called inrational.

For example, the polynomial $x^3 + x^2 + x + 1$ is reducible (it is equal to $(x+1)(x^2+1)$ - check!), and the polynomial $x^2 + 1$ is reducible (think about why).

The linear binomial $a_0 + a_1x$ provides the simplest example of an inrational polynomial. Its only root $x = -a_0/a_1$ is a rational number. But

among the roots of an inrational polynomial $n \geq 2$ cannot be rational.

⟦folio 7⟧

This property follows from a more general fact:

THEOREM. If the number a is the root of two simultaneous polynomials $P(x)$ and $Q(x)$ and one of them, say $Q(x)$, is irreducible, then the polynomial $d \cdot P(x)$ is divisible by $Q(x)$ for some integer $d \neq 0$:

$$d \cdot P(x) = L(x) \cdot Q(x).$$

This THEOPEMA is associated with the name of the famous German mathematician K. F. Gauss (1777-1855).

It will be proven on p. 10, and the above property follows from it, since a linear binomial cannot be divided by a polynomial of degree $n \geq 2$.

The opportunity opens up to obtain many new irrational numbers. They should be looked for among the roots of irreducible polynomials. Takes me to the mysterious land of irreducible polynomials.

Eisenstein's sign. If for the polynomial $P(x)$ one can specify such a prime number $p$ that the leading coefficient $a_n$ is not divisible by $p$, and all other coefficients $a_k$ are divisible by $p$, $k=0, 1, \dots, n$, but the free term $a_0$, divisible by $p$, is not divisible by $p^2$, then such a polynomial $P(x)$ is irreducible.

F. G. M. Eisenstein (1823-1852), also a German mathematician, experienced the disfavor of fate and the indifference of his contemporaries. His ideas were accepted only many years later.

Proof

Let, in contradiction to the statement, the polynomial $P(x)$ with the indicated property of coefficients be reducible and therefore decompose into the product

$$P(x) = L(x) \cdot Q(x)$$

polynomials

In the first of the written equalities, the free term $a_0$ is divided by $p$; that means either $b_0$ or $c_0$ is divisible by $p$; they cannot be divisible by $p$ at the same time, or $a_0 = b_0 c_0$ is not divisible by $p^2$.

Let $b_0$ be divisible by $p$ and let $c_0$ not be divisible. Then we move on to the second equality: $a_1$ is divided by $p$, $b_0 c_1$ is divided by $p$; so $b_1 c_0$ is also divisible by $p$ and $b_1$ is divisible by $p$...

...And so we go up to the $l+1$-th equality (at $x^l$): $a_l$ is divided by $p$, all $b_0, \dots, b_{l-1}$ are divided by $p$; then $b_l c_0$ is divisible by $p$ and therefore $b_l$ is divisible by $p$.

And now let’s move on to the last equality: this means that the leading coefficient $a_n = b_1 c_m$ is divisible by $p$, which is impossible according to the condition of the sign.

If in the first equality $c_0$ is divisible by $p$, but $b_0$ is not divisible, then, starting all over again, we go to the $m+1$th equality (at $x^{m+1}$), and then again move to the last one.

This means that the expansion $P(x) = L(x) \times Q(x)$ is impossible, and the polynomial $P(x)$ is irreducible. The sign has been set, but we are already killed

Irrational radicals

The polynomial $x^2-2$ is irreducible by Eisenstein's criterion (take $p=2$).

⟦folio 9⟧

Moreover, here too, Eisenstein’s test cannot be considered exhausted - one should only “split” $P(x)$ by changing the variable $x$.

Question about the irreducibility of a polynomial

$$P(x) = x^2 + 1$$

reduces to the Eisenstein criterion as follows. If $P(x)$ were reducible, then $P(x+1)$ would be reducible. But $P(x+1) = x^2 + 2x + 2$ is irreducible by Eisenstein’s criterion for $p=2$. The polynomials $x^4 + 1$, $x^6 + x^3 + 1$ are irreducible for the same reason. A similar transformation solves the question of the irreducibility of the polynomial

$$P(x) = x^{n-1} + x^{n-2} + \dots + 1$$

called the “circle division” polynomial.

The polynomial $P(x)$ is reducible if $n=p \cdot k$ is a composite number, since $P(x) = \frac{x^n-1}{x-1} = \frac{(x^p)^k-1}{x-1} = \frac{(x^p-1)(x^p(k-1)+x^p(k-2)+\dots+1)}{x-1} = (x^{p-1}+x^{p-2}+\dots+1) \times (x^{p(k-1)+x^p(k-2)+\dots+1})$, and irreducible if $n=p$ is a prime number.

Indeed, if $P(x)$ were reducible in this case, then $P(x+1)$ would be reducible. But

$$P(x+1) = \frac{(x+1)^p-1}{(x+1)-1} = x^{p-1} + x^{p-2} + \dots + 1$$

the numerator is divisible by $p$, but the denominator is not divisible. Additionally, the dummy term is $C_p^{p-1} = p$ and is not divisible by $p^2$. Then, according to Eisenstein’s test, $P(x+1)$ is irreducible, and therefore $P(x)$ is also irreducible.

From the proven irreducibility of $P(x)$ it follows that among the roots of the circle division equation

*) We use binomial coefficients $C_k^i$ and Newton’s binomial formula - see «Kvant», 1986, No. 1, p. 23.

$$x^{p-1} + x^{p-2} + \dots + 1 = 0$$

for any prime $p \geqslant 3$ cannot be rational.

One can prove that the equation for dividing a circle has no real roots—they are all complex numbers—and ask a more difficult question: when are these roots “not too irrational,” that is, when are they representable by different radicals (that is, they can be obtained by applying four arithmetic operations and the operation of extracting square roots to integers)? This question, in essence, was of interest to ancient Greek mathematicians, since it was equivalent to the following construction problem: for what $p$ can one construct a regular $p$-gon using a compass and a ruler?

Consistently, Gauss coped with this problem and proved*) that the roots of the equation for dividing a circle are expressed by square radicals when (and head then**)) when $p$ is a prime Fermat number, $p=3, 5, 17, 257, \dots, 2^{2k}+1, \dots$. Gauss was very proud of his discovery and even “expressed a desire for the seventeenth-gon to be immortalized on his grave.”

Other, more modest achievements of Gauss include

**Lemma on applied polynomials**

This lemma will help us give a general proof of the theorem. Polynomial

$$P(x) = a_0 + a_1x + \dots + a_nx^n$$

is called applied if its coefficients $a_0, a_1, \dots, a_n$ do not have common prime factors.

Gauss's Lemma states that

**The product of two applied polynomials is again the applied polynomial.**

This lemma makes use of many theorems of numbers and algebra. A reader who has completed the proof of Eisenstein’s test (on p. 7) will easily master the proof given below, or the names have much in common with each other.

*) The details of this event are reflected by S. G. Gindikin in “Stories about Physics and Mathematics” (M.: Nauka, 1981. - Bible Series. «Kvant», issue 14).

*) This part of the statement was proven by P. L. Vanzel (1814-1848), a tutor at the Polytechnic School in Paris.
