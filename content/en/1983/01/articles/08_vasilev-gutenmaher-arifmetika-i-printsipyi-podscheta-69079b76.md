---
id: 1983-1-vasilev-gutenmaher-arifmetika-i-printsipyi-podscheta-69079b76
issue: kvant_1983_1
year: 1983
number: "1"
title: Arithmetic and counting principles
authors:
  - Васильев Н. Б.
  - Гутенмахер В. Л.
rubric: shkola-v-kvante
rubric_sub: Школа в «Кванте»
page_first: 32
page_last: 37
page_labels: 30-35
tag: 7EGL
lang: en
source: kvant_digital
extraction: vision
content_sha256: 2fd66833c7681916137f2f00e65c28a60e3c0c2533a1973008ad88c24fe96848
prompt_sha256: draft-1
translated_from: content/ru/1983/01/articles/08_vasilev-gutenmaher-arifmetika-i-printsipyi-podscheta-69079b76.md
source_content_sha256: ba6d7ebca30244debe266c260d947c200052163f8fb112f9fc6169e4ebbbc27f
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 30⟧

Arithmetic and counting principles

N. B. VASILIEV,
V. L. GUTENMACHER

Mathematics is based on arithmetic - the theory of natural numbers 1, 2, 3, .... In theory, there are a number of deep and red theorems. There are many difficult and still unsolved problems in it, which for hundreds of years have defied the efforts of the most outstanding mathematicians. Purpose The branches of modern mathematics arose from attempts to solve and generalize number-theoretic problems. C. F. Gauss (1777-1855), who made many remarkable discoveries in number theory and other areas of mathematics, said: “Matematika is the queen of sciences; number theory is the queen of mathematics.”

The purpose of this article is to introduce readers to the simplest concepts of this fascinating science, the fundamental theorem of arithmetic, some arithmetic functions and the principles of counting.

§ 1. Prime and composite numbers

Throughout what follows we will deal with natural numbers. We say that the number $n$ is divisible by the number $a$ if there is a number $b$ such that $n=ab$. In this case, the number $a$ is called a divisor of the number $n$, and the number $n$ is called, in turn, a multiple of the number $a$.

Every natural number greater than one has at least two divisors: 1 and the number itself. A number greater than 1 is called prime if it has no other factors, and composite if it does. One is neither a prime nor a composite number.

Every natural number can be decomposed into a product of primes.

In fact, the composite number $n$ can be decomposed into the product of two factors less than $n$. If among them there are non-simple (composite) ones, each of them can be decomposed into a product of two less

⟦folio 31⟧

etc. Obviously this process cannot continue indefinitely, because at each step we get fewer factors than at the previous one, and the total number of natural numbers less than $n$ is finite: $n-1$. As a result, we come to decomposing the number into prime factors.

Typically, identical prime factors are collected together and the expansion is written in this standard form:

$$n = p_1^{a_1} \cdot p_2^{a_2} \cdot \dots \cdot p_k^{a_k},$$

where $p_1 < p_2 < \dots < p_k$ are various prime numbers, $a_1, a_2, \dots, a_k$ are natural numbers. For example, $1350 = 2 \cdot 3^3 \cdot 5^2$.

Fundamental theorem of arithmetic. Every natural number greater than 1 can be factorized in a unique way.

This theorem is called fundamental because practically all the properties of divisibility of numbers are its consequences.

We will not dwell on the proof of the main theorem (it can be found, for example, in [1], [3]), but formulate only one of its corollaries.

In order for the number $a$ to be divisible by the number $b$, it is necessary and sufficient that each prime factor included in the expansion of the number $b$ is included in the expansion $a$ to the same or a higher degree.

How can you factor a larger number into prime factors? This useful observation will help us with this.

If the number $n$ is, then it has a divisor not exceeding $\sqrt{n}$ and greater than 1.

Let's assume the opposite. Let $n=ab$, and both divisors $a$ and $b$ be greater than $\sqrt{n}$. Since $a > \sqrt{n}$ and $b > \sqrt{n}$, we have $ab > n$, which contradicts the assumption.

To verify the primeness of a given number $n$ or, if $n$ is a factor, to find its divisor, it is enough to check whether $n$ is divisible by prime numbers not greater than $\sqrt{n}$.

You can create a list of prime numbers not exceeding a given number $N$ in this way. You need to write down all the natural numbers from 1 to $N$ in a row, cross out one, then cross out all the even numbers except the number 2, then cross out all the numbers that are multiples of 3, except the number 3 itself, then the multiples of 5, etc. until the largest prime number not exceeding $\sqrt{N}$. After crossing out numbers that are multiples of some prime number $p$, the first number not crossed out will be the next prime number after $p$. This method of reading numbers is called the “sieve of Eratosthenes.” It is not as bad as it seems at first glance: for example, to create a table of prime numbers up to 2000, it is enough to cross out all multiples of the first fourteen prime numbers from 2 to 43 (since $47^2 > 2000 > 43^2$). With the help of modern computers, many more tables of prime numbers have been compiled. Here, of course, it is worth noting that all prime numbers cannot be written down. As Euclid was able to prove,

There are infinitely many prime numbers.

Suppose there are a finite number of primes and $p$ is the largest of them. Consider the product $p! = 1 \cdot 2 \cdot 3 \cdot 4 \cdot \dots \cdot p$ of all numbers from 1 to $p$ (read “$p$ factorial”). The number $p!$ is divisible by all prime numbers, since, by assumption, the product $p!$ contains all prime numbers. The number $p! + 1$ following it in the natural series should be factorized into prime factors, but this is not possible, since $p! + 1$ is not divisible by any of the prime numbers! Contradiction.

Many ancient and still not completely solved problems of number theory relate to the distribution of prime numbers in the natural series.

⟦folio 32⟧

For example, by observing they show that there are adjacent simple odd numbers: 3 and 5, 5 and 7, 17 and 19, 29 and 31, etc. Such numbers are called close primes. Until then, it is not known whether the number of pairs of simple twins is finite or infinite.

On the other hand, between prime numbers there can be as many gaps as possible, more precisely

For any $k$ in the natural series there are $k$ consecutive composite numbers.

Indeed, let's take the number $(k+1)!$ and consider a series of $k$ consecutive numbers:

$$(k+1)!+2; (k+1)!+3; (k+1)!+4;...$$
...; $(k+1)!+k+1,$

All of them are composite: the first is divisible by 2, the second by 3, ..., the last by $k+1$.

Tasks
1. Factor the numbers $a$) 1981 into prime factors; $b$) 1982; $c$) 1983; $d$) 1984.
Solution to problem 1$\theta$). Dividing 1983 by 3, we get 1983=3·661. Teler, we are looking for divisors of the number 661. Since $25^2<661<26^2$, we need to check divisibility by prime numbers 3, 5, 7, 11, 13, 17, 19, 23. 661 is not divisible by any of them, which means 661 is a prime number.
2. Write six in the natural series $a)$; $b)$ thirteen consecutive composite numbers.
$\theta)$ Are there such neighboring prime numbers that exactly six composite numbers fit between them in the natural series?
3. Prove that if $d$ is the greatest divisor of the composite number $n$, less than $n$, then the number $n/d$ is prime.
4. Prove that among the natural numbers from 1 to 30$m$ there are at most 10$m$ prime numbers (for each $m=1, 2, 3, ...$).
5. Find all numbers $p$ such that $p, p+2, p+4$ is also prime (such numbers can be called prime “triplets”).

6. How many zeros does the decimal notation of the number 30 end with?
7. Prove that among the numbers 2, 5, 8, 11, ... (that is, numbers of the form $3m+2$, where $m=0, 1, 2, ...$) there are infinitely many primes.

§ 2. Number of divisors.
Combinatorial product rule

On figure 1 below are written all the natural divisors of the numbers 96 and 144. We see that all the divisors of the number 96 are divided into pairs of divisors complementary to each other (on figure 1 they are connected by two), and in the number 144 one of the divisors, 12, is complementary to itself, since $144=12^2$. From the symmetry of the set of divisors the following statement follows:

If the number $n$ is not a square of an integer, then it has an even number of divisors, and if it is, then it has an odd number.

In fact, for every divisor $a$ of the number $n$, less than $\sqrt{n}$, there is a corresponding divisor $n/a$, greater than $\sqrt{n}$. Therefore, divisors other than $\sqrt{n}$ are always a number. If $n=k^2$, then another divisor $k$ is added to them.

Let $d(n)$ be the number of divisors of the number $n$. As shown above, if $n$ is a perfect square, then $d(n)$ is an odd number (for example, $d(144)=15$), and if not, then $d(n)$ is an even number (for example, $d(96)=12$). Let us now show how, knowing the decomposition of the number $n$ into prime factors, find the value $d(n)$.

First of all, note that for a prime $p$ there is always $d(p^a)=a+1$.

Indeed, by definition, the prime number $p$ has only two de-

Fig. 1. Divisors and their complements

⟦folio 33⟧

Fig. 2. Product rule: divisors $2^{\beta_1} \cdot 3^{\beta_2}$ of numbers $144 = 2^4 \cdot 3^2 (0 \leq \beta_1 \leq 4, 0 \leq \beta_2 \leq 2)$ are placed in the table $5 \times 3$.

cast: 1 and $p$, and, by virtue of the corollary to the fundamental theorem of arithmetic, the number $p^a$ has $(a+1)$ divisors: 1, $p$, $p^2$, ..., $p^a$ (it is considered that $p^0 = 1$).

Consider now the number $n$ with two different prime factors, for example $n = 144 = 2^4 \cdot 3^2$. All its divisors are of the form $2^{\beta_1} \cdot 3^{\beta_2}$, where $\beta_1$ can take any of five integer values ​​from 0 to 4, $\beta_2$ is one of three values ​​0, 1 or 2. This means that the total number of different pairs of $(\beta_1; \beta_2)$ can be $3 \cdot 5 = 15$, so $d(144) = 15$ (see Fig. 2). Here we have used a useful counting principle.

Product rule. If the element $\beta_1$ can be chosen in $N_1$ ways, and the element $\beta_2$ can be chosen in insignificantly from $\beta_1 - N_2$ ways, then a total of $N_1 \cdot N_2$ different pairs $(\beta_1; \beta_2)$ can be made. In general, if you need to compose a set $(\beta_1; \beta_2; ..., \beta_k)$ of $k$ elements, and element $\beta_1$ can be chosen in $N_1$ ways, element $\beta_2$ in $N_2$ ways, ..., element $\beta_k$ in $N_k$ ways, then in total you can compose $N_1 \cdot N_2 \cdots N_k$ different sets $(\beta_1; \beta_2; ...; \beta_k)$.

This general rule allows us to write a formula for the number of divisors of any $n = p_1^{\alpha_1} \cdot p_2^{\alpha_2} \cdots p_k^{\alpha_k}$. Indeed, according to the corollary of the fundamental theorem of arithmetic, any divisor of the number $n$ has the form $p_1^{\beta_1} \cdot p_2^{\beta_2} \cdots p_k^{\beta_k}$, where $\beta_i$ takes one of the $(\alpha_i + 1)$ values ​​0, 1, ..., $\alpha_i$. Therefore, the number of different sets of $(\beta_1; \beta_2; ...; \beta_k)$, and therefore different divisors of $n$, is $d(n) = (\alpha_1 + 1)(\alpha_2 + 1) \cdots (\alpha_k + 1)$. (*)

Exercise:
8. Find: a) $d(1000)$; 6) $d(1350)$; b) $d(5040)$; d) $d(84^{19})$.

Solution to problem 6). Answer: 24. Since $1350 = 2 \cdot 3^3 \cdot 5^2$, using formula (*) we obtain $d(2^1 \cdot 3^3 \cdot 5^2) = (1 + 1)(3 + 1)(2 + 1) = 24$.

9. Give an example of a number that has a) exactly 6 divisors; 6)exactly 7 divisors.

10. Prove that the number $n$, which leaves remainder 2 when divided by 3, has an equal divisor of the form $3l + 1$ and $3s + 2$ and is not a perfect square.

11. The circle is divided into 720 identical arcs. How many different (by the number of sides) regular polygons with vertices at the points of division are there?

12. How many even divisors does the number $n$ have (write the general formula)? For which numbers $n$ the number of such divisors is equal to $\frac{1}{2} d(n)$?

13. The desk has 9 drawers. How many ways can five different books be arranged into them?

Answer: $9^5$ ways. Solution. We can put the first book in 9 ways in one box or another, and, regardless of this choice, there are 9 ways to choose a box for the second book, etc. According to the rules of the work, all ways are $9^5$.

14. How many three-digit numbers are there in which all digits are odd?

15. How many five-digit numbers are there in which the digit 5 ​​appears at least once in decimal notation?

§ 3. Euler's function.
Inclusions and exclusions

In § 2 we became acquainted with Euler's arithmetic function: $\varphi(n)$ is the number of numbers less than the number $n$ and coprime to it, that is, numbers that do not have common divisors with $n$ (except 1).

For example, on figure 3 the numbers from 1 to 18 are written out. We see that all relatively prime numbers from 18 onwards are divided into pairs $(a; 18 - a)$.

Such symmetry will be for any $n > 2$: if the number $a$ is coprime with $n$, then $(n - a)$ will also be coprime with $n$ and not equal to $a$. In fact, if $n - a$ and $n$ had a common divisor $p > 1$, then their difference $n - (n - a) = a$ would have the same divisor $p$, thus $n$ and $a$ would not be coprime.

From this symmetry $a \leftrightarrow (n - a)$ we see that the number $\varphi(n)$ is always even (for $n > 2$).

Let us now show how $\varphi(n)$ is found, knowing the decomposition of the number $n$ into

⟦folio 34⟧

Prime factors. First of all, note that if $p$ is prime, then $\varphi(p) = p - 1$, since all numbers 1, 2, ..., $(p - 1)$ are coprime to $p$ and less than it. Let $n = p^\alpha$, where $p$ is a prime number and $\alpha > 1$. then from the $n$ numbers, without exceeding them $n$, we must exclude those that are divisible by $p$. So numbers

$$\frac{n}{p} = \frac{p^\alpha}{p} = p^{\alpha - 1},$$

pose

$$\varphi(n) = n - \frac{n}{p} = n \left(1 - \frac{1}{p}\right).$$

Let us now consider the numbers $n = p_1^{\alpha_1} p_2^{\alpha_2}$ with two different prime factors. We illustrate the counting of $\varphi(n)$ (for $n = 18$ it continues to figure 3) with a diagram on figure 4: the square represents the set of numbers from 1 to $n$, the red and blue circles are the set of numbers divisible by $p_1$ and $p_2$ respectively, the intersection of the circles is the set of numbers, divisible by $p_1 p_2$.

Numbers coprime to $n$ are represented by the shaded part of the square. To determine their number, we must exclude $N_1 = n/p_1$ “red numbers”, $N_2 = n/p_2$ “blue” numbers and add $N_{12} = n/p_1 p_2$ numbers lying at the intersection of the circles. Thus,

$$\varphi(n) = N - N_1 - N_2 + N_{12} = n - \frac{n}{p_1} - \frac{n}{p_2} + \frac{n}{p_1 p_2} =$$

$$= n \left(1 - \frac{1}{p_1}\right) \left(1 - \frac{1}{p_2}\right).$$

figure 5 will help us analyze the case of the number $n = p_1^{\alpha_1} p_2^{\alpha_2}$ with different factors: the square represents the set of numbers without exceeding them, and the circles represent the set of numbers divisible by $p_1$, $p_2$ and $p_3$; then in the circles there will be $N_1 = \frac{n}{p_1}, N_2 = \frac{n}{p_2}$ and $N_3 = \frac{n}{p_3}$ numbers corresponding, in their pairwise intersections - $N_{12} = \frac{n}{p_1 p_2}, N_{13} = \frac{n}{p_1 p_3}$ and $N_{23} = \frac{n}{p_2 p_3}$ numbers, and in the intersection of all three circles - $N_{123} = \frac{n}{p_1 p_2 p_3}$ numbers (these are numbers divisible simultaneously by $p_1, p_2$ and $p_3$, that is, by $p_1 p_2 p_3$).

We have to count how many numbers are contained in the square but do not fall into any of the circles. If we subtract the sum $(N_1 + N_2 + N_3)$ from $n$, then we subtract the numbers that fall into exactly two of the three circles twice, and the numbers that fall into all three circles even three times.

Now to the difference $N - (N_1 + N_2 + N_3)$ we add the sum $(N_{12} + N_{13} + N_{23})$. Then we will take into account correctly all the numbers that fall in only one of the two circles, and only the numbers

Fig. 4.

Fig. 5. If all this is in the square of $N$ elements, then outside the circles there are $N - N_1 - N_2 - N_3 + N_{12} + N_{23} + N_{31} - N_{123}$ of them.

⟦folio 35⟧

falling into all three circles at the same time is incorrect: we subtracted their number three times and added them three times again. You will have to subtract another $N_{123}$ from the sum $N - (N_1 + N_2 + N_3) + (N_{12} + N_{13} + N_{23})$. Now we learned all the numbers included in the union of the three circles once and came to the following formula:

$$\varphi(n) = n - \frac{n}{p_1} - \frac{n}{p_2} - \frac{n}{p_3} + \frac{n}{p_1 p_2} + \frac{n}{p_1 p_3} + \frac{n}{p_2 p_3} - \frac{n}{p_1 p_2 p_3} = n \left(1 - \frac{1}{p_1}\right) \left(1 - \frac{1}{p_2}\right) \left(1 - \frac{1}{p_3}\right).$$

We have encountered here special cases of this promised counting rule.

Rule of inclusions and exclusions. Let the set $A$ be given and its subset $k$ selected. The number of elements of the set $A$, which are not included in any of the selected subsets, is calculated as follows: from the total number of elements $A$, subtract the number of elements of all $k$ subsets, add the number of elements of all their pairwise intersections, subtract the number of elements of all triple intersections, add the number of elements of all intersections by four, etc. until the intersection of all $k$ subsets.

Apply this rule to counting $\varphi(n)$, where

$$n = p_1^{a_1} p_2^{a_2} \dots p_k^{a_k},$$

and uses algebraic identities

$$1 - x_1 - x_2 - \dots - x_k + x_1 x_2 + x_1 x_3 + \dots + x_{k-1} x_k - x_1 x_2 x_3 - \dots - x_{k-2} x_{k-1} x_k + \dots + (-1)^k x_1 x_2 \dots x_k = (1 - x_1) (1 - x_2) \dots (1 - x_k)$$

(its left side of the device is exactly according to the rules of “inclusions and exclusions”), you can get the general formula

$$\varphi(n) = n \left(1 - \frac{1}{p_1}\right) \left(1 - \frac{1}{p_2}\right) \dots \left(1 - \frac{1}{p_k}\right).$$

Note that the algebraic identity written above can also be used to prove the general rule of inclusion and exclusion: by setting several $j$ of the $k$ letters $x_1, x_2, \dots, x_k$ equal to 1, and the remaining $(k - j)$ equal to zero, we obtain (for $0 < j \leq k$) on the right side 0, and the left side shows that the intersection elements are exactly $j$ subsets are added and subtracted the same number of times.

In conclusion, we note that the function $\varphi(n)$ and the function $d(n)$ from the previous section have such an important property, which in number theory is called multiplicative:

If $a$ and $b$ are coprime, then $\varphi(ab) = \varphi(a) \cdot \varphi(b)$ and $d(ab) = d(a) d(b)$

(Check this out for yourself.)

Tasks

16. How many proper irreducible fractions are there with a value of 288?

17. Find $a)$ $\varphi(96)$; $b)$ $\varphi(540)$; $b)$ $\varphi(1983)$.

18. How many numbers are there, not exceeding 1000, which $a)$ are divisible by both 6 and 15; $b)$ are divisible by 3 but not divisible by 7; $b)$ are divisible by 6 or 15.

19. How many natural numbers are there, not exceeding 1000, that are not divisible by 3, 5, or 7?

20. The union of the set $A$ and $B$ consists of 25 elements, the intersection - of 10 elements. How many elements are in the set $A$ if there are 15 elements in $B$; $6$ 21 elements; $b)$ 10 elements?

21. In December there were 10 clear and calm days, 15 days there was wind and 12 days of snow. How many days was there a snowstorm (both snow and wind)?

22. In a group of 25 students, 12 are studying Latin, 10 Greek and 9 Sanskrit. For every two languages, there are exactly 5 students studying about these languages. How many students study all three languages?

23. On each side of the triangle $ABC$ 9 points are marked and divided into 10 equal parts. Let's space out all possible triangles with vertices at offset points (one on each side). How many of these triangles are there in which one of the sides is not parallel to the side of the triangle $ABC$?

Literature

1. I. M. Vinogradov. “Fundamentals of Number Theory” (M., “Nauka”, 1980).

2. I. I. Ezhov, A. V. Skorokhod, M. I. Yadrenko. “Elements of Combinatorics” (Moscow, “Nauka”, 1977).

3. L. A. Kaluzhin. “The Fundamental Theorem of Alfmetic” (Moscow, “Nauka”, 1969).

4. O. Ore. “An Invitation to Number Theory” (M., “Nauka”, Library «Kvant», 1980).

5. L. A. Basova, M. A. Shubin, L. A. Epstein. “Lectures and problems in mathematics” (M., “Prosveshcheniye”, 1981).

6. Correspondence mathematical optimization (M., “Nauka”, 1981).

7. R. Courant, G. Robbins. "What is mathematics?" (M., “Enlightenment”, 1967).
