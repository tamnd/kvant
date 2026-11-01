---
id: 1980-12-zalgaller-zalgaller-vengerskiy-sharnirnyiy-kubik-be0d1cc1
issue: kvant_1980_12
year: 1980
number: "12"
title: Hungarian hinged cube
authors:
  - Залгаллер В. А.
  - Залгаллер С. И.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 19
page_last: 22
page_labels: 17, 18, 20
tag: D22T
lang: en
source: kvant_digital
extraction: vision
content_sha256: 5236cac4b9da122d1cc0d42899baf24230b366901253cd08bbc6c6222004342e
prompt_sha256: draft-1
translated_from: content/ru/1980/12/articles/08_zalgaller-zalgaller-vengerskiy-sharnirnyiy-kubik-be0d1cc1.md
source_content_sha256: b6567d5ea7802a05f85e44fd6b1694a2e91640f80742d468070cc03f2312675a
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 17⟧

The hobby of mathematical puzzles, created in 1975 by the Hungarian architect, Professor Ernő Rubik, is spreading in the Hungarian People's Republic. Its appearance is shown on the fourth page of the cover: it is a plastic cube divided into 27 congested cubes. The inner cube is removed, and the 26 outer cubes are interlocked using special protrusions so that any tile of the 9 cubes adjacent to one side of the cube can be rotated 90° in any direction. (The beginning of two such rotations is shown at figure 1.) After a rotation of 90°, the entire system retains the same freedom of rotation: again, any tile in any direction can be rotated in its plane by 90°.

A separate article can be written about the hinge design of these cups - now we will discuss another issue.

Initially, each of the faces of the large cube was painted a different color (red, orange, yellow, green, blue, white). After a series of randomly selected rotations, the color of the cube's faces becomes variegated: there are cells of different colors on the edge. The puzzle is that, having received such a colorful cube in your hands, add, using rotations, the *correct* arrangement of cubes, that is, such an arrangement in which each face of the cube will again be the same color.

This task is not at all easy. A person not armed with a theory, even a capable one, rarely manages to immediately collect more than one facet. The number of cube arrangements that can be obtained (it is estimated that there are $N=43\ 252\ 003\ 274\ 489\ 856\ 000$) makes it inaccessible to brute force even on a computer. Note, however, that not any arrangement can be obtained by rotating the cube tiles: if you allow the cube to be disassembled into its 26 cubes, then you can create $12 \cdot N=529\ 024\ 039\ 393\ 878\ 272\ 000$ different arrangements (see Problem 8 from the Appendix).

Currently, we offer the reader rules (they are not the most economical in terms of the number of rotations) that allow any of the $N$ possible arrangements of cubes to be returned to their correct arrangement.

Description of rotations

To outline the proposed rules, terms and conditions first about terminology.

We will call *central* the cubes that stand in the centers of the faces of the cube. Each central cube is always central and faces outwards from one square of the designated color.

Since we are not interested in changes in the position of the entire cube in space, but only in changes in the relative position of its part, we will consider its position in space to be fixed. It means:

Fig. 1.

⟦folio 18⟧

It means that the position of all central cups in space remains unchanged. This also means that out of the nine planes of the cube we will rotate only six.

If on figure a certain central cell is offset by the letter $A$, then we will denote the rotation of the (not “middle”) tile containing this cell by $90^\circ$ clockwise by $A$, and the rotation of the same tile by $90^\circ$ counterclockwise will be denoted by $A^{-1}$. Obviously, $A^{-1}A^{-1}A^{-1}=A$ and $A^2=A^{-2}$, where $A^2=A$ and $A^{-2}=A^{-1}$ $A^{-1}$.

The cubes containing the middle part of the edge of a large cube will be called medium. The middle cube always remains medium and faces outward with two cells of the defining color. For each pair of colors (except for those pairs of colors that were originally painted on opposite sides of the cube) there is a single middle cube with cells of these colors.

Uel cubes are cubes that occupy corner positions within a cube. Each corner cube always remains a corner cube and faces outward to a third square surrounded by different colors. The correspondence of these three colors is different for each of the corner cups.

Main stages

A tempting, at first glance, path: gradually increasing the spot of single-bar cells, obtaining a single-bar edge, and then taking another - apparently only leads to insurmountable difficulties. Not being able to compare with the puzzle, they will tear it apart - out of anger or out of curiosity about the structure of the hinge. We are on

We hope that the solution proposed below will make the puzzle accessible, but it also requires certain conditions for implementation.

We will divide the proposed actions into four large stages. We have already agreed that while solving the puzzle, the central cubes do not change their position in space. As for the middle cups, each of them must take a certain place in the wave during the solution: appear on the edge between two “own” faces of the cube, that is, those faces whose central cells are the same color as the two cells of the given middle cube. In addition, it must be rotated correctly: its colored cells must be adjacent to the central cells of the same color. The situation is completely similar with the corner cups: each of them has its own place (at the junction of three faces with the central cells of its colors) and a single correct turn. In accordance with this, our procedure will be as follows:

1. Place all the middle cubes in the right places.
2. Rotate all the middle cubes correctly in their places.
3. Place all the corner cubes in the right places.
4. Rotate all corner cubes correctly.

We will perform each stage only after the previous stage is completely completed. At the same time, we will perform the next stage in such a way that after its completion we will not be disrupted by the achievements of the previous stages.

⟦folio 20⟧

Obviously, pairwise permutations of the middle cubes allow us to carry out stage 1: put all the middle cubes in their place.

Stage 2: Rotate the middle cubes

Twelve twist combination
$$K_2 = (AB^{-1}A^{-1}B)(BC^{-1}B^{-1}C)(CA^{-1}C^{-1}A)$$
simultaneously rotates cubes 1, 2 (Fig. 4) in their nests and does not change either the location or rotation of the remaining middle cubes (check!).

The combination $K_2$ allows you to rotate any two middle cubes in their places. Indeed, if they were not adjacent to the same edge or were not adjacent to it, then you can always use auxiliary turns (remember these turns by the color of the center of the tile being rotated) to bring the desired two cubes to position 1, 2 (Fig. 4), rotate them with the combination $K_2$, and then, in the reverse order and in the opposite directions, turn the auxiliary turns.

Pairwise joint rotations of the middle cubes make it possible to carry out stage 2, since (due to property 1) it cannot be the case that only one middle cube requires rotation.

Stage 3: corner cubes - in place

Twelve twist combination
$$K_3 = (ABA^{-1}B^{-1})^3$$
performs simultaneous rearrangements of cubes 1, 2 and cubes 3, 4 (Fig. 5), preserves all achievements of stages 1, 2 and does not change the location of corner cubes other than 1, 2, 3, 4 (check!)

Combination of twelve four turns
$$K_4 = (ACA^{-1}C^{-1})^3(B^{-1}A^{-1}BA)^3$$
rearranges cubes 1, 2, 3 (Fig. 6) according to scheme $1 \rightarrow 2 \rightarrow 3 \rightarrow 1$, retains all achievements of stages 1, 2 and does not change the location of corner cubes other than 1, 2, 3.

Let us explain how to use the combinations $K_3$ and $K_4$ to carry out stage 3.

Let's say that after completing stage 2, some of the corner cubes are not in their places. Due to property P, there will be at least three such cubes. Let's choose one of them and mark it with number 1. The cube that occupies the place where cube 1 should go will be marked with number 2.

If cube 2 itself should move to the place of cube 1, then with number 3 we will mark any corner cube different from the first two and standing out of place, and with number 4 - the cube standing where cube 3 should go. Then, using auxiliary rotations (remember them), we will place cubes 1, 2 and 3, 4 in the position of pairs 1, 2, and 3, 4, shown on figure 5. Using the combination $K_3$ we will carry out the rearrangement $1 \rightarrow 2, 3 \rightarrow 4$, after which in reverse order and reverse intentional turns.

As a result, in addition to the corner cubes previously standing in their places, the rotation of cubes 1, 2, 3 into their place was completed.

If cube 2 was not supposed to go to the place of cube 1, then we mark with number 3 the cube standing where cube 2 should go. If cube 3 should not go to the place of cube 1, then we mark with number 4 the cube standing where cube 3 should go. After this, as above, that is, with the help of auxiliary rotations and the combination $K_3$, a rearrangement of $1 \rightarrow 2, 3 \rightarrow 4$ is carried out, which puts it in its place cubes 1 and 3.

There remains a case where a rearrangement of the cubes $1 \rightarrow 2 \rightarrow 3 \rightarrow 1$ is required. In this case, with the help of auxiliary turns (remember them), we put cubes 1, 2, 3 in some order in place of 1, 2, 3 (Fig. 6). However, of the two combinations $K_4, K_4^{-1}$, which perform rearrangements of places $1 \rightarrow 2 \rightarrow 3 \rightarrow 1, 1 \rightarrow 3 \rightarrow 2 \rightarrow 1$, will perform the rearrangement of cubes $1 \rightarrow 2 \rightarrow 3 \rightarrow 1$ (located in places 1, 2, 3). Let's do this exact combination. After this, we will turn the auxiliary turns in the reverse order and in the opposite directions. As a result, cubes 1, 2, 3 will fall into place.

Repeating this process, we will complete step 3 - we will put all the corner cubes in their place.

Stage 4: Rotate the corner cubes

We will need the following two combinations:
$$K_5 = [(A^{-1}CAC^{-1})(C^{-1}BCB^{-1})(B^{-1}ABA^{-1})]^2, K_5^{-1} = [(AB^{-1}A^{-1}B)(BC^{-1}B^{-1}B)(BA^{-1}B^{-1}A)]^2.$$

The combination $K_5$ simultaneously rotates each of the cubes 1, 2, 3 (Fig. 7) of the set going from its center to the center of the cube. 120° clockwise. The combination $K_5^{-1}$ rotates the same cubes counterclockwise. The location and rotation of any of the other cubes does not change.

Knowing the combination of $K_5$ and $K_5^{-1}$ allows you to jointly turn in the desired direction (but in the same direction) or three corner cubes. It is enough to collect them using auxiliary turns into one face, rotate them together using the combination $K_5$ or $K_5^{-1}$ (depending on the desired direction of rotation), and then return them to their place with turns inverse to the auxiliary ones.

Let us now explain how to use the combinations $K_5$ and $K_5^{-1}$ to carry out step 4.

If after completing stage 3 there are incorrectly turned corner cubes, then, due to property III, there are at least two such cubes.

Let's say there are more than two. Let's take any three of them. At least two of these three dice require turning in the same direction. Rotate all three cubes in this direction, we will reduce the number of incorrectly rotated cubes. So we will come to a situation where it is either wrong to turn the cubes, or exactly two.
