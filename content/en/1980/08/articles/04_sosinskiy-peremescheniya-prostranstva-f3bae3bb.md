---
id: 1980-8-sosinskiy-peremescheniya-prostranstva-f3bae3bb
issue: kvant_1980_8
year: 1980
number: "8"
title: Moving space
authors:
  - Сосинский А. Б.
rubric: osnovnye-stati
page_first: 4
page_last: 7
page_labels: 2-5
tag: UPMN
lang: en
source: kvant_digital
extraction: vision
content_sha256: 1f02c9550d10103414e8ac4ad703c2639a5be5d67362581da2c5c80649a2731b
prompt_sha256: draft-1
translated_from: content/ru/1980/08/articles/04_sosinskiy-peremescheniya-prostranstva-f3bae3bb.md
source_content_sha256: 63964931eef9fbb88fbaa6600d77dbf79b8c53b1ce671a125548b833c3aca986
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 2⟧

A. Sosinsky

Moving space

In this article I want to tell you what space movements are like. First it is written: the displacement of space is the mapping $f$ of space onto itself, preserving the distances between points. This means that for any points $A, B$

$$|AB| = |A'B'|,$$

(1)

where $A' = f(A), B' = f(B)$.

You, of course, know the examples - these are symmetries (central, osvaya, relative to the plane) and parallel translation $\vec{a}$; it is easy to say that the movement will also

gate $R_l^\phi$ around line $l$ at a given angle φ (Fig. 1). Our task is to list all the movements of space, just as was done for the plane in the article by V. Boltyansky “Movements of the plane” («Kvant», 1980, No. 3).

It is easy to deduce from the definition that displacement transforms a straight line into a straight line, a plane into a plane, a circle into a concentric circle, an angle into a concentric angle, etc.

Movements and Orientations

On a plane, orientation is specified by specifying one of two possible directions of rotation - “clockwise” or “counterclockwise”. Obviously the direction “counterclockwise” is called positive, “clockwise” is called negative.

There are also two orientations in space: one is given by the left gimlet (such, for example, as a general corkscrew), the other by the left one (Fig. 2).

Mathematicians do not really like to talk about gimlets - they prefer to specify the orientation of space by indicating a non-planar triple of vectors $(\vec{a}; \vec{b}; \vec{c})$.

Fig. 1.

⟦folio 3⟧

The fact is that all such triples are naturally divided into two classes - into triples in which the shortest time from the first vector to the second for the observed, located at the end of the third vector, is positive (see Fig. 3; let's call such triples positive), and into triples in which it is negative (negative triples).

Check yourself: are you going that way?
a) do the triples ($\vec{a}; \vec{b}; \vec{c}$) and ($\vec{c}; \vec{a}; \vec{b}$) have the same sign?
b) do the triples ($\vec{a}; \vec{b}; \vec{c}$) and ($\vec{a}; \vec{c}; \vec{b}$) have different signs?
b) do the triples ($\vec{a}; \vec{b}; \vec{c}$) and ($\vec{a}; \vec{b}; -\vec{c}$) have different signs?

Physicists prefer hands to triples of vectors: the right hand sets a positive orientation, the left - a negative one (Fig. 4); remember the left-hand rule in electronagenism.

So, specifying a non-planar triple of vectors specifies one of two possible orientations of space.

If the translation $f$ transforms a selected vector triple into a triple of the same sign (it can be proven that it then preserves the sign of either triple!), we will say that it preserves orientation; otherwise we will naturally

Fig. 2.
Fig. 3.
Fig. 4.

Fig. 5.

⟦folio 4⟧

Fig. 6.

say that moving $f$ changes orientation.

For example, parallel translation and rotation around a line (in particular, axial symmetry) preserve orientation, while central symmetry and symmetry relative to a plane change it (Fig. 5).

I don’t want to mislead you: everything is not that simple here. For example, the complex order “counterclockwise” and “the shortest rotation... for an observer finding...” (see above) do not, strictly speaking, have any mathematical meaning - they cannot be defined within the framework of school akinomatics of geometry (and in other akinomatics known to the author).

In fact, it is possible to strictly define equally and oppositely oriented “circles with an arrow” or triples of vectors, but formally one cannot give preference to one of the types of circles or triples. Further, without proof, we butt one non-trivial fact: a move that preserves the orientation of one triple cannot place the orientation of the other. A detailed discussion of these issues would take us too far: visual clarity is enough for us to proceed further.

Composition of movements

The composition of the mapping $f$, $g$ (in particular, displacements) is called the mapping $h = g \circ f$, which is obtained by sequentially performing first $f$ and then $g$; this means that for any point $A$

$$h(A) = g(f(A)).$$

Note the order in the $g \circ f$ entry: $f$ is executed first, then $g$. This entry is completely natural, since according to formula (2)

$$(g \circ f)(A) = g(f(A)).$$

It is easy to see that the composition of displacements is displacement (this is instantly obtained if you apply (1) twice). Let's see what displacements are obtained if we take compositions of displacements known to us. I will start with very simple examples that you can easily understand by looking at the corresponding drawings. But there is little visual understanding here - you need to check the evidence (however, there are a lot of processes).

1°. The composition of two symmetrical relatively parallel planes is a parallel translation (Fig. 6 a).

2°. Composition of two symmetrical relatively intersecting planes - rotation around circles of their intersection line (Fig. 6 b).

3°. The composition of three symmetrical relative to three mutually perpendicular planes is symmetry relative to their common point (Fig. 6 in).

4°. The composition of symmetrical relative to a plane and the transfer to a vector perpendicular to it is symmetry relative to (another) plane.

⟦folio 5⟧

Fig. 7.

In these examples, the composition resulted in displacements previously known to us. But this, of course, is not always the case - for example, moving

$$W_{l,\vec{a}}^{\varphi} = \vec{a} \circ R_{l,\varphi},$$

where the vector $\vec{a}$ is parallel to the line $l$, we have not yet encountered; $W_{l,\vec{a}}^{\varphi}$ is called helical movement (with axis $l$, angle $\varphi$ and vector $\vec{a}$); it will play a major role in the further story ZE (Fig. 7).

It is clear that for $\vec{a} \parallel l$

$$\vec{a} \circ R_{l,\varphi} = R_{l,\varphi} \circ a.$$ (3)

It is also obvious that the composition of a screw movement and a displacement on a vector parallel to the rotation axis will again be a screw movement with the same rotation axis, but with a different displacement vector (equal to the sum of the old displacement and the new one). But the following fact is not very interesting at all:

$$5^\circ. \text{Композиция поворота } R_{l,\varphi} \text{ и произвольного перемещения } c \text{ является винтовым перемещением } c \text{ осью } l' \parallel l \text{ на угол } \varphi.$$

We will need this statement soon; let's prove it. For this purpose, we decompose the vector $c$ into the sum $\vec{c} = \vec{c}_1 + \vec{c}_2$, where the vector $\vec{c}_1$ is directed along the $l$ axis, and $\vec{c}_2$ is perpendicular to this axis. The composition of parallel translations corresponds to the sum of vectors, therefore $\vec{c} = \vec{c}_2 \circ \vec{c}_1$, hence by virtue of (3)

Fig. 8.

$$\vec{c} \circ R_{l,\varphi} = (\vec{c}_2 \circ \vec{c}_1) \circ R_{l,\varphi} = \vec{c}_2 \circ (\vec{c}_1 \circ R_{l,\varphi}) = \vec{c}_2 \circ (R_{l,\varphi} \circ \vec{c}_1) = (\vec{c}_2 \circ R_{l,\varphi}) \circ \vec{c}_1.$$ (4)

Will move $\vec{c}_2 \circ R_{l,\varphi}$, remembering that $\vec{c}_2 \perp l$. Consider an arbitrary plane $l$ (Fig. 8). On this plane, the displacement $\vec{c}_2 \circ R_{l,\varphi}$ is a composition of the rotation of the plane $R_{0}^{\varphi}$ (where $O = l \cap \pi$) and the transfer of the plane to the vector $\vec{c}_2$ (after all, $\vec{c}_2 \perp l \Rightarrow \vec{c}_2 \parallel \pi$). Such a composition will be («Kvant», 1980, no. 3, p. 6) a rotation by the same angle $\varphi$ around a new center $O'$, which is easy to construct (see Fig. 8, where $[OA] \rightarrow [AA']$). The same picture is observed in all planes perpendicular to $l$, so that

$$\vec{c}_2 \circ R_{l,\varphi} = R_{l,\varphi},$$

where $l'$ is a line passing through $O'$ parallel to $l$. From (4), taking into account $\vec{c}_1 \parallel l$, we obtain

$$\vec{c} \circ R_{l,\varphi} = (\vec{c}_2 \circ R_{l,\varphi}) \circ \vec{c}_1 = R_{l,\varphi} \circ \vec{c}_1 = \vec{c}_1 \cdot R_{l,\varphi} = W_{l,\varphi} \cdot \vec{c}_1.$$

Geometrically, such a statement is even less obvious:

$$6^\circ. \text{Композиция винтового перемещения } W_{l,\varphi} \text{ и произвольного перемещения } c \text{ осью, параллельной прямой } l, \text{ на угол } \varphi.$$

However, this fact can be proven in two ways:

$$\vec{c} \circ W_{l,\varphi} = \vec{c} \circ (\vec{a} \circ R_{l,\varphi}) = (\vec{c} \circ \vec{a}) \circ R_{l,\varphi} = W_{l,\varphi} \cdot \vec{c}_1,$$
