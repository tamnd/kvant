---
id: 1979-12-ore-prostyie-chisla-ferma-8e89f4b6
issue: kvant_1979_12
year: 1979
number: "12"
title: Fermat primes
authors:
  - Оре О.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 33
page_last: 35
page_labels: 31-33
tag: ALWO
lang: en
source: kvant_digital
extraction: vision
content_sha256: 350227d1720b9b19d11a7aa390c61c0f458a228a3ffc66e1c95afd6ca1faa0ae
prompt_sha256: draft-1
translated_from: content/ru/1979/12/articles/11_ore-prostyie-chisla-ferma-8e89f4b6.md
source_content_sha256: d9f35b2c99d163f00fd9f6c0422f36cc4f7b5eba535de29f82d16b094c823d87
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 31⟧

O. Ore

Fermat primes

Probably one of the first properties of numbers discovered by people was the fact that some numbers can be decomposed into two smaller factors, for example
$$6=2\cdot 3, 9=3\cdot 3, 30=2\cdot 15=3\cdot 10,$$
while others, e.g.
$$3, 7, 13, 37,$$
are not factorized in this way.

If the number $c$ is the product of two numbers $a$ and $b$ ($c=a\cdot b$), we call the numbers $a$ and $b$ the multigels or divisors of the number $c$. Each number has a primal (simplest) factorization:
$$c=1\cdot c=c\cdot 1.$$
Accordingly, we call the numbers 1 and $c$ multigels and divisors of the number $c$.

This article is an open source from O. Ore’s book “Invitation to Number Theory,” published in 1980 in Biblotechek «Kvant» (translation by L. Savina, edited by A. Savin).

Any number $c>1$ that has a non-trivial factorization is called composite. If a number greater than one has only a trivial factorization, then it is called prime. Among the first hundred numbers, the following 25 numbers are prime:
2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47, 53, 59, 61, 67, 71, 73, 79, 83, 89, 97, and all other numbers except 1 are composite.

Many prime number tables have been published over the past 200 years. The most extensive of them is the table of D. N. Lechmer, containing all prime numbers up to 10,000,000.

Some enthusiasts have compiled tables of prime numbers greater than 10,000,000, but there seems to be little point in publishing these tables. Only in very rare cases does a mathematician, even a special one in number theory, come to solve the question of whether some larger number is prime. Moreover, the larger number that a mathematician wants to know whether it is prime or composite does not arise arbitrarily. They usually appear in special mathematical problems and therefore have a very specific form.

⟦folio 32⟧

Let's talk about one of the types of prime numbers that has a long and interesting history. These numbers were first introduced by Pierre Fermat (1601-1665), a French lawyer who was also an outstanding mathematician *). The first five Fermat primes are

$$F_0 = 2^{20} + 1 = 3, \quad F_1 = 2^{21} + 1 = 5, \quad F_2 = 2^{22} + 1 = 17, \quad F_3 = 2^{23} + 1 = 257, \quad F_4 = 2^{24} + 1 = 65537.$$

According to this sequence, Fermat's general formula for prime numbers should be of the form

$$F_n = 2^{2n} + 1.$$

Fermat was absolutely sure that all numbers of this type are prime, although he did not calculate other numbers except the indicated heels. But after Leonhard Euler went one step further by showing that the following Fermat number is:

$$F_5 = 4294967297 = 641 \cdot 6700417$$

is not simple, this assumption was made in the archive of unjustified mathematical hypotheses. Perhaps this would have been the end of the history of Fermat numbers if Fermat numbers had not appeared in a modern problem - the problem of constructing regular polygons using a compass and ruler.

A regular polygon is a polygon whose vertices lie on a certain circle at equal distances from each other (see figure). If a regular polygon has $n$ vertices, then we call it a regular $n$-gon. If we draw $n$ radii connecting the center of the circle to the vertices, we get $n$ central angles of size $\frac{1}{n} \cdot 360^\circ$ each. If you can construct an angle having this value, then you can construct the polygon itself.

The ancient Greeks were very familiar with the methods of constructing regular polygons using compasses

*) See «Kvant», 1976, No. 8 (editor's note).

Leonhard Euler (1707-1783).

A and rulers. Of course, they were able to construct simple ones - an equilateral triangle and a square. By repeated bisection of the central angle, they could also construct regular polygons with

8, 16, 32, ...
6, 12, 24, ...
peaks. In addition, they were able to construct a regular pentagon and, therefore, also regular polygons with

10, 20, 40, ...
peaks. Another type of regular polygon was also obtained. The central angle in a regular 15-gon is equal to

$$\frac{1}{15} \cdot 360^\circ = 24^\circ,$$

⟦folio 33⟧

Karl-Friedrich Gauss (1777-1855).

and it can be obtained by using the angle of 72° corresponding to a regular pentagon, and the angle of 120° corresponding to a regular triangle, if the satisfying angle is subtracted from it by the second. Therefore, we can construct regular polygons with 15, 30, 60, 120, ... sides.

The problem remained in this state until 1801. That year, the young German mathematician Carl-Friedrich Gauss (1777–1855) published a work on number theory, Arithmetic Studies. This work opened a new era in mathematics. In it, Gauss surpassed the Greek geometers not only in that he indicated a method for constructing a circumference and a linear regular 17-gon - he went much further. For all numbers $n$ he determined which $n$-gons could be constructed in this way and which could not. We will now describe the results obtained by Gauss.

We have already said that, for every central angle bisected, from a regular $n$-gon one can obtain a regular $2n$-gon. On the other hand, from a $2n$-gon you can get a $n$-gon using only every second vertex. This shows that it is sufficient to carry out a search of polygons that can be constructed using a compass and straightedge only among polygons with an odd number of vertices. Gauss showed that a regular polygon with an odd number of vertices can be constructed using a compass and ruler, only among polygons with an odd number of vertices. For $n=11$ and $n=13$ the corresponding $n$-gon cannot be constructed, but it can be constructed for $n=15=3.5$ and $n=17$.

Gauss's discovery naturally sparked interest in Fermat's numbers. Over the last century, ponks have been proposed “by hand”, without the help of machines, new Fermat primes. Currently, these calculations are carried out with all possible speed using a computer, but so far the results have been negative. No new Fermat primes have yet been found. And now many mathematicians are inclined to believe that they no longer exist.

Exercise

1. Find all odd numbers $n<100$ for which a regular $n$-gon can be constructed.
2. How to construct a regular 51-gon given a regular 17-gon?
3. If there are no Fermat primes other than the above fives, then how many regular $n$-gons ($n$ odd) are there that can be constructed with a compass and straightedge? What is the most odd $n$ for which a regular $n$-gon can be constructed?
