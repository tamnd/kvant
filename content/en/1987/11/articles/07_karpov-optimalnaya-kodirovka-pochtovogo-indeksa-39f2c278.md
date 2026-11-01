---
id: 1987-11-karpov-optimalnaya-kodirovka-pochtovogo-indeksa-39f2c278
issue: kvant_1987_11
year: 1987
number: "11"
title: Optimal postal code encoding
authors:
  - Карпов Я. Ю.
rubric: raznoe
rubric_sub: Разное
page_first: 21
page_last: 22
page_labels: 19-20
tag: ZP92
lang: en
source: kvant_digital
extraction: vision
content_sha256: aac2865a0468b75fc0f0fd8b0ecf4ddac0e5a96c3d9c23d32cca3980b4ce2240
prompt_sha256: draft-1
translated_from: content/ru/1987/11/articles/07_karpov-optimalnaya-kodirovka-pochtovogo-indeksa-39f2c278.md
source_content_sha256: 22ed19f88d860a6aaf16e745685738177827c0d3f01589c2b372c13dd1a2bb88
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 19⟧

MATHEMATICAL
SCHOOLCHILDREN'S WORK

Here are two short notes written by ten-grade students Yaroslav Karpov from Leningrad (school No. 239) and Alexander Lobkovsky from Chernogodovka, Moscow region (school No. 82) on modern different topics. They are united by the fact that both articles are “computer-mathematical”: in them, mathematical reasoning makes it possible to obtain interesting observations only after connecting to a computer.

Optimal postal code encoding

Y. Y. KARPOV

I was faced with a question: why exactly this set of numbers (Fig. 1) is used on envelopes—after all, these encodings can be replaced by others. Let's see how many different sets we can come up with (Table 1). Total 2×4×3×2×2×2×3×2=1152 options.

In order to display the best of these sets, we must first select the criterion by which we will compare the sets. As you know, the codes used on envelopes are checked by machine. Therefore, the criterion for the optimality of a set should be precisely that with this set the machine will make fewer errors in sorting than with other sets.

To characterize different encodings of numbers, we introduce the term - the distance between two encodings. Distances must satisfy the following conditions:

1) The greater the distance between two encodings, the less likely it is that the machine will mistake one encoding for another.

2) The distance from encoding $A$ to encoding $B$ must be equal to the distance from encoding $B$ to encoding $A$.

These conditions satisfy the Hamming distance. In our case, this is the number of “mismatched” characters in the encodings, i.e. the number of mismatched sticks.

Example: Find the distance between encodings 5 ​​and 2 (Fig. 2). The distance between these encodings is 5, since these encodings have 5 non-matching sticks.

Let us denote by $p$ the basic error probability, i.e. the probability of the machine mistaking a stick for a “non-stick” or vice versa. Then the probability of correctly recognizing one stick is $1-p$.

Let us find, for example, the probability of accepting the number 6 as 0 (Fig. 3). To do this, it is necessary that 8 sticks and two spaces are understood correctly by the machine, and one stick is accepted as a space. The probability of this event is $p(1-p)^{8}$.

In general, given the distance of any digit automatically, the probability that this digit will be mistaken for another is equal to $p^{\gamma}(1-p)^{\alpha-\gamma}$, where $\gamma$ is the distance between these two Hamming encodings.

Given the automatic distance of one specific digit $i$, the probability that it will be mistaken for any other is equal to

$$\sum_{j=i}^{n} p^{\gamma,j}(1-p)^{n-\gamma},$$

where $r_{i,j}$ is the distance between the digits $i$ and $j$.

⟦folio 20⟧

Let's assume that all numbers occur equally in any of the places. Then the average probability of incorrect recognition of a digit is equal to

$$P = \frac{1}{10} \sum_{i=0}^{9} \sum_{j=0}^{p_{j,i,j}} (1-p)^{9-r_{j,i,j}}.$$

We will use this confidence as a criterion for the quality of the set: the lower it is, the “better” the set.

An enumeration of all 1152 code options based on this criterion was obtained on an ES-1035 computer. The search program was written in Fortran. In the program, all variants of digit recordings were encoded in the form of arrays consisting of 1 and 0, according to the following principle (Fig. 4): if in the digit recording there is a stick in a given place, then in the encoding in the place with the number indicated in the diagram, 1 will be written, if not, then 0.

Example: Let's encode the number 2, given in general form (as on envelopes):

$$0, 1, 0, 0, 1, 1, 0, 0, 1.$$

Encoding options for the number $i$ were written in the matrix $ki$, where the number of rows is 9, and the number of columns coincides with the number of encoding options.

For each value of the basic error probability $p$, all 1152 variants of sets were sorted out, their quality was assessed using the formula (*), and the best and second best ones were selected. To do this, a distance matrix was formed for each set, which was derived for the best set. Since encodings 8 and 0 have only one option each, these numbers were not sorted through and did not participate in the output.

The following results were obtained. With a confidence level of the base error within

$$0 < p \leq 0,3$$

The actual encoding turned out to be the same one that is used on envelopes (see Fig. 1). Since the actual error probability of the recognizing machine at the post office obviously lies in this limit, this set is the most important.

The second best quality in this range is the set shown at figure 5. The second set differs from the first in only two places, and the probability of error with this set is not much greater than with the best one.

At $p=0,4$ these sets are swapped.

When the confidence increases to 0.5, all the confidences become equal, so it is very likely that all sets will become the same.

Of course, I would have accepted if my program had identified a different set than the one accepted at the post office: I would then be able to offer to replace the accepted set with my own - a better one.

Alas! Probably, when the optimal set was selected at the post office, they solved the optimization problem in the same way as I did.

Editorial. To his materials published above, Y. Karpov attached printouts of the program (in Fortran) that implements the algorithms described in the article. The printouts give an idea of ​​the fairly high programming culture of the author of the article. They have clearly worded comments that make the programs easy to read. However, lack of space, as well as an unfortunate choice of language (Fortran is not included in the school computer science course) does not allow us to publish this part of the materials.

We ask authors of articles intended for computer use to search their listings; It is desirable that the programs be written in BASIC (or Rappa).
