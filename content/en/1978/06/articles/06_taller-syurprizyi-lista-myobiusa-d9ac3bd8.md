---
id: 1978-6-taller-syurprizyi-lista-myobiusa-d9ac3bd8
issue: kvant_1978_6
year: 1978
number: "6"
title: Surprises of the Mobius strip
authors:
  - Таллер А.
rubric: osnovnye-stati
page_first: 30
page_last: 33
page_labels: 28-31
tag: 6AR7
lang: en
source: kvant_digital
extraction: vision
content_sha256: 14fa79bddfe3be21febfdd9e4a5619df0e053b2b7b40a647d23e5450eca22f15
prompt_sha256: draft-1
translated_from: content/ru/1978/06/articles/06_taller-syurprizyi-lista-myobiusa-d9ac3bd8.md
source_content_sha256: 1334c2851b50ce90ec55f4ec929596e23029a5ae0f5cf8d7e09361e516535451
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 28⟧

A. Thaler

Suorpiza
Mobinus strip

Let's imagine a surface and an ant sitting on it. Did the ants reach the rim side of the surface - figuratively speaking, to its underside - without overflowing the edges? Of course not! Mathematicians were convinced of this until the middle of the century, when the German astronomer and geometer August Mobinus gave the first example of a one-sided surface, to any place of which an ant could crawl without lying over the edges. We will talk about this surface, called the Möbinus strip (or strip).

Before reading further, make a model of a Mobinus strip: take a paper strip the length of a narrow rectangle ABCD (Fig. 1); twist it 180°, glue a ring out of it - the Möbinus strip is ready. Try covering one side of it, leaving the other white. You will soon discover with judgment that the dye is “inside out.” Thus, the Möbinus strip is truly a one-sided surface.

The Möbinus strip will overcome more than one speed even if you try to cut it:

1) Cut your Mobinus strip along the center line. At the last cut (Fig. 2), the piece, instead of falling apart into two pieces, unfolds into a long connected closed strip.

2) Cut the tape obtained after the first cut again along its center line. Before the last downfall, try to guess what will happen?

3) Take another very narrow strip of paper, this time twist it not 180°, but 360° and glue it together.

Fig. 1.

⟦folio 29⟧

those; then cut it along the center line. Compare the result with the result of the previous cut.

Why is this happening? Without resorting to paper models and scissors, let's try to figure it out mathematically.

Möbnus surface equation

Let us construct Möbnus surfaces in the three-dimensional Cartesian coordinate system $Oxyz$. Consider on the plane $z = 0$ a circle of radius $R$ with center at the origin $O\left(x^2 + y^2 = R^2\right)$. Let the point $A$ move uniformly in the positive direction along this circle; then the plane $\alpha$, passing through the axis $Oz$ and the point $A$, will rotate with it uniformly around the axis $Oz$. Let us consider in the plane $\alpha$ the line $l$ passing through the point $A$. Let the straight line $l$ rotate around the point $A$ counterclockwise (if you look at $\alpha$ in the direction of movement of the point $A$), and at any moment the angle between the ray $OA$ and the straight line $l$ is equal to half the angle $\varphi$ between the axis $Ox$ and the ray $OA$. Thus, when point $A$ completes a full revolution, straight line $l$ appears on the surface relative to the initial position at $180^\circ$.

The set of points in space through which the straight line $l$ passes (participating in two motions) are Möbnus surfaces (Fig. 3). At-
Fig. 2.

Fig. 3.

⟦folio 30⟧

$$\begin{cases} x = \left( R + \lambda \cos \frac{\varphi}{2} \right) \cos \varphi, \\ y = \left( R + \lambda \cos \frac{\varphi}{2} \right) \sin \varphi, \\ z = \lambda \sin \frac{\varphi}{2}, \end{cases}$$

where $0 \leq \varphi < 2\pi, \lambda \in \mathbb{R}^*$).

A general view of the Möbius surface is depicted on the cover of the magazine. Fig. 4 shows the part of the surface corresponding to $-1 \leq \lambda \leq 1$; We depicted this part of the surface with a paper model.

If, when going around the circle, we rotate our straight line at twice the speed, then at $-1 \leq \lambda \leq 1$ we will get a strip twisted by $360^\circ$ (remember cut 3)). This is already a two-sided surface (Fig. 5). Her equation will obviously be

$$\begin{cases} x = \left( R + \lambda \cos \varphi \right) \cos \varphi, \\ y = \left( R + \lambda \cos \varphi \right) \sin \varphi, \\ z = \lambda \sin \varphi. \end{cases}$$

Let us now note that at $\varphi = 0$ the generator $l$ also intersects the original circle at the point $(-R, 0, 0)$. Therefore, it does not intersect

*) This type of surface definition is often called parametric; here the parameters $\varphi$ and $\lambda$ are used exclusively by the surface (similar to latitude and longitude on the earth's surface).

Linear self-intersection

To find the self-intersection line of the Möbius surface, we find out which pairs of generators can intersect.

If two generators lie in different vertical planes, then the point of their intersection, if it exists, must lie on the line of intersection of these planes, i.e., on the $Oz$ axis.

For each $\varphi \in [0; 2\pi]$ we find the point of intersection of the generatrix with the axis $Oz$. For this point

$$x = \left( R + \lambda \cos \frac{\varphi}{2} \right) \cos \varphi = 0,$$

$$y = \left( R + \lambda \cos \frac{\varphi}{2} \right) \sin \varphi = 0.$$

Since $\sin \varphi$ and $\cos \varphi$ cannot be 0 at the same time, $R + \lambda \cos \frac{\varphi}{2} = 0$. At $\varphi \neq \pi$, $\lambda = -\frac{R}{\cos \frac{\varphi}{2}}$. From (1) $z = -R \mathrm{tg} \frac{\varphi}{2}$.

Thus, the coordinates of the point of intersection of the generatrix with the axis $Oz$:

$$\left( 0, 0, -R \mathrm{tg} \frac{\varphi}{2} \right).$$

Existence for us is the fact that all generators at $\varphi \neq \pi$

⟦folio 31⟧

intersect the $Oz$ axis at various points. At $\varphi = \pi$ they are formed parallel to the $Oz$ axis.

Thus, only pairs of generatrixes that lie in the same vertical plane can intersect; in other words, if one of the intersecting generators corresponds to the angle $\varphi$, then the other corresponds to the angle $\varphi + \pi$. Let the position of the intersection point of these images be determined by the value $\lambda_1, \lambda_2$ of the parameter $\lambda$. Then from (1)

$$\begin{cases}
x = \left(R + \lambda_1 \cos \frac{\varphi}{2}\right) \cos \varphi \\
= -\left(R - \lambda_2 \sin \frac{\varphi}{2}\right) \cos \varphi \\
y' = \left(R + \lambda_1 \cos \frac{\varphi}{2}\right) \sin \varphi \\
= -\left(R - \lambda_2 \sin \frac{\varphi}{2}\right) \sin \varphi \\
z = \lambda_1 \sin \frac{\varphi}{2} = \lambda_2 \cos \frac{\varphi}{2}.
\end{cases}$$

From these expressions it follows that $\lambda_1, \lambda_2$ satisfy the system of equations

$$\begin{cases}
R + \lambda_1 \cos \frac{\varphi}{2} = -R + \lambda_2 \sin \frac{\varphi}{2}, \\
\lambda_1 \sin \frac{\varphi}{2} = \lambda_2 \cos \frac{\varphi}{2},
\end{cases}$$

where ($\text{при } \varphi \neq \frac{\pi}{2}, \frac{3\pi}{2}$) is $\lambda_1 = -2R \frac{\cos \frac{\varphi}{2}}{\cos \varphi}$. Substituting the found value $\lambda_1$ into equations (1), we obtain the coordinates of the self-intersection point:

$$x = -R, \ y = -R \text{tg} \varphi, \ z = -R \text{tg} \varphi.$$

From this we can see that as $\varphi$ changes, the self-intersection point of the Möbius surface moves along a straight line that lies in the $x = -R$ plane and is described by the equation $z = y$. Thus, the line of self-intersection is straight (but not generative!). A segment of this straight line is depicted on the cover. Having carefully studied the screensaver, you will find a self-intersection line on it.

Fig. 6.

Why doesn't the Möbius strip disintegrate when cut?

Now it is not difficult to answer this question. Unwind on figure 4 (and on the cover) the edge of the Möbius strip, i.e. line $\lambda = \pm 1$. Take a closer look: this edge does not break up into a pair of closed curves, as would be the case for an untwisted plane, but represents one continuous curve. Our cut did not touch the edge, and therefore the edge (and therefore the entire strip) will remain a whole piece after the cut.

How to explain other sioprizzes?

We can assume that the second cut is made along the line $\lambda = \frac{1}{2}$ (Fig. 6).

The coordinates of a point on this line are described (at $\varphi \in [0, 2\pi]$) by the equations

$$\begin{cases}
x = \left(R + \frac{1}{2} \cos \frac{\varphi}{2}\right) \cos \varphi \\
y = \left(R + \frac{1}{2} \cos \frac{\varphi}{2}\right) \sin \varphi \\
z = \frac{1}{2} \sin \frac{\varphi}{2}.
\end{cases}$$

Obviously, the cut divides our plane into two parts, which can be conditionally called external and internal, and the internal part is the same, only narrower, strip of a Möbius strip. What is the outer part?

(Continued on page 59)
