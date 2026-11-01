---
id: 1985-4-eppel-formula-ploschadi-segmenta-78dfab7b
issue: kvant_1985_4
year: 1985
number: "4"
title: Segment area formula
authors:
  - Эппель Б. С.
rubric: smes
page_first: 48
page_last: 48
page_labels: "46"
tag: XYF9
lang: en
source: kvant_digital
extraction: vision
content_sha256: 75894cdc06b91562ce2c06db84378341c06222c8c1acd01403a62d3f2873f4fc
prompt_sha256: draft-1
translated_from: content/ru/1985/04/articles/17_eppel-formula-ploschadi-segmenta-78dfab7b.md
source_content_sha256: e05c471fd0853ac2408eacb85220d65674c0e55df44037bd89ed8f10983a3518
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 46⟧

F912. A direct current is created in a coil of superconducting wire, which is connected to a current source through a switch $K_1$ (see figure). After this, a battery of two identical capacitors connected in parallel is connected to the end of the coil. The switch $K_1$ is opened, after which current begins to flow through the capacitors, charging them. At the moment of time when the voltage on the capacitors is maximum and the current is zero, the double switch $K_2$ is transferred from base 1 to base 2, so that the capacitors are connected in series, and the voltage on the coil doubles. Since the inductance of the coil has not changed, but the voltage has increased, the maximum current through the coil, and therefore the stored energy, will be greater than the first similar ones. Find the error in the above calculations.

Segment area formula

The area of ​​the segment $AnB$ (Fig. 1) can be found using the formula

$$S_{\text{сегм}} = \frac{\pi R^2}{360^\circ} \cdot a - \frac{R^2}{2} \sin a,$$

(1)

where the central angle $\alpha$ is expressed in degrees; or, if the same angle in radians is $\varphi$, by the formula

$$S_{\text{сегм}} = \frac{R^2}{2} (\varphi - \sin \varphi).$$

(2)

Formula (1) is easy to derive: the area of ​​the segment $AnB$ is equal to the difference between the areas of the sector $OAnB$ ($\frac{\pi R^2}{360^\circ} \cdot a$, that is, the area of ​​the sector of one degree, multiplied by the number of degrees) and the triangle $OAB$ ($\left(R^2/2\right) \sin a$).

This useful formula is not only true when $\alpha < 180^\circ$ (as on figure 1), but also for any $\alpha$, including $\alpha \ge 180^\circ$ (Fig. 2, 3). Indeed, at $\alpha > 180^\circ$ (Fig. 2) the area of ​​the triangle $OAB$ must be added to the area of ​​the sector $OAnB$, but in this case $\sin \alpha < 0$ and formula (2) again gives the correct answer! The case $\alpha = 180^\circ$ also fits formula (2), since then $\sin \alpha = 0$, and the area of ​​the degenerate triangle $OAB$ is equal to zero (Fig. 3).

When passing the angle $\alpha = 180^\circ$, the sign of the sine changes from plane to minus; on figure this will precisely answer the fact that the shaded figures should not be subtracted, but added. A similar effect is observed in the cosine theorem, when the sign changes when passing the angle $\gamma = 90^\circ$.

V. S. Eppel
