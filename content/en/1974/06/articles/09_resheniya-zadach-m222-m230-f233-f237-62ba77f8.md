---
id: 1974-6-resheniya-zadach-m222-m230-f233-f237-62ba77f8
issue: kvant_1974_6
year: 1974
number: "6"
title: Solutions to problems M222—M230; F233—F237
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 22
page_last: 32
page_labels: 20, 21, 22, 23, 25, 26, 27, 28, 29, 30
tag: 3UD9
lang: en
source: kvant_digital
extraction: vision
content_sha256: 125545bf1f3cd9639eb64e36937f0b02520ceea3f57c681805d5ffc2db700697
prompt_sha256: draft-1
translated_from: content/ru/1974/06/articles/09_resheniya-zadach-m222-m230-f233-f237-62ba77f8.md
source_content_sha256: 307cc7ab25cac9c97d206621af7abc4b51c4ad69983b8b0073ca52292015d00a
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 20⟧

Problem solutions
M222—M230; F233—F237

M222. Prove that every convex polygon has two faces with the same number of sides.

Suppose that any two faces of a convex polygon have a different number of sides. Let us consider the face G with the smallest number of sides. Let us consider that face O, which has the smallest number of sides. Let us consider the face C that has less of this among the other faces. This means that the number of remaining faces of this is less than m (by entering even if there were 1-gons and 2-gons, we could only enter m - 1 different polygons). On the other hand, the face Γ is adjacent to exactly m other faces of the polygon (one to each side). We got a contradiction.

It stands to reason that some two faces must have the same number of sides.

The given solution almost verbatim repeats the solution to the following, fairly well-known problem (using the “Dirichlet principle” *)).

In the book theater "October" at the last session there will definitely be two targets whose number of acquaintances is the same.

However, our problem is geometric in essence - there is no guarantee in its solution.

*) See article by A. I. Orlov “Priitsip Dirichlet”, «Kvant», 1971, No. 7.

Fig. 1.

The use of convexity of a polygon is where it is stated that a face having m sides is adjacent to m faces. This means that each edge of a face of a polygon is adjacent to exactly one face, and different edges of this face are adjacent to different faces. However, this is not true for small polytopes - on figure 1 the edges a, b are adjacent to the same face α, so in the count of faces it is taken into account twice, and the above reasoning becomes incorrect.

The statement of the problem, however, remains valid for small polygons (without “through holes”) - its proof is based on Euler’s formula *)

B - P + Γ = 2;

it is rather cumbersome and not so elegant that it is necessary to present it here.

G. A. Galperin

M223. A natural number is called perfect if it is equal to the sum of all its divisors except the number itself. (For example, the number 28 is perfect: 28 = 1 + 2 + 4 + 7 + 14.) Prove that a perfect number cannot be a perfect square.

Let n = p₁ᵢ p₂ᵢ ... pᵢᵢ m, where p₁, ..., pᵢ are distinct primes, r₁, ..., rᵢ are natural numbers (according to the fundamental theorem of arithmetic, every integer n > 1 can be represented in this form in a unique way).

The divisors of n are numbers of the form

p₁ᵢ p₂ᵢ ... pᵢᵢ m,

where 0 ≤ k₁ ≤ r₁, ..., 0 ≤ kᵢ ≤ rᵢ. Therefore, the sum of all divisors of n (including 1 and n) is equal to the product

S = (1 + p₁ + ... + p₁ᵢ) ... (1 + pᵢ + ... + pᵢᵢ).

Since n is a perfect number, S must be equal to 2n, that is, it must be an even number. But if n is the square of an integer, then all exponents r₁, ..., rᵢ are even numbers, so the square is a parenthesis in the product S

$$\frac{(1 + p_i + p_i^2 + ... + p_i^{i-1})}{1 + r_i}$$

If the number is odd, therefore S is odd.

We have received a contradiction, which means that a perfect number cannot be a perfect square.

Some readers derive their solution from the formula 2p⁻¹ (2p - 1) for what

*) See article by A.P. Savin “Maps and coloring books”, «Kvant», 1972, No. 4.

⟦folio 21⟧

Fig. 2.

and you are perfect numbers *). Such solutions are incomplete: after all, no one has yet proven that there are no odd perfect numbers.

M224. For a trihedral angle, bicectors of plane angles are drawn. Let us prove that the pairwise angles between three bisectors are either all tule, or all acute, or all right.

The simplest solution to this problem is based on the concept of a scalar product of vectors. For example, the scalar product of vectors a and b is the number

$$ab = |a| |b| \cos \varphi,$$

where $|a|$ and $|b|$ are the lengths of vectors a and b, $\varphi$ is the angle between them. Thus, the angle between a and b is acute, right or obtuse if $ab > 0$, $ab = 0$ and $ab < 0$ respectively. Of course, for any vectors $ab = ba$. We also need the distributivity (distribution property) of the scalar product: for any three vectors a, b and c

$$(a + b)c = ac + bc$$

(this property was discussed in detail in «Kvant», 1972, No. 6).

Let a trihedral angle be given. For example, along its edges there are vectors of unit length a, b and c. Then the vectors a + b, b + c, c + a flow along the bicsectrices of plane angles. Dot products

$$\begin{align*}
(a + b)(b + c) &= \\
(b + c)(c + a) &= \\
(c + a)(a + b) &= \\
\end{align*}$$

are the same - thus, the angles between bicectors will be simultaneously acute, right or obtuse. This solution was also proposed by the author of the problem, E. G. Gotman.

For those unfamiliar with vectors, we will give a more straightforward, purely geometric explanation. Let us first note this fact

*) See «Kvant», 1971, No. 8, p. 2.

Fig. 3.

If $OL$ is a ray lying in the plane $p$, $OM$ is a ray not perpendicular to this plane, $OM'$ is the projection of ray $OM$ onto the plane $p$, then the angle $LOM$ is acute, straight or obtuse, depending on whether the angle is acute, right or obtuse $LOM'$; real, if through the point $O$ the plane $q$ is drawn perpendicular to the ray $OL$, then the points $M$ and $M'$ always lie on the same side of the plane $q$ (after all, $MM' \perp p$ and $q \perp p$, see Fig. 2). Let $OA, OB, OC$ be the edges of a trihedral angle; $OK, OL, OM$ — bicsectrices of angles $AOB, BOC, COA$; $p$ is the plane passing through $OK$ and $OL, OA', OB', OC', OM'$ are the projections of rays $OA, OB, OC, OM$ onto the plane $p$.

Rays $OA$ and $OC$ are symmetrical to ray $OB$ relative to straight lines $OK$ and $OL$, respectively. Therefore, $OA'$ and $OC'$ are symmetrical $OB'$ relative to the same lines, and all three rays $OA, OB$ and $OC$ make the same angles with the plane $p$.

Let us first consider the situation in the $p$ plane - for projections. If $KOL < 90^\circ$ (Fig. 3), then $A'OC' = 2 \times KOL < 180^\circ$ contains the internal ray $OK, OL$, it is clear that the angles that make the right angles $OK$ and $OL$ with the bicsectrix $OM'$ of the angle $A'O'C'$ are acute. If $KOL > 90^\circ$ (Fig. 4), then $A'OB' + B'OC' = 2 \times KOL > 180^\circ$, so the bicsectrix $OM'$ of angle $A'OC'$ is $OK$ and $OL$ obtuse angles. (Case $KOL = 90^\circ$ is considered itself.)

⟦folio 22⟧

From the fact mentioned above, it now immediately follows that the angles LOM and KOM are acute, obtuse or right, if such is the angle KOL.

N. B. Vasiliev

M225. The faces of the cube are lined with the numbers 1, 2, 3, 4, 5, 6, poppy, so that the sum of the numbers on the opposite faces is 7. The cube cumt from the lower left to the upper right corner of a maximal doxie measuring 50 × 50 cells (each doxie cell is equal to a cube) poppy, so that each time it rolls over its edge onto the adjacent square; in this case, the milk is cut to the right or upward. On each of the cells along the path of the cube there is a number of a face; the comora rested on this cell. What is the greatest value the sum of all 99 numbers written down can have? What is the smallest?

Suppose we somehow rolled the cube from the lower left corner of the doxy to the upper right. We will assume that after each roll over an edge, the doxie cell is imprinted with the number written on the side of the cube that rested on this cell.

We write out the printed numbers $\alpha_1, \dots, \alpha_{99}$ in a row on a line, and denote their sum by $\Sigma$:

$$\alpha_1 + \alpha_2 + \dots + \alpha_{99} = \Sigma.$$

If the numbers on all sides of the cube are replaced by the average number 3.5, then the sum of the printed numbers will be equal to

$$\Sigma_{cp} = 3,5 \cdot 99 = 346,5.$$

We need to determine the most values ​​of $\Sigma$. Let us estimate the quantities $|\Sigma - \Sigma_{cp}|$ for this.

The most important property of the numbers in the sequence $\alpha_1, \dots, \alpha_{99}$ is the following. Let the numbers $\alpha$ in the sequence number $\alpha$ occur twice in a row ($\alpha =$ one of the numbers 1, 2, 3, 4, 5, 6).

Since there are as many numbers $\alpha$ in the sequence as there are numbers $7 - \alpha$;

2) or there are exactly one more numbers $\alpha$ than numbers $7 - \alpha$;

3) or there are exactly one fewer numbers $\alpha$ than numbers $7 - \alpha$.

In case 1) replacing all numbers $\alpha$ and $7 - \alpha$ by 3.5 does not change their inclusion in $\Sigma$. In case 2) and 3), replacing all the numbers $\alpha$ and $7 - \alpha$ by 3.5, including them in $\Sigma$ will increase or decrease by $(3,5 - \alpha)$. As a result, the entire amount will increase or decrease at most by $(3,5 - 1) + (3,5 - 2) + (3,5 - 3) = 4,5$.

Thus,

$$342 = \Sigma_{cp} - 4,5 \leq \Sigma \leq \Sigma_{cp} + 4,5 = 351.$$

The values ​​$\Sigma_{max} = 351$ and $\Sigma_{min} = 342$ are actually achieved by rolling the cube as shown in Figures 5 and 6.

G. A. Galperin

M226. At the three vertices of the square there are three grasshoppers. They are leapfrogging. Moreover, if the grasshopper $A$ spins the grasshopper $B$, then after spinning it ends up at the same distance from $B$ (but, naturally, on the other side and on the same spicy side; Fig. 7). After several spins, can one of the grasshoppers hit the central vertex of the original square?

Let us prove that none of the grasshoppers can get to the central vertex.

⟦folio 23⟧

Fig. 7.

Let's enter coordinates on the plane so that the three points where the grasshopper is located at the very beginning receive coordinates: (0, 0), (0, 1) and (1, 0).

If a grasshopper sits at point $(x, y)$ and yokes through grasshopper $(a, b)$, then it ends up at point $(2a-x, 2b-y)$ (Fig. 8). From this it can be seen that with buckles, the parity of both coordinates for each grasshopper is preserved. Therefore, none of the grasshoppers can get to those points where both coordinates are odd - in part, to the point $(1, 1)$.

This solution can be declared without coordinates. figure 9 shows many dots: synch, red and black. (We marked the grasshoppers with these colors to distinguish them from each other). It is easy to check that if any of its points is symmetrical, this set of points transforms into itself, and a point of each color transforms into a point of the same color. It follows that each grasshopper can only hit a point of its own color.

Prove that after several buckles each grasshopper can end up at any point of its color. Also try to answer a more difficult question: can two grasshoppers be simultaneously in any two given points of the corresponding color? What points can three grasshoppers hit at the same time?

There is a simple and clear answer to this question, but we will not deprive the reader of finding it on his own, but will return to it in one of the next issues of the magazine.

M227. A point is taken on each side of the parallelogram. The area of ​​a quadrilateral with vertices at these points is equal to half the area of ​​a parallelogram. Prove that at least one of the diagonals of the quadrilateral is parallel to one of the sides of the parallelogram.

Obviously, if at least one of the diagonals of the quadrilateral KLMN (Fig. 10) is parallel to the side of the parallelogram ABCD, then the area of ​​the quadrilateral s is equal to half the area of ​​the parallelogram S.

Let us now assume that the diagonal LN is not parallel to AD. Let us fix the positions of points L, M and N and see how the area s changes depending on the position of point K on side BC. Since the area of ​​the triangle LMN does not change, and the area of ​​the triangle KLN with a fixed base LN is proportional to the distance from point K to the straight line LN, it is clear that when point K moves from B to C, the area of ​​the quadrilateral KLMN will change monotically: increase if LC>BN, and decrease if LC<BN. We know that if KM || AB, then the area s is equal to half S; but since the value of s changes monotically, it means that for all other positions of the point K, the area of ​​s will be either greater or less than S/2.

Thus, $s = S/2$ only when either LN || AD or KM || AB, which is what needed to be proven.

It would be possible to do without monotism messages (however, the weights obtained), and simply express the area ratio s/S in terms of the lengths of the segments $|BC| = |AD| = a, |AB| = |CD| = b, |AM| = x_1$.

Fig. 9.

Fig. 10.

⟦folio 25⟧

Lyceum is equal to $u$, and will enter - $v$. The goal of the policeman is to end up with a skid on one side of the square. Prove that

a) if $\frac{u}{v} > \frac{1}{3}$, then he can achieve his goal;
b) if $\frac{u}{v} < \frac{1}{3}$, then the score can allow him to do this.

The problem conditions say nothing about what will happen to the policeman and the gangster if $\frac{u}{v} = \frac{1}{3}$. The solution given here also addresses this question.

Let us introduce a coordinate system with the origin at the center of the original square $ABCD$ and axes parallel to its sides. Let's put the side of the square $ABCD$ equal to 1 and assume that the maximum speed of the gangster is $v = 1$ (we only care about the ratio $u/v$). The points at which the policeman and the gangster are located are denoted by $\Pi(x_\pi, y_\pi)$ and $\Gamma(x_\pi, y_\pi)$, respectively.

a) Let $u > \frac{1}{3}$. Let us prove that then the policeman will reach his goal (that is, he will be on the same side of the square with the gangster; we will say that in this case he will negotiate (or LOB the gangster).

Let us denote by $\Gamma'$ the point with coordinates $\left(\frac{1}{3}x_\Gamma, \frac{1}{3}y_\Gamma\right)$; it is obvious that if point $\Gamma$ moves along the contour of the square $ABCD$ with a maximum speed $v = 1$, then $\Gamma'$ moves along the contour of a similar square $A'B'C'D'$ (Fig. 15) with a maximum speed $v_{\Gamma'} = \frac{1}{3}$.

The policeman will LOB the gangster in several stages.

First stage. The policeman achieves his goal (that is, he will end up with the gangster on the same side of the square; we will say that in this case he will negotiate (or LOB the gangster).

Let us denote by $\Gamma'$ the point with coordinates $\left(\frac{1}{3}x_\Gamma, \frac{1}{3}y_\Gamma\right)$; it is obvious that if the point $\Gamma$ moves along the contour of a similar square $A'B'C'D'$ (Fig. 15) with a maximum speed $v_{\Gamma'} = \frac{1}{3}$.

The first stage from his second stage, the policeman must reach any speed not exceeding $\sqrt{u^2 - \left(\frac{1}{3}v\right)^2}$, (Fig. 16). We also require that at the second stage the policeman moves towards side $AB$ with the maximum speed along axis $Oy$. There are two possible cases:

1) $\Gamma$ remains at $AB$ all the time. Then $\Pi$ through some.deviget $AB$, and therefore the gangster will be “caught”; solution problem.
2) At some point $\Gamma$ satisfies the boundary $AB$ (we assume the points $B$) begins.

Third stage. By the beginning of this stage, points $G$ and $B$ coincide, and point $\Pi$ is located from each side $AB$ and $BC$ at a distance of no more than $\frac{1}{3}$. At the third stage, the policeman must approach with maximum speed perpendicular to the side on which the gangster is located (if $\Gamma = B$, then it does not matter which one - side $AB$ or side $BC$).

To run from point $B$ to point $A$ or to point $C$, the gangster will be hit in one unit of time, and for the policeman to reach the corresponding side ($AB$ or $BC$), the hit will be strictly less than one unit of time. Consequently, the policeman "caught" the gangster on one of the sides $AB$ or $BC$. Thus it should be disassembled.

⟦folio 26⟧

6) Let now $u < \frac{1}{3}$. Let us show that in this case the gangster can choose such a stramecia in which the policeman will not be able to “catch up” with him.

It is clear that if $u = \frac{1}{3}$ (recall that $v = 1$), then it will be more difficult for the gangster to “escape” from the policeman. Let's see what happens in this, the most unfavorable case for a gangster.

In the center of the square $ABCD$ we construct a square $A'B'C'D'$, similar to the original one with a similarity coefficient $k = \frac{1}{3}$; draw lines $A_2B_3$, $A_1B_4$, $D_4C_1$, $D_3C_2$, parallel sides $AB$, and lines $A_3D_2$, $A_4D_1$, $B_1C_4$, $B_2C_3$, parallel $BC$, so that $AA_3 = A_3A_4 = AA_2 = A_2A_1 = B_1B_2 = B_2B = D_4D_3 = D_3D$ (Fig.17).

Let at the very beginning the gangster G be in the middle of the side $AB$, and the policeman P be above the line $A_2B_3$. Let's draw two auxiliary lines $\hat{A}\hat{B}$ and $\hat{A}\hat{B}$, parallel to $AB$, so that policeman P is above the line $\hat{A}\hat{B}$ (Fig. 18).

Let us show that we can always choose a non-tortoic segment $KM$ so that it contains the midpoint of side $AB$ and so that from any of its points the gangster G would have time to add $A$ or $B$ to any of the vertices faster than the policeman P will have time to add from $\hat{A}\hat{B}$ to $AB$. In fact, the distance from $\hat{A}\hat{B}$ to $AB$ is greater than $1/6$; therefore, P will hit more than $1/2$ time units in order to add from $\hat{A}\hat{B}$ to $AB$; This means that for the segment $KM$ we can choose, for example, a segment symmetrical with respect to the middle of the side $AB$, with a length strictly less than $2\left(3|A\hat{A}| - \frac{1}{2}\right)$.

Let us now describe the strameccia of the gangster G. While policeman P is above the straight line $\hat{A}\hat{B}$, the gangster remains in place - in the middle $AB$. Sooner or later the policeman will be available $\hat{A}\hat{B}$ (before he never appears the gangster); In this case, two situations are possible:

(1) either $x_{\Pi} \neq \frac{1}{3}x_{\Gamma}$,

(2) or $x_{\Pi} = \frac{1}{3}x_{\Gamma}$.

If case (2) occurs, then G begins to run at maximum speed along the segment $KM$ from the right to the left. If at the same time $x_{\Pi} = \frac{1}{3}x_{\Gamma}$ all the time, then the horizontal component of the policeman’s speed must be equal to $\frac{1}{3}$ the horizontal component of the gangster’s speed; and since the latter is equal to 1, then, therefore, the horizontal component of the velocity P must be equal to $\frac{1}{3}$, that is, $u = \frac{1}{3}x_{\Gamma}$.

Let's assume that the gangster notices that the policeman has left the straight line $\hat{A}\hat{B}$, reaching quickly, for example, even before the policeman reaches the straight line $\hat{A}\hat{B}$.

So, now we have $x_{\Pi} \neq \frac{1}{3}x_{\Gamma}$, $\Pi$ - above the straight line $\hat{A}\hat{B}$, $\Gamma$ - on the segment $KM$.

The further behavior of $G$ should be as follows. Suppose, without loss of generality, that $x_{\Pi} < \frac{1}{3}x_{\Gamma}$; then $\Gamma$ moves to the right with maximum speed

⟦folio 27⟧

to point $B$ (or if $x_{\Pi} > \frac{1}{3} x_{\Gamma}$, then it should move higher - to point $A$). Due to the choice of segment $KM$, the policeman will not have time to reach straight line $AB$ in the time it takes the gangster to reach point $B$; this means P will not be able to understand $\Gamma$ on the side $AB$. Further, since we assumed that at the “initial” moment $x_{\Pi} < \frac{1}{3} x_{\Gamma}$ and $\Gamma$ move to the right at a speed of $3 u$, then the inequality $x_{\Pi} < \frac{1}{3} x_{\Gamma}$ will hold all the time. Therefore, when $\Gamma$ reaches point $B$, then P will be to the left of straight line $B_1C_4$ (Fig. 19).

Now $\Gamma$ runs at maximum speed along side $BC$ towards its middle. It takes $\Gamma$ $1/2$ time units to reach the middle; During this time, P will travel a path of length no more than $1/6$, and therefore will not have time to reach the straight line $B_2C_3$.

So, we have arrived at the already considered configuration: $\Gamma$ is in the middle of side $BC$, and $\Pi$ is to the left of straight line $B_2C_3$. In this case, the point $\Gamma$ from the middle of side $AB$ moved to the middle of side $BC$; This means that at least 1 unit of time has passed. Further behavior of $\Gamma$ is similar to that described above. It is absolutely inconceivable that with such a gangster’s strategy, the policeman will not “catch” him in any finite amount of time.

Thus, we know what the behavior of a gangster should be in the “worst” case: $u = \frac{1}{3}$; it is clear that for $u < \frac{1}{3}$ the strategy indicated for it will be all the more correct.

G. A. Galperin, A. B. Khodulyev

**M230. Proof that from any convex equilateral (but not necessarily regular) rectangle one can cut a regular triangle, one of the sides of which coincides with the side of the rectangle (Fig. 20).

Fig. 20.

Suppose that for some equilateral convex rectangle $ABCDE$ with sides equal to one, the statement of the problem is false. We can assume that on the largest of the diagonals is AD, that the points $A$ and $D$ lie on the horizontal line (D is to the right of $A$), the points $B$ and $C$ are in its upper half-plane, and $C$ is not closer to the line $AD$ than $B$ (Fig.21). It is clear that $1 < |AD| < |AE| + |ED| = 2$.

Since in triangles $ABD$ and $ACD$ side $AD$ is the largest, angles $ABD$ and $ACD$, and even more so $ABC$ and $BCD$ are increasingly larger than $60^\circ$, therefore, equilateral triangles built on sides $AB$, $BC$ and $CD$ must be intersected by the segment $AD$ (after all, each of them, by assumption, is intersected by the contour of a rectangle, but these triangles cannot intersect with the segments $AB$, $BC$ and $CD$). Thus, angles $BAD$ and $CDA$ are smaller than $60^\circ$.

Let us mark the points $B_1$, $C_1$ on the segment $AD$ and the point $C_3$ on its continuation, for which $|AB_1| = |C_1D| = |B_1C_3| = 1$, and construct equilateral triangles $AB_1B_2$, $C_1DC_2$, $B_1C_3C_4$ (Fig. 22) in the upper half-plane. Point $B$ should lie somewhere on arc $B_1B_2$ with center $A$, point $C$ - on arc $C_1C_2$ with center $D$. On the other hand, since $|BC| = 1$ and $C$ lie not lower than $B$ (but not higher than at a distance $\sqrt{3}/2$ from the line $AD$), then the points $C$ should lie to the right of the arc $C_3C_4$ with center $B_1$. But from (*)

⟦folio 28⟧

Fig. 22.

it follows that $\triangle C_1DC_2$ is located to the left of $\triangle B_1C_3C_4$, therefore arc $C_1C_2$ is located to the left of arc $C_3C_4$. We got a contradiction. This means that angles $BAD$ and $CDA$ cannot be simultaneously less than $60^\circ$, and there is at least one equilateral triangle (constructed either on the side $AB$, or on $BC$, or on $CD$), which will not be intersected by the contour of the pentagon.

Of the various solutions problem M230, we chose this one because it is generalizable and allows us to prove the statement problem M230 for any equilateral convex $(2n+1)$-gon.

N. B. Vasiliev

F233. During a high-speed descent, the skier slides down the slope ($\varphi=45^\circ$), without optimizing with poles. Ski-to-snow time coefficient $k=0,1$. The force of air resistance is proportional to the square of the skier's speed $F_c=\alpha v^2$, where $\alpha$ is a constant equal to $0,7$ and $(m/c)^2$. What is the maximum speed that a skier can develop if his mass is 70 kg?

Let us consider the movement of a skier, projecting all the forces acting on him on the coordinate axis, directed parallel

Fig. 23.

the inclined plane that forms the slope, and perpendicular to it (Fig. 23).

Since the skier does not move along the $Y$ axis, then

$$N-mg\cos\varphi=0.$$ (1)

The projection of the gravity force on the axis $X$, equal to $mg\sin\varphi$, and the friction force $F_{TP}=kN$ does not depend on the speed of the skier, and the air resistance force $F_c=\alpha v^2$ returns with increasing speed of the skier. Therefore, as the speed of the skier increases, it will increase, and the skier will move evenly. The speed $v_{max}$ at which this happens is the skier's maximum speed.

Let us write the equation for the uniform motion of a skier along the $X$ axis:

$$mg\sin\varphi-kN-\alpha v_{max}^2=0.$$ (2)

From (1) and (2) we find

$$v_{max}=\sqrt{\frac{mg}{\alpha}}(\sin\varphi-k\cos\varphi)=$$

$$=\sqrt{\frac{70\cdot9,8}{0,7}\left(\frac{\sqrt{2}}{2}-0,1\cdot\frac{\sqrt{2}}{2}\right)}\approx 25(m/c).$$

F234. The exploding chamber is filled with a mixture of methane and oxygen at room temperature and a pressure of $p_0=760$ mm rm. cm. The partial pressures of methane and oxygen are the same. After the chamber is thermalized, an explosion occurs in it. The name is given to the pressure inside the chamber after cooling the sorted products to the first initial temperature, at which the pressure of saturated water vapor is $p_H=17$ mm rm. cm.

Let us first write down the explosion reaction equation:

$$CH_4+2O_2=CO_2+2H_2O.$$

From this equation it can be seen that each molecule creates two moles of oxygen. The reaction results in 1 mol of carbon dioxide and 2 mol of water.

Before the explosion, the partial pressures of methane and oxygen were the same and equal to $\frac{1}{2}p_0$. According to the equation of gas state, gas pressure is proportional to the number of moles of gas. Then, from the equivalence of the partial pressures of methane and oxygen, it follows that the vessels contain the same number of moles of gases. Consequently, during an explosion, all the oxygen will react with methane, and half of the first initial amount of methane remains in the vessels, which has not reacted.

Thus, after the explosion, the vessels will contain methane, carbon dioxide and water,

⟦folio 29⟧

and the total pressure will be equal to the sum of the partial pressures of methane, carbon dioxide and water vapor:

$$p = p_{\text{CH}_4} + p_{\text{CO}_2} + p_{\text{H}_2}\text{O}.$$

After cooling the mixture of gases to the original temperature, the partial pressure left of methane will be equal to half of its original partial pressure, that is, $\frac{1}{4} p_0$.

The number of moles of carbon dioxide in the vessel is equal to the number of moles of methane that has evaporated, and therefore the remaining methane. Therefore, the partial pressure of carbon dioxide will also be equal to $\frac{1}{4} p_0$.

Now let's find out what the water vapor pressure is. Let us assume that all water formed during the explosion is in a vapor state. Since the number of moles of water is twice the number of moles of methane remaining in the vessel, the partial pressure of water vapor must be equal to $\frac{1}{2} p_0 = 380 \text{ mm} \cdot \text{cm}$. This, however, is greater than the saturated vapor pressure of water. Consequently, more of the water vapor will condense during cooling, and the partial pressure of saturated water vapor in the vessel will be equal to $p_{\text{H}} = 17 \text{ mm} \cdot \text{cm}$.

Finally, after the explosion and cooling of the mixture, the total pressure in the vessel

$$p = p_{\text{CH}_4} + p_{\text{CO}_2} + p_{\text{H}_2}\text{O} = \frac{1}{4} p_0 + \frac{1}{4} p_0 + p_{\text{H}} = 397 \text{ mm} \cdot \text{cm}$$

In our solution, we neglected the fact that as a result of water condensation, the volume occupied by the gas decreased. This is acceptable since the volume of liquid water is small compared to the volume of vapor.

F235. A small drop of water falls in the air at a constant speed due to the fact that it is acted upon by the air force caused by the collision of air molecules with the drop. How does the rate at which a drop spreads change as the air temperature increases?

Neglect the evaporation of the drops.

A drop of water moving in the air is affected by two forces: gravity and drag. If these forces are equal in magnitude, then the drop moves at a constant speed. The magnitude of this speed obviously depends on the mass of the drop and on the drag force caused by the collision of air molecules with the drop. When the air temperature changes, the speed of thermal movement of molecules changes. Therefore, it is natural to expect that the speed of the drop will also change.

Now we carry out quantitative calculations.

Let's consider the collision of air molecules with a drop and find how the resistance force depends on the speed of thermal motion of the molecules. In this case we will assume that:

1) collisions of molecules with a drop are elastic;
2) molecules colliding with a drop move either vertically upward or vertically downward;
3) the speeds of all molecules are the same.

These assumptions simplify the calculations, but they do not change the real picture of the phenomenon.

First, let us consider the collision of a parallel beam of a part with a fixed wall. Let us denote the area of ​​the transverse section of the beam as $s$, the particle speed as $u$, and the number of particles per unit volume as $n$. In time $\Delta t$, those molecules that are located from it at a distance no greater than $u \Delta t$ form a sink stacker. The number of such particles is $su \Delta tn_0$ (m$_0$ is the mass of one particle), and the momentum is $mu = su^2 \Delta tn_0$.

After elastic collision, the momentum of the part is reversed, so the change in momentum is $\Delta (mu) = 2mu$.

This means that the particles from the side of the wall and the wall from the side of the particles are acted upon by average forces equal in absolute value.

$$F = \frac{\Delta (mu)}{\Delta t} = 2su^2 nm_0$$

Thus, the force acting on the wall is proportional to the square of the velocity of the part of the relative wall.

Now let's calculate the drag force for the movement of the drop. Let's denote the speed of the drop $v$, and the speed of thermal movement of air molecules $u$. Molecules incident on a drop from above move relative to the drop with a speed of $u + v$, and molecules incident on a drop from above move with a speed of $u - v$. Therefore, the force $F_1 = k (u + v)^2$ acts on the drop from below, and $F_2 = k (u - v)^2$ from above (k is the coefficient of proportionality, does not depend on the speeds $v$ and $u$).

Resultant force

$$F = F_1 - F_2 = 4kuv$$

So, the drag force acting on the drop is proportional to the speed $u$ and $v$. In addition to this force, the gravity force $Mg$ also acts on the drop. With uniform movement

$$Mg = 4kuv,$$

where

$$v = \frac{Mg}{4ku}.$$

⟦folio 30⟧

That is, the speed of a drop falling is inversely proportional to the thermal speed of movement of air molecules. But, as you know, $u \sim \sqrt{T}$. Hence,

$$v \sim \frac{1}{\sqrt{T}}.$$

Therefore, as the air temperature increases, the droplet falling speed will decrease.

F236. Determine the period of vibration of a polar molecule in a uniform electric field directed toward $E=300$ v/cm. A polar molecule can be represented as a rigid dumbbell of length $l(l=10^{-8} \text{ cm})$, at the ends of the comoro there are two material points of mass $m(m=10^{-24} \text{ e})$, non-existence charges $+e$ and $-e$ respectively ($e=1,6 \cdot 10^{-19} \text{ K})$.

In a stable equilibrium position, the molecule is located along the field (Fig. 24). If it is taken out of this state, then a rotational moment arises, turning the molecule around its center of gravity. This moment is created by electric forces $F_1$ and $F_2$, acting on the charges from the electric field (Fig. 25).

If we consider the charges of each separately, we can say that electric forces for them play the role of restoring forces. Therefore, the charges oscillate like mathematical matrices of length $\frac{l}{2}$.

Let's use this analogy and write the vibration period of the molecule as follows:

$$T = 2\pi \sqrt{\frac{l}{2g'}}$$

where $g'$ is the acceleration that the electric field imparts to each charge. Since $g' = \frac{F_{эл}}{m}$ and $F_{эл} = eE$, then

$$g' = \frac{eE}{m}.$$

Poet finally

$$T = 2\pi \sqrt{\frac{l}{2g'}} = 2\pi \sqrt{\frac{lm}{2eE}} \approx 2 \cdot 10^{-11} \text{ c}.$$

In answering this question, let’s focus on the two most significant factors.

Firstly, the face of a person in a mass is illuminated much worse than the mass itself and the surrounding environment, looking from the mask and other objects. Therefore, the light reflected from the face is very weak compared to the light reflected from the mask and other objects. That is why, for an observer from the public, the face of the fencer in the mass is practically indistinguishable. The athlete himself, on the contrary, sees brightly lit objects around him well against the background of weak light reflected inside a third-party wired mask. In addition, the image of the mask in the athlete’s eyes turns out to be very blurry (unfocused), since the mask is located too close to the eye.

The same reason why stars cannot be seen with the naked eye during the day: sunlight, scattered by the atmosphere, is much stronger than light.

Secondly, since the wire mesh is located close to the athlete's face, it covers quite a large part of the face from the observer. At the same time, this mask hardly interferes with sportsmen.

In conclusion, let’s consider another similar problem - why during the day from the street nothing can be seen inside the room if you look through a window covered with mesh fabric? Obvious in this case is the fact that the strongly illuminated canopy is poorly illuminated. However, it will be much worse to see if the rooms are exposed to direct sunlight and the walls of the room have a good reflector of light - then the canopy is well lit from the inside. In order to clearly see what is happening on the street, in this case it is necessary to come close to the window.

I.Sh. Slovodechky
