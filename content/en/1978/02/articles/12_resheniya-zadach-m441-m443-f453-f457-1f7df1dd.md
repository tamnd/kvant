---
id: 1978-2-resheniya-zadach-m441-m443-f453-f457-1f7df1dd
issue: kvant_1978_2
year: 1978
number: "2"
title: Solutions to problems M441—M443; F453—F457
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 30
page_last: 35
page_labels: 28, 29, 31, 32, 33
tag: KWGJ
lang: en
source: kvant_digital
extraction: vision
content_sha256: a7fadcaff1203272fc2ad6867c631c110986ce236f9b57c6e996f961071509be
prompt_sha256: draft-1
translated_from: content/ru/1978/02/articles/12_resheniya-zadach-m441-m443-f453-f457-1f7df1dd.md
source_content_sha256: 4cb5a8a476689166bbdfab23567acdee17e903951de430bab922f381072c5515
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 28⟧

Problem solutions
M441 — M443; F453 — F457

M441. A point P is taken inside a convex 2n-space. A straight line is drawn through each vertex and point P. Let us prove that there is a side of the polygon with which none of the drawn lines has common points (except, perhaps, the ends of the side).

Fig. 1.

Internally, we say that a straight line intersects a side of a polygon M if their intersection point does not coincide with the vertex of the polygon.

Two cases are possible: 1) point P belongs to some diagonal AB of the polygon M; 2) point P does not belong to any of the diagonals of the polygon M.

In the first case, the lines PA and PB coincide with (AB) and do not intersect any sides of M, and the lines passing through the point P and the remaining 2n-2 vertices of M intersect at most 2n-2 sides. Therefore, at least two sides of the polygon M are not intersected by any of the drawn lines.

Now let P not lie on any of the diagonals of M. Take a diagonal AB of the polygon M that divides its boundary into two n-link broken lines Γ1 and Γ2, and the 2n-gon M into two convex (n+1)-gons M1 and M2 (Fig. 1). Let us assume that P is inside M1; and let C be an arbitrary vertex of the polygon M2 (different from A and B). Since M1 and M2 are on opposite sides of (AB), P∈M1, C∈M2 and the polygon M is convex, the lines PC and AB intersect at some point K∈[AB] (see Fig. 1). A line PC passing through the interior point of the polygon M1 and intersecting its boundary at point K on side AB intersects the boundary of M1 at another point not lying on AB, i.e., intersects Γ1. Thus, any line passing through the vertices Γ2 (other than A and B) intersects the boundary of the convex polygon M at two points: the vertex Γ2 and a point lying on Γ1 (possibly coinciding with the vertex Γ1). Consequently, any straight line does not intersect the segments of the broken line Γ2.

It is proved in a similar way that the lines AP and BP also do not intersect the segments of the broken line Γ2.

So, n+1 straight lines intersect at most n sides of the polygon M (links of the broken line Γ1). The remaining n-1 straight lines cannot intersect more than n-1 sides of the polygon M (links of the broken line Γ2). Consequently, at least one side (of the links of the broken line Γ2) is not intersected by any of the lines drawn through the point P and the vertices of the polygon M.

G. Gurevishch

Let's rewrite the sum $a_1 + a_2 + a_3 + \dots + a_{p-1}$ like this:

$$(a_1 + a_{p-1}) + (a_2 + a_{p-2}) + \dots + (a_{\frac{p-1}{2}} + a_{\frac{p+1}{2}})$$

($p-1$ is an even number; in the last sum there are $\frac{p-1}{2}$ expressions in parentheses). Let's consider one of the expressions $a_i + a_{p-i}$, enclosed in brackets. It's easy to see that

$$i^p + (p-i)^p = p^p - C_p^1 \cdot i \cdot p^{p-1} + \dots + C_p^{p-1} \cdot i^{p-1} \cdot p = p^2 l$$

— is divisible by $p^2$ (since $C_p^{p-1} = p$; $p > 2$, $1 \leq i \leq p-1$). Therefore $a_i + a_{p-i}$ is divisible by $p^2$; and since $a_i < p^2$, $a_{p-i} < p^2$, then $a_i + a_{p-i} = p^2$ for all $i = 1, \dots, p-1$. So,

$$a_1 + a_2 + \dots + a_{p-1} = (a_1 + a_{p-1}) + \dots +$$

$$+ (a_{\frac{p-1}{2}} + a_{\frac{p+1}{2}}) = p^2 \cdot \frac{p-1}{2} = (p^3 - p^2)/2$$

which is what was stated.

S. Okhimin

⟦folio 29⟧

M443. There is a table of $n \times n$ cells, in each cell of which the initial value is 0. It is allowed to randomly select $n$ numbers, standing in different rows and different columns, and notify each of them by 1.

a) Can the tables shown in Figures 2 and 3 be obtained in a few steps?

b) Is it possible to get a table with pairwise distinct numbers?

b) What kind of tables can be obtained in $T$ steps?

Fig. 2.

| 1 | 2 | 3 | • • • | $n$ |
| :--- | :--- | :--- | :--- | :--- |
| 2 | 3 | 4 | • • • | 1 |
| 3 | 4 | 5 | • • • | 2 |
| • • | • • | • • | • • | • |
| • • | • • | • • | • • | • |
| $n$ | 1 | 2 | • • • | $n-1$ |

Fig. 3.

| 1 | 2 | 3 | • • • | $n$ |
| :--- | :--- | :--- | :--- | :--- |
| 2 | 3 | 4 | • • • | $n+1$ |
| 3 | 4 | 5 | • • • | $n+2$ |
| • • | • • | • • | • • | • |
| • • | • • | • • | • • | • |
| $n$ | $n+1$ | $n+2$ | • • • | $2n-1$ |

Fig. 4.

It is easy to obtain a table on figure 2 by adding up tables in which the units are built parallel to the diagonal (Fig. 4).

Let us now move straight to problem c). First of all, we note that in the table $n \times n$, which is obtained from zero in $T$ steps, the sums of the numbers in each row and each column are the same and equal to $T$. At first, all these sums were equal to zero, and by adding one to the $n$ numbers in different rows and different columns of the table, we change all the sums equally - exactly by one for each. So the condition for the equality of the sum of numbers in each row and each column is a necessary property 3, which cannot be obtained by indicating transformations.

Let us prove that the condition for equality of sums across rows and columns is also sufficient. In doing so, we will rely on such an important lemma. Let a table $n \times n$ be given, filled with non-negative integers, in which the sum of the numbers in the rows and columns is the same (we will call such tables magic). Then, if this table is not zero, then it can contain a set of $n$ numbers located in different rows and different columns of the table, each of which was non-zero.

It immediately follows from the lemma that any magic table can be obtained from the zero one. In fact, let the sums over the rows and columns be non-negative numbers, for which the sum of the numbers over the rows and columns is the same (we will call such tables magic). Then, if this table is not zero, then it can contain a set of $n$ numbers located in different rows and different columns of the table, each of which was non-zero.

So, it remains to prove the lemma. Let us formulate it this way: if among the $n$ arbitrary numbers of the magnetic table $n \times n$, located in different rows and different columns, there is at least one zero, then we would again select a set of $n$ zero numbers from this table (from different rows and different columns), again calculate one from each of these numbers, and move on to the magic table with the sum $T-2$ by every row and every column, etc.; - in $T$ steps we would get a table with zero sums, i.e. a zero table. Moving in the opposite direction, we can obtain the original table $M$ from the zero table.

So, it remains to prove the lemma. Let us formulate it this way: if among the $n$ arbitrary numbers of the magnetic table $n \times n$, located in different rows and different columns, there is at least one zero, then we would again select a set of $n$ zero numbers from this table (from different rows and different columns), again calculate one from each of these numbers, and move on to the magic table with the sum $T-2$ by every row and every column, etc.; - in $T$ steps we would get a table with zero sums, i.e. a zero table. Moving in the opposite direction, we can obtain the original table $M$ from the zero table.

So, it remains to prove the lemma. Let us formulate it this way: if among the $n$ arbitrary numbers of the magnetic table $n \times n$, located in different rows and different columns, there is at least one zero, then we would again select a set of $n$ zero numbers from this table (from different rows and different columns), again calculate one from each of these numbers, and move on to the magic table with the sum $T-2$ by every row and every column, etc.; - in $T$ steps we would get a table with zero sums, i.e. a zero table. Moving in the opposite direction, we can obtain the original table $M$ from the zero table.

⟦folio 31⟧

where $x_1, x_2$ and $x_3$ are the initial coordinates of cubes with masses $m_1, m_2$ and $M$ relative to an arbitrary origin of the report.
From here

$$l_0 = \frac{m_1}{m_1 + m_2} l.$$

I. Slobodetsky

Fig. 7.

F454. If the direction $U_0 = 220$ V is applied to the primary winding of an unexposed transformer, then the direction on the secondary winding will be $U_1 = 127$ V. What direction $U$ will be at $U_0 = 220$ V to the direction $R = 10$ Ohm connecting to the secondary winding of this transformer? The active resistance of the primary winding of the transformer is $r_1 = 2$ Ohm, and the secondary winding is $r_2 = 1$ Ohm. The internal resistance of the moka generator is equal to zero.

Let us denote the effective value of the emf. induction occurring in the primary winding of an unexposed transformer through $E_1$, and in the secondary winding through $E_2$. It's obvious that

$$\frac{E_1}{E_2} = \frac{n_1}{n_2} = k,$$

where $n_1$ is the number of turns in the primary winding, $n_2$ - in the secondary winding and $k = n_1/n_2$ is the transformation coefficient. Since in a non-external transformer

$$E_1 = U_0 \text{ и } E_2 = U_1,$$

That

$$k = \frac{E_1}{E_2} = \frac{U_0}{U_1} = \sqrt{3}.$$

When the transformer is loaded, that is, resistance $R$ is connected to the secondary winding, current flows through the primary winding

$$I_1 = \frac{U_0 - E_1'}{r_1},$$

and on the secondary winding—

$$I_2 = \frac{E_2'}{R + r_2}.$$

Here $E_1'$ and $E_2'$ are the effective value of the emf. induction in the primary and secondary windings of a loaded transformer.

The efficiency of the transformer is almost equal to unity. This means that the power in the primary winding of the transformer is equal to the power transferred to the secondary circuit:

$$I_1 E_1' = I_2 E_2'.$$

Then

$$\frac{I_2}{I_1} = \frac{E_1'}{E_2'} = k.$$

Let's combine equations (1), (2) and (3) in the system:

$$\begin{align*}
I_1 &= \frac{U_0 - E_1'}{r_1} \\
I_2 &= \frac{E_2'}{R + r_2} \\
\frac{I_2}{I_1} &= k,
\end{align*}$$

where

$$I_2 = \frac{k U_0}{r_1 + k^2 (R + r_2)},$$

And

$$U_2 = I_2 R = \frac{k U_0 R}{r_1 + k^2 (R + r_2)} \approx 110 \text{ B}.$$

V. Skorovarov

⟦folio 32⟧

F455. Power loss in the power transmission line is 5% of the power received by the consumer. How do you need to change the voltage at the line input and the consumer resistance for mono, so that with the same power received by the consumer, the consumption in the line is reduced to 1%?

The power received by the consumer is equal to

$$P = I_0^2 R = \frac{U_0^2}{(R + r)^2} R,$$

where $I_0$ is the current in the power transmission line, $r$ is the line resistance, $R$ is the consumer resistance and $U_0$ is the voltage at the line input. This power according to the condition must remain unchanged. Hence,

$$\frac{U_0^2}{(R + r)^2} R = \frac{U_1^2}{(R_1 + r)^2} R_1,$$

where $U_1$ is the new voltage at the line input and $R_1$ is the new consumer resistance. Let us denote by $\alpha$ the ratio of the power lost in the wires to the power received by the consumer. Then

$$\alpha_1 = \frac{I_0^2 r}{I_0^2 R} = \frac{r}{R} = 0.05, \quad \alpha_2 = \frac{r}{R_1} = 0.01.$$

Hence $R = \frac{r}{\alpha_1}$ and $R_1 = \frac{r}{\alpha_2}$.

Hence,

$$\frac{R_1}{R} = \frac{\alpha_1}{\alpha_2} = 5,$$

$$\frac{U_1}{U_0} = \frac{R_1 + r}{R + r} \sqrt{\frac{R}{R_1}} =$$

$$= \frac{r \left(1 + \frac{1}{\alpha_1}\right)}{r \left(1 + \frac{1}{\alpha_2}\right)} \sqrt{\frac{\alpha_2}{\alpha_1}} = \frac{1 + \alpha_2}{1 + \alpha_1} \sqrt{\frac{\alpha_1}{\alpha_2}} \approx \sqrt{5}.$$

I. Slobodetsky

F456. What minimum speed does a spaceship need to reach on Earth for mono to get to the Sun? What will be the time of the ship's flight to the Sun?

Let's imagine that a spaceship is launched from the Earth, the speed of which is slightly less than the speed of the Earth's reverse motion. The trajectory of the ship will be an ellipse, at one of the focuses of which is the Sun. The lower the initial speed of the ship relative to the Sun, the more elongated its orbit. At certain values ​​of this speed, the ship in its movement will touch the surface of the Sun. In other words, the altitude of the perihelion of the ship's orbit will be equal to the Sun. The radius of the Sun is approximately 200 times smaller than the radius of the Earth's orbit, so the small band of the ship's elliptical orbit touching the Sun is much smaller than the larger band. For estimation, we can assume that the small gain is simply equal to zero. With this assumption, the trajectory of the ship turns into a straight line, connecting the launch point of the ship with the Sun, that is, the ship hits the Sun, freely falling onto it. Consequently, at the initial moment the speed of the ship relative to the Sun should be equal to zero. In order for this condition to be fulfilled, the ship must communicate on Earth at a speed equal in abscyl value to the inverse speed of the Earth, but directed in the opposite direction.

The radius of the Earth's orbit is approximately $1,5 \cdot 10^{11}$ m, the period of revolution of the Earth around the Sun is $\sim 3,15 \cdot 10^{7}$ s. Therefore, the orbital speed of the Earth is

$$v = \frac{2\pi \cdot 1,5 \cdot 10^{11}}{3,15 \cdot 10^7} \approx 3 \cdot 10^4 \text{ м/с}.$$

This speed must be achieved on Earth (Fig. 8).

In order to determine the time of the ship's flight to the Sun, use Kepler's third law. According to this

⟦folio 33⟧

The squares of the periods of revolution of the ship and the Earth around the Sun are related to the cubes of the semimajor axes of the orbits of the ship and the Earth:

$$\frac{T^2_K}{T^2_3} = \frac{(R/2)^3}{R^3}$$

(R is the radius of the Earth’s orbit). The flight time of a ship to the Sun is half the period of its revolution in an elliptical orbit, that is

$$t = \frac{T_K}{2} = \frac{1}{4\sqrt{2}} T_3 \approx 5.6 \cdot 10^6 \text{ с.}$$

A. Dozorov

F457. Two flat air capacitors with identical plates and have identical charges. The distance between the plates of the first capacitor is twice as large as that of the second. How will the energy of the electric field of the system change if the second capacitor is left between the plates of the first Mak, as shown in figure 9, a and 6?

The energy of the electric field of a charged capacitor is equal to

$$W = \frac{\varepsilon_0 \varepsilon E^2}{2} V,$$

where $\varepsilon_0$ is the electric constant, $\varepsilon$ is the dielectric constant of the medium, $\vec{E}$ is the direction of the field and $V$ is the volume occupied by the electric field.

Let us find the initial energy $W_0$ of the electric field of the system of two air capacitors ($\varepsilon=1$). Since the charges on the capacitors are the same, the direction of the field in the first capacitor is the same as in the second. Let us denote its absolute value by $E_0$. Let the volume of the first capacitor be $V_0$, and the volume of the second, respectively, $V_0/2$. Then

$$W_0 = \frac{\varepsilon_0 E^2}{2} V_0 + \frac{\varepsilon_0 E^2}{2} \frac{V_0}{2} = \frac{3}{4} \varepsilon_0 E^2 V_0.$$

After the capacitors are placed one inside the other, the absolute values ​​of the directions of the electric fields between the plates will become different. For case a) (Fig. 9, a)

$$E_1 = E_3 = E_0, \quad E_2 = 2E_0.$$

The correspondence will change and the energy of the system will change:

$$W = \frac{\varepsilon_0 E^2}{2} (V_1 + V_3) + \frac{\varepsilon_0 E^2}{2} V_2 = \frac{5}{4} \varepsilon_0 E^2 V_0.$$

From here

$$\frac{W}{W_0} = \frac{5}{3}.$$

In case b) (Fig. 9, b)

$$E_1 = E_3 = E_0, \quad E_2 = 0.$$

Then

$$W = \frac{\varepsilon_0 E^2}{2} (V_1 + V_3) = \frac{1}{4} \varepsilon_0 E^2 V_0,$$

And

$$\frac{W}{W_0} = \frac{1}{3}.$$

S. Kozel
