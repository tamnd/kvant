---
id: 1984-5-evolyuta-c5c96d96
issue: kvant_1984_5
year: 1984
number: "5"
title: Evolute
rubric: raznoe
rubric_sub: Разное
page_first: 40
page_last: 41
page_labels: 38-39
tag: VQJR
lang: en
source: kvant_digital
extraction: vision
content_sha256: 46c234023d948ab328909475831883a0c70d350d4c893595024f93d60bc2e0a9
prompt_sha256: draft-1
translated_from: content/ru/1984/05/articles/16_evolyuta-c5c96d96.md
source_content_sha256: ba02461ca080ed6efa0237bc7037f7a0b67c8c8263ef2c09219da208e83ae9ab
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 38⟧

Evolute

Edited by
D. B. FUCSA

Last time (see «Kvant» No. 2, p. 40) you were offered three curves (an ellipse, an “inverted figure eight” and a semi-chibic parabola), for which it was necessary to prove quite often a family of normals (normal is a perpendicular to the tangent at the point of contact). You can see the correct drawings for the first two curves in front of you. In each of these drawings, the normals to the curve are condensed to points on some other curve. This other curve is called the evolute of the original curve*). In the first two cases, the evolute has cusp points (points at which the rolling pin curve changes its direction by 180°). We will try to understand what evolute is and understand the principles of all these phenomena.

To do this, we need one more geometric concept - the center of curvature. Let $c$ be a curve, $n_A$ the normal to it at its fixed point $A$. Let $M$ be a variable point on the curve $c$ and $n_M$ the corresponding normal. Let us denote by $X(A, M)$ the intersection point of the normals $n_A$ and $n_M$. We will now move the point $M$ along the curve $c$, directing it to $A$ (from any side). Then the point $X(A, M)$ will, generally speaking, change; the limiting position of this point when $M$ reaches $A$, if it exists, is called the center of curvature of the curve $c$ at point $A$ and is denoted by $O_A(c)$ (Fig. 1).**)

Let's introduce a few more names. A circle with center $O_A(c)$ passing through $A$ is called collocated with curve $c$ at point $A$, its radius, that is, the distance from point $O_A(c)$ to point $A$, is the radius of curvature of curve $c$ at point $A$, and the reciprocal of radius of curvature, - the curvature of the curve $c$ at point $A$.

The simplest example. Let $c$ be a circle of radius $R$ with center $O$. Then all the normals to $c$ pass through $O$ and therefore, when the point is moved along $c$, the point $X(A, M)$ does not change at all, but occupies a fixed position $O$. Therefore, the limit of this point is $O$, that is, the center of curvature of our circle at any point coincides with the center of the circle. Therefore, the limit of curvature and the curvature of our circle at any point on it correspond to $R$ and $1/R$.

*) The evolute of the ellipse, constructed by a computer, is also shown on the first page of the cover. Note the red moire pattern in the form of a family of hyperbolas of the grandeur of an ellipse. Think about why it worked.

**) It can be shown that if the curve $c$ is “sufficiently smooth” and the point $A$ is not its inflection point, then $O_A(c)$ increases significantly.

⟦folio 39⟧

If $c$ is not a circle, but another curve, then when the point $A$ moves along it, the center of curvature $O_A(c)$ does not stand still, but itself writes out some curve. As we will see, this curve is the evolute. Before this is proved, we will talk a little about the properties of the introduced concepts.

The tangent circle of all circles passing through the point $A$, the observer, is adjacent to the curve $c$. We can say that if the tangent to $c$ at point $A$ serves as a first approximation for curve $c$, then the tangent circle serves as a second approximation for curve $c$ at point $A$. This statement can be given precise meaning in multiple ways, for example, like this. Let points $O'$ and $O''$ lie on $n_A$ on opposite sides of $O_A(c)$, and let $c'$, $c''$ be circles $c$ with centers $O'$, $O''$ passing through point $A$. Then the non-octoral piece of the curve $c$, enclosing the point $A$, is contained between the circles $c'$ and $c''$ (Fig. 2).

Let's finally turn to our family of normals. Let $C$ be a point on the plane. Let us fix the number $\varphi$ and mark on the curve $c$ the set of those points $A$ for which the normal $n_A$ passes from $C$ at a distance less than $\varphi$. This set consists of one or more intervals (Fig. 3). Let us denote by $L(\varphi)$ the sum of their lengths. The separation limit $L(\varphi)/\varphi$ at $\varphi \rightarrow 0$ is called the density of our family of normals at the point $A$. (This definition is consistent with the visual representation of density: the greater the density, the more densely the normals are scaling towards the point $C$.)

Theorem. The density of the family of normals at points of the form $O_A(c)$ is infinite; at other points it is finite.

We will limit ourselves to proving the first part of the theorem. Since the limiting position of the points $X(A, B)$, when $B$ tends to $A$, is $O_A(c)$, for any $\varepsilon > 0$ one can find a $\delta > 0$ such that if the distance from $B$ to $A$ is less than $\delta$, then the distance from $X(A, B)$ to the normal $n_B$ is less than $\varepsilon$. In this case, the distance from point $O_A(c)$ to straight line $n_B$ is less than $\varepsilon(\delta - \varepsilon)$, where $r$ is the radius of curvature at point $A$ (Fig. 4), as a result of which $L(\varepsilon\delta/(r - \varepsilon)) > \delta$ and at $\varphi = \varepsilon\delta/(r - \varepsilon)$, we obtain $L(\varphi)/\varphi > \delta/((\varepsilon\delta/(r - \varepsilon))) = (r - \varepsilon)/\varepsilon$. It remains to note that we can take $\delta < 1$ and then for $\varepsilon \rightarrow 0$

$$\varphi = \frac{\varepsilon\delta}{r - \varepsilon} \rightarrow 0, \frac{L(\varphi)}{\varphi} > \frac{r - \varepsilon}{\varepsilon} \rightarrow \infty,$$

that is, the density is infinite.

This theorem shows that the points of greatest condensation of our family of normals actually constitute an evolute.

In conclusion, we will name one more property of evolutes.

Theorem. The normal $n_A$ is tangent to the evolutes at point $A$.

This theorem, the proof of which we do not provide strictly, is essentially a consequence of the previous theorem: since the family of normals has infinite density at the evolute points, every normal $n_A$ passes very close to the point $O_B(c)$, relatively far from $O_A(c)$, in the sense; that the limiting distance from $O_B(c)$ to $n_A$ to the distance from $O_B(c)$ to $O_A(c)$ tends to 0. And this means that straight line $n_A$ touches the evolutes (Fig. 5).

(The converse can also be proven: if a non-ctor curve touches all normals to the curve $c$, then it is its evolute.)

From the last theorem it is clear that when point $A$ moves along curve $c$, point $O_A(c)$ moves either in the direction from point $A$ or in the direction towards point $A$. We can say that if, as the point $A$ moves along c, the radius of curvature increases, then the point $O_A(c)$ moves in the direction from $A$, and if the radius of curvature decreases, then the point $O_A(c)$ moves in the direction towards $A$ (Fig. 6). What happens at the points where the radius of curvature reaches a maximum or minimum? And at these points the center of curvature changes its direction of movement to the opposite - hence the cusp points on the evolute. For example, the four cusp points of the evolute of the ellipse correspond to two maxima and two minima of the radius of curvature of the ellipse at its four “vertices”—the points of intersection with the axes of symmetry.

We did not have time to discuss the third part of the homework - the evolution of a semi-chibic parabola. All for the better: it will be more appropriate to talk about this next time. In the meantime -
