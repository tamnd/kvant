---
id: 1985-8-fabrikant-chto-takoe-nelineynaya-optika-85de8b1c
issue: kvant_1985_8
year: 1985
number: "8"
title: What is nonlinear optics
authors:
  - Фабрикант В. А.
rubric: osnovnye-stati
page_first: 4
page_last: 8
page_labels: 2, 4, 5, 6
tag: T8YA
lang: en
source: kvant_digital
extraction: vision
content_sha256: 8e2c2239616c160928108e3515393b7619dafba431806ee94521e1a1e22255ee
prompt_sha256: draft-1
translated_from: content/ru/1985/08/articles/04_fabrikant-chto-takoe-nelineynaya-optika-85de8b1c.md
source_content_sha256: d609a94dd73ada5de1acbf46a7d0e603daac982dbd12f7e2be79a3da5d01a7d4
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 2⟧

What is nonlinear optics

Academician of the Academy of Pedagogical Sciences of the USSR
V. A. FAVRIKANT

Over the past twenty years, there has been rapid development of a new branch of physical science - nonlinear optics. To be fair, it must be said that back in the twenties of our century, S.I. Vavilov persistently searched for nonlinear optical effects. The result of these studies was the work of S.I. Vavilov and V.L. Levshin in 1926, in which a nonlinear optic was observed for the first time.

Laser experimental setup for studying nonlinear optical phenomena.
(Photos for the article were taken in the laboratory of laser biophysics and biomedicine of the Faculty of Physics of Moscow State University.

tical effect - a decrease in the absorption coefficient of equalizing glass when light from a bright spark passes through it. In honor of this pioneering work, at the suggestion of Academician R.V. Khokhlov, Soviet conferences devoted to nonlinear optics are called Vwiliv conferences. The creation of lasers in 1960 caused a buccal explosion of work on nonlinear optics.

Before moving on to talk about some nonlinear optical phenomena, let us recall the basic principles of laser optics, which, despite their attractiveness, are in fact far from trivial.

“The imperfection of experience contributes to the development of science”

One of the fundamental principles underlying laser optics is the principle of superposition, according to which when one light wave passes through another, both will propagate without interacting with each other. True, it is often said that during interference, a dark field is formed where one of the interference waves “quenches” the other. This, however, does not mean that the waves interact with each other. Here, the oppositely directed electric fields of both waves simply occur. When the waves interact, these electric fields themselves should change under the influence of each other, which does not occur with interference.

Further we will see that in reality there should always be interaction between waves, but its results are noticeable only when determining the conditions. First of all, when the intensities *) of the interacting waves are large. These are the terms and definition of pops. Thus, S.I. Vavilov is trying to discover

*) Wave intensity is the energy passing through a unit area of ​​the wave front per unit time. The intensity value is proportional to the square of the wave amplitude.

⟦folio 4⟧

no on the speed $c$ of light propagation in vacuum. This leads to the fact that the refractive index of the medium $n=c/v$ turns out to be different from unity.

The electrode mixing caused by the light wave from the common light source, the scales are small. They are determined by the correspondence of the directions of the electric field of the light wave and the internal field. In waves from common light sources, the direction of the field is of the order of $10^9$ V/cm. Thus, when exposed to a light wave field, the displacement of the electrode does not exceed $10^{-6}$ from the atomic radius, which is $10^{-14}$ cm. The value is on the order of percent of the radius of the atomic nucleus!

In laser beams, the field direction reaches $10^6-10^7$ V/cm and, accordingly, the displacements can be horizontally large.

At small relative displacements of the electrode, we can assume that the restoring force acting on the electron is expressed by the law: $F=-kx$, that is, there is a linear dependence of the force $F$ on the displacement $x$ (Hooke’s law for a general spring). However, with an increase in the magnitude of the displacements (for example, in the field of a laser beam), deviations from this law should appear. In the simplest case, which will be considered below, the deviation from the linear dependence can be taken in the form $F=-kx+\alpha x^2$, where the nonlinear term $\alpha x^2$ affects only at sufficiently large displacements (the square of a small value is small compared to the value itself). Note that now the magnitude of the force changes asymmetrically when the sign of the displacement changes (figure 2). It turns out that it is easier to shift an electron to the water side than to the other (for example, at $\alpha>0$ towards positive $x$ it is easier than towards negative ones).

So, we can say that the linear optics approximation corresponds to the choice of a simple linear dependence of the restoring force acting on the electron on the displacement. The world of nonlinear optics begins where deviations from this simple law become significant and the realities of

Let's consider the simplest case, which was already discussed above. The equation of motion of the electrode will have the form

$$ma=-kx+\alpha x^2+eE_0\cos \omega t,$$

(1) where $m$ is the mass of the electrode, $a=x''$ is its acceleration, $eE_0\cos \omega t$ is the force acting on the electron from the electric field of the light wave ($E_0$ is the field amplitude, $\omega$ is the frequency). The task is to find the dependence $x(t)$ from this equation and, on its basis, judge the properties of secondary waves in the medium under consideration. Unfortunately, mathematics does not give us exact methods for solving such nonlinear equations.

The remarkable English physicist Rayleigh, who deals with the theory of colbannias, proposed

⟦folio 5⟧

an approximate method for solving a problem that is highly effective. Since the nonlinear term $ax^2$ manifests itself only for sufficiently large $x$, Raleigh neglected the term $ax^2$ as a zero approximation.
After this, the linear equation remains
$$ma = -kx + eE_0 \cos \omega t$$
the same as the equation of forced oscillations of a weight on the outside under the action of a periodic external force. It is understood that in this case the movement will occur according to the harmonic law, but not with the natural frequency $\omega_0 = \sqrt{k/m}$, but with the frequency $\omega$ of the forced force:
$$x_0(t) = beE_0 \cos(\omega t + \varphi)$$
where $beE_0$ is the amplitude of the forced oscillations of the weight (for convenience of detuning, the factor $eE_0$ is highlighted in the amplitude), and $\varphi$ is the phase shift of this oscillation compared to the phase of the forced force.
To obtain the next approximation, Raleigh replaced in equation (1) the value $x^2(t)$ with the found approximate value $x_0^2(t)$. As a result, equation (1) turns from nonlinear to linear ($x$ is included only in the first degree):
$$ma = -kx + \alpha b^2 e^2 E_0^2 \cos^2 \omega t + eE_0 \cos \omega t.$$ (2)
Using the well-known trigonometric relation
$$\cos^2 \omega t = \frac{1}{2} (1 + \cos 2\omega t)$$
we finally get it
$$ma = -kx + \left( \frac{1}{2} \alpha b^2 e^2 E_0^2 + \frac{1}{2} \alpha b^2 e^2 E_0^2 \cos 2\omega t + eE_0 \cos \omega t \right).$$
From this equation of motion we see that the electron is, as it were, acted upon by three forced forces (the terms enclosed in parentheses). The first of them, independent of time, will simply cause a constant change of electron from the equilibrium position (asymmetry, which we already mentioned above).

The second force, changing with frequency $2\omega$, causes the appearance of a component in the electron displacement, changing with the same frequency $2\omega$. We emphasize that the amplitude of this component is proportional to the square of the amplitude of the light wave. Finally, the last force, changing with frequency $\omega$, is already familiar to us. It corresponds to the field of the incident light wave, due to which secondary waves arise. The amplitude of this component is proportional to the amplitude of the incident light wave. With increasing intensity of the light wave, the role of the second force in relation to the third equation (the square of the larger magnitude increases compared to the magnitude itself).

Thus, the forced oscillations of the electron will consist of two harmonic oscillations with frequencies $\omega$ and $2\omega$. The correspondence and secondary waves emitted by the atoms (ions) of the crystal will consist of waves with the same frequency $\omega$ as the primary wave, as well as waves with a satisfying frequency. It turns out that due to the nonlinear term $ax^2$ in the forces acting on the electron, a secondary wave arises in the crystal with a satisfying frequency (it is called the second harmonic) and thus

The photo refinement shows how an infrared laser beam ($\lambda=1064$ nm) is converted into visible light ($\lambda=532$ nm) when passing through a nonlinear optical medium. The course of the invisible infrared beam from the laser to the nonlinear transformation can be traced by the weak “reflection” beam emerging from the transformer.

⟦folio 6⟧

This violates the principle of frequency construction that reigned in linear optics.

Using nonlinear effects, you can transform the frequency of a light beam without disturbing its direction. This is extremely important for practice, especially in laser technology. For example, a neodymium glass laser produces powerful but invisible infrared radiation with a wavelength of 1064 nm. If you double its frequency, the wavelength will become half as long - 532 nm, which corresponds to green light, perfectly visible to the human eye.

In radio engineering, the nonlinear effect of frequency conversion was observed long before the advent of nonlinear optics. When a powerful radio station was built in Moscow, when receiving broadcasts in Gorky, radio stations located in cities west of Moscow began to listen to Moscow broadcasts. This is explained by the fact that the powerful waves of the Moscow radio station change the ionosphere above Moscow and thereby modulate the passage of radio waves received in Gorky (figure 3).

Synchroism condition

Still, one should not think that converting the frequency of light with a high coefficient of performance (efficiency) is a simple task. Thus, in the work of Franken and his colleagues, published in 1961 and containing a description of the first observed doubling of the frequency of light, the efficiency (that is, the ratio of the intensity of the incoming wave with frequency 2ω to the intensity of the incident wave with frequency ω) is only 10⁻¹⁰! In these experiments, the red light of a ruby ​​laser with a wavelength of 0.6943 microns was converted into ultraviolet radiation with a wavelength of λ = 0.3471 microns (recall that the wavelength is figuratively proportional to its frequency). A square was used as a crystalline nonlinear medium.

In order for the harmonic generation effect to take place fully, it is necessary that the phases of the secondary waves at the output of the crystal be consistent (wave synchroism condition). Only in this case, the addition of secondary waves gives an intense resulting wave.

The atoms are distributed along the entire length of the crystal, through which light passes. Therefore, the secondary waves generated by immi will have different initial phases (figure 4). The farther an atom is from the source, the later the pepper wave should reach it and the later it itself begins to emit a secondary one. On the other hand, this atom, farther from the source, turns out to be closer to the user. Consequently, its secondary wave is given a shorter path than the wave emitted by an atom closer to the light source.

In linear optics, the primary and secondary waves have the same frequencies, and therefore the same propagation speeds in the medium. Therefore, in this case, it does not matter where the transformation of the primary wave into the secondary one occurs - they all arrive at the application with the same phase. The situation is different in nonlinear optics. The refractive index of a medium depends on frequency (dispersion), therefore a secondary wave with a frequency
