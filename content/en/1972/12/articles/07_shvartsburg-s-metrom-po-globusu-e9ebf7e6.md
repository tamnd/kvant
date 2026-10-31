---
id: 1972-12-shvartsburg-s-metrom-po-globusu-e9ebf7e6
issue: kvant_1972_12
year: 1972
number: "12"
title: With a meter around the globe
authors:
  - Шварцбург А. Б.
rubric: raznoe
page_first: 28
page_last: 34
page_labels: 26-32
tag: CAMU
lang: en
source: kvant_digital
extraction: vision
content_sha256: 737533c0fb29b3e1c5174180f0b23a5d2652fb38140226d412f110aebba5c84c
prompt_sha256: draft-1
translated_from: content/ru/1972/12/articles/07_shvartsburg-s-metrom-po-globusu-e9ebf7e6.md
source_content_sha256: 1a27f2ebc69cc35e6bf50d7240fbbc1456929628a3dd62edc00ce9933d03faff
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 26⟧

WITH METER ON THE GLOBE

A. B. Schwartzburg

Let's try to draw on the surface of the globe the path of a ship that left port $A$ and must go to port $B$. This path can be done in different ways, and each has its own advantages and disadvantages. If the ship is in a hurry, then it is important to know the shortest route between ports. As you know, on a plane the shortest distance between two points is a straight line. However, on the sphere the picture is conditional. By stretching a thread flexible and inextensible on a globe between points $A$ and $B$ (the beginning and end of the path), one can find a position of the thread at which the length $AB$ will be the smallest. However, the orientation of the thread relative to the grid of meridians and parallels marked on the globe will be different at each point along the length $AB$. This means that it is not easy to lay such a path on the open sea.

You can choose another method - for example, move all the time in one direction, crossing all meridians at the same angle. Then it will be easier to navigate the sea. However, using the same thread on the globe, it is easy to verify that such a path will be longer than the first. To better imagine each path, consider one auxiliary problem.

Movement near the pole

On a school map, meridians and parallels are usually depicted in the form of a rectangular grid. However, to depict areas adjacent to the pole, another coordinate grid is used, in which meridians are represented by rays emanating from the pole $O$, and parallels are represented by circles centered at the pole. Let us assume that points $A$ and $B$ are marked on such a map. Let's try to plot the trajectory $AB$, not caring about the length of the path, but requiring that the direction of movement be constant. In other words, it is required to measure a flat curve that would pass through points $A$ and $B$, intersecting all rays emerging from the pole at some constant angle $\alpha$ (Fig. 1, a).

The coordinates of the point $A$ and $B$ are considered known (that is, their distances to the pole $\rho_A$ and $\rho_B$ and the difference in their longitudes are known). It is easy to indicate a special case of such a trajectory corresponding to $\rho_A = \rho_B$. A line perpendicular to all rays emanating from one point is a circle. To find a trajectory at an arbitrary angle $\alpha$, consider two rays forming a small angle $\theta$. Let one of them $OA = \rho_0$ correspond to the value $\theta = 0$. Putting aside $ON = \rho_0 = OA$ (Fig. 1, b) on the second ray, we note that $\rightarrow ANO \approx \frac{\pi}{2}$ (since the angle $\theta$ is small).

⟦folio 27⟧

Let the trajectory intersect the ray $ON$ at point $K$. Then from the triangle $ANK$, in which $AN = \rho_0 \theta^*$): we find $NK = AN \cdot \text{ctg} \alpha = \rho_0 \theta \text{ctg} \alpha$. From this we can see that the length of the radius vector of the trajectory $OK$ is

$$\rho_1 = \rho_0 - \rho_0 \theta \text{ctg} \alpha = \rho_0 (1 - \theta \text{ctg} \alpha).$$

Delaying the angle $\theta$ clockwise from $ON$ again, we obtain for the radius vector

$$\rho_2 = \rho_1 (1 - \theta \text{ctg} \alpha) = \rho_0 (1 - \theta \text{ctg} \alpha)^2.$$

Repeating these calculations $n$ times, we find

$$\rho_n = \rho_0 (1 - \theta \text{ctg} \alpha)^n.$$

Suppose that the radius vector $\rho_0$ has rotated through an angle $\lambda$ in $n$ turns, then $\theta = \frac{\lambda}{n}$ and

$$\rho_n = \rho_0 \left(1 - \frac{\lambda}{n} \text{ctg} \alpha\right)^n.$$

Let us assume that we, considering the angle $\lambda$ constant, increase the number of “steps” so that the magnitude of one “step” $\theta = \frac{\lambda}{n}$ decreases. If $n$ increases indefinitely, then this will correspond to the continuous movement of the point along the trajectory. Passing in formula (4) to the prelude at $n \to \infty$, we find (see L. G. Limanov “On the number $e$ and $n!$” «Kvant» No. 5, 1972):

$$\rho = \lim_{n \to \infty} \rho_n = \rho_0 e^{-\lambda \text{ctg} \alpha},$$

where $e = 2,73$ is a constant known in mathematics, the famous “number $e$”, which is the base of natural logarithms.

We have obtained the equation of a curve that intersects all rays emanating from the center at an angle $\alpha$. The value of this angle can be found by knowing the coordinates of the points $A$ and $B$ and the difference in their longitudes $\lambda$. From (5) we find

$$\text{ctg} \alpha = -\frac{1}{\lambda} \ln \frac{\rho}{\rho_0}.$$

Crossing each meridian at an angle $\alpha$, the crucian carp will come from port $A$ to port $B$.

From formula (6) one can see other important properties of the resulting curve: the angle between the radius vectors is proportional to their logarithm

*) Such a replacement is equivalent to an approximate equality made for small values ​​of the angle $x \left(x \ll \frac{\pi}{2}\right)$: $\sin x \approx x$. This equality and the equality $\text{ctg} x \approx x$ that follows from it are used more than once in this article.

⟦folio 28⟧

$$\lambda = - \frac{\ln \frac{\rho}{\rho_0}}{\text{ctg} \alpha}.$$

Curve (5) has a special name “logarithmic spiral”, and the mathematician Jacob Bernoulli even called it “spira mirabilis”, which in Latin means “wonderful spiral”.

In this auxiliary problem, the part of the earth's surface on which motion occurs was considered a plane. Let's try to generalize the resulting solution (6) to the case of a spherical surface. In other words, let's try to draw a curve on the globe connecting points A and B and intersecting all meridians at a constant angle α. In this case, we will need the same mathematical primer that was used in the auxiliary problem.

Snell curve

We will assume that at least one of the points A and B does not coincide with the pole of the sphere. (If A and B are poles, then any meridian is an exception of the curve). We will characterize the position of each point by its latitude φ, absence from the equator, and longitude λ. It is required to check a curve on the sphere starting from point A with coordinates φ_A, λ_A and arriving at point B with coordinates φ_B, λ_B (see Fig. 2), so that all meridians intersect at the same angle α. In an auxiliary problem we showed that a plane curve with this property is a logarithmic spiral.

Consider two close points on the sphere (A and N) (Fig. 3), the difference in latitude (arc AO) is Δφ, and the difference in longitude (arc ON) is θ, where θ is a small angle, (θ << λ). If both points lie on the curve of interest to us, then this curve forms equal angles α with the meridians passing through these points. Consider the curved triangle AON, where the arc AO coincides with the part of the meridiana, the arc ON with the part of the circle of latitude φ₁, and ⇄ OAN = α. Let us denote the value of the coordinate φ at point A by φ_A = φ_0. Thus, φ₁ = φ_0 + Δφ.

Fig. 2.
Fig. 3.

⟦folio 29⟧

It can be rigorously proven that the coordinate values ​​$\varphi_0$ and $\varphi_1$ are related as follows:

$$\text{tg} \left( 45^\circ + \frac{\varphi_1}{2} \right) = \text{tg} \left( 45^\circ + \frac{\varphi_0}{2} \right) [1 + \theta \text{ctg} \alpha].$$

(A detailed derivation of this equality is given in Appendix I.)

Further, you can reason in the same way as when solving an auxiliary problem. The value of the function $\text{tg} \left( 45^\circ + \frac{\varphi}{2} \right)$ at the point with coordinates $\varphi_2$, $2\theta$ will be

$$\text{tg} \left( 45^\circ + \frac{\varphi_2}{2} \right) = \text{tg} \left( 45^\circ + \frac{\varphi_1}{2} \right) [1 + \theta \text{ctg} \alpha] =$$

$$= \text{tg} \left( 45^\circ + \frac{\varphi_0}{2} \right) [1 + \theta \text{ctg} \alpha]^2.$$

After $n$ “steps” we get for $\varphi_n$

$$\text{tg} \left( 45^\circ + \frac{\varphi_n}{2} \right) = \text{tg} \left( 45^\circ + \frac{\varphi_0}{2} \right) \left[ 1 + \frac{\lambda}{n} \text{ctg} \alpha \right]^n.$$

Let us now assume that we notify the number of “steps” $n$ to infinity, approaching the point $B$. At the same time $\varphi_n \rightarrow \varphi_B$. Then the value of each step $\theta = \frac{\lambda}{n}$ tends to 0, and the number of factors on the right side of (9) grows without limit. Passing to the limit at $n \rightarrow \infty$ in formula (9), we obtain (by analogy with formula (5)):

$$\text{tg} \left( 45^\circ + \frac{\varphi_B}{2} \right) = \lim_{n \rightarrow \infty} \left\{ \text{tg} \left( 45^\circ + \frac{\varphi_A}{2} \right) \left[ 1 + \frac{\lambda}{n} \text{ctg} \alpha \right]^n \right\} =$$

$$= \text{tg} \left( 45^\circ + \frac{\varphi_A}{2} \right) e^{\lambda \text{ctg} \alpha}.$$

The resulting curve intersects all meridians on the sphere at a constant angle $\alpha$. The value of this angle can be easily found from (10), knowing the latitude of each port ($\varphi_A$ and $\varphi_B$) and the difference in longitude ($\lambda_B - \lambda_A) = \lambda$ between them:

$$\text{ctg} \alpha = \frac{1}{\lambda} \ln \frac{\text{tg} \left( 45^\circ + \frac{\varphi_B}{2} \right)}{\text{tg} \left( 45^\circ + \frac{\varphi_A}{2} \right)}.$$

The curve expressed by formula (10) has a special name “loxodrome”, which can be translated from Latin as “oblique”. This curve was studied in the 18th century by the mathematician Snell, who is also famous for the fact that he formed the law of refraction of light rays at the boundary of two media, known as the homeschooler.

The loxodrome crosses “obliquely” the meridians of the ball and approaches the pole, “winding” onto it like a spiral. It is not difficult to show that the alignment of the loxodrome pole is close to the logarithmic spiral, which we discussed in the auxiliary problem. Indeed, near the pole $\varphi = 90^\circ - \delta$, where $\delta \ll 90^\circ$. Then

$$\frac{\text{tg} \left( 45^\circ + \frac{\varphi}{2} \right)}{\text{tg} \left( 45^\circ + \frac{\varphi_0}{2} \right)} \approx \frac{\text{tg} \left( \frac{\delta_0}{2} \right)}{\text{tg} \left( \frac{\delta}{2} \right)} \approx \frac{\delta_0}{2} \frac{\delta}{2}.$$

⟦folio 30⟧

Comparing formulas (10a) and (10), we obtain

$$\delta = \delta_0 e^{-\lambda \text{ctg} \alpha}.$$

(106)

On the other hand, the distances from the pole to points $A$ and $B$, whose latitudes are $\delta_A$ and $\delta_B$, are equal to the correspondence $\rho_A = R \delta_A$, $\rho_B = R \delta_B$ (R is the radius of the globe). (When writing these equalities, we replace part of the meridian arc with a chord connecting the ends of the arc.) Then from (106) we obtain:

$$\rho_B = \rho_A e^{-\lambda \text{ctg} \alpha}.$$

(10v)

We have already obtained this equality in an auxiliary problem.

Loxodrome (10) describes the course of a ship on the open sea, in which the direction of movement remains constant, so it is easy to navigate along the way. However, the path along the rhoxodrome, as we said above, is not the shortest path on the sphere between two points.

Geodetic line

Let's now try to find a curve that is the shortest path between two points on the ball. Such a curve is called a geodesic line, but it is not only for surveyors. This curve is also important for sailors, pilots, and travelers. If we simplify the problem and choose points $A$ and $B$, located on the same circle of latitude $\varphi$, then it may seem that the shortest path between these points is an arc of the circle of latitude. However, this answer is incorrect. To verify this, compare the distances $S_1$ and $S_2$ between points $A$ and $B$, modified along the latitude circle ($S_1$) and along the great circle arc ($S_2$) (Fig. 4). If the difference in longitudes of points $A$ and $B$ is $\lambda$, then

$$S_1 = R \lambda \cos \varphi,$$

$$S_2 = RC,$$

where $C$ is the radian measure of arc $S_2$.

It can be proven that the magnitude of the arc $C$ (in radians) is equal to

$$C = \arccos \left[ \cos^2 \varphi' + \sin^2 \varphi' \cos \lambda \right],$$

where $\varphi' = \frac{\pi}{2} - \varphi$. (This is proven in Appendix II.)

Let us prove that the length of the arc of the great circle $S_2$ is not greater than the length of the arc of the latitude circle $S_1$ ($S_2 \leq S_1$), that is, we will prove the inequality:

$$R \arccos \left[ \cos^2 \varphi' + \sin^2 \varphi' \cos \lambda \right] \leq R \lambda \sin \varphi'.$$

(14)

Equality (14) returns only for $\varphi' = 90^\circ$ or $\varphi = 0$, that is, when the latitude circle coincides with the great circle.

Both sides of inequality (14) are positive. We will assume that the difference in longitude between points $A$ and $B$ lies in the interval $0 \leq \lambda \leq \pi$. For $0 \leq \lambda \leq \pi$ cos $\lambda$ is a decreasing function.

⟦folio 31⟧

From inequality (14) follows the following inequality:

$$\cos^2 \varphi' + \sin^2 \varphi' \cos \lambda \geq \cos (\lambda \sin \varphi').$$

Using the identity $\cos \lambda = 1 - 2 \sin^2 \frac{\lambda}{2}$, we reduce inequality (15) to the form

$$\sin^2 \varphi' \sin^2 \frac{\lambda}{2} \leq \sin^2 \left( \frac{\lambda}{2} \sin \varphi' \right).$$

Multiplying and dividing this inequality by the positive value $\left( \frac{\lambda}{2} \sin \varphi' \right)^2$, we obtain:

$$\left( \frac{\sin \frac{\lambda}{2}}{\frac{\lambda}{2}} \right)^2 \leq \left( \frac{\sin \left( \frac{\lambda}{2} \sin \varphi' \right)}{\frac{\lambda}{2} \sin \varphi'} \right)^2.$$

If we now construct graphs of the functions $y = \left( \frac{\sin x}{x} \right)^2$ using trigonometric tables, we will see that this function increases monotonically from $y = \left( \frac{2}{\pi} \right)^2 < 1$ to 1 as $x$ decreases from $\frac{\pi}{2}$ to 0. Since $\frac{\lambda}{2} \sin \varphi' \leq \frac{\lambda}{2}$, then inequality (17) is always satisfied, which means that the original inequality (14) is also satisfied. Consequently, the arc of the great circle is shorter than the other latitudinal circles connecting the same two points.

It can be proven that even with an arbitrary location of two points on a sharra, the shortest distance between them is determined by the arc of a great circle passing through these points. In other words, the geodesic line on a ball is the arc of a great circle.

However, it is difficult to navigate when moving along a great circle arc - the angle $\alpha$ between the direction of movement and the meridian changes all the time.

Thus, the rhoxodrome and great circle paths have their advantages and disadvantages. When choosing between these paths, they often act in the same way as when moving along a plane, when together movements along a complex plane curve outline paths along a broken line, all the vertices of which lie on the desired curve.

Similarly, when moving on a sphere, several points are marked on the great circle arc connecting the point of departure and destination, and from point to point one moves along rhoxodromes.

**Appendix I**

It is convenient to characterize a point on a sphere not by latitude $\varphi$, but by an additional angle $\varphi'$

$$\varphi' = 90^\circ - \varphi.$$

The convenience of this description is due to the fact that the function $ctg \left( \frac{90^\circ - \varphi}{2} \right)$ has an important property. Let's calculate, using the formula for the tangent of the sum of two angles, the increment of this function when changing $\varphi$:

$$ctg \left( \frac{90^\circ - \varphi}{2} \right) = tg \left( \frac{90^\circ + \varphi}{2} \right) = tg \left( 45^\circ + \frac{\varphi}{2} \right);$$

⟦folio 32⟧

$$\Delta tg \left( 45^\circ + \frac{\varphi}{2} \right) = tg \left( 45^\circ + \frac{\varphi}{2} \right) - tg \left( 45^\circ + \frac{\varphi}{2} \right) =$$

$$= \frac{tg \left( 45^\circ + \frac{\varphi}{2} \right) + tg \frac{\Delta \varphi}{2}}{1 - tg \left( 45^\circ + \frac{\varphi}{2} \right) tg \frac{\Delta \varphi}{2}} - tg \left( 45^\circ + \frac{\varphi}{2} \right) =$$

$$= \frac{tg \frac{\Delta \varphi}{2}}{\cos^2 \left( 45^\circ + \frac{\varphi}{2} \right)} \cdot (I-3)$$

Using the same identity $\frac{1}{\cos \left( 45^\circ + \frac{\varphi}{2} \right)} = 2 \sin \left( 45^\circ + \frac{\varphi}{2} \right) \cos^{-1} \varphi$, we obtain from the formula

$$\Delta tg \left( 45^\circ + \frac{\varphi}{2} \right) = \frac{2 tg \frac{\Delta \varphi}{2} tg \left( 45^\circ + \frac{\varphi}{2} \right)}{\left[ 1 - tg \frac{\Delta \varphi}{2} tg \left( 45^\circ + \frac{\varphi}{2} \right) \right] \cos \varphi}.$$

(I-4)

Consider the case where the increments $\Delta \varphi$ are small, so that $|tg \frac{\Delta \varphi}{2}| \cdot |tg \left( 45^\circ + \frac{\varphi}{2} \right)| \ll 1$. Then the value in formula (I-4) can be considered approximately equal to 1, and $tg \frac{\Delta \varphi}{2}$ can be replaced by $\frac{\Delta \varphi}{2}$. Then from (I-3) and (I-4) we find:

$$\Delta tg \left( 45^\circ + \frac{\varphi}{2} \right) = \frac{\Delta \varphi}{\cos \varphi} \cdot tg \left( 45^\circ + \frac{\varphi}{2} \right).$$

(I-5)

Formula (I-5) shows that the function $tg \left( 45^\circ + \frac{\varphi}{2} \right)$ actually has important properties: small increments of this function are proportional to the value of the function itself.

Let's find the proportionality coefficient in formula (I-5). Since the radius of the spin circle is equal to

$$r = R \cos \varphi,$$

then the length of arc $ON$ is (see Fig. 3)

$$ON = R \theta \cos \varphi.$$

Here $R$ is the radius of the sphere. Similarly, the length of arc $OA$ is

$$OA = R \Delta \varphi.$$

Since the angle $\angle AON = \frac{\pi}{2}$ in a triangle, then for the tangent of angle $\alpha$ we can write

$$tg \alpha = \frac{R \theta \cos \varphi}{R \Delta \varphi}.$$

From this relationship, $\frac{\Delta \varphi}{\cos \varphi}$ is found in formula (I-5):

$$\frac{\Delta \varphi}{\cos \varphi} = \theta \text{ ctg } \alpha.$$
