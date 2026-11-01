---
id: 1985-12-goncharov-arifmetika-gaussovyih-chisel-bc0aacb5
issue: kvant_1985_12
year: 1985
number: "12"
title: Arithmetic of Gaussian numbers
authors:
  - Гончаров А. Б.
rubric: osnovnye-stati
page_first: 10
page_last: 15
page_labels: 8, 10, 13
tag: XGTX
lang: en
source: kvant_digital
extraction: vision
content_sha256: 92ab6d8e624b58d6d03cf414b340e2322ca8d6b10718a53065064e951048a50b
prompt_sha256: draft-1
translated_from: content/ru/1985/12/articles/03_goncharov-arifmetika-gaussovyih-chisel-bc0aacb5.md
source_content_sha256: d03b34816c76b26ee24506f900727ad916e7381cf258392074a1e2eea8e8d6d2
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 8⟧

Arithmetic of Gaussian numbers

A. V. GONCHAROV

One of the most beautiful arithmetic theories, built by the great German mathematician K. F. Gauss, is described in this article. Gaussian numbers (points with integer coordinates on a plane) can be added and multiplied in a certain way. The resulting theory of divisibility, which fills the general arithmetic of numbers, but also has its own characteristic features, exudes internal harmony and beauty. However, the theory of Gaussian numbers is not just an elegant mathematical toy - it is also a useful apparatus that allows you to find red proofs of various facts from number theory (Pyfarodian triplets, the representation of a natural number as the sum of two squares), and even crystallography (see the article by A. L. Petelin and A. I. Fedoseev in this issue «Kvant»).

The natural numbers 0, 1, 2, 3, ... are the basis of all mathematics. Regarding addition, they are arranged in a simple weight, namely: 1, 2=1+1, 3=1+1+1, ..., so that the only original starting brick is 1.

By introducing subtraction into the game, we find ourselves in the area of ​​integers - 3, - 2, -1, 0, 1, 2, 3... Regarding multiplication, the same series of integers is much more complicated. Namely, there are an infinite number of the simplest bricks from which all non-zero integers are built by multiplication - these are all prime numbers: 2, 3, 5, 7, 11, 13, .... Natural numbers greater than 1 are obtained from them by multiplication: 2, 3, 2×2, 5, 2×3, 7, 2×2×2, 3×3, .... For this However, in order to obtain all rational integers by multiplication, we must also involve both units 1 and -1.

The following theorem stipulates in what sense prime numbers are the building material for the multitypical (i.e. relating to multiplication) construction of natural numbers.

Fundamental theorem of integer arithmetic. Every non-zero number a = εp₁ᵢ p₂ᵢ ... pₙᵢ (1)

zde n≥0, pᵢ are different prime numbers, eᵢ are positive integers, and ε is one of the units. This representation is uniquely defined up to the order of the factors.

If the prime numbers p₁, p₂, ..., pₙ are arranged in ascending order (which is natural), then equality (1) is completely determined by the number a: both the number ε (equal to ±1) and the prime factors p₁<p₂<...<pₙ, and their exponents e₁, e₂, ..., eₙ are uniquely determined by the choice of a.

This theorem*) was known in ancient times.

For a long time, mathematicians obtained proofs of arithmetic theorems about natural numbers, working only with integers. However, at the beginning of the 19th century, Gauss discovered that some questions of number theory only appear in all their clarity and natural beauty when the field of arithmetic also extends to the “numbers” that we now call Gaussian integers. What are these numbers?

Gaussian numbers G are a simple pair of integers

G = {(a, b)|a, b∈Z},

which add and multiply according to the following rules

(a; b)+(c; d)=(a+c; b+d), (2)
(a; b)·(c; d)=(ac-bd; ad+bc). (3)

For clarity, we can imagine the set G as an “integer lattice on the plane,” that is, as the set of all points on the coordinate plane for which both the abscissa and ordinate are integers (Fig. 1), or - which is the same thing - as the set of all vectors with a beginning O and ends at these points. Then the addition of Gaussian numbers (2) is represented as a general addition of vectors according to the parallelogram rule, but multiplication looks somewhat complicated - for the reader, it is not significant on p.11).

⟦folio 10⟧

Fig. 4. Gaussian numbers dividing by 2+3i.

$$5 - 3i = 1 + 1 + 1 + 1 + (-i) + (-i).$$

It turns out that Gaussian numbers have their own “fundamental theorem of arithmetic”, which reduces the study of the multitypical structure of Gaussian numbers to the study of simple Gaussian numbers.

Prime Gaussian numbers and divisibility. If for two Gaussian numbers $a, b$ there is a third number $c \in G$ such that $a = b \cdot c$, we say that $a$ is divisible by $b$ (record $a \div b$) or $b$ divides $a$ (record $b \mid a$). For example, $2 \div 1 + i$ and $2 = (1 + i) \cdot (1 - i)$. figure4 shows Gaussian numbers that are divisible by $2 + 3i$.

Exercise 4. a) Check that $1 + i \div 1 - i$. 6) Prove that the usual divisibility properties hold for Gaussian numbers:

$$a \div b \Rightarrow ac \div bc,$$
$$ac \div bc, c \neq 0 \Rightarrow a \div b,$$
$$a \div b, b \div c \Rightarrow a \div c.$$

c) Mark on the coordinate plane all Gaussian numbers that are divisible by $3 - 2i$.

In the domain of integers, the correspondence between $a \div b$ and $b \div a$ implies that $a = \pm b$. In the domain of Gaussian numbers, this is no longer the case, for example $a \div \pm a, a \div \pm ia$. However, the following is true:

$$a \div b, b \div a \Rightarrow a = \pm ib$$

Proof. Let $a \mid b = c$, then $c$ and $c^{-1} = b \mid a$ are Gaussian numbers. Obviously

$$1 = N(1) = N(c \cdot c^{-1}) = N(c)N(c^{-1})$$,

whence $N(c) = N(c^{-1}) = 1$ (since $N(c)$ and $N(c^{-1})$ are ordinary positive integers). But there are only 4 Gaussian numbers with norm $1 -$ numbers $1, -1, i, -i$, which we will henceforth call *units*.

Let us call two Gaussian numbers conjugate if their quotient is one of ones (Fig. 5). A Gaussian number is called *prime* if it has no other non-zero divisors other than numbers and units associated with it. For example, the numbers 3 and $2 + 3i$ are prime, but the number 5 is not: $5 = (2 + i)(2 - i)$. (To prove the primeness of the numbers 3 and $2 + 3i$, you need to use the correspondence $N(a)N(b) = N(ab)$ and enumerate all Gaussian numbers whose norm is a divisor of the norm of these numbers.)

Exercise 5. Find out which prime numbers from 2 to 30 are Gaussian primes.

Fundamental theorem of the arithmetic of Gaussian numbers. What non-zero Gaussian number g can be represented as

$$g = \varepsilon \cdot g_1^{e_1} g_2^{e_2} \dots g_n^{e_n}$$

food $\varepsilon$ is one of the units, $g_1, g_2, \dots g_n$ are distinct (that is, not allied) prime Gaussian numbers, and $e_1, e_2, \dots e_n$ are positive exponents. This decomposition is unique in the sense that any other decomposition of g into simple components has the form $a = \varepsilon' \cdot h_1^{e_1} h_2^{e_2} \dots h_n^{e_n}$, where a set of simple components and replacing some of them with allied ones, and a set of exponents consists of the same numbers, differing only in order.

Proof. To prove the existence of expansion (6), we perform induction on the norm $N(g)$ of the number g. Base of induction: singular numbers c normie

⟦folio 13⟧

Let us now find the number of decompositions $n=a^2+b^2$ for an arbitrary natural number $n$. It will be convenient for us to consider as different expansions that differ in the change of signs of $a$ and $b$ or the order of the terms. Then this number will be equal to the number of points with integer coordinates on a circle of radius $\sqrt{n}$ with center 0.

Theorem 3. The number of integer points on a circle of radius $\sqrt{n}$, $n \in \mathbb{N}$ or (which is the same) the number of decompositions of the integer $n$ into the sum of two squares is equal to the quadruple image of the number divisor $n$ of the form $4k+1$ over the number divisor of the form $4k+3$.

For example, it is easy to see that circles of radii $\sqrt{5}, \sqrt{13}, \sqrt{17}, 5$ pass through 4, 4, 4, 12 points of the corresponding (check that in all three cases this number is equal to the corresponding quadruple image of the number divisor $n$ of the form $4k+1$ over the number divisor of the form $4k+3$.

For example, it is easy to see that circles of radii $\sqrt{5}, \sqrt{13}, \sqrt{17}, 5$ pass through 4, 4, 4, 12 points of the corresponding (check that in all three cases this number is equal to the corresponding quadruple image of the number divisor $n$ of the form $4k+1$ over the number divisor of the form $4k+3$.

Proof. Let's represent $n$ as $n=2^a q_1^{a_1} \cdots q_k^{a_k} p_1^{e_1} p_1^{e_1} \cdots p_m^{e_m} p_m^{e_m}$,

where $q_j=q_j>0$ and $p_j, p_j$ are prime Hussian numbers ($p_j$ and $p_j$ are inconsistent). Let $n=a^2+b^2=(a+bi)(a-bi)$. From the main theorem it easily follows that $a+bi$ is allied with the number $(1+i)^a \cdot q_1^{a_1/2} \cdots q_k^{a_k/2} \cdot p_1^{f_1} \cdot p_1^{e_1}-f_1 \cdot \cdots \cdot p_m^{f_m} p_m^{e_m}-f_m$,

where $0 \leq f_j \leq e_j$.

This shows that the number represented by $n$ as the sum of two squares is equal to

$$\begin{cases} 0 - \text{если среди чисел } a_i \text{ есть нечетные числа}, \\ 4(e_1+1) \cdot \cdots \cdot (e_m+1) - \text{если все } (13) \\ a_i \text{ четные} \end{cases}$$

(4 appears as a result of the fact that expression (12) differs from $a+bi$ by one, and one is only 4).

On the other hand, any odd divisor $x$ of $n$ has a decomposition into prime Hussian numbers of the form

$$x=q_1^{q_1} \cdot \cdots \cdot q_k^{q_k} p_1^{p_1} p_1^{p_1} \cdots p_m^{p_m} p_m^{p_m},$$

where $b_1 \leq a_1, \cdots, b_k \leq a_k; f_1 \leq e_1, \cdots, f_m \leq e_m$.

But $q_i$ are natural numbers that are Hussian primes, so $q_i$ has remainder 3 when divided by 4 and

$$(b_1+\cdots+b_k):2 \Leftrightarrow x=4k+1 \quad (k \in \mathbb{Z}).$$

From here it is easy to deduce (derive!) that the image of a number divisor of the form $4k+1$ over a number divisor of the form $4k+3$ is equal to

$$\begin{cases} 0, \text{ если среди чисел } a_i \text{ есть нечетное}, \\ (e_1+1) \cdot \cdots \cdot (e_m+1), \text{ если все } a_i - \quad (14) \\ \text{ четные числа.} \end{cases}$$

Comparing (13) and (14), we obtain the proof of the theorem.

Conclusion. We have not explained where the theory stated above came from. And it was like this: in 1796, nineteen-year-old Gauss proved the quadratic law of reciprocity, which is one of the most beautiful pearls of number theory. The history of its origin and proof are described in the article by S. G. Gindikin “The Golden Theorem” (in «Kvant», 1973, No. 1).

The quadratic reciprocity law allows us to exhaustively study an equation of the form $x^2-a \equiv 0(\text{mod } b)$, that is, to find all $x \in N$ such that the number $x^2-a$ is divisible by $b$.

Naturally, Gauss wanted to have a similar theory for an equation of a higher degree, for example $x^4-a \equiv 0(\text{mod } b)$, and therefore began the search for the “biquadratic reciprocity law”. And then they found out that although this is the equation of the first analysis in the field of natural numbers, it is a complete result of practical necessity to even formulate (!) without Hussian integers. Subsequently (1832), Gauss wrote:

“After we began to investigate these questions in 1805, (...) we soon became convinced that (...) for a general theory it is necessary in some sense to endlessly expand the field of higher arithmetic. As soon as we enter this area, we immediately discover an approach to inductively finding the weight of simple and exhaustive theories; however, their evidence is hidden so deeply that they were brought to light only after endless attempts.”

The area that Gauss writes about is the theory of those numbers that now bear his name.
