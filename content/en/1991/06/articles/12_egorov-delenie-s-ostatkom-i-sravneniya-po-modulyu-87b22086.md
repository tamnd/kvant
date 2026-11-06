---
id: 1991-6-egorov-delenie-s-ostatkom-i-sravneniya-po-modulyu-87b22086
issue: kvant_1991_6
year: 1991
number: "6"
title: Division with remainder and modulo comparisons
authors:
  - Егоров А. А.
rubric: shkola-v-kvante
page_first: 38
page_last: 42
page_labels: 36-40
lang: en
source: kvant_digital
extraction: vision
content_sha256: 6393f8d55ca0b9f49bceaadd9c595cac8269bb5ad8a4705408b1155002835d22
prompt_sha256: draft-1
translated_from: content/ru/1991/06/articles/12_egorov-delenie-s-ostatkom-i-sravneniya-po-modulyu-87b22086.md
source_content_sha256: 5c21f85f86170f232eb665af757702498220b5170c6e654a3aff8ae7bdd72e93
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 36⟧

Division with remainder and modulo comparisons

On September 3, 1990, I needed to find out what day of the week December 20, 1991 would be. I didn’t have a calendar at hand, so I had to do some calculations. I knew that September 3 is Monday, and from September 3, 1990 to December 20, 1991

27+31+30+20+365=473 days, i.e. 67 full weeks and 4 more days (473=67·7+4). Therefore, December 20th, 1991 is Friday.

By squaring a multi-digit number, the student received the answer 46,991,075. The teacher, looking at his notebook, immediately said: “The answer is incorrect!” How did he understand this?

Exercise 1. Think about whether the square of an integer could turn out to be the digits 75.

Later we will see that the solution to this simple problem and many others is based on divisibility messages. However, first we need to remember what division with a remainder is.

Division with remainder

Definition. Dividing a natural number a by a natural number b with a remainder means writing a in the form a=qb+r, where q and r are non-negative integers, and r<b. The number q is called the quotient, and a r is the remainder of dividing a by b.

In practice, division with a remainder is performed in a general way, i.e., “division by an angle.” For example:

$$\frac{179}{14} \frac{14}{12}$$

Here the remainder is 11 and the quotient is 12: 179=12·14+11.

Note that in this definition we do not require a to be greater than b. You can, for example, divide 5 by 7: 5=0·7+5. In general, if a<b, then a=0·b+a, i.e. in this case q=0, r=a.

Sweeping. You can define division with remainder of any integer a by any integer b≠0 as follows: to divide a by b with remainder means to represent a in the form a=qb+r, where q is an integer, a 0≤r≤|b|. For example, with a=-15, b=7: -15=(-3)·7+6; with a=-224, b=-9: -224=15·(-9)+1, etc.

If the remainder is zero, i.e. a=qb, a is said to be divisible by b.

The following simple observation is very important. If a and b are divisible by c, then for any integer k and l the number ka+lb is divisible by c.

⟦folio 37⟧

---
running_head:
folio:
---

Task 1. The numbers $7n+1$ and $8n+3$ are divisible by some natural number $d \neq 1$. Find $d$.

Solution. Since $7(8n+3) - 8(7n+1) = 13$, the number 13 is divisible by $d$, then $d = 13$ (since $d \neq 1$, and 13 is a prime number).

Do you get married?
2. Divide with the remainder
a) 1931 to 17; 6) - 295 to 31;
c) - 1005 to - 98.
3. The number $17x+3y$ is divisible by 61. Prove that $8x+5y$ is also divisible by 61 ($x$ and $y$ are integers).
4. Find remainders when dividing numbers
a) $n$ on $n-1$ and on $n-2$;
b) $n^2+n+1$ on $n+1$ and $n+2$;
c) $n^4+1$ to $n+3$ ($n \geqslant 80$).
5. Find all integers $n$ such that a) $\frac{n^2+1}{n-1}$ is an integer; 6) $\frac{n^5+3}{n^2+1}$.

Modulo comparisons
Let us immediately stipulate that all the numbers that will be discussed below will be integers, so that this will not be specifically stated in the future. Let's consider one more problem.

Task 2. What digit does the number $2^{999}$ end with?

Solution. Let's write down successive powers of two:
2, 4, 8, 16, 32, 64,...
It is easy to see that the last digits of these numbers are repeated after 4, so that the last digit of the number $2^n$ depends only on what remainder the exponent $n$ gives when divided by 4. Since $999=996+3=4 \cdot 249+3$, the answer in our problem is: 8.

In this example, the entire set of exponents was divided into 4 classes, consisting of numbers $n$ of the form $4k, 4k+1, 4k+2, 4k+3$.

Moreover, for any natural number $m$ all integers (not only positive ones!) are divided into $m$ classes. Each class consists of numbers that give identical remainders when divided by $m$.

These are the classes:
0) numbers $a$ of the form $a=km$,
1) - a - a=km+1,
$m-1)$ — а — а=km+m-1.

It is clear that any number belongs to one of the above classes. In this case, the difference of any two numbers from the same class is divisible by $m$, but the difference of two numbers from different classes is not divisible by $m$.

Definition. If the difference of the integers $a$ and $b$ is divisible by the natural number $m$, then $a$ and $b$ are said to be comparable in modulus.

The comparability of numbers modulo $m$ is written as follows:

$a \equiv b(\text{mod } m)$.

The numbers $a$ and $b$ are comparable modulo $m$ if and only if they belong to the same class, that is, they give the same remainders when divided by $m$. In other words, $a \equiv b(\text{mod } m)$ means $a=b+km$, where $k$ is an integer. For example, $27 \equiv 7(\text{mod } 10)$, $78 \equiv 6(\text{mod } 24)$, $6 \equiv 0(\text{mod } 3)$, $25 \equiv -4(\text{mod } 29)$.

Do you get married?
6. Prove that
a) $a^3 \equiv a(\text{mod } 6)$, 6) $a^4 \equiv a(\text{mod } 5)$.
7. Prove that the number $a(a+1)...(a+k-1)$ is an integer.

8. Prove that $2^{100} \equiv 3^{100}$ modulo 5, 13, 211.
9. Prove that $11^{10} - 1$ is divisible by 100.
10. Let $S(N)$ be the sum of the digits of the number $N$. Prove that $N \equiv S(N)$ mod 3 and 9.
11. Let $S(A)=S(5A)$. Prove that $A \equiv 0(\text{mod } 9)$.
12. Some numbers are written in the decimal system using 1991 ones and some zeros. Can they be a perfect square?
13. Using the fact that $10 \equiv -1(\text{mod } 11)$, prove a test for the divisibility of a number by 11: the number $a=a_na_{n-1}...a_0 \equiv 0(\text{mod } 11)$ if and only if $(-1)^n a_n + (-1)^{n-1} a_{n-1} + ... + a_0$ is divisible by 11.

Comparison properties
Comparisons fill general equalities with their properties:
1) if $a \equiv b(\text{mod } m)$ and $b \equiv c(\text{mod } m)$, then $a \equiv c(\text{mod } m)$.
2) $a+c \equiv b+d(\text{mod } m)$.
3) $a-c \equiv b-d(\text{mod } m)$.
4) $ac \equiv bd(\text{mod } m)$.
that is, comparisons, like general equalities, can be added, subtracted and variable.

⟦folio 38⟧

---
running_head:
folio:
---

Let us prove, for example, property 4. Since $a \equiv b$ and $c \equiv d$, then $a - b$ and $c - d$ are divisible by $m$.

From the equality $ac - bd = a(c - d) + d(a - b)$ it turns out that the number $ac - bd$ is divisible by $m$, i.e.

$$ac \equiv bd(\text{mod } m).$$

Exercise 14. Prove the remaining properties of the comparison.

Let $a \equiv b(\text{mod } m)$. From the already established comparison properties it follows
5) for any natural $k$
$$a^k \equiv b^k.$$

In addition, in some cases comparisons can be reduced by a common factor of the left and right sides:
6) if $ac \equiv bc(\text{mod } m)$ and the numbers $c$ and $m$ are coprime, then
$$a \equiv b(\text{mod } m);$$
7) if $a \equiv b(\text{mod } m)$, $k$ is an integer and $a = ka_1$, $b = kb_1$, $m = km_1$, then
$$a_1 \equiv b_1(\text{mod } m_1).$$

In other words, both sides of the comparison and the model can be divided by their common divisor. Let us prove property 6. The number $c(a - b)$ is divisible by $m$. Since $c$ and $m$ are coprime, the number $a - b$ is divisible by $m$. That's why
$$a \equiv b(\text{mod } m).$$

Exercise 15. Prove property 7.

From the above it follows that in any algebraic expression obtained from the integers $a, b, c, \dots$, $z$ using additions, multiplications and subtractions, you can replace these numbers with their remainders from division by $m$, without changing the remainder that this expression gives when divided by $m$.

Let us now solve the following problem.
Problem 3. Find the remainder when divided by 3 numbers
$$N = (1^2 + 1)(2^2 + 1)(3^2 + 1)...(1000^2 + 1).$$

Solution. From the above remark it follows that
$$N \equiv (1^2 + 1)^{333} \cdot (2^2 + 1)^{333} \cdot (3^2 + 1)^{333} \equiv 2^{333} \cdot 2^{333} \cdot 1^{333} \equiv 2^{666} \equiv (2^2)^{333} \equiv 1^{333} \equiv 1.$$

Problem 4. For what natural numbers $n$ is the number $8n + 3$ divisible by 13 (see Problem 1)?

Solution. Let us write, using the properties of comparison, the following integer correspondence:
Let $8n + 3 \equiv 0(\text{mod } 13)$, then
$$8n \equiv -3(\text{mod } 13),$$
$$8 \times 8n \equiv -24(\text{mod } 13),$$
$$-n \equiv -24 \equiv -11(\text{mod } 13).$$

Where $n \equiv 11(\text{mod } 13)$ is from.

Finally, $8n + 3$ is divisible by 13 if and only if $n = 13k + 11$.

Exercise 16. Find remainders when dividing numbers
a) $2^{1991} + 1$ by 17;
b) $(3^{20} + 11)^{55}$ on 13.
17. Prove that the number
a) $2^{50} + 1$ is divisible by 125;
b) $2^{48} - 1$ is divisible by 105.
b) $2^{3^n} + 1$ is divisible by $3^{n+1}$ and not divisible by $3^{n+2}$.
18. Find all prime numbers $p$ for which $20p^2 + 1$ is also a prime number.
19. Prove that the number
a) $1^{1991} + 2^{1991} + \dots + 30^{1991}$ is divisible by 31;
b) $1^m + 2^m + \dots + (n - 1)^m$ is divisible by $n$ for any odd $m$ and $n$.
20. For what natural numbers $n$ is the number $20^4 + 16^4 - 3^4 - 1$ divisible by 323?
21. Prove that the number $5^{2n+1} + 3^{n+2} \cdot 2^{n-1}$ is divisible by 19 for any natural number $n$.
22. At what $n$ will the fraction cancel?
$$\frac{15n + 2}{14n + 3}?$$

Chinese remainder theorem

Consider $m$ terms of the arithmetic progression
$$a, a + d, \dots, a + (m - 1) \cdot d,$$ (*)
where $a$ is an integer, $a$ is coprime to $m$. The following is often very useful

Theorem 1. Among the numbers (*) there is one odd, divisible by $m$.

Proof. The difference between the $k$-th and $l$-th numbers (*), equal to $d(k - l)$, is not divisible by $m$. Otherwise, it turns out that $k - l$ is divisible by $m$, which is impossible, since $|k - l| < m$.

Thus, the numbers (*) are pairwise incomparable modulo $m$ and therefore give a difference in remainders when divided by $m$.

Therefore, among the numbers (*) there are

⟦folio 39⟧

---
running_head:
folio:
---

all classes are set modulo $m$, i.e. for each of the remainders 0, 1, 2, ..., $m-1$ exactly one of the numbers (*) is comparable to it modulo $m$.

We have proved an even somewhat stronger statement than Theorem 1.
Exercises
23. Find all triples of primes of the form $p, p+2, p+4$.
24. Find a finite arithmetic progression with a maximum length difference of 6 and consisting of prime numbers.
25. Fifteen prime numbers form an arithmetic progression with difference $d$.
Prove that $d > 30000$.

Now we apply Theorem 1 to prove the so-called Chinese remainder theorem. This theorem was known more than 2000 years ago in ancient China.

Theorem 2. Let the data $n$ be pairwise coprime numbers $m_1, m_2, ..., m_n$ and numbers $r_1, r_2, ..., r_n$ such that $0 \leqslant r_i \leqslant m_i-1$ ($i=1, 2, ..., n$). Then there is a number $N$ that gives a remainder $r_i$ when divided by $m_i$.

In other words, $N \equiv r_i(\text{mod } m_i)$ for all $i=1, 2, ..., n$.

Proof. Let us apply induction by $n$. For $n=1$ the statement of the theorem is obvious. Let the theorem be valid for $n=k$. Then there is a number $M$ such that $M \equiv r_i(\text{mod } m_i)$ for $i=1, 2, ..., k$.

Let $d=m_1m_2...m_{k-1}$.

Let's look at the numbers
$M, M+d, M+2d, ..., M+(m_k-1)d$.

Since $d$ is coprime to $m_k$, it follows from the proof of Theorem 1 that among the written numbers there is a number $N$ that gives a remainder $r_k$ when divided by $m_k$. At the same time, when divided by $m_1, m_2, ..., m_{k-1}$, the number $N$ gives remainders $r_1, r_2, ..., r_{k-1}$, respectively.

The theorem has been proven.
And finally, one more theorem.
Theorem 3. For any pairwise coprime numbers $m_1, m_2, ..., m_n$ and remainders $r_1, r_2, ..., r_n$ modulo $m_1, m_2, ..., m_n$ there are $n$ consecutive numbers $a, a+1, ..., a+n-1$ such that $a \equiv r_1(\text{mod } m_1), a+1 \equiv r_2(\text{mod } m_2), ..., a+n-1 \equiv r_n(\text{mod } m_n)$.

In other words, for any pairwise coprime modules $m_1, m_2, ..., m_n$ there are $n$ consecutive natural numbers giving the corresponding any directed remainders when divided by these numbers.

Proof. By the Chinese remainder theorem, there is a $a$ such that
$a \equiv r_1(\text{mod } m_1),$
$a \equiv r_2-1(\text{mod } m_2),$
$a \equiv r_n-n+1(\text{mod } m_n)$.

But then the numbers $a, a+1, ..., a+n-1$ satisfy the conditions of the theorem.

Exercises
25. Prove that a) among any ten;
6) For any sixteen consecutive natural numbers there is a number that is coprime to the others.
c) is the statement of the problem true for any 17 consecutive natural numbers?
26. Prove that for any $n$ there are $n$ consecutive natural numbers, each of which is divisible by the square of some number.
27. Is there a moment in the day when the minute and second hands of a regularly running clock, located on the common axis of the clock, form angles of $120^\circ$ in pairs?
28. Find the smallest natural number that when divided by 2, 3, 5, 7, respectively, gives remainders 1, 2, 4, 6.
29. Find the smallest number $a$ such that $a+1$ is divisible by 3, $a+2$ is divisible by 5, $a+3$ is divisible by 7, $a+4$ is divisible by 11, $a+5$ is divisible by 13.

How comparisons are solved

If you remember, when solving Problem 4, we found all the integers $n$ for which $8n+3$ is divisible by 13.
In other words, we decided to compare
$8n+3 \equiv 0(\text{mod } 13)$.

Theorems we can solve this problem in general form. So, let the integers $a$ and $m$ be the product of each other.
Let's solve the comparison
$ax \equiv b(\text{mod } m)$, where $b$ is any number.
By Theorem 1, there exists $k$ such that $ak \equiv 1(\text{mod } m)$.
Multiplying the left and right sides of this comparison by $k$, we get

(For the ending see p. 49)

⟦folio 40⟧

---
running_head:
folio:
---

I accept that in the Universe... there is a known other other, then it loses so much of its movement that it cannot, cannot, and, thus,

R. Descartes
