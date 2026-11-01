---
id: 1981-1-resheniya-zadach-m611-m615-f618-f622-37c617a3
issue: kvant_1981_1
year: 1981
number: "1"
title: Solutions to problems M611—M615; F618—F622
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 30
page_last: 34
page_labels: 28, 29, 31, 32
tag: JXXY
lang: en
source: kvant_digital
extraction: vision
content_sha256: 4382eee4f8e83136ed7a7d84737a4f0b5e2cc4d2a6cd8487fad1380f898d048d
prompt_sha256: draft-1
translated_from: content/ru/1981/01/articles/09_resheniya-zadach-m611-m615-f618-f622-37c617a3.md
source_content_sha256: f3ec660cbfca09844f8de1c10b534533b46637f60ba477db7888118c5b1c4423
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 28⟧

Problem solutions
M611—M615; F618—F622

M611. On the chord AB of a circle with center O, take an arbitrary point M. Through points A, M and O, draw a circle intersecting the first circle at points A and C. Prove that $|MB| = |MC|$.

Let $\widehat{ABC} = \beta$. Then $\widehat{AOC} = 2\beta$, since $\widehat{ABC}$ and $\widehat{AOC}$ are inscribed and, respectively, central angles based on the same arc AC of the given (black - see figure) circle.

On the other hand, $\widehat{AMC}$ and $\widehat{AOC}$ are inscribed angles subtended by the same arc AC of the constructed (blue) circle (located in the non-black circle). Therefore $\widehat{AMC} = 2\beta$.

$AMC$ is the external angle of triangle MBC. So, $\widehat{MCB} = \widehat{AMC} - \widehat{MBC} = \beta$. From $\widehat{MCB} = \widehat{AMC}$ follows $|MB| = |MC|$.

This solution is suitable (unlike some solutions sent by readers) for any location of the point M on [AB], except for the case when M coincides with the midpoint of the chord AB. In this last case, the blue circle touches the black circle, points A and C merge and the equality $|MB| = |MC|$ turns into equality $|MB| = |MA|$.

Think about whether the proven statement will remain true if M is taken on the continuation of the segment AB.

N. Vasiliev

M612. The increasing sequence of natural numbers ($a_n$) is such that $a_{n+1} \leq 10a_n$. Prove that if all the numbers $a_n$ are written side by side (without spaces or commas), then the resulting sequence of numbers will not be periodic.

Let us assume that we have a periodic sequence of digits and that the length of the period (the number of digits in it) is equal to T. It is easy to see that the number $a_{n+1}$ can be “longer” than the number $a_n$ by no more than one digit (and, of course, not shorter). Since the sequence ($a_n$) is returning, it contains numbers of any length greater than the length of $a_1$. Therefore, in it there is an incorrect number $a_m$, the length of which $kT$ is a multiple of the period (see figure). The first $kT$ digits of $a_{m+1}$ must match the digits of $a_m$, so $a_{m+1}$ has one more digit ($a_{m+1} > a_m$), and it must have a zero ($10a_m \geq a_{m+1}$). But then the first digit in the entry $a_m$ is zero, which, of course, is impossible.

Note that if the condition $a_{n+1} \leq 10a_n$ is replaced by a slightly weaker one: $a_{n+1} \leq 10a_n + 1$ or $a_{n+1} \leq (10 + \varepsilon)a_n$, where $\varepsilon$ is an arbitrary positive number, then the resulting sequence of digits may turn out to be periodic.

I. Klumova

M613. On the sides of triangle ABC, similar triangles ADB, BEC and CFA ($|AD|/|DB| = = |BE|/|EC| = = |CF|/|FA| = k$, $ADB = BEC = CFA = \alpha$) are constructed to the outside. Prove that a) the midpoints of the segments AC, DC, BC and EF are the vertices of the parallelogram; b) this parallelogram has two integers called a, and the side length ratio is equal to k.

Let us denote by $\vec{a}'$ the vector obtained from the vector $\vec{a}$ by rotation by angle a counterclockwise. (It is known that $(k\vec{a})' = k\vec{a}'$ for any number $k$, $(\vec{a} + \vec{b})' = \vec{a}' + \vec{b}'$, and in general, for any number of terms, $(\vec{a} + \vec{b} + \dots + \vec{c})' = \vec{a}' + \vec{b}' + \dots + \vec{c}'$.) Let us introduce the vectors $\vec{DA} = \vec{a}$, $\vec{EB} = \vec{b}$, $\vec{FC} = \vec{c}$ (see figure).

By condition $\vec{DB} = \frac{1}{k}\vec{a}'$, $\vec{EC} = \frac{1}{k}\vec{b}'$, $\vec{FA} = \frac{1}{k}\vec{c}'$.

Since $\vec{AD} + \vec{DB} + \vec{BE} + \vec{EC} + \vec{FC} + \vec{FA} = 0$, $\vec{a} + \frac{1}{k}\vec{a}' - \vec{b} + \frac{1}{k}\vec{b}' - \vec{c} + \frac{1}{k}\vec{c}' = 0$, that is, $\vec{a} + \vec{b} + \vec{c} = \frac{\vec{a}' + \vec{b}' + \vec{c}'}{k} = \frac{1}{k} (\vec{a} + \vec{b} + \vec{c})'$.

Denoting $\vec{a} + \vec{b} + \vec{c}$ by $\vec{u}$, we obtain $\vec{u} - \frac{1}{k}\vec{u}' = 0$. (*)

Since the vectors $\vec{u}$ and $\vec{u}'$ are non-collinear ($\alpha \neq 0$ and $\alpha \neq 2\pi$), equality (*) is possible when $\vec{u} = \vec{0}$. Therefore $\vec{a} + \vec{b} + \vec{c} = \vec{0}$.

⟦folio 29⟧

Further, since $Q$ is the middle of $[DC]$ and $P$ is the middle of $[AC]$ (see figure), $\overrightarrow{QP} = \frac{1}{2} \vec{a}$. Same as $\overrightarrow{QR} = \frac{1}{2} \overrightarrow{DB}$. From $(PQ) \parallel (AD)$ and $(QR) \parallel (BD)$ it follows $PQR = \alpha$.

Finally,

$$\overrightarrow{RS} = \overrightarrow{RC} + \overrightarrow{CF} + \overrightarrow{FS} = \frac{1}{2} \overrightarrow{BC} - \vec{c} + \frac{1}{2} \overrightarrow{FE} =$$

$$= \frac{1}{2} \left( -\vec{b} + \frac{1}{k} \vec{b}' \right) - \vec{c} + \frac{1}{2} \left( \vec{c} - \frac{1}{k} \vec{b}' \right) = -\frac{\vec{b} + \vec{c}}{2} = \frac{\vec{a}}{2} = \overrightarrow{QP}$$

Thus, the quadrilateral $PQRS$ is a parallelogram with angle $PQR$ equal to $\alpha$ and side length ratio $|PQ|/|RQ| = |AD|/|DB| = k$.

L. Kuptsov

**M614. For each natural number $n$, let $S(n)$ denote the sum of the digits of all natural numbers from 1 to $n$ (in decimal notation):

$S(1) = 1, S(2) = 3, S(3) = 6, \dots, S(9) = 45, S(10) = 46, S(11) = 48, S(12) = 51, \dots$

a) Find $S(100)$.

b) Prove that $S(10^k - 1) = 45k \cdot 10^{k-1}(*)$ for all $k = 1, 2, \dots$

c) Prove that for two natural numbers $\overrightarrow{ab}$

$$S(\overrightarrow{ab}) = 5a^2 + ab + 41a + b(b+1)/2.$$

f) Find a similar formula for three-digit numbers.

e) Calculate the sum $S(1980)$.

Let us derive a general formula for $S(\overrightarrow{a_k a_{k-1} \dots a_1})$. Let's represent this sum in the form of $a_k + 1$ terms, separately calculating it for numbers with the $k$th digit 0, 1, ..., $a_k - 1$ and $a_k$, respectively.

The first $a_k$ terms are unambiguous: in them, no restrictions are imposed on the digits in smaller digits than $k$. If the $k$th digit is equal to $b$ (and $0 \leq b \leq a_k - 1$), then the sum of the digits of all such numbers is equal to $10^{k-1} \cdot b + S(10^{k-1} - 1)$ (the contribution from the $k$th digit and from the remaining digits, respectively). The $(a_k + 1)$th term (when the $k$th digit contains the digit $a_k$) looks like this: $a_k \cdot (\overrightarrow{a_{k-1} \dots a_1} + 1) + S(\overrightarrow{a_{k-1} \dots a_1})$ (again the contribution from the $k$th digit and the remaining digits, respectively).

Okfinally for $S(\overrightarrow{a_k \dots a_1})$ we get

$$S(\overrightarrow{a_k \dots a_1}) = a_k \cdot (\overrightarrow{a_{k-1} \dots a_1} + 1) + S(\overrightarrow{a_{k-1} \dots a_1}) +$$

$$+ 10^{k-1}(0 + 1 + \dots + (a_k - 1)) + a_k \cdot S(10^{k-1} - 1) =$$

$$= a_k \cdot (\overrightarrow{a_{k-1} \dots a_1} + 1) + S(\overrightarrow{a_{k-1} \dots a_1}) + 5 \cdot 10^{k-2}a_k(a_k - 1) +$$

$$+ a_k \cdot S(10^{k-1} - 1).$$

It remains to calculate $S(10^{k-1} - 1)$. If we use the formula already derived, we get

$$S(10^{k-1} - 1) = 9 \cdot 10^{k-2} + S(10^{k-2} - 1) + 5 \cdot 10^{k-3} \cdot 9 \cdot 8 +$$

$$+ 9 \cdot S(10^{k-2} - 1) = 10 \cdot S(10^{k-2} - 1) + 45 \cdot 10^{k-2}.$$

If we consider it already proven that

$$S(10^{k-2} - 1) = 45(k - 2) \cdot 10^{k-3},$$

we get the formula

$$S(10^{k-1} - 1) = 45(k - 1) \cdot 10^{k-2},$$

It is sufficient to prove (*) (see item 6) the conditions for $k = 1$.

We have $S(10 - 1) = 45 \cdot 1 \cdot 10^\circ = 45$ - formula (*) is correct. So, $S(10^k - 1) = 45k \cdot 10^{k-1}$ - we have proven statement 6) of the problem.

For two values ​​this gives

$$S(\overrightarrow{a_2 a_1}) = a_2(a_1 + 1) + S(a_1) + 5a_2(a_2 - 1) +$$

$$+ 45a_2 = a_2(5a_2 + a_1 + 41) + \frac{a_1(a_1 + 1)}{2} -$$

- see paragraph in the task.

For three digit numbers

$$S(\overrightarrow{a_3 a_2 a_1}) = a_3((\overrightarrow{a_2 a_1} + 1) + 900 + 50(a_3 - 1)) + S(\overrightarrow{a_2 a_1}) =$$

$$= a_3(50a_3 + \overrightarrow{a_2 a_1} + 851) + a_2(5a_2 + a_1 + 41) + \frac{a_1(a_1 + 1)}{2}.$$

(In particular, $S(100) = 901$).

Finally,

$$S(1980) = 980 + 1 + 45 \cdot 3 \cdot 10^2 + S(980) =$$

$$= 13500 + 981 + 9(450 + 80 + 851) + 8(40 + 41) = 27558.$$

I. Klumova

⟦folio 31⟧

we say $F = 10$ cm. The point was mixed at a distance of $h = 5$ cm in a plane perpendicular to the main optical axis. How much and where should the lens be moved so that the selection of the luminous point returns to its old position?

move in the direction opposite to the direction the point is moving.

When moving point $A$ to point $A'$, the optical center of the lens must be shifted from point $O$ to point $O'$ such that points $A', B, O'$ lie on the same straight line. In the new position of the lens, its optical axis $N'N'$ should be parallel to the straight line $NN$.

From figure it is clear that the distance $x$ at which the optical center of the lens must be mixed satisfies the condition

$$\frac{x}{h} = \frac{f}{d-f} \Rightarrow x = \frac{hf}{d-f}.$$

We find the unweighted value $f$ using the diverging lens formula:

$$\frac{1}{d} - \frac{1}{f} = -\frac{1}{F} \Rightarrow f = \frac{dF}{d+F}.$$

Thus,

$$x = \frac{hF}{d} = 1,25 \text{ см.}$$

A. Izerenin, S. Manida, V. Saulit

F620. If you place an object with a mass greater than $m$ in the center of a square table, the table legs will break. Find a set of points on the table where you can place an object of mass $m/2$ without fear of breaking the table.

To prevent the table legs from breaking, the force acting on each leg should not be greater than $m/4$ (this follows from the problem conditions). Let's see what force $f_1$ acts on leg $I$ (Fig. 1) when there is a mass load $m/2$ on the table at a point with coordinates $x, y$ (point $I$ is taken as the origin).

Let $f_2, f_3, f_4$ be the forces acting on the legs $II, III, IV$, respectively. It is obvious that the action of forces $f_1$ and $f_2$ is equivalent to the action of force $f_{1-2} = f_1 + f_2$ applied at point $A$ with coordinates {0; $y$}, and the action of forces $f_3$ and $f_4$ is equivalent to the action of force $f_{3-4} = f_3 + f_4$ applied at point $B$ with coordinates { $l$; $y$} (the length of the table side is $l$). Let us write down the equilibrium conditions for the table:

$$f_{1-2} + f_{3-4} = \frac{mg}{2},$$

$$f_{1-2} x = f_{3-4} (l - x).$$

From here

$$f_1 + f_2 = f_{1-2} = \frac{mg}{2} \frac{l-x}{l}.$$

On the other hand, $f_1 y = f_2 (l - y)$, from where

$$f_1 = f_2 \frac{l-y}{y}.$$

From (1) and (2) we find

$$f_1 = \frac{mg}{2} \frac{(l-x)(l-y)}{l^2}.$$

To prevent the leg from breaking, the following conditions must be met:

$$f_1 = \frac{mg}{2} \frac{(l-x)(l-y)}{l^2} < \frac{mg}{4},$$

that is, the mass load $m/2$ can stand at a point whose coordinates are related to the relations

$$y > l \left(1 - \frac{l}{2(l-x)}\right).$$

The graph of function $y(x) = l \left(1 - \frac{l}{2(l-x)}\right)$ is shown only

⟦folio 32⟧

F621. Throw the end of the thread wound onto a spool over a star into the wall (see figure). The thread is pulled at a constant speed v. At what speed does the center of the reel move at the moment when the thread makes an angle a with the vertical? The outer radius of the coil is R, the inner radius is r.

If the thread is pulled as shown at figure, the bobbin will roll to the right, while rotating clockwise around the motion and linear speed of the rotational motion with an angular velocity ω per direction of the thread equal to v:

$$v_0 \sin \alpha - \omega r = v$$

(v₀ is the modulus of the desired speed). Due to the absence of sliding of the coil along the horizontal surface, the sum of the projections of the corresponding velocities for point C is equal to zero:

$$v_0 - \omega R = 0.$$

The resulting equations give

$$v_0 = v \frac{R}{R \sin \alpha - r}.$$

Obviously, when R \sin \alpha = r (this corresponds to the case when points A, B and C lie on the same line), the expression for v₀ loses its meaning. Note also that the found expression describes the movement of the coil both to the right (when point B is to the left of straight line AC and R \sin \alpha > r) and to the left (when point B is to the right of straight line AC and R \sin \alpha < r).

S. Krotov

F622. When and how many times greater is the absolute air humidity (air density) in the nubre at a temperature t₁ = 0°C and a humidity of 95% or in the nyula at t₂ = 35°C and a humidity of 40%, if the saturated vapor pressure at t₁ = 0°C is p₁ = 6 10²Pa, and at t₂ = 35°C it is p₂ = 5.5 × 10³Pa?

The water vapor pressure at relative humidity α is equal to

$$p = \alpha p_H,$$

where p_H is the saturated vapor pressure at a given temperature. We find the density of water vapor (absolute humidity) from the equation of gas state:

$$pV = \frac{m}{\mu} RT \Rightarrow \varrho = \frac{m}{V} = \frac{\mu p}{RT} = \frac{\mu a p_H}{RT}.$$

The ratio of water vapor densities q₂/q₁ in zero and in nyubre under specified conditions (α₂ = 0.4, T₂ = 308 K, p_H₂ = p₂ = 5.5 10³Pa, α₁ = 0.95, T₁ = 273 K, p_H₁ = p₁ = 6 10²Pa) is equal to

$$\frac{q_2}{q_1} = \frac{\alpha_2 p_2}{\alpha_1 p_1} \cdot \frac{T_1}{T_2} \approx 3,4.$$

Thus, in dry nyubr (40% humidity) there is 3.4 times more water vapor in the air than in raw nyubr (95% humidity).

V. Belonukkin
