---
id: 1980-11-zalgaller-zadacha-o-treugolnikah-s-obschim-osnovaniem-652d2e9d
issue: kvant_1980_11
year: 1980
number: "11"
title: Common base triangle problem
authors:
  - Залгаллер В. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 17
page_last: 20
page_labels: 15-18
tag: A8NV
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0a5825cf56818ece7cda6c9c3494e842b412b0c18bb41e00ccd9f4d050c03750
prompt_sha256: draft-1
translated_from: content/ru/1980/11/articles/06_zalgaller-zadacha-o-treugolnikah-s-obschim-osnovaniem-652d2e9d.md
source_content_sha256: 67f10cb09c95036037b7e692591d9fe695173d2afb9467aafd62d3a4fb6a4e69
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 15⟧

Task
about triangles
with common ground

In the fifth issue of «Kvant» for 1978, it was proposed to find a geometric solution to the following problem: two triangles on a plane have a common base, and their vertices $C_1, C_2$ are different and lie on the same side of the base; prove that the distance between the vertices $C_1$ and $C_2$ is greater than the distance between the centers $O_1$ and $O_2$ of the incircles of these triangles.

Over the past two years, the editors have received many messages about this interesting and difficult task. However, none of our readers was able to find a proof that takes into account all the possibilities of the relative positions of the vertices.

We place two pieces of evidence; the first was invented by the Kharkov mathematician A. I. Medyannik, the second is a proof suggested by the authors of the problem V. A. Zalgaller and A. A. Ivanov, simplified on the advice of academician A. V. Pogorelov.

First proof

We will need the following property of the bisector of an angle of a triangle (“Geometry 6-8”, problem 914): if AD is the bisector of angle A of a triangle

prisoner $ABC$ ($D \in [BC]$), then $\frac{|BD|}{|DC|} = \frac{|AB|}{|AC|}$.

Let point O be the center of the circle (Fig. 1) inscribed in $\triangle ABC$. Let us express the vector $\vec{O} = AO$ in terms of the vectors $\vec{a} = \vec{BC}, \vec{b} = \vec{AC}, \vec{c} = \vec{AB}$ and in terms of their lengths $a, b, c$.

It is easy to see that $\vec{\varrho} = \frac{|AO|}{|AD|} \cdot \vec{AD} = \frac{|AO|}{|AD|} \left( \vec{c} + \frac{|BD|}{|DC|} \vec{a} \right)$.

By the property of the bisector $\frac{|DC|}{|BC|} = \frac{|BD|}{|DC|} + \frac{|BD|}{|DC|} = \frac{c}{b+c}$.

Similarly ($BO$ is the bisector of angle B),

$\frac{|AO|}{|AD|} = \frac{1}{1 + \frac{|OD|}{|AO|}} = \frac{1}{1 + \frac{|BD|}{c}}$.

From $\frac{|BD|}{|DC|} = \frac{c}{b}$ and $|BD| + |DC| = a$ we get $|BD| = \frac{ac}{b+c}$.

Therefore $\frac{|AO|}{|AD|} = \frac{b+c}{a+b+c}$.

Taking advantage of the fact that $\vec{a} = -(\vec{b} + \vec{c})$, we obtain the final $\vec{\varrho} = \frac{b\vec{c} - c\vec{b}}{p}$,

(1)

where $p = a + b + c$.

Now let's start solving the problem. Let us express the length of the vector $\vec{d}_0 = O_1O_2$ in terms of $d = |C_1C_2|$ and the lengths of the sides of the triangles $ABC_1, ABC_2$.

According to what has been proven (see Fig. 2)

$\vec{d}_0 = \vec{\varrho}_2 - \vec{\varrho}_1 = \frac{b_2\vec{c} - c\vec{b}}{p_2} + \frac{c\vec{b}_1 - b_1\vec{c}}{p_1}$,

Fig. 1.

⟦folio 16⟧

where $p_1 = a_1 + b_1 + c$, $p_2 = a_2 + b_2 + c$.

Calculating $\vec{d}_0 \cdot \vec{d}_0 = d_0^2$, after simple transformations we obtain
$$p_1^2 p_2^2 d_0^2 = p_1^2 cb_2 [2cb_2 - 2(\vec{b}_2 \vec{c})] +$$
$$+ p_2^2 cb_1 [2cb_1 - 2(\vec{b}_1 \vec{c})] +$$
$$+ 2p_1 p_2 [cb_2(\vec{b}_1 \vec{c}) - c^2(\vec{b}_1 \vec{b}_2)] -$$
$$- b_1 b_2 c^2 + cb_1(\vec{b}_2 \vec{c})].$$

(2)

Note that $2(\vec{b}_1 \vec{c}) = a_1^2 - b_1^2 - c^2$, $2(\vec{b}_2 \vec{c}) = a_2^2 - b_2^2 - c^2$; That's why
$$2cb_1 - 2(\vec{b}_1 \vec{c}) = 2cb_1 - a_1^2 + b_1^2 + c^2 =$$
$$= (a_1 + b_1 + c)(b_1 - a_1 + c) =$$
$$= p_1(b_1 - a_1 + c),$$

similarly,
$$2cb_2 - 2(\vec{b}_2 \vec{c}) = p_2(b_2 - a_2 + c).$$

This reduces the equality
(2) on $p_1 p_2$. Also, $\vec{d} = \vec{b}_2 - \vec{b}_1$, whence $2(\vec{b}_1 \vec{b}_2) = b_1^2 + b_2^2 - d^2$. That's why
(2) takes the form
$$p_1 p_2 d_0^2 = p_1 cb_2(b_2 - a_2 + c) +$$
$$+ p_2 cb_1(b_1 - a_1 + c) +$$
$$+ [cb_2(a_1^2 - b_1^2 - c^2) - c^2(b_1^2 + b_2^2 - d^2)] -$$
$$- 2b_1 b_2 c^2 + cb_1(a_2^2 - b_2^2 - c^2)],$$
where
$$p_1 p_2(d^2 - d_0^2) =$$
$$= [(a_1 + b_1 + c)(a_2 + b_2 + c) - c^2]d^2 +$$
$$+ [(a_2 - b_2 - c)(a_1 + b_1 + c)b_2 +$$
$$+ (a_1 - b_1 - c)(a_2 + b_2 + c)b_1 +$$
$$+ (b_1^2 - a_1^2 + c^2)b_2 + (b_1^2 + b_2^2)c +$$
$$+ 2b_1 b_2 c + (b_2^2 - a_2^2 + c^2)b_1]c,$$

which after transforming inside the square brackets gives
$$p_1 p_2(d^2 - d_0^2) = [(a_1 + b_1)(a_2 + b_2) +$$
$$+ c(a_1 + b_1 + a_2 + b_2)]d^2 +$$
$$+ [c(a_2 - a_1)(b_2 - b_1) +$$
$$+ (a_1 b_2 - b_1 a_2)(a_2 - a_1 + b_1 - b_2)]c.$$

(3)

To prove that $d > d_0$, it is enough for us to verify that the right-hand side of equality (3) is positive. The latter consists of two terms. Since $a_1 + b_1 > c$ and $a_2 + b_2 > c$, the first term is greater than $3c^2 d^2$. It remains to check that the second term is less than $3c^2 d^2$ in absolute value. The correspondences $|a_2 - a_1| < d$, $|b_2 - b_1| < d$ are obvious.

Fig. 3

Because
$$p_1 p_2(d^2 - d_0^2) > (c^2 + 2c^2)d^2 -$$
$$- |c^2(a_2 - a_1)(b_2 - b_1)| -$$
$$- |a_1 b_2 - b_1 a_2|(|a_2 - a_1| +$$
$$+ |b_2 - b_1|)c > 3c^2 d^2 - c^2 d^2 -$$
$$- 2dc|a_1 b_2 - b_1 a_2| = 2c^2 d^2 -$$
$$- 2dc|a_1 b_2 - b_1 a_2|.$$

Below we will prove that $|a_1 b_2 - b_1 a_2| \leq cd$.

Therefore, the right side of inequality (4) is non-negative.

Therefore, $d > d_0$.

So, it remains to prove the following lemma.

Lemma. Let the point $C_2$ be arbitrarily located in the plane of the triangle $ABC_1$. Then (Fig. 3)
$$|a_1 b_2 - b_1 a_2| \leq cd.$$

Proof. Let us drop from the point $C_2$ the perpendicular $C_2 P$, $C_2 Q$, $C_2 T$ to the straight lines $BC_1$, $AC_1$, $AB$.

A circle with diameter $AC_2$ can be described around the quadrilateral $AQC_2 T$.

Since $Q\hat{A}T = \alpha$, by the theorem of sines, $|QT| = b_2 \sin \alpha$.

Considering similarly the quadrilaterals $C_1 PC_2 Q$ and $PC_2 TB$, we obtain $|PQ| = d \sin \gamma$ and $|PT| = a_2 \sin \beta$.

Let $R$ be the radius of the circle circumscribed about the triangle $AC_1 B'$. By the law of sines, $\sin \gamma = \frac{c}{2R}$, $\sin \beta = \frac{b_1}{2R}$, $\sin \alpha = \frac{a_1}{2R}$. Postoomy $|QT| = \frac{a_1 b_2}{2R}$, $|PT| = \frac{a_2 b_1}{2R}$, $|PQ| = \frac{cd}{2R}$.

The triangle inequality implies $|PT| - |QT| \leq |PQ|$; That's why

⟦folio 17⟧

Fig. 4

mu after substituting the expressions for $|QT|$, $|PT|$, $|PQ|$ and simplified we get

$$|a_1b_2-a_2b_1| \leq cd.$$

Second proof

With the base $AB$ fixed, we will uniformly move the vertex $C$ along the segment $C_1C_2$ from $C_1$ to $C_2$. In this case, the center $O$ of the inscribed circle will move along some path from $O_1$ to $O_2$.

Lemma. When the vertex $C$ moves with a non-zero speed, the center $O$ moves with a lower speed.

From this lemma it follows that when $C$ passes the segment $C_1C_2$ at a constant speed, the point $O$, moving at each moment with a lower speed, will pass from $O_1$ to $O_2$ a shorter path. Moreover, the direct path $|O_1O_2|$ is shorter than $|C_1C_2|$.

Before proving the lemma, let us consider the following. If the vertex $C$ moves with a speed $\vec{v} \neq 0$, then the rays $BC$ and $AC$, running along the sides of the triangle, rotate with some angular velocities $\omega_1$ and $\omega_2$, and at least one of these velocities is not zero. Let's agree on the signs: we consider the angular velocity to be positive if the beam rotates clockwise, and negative if the beam rotates counterclockwise.

Speeds $\vec{v}$ and $\omega_1$, $\omega_2$ are related. If we remove the vector $\vec{v} = \vec{CT}$ (Fig. 4) from the point $C$, then the length $|CP|$ of its projection onto the direction perpendicular to the ray $BC$ is equal to $|\omega_1| \cdot |BC|$. (This is because

Fig. 5

the total speed of movement of the point $C$ is composed of the speed of its movement together with the rotating ray $BC$ and the speed of its movement along this ray.) Similarly, the length $|CQ|$ of the projection $\vec{v}$ to the direction perpendicular to the ray $AC$ is equal to $|\omega_2| \cdot |AC|$. A circle can be drawn around the quadrilateral $CPTQ$. Moreover, $\vec{v}$ is equal to the diameter of this circle.

A similar construction can be done for the speed $\vec{v}_0$ of movement of the center $O$, only in this case $[BC)$, $[AC)$ are replaced by $[BO)$, $[AO)$, and $\omega_1$, $\omega_2$ are replaced by $\frac{\omega_1}{2}$, $\frac{\omega_2}{2}$.

At least one of the speeds $\omega_1$, $\omega_2$ is not zero. In addition, a simultaneous change in the signs of $\omega_1$, $\omega_2$ reverses the direction of $\vec{v}$ and $\vec{v}_0$ without changing the magnitude of $\vec{v}$ and $\vec{v}_0$. Therefore, when proving inequality $\|\vec{v}\| > \|\vec{v}_0\|$, without loss of generality, we can assume that $\omega_1 > 0$ and consider three cases separately: $\omega_2 > 0$, $\omega_2 = 0$, $\omega_2 < 0$.

Case 1. Let $\omega_2 > 0$. Let us rotate by $90^\circ$ the quadrilateral $CPTQ$ around the point $C$ to the position $CP'TQ'$ (Fig. 5), and the quadrilateral $OP_0T_0Q_0$ around $O$ to the position $OP'_0T'_0Q'_0$, and draw $(P'_0P'') \parallel (Q'_0Q'') \parallel (OC)$. The points $P''$ and $Q''$ will bisect the segments $CP'$, $CQ'$, because $|CP'| / |CB| = \omega_1$ and $|OP'| / |OB| = \frac{\omega_1}{2}$.

Since $\vec{v}$ is the diameter of the circle circumscribed by triangle $CP'Q'$, and $\vec{v}_0$ is the diameter of the circle circumscribed by triangle $CP'Q'$, and $\vec{v}_0$ is the diameter of the circle circumscribed by triangle $CP'Q'$, and $\vec{v}_0$ is the diameter of the circle circumscribed by

⟦folio 18⟧

Fig. 6

Fig. 7.

sled around $OP'_0Q'_0$, we have
$$|\vec{v}| = \frac{|P'_0Q'|}{\sin \gamma} = \frac{|P''Q''|}{\sin \frac{\gamma}{2} \cos \frac{\gamma}{2}},
$$
$$|\vec{v}_0| = \frac{|P'_0Q'|}{\sin \left(\frac{\pi}{2} + \frac{\gamma}{2}\right)} = \frac{|P'_0Q'|}{\cos \frac{\gamma}{2}}.$$

The segment $P'_0Q'_0$ is inclined to the bisector $CO$ steeper than one of the rays $AO$, $BO$, and even more steeply than $AC$ and $BC$, which are inclined to $CO$ at an angle $\frac{\gamma}{2}$. Therefore, the distance between parallel lines $P'_0P''$ and $Q'_0Q''$ exceeds $|P'_0Q'_0| \sin \frac{\gamma}{2}$.

Moreover, $|P''Q''| > |P'_0Q'_0| \sin \frac{\gamma}{2}$, which together with (5) gives $|\vec{v}| > |\vec{v}_0|$.

Case 2. Let $\omega_2 = 0$ (Fig. 6); then $|CP| = \omega_1 |BC|$, $|OP_0| = \omega_1/2$, whence $|\vec{v}| = \frac{\omega_1}{\sin \gamma} |BC|$, $|\vec{v}_0| =$

$$\frac{\omega_1}{2 \sin \frac{\gamma}{2}} |BO|.$$

But $|BC| > |BO|$ (since $\angle BOC$ is stupid), and $\sin \gamma < 2 \sin \frac{\gamma}{2}$, hence $|\vec{v}| > |\vec{v}_0|$.

Case 3. Let $\omega_2 < 0$. As in case 1, we rotate the quadrilaterals $CPTQ$, $OP_0T_0Q_0$ by $90^\circ$ to the position $CP'T'Q'$, $OP'_0T'Q'_0$ (Fig. 7) and draw $(P'_0P'') \parallel (Q'_0Q'') \parallel (BD) \parallel (OC)$. Points $P''$, $Q''$ again lie in the midpoints of segments $CP'$, $CQ'$.

This time again
$$|\vec{v}| = \frac{|P'_0Q'|}{\sin (\pi - \gamma)} = \frac{|P''Q''|}{\sin \frac{\gamma}{2} \cos \frac{\gamma}{2}},
$$
$$|\vec{v}_0| = \frac{|P'_0Q'|}{\sin \left(\frac{\pi}{2} - \frac{\gamma}{2}\right)} = \frac{|P'_0Q'|}{\cos \frac{\gamma}{2}},
$$
and to make sure that $|\vec{v}| > |\vec{v}_0|$, we only need to check that in this case
$$|P''Q''| > |P'_0Q'_0|.$$

Let us prepare the segment $P''Q''$ with center $C$ so that it goes into some segment $BM$. Similarly, let us prepare the segment $P'_0Q'_0$ with center $O$ so that it goes into some segment $BN$. It is important that the cooking coefficients are the same. Therefore, to prove (6) it is enough to verify that $|BM| > |BN|$. But the latter is clear from the fact that the triangle $BNM$ has an obtuse angle at the vertex $N$. Indeed, if $N$ lies to the left of the straight line $BD$, then $M\widehat{NB} > \widehat{COB} > \frac{\pi}{2}$, and if $N$ lies to the right of $BD$, then $M\widehat{NB} > M\widehat{NO} = \widehat{COA} > \frac{\pi}{2}$. The lemma is proven.

Comment. It is easy to deduce from the lemma that the inequality $|O_1O_2| < |C_1C_2|$ is preserved, firstly, if $C_1$, $C_2$ lie on different sides of the straight line $AB$, and secondly, if the triangles $ABC_1$, $ABC_2$ with a common base $AB$ are located in space in different planes.

Question. Let's fix the base of the triangular paramid and move its top. Will the center of the inscribed sphere move at a slower speed than the vertex?
