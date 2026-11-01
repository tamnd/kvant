---
id: 1987-1-ionin-nekrasov-vyichislenie-rasstoyaniy-i-uglov-39cfafea
issue: kvant_1987_1
year: 1987
number: "1"
title: Calculating distances and angles
authors:
  - Ионин Ю. И.
  - Некрасов В. Б.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 49
page_last: 53
page_labels: 47, 48, 50, 51
tag: ROC0
lang: en
source: kvant_digital
extraction: vision
content_sha256: 2e4f6941e14196e5b2d569a7136af19be1d622ec35a753e3e958854966d8d4e3
prompt_sha256: draft-1
translated_from: content/ru/1987/01/articles/14_ionin-nekrasov-vyichislenie-rasstoyaniy-i-uglov-39cfafea.md
source_content_sha256: bd92730ddf940480deef215de2d84af829a826b5218ca8ee01440a0a1de60d71
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 47⟧

Elevating distances and angles

Candidate of Pedagogical Sciences
Yu. I. IONIN,
V. V. NEKRASOV

This article discusses several geometric problems, for the solution of which it is necessary to calculate certain distances or angles in space (these problems are presented in the entrance exams to the development of universities). Problems of this type can be conveniently solved using the scalar product of vectors. The main solution method is to select a suitable basis in space and compile a multiplication table - a table of scalar products of vectors of this basis. Having such a table and knowing the decomposition of vectors in the selected basis, it is already easy to calculate the lengths of these vectors and the angles between them. We'll start with a simple problem where this method guides itself, and then move on to more complex problems, demonstrating all the basic cases.

Task 1 (MAI, 1981). In a triangular paramid ABCD, all edges have the same length. Point M is the midpoint of edge AD, point O is the center of triangle ABC, point N is the midpoint of edge AB, and point K is the midpoint of edge CD. Find the angle between lines MO and KN.

Solution e. Let us take the edge length of the tetrahedron to be one and choose the vectors $\overrightarrow{DA} = \vec{a}, \overrightarrow{DB} = \vec{b}, \overrightarrow{DC} = \vec{c}$ as a basis. Let's create a multiplication table for this basis (Table 1, p. 48). Let us expand the vectors $\overrightarrow{MO}$ and $\overrightarrow{KN}$ into the vectors $\vec{a}, \vec{b}, \vec{c}$:

$$\overrightarrow{MO} = \overrightarrow{DO} - \overrightarrow{DM} = \frac{1}{3} (\vec{a} + \vec{b} + \vec{c}) - \frac{1}{2} \vec{a} = \frac{1}{6} (-\vec{a} + 2\vec{b} + 2\vec{c}),$$

$$\overrightarrow{KN} = \overrightarrow{DN} - \overrightarrow{DK} = \frac{1}{2} (\vec{a} + \vec{b}) - \frac{1}{2} \vec{c} = \frac{1}{2} (\vec{a} + \vec{b} - \vec{c}).$$

The angle $\varphi$ between straight lines MO and KN is calculated by the formula

$$\cos \varphi = \frac{|\overrightarrow{MO} \cdot \overrightarrow{KN}|}{|\overrightarrow{MO}| \cdot |\overrightarrow{KN}|}.$$

Let's find $\overrightarrow{MO} \cdot \overrightarrow{KN}$, $|\overrightarrow{MO}|$ and $|\overrightarrow{KN}|$, getting table 1:

⟦folio 48⟧

$$\overrightarrow{MO} \cdot \overrightarrow{KN} = \frac{1}{12} (-\vec{a} + 2\vec{b} + 2\vec{c}) (\vec{a} + \vec{b} - \vec{c}) = \frac{1}{12};$$
$$|\overrightarrow{MO}| = \frac{1}{6} \sqrt{(-\vec{a} + 2\vec{b} + 2\vec{c})^2} = \frac{1}{2};$$
$$|\overrightarrow{KN}| = \frac{1}{2} \sqrt{(\vec{a} + \vec{b} - \vec{c})^2} = \frac{\sqrt{2}}{2}.$$
Hence $\cos \varphi = \frac{\sqrt{2}}{6}$, $\varphi = \arccos \frac{\sqrt{2}}{6}$.

However, the condition of the problem does not always allow choosing a basis with a fully defined multiplication table. In this case, you need to try to create an equation for the insufficient element.

Problem 2 (MIPT, 1974). The side of the base of a right triangular prism $ABCA_1B_1C_1$ is equal to $a$, the points $O$ and $O_1$ are the centers of the bases $ABC$ and $A_1B_1C_1$, respectively. The length of the orthogonal projection of the segment $AO_1$ onto the line $B_1O$ is equal to $\frac{5a}{6}$. Determine the height of the prism.

Solved and e. Let us choose the vectors $\overrightarrow{AA_1} = \vec{m}, \overrightarrow{AB} = \vec{n}, \overrightarrow{AC} = \vec{p}$ (Fig. 1) as a basis. Let $h = |\vec{m}|$. Table 2 is the multiplication table for the basis $(\vec{m}, \vec{n}, \vec{p})$.

The orthogonal projection of the segment $AO_1$ onto the line $B_1O$ is equal to the length of this segment multiplied by the cosine of the angle

Fig. 1.

f between lines $AO_1$ and $B_1O$. To calculate $|\overrightarrow{AO_1}|$ and cos $\varphi$, we expand the vectors $\overrightarrow{AO_1}$ and $\overrightarrow{B_1O}$ into the basis $(\vec{m}, \vec{n}, \vec{p})$:

$$\overrightarrow{AO_1} = \frac{1}{3} (\overrightarrow{AA_1} + \overrightarrow{AB_1} + \overrightarrow{AC_1}) =$$
$$= \frac{1}{3} (\vec{m} + \vec{m} + \vec{n} + \vec{p}) =$$
$$= \frac{1}{3} (3\vec{m} + \vec{n} + \vec{p});$$
$$\overrightarrow{B_1O} = \overrightarrow{AO} - \overrightarrow{AB_1} = \frac{1}{3} (\vec{n} + \vec{p}) - (\vec{m} + \vec{n}) =$$
$$= \frac{1}{3} (-3\vec{m} - 2\vec{n} + \vec{p}).$$

Using table 2, we find:

$$|\overrightarrow{AO_1}| = |\overrightarrow{B_1O}| = \frac{1}{3} \sqrt{9h^2 + 3a^2},$$
$$\overrightarrow{AO_1} \cdot \overrightarrow{B_1O} = -\frac{1}{6} (6h^2 + a^2),$$
$$\cos \varphi = \frac{6h^2 + a^2}{2(3h^2 + a^2)}.$$

Since $|\overrightarrow{AO_1}| \cdot \cos \varphi = \frac{5a}{6}$, we get the equation
$$\frac{\sqrt{9h^2 + 3a^2}(6h^2 + a^2)}{6(3h^2 + a^2)} = \frac{5a}{6}.$$
Hence $h = \frac{a \sqrt{6}}{3}$.

There are four main types of problems for calculating distances and angles:

1. Distance from a point to a straight line

Given: point $M$; line $l$ with direction vector $\vec{a}$, point $A$ belonging to line $l$; $\overrightarrow{AM} = \vec{m}$.

Find: the distance from point $M$ to straight line $l$.

(Vectors $\vec{a}$ and $\vec{m}$ under conditions of their expansion in a certain basis with a given multiplication table.)

Let us present a diagram for solving this problem.

Let $N$ be the orthogonal projection of the point $M$ onto the line $l$ (Fig. 2). Then $\overrightarrow{MN} = \overrightarrow{AN} - \overrightarrow{AM} = x\vec{a} - \vec{m}$. Nezvest-

⟦folio 50⟧

$\vec{A} = 60^\circ$. All edges of the prism have length $a$. Point $K$ is the orthogonal projection of point $B_1$ onto the plane $DA_1C_1$, and point $L$ is the orthogonal projection of point $K$ onto the plane $DD_1C_1C$. Find the volume of the pyramid $DCLK$.

Solution. Taking the base of the prim $DCLK$ as a triangle $CDL$, lying in the plane $DD_1C_1C$. then the segment $KL$ is the height of the prim (Fig. 5). Therefore, $V_{KCDL} = \frac{1}{3} S_{CDL} \cdot KL = \frac{1}{6} DC \cdot LM \cdot KL$, where $M$ is the orthogonal projection of the point $L$ onto the line $DC$.

Let's choose the vectors $\vec{C}_1\vec{B}_1 = \vec{m}, \vec{C}_1\vec{D}_1 = \vec{n}, \vec{C}_1\vec{C} = \vec{p}$ as a basis and fill out Table 4 - the multiplication table for this basis.

Next,
$$\vec{B}_1\vec{K} = \vec{C}_1\vec{K} - \vec{C}_1\vec{B}_1 = x\vec{C}_1\vec{A}_1 + y\vec{C}_1\vec{D} - \vec{C}_1\vec{B}_1 = x(\vec{m} + \vec{n}) + y(\vec{n} + \vec{p}) - \vec{m} = (x - 1)\vec{m} + (x + y)\vec{n} + y\vec{p}.$$

Since the vector $\vec{B}_1\vec{K}$ is perpendicular to the vectors $\vec{C}_1\vec{A}_1$ and $\vec{C}_1\vec{D}$, we obtain the system
$$\vec{B}_1\vec{K} \cdot (\vec{m} + \vec{n}) = 0, \quad \vec{B}_1\vec{K} \cdot (\vec{n} + \vec{p}) = 0.$$

Replacing the vector $\vec{B}_1\vec{K}$ with its decomposition into the basis $(\vec{m}, \vec{n}, \vec{p})$ and using Table 4, the procedure simplified to the control system $2x + y = 1$, $3x + 4y = 1$, we open $\vec{KL} = \frac{3}{5}(\vec{m} + \vec{n}) - \frac{1}{5}(\vec{n} + \vec{p}) = \frac{1}{5}(3\vec{m} + 2\vec{n} - \vec{p})$. Same as $\vec{KL} = \vec{C}_1\vec{L} - \vec{C}_1\vec{K} = z\vec{C}_1\vec{D}_1 + t\vec{C}_1\vec{C} - \vec{C}_1\vec{K} = z\vec{n} + t\vec{p} - \frac{1}{5}(3\vec{m} + 2\vec{n} - \vec{p}) = \frac{1}{5}(-3\vec{m} + (5z - 2)\vec{n} + (5t + 1)\vec{p})$. Since $\vec{KL} \cdot \vec{n} = 0$, then $-\frac{3}{2} + 5z - 2 = 0$, open $z = \frac{7}{10}$, and $5t + 1 = 0$, open $t = -\frac{1}{5}$. Hence,
$$\vec{KL} = \frac{1}{5}(-3\vec{m} + \frac{3}{2}\vec{n}) = \frac{3}{10}(-2\vec{m} + \vec{n}).$$

Now you can find the height of the prima $KCDL$:
$$KL = \frac{3}{10}\sqrt{(-2\vec{m} + \vec{n})^2} = \frac{3a\sqrt{3}}{10}.$$

All that remains is to find $\vec{LM}$:
$$\vec{LM} = \vec{CM} - \vec{CL} = u\vec{CD} - (\vec{C}_1\vec{L} - \vec{C}_1\vec{C}) = u\vec{n} - z\vec{n} - t\vec{p} + \vec{p} = (u - \frac{7}{10})\vec{n} + \frac{6}{5}\vec{p}.$$

Since $\vec{LM} \cdot \vec{n} = 0$, then $u = \frac{7}{10}$, open $\vec{LM} = \frac{6}{5}\vec{p}$, $|\vec{LM}| = \frac{6a}{5}$. Thus,
$$V_{KCDL} = \frac{1}{6} \cdot a \cdot \frac{6a}{5} \cdot \frac{3a\sqrt{3}}{10} = \frac{3a^3\sqrt{3}}{50}.$$

3. Distance and angle between intersecting lines

Given: line $l_1$ with direction vector $\vec{a}_1$, point $A_1$ belonging to line $l_1$; line $l_2$ with direction vector $\vec{a}_2$, point $A_2$ belonging to line $l_2$; $\vec{A}_1\vec{A}_2 = \vec{m}$.

Find: distance $u$ angle between lines $l_1$ and $l_2$.

⟦folio 51⟧

Specify this type of solution according to the following scheme.

The cosine of the angle φ between the lines $l_1$ and $l_2$ is found by the formula

$$\cos \varphi = \frac{|\vec{a}_1 \cdot \vec{a}_2|}{|\vec{a}_1| \cdot |\vec{a}_2|}.$$

To determine the distance between straight lines $l_1$ and $l_2$, that is, the length of their common redistribution $P_1P_2$ ($P_1 \in l_1$, $P_2 \in l_2$, figure 6), we represent the vector $\vec{P}_1\vec{P}_2$ as $\vec{P}_1\vec{P}_2 = \vec{P}_1\vec{A}_1 + \vec{A}_1\vec{A}_2 + \vec{A}_2\vec{P}_2 = x\vec{a}_1 + \vec{m} + y\vec{a}_2$. The unweighted coefficients $x, y$ are found from the condition of redistributing the vector $\vec{P}_1\vec{P}_2$ to the vectors $\vec{a}_1$ and $\vec{a}_2$:

$$\begin{cases}
(x\vec{a}_1 + y\vec{a}_2 + \vec{m})\vec{a}_1 = 0, \\
(x\vec{a}_1 + y\vec{a}_2 + \vec{m})\vec{a}_2 = 0.
\end{cases}$$

The required distance is the length of the vector $\vec{P}_1\vec{P}_2$, that is, $\sqrt{(x\vec{a}_1 + y\vec{a}_2 + \vec{m})^2}$.

Task 5 (MSU, Mek.-Mat., 1977). The base of the parameters SABC is an equilateral triangle ABC whose side length is $4\sqrt{2}$. The lateral edge SC is redistributed to the base plane and has length 2. Find the angle and distance between the crossing lines, one of which passes through the point S and the midpoint of the edge BC, and the other passes through the point C and the midpoint of the edge AB.

Solution. Let $M$ and $N$ be the midpoints of edges BC and AB (Fig. 7). Let us choose the vectors $\vec{CA} = \vec{a}$, $\vec{CB} = \vec{b}$, $\vec{CS} = \vec{c}$ as a basis. The multiplication table for this basis is table 5. Let's find the angle φ between straight lines SM and CN:

$$\vec{SM} = \vec{CM} - \vec{CS} = \frac{1}{2} \vec{b} - \vec{c} = \frac{1}{2} (\vec{b} - 2\vec{c}); \quad \vec{CN} = \frac{1}{2} (\vec{a} + \vec{b}).$$

Let's calculate $\vec{SM} \cdot \vec{CN}$, $|\vec{SM}|$, $|\vec{CN}|$:

$$\vec{SM} \cdot \vec{CN} = 12, \quad |\vec{SM}| = 2\sqrt{3}, \quad |\vec{CN}| = 2\sqrt{6}.$$

Therefore, $\cos \varphi = \frac{12}{2\sqrt{3} \cdot 2\sqrt{6}} = \frac{\sqrt{2}}{2}, \quad \varphi = 45^\circ$.

Let us now calculate the distance between the lines SM and CN, that is, the length of their common redistribution PQ ($P \in SM, Q \in CN$):

$$\vec{PQ} = x\vec{SM} + y\vec{CN} + \vec{SC} = \frac{x}{2} (\vec{b} - 2\vec{c}) + \frac{y}{2} (\vec{a} + \vec{b}) - \vec{c} = \frac{1}{2} (y\vec{a} + (x + y)\vec{b} - (2x + 2)\vec{c}).$$

From the condition of redistribution of the vector $\vec{PQ}$ of the vector $\vec{b} - 2\vec{c}$ and $\vec{a} + \vec{b}$ we obtain a system of equations

$$3x + 3y = -1, \quad x + 2y = 0,$$

whence $x = -\frac{2}{3}, \quad y = \frac{1}{3}$.

Therefore, $\vec{PQ} = \frac{1}{6} (\vec{a} - \vec{b} - 2\vec{c}), \quad PQ = \frac{1}{6} \sqrt{(\vec{a} - \vec{b} - 2\vec{c})^2} = \frac{2\sqrt{3}}{3}$.

4. Angle between planes

The angle between two planes is equal to the angle between their straight lines. Indeed, the empty planes $a$ and $b$ intersect along the straight line $c$ (Fig. 8). Through some line $c$, we draw lines $a$ and $b$, intersects the planes $a$ and $b$ along the lines $a_1$ and $b_1$, redistributed by the line $c$ (see Fig. 8). The angle between planes $a$ and $b$ is equal to the angle between lines $a_1$ and $b_1$, which, in turn, is equal to the angle between lines $a$ and $b$ (since lines $a, b, a_1, b_1$ lie in the same plane and $a \perp a_1, b \perp b_1$).
