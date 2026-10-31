---
id: 1972-9-kudrevatov-sravneniya-32a72226
issue: kvant_1972_9
year: 1972
number: "9"
title: Comparisons
authors:
  - Кудреватов Г. А.
rubric: osnovnye-stati
page_first: 18
page_last: 20
page_labels: 16, 18
tag: 9DNE
lang: en
source: kvant_digital
extraction: vision
content_sha256: a903c38b24064acd451df204b333e77b444f9fba9a09605a32ed1e6d4d4991d2
prompt_sha256: draft-1
translated_from: content/ru/1972/09/articles/02_kudrevatov-sravneniya-32a72226.md
source_content_sha256: c20f55aa0b6ab1fb0562c022c7223e13013c786b74d2caaa4f80b294f2ee54c8
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 16⟧

Will it split or not? This question often arises in integer arithmetic. And this is no coincidence - after all, division is the most complex of arithmetic operations.

Let us denote the dividend and divisor by the letters $a$ and $m$ (we will restrict ourselves to the case of $m > 0$), and the quotient and remainder by the letters $q$ and $r$, respectively. Then (see figure) $a = mq + r$, $0 \leq r < m$ (definition of division with remainder).

If $r = 0$, then $a = mq$, and we say that “a is divisible by $m$” or “a is a multiple of $m$”. This is indicated by three eyes: $a : m$; symbol : means “divided by...”

In some cases, signs of divisibility help to answer the question of whether it is divisible or not. But in the school course, only the simplest of them are considered: by 2, 3, 5 and 9. Signs of divisibility, for example, by 7, 11, lie outside the scope of the school course. The knowledge gained in arithmetic lessons is not enough to find the remainder of dividing $2^{25} + 1$ by 641, 1971$^{1972}$ by 7, $22^{11} + 11^{22}$ by 3. These and many other questions are answered by the theory of comparison, the elements of which are discussed in this article.

1. Remainder of division

Often the remainder $r$ is of more interest than the quotient $q$. For example, to determine GCD

$$mq \cdot a \cdot m(q+1)$$

Fig. 1.

(*) This is described in detail in the article by V. N. Vaguten “Euclidean Algorithm and the Fundamental Theorem of Arithmetic”, «Kvant» No. 6, 1972.

⟦folio 18⟧

possible, multiple modulo. In this case, it is worth noting that comparisons not only have an external resemblance to general equalities, but also possess almost all of their basic properties.
Thus, comparisons over the same modulo can be obtained by adding, subtracting and multiplying:

$$a \equiv b, c \equiv d \pmod{m} \Rightarrow a \pm c \equiv b \pm d, ac \equiv bd \pmod{m}.$$ (C)

This also leads to the following corollary:
the same number can be added to the part of the given comparison, they can be multiplied by the same number, and also raised to the same natural power, that is

$$a \equiv b \pmod{m} \Rightarrow a + c \equiv b + c, ac \equiv bc, a^k \equiv b^k \pmod{m}.$$

Exercises

1. Prove criterion (K) and comparison properties (C).
2. Prove that the parts of the comparison can be reduced by a number coprime to the model (if, of course, both parts of the comparison are divisible by this number).
3. Show that the comparison 3x ≡ 4(mod5) is true for any x comparable to 3 in a given modulo.
4. Check that there are no integers x satisfying 3x ≡ 2(mod 6).

3. Modulo comparisons and class partitions

The properties of comparison given in paragraph 2 make it possible to relatively simply solve many problems in the theory of divisibility, which were often encountered among olympiads, competitions, etc. Let's consider some of them, but first note that when solving these problems, you can solve them by dividing them into classes of numbers comparable in a given modulo (in this case, the model is selected depending on the circumstances or is determined by the condition of the problem itself).

For each a comparison, x ≡ a(mod m) satisfies classes of numbers x that, when divided by m, give remainder r(a, m). For each x one of the comparisons is performed

$$x \equiv 0, x \equiv 1, x \equiv 2, \dots, x \equiv m - 2, x \equiv m - 1 \pmod{m}$$

or, what is the same, one of the equalities

$$x = mt, x = 1 + mt, x = 2 + mt, \dots, x = m - 2 + mt, x = m - 1 + mt,$$

where t is the corresponding integer. So, each integer belongs to one of m classes; numbers that are not comparable in a given modulo belong to different classes.

Exercise

5. Check that the comparability relation is an equivalence relation and partitions all numbers into classes of comparables, namely, prove that

a) x ≡ x(mod m);
b) x ≡ y(mod m) ⇒ y ≡ x(mod m);
b) x ≡ y, y ≡ z(mod m) ⇒ x ≡ z(mod m).

Partitioning into classes is discussed in detail in the article by M. M. Glukhov “The relation of equivalence and partitioning of a set”, “Quant” No. 2, 1972.

4. Some tasks

To more freely use the “language of comparison” when solving problems, consider the following questions: which classes, for example, in modulo 6, contain prime numbers? Which of these classes does the prime number 37 belong to? Which modulo 6 classes contain target powers of numbers?

It is easy to see that the class x ≡ 0(mod 6) does not contain prime numbers: it consists of numbers that are multiples of 6. The class x ≡ 4(mod 6) does not contain prime numbers, since it consists of four numbers 4+6t = 2(2+3t) (and does not contain the number 2). the classes x ≡ 2 and x ≡ 3(mod 6) each contain one prime number: 2 and 3, respectively. the classes x ≡ 1, x ≡ 5(mod 6) contain all other prime numbers; for example, the first of them includes 7 and 13, and the second includes 11 and 17.
