---
id: 1973-11-resheniya-zadach-m191-m194-f203-f207-af587d17
issue: kvant_1973_11
year: 1973
number: "11"
title: Solutions to problems M191—M194; F203—F207
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 44
page_last: 52
page_labels: 42-50
tag: 8THV
lang: en
source: kvant_digital
extraction: vision
content_sha256: c587242fc4a6f305fbaf4d48558c9386d8e3f243aa24fee881e5d71feba5eb46
prompt_sha256: draft-1
translated_from: content/ru/1973/11/articles/09_resheniya-zadach-m191-m194-f203-f207-af587d17.md
source_content_sha256: 3f6deb95dce9fb8d5142306ab2d34a17e6396fee2d9cfd49a9874e097d50a6f2
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 42⟧

Problem solutions
M191—M194; F203—F207

M191. On the plane, given two points A and B and a line l passing through point A and not passing through point B. An arbitrary circle is drawn through points A and B. Let O be its center, C be its point of intersection with line l, distinct from A. Let us find the geometric location of the midpoint of the segments OC.

We will find the sets sequentially (all of them turn out to be straight lines, Fig. 1):
$m_1$ centers O;
$m_2$ midpoints of segments OA - points K;
$m_3$ midpoints OL of equilateral triangles AOC - points P;
$m_4$ midpoints of segments OC - points M.

The set $m_1$, as is well known, is a line drawn perpendicular to the segment AB through its midpoint. Let us denote by D and E the points of intersection of the line $m_1$, respectively, with the line l and with the perpendicular, restored to the line l at point A (the case when the lines $m_1$ and l are parallel is very simple, but must be separated); through G - the middle of the segment AE; through F and H are points of the line l such that AF = FD = DH (Fig. 1).

Now we need to prove three statements:

(1) The set of midpoints of segments in which one end (A) is fixed and the other is located on a given line (DE) is a straight line (FG; Fig. 2).

(2) The set of midpoints of segments parallel to a given direction (AE) with ends on two given straight lines (ED and AD) is a straight line (DG; Fig. 3).

(3) The set of second ends of segments parallel to a given direction (l), the first ends and midpoints of which are located on given straight lines (FG and DG), is a straight line (HG; Fig. 4).

All these statements can be proven easily and almost identically. Let us prove (3) as an example. Firstly, it is clear that any point M on the line HG satisfies the necessary condition: if through the point M draw a line parallel to l, and denote by K and P its points of intersection with the lines FG and DG, then P will be the midpoint of the segment KM

⟦folio 43⟧

(this is easy to prove by similarity using the equality $HD = DF$). Secondly, any line parallel to $l$ obviously contains only one point of the desired set. Therefore, there cannot be other points (not lying on the line $HG$) in this set.

Do the rest of the proof yourself.

Let us also consider the case when $AB \perp l$; in this case, all three straight lines $(m_2), (m_3), (m_4)$ merge into one parallel line $l$ and dividing stress $AB$ in relation to $1:3$.

**M192. The given numbers are 1, 2, 3, ..., 1000. The smallest is the most m, which has the maximal property: no matter which m of the given numbers is crossed out, among the remaining 1000 - m numbers there will be two, of which one is divisible by the other.

Let's prove that the most m is 499. First of all, let's check that no m greater than or equal to 500 has the desired property. Indeed, if $m \geq 500$, then, by crossing out m numbers (from 1 to m), we will leave numbers from $m + 1 \geq 501$ to 1000, among which none, very much, is divisible by another (all pairwise relations are less than two).

Now we prove that $m = 499$ has the required property. In other words, we will prove that among any 501 numbers from 1 to 1000 there are two, of which one is divisible by the other (a similar solution problem in the book “Selected Problems and Theorems of Elementary Mathematics”, Part 1, “Arithmetic and Algebra” No. 91, “Science”, 1965).

Let us match each number (out of 501) with its most odd divisor: the number $2^k (2l + 1)$ is matched with the number $(2l + 1)$. All odd numbers less than 1000, there are only 500. Therefore, some two of the 501 numbers will correspond to the same odd number. Of these two numbers, one will necessarily be obtained from the other by multiplying by some power of two.

**M193. Prove that the sum of the areas of right triangles forming pairs of sides**

Let us present one of the shortest solutions, adapted by A. Makartsev (Lvov).

Let us prove that the sum of the areas of some four numbers from the areas of triangles $ABC, BCD, CDE, DEA$ and $EAB$ (see Fig. 5). Let $F$ be the intersection point of $AD$ and $EC$. Since point $F$ lies on line segment $EC$, the area of ​​$S_{ABF}$ is contained between $S_{ABE}$ and $S_{ABC}$ (Fig. 6). But we know that $S_{ABC} \leq S_{ABE}$. Therefore $S_{ABF} \leq S_{ABE}$.

Similarly, since the point $F$ lies on $AD$ and $S_{ABC} \leq S_{BCD}$, then $S_{BCF} \leq S_{BCD}$.

But triangles $AED, EDC, ABF$ and $BCF$ cover the fifth triangle (piece $EFD$ - twice). Therefore, the sum of their areas is greater than $S_{ABCDE}$. Especially

$$S_{ABE} + S_{AED} + S_{EDC} + S_{BCD} \geq S_{ABCDE}.$$

⟦folio 44⟧

The example given in figure 7 shows that the ratio of the heel area of ​​triangles to the area of ​​the pentagon can be very close to 1.

Fig. 8.

Fig. 9.

It is easy to see that this ratio is not greater than 2. Figure 8 shows that it can be made as close as possible to 2.

**M194.** Given two coprime angular numbers a and b. It is known that any integer can be represented as ax + by, where x and y are integers. The distance between integers, which can be represented as ax + by, where x and y are non-negative integers.

a) What is the largest number c that is not in the set M?

b) Prove that of two numbers n and c - n (n is any integer), one belongs to M and the other does not.

(On figure 9 for a = 5 and b = 3 integer points that belong to the set M are red, those that do not belong are blue).

Let's draw the Oxy coordinate system on the plane and formulate our problem in geometric language. We will call each pair of integers (x, y) an “integer point” and represent it as a red point if both of its coordinates are non-negative (x ≥ 0, y ≥ 0), and a blue point if at least one coordinate is negative (Fig. 10). We consider mutually prime angular numbers a and b to be fixed (on figure we take a = 5, b = 3). For each n the equation

$$ax + by = n$$

defines, as is known, a straight line. Let's denote it by $l_n$. Of course, all lines $l_n$ are parallel to each other. Let $n$ be an integer. We will consider the line $l_n$ red if it passes through at least one red point, and blue otherwise *). We must find out what is the largest c that corresponds to the blue line $l_c$, and prove that then of the two lines $l_n$ and $l_{c-n}$ one is blue and one is red (n is any integer).

In our solution, we will use plane displacements that map a set of integer points onto themselves and simultaneously transform each line $l_n$ into the same or some other line $l_n'$ from our family. These are, firstly, parallel transfers to any vector (p, q) with integers p and q:

$$(x, y) \mapsto (x + p, y + q),$$

and, secondly, rotations by 180° (or, what is the same, a symmetric relative point) with any centers $\left(\frac{p}{2}, \frac{q}{2}\right)$, where p and q are integers:

$$(x, y) \mapsto (p - x, q - y).$$

Let us prove that on each line $l_n$ integer points meet at equal intervals.

*) As follows from what was said in the conditions, each straight line $l_d$ passes through at least one whole point. Below we will prove this fact.

⟦folio 45⟧

Lemma 1. If $(x_0, y_0)$ is an integer point on the line $l_n$, then the integer points close to it on $l_n$ will be $(x_0 - b, y_0 + a)$ and $(x_0 + b, y_0 - a)$ (a and b are coprime!).

Consider the line $l_0$ passing through $(0, 0)$. Let $(-b_1, a_1)$ be an integer point $l_0$ close to $(0, 0)$ such that $b_1 > 0$, $a_1 > 0$ (we do not yet know that $b_1 = b, a_1 = a$), $(x_0, y_0)$ is an integer point $l_n$. When crossing onto the vector $(x_0, y_0)$, the line segment $l_0$ from $(0, 0)$ to $(-b_1, a_1)$ will turn into the segment $l_n$ from $(x_0, y_0)$ to $(x_0 - b_1, y_0 + a_1)$. Thus, point $(x_0 - b_1, y_0 + a_1)$ will be close to $(x_0, y_0)$ point $l_n$ from above. In the same way, when crossing onto the vector $(x_0 + b_1, y_0 - a_1)$, the same line segment $l_0$ will go into the line segment $l_n$ from $(x_0 + b_1, y_0 - a_1)$ to $(x_0, y_0)$. Consequently, on this segment only its ends will be integer points.

From here it already follows that on any line $l_n$ (if there is at least one integer point on it) the gap between neighboring integer points is the same: $a_1$ units along the $Oy$ axis and $b_1$ units along the $Ox$ axis. This applies in particular to straight line $l_0$. Since $(-b, a)$ belongs to $l_0$, it follows that $b = db_1$, $a = da_1$, where $d$ is an integer. But the numbers $a$ and $b$ are relatively prime by convention. So, $d = 1$, that is, $a = a_1$, $b = b_1$. Lemma 1 is proven.

From this lemma it follows that each line $l_n$, where $n$ is an integer, passes through exactly one point inside the strip $0 \leqslant x \leqslant b - 1$. In this case, obviously (see Fig. 10), if the straight line is red, that is, somewhere passes through a red point, then its entire point in the seen strip will also be red (and the point of the blue straight line, of course, is blue).

Now note that when the relative point $\left(\frac{b - 1}{2} - \frac{1}{2}\right)$ $(x, y) \rightarrow (x', y') = (b - 1 - x, -1 - y)$ is symmetrical, the strip $0 \leqslant x \leqslant b - 1$ transforms into itself, and the red points transform into blue ones, and vice versa. Taking $l_n$ after this symmetrical one goes into the straight line $l_{ab-a-b-n}$: if $ax + by = n$, then $ax' + by' = a(b - 1 - x) + b(-1 - y) = ab - a - b - n$. (Through the center of symmetry, where $a\left(\frac{b - 1}{2}\right) + b\left(-\frac{1}{2}\right) = \frac{ab - a - b}{2}$, none of our straight lines may pass; at Fig. 10 the center is the point $(1, -\frac{1}{2})$.

It is clear that the lowest red line is $l_0$. Therefore, the topmost blue line is $l_{ab-a-b}$. So, the most number that does not belong to the set is $c = ab - a - b$,

and of the two numbers $n$ and $c - n$ one belongs to $M$ and the other does not.

We used the fact that each integer $n$ can be represented as $ax + by$, where $x$ and $y$ are integers. This is also easy to prove using the “lattice”.

Lemma 2. On every line $l_n$, where $n$ is an integer, there is at least one integer point.

It is enough to prove that the integer point $(x_0, y_0)$ is on the line $l_1$: if $ax_0 + by_0 = 1$, then $a(nx_0) + b(ny_0) = n$, so $(nx_0, ny_0)$ will belong to $l_n$.

Consider parallels with vertices $(0,0)$; $(0,1)$; $(b,1 - a)$; $(b,-a)$, two changing sides of which are equal to 1, and the larger one lies on the lines $l_0$ and $l_b$. Inside this parallel (not at the vertices) lies $b - 1$ an entire point: on each line $x = 1$, $x = 2$, $x = b - 1$ - one. On the other hand, all this parallelism is intersected by just the same collisions $(b - 1)$ - straight lines $l_n : l_1, l_2, \dots, l_{b-1}$ (not counting $l_0$ and $l_b$). Since the straight line $l_n$ cannot have more than one whole point whose coordinates $x$ differ less by $b$, it would therefore be that all the points in the number $(b - 1)$ lie one on each straight line. In particular, there is an entire point at $l_1$. Lemma 2 is proven.

F203. The electronic generator uses a prudod in which the consideration between the chamber and the anode is 1 mm. Estimate the maximum number of oscillations that can be obtained using this generator if the anode direction is 200 V.

Periodically, bulb points in one generator lamp circuit are achieved by periodically changing the lamp grid potential. The time $t$ during which the grid potential occurs must be no less than the time $t$ of the electron project from the cada to the anode. The maximum possible frequency of oscillations obtained using this generator can be determined from the condition

$$\tau = t \Rightarrow v_{\max} = \frac{1}{\tau}.$$

(If $\tau > t$, then the electron does not have time to reach the directory before the lamp is “locked.”)

The field voltage between the electrodes is $E = \frac{U}{d}$ (we do not take into account the changing grid field), the electron acceleration is $a = \frac{eE}{m} = \frac{eU}{md}$. Hence,

$$d = a \frac{\tau^2}{2} \Rightarrow \tau = \sqrt{\frac{2d}{a}} = \sqrt{\frac{2d^2m}{Ue}}.$$

Poztou $v_{\max} = \sqrt{\frac{Ue}{2d^2m}} \approx 3000$ Metz.

I.Sh. Slovodechky

⟦folio 46⟧

F204. The spacecraft approaches the Moon along a parabolic trajectory, almost touching the surface of the Moon. At the moment of maximum merging with the Moon, the frost thruster is turned on for a short time, and the ship goes into a circular orbit around the Moon. Determine the change in speed of the ship during freezing. The radius of the Moon is $R_\pi = 1740$ km, the acceleration of free fall on the surface of the Moon is $g_\pi = 1,7 \text{ m/c}^2$.

Note: On a parabolic trajectory, the total energy of the ship is zero.

When a spacecraft moves along a parabolic trajectory, the following conditions are met at any point along the trajectory:

$$E_{\text{полн}} = E_{\text{пот}} + E_{\text{кип}} = 0,$$

that is

$$\gamma \frac{m M_\pi}{R} = \frac{mv^2}{2},$$

where $M_\pi$ is the mass of the Moon, $m$ is the mass of the ship, $R$ is the distance from the ship to the Moon, $v$ is the speed of the ship at a given point, $\gamma$ is the gravitational constant. At the moment of closest approach to the Moon $R = R_\pi$ (since the trajectory almost touches the surface of the Moon, we neglect the altitude of the orbit compared to the radius of the Moon $R_\pi$).

The speed of the ship at this moment is maximum; let's find it from the condition

$$\frac{mv^2_{\text{max}}}{2} = \gamma \frac{M_\pi m}{R_\pi};$$

from here

$$v_{\text{max}} = \sqrt{2\gamma \frac{M_\pi}{R_\pi}} = \sqrt{2g_\pi R_\pi}$$

($v_{\text{max}}$ is the second escape velocity for the Moon). When moving in a circular orbit, the centripetal acceleration of the ship is imparted by the force of gravity. Consequently, when braking, the speed of the ship must be reduced to the value $v_1$, determined from the condition

$$\frac{mv^2_1}{R_\pi} = \gamma \frac{M_\pi m}{R^2_\pi}$$

(according to Newton's second law). From here

$$v_1 = \sqrt{\gamma \frac{M_\pi}{R_\pi}} = \sqrt{g_\pi R_\pi}.$$

Speed ​​change when braking

$$\Delta v = v_{\text{max}} - v_1 = g_\pi R_\pi (\sqrt{2} - 1) \approx 700 \text{ m/c}.$$

S. M. Kozel

Fig. 11.

F205. Using a fragment of irregularly shaped stack A on a vertical wall, a sunbeam is released once in mochi B, another time in mochi C (Fig. 11). The bunny in urine B turns out to be round, and its illumination in the center is greater than in areas illuminated by mildly diffused light. What is the illumination in the center of the bunny in urine C?

Loons SA, AB and AC lie in the same vertical plane, moon AB is horizontal, $SAB = BAC = 45^\circ$.

You have probably realized more than once that if the wall on which you shoot a sunbeam is further from you, then the bunny turns out to be round, and if the wall is close, then the sunbeam has the same shape as the mirror. Why is this happening?

The rays of light coming from any point of the Sun are reflected from the mirror and, then hitting the screen, give a spot shaped like a mirror (Fig. 12). Since the Sun is

⟦folio 47⟧

very far away and the rays coming from the point of the Sun and then reflected from the mirror can be considered parallel to each other, then the size of the spot coincides with the size of the mirror. Each point of the Sun produces such a spot. The spots on the screen overlap each other. If the screen is close to the mirror, so that the size of each of the spots is greater than the distance between the spots, which are obtained when rays coming from diametrically opposite points of the Sun are reflected from the mirror, then the bunny on the screen will have the shape of a mirror, although somewhat crushed (the size of the bunny will differ little from the size of the mirror). If the screen is located far from the mirror, so that the size of each spot is small compared to the large “total” spot, then this larger spot will be round or elliptical, depending on the angle between the planes of the mirror and the screen.

Above we talked about the large or small distance between the mirror and the screen. But which distances can be considered large and which small? In order to answer this question, consider the rays coming from diametrically opposite points of the Sun (or, what is the same, from the points of the minimum image of the Sun in the mirror) (see Fig. 13, a). It is clear that a spot on the screen has the shape of a mirror if the angular size of the mirror, that is, the angle $\gamma_1$ at which the mirrors are visible from a point on the screen, is greater than the angular size of the Sun $\alpha$ (Fig. 13, b). If the angular size of the Sun is greater than the angular size of the mirror $\gamma_2$ (Fig. 13, s), then the bunny on the screen has the shape of a circle (or ellipse).

⟦folio 48⟧

In our case, the bunny from the stack socket turned out to be round at point $B$. It will also be round at point $C$, which is even further from the stack than point $B$. This means that the angular size of the Sun in our case is larger than the angular size of the stack. But in this case, as can be seen from figure 13, $\theta$, rays enter each point of the screen, and not from all points of the Sun or its minimum image, but only from those that are visible from a point on the screen at the same solid angle $\Omega$ as the glass. Consequently, the illumination of a spot on the screen due to those rays that are reflected from the stack is proportional to the solid angle $\Omega$ at which the glass is visible from a point on the screen. For point $B$ this angle is equal to $\Omega_1 = \frac{S \cos \alpha_1}{R_1^2}$, where $S$ is the surface area of ​​the stack (Fig. 14, a). Therefore, the addition to the illumination by scattered light at a point

$$B \text{ экрана равна } k \frac{S \cos \alpha_1}{R_1^2}, \text{ где } k \text{ — коэффициент пропорциональности.}$$

Let $E_0$ be the illumination of those areas of the screen that receive only diffuse light. Then at point $B$ the addition to the illumination by scattered light is

$$\Delta E_B = 3E_0 - E_0 = 2E_0 = \frac{kS \cos \alpha_1}{R_1^2}. \tag{1}$$

At point $C$ the solid angle at which the mirror is visible (Fig. 14, b) is equal to

$$\Omega_2 = \frac{S \cos \alpha_2}{R_2^2}.$$

This means that if the screen at point $C$ was perpendicular to the sun's ray, then its illumination at point $C$ would be equal

$$E_C = E_0 + k\Omega_2 = E_0 + k\frac{S \cos \alpha_2}{R_2^2}.$$

Since the reflected sun rays at point $C$ make an angle $\beta$ with the normal to the screen surface, then

$$E_C = E_0 + k \frac{S \cos \alpha_2}{R_2^2} \cos \beta. \tag{2}$$

Let's compare formulas (1) and (2), we find that

$$E_C = E_0 \left[ 1 + 2 \frac{\cos \alpha_2}{\cos \alpha_1} \left( \frac{R_1}{R_2} \right)^2 \cos \beta \right].$$

Since $R_2 = R_1/\cos \beta$, $\alpha_1 = 22.5^\circ$, $\alpha_2 = 45^\circ$ and $\beta = 45^\circ$, then

$$E_C = E_0 \left[ 1 + 2 \frac{\cos^4 45^\circ}{\cos 22.5^\circ} \right] = 1.52 E_0.$$

F206. Estimate the maximum temperature to which the surface of an aircraft flying at a speed close to the speed of sound can be heated due to air pressure. To estimate the situation, air is composed of two amortine nitrogen molecules, the energy of which is equal to 5/2 kT, where $k$ is Boltzmann’s constant and $T$ is the absolute temperature. The ambient air temperature is considered equal to $-10^\circ C$.

When nitrogen molecules collide with the surface of an airplane, it cannot receive an energy greater than $\frac{5}{2} kT_1 + \frac{mv^2}{2}$, where $v$ is the speed of the airplane (or, in the coordinate system associated with the airplane, the average speed of the ordered movement of nitrogen molecules flying on the nose of the airplane), $m$ is the mass of nitrogen molecules, $T_1$ is the temperature of the surrounding air.

⟦folio 49⟧

Fig. 15.

Since nitrogen molecules after a collision with an airplane must have energy $\frac{5}{2} kT_2$ corresponding to the temperature $T_2$ of the surface of the airplane, then

$$\frac{5}{2} kT_2 < \frac{5}{2} kT_1 + \frac{mv^2}{2}.$$

From here

$$T_{2\max} = T_1 + \frac{1}{5} \frac{mv^2}{k} \approx 373^\circ\text{K}.$$

F207. A piece of water ice floats on the surface of the oil in a cylindrical vessel. The temperature of the entire system is $0^\circ\text{C}$. How will the oil level and pressure at the bottom of the vessel change when the ice is melted and the resulting water sinks to the bottom of the vessel?

The pressure at the bottom of the vessel will not change. Indeed, the pressure force on the bottom $F$ is equal to the weight of the contents of the vessel, and the weight does not change. Consequently, the pressure itself, equal to $\frac{F}{S}$, where $S$ is the area of ​​the bottom of the vessel, does not change.

How does the oil level change? Let the height of the water level in the vessel be $h_3$, the height of the oil level be $h_2$, and the height of the oil level before the ice melts $h_1$ (Fig. 15). Since the ice floats and does not touch the bottom of the vessel, the pressure on the bottom in the first case is equal to

$$p_1 = \rho_M g h_1.$$

In the second case it is equal

$$p_2 = \rho_M g \left(h_2 - h_1\right) + \rho_E g h_3$$

($\rho_M$ is the density of oil, $\rho_E$ is the density of water).

From the equality of pressure it follows that

$$\rho_M h_1 = \rho_M \left(h_2 - h_1\right) + \rho_E h_3$$

And

$$h_2 = h_1 - \left(\frac{\rho_B}{\rho_M} - 1\right) h_3.$$

Since $\frac{\rho_B}{\rho_M} > 1$, then $h_2 < h_1$.

Consequently, the oil level will decrease when the ice melts.

I. Sh. Slobodetsky

⟦folio 50⟧

1, 3, 4, 8; O. Kozhuschiy (Moscow) 3; K. Kozel (Poland) 1, 4; B. Kolomensky (Kyiv) 3; V. Komlev·Krasnoisk) 3; S. Konyazin (Saratov) 0, 1, 3—5, 7, 8; S. Korneev (Novokuznetsk) 3; S. Kuznetsov (Cheboksary) 1, 3; A. Kukush·Kyiv) 3, 7, 9; E. Kulyanin (Ryazan) 3; V. Kulbaka (Derzhanovka village, Chernigov region) 3; V. Kuranov (Tetyush TASSR) 3; A. Kurbamov (Moscow) 3; A. Kurlyandchik (Leningrad) 1, 3—5, 8, 9; L. Lalayan (Baku) 3; A. Leosmeev (Moscow) 3; G. Liberov (Moscow) 1; A. Limovenko (Belokorovich, Zhytomyr region) 1, 3, 4; M. Lifits (Leningrad) 0 6); Yu. Leban (Evpatoria) 1, 7, 8; T. Lokomoshi (Odesca) 3; I. Luchinkin (Dnepropetrovsk) 1, 3, 4; A. Lvov (Saratov) 3; M. Lyubits (Kharkov) 8; E. Mazur (Derbent) 1; A. Makariev (Lviv) 1, 4, 5; G. Malashonok (Lviv) 1, 3, 4, 7, 8; V. Markin (Tolochin, Vitebsk region) 1, 4; G. Mamevev (Leningrad) 3, 4, 7; V. Matsukamov (Tsalka village, GSSR) 3; I. Medzhivovsky (Moscow) 3; S. Melnik (Kharkov) 1, 3; S. Merzlyakov (Ufa) 3, 4; Yu. Merenkov (Berdigestyakh YASSR) 3, 4; K. Minnakhmetov (Bugulma TASSR) 1, 3; A. Molotkv (Kubinka, Moscow region) 7; V. Mondrus (Tbilisi) 3; Zh. Mukazhanov (Zharma station, Semipalatinsk region) 7; G. Mumiov (Khadzhabad district of the UzSSR) 3, 4; K. Minnakhmetov (Bugulma TASSR) 1, 3; A. Molotkv (Kubinka, Moscow region) 7; V. Napadov (Kharkov) 7; S. Nasyrov (Kazan) 3; V. Naumov (Kommunar village, Leningrad region) 4; L. Nakhmanson (Orsk) 3; A. Nikolaev (Moscow) 1, 3, 5, 7; T. Nikonova (Moscow) 3; R. Norvation (Couns) 3; S. Nuzhny (Kuibyshev) 1, 3, 7; S. Ovchinnikov (Leningrad) 3, 4; S. Odeanesyan (Armavir) 3; V. Oleynik (Dnepropetrovsk) 1, 4; V. Orlov (Astrakhan) 3; D. Panzhensky (Ust-Kamenogorsk) 4; V. Pankov (Minsk) 1, 3; O. Parakina (Moscow) 3; P. Paramonov (Moscow) 1, 3; E. Pariis (Tashkent) 1, 3, 8; A. Parlov (Uzlovaya station, Tula region) 1; A. Pasmukhov (Sverdlovsk) 1; N. Petrs (Bulgaria) 4; A. Pechkovsky (Moscow) 1, 3, 4; A. Pidman (Odessa) 1, 3, 4; V. Pisarsky (Moscow) 1; S. Pitskov (Moscow) 3; L. Pitskvsa (p/o Plisma, Minsk region) 3; S. Pozhidaev (Kuibyshev) 1, 3, 7; M. Polovinnik (Mena, Chernigov region) 1; V. Porkshein (Rostov-on-Don) 1; A. Priornitsky (Slavyansk, Donetsk region) 3; V. Prunes (Moscow) 8; S. Putintsev (Kemerovo) 1, 3; G. Pyatetsky (Moscow) 3; A. Razguleev (Klin, Moscow region) 8; A. Rayin (Moscow) 1, 3-5; A. Rashkovsky (Kharkov) 1, 3-5; A. Reznikov (Kyiv) 3; G. Reznikov (Saratov) 3, 4; S. Rodtsov (Saratov) 1, 3-5; R. Rozhkov (Ryazan) 1, 3; E. Ruderman (Chernivtsi) 3; N. Rundkovist (Sverdlovsk) 1; M. Sadykov (Kazan) 3; M. Sapir (Sverdlovsk) 1, 3, 4; S. Samanovsky (Kharkov) 1, 3—5, 7; A. Sboev (Medvedok village, Kirov region) 4; A. Sedal (Leningrad) 8; T. Selbirak (Poland) 1, 3; V. Semenov (Minsk, Chelyabinsk region) 1; S. Semenov (Voronezh) 3; I. Sivtsky (Lenin-grad) 7; I. Sidorov (Moscow) 3, 4; I. Simonsiv (Moscow) 1, 3, 4, 7; M. Sinyakov (Saratov) 1; R. Siroma (Kharkov) 3-5; G. Warehouse (Kharkov) 1, 3—5; V. Blind (Frunze) 3, 7; A. Sleraenko (Rubtsovsk, Altai Territory) 1, 3.7-9; A. Slinkin (Moscow) 1, 3, 4, 7.8; A. Sokolov (Novosibirsk) 3; V. Solodukin (Stepnogorsk) 1; V. Solomyak (Leningrad) 1, 3; T. Sona (village Kamenskoye, Zaporozhye region) 3; P. Sukhov (Saratov) 1, 3; S. Stepkina (Mogilev) 3; S. Tabachinkov (Moscow) 1, 3, 4, 7-9; A. Tarnopolsky (Korosten, Zhitomir region) 4, 7; I. Termny (Pervomaisk, Nikolaev region) 1; A. Tkay (Kamenets-Podolsky) 1; V. Tkachenko (Kyiv) 3; O. Trukov (Jalal-Abad Kyrgyz SSR) 3; E. Turketsi (Chernivtsi) 1, 3, 4, 7.9; S. Fomin (Leningrad) 1, 3—5, 7.9; V. Khodorvsky (Dnepropetrovsk) 3; V. Khonin (Pervouralsk) 4; S. Tserkovny (Leningrad) 1, 3, 4, 9; I. Tsukerman (Leningrad) 1; Yu. Tsyzanov (Verbilki village, Moscow region) 3, 7; V. Circleevi (Balti) 1; N. Chaturleev (Tbilisi) 3; S. Chermeshantsev (Leningrad) 3, 4; N. Chernov (Krivoy Rog) 1, 3, 4; A. Chebamov (Omsk) 8; Yu. Chernyavsky (Kyiv) 1, 3; Z. Chertkov (Kyiv) 1, 3; M. Shaimukhambetov (Almaty) 3; A. Sherstok (Nikolaev) 1, 3, 4; E. Shesakov (Moscow) 1, 3, 4; V. Shirman (Kharkov) 1, 3—5, 7.9; A. Shekhorsky (village of Stariki, Zhytomyr region) 1, 3, 4; I. Yunus (Kharkov) 1, 3—5, 7; A. Yakovlev (Samokhvalovich village, Minsk region) 1, 3; A. Yaroslavtsev (Shelkovo, Moscow region) 4.

Yu. P. Lisov

The editors received over 500 letters with solutions to problems F193—F202. The correct solutions to these problems were added (the bold figure after the last name is the last digit of the problem number): N. Azhitsev (Lipovka village, Lviv region) 9, 0; S. Akmertsev (Magnitogorsk) 9; S. ALEXin (Lipetsk) 1; A. Amirov (Orenburg) 9; Sh. Amakulov (Fergana) 9; N. Amitsev (Lipovka village, Lviv region) 9; R. Basirov (village N. Karakityany TASSR) 0, 2; S. Blaoder (Bokistogorsk) 9; A. BLEXMAN (Alma-Ata) 9; S. Bobkov (Kurgan) 2; L. Bratsinsky (Frunze) 8, 9, 0, 1, 4, 5; A. Braslavets (Novosibirsk) 7; I. Bramovskaya (Usolye-Sibirsk) 7; M. Buneev (Kechevka village, Kechevsky district) 9; P. Bukharinov (Bezznyaki) 9; M. Vasnetsov (Kyiv) 0; Yu. Vizen (Leningrad) 4; I. Volkov (Moscow) 9, 0; A. Voskanyan (Yervan) 4, 5; V. Gerasimov (Sarapul UdASSR) 6; A. German (Voronezh) 0, 4, 6, 7; S. Hertz (Khust) 1; N. Golovko (Prosladny) 6; V. Golumva (Vyskopolye) 9; V. Gorbulin (village Krasnogvardeyskoye Stav-
