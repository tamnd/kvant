---
id: 1981-11-galperin-galperin-osveschenie-ploskosti-prozhektorami-9ea4fd4a
issue: kvant_1981_11
year: 1981
number: "11"
title: Lighting the plane with spotlights
authors:
  - Гальперин В.
  - Гальперин Г. А.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 30
page_last: 32
page_labels: 28-30
tag: ESJY
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0663d0b192a733659a84137177de7671fde922c09bf7594b01f52be8429042b4
prompt_sha256: draft-1
translated_from: content/ru/1981/11/articles/08_galperin-galperin-osveschenie-ploskosti-prozhektorami-9ea4fd4a.md
source_content_sha256: 68d7dfcd82a8c35d498523f7f6dd46d07ca5d088c5cdd9372582fe989e4adb2a
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 28⟧

V. Galperin, G. Galperin

Covering the plane with projectors

Interesting and difficult problem M545, the solution of which is related to this note, in the formulation of the question and methods of solution is typical for combinatorial geometry - a section of geometry dealing with problems of partitions, coverings, packings of figures.
Let us recall its formulation:

There are n points given on the plane. It is necessary to place n projectors at these points, each of which illuminates an angle of magnitude $\frac{360^\circ}{n}$ so as to illuminate the entire plane. Prove that this is possible for any location of these points if a) n=3; 6) n=4; c) n - any natural number (in case a) - c) projectors can be rotated); d) Let now the projectors illuminate the corners $a_1, a_2, \dots, a_n$ ($a_1 + a_2 + \dots + a_n = 360^\circ$) and are arranged at one point so that they illuminate the entire plane. Prove that it is possible to transfer*) one of the n projectors to each of these points so that the entire plane is still illuminated.

The history of this problem is quite interesting. Its simplest special case 6) was presented at the first All-Union Mathematical Optimization in 1967. It was there that the second of the authors of this note met her (he was still a schoolboy at the time). A few years later he found evidence of more

*) This means that the projectors can be moved in parallel, but not rotated!

Let us now consider the angles symmetrical to these angles with respect to point O. figure 2 shows how to direct a projector placed at point $M_1$ so that it illuminates the corner shaded in red. Similarly, the projectors at points $M_2$ and $M_3$ can be directed so that they illuminate “their” corners.

The same idea - to divide the plane into parts. So that each of them can be illuminated with its own group of projectors, this can be applied in case c).

To do this, it is enough to prove the following two statements.

Statement 1. Let there be k projectors located inside a given angle of magnitude $\alpha = k \frac{2\pi}{n}$, where $k \leqslant \frac{n}{2}$. Then they can be rotated so that together they illuminate the entire angle symmetrical to the given one relative to its vertex (Fig. 3).

To prove this statement by indication on k, it is convenient to use the following arithmetic lemma. If $s_1, s_2, \dots, s_k$ are non-negative integers, and $s_1 \geqslant 1$,

Fig. 1.
Fig. 2.

⟦folio 29⟧

$s_k \geq 1$ and $s_1 + s_2 + \dots + s_k = k$, then there is a $m < k$ for which $s_1 + \dots + s_m = m$ (that is, $s_{m+1} + \dots + s_k = k - m$).

Finally, it remains to prove this rather regular fact - it is easier to do this separately for the even and odd $n$.

Statement 2. If a plane is given $n$ points $A_1, A_2, \dots, A_n$, then it can be divided into two half-planes containing $n/2$ points each, if $n$ is even, or into three angles with a common vertex and magnitude $k_1, k_2, \frac{2\pi}{n}, k_3, \frac{2\pi}{n}$, where $k_1 + k_2 + k_3 = n$ and $k_i < n/2$ ($i=1, 2, 3$), each of which contains by $k_i$ points if $n$ is odd.

Exercise 1. Prove statement 1, lemma and statement 2.

After this, according to Statement 1, we illuminate with the corresponding projectors the angles that are symmetrical with respect to their common vertex by the angle in which they are located, and the entire plane turns out to be illuminated.

Improvement algorithm

Let us outline the idea of ​​solving the point. G). Let us arrange the projectors at these points $M_1, M_2, \dots, M_n$ in an arbitrary manner. If not the entire plane is illuminated, we will present another, “improved” method of arranging projectors (in this case, the “quality” of the arrangement will be assessed by a certain numerical function $f$). Since there is only a finite number of projector arrangements at points $M_1, M_2, \dots, M_n$ (equal to $n!$), taking the arrangement for which the value of the function $f$ is maximum, we will automatically illuminate the entire plane: indeed, if not the entire plane were illuminated, we could still “improve” the arrangement, thereby obtaining a contradiction.

Let's implement this plan. Now the projectors are any angles $a_i$ with a common vertex $O$, $0 < a_i < \pi$, $a_1 + a_2 + \dots + a_n = 2\pi$, and each of them illuminates a side of some convex $n$-gon $A_1A_2\dots A_n$ (Fig. 4), $A_i \overrightarrow{OA_{i+1}} = a_i$. Let us drop perpendiculars $OH_i$ from point $O$ to the sides of the polygon (or their extensions); let $|OH_i| = h_i$.

Consider the vectors $\vec{e}_i = \frac{1}{h_i} \overrightarrow{OH_i}$. It is clear that $|\vec{e}_i| = \frac{1}{h_i}$ (Fig. 5).

The arrangement of projectors at points $M_1, M_2, \dots, M_n$ corresponds to the arrangement of vectors $\vec{e}_1, \vec{e}_2, \dots, \vec{e}_n$ at these points (we seem to attach the vector $\vec{e}_i$ to the projector $a_i$ and rearrange them together as a single whole).

The only geometric fact that we need in the future and that “justifies”, at first glance, the choice of vectors $\vec{e}_i$, is the following:

Lemma. Let the projector $a_p$ placed at the point $M$ illuminate the point $N$, but the projector $a_q$ does not. Then $\overrightarrow{MN} \cdot \vec{e}_p > \overrightarrow{MN} \cdot \vec{e}_q$.

Proof. Let $\overrightarrow{MN} = \vec{v}$. Let us plot the vector $\overrightarrow{OP} = \vec{v}$ (Fig. 6) from the point $O$. The ray [OP] intersects the $p$-th side of the polygon $A_1A_2\dots A_n$ at some point $K$, but does not intersect the $q$-th side, the distance of the projector $s_k \geq 1$ and $s_1 + s_2 + \dots + s_k = k$, then there exists $m < k$, for which $s_1 + \dots + s_m = m$ (that is $s_{m+1} + \dots + s_k = k - m$).

Finally, it remains to prove this rather regular fact - it is easier to do this separately for even and odd $n$.

Statement 2. If a plane is given $n$ points $A_1, A_2, \dots, A_n$, then it can be divided into two half-planes containing $n/2$ points each, if $n$ is even, or into three angles with a common vertex and magnitude $k_1, k_2, \frac{2\pi}{n}, k_3, \frac{2\pi}{n}$, where $k_1 + k_2 + k_3 = n$ and $k_i < n/2$ ($i=1, 2, 3$), each of them illuminates the inside of a certain convex $n$-gon $A_1A_2\dots A_n$ (Fig. 4), $A_i \overrightarrow{OA_{i+1}} = a_i$. Let us drop perpendiculars $OH_i$ from point $O$ to the sides of the polygon (or their extensions); let $|OH_i| = h_i$.

Consider the vectors $\vec{e}_i = \frac{1}{h_i} \overrightarrow{OH_i}$. It is clear that $|\vec{e}_i| = \frac{1}{h_i}$ (Fig. 5).

Fig. 6.

projector $a_p$ illuminates point $N$, but projector $a_q$ does not illuminate.

There are two possibilities: 1) the ray [OP] does not intersect the line on which the $q$-th side lies, and 2) the ray [OP] intersects this line at some point $R$.

In the first case it is very important, since $\vec{v} \cdot \vec{e}_p > 0$, and $\vec{v} \cdot \vec{e}_q \leq 0$.

In the second case it is very important, since $\vec{v} \cdot \vec{e}_p > 0$, and $\vec{v} \cdot \vec{e}_q \leq 0$.

The ray [OP] intersects the $p$-th side of the polygon $A_1A_2\dots A_n$ at some point $K$, but does not intersect the $q$-th side, the distance of the projector $s_k \geq 1$ and $s_1 + s_2 + \dots + s_k = k$, then there is $m < k$, so that they are illuminated by $n/2$ points, if $n$ is even, or into three angles with a common vertex and magnitude $k_1, k_2, \frac{2\pi}{n}, k_3, \frac{2\pi}{n}$, where $k_1 + k_2 + k_3 = n$ and $k_i < n/2$ ($i=1, 2, 3$), each of them illuminates a side of a certain convex $n$-gon $A_1A_2\dots A_n$ (Fig. 4), $A_i \overrightarrow{OA_{i+1}} = a_i$. Let us drop perpendiculars $OH_i$ from point $O$ to the sides of the polygon (or their extensions); let $|OH_i| = h_i$.

Consider the vectors $\vec{e}_i = \frac{1}{h_i} \overrightarrow{OH_i}$. It is clear that $|\vec{e}_i| = \frac{1}{h_i}$ (Fig. 5).

⟦folio 30⟧

Let us now introduce the quantities $f_{\sigma}(N)$, depending on the point $N$ of the plane and on the arrangement $\sigma$ of the projectors at points $M_1, M_2, \dots, M_n$, as follows:

$$f_{\sigma}(N) = \overrightarrow{M_1} N \cdot \overrightarrow{e_{\sigma(1)}} + \overrightarrow{M_2} N \cdot \overrightarrow{e_{\sigma(2)}} + \dots + \overrightarrow{M_n} N \cdot \overrightarrow{e_{\sigma(n)}}$$

(1) ($\sigma(i)$ is the number of the projector placed at point $M_i$).

The following main statement shows that the function $f_{\sigma}(N)$ can characterize the “quality” of the arrangement.

Statement 3. If the point $N$ in the arrangement $\sigma$ is not illuminated, then there is an arrangement of projectors m such that $f_{\tau}(N) > f_{\sigma}(N)$.

Proof. Let us first present an algorithm that allows us to “improve” the arrangement $\sigma$.

Let the projector $\alpha_i$ be located at point $M_i$. Let the projector $\alpha_1$ standing at point $M_1$ not illuminate point $N$. Let's remove it for a while, and at point $M_1$ we will cross the projector, which will then re-illuminate point $N$.

Exercise 2. Prove that such a projector exists.

Let this be the projector $\alpha_2$. Now at point $M_2$, where the projector $\alpha_2$ stood, there is nothing. Let's place one of the remaining projectors $n-1$ at this point, which will then illuminate point $N$. Let it be a projector $\alpha_3$. Let us now place the projector $\alpha_4$ at point $M_3$, which will then be illuminated by $N$, at point $M_4$ we place the projector $\alpha_5$ and so on until a cycle is formed (Fig. 7): this means that at point $M_k$ the projector $\alpha_{k+1}$ is intersected, to point $M_{k+1}$ - projector $\alpha_{k+2}$, to point $s$ - projector $\alpha_k$ ($s > k$). We will return the projectors $\alpha_1, \alpha_2, \dots, \alpha_{k-1}$ to their old places (to points with the same numbers). As a result, point $N$ will be illuminated by each projector $\alpha_k, \alpha_{k+1}, \dots, \alpha_s$ (since point $N$ was not illuminated, $s \geq k+1$).

Let's see how the number $f(N)$ has changed. The terms with numbers other than $k, k+1, \dots, s$ in sum (1) have not changed. And from the lemma it follows that all terms with numbers $k, k+1, \dots, s$ increased after the indicated rearrangement.

So, statement 3 is proven. True, the values ​​$f_{\sigma}$ cannot yet be used directly to assess the “quality” of the arrangement $\sigma$ - after all, it depends on the point $N$. This is where the wonderful thing saves.

Statement 4. For any two points $N_1$ and $N_2$, the difference $f_{\sigma}(N_1) - f_{\sigma}(N_2)$ does not depend on the arrangement of projectors.

Proof. $f_{\sigma}(N_1) - f_{\sigma}(N_2) = \sum_{i=1}^{n} \overrightarrow{M_{\sigma(i)}} N_1 \cdot \overrightarrow{e_{\sigma(i)}} - \sum_{i=1}^{n} \overrightarrow{M_{\sigma(i)}} N_2 \cdot \overrightarrow{e_{\sigma(i)}} = \sum_{i=1}^{n} (\overrightarrow{M_{\sigma(i)}} N_1 - \overrightarrow{M_{\sigma(i)}} N_2) \cdot \overrightarrow{e_{\sigma(i)}} = \sum_{i=1}^{n} \overrightarrow{N_2} N_1 \cdot \overrightarrow{e_{\sigma(i)}} = c$.

The sum $\sum_{i=1}^{n} \overrightarrow{e_{\sigma(i)}}$ is a constant vector (does not depend on the arrangement), $N_2 N_1$ is also a fixed vector, and therefore the number $c$ does not depend on the arrangement of the projectors, which is what needed to be proven.

This means that the function $f_{\sigma}(N)$ can be replaced by the function $f_{\sigma} = f_{\sigma}(N) + \overrightarrow{N_0} \cdot \overrightarrow{e_{\sigma(i)}} = \sum_{i=1}^{n} \overrightarrow{M_{\sigma(i)}} N_0 \cdot \overrightarrow{e_{\sigma(i)}}$, where $N_0$ is an arbitrary fixed point of the plane.

The number $f_{\sigma}$ no longer depends on the point $N$ and will increase with each permutation we described.

The idea is thus fully realized: a “quality function” was found that depended only on the arrangement of the projectors, and it was shown how to increase its value if some point is not illuminated. Since in some arrangement $\omega$ the number $f_{\omega}$ is maximum, with arrangement $\omega$ the entire plane is illuminated.

Exercise 3. Conduct a proof of spatial variants of the projector problem.

a) At any 8 points in space, you can place edgings (trihedral angles with right flat angles (see Fig. 8, a)) so that they cover the entire space.

b) Let a convex polyhedron with faces $\Gamma_1, \Gamma_2, \dots, \Gamma_n$ and a point $O$ inside it, as well as $n$ points $M_1, M_2, \dots, M_n$, be given in space. Each face $\Gamma_i$ defines a polyhedral angle $\alpha_i$ with vertex at $O$. At point $O$ there are $n$ projectors, and the $i$th projector, $1 \leq i \leq n$, illuminates the polyhedral corner $\alpha_i$ (thereby the entire space is completely illuminated (Fig. 8, b)). Prove that the projectors can be moved to points $M_1, M_2, \dots, M_n$ so that the entire space is still illuminated.
