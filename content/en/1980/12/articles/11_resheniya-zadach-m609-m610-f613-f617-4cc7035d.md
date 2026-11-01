---
id: 1980-12-resheniya-zadach-m609-m610-f613-f617-4cc7035d
issue: kvant_1980_12
year: 1980
number: "12"
title: Solutions to problems M609, M610; F613—F617
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 26
page_last: 30
page_labels: 24-28
tag: SXYG
lang: en
source: kvant_digital
extraction: vision
content_sha256: 72f0241b5b06cfd8e5e772db787ce9861467e9e6f35cc03574f4bf58cf1fb114
prompt_sha256: draft-1
translated_from: content/ru/1980/12/articles/11_resheniya-zadach-m609-m610-f613-f617-4cc7035d.md
source_content_sha256: 0b74285472da05aecef0a20af47ea37529f6a76e98b3406881d5e1d406a9b796
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 24⟧

M609. a) The lengths of the projections of a convex polygon of area S onto two mutually redistributing straight lines are equal to $l_1$ and $l_2$. Prove that $S \leq l_1 l_2$.
b) The lengths of the projections of a convex polygon of volume V onto three mutually redistributing straight lines are equal to $l_1, l_2$ and $l_3$. Prove that $V \leq l_1 l_2 l_3$.
c) The areas of projections of a convex polygon of volume V onto three mutually redistributing straight lines are equal to $S_1, S_2$ and $S_3$. Prove that $V \leq \sqrt{S_1 S_2 S_3}$.

M609, M610; F613—F617

The statement of points a) and b) directly follows from the fact that in case a) the polygon is contained in a rectagon on the sides $l_1$ and $l_2$, and in case b) the polygon is contained in a rectangular parallelip with edges $l_1, l_2, l_3$.

c) Let $\pi_1, \pi_2, \pi_3$ be mutually redistributing planes, $S_1, S_2, S_3$ be the areas of projections of the polygon M onto these planes, and $l_1, l_2, l_3$ be the lines of projections of the polygon M onto straight lines $\pi_2 \cap \pi_3, \pi_1 \cap \pi_3, \pi_1 \cap \pi_2$, respectively, $V = V(M)$ be its volume. Planes parallel to $\pi_1$ will henceforth be called horizontal.

First decision. Fair inequalities
$$V \leq \sqrt{S_1 S_2 S_3}$$

for a direct feature with horizontal bases it easily follows from a): for such a feature $S_1 \leq l_2 l_3, S_2 = l_1 l_3, S_3 = l_1 l_2$ and $V^2 = (S_1 l_1)^2 = S_1 \cdot S_1 l_1^2 \leq S_1 \cdot l_1 l_2 \cdot l_1 l_3 = S_1 S_2 S_3$.

To prove (1) for an arbitrary polygon, we need

Lemma. Let the polygon M be cut by horizontal planes into n polygons $M_1, \dots, M_n$. If inequality (1) is satisfied for each of them, then it is also true for M.

Let us prove the lemma first for $n = 2$. Let the areas of the projections of polygons $M_1$ and $M_2$ onto the plane $\pi_2$ be equal to $a_1^2$ and $a_2^2$, and onto the plane $\pi_3$ - $b_1^2$ and $b_2^2$, respectively ($a_i > 0, b_i < 0$). The area of ​​projections $M_1$ and $M_2$ onto $\pi_1$ does not exceed $S_1$. That's why
$$V(M) = V(M_1) + V(M_2) \leq \sqrt{S_1} (a_1 b_1 + a_2 b_2) \leq \sqrt{S_1} \sqrt{a_1^2 + a_2^2} \sqrt{b_1^2 + b_2^2} = \sqrt{S_1 S_2 S_3}.$$

Inequality
$$(a_1 b_1 + a_2 b_2)^2 \leq (a_1^2 + a_2^2) (b_1^2 + b_2^2),$$

which we will use is equivalent to the estimated $(a_1 b_2 - a_2 b_1)^2 \geq 0$.

The proof of the lemma for any $n$ can be proven either by going through $n$, or similar to the case $n = 2$ using together (2) Cauchy’s inequality («Kvant», 1972, no. 1)
$$(a_1 b_1 + \dots + a_n b_n)^2 \leq (a_1^2 + \dots + a_n^2) (b_1^2 + \dots + b_n^2).$$

Now the proof of inequality (1) ends like this. Let us cut the polygon M into horizontal elephants. With a small thickness, say the volumes of the polygon M and the union of some features placed on top of each other (as well as the areas of their corresponding projections) differ in how small the angle is. Exactly:

Let $h$ be a small positive number. Let us draw sufficiently dense horizontal planes (including through all the vertices of the polygon M) so that M turns out to be cut into $n$ words of thickness $h_i \leq h(l_1 = h_1 + h_2 + \dots + h_n)$. Let us enclose the $i$th layer in a straight line with a height $h_i$ and a horizontal base coinciding with the projection of this layer onto the $i$th secant plane.

Let $M'$ be the union of the constructed features. The projection $M'$ onto $l_1$ coincides with the projection of the polygon M onto $l_1$: $S_1' = S_1$, and the areas $S_2'$ and $S_3'$ of the projections $M'$ on the plane $l_2$ and $l_3$ are not less than the areas $S_2$ and $S_3$, respectively, and the differences from them by the sum of the areas of rectangles protected on figure 1. This sum is not greater than $cl_1 h$, where $c$ is the most alta degree of the angles formed by the projections of the edges of the polygon M on the planes $l_2$ and $l_3$ with the vertical. That's why
$$V(M) \leq V(M') \leq \sqrt{S_1' S_2' S_3'} \leq \sqrt{S_1 (S_2 + cl_1 h) (S_3 + cl_1 h)}.$$

⟦folio 25⟧

Since this inequality is true for any $h$, $V \leqslant \sqrt{S_1 S_2 S_3}$.

Second solution. Let us introduce a rectangular coordinate system in space, taking $\pi_1 \cap \pi_2$, $\pi_1 \cap \pi_3$, $\pi_2 \cap \pi_3$ as the $Ox$, $Oy$ and $Oz$ axes, respectively. Let $[a; b]$ be a segment of the axis $Oz$ on which the polyhedron $M$ is projected. Through each point $z \in [a; b]$ we draw a horizontal plane. Let $S(z)$ be the cross-sectional area of ​​the polyhedron of this plane, and $l_2(z)$ and $l_3(z)$ the lengths of the projections of this section on the planes $\pi_2$ and $\pi_3$, respectively. It can be proven that

$$V = \int_a^b S(z) dz. \tag{4}$$

In the textbook “Geometry 9-10” (§58 and §66) this formula is derived for examples and for a body of revolution; for arbitrary polytopes the proof is similar. We will also use the formula (prove it yourself!)

$$S = \int_a^b l(z) dz, \tag{5}$$

where $S$ is the area of ​​a convex polygon lying in the $xOz$ plane, and $l(z)$ is the length of the segment along which a straight line parallel to the $Ox$ axis and passing through the point $z \in [a; b]$ (Fig. 2) intersects with the polygon. In addition, we will need Bunyakovsky’s integral inequality, which is an analogue of inequality (3):

$$\left| \int_a^b f(z) g(z) dz \right| \leqslant \sqrt{\int_a^b f^2(z) dz} \cdot \sqrt{\int_a^b g^2(z) dz}.$$

We will prove it for continuous functions $f$ and $g$.

Proof. Let $\lambda \in \mathbb{R}$. Let's consider the function

$$\varphi(\lambda) = \int_a^b (f(z) - \lambda g(z))^2 dz =$$

$$= \lambda^2 \int_a^b g^2(z) dz - 2\lambda \int_a^b f(z) g(z) dz + \int_a^b f^2(z) dz = A\lambda^2 - 2B\lambda + C$$

$$\left( A = \int_a^b g^2(z) dz, B = \int_a^b f(z) g(z) dz, C = \int_a^b f^2(z) dz \right).$$

The function $\varphi$ is a square trinomial that takes non-negative values ​​for any $\lambda$. Therefore, $\frac{D}{4} = B^2 - AC \leqslant 0$ or $B \leqslant \sqrt{A} \cdot \sqrt{C}$, and this is the required inequality. (Proof of inequality (3) by analogue.)

Now let's complete the second solution to the problem.

$$V = \int_a^b S(z) dz = \int_a^b \sqrt{S(z)} \cdot \sqrt{S(z)} dz.$$

Since $S(z) \leqslant S_1$ for any $z \in [a; b]$, we get

$$V \leqslant \sqrt{S_1} \cdot \int_a^b \sqrt{S(z)} dz.$$

By virtue of point a) $S(z) \leqslant l_2(z) l_3(z)$. That's why

$$V \leqslant \sqrt{S_1} \cdot \int_a^b \sqrt{l_2(z)} \cdot \sqrt{l_3(z)} dz.$$

Applying Bunyakovsky’s integral inequality and formula (5), we obtain

⟦folio 26⟧

M610. We fix $k \in \mathbb{N}$.
a) Consider the set of all sets of integers $a_1, \dots, a_k$ such that $0 \leq a_1 \leq a_2 \leq \dots \leq a_k \leq k$; let us denote the number of such sets by $N$. Let us consider among them those for which $a_k = k$; let their number be $M$. Prove that $N = 2M$.
b) Let us impose an additional constraint on the sets under consideration: the sum $a_1 + \dots + a_k$ is divisible by $k$. Let the corresponding numbers be $N'$ and $M'$. Prove that $N' = 2M'$ (From figure 1 it is clear that for $k = 3$ these numbers are $M = 10$, $N = 20$, $M' = 4$, $N' = 8$).

Fig. 1.

Fig. 2.

Fig. 3.

Fig. 4.

Fig. 5.

As is known, if two sets have the same number of elements, a one-to-one correspondence can be established between them. Strictly speaking, this is a certainty of what is equal in the set of elements, but this fact is sometimes forgotten. Meanwhile, quite often the equality of two numbers is established precisely through the one-to-one correspondence of the set.

We need to prove that there are exactly half of the sets containing $a_k = k$. Therefore, we will try to establish a one-to-one correspondence between their sets and the remaining ones with $a_k < k$.

It is impossible to associate the set $(a_1, a_2, \dots, a_k)$ with the set $(a_k, a_{k-1}, \dots, a_1)$, since the new set is unincreased. You can try to compare the set $(a_1, \dots, a_k)$ with the set $(k - a_k, k - a_{k-1}, \dots, k - a_1)$: it is already irreducible, but... $k - a_1$ does not have to be less than $k$. Therefore, this correspondence does not solve the problem. (Question: what problem does this correspondence solve?)

This means that a more complex correspondence is needed. To construct it, we need the concept of a Young diagram of a given set.

What this is, can only be explained with an example: the set $(0, 0, 2, 3, 5)$ corresponds to the diagram shown in figure 2 - in each line there are as many squares as the corresponding number.

Additional Young diagram to square (Fig. 3). Then it becomes clear that our initial idea was to have a diagram not of red, but of white squares (and, accordingly, not on the left-bottom, but on the right-top).

Let us now try the additional figure 3 with a vertical diagram - as in figure 4. Without this diagram on the left, we get the set $(2, 2, 3, 4, 4)$. Let us make this set complementary to set $(0, 0, 2, 3, 5)$.

Another example is depicted at figure 5.

It is clear that if the original set is $(a_1, \dots, a_k)$ and the additional set is $(b_1, \dots, b_k)$, then $a_k = k$ if and only if $b_k < k$. Indeed, $a_k = k$ if the upper right cell is included in the main Young diagram, and $a_k < k$ if it is included in the additional one.

The correspondence we have established between sets with $a_k = k$ and sets with $a_k < k$ is very indo and one-to-one. Thus we solved a). In addition, the sum of the numbers in the original and additional set is equal to $k^2$ (in our example - 25). Therefore, the sum of the numbers in the complementary set is divisible by $k$ if and only if the sum of the numbers in the original set is divisible by $k$. This solves 6).

There is also another solution: we can count the numbers $N$ and $M$ indefinitely. Exactly:

Lemma a. The number of sets of integers $a_1, \dots, a_m$ such that $0 \leq a_1 \leq \dots \leq a_m \leq k$ is $C_{k+m}^m$.

Proof. Consider the set $(b_1, \dots, b_m)$, where $b_i = a_i + i$: $b_1 = a_1 + 1$, $b_2 = a_2 + 2$, etc. Then, obviously, $1 < b_1 < b_2 < \dots < b_m < k + m$, that is, $(b_1, \dots, b_m)$ is an arbitrary set of $m$ integers of their first $k + m$ numbers. The number of such sets is $C_{k+m}^m$.

The number of sets in which $a_k \leq k$ is equal to $C_{k+k}^k$ according to the lemma. If $a_k = k$, then all we have to do is choose the numbers $a_1, \dots, a_k - 1$ so that $0 \leq a_1 \leq \dots \leq a_k - 1 \leq k$; their number is $C_{k+k-1}^k$. It remains to calculate that $2C_{k+k-1}^k$ is equal to $C_{k+k}^k$.

A. Crowd

⟦folio 27⟧

F613. A box of mass M stands on a horizontal table. In a box with external compression k, a load of mass m is suspended. At what amplitude of oscillations of the load does the box begin to bounce on the table?

Since a load of mass m is suspended in a circle, in a state of equilibrium the beam is stretched by values ​​Δx₁ (see mark) such that k Δx₁ = mg, that is

Δx₁ = mg/k.

The box is acted upon by a gravitational force Mg and a reaction force T from the spring. The force T is equal in absolute value to the elastic force - T = kx - and is directed downwards when the spring is stretched, and upwards when the ramp spring is stretched. The box begins to bounce when the force T becomes greater than the force Mg: T ≥ Mg. At the moment when T = Mg, the slope Δx₂ of the spring is equal to

Δx₂ = Mg/k.

Consequently, the box begins to bounce when the amplitude of oscillation of the spring is equal to

A = Δx₁ + Δx₂ = (M + m) g/k.

L. Bakanina

F614. In a closed vessel there was nitrogen gas at room temperature t₀ = 20°C and pressure p₀ = 10⁵ Pa. Some vibrations of the load have been injected into the vessel; the box begins to jump up on the table with a temperature t₁ = -196°C (the temperature of nitrogen at normal atmospheric pressure). Liquid nitrogen quickly evaporated, after which the temperature in the vessel turned out to be t₂ = -140°C. After the vessel reached room temperature, a pressure p = 1.5 10⁵ Pa was established in it. Determine the molar heat of vaporization of each nitrogen. The heat capacity of nitrogen gas at constant volume is Cₙ = 20.8 J/ (mol K).

Since the evaporation of each nitrogen, according to the conditions of the problem, occurred quickly, temperature exchange with the environment can be avoided. Evaporation of a mass of nitrogen Δm and its heating from temperature t₁ to temperature t₂ occurs due to heat taken away from the initial mass of nitrogen m. Let's write the heat balance equation:

C_V m/M (t₀ - t₂) = Δm/M [λ + C_V (t₂ - t₁)].

From here we find the molar heat of evaporation of each nitrogen λ:

λ = [ (t₀ - t₂) / Δm/m] (t₂ - t₁)] C_V.

According to the conditions of the problem, the final pressure in the vessel turned out to be 1.5 times greater than the initial pressure P₀ at the same room temperature t₀. This means that the mass of nitrogen in the vessel has increased by 1.5 times, that is, (m + Δm)/m = 1.5, and Δm/m = 0.5. Substituting this value from the condition for the values ​​of t₀, t₁, t₂ and C_V into expression (*), we find

λ = 5500 J/mol.

V. Belonukin

F615. In the case of a non-self-sustaining gas discharge, the dependence of the current I through the gas-discharge coarse on the voltage U between the electrodes of the coarse has the form shown in figure 1. A tube with a series connection with a ballast resistance R = 3 · 10⁸ Ohm is connected to a source with a constant EMF E = 6 kV. Find what current is installed through the wire and what will be the voltage across the wire. Neglect the internal resistance of the source.

The connection diagram for the gas-discharge roughener is shown in figure 2.

Let's find the minimum value of the source emf at which it will reach saturation through the coarse. To do this, complete Ohm's law for the circuit:

ε_min = U_H + I_H R,

where U_H = 10³ V, I_H = 10⁻⁵ A (see Fig. 1). Substituting numerical values, we find ε_min = 4 kV.

In our case, the emf of the source is ε > ε_min. Therefore, the current through the rougher is equal to the saturation current. For example, this is determined by the condition ε = U + I_H R, whence

U = ε - I_H R = 3 kV.

The magnitude of the current through the grinder can be determined in another way. Let us assume that the current I in the circuit is less than the saturation current. Let's write Ohm's law for this case:

ε = I(R_Tp + R),

where R_Tp is the internal resistance of the rough. The value of R_Tp is found from the slope of the linear section of the current-voltage xa-

⟦folio 28⟧

Ractor pipes (see Fig. 1):

$$R_{\text{тр}} = \frac{U_H}{I_H} = 10^8 \text{ Ом.}$$

Thus,

$$I = \frac{\mathcal{E}}{R_{\text{тр}} + R} = 15 \text{ мкA.}$$

The found current value is large $I_H$. Therefore, our assumption that $I < I_H$ is incorrect. The current through the tube is equal to the saturation current.

V. Mozhaev

Fig. 1.

Fig. 2.

F616. The length of the accumulation filament of a light bulb is $l$, and the diameter is $d$. What are the length $l_1$ and diameter $d_1$ of another light bulb designed for the same mains voltage, but with a higher luminous flux input, if the efficiency of both light bulbs is the same?

Let $W$ and $W_1$ be the powers consumed from the network by the first and second lamps. Then the energies emitted by the lamps in the form of light (light fluxes) are equal, respectively, to $E = \eta W$ and $E_1 = \eta W_1$, where $\eta$ is the efficiency of the lamps.

In a state of equilibrium, the power $W$ ($W_1$) received by the lamp from the network must be equal to the power $P$ ($P_1$) emitted by the lamp in the form of light and heat. The power $P$ ($P_1$), very indo, is proportional to the area $S$ ($S_1$) of the filament surface and some function of the temperature $f(T)$ ($f(T_1)$). Hence,

$$P = W = k_1 S f(T), \quad W_1 = k_1 S_1 f(T_1),$$

where $k_1$ is the proportionality coefficient. The luminous flux emitted by the lamp is also proportional to the surface area of ​​the filament and some function of temperature:

$$E = k_2 S \varphi(T), \quad E_1 = k_2 S_1 \varphi(T_1).$$

And since $E = \eta W$, then

$$k_2 \varphi(T) = \eta k_1 f(T), \quad k_2 \varphi(T_1) = \eta k_1 f(T_1).$$

From these equalities it is clear that the efficiency of a light bulb is determined by the temperature of the filament. Consequently, with the same efficiency of two lamps, the temperatures of their filaments accumulate, that is, $T_1 = T$. This means that

$$\frac{E_1}{E} = \frac{k_2 S_1 \varphi(T)}{k_2 S \varphi(T)} = \frac{S_1}{S} = \frac{d_1 l_1}{dl}.$$

According to the conditions of the problem $E_1: E = 2$, that is

$$\frac{d_1 l_1}{dl} = 2.$$

At mains voltage $U$

$$E = \eta W = \eta \frac{U^2}{R}, \quad E_1 = \eta W_1 = \eta \frac{U^2}{R_1},$$

where $R = \varrho \frac{4l}{\pi d^2}$, $R_1 = \varrho \frac{4l_1}{\pi d_1^2}$ are the resistance of the lamp filament ($\varrho$ is the resistivity of the filament materials at the operating temperature of the lamps). Therefore, $\frac{E_1}{E} = \frac{ld_1^2}{l_1 d^2}$, and according to the condition,

$$\frac{l d_1^2}{l_1 d^2} = 2.$$
