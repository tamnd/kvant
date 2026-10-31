---
id: 2021-4-zlatopolskiy-byivayut-li-otritsatelnyie-tsifryi-e2197ae1
issue: kvant_2021_4
year: 2021
number: "4"
title: Are there negative numbers?
authors:
  - Златопольский Д. М.
rubric: iz-istorii-nauki
rubric_sub: Из истории науки
page_first: 13
page_last: 17
page_labels: 14-15
tag: A19D
lang: en
source: kvant_digital
extraction: native
content_sha256: 9b5d62b5f4b2d92a2403591cc7e4bc5aab1e3695f8f9bbdc30eb696a6450aa2b
prompt_sha256: draft-1
translated_from: content/ru/2021/04/articles/02_zlatopolskiy-byivayut-li-otritsatelnyie-tsifryi-e2197ae1.md
source_content_sha256: 943583e1a214a0ffeaf145344c94e1b6f98928e73bfffe41fb9cfa99581f6eb3
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

AND HISTORY OF SCIENCE

Are there negative numbers?

D.ZLATOPOLSKY

What are negative numbers

Oddly enough, the answer to the question posed in the title of the article: “Yes, they do!” The use of negative numbers was first proposed by the English mathematician John Colson in 1726 in his article “A Summary of Negative-Positive Arithmetic” [1]. To distinguish negative numbers from “ordinary” ones, he proposed denoting them with a dash above the number. Thus, at the beginning of the article, the scientist gives the number 3709286573961472 and further shows that it corresponds to the “ordinary” number 2308726432039468, although the given example does not quite correspond to the goal that, as Colson himself writes, he sets by introducing negative numbers. And this goal is to simplify arithmetic operations on large numbers by eliminating the use of “large” numbers 6, 7, 8 and 9 and replacing them with values ​​​​with negative numbers 14, 13, 12 and 11. Here 14 10 4, the same as 14 10 4 (similarly for 13, 12, 11). In the following, Colson gives an example of such a transformation - instead of the number 181937462, use the number $22 2 143542.^{1}$ in calculations

Easier to fold

Showing the advantages (in his opinion) of his system, Colson gives the following example of adding several numbers:

1 Of course, Colson describes in the article the rules for converting numbers with the digits 6, 7, 8 and 9 to numbers with negative digits and vice versa.

DOI: https://doi.org/10.4213/kvant20210402

⟦column⟧

It can be seen that if the terms were presented in ordinary decimal notation, then it would be necessary, for example, to add the numbers in the last digit

3 8

7 1

8 6

5 while in the above version you need to add the numbers

3 2

3 1

2 4

5 which, of course, is simpler (and also reduces the likelihood of error).

⟦folio 14⟧

KVANT 2021/№4

let it be 1. Then the last equality can be written as 2 $3^{m} 3^{m} 1 1$ $3^{m}$. This means that any integer K can be represented in the ternary number system using the numbers 0, 1 and 1 (replacing all the digits 2 in its expanded notation with the corresponding difference):

K

$b_{m} ^{3} m b_{m} 1 ^{3} m^{1}$ … $b_{1} ^{3} b_{0}$, where each of the coefficients $b_{m}, b_{m} 1$, …

$..., b_{0}$ can be equal to 0, 1 or 1. This way of writing numbers is called the “ternary balanced system $счисления».^{2}$ So, if we know how the mass of the load K is written in this system, then in order to balance it on the scales, we need to put it on the first pan of the scales, and put a weight of 1 g on the second cup, if $b_{0} 1$, and on the first cup, if $b_{0} 1$ (if $b_{0} 0$, then the 1 g weight is not used at all); further, a weight of 3 g is placed on the second cup if $b_{1} 1$, and on the first if $b_{1} 1$, etc. It is easy to understand that by arranging the weights according to this principle, we will balance the load. Before giving an example, we will show how to convert ordinary ternary notation into notation in the balanced ternary system. To do this, you need to perform the following steps for each two: 1) replace it with the number 1; 2) add 1 to the digit adjacent to the left (if the result in this digit is 2, then the specified actions are repeated for it). For example, the number 130, which is usually written in the ternary system as 11211, in the second version will have the form

5

4

111111 ( 3 3 3 3 3 3

3

2

1

0

130 ).

Thus, to balance a 130 gram load placed on one of the

2 Such a system was first described by the French engineer Leon Lalanne in 1840. He gave the first few natural numbers in this system:

1, 11, 10, 11, 111, 110, 111, 101, 100, 101, 111, …

⟦column⟧

cups of scales, you need to put weights of 81, 27 and 9 grams on the same cup, and weights of 243, 3 and 1 grams on the opposite cup. The balanced ternary number system helped us in solving the problem.$^{3}$ In conclusion, we note that the “most real” example of the use of negative numbers is the electronic computers $«Сетунь»^{4}$ and “Setun 70”, developed, respectively, in 1960 and 1970 at the Lomonosov Moscow State University under the leadership of Nikolai Petrovich Brusentsov (1925–2014). Their design and operation were based on a balanced ternary number system with the numbers 1, 0 and 1.[5]

More about the balanced ternary number system Donald Knuth, the author of the world-famous series of books devoted to basic algorithms and methods of computational mathematics, in his book [6, pp. 230–231] gives another method $перевода.^{5}$ It is as follows. 1. A number of only ones is added to a ternary number. For example, for $130_{10} 11211_{3}$:

2. From the resulting amount, the number of units used in the addition is subtracted (bitwise) (each digit of the minuend is reduced by 1):

3 For the first time, the connection between the problem of a set of weights and a balanced ternary system was pointed out by Luca in the book “Mathematical Entertainment” [4]. True, the scientist did not describe how to solve the problem for a specific weight value $груза.^{4}$ Setun is the name of the river flowing near $МГУ.^{5}$ The scientist calls the balanced ternary system “perhaps the most elegant of all number systems.”

⟦folio 15⟧

FROM

STORIES

The result coincides with that obtained in our article.

Exercises

1. Write down the ternary numbers in a balanced system: a) 210; b) 1202. 2. Write down the decimal numbers in the balanced ternary system: a) 17; b) 53.

Properties of the balanced ternary number system The balanced ternary number system has many very attractive properties. First, it makes it possible to express both positive and negative numbers in a consistent manner (as noted above, when using the binary system, negative numbers in a computer are represented in so-called “computer code”). In it, the sign of the number is determined by the first character in the notation of the number in this system: if it is equal to 1, then the number is positive, and if 1 (1), then it is negative. It is very easy to go to the opposite number by replacing 1 with 1 (1) and vice versa. In fact:

8 10

$101_{3} ; 8_{10}$

$101_{3}$.

This means that you can compare any two numbers as in the decimal system, comparing numbers from left to right. To round a real ternary number to the nearest integer, it is enough to discard its fractional part. This property is also quite obvious, since the largest possible positive fractional part 0.111... represents the sum 1 3 1 9 1 27 ..., which is always less than 1 2. Arithmetic operations in the ternary symmetric system are practically no more complicated than binary ones, and if we consider that in the case of signed numbers, binary arithmetic uses artificial codes, then it turns out that ternary arithmetic is even simpler. The operation of adding any number with zero

SCIENCE

⟦column⟧

results in the same figure. Adding 1 to 1 gives zero. And only the sum of two 1s or two 1s is formed by moving a digit of the same sign as the terms to the next digit and setting a digit of the opposite sign in the current digit. The complete addition table, which we will use for the usual “column” addition of numbers, has the form

Note. Entry 11 means that the result is 1 and another 1 is transferred to the next digit, entry 11 means that the result is 1 and another 1 is transferred to the next digit.

Let's add the numbers 412 and 181 in a balanced ternary system:

412 10

120021 3

1110111 3

181 10

20201 3

111101 3

It's easy to check that $1111001_{3}$

$593_{10}$.

Exercise 3. Find the sum of numbers in a balanced ternary system:

a) 10111 and 1101; b) 111011 and 11011. Present the results in the decimal system.

Subtraction is just as simple: to do this, just change the sign of the subtrahend to the opposite one and add the number with the minuend. Of course, “direct” subtraction can also be carried out. To do this, it is convenient to create a subtraction table. Let's discuss it, because when compiling such a table, a number of interesting results are obtained. There is nothing unusual for the following cases: 1) 0 0 0; 2) 1 0 1; 3) 1 1 0; 4) 0 1 1 (this follows from the rules of algebra and from the addition table given above); 5) 1 – 1 0 (for the same reasons).
