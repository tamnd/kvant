---
id: 1982-8-resheniya-zadach-m721-m730-f733-f742-9579a45b
issue: kvant_1982_8
year: 1982
number: "8"
title: Solutions to problems M721—M730; F733—F742
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 36
page_last: 50
page_labels: 34, 36, 37, 38, 41, 42, 43, 44, 45, 46, 47, 48
tag: O92T
lang: en
source: kvant_digital
extraction: vision
content_sha256: 4cc320f31af27fe117cfe7cbd1306df7ed089a6a9880d9b29ac25093ec4691bb
prompt_sha256: draft-1
translated_from: content/ru/1982/08/articles/11_resheniya-zadach-m721-m730-f733-f742-9579a45b.md
source_content_sha256: 3b1ebca7d4b03d6ab54e6074339ffdd71f163ada6d5a8003f522e02d85655b45
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 34⟧

key $K$ at the moment $t=0$ to a source of alternating tension $u=U_M \cos \omega t$. Determine the current in the solenoid as a function of time. Construct the graph of this function. The diod and the solenoid are assumed ideal, the inner resistance of the source may be neglected. (10).

V. Skorovarov

P772. An interplanetary space-ship made a soft landing on the Moon. The ship has the form of a disk of radius $r=4\text{m}$, its surface is covered by black (non-reflecting) paint. Can the landing on the Moon be observed from the largest telescope in the world, the Soviet telescope BTA with object lens diameter $D=6\text{m}$, if a photographic plate is placed in the focal plane to take a picture of the area of the Moon where the landing is to take place. Assume that clearly noticeable contrast of the image on the photo (i.e. the minimal relative difference of the dark and light parts of the image) is $k=0.05$. The distance from Earth to Moon is $L=4 \times 10^5\text{km}$; the picture is taken in light with wavelength $\lambda=0.6\text{mkm}$. Estimate the size of letters arranged by astronauts on the moon surface that can be read from the Earth using the BTA telescope. (10)

S. Kozel

Problem solutions

M721—M730; F733—F742

M721. Each side of the triangle is divided into 3 equal parts. The division points serve as the vertices of two triangles, the intersection of which is a hexagon. Find the area of ​​this hexagon if the area of ​​the given triangle is $S$.

Answer: $\frac{2}{9} S$. Let us show that this triangle can be divided into 27 equal-sized triangles, 6 of which make up the hexagon to be solved in the task. Let $K, L, M, N, P, Q$ be the points dividing the sides of triangle $ABC$, as specified in the conditions (see figure). Note that the segments $KM$ and $QN$, $QL$ and $PM$, $KP$ and $LN$ are parallel and correspond to the media of this triangle. For example, line segment $KM$ is parallel to media $AD$ because $\frac{|BK|}{|BA|} = \frac{|BM|}{|BD|} = \frac{2}{3}$ and therefore triangles $BKM$ and $BAD$ are prepared. Drawing from the division points the remaining segments parallel to the media, as well as the medians themselves, we obtain the required partition.*) In fact, the hexagon is divided into 6 congruent triangles (on figure - heads), another 12 triangles (white) are congruent to them, and the remaining 9 (red) are equal in size. (Say, the areas of triangles $MEN$ and $MFE$ are equal because their sides $EN$ and $EF$ are congestive, and the heights dropped to these sides from vertex $M$ are the same.) Thus, the area of ​​the hexagon is $6 \cdot \frac{S}{6+12+9} = \frac{2}{9} S$.

A. Edorov

M722. At points $A_1, A_2, \dots, A_n$ located around the circle, the numbers 1, 2, ..., $n$ will be scattered in some order. a) Prove that the sum of $n$ models of differences of numbers is not less than 2n—2. b) For how many arrangements is this sum equal to 2n-2?

Let the numbers 1 and $n$ stand at points $A_i$ and $A_j$ respectively. We will calculate the differences between neighboring numbers, using figure: the number at the beginning of each arrow is subtracted from the number at the end.

*) For the solution to be perfect, we must also prove that the segments we have constructed actually intersect in threes, as shown in figure. Let, for example, $H$ be the intersection point of $[KP]$ and $[LQ]$. Then triangles $LHP$ and $BGC$ are prepared with center $A$, hence $H \in [AD]$ (G is the intersection point of the medians). Likewise, the intersection point $E$ of $[LN]$ and $[MP]$ lies on $AD$ because triangles $MEN$ and $BGC$ are prepared with center $D$, etc.

⟦folio 36⟧

It is clear that none of the sums of numbers $b_1, b_2, \dots, b_{k+1}$ belongs to the set $A$. The existence of the set $B$ is proven.

By virtue of the lemma, to state the answer to the question of the problem, it is enough to prove that the set $S = \{a^k | a \geq 1, k \geq 2\}$ of all possible powers of natural numbers has zero density.

Let us estimate the number of $v_n(S)$ degrees that do not exceed the number $n$. If $a^k \leq n$, then $a \leq \sqrt[k]{n}$. Therefore, there are at most $[\sqrt[k]{n}]$ natural numbers whose $k$th power does not exceed $n$, where $[x]$ is the integer part of the number $x$. In particular, for $k > m = [\log_2 n]$ there is only one such number - one. Hence,

$$v_n(S) \leq \frac{[\sqrt{n}] + [\sqrt[3]{n}] + \ldots + [\sqrt[n]{n}]}{n} \leq \frac{\sqrt{n} \log_2 n}{n} = \frac{\log_2 n}{\sqrt{n}}.$$

Passing to the limit at $n \to \infty$, we obtain

$$d(S) = \lim_{n \to \infty} v_n(S) \leq \lim_{n \to \infty} \frac{\log_2 n}{\sqrt{n}} = 0.$$

L. Gurvits

**M724. Several cuttings crawl along the plane, the speeds of which are equal in magnitude but different in direction. Prove that, no matter how the cuttings are located at the beginning, after some time they will be at the vertices of a convex polygon.**

Let at the initial moment Cherenakh be at points $A_1, \dots, A_n$ located in a circle of radius $R$ with center at point $O$. Let us plot the velocity vectors of the Cherenakh $\vec{v}_1, \dots, \vec{v}_n$ from the point $O$. It is clear that the ends $V_1, \dots, V_n$ of these vectors are the vertices of some convex $n$-gon inscribed in a circle of radius $v$, equal to the value of the velocity of any handle. Let's construct circles of radius $e$ with centers at points $V_1, \dots, V_n$. For a sufficiently small $e$, any polygon $B_1B_2\dots B_n$ whose vertices belong to these circles is very indo, the same will be convex. (As $e$ we can take, for example, the minimum of the distance from the points $V_i$ to the lines connecting the vertices $V_i$ - see figure.)

Let after time $T$ be at points $A'_1, \dots, A'_n$, and let, during thunderstorm with center $O$ and coefficient $\frac{1}{T}$, these points turn into points $B_1, \dots, B_n$. Let us prove that for sufficiently large $T$ the points $B_1, \dots, B_n$ fall into the circles we have constructed, that is, that $|V_iB_i| < \varepsilon$ for $i=1, \dots, n$. The vector $\overrightarrow{A_iA'}_i$, on which the $i$-th handle moved during the time $T$, is equal to $\overrightarrow{Tv}_i$. Therefore, $\overrightarrow{OA'}_i = \overrightarrow{OA}_i + \overrightarrow{Tv}_i$, and $\overrightarrow{OB}_i = \frac{1}{T}\overrightarrow{OA'}_i = \overrightarrow{v}_i + \frac{1}{T}\overrightarrow{OA}_i = \overrightarrow{OV}_i + \frac{1}{T}\overrightarrow{OA}_i$. Therefore, $|V_iB_i| = \frac{1}{T}|OA_i| \leq R/T$. This means that at $T > \frac{R}{\varepsilon}$ the points $B_i$ fall into circles of radius $e$ with centers $V_1, \dots, V_n$, the polygon $B_1 \dots B_n$ will be convex, and then the points $A'_1, \dots, A'_n$, in which the kernel $T$ appears, serve as the vertices of the convex polygon.

V. Prasolov

**M725.* Put $r_n = \cos^n \frac{\pi}{7} + \cos^n \frac{3\pi}{7} + \cos^n \frac{5\pi}{7}$. Find $a)$ $r_1$ and $r_2$, $b)$ $r_3$ and $r_4$. Prove that $r_n$ is a rational number for any $n$.

Let $c_k = \cos \frac{\pi k}{7}$ at $k=0, \pm 1, \pm 2, \pm 3, \dots$. Note that $c_k$ is the projection onto the $Ox$ axis of a single vector $\vec{e}_k$ forming an angle $\frac{\pi}{7}$ with the ray $x \geq 0$, $y=0$ (see figure). It is easy to verify that $c_{7+m} = c_{7-m} = -c_m$.

a) It is not difficult to prove that

$$\vec{e}_1 + \vec{e}_3 + \vec{e}_5 + \vec{e}_7 + \vec{e}_-3 + \vec{e}_-1 = 0$$

(one of the proofs: when turning through an angle $\frac{2\pi}{7}$ this

⟦folio 37⟧

the system of vectors turns into itself; in this case the sum does not change and, therefore, is equal to 0).

From (1) it immediately follows that $c_7 + 2c_1 + 2c_3 + 2c_5 = 0$, that is
$$r_1 = c_1 + c_3 + c_5 = -\frac{1}{2} c_7 = \frac{1}{2}.$$

Using the well-known formula $2\cos^2\alpha = 1 + \cos 2\alpha$, we get $2c_1^2 = 1 + c_2$, $2c_3^2 = 1 + c_6$, $2c_5^2 = 1 + c_{10}$, and since $c_2 = -c_5$, $c_6 = -c_1$, $c_{10} = -c_3$, we find
$$r_2 = c_1^2 + c_3^2 + c_5^2 = \frac{1}{2} (3 - c_1 - c_3 - c_5) = \frac{5}{4}.$$

6), c) Let us prove that $c_1, c_3, c_5$ are roots of a third-degree polynomial with rational coefficients. Consider the polynomial
$$p(x) = (x - c_1)(x - c_3)(x - c_5) = x^3 + a_1 x^2 + a_2 x + a_3,$$
whose roots are $c_1, c_3$ and $c_5$. Let us express the coefficients of this polynomial in terms of its roots. Opening the brackets, we get
$$a_1 = -(c_1 + c_3 + c_5) = -r_1 = -\frac{1}{2};$$
$$a_2 = c_1 c_3 + c_3 c_5 + c_5 c_1 = \frac{1}{2} ((c_1 + c_3 + c_5)^2 -$$
$$-c_1^2 - c_3^2 - c_5^2) = \frac{r_1^2 - r_2}{2} = \frac{1}{2} \left(\frac{1}{4} - \frac{5}{4}\right) = -\frac{1}{2};$$
$$a_3 = -c_1 c_3 c_5 = -c_1 c_2 c_4 = -\cos \frac{\pi}{7} \cdot \cos \frac{2\pi}{7} \cdot \cos \frac{4\pi}{7} =$$
$$= -\frac{\sin \frac{\pi}{7} \cdot \cos \frac{\pi}{7} \cdot \cos \frac{2\pi}{7} \cdot \cos \frac{4\pi}{7}}{\sin \frac{\pi}{7}} =$$
$$= -\frac{\sin \frac{2\pi}{7} \cdot \cos \frac{2\pi}{7} \cdot \cos \frac{4\pi}{7}}{2 \sin \frac{\pi}{7}} =$$
$$= -\frac{\sin \frac{4\pi}{7} \cdot \cos \frac{4\pi}{7}}{4 \sin \frac{\pi}{7}} = -\frac{\sin \frac{8\pi}{7}}{8 \sin \frac{\pi}{7}} = \frac{1}{8}.$$

So, for each $j=1, 3, 5$ the equality
$$c_j^3 - \frac{1}{2} c_j^2 - \frac{1}{2} c_j + \frac{1}{8} = 0.$$
This means that for any $n \geqslant 2$
$$c_j^{n+1} = \frac{1}{2} c_j^n + \frac{1}{2} c_j^{n-1} - \frac{1}{8} c_j^{n-2}.$$
Adding three such equalities (for $j=1, 3, 5$), we obtain for $r_n = c_1^n + c_3^n + c_5^n$ the recurrent formula
$$r_{n+1} = \frac{1}{2} r_n + \frac{1}{2} r_{n-1} - \frac{1}{8} r_{n-2},$$
allowing one to calculate $r_{n+1}$ if $r_n, r_{n-1}, r_{n-2}$ is known. Since, due to a), $r_1 = \frac{1}{2}, r_2 = \frac{5}{4}$, and $r_0 = 3$, we find
$$r_3 = \frac{1}{2} \cdot \frac{5}{4} + \frac{1}{2} \cdot \frac{1}{2} - \frac{1}{8} \cdot 3 = \frac{1}{2},$$
$$r_4 = \frac{1}{2} \cdot \frac{1}{2} + \frac{1}{2} \cdot \frac{5}{4} - \frac{1}{8} \cdot \frac{1}{2} = \frac{13}{16}.$$

⟦folio 38⟧

It is clear that the numbers $r_n$ for each $n$ are rational. (For more information about the application of the idea in solving, see the article “Consider the difference”, «Kvant», 1981, No. 4.)

N. Vasiliev

M726. A point inside a regular 2n-space is connected to the vertices. The resulting 2n triangles are colored alternately in 轮廓 and red. Prove that the sum of the areas of the head triangles is equal to the sum of the areas of the red ones a) for n=4, 6) for n=3, c) for an arbitrary natural number n.

Since in a regular polygon the lengths of all sides are equal, it is enough to prove that the sum of the lengths of the heights of the red triangles is equal to the sum of the lengths of the heights of the head triangles (see Fig. 1). By dividing the triangles into pairs adjacent to opposite sides, we immediately obtain a statement of the problem.

Fig. 1. Fig. 2

For odd n, by continuing the “red” sides of the 2n-removal, we obtain the correct n-receiver (Fig. 2). The head n-sole constructed in the same way is congested to red. The area of ​​the head n-sleeve is equal to the sum of the lengths of the heights of the head triangles multiplied by half the length of its side. The same is true for the red n-soldier. This implies the equality of the sums of the lengths of the heights of the head and red triangles and, at the same time, the statement of the problem.

V. Prasolov

M727. Prove inequality $a^2+b^2+c^2+2abc<2$, where a, b, c are the side lengths of the triangle perimeter 2.

If a, b and c are the lengths of a side of a triangle of perimeter 2, then a<1, b<1, c<1 (otherwise one of the sides of the triangle will be greater than the sum of the other two). Therefore (1-a)(1-b)(1-c)>0. Expanding the brackets and transforming the left part, we get

$$1 - (a+b+c) + ab+bc+ac - abc = -1 + \frac{a^2+b^2+c^2}{2} + ab+bc+ac - \frac{a^2+b^2+c^2}{2} - abc = -1 + \frac{(a+b+c)^2}{2} - \frac{a^2+b^2+c^2}{2} - abc = 1 - \frac{a^2+b^2+c^2}{2} - abc > 0,$$

and this means that $a^2+b^2+c^2 < 2(1-abc)$.

A. Egorov

M728. Let A, B, C be the vertices of a parallel plane adjacent to its vertex P, and let Q be the vertex opposite to P. Prove that a) the distances

⟦folio 41⟧

($a_{n+3} = a_{n+2} = a_{n+1} = a_n = a$). It also follows from the above that the numbers $a_n$ sequentially run through the weight of the natural series.

Let us now derive an explicit formula for $a_n$. In the sum $a_n = (a_n - a_{n-1}) + (a_{n-1} - a_{n-2}) + \dots + (a_2 - a_1)$ all terms are equal to 0 or 1, and exactly as many as there are numbers of the first kind not exceeding $n$. Therefore, $a_n$ is equal to the number of numbers of the first kind not exceeding $n$. It is easy to show that

$$a_n = \left[ \frac{n}{2} \right] - \left[ \frac{n}{4} \right] + \left[ \frac{n}{8} \right] - \dots$$

(1)

(the number of non-zero terms here is finite, or $n < 2^m$ for some $m$). To prove formula (1), we note that $\left[ \frac{n}{2} \right], \left[ \frac{n}{4} \right], \left[ \frac{n}{8} \right], \dots$ is the number of numbers not exceeding $n$ and divisible by 2, 4, 8, .... Therefore, the difference $\left[ \frac{n}{2} \right] - \left[ \frac{n}{4} \right]$ is equal to the number of numbers from 1 to $n$ that are divisible by 2 and not divisible by 4, $\left[ \frac{n}{8} \right] - \left[ \frac{n}{16} \right]$ is the number of numbers from 1 to $n$, divisible by 8 but not divisible by 16, etc.

Let us calculate $a_n$ using formula (1) for $n = 3 \cdot 2^k$. If $k$ is odd, then

$$a_{3 \cdot 2^k} = \frac{3 \cdot 2^k}{2} - \frac{3 \cdot 2^k}{4} + \dots + \frac{3 \cdot 2^k}{2^k} - \left[ \frac{3}{2} \right] =$$

$$= 3(2^{k-1} - 2^{k-2} + \dots + 1) - 1 = 3 \frac{2^k + 1}{3} - 1 = 2^k.$$

Note that in this case $n$ and $n+2 = 2(3 \cdot 2^{k-1} + 1)$ are numbers of the first kind. Therefore, if $k$ is odd, the number $2^k$ occurs 2 times in our sequence. Let $k$ be an even number. Then again

$$a_{3 \cdot 2^k} = \frac{3 \cdot 2^k}{2} - \frac{3 \cdot 2^k}{4} + \dots + \left[ \frac{3}{2} \right] = 3 \frac{2^k - 1}{3} + 1 = 2^k.$$

But now $3 \cdot 2^k$ is a number of the second kind. Therefore, the number $2^k$ with even $k$ is repeated among the numbers $a_n$ four times. Along the way, we proved statement (d), since $a_n = n/3$ for all $n = 3 \cdot 2^k$.

e) Answer: yes. Let us assume that $n$ is divisible by 4. Then, according to formula (1)

$$a_n = \frac{n}{2} - \frac{n}{4} + \left[ \frac{n}{8} \right] - \left[ \frac{n}{16} \right] + \dots = \frac{n}{4} + a_{\frac{n}{4}}.$$

(2)

Consider the sequence $a_{n_m}$, where $n_m = \frac{4^m - 1}{3}$ for $m = 1, 2, \dots$ ($n_m$ is an odd integer for any $m$). Note that $\frac{n_m - 1}{4} = \frac{4^m - 4}{3 \cdot 4} = \frac{4^{m-1} - 1}{3} = n_{m-1}$. Therefore, according to formula (2) for $n = n_m - 1$

$$a_{n_m} = a_{n_m-1} = n_{m-1} + a_{n_{m-1}}.$$

Hence,

$$a_{n_m} = n_{m-1} + n_{m-2} + \dots + n_1 + a_1 = \frac{n_m}{3} - \frac{m}{3}.$$

For $m = 6000$ we get $\left| a_{n_m} - \frac{n_m}{3} \right| = 2000 > 1982$.

e) Note that in formula (1) the number of terms different from zero is equal to $v = [\log_2 n]$. That's why

$$\left| a_n - \left( \frac{n}{2} - \frac{n}{4} + \frac{n}{8} \right) \right| \leq v,$$

since, by removing the signs of the whole part, we make an error in each term that is less than 1. The sum of the geometric progression is in parentheses. Calculating it, we get

⟦folio 42⟧

$$\left| a_n - \frac{n \left( 1 - \left( -\frac{1}{2} \right)^v \right)}{3} \right| \leq \log_2 n$$

or
$$\left| \frac{a_n}{n} - \frac{1}{3} + \frac{(-1)^v}{3 \cdot 2^v} \right| \leq \frac{\log_2 n}{n}.$$
And since $\frac{(-1)^v}{3 \cdot 2^v} \to 0$ and $\frac{\log_2 n}{n} \to 0$ at $n \to \infty$,
$$\lim_{n \to \infty} \frac{a_n}{n} = \frac{1}{3}.$$

V. Shevelev

F733. A dumbbell of length $l$ (Fig. 1) rests on a “half-frame” with base radius $R$. Find the period of small oscillations of the dumbbell.

Fig. 1.

Fig. 2.

Let the dumbbell be rotated through a small angle $\alpha$ relative to the equilibrium position (Fig. 2); point $B$ is the point of contact of the rod with the received core; $A\hat{O}B = \alpha$ (the surface is rough, and the dumbbell does not slip). The moments of force that arise tend to return the dumbbell to the equilibrium position. Since the angle $\alpha$ is small, we can assume that the dumbbell balls will move along arcs of circles of radii
$$r_1 \approx \frac{l}{2} - |AB| = \frac{l}{2} - R\alpha, \quad r_2 = \frac{l}{2} + R\alpha.$$
The speeds of the balls will be equal, respectively.
$$v_1 = x_1' = (r_1\alpha)' = \alpha' \left( \frac{l}{2} - 2R\alpha \right), \quad v_2 = x_2' = (r_2\alpha)' = \alpha' \left( \frac{l}{2} + 2R\alpha \right).$$
The total energy of the dumbbell remains constant and equal to its potential energy $\Pi_0$ at the moment of maximum deviation from the equilibrium position. When the dumbbell is tilted at an angle $\alpha$ from its equilibrium position, its energy is equal to
$$\Pi_1 + K = mg(R + x_2) + mg(R - x_1) + \frac{mv_1^2}{2} + \frac{mv_2^2}{2} = m \frac{l^2(\alpha')^2}{4} + 2mgR \left( 1 + \frac{\alpha^2}{2} \right) = \Pi_0$$
(m is the mass of each ball; we consider the rod to be unknown; when calculating $v_1^2$ and $v_2^2$ we neglected terms of order $\alpha^2(\alpha')^2$). Let's differentiate what we got:
$$\frac{ml^2\alpha' \alpha''}{2} + 2mgR\alpha' = 0,$$
where
$$\alpha'' = - \frac{4gR}{l^2} \alpha.$$
The resulting equation is the equation of harmonic oscillations with frequency $\omega = \sqrt{4gR/l^2}$. Therefore, the period of small oscillations of the dumbbell is equal to
$$T = \frac{2\pi}{\omega} = \pi l \sqrt{\frac{1}{gR}}.$$
A. Frolov

F734. A rope, attached at one end to the side surface of the cylinder at its base of radius $r$, is wound around the cylinder $k$ times

The tension force of the rope acting on the load is directed perpendicular to the speed of the load. Consequently, the absolute value of the speed of the load remains constant and equal to $v$.
Consider the movement at the moment when the rope

⟦folio 43⟧

(k is an integer). A zruz is attached to the free end of the vervika. The load is given a speed v directed along the radius of the cylinder (Fig. 1). How long will it take for all the rope to be wound around the cylinder again? The cylinder is fixed on the main surface.

Fig. 1.

completely unwound from the cylinder and the load is at point C (Fig. 2). In a short period of time Δt, the load will move to point C'. Since Δt is small, the angle α at which the entire rope will rotate is small and

$$\alpha = \frac{v \cdot \Delta t}{l} = \frac{\Delta l}{r} \Rightarrow rv \cdot \Delta t = l \cdot \Delta l = \Delta \left( \frac{l^2}{2} \right).$$

From the last equality we find the time during which the entire rope of length l is wound around the cylinder:

Fig. 2.

$$t = \frac{l^2}{2rv}.$$ In the same amount of time, the rope is unwound from the cylinder, and the load ends up at point B (see Fig. 2). The time it takes for the load to move from point B to point C is equal to τ = πl/v.

Thus, the complete rope, after which a rope of length l = 2πrk is unwound from the cylinder and wound around it again, is equal to

$$T = 2t + \tau = \frac{4\pi^2k^2r}{v} + \frac{2\pi^2rk}{v} = \frac{2\pi^2kr}{v} (2k + 1).$$

B. Mukushev

F735. Two identical inductors connected via switches K1 and K2 to a source with a constant EMF and internal resistance r (see Fig.ok). At the initial moment of activation, both keys are open. Then keys K1 are closed first, and then keys K2. Determine the magnitude of the current flowing through the switches K1 at the moment of closing the switches K2, if it is known that after closing the switches K2, the steady-state current through the switches K1 is twice as large as the steady-state current through the switches K2. Neglect the active resistance of the coil.

◆

After closing key K1, the current through coils 1 (see Fig.nok) will increase. Let at the moment when the switches K2 are closed, the magnitude of this current is equal to I0. After closing key K2, the directions at the ends of the coil will be equal. Neglecting the active resistance of the coil, we can write this condition in the form

$$L \frac{dI_1}{dt} = L \frac{dI_2}{dt},$$

where L is the inductance of the coil, and I1 and I2 are points in coils 1 and 2, respectively, at some arbitrary moment in the turn after the switch K2 is closed. The same condition can be written in another form:

$$\frac{d(I_1 - I_2)}{dt} = 0,$$ or I1 - I2 = const,

that is, the difference between the absolute values ​​of the currents in the coils at any moment during the operation (with both switches closed) remains constant. Let's find this difference I1 - I2 based on the initial conditions, that is, at the moment of connecting the key K2. At this moment I1 = I0 and I2 = 0; therefore, I1 - I2 = I0.

In steady state, the coils will be accurate; let's denote them I_{yct.1} and I_{yct.2}. The potential difference at the ends of the coil, and therefore at the ends of the battery, will be zero. If current I6 flows through the battery at this time, then

$$\varepsilon - I_6 r = 0.$$

Therefore, in steady state, the flow through the battery will be equal to I6 = ε/r. From the charge conservation condition we can write

$$I_{yct.1} + I_{yct.2} = I_6 = \varepsilon/r.$$

(1)

Condition for maintaining the charge of absolute current values

⟦folio 44⟧

Through the coils it is also carried out to set their currents; That's why

$$I_{\text{уст. 1}} - I_{\text{уст. 2}} = I_0.$$

(2)

Solving equations (1) and (2) together, we obtain

$$I_{\text{уст. 1}} = \frac{I_0 + \mathcal{E}}{r}, \quad I_{\text{уст. 2}} = \frac{\mathcal{E}}{r - I_0}.$$

Using the given correspondence to set their currents - $I_{\text{уст. 1}} / I_{\text{уст. 2}} = 2$ - we find $I_0$:

$$I_0 = \mathcal{E} / 3r.$$

V. Mozhaev

F736. A beam of electrons falls on a homogeneous rod, both ends of which are grounded, and the same number of electrons per second hits each centimeter of the length of the rod. The resistance of the rod is R. The current in the grounding section is equal to I. Find the potential difference between the middle of the rod A and its end B (see Fig. 1).

F737. A parallel beam of light is scattered as it passes through plate P. For any ray passing through the plate, the maximum angle of deviation from the original direction is α. What is the smallest radius of the bright spot that can be obtained by placing a collecting lens L with focal length F (Fig. 1) behind the plate?

Since the rod is homogeneous, the current flows through it symmetrically relative to point A. Therefore, at point A the current is zero, that is, $I_A = 0$.

Let us mentally divide the section AB of the rod into N identical parts. Let at the end of the first (from point A) section the current be equal to $I_1$. Then at the end of the kth section the current is $I_k = kI_1$; at the end of the Nth section, that is, at point B, the current is $I_N = NI_1$. At the same time, the current $I_N$ is equal to half the current I at the grounding section, that is, $NI_1 = I/2$. Hence $I_1 = I/2N$.

The resistance of each section is $R/2N$, and the voltage drop at the kth section is

$$U_k = I_kR/2N = kI_1R/2N = kIR/4N^2.$$

The potential difference between points A and B is equal to the sum of the voltage drops across all N sections. Hence,

$$U_{AB} = \sum_{k=1}^{N} U_k = \frac{IR}{4N^2} \sum_{k=1}^{N} k = \frac{IR}{8} \frac{N+1}{N} \xrightarrow{N \to \infty} \frac{IR}{8}.$$

N. Dikansky

Let's find the boundary of the illuminated area behind the lens. Its character depends on the size of the lens (aperture radius), on the radius of the light beam and on the distance between the plate and the lens. Let these parameters be equal to the correspondence of r, R and s.

At $r > R + stg\alpha$ all rays scattered by the plate fall on the lens (Fig. 2). Behind the lens, the boundary of the illuminated area is formed by rays $I'$ and $4'$ (the result of the refraction of rays 1 and 4, determined by the boundary of the scattering beam incident on the lens). The break points of the boundary are below the awareness of A, B, C. Point A is in the plane of the lens at a distance of $R + stg\alpha$ from the axis. Point B, the intersection point of rays $I'$ and $3'$, is located in the focal plane, since rays 1 and 3 incident on the lens are parallel. The distance from point B to the axis is $Ftg\alpha$. Point C—the intersection point of rays $3'$ and $4'$—lies in the plane of a clear image of the scattering plate, since the rays emanating from one point of the plate are collected here. Thus, point C is the image of a point located

⟦folio 45⟧

at a distance $R$ from the axis and at a distance $s$ from the plane of the lens. Therefore, the distance from $C$ to the axis is $RF/(s-F)$ (calculate this yourself).

The spot name lies in the plane closest to the fracture axis; therefore its radius is equal to the minimum of the distances $R+s tg \alpha$, $F tg \alpha$ and $RF/(s-F)$. Accordingly, the screen must be located either close to the lens, or in the focal plane, or in the plane of the clear image of the plate. Note that at $s<F$ the rays $3'$ and $4'$ behind the lens do not intersect (the plate image is minimal) and only the kinks $A$ and $B$ remain.

At $r<R-s tg \alpha$, the boundary of the illuminated area behind the lens is formed by “limiting” rays passing through the edges of the lens (Fig. 3). The boundary breaks are located in the lens plane at a distance of $r$ from the axis (point $A_1$) and in the focal plane, as before, at a distance of $F tg \alpha$ (point $B_1$). There are no big breaks. The minimum of the values ​​$r$ and $F tg \alpha$ gives the radius of the smallest spot.

Finally, in the intermediate case $R+s tg \alpha>r>R-s tg \alpha$ (Fig. 4), the boundary breaks lie in the lens plane, in the focal plane and in the clear image plane of the plate at distances $r$, $F tg \alpha$ and $RF/(s-F)$, respectively.

For a sufficiently small $\alpha$, in all these cases the smallest spot will be in the focal plane, and the radius of this spot $F tg \alpha$ does not depend either on the radius of the first beam or on the diameter of the lens. Interestingly, such compression of the beam near the focal plane - called crossover - is used in an electron oscilloscope to form a narrow, concentrated electron beam.

I. Vorobiev

F738. The particles move in a direction at constant speeds. Particle velocities increase uniformly from a value of $v_1$ in the cold of the column to a value of $v_2$ in the tail of the column. At some point, particles occupy a segment of length $l_0$ and at the same time there are $n_0$ particles per unit length. How many particles after time $t$ will be per unit length in the tail of the column?

Let the particles occupy a segment of length $l_0$ at time 0. In time $t$, the particle at the head of the column will move $v_1 t$, and the particle at the tail of the column will move $v_2 t$ (Fig. 1). The back particles move quickly and push up the particles at the beginning of the column. The consideration between the first and last parts will be reduced in time $t$ by $(v_2-v_1) t$ and will become equal

$$l = l_0 - (v_2 - v_1) t.$$

The reduction in the length of the segment occupied by all particles is determined by the difference in particle velocities at the end and at the beginning of the segment. The same is true for the gap between any two particles of the column.

Let at the initial moment of time there be some two particles at a distance $\Delta x_0$. Then the difference in their speeds is

$$\Delta v = \frac{(v_2 - v_1)}{l_0} \Delta x_0$$

(since the particle speeds uniformly increase towards the tail of the column). Consideration between particles for time $t$ will be reduced by $\Delta v t$ and will become equal

⟦folio 46⟧

$$\Delta x = \Delta x_0 - \Delta v \cdot t = \left( 1 - \frac{(v_2 - v_1) t}{l_0} \right) \Delta x_0.$$

As we see, the distances between any two particles decrease over time by the same number of times; therefore, the particles remain evenly distributed along the column. In other words, the number $n$ of a particle arriving per unit length of the column is the same at any location, as it was at the initial moment.

To find $n$, remove the total number of part $n_0 l_0$ by the length of the column at time $t$:

$$n = \frac{n_0 l_0}{l_0 - (v_2 - v_1) t} = \frac{n_0}{1 - \frac{(v_2 - v_1) t}{l_0}}.$$

At figure 2 the dependence $n(t)$ is shown. As time $k$ approaches moment $t_0 = l_0/(v_2 - v_1)$, the concentration $n$ of particles increases indefinitely and at $t > t_0$ changes sign, further decreasing in absolute value. This behavior $n(t)$ is not difficult to understand: by the moment of time $t_0$ all particles will gather at one point - this corresponds to infinite concentration; after this, when the rear particles overtake the front ones, the order of the particles will change - this is indicated by the change in the sign of $n$.

I. Vorobiev

F739. In a cylindrical connection of height $H$ with base area $S$, a mass of water $M$ flows in from a horizontal pipe every second. There is a small hole at the base. On the surface of the water in the vessel lies a thin lekka clove. From a certain moment, the height of the water level in the vessel becomes constant and equal to $h_0$. Determine the speed at which water flows out of the hole.

In the steady state, the dreams acting on the sponge are balanced. A force is exerted on the sponge by the falling water

$$F = \frac{M \cdot \Delta t \cdot \sqrt{2g(H - h_0)}}{\Delta t} = M \sqrt{2g(H - h_0)}.$$

This force does work in time $\Delta t$

$$\Delta A = F \cdot \Delta x = F \frac{\Delta V}{S} = F \frac{M \cdot \Delta t}{\rho S}.$$

According to the law of conservation of energy

$$\Delta A + \Delta \Pi = \Delta K,$$

or

$$\Delta A + M \cdot \Delta t \cdot g \cdot h_0 = M \cdot \Delta t \cdot \frac{v_1^2 - v_2^2}{2},$$

where $v$ is the speed of water falling on the sponge, $v_1$ is the speed of water flowing out of the hole. Since the hole is small, $v^2 \ll v_1^2$. Finally we get

$$\frac{F}{\rho S} + g h_0 = \frac{1}{2} v_1^2,$$

where

$$v_1 = \sqrt{2 g h_0 + \frac{2 M}{\rho S} \sqrt{2 g(H - h_0)}}.$$

I. Omelyan

F740. The vessel contains a mixture of gases - helium and oxygen. At temperature $t = -2^\circ C$ and pressure $p = 0,9$ atm, the density of this mixture is $Q = 0,44 \text{ кel/м}^3$. What does it look like in a vessel if half of the oxygen molecules are removed from it?

Let the $1 \text{ m}^3$ mixture contain $v_1$ moles of helium and $v_2$ moles of oxygen. Then the total number of moles in volume $V = 1 \text{ m}^3$ is equal to

$$v = v_1 + v_2 = \frac{p V}{RT} = \frac{0,9 \cdot 10^5 \cdot 1}{8,3 \cdot 271} \approx 40 \text{ mol}.$$

The mass of the mixture in this volume is equal to

$$m = m_1 + m_2 = \mu_1 v_1 + \mu_2 v_2 = \rho V = 0,44 \text{ кг}.$$

Solving a system of equations

⟦folio 47⟧

$$\begin{align*}
v_1 + v_2 &= 40, \\
4 \cdot 10^{-3} v_1 + 32 \cdot 10^{-3} v_2 &= 0,44,
\end{align*}$$

we find $v_1$ and $v_2$:

$$v_1 = 30 \text{ моль}, \quad v_2 = 10 \text{ моль}.$$

If half of the oxygen molecules are removed from the vessel, the total number of moles becomes $v' = 35 \text{ моль}$. Pressure $p'$ in the vessel under this condition will be found from correspondence $p/p' = v/v'$:

$$p' = p \frac{v'}{v} = 0,9 \cdot 10^5 \cdot \frac{35}{40} \approx 0,79 \cdot 10^5 \text{ Па.}$$

A. Zilberman

F741. We connect two capacitors with a capacity of 1 μF each in series to an alternating current with a direction of 220 V and a frequency of 50 Hz. A resistor with resistance $R = 100 \text{ кОм}$ is connected in parallel to one of the capacitors (see Fig.ok). Find the thermal power.

◆ Capacitance resistance at a given frequency $f = 50$ Hz is equal to

$$Z_C = \frac{1}{2\pi f C} \approx 3 \cdot 10^3 \text{ Ом}.$$

Since the resistance of the resistor is $R = 10^6 \text{ Ом}$, that is

$$R \gg Z_C, \text{ можно считать, что } U_R \approx U/2 = 110 \text{ В (U — напряжение сети)}. \text{Takим образом, тепловая мощность равна}$$
$$P = U_R^2/R \approx 0,12 \text{ Вт.}$$

A. Zilberman

F742. A glass vessel with a primaudal cross-section is installed between two collecting lenses with focal lengths $F$ perpendicular to the optical axis of the lenses (Fig. 1). The precision light source $S$ is located in the focal plane of the lens $J_1$. When the vessel is empty, the source image is observed on the screen E located in the focal plane of the lens $J_2$. The vessel is filled with a transparent liquid, shown

A spherical wave propagates from an exact light source $S$, that is, the wave front (constant phase surface) has the form of a sphere with a center at point $S$. After passing through lens $J_1$, the front becomes flat (since point $S$ is at the focus of lens $J_1$). Since the front is parallel to the plane in which the lens lies and to the side walls of the vessel. If the vessel were empty, then after passing through the vessel the wave front would still be parallel to the walls of the vessel. A beam of rays parallel to the main axis of the lens would be applied to the lens $J_2$, and the image of the source $S$ would be at the right focus of the lens.

When a vessel is filled with a changing (height) refractive index, the orientation of the wave front in space after passing through the vessel changes. To find the front in this case we use

Fig. 1.

Fig. 2.

⟦folio 48⟧

the refractive index of which changes with height according to the law $n(y) = n_0 + \alpha y$. The thickness of the liquid layer is $L$. How much will the source image on the screen shift vertically? The change in the refractive index with the depth of the sauce is considered small within the diameter of the light beam.

principle of Heugens - Fresnel. According to this principle, the front after light passes through the sauce will be an envelope of secondary waves, the sources of which lie on the left side wall of the sauce.

Let us find the position of the front at the moment in time when secondary waves from sources lying on the left wall of the sauce at a height $h$ from its bottom (Fig. 2) reach the right wall of the sauce. The time $t$, during which these waves will travel the distance $L$, is equal to

$$t = \frac{L}{c/n(h)} = L \frac{n_0 + \alpha h}{c},$$

where $c$ is the speed of light in vacuum, $n(h) = n_0 + \alpha h$ is the refractive index in liquid at a height of $y = h$. The same distance $L$ waves propagating from sources lying on the left wall of the sauce at a height $y < h$ will travel in time

$$t_1 = L \frac{n_0 + \alpha y}{c} < t$$

(we assume $\alpha > 0$). Consequently, in time $t$ these waves will propagate to the right of the sauce to a distance

$$l(y) = (t - t_1)c = L\alpha(h - y).$$

The quantity $l(y)$ is a linear function of $y$. Consequently, after the light passes through the sauce, the envelope of the secondary waves, that is, the wave front, will be a plane inclined to the side wall of the sauce at an angle such that (see Fig. 2)

$$tg\varphi = l(y)/(h - y) = L\alpha.$$

Thus, a beam of parallel rays inclined at an angle $\varphi$ to the optical axis of the lens will fall on the lens $\varPi_2$. The image of the source $S$ will be obtained in the focal plane of the lens $\varPi_2$ at a distance

$$\delta = F \cdot tg\varphi = FL\alpha$$

from the axis of the lens. With $\alpha < 0$ the image will be shifted down the axis by the same amount.

V. Mozhaev

Matematika
magic cube

(For the beginning, see p. 22)

12. "Repainted Cube" The elementary operations are the same, but 1) an arrow is drawn on each central cube, registering its turns; 2) the cube is painted in three colors so that the color of opposite faces in the zero state is the same.

13. "Magic paralleliped $n \times m \times k$". The description of this game should be obvious from the title. Of course, not every face can be rotated only by $180^\circ$, and not only the faces, but also the internal elephants can be expressed. Further 9 options corresponding to $n, m, k \leq 3$ are by no means trivial. Variation $3 \times 3 \times 2$ is performed in Hungary under the name "Domino". Recently, the $4 \times 4 \times 4$ cube began to be produced in Hungary under the wonderful name “Rubik’s Places”!

14. "Magic cube $3 \times 3 \times 3$". (For those who are a little familiar with four-dimensional geometry.)

15. "The Magic Polyhedron". Balls of different colors are located at the vertices and in the middle of the edges of an arbitrary polyhedron (the number of colors is equal to the total number of vertices and edges of the polyhedron). In one move, you can cyclically rearrange all the balls on one side. The state here is completely described by the permutations $s$ and $t$.

16. "Magic terraedron" The zero state is a regular terrahedron, each face of which is painted in one of four colors. When “rotating the faces,” 4 corner and 6 edge “elements” move, the shape of which will not be specified. It is important that here, in addition to permutations, their orientation must also be taken into account. Other options for obtaining with octahedron, dodecadron and icosadron.
