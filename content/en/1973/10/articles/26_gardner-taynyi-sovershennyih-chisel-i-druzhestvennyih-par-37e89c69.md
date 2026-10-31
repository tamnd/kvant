---
id: 1973-10-gardner-taynyi-sovershennyih-chisel-i-druzhestvennyih-par-37e89c69
issue: kvant_1973_10
year: 1973
number: "10"
title: Secrets of perfect numbers and friendly pairs
authors:
  - Гарднер М.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 73
page_last: 76
page_labels: 71-74
tag: HSZ9
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1e8ab1abce4815e8969555e1a702d49e0e64737acabbcae0c42e1742e6bd2ab2
prompt_sha256: draft-1
translated_from: content/ru/1973/10/articles/26_gardner-taynyi-sovershennyih-chisel-i-druzhestvennyih-par-37e89c69.md
source_content_sha256: 40dbe9aa82619463d6fae6365f7265748a4bfb399f3c21b5c1c1f44784c2a475
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 71⟧

A. S. Varpakhovsky
Secrets of perfect numbers and other pairs

In the eighth issue of our magazine for 1971, a note by I. Ya. Delman was published on the history of the so-called perfect numbers - numbers equal to the sum of their divisors. In continuation of this topic, we post a revised article by M. Gardner *), which talks about the remarkable properties of these numbers. Publication for «Kvant» prepared by A. S. Varpakhovsky.

Please, no number has such a fascinating history as perfect numbers and their closest relatives - other numbers.

The first important step in constructing the theory of perfect numbers was taken by Euclid, who established that the formula $2^{n-1} (2^n-1)$ gives a perfect number whenever the factor in brackets turns out to be prime (for this it is necessary that $n$ be prime, although not for every prime number $n$ the number $2^n-1$ is also prime).

Here is the proof of Euclid's theory. Let the number $2^{n-1} (2^n-1)$ have a simple set in brackets. then the divisors of this number, different from the number itself, will be

$$1, 2, 4, \dots, 2^{n-1},$$
$$2 (2^n-1), 4 (2^n-1), \dots, 2^{n-2} \times (2^n-1).$$

Let's take the sum of all these divisors:

$$(1 + 2 + 4 + 8 + \dots + 2^{n-1}) + (1 + 2 + 4 + 8 + \dots + 2^{n-2}) \times (2^n-1) = (2^n-1) + (2^{n-1}-1) \times (2^n-1) = 2^{n-1} (2^n-1)$$

Therefore, the number $2^{n-1} (2^n-1)$ is perfect.

2000 years later, Leonhard Euler proved that Euclid's formula defines all even perfect numbers. It is curious that so far no one has been able to find an odd perfect number, and perhaps such a one does not exist at all. Therefore, in the future, when speaking about perfect numbers, we will mean even perfect numbers. Euclid's amazing formula is closely related to the general geometric progression with value 2 (1, 2, 4, 8, 16, . . .).

Let's remember the ancient story about the Persian king and the author of the chess game. Admired by this game, the king invited the author to choose his own chest. He, at first glance, expressed a very modest desire, asking to place one grain of wheat on the first cell of the chessboard, two grains on the second, four grains on the third, and in this way fill all 64 cells. It turned out that the number of grains in the last square is 9,223,372,036,854,775,808, and twice this number without 1 is equal to the total number of grains on the board, which is several thousand times the annual level of wheat throughout the world. Having written in each cell of the chessboard the number of grains that should be in it, and taking one grain from each cell, we will see that the remainder in the cell

⟦folio 72⟧

Fig. 1.

the number of grains in Euclid's formula is determined by the expression $2^n - 1$. If this number is prime, then multiplying it by the number of grains in the previous cell, that is, by $2^{n-1}$, we obtain a perfect number. (see Fig. 1).

Prime numbers in the series $2^n - 1$ are called Mersenne numbers after the 17th century French mathematician who studied them *). On

*) See also «Kvant», 1971, No. 8, p. 3.

In row 1, those cells are shaded in which, after subtracting 1, the Mersenne numbers are obtained. There are 9 such cells on the board - they correspond to the first two northern numbers.

Northern numbers have a number of mysterious and at the same time remarkable properties. For example, all perfect numbers are “triangular”. This means that if you take, say, a number of balls equal to a perfect number, then they can be arranged so that they form an equilateral triangle.

In other words, every perfect number is a sum of the form $1 + 2 + 3 + 4 + ... + n$.

It can also be easily seen that every perfect number, with the exception of 6, is a partial sum of the series of cubes of odd numbers $1^3 + 3^3 + 5^3 + ...$.

And here is another property of perfect numbers: the sum of the reciprocal values ​​of the divisor of a perfect number, including the number itself as a divisor, is always equal to 2. So, for the number 28 we have

$$\frac{1}{1} + \frac{1}{2} + \frac{1}{4} + \frac{1}{7} + \frac{1}{14} + \frac{1}{28} = 2.$$

Do today remain unanswered for important questions: is there an odd perfect number and is there a greatest even perfect number? Until cxx not a single odd perfect number has been found, but at the same time it has not been proven that such a number does not exist. The answer to the second question depends on whether the series of Mersenne primes is infinite, since each prime number in this series leads to a perfect number. It has been observed that by substituting the first four Mersenne numbers (3, 7, 31, 127) together with $n$ into the formula $2^n - 1$ the Mersenne numbers are again obtained. More than 70 mathematicians have found that such a pattern should lead to the conclusion that the series of Mersenne prime numbers is infinite. However, in 1953, a computer crushed their hopes. It was found that

⟦folio 73⟧

in the case of $n = 2^{13} - 1 = 8191$ (a Mersenne prime), the number $2^{8191} - 1$ is not prime. It is still not known whether the Mersenne series is infinite or whether it contains the largest number.

Ore, in his book The Theory of Numbers and Its History, quotes an amusing statement by Peter Barlow from his book The Theory of Numbers, which he wrote in 1811. Barlow, having calculated the nine-hundredth number, declared that “this is the most number that will ever be found, because perfect numbers are no more than curious and whether it would harm anyone to try to find a larger perfect number.” However, in 1876, the French mathematician Edward Luxas, author of a classic four-volume work on intricate mathematics, announced the discovery of the twelfth perfect number $2^{126} (2^{127} - 1)$. Luxas later doubted that $2^{127} - 1$ was a Mersenne prime, but its simplicity was later confirmed. $2^{127} - 1$ is the most Mersenne number found without the help of a computer. Table 1 shows expressions using the Euclid formula for 23 known perfect numbers, the first of all of them is written out (further numbers contain a list of many signs) and the number of decimal places for each of these numbers is indicated. The last known perfect number, which has 22,425 divisors, was born in 1963 after the University of Illinois computer discovered the 23rd Mersenne number. In honor of this event, the university’s mathematics department put a stamp on mail items with the inscription: “$2^{11213} - 1$ is a prime number.”

A generalization of perfect numbers is friendly numbers. Take any number and sum its divisors to get the second number. Then we add up the factors of the second number, and so on, in the hope that we will eventually arrive at the original number. If the original number is obtained in the first step, then the integer has only one link, and the number itself is perfect. With a two-part integer, two numbers form a friendly pair: the sum of the divisors of one of the numbers is equal to the other number. The smallest friendly numbers that form a pair are 220 and 284.

In 1636, Pierre Fermat found another friendly pair of numbers: 17,296 and 18,416. He and René Descartes independently worked on the correct formation of friendly pairs, not suspecting that this correct one was formed back in the 9th century by an Arab astronomer *. The third pair was found by Descartes: 9,363,584 and 9,437,056. In the 18th century, Euler published

*) A resident of the Potamian city of Harran - Abu-l-Hasan Sabit ibn Korra ibn Marwan al-Sabi al-Harrani (c. 830-901). (Editor's note)

⟦folio 74⟧

a list of 64 other pairs, however, as a later check showed, in two cases he was mistaken. In 1830, Adrien Marie Legendre found another other pair, and in 1867, the sixteen-year-old Italian youth V. I. Paganini surprised the mathematical world by announcing that the numbers 1184 and 1210 are other numbers. This was the second largest pair that everyone overlooked. And although Paganini may have found this pair by trial and error, his name went down in the history of number theory.

Today, more than 600 other pairs are known; many number pairs have more than 30 digits. The last known pair was calculated on a computer in 1964. Table 2 shows other other pairs in the range of numbers from 0 to 100,000.

All other known pairs consist of either two even numbers or (which is much less common) two odd numbers. But no one has proven that there is no other mixed pair. Bratley and McKay hypothesized that all odd other numbers are divisible by 3, and the sum of the numbers forming an other number pair is a multiple of 9. No one has yet proposed a general formula for all other number pairs, and it is not known whether the number of such pairs is finite or infinite.

Currently, only two chains of numbers are known that lead to the original number and have
