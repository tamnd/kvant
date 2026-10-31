---
id: 1976-3-gindikin-volshebnyiy-mir-anri-puankare-90fbb1e1
issue: kvant_1976_3
year: 1976
number: "3"
title: The Magical World of Henri Poincaré
authors:
  - Гиндикин С. Г.
rubric: osnovnye-stati
page_first: 11
page_last: 19
page_labels: 9, 10, 11, 12, 14, 15, 17
tag: UQAT
lang: en
source: kvant_digital
extraction: publisher
content_sha256: e62db19e681704b7e1a11d847759dbaa52fb558a02e78391205da5ad56b72881
prompt_sha256: draft-1
translated_from: content/ru/1976/03/articles/04_gindikin-volshebnyiy-mir-anri-puankare-90fbb1e1.md
source_content_sha256: 5db03f901d55e23b17392e3579b1b2c7322d8cb4e91672cd777b9e3ce07598a1
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦figure⟧

## The Magical World of Henri Poincaré

I described an imaginary world, the inhabitants of which would inevitably come to the creation of Lobachevsky's geometry.

A. Poincare

When the history of Lobachevsky’s geometry is told today, one may get the impression that if the creators of non-Euclidean geometry had proven its consistency, it would have been favorably accepted. However, it was not the lack of this evidence that was most disturbing to critics. People are accustomed to the fact that geometry deals with our real space and that this space is described by Euclidean geometry. It is characteristic that Gauss distinguished geometry from other branches of mathematics, considering it, like mechanics, an experimental science. But at the same time, Gauss, just like Lobachevsky and Bolyai, understood that, firstly, logically harmonious geometric constructions are possible, behind which there is no physical reality - “imaginary” geometries, and, secondly, it is not so indisputable that on an astronomical scale, Euclidian geometry reigns in our world. However, what only a few mathematicians understood was completely inaccessible to non-professionals. They measured the statements of Lobachevsky's geometry against the Euclidean yardstick of their geometric intuition - and received an inexhaustible source of wit. N.G. Chernyshevsky wrote to his sons from exile that the whole of Kazan laughed at Lobachevsky: “What is “curvature of a ray” or “crooked space”? What is geometry without the axiom of parallel lines? He compares this to “squaring boots” and “extracting roots from the tops,” and says that this is as absurd as “writing in Russian without verbs” (here goes to Fet: “rustle, timid breathing, trills of a nightingale,” at which, it turns out, they also “laughed until their sides hurt”).

A new stage in the development of non-Euclidean geometry began when its first models appeared. We now perceive these models as a means to prove the consistency of Lobachevsky's geometry; but they were remarkable not only for this. Even to a favorable eye, Lobachevsky's geometry seemed too sophisticated, out of touch with the rest of mathematics, and the Cayley-Klein model showed that it naturally arises on the high road of projective geometry, very popular at that time! On the other hand, consideration of a model, the basic concepts of which are constructed from images of the familiar Euclidean geometry, made it possible to replace the formal axiomatic presentation of non-Euclidean geometry with a more visual one.

Another model was invented by Henri Poincaré, dealing with purely analytical issues in the theory of functions of a complex variable. He unexpectedly discovered that the transformations appearing in him can be interpreted as displacements in the Lobachevsky plane. This discovery made such a strong impression on him that many years later he recalled how it occurred to him: “without any seemingly previous thought” when he climbed onto the step of an omnibus during an excursion to Coutances. Ten years later, Poincaré made a remarkable addition to his model - he laid a “physical” basis for it. This article is dedicated to the story of the Poincaré model.

### Excursion into physics

Our geometric concepts have physical premises. For example, we perceive light rays as straight lines. A light ray coming towards us continues to appear straight, even if it has been refracted along the way (for example, entering water from air). To dispel this illusion, you need to conduct an experiment, or look at what is happening from the outside.

⟦figure⟧
Fig. 1

Let us have an optically inhomogeneous medium on the upper half-plane ($y\gt0$), in which the speed of light changes according to the law $c(x,y)=y$ (regardless of the direction of the ray). From Fermat's principle it follows that the path of light between two points is the path for which light requires the shortest possible time to travel. In our environment (where $c(x,y)=y$) light between two points will propagate along such curves $L$ (Fig. 1), for which
$$
\dfrac{\sin\alpha(y)}y=k,\tag1
$$
where $\alpha(y)$ is the angle that the tangent drawn to $L$ at the point with ordinate $y$ forms with the vertical; $k$ is a fixed number for all points of the curve $L$. It is clear that condition (1) is satisfied by all circles with centers on the $x$-axis (i.e., perpendicular to this axis); for each such circle $k=\dfrac1r$, where $r$ is its radius. With $k=0$ we get vertical straight lines. It can be shown that there are no other curves satisfying condition (1); There is also a physical explanation for this (for example, this: light propagates from a given point in a given direction along a single path).

Circles perpendicular to the $x$-axis and vertical straight lines (or rather, their parts located in the upper half-plane) will play the main role in our story.

### "Poincaria" and its geometry

The Poincaré world (let's call it in honor of its creator *Poincaria*) is the upper half-plane $\{(x,y){,}~y\gt0\}$ without the boundary $y=0$ (this is important!). The creatures inhabiting Poincaria (*Poincarians*) perceive as “straight” upper semicircles with centers on the $x$ axis (without ends!) and vertical rays (Fig. 2). We will call these lines n-lines. P-lines seem to Poincarians to be infinite (light travels along them for an unlimited time), and the ends of the p-lines, like the entire axis of the $x$-s, are invisible. So, the Poincarians believe that their Poincaria is unlimited in all directions. Let's call the invisible points of the n-line its *points at infinity*; for a ray, we will consider the point $\infty$ (infinity) to be one of its infinitely distant points. P-lines are uniquely determined by a pair of their infinitely distant points (why?); so we will distinguish them and denote them by $L(\alpha,\beta)$, where $\alpha$, $\beta$ are real numbers (one of them can be $\infty$) - the coordinates of infinitely distant points on the $x$ axis.

⟦figure⟧
Fig. 2

Let's try, together with the Poincarians, to construct the geometry of their space. Like us, when living in Euclidean space, some statements seem obvious to Poincarians; they accept them without proof (axioms) and deduce from them more complex statements (theorems). For us, looking at Poincaria from the outside, all these statements will look different than for the Poincarians (for example, semicircles or rays are straight for us!), so we will “translate” the Poincarians’ formulations into our own “prosaic” Euclidean language and prove it in our own way.

For example, Poincarians know that an n-line passes through two different points and, moreover, it is the only one. For us, this means that through two different points of the half-plane there passes a single semicircle perpendicular to the $x$-axis, or a vertical ray (prove it!); see figure 2. Note that the physical explanation of this statement, which consists in the fact that light between two points propagates along a single path, is the same for the Poincarians and for us (however, for geometry this explanation has no evidentiary force). It is not difficult to verify that in Poincaria all the axioms of Euclidean geometry are valid concerning the relative positions of points and lines and the order of points on a line. (To get used to Poincaria, understand n-segments, n-half-planes into which the n-line divides Poincaria so that n-segments connecting points in one n-half-plane do not intersect the boundary n-line, but n-segments connecting points in different n-half-planes do intersect it; draw n-triangles, n-polygons; think about p-convexity, if you know about the “ordinary” convexity, figure 3, *a* and *b* will help you.)

⟦figure⟧
Fig. 3

The difference between Poincaria geometry and Euclidean geometry is revealed when considering the relative position of a pair of n-lines. We already know that two different n-lines can intersect at most at one point. If they do not intersect, then they have a common point at infinity (invisible!) or do not have common points even on the invisible border. In the first case we will call such n-lines *parallels*, and in the second - *superparallels*. If there is an n-line $L(\alpha,\beta$), then through a point outside it there pass only two parallel $L(\alpha,\beta)$ n-lines (corresponding to the infinitely distant points $\alpha$ and $\beta$, respectively; Fig. 4) and an infinite number of superparallel ones lying between the parallels. Thus, in Poincaria the axiom of parallels is unfair (to us, observers, however, this is not very surprising - after all, the Poincarians do not know that their “straight” ones are “not real”!); this allows us to hope that Poincaria's geometry will turn out to be Lobachevsky's geometry.

⟦figure⟧
Fig. 4

The main thing we need to do now is to determine the *distances* and *displacements* in Poincaria.

### Distances and movements

From the point of view of optics, it is most natural to take as the distance between two points $A$ and $B$ in Poincaria the time during which light travels from point $A$ to point $B$: then the n-straight lines will be the shortest lines between the points lying on them. From physical considerations it follows that the distance $\rho(A,B)$ defined in this way has the usual properties of the Euclidean distance:

1. $\rho(A,B)=\rho(B,A)$;
2. if $A$, $B$, $C$ lie on the same n-line and $B\in[AC]$, then $\rho(A,B)+\rho(B,C)=\rho(A,C)$ (light propagates from $A$ to $C$ along the n-line and will pass through the point $B$);
3. for any points $A$, $B$, $C$: $\rho(A,B)+\rho(B,C)=\rho(A,C)$ - *triangle inequality*, and equality occurs only when $B\in[AC]$ (if this inequality were not satisfied, then the light would need less time to travel along the p-broken line $ABC$ than to travel along the n-straight line $AC$ - the fastest way, which cannot be).

For the Poincarians, the introduced distance $\rho$ is primary (note that relative to this distance light travels at unit speed), and they have no reason to express $\rho$ in terms of anything else; It’s natural for us to express $\rho$ through our Euclidean distance. This is not easy: you have to deal with the uneven movement of light, and to calculate the time spent by it, you need to calculate integrals. Therefore, we will give only the final answer:
$$
\rho(A,B)=\ln\dfrac{r'+r}{r'-r},\tag2
$$
where $r$ is the Euclidean distance between points $A$ and $B$, $r'$ is the Euclidean distance between point $A$ and point $B'$, symmetrical to point $B$ relative to the axis $x$; the logarithm is taken to the base $e$ (with a different base of the logarithm we get $\rho$ up to a constant factor). The Euclidean distance is remarkable in that there are many plane transformations that preserve it; Such transformations are called *movements*. Let's see what displacements look like in Poincaria (n-*translations*) - transformations that preserve $\rho$, and therefore transform n-lines into n-lines.

Let's start with transformations that do not leave a single point in place. First of all, these are the usual *parallel translations* along the $x$ axis: $T_a(x,y)=(x+a,y)$. These parallel transfers preserve both the Euclidean distance and the speed of light $c(x,y)=y$, and therefore the time it takes light to travel between two points $A$ and $B$, i.e. n-distance $\rho(A,B)$, and, of course, n-lines are converted into n-lines. On the other hand, *homothy* $F_b(x,y)=(bx,by)$, $b\gt0$, proportionally changing both the Euclidean distance and the speed of light $c(x,y)$, also does not change the time spent by light, i.e. the n-distance $\rho(A,B)$. So, what seems to us to be a homothety (with center on the $x$-s axis), to the Poincarians seems to be displacement. Using the indicated n-movements, you can translate any point to any point. For example, point $(x_0;y_0)$ goes to point $(0;1)$ with n-movement $\left(\dfrac{x-x_0}{y_0},\dfrac y{y_0}\right)$. Regarding the introduced n-displacements - let's call them n-*shifts* - n-straight lines fall into two classes: semicircles can be translated into each other separately, and rays separately (why?).

Let us now explain how, using n-shifts and the properties of the introduced n-distance $\rho$, we can simply obtain formula (2), expressing $\rho$ through Euclidean distances, in the particular case when both points $A$ and $B$ are on the $y$-axis: $A=(0;y_1)$, $B=(0;y_2)$. Let's put $\rho(A,B)=\phi(y_1,y_2)$ and find the form of the function $\phi$. Since $\rho$ is preserved under Euclidean homotheties centered at $O$, then $$
\phi(by_1,by_2)=\phi(y_1,y_2).\tag{*}
$$

In addition, if $C=(0;y_3)$ is the warming point on the axis $y$, then by virtue of what was said above
$$
\phi(y_1,y_2)+\phi(y_2,y_3)=\phi(y_1,y_3).\tag{**}
$$
According to (*)
$$
\phi(y_1,y_2)=\psi{\left(\dfrac{y_1}{y_2}\right)}=\psi(z_1),\quad
\phi(y_2,y_3)=\psi{\left(\dfrac{y_2}{y_3}\right)}=\psi(z_2),\quad
\phi(y_1,y_3)=\psi{\left(\dfrac{y_1}{y_3}\right)}=\psi(z_3).
$$

Taking into account relation (**) and the last three equalities, we obtain
$$
\psi(z_1\cdot z_2)=\psi(z_1)+\psi(z_2),
$$
whence, under the assumption that the function $\psi$ is sufficiently “good” (see the article by A. Lopshitz “Functional Equations”, «Kvant», 1975, No. 1), $\psi(z)=k\ln z$, where $k$ is a constant factor that is calculated directly.

The found n-displacements are still not enough: we do not have transformations with the help of which we could transform n-lines of one type (semicircles) into n-straight lines of another type (rays). To do this, let's add n-*symmetries* relative to n-lines. For rays this is the usual *axial symmetry*, and for semicircles it is inversion. (For example, n-symmetry with respect to the n-line $L(-1,1)$ is an inversion with respect to a circle with center $O=(0;0)$ of radius 1; it takes a point $A$, different from the center $O$, to a point $A'$ lying on the ray OA such that $|OA|\cdot|OA'|=1$). We know that during inversion, circles and straight lines turn into circles or straight lines, and the values ​​of the angles are preserved. In Poincaria language, this means that, for example, with n-symmetry with respect to the n-line $L(-1,1)$, the n-line $L(\alpha,\beta)$ goes into the n-line $L{\left(\dfrac1\alpha,\dfrac1\beta\right)}$. In particular, the n-lines $L(\alpha,0)$, which are semicircles for $\alpha\ne\infty$, are transformed into n-lines $L{\left(\dfrac1\alpha,\infty\right)}$, which are rays. So, n-symmetries take Poincaria into themselves, and n-lines go into n-lines. It is checked separately (we omit this check) that n-symmetries do not change n-distances $\rho$. (However, in Poincaria, any transformation that takes n-lines into n-lines preserves $\rho$ (there are no homotheties here); this is the most important difference between Lobachevsky’s geometry and Euclid’s geometry.)

The n-displacements that can be obtained by combining n-shifts with n-symmetries are already enough to transform any n-line into any n-line; Moreover, any given point of the first n-line can be combined with a given point of the second, and any n-ray with another n-ray (prove it!). This means that these n-movements can combine any n-segments of equal n-length, and we get that such segments are n-congruent. It can be shown that all n-displacements reduce to those described.

⟦figure⟧
Fig. 5

⟦figure⟧
Fig. 6. $\pi-(\alpha+(\beta+\delta)+\gamma)=$$=[\pi-(\alpha+\beta+\nu)]+{}$${}+[\pi-(\mu+\delta+\gamma)]$

With n-translations, the angle transforms into an angle equal to it in the Euclidean sense (since this is true for parallel translations, homotheties, axial symmetries and inversions). Therefore, the concept of congruence of angles in Poincaria does not differ from Euclidean. Taking this circumstance into account, the Poincarians, just like us, will prove two signs of the congruence of triangles: by two sides and the angle between them, and by a side and two angles adjacent to it. The situation is more complicated with the proof of the third criterion for the congruence of triangles - on three sides: after all, our proof of this criterion uses the fact that circles intersect at most two points. Fortunately, it turns out that the n-circles coincide with the Euclidean ones (wholly lying in the upper half-plane), only their n-center does not coincide with the usual one (this is a rather difficult fact), and therefore everything is in order with the sign of congruence on three sides in Poincaria. However, in Poincaria there is another sign of the congruence of triangles: *triangles with pairwise congruent angles are congruent*! (Translate this statement into the language of Euclidean geometry and try to prove it; see figure 5 and Problem 4.) This means that the area of ​​a triangle in Poincaria (like the triangle itself) is determined by the values ​​of its angles $\alpha$, $\beta$ and $\gamma$. In Lobachevsky geometry, the sum of the angles of a triangle is less than $\pi$. The value $\pi-(\alpha+\beta+\gamma)$ is called *triangle defect*. It can be seen that a triangle defect behaves in the same way as an area; more precisely: if a given triangle is cut by a straight line passing through its vertex, then its area will be equal to the sum of the areas of the resulting triangles; the same will be true for the defect of any triangle: it is equal to the sum of the defects of the resulting triangles (Fig. 6). From this we can conclude that the area of ​​the triangle in Lobachevsky geometry is proportional to the defect $\pi-\alpha-\beta-\gamma$.

### Multiple tasks

1. Make sure that all n-lines perpendicular to a fixed n-line are superparallel (Fig. 7).
Show that for a pair of superparallels there is a unique common n-perpendicular (figure 8, *a* and *b*).

⟦figure⟧
Fig. 7

⟦figure⟧
Fig. 8

1. Check that the n-bisectors of the n-triangle intersect at one point - the center of the inscribed n-circle. Think about what can be said about the described n-circle - does it always exist (see figure 9: on this figure n-triangles $A_iBC_i$ are isosceles, with an axis of symmetry $L(0,\infty)$; $i=1$, 2, 3; n-perpendiculars to the sides of these n-triangles are shown in blue, carried out in their n-midpoints)?

⟦figure⟧
Fig. 9

⟦figure⟧
Fig. 10

1. Check that an obtuse (but not acute) n-triangle can have superparallel altitudes (at Fig. 10; the sides of the triangle are shown in blue and its altitudes in red). What can you say about medians?
2. Show that an isosceles n-triangle has equal base angles and the bisector of the vertex angle is the median and altitude. Prove for this case the fourth criterion for the p-congruence of triangles.
3. Let $L(\alpha,\beta)$, $L(\alpha,\beta_1)$, $L(\alpha,\beta_2)$ be three parallel n-lines (Fig. 11). Prove that there is an n-translation that takes $L(\alpha,\beta)$ into itself and $L(\alpha,\beta_1)$ into $L(\alpha,\beta_2)$.

It follows that in Lobachevsky’s geometry it is impossible to determine the distance between parallels.

⟦figure⟧
Fig. 11

⟦figure⟧
Fig. 12

1. If the n-line $L_1$ intersects the n-line $L_0$ or is superparallel to it, then it projects onto $L_0$ as a finite n-interval; if $L_1$ is parallel to $L_0$, then the projection is a n-ray.
2. Let the n-line $L_0$ be perpendicular to $L_1$ and let $A$ be a point on $L_0$ separated from $L_1$ by a distance $x$ (Fig. 12). Let us draw through the point $A$ an n-line $M_x$, parallel to $L_1$, and denote by $\phi(x)$ the value of the angle that the n-line $M_x$ forms with $L_0$. Find $\phi(x)$ and show that $\phi(x)\to\dfrac\pi2$ is at $x\to0$ and $\phi(x)\to0$ is at $x\to\infty$.

The function $\phi(x)$ is called *Lobachevsky function*; this function connects the values ​​of angles and lengths, and since for angles there is an absolute unit of measurement - a full angle, then in Lobachevsky’s geometry there is such an absolute unit of measurement for lengths (it is transferred from angles using the function $\phi$). In Euclidean geometry there is $\phi(x)\equiv\dfrac\pi2$, and therefore there is no similar absolute unit of measurement for length.

### Solids in Poincaria

So far in all our geometric considerations we have been guided only by optical premises. Here it must be emphasized that Poincaré’s geometry turned out to be non-Euclidean not because Poincaré has different laws of optics than ours: we build (*model*) Poincaré in our own world and do not change the laws of physics! The optical illusions of the Poincarians are explained by the optical heterogeneity of their world.

Although, of course, the brightest implementation of a straight line is a light beam, we still do not measure lengths using the time of propagation of light - for this purpose we have a ruler. It's probably worth getting a ruler and a poincarian. Of course, the Poincarians will make a “p-*straight*” ruler; but if a Poincarian moves such a ruler from one place to another, then it will no longer seem “straight” (s-straight) to him. From the Poincarian point of view, when a rigid body moves, its shape changes. How should a Poincarian react to this? It is clear that the concept of a rigid body must somehow be linked with Poincarian geometry, otherwise the Poincarians will have to believe in the existence of supernatural forces. Henri Poincaré came up with an ingenious way out of this seemingly hopeless situation: *he took advantage of the phenomenon of thermal expansion of bodies*.

Let all bodies in Poincaria have the same coefficient of thermal expansion and zero thermal conductivity, and the sizes of the bodies are proportional to the absolute temperature $T$. (Note that under these conditions, Poincarians cannot measure temperature using an ordinary thermometer, since such a measurement involves comparing the expansion of bodies with different coefficients of thermal expansion.) A rigid body is characterized by the fact that when moving in a medium with a constant temperature, the distance $r(A,B)$ (Euclidean) between any two of its points $A$ and $B$ is preserved. But if a body moves from a region with temperature $T_1$ to a region with temperature $T_2$, then the distance between its points will be multiplied by $\dfrac{T_2}{T_1}$, in other words, the ratio $\dfrac{r(A,B)}T$ will remain the same. What will happen if the body immediately finds itself in an area with different temperatures? What value will be maintained under these conditions? Let, for example, a sufficiently large solid body move in a medium where on one side of a certain line $m$ the temperature is $T_1$, and on the other - $T_2$; let $A$ be a point of the body located in a region with temperature $T_1$, and $B$ be a point of the body located in a region with temperature $T_2$. Let's take a broken line with ends at points $A$ and $B$ and vertex $C$ on line $m$. Let us denote $|AC|=r_1$, $|CB|=r_2$ and consider the value $\dfrac{r_1}{T_1}+\dfrac{r_2}{T_2}$. It turns out that when moving in such a temperature environment, the smallest value of the quantity $\dfrac{r_1}{T_1}+\dfrac{r_2}{T_2}$ is preserved, taken along all broken lines with vertices on the straight line $m$ and ends at two given points $A$ and $B$! Next, we can repeat exactly the same reasoning as when applying Fermat’s principle, for example, to the derivation of Snell’s law of refraction, and we will obtain that the desired smallest value will correspond to a broken line for which $\dfrac{\sin\alpha_1}{T_1}=\dfrac{\sin\alpha_2}{T_2}$, where $\alpha_i$ is the angle of the corresponding link of the broken line with the normal to the straight line $m$.

Let now in Poincaria at point $(x;y)$ the absolute temperature $T(x,y)=y$ be constantly maintained. Then, due to the chosen temperature regime, during the movement of solid (in our sense!) bodies, not Euclidean distances, but n-distances will be preserved, and from the point of view of the Poincarians (after all, they do not feel the temperature difference!) the size of a body moving in such a medium is preserved, i.e. it is n-solid. All that remains to be taken care of is that all objects have small heat capacities and move so slowly as to be in thermal equilibrium, and that the change in temperature is imperceptible to the Poincarians. As a result, the Poincarians not only will not see the border of the world, but will never be able to get to it: when approaching the border, the temperature tends to absolute zero, and therefore the sizes of objects will tend to zero, without changing the proportions between objects. Henri Poincaré tried to exclude all possibilities for the Poincarians to learn that their non-Euclidean world was merely constructed in our Euclidean one. But did he foresee everything? If you discover any unexplored Poincarian features, please write to us about it.
