---
id: 1977-9-resheniya-zadach-m421-m425-f432-f437-108fc12c
issue: kvant_1977_9
year: 1977
number: "9"
title: Solutions to problems M421—M425; F432—F437
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 37
page_last: 44
page_labels: 35, 37, 38, 39, 41, 42
tag: BD25
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1b7b1f5b7e764defce25ec26b1d4f70fa0b2c4850c5aa6ac7910b3ee0cbb790f
prompt_sha256: draft-1
translated_from: content/ru/1977/09/articles/10_resheniya-zadach-m421-m425-f432-f437-108fc12c.md
source_content_sha256: d80527acd9cb4e50bab632a4f4893d3970f8d9cb1ba40c020f686036149d9b52
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 35⟧

Problem solutions

M421—M425; F432—F437

M421. For what natural m and n (m < n) can the noncomoral cells of an infinite sheet of checkered paper be painted black Mak so that any rectangle of size m × n contains exactly one black cell?

Fig. 1.

Fig. 2.

(Fig. 6). The gas passing through the walls of the pipe is pumped out of vessel C. Estimate the ratio of the concentrations of $^{235}$UF$_6$ and $^{238}$UF$_6$ in the pumped gas. The relative atomic mass of fluorine is 19. (10cl.)

F477. A rubber stab of mass M lies on a smooth horizontal plane. Puncture a little distance so that it retains the shape of a circle and its center remains motionless. After this, the stab is released. Describe the further behavior of the ring. The elasticity coefficient of the rubber band is equal to k.

A. Abrahamyan

Problem solutions

M421—M425; F432—F437

Let us prove that the required coloring of the checkered plane for the pair (m, n), m < n, exists if and only if n is divisible by m.

If the coloring of the plane is such that in any row (vertical and horizontal) every k-th cell is painted black (as in figure 1, where k=3), then in any 1×k rectangle there will be exactly one black cell. From such a periodic coloring for the pair (1, k) it is not difficult to obtain a periodic coloring for the pair (m, km): you need to refine the grid m times and in each black cell of the old (large) lattice leave only one black cell, say, the lower left cell (figure 2 is obtained from figure 1 and with exactly this example; here k=3, m=2). So, we have shown how to construct the required coloring for the pair (m, n) if n is divisible by m.

Let us now assume that for the pair (m, n), where n is not divisible by m (n > m > 1), the required coloring has been constructed, and we arrive at a contradiction.

Let's look at two services.

1) Let n ≤ 2m – 1. If two vertical m × n rectangles share a corner black cell, as shown in figure 3, then their union cannot contain any more black cells. But it can contain a horizontal (red) n × m rectangle that does not contain a black cell. Contradiction.

2) Let n > 2m – 1. Let us first prove that if K is a black cell, then the nth cell in the same row (counting from K) is also black. Consider two vertical m × n rectangles with a common bottom corner cell K and two more rectangles obtained from them by moving one cell up (blue and yellow at figure 4). Since they must each have one black cell, either one of the yellow cells and one of the blue ones, or one green cell must be painted in black. But the first possibility is excluded, since a horizontal red rectangle cannot contain two black cells; This means that the green cell needs to be painted black.

Consider now an n×n square with a black square in the lower left corner. If n = mk + r, where 0 < r < m, then the square can be cut into k horizontal rectangles n×m and the “remainder” is a rectangle n×r (Fig. 5).

⟦folio 37⟧

M424. Through the same vertex of the metrahedron a plane is drawn containing the center of the circle circumscribed about the opposite face and perpendicular to the opposite face. Let us prove that these four planes intersect at one point.

Fig. 7.

M425. Is there a nagural $N$ such that any rational number between zero and one can be represented as the sum of $N$ inverses of the nagurals?

Let $S$ be one of the vertices of the tetrahedron, $SH$ its height, $O_1$ the center of a circle circumscribed around the face opposite to vertex $S$. The plane passing through the vertex $S$ contains the height $SH$ and the segment $SO_1$ (Fig. 7). Let us draw through the point $O_1$ a line parallel to $SH$; it is obvious that it belongs to our plane. On the other hand, it is clear that this line passes through the center of the sphere circumscribed around the plane. Therefore, all four planes containing the center of the sphere circumscribed around the tetrahedron intersect at one point.

A. Yagubyants

Let us denote by $A_n$ the set of numbers that can be represented as the sum of no more than $n$ terms that are the inverses of nagurals. Then $A_{n+1} = \{ \alpha + 1/q \}, \alpha \in A_n, q \in \mathbb{N}$ (nagural); it is clear that $A_{n+1} \supset A_n$.

We will now prove that $A_n$ (for no $n$) does not contain all rational numbers in the interval ] 0; 1 [for this we prove by induction on $n$ a stronger statement:

I. In any segment $[a; b] \subset ]0; 1[$ there is an entire segment $[c; d]$ that does not intersect with $A_n$*).

For $n = 1$ this is obvious. Let us prove this statement for some $n$, assuming that it is proven for $n - 1$.

Let the segment $[a; b] \subset ]0; 1[$ be given. Let us choose a segment $[c_0; d_1] \subset [a; b]$ that does not intersect with $A_{n-1}$, and take a number $m \in \mathbb{N}$ such that $d_1 - c_0 > 2/m$ (i.e. $2/(d_1 - c_0) < m$. Then none of the numbers of the form $\alpha + 1/q$, where $\alpha \in A_{n-1}, q \geq m$, lies in the right half $[c_1; d_1]$ of the segment $[c_0; d_1]$: if $\alpha \leq c_0$, then $\alpha + 1/q < (c_0 + d_1)/2 = c_1$. We can further choose $[c_1; d_1] \supset [c_2; d_2] \supset [c_3; d_3] \supset \dots \supset [c_m; d_m]$ so that $[c_k - 1/k; d_k - 1/k]$ does not intersect with $A_{n-1}(k = 1, 2, \dots, m)$. Thus, the interval $[c_2; d_2]$ will not contain numbers of the form $\alpha + 1/2$ and $\alpha + 1/q$, where $\alpha \in A_{n-1}, q \geq m$; the interval $[c_3; d_3]$ does not contain numbers of the form $\alpha + 1/2$, $\alpha + 1/3$ and $\alpha + 1/q$ for $q \geq m$, $\alpha \in A_{n-1}, q \in \mathbb{N}$. That is, the segment $[c_m; d_m]$ does not intersect with $A_n$, which is what we needed to prove.

Thus, the answer to the question posed in problem M425 is negative: there is no such natural number $N$.

In the solution added by readers, a number of properties of the set $A_n$ were noticed; some of them are stronger than what I proved above.

*) As stated, the set $A_n$ is not flat.

⟦folio 38⟧

Other properties of $A_n$ that also distinguish it from the set of all rational numbers:

II. $A_n$ does not contain any non-finite increasing sequence.

This property is equivalent to these two.

III. For each point $x \in A_n$ there is a point close to it on the left.

IV. Each subset $A_n$ contains the most number.

V. The limit of a sequence of distinct numbers containing $A_n$ can only be the number containing $A_{n-1}$ or 0 (and not any real number on the interval, as would be the case if $A_n$ contained all the rational numbers of this interval!)

The proof of this last property has been particularly studied.

Let $x_m = \frac{1}{q_1^{(m)}} + \dots + \frac{1}{q_n^{(m)}}$, $q_1^{(m)} \leq q_2^{(m)} \leq \dots \leq q_n^{(m)}$, $m = 1, 2, \dots$ be some sequence of numbers from $A_n$ tending to the limit $a$. We can choose from the sequence $q_1^{(m)}$ (there are no numbers!) either increasing under the sequence, or “stationary”, in which the same number is repeated; then (throwing out all the remaining $x_m$) perform the same operation for $q_2^{(m)}$, etc. Since all $x_m$ are different, some sequence $q_1^{(m)}$ must increase and tend to infinity. Thus, we get, let's move on to the sequence, such $x_m$, that for some $r < n$

$q_1^{(i)} = q_2^{(i)} = q_3^{(i)} = \dots = q_i$ at $i \leq r$ and $q_i \rightarrow \infty$.

Then the number $a = \lim_{m \to \infty} x_m = \frac{1}{q_1} + \frac{1}{q_2} + \dots + \frac{1}{q_r}$ becomes zero if we can choose an increasing one from the sequence $q_1^{(m)}$.

On the other hand, it is very unlikely that every point $A_{n-1}$ will indeed be a limit point $A_n$.

The reader can easily prove properties II, III, IV of the set $A_n$. Of course, from V it is easy to derive both the statement of the problem (by induction) and the properties of I.

N. Vasiliev

F432. The glass ball has the ability to create a spherical bubble. It is necessary to find a way to measure the diameter of the bubble. The ball should remain intact. The method should be described as little as possible.

Fig. 8.

First of all, let’s find out at what diameter of the ball the center of the air bubble is located. To do this, place the ball on a horizontal surface and wait until it stops swinging. In the stable equilibrium position of the ball, the center of the bubble lies on the vertical diameter, above the center of the ball (Fig. 8).

Then we find the position of the center of gravity of the ball with the bubble. Let's place the ball on an inclined plane and slowly increase the angle of inclination of the plane to the horizon. In this case, the ball will rotate around a horizontal axis passing through its geometric center, so that at any moment the center of gravity of the ball is on the vertical passing through the point of contact of the ball with the plane. The ball begins to roll (with a sufficiently large coefficient of sliding friction between the ball and the plane) when the center of gravity is the most right of all its possible positions (Fig. 9). This allows you to determine the position of the center of gravity of a ball with an air bubble: it is separated from the geometric center of the ball by a distance

$$l = R \sin \alpha,$$

where $R$ is the radius of the ball, $\alpha$ is the angle of inclination of the plane to the horizon at which the ball begins to roll.

Telerc will indefinitely determine the size of the bubble and its position inside the glass ball. Suppose we filled a plane with glass, from which

⟦folio 39⟧

the ball was made. The center of gravity of the displacement is at the geometric center of the ball. This means that

$$\frac{4}{3} \pi r^3 \rho a = \frac{4}{3} \pi (R^3 - r^3) \rho l.$$

Here $r$ is the radius of the air bubble (cavity), $\rho$ is the density of the glass, $a$ is the distance from the center of the bubble to the center of the ball (Fig. 10). Weighing a ball in air and water (with a known density $\rho_0$), we can write two more equations:

$$\frac{4}{3} \pi (R^3 - r^3) \rho |\vec{g}| = P_1,$$

$$\frac{4}{3} \pi (R^3 - r^3) \rho |\vec{g}| - \frac{4}{3} \pi R^3 \rho_0 |\vec{g}| = P_2.$$

Having solved the system of three equations with the third unknown, we find the radius of the bubble $r$ and its position $a$.

Another method of measuring $r$ is possible - optical. It is enough to place a ball in a liquid with a refractive index equal to the refractive index of glass for the ball to become invisible in this liquid. By looking at the path of the rays, for example, from the exact source, you can find $r$ (check this yourself).

Of course, many other methods can be proposed. Therefore, we will definitely return to this task once again when we read all the letters from our readers.

F433. Two identical plano-convex lenses with a focal length of $F = 20$ cm are each located at a distance of $l = 30$ cm from each other. The optical axes of the lenses coincide, the lenses face each other with their flat sides. Where will the image of the source be located, located at a distance of $d = 40$ cm from the left lens, if we look between the lenses and fill it with glass with a refractive index maximum the same as that of the lenses?

Let us denote by $f$ the distance from the left lens to the source image, which is formed during refraction on the convex spherical surface of the left lens. This distance is related to the distance $d$ from the source to the left lens by the correspondence

$$\frac{1}{d} + \frac{n}{f} = (n - 1) \frac{1}{R},$$

where $n$ is the refractive index of the glass, $R$ is the radius of the spherical surface of the lens.

A similar equality can be written for refraction on the convex surface of the right lens:

$$\frac{n}{d'} + \frac{1}{f'} = (n - 1) \frac{1}{R}.$$

Here $d^1 = l - f$ is the distance from the first image, which is the “source” for the second image, to the right lens, and $f'$ is the desired distance from the right lens to the image given to the system. In addition, for each lens separately, compliance is carried out

$$(n - 1) \frac{1}{R} = \frac{1}{F}.$$

Solving all three equations together, we find $f'$:

$$f' = \frac{F \left[ l (d - F) - ndF \right]}{(d - F) (l - nF) - ndF}.$$

Putting $n = 1,5$, we get $f' = 10$ cm.

F434. What amount of menloma is released at resistance $R$ when equilibrium is established after washing the key $K$ (Fig. 11), if the capacitor was pre-charged to the difference

⟦folio 41⟧

There will be no oscillations of the coupling if, when moving the coupling from the equilibrium position, its acceleration $\vec{a}$ relative to the rod turns out to be in the direction from the axis of rotation, that is

$$\frac{2k}{m} - \omega^2 < 0,$$

or $\omega > \sqrt{\frac{2k}{m}} = 10$ rad/s.

F436. The density $\rho$ of a gas consisting of a mixture of zeilium and argon, at a pressure $p = 152$ kN/$m^2$ and a temperature $T = 300$ K, is 2.0 kk/m³. How many zeilium atoms are contained in 1 cm³ of gas mixture?

In order to find the number of helium molecules (atoms) $N_1$ in a volume $V = 10^{-6}$ m³, it is necessary to determine the ratio of the mass of helium $m_1$ to its molar mass $\mu_1 = 4 \cdot 10^{-3}$ kg/mol:

$$N_1 = \frac{m_1}{\mu_1} N_A.$$

(1)

Let us write down the equations of gas state for helium and argon:

$$p_1 V = \frac{m_1}{\mu_1} RT, \quad p_2 V = \frac{m_2}{\mu_2} RT$$

($p_1$ is the helium pressure, $p_2$ is the argon pressure, $m_2$ is the mass of argon, $\mu_2 = 40 \cdot 10^{-3}$ kg/mol is its molar mass). According to Dalton's law, the pressure of a gas mixture is $p = p_1 + p_2$, that is

$$p = \left( \frac{m_1}{\mu_1} + \frac{m_2}{\mu_2} \right) \frac{RT}{V}.$$

(2)

The density $\rho$ of the mixture is equal to the sum of the densities of helium and argon:

$$\rho = \rho_1 + \rho_2 = \frac{m_1}{V} + \frac{m_2}{V}.$$

(3)

From equalities (2) and (3) we find the relation $\frac{m_1}{\mu_1}$, substitute it into expression (1) and obtain

$$N_1 = N_A V \frac{\rho \mu_2 - \rho RT}{RT (\mu_2 - \mu_1)} \approx 4 \cdot 10^{15} \text{ m}^{-3} = 4 \cdot 10^9 \text{ cm}^{-3}.$$

F437. A wire frame in the shape of a triangle with an angle $\alpha = 30^\circ$ is placed in a vertical plane 马克, as shown in figure 14. By wiring, the friction-free sliding of two weights with a different thread is carried out with masses $m_1 = 0,1$ kk and $m_2 = 0,3$ kk. What is the tension in the thread and the angle $\beta$ in the equilibrium position of the weights?

Is this equilibrium stable?

figure 14 shows all the forces acting on the weights. The forces $\vec{T}_1$ and $\vec{T}_2$ of thread tension are equal in the abscissa externally and oppositely directed: $\vec{T}_1 = -\vec{T}_2$ and $|\vec{T}_1| = |\vec{T}_2| = T$. The reaction forces $\vec{N}_1$ and $\vec{N}_2$ are perpendicular to the sides of the frame and, therefore, form an angle $90^\circ$ with each other. The gravity forces $m_1\vec{g}$ and $m_2\vec{g}$, as always, are directed vertically.

Since the system of weights connected by a thread is in equilibrium, then

$$\vec{N}_1 + \vec{N}_2 + \vec{T}_1 + \vec{T}_2 + m_1\vec{g} + m_2\vec{g} = 0,$$

or

$$\vec{N}_1 + \vec{N}_2 + m_1\vec{g} + m_2\vec{g} = 0.$$

This means that the vectors $\vec{N}_1, \vec{N}_2$ and $m_1\vec{g} + m_2\vec{g}$ form a triangle (Fig. 15), and this triangle is a straight triangle: $\widehat{BAC} = 90^\circ$. It is in equilibrium from weights. Hence,

$$m_1\vec{g} + \vec{N}_1 + \vec{T}_1 = 0, \quad \vec{N}_2 + m_2\vec{g} + \vec{T}_2 = 0.$$

⟦folio 42⟧

From these equalities it follows that the vector $\vec{T}_1$ connects the vertex $A$ of the triangle $ABC$ with the point $E$, and the vector $\vec{T}_2$ connects the point $E$ with the point $A$.

In the triangle $AEC$ there are $\widehat{ACE} = \alpha$ and $\widehat{CAE} = 90^\circ - \beta$, and in the triangle $ABE$ there are $\widehat{ABE} = 90^\circ - \alpha$ and $\widehat{BAE} = \beta$. According to the sine theorem

$$\frac{T}{\sin \alpha} = \frac{m_1 |\vec{g}|}{\sin (90^\circ - \beta)} = \frac{m_1 |\vec{g}|}{\cos \beta}, \quad \frac{m_2 |\vec{g}|}{\sin \beta} = \frac{T}{\sin (90^\circ - \alpha)} = \frac{T}{\cos \alpha}.$$

Solving these equations together, we find

$$tg \beta = \frac{m_2}{m_1} \text{ctg} \alpha = 3\sqrt{3}, \quad \beta \approx 79^\circ;$$

$$T = m_1 |\vec{g}| \frac{\sin \alpha}{\cos \beta} \approx 2.7 \text{ H.}$$

Now let's find out whether the found equilibrium position is stable. The equilibrium position is stable if the potential energy of the system in this position is minimal, that is, the center of gravity of the load system is in the lowest position. In order to find out whether this condition is satisfied, we find the coordinate of the center of gravity of the system.

Let us denote the length of the side $DK$ of the wire triangle (Fig. 16) by $a$, and the length of the thread by $l$. The center of gravity of the system (point $O$) divides the length of the thread in the ratio $\frac{m_2}{m_1}$.

Therefore, it is located at a distance $b = \frac{m_2}{m_1 + m_2} l$ from the left weight. From figure 16 it is clear that $y_0 = (a - l \cos \beta) \sin \alpha - b \sin (\beta - \alpha) = a \sin \alpha - l (\cos \beta \sin \alpha) + \frac{m_2}{m_1 + m_2} \sin (\beta - \alpha))$.

This expression is minimum when the maximum expression is

$$y_1 = \cos \beta \sin \alpha + \frac{m_2}{m_1 + m_2} \sin (\beta - \alpha).$$

Let's transform the expression (*):

$$y_1 = \cos \beta \sin \alpha + \frac{m_2}{m_1 + m_2} (\sin \beta \cos \alpha - \cos \beta \sin \alpha) = \frac{m_2}{m_1 + m_2} \sin \beta \cos \alpha + \frac{m_1}{m_1 + m_2} \cos \beta \sin \alpha = \sin (\beta + \varphi),$$

where $\sin \varphi = \frac{m_1}{m_1 + m_2} \sin \alpha$, $\cos \varphi = \frac{m_2}{m_1 + m_2} \cos \alpha$ and $tg \varphi = \frac{m_1}{m_2} \text{tg} \alpha$.

Obviously, expression (*) is maximum at

$$\beta + \varphi = \frac{\pi}{2},$$ or $tg \beta = \text{ctg} \varphi = \frac{m_2}{m_1} \text{ctg} \alpha$.

Consequently, the found equilibrium position is stable. Anyone who has to differentiate could this value $\beta$ from the extremum (maximum) condition of the expression (*).

I. Slovodechkiy
