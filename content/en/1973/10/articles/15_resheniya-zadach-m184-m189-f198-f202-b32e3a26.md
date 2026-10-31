---
id: 1973-10-resheniya-zadach-m184-m189-f198-f202-b32e3a26
issue: kvant_1973_10
year: 1973
number: "10"
title: Solutions to problems M184—M189; F198—F202
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 50
page_last: 57
page_labels: 48, 49, 50, 51, 52, 54
tag: U629
lang: en
source: kvant_digital
extraction: vision
content_sha256: 615e2ae1f41522a0041d0c84dac5a5052ca95831ebd4268157d934d151f21450
prompt_sha256: draft-1
translated_from: content/ru/1973/10/articles/15_resheniya-zadach-m184-m189-f198-f202-b32e3a26.md
source_content_sha256: 0e25a83f4a77f655184e80a9c45cc4d56260b3e09587640a161073b3285dc64c
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 48⟧

Problem solutions
M184—M189; F198—F202

M184. Prove Christmas

$$\frac{C_n^0}{x} - \frac{C_n^1}{x+1} + \dots + (-1)^n \frac{C_n^n}{x+n} = \frac{n!}{x(x+1)(x+2)\dots(x+n)}$$

Let us prove this also by the method of mathematical induction. For $n=1$ it is true because $C_1^0 = C_1^1 = 1! = 1$:

$$\frac{C_1^0}{x} - \frac{C_1^1}{x+1} = \frac{1!}{x(x+1)}$$

Let's assume that this is also true:

$$\frac{C_n^0}{x} - \frac{C_n^1}{x+1} + \frac{C_n^2}{x+2} - \dots + (-1)^{n-1} \frac{C_n^{n-1}}{x+n-1} + (-1)^n \times \frac{C_n^n}{x+n} = \frac{n!}{x(x+1)\dots(x+n)}$$

Let us replace $x$ in (1) with $x+1$. We also get:

$$\frac{C_n^0}{x+1} - \frac{C_n^1}{x+2} + \dots + (-1)^{n-1} \frac{C_n^{n-1}}{x+n} + (-1)^n \times \frac{C_n^n}{x+n} = \frac{n!}{x(x+1)\dots(x+n)}$$

Let us subtract term by term (2) from (1) and use the fact that

$$C_n^0 = C_n^n = C_n^{n+1} = C_n^{n+1} = 1,$$

$$C_n^k + C_n^{k+1} = C_n^{k+1}$$

for each $k=0,1,2,\dots,n-1$. We get

$$\frac{C_n^0}{x} - \frac{C_n^1}{x+1} + \frac{C_n^2}{x+2} - \dots + (-1)^n \frac{C_n^n}{x+n} + (-1)^n \times \frac{C_n^{n+1}}{x+n+1} = \frac{n!}{x(x+1)(x+2)\dots(x+n)}$$

Thus, the inductive step has been completed and our equality is proven for all $n$.

Those who read V. N. Vaguten’s article “Numbers $C_n^k$, sequences and polynomials” in «Kvant» No. 2 (1973) noticed, of course, that in problem M184 we obtained a difference formula of order $n$ for the sequence $f(x) = \frac{1}{x}$:

$$\Delta^n f(x) = \frac{(-1)^n n!}{x(x+1)\dots(x+n)}$$

Many readers have provided a proof of the following statement about the uniqueness of an identity of the form (1): if the identity is true

$$\frac{n!}{x(x+1)\dots(x+n)} = \sum_{i=0}^{n} \frac{A_k}{x+k},$$

food $A_k$ – some numbers, maybe

$$A_k = (-1)^k C_n^k = \frac{(-1)^k n!}{k!(n-k)!}$$

Indeed, it is enough to multiply both sides of (4) by the common denominator $x(x+1)\dots(x+n)$ and put $x = -k$ in the resulting identity. Then on the right are all terms except one

$$A_k(-k)(-k+1)\dots(-1)1\cdot2\dots\dots(n-k) = A_k(-1)^k k!(n-k)!$$

will go to zero and we will come to (5).

M185. On a kafman with area 1, 5 flames are placed, the area of ​​each of which is not less than $1/2$. Prove that there are two flames whose common part area is not less than $1/5$.

⟦folio 49⟧

Fig. 1.

Let us denote by $x_k$ the area of ​​the part of the caftan covered with $k$ patches ($k = 0, 1, \dots, 5$). By condition, the area of ​​the caftan is 1, and the sum of the areas of the patches is $\frac{5}{2}$:
$$S_0 = x_0 + x_1 + x_2 + x_3 + x_4 + x_5 = 1,$$
$$S_1 = x_1 + 2x_2 + 3x_3 + 4x_4 + 5x_5 = \frac{5}{2}.$$

The sum of the areas of all 10 pairwise intersections of patches is equal to
$$S_2 = x_2 + 3x_3 + 6x_4 + 10x_5 \geq -3x_0 - x_1 + x_2 + 3x_3 + 5x_4 + 7x_5 = 2S_1 - 3S_0 = 2,$$
Posibly, at least one of the 10 pairwise intersections will be at least $\frac{2}{10} = \frac{1}{5}$ in area (equality is possible only if $x_0 = x_1 = x_4 = x_5 = 0$ and all 10 pairwise intersections are equal in area!).

The solution to Problem M185 and its various variants and generalizations is closely related to one replacement general formula for additive set functions—the “inclusion and exclusion formulation.” This connection is discussed in detail in a separate article “Patches on the Caftan”, which will be published in the 12th issue of the magazine.

M186. Two points $A$ and $B$ are given on the plane. Let us find the geometric locus of the premarket $C$ of the triangle $ABC$, for which:
a) height $AA'$ is equal to side $BC$;
b) the median $AA_1$ is equal to the side $AC$;
c) the median $AA_1$ is equal to the side $BC$;
d) the height $CC'$ is equal to the median $BB_1$;
e) the height $BB'$ is equal to the median $CC_1$.

a) The required set of the point $C$ will be very indo symmetric with respect to the line $AB$; therefore, it is sufficient to investigate only the points lying in one of the half-planes into which the straight line $AB$ divides the plane.

Let us construct a point $D$ such that $DB \perp AB$ and $DB = BA$. In the half-plane that we will consider, there is such a point $D$, very indo, the only one. If the height of $AA'$ is $CB$, then (Fig. 2)
$$\Delta AA'B = \Delta CBD$$
(angles $A'AB$ and CBD are equal, both of them are acute to the plane, $AA' \perp BC$ and $AB \perp BD$). Thus,
$$\Rightarrow BCD = 90^\circ.$$

Conversely, if for some point $C$ the angle

⟦folio 50⟧

Fig. 3.

VSD is direct, then, obviously, ΔAA'B = ΔCBD and AA' = BC. Thus, it is enough to find the set of points C for which condition (1) is satisfied (B and D are fixed points). This set, as is known, is a circle with diameter BD.

6) Let E be a point on the extension of the median AA1 such that A1E = AA1. Then ACEB is a parallelogram (Fig. 3). The condition AA1 = AC is equivalent to AE = 2BE.

(2) Let us use the following theorem:

If A and B are two given points of the plane, then the set of points E of the plane for which $\frac{AE}{BE} = k$ (k is a fixed positive number different from 1) is a circle constructed on the diameter E1E2, where E1 and E2 are points on the line AB for which

$$\frac{AE_1}{BE_1} = k \quad u \quad \frac{AE_2}{BE_2} = k$$

(E1 lies inside the segment AB, E2 lies outside this segment). Below we briefly recall how this theorem can be proved *).

From this theorem it follows that the set of points E is a circle with diameter E1E2, E1 and E2 are points on the line AB and that

$$\frac{AE_1}{BE_1} = \frac{AE_2}{BE_2} = 2$$

*) See also books: Vasiliev N.B., Gutenacher V.L. Straights and curves. M., “Science”, 1970, p. 22, 102 and Gelfand I.M., Glagoleva E.G., Kirillov A.A. Coordinate method. M., “Science”, 1968, p. 32.

Fig. 5.

d) From point B1, the middle of side AC, we lower the perpendicular B1K to line AB. Of course, CC' = 2B1K, so the condition CC' = BB1 is equivalent to this condition (Fig. 5): BB1 = 2B1K (the leg is equal to the polyvine of the hypotenuse). Therefore, ∠B1BK = 30°. Therefore, the locus of point B1 is four rays emanating from point B and forming angles of 30° and 150° with segment AB. The set of points C is obtained from it by dilation with a factor of 2 and the center at point A.

e) Let L be the projection of point C1 (the midpoint of segment AB) onto line AC. Since (Fig. 6) BB' = CC1, then 2C1L = CC1 and ∠LCC1 = 30°. Therefore, ∠ACC1 is equal to 30° or 150°, and the locus of point C will be a pair of circles passing through points A and C1.

figure 7 shows the answers to problems M187 a)–d). We do not include the points C lying on the line AB itself in the original set of points (they lead to “degenerate” triangles ABC); higher

⟦folio 51⟧

WE didn't steal it on a case-by-case basis to save space.

We have received many solutions to problems M187 a)—e), but most of them contain shortcomings (for example, the loss of “use” of the answer, there is no complete proof “in both directions,” etc.).

N. B. Vasiliev

M188. Between some of the 2n cities there is a possibility of communication, and each city is connected with at least n others (non-stop solutions). Prove that even if you cancel any n-1 decisions, you can still get from any city to any other city by plane (with transfers). Indicate all cases when such “connectedness” is violated when n decisions are canceled.

Let us assume that after canceling some l decisions, the “connectedness” is broken. Then there are probably k cities where k ≤ n such that it is impossible to travel from them to the remaining 2n-k cities. Indeed, the distance between cities A and all the cities to which you can travel from it (possibly with transfers). If there are no more than n of them (together with A), then k cities need to be found.

If there are m and m > n, then it is impossible to get from them to the remaining 2n-m cities, and from these 2n-m < n cities it is impossible to get to the remaining m cities. So, in any case, there are k cities, where k ≤ n, from which it is impossible to travel to the remaining 2n-k cities. Initially, each of these cities was connected by avalins to at least n cities, so at least n+1-k decisions connected it to other than the allocated k cities and were therefore reversed. This means that in total no less than k(n+1-k) decisions were canceled. But k(n+1—k) > n—1 for k=1, 2, ..., n. Consequently, if n-1 decisions are canceled, then the “connectedness” is not violated.

Let us now answer the second question of the problem. Note that k(n+1—k) = n only for k=1 and k=n. If k=1, then this means that some cities were connected to exactly n cities and all these decisions were canceled. If k=n, then this means that some n cities A1, A2, ..., An are connected in pairs by avalines, the remaining n cities A1′, A2′, ..., An′ are also connected in pairs by avalines and there are n solutions connecting the cities A1 and A1′, A2 and A2′, ..., An and An′. On figure 8 you see avaline diagrams for n=2 and n=3.

L. G. Limanov

M189. Three segments AB, EF and CD pass through one point O, with point E lying on segment AC, and point F on segment BD. Prove that EF is less than at least one of the two segments—AB or CD (Fig. 9).

We will take advantage of the fact that the length of the bisectrix in a triangle does not exceed half the sum of the lengths of the sides enclosing it (prove this!). Suppose that the segment EF is longer by Δ than the segments AB, CD (max (AB, CD)). Let $\Rightarrow AOE \neq EOC$ — otherwise EF $\leq \frac{AB+CD}{2}$ and EF cannot be of length max (AB, CD). Let for definition $\Rightarrow AOE > EOC$. Therefore, then the segment E1F1 (see Fig. 10) is such that $\Rightarrow E1OE = EOC$. It is clear that point E1 belongs to segment AC, and point F1 belongs to segment BD. EF $\leq \frac{CD+E1F1}{2}$, so E1F1 at least at 2Δ length max (AB, DC). Thus, we were able to move from a segment “larger by Δ” to a segment “larger by 2Δ,” where Δ is some positive number. Having repeated this transition k times, we obtain a segment E1F1, which is at least 2^k·Δ longer than max(AB, CD). By choosing k large enough, we can make the length of the segment E1F1 greater than AB+CD, which is impossible. The resulting contradiction shows that the segment EF cannot be greater than max(AB, CD). Solution problem.

Fig. 7.

⟦folio 52⟧

Fig. 8.

Fig. 9.

Fig. 10.

Here is the second solution problem M189. Let us draw straight lines through points E and F perpendicular to EF. Let us continue the segments OA, OB, OC, OD until they intersect with these straight lines and introduce the notation as shown in figure 11. Let point A lie inside the strip between the straight lines, C - outside it; then D must lie inside the strip (otherwise, very indo, CD > EF), and B must lie outside. From not

Fig. 11.

equalities

$$\frac{AA_2}{CC_2} = \frac{A_2E}{EC_2} \leq \frac{A_1E}{EC_1} = \frac{B_1F}{FD_1} \leq \frac{B_2F}{FD_2} = \frac{BB_2}{DD_2}$$

it follows that either $AA_2 \leq BB_2$ (and then $AB > EF$) or $CC_2 \geq DD_2$ (and then $CD > EF$).

D. Yu. Grigoriev

F198. The skater decided to slow down and brought the straights together. Although it is difficult (at night?), a skater can keep the straight lines together. How will it move the data?

Obviously, at low speeds, the skater slows down, bringing the toes, not the heels, together. This movement of the skater is stable. However, the skater is going to fall. Therefore, at high speeds, a skater (like a hockey player) slows down, turning both skates in one direction. At the same time, of course, he slows down and at the same time moves to the side. However, even with the ability to wear their feet together, a skater usually rides alternately on one or the other skate.

When the blade of the skate is located in the direction of movement of the skater, the skate easily slides on the ice, that is, the friction force is very small. If a skater wants to brake, he places his skate at a certain angle to the direction of movement, and another friction force arises, perpendicular to the blade. The magnitude of this force is much greater than the first, since in this case the blade of the skate seems to be surrounded by ice. For simplicity, in the future we will only talk about this friction force perpendicular to the blade.

Let the skater manage to bring his heels together. From figure 12, a it is clear that in this case, in addition to the resistance forces $F_{c.1}$ and $F_{c.2}$, directed against the speed v, there are forces $F'_1$ and $F'_2$, which tend to move the skates apart. This is why the skater has to work hard to keep his heels together.

How will the skater move after he has brought his heels together? It is not difficult to answer this question, since it is known from experience that in this case the skater will turn around and then eat backwards. It's harder to explain why this happens. Several factors appear to be important here.

One of them is the dependence of the friction forces perpendicular to the plane of the skate on the angle formed by the plane of the skate with the direction of movement of the skate. If the angle is zero, then this force is also zero; at an angle of 90°, the force is maximum. (The dependence of friction forces on the angle is related.)

⟦folio 54⟧

Fig. 13.
write like this:

$$2 + \left( k + \frac{1}{k} \right).$$

According to the mean value theorem*), the sum $k + \frac{1}{k}$ is minimal when the terms are equal, that is, when $k = \frac{1}{k}$ or $k = 1$. At the same time $W_a = W_0$.

So, the neutron transfers the maximum part of its initial kinetic energy to the atom when the masses of the neutron and the atom are equal, as in the case of the hydrogen atom.

At $k = 207$, as in the case of lead, a neutron, when colliding with an atom, transfers to it approximately $\frac{4}{209}$ of its kinetic energy.

All arguments, in principle, remain valid for off-center impacts. Since collisions of a neutron with atoms of matter occur many times, the initial kinetic energy of the neutron quite quickly turns into heat.

This explains the fact that neutrons are well retained by water, paraffin or other connectors containing hydrogen atoms, and easily pass through the same blocks of lead.

F200. As a result of the pulsed discharge of the capacitor through a rarefied whole, a cutting occurs esa do temperature $T$. Estimate the values ​​of $T$ if the direction on the capacitor is $U = 30$ kV, the capacitance of the capacitor is $C = 18$ µF and the gas occupies a volume of 10 l at a pressure of $10^{-2}$ mm Hg. Art.

To estimate, we will assume that when a capacitor is discharged, all its energy is spent only on heating the helium, that is, on increasing its internal energy. Therefore we can write that

$$\frac{CU^2}{2} = \Delta W_{\text{BN}}.$$

Helium is a monatomic gas. Therefore, its internal energy $W_{\text{BN}}$ is equal to $\frac{3}{2}RTn$, and its change is $\Delta W_{\text{BN}} = \frac{3}{2}Rn(T - T_0)$, where $R$ is the universal gas constant, $n$ is the number of moles of gas, $T_0$ is the initial temperature. According to the equation of gas state

$$P_0V_0 = nRT_0$$

And

$$n = \frac{P_0V_0}{T_0R},$$

where $P_0$, $V_0$, $T_0$ are the initial parameters of helium ($T_0$ can be considered equal to room temperature, that is, $300^\circ\text{K}$). Thus, we get

$$\frac{CU^2}{2} = \frac{3}{2}R \frac{P_0V_0}{RT_0}(T - T_0),$$

where

$$\frac{T}{T_0} = \frac{CU^2}{3P_0V_0} + 1 \approx 1,2 \cdot 10^6$$

and $T \approx 3,6 \cdot 10^8$ degrees Kelvin.

When solving the problem, we assumed that we could neglect heat exchange with the environment, heating of the capacitor plates, and radiation of electromagnetic wave energy. The obtained result differs sharply from the experimental data, so it should be noted that our assumptions contradict reality. For example, taking into account heat exchange with the environment reduces the temperature by several orders of magnitude (up to about thousands of degrees).

F201. If a battery is connected to some resistance, then the time-dependent moka in the circuit will be maki, as shown in figure 14 red face. If a battery is connected to the same resistance, but is frequently discharged, then the time-dependent moka will be maki, as shown in figure 14 blue face. If both batteries are connected to the same resistance together, connecting them in parallel, then initially 1.5 A will flow through the circuit. Draw a graph of how the circuit continues to change over time.

The internal resistance of the battery does not change during the discharge process.

*) See article: Borovinsky L. A. Maximum and minimum problems. «Kvant», 1973, No. 5.

⟦folio none⟧

Since the batteries have the same e. d.s. and internal resistances, then when they are connected in parallel, equal currents will flow through them, equal to half the current through the resistance, that is, 0.75 A. Both batteries will be discharged.

According to the conditions of the problem, the cost *) of the first battery is 1 a·3 u = 3 a·u. Therefore, the second battery will be discharged within four hours ($\frac{3 a \cdot u}{0,75 a} = 4 u$); the capacity of the first by the end of this process will decrease to 2 a·u. After this, the second battery will behave similarly to a capacitor, on which there is some voltage, but no current flows through it. Indeed, as soon as e. d.s. This battery begins to decrease, the first battery will recharge it to e. d.s., equal to the voltage at the terminals of the battery.

From this moment on, the first battery will work only with external resistance. Since its remaining capacity is 2 a u, and the resistance carries a current of 1 a, its energy is enough for two hours of operation.

Consequently, for four hours a current of 1.5 A flows through the resistance, then for two hours - 1 A. A graph of current versus time is shown on figure 14 black line.

F202. A pipe of radius r is filled with a porous substance of density $\rho_0$. Weightless porridge, on which a constant force F acts, penetrating into the pipe, compacts the substance to a density of $\rho$ (Fig. 15). At what speed does the porridge move if compaction occurs with a rolling pin, that is, the surface in the pipe seems to be moving at a certain speed, to the right of the substance component $\rho_0$, and to the left p? At the initial moment, this surface coincides with the plane of the painting.

We will assume that the pipe is large enough so that the boundary of the region with different densities is located far from the end of the cylinder. Then it is clear that the only horizontal force acting on the substance in the cylinder is the force F; therefore, the change in the momentum of the substance in the cylinder is equal to the momentum of this force.

Each of the parts of matter set in motion moves at the speed of movement of the boundary between areas with different densities. Let's denote this speed c, and the speed of movement v.

*) Battery capacity is the maximum charge that can be obtained from it when discharged.

Fig. 15.

During the time $\Delta t$, the piston will move to a distance $v \Delta t$, and those particles that are in the volume $v \Delta t \pi r^2$ will begin to move, and the density of these particles is equal to $\rho_0$ (the remaining particles, whose density is $\rho - \rho_0$, are already moving at speed c). Since the speed of each particle is equal to c, the momentum that the particles of matter acquire in time $\Delta t$ is equal to $v \Delta t \rho_0 c \pi r^2$. This impulse, as we have already said, is equal to the impulse of force F. Therefore,

$$F \Delta t = \pi v \rho_0 c r^2 \Delta t.$$ (1)

It is clear that the velocities c and v are not independent. From the condition of conservation of mass it follows that the mass of the substance located in volume $v \Delta t \pi r^2$, when the piston is mixed at a distance $v \Delta t$, should be distributed over volume $c \Delta t \pi r^2$, and here it will have a density $\rho - \rho_0$. That's why

$$v \rho \Delta t \pi r^2 = c (\rho - \rho_0) \Delta t \pi r^2.$$

From here

$$c = v \frac{\rho}{\rho - \rho_0}.$$ (2)

Substituting (2) into formula (1), we get

$$F = \pi v^2 \frac{\rho \rho_0}{\rho - \rho_0} r^2,$$

And

$$v = \sqrt{\frac{F}{\pi r^2} \frac{\rho - \rho_0}{\rho \rho_0}}.$$

I.Sh. Slovodechky
