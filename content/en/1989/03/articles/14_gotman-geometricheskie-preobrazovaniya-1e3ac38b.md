---
id: 1989-3-gotman-geometricheskie-preobrazovaniya-1e3ac38b
issue: kvant_1989_3
year: 1989
number: "3"
title: Geometric transformations
authors:
  - Готман Э. Г.
rubric: shkola-v-kvante
rubric_sub: Школа в «Кванте»
page_first: 54
page_last: 56
page_labels: 52-54
tag: 0SES
lang: en
source: kvant_digital
extraction: vision
content_sha256: 83c2c22ef7c4348eaef09c388759966b6483ebc5e22d72ab285fe0189a7f8f16
prompt_sha256: draft-1
translated_from: content/ru/1989/03/articles/14_gotman-geometricheskie-preobrazovaniya-1e3ac38b.md
source_content_sha256: 9a14e455f84b9fe5745e2b0397066288bb18921670e98eed775a854d6728a9f5
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 52⟧

and bending over notebooks with assigned controls.”

In 1913, Rutherford's collaborators tested Rutherford's formula for α-particle scattering by counting scinitillations observed at different angles over equal periods of time and confirmed it. This certainly indicated the validity of the nuclear model.atoma. Since a system of stationary charges cannot be in stable equilibrium, Rutherford abandoned the static atoma model and assumed that the electrons in an atom move around the nucleus, describing curved trajectories. But in this case, the electron must move with acceleration and, according to classical electrodynamics, emit electromagnetic waves, which, in turn, must be accompanied by a loss of energy. Ultimately, the electron must fall into the nucleus.

A way out of this contradiction was found by Niels Bohr. But that, as they say, is a completely different story. What about Rutherford's experiments? Are they now only important for the history of physics? It turns out not. It is interesting that almost 60 years later, already in the seventies, Rutherford’s method of probing matter with alpha particles began to be widely used in laboratories to study the structure of crystals, determine the location of various impurities in them and determine their composition. It is now called the Rutherford inverse scattering method. Only the sources of α-particles are not radium crumbs, but powerful accelerators, which make it possible to obtain large fluxes of them with high energies. And their prototype was a small lead box with radium salt, which, as you remember, Dr. Rutherford categorically refused to part with at the American customs.

M. Yu. Ditsilov

Matematika8,9,10

Geometric transformations

Part II: Similarity Transformations

In Part I of this article, published in the last issue «Kvant», we talked about how duodenum is used in solving geometric problems. Here we will talk about the application of a broader class of geometric transformations: similarity transformations.

Definition. A homothety with center O and coefficient k≠0 is a transformation in which the image of an arbitrary point A is a point A' such that OA'=k·OA.

⟦folio 53⟧

The single-walled fixed point of a homothety (at $k \neq 1$) is its center. If $k > 0$, then the points $A$ and $A'$ lie on the line $OA$ on one side of the homothety center, if $k < 0$, then on opposite sides. At $k = -1$ homothety is a central symmetry (rotation around the point $O$ by $180^\circ$).

A homothety with a positive coefficient $k$ translates each ray in conjunction with it and, therefore, does not change the orientation of the triangles. A homothety with a negative coefficient $k$ can be represented as a composition of a homothety with a positive coefficient $|k|$ and a rotation around the center by $180^\circ$. In this case, each ray transforms into a ray oppositely directed to it, but the orientation of the triangles does not change.

Let us consider the composition of homothety and rotation with a common center. Let, under homothety with center $O$ and coefficient $k$, point $A$ go to point $A'$, and when rotating around point $O$ by angle $\varphi$ (remember that by turning we always mean turning counterclockwise), point $A'$ goes to point $A''$ (Fig. 1). Their composition takes point $A$ to point $A''$. It is easy to check that the result does not change if we first perform the rotation and then the homothety.

The composition of homothety and rotation with a common center is similarity. If the homothety coefficient is positive, then the composition is called a center-like rotation. Let us introduce the following notation: $R_O^\varphi$—rotation around point $O$ by angle $\varphi$; $H_O^k$ — homothety with center $O$ and coefficient $k$; $\Pi_{k,\varphi}^O$ is a center-like rotation with center $O$, coefficient $k$ and rotation angle $\varphi$. Thus, $\Pi_{k,\varphi}^O = R_O^\varphi \cdot H_O^k = H_O^k \cdot R_O^\varphi$, $k > 0, 0 \leqslant \varphi < 360^\circ$.

With a central-like rotation, the angle between any ray and its image is equal to the angle of rotation. This follows from the fact that with a homothety with a positive coefficient, the ray goes into a co-directed ray, and when rotated, the angle between any image and its image is equal to the angle of rotation (see Theorem 1 of Part I in the previous issue «Kvant»).

Rotation and homothety preserve the orientation of triangles, which means that a center-like rotation also preserves it. Homotheties and central-like rotations, as well as parallel translations, are called similarity transformations of the first kind.

Homothety, rotation around a point and identity transformation can be considered as special cases of the central-like rotation $\Pi_{k,\varphi}^O$: for $\varphi = 0$ it is a homothety $H_O^k$, for $k = 1$ it is a rotation $R_O^\varphi$, for $k = 1$ and $\varphi = 0$ it is an identity transformation.

Similarity transformations of the first kind could be defined, like movements of the first kind, as plane transformations in which all distances are multiplied by the same positive number and the orientations of all triangles are preserved. The proof is similar to Theorem 2 of Part I.

Theorem 1. Every similarity transformation of the first kind is a central-like rotation or parallel translation (i.e., our original definition of a similarity transformation of the first kind is equivalent to the last definition).

Consequence. The composition of two center-like turns is a center-like turn or parallel translation.

We do not prove these statements, limiting ourselves to the following fact.

Theorem 2. The composition of two center-like rotations $\Pi_{k,\varphi}^A$ and $\Pi_{k,\varphi}^B$ at $k_1 k_2 = 1$ is a motion of the first kind: rotation if $\alpha + \beta \neq 360^\circ$, and parallel translation if $\alpha + \beta = 360^\circ$.

⟦folio 54⟧

Proof. The composition of two similarities of the first kind with coefficients $k_1$ and $k_2$ is a similarity of the first kind with coefficient $k_1 k_2$. Since $k_1 k_2 = 1$, the composition $F = \Pi_B^{k_2, \beta} \circ \Pi_A^{k_1, \alpha}$ is a movement of the first kind, in which each ray rotates first through the angle $\alpha$, and then through the angle $\beta$, and as a result, through the angle $\alpha + \beta$. Therefore, if $\alpha + \beta \neq 360^\circ$, then $F$ is a rotation around a certain point by an angle $\alpha + \beta$; if $\alpha + \beta = 360^\circ$, then $F$ is a parallel transfer.

Consequence. The composition of three similarities $F = \Pi_C^{k_3, \gamma} \circ \Pi_B^{k_2, \beta} \circ \Pi_A^{k_1, \alpha}$ is an identity transformation if and only if $k_1 k_2 k_3 = 1$, the sum of the rotation angles is equal to $360^\circ$ or $720^\circ$ and the transformation $F$ has a fixed point.

To prove this corollary, it is necessary to use the corollary of Theorem 1.

Exercises
1. Given two identically oriented squares $ABCD$ and $AB'C'D'$. Find the angle between rays $BB'$ and $CC'$.
2. Find a song
$$\Pi_C^{k, 120^\circ} R_B^{120^\circ} R_A^{120^\circ},$$
if $ABC$ is an equilateral triangle oriented negatively.
3. Find the angles of triangle $MNP$ if the composition
$$\Pi_N^{1/k, 90^\circ} \Pi_P^{k, 90^\circ} R_M^{180^\circ}$$
has a fixed point.

At the XVII International School Olympiad in 1975, the following task was proposed, which can be easily solved using transformation composition *).

*) The solution was proposed by Z. A. Skopets (magazine “Matematika at school”, 1977, No. 6).

Task. On the sides of an arbitrary triangle $ABC$, triangles $ABM$, $BCN$ and $CAP$ are constructed outside it so that $\angle CAP = \angle CBN = 45^\circ$, $\angle ACP = \angle BCN = 30^\circ$, $\angle ABM = \angle BAM = 15^\circ$. Prove that $\angle PMN = 90^\circ$ and $PM = MN$.

Solution. Let the given triangle $ABC$ be oriented positively (Fig. 2, a). Consider the composition

$$F = \Pi_N^{1/k, 105^\circ} \circ \Pi_P^{k, 105^\circ} R_M^{150^\circ},$$

where $k = \frac{\sin 45^\circ}{\sin 30^\circ} = \sqrt{2}$.

We have:

$$R_M^{150^\circ}(B) = A, \Pi_P^{k, 105^\circ}(A) = C,$$

$$\Pi_N^{1/k, 105^\circ}(C) = B.$$

Consequently, $F(B) = B$, i.e. $B$, is a fixed point of the transformation $F$. Since the product of the similarity coefficients is equal to 1 and the sum of the rotation angles is equal to $360^\circ$, we obtain that $F$ is the identity transformation.

The angles of the triangle $MNP$ can be found by constructing the image of the point $M$ with the composition $F$ (Fig. 2, b). Considering that $F(M) = M$, we get

$$R_M^{150^\circ}(M) = M, \Pi_P^{k, 105^\circ}(M) = M',$$

$$\Pi_N^{1/k, 105^\circ}(M') = M.$$

Triangles $PMM'$ and $PAC$ (as well as triangles $NMM'$ and $NBC$) are similar and have the same orientation. Triangles $PMM'$ and $NMM'$ are similar and oppositely oriented, $MM'$ is their common side, which means they are equal; hence $\angle PMN = 90^\circ$ and $PM = MN$.
