---
id: 1979-9-dmitriev-ivlev-elektricheskaya-tsep-izvlekaet-kvadratnyie-korni-1a85587a
issue: kvant_1979_9
year: 1979
number: "9"
title: Electric circuit extracting square roots
authors:
  - Дмитриев Н.
  - Ивлев В.
rubric: smes
page_first: 18
page_last: 18
page_labels: "16"
tag: 11VG
lang: en
source: kvant_digital
extraction: vision
content_sha256: e0976afb67874f6ba1bd04b30e88aa2976665dd21ff8157cd320b771496a8a20
prompt_sha256: draft-1
translated_from: content/ru/1979/09/articles/06_dmitriev-ivlev-elektricheskaya-tsep-izvlekaet-kvadratnyie-korni-1a85587a.md
source_content_sha256: 778ee06817ec2f78b767342d773f4b664884a7a4c39c733ed696cbbe308c7fe0
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 16⟧

servatory). The inner dark kolyu is often referred to as crepe, and its inner edge is greatly eroded.

Currently, the plane of the equator and the rings of Saturn is inclined to the ecliptic plane (to the plane of the Earth's orbit) by 28°, and this inclination persists for a long period of time (in 100 years the inclination decreases by only 47°). Thus, during the period of Saturn’s revolution around the Sun, equal to 29.5 Earth years, the plane of the equator and the rings of the planet retains its direction in space, just as the direction of the Earth’s axis of rotation and the plane of the Earth’s equator are preserved during the Earth’s annual revolution. Therefore, the regulator, every 14.7 Earth years (time intervals equal to half of Saturn’s orbital period), the planet’s rings face the Earth edge-on and are not visible due to their insignificant thickness. Only a narrow strip of the body from the ring can be replaced on the planet's disk. The rings also become invisible when their plane is directed towards the Sun.

This phenomenon, called colsatrin insertion-disappearance, will occur in the fall of 1979 and spring of 1980. From the beginning of the planet's morning visibility in September 1979 until June 1980, ringsatrin will not be visible. Only in December, January and May, in a telescope with no less than meaningful magnification, will it be possible to notice colcesatrin in the form of an extremely thin light strip.

The disappearance of ringsatrin is very rare, and we strongly advise anyone interested in astronomy to observe this planet for almost the entire academic year.

Electric circuit extracting square roots

In the “Collection of Questions and Problems in Physics,” edited by N. Goldfarb, the following problem is given: an electrical circuit is composed of an infinite number of cells, consisting of three identical resistances r (Fig. 1). Find the resistance of this circuit.

To solve, let’s first calculate the resistance R1 of the first cell (open terminals K1, L1). Obviously, R1=3r. Terminals K1, L1 and open terminals K2, L2 are closed again, let’s find the resistance R2 of two cells:

$$R_2 = 2r + \frac{rR_1}{r + R_1}.$$

Likewise,

$$R_3 = 2r + \frac{rR_2}{r + R_2}, \dots,$$

$$R_n = 2r + \frac{rR_{n-1}}{r + R_{n-1}}.$$

where Rn is the circuit resistance with open terminals Kn, Ln, n=1, 2, 3, ... (Fig. 1). For an infinite chain we get

$$R_\infty = 2r + \frac{rR_\infty}{r + R_\infty}.$$

Let's solve this equation for R_\infty:

$$R_\infty = r(1 + \sqrt{3}).$$

In order for this calculation to be correct, it is necessary to prove, taking into account van and the limit, lim Rn=R_\infty. But under our assumptions, this follows from Weierstrass’s theorem (“Algebra and the beginning of analysis 9”, paragraph 32); indeed, the sequence (Rn) is bounded by the number (1+√3) r) and kills monotically (check it out!).

From the answer received it is clear that this circuit allows you to calculate the value of √3 by changing the resistance of the chain when reaching a large number of cells.

Setting the resistance values ​​in the jumpers equal to 2r, we obtain

$$R_\infty = r(1 + \sqrt{5}).$$

For the value 3r

$$R_\infty = r(1 + \sqrt{7}),$$

for the value nr (n is any natural number)

$$R_\infty = r(1 + \sqrt{2n+1}).$$

Our chain “takes the root” of any odd number!

It can be shown that for any real number a≥1 it is possible to select the resistance on the jumpers so that the resistance of the infinite circuit is equal to r(1+√a).

We leave this statement as an assignment to the reader.

N. Dmitriev, V. Ivlev
