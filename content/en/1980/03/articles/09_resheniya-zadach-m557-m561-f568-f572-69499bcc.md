---
id: 1980-3-resheniya-zadach-m557-m561-f568-f572-69499bcc
issue: kvant_1980_3
year: 1980
number: "3"
title: Solutions to problems M557—M561; F568—F572
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 30
page_last: 37
page_labels: 28-35
tag: 0U9H
lang: en
source: kvant_digital
extraction: vision
content_sha256: 8cea40b2e6a3c2a76cba916f0bbe78420d9a8e66294cd1956d57e49e4d923947
prompt_sha256: draft-1
translated_from: content/ru/1980/03/articles/09_resheniya-zadach-m557-m561-f568-f572-69499bcc.md
source_content_sha256: 486cf43cd1eb10840c79fd61df7262c928e3a39f76f069b2d53c241290ccb2cf
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 28⟧

Problem solutions
M557—M561; F568—F572

M557. Given n in pairs of prime numbers greater than 1 and less than (2n-1)². Prove that among them there will definitely be a prime number.

We prove the statement of the problem using the method “by contradiction”. Let us assume that all given numbers $a_1, a_2, \dots, a_n$ are composite. Let us associate to each of them its minimal prime divisor: $a_i \rightarrow q_i$. Let $q = \max_{1 \leq i \leq n} \{q_i\}$. then $q \geq p_n$, where $p_n$ is an n-e prime number (since the numbers $a_1, \dots, a_n$ are mutually prime in pairs).

Indication on $k$ easily proves the inequality $p_k \geq 2k - 1$. (Indeed, it is true for $p_2 = 3$. Then $p_{k+1} \geq p_k + 2$ for $k \geq 2$.) Thus $q \geq 2n - 1$. Therefore, for that $a_j$ for which $q_j = q$,

$$a_j \geq q_j^2 \geq (2n-1)^2$$

- a contradiction. This means that among these numbers there will definitely be a prime.

A. Kolotov

M558. There are $k > 1$ black sectors in the circle, whichever of them is less than $180^\circ / (k^2 - k + 1)$. Prove that the circle can be rotated around the center O so that all the black sectors go to the white part of the circle.

Fig. 1.

Let two circles be folded together, on one of which there are r black sectors with central angles $a_1, a_2, \dots, a_r$, on the other - s blue ones with angles $\beta_1, \beta_2, \dots, \beta_s$ (Fig. 1). Let's try to find decent conditions under which the circle with blue sectors can be rotated by such an angle $\varphi$ ($0 < \varphi < 2\pi$) that none of the blue sectors intersect with the black ones.

It is convenient to mark the rotation angles $\varphi$ on a special circle $c$ of length $2\pi$ with a given point 0 (zero) on it. Let's turn the problem around differently. Let's mark on $c$ all the forbidden angles $\varphi$ - those, when turning through which some blue radius coincides with some black one. Each pair (black sector with angle $a_i$, blue sector with angle $\beta_j$) gives an interval of forbidden $\varphi$ of length $a_i + \beta_j$. Therefore, if what is $a_i < \pi/k$, in particular, if what is $a_i < \pi/k^2$. It is also possible to prove the statement for sectors with angles $a_i < \gamma = \pi / (k^2 - k + 1)$, but in this case we can refine the estimate

*) Summation $\sum_{i,j} \text{ произвольных } i = 1, 2, \dots, r, j = 1, 2, \dots, s$.

Fig. 2.

⟦folio 29⟧

length of the “forbidden” set. All “forbidden” intervals corresponding to the parameters of the matching sectors ($\alpha_i, \alpha_i$) are contained in one interval of length $2\gamma$ with center $O$. And the sum of all other values ​​of forbidden angles

$$\sum_{i,j,i \neq j} (\alpha_i + \alpha_j) = 2(k-1)\sum_i \alpha_i$$

variable $2(k-1)k\gamma = 2\pi - 2\gamma$, so in this case there is a “non-forbidden” value $\varphi$.

The problem is a solution, but the question arises: is it possible to raise the bounds for $\alpha_i$? The statement of the problem, generally speaking, does not hold true if the angles of all $k$ sectors are taken to be equal in magnitude to $\gamma = \pi/(k^2-k+1)$. Refuting examples for $k=2, 3, 4, 5$ are very interesting (Fig. 2): red points - the ends of bisectors of sectors - must be located at $k$ vertices of a regular ($k^2-k+1$)-gon, chosen so that for any $m=1, 2, ..., k^2-k$ there is a pair of red points between which $m$ sides are located (in one direction or another along the circle) ($k^2-k+1$)-gon. Check that then the “forbidden set” is all $\varphi \in [0; 2\pi]$.

The problem itself is a combinatorial problem: for what $k$ can we arrange $k$ red points on a circle of length $2C_k^2+1=k^2-k+1$ so that for any $m=1, 2, ..., k^2-k$ there is a pair of red points between which $m$ sides of a ($k^2-k+1$)-gon are located (in one direction or another along the circle). Check that then the “forbidden set” is all $\varphi \in [0; 2\pi]$.

The problem itself is a combinatorial problem: for what $k$ can we arrange $k$ red points on a circle of length $2C_k^2+1=k^2-k+1$ so that for any $m=1, 2, ..., k^2-k$ there is a pair of red points between which $m$ sides of a ($k^2-k+1$)-gon are located (in one direction or another along the circle). Check that then the “forbidden set” is all $\varphi \in [0; 2\pi]$.

Let for some $k$ such a red set $\Pi_0$ exist. Then $\Pi_0$ and its images $\Pi_m$ ($m=1, 2, ..., k^2-k$), when rotated by angles $m\gamma, \gamma=\pi/(k^2-k+1)$, have the following properties:

1°. For any $i \neq j$ the intersection $\Pi_i \cap \Pi_j$ consists of one point.

2°. Any two points in the set $\Pi = \bigcup_m \Pi_m$ (the vertices of a regular ($k^2-k+1$)-gon) belong to exactly one of $\Pi_m$.

3°. There are four points of the set $\Pi$ that are not contained in one $\Pi_i$.

The set $\Pi$ with such a subset system $\Pi_m \subset \Pi$ is called a finite projective plane*). It is known that finite projective planes exist for $k=p^r+1$, where $p$ is a prime, $r$ is a natural number (for example, $k=3, 4, 5, 6, 8, 9$) and does not exist if $k=7, 15$; It's clear; now that in the latter case there cannot be a refuting example in problem M558 (so, for example, for seven sectors with angles $\pi/43$ her statement is true). But already for $k=10$ the issue cannot yet be solved even with the help of a computer.

Note that a finite projective plane is not required, and such a “cyclic” numbering of points is not required, in which the lines $\Pi_m$ are obtained from each other with two numbers - this additional requirement may make it easier to prove the absence of such “cyclic planes” for some $k$. (Note that all projective planes over a finite field of $p^r$ elements have such cyclic numbering; see about this in the chapter “Difference Sets” of M. Hall’s book.)

N. Vasiliev, G. Galperin, V. Proizvolov

*) We have already encountered in «Kvant» that problems of different contents affect this concept - see, for example, problem M5, («Kvant», 1970, No. 1) and M335 («Kvant», 1975, No. 7). The number $n=k-1$ is called the "order" of the projective plane; here $k=n+1$ is the number of a point on the “line” $\Pi_n$ (and the number of “lines” passing through a given point; these numbers are always the same for all points and “lines”). For information on finite projective planes, see E. Artin’s book “Geometric Algebra” (M., “Nauka”, 1969) and M. Hall’s book “Combinatorics” (M., “Mir”, 1970).

⟦folio 30⟧

M559. Prove that if $x, y, z$ is the length of a side of a triangle, then

$$\left| \frac{x}{y} + \frac{y}{z} + \frac{z}{x} \right| - \frac{y}{x} - \frac{z}{y} - \frac{x}{z} < 1.$$

It is convenient to factor the left side:

$$B = \left| \frac{x}{y} + \frac{y}{z} + \frac{z}{x} \right| = \frac{\left| z \left( x^2 - y^2 \right) + x \left( y^2 - z^2 \right) \right|}{xyz} = \frac{\left| (y-z) \left( z-x \right) \left( x-y \right) \right|}{xyz}.$$

$B < 1$ because $|y-z| < x$, $|z-x| < y$ and $|x-y| < z$.

You cannot reduce the score of 1: for example, with $x = \varepsilon$, $y = 1 + \varepsilon^2$, $z = 1 + \varepsilon$ ($\varepsilon$ is a small positive number) $B$ will be greater than $(1-\varepsilon)^3$.

V. Senderov

M560. There is a hole in the bottom of the box. It is necessary to make a convex flap of the smallest area, in any position of which the hole at the bottom of the box will be closed. Solve this problem if:

a) the bottom of the box is a square $4 \times 4$, and the hole is located as shown in figure 1.

b) the bottom of the box is a square $n \times n$ ($n$ is odd), and the hole is located in the center (Fig. 2).

Fig. 1.

Fig. 2.

Fig. 3.

14 in the form of a convex octagon, composed of the above squares and triangles (it is highlighted at figure 3), always covers the square $A_1$. Therefore, it is an exception.

6) Let us assume that we have a convex shutter, in any position of which at the bottom of the box $n \times n$ the hole $A$ is completely closed.

Consider the smallest rectangle $P$ with sides parallel to the sides of the square, containing our shutter. Let its dimensions be $(n-x) \times (n-y)$. In parallel with moving $P$ together with the flap, it is easy to make sure that all rectangles obtained by moving the cell $A$ to a distance of no more than $x$ left-right and $y$ up-down should be covered by the flap; The side lengths of this rectangle are $u = 1+x$, $v = 1+y$. In addition, there must be a flapper point on each side of $P$; therefore, the flap must include at least four more triangles (Fig.4) with a total area of ​​$(n-u-x)v/2 + (n-v-y)u/2$. So, the damper area is no less

$$uv + (n-u-x)v/2 + (n-v-y)u/2 = (n-x)(1+y)/2 + (n-y)(1+x)/2 = n + x(n-y-1)/2 + y(n-x-1)/2 \geq n.$$

(after all, obviously, $x$ and $y$ do not even exceed $(n-1)/2$).

figure 5 shows the figure $M$, which always covers the central square $A$. Its area is obviously

⟦folio 31⟧

Fig. 5.

M561. Two triangles $A_0B_0C_0$ and $A_1B_1C_1$, the areas of which are $S_0$ and $S_1$, are arranged so that the rays $A_0B_0$ and $A_1B_1$, $B_0C_0$ and $B_1C_1$, $C_0A_0$ and $C_1A_1$ are parallel but opposite in direction. Find the area of ​​a triangle with vertices at the midpoints of segments $A_0A_1$, $B_0B_1$, $C_0C_1$.

Fig. 1.

Fig. 2.

Fig. 3.

equal to $n$, that is, the minimum possible. Thus, this is the desired barrier.

Note that the solution did not use that the side of the square $n$ is an integer, only that $n > 1$ is important.

It would be interesting to solve this problem for other pairs of figures; for example, it is quite plausible that if the “hole” and the “bottom of the box” are concentric circles of radii $r$ and $R$, then the convex barrier of the smallest area is the smallest convex figure containing the smaller circle and the diameter of the larger circle (whose area is equal to $2r\sqrt{R_2-r^2}+2r^2\arcsin r/R$).

V. Batyrev

◆ Answer. Required area

$$S = \left( \frac{\sqrt{S_0}-\sqrt{S_1}}{2} \right)^2.$$ (1)

From the conditions of the problem it follows that the triangles $A_0B_0C_0$ and $A_1B_1C_1$ are prepared (Fig. 1), and the coefficient of preparation is negative and is equal in modulus

$$k = \frac{|A_1B_1|}{|A_0B_0|} = \frac{|B_1C_1|}{|B_0C_0|} = \frac{|C_1A_1|}{|C_0A_0|} = \frac{\sqrt{S_1}}{\sqrt{S_0}}.$$

Let $O$ be the center of this readiness, that is

$$\overrightarrow{OA}_1 = -k\overrightarrow{OA}_0, \overrightarrow{OB}_1 = -k\overrightarrow{OB}_0, \overrightarrow{OC}_1 = -k\overrightarrow{OC}_0.$$

Then, if $A, B, C$ are the midpoints of the segments $A_0A_1$, $B_0B_1$, $C_0C_1$, respectively, then

$$\overrightarrow{OA} = (\overrightarrow{OA}_0 + \overrightarrow{OA}_1)/2 = \overrightarrow{OA}_0(1-k)/2$$

and similarly

$$\overrightarrow{OB} = \overrightarrow{OB}_0(1-k)/2, \quad \overrightarrow{OC} = \overrightarrow{OC}_0(1-k)/2.$$

Consequently, triangle $ABC$ is matched to triangle $A_0B_0C_0$, and the coefficient modulo is equal to $\frac{|1-k|}{2}$; That's why

$$\frac{\sqrt{S}}{\sqrt{S_0}} = \frac{|1-k|}{2} = \frac{|1-\sqrt{\frac{S_1}{S_0}}|}{2} = \frac{\sqrt{S_0}-\sqrt{S_1}}{2\sqrt{S_0}}.$$

From this follows formula (1).

Note $1^\circ$. Triangles $A_0B_0C_0$ and $A_1B_1C_1$ can lie in parallel planes; the plane of the triangle $ABC$ will also be parallel to them. All the above explanations and answer (1) remain valid.

$2^\circ$. Our solution is closely related to this useful fact: the segment $AB$, connecting the midpoints of the diagonals $A_0A_1$ and $B_0B_1$ of the trapezoid with the bases $A_0B_0$ and $A_1B_1$, is parallel to the bases and is equal in length to half the difference in their lengths (Fig. 2).

$3^\circ$. Let the points $A_t, B_t, C_t$ divide the segments $A_0A_1$, $B_0B_1$, $C_0C_1$ in the same given ratio; let, for example,

$$\frac{\overrightarrow{A_0A_t}}{\overrightarrow{A_0A_1}} = \frac{\overrightarrow{B_0B_t}}{\overrightarrow{B_0B_1}} = \frac{\overrightarrow{C_0C_t}}{\overrightarrow{C_0C_1}} = t.$$

Then the area $S_t$ of the triangle $A_tB_tC_t$ will be expressed by formula (1) (corresponding to the ray $t = 1/2$). Think about what happens with $t = \frac{\sqrt{S_0}}{\sqrt{S_0}+\sqrt{S_1}}$.

$4^\circ$. The fact that there are triangles in the data problem is not significant; triangles can be replaced

⟦folio 32⟧

Fig. 4.

F568. When a front target is bombarded with protons with an energy of at least 1.88 MeV, a nuclear reaction can occur

$$7\text{Li} + p \rightarrow 7\text{Be} + n.$$

At what energy of the protons produced in the reaction can neutrons fly backward from the front target?

we are other figures, ready-made relative to some center $O$. More precisely: let a point $O$ be given and a point $A_0$ describe some closed non-self-intersecting curve enclosing a figure of area $S_0$ (see Fig. 3).

At the same time, the point $A_1$, defined by the vector $\overrightarrow{OA}_1 = -k \cdot \overrightarrow{OA}_0$, $k = \sqrt{S_1/S_0}$, describes another curve (encompassing the figure of area $S_1$). Then the midpoint $A$ of the segment $A_0A_1$ will describe a curve enclosing the figure of area (1). Similarly, the point $A_t$ such that $\overrightarrow{A_0A_t} = t\overrightarrow{A_0A_1}$ (that is, $\overrightarrow{OA_t} = t\overrightarrow{OA_0} + (1-t)\overrightarrow{OA_1} = (t-k+kt)\overrightarrow{OA_0}$; $t$ is a fixed number) will describe a curve enclosing a figure of area determined by formula (2).

$$S_{KLMNPQ} = \left( \frac{\sqrt{S_0} + \sqrt{S_1}}{2} \right)^2.$$

(cf. formula (1))*).

L. Kuptsov

According to the laws of conservation of energy and momentum

$$E_p = E_{\text{Be}} + E_n + Q,$$

(1)

$$\vec{p}_p = \vec{p}_{\text{Be}} + \vec{p}_n,$$

(2)

where $E_p$, $E_{\text{Be}}$, $E_n$ are the energies of the proton, beryllium nucleus and neutron, respectively, $\vec{p}_p$, $\vec{p}_{\text{Be}}$, $\vec{p}_n$ are the momenta of these particles. At the proton energy $E_p = E_0 = 1,88$ MeV, the total energy $E$ of the beryllium nucleus and neutron is minimal. Let's find her.

To do this, consider the process in the reporting system, moving at the speed of the center of mass of the proton system - the lithium nucleus. In this system, a proton and a lithium nucleus move towards each other. At the minimum possible energy of interacting particles (proton and lithium nucleus), the energy of the beryllium nucleus and neutron formed during the reaction is zero - these particles are at rest.

Now let's move on to the reporting system in which the lithium target is motionless. In this system, a beryllium nucleus and a neutron, formed as a result of bombardment of a target by a proton with energy $E_p = E_0$, move as one with a speed equal to the speed of the center of mass of the proton-lithium nucleus system. Their total energy $E$, according to the law of conservation of energy, is determined by the equality

$$E_0 = E + Q,$$

(1')

and their total momentum $\vec{p}$, according to the law of conservation of momentum, is equal to

$$\vec{p} = \vec{p}_0$$

(2')

($\vec{p}_0$ is the momentum of a proton with energy $E_0$). Considering that the momentum of a particle and its energy are related by the relation $p = |\vec{p}| = \sqrt{2mE}$ ($E = \frac{mv^2}{2} = \frac{(mv)^2}{2m} = \frac{p^2}{2m}$), we can rewrite equality (2') as follows:

$$\sqrt{2mE_0} = \sqrt{2(m+M)E}$$

(here $m$ denotes the mass of the proton and the mass of the neutron, $M$ the mass of lithium and the mass of the beryllium nucleus). From here comes $E = \frac{m}{m+M} E_0$. Substituting this value into (1'), to

*) Note ed. I talk about far-reaching generalized formulas in the article “Family of parallel $n$-gons” («Kvant», 1974, No. 11).

⟦folio 33⟧

go value $Q$:

$$Q = \frac{M}{m+M} E_0.$$

Thus, at the proton energy $E_p > E_0$, we can write the energy conservation law (1) as follows:

$$E_p = E_{\text{Be}} + E_n + \frac{M}{m+M} E_0.$$

(3)

If the formation as a result of the reaction, the neutron flies back from the cast target, then the law of conservation of momentum (2) can be written as follows:

$$p_p = p_{\text{Be}} - p_n (p = |\vec{p}|),$$

or

$$\sqrt{2mE_p} = \sqrt{2ME_{\text{Be}}} - \sqrt{2mE_n}.$$

(4)

From equality (4) we find

$$E_{\text{Be}} = \frac{m}{M} (E_p + E_n + 2\sqrt{E_p E_n})$$

and substitute this value into (3). As a result we get

$$E_p = E_n + \frac{m}{M} (E_p + E_n + 2\sqrt{E_p E_n}) + \frac{M}{m+M} E_0.$$

From the last equality it is clear that $E_p$ is minimal at $E_n = 0$. At the same time

$$E_p = \frac{M^2}{M^2 - m^2} E_0 \approx 1,92 \text{ (МэВ)}.$$

Thus, at $E_p \approx 1,92 \text{ МэВ}$ the neutron produced in the reaction will end. At $E_p > 1,92 \text{ МэВ}$ the neutron can fly backward from the cast target.

I. Slobodetsky

◆ Let us denote by $\tau_1$ the water heating time ($\tau_1 = 2$ min). From the law of conservation of energy it follows that

$$W\tau_1 = cm (t_2 - t_1) + Q_1,$$

(*)

where $m$ is the mass of water, $Q_1$ is the energy loss associated with heat transfer in the surrounding space. $Q_1$ is proportional to time $t_1$ and the temperature difference between the water and the environment.

When the water remains (when the heating is turned off), the energy released in the surrounding space is equal to

$$Q_2 = cm \Delta t,$$

where $\Delta t = 1^\circ\text{C}$ is the change in water temperature over time $\tau_2 = 1$ min. Since the temperature difference between water and the environment changes slightly, but $\tau_2 = 0,5\tau_1$, $Q_2 = 0,5Q_1$, so

$$Q_1 = 2Q_2 = 2cm \Delta t.$$

Substituting this expression for $Q_1$ into equality (*), we obtain

$$W\tau_1 = cm (t_2 - t_1 + 2\Delta t).$$

From here

$$m = \frac{W\tau_1}{c(t_2 - t_1 + 2\Delta t)} \approx 1,8 \text{ кг}.$$

E. Surkov

◆ Let's draw a graph of the dependence $\varphi(x)$. The graph shows that at first the potential is negative, then it begins to increase. It is minimal at $x = 1$ mm, $\varphi_{\text{min}} = 1$ V. This means that at first (at small $x$), while the potential decreases, the electric field when moving an electron does negative work and turns into moving the electron. At $x > 1$ mm, when the potential begins to increase, the field

⟦folio 34⟧

Rakh, f - in volts). The distance between the cathode and anomal d = 10 mm. The x coordinate coincides with the distance to the cathode. Determine at what minimum kinetic energy an electron from the surface of Katoda can reach the anode. What will be the maximum acceleration of electrons that reach the anode?

$$W_{\min} = e\varphi_{\min} = 1 \text{ эВ.}$$

The acceleration of an electron is determined by the force acting on the electron, that is, the field strength. Therefore, the acceleration of the electron is maximum at the point at which the maximum voltage is the electron, directed opposite to the field.

Since $\Delta\varphi = E\Delta x$,

$$E = \frac{\Delta\varphi}{\Delta x} = \frac{(x + \Delta x)^2 - 2(x + \Delta x) - (x^2 - 2x)}{\Delta x} = \frac{2x\Delta x + (\Delta x)^2 - 2\Delta x}{\Delta x}.$$

For small $\Delta x$ we can neglect $\Delta x^2$, so

$$E(x) = 2x - 2 \quad (x - \text{в мм}, E - \text{в В/мм}).$$

The field is directed from the cathode to the anom at $x < 1$ mm and from the anom to the cathode at $x > 1$ mm. Since the electron's charge is negative, the force acting on the electron is directed opposite to the field.

So, voltage is an electrostatic field proportional to the coordinate. It is maximum at $x = d$ and is equal to $E_{\max} = 18 \text{ В/мм}$. Consequently, at $x = d$ the acceleration of the electron is maximum and equal to

$$a = \frac{F}{m} = \frac{eE}{m} \approx 3.2 \cdot 10^{15} \text{ м/c}^2.$$

♦

1) Let us take the directions of the currents through the resistors as shown in figure 1, and denote $U$ the direction between points $A$ and $B$. Then

$$U = -\mathcal{E}_1 + I_1R_1, \quad (1)$$

$$U = \mathcal{E}_2 + I_2R_2, \quad (2)$$

$$U = -\mathcal{E}_3 + I_3R_3, \quad (3)$$

$$U = \mathcal{E}_4 + I_4R_4. \quad (4)$$

Since the sum of currents arriving at point $B$ is zero (charge does not accumulate at point $B$), then

$$I_1 + I_2 + I_3 + I_4 = 0. \quad (5)$$

From the system of equations (1)–(5) it is not difficult to find the points and direction $U$. To do this, let’s substitute into equation (1)–(4) the known values ​​of emf (in volts) and resistance (in ohms):

$$U = -1 + I_1,$$

$$U = 2 + 2I_2,$$

$$U = -3 + 3I_3,$$

$$U = 4 + 4I_4,$$

$$I_1 + I_2 + I_3 + I_4 = 0.$$

Solving this system, we find

$$U + \frac{1}{2}U + \frac{1}{3}U + \frac{1}{4}U = 0 \Rightarrow U = 0.$$

Pozny

$$I_1 = 1\text{ А}; I_2 = -1\text{ А}; I_3 = 1\text{ А}; I_4 = -1\text{ А}.$$

(Currents $I_2$ and $I_4$ are directed opposite to the arrows.) If the wires are cut at points $A$ and $B$, then

$$-\mathcal{E}_1 + I_1R_1 = \mathcal{E}_2 + I_2R_2,$$

$$I_1' + I_2' = 0,$$

So

$$I_1' = 1\text{ А}, I_2' = -1\text{ А};$$

⟦folio 35⟧

similarly

$$\frac{\delta h_1}{\Delta h_2} = \left( \frac{r_2}{r_1} \right)^3$$

Since the cube of the radius is proportional to the mass of the particle,

$$\frac{\Delta h_1}{\Delta h_2} = \frac{m_2}{m_1}$$

($m_1, m_2$ are the masses of gummigut particles with radii $r_1$ and $r_2$, respectively).

The change in the density of oxygen in the atmosphere with altitude is similar to the change in the number of gum particles with altitude. From Fig. 2 it is clear that the oxygen density decreases as the altitude changes by $\Delta H = 5,5$ km. That's why

$$\frac{\Delta h_1}{\Delta H} = \frac{m}{m_1},$$

where $m$ is the mass of an oxygen molecule. From here

$$m = m_1 \frac{\Delta h_1}{\Delta H} = \frac{4}{3} \pi r_1^3 q_r \frac{\Delta h_1}{\Delta H} \approx 5,8 \cdot 10^{-26} \text{ кг}.$$

I. Slobodetsky
