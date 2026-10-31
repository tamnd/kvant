---
id: 1971-10-shirshov-ob-odnom-svoystve-binomialnyih-koeffitsientov-de120e7b
issue: kvant_1971_10
year: 1971
number: "10"
title: On one property of binomial coefficients
authors:
  - Ширшов А. И.
rubric: osnovnye-stati
page_first: 18
page_last: 22
page_labels: 16, 20
tag: 0H1J
lang: en
source: kvant_digital
extraction: vision
content_sha256: 2f983630c18d52e47bae3c5ca7b9d4d59a5faa6b8c05cf0ca04e5ebf6b20ee6e
prompt_sha256: draft-1
translated_from: content/ru/1971/10/articles/06_shirshov-ob-odnom-svoystve-binomialnyih-koeffitsientov-de120e7b.md
source_content_sha256: b30baeeb85f07444e3de8a0555091d2115bfc2d487f20eab9371136a9ba1b59f
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 16⟧

A. I. Shirshov

In «Kvant» No. 6 for 1970, an article by D. B. Fuks and M. B. Fuks “Arithmetic of biomial coefficients” was published. In this paper, the authors proposed the following problem: let $p$ be a prime number; find out by what power $p$ the number $C_{p^{n+1}}^{p^n} - C_{p^n}^{p^{n-1}}$ is divisible

This problem has attracted the attention of many of our readers. The editors have received letters from V. G. Gaidalovich (Tashkent), S. P. Krutik (stanitsa Staro-Sherbinskaya, Krasnodar Territory), 9th grade student A. Merkuverev (Leningrad), V. V. Prlensky (Moscow) and other goods who will offer varying degrees of solution to this problem.

We asked the prominent Soviet algebraist, corresponding member of the USSR Academy of Sciences A. I. Shirshov to highlight in detail the solution to the problem.

Schoolchildren are familiar with many popular science books and articles on mathematics. They are written as simply as possible, detailed and accessible, in bright and lively language, with engaging examples and colorful pictures - so as to interest the reader and give him the opportunity to easily understand the material.

How are server-side mathematical articles written in reputable scientific journals? The article by A. I. Shirshov, offered to the attention of readers, gives an idea of ​​the scientific mathematical style of presentation. In terms of its content, it is accessible to high school students, but it is written specifically in the same way as notes are written, say, in the journal “Reports of the USSR Academy of Sciences.”

The scientific and mathematical style is characterized by slope and brevity. As a rule, the presentation is divided into separate steps - lemmas, rising along which we arrive at the final result - the theorem. The initial article always contains a statement of the problem, an explanation of the concepts introduced and notations used, and references to the literature. The proofs are not reproduced in detail - only their idea and the general course of reasoning are outlined. Therefore, you can read such an article only with a pencil and paper in your hands, restoring intermediate calculations; understanding its content requires a certain amount of effort and independent reflection.

A math lover will undoubtedly be interested in learning about the scientific mathematical style of presentation.

In article [1], it was proposed that numbers of the form $C_{p^{k+1}}^{p^k} - C_{p^{k-1}}^{p^{k-2}}$, where $p$ is prime, are divisible by a sufficiently high number $p$. However, this statement has been proven only in the case $p=2$ (Theorem 5 from [1]).

This note is devoted to the proof of a more general theorem.

All numbers $m, k, t, s$, etc., considered below are natural, and $p$ is a prime number. The symbol $(m, n)$, as usual, means the most common divisor of the numbers $m$ and $n$. We will use the symbol $[k, s]_n$ to denote the product of all natural numbers $t$ such that $k \leq t \leq s$ and $(t, n)=1$; on-

⟦folio 20⟧

Noticing that
$$1(p^{k-1}-1) \cdot 2(p^{k-1}-2) \dots \frac{1}{2}(p^{k-1}-1) \frac{1}{2}(p^{k-1}+1) = [1, p^{k-1}]_p,$$

we can write:
$$[p^k - p^{k-1}, p^k]_p = [1, p^{k-1}]_p + p^{2k-1}(p-1)[1, p^{k-1}]_p \cdot \frac{1}{2} \left\{ \frac{2}{1(p^{k-1}-1)} + \dots \right\} + p^{4k-2}Q =$$
$$= [1, p^{k-1}]_p + \frac{1}{2} p^{2k-1}(p-1)[1, p^{k-1}]_p \times$$
$$\times \left\{ \frac{1}{1(p^{k-1}-1)} + \dots + \frac{1}{(p^{k-1}-1)1} \right\} + p^{4k-2}Q,$$

which is what lemmy proves at $p > 2$.
The case $p = 2$ is considered according to the same scheme.
Lemma 12.

$$1^2 + 2^2 + \dots + (p-1)^2 + (p+1)^2 + \dots + (p^{k-1}-1)^2 =$$
$$= \frac{1}{6} p^{k-1}(p^{k-1}+1)(2p^{k-1}+1) - p^k L, \quad p > 2$$
(all numbers coprime to $p$ are written down on the left side).
Proof. It is enough to represent the left side in the form
$$\sum_{i=1}^{p^{k-1}} i^2 - p^2 \sum_{i=1}^{p^{k-2}} i^2$$

and calculate both sums according to Lemme 1.
Theorem. The following equality is fair:
$$C_{p^k}^{p^{k-1}} - C_{p^{k-1}}^{p^{k-2}} = p^{3k-1} R, \quad p > 3;$$
$$C_{3k}^{3k-1} - C_{3k-1}^{3k-2} = 3^{3k-2} S;$$
$$C_{2k}^{2k-1} - C_{2k-1}^{2k-2} = 2^{3k-3} T,$$

where $k \geqslant 3$ and $R, S, T$ are integers.
The proof of the theorem is carried out by sequential use of lemme 9, 11, 6, 12, 2.

Comment. From the proof of the theorem, one can additionally see that the numbers $S$ and $T$ indicated in the theorem are not divisible by 3 and 2, respectively. The author does not know how things stand in the general case - whether the number $R$ is divisible or not divisible by $p$.

Literature Cited

1. Fuchs D. B., Fuchs M. B., Arthmetic of biomp coefficients. «Kvant» No. 6, 1970, pp. 17-25.
2. Sominsky I. S., Method of mathematical induction. M., Fizmatgiz, 1961.
3. Egorov A. A., Comparisons by modulus and arithmetic of remainders. «Kvant» No. 5, 1970, pp. 27-33.

Editor's note. As reader Yu. Trakhtman (Dnepropetrovsk) told us, he managed to obtain certain numbers for which the numbers $R, S, T$ appearing in the theorem are not divisible by $p, 3, 2$, respectively. However, this result is formulated in terms unfamiliar to schoolchildren and is proven by non-trivial means.
