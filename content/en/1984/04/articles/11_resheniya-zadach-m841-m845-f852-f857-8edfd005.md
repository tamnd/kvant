---
id: 1984-4-resheniya-zadach-m841-m845-f852-f857-8edfd005
issue: kvant_1984_4
year: 1984
number: "4"
title: Solutions to problems M841—M845; F852—F857
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 37
page_last: 42
page_labels: 35-40
tag: NBKU
lang: en
source: kvant_digital
extraction: vision
content_sha256: 39931d7c6061e024cdbc8ccb55f3e65e0c82992fe3b1d7eaba9f8af31f021049
prompt_sha256: draft-1
translated_from: content/ru/1984/04/articles/11_resheniya-zadach-m841-m845-f852-f857-8edfd005.md
source_content_sha256: 3b83419bc6145553bff88363038eaba26e714176af68dae7dae59e23e8e31f1c
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 35⟧

isochorically heated to its initial temperature, which requires the amount of heat $Q=125$ J. Determine $c_x$.

A. A. Sheronov

P871. An initially uncharged capacitor of capacity $C$ is connected consecutively to a battery of EMF of tension $U_0$ and a coil of inductivity $L$. The current in the coil first increases, then decreases. At the moment when the current banishes, the capacitor is disconnected and then reconnected with the ends interchanged.

What maximal current will then flow through the coil. How will the current change if the reconnection process is repeated 1984 times? The circuit’s resistance is negligible.

A. R. Zilberman

P872. A long sled, sliding on very slippery ice, reaches an ice-free section of the road and stops before travelling half its length. Then a sharp push restores the sled’s previous velocity, and it stops again. What is the relationship between 1) the slowing down times in the first and second cases? 2) the distances travelled while slowing down?

S. S. Krotov

Problem solutions

M841 — M845; F852 — F857

This simple problem has several solutions. Let's give just one of them. Let $a$ and $b$ be the lengths of the legs, $c$ the length of the hypotenuse of the given triangle $ABC$; $A_1, B_1$ and $C_1$ are points of tangency of the inscribed circle from the side (see figure). By the theorem on the equality of tangents drawn to a circle from one point, $|AB_1| = |AC_1|$, $|BC_1| = |BA_1|$ and $|CA_1| = |CB_1|$. It follows that

$$|AC_1| = \frac{c+b-a}{2}, \quad |BC_1| = \frac{c+a-b}{2}.$$

Because

$$|AC_1| \cdot |BC_1| = \frac{1}{4} (c+b-a)(c-(b-a)) = \frac{1}{4} (c^2-(b-a)^2) = \frac{1}{4} (c^2-b^2-a^2+2ab) = \frac{ab}{2} = S_{\triangle ABC}$$

(we used the Pythagorean theorem).

In the case of an arbitrary triangle $ABC$, a similar calculation leads to the following formula:

$$S_{\triangle ABC} = |AC_1| \cdot |BC_1| \cdot \text{ctg} (\widehat{C}/2).$$

V. N. Dubrovsky

a) This is a fairly well-known statement - a hint to point 6); it can be easily proven using standard formulas for converting the sum of sines and the difference of cosines into a product:

$$\sin \alpha + \sin \beta + \sin \gamma = 2 \sin \frac{\alpha+\beta}{2} \cos \frac{\alpha-\beta}{2} + 2 \sin \frac{\gamma}{2} \cos \frac{\gamma}{2} = 2 \sin \frac{\gamma}{2} \left( \cos \frac{\gamma}{2} - \cos \frac{\alpha-\beta}{2} \right) =$$

b) The values ​​$\widehat{A}$, $\widehat{B}$ and $\widehat{C}$ of the triangle satisfy

⟦folio 36⟧

Condition
$$\frac{\sin \hat{A} + \sin \hat{B} + \sin \hat{C}}{\cos \hat{A} + \cos \hat{B} + \cos \hat{C}} = \sqrt{3}.$$
Prove that at least one of them is equal to 60°.

$$= 4 \sin \frac{\gamma}{2} \sin \frac{\alpha - \beta - \gamma}{4} \sin \frac{\alpha + \gamma - \beta}{4} = -4 \sin \frac{\alpha}{2} \sin \frac{\beta}{2} \sin \frac{\gamma}{2}$$
(in the latter the transition of the condition $\alpha + \beta + \gamma = 0$).

6) Since $\sqrt{3} = \frac{\sin 60^\circ}{\cos 60^\circ}$, the conditions can be rewritten as follows:
$$\sin \hat{A} \cos 60^\circ - \cos \hat{A} \sin 60^\circ + \sin \hat{B} \cos 60^\circ - \cos \hat{B} \sin 60^\circ = 0$$
or
$$\sin (\hat{A} - 60^\circ) + \sin (\hat{B} - 60^\circ) + \sin (\hat{C} - 60^\circ) = 0.$$
Applying the statement of point a) to the angles $\hat{A} - 60^\circ$, $\hat{B} - 60^\circ$ and $\hat{C} - 60^\circ$, we obtain that
$$\sin \frac{\hat{A} - 60^\circ}{2} \cdot \sin \frac{\hat{B} - 60^\circ}{2} \cdot \sin \frac{\hat{C} - 60^\circ}{2} = 0,$$
that is, at least one of the angles $\hat{A}$, $\hat{B}$, $\hat{C}$ is equal to 60°.
L. D. Kurlyandchik

**M843. At the vertices of triangle ABC, the redistributions AA1, BB1 and CC1 to its plane on one side of it, equal in length to the corresponding altitudes of the triangle, have been restored. Prove that the redistribution of the planes ABC1, BB1 and CC1 onto the plane ABC falls at the center of the inscribed circle in triangle ABC and is equal in length to its radius.

◆ Let $Q$ be the intersection point of the planes ABC1, BB1 and CC1, $O$ its projection onto the ABC plane, $P$ the projection $O$ onto one of the sides of the triangle, for definition - onto the line BC. Obviously, triangle QOP is similar to triangle $A_1AH$, where $AH$ is the altitude of triangle ABC (see Fig. 1). Therefore, $|OP|:|OQ| = |AH|:|AA_1| = 1$, that is, $|OP| = |OQ|$. It is similarly proven that the distances from the point $O$ to the lines $AB$ and $AC$ are also equal to $|OQ|$. But this also means that $O$ is the center of the inscribed circle, $a$ $|OQ|$ is its radius.

Let us give a general correspondence between the distance $d$ from point $Q$ to plane ABC and the lengths $a$, $b$ and $c$ of segments AA1, BB1 and CC1:
$$\frac{d}{a} + \frac{d}{b} + \frac{d}{c} = 1$$ or $d = \frac{abc}{ab + bc + ca}$.

Fig. 1.
Fig. 2.

Prove it yourself and check that if $a$, $b$ and $c$ are the lengths of the altitudes of a triangle, then $d$ is the radius of its inscribed circle. Fig. 2 illustrates the proof of a similar correspondence in the two-dimensional case.

V. N. Dubrovsky,
A. A. Yaguyants

**M844. a) Prove that any natural number $a$ can be represented in a straightforward manner in the form
$a = a_1 \cdot 1! + a_2 \cdot 2! + \dots + a_n \cdot n!$, (1)
food $a_k$ - integers, $0 \leq a_k \leq k$, $a_n \neq 0$. (By definition, $k! = 1 \cdot 2 \cdot \dots \cdot k$, $1! = 1$.)
b) * Prove that any rational number $r$, $0 < r < 1$ can be

◆ a) Let us show how, given a number $a$, find the leading coefficient $a_n$ in the representation
$$a = a_1 \cdot 1! + a_2 \cdot 2! + \dots + a_{n-1} \cdot (n-1)! + a_n \cdot n!$$
(*)
where $0 \leq a_k \leq k$, $a_n \neq 0$, and its number $n$.
From the first point in the margins (see p. 37) it follows that for the indicated values ​​of the coefficients $a_k$
$a' = a_1 \cdot 1! + a_2 \cdot 2! + \dots + a_{n-1} \cdot (n-1)! \leq$
$\leq 1 \cdot 1! + 2 \cdot 2! + \dots + (n-1) \cdot (n-1)! < n!$,
in addition, $n! \leq a_n \cdot n! \leq n \cdot n!$. For every natural number $a$ one can find a unique $n$ such that $a$ lies in the interval $n! \leq a < (n+1)!$; this uniquely determines $n$ in the representation-

⟦folio 37⟧

represent in the form
$$r = \frac{b_1}{2!} + \frac{b_2}{3!} + \dots + \frac{b_n}{(n+1)!},$$
(2)
food $b_k$ - integers, $0 \leq b_k \leq k$, $b_n \neq 0$.
c) Present the number $a=1984$ in the form (1) and the number $r=19/84$ in the form (2).

$$1 \cdot 1! + 2 \cdot 2! + \dots + n \cdot n! = (2! - 1!) + (3! - 2!) + \dots + ((n+1)! - n!) = (n+1)! - 1$$

them (*). By dividing this interval into $n$ intervals (each $n!$ long), we find the only possible value $a_n$ as the number of the interval where $a : a_n \cdot n! \leq a < (a_n+1)n!$ falls; in other words, $a_n$ is the partial quotient of $a$ divided by $n! : a = a_n \cdot n! + a'$, where $0 \leq a' < n!$ ($a_n = [a/n!]$, where $[x]$ is the integer part of $x$).

Similarly, we can find for $a'$ the leading coefficient in the representation
$$a' = a_1 \cdot 1! + a_2 \cdot 2! + \dots + a_{n-1} \cdot (n-1)!$$
etc. A formal proof of the existence and uniqueness of the required representation (*) can be proven by the method of mathematical induction: for $a=1$ the statement is obvious, and our reasoning shows how from the assumption that it is true for numbers less than $a$, it follows that it is true for the given $a$.

You can also wonder in the opposite direction: first find $a_1$, then $a_2$, etc. In this case, $a_1$ is the remainder of dividing $a$ by 2, $a_2$ is the remainder of dividing $(a-a_1 \cdot 1!)/2$ by 3 and, in general, $a_k$ is the remainder of dividing $(a-a_1 \cdot 1! - \dots - a_{k-1} \cdot (k-1)!)/k!$ by $k+1$.

Both of these methods allow us to derive the following general formula for $a_k$:
$$a_k = [a/k!] - [a/(k+1)!] (k+1).$$

6) We will sequentially split the segment [0; 1]: at the 1st step - into 2 equal parts, at the 2nd step of each of the two formed segments - into 3 equal parts, etc. In general, at the $k$-th step of each of the segments obtained at the $(k-1)$-th step, we split into $k+1$ equal parts. It is clear that after the $k$th step the segment [0; 1] will be divided into $(k+1)$ equal parts.

Consider the partition point $r$, which first appeared at the $n$th step (obviously $r=m/(n+1)!$, where $m$ is not divisible by $n+1$). This point is distant from the point of the $(n-1)$-th step closest to it on the left by the amount $b_n/(n+1)!$, where $b_n$ is an integer, $0 < b_n \leq n$. In turn, this point of the $(n-1)$th step is distant from the point of the $(n-2)$th step closest to the left by $b_{n-1}/n!$, where $0 \leq b_{n-1} \leq n-1$, etc. As a result, we get the representation
$$r = \frac{b_1}{2!} + \frac{b_2}{3!} + \dots + \frac{b_n}{(n+1)!}, 0 \leq b_k \leq k, b_n \neq 0.$$

(**)

Its only consequence is that for any set of $b_1, \dots, b_n$ in (**) the numbers
$$\frac{b_1}{2!}, \frac{b_1}{2!} + \frac{b_2}{3!}, \dots, \frac{b_1}{2!} + \frac{b_2}{3!} + \dots + \frac{b_n}{(n+1)!}$$

are obtained, accordingly, no later than at the 1st, 2nd, ..., $n$-th steps of the partition, and (due to inequalities $0 \leq b_k \leq k$) each of them is closest to the left to the next one among all numbers of the same step.

It remains to note that any different number $r=p/q$ from the interval [0; 1] will appear as a partition point no later than at the $(q-1)$th step, since $r=p(q-1)/q!$.

In fact, in this solution the coefficients $b_1, \dots, b_n$ are determined sequentially starting from $b_n$: if $b_n, \dots, b_k$ have already been found, then $b_{k-1}$ is the remainder of the division of the (integer!) number
$$\left(r - \frac{b_n}{(n+1)!} - \dots - \frac{b_k}{(k+1)!}\right) \cdot k!$$ to $k$. Think about how you can find
Dial these coefficients starting from $b_1$. Check if the following formula is correct:
$$b_k = [r \cdot (k+1)!] - [r \cdot k!](k+1)$$
(you can use the second identity in the margins).

c) Answer: 1984 = 2 2! + 3·3! + 2·4! + 4·5! + 2 6!, 19/84 = 1/3! + 1/4! + 2/5! + 6/7!. These representations are easy to find based on the solutions to points a) and b).

V. E. Kolosov

♦ Answer: for any even $n$.

figure 2 shows how to form a centrally symmetrical figure from any even number $n$ of corners (corner $4 \times n$). Let us show that, conversely, any centrally symmetric figure $f$ from the condition can contain only an even number of angles. Let us give two proofs.

⟦folio 38⟧

The first is based on traditional Olympic ideas - coloring and parity. The center of symmetry $O$ of the figure $\Phi$ is one of the centers of symmetry of the corresponding square grid, that is, either its node, or the middle of the segment between two adjacent nodes, or the center of the cell. Lastly, the number of cells in the figure would be odd, but it should be divisible by 4. Let's paint the plane “with a blue stripe”, as shown in figure 3. Then the number of blue cells in the figure $\Phi$ will be even. (Depending on the location of the center $O$, either each blue cell of symmetrine is white - as for centers $O_1$ and $O_2$ on figure 3, $a$, and then the number of blue cells in $\Phi$ is equal to half the total number of cells, a multiple of four; or each blue cell of symmetrine is another blue - as for the point $O_3$ on figure 3, $a$.) But in any rectangle $4 \times 1$ on the grid the number of blue cells is even (Fig. 3, $a$), and in any corner it is odd (Fig. 3, $6$). Therefore, the number of corners must be even.

The second proof is based on the fact that the center of symmetry $O$ of the figure $\Phi$ is also its center of mass (if we consider it as a homogeneous plate; we can also replace $\Phi$ with a finite system of equal masses concentrated at the centers of the cells composing this figure). As we saw above, at least one of the grid lines passes through the point $O$; Let's take it as the ordinat axis, and as the abscissa axis - any pre-predilcular grid line. The unit of length will be the side of the cage. In these axes, the coordinates of the point $O$, as well as the center of mass of any rectangle $4 \times 1$ will be integers or obtained, that is, numbers of the form $a/2$, where $a$ is an integer. The center of mass of the corner lies in the middle of the segment connecting the centers of the two rectangles $2 \times 1$ from which it is composed (Fig. 4), therefore its coordinates have the form $b \pm 1/4$ ($b$ is an integer). Let us now take advantage of the fact that if we replace each figure - rectangles and angles that make up $\Phi$, with its center of mass and place equal masses at these centers, then the center of the resulting new system also falls at point $O$. This means that the coordinates of point $O$ are equal to the arithmetic mean of the corresponding coordinates centers of the masses of all figures making up $\Phi$. Consequently, the sum of the abscissas of these centers, that is, the sum of several numbers of the form $a/2$ and $n$ numbers of the form $b \pm 1/4$, must be equal to zero. But this, very much, is possible only with even $n$.

For the second proof to become completely rigorous, we must also give an exact mathematical definition of the center of mass and prove our use of its properties, for example, the lawfulness of replacing a certain group of masses with its center. This is discussed in detail in the article by M. B. Balk and V. G. Boltyansky in this issue of the magazine.

V. G. Belov

F852. On a horizontal non-conducting plane without piercing a uniform loaded ring of mass $m$. After turning on a horizontal magnetic field with induction $\vec{B}$, redistributing the plane of the ring, the force of pressure of the ring on the plane was halved. At what speed did the ring roll if its charge is $q$?

The change in the pressure force of the ring on the plane is due to the action of a certain force on the ring from the magnetic field. Let's find this strength.

Let's consider two small diametrically opposite sections of the ring near points $A$ and $C$ (see Fig.ok). Since point $O$ is the instantaneous center of rotation of the ring, the instantaneous velocities of points $A$ and $C$ are equal to the corresponding

$$v_A = \frac{v}{R} |OA| = \frac{v}{R} 2R \cos \frac{\alpha}{2} = 2v \cos \frac{\alpha}{2},$$

$$v_C = \frac{v}{R} |OC| = 2v \sin \frac{\alpha}{2},$$

where $R$ is the radius of the ring. Vectors $\vec{v}_A$ and $\vec{v}_C$ redistribute the corresponding segments $OA$ and $OC$. Let the charge of each section be $\Delta q$. Since the areas are small, these charges can be considered precise. The Lorentz forces acting on each charge from the magnetic field are equal to

$$F_A = \Delta q \cdot B2v \cos \frac{\alpha}{2},$$

$$F_C = \Delta q \cdot B2v \sin \frac{\alpha}{2}.$$

Vectors $\vec{F}_A$ and $\vec{F}_C$ are directed along the segments $OA$ and $OC$ and the composition

⟦folio 39⟧

They lay at horizontal angles equal to, respectively,

$$\beta = \frac{\alpha}{2} + \left( \frac{\pi}{2} - \alpha \right) = \frac{\pi}{2} - \frac{\alpha}{2},$$

$$\gamma = \frac{\pi}{2} - \left( \frac{\pi - \alpha}{2} \right) = \frac{\alpha}{2}.$$

In the projection onto the horizontal, the resulting force acting on both parts is equal to

$$\dot{f}_x = \Delta q \cdot 2Bv \left( \cos \frac{\alpha}{2} \sin \frac{\alpha}{2} - \sin \frac{\alpha}{2} \cos \frac{\alpha}{2} \right) = 0,$$

and in projection onto the vertical

$$\dot{f}_y = \Delta q \cdot 2Bv \left( \cos^2 \frac{\alpha}{2} + \sin^2 \frac{\alpha}{2} \right) = \Delta q \cdot 2Bv.$$

Considering similarly each pair of diametrically opposite parts, we find that the horizontal projection of the force acting on the stake from the magnetic field is equal to zero, and the vertical projection is equal to

$$F_y = \sum_i F_{yi} = 2vB \sum_i \Delta q_i,$$

where $\sum_i \Delta q_i$ is the sum of the charges of all elements of the particles that make up half of the ring, that is, $\sum_i \Delta q_i = \frac{q}{2}$. Thus,

$$F_y = qvB.$$

Let us write down the equilibrium condition of the ring in projection onto the vertical:

$$mg = N + qvB.$$

According to the conditions of the problem $N = mg/2$ and, therefore,

$$qvB = mg/2.$$

From here

$$v = mg/2qB.$$

L. G. Markovich

◆ When a force $F_1$ is applied to the center of the right wall, the container will move when this force becomes equal to the frictional force $\mu N'_1$ acting on the fixed supports. So the force of floor pressure on these supports is -

$$N_1 = F_1/\mu.$$

The total moment of forces relative to the axis passing through the rollers must be equal to zero (the container does not tip over). Therefore (see Fig. 1)

$$\frac{mg l}{2} - \frac{F_1 l}{2} - N_1 l = 0.$$

From here, taking into account the fact that $N_1 = F_1/\mu$, we obtain:

$$mg = F_1 \left( 1 + \frac{2}{\mu} \right).$$

When a force $F_2$ is applied to the center of the left face (Fig. 2), the pressure force of the floor on the fixed supports is equal to $F_2/\mu$. The equality to zero of the total torque about the axis passing through the rollers leads to compliance with the corresponding one.

$$mg = F_2 \left( \frac{2}{\mu} - 1 \right).$$

($F_2 > F_1$, because in the second case the moment of force $F_2$ leads to an additional load on the fixed supports, and therefore to an increase in the friction force.)

Solving (1) and (2) together, we find $m$:

$$m = \frac{2F_1 F_2}{g (F_2 - F_1)}.$$

Some refrigerators have the same support structure as our container. They move easily towards the rollers and much more difficult in the opposite direction. Sometimes the refrigerator does not want to slide at all, but begins to tip over. This occurs at a certain value of the friction coefficient. In the case of a “cubic” refrigerator with a uniform distribution of mass - at $\mu \geq 1$. The limit value $\mu$ is obtained

⟦folio 40⟧

F854. Estimate the average force that must be applied to the edge of the air mattress in order to sleep it in the middle under a straight edge. The mattress has no lateral overloads. Set the quantities necessary for the solution and their fairly realistic numerical values ​​yourself and get a numerical result.

Let's estimate the work that needs to be done to fit the mattress at a right angle. In order of magnitude, it can be estimated as $A \sim p \cdot \Delta V$, where $p$ is the difference between atmospheric pressure and air pressure inside the mattress, $\Delta V$ is the change in the volume of the mattress during the process of its deformation. As can be seen from figure, $\Delta V$ is approximately equal to the product of the area of ​​the triangle $ABC$ and the width of the mattress $b$:

$$\Delta V \approx \frac{2d \cdot d}{2} b = d^2 n,$$

where $d$ is the thickness of the mattress.

On the other hand, the work of bending a mattress can be estimated as the product of the average force $F_{cp}$ and the distance traveled:

$$A \approx F_{cp} \frac{2\pi l}{4} \sim F_{cp} l$$

(l is the length of the mattress).

From the above expressions it follows that

$$A \sim p \cdot \Delta V \sim p d^2 b \sim F_{cp} l,$$

where

$$F_{cp} \sim \frac{p d^2 b}{l}.$$

For numerical calculations, you can put $b \approx 0,8$ m, $d \approx 0,15$ m, $l \approx 2$ m. It is more difficult to estimate $p$. Let's use this idea. If you stand on the mattress with your feet, then it most often continues to the ground. Therefore, $p$ is of the same order as the pressure exerted by a person’s feet on the ground:

$$p \sim \frac{mg}{S} \sim \frac{700 \text{ H}}{0,2 \cdot 0,3 \text{ m}^2} \sim 10^4 \text{ Pa}.$$

We finally calculate:

$$F_{cp} \sim \frac{10^4 \Pi a \cdot (0,15 \text{ m})^2 \cdot 0,8 \text{ m}}{2 \text{ m}} \sim 10^2 \text{ H},$$

which agrees well with our everyday experience.

E. I. Palchikkov

F855. A flat capacitor connected to the pole of a battery with emf $\delta$ was completely inserted parallel to its plates by a charged plate at a distance $b$ from one of the plates of the capacitor (see figure). Find the force acting on the input plate if its charge is $q$. Run next. The area of ​​the capacitor plates is $S$, the distance between them is $d$.

The electric field inside the capacitor is the sum of the field created by the plate with charge $q$ and the field created by the charges of the capacitor plates. For example, these fields are designated corresponding to $E$ and $E_1$. (On figure the directions of the fields $E$ and $E_1$ are indicated for the case of positive charges entering the plate.)

The force acting on the insertion plate is equal to

$$F = q E_1.$$

The voltage $E_1$ can be found by writing the potential difference between the capacitor plates in the form

$$\delta = (E_1 + E)(d - b) + (E_1 - E) b.$$

From here

$$E_1 = \frac{\delta + E(2b - d)}{d}.$$

Substituting $E = q/2\varepsilon_0 S$, we get:

$$E_1 = \frac{\delta + q(2b - d)}{2S\varepsilon_0}.$$

Thus, the force acting on the insertion plate is
