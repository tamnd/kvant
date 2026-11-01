---
id: 1986-12-galperin-korlyukov-binarnyiy-algoritm-eeb74fbf
issue: kvant_1986_12
year: 1986
number: "12"
title: Binary algorithm
authors:
  - Гальперин Г. А.
  - Корлюков А. В.
rubric: raznoe
rubric_sub: Разное
page_first: 42
page_last: 43
page_labels: 40-41
tag: MPKG
lang: en
source: kvant_digital
extraction: vision
content_sha256: a59840030dab183ff736c735f7184b1654c5a033de927270613d9c9298c4d99b
prompt_sha256: draft-1
translated_from: content/ru/1986/12/articles/13_galperin-korlyukov-binarnyiy-algoritm-eeb74fbf.md
source_content_sha256: 18f8acb2c4da033c5326c1703d6d32c14c07a16da3867c9f4ae7974ec317803c
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 40⟧

Binary algorithm

Candidate of Physical and Mathematical Sciences
G. A. GALPERIN,
PhD in Physics and Mathematics
A. V. KORLYUKOV

Euclid's algorithm for finding the greatest common divisor (GCD) of two numbers is outlined in the next book of his Elements (circa 300 BC). Many scholars suggest that it is an interpretation of the algorithm proposed by Evdkocom (circa 375 BC). One way or another, the Euclidean algorithm can be called the “grandfather” of all algorithms, since it is the very first non-trivial algorithm, which remains to this day *. This part could, perhaps, describe the calculation methods for solving certain systems of quadratic equations with two unknowns, which appeared one and a half millennia before Euclid. However, they do not stand out in comparison with Euclidean's algorithm because they do not contain iteration and because they were derived from modern algebraic methods.

As stated in the article cited in the list, “Most ancient algorithms have over time been crowded out of computing practice by newer algorithms. The Euclid algorithm avoided this part primarily due to its parsimony.” It is all the more surprising that although the venerable Euclidean algorithm is used for pillar tables, it (as will be shown below) is not always the best way to find GCD!

Around 1962, Roland Silver and John Terzan discovered a completely different algorithm for finding GCD, which is primarily suitable for double arithmetic. This new “binary” algorithm does not need commands that require (as in the Euclidean algorithm) the execution of an action, much less an action with a remainder. Based on subtraction operations, the binary algorithm also checks whether a number is even or not and shifts the double representation of the even number to the right (thereby performing a halving).

The binary algorithm is very simply implemented on microcalculators and this differs favorably from the Euclidean algorithm. Note that the implementation of the Euclidean algorithm on microcalculators is difficult: the main difficulty is the absence of division operations with a remainder of two integers. For example, among the 300 programs given in the reference book by V.P. Dyakonov*) there is no Euclidean algorithm. Let us also note that there is no generally accepted designation in the school for the remainder of division; Perhaps for this reason, in the textbook on information for the 9th grade, when writing the Euclid algorithm, it is proposed to replace division with a remainder with sequential subtractions.

Let's move on to a description of the binary algorithm for finding the greatest common divisor of two integers. It is based on the following three evaluative properties of GCD:

1. GCD (2m, 2n)=2·GCD (m, n).
2. GCD (2m, 2n+1)=GCD (m, 2n+1).
3. GCD (m, n)=GCD (m−n, n). By definition of GCD, GCD (m, n)=GCD (n, m), GCD (−m, n)=GCD (m, n), GCD (0, 0)=0, GCD (m, 0)=|m|. From properties 1 - 3, an algorithm is immediately obtained, which we will describe verbally, explaining it using the example of finding the gcd of the numbers 40,902 and 24,140.

Suppose we need to find gcd (m₀, n₀); let's denote it d. By property 1, we first select the largest power of two 2ᵉ, which divides both m₀ and n₀, as well as the number d (for numbers 40,902 and 24,140, ​​k=1 and 2ᵉ=2). Let's reduce m₀ and n₀ by 2ᵉ times, and remember the number 2ᵉ. We get two numbers (20,451 and 12,070), one of which (or both) is odd (our number 20,451 is odd), and the gcd of these numbers is d₁=d/2ᵉ. Then, if one of these numbers is even (12,070), then divide it by the maximum possible power of two, leaving the second number of changes, and as a result we get two odd numbers m and n

*) For more information about the Euclidean algorithm, see the article by S. A. Abramov in «Kvant», 1985, No. 11, p. 44.

⟦folio 41⟧

(20,451 and 6,035) with gcd (m, n) = d₁. After these operations, we came to the problem of finding GCD only for odd numbers. To solve it, we will use property 3. We will subtract the smaller number from the large number (20451-6035=14,416), without changing GCD = d₁, and since the difference of odd numbers is always even, we will apply property 2: we will reduce this difference by the maximum power of two (in the example by 2²), again obtaining an odd number (901). Then again we use property 3 (6035-901=5134) and one or more times property 2 (5134:2=2567), so again properties 3 and 2, and so on (2567—901=1666→833→901—833=68→17→833—17=816→51→51—17=34→17). After each operation, the GCD does not change, but at least one number of the pair decreases. Therefore, at some points both numbers will become equal to each other; it is obvious that both of them will be equal to d₁ at this moment. The desired gcd (m₀, n₀) is then calculated as the product of the numbers 2ᵏ and d₁. (For our numbers GCD (40902, 24140)=2·17=34.)

In the given binary algorithm, only the operations of subtraction and division by 2 were used. The latter is especially simple if m and n are written in the double number system.

In educational algorithmic language, this algorithm can be written as follows*):

alg binary (integer m, n, k, r, s, d)
apr m, n
res d
start r:=0, s:=0
while m≠n
not yet m is even
neither m:=m/2
r:=r+1
kts
as long as n is even
neither n:=n/2
s:=s+1
kts
k:=min {r, s, k}
while m>n
neither m:=m-n
kts
while n>m
neither n:=n-m
kts
d:=2ᵏ·m

con

*) If k is not defined, when finding min {r, s, k} we assume that min {r, s, k} = min (r, s). This little trick allows you to determine k once and for all: with a further increase in r and s, it does not change.

This program can be easily translated into the Robik or Basic languages ​​or translated into codes for a programmable microcalculator such as BZ-34 (see «Kvant», 1986, No. 2, 3).

Let's see how to organize calculations using a binary algorithm on a general (non-programmable) calculator. Let the given positive integers m and n; the calculation of d=gcd(m, n) then breaks down into the following steps.

1. We send the number m to the indicator and divide it in half k₁ times (k₁≥0) until we get an odd number m₁.
2. We send the number n to the indicator (at the same time m₁ is shifted to the memory cell) and divide it in half k₂ times (k₂≥0) until we get an odd number.
3. If the numbers in memory and on the indicator are equal, then the number on the indicator is doubled k times, where k=min {k₁, k₂}; the resulting number is d.
4. If the number on the indicator is less than the number in memory, then we swap them.
5. Let's do the subtraction.
6. Divides the number on the indicator in half until an odd number is obtained and returns to step 3.

It is surprising that even when manually finding the GCD of two multi-digit numbers (for example, four-digit numbers), the superiority of the binary algorithm over the Euclidean algorithm is manifested. It takes less, and there are practically no calculation errors: after all, only a reduced number is needed in the Euclidean algorithm, but each iteration is performed much more simply - there are no division steps at all. This simplicity allows you to significantly save time when finding GCD, as can be seen in the following example.

Euclid's algorithm
GCD (40902, 24140)=34
