---
id: 1977-6-reshenie-zadachi-o-pentamino-dd2677c9
issue: kvant_1977_6
year: 1977
number: "6"
title: '[Solution to the pentomino problem]'
rubric: smes
page_first: 39
page_last: 39
page_labels: "37"
tag: PRET
lang: en
source: kvant_digital
extraction: vision
content_sha256: b94e7c8e14af31c9b2a81d5bd51c837c0d50d8fcadfcbb3d3c26dcfa41700028
prompt_sha256: draft-1
translated_from: content/ru/1977/06/articles/09_reshenie-zadachi-o-pentamino-dd2677c9.md
source_content_sha256: e3d7d308b5557fe46e692bbc709c8a8ab4b9ec6b98cf9142e776b09eab7ba8f4
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 37⟧

then two second-order spectra, etc. As the order of the spectrum increases, the distance between the corresponding lines of the spectra increases, so that the spectra can overlap each other. For example, for sunlight, the spectra of the second and third orders already partially overlap.

Now let's move directly to the experience. To change the wavelength corresponding to a certain color, it is necessary to determine the period of the grating $(d)$, the sine of the angle of incidence of light on the grating $(\sin \theta)$ and the sine of the angle that determines the direction to some maximum, for example, to the first-order maximum $(\sin \varphi_1)$. The grid period is easy to find by playing a record:

$$d = \frac{\Delta R}{n \Delta t}.$$

Here $\Delta R$ is the absolute value of the needle movement along the radius of the plate in time $\Delta t$, $n$ is the number of revolutions per unit time. Usually $d \approx 0,01$ see.

You can use a regular table lamp as a light source. To prevent the light from it from interfering with the observation of the diffraction pattern, make a screen with a slot out of cardboard and cover the lamp with it. In this case, the lamp filament should be visible through the slit. Place the lamp near one wall of the room, place the plate horizontally near the opposite wall and find the image of the slot (Fig. 3). At the same time, you will see blurry color stripes. This is the first order spectrum $(k = 1)$. It is easy to verify that the reality is that the larger the angle $\theta$, the wider the color image of the slit is obtained and the more accurately we can change the angle at which light of the wavelength of interest to us is diffracted.

To determine $\sin \varphi_1$, you need to have a friend sleep and hold the card (or some other object) over the slot so that its image in the light reflected from the grating (as from a flat mirror) coincides with the selected part of the spectrum (see Fig. 3). Having measured $a$, $b$ and $h$ with a ruler, we find $\sin \varphi_1$ and $\sin \theta$:

$$\sin \varphi_1 = \frac{a}{\sqrt{a^2 + b^2}},$$

$$\sin \theta = \frac{a}{\sqrt{a^2 + h^2}}.$$

These expressions can be simplified somewhat. Since $b \ll a$ and $h \ll a$, $$\frac{a}{\sqrt{a^2 + b^2}} = \frac{1}{\sqrt{1 + b^2/a^2}} \approx 1 - \frac{1}{2} \frac{b^2}{a^2}$$

and $$\frac{a}{\sqrt{a^2 + h^2}} = \frac{1}{\sqrt{1 + h^2/a^2}} \approx 1 - \frac{1}{2} \frac{h^2}{a^2}.$$

Then finally

$$\lambda = d | \sin \varphi_1 - \sin \theta | \approx d \frac{|h^2 - b^2|}{2a^2}.$$

Having measured the wavelengths of light of different colors, it is interesting to compare them with the table values. In our experiments, with careful images, the error was of the order of $10^{-8}$ m. For wavelengths of visible light ($\lambda \sim 10^{-7}$ m), such wave accuracy is acceptable.

In the second issue of this year's magazine, we offered our readers several problems related to pentamino. Two readers (L. Mutalup from the Anjan region and Yu. Stasevich from the Voroshilgovgrad region) managed to solve one of the complete set of pentamino simultaneous two rectangles $4 \times 5$ and $4 \times 10$. Their solutions are the same for the small rectangular one and different for the large Volt:
