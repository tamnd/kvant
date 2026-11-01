---
id: 1978-11-integralom-po-schastlivyim-biletam-4a118026
issue: kvant_1978_11
year: 1978
number: "11"
title: Integral - with lucky tickets!
rubric: raznoe
rubric_sub: Разное
page_first: 54
page_last: 55
page_labels: 52-53
tag: DSYF
lang: en
source: kvant_digital
extraction: vision
content_sha256: 89fdcd6601f3ccc9e25fa7553978e9fd8ec9adde8d7903da97ebc3a364d8e44e
prompt_sha256: draft-1
translated_from: content/ru/1978/11/articles/24_integralom-po-schastlivyim-biletam-4a118026.md
source_content_sha256: 5f56c8dd39ef40e15b21e14707705986703f349ca4afbb7e429e1857d19c2645
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 52⟧

Integalom - with private tickets!

The editor received a letter from our old reader B. Ivyakin. In it he asks the following question:
“The magazine published several articles about lucky tickets. However, the final formula has not been obtained in any of them. Although it is clear to me that it is impossible to set the number of lucky 2n-digit tickets using a simple formula, it still seems to me that such a formula should exist. Am I right or wrong?
Obviously we do not answer such vague questions. However, Boris was lucky - after receiving his letter, we received two answers to his question at once.
We think that other readers will be interested in the formula contained in them.
(We remind you that a ticket is called lucky if the sum of the first three digits is equal to the sum of the last three.)

Are there many lucky tickets? How often do you come across them?

This issue has already been discussed on the pages of our magazine; It was found that out of a million tickets with six-digit numbers (from 000,000 to 999,999), 55,252 were lucky, i.e., approximately one out of every 18 tickets was lucky.

As usual with mathematicians, a more general problem was also solved - about the number of $C_{2n}$ lucky 2n-digit numbers (it is clear what the concept is; for example, 0 035 120 115 is a lucky tenth number). An explicit formula for $C_{2n}$ was not established - only recurrence relations were obtained («Kvant», 1976, No. 12, p. 68).

But then two letters came to the editor. The first was sent in February by M. Mnatsakanyan and A. Melikyan, and the second - in March - by R. Aydagulov. Both contain the same explicit formula for $C_{2n}$. Here is this wonderful formula:

$$C_{2n} = \frac{1}{\pi} \int_{0}^{\pi} \left( \frac{\sin 10x}{\sin x} \right)^{2n} dx. \tag{1}$$

It is interesting that this formula was obtained using completely different methods: M. Mnatsakanyan and A. Melikyan use arbitrary functions (i.e. functional analysis), while R. Aydagulov uses the method of trionometric sums (analytic number theory). Unfortunately, their proofs, although not complicated, still go beyond the scope of school mathematics and cannot be published in our journal. Now we give an elementary proof of formula (1), using the recurrence relations discussed above. Let's remind them.

To do this, let us denote by $P_m(s)$ the number of $m$-digit numbers ($m=1, 2, 3,...$), the sum of the digits of each of which is equal to $s$. Thus, $P_m(s)=0$ at $s<0$ and $s>9m$. Obviously $P_m(0)=1$.

Since a $m$-digit number with a sum of digits $s$ is obtained from a $(m-1)$-digit number with a sum of digits $j$ (where $s-9 \leq j \leq s$) we add the digits $s-j$, we can write

$$P_m(s) = \sum_{j=s-9}^{s} P_{m-1}(j).$$

This is the ratio discussed above. Substituting $s+1$ together with $s$ into them, after subtraction we get

$$P_m(s+1) - P_m(s) = P_{m-1}(s+1) - P_{m-1}(s-9). \tag{2}$$

How to use this relation to calculate $P_m(s)$? Take a look at Fig. 1. If, for a fixed $m$, all $P_{m-1}(s)$ (i.e., all $(m-1)$-row) and at least one element $P_m(s_0)$ of the $m$-th row are known, then formula (2) allows, moving to the right and backwards, to calculate the remaining elements of the $m$-th row (explain!). But for anyone $m$

$$P_m(0) = 1 \tag{2'}$$

And

$$P_1(s) = \begin{cases} 1, \text{ если } 0 \leq s \leq 9, \\ 0, \text{ если } s < 0 \text{ или } s > 9. \end{cases} \tag{2''}$$

⟦folio 53⟧

Thus, formulas (2), (2′), (2″) allow us to calculate all numbers $P_m(s)$.

Let's take any partial 2n-digit number and replace the last $n$ digits with their complements up to 9. Then we get a 2n-digit number whose sum of digits is 9n. It's easy to understand that

$$C_{2n} = P_{2n}(9n).$$

Formula (3) makes it possible to calculate the number $C_{2n}$.

To prove (1), let's put

$$\bar{P}_m(s) = \frac{1}{\pi} \int_0^{\pi} \left( \frac{\sin 10x}{\sin x} \right)^m \cos(9m-2s) x dx.$$

Turns out,

$$\bar{P}_m(s) = P_m(s).$$

From formulas (3), (5) and (4) (1) immediately follows. Thus, we only have to prove (5), for which it is enough to check that the numbers $P_m(s)$ satisfy equalities (2), (2′), (2″). Substituting (4) into (2), we obtain the correspondence

$$\frac{1}{\pi} \left\{ \int_0^{\pi} \left( \frac{\sin 10x}{\sin x} \right)^m \left[ \cos(9m-2s-2) x - \cos(9m-2s) \right] dx \right\} = \frac{1}{\pi} \left\{ \int_0^{\pi} \left( \frac{\sin 10x}{\sin x} \right)^m - 1 \left[ \cos(9m-9-2s-2) x - \cos(9m-9-2s+18) x \right] dx \right\},$$

equal match

$$\int_0^{\pi} \left( \frac{\sin 10x}{\sin x} \right)^m - 1 \left[ \frac{\sin 10x}{\sin x} \right] \left[ \cos(9m-2s-2) x - \cos(9m-2s-11) x - \cos(9m-2s+9) x \right] dx = 0,$$

which is true (it is easy to consider that the trigonometric expression in the square bracket is also effectively equal to zero).

Thus, recurrent correspondence (2) for $\bar{P}_m(s)$ is satisfied. It remains to check the induction basis (2′) and (2″). The second of these correspondences can be verified directly (for example, for $m=1$ and $s>9$ the integrand expression is transformed into the sum of the cosines of angles that are multiples of $x$), but (2′) is not so easy to prove, and we will have to undertake a workaround.

Let us remember that together with (2′) it is enough to check any other correspondence on the $m$th row, for example $\bar{P}_m(10m) = 0$ This is no longer a difficult (but cumbersome) exercise on trigonometric transformations, which we will leave to the reader. This concludes the proof of formula (5).

The attentive reader probably asked himself the question: where did formula (4) come from? Of course, formulaically we can assume that we guessed it in the same way as we “guessed” formula (1). In fact, formula (4), like formula (1), was extracted from a letter from M. Mnatsakanyan and A. Melikayan, i.e., the finished result was used. After all, our method of proof, unlike the method of P. Aydagulov and the method of M. Mnatsakanyan and A. Melikayan, does not make it possible to discover formula (1), but only allows us to check it.

In conclusion, we invite readers to prove the following formulas (1) for the number of cil numbers in the cil system based on the base $k$:

$$C_{2n}^k = \frac{1}{\pi} \int_0^{\pi} \left( \frac{\sin kx}{\sin x} \right)^2n dx.$$
