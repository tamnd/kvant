---
id: 1990-12-gisin-chertezhnik-risuet-kvadrat-9fb93722
issue: kvant_1990_12
year: 1990
number: "12"
title: A draftsman draws a square
authors:
  - Гисин В. Б.
rubric: osnovnye-stati
page_first: 16
page_last: 19
page_labels: 14-17
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0be5e9196999a11b1511125ac8672575454c3b54777dc1b9a12b1a63021b936d
prompt_sha256: draft-1
translated_from: content/ru/1990/12/articles/04_gisin-chertezhnik-risuet-kvadrat-9fb93722.md
source_content_sha256: 60165098a7ac3335f24c3c4dea4c50bf251595bfb63dfc42a90609240edb430d
translation_model: draft
translation_run: en-draft-2026-11-06
translation_quality: draft
---

⟦folio 14⟧

---
running_head:
folio:
---

TO POINT X
LOWER
FEATHER!
LIFT
FEATHER!
mean
ON
VECTOR
Tishkov

14

⟦folio 15⟧

---
running_head:
folio:
---

DRAFTSMAN
DRAWS A SQUARE

Candidate of Physical and Mathematical Sciences
V. GISIN

Sometimes seemingly very simple problems in computer science lead to interesting mathematical problems. We will consider one such problem from the computer science textbook edited by A. P. Ershov (1988).

First, let us recall the description of the Draftsman - a device designed to plot figure on the coordinate plane. The draftsman has a pen that can move along a plane. If the pen is down, it leaves a mark. The draftsman can execute 4 commands: “raise pen”, “lower pen”, “move to point $(x; y)$”, “move to vector $(d_x; d_y)$”. The coordinates of points and vectors in the Draftsman's commands are written in the form of finite decimal fractions. It is believed that before the Draftsman begins to work, the plane is clean, the pen is raised and located at the origin of coordinates. To get figure you need to give the Draftsman a series of commands. For example, if you command:

move to point $(1; 1)$; lower the pen; shift by vector $(0; -2)$; shift by vector $(-2; 0)$; shift by vector $(0; 2)$; shift by vector $(2; 0)$; raise the pen

then after execution a square will be drawn from side 2 and center at the origin (problem 1 in §4). A natural question arises: can the Draftsman draw any square with side 2 and center at the origin that does not coincide with our square?

It is clear that the coordinates of the vertices of any such square are expressed in finite decimal fractions. On the contrary, if the coordinates of at least one vertex of a square centered at the origin are finite decimal fractions (for example, $(x; y)$), then the coordinates of the remaining vertices (namely, $(x; y)$, $(-y; x)$, $(-x; -y)$, $(y; -x)$) and the coordinates of all side vectors (namely, $(-x - y; x - y)$, $(-x + y; -x - y)$, $(x + y; -x + y)$, $(x - y; x + y)$) - figure 1. Similarly, if at least one of our four vectors has finite decimal coordinates, then the remaining vectors and all vertices have finite decimal coordinates. Thus, a square centered at the origin can be constructed using our Draftsman if and only if at least one of its vertices or at least one vector of its sides has coordinates that are finite decimal fractions.

It is more convenient for us to consider not vectors, but half of vectors. If for the side of the square is equal to 2, then for its half is equal to 1. Thus, so that all squares that are solutions to our problem

Fig. 1.

⟦folio 16⟧

---
running_head:
folio:
---

we must simply find all pairs of $(a; b)$ finite decimals for which $a^2 + b^2 = 1$. Another way is to find all the points of the unit circle with the center at the origin, the coordinates of which are finite decimal fractions.

Four such points are immediately visible: $(\pm 1; 0)$ and $(0; \pm 1)$. But they correspond to our square. Is there anything else? Yes, for example, $a = 0,6$, $b = 0,8$ (or $a = \pm 0,6$, $b = \pm 0,8$, or $a = \pm 0,8$, $b = \pm 0,6$). What else? There is more, as simple geometric reasoning shows.

The coordinates of an arbitrary point on our circle are $(\cos \varphi; \sin \varphi)$, where $\varphi$ is the angle between the positive direction of the $OX$ axis and the radius vector of our point, not counterclockwise. This means we want to find all angles $\varphi$ also that $\cos \varphi$ and $\sin \varphi$ are finite decimals. Now we also have decimal angles.

Lemma. If $\varphi_1$ and $\varphi_2$ are decimal angles, then $\varphi_1 + \varphi_2$ and $\varphi_1 - \varphi_2$ are also decimal angles.

Proof. This is immediately clear from the formulas $\cos(\varphi_1 \pm \varphi_2) = \cos \varphi_1 \cos \varphi_2 - \sin \varphi_1 \sin \varphi_2$, $\sin(\varphi_1 \pm \varphi_2) = \sin \varphi_1 \cos \varphi_2 \pm \cos \varphi_1 \sin \varphi_2$.

Consequence. If $\varphi_1$ and $\varphi_2$ are decimal angles, then $k_1 \varphi_1 + k_2 \varphi_2$ is the decimal angle for any integers $k_1$ and $k_2$.

The point $(0,6; 0,8)$ corresponds to the angle $\varphi_0$, for which $\cos \varphi_0 = 0,6$, $\sin \varphi_0 = 0,8$. Angle $\varphi_0$ is decimal. But according to what has been proven, $2\varphi_0$ is also a decimal angle. According to the well-known formulas $\cos 2\varphi_0 = 0,6^2 - 0,8^2 = -0,28$, $\sin 2\varphi_0 = 2 \cdot 0,6 \cdot 0,8 = 0,96$. So, here is another approach to the circle point: $(-0,28; 0,96)$. Or you can take $(0,28; 0,96)$, and in general $(\pm 0,28; \pm 0,96)$ or $(\pm 0,96; \pm 0,28)$. You can also take $3\varphi_0$, $4\varphi_0$, ... Then let’s not forget about points $(\pm 1; 0)$ and $(0; \pm 1)$. They correspond to angles $0, \frac{\pi}{2}, \pi, \frac{3\pi}{2}$, i.e. angles $\frac{l\pi}{2}$ with $l = 0,1,2,3$. This means we know the mass of decimal angles: these are all angles

$k\varphi_0 + \frac{l\pi}{2}$ (*)

with any integer $k$ and $l = 0,1,2,3$ (you can say “with any integer $l$”, but if $l$ is changed to 4, the angle will change to $2\pi$, i.e. it will give the same rotation). But maybe that's not all? No, that's all. We will also consider the theorem.

Theorem 1. All decimal angles are of the form (*), and all angles (*) ($c l = 0,1,2,3$) are distinct.

We will prove this theorem a little later. Now let's note that the squares that our Draftsman can build are obtained from the square described at the beginning of the stat, by rotating by decimal angles $\varphi$ around the origin. figure 2 shows the squares formed by the midpoints of the sides of the original and rotated squares. Unit vectors going from the origin to their vertices are tenths. In addition, since rotating a vector through an angle $\pi/2$ transforms every square into itself, the following theorem turns out to be true.

Theorem 2. Squares with side 2 and center at the origin, which can be constructed using the Draftsman, are squares obtained from the first analogous square by turning in one direction or another by angles $\varphi_0, 2\varphi_0, 3\varphi_0$, ... All these squares are different.

⟦folio 17⟧

---
running_head:
folio:
---

(Recall that a rotation through an angle - φ is a rotation through an angle φ in the opposite direction.)
We will now move on from our drawing problems and turn to the proof of Theorem 1.
Proof of Theorem 1.
Let $\alpha$ be the decimal angle, and let $\cos \alpha = A/10^n$, $\sin \alpha = B/10^n$, where $A$ and $B$ be integers. Then
$$\left(\frac{A}{10^n}\right)^2 + \left(\frac{B}{10^n}\right)^2 = 1, A^2 + B^2 = (10^n)^2 = 10^{2n}.$$
Let us denote by $C$ the most common divisor of the numbers $A, B$ and $10^n$ and set $a = A/C, b = B/C$; we have:
$$a^2 + b^2 = (10^n/C)^2.$$
The number $10^n/C$ must be odd, which means it is a power of five. Indeed, if $10^n/C$ is even, then $a$ and $b$ cannot both be even; but if one of them is even and the other odd, then the sum $a^2 + b^2$ is odd, and with it $10^n/C$ is odd, but if $a$ and $b$ were both odd, then $a^2$ and $b^2$ would have a remainder of 1 when divided by 4, contrary to the fact that the number $(10^n/C)^2$, being even, must be divisible by 4.
So we have to solve in integers the equations
$$a^2 + b^2 = 5^{2m}.$$
Our goal is to show that these solutions are exhaustive to the following:
$$a = 5^m \cos \alpha, b = 5^m \sin \alpha,$$
where $\alpha = k \varphi_0 + \frac{l \pi}{2}$ (and $m$ is an integer such that $a$ and $b$ are integers). In other words,
$$a = 5^m \cos \left(k \varphi_0 + \frac{l \pi}{2}\right) = \left\{ \begin{array}{l} \text{или } \pm 5^m \cos \left(\pm k \varphi_0\right), \\ \text{или } \pm 5^m \sin \left(\pm k \varphi_0\right) \end{array} \right.$$
and similarly for $b$.
Let us assume that for $m < m_0$ all integer solutions of our equation have the indicated form. Let us take the solution $a, b$ of the equation
$$a^2 + b^2 = 5^{2m}.$$
We can assume that $a$ and $b$ are not de-
are divisible by 5 (if $a$ is divisible by 5, then $b$ is also divisible by 5, and then $a' = a/5, b' = b/5$ is a solution to a similar equation with $5^{2(m-1)}$ instead of $5^{2m}$ and it has the desired form by assumption). Let's write our solution in the form $a = 5^m \cdot \cos \alpha, b = 5^m \cdot \sin \alpha$ and consider the numbers $3a + 4b, 3a - 4b$. Their product $9a^2 - 16b^2 = 9(a^2 + b^2) - 25b^2 = 9 \cdot 5^{2m} - 25b^2$ is divisible by $5^2$ and not divisible by $5^3$; their sum $6a$ is not divisible by 5. This means that one of these numbers, let $3a + 4b$ be used to determine this, is divisible by $5^2$. Let's put $a' = \frac{3a + 4b}{5^2}$. This is an integer not divisible by 5. Let's also put $b' = a + b - 7a' = \frac{4a - 3b}{5^2}$. Then
$$(a')^2 + (b')^2 = \frac{9a^2 + 12ab + 16b^2 + 16a^2 - 12ab + 9b^2}{5^4} = \frac{25(a^2 + b^2)}{5^4} = 5^{2m+2-4} = 5^{2(m-1)}.$$
This means that $a'$, $b'$ is a solution to an equation of our type with $5^{2(m-1)}$ instead of $5^{2m}$, i.e.
$$a' = 5^{m-1} \cos \beta, b' = 5^{m-1} \sin \beta,$$
where $\beta$ has the form $q \varphi_0 + \frac{r \pi}{2}, r = 0, 1, 2, 3.$
But at the same time
$$a' = \frac{3a + 4b}{5^2} = 5^{m-1} \cdot \left(\frac{3}{5} \cos \alpha + \frac{4}{5} \sin \alpha\right) = 5^{m-1} (\cos \varphi_0 \cos \alpha + \sin \varphi_0 \sin \alpha) = 5^{m-1} \cos (\alpha - \varphi_0)$$
and, similarly,
$$b' = 5^{m-1} \sin (\alpha - \varphi_0).$$
This means that $\beta = \alpha - \varphi_0, \alpha = \beta + \varphi_0$, and our solution also has the required form. The theorem has been proven.

Exercise. Let's introduce an additional restriction on the form of the Draftsman's commands: the number entry should not contain more than five significant digits (consecutive zeros on the left and right are not counted). Determine how many squares with side 2 and center at the origin can be violated by the Draftsman.
