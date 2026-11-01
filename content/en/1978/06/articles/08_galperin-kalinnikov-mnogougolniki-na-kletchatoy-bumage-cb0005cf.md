---
id: 1978-6-galperin-kalinnikov-mnogougolniki-na-kletchatoy-bumage-cb0005cf
issue: kvant_1978_6
year: 1978
number: "6"
title: Polygons on checkered paper
authors:
  - Гальперин В.
  - Калинников В.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 40
page_last: 43
page_labels: 38-41
tag: D6II
lang: en
source: kvant_digital
extraction: vision
content_sha256: 620dbdb2982ee4f1066c0a670cd74b3c9182f2d2d44247e9480ccfe950cc3123
prompt_sha256: draft-1
translated_from: content/ru/1978/06/articles/08_galperin-kalinnikov-mnogougolniki-na-kletchatoy-bumage-cb0005cf.md
source_content_sha256: 1fa091d5ac66f1ce01abb9d67f51ba5574eb45700b317905e2c1b555b49618cd
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 38⟧

Polygons on checkered paper

Is it possible to draw a polygon of a given shape on checkered paper, placing all its vertices at the grid nodes? As a rule - it is impossible. For example, from regular polygons, only a square can be drawn this way. And for which polygons can this be done approximately, i.e., by placing the vertices how angularly close to the nodes? It turns out - for everyone.
This note, written by students, shows why and how this can be done.

Let $\vec{a}$ and $\vec{b}$ be non-zero and non-linear vectors, $O$ be some point; then the set $\Pi$ of all such points

Fig. 1.

Fig. 2.

Fig. 3.

Fig. 4.

⟦folio 39⟧

Moreover, in the article by A. Egorov it was proven *) that no regular polygons, except triangles, squares and hexagons, can be written into any lattice. It is also clear that a predetermined polygon of arbitrary shape, as a rule, cannot be written into any lattice.

Since the problem of fitting polygons into a lattice leads in most cases to a negative result, it is natural to weaken it: to require that the vertices fall into the nodes only approximately. Let's give a precise definition:

A polygon is ε-added to the lattice Π if there exists a polygon similar to it (with a natural similarity coefficient), each of whose vertices is at a distance less than ε from one of the lattice nodes (Fig. 5). Note that for ε = 0 the definition of inscribedness given above is obtained, and for large ε (greater than the distance between nodes) the definition is meaningless.

It would become just as meaningless if we first assumed the naturalness of the similarity coefficient; by taking this coefficient close enough to 0, it would be possible to shrink the entire polygon near one lattice point. With a natural similarity coefficient (and a sufficiently small ε), any two vertices of the polygon obviously cannot fall into the ε-neighborhood of the same node.

Further, we will say that the polygon is cleared in

*) «Kvant», 1974, № 12, c. 30.

Fig. 5.

Fig. 6.

⟦folio 40⟧

Fig. 7.

and $\{n\sqrt{3}\}$, where $m > n$ are natural numbers. Then $(m-n)\sqrt{3}$ differs from the whole by less than $\frac{1}{N}$ and therefore less than $\varepsilon$. Setting $k$ equal to $m-n$, we obtain what is required.

The theorem has been proven, but there is a much more general fact.

Fundamental theorem. The fix polygon fits into any grid.

Note that point c) problem M475 is a special case of this theorem.

Proof. Let a lattice $\Pi$, a number $\varepsilon > 0$ and a polygon $\Phi$ be given.

Let us prove that under some homothety with a natural coefficient $N$, the polygon $\Phi$ goes into a polygon $\Phi'$ such that all vertices $\Phi'$ will be at a distance less than $\varepsilon$ from the lattice nodes.

Consider the vertex $A$ of the polygon. Let the homothety with center $O$ and coefficient $k$ transform the point $A$ into $A_k$ and $\overrightarrow{OA} = x_A \overrightarrow{a} + y_A \overrightarrow{b}$, where $\overrightarrow{a}$ and $\overrightarrow{b}$ are vectors generating the lattice. Then $\overrightarrow{OA}_k = k(x_A \overrightarrow{a} + y_A \overrightarrow{b}) = (kx_A) \overrightarrow{a} + (ky_A) \overrightarrow{b}$.

The condition that $A_k$ is less than $\varepsilon$ away from the lattice node (Fig. 7) will be satisfied if each of the coordinates $(kx_A)$ and $(ky_A)$ differs from the whole by less than $c.\varepsilon$, where $c$ is a coefficient independent of $k$:

$$\text{можно, например, взять } c = \frac{1}{2\max(|\overrightarrow{a}|, |\overrightarrow{b}|)}$$

Indeed, let $\overrightarrow{OF} = \overrightarrow{ma} + \overrightarrow{nb}$.

Fig. 8.

Then if

$$|m|\overrightarrow{a}| - kx_A|\overrightarrow{a}| \leq \frac{\varepsilon}{2} \text{ и } |n|\overrightarrow{b}| - ky_A|\overrightarrow{b}| < \frac{\varepsilon}{2}, \text{ то } |A_kF| = |A_hF| = |\overrightarrow{OF} - \overrightarrow{OA}_k| = |m\overrightarrow{a} + n\overrightarrow{b} - kx_A\overrightarrow{a} - ky_A\overrightarrow{b}| = |(m - kx_A)\overrightarrow{a}| + (n - ky_A)\overrightarrow{b}| \leq |(m - kx_A)\overrightarrow{a}| + |(n - ky_A)\overrightarrow{b}| + |m\overrightarrow{a}| - kx_A|\overrightarrow{a}| + |n|\overrightarrow{b}| - ky_A|\overrightarrow{b}| < \frac{\varepsilon}{2} + \frac{\varepsilon}{2} = \varepsilon.$$

But the inequalities $|m|\overrightarrow{a}| - kx_A|\overrightarrow{a}| < \frac{\varepsilon}{2}$ and $|n|\overrightarrow{b}| - ky_A|\overrightarrow{b}| < \frac{\varepsilon}{2}$ are equivalent to the inequalities $|m - kx_A| < \frac{\varepsilon}{2|a|}$ and $|n - ky_A| < \frac{\varepsilon}{2|b|}$. Therefore, if $kx_A$ and $ky_A$ differ from integers by less than $\frac{\varepsilon}{2\max(|\overrightarrow{a}|, |\overrightarrow{b}|)}$, then $|A_hF| < \varepsilon$ for the next node $F$, and this is what was required.

We need the vertices of the polygon $\Phi'$ to fall into the $\varepsilon$-neighborhoods of the lattice nodes. It will be so if all the numbers $Nx_A, Ny_A, Nx_B, Ny_B$, ... differ from the integers by less than $c.\varepsilon$, that each of the numbers $m\alpha_i$, where $i = 1, 2, ..., n$, differs from the integer by less than $\varepsilon$; that $\alpha$ was equal to $\sqrt{3}$ does not exist). Kroneckar's theorem states that for a set $\alpha_1, \alpha_2, ..., \alpha_n$ of any length with some natural number $m$ the numbers $\alpha_i$ at one time do not differ from the integers by less than $\varepsilon$.

Let's move on to the proof of Kroneckar's theorem.

Consider $n$ sequences:

$$\{\alpha_1\}, \{2\alpha_1\}, \{3\alpha_1\}, ..., \{k\alpha_1\}, \dots$$

$$\{\alpha_2\}, \{2\alpha_2\}, \{3\alpha_2\}, ..., \{k\alpha_2\}, \dots$$

$$\{\alpha_n\}, \{2\alpha_n\}, \{3\alpha_n\}, ..., \{k\alpha_n\}, \dots$$

⟦folio 41⟧

some $k_1 < k_2 \leq M^n + 1$ sets will match. In this case, the number $m = k_2 - k_1$ satisfies the condition, since $\{m\alpha_i\} = \{(k_2 - k_1)\alpha_i\} = \{k_2\alpha_i - k_1\alpha_i\}$, and $\{k_1\alpha_i\}$ and $\{k_2\alpha_i\}$ are in one semiperval of length less than $\varepsilon$, so $m\alpha_i$ is at a distance less than $\varepsilon$ from the integer. The theorem has been proven.

Do six pins pass matrizes the grids on the plane. Spatial lattices can also be considered. They are defined in the same way as planar ones, only instead of two non-clip vectors, you need to take three non-coplane ones (Fig. 9). In the same way as was done above for polygons and flat lattices, the inscribedness and almost inscribedness of polygons in a spatial lattice is determined. Which of the heels of regular polygons (Fig. 10) fit into the integer*) spatial lattice? Here's the answer:

Problem 4. The cube, tetrahedron and octahedron fit into an integer lattice.

Problem 5. The dodecahedron and icosahedron do not fit into any lattice.

Problem 6. Let a family of parallel planes be given in space such that the distances between neighboring planes of the family are equal. Is it possible to arrange in space a) an icosahedron, b) a dodecahedron so that their vertices lie on the planes of the family?

We received a comprehensive answer about the inscription of regular polygons into a spatial lattice. For almost inscription, we also get a comprehensive answer, the same as for the flat case:

Problem 7. Any polygon almost fits into any lattice in space.

All members of these sequences belong to the interval [0; 1[. Divide this interval into pieces (half-sections) of length less than $\varepsilon$:

$$\begin{align*}
0; \frac{1}{M} \mid ; \left[\frac{1}{M}; \frac{2}{M}\right] \mid \dots \mid \left[\frac{M-1}{M}; 1\right] \\
\mathrm{где} M - \mathrm{натуральное}, M > \frac{1}{\varepsilon} \quad (\mathrm{тогда} \frac{1}{M} < \varepsilon). \end{align*}$$

Now let’s assign each member of the sequence that piece of the interval [0; 1[, in which it is located.

Then for each natural number $k$ an ordered set of semipervals corresponding to the points $\{k\alpha_1\}$, $\{k\alpha_2\}, \dots, \{k\alpha_n\}$ will be defined. But since there are only $M$ semi-pervals under consideration, and each set includes $n$ semi-pervals, then the number of different such sets is $M^n$. If $k$ ranges from 1 to $M^n + 1$, then for
