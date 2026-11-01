---
id: 1979-11-resheniya-zadach-m538-m539-f547-f552-d77f0093
issue: kvant_1979_11
year: 1979
number: "11"
title: Solutions to problems M538, M539; F547—F552
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 29
page_last: 37
page_labels: 27, 28, 30, 31, 32, 33, 34, 35
tag: PFXN
lang: en
source: kvant_digital
extraction: vision
content_sha256: 871223bfcff96f82c05cf99024465ab5421f296b48f2a4a605263728e0779329
prompt_sha256: draft-1
translated_from: content/ru/1979/11/articles/09_resheniya-zadach-m538-m539-f547-f552-d77f0093.md
source_content_sha256: 8646554f75a09329e85d2e335d1c6734c7838a9679bad1882b7beec67bd15ac0
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 27⟧

Problem solutions
M538, M539; F547—F552

M538. The set of all natural numbers is the depletion of two disjoint subsets $f(1), f(2), \dots, f(n), \dots$}, $\{g(1), g(2), \dots, g(n), \dots\}$, $\exists f(1) < f(2) < \dots < f(n) < \dots, u g(n) = f(f(n)) + 1$ for all $n \ge 1$. Identify $f(240)$.

Let us denote the set $f(n)$ and $\{g(n)\}$ by $F$ and $G$ (by convention $F \cap G = \emptyset$ and $F \cup G = N$). Starting with the first natural numbers 1, 2, 3, ..., it is easy to consistently find out which of the sets $F$ or $G$ the next natural number should be assigned to and which number $n$ it corresponds to in its set: it is clear that $1 = f(1)$, therefore $2 = f(f(1)) + 1 = g(1)$; further, $3 = f(2), 4 = f(3), 5 = f(f(2)) + 1 = g(2)$, ... (Table 1). In this case, we get the condition $g(n) = f(f(n)) + 1$ - we place the next $g(n)$ immediately after $f(f(n))$ is placed.

Thus, $f(n)$ and $g(n)$ are defined uniquely, and in principle we can solve the problem by simply bringing our table to the 240th row. However, it is tedious and uninteresting. You can save time by noticing emerging patterns:

1°. the difference $f(n+1) - f(n)$ is always equal to 1 or 2, and

$$f(n+1) - f(n) = \begin{cases} 1, \text{ если } n \in G, \\ 2, \text{ если } n \in F \end{cases}$$

(if $n = f(k)$, then $f(n)+1 \neq g(k)$);

2°. $g(n) = f(n)+n$ for any $n$. Indeed, among the $g(n)$ numbers 1, 2, ..., $f(f(n)), g(n)$ there are $f(n)$ numbers $f(1), f(2), \dots, f(f(n))$ from $F$ and $n$ numbers $g(1), g(2), \dots, g(n)$ from $G$. Thus, $g(n) = f(n)+n$.

Properties 1° and 2° give us the opportunity to create an “accelerated” table 2. Teler remains, using property 1°, to move from 234 to 240 (table 3). It’s even simpler, as our reader A. Balinsky agreed, to take the extra step earlier (using the equality $f(f(n)) = f(n)+n-1$):

$$f(57) = 90+2 \quad (56 \in F), \quad f(92) = 92+56 = 148,$$

$$f(148) = 148+91,$$

$$f(239) = 239+147 = 386, \quad f(240) = 386+2 = 388 \quad (239 \in F).$$

So, the answer to the specific question of problem M538 was received: $f(240)=388$. However, it turns out that here you can go much further - find replacement simple formulas that immediately give the answer for any $n$:

$$f(n) = \left[ \frac{1+\sqrt{5}}{2} n \right], \quad g(n) = \left[ \frac{3+\sqrt{5}}{2} n \right]$$

(here $[x]$ is the integer part of $x$). Several of our readers figured out the formulas (*), but not everyone managed to accurately prove them. The algebraic proof of content is cumbersome (though not very difficult); Together we will not present a clear picture from which both formulas (*) and the course of constructing the sequences $f(n)$, $g(n)$ will be clear. But first, let’s explain “on the fingers” where the irrational number $\frac{\sqrt{5}+1}{2}$ appears in this problem.

Looking at Table 1, it is natural to assume that the sequence $f(n)$ grows approximately as a linear function of $n$: $f(n) \approx \gamma n$. Then for large $n$ there should be $g(n) \approx f(f(n)) \approx \gamma (\gamma n) = \gamma^2 n$. But according to 2°, $g(n) = f(n)+n$, so $\gamma^2 n \approx \gamma n+n$, and this is only possible for $\gamma^2 = \gamma+1$, whence (if $\gamma > 0$) $\gamma = (\sqrt{5}+1)/2$. From what follows it will be clear that our set $F$ and $G$ of the first $n$ natural numbers contain approximately $n/\gamma$ and $n/\gamma^2$ numbers of the corresponding ones (as they say, they have completenesses $1/\gamma$ and $1/\gamma^2$).

⟦folio 28⟧

The number γ and its close “relatives”

$$\frac{1}{\gamma} = \gamma - 1 = \frac{(\sqrt{5} - 1)}{2}, \quad \gamma^2 = \gamma + 1 = \frac{(\sqrt{5} + 3)}{2}, \quad 1/\gamma^2 = \frac{(3 - \sqrt{5})}{2}$$

arise in a wide variety of problems *), in particular, in the study of Fibonacci numbers 1, 2, 3, 5, 8, 13, ..., $\Phi_{n+1} = \Phi_{n-1} + \Phi_n$, ... (anything Pitts knows that these numbers are 1 less than the numbers $n$ from Table 2; think why), in number theory, in geometry. In particular, it is easy to check that when cutting a square from a straight ski with the “golden” length ratio, the side γ remains of a straight ski similar to the original one - it follows that on figure 1, ​​where such cutting is done twice, points O, K and M lie on the same straight line. This property of the number γ will be useful to us.

Let us now present a simple way to construct the numbers $f(n)$ and $g(n)$. On the checkered paper as on the coordinate plane (Fig. 2) we draw a straight line $l$, defined by the equation $y = \gamma x$ - with the “golden” slope $\gamma = \frac{(\sqrt{5} + 1)}{2}$. (How to do this with a compass and ruler?) Line up all those “red” cells (Fig. 2) that the straight line $l$ intersects, starting with the zero cell containing the origin $O$. Since γ is playal, $l$ does not pass through the grid nodes, that is, it enters the next cell, intersecting either the line $y = n$ or the line $x = n$ ($n \in \mathbb{Z}$). Note that the cell number $\{(x; y) : [x] = i, [y] = j\}$ is equal to $i+j$ (why?). We claim that if the cell number is $m$, then either $m = f(n)$ or $m = g(n)$. In other words, if we line the segments of the coordinate rays $Ox$ and $Oy$ in order, then on the segment number $n$ of the axis $x$ lies cell number $g(n)$, and to the right of the segment number $n$ of the axis $y$ lies cell number $f(n)$. Check it out in Table 1 and figure 2!

The proof that the numbers $f(n)$ and $g(n)$ constructed in this way, using checkered paper, are in fact what we need, consists of checking that the numbers of the cells satisfy all the properties of the sequence $f$ and $g$ from the problem statement. The fact that we obtain a partition of the entire natural series $N$ into two disjoint increasing sequences is clear. It remains to check that $g(k) = f(f(k)) + 1$. Let's “extend” the numbering of red cells to the entire plane: each cell of the plane $\{(x; y) : [x] = i, [y] = j\}$ will be assigned the number $i+j$ (blue numbers on figure 2); in this case, the numbers of segments on the wasps coincide with the numbers of the cells containing them.

For an arbitrary $n$, we mark the points $K(n/\gamma; n)$ and $M(n/\gamma; n)$ of intersection of the line $l$ with the lines $y = n$ and $x = n$ (Fig. 3). Then the left cell containing the point $K$ is numbered $f(n)$, and the bottom cell containing the point $M$ is numbered $g(n)$. Let us note the projections $K'$ and $M'$ of the points $K$ and $M$ onto the axis $y$. Note that $K'KM' = 45^\circ$ (remember figure 1), so the cells containing points $K$ and $M'$ are numbered $f(n)$. At point $M$, therefore, there is a straight line $f(f(n))$ into cell number $g(n)$, that is, $f(f(n)) + 1 = g(n)$.

*) N. N. Vorobyov “Fibonacci Numbers” (M., “Nauka”, 1978); G. S. M. Coxeter “Introduction to Geometry” (Moscow, “Nauka”, 1966), ch. “Golden ratio and phyllotaxis”; A. D. Bendukdze “The Golden Section” («Kvant», 1973, No. 8, p. 22).

⟦folio 30⟧

Note that this lemma is also true for any point $K$ in space: if the point $K$ belongs above the drawing plane 5 at a distance $z$, that is, has coordinates $(x; y; z)$, then $2z^2$ will be added to both sides of (1).

Let us now prove the statement $2^\circ$. According to $1^\circ$, the vertices $A_1, B_1$ and $C_1$ of the parallelepid—the fourth vertices of the line/libs $PBA_1C$, $PCB_1A$, and $PAC_1B$ (Fig. 6)—lie at a distance $\sqrt{2r^2-p^2}$ from the point $K$. Again uses $1^\circ$: the fourth vertex $D$ of the direct/libnikov $A_1CB_1D$, for which $|A_1K|^2 = |B_1K|^2 = 2r^2 - p^2$, $|CK|^2 = r^2$, is located at a distance from the point $K$

$$\sqrt{2(2r^2-p^2)}-r^2 = \sqrt{3r^2-2p^2}.$$

So, we have proven that the vertex $D$ of the parallelepid lies on a sphere with center $K$ and radius $\sqrt{3r^2-2p^2}$. But, as in any problem of finding a set of points, it is necessary to prove the opposite: that any point on this sphere is the vertex of a certain parallelepid that satisfies the conditions of the problem. I've forgotten a lot about this from the readers who sent us the solution problem M539. Meanwhile, here we give a neat proof of the converse statement, which is far from being as simple as in the plane case (there, given points $P$ and $D$, it is easy, by constructing a circle with diameter $[PD]$, to find the vertex $A$ and using $1^\circ$ to prove that the fourth vertex $C$ is straight $PADC$ lies on the given circle). Perhaps this is due to the fact that in a spatial problem there is more freedom in choosing the desired parallelepid: for the given points $P$ and $D$ there is a whole family of them. (We, of course, only need to build one of them.)

To prove the converse, some readers have used the coordinate method, others have used continuity messages. Here, too, we will begin with the geometric observations that were made in attempts to solve this problem:

$$3^\circ. \text{Квадраты радиусов четырех сфера с центром } K, \text{ на коморых лежат точки } P; A, B \text{ и } C; A_1, B_1 \text{ и } C_1, D, \text{ образуют арифметическую прогрессию:}$$
$$p^2, r^2, 2r^2-p^2, 3r^2-2p^2.$$

A similar pattern exists in the flat version (although there are only three terms in the program). In this regard, we indicate the following logic of the statement being proved:

If several concentric circles, the quadratiches of which form an arithmetic progression,

⟦folio 31⟧

Fig. 8.

gressio, intersect some circle γ, then the common (with γ) chords of these circles are parallel and are at the same distance from each other (Fig. 7).

We will come across a spatial version of this statement, where instead of circles there are spheres, together with chords there are circles, etc. (it is obtained from flat figure 7 by rotation around the axis of symmetry).

4°. It is easy to prove that the planes ABC and A₁B₁C₁ intersect the diagonal PD of the paralleleped at the maximum points M and M₁, which divide it into three identical segments: |PM| = |MM| = |M₁D| — and is the intersection point of the medians of triangles ABC and A₁B₁C₁ (Fig. 8). The midpoint Q of the diagonal PD serves as the center of the symmetry of the paralleleped.

5°. To obtain spatial figure 6 and 8, we also point out the following facts:

The projection Q' onto plane ABC of the center Q of a right paralleleped falls into the center of a circle circumscribed around triangle ABC; the projection P' of the vertex P of the paralleleped is to the orthocenter of triangle ABC (the point of intersection of the heights). From here and from 4° it is easy to derive Euler’s theorem: M∈[Q'P'] and |MQ'| : |MP'| = 2 (Fig. 9) *). Theorels are all ready to finish solving problem M539.

Let |KP| = p and |DK| = √3r² - 2p²; Q is the midpoint of the segment [PD], γ and γ₁ are the circles along which a sphere with diameter [PD] intersects spheres of radii r and √2r² - p² with center K (see Fig. 8). According to 4°, the planes of these circles divide [PD] into three equal parts: [PM], [MM₁], [M₁D]. Take any point A∈γ and denote by A₁ the point A₁∈γ₁ symmetric to it with respect to Q.

It is clear that PAD = PA₁D = 90°. Let us draw planes through points P and D peredicular to the segments [PA] || [DA₁]. The points of intersection of these planes with the circles γ and γ₁ give us the vertices of the required straight paralleleped (see Fig. 8): in fact, the midpoints E and E₁ of the segments AD and A₁P (Fig. 10, 11) lie in the plane of the circles γ and γ₁ and serve as the centers of sections of the sphere by constructed planes; therefore, AC₁DB₁ and A₁CPB are straight.

N. Vasiliev

*) True, such a proof is only suitable for an acute triangle, because only such a triangle can serve as a section (ABC) for a right paralleleped. Consider whether this proof could be reworked for obtuse ΔABC.

⟦folio 32⟧

F547. Photorefines of spherical clumps of luminous plasma flying uniformly slow until they stop have the form of stripes of length l. Maximum strip width d ≤ l. The distance between the plasma and the camera lens is L, the focal length of the lens is F. The minimum “exposure” time required for an image to appear on the photographic surface is t. Determine the acceleration of the clumps. The camera lens remains open until the clots stop completely.

F548. Reactive shallowing of mass m we describe a dead mass along a vertical circular path of radius R with a constant linear speed v. How much work is done by the claim force when moving the haul from the lowest position to the highest one? The coefficient of claim between shallow and road is equal to μ.

Fig. 12.

The maximum width of the strip is obviously determined by the diameter D of the bunch. If Γ = |$\frac{F}{F-L}$| is the magnification of the camera, then D = $\frac{d}{Γ}$. To avoid appearing on the film, it is necessary that the speed v of the bunch be such that in time t the bunch would travel a distance of no more than D. If time t elapses from the moment the image appears until the bunch stops completely, then at the moment the image appears the speed of the bunch is |v| = |a| t and satisfies the conditions

$$\frac{D}{|a| t} = \frac{d}{\Gamma |a| t} = \tau.$$ (1)

Until the clot comes to a complete stop, it will cover the distance

$$L = \frac{l}{\Gamma} = \frac{|a| t^2}{2}.$$ (2)

From equations (1) and (2) we find the acceleration of the bunch:

$$|\vec{a}| = \frac{d^2}{2\Gamma l\tau^2} = \frac{d^2}{2l\tau^2} \left| \frac{F-L}{F} \right|.$$

V. Seretsevich

Let us consider two symmetrical positions of the cart, in which the radius vectors of the points in which the cart is located make the same angle α (Fig. 12) with the vertical one. $\vec{N}_1$ and $\vec{N}_2$ are the road reaction forces in these positions, $\vec{F}_{T1}$ and $\vec{F}_{T2}$ are the traction forces, $\vec{F}_{Tp1}$ and $\vec{F}_{Tp2}$ are the friction forces. Since the cart slides along the road, $F_{Tp1} = \mu N_1$ and $F_{Tp2} = \mu N_2$ (here $N_1 = |\vec{N}_1|$, $F_{Tp1} = |\vec{F}_{Tp1}|$, etc.).

The cart moves in a circle with speed v; therefore, the sum of the projections of all forces acting on the cart onto the direction of the radius is equal to $mv^2/R$, that is (see Fig. 12)

$$N_1 - mg \cos \alpha = mv^2/R, \quad N_2 + mg \cos \alpha = mv^2/R.$$

From here

$$N_1 = (mv^2/R) + mg \cos \alpha, \quad N_2 = (mv^2/R) - mg \cos \alpha$$

And

$$F_{Tp1} = \mu [(mv^2/R) + mg \cos \alpha], \quad F_{Tp2} = \mu [(mv^2/R) - mg \cos \alpha].$$

When the radius vector is rotated through a small angle Δα, that is, when the projection of the cart is small at Δl = R Δα with strong friction $\vec{F}_{Tp1}$ and $\vec{F}_{Tp2}$, work $\Delta A_1 = F_{Tp1}R \Delta \alpha$ and $\Delta A_2 = F_{Tp2}R \Delta \alpha$ is performed.

The sum of the work of forces $\vec{F}_{Tp1}$ and $\vec{F}_{Tp2}$ in small areas Δl is equal to $\Delta A = (F_{Tp1} + F_{Tp2})R \Delta \alpha = 2\mu mv^2 \Delta \alpha.$

The value of ΔA does not depend on α. This means that when the radius vector of the cart rotates through a small angle Δα from any two symmetrical points (similar to I and 2), the merger does the same work, proportional to Δα.

Moving the cart from the bottom point of the track to the top corresponds to a change in α by π/2, that is, ΣΔα = π/2. Consequently, the work done by the friction force with such a projection is equal to

$$A = \sum \Delta A = 2\mu mv^2 \Delta \alpha = \pi\mu mv^2.$$

O. Savchenko

⟦folio 33⟧

F549. Two balls with masses $m_1$ and $m_2$ are connected by a spring with stiffnesses $k$; the spring is positioned correctly and is not deformed. The balls are simultaneously given speeds $\vec{v}_1$ and $\vec{v}_2$, as shown in figure 13, with $|\vec{v}_1| = |\vec{v}_2| = v$.
Find the maximum height of the system and the maximum deformation of the spring.

Fig. 13.

The center of mass of the system (c.m.) will move like a body with mass $M = m_1 + m_2$, thrown at an angle to the horizon with an initial impulse $\vec{p}_0$ equal to the sum of the initial impulses of the balls:

$$\vec{p}_0 = M \vec{u}_0 = m_1 \vec{v}_1 + m_2 \vec{v}_2$$

($\vec{u}_0$ is the initial speed of the centroid). The projection of the impulse $\vec{p}_0$ onto the vertical axis $OY$ is equal to $m_2 v$, therefore, the projection of the initial velocity c. m. on axis $OY$ is equal to $u_y = m_2 v / M$. This means that the maximum height of the center of mass of the system is equal to

$$H = \frac{u_y^2}{2g} = \frac{v^2}{2g} \left( \frac{m_2}{m_1 + m_2} \right)^2.$$

Now let's find the maximum deformation of the spring. Obviously, at the moment when the deformation of the spring is maximum, in a coordinate system moving with the speed of the center of mass of the system, the balls can only roll around the center of mass. This means that the energy of the system can be represented as the sum of the energy $W_C$ of the system as a whole and internal energy, which is equal to the sum of the potential energy of deformation of the spring $kx^2 / 2$ (x is the amount of deformation) and the kinetic energy of rotation of the balls $W_K = 1 / 2 \left[ m_1 (\omega l_1)^2 + m_2 (\omega l_2)^2 \right]$, where $\omega$ is the angular velocity of rotation, and $l_1$ and $l_2$ are the distances from the corresponding balls to the center wt.

Let us denote the length of the spring by $l$. Then $l_1 = lm_2 / M$, $l_2 = lm_1 / M$, so

$$W_K = \frac{1}{2} \omega^2 l^2 \left( \frac{m_1 m_2^2}{M^2} + \frac{m_2 m_1^2}{M^2} \right) = \frac{1}{2} \omega^2 l^2 \frac{m_1 m_2}{M}.$$

Let's find $\omega$. From the law of conservation of angular momentum it follows that

$$m_1 (\omega l_1) l_1 + m_2 (\omega l_2) l_2 = m_1 \omega_0 l_{10}^2 + m_2 \omega_0 l_{20}^2,$$

where $l_{10}$ and $l_{20}$ are the initial distances from the balls to the center of mass, $\omega_0$ is the initial angular velocity. Obviously, if the initial length of the spring is $l_0$, then

$$l_{10} = l_0 m_2 / M, \quad l_{20} = l_0 m_1 / M.$$

Poznym we can write

$$\left[ m_1 \left( \frac{m_2}{M} \right)^2 + m_2 \left( \frac{m_1}{M} \right)^2 \right] \omega l^2 = \left[ m_1 \left( \frac{m_2}{M} \right)^2 + m_2 \left( \frac{m_1}{M} \right)^2 \right] \omega_0 l_0^2.$$

Hence $\omega = \omega_0 (l_0 / l)^2$. In order to find $\omega_0$, it is necessary to find the initial velocities of $\vec{v}_1$ and $\vec{v}_2$ balls in the center of mass system. Since the speed of the center of mass at the initial moment is equal to $\vec{u}_0 = \left( m_1 \vec{v}_1 + m_2 \vec{v}_2 \right) / M$, the speed of the balls in the center of mass system corresponds to

$$\vec{v}_1 = \vec{v}_1 - \vec{u}_0 = \frac{m_2}{M} \left( \vec{v}_1 - \vec{v}_2 \right),$$

$$\vec{v}_2 = \vec{v}_2 - \vec{u}_0 = \frac{m_1}{M} \left( \vec{v}_2 - \vec{v}_1 \right).$$

The angular velocity $\omega_0$ of the balls is equal, for example, to the projection of the velocity $\vec{v}_0$ onto the axis $OY$ divided by $l_{20}$, that is

$$\omega_0 = \frac{v m_1 / M}{l_{20}} = \frac{v}{l_0}.$$

⟦folio 34⟧

Thus,

$$W_K = \frac{1}{2} \omega_0^2 l_0^2 \frac{m_1 m_2}{M} = \frac{v^2}{2} \frac{m_1 m_2}{M} = \frac{m_1 m_2}{2M} v^2.$$

Now let's use the law of conservation of energy. The total energy of the system is

$$\frac{m_1 v_1^2}{2} + \frac{m_2 v_2^2}{2} = \frac{M v^2}{2}.$$

Because

$$\frac{M v^2}{2} = W_C + \frac{k x^2}{2} + W_K.$$

But, according to the law of conservation of energy, for the system as a whole

$$W_C = W_{co} = \frac{M u_0^2}{2} = \frac{M}{2} \left( \frac{m_1 \vec{v}_1 + m_2 \vec{v}_2}{M} \right)^2.$$

Since the vectors $m_1 \vec{v}_1$ and $m_2 \vec{v}_2$ have been mutually redistributed,

$$\left( m_1 \vec{v}_1 + m_2 \vec{v}_2 \right)^2 = m_1^2 v_1^2 + m_2^2 v_2^2 = \left( m_1^2 + m_2^2 \right) v^2.$$

Because

$$W_C = \frac{m_1^2 + m_2^2}{2M} v^2,$$

and the law of conservation of energy can be rewritten as

$$\frac{M v^2}{2} = \frac{m_1^2 + m_2^2}{2M} v^2 + \frac{k x^2}{2} + \frac{m_1 m_2 v^2}{2M}.$$

From here

$$x = v \sqrt{\frac{m_1 m_2}{k M}}.$$

I. Slobodetsky

The distance $h$ from the center of the aluminum washer to the top of the cone is determined by the equation $\frac{h + a}{h} = \frac{R}{r}$ (Fig. 14) and is equal to $h = a \frac{r}{R - r} = 3$ (cm).

When heated, the aluminum washer expands more than the area of ​​the cone with which it is in contact ($\beta_2 > \beta_1$), so it slides down. The iron washer "wedges" onto the cone ($\beta_3 < \beta_1$) and becomes mixed together with the section of the cone that holds it. When heated, the angle at the apex of the cone does not change. The new distance $h'$ from the center of the aluminum washer to the top of the cone is determined by the equation $\frac{h'}{h} = \frac{r'}{r}$ and is equal to

$$h' = h \frac{r (1 + \beta_2 \Delta t)}{r} = h (1 + \beta_2 \Delta t).$$

The distance between the washers when heated increased by

$$\Delta a = \left( H' - h' \right) - a = a \beta_1 \Delta t - h \left( \beta_2 - \beta_1 \right) \Delta t \approx 0,16 \text{ (мм)}.$$

G. Komkin

⟦folio 35⟧

F551. A load of mass m is suspended from two springs with stiffnesses $k_1$ and $k_2$ using a thread and a block (Fig. 15). Find the period of small fluctuations of the load. Nimtb and block sitam weightless.

When the block is mixed with a load by values ​​$x$, the total deformation of the springs is equal to $2x$, that is
$$x_1 + x_2 = 2x,$$
where $x_1, x_2$ is the deformation of springs with stiffness $k_1$ and stiffness $k_2$, respectively. The elastic forces that arise in the springs are the same - each of them is equal in absolute value to the force $\vec{T}$ of thread tension. Thus, $x_1 = T/k_1, x_2 = T/k_2$ and
$$2x = \frac{T}{k_1} + \frac{T}{k_2}$$
(here $T = |\vec{T}|$). From here is
$$T = 2 \frac{k_1 k_2}{k_1 + k_2} x.$$
The force $\vec{F}$ acting on the block with the load is equal in abscimal value to $2T$, that is
$$F = \frac{4k_1 k_2}{k_1 + k_2} x$$
(here $F = |\vec{F}|$). Thus, oscillations of a block with a load can be considered as oscillations of a mass $m$ on a spring with a stiffness $k' = \frac{4k_1 k_2}{k_1 + k_2}$. The period of such oscillations is equal to
$$T = 2\pi \sqrt{\frac{m}{k'}} = \pi \sqrt{\frac{m(k_1 + k_2)}{k_1 k_2}}.$$

F552. The volt-ampere characteristic of a neon lamp is shown in Fig. 16. At what value $R$ of the resistor, included in the circuit shown in Fig. 17, will the neon lamp (n.l.) not turn on after closing the key $K$?

When the key is closed, the capacitor begins to charge. When the voltage on the capacitor, and therefore on the lamp, becomes equal to 110 V, the lamp will light up. From this moment on, the current flowing through the lamp will increase, and the voltage across the lamp and, therefore, across the capacitor will fall - the capacitor will charge. If during charging the capacitor becomes less than 80 V, the lamp will go out - the current in the circuit is less than the rated current flowing through the lamp when charging ~80 V (see Fig. 16). Therefore, in order for the lamp not to go out, the voltage on the capacitor should not be in the process

Fig. 16. Fig. 17.

discharge drops below 80 V. In the limiting case of $U_C = 80$ V, the voltage across the resistor is 40 V, the current flowing through the resistor is equal to the current flowing through the lamp (1 µA), and hence the resistance of the resistor is $R = 40$ ohm. With a lower resistance value $U_C < 80$ V the lamp does not light.

I. Slovodetsky
