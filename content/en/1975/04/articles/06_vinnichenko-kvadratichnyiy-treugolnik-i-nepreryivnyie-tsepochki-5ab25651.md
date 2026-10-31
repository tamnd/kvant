---
id: 1975-4-vinnichenko-kvadratichnyiy-treugolnik-i-nepreryivnyie-tsepochki-5ab25651
issue: kvant_1975_4
year: 1975
number: "4"
title: Quadratic triangle and continuous chains
authors:
  - Винниченко А. П.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 23
page_last: 25
page_labels: 21-23
tag: Q0LG
lang: en
source: kvant_digital
extraction: vision
content_sha256: 94eb50f51b721f761033025396470fe576190676c139d43f890f4ceee78985f6
prompt_sha256: draft-1
translated_from: content/ru/1975/04/articles/06_vinnichenko-kvadratichnyiy-treugolnik-i-nepreryivnyie-tsepochki-5ab25651.md
source_content_sha256: 891ec3bdeb0486fa5957b1936d0fc90082bd92a2860969664e8779b7744c5532
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 21⟧

Square triangle and continuous chains

A. P. Vinchienko

Probably, some readers referred to the Ulam spiral (it is described, for example, in M. Gardner’s book “Mathematical Access”). If someone knows nothing about this spiral, it doesn’t matter; here's her story. One day, the American mathematician Stanislav Ulam, attending some uninteresting meeting, wrote a spiral out of boredom on a piece of checkered paper, numbered the cells of this spiral and circled the prime numbers *). Ulam got the picture depicted in figure 1: the prime numbers in his spiral seemed to protrude along diagonals. Now we will talk about a different order of writing the natural series, in which the prime numbers are still placed as if on diagonals.

*) A natural number (not equal to 1) is called prime if it is divisible only by itself and one.

Let’s make a “square triangle”: write in the first line only one number - 1, in the second - the numbers from 2 to 4, in the third - the numbers from 5 to 9, and so on, declaring a line every time we get a square of some natural number (see Fig. 2). Thus, our first line ends with $1^2$, the second - $2^2$, the third - $3^2$ and so on (hence the name of the resulting figure - “square triangle”; prove that each line of a square triangle is exactly 2 cells longer than the previous one).

Let us now circle the prime numbers - just as we did on figure 3.

Have you noticed that here too the prime numbers “line up” along the diagonals (by the way, think about why they are not on all diagonals, but only after one - using

Fig. 1. Fig. 2.

⟦folio 22⟧

⟦figure⟧
Fig. 3.

⟦folio 23⟧

The only difference is the number 2)? But besides this, in our picture we have “continuous chains” stretching from the “hypotenuse” of the “triangle” to its “leg” - there are six such chains on figure 3. Let's write down the prime numbers along these chains:

2
3, 5
7, 11, 17
23, 31, 41, 53, 67, 83, 101
47, 59, 73, 89, ..., 227, 257
223, 251, 281, 313, ..., 1523, 1601

It turns out that all these numbers obey the same law:

The 1st chain is the value of the polynomial $x^2 + x + 2$ at $x = 0$ (at $x = 1$ we get $2^2$),
The 2nd chain is the values ​​of the polynomial $x^2 + x + 3$ at $x = 0,1$ (at $x = 2$ we get $3^2$),
The 3rd chain is the values ​​of the polynomial $x^2 + x + 5$ at $x = 1,2,3$ (at $x = 4$ we get $5^2$),
The 4th chain is the values ​​of the polynomial $x^2 + x + 11$ at $x = 3,4,5,...,8,9$ (at $x = 10$ we get $11^2$),
The 5th chain is the values ​​of the polynomial $x^2 + x + 17$ at $x = 5,6,...,14,15$ (at $x = 16$ we get $17^2$),
The 6th chain is the values ​​of the polynomial $x^2 + x + 41$ at $x = 13,14,...,38,39$ (at $x = 40$ we get $41^2$).

Polynomials of the form $x^2 + x + k$ were known to Euler; the formula $x^2 + x + k$ for $k = 2, 3, 5, 11, 17, 41$ gives prime numbers for all $x = 0, 1,...,(k-1),(k-2)$.

Thus, our continuous chains are the “tails” of the values ​​of the polynomials $x^2 + x + k$, where $k = 2, 3, 5, 11, 17, 41$. Are there longer continuous chains? This is unknown for now.

Let's return to our square triangle - transfer the “reshemo of Eramosthenes” to it (see «Kvant» No. 1 for 1974): take some natural number and cross out all the numbers divisible by it. We will get some kind of pattern; for example, for the number 2 it is a “chess” pattern (Fig. 4). For a three, the pattern is already the latter (see Fig. 5). However, there is a pattern to these values. So, if you make a square from cardboard with side 2 and cut out two squares from it, placed on figure with 6 crosses, then using such a stamp you can cross out all numbers divisible by 2 from the square triangle.

Really:

1) apply the stamp so that only the 1 is visible above it;
2) cross out the numbers in the answers;
3) move the stamp down, right or left two squares;
4) again cross out the numbers in the answers and so on.
