---
id: 1983-11-resheniya-zadach-m816-m817-m819-m820-f828-f832-fb6e14fb
issue: kvant_1983_11
year: 1983
number: "11"
title: Solutions to problems M816, M817, M819, M820; F828—F832
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 41
page_last: 45
page_labels: 39, 40, 43
tag: IIDV
lang: en
source: kvant_digital
extraction: vision
content_sha256: 69346a45dec41f4ae19480a1414111ee83f7faec2657f85a869d0ee54ae70cb3
prompt_sha256: draft-1
translated_from: content/ru/1983/11/articles/13_resheniya-zadach-m816-m817-m819-m820-f828-f832-fb6e14fb.md
source_content_sha256: 6502541d952a232a58231441eb6e423fea6100b4a3ac1d8110ff7a1e83155781
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 39⟧

Problem solutions
M816, M817, M819, M820*); F828—F832

M816. The natural numbers a and b are obtained from each other by rearranging the digits. Prove that
a) the sums of the digits of numbers 2a and 2b are equal;
b) the sums of the digits of the numbers a/2 and b/2 are equal (if a and b are even);
c) the sums of the digits of numbers 5a and 5b are equal.

First we prove one auxiliary statement.
Let $S(x)$ be the sum of the digits of the natural number $x$, $N(x)$ the number of its digits greater than 4. Then
$$S(2x) = 2S(x) - 9N(x).$$

Let's imagine that we add the number $x$ to itself in a column, starting with the lowest digits. The transfer of one to the next, $(k+1)$th digit of the sum occurs if and only if the $k$th digit of the number $x$ contains one of the digits 5, 6, 7, 8 or 9 (in the example in the margins this occurs in the 2nd, 3rd and 5th from the end of the digit), that is, the number of transfers is $N(x)$. With each transfer of a ten, which is included in the sum $S(x) + S(x)$, a unit appears, which is included in the sum $S(2x)$, that is, $S(2x)$ compared to $2S(x)$ decreases by 9. From here we get (*).

Now it is easy to prove the statement of the problem.
a) Substituting into (*) together $x$ alternately $a$ and $b$ and taking into account the next equalities $S(a) = S(b)$ and $N(a) = N(b)$, we obtain that $S(2a) = S(2b)$.
b) Note that the digit $i$ of the number $x$ is greater than 4 if and only if the digit $(i+1)$ of the number $2x$ is odd. Therefore, $N(x)$ is equal to the number of odd digits in $2x$. Therefore, for the numbers $a$ and $b$, composed of the same digits, $N(a/2) = N(b/2)$ and by virtue of (*)
$$S\left(\frac{a}{2}\right) = \frac{1}{2}\left(S(a) + 9N\left(\frac{a}{2}\right)\right) = \frac{1}{2}\left(S(b) + 9N\left(\frac{b}{2}\right)\right) = S\left(\frac{b}{2}\right).$$
c) Obviously, the numbers 10a and 10b satisfy the conditions in point 6), therefore
$$S(5a) = S\left(\frac{10a}{2}\right) = S\left(\frac{10b}{2}\right) = S(5b).$$
A. D. Lisitsky

M817. Point $K$ lies on side $BC$ of triangle $ABC$. Prove that the correspondence $|AK|^2 = |AB| \cdot |AC|$ - $|KB| \cdot |KC|$ holds if and only if $|AB| = |AC|$ or $BAK = CAK$.

Fig. 1.
$$|AK|^2 = q|AB|^2 + p|AC|^2 - |BK| \cdot |KC|$$
where $p = |BK| : |BC|$, $q = |CK| : |BC|$.

First solution (Fig. 1). Let $p = |BK| : |BC|$, $q = 1 - p = |CK| : |BC|$, then
$$\overrightarrow{AK} = \overrightarrow{AB} + \overrightarrow{BK} = \overrightarrow{AB} + p\overrightarrow{BC} = \overrightarrow{AB} + p(\overrightarrow{AC} - \overrightarrow{AB}) = q\overrightarrow{AB} + p\overrightarrow{AC}.$$
(*)

Under conditions $|AK|^2 = (q\overrightarrow{AB} + p\overrightarrow{AC})^2 = |AB| \cdot |AC|$ - $|KB| \cdot |KC| = |AB| \cdot |AC| - pq(\overrightarrow{AC} - \overrightarrow{AB})^2$.

Expanding the brackets and taking into account that $p + q = 1$, we get:
$$q|AB|^2 + p|AC|^2 - |AB| \cdot |AC| = 0.$$

Therefore, the triangle side length ratio $\lambda = |AB| : |AC|$ satisfies the quadratic equation $q\lambda^2 - \lambda + p = 0$, that is, $\lambda = 1$ or $\lambda = p/q$. In the first case $|AB| = |AC|$, in the second - $|AB| : |AC| = p/q = |BK| : |KC|$, from which, according to the well-known theorem***), it follows that $AK$ is a bisserris or $BAK = CAK$.

Using equality (*), it is easy to derive a general formula for the lengths of the segment $AK$, known as Stewart's formula. It is given in the margin.

*) Problem M818 will be solved in one of the following numbers «Kvant».
***) See, for example, S. R. Sefi Bekov “Four proofs of the Bisseris theorem” («Kvant», 1983, No. 8).

⟦folio 40⟧

Second solution. Let us take a point L on the segment BC such that $\widehat{CAL} = \widehat{KAB}$ (Fig. 2). Let us show that $|AL| = |AK|$. From here it will follow that either the points L and K coincide, that is, AK is the bissertis of angle A, or $\Delta ALK$ is equilateral and then, by the theorem on the external angle of a triangle

$$\widehat{ABC} = \widehat{AKC} - \widehat{BAK} = \widehat{ALB} - \widehat{LAC} = \widehat{ACB},$$

that is, triangle ABC is equilateral.

Let us denote by D the point of intersection of the straight line AK and the circumcircle of the triangle ABC. Since $ACB = ADB$, triangle ACL is similar to triangle ADB, hence $|AL| \cdot |AD| = |AB| \cdot |AC|$. Triangles ACK and BDK are also similar ($\widehat{ACB} = \widehat{ADB}, \widehat{AKC} = \widehat{BKD}$), so $|BK| \cdot |KC| = |AK| \cdot |KD|$. Thus, the equality given in the conditions is equivalent to the following

$$|AK|^2 = |AL| \cdot |AD| - |AK| \cdot |KD|$$

or

$$|AK|(|AK| + |KD|) = |AL| \cdot |AD|.$$

Hence it follows that $|AK| = |AL|$.

A. L. Toom, N. B. Vasiliev

**M819. There are n cities in Schwambrania, each two of which are connected by a road. (Roads converge only in cities, all intersections are limited at different corners.) The evil wizard intends to establish one-way traffic on each road so that, once you leave any city, it will no longer be possible to return to it. Prove that a) a wizard can do this;
b) in this case, there will be a city from which you can get to all the others, and there will be a city from which you cannot leave;
c) there are $n! = 1 \times 2 \times \dots \times n$ ways to carry out this wizard's intention.**

a) The wizard can number all the cities of Schwambrania with numbers from 1 to n and set on each road a movement from the city with the lower number to the city with the higher number. By doing this, he will achieve his goal, because the numbers of cities that are encountered when moving along any route with such a restriction will always be returned.

b) Starting from any city, we will go along the roads of Schwambrania, observing the rules of this wizard. Let us marvel as long as this is possible. No city will be found on our route, and since the number of cities is finite, sooner or later we will have to stop. But this means that we ended up in city Z, from which we cannot leave.

Now let's reverse the directions of movement on all roads. It is clear that, according to the new rules, we will again not be able to visit the same city. Therefore, as above, there is a city A from which you cannot leave according to the new (!) rules. Consequently, initially on the road connecting A with any other city B, traffic was established from A to B, that is, from A you can get to any city (only one road is passed).

Note that you can travel from any city except Z (for example, to Z), and you can travel to any city except A.

c) Let us carry out induction on the number of cities n. For n = 1, statement c) is obvious. Let us prove it for n cities, assuming that it is valid for n - 1 cities. According to point 6), for any traffic rules satisfying the conditions of this wizard, there is one and only one city Z from which it is impossible to leave. It can be any of n cities.

On all roads connecting towards the city Z. Therefore, no route connecting two other cities can no longer pass through Z and it is only necessary to set the directions on the roads between the remaining n - 1 cities so that it is impossible to go to any of them while traveling along these directions. By the induction hypothesis this can be done (n - 1)! ways. Therefore, the total number of ways is n · (n - 1)! = n!.

Another solution is based on the fact that there is a single longest (in terms of number of roads) route

⟦folio 43⟧

The vapor above the surface of the raster contains only water molecules. The universal value constant is $R = 8,3$ J/(mol K).

We find the density $\rho_{\pi}$ of steam at a temperature $T = 293$ K from the equation of the gas state:

$$\rho_{\pi} = p_{\text{mac}} \frac{\mu}{RT}.$$

Thus,

$$h = \frac{0,05c_2RT}{\mu g} (2 \frac{h_0}{h} - 1).$$

Substituting the numerical data given in the conditions, we find

$$h \approx 16,4 \text{ см.}$$

It is interesting to note that, as follows from the problem considered, if there are two identical vessels with solutions of different concentrations under the hood, then evaporation will occur from the solution with a lower concentration. Conversely, water vapor will condense into a solution with a higher concentration. Thus, concentrations will tend to equalize. It is this physical phenomenon that is associated with the wetting of sugar, salt, etc. in an atmosphere of humid air.

A. I. Buzdin

F831. An uncharged conducting thin-walled spherical shell is placed in a uniform electric field. When the field direction is $E_0$, the shell breaks. At what minimum field direction will a shell of twice the radius and having the same wall thickness rupture?

◆ A conductive shell placed in an electric field will have induced charges. The surface density of these charges is proportional to the direction of the field $E$. When the size of the shell changes by $n$ times and the direction of the field by $k$ times, the forces acting on the halves of the sphere (on which charges of opposite signs are induced) changes by $k^2n^2$ times.

Since the wall thickness remains constant, the force per unit length of the shell should be the same. If in the first case the discontinuity is proportional to the direction of the field by $k$ times and the direction of the field by $n$ times and the direction of the field by $k$ times the discontinuity is proportional, From condition $f = (k^2n^2/n)f_0$. From condition $f = f_0$ it follows:

$$\frac{k^2n^2}{n} = 1 \Rightarrow k = \frac{1}{\sqrt{n}}.$$

When the shell radius doubles, the discontinuity is proportional to the field

$$E = E_0 / \sqrt{2}.$$

S. K. Strokov

F832*. A square non-deformable superconducting frame on side a is located horizontally and is in a low-grade magnetic field, the induction of which varies in space according to the law

$$B_x = -kx,$$

$$B_y = 0,$$

$$B_z = kz + B_0.$$

Frame mass $m$, inductance $L$. At the initial moment, the center of the frame coincides with the origin of coordinates, and the sides are parallel to the $X$ and $Y$ axes. The frame is tarnished. How will it move and where will it end up after time $t$?

The magnetic flux producing the area limited by the superconducting circuit is constant. Indeed, $\Delta \Phi / \Delta t = \delta_i$, but $\delta_i = iR = 0$ (since $R = 0$), therefore $\Phi = B_0 a^2 + kz^2 + Li$.

Since at the initial moment $(z = 0, i = 0)$ $\Phi = B_0 a^2$, at any other moment of time the value of point $i$ will be determined by the relation

$$Li = -kz^2 \Rightarrow i = -\frac{kz^2}{L}.$$

The resulting force acting from the magnetic field on the frame with current $i$ is equal to the sum of the forces acting on those sides of the frame that are parallel to the axis $Y$,
