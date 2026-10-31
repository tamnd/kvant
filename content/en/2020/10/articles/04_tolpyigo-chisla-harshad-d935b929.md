---
id: 2020-10-tolpyigo-chisla-harshad-d935b929
issue: kvant_2020_10
year: 2020
number: "10"
title: Harshad numbers
authors:
  - Толпыго А. К.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 36
page_last: 36
tag: YVLH
lang: en
source: kvant_digital
extraction: native
content_sha256: 932f4e452373d9ce01fd770f891daf1c8d01ebda6b164193a22948646e9e1582
prompt_sha256: draft-1
translated_from: content/ru/2020/10/articles/04_tolpyigo-chisla-harshad-d935b929.md
source_content_sha256: 91d8c663b0c04b6e6c7cb1aead2abc1b5cfe512d7fd2af297c6eb135eaaa7359
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

MATHEMATICAL CIRCLE

Harshad numbers

A. TOLPYGO

THE RANGE OF TASKS CONSIDERED in this article can be described in one phrase: How often does it happen that a number is divided by the sum of its digits? It turns out that this simple question leads to a whole cycle of quite diverse problems. Numbers with this property are called Niven numbers, or Harshad numbers (from the Sanskrit “harsha” - great joy); this name was given to them by the Indian mathematician D.C. Kaprekar; For brevity, we will call them X-numbers. Since single-digit numbers are obviously such, we will immediately agree that we are considering only those X-numbers that have at least two (or even better, at least three) digits. Let's start with the obvious fact that all numbers with a sum of digits of 3 or 9 are Harshad. It is also easy to give examples of X-numbers with other small sums of digits; for example, these are all even numbers with a sum of digits of 2 or 6. It is not difficult to come up with other examples: these are the numbers 224, 605 or 999999999. But what if the sum of the digits is large? Is it always possible to construct such a number of Harshads? The answer is yes. Statement 1. For any natural m there is an X-number with a sum of digits m. Proof. Consider the numbers 1, 10, 100, …, $10^{k}$, … According to the Dirichlet principle, there is a remainder r such that an arbitrarily large number of these numbers give a remainder r when divided by m. Now it is enough to take the sum of m corresponding numbers $10^{k}$ for different such k (it is also possible for coinciding ones, but in the amount of no more than 9). Example 1. Let m 37. Since 999 is divisible by 37, then all the numbers $1, 10^{4}, 10^{7}$, ... $..., 10^{3k1}$ give the same remainder when divided by 37. Thus, we can take

DOI: https://doi.org/10.4213/kvant20201004

⟦column⟧

number 100100100...1 (and so on 37 times); but it’s easier to take, for example, the number 9009009009001. Note. Below we will prove a significantly stronger statement, namely: whatever m is, the fraction of X-numbers among all numbers with the sum of the digits m is greater than zero (tends to a limit that is greater than zero; a more precise formulation will be given below).

Long rows

Let us call a series of length k a sequence of numbers n, n 1, n 2, …, $n k_{–} 1,$ which are all Harshad. Since a series is always completely determined by its first term, in what follows we will, as a rule, write out only this one. It is not difficult to give an example of a series of length 3: it can, for example, begin with the number 110, since 111 and 112 are also X-numbers. (The numbers 1010, 10010, etc. are also suitable.) Is it possible to build a longer series? Statement 2. There is a series of length 10. To prove it, of course, it is enough to give an example (which we will do now), but it is interesting to know how to construct it. You can, of course, entrust the task to a computer (and this method leads to the goal), but then - where is the mathematics here? It would be very easy to construct an example if we were allowed to consider single-digit numbers (all numbers from 1 to 10 are divisible by the sum of their digits), but this is not allowed. However, it does suggest an idea: let the first number end in zero, and let the sum of its digits be equal to r. Then the following numbers will end in 1, 2, ..., 9, and their sums of digits will be r 1, ..., r 9. It would not be difficult to find a number (even with a given sum of digits, if only it is large enough) that is divisible by all these numbers, but we need not one number to be divisible, but successive ones. But this can also be done if you use this trick. Let's start with some “convenient” number (what exactly its “convenience” consists of will be seen later), which we will take as r, i.e. for the sum of the digits of the first of the numbers in our series. We will call this number the reference number. To begin with, let's take the number 30 as a reference. Let's assume that our first number ends with the numbers ...30 or,
