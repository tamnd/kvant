---
id: 1975-6-resheniya-zadach-m292-m295-f300-f302-ddae61ac
issue: kvant_1975_6
year: 1975
number: "6"
title: Solutions to problems M292—M295; F300—F302
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 26
page_last: 32
page_labels: 24-30
tag: JEZ2
lang: en
source: kvant_digital
extraction: vision
content_sha256: 542f2214a09e977fc6b716f97b745d5f111c6373f50d3a0b58d4130f3fb8e5d9
prompt_sha256: draft-1
translated_from: content/ru/1975/06/articles/10_resheniya-zadach-m292-m295-f300-f302-ddae61ac.md
source_content_sha256: 8fc3d2cc9ac2e44bb724856e129fd876e570d278ef1ac18677130fc5b7ce4705
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 24⟧

Problem solutions

M292. Numbers from 1 to 50 are written on the board. We are allowed to erase any two numbers and write them together as one number - the modulus of their difference. After repeating this procedure several times, one number remains on the board. What number could this be?

Answer. Any odd number less than 50, that is, one of the 25 numbers 1, 3, 5,..., 49.

Let us first show that any of these numbers can obtain. Let us want to get the number 2m+1 (m=0,1,...,24). The division of numbers from 1 to 50 into pairs is as follows: (1, 2m+2), (2, 3), (4, 5), ..., (2m, 2m+1), (2m+3,2m+4), ..., (49, 50). Let us write down together a model of the difference of the numbers included in it: 2m+1, 1, ..., 1 (24 units). It remains to get rid of the units. To do this, you can split them into pairs to get 12 zeros, and then get rid of the zeros (instead of the pair (a, 0) we can write one number |a−0|=a).

Now we will prove that no other number except 1, 3, 5,...,49 can be obtained. First of all, it is clear that any number written on the board will be between 0 and 50 (if 0≤a≤50, 0≤b≤50, then 0≤a−b≤50). Let us prove that the resulting number will necessarily be odd. Let's keep track of the sum of all the numbers written on the board. At first it is equal

$$1+2+3+\dots+50=25\cdot51,$$

that is, odd. But replacing the pair (a, b) with a single number |a−b| does not change the parity of the entire sum, since the numbers a+b and |a−b| always of the same parity (either both are even, or both are odd). Therefore, the sum of the written numbers at each step, including the very last one, when one number remains, will be odd.

It can be shown that in a more general case, when the numbers from 1 to n are written on the board at the beginning, at the end any integer k can be obtained such that 0≤k≤n and k has the same parity as n(n+1)/2 (that is, k is even if n leaves a remainder of 3 or 0 when divided by 4, and odd if the remainder is 1 or 2).

◆

Let's try to prove what this limit is (assuming that there is another limit that has already been proven). From the problem conditions it follows that $C_{n+1}C_{n+2}$ is the bisexation of the angle of the triangle $C_nC_{n+1}O$ (Fig. 1), therefore

$$2\gamma_{n+1}+\gamma_n+\alpha=\pi.$$

If the limit lim $\gamma_n$ exists and is equal to $\beta$, then, passing to the limit in equality (1), we obtain

$$2\beta+\beta+\alpha=\pi,$$

where

$$\beta=(\pi-\alpha)/3.$$

Now we will prove that $\gamma_n$ the real tends to the limit $\beta=(\pi-\alpha)/3$. Let's see how the difference between $\gamma_n$ and $\beta$ changes as n increases. Let's change (1) like this:

$$2\left(\gamma_{n+1}-\frac{\pi-\alpha}{3}\right)=\frac{\pi-\alpha}{3}-\gamma_n.$$

It follows that |$\gamma_{n+1}-\beta$|=|$\gamma_n-\beta$|/2, that is, that the difference between $\gamma_n$ and $\beta$ when moving from n to n+1 is halved. Therefore, |$\gamma_n-\beta$|=|$\gamma_1-\beta$|/2$^{n-1}$ tends to zero, that is, the limit $\gamma_n$ is real and equal to $\beta=(\pi-\alpha)/3$.

⟦folio 25⟧

M294. Prove that if $a, b, c, d, x, y, u, v$ are real numbers $u abcd > 0$, then $(ax + bu)(av + by)(cx + dv) \times (cu + dy) \geq (acuvx + bcuxy + advxy + bduvy) \times (acx + bcu + adv + bdy)$.

M295. Sections of the convex manifold of a triangle by parallel planes $p_0, p_1, p_2$ ($p_1$ is located between $p_0$ and $p_2$ at the same distance $h$ from my $u$ other) we have areas $S_0, S_1$ and $S_2$ respectively. There is no vertex of the manifold between $p_0$ and $p_2$.
a) Prove that
$$2\sqrt{S_1} \geq \sqrt{S_0} + \sqrt{S_2}.$$
b) In what case does inequality turn into equality?
e) Find the area $S_t$ of a section of the manifold by a plane parallel to $p_0$ and located at a distance $th$ from $p_0$ and $(2-t)$ from $p_2$ ($0 < t < 2$).
e) Find the volume of the number of the manifold contained between the planes $p_0$ and $p_2$.

Fig. 2.
Fig. 3.
Fig. 4.

If you open all the brackets, then in each part of the inequality you get 16 terms, of which 12 are identical and cancel. The remaining terms after bringing similar terms form the following obvious inequality, equivalent to the original one:
$$abcd (xy - uv)^2 \geq 0.$$

Let us denote the part of the polyhedron contained between the planes $p_0$ and $p_2$ by $M$; through $V$ is the volume of the convex polyhedron $M$. By condition, all vertices $M$ lie in the planes $p_0$ and $p_2$. In the figures, we will depict the vertices and edges of the polyhedron $M$, lying in the plane $p_2$, as the head color, in $p_0$ - in green, and the section of the plane $p_1$ - in red.

Let's look at a few examples first.
1°. $M$ — recognized with bases in the planes $p_0$ and $p_2$ (Fig. 2). Then $S_t = C$ (constant value), in part, $S_0 = S_1 = S_2 = C$, so the equality holds
$$2\sqrt{S_1} = \sqrt{S_0} + \sqrt{S_2}$$

and $V = 2S_0h$ (the height of the feature is 2h).
2°. $M$ is a triangular paramid whose vertex lies in the $p_0$ plane and its base in the $p_2$ plane (Fig. 3). Then the linear dimensions of a section by a plane parallel to $p_0$ are proportional to the distance of this plane from $p_0$, so that $S_t$ is proportional to $t^2$: $S_t = At^2$, so that
$$S_0 = 0, S_1 = A, S_2 = 4A,$$
and equality (*) is satisfied again; at the same time $V = 2S_2h/3$.
3°. $M$ is a truncated triangular paramid with bases in the plane $p_0$ and $p_2$ (Fig. 4). Then $S_t = A(t - \tau)^2$ (this is determined by the distance $|\tau|$ from the plane $p_0$ the extensions of the lateral faces of the paramid intersect; $\tau > 2$ or $\tau < 0$, depending on whether the point of intersection of the extensions of the lateral faces lies on the same side of $p_0$ as $p_2$, or on the other), so
$$S_0 = A\tau^2, S_1 = A(1 - \tau)^2, S_2 = A(2 - \tau)^2.$$

Check that equality (*) holds again, and $A$ and $\tau$ can be expressed in terms of $S_0$ and $S_2$ like this:
$$\frac{\tau - 2}{\tau} = \sqrt{\frac{S_2}{S_0}} \Rightarrow \tau = \frac{2\sqrt{S_0}}{\sqrt{S_0} - \sqrt{S_2}};$$
$$A = \left(\frac{\sqrt{S_0} - \sqrt{S_2}}{2}\right)^2.$$

The volume of $V$ is equal to $2(S_0 + \sqrt{S_0}S_2 + S_2)h/3$ (it can be found as the difference between the volumes of two non-truncated paramids: $V = \frac{S_0h\tau}{3} - \frac{S_2h(\tau - 2)}{3}$).

Of course, example 2° can be considered partly case 3°.
4°. $M$ is a triangular feature lying on its side (Fig. 5, a). There's $S_t = B(2 - t)$ here, so
$$S_0 = 2B, S_1 = B, S_2 = 0,$$
and the inequality is satisfied
$$2\sqrt{S_1} > \sqrt{S_2} + \sqrt{S_0},$$
a $V = S_0h$ (Fig. 5, b).

⟦folio 26⟧

5°. M is a triangular paramid with two vertices belonging to $p_0$ and two to $p_2$ (Fig. 6, a). Then $S_t$ is the area of ​​a parallelogram whose side length linearly depends on $t$, and one turns to 0 at $t=0$, and the other at $t=2$, therefore $S_t=At$ (t-2), so $S_0=S_2=0$, $S_1=-A$ and inequality (**) holds. The volume of $V$ here is equal to $4S_1h/3$ (Fig. 6, b).

6°. M is a polyhedron whose all sections by planes parallel to $p_0$ and $p_2$ are parallelograms (perhaps degenerate at $t=0$ or $t=2$ - see Fig. 7). This example includes 4°, 5°, paraleloppeds, a truncated paramid with a parallelogram at the base, and other polyhedra. Here we only note that the lengths of one and the other side of the parallelogram linearly depend on $t$ (or do not depend on $t$ at all), so that $S_t$ is expressed by a function of the form $S_t=C$, $S_t=B(t-\tau_0)$ or $S_t=A(t-\tau_1)(t-\tau_2)(\tau_j$-numbers not belonging to the interval ]0;2[).

Now we present a scheme for solving the problem in the general case, leaving the details of the proofs to the reader.

Any polyhedron $M$ can be reduced to those already considered using one or another of the following methods:

(P). $M$ can be cut into triangular paramids (types 2° and 5°) by certain planes passing through its vertices (Fig. 8, a-f).

(D). If $M$ is different from polyhedra of the type 6°, then, by continuing some of its faces, we can use several triangular truncated paramids and recognitions (types 3° and 2° and 1°) to polygons $M$ to a triangular truncated paramid or recognition (Fig. 8, d).

Theorem 1. The cross-sectional area $S_t$, as a function of $t$, is expressed for any polyhedron $M$ by a square trinomial:

$$S_t=At^2+Bt+C,$$

and the discriminant is a non-negative trinomial:

$$B^2-4AC\geq 0$$

and is equal to zero molko for recognized and paramids (including truncated ones) with a base in the planes $p_0$ and $p_2$.

Lemma a. Let $F(t)=At^2+Bt+C\geq 0$ be on the interval $a\leq t\leq b$. Then the graph of the function $y=\sqrt{F(t)}$ on this segment is convex upward if $B^2-4AC>0$, convex downward if $B^2-4AC<0$, and is a straight line segment (or consists of segments of two straight lines) if $B^2-4AC=0$. (We call the graph of a function $y=f(t)$ on the segment $[a,b]$ convex upward if for any points $c$, $c-d$ and $c+d$ of this segment the inequality is convex—see Fig. 9.)

It is clear that Statement a) of Problem M295 and answers to questions 6) and c) follow from Theorem 1 and the lemma.

6) equality (*) holds true only for paramids, recognized and truncated paramids with a base in the planes $p_0$ and $p_2$.

c) $S_t=At^2+Bt+C$, where $A,B$ and $C$ are determined from the system of equations $S_0=C$, $S_1=A+B+C$, $S_2=4A+2B+C$; from here

$$S_t=\frac{S_2-2S_1+S_0}{2}t^2-\frac{3S_0-4S_1+S_2}{2}t+S_0.$$

To find the volume of $V$, those familiar with early integral calculus can simply integrate $S_t$ from $t=0$ to $t=2$ and multiply the result by $h$. However, from the very beginning it is clear that if the required formula exists (that is, the scope of the action expression through $S_0$, $S_1$, $S_2$ and $h$), then it should have the form $V=(\alpha S_0+\beta S_1+\alpha S_2)h$, and the numbers $\alpha$ and $\beta$

⟦folio 27⟧

easy to find from the five examples discussed. Thus, we arrive at the following theorem, which gives an answer to question d).

Theorem 2. *The volume V of the polyhedron M is equal to* $(S_0+4S_1+S_2)h/3$.

In conclusion, we will give a few pointers to the evidence of all the statements made.

Statements (P) and (D) can be proved by induction on the number of vertices or on the number of faces of the polyhedron M.

In the proof of Theorem 1, it is convenient to use (E) - if $M\bigcup П_1\bigcup...\bigcup П_n=П_0$ and $S_t^i (i=0, 1,..., n)$ are the cross-sectional areas of the polyhedra $П_i$ (truncated pyramids and prisms), then

$$S_t=S_t^{(0)}-S_t^{(1)}-...-S_t^{(n)}=At^2+Bt+C,$$

where each $S_t^{(i)}$ is either $C_i$ or $A_i(t-\tau_i)^2$; since $S_t\geqslant0$ for $0\leqslant t\leqslant2$ and (if $S_t$ is not constant) $At^2+Bt+C$ takes non-positive values (if $S_t^{(0)}=A^{(0)}(t-\tau_0)^2$, then for $t=\tau_0$, if $S_t^{(0)}=C_0$, then for sufficiently large $t$), $S_t=At^2+Bt+C$ has real roots, that is $B^2-4AC\geqslant0$.

To prove the lemma, it is useful to use the fact that the property of “having real roots” and the direction of convexity of the graph are preserved if we multiply the trinomial by a positive number or go to a new trinomial using a linear change of variable $t=pt^*+q$ ($p$ and $q$ are any numbers, $p\neq0$). For those who became acquainted with second-order curves from the articles of I. N. Bronstein («Kvant», Nos. 1, 3, 4), we note that in the case of $B^2-4AC>0$ the graph of $y=\sqrt{F(t)}$ will be a piece of an ellipse or hyperbola, the foci of which lie on the axis $Ot$, and in the case of $B^2-4AC<0$ - a piece of a hyperbola whose the segment connecting the foci is perpendicular to $Ot$.

To prove Theorem 2, it is better to use (P) - then the formula for $V$ is enough to check for the tetrahedra $2^\circ$ and $5^\circ$.

N. B. Vasiliev

◆

⟦figure⟧
Fig. 8, c.

⟦figure⟧
Fig. 8, g.

⟦figure⟧
Fig. 8, bldg.

⟦figure⟧
Fig. 9.

F300*). *Find to what height the liquid rises in expanding and contracting conical capillaries. Wetting is complete. The angle at the apex of the cone that forms the capillary is $2\alpha$. This angle is considered small. Liquid surface tension coefficient $\sigma$.*

---
*) The solution problem F299 will be published in the next issue.

⟦column⟧

Since wetting is complete, the free surface of the liquid in the capillary is part of a spherical surface inscribed in a cone. The radius of this sphere $R$ is equal to $r/\cos\alpha$, where $r$ is the radius of the capillary at the height to which the liquid rises (Fig. 10, 11). Under a concave spherical surface of radius $R$, the pressure in the liquid is less than atmospheric pressure by $p_д=\dfrac{2\sigma}{R}=\dfrac{2\sigma\cos\alpha}{r}$ and equal to $p=p_0-p_д=p_0-\dfrac{2\sigma\cos\alpha}{r}$. At the surface level of the liquid in a wide vessel, the pressure in the capillary is $p+\rho gh$ and, obviously, equal to the atmospheric pressure $p_0$. Hence,

$$p_0-\dfrac{2\sigma\cos\alpha}{r}+\rho gh=p_0,\quad\text{или}\quad \rho gh=\dfrac{2\sigma\cos\alpha}{r}.\qquad(1)$$

Let us denote by $r_0$ the radius of the capillary at the level of the liquid surface in a wide vessel. Then $r=r_0+h\,\mathrm{tg}\,\alpha$ in the case of an expanding capillary and $r=r_0-h\,\mathrm{tg}\,\alpha$

⟦folio 28⟧

with drying capillary. Or, for both cases, $r = r_0 + kh \text{tg} \alpha$, where $k = 1$ is for the expanding capillary and $k = -1$ for the drying capillary. Taking this into account, we rewrite (1) in the form

$$\rho gh = \frac{2\sigma \cos \alpha}{r_0 + kh \text{tg} \alpha}.$$

(2)

For $\alpha = 0$ this equation gives the known result $h = \frac{2\sigma}{\rho g r_0}$. If $\alpha$ is not equal to zero, then from (2) we obtain the quadratic equation

$$k \rho g \text{tg} \alpha h^2 + \rho g r_0 h - 2\sigma \cos \alpha = 0.$$

(3)

Solving this equation, we find

$$h_{1,2} = \frac{-\rho g r_0 \pm \sqrt{(\rho g r_0)^2 + 8k \rho g \sigma \sin \alpha}}{2k \rho g \text{tg} \alpha}$$

(4)

In the case of an expanding capillary (at $k = 1$) there is only one positive value for the root of equation (3):

$$h = \frac{-r_0 + 1 \sqrt{r_0^2 + 8\sigma \sin \alpha/\rho g}}{2 \text{tg} \alpha}$$

The liquid in the expanding capillary will rise to this height.

In the case of a drying capillary ($k = -1$), if $\rho g r_0^2 > 8\sigma \sin \alpha$, the root may be positive and therefore it is necessary to examine the answer in more detail. To do this, let's return to equation (2). The expression on the left side of the equation is the hydrostatic pressure of a column of liquid of height $h$; let's denote it $p_r$. The expression on the right side is the additional, “supporting” pressure $p_d$, which arose due to the action of surface tension forces. Let's draw in one drawing graphs of the dependence of $p_r$ and $p_d$ on $h$ (Fig. 12). The intersection points of the graphs correspond to the found values ​​$h_1$ and $h_2$, that is, the equilibrium position of the liquid in the capillary. Let's consider both of these provisions. Let $h = h_1$ and by some random principles the liquid level increase slightly. In this case, $p_d$ will increase less than $p_r$, therefore, the surface of the liquid will drop, returning to the level $c = h_1$. As $h$ decreases, $p_d$ will decrease less than $p_r$, therefore, the surface of the liquid will increase. This means that the equilibrium position of the fluid is unstable. Similarly, by considering the equilibrium position $h = h_2$, it can be shown that it is unstable. If the liquid level changes, it will continue to decrease to $h_1$, and if $h$ increases, it will increase to the upper boundary of the capillary.

At $\rho g r_0^2 = 8\sigma \sin \alpha$ there is only one root value, the graphs $p_r$ and $p_d$ (dashed line at figure) touch at point $h = \frac{r_0}{2 \text{tg} \alpha}$.

In this case, the equilibrium position of the liquid is unstable, and if the liquid level increases slightly, it will continue to decrease to the capillary boundary. At $\rho g r_0^2 < 8\sigma \sin \alpha$ there is no equilibrium position at all, and the liquid must reach the top of the capillary.

⟦folio 29⟧

F301. A Kruezda lens of diameter D consists of two halves connected in diameter. The focal length of one of them is F, the other is 2F. At a distance a from the line there is a light source, at a distance 2a on the other side of the lens there is a screen. Draw a graph of the dependence of the illumination of the source image on the screen on the distance of the screen power to the optical axis of the lens. The changer is located on the optical axis of the lens, the screen is perpendicular to this axis.

The two halves of the lens form an optical system of two lenses with focal lengths F (lin for L1) and 2F (lin for L2). The optical axes of these lenses coincide. By definition, illumination depends on the luminous flux incident on the screen and on the area of ​​the spot on the screen. In our case, when determining the position of the source, each lens creates its own light spot on the screen, since the lens distances are different. The magnitudes of the light fluxes passing through the lenses are the same, since the areas of the lens are the same, and therefore the solid angles within which the light fluxes falling on the screen are contained. Consequently, the illumination of the screen is determined by the size of the image area. Obviously, when the position of the source changes, the position of its image changes, therefore, the area of ​​the spot on the screen and the illumination of the image on the screen change.

Fig. 13.

Using the lens formula, we find that the source image is located from the lenses at distances f1 = Fa/a - F and f2 = 2Fa/a - 2F. Let's distance several positions of the source.

For a < F f1 < 0 and f2 < 0, that is, both source images are minimal. The rays of rays shown on figure 13 fall on the screen. These rays on the screen do not overlap which lens illuminates its part of the screen and creates its own illumination on it. (Recall that in geometric optics narrow paraxial beams are considered, therefore the light spot on the screen is small, and we can assume that the illumination anywhere in the spot is the same.) On the right, figure shows a graph of the dependence of illumination on the distance x to the optical axis.

For F < a < 2F f1 > 0 and f2 < 0. The image of the source in the first lens is real, and in the second it is minimal. However, the illumination distribution depends on whether f1 is larger or smaller than the distance to the screen 2a. This corresponds to the following F < a < 3/2 F and 3/2 F < a < 2F.

⟦folio 30⟧

Fig. 15.

Ray beams and illumination graphs for these cases are shown at Fig. 14 and 15.

And finally, for $a > 2F$ both source images are valid, and $f_1 < 2a$ and $f_2$ can be both larger and smaller than $2a$. If $2F < a < 3F$, then $f_2 > 2a$; the course of rays and illumination graphs are similar to the case shown in Fig. 15. If $a > 3F$, then $f_2 < 2a$, the constructions and graphs are similar to the case corresponding to Fig. 14. Make sure of this yourself.

F302. Behind the fox, running straight and uniformly with speed $v_1$, a dog follows, the speed with $v_2$ is constant in absolute value and is directed all the time towards the fox. At the moment when the speeds $v_1$ and $v_2$ turned out to be mutually overriding, consider the difference between the fox and the dog was equal to $l$. What was the dog's acceleration at this moment?

Since the absolute value of the dog’s speed is constant, and only the direction of the speed changes, the dog’s acceleration is directed perpendicular to the speed vector. To find the dog’s acceleration, we take advantage of the fact that any trajectory of a material point in a very short period of time can be considered a different circle. Then the acceleration of the dog is represented by the centripetal acceleration equal to

$$a = \frac{v_2^2}{R},$$

where $R$ is the radius of the circle, which can be replaced by the actual trajectory of the dog.

Consider the movement of a dog in a short time $\Delta t$. During this time, the dog’s velocity vector will rotate through an angle $\alpha$ such that $\alpha = \frac{v_2 \Delta t}{R}$ (Fig. 16). On the other hand, the fox will move a distance $v_1 \Delta t = \alpha l$ in time $\Delta t$, since the dog’s velocity vector is always directed towards the fox. Hence,

$$\frac{v_2 \Delta t}{R} = \frac{v_1 \Delta t}{l}.$$

Then

$$R = \frac{v_2}{v_1} l \text{ и } a = \frac{v_1 v_2}{l}.$$

I. Sh. Slobodetsky
