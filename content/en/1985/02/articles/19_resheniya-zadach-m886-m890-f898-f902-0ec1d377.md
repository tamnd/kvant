---
id: 1985-2-resheniya-zadach-m886-m890-f898-f902-0ec1d377
issue: kvant_1985_2
year: 1985
number: "2"
title: Solutions to problems M886—M890; F898—F902
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 42
page_last: 49
page_labels: 40, 41, 42, 43, 45, 46, 47
tag: 8N8U
lang: en
source: kvant_digital
extraction: vision
content_sha256: af2859a727a286b7d3a9652c624047e383fbf754f5c75db8e6d1c3675772f791
prompt_sha256: draft-1
translated_from: content/ru/1985/02/articles/19_resheniya-zadach-m886-m890-f898-f902-0ec1d377.md
source_content_sha256: d07d4d8f0b8e9d69491e443d048065e2b414866c721e7bd893fbe15647788b3c
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 40⟧

P921. A flat capacitor is connected to a source of tension $U$. The capacitor’s plates are of area $S$ each, the distance between them is $d_1$. A metal plate of area $S$, mass $m$ and thickness $d_2$ is pressed against one of the capacitor’s plates (Fig. 4). Then the metal plate is released. With what velocity will it hit the capacitor’s other plate?

P922. In order to get close up of an ant, a photographer added a cylindrical extension to his camera, increasing the distance between the film and the lens by $\Lambda l=7.5$ mm. A well focused picture of the ant was obtained when the distance reading on the camera was $b=1.05$ m (the distance reading does not take the extension into account). The focal distance of the lens is $F=50$ mm. What was the actual distance between the lens and the ant? The lens may be assumed thin.

A. P. Ershov

Problem solutions
M886 — M890; F898 — F902

Answer: a) possible (Fig. 1); $s$ can equal $\pm 41, \pm 12; 6)$ cannot; b) possible (Fig. 2); $s=\pm 8, \pm 24; r)$ possible; $s=\pm 3968, \pm 11904$.

The task is to split some set of $4n-4$ consecutive integers into $n-2$ quadruples and 2 more pairs of numbers so that the sums of the numbers in all quadruples and pairs are the same and equal to $s$. Let us denote by $c$ the sum of the two extreme of $4n-4$ such numbers—the smallest $m$ and the largest $M$. (For further consideration, note that $M=m+4n-5$, that is, $c=2m+4n-5$ and $m=(c+5)/2-2n, M=(c-5)/2+2n$.) Of course, $c$ is always odd. The sum of all $4n-4$ numbers is equal to $(2n-2)c$, therefore, if we require the division of air, the equality must satisfy

$$ns=2(n-1)c.$$

This necessary condition allows us to immediately use the case when $n$ is divisible by 4, in particular, $n=4$ (point 6) of the problem): for such $n$ there is no partition, since the right side of (1) is not divisible by 4, and the left side is.

For the odd $n$, to which everything below applies, condition (1) also gives strong restrictions: since $n$ and $n-1$ are coprime, and $n$ and $c$ are odd, $c$ is divisible by $n$, so that for an uneven odd $r$ the equalities must hold

$$c=nr, \quad s=2(n-1)r.$$

figure 3 shows how the required partitions can be constructed for $r=1$ and $r=3$. Two pairs of numbers - "red" and "yellow" - have the same sums $s$ (that is, the common center of symmetry at the point $s/2$), and the remaining $4n-8$ numbers form four "blue" sequences of $n-2$

⟦folio 41⟧

Issled (and souls in a row), two of which we consider ascending, and the other two - descending. Then the sum of the first numbers of these sequences is equal to the sum of the second, the sum of the third, etc., so that we get $n-2$ quadruples with the same sums; if correspondence (1) is satisfied between $s$ and $c$, then all these sums are also equal to $s$. The examples shown in figure 3, a and b correspond to $r=3$ and $r=1$ in formulas (2), for any odd $n$. (Figures 1 and 2 show the corresponding fillings of the boundaries of the squares for $n=3$ and $n=5$.) By changing the signs of all $4n-4$ numbers (which will lead to a change in the signs of $s$ and $c$) we get examples with $r=-3$ and $r=-1$.

So, we indicated the arrangement of numbers with the values ​​$s$ a) $\pm 4$, $\pm 12$ for $n=3$; c) $\pm 8$, $\pm 24$ for $n=5$; d) $\pm 3968$, $\pm 11904$ for $n=1985$ (and in general, $\pm 2(n-1)$, $\pm 6(n-1)$ for odd $n$). Let us prove that these values ​​exhaust the answer to problems a), c) and d). The sum $2s$ of two pairs of red and yellow numbers together is not less than the sum $4m+6$ of the four smallest ones $m$, $m+1$, $m+2$, $m+3$ and not more than the sum $4M-6$ of the four smallest ones $M$, $M-1$, $M-2$, $M-3$ from the integers $m$ to $M$. Expressing $m$ and $M$ through $c$ and $n$ and using formulas (2), we obtain

$$2(c+8-4n)=4m+6 \leq 2s \leq 4M-6=2(c-8+4n),$$
$$nr-4n+8 \leq 2r(n-1) \leq nr+4n-8,$$

where

$$-4(n-2) \leq (n-2)r \leq 4(n-2),$$

that is, $|r| \leq 4$. It remains to remember that $r$ is odd.

If any of the readers manage to figure out this problem also for $n=6$ and, in general, for $n=4k+2$, we will be glad to get acquainted with the solution and report about it in the journal.

V. G. Boltyansky, N. V. Vasiliev

◆ Let straight line $AM$ intersect with the second circle at point $D$ (see figure). Obviously, it is enough to prove that the quadrilateral $ABCD$ is a parallelogram.

Using the fact that the magnitude of an angle with a vertex on a circle formed by two chords or a chord and a tangent is equal to half the magnitude of the angle contained within the angle, we can write two chains of equalities:

$$\angle ADB = \frac{1}{2} \cup BsM = \angle ABM = \frac{1}{2} \cup AM = \angle CAD,$$

$$\angle ADC = \frac{1}{2} \cup MC = \angle MBC = \frac{1}{2} \cup BfM = \angle BAM$$

( $\cup BfM$ and $\cup BsM$ are the values ​​of each $BM$ for the first and second circles). The equality of the angles $ADB$ and $CAD$ means that the parallel lines $AC$ and $BD$, the equality of the angles $ADC$ and $BAM$ means that the parallel lines $AB$ and $CD$; this was what needed to be proven.

I. F. Sharyzin

⟦folio 42⟧

M888. The natural numbers a, b, c and d satisfy the equality ab=cd. Prove that the number a$^{1984}$+b$^{1984}$+c$^{1984}$+d$^{1984}$ is composite.

Let us prove that if ab=cd, then a=uv, b=wt, c=uw, d=wt, where u, v, w, t are some natural numbers.

Since ab is divisible by c, c can be written as c=uw, where u is a divisor of a and w is a divisor of b (for example, u can be the most common divisor of a and c). Then a=uv, b=wt and therefore d=vt. The rest is simple:
$$a^{1984}+b^{1984}+c^{1984}+d^{1984} = (uv)^{1984}+(wt)^{1984}+(uw)^{1984}+(vt)^{1984} = (u^{1984}+t^{1984})(v^{1984}+w^{1984}),$$
and the number on the right side is obviously composite.

A. V. Anzhans

M889. Are there three points A, B, C on the plane such that for any point P in the plane at least one of the segments PA, PB and PC has an irrational length?

ANSWER: such points exist.

Let A and B be two points of the plane, the distance between which is $\sqrt{2}$, C be the midpoint of the segment AB, P be an arbitrary point of the plane.

Then $2\vec{PC} = \vec{PA} + \vec{PB}, \vec{AB} = \vec{PB} - \vec{PA}$, that is
$$4PC^2 = PA^2 + PB^2 + 2\vec{PA} \cdot \vec{PB},$$
$$AB^2 = PA^2 + PB^2 - 2\vec{PA} \cdot \vec{PB}.$$
Adding these equalities, we get
$$4PC^2 + AB^2 = 2PA^2 + 2PB^2,$$
and, since the number AB$^2 = \sqrt{2}$ is irrational, the numbers PA, PB and PC cannot be rational at the same time.

A. M. Slinko

M890. On the territory of the countries, which is shaped like a square with a side of 1000 km, there are 51 cities. The country has the means to build 11,000 km of highways. Will it be able to connect all its cities with a network of highways?

ANSWER: yes, it can. We will indicate one of the possible ways of laying roads. Let's lay out a 1000 km long highway through one of the country's cities parallel to the side of the square from the border do borders (Fig. 1). At a distance of 100 km from the ends of this highway, we will mark two points on the highway. Between them, at an equal distance of 200 km from each other, we will place 3 more points. Through these 5 points we will build 5 roads, perpendicular to the previously built highway and space route from one border to another. Now we will build a highway from each city, connecting this city along the shortest route with one of the already laid roads. The length of each additional highway in each city is no more than 100 km, and in total there are no more than 50 such highways. Therefore, the total length of all highways does not exceed 6·1000+50·100=11,000 km.

The indicated highway network is not the shortest. figure 2 shows an example of a more localized highway layout. The broken line has a total length of 5·800+4·200=4800 km with an additional 12 “tendrils” each (100$\sqrt{2}$−100) km long. Receiving at the same time a network of highways with a length of 4800+12·(100$\sqrt{2}$−100)=3600+1200$\sqrt{2}$ km also, which, as is easy to see, the distance from any point of the square to the nearest highway does not exceed 100 km. Therefore, in order to connect 51 cities with the already built highway network

⟦folio 43⟧

To solve the problem, we use the law of conservation of energy. At the initial moment of the stick, an angle α is formed with the horizon such that sinα=H/2l. The total energy of the stick at the initial moment is equal to its potential energy and is equal to

$$U_0 = mg \frac{H}{4}.$$

When a stick moves, its total energy at any moment of time is the sum of its potential energy

$$U_t = mg \frac{l \sin \beta}{2}$$

(β is the angle that the sticks form with the horizon at a given moment (Fig. 2)), the kinetic energy of translational motion

$$E_{t1} = m \frac{v_t^2}{2}$$

($v_t$ is the speed of the center of mass of the stick) and the energy $E_{t2}$ of the rotational motion. According to the law of conservation of energy

$$U_t + E_{t1} + E_{t2} = U_0,$$

where

$$E_{t1} = \frac{mv_t^2}{2} = U_0 - U_t - E_{t2},$$

And

$$v_t = \sqrt{\frac{2}{m}(U_0 - U_t - E_{t2})}.$$

Obviously, the speed $v_t$ of the center of mass of the stick will be maximum when the values ​​of $U_t$ and $E_{t2}$ are minimum.

Potential energy is minimal at the moment when the upper end of the stick occupies the most possible position, that is, when the thread is vertical. At the same time

$$U_{t_{\min}} = mg \frac{|l - l|}{2}.$$

It is not difficult to understand that at this moment in time the stick moves only forward. Indeed, since the stick is inextensible, the projections of the velocities of any of its points onto the direction of the stick itself should be the same. The speed of the lower point (point C on figure 2) is always directed horizontally, and at the moment when the thread is vertical, the speed of the upper point (point B on figure 2) is also horizontal (since the thread is inextensible). From the condition of inextensibility of the stick it follows that these velocities must be the same and all points of the stick must be moving at this moment.

⟦folio 45⟧

Sew in it a layer of rututi of height $h_1$ (Fig. 4). This force is numerically equal to the weight of the rut in the volume of that part of the cup that is shaded at figure 4:

$$F_{p1} = q_1 g \left( \pi R^2 h_1 - V_1 \right),$$

(5)

where $V_1$ is the volume of ruthury remaining in the cup, equal to

$$V_1 = \frac{2}{3} \pi R^3 - \pi \left( R - h_1 \right)^2 \left( R - \frac{R - h_1}{3} \right).$$

(6)

Substituting (5) taking into account (6) into the equilibrium conditions (4) and solving the resulting equation of the relative $h_1$, we obtain the answer to the second question of the problem:

$$h_1 = \sqrt[3]{\frac{3m}{\pi q_1}}.$$

M. G. Abrahamyan

F900. Part of the graph depicting the process of passage with an ideal monatomic gas is validated (Fig. 1). The volume scales are known (they are indicated on figure 1). During the entire process of transition from state 1 to state 2, the gas gave back as much as it received. Find the work done by the gas in this process.

If the process graph were completely specified (Fig. 2), then to determine the work done by the gas, one would simply need to determine the area $S_1$ of figure C12D. Let us show that the area $S_1$ can be expressed in terms of the area $S_2$ of the figure M12N, which can be determined from the given “incomplete” graph.

As can be seen from figure 2,

$$\left| p_1 V_1 \right| + S_1 = \left| p_2 V_2 \right| + S_2 \Rightarrow S_2 = S_1 + \left| p_1 V_1 \right| - \left| p_2 V_2 \right| \left( \left| p_1 V_1 \right|, \left| p_2 V_2 \right| \right) - \text{соответствие площади прямогонников M1CO и N2DO}).$$

Since during the entire process the gas gave up as much as it received, we can conclude from the first law of thermodynamics that

$$A = -\Delta U,$$

where $\Delta U$ is the change in the internal energy of the gas during the process.

For an ideal monatomic gas $U = \frac{3}{2} v R T$, so

$$A = \frac{3}{2} v R \left( T_1 - T_2 \right),$$

where $T_1$ and $T_2$ are the gas temperatures at points 1 and 2, respectively.

From the Mendeleev-Clapeyron equation it follows that

$$p_1 V_1 - p_2 V_2 = v R \left( T_1 - T_2 \right) = \frac{2}{3} A,$$

so $\left| p_1 V_1 \right| - \left| p_2 V_2 \right| = \frac{2}{3} S_1$ and

$$S_1 + \frac{2}{3} S_1 = S_2,$$

where

$$S_1 = \frac{3}{5} S_2.$$

The value of area $S_2$ can be determined from the graph specified in the conditions of the problem; Using the scales specified on the graph, we find $S_2 \approx 3$ kJ; hence,

$$A \approx 1,8 \text{ кДж.}$$

V. T. Karpetyan

⟦folio 46⟧

F901. Three identical capacitors, each of capacitance C, are connected in series and connected to a battery with an emf E. After they are fully charged, they are disconnected from the battery. Then two resistors with a resistance R each were simultaneously connected to them as shown in figure. How much heat will be generated by each resistor? What are the points across the resistors at the point in time when the voltage on the middle capacitor is 10 times less than the emf of the battery?

The most important thing is that the capacitors in this circuit are not completely discharged. After the currents in the circuit stop, the capacitors are connected in parallel, that is, the voltages across them are the same.

Thus, the discharging middle capacitor is equal to the sum of the currents of the outer capacitors, and since, due to symmetry, they are equal to each other (see figure),

$$I_2 = 2I_1.$$

Let us denote the voltage on the capacitors at the end of the discharge $U_x$. Since the initial voltage on each of them was $\frac{\varepsilon}{3}$, during the discharge time charges $q_1 = C\left(\frac{\varepsilon}{3} - U_x\right)$ will flow through the capacitors, and charge $q_2 = C\left(\frac{\varepsilon}{3} + U_x\right)$ will flow through the middle capacitor (the middle capacitor will be recharged to the opposite polarity). It is clear that $q_2 = 2q_1$, that is

$$2C\left(\frac{\varepsilon}{3} - U_x\right) = C\left(\frac{\varepsilon}{3} + U_x\right),$$

where

$$U_x = \frac{1}{9} \varepsilon.$$

We find the heat that will be released on each of the resistors from the law of conservation of energy:

$$Q_1 = Q_2 = \frac{1}{2}\left(W_{\text{нач}} - W_{\text{кон}}\right) = \frac{1}{2} \cdot 3 \cdot C\left(\frac{\varepsilon}{3}\right)^2 - \frac{1}{2} \cdot 3 \cdot C\left(\frac{\varepsilon}{9}\right)^2 = \frac{2}{27}C\varepsilon^2.$$

Since the middle capacitor is recharged to the opposite polarity, the voltage $\varepsilon/10$ will be across it twice - during the discharge from $\varepsilon/3$ to 0 and during the charge from 0 to $\varepsilon/9$. For the first case, according to Ohm's law,

$$U_{t1} + \frac{\varepsilon}{10} = RI_{t1}$$

(1)

($U_{t1}$ - voltage on the outer capacitors at this moment); the charges that will flow at this moment through the outer capacitors and through the middle one are related by the ratio

$$C\left(\frac{\varepsilon}{3} - U_{t1}\right) = \frac{1}{2}C\left(\frac{\varepsilon}{3} - \frac{\varepsilon}{10}\right).$$

(2)

Solving (1) and (2) together, we find the current $I_{t1}$ flowing in the first case through the resistors:

$$I_{t1} = \frac{19}{60}\frac{\varepsilon}{R}.$$

Compiling similar equations for the second case -

$$U_{t2} - \frac{\varepsilon}{10} = RI_{t2}, \quad C\left(\frac{\varepsilon}{3} - U_{t2}\right) = \frac{1}{2}C\left(\frac{\varepsilon}{3} + \frac{\varepsilon}{10}\right),$$

- we find:

$$I_{t2} = \frac{1}{60}\frac{\varepsilon}{R}.$$

A.R. Zilberman

⟦folio 47⟧

F902. Two flat layers of thickness d each are uniformly charged throughout the volume with a charge density of -ρ u +ρ. A particle with a negative charge -e and mass m is adjacent to a positively charged layer with a speed v directed at an angle α to the surface of the layer (see figure).
1) At what speed can a particle not penetrate into a negatively charged layer?
2) After how much time and at what distance from point A does the particle leave the positively charged layer in this case?

Let's choose an XY coordinate system as shown in figure. We can immediately note that the movement of the particle along the Y axis will be uniform with a speed v cos α (we neglect the effect of gravity). The force acting on the particle from the charged layer is directed along the X axis and at the x coordinate point is determined by the charges rotating on the figure region (symmetrical to the relative interface plane of the layer). Indeed, the effect of unshaded regions with charges of different sizes is compensated, since the space charge region can be imagined as a set of planes with a surface charge, and the field created by a charged plane does not depend on the distance to it. For the same reason, we can assume that the field at a point with coordinate x is determined by charged planes with surface charges -ρx and +ρx located to the left and right of this point. The voltage of such a field is equal to

$$E = 2 \frac{\rho x}{2 \varepsilon_0} = \frac{\rho x}{\varepsilon_0}.$$

This means that the force acting on the particle at the moment when it is at a point with coordinate x is equal to

$$F_x = -e \frac{\rho x}{\varepsilon_0},$$

and the equation of particle motion in the direction of the X axis is

$$x'' = - \frac{e \rho}{m \varepsilon_0} x$$

is the equation of harmonic oscillations with frequency $\omega_0 = \sqrt{e \rho/m \varepsilon_0}$. It is understood that the particle will not penetrate into areas of negative charge if the amplitude of these oscillations is less than d. The maximum speed v_pr of particles at which this condition is satisfied is determined by the equality

$$v_{пр} \sin \alpha = \omega_0 d = d \sqrt{\frac{e \rho}{m \varepsilon_0}};$$

from here

$$v_{пр} = \frac{d}{\sin \alpha} \sqrt{\frac{e \rho}{m \varepsilon_0}}.$$

At speed v < v_{pr} the particle penetrates into the positive layer to a certain depth and then is “pushed out” of it. The time t that the particle spends inside the layer is half the period of oscillations with frequency $\omega_0$, that is

$$t = \frac{T}{2} = \pi \sqrt{\frac{m \varepsilon_0}{e \rho}};$$

During this time, the particles will mix vertically over a distance

$$y = t v \cos \alpha = \pi v \sqrt{\frac{m \varepsilon_0}{e \rho}} \cos \alpha.$$

At this distance from point A, the particle will fly out of the positively charged layer.

A. I. Buzdin
