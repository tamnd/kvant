---
id: 1985-1-belkin-na-chto-sposoben-mikroskop-a8155239
issue: kvant_1985_1
year: 1985
number: "1"
title: What can a microscope do?
authors:
  - Белкин И. К.
rubric: shkola-v-kvante
page_first: 29
page_last: 30
page_labels: 27-28
tag: 8PL1
lang: en
source: kvant_digital
extraction: vision
content_sha256: 5444d203cee95c0127fe0b11d8ae2127a28fb8bdca36861186bca3889c160ceb
prompt_sha256: draft-1
translated_from: content/ru/1985/01/articles/09_belkin-na-chto-sposoben-mikroskop-a8155239.md
source_content_sha256: 75294d9abece799add0667849147d9cb0fcbd27aad027a9ee994aae71bb71a9f
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 27⟧

sew a job greater or less than $I_1R_1$. In this section, the current source with EMF $\varepsilon_1$ reduces the potential difference (internal external forces do positive work), and therefore we can write:

$$U_{AB} = \varphi_A - \varphi_B = I_1R_1 - \varepsilon_1.$$  (1)

On section $BC$ everything will be exactly the same:

$$U_{BC} = \varphi_B - \varphi_C = I_2R_2 - \varepsilon_2.$$  (2)

In the case of section $CD$, the current source has the opposite polarity compared to previous sources, and therefore it does not reduce, but increases the potential difference (external internal forces perform negative work):

$$U_{CD} = \varphi_C - \varphi_D = I_3R_3 + \varepsilon_3.$$  (3)

In the last section, the circuit is considered; according to our assumption, the current flows from point $A$ to point $D$, and the reading fully corresponds to section $AB$:

$$U_{AD} = I_4R_4 - \varepsilon_4,$$

or, given the selected traversal direction,

$$U_{DA} = \varphi_D - \varphi_A = -U_{AD} = -I_4R_4 + \varepsilon_4.$$  (4)

Adding term-by-term equalities (1)-(4), we obtain:

$$I_1R_1 + I_2R_2 + I_3R_3 - I_4R_4 = \varepsilon_1 + \varepsilon_2 - \varepsilon_3 - \varepsilon_4.$$  (5)

This correspondence expresses Kirchhoff's second rule: for any closed circuit, the allebraic sum of the given direction is equal to the allebraic sum of the emf.

Kirchhoff's rules do not express any new properties of the electric field and therefore cannot be considered as physical laws. The first of them, as we have already said, is a consequence of the law of conservation of charge, the second is a consequence of the law of conservation of energy. However, they are extremely useful when there is no current in branched circuits.

Let's return to the diagram shown in figure and write down the equations expressing Kirchhoff's rules for nodes $A$, $B$, $C$, $F$ and contours $ABCDA$, $AFDA$, $DFCD$:

$$I_5 - I_1 - I_4 = 0,$$
$$I_1 - I_2 = 0,$$
$$I_2 - I_3 - I_6 = 0,$$

$$I_6 + I_7 - I_5 = 0,$$
$$I_1R_1 + I_2R_2 + I_3R_3 - I_4R_4 = \varepsilon_1 + \varepsilon_2 - \varepsilon_3 - \varepsilon_4,$$
$$-I_4R_4 - I_5R_5 - I_7R_7 = -\varepsilon_4,$$
$$I_7R_7 - I_6R_6 + I_3R_3 = -\varepsilon_3.$$  (6)

Let us once again pay attention to the choice of plus or minus signs when composing equations. Before the drop in direction on the resistor, a plus “plus” is placed if the direction we have chosen for the current in this section coincides with the selected direction of bypass, and a plus “minus” - otherwise. The emf of the source is taken as “plus” if the direction of the current that it could create in the circuit coincides with the direction of bypassing the circuit, and so with the “minus” sign in the opposite case.

The true direction of the currents can be determined only after solving the system of equations: if the resulting value of any current turns out to be positive, then this means that the direction of this current was chosen correctly; if the current turns out to be negative, then its true direction is opposite to the chosen one.

It is not difficult to show that by applying Kirchhoff's rules, it is always possible to obtain exactly as many independent equations as there are unknown currents, that is, to completely and unambiguously solve the problem posed*).

What can a microscope do?

When creating optical instruments that “arm” the eye, the question naturally arises about their maximum capabilities. For a microscope, for example, such a characteristic serves as its notification. From the point of view of geometric optics, similar to the corresponding eyepiece and objective, the microscope can be made as large as possible. However, in reality this is not the case, and the reason for this is the wave nature of light. The idea of ​​rays of light as geometric linear serves.

*) A detailed mathematical proof of this fact is given in the article by O. V. Lyashko in this issue of the journal. (Editor's note)

⟦folio 28⟧

only an approximation, valid as long as the wavelength of light is much smaller than the size of the object under study.

Before talking about the “abilities” of the microsop, let's look at some mechanical tasks. Without being literally analogous, it will still help to understand where the objects of the capabilities of an optical device lie.

Imagine that a certain researcher decided to study the shape of a cold surface. To do this, in particular, he happened to reduce the restored perpendicular to the surface at any point. The researcher approached this problem in a somewhat unusual way - he began throwing urtug balls on the surface, each time measuring the angle between the directions of incidence and reflection of the ball and constructing a bissertis of this angle. Obviously, in this way it is indeed possible to obtain the required set of perpendiculars, but only if the diameter of the ball is much smaller than the distances between nearby “humps” and their radii of curvature (Fig. 1, a). Otherwise (Fig. 1, b) no information about the shape of the surface can be obtained.

Something similar happens when observing an object in a microscope, although there is a significant difference between the light rays and the balls. As we want

Fig. 1.

Fig. 2.

To examine more and more fine details of an object, we change the magnification of the microscope. It turns out that at a magnification of about 2000 times, it is possible to distinguish two points if they are located at a distance of about 0.2 microns from each other, which is about half the wavelength for visible light. Formally, you can add a microscope magnification of up to 5000 and 10,000, however, in this case, points located at distances less than 0.2 microns will remain indistinguishable.

Let's try to figure out why this happens by turning to the wave properties of light. Let's consider a thin lens (which can serve as the object of our microscope). Let the image of some point A be at point B (Fig. 2). Let's take point A', close to point A. From geometric optics it follows that its image will be at some point B', which obviously does not coincide with point B. However, is it always possible to distinguish points B and B' from a distance, that is, to see them exactly as two points?

From the point of view of wave optics, the image in the lens of each point is formed by the totality of all rays passing through the lens. In our example, this means that the image of point A' will not coincide with point B if the transit times of the extreme rays A'MB and A'NB through the lens are different. What does this mean? Here it should be noted that times can be considered different if they differ from each other by at least the period T of oscillations of the light wave. In the problem under consideration, this is the only time scale available to us.

Thus, it is necessary that the condition be satisfied
