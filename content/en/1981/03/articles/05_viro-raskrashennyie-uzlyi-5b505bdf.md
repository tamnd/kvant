---
id: 1981-3-viro-raskrashennyie-uzlyi-5b505bdf
issue: kvant_1981_3
year: 1981
number: "3"
title: Colored knots
authors:
  - Виро О. Я.
rubric: osnovnye-stati
page_first: 10
page_last: 15
page_labels: 8-13
tag: CTPE
lang: en
source: kvant_digital
extraction: vision
content_sha256: 03caf1ecc519d4c9f516e42b9ca2f90cfe8829d721d9eb0e9c9c1f370a40c2ac
prompt_sha256: draft-1
translated_from: content/ru/1981/03/articles/05_viro-raskrashennyie-uzlyi-5b505bdf.md
source_content_sha256: 22a7b8cecbfe32604d93ccc615c4a821d28ae388c484bab0b0733a4fc6a9c99c
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 8⟧

O. Viro

Colored knots

What is a node
When dealing with a real-life subject, mathematicians usually replace it with a suitable mathematical object. The rope knot did not escape this fate either - it was turned into a mathematical knot.

The prototype of a mathematical knot is a knotted piece of rope with its ends secured.

One of the questions that prompted mathematicians to take up knots was the question of which knots can be undone without breaking, and which cannot.

The ends of the rope come to be secured, because if you do not prevent them from being manipulated, all the knots will end up tied equally (in fact, any knot on a rope can be untied by pulling the end of the rope one by one through the loops of the knot).

A more convenient way to take the hassle out of worrying about the ends of the rope is to connect them together. This operation is shown in figure 1. As a result, a piece of rope is transformed into a knotted ring.

The next step to a mathematical knot is to replace the rope with lines - the axis of the rope.

Not every line can be the axis of a rope. For example, a curve with an infinite sequence of infinite killing knots (Fig. 2) cannot be “increased” to a rope of finite thickness. Curves of this kind are considered in mathematics; these are called wild nodes.

We will not deal with wild nodes here and, in order to exclude them, we will use the following definition: a polygonal node is a closed, connected spatial broken line that does not have self-intersection points, composed of a finite number of straight segments.

This definition is quite consistent with our visual representation of nodes. Any polygonal knot can be extended to a rope loop, and in any rope loop you can find an axis, a co-

⟦folio 9⟧

made from a finite number of segments.

The word “connected” in the definition of a polygonal node means that the broken line is not represented as a union of several closed broken lines. If you don't make the connection, you will get a definition of a polygonal linkage. figure 3 shows polygonal knots, and figure 4 shows polygonal links that are not knots.

Since in this article all nodes and links will be polygonal, the word “polygonal” will be omitted for brevity.

How to write a node

When depicting a node, choose an observation point such that, firstly, the node lies on one side of a certain plane passing through this point, and, secondly, so that no three links of the node seem to pass through one point. The fulfillment of the first condition can be achieved by choosing an observation point far from the node. From a point that satisfies these conditions, the scales can be projected onto a plane, that is, as if to take in the whole space with one’s gaze. To satisfy the second condition, it is necessary that any straight line passing through the observation point define no more than two node links. The fulfillment of this condition can be achieved by an arbitrarily small shift of the observation point.

In the place where the images of two non-intersecting links of a node intersect, you need to indicate which link is close and which is further. To do this, the image of the distant link is redrawn, as was done in Figures 3 and 4.

A picture of a knot made in accordance with these rules is called a “knot design.”

What does “equally meshed” knots mean?

Rope pegs, which are formed from each other as a result of bending, stretching, skating and other continuous deformations, naturally

but consider “equally geared”. This visual representation of the same linkage when moving to polygonal nodes turns into the concept of isotopy: two nodes (or, more generally, two links) are called isotopic if one can move from one to the other by sequentially performing transformations that are called elementary isotopes. Elementary isotopy is either the replacement of one of the links of a knot with two new segments, which together form the contour of a triangle, intersecting with a straight knot only along the replaced link*), or the inverse operation - replacing two adjacent links with one segment, which together with them forms the contour of a triangle, intersecting with a straight knot only along the replaced links. figure 5 shows two nodes obtained from each other by elementary isotopy.

*) These “two new segments”, together with the replaced link, can form a “degenerate” triangle - a segment. In this case, the elementary isotopy indicates the addition of a new vertex inside the link.

⟦folio 10⟧

Fig. 5.

The triangle involved in determining the elementary isotopy must be perceived as a deformation trajectory.

Exercise 1. Prove that nodes with the same isotope diagrams.

A node, an isotopic contour of a triangle, is called trivial. The nodes shown in figure 5 are trivial. The sequence of elementary isotopies connecting them to the outline of the triangle is shown in figure 6.

It is clear that the contours of any two triangles are isotopic, so all trivial nodes are isotopic to each other. However, trivial nodes can be quite complex.

Exercises

2. Prove the triviality of the knots shown in figure 7.
3. Prove that the nodes shown in Figures 3a and 3b are isotopes.

How to prove that nodes are non-isotopic

The definition of isotopicity immediately confronts us with a gap: are there non-isotopic nodes?

Until we can answer this question, all nodes will look the same to us.

We know that very intricate knots can turn out to be trivial

Fig. 6.

Fig. 7.

10

⟦folio 11⟧

Fig. 8.

However, the introduction of these and many similar invariants does not help solve old questions, but leads to the formulation of new ones. The point is that calculating these invariants causes the same difficulties as proving a nontrivial knot.

The only thing that can help in proving a non-trivial node is an easily computational invariant, which is determined not through a whole class of isotopic nodes, but directly from the node diagram. We will now introduce such an invariant.

Coloring node diagrams in three colors

Let me remind you that the diagram of a node is its image on a plane, in which the images of no three links pass through one and in places where the images of non-intersecting links should intersect, the image of the further link is overextended. Because of these changes, the knot diagram turns out to be composed of several non-intersecting broken lines. We will call these broken lines sections of the diagram. Their number is equal to the number of transitions, that is, the number of crossings.

To prove the nonisotopic nature of nodes, it turns out to be useful to color their diagrams, following certain rules.

We will call the coloring of a node diagram in black, red and blue colors correct if each of its sections is painted in one color and near each crossing point either all three sections are painted in the same color or all three colors occur. Examples of correct coloring are shown at figure 9, examples of incorrect coloring are shown at figure 10.

Exercises

4. Prove that the node diagrams shown in Figures 6 and 7 cannot be correctly colored using all three colors, that is, prove that these diagrams admit only three mono-nominal colorings.

5. Prove that the number of correct colorings of the trefoil (Fig. 8,6) is nine.

Theorem 1 (Main theorem on three-color colorings). The number of correct colorings of a node's diagram in three colors is an invariant of the node.

Before proving Theorem 1, let us discuss some of its applications. Here is the simplest corollary:

Corollary 1. If the node diagram admits a correct coloring, the section in question is trivalny.

This corollary immediately allows us to solve the problem formulated in Exercise 4 (the nodes discussed there are trivalny). But what is immeasurably more important is that a non-trivial trefoil and many other nodes flow from it.

Fig. 9.

Fig. 10.

⟦folio 12⟧

Comment. If the target diagram does not allow for correct coloring, in which more than one color would be present, then the target cannot be evaluated (that is, it is not isotopic to any target consisting of nodes that are located on opposite sides of the neotopic plane).

Pravanke has 8. Prove that the targets shown on figure 4 are not considered.

How to prove Theorem 1

Theorem 1 follows very closely from the following two theorems, the proofs of which are simple, but rather cumbersome; applications, the reader will undoubtedly find them on his own.

Theorem 2. Any elementary healing isotopy can be replaced by a finite sequence of elematrine isotopies, each of which changes the healing diagram in one of the ways depicted in figure 11.

For example, the elementary isotopy shown in figure 12 can be replaced by a sequence of elematrine isotopes shown in figure 13 (the numbers indicate the order in which the elematrine isotopies are performed).

Theorem 3. Between the regular three-color colorings of diagrams resulting from each other, the operations depicted in figure 11, there is a one-to-one correspondence in which, according to their colorings, the unchanging parts of the diagrams are colored identically.

For all operations except the operation depicted in figure 11, 3, the statement of Theorem 3 is very strong. In the latter case, the proof easily reduces to the pictures shown in figure 14.

Why is the number of correct colorings of a diagram an invariant of a node?

I hope that the reader has proven Theorems 2 and 3, and with them Theorem 1. However, what is the answer to the question posed in the title of this paragraph?

You are convinced of the invariance of the number of correct colorings, but,

⟦folio 13⟧

You will probably say that you would like to know about the real reasons for this amazing phenomenon. You want an explanation and want to understand how mathematicians should color knot diagrams. Besides, this proof could not be the first proof! This way you can prove the invariance of any invariant determined by a node diagram, without completely understanding where it came from! After all, it is not clear why it is necessary to paint in three colors and how the coloring rules arose. Finally, it is not clear how to generalize this, and this is a sure sign of misunderstanding.

Why did I choose this path of proof? There were two reasons for this. First, the real proof of Theorem 1, which clarifies the essence of the matter, involves complex auxiliary objects, which occupy a place of honor in modern mathematics, but which are not found in school mathematics. I wanted to present a purely elementary proof of the existence of non-trivial nodes. There was no such evidence in the literature, and especially in popular literature. Secondly, based on Theorem 2, the real one can prove the invariance of any invariant determined from the diagram. Try to come up with a completely new invariant and prove its invariance in this way. If it works, please let me know, it could be very interesting! There are many known invariants defined by a knot diagram, but most of them defined contain non-elementary mathematical concepts. Therefore, the danger of inventing something known is not great.

What actually explains the invariance of the number of correct colorings? The most important invariant of a node is its group. The node group itself is not a simple object. This is a set in which an operation is defined that fills the addition of integers with connections and properties. Proving that two node groups are different can be very difficult. However, the simplest way to do this is to study
