---
id: 1984-11-belkin-uravnenie-volnyi-49e6b1ca
issue: kvant_1984_11
year: 1984
number: "11"
title: Wave equation
authors:
  - Белкин И. К.
rubric: shkola-v-kvante
page_first: 29
page_last: 30
page_labels: 27-28
tag: W91Y
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0f06d6ce6b9a216106cbd618605c4e01bfca1fbe5d1b6530c133d47fda263dd0
prompt_sha256: draft-1
translated_from: content/ru/1984/11/articles/08_belkin-uravnenie-volnyi-49e6b1ca.md
source_content_sha256: e7b7b8e04e213276c061685dbb93de55eade308d4426b577265fe7910e3e3e15
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 27⟧

English physicist Thomas Endris brought final clarity to this issue. In 1869, he published the results of his many years of experiments. Like Van Marum, Endries studied the behavior of gas as its volume decreases and pressure increases. But if Van Marum conducted experiments only at room temperature, then Endries conducted experiments at a variety of temperatures.

In figure 3 the solid lines show the curves obtained by Endris. He also observed the appearance of liquid at pressures that correspond to the horizontal sections of the curves. But with increasing temperature, these pressures gradually increased, and the width of the horizontal sections became smaller, until at some temperatures, denoted by figure 3 through $T_k$, the horizontal section on the curve disappeared completely. At the same time, the boundary between liquid and vapor also disappeared - something that was observed by Cagnard de Latour.

Above this temperature, called the critical temperature by Endris, the substance cannot be liquid. Liquid and saturated vapor above it can be observed only in that region of pressure and volume, which at figure 3 is limited by the dashed line. If the gas temperature is higher than $T_k$, then cooling is necessary for its combustion.

After Endris's work, it became clear that “permanent” gases are not constant at all. It’s just that their critical temperatures are much lower than room temperatures. From that time on, the struggle to burn “permanent” gases turned into a struggle to obtain low temperatures. It took another 40 years before it was possible to burn all the gases without exception. So in 1877, nitrogen ($T_k = 126,3$ K) and oxygen ($T_k = 154,8$ K) were burned. In 1898, liquid hydrogen ($T_k = 33,2$ K) was obtained. Another 10 years later, in 1908, the last gas, helium ($T_k = 5,2$ K), was turned into liquid. This marked the beginning of the development of one of the most important areas of physical science—low-temperature physics.

Thus, for substances known to us as gases, room temperature is higher than their critical temperature. That's why they are gaseous. On the contrary, for substances that we are accustomed to being liquid, room temperature is lower than their critical temperature.

Wave equation

A wave, as is known, is the process of propagation of vibrations in space. In order for a wave in a medium to propagate, the points of the medium must be connected to each other by bonds capable of causing vibrations, that is, by elastic bonds. figure 1 shows a number of such interconnected points. If one of the points, for example point $O$, begins to oscillate, then its oscillations move in the direction $r$.

Let the point $O$ oscillate along the axis $X$ according to the law

$$x = x_m \sin \omega t. \tag{1}$$

Here time $t$ is counted from the moment when point $O$ is in the equilibrium position. Its vibrations spread to other points not instantly, but at a certain speed $v$. This means that per unit time the oscillation must reach a point in the series located from the point $O$ at a distance numerically equal to $v$. The distance over which the oscillation propagates in a time equal to one period $T$ of oscillations is called the wavelength $\lambda$ (“Physics 10”, p. 81). It follows that

$$\lambda = vT, \text{ или, так как } T = \frac{1}{v}, \quad v = \lambda v.$$

Any point in our row (see Fig. 1), as soon as a wave reaches it, begins to oscillate with the same frequency as point $O$, that is, it will repeat these oscillations. But repeat with some delay - after all, to a point located from $O$ at a distance of $r$, the oscillation should occur after a time interval equal to $r/v$. Therefore, for the coordinate $x$ of a point at a distance $r$ we must write

$$x = x_m \sin \omega \left( t - \frac{r}{v} \right). \tag{2}$$

⟦folio 28⟧

Equation (2) is called the *wave equation*. It allows you to find the displacement $x$ from the equilibrium position of any point (located at any distance $r$) at any time. For a given moment in time, it gives, as it were, a photograph of the positions of all points of the series relative to the $X$ axis. The wave equation shows that all points actually oscillate the same way (all oscillate along the $X$ axis, and all have the same amplitude and frequency of oscillation). Only the phases of the oscillations are different - the difference in the phases of the oscillations of two points, the distance between which is $\Delta r$, is $\omega \Delta r/v$.

Sometimes it is more convenient to present the wave equation a little differently. Let us rewrite equation (2) in the form

$$x = x_m \sin \left( \omega t - \frac{\omega r}{v} \right).$$

Let us substitute into the second term in brackets instead of the wave speed $v$ the value $\lambda$ equal to it, and together with $\omega$ we write $2\pi v$. Then we get

$$x = x_m \sin \left( \omega t - \frac{2\pi r}{\lambda} \right).$$

From this expression it is clear that the coordinate $x$ of any point at a distance $r$ from the wave source depends on the value $r/\lambda$, that is, on the number of wavelengths that fit at a distance $r$. If, for example, $r=\lambda$, then the phase lag will be equal to $2\pi$, which means that the oscillation phase of this point will be the same as that of point $O$. In the same way, if $r=2\lambda$, $3\lambda$, etc., then the phase shift will be equal to $4\pi$, $6\pi$, etc., that is, in this case the phases will be the same. Thus, wave points located from each other at a distance equal to the wavelength, two wavelengths, in general

$$\varphi_1 - \varphi_2 = \frac{2\pi}{\lambda} \left( r_1 - r_2 \right).$$

Pozny's gain condition (maxims) has the form

$$\varphi_1 - \varphi_2 = \frac{2\pi}{\lambda} \left( r_1 - r_2 \right) = 2\pi k,$$

where $k=0, 1, 2, \dots,$

where

$$r_1 - r_2 = k\lambda = 2k \frac{\lambda}{2}$$

- the oscillations will be amplified (that is, the amplitudes of the complex oscillations will be equal to the sum of the amplitudes of the added oscillations) if the difference in the path $r_1 - r_2$ of the waves to the place of “meeting” is equal to an even number of half-terms. Accordingly, the minims are strengthened -

$$\varphi_1 - \varphi_2 = \frac{2\pi}{\lambda} \left( r_1 - r_2 \right) = (2k+1)\pi,$$

or

$$r_1 - r_2 = (2k+1) \frac{\lambda}{2}$$

- the oscillations will be weakened (the resulting amplitudes will be equal to the difference in the amplitudes of the oscillations in two waves), if the difference in the wave paths is equal to an even number of half-terms.
