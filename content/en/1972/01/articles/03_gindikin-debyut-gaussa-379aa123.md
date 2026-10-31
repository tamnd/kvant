---
id: 1972-1-gindikin-debyut-gaussa-379aa123
issue: kvant_1972_1
year: 1972
number: "1"
title: Gaussian debut
authors:
  - Гиндикин С. Г.
rubric: osnovnye-stati
page_first: 6
page_last: 11
page_labels: 4, 6, 9
tag: 1VLR
lang: en
source: kvant_digital
extraction: vision
content_sha256: bd37eb9c1fe0335a5ab8c868fbdc578b8f39d898b666a1fbf4dd455e1715abcd
prompt_sha256: draft-1
translated_from: content/ru/1972/01/articles/03_gindikin-debyut-gaussa-379aa123.md
source_content_sha256: 1dcf6e90ce4945056dc91c260fee6b2c06366e59678661d3666affe57fbcfc76
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 4⟧

Equivalent to the problem of dividing a circle of radius 1 into $n$ equal parts. The chords of the arcs into which the circle is divided are the sides of a regular $n$-gon and the length of each of them is $2\sin \frac{\pi}{n}$ (Fig. 2).

Consequently, for those $n$ for which $\sin \frac{\pi}{n}$ is a square irrationality, one can construct regular $n$-gons with a circlel and a ruler. This condition is satisfied, for example, by the values ​​$n=3, 4, 5, 6, 10$. For $n=3, 4, 6$ this is well known.

Let us show that $\sin \frac{\pi}{10}$ is a square irrationality. Consider an equilateral triangle $ABC$ (Fig. 3), the vertex angle of which is $\frac{\pi}{5}=36^\circ$, length $AB$ is 1; let $AD$ be the bisector of angle $A$. Then $x=AC=AD=BD=2\sin \frac{\pi}{10}$.

We have:

$$\frac{BD}{DC}=\frac{AB}{AC}; \frac{x}{1-x}=\frac{1}{x}, x=\frac{\sqrt{5}-1}{2}.$$

This number is a square irrationality; thus we can construct the side of a regular decagon.

Further, from the possibility of dividing a circle into $p_1 p_2$ equal parts

It follows, of course, that it can be divided into $p_1$ equal parts (in part, it is possible to construct a regular pentagon). The converse statement is, generally speaking, false. Let us indicate two special cases when it is still true.

1) From the possibility of dividing a circle into $p$ equal parts it follows the possibility of dividing it into $2^k p$ equal parts for any $k$.

2) If we reduce a circle into $p_1$ equal parts and $p_2$ equal parts, where $p_1$ and $p_2$ are mutually prime (for example, $p_1, p_2$ are distinct primes), then the circle can be divided into $p_1 p_2$ equal parts.

A few words about complex numbers

We need to know very little about complex numbers: operations on them and geometric interpretation; All this is contained, for example, in the Kochetkovs’ school textbook. Let us say that the complex number $z=a+ib$ is associated with a point with coordinates $(a, b)$ (Fig. 4) and a vector with an end at this point and a beginning at $(0, 0)$. The length of the vector $r=\sqrt{a^2+b^2}$ is called the modulus of the given number. The complex number $z$ can be written in trigonometric form: $z=a+bi=r(\cos \varphi+i\sin \varphi)$; the angle $\varphi$ is called the argument of the number $z$.

⟦folio 6⟧

equations: first, equation (4) is solved, the roots of which are the sums $\varepsilon_1 + \varepsilon_4$ and $\varepsilon_2 + \varepsilon_3$ of the symmetric (see Fig. 6!) roots of equation (3), and then the roots of equation (3) themselves are found from equation (5).

It was in this way that Gauss managed to construct a regular 17-gon: here, too, groups of roots are distinguished, the sum of which is found sequentially from quadratic equations. But how do you find these “good” bands? Gauss has an amazing way to answer this question...

Construction of a regular 17-gon

March 30, 1796 was the day of creative baptism for him (Gauss)... Gauss had already been engaged for some time in grouping roots from units on the basis of his theory of “primitive” roots. And then one morning, when we woke up, he clearly and distinctly realized that the construction of a 17-agon follows from his theory... This event was a turning point in Gauss’s life. He decides to devote himself not to philology, but exclusively to mathematics.

F. Klein

In order to reveal the hidden “symmetries” found by Gauss in the set of roots of the 17th power of units and, using immy, to divide the roots into the necessary groups, we introduce a new numbering of the roots. We will raise 3 to successive powers 0, 1, 2, ... and each time take the remainder of dividing the resulting number by 17. We will spare the reader from carrying out these calculations and present the final results in the table. The first line contains the exponents $k$, and below it the remainders from dividing $3^k$ by 17.

Notice that the bottom line contains all the numbers from 1 to 16; then $3^{16}$ gives remainder 1 and then periodic remainders are repeated (prove it!)

The pattern noticed by Gauss is a special case of the following theorem: for every prime $p$ there is a number $l$, called a primitive root, such that among the remainders of the division of $l^k$ by $p$ all the numbers 1, 2, ..., $p-1$ are found. This fact was first noted by Euler (1707-1783), but only Legendre (1752-1833) was able to prove it; Other proofs were obtained by Gauss, but, most likely, in 1796 he did not yet have a general theorem, but discovered the given empirical fact by carrying out calculations for specific numbers. This is a very important circumstance, without taking into account the fundamental one, it is difficult to correctly understand the nature of Gauss's early works.

Let us assign the root $\varepsilon_h$, $k=3^l$, a new number, namely $l$, which we

Table

| 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 | 16 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 1 | 3 | 9 | 10 | 13 | 5 | 15 | 11 | 16 | 14 | 8 | 7 | 4 | 12 | 2 | 6 | 1 |

⟦folio 9⟧

Appendix 1.

Now we will prove the square irrationality of the 17th roots of ones. Note that $\varepsilon_k \varepsilon_l = \varepsilon_k + l$ (if $k + l \geq 17$, then $k + l$ is replaced by the remainder of its division by 17), $\varepsilon_k = (\varepsilon_1)^k$. Let's renumber the roots of units using our table, namely, we will write $\varepsilon_{[l]}$ together with $\varepsilon_k$ (see formula (1)), where $l$ is the number above $k$ in the table. Let's divide the roots into groups, as shown in figure 8. We will find the sums of roots whose numbers appear in one rectangle (Fig. 8), moving from a large rectangle to a smaller one. First of all, we note that

$$\varepsilon_1 + \varepsilon_2 + \ldots + \varepsilon_{16} = \varepsilon_0 + \varepsilon_1 + \ldots + \varepsilon_{15} = -1.$$

(You can verify this, for example, by considering this expression as the sum of a geometric progression.) So, we have found the sum of the roots in the largest rectangle (No. 0).

Let us denote by $\sigma_m, r$ the sum of $\varepsilon_k$ with those $k$ that give remainder $r$ when divided by $m$. Let us consider the sums of the roots corresponding to the next rectangle (No. 1).

We get

$$\sigma_{2,0} = \varepsilon_0 + \varepsilon_2 + \varepsilon_4 + \ldots + \varepsilon_{14},$$

$$\sigma_{2,1} = \varepsilon_1 + \varepsilon_3 + \varepsilon_5 + \ldots + \varepsilon_{15}.$$

It's clear that

$$\sigma_{2,0} + \sigma_{2,1} = \varepsilon_0 + \varepsilon_1 + \ldots + \varepsilon_{15} = -1.$$

It can be shown that

$$\sigma_{2,0} \cdot \sigma_{2,1} = 4 (\varepsilon_0 + \varepsilon_1 + \ldots + \varepsilon_{15}) = -4^*.$$

Now, using Vieta’s theorem, we can create a quadratic equation whose roots are $\sigma_{2,0}, \sigma_{2,1}$:

$$x^2 + x - 4 = 0; \quad x_{1,2} = \frac{-1 \pm \sqrt{17}}{2}.$$

To distinguish the roots, use Figure 7. In each of the sums, the roots are included along with their conjugates. It is clear that $\sigma_{2,0} > \sigma_{2,1}$ (in the first case, you need to add and double the real parts of the roots $\varepsilon_1, \varepsilon_2, \varepsilon_4, \varepsilon_8$, in the second - $\varepsilon_3, \varepsilon_5, \varepsilon_6, \varepsilon_7$). So,

$$\sigma_{2,0} = \frac{\sqrt{17} - 1}{2}, \quad \sigma_{2,1} = \frac{-\sqrt{17} - 1}{2}.$$

Let us consider the sums of roots corresponding to the following rectangle (No. 2) on figure 8:

$$\sigma_{4,0} = \varepsilon_0 + \varepsilon_4 + \varepsilon_8 + \varepsilon_{12},$$

$$\sigma_{4,1} = \varepsilon_1 + \varepsilon_5 + \varepsilon_9 + \varepsilon_{13},$$

$$\sigma_{4,2} = \varepsilon_2 + \varepsilon_6 + \varepsilon_{10} + \varepsilon_{14},$$

$$\sigma_{4,3} = \varepsilon_3 + \varepsilon_7 + \varepsilon_{11} + \varepsilon_{15}.$$

*) You can verify this, the wires are direct changes, taking into account that $\varepsilon_k \cdot \varepsilon_l = \varepsilon_k + l$, and it is convenient to use Figure 7. However, Appendix 2 will indicate a way to avoid these tedious calculations.
