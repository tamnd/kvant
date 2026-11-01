---
id: 1977-8-vilenkin-matematika-i-shifryi-2dda3bf9
issue: kvant_1977_8
year: 1977
number: "8"
title: Mathematics and ciphers
authors:
  - Виленкин Н. Я.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 54
page_last: 57
page_labels: 52-55
tag: OJTN
lang: en
source: kvant_digital
extraction: vision
content_sha256: 4b9cd3a96cffbf66d07f1ea1756ea4dac554440ea9d1f8586809606229e2f829
prompt_sha256: draft-1
translated_from: content/ru/1977/08/articles/13_vilenkin-matematika-i-shifryi-2dda3bf9.md
source_content_sha256: 797807cae9ee5188f80d23f1ea4c3c6f6a078082871080c34fa4f64b55cdebf2
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 52⟧

N. Vilenkin

Matematika
and ciphers

“What is invented by one person can be understood by another,” said Holmes.

Arthur Conan Doyle.
"Dancing People"

Gibberish letter

People have long been looking for ways to protect messages from prying eyes. One ancient king, for example, shaved the head of a messenger, wrote a message on it, and sent the messenger to his ally only when the hair on his head had grown back. The development of chemistry provided a more convenient means: a nicer ink, the writing of which is not visible until the paper is heated or formed with some kind of chemical. In most cases, ciphers are used for secret writing. They are used by diplomats seeking to preserve the secrets of negotiations, military leaders hiding given orders from the enemy, intelligence officers, etc. And in ancient times they were used by pirates, noting the location of treasures, alchemists, merchants, conspirators, and much more.

At first the ciphers were very simple. For example, Russian diplomats of the 15th-16th centuries used the so-called “gibberish letter”, in which all vowels remained unchanged, and consonants were replaced with each other according to the following scheme:

b c d j h h k l mn
↑ ↑ ↑ ↑ ↑ ↑ ↑ ↑
shchts x ft srp

(in the first line the consonants are in the common order, and in the second line they are in the reverse order). For example, together “Great Sovereign” turned out to be “She-

⟦folio 53⟧

sitiy cholucham.” This code is very simple (you can even learn to speak “gibberish”).

Gradually, secret writing became possible, but even the code that Princess Sophia used at the end of the 17th century in her correspondence with Vasily Golitsky was very simple - one of her letters was published several years ago in the journal Science and Life, and many readers deciphered it. The traitor Mazen also used codes. As A. S. Pushkin writes in the pose “Poltava”:

“In the darkness of the night they are like thieves,
Conducting their negotiations
Treason is valued among themselves,
They make digital universal..."

What should the shfr be?

When engraving, certain conditions must be met. First, different letters must be represented by different signs - otherwise the recipient will have to guess which of several letters represents which sign. Further, the code must be difficult to solve - light codes can be used only on the condition that the enemy does not have time to solve it. Finally, the secrecy of the code must be combined with the comparative simplicity of the encoding and decoding operations - otherwise they will take so much time that the transmitted information gets tired *). And if decoding requires too much effort, then you can find yourself in the position of the legendary scribe who wrote letters for a fee in an oriental bazaar, but also charged a fee as a messenger, claiming that no one but himself could understand what he wrote.

Gibberish writing refers to scripts in which each letter is replaced by a specific sign - another letter, number or image. In the same way, the last Chicago bandits defrauded themselves in Conan Doyle’s story “Dancing”

*) However, now these operations can be entrusted to a computer.

people" and rights in Edgar Poe's story "The Gold Bug" (only the rights were also used sympathetically ink). Sometimes, in order to make it difficult to read the code, redundant codes are used - the same letter is denoted by different signs. Then, even if the enemy guesses the meaning of a sign, he will not be able to use this when deciphering another part of the text, since there the same letter will be designated inchete.

However, sometimes redundancy will arise naturally. When specialists in ancient languages ​​began to decipher the inscriptions made many thousands of years ago by the Carians (a people who lived in Asia Minor), they discovered that the number of characters was too large for the alphabet. Therefore, they decided that neokot signs mean individual letters, and neokot symbols mean syllables. However, insurmountable difficulties arose along this path. And only when the Soviet scientist V.V. Shevoroshkin began to see in which areas no more than three dozen different signs were found, that is, the writing was still alphabetic. Only in different places the neokot letters were depicted differently, which made it difficult to decipher the Carian inscriptions.

Ciphers and combinatorics

Since the set of signs used in a given code is finite, its elements can be re-ordered and their numbers can be used with them. For simplicity, we will consider spools in which there is no redundancy. Then the number of characters is equal to the number of letters in the alphabet, as well as such characters as a space between words, a period, a comma. For the Russian language, you can get by with 35 characters: 31 letters (e, é, and b, ѫ are not different), space, period, comma, type. If the number of characters used in shfro-

⟦folio 54⟧

vani is also equal to 35, then each such shfr is defined by a one-to-one mapping of one set of 35 elements to another such set. In combinatorics it is proven that the number of such mappings is 35!, that is, the product of natural numbers from 1 to 35. This is such a huge number that it is difficult to imagine - it is approximately equal to $10^{40}$.

Dealing with arbitrary mappings $f$ of a set of letters of the alphabet and punctuation marks $A = \{a_1, a_2, \ldots, a_{35}\}$ onto a set of shfra signs $B = \{b_1, b_2, \ldots, b_{35}\}$ is not very convenient: it is difficult to remember such a mapping, and keeping a mapping table with you - the “key” of the shfra – is undesirable. It’s better to have some simple rule that allows you to find $f(k)$ using $k$. And also the rules are given by the methods of mathematics - after all, there is nothing better for unraveling all sorts of complexities than the use of mathematical methods.

Ciphers and comparisons

Mathematics has long been used in the theory of shfrov. Back at the end of the 16th century, one of the creators of modern algebra, France Viète, was deciphering correspondence between opponents of the French king Henry III. And the English monarchist conspirators in the 17th century were amazed at the speed with which Cromwell penetrated their plans. They thought that the secrets they used were impossible to unravel, and believed that the keys to them had been given out by someone studying the conspiracy. Only after the fall of the Resurblika and the accession of Charles II did he learn that all these secrets were being solved by one of the best mathematicians of that time, Oxford University professor Wallis, who considered himself the founder of a new science - critical morphology.

One coding method is as follows. Let's divide the ring into 35 congruent parts, number them and mark each with a letter or punctuation mark (see figure). Now let’s choose some number $a$ (“key number” of the shfra) and rotate the ring around the center clockwise so that each part moves $a$ steps. This defines the shfr—the mapping of the set $A = \{a_1, a_2, \ldots, a_{35}\}$ onto the set of shfra signs $B = \{01, 02, \ldots, 35\}$ (you must write 0 before single-digit numbers, otherwise it is unclear what 15 is—“fifteen” or “one,” “five”).

For example, if $a = 11$, then the part marked with the number 01 will go into the part marked with the number 12, which means that the letter “A”, when encoded, corresponds to the number 12. In the same way, the letter “B” corresponds to the number 14, and so on.

The result is the latter, in which each letter or sign is written as two numbers. To decipher the address, you need to break the resulting sequence of numbers into two-part numbers, subtract the key number from each and replace the resulting number $k$ - the character number $a_k$ - with a letter of the alphabet or a punctuation mark.

However, in fact, the rules of encoding and decoding are not so simple - if $k$ is greater than 24, then the sum $k + 11$ is greater than 35, and in the set $B$ the largest number is 35. But here we must remember that we wrote numbers not on a straight line, but on a ring, and, as you know, a ring has no beginning and no end - after the number 35 comes 1. In other words, after the number 35 everything repeats again. This means that, having received a sum exceeding 35, you need to subtract 35 from it.

⟦folio 55⟧

ity and will show what number $a_k$ goes to. For example, $a_{27}$ (the letter “ы”) goes not to the number 38, but to 03, $a_{32}$ (“space”) - to 08, and so on. Thus,

$$f(a_k) = \begin{cases} k + 11, & \text{ если } k \leq 24, \\ k - 24, & \text{ если } 25 \leq k \leq 35. \end{cases}$$

And decoding is done according to the following formulas:

$$g(n) = \begin{cases} a_{n-11}, & \text{ если } 12 \leq n \leq 35, \\ a_{n+24}, & \text{ если } 1 \leq n \leq 11. \end{cases}$$

The coding rule can be written more compactly if addition is understood in a special sense.

Let us divide all the integer numbers into classes, assigning to one class the numbers that give the same remainder when divided by 35. For example, the numbers 32,3,38,73 will fall into the same class, since all of them when divided by 35 give a remainder of 3. The general form of numbers in this class is $3+35k$, where $k$ is an integer. Let us denote by $Z_{35}$ the set of such classes. The number of different classes is 35 (when divided by 35, the remainders are 0, 1, 2, ..., 34), and they can be denoted by the same numbers as the corresponding remainders, only with a dash on top. For example, 5 does not mean the number 5, but the class containing this number, that is, the set of numbers {..., - 30, 5, 40, 75, ...}. Specifically, 0 means the class containing the number 35.

Now we can write that $27 + 11 = 3$, that is, by adding 11 to the numbers of the class $27$, we get numbers from class 3. This means that if the classes from $Z_{35}$ are considered to be the numbers of encoded letters and the symbols of the code, then the encoding and decoding formulas can be written as follows:

$$f(a_k) = \bar{k} + 11,$$
$$g(n) = a_{n-11}.$$

This kind of “arithmetic” of remainders is useful in many other matters. For example, let the minute hand now show 25 minutes. What will its position be after 176 minutes? To answer this question, it is enough to note that every 60 minutes the arrow returns to its original position. Therefore, we need to find the remainder of dividing the sum 25 + 176 = 201 by 60. We find that this remainder is equal to 21. This means that the hand will show 21 minutes.

To facilitate the addition and subtraction of remainders when dividing by $m$ in arithmetic, you need to create an addition table. To do this, take a general addition table and replace each number with its remainder when divided by $m$.

Such an arithmetic is conventionally called arithmetic modulo $m$, and numbers that have identical remainders when divided by $m$ are called comparable modulo $m$. If $a$ and $b$ are comparable modulo $m$, then write

$$a \equiv b \pmod{m}.$$

For example,

$$215 \equiv 40 \pmod{7},$$

since $k$ and 215 and 40 when divided by 7 leave a remainder of 5.

If it is already known that the code is obtained by adding the same number to the letter numbers, then it can be solved by guessing the meaning of at least one letter, or even better, several letters. For example, if it is known that the letter is about Moscow and the combination “UHSHSYZ” is often found in it, then it is easy to guess that when engraving the number of each letter increases by 7.

A more complex code is obtained if you replace addition with multiplication. For example, we will multiply the numbers of all letters by 2. Of course, if the product turns out to be greater than 35, we must replace it with the remainder of division by 35. For example, the letter “CH” will receive the number 13 when engraving, since the number of the letter “CH” is 24, and when dividing 24 2 = 48 by 35, the remainder is 13. This transformation is more confusing than addition, and one can be afraid that different letters will be encoded will go to the same letter. But, fortunately, this will not happen in this case - the code is non-expressive. The proof of this statement is based on the fact that the product of two numbers is divisible by 2 only if one of the factors is even. And if we tried to multiply the letter numbers not by 2, but by 5 (the divisor of the number is 35), we would get a degenerate code (check it yourself!). Interesting codes are obtained by replacing multiplication with multiplication in st.
