---
id: 1974-12-resheniya-zadach-m256-m260-f269-f272-48b2f833
issue: kvant_1974_12
year: 1974
number: "12"
title: Solutions to problems M256—M260; F269—F272
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 48
page_last: 56
page_labels: 46-54
tag: 2N1O
lang: en
source: kvant_digital
extraction: vision
content_sha256: 38eb14865e4e3452ffd95b2724659d1e6093ada135e2d0c81813ceeef5d3107e
prompt_sha256: draft-1
translated_from: content/ru/1974/12/articles/13_resheniya-zadach-m256-m260-f269-f272-48b2f833.md
source_content_sha256: 565b24fdb5a1701f5b41bbcbaa85db540ea9bad2fc00dfcb6f9c31a433eb4996
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 46⟧

Problem solutions

M256—M260; F269—F272

M256. A polygon is described around a circle. The points of contact of its sides with the circle are the vertices of the second polygon inscribed in the circle. Prove that the product of the distances from an arbitrary point M of the circle do sides of one polygon is equal to the product of the distances from the same point M do sides of the second.

(Under consideration from the point M do of the side, the distance to the straight line on which this side lies is trampled.)

Let us first prove this lemma. If M, P and Q are three arbitrary points of a given circle, then the distance |MK| from point M to straight line PQ is equal to the geometric mean of distances |ML| and |MN| from M to tangents drawn at points P and Q:

$$|MK|^2 = |ML| \cdot |MN|.$$ (1)

Let's imagine that points P and Q are fixed, and M moves around the circle. For any position *) angles

*) Below we assume that M does not coincide with P or Q (in the expressed case, equality (1) is very strong - both of its parts are equal to 0).

$$\Rightarrow MPL \text{ и } \Rightarrow MQK \text{ (не превысющие, разумеется, } 90^\circ \text{) равны по величины — каждый из них изменяется положной дуги PM (не превысшейшей положружности), поэтому прямогольные треугольники MPL и MQK подобны и}$$

$$\frac{|ML|}{|MK|} = \frac{|MP|}{|MQ|}.$$ (2)

(This equality, very indo, also holds in the case when right-angled triangles degenerate into segments - at this moment the point M is diametrically opposite to P.) In the same way it is proved that $\triangle MQN \sim \triangle MPK$:

$$\frac{|MN|}{|MK|} = \frac{|MQ|}{|MP|}.$$ (3)

From (2) and (3) follows (1).

Let us now prove the statement of the problem. To do this, apply lemmy to the point M of the circle and to each side PQ of the inscribed polygon, and then overcome all equalities of the form (1).

The shortcomings in the solutions sent by readers were mainly due to the fact that in the proof of Lem we did not take into account all possible cases of the location of points P, Q and M on the circle (some of them are shown in Fig. 1, a, b, c). Our decision uses reasoning that covers all cases at once.

M257. For what natural n ≥ 2 does the inequality

$$x_1^2 + x_2^2 + \dots + x_n^2 \geq p \left( x_1 x_2 + x_2 x_3 + \dots + x_{n-1} x_n \right)$$

holds for any real numbers x1, x2, ..., xn, if a) p = 1; 6) p = 4/3; b) p = 6/5?

Answer. a) for all n; 6) for n ≤ 3; b) for n ≤ 4.

Fig. 1.

⟦folio 47⟧

Fig. 2. The closer $p$ is to one, the closer the hyperbola is to the circle and the more steps the staircase has.

Note that if we put $x_1^2 + x_2^2 + \dots + x_n^2 - 1 + x_n^2 - px_1x_2 - px_2x_3 - \dots - px_n - 1x_n \geq 0$ (*) in the inequality

the last few variables $x_k, x_{k+1}, \dots, x_n$ are equal to zero, then we obtain a similar inequality corresponding to the smaller one $n$. It follows that if (*) holds (for all $x_1, x_2, \dots, x_n$) for some $n$, then it holds for smaller $n$. Thus, for every fixed $p$ there is an integer $N(p) \geq 2$ such that (*) holds for $n < N(p)$ and fails (for some $x_1, x_2, \dots, x_n$) for $n \geq N(p)$; it is also possible that (*) holds for all $n$ (in this case we can assume that $N(p) = \infty$).

The last case occurs at $p = 1$. Indeed, in this case (*) is equivalent to the very strong inequality

$$x_1^2 + (x_1 - x_2)^2 + (x_2 - x_3)^2 + \dots + (x_{n-1} - x_n)^2 + x_n^2 \geq 0.$$

Let $p = \frac{4}{3}$. Then for $n = 3$ (*) is equivalent to the inequality

$$(3x_1 - 2x_2)^2 + x_2^2 + (2x_2 - 3x_3)^2 \geq 0,$$

and for $n = 4$ inequality (*) is violated, for example, when $x_1 = x_4 = 2, x_2 = x_3 = 3$ (for $n = 4$ inequality (*) is equivalent to:

$$(3x_1 - 2x_2)^2 - x_2^2 + 6(x_2 - x_3)^2 - x_3^2 + (2x_3 - 3x_4)^2 \geq 0;$$

This is where our example comes from.)

Let $p = \frac{4}{5}$. Then for $n = 4$ (*) is equivalent to the inequality

$$(5x_1 - 3x_2)^2 + x_2^2 + 15(x_2 - x_3)^2 + x_3^2 + (3x_3 - 5x_4)^2 \geq 0,$$

and for $n = 5$ it is an inequality, for example, when $x_1 = x_5 = 9, x_2 = x_4 = 15, x_3 = 16$ (this example arises naturally if we transform (*) to the form

$$16(5x_1 - 3x_2)^2 + (16x_2 - 15x_3)^2 - 50x_3^2 + (15x_3 - 16x_4)^2 + 16(3x_4 - 5x_5)^2 \geq 0).$$

Discuss now how to answer the problem question for arbitrary $p > 0$. It is easy to show that $N(p) = \infty$ for any $p \in [0, 1]$ and $N(p)$ is finite for every $p > 1$, and $N(p) = 2$ for $p > 2$. In principle, for each $p > 1$ you can find $N(p)$ by transforming the left side (*) to a sum of squares (and it is not at all necessary to worry about the symmetric formula and ensuring that the coefficients are integer or rational; above we did this in order to write the solution shorter). For example, you can reduce (*) to the form

$$(s_1x_1 - t_1x_2)^2 + (s_2x_2 - t_2x_3)^2 + \dots + (s_{n-1}x_{n-1} - t_{n-1}x_n)^2 + r_nx_n^2,$$

consistently believing

$$t_k = p/2s_k, s_{k+1} = \sqrt{1 - t_k^2}$$

($s_1 = 1, k = 1, 2, \dots$). Then $r_n = s_n^2 \geq 0$ at $n < N(p)$ and $r_n < 0$ at $n = N(p)$. Thus, $N(p) - 1$ (the largest $n$ for which (*) still holds) is equal to the number of steps of the “ladder” contained between the graphs $s^2 + t^2 = 1$, $st = p/2$ and starting at the point $s = 1$, $t = 0$, (Fig. 2). Let $p_k$ be the value of $p$ at which the staircase is symmetrine relative to the bisserrissa $s = t$ (ends at the point $s = 0$, $t = 1$) and contains $k$ steps; it is clear that the sequence $p_1 = 2 > p_2 > p_3 > \dots$ tends to 1 and $N(p) = k + 1$ as $p_{k-1} \geq p > p_k$.

It is not difficult to prove that $p_2 = \sqrt{2}$, but the following $p_k$ is already found from cumbersome equations related to high-level algebraic equations.

⟦folio 48⟧

Let's solve problem M257, we estimated $p_2$,

$$p_3 \text{ и } p_4: \text{поскольку } N\left(\frac{4}{3}\right)=4, N\left(\frac{6}{5}\right)=5, \text{ то } p_2>\frac{4}{3}>p_3>\frac{6}{5}>p_4.$$

N. B. Vasiliev

**M258.** Three points $K, L, N$ are given on the plane. It is also known that the overweight object is convex and that the midpoints of some of its three sides lie at the given points $K, L, N$. Specifying a set of points that can hit:

a) the middle of the back side;
b) the top of the emnoy wormhole.

a) Note that if the midpoints of the sides are connected in series in a quadrilateral, a parallelogram is formed. To prove this well-known fact, it is enough to examine one of the diagonals of this quadrilateral (Fig. 3): in the resulting triangles, the two segments connecting the midpoints of the side are midlines, and, therefore, they are parallel to the drawn diagonal and are equal to half.

From the remark made, it follows that the middle of the vertex side - point $M$ - is the vertex of the parallelogram, the other vertices of which are $K, L$ and $N$. It is easy to see that the set of points in which the point $M$ can fall consists of three points $\{M_1, M_2, M_3\}$ - the vertices of a triangle, the middle lines of which are the sides of the triangle $KLN$ (Fig. 4).

6) Consider one of the parallelograms, for example, $KLM_1N$. Where can the vertices of a convex quadrilateral be located if the midpoints of the side are at points $K, L, M_1$ and $N$? Recall that a polygon is convex if it lies on one side of each straight line that is a continuation of its side. Therefore, the vertices of the quadrilateral can only lie in half-polls between the extensions of the opposite sides of the parallelogram (Fig. 5, a). Using the fact that the two adjacent vertices of the quadrilateral are symmetrical relative to the vertex of the parallelogram, we find the set of points at which the vertices of the quadrilateral can appear - it consists of four parallelograms obtained from $KLM_1N$ by parallel translation and having a common side with it (Fig. 5, 6); you also need to make sure that any point of this “cross” can serve as the vertex of a quadrilateral.

If we now consider two more points $M_2$ and $M_3$, in which the middle of the worm side of the polygon may be, and take the lunch triangle corresponding to $M_1, M_2$ and $M_3$, then we will finally get a polygon highlighted by a trihovka at figure 6; it consists of 15 triangles congruent to $\Delta KLN$.

A. P. Savin

**M259.** Let us draw a quartet of squares on checkered paper, the centers of which lie at the vertices of the rectangle from the side, with parallel lines (For example, on figure 7 three squares are drawn).

What is the maximum number of quartems that do not have common cells that can be placed:

a) squared $5 \times 5$?
b) in a rectangle of $m \times n$ cells?

a) Five quartets can be arranged in the square $5 \times 5$ (see Fig. 8). The big heel of quartets cannot be placed in it, since $5 \times 5 = 25$ cells at least five cells - one in each row - will not fit into the squares.

6) If $m$ and $n$ are even, then it is very likely that $mn/4$ cells can be placed in the rectangle $m \times n$.

⟦folio 49⟧

Fig. 7. Fig. 8.

If $m$ is even and $n$ is odd, then $m(n-1)/4$ quartets can be placed (a similar formula holds for odd $m$ and even $n$).

If $m$ and $n$ are odd, then two cases must be considered. (We will assume that $m \geq n$).

1) $n = 4k + 1$. It is clear that in this case it is possible to cover no more than $mn - (m-n) - n = m(n-1)$ cells with quartets; figure 9 shows how to do this: the diagonal is removed from the square $n \times n$ (remember that $n$ is odd), and the quartets are placed in the same way as it was done on figure 8 in the square $5 \times 5$; from the rectangular $(m-n) \times n$ $(m-n)$ is already even) the bottom line will be thrown out - then in the rectangular $k \times l = (m-n) \times (n-1)$ and $k$ and $l$ are even, and how to mix the quartets is very indo. In total - $m(n-1)/4$ quartet.

2) $n = 4k + 3$. In this case, it is not possible to cover $m(n-1)$ cells with quartets, since the number $m(n-1)$ is not divisible by 4. But $m(n-1) - 2$ cells can already be covered - exactly how is shown in figure 10 - $m + 2$ shaded cells are thrown out: $n-2$ - on the diagonal of the square $(n-2) \times (n-2)$, $(m-n+2)$ are on the right side of the bottom line of the original rectangle, and two cells are in the upper left corner (then $n-3$ is divided by 4, $m-n+2$ and $n-1$ are both even).

A. A. Gritsoryan

M260. The circle is divided by the relics $A_1, A_2, \dots, A_n$ into $n$ equal parts, each of which is painted a certain color. Two arcs (with ends in the relics of the division) are called identically colored if, with some repetition of the circle, one of their stripes, including the color of each part, coincides with the arc. (For example, on figure 11 arcs $A_2A_6$ and $A_6A_{10}$ are equally colored.) Prove that if for each power of partition $A_i$ one can specify two disjoint

⟦folio 50⟧

start with the fact that the arcs α and β are equally colored. In what follows, identically colored arcs will be called equal. Through |α| let's denote the arc length α. We use the clockwise direction of traversing the circle as positive (this allows us to naturally spread the beginnings and ends of the arc). Let βγ denote the arc that results if we attach the beginning of the arc γ to the end of arc β (Fig. 12).

A symmetric arc is an arc on which equal smaller arcs lie at the beginning and end, that is, α is a symmetric arc if there are arcs β, γ and δ such that α = βγ = δβ (Fig. 13).

According to the condition, for each split point you can specify a pair of non-intersecting equal arcs with a common end at this point. Generally speaking, there may be several such pairs of arcs for each point—try to give an example. Therefore, let us clarify exactly which pair we will consider: we associate to each split point that pair of non-intersecting equal arcs (with a common end), the arcs of which have a minimum length; In what follows, we will consider only such pairs.

We will need the following

Lemma 1. If the arc α is a minimal arc, then it is not symmetric (prove this lemma yourself).

Suppose that among all minimal pairs of arcs corresponding to different points, the split pair corresponding to point A has the maximum length, and let the ends of the arc of this pair different from A—points B and C (see Fig. 14, a)—do not coincide.

The central point of the proof is

Main lemma. If you cut out arcs BA from a circle and “glue” point A to point B, then the new circle will again have the property that for any split point you can specify a pair of disjoint equal arcs with a common end at this point.

Using this lemma, the “periodicity” of the color is proved by induction on the number of points of the partition. We will carry out induction later, but now we outline the proof of the main lemma.

Let us denote the arcs BA and AC by the letter α. Let's consider part of the new circle obtained from the old one after cutting out arc BA and “gluing” point A to point B (see Fig. 14, b); Let us denote the points of division of the new circle by letters with dashes.

Let M' be some point split on the new circle that does not lie on the arc A'C', and let M be the corresponding point on the old circle. Point M corresponds to the minimum pair of equals (for example, arcs v - see Fig. 14, a) for LM and MK. By the conditions of Lemma |α| ≥ |v|, therefore, the arc MK lies entirely on the arc MA.

But the arc MA is equal to the arc M'C'; this means that the arc v lies at the beginning of the arc M'C', that is, the point M' serves as its beginning. Reasoning in a similar way, let us construct along the arc LM an arc on a new circle equal to v with its end at point M'.

However, it could happen that the two constructed arcs (one with a beginning at point M', the other with an end at this point) intersect (Fig. 15). Let us show that this cannot actually happen.

Let us denote the arcs M'L', L'K' and K'M' (in a clockwise direction) by β, η and δ, respectively; then v = βη = ηδ, that is, v is a symmetric arc; but this contradicts Lemma 1, and therefore the arcs L'M' and M'K' do not intersect.

Thus, for points M' that do not lie on the arc A'C', everything is proven.

Let now the point M' lie on the arc A'C', and let, to determine |A'M'| ≤ |M'C'| (see Fig. 16, b). Then on the old circle the point M' corresponds to two points - we denote them by M and M1; point M lies on arc BA, point M1 on arc AC (Fig. 16, a). The case when arc MK (minimal arc v with origin at point M)

⟦folio 51⟧

Fig. 15.

does not intersect with the arc AC, is divided in the same way as the first one (when the point M' does not lie on A'C'). At figure 16, a, the most complex case is depicted, when the arcs MK and AC intersect. In this case (see notation figure 16, a) the following relations hold:

1) δαα = vvγ;
2) |δ| < |v|, |γ| < |α|.

Lemma 2. If correspondence 1) and 2) holds and if the duen v and α are non-isymetric, then there is a duen β such that α = βγ, v = γβ.

From this lemma it follows that the point K coincides with the point M₁ and δ = γ (see Fig. 17, a.).

Using Lemma 2 and the fact that |A'M'| ≤ |M'C'|, it is easy to show that the point M₁ corresponds to a pair of arcs equal to the arc v = γβ, which implies that C is the beginning of the arc equal to β (Fig. 17, a); therefore, the point M' corresponds to a pair of arcs equal to γβ (Fig. 17, b).

This concludes the proof of the Main Lemma. It follows, in part, that the length of the maximum pair of arcs on a new circle does not exceed the length

Fig. 17.

maximum pair of arcs on the old circle.

Let's move on to proving the periodicity of coloring. Let us carry out induction on the number n of points of partition. For n = 2 this is obvious. Let us assume that we have proven periodicity for n ≤ k, and we will prove it for n = k + 1. Let the pair of arcs with the maximum length correspond to the definition of point A. If the entire circle is the circumference of this pair of arcs, then the induction proposition is true. If not, then we will express one of these arcs and glue the ends together. By virtue of the Main Lemma, the new circle satisfies the conditions of the problem, and the partition point on it is smaller than on the old one; therefore, by the induction hypothesis, the coloring of the new circle is periodic; and the length of the period does not exceed the length of the cut arc - let us denote it by α.

Lemma 3. If |α| ≥ 0, α is a non-isymmetric duea u αα...αβ = v ... v, mo |α| = |v|.

From this lemma it follows that the length of the period is equal to α, and therefore the new circle has

⟦folio 52⟧

View shown at figure 18. The old circle will be obtained if we cut the new one at the point $A'$ and insert an arc $\alpha$; It is clear that this operation will not disrupt the periodicity of painting. The proof is complete.

G. A. Gurevits

F269. A mathematical matrix, which consists of a soft metal ball of mass $m$ and a thin wire of nim and length $l$, performs a small oscillation in a horizontal uniform magnetic field with induction $B$, directed perpendicular to the plane of oscillation of the matrix. The maximum angle at which the matrix deviates from the vertical is $\alpha_0$. How will this angle change if, at the moment when the matrix passes the equilibrium position, a capacitor with a thickness of $C$ (Fig. 19) is connected to it using dental wires, and during the contact time, which is very short, the capacitor is charged in a stripe.

Since the conducting thread of the matrix moves in a magnetic field, a certain potential difference arises at the ends of the thread. Thanks to this, when a capacitor is connected to the matrix, current will flow through the circuit and the capacitor will charge. In this case, part of the energy of the matrix $W_M$ will turn into the energy of the capacitor $W_K$ and part will be released in the form of heat in the wires. The vibration energy of the matrix is ​​related to the maximum angle of matrix deposition from the vertical. Therefore, we will first find the new energy of the matrix $W_M'$, and then the maximum angle $\alpha_1$.

From the law of conservation of energy it follows that

$$W_M = W_M' + W_K + Q.$$

Let the direction at the ends of the matrix thread when passing through the equilibrium position be equal to $U$. Since the contact time with the capacitor is very short, we can assume that the direction does not change during this time. Then the direction to the capacitor after charging it

$$W_M = mgl(1 - \cos \alpha_0)$$

And

$$W_M' = mgl(1 - \cos \alpha_1).$$

Pozumu

$$mgl(1 - \cos \alpha_1) = mgl(1 - \cos \alpha_0) - CU^2.$$ (1)

In order to find $\alpha_1$, we need to calculate $U$. Let's do this. The electron, which is located at point $A$ at a distance $x$ from the suspension point of the matrix (Fig. 20), is acted upon by the Lorentz force

$$F_\pi = evB = e\omega xB,$$

where $v$ is linear and $\omega$ is the angular velocity of point $A$ as the matrix passes through the equilibrium position. Under the influence of the Lorentz force, free electrons will mix downwards (we assume that the induction vector in the magnetic field is directed beyond the drawing) until the resulting electric field prevents this. Thus,

$$F_\pi = F_{\text{эл}},$$

or

$$e\omega xB = eE,$$

whence $E = \omega Bx$. That is, the field direction linearly depends on $x$ (Fig. 21).

⟦folio 53⟧

Fig. 21.

As we know, the work done by a force is always numerically equal to the area of ​​the figure under the graph of the force versus coordinates. The potential difference at the ends of the thread is the work done to cross a unit positive charge along the thread, and $E$ is the force acting on this charge. Therefore, using the graph shown in figure 21, we find

$$U = \frac{1}{2} l \omega l B = \frac{1}{2} \omega l^2 B.$$

Since $\omega = v/l$ and according to the law of conservation of energy

$$\frac{mv^2}{2} = mgl (1 - \cos \alpha_0),$$

That

$$\omega = \frac{1}{l} \sqrt{2gl (1 - \cos \alpha_0)}$$

And

$$U = \frac{1}{2} l B \sqrt{2gl (1 - \cos \alpha_0)}. \quad (2)$$

Substituting (2) into equality (1), we get

$$mgl (1 - \cos \alpha_1) = mgl (1 - \cos \alpha_0) - \frac{1}{2} Cl^3 B^2 g (1 - \cos \alpha_0).$$

From here

$$1 - \cos \alpha_1 = (1 - \cos \alpha_0) \left(1 - \frac{Cl^2 B^2}{2m}\right). \quad (3)$$

Since $1 - \cos \alpha = 2 \sin^2 \frac{\alpha}{2}$ and angles $\alpha_0$ and $\alpha_1$ are small, so $\sin \alpha \approx \alpha$, then

$$1 - \cos \alpha_1 \approx \frac{\alpha_1^2}{2} \quad \text{и} \quad 1 - \cos \alpha_0 \approx \frac{\alpha_0^2}{2}.$$

Therefore, we rewrite equality (3) in the form

$$\alpha_1^2 = \alpha_0^2 \left(1 - \frac{Cl^2 B^2}{2m}\right),$$

where

$$\alpha_1 = \alpha_0 \sqrt{1 - \frac{Cl^2 B^2}{2m}}.$$

F270. In a long test tube at a distance $l_1$ from the sealed end there is a short amount of mercury (Fig. 22). Mass of mercury $m$. At what speed $\omega$ should the test tube be moved around the vertical axis so that the mercury reaches the end of the test tube? The length of the test tube is $l$, the air temperature in the test tube does not change. Atmospheric pressure $p_0$.

In a stationary frame of reference, two forces act on a column of mercury in the horizontal direction: the atomospheric pressure force $F_1 = p_0 S$ ($S$ is the cross-sectional area of ​​the test tube) and the air pressure force in the test tube $F_2 = p S$ (see Fig. 22). The difference in these forces imparts to the mercury container a centripetal acceleration equal to $a = \omega^2 l$ (since the mercury is located at the edge of the test tube). Thus,

$$m \omega^2 l = p_0 S - p S.$$

Since the air temperature in the test tube does not change, then according to the Boyle-Mariotte law

$$p_0 Sl_1 = pSl,$$

where

$$p = p_0 \frac{l_1}{l}.$$

Then

$$m \omega^2 l = p_0 S \left(1 - \frac{l_1}{l}\right)$$

And

$$\omega = \sqrt{\frac{p_0 S (l - l_1)}{ml^2}}.$$

F271. Calculate the average density $\rho$ of electronic charges in the atomosphere, if it is known that the direction of the electronic field on the Earth’s surface is 100 $\cdot$ $m^{-1}$, and at a height of $h = 1,5$ km this directionality is increased to 25 $\cdot$ $m^{-1}$.

As is known, the direction of the electronic field of the internal thin sphere

⟦folio 54⟧

ric layer is zero, and outside this layer the directivity is the same as it would be if the entire charge of the layer were concentrated in its center. (This can be shown based on Coulomb's law and the principle of superposition.)

Let's divide the Earth and the Earth's atmosphere into thin spherical elephants. Then it is clear that on the surface of the Earth the direction of the electric field is equal to

$$E_0 = \frac{Q_3}{4\pi\varepsilon_0 R_3^2},$$

where $Q_3$ is the total charge of the Earth, $R_3$ is the radius of the Earth.

At an altitude $h$, the directionality of the electric field consists of the directionality of the field created by the charge $Q_3$ of the Earth, and from the directionality of the field created by the charge $Q_a$ of atmospheric layers with radii less than $R_3 + h$. That is

$$E_h = \frac{Q_3 + Q_a}{4\pi\varepsilon_0 (R_3 + h)^2}.$$

Because

$$Q_a V_a \rho = \left[ \frac{4}{3} \pi (R_3 + h)^3 - \frac{4}{3} \pi R_3^3 \right] \rho,$$

That

$$E_h = \frac{Q_3}{4\pi\varepsilon_0 (R_3 + h)^2} + \frac{\rho}{3\varepsilon_0} \left[ R_3 + h - \frac{R_3^3}{(R_3 + h)^2} \right].$$

The radius of the Earth $R_3$ is much greater than the height $h$, therefore in the denominator of formula (2) the sum $R_3 + h$ can be replaced by $R_3$. Then

$$E_h = \frac{Q_3}{4\pi\varepsilon_0 R_3^2} + \frac{h}{3\varepsilon_0} \rho = E_0 + \frac{h}{3\varepsilon_0} \rho.$$

From here

$$\rho = \frac{3\varepsilon_0 (E_h - E_0)}{h} = - \frac{3 \cdot 8,85 \cdot 10^{-12} \kappa^2 \cdot h^{-1} \cdot m^{-2} \cdot 75 \cdot \theta \cdot m^{-1}}{1500 \, m} \approx -1,3 \cdot 10^{-12} \kappa \cdot m^{-3}.$$

F272. A magnet of length $l$ (Fig. 23) is suspended from a wall inclined at an angle $\alpha$ to the vertical. The magnet was deflected in a plane perpendicular to the wall at a small angle $\beta$ from the vertical position and removed. The name of the vibrations of the magnet, if

$$\beta > \alpha \text{ и удар шарика о стенку абсолютино уррушей.}$$

If there were no walls, the magnet would perform a harmonic oscillation with an angular amplitude (maximum angle of deviation from the vertical) $\beta$ and with a period

$$T_0 = 2\pi \sqrt{\frac{l}{g}}.$$

In the event of a collision with a wall, the absolute value of the magnet's speed does not change, but the direction of movement changes to the opposite. This means that the period of oscillation of the magnet $T$ in the presence of the wall is not equal to $T_0$, but is less than this value for a time $t$. During this time, $t$ magnet, performing free oscillations, would deviate to the right from the vertical from angle $\alpha$ to angle $\beta$ and return back.

Let us write the equation of harmonic oscillations for angular displacement $\varphi$:

$$\varphi = \beta \cos \omega t,$$

where $\omega = \frac{2\pi}{T_0}$. At time $t = 0$ $\varphi = \beta$, that is, the magnet is in the extreme right position. After some time $t_1$ the angle of deviation of the magnet from the vertical becomes equal to $\alpha$. From the equation of oscillations

$$\alpha = \beta \cos \omega t_1,$$

where

$$t_1 = \frac{1}{\omega} \arccos \frac{\alpha}{\beta}.$$

From the symmetrical it is obvious that

$$\tau = 2t_1 = \frac{2}{\omega} \arccos \frac{\alpha}{\beta} = \frac{T_0}{\pi} \arccos \frac{\alpha}{\beta}.$$

Then finally

$$T = T_0 - \tau = T_0 \left( 1 - \frac{1}{\pi} \arccos \frac{\alpha}{\beta} \right) = 2 \sqrt{\frac{l}{g}} \left( \pi - \arccos \frac{\alpha}{\beta} \right).$$

I.Sh. Slobodetsky
