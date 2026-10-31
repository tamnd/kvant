---
id: 1974-8-resheniya-zadach-m236-m240-f243-f247-90c8095b
issue: kvant_1974_8
year: 1974
number: "8"
title: Solutions to problems M236—M240; F243—F247
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 48
page_last: 55
page_labels: 46, 47, 48, 51, 52, 53
tag: Y5MF
lang: en
source: kvant_digital
extraction: vision
content_sha256: bf4b1f8e1f70c6f981d8cb689b3d4a6be4e26f48e44551c727fbe46ddc740eaf
prompt_sha256: draft-1
translated_from: content/ru/1974/08/articles/11_resheniya-zadach-m236-m240-f243-f247-90c8095b.md
source_content_sha256: 36b3cab34c289f2f057ecf1bd1ae8d0c2869917d3cfa48181743e935f60400ca
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 46⟧

Problem solutions
M236—M240; F243—F247

M236. a) There are 51 two-digit numbers. Let us prove that from these numbers it is possible to choose at least 6 numbers so that no two of the selected numbers have the same digit in any digit.

b) Given natural numbers k and n, 1 < k < n. For every smallest m, the following statements are true: for any dispersion of m rooks on a board of size n × n, is it possible to choose k rooks from these m such that no two of the selected rooks are each other?

Let's solve problem 6 first). Let us prove that if m = n (k − 1) + 1, then it is always possible to choose k rooks so that no two of them are each other. (The fact that n (k − 1) rooks is not enough means there is too much to arrange in the first k − 1 columns and then it is impossible to choose more than k − 1.) So, m = n (k − 1) + 1. Let us show that from these m rooks it is always possible to choose one such that in its “cross” - passing through a rook in a column and row - costs no more than n + k − 2 rooks. Let this not be done. Among all the rows (rows and columns), we choose the one with the most rooks; Let's denote their number by l. By assumption, the cross of each of these rooks contains more than n + k − 2 rooks; This means that there are at least l (n − k − l) rooks in total, and l ≥ n + k − l and n ≥ l, that is, l ≥ k. Now it is easy to see that l (n + k − l) is not less than n · k, which is greater than m = n (k − 1) + 1 if n is greater than one. We received a contradiction; Therefore, there is a rook whose cross contains at most n + k − 2 rooks. Let's mark this rook and cut out its cross from the dock. From the remaining parts we will make a dock of dimensions (n ​​− 1) × (n − 1). There will be at least m − (n + k − 2) = n (k − 1) + 1 − (n + k − 2) = (n − 1) (k − 2) + 1 rooks on the new board.

Now suppose that for r × r boards, where r < n, the statement has already been proven (check it, for example, for n = 3, k = 2). Then on a board of (n − 1) × (n − 1) from (n − 1) · (k − 2) + 1 rooks it is always possible to select (k − 1) rooks so that no

⟦folio 47⟧

kaospessya inside the triangle at point O (Fig. 1). Note that in order for the center of gravity*) of these masses to reach point O, it is necessary to satisfy the correspondences $\frac{m_c}{m_a} = \frac{AD}{DC}$ and $\frac{m_b}{m_a} = \frac{AE}{BE}$ (prove this). Let us now move on to solving the problem.
a) Let BD and CE be the altitudes of triangle ABC (Fig. 2). Then
$$\frac{BD}{AD} = \text{tg} \alpha, \quad \frac{BD}{DC} = \text{tg} \gamma,$$
that is
$$\frac{AD}{DC} = \frac{\text{tg} \gamma}{\text{tg} \alpha}.$$
According to the following remark, $\frac{m_c}{m_a} = \frac{\text{tg} \gamma}{\text{tg} \alpha}$ and similarly $\frac{m_b}{m_a} = \frac{\text{tg} \beta}{\text{tg} \alpha}$. This means that, for example, masses $m_a = \text{tg} \alpha, m_b = \text{tg} \beta, m_c = \text{tg} \gamma$ can be placed at the vertices A, B, C of triangle ABC.
6) Let O be the center of the circumscribed circle (Fig. 3). We have:
$$\frac{AD}{BD} = \frac{\sin \beta_1}{\sin \alpha},$$
$$\frac{DC}{BD} = \frac{\sin \beta_2}{\sin \gamma}.$$
(theme of sines for triangles ABD and BCD).
Therefore
$$\frac{AD}{DC} = \frac{\sin \gamma \cdot \sin \beta_1}{\sin \alpha \cdot \sin \beta_2}.$$
Triangle BAK - rectangular

*) On centers of gravity, see the article by M. B. Balka, N. A. Grigoriev, Mechanics helps geometry, «Kvant», 1973, No. 11, p. 34-35.

(✉BAK = 90°) and ✉BKA = ✉BCA = γ; therefore $\sin \beta_1 = \cos \gamma$. Same as $\sin \beta_2 = \cos \alpha$.
So,
$$\frac{AD}{DC} = \frac{\sin \gamma}{\sin \alpha} \cdot \frac{\cos \gamma}{\cos \alpha} = \frac{\sin 2\gamma}{\sin 2\alpha}.$$
Considering the note:
$$\frac{m_c}{m_a} = \frac{\sin 2\gamma}{\sin 2\alpha}.$$
In the same way
$$\frac{m_b}{m_a} = \frac{\sin 2\beta}{\sin 2\alpha}.$$
So we can take $m_a = \sin 2\alpha, m_b = \sin 2\beta, m_c = \sin 2\gamma$.
c) It is easy to see (see Fig. 4) that AD=p-a, DC=p-c, where $p = \frac{a+b+c}{2}$, therefore
$$\frac{m_c}{m_a} = \frac{p-a}{p-c}.$$
Similarly AE=p-a, EB=p-b, that is
$$\frac{m_b}{m_a} = \frac{p-a}{p-b}.$$
Therefore, it is enough to put
$$m_a = \frac{1}{p-a}, \quad m_b = \frac{1}{p-b}, \quad m_c = \frac{1}{p-c}.$$
d) Since BD is the bisector of angle B (see Fig. 5), then $\frac{AD}{DC} = \frac{c}{a}$ or $\frac{m_c}{m_a} = \frac{c}{a}$;
correspondence CE is the bisector of angle C and $\frac{AE}{BE} = \frac{b}{a}$, that is, $\frac{m_b}{m_a} = \frac{b}{a}$. Therefore, you can take $m_a = a, m_b=b, m_c=c$.

B. D. Ginzburg

⟦folio 48⟧

Fig. 6.

**M238.** Prove that the sum $C_n^1 + C_n^3 \cdot 1973 + C_n^5 \cdot (1973)^2 + C_n^7 \cdot (1973)^3 + \dots$ is divisible by $2^{n-1}$. (Here $C_n^k$ are the multiplier coefficients of the multiplier)

$$ (a + b)^n = \sum_{k=0}^{n} C_n^k a^k b^{n-k}. $$

We will solve our problem by induction. Let's put

$$ \gamma_n = C_n^1 + C_n^3 \cdot 1973 + C_n^5 \cdot (1973)^2 + \dots $$

We have:

$$ \gamma_1 = 1 \text{ делится на } 2^{1-1}=1; $$
$$ \gamma_2 = 2 \text{ делится на } 2^{2-1}=2. $$

Suppose that for all $k<n$

$$ \gamma_k = C_k^1 + C_k^3 \cdot 1973 + \dots. $$

is divisible by $2^{k-1}$, and we will prove that then $\gamma_n$ is divisible by $2^{n-1}$. From the definition of numbers $C_n^k$ it immediately follows that

$$ \gamma_n = C_n^1 + C_n^3 \cdot 1973 + \dots = \frac{(1 + \sqrt{1973})^n - (1 - \sqrt{1973})^n}{2\sqrt{1973}}. $$

Let us denote $1 + \sqrt{1973}$ by $\alpha, a_1 - \sqrt{1973}$ by $\beta$.

Taking these notations into account, we rewrite $\gamma_n$ as follows:

$$ \gamma_n = \frac{(\alpha^{n-1} - \beta^{n-1})(\alpha + \beta)}{2\sqrt{1973}} - \frac{\alpha \beta (\alpha^{n-2} - \beta^{n-2})}{2\sqrt{1973}} = 2\gamma_{n-1} + 1972 \gamma_{n-2} = 2\gamma_{n-1} + 4 \cdot 493\gamma_{n-2}. $$

By induction assumption, $\gamma_{n-1}$ is divisible by $2^{n-2}$, $\gamma_{n-2}$ is divisible by $2^{n-3}$; This means that the entire sum is divisible by $2^{n-1}$ - which is what needed to be proven.

L. G. Limanov

**M239.** Two points $A$ and $B$ are given on the plane. Let $C$ be a non-sharp point equally distant from $A$ and $B$. Let us construct a sequence of points $C_1 = C$, $C_2$, $C_3$, ..., $C_n$, $C_{n+1}$, ..., and $C_{n+1}$ - the center of the circle circumscribed about the triangle $AC_nB$. At what position of point $C$

a) point $C_n$ will fall in the middle of the segment $AB$ (in this case $C_{n+1}$ and further terms of the sequence are not defined)?
b) does the point $C_n$ coincide with $C$?

Let $\not\Rightarrow C_nBA = \not\Rightarrow C_nAB = \alpha_n$. It is easy to check (Fig. 6 a, 6) that for an acute triangle

$$ \alpha_{n+1} = 2\alpha_n - \frac{\pi}{2}, \frac{\pi}{4} < \alpha_n < \frac{\pi}{2}, $$

for obtuse

$$ \alpha_{n+1} = \frac{\pi}{2} - 2\alpha_n, 0 < \alpha_n < \frac{\pi}{4}. $$

This can be written in one formula:

$$ \alpha_{n+1} = \left| 2\alpha_n - \frac{\pi}{2} \right|, 0 < \alpha_n < \frac{\pi}{2}, $$

which is also suitable for a right triangle; for $\alpha_n = \frac{\pi}{4}$ we get $\alpha_{n+1} = 0$ - the center $C_{n+1}$ falls in the middle of the segment $AB$.

Let us set $\alpha_n = x_n \cdot \frac{\pi}{2}$ ($x_n$ is the ratio of the value of the angle $\alpha_n$ to the value of the right angle). From (3) it is clear that $x_n$ is obtained from $x_0$ by $n$-fold applicable mapping

$$ x \rightarrow f(x) = |2x - 1|, x \in [0, 1], $$

Fig. 7.

⟦folio 51⟧

Comment. We calculated the polynomial $x^{1000}$ using method (2). However, there are polynomials for which neither method (1) nor method (2) is the best. For example, the polynomial $x^{170}$ can be calculated in 9 multiplications (find such a way yourself!), although $\langle 170 \rangle_2 = 10 \cdot 101 \cdot 010$, so $E(170) = H(170) = 4$, $[\log_2 170] = 7$; with method (1) you need 10 multiplications, and with method (2) - 11 multiplications and one division.

E. G. Belaya

F243. Why, in bright light, can those who use not very strong glasses read me without errors?

Why, in order to simultaneously form two objects, one of which is further away from the other, and obtain a sharp image of the object on the form, the total diameter of the object's aperture (lens diameter) is reduced?

The sharp image produced by the lens of an imperfect eye is obtained not on the retina, but in front of it, if the person is nearsighted, or behind it, if the person is farsighted. In both cases, the image of each point on the retina of the eye is obtained in the form of a molten round spot, the diameter of which depends on the diameter of the pupil and on the degree of myopia (or farsightedness) of the person (Fig. 9). The smaller the diameter of the pupil, the narrower the beam of rays that creates the image of a point, the smaller the beam of rays that creates the image on the retina. In bright light, the diameter of the pupil decreases, and the image of beech trees for people wearing not very strong glasses appears slightly blurred. Therefore, they can read without errors. For those who use strong windows, the image of the beeches is far from the retina, and despite the small diameter of the pupil, the image of the beeches turns out to be very blurred, so it is still impossible to read the text without errors.

Similarly, an increase in depth of field (that is, the area that

Fig. 10.

turns out sharp on photographic film) by reducing the diameter of the object's hole. Indeed, empty we want to simultaneously form two points located at some distance from each other (Fig. 10). If the apparatus is formed on some object between these two points (the lens gives a sharp image of this object on the photographic film), then the image of the point on the photographic film turns out to be blurry, but the diameter of each of the spots - depicted by the dots - depends on the diameter of the object's hole, decreasing as this diameter decreases.

F244. Attached to two points are chains of length l and the ends of two rods, the sum of whose length may be equal to l, and the free ends are hinged. Whose chain of softness are we below - the chain or the rods?

Pull one of the links of the chain (Fig. 11), it can be shaped into rods. In this case, work will be done, which, very conveniently, goes to increase the potential energy of the chain, that is, to raise its center of gravity. Since the new position of the center of gravity of the chain coincides with the position of the center of gravity of the rods, it is clear that the chain of gravity of the freely hanging chain is located below the center of gravity of the rods.

F245. There is a uniformly loaded hemisphere. a) Show that the plane “covering” this hemisphere is equivalent. b) Determine the direction of the field at points of this plane.

The density of the loaded hemisphere is σ.

⟦folio 52⟧

Let's add two identical uniformly charged hemispheres with equal charge densities. In this case, we get a uniformly charged sphere, inside which the field direction, as is known, is zero. According to the principle of superposition, however, the directionality of the charge field of the sphere is equal to the sum of the directions of the charge fields of the hemispheres. Consequently, the sum $E_1 + E_2$ of the directions of the fields of charges of the hemispheres is equal to zero. This is only possible if $|E_1| = |E_2|$ and, in addition, both vectors $E_1$ and $E_2$ are directed towards the plane $\Pi$, which “covers” the hemisphere. Indeed, from symmetry it is clear that the components of the vectors $E_1$ and $E_2$, parallel to this plane, must be equal. When added, they give zero only if they themselves are equal to zero.

So, we have proven that the field direction vectors at points of the $\Pi$ plane are perpendicular to this plane. This means that when moving a charge in the $\Pi$ plane, the work does not coincide. Therefore the plane $\Pi$ is equivalent.

Now let's find the field direction at points of the $\Pi$ plane. According to the principle of superposition, the direction of the field at point $O$ is equal to the sum of the directions of the charge fields of individual sections of the hemisphere. the direction of the charge field of section $A$ is obviously equal in absolute value

$$E_A = \frac{Q_A}{R^2} = \frac{\sigma S_A}{R^2},$$

where $S_A$ is the area of ​​section $A$ (section $A$ is the directional section of the hemisphere, a soap column, that it can be considered flat, that is, its linear size is much less than the radius of the hemisphere).

 The direction of the field at point $O$ is obviously equal to the sum of the directions of the charge fields of individual sections of the hemisphere. The component $E_A$, directed to the plane of the hemisphere, is equal to $E_A$ cos $\alpha$ (see Fig. 12). Therefore we need

$$E = \sum \frac{\sigma}{R^2} S_A \cos \alpha = \frac{\sigma}{R^2} \Sigma S_A \cos \alpha.$$

Since $S_A$ cos $\alpha$ is the projection of the area of ​​the section $A$ onto the plane $\Pi$, and the sum of such projections of the areas of all sections of the hemisphere is obviously equal to the area of ​​the plane $\Pi$, that is, $\pi R^2$, then

$$E = \frac{\sigma}{R^2} \pi R^2 = \pi \sigma.$$

We found the directionality at the center of the $\Pi$ plane. It is not difficult to find the direction of the field at points of the circle, which is the intersection of the plane $\Pi$ and the hemisphere. Since the surface of the hemisphere is equivalent, the confluence lines at any point of the hemisphere must be perpedicular to the hemisphere. On the other hand, at points $C$ and $B$ must be perpedicular to the plane $\Pi$. However, both are possible only if the direction of the field at these points is zero.

Finding the direction of the field created by the charge of the hemisphere at other points of the plane requires complex calculations. This field is not unsuitable. Obviously, it has symmetry with respect to the point $O$ and at each point of the plane depends on the distance to this point from the center $O$.

F246. A tellochosed vessel with a volume of 2 V is divided in half by a monk partition. In one polygon of the vessel there is a monatomic gas with a temperature of $T_1$ and a pressure of $p_1$, in the other polygon there is another monatomic gas with a pressure of $p_2$ and a temperature of $T_2$. Find the set temperature of the gas mixture after mine, as the partition was removed.

Let's use the law of conservation of energy. Since the vessel is thermally conductive, the total energy of the gases cannot change when they move. The internal energy $n$ moles of an ideal monatomic gas is equal to the kinetic energy of the chaotic movement of gas molecules:

$$U = \frac{3}{2} nRT,$$

where $T$ is the absolute gas temperature, $R$ is the universal gas constant. This means that until the partition was removed, the internal energy of the system was equal to

$$U = \frac{3}{2} n_1RT_1 + \frac{2}{3} n_2RT_2$$

($n_1$ is the number of moles of the first gas, $n_2$ is the number of moles of the second gas). After the partition was removed, the temperature of the gases became $\frac{3}{2} n_1RT$ and $\frac{3}{2} n_2RT$. According to the law of conservation of energy

$$\frac{3}{2} n_1RT_1 + \frac{3}{2} n_2RT_2 = \frac{3}{2} n_1RT + \frac{3}{2} n_2RT.$$

⟦folio 53⟧

Fig. 13.

From here

$$T = \frac{n_1 T_1 + n_2 T_2}{n_1 + n_2} = \frac{\frac{n_1}{n_2} T_1 + T_2}{\frac{n_1}{n_2} + 1}.$$

This expression includes the relation $n_1/n_2$. To find it, we write the equation of gas state for both gases before mixing:

$$p_1 V = n_1 R T_1; \quad p_2 V = n_2 R T_2.$$

Dividing the first equality by the second, we get

$$\frac{n_1}{n_2} = \frac{p_1}{p_2} \frac{T_2}{T_1}.$$

Hence,

$$T = \frac{T_1 T_2 (p_1 + p_2)}{p_1 T_2 + p_2 T_1}.$$

F247. The model of a molecule of carbon dioxide CO₂ is a ball, connected by springs and located in an equilibrium position along one straight line. Such a molecule can perform linear vibrations of two types: a) or b) at Fig. 13. Name of frequencies of empirical vibrations.

Let us denote the stiffness of the springs of the molecule model as $k$, the mass of the balls as oxygen atoms as $M$, and the mass of the ball as carbon atoms as $m$ ($m/M = 12/16$).

Performing vibrations of the $a$ type), both oxygen atoms vibrate synchronously relative to the stationary carbon atom. This is due to the fact that, due to the symmetry of the vibrations of oxygen atoms, forces of equal absolute magnitude and opposite directions act on a carbon atom at any moment from both sides, which “balance” each other. Therefore, in case a) oxygen atoms perform free vibrations, the period of which is equal to

$$T_a = 2\pi \sqrt{\frac{M}{k}}.$$

During vibrations of type $\delta$), the effects on the carbon atom are equal in absolute magnitude, but they are directed in the same direction. If a ball - a carbon atom is divided into two equal parts, then it is clear that they will vibrate as one whole: they are always acted upon by equal forces and, therefore, the ball halves will have the same accelerations, velocities and coordinates at any moment. The vibration frequency of a CO₂ molecule is equal to the vibration frequency of a system consisting of an oxygen atom and half a carbon atom. Thus, the problem comes down to determining the period of oscillations of the balls of mass $M$ and $m/2$ connected by a spring. Such balls oscillate around the fixed center of mass of the system. If the length of the spring in the uncrucifixed state is equal to $l$, then the center of mass of the system is at a distance $l \frac{m}{m+2M}$ from the ball of mass $M$. Therefore, we can assume that a ball of mass $M$ (oxygen atom) oscillates relative to the center of mass on a spring of length

$$l_1 = l \frac{m}{m+2M}.$$

The stiffness of part of the spring is greater than the stiffness of the whole spring. Since the stiffness is inversely proportional to the relative part to the length of the whole spring, then the stiffness of the part of the spring

$$k_1 = k \frac{l}{l_1} = k \frac{m+2M}{m}.$$

The period of oscillation of a ball of mass $M$ on a stiffness spring $k_1$ is equal to

$$T_\delta = 2\pi \sqrt{\frac{M}{k_1}} = 2\pi \sqrt{\frac{mM}{k(m+2M)}}.$$

A

$$\frac{T_\delta}{T_a} = \sqrt{\frac{m+2M}{m}} = \sqrt{1 + \frac{2M}{m}}.$$

Since $\frac{M}{m} = \frac{16}{12} = \frac{4}{3}$, from

$$\frac{T_\delta}{T_a} = \sqrt{1 + \frac{8}{3}} = \sqrt{\frac{11}{3}}.$$

Therefore, the frequency ratio

$$\frac{v_\delta}{v_a} = \sqrt{\frac{3}{11}}.$$

I. Sh. Slovodechkiy
