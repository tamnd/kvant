---
id: 1972-7-kordemskiy-tak-ili-ne-tak-deystvoval-ferma-87f020e9
issue: kvant_1972_7
year: 1972
number: "7"
title: Did Fermat act this way or not?
authors:
  - Кордемский Б. А.
rubric: osnovnye-stati
page_first: 13
page_last: 13
page_labels: "11"
tag: 8BRT
lang: en
source: kvant_digital
extraction: vision
content_sha256: 9e68950e2bc6b5791d12b9565149b4a704bea71b70d9f190ed9ff3650cb5a216
prompt_sha256: draft-1
translated_from: content/ru/1972/07/articles/05_kordemskiy-tak-ili-ne-tak-deystvoval-ferma-87f020e9.md
source_content_sha256: d7aeb4d713e20bb86f455f0f246642fbcd3d1bc67885cc2cdc201e0383f357dd
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 11⟧

Did Fermat act this way or not?
(about factorization of numbers)

B. A. Kordemsky

There are many secrets associated with the name of the famous Pierre Fermat. However, he received a letter asking: “Is 100895598169 a prime number?” Fermat immediately responded that this twelve-digit number was the product of two prime numbers: 898423 and 112303.

He did not disclose the method for researching the number.

Finding prime factors of a natural number is called, for brevity, “factorization” (“factor” means a set of references to a word that is commonly used). Further, with such aids as electronic computers, factoring large numbers is an extremely labor-intensive task, all the more difficult to do it “manually.” The first few prime numbers (2, 3, 5, 7, 11, ...) are easily checked for their naturalness as possible factors of the test number - according to the known signs of divisibility by these numbers. Simplifies calculations and the meaning of the signs of divisibility by any of the subsequent prime numbers *).

It is also clear that for any given number $N$ it is sufficient to test prime numbers less than $V\overline{N}$ as possible factors. Indeed, if the number $N$ has a factor $m > V\overline{N}$, then it corresponds, as a result of dividing $N$ by $m$, and some factor less than $V\overline{N}$.

As a factorization technique, you can use the well-known Euclidean algorithm.

*) See, for example, the note on the criteria for divisibility by 19 and 7 in «Kvant» No. 6, 1970, p. 10.

clid to find the most common divisor (GCD) of two numbers. It consists, as you may remember, of the following *): we find the remainder $r_1$ from the division of a large number by a smaller number, then we find the remainder $r_2$ from the division of the previous divisor by $r_1$, then the remainder $r_3$ from the division of $r_1$ by $r_2$, etc. The subsequent non-zero remainder (it certainly exists, since the numbers $r_i$ are decreasing) and is the gcd of the given numbers (if it is equal to 1, then they are mutually prime).

For example, apply this algorithm to the numbers 104 and 39:

104 : 39 = 2 (remainder 26);
39 : 26 (remainder 13);
26 : 13 = 2 (remainder 0).

Answer: GCD (104.39) = 13.

How to apply the Euclid algorithm to factorization of numbers?

To identify prime factors of the number $N$, another number $P$ is formed - the product of all prime numbers from the smallest of the “suspected” factors of the number $N$ to the smallest among all primes, less than $\sqrt{N}$. We will apply the Euclidean algorithm to these numbers $N$ and $P$.

Let, for example, $N = 851$. We notice that $\sqrt{N} < 31$. We establish by divisibility criteria that $N$ is not divisible by 3, 7, 11, 13. In addition, it is immediately clear that 851 when divided by 17 leaves a remainder of 1. It remains to test the divisibility of $N$ by 19, 23 and 29. For such a small number as 851, this is easy to do by simple division

*) Justification and examples of the use of the Euclid algorithm are given in the article by A. N. Vilenkin “Reduction of algebraic fractions” («Kvant» No. 11, 1970) and Vaguten “Euclidean Algorithm and the Fundamental Theorem of Alphametic” («Kvant» No. 6, 1972).
