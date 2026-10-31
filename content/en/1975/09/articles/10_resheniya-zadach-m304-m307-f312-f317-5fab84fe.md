---
id: 1975-9-resheniya-zadach-m304-m307-f312-f317-5fab84fe
issue: kvant_1975_9
year: 1975
number: "9"
title: Solutions to problems M304—M307; F312—F317
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 36
page_last: 44
page_labels: 34-42
tag: HBMD
lang: en
source: kvant_digital
extraction: vision
content_sha256: 48295b292e5196504dfde6e1d887ba08ba69cd868478294a4da12f1d16d4feab
prompt_sha256: draft-1
translated_from: content/ru/1975/09/articles/10_resheniya-zadach-m304-m307-f312-f317-5fab84fe.md
source_content_sha256: 3476b3017a923acacbede52653a626d0fa59ec904075cb77aab2607e0d37ad9c
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 34⟧

Problem solutions

M304. We will use a circle to denote a certain (yet unknown) operation that can be applied to any two non-negative integers a and b and can give a non-negative integer a*b=c. Let this operation satisfy the following conditions:

1) a*b = b*a;
2) if a*b=c, then b*c=a;
3) if a*b > c, then b*c < a or a*c < b.
a) Find 0*0; 0*1; 1*1; 0*2.
6) Let's prove that 0*a=a and 1*a =
-{a+1, if a is even,
-a-1 if a is odd.
8) Let us prove that there is at most one operation that satisfies the conditions of the problem.
2) Let us prove that this operation exists and indicate a rule that allows us to calculate a*b given a, b.

a) Let's find 0*0.
Let's assume that 0*0>0. Substituting a=b=c=0 into conditions 3) we get that 0*0<0, which is impossible. So, 0*0=0. Let's find 0*1.
If 0*1=0, then 0*0=1, which is incorrect. If 0*1>1, then from condition (3) 1*1<0, which is impossible. Therefore 0*1=1.
By similar reasoning we obtain that
1*1=0, 0*2=2.

6) 1. Let's prove that 0*a=a by indication of a.
Suppose this is true for all a<n и докажем, что 0*n=n. Пусть 0*n=k<n. тогда 0*k=n, что противоречит допущению. Пусть 0*n>n. then from condition 3) n*n<0, which is impossible. So, 0*n=n.

2) Let's prove that 1*a =
{a+1, if a is even,
a-1 if a is odd.

indication by a.
Let us assume that this has been proven for all a<n, and we will prove it for a=n.
Let's consider two cases.

(a) n is even.
Let's denote 1*n=k. then 1*k=n. If k≤n, then we get a contradiction. Let now 1*n>n+1. then by condition 3) 1*(n+1)<n or n*(n+1)<1, but both lead to a contradiction. So, 1*n=n+1.

(6) n - odd.
Then, by what has been proven, 1*(n-1)=n, whence 1*n=n-1.

c) Let us now prove that there is at most one operation that satisfies the conditions of the problem.
Let us assume that there are two such operations. Let us denote the first operation by $\circ$, and the second by $\odot$. By assumption, there is at least one such pair of numbers a, b for which a*b≠a*b. From all such pairs, choose the one in which the sum a+b is the smallest. So, let a*b≠a*b; if a'+b'<a+b, то a'*b'=a'*b'. Обозначим a*b=k, a*b=l. Пусть k<l (случай k>l is similar). Since a*b>k, then a*k<b or b*k<a. Let a*k=m<b (the case when b*k<a is similar). then a*m=k. Since m<b, then a+m<a+b, and therefore a*m=a*m=k. Then a*k=m, which contradicts the fact that a*k=b.

The resulting contradiction proves statement c).
d) Let us now prove that such an operation exists.
Every non-negative integer a is uniquely represented in the form
a=a₀·2⁰+a₁·2¹+a₂·2²+...+aₖ·2⁷+...*).

*) This is a representation of the number a in the double number system.

⟦folio 35⟧

Here $a_0, a_1, \dots$ is an infinite sequence in which a finite number of terms are ones, the rest are zeros.

Let $a = \sum_{k=0}^{\infty} a_k \cdot 2^k, b = \sum_{k=0}^{\infty} b_k \cdot 2^k$.

Let's define the value of $c = a \circ b$: put $c = \sum_{k=0}^{\infty} c_k \cdot 2^k$, where the numbers $c_k$ are determined by the following rule:

$$c_k = \begin{cases} 0, & \text{ если } a_k = b_k, \\ 1, & \text{ если } a_k \neq b_k. \end{cases}$$

It is obvious that for such a defined operation conditions 1) and 2) are met. Let us check that condition 3) is satisfied. Let's reformulate it like this:

if $a \circ b \neq c$, then: $a \circ b < c$, or $a < c < b$, or $b \circ c < a$.

Let $a \circ b \neq c$. Let us denote by $k$ the highest number at which condition (*) is not satisfied. Then one of the following two cases occurs:

(a) $a_h = b_h = c_h = 1$.

In this case, even all three inequalities are satisfied. Indeed, let us prove, for example, that $a \circ b < c$. Since the $k$th digit of the number $a \circ b$ is equal to 0, and in the $(k+1)-м, (k+2)-м, \dots$ digit the numbers $a \circ b$ and $c$ coincide, then

$$a \circ b \leq 2^0 + 2^1 + \dots + 2^{k-1} + \Delta = 2^k - 1 + \Delta,$$

where by $\Delta$ we denote the number $c_{k+1} \cdot 2^{k+1} + c_{k+2} \cdot 2^{k+2} + \dots$. But the $k$th digit of the number $c$ is 1; that means $c \geq 2^k + \Delta$, hence $a \circ b < c$.

(6) Of the three numbers $a_h, b_h, c_h$, one is equal to one, the other two are equal to zero.

Let $a_h = b_h = 0, c_h = 1$ (other cases are similar). Then $a \circ b < c$, since again $a \circ b \leq 2^k - 1 + \Delta, c \geq 2^k + \Delta$.

A. A. Gritsoryan, A. L. Toom

♦

a) There are two possible cases; they are shown in Figures 1, a and 6. Consider the triangles $B'PC'$ and $BPC$. For their areas we have

$$\frac{S_{B'PC'}}{S_{BPC}} = \frac{|C'P| \cdot |B'P|}{|CP| \cdot |BP|} = \frac{q' \cdot |B'P|}{q \cdot |BP|}.$$

On the other side,

$$\frac{S_{B'PC'}}{S_{BPC}} = \frac{S_{A'PB'} \cdot \frac{|B'C'|}{|A'B'|}}{S_{APB'} \cdot \frac{|BC|}{|AB|}} = \frac{|B'P| \cdot |A'P| \cdot |B'C'| \cdot |AB|}{|BP| \cdot |AP| \cdot |BC| \cdot |A'B'|}.$$

Since $\triangle APB \sim \triangle A'PB'$, then

$$\frac{|A'P|}{|A'B'|} = \frac{|BP|}{|AB|},$$

that is

$$|A'P| \cdot |AB| = |BP| \cdot |A'B'|.$$

Pozny

$$\frac{q' \cdot |B'P|}{q \cdot |BP|} = \frac{|B'P| \cdot |B'C'|}{|AP| \cdot |BC|},$$

⟦folio 36⟧

where
$$|B'C'| = \frac{|BC| \cdot |AP|}{|BP|} \cdot \frac{q'}{q}. \tag{1}$$

Likewise
$$|A'C'| = \frac{|AC| \cdot |BP|}{|AP|} \cdot \frac{q'}{q}. \tag{2}$$

Multiplying equalities (1) and (2), we obtain
$$\frac{s'}{s} = \left( \frac{q'}{q} \right)^2. \tag{3}$$

Daloe
a) $$|AP|^2 = |AC|^2 + |CP|^2 + 2|AC| \cdot |CP| \cdot \cos(\widehat{BCP}) =$$
$$= |AC|^2 + q^2 + 2q \cdot |AC| \cdot \cos(\widehat{BCP});$$
$$|BP|^2 = |BC|^2 + q^2 - 2q \cdot |BC| \cdot \cos(\widehat{BCP}).$$

Multiplying the first match by |BC|, the second by |AC| and adding them up we get
$$|AP|^2 \cdot |BC| + |BP|^2 \cdot |AC| = (s + q^2) \cdot |AB|,$$
that is
$$s + q^2 = \frac{|BC| \cdot |AP|^2 + |AC| \cdot |BP|^2}{|AB|}. \tag{4}$$

In the same way it is found that
$$s' + (q')^2 = \frac{|A'C'| \cdot |B'P|^2 + |B'C'| \cdot |A'P|^2}{|A'B'|}. \tag{5}$$

Let us transform correspondence (5), taking into account equalities (1), (2), (4), and similar triangles APB and A'PB':

$$s' + (q')^2 = |A'P|^2 \cdot \frac{1 + \frac{|B'P|^2}{|A'P|^2} \cdot \frac{|A'C'|}{|B'C'|}}{1 + \frac{|A'C'|}{|B'C'|}} =$$
$$= |A'P|^2 \cdot \frac{1 + \frac{|B'P|^2}{|A'P|^2} \cdot \frac{|AC| \cdot |BP|^2}{|BC| \cdot |AP|^2}}{1 + \frac{|AC| \cdot |BP|^2}{|BC| \cdot |AP|^2}} =$$
$$= |A'P|^2 \cdot |AP|^2 \cdot \frac{|AB|}{|BC| \cdot |AP|^2} = \frac{t^2}{s + q^2},$$
that is
$$\frac{s' + (q')^2}{t} = \frac{t}{s + q^2}. \tag{6}$$

It remains only to prove that, for example,
$$\frac{t}{s + q^2} = \sqrt{\frac{s'}{s}}.$$

But this is just an exercise (see (3) and (6)):
$$\frac{s' + (q')^2}{s + q^2} = \frac{s'}{s} \Rightarrow s' + (q')^2 =$$
$$= \frac{s'}{s} \cdot (s + q^2) \Rightarrow t^2 = \frac{s'}{s} \cdot (s + q^2)^2.$$

Fig. 1.

Fig. 2.

⟦folio 37⟧

6) We will solve problem 6) under the assumption that the point $P$ is located in the non-given sphere $S$ (for the case when $P$ is the interior of the sphere $S$, all reasoning is similar).

Let $AB$ and $QR$ be two intersecting chords of the circle $\sigma$, $A'$ and $B'$ - points from the set $\sigma'$ corresponding to points $A$ and $B$ (Fig. 2). Let us draw a plane through the points $A$, $B$ and $P$; then the cross-section will produce a picture corresponding to figure 1, ​​6.

In problem a) we proved that

$$|C'P| = \frac{|CP| \cdot |AP| \cdot |A'P|}{|AC| \cdot |CB| + |CP|^2}$$

If $Q'$ and $R'$ are points of the set $\sigma'$ corresponding to points $Q$ and $R$ of the circle $\sigma$, then

$$|QP| \cdot |Q'P| = |AP| \cdot |A'P|,$$

and, in addition,

$$|QC| \cdot |CR| = |AC| \cdot |CB|.$$

This means that the point $C'$ (belonging to the chord $A'B'$) also belongs to the segment $Q'R'$, and, therefore, the points $A', B', Q'$ and $R'$ lie in the same plane. Since we chose points arbitrarily, it follows that all points of the set $\sigma'$ belong to the same plane; means $\sigma'$ is a circle.

A. I. Shirshov

Let us now present two solutions to problem 6) that do not use the calculations of problem a).

The idea of ​​the first decision is submitted to our reader S. Finashin (Leningrad).

Let us draw through the points $P$ and the circle $\sigma$ the spheres $S'$; let $\pi$ be the plane tangent to the sphere $S'$ at point $P$. Let us show that all points of the set $\sigma'$ belong to the plane $\pi'$, parallel to the plane $\pi$. To do this, we fix the point $A'$ that belongs to $\sigma'$, and prove that for any point $B'$ the set $\sigma'$ belongs to $\sigma'$ is parallel to the plane $\pi$.

Consider the plane passing through the points $P$, $A'$ and $B'$. This plane intersects the spheres $S$ and $S'$ along the circle $\tau$ and $\tau'$, respectively, the plane $\pi$ - along the straight line $l$ (Fig. 3; points $A$ and $B$ are the intersection points of $(PA')$ and $(PB')$ with the sphere $S$ - they belong to the circle $\sigma$).

Let us denote the angle $A'B'B$ by $\alpha$. Then arc $A'AB$ is equal to $2\alpha$, arc $BB'A'$ is equal to $(2\pi - 2\alpha)$, angle $A'AB$ is equal to $\pi - \alpha$, and angle $BAP$ is equal to $\alpha$; that is, the angle $PBA$ is equal to $2\alpha$. Therefore, angle $BPQ$ is equal to $\alpha$, that is, angles $A'B'B$ and $BPQ$ are congruent. This means that line $A'B'$ is parallel to line $l$, which is what needed to be proven.

The second solution to problem 6) is obtained using a geometric transformation - inversion. Let us first recall what inversion on a plane is (the properties of inversion on a plane were discussed in detail in the article by A.P. Savin and “Inversion and the Apollo Problem”, «Kvant», 1971, No. 8; the second chapter of I.M. Ya glom “Geometric transformations”, vol. II, Linear and steep transformations, M., Gostekhidat, 1956 is devoted to inversion).

Let $A$ be some point that does not coincide with the center $P$ of a given circle of radius $k$. The inversion to $A$ point $A'$ (that is, the image of $A$ point under inversion) is defined as follows. This point lies on the ray $PA$ (see Fig. 4), and its distance from the center $P$ satisfies the corresponding inversions.

⟦folio 38⟧

Let us now list some properties of inversion.

1. A straight line passing through the center P of inversion turns into itself during inversion.

2. Any straight line that does not pass through the center P of the inversion goes into a circle passing through the point P, and vice versa (Fig. 5, a, 6).

3. A circle that does not pass through the center P of inversion goes during inversion into another circle that also does not pass through the point P (Fig. 6, a, 6), or, perhaps, into the same circle. The latter possibility is realized in two cases: 1) when the given circle is relative to the inversion circle (Fig. 4); 2) when this circle coincides with the inversion circle.

You can find evidence of these properties in the already mentioned article by A. P. Savin and the book by I. M. Yaglom.

The theory of inversion is easily transferred from the plane to space: this is not difficult to verify if we consider the spatial bodies that, as a result of the rotation of the figures shown in Figures 4-6, obtain around the line of centers (PA, or PB, or PO₁). Let a sphere Σ with center P and radius k; we define a point inverse to a given point A relative to the sphere Σ as a point A' belonging to the ray PA and such that the distance |PA|·|PA'|=k².

In this transformation, the sphere of inversion turns into itself. Spheres orthogonal to the sphere of inversion also turn into themselves during inversion: the sphere of inversion divides the sphere orthogonal to it into two parts, which during inversion “swap places.”

The theory will show how to solve problem M305 6) using inversion. Consider a sphere Σ with a center at a given point P, orthogonal to a given sphere S. Let us make an inversion with respect to the sphere Σ. In this case, the sphere S will transfer into itself, and any point A of the circle σ∈S will transfer into its inversion the point A': the second point of intersection of the ray PA with the sphere S. Therefore, the points of the set σ' are points whose inversions correspond to the points of the circle σ and vice versa. From all the comments made earlier it follows that σ' is a circle.

I. N. Klumova

Obviously, the remaining part of the board can be cut into 18 equal-sized triangles (Fig. 7). Let us prove that it is no longer possible to cut into 17 triangles.

In fact, if the rest of the board could be cut into 17 equal-sized triangles, then the area of ​​each of them would be greater than $\frac{7}{2}$ (namely, $\frac{63}{17}$).

Consider two triangles whose bases contain a side (or part of a side) of a distant cell and the vertex of this cell lying inside the board (Fig. 8). The heights of these triangles do not exceed 7, and the base of one of them is no more than 1. Consequently, the area of ​​at least one of the triangles under consideration cannot be greater than $\frac{7}{2}$.

So, the smallest number of equal-sized triangles into which the rest of the board can be cut is 18.

V. P. Fedomov

⟦folio 39⟧

M307. The plane is divided into identical six-walled rooms. Some walls have poppy doors, so that for any vertex at which three walls (the sides of the poles) meet, there are doors in exactly two walls. Let us prove that any closed path through a maze passes through an even number of doors.

Let us now have a closed path along the red lines. Generally speaking, it can cross itself. But if he passes through the same room twice, we will split him into d in a closed path. We will do this until we split this path into several closed non-self-intersecting paths. Thus, it is enough to note that every non-self-intersecting path contains an even number of segments.

Let us be given a non-self-intersecting closed path $L$ (one such path is shown on figure by 9 arrows). It limits the part of the plane consisting of rhombuses. Let there be $A$ rhombuses in it. They only have 4A sides. To find out the number of segments of the path $L$, it is necessary to subtract from the number 4A the double number of those sides along which the rhombuses meet. The difference will be an even number, as required.

Another solution can be obtained by making sure that for a given layout it is possible to paint the rooms in two colors so that adjacent rooms have different colors (Fig. 10).

A. L. Toom

F312. The hoop of the padus $R$ is moving at a speed $v$ on a horizontal surface, while we are flying absciltonically inelastic, then when we move away from the step, the momentum of the hoop will change. From the side of the step, a force acts on the hoop directed along the padus $R$ hoop (Fig. 11). Due to this, the momentum of the hoop changes as it steps so that its projection onto the axis $OX$, running along the padus $R$, becomes equal to zero. The projection of the impulse onto the $OY$ axis does not change. Consequently, as a result of the step, the impulse of the hoop becomes equal in abscyl value to $mv \sin \alpha$, and its speed becomes $v \sin \alpha = v \frac{R-h}{R}$ (see Fig. 11). Let us now use the law of conservation of energy. Immediately after removal, the hoop has kinetic energy $\frac{mv^2}{2}\left(\frac{R-h}{R}\right)^2$. Raising-

⟦folio 40⟧

When placed on a step, the hoop will have potential energy $mgh$ and some kinetic energy $\frac{mv_h^2}{2}$; hence,

$$\frac{mv_h^2}{2} \left( \frac{R-h}{R} \right)^2 = mgh + \frac{mv_h^2}{2}.$$

From here we will find the speed that the hoop will have when it “runs up” the step:

$$v_h = \sqrt{v^2 \left( \frac{R-h}{R} \right)^2 - 2gh}.$$

If the speed $v_{\min}$ is the minimum speed at which the hoop will “run up” to the step, then on the step it will have only potential energy, that is

$$v_h = \sqrt{v_{\min}^2 \left( \frac{R-h}{R} \right)^2 - 2gh} = 0.$$

From here

$$v_{\min} = \frac{R}{R-h} \sqrt{2gh}.$$

I. Sh. Slobodetsky

F313. The refractive index of the planar atmosphere decreases with height $h$ above its surface according to the law $n = n_0 - \alpha h$. The radius of the plan is $R$. Namely, at what height $h_0$ above the surface of the plan there is an optical channel through which light rays will bypass the plan, remaining at a constant height. Let's look at the two extreme rays.

A beam remaining at a constant height $h_0$ (Fig. 12) will bypass the plan in time

$$t = \frac{2\pi(R+h_0)}{v_1} = 2\pi(R+h_0) \frac{n_0 - \alpha h_0}{c}.$$

Another ray of the same light channel, absent from the first one at a distance of $\Delta h \ll h_0$, must bypass the plane at a height of $h_0 + \Delta h$ in the same time (only in this case, the front of the light wave propagating along the channel will be everywhere perpendicular to a circle of radius $R + h_0$):

$$t = \frac{2\pi(R+h_0 + \Delta h)}{v_2} = 2\pi(R+h_0 + \Delta h) \frac{n_0 - \alpha(h_0 + \Delta h)}{c}.$$

Equating the propagation time and taking into account that $\Delta h \ll h_0$, we find

$$h_0 = \frac{1}{2} \left( \frac{n_0}{\alpha} - R \right).$$

Note that the distance is a circular refraction. As observations show, it is possible, for example, in the atmosphere of Venus.

⟦folio 41⟧

F314. By smooth and absolute
a lot of unyielding grubka,
containing a very large
number of knees, starting from how many
winter ball (Fig. 13). Find
steady speed
horizontal movement of the ball
logging areas. Does it depend on the initial
speed? Difference in height of adjacent horizontal lines
plots h. Oblique
the plots form with the horizon angle α.

Moving along the inclined section of the main tube, the ball increases its kinetic energy, and when it moves at the moment of transition from one section to another, it loses energy. Therefore, we can actually talk about the steady-state speed $v_{yct}$ of the ball moving along such a tube. Let's show this more strictly.

With each impact, the component of the ball's momentum, redefined by the axis of the bend of the tube in which the ball passes, becomes equal to zero. The component of the impulse, directed along the axis of this knee, remains unchanged. Therefore, if the ball approaches the bend of the tube with a speed of $v$, it will move away from it with a speed of $v$ angle α (Fig. 13).

Let the speed of the ball at the end of the initial horizontal section be $v_0$. After passing through the kink, it will be equal to $v_0$ angle α. At the end of the first initial section, the speed will increase to the value

$$v_1 = \sqrt{v_0^2 \cos^2 \alpha + 2gh},$$

which can be found by applying the law of conservation of mechanical energy

$$\frac{m(v_0 \cos \alpha)^2}{2} + mgh = \frac{mv_1^2}{2}.$$

On the second horizontal section, next after crossing the kink, the speed will be equal to

$$v_2 = v_1 \cos \alpha = \sqrt{v_0^2 \cos^2 \alpha + 2gh \cos \alpha},$$

on the third horizontal section -

$$v_3 = \sqrt{v_0^2 \cos^6 \alpha + 2gh \left(\cos^4 \alpha + 1\right) \cos \alpha},$$

on the fourth -

$$v_4 = \sqrt{v_0^2 \cos^{10} \alpha + 2gh \left(\cos^8 \alpha + \cos^4 \alpha + 1\right) \cos \alpha},$$

on the nth -

$$v_n = \sqrt{v_0^2 \cos^{2(2n-3)} \alpha + 2gh \left(\cos^4(n-2)\alpha + \cos^4(n-3)\alpha + \ldots + 1\right)} \times \cos \alpha = \sqrt{v_0^2 \cos^{2(2n-3)} \alpha + 2gh \frac{1 - \cos^4(n-1)}{\cos^4 \alpha}} \cos \alpha.$$

Since $\cos \alpha < 1$, for very large $n \cos^2(2n-3) \alpha \ll 1$ and $\cos^4(n-1) \alpha \ll 1$. Therefore, the ball will move along horizontal sections at a steady speed

$$v_{yct} \approx \frac{\cos \alpha}{\sqrt{1 - \cos^4 \alpha}} \sqrt{2gh} = \frac{\cos \alpha}{\sin \alpha \sqrt{1 + \cos^2 \alpha}} \sqrt{2gh}.$$

Note that $v_{yct}$ does not depend on the initial speed $v_0$. Meaning that the steady-state speed is essential from equation (*), where it is necessary to put $v_{yct} = v_0 = v_1 \cos \alpha$ (see Fig. 13).

⟦folio 42⟧

F315. A wire spiral connected to a city lighting system is charged with electric current. Half of the spiral begins to be cooled (for example, with water). How will this affect the amount of metal released by this half of the spiral? All spirals? The voltage of seven is considered unchanged.

Fig. 14.

Fig. 15.

Let us denote the resistance of each half of the spiral before the start of cooling as $R$ (Fig. 14). Since the resistance of metals depends on temperature (increases when heated and decreases when cooled), cooling one of the halves of the spiral will lead to a decrease in the resistance of this half to a certain value $R_1 < R$. Since the mains voltage $U$ is unchanged, this will cause an increase in current in the circuit and, therefore, additional heating of the other half of the coil. The resistance of this half will increase and become equal to $R_2 > R$ (Fig. 15).

The new current value in circuit $I = \frac{U}{R_1 + R_2}$ will be greater than the previous value $I_0 = \frac{U}{2R}$. Indeed, let us assume the opposite, that $I \leqslant I_0$. then the resistance of the uncooled half of the spiral remains the same or decreases ($R_2 \leqslant R$), and the resistance of the cooled half $R_1 < R$. Therefore, the total resistance is $R_1 + R_2 < 2R$ and the new current value is $I > I_0$, which contradicts our assumption.

So, $I > I_0$, and therefore the power released in the entire circuit (that is, the amount of heat per unit time) $P = IU$ will increase.

Since $I > I_0$ and $R_2 > R$, the amount of heat $P_2 = I^2 R_2$ released in the uncooled half will also increase.

The power $P_1 = I^2 R_1 = \frac{U^2 R_1}{(R_1 + R_2)^2}$ released in the cooled half, on the contrary, will first decrease the power $P_0 = I^2 R = \frac{U^2}{4R}$. Let's show it.

Let's find the ratio $P_0/P_1$:

$$\frac{P_0}{P_1} = \frac{U^2}{4R} : \frac{U^2 R_1}{(R_1 + R_2)^2} = \frac{(R_1 + R_2)^2}{4R_1 R_2}.$$

It's obvious that

$$\frac{(R_1 + R_2)^2}{4R_1 R} > \frac{(R_1 + R_2)^2}{4R_1 R_2},$$

and the last expression is greater than or equal to 1, since the geometric mean of two quantities $(\sqrt{R_1/R_2})$ does not exceed the arithmetic mean $(\frac{R_1 + R_2}{2})$.

Thus, indeed $P_1 < P_0$, that is, the power released in the cooled half of the spiral, will decrease.

F316. If the “star-shaped” convexes are varied, made of plastic, with a strong throw vertically downwards, then it will bounce like an elastic rubber ball, practically without creasing. In my time, plastic melts are easily wrinkled by hand. Why?

Under the influence of external forces, any body can deform. If a body freed from the action of forces is restored to its original shape and size, then the deformation is called elastic. If the body does not completely return to its original form, then they say that along with elastic deformation, plastic deformation also occurs.

Materials that can withstand plastic deformations without destruction, which are very large compared to the magnitude of elastic deformation, are called plastic. On the contrary, if fracture occurs after plastic deformation, which is very small compared to elastic deformation, then the material is called brittle.
