---
id: 1980-2-ashmanov-chisla-i-mnogochlenyi-e5b4fad1
issue: kvant_1980_2
year: 1980
number: "2"
title: Numbers and polynomials
authors:
  - Ашманов С. А.
rubric: osnovnye-stati
page_first: 19
page_last: 23
page_labels: 17, 19, 20, 21
tag: KH6V
lang: en
source: kvant_digital
extraction: vision
content_sha256: 2237d24bc3de6864311138ecb61896bf47fc08d83f99c5e54f12884caaa56605
prompt_sha256: draft-1
translated_from: content/ru/1980/02/articles/05_ashmanov-chisla-i-mnogochlenyi-e5b4fad1.md
source_content_sha256: 52072e873ee40b6b3a95efc32d60aa9b0f3eb93d7174a814878e8019e7324a1a
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 17⟧

S. Ashmanov

Numbers and polynomials

In this article we will talk about how complex numbers and polynomials are intertwined in mathematics.

When numbers are not enough

There are different numbers: positive and negative, rational and irrational, algebraic and transcendental. The history of the emergence of each new class of spring numbers is respectful and even dramatic.

Such an inculcating object for us as negative numbers has been the subject of debate throughout the century. They were known in ancient times in India, China and Babylon, but disputes about the nature of negative numbers and their right to exist were conducted back in the time of Newton at the end of the 17th century.

The reason for introducing negative numbers was, apparently, the difficulty of solving an equation of the form $x+a=b$ for any positive numbers $a$ and $b$.

Introducing rational numbers should arise to solve an equation of the form $ax=b$, where $a$ and $b$ are integers ($a \neq 0$).

After the rationality of the number $\sqrt{2}$ was proven in Ancient Greece, that is, the impossibility of solving the equation $x^2=2$, having only rational numbers at its disposal, mankind was again faced with the need to expand its numerical reserve.

You can expand the set of rational numbers so that the equation $x^2=2$ in a new, wider set has a root, not only as it is done in the textbook, but also as follows:

Let's enter the symbol $j$ and put $j^2=2$. We will consider expressions of the form $a+bj$, where $a$ and $b$ are arbitrary rational numbers.

Let’s formulate rules for action on our candidates for new numbers:

$$(a_1+b_1j) + (a_2+b_2j) = (a_1+a_2) + (b_1+b_2)j;$$

$$(a_1+b_1j) (a_2+b_2j) = (a_1a_2+2b_1b_2) + (a_1b_2+a_2b_1)j.$$

⟦folio 19⟧

If you add i

Let's try, just as we did with the field of rational numbers and the equation $x^2=2$, to expand the field R of real numbers by adding to it the “root” of the equation $x^2+1=0$.

Let $i$ be a symbol whose only property is that it is the root of the equation $x^2+1=0$; that is, $i^2=-1$.

Consider expressions of the form $a+bi$, where $a$ and $b$ are arbitrary real numbers; Let's call them complex numbers. Let us introduce the rules for operating on complex numbers:

$$\begin{align*}
(a_1+b_1i) + (a_2+b_2i) &= (a_1+a_2) + (b_1+b_2)i; \\
(a_1+b_1i) (a_2+b_2i) &= (a_1a_2-a_1b_2) + (b_1b_2+a_2b_1i).
\end{align*}$$

The reader can easily prove that the set of complexes of numbers with addition and multiplication so defined is a field.

It is easy to verify that number complexes of the form $a+0i$ behave in the same way as real numbers. Therefore, the real number $a$ and the complex number $a+0i$ can be identified with each other. This means that we can consider that we have expanded the field of real numbers to the field of complexes of numbers. In this broader equation field, $x^2+1=0$ has a root: $i^2+1=0$ (and even two roots: $(-i)^2+1=0)$.

But what have we added? Just because the equation $x^2+1=0$ has taken root? It turns out that we have added more cities. There is a replacement

Fundamental theorem of algebra

Any polynomial $P(x) = a_nx^n + a_{n-1}x^{n-1} + \dots + a_2x^2 + a_1x + a_0$ of non-zero degree has at least one root in polynumber complexes of numbers (which, of course, can also be a real number).

The first attempt to prove this theorem was made by d'Alembert in 1746. A rigorous proof was given by Gauss in 1799.

It turns out that the fundamental theorem of algebra is true not only for polynomials

addition: 1. commutative, 2. associative, 3. there is a zero, 4. for each element of M there is an opposite;

multiplication: 5. commutative, 6. associative, 7. there is one, 8. for every non-zero element of M there is an inverse, 9. distributive with respect to addition.

with real coefficients, but also for polynomials with complex coefficients (or, as is commonly said, for polynomials over a field of complex numbers).

The Fundamental Theorem of Algebra allows us to give an elegant answer to the question of how many roots an arbitrary polynomial of degree $n$ has, if we consider polynomials over the field of complexes of numbers.

To formulate this answer, we need the concept of “multiplicity” (the root of a polynomial), and this concept is defined through the concept of “one polynomial is divided by another.” A polynomial $P_1(x)$ is said to be divisible by a polynomial $P_2(x)$ if there is a polynomial $q(x)$ such that $P_1(x) = q(x) \cdot P_2(x)$.

The concept is “divided” and “root” Theorem 1. The number a is a toed and only a toed is the root of the polynomial $P(x)$, the cord $P(x)$ is divisible by $x$-a.

Theorem 1 is not difficult to prove on your own. (At the cauldron and e. Divide with a “corner”.).

It may be that the polynomial $P(x)$ of degree $n$ will be divisible not only by $x$-a, but also by some degree $x$-a. According to these conditions, a is called a $k$-fold root of the polynomial $P(x)$ if $P(x)$ is divisible by $(x-a)^k$ but not divisible by $(x-a)^{k+1}$. (For example, the number 1 is the double root of the polynomial

$$P(x) = x^3 + x^2 - 5x + 3 = (x-1)^2(x+3).$$

Teler can easily be proven

Theorem 2. Every polynomial $P(x)$ of degree $n$ (with real or complex coefficients) has in its field complexes of exactly $n$ roots (among which, of course, there can be real numbers), if each root is counted only once, what is its multiplicity.

Proof. By the fundamental theorem of algebra, the polynomial $P(x)$ has complexes of exactly $n$ roots in the field. Let us assume that $a_1$ is the root of the polynomial $P(x)$. By Theorem 1 $P(x) = (x-a_1)q(x)$, where $q(x)$ is a polynomial of degree $n-1$. (Further on, the coefficients of the polynomial $P(x)$ are real numbers; the polynomial $q(x)$ will be if $a_1$ is a complex root and has complex coefficients.)

Let us further apply the same reasoning to the polynomial $q(x)$. By the fundamental theorem of algebra, there is a root $a_2$ of the polynomial $q(x)$, so that $q(x) = (x-a_2)h(x)$, where $h(x)$ is a polynomial whose degree is already $n-2$. Repeating this reasoning $n-1$ times (applying, of course, when

⟦folio 20⟧

strict presentation of the principles of mathematical induction), we will eventually arrive at the decomposition

$$P(x) = a_n (x - a_1) (x - a_2) \dots (x - a_n),$$

where $a_n$ is the coefficient of the highest degree $x^n$ of the polynomial $P(x)$.

From identity (*) it follows not only that the complex numbers $a_1, a_2, \dots, a_n$ (their averages may be equal!) are the roots of the polynomial $P(x)$, but also that this polynomial has no other roots. Indeed, if the number $\beta$ is a polynomial of the polynomial $P(x)$, then

$$P(\beta) = a_n (\beta - a_1) (\beta - a_2) \dots (\beta - a_n).$$

But the product of complex numbers is equal to zero if and only if one of the components is equal to zero (this is proof). Therefore, one of the components is equal to zero, that is, $\beta = a_i$. This completes the proof of Theorem 2.

As science developed, it became clear that it is impossible to do without complex numbers in the most “real” matters. When airplanes appeared, a theory of air flow around an airplane wing was required. It turned out that the most natural language for describing such a process, i.e., the language of aerodynamics, is the theory of functions of a complex variable! So when you see a modern airliner, know that it was made by a lot of designers, engineers, workers and... complex numbers. The same can be said about the science of water flowing around a ship - hydrodynamics. Do you know another toy - Vanka-insert? You put Vanka to sleep, and he immediately jumps up - he has the most stable position when he stands. The mathematical theory of stability deals with similar questions for cities of more complex mechanical, electrical and other systems. And it turned out that the answer to whether a system is stable lies in the properties of complex numbers, which are the roots of a certain polynomial characterizing the system under consideration.

Modern aircraft and Vanka-insert - this is the range of action of complex numbers. We have given only a few areas of their application, since all of the above are impossible. Here are the minimum numbers for you!

We will now show, by way of example, how complex numbers have helped answer some important questions about polynomials with real coefficients.

Polynomials similar to prime numbers

Consider the set of all polynomials of arbitrary degree in the variable $x$. You can add the variable elements of this polynomial, that is, polynomials, and you know how to decompose them into polynomials.

This is very similar to what you can do with natural numbers. You can also factor natural numbers into simple polynomials. You probably know that this can always be done and, moreover, in the only way.

The role of prime numbers in the theory of polynomials is played by the so-called irreducible polynomials. A polynomial $P(x)$ of degree $n > 0$ is said to be irreducible if it is not divisible by any polynomial of degree $0 < s < n$.

An analogue of the statement about the decomposition of any natural number into a product of simple polynomials sounds like this:

Theorem 3. Every polynomial of non-zero degree resolves into a product of irreducible polynomials:

$$P(x) = P_1(x)P_2(x) \dots P_m(x),$$

and this expansion is the unity of order do and polynomials of degree zero*).

Proving Theorem 2, we obtained that every polynomial $P(x)$ of degree $n$ can be decomposed over the field of complex numbers into a product of linear (i.e., first degree) irreducible (*)).

Thus, over the field of complex numbers of non-zero degree of non-zero degree.

Which polynomials are non-zero over the field of real numbers? No matter the country, complex numbers will help us answer this question.

Let $z = a + bi$ be an arbitrary complex number. On the surface complex the number $z = a - bi$ is conjugate to the number $z$.

We need Theorem 4. If $z$ is the root of a polynomial $P(x)$ with real coefficients, then $u$ $z$ is its root.

To prove this, we note the following properties of the operation of taking the conjugate number $z$:

1. The conjugate of the number $z$ to the conjugate of the number $z$ is the same as the original complex number $z$.
2. The number $z$ is equal to the offset of the number $z$ if and only if $z$ is a real number.
3. The conjugate to the sum of complex numbers conjugate to the terms:

$$z_1 + z_2 = z_1 + z_2.$$

4. The number conjugate to a product is equal to the product of conjugates to complex ones:

$$z_1 \cdot z_2 = z_1 \cdot z_2.$$

*) For the proof of Theorem 3, see, for example, «Kvant», 1976, No. 8, p. 15.

⟦folio 21⟧

Using the method of mathematical induction, it can be shown that Rules 3 and 4 apply to the sum and product of more than two numbers:

$$\frac{z_1 + z_2 + \ldots + z_m}{z_1 \cdot z_2 \cdot \ldots \cdot z_m} = \frac{z_1 + z_2 + \ldots + z_m}{z_1 \cdot z_2 \cdot \ldots \cdot z_m}$$

specifically $\bar{z}^m = (\bar{z})^m$.

5. The product of the polynomials $x - z$ and $x - \bar{z}$ is a polynomial with real coefficients:

$$(x - z)(x - \bar{z}) = x^2 - 2ax + (a^2 + b^2).$$

Proof of Theorem 4. Let

$$P(x) = a_n x^n + a_n \frac{1}{x^{n-1}} + \ldots + a_2 x^2 + a_1 x + a_0,$$

where $a_n, a_{n-1}, \ldots, a_2, a_1, a_0$ are real numbers, $z$ is the root of this polynomial. Then

$$0 = P(z) = a_n z^n + a_{n-1} z^{n-1} + \ldots + a_2 z^2 + a_1 z + a_0.$$

Let's use the property of the pairing operation:

$$0 = \bar{P}(z) = \frac{a_n z^n + a_{n-1} z^{n-1} + \ldots + a_2 z^2 + a_1 z + a_0}{a_n z^n + a_{n-1} z^{n-1} + \ldots + a_2 z^2 + a_1 z + a_0} = P(\bar{z}).$$

Theorem 4 is proven.

From Theorem 4 it easily follows

Theorem 5. A polynomial with real coefficients has an even number of non-real roots.

In fact, according to Theorem 4, non-real roots of a polynomial with real coefficients “go in pairs”: $(z; \bar{z})$.

It immediately follows from Theorem 5

Theorem 6. A polynomial of odd degree with real coefficients has at least one real root.

According to the fundamental theorem of algebra, this polynomial has an odd number of roots (equal to its degree), therefore, according to Theorem 5, they cannot all be non-real roots.

Using complex numbers, we have proven a completely “real” theorem. But much more important and interesting is the following fact:

Theorem 7. Any polynomial with real coefficients whose degree is greater than two can be reduced to the field of real numbers.

Proof. If the polynomial $P(x)$ has a real root $a$, then $P(x) = q(x) \cdot (x - a)$. From the proof of Theorem 1 you came up with, it is clear that $q(x)$ is a polynomial with real coefficients. Consequently, in this case $P(x)$ is a reduction of two polynomials with real coefficients, that is, $P(x)$ is reducible to the field of real numbers.

Now let all the roots $z_1, z_2, \ldots, z_m$ of the polynomial $P(x)$ be not real. By Theorem 6 $n$ is even and

$$P(x) = a_n (x - z_1) (x - z_2) \ldots (x - z_n).$$

Divide the roots $z_1, \ldots, z_n$ into conjugate pairs of the form $(z_i; \bar{z}_i)$ and write $P(x)$ like this:

$$P(x) = a_n (x - z_1) (x - \bar{z}_1) (x - z_2) (x - \bar{z}_2) \times \ldots \times (x - z_k) (x - \bar{z}_k);$$

here $k = \frac{n}{2}$.

Each polynomial $P_i(x) = (x - z_i) \times (x - \bar{z}_i)$, $i = 1, 2, \ldots, k$, has, as we have seen, real coefficients. Consequently, the polynomial $P(x) = a_n P_1(x) P_2(x) \ldots P_k(x)$ is reducible to the field of real numbers - after all, this is a product of at least two factors (from $n > 2$ it follows $k > 1$).

Therefore, the final conclusion about the non-conductivity of polynomials over the field of real numbers is as follows:

Theorem 8. Only polynomials of the first degree and polynomials of the second degree with a negative discriminant are irreducible over the field of real numbers.

Consequence. Any polynomial with real coefficients can be decomposed into the product of polynomials of the first and second degrees with real coefficients.

What haven't we talked about yet? About the role that polynomials played in solving significant problems of arborization - the problems of trisection of an angle, squaring a circle and doubling a cube. About how the young Niels Abel proved that there are no formulas for finding the roots of polynomials of degree above four; how the even younger Evariste Galya completely solved the problem of solving the equation in radics. Finally, we have not yet proven the fundamental theorem of algebra...

No, the author must admit that he took on an impossible task; He puts down his pen in exhaustion and asks the reader not to be too demanding.
