---
id: 1989-11-resheniya-zadach-m1166-m1169-f1178-f1182-f9e2acc8
issue: kvant_1989_11
year: 1989
number: "11"
title: Solutions to problems M1166—M1169; F1178—F1182
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 27
page_last: 31
page_labels: 25-29
tag: 7B0G
lang: en
source: kvant_digital
extraction: vision
content_sha256: 74d86f106712ca91058f018e61f14733659142de04dfa78c27d57c26bcf2e5a5
prompt_sha256: draft-1
translated_from: content/ru/1989/11/articles/06_resheniya-zadach-m1166-m1169-f1178-f1182-f9e2acc8.md
source_content_sha256: 912e3ef86823eae774e5ec35066a26a0794073580d0ce1bfce1bb6ba34099cea
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 25⟧

Problem solutions
M1166 — M1169, F1178 — F1182

Replacing $p, q, r$ with their opposites if necessary, we can reduce the matter to the case where two of the numbers $p, q, r$, for example $p$ and $q$, are non-positive, and the third (number $r$) is non-positive. By the triangle inequality $c^2 \geq (a-b)^2$, therefore,
$$a^2 pq + b^2 qr + c^2 rp \leq a^2 pq + b^2 qr + (a-b)^2 rp = a^2 p(q+r) + b^2 r(q+p) - 2abrp = -(ap+br)^2 \leq 0.$$
Ya. Sh. Mustafaev

M1167. How many permutations of numbers $1, 2, ..., n$ are there in which, for any number $i$ that is not in first place, at least one of the numbers $i-1$ and $i+1$ is to the left of $i$?

Answer: $2^{n-1}$. Let the number $k$ be in first place. Note that if $k > 1$, then the numbers $k-1, k-2, ..., 1$ are in our permutation in descending order (if we move from left to right). Indeed, according to the condition, to the left of the number 1 there should be 2, to the left of 2-1 or 3, i.e. 3, to the left of 3-2 or 4, i.e. 4, etc. Similarly, with $k < n$ of the number $k+1, k+2, ..., n$ is in ascending order, since to the left of $n$ there should be $n-1$, to the left of the number $n-1$ is the number $n-2$, etc. Consequently, any of the rearranged permutations is uniquely determined by the set of places occupied by the numbers $1, 2, ..., k-1$ (such places may not exist at all if $k=1$, i.e. for the permutation $1, 2, ..., n$). The number of these sets is equal to the number of subsets of the set of $n-1$ elements - all places except the first one, i.e. $2^{n-1}$.

A. V. Anzhans

M1168*. The country has 1989 and 4000 (each road connects two cities). Prove that it is possible to choose a circular route passing through no more than 20 cities.

Let's call a city “backwater” if there are no more than 2 roads leading from it. Let's erase the ring provincial city, if there is one, from the map of the country, along with the roads leading from it. Let's create a new map in the same way and continue erasing provincial towns until they disappear. The number of roads that we can erase in this case does not exceed 2·1989, which is less than 4000; so at least one city will remain.

Let's choose the left one from the remaining cities. At least 3 roads exit from it, as from the other remaining cities. Let's go along one of them and every time we come to a new city, we will be amazed further along one of the roads, different from the road along which we came. If any 2 routes consisting of no more than 10 roads end in the same city, then we get the desired ring route of no more than 20 roads (see figure). But it cannot be otherwise, because the number of all such routes is not less than $3+3\cdot 2+3\cdot 2^2+...$

⟦folio 26⟧

...+3 · 2^9=3069, and the number of cities, i.e., possible ends of these routes, is no more than 1989.

This solution can be generalized to the case of $n$ cities and $m$ roads. As a result of the “subdivision” of the map of the city’s status, from which there are at least $s$ roads, where $s$ is the smallest number such that $s \geq m/n$. And the difference with non-intersecting routes allows us to prove the existence of a cycle (circular route) of $l$ roads, where

$$l \leq 2[\log_{s-1} \frac{n(s-2)+2}{s} +1]$$

(square brackets indicate the integer part of the number). In particular, with $n=1989$ and $m=4000$ we get $s=3$ and $l \leq 20$.

Another interesting question is: for what number of roads $m$ between $n$ cities can we find a road system that does not contain cycles of length $d$? Using a rather complex estimate of the average number of roads in such a system, it can be shown that this is possible with

$$m < p \left( \frac{n(n-1)}{2} - \frac{n^2}{2d} \right),$$ where $p=n^{-\frac{d-2}{d-1}}$.

A. A. Razborov

**M1169. Let $M$ be a point lying inside the line ABCD, $S$ its area. Prove the inequality $S \leq AM \cdot CM + BM \cdot DM$.**

It is clear that the area of ​​the rectangle is twice the sum of the areas of triangles AMD and BMC. (To prove it, it is enough to check through $M$ the line parallel to $AD$, and then that the area of ​​each of the two formed straight lines/Lliners.) Apply to the side $AD$ the triangle AND equal to CMB so that $AN=CM$, $DN=BM$ (see Fig.ok). Then

$$S = 2(S_{AMD} + S_{BMC}) = 2S_{AMDN} = 2S_{AMN} + 2S_{DMN} \leq AM \cdot AN + DN \cdot DM = AM \cdot CM + BM \cdot DM,$$

Q.E.D.

I. Ya. Goldsheid

**F1178. A sheet of plywood falls in space. It turned out that at some point in time the velocities of two points of the sheet $a$ and $b$ are the same - $\vec{v}_a = \vec{v}_b = \vec{v}$ - and lie in the plane of the sheet. It also turned out that sco-**

Let us imagine the complex motion of all points of a plywood sheet at a specified moment in time as the sum of two simple motions - translational along with points $a$ and $b$ (and therefore together with straight line $ab$) and rotational relative to the axis $ab$.

Consider the point $c$. Its velocity vector $\vec{v}_c$ consists of vector $\vec{v}$, corresponding to translational motion, and vector $\vec{v}_{bp}$, corresponding to rotational motion

⟦folio 27⟧

the growth of a point on the sheet c, located from points a and b at a distance equal to the distance between points a and b, is twice the speed v. Where on the sheet at this moment are the points whose speeds are equal to 3v?

Fig. 1.

Fig. 2.

Movement, and the vectors $\vec{v}$ and $\vec{v}_{\text{bp}}$ are mutually perpendicular (Fig. 1):

$$\vec{v}_c = \vec{v} + \vec{v}_{\text{bp}},$$
or $v_c^2 = v^2 + v_{\text{bp}}^2.$

Since $v_c = 2v$, we get

$$v_{\text{bp}} = \sqrt{3}v.$$

Let us now find the distance from point c to straight line ab. Points a, b and c are the vertices of an equilateral triangle (Fig. 2). Let's denote its side, for example ab, by l. Then the distance we are interested in

$$d = l \frac{\sqrt{3}}{2}.$$

It is obvious that the desired points of the plywood sheet, the speed of which is 3 times greater than v in absolute value, lie on two straight lines parallel to the ab axis and located at a certain distance L from it. To find this distance, we proceed as follows. By analogy with point c, we express the speed of the required points as the sum of the velocities $\vec{v}$ and $\vec{v}'_{\text{bp}}$ perpendicular to each other:

$$(3v)^2 = v^2 + (v'_{\text{bp}})^2,$$

where do we get it from

$$v'_{\text{bp}} = 2\sqrt{2}v.$$

Now let’s compare the speeds $v_{\text{bp}}$ and $v'_{\text{bp}}$. On the one side,

$$\frac{v_{\text{bp}}}{v'_{\text{bp}}} = \frac{\sqrt{3}v}{2\sqrt{2}v} = \frac{\sqrt{3}}{2\sqrt{2}},$$

on the other hand -

$$\frac{v_{\text{bp}}}{v'_{\text{bp}}} = \frac{d}{L} = \frac{l\sqrt{3}/2}{L}.$$

Thus,

$$\frac{l\sqrt{3}/2}{L} = \frac{\sqrt{3}}{2\sqrt{2}},$$
and $L = l\sqrt{2}$.

K. S. Sergeev

F1179. If lightning strikes the water during a thunderstorm, then after the thunderstorm, dead fish are sometimes seen floating up on the lake. How to oblige? After all, the probability of lightning hitting an individual low-water fish is low.

The fish are killed, of course, not by a direct lightning strike, but by an electric current that passes through the water. As you move away from the location of the lightning strike, the current density decreases. The potential difference that appears on the body of the fish is proportional to the magnitude of the current and a certain current density through the water. The fish that are located in the area where the current density exceeds a critical value dies. The characteristic size of this area ranges from several meters to several meters,

⟦folio 28⟧

And there may well be several fish in this dangerous zone.

In some cases, a similar situation can arise when high voltage turns and falls to the ground. In this case, the density of the current flowing through the ground increases as it approaches the place where the wire falls. The degree of danger to a person is characterized here by the so-called “step voltage” - the voltage that arises between a person’s feet when in contact with the ground. It is clear that small steps lead to lower step voltage - that is why it is necessary to leave the dangerous zone where the sealing pipe is in small steps.

A. I. Buzdin

F1180. The light bulb connected to the battery burns for three hours, after which the battery is completely discharged. We made a copy of this battery with twice the linear dimensions from the same materials. How long will the same light bulb stay on when connected to such a copy? The internal resistance of the battery is much less than the resistance of the light bulb.

Since the electromotive force of a chemical current source is determined only by its chemical composition, the emf of the copy will be equal to the emf of the battery. Let this emf be equal to $\mathcal{E}$, the resistance of the light bulb to be $R$ and the internal resistance of the source to be $r$. Then the total power released in the battery circuit is $P_1 = \mathcal{E}^2 / (R + r_1)$, and in the copy circuit - $P_2 = \mathcal{E}^2 / (R + r_2)$. Since $r_1 \ll R$ and therefore $r_2 \ll R$,

$$P_1 \approx P_2 \approx \frac{\mathcal{E}^2}{R}.$$

A chemical current source does work by consuming the energy of chemical substances stored in it. Compared to a battery, the copy contains $2^3 = 8$ times more reagents, so with the same power it can do the same amount of work. This means that the light bulb connected to the copy will remain on for 24 hours.

K. S. Bedov

F1181. A hard, thin conductive material prickles on a non-conducting horizontal surface and is located in a uniform magnetic field, the induction lines of which are horizontal. Ring mass $m$, radius $R$, index values ​​$B$. How much current must be passed through the thorn so that it begins to lift?

Let's look at the ring when it is still in a horizontal position (see figure; it shows a top view). Let us highlight on it the size of points $C$ and $D$, two small sections of length $\Delta l$ each, located symmetrically relative to the diameter of the ring $AB$. The first section is subject to a vertical downward force

$$\Delta F_1 = BI \Delta l \sin \alpha = BI \Delta x,$$

where $\Delta x$ is the projection of the segment $\Delta l$ onto the direction of the diameter $AB$. The second section is subject to a vertical upward force

$$\Delta F_2 = BI \Delta l \sin \alpha = BI \Delta x.$$

⟦folio 29⟧

These forces, identical in magnitude and directed in opposite directions, represent a pair of forces that creates a rotational moment relative to the $AB$ axis

$$\Delta M = \Delta F_1 l_{CD} = BI \Delta x l_{CD} = BI \Delta S,$$

where $\Delta S$ is the area of ​​the contour part shaded on figure.

Divide the entire ring into similar pairs of small sections located symmetrically with respect to the diameter $AB$. Then we get that a thin conducting ring with current $I$, located in a horizontal magnetic field with induction $B$, will be subject to a moment of magnetic forces equal to

$$M_{\text{магн}} = BIS = BI \pi R^2.$$

He rotates the ring around the horizontal axis $AB$.

When the ring is on the verge of lifting, two mechanical forces will oppose its rotation - the gravity force $mg$, applied at the center of the ring and in the vertical direction downwards, and the normal reaction force $N$, applied at the point of contact of the ring and the plane and in the vertical direction upwards. Since the ring is still in balance,

$$mg - N = 0, \text{ т. е. } N = mg,$$

so the mechanical forces form their own pair of forces, which creates its own torque

$$M_{\text{мек}} = mgR.$$

From the equilibrium of the ring it follows that the total moment of all forces - in our case this is the sum of the moments of magnetic and mechanical forces - is equal to zero:

$$M_{\text{магн}} - M_{\text{мек}} = 0, \text{ или } BI \pi R^2 - mgR = 0.$$

From here the current value is found:

$$I = \frac{mg}{\pi BR}.$$

S. S. Krotov

F1182. When conducting radiolocation of the Moon, which had risen above the horizon, in order to ensure the return of directionality, the emitter of high-frequency radio scenes was coupled with an optical telescope. However, in the presence of an optical image of the Moon, there was no reflected radio scene. At the same time, when it was possible to obtain the reflected radiation

The described phenomenon actually occurs - the author encountered it while studying a communication channel in which the Moon was used as a passive reflector of radio systems. Moreover, the antenna connected to the optical telescope was not intended to work with the Moon, but to receive satellite television.

When the Moon rises above the horizon, the refraction of light is very significant, i.e., the bending of light rays due to refraction in the atmosphere. (Remember, for example, how greatly the shape and size of the Moon and Sun are distorted when they are low above the horizon.) For radio waves (using sant-
