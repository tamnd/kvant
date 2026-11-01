---
id: 1987-4-stolyar-priznak-delimosti-na-chisla-vida-10n-1-aefb4d9e
issue: kvant_1987_4
year: 1987
number: "4"
title: Divisibility test for numbers of the form 10n ± 1
authors:
  - Столяр В. Г.
rubric: shkola-v-kvante
page_first: 41
page_last: 41
page_labels: "39"
tag: QWTZ
lang: en
source: kvant_digital
extraction: vision
content_sha256: 8c88b8d635babe11112a8c4f2b655052c4da2beb11d84e1307a5adbae2208fcf
prompt_sha256: draft-1
translated_from: content/ru/1987/04/articles/14_stolyar-priznak-delimosti-na-chisla-vida-10n-1-aefb4d9e.md
source_content_sha256: 8ef34f33f6576a4556236fcc3fb2034ba9f420e16770af83bac6015c339b3a4a
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 39⟧

Math 8, 9, 10

The note “Test of divisibility by numbers of the form 10n±1” published below is intended for eighth-graders, the note “The First Diplomat Limit” is for ninth- and tenth-graders, and the note “Viete’s Formulas” is for students in eighth-tenth grades.

Divisibility test for numbers of the form 10n±1

In 1884, in one of the issues of the “Journal of Elementary Mathematics” published in Kyiv, an article by the founder of the journal, Professor V.P. Ermakov, “Signs of divisibility of numbers” was published. The article showed the signs of divisibility described below by numbers of the form 10n±1.

To find out whether a given number N is divisible by the number m=10n+1, you need:
A. discard the last digit from the number N;
B. subtract from the resulting number the product of the discarded digit by n;
B. Perform operations A and B with the resulting number;
D. do this until (last operation B) there is a number less than or equal to 0 left;
D. if the remaining number is 0, then N is divided by m=10n+1; otherwise N is not divisible by m.
Let's prove it. If k is the last digit of N, then operations A and B turn N into a number
$$\frac{N-k}{10} - kn = \frac{N-k-10kn}{10} = \frac{N-km}{10}.$$
Obviously, this number is divisible by m if and only if N is divisible by m. Further operations reduce the number without changing its divisibility by m, which is where D follows.

Examples

$$N = 11934, m = 51:$$
$$11934 \rightarrow 1193 \rightarrow 1173 \rightarrow 117 \rightarrow 102 \rightarrow 10 \rightarrow 0$$

$$N = 15314, m = 61:$$
$$15314 \rightarrow 1531 \rightarrow 1507 \rightarrow 150 \rightarrow 108 \rightarrow 10 \rightarrow 38$$

We see that 11,934 is divisible by 51, but 15,314 is not divisible by 61.

Note that if, in the case of divisibility, we write the discarded digits in reverse order, we get partial
