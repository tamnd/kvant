---
id: 1976-5-shihanovich-formula-dlya-prostyih-chisel-8decfc36
issue: kvant_1976_5
year: 1976
number: "5"
title: Formula for prime numbers
authors:
  - Шиханович Ю. А.
rubric: smes
page_first: 44
page_last: 44
page_labels: "42"
tag: TQEU
lang: en
source: kvant_digital
extraction: vision
content_sha256: 163d3b1824bc1081b6efca8dc6deee3aaa8a620d3dbffae08aad1127f0e9b59f
prompt_sha256: draft-1
translated_from: content/ru/1976/05/articles/08_shihanovich-formula-dlya-prostyih-chisel-8decfc36.md
source_content_sha256: 5557cf9ad53fee213edb31bedf31801136e9596d0b32f1d42f3b10fa8f53c79c
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 42⟧

FORMULA
FOR PRIME NUMBERS

Let us denote by $p_n$ the $(n+1)$th prime number in ascending order: $p_0 = 2, p_1 = 3, p_2 = 5, p_3 = 7, p_4 = 11, p_5 = 13$, etc.

It is widely believed that there is no formula that expresses formula (1), it can be seen that the constructed $a$ is the positive wavelength propagating in a paper sheet!

So, the experiment is clear: from the end of an oscillating tube, a circular wave propagates across the paper, which is reflected by the edge of the sheet without changing phase; the incident and reflected waves are correct and therefore interfere; crystals of manganese potassium are thrown off from the maxima of the intensity of oscillations (antinodes of a standing wave) and are collected in minima (nodes), the perfection of which represents a family of hyperbolas.

In conclusion, we offer you a not-so-ordinary task: find in the article those statements that are given without proof, and try to prove them experimentally.

$$sg(n) = \begin{cases} 1, \text{ если } n > 0, \\ 0, \text{ если } n \leqslant 0, \end{cases}$$

how such a formula can already be written (top right, here $E(x)$ is the integer part of the number $x$). A similar formula was sent to the editor by Moscow dessert class teacher V. Gugin.

The trouble is that such formulas are of little use. Firstly, the calculation using them is no shorter than the calculation using the Eratovsen sieve algorithm («Kvant», 1973, No. 4, p. 72 and 1974, no. 1, p. 77). Secondly, with their help it is difficult to study the “behavior” of a set of prime numbers “at infinity” (i.e., at $n \rightarrow +\infty$ or, as mathematicians say, the “asymptotic behavior” of a set of prime numbers.

Nevertheless, apparently, the given formula will satisfy the needs of a small part of the readers «Kvant».

How to prove the proposed formula? In number theory, $\pi(m)$ denotes the number of prime numbers not exceeding $m$. Easy to assemble that

$$sg(n + 1 - \pi(m)) = \begin{cases} 1, \text{ если } m < p_n, \\ 0, \text{ если } m \geqslant p_n. \end{cases}$$

Now let $\mu$ be an arbitrary “upper estimate” for $p_n$, i.e., a function such that for all $n$ we have $p_n \leqslant \mu(n)$.

Then

$$p_n = \sum_{m=0}^{n^2+1} sg(n + 1 - \pi(m)).$$

Let further $\chi - \chi_{\text{карактическая функция}}$ be representable, i.e., a function such that

$$\chi(k) = \begin{cases} 1, \text{ если } k - \text{ простое число}, \\ 0, \text{ если } k - \text{ составное число}. \end{cases}$$

Obviously,

$$\pi(m) = \sum_{k=2}^{m} \chi(k).$$

Then

$$p_n = \sum_{m=0}^{n^2+1} sg(n + 1 - \sum_{k=2}^{m} \chi(k)).$$

In order to obtain a specific formula from formula (1), it is necessary to substitute expressions for the function $x$ and $\mu$ into it.

Our formula is precisely obtained from formula (1) for $\mu(n) = n^2 + 1$ (in number theory it has been proven that $p_n \leqslant n^2 + 1$ for all $n$) and

$$\chi(k) = \frac{[(k - 1)!]^2 - k \cdot E \left( \frac{[(k - 1)!]^2}{k} \right)}{2}.$$

Formula (2) is obtained using Wilson's theorem: if $k - \text{ простое число},$ then $(k - 1)! + 1$ is divisible by $k$.
