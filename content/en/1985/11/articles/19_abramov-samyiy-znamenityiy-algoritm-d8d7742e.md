---
id: 1985-11-abramov-samyiy-znamenityiy-algoritm-d8d7742e
issue: kvant_1985_11
year: 1985
number: "11"
title: The most famous algorithm
authors:
  - Абрамов С. А.
rubric: raznoe
rubric_sub: Разное
page_first: 46
page_last: 48
page_labels: 44-46
tag: 3RZO
lang: en
source: kvant_digital
extraction: vision
content_sha256: 9f92279ce59ca27f03584cbf98c088d51beb9d9e158e61305f7156fcc2bdc4aa
prompt_sha256: draft-1
translated_from: content/ru/1985/11/articles/19_abramov-samyiy-znamenityiy-algoritm-d8d7742e.md
source_content_sha256: 7ac6736602d20b5f6323cba2ebd95222a6a7461dcd42d4a9e0667133b10871f2
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 44⟧

The most famous algorithm

The previous articles in this section provided extensive examples of algorithms and talked about the general principles of writing them in algorithmic language. Here the author dwelled in detail on one single algorithm - this is one of the most ancient and probably the most famous mathematical algorithm.

Doctor of Physical and Mathematical Sciences
S. A. ABRAMOV

In Euclid's Elements, an algorithm is given for finding the greatest divisor (GCD) of non-negative integers, based on the following properties of this quantity. Let $f$ and $g$ be simultaneously non-zero non-negative integers, and let $f \geq g$. Then, if $g=0$, then gcd $(f,g)=f$, and if $g \neq 0$, then for the numbers $f, g$ and $r$, where $r$ is the remainder of the division of $f$ by $g$, the equality gcd $(f,g)=\text{НОД}(g,r)$ holds: for any integer $a$ the numbers $f$ and $g$ have the same common factors as the numbers $g, f-ag$, and the remainder $r$ is a number of the form $f-ag$.

Applying Euclidean's algorithm to the numbers $f$ and $g$ consists of performing a series of one-step steps one after the other, each of which begins with checking whether the second number is zero. If not equal, then the remainder of the division of the first number by the second is calculated, then the first number is replaced by the second, and the second by the calculated remainder, and the transition to the next step occurs. If the second number is equal to zero, then all calculations stop, and the first number is declared as the GCD value.

So, when calculating GCD (39.15), it moves from one pair of numbers to another in the following sequence: (39.15), (15.9), (9.6), (6.3), (3.0). We get that GCD (39.15) = 3.

The remainder is always less than the divisor, and a decreasing sequence of non-negative integers cannot be infinite. Therefore, the application of the Euclidean algorithm will end at some steps due to the next remainder going to zero.

Task 1. Find GCD (21042, 18921).
Task 2. Completely cancel the fraction, which is written as $\underbrace{3\dots3}_{n}$, and the value written as $-3\dots3, m>n$.

***

Most of the ancient algorithms over time were crowded out of computing.

⟦folio 45⟧

practical practice of newer algorithms. The Euclid algorithm avoided this part primarily due to its parsimony. The value of GCD(f,g) can be calculated in many ways, for example, using the following trivial algorithm: if $g=0$, then take the value $f$ as GCD(f,g), otherwise choose from the numbers $g,g-1,...,1$ of the first, when divided by shorter $f$ and $g$ give zero remainders. But, like other similar algorithms, the last algorithm is too wasteful. For example, in the case of coprime $f$ and $g$ it requires $2g$ divisions. Let us now examine the number of divisions required by the Euclidean algorithm and show that for large values ​​of $g$ it exists less than $2g$. We will consider the sequence of all remainders that are calculated during the execution of the Euclidean algorithm. It is useful to denote the original numbers not by $f,g$, but by $f_0,f_1$ (we assume that $f_0>f_1$). We denote the resulting non-zero remainders by $f_2,...,f_n$, and the quotients from dividing $f_0$ by $f_1,f_1$ by $f_2,...,f_{n-1}$ by $f_n$ by $a_1,a_2,...,a_n$:

$$\begin{align*}
f_0 &= a_1f_1 + f_2, \\
f_1 &= a_2f_2 + f_3 \\
\cdots \\
f_{n-2} &= a_{n-1} + f_n, \\
f_{n-1} &= a_nf_n;
\end{align*}$$

here GCD($f_0,f_1$)=$f_n$. The remainder is always less than the divisor, so $f_0>f_1>f_2>...>f_n>0$. As a result, each of the quotients $a_1,...,a_n$ is greater than or equal to one.

Lemma 1. For $i=1,2,...,n-2$ the inequality $f_i>2f_{i+2}$ holds.

Proof. $f_i = a_{i+1}f_{i+1} + f_{i+2} \geq f_{i+1} + f_{i+2} > 2f_{i+2}$.

Lemma 2. Let $k$ be a natural number such that applying the Euclidean algorithm to $f_0,f_1$ does not end after $2k$ divisions (that is, $f_{2k+1} \geq 1$). Then $f_1>2^k$.

Proof. Using Lemma 1, we get

$$f_1 > 2f_3 > 4f_5 > ... > 2^k f_{2k+1} \geq 2^k.$$

Theorem. The number of divisions required by the Euclidean algorithm does not exceed $2[\log_2 f_1]+2^*$.

Proof. It follows from Lemma 2 that if $k$ is a natural number for which $f_1 \leq 2^k$, then the number

$$\begin{align*}
p - a_{i+1}s) + f_1(q - a_{i+1}t) = f_{i+2}.
\end{align*}$$

Thus, to solve problem (2), it is necessary to apply the Euclidean algorithm to $f$ and $g$, considering at each step of its application, in addition to the two numbers that were considered before, also the factors $p,q$ and $s,t$ corresponding to these numbers. At the first step, as multipliers, co-

⟦folio 46⟧

corresponding to the original number $f$ and $g$, 1.0 and 0.1 are taken. To perform the division and having received part $a$ and some remainder, it is necessary, if the remainder is not equal to 0, before moving on to the next step, calculate using the formulas $p - as$, $q - at$ the factors corresponding to obtaining the remainder. The last non-zero remainder and its corresponding factors $u$ and $v$ will satisfy (2).

In the process of applying this algorithm to $f = 39$, $g = 15$ the remainders 9 are sequentially calculated; 6; 3; 0 and the corresponding multipliers 1, -2; -1.3; 2, -5. Thus, $39 \cdot 2 + 15 \cdot (-5) = 3 = \text{НОД}(39,15)$.

Now note that the algorithm can be changed so that the number of operations it requires is reduced by almost one and a half times: of the two numbers $u$ and $v$, it is enough to calculate only $v$ together with $\text{НОД}(f,g)$, and then determine $u$ using the formula $u = (\text{НОД}(f,g) - gv)/f$. For $f = 39$, $g = 15$ we could put $u = (3 - 15 \times (-5))/39 = 2$.

Problem 4. Prove that if the numbers $x$, $y$ give some solution to equation (3), then all solutions are described by the formula $x = x + l't$, $y = y - k't$, where $k' = k/\text{НОД}(k,l)$, $l' = l/\text{НОД}(k,l)$, $t = 0$, $\pm 1$, $\pm 2$.

Problem 5. Using the formulas written in Problem 4, describe an algorithm that allows you to check whether equation (3) has solutions in non-negative integers and if it does, then it allows you to construct one such solution.

***

Consecutive divisions with a remainder, corresponding to scheme (1), also form the basis of the integer fraction algorithm, which allows one to obtain very interesting approximations of the number $f_1/f_0$. A continued fraction (finite) is an expression of the form

$$\frac{1}{b_1 + \frac{1}{b_2} + \dots + \frac{1}{b_k}}$$

where $b_1, \dots, b_k$ are natural numbers. The continued fraction (5) is briefly written as $[b_1, b_2, \dots, b_k]$. Since $f_0 = a_1 f_1 + f_2$, we have

$$\frac{f_1}{f_0} = \frac{1}{f_0} = \frac{1}{a_1 + f_2}$$

Next, we transform $f_2$ in the same way, etc. In the end we get $f_1/f_0 = [a_1, a_2, \dots, a_n]$. Additionally, we will consider the integer fractions $[a_1], [a_1, a_2], \dots, [a_1, \dots, a_{n-1}]$, the values ​​of which are called *nodmoving fractions* of the number $f_1/f_2$. Let us denote the irreducible forms of suitable fractions by $p_1/q_1, \dots, p_{n-1}/q_{n-1}$. We present the following properties of approximations of the number $f_1/f_0$ by suitable fractions without proof:

a) $$\frac{f_1}{f_0} - \frac{p_i}{q_i} < \frac{1}{q_i^2}, \quad i = 1, 2, \dots, n - 1$$

b) If for some fraction $u/v$ and suitable fraction $p_i/q_i$, $i \leqslant i \leqslant n - 1$,

$$\left| \frac{f_1}{f_0} - \frac{u}{v} \right| < \left| \frac{f_1}{f_0} - \frac{p_i}{q_i} \right|,$$

then $v > q_i$.

It is easy to see that the suitable fractions for the number 15/39 (the irreducible form of which is 5/13) are 1/2, 1/3, 2/5. The differences between the irreducible number and this fraction are respectively equal to -3/26, 2/39, -1/65.

Properties a), b) are used in solving a variety of practical problems that require selecting a good approximation for a given non-integer number in the form of a fraction with a relatively small value. An example is the problem of calculating a gear train consisting of two gears. The transmission number must be close to the specified value, and the number of teeth of each gear cannot exceed a certain specified limit.

Problem 6. An Earth year lasts 365.242199 days. Find suitable fractions of the number $\frac{242199}{1000000}$. Which of these fractions determines the law of alternation between simple and highly effective years in the modern calendar?

Problem 7. Write down the following algorithms in the form of a program in the algorithmic language from your textbook (see also the article by A. P. Ershov in the previous issue):

a) a trivial algorithm for calculating GCD;

b) Euclidean algorithm for calculating GCD;

c) an algorithm for solving integer equations of the form $kx + ly = m$;

d) an algorithm for representing the ratio $f_0/f_1$ as a continued fraction.

***

The Euclid algorithm also allows other generalizations, which, in particular, are used in the approximation of irrational numbers and in the calculation of gcd of polynomials. Therefore, in modern computing practice, based on the use of electronic computers, there is an application of this algorithm, which goes back 2300 years.
