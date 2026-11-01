---
id: 1981-5-eritspohov-postroenie-izobrazheniy-naklonnyih-predmetov-20866aea
issue: kvant_1981_5
year: 1981
number: "5"
title: Constructing images of inclined objects
authors:
  - Ерицпохов Б. Ф.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 39
page_last: 42
page_labels: 37-40
tag: O98F
lang: en
source: kvant_digital
extraction: vision
content_sha256: 13b460e8128bb6b965e7dade1084a94b337e6f0b64d4e50ff6137d7c8fac46c0
prompt_sha256: draft-1
translated_from: content/ru/1981/05/articles/13_eritspohov-postroenie-izobrazheniy-naklonnyih-predmetov-20866aea.md
source_content_sha256: 449b636447ea0781b4fcff68ce134c142b04706949995d3077b6ea355f2173a9
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 37⟧

Constructing images of inclined objects

To find the image of a luminous point in an optical system, for example in a lens or a mirror, it is enough to construct the path of two rays emanating from the point. Typically, two of the three characteristic rays are selected, the path of which after the system is known. These are the ray passing through the optical center of the system, the ray incident on the system parallel to its optical axis, and the ray passing through the front focus of the system.

But what if the light source is not precise, but extended? You can, of course, construct images of individual points, but sometimes it is possible not to use simplifications. So, if an object is perpendicular to the main optical axis, the image is also perpendicular to it. What if the object is inclined to the axis at an arbitrary angle? Let's take a closer look at this case.

Let the object $AB$ rest on the axis at point $A$ and make an angle $\alpha$ with the axis. Let's construct an image $A'B'$ of this object in an optical system, for example, in a collecting lens (Fig. 1). Intuitively, it can be suggested that the image will be located symmetrically to the object relative to the axis. However, this is not true. Let us find the dependence of angle $\beta$ on angle $\alpha$.

Let's direct the coordinate axes $XOY$ in the space of objects and $X'OY'$ in the space of images corresponding to the rule of signs adopted in the school textbook. In this case, the coordinate $x$ corresponds to the distance $d$ from the object to the lens, and the coordinate $x'$ to the distance $f$ from the lens to the image.

Angles $\alpha$ and $\beta$ will be determined by their tangents $^*$). From figure 1

$$tg\alpha = \frac{y}{d - d_0}, \quad tg\beta = -\frac{y'}{f_0 - f} = \frac{y'}{f - f_0},$$

$$\frac{y'}{y} = \frac{f}{d}.$$

From the lens formula $\frac{1}{d} + \frac{1}{f} = \frac{1}{F}$ and $\frac{1}{d_0} + \frac{1}{f_0} = \frac{1}{F}$ we express $f$ and $f_0$:

$$f = \frac{Fd}{d - F}, \quad f_0 = \frac{Fd_0}{d_0 - F}.$$

We'll finally get it

$$tg\beta = tg\alpha \left(1 - \frac{d_0}{F}\right).$$

* In this case, the angle $\alpha$ is absent in the direction of rotation from the axis $OX$ to the axis $OY$, and the angle $\beta$ is absent from the axis $OX'$ to the axis $OY'$.

⟦folio 38⟧

figure 2 shows a more general case when the object $AB$ and its image $A'B'$ do not touch the optical axis. Consider this case yourself and obtain a more general formula for the tangent of angle $\beta$:

$$\text{tg} \beta = \frac{y_1(d_2 - F) - y_2(d_1 - F)}{F(d_2 - d_1)}$$

Let's assume that the light source is a luminous line (Fig. 3). The equation of this line has the form $y = kx + b$, where $b = -kd_0$ and $x = d$. Let's find the function $y'$ in image space:

$$y' = y \frac{f}{d} = y \frac{f - F}{F} = k \left( \frac{fF}{f - F} - d_0 \right) \frac{f - F}{F} = k \left( 1 - \frac{d_0}{F} \right) f + kd_0,$$

or

$$y' = k'x' + b'$$

where $k' = k \left( 1 - \frac{d_0}{F} \right)$ and $b' = kd_0$.

Obviously this is an equation of a straight line; therefore, the image of a straight line is also a straight line. Coefficients $k$ and $k'$ are the tangents of angles $\alpha$ and $\beta$ respectively:

$$k = \text{tg} \alpha, \ k' = \text{tg} \beta.$$

Thus, the connection between the tangents of angles $\alpha$ and $\beta$ is once again derived.

Note that in geometric optics only parascal rays are considered, that is, very close to the main optical axis. However, from the visualization messages in all the figures (previous and subsequent), the angles $\alpha$ are shown to be quite large.

Let's now move on to specific examples. Let's agree that in all the figures the luminous line has the form $y = kx + b$, where $b = -kd_0$ and $x = d$. Let's find the function $y'$ in image space:

$$y' = y \frac{f}{d} = y \frac{f - F}{F} = k \left( \frac{fF}{f - F} - d_0 \right) \frac{f - F}{F} = k \left( 1 - \frac{d_0}{F} \right) f + kd_0,$$

or

$$y' = k'x' + b'$$

where $k' = k \left( 1 - \frac{d_0}{F} \right)$ and $b' = kd_0$.

Example 1. Let the luminous straight line intersect the optical axis of the collecting line at the point with coordinate $d_0 = 2F$ (Fig. 4). Then

$$k' = k \left( 1 - \frac{d_0}{F} \right) = k \left( 1 - \frac{2F}{F} \right) = -k,$$

or

$$\text{tg} \beta = k' = -k = -\text{tg} \alpha.$$

Example 2. Let $d_0 = 0$. Then

$$k' = k \left( 1 - \frac{d_0}{F} \right) = k.$$

The corresponding luminous line and its image in the collecting line are shown in figure 5.

Example 3. Find the image of a straight line in a wavy spherical mirror if $d_0 = F/2$ (Fig. 6).

Note that in the case of a wavy mirror, the $OX'$ axis in image space is directed in the same direction as the $OX$ axis in object space.

⟦folio 39⟧

Fig. 4.

Example 4. Let us construct an image of a straight line in a diverging lens and in a convex mirror, provided that $d_0 = F$.

For scattering systems, the lens formula has the form

$$\frac{1}{d} + \frac{1}{f} = -\frac{1}{F},$$

that's why

$$k' = k \left( 1 + \frac{d_0}{F} \right).$$

In our case

$$k' = k \left( 1 + \frac{d_0}{F} \right) = 2k.$$

Fig. 5.

Fig. 6.

Since all the formulas for a concave mirror are the same as for a converging lens, we get

$$k' = k \left( 1 - \frac{d_0}{F} \right) = \frac{k}{2}.$$

The correspondence of the construction for a diverging lens and a convex mirror is shown in Figures 7 and 8.

Example 5. Let a luminous line pass through a point with coordinate $d_0 = F$. What will her image be?

⟦folio 40⟧

fermentation in a collecting system (collecting lens or wavy mirror)?
If $d_0 = F$, then
$$k' = k \left( 1 - \frac{d_0}{F} \right) = 0.$$
This means that the image of an inclined line will be a straight line parallel to the main optical axis of the system. At figure 9 the construction for a converging lens was carried out.
Example 6. Let us find out at what position of the straight line its image in the scattering system will be parallel to the optical axis of the system.
Since for the dispersing system
$$k' = k \left( 1 + \frac{d_0}{F} \right),$$
then $k'$ will be equal to zero at $d_0 = -F$. The corresponding constructions for a convex mirror are shown in figure 10.

Let's look at the last two examples in a little more detail.
First, from figure 9 and 10 it follows that $y' = F \mathrm{tg} \alpha$. This means that the greater the angle of inclination of the luminous straight line to the optical axis of the system, the farther the image line is from the axis.
Secondly, we note that with a uniform distribution of linny points of an object on the linny image, the distribution points are uneven (see, for example, Fig. 10). This is due to the so-called longitudinal magnification (magnification in the direction of the optical axis), which is determined by the formula
$$\Gamma_{\text{прод}} = \lim_{d_2 \to 0} \frac{f_2 - f_1}{d_2 - d_1}.$$
In other words, the longitudinal increase is equal to an arbitrary one from $f$ to $d$:
$$f' = \left( \frac{Fd}{d-F} \right)' = -\left( \frac{F}{d-F} \right)^2 = -\Gamma_{\text{попер}}^2$$
