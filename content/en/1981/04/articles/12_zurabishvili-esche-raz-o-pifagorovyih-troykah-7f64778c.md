---
id: 1981-4-zurabishvili-esche-raz-o-pifagorovyih-troykah-7f64778c
issue: kvant_1981_4
year: 1981
number: "4"
title: Once again about Pythagorean triplets
authors:
  - Зурабишвили З.
rubric: smes
page_first: 41
page_last: 41
page_labels: "39"
tag: A164
lang: en
source: kvant_digital
extraction: vision
content_sha256: 12b395858a6f07c0589ee05ce335dd080685b501bb1761b30ae2a4b974df6e30
prompt_sha256: draft-1
translated_from: content/ru/1981/04/articles/12_zurabishvili-esche-raz-o-pifagorovyih-troykah-7f64778c.md
source_content_sha256: b997b152d0e046a140475f53096e8f54ca0ae2d075b5b8c14a3cf0df90f06277
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 39⟧

Once again about Pythagorean triplets

The triple of natural numbers (3, 4, 5) is Pyfadorian: $3^2 + 4^2 = 5^2$. How to find all Pythagorean triples? This was already written about in «Kvant» (1979, No. 4, p. 40). Here is another way to solve this problem.

Obviously, if $(a, b, c)$ is a Pythagoian triple, then any triple $(ak, bk, ck)$, where $k$ N, is Pythagogian. If any two of the numbers $a, b, c$ have a common prime divisor $p$, then the third number is also divisible by $p$. Therefore, it suffices to list Pythagogian triples with pairwise simultaneous primes $a, b, c$.

So, let $(a, b, c)$ be a Pythagoian triple and let the numbers $a, b, c$ be pairwise simplistic.

The numbers $a$ and $b$ cannot be even at the same time. They cannot be odd at the same time, since otherwise the sum of their squares is divisible by 2, but not divisible by even, and, therefore, cannot be the square of a natural number. So, one of the numbers $a$ and $b$ must be even, the second odd; Moreover, the number $c$ is odd. We will assume that $a$ is odd and $b$ is even.

Let's draw a square from the side of length $c$. In its upper left corner we put a square from the side of length $a$, and in the lower right corner - a square from the side of length $b$ (see figure). This square is intersected by the red square, and in the large square two synchronized rectangles will remain uncovered. From condition $a^2 + b^2 = c^2$ it follows that the area of ​​the square is equal to the sum of the areas of the synchronous rectangles.

The side lengths of the synch rectangles are $c - a$ and $c - b$, and the side length of the red square is $a + b - c$. Since the numbers $c - a$ and $a + b - c$ are even, each of the synch rectangles can be divided into two identical rectangles, and the red square can be divided into four identical squares with integral side lengths. Let us denote the lengths of the sides of the protected rectangle by $k$ and $l$ ($k = c - b, 2l = c - a$), and the length of the side of the protected square by $s$ ($2s = a + b - c$). From the equality of their areas it follows $kl = s^2$.

From the pairwise mutual primeness of the numbers $a, b$ and $c$ it follows that the numbers $k$ and $l$ are mutually prime. It is true that the numbers $k$ and $l$ have a common prime factor $p$. Because $b^2 = c^2 - a^2 = (c - a)(c + a) = 2l(c + a)$ is magnified by $p$. But $c = b + k$. This means that $c$ is also divisible by $p$, which contradicts the mutual primeness of $b$ and $c$.

Let's return to the equality $kl = s^2$. Since $k$ and $l$ are coprime, and their product is a perfect square, each of these numbers must itself be a square. Let $k = m^2, l = n^2$. Then $s = m \cdot n$.

Let us now express $a, b$ and $c$ in terms of $m$ and $n$:

$$a = k + 2s = m^2 + 2mn = (m + n)^2 - n^2,$$
$$b = 2l + 2s = 2n^2 + 2mn = 2n(m + n),$$
$$c = k + 2l + 2s = m^2 + 2n^2 + 2mn = (m + n)^2 + n^2.$$

Putting $m + n = t$, we get $a = t^2 - n^2, b = 2nt, c = t^2 + n^2$.

It is easy to check that for any $t$ and $n$ these formulas give, if $t > n$, a Pythagogian triple. If $t$ and $n$ are coprime numbers of different parities, then the numbers $a, b, c$ will be pairwise coprime.

3. Zurabivili
