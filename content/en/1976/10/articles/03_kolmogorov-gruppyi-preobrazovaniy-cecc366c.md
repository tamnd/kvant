---
id: 1976-10-kolmogorov-gruppyi-preobrazovaniy-cecc366c
issue: kvant_1976_10
year: 1976
number: "10"
title: Transformation groups
authors:
  - Колмогоров А. Н.
rubric: osnovnye-stati
page_first: 4
page_last: 6
page_labels: 2, 4
tag: SM6R
lang: en
source: kvant_digital
extraction: vision
content_sha256: 3cd8a9465dc3ecf7ca3fb28a59afc5dafcf2085b527caff949db60cc6908e1f8
prompt_sha256: draft-1
translated_from: content/ru/1976/10/articles/03_kolmogorov-gruppyi-preobrazovaniy-cecc366c.md
source_content_sha256: 73df56adcea2b2207a24ca33db2414d0a7d9c9a27785de4c7066609423d40cd5
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 2⟧

TRANSFORMATION GROUPS

The purpose of my short note is to make the content of the published article “Groups” by L. Sadovsky and M. Arshinov more accessible and connect it with new school textbooks.

According to the new school programs, schoolchildren in the fifth grade are introduced to the concept of “mapping a set to a set.” In sixth grade, they are introduced to the concept of “invertible mapping” (in another terminology, familiar to many readers «Kvant», “one-to-one mapping”).

Every invertible map has an inverse map. For example, the rotation $R_0^{70^\circ}$ around the point $O$ by $70^\circ$ counterclockwise (Fig. 1) has as its inverse mapping a rotation around the point $O$ by $70^\circ$, but in a clockwise direction. In the new geometry textbook, this rotation is represented by $R_0^{-70^\circ}$ (rotation around the point $O$ by minus $70^\circ$).

In the next and last classes, students are introduced to the concept of “display composition.” Let us consider, for example, two movements of the plane, that is, two mappings of the plane onto itself that preserve distances. As the first displacement we take the axial symmetry $S_x$ with the axis $x$, and as the second - the axial symmetry $S_y$ with the axis $y$, perpendicular to the axis $x$ (Fig. 2). What happens if you perform these two mappings sequentially: first $S_x$, and then $S_y$?

The point $P$ with its own symmetry $S_x$ will go into the point $P_1$, which is symmetric relative to the axis $x$, and with the symmetry $S_y$ of the point $P_1$ it will go into the point $P_2$. The above can be written in the form of equality

$$P_2 = S_y(S_x(P)).$$

On the other hand, the point $P_2$ can be obtained directly from the point $P$ using the central symmetry $Z_0$ with the center $O$ being the intersection point of the lines $x$ and $y$:

$$P_2 = Z_0(P).$$

Prove on your own that for any point $P$ of the plane

$$S_y(S_x(P)) = Z_0(P)$$

(it is assumed, as was said, that the lines $x$ and $y$ are perpendicular and intersect at the point $O$).

⟦folio 4⟧

Having solved problems 2 and 3, you will establish that the set $G_1$ has properties (1) and (2) from the definition of a transformation group, that is, that $G_1$ is a transformation group of the plane.

A more general fact can be proven: the set $G_\Phi$ of all displacements of the plane; which map any given figure $\Phi$ onto itself is a plane transformation group. The proof is not difficult (do it!). The group $G_\Phi$ is called the symmetric figure group $\Phi$.

From the composition table of the set $G_1$ we see that the composition of movements is not always repositionable:

$$S_{(OA)} \circ S_{(OB)} = R_0^{-120^\circ} \neq R_0^{120^\circ} = S_{(OB)} \circ S_{(OA)}.$$

It can, however, be proven that the composition operation of transforming the set $M$ always has the associativity property:

$$F_3 \circ (F_2 \circ F_1) = (F_3 \circ F_2) \circ F_1$$

(try this).

Table 1

| $\circ$ | $E$ | $S_{(OA)}$ | $S_{(OB)}$ | $S_{(OC)}$ | $R_0^{120^\circ}$ | $R_0^{-120^\circ}$ |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $E$ | $E \circ E = E$ | $E \circ S_{(OA)} = S_{(OA)}$ | $E \circ S_{(OB)} = S_{(OB)}$ | $E \circ S_{(OC)} = S_{(OC)}$ | $E \circ R_0^{120^\circ} = R_0^{120^\circ}$ | $E \circ R_0^{-120^\circ} = R_0^{-120^\circ}$ |
| $S_{(OA)}$ | $S_{(OA)} \circ E = S_{(OA)}$ | $S_{(OA)} \circ S_{(OA)} = E$ | $S_{(OA)} \circ S_{(OB)} = R_0^{-120^\circ}$ | | | |
| $S_{(OB)}$ | | $S_{(OB)} \circ S_{(OA)} = R_0^{120^\circ}$ | | | | |
| $S_{(OC)}$ | | | | | | |
| $R_0^{120^\circ}$ | | | | | | |
| $R_0^{-120^\circ}$ | | | | | | |
