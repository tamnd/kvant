---
id: 1977-3-resheniya-zadach-m391-m394-f397-f402-8e5b621a
issue: kvant_1977_3
year: 1977
number: "3"
title: Solutions to problems M391—M394; F397—F402
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 32
page_last: 39
page_labels: 30, 31, 32, 33, 34, 36, 37
tag: X6NE
lang: en
source: kvant_digital
extraction: vision
content_sha256: b17e8c519905553c1bcc9722357b905511914b230916c3dd0b9369f54683f86c
prompt_sha256: draft-1
translated_from: content/ru/1977/03/articles/12_resheniya-zadach-m391-m394-f397-f402-8e5b621a.md
source_content_sha256: 7d977163577679ce7e57cacdcd865c47782cecd695180e8b3e87640e6e47bf4c
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 30⟧

Problem solutions

M391. a) In the sequence $x_0, x_1, x_2, \dots$, the numbers $x_0$ and $x_1$ are natural and less than 1000, and each of the remaining numbers is equal modulo to the difference of the two previous ones. Prove that one of the numbers $x_1, x_2, \dots, x_{1500}$ is equal to 0.

b) In the sequence $x_0, x_1, x_2, \dots$, the numbers $x_0$ and $x_1$ are natural and less than 1000, and each of the numbers $x_2, x_3, \dots$ is equal to the smallest of the abscissa values ​​of the differences of the two previous ones. Prove that $x_{20}=0$.

a) Let us prove by induction on all natural numbers $n$ that if in such a sequence $x_0$ and $x_1$ are less than 2$n$, then one of the numbers $x_1, x_2, \dots, x_{3n}$ is equal to 0 (in the conditions of problem $n=500$).

Case $n=1$ is easy to check. Let the statement be proven for all $n$, less than one. Since $x_0 \leqslant 2n-1$, $x_1 \leqslant 2n-1$, $x_2 \geqslant 1$, then $x_3 \leqslant 2n-2$ and $x_4 \leqslant 2n-3$. If $x_3 < 2n-2$ and $x_4 < 2n-2$, then everything follows from the inductive hypothesis. If $x_3=2n-2$, then $x_2=1$, $x_1=2n-1$, $x_0=2n-2$. It remains to prove the statement in this case. We have:
$x_3=2n-2$, $x_4=2n-3$, $x_5=1$, $x_6=2n-4$, $x_7=2n-5$, $x_8=1$, ..., $x_{3k}=2n-2k$, ..., $x_{3n}=0$.

b) First we rearrange the terms $x_0, x_1$ and $x_2$ in descending order. The resulting sequence may differ from the original one only in the order of the first three terms (see this for yourself). In addition, it, very indo, kills: defining the term $x_k$, we have all the differences that were used to determine the term $x_{k-1}$, plus the differences between $x_{k-1}$ and the remaining terms of the sequence (with lower numbers).

Let us now note that for any integer $k>0$
$x_k \geqslant x_{k+1}+x_{k+2}$.

Otherwise we would have
$x_{k+2}>x_k-x_{k+1}=|x_k-x_{k+1}|$, which is impossible.

Let's assume that $x_{20} \geqslant 1$. Then, of course, $x_{19} \geqslant 1$, and by (*) we have: $x_{18} \geqslant x_{19}+x_{20} \geqslant 2$, $x_{17} \geqslant x_{18}+x_{19} \geqslant 2+1=3$, $x_{16} \geqslant x_{17}+x_{18} \geqslant 3+2=5$, ..., $x_0 \geqslant x_1+x_2 \geqslant 4181+6765=10946>10000$, which is counter to the problem.

S. Fomin

M392. According to those approximate doses with constant speeds, decisions are made. At the initial moment they were not on the same straight line. Prove that they can be on the same line no more than twice.

We present two solutions to this problem. The first (geometric) uses a technique typical of physics: transition to a driving reporting system; the second (analytic) can be briefly written using the “pseudo-scalar product” of vectors.

I. We will write the condition that the point $P, Q, R$ is on the same line as follows: $R \in (PQ)$ (at $P \neq Q$).

Let's move to the coordinate system associated with one of the solutions. Then the problem will be reduced to the following: a fixed point $A$ is given on the plane; prove that if points $P$ and $Q$ move smoothly and uniformly, then proper $A \in (PQ)$ can occur no more than twice (if it is known that at the initial moment $t=0$ it will not happen).

Let at some point in time $t_1$ solutions $P$ and $Q$ be at points $B$ and $C$ such that $A \in (BC)$. Let us introduce another “fictitious” solution $Q'$: $Q'$ is located at point $B$ at $t=t_1$ and moves parallel to the solution path $Q$ so that it is always $A \in (QQ')$ (Fig. 1, ​​a). It is clear that conditions $A \in (PQ), A \in (PQ')$ and $Q' \in (AP)$ are equivalent *). Obviously, $Q'$ moves uniformly. Therefore, straight line $PQ'$ maintains the same direction - it moves parallel to itself - and can only pass through point $A$ (Fig. 1, o) at one moment of time $t_2$ (different from $t_1$). (The possibilities that the points $P$ and $Q'$ coincide all the time or that they move along the straight line $AB$ are excluded from the initial conditions.)

⟦folio 31⟧

It is not difficult to give examples showing that three solutions of a real can appear on the same straight line twice, once, or not at all. Before moving on to solution II, let us note without proof one fact from which our problem easily follows. If two points $P$ and $Q$ move uniformly along two lines, then all lines $PQ$ either pass through one point, or are parallel to one direction, or (and this is the general case) - touch one parabola - the “envelope” of this family of lines (Fig. 2). It is clear that through each point $A$ of the plane there are at most two lines of this family.

II. Let us introduce the coordinate system $Oxy$. The condition that two vectors $v$ and $w$ with coordinates $(v_x; v_y)$ and $(w_x; w_y)$ are collinear (parallel to one direction) can obviously be written as follows: $v_x w_y = v_y w_x$. Let us introduce the notation

$$[v, w] = v_x w_y - v_y w_x.$$ (1)

A numerical function of a pair of vectors $(v, w) \rightarrow [v, w]$ has, as is easy to verify, the following property:

$$[\lambda v, w] = [v, \lambda w] = \lambda [v, w];$$
$$[v + w, u] = [v, u] + [w, u],$$
$$[u, v + w] = [u, v] + [u, w]$$ (2)

for any vectors $u, v, w$ and any number $\lambda$. As already stated, $[v, w] = 0$ if and only if $v$ and $w$ are collinear. (The value $[v, w]$ has a simple geometric meaning: its model is equal to the area of ​​the parallelogram, the lines of which are represented by the vectors $v$ and $w$, and the sign depends on the “orientation” of the pair $(v, w)$, with $[v, w] = -[w, v]$ (Fig. 3); but we will not need these properties.)

Let us now proceed directly to solving the problem. Let $P, Q$ and $R$ move rectilinearly and uniformly. Then

$$\vec{RP} = \vec{a} + t \vec{v}, \quad \vec{RQ} = \vec{b} + t \vec{w},$$ (3)

where $t$ is time, $\vec{a}, \vec{b}, \vec{v}, \vec{w}$ are vectors independent of $t$. It is not difficult to obtain formulas of the form (3), use the fact that if some point $M$ moves with a speed $\vec{u}$, then $\vec{OM} = \vec{OM}_0 + t \vec{u}$, where $\vec{M}_0$ is the position of $M$ at $t = 0$, $O$ is a fixed point of the plane. Taking into account (1) - (3), conditions $R \in (PQ)$ can be written as follows:

$$[v, w] t^2 + ([a, w] + [b, v]) t + [a, b] = 0.$$ (4)

We have obtained a quadratic equation for $t$. Although some of its coefficients can turn to 0, but for $t = 0$, as stated in conditions (4), it is not satisfied, so (4) is not the same. Therefore, $R \in (PQ)$ for at most two values ​​of $t$.

N. Vasiliev

M393. Find the amount

$$\varphi(0) + \varphi\left(\frac{1}{n}\right) +$$
$$+ \varphi\left(\frac{2}{n}\right) + \dots + \varphi(1),$$

if $\varphi(x) = \frac{4^x}{4^x + 2}$.

We will solve a more general problem, namely, when $\varphi(x) = \frac{a^{2x+k}}{a^{2x}+a}$, where $k$ is any real number, and $a > 0$ (putting $k = 0$, $a = 2$, we get the answer to problem M393).

Let's find an expression for $\varphi(1-x)$:

$$\varphi(1-x) = \frac{a^{-2x+k+2}}{a^{-2x+2}+a} = \frac{a^{k+1}}{a^{2x}+a}.$$

⟦folio 32⟧

Adding $\varphi(1-x)$ and $\varphi(x)$, we get:

$$\varphi(x) + \varphi(1-x) = \frac{a^{2x+k} + a^{k+1}}{a^{2x} + a} = a^k.$$

Let the required sum be equal to $S$. Then

$$S = \varphi(0) + \varphi\left(\frac{1}{n}\right) + \ldots + \varphi\left(\frac{n-1}{n}\right) + \varphi(1),$$

$$S = \varphi(1) + \varphi\left(\frac{n-1}{n}\right) + \ldots + \varphi\left(\frac{1}{n}\right) + \varphi(0).$$

Adding these two equalities and taking into account that

$$\varphi(0) + \varphi(1) = \varphi\left(\frac{1}{n}\right) + \varphi\left(\frac{n-1}{n}\right) = \ldots =$$

$$= \varphi(x) + \varphi(1-x) = a^k,$$

we get

$$2S = (n+1)a^k,$$

that is, $S = \frac{1}{2}(n+1)a^k$.

So the answer in problem M393 is:

$$S = \frac{1}{2}(n+1).$$

S. Berkolaiko

**M394. a) Vectors $a, b, c, d$ are given on the plane, the sum of which is 0. Prove the inequality:**

b) for four numbers and c) four vectors in three-dimensional space, the sum of which is 0.

**Fig. 5.**

**Fig. 6.**

We will now solve only problem a) (at the Olympiad, schoolchildren in grades 9-10 were offered exactly this); A note will be devoted to solving problems b) and c), which we will publish in one of the upcoming issues of the journal.

Putting aside the vectors $\vec{MN} = \vec{a}, \vec{NP} = \vec{b}, \vec{PQ} = \vec{c}, \vec{QM} = \vec{d}$ successively, we obtain a closed broken line (since $\vec{a} + \vec{b} + \vec{c} + \vec{d} = 0$). By changing the order of the vectors $\vec{a}, \vec{b}, \vec{c}, \vec{d}$, one can obtain several such broken lines. Let us show that among these broken lines there is self-section. To do this, let's take one of our broken lines. If one of its vertices, for example $Q$, lies inside the triangle $MNP$ formed by three vertices (Fig. 4, a), then we set aside the vector $\vec{QQ'} = \vec{MN}$. Since in this case $\vec{Q}'N = \vec{QM}$, the broken line $MNPQ$ can be replaced by the self-cutting broken line $NPQQ'$ (Fig. 4, b). If $MNPQ$ is a convex broken line, then first we carry out the construction shown in figure 5.

So, let $\vec{MN} = \vec{a}, \vec{NP} = \vec{b}, \vec{PQ} = \vec{c}, \vec{QM} = \vec{d}$, and the segments $NP$ and $QM$ have a common point $R$ (Fig. 6). Then $|MR| + |PR| \geq |PM|, |NR| + |QR| \geq |QN|$, whence $|MR| + |PR| + |NR| + |QR| \geq |PM| + |QN|$. But $|PM| = |PQ + QM| = |c + d|,$

$$|QN| = |QM + MN| = |a + d|,$$

a $|MR| + |PR| + |NR| + |QR| = |QM| + |NP| = |b + d|$. Hence,

$$|b| + |d| \geq |a + d| + |c + d|.$$

(1)

Moreover, it is very important that $|a| + |c| \geq |a + c|$ and that $|a + c| = |b + d|$ (see Fig. 6); That's why

$$|a| + |c| \geq |b + d|.$$

(2)

Adding inequalities (1) and (2), we obtain what was required.

Yu. Nonin

⟦folio 33⟧

F397. There is the following draft of a lematic annaram. The upper surface of the large flat plate is fired at a constant temperature of 0°C, and the lower surface is fired at a temperature of 100°C. The inventor claims that by dipping plastic we will soar in the air like an airship. Explanation, therefore. Estimate the order of magnitude of the lifting force of a poppy plate with an area of ​​1 m² at an air temperature of 20°C.

Air molecules incident on the plate have a root-mean-square speed equal to $\bar{v}_{\text{cp.кв.}} = \sqrt{\frac{3kT}{m}}$, where $T$ is the air temperature, $m$ is the mass of the molecules. The average absolute value of the design velocity of molecules on the axis $OY$, perpendicular to the surface of the plate, is equal to $\bar{v}_y \approx \frac{\bar{v}_{\text{cp.кв.}}}{\sqrt{3}} = \sqrt{\frac{kT}{m}}$.

When colliding with a plate, the “temperature” of the molecules becomes equal to the temperature of the plate. This means that after reflection from the top surface

$$\bar{v}'_y = \sqrt{\frac{kT_1}{m}},$$

and after reflection from the upper surface

$$\bar{v}'_y = \sqrt{\frac{kT_2}{m}}.$$

As a result, the projection $p_y$ of the momentum of molecules falling on the lower surface of the plate changes upon collision by the following values:

$$\Delta p'_y = m \left( \sqrt{\frac{kT}{m}} + \sqrt{\frac{kT_1}{m}} \right),$$

and a molecule falling on the upper surface - by values

$$\Delta p''_y = m \left( \sqrt{\frac{kT}{m}} + \sqrt{\frac{kT_2}{m}} \right).$$

During time $\Delta t$, molecules located from the plate at a distance equal to $\bar{v}_y \Delta t$ reach each surface. The number of these molecules is $N = nv_y s \Delta t$, where $n$ is the number of molecules per unit volume, $s$ is the area of ​​the plate.

In accordance with Newton's second and third laws, forces acting on the plate in the upper direction are equal in absolute magnitude to the change in the projections of molecular impulses per unit time. An upward force acts on the bottom surface of the plate (Fig. 7)

$$|\vec{F}_1| = \frac{N \Delta p'_y}{\Delta t} = m n \bar{v}_y s \left( \sqrt{\frac{kT_1}{m}} + \sqrt{\frac{kT}{m}} \right),$$

and on the top - a downward force

$$|\vec{F}_2| = \frac{N \Delta p''_y}{\Delta t} = m n \bar{v}_y s \left( \sqrt{\frac{kT_2}{m}} + \sqrt{\frac{kT}{m}} \right).$$

Since $T_1 > T_2$, then the equal leading $\vec{R}$ of forces $\vec{F}_1$ and $\vec{F}_2$ is directed upward and equal in absolute value

$$|\vec{R}| = |\vec{F}_1| - |\vec{F}_2| = m n \bar{v}_y s \left( \sqrt{\frac{kT_1}{m}} - \sqrt{\frac{kT_2}{m}} \right) = nsk \sqrt{T} \left( \sqrt{T_1} - \sqrt{T_2} \right).$$

The number of molecules contained in volume $V$ of air at pressure $p$ and temperature $T$ is equal to $N_V = v \cdot N_A$, where $v$ is the number of air molecules in volume $V$, $N_A$ is Abogadro’s number. But $v = \frac{M}{\mu} = \frac{pV}{RT}$. So the number of molecules per unit volume

$$n = \frac{p}{RT} N_A.$$

⟦folio 34⟧

Thus,

$$|\vec{R}| = \frac{pN_A sk}{RT} \sqrt{T_1} - \sqrt{T_2} = \frac{ps}{\sqrt{T}} (\sqrt{T_1} - \sqrt{T_2}).$$

Substituting the data into the quantity conditions in this expression (counting $p = 10^5 \text{h}/\text{m}^2$), we obtain

$$|\vec{R}| \approx 1,5 \cdot 10^4 \text{ h}.$$

F398. An error was made when connecting a seven-lamp meter with two switches. As a result, when one of the switches was closed, all three lamps burned at incomplete intensity. When closing, the others were still burning), and the same effect was achieved by closing both switches at the same time. When the switches were open, all three lamps did not light. Draw a diagram of the completed installation and explain the resulting effects.

F399. Three small identical metal balls in a vacuum are placed at the vertices of an equilateral triangle. The balls are connected one at a time to a remote conductor, which is placed and maintained constant. As a result, the first ball has a charge $Q_1$, and the second one has a charge $Q_2$. Determine the charge of the third ball.

The lamp switching circuit is shown at figure 8. With the key $K_1$ closed and the key $K_2$ open, all three lamps are switched on in series, and therefore they burn with incomplete heat. When both switches are simultaneously closed, lamp $J_1$ is turned on, and lamps $J_2$ and $J_3$ are connected in parallel to a section of the circuit with very little resistance. For example, there are not enough on them, and the lamps do not light. When one key $K_2$ is closed, only the lamp $J_1$ turns on.

Fig. 8.

When each of the balls is connected to a remote conductor, the potential of which F is maintained constant, the potential of the ball becomes equal to F.

The charge $Q_1$ appearing on the first ball is equal to

$$Q_1 = C\varphi,$$

where $C$ is the capacity of the ball.

The potential Ф of the second ball consists of the field potential created by the charge $Q_1$ at a distance $l$ from the first ball ($\varphi_1 = \frac{Q_1}{l}$), and the potential of the “own” field of the charge $Q_2$ ($\varphi_2 = \frac{Q_2}{C}$):

$$\varphi = \varphi_1 + \varphi_2 = \frac{Q_1}{l} + \frac{Q_2}{C}.$$

The potential Ф of the third ball is equal to

$$\varphi = \frac{Q_1}{l} + \frac{Q_2}{l} + \frac{Q_3}{C},$$

where $\frac{Q_1}{l}$, $\frac{Q_2}{l}$ are the corresponding potentials of the fields of charges $Q_1$ and $Q_2$ at a distance $l$ from them, $\frac{Q_3}{C}$ is the potential of the “own” field of charge $Q_3$.

From equality (2), using equality (1), we find $l$:

$$l = \frac{Q_1 C}{Q_1 - Q_2}.$$

Substituting this expression for $l$ into equality (3), we find $Q_3$:

$$Q_3 = C \left[ \varphi - \frac{Q_1 + Q_2}{l} \right] = \frac{Q_2^2}{Q_1}.$$

⟦folio 36⟧

F402. A diverging lens with a focal length $F = -0,6$ m is located so that one of its foci coincides with the stripe in the internal mirror. What is the focal length $F'$ of the mirror if it is known that the system produces a real image of an object placed at any distance in front of the lens? The image is created by rays passing through the lens for the second time after reflection from the mirror.

where
$$\frac{I_2}{I_1} = \frac{R}{r_2}.$$

On the other hand, $\varphi_A = \varphi_C + I_1 r_G$ ($r_G$ is the resistance of the galvanometer), and $\varphi_B = \varphi_C + I_2 r_1$. So
$$\varphi_C + I_1 r_G = \varphi_C + I_2 r_1,$$

where
$$\frac{I_1}{I_2} = \frac{r_G}{r_1}.$$

Comparing expressions (1) and (2), we obtain:
$$\frac{R}{r_2} = \frac{r_G}{r_1},$$

or
$$r_G = \frac{r_1}{r_2} R.$$

Knowing the resistances $r_1$, $r_2$, $R$, you can find the resistance of the galvanometer $r_G$.

◆
A diverging lens always produces a minimal image of the actual source. Therefore, in order for the system to produce a valid image, the intermediate image that is obtained after the rays are reflected from the mirror must be the minimum source for the lens, that is, it must be to the right of the lens.

In fact, from the formula for a diverging lens in the case of a minimal source
$$-\frac{1}{d} + \frac{1}{f} = -\frac{1}{F}$$

it follows that
$$f = \frac{dF}{F - d}.$$

(Recall that $d$ is the distance from the lens to the source, $f$ is the distance from the lens to the image, $F$ is the focal length of the lens.) From (1) it is clear that $f \geq 0$ if $d$ is positive and does not exceed $F$.

Thus, the intermediate image $S_2$ of the source after the mirror (Fig. 14) must be located to the right of the mirror at a distance $f_2$ such that
$$F \leq f_2 \leq 2F.$$

The source for the mirror is the intermediate image $S_1$ - the minimum image of the source $S$, given by the lens after the first refraction of the rays (see Fig. 14). From the lens formula for this case
$$\frac{1}{d_1} - \frac{1}{f_1} = -\frac{1}{F}$$

- we find
$$f_1 = \frac{d_1 F}{d_1 + F}.$$

⟦folio 37⟧

The distance $d_1$ from the source to the lens can vary from 0 to $\infty$. In this case, as follows from formula (3), $f_1$ changes from 0 to $F$. The distance $d_2 = F + f_1$ from the image $S_1$ to the mirror changes from $F$ to $2F$. Recall that this image serves as a source for the mirror. Thus, we need to find at what focal length $F'$ of the mirror the image of a source located at a distance $d_2$ from the mirror such that

$$F \leqslant d_2 \leqslant 2F,$$

(4a)

is obtained at a distance $f_2$ from the mirror such that

$$F \leqslant f_2 \leqslant 2F.$$

(46)

From the mirror formula -

$$\frac{1}{d_2} + \frac{1}{f_2} = \frac{1}{F'}$$

- it follows that

$$\frac{1}{f_2} = \frac{1}{F'} - \frac{1}{d_2}.$$

(5)

According to condition (46)

$$\frac{1}{2F} \leqslant \frac{1}{f_2} \leqslant \frac{1}{F},$$

so the right part of equality (5) lies within

$$\frac{1}{2F} \leqslant \frac{1}{F'} - \frac{1}{d_2} \leqslant \frac{1}{F}.$$

Hence,

$$\frac{1}{2F} + \frac{1}{d_2} \leqslant \frac{1}{F'} \leqslant \frac{1}{F} + \frac{1}{d_2}.$$

The resulting inequality must hold for all arbitrary $d_2$ satisfying conditions (4a). According to this condition

$$\frac{1}{2F} \leqslant \frac{1}{d_2} \leqslant \frac{1}{F},$$

so the focal length $F'$ of the mirror must be such that the conditions

$$\frac{1}{2F} + \frac{1}{F} \leqslant \frac{1}{F'} \leqslant \frac{1}{F} + \frac{1}{2F}.$$

Therefore, $\frac{1}{F'} = \frac{3}{2F}$, or

$$F' = \frac{2}{3} F = 0,4 \text{ m}.$$

I. Slovodetsky
