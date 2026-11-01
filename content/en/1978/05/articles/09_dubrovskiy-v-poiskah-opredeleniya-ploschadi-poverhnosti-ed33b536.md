---
id: 1978-5-dubrovskiy-v-poiskah-opredeleniya-ploschadi-poverhnosti-ed33b536
issue: kvant_1978_5
year: 1978
number: "5"
title: In search of a definition of surface area
authors:
  - Дубровский В. Н.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 33
page_last: 34
page_labels: 31-32
tag: PQ9H
lang: en
source: kvant_digital
extraction: vision
content_sha256: dc33d891d978755257d8780541e4187f3d667988693246d10d4cefd3332241d7
prompt_sha256: draft-1
translated_from: content/ru/1978/05/articles/09_dubrovskiy-v-poiskah-opredeleniya-ploschadi-poverhnosti-ed33b536.md
source_content_sha256: 51f0b2b218d38085fd9c43e366ac7fcc3d83c19bf2027b4143113dba822b929a
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 31⟧

In Japanese definitions of surface area

Determining the area of ​​a surface is one of the traditionally difficult topics in school geometry. This is due to the lack of a completely simple general definition that would cover at least all surfaces studied in school: cylinder, cone and sphere. The replacement examines two approaches to such definitions and discusses the difficulties encountered in these approaches.

Can everything be deployed?

The easiest way is to determine and calculate the areas of the surfaces of a cylinder and a cone - just consider the development of these surfaces (see “Geometry 8”, paragraphs 127, 128). However, the definition of the area of ​​a surface as the area of ​​its development is not suitable as a general definition simply because there are too few surfaces that could be “unfolded”. We will explain why the sphere cannot be “expanded”; Similar reasoning is applied to many other rotating surfaces.

Let's give a precise definition of sweep - it's quite a troublesome matter. It is clear, however, that if it were possible to “unfold” the sphere, then, in particular, we would obtain a mapping $f$ of some quite small “spherical cap” on a part of the plane (Fig. 1), in which the length of any curve $L$ lying on this “cap” would be equal to the length of the corresponding curve $f(L)$ on the plane. In particular, the length $d(A, B)$ of the shortest curve connecting points $A$ and $B$ on the sphere must be equal to the length of the shortest curve connecting points $A'=f(A)$ and $B'=f(B)$ on the plane, that is, the length of the segment $A'B'$:

$$d(A, B) = |A'B'|.$$

It is possible to prove that $d(A, B)$ is the length of the smaller of the other two circles passing through the points $A$ and $B$ defined by these points, but we will not need this.

Consider the set $C$ of points $M$ of a sphere for which the “spherical distance” $d(M, P)$ from some fixed point $P$ is equal to a fixed number $R>0$. Obviously, if the point $M_1$ is obtained from the point $M$ by repeating about the diameter of the sphere passing through $P$, then $d(M_1,P)=d(M,P)$. From here it is easy to deduce (derive!) that the set $C$ is a circle. Its center $O$ coincides with the base of the perpendicular, down-

Fig. 1. It is impossible to unwrap a sphere.

⟦folio 32⟧

Fig. 2. A sequence of broken lines $l_n$ converging to a segment of unit length (but not inscribed in it), the length of each of which is equal to $\sqrt{2}$.

extended from any point $M \in C$ to the radius of the sphere passing through the point $P$ (Fig. 1); therefore the radius of this circle is $r = |OM| < |MP|$. On the other hand, $d(M,P)$ is the length of some curve connecting $M$ and $P$, and the segment $MP$ is the shortest of such curves; therefore $|MP| \leq d(M,P) = R$. Therefore, $r < R$. When unfolding the circle, $C$ will go into a set of $C' = f(C)$ points distant from the point $f(P)$ at a distance $R$, that is, into a circle of radius $R$. The length of the circle $C$ is $2\pi r$, and the circumference $C' = 2\pi R > 2\pi r$. This contradicts the property of conservation of length formulated above, and thus the development of a sphere is impossible.

Sanor Schwartz

So, it is, generally speaking, impossible to unfold the surface; try to build differently. Consider a sequence of polyhedral surfaces $\Pi_n$ “converging” to a given surface $\Pi$. Let us assume that the sequence of their areas $S_n$ has limit $S$; then it seems natural to take the number $S$ as the surface area $\Pi^*$. Of course, caution must be exercised in this case - after all, even when determining the length of a curve, they consider not arbitrary, but described broken lines (they correspond to polyhedral surfaces) converging to the curve, otherwise the limit of their lengths will depend on the choice of the sequence of broken lines (see Figure 2 and Problem 3). Let's try to find the surface area of ​​a cylinder as the limit of the areas of polyhedral surfaces inscribed in it. We define these surfaces as follows.

Let us inscribe a regular $n$-gon at the base of the cylinder; Let us further consider the same $n$-gon located above the base at a height $\frac{H}{k}$, where $H$ is the height of the cylinder, $k$ is a fixed natural number, and rotate it relative to the first $n$-gon by an angle $\frac{\pi}{n}$.

Continuing this construction, we obtain $(k+1) \cdot n$ points - vertices of $n$-gons: we connect these vertices with edges, as shown in figure 3. As a result, a polyhedral surface $\Pi(n,k)$ inscribed in the cylinder is formed, which has $nk$ congruent triangular faces. By setting various

*) It is this approach that is used in the old geometry textbook by A.P. Kiselev when determining the surface areas of a cylinder and a cone.

Fig. 3. “Schwartz Sanor” (P (6, 4)).
