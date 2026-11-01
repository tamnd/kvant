---
id: 1978-4-bartenev-nablyudeniya-v-matematike-e3ea24bf
issue: kvant_1978_4
year: 1978
number: "4"
title: Observations in mathematics
authors:
  - Бартенев Ф. А.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 42
page_last: 43
page_labels: 40-41
tag: J8Q9
lang: en
source: kvant_digital
extraction: vision
content_sha256: 8366d16647fa42fe9b96f2bf818ded829ea70afd0d717083e9db2310f1f02a8e
prompt_sha256: draft-1
translated_from: content/ru/1978/04/articles/15_bartenev-nablyudeniya-v-matematike-e3ea24bf.md
source_content_sha256: 6cafbbfa828ca346258563e0dc8b517d7de1b160398da7803b6b2ed61fbad30c
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 40⟧

F. Barmenev

Observations in mathematics

The properties of numbers known today were largely discovered through observation.

Leonard Euler

How are the laws of nature usually studied?

Physicists, chemists, and biologists conduct experiments. Then they examine the resulting measurement results, notice patterns, and draw certain conclusions.

Surprisingly, mathematicians often use observations, as well as natural ones, in their scientific work. In order to deeply understand even “school” mathematics and solve complex problems, you need to learn to observe in mathematics.

Here is one interesting fact from the history of science. The outstanding mathematician K. Gauss and A. Kolmogorov were offered similar problems in childhood: ten-year-old Gauss was asked to find the sum 1 + 2 + 3 + ... + 98 + 99 + 100, and six-year-old Kolmogorov was asked to find the sum 1 + 3 + 5 + ... + 95 + 97. Gauss solved his problem almost instantly, noticing that 1 + 99 = 2 + 98 = 3 + 97 = ... Kolmogorov, having calculated the sums 1 + 3, 1 + 3 + 5, 1 + 3 + 5 + 7, noticed that 1 = 1², 1 + 3 = 2², 1 + 3 + 5 = 3², 1 + 3 + 5 + 7 = 4², and also quickly found the answer.

How to solve this problem:

Find the last two digits of 311²²?

Should we really not calculate the 28th power of 311? Of course not! It is enough to note that the last two digits of the number 311¹ are 11, the numbers 311² are 21, 311³ are 31, ...; so the last two digits of 311²² are 81.

Let's consider another similar problem:

What two digits are the number 7⁵¹?

Let's first find the last two digits of the numbers 7¹, 7², 7³, 7⁴ and 7⁵. It is easy to see that 7¹ has only one digit - 7; let's write it like this: 07; 7² has 49, 7³ has 43 (the last two digits of the product 49 by 7), 7⁴ has 01, so 7⁵ has the last two digits again 07. We see that the last two digits of the powers of seven intersect, forming a so-called periodic sequence with a period of 4: 07, 49, 43, 01, 07, 49, 43, 01, 07, 49, ...

All that remains is to find the remainder when dividing the number 51 by 4 - it is equal to

⟦folio 41⟧

three, and see what two digits the cube of seven turns out to be: the numbers $7^{51}$ and $7^3$ have the same last two digits. So here's the answer: the last two digits of $7^{51}$ are 43.

Let's solve one more problem, different from the previous ones.

For which numbers is the inequality true:
$$|a| + |b| > |a + b|$$

Let's look at a few examples. To do this, fill in a few rows of the following table:

| a | b | |a|+|b| | |a+b| |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| -3 | 2 | 5 | 1 | | | |
| -7 | -1 | 8 | 8 | | | |
| 0 | -4 | 4 | 4 | | | |
| 4 | 0 | 4 | 4 | | | |
| 2 | 3 | 5 | 5 | | | |
| 7 | -1 | 8 | 6 | | | |

Looking at this table, it is no longer difficult to guess what the answer to the last problem should be: the sum of the abscimal values ​​of two numbers is greater than the abscimal value of the sum of these numbers only when these numbers differ from zero and have different values.

Of course, any “guess” or hypothesis needs strict mathematical proof. We leave this to our readers.

If you have figured out how to solve the first three problems, try solving three more problems yourself, a little later.

Task 1.
1. What digits cannot be the sums $1+2$, $1+2+3$, $1+2+3+4$, $1+2+3+4+...$?

2. There are 60 positive and negative units in a circle (and there are both). It is known that the product of any three consecutive numbers is -1. Find the sum of all numbers.

3. How many cuts will be required to cut a cube from a 3 cm side into cubes from a 1 cm side?

In conclusion, we advise the reader to avoid hasty conclusions from the observation results. To prove a statement, you need to make sure that it is true in every part of the merge; at the same time, in order to verify any statement, it is enough to show that it is not true in at least one particular case (as mathematicians say, bring a counterplier). Let us explain what we mean.

Consider a set of numbers of the form $m = n^2 + 3n + 1$, where $n$ is any natural number. For the values ​​$n = 1, 2, 3, 4$ and 5 we get $m = 5, 11, 19, 29$ and 41, that is, the first five values ​​of $m$ are prime numbers. Can we conclude that any element of our set will be a prime number (for any natural number $n$)? Of course not: already at $n = 6$ we get the composite value $m = 55$.

Task 2.
4. Let $A$ be the set of numbers of the form $6n-1$, and $P$ be the set of prime numbers. Is the statement: $A \subset P$ true or false if $n \in N$?

5. Is it true that for any integer $n$ the inequality $4n^2 + 40n + 99 > 0$ is valid?

Sometimes it is very difficult to find a counterpoint that defines a general statement. It happens that it is easier to prove the existence of the corresponding counterpter than to build it.

For example, it is obvious that if 100 schoolchildren received 101 terrads, and each student received at least one terrad, then there is a schoolchild who received two terrads.

The reasoning technique with which we reached the conclusion in the last example is called “Dirichlet Priitz” and is often applied to solving a problem. Let's use it to solve the following problem:

Prove that from 101 numbers you can choose two, the difference of which is divisible by 100.

In fact, when divided by 100, the remainder can result in one of the following numbers: 0, 1, 2, ..., 99 - these are different numbers. Therefore, for 101 numbers, there are sure to be two that give equal remainders when divided by 100. Therefore, their difference is divided by 100.

And finally, another problem based on the Dirichlet principle.

Task 6. There are 710,000 Christmas trees growing in the forest. There are no more than 100,000 Christmas trees on each tree. Prove that there are at least 8 fir trees in the forest with the same number of fir trees.
