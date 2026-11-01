---
id: 1985-12-yavelov-formula-balmera-74d1a57e
issue: kvant_1985_12
year: 1985
number: "12"
title: Balmer formula
authors:
  - Явелов Б. Е.
rubric: raznoe
rubric_sub: Разное
page_first: 18
page_last: 19
page_labels: 16-17
tag: S7J1
lang: en
source: kvant_digital
extraction: vision
content_sha256: a4b345afd950dd4703538eec40db24b9c3a8241fc41658dfa94378cdc2df52bf
prompt_sha256: draft-1
translated_from: content/ru/1985/12/articles/05_yavelov-formula-balmera-74d1a57e.md
source_content_sha256: 3719af10778ff930ed3a4e655821798c6b1c1d9d8b8fe999c46d7e061ef4ee9c
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 16⟧

Some remarkable inequalities

1. Cauchy's inequality:
$$\frac{a_1 + a_2 + \dots + a_n}{n} \geq \sqrt[n]{a_1 \dots a_n} = G.$$

Proof. We can assume that $a_1 \geq a_2 \geq \dots \geq a_n$. Consider sets of numbers
$$\frac{a_1}{G}; \frac{a_1 a_2}{G^2}, \dots, \frac{a_1 a_2 \dots a_n}{G^n} = 1,$$
$$\frac{G}{a_1}; \frac{G^2}{a_1 a_2}, \dots, \frac{G^n}{a_1 \dots a_n} = 1.$$

These sets are ordered in opposite ways. That's why
$$n = \frac{a_1}{G} \cdot \frac{G}{a_1} + \frac{a_1 a_2}{G^2} \cdot \frac{G^2}{a_1 a_2} + \dots + \frac{a_1 \dots a_n}{G^n} \leq \frac{a_1}{G} \cdot 1 + \frac{a_1 a_2}{G^2} \cdot \frac{G}{a_1} + \dots + \frac{a_1 a_2 \dots a_n}{G^n} \times \frac{G^{n-1}}{a_1 a_2 \dots a_{n-1}} = \frac{a_1 + a_2 + \dots + a_n}{G}.$$

2. Chebyshev's inequality. If $a_1 \geq a_2 \geq \dots \geq a_n > i$ and $b_1 \geq b_2 \geq \dots \geq b_n \geq 0$, then
$$n (a_1 b_1 + a_2 b_2 + \dots + a_n b_n) \geq \geq (a_1 + a_2 + \dots + a_n) (b_1 + b_2 + \dots + b_n).$$

Proof. Adding $n$ inequalities
$$a_1 b_1 + \dots + a_n b_n \geq a_1 b_1 + a_2 b_2 + \dots + a_n b_n,$$
$$a_1 b_1 + \dots + a_n b_n \geq a_1 b_2 + a_2 b_3 + \dots + a_n b_1,$$
$$a_1 b_1 + \dots + a_n b_n \geq a_1 b_n + a_2 b_1 + \dots + a_n b_n,$$
we get what we need.

Our calendar

Balmer formula

“As soon as I saw Balmer’s formula, everything immediately became clear to me,” N. Bohr said in general about the final stage of his work on the creation of the quantum theory of the atom.*)

This year marks 100 years since this formula, which was to play an outstanding role in the history of science, became known to a wide circle of scientists. It was first published by Balmer in 1884, but almost no one knew about it until an article appeared in a German physics journal in 1885.

The Swiss Johann Jacob Balmer (1825-1898), having received a university mathematical education, from the 60s to the 90s, taught mathematics in Basel at a gymnasium for girls and taught classes in descriptive geometry at the local university.

Balmer's range of interests was very wide - philosophy and literature, music and architecture, ancient history and the history of the natural world, medicine. But how useful mathematics is, he was most attracted to the search for mathematical harmony, concrete - regular numerical relationships: in the shapes of crystals, in the geometric parameters of the significant parameters of architecture, etc. It was this fascination with the “magic of numbers” that led the Basel teacher to his remarkable discovery.

This is the task that

⟦folio 17⟧

Shiel Balmer. The data is four hours.

6562,10; 4860,74; 4340,10; 4101,2.

It is required to find the “law” that they follow.

Anyone who wants to solve this problem on their own (and for this you will not need anything other than elementary mathematics) should stop reading the note here for a while, since the answer is given a little further.

The numbers, the regularity of which by Neil Balmer, are the wavelength (10⁻¹⁰ m) of four lines in the visible region of the spectrum of the hydrogen atom. In physics, Balmer was the greatest in diameter and came to the formulation of the problem by accident - after listening to a lecture by a physics professor on spectral research. It must be said that the series of lines in the hydrogen spectrum has been well known to professional physicists since at least 1868. But in their attempts to establish the spectral law, physicists were invariably guided, as it turned out later, by an actic analogy that had nothing to do with the matter: the lines of the series were likened to an overtone of sound and expressions of the form λ/n were sought for them, where λ is some fundamental wavelength, and n is an integer. At the same time, for the spectra of different elements, different sets of integers were obtained, between which no connection was made.

Perhaps Balmer was helped by the fact that he was not a physicist. Not deterred by any demands, he was only looking for a simple formula that would most accurately reproduce the detected wavelength of the spectral series. And the result of these attempts became the famous “Balmer formula”:

$$\lambda = \frac{n^2}{n^2 - 2^2}.$$

Here λ is the wavelength of the spectral line, d is some constant (equal to 3645.6 · 10⁻¹⁰ m), and n are integers. The four hydrogen lines shown are obtained from this formula by substituting for n the values ​​3, 4, 5 and 6, respectively. How the scientist came to this formula is not known, but there are indirect indications that he relied on a fairly simple geometric space.

Having received his formula, which surprisingly accurately describes four waves, Balmer still agreed - whether he had found a physical pattern or whether its result was just a consequence of a striking coincidence. Having read a popular reference book on the latest scientific achievements, he learned that another, fifth line of the hydrogen series with a wavelength of 3969 · 10⁻¹⁰ m is known (this is the invisible ultraviolet region of the spectrum). Substituting n=7 into his formula, Balmer received λ=3969 · 10⁻¹⁰ m! This success greatly strengthened his confidence in the formula, and he showed its quantity to the University of Basel, professor of physics. He reported the discovery with great interest and told Balmer that, in fact, nine more lines were known in the ultraviolet part of the hydrogen spectrum. It was not difficult to verify that these lines are perfectly described by the “magic” formula (with the substitution n = 8, 9, ..., 16). There was no other alternative than that some new fundamental law of nature had been found.

In 1890, the Swedish physicist I. Rydberg (1854-1919) wrote down Balmer’s formula somewhat differently:

$$v = \frac{c}{\lambda} = Rc \left( \frac{1}{2^2} - \frac{1}{n^2} \right)$$

(v is the frequency of the spectral line, c is the speed of light, and R is a functional physical constant, which is now called the “Rydberg constant”). Named in this entry, Balmer's formula was presented by Bohr in February 1913. Taking into account the expression for the quantum energy hv (h is Planck’s constant), Bohr immediately unraveled the physical meaning of the formula, which remained perfect for almost three decades. And this meaning is presented precise and clear - the spectral lines correspond to a quantum of electromagnetic radiation emitted by electrons when jumping from orbit with number n (n = 3, 4, etc.) to the 2nd orbit closer to the nucleus.

Two statements are very often repeated: 1) scientists make major scientific discoveries only in their youth; 2) such discoveries cannot be arrived at. The story of Balmer's discovery clearly demonstrates that there are exceptions.

V. E. Yavelov
