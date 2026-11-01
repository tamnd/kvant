---
id: 1978-10-vilenkin-sravneniya-i-klassyi-vyichetov-16d6670a
issue: kvant_1978_10
year: 1978
number: "10"
title: Comparisons and classes of deductions
authors:
  - Виленкин Н. Я.
rubric: osnovnye-stati
page_first: 6
page_last: 9
page_labels: 4-7
tag: IV5K
lang: en
source: kvant_digital
extraction: vision
content_sha256: 3b3392cbc0b59c169256349e0c3f219944043e4660ca59f8612500b839d2baf3
prompt_sha256: draft-1
translated_from: content/ru/1978/10/articles/04_vilenkin-sravneniya-i-klassyi-vyichetov-16d6670a.md
source_content_sha256: 8865151fe074bc06da9c47d854420831b22c9dcde401b1bf540421eebcd0a95e
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 4⟧

N. Vilenkin

Comparisons and classes of deductions

Many people who love mathematics are familiar with the following problem:

Monkey and nuts

Five travelers stopped for a while. They took with them a bag of nuts and a monkey. One of them woke up, went to the bag and divided the nuts into 5 equal parts, with one nut remaining. He gave the monkey a nut, ate his share and went back to sleep. Then the second traveler woke up and, not knowing about the action of the first, continued the same thing. Then the other three travelers did the same in turn. When the remaining nuts were divided into 5 equal parts in the morning, there was again a nut left for the monkey. How many nuts were there?

The whole difficulty of this problem is in the extra nuts; without them, the answer would be any number that can be divided six times without a remainder by 5, that is, any number that is a multiple of $5^6 = 15625$. And due to the fact that each time division occurred with a remainder, the problem was much more difficult to solve. I came up with a wonderful solution in school

childhood acquaintance of the English physicist Dirac. He decided to find the number of nuts that would ... not change during the described operation (dividing into five parts, allocating a nut to a monkey and giving one part). The reader undoubtedly said that there could not be such a number of nuts - it is clear that after this operation it should decrease. But the whole point is that Dirac did not limit himself to natural numbers. And then all he had to do was solve the equation $\frac{4}{5}(x-1)=x$. The root of this equation is the number -4. Therefore, the number -4 could be a solution to our problem, but in its meaning, of course, it is not suitable. But now it is clear how to get a positive answer: you need to add $5^6$ to the number -4 found by Dirac. Check that the answer 15 621 satisfies the conditions of the problem. However, it is also satisfied by every number of the form -4 + $5^6 \cdot k$, where $k$ is any natural number.

What are comparable numbers?

If we ignore the requirement for positive solutions, then any number of the form -4 + $5^6 \cdot k$, where $k$ is an integer, is a solution to the nuts and monkey problem. These numbers form a "two-way arithmetic progression" with the difference $5^6$ extending in both directions. They have one thing in common - when divided by $5^6$ they all give the same remainder 15,621.

⟦folio 5⟧

They also say about numbers in mathematics that they are comparable to each other modulo*) 15 625.

In general, the concept of comparability over some modulo $m \in \mathbb{N}$ can be defined in two equivalent ways:

About the limit 1. Integers $a$ and $b$ are said to be comparable modulo $m$ if their difference is divisible by $m$ without remainder.

About the limit 1'. Integers $a$ and $b$ are said to be comparable modulo $m$ if their remainders when divided by $m$ are oddnakovy*).

If the numbers $a$ and $b$ are comparable to each other modulo $m$, then they write like this:
$$a \equiv b \pmod{m}.$$
For example, $16 \equiv 30 \pmod{7}$, since the difference $16 - 30 = -14$ is divisible by 7, and $72 \neq 45 \pmod{8}$, since $72 - 45 = 27$ is not divisible by 8.

Arithmetic of remainders

All numbers comparable to the number 2 modulo 5 behave identically when divided by 5 - they give a remainder of 2. Let's combine these numbers into one set and call it the class of excises modulo 5. Let's denote this class by the same number 2, only to distinguish it from the number 2, we'll write it like this: $\bar{2}$. This means that $\bar{2}$ is not a number, but an infinite collection of numbers:
$$\bar{2} = \{... -8, -3, 2, 7, 12, ...\}$$
The class of targets is also determined according to any modulo $m$. Dividing by $m$ can result in $m$ different remainders: 0, 1, 2, ..., $m - 1$. Each of them has its own target class. The remainder $r$ corresponds to the elimination class $\bar{r}$, consisting of numbers of the form $r + km$, where $k$ is an integer:
$$\bar{r} = \{r + km \mid k \in \mathbb{Z}\}.$$
The entire set of $\mathbb{Z}$ integers falls into $m$ target classes modulo $m$. The set of all these classes is denoted by $F_m : F_m = \{0, 1, ..., m - 1\}$. When studying questions concerning divisibility by $m$, it is better to deal with the finite set $F_m$ than with the infinite set $Z$.

To solve divisibility problems, you must be able to perform argumentative operations on target classes. Let's start with addition. It is defined very simply - in each of the terms (recall that the class of targets is an infinite set of integers), it takes a representative and adds them, and then looks at which class of targets the sum falls into. It is called the sum of these classes. For example, let’s add up the target classes $\bar{4}$ and $\bar{5}$ modulo 6. To do this, choose a representative in them. In order not to think too long, let’s take the remainders $\bar{4}$ and $\bar{5}$ themselves, which gave the classes their name. Their sum is 9. But $9 \equiv 3 \pmod{6}$ and therefore $\bar{4} + \bar{5} = \bar{3}$. If the target classes are not in $F_6$, but in $F_8$, then the sum will be different: $\bar{4} + \bar{5} = \bar{1}$. And at $F_9$ $\bar{4} + \bar{5} = \bar{0}$.

To put an end to the question of adding up the classes of survivors, it is also necessary to prove that if other representatives are chosen, the sum will not change. This follows from the following theorem:

Theorem 1. If $a \equiv a_1 \pmod{m}$ and $b \equiv b_1 \pmod{m}$, then $a + b \equiv a_1 + b_1 \pmod{m}$.

Proof. Since $a \equiv a_1 \pmod{m}$, $a = a_1 + km$, where $k \in \mathbb{Z}$, and since $b \equiv b_1 \pmod{m}$, $b = b_1 + lm$, where $l \in \mathbb{Z}$. Therefore $a + b = a_1 + b_1 + (k + l)m$, where $k + l \in \mathbb{Z}$, and $a + b \equiv a_1 + b_1 \pmod{m}$.

We have reduced the addition of target classes to the addition of numbers. Therefore, the Vytsel classes are computative and associative, that is, $a + b = \bar{b} + \bar{a}$ and $(\bar{a} + \bar{b}) + \bar{c} = \bar{a} + (\bar{b} + \bar{c})$, adding the class $\bar{0}$ does not change the Vytsel class, that is, $\bar{a} + \bar{0} = \bar{a}$, etc.

Subtraction and multiplication of target classes are defined in exactly the same way - in the class one selects a representative and performs operations on them. And here the results do not depend on the choice

⟦folio 6⟧

ra representative (prove it yourself). Moreover, the following conditions are true:

If $P(x)$ is a polynomial with integer coefficients $u$ $a \equiv a_1$ (mod $m$), then $P(a) \equiv P(a_1)$ (mod $m$). Try to prove it yourself.

The properties of the subtraction and multiplication operations of the subtraction classes are also very similar to the properties of these operations for integers (with one exception; more on that below).

Divisibility task

Since classes of subtractions modulo $m$ are directly related to remainders when dividing by $m$, almost all problems in which one has to decide about the divisibility of numbers can be conveniently solved using comparison.

Example 1. Find the remainder when $212^{1978}$ is divided by 7.

Since dividing 212 by 7 leaves a remainder of 2, $212 \equiv 2$ (mod 7). It follows that $212^{1978} \equiv 2^{1978}$ (mod 7). Note now that $2^3 = 8 \equiv 1$ (mod 7). But 1978 = $659 \times 3 + 1$. This means that from $2^3 \equiv 1$ (mod 7) it follows that $2^{1978} = (2^3)^{659} \cdot 2 \equiv 1^{659} \cdot 2 = 2$ (mod 7). Therefore, when $212^{1978}$ is divided by 7, the remainder is 2.

Example 2. Let's derive the test for divisibility by 9.

Since $10 \equiv 1$ (mod 9), for any $k$ we have $10^k \equiv 1$ (mod 9). But then

$$a_0 \cdot 10^n + a_1 \cdot 10^{n-1} + \dots + a_n \equiv a_0 + a_1 + \dots + a_n \pmod{9}.$$

This means that the numbers $N = a_0 \cdot 10^n + \dots + a_n$ and $M = a_0 + \dots + a_n$ have the same remainders when divided by 9. In particular, $N$ is divisible by 9 if and only if the number $M$ (the sum of the digits of the number $N$) is divisible by 9.

Example 3. Let us prove that the square of any natural number is either divisible by 9, or we give a remainder of 1 when divided by 3.

Indeed, if $x \equiv 0$ (mod 3), then $x^2$ is divisible by 9. If $x \equiv 1$ (mod 3) or $x \equiv 2$ (mod 3), then $x^2 \equiv 1$ (mod 3), since $1^2 = 1$ and $2^2 = 4 \equiv 1$ (mod 3).

Example 4. Find the last digit of the number $7^{71}$

We need to find the remainder when dividing the number $7^{77}$ by 10. But $7^2 = 49 \equiv -1$ (mod 10), and therefore $7^4 \equiv (-1)^2 \equiv 1$ (mod 10). Let's find the remainder of dividing the exponent $7^7$ by 4. Since $7 \equiv -1$ (mod 4), $7^7 \equiv (-1)^7 \equiv -1 \equiv 3$ (mod 4), and therefore $7^7 = 4m + 3$. Therefore, $7^{77} = (7^4)^m \cdot 7^3 \equiv (-3)^3 \equiv -27 \equiv 3$ (mod 10). This means that the numbers $7^{77}$ and 3 have the same last digit, that is, $7^{77}$ ends with 3.

Division of subtraction classes

To divide the subtraction class $\bar{b}$ into the subtraction class $\bar{a}$ means to find a subtraction class $\bar{x}$ such that $\bar{ax} = \bar{b}$. For integers, the division problem is not always solvable, but it can already be solved in a unique way. This is due to the fact that the product of two integers is equal to zero only in the case when at least one of the factors is equal to zero. But in $F_m$ it is divided differently. Looking at the multiplication table for $F_6$, we note that zeros are built in it not only in the first row and first column (where one of the factors is equal to zero).

The product $\bar{2} \cdot \bar{3}$, $\bar{3} \cdot \bar{4}$ is also equal to zero, although the factors are non-zero. As they say, $F_6$ has zero divisors (the subtraction class $\bar{a}$ is called a zero divisor if it is different from 0, but there is a class $\bar{b} \neq \bar{0}$ such that $\bar{a} \cdot \bar{b} = \bar{0}$). In $F_6$ the zero divisors turn out to be relatively prime with model 6. This suggests the validity of the following theorem:

| | $\bar{0}$ | $\bar{1}$ | $\bar{2}$ | $\bar{3}$ | $\bar{4}$ | $\bar{5}$ |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $\bar{0}$ | $\bar{0}$ | $\bar{0}$ | $\bar{0}$ | $\bar{0}$ | $\bar{0}$ | $\bar{0}$ |
| $\bar{1}$ | $\bar{1}$ | $\bar{2}$ | $\bar{3}$ | $\bar{4}$ | $\bar{5}$ | $\bar{5}$ |
| $\bar{2}$ | $\bar{0}$ | $\bar{2}$ | $\bar{4}$ | $\bar{0}$ | $\bar{2}$ | $\bar{4}$ |
| $\bar{3}$ | $\bar{0}$ | $\bar{3}$ | $\bar{0}$ | $\bar{3}$ | $\bar{0}$ | $\bar{3}$ |
| $\bar{4}$ | $\bar{0}$ | $\bar{4}$ | $\bar{2}$ | $\bar{0}$ | $\bar{4}$ | $\bar{2}$ |
| $\bar{5}$ | $\bar{0}$ | $\bar{5}$ | $\bar{4}$ | $\bar{3}$ | $\bar{2}$ | $\bar{1}$ |

⟦folio 7⟧

Theorem 2. The residue class $a$ in $F_m$ is not a zero divisor if and only if $a$ and $m$ are coprime.

Proof. Let $a$ and $m$ be relatively prime. If $a \cdot b = 0$, then the number $ab$ is divisible by $m$. But, due to the mutual simplicity of $a$ and $m$, this can only be the case when $b$ is divisible by $m$, that is, $b = 0$. This means that $ab = 0$ is only for $b = 0$, that is, that $a$ is not a divisor of zero.

Suppose now that the most common divisor of the numbers $a$ and $m$ is different from 1, $a = a_1d$, $m = m_1d$, $d > 1$. then the number $m_1 < m$ is an integer, and different from $m$, and therefore $m_1 \neq 0$. But $am_1 = a_1dm_1 = a_1m$, that is $am_1 = 0$. So $a$ is a zero divisor.

If the number $a$ is coprime to the model $m$, then all numbers from the residue class $a$ are coprime to $m$. In this case, the class $a$ is said to be coprime to $m$.

Theorem 2 implies the important Corollary 1. If the residue class $a$ is coprime to $m$, then $F_m$ can be uniquely divided by $a$, that is, for any $b \in F_m$ the equation $ax = b$ has one and only one solution.

First we prove that this equation cannot have different solutions. If $ax_1 = b$ and $ax_2 = b$, then $a(x_1 - x_2) = 0$, and since $a$ is not a zero divisor, then $x_1 - x_2 = 0$, that is, $x_1 = x_2$. This means there can only be one solution.

It remains to show that a solution exists.

We have just proved that the means of the residue classes $a \cdot 0, a \cdot 1, \ldots, a(m-1)$ are not identical. This means that these are the same classes $0, 1, \ldots, m-1$, only perhaps taken in a different order. And then for any class $b$ there is a class $x$ such that $a \cdot x = b$.

The proven corollary can be confirmed by the multiplication table using the model $6$ - it shows that only in the rows for classes $1$ and $5$ are all classes of residues found. Other lines contain only part of the classes: in the lines for $2$ and $4$ there are classes $0, 2, 4$, and in the line for $3$ there are classes $0$ and $3$. It is easy to understand how things work in the general case:

Corollary 2. If $(a, m) = d^*$, then the equation $ax = b$ has a solution only if $b$ is divisible by $d$. In this case, the solution number is $d$.

We leave it to the reader to prove this statement.

In the case where the model equation is a prime number, it can be divided into any non-zero residue class - in this case, all such classes are coprime to the model. Therefore, for example, in the multiplication table according to model 5, one row consists of zeros, and the rest contain all classes of residues once each.

Fermat and Euler's theorems

In number theory, the so-called Fermat's Little Theorem is very often used:

Theorem 3. If $p$ is a prime number and $a$ is not divisible by $p$, then the remainder when $a^{p-1}$ is divided by $p$ is 1.

In another way it can be formulated as follows:

Theorem 3'. If $a$ is a non-zero residue class according to the simple model $p$, then $a^{p-1} = 1$.

Proof. Since $0 < a < p$ and model $p$ is a prime number, then $a$ and $m$ are coprime. Therefore the residue classes $a \cdot 1, a \cdot 2, \ldots, a(p-1)$ are the same as $1, 2, \ldots, p-1$, only

$*)$ $(a, m)$ is the most common divisor of the numbers $a$ and $m$.
