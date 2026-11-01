---
id: 1982-2-resheniya-zadach-m686-m690-f698-f702-a4ccf6ae
issue: kvant_1982_2
year: 1982
number: "2"
title: Solutions to problems M686—M690; F698—F702
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 30
page_last: 35
page_labels: 28, 29, 31, 33
tag: B9U2
lang: en
source: kvant_digital
extraction: vision
content_sha256: 9d447b8b85a9c09b0aa862f772c3cc58f1efe108ecd03de3ead61277bca0706a
prompt_sha256: draft-1
translated_from: content/ru/1982/02/articles/09_resheniya-zadach-m686-m690-f698-f702-a4ccf6ae.md
source_content_sha256: 3b2e64ae77cc81a4111cf6e7d765e8e798610da730e2460e18ed086281d64c1e
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 28⟧

P742. A glass receptacle of rectangular section is placed between two convergent lenses of focal distances $F$, perpendicularly to the lenses' optical axis (see figure Pisc. 3, p. 26). A point light source $S$ is located in the focal plane of the lens $\Lambda_1$. When the receptacle is empty, the image of the source may be observed on the screen $\exists$ located in the focal plane of the lens $\Lambda_2$. The receptacle is filled with a transparent liquid whose refraction index varies with height in accordance to the rule $n(y) = n_0 + ay$. The thickness of the layer of water is $L$. What will the vertical displacement of the image on the screen be? The change of the refraction index within the diameter of the light beam may be assumed negligible.

V. Mojaev

Problem solutions

M686 — M690; F698 — F702

Answer: for anyone.

Let $a$ be a natural number for which $a^4 \leqslant x < (a+1)^4$. Then $a^2 \leqslant \sqrt{x} < (a+1)^2$. Hence, on the one hand, $a \leqslant \sqrt{x} < a+1$, $[\sqrt{x}] = a$. On the other hand, $a^2 \leqslant [\sqrt{x}] < (a+1)^2$, $a \leqslant \sqrt{x} < a+1$, $[\sqrt{x}] = a$.

G. Galperin

M687. a) In the nine-coel paramid, all 9 lateral ribs and all 27 base diagonals are colored: some are red, the rest are blue. Prove that there are three vertices of a paramid that serve as vertices of a triangle, all sides of which are colored the same color.

b) Is the same statement true for the premycetal paramid?

a) Among the nine lateral ribs of the paramid, there are five painted in one color (for example, red). Let $A_1, A_2, A_3, A_4, A_5$ be the ends of these edges, numbered consecutively. One of the pentagon's sides $A_1A_2A_3A_4A_5$ is the diagonal of the base (let, for definition, be $A_1A_2$). Consider the triangle $A_1A_2A_4$; its sides are the diagonal of the base. If it is one-link, then everything is proven. If not, then one of its sides (diagonals of the base) is red, and therefore the triangle formed by this diagonal and the lateral edges connecting its ends with the vertex of the paramid will be a single-linked one.

b) Answer: false. An example is obtained if four indicative edges in a row are colored red, and the remaining four edges are colored blue, with the ends of the red edges connected by blue diagonals, and the ends of the blue ones by red ones. (Tell me how to color the remaining diagonals.)

H. Nenov

M688. Given the natural numbers $a_1, a_2, ..., a_n$ the same as $a_k \leqslant k$ ($k=1, 2, ..., n$) and the sum $a_1 + a_2 + ... + a_n$ is even. Prove that one of the expressions $a_1 \pm a_2 \pm a_3 \pm ... \pm a_n$ is equal to zero.

Let us prove that the statement is by indication of $n$.

For $n=2$ it is obvious, since the only possible set is $a_1 = a_2 = 1$.

Let it be proven for a set of less than $n+1$ numbers; Let's prove it for $n+1$ numbers.

Let's take an arbitrary set $a_1, a_2, ..., a_n, a_{n+1}$ of $n+1$ numbers that satisfies the condition. If $a_n = a_{n+1}$, then the sum $a_1 + ... + a_{n-1}$ is even; Taking into account the indication assumption, we conclude that one of the sums $a_1 \pm a_2 \pm ... \pm a_{n-1} + a_n - a_{n+1}$ is equal to zero. If $a_n \neq a_{n+1}$, we replace this set with $a_1, a_2, ..., a_n - a_{n+1}$ of $n$ numbers. For the new set, all conditions are met: the number $|a_n - a_{n+1}|$ has the same parity as $a_n + a_{n+1}$, so the sum of $n$ numbers is still even; from $a_n \neq a_{n+1}$, $1 \leqslant a_n \leqslant n$ and $1 \leqslant a_{n+1} \leqslant n+1$ follows $1 \leqslant |a_n - a_{n+1}| \leqslant n$. By assumption of the indication, one of the sums $a_1 \pm a_2 \pm a_3 \pm ... \pm a_n$ is equal to zero. Remains-

⟦folio 29⟧

Xia “open the model”. In any case, $|a_n - a_{n+1}| = \pm (a_n - a_{n+1})$, and we get that one of the expressions $a_1 \pm a_2 \pm a_3 \pm \dots \pm a_n \pm a_{n+1}$ is equal to zero (in our solution, $a_{n+1}$ and $a_n$ are always preceded by different signs).

S. Nenashev

M689. Prove that it is impossible to form a rectangle from identical tiles in the shape of equilateral trapezoids with bases of 3 cm, 1 cm and a height of 1 cm.

Let us assume that the rectangle has been removed from $n$ trapezoids. Let us mark the points where the vertices of the trapezoid fall, including the four vertices of the rectangle.

Each trapezoid has two acute angles (45° each) and two obtuse angles (135° each), so all $n$ trapezoids together have the same number of acute and obtuse angles - 2$n$ each.

On the other hand, it is clear that at each of the marked points there are no less acute angles than obtuse ones (if there is one type of angle there, then there is at least one acute angle, and if there are two obtuse ones, then two acute ones - see figure); in this case, only the sharp corners of trapezoids can appear at the vertices of the rectangle. Thus, there are more acute angles than obtuse angles (at least 8).

The resulting contradiction proves the impossibility of constructing a rectangle from trapezoids.

N. Vasiliev

M690. a) Inside a convex polygon of area $S_1$ and perimeter $P_1$ there is a convex polygon of area $S_2$ and perimeter $P_2$. Prove the inequalities
$$2\frac{S_1}{P_1} > \frac{S_2}{P_2}.$$
6) Form and prove a similar statement for convex polygons.

Fig. 1.

a) Let us first note that for triangles a stronger statement is true: $\frac{S_1}{P_1} > \frac{S_2}{P_2}$. This is almost obvious, since $\frac{2S_1}{P_1}$ and $\frac{2S_2}{P_2}$ are the radii of the circles inscribed in these triangles.

To prove the general statement, we will use two facts, which we will prove below:

1) in any convex polygon of area $S$ and perimeter $P$ one can place a circle of radius $R > \frac{S}{P}$;

2) for any circle containing a given polygon, $R \leq \frac{2S}{P}$.

Statement a follows immediately from 1) and 2): let us place a circle of radius $R > \frac{S_2}{P_2}$ in the internal polygon; since $R \leq \frac{2S_1}{P_1}$, we obtain what is required.

Let's prove 1). On each side of the (convex) polygon we construct a rectangle with height $h = \frac{S}{P}$ (Fig. 1; $S$ is the area, $P$ is the perimeter of the polygon). These lines overlap; they can even “crawl” outside the polygon. Since the total area of ​​the rectangles is $S$, the area of ​​the part of the polygon covered by them is less than $S$. Therefore, there is an uncovered point located at a distance $R > h$ from all sides.

Let's prove 2). Let $O$ be the center of a circle of radius $R$ containing in the polygon (Fig. 2). Since the length of the altitudes of triangles with vertex $O$, the bases of which are the sides of the polygon, is not less than $R$, we obtain

⟦folio 31⟧

speed of rotation of the liquid begins to float out of the capillary? Liquid density q, surface tension σ, liquid completely wets the capillary; capillary dimensions are indicated at figure.

Let ω be the maximum angular velocity of rotation of the capillary. Divide the mental horizontal bend into N segments of small length Δx=l/N (Δx<<l). Let's consider two small elements of water mass Δm=πr²ρ·Δx, located at distances x from the middle of the elbow (see figure). Let us write down the equation of motion of these elements:

$$\Delta m \cdot \omega^2 \left( \frac{l}{2} - x \right) = \left( p_{i+1} - p_{i-1} \right) \pi r^2,$$

$$\Delta m \cdot \omega^2 \left( \frac{l}{2} + x \right) = \left( p_{q+1} - p_{q-1} \right) \pi r^2,$$

where $p_{i-1}$ ($p_{q-1}$) and $p_{i+1}$ ($p_{q+1}$) are the pressure on these elements of the corresponding left and right. The number of such pairs is very large N/2. Summing up all similar equations, we get

$$\frac{N}{2} \cdot \Delta m \cdot \omega^2 l = \left( p_B - p_A \right) \pi r^2 \Rightarrow \frac{\varphi \omega^2 l^2}{2} = \frac{4\sigma}{r} - \varphi gh.$$

From here we find ω:

$$\omega = \sqrt{\frac{8\sigma/r - 2\rho gh}{\rho l^2}}.$$

A. Buzdin

F701.*) figure 1 shows the distribution of water temperature of a thin homogeneous heat-conducting rod at some point in time. How will the temperature distribution change in the future? What distribution will be established after a sufficient fraction of time?

The process of temperature redistribution ends with temperature equalization along the entire length of the rod. Since the rod conducts heat, its internal energy remains unchanged. It is easy to understand that the area under the temperature distribution curve at any intermediate stage will remain constant. Consequently, the temperature $t_y$ of the rod, which will be established after a sufficient fraction of time (Fig. 2), can be determined from the condition

$$t_y \cdot 90 = 2(200 \cdot 30) + 100 \cdot 30.$$

Fig. 1.

Fig. 2.

From here is

$$t_y \approx 166,6^\circ C.$$

At the beginning of the temperature equalization process, the most changes will be at the boundaries between areas with the most different temperatures. In the middle part of the rod (40÷70 cm at figure 2) the temperature will increase, approaching 166.6°C, and in the side parts (10÷40 cm and 70÷100 cm at figure) - the concept, approaching this temperature.

O. Savchenko

F702. Two systems, one of which consists of two identical masses m, connected by a clamp of stiffness k, move along a smooth horizontal surface on

After time $t_1 = L/2v_0$ there will be a collision of masses I and I'. Since the collision is abscise elastic, immediately after the impact the speed of each of these masses remains the same in abscise magnitude, but puts the direction in the opposite direction, and the speeds of masses II and II' do not change (Fig. 2). Consequently, immediately after the collision in each system

⟦folio 33⟧

the corresponding charges at a given location on the surface are reversed. Indeed, the mergers of interactions in the $P_1$ ($P_2$) configuration are mergers of mutual repulsion of charges “sitting” on the surface. Changing the signs of all charges leaves these fusions unchanged, so each elemental surface charge will be in equilibrium; in this case, the electric field at each point in space outside the conductor will only change direction to the opposite. Thus, the $P'_1$ ($P'_2$) configuration will also be equilibrium.

Let's consider this situation further. The reported conductor charge $Q$ takes on the distribution $P_1$. Having “frozen” this distribution, we place a charge on the conductor - $Q$ so that it takes on the distribution $P'_2$. If now the total charge of the conductor (equal to zero) represents itself, then, according to the principle of superosition, the system will be in equilibrium and no charge flow will occur over the surface of the conductor. So, the total charge of the conductor turns out to be zero; in this case, on the surface of the conductor it is necessary to find differently charged areas: $A_1$, positively charged, and $B_1$, negatively charged. Consider the merging line coming out of the region $A_1$. Since the conductor is remote, this draining line either ends at it or goes to infinity. In the first case, the start and end points of the drain line (belonging to the conductor) must have different potentials (why?), which cannot be the case. The second case remains. Similarly, if we consider one of the plumbing lines coming to the conductor in the region $B_1$, we come to the conclusion that it came from infinity. We believe that infinity has a fixed potential; but then the potential of region $A_1$ is higher than the potential of infinity, and the potential of infinity is higher than the potential of region $B_1$, that is, different areas of the conductor have different potentials. But this contradicts the condition of equilibrium of charges on the surface of the conductor.

So, the assumption about the possibility of two different equilibrium charge distributions was incorrect. The charge on a conductor can be distributed in only one way. If in a particular problem we managed to guess the equilibrium distribution of charges, then this will be the answer.

Let us consider in the light of the above solution problem F700. Let us recall its conditions:

$\Phi 700$. There are two conductors $A$ and $B$ of arbitrary shape. Initially, conductor $A$ has a charge $Q$, and conductor $B$ is not charged. The conductors are brought into resistance (see Fig.ok), and charge $q$ flows onto the conductor $B$. The contacting conductor imparts an additional charge $q_x$, and as a result, charge $q$ appears on the conductor $A$. Determine the charge $q_x$.

Two touching conductors $A$ and $B$ constitute a solitary conductor ($A+B$). The charge imparted to this conductor is $Q$. Let us consider a small element Ds of the surface of the conductor, on which, as a result of the equilibrium distribution of the charge $Q$ over the surface of the conductor ($A+B$),

the charge density $\sigma$ was new. If the conductor ($A+B$) (uncharged) were given a charge $Q'$, then the steady-state charge density $\sigma'$ on $\Delta s$ would satisfy the following relation:

$$\frac{\sigma'}{\sigma} = \frac{Q'}{Q}.$$

Indeed, merging, acting on the charged element $\Delta s$ of the conductor surface ($A+B$) from other charged areas of the surface, is defined as the sum of the forces of interaction of a given surface element with all the others. Since the spatial arrangement of the conductors remained unchanged (this is an important point), the mutual distances between the elementary charges (charges of individual surface elements ($A+B$)) also remained unchanged, and only the values ​​of the charges associated with the surface of the surface changed. Therefore, each of the forces of pairwise interaction of charge elements changed by the same number of times - $(Q'/Q)^2$ times. Thus, each elementary region of the surface will still be in equilibrium.

From the above reasoning it follows that, no matter what charge is imparted by the contacting conductor $A$ and $B$ (conductor ($A+B$)), the relation of the charge $q_A$, distributed on the conductor $A$, to the charge $q_B$, distributed on the conductor $B$, remains unchanged (of course, with the same relative position of the contacting conductors).

Initially, when charge $Q$ is distributed on the conductor ($A+B$),

$$\frac{q_A}{q_B} = \frac{Q - q}{q}.$$

When communicating to the conductor ($A+B$) an additional charge $q_x$

$$q_x = Q \frac{2q - Q}{Q - q}.$$
