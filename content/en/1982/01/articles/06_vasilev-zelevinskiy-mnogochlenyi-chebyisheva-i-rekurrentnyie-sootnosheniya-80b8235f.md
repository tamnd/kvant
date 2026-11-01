---
id: 1982-1-vasilev-zelevinskiy-mnogochlenyi-chebyisheva-i-rekurrentnyie-sootnosheniya-80b8235f
issue: kvant_1982_1
year: 1982
number: "1"
title: Chebyshev polynomials and recurrence relations
authors:
  - Васильев Н. Б.
  - Зелевинский А. В.
rubric: osnovnye-stati
page_first: 14
page_last: 21
page_labels: 12-19
tag: S5J3
lang: en
source: kvant_digital
extraction: vision
content_sha256: 48e5cf5b9ed478cff61f217abf4fc22ea003522441e67ed93dcce9bd29d0c3ad
prompt_sha256: draft-1
translated_from: content/ru/1982/01/articles/06_vasilev-zelevinskiy-mnogochlenyi-chebyisheva-i-rekurrentnyie-sootnosheniya-80b8235f.md
source_content_sha256: a2d1b2cfc3577aa284ec1159bc1fe4d2caadca5f9279d91343c97dc38cf9a8fe
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 12⟧

Chebyshev polynomials and recurrence relations

There is a widespread view of a mathematician as a person who is constantly engaged in the most complex arithmetic calculations (in a more sophisticated version, writing out and transforming lengths and complex formulas). Readers «Kvant» are well aware that there is beautiful and important mathematics “without formulas”; there is still a single truth in such a view. The ability to look at formulas from the necessary point of view, transform them, discover new ones, and find connections between them is an important part of the work of mathematicians. In this article we will look at a number of interesting formulas related to the meaning of the sequence of “Chebyshev polynomials” (some of these formulas were proposed to be proven in problem M488 - «Kvant», 1978, No. 2), as well as the general mathematical ideas that stand behind them.

Introduction. Two remarkable sequences of polynomials

The polynomials that will be discussed are found in many problems in analysis, computational mathematics, and algebra. They appeared in 1854, in the work of the Russian mathematician Pafnutya Lvovich Chebyshev in connection with this question.

Consider all possible polynomials of a given degree $n$ with leading coefficient 1; which of them deviates least from zero on the segment $[-1; 1]$, that is, for each polynomial $F_n(x) = x^n + \dots$ the quantities

$$c_n = \max_{[-1; 1]} |F_n(x)|$$

smallest?

It turns out that this is $\bar{T}_n(x) = \frac{1}{2^{n-1}} T_n(x)$ - the polynomial from the left column of Table 1, divided by the leading coefficient. For example, among square trinomials it is $x^2 - \frac{1}{2}$ (its deviation from zero $c_2$ is equal to $\frac{1}{2}$, and for any other square trinomial $x^2 + px + q$ it is greater); among cubic polynomials it is $x^3 - \frac{3}{4} x$ (for it $c_3 = \frac{1}{4}$); and in general the deviation from zero $c_n = \frac{1}{2^{n-1}}$ of the polynomial $\bar{T}_n(x)$ is less than that of any other polynomial $F_n(x) = x^n + \dots$ of degree $n.*$).

Table 1. Chebyshev polynomials of the first and second kind. If you multiply each of the polynomials by 2x and subtract the previous one (standing above it), you get the next one.

| $n$ | $T_n$ | $U_n$ |
| :--- | :--- | :--- |
| 0 | 1 | 1 |
| 1 | $x$ | $2x$ |
| 2 | $2x^2 - 1$ | $4x^2 - 1$ |
| 3 | $4x^3 - 3x$ | $8x^3 - 4x$ |
| 4 | $8x^4 - 8x^2 + 1$ | $16x^4 - 12x^2 + 1$ |
| 5 | $16x^5 - 20x^3 + 5x$ | $32x^5 - 32x^3 + 6x$ |
| 6 | $32x^6 - 48x^4 + 18x^2 - 1$ | $64x^6 - 80x^4 + 24x^2 - 1$ |
| 7 | $64x^7 - 112x^5 + 56x^3 - 7x$ | . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . in in in in klyrsys s s teipetss neypets teipetss teipets teipets teipets teipets teipets teipets teipets teipets teipets teipets teipets teipets teipets teipets teipets teipets teipets teipets teipets teips

⟦folio 13⟧

If the deviation from zero is changed differently, replace the expression $c_n$ with the expression

$$l_n = \sum_{-1}^{1} |F_n(x)| dx,$$

then the least deviating from zero polynomial of the $n$th degree with the leading coefficient 1 is the polynomial $\tilde{U}_n(x) = \frac{1}{2^n} U_n(x)$, where $U_n(x)$ is taken from the right column of Table 1: for the polynomial $U_n(x)$ the values ​​$l_n$ (blue area on figure 1) are equal to 2; therefore, for $\tilde{U}_n$ it is equal to $1/2^{n-1}$; for any other polynomial $F_n(x) = x^n + \dots$ it is greater (theorem of A. N. Korkin and E. I. Zolotarev).

These facts are related to the following characteristic properties of Chebyshev polynomials:

1°. The values ​​of the polynomial $T_n$ at all extremum points and at the ends of the segment [—1; 1] are identical modulo. The area of ​​each of the $n+1$ pieces bounded by the graph of the polynomial $U_n(x) = \frac{1}{n+1} T'_{n+1}(x)$, the Ox axis and the lines $x = \pm 1$ is the same (Fig. 1).

(Only polynomials obtained from the equalities $y = U_n(x)$ and $y = T_n(x)$ by a linear change of variables $x$ and $y$ have similar properties.)
Property 1° follows from the basic relations

$$2^\circ. T_n(\cos \varphi) = \cos n\varphi, \quad \sin \varphi \cdot U_{n-1}(\cos \varphi) = \sin n\varphi.$$

*) We will not prove this here. An elementary proof can be found in [1], the first book in the bibliography at the end of the article.

At $r=1$:
$$y = T_n(x),$$
at $r=2$:
$$y = Q_n(x)$$

At $r=1$:
$$y = U_{n-1}(x),$$
at $r=2$:
$$y = P_{n-1}(x)$$

Fig. 1. If a sheet of paper $0 \leqslant x \leqslant 2\pi r, -r \leqslant y \leqslant r$ with a graph $y = r$ cos $nx$ drawn on it is rolled into a cylinder (diameter and height $2r$) and looked at from the side so that the graphs on the front and back halves coincide, we will see the graph of the $n$-th Chebyshev polynomial of the first kind. These graphs at $n=2,3,4,5$ are shown in the top row (when choosing a scale $r=1$, graphs $y = T_n(x)$ are obtained, at $r=2$, graphs $y = Q_n(x)$ are obtained - see exercise 3). In the bottom row, under the $n$-th polynomial, its derivative divided by $n$ is depicted; this is the $(n-1)$th Chebyshev polynomial of the second kind; all of his $n$ blue figures have the same area.

⟦folio 14⟧

In addition to the trigonometric formulas $2^\circ$, which determine the values ​​of the polynomials $T_n$ and $U_n$ for $|x| \leq 1$, for $|x| > 1$ there are completely different-looking identities:

$$3^\circ. \quad T_n(x) = \frac{(x + \sqrt{x^2 - 1})^n + (x - \sqrt{x^2 - 1})^n}{2},$$

$$U_n(x) = \frac{(x + \sqrt{x^2 - 1})^{n+1} - (x - \sqrt{x^2 - 1})^{n+1}}{\sqrt{x^2 - 1}}.$$

The roots of the polynomials $T_n$ and $U_n$ are visible from the following pair of identities:

$$4^\circ. \quad T_n(x) = 2^{n-1} \left( x - \cos \frac{\pi}{2n} \right) \left( x - \cos \frac{3\pi}{2n} \right) \dots \left( x - \cos \frac{(2n-1)\pi}{2n} \right),$$

$$U_n(x) = 2^n \left( x - \cos \frac{\pi}{n+1} \right) \left( x - \cos \frac{2\pi}{n+1} \right) \dots \left( x - \cos \frac{n\pi}{n+1} \right).$$

Thus, the roots and extremum points of the polynomial $T_n(x)$ are the projects of the vertices of a right $4n$-gon with diameter $[-1; 1]$ by this diameter (Fig. 1).

Below we will prove, along with others, the correspondences $2^\circ - 4^\circ$ and illustrate some important methods of algebraic transformations using their example.

Any of the formulas written above could be taken as the definition of Chebyshev polynomials, but it is more convenient for us to base it on a simple recurrent relationship between them, which is described in the caption to Table 1, and derive all the formulas from it.

Below we propose to deal with polynomials obtained from $T_n$ and $U_n$ by changing the scale (see Fig. 1): $P_n(x) = U_n(x/2)$, $Q_n(x) = 2T_n(x/2)$; the role that the segment $[-1; 1]$ plays for $T_n$ and $U_n$ will now be played by the segment $[-2; 2]$. The good thing about the new polynomials is that they have integer coefficients, and their leading coefficients are equal to 1. (Of course, the transition formulas, rewritten in the “reverse” form: $P_n(2x) = U_n(x)$, $Q_n(2x) = 2T_n(x)$, allow us to return to the polynomials $U_n$ and $T_n$ at any time.) As a rule, we will prove something for $P_n$, offer similar properties of $Q_n$ to the reader as an exercise. We urge him to arm himself with a pencil and paper and do all the calculations in detail, first for specific small values ​​$n = 2, 3, 4, \dots$ (until everything becomes clear).

Recurrence relations and induction

Let's put $P_0(x) = 1$, $P_1(x) = x$ and

$$P_{n+1}(x) = x \cdot P_n(x) - P_{n-1}(x).$$

(1)

Let us write down the first few terms of this sequence. Following $P_0(x) = 1$ and $P_1(x) = x$ are

$$P_2(x) = x^2 - 1,$$

$$P_3(x) = x(x^2 - 1) - x = x^3 - 2x,$$

$$P_4(x) = x(x^3 - 2x) - (x^2 - 1) = x^4 - 3x^2 + 1,$$

$$P_5(x) = x(x^4 - 3x^2 + 1) - (x^3 - 2x) = x^5 - 4x^3 + 3x$$

etc. (for polynomials up to $P_{12}$ you can check the results in Table 2).

Polynomials $P_n(x)$ arise in different situations. Consider, for example, fractions

$$R_1(x) = x, \quad R_2(x) = x - \frac{1}{x}, \quad R_3(x) = x - \frac{1}{x - \frac{1}{x}},$$

$$R_4(x) = x - \frac{1}{x - \frac{1}{x}}, \quad R_5(x) = x - \frac{1}{x - \frac{1}{x}}, \dots$$

⟦folio 15⟧

Such “multi-story” (so-called continued) fractions are a useful tool for various problems about approximations of numbers and functions; By the way, P. L. Chebyshev is also involved in them.

After transformation it turns out

$$R_2(x) = \frac{x^2 - 1}{x}, \quad R_3(x) = \frac{x^3 - 2x}{x^2 - 1},$$

$$R_4(x) = \frac{x^4 - 3x^2 + 1}{x^3 - 2x}, \quad R_5(x) = \frac{x^5 - 4x^3 + 3x}{x^4 - 3x^2 + 1},$$

(check!). We see that the numerators and denominators in the standard notation of these fractions are precisely the polynomials $P_n(x)$.

Another example: consider the function sin $n\varphi$ and construct an expression for it through sin $\varphi$ and a polynomial in cos $\varphi$:

$$\sin 2\varphi = 2\sin \varphi \cdot \cos \varphi,$$

$$\sin 3\varphi = \sin \varphi \cdot (4\cos^2 \varphi - 1),$$

$$\sin 4\varphi = \sin \varphi (8\cos^3 \varphi - 4\cos \varphi)$$

(check!). It turns out that sin $n\varphi = \sin \varphi \cdot P_{n-1}(2\cos \varphi)$ for all $n \geqslant 1$; in other words, for sin $\varphi \neq 0$

$$P_n(2\cos \varphi) = \frac{\sin(n+1)\varphi}{\sin \varphi}.$$

The resulting correspondences are easy to obtain using the method of mathematical induction and formula (1). Indeed, $R_{n+1}(x) = x - \frac{1}{R_n(x)}$. Therefore, if we assume that for some $n$

$$R_n(x) = \frac{P_n(x)}{P_{n-1}(x)},$$

then from correspondence (1) it is easy to obtain a similar equality for $n$ increased by 1:

$$R_{n+1}(x) = x - \frac{P_{n-1}(x)}{P_n(x)} = \frac{xP_n(x) - P_{n-1}(x)}{P_n(x)} = \frac{P_{n+1}(x)}{P_n(x)},$$

which is what is required.

Similarly for sines: if we assume that for $k=n-1$ and $k=n$

$$\sin(k+1)\varphi = \sin \varphi \cdot P_k(2\cos \varphi),$$

then from (1) it follows

$$\sin \varphi \cdot P_{n+1}(2\cos \varphi) = 2\cos \varphi \cdot \sin \varphi \cdot P_n(2\cos \varphi) - \sin \varphi \cdot P_{n-1}(2\cos \varphi) =$$

$$= 2\cos \varphi \cdot \sin(n+1)\varphi - \sin n\varphi = \sin(n+2)\varphi;$$

we used the identity 2 cos $\alpha$ sin $\beta = \sin(\alpha + \beta) + \sin(\beta - \alpha)$.

⟦folio 16⟧

(Note that we carried out an inductive transition not from $n$ to $n+1$, as usual, but from $n-1$ and $n+1$; in this case, it is necessary to separately check the first two equalities for $n=0$ and $n=1$.)
Exercises
1. Prove using the inductive transition not from $n$ to $n+1$, as usual, but from $n-1$ and $n+1$; in this case, it is necessary to separately check the first two equalities for $n=0$ and $n=1$.
$$P_n(x) = \frac{(x + \sqrt{x^2 - 4})^{n+1} - (x - \sqrt{x^2 - 4})^{n+1}}{2^{n+1}\sqrt{x^2 - 4}}.$$

(We'll come back to it later.)
2. Prove that a) $P_n(2) = n+1$, 6) $P_n(-2) = (-1)^n \cdot (n+1)$. (Do this in three ways: using (1), and also by going to the limit in equality (2) for $\varphi \rightarrow 0$ and $\varphi \rightarrow \pi$ and in equality (3) for $x \rightarrow \pm 2$.)
3. Consider a sequence of polynomials $Q_0(x), Q_1(x), Q_2(x), \dots$ satisfying correspondence (1) and initial conditions $Q_0(x) = 2, Q_1(x) = x$. Write down the first 6 polynomials $Q_n(x)$. Prove the identity.
a) $Q_n(x)/Q_{n-1}(x) = x - \frac{1}{x - \frac{1}{x - \frac{2}{x}}}$ ($n-1$ minutes);
b) $2\cos n\varphi = Q_n(2\cos\varphi)$;
b) at $|x| > 2$
$$Q_n(x) = \frac{(x + \sqrt{x^2 - 4})^n + (x - \sqrt{x^2 - 4})^n}{2^n}.$$
4. Prove that any sequence of polynomials $R_0(x), R_1(x), \dots$ satisfying (1) can be expressed through the sequence $(P_n(x))$ by the formula $R_n(x) = R_1(x) \cdot P_{n-1}(x) - R_0(x) \cdot P_{n-2}(x)$.
Specifically, $Q_n(x) = xP_{n-1}(x) - 2P_{n-2}(x) = P_n(x) - P_{n-2}(x)$. Derive from here all the identities from Exercise 3.

Roots of polynomials and product
Many interesting formulas involving symmetric expressions of $n$ numbers (or letters) turn out to be easily applicable if these numbers are considered as roots of some polynomial of degree $n$. For $n$ numbers $\gamma_k = 2\cos \frac{k\pi}{n+1}$ (where $k=1,2,\dots,n$) our $P_n(x)$ serves as such a polynomial. In fact, substituting in (2) instead of $\varphi$ the value $\frac{\pi}{n+1}$, $\frac{2\pi}{n+1}, \dots, \frac{n\pi}{n+1}$, we see that the numbers $\gamma_k = 2\cos \frac{k\pi}{n+1}$ are the roots of the polynomial $P_n(x)$. Here we need a corollary from Bezout’s theorem: if $\gamma$ is the root of the polynomial $F(x)$, then $F(x)$ is divisible by $x-\gamma$. (Indeed, replacing the variable $x$ with $y=x-\gamma$, we get the polynomial $\tilde{F}(y) = F(x-\gamma)$, which has the root $y=0$, and such a polynomial, very indo, is divisible by $y^*$). Our polynomial $P_n(x)$ must be divisible by each of the bilens $x-\gamma_k$, and therefore by their product; since it has degree $n$ and leading coefficient 1, it is simply equal to the product $\prod_{1 < k < n} (x-\gamma_k)$. So,
$$P_n(x) = \prod_{1 < k < n} (x-2\cos \frac{k\pi}{n+1}).$$

Exercise 5. a) Prove the identity
$$Q_n(x) = \prod_{1 < k < n} (x-2\cos \frac{(2k-1)\pi}{2n}).$$

6) Check it and identity (4) for $n=2,3,4$ and 5.

*) For more information about Bezout’s theorem and expansion into polynomials, see [2].

⟦folio 17⟧

Let us present one interesting fact that follows from a comparison of formulas (4) and (2).

Let us calculate $P_{2m}(0)$ for $m > 0$ in two ways and equate the resulting expressions.

On the one hand, from (2) we obtain

$$P_{2m}(0) = P_{2m}\left(2\cos\frac{\pi}{2}\right) = \left(\sin\frac{(2m+1)\pi}{2}\right)/\sin\frac{\pi}{2} = \sin\left(\frac{\pi}{2} + m\pi\right) = (-1)^m$$

On the other hand, according to (4),

$$P_{2m}(0) = \prod_{1 \le k \le 2m} \left(-2\cos\frac{k\pi}{2m+1}\right).$$

Replacing each $\cos\frac{k\pi}{2m+1}$ at $m+1 \le k \le 2m$ with $\left(-\cos\left(\pi - \frac{k\pi}{2m+1}\right)\right)$, we get

$$P_{2m}(0) = (-1)^m \cdot \left[2^m \cdot \prod_{1 \le k \le m} \cos\frac{k\pi}{2m+1}\right]^2.$$

But the expression in square brackets is positive, since the product includes only the cosines of acute angles; therefore it is equal to 1, that is

$$\prod_{1 \le k \le m} \cos\frac{k\pi}{2m+1} = \frac{1}{2^m}.$$

Let us give a beautiful “verbal” formulation of (5): for $m > 0$ the geometric mean of the cosines of acute angles that are multiples of $\frac{\pi}{2m+1}$ is equal to $\frac{1}{2}$.

Exercises
6. a) Find $P_n(1), P_n(-1), Q_n(1), Q_n(-1)$.

Prove equalities similar to (5):

6) $\prod_{1 \le k \le m} \sin\frac{k\pi}{2m} = \frac{\sqrt{m}}{2^{m-1}}$ ($m \ge 1$);

b) $\prod_{1 \le k \le m} \mathrm{tg}\frac{k\pi}{2m+1} = \sqrt{2m+1}$ ($m \ge 1$);

d) $\prod_{1 \le k \le m} \cos\frac{(2k-1)\pi}{4m} = \frac{\sqrt{2}}{2^m}$ ($m \ge 1$).

7. Find out at what $m$ and $n$

a) the polynomial $P_n$ is divisible by $P_m$;

b) the polynomial $Q_n$ is divisible by $Q_m$.

Generating functions, powers of series and coefficients

In this section we will introduce you to a very fruitful method, widely used in various branches of mathematics - analysis, combinatorics, probability theory - the method of generating functions. This method sometimes allows you to assemble individual members of a sequence, like a “brick,” into one integral “building” and obtain information about the entire sequence at once.

Let us be given the sequence $a_0, a_1, a_2, \dots$. Let us give its generating function the expression

$$f(z) = a_0 + a_1z + a_2z^2 + \dots = \sum_{n \ge 0} a_nz^n.$$

Such mathematical expressions are called formulaic powers of the series. These series can be added, subtracted and variable as general polynomials, one series can be divided by another (if the free term of the divisor series is different from 0), any series can be differentiated and integrated term by term - and all these operations can be used,

⟦folio 18⟧

To obtain new sequences from those already studied. It is often possible to find a simple formula for its generating function from the recurrence relation that defines the sequence, and from the generating function to extract a formula or relationship for the terms of the sequence.

For a finite sequence $a_0, a_1, a_2, \dots, a_n$ the generating function is the polynomial $f(z) = a_0 + a_1z + \dots + a_nz^n$. For example, the polynomial $f_n(z) = (1+z)^n$ serves as a generating function for the biompaul coefficients $C_n^0, C_n^1, \dots, C_n^n$—the terms of the $n$th row of Pascal’s triangle (Table 2):

$$\sum_{0 < k < n} C_n^k z^n = (1+z)^n.$$ (6)

Having differentiated this identity $k$ times and then putting in $z=0$, we find $C_n^k = n(n-1) \dots (n-k+1)/1 \cdot 2 \cdot \dots \cdot k$.

Opening the brackets and isolating the coefficients for $z^m$ in the next identity $(1+z)(1+z)^n = (1+z)^{n+1}$, written in the form

$$(1+z) \left( \sum_{0 < k < n} C_n^k z^k \right) = \sum_{0 < k < n+1} C_{n+1}^k z^k,$$

we obtain the important relation $C_n^m + C_n^{m-1} = C_{n+1}^m$.

The average of infinite sequences has a particularly simple, easily “collapsing” function that produces the geometric progression $b_0=b, b_n=qb_{n-1}$. Replacing the total $f(z) = \sum_{n>0} b_n z^n = b + \sum_{n>1} b_n z^n$ each $b_n$ with $qb_{n-1}$, we get $f(z) = b + qz \sum_{n>1} b_{n-1} z^{n-1} = b + qzf(z)$, whence $f(z)(1-qz) = b$, that is

$$f(z) = \sum_{n>0} b_n z = \frac{b}{1-qz}.$$ (7)

This is, of course, a well-known formula for the sum of an infinite geometric progression (at $|qz|<1$). But using the same technique, we can also obtain the generating function for our sequence of polynomials $P_n(x)$.

Let's put $\Phi(z) = \sum_{n>0} P_n(x) z^n = 1+xz+\sum_{n>2} P_n(x) z^n$. (Here $x$ plays the role of a parameter and below, for brevity, we will write $P_n(x), P_{n-1}(x), \dots$ together as $P_n, P_{n-1}, \dots$.) According to (1), we replace each $P_n$ at $n \geqslant 2$ with $xP_{n-1}-P_{n-2}$. Then

$$\Phi(z) = 1+xz + \sum_{n>2} xP_{n-1} z^n - \sum_{n>2} P_{n-2} z^n =$$

$$= 1+xz+xz \cdot \sum_{n>2} P_{n-1} z^{n-1} - z^2 \cdot \sum_{n>2} P_{n-2} z^{n-2} =$$

$$= 1+xz+xz(\Phi(z)-1)-z^2\Phi(z).$$

Therefore, $\Phi(z) \cdot (z^2-xz+1) = 1$ and

$$\Phi(z) = \frac{1}{z^2-xz+1}.$$ (8)

This simple formula hides all the tricky sequence of polynomials $P_n$ that we have been studying so far! We will “pull out” the individual $P_n$ hidden in it in two different ways.

1) For $|x|>2$, the quadratic equation $z^2-xz+1=0$ has two roots:

$$u = \frac{x+\sqrt{x^2-4}}{2}, \quad v = \frac{x-\sqrt{x^2-4}}{2}.$$ (9)

From $z^2-xz+1=(z-u)(z-v)$, taking into account $uv=1$, we get

⟦folio 19⟧

$$\Phi(z) = \frac{1}{(u-z)(v-z)} = \left( \frac{1}{v-z} - \frac{1}{u-z} \right) \frac{1}{u-v} = \left( \frac{u}{1-zu} - \frac{v}{1-zw} \right) \frac{1}{u-v} = \sum_{n \geq 0} \frac{u^{n+1}-v^{n+1}}{u-v} z^n,$$

that is, $P_n(x) = \left( u^{n+1}-v^{n+1} \right) / (u-v)$; this is formula (3).

2) Let us find from (8) the individual coefficients of each polynomial $P_n(x)$. This is done like this:

$$\Phi(z) = \frac{1}{1-(xz-z^2)} = \sum_{k>0} \left( xz-z^2 \right)^k = \sum_{k>0} \left( \sum_{0<j<k} (-1)^j C_k^j x^{k-j} z^{k+j} \right) = \sum_{n>0} z^n \left( \sum_{j} (-1)^j C_{n-j}^j \cdot x^{n-2j} \right)$$

(we used the formulas for the sum of an infinite geometric progression (7), Newton’s biome (6) and identified the coefficient for $z^n$, which is the $P_n(x)$ we need). Hence,

$$P_n(x) = \sum_{j} (-1)^j C_{n-j}^j x^{n-2j}$$

(for example: $P_6(x) = C_6^0 x^6 - C_5^1 x^4 + C_4^2 x^2 - C_3^3 = x^6 - 5x^4 + 6x^2 - 1$).

Of course, it is possible to prove ready-made formulas (3) and (10) without arbitrary functions - the most remarkable thing is how they arose, almost by themselves, from the short formula (8).

The justification for all the operations with infinite series that we performed - and it is, of course, necessary - could be checked either by noting that, if necessary, according to the model of numerical values $z$, all the series under consideration converge (as (7) for $|z| < 1/|q|$), that is, they represent real functions of $z$, or by checking that for certain formulaically operational additions, multiplications, etc. (each coefficient of the series is expressed through a finite number of others, and $z$ is just a letter!) all the usual laws are fulfilled. You can learn more about the method of arbitrary functions and power series in the books [3], [4], [6].

Exercises

8. Consider the sequence of Fibonacci numbers

$$u_0 = 0, u_1 = 1, u_{n+1} = u_n + u_{n-1}.$$

a) Prove that its arbitrary function is equal to $\frac{z}{1-z-z^2}$. Get me out of here

b) Binet's formula

$$u_n = \frac{1}{\sqrt{5}} \left[ \left( \frac{1+\sqrt{5}}{2} \right)^n - \left( \frac{1-\sqrt{5}}{2} \right)^n \right]$$

(for another derivation of this formula, see [5]).

b) Prove also that $u_n = \sum_{j} C_{n-j}^j$.

9. a) Find an arbitrary function for the sequence of polynomials $Q_n(x)$ from Exercise 3 and use it to prove that (for $|x| > 2$)

$$Q_n(x) = u^n - v^n,$$

where $u$ and $v$ are defined by formulas (9) (this was exercise 3 c)).

6) (For those familiar with complex numbers; see [1]). Check that formulas (3) and (3') at $|x| < 2$ turn into formulas (2) and (2'). (Hint: $u = \cos \varphi + i \sin \varphi, v = \cos \varphi - i \sin \varphi$ if $x = 2 \cos \varphi$.) References

1. A. M. Yaglom and I. M. Yaglom. "Non-elementary problems in an elementary presentation." (“Library of the Mathematical Circle”, issue 5) (M., Gostekhtoridat, 1954); problems 130-134.

2. “Selected Questions of Mathematics” (elective course 10), section “Complex numbers and polynomials” (M., “Prosveshcheniye”, 1980).

3. D. Polya, G. Szege. “Task and theorems from analysis” (M., “Nuka”, 1978).

4. Anira Kartan. “Elementary theory of analytical functions of one and several complex variables” (M., “IL”, 1963).

5. N. N. Vorobyov. “Fibonacci Numbers” (“Popular lectures on mathematics”, issue 6) (M., “Nuka”, 1978).

6. N. Ya. Vilenkin. “Combinatorics” (M., “Nuka”, 1969).

7. V. A. Uspensky. “Pascal’s Triangle” (“Popular lectures on mathematics”, issue 43) (M., “Nuka”, 1979).
