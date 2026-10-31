---
id: 1974-9-bulavko-delimost-chisel-e814f52d
issue: kvant_1974_9
year: 1974
number: "9"
title: Divisibility of numbers
authors:
  - Булавко И. Г.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 72
page_last: 75
page_labels: 70, 72, 73
tag: E37E
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7b76308429b83146525070329873aa3fbda5f62fc31590e9b5c8af2691514cc3
prompt_sha256: draft-1
translated_from: content/ru/1974/09/articles/25_bulavko-delimost-chisel-e814f52d.md
source_content_sha256: f8d7f92fd2dc44fa109526f3f912db6cdb34a6910330eaaa4f98a4ba63c6e3ce
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 70⟧

I. G. Bulavko
Divisibility of numbers

You all know well what divisibility of numbers is. Do you know how to solve divisibility problems? These problems are often offered at mathematics Olympids and at entrance exams to mathematics schools. In this article, we take a closer look at several divisibility problems; For each task, advice is given that may be useful in solving other problems.

Let us recall the basic information from the theory of divisibility.

About the limit. Let $a$ and $b$ be integers and $b \neq 0$. We will say that $a$ is divisible by $b$, write it like this: $a \mid b$, or they say that $b$ divides $a$, and write: $b/a$ (accordingly, if $a$ is not divisible by $b$ (that is, $b$ does not divide $a$), written $a \neq b$).

Theorems
1) If $a$ is divisible by $b$, $b$ is divisible by $c$, then $a$ is divisible by $c$:
   $(a \mid b \text{ и } b \mid c) \Rightarrow (a \mid c)$.
2) If $a$ is divisible by $m$, then $m$ and $ab$ are divisible by $m$ ($b$ is any integer):
   $(a \mid m) \Rightarrow (ab \mid m)$.
3) If $a$ is divisible by $m$ and $b$ is divisible by $m$, then $m$ and $a + b$ are divisible by $m$:
   $(a \mid m \text{ и } b \mid m) \Rightarrow (a + b \mid m)$.

*) For the first time we will use Latin letters $a, b, c, d, \dots$ to denote integers; if the number is prime, we denote it by the letter $p$.

4) If $a + b$ is divisible by $m$ and $a$ is divisible by $m$:
   $(a + b \mid m \text{ и } a \mid m) \Rightarrow (b \mid m)$.
5) If $a$ is divisible by $m$, and $a$ is divisible by $k$, and $m$ and $k$ are coprime*), then $a$ is divisible by the product $mk$:
   $(a \mid m \text{ и } a \mid k \text{ и } (m, k) = 1) \Rightarrow \Rightarrow (a \mid mk)$.
6) If $ab$ is divisible by $m$ and $a$ mutually prime $c$ $m$, then $b$ is divisible by $m$:
   $(ab \mid m \text{ и } (a, m) = 1) \Rightarrow (b \mid m)$.

In what follows we will use these theorems without special reference to them.

Problem 1. If you assign the digit $6$ to the right of some direct number**) and multiply the resulting new number by $4$, you get the original number with the assigned digit $6$ in front. Find the best number.

Advice. Before solving a problem, write down (if possible, better) its text in mathematical language.

Solution.

$$\frac{\times \frac{abcde}{4}}{6abcde}.$$

When performing multiplication, sequentially find the digit of the desired number: $e = 4$, $d = 8$ and so on.

Answer. 615384.

Task 2. We wrote down four consecutive digits one after the other, then replaced the other two

*) They say that the number $a$ is coprime $c$ $b$ if the most common divisor of $a$ and $b$ is equal to 1. The most common divisor of the numbers $a_1, a_2, \dots, a_n$ is denoted by $(a_1, a_2, \dots, a_n)$. Then the fact that $a$ is coprime to $c$ is written as $(a, b) = 1$.

**) A multi-valued number, for example, $n + 1$-digit, is usually denoted as follows: $a_n a_{n-1} \dots a_0$, where $a_i$ ($i = 0, 1, 2, \dots, n$) are the digits of the number; numbers can also be denoted by the letters $a, b, c, \dots$

⟦folio 72⟧

are obtained from the formula $a = 5q + r$, that is, together with the equalities $a = 5q$, or $a = 5q + 1$, or $a = 5q + 2$, or $a = 5q + 3$, or $a = 5q + 4$, taking into account (2), we can write that $a - \text{либо } 5m$, or $5m \pm 1$, or $5m \pm 2$.

Obviously, this form of notation is more compact. (In the example above, we wrote $r = 3$ and $r = 4$ together as $(5 - r)$, that is, $-1$ and $-2$.) Solution. Let $a$ and $b$ be two numbers that satisfy the conditions of the problem. Let's find out what values ​​the remainders can take when dividing these numbers and their squares by 24. Let's represent the number $a$ as $a = 24q + r$, where $0 \leq r < 24$. Since $a$ is not a multiple of 2 and not a multiple of 3, then $r$ can only take the values 1, 5, 7, 11, 13, 17, 19, 23. Therefore, $a$ can be written in one of the forms: $a = 24m_1 \pm 1$, $a = 24m_2 \pm 5$, $a = 24m_3 \pm 7$, $a = 24m_4 \pm 11$. It is easy to verify that in any of these cases the remainder when dividing $a^2$ by 24 is 1.

Similarly, we obtain that $b^2 = 24n + 1$. Then $a^2 - b^2 = 24(m - n)$, that is, $a^2 - b^2$ is divisible by 24. Solution problem.

Exercise 3. Prove that the number $5q + 2$ is not a square of an integer for what value $q$.

Problem 5. Prove that $A = n^5 - 5n^3 - 6n$ is divisible by 10.

Advice. When solving a divisibility problem, the following theorem often helps: of $n$ consecutive natural numbers, one is divisible by $n$.

Prove this theorem yourself. State and prove similar theorems for $n$ successive odd numbers and $n$ successive even numbers (here it already exists whether $n$ is even or odd).

Solution. $A = n(n^4 - 5n^2 - 6) = n(n^4 - 5n^2 + 4) - 10n = n[(n^4 - n^2) - (4n^2 - 4)] - 10n = n(n^2 - 1)(n^2 - 4) - 10n = (n - 2)(n - 1)n(n + 1) \times (n + 2) - 10n$.

The product $(n - 2)(n - 1)n(n + 1)(n + 2)$ is divisible, according to the mentioned theorem, by both 2 and 5, that is, divisible by 10. But, this means that the entire difference (equal to $A$) is also divisible by 10, which is what needed to be proven.

Problem 6. Prove that the number $N = \underbrace{11 \dots 1}_{k \text{ цифр}} \underbrace{12 \dots 2}_{k \text{ цифр}} \underbrace{2 \dots 2}_{k \text{ цифр}}$ is the product of two consecutive natural numbers.

Advice. If a problem cannot be solved in a general form, consider several of its special cases and then try to move from them to the general case.

Solution. Note that $12 = 3 \cdot 4$, $1122 = 33 \cdot 34$, $111222 = 333 \cdot 334$.

It is natural to assume that in the general case $N = \underbrace{11 \dots 1}_{k \text{ цифр}} \underbrace{12 \dots 2}_{k \text{ цифр}} = \underbrace{33 \dots 3}_{k \text{ цифр}} \underbrace{33 \dots 34}_{k \text{ цифр}}$.

Let us prove equality (3). We have: $33 \dots 3 \cdot 33 \dots 34 = 3 \cdot 11 \dots 1 \times \times (33 \dots 3 + 1) = 11 \dots 1 \times \times (99 \dots 9 + 3) = 11 \dots 1 \times (10^k + 2) = 11 \dots 122 \dots 2$, which is what we needed to prove.

Problem 7. Prove that $A_n = 2^{n+2} \cdot 3^n + 5n - 4$ is divisible by 25 for any natural number $n$.

Advice. It is reasonable to prove such statements using the method of mathematical induction.

Solution. 1) For $n = 1$ the statement is true:

$A_1 = 2^3 \cdot 3 + 5 - 4 = 25$ is divisible by 25.

⟦folio 73⟧

2) Let us assume that the statement has already been proven for all $n \leq k$; Let's prove that it is also true for $n = k + 1$, that is, we prove that $A_{k+1}$ is divisible by 25. We have:

$$A_{k+1} = 2^{k+3} \cdot 3^{k+1} + 5k + 1 = 2 \cdot 2^{k+2} \cdot 3 \cdot 3^k + 5k + 1 = 6 (2^{k+2} \cdot 3^k) + 5k + 1 = 6 (2^{k+2} \cdot 3^k + 5k - 4) - 25k + 25 = 6A_k - 25 (k - 1)$$

is divisible by 25 because $A_k$ is divisible by 25 by induction hypothesis.

Therefore, $A_n$ is divisible by 25 for any natural number $n$.

Problem 8. An expressed number, which is a perfect square, has the following property: if all its digits are reduced by the same number, you get a whole digit of the number, which is also a perfect square. Find all integer digits of a number with the described property.

Advice. In some cases, it is advisable to try to solve the problem by selection. It should be remembered that the selection must be exhaustive, otherwise the problem cannot be considered solved.

Solution. It is given that

$$\frac{abcd}{(a-k)(b-k)(c-k)(d-k)} = B^2.$$

It's clear that

$$a \geq k, b \geq k, c \geq k, d \geq k.$$

Consider the difference $A^2 - B^2$:

$$A^2 - B^2 = (1000a + 100b + 10c + d) - [1000(a-k) + 100(b-k) + 10(c-k) + (d-k)] = 1111k,$$

that is

$$(A + B)(A - B) = 11 \cdot 101k.$$

Since $A^2$ and $B^2$ are integer digits, then $32 \leq A \leq 99$ and $32 \leq B \leq 99$; that means, in any case

$$64 < A + B < 200,$$

$$0 < A - B < 67.$$

It immediately follows that $A + B = 101$, $A - B = 11 \cdot k$. Razumma $A + B$ is an odd number, then the difference $A - B$ is an odd number. Therefore, $k$ must also be odd. Since $A - B < 67$, the following values ​​for $k$ may be suitable: 1, 3, 5. Only $k = 1$ and $k = 3$ are suitable.

Answer. a) $3136 = 56^2$; $2025 = 45^2$.

6) $4489 = 67^2$, $1156 = 34^2$.

And finally, the main advice: solve as many problems as possible, because contracts and ingenuity come only with experience.

Exercises

4. Prove that $A = m(m^2 - 7)$ is divisible by 6 for any natural number $m$.

5. Prove that if you add the same number to the right of any three-digit number, then the resulting six-digit number is divisible by 7, 11 and 13.

6. Find a two-digit number equal to the partial square of the sum of its digits.

7. Prove that a number consisting of $3^n$ units is divisible by $3^n$.

8. Prove that there are no integers $a, b, c$ satisfying the equalities: $abc + a = 3333, abc + b = 5555, abc + c = 7777$.

9. Prove that if $p$ is a prime number greater than 3, then $N = p^2 + 3n + 2$ is composite for any natural number $n$.

10. Prove that $S = 3 + 3^3 + 3^5 + \dots + 3^{4n-1}$ is divisible by 10.

11. Find a five-digit number that is 45 times the product of its digits.

12. Prove that the amount

$$\underbrace{11 \dots 1}_{m\text{ цифр}} \cdot \underbrace{100 \dots 5}_{m+1\text{ цифра}} + 1$$

is the square of a natural number.
