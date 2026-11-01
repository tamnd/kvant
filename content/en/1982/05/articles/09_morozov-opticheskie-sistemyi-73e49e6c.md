---
id: 1982-5-morozov-opticheskie-sistemyi-73e49e6c
issue: kvant_1982_5
year: 1982
number: "5"
title: Optical systems
authors:
  - Морозов Е.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 37
page_last: 41
page_labels: 35, 36, 37, 39
tag: T0S5
lang: en
source: kvant_digital
extraction: vision
content_sha256: 10b0b9cfd932d0363abcb2f67da32a2c22f67c05f34810efa8aabcc67ae8d8c7
prompt_sha256: draft-1
translated_from: content/ru/1982/05/articles/09_morozov-opticheskie-sistemyi-73e49e6c.md
source_content_sha256: 2001ae46212800fc9dcd389fcf53147c637c0c6d0a33a975f16eb0a99ea25df1
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 35⟧

Entrance workshop

E. Morozov

Optical systems

An optical system is usually called a set of various optical elements: lenses, mirrors, prisms, plane-parallel plates, etc. Their action is based on the simplest laws of geometric optics - the laws of reflection and refraction of light.

The main elements of multihoptic systems are thin lenses and flat mirrors (it is precisely such systems that are discussed in the stats). Let us recall the main results of applying the laws of reflection and refraction of light for them.

For a thin lens the formula is valid

$$\frac{1}{d} + \frac{1}{f} = \frac{1}{F},$$

which allows you to find the distance $f$ from the lens to the image from the known distance $d$ from the object to the lens and the focal length of the lens $F$. To use this formula, you must carefully follow the rules of signs. Thus, it should be borne in mind that the focal length $F$ is always positive for a converging lens and negative for a diverging lens. (This is why the converging lens is also called positive, and the diverging lens - negative.) The distance $d$ is considered positive for the realization of a (real) object or its image, previously obtained using some other optical element and located with

⟦folio 36⟧

At what distance from the second line is the image $S_2$ of the object $S$ located in front of the first line at a distance $d$ from it? What will be the optical system of these two lines if the distance $l$ between them becomes zero?

Obviously, the solution to the problem lies in the sequential application of the lens formula to lenses $\varLambda_1$ and $\varLambda_2$. Let us first note that this formula simply expresses not the corresponding distances, but their reciprocal quantities, therefore it is convenient to operate with them. Otherwise, as experience shows, the cumbersomeness of the calculation often leads to erroneous results.

For the first line the formula gives

$$\frac{1}{f_1} = \frac{1}{F_1} - \frac{1}{d_1} = \frac{1}{F_1} - \frac{1}{d},$$

where $f_1$ is the distance to image $S_1$. This intermediate image represents from the second line at a distance of $d_2 = l - f_1$. Applying the lens formula a second time, we arrive at the desired result:

$$\frac{1}{f_2} = \frac{1}{F_2} - \frac{1}{d_2} = \frac{1}{F_2} - \frac{1}{l - f_1} =$$

$$= \frac{1}{F_2} + \frac{\frac{1}{f_1}}{1 - l \frac{1}{f_1}} = \frac{1}{F_2} + \frac{\frac{1}{F_1} - \frac{1}{d}}{1 - l \left(\frac{1}{F_1} - \frac{1}{d}\right)}.$$

From here, in principle, one can find the distance $f_2$ itself.

If the lenses are folded tightly, that is, $l = 0$, then the resulting expression simplifies:

$$\frac{1}{f_2} = \frac{1}{F_2} + \frac{1}{F_1} - \frac{1}{d}.$$

To find the distance formula for such a system, let's put $d \to \infty$.

$$\frac{1}{f_2} = \frac{1}{F_{\text{системы}}} = \frac{1}{F_1} + \frac{1}{F_2},$$

or

$$D_{\text{системы}} = D_1 + D_2$$

— the optical system of two thin lines folded closely together is equal to the sum of their optical powers. This result can be generalized to the case of a large number of lines.

Problem 2. Filled with a lens with a shape distance $F$ perpendicular to the optical axis lines at a distance $l$ from it there is a flat mirror (Fig. 4). In front of the lens at a distance $d$ there is a precise light source $S$. Determine the position of the image.

⟦folio 37⟧

At what values ​​of d will the image be valid and at what values ​​will it be minimal (distance case l=0)?

Rays from a light source, hitting the lens, are refracted in it, then reflected from the mirror and refracted again by the lens.

After the first refraction by the lens, the rays converge at point $S_1$. We find the size of the segment $f_1$ from the lens formula:

$$\frac{1}{f_1} = \frac{1}{F} - \frac{1}{d_1} = \frac{1}{F} - \frac{1}{d}.$$

The image of point $S_1$ in a plane mirror will be point $S_2$, located at the same distance from the mirror as point $S_1$, but on the other side of it. This distance is $d_2 = f_2 = l - f_1$.

Having reflected from the mirror, the rays again fall on the lens, as if coming from the point $S_2$, located at a distance from the lens

$$d_3 = l + (l - f_1) = 2l - f_1.$$

After the second refraction by the lens, the rays (or their continuation) will converge at a distance $f_3$ from it, and

$$\frac{1}{f_3} = \frac{1}{F} - \frac{1}{d_3} = \frac{1}{F} - \frac{1}{2l - f_1} =$$

$$= \frac{1}{F} - \frac{\frac{1}{f_1}}{2l \frac{1}{f_1} - 1} = \frac{1}{F} - \frac{\frac{1}{F} - \frac{1}{d}}{2l \left(\frac{1}{F} - \frac{1}{d}\right) - 1} =$$

$$= \frac{2l \left(\frac{1}{F} - \frac{1}{d}\right) + \frac{F}{d} - 2}{F \left(2l \left(\frac{1}{F} - \frac{1}{d}\right) - 1\right)}.$$

Hence the required quantity

$$f_3 = \frac{F \left(2l \left(\frac{1}{F} - \frac{1}{d}\right) - 1\right)}{2l \left(\frac{1}{F} - \frac{1}{d}\right) + \frac{F}{d} - 2}.$$

Now let’s analyze when the resulting image will be valid and when it will be minimal. Obviously, the final image is minimal if the point $S_2$ is between the lens and its right focus, that is, $d_3 < F$. Therefore, point $S_1$ must be located to the right of the mirror at a distance $d_2 > l - F$ from it and at a distance $f_1 > 2l - F$ from the lens. Then from the lens formula we get

$$\frac{1}{d} = \frac{1}{F} - \frac{1}{f_1},$$

illy

$$d = \frac{Ff_1}{f_1 - F} < \frac{F(2l - F)}{2(l - F)}$$

— at such distances of the source $S$ from the lens, its image will be minimal.

In particular, when $l = 0$, the image is minimal for values ​​$d < F/2$ and valid for $d > F/2$.

Problem 3. A thick lens is made from a stack with a refractive index $n = 1,5$. The radius of its first convex surface is $R_1 = 20$ cm, the radius of the second surface, which is both convex and convex, is $R_2 = 5$ cm. Find the thickness of the lens if it is known that the lens leaves a parallel beam of light parallel.

Because the lens is thick, the thin lens formula is not applied to it. To solve the problem, we have to use the law of light refraction indefinitely.

Let us consider a parallel beam of rays incident on the first spherical interface between the double optical axis of the lens. After refraction, the rays will converge at a certain point on the optical axis. Let's find the position of this point.

To do this, we select one ray from the beam - ray $AB$, distant from the axis at a distance $h$, and find the point $S$ of its intersection with the axis after refraction (Fig. 5, a). Let's draw the radius $OB$ to the point of incidence of the beam. Then the angle $\alpha$ will be the angle of incidence, and $\beta$ will be the angle of refraction, and, according to the law of refraction,

$$\frac{\sin \alpha}{\sin \beta} = n,$$ or $\sin \beta = \frac{\sin \alpha}{n}$.

From triangle COB

$$\sin \alpha = \frac{h}{R_1},$$ and $\sin \beta = \frac{\sin \alpha}{n} = \frac{h}{nR_1}$.

Note that all optical systems provide clear images of objects only if squinting beams are used. In this case, this means that $h \ll R_1$, so the sines of the angles of incidence and refraction can be replaced by the angles themselves:

$$\alpha = \sin \alpha = \frac{h}{R_1},$$

⟦folio 39⟧

focal line. By moving this line, focusing on more or less distant objects is achieved.

Problem 4. Find the focusing area of ​​a telescope with a focusing line whose focal length is equal to the focal length of the object. Within what limits does the focusing line move? What should be the length of the tube without a focusing line, but with the same focusing area?

When the tube is set to infinity, the focusing line should not interfere with the image produced by the lens in any way; therefore, it must be located where this image is obtained, that is, in the common focal plane of the object and the eyepiece.

The further the focusing line is positioned from this plane, the more the image created by the lens will shift. In extreme cases, the lines can be screwed tightly to the lens. Let us find at what minimum distance $d$ the telescope is focused.

Since two identical lines (the focusing line and the lens) are twisted together, their total focal length will be equal to half the focal length of the object, that is, $F_{06}/2$. The image created by the system of these lines should be received at a distance of $f=F_{06}$. Then from the thin line formula we find $d$:

$$\frac{1}{d} + \frac{1}{F_{06}} = \frac{2}{F_{06}}, \text{ и } d=F_{06}.$$

Thus, the telescope can be focused on objects located from the telescope at distances from $d=F_{06}$ to $d \to \infty$. In this case, the focusing line moves directly from the object to the common focal plane of the object and the eyepiece, that is, to a distance equal to $F_{06}$.

Obviously, a telescope without a focusing line cannot have such large focusing limits, since for this the tube lines must be infinitely large.

Exercises

1. A parallel beam of light is incident on a system of three lenses, the main optical axes of which coincide. Find the position of the intersection point of the rays after passing through the system if the focal lengths of the line are $F_1=+10$ cm, $F_2=-20$ cm and $F_3=+10$ cm, the distance between the first and second lines is $l_1=15$ cm, and the distance between the second and third is $l_2=6$ cm.

2. The flat surface of a plano-convex line with a focal length $F$ is covered with a good reflective layer. At a distance $d$ from the lens on the side of its convex surface there is a point source of light. Determine the position of the image. At what values ​​of $d$ will the image be valid and at what values ​​will it be minimal?

3. A variable focal length lens consists of two identical thin plano-convex lenses, the space between which can be filled with various liquids (Fig. 7). Considering the lens to be a thin line, find the dependence of its focal length $F$ on the refractive index of the liquid $n$ and draw this dependence graphically. The radii of the spherical surfaces of the line are $R=20$ cm, the refractive index of the lens materials is $n_1=1,5$.

4. Why does a crocodile have flat eyes?
