---
id: 1987-4-galperin-prosto-o-prostyih-chislah-ce61d743
issue: kvant_1987_4
year: 1987
number: "4"
title: Just about prime numbers
authors:
  - Гальперин Г. А.
rubric: raznoe
page_first: 11
page_last: 16
page_labels: 9-14
tag: L8DM
lang: en
source: kvant_digital
extraction: vision
content_sha256: 9e9a8edcd936bbf52c5fa7939f579eb8479306a4bef07d7cd4ab62a907522ffc
prompt_sha256: draft-1
translated_from: content/ru/1987/04/articles/04_galperin-prosto-o-prostyih-chislah-ce61d743.md
source_content_sha256: ab45eab8458514aabc142fb705005a5bdc0d1ce4deb287bdca5b9bf1adb8dd02
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 9⟧

JUST ABOUT PRIME NUMBERS

Candidate of Physical and Mathematical Sciences
G. A. GALYPERIN

The infinity of the set of prime numbers

Everyone knows that most natural numbers can be factored: 10=2·5, 60=3·4·5, 111=3·37, 144=3·3·2·2·2·2 and so on. Such numbers are called composite. But among the natural numbers there are also those that can be factorized in a similar way: for example, 11 cannot be represented as the product of two smaller natural numbers, both of which are greater than 1. Therefore, 11 is called a prime number. In general, prime numbers (or “prime” - as the ancient Greeks put it) are those natural numbers that cannot be decomposed into two factors greater than 1 (one is not considered a prime number). Here are the first few prime numbers: 2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41,... Among them, one even number is 2, the rest of the numbers are odd.

Task 1. Find all pairs of prime numbers that differ: a) by 1, 6) by 17.

At first glance you can see that the series of prime numbers is somewhat bizarre; no simple law is found in its structure.

Does this series have an end? This question is posed in Book IX of Euclid’s Elements and the answer is given there: after each prime number, another, large prime number can be indicated - the series of prime numbers is infinite.

The proof of this statement given by Euclid is extremely ingenious. Euclid reasons as follows: if there are only a finite number of prime numbers and p is the most of them, then the number N = 2 3 5 ... p + 1, since it is greater than p, is not prime, and therefore is divided by some prime number from the available primes from 2 to p (after all, by assumption, there are no other prime numbers!). However, N is not divisible by any of these numbers, since the remainder of dividing N by any of them is 1. The resulting contradiction proves that there is not a finite number of prime numbers, but an infinite number.

This proof by contradiction says that there are any number of large prime numbers, but it does not say how to explicitly find at least one prime number large p. However, this is not difficult to do: to do this, it is enough to check for simplicity the natural numbers on the interval from p+1 to N - among them there must be a prime. Indeed, if N itself is not prime, then it is divisible by a prime number, moreover (as we saw) greater than p, but less than N, i.e., located on the segment [p; N].

Segments with prime numbers

The division of the number line into segments, each of which contains a prime number, can be arbitrarily divided in another way. Let us first prove the following statement: the smallest divisor of the number N=n!+1 (where n!=1·2·3…·n) is a prime number greater than n.

Let's denote this smallest divisor of the number p. Since n!+1 is not divisible by any of the numbers 2, 3, 4, ..., n, we get p>n. On the other hand, if we assume that p is a composite number, i.e., p is divisible by a non-ctor number less than p, then p will not be the smallest divisor of n!+1, which contradicts the assumption. So, p is a prime number greater than n, which is what we needed to prove.

From this proof it follows that on any interval [n; n!+1] there is at least one prime number. And then the numbers 2, 2!+1, (2!+1)!+1,

⟦folio 10⟧

((2!+1)!+1)!+1, etc. split the entire number line into an infinite number of segments, each of which contains at least one prime number; We have again proved that there are infinitely many prime numbers.

It turns out that already in each of the segments [2; 4], [4; 8], [8; 16], [16; 32], ... contains at least one prime number. But this is a difficult theorem, known as “Bertrand’s proposition”*), which sounds like this: between the numbers n and 2n−2 for n>7 there is always a prime number. Bertrand's procedure was proved in 1852 by the famous Russian mathematician Pafnut Lvovich Chebyshev (1821-1894).

Problem 2. Prove that if (p−1)!+1 is divisible by p, then p is a prime number. Note. Use proof of the statement.

Problem 3. Prove, using Bertrand's primer, that for any natural number n there is at least: a) one prime n-digit number; b) 3 prime n-digit numbers. Note. The numbers 10^{n−1}, 2 10^{n−1}, 4 10^{n−1} and 8 10^{n−1} are n-digit.

Note that Euclid's proof does not always give the nearest prime number after p, but only a certain number that usually lies quite far from p. For example, as a prime number obviously greater than 11, the proof gives not 13, but 2311; for 13 it gives not 17, but 59 - a simple divisor of the number 30,031.

Segments without prime numbers

To give a concrete idea of ​​the complexity of the structure of the set of prime numbers, we will show that in the series

*) M.I. Bashmakov. Bertrand's act. «Kvant», 1971, No. 5, p. 4.

Arithmetic progressions and prime numbers

Let's consider all natural numbers that leave a remainder of 2 when divided by 3: 2, 5, 8, 11, 14, ...; the general form of such numbers is 3n+2. Let us prove that among all infinite numbers there are many prime numbers. To do this, we can slightly modify Euclid's proof,

Table 1. Fragment of the distribution of prime numbers.

The table shows how the number of prime numbers changes over the interval from 8,900,000 to 9,000,000, divided into 1000 hundreds. In each column of the table, the bottom number indicates the number of those hundreds of the interval under consideration in which the number of prime numbers is equal to the corresponding top number of the column. For example, in one hundred there are no prime numbers at all, in 117 hundredths there are 4 prime numbers, in 130 hundredths there are 8 prime numbers.

| 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | 4 | 13 | 53 | 117 | 177 | 196 | 175 | 130 | 72 | 47 | 11 | 4 |

10

⟦folio 11⟧

Table 2. Frequency distribution of prime numbers in the natural series.

$A_n$ is the number of prime numbers among the first $n$ natural numbers. The ratio $A_n/n$ is greater to 1/ln $n$, the more $n$ (frequent $A_n/n:1/\ln n$ practically does not differ from 1 at $n=10^9$).

namely, instead of the number $N=2\cdot 3 \times 5 \dots p+1$, the number $M=2\cdot 3\cdot 5 \dots p-1$ is considered, which, being 1 less than a multiple of 3, takes to the sequence 2, 5, 8, 11, 14, ..., $3n+2$, ...

Task 4. Give a complete proof that $M$ has the form $3n+2$.

The number $M$, like $N$, is not divisible by any of the prime numbers 2, 3, 5, ..., $p$. Whether $M$ is prime or can be factorized into several prime factors - in general cases these primes will be greater than $p$. But is there one among the obtained factors that would have the form $3n+2$, i.e., would be contained in the sequence 2, 5, 8, 11, ...? Let us assume that it is not, that is, we assume that all prime factors of $M$ are of the form $3k+1$. But then their product also has the form $3k+1$ (see Problem 5, a), and this contradicts the fact that $M$ has the form $3n+2$ (see Problem 4). Consequently, our assumption is incorrect, and at least one prime factor of the number $M$ has the form $3k+2$. Therefore, there are many prime numbers of the form $3k+2$ infinite.

Task 5. a) Prove that the product of any number of numbers of the form $3k+1$ also has the form $3k+1$. b) Prove the same statement for numbers of the form $4k+1$, c) for numbers of the form $6k+1$.

The above reasoning (with a slight modification) provides a tool for proving the infinity of the set of prime numbers of the form $4k+3$ and $6k+5$. We first ask readers to think about the following problem.

Task 6. Prove that any prime number greater than 3 has: a) the form $4k+1$ or the form $4k+3$; b) view $6k+1$ or view $6k+5$.

Here we will only prove the infinity of the set of prime numbers of the form $6k+5$. We will carry out the proof “by contradiction” in two ways inherent in Euclid’s original proof. Let us assume that there are only a finite number of prime numbers of this type: $p_1, p_2, \dots, p_n$. Consider the number $K=$ $6p_1p_2\dots p_n-1 = 6(p_1p_2\dots p_n-1)+5$. However, of the two: either the number $K$ is itself prime, or it can be decomposed into a finite number of prime factors, among which there is none of the numbers $p_1, p_2, \dots, p_n$ (why?), and not all of which have the form $6k+1$, since $k$ itself does not have this form (see Problem 5, c). This means that one of the prime factors of the number $k$, which does not coincide with $p_1, p_2, \dots, p_n$, has the form $6k+5$, which contradicts the assumption we made. This contradiction shows that the list of prime numbers of the form $6k+5$ is infinite.

Task 7. Conduct a proof of the infinity of the set of prime numbers of the form $6k+5$, indicating an explicit method for finding these numbers.

Task 8. Conduct a detailed proof of the infinity of the set of prime numbers of the form $4k+3$. Note: Quadruple the product of numbers of this type and subtract 1 from the product.

Task 9. Prove that there are an infinite number of prime numbers that do not end in 1 (i.e., end in 3, 7, and 9). Note: Consider all prime numbers of the form $10k+a$, where $a \neq 1$, and carry out similar reasoning as above.

A generalization of the issues considered is the following theorem, formulated in 1788 by the French mathematician Legendre and proven by the German mathematician Dirichlet in 1837.

Theorem. Any infinite arithmetic progression $a_1, a+d, a+2d, a+3d$, in which the first term a is coprime with the difference $d$, contains an infinite number of prime numbers. In other words, the function $y=dx+a$, where $d$ and $a$ are relatively prime numbers, takes on an infinite number of prime values ​​when $x$ passes through a successive series of natural numbers.

Dirichlet's proof is not elementary, and for many years no elements of the proof of this remarkable theorem were visible. Elementary proof was first obtained in 1949 (161 years after Le-

⟦folio 12⟧

Zhandra!) by the prominent Danish mathematician A. Selberg, who proved many very difficult theorems of number theory in an elementary way, without the use of higher mathematics.

Twins

Let us recall the first task formulated at the very beginning of the article. As you probably proved, if two prime numbers differ by an odd number $p$ (by 1 or 17, as in Problem 1), then one of these prime numbers is even, and would become equal to 2. Therefore, the other prime number $q$ differs from $p$ by 2. If, in addition, $p$ is a prime number (like $p=17$ in problem 1), then the prime numbers $p$ and $q$ are called twin numbers; in problem 1 these are numbers 17 and 19.

Task 10. Prove, using Dirichlet's theorem, that there are infinitely many prime numbers that do not belong to any pair of twin prime numbers. e are indicated. All these prime numbers should be, for example, from the arithmetic progression $\{15k+7\}$.

The question arises: how many pairs of twin numbers are there? For example, on the interval from 0 to 100,000 there are 1225 such pairs, and in the interval from 8,000,000 to 8,100,000 there are only 518. Are such pairs ever discontinuous in the infinitely far-extending series of prime numbers? Neither this nor the more general question posed by the great German mathematician David Hilbert at the 2nd International Congress of Mathematicians in Pa-

Rige in 1900, is the linear equation $ax+by=c$ with integer coefficients $a, b, c$, where $a$ and $b$ coprime, always solvable in prime numbers $x$ and $y$? - no response has yet been received.

Fundamental Theorem of Arithmetic

Any natural number greater than one admits one and only one (up to the order of the factors) decomposition into prime factors.

Proof. If there is at least one number that admits two expansions into different prime factors, then there necessarily exists the smallest number $N$ that has this property:

$$N = p_1 p_2 \dots p_n = q_1 q_2 \dots q_m,$$

where $p$ and $q$ denote prime numbers. Changing, if necessary, the order of these factors, we can assume that $p_1 \leq p_2 \leq \dots \leq p_n, q_1 \leq q_2 \leq \dots \leq q_m$. Note that $p_1 \neq q_1$, since in the case of $p_1 = q_1$ the natural number $N/p_1 = N/q_1$ is less than $N$, would have two different prime factorizations, which contradicts the assumption that $N$ is minimal. Let's assume $p_1 < q_1$ and consider the number $N' = N - p_1 q_2 \dots q_m$. It is easy to see that the number $N' = p_1(p_2 p_3 \dots p_n - q_1 q_2 q_3 \dots q_m) = (q_1 - p_1)q_2 q_3 \dots q_m$ is positive and less than $N$. This means, according to our assumption, $N'$ having

⟦folio 13⟧

there is a unique factorization into prime factors. But just as the prime number $p_1$ is included in the expansion $N'$, then $p_1$ is included in $q_1 - p_1$ or $q_2 q_3 \dots q_m$. From inequalities $p_1 < q_1 \leqslant q_2 \leqslant \dots \leqslant q_m$ it follows that $p_1$ is not a factor in $q_2 q_3 \dots q_m$. Therefore, $p_1$ is a factor in $q_1 - p_1$, i.e. $q_1 - p_1$ is divided by $p_1$. And then $q_1$ is divided by the prime number $p_1$. This, however, cannot be, since $q_1$ is a prime number. The contradiction we have arrived at shows the invalidity of the first initial assumption, which is where the proof ends.

Sweeping. From the proof of the fundamental theorem of arithmetic, it becomes clear why *ed1* is not classified as a prime number. If it is included among the prime numbers, then any natural number begins to be decomposed into prime factors in many ways, since an arbitrary number of ones can be added to the decomposition.

Bot one important consequence of the fundamental theorem of arithmetic: if a prime number $p$ is a factor in the product $ab$, then it is a factor in either $a$ or $b$. Indeed, if $p$ was not a factor in either $a$ or $b$, then the variable of the prime factorization of the numbers $a$ and $b$ would result in a prime factorization of the number $ab$ that does not contain the factor $p$. On the other hand, the equality $ab = pt$ is true, where $t$ is some natural number. Therefore, the variable $p$ and the decomposition into prime factors of the number $t$, we obtain the decomposition of the number $ab$ into prime factors already containing the factor $p$. Thus, we obtain two expansions of $ab$ into different prime factors, which contradicts the main theorem.

It follows from the main theorem that the number $N$ can be represented in the form
$$N = p_1^{k_1} p_2^{k_2} \dots p_s^{k_s},
$$ where $k_1, \dots, k_s$ is the number of distinct prime divisors of $p_1, \dots, p_s$ corresponding in the expansion $N$. All divisors of $N$ are of the form $a = p_1^{r_1} p_2^{r_2} \dots p_s^{r_s}$, where $0 \leqslant r_1 \leqslant k_1$, $0 \leqslant r_2 \leqslant k_2$, $0 \leqslant r_s \leqslant k_s$.

Once again about the infinity of prime numbers
The unity of factorization allows us to give a new proof of the infinity of prime numbers. This proof is due to Leonhard Euler.

Suppose that 2, 3, 5, ..., $p$ are all existing prime numbers. Then from the formula for the sum of a geometric progression with a value less than 1, it follows that for any natural number $n$ $1 + \frac{1}{2} + \frac{1}{2^2} + \dots + \frac{1}{2^n} < \frac{1}{1 - \frac{1}{3}}, \dots, 1 + \frac{1}{p} + \frac{1}{p^2} + \dots + \frac{1}{p^n} < \frac{1}{1 - \frac{1}{p}}$.

Variable these inequalities are corrected:
$$\left(1 + \frac{1}{2} + \dots + \frac{1}{2^n}\right)\left(1 + \frac{1}{3} + \dots + \frac{1}{3^n}\right) \dots
\dots \left(1 + \frac{1}{p} + \dots + \frac{1}{p^n}\right) <
\frac{1}{\left(1 - \frac{1}{2}\right)\left(1 - \frac{1}{3}\right)\dots\left(1 - \frac{1}{p}\right)}$$.

On the right is a very specific number; let's denote it $A$. The product on the left, after opening all the parentheses, turns into the sum of $S$ numbers, the reciprocals of all the divisors of the number $N = 2^n 3^n 5^n \dots p^n$ (this is where the fundamental theorem of arithmetic is used - make sure!). Therefore, the left side of the inequality is large sums $A_n = 1 + 1/2 + 1/3 + 1/4 + 1/5 + \dots + 1/2^n$, which includes only part of the terms of the sum $S$. So for any $n$ $A_n < A$. But $A_n = 1 + 1/2 + (1/3 + 1/4) + (1/5 + 1/6 + 1/7 + +1/8) + \dots + (1/(2^n - 1) + 1) + \dots + (1/2^n) > 1 + 1/2 + 2 \cdot 1/4 + 4 \cdot 1/8 + \dots + 2^{n-1} \cdot 1/2^n = 1 + n/2$, which immediately leads to a contradiction: $A > 1 + n/2$ with all $n$. Therefore, prime numbers cannot be limited to any finite list, which is what needed to be proven.

Simplicity check

When factoring $N$ into factors or testing it for simplicity, you should check the divisibility of $N$ into successive prime numbers 2, 3, 5, 7, .... When checking the number $N$ for simplicity, it is enough to limit yourself to prime divisors not exceeding $\sqrt{N}$. Indeed, if $N = ab$, then the lesser of the numbers $a, b$ is not greater than $\sqrt{N}$ (if both were greater than $\sqrt{N}$, then their product would be greater than $N$), and from the divisibility of $N$ by $a$ it automatically follows that $N$ is also divisible by $N/a$ (so the divisibility there is no need to check for $N/a$). The first mathematical ications (Leonardo of Pisa).

Examples. a) If $N = 91$, then $\sqrt{91} < 10$; Having checked the prime numbers 2, 3, 5, 7, we find that $91 = 7 \cdot 13$.

⟦folio 14⟧

6) If $N=1987$, then $\sqrt{N}<45$, ..., and since $N$ is not divisible by any of the primes up to 43, then 1987 is prime.

In some cases, when determining prime numbers $N$, it is possible not to perform the indicated divisions by prime numbers. The following simple statement, formulated by Euler back in the 18th century, allows us to define the prime number $N$ in a completely different way.

Euler's first criterion. If the odd number $N>1$ can be represented as the difference of the squares of two natural numbers in more than one way, then $N$ is composite; if there is only one such method, then $N$ is simple.

Proof. We consider $N$ not a perfect square, since a perfect square is always a composite number. Let $N=m^2-n^2=(m-n)(m+n)$. It follows that $m-n$ and $m+n$ are divisors of $N$. If $N$ is prime, then $m-n=1$, $m+n=N$ and the numbers $m=(N+1)/2$, $n=(N-1)/2$ are uniquely determined by the number $N$, and therefore $N$ cannot be represented in another way as the difference of two squares.

If $N$ is composite, i.e. $N=ab$, and $a>b>1$ are odd numbers, then, taking $x=(a+b)/2$ and $y=(a-b)/2$, we obtain: $a=x+y$, $b=x-y$, from which $N=ab=x^2-y^2$: another representation of $N$ is obtained in the form of a difference of squares.

It follows that if $N$ is represented in more than one way as a difference of squares, then $N$ cannot be prime: for a prime $N$ such a representation is singular. If $N$ is represented in only one way in the form of a difference of squares, then $N$ cannot be composite (as proven above), so it would be simple. The criterion has been established.

This criterion makes it possible to test the divisors $N$ using a table of squares, and, by adding sequentially to $N$ the squares of $n^2$ integers, check whether the sum at $n<(N-1)/2$ is an exact square or not.

Let's factorize, for example, 3551 in this way. By adding successively the numbers $1^2$, $2^2$, $3^2$, ... to 3551, we check each time whether the resulting sum is an exact square. Checking (using a table of squares) shows that $3551+7^2=60^2$. So, $3551=60^2-7^2=53\cdot67$.

Task 11. Factor the numbers 6557, 19019, 209209 using the indicated method.

It is also easy to prove.

Euler's second criterion. If a natural number can be represented as the sum of two squares of natural numbers in more than one way (it is assumed that rearranging the sweeteners does not give a new way), then $N$ is a composite number.

From Euler's second criterion it follows that if a prime number is represented as the sum of two squares of natural numbers, then there is only one way. But what prime numbers are represented in this form?

Task 12. Prove that numbers of the form $4k+3$ cannot be represented as the sum of two squares. Note. The square of an even number is divisible by 4, and the square of an odd number leaves a remainder of 1.

Prime numbers of the form $4k+1$ remain contenders, and, as Pierre Fermat proved, all such numbers can be represented as the sum of two squares. Therefore, it is not difficult to answer, for example, the following question: which of the three prime numbers 1973, 1979 and 1987 are representable as the sum of two squares?

Task 13. a) Prove that for all natural numbers $n$ the number $N=n^4+4$ is composite (Sophie Germain’s theorem). 6) Prove that for all natural numbers $m$ and $n$ the number $N=n^4+4m^4$ is composite. Note. $N=(n^2-2m^2)^2+(2mn)^2$; apply Euler's second criterion.

Polynomials that produce prime numbers

With prime numbers, everything would be simple if there was a general formula for finding them. Attempts to construct such a formula were made, of which only simple values. But already at $n=40$ its value is equal to $41^2$. It is easy to prove that no polynomial in one variable can take only simple values.

Just recently a polynomial was found, all positive values

(For the end see page 38)
