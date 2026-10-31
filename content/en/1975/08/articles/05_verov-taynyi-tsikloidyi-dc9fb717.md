---
id: 1975-8-verov-taynyi-tsikloidyi-dc9fb717
issue: kvant_1975_8
year: 1975
number: "8"
title: Secrets of the Cycloid
authors:
  - Веров С. Г.
rubric: osnovnye-stati
page_first: 21
page_last: 29
page_labels: 19-27
tag: V3GL
lang: en
source: kvant_digital
extraction: vision
content_sha256: c11b09966b7f3ff1e46caaadcd503dbab0b2242aca12399c8b4165210a41e82e
prompt_sha256: draft-1
translated_from: content/ru/1975/08/articles/05_verov-taynyi-tsikloidyi-dc9fb717.md
source_content_sha256: 72b1fe8b0dbb63ba00da9e95b38e4a06540cab14d99274e7002f2be1973320a2
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 19⟧

## Secrets of the Cycloid
S. G. Verov

⟦figure⟧

*“The roulette is a line so common that after the straight line and the circle there is no more frequently occurring line; it is so often drawn before the eyes of everyone that one must be surprised that the ancients did not consider it ... for it is nothing other than the path described in the air by the nail of a wheel when it rolls with its own movement from the moment the nail began to rise from the ground until the continuous rolling of the wheel brings it back to the ground after the end of a whole revolution.

Pascal

The curve, “so often drawn before everyone’s eyes,” was first noticed by Galileo (in Italy) and Mersenne (in France). In Italy it was called *cycloid*, in France - *roulette*. The first name stuck, and curves of a wider class are now called roulettes (see the article “Tangents to roulettes”, «Kvant», 1975, No. 5, p. 22; in the future, referring to this article, we will write KR). The mathematicians of the 17th century, who created general methods for studying curves, were very interested in new “experimental” curves. Among these curves, the cycloid occupies a special place. It turned out to be one of the first *transcendental* curves (curves of non-algebraic origin) for which it was possible to find a beautiful explicit answer in problems about constructing tangents and calculating area. But what was most striking was that the cycloid appeared again and again in solving a variety of problems, primarily

2*

⟦column⟧

the initial production of which she did not participate. All this made the cycloid the most popular curve of the 17th century: in 1673, Huygens stated that “the cycloid has been studied more accurately and thoroughly than all other curves.”

### 1. From kinematic definition to analytical

The kinematic definition of a cycloid is contained in the epigraph to this article. Let's try to decipher it.

Let us choose a coordinate system on the plane so that the straight line along which the circle rolls (*directing* straight line) coincides with the $Ox$ axis, and let the circle (it is called the *generating* circle) roll in the positive direction of the $Ox$ axis. Let us assume that at the initial moment of time the observed point of the circle boundary occupies position $A_0=O=(0,0)$ (Fig. 1). If $r$ is the radius of the generating circle, then its center will move along the straight line $y=r$. To fully characterize the rolling of a circle, it is enough to describe the movement of its center, if only to add that *the circle rolls without slipping* *). It is convenient for us, having fixed the unit of time, to assume that the center of the circle moves uniformly with a speed of $r$. At time $t$

---

*) This is probably what Pascal had in mind when he wrote that the wheel “rolls by its own motion.”

⟦folio 20⟧

the center of the circle is at point $C_t = (tr, r)$, and the generating circle will touch the directing line at point $B_t = (tr, 0)$.

Let us now find the position of $A_t$ at the nearest point at time $t$ (by definition, $A_t$ will be a point of the cyclonde). To do this, you need to clearly formulate in the word and e that the rolling of the circle will occur without sliding: it consists in the fact that the length of the segment between the points of contact of the generating circle with the directing line at the moment of time 0 and $t$ (segment $OB_t$; see Fig. 1) is equal to the length of the other $B_tA_t$, “rolled” along this segment (in this case, the arc can exceed a full circle).

Therefore, at time $t$, the angle $B_tC_tA_t$ is equal to $t$ (in radian measure), since the length of the other $B_tA_t$ is equal to $tr$. Denoting through $D_t$ the projection of the point $A_t$ onto a straight line passing through the center of the circle $C_t$ parallel to the axis $Ox$, and through $E_t$ the projection of the point $A_t$ onto a straight line passing through the center $C_t$ parallel to the axis $Oy$ (Fig. 2), we obtain (taking into account the direction of the coordinate axes)

$$C_tD_t = -r\sin t, \quad C_tE_t = -r\cos t$$

(see what happens in case $t > \frac{\pi}{2}, t > \pi$). Therefore, the coordinates of the point $A_t$ of the cyclonde are respectively

$$x = rt - r\sin t, \quad y = r - r\cos t$$

Note that at $t = 2\pi$ the length of the segment $OB_t$ turns out to be equal to the length of the circle, the observed point again falls on the axis $Ox$ ($A_{2\pi} = (2\pi, 0)$) and the pattern begins to repeat. Thus, the period of the cyclonde is $2\pi r$.

So, a cyclonde can be defined as a set of points with coordinates $(rt - r\sin t, r - r\cos t)$ and, if desired, the original kinematic definition can be forgotten. We have obtained the so-called *parametric* definition of the cyclonde: both coordinates $x$ and $y$ of the point $A_t$ of the cyclonde are functions of some auxiliary variable $t$.

Let us call the points of the cyclonde lying on the axis $Ox$ the points of the cyclonde, the points lying on the straight line $y = 2r - \text{вершинами}$, and the other neighboring points - the arches of the cyclonde. In the chosen coordinate system, the cyclone is characterized by one parameter $r$ (the radius of the generating circle). All cyclondes whose points $(0, 0)$ are points receive a ready-made solution from each other. For each point $(x, y)$, $x \neq 0$ one can uniquely choose $r$ so that this point will lie on the first arch emerging from $(0, 0)$, the corresponding cyclonde (prove).

In the KR article it is proved that the tangent to the cyclonde at the point $A_t$ (Fig. 3) passes through the top point of the generating circle - point $F$ at Fig. 1.

⟦folio 21⟧

Figure 3. Let $B_t$ be the bottom point of the circle, $\alpha$ the angle between the tangent and the vertical $FB_t$. Then $A_t B_t$ is the normal to the cyclone (perpendicular to the tangent), and for the ordinate $y$ of the point $A_t$ we have: $y = E_t B_t = 2 r \sin^2 \alpha$. From here

$$\sin \alpha = \sqrt{\frac{y}{2r}}.$$

This correspondence will play an important role in the future. It can be shown that the cyclone with parameter $r$ is the only curve passing through the point $(0, 0)$ that satisfies correspondence (1).

2. On the areas of curvilinear figures

People were able to calculate the areas of some curvilinear figures back in Ancient Greece. At first, they were only interested in the quadrature of figures, that is, in constructing for a given figure a cyclulum and a linear segment whose length is equal to its area. As we found out later, this can be done for those figures whose area is calculated using arithmetic operations and the operation of extracting the square root. Gradually, people began to become interested in figures whose area was calculated using arbitrary algebraic operations (algebraic quadrature), and then even in figures whose expressions for areas included the number $n$. The main method of calculating areas is to approximate a given figure with polygons and go to the limit; but one must be very lucky to bring these calculations to an explicit answer.

Sometimes the calculation of the area of ​​figures can be simplified by using some general properties of areas. Here are a few such properties.

1. In this case, when a figure is divided with a coefficient of $k$, its area is multiplied by $k^2$, and when the figure is dissected relative to a certain axis with a coefficient of $k$, its area is multiplied by $k$.

2. Equidistant figures (i.e. figures that can be cut into pairs of congruent parts) are equal in size (they have areas).

3. Two figures, the intersection of which by any line parallel to some fixed line $l$, yield congruent segments of equal size (this principle was formulated in 1635 by Cavalieri (1598-1647)).

Let's imagine that the contour of the figure is a flexible tape, and the figure itself is composed of very thin rigid layers parallel to the straight line $l$ (“indivisible”, in Cavalieri’s terminology). Let's consider transformations that preserve these layers, but separate them from each other. By virtue of Cavalieri's principle, all the figures receiving during such transformations will be equal in size.

The listed properties of areas are needed in proofs (the main difficulty of these proofs is to give a strict definition of area), but they are easy to verify. Now we will talk about how elegantly these properties are used when calculating the area of ​​​​a figure lying under the arch of a cyclonde.

⟦folio 22⟧

3. The cyclone's companion, Roberval's petals and the area under the cyclone

Since the cyclondes are similar, we restrict ourselves to the case $r=1$. Following Roberval (1602-1675), the connection with each point of the cyclonde $A_t$ (see Fig. 3) ​​is its projection $E_t$ on the vertical diameter of the generating circle. Point $E_t$ has coordinates $x=t, y=1-\cos t=1+\sin\left(t-\frac{\pi}{2}\right)$.

Roberval called the curve composed of points $E_t$ for all possible $t$ “the companion of the cyclonde.” It is clear that the “companion of the cyclonde” is an inverted sinusoid (1 up and $\frac{\pi}{2}$ to the right).

The historical course is connected with this circumstance. Mathematicians have been studying trigonometric functions since time immemorial, but sinusoids first appeared only in the 17th century, and not as a graph with a sine wave, but as ... “with a cyclond path” (this can be partly explained by the fact that for a long time they did not consider functions of non-algebraic origin).

“The Companion of the Cyclonde” breaks it into three parts (Fig. 4): a figure under a sine wave and two symmetrical figures called “Roberval petals”. By virtue of property 2, the area of ​​the figure under the sinusoid is equal to $2\pi$: this figure is equivalent to a rectangle of such area (Fig. 5). One “petal” apart. The horizontal line at height $y=1-\cos t$ intersects it along a segment $A_t E_t$ of length $|\sin t|$ (see Fig. 2). By moving these horizontal segments (for all possible $t$) along their horizontals so that their left ends fall on the same vertical, we obtain a semicircle of the unit circle (Fig. 6). By virtue of Cavalieri's principle, the area of ​​the “petal” is equal to the area of ​​this semicircle, i.e. $\frac{\pi}{2}$. This means that the area of ​​the figure under the arch of the cyclonde with $r=1$ is equal to $2\pi+2 \cdot \frac{\pi}{2}=3\pi$ (and therefore $3\pi r^2$ at $r\neq 1$).

The question of calculating the areas of the cyclonde segments is less elementary. Huygens (1629-1695) wrote, not without pride: “I was the first to measure the area of ​​the point of a cyclonde, which will be obtained if part of the axis $1/4$ is removed from the top and parallel to the base is drawn. This part constitutes half of an area hexagon inscribed in the forming circle.”

⟦folio 23⟧

4. Tautochrone

“The cyclopadic mathematical matrix was invented by Christan Huyens, a major scientist of the 17th century and the general watchmaker of all times.”
Sommerfeld. Mechanics

Galileo argued that the period of oscillation of a mathematical matrix is ​​determined only by its length $l$ and does not depend on the angle $\varphi$ of its maximum size. Huygens, having found out that this statement is true only for small angles $\varphi$, decided to construct a matrix whose oscillation period would indeed not depend on $\varphi$ (such a matrix is ​​called *maymochronous or isochronous*).

Huygens divided the construction of the tautochronic matrix into two stages:

1) finding the curve along which the end of the matrix should move (*maymochrones*);
2) finding a matrix suspension that ensures the movement of its end along the tautochrone.

We will start with the Japanese tautochrone (the existence of which is not very convenient in advance).

The end of the mathematical matrix moves along an arc of a circle in exactly the same way as a heavy matrix point - along a groove, the contour of which coincides with this circle. If we neglect friction and air resistance, then a heavy point, thrown in a circle around the groove without an initial speed from a height of $H$, having passed the lower position, again rises to a height of $H$, and then will perform periodic oscillations, rising first in one direction, then in the other direction to a height $H$. Galileo's incorrect statement is that the period of oscillation $T(H)$ does not depend on $H$. Our task is to determine what shape the trench must be for what Galileo claimed to be true.

Thanks to a lucky coincidence (they play an important role in the history of science), Huygens studied the cycle (in connection with the Pascal competition, 1658) at the same time when he was looking for a tautochronic matrix. It was the cyclone that turned out to be a tautochrone! Probably, Huygens himself did not expect this in advance (this is how you can understand his words: “I discovered the readiness of it (cyclones) for measuring time by studying its structure rules of science without suspecting its application").

Let us consider a heavy matrix point on a trough made in the shape of an inverted cyclone (Fig. 7; $r$ is the radius of the generating circle); let at the initial moment of time it be at height $H$ (at point $C_0$ on figure). Let's try to find the time $t$ after which it reaches the bottom point $B$ (the top of the cyclone). Then after $2\tau$ it will be at point $C_{2\tau}$ cyclones, symmetrical to the relative vertical axis of point $C_0$, and after time $T=4\tau$ (full period) it will return to point $C_0$. We are not interested in the dependence of $t$ on $H$.

Let at time $t$the hard point occupy position $C_t$ at height $h=h(t)$. The velocity vector $\vec{v}(t)$ at time $t$ is directed tangentially to the cyclone at point $C_t$, its length $|\vec{v}(t)|$ (velocity value) is determined from the law of conservation of energy:

$$\frac{m|\vec{v}(t)|^2}{2} = mg(H-h(t)),$$

i.e.

$$|\vec{v}(t)| = \sqrt{2g(H-h(t))}.$$

Let's see how the projection moves to the center and our point to the vertical $C_0B'$. At time $t$ this projection occupies position $C'_t$, and at time $t$ it finds itself at point $B'$ (see Fig. 7), having passed the segment $C_0B'$ of length $H$. The speed $\omega(t)$ at time $t$ of this linear motion (at point $C'_t$ on Fig. 7) is the projection of the speed vector $\vec{v}(t)$ onto

⟦folio 24⟧

vertical: $w(t) = |v(t)| \cos \alpha$, where $\alpha$ is the angle between the tangent to the cyclude and the vertical. Since (see (1), p. 21) $\cos \alpha = \sqrt{\frac{2r-y}{2r}}$ and $y = 2r - h(t)$, then $\cos \alpha = \sqrt{\frac{h(t)}{2r}}$, and therefore $w(t) = \sqrt{\frac{g}{r}} \cdot \sqrt{h(t)(H-h(t))}$.

So, the law of change in speed for our rectilinear motion is quite complex. But Huygens noticed (a decisive proof!) that with uniform rotational motion along a circle of diameter $H$, the vertical component of the velocity vector has the same form as $w(t)$. Indeed, let us construct a semicircle on the segment $C_0B'$ as a diameter, and let $C'_t$ be the point of this semicircle lying at the height $h(t)$. The length of the segment $C'_t C'_t$ is equal to $\sqrt{h(t) \cdot (H-h(t))}$.

From the similarity of right-angled triangles colored red at Fig. 7 (their sides are mutually perpendicular: $OC'_t$ is the radius, at point $C'_t$ the tangent to the semicircle and the vertical are drawn), it follows that the tangent to the circle at point $C'_t$ the vector of length $\sqrt{\frac{g}{r}} \frac{H}{2}$ has a vertical projection of length $w(t)$. This means that when our point $C$ moves along a cyclude, the corresponding point $C''$ rotates uniformly with an angular velocity $\sqrt{\frac{g}{r}} \cdot \pi$ point $C''$ will pass the semicircle $C_0B'$, during the same time the point $C'$ will pass the segment $C_0B'$, and the point $C$ itself will pass the arc cycludes $C_0B$. So, we not only proved that the cyclude is maytochronic (i.e., that $\tau$ does not depend on $H$), but also found the full period of oscillations:

$$T = 4\tau = 4\pi \sqrt{\frac{r}{g}}.$$

Formula (2) is the present filling of the hypothetical Galilean formula for the period of a mathematical matrix of length $l(T = 2\pi \sqrt{\frac{l}{g}})$, so it was natural to try to use (2) to justify the latter. And in fact, with the help of (2), Huygens obtained the first rigorous proof of the formula for the period of oscillation of a mathematical matrix at small swing angles $\varphi$. He noticed that at small angles a circular gland is almost no different from a cyclondal one, and all that remained was to understand at what correspondence between the length $l$ of the mathematical matrix and the parameter $r$ of the cyclonde this difference is the smallest. It turned out that at $l = 4r$ (this is not a very important fact; we will return to it later). Substituting $r = l/4$ into (2), we obtain the sign formula for the period of the mathematical matrix: $T = 2\pi \sqrt{\frac{l}{g}}$ (for small $\varphi$).

*) In fact, it has been proven that the movement of a heavy material point along a cyclonic iron can be represented as the sum of a uniform rotational movement with angular velocity, independent of the height $H$ from which the point is pushed, and some (in general, uneven) construction movement. For $H = 2r$ this can be easily deduced from the kinematic definition of the cyclude and correspondence (1), p. 21.

⟦folio 25⟧

5. Cyclondal matnik

By creating the first watch model, Heugens hoped to compensate for the deviation of a simple (mathematical) matrix from tattoo-chronicity, reducing its length in the process of deviation. The length of the matrix can be adjusted by installing “necks” (Fig. 8), on which the suspension thread will be wound during the deflection process. Attempts to experimentally determine the desired dependence of the length of the matrix on the angle of deflection were unsuccessful, and Geugens, following the properties of the clock design, installed “neck” amplitude-span limiters. When they found out that the cyclonde is a tattoochrona, it became clear that the shape of the “necks” should be such that the end of the matrix would move along the cyclonde.

Geugens was looking for the form of “shek”, reasoning (in a somewhat hesitant retelling) something like this. Let there be an obstacle bounded by a curve $L$, at some point $O$ of which a non-growing thread of length $l$ (Fig. 9) is fixed. We wind the thread around the obstacle, observing the curve $M$, which describes the loose end of the thread. Geugens called the curve $M$ the development of the curve $L$; now $M$ is called an evolute of the curve $L$, and $L$ is an evolute of the curve $M$ (many evolutes are associated with one evolute, corresponding to different lengths $l$). We need to find the evolution of the cyclonde.

Curve $M$ consists of points $B$ such that the sum of the lengths of the tangent segment $BA$ to curve $L$ at point $A$ and the other AO of curve $L$ is equal to $l$ (see Fig. 9 - this exactly means the tension partially wound on $L$ threads). Heugens's first insight was that the tangent to the curve $M$ at the point $A$ is simultaneously normal to the curve $M$ at the point $B$. The easiest way to understand this fact is based on the kinematic definition of the curve $M$. Let us remember that the velocity vector is directed tangentially to the trajectory of motion and that when the action of forces changes, the velocity vector cannot change instantly (for more details, see the article KR). “We will cut off” the obstacle at point $A$, but we will continue to move the tensioned thread (Fig. 10); then the end of the thread begins to move in a circle with the center at point $A$; its vector speed at point $B$ will not change; therefore, at point $B$, the curve $M$ and the circle with center $A$ will have a common tangent perpendicular to the radius $BA$.

The reader of the KR article will also notice that if we consider threads of different lengths, then the described movement of the end of the thread continues to such a movement of the entire plane as a solid plate, in which the points of the curve $L$ are the exchange centers of rotation, and the various involutes are the trajectories of the point of the plane. This remark immediately implies perpendicularity

⟦folio 26⟧

segment $AB$ to the tangent to the curve $M$ at point $B$.

Huygen's next guess is that in a “good” situation, the evolution of the curve is restored with dh significance (remember, one curve has many evolutions!) The fact is that the normals to the curve $M$ at different points are tangents to its evolute $L$. A “good” curve can be restored from tangents: by taking many tangents, construct the described broken line and, then “increasing” the tangents, approximate the curve better and better (they say that the curve will be estimated by the set of its tangents).

We need to find a curve whose tangents are normal to a given cyclode. Huygens guessed that this curve would be the same cyclode, only raised by $2r$ and syndicated onto the polerid (so that its vertices coincide with the points of the original cyclode; see Fig. 11).

Indeed, let $r=1$; $l$ and $l'$ are the directing lines of the corresponding lower and upper cyclodes, $O$ and $O'$ are their starting points ($l'$ one unit above $l$; $O'$ one l units to the right of $O$). Let's take a point $C$ on the line $l$ and consider the positions of the generating circles (both cyclodes) when they touch $l$ at this point $C$. Let $C'$ and $C''$ be the points diametrically opposite to it of the corresponding upper and lower circles, $A$ and $A'$ the corresponding points of the cyclodes. Arc $CC''A$ is equal in length to segment $OC$; therefore, it is l larger than the others $C'A'$, which is equal in length to the segment $O'C'$. Hence $C'CA' \cong C''CA$, and points $A'$, $C$, $A$ lie on the same straight line. It remains to note that $CA'$ is the tangent to the upper cyclode, and $CA$ is the normal to the lower one ($AC''$ is the tangent to it).

Now we know that the “necks” of the tutochronic matrix must be cyclodal, and that the length of the thread $l$ must be equal to $4r$ (it is with this value $l$ that we will obtain the desired cyclode as an involution). At small swing angles, the regulating “necks” have almost no effect on the length of the matrix, and the cyclode is close to other circles of radius $4r$ (see the end of the previous paragraph).

6. Christopher Wren's theorem.
Evolots and calculation of curve lengths

Having solved the problem of the cyclodal matrix, Huygens did not stop, realizing that he had created a wonderful mathematical theory. He writes: “To apply this powerful invention to matrices, I needed to establish a new theory, namely, the theory of processing new lines through the deployment of curved lines. Here I was faced with the task of comparing curves and straight lines. I studied this question a little further than was necessary for my purpose, since the theory seemed elegant and new to me.”

First of all, Huygens noticed that when the entire thread of the matrix is ​​wound around the “neck,” its end ends up at the top of the cyclode; this means that the length of the matrix thread ($4r$) coincides with the length of half the cyclode arch, and, therefore, the length of the cyclode arch is equal to $8r!$ This theorem was formed and proved by Christoph Wren in 1658; Huygens, as we see, obtained a very natural proof of this theorem.

Christopher Wren's theorem made a very strong impression on his contemporaries and here's why.

⟦folio 27⟧

Fig. 11.

Calculating the length of curves mathematicians were no less interested in calculating areas. At first, by analogy with the square (see p. 21), they were interested in rectification - constructing a compass and a linear segment of the corresponding length; later they began to become interested in allebraic rectification - the expression of the length of a curve using any allebraic operations. We have already said that square non-circles ending at the bottom point of the circle take the same time (similarly for chords starting at the top point of the circle).

2. Let there be a curve $L$ (sufficiently “good”) and a point $A$ not lying on $L$. Find a point $B$ on $L$ such that the segment $AB$ is traversed by the mathematical point under the influence of gravity in the minimum time.

Newton's battles

Let there be a central field in which the forces are proportional to the distance $r$ to the center: $F(r) = kr$, $k > 0$.

Newton noticed that in such a field biocyclopds (see KR) play the same role as cyclopds in the gravity field, namely:

1) biocyclopdes are (in this field) mathematical (Newton calls them isochrones);
2) evolution of biocyclopdae are the same biocyclopdae **).

Try to solve Newton’s problems (you could write a whole mathematical “essay” on this topic). Remember how tangents are drawn to biocyclops (article KR), look again at the solutions to similar problems for cyclops and ... We will discuss your solutions.

**) On mathematical clocks, see the article by S. G. Gindkin “From the history of mathematical clocks”, «Kvant», 1974, No. 9.

**) This is a purely geometric fact, it does not apply to mechanics, but it allows us to arrange a biocyclopdal mathematician, and in turn, calculate the length of the biocyclopdal.
