---
id: 1985-9-chislovyie-golovolomki-d018da65
issue: kvant_1985_9
year: 1985
number: "9"
title: Number puzzles
rubric: kaleydoskop-kvanta
rubric_sub: Калейдоскоп
page_first: 35
page_last: 37
page_labels: 34-35
tag: EW8H
lang: en
source: kvant_digital
extraction: vision
content_sha256: 22e14dcae6d05d774eb1f4630f5c30131e1306b7679a6c40d9ed9d80f3cbdfd4
prompt_sha256: draft-1
translated_from: content/ru/1985/09/articles/13_chislovyie-golovolomki-d018da65.md
source_content_sha256: e836a693758c66793df74c3a71db0f75fdeee3a7b674bbc8812e8a81c5200977
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio none⟧

shero prime number, which implies the infinity of the set of prime numbers and, of course, the set of natural numbers. Here is a poignant proof of this fact. Let $p$ be a prime number. Let's change all prime numbers up to $p$, including $p$ itself, and add one to this product. We get the number $2 \cdot 3 \cdot 5 \cdot 7 \cdot \dots \cdot p + 1$. This number greater than $p$ will be either prime or composite. If it is prime, then it is proved that there is a prime number greater than $p$. If it consists of prime numbers 2, 3, 5, ..., $p$ it is not divisible - when divided by these numbers the remainder is 1. This means that it must be divisible by a prime number greater than $p$. So, in this case too, we must admit that there is a prime number greater than $p$. But this also means that there is no simplest number.

The term "natural number" was first used by the Roman philosopher Boethius (c. 480-524), but became commonly used after it was included in the Encyclopedia by the French mathematician D'Alembert (1717-1783).
In the 19th century mathematicians

$$1 + 3 + 5 + \dots + (2n - 1) = n^2$$
$$1^2 + 3^2 + 5^2 + \dots + (2n - 1)^2 = \frac{1}{3} n (2n - 1)(2n + 1)$$
$$1 \cdot 2 + 2 \cdot 3 + 3 \cdot 4 + \dots + n (n + 1) = \frac{1}{3} n (n + 1)(n + 2)$$

Number puzzles

Crossumber
Horizontal:
a) A number whose digits are consecutive and arranged in ascending order; b) a number that is a multiple of 9; d) complete square; e) a number that is a multiple of 36.
Vertical:
a) A number whose digits are consecutive and arranged in descending order; b) square of a prime number; c) full cube; e) powers of 2.

N. K. Antonovich
Same numbers when multiplying
Is it possible, when changing two two-digit numbers, to obtain a four-previously known number, all of whose digits are the same?

F. K. Kadirov
Same numbers when adding
Is it possible to pick up such a natural number $A$, and then stop like this?

add numbers in it so that when adding the resulting number with the number $A$ the sum turns out to be the number written in 1985 nines: 99...999?

M. Bayramov, tenth grader from Baku

Arithmetic Rebets

LYUBA
LOVES
WATERMELONS

SPORT
+ PORT
ORT
RRRR

N. K. Antonovich

⟦folio 34⟧

Like the surname Dacosta, and by trying them one after another, perhaps they would find the number that is the key of the cryptograph.

It is not clear why the lack of division of the text into separate words for each judge is an insurmountable obstacle. In fact, it only increases the amount of searching required. Manozl returns fate: “Well, well! If the name of Dacosti is mentioned, then, taking one another each letter of these lines for the first of those seven that make up his name, we will eventually find him.

Here it is - the direct path to solving the problem! The overkill is not that great. The text consists of 252 letters. Therefore, it is necessary to sort through a maximum of 246 options. At one point, having written the words DAKOSTA above the IBNTFE fragment, we would determine the sequence of numbers 5134325. It is natural to assume that the last number 5 is the beginning of the next period:

DACOSTA
... 5 1 3 4 3 2 5 1 3 4 3 2 5 1 3 4 ...
... T G O I BNT F E O I X ...

Instead of the key 432513, we found its cyclic permutation 513432, which in no way interferes with the decryption of the text.

Finally, let's discuss the next question. We have an idea of ​​the contents of the document and therefore were able to guess the words included in it. This word was used for decoding. But what to do when the contents of the document are unknown?

There are several ways. You can, as before, try to debug some words (or part of a word) included in the document. (The texts often contain the words “which”, “then”, “if”, “what”, etc.; the presence of “at”, “pre”, “under”.) Such a search can significantly increase the volume of search, but there are many chances for success. Apparently, a more rational way is to analyze the frequency of use of various letters in the cryptograph. But how can this be?! After all, Jarrix directly says that if the key to the cipher is a number, this path is not applicable: “What follows from this? That the meaning of each letter is determined by a number randomly placed under it, and a letter in cryptographism does not in any way designate the same letter of the text.”

Consider the following encoding device (Fig. 1). For simplicity, let's assume that the encryption key is a three-digit number. On four concentric circles, the smaller of which is motionless, and the rest can rotate relative to their center, we write down the letters of the alphabet. Let the number 259 be chosen as the key. Let's turn the first circle counterclockwise by two letters, the second by five letters, and the third by nine letters (Fig. 2). The coding will be done as follows. The first letter of the text is on a fixed circle and together we do not write down the corresponding letter of the first circle, together with the second letter of the text we write the corresponding letter of the second circle, etc., together 3k+i

⟦folio 35⟧

(i=1, 2, 3; k=0, 1, 2, ...) letters of the text - the corresponding letter of the i-th circle.

From the encoding process itself, it follows that if the difference between the numbers of places on which any letters of the text stand is a multiple of 3, then the same number is used when encoding them. Therefore, Jarricas’s statement that a letter in a cryptograph does not denote the same letter of the text is erroneous.

Now let's move on to decoding. Suppose we know that the key is a three-digit number. It becomes clear that to find the first digit of this number it is necessary to check the analysis of a set consisting of the first, fourth, ..., 3k+1st, ... letters of the text; to determine the second digit - a set consisting of the second, fifth, ..., 3k+2nd, ... letters; to determine the third digit - a set consisting of the third, sixth, ..., 3(k+1)th, ... letters.

The question remains: what to do when it is unknown how many digits the key consists of? There is no way around this without going overboard. First we assume that the key is a two-digit number, then a three-digit number, etc., until the text is decrypted.

Leaving aside intermediate options, let us immediately consider the sequence of decryption of our cryptograph for the case when the key is a six-digit number.

We divide the entire text of the cryptograph into six sets of letters according to the rules described above*), and count how many times the letters of the alphabet are included in each of the sets. The calculation results are shown in Table 1.

Each set contains only 42 letters: this, of course, is not enough to make reliable conclusions about the frequency of use of each of the cryptograph letters. Our task is simplified by the fact that for each set it is enough to debug the number by which the letters of the alphabet are shifted during encoding.

Let's take the four most common letters: A, E, I, O - and count the total number of their occurrences in the original text for various shift values ​​from 0 to 9. The results are shown in Table 2.

| Set no. | Shift value |
| :--- | :--- |
| 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 |
| 1 | 5 | 1 | 1 | 9 | 13 | 1 | 6 | 4 | 7 | 6 |
| 2 | 6 | 2 | 2 | 19 | 3 | 4 | 9 | 5 | 4 | 5 |
| 3 | 8 | 8 | 11 | 3 | 5 | 12 | 11 | 5 | 5 | 5 |
| 4 | 5 | 4 | 6 | 3 | 8 | 15 | 1 | 4 | 6 | 8 |
| 5 | 6 | 17 | 3 | 7 | 6 | 1 | 9 | 7 | 2 | 8 |
| 6 | 9 | 4 | 6 | 12 | 3 | 10 | 7 | 8 | 7 | 4 |

Since we have chosen the most frequently occurring letters, it is natural to assume that the first digit of the key is 4, the second is 3, the fourth is 5, the fifth is 1, the sixth is 3. As for the third digit, it should be chosen from the numbers 2, 5, 6. The final decryption of the cryptograph is now no longer difficult.

To our readers
Subscription to the magazine «Kvant» for 1986 continues. The journal index in the Soyuzechati catalog is 70465. The subscription price for the year is 4 rubles 80 kopecks. Subscriptions are accepted without restrictions by all post offices throughout the year.
