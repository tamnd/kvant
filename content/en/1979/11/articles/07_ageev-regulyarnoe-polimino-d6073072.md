---
id: 1979-11-ageev-regulyarnoe-polimino-d6073072
issue: kvant_1979_11
year: 1979
number: "11"
title: Regular polyomino
authors:
  - Агеев С.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 24
page_last: 25
page_labels: 22-23
tag: M9AE
lang: en
source: kvant_digital
extraction: vision
content_sha256: 4d57fb12591422044eccdd975024a68453453d0b17fe091a82c3d78268abc648
prompt_sha256: draft-1
translated_from: content/ru/1979/11/articles/07_ageev-regulyarnoe-polimino-d6073072.md
source_content_sha256: d3784751c4e17d6ad3ca507554fc80178332cd07b516a57a9a148883a22d4dd7
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 22⟧

S. Adeev

Regular polyomino

The name of S. V. Golomb, an American scientist, specialist in the field of information theory and statistics, is well known to fans of entertaining mathematics. Golomb invented a remarkable series of games, which he gave the general name "polyominoes". This game has been the subject of many publications in a variety of magazines. «Kvant» also repeatedly addressed this topic, and in 1975, the Mir publishing house published a book by the author of this invention, containing many beautiful and entertaining mathematical problems *).

Here is an example of a “polyominoic” problem (it was placed in one of the numbers «Kvant»): Prove that from three corners and the corresponding number of tiles, but it is extremely difficult to prove. As a rule, such problems cannot be explored by the brute-force method even on a fast computer. Therefore, very ingenious methods are used to solve them. One of them, mainly on coloring pages, is described in «Kvant» No. 11 for 1972. In this article we will talk about a completely different approach related to... geography and dice.

Geography on checkered paper and dice

All further events in our article will take place on checkered paper marked with “geographical orientation” (Fig. 2). On this checkered paper we will roll, according to certain rules, an ordinary dice - a cube with an edge of unit length and numbered faces. The cube will always be positioned on the paper so that the center of its bottom edge coincides with the grid node, and the side edges are parallel to the grid lines. For each position of the cube on the checkered paper we will assign two numbers - the numbers of the southern and upper faces. Let's define this pair of numbers by the orientation of the cube.

Exercise 1. How many different orientations of the cube are there?

Let a path Γ be given connecting nodes A and B of the grid. We, of course, will consider paths that are Indian only along grid lines. If the cube is on node A, then it can be

*) “Polymino” (M., “Mir”, 1975)

Fig. 1.

Fig. 2.

⟦folio 23⟧

roll along path Γ to node B (Fig. 3). In this case, its initial orientation α will be replaced by some orientation β. We will write this as follows: β = Γ(α).

Y softening 2. Let nodes A and B and initial orientation α be fixed. Prove that by rolling a cube along all possible paths from A to B, you can obtain no more than half the orientation of the cube. Make sure that useful orientation is always available.

If the end of the path Γ₁ coincides with the beginning of the path Γ₂, then a path Γ₂°Γ₁ arises, composed of these two paths (Fig. 4). In addition, for each path Γ a “reverse” path Γ⁻¹ is naturally defined, which is obtained by replacing the direction along the path Γ with the opposite one. It is easy to verify (do this) that (Γ₂°Γ₁)(α) = Γ₂(Γ₁(α)) and Γ⁻¹(Γ(α)) = α.

We call a path Γ rezular if Γ(α) = α for some orientation α.

Y softening 3. Prove that a) if Γ is a regular path, then Γ(β) = β for any orientation β;
b) if Γ is a regular path, then Γ⁻¹ is a regular path;
c) if Γ₁ and Γ₂ are regular paths and the path Γ₂°Γ₁ is defined, then Γ₂°Γ₁ is a regular path.

4. Prove that every regular path has even length, and give an example of a non-resular path of even length.

Regular polynomial

Now let's return to polynomials. Recall that a polymno is a multi-

year, a square made up of single-cell squares, with any square adjacent to at least one adjacent one on the side (that is, a chess rook can move from any cell polymically to any other). The general problem from polymno theory is formulated as follows: is it possible to add a given figure from a given set of polymnos? We will be able to solve a whole class of such problems. We will consider a polynom as a polygon drawn on our checkered paper. We are polyminoregular at a node A if the path searching along its contour with its beginning and end at a node A lying on this contour is regular. It turns out that this definition does not depend on the selected node.

The dilution is 5. If a polymnoy is regular at some node of its contour, then it is regular at any other node. Prove it.

Exercise 5 gives us the opportunity to talk simply about regular polynomials. Several such polynomials are given on figure 5.

U dilution 6. Prove that these polymnoids are regular.

It turns out that you cannot use a non-regular polymno from regular polymnoes. To verify this, it is enough to prove the following:

Sum theorem. If the polynomial P and Q are rezular and the polymno T is composed of them, then it can be rezular.

Explanations for the proof of this theorem are given on figure 6.

It is also possible to prove the difference theorem: if a polynomial T, composed of a polynomial P and Q, is rezular and the polymno P is rezular, then the polymno Q is also rezular.

Y dilution 7. Prove the theorem about the polymnoid difference.

Y dilation 8. Prove that a rectangular polynomial is regular if and only if its area is a multiple of four.

From the sum theorem and exercises 6 and 8, the solution to a problem similar to the problem about knots immediately follows: to prove that from any number of polynomials given on figure 5, it is impossible to add a rectangle with an area not a multiple of four.
