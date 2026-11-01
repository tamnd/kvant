---
id: 1987-10-gutenmaher-osnovnyie-teoremyi-0498e251
issue: kvant_1987_10
year: 1987
number: "10"
title: Basic theorems
authors:
  - Гутенмахер В. Л.
rubric: shkola-v-kvante
rubric_sub: Школа в «Кванте»
page_first: 38
page_last: 40
page_labels: 36-38
tag: 561V
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7b8c28b721fd92804eb6dd5c77bd276b4ef64e8f8e5f014bc9f7f70b6c0658fa
prompt_sha256: draft-1
translated_from: content/ru/1987/10/articles/14_gutenmaher-osnovnyie-teoremyi-0498e251.md
source_content_sha256: 6072344ad0900278303c5525c7d2d7e109c480d673af44f02b5ef71b23cc2f24
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 36⟧

Basic theorems

Candidate of Physical and Mathematical Sciences
V. L. GUTENMACHER

Our goal is to talk about the three main theorems of the three great A: Arithmetic, Algebra, Analysis. Anyone who is even slightly interested in mathematics should know these theorems. The first is about decomposing numbers into prime factors, the second is about decomposing polynomials into irreducible polynomials, the third is about calculating area.

We start with the fundamental theorem of algebra: Rene Descartes wrote about it in 1637 - exactly 350 years ago - in his book Geometry.
This book has a chapter on equations; it begins with these words:

“Know that any equation can have as many roots as the degree of the equation; or the variability of two equations $x-2=0$ and $x-3=0$, then we get an equation of the second degree: $x^2-5x+6=0$, which has roots 2 and 3. If this equation, in turn, is multiplied by $x-4=0$, we get an equation of the third degree $x^3-9x^2+26x-24=0$ with thirds 2, 3 and 4.”

In the 8th grade algebra course, it is proven that a polynomial of the second degree $x^2+px+q$, having roots $x_1$ and $x_2$, is represented as a product of polynomials of the first degree:

$$x^2+px+q=(x-x_1)(x-x_2).$$

Examples of decomposition of a square trilen into a product:

$$x^2-x-2=(x+1)(x-2);$$
$$x^2-2x+1=(x-1)^2;$$
$$x^2-2=(x-\sqrt{2})(x+\sqrt{2});$$
$$x^2+x-1=(x+1/2-\sqrt{5}/2)(x+1/2+\sqrt{5}/2).$$

However, it follows that a square trilen has no roots and cannot be decomposed into such a product. As for polynomials of a higher degree, the theorem also holds for them:

Any polynomial of the form $x^n+a_{n-1}x^{n-1}+a_{n-2}x^{n-2}+\ldots+a_0$ can be decomposed into the product of polynomials of the form $x-a$ and polynomials of the second degree of the form $x^2+px+q$, which have no roots; Moreover, this expansion is unique: two such expansions differ only in the order of the factors.

⟦folio 37⟧

Examples of factoring polynomials:
$$x^3 + 1 = (x + 1)(x^2 - x + 1) \quad - 1 \text{ корень};$$
$$x^3 - 6x^2 + 11x - 6 = (x - 1)(x - 2)(x - 3) \quad - 3 \text{ корня};$$
$$x^3 - 3x^2 + 3x - 1 = (x - 1)^3 \quad - 1 \text{ корень};$$
$$x^4 - 1 = (x^2 + 1)(x - 1)(x + 1) \quad - 2 \text{ корня};$$
$$x^4 + 1 = (x^2 - \sqrt{2x} + 1)(x^2 + \sqrt{2x} + 1) \quad - 0 \text{ корней}.$$

From this theorem it follows that a polynomial of degree $n$ can have at most $n$ roots; there will be exactly $n$ roots if it can be decomposed into a product of $n$ different polynomials of the form $x-a$. A polynomial can have nominal roots due to the fact that some such polynomials are repeated (in this case multiple roots arise), and due to the fact that some polynomials are square trinomials that have no roots.

This theorem will take a much more studied form if we introduce the use of a number complexion, that is, an expression of the form $a - b\sqrt{-1}$, where $(a; b)$ is a pair of real numbers. Then any square trinomial (with real or complex coefficients) has two complex roots and can be decomposed into a polynomial of the first degree.

Examples of expansion of quadratic trinomials with complex roots:
$$x^2 + 1 = (x + \sqrt{-1})(x - \sqrt{-1});$$
$$x^4 - 4x + 3 = (x - 1)^2(x + 1 - \sqrt{-2}) \times (x + 1 + \sqrt{-2}).$$

Thanks to this, the previously formulated theorem takes the following form:

Any polynomial of the form $x^n + \alpha_{n-1}x^{n-1} + \alpha_{n-2}x^{n-2} + \dots + \alpha_0$ (ede $\alpha_{n-1}, \alpha_{n-2}, \dots, \alpha_0$ are complex numbers) is represented as a product of $n$ complices $(x - \beta_1)(x - \beta_2) \dots (x - \beta_n)$, and $\beta_1, \beta_2, \dots, \beta_n$ are complex numbers, and such a representation is unique up to the order of complices.

This is the fundamental theorem of algebra.

* * *

The fundamental theorem of arithmetic is akin to the fundamental theorem of algebra:

Every positive integer greater than one can be represented as a product of prime numbers. Moreover, two such decompositions can differ only in the order of the complicates.

Examples of factoring numbers into prime factors:
$$400 = 2^4 \cdot 5^2; \quad 1001 = 7 \cdot 11 \cdot 13;$$
$$290 981 = 43 \cdot 67 \cdot 101; \quad 1987 = 1987.$$

We actually use this theorem, starting from elementary school, both when reducing fractions and when reducing them to the most general value.

Most often we use the following statement, which, as is easy to understand, is equivalent to the fundamental theorem of arithmetic: if the product of numbers of numbers is divisible by some prime number, then at least one of the factors is divisible by this prime number.

So, both basic theorems - arithmetic and algebra - concern the issue of decomposition into a product of indecomposables. The goal is that numbers are decomposed into the product of prime numbers, and polynomials are decomposed into the product of, as they say, non-conducting polynomials. Both theorems state that such a decomposition is unique.

A rigorous proof of the fundamental theorem of algebra was given in 1799 by the great German mathematician K. F. Gauss (1777-1855); In 1801, he formulated and proved the fundamental theorem of arithmetic *).

The statement of the fundamental theorem of arithmetic is completely clear and has been known since ancient times, but it was Gauss who understood how important the statement about the uniqueness of factorization is. It turns out that it is possible to have numerical systems in which the analysis of the fundamental theorem of arithmetic ceases to be true. Without dwelling on this in detail, we will only give the most famous example - systems of numbers of the form $a + b\sqrt{-5}$, where $(a; b)$ is a pair of numbers of numbers (which add and multiply according to the same rules as complements). In this system, for example, $21 = 3 \cdot 7 = (4 + \sqrt{-5})(4 - \sqrt{-5})$. We will not discuss here why the numbers 3, 7, 4 + \sqrt{-5}, 4 - \sqrt{-5} are prime in this number system. The interested reader can find the answer in the wonderful book by G. Rademacher and O. Teplitz “Numbers and Figures” - M.: “Fizmatgiz”, 1962.

However, one should not think that in any number systems of the form $a + b\sqrt{d}$

*) For the proof of the fundamental theorem of arithmetic, see, for example, «Kvant», 1987, No. 4, p. 12; proof of the main theorem of algebra - in «Kvant», 1980, No. 2, p. 17; 1982, no. 4, p. 3.

⟦folio 38⟧

(a, b are integers, d is a fixed integer) there is no unique factorization into prime factors. An important example of a “good” number system is the so-called Gaussian numbers, i.e. numbers of the form $a+b\sqrt{-1}$, where $a$ and $b$ are integers. For them, the analysis of the fundamental theorem of arithmetic takes place.

In formulating this analysis, we must take into account the presence of so-called invertible numbers. A number (Gaussian or ordinary) is called inverse if there exists another (possibly the same) number such that the product of these two numbers is equal to 1. Among integers, the numbers 1 and - 1 are invertible; among polynomials, polynomials of “degree zero” are invertible - numbers different from zero; among Gaussian numbers - the numbers 1, - 1, $\sqrt{-1}$ and - $\sqrt{-1}$. In the expansion of $q=p_1\dots p_n$ into simple polynomials, one can multiply, say, $p_1$ and $p_2$ by numbers whose product is 1, to obtain another expansion. This forces us not to distinguish between expansions obtained from each other by multiplying components by reciprocals. In this case, both $q$ and $p_1$, ..., $p_n$ should be considered non-reverse. In formulating the fundamental theorem of arithmetic, we avoided these reservations by assuming that all numbers are greater than 1; in the formulation of the fundamental theorem of algebra - assuming that the leading coefficients of the polynomials are equal to 1.

* * *

While the fundamental theorems of algebra and arithmetic are related, as we have seen, to each other, the fundamental theorem of analysis departs quite far from them. This is the Newton-Leibniz theorem included in the 10th grade school mathematics course.

This theorem is replaced by the fact that it allows one to find areas of curved funcures. It produces a huge amount of typing also because it links together two seemingly completely different geometric problems: the problem of checking tangents (derivatives) and the problem of finding areas (interrals). The idea that these problems should be mutually inverse was first replaced by Newton's teacher, the English mathematician Isaac Barruu. But this connection was first obtained in the form of a formula by Newton and, independently of him, by Leibniz.

The Newton–Leibniz theorema states, in particular, that if a continuous positive function $f$ defined on the same interval (or, as they say, the function $F$ is an intransform of the function $f$), then the area $S$ under its graph is found by the formula

$$S = \int_a^b f(x)dx = F(b) - F(a) \text{ (см. рис. 1)}.$$

For example, the area of ​​the “parabolic stand” (Fig. 2) can be found using this formula: the function $f(x) = x^2$ is the derivative of the function $F(x) = x^3/3$ and, therefore, the area of ​​interest to us is equal to

$$\int_0^1 x^2dx = \frac{1}{3} - \frac{0}{3} = \frac{1}{3}.$$

This area was first calculated by Archimedes, without knowing anything, of course, about the Newton-Leibniz formula. (Interestingly, Archimedes solved this problem in different contexts at least three times, without realizing that he was solving the same problem.)

The problem of finding a nontransformer for a given function turned out to be an important analytical problem. For rational functions, it is related to the fundamental theorem of algebra: an untransformed fractional-rational function can always be expressed in terms of elementary functions (including logarithm and arcgent), but to do this you need to know the decomposition of the denominator into linear and square factors.
