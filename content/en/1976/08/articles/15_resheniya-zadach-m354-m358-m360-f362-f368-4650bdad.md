---
id: 1976-8-resheniya-zadach-m354-m358-m360-f362-f368-4650bdad
issue: kvant_1976_8
year: 1976
number: "8"
title: Solutions to problems M354—M358, M360; F362—F368
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 40
page_last: 48
page_labels: 38-46
tag: 8V1H
lang: en
source: kvant_digital
extraction: vision
content_sha256: 93e8dacad80e4423b9cacb838bfd55d6d24c655571f5ac269275ccc52082d696
prompt_sha256: draft-1
translated_from: content/ru/1976/08/articles/15_resheniya-zadach-m354-m358-m360-f362-f368-4650bdad.md
source_content_sha256: 829d67a978aef3b8564863bdb8ad887e7a5e7e187a889a87650dc42e63ac0d0f
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 38⟧

F410. In an electron-based device, a pure tungsten cathode is located in a large flask containing residual oxygen at a pressure of $p = 10^{-7}$ atm and a temperature of $T = 300^\circ\text{K}$. Assuming that every molecule that hits the cathode sticks to it, estimate the time for the formation of a monomolecular layer. Molecules can be considered balls with a diameter of $d \approx 3 \cdot 10^{-8}$ cm. (9 cells)

F411. One U-shaped manual pressure gauge can change pressures up to 1 atm. What is the maximum pressure that can be changed if two such pressure gauges are connected in series with a short tube? (9-10 grades)

F412. The teacher, responding to the doxa, monitors the class by reflections in the glasses. At the same time, he sees two reflections of a student sitting 5 m from him: one at a distance of 5 m, the other at a distance of $\frac{5}{7}$ m. Turning only to face the class, through his glasses he sees an image of the same student at a distance of 2.5 m. Determine the refractive index of the glass from which the lenses of the glasses are made. (10 grades)

Problem solutions
M354 — M358, M360; F362 — F368

M354. Is it possible to consider the numbers 1, 2, 3, ..., $4n + 2$ at the vertices and midpoints of the sides of a regular (2n + 1)-knot so that the sum of the three numbers at the ends and middle of each side is the same for all sides?

Let us consider as examples the case $n = 3, n = 8$,

Fig. 1.

Answer. Can.

Let's give one of the arrangement methods. At the midpoints of the sides of the polygon we put numbers from 1 to $2n + 1$ in order. This message helps you arrange the remaining numbers $2n + 2, \dots, 4n + 2$. Let's find the sum $S$ of three numbers at the end and middle of each side. Obviously, $S = \frac{\Sigma + \Sigma'}{2n + 1}$, where $\Sigma = 1 + 2 + \dots + (4n + 2) = (2n + 1) \times (4n + 3)$ is the sum of all written numbers, $\Sigma' = (2n + 2) + \dots + (4n + 2) = (2n + 1) (3n + 2)$ is the sum of the numbers that need to be placed at the vertices; therefore $S = 7n + 5$. Let us now put the number $4n + 2$ at the vertex, common for the sides with numbers 1 and 2 in the middle, and we will place the numbers $4n + 1, 4n, \dots, 2n + 2$ at the vertices one after another, considering the vertex with the number $4n + 2$ as the initial one - see figure 1 (on this figure all points are located on the same circle; black dots are “midpoints”, red ones are “vertices”). Let us show that in this way the required number will be placed at each vertex (there is no doubt that this will be the numbers $2n + 2$, ..., $4n + 2$). In fact, after $n$ steps we will first get to the vertex adjacent to the initial one, and the number $(4n + 2) - n = 3n + 2$ will be placed at this vertex, so the sum of the numbers on the side with one in the middle is exactly $(3n + 2) + 1 + (4n + 2) = 7n + 5$. Now the very exact amount is not

⟦folio 39⟧

M355. N kids pass N balls. At the beginning of each of them, we throw our ball to one of our companions and catch the ball thrown by someone (he can throw and catch his own ball) so that again everyone has a ball. Then the guys again throw the ball to the same ones to whom they threw them the first time and so on. The game stops when all the balls are returned to their owners (the balls have not been replaced, we will consider them to be of different colors).

Prove that
a) return the ball to each of the participants after N thrown;
b) cerra obliges to end;
e) the duration of the cerra is always a divisor of the number N!=1·2·…·N;
d) the duration of the cerra cannot exceed $\frac{N}{3}$.

Let player $A_1$ pass his ball to player $A_2$, player $A_2$ to player $A_3$it. D. Since there are a finite number of players, in this sequence, sooner or later one of the players will meet twice. It is clear that the first such player will be player $A_1$. Effective, let player $A_n$ pass his ball to player $A_k$, where $k < n$ and $k > 1$. Then players $A_n$ and $A_{k-1}$ pass the balls to the same player, and from the problem statement it follows that players $A_{k-1}$ and $A_n$ are the same person. Therefore, players $A_1$, $A_2$, ... can be placed in a circle so that each player passes and receives the ball from his neighbors. However, players can be placed in several such circles. Since there are no more than N people in each of these circles, the ball will return to any of the players in no more than N throws.

Let us have s circles in total, in which there are $l_1$, $l_2$, ..., $l_s$ people, respectively. If there are l people in a circle, then after m·l is thrown, all the balls in it are in the hands of the owners. Therefore, the game will end after $T = H.O.K.(l_1, l_2, ..., l_s)$ throws. (H.O.K.(l_1, ..., l_s) is the least common multiple of $l_1$, ..., $l_s$). Since everything is $l_i \leq N$, it is clear that T is a divisor of N!. Thus, we have answered points a), b) and d) of the problem. Let's look at point d).

Note that $l_1 + l_2 + ... + l_s = N$ and all $l_i$ are integers.

Let us show that $l_1 \cdot l_2 \cdot ... \cdot l_s \leq 3$. (In the problem statement published in «Kvant» No. 11 for 1975, in paragraph d) there was a typo: the duration of the game cannot exceed $\frac{N}{3}$, and not 3N/3.) Effective, if some $l_s \geq 4$, then replacing it with 2+($l - 2$), we will not change the sum $l_1 + l_2 + ... + l_s$ and let us not reduce the product $l_1 \cdot l_2 \cdot ... \cdot l_s$. Therefore, from the product $l_1 \cdot l_2 \cdot ... \cdot l_s$ we can go to the non-minimal one, in which all components are no more than three. Notes, if this turns out to be possible, 1+1 by 2, 1+3 by 2+2 and 2+2+2 by 3+3, we will get a product of the form 3·3·…·3, 3·3···3·2 or 3·3···3·2·2 depending on the remainder obtained when dividing N by 3, which is not less than any product $l_1 \cdot l_2 \cdot ... \cdot l_s$. Namely: if N is divisible by 3, then we take $\frac{N}{3}$ triplets and get the required estimate; if the remainder is 1, then take $\frac{N}{3}$ threes and two twos; then $l_1 \cdot l_2 \cdot ... \cdot l_s < 2 \cdot 2 \cdot 3 = \frac{N-4}{3}$; but 4·3 < 3, since $4^3 > 3^4$. If the remainder is 2, then take $\frac{N}{3}$ threes and one two;

⟦folio 40⟧

M356. From point M, taken inside the triangle $A_1B_1C_1$, perpendiculars $MA_2$, $MB_2$, $MC_2$ are dropped onto lines $B_1C_1$, $A_1C_1$, $A_1B_1$, respectively, then from this point of point M perpendiculars $MA_3$, $MB_3$ are dropped, $MC_3$ to straight lines $B_2C_2$, $A_2C_2$, $A_2B_2$ and so on. Let us prove that in the resulting sequence of triangles $A_1B_1C_1$, $A_2B_2C_2$, $A_3B_3C_3$, ... triangle $A_{3n+1}B_{3n+1}C_{3n+1}$ is similar to triangle $A_1B_1C_1$.

Let us first prove the following auxiliary correspondence: $\hat{A}_{i+1} = B_i\hat{M}C_i - \hat{A}_i$ (correspondence $\hat{B}_{i+1} = A_i\hat{M}C_i - \hat{B}_i$, $\hat{C}_{i+1} = A_i\hat{M}B_i - \hat{C}_i$).

Indeed, since $MA_{i+1}\bot B_iC_i$, $MB_{i+1}\bot A_iC_i$ and $MC_{i+1}\bot A_iB_i$, circles with diameters $MC_i$ and $MB_i$ can be described around the quadrilaterals $MA_{i+1}C_iB_{i+1}$ and $MA_{i+1}B_iC_{i+1}$, respectively. Therefore, $MA_{i+1}\bot B_{i+1} = MC_i\bot B_{i+1}$ and $MA_{i+1}\bot C_{i+1} = MB_{i}\bot C_{i+1}$ (as hanging angles based on the same arcs), and for the angle $A_{i+1}$ we have (see Fig. 3):

$$\hat{A}_{i+1} = C_{i+1}\hat{A}_{i+1}B_{i+1} + MA_{i+1}C_{i+1} = MC_{i}\hat{B}_{i+1} + MB_{i}\hat{C}_{i+1} = (\hat{C}_i - M\hat{C}_iB_i) + (\hat{B}_i - M\hat{B}_iC_i) = (\hat{B}_i + \hat{C}_i) - (M\hat{B}_iC_i + M\hat{C}_iB_i) = (180^\circ - \hat{A}_i) - (180^\circ - M\hat{C}_i) = B_i\hat{M}C_i - \hat{A}_i.$$

After tempera the angles of the triangle are $A_4B_4C_4$. We have:

$$\hat{A}_4 = B_3\hat{M}C_3 - \hat{A}_3 = (180^\circ - \hat{A}_2) - (B_2\hat{M}C_2 - \hat{A}_2) = (180^\circ - B_2\hat{M}C_2) = \hat{A}_1.$$

Similar to $\hat{B}_4 = \hat{B}_1$, $\hat{C}_4 = \hat{C}_1$, that is, $\Delta A_4B_4C_4 \sim \Delta A_1B_1C_1$. Taking triangle $A_4B_4C_4$ except ($\Delta A_1'B_1'C_1'$), we prove in the same way that

$$\Delta A_7B_7C_7 \sim \Delta A_4B_4C_4 \sim \Delta A_1B_1C_1,$$

then what

$$\Delta A_{10}B_{10}C_{10} \sim \Delta A_7B_7C_7 \sim \dots \sim \Delta A_1B_1C_1,$$

and so on, so

$$\Delta A_{3n+1}B_{3n+1}C_{3n+1} \sim \Delta A_{3n} \sim 2C_{3n} \sim 2 \dots \sim \Delta A_1B_1C_1,$$

Q.E.D.

J. Sukonic

⟦folio 41⟧

M357. Prove that if $x + \frac{1}{y} = y + \frac{1}{z} = z + \frac{1}{x}$ then $x = y = z$ or $x^2y^2z^2 = 1$.

From the problem conditions it follows that
$$x - y = \frac{y - z}{yz}, \quad y - z = \frac{z - x}{xz} \quad \text{и} \quad z - x = \frac{x - y}{xy}.$$

Of the first two relations $x - y = \frac{z - x}{xyz^2}$; substituting instead of the difference $z - x$ its expression through $x$ and $y$ (the last relation), we obtain that $x - y = \frac{x - y}{x^2y^2z^2}$. Hence either $x = y$ and then $z - x = 0$, $y - z = 0$, that is $x = y = z$, or $1 = \frac{1}{x^2y^2z^2}$, that is $x^2y^2z^2 = 1$.

I. Klumova

M358. Prove that any n-line ($n \geqslant 4$) has at least one diagonal entirely lying inside the n-line, and find out what is the smallest number of such diagonals an n-line can have ($n$ each $n$).

Fig. 4.

Fig. 5

First of all, we note that all the diagonals of a convex $n$-shell lie inside it, and the number of these diagonals is equal to $\frac{n(n - 3)}{2}$. It is also very important that for each given $n$ the number $\frac{n(n - 3)}{2}$ of diagonals lying inside is not minimal: on figure 4 a quadrilateral is depicted, inside of which only a diagonal lies, while for any convex quadrilateral both diagonals are located inside.

Let us prove that for non-convex $n$-velovians ($n \geqslant 4$) at least one diagonal lies entirely inside.

Consider the angle $ABC$ of our non-convex $n$-angle, which exceeds $180^\circ$. Rays $BA$ and $BC$, forming this angle, divide the entire plane into two parts: the blue part $I$ and the white part $II$ (see Fig. 5).

Let us now take the vertex of the $n$-unit - we denote it by the letter $D$ - lying in the part $II$ (there is such a vertex, since $\widehat{ABC} > 180^\circ$); and draw the diagonal $BD$. If the diagonal $BD$ intersects any side of our $n$-bar, then this side does not lie entirely in the part $I$; therefore, at least one of its ends - let's denote it by the letter $E$ - lies in the part $II$. If the diagonal $BE$ also intersects some side of the $n$-line, then, by similar reasoning, we obtain that one of the ends of this side lies in the part $II$, and we can draw the diagonal $BF$. Let's continue this process. Since none of the vertices can appear twice in our sequence (check this) and there are only a finite number of them, sooner or later we will end up with a diagonal that lies entirely inside the polygon.

Let us now denote by $x_n$ the smallest possible number of diagonals lying entirely inside a $n$-bar (for each $n$; it is clear that a $n$-bar with the smallest possible number of such diagonals will be non-convex). It is obvious that $x_4 = 1$ (see Fig. 4), and $x_3 = 0$ (there are no diagonals in the triangle at all). Based on these examples, we can assume that for every $n$ the number is $x_n = n - 3$. Let us prove that this is true using the method of mathematical induction.

Induction base. $n = 4$, $x_n = 1 = 4 - 3$.

Induction step. Let us assume that for all $n \leqslant k$ the statement is true: $x_5 = 5 - 3$, ..., $x_k = k - 3$. Let us prove that $x_{k+1} = (k + 1) - 3$.

Take a non-convex $(k+1)$-wall with the smallest possible range of all $(k+1)$-walls with the number of diagonals entirely lying inside and consider that vertex

⟦folio 42⟧

B, the angle at which exceeds $180^\circ$. We proved above that a diagonal $BQ$ emanates from such a vertex, which lies entirely inside this $(k+1)$-gon. The diagonal $BQ$ of our $(k+1)$-gon is divided into two polygons with a smaller number of sides: $m \geq 3$ and $[(k+1)-m+2] = k-m+3$, each of which has the smallest possible number of $(m)$-and $(k-m+3)$-gons lying entirely inside the diagonal medium, respectively. According to the indication assumption, for the first polygon $x_m = m-3$, for the second $x_{k-m+3} = k-m$. The number of diagonals lying inside our $(k+1)$-gon is no less than the sum of the number of such diagonals in the $(m)$- and $(k-m+3)$-gons, plane one (the diagonal $BQ$ itself); that is

$$x_{k+1} \geq (m-3) + (k-m+1) = (k+1)-3.$$

So, so far it has been proven that for $n > k$ the number is $x_n \geq n-3$. It remains for each given $n$ to give an example of a $n$-gon, which had exactly $n-3$ diagonals inside. Take any convex curve $\Gamma$—like at figure 6 (for example, paraboly), and take a point at $\Gamma$ $n-1$. Curve $\Gamma$ divides the entire plane into two regions: $I$ and $II$. Let's take another point in the area $II$ and connect it to each of the $(n-1)$ points located on $\Gamma$. We will get the required $n$-gon: it is easy to see that there are no $n-3$ diagonals inside.

I. Klumova, L. Limanov

**M360*). For the sequence $a_1, a_2, a_3, \dots$ it is known that $|a_1|=1$ and $|a_{k+1}|=|a_k|+1$ for each $k=1,2,\dots$. Add the smallest possible value of the sum $|a_1|+a_2|+\dots+a_k|$ if

a) $n=1975$;
b) $n=1976$.

Answer. The smallest possible value of the sum $|a_1+a_2+\dots+a_n|$ with $n=1975$ is 20; at $n=1976$, equals 24.

Solution. For the sequence $\{a_i\}$ from the problem conditions we have:

$$\begin{cases}
a_1^2 = 1, \\
a_2^2 = a_1^2 + 2a_1 + 1, \\
\dots \\
a_{n+1}^2 = a_n^2 + 2a_n + 1.
\end{cases}$$

Adding these equalities, we get:

$$a_{n+1}^2 = n+1+2\sum_{i=1}^{n} a_i,$$

where

$$\sum_{i=1}^{n} a_i = \frac{a_{n+1}^2 - (n+1)}{2}$$

(this is an integer because the number $a_k$ is the same as the parity $k$). So,

$$|a_1| + \dots + a_{1975}| = \frac{a_{1976}^2 - 1976}{2},$$

$$|a_1| + \dots + a_{1976}| = \frac{a_{1977}^2 - 1977}{2}$$

Note now that any integer $x$, $|x| \leq n$ whose parity is the same as $n$ can be realized as $a_n$ for some sequence $\{a_i\}$ (prove it yourself!). Next, $44^2 < 1976 < 45^2$, and $44^2 < 1977 < 45^2$, so close to 1976 square

⟦folio 43⟧

The square of an even number is $1936 = 44^2$, and the square closest to 1977 of an odd number is $2025 = 45^2$. Therefore, the sum $|a_1 + a_2 + \ldots + a_{1975}|$ takes the smallest value $\frac{1936 - 1976}{2} = 20$ (this value is achieved for such sequences $\{a_i\}$, which have $|a_{1976}| = 44$), and the sum $|a_1 + a_2 + \ldots + a_{1976}|$ takes the smallest value $\frac{2025 - 1977}{2} = 24$ (for such sequences $\{a_i\}$, which have $|a_{1977}| = 45$).

V. Golubyatnikov

F362. A layered capacitor consists of three metal parallel plates of area S. The spaces between the plates are filled with dielectrics with dielectric properties $\varepsilon_1$ and $\varepsilon_2$ and resistivities $\rho_1$ and $\rho_2$. Thicknesses of dielectric layers $d_1$ and $d_2$. The capacitor is under constant voltage U. Determine the charge of the middle plate at a steady current in the circuit.

Fig. 7.

F363. Threads are wound on the cylinder, as shown in figure 7. The right ends of the thread are pulled at a speed of $v_1$, the left ends at a speed of $v_2$. At what speed does the cylinder rotate around its axis? The radius of the cylinder is R.

Fig. 8.

This layered capacitor is a combination of two capacitors. Let us denote by the direction of the electric fields in them through $E_1$ and $E_2$ the charge density surfaces on their plates - $\sigma_1$ and $\sigma_2$ and the directions to the capacitors - through $U_1$ and $U_2$, respectively.

The charges on both sides of the middle plate have different signs, so the charge on the middle plate is equal to

$$q = (\sigma_2 - \sigma_1) S.$$

With a stationary distribution of charges, you can use the formulas of electrostatics. Then

$$E_1 = \frac{\sigma_1}{\varepsilon_0 \varepsilon_1}, \quad E_2 = \frac{\sigma_2}{\varepsilon_0 \varepsilon_2},$$

$$U_1 = E_1 d_1, \quad U_2 = E_2 d_2, \quad U_1 + U_2 = U.$$

On the other hand, with respect to electric current, capacitors can be considered as conductors with corresponding resistances $R_1 = \rho_1 d_1 / S$ and $R_2 = \rho_2 d_2 / S$. According to Ohm's law

$$U_1 = I \frac{\rho_1 d_1}{S} \quad \text{и} \quad U_2 = I \frac{\rho_2 d_2}{S}.$$

Having solved the resulting system of water equations, we find

$$q = \frac{\varepsilon_2 \rho_2 - \varepsilon_1 \rho_1}{d_2 \rho_2 + d_1 \rho_1} \varepsilon_0 US.$$

figure 7 shows a method of winding thread on a cylinder, in which the cylinder can rotate around its axis. Let us denote by $\omega$ the angular velocity of this rotation. In turn, the cylinder axis moves uniformly parallel to itself. Let's denote its speed by $v$.

The velocities of points 1 and 2 of the cylinder surface can be represented as the algebraic sum of the linear speed $\omega R$ and the speed $v$ of the translational movement of the cylinder (Fig. 8):

$$v_1 = v + \omega R, v_2 = v - \omega R.$$

From here

$$\omega = \frac{|v_1 - v_2|}{2R}$$

(note that $v_1$ and $v_2$ have different signs).

⟦folio 44⟧

F364. What should be the coefficient of friction for the cutter on the outer surface of a cone with an apex angle of 2α so that a motorcycle can move along the surface to the surface of the cone along a horizontal circle of radius R with a speed v (Fig. 9)?

Fig. 9.

We will consider the motorcyclist as a material point, thereby eliminating all problems associated with his stability in relation to capsizing. The forces acting on the motorcyclist are shown in figure 9. These are the gravity force mg, the reaction force N and the friction force F_TP.

Let's write down Newton's second law in projections onto the horizontal and vertical axes:

$$F_{Tp} \sin \alpha - N \cos \alpha = m \frac{v^2}{R},$$

$$F_{Tp} \cos \alpha + N \sin \alpha - mg = 0.$$

The force of dry friction of rubber on the outer surface of the cone

$$F_{Tp} \leq kN.$$

Solving the resulting system, we find

$$k \geq \frac{gR + v^2 \mathrm{tg} \alpha}{gR \mathrm{tg} \alpha - v^2},$$

if $v < \sqrt{gR \mathrm{tg} \alpha}$. Otherwise, the motorcycle will not be able to move around a circle of radius R.

B. Bukhovtsev

F365. Find the emkosti of the system of capacitors connected as shown in figure 10.

Fig. 10.

Let us denote by $U_i$ and $q_i = C_i U_i$ the voltage and charge on the capacitor with emkomnost $C_i$ (Fig. 11). If this system of capacitors is connected to a battery with electromotive force $\delta$, then the total capacitance of the system

$$C_{06ш} = \frac{q_1 + q_2}{\mathcal{E}} = \frac{C_1 U_1 + C_2 U_2}{\mathcal{E}}.$$

(*)

Let's write down the next correspondences (see Fig. 11):

$$U_1 + U_2 = \mathcal{E},$$

(1)

$$U_4 + U_5 = \mathcal{E},$$

(2)

$$U_1 + U_3 + U_5 = \mathcal{E}.$$

Taking into account the expected polarity of the charge on a capacitor with emkomnost $C_3$, the charge conservation law, written for selected sections of the circuit (see Fig. 11), gives

$$q_1 - q_2 - q_3 = 0, \quad q_3 + q_4 - q_5 = 0.$$

These equations, after substituting the corresponding empacity values, are reduced to the form

$$U_1 - 2U_2 - 3U_3 = 0,$$

(4)

$$3U_3 + 2U_4 - U_5 = 0.$$

By solving the system of equations (1) - (5), we can find the voltages $U_1$ and $U_2$:

$$U_1 = \frac{5}{9} \mathcal{E}, \quad U_2 = \frac{4}{9} \mathcal{E}.$$

Then finally, according to expression (*), we have

$$C_{06ш} = \frac{C_1 U_1 + C_2 U_2}{\mathcal{E}} = \frac{13}{9} C.$$

V. Belonukkin

⟦folio 45⟧

F366. The flask-ball with a capacity of $V=1$ l was opened and closed. A monomolecular layer of air remained on the walls of the flask. Evaluate the pressure that will be in the flask at temperatures up to 300°C, if you know that at this temperature the walls of the flask are completely decontaminated.

The number of molecules remaining on the walls of the flask is approximately $N \sim \frac{4\pi R^2}{d^2}$, where $R \approx 0,06$ m is the radius of the flask, $d \sim 10^{-10}$ m is the diameter of the gas molecule. After decontamination of the walls, the concentration of molecules in the flask will be equal to

$$n = \frac{N}{V} \sim \frac{3}{d^2 R},$$

and the desired pressure

$$p = nkT \sim \frac{3kT}{d^2 R} \approx 40 \text{ н/м}^2.$$

Here $k = 1,38 \cdot 10^{-23}$ j/srad is Boltzmann’s constant, $T \approx 600^\circ\text{K}$.

Let's compare the resulting pressure with normal atmospheric pressure $p_0 \approx 10^5 \text{ н/м}^2$:

$$\frac{p}{p_0} \approx \frac{40}{10^5} \sim 10^{-4}.$$

This simple example shows how much the “vacuum” in a sealed state can deteriorate if the walls of the vessel are not disinfected first.

A. Mitrofanov

F367. Construct the image of the square given by the converging lens (Fig. 12). The middle of the side of the square lying on the main optical axis of the lens is located from the lens at a distance equal to the focal one.

To construct an image of a square, it is most convenient to use rays passing through the focus of the lens. The most necessary of them is the ray $ABGF$ (Fig. 12), running along the upper side of the square, since the images of all points on this side must lie on the ray $GF$ itself or its continuation. Let us also construct the path of the ray $AM$, passing through the left focus $F$ of the lens, and the ray $BN$, as if emerging from the same focus. After the lens, both rays go parallel to the main optical axis of the lens.

Fig. 12.

The actual image $A'$ of point $A$ is at the intersection of rays $GF$ and $MA'$. Similarly, the minimum image $B'$ of the point $B$ is located at the intersection of the extensions of the ray

⟦folio 46⟧

Whose $GF$ and $NH$. To determine the images $C'$ and $D'$ of the corresponding points $C$ and $D$, it is enough to lower the perpendiculars from $A'$ and $B'$ to the main optical axis. The images of sides $AC$ and $BD$, perpendicular to the optical axis of the lens, must be perpendicular to the optical axis.

To construct the path of rays $AM$ and $BN$ we had to extend the lens in both directions as if it were larger than the size. This can be done on the basis that any part of the lens creates the same image as the whole lens (the difference between the lens is the illumination).

Thus, the image of a square consists of two parts: real (part of the angle to the right of $A'$ $C'$) and minima (part of the angle to the left of $B'$ $D'$). the real part is the image of half a square lying further than the focal plane, and the minimal part is the image of half a square lying close to the focal plane of the lens.

B. Bukhovtsev

F368. A rocket of mass $m$ starts at an angle $\alpha$ to the horizon. Does the work of t seconds move the packages, creating thrust $F$ and ensuring linear movement of the packages. Neglecting the change in package mass and air resistance, determine the height $h$ at which engine operation stops.

When solving the problem, we will assume that the reporting system associated with the Earth is inertial and that the motion of the package is limited to space where the free fall acceleration $g$ is constant.

Let us write down the equation of motion of the packets during the operation of its movement:

$$m a = m g + F = R.$$

Here $a$ is the acceleration of the packet, $R$ is the equal force acting on the packet. From the conditions of the problem and the assumption about the inertiality of the selected reporting system, it follows that the force $R$ (as well as the acceleration $a$) must remain constant throughout the entire time of movement and make an angle $\alpha$ (Fig. 13) with the horizon. Therefore, the height $h$ at which the packet rises in time $t$ is equal to

$$h = \frac{a_y t^2}{2} = \frac{R_y t^2}{2 m},$$

where $a_y$ and $R_y$ are the projections of the vectors $a$ and $R$ onto the coordinate axis $OY$, directed vertically upward.

As can be seen from figure 13, the equality must be satisfied

$$(R_y + m g)^2 + (R_y \text{ctg} \alpha)^2 = F^2.$$

From here

$$R_y = m g \left( \sqrt{(F/mg)^2 - \cos^2 \alpha} - \sin \alpha \right) \sin \alpha,$$

and finally

$$h = \frac{R_y t^2}{2 m} = \frac{g t^2}{2} \left( \sqrt{(F/mg)^2 - \cos^2 \alpha} - \sin \alpha \right) \sin \alpha.$$

V. Pozozhev
